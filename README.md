# ATP021 — Perses

An Astrona **training path**: a course track that groups training series
(`ATSxxx`) as its domains. Each stage in `path.yaml` is one domain and points
at the repository that teaches it. There is no official Perses certification
exam, so the domains and weights are Astrona's own and `examPreparation` is
off. Everything is written for Perses v0.54.0 and the Perses Operator v0.5.0.

| Stage | Domain | Weight | Content | Status |
| --- | --- | --- | --- | --- |
| STG001 | Fundamentals, Architecture & percli Setup | 10 % | [ATS106](https://github.com/astrona-io/ATS106) | Draft, written, not yet run |
| STG002 | Multi-Pillar Datasources & Variable Scopes | 20 % | [ATS107](https://github.com/astrona-io/ATS107) | Draft, written, not yet run |
| STG003 | Dashboard-as-Code With CUE & Go | 25 % | [ATS108](https://github.com/astrona-io/ATS108) | Draft, written, not yet run |
| STG004 | Open Specification & Grafana Migration | 15 % | [ATS109](https://github.com/astrona-io/ATS109) | Draft, written, not yet run |
| STG005 | Embedded UI Packages & Plugin Development | 15 % | [ATS110](https://github.com/astrona-io/ATS110) | Draft, written, not yet run |
| STG006 | Kubernetes-Native Operations & The Perses Operator | 15 % | [ATS111](https://github.com/astrona-io/ATS111) | Draft, written, not yet run |

The site picks it up through [astrona-content](https://github.com/astrona-io/astrona-content):
a file in `courses/` that points at this repository, and the content sync
builds the course — one section per stage, with the readings, playgrounds and
labs each stage repository lists in its `astrona.yaml`. That course file does
not exist yet; add it when the first stage is ready to show.
