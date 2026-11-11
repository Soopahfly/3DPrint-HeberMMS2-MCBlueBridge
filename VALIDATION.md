# Validation and testing

The maker reports that all development versions were printed and tested on a Bambu A1 using PLA, and prefers the centred/rearward placement at both PCB heights. These print sets select those useful layouts: v8 low profile, v7 raised with LED/cable guides, and v6 raised basic.

The separate retaining ring was found not to stay in place and is omitted. The button flange prevents outward loss; the installed Pico captures the button from inside. Verify free pressing and release after assembly.

Digital checks on the source models cover CAD validity, connected/watertight printable meshes, post profiles, matching button heights, light-pipe alignment and cable-guide tunnel clearances. Sub-micron export-seam cleanup was applied where needed in the development exports. This publication copies the checked STL bytes without further geometry changes.

[file_manifest.json](file_manifest.json) records the SHA-256 hashes and development origins of the 15 STLs. The history's source paths refer to the development layout, not additional public downloads. Both board heights use 2.10 mm fitting pegs and the corrected 5.00 mm nominal button aperture.

The original source is the Heber v17 / C183 flap revision dated 23 June 2025. The official Pico W STEP was used as a mechanical surrogate and checked against the Pico 2 W component drawing during development. Physical printing and maker feedback informed the revisions; this is not a guarantee for every case revision, printer, filament, USB lead or internal hardware configuration.

The overview image is a CAD render. There is no pre-sliced, printer-specific 3MF profile or G-code in this repository. Use the supplied fit checks and inspect the sliced parts for your printer.
