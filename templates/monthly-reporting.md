# Monthly Reporting

Updated September 28, 2026

This SOP covers one monthly cycle, from the first business day after a calendar month ends through the report going out and being archived. The report preparer (a trained team member) pulls the full closed month from each approved source, checks every metric against prior periods, writes the analysis, and formats it in the standing template. A reviewer who is not the preparer then checks the numbers before the report goes to the distribution list by the send date, [day] of the following month. It exists so the report keeps the same shape and the same source of truth every month, and so it does not depend on one person.

**What this gives you:** You steer by a report that arrives the same way every month, so the hours that went into rebuilding it go into deciding where the company goes next, the work only you can do.

**Primary owner:** Report preparer  
**Runs:** Monthly, starting on the first business day after each calendar month ends  
**Time:** [your hands-on time, e.g. 3 to 5 hours], spread from the first business day after month end to the send date; replace the example with your own after three timed runs

## Before you start

- A metric table with one row per KPI: the single source of truth for that number ([your CRM], [your accounting software], [your marketing platform], [your ops dashboard], or another system), the calculation, the target, the metric owner (the person who explains a movement in that number), and a mark showing which KPIs are headline metrics
- A named backup preparer with access already granted to every source in the metric table
- [ops lead role], who receives every "stop and tell" message in this procedure and is not the preparer
- A standing report template with fixed sections and documented metric definitions, saved at [template location]
- A KPI cap of [N] metrics (e.g. 5 to 10) that drive a decision
- A distribution list and the channel used to send the finished report, both saved at [distribution list location]
- The send date for the report, written as [day] of the following month (e.g. the 5th)
- The reviewer role, which must be someone other than the preparer, written as [reviewer role]
- The anomaly threshold, written as [x]% or [$y] of movement in either direction
- The prior month's report and last year's report for the same month, kept in [report archive location]
- A shared folder, [report archive location], where every report version is stored

## Procedure

1. **Confirm the metric table before pulling any data** (Owner: Report preparer)

   - **a.** Open the metric table in [metric table location] and confirm every KPI still has a named source, a calculation, a target, and a metric owner.
   - **b.** If a metric no longer changes a decision, remove it from the table and note the removal in the change log at [change log location].
   - **c.** Count the rows. If the count is above the cap of [N], remove a metric before you add or keep another one.
   - **d.** If a metric has no named owner or source, stop and notify [ops lead role] before you pull data, then go to step 2 once the row is complete.

   *Why this matters:* A KPI list that keeps growing makes the report harder to read.

2. **Pull the full closed month from every source on the first business day after month end** (Owner: Report preparer)

   - **a.** Wait until the month has closed. A pull before the last day of the month covers only part of it, so do not use it in the report.
   - **b.** For figures from [your accounting software], pull only after the books for the month are locked (see Month-End Close). If they are not locked by the end of the first business day, tell [ops lead role], mark those figures "pending" in the template, and skip the step 3 comparison for them.
   - **c.** Export or refresh each source in the metric table for the whole calendar month, from [first day] to [last day], using the same window for every source.
   - **d.** Pull the prior month and the same month last year from the same source, with the same calculation, so the comparison in step 3 matches.
   - **e.** Paste each figure into the standing template and write the source name and the pull date next to it.
   - **f.** If a source cannot be reached, ask the backup preparer to pull it. If neither of you can pull it by the end of the first business day, tell [ops lead role], mark the figure "pending", and go to step 3. In step 3, skip the comparison for any pending figure.

   *Why this matters:* Full-month figures pulled from a defined set of sources make the report one source of truth instead of several conflicting numbers, and they match the full-month figures you compare against.

3. **Validate against prior periods and flag anomalies** (Owner: Report preparer)

   - **a.** For every metric, calculate the change from the prior month and from the same month last year.
   - **b.** Flag any metric that moved more than [x]% or [$y] in either direction against either comparison.
   - **c.** For each flagged metric, send the metric owner the message under "Use this wording: Anomaly question" below.
   - **d.** If the metric owner explains the movement, write the explanation next to the figure and keep the figure in the report.
   - **e.** If the metric owner has not replied within [N] business days, keep the figure in the report, mark it "unconfirmed" in the template, and note the date you asked. Then go to step 4.
   - **f.** If two sources disagree on the same metric, use the source listed in the metric table, note the difference in the report, and tell [ops lead role] so the disagreement is fixed at the source.

   > **Use this wording: Anomaly question**
   > 
   > [Metric] for [month] came in at [figure], which is [change] against [prior month or same month last year]. The source is [source]. Can you tell me what drove the movement, and whether the figure is right, by [date]?

   *Why this matters:* An anomaly caught in prep can be explained before anyone reads it. An anomaly first caught by a recipient can look like an error.

