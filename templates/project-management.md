# Project Management

Updated September 28, 2026

This SOP covers one recurring task: the weekly project control run for a client or internal project that has already been through Project Kickoff. Each week the project manager updates the tracker against the scope baseline, sets each workstream's status by written criteria, decides or routes pending change requests, reviews the risk and issue log, publishes the status update to the distribution list, and escalates anything that has passed its limit. It runs on [day of week] every week from the week after kickoff until closeout begins, so the owner or sponsor only sees the status update and the escalations.

**Primary owner:** Project manager  
**Runs:** Weekly, on [day of week], from the week after kickoff until closeout begins  
**Time:** 3-5 hours per weekly run

## Before you start

- A completed Project Kickoff: signed charter with the definition of done, RACI, milestone timeline, risk log, and communication plan with a named escalation path. If any of these is missing, run Project Kickoff first
- One-time setup before the first weekly run: save the approved charter and milestone timeline as the scope baseline at [read-only baseline location], with edit rights limited to [baseline custodian role], separate from the working project plan
- Every workstream owner has seen and agreed to the baseline, confirmed in writing at [baseline confirmation location]
- Your [task tracker], with one row per workstream and per milestone, and the baseline dates copied into it
- A change request template, saved at [change request template location], and a change log saved at [change log location]
- The approval threshold for scope changes, written as [approval threshold, e.g. any change over a set number of business days or a set dollar amount], and the [sponsor role] who decides changes above it
- The status criteria in step 2, with the [x], [y], and [$ or %] values filled in
- A status update template and a distribution list saved at [distribution list location], with the send time written as [day and time]
- The risk and issue log carried forward from kickoff, saved at [risk log location]
- A project archive at [project archive location] for the baseline, approved change requests, and risk log. Closeout is its own procedure and is not part of this weekly run

## Procedure

1. **Update the tracker against the baseline** (Owner: Project manager)

   - **a.** Ask each workstream owner for progress since last week, and enter the new percent complete and forecast dates for each workstream in the [task tracker].
   - **b.** Compare each forecast milestone date to the baseline date at [read-only baseline location]. Write the difference in business days in the variance column.
   - **c.** For each milestone due this week, check the deliverable against the definition of done in the charter, then ask the accountable owner per the RACI to sign it off and write their initials and the date in [sign-off location].
   - **d.** If the deliverable does not meet the definition of done, leave the milestone open, add a rework item with an owner and a date, and record the added delay in the variance column.
   - **e.** If a workstream owner has not replied by [time], enter "no report" for that workstream and go to step 2.

   *Why this matters:* Without a locked baseline and a weekly comparison, scope creep and schedule slips are invisible because nothing fixed is being compared against the current state.

2. **Set each workstream's status by the written criteria** (Owner: Project manager)

   - **a.** On track: no milestone is forecast to slip more than [x] business days against the baseline, no open issue is past its committed resolution date, and budget variance is at or under [$ or %].
   - **b.** At risk: a milestone is forecast to slip more than [x] and up to [y] business days, or budget variance is over [$ or %], or an open issue is past its committed resolution date.
   - **c.** Blocked: work cannot continue until a named decision or resource arrives, or a milestone is forecast to slip more than [y] business days.
   - **d.** Enter the status for each workstream in the [task tracker]. For At risk and Blocked, write the specific reason and the decision or resource needed to unblock it.
   - **e.** A workstream with "no report" from step 1 is set to At risk until its owner reports.

   *Why this matters:* A three-value status only means something when each value has a stated test. Otherwise the report keeps saying "on track" until the milestone is missed.

