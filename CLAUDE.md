# road-dog-download

Public download page. Holds `RoadDog-latest.apk` (see the road-dog repo's CLAUDE.md) and
`dor.html`, the offline DOR Narrative Builder.

## DOR builder versions
The DOR builder exists twice: the claude.ai artifact "DOR Narrative Builder — CHP 115A"
(AI writer) and `dor.html` here (offline, built-in writer). They share one version number,
shown at the top of the page (`<p id="ver">`). For every change, bump it in BOTH copies
(1.1 → 1.2 for changes, 2.0 for big redesigns), update the date, and keep `(offline)` on
this copy.
