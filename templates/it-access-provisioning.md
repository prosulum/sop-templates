# IT Access Provisioning

Updated September 28, 2026

The IT admin runs this one sequence for three kinds of request: a new hire, a role change, and an ad hoc access request. It starts when a written request with the requesting manager's approval arrives, and it ends when the grant is logged and the requester has confirmed their logins. Each step says what differs by request type, including removing the old role's access on a role change. It uses a role-based access matrix and least-privilege defaults, so IT can act on a clear, approved request without guessing what a role needs.

**Primary owner:** IT admin  
**Runs:** Every approved new-hire request, role change, or ad hoc access request  
**Time:** 1 to 2 hours of setup per new hire; 15 to 30 minutes for most ad hoc requests

## Before you start

- A documented role-based access matrix defining default access per role
- Single sign-on (SSO) through [your identity provider], covering as many core systems as possible, with MFA enforced
- An access request and approval workflow ([your request form or ticketing system]) with one form or ticket type each for a new hire, a role change, and an ad hoc request, not verbal or hallway requests
- A current access registry showing who has access to what
- The name of the [exception approver role, e.g. IT lead] and the [backup approver role], and the response time for each, [N] business hours
- A device management (MDM) process for company hardware, [your device management tool], if applicable
- Access reviews run as their own routine on [your access review cadence, e.g. quarterly] and are not part of this sequence

## Procedure

1. **Receive the request and confirm it is approved** (Owner: IT admin)

   - **a.** Open the request and mark its type on the ticket: new hire, role change, or ad hoc. Every later step says what differs by type.
   - **b.** Confirm the approver's approval is recorded on the request (a status or a signature), and that the approver is the requester's manager or the [backup approver role].
   - **c.** If the request is not approved, do not provision. Send the return message below, set the ticket to "awaiting approval", and stop. If the approver denies it, record the denial on the ticket, tell the requester, and stop.
   - **d.** If the approver has not answered within [N] business hours, send the request to the [backup approver role]. If neither answers within [N] more business hours, tell the requester the request is on hold and keep the ticket open.
   - **e.** New hire: confirm start date, role, department, and reporting manager. Role change: confirm the old role, the new role, and the effective date. Ad hoc: confirm the specific system, the reason, and whether it is temporary or standing.

   > **Use this wording: Return message when a request is not approved**
   > 
   > Hi [requester name], I cannot start on your request [ticket number] yet because it has no recorded approval from [approver name]. Please ask them to approve it in [request form or ticketing system]. I will pick it up as soon as I see the approval.

   *Why this matters:* Provisioning off a verbal request or a hallway conversation is how access sprawl happens. A written, approved request is the first control in the chain.

2. **Apply the role-based access matrix, not an ad hoc list** (Owner: IT admin)

   - **a.** New hire: look up the new role's default access in the matrix. Role change: look up both the old role and the new role. Ad hoc: look up whether the matrix already gives the requested system to the requester's role.
   - **b.** Grant only what the matrix specifies for the role. This is the least-privilege default, not a starting point to negotiate up from.
   - **c.** If the request asks for access beyond the role's default, treat it as an exception: write the business reason on the ticket and send it to the [exception approver role].
   - **d.** If the exception approver approves, record the approver and the reason on the ticket and go on to step 3.
   - **e.** If the approver denies it, tell the requester and the requesting manager and record the denial on the ticket. Then go to step 3 with the matrix defaults only. If the whole request was the exception (a typical ad hoc request), there is nothing to grant, so go to step 8 to log the denial.
   - **f.** If the exception approver has not answered within [N] business hours, tell the requester the exception is on hold, grant the matrix defaults only, and go to step 3.

   *Why this matters:* Least privilege means starting minimal and expanding only on documented justification. A role-based matrix keeps that consistent instead of dependent on who asks loudest.

3. **Create or confirm the account through SSO** (Owner: IT admin)

   - **a.** New hire: create the identity in [your identity provider] first, because it is the fastest way to grant or revoke access to every connected system at once.
   - **b.** Role change or ad hoc: confirm the person's existing identity is active in [your identity provider] and the department, title, and manager fields match the request.
   - **c.** Confirm MFA enrollment in the admin console of [your identity provider] and write the enrollment status and date on the ticket. Grant nothing until it shows enrolled. If it does not, tell the requester to enroll and hold the request.
   - **d.** For systems not connected to SSO, create individual accounts and log each one in the access registry so it is not missed later.

   *Why this matters:* Centralizing identity through SSO (one login that opens your other tools) with MFA (a second check at sign-in) enforced makes both provisioning and, later, offboarding fast and reliable instead of a scavenger hunt across every tool.

