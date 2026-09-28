# Vendor Payment

Updated September 28, 2026

This procedure takes one vendor invoice from the day it arrives to a payment that is released, reconciled, and filed. It exists so you pay only invoices that are real, matched to what you ordered and received, and approved at the right level, and so vendors are paid on time. The AP Clerk logs, verifies, matches, codes, and pays each invoice, the Approver named for the invoice amount approves it, and the Bookkeeper reconciles it. Start it every time a vendor invoice is received; payments are released on your [weekly or biweekly] payment run, or earlier when the due date falls before the next run.

**Primary owner:** AP Clerk  
**Runs:** Each time a vendor invoice is received; payments released on your [weekly or biweekly] payment run  
**Time:** 10 to 20 minutes per invoice for routine payments; longer for a new vendor or any bank detail change

## Before you start

- [Your AP or accounting software] with vendor records set up
- An approved vendor list with verified banking details and a W-9 or equivalent on file for each vendor
- Purchase orders or contracts for anything that requires a three-way match
- A written approval matrix: Tier 1 up to [amount, e.g. $500], the AP Clerk approves; Tier 2 from that amount up to [amount, e.g. $5,000], the Manager approves; Tier 3 above that, the Owner approves. "Approver" below means whoever the matrix names for the invoice amount.
- A second-release amount: [second-release amount] or more must be released by the Approver, not by the AP Clerk alone
- A confirmation amount: [confirmation amount] or more gets a payment confirmation message to the vendor
- Access to the company bank or payment platform, limited to the AP Clerk and the Approvers
- A chart of accounts for expense coding
- A naming format and two folders set in advance: for example VendorName_InvoiceNumber_YYYYMMDD, saved in [unpaid folder] and [paid folder]
- Roles used below (rename to match your team): AP Clerk, Approver, Bookkeeper. Name a backup Approver for each tier on your worksheet.

## Procedure

1. **Receive and log the vendor invoice** (Owner: AP Clerk)

   - **a.** Record the vendor name, invoice number, amount, due date, and what the invoice covers in [your AP software].
   - **b.** Search [your AP software] for the same invoice number, or the same vendor and amount within [N] days. If you find a match, stop and contact the vendor to confirm.
   - **c.** If the vendor confirms it is a duplicate, mark it "duplicate, do not pay" and stop. If it is a different invoice, continue.
   - **d.** Save the invoice in [unpaid folder], named in the standing format (e.g. VendorName_InvoiceNumber_YYYYMMDD).

   *Why this matters:* An invoice not logged the day it arrives is paid late or missed, and duplicate submissions are a common cause of double payment.

2. **Verify the vendor is legitimate and approved** (Owner: AP Clerk)

   - **a.** Find the vendor on the approved vendor list. Compare the sender's email domain to the domain on the vendor record, letter by letter, and compare the remit-to details on the invoice to the bank details on the vendor record.
   - **b.** Do not pay if the sender's domain differs from the record, the invoice shows bank details that are not on the record, or the vendor asks to change payment details. Follow the bank detail change entry in the troubleshooting section below, then return to step 2.
   - **c.** If the vendor is not on the approved vendor list, follow the new vendor entry in the troubleshooting section below, then return to step 2.

   > **Use this wording: Request for missing vendor information**
   > 
   > Hello [vendor contact],
   > 
   > We received your invoice [invoice number] for [amount]. Before we can pay it, we need [W-9 or equivalent / bank account details on your letterhead / the missing item]. Please send it to [your AP email address] by [date]. We will pay the invoice on the next payment run after we have it and have confirmed the details with you by phone.
   > 
   > Thank you,
   > [AP Clerk name], [your company name]

   *Why this matters:* Vendor impersonation and fake-invoice fraud target this step; a legitimate-looking invoice can come from a spoofed vendor.

