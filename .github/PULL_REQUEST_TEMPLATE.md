# Description

_Summary of the change and why it was made_

## PR Type (tick all that apply)

- [ ] Code change
- [ ] Skill / contract change

## Type of Change

- [ ] Bug fix (non-breaking change which fixes an issue)
- [ ] New feature (non-breaking change which adds functionality)
- [ ] Breaking change (fix or feature that would cause existing functionality to not work as expected)
- [ ] Documentation update

---

# Common Checklist

- [ ] JIRA ticket(s) ID in PR title
- [ ] I have rebased my changes onto the head of the target branch
- [ ] I have performed a self-review of my own changes
- [ ] Any dependent changes have been merged and published in downstream modules

---

<details>
<summary><strong>Secure Development Checklist</strong> (expand if applicable)</summary>

### Design and Scope

- [ ] Change scope is defined and limited
- [ ] No unintended impact to other regions / tenants
- [ ] Security implications considered during design

### Data & Access

- [ ] No hardcoded secrets
- [ ] Credentials stored in approved secret store
- [ ] Least privilege applied where applicable

### Dependencies & Code

- [ ] Approved libraries / frameworks used
- [ ] No untrusted external code introduced
- [ ] Input validation considered where applicable
- [ ] Error handling does not leak system detail

### Environments & Deployment

- [ ] Change tested in non-production
- [ ] Deployment follows standard release process
- [ ] Environment segregation maintained
- [ ] Rollback possible if required

### Change Control

- [ ] PR reviewed before merge
- [ ] Change traceable to requester / business need

### Risk Containment

- [ ] Rollout scope defined (e.g. region, client, POC)
- [ ] No global impact from localised change
- [ ] Feature can be disabled if required

### Logging & Monitoring

- [ ] Relevant events logged
- [ ] No sensitive data logged
- [ ] Monitoring impact considered

### Testing

- [X] Works locally
- [ ] Tested in production
- [ ] I have added tests that prove my fix is effective or that my feature works
- [ ] New and existing unit tests pass locally with my changes

### Quality

- [ ] My code follows the style guidelines of this project
- [ ] I have commented my code, particularly in hard-to-understand areas
- [ ] My changes generate no new warnings
- [ ] Security review on code has been conducted
- [ ] I have made corresponding changes to the documentation
- [ ] Any dependencies that are required for this change are listed

</details>

---

<details>
<summary><strong>Skill / Contract Change Checklist</strong> (expand if applicable)</summary>

### What Changed

- New guidance added
- Behaviour clarified
- Failure modes updated
- Contract/interface modified

### Skills / Contracts Affected

- **Skill(s):** (link to canonical `SKILL-*.md`)
- **Based on / Extends:** (link to core or integration skill, if applicable)
- **Contract(s):** (link to OpenAPI / AsyncAPI / schema, if applicable)

### Scope

- [ ] Local skill change (repo-scoped `SKILL-*.md`)
- [ ] Core skill change (org-wide skill)
- [ ] Integration skill change (cross-service)
- [ ] Contract change (API / event / schema)

### Review

- [ ] Intent is clear and unambiguous
- [ ] Reflects real system behaviour
- [ ] Failure modes documented
- [ ] Escalation conditions defined
- [ ] Does not contradict core skills
- [ ] Owner(s) listed and status set
- [ ] Backward compatibility assessed
- [ ] Versioning or deprecation documented
- [ ] CI validates contract changes
- [ ] Integration skills updated if needed

### Impact & Risk

_Who or what is affected? Backward compatibility considerations? Risk of misapplication?_

### Rollback

_How would this change be reverted if it proves incorrect?_

</details>

---

# Notes for Reviewers

_Anything reviewers should pay special attention to?_
