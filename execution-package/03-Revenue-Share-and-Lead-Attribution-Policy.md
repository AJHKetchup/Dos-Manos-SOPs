# Revenue Share and Lead Attribution Policy

Policy draft for determining when a participant earns 10% of collected revenue.

Use before the participant starts booking or claiming approved jobs. This policy should also be checked during monthly reviews and before any revenue share payment is approved.

## Purpose

This policy defines when a participant may receive 10% of collected revenue on approved jobs and how Dos Manos attributes leads during the Operator Track and Territory Operator stage.

The goal is to prevent confusion about payment, lead credit, territory credit, refunds, chargebacks, unpaid balances, claims, and customer issues.

## Current Compensation Structure

Participants are paid normally for field work they perform.

Participants may also receive 10% of collected revenue on approved jobs, in addition to normal field pay for field work performed.

Normal field pay and program revenue share should be treated as separate questions. A participant may be paid for field work performed even if a job does not qualify for the 10% revenue share.

Working payroll default: for employees, treat the 10% as employee compensation through payroll, likely as commission, bonus, or supplemental wages, until CPA/payroll counsel gives final classification. Use the safer assumption that revenue share may affect overtime calculations for non-exempt employees until counsel/payroll confirms otherwise.

Future compensation arrangements may change based on role, stage, territory, location maturity, and company policy.

This policy does not create a guarantee of future work, promotion, territory assignment, General Manager role, ownership, cash-flow participation, profit participation, buy-in rights, or any specific future compensation structure.

## Collected Revenue

Collected revenue means revenue Dos Manos has actually been paid for the job under company collection standards.

Supermove should be treated as the central job record whenever possible. QuickBooks or accounting records should confirm payment status, collected revenue, refunds, chargebacks, unpaid balances, and payment timing before revenue share is approved.

Working verification default: Alex or the bookkeeper verifies payment in QuickBooks or the approved accounting record. Bryan confirms the job was completed properly and has no known major service issue. Alex and Bryan approve exceptions.

## Accounting Control Points

| Control | Required check |
| --- | --- |
| Job exists | Job is in Supermove or the approved record. |
| Customer payment | Payment is visible in QuickBooks or the approved accounting record. |
| Collected amount | Amount used for revenue share matches accounting record. |
| Refund/chargeback | Accounting confirms none exists or treatment is approved. |
| Unpaid balance | Accounting confirms balance status. |
| Claim/customer issue | Operations confirms no unresolved blocker. |
| Payout approval | Manager and payroll/accounting approve before payment. |

Collected revenue does not include:

- Deposits before the job is completed and collected under company standards.
- Amounts refunded to the customer.
- Chargebacks.
- Unpaid balances.
- Amounts tied to unresolved claims.
- Amounts tied to major unresolved customer issues.
- Amounts outside approved Dos Manos billing and collection channels.

Deposits do not trigger the 10% revenue share by themselves.

Canceled or rescheduled jobs do not trigger revenue share unless the job is later completed, collected, and approved under this policy. Deposit, cancellation, refund, or reschedule treatment must follow company policy and accounting review.

## Operator Track Approved Jobs

At the Operator Track stage, an approved job is a job that:

- The participant personally brings in or books.
- Follows Dos Manos pricing guidelines.
- Follows Dos Manos service standards.
- Is entered into Supermove or reported through the approved Dos Manos process.
- Is completed under the Dos Manos brand.
- Is collected from the customer.

The participant must either enter the lead in Supermove or notify management so the lead can be tracked before payment approval.

## Territory Operator Approved Jobs

At the Territory Operator stage, an approved job is a job booked through that territory's approved advertising or lead channels.

Approved territory channels may include:

- Territory phone number.
- Territory website page.
- Territory quote form.
- Territory social media.
- Local ads.
- Territory referral sources.
- Other approved territory-tracked channels.

Territory Operator jobs must still follow Dos Manos pricing guidelines, service standards, Supermove process, billing and collection standards, and claims/customer issue standards.

## Lead Attribution Rules

### Operator Track

During the Operator Track, attribution is based on the participant personally bringing in or booking the job.

To receive credit, the participant must:

- Record the lead in Supermove, or notify management so the lead can be recorded.
- Identify the source of the lead.
- Connect the lead to the customer name, phone number, job date, and job address.
- Avoid duplicate claims with other participants or company channels.
- Keep communication inside approved Dos Manos channels when required by management.

If a lead is not tracked, management may deny revenue share credit.

Operator Track source tags:

- `OPTRACK_[ParticipantName]`
- `OPTRACK_[ParticipantName]_REFERRAL`
- `OPTRACK_[ParticipantName]_PERSONAL`
- `OPTRACK_[ParticipantName]_FOLLOWUP`

### Territory Operator Stage

At the Territory Operator stage, attribution is based primarily on inbound source.

Examples:

- Customer calls the territory phone number.
- Customer submits the territory quote form.
- Customer comes through the territory website page.
- Customer messages the territory social account.
- Customer responds to a local ad assigned to the territory.
- Customer is referred by a territory referral partner assigned in Supermove or the approved referral tracker.

If the source is unclear, management decides attribution based on Supermove records, call records, form records, ad records, referral notes, QuickBooks/payment records, and customer statements.

Territory source tags:

- `TERR_[Territory]_PHONE`
- `TERR_[Territory]_WEBPAGE`
- `TERR_[Territory]_QUOTEFORM`
- `TERR_[Territory]_GOOGLEADS`
- `TERR_[Territory]_METAADS`
- `TERR_[Territory]_SOCIAL_FB`
- `TERR_[Territory]_SOCIAL_IG`
- `TERR_[Territory]_REF_[PartnerName]`
- `TERR_[Territory]_REPEAT`
- `TERR_[Territory]_WALKIN_OR_DIRECT`

## Split Or Disputed Attribution

If two participants claim the same job, management reviews:

- Who first identified the lead.
- Who booked the job.
- Which channel the customer used.
- Whether the lead was already in Supermove or the approved Dos Manos process.
- Whether the customer was already an active Dos Manos customer.
- Whether the job was generated by a territory channel.
- Whether each participant followed the tracking process.

Management may assign full credit, split credit, defer payment until facts are clear, or deny credit if the lead was not handled properly.

Default dispute priority:

1. Supermove source tag.
2. Dedicated territory phone, form, page, ad, or social source.
3. Written referral record.
4. Customer statement.
5. Management decision.

## Dispute Resolution Process

If a participant disagrees with a revenue share or attribution decision:

1. Participant identifies the specific job/customer and disputed decision.
2. Manager reviews Supermove, call/form/ad/referral records, QuickBooks/accounting records, and issue/claim status.
3. Manager documents the decision or escalates to ownership/leadership if needed.
4. Payroll/accounting processes payment only after the final decision is recorded.

Disputes should be based on records, not memory or informal claims.

## Jobs That Are Not Eligible

A job is not eligible for the 10% revenue share if:

- It was not entered into Supermove or reported through the approved Dos Manos process.
- It did not follow Dos Manos pricing guidelines.
- It did not follow Dos Manos service standards.
- It was not completed under the Dos Manos brand.
- It was not collected from the customer.
- It resulted in a refund.
- It resulted in a chargeback.
- It has an unpaid balance.
- It resulted in a claim.
- It has a major unresolved customer issue.
- The participant made an unapproved arrangement outside the approved Dos Manos process.
- The participant misrepresented pricing, availability, service terms, or company approval.
- The job violates company policy or legal/regulatory requirements.
- The job was an interstate move performed without the required federal authority or compliance approval.

Approved pricing exceptions do not automatically make a job ineligible, but the exception must be documented and approved by management. Unapproved discounts, side arrangements, or misquotes may make the job ineligible.

## Practical Examples