3. **Match the invoice against the purchase order and receiving confirmation** (Owner: AP Clerk)

   - **a.** Find the purchase order by number (created under the Purchase Order Approval procedure) or the contract, and compare the invoiced amount and quantity to it.
   - **b.** Confirm in the receiving record that the goods or services were delivered before you continue. If the invoice has no purchase order because none was required, note the reason on the invoice record and continue.
   - **c.** If the invoice does not match the purchase order or receiving record, hold payment, send the discrepancy message to both the vendor and the internal requester, and return to step 3 when both have replied.
   - **d.** If the vendor has not replied within [N] business days, tell the Approver for the invoice amount and keep the invoice on hold.

   > **Use this wording: Discrepancy notice to the vendor**
   > 
   > Hello [vendor contact],
   > 
   > Invoice [invoice number] for [amount] does not match our purchase order [PO number] for [PO amount]. The difference is [description of difference]. We have placed the invoice on hold. Please send a corrected invoice or a written explanation by [date], and we will process it on the next payment run after that.
   > 
   > Thank you,
   > [AP Clerk name], [your company name]

   *Why this matters:* This three-way match is the standard control against paying for goods never received or being overbilled.

4. **Code the expense and send it for approval** (Owner: AP Clerk)

   - **a.** Assign the invoice to [the chart-of-accounts category for this type of expense] in [your AP software].
   - **b.** Look up the invoice amount in the approval matrix and write the Approver's name on the invoice record.
   - **c.** Send the invoice, the purchase order, and the receiving record to that Approver through the approval workflow in [your AP software].
   - **d.** If the Approver has not responded within [N] business days, send the request to the backup Approver named on your worksheet. If the invoice will pass its due date before anyone approves it, tell the vendor the expected payment date.

   *Why this matters:* Correct coding keeps the books accurate, and naming the Approver now prevents a wait while someone works out who signs.

5. **Approve or reject the invoice** (Owner: Approver)

   - **a.** Check the invoice against the purchase order and the receiving record that came with it.
   - **b.** To approve, click approve in the workflow. The workflow stamp with your name and the date is the record of approval; an email alone does not count.
   - **c.** To reject, enter the reason in the workflow and tell the vendor and the internal requester the reason. The invoice stays on hold and does not go to step 6 until the issue is resolved and the AP Clerk restarts at step 3.

   *Why this matters:* Dollar-threshold approval keeps small routine payments moving while making sure large spend gets a second approver.

6. **Release the payment through the approved method** (Owner: AP Clerk)

   - **a.** On the next payment run, or earlier if the due date falls before it, pay by the method already on the vendor record: ACH, check, or card.
   - **b.** Before you submit, compare the payment amount and destination account to the approved invoice and to the bank details on the vendor record. If either differs, stop and return to step 2.
   - **c.** For a payment of [second-release amount] or more, the Approver releases it in the bank or payment platform. The AP Clerk prepares it but does not release it.
   - **d.** Mark the invoice paid in [your AP software] with the payment date, method, and the confirmation or transaction ID.

   *Why this matters:* Copy-paste errors and last-minute manual overrides can introduce mistakes at the payment step.

7. **Reconcile, notify the vendor, and file the paid invoice** (Owner: Bookkeeper)

   - **a.** Confirm the payment cleared or settled for the expected amount on the bank statement or in the payment platform, and record the confirmation ID on the invoice record.
   - **b.** If the payment did not clear or the amount is wrong, tell the AP Clerk and the Approver the same business day and return to step 6.
   - **c.** For any payment of [confirmation amount] or more, send the vendor the payment confirmation message.
   - **d.** Move the invoice from [unpaid folder] to [paid folder] using the standing naming format.

   > **Use this wording: Payment confirmation to the vendor**
   > 
   > Hello [vendor contact],
   > 
   > We sent payment of [amount] for invoice [invoice number] on [payment date] by [payment method]. Reference: [confirmation ID]. Please tell us if it has not arrived by [date].
   > 
   > Thank you,
   > [Bookkeeper name], [your company name]

   *Why this matters:* Unreconciled payments hide errors until the bank reconciliation, where they are harder to unwind.

## Exceptions and troubleshooting

