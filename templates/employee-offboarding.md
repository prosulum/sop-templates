# Employee Offboarding

Updated September 28, 2026

HR runs this procedure for every employee or contractor separation, whether it is a resignation, a termination, or a layoff. It starts the day the separation is confirmed and runs in time order: log the separation, inventory access, transfer knowledge while the person is still reachable, hold the exit interview, confirm the handoff is complete before access is cut, revoke access, recover property, audit that access is gone, and close the record. Final pay goes to Payroll Processing as soon as the last day is confirmed, so it never waits on the access audit. It exists so HR, IT, and the manager can each run their piece without waiting on the others or relying on memory.

**What this gives you:** Every departure runs the same careful way, so people leave treated with respect and what you built stays secure. How someone leaves shows what your company stands for, and now you decide what it shows.

**Primary owner:** HR  
**Runs:** Every employee or contractor separation, starting the day a resignation notice is received or a termination or layoff decision is made  
**Time:** [2 to 4] hours of active work across the notice period, plus same-day access revocation on the last day (example figures, replace with your own after your first few departures)

## Before you start

- A current access registry showing every system the departing employee can reach
- A company property log (laptop, phone, keycard, and any other hardware issued at hire)
- An offboarding checklist shared between HR, IT admin, and the manager, with a revocation record (one row per system: system, date and time revoked, revoked by, checked by)
- A knowledge transfer template or handoff document, and a [shared handoff location] where finished notes are stored
- A standardized exit interview question set and a written feedback form for people who decline a live interview
- Confirmation of the separation type (resignation, termination, layoff), since it changes the order of the steps below
- Your [written policy] for accrued time off and the [benefits provider contact] for continuation notices
- Named backups for HR, IT admin, and the manager, set in the worksheet, so the checklist keeps moving if one person is out

## Procedure

1. **Confirm the separation and open the offboarding checklist** (Owner: HR)

   - **a.** Log the separation type (resignation, termination, or layoff), the last day, and the reason category on the checklist the same day the separation is confirmed.
   - **b.** Open the shared offboarding checklist and assign one owner per track: IT admin for access and property, Manager for knowledge transfer, HR for the exit interview, final pay, and the record.
   - **c.** If the separation is a resignation with notice, go to step 2 and run steps 3, 4, and 5 during the notice period. Access is revoked at [time, e.g. end of business] on the last day (step 6).
   - **d.** If the separation is a termination, a layoff, or a resignation with no notice, finish step 2 before the separation conversation. Revoke access at the start of that conversation (go to step 6), then run steps 3, 4, and 5 afterward from records, because the person no longer has access to hand anything over.
   - **e.** If a layoff carries a required notice period, check with [your counsel or HR advisor] first.

   > **Use this wording: Opening line for an involuntary separation conversation (have [your counsel or HR advisor] review it before you adopt it)**
   > 
   > [Employee first name], we have decided to end your employment, effective [date]. Your access to company systems ends now. [HR name] will walk you through final pay, benefits, and returning company property.

   *Why this matters:* A shared checklist with named owners prevents the failure where no one owns a step: everyone assumes someone else is handling access or the final paycheck, and the separation type decides which steps come first.

2. **Inventory every system the employee can access** (Owner: IT admin)

   - **a.** Pull the employee's row from the access registry. If no registry exists, build the list from their role's access matrix and ask the manager to add anything the matrix does not cover.
   - **b.** List every system: email, single sign-on (SSO, one login that opens your other tools), CRM, cloud storage, communication tools, billing platforms, admin panels, and any client-facing accounts.
   - **c.** Flag every shared or service-account credential the employee knew, because those need rotation, not just individual revocation.
   - **d.** Copy the list into the revocation record on the checklist, one row per system, with the revoke columns blank.

   *Why this matters:* You cannot revoke what you have not listed. An incomplete inventory is how a departed employee retains access to something nobody remembered, and the list becomes the record you check later.

