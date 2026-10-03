# Changelog

## 1.5.3 - 2026-10-03

- Complete visual overhaul & 2079 modernization:
  - Redesigned sleek supersonic aerodynamic fuselage (0.49 m diameter) eliminating the bulky profile while preserving supersonic handling.
  - Detailed 16-petal vectoring exhaust nozzle with articulating titanium thermal bloom petals and boattail maintenance access panel.
  - Full 3D interior combustion chamber: sealed turbine bulkhead, 24 aerodynamic stator blades, concentric afterburner flame holder spray rings, 8 guide vanes, and central tail bullet cone.
  - Symmetrical machined aluminum attitude control thruster pods on both starboard (+X) and port (-X) forward radome flanks.
  - Masterwork 2K PBR textures: naval anthracite coating, English military stencils (R-460 POSEIDON, NO STEP), hazard stripes, and calibrated dark PBR metallic/smoothness (fixing previous washed-out engine reflections in Unity).
- Fixed R-460N Tactical Nuclear missile encyclopedia & cost:
  - Corrected unit definition reference in R_460_Poseidon_Nuclear.prefab so the in-game Encyclopedia accurately reports the 34 million cost, nuclear anti-ship role, and 1.5 kt yield instead of falling back to the conventional missile definition.

## 1.5.0 — 2026-09-29

- Added a twin Poseidon mount with two missiles and one launch per trigger press for Medusa, Alkyon, and Darkreach hardpoints.
- Added the separate R-460N Poseidon tactical nuclear missile (1.5 kt), its encyclopedia entry, weapon mount, and compact vanilla nuclear explosion effect. The nuclear round costs 34 million and has slightly stronger armor and durability.
- Added a real terminal pop-up profile to aircraft, nuclear, and TEL missiles: up to 300 m of climb from 6.5 km, tapering into a dive near the target.
- Retuned the aircraft-launched motors so the encyclopedia's calculated top-speed figure is close to the 1,800 km/h flight cap.
- Kept the nuclear variant available in normal encyclopedia and loadout menus by removing Event Content gating.

## 1.4.1 — 2026-09-28

- Reduced both R-460 missile prices from 30 to 3 million.
- Reduced radar size from 0.01 to 0.008.
- Increased armor tier from 0.1 to 0.12, damage tolerance from 30 to 35, and pierce/blast armor from 10 to 12.
- Applied the same balance to aircraft- and TEL-launched missiles.

## 1.4.0 — 2026-09-28

- Equipped the TEL missile with the vanilla AShM1 VLS booster model and native separation component.
- Reused the game's booster sound, fire, smoke, and trail effects.
- Reused the game's cruise motor particle effect on both R-460 missile variants.
- Started the TEL cruise motor after the five-second booster burn.
- Set both missile definitions' missile identity to 1 and air identity to 0.14, matching the game's anti-ship missile convention, and added standard missile icons for target recognition.
- Kept the existing radar size of 0.01 and the TEL's ship-only targeting logic.
