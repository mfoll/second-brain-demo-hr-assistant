---
type: Event
date: 2025-10-22
belongs_to: "[[helpdesk-chatbot-trial]]"
related_to:
  - "[[chatbot-test-question-set-2025]]"
  - "[[knowledge-base-content-audit-2025]]"
_organized: true
---

# Chatbot Test Run 2025-10-22

The formal test of Deskwell Assist against the 150-question [[chatbot-test-question-set-2025]]. I ran it in one sitting with [[callum-rourke]] scoring blind against the agreed answers; disagreements went to [[leon-adjei]].

## Result

> [!failure]
> 62 of 150 correct and complete (41%), 51 partially correct, 37 wrong. 14 of the wrong answers were confidently wrong about pay or leave, such as carry-over limits and weekly pay dates. The success bar was 70% and no confident errors on pay.

## Why it failed

We traced each wrong or partial answer to its cited article:

- 50 answers quoted an outdated article (old carry-over rules, the 2023 pay calendar).
- 19 drew on two articles that contradicted each other and picked one.
- 17 had no relevant article, and the bot answered anyway from loosely related text.

- 2 misread an article that was correct.

So 86 of the 88 failures were content problems, not the tool. This became the starting list for the [[knowledge-base-content-audit-2025]].

## Next

Leon took the result to [[deborah-okwuosa]]; trial stopped three weeks later ([[chatbot-trial-stopped-2025-11-14]]).
