---
type: Pain point
belongs_to: "[[Slack Client Product Analysis Summary]]"
client: Amenitiz
source: slack_channels_data
---

# Client Analysis: Amenitiz

## Client name

Amenitiz

## Summary of relevant conversation context

Amenitiz is a clear signal that the biggest problem is not isolated bugs but low operational confidence. The account depends too heavily on manual intervention from the Dolfin team for mappings, syncs, retroactive changes, and investigations. The client wants more autonomy, faster resolution, and less support dependency.

## Product-related pain points identified

| Pain point | Pain point category | Type of pain point | Estimated criticality | Supporting evidence or excerpts | Suggested product implications or follow-up actions |
| --- | --- | --- | --- | --- | --- |
| Core workflows still require manual intervention from support | Admin workflow and autonomy | Workflow limitation | High | "Dolfin works, but only if Alejo manually intervenes." | Prioritize self-serve admin workflows for mappings, retro changes, conflict handling, and investigations. |
| Admins cannot safely manage user mappings, retroactive edits, and sync-related exceptions | Data integrity and sync operations | Missing feature | High | "user mappings", "SDR syncs", "retroactive changes", "overlap fixes" were called out as recurring dependencies | Build safer retro-edit tooling, sync diagnostics, conflict prevention, and guided recovery flows. |
| Admins cannot edit user types and start dates directly, creating accuracy incidents | HRIS and user data management | Missing feature | High | "incident of accuracy... Dolfin does not allow the admin to edit user types and start dates" | Revisit admin override controls and consider deeper HRIS sync coverage for employee attributes. |
| Validation and trust tooling are insufficient for strategic accounts | Data validation and traceability | Missing feature | High | "validation tooling" was described as an operational necessity, not a nice-to-have | Add data health checks, pre-release validation steps, and clearer auditability before customer-facing changes go live. |
| Some uploads and sync experiences appear unreliable or opaque | Usability and reliability | Bug or UX gap | Medium | "csv upload worked perfectly, but then the targets aren't showing"; "Sync Issues Banner" | Improve post-upload confirmation, error surfacing, and sync-status explainability. |

## Suggested product implications or follow-up actions

- Treat admin autonomy for complex accounts as a core roadmap theme, not a support playbook problem.
- Package validation tooling, conflict prevention, and safer data editing into one operational trust initiative.
- Close the loop with the client after each fix using concrete proof, guides, and re-validation requests.