3. **Start the knowledge transfer at notice** (Owner: Manager)

   - **a.** List every open project, pending task, and client or vendor relationship the employee owns, using [your project management tool] and [your CRM] as the source, not the employee's memory.
   - **b.** If the separation is involuntary or has no notice, skip sending the handoff request and skip asking for files on personal devices. Write the handoff from those records, as the last action in this step describes.
   - **c.** Send the employee the handoff request below and set the due date at [N] business days before the last day.
   - **d.** Ask the employee to move any company files or client data stored on a personal device or personal account into [your company cloud storage] now, before access is cut.
   - **e.** As each item is handed over, reassign its owner in [your project management tool] and [your CRM] so nothing sits orphaned.
   - **f.** If the employee refuses or cannot hand over, write the handoff yourself from the project and CRM history, note "handoff reconstructed" on the checklist, tell HR, and go to step 4.

   > **Use this wording: Handoff request to the departing employee**
   > 
   > Hi [employee first name], as you wrap up before [last day], please write handoff notes for each open project, client, and vendor you own: current status, next action, key contacts, and where the files live. Please put them in [shared handoff location] by [date]. I will review them with you on [date]. Thank you for making this easy on the team.

   *Why this matters:* Knowledge that only exists in one person's head leaves with them. Starting at notice, not on the last day, leaves time to fill gaps while the person can still answer questions.

4. **Hold the exit interview** (Owner: HR)

   - **a.** Schedule the exit interview for [interview length, e.g. 15 to 20 minutes] in the last week. HR runs it, not the manager, so people say what they think. The person still has access, but the interview does not need it.
   - **b.** Ask the same standardized questions every time: what worked, what did not, and whether they would recommend the company to a peer.
   - **c.** Log themes, not just individual comments, so patterns across multiple exits are visible to leadership.
   - **d.** If the employee declines, write "declined" and the date on the checklist, send the written feedback form, and go to step 5.
   - **e.** If access was already revoked (termination, layoff, or no notice), offer the interview by phone or the written feedback form within [N] business days after the last day. If there is no reply after one reminder, write "no response" on the checklist and go to step 5.

   > **Use this wording: Opening line for the exit interview**
   > 
   > Thank you for making time, [employee first name]. I ask everyone who leaves the same questions. What you say is used to improve how we work. What worked well for you here, and what did not?

   *Why this matters:* Consistent questions turn exit interviews into usable retention data instead of a one-off, forgettable conversation, and offering it to every leaver keeps the data from skewing toward voluntary exits only.

5. **Confirm the handoff is complete before access is cut** (Owner: Manager)

   - **a.** Open [your project management tool] and [your CRM] and confirm every item on the list from step 3 has a new owner other than the departing employee.
   - **b.** Confirm the handoff notes are in [shared handoff location] and the manager has read them.
   - **c.** Initial the knowledge transfer line on the checklist with the date.
   - **d.** If any item still has no new owner [N] business days before the last day, tell [department head role] and have them assign it before you initial.
   - **e.** If access was already revoked, confirm the same items against the reconstructed handoff and initial the line as "reconstructed".

   *Why this matters:* An initialed line is the proof the handoff happened. Without it, orphaned work is discovered weeks later by a client who asks where their project went.

6. **Revoke access** (Owner: IT admin)

   - **a.** Revoke at [time, e.g. end of business] on the last day for a resignation with notice, and at the start of the separation conversation for any other separation type.
   - **b.** Disable the SSO or primary identity account first. For every app connected to it, this cuts access at once.
   - **c.** Confirm each high-risk system separately, because not every tool connects to SSO: email forwarding rules, billing and financial tools, client CRM, and every admin-level account.
   - **d.** Rotate every shared credential flagged in step 2 and remove the employee from distribution lists and shared mailboxes.
   - **e.** For each system on the revocation record, write the date, time, and your initials.
   - **f.** Have [a second person, e.g. HR] compare the revocation record to the step 2 inventory, confirm every row is filled, and initial it.
   - **g.** If you cannot confirm a revocation for any system, tell [IT lead role] the same day and keep that row open on the checklist. Steps 7 and 8 can continue, but do not go to step 10 until every row is closed. Step 9 does not wait on this row.

   *Why this matters:* Same-day revocation limits what a departed person can still reach. Access left open, even briefly, can be used, and the second-person check catches the row someone skipped.

