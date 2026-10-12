# Sequence Timing update notices

Installed copies of Sequence Timing read [`updates.json`](updates.json) once a day to tell their admins when a
new version is out, and whether it fixes a security problem. Nothing about an install is sent.

Each release lists its `version`, `date`, a one-line `summary`, and whether it is a `security` fix with a
`severity` of `low`, `moderate`, `high`, or `critical`. Releases are announced with `scripts/announce-release.ps1`
in the main repository.
