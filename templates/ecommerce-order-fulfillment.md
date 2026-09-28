# Ecommerce Order Fulfillment

Updated September 28, 2026

This SOP covers one customer order from the moment it is placed through delivery, for a business shipping physical product directly to customers. The fulfillment lead runs the desk steps (risk review, stock allocation, customer notification, delivery monitoring), which any trained team member can run, and warehouse staff do the physical picking, packing, and label handoff. It starts every time an order arrives, with pick, pack, and ship runs at [fixed daily times]. Exceptions such as holds, backorders, and address problems are handled in the troubleshooting section, and the weekly review of exception reason codes is its own procedure.

**Primary owner:** Fulfillment lead  
**Runs:** Every time an order arrives; pick, pack, and ship runs at [fixed daily times]  
**Time:** 5-15 minutes per standard order; longer for an exception that needs research or customer contact

## Before you start

- [Your order management platform] connected to [your inventory system] and [your shipping tool], with real-time stock visible across every warehouse or storage location
- A risk checklist saved at [risk checklist location], listing each signal that counts (for example a billing and shipping address mismatch, a first order over [amount], or a shipping address that is a known freight forwarder)
- The risk reviewer role, written as [risk reviewer role], who decides held orders, and the owner role, written as [owner role], who is the escalation above it
- Shipping carrier accounts, the standard carrier and service level written as [standard carrier and service level], and the same-day carrier cutoff written as [cutoff time]
- The packaging standard for fragile, oversized, and multi-item orders, saved at [packaging standard location]
- The backorder policy, the split-ship rule (step 2), and the address correction policy, saved at [policy location]
- The list of exception reason codes, written as [reason codes, e.g. risk hold, out of stock, address issue, carrier delay], in [your support system]
- The Refund and Return Processing SOP for cancellations, refunds, returns, and damage claims, and your lost-in-transit policy at [lost-in-transit policy location]

## Procedure

1. **Review the order for risk signals and address problems** (Owner: Fulfillment lead)

   - **a.** Check the order against the risk checklist at [risk checklist location] and count how many signals apply.
   - **b.** Confirm payment authorization status in [your order management platform] shows authorized, and run the address through [your carrier address check].
   - **c.** If two or more risk signals apply, or payment is not authorized, put the order on hold, log the reason code "risk hold" on the order, send it to [risk reviewer role], and do not release the order to step 2.
   - **d.** Send the customer the message under "Use this wording: Held order notice". The reviewer's decision (release, cancel, or refund) and the time limit are in the "Held order" entry in the troubleshooting section.
   - **e.** If the address fails the check, log the reason code "address issue" and send the customer the message under "Use this wording: Address confirmation". The next action is in the "Address problem" entry in the troubleshooting section.
   - **f.** If no risk signals apply, payment is authorized, and the address passes, mark the order released and go to step 2.

   > **Use this wording: Held order notice**
   > 
   > Your order [order number] is on hold while we complete a routine check before it ships. Please reply with [what to send, e.g. the name on the card and the billing ZIP] by [date]. We will update you by [date] at the latest.

   > **Use this wording: Address confirmation**
   > 
   > We could not confirm the shipping address on order [order number]: [address as entered]. Please reply with the correct address by [date] and we will ship the same day we hear from you.

   *Why this matters:* Catching a fraudulent order or a bad address before it ships is the point where the cost is a held shipment instead of a lost product, a reshipment, and a chargeback.

2. **Confirm inventory and allocate stock to the order** (Owner: Fulfillment lead)

   - **a.** Check real-time stock across every location for every line item on the order.
   - **b.** Allocate stock to the order in [your inventory system] so the same unit cannot be sold to another order.
   - **c.** If every line is in stock, go to step 3.
   - **d.** If any line is short, log the reason code "out of stock", send the customer the message under "Use this wording: Backorder notice", and apply the split-ship rule in the next two actions.
   - **e.** If the customer chooses to receive the in-stock lines now, allocate those lines and go to step 3 for them, and ship the short line later as its own shipment with its own tracking notice.
   - **f.** If the customer chooses to wait, hold all lines until the short item is in stock. The full path is in the "Backorder" entry in the troubleshooting section.

   > **Use this wording: Backorder notice**
   > 
   > Your order [order number] includes [item], which ships on [date]. You can [receive the rest of your order now and [item] on [date] / wait and receive everything together on [date] / substitute [item] / cancel [item] for a refund]. Please reply with your choice by [date].

   *Why this matters:* Allocating stock at this step, not at pick time, prevents two orders from competing for the same last unit.

