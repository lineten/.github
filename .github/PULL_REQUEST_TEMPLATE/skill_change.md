---
name: Skill Change
about: Use this template when creating or updating a skill definition
---

## Summary
Briefly describe what changed and why.

---

## Change Type (select one or more)
- [ ] Local skill change (repo-scoped `SKILL-*.md`)
- [ ] Core skill change (org-wide skill)
- [ ] Integration skill change (cross-service)
- [ ] Contract change (API / event / schema)
- [ ] Code change only (no skill or contract change)

---

## What Changed
Summarise the material changes:
- New guidance added
- Behaviour clarified
- Failure modes updated
- Contract/interface modified

---

## Skills / Contracts Affected
- **Skill(s):** (link to canonical `SKILL-*.md`)
- **Based on / Extends:** (link to core or integration skill, if applicable)
- **Contract(s):** (link to OpenAPI / AsyncAPI / schema, if applicable)

---

## Impact & Risk
- Who or what is affected?
- Backward compatibility considerations
- Risk of misapplication or misuse

---

## Review Checklist (complete what applies)

### Skills (if applicable)
- [ ] Intent is clear and unambiguous
- [ ] Reflects real system behaviour
- [ ] Failure modes documented
- [ ] Escalation conditions defined
- [ ] Does not contradict core skills
- [ ] Owner(s) listed and status set

### Contracts (if applicable)
- [ ] Backward compatibility assessed
- [ ] Versioning or deprecation documented
- [ ] CI validates contract changes
- [ ] Integration skills updated if needed

---

## Rollback
How would this change be reverted if it proves incorrect?

---

## Notes for Reviewers
Anything reviewers should pay special attention to?