4. **Grant system-specific permissions at the least-privilege level** (Owner: IT admin)

   - **a.** In each system (your CRM, billing, cloud storage, admin panels), set the permission level, not just whether the account exists, per the access matrix and any approved exception.
   - **b.** Default to read or standard-user permissions unless the role specifically requires admin or write access to that system.
   - **c.** For temporary ad hoc access, set an expiry of [N] days (e.g. 30) or the end date the approver gave, whichever is sooner, and write it on the ticket.
   - **d.** Log every grant in the access registry with the date, system, permission level, expiry if any, and who approved it.

   *Why this matters:* An account that exists but has the wrong permission level is still a gap, either blocking legitimate work or exposing more than the role needs.

5. **Remove access the old role no longer needs (role change only)** (Owner: IT admin)

   - **a.** New hire or ad hoc: skip this step and go to step 6.
   - **b.** Compare the old role's matrix defaults to the new role's. List every system and permission the old role has that the new role does not.
   - **c.** Remove each one on the effective date, and write the removal date and your initials on the ticket.
   - **d.** If the manager asks to keep an old-role access for a handover, treat it as a temporary ad hoc exception: send it to the [exception approver role] as in step 2, give it an expiry of [N] days, and log it.
   - **e.** Open each affected system's user list and confirm the person's access shows the change, then update the access registry to match.

   *Why this matters:* Without this step a role change only adds access, and over the years a person collects every permission they have ever had. Removing the old role's access keeps least privilege true.

6. **Set up hardware and remote access** (Owner: IT admin)

   - **a.** Ad hoc requests that need no new device: skip this step and go to step 7.
   - **b.** For in-office roles, image and prepare the workstation with the required software before the start date or effective date.
   - **c.** For remote roles, configure [your VPN or remote access method] and confirm the required tools are reachable from outside the office network.
   - **d.** Enroll company hardware in [your device management tool] so it can be locked or wiped if lost, or at offboarding.

   *Why this matters:* Hardware and remote access are easy to leave until last and can block a new hire's first morning if they are skipped.

7. **Send the access guide and confirm logins before they are needed** (Owner: IT admin)

   - **a.** Send the access guide below, covering how to log in to each system, where documentation lives, and who to contact for IT help.
   - **b.** Ask the new hire, the person whose role changed, or the ad hoc requester to log in to every granted system and reply with the result before the start date, effective date, or need date.
   - **c.** If a login fails, fix it now. If you have not fixed it within [N] business hours, tell the requester's manager and keep the ticket open.
   - **d.** If no confirmation arrives within [N] business days, send one follow-up. If there is still none, write "logins unconfirmed" on the ticket and tell the requester's manager.

   > **Use this wording: Access guide message**
   > 
   > Hi [name], your access is ready as of [date]. You can log in to [system list] with your [identity provider] account. Guides are in [documentation location]. Please log in to each system and reply to me by [date] to tell me it works or what failed. If you get stuck, contact [IT contact].

   *Why this matters:* Confirming access works before it is needed is the difference between a smooth first day and a morning lost to password resets.

8. **Log the grant, set the review, and close the ticket** (Owner: IT admin)

   - **a.** Record the final access list in the registry: every system, permission level, grant date, expiry if any, and approver. Employee Offboarding uses this same registry to revoke everything later.
   - **b.** Write on the ticket that the grant was checked against the request: the request type, the matrix role, any approved or denied exception, the MFA status, and the login confirmation.
   - **c.** Add the new or changed access to the list for the next scheduled access review ([your access review cadence]).
   - **d.** Close the ticket only when the registry matches the systems. If it does not, fix the registry or the system now and check again.

   *Why this matters:* Access that is never reviewed again is how "temporary" turns into a permanent, forgotten security gap.

## Exceptions and troubleshooting