| Scenario | Eligible? | Reason |
| --- | --- | --- |
| Participant books a customer, enters the lead in Supermove, the job follows pricing guidelines, is completed well, and the customer pays in full. | Yes, if approved | The job meets Operator Track approved job requirements and collected revenue is confirmed. |
| Participant talks to a customer but does not enter or report the lead, and management cannot confirm attribution. | Usually no | The lead was not tracked properly. |
| Customer pays a deposit but the job has not been completed. | No | Deposits do not trigger the 10% revenue share by themselves. |
| Job is completed but the customer has an unpaid balance. | No until resolved | Collected revenue has not been fully confirmed under company standards. |
| Customer receives a refund or chargeback. | No, unless management makes a specific exception | Refunds and chargebacks make the job ineligible under this policy. |
| Territory lead comes through the territory phone number and is completed under Dos Manos standards. | Yes, if collected and approved | Territory attribution is based on approved territory-tracked channels. |
| Referral partner sends a job and the partner is eligible for a 5% referral fee. | Separate review | Affiliate referral fees are separate from the participant's 10% revenue share. |

## Calculation Examples

These examples are for plain-English understanding only. Payroll/accounting controls the actual payment process.

| Job result | Collected revenue basis | Revenue share result |
| --- | ---: | ---: |
| Job completed and customer paid $1,200 in full. | $1,200 | $120 if approved. |
| Customer paid $300 deposit but job is not completed yet. | $0 for revenue share timing | No revenue share yet. |
| Job billed at $1,500, customer paid $1,000, and $500 remains unpaid. | $0 until management/accounting approves treatment | Usually no revenue share while unpaid balance remains. |
| Job paid $1,500, then $300 refunded. | $0 unless management/accounting approves treatment | Refund generally makes the job ineligible under this policy. |
| Job paid $900 but has an unresolved claim. | $0 until claim is resolved and management approves eligibility | Claim can make the job ineligible. |

## Referral / Affiliate Program Interaction

Dos Manos may separately pay referral partners or affiliates, generally 5% of the referred moving job after Dos Manos is paid by the customer.

Affiliate referral fees are separate from the Accelerated Management Program 10% revenue share. A participant should not promise referral fees, split fees, or special payment arrangements unless management has approved the referral partner, tracking source, W-9 process, and payout terms.

If a participant recruits a referral partner, management must decide whether that activity is credited as participant business development, affiliate program activity, or both. The decision should be recorded in Supermove, the referral partner tracker, or another approved management record before payment is approved.

Referral partners may need W-9 collection and 1099-NEC review if payments meet reporting thresholds. Participants should not give tax advice to referral partners.

If a job could trigger both a participant revenue share and a referral partner payout, management must approve the combined treatment before payment. Do not assume the 10% participant revenue share and 5% referral fee automatically stack on the same job.

Working stacking rule: at Territory Operator stage, the 5% referral partner fee and 10% Territory Operator revenue share may stack if both are approved, tracked, and the referral source is an approved territory channel. During the Operator Track, stacking requires management approval before payment.

## Payment Review Process

Use this process before approving revenue share:

1. Confirm the job is completed in Supermove or the approved job record.
2. Bryan/operations confirms no major service issue.
3. Confirm the customer paid Dos Manos in QuickBooks or the approved accounting record.
4. Confirm there is no refund, chargeback, unpaid balance, claim, or major unresolved customer issue.
5. Confirm the job was priced and performed under Dos Manos standards.
6. Confirm the lead was tracked in Supermove or an approved tracking record.
7. Confirm the participant or territory attribution.
8. Alex/Bryan approve the 10% revenue share for payroll or accounting processing.
9. Update the Operator Performance Tracker or payment log.

Working payment timing: pay on the next regular payroll after the job is completed, collected revenue is confirmed, attribution is approved, and no known claim or major customer issue exists. Do not promise off-cycle payment unless management and payroll/accounting approve it.

Referral partner payments follow the separate affiliate/referral process. A prior target was 7-10 business days after Dos Manos is paid by the customer, but management should confirm the current payout timing before promising it.

## Revenue Share Hold Reasons

Revenue share may be held pending review if:

- Collected revenue has not been confirmed in QuickBooks or accounting records.
- The job has an unpaid balance.
- A refund or chargeback is possible.
- A claim, damage issue, or major customer complaint is unresolved.
- Lead attribution is disputed.
- The job source is unclear.
- The job was not entered or reported through Supermove or the approved process.
- Pricing guideline compliance is unclear.
- Management needs to review an exception.

If payment is held, management should record the reason, owner, and next review date.