7. **Recover company property and confirm data location** (Owner: IT admin)

   - **a.** Collect the laptop, phone, keycard, and any other issued hardware listed in the company property log, or send a prepaid return kit to a remote employee.
   - **b.** Check the property log line by line and initial each item as it is received.
   - **c.** Confirm where company files and client data live. Anything still stored locally goes into [your company cloud storage] before the device is wiped.
   - **d.** Wipe and re-image returned devices before reissue, following [your device retirement process].
   - **e.** If an item is not returned by [N] business days after the last day, send the return reminder below.
   - **f.** If it is still not returned [N] business days later, mark it "not returned" in the property log, lock the device remotely through [your device management tool] if it is enrolled, tell [HR lead role], and wipe it only after [HR lead role] confirms.

   > **Use this wording: Return reminder for unreturned property**
   > 
   > Hi [employee first name], our records show we have not yet received the following company property: [item list]. Please return it by [date] using [return address or prepaid kit instructions]. If you have any trouble, reply to this message and I will help.

   *Why this matters:* Company data that only lived on one person's device disappears when they leave, unless it is confirmed and moved before the device is reset.

8. **Run the final access audit** (Owner: IT admin)

   - **a.** [N] business days after the last day, open the user list of every system on the revocation record and confirm the departed employee's account is disabled or removed.
   - **b.** Search email, shared mailboxes, and distribution lists for the employee's address and confirm nothing still delivers to it unless it is an approved forward to the manager.
   - **c.** Write the audit date and your initials on the checklist, and have [a second reviewer, e.g. the IT lead] check the same rows and initial.
   - **d.** If any account still shows access, revoke it now, tell [IT lead role], add the system to the access registry and the role's access matrix, and note it on the checklist. Then re-run this audit for that system before you go to step 10.

   *Why this matters:* The step 6 revocation shows what you did. The audit shows what is true a few days later, after restored accounts, forgotten integrations, and delayed syncs have had a chance to appear.

9. **Send final pay and benefits details to payroll and the benefits provider** (Owner: HR)

   - **a.** Start this step as soon as the last day is confirmed, not after step 8, so final pay follows [your written policy] and not the audit schedule.
   - **b.** Give the payroll owner the last day, the separation type, and the accrued time off figure from [your written policy], and ask them to run the final pay through Payroll Processing.
   - **c.** Record the payroll confirmation (date and confirmation number or receipt location) on the checklist.
   - **d.** Send the benefits termination and continuation notices through [benefits provider contact] and record the date sent.
   - **e.** If the payroll confirmation is not received by [N] business days after the last day, tell [payroll owner role] and record the follow-up date on the checklist.

   *Why this matters:* Final pay and benefit notices carry compliance exposure. A confirmation number turns "we think it was paid" into a fact you can point to months later.

10. **Close the offboarding record** (Owner: HR)

   - **a.** Walk the checklist top to bottom and confirm every line is filled: separation logged, inventory, handoff initials, exit interview (or "declined" or "no response"), revocation record, property log, final access audit, payroll confirmation, benefits notices.
   - **b.** If any line is open, do not close the record. Assign the open line to its owner with a date and re-check it on that date.
   - **c.** File the completed checklist and revocation record in [record location] and write the filing date on the checklist.

   *Why this matters:* A record closed with lines still open leaves "did we finish this?" unanswered months later.

## Exceptions and troubleshooting

