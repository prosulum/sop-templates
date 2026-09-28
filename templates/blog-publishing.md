# Blog Publishing

Updated September 28, 2026

This SOP takes one editor-approved final draft through formatting, on-page SEO, schema, pre-publish QA, going live, and distribution. The Content lead runs it each time a draft is approved and ready to publish, so the writer and the owner never touch the publishing mechanics. It applies to any business publishing blog content on a CMS, and it works because every check has a named artifact: an approval status, a signed-off QA checklist, a live-URL check and a logged URL.

**Primary owner:** Content lead  
**Runs:** Each time an approved draft is ready to publish  
**Time:** 45-60 minutes per post, plus distribution follow-up

## Before you start

- An approved, final draft in [content calendar name and location] with status "Approved"
- Access to [your CMS] with publishing permissions
- [Style guide title and location], covering heading structure, meta length limits and internal linking rules
- [QA checklist title and location], the pre-publish checklist used in step 5
- [QA log location], where any item that had to be fixed is written down
- Featured image and any in-post graphics ready, with alt text planned
- Access to [your email platform] and [your social scheduling tool] for step 7
- The names of [editor role] and [sales lead role], the two people this SOP sends messages to

## Procedure

1. **Confirm the draft is approved and final** (Owner: Content lead)

   - **a.** Open [content calendar name and location] and check that the post status reads "Approved" before touching formatting.
   - **b.** If the status is not "Approved", stop and return the draft to [editor role] with a note saying what is missing. Do not start again until the status changes.
   - **c.** Confirm the version in front of you matches the version the editor signed off on, not an earlier revision. If you cannot tell which is final, stop and ask [editor role]; continue only when the editor confirms in writing.
   - **d.** Note the target publish date and any campaign or launch the post is tied to. Step 6 uses both.

   *Why this matters:* Formatting an unapproved or outdated draft wastes the publishing step and risks putting unreviewed claims live.

2. **Format the post in the CMS** (Owner: Content lead)

   - **a.** Apply H2 and H3 headings per [style guide title and location] so the post is easy to scan.
   - **b.** Break up long paragraphs, add bullet lists where they help, and confirm the formatting renders correctly in the CMS preview, not just in the draft document.
   - **c.** Add a short, direct answer to the post's core question near the top. This is a suggestion, not a verified rule: an answer-first opening tends to help readers who skim. Follow your style guide if it says otherwise.

   *Why this matters:* Clean structure makes a post readable and easy to quote.

3. **Write the meta title, meta description, and URL slug** (Owner: Content lead)

   - **a.** Write a meta title within [meta title limit, e.g. 60 characters] that includes the primary keyword naturally.
   - **b.** Write a meta description within [meta description limit, e.g. 160 characters] that states what the post covers and gives a reason to click.
   - **c.** Set a short, descriptive URL slug that follows [URL convention in the style guide].

   *Why this matters:* Meta fields are the first thing a searcher sees in results; a weak or truncated meta directly costs click-through.

4. **Add images, alt text, and schema markup** (Owner: Content lead)

   - **a.** Upload the featured image and any in-post graphics, and compress them so they do not slow page load.
   - **b.** Write descriptive alt text for every image that gives real context. Use the primary keyword only where it fits naturally, never stuffed.
   - **c.** Add or confirm that the CMS applies Article schema (author, datePublished, publisher). Add FAQPage or HowTo schema where the post format supports it.
   - **d.** Note in the QA checklist that schema was added. Step 6 confirms it in the published page source.

   *Why this matters:* Alt text makes the post accessible, and schema gives search engines structured facts about the page; confirming it in the published page source proves it is live and not only visible in the editor.

5. **Add internal links and run the pre-publish QA gate** (Owner: Content lead)

   - **a.** Link to [number of internal links, e.g. 2 to 5] related posts or hub pages using descriptive anchor text, not "click here". Include at least one hub page related to the topic.
   - **b.** Run [QA checklist title and location] from the first item to the last: proofread for typos and broken formatting, click every outbound and internal link, confirm images load, verify meta title and description length, and confirm schema is present.
   - **c.** If any item fails, fix it, write the item and the fix in [QA log location], and rerun the checklist from the first item. Do not go to step 6 until every item passes on the same run.
   - **d.** When every item passes, initial and date the checklist in [QA checklist title and location]. That initialed checklist is the record that the gate was passed.

   *Why this matters:* Internal links help readers move through the site; the QA gate is the last chance to catch an error before it is live and indexed.

6. **Publish or schedule, and verify the live URL** (Owner: Content lead)

   - **a.** If step 1 tied the post to a dated campaign or launch, schedule the post for that date and time in [CMS time zone]. Otherwise publish now.
   - **b.** Once the post is live, open the live URL in a private (incognito) window and confirm it renders correctly, images load, and links work.
   - **c.** Check that the title and description appear in the browser tab and in [your search preview tool].
   - **d.** View the page source, or use [your schema testing tool], and confirm the Article schema added in step 4 is present in the published page.
   - **e.** Submit the URL for indexing in [your search console tool, e.g. Google Search Console URL inspection] so it is not waiting on a crawl.
   - **f.** Write the live URL and the publish date in [content calendar name and location] and change the status to "Published".
   - **g.** If you scheduled the post and it is not live [number of minutes, e.g. 15] minutes after the scheduled time, check the CMS scheduler status and time zone. If you cannot fix it in the CMS, publish it manually and log the cause in [QA log location].
   - **h.** If any check in this step fails, fix it in the CMS and repeat this step from the live-URL check.

   *Why this matters:* A published post that has not been checked live, or has not been submitted for indexing, can sit invisible or broken for days before anyone notices.