For partially paid jobs, the safer rollout rule is to hold revenue share until the job is fully collected unless management approves partial payout. If a claim opens after payout, flag the job and get legal/payroll review before any future offset or wage deduction. Do not create an automatic clawback without review.

## Revenue Share Hold Log

| Job/customer | Participant | Hold reason | Owner | Next review date | Final decision |
| --- | --- | --- | --- | --- | --- |
|  |  |  |  |  |  |

## Approval Roles

| Role | Responsibility |
| --- | --- |
| Participant | Enters or reports the lead, source, job facts, and follow-up activity. |
| Manager | Confirms attribution, pricing discipline, and eligibility. Default first manager: Bryan Abrego. |
| Operations | Confirms completion, claims/customer issue status, and service-standard concerns. Default owner: Bryan Abrego. |
| Accounting/payroll | Confirms collected revenue, payment status, payroll/accounting treatment, and payout timing. Default verifier: Alex/bookkeeper until delegated. |
| Owner/leadership, if needed | Alex and Bryan resolve disputes, exceptions, or unusual payment questions. |

## Exceptions

Exceptions should be rare and documented.

| Exception question | Required answer |
| --- | --- |
| What policy requirement was not met? |  |
| Why is management considering an exception? |  |
| Who approved the exception? |  |
| Was collected revenue confirmed in QuickBooks or accounting records? | Yes / No |
| Were job quality, claims, and customer issues reviewed? | Yes / No |
| Does the exception create a precedent? | Yes / No |
| How will the precedent be avoided or handled next time? |  |

Do not use exceptions to fix poor lead tracking, side arrangements, or repeated failure to follow the approved Dos Manos process.

## Revenue Share Approval Log

| Field | Entry |
| --- | --- |
| Participant |  |
| Stage | Operator Track / Territory Operator |
| Customer name |  |
| Job date |  |
| Job number |  |
| Supermove project/job link |  |
| Lead source |  |
| Gross job revenue |  |
| Collected revenue |  |
| QuickBooks/payment confirmation |  |
| Refunds or chargebacks |  |
| Claims or unresolved issues |  |
| Approved revenue share amount |  |
| Bryan operational approval |  |
| Alex/payment approval |  |
| Payroll period |  |
| Payroll/accounting processing date |  |
| Payment date |  |
| Notes |  |

## Internal Acceptance Check

Before using this policy, management should confirm:

- The definition of collected revenue is clear.
- Operator Track approved jobs are clear.
- Territory Operator approved jobs are clear.
- Supermove/source tracking is required.
- Disputed attribution has a decision process.
- Refunds, chargebacks, unpaid balances, claims, and unresolved customer issues are handled.
- The Operator Performance Tracker has enough fields to support payment review.

## Final Review Items

- Payroll/accounting should confirm whether the 10% revenue share is treated as commission, bonus, supplemental wages, or another category.
- Counsel/payroll should review whether revenue share payments affect overtime calculations for nonexempt employees.
- Counsel should confirm employee versus contractor classification language and avoid any assumption that a participant can be treated as a contractor because of revenue share.
- Counsel should review territory and location-level language to avoid accidental franchise implications.
- Insurance and claims handling should confirm when claim activity makes a job ineligible.
- Accounting should confirm W-9 and 1099-NEC handling for affiliate/referral payments.

Research notes:

- IRS Publication 15, supplemental wages including bonuses and commissions: https://www.irs.gov/publications/p15
- U.S. Department of Labor Fact Sheet 56A, regular-rate overview: https://www.dol.gov/agencies/whd/fact-sheets/56a-regular-rate
- U.S. Department of Labor guidance on bonuses under the FLSA: https://www.dol.gov/agencies/whd/fact-sheets/56c-bonuses
- IRS independent contractor definition and worker classification guidance: https://www.irs.gov/businesses/small-businesses-self-employed/independent-contractor-defined
- IRS Form W-9 overview: https://www.irs.gov/forms-pubs/about-form-w-9
- IRS Form 1099-NEC overview: https://www.irs.gov/forms-pubs/about-form-1099-nec
- FTC Franchise Rule: https://www.ftc.gov/legal-library/browse/rules/franchise-rule
