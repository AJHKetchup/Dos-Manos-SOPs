# Email Triage SOP

Status: Draft for internal review
Last updated: 2026-07-03
Owner: Management / assigned mailbox operator
Applies to: Humans and agents reviewing `owner@dosmanosmoving.com`

## Purpose

Keep the Dos Manos mailbox useful as both an action queue and a business log. Labels help route work, but they do not make it safe to hide, ignore, delete, or expose messages.

## Main rule

Inbox means current action queue. Labels and archive are business memory/logging tools. Never bulk archive, delete, trash, mark read, send, reply, forward, unsubscribe, or create persistent filters unless that exact action has been approved.

## Source inputs

- Email queue guide: `C:/Users/SLIB/Documents/DosManos-Agent-HQ/handoffs/email-queue-guide-current.md`
- Gmail dashboard: `C:/Users/SLIB/Documents/DosManos-Agent-HQ/manifests/gmail-operations-dashboard-current.md`
- Gmail body-learning summary: `C:/Users/SLIB/Documents/DosManos-Agent-HQ/manifests/gmail-inbox-body-learning-current.md`
- First-principles cleanup plan: `C:/Users/SLIB/Documents/DosManos-Agent-HQ/workflows/gmail-first-principles-cleanup-plan.md`
- Mailbox operations playbook: `C:/Users/SLIB/Documents/DosManos-Agent-HQ/agent-skills/mailbox-operations.md`

## Current mailbox model

The mailbox mixes four jobs:

1. Action queue: leads, quotes, customers, claims, COIs, payments, reviews, Supermove/job items.
2. System log: Google, Intuit/QuickBooks, Stripe, Supermove, ADP, insurance, security, purchasing, and other account notices.
3. Marketing/list feed: chambers, local platforms, newsletters, vendor promos, social/local notification feeds.
4. Permanent storage: old messages that were never archived after they stopped being actionable.

Treat cleanup as routing, not as a sweep.

## Core labels and queues

| Label | Use | Handling standard |
| --- | --- | --- |
| `Action Needed` | Unread/inbox items likely needing human review. | Keep visible until handled. |
| `New Leads and Quotes` | Quote requests, moving inquiries, possible leads. | Review quickly; collect move facts before quoting. |
| `Supermove` | Job/customer/system messages tied to operations. | Keep active scheduling/customer issues visible. |
| `QuickBooks and Payments` | Payment/accounting/admin notices. | Sensitive; do not broad archive. |
| `Insurance and COIs` | COI, insurance, certificate requests. | Sensitive; verify before action. |
| `Google Business Profile and Reviews` | GBP/maps/reviews/testimonials/platform notices. | Public replies/profile edits need approval. |
| `Claims, Refunds, and Damage` | Complaints, damage, claims, refunds. | Escalate; never auto-archive/delete. |
| `Automated Notifications` | System/list/no-reply messages. | Lowest-risk cleanup bucket only after rules and exclusions. |

Because `owner@dosmanosmoving.com` is already the company mailbox, do not create a redundant visible `Dos Manos/` label prefix.

## Same-day handling priorities

Review these the same day when practical:

- New lead or quote requests.
- Customer messages about active jobs, scheduling, access, elevator reservations, building rules, or scope changes.
- Claims, damage, refund, complaint, legal, chargeback, ICC, or public-review threats.
- COI, certificate, additional insured, or building compliance requests tied to a scheduled or quoted move.
- Supermove messages that may affect scheduling, dispatch, job status, or customer communication.
- Payment, QuickBooks, Stripe, bank, fraud, or collection problems that may affect a customer/job/vendor/account.
- Google Business Profile, review, or reputation items that need an owner-approved response.

## Triage steps

1. Start with unread inbox and `Action Needed` messages.
2. Identify whether the message is a lead, active customer/job issue, payment/admin item, platform log, list/marketing feed, or old/no-action record.
3. Apply or confirm the plain-language label that best routes the message.
4. Keep lead, customer, job, payment, COI, claims, review, and active operations messages visible until a human owner/operator has handled them.
5. Draft replies or next-action notes when useful, but do not send or reply without approval.
6. For lead messages, follow `03-Lead-Intake-and-Quote-Handoff-SOP.md`.
7. For claims, damage, refunds, insurance, ICC, or legal/compliance content, escalate instead of summarizing broadly.
8. For apparent list/no-reply/bulk messages, sample first and separate true business logs from non-critical subscription traffic.
9. Record safe counts, routing lessons, and queue summaries in Agent HQ. Keep raw subjects, snippets, message IDs, customer details, payment details, and claim details out of broad docs.

## What not to archive, delete, mark read, or hide automatically

Do not auto-hide:

- Lead or quote requests.
- Customer messages.
- Active job or Supermove messages.
- Claims, complaints, refunds, damage reports, legal threats, chargebacks, ICC issues, or review threats.
- Payment, QuickBooks, Stripe, banking, payroll, tax, or accounting notices.
- Insurance, COI, certificate, additional insured, or compliance messages.
- Google Business Profile, review, Maps, platform health, or public-listing messages.
- Security/fraud/access notices.
- Messages with attachments that may contain business records.

## Approval-gated actions

Ask before:

- Sending, replying, forwarding, or scheduling messages.
- Unsubscribing from any sender.
- Bulk archiving or broad archive rules.
- Marking batches read or unread.
- Deleting or trashing messages.
- Creating or changing persistent Gmail filters.
- Exposing raw sensitive email content outside approved restricted storage.

Label-only routing may be safe when scoped, reversible, logged, and specifically approved by the current operating plan.

## Escalation rules

Escalate immediately when an email includes:

- Damage, refund, complaint, claim, legal, ICC, chargeback, or public-review threat.
- Customer asks for an exception, discount, refund, settlement, or claim outcome.
- COI/additional insured request with building requirements.
- Payment failure, disputed charge, fraud/security notice, or accounting problem.
- Active job scheduling issue, missed pickup, major scope change, crew issue, or safety concern.
- Public-profile/review issue that could affect the brand.

## Triage note template

Use this internally when handing a message to an owner/operator:

```text
Queue: [Lead / Customer / Supermove / Payment / COI / Claim / GBP / List]
Visibility: [Keep in inbox / labeled only / review for archive later]
Why it matters: [one sentence, no unnecessary private detail]
Needed action: [call / reply draft / Supermove update / owner decision / restricted review]
Deadline: [same day / this week / no deadline]
Approval gate: [send/reply/archive/delete/filter/etc. if any]
```

## Quality checks

Before ending a triage pass, confirm:

- [ ] No email was sent, replied to, forwarded, deleted, trashed, marked read, archived, unsubscribed, or filtered without approval.
- [ ] Lead/customer/job/payment/claim/COI/GBP items remain visible until handled.
- [ ] Sensitive details stayed out of GitHub and broad prompts.
- [ ] Any proposed cleanup has a sample/review packet and explicit exclusions.
- [ ] Next actions are written in plain business language.

## Automation opportunities

- Scheduled read-only dashboards for counts by label/queue.
- Label-only routing for conservative categories after approval.
- Restricted sample packets for unsubscribe/archive pilots.
- Draft queue summaries that exclude raw customer/payment/claim details.