4. **Write a short analysis for each headline metric** (Owner: Report preparer)

   - **a.** For every headline metric, write two to three sentences covering what happened, the most likely reason, and what it means going into next month.
   - **b.** Use the pattern under "Use this wording: Headline metric analysis" below, so every metric reads the same way.
   - **c.** Take the reason from the metric owner's reply where you have one. If you have no reason, mark the figure "unconfirmed", the same mark as step 3, rather than guessing.

   > **Use this wording: Headline metric analysis**
   > 
   > [Metric] was [figure] in [month], [up or down] [amount] versus [comparison period]. The main driver was [reason, from the metric owner]. Going into [next month], [what to watch or do].

   *Why this matters:* A number with no context forces every reader to guess at the story behind it.

5. **Format into the standing template** (Owner: Report preparer)

   - **a.** Place the data and analysis into the template at [template location], in the same layout and order as last month.
   - **b.** Use the same charts or comparisons as last month for anything trending over time.
   - **c.** Save the draft in [report archive location] with the name [report name]-[YYYY-MM]-draft.
   - **d.** Hand the draft to the reviewer and record the date and time you handed it over on the draft.

   *Why this matters:* Recipients learn where to find each number when the layout does not change. A report reformatted every month is harder to read.

6. **Review the numbers against the source data and initial the draft** (Owner: Report reviewer)

   - **a.** The reviewer is [reviewer role], and must not be the person who prepared the report.
   - **b.** Compare each figure in the draft to the source named next to it. Check that every flagged anomaly has an explanation or an "unconfirmed" mark in the report.
   - **c.** If every figure matches, write your initials and the date at [sign-off location] on the draft, then go to step 7.
   - **d.** If a figure does not match, return the draft to the preparer with the figure and the source value. The preparer corrects it and hands it back, and you repeat the comparison for that figure.
   - **e.** If the figure still does not match by the end of [N] business days, mark it "pending" in the report and go to step 7 with the follow-up date set by the preparer.

   *Why this matters:* A second reviewer can catch transcription errors and unexplained swings before a stakeholder does, and the initials show that someone other than the preparer checked.

7. **Distribute by the send date** (Owner: Report preparer)

   - **a.** Confirm the reviewer's initials are on the draft. If they are not, do not send. Go back to step 6.
   - **b.** Send the report through [distribution channel] to the full list at [distribution list location] on or before [day] of the following month, using the wording under "Use this wording: Report cover message" below.
   - **c.** If one figure is still pending, send the report with the figure marked "pending" and the follow-up date in the message, using the wording under "Use this wording: Pending figure notice". Do not hold the whole report.
   - **d.** Open the sent copy and confirm the list, the attachment or link, and the date are correct. Write the send time on the draft.
   - **e.** When the pending figure arrives, send the corrected page to the same list on the follow-up date.

   > **Use this wording: Report cover message**
   > 
   > The [month] report is attached ([link]). The headline movements are [metric] and [metric]. Reply to [preparer role] with questions by [date].

   > **Use this wording: Pending figure notice**
   > 
   > [Metric] is marked "pending" in this report because [reason]. We will send the confirmed figure on [follow-up date].

   *Why this matters:* A late report is less useful by the time it is read. Consistent timing helps readers build the habit of reading it.

8. **Archive the report and log any changes** (Owner: Report preparer)

   - **a.** Save the final report in [report archive location] using the name [report name]-[YYYY-MM].
   - **b.** Save the reviewer-initialed draft in the same folder.
   - **c.** Record any change to a metric's definition, source, or the KPI list in the change log at [change log location], with the date and the person who approved it.
   - **d.** Tell the backup preparer where the final report and the change log are saved.

   *Why this matters:* An archived, consistently named history lets anyone trace how a metric has moved over time, not only this month.

## Exceptions and troubleshooting

