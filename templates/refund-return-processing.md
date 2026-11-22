# Refund and Return Processing

Updated November 22, 2026

This SOP covers one refund or return request, from the moment it arrives until it is refunded or denied, the customer is told in writing, and the record is tagged and closed. It applies to any business selling a physical product, a digital product, or a service with a stated refund policy. The support lead runs it every time a request arrives, and it is written so a trained team member can resolve a standard request without escalating to the owner. The monthly reason-code review runs on its own cadence, so it is described as a separate procedure in the troubleshooting section.

**What this gives you:** Every customer gets the same fair answer, and each refund leaves a written reason behind it. Complaints stop being something you react to and become something you can see, which keeps what you sell worth putting your name on.

**Primary owner:** Support lead  
**Runs:** Every time a refund or return request arrives  
**Time:** [e.g. 10 to 20] minutes per standard request and [e.g. 30 to 45] minutes for a physical return requiring inspection; replace with your own after three timed runs

## Before you start

- A written refund and return policy (eligibility window of [N] days, condition requirements, refund method, and what happens to an item that fails inspection) published at checkout and in the order confirmation
- Access to [your payment processor] and its refund tool
- Access to the order or client record in [your CRM or order system]
- The role that approves out-of-policy exceptions: [approver role], and the role that steps in if that person does not answer within [N] business hours: [second approver role]
- A refund approval limit: [approval limit, e.g. $500]. Any refund above it needs the Owner's initials on the record before it is issued
- A reason-code list for tagging every request: defect, not as described, changed mind, billing error, other
- Return shipping labels or a return authorization (RMA) process, if the business ships physical product: [your RMA or return-label tool]
- Your response window: every request is answered within [N] business hours of arriving, stated in the policy or order confirmation
- The wording in step 6, loaded as saved replies in [your email or support tool] with your company name and support contact filled in

## Procedure

1. **Log the request and confirm the order record** (Owner: Support lead)

   - **a.** The moment the request arrives, open a case in [your CRM or support system] and record the date and time received and how the customer asked (email, phone, chat).
   - **b.** Find the original order in [your order system]. Write the order ID, order date, product or service, and amount paid on the case.
   - **c.** If you cannot find the order, or the name on the request does not match the order, ask the customer for the order confirmation email.
   - **d.** If the customer has not sent the order confirmation email [N] business days after your request, go to step 6 and send the denial wording with "we could not match your request to an order" as the reason, then go to step 7 and tag the case "other, no order found".
   - **e.** When the order ID is on the case, go to step 2.

   *Why this matters:* Logging immediately timestamps the request, and an order ID on the case ties every later action to a real purchase.

2. **Check the request against the policy and get an exception decision if it is outside it** (Owner: Support lead)

   - **a.** Compare the order date and the reason given with the policy window of [N] days and the eligibility rules. Write "in policy" or "out of policy" and the rule you applied on the case. Decide from the written policy.
   - **b.** If the request is in policy and a physical item must come back, go to step 3. If it is in policy and nothing needs to come back (digital product, service, billing error), go to step 5.
   - **c.** If the request is out of policy, send it to [approver role] with the reason for the exception request, the customer's order history, and the refund amount you would issue. Write the date and time you sent it on the case.
   - **d.** If [approver role] has not answered within [N] business hours, send the same message to [second approver role] and note it on the case. If neither answers by the end of the next business day, follow the approver entry in the troubleshooting section.
   - **e.** When an approver answers, write their decision, the refund amount they approve, and their reasoning on the case.
   - **f.** If the approver approves, follow the in-policy path from the start of this step (step 3 for a physical item, step 5 for anything else). If the approver denies it, go to step 6 and send the denial wording.

   *Why this matters:* Checking the policy first means only in-policy or approved requests get an RMA, and a written decision means the same call is made the same way next time.

3. **Authorize the return of a physical item** (Owner: Support lead)

   - **a.** Issue a return authorization number (RMA) in [your RMA or return-label tool], with shipping instructions, and set a return deadline of [N] days from today (for example 14).
   - **b.** Write the RMA number and the return deadline on the case and send both to the customer using the return instructions wording below.
   - **c.** Refund once the item arrives. If the item has not arrived by the return deadline, send the return reminder wording below.
   - **d.** If it has not arrived [N] days after the reminder, close the case as "item not returned" with no refund, go to step 6 and send the denial wording, then go to step 7.
   - **e.** When the item arrives, go to step 4.

   > **Use this wording: Return instructions**
   > 
   > Subject: Return instructions for order [order ID]
   > 
   > Hi [first name],
   > 
   > Your return is authorized. Your RMA number is [RMA number]. Please send the item to [return address] using [shipping instructions] by [return deadline]. Include the RMA number on the package. When we receive the item we check it against our policy and will write to you with the result within [N] business days.
   > 
   > [Your name]\
   > [Your company]

   > **Use this wording: Return reminder**
   > 
   > Subject: Reminder: return for order [order ID]
   > 
   > Hi [first name],
   > 
   > We have not yet received the item for RMA [RMA number], which is due by [return deadline]. If you need help with the shipment, reply here or contact [support contact]. If we do not receive it by [date], we will close this request without a refund.
   > 
   > [Your name]\
   > [Your company]

   *Why this matters:* Refunding once the item is back in hand means the refund and the returned product move together.