3. **Process pending change requests** (Owner: Project manager)

   - **a.** Open each pending change request at [change request template location]. If it is not on the change request template, return it to the requester and ask them to resubmit it on the template. Any request that changes scope, timeline, or budget counts, however small.
   - **b.** Write the impact on scope, timeline, and budget against the baseline on the request.
   - **c.** If the impact is within [approval threshold], you decide it as project manager. If it is above [approval threshold], send it to the [sponsor role], who decides it.
   - **d.** If it is approved, add a dated entry to the change log at [change log location], update the working plan and the [task tracker], and save a new dated version of the baseline at [read-only baseline location]. Never edit the original baseline in place.
   - **e.** Then tell the requester and the affected workstream owners using the wording under "Use this wording: Change approved".
   - **f.** If it is rejected, record the rejection and the reason in the change log, tell the requester within [N] business days using the wording under "Use this wording: Change rejected", and start no work on it.
   - **g.** If the [sponsor role] has not decided within [N] business days of receiving it, treat the request as not approved, start no work on it, and list it in step 6.

   > **Use this wording: Change approved**
   > 
   > Change request [number], [short description], was approved on [date] by [approver role]. The new scope, date, or budget is [detail]. The updated baseline is saved at [read-only baseline location]. Work on it can start on [date].

   > **Use this wording: Change rejected**
   > 
   > Change request [number], [short description], was not approved on [date] by [approver role]. The reason is [reason]. No work will start on it. If you want it reconsidered, resubmit it with [what would change the answer].

   *Why this matters:* An unrouted "quick favor" is how a fixed-scope project becomes a different, unbudgeted project, and the request record and change log keep the history visible.

4. **Review the risk and issue log** (Owner: Project manager)

   - **a.** Add every new risk or issue raised since last week to the log at [risk log location].
   - **b.** Give every open item an owner, a next action, and a committed resolution date no more than [N] business days out. An item with no owner and no date is not accepted into the log.
   - **c.** Close every item that was resolved this week and write the resolution and the date next to it.
   - **d.** Mark every item whose committed resolution date has passed, and list it in step 6.

   *Why this matters:* A risk log touched only at kickoff stops reflecting reality within a few weeks. The committed date lets step 6 tell a slow item from a stuck one.

5. **Publish the status update** (Owner: Project manager)

   - **a.** Fill in the status update template with each workstream's status and reason, the top open risks and issues, any decision needed and from whom, the change requests decided this week, and what is coming next.
   - **b.** Compare every status in the update to the [task tracker] before sending, so the two agree.
   - **c.** Send the update to the list at [distribution list location] by [day and time], using the wording under "Use this wording: Weekly status update".
   - **d.** Open the sent copy, confirm the list and the date are correct, and write the send time in the status log at [status log location].
   - **e.** Send the update even when nothing has changed, with the line "On track, nothing new."

   > **Use this wording: Weekly status update**
   > 
   > Project [name], week of [date]. Overall status: [on track / at risk / blocked]. [Workstream]: [status], because [reason]. Decision needed: [decision], from [role], by [date]. Change requests decided: [number and outcome]. Next week: [milestones and actions].

   *Why this matters:* An update that slips "just this week" becomes an update nobody trusts, and stakeholders start asking for one-off updates instead.

6. **Escalate anything past its limit** (Owner: Project manager)

   - **a.** List every item that has passed its limit this week: a Blocked workstream, an open issue past its committed resolution date, a change request the [sponsor role] has not decided within [N] business days, or a budget or schedule variance over [$ or %] or [y] business days.
   - **b.** Send each item to the escalation contact named in the communication plan, [escalation contact role], using the wording under "Use this wording: Escalation". State the specific decision or resource needed and the date you need it by.
   - **c.** If there is no reply by [N] business days after you send it, send it to [next-level escalation role].
   - **d.** Record the escalation and its outcome in the risk and issue log, and include the outcome in next week's status update.
   - **e.** Put the next run on your calendar for [day of week] next week.

   > **Use this wording: Escalation**
   > 
   > [Item] on project [name] has been [blocked / past its committed date of [date]] since [date]. The impact is [impact on the baseline]. I need [decision or resource] from [role] by [date] to unblock it. The options are [option 1] or [option 2].

   *Why this matters:* A blocked item that sits in the tracker without escalation is how a project misses its deadline without anyone seeing it coming.

## Exceptions and troubleshooting

