# ChangeLog

## Version [v1.4.5](https://github.com/krossgg/GregTech-Modern/compare/v1.4.3...v1.4.5)
### Added

- Replace wrench with plate in bender recipe by JuiceyBeans in [#2057](https://github.com/GregTechCEu/GregTech-Modern/pull/2057)
- Machine Ownership by YoungOnionMC in [#1970](https://github.com/GregTechCEu/GregTech-Modern/pull/1970)
- Give coils an actual EU discount in EBF by YoungOnionMC in [#2055](https://github.com/GregTechCEu/GregTech-Modern/pull/2055)
- Multiblock Display Text for Outputs by YoungOnionMC in [#2048](https://github.com/GregTechCEu/GregTech-Modern/pull/2048)
- Make magnetic tool property pull mob drops too by JuiceyBeans in [#2037](https://github.com/GregTechCEu/GregTech-Modern/pull/2037)
- Yeet Sand from OreVeins by Ghostipedia in [#2078](https://github.com/GregTechCEu/GregTech-Modern/pull/2078)
- Give torch placing a sound by YoungOnionMC in [#2091](https://github.com/GregTechCEu/GregTech-Modern/pull/2091)
- Port of 1.12 hard ebf recipe by YoungOnionMC in [#2093](https://github.com/GregTechCEu/GregTech-Modern/pull/2093)

### Fixed

- Give coils an actual EU discount in EBF by YoungOnionMC in [#2055](https://github.com/GregTechCEu/GregTech-Modern/pull/2055)
- Update tooltip capitalization for consistency by JuiceyBeans in [#2061](https://github.com/GregTechCEu/GregTech-Modern/pull/2061)
- Misc recipe fixes by JuiceyBeans in [#2056](https://github.com/GregTechCEu/GregTech-Modern/pull/2056)
- Torch Behaviour, now with less duping by YoungOnionMC in [#2067](https://github.com/GregTechCEu/GregTech-Modern/pull/2067)
- Fix broken treated wood recipes by Electrolyte220 in [#2045](https://github.com/GregTechCEu/GregTech-Modern/pull/2045)
- Remove any connected miner pipes when the machine is removed by Vextin in [#2064](https://github.com/GregTechCEu/GregTech-Modern/pull/2064)
- Add missing flags for materials by JuiceyBeans in [#2024](https://github.com/GregTechCEu/GregTech-Modern/pull/2024)
- Output Line Infinite formatting by YoungOnionMC in [#2082](https://github.com/GregTechCEu/GregTech-Modern/pull/2082)
- AE2 Integration: Use smart cable connection type for ME Connected blocks by RealKC in [#2087](https://github.com/GregTechCEu/GregTech-Modern/pull/2087)
- Missing progress lang for some multis by YoungOnionMC in [#2090](https://github.com/GregTechCEu/GregTech-Modern/pull/2090)
- Fix fluid drilling rig not working with 2 hatches by YoungOnionMC in [#2092](https://github.com/GregTechCEu/GregTech-Modern/pull/2092)
- Fix Wooden sign recipes by YoungOnionMC in [#2094](https://github.com/GregTechCEu/GregTech-Modern/pull/2094)
- Stone tags and LPG localisation by JuiceyBeans in [#2095](https://github.com/GregTechCEu/GregTech-Modern/pull/2095)
- Add more interactions + fixes for Lighter by JuiceyBeans in [#2075](https://github.com/GregTechCEu/GregTech-Modern/pull/2075)

### Changed

- Update manage-pr-labels.yml by krossgg in [#2062](https://github.com/GregTechCEu/GregTech-Modern/pull/2062)
- Change Wooden Multiblock Tank recipe to use copper instead of lead by JuiceyBeans in [#2107](https://github.com/GregTechCEu/GregTech-Modern/pull/2107)

 
Version: 1.4.1

### ADDITIONS:
 
- Added Textures for Computer Casings styled around the new texture standard
- Fluid Tags for Molten Fluids & Plasmas
- Datasticks will now render the primary item within contained data when holding SHIFT

### CHANGES:

- Parallel Hatches can no longer be shared.
- SI Formatting for large fluid amounts
- Updated all hatches and busses recipes to match GTCEU : 1.12.2
- Hazard gear works in curios slots
- Changed the location of the dimension icon for dimension based recipes
- KubeJS Support for research methods
- Research recipes now display CWU total in JADE and use the proper EU values.
- PACK DEVS ! - Can now define render toggles for multiblocks
- ADDON DEVS ! - OCLogic has been modified, please verify your addons reflect these new changes.

### FIXES:
   
- Fixed Rubber Leaves and Saplings not being able to compost.
- Fix fluid output slots accepting manual inputs
- Large variety of recipe logic and OC logic fixes
- Fixed AEParts in assembly lines having wrong recipe voltages
- Fixes Crashes due to null recipes caused by HighTier being disabled
- Fixed PartialNBT usage in recipes
- Various KubeJS recipe fixes
- ME Export Bus is now considered an "EXPORT_ITEMS" part ability
- Fix bedrock ore miner not overclocking
- Assembly line Structure no longer allows MEBufferParts