- **If** The employee resigned with no notice or was terminated for cause. **Then:** Compress the timeline as step 1 describes: revoke access before or during the separation conversation, and complete the property inventory that same day. Run the knowledge transfer from records afterward instead of spreading it across a notice period that does not exist.
- **If** You discover a system the departing employee could access that is not in the registry. **Then:** Revoke it immediately, add it to the revocation record, then add it to the registry and the standard role-based access matrix so it is caught automatically next time.
- **If** Company files turn up only on a personal device or personal cloud account. **Then:** Have the employee move the files into company storage before device or account access is cut, and document what was found on the checklist. If access is already cut, tell [HR lead role] and follow [your data recovery process].
- **If** A departed employee's access shows up again in the final access audit or in a later scheduled access review. **Then:** Treat it as a security incident: revoke immediately, trace how it was missed or restored, and fix the gap in the checklist and the access registry.
- **If** The departing employee refuses or is unable to complete the handoff notes. **Then:** The manager writes the handoff from [your project management tool] and [your CRM] history, marks the checklist line "reconstructed", and tells HR. Do not hold access open to force the handoff.

## Quality checklist

- [ ] Separation logged with type and last day, and the offboarding checklist opened the same day
- [ ] Steps ordered for the separation type: knowledge transfer started at notice for a resignation, access revoked at the start of the conversation for any other type
- [ ] Full access inventory pulled from the registry or built from the role's access matrix, and copied into the revocation record
- [ ] Knowledge transfer started at notice, every open item reassigned, and the line initialed by the manager
- [ ] Exit interview held, or "declined" or "no response" recorded, and offered to every leaver
- [ ] Every system on the revocation record shows date, time, and initials, and a second person checked and initialed the record
- [ ] Shared or service-account credentials rotated
- [ ] Company property collected or marked "not returned", and returned devices wiped or re-imaged after data was moved to company storage
- [ ] Final access audit run and initialed by two people
- [ ] Final pay routed through Payroll Processing with a confirmation recorded, benefits notices sent, and the record filed

## Common mistakes

- **Mistake:** Revoking access "sometime in the next few days" instead of on the last day, or at the start of the conversation for an involuntary separation. **Fix:** Treat access revocation as a same-day, non-negotiable step and follow the timing set in step 1 for the separation type.
- **Mistake:** Assuming SSO revocation covers everything without checking high-risk systems individually. **Fix:** Confirm billing, financial, admin, and client-facing systems separately, since not every tool is connected to SSO, and write each one on the revocation record.
- **Mistake:** Waiting until the last day to start knowledge transfer. **Fix:** Begin the handoff as soon as notice is given (step 3), so there is time to fill gaps before the person is gone.
- **Mistake:** Closing the checklist before running the final access audit, or before every access row has a date and initials. **Fix:** Run the audit in step 8 and walk the revocation record line by line in step 10 before marking the checklist complete.
- **Mistake:** Offering the exit interview only to people who resign. **Fix:** Offer it to every leaver. For involuntary separations, offer it after the last day by phone or the written feedback form.

## How to know it is working

- Every row of the revocation record shows the departed employee revoked by the timing set in step 1, with a second person's initials.
- The final access audit found no remaining access, or every finding was revoked and re-checked.
- No company data remains on a personal device, and every unreturned item is marked "not returned" with a decision recorded.
- Open projects and client relationships have a named new owner, not a gap.
- The exit interview was held, declined, or unanswered, and the outcome is logged. Final pay is confirmed through Payroll Processing and benefits notices are sent.
- The next scheduled access review ([your access review cadence]) shows zero lingering access for anyone who has left.

| Metric | Target |
| --- | --- |
| Access revoked at the timing set for the separation type | 100%, zero exceptions |
| Final access audit completed and initialed by two people | 100% before the record is closed |
| Offboarding checklist completion rate | 100% before the record is closed |
| Exit interview offered and outcome logged | 100% of departures, voluntary and involuntary |
| Access review findings (departed employees with active access) | Zero |

## Related procedures

- Hiring Process
- IT Access Provisioning
- Performance Review
- Payroll Processing

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

Template by Pro Sulum. Online version with a fillable worksheet: https://www.prosulum.com/sops/templates/employee-offboarding/

Free to use and adapt for your own business, licensed CC BY 4.0: credit Pro Sulum (prosulum.com) if you republish it.
