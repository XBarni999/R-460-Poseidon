# R-460 Poseidon 1.5.4

Update focusing on new engine exhaust effects and critical damage attribution / kill credit fixes.

### New Features & Improvements
- **New Engine Exhaust Effects**: Overhauled jet/rocket motor particle and exhaust visual effects for both aircraft-launched and ground-launched (TEL) variants, delivering enhanced supersonic thrust plume aesthetics.

### Fixes & Combat Scoring
- **Damage Attribution & Kill Credit Fix**: Fixed an issue where the missile's warhead detonation was treated as neutral world damage. `PoseidonTELRuntime` now properly binds the launcher unit's `NetworkownerID` and `NetworkHQ` upon launch, ensuring that all splash, impact, and blast damage correctly credit the player/launcher and award kill scores.

Install `R-460 Poseidon_1.5.4.nobp` and `PoseidonTELRuntime.dll` together. Remove older Poseidon `.nobp` files before installing. Nuclear Option 0.34.2, BepInEx, and NOBlueprinter are required.