- **If** A number looks wrong close to the send date. **Then:** Do not publish it as final. Mark it "pending" with a follow-up date and send the rest of the report by the send date.
- **If** Two data sources disagree on the same metric. **Then:** Use the source listed in the metric table, note the difference in the report, and tell [ops lead role] so the disagreement is fixed at the source before next cycle.
- **If** The report keeps growing every month with more metrics and sections. **Then:** Enforce the cap of [N] metrics. Remove a metric before adding one, and ask whether each addition changes a decision.
- **If** The preparer is out on the first business day after month end. **Then:** The backup preparer runs steps 1 to 4 from the same metric table. If nobody can pull the data, tell [ops lead role] and give recipients a revised send date before the original one passes.
- **If** The books in [your accounting software] are not locked by the first business day after month end. **Then:** Do not pull accounting figures from an open month. Tell [ops lead role], mark those figures "pending" in the template, and send the report by the send date with the pending notice. When the books lock (see Month-End Close), pull the figures and send the corrected page on the follow-up date.
- **If** You want to confirm source access before the month ends. **Then:** Run a test export from each source a few business days before month end to confirm the logins work. Treat it as an access check only, and do the real pull in step 2 after the month has closed.

## Quality checklist

- [ ] Metric table reviewed and the KPI count is at or under [N] before the data pull started
- [ ] Data pulled on the first business day after month end (accounting figures once the books were locked), for the full closed month, from the source named in the metric table
- [ ] Every metric compared to both the prior month and the same month last year
- [ ] Every metric that moved more than [x]% or [$y] has an explanation or an "unconfirmed" mark
- [ ] Every headline metric has a short written explanation, not just a number
- [ ] Report formatted in the standing template, not rebuilt from scratch
- [ ] The reviewer, who is not the preparer, checked the numbers against the source data and initialed the draft
- [ ] Report sent on or before [day] of the following month, and the sent copy was checked
- [ ] Final report, initialed draft, and any change-log entry saved in [report archive location]

## Common mistakes

- **Mistake:** Adding new metrics or reformatting the report ad hoc, so recipients can never find things in the same place twice. **Fix:** Lock the template and the metric table. Changes go through a deliberate review and a change-log entry, not an in-the-moment addition.
- **Mistake:** Publishing a metric that moved past the threshold without asking the metric owner why first. **Fix:** Send the anomaly question in step 3 for every metric past [x]% or [$y]. If the owner has not replied within [N] business days, mark the figure "unconfirmed" instead of guessing.
- **Mistake:** Pulling data before the month closes and comparing that part-month figure to full-month figures for prior periods. **Fix:** Pull on the first business day after month end, for the whole calendar month, so every comparison uses the same window.
- **Mistake:** Reviewing your own report, or skipping the initials. **Fix:** The reviewer is [reviewer role], never the preparer, and the report does not go out until their initials are on the draft.
- **Mistake:** Holding the whole report because one number is still pending. **Fix:** Send by the send date with the figure marked "pending" and a follow-up date in the message.
- **Mistake:** Letting one person hold the entire process in their head, with no written steps and no backup who can reach the sources. **Fix:** Keep the steps written down, name a backup preparer in the prerequisites, and confirm that person has access to every source in the metric table.

## How to know it is working

- The report goes out on or before the send date every month without depending on one specific person being available.
- Recipients find the same metric in the same place every month without asking where it moved.
- Movements past the threshold are explained, or marked "unconfirmed", inside the report, not discovered by a recipient asking why afterward.
- No metric appears in the report without a named source, calculation, target, and metric owner.
- Every report in the archive has a draft initialed by a reviewer who is not the preparer.

| Metric | Target |
| --- | --- |
| On-time distribution rate | 100% on or before the send date |
| Movements past the threshold explained or marked "unconfirmed" before distribution | Zero surprises found by recipients |
| Reports with a reviewer's initials from someone other than the preparer | 100% |
| KPI count held at or under the cap | No unexplained growth month over month |
| Time to produce the report | Trending down as the process gets more documented |

## Related procedures

- Weekly Team Meeting
- Performance Review
- Client Invoicing
- Project Kickoff
- Month-End Close

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

Template by Pro Sulum. Online version with a fillable worksheet: https://www.prosulum.com/sops/templates/monthly-reporting/

Free to use and adapt for your own business, licensed CC BY 4.0: credit Pro Sulum (prosulum.com) if you republish it.