4. **Inspect the returned item against the condition requirements** (Owner: Support lead)

   - **a.** Check the item against each condition requirement in the policy. Take photos of the item and the packaging, and attach them to the case.
   - **b.** Write "passed" or "failed" on the case, with the specific condition that failed if it failed, and your initials and the date.
   - **c.** If it passed, go to step 5 with the full refund amount.
   - **d.** If it failed and the policy provides a partial refund, calculate it using [your partial refund rule from the policy], write the amount on the case, and go to step 5 with that amount.
   - **e.** If the policy provides no partial refund, go to step 6 and send the denial wording with the failed condition stated.

   *Why this matters:* An inspection recorded with photos and initials keeps the decision tied to the written policy, so the customer gets a clear, fair answer.

5. **Check the amount and issue the refund** (Owner: Support lead)

   - **a.** Write the refund amount on the case: the full order amount for an in-policy request, the amount the approver wrote in step 2, or the partial amount from step 4. Enter an amount no higher than the amount paid on the original order.
   - **b.** If the amount is above [approval limit, e.g. $500], get the Owner's initials and the date on the case before you continue. If the Owner declines, write the Owner's reason on the case and go to step 6 to send the denial wording.
   - **c.** Issue the refund in [your payment processor] to the original payment method. Use store credit only if the policy specifies it or the customer agrees in writing. Issue it within [N] hours of the decision.
   - **d.** Compare the amount and the status shown in the processor to the amount on the case. If they match, write the transaction ID, amount, and date on the case and go to step 6.
   - **e.** If they do not match, hold off on a second refund and send the transaction ID and both amounts to the Owner.

   *Why this matters:* The refund is checked before it is sent and again against the processor afterward, so the right amount reaches the customer, and the transaction ID shows it posted.

6. **Send the written confirmation or denial to the customer** (Owner: Support lead)

   - **a.** Choose the wording that matches the outcome: refund for a defect, an item not as described, or a billing error; refund for a change of mind or any other reason; partial refund; or denial. Fill in every [slot] and send it from [your email or support tool].
   - **b.** For a refund, state the posting time your processor gives for the payment method. For a denial, state the specific rule or failed condition and how to reach a person.
   - **c.** Write the date and time the message was sent on the case.
   - **d.** If the customer replies disputing a denial or asking for a manager, open a case under the Customer Support Escalation procedure and note the case number here.

   > **Use this wording: Refund confirmation, defect, not as described, or billing error**
   > 
   > Subject: Your refund for order [order ID]
   > 
   > Hi [first name],
   > 
   > I'm sorry about the problem with [product or service]. Your refund of [amount] has been issued to your [payment method] as of [date]. Card refunds can take [posting time from your processor] to appear, and that timing is set by the card issuer.
   > 
   > If it has not appeared by [date], reply to this email or contact [support contact] and we will look into it the same day.
   > 
   > [Your name]\
   > [Your company]

   > **Use this wording: Refund confirmation, change of mind or other reason**
   > 
   > Subject: Your refund for order [order ID]
   > 
   > Hi [first name],
   > 
   > Your refund of [amount] for [product or service] has been issued to your [payment method] as of [date]. Card refunds can take [posting time from your processor] to appear.
   > 
   > If it has not appeared by [date], reply to this email or contact [support contact].
   > 
   > [Your name]\
   > [Your company]

   > **Use this wording: Partial refund**
   > 
   > Subject: Update on your return for order [order ID]
   > 
   > Hi [first name],
   > 
   > We received your return and checked it against our policy. [The specific condition that was not met]. Under [policy name or section], we can refund [partial amount] of the [amount paid] you paid. That refund has been issued to your [payment method] as of [date] and can take [posting time from your processor] to appear.
   > 
   > If you have questions, reply here or contact [support contact].
   > 
   > [Your name]\
   > [Your company]

   > **Use this wording: Denial**
   > 
   > Subject: Update on your request for order [order ID]
   > 
   > Hi [first name],
   > 
   > Thank you for contacting us about [product or service]. We are not able to refund this order because [the specific policy rule or failed condition]. Our policy is at [link to policy].
   > 
   > If you would like someone to look at this again, reply to this email or contact [support contact] and we will respond within [N] business days.
   > 
   > [Your name]\
   > [Your company]

   *Why this matters:* A written decision answers the customer's question the first time, and a denial with a stated reason is clear and fair.

