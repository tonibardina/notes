---
type: Pain point
belongs_to: "[[Slack Client Product Analysis Summary]]"
client: Sparta
source: slack_channels_data
---

# Client Analysis: Sparta

## Client name

Sparta

## Summary of relevant conversation context

Sparta is primarily blocked by integration and data-model fit. HubSpot deal splits, CRM quality problems, and currency traceability gaps delayed go-live and increased pressure on trust during onboarding.

## Product-related pain points identified

| Pain point | Pain point category | Type of pain point | Estimated criticality | Supporting evidence or excerpts | Suggested product implications or follow-up actions |
| --- | --- | --- | --- | --- | --- |
| Dolfin lacked the deal split support needed for Sparta’s compensation model | CRM integration and data model coverage | Missing feature | Critical | "Missing deal split support on our side"; "we don't have Deal Splits in Dolfin" | Prioritize native support for multi-owner deal attribution in HubSpot-driven accounts. |
| HubSpot permission and resync issues blocked validation | Integration operations | Integration gap | High | "we're not getting the authorization to access the deal split... We need access... re sync data" | Add clearer integration permission checks and guided resync flows. |
| CRM data quality issues make it hard to validate payouts confidently | Data integrity and onboarding trust | Data quality gap | High | "Deals consolidated incorrectly", "missing or inaccurate deal classifications", "Q1 historical data not being reliable" | Add onboarding diagnostics that expose data readiness before payout validation starts. |
| Multi-currency handling lacks transparency | Currency support and payout traceability | Missing feature | High | Concerns about local currency not showing, AED missing, and unclear conversion logic shown to end reps | Improve FX support, currency coverage, and explainability of conversion logic in payout views. |
| Users cannot trace payout logic deeply enough | Explainability and trust | Product gap | Medium-High | Dolfin should answer "why did this person get paid this amount on this deal?" | Build richer deal-level payout traceability for reps, managers, and finance. |

## Suggested product implications or follow-up actions

- Sparta is a strong argument for investing in integration fit before go-live commitments.
- Deal split support, permission diagnostics, and FX traceability should be treated as enablement blockers, not polish.
- Introduce a data-readiness checkpoint for complex HubSpot implementations.
