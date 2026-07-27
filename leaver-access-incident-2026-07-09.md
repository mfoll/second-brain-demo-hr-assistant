---
type: Event
date: 2026-07-09
belongs_to: "[[talvento-hris-migration]]"
related_to:
  - "[[olumide-fashola]]"
  - "[[talvento-it-provisioning-design]]"
  - "[[how-fast-must-leavers-lose-system-access]]"
_organized: true
---

# Leaver Access Incident 2026-07-09

Ten days after go-live, IT found that 17 leavers whose last day had passed still had active accounts.

- Cause: the leavers were keyed in Talvento after their last working day (managers had told us late), with a termination date in the past. The provisioning feed only acted on termination dates reached at the nightly run, so past-dated terminations were skipped ([[talvento-it-provisioning-design]]).
- No sign any account was used after the last day; IT checked sign-in logs. Reported to [[kasia-wrobel]] as a near miss, not a breach.
- Fix by [[olumide-fashola]] on 2026-07-14: any termination with a date on or before today disables the account within an hour.
- Process fix on our side: leaver notifications from managers go through self-service, which asks for the last day up front ([[manager-self-service-rollout]]).

Records concerned are in the IT incident ticket, not here. Resolved question: [[how-fast-must-leavers-lose-system-access]].
