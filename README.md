# Race car wiring schematics — Revision J

Public website: https://dannydowns46.github.io/race-car-wiring-schematics/

The website includes an interactive wire-tracing viewer, native and continuous
schematic PDFs, construction work lists, an offline viewer ZIP and a current
rebuildable project bundle. Open the website for the current download links and
release archive. The drawings remain a design review draft with hardware and
NSP commissioning holds; see the supplied project handoff and open items.

## Future updates

The authoritative electrical sources are in the full project workspace, NOT in
this compiled website repository. Extract the current project ZIP and read its
AGENTS.md, START_HERE.md and CODEX_HANDOFF.md before changing the design.

After the requested changes, rebuild and validate the native schematics and both
continuous drawings, inspect the changed pages, then run the included
Public_Site/prepare_release.py with a new dated release ID. Publish the CONTENTS
of its dist directory to this repository's main-branch ROOT. GitHub Pages is
configured to deploy main/root, with .nojekyll; the optional dist-based Actions
workflow in the source bundle is not used for this layout.

Keep the repository identity and website URL. Preserve old dated project ZIPs;
do not overwrite published release bytes. Update current links, release.json and
releases.json together. Check the deployed viewer and download hashes. Retain
.gitattributes so Git does not change generated artifact line endings.

No background synchronization or scheduled publishing job is installed. Updates
are rebuilt and published when requested. Source-bundle hosting notes describe
their capture state; this repository and the workspace publishing.json hold the
current hosting identity.