- **If** An invoice appears to be a duplicate of one already paid. **Then:** Step 1 covers this. Search [your AP software] for the invoice number and the vendor and amount. If you find a match, contact the vendor to confirm and do not pay a second time. Mark the second invoice "duplicate, do not pay."
- **If** A vendor asks to update their payment or bank details (bank detail change). **Then:** Do not act on the email or the invoice. First, hold every unpaid invoice for that vendor. Second, phone the vendor at a number already on the vendor record, not one from the request, and confirm the change out loud with a person you know at the vendor. Third, ask the Approver to sign off on the change in [where the sign-off is recorded, e.g. an approval field on the vendor record] before anyone edits the record. Fourth, update the record, then return to step 2 for each held invoice. If the vendor does not confirm, keep the record unchanged, leave the invoices on hold, and tell the Owner the same business day.
- **If** An invoice comes from a vendor that is not on the approved vendor list (new vendor). **Then:** First, hold the invoice. Second, send the request for missing vendor information (step 2) asking for a W-9 or equivalent and bank details. Third, phone the vendor at a number you found independently, not one from the invoice, and confirm the bank details out loud. Fourth, the Approver signs off on adding the vendor in [where the sign-off is recorded]. Fifth, add the vendor to the approved vendor list. Then return to step 2. If the vendor has not sent the missing items within [N] business days, tell the Approver and leave the invoice on hold.
- **If** The invoiced amount does not match the purchase order. **Then:** Step 3 covers this. Hold payment, send the discrepancy notice to the vendor and the internal requester, and record the resolution on the invoice record before releasing any payment.
- **If** A payment is due but the required Approver is unavailable. **Then:** Send the request to the backup Approver for that tier named on your worksheet, as in step 4. Do not release the payment without a workflow stamp from an Approver.

## Quality checklist

- [ ] Every invoice logged the day it is received, with a search for duplicates recorded
- [ ] Vendor found on the approved vendor list; sender domain and remit-to details compared to the vendor record
- [ ] New vendors have a W-9 and callback-verified banking on file before payment
- [ ] Three-way match completed (purchase order, receiving confirmation, invoice), or the reason for no purchase order noted
- [ ] Expense coded to the correct account and the Approver named per the approval matrix
- [ ] Approval recorded as a workflow stamp before payment is released
- [ ] Any new or changed bank details verified by callback to a number already on file, with the Approver's sign-off
- [ ] Payment amount and destination compared to the approved invoice, and a second person released any payment at or above the second-release amount
- [ ] Payment marked paid with date, method, and confirmation ID, reconciled to the bank statement, and filed in [paid folder]

## Common mistakes

- **Mistake:** Paying a vendor invoice with new bank details without a callback. **Fix:** For every bank-detail change: use the bank detail change entry in the troubleshooting section, with a callback to a number already on file and the Approver's sign-off, even when you are in a hurry.
- **Mistake:** Skipping the three-way match on rush payments. **Fix:** Keep the match mandatory for anything with a purchase order. If there is no purchase order, note the reason on the invoice record and get the Approver's workflow stamp instead of skipping the control.
- **Mistake:** One person can log, approve, and pay every invoice. **Fix:** Set up the approval matrix inside your AP software so a payment above the AP Clerk's tier cannot be released without the named Approver's stamp.
- **Mistake:** Filing invoices inconsistently so nobody can confirm whether something was already paid. **Fix:** Use the same naming format and the same [unpaid folder] and [paid folder] for every vendor.
- **Mistake:** Calling the phone number printed on the invoice or the change request to verify a bank change. **Fix:** Use only a number already on the vendor record from before the request arrived.

## How to know it is working

- Vendors are paid on or before terms with no recurring late-payment disputes.
- No duplicate payments and no payments released to unverified bank details occur.
- Every payment above Tier 1 has an Approver's workflow stamp on file.
- AP aging and cash forecasts stay accurate because every invoice is logged and reconciled promptly.

| Metric | Target |
| --- | --- |
| On-time payment rate | [Your target, e.g. 95 percent or more of invoices paid by the due date] |
| Duplicate or erroneous payment rate | Zero |
| Invoice processing time, receipt to payment | Within your standard terms window |
| Invoices held more than [N] business days for approval | [Your target] |

## Related procedures

- Purchase Order Approval
- Client Invoicing
- Monthly Reporting
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

Template by Pro Sulum. Online version with a fillable worksheet: https://www.prosulum.com/sops/templates/vendor-payment/

Free to use and adapt for your own business, licensed CC BY 4.0: credit Pro Sulum (prosulum.com) if you republish it.
