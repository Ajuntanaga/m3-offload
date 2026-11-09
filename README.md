# M3 processing

This public repository runs bounded M3 guitar-to-MIDI diagnostics on GitHub Actions. Source code comes from a full commit in Ajuntanaga/polyphonic-audio-to-midi. Recorded inputs live in the corpus-20261108 release and are verified before use.

Dispatch M3 processing with the source commit and task. Assignment traces compare a fresh OFF reference with an instrumented OFF replay. Corpus recovery produces new offline references; it does not authorize installation or live-use acceptance.

Reports are retained for 14 days and compressed evidence for 7 days. Collect important outputs into the project checkpoint before they expire. All new offloaded processing uses GitHub Actions. Legacy Kaggle jobs may only be collected.

The repository stays public between runs, as requested. Recordings, calibration, release assets and Actions logs are publicly accessible; signed-in GitHub users can download published artifacts. Standard GitHub-hosted CPU runners are free for public repositories; larger runners remain billable. See [GitHub Actions billing](https://docs.github.com/en/billing/concepts/product-billing/github-actions). Changing visibility does not establish the billing treatment of a job already running.

No credentials or raw recordings belong in the git tree. The workflow uses its scoped GitHub token to read the release and requires this repository to be public. The installed scoreboard stays unchanged until a measured candidate passes its acceptance gates.
