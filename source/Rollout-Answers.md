# Working Rollout Answers

These are working rollout answers for completing the Dos Manos Moving Accelerated Management Program execution package for first live use.

They are operational defaults, not final legal, tax, payroll, insurance, or compliance advice. Items involving candidate-facing legal language, payroll treatment, wage/hour rules, ICC compliance, interstate authority, referral tax reporting, insurance, customer contract terms, territory rights, and location-level economic structures still require professional review before broad rollout.

## Approval And Decision Authority

- Program Brief final approval: Alex Heinz and Bryan Abrego jointly.
- Alex approves candidate-facing language, business structure, policy exceptions, revenue-share exceptions, and public launch copy.
- Bryan approves operations reality, candidate operational readiness, pricing/dispatch feasibility, claims/service facts, and day-to-day execution.
- Luis Abrego may provide operational input when involved, but central management should make program decisions.
- First participant manager responsible: Bryan Abrego, with Alex reviewing program-stage decisions and revenue-share approvals.
- First participant rollout sign-off: Alex Heinz and Bryan Abrego.

## Candidate Selection Defaults

- Candidates should sign an acknowledgment before entering the Operator Track.
- Outside hires are eligible only after normal hiring, background, safety, and driver qualification steps are complete.
- Selection scoring thresholds should be used as a pilot standard, not a legal entitlement or automatic decision rule.
- Prior sales, management, or moving experience does not skip the Operator Track.

## Pricing And Booking Defaults

- Working minimum job revenue / minimum job cost: $450.
- No discounts unless approved.
- Bryan approves operational/pricing exceptions.
- Alex approves policy exceptions.
- Recurring exceptions should be added to the pricing guide.
- Exact hourly rates, crew/truck rates, travel time, materials, stair/heavy-item charges, and tariff-specific pricing still need to be inserted.

## Supermove Defaults

Supermove is the central job-management record whenever possible.

Required lead fields:

- Customer name.
- Phone.
- Email.
- Pickup address / ZIP.
- Delivery address / ZIP, if known.
- Move date or target window.
- Move type.
- Lead source.
- Referring person / partner, if any.
- Assigned operator / participant.
- Lead status.
- Notes on job size/scope.
- Next follow-up date.

Required before booking:

- Written estimate completed/sent.
- Estimate accepted.
- Crew/truck plan.
- Pricing/rate/minimum confirmed.
- Inventory/scope notes.
- Specialty items.
- Access issues.
- Deposit/payment terms.
- Customer documents sent/signed.
- Source/attribution confirmed.
- Pricing exception approval, if applicable.

Operator Track source tags:

- `OPTRACK_[ParticipantName]`
- `OPTRACK_[ParticipantName]_REFERRAL`
- `OPTRACK_[ParticipantName]_PERSONAL`
- `OPTRACK_[ParticipantName]_FOLLOWUP`

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

Referral tags:

- `REF_[PartnerName]`
- `REF_REALTOR_[PartnerName]`
- `REF_PM_[PartnerName]`
- `REF_SENIOR_[PartnerName]`
- `REF_CONTRACTOR_[PartnerName]`
- `TERR_[Territory]_REF_[PartnerName]`

Bryan owns operational enforcement. Alex or admin/back office may own setup, naming conventions, and audit review.

Leads not entered on time are not eligible for revenue share unless management can verify the lead source before the job is booked/completed. Repeated failure counts against Supermove discipline and promotion readiness.

## QuickBooks And Payment Verification

- Supermove to QuickBooks connection behavior still needs confirmation.
- Working verifier: Alex/bookkeeper verifies payment in QuickBooks; Bryan confirms job completion and no known major service issue.
- Proof of payment: QuickBooks paid invoice, payment receipt, bank/merchant deposit record, or reconciled payment record tied to the Supermove job.
- Deposits do not trigger the 10% revenue share.
- Refunds, chargebacks, unpaid balances, and claims make the job ineligible or place it on hold under the working policy.

Approval workflow:

1. Job completed in Supermove.
2. Bryan/operations confirms no major service issue.
3. QuickBooks confirms collected revenue.
4. Source/attribution confirmed.
5. Revenue-share amount calculated.
6. Alex/Bryan approve.
7. Paid through payroll or approved payment process.
8. Tracker updated.

## Revenue Share Defaults

- For employees, treat the 10% as employee compensation through payroll, likely commission/bonus/supplemental wages, until CPA/payroll counsel gives final classification.
- Safe assumption: revenue share may affect overtime calculations for non-exempt employees.
- Recommended payment timing: next regular payroll after job completion, collected revenue confirmation, attribution approval, and no known claim/major customer issue.
- Exceptions: Alex and Bryan approve.
- Referral payout and participant revenue share can stack only when both are approved and tracked.
- At Territory Operator stage, referral partner 5% and Territory Operator 10% can stack if the referral source is an approved territory channel.
- At Operator Track, stacking requires management approval.
- Partially paid jobs: safer rollout rule is hold until fully collected unless management approves partial payout.
- Claims opened after payout: flag the job. Any future offset/clawback needs legal/payroll review before wage deduction.

Attribution dispute priority:

1. Supermove source tag.
2. Dedicated territory phone/form/page/ad/social source.
3. Written referral record.
4. Customer statement.
5. Management decision.

If unclear, management may split, deny, or defer credit.