3. **Pick the order against the pick list** (Owner: Warehouse staff)

   - **a.** Print or open the pick list generated by [your order management platform] at the [fixed daily pick run].
   - **b.** Pick each line item and scan its barcode. Do not pick from memory.
   - **c.** Check the quantity and the variant (size, color, configuration) against the pick list before you move the items to packing.
   - **d.** If an item is not at its listed location, or the scan does not match, stop picking that line and tell the fulfillment lead. The fulfillment lead corrects the inventory record, flags the location for a cycle count, and returns the order to step 2.

   *Why this matters:* A picking error is a common cause of a wrong-item complaint, and it is cheaper to catch here than after it ships.

4. **Pack the order and check it before sealing** (Owner: Warehouse staff)

   - **a.** Pack the items according to the packaging standard at [packaging standard location] for the product type: fragile, oversized, or multi-item.
   - **b.** Add the packing slip and any insert the order calls for.
   - **c.** Scan each item again at the pack station against the order and confirm the quantity matches. Write your initials on the packing slip.
   - **d.** If the second scan does not match the order, do not seal the package. Take it back to the fulfillment lead, who returns it to step 3 or step 2 depending on the mismatch.

   *Why this matters:* The pack step is the last chance to catch a picking error before it becomes a customer-facing problem, and the initials show who checked.

5. **Print the label, hand off to the carrier, and record the tracking number** (Owner: Warehouse staff)

   - **a.** In [your shipping tool], apply [standard carrier and service level], or the service the customer chose at checkout, for the weight, destination, and any promised delivery window.
   - **b.** Print the label, apply it, and hand the package to the carrier by [cutoff time] on the same business day.
   - **c.** Record the tracking number against the order in [your order management platform] the moment the label prints, and confirm the number shows on the order.
   - **d.** If the carrier tool rejects the address or the label will not print, do not ship. Return the order to step 1 and follow the "Address problem" entry in the troubleshooting section.
   - **e.** If the package misses the cutoff, keep it on the shelf marked for the next business day's run, and note it on the order.

   *Why this matters:* A shipped order without a recorded tracking number becomes a support ticket the first time a customer asks where it is.

6. **Send the shipping and tracking notification** (Owner: Fulfillment lead)

   - **a.** Confirm the automated shipping confirmation, with the tracking number and carrier link, was triggered when the label printed.
   - **b.** At the end of each shipping run, open [N] orders from the run and confirm the notification shows as sent. If any of them did not send, check every order in the run.
   - **c.** For any order where the notification did not send, send it manually using the wording under "Use this wording: Shipping confirmation", including the expected delivery window from the carrier where available.

   > **Use this wording: Shipping confirmation**
   > 
   > Your order [order number] shipped on [date] with [carrier]. Your tracking number is [tracking number], and you can follow it at [tracking link]. It is expected to arrive by [date].

   *Why this matters:* A customer who can track their own order has less reason to contact support.

7. **Monitor delivery and hand off returns** (Owner: Fulfillment lead)

   - **a.** Check carrier tracking until the order shows delivered.
   - **b.** If a shipment has not moved or has not arrived [N] business days past the expected delivery date, contact the carrier and open a claim under [lost-in-transit policy location]. Tell the customer the claim is open and what happens next.
   - **c.** If a shipment shows delivered but the customer says it did not arrive, pull the carrier's delivery scan and any photo confirmation, then follow [lost-in-transit policy location].
   - **d.** Send any return, refund, or damage claim to the Refund and Return Processing SOP and log the order as handed off. Do not decide it inside fulfillment.
   - **e.** When the order shows delivered and no return or claim is open, mark it complete.

   *Why this matters:* Fulfillment does not finish until the package reaches the customer or the order moves cleanly to the return process. Stopping at "shipped" hides the last-mile problems that drive complaints.

## Exceptions and troubleshooting

