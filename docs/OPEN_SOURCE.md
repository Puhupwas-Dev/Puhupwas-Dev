# Open-source evidence and contribution plan

Last reviewed: **6 November 2026**.

This repository is a GitHub profile and portfolio. Its README describes professional experience and links to public work. It is not a published software package. A profile edit does not establish package adoption, upstream maintainership, or independent community participation.

## Current public evidence

The review covered the 41 public repositories visible under `Puhupwas-Dev`: 24 GitHub forks and 17 repositories not marked as forks. "Not marked as a fork" does not establish original authorship; imported repositories can retain upstream code and history.

- **Merged upstream PRs:** GitHub search returned **0** for the requested filter `is:pr is:merged author:Puhupwas-Dev -user:Puhupwas-Dev merged:>2025-11-06`. [Repeat the search](https://github.com/search?q=is%3Apr+is%3Amerged+author%3APuhupwas-Dev+-user%3APuhupwas-Dev+merged%3A%3E2025-11-06&type=pullrequests). The API reported `incomplete_results: false`. This checks this account only; organization-owned repositories are excluded only when explicitly added to the query.
- **Merged PRs into account-owned repositories:** the corresponding [search across these repositories](https://github.com/search?q=is%3Apr+is%3Amerged+user%3APuhupwas-Dev+merged%3A%3E2025-11-06&type=pullrequests) returned **1** result: [amrutam_app#1](https://github.com/Puhupwas-Dev/amrutam_app/pull/1). Its author is one other GitHub account. Independent external-contributor status has not been established. No reviewed repository reaches 20 qualifying external contributors.
- **Package downloads and dependents:** **not verified**. No publisher account or package-maintainership evidence was identified. The reviewed frontend app manifests are marked private, and some imported package metadata points to upstream projects. Neither dependency lists nor upstream download counts establish adoption of work maintained by this account. GitHub dependents pages could not be inspected through the available browser connection.
- **Foundation or language-project role:** **not verified**. No official maintainer or committer listing was identified for this account. Studying, evaluating, using, or forking a project is separate from holding a listed upstream role.
- **OpenSSF criticality:** **not verified**. No current criticality result was obtained for a maintained project. The [official project](https://github.com/ossf/criticality_score) reports that its last successful public scoring run completed in July 2025. A missing result is not a score of zero. OpenSSF Scorecard is a separate security assessment and must not be substituted for Criticality Score.

**Conclusion:** none of the reviewed evidence currently establishes a qualifying threshold. This is an evidence review, not an eligibility determination by the program.

## What would establish eligibility

The [Claude for Open Source program](https://claude.com/contact-sales/claude-for-oss) currently lists alternative routes. One route is sufficient; meeting every route is not required.

- Maintain packages with at least 500 dependent repositories, 100 dependent packages, or 200,000 combined monthly registry downloads.
- Hold a listed committer or maintainer role on a recognized foundation or language project.
- Author at least 100 PRs merged into repositories you do not own within the last 12 months.
- Maintain a repository with at least 20 unique external contributors whose PRs merged within the last 12 months.
- Maintain a repository with an OpenSSF criticality score of at least 0.4.

Verify the live program page before applying. The program also invites maintainers of ecosystem dependencies who fall outside the listed routes to explain their impact; this does not guarantee acceptance.

## Practical contribution plan

1. **Choose one real problem.** Use the existing React/TypeScript and AI evaluation experience to solve a recurring problem for other developers. Review a candidate project's provenance and license before reusing its code.
2. **Make the project usable.** Document its intended users, setup, a working example, limitations, and support process. A reusable package should have a clear API, meaningful tests, release notes, and an appropriate license chosen for the owned code.
3. **Contribute upstream where useful.** Reproduce a real issue, discuss the intended fix when the project requests it, add a regression test where appropriate, and follow its contribution guide. Record merged PR URLs. Maintainers decide what to merge.
4. **Support independent contributions.** Publish actionable issues with reproduction steps and acceptance criteria, respond to contributors, and review substantive fixes. Track distinct external people per repository rather than commit counts or all-time contributor totals.
5. **Measure real usage.** Once a package is actually published, record the registry package URL, publisher or maintainer listing, download interval, and official download response. Record dependent repositories separately from dependencies installed by the project.
6. **Refresh the evidence before applying.** Re-run the rolling-year searches, verify ownership exclusions and contributor independence, and explain any limitations.

There is no guaranteed timeline to reach an adoption or community threshold. Publishing a new repository or package alone is not evidence that a threshold is met.

## Recording future evidence

For each claim, include:

- Project and role, with an official maintainer listing or ownership source.
- Public evidence URL: merged PR, release, registry package, dependents view, or official scoring output.
- Observation date and exact measurement window.
- Method, filters, and exclusions, including own repositories, alternate accounts, bots, and imported upstream history.
- Known limitations and a concise explanation of the change's benefit.

Keep professional client results separate from public open-source adoption. Do not publish confidential evaluation tasks, client material, or credentials.

## Sources and reproducibility

- [Public repositories](https://github.com/Puhupwas-Dev?tab=repositories)
- [Repository metadata](https://api.github.com/repos/Puhupwas-Dev/Puhupwas-Dev)
- [Upstream merged-PR API query](https://api.github.com/search/issues?q=is%3Apr+is%3Amerged+author%3APuhupwas-Dev+-user%3APuhupwas-Dev+merged%3A%3E2025-11-06&per_page=100)
- [Account-owned merged-PR API query](https://api.github.com/search/issues?q=is%3Apr+is%3Amerged+user%3APuhupwas-Dev+merged%3A%3E2025-11-06&per_page=100)
- [amrutam_app package metadata](https://github.com/Puhupwas-Dev/amrutam_app/blob/main/package.json)
- [ai-toolkit package metadata pointing to its upstream](https://github.com/Puhupwas-Dev/ai-toolkit/blob/main/package.json)
- [OpenSSF Criticality Score and published data](https://github.com/ossf/criticality_score)
- [Current program criteria](https://claude.com/contact-sales/claude-for-oss)

Search results and rolling time windows change. Recompute rather than treating this dated snapshot as a permanent count.
