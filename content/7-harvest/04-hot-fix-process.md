---
title: "Hot-fix Process"
metaTitle: "Hot-fix Process | WP"
metaDescription: "Team and process arrangement to release an update to fix a critical or major error while maintaining SLA obligations in production."
published: true
metaTags:
  - Harvest
  - Hot-fix Process
  - Winning Product
  - Technology Mastery
---

## Why

A hotfix is a cumulative package generated over a previous official release and created to fix a problem in a product (e.g. bug fix). Unlike typical version updates, hotfixes are urgently developed and released as soon as possible to limit the effects of the product issue. The reality is sometimes messier. If a critical defect comes in, and if a flaw is costing you money, opening your company up to liability, leaving an opening for hackers, or disabling a fundamental feature, fix it now.

## How

A hotfix is a significant bug that affects a majority of users for which there is no reasonable workaround. Consider these questions:


- Is this bug significant?
- Does it affect the majority of users?
- Is there a reasonable workaround? When an issue is found, you first do a triage of the issue to determine if it’s really a critical "fix now" problem or if it can wait and be planned along with the other work. If the issue must be fixed immediately, then pull it into the current sprint (for Agile teams) as unplanned work and track how much time the team spends on it.

To facilitate the hot-fix process, it is essential to maintain best practices in release management, including proper branching strategies and delivery automation.

**Hotfix Testing**
- An impact analysis of the bug(s) should be performed to identify the scope of the test. 
- To lower the risk associated with the Hotfix, the fix should be first verified on an environment that simulates the production environment as closely as possible. 
- Once you have composed your environment and verified the fix, you should verify that the hotfix has not produced any regressions. A regression test could be performed for this purpose.
- Once the hotfix has been deployed to the live environment, the bug fix would need to be verified in addition to the execution of a smoke test.
- Verification results should be communicated to the stakeholders including any issues that may have been found on production.

## References

- [Hot-fix](https://en.wikipedia.org/wiki/Hotfix)
- [Hotfix or Not? Managing a Successful Release Process](https://www.viget.com/articles/successful-release-management-and-how-to-communicate-about-it/)
- [Release Management Process and Best Practices](https://www.plutora.com/blog/release-management-best-practices)
