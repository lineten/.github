---
name: Skill Change
about: Use this template when creating or updating a skill definition
---

## Summary
Briefly describe what changed and why this skill update is needed.

---

## Skill Details
- **Skill name:**  
- **Canonical file (`SKILL-*.md`):**  
- **Skill type:** Local / Core / Integration  
- **Status:** Draft / Trusted / Core / Deprecated  
- **Owner(s):**  

---

## Reason for Change
What prompted this update?
- Production incident
- New constraint or requirement
- Clarification / correction
- Standardisation across repos

---

## What Changed
Summarise the material changes to the skill:
- New guidance added
- Behaviour clarified
- Failure modes updated
- Scope narrowed or expanded

---

## Relationships to Other Skills
- **Extends / based on:** (link to core or integration skill, if applicable)
- **Conflicts with:** (should normally be *none*)

---

## Failure Modes & Risk
- New or updated failure modes:
- Escalation conditions:
- Risk of misapplication:

---

## Applicability
Where should this skill be applied?
- Repositories:
- Services / components:
- Situations where it **does not** apply:

---

## Skill Review Checklist (required)

### Intent & Scope
- [ ] Intent is clear and unambiguous
- [ ] Addresses a real, recurring problem
- [ ] Scope is appropriate

### Correctness & Reality
- [ ] Reflects real system behaviour
- [ ] Assumptions are explicit
- [ ] Consistent with platform constraints

### Failure Modes & Safety
- [ ] Known failure modes documented
- [ ] Escalation conditions defined
- [ ] Does not mask real faults

### Relationships
- [ ] Extends other skills explicitly (if applicable)
- [ ] Does not contradict core skills
- [ ] Links to relevant contracts (for integration skills)

### Governance
- [ ] Owner(s) listed and correct
- [ ] Status set correctly
- [ ] Reviewed by appropriate CODEOWNERS

---

## Rollback
How would this skill change be reverted if it proves incorrect?

---

## Notes for Reviewers
Anything reviewers should pay special attention to?
