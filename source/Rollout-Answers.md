# Program Policy Defaults

These are the current rollout answers for completing the Dos Manos Moving Accelerated Management Program execution package for live use.

This file resolves business-policy ambiguities that can be decided by company leadership. Items involving payroll law, tax treatment, ICC compliance, interstate authority, insurance, customer contract language, employment classification, referral tax reporting, and location-level economic structures still require professional review before broad rollout.

## Approval And Decision Authority

- Bryan Abrego is CEO and final operating authority for the program unless he delegates authority in writing.
- Bryan Abrego has final authority over pricing, discounts, operational exceptions, special pricing, revenue-share eligibility, partial-payment treatment, claims, refunds, repairs, settlements, denials, insurance submissions, referral payout approval, territory assignment, territory pause/reassignment, Formal Location review, and program exceptions.
- Alex Heinz may support program documentation, tracking, business structure, accounting review, public-facing copy, and administrative setup where assigned, but final authority rests with Bryan Abrego unless otherwise delegated.
- Management records should show Bryan Abrego approval for any major exception, payout dispute, claim/refund decision, territory launch, or Formal Location decision.

## Candidate Selection Defaults

- Candidates should sign an acknowledgment before entering the Operator Track.
- Outside hires must complete normal hiring, onboarding, background, safety, and driver qualification steps where applicable.
- Outside hires must also complete a probationary field period before Operator Track acceptance.
- Prior sales, management, or moving experience does not skip the Operator Track.
- Selection scoring is a management tool, not an automatic acceptance rule.

## Pricing And Booking Defaults

- Current minimum job revenue / minimum job cost: $450, subject to the CEO-approved Dos Manos Pricing Policy.
- Operators may not approve discounts, special pricing, waived charges, free labor, free transportation, or side arrangements.
- Bryan Abrego approves pricing exceptions, operational exceptions, and recurring rule changes.
- Recurring exceptions should be added to the Dos Manos Pricing Policy.
- Detailed rate rules belong in the separate Dos Manos Pricing Policy, not in the Accelerated Management Program execution package.

### Current Pricing Reference

Local moves, hourly ranges:

| Crew size | Hourly range |
| ---: | ---: |
| 2 movers | $140-$155 |
| 3 movers | $175-$190 |
| 4 movers | $210-$225 |
| 5 movers | $245-$260 |

Labor-only, hourly ranges:

| Crew size | Hourly range |
| ---: | ---: |
| 2 movers | $130-$145 |
| 3 movers | $165-$180 |
| 4 movers | $200-$215 |
| 5 movers | $230-$245 |

Truck and transportation fees:

| Distance | Fee |
| ---: | ---: |
| 0-20 miles | $175 |
| 20-30 miles | $225 |
| 35+ miles | Special Pricing |

U-Haul rental: $150 flat + $2.25 per mile.

Current range rules:

- Peak pricing if: two bookings / capacity pressure, Chicago jobs, or more than 25 miles.
- Low end = easy jobs.
- Mid range = standard jobs.
- High end = tight schedule / high demand.

Pricing Policy build questions include final rate-selection authority, minimum-hours rules, mileage calculation, the 30-35 mile transportation-fee gap, U-Haul treatment, materials, specialty items, deposits, cancellation rules, and the exact revenue-share base.

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
- Bryan Abrego approval for pricing exception, if applicable.

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

Leads not entered on time are not eligible for revenue share unless Bryan Abrego can verify the lead source before approval. Repeated failure counts against Supermove discipline and promotion readiness.

## QuickBooks And Payment Verification

- Supermove is the job record. QuickBooks or approved accounting records confirm collected revenue and payment status.
- Proof of payment may include a QuickBooks paid invoice, payment receipt, bank/merchant deposit record, or reconciled payment record tied to the Supermove job.
- Deposits do not trigger the 10% revenue share by themselves.
- Refunds, chargebacks, unpaid balances, claims, and major unresolved customer issues place the revenue-share decision on hold unless Bryan Abrego approves treatment.

Approval workflow:

1. Job completed in Supermove.
2. Job quality / service status reviewed.
3. QuickBooks or approved accounting record confirms collected revenue.
4. Source/attribution confirmed.
5. Revenue-share amount calculated using CEO-approved rules.
6. Bryan Abrego approves any exception, dispute, partial payment, claim/refund issue, or unusual treatment.
7. Paid through payroll, month-end, accounting run, or another CEO-approved payment process.
8. Tracker updated.

## Revenue Share Defaults

- Participants may receive 10% of collected revenue on approved jobs, in addition to normal field pay for field work performed.
- For employees, treat the 10% as employee compensation through payroll until CPA/payroll counsel gives final classification.
- Safe assumption: revenue share may affect overtime calculations for non-exempt employees.
- Revenue-share timing may vary by company process. Approved timing methods may include next regular payroll, month-end, a scheduled accounting/payment run, or another CEO-approved payout cycle.
- Required controls before payment: job completion, collected revenue confirmation, attribution approval, and review of any customer issue, claim, refund, chargeback, unpaid balance, or exception.
- Partially paid jobs are handled by Bryan Abrego's decision. Do not create an automatic partial-payment payout rule.
- Claims opened after payout should be flagged. Any offset or clawback requires legal/payroll review before wage deduction.

Attribution dispute priority:

1. Supermove source tag.
2. Dedicated territory phone/form/page/ad/social source.
3. Written referral record.
4. Customer statement.
5. Bryan Abrego decision.

If unclear, Bryan Abrego may split, deny, defer, or approve credit based on the records.

