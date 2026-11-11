# Development history: v1 to v8

Prepared 4 November 2026. These numbers describe the development sequence, not eight equally recommended public downloads. The maker reports that all versions have been printed and tested, prefers the centred/rearward position, wants both PCB heights available, and finds the separate retaining ring ineffective. The public print sets therefore select v6, v7 and v8 and omit the retaining-ring STL.

## Revision-by-revision description

| Version | Description and changes from the previous version | Outcome / public use |
| --- | --- | --- |
| v1 | First Pico 2 W flap mount, based on the original Heber left/right flap STLs. Added four 2.10 mm round pegs with tapered tips, a 4.40 mm nominal BOOTSEL aperture, separate short button and retaining ring. Board standoff 4.20 mm; USB pointed towards the rounded end. | Development baseline. Superseded placement and aperture. Keep as history. |
| v2 | Replaced v1's fitting pegs with the 1.90 mm, 29-sided straight profile from the supplied reference Pico case, shortened to suit this mount. Board position, standoff and button layout stayed as v1. | The new 1.90 mm pegs were reported too loose. Keep as history. This profile is not used in the published variants. |
| v3 | Rotated the Pico 180 degrees, so USB pointed towards the straight end. Moved the button aperture/guide to follow BOOTSEL. Restored the 2.10 mm round/tapered peg profile; mounting-hole symmetry allowed the post centres to remain in place. | Corrected USB direction, but retained the older lateral/lengthwise location and 4.40 mm aperture. Keep as history. |
| v4 | Increased the fitting peg diameter from 2.10 to 2.20 mm following the successful peg test. Retained the v3 placement, original standoff and short button. | Fit-development option. The maker later requested 2.10 mm pegs. Keep as history. |
| v5 | Returned to 2.10 mm pegs and enlarged the button aperture from 4.40 to 5.00 mm. The previous print was reported at about 3.95 mm against a 4.04 mm printed button stem; the enlarged opening worked much better. Short button and board position otherwise retained. | Button-clearance correction, but USB plug access was still obstructed by the original flap posts/end area. Keep as history. |
| v6 | Moved the PCB 3.30 mm towards the rounded end and centred the socket between the existing screw posts: left PCB moved 1.75 mm left; right PCB moved 1.75 mm right. Moved the button aperture/guide with the PCB. Raised the PCB seating shoulders by 1.00 mm, from 4.20 to 5.20 mm above the panel. Lengthened only the button's internal tip by 1.00 mm. Retained 2.10 mm fitting pegs and the 5.00 mm button aperture. | First selected public layout. Offer as the optional raised basic variant, without light-pipe hole or cable guides. |
| v7 | Added the 1.75 mm nominal hole above the Pico LED for a filament light pipe, plus two internal USB cable-tie bridges. Retained v6 board position, raised supports and long-tip button. The bridges have 3.20 x 1.60 mm tunnels for a small 2.5 mm tie and leave a 15 mm corridor between them. | Main raised feature-complete public option. Light pipe starts around 5.7 mm for an outside-flush fit, trimmed to the actual LED. |
| v8 | Kept v7's centred/rearward placement, LED hole and cable guides, but lowered the PCB seating shoulders and peg tips by 1.00 mm for the soldered-USB installation. Restored the original shorter button geometry. The fitted light-pipe filament must also be 1.00 mm shorter. V7 was explicitly preserved as its own variant. | Main low-profile feature-complete public option. Board standoff 4.20 mm, short button, light pipe around 4.7 mm as a starting length. |

## Dimension summary

Board standoff means the distance from the flat inside panel face to the component-facing PCB seating plane. Peg fitting length is 1.00 mm plus a 0.50 mm tapered tip on the round-peg versions; it is not the full standoff height.

| Revision | Peg diameter | Board standoff | Button aperture | Total printed button height | Centred/rearward layout | LED hole / USB guides |
| --- | --- | --- | --- | --- | --- | --- |
| v1 | 2.10 mm | 4.20 mm | 4.40 mm | 3.69 mm | No | No / No |
| v2 | 1.90 mm straight | 4.20 mm | 4.40 mm | 3.69 mm | No | No / No |
| v3 | 2.10 mm | 4.20 mm | 4.40 mm | 3.69 mm | No | No / No |
| v4 | 2.20 mm | 4.20 mm | 4.40 mm | 3.69 mm | No | No / No |
| v5 | 2.10 mm | 4.20 mm | 5.00 mm | 3.69 mm | No | No / No |
| v6 | 2.10 mm | 5.20 mm | 5.00 mm | 4.69 mm | Yes | No / No |
| v7 | 2.10 mm | 5.20 mm | 5.00 mm | 4.69 mm | Yes | Yes / Yes |
| v8 | 2.10 mm | 4.20 mm | 5.00 mm | 3.69 mm | Yes | Yes / Yes |

## Retaining ring

The ring stayed in the development archives, but the maker reports that it does not stay in place and is unnecessary in the assembled mount. It is intentionally excluded from the public print sets. The button flange prevents outward loss and the installed PCB prevents inward loss. The integral circular button guide remains on each flap. Do not describe a retainer-based 0.60 mm hard travel stop as a guaranteed feature of the ring-free assembly; check button operation on the actual board.

## Validation status

Current maker feedback: all development versions printed and tested on the stated A1/PLA setup. The centred/rearward variants and both heights are preferred. The separate ring does not hold reliably.

Digital checks already recorded for the selected files cover valid CAD, connected/watertight printable meshes, fitting peg profiles, height/position changes and LED/guide placement against the wireless reference. This audit copies those checked meshes without editing them. A statement that the maker tested them is not a guarantee of fit with every filament, printer, USB lead or MMS2 configuration.
