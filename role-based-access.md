---
type: Concept
belongs_to: "[[maintain-hr-systems]]"
related_to:
  - "[[talvento-access-roles-matrix]]"
  - "[[data-minimisation]]"
  - "[[talvento]]"
_organized: true
---

# Role-Based Access

Granting system access by role rather than by person: a user gets the role "line manager" or "HR assistant", and the role decides what they can see and change. In Talvento, the role is combined with a scope (my team, my division, everyone).

## Why it matters here

- Staffora gave access per person, built up over fifteen years. When we reviewed it before go-live, 23 people had access to pay data who had no current reason to.
- In Talvento every access request is checked against the [[talvento-access-roles-matrix]]. I check the role is right for the job title; Rashid grants it; the HRBP approves anything with pay or case data.
- It is the practical form of [[data-minimisation]] in a system: people see what their role needs.

## Rules of thumb

- No one-off exceptions on a person; if a need is real, change the role.
- Remove roles on job change, not only on leaving. The provisioning feed handles leavers ([[how-fast-must-leavers-lose-system-access]]); job changes still need a ticket.