## Referral / Affiliate Program Defaults

- Referral partner approval: Alex and Bryan.
- Official referral fee: 5% of collected revenue on approved referred jobs, subject to exceptions.
- Referral partners are paid after Dos Manos is paid, the job is completed, no refund/chargeback/unpaid balance exists, and W-9/payment information is on file.
- W-9 collection: admin/bookkeeper, with Alex responsible until delegated.
- 1099-NEC review/reporting: bookkeeper/CPA.
- Operator Track participants may recruit referral partners before territory assignment only with management approval.
- Participants may not promise referral terms, territory exclusivity, special pricing, or ownership of the relationship.

## Claims And Service Recovery Defaults

- Bryan/Operations receives damage reports first.
- Alex is copied for material claims, payment issues, legal threats, ICC exposure, or insurance exposure.
- Required documentation: job number, customer name, date, photos/video, item description, claimed damage, location, pre-existing condition if known, crew notes, customer statement, bill of lading/estimate, inventory if applicable, and any repair/replacement estimate.
- Immediate escalation: injury, truck accident, police involvement, major property damage, high-value item damage, customer legal/ICC/review threat, missed pickup, payment refusal, crew conflict, or insurance issue.
- Claim impact on revenue share: Bryan determines operational facts; Alex approves compensation eligibility.
- Service response standard: same day when possible, no later than 24 hours for complaints. Formal legal claims follow required written claim timelines.

## Compliance And Insurance Defaults

- Illinois intrastate moves require ICC-compliant estimate, Consumer Guide confirmation, bill of lading/freight bill, valuation election, inventory when required, and vehicle/cab-card documentation as applicable.
- Day-to-day ICC execution: Bryan.
- Final policy/legal review: Alex with counsel as needed.
- Interstate move policy: do not book interstate household goods moves unless FMCSA/U.S. DOT authority and required interstate documents are confirmed.
- FMCSA/U.S. DOT authority: not confirmed. Do not represent that Dos Manos has interstate household goods authority until verified.
- COI/additional insured requests: central admin/ownership through insurance agent. Operators should not issue or modify COIs.
- Operator insurance statement: "We are licensed and insured for the work we are authorized to perform, and our office can provide the appropriate certificate if needed."

## Contract And Legal Terms

- Supermove hold-harmless/liability language is unknown and needs contract review.
- Counsel review of customer contract is not confirmed.
- Operators should say: "We'll document it and get it to management so it can be handled through the company's claims process."
- Operators should not admit fault, promise payment, interpret insurance, waive charges, or make side agreements.
- Customer ownership, referral partner ownership, confidentiality, and non-solicitation should be added to the Operator Acknowledgment, Referral Partner Agreement, and internal policy set.

## Territory Defaults

- First territory to consider: North Side / North Shore Chicago.
- Safer pilot alternative: defined DuPage / West Suburbs territory if Dos Manos wants less operational expansion risk.
- Working North Side / North Shore boundaries: Chicago North Side plus Evanston, Skokie, Wilmette, Winnetka, Glenview, Northbrook, Highland Park, Lake Forest, and nearby affluent suburbs. Must be tightened before launch.
- Territory tracking setup: Alex/admin for website, forms, phone, source tags, and reporting; Bryan for operational routing and dispatch process.
- Public launch copy approval: Alex for copy/brand/legal risk; Bryan for service area/operations accuracy.
- Public local address/listing: do not use casually. No random virtual address or fake local office; review Illinois household goods advertising rules before listing any address where authorized employees are not on duty during normal business hours.

Recommended threshold before territory assignment:

- At least 3-5 approved jobs personally brought in/booked.
- No major unresolved complaints.
- No serious avoidable claims.
- Clean Supermove usage.
- Follows pricing standards.
- Demonstrates customer communication.
- Demonstrates crew leadership.
- Completes weekly reporting.
- Management trusts the candidate to represent Dos Manos locally.

## Formal Location Defaults

- Use only Supermove, QuickBooks, claims, reviews, referral, and operational data from the assigned territory. No pro forma-only promotion.
- Working margin target: positive contribution margin after labor, truck/rental, materials, fuel, direct marketing, claims, and referral/revenue-share payouts.
- Labor benchmark: roughly 35% of revenue.
- Asset plan: mixed/rental-first until volume proves dedicated assets.
- Startup capital: lean tracking/referral/ads first; rented trucks before owned/dedicated assets unless proven by volume and margin.
- Location-level economics review: Alex, Bryan, bookkeeper/CPA.
- General Manager promotion approval: Alex and Bryan.
- Cash-flow/profit/phantom equity/buy-in/ownership approval: ownership group with attorney and CPA review.

## Primary Source Links Used For Compliance Review

- Illinois Commerce Commission Applicant's Handbook for Household Goods Moving Service within Illinois: https://icc.illinois.gov/downloads/public/mc/HHGHandbook.pdf
- Illinois Commerce Commission Household Goods Movers authority page: https://icc.illinois.gov/authority/household-goods-movers
- IRS Publication 15, Employer's Tax Guide: https://www.irs.gov/publications/p15
- U.S. Department of Labor Fact Sheet 56A, Regular Rate of Pay: https://www.dol.gov/agencies/whd/fact-sheets/56a-regular-rate
- FMCSA Types of Operating Authority: https://www.fmcsa.dot.gov/registration/types-operating-authority
