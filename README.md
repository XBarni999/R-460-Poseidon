# R-460 Poseidon

An anti-ship cruise missile mod for **Nuclear Option**, built with **NOBlueprinter**.

Poseidon launches from compatible aircraft or the R-460 Poseidon TEL. It follows a low route over water, then makes lateral evasive maneuvers and a terminal pop-up before diving on its target. A separate R-460N carries a 1.5 kt tactical nuclear warhead.

## Features

- Sea-skimming cruise profile with inertial midcourse and optical terminal guidance.
- Terminal evasive maneuvers and a pop-up of up to 300 m within 6.5 km of the target.
- Custom R-460 model and textures.
- Conventional and nuclear aircraft mounts for Medusa, Alkyon, and Darkreach.
- Twin Poseidon mount with two missiles, fired one per trigger press.
- R-460 Poseidon TEL: a separate mobile ground launcher with two missiles, based on the game's MSV Ballistic Missile Launcher. It attacks tracked enemy ships within 108 km.
- Reduced explosive yield and penetration compared with the test build.

<img width="1027" height="500" alt="image" src="https://github.com/user-attachments/assets/dfd549c9-5307-4e51-b76e-aba308811e8c" />


## Requirements

- Nuclear Option. Built against game version **0.34.2**.
- BepInEx and [NOBlueprinter](https://github.com/nikkorap/NOBlueprinter-Releases/releases/latest). The TEL target filter uses the included BepInEx plugin.

## Install

1. Install BepInEx and NOBlueprinter for Nuclear Option.
2. Place `R-460 Poseidon_1.5.3.nobp` and `PoseidonTELRuntime.dll` in `Nuclear Option/BepInEx/plugins`. Both files are included in the install ZIP.
3. Start the game, equip R-460 Poseidon on a compatible aircraft or place the R-460 Poseidon TEL as a ground unit. The TEL automatically engages enemy ships that its faction has detected within 108 km.

Remove any older `R-460 Poseidon_*.nobp` file before installing this version to avoid loading two copies of the weapon. Other unit types are unaffected by the TEL target filter.

## Source

The editable Unity assets and the TEL runtime source are in the separate `R-460-Poseidon-v1.5.3-source.zip` archive. This is a raw project snapshot; follow `SOURCE_README.md` inside the archive to use it. Blueprinter resolves local game asset placeholders against the installed game; the mod package does not include original game assets.

## Version 1.5.3

- Complete visual overhaul: refined 0.49m sleek aerodynamic profile, 16-petal vectoring nozzle, fully modeled interior combustion chamber and turbine, and dual machined aluminum nose thrusters.
- Masterwork 2K PBR textures: tactical naval anthracite finish, English military stencils, and calibrated PBR metallic/smoothness.
- Fixed R-460N Tactical Nuclear encyclopedia definition and 34M price display in-game.

## Version 1.5.0

- Added twin mounts, the R-460N 1.5 kt variant, and a real terminal pop-up for all Poseidon missiles.
- Priced the nuclear round at 34 million and increased its survivability slightly.
- Corrected the aircraft missile speed estimate shown in the encyclopedia.

## Version 1.4.1

- Reduced the missile price from 30 to 3 million.
- Reduced radar size by 20% and increased armor slightly for both launch variants.

## Version 1.4.0

- Added the game's AShM1 VLS booster model, booster audio, fire, smoke, trail, and native booster separation behavior to the TEL missile.
- Added the game's cruise motor particle effect to both aircraft- and TEL-launched missiles; the TEL cruise motor starts after the five-second booster burn.
- Corrected missile target classification and icons so air-defense systems can recognize the R-460 as a missile.
- Retained the TEL's ship-only datalink targeting within 108 km.

See [CHANGELOG.md](CHANGELOG.md) for release details.

## Version 1.2.0

- TEL fire control now uses the faction datalink and checks targets every two seconds, without waiting for strategic weapon authorization.
- TEL only considers detected enemy ships within 108 km. Ground targets, aircraft and submarines are excluded by the included runtime plugin.
- Improved the missile's target eligibility against armored ships.

## Version 1.1.0

- Added the R-460 Poseidon TEL with two launch positions and two missiles.
- Extended terminal guidance to 6.5 km and made lateral maneuvers stronger over the final 6 km.
- Removed the minimum speed threshold for the maneuvers.

## Version 1.0.0

- Fixed target eligibility and the incorrect `OUT OF ARC` cue.
- Stabilized flight and low-altitude ship approach.
- Fixed the mounted visual remaining on the pylon after launch.
- Added restrained terminal weaving and reduced warhead damage.

Nuclear Option and NOBlueprinter are separate projects; this is an unofficial community mod.
