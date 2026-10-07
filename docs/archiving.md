# Zenodo archiving status

Repository: https://github.com/Quantyra/theta-phi

Status: metadata prepared; integration not verified. No release, reserved DOI, or published DOI exists.

On 2026-10-07, the approved credential's read-only Zenodo deposition API check returned HTTP 403 with an HTML response. This does not establish authenticated access. Connection requires authenticated Zenodo access and enabling this exact repository; a webhook alone is not proof of a successful archive.

After access is restored, follow Zenodo's [repository enabling guide](https://help.zenodo.org/docs/github/enable-repository/). Before a DOI-bearing research release, record a publication readiness decision, settle authorship and licensing, validate citation and Zenodo metadata, and freeze the candidate commit. Once publication is authorized and the connection verified, create the release and verify the resulting archive, version DOI, concept DOI, and exact archived commit before adding a badge.

Zenodo's [GitHub archiving guide](https://help.zenodo.org/docs/github/archive-software/github-upload/) explains release ingestion; its [DOI guide](https://help.zenodo.org/docs/deposit/describe-records/reserve-doi/) distinguishes reservation from publication. An account access failure must not be reported as a completed connection.