- **If** A new hire cannot log into a required system on day one. **Then:** Check the access registry against the role matrix to confirm the grant was completed, not only requested, and resolve the specific system's login issue immediately rather than routing them to wait.
- **If** A manager requests access beyond what the role matrix specifies. **Then:** Treat it as an exception request as in step 2: document the specific business reason, get it approved in writing by the [exception approver role], and log it as an exception rather than expanding the role's default matrix without approval.
- **If** An access review finds an account with permissions no one can explain. **Then:** Suspend the unexplained access pending investigation, trace it back to the original grant in the registry, and correct or remove it based on what you find. The review itself runs as its own routine on [your access review cadence].
- **If** SSO is down and a new hire needs access urgently. **Then:** Use [your emergency-access procedure] for the specific system, log the manual grant in the registry immediately, and revert to normal SSO-based access once it is restored.
- **If** A temporary grant reaches its expiry date. **Then:** Remove the access on the expiry date, mark the registry row removed, and tell the requester. If they still need it, they submit a new ad hoc request and it goes through step 1 again.

## Quality checklist

- [ ] Request typed as new hire, role change, or ad hoc, and provisioned only after a recorded approval from a named approver
- [ ] A request with no approval, a denial, or an unanswered approval handled as step 1 says, not provisioned
- [ ] Access granted per the documented role-based matrix, not an ad hoc list
- [ ] Any exception approved by the [exception approver role] in writing, or denied and logged
- [ ] Account created or confirmed through SSO, with MFA enrollment status written on the ticket before any grant
- [ ] Permission levels set to least privilege for each system, not default admin
- [ ] On a role change, the old role's access removed on the effective date and the user lists checked
- [ ] Every grant logged in the access registry with date, system, level, expiry if any, and approver
- [ ] Hardware and remote access configured and tested before the start date or need date
- [ ] Requester confirmed logins, or "logins unconfirmed" recorded, and the registry matches the systems

## Common mistakes

- **Mistake:** Provisioning access based on a verbal request or what the employee asks for, instead of the documented role matrix. **Fix:** Require a written, approved request, and grant exactly what the matrix specifies for that role.
- **Mistake:** Defaulting new accounts to admin or elevated permissions because it is faster than scoping them correctly. **Fix:** Default to least privilege for every system and require a separate, documented approval for anything beyond the role's baseline.
- **Mistake:** Adding the new role's access on a role change without removing the old role's. **Fix:** Run step 5 on every role change: list what the old role has that the new one does not, and remove it on the effective date.
- **Mistake:** Creating accounts outside SSO without logging them in the access registry. **Fix:** Log every account, SSO-connected or not, in the registry the moment it is created.
- **Mistake:** Granting temporary or ad hoc access with no expiration or review date. **Fix:** Set an expiry on every temporary grant at the time it is created (step 4) and log it.

## How to know it is working

- New hires and role changes are productive with full required access on their start or effective date, with every required login working.
- Every access grant in the registry traces back to an approved request and the role-based matrix.
- Every role change shows the old role's access removed on the effective date.
- Scheduled access reviews ([your access review cadence]) find zero unexplained or orphaned accounts.
- Temporary and ad hoc access grants are removed or reviewed on schedule, not left standing indefinitely.

| Metric | Target |
| --- | --- |
| New-hire access readiness (all systems working by start date) | 100% |
| Access requests provisioned from the role matrix vs. ad hoc | Track toward 100% matrix-based |
| Role changes with old-role access removed by the effective date | 100% |
| Access review findings (unexplained or orphaned access) | Zero |

## Related procedures

- Hiring Process
- Employee Offboarding
- Performance Review
- Purchase Order Approval

## Make it your procedure

1. Have the person who does this work fill in the [bracketed] parts and correct the steps. They know the details an owner skips.
2. Hand it to someone who has never done the task and watch them follow it without help. Every question they ask is a missing step. Add it.
3. When the work changes, change the procedure first, update the date under the title, and tell the people who use it what changed. Then nobody has a reason to work around it.
4. Save it with the others in one shared procedures folder, and fill in the procedure record at the bottom.

## Procedure record

- **File name and folder:** ______________________
- **Written by:** ______________________
- **Created on:** ______________________
- **Updated on:** ______________________
- **Approved by:** ______________________
- **Next review date:** ______________________

---

Template by Pro Sulum. Online version with a fillable worksheet: https://www.prosulum.com/sops/templates/it-access-provisioning/

Free to use and adapt for your own business, licensed CC BY 4.0: credit Pro Sulum (prosulum.com) if you republish it.
