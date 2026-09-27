# Ashfen DE-LAUNCHER

Closed-source **Nuclear Option** BepInEx plugin. Source is not included.

Manufacturer: **Ashfen**.

This is a **submod** of [G1E](https://github.com/iallemege/G1E). It does not replace G1E. G1E and `BIA.Runtime` still have to be installed.

DE-LAUNCHER is a directed-energy weapon. Press K while G1E is powered. Targets in the forward cone out to 50 km, and targets within 3 km behind the aircraft, take the kinetic hit. Ground vehicles and ships in that volume also take damage, weaker with distance. A full-strength hit destroys a vehicle or ship. The mach ring is visual only.

Using it faults about half of the G1E displays. Those screens show ERROR. Press U to shut the system down, then U again to boot the faulted screens. The radio line is from DE-S: "Preparing overclock detonation."

## Install

1. Install G1E and `BIA.Runtime` first.
2. Copy `plugins/G1EAshfen/G1E.Ashfen.dll` into `BepInEx/plugins/G1EAshfen/`.
3. Remove or rename any older `BepInEx/plugins/PERV.dll`. Do not run both.
4. Fully quit Steam, then launch.

Download the zip from **Releases**. This repository does not ship source.

## License

Proprietary. All rights reserved. See `LICENSE`.