## Referral / Affiliate Program Defaults

- Official referral fee: 5% of collected revenue on approved referred jobs, subject to exceptions.
- Referral partners are paid at month end for now.
- Referral payment requires proper tracking, Dos Manos collection from the customer, management approval, and a W-9-backed process.
- W-9 collection: admin/bookkeeper, with Bryan Abrego responsible until delegated.
- 1099-NEC review/reporting: bookkeeper/CPA.
- Operator Track participants may recruit referral partners before territory assignment only with Bryan Abrego approval.
- Participants may not promise referral terms, territory exclusivity, special pricing, customer ownership, or payment timing without Bryan Abrego approval.

## Claims And Service Recovery Defaults

- Bryan Abrego receives damage reports and customer-issue escalations first unless he delegates intake.
- Bryan Abrego has final authority over repairs, refunds, settlement offers, denials, insurance submissions, and whether a claim affects revenue-share eligibility.
- Operators must document facts and escalate. Operators must not admit fault, promise payment, interpret insurance, waive charges, or promise claim outcomes.
- Required documentation: job number, customer name, date, photos/video, item description, claimed damage, location, pre-existing condition if known, crew notes, customer statement, bill of lading/estimate, inventory if applicable, and repair/replacement estimate if available.
- Immediate escalation: injury, truck accident, police involvement, major property damage, high-value item damage, customer legal/ICC/review threat, missed pickup, payment refusal, crew conflict, or insurance issue.
- Service response target: same day when practical, no later than 24 hours for complaints where possible. Formal legal claims follow required written claim timelines.

## Compliance And Insurance Defaults

- Illinois intrastate moves require ICC-compliant estimate, Consumer Guide confirmation, bill of lading/freight bill, valuation election, inventory when required, and vehicle/cab-card documentation as applicable.
- Final policy/legal review: Bryan Abrego with counsel as needed.
- Interstate move policy: do not book interstate household goods moves unless FMCSA/U.S. DOT authority and required interstate documents are confirmed.
- FMCSA/U.S. DOT authority: not documented. Do not represent that Dos Manos has interstate household goods authority until verified.
- COI/additional insured requests: central administration/ownership through insurance agent. Operators should not issue or modify COIs.
- Operator insurance statement: "We are licensed and insured for the work we are authorized to perform, and our office can provide the appropriate certificate if needed."

## Contract And Legal Terms

- Supermove hold-harmless/liability language is not documented and needs contract review.
- Counsel review of customer contract is not documented.
- Operators should say: "We'll document it and get it to management so it can be handled through the company's claims process."
- Operators should not admit fault, promise payment, interpret insurance, waive charges, or make side arrangements.
- Customer ownership, referral partner ownership, confidentiality, and non-solicitation should be added to the Operator Acknowledgment, Referral Partner Agreement, and company policy set.

## Territory Defaults

- Do not write the package around a single first territory. Territory documents must be evergreen.
- Current location context: Dos Manos calls its primary location Naperville. The secondary advertised location currently being advertised is River Grove.
- Territory assignment is not contingent on a fixed number of completed jobs.
- Territory creation and placement should consider market fit, customer demand, referral density, wealth/home-value profile, operating capacity, crew/truck access, dispatch burden, claims risk, current brand coverage, trackable inbound channels, and Bryan Abrego's final judgment.
- Public local address/listing: do not use casually. No random virtual address or fake local office; review Illinois household goods advertising rules before listing any address where authorized employees are not on duty during normal business hours.

Recommended territory-assignment signals:

- Operator shows customer judgment, pricing discipline, service quality, documentation discipline, crew leadership, and trust.
- Dos Manos is prepared to expand or advertise that territory.
- The territory has practical crew/truck/dispatch coverage.
- The market has a believable local customer base and referral opportunity.
- The inbound channels can be tracked cleanly through phone, page, form, social, ads, referrals, and Supermove.
- Bryan Abrego is comfortable with the operator representing Dos Manos locally.

## Formal Location Defaults

- Formal Location review requires at least six months of territory activity.
- Use only actual Supermove, QuickBooks, claims, reviews, referral, and operational data from the assigned territory. No pro forma-only promotion.
- Margin target: positive contribution margin after labor, truck/rental, materials, fuel, direct marketing, claims, and referral/revenue-share payouts.
- Labor benchmark: roughly 35% of revenue.
- Asset plan: mixed/rental-first until volume proves dedicated assets.
- Startup capital: lean tracking/referral/ads first; rented trucks before owned/dedicated assets unless proven by volume and margin.
- Location-level economics review: Bryan Abrego with bookkeeper/CPA and legal/tax review where applicable.
- General Manager promotion approval: Bryan Abrego unless delegated.
- Cash-flow/profit/phantom equity/buy-in/ownership approval: Bryan Abrego / ownership group with attorney and CPA review.

## Primary Source Links Used For Compliance Review

- Illinois Commerce Commission Applicant's Handbook for Household Goods Moving Service within Illinois: https://icc.illinois.gov/downloads/public/mc/HHGHandbook.pdf
- Illinois Commerce Commission Household Goods Movers authority page: https://icc.illinois.gov/authority/household-goods-movers
- IRS Publication 15, Employer's Tax Guide: https://www.irs.gov/publications/p15
- U.S. Department of Labor Fact Sheet 56A, Regular Rate of Pay: https://www.dol.gov/agencies/whd/fact-sheets/56a-regular-rate
- FMCSA Types of Operating Authority: https://www.fmcsa.dot.gov/registration/types-operating-authority