- **If** A stakeholder requests a change directly to a team member instead of through the change request process. **Then:** Ask the team member to send the request to you, do no work on it, and record it as a pending change request for step 3. Say in the status update that it is pending a decision.
- **If** The status report keeps showing "on track" right up until the project misses a milestone. **Then:** Check whether the [x], [y], and [$ or %] values in step 2 are set tightly enough, and lower them if a milestone slipped without turning At risk first. Keep writing the specific reason for every At risk or Blocked status.
- **If** Two workstreams both claim ownership of the same overlapping deliverable. **Then:** Resolve it against the RACI from kickoff. If the RACI does not cover the overlap, fix the RACI right away and tell both owners in writing.
- **If** The project is trending over budget or behind schedule by more than the escalation limit. **Then:** Escalate it in step 6 with the variance against the baseline and the options: cut scope, extend the timeline, or add resources. Do not absorb the overrun without telling anyone.
- **If** The project is finished, or is being stopped early. **Then:** Stop the weekly run and start [your project closeout procedure]. Closeout confirms every deliverable is accepted against the baseline, captures lessons learned, and archives the record at [project archive location].
- **If** A workstream owner does not report for two weeks in a row. **Then:** Keep the workstream's status at At risk under step 2, and escalate it in step 6 to [escalation contact role] with the name of the workstream and the dates you asked.

## Quality checklist

- [ ] Scope baseline saved at [read-only baseline location] and confirmed by every workstream owner before the first weekly run
- [ ] Tracker updated against the baseline dates, with the variance written for every workstream and milestone
- [ ] Every milestone marked complete was checked against the definition of done and initialed by the accountable owner
- [ ] Every workstream status set by the written criteria, with a specific reason for every At risk and Blocked status
- [ ] Every scope, timeline, or budget change went through a change request, and every decision is in the change log
- [ ] Every rejected change request has a reason in the change log and a notice sent to the requester
- [ ] Every open risk or issue has an owner, a next action, and a committed resolution date
- [ ] Status update sent by [day and time] and the send time recorded in the status log
- [ ] Every item past its limit escalated with a specific ask and a date

## Common mistakes

- **Mistake:** Letting scope changes happen informally because "it's a small ask." **Fix:** Route every change through the change request in step 3, whatever its size, and save a new dated baseline version once it is approved.
- **Mistake:** Skipping a status update when there is nothing new to report. **Fix:** Send the update every week, even a one-line "On track, nothing new." A skipped update sends stakeholders looking for their own one-off check-ins.
- **Mistake:** Marking a milestone done because the date arrived, not because the deliverable met the definition of done. **Fix:** Check every milestone against the definition of done in the charter and get the accountable owner's initials before marking it complete.
- **Mistake:** Setting the status by feel, so everything reads "on track" until a milestone is missed. **Fix:** Apply the written criteria in step 2 to every workstream every week, and write the specific reason for At risk and Blocked.
- **Mistake:** Adding a risk or issue to the log with no owner and no committed date. **Fix:** Do not accept the item into the log until it has an owner, a next action, and a committed resolution date, so step 6 can tell when it has stalled.

## How to know it is working

- Every scope change is documented and traceable back to an approved change request in the change log.
- The status update goes out at [day and time] every week, with no gaps.
- No milestone is marked complete without the accountable owner's initials against the definition of done.
- Every status is set by the written criteria, and every At risk or Blocked status has a stated reason.
- Every open risk or issue has an owner and a committed resolution date, and every one that passes its date is escalated within the same weekly run.

| Metric | Target |
| --- | --- |
| Status updates sent by the scheduled day and time | 100% |
| Scope changes with a documented change request | 100%, zero informal changes |
| Change requests decided within [N] business days | 100% |
| Open risks and issues with an owner and a committed resolution date | 100% |
| Milestone hit rate against the baseline timeline | Baseline it in month one, then set [your target] |

## Related procedures

- Project Kickoff
- Weekly Team Meeting
- Monthly Reporting
- Customer Support Escalation

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

Template by Pro Sulum. Online version with a fillable worksheet: https://www.prosulum.com/sops/templates/project-management/

Free to use and adapt for your own business, licensed CC BY 4.0: credit Pro Sulum (prosulum.com) if you republish it.
