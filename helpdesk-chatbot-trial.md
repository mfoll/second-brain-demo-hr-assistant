---
type: Project
status: Superseded
start: 2025-06-02
end: 2025-11-14
belongs_to: "[[run-hr-helpdesk]]"
related_to:
  - "[[knowledge-base-rebuild]]"
  - "[[leon-adjei]]"
  - "[[hr-service-delivery]]"
has:
  - "[[chatbot-test-question-set-2025]]"
  - "[[chatbot-trial-closure-report]]"
  - "[[chatbot-trial-stopped-2025-11-14]]"
  - "[[should-we-retry-a-helpdesk-chatbot]]"
_organized: true
---

# Helpdesk Chatbot Trial

A six-month test of Deskwell Assist, the chatbot add-on in [[deskwell]], answering employee questions from the knowledge base. Stopped by [[leon-adjei]] on 2025-11-14 and superseded by the [[knowledge-base-rebuild]].

## Outcome

Test whether a chatbot over the knowledge base can answer common queries. Superseded by the knowledge base rebuild after it answered 41% of 150 test questions correctly.

## Current State

> [!failure]
> On the 150-question test of 2025-10-22, the chatbot gave a correct and complete answer to 62 questions (41%), a partial one to 51 and a wrong one to 37, including 14 confidently wrong answers about pay or leave. Most wrong answers came from outdated or contradictory articles, not from the tool.

- Closed; nothing running. The trial licence lapsed on 2025-11-30 ([[deskwell-assist-trial-terms]]).
- Whether and when to try again is [[should-we-retry-a-helpdesk-chatbot]]; the current answer is not before the rebuild is done and has had one full review cycle.

## Scope and Boundaries

Internal test only: the bot was never shown to employees outside People Services. It read published knowledge base articles and nothing else. [[kasia-wrobel]] ruled out training or grounding it on ticket history ([[could-the-chatbot-use-ticket-history]]).

## Working Context

The idea came from the 2025 service review: about a third of tickets were questions an article already answered. The vendor offered six months of Deskwell Assist free. I built the [[chatbot-test-question-set-2025]]: 150 questions written from ticket themes, never copied from tickets, each with an agreed correct answer signed off by the article owner.

What we learned is in [[chatbot-trial-lessons-learned]] and my view in [[the-chatbot-failed-on-content-not-technology]]. Background reading: [[chatbot-wikipedia]], [[hallucination-artificial-intelligence-wikipedia]], [[retrieval-augmented-generation-wikipedia]].

Rejected options at closure: extending the trial with a paid licence (Leon: paying to test bad content), and limiting the bot to 20 "safe" questions (too few to save tickets).

## Next Actions

- [ ] None in this project. Any retry starts as a new project after the rebuild.

## Important Notes

- [[chatbot-trial-closure-report]]
- [[chatbot-test-run-2025-10-22]]
- [[knowledge-base-content-audit-2025]]
- [[chatbot-trial-lessons-learned]]

## Maintenance Log

- 2025-11-17: Successor project [[knowledge-base-rebuild]] started.
- 2025-11-14: Stopped by Leon ([[chatbot-trial-stopped-2025-11-14]]).
- 2025-10-22: 150-question test: 41% correct and complete.
- 2025-06-02: Trial started ([[chatbot-trial-kickoff-2025-06-02]]).