7. **Tag the reason code and close the case** (Owner: Support lead)

   - **a.** Tag the case with one reason code (defect, not as described, changed mind, billing error, other) and one outcome (refunded, partially refunded, denied, item not returned).
   - **b.** Attach the supporting evidence to the case: photos, correspondence, the RMA, the approver's decision, and the transaction ID if a refund was issued.
   - **c.** Close the case in [your CRM or support system] only after the tag, the outcome, and the evidence are on it.

   *Why this matters:* A tagged case is one you learn from. The reason code shows the pattern across individual requests.

## When something comes up

- **If** The customer disputes the charge with their bank before contacting you. **Then:** Respond to the dispute immediately with your evidence: the order record, delivery confirmation, and correspondence from the case. If the underlying request is legitimate and in policy, refund directly through step 5 rather than contest it. If it is not, send your evidence and keep the case open until the bank decides.
- **If** A returned item fails inspection. **Then:** Follow step 4. Issue the partial refund your policy provides, or send the denial wording in step 6 with the specific failed condition. Use the amount the policy sets.
- **If** The approver in step 2 does not answer. **Then:** After [N] business hours, send the request to [second approver role] and note it on the case. If neither answers by the end of the next business day, tell the customer in writing when to expect a decision and notify the Owner.
- **If** A customer requests a refund well outside the policy window and threatens a chargeback. **Then:** Send it through step 2 like any out-of-policy request, and tell the approver about the chargeback threat. The approver weighs the cost of the exception against the cost of a dispute, and writes the decision and reasoning on the case either way.
- **If** It is time for the monthly reason-code review (a separate monthly procedure, run on [day of the month] by the support lead). **Then:** Pull every closed case for the month and total them by reason code and by product or SKU. Flag any code that reaches [N] or more cases (for example 3) as a sign that a product, listing, or process needs correcting at the source. Send the monthly total, the refund rate, and each flagged pattern to the Owner and to the person responsible for that product, and note next month whether the fix reduced the code.

## Quality checklist

- [ ] Case opened at the moment the request arrived, with the order ID on it
- [ ] Request checked against the written policy, with "in policy" or "out of policy" and the rule written on the case
- [ ] Out-of-policy requests decided by the approver in writing, with the amount and reasoning on the case
- [ ] RMA issued after the policy check, and the item inspected with photos and initials before any refund
- [ ] Refund amount checked against the original order and the approval limit before it was issued
- [ ] Processor status and amount match the case, with the transaction ID recorded
- [ ] Confirmation or denial sent using the matching wording, with the time sent recorded
- [ ] Reason code and outcome tagged, evidence attached, and the case closed only after both

## What a clean run looks like

- **What it looks like:** Every exception to the refund policy is documented on the case. **How:** Send every out-of-policy request to the approver in step 2 and write the decision on the case, so the same call is made the same way next time.
- **What it looks like:** An RMA is issued after the request is checked against the policy. **How:** Do the policy check in step 2 first. An in-policy or approved request gets an RMA in step 3.
- **What it looks like:** Every request gets a response inside the stated window. **How:** Respond inside your stated window every time, so the customer has a clear answer and less reason to go to their bank.
- **What it looks like:** A physical return is refunded after the item is received and inspected. **How:** Hold the refund until step 4 is recorded as passed, or until the partial amount is calculated.
- **What it looks like:** The processor is compared to the case on every refund. **How:** Do the amount check in step 5 every time, so the right amount goes out once.
- **What it looks like:** Every case gets a reason code before it closes. **How:** Tag the reason code in step 7 before you close the case. It is how you catch a defective product or a billing bug early.

## How to know it is working

- Every refund request is logged, checked against the policy, and answered inside the stated window.
- No case is closed without a reason code, an outcome, and evidence on file.
- Out-of-policy exceptions are rare, decided in writing by the approver, and consistent.
- Every refund shows a transaction ID that matches the processor.
- Dispute and chargeback volume trends flat or down relative to refund volume.
- The monthly reason-code review surfaces upstream patterns, and each one gets an owner and a fix date.

| Metric | Target |
| --- | --- |
| Refund request response time | Inside your stated window, e.g. 24 to 48 hours |
| Refunds processed before a chargeback is filed | 100% where the request was legitimate and in policy |
| Refund amount checked against the order and the processor | 100% of refunds |
| Reason-code tagging completion | 100% of closed cases |
| Repeat reason-code incidents per month | Trending down |

## Related procedures

- Client Invoicing
- Customer Support Escalation
- Contract Renewal

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

Template by Pro Sulum. Online version with a fillable worksheet: https://www.prosulum.com/sops/templates/refund-return-processing/

Free to use and adapt for your own business, licensed CC BY 4.0: credit Pro Sulum (prosulum.com) if you republish it.
