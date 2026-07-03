# File Storage And Drive Handling SOP

Status: Draft for internal review
Last updated: 2026-07-03
Owner: Management / assigned admin
Applies to: Humans and agents organizing Dos Manos business documents

## Purpose

Keep Dos Manos files findable, safe, and useful without exposing restricted material or creating duplicate source-of-truth copies.

## Main rule

Use Google Drive for human business documents. Use GitHub Agent HQ and this SOP repo for agent playbooks, manifests, workflows, markdown source, automation, and repeatable procedures.

Do not treat exported Google Docs, PDFs, screenshots, or one-off copies as canonical if the source lives in this repo or another approved source system.

## Source inputs

- Agent HQ file storage guide: `C:/Users/SLIB/Documents/DosManos-Agent-HQ/handoffs/file-storage-guide-current.md`
- Current source map: `C:/Users/SLIB/Documents/DosManos-Agent-HQ/manifests/current-source-map.md`
- Drive librarian playbook: `C:/Users/SLIB/Documents/DosManos-Agent-HQ/agent-skills/drive-librarian.md`
- SOP maintenance guide: `C:/Users/SLIB/Documents/DosManos-Agent-HQ/agent-skills/sop-maintenance.md`

## Approved working locations

| Surface | Use |
| --- | --- |
| Google Drive `My Drive > Dos Manos Docs` | Human business library and shared working documents. |
| Drive `Start Here` | Human entry point, indexes, strategy, and general operating references. |
| Drive `Brand Source of Truth` | Approved brand board, logos, assets, voice, and visual standards. |
| Drive `Brand and Marketing` | Marketing folders, public-copy drafts, campaign resources, and media working material. |
| Drive `Sales and Customer Growth` | Sales scripts, lead/quote resources, customer-growth documents. |
| Drive `Partners and Affiliates` | Affiliate/referral documents, partner CRM, and partner workflow resources. |
| Drive `Agent and Automation HQ` | Human-readable exports from agent workflows. |
| Drive `Inbox - Needs Sorting` | Temporary home for ambiguous, duplicate, unsorted, or needs-review items. |
| GitHub Agent HQ | Agent source maps, manifests, workflows, dashboards, scripts, and handoff packets. |
| SOP repo | Canonical markdown source for formal SOPs and company operating procedures. |
| Supermove | Central job and customer/job-operation record whenever possible. |
| QuickBooks/accounting records | Confirmation source for collected revenue and payment status. |

## Restricted branches and sensitive material

Treat these as restricted unless management gives a specific review plan:

- ICC / regulatory / compliance records.
- Human Resources and employee records.
- Financial, payment, QuickBooks, tax, accounting, banking, and payroll records.
- Legal, insurance, COI, claims, complaints, refund, and damage records.
- Customer names, addresses, phone numbers, emails, quote details, payment issues, job disputes, or private partner/contact lists.

Restricted material may be indexed at a safe summary level when needed, but raw details should stay in approved systems or restricted local caches, not broad GitHub docs, public prompts, or shared general folders.

## File routing process

1. Identify the document type and source.
2. Decide whether it is public-safe, internal, customer-sensitive, or restricted.
3. If it is restricted or uncertain, do not move it casually. Route it to the approved restricted branch or `Inbox - Needs Sorting` with a note for review.
4. If it is clearly non-sensitive and belongs in a current business lane, place or link it in the matching Drive folder.
5. If it is agent source, automation, manifest, markdown SOP source, or repeatable workflow logic, keep it in Agent HQ or the SOP repo.
6. Preserve original files and metadata. Do not delete, trash, or overwrite originals by default.
7. Update the relevant index, README, source map, or handoff note so the next person can find the decision.

## Destination guide

| Item type | Default destination |
| --- | --- |
| Brand board, logo, approved voice/visual rules | Drive `Brand Source of Truth` |
| Marketing docs, public-copy drafts, campaign ideas | Drive `Brand and Marketing` |
| Sales scripts, quote resources, customer-growth docs | Drive `Sales and Customer Growth` |
| Affiliate/referral docs and partner CRM | Drive `Partners and Affiliates`, subject to restricted handling for signed/tax/contact records |
| General strategy and planning docs | Drive `Start Here/Strategy and Planning` or another approved Start Here subfolder |
| Agent-generated human-readable reports | Drive `Agent and Automation HQ` and Agent HQ repo source where applicable |
| SOP markdown source | SOP repo |
| Agent manifests, automation, scripts, dashboards | Agent HQ repo |
| Unsure, duplicate, mixed, or needs-review docs | Drive `Inbox - Needs Sorting` |
| Finance, HR, legal, ICC, compliance, claims, insurance-sensitive docs | Restricted branch only |
| Live customer/job records | Supermove or approved operating system |

## Naming rules

Use plain business language. Avoid visible numbered prefixes, agent-ish scaffolding, and cryptic internal abbreviations in shared Drive resources.

Good names are descriptive and stable:

- `Lead Intake Checklist`
- `Brand Resource Guide`
- `Review Reply Drafts`
- `Partner Follow-Up Notes`

Avoid names like:

- `00_START_HERE`
- `01_Agent_Output`
- `AI Generated Thing Final Final`
- `misc`

When a date is useful, use an unambiguous format such as `2026-07-03`.

## Human helper rules

Do:

- Inventory before moving.
- Preserve originals.
- Keep sensitive branches restricted.
- Use `Inbox - Needs Sorting` when unsure.
- Leave a note in an index or README when routing is not obvious.
- Ask management before public, sensitive, or irreversible changes.

Do not:

- Delete, trash, or permanently delete files without explicit approval.
- Change sharing, permissions, ownership, or public access without approval.
- Move restricted finance, HR, legal, ICC, insurance, compliance, claim, or customer-sensitive files without a specific restricted-review plan.
- Rename shared folders into numbered or agent-centric labels.
- Copy raw sensitive details into GitHub, broad prompts, or public documents.

## Quality checks

Before marking file work complete, confirm:

- [ ] The destination matches the business surface.
- [ ] Restricted material stayed restricted.
- [ ] No originals were deleted or overwritten.
- [ ] No permissions or sharing were changed unless approved.
- [ ] The relevant index/source map/handoff was updated.
- [ ] Any unresolved ambiguity is noted for review.

## Escalation

Escalate to management before moving, sharing, deleting, renaming, publishing, or broadly summarizing restricted or sensitive material. If a file involves claims, insurance, ICC, legal, HR, finance, tax, payroll, customer disputes, or public-facing claims, pause and route through the appropriate specialist or owner approval.

## Automation opportunities

- Refresh Drive inventory and source maps on a schedule.
- Detect unsorted root files and propose destination packets.
- Generate safe index updates from Drive metadata.
- Flag sensitive names for restricted review before any movement.
