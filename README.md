# MoRaj Finance — update manifests

Public version manifests for the MoRaj Finance desktop apps. **Version numbers and a
download link only — no installers, no data.** Each app reads its file on start-up and
from Help ▸ Software, compares the `version` to the running build, and (if newer) shows a
"Download" bar that opens the `url` in the browser. Installers stay in the private release
repos; the operator installs by hand, exactly as before.

To publish a new version: edit the `version` (and optionally `notes`) in the matching file
and commit. Old builds start noticing within a few minutes.