7. **Distribute across social, email, and sales** (Owner: Content lead)

   - **a.** Hand the post to Social Media Posting: add it to the social calendar with platform-adapted copy, not just a raw link drop.
   - **b.** Include the post in the next scheduled email newsletter. If it is a major piece by [criteria for a major post, e.g. a cornerstone guide or a campaign anchor], send a dedicated notification through [your email platform] instead.
   - **c.** If the post covers a topic that active prospects or clients are asking about, send the sales notification below to [sales lead role]. If it does not, skip this action.
   - **d.** Record each channel you used in [content calendar name and location] next to the post.

   > **Use this wording: Sales notification**
   > 
   > New post is live: [post title], [live URL]. It covers [topic in one line]. It may help with [objection or question]. Use it if [situation] comes up. Reply if you want a different angle covered.

   *Why this matters:* A published post nobody sees is a wasted asset; distribution is how a published post gets read.

## Exceptions and troubleshooting

- **If** The live post is missing an image or a formatting element that was correct in the draft. **Then:** Compare the CMS preview to the live render; a common cause is a theme or template conflict. Fix directly in the CMS and repeat the live-URL check in step 6.
- **If** The post is not showing up in the search console tool or is not indexed after [N] days. **Then:** Confirm it was submitted for indexing, check for a noindex tag left on by accident, and confirm it is linked from at least one other indexed page on the site. If it is still not indexed after fixing those, tell [editor role] and log it in [QA log location].
- **If** A factual error is discovered after the post is live. **Then:** Correct it immediately in the CMS, note the correction on the post if it involves a stated fact or figure, tell [editor role] what was wrong, and add the root cause to [QA log location] so review catches it next time.
- **If** The scheduled publish time passed and the post never went live. **Then:** Check the CMS scheduler status and time zone setting; many silent scheduling failures come from a time zone mismatch between the CMS and the content calendar. If it cannot be fixed quickly, publish manually and continue from step 6.
- **If** The editor changes the draft after it was approved and before it is published. **Then:** Stop, set the status back to whatever [editor role] uses for "in review", and restart this SOP at step 1 once the status is "Approved" again.

## Quality checklist

- [ ] Draft status confirmed "Approved" and the version matched the editor's sign-off before any formatting began
- [ ] Headings (H2/H3) applied per the style guide
- [ ] Meta title and meta description written within the limits in the style guide
- [ ] Featured image and all in-post images have descriptive alt text
- [ ] Article schema (and FAQPage or HowTo where applicable) confirmed in the published page source
- [ ] The set number of internal links added with descriptive anchor text, including one hub link
- [ ] QA checklist passed on a single run, initialed and dated, with any fixes written in the QA log
- [ ] Live URL checked in a private window: renders correctly, links work, images load, meta displays correctly
- [ ] URL submitted for indexing and the live URL recorded in the content calendar
- [ ] Post distributed through the channels chosen in step 7 and each one recorded

## Common mistakes

- **Mistake:** Publishing before the pre-publish QA gate is complete. **Fix:** Nothing goes live until every item passes on one run and the checklist is initialed.
- **Mistake:** Writing meta descriptions and titles as an afterthought, generic or truncated. **Fix:** Write meta fields deliberately within the limits in the style guide, for the searcher who has not read the post yet.
- **Mistake:** Relying on the CMS to auto-generate schema and never checking it is in the published page. **Fix:** View the page source, or use a schema testing tool, after publishing to confirm schema is present and correct.
- **Mistake:** Publishing and moving on without distributing the post anywhere. **Fix:** Distribution is step 7 of the same run, not a separate task that gets skipped when things get busy.
- **Mistake:** Fixing a failed QA item and continuing from that item instead of rerunning the checklist. **Fix:** Rerun the checklist from the first item after every fix; a fix can break something earlier in the list.

## How to know it is working

- Every published post passed the full pre-publish QA gate on a single run, with the checklist initialed and any fixes logged.
- The live URL was verified in a private browser window immediately after publishing.
- The post was submitted for indexing and its live URL is recorded in the content calendar.
- The post was distributed through at least one channel beyond the blog itself.

| Metric | Target |
| --- | --- |
| Posts passing QA on first check | [Your target, e.g. 100%] |
| Time from approval to live publish | [Your target, e.g. same day for standard posts] |
| Posts indexed within [N] days of publish | Tracked and trending toward 100% |
| Organic traffic per post at [N] days | Baseline it in month one, then set [your target] |

## Related procedures

- Social Media Posting
- Product Launch
- Monthly Reporting

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

Template by Pro Sulum. Online version with a fillable worksheet: https://www.prosulum.com/sops/templates/blog-publishing/

Free to use and adapt for your own business, licensed CC BY 4.0: credit Pro Sulum (prosulum.com) if you republish it.
