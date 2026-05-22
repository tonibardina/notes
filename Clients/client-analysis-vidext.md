---
type: Pain point
belongs_to: "[[Slack Client Product Analysis Summary]]"
client: Vidext
source: slack_channels_data
---

# Client Analysis: Vidext

## Client name

Vidext

## Summary of relevant conversation context

Vidext is a strong autonomy signal. The account needed reliable invoice logic, easier resync tools, and better comp-rule coverage to avoid depending on the product team for routine operational corrections.

## Product-related pain points identified

| Pain point | Pain point category | Type of pain point | Estimated criticality | Supporting evidence or excerpts | Suggested product implications or follow-up actions |
| --- | --- | --- | --- | --- | --- |
| Admins cannot resync deals or invoices easily after config changes | Integration operations and autonomy | Missing feature | High | "should be able to launch a re-sync from X date" after mapping a new field | Add self-serve resync controls from integration settings. |
| Invoice-to-deal linking and invoice sync logic are not robust enough | Data integrity and sync operations | Integration gap | High | Issues referenced missing Holded invoices and inability to sync invoices to deals without deal line | Improve invoice linking coverage and make integration recovery flows less manual. |
| Commission logic can be wrong when invoice line items are involved | Compensation accuracy | Bug or logic gap | High | Duplicate commissions occurred because the platform used invoice totals instead of line-item amounts | Review invoice-based calculation logic and add validation for line-item commission setups. |
| Comp-rule builder does not support some plan designs | Plan modeling coverage | Missing feature | High | AE Manager plan required functionality the builder did not support | Expand plan-model expressiveness for manager and aggregated-metric use cases. |
| The client still lacked enough autonomy to come back confidently | Admin autonomy | Product gap | High | "There are still missing things that don’t allow them to be fully autonomous" | Frame roadmap work around reducing product-team dependency for routine admin operations. |

## Suggested product implications or follow-up actions

- Vidext is a high-value case for self-serve integration recovery and richer comp-rule modeling.
- Tighten invoice-based compensation validation because calculation mistakes directly damage trust.
- Use this account to define a minimum autonomy bar for admin teams running complex invoice logic.