- **If** Held order: an order tripped two or more risk signals, or payment is not authorized. **Then:** The order stays on hold and does not ship. [Risk reviewer role] reviews it and decides within [N] hours. Release: the order returns to step 2. Cancel: if payment has not been captured, cancel the order, void the authorization, and tell the customer. Refund: if payment has been captured and the order will not ship, refund it through the Refund and Return Processing SOP and tell the customer. If there is no decision within [N] hours, send the order to [owner role] and tell the customer their update date. Do not ship a held order because the customer is pressing for faster shipping.
- **If** Backorder: a line item is short at allocation, or the physical count at pick is short. **Then:** Correct the inventory record. Send the backorder notice from step 2. Split-ship rule: if the customer chooses the in-stock lines now, ship those lines and ship the short line later as its own shipment with its own tracking notice, with the extra shipping cost handled as [split-ship shipping cost rule]. If the customer chooses to wait, hold all lines until the item is in stock. If the customer has not replied within [N] business days, [default action, e.g. ship the in-stock lines and refund the short line]. If the item is not in stock within [N] business days of the promised date, offer a cancellation and a refund through the Refund and Return Processing SOP. Log the reason code "out of stock".
- **If** Address problem: the address failed the check at step 1, or the carrier tool rejected it at step 5. **Then:** Send the address confirmation message from step 1 and log the reason code "address issue". Do not guess at a correction. When the customer replies with the address, update the order, note the correction on the customer's account, and go back to step 1. If there is no reply within [N] business days, cancel the order, void or refund the payment through the Refund and Return Processing SOP, and tell the customer.
- **If** The same product keeps triggering backorders, or the same exception code keeps repeating. **Then:** Do not review these patterns inside this order procedure. Run [your weekly exception review procedure] on [day of week], which reads the reason codes and delay reasons for the week and sends recurring patterns, such as one product often out of stock or one carrier service often late, to [purchasing or demand-planning role].
- **If** A shipment shows as delivered but the customer says it never arrived. **Then:** Pull the carrier's delivery scan and photo confirmation where available, and follow [lost-in-transit policy location] rather than deciding case by case.

## Quality checklist

- [ ] Every order checked against the risk checklist, payment status, and the address check before release to step 2
- [ ] Every held order sent to [risk reviewer role] with the held order notice sent to the customer
- [ ] Inventory allocated in the system before picking begins, and every short line has a backorder notice and a split-ship decision recorded
- [ ] Pick list followed with barcode scans, and any quantity or variant mismatch reported to the fulfillment lead, not silently corrected
- [ ] Packaging standard followed, with a second scan and initials on the packing slip before sealing
- [ ] Tracking number recorded on the order and the shipping notification confirmed sent
- [ ] Every exception has a reason code from the list, a customer message sent, and a documented outcome
- [ ] Delivery confirmed, or the order handed off to the Refund and Return Processing SOP or a carrier claim

## Common mistakes

- **Mistake:** Shipping an order before checking it against the risk checklist. **Fix:** Run the risk check in step 1 before any order is released to picking, even when order volume makes it tempting to skip.
- **Mistake:** Picking from memory instead of the generated pick list, especially for a familiar product. **Fix:** Require the pick list and a barcode scan for every order, regardless of how routine the item seems.
- **Mistake:** Letting a backorder sit unfulfilled with no customer notification. **Fix:** Send the backorder notice the moment allocation fails in step 2, with the ship date and the choices from your written policy.
- **Mistake:** Leaving a held order with the reviewer and no time limit, so it sits for days. **Fix:** Apply the decision time limit in the "Held order" entry in the troubleshooting section and escalate to [owner role] when it passes without a decision.
- **Mistake:** Calling the order done the moment the label prints and never checking whether it arrived. **Fix:** Follow carrier tracking through delivery in step 7 and open a carrier claim for anything stalled past the window.

## How to know it is working

- Every order is screened, allocated, and released to picking within [your processing window, e.g. one business day].
- Wrong-item and short-ship complaints trend down as picking accuracy improves.
- Every shipped order has a recorded tracking number and a sent notification.
- Every held order is decided within the time limit, and every backorder and address exception has a documented customer message and reason code.
- Delivery is confirmed or handed off to the Refund and Return Processing SOP or a carrier claim for every order, with no shipment left unmonitored.

| Metric | Target |
| --- | --- |
| Orders shipped within the committed processing window | 100% |
| Picking accuracy (orders shipped complete and correct) | [Your target, e.g. 99% or higher] |
| Orders with a recorded tracking number and sent notification | 100% |
| Held orders decided within the time limit | 100% |
| Backorder and address exceptions with a documented customer message and reason code | 100% |

## Related procedures

- Refund and Return Processing
- Client Invoicing
- Customer Support Escalation
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

Template by Pro Sulum. Online version with a fillable worksheet: https://www.prosulum.com/sops/templates/ecommerce-order-fulfillment/

Free to use and adapt for your own business, licensed CC BY 4.0: credit Pro Sulum (prosulum.com) if you republish it.
