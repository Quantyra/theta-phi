# Zenodo archiving status

Repository: https://github.com/Quantyra/theta-phi

Status: metadata prepared; Dan enabled this repository in Zenodo on 2026-10-07. GitHub confirms an active release webhook. No release, reserved DOI, or published DOI exists; archive ingestion has not been tested.

On 2026-10-07, the approved credential's read-only Zenodo deposition API check returned HTTP 403 with an HTML response. This does not establish authenticated API access. Dan subsequently enabled the integration through his account, and the release webhook was verified. Direct API access remains unresolved; a webhook is not proof of a successful archive.

Integration follows Zenodo's [repository enabling guide](https://help.zenodo.org/docs/github/enable-repository/). Authorship is Grant Boudreaux first and Daniel Fredriksen second. Before a DOI-bearing research release, record a publication readiness decision, settle source-sharing and licensing, validate citation and Zenodo metadata, and freeze the candidate commit. Once publication readiness passes, create the release and verify the resulting archive, version DOI, concept DOI, and exact archived commit before adding a badge.

Zenodo's [GitHub archiving guide](https://help.zenodo.org/docs/github/archive-software/github-upload/) explains release ingestion; its [DOI guide](https://help.zenodo.org/docs/deposit/describe-records/reserve-doi/) distinguishes reservation from publication. An account access failure must not be reported as a completed connection.
