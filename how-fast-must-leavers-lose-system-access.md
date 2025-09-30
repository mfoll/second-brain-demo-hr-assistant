---
type: Question
status: Answered
belongs_to: "[[talvento-hris-migration]]"
related_to:
  - "[[talvento-it-provisioning-design]]"
  - "[[olumide-fashola]]"
  - "[[leaver-access-incident-2026-07-09]]"
_organized: true
---

# How Fast Must Leavers Lose System Access?

When someone leaves Pellmore, how quickly must their accounts be disabled, and what does HR have to do to make that happen?

## Current Answer

> [!success]
> At the end of the last working day, via the Talvento termination date. If the leaver is keyed late, with a termination date already passed, the account is disabled within an hour of the Talvento change (fix of 2026-07-14). HR's part is to key leavers as soon as the manager tells us, never after the last day if avoidable. IT security policy, confirmed by Olumide Fashola.

## How we got here

The design assumed leavers would always be keyed ahead of time. Ten days after go-live, 17 past-dated leavers still had active accounts ([[leaver-access-incident-2026-07-09]]). The fix and the process change are in [[talvento-it-provisioning-design]].

Background on how HR systems drive provisioning: [[microsoft-learn-cloud-hr-provisioning-plan]], [[rfc-7644-scim-protocol]].
