# MMS2 Pico 2 W flap mounts for MC BlueBridge

These replacement MMS2 flaps let you mount a Raspberry Pi Pico 2 W inside the case for MC BlueBridge, with an external button to press BOOTSEL for pairing.

I made these for my own Multisystem2. There are left and right versions, so you can use whichever side suits the space and wiring in your machine. All three options use the later centred position, moved 3.3 mm towards the rounded end of the flap.

The designs have been printed and tested on a Bambu A1 using PLA. I have kept the useful variants here rather than including every early fit-test revision.

## Choose a variant

| Variant | PCB standoff | Button | Light pipe | Cable guides |
| --- | --- | --- | --- | --- |
| Low profile - LED and cable guides (v8) | 4.2 mm | Short | Yes | Yes |
| Raised - LED and cable guides (v7) | 5.2 mm | Long | Yes | Yes |
| Raised basic (v6) | 5.2 mm | Long | No | No |

The standoff is measured from the flat inside face of the flap to the PCB seating plane. Choose one complete variant and use the button from the same folder. Do not mix the long button with the low-profile mount.

The low-profile version was made for an installation with the USB wires soldered to the Pico. The raised versions put the PCB 1 mm higher. USB plug bodies and cable bends vary, so check your own lead and internal clearance if using the socket. The raised version is not a promise that every micro-USB plug will fit.

## What's included

- Left and right replacement flap for each option. You only need the side you are fitting.
- Matching short or long BOOTSEL button in each variant folder.
- Small peg, button-opening, filament-hole and cable-tie fit tests.
- Smaller complete mounting-pattern/button tests for both PCB heights.

The supplied models use a bare Pico 2 W without GPIO headers, 2.10 mm fitting pegs and a 5.00 mm nominal button opening. Fit depends on your printer and filament, so try the small test pieces first if needed.

## Fitting

Insert the button from inside the flap, with the wide flange inside and the narrow end through the opening. Mount the Pico with its component side facing the flap and USB towards the straight end. Check that the external button presses BOOTSEL and releases freely.

There is no separate retaining ring to print. The button flange keeps it from falling outwards and the fitted Pico captures it from the inside.

For the LED versions, use a short piece of 1.75 mm filament as a light pipe. For an outside-flush end, start around 5.7 mm long on the raised version or 4.7 mm on the low-profile version, then trim to suit your board. Leave a small gap before the LED; the filament must not push on the component. Check a tight hole with the PCB removed.

The cable guides take a small 2.5 mm cable tie. Use them to secure the USB lead, plug body or insulated wire bundle and keep pulling force off the Pico's connection. Check that the tie and its lock clear the rest of your installation.

## Printing

The parts are supplied in millimetres at 100% scale, with the flat outside face of the flap towards the bed. The working process used a 0.12 mm quality profile on the A1 with PLA. Use your own slicer and inspect support needs, especially under the button flange and across the cable-tie bridges. Keep the same settings between your fit test and full flap.

This download contains STLs, not a pre-sliced or verified printer-specific 3MF profile. The included overview is a CAD render.

## Compatibility and credits

These are modifications of the Heber Multisystem2 v17 / C183 flap files dated 23 June 2025. Check your case revision and space around any NFC reader, display, NVMe adapter and wiring.

The original enclosure was designed by Richard Horne (RichRap) for Heber Ltd and The Retro Collective. Original model: [MiSTer Multisystem2 Analogue enclosure](https://www.printables.com/model/1378481-mister-multisystem2-analogue-fpga-based-retrogamin). This remix adds the Pico mount, external BOOTSEL button and the selected light-pipe/cable-guide features.

The original model is listed as Creative Commons Attribution-ShareAlike (CC BY-SA). Keep that attribution and the corresponding ShareAlike licence on this remix.

MC BlueBridge firmware is by Anime0t4ku: [project and firmware information](https://github.com/Anime0t4ku/MC-BlueBridge). This download contains mechanical parts; it does not include the firmware.
