<h1 {{{ CENTER_ALIGN }}}>Release 1.7.4</h1>

# Changes Since 1.7.3

## Balancing Changes:
### Both Modes:
* **Misc NuclearCraft Balancing Tweaks** ([#1188](https://github.com/Nomi-CEu/Nomi-CEu/pull/1188)) - @IntegerLimit ([`1599568`](https://github.com/Nomi-CEu/Nomi-CEu/commit/1599568b639043ef1d22471a82059d4ae6372096))
  * Uranium 238 from Renewable Red Granite has been buffed to 1% (+1%)
    * Uranium 233 Fuels are now Passivable, with TBU Breeding!
  * Thermal Centrifuge Times for Prepared Thorium have been reduced by ~14%
  * ields from Depleted Fuels have been increased by 10%
* Misc Thermal Expansion Improvements ([#1127](https://github.com/Nomi-CEu/Nomi-CEu/pull/1127)) - @IntegerLimit ([`9474cca`](https://github.com/Nomi-CEu/Nomi-CEu/commit/9474cca4c5015dde085fa2e43950840d6dc4f35a))
  * Streamlines Portable Tank Upgrade Recipes
    * Now takes Upgrade/Conversion Kits instead of Custom Materials
    * Portable Tanks could be Upgraded with Kits as Placed Blocks Previously
* Reduce Plutonium 239 Fusion Recipe Power Consumption ([#1265](https://github.com/Nomi-CEu/Nomi-CEu/pull/1265)) - @IntegerLimit ([`157f647`](https://github.com/Nomi-CEu/Nomi-CEu/commit/157f64796124ff1593395305730b84f5b1ac0bd2))
  * Reduces Confusion by Allowing P-239 Fusion with MK I Reactors
  * Fixes [#1230](https://github.com/Nomi-CEu/Nomi-CEu/issues/1230)
* Buff Enriched Naquadah for the EM Separator ([#1261](https://github.com/Nomi-CEu/Nomi-CEu/pull/1261)) - @D-Alessian ([`59f99b8`](https://github.com/Nomi-CEu/Nomi-CEu/commit/59f99b83aae9cfa479397d04d633034235f837ff))
  * Buffs Enriched Naquadah from 15% + 4% to 1 Guaranteed + 20% + 5%
* Change EV Coils to Use Platinum ([#1231](https://github.com/Nomi-CEu/Nomi-CEu/pull/1231)) - @IntegerLimit ([`0942a30`](https://github.com/Nomi-CEu/Nomi-CEu/commit/0942a30eea420e05c8e740a0794c9e5071abfa1d))
  * Used to use Tungstensteel, which made for awkward progression.
* Create Crafting Recipes for Early GT Cells ([#1132](https://github.com/Nomi-CEu/Nomi-CEu/pull/1132)) - @IntegerLimit ([`a75526d`](https://github.com/Nomi-CEu/Nomi-CEu/commit/a75526ddb95738d17898fe0fd746c493053922b8))
* Update Nomi-Labs to v0.11.0 ([#1126](https://github.com/Nomi-CEu/Nomi-CEu/pull/1126)) - @IntegerLimit ([`37bbdfe`](https://github.com/Nomi-CEu/Nomi-CEu/commit/37bbdfe0a37bc0ad2833c2afae02bc5d7cde1698))
  * Increase Solid Fuel Efficiency 10x for Large Boilers
* Add Ender Lily Item to Resonant Ender Recipe ([#1105](https://github.com/Nomi-CEu/Nomi-CEu/pull/1105)) - @v3ect0rgames ([`a715a22`](https://github.com/Nomi-CEu/Nomi-CEu/commit/a715a22afaa25808736566a565c5b541cf4228eb))
  * Fixes [#1076](https://github.com/Nomi-CEu/Nomi-CEu/issues/1076)
* Remove Glowstone Electrolyzer Recipe ([#1096](https://github.com/Nomi-CEu/Nomi-CEu/pull/1096)) - @IntegerLimit ([`6bbd2bd`](https://github.com/Nomi-CEu/Nomi-CEu/commit/6bbd2bd826eada4593740e344fccd21cd4651aee))
  * Accidentally Added in 1.7-alpha-3
  * Fixes Phosphorous Balancing

### Hard Mode:
* **Rebalancing of Various Thermal Dust Related Recipes** ([#1187](https://github.com/Nomi-CEu/Nomi-CEu/pull/1187)) - @IntegerLimit ([`b975f34`](https://github.com/Nomi-CEu/Nomi-CEu/commit/b975f348c8025f3080fcb10a0c25828598c53f9d))
  * **Crafting Recipes for Thermal Elemental Dusts have been REMOVED!**
  * Changed Thermal Powder -> Dust Recipes to Not Need Redstone
  * Added an Alternative Elemental Reduction Fluid Recipe, Designed to be Passivable
  * Changes the Carbon + Sulfur Chem Reactor Recipe for Blaze Powder to MV
* **Add Tritanium Recipe to Universal Crystalizer** ([#1184](https://github.com/Nomi-CEu/Nomi-CEu/pull/1184)) - @IntegerLimit ([`aacc143`](https://github.com/Nomi-CEu/Nomi-CEu/commit/aacc143875f7d0948d635d4aa2622d895e80293c))
  * Excluding Parallels and OCs, the recipe is 21.6x faster than a Fusion MK III!
* Small Earlygame Tweaks ([#1139](https://github.com/Nomi-CEu/Nomi-CEu/pull/1139)) - @IntegerLimit ([`8b5bcf1`](https://github.com/Nomi-CEu/Nomi-CEu/commit/8b5bcf15b7d41996112643fd227d922019735d59))
  * Adds a Log -> Stick Shortcut Recipe
  * Removes Paper Recipes Directly from Sugar Cane and Rice
  * Makes Wood Pulp Crafting Output 2 Instead of 4
* Revamp Concrete Bucket Crafting Recipe ([#1142](https://github.com/Nomi-CEu/Nomi-CEu/pull/1142)) - @IntegerLimit ([`86cb1fb`](https://github.com/Nomi-CEu/Nomi-CEu/commit/86cb1fbf8582e6002ef2c720b2a9272ec43f2dff))
  * Now takes an Empty Cell as Input, and outputs a Filled Cell

## Performance Improvements:
* Update Alfheim Lighting Engine to v1.5 ([#1227](https://github.com/Nomi-CEu/Nomi-CEu/pull/1227)) - @IntegerLimit ([`1d2257f`](https://github.com/Nomi-CEu/Nomi-CEu/commit/1d2257f28f907f254c63192bacaf1aaedc122872))
  * Fixes Lighting Issues Across Chunks (Usually Experienced While Mining)
  * Increases Stability of FPS
  * Potentially Slightly Reduces Memory Consumption
* Greatly Improves Solar Panel Performance, especially in Grids ([#1216](https://github.com/Nomi-CEu/Nomi-CEu/pull/1216)) - @IntegerLimit ([`136d2d0`](https://github.com/Nomi-CEu/Nomi-CEu/commit/136d2d0df247d20b2a0838ea126ce6e8756e64dd))
  * Up to 60-70% Performance Improvements for Solar Grids!
  * Solar Grids now perform BETTER than Solar Towers!
* Change Labs' GT Recipe Search to Fast Discarded Tree ([#1168](https://github.com/Nomi-CEu/Nomi-CEu/pull/1168)) - @IntegerLimit ([`0f0d022`](https://github.com/Nomi-CEu/Nomi-CEu/commit/0f0d0226174d7773a0c332001865e74c52da4af3))
  * Slight Improvement in Game Loading Time! (Around 4%)

## Feature Additions:
### Quality of Life:
* Add Uber Conduit Probe ([#1099](https://github.com/Nomi-CEu/Nomi-CEu/pull/1099)) - @D-Alessian ([`caab28d`](https://github.com/Nomi-CEu/Nomi-CEu/commit/caab28d69e7016785308526141c45c4129654035))
  * Allows Mass-Configuring of Conduit Connections

### Both Modes:
* **Allow Usage of Any Fluid Container in Crafting** ([#1142](https://github.com/Nomi-CEu/Nomi-CEu/pull/1142)) - @IntegerLimit ([`86cb1fb`](https://github.com/Nomi-CEu/Nomi-CEu/commit/86cb1fbf8582e6002ef2c720b2a9272ec43f2dff))
  * Allows using ANY Fluid Container (GT Drums/Cells, EIO Tanks, Thermal Tanks, etc.) in Crafting Recipes, Substituting Filled Buckets
  * Also adds Crafting Recipe for Obsidian (Water + Lava)
* **Update Nomi-Labs to v0.11.0** ([#1126](https://github.com/Nomi-CEu/Nomi-CEu/pull/1126)) - @IntegerLimit ([`37bbdfe`](https://github.com/Nomi-CEu/Nomi-CEu/commit/37bbdfe0a37bc0ad2833c2afae02bc5d7cde1698))
  * Add Bronze Cell (Capacity: 8B)
  * Increase Steel Cell Capacity to 16B (From 8B)
  * Allow GT Cells to Place/Collect Fluids
* **Disable NuclearCraft Fission Reactor Meltdowns** ([#1191](https://github.com/Nomi-CEu/Nomi-CEu/pull/1191)) - @IntegerLimit ([`967cecf`](https://github.com/Nomi-CEu/Nomi-CEu/commit/967cecfa4a8829ef034f9876113e9324bebfc8ec))
* **Misc The One Probe Improvements** ([#1182](https://github.com/Nomi-CEu/Nomi-CEu/pull/1182)) - @IntegerLimit, @Mireole ([`678c914`](https://github.com/Nomi-CEu/Nomi-CEu/commit/678c9143734e96ae234bd4aa36f72f79a3906a52), [`6830743`](https://github.com/Nomi-CEu/Nomi-CEu/commit/6830743eabc1ac30209f7d3eb6d5ffc6b1db4416))
  * Improved Display of Fluids
    * Removed Duplicate Textual Display
    * Improved Compactness and Readability
  * Added Display of GT Machine Recipe Outputs
    * Originally from GregicProbeCEu, but changes were made:
      * Improved Compactness
      * Merging of Item and Fluid Outputs into One Display
      * Removed Display for Generators
      * Fixed Fluid Localization
  * Improved Ordering
    * Consistent Grouping of Items and Fluid Information
    * Moves Energy Information to Bottom
* Improvements to Advanced Memory Card ([#1169](https://github.com/Nomi-CEu/Nomi-CEu/pull/1169)) - @IntegerLimit ([`39a30e6`](https://github.com/Nomi-CEu/Nomi-CEu/commit/39a30e6bcb377f41152ba580a003ed623c31585f))
  * Improved Mouse and Keyboard Interactions
  * Improved Renaming Interactions
  * Display of Distance for Listed P2Ps
  * Improved Default Sorting
  * Sort Modes and Sort Direction
  * Filtering by Distance
  * Selected P2P Blinks instead of being Outlined in Green
* Update Nomi Labs to v0.14.0 ([#1242](https://github.com/Nomi-CEu/Nomi-CEu/pull/1242)) - @IntegerLimit ([`a8d9f66`](https://github.com/Nomi-CEu/Nomi-CEu/commit/a8d9f664a287f0d910751c3500ec2784eb47b7d5))
  * Allows for Links and Copyable Parts in Quest Descriptions
  * Validates Dedicated Servers and Clients have Same Mode
  * Disables Muffler Hatch Ash Production, improving performance for High Parallel Multiblocks with Mufflers
  * Displays y-levels in Prospector, and waypoints set respect Ore y-levels
  * Defaults Prospector to Dark Mode, improving visibility of (most) Ores
  * Displays a 'Welcome Message' on server start, to clarify server is ready
* Display of Custom Names for AE2 Blocks and Parts in TOP ([#1169](https://github.com/Nomi-CEu/Nomi-CEu/pull/1169)) - @IntegerLimit ([`39a30e6`](https://github.com/Nomi-CEu/Nomi-CEu/commit/39a30e6bcb377f41152ba580a003ed623c31585f))
* Adds a Tooltip Showing Contents of Drawers ([#1252](https://github.com/Nomi-CEu/Nomi-CEu/pull/1252)) - @IntegerLimit ([`8d52755`](https://github.com/Nomi-CEu/Nomi-CEu/commit/8d5275511908e1bcc4e95d4e259d5203d584f2b3))
* Allow NuclearCraft Active Coolers to Permeate Fluids ([#1249](https://github.com/Nomi-CEu/Nomi-CEu/pull/1249)) - @D-Alessian ([`4a4ac94`](https://github.com/Nomi-CEu/Nomi-CEu/commit/4a4ac94c676db9af9a9764bfe65643d7172b6f99))
  * Allows Active Coolers to automatically spread fluid to directly adjacent Active Coolers, without pipes.
* Update AE2 to v0.56.6 ([#1242](https://github.com/Nomi-CEu/Nomi-CEu/pull/1242)) - @IntegerLimit ([`a8d9f66`](https://github.com/Nomi-CEu/Nomi-CEu/commit/a8d9f664a287f0d910751c3500ec2784eb47b7d5))
  * Makes items inserted into Interfaces skip the buffer, and go straight to storage
  * Whilst this release had major issues, they have been patched out with Nomi Labs
* Add Seperate Icons and Titles for Expert Mode ([#1219](https://github.com/Nomi-CEu/Nomi-CEu/pull/1219)) - @IntegerLimit ([`2b864cc`](https://github.com/Nomi-CEu/Nomi-CEu/commit/2b864ccb95d9080120c9f06dcd57b768cfe0ae76))
* Add Maceration Recipe for Black Quartz Ore ([#1243](https://github.com/Nomi-CEu/Nomi-CEu/pull/1243)) - @IntegerLimit ([`946d0cd`](https://github.com/Nomi-CEu/Nomi-CEu/commit/946d0cd4da03204c1df5a2c44c266b5c3027692e))
* Improves Phantomface GUIs and Phantom Connector Warnings ([#1216](https://github.com/Nomi-CEu/Nomi-CEu/pull/1216)) - @IntegerLimit ([`136d2d0`](https://github.com/Nomi-CEu/Nomi-CEu/commit/136d2d0df247d20b2a0838ea126ce6e8756e64dd))
* Change Actually Additions' Laser Tool to GT Screwdriver ([#1166](https://github.com/Nomi-CEu/Nomi-CEu/pull/1166)) - @ChromaPIE ([`707c875`](https://github.com/Nomi-CEu/Nomi-CEu/commit/707c87504edcec907251796a26ac4bfb8764c1e9))
* Add OreDict to Radium Salt ([#1273](https://github.com/Nomi-CEu/Nomi-CEu/pull/1273)) - @IntegerLimit ([`cc798f3`](https://github.com/Nomi-CEu/Nomi-CEu/commit/cc798f3a4f97fc2022b10961eb81d17c3ce9b101))
* ZBGT Addon Script Compat ([#1203](https://github.com/Nomi-CEu/Nomi-CEu/pull/1203)) - @D-Alessian ([`7995b18`](https://github.com/Nomi-CEu/Nomi-CEu/commit/7995b18290720dcd3080c4bc0e3fd4df252dc3ed))
  * **Only activated if ZBGT is manually installed!**
  * Rebalances recipes for Mega Multiblocks
  * Adds recipes for most ZBGT Creative Items

## Quest Book Changes:
### Both Modes:
* Improve Description of Parallelization Mechanics ([#1287](https://github.com/Nomi-CEu/Nomi-CEu/pull/1287)) - @IntegerLimit ([`eb09ee2`](https://github.com/Nomi-CEu/Nomi-CEu/commit/eb09ee23f302516f6b55d19d391d45efd593de19))
* Misc Quest Book Fixes and Improvements: Round 2 ([#1267](https://github.com/Nomi-CEu/Nomi-CEu/pull/1267)) - @IntegerLimit ([`09e48f9`](https://github.com/Nomi-CEu/Nomi-CEu/commit/09e48f9f9237c8fca30a20322b859eecaa6a6bd8))
  * **Misc**
    * Large Improvement to Fission Reactor Quests
      * Mentions the Lack of Meltdown
      * New Quests for Reactor Types (Power vs Breeding), Planning Reactors, and Pasting Reactors
      * Mentioning New Red Granite Processing Route for Uranium 238
      * Adds a link to a new reactor utility tool for Nomi-CEu
      * Splits up information
    * Updates Muffler Hatch Information with New Disabled Status
    * Add Links to Recommended AE2 Guides, GitHub Pages and Discord
    * Recommend LCR in Early HV
    * Clean up Naquadah Processing Dependencies
    * General Typo and Grammar Fixes
  * **Additions**
    * Mentions AE2 Shortcut Recipes in EV
    * Mentions Methods to Obtain Meat for Wetware
    * Mentions Spades
    * Mentions Auto Balancing Solars in Solar VIII Quest
    * Adds Quest for Passive Crafters
    * Adds Quest for Extra Utilities 2 Player Chest
    * Adds Quest for Draconic Evolution's Place in World
    * Adds Seperate Quest for Distinct Buses
  * **Fixes**
    * Fixes Interdimensional Networking Quest and PMT Quest not ignoring NBT
    * Fixes Nitrogen Quest in LV, when Atmospheric Collector is only available in MV
    * Fixes Polariser Quest mentioning the wrong max voltage
    * Fixes the word 'Cables' being used for Superconductors
* Miscellaneous Quest Book Fixes and Improvements ([#1164](https://github.com/Nomi-CEu/Nomi-CEu/pull/1164)) - @IntegerLimit ([`59ff298`](https://github.com/Nomi-CEu/Nomi-CEu/commit/59ff298dd01759896d38c7f8ce0896d4421a0798))
  * **Misc:**
    * Rearranges Genesis Chapter
    * Slight Rearrangement of Mid Game Chapter
    * Streamlines Instruction Locations for Multi Building
    * Sorts Required Items for EBF and Pyrolyse Oven Quests
    * General Clarity and Coloring Improvements
    * Mentions Sun's Black Hole Background in Warp Core Quest
    * Updates Advanced Memory Card Quest With Changes in Labs 0.12.0
    * Makes Flux Capacitor Quest No Longer Require Battery Buffer
  * **Additions:**
    * Adds Quest for Excitation Coil Night Vision
    * Adds Quest for Earlygame Fluid Storage and Collection
    * Adds Quest for Simple Automation of Machines Pre-AE2
    * Adds Mention of Black Hole Background in the Sun for Warp Core
    * Adds Quest for AE2 Cutting Knives
    * Adds Quest for Wireless Charging
  * **Improvements:**
    * Improves Dependency Chains in Genesis
    * Improves Interdimensional Networking Quest, adding more Debug and Setup Steps
    * Improves Research Related Dependency Chains
  * **Fixes:**
    * Fixes Issues with Polyethylene Boost Recommendation
    * Fixes Dependencies of Magnesium End Game Quest
    * Fixes Naquadah Reactor Quest Requesting Energy Hatch instead of Dynamo Hatch
  * **Removals:**
    * Removes of LBB Task in Steam Dynamo Quest (Unsuitable Timing)
    * Removes Steel Quest in Genesis
    * Removes Hot Titanium Quest, Moves Automation Info to Vacuum Freezer
* Fixed Wrong Keybinds in FindMyItemsAndFluids Quest ([#1131](https://github.com/Nomi-CEu/Nomi-CEu/pull/1131)) - @IntegerLimit ([`1f676ed`](https://github.com/Nomi-CEu/Nomi-CEu/commit/1f676edd481fe69a3e02b5c59e9735b951239756))
* Removal of Unused Quests ([#1125](https://github.com/Nomi-CEu/Nomi-CEu/pull/1125)) - @IntegerLimit ([`cbd9b9f`](https://github.com/Nomi-CEu/Nomi-CEu/commit/cbd9b9f6a49748a894c78252d50733911820c051))
  * Streamlines Experience
  * Fixes Uncompletable Quests

### Normal Mode:
* Miscellaneous Quest Book Fixes and Improvements ([#1164](https://github.com/Nomi-CEu/Nomi-CEu/pull/1164)) - @IntegerLimit ([`59ff298`](https://github.com/Nomi-CEu/Nomi-CEu/commit/59ff298dd01759896d38c7f8ce0896d4421a0798))
  * Mentions LV Compressor Usage in Making Rubber Sheets
  * Moved Battery Buffer to The Beginning, after Electric Blast Furnace
    * When it is helpful, due to EBF's Large Power Draw
* Fix Uncompletable Quests ([#1120](https://github.com/Nomi-CEu/Nomi-CEu/pull/1120)) - @smallming675 ([`1d3d523`](https://github.com/Nomi-CEu/Nomi-CEu/commit/1d3d523a2b04ec9f56ebfdfca9b2a6c0dfc4213f))
  * Includes Palladium Quest (In End Game Tab) and Gasoline Quest
  * Issue Caused due to Invalid Dependencies

### Hard Mode:
* Misc Quest Book Fixes and Improvements: Round 2 ([#1267](https://github.com/Nomi-CEu/Nomi-CEu/pull/1267)) - @IntegerLimit ([`09e48f9`](https://github.com/Nomi-CEu/Nomi-CEu/commit/09e48f9f9237c8fca30a20322b859eecaa6a6bd8))
  * Updates for Tritanium Recipe in Universal Crystallizer
  * Update Elemental Dust and Pulsating Dust Related Quests
  * Improves Placement and Logic of Molds Quest
  * Improves Flow of Treated Wood Related Quests
* Improve Primitive Blast Furnace HM Quest ([#1176](https://github.com/Nomi-CEu/Nomi-CEu/pull/1176)) - @IntegerLimit ([`21c0093`](https://github.com/Nomi-CEu/Nomi-CEu/commit/21c0093d394c74482dc8542d4ff65624b07a9d43))
* Miscellaneous Quest Book Fixes and Improvements ([#1164](https://github.com/Nomi-CEu/Nomi-CEu/pull/1164)) - @IntegerLimit ([`59ff298`](https://github.com/Nomi-CEu/Nomi-CEu/commit/59ff298dd01759896d38c7f8ce0896d4421a0798))
  * **Misc:**
    * Reworks Genesis Chapter
      * Allows Completion with EU Power Generation or RF Power Generation
    * Allows MV Converter Quest to Accept Converter or Transformer
    * Separates Ethylene and Polyethylene into Two Quests *(originally implemented in NM)*
    * Recommends Arc Furnace (for Wrought Iron and Glass)
    * States Differences Between Steam, High Pressure, and LV Machines
    * Allows Staff of Travelling Quest to take Staff of Travelling or Dark Steel Travel Upgrade *(originally implemented in NM)*
  * **Additions:**
    * Adds Quest for Turbine Conversion Augment
    * Adds Quest for Large Bronze Boiler
    * Adds Quest for Stone Processing
    * Adds Quest for NuclearCraft Infinite Cobblestone Generator
    * Adds Quest for Black Granite Processing *(originally implemented in NM)*
    * Adds Quest for Multi Fluid Hatches *(originally implemented in NM)*
    * Adds Quest for HV Rock Breaker *(originally implemented in NM)*
    * Adds Quest for Singleblock Miners *(originally implemented in NM)*
    * Adds Quest for Rubber (From Chemical Reactor and Fluid Solidifier)
  * **Improvements:**
    * Improves Clarity of Steam Production Quest
    * Improves Dependency Chains in Plastic-Related Quests
    * Improves Quest for Rock Breakers and Increases its Visibility
  * **Fixes:**
    * Fixes Wrong Recommendation of Oil for Ethylene Production
    * Fixes Wrong Block Requested for Naquadah Reactor Quest
  * **Removals:**
    * Removes Light Fuel, Heavy Fuel and Patriot's Plastic Quests *(originally implemented in NM)*
    * Removes LV Compressor Quest

## Bug Fixes:
### Both Modes:
* Fix Fractionating Distillery Edge Case Crash ([#1257](https://github.com/Nomi-CEu/Nomi-CEu/pull/1257)) - @IntegerLimit ([`8066919`](https://github.com/Nomi-CEu/Nomi-CEu/commit/80669195ed548cad452be3fa5d791ddec6376a5f))
  * Fixes [#1256](https://github.com/Nomi-CEu/Nomi-CEu/issues/1256)
* Fix Ores not displaying in JourneyMap on the Moon ([#1245](https://github.com/Nomi-CEu/Nomi-CEu/pull/1245)) - @IntegerLimit ([`f9dc5a6`](https://github.com/Nomi-CEu/Nomi-CEu/commit/f9dc5a6fe248115dca39857232866ba33475e603))
* Update Nomi Labs to v0.14.0 ([#1242](https://github.com/Nomi-CEu/Nomi-CEu/pull/1242)) - @IntegerLimit ([`a8d9f66`](https://github.com/Nomi-CEu/Nomi-CEu/commit/a8d9f664a287f0d910751c3500ec2784eb47b7d5))
  * Fixes Prospector and Ore Drills not working with Dilithium and Black Quartz Ore
  * Removes Armor Plus Fragment Drops
  * *(Addon)* Fixes NAE2 Upgrade Cards not working in AE2 Fluid Crafting Interfaces
* Update Mouse Tweaks Unofficial to v3.1.5 ([#1232](https://github.com/Nomi-CEu/Nomi-CEu/pull/1232)) - @IntegerLimit ([`57cd5b5`](https://github.com/Nomi-CEu/Nomi-CEu/commit/57cd5b5585431b1fdb7d3a6a1ecc8aa4d09ad5e5))
  * Fixes Wheel Tweak applying across GUIs
  * Fixes [#947](https://github.com/Nomi-CEu/Nomi-CEu/issues/947)
* Fix Ore Dictionary Storage Bus Crafting Recipe ([#1226](https://github.com/Nomi-CEu/Nomi-CEu/pull/1226)) - @IntegerLimit ([`168e778`](https://github.com/Nomi-CEu/Nomi-CEu/commit/168e77885217399bd5a378cfeeaa6c7f6b74a125))
  * The recipe was the base AE2 one, not the custom Nomi-CEu one.
* Fixes Disappearing Experience when Using Dimension Cakes ([#1223](https://github.com/Nomi-CEu/Nomi-CEu/pull/1223)) - @IntegerLimit ([`6fbf2e8`](https://github.com/Nomi-CEu/Nomi-CEu/commit/6fbf2e8d11883ef14f96b5f4a81835804660d1ee))
* Fixes a Crash related to FTB Utils and Snow ([#1216](https://github.com/Nomi-CEu/Nomi-CEu/pull/1216)) - @IntegerLimit ([`136d2d0`](https://github.com/Nomi-CEu/Nomi-CEu/commit/136d2d0df247d20b2a0838ea126ce6e8756e64dd))
* Fixes GregTech Electric Chainsaw Breakage Voiding Items ([#1216](https://github.com/Nomi-CEu/Nomi-CEu/pull/1216)) - @IntegerLimit ([`136d2d0`](https://github.com/Nomi-CEu/Nomi-CEu/commit/136d2d0df247d20b2a0838ea126ce6e8756e64dd))
* Fix AE2 Blocking Config ([#1199](https://github.com/Nomi-CEu/Nomi-CEu/pull/1199)) - @IntegerLimit ([`c39603a`](https://github.com/Nomi-CEu/Nomi-CEu/commit/c39603ae101a1904f0b03119bf02cde9e1dda6da))
  * May fix issues relating to Blocking Mode and Glass Lenses (White) and Programmed Circuits
* Disable All Draconic Evolution World Generation ([#1189](https://github.com/Nomi-CEu/Nomi-CEu/pull/1189)) - @officereso ([`fd0931e`](https://github.com/Nomi-CEu/Nomi-CEu/commit/fd0931ec8f6893a0e3a81b7a01244c02a8c079f2))
  * Fixes Draconic Evolution's Draconium Ore Spawning on Advanced Rocketry's Planets
* Simplify CraftPresence Window Title Handling ([#1143](https://github.com/Nomi-CEu/Nomi-CEu/pull/1143)) - @IntegerLimit ([`e6a3912`](https://github.com/Nomi-CEu/Nomi-CEu/commit/e6a39127a7e9446da7168df69bfd6c563fca142c))
  * May fix issues with CraftPresence on Cleanroom
* Update Nomi-Labs to v0.11.0 ([#1126](https://github.com/Nomi-CEu/Nomi-CEu/pull/1126)) - @IntegerLimit ([`37bbdfe`](https://github.com/Nomi-CEu/Nomi-CEu/commit/37bbdfe0a37bc0ad2833c2afae02bc5d7cde1698))
  * Fixes ME Stocking Hatch/Bus Duplication Glitch
  * Fixes Edge Case Cleanroom Crash
  * Fixes Edge Case Effortless Building Crash

### Normal Mode:
* Fixes DME Sim Chamber Not Working with New Data Models ([#1252](https://github.com/Nomi-CEu/Nomi-CEu/pull/1252)) - @IntegerLimit ([`8d52755`](https://github.com/Nomi-CEu/Nomi-CEu/commit/8d5275511908e1bcc4e95d4e259d5203d584f2b3))

### Hard Mode:
* Fixes Incorrect Xenic Acid Breakdown ([#1216](https://github.com/Nomi-CEu/Nomi-CEu/pull/1216)) - @IntegerLimit ([`136d2d0`](https://github.com/Nomi-CEu/Nomi-CEu/commit/136d2d0df247d20b2a0838ea126ce6e8756e64dd))

## General Changes:
### Just Enough Items:
* Remove Useless Recipes in Thermal Compactor ([#1283](https://github.com/Nomi-CEu/Nomi-CEu/pull/1283)) - @D-Alessian ([`bfc8222`](https://github.com/Nomi-CEu/Nomi-CEu/commit/bfc8222ee457bfefac50bb0f390b951c374eb037))
* Remove Null Item Extractor Recipe ([#1272](https://github.com/Nomi-CEu/Nomi-CEu/pull/1272)) - @IntegerLimit ([`d67d83a`](https://github.com/Nomi-CEu/Nomi-CEu/commit/d67d83af4ecf1bb98b0c9dd69fe61c6a558bdc4f))
* Remove Useless NuclearCraft Thermal Centrifuge Recipes ([#1264](https://github.com/Nomi-CEu/Nomi-CEu/pull/1264)) - @D-Alessian ([`5368f27`](https://github.com/Nomi-CEu/Nomi-CEu/commit/5368f274a6c05af4d5821b903cfe623fd21a315f))
  * Fixes [#1263](https://github.com/Nomi-CEu/Nomi-CEu/issues/1263)
* Hide Thermal Excavators from JEI ([#1268](https://github.com/Nomi-CEu/Nomi-CEu/pull/1268)) - @IntegerLimit ([`ce35a87`](https://github.com/Nomi-CEu/Nomi-CEu/commit/ce35a8796ae8d0a8dfecdd7e181deeeaf8f0522a))
* Deprecate the AA Player Interface ([#1253](https://github.com/Nomi-CEu/Nomi-CEu/pull/1253)) - @D-Alessian ([`f98581d`](https://github.com/Nomi-CEu/Nomi-CEu/commit/f98581db9ed6789f0c239e7042182b6e7642e6df))
  * Extra Utilities 2's Player Chest is more feature dense, less bug prone, and has an easier recipe.
* Remove EnderIO's 'Old' Glowstone Nano Particles ([#1225](https://github.com/Nomi-CEu/Nomi-CEu/pull/1225)) - @IntegerLimit ([`0133acb`](https://github.com/Nomi-CEu/Nomi-CEu/commit/0133acb2d29da29f633e501afdf5e7082ea248e3))
* Fixes Soul Binder Recipes Erroring in JEI when Searching by Output ([#1223](https://github.com/Nomi-CEu/Nomi-CEu/pull/1223)) - @IntegerLimit ([`6fbf2e8`](https://github.com/Nomi-CEu/Nomi-CEu/commit/6fbf2e8d11883ef14f96b5f4a81835804660d1ee))
* Improve Deprecation Tooltips and Conversion Recipes ([#1202](https://github.com/Nomi-CEu/Nomi-CEu/pull/1202)) - @IntegerLimit ([`59a2844`](https://github.com/Nomi-CEu/Nomi-CEu/commit/59a2844b83d7ea584da60ff122294e69921a729f))
* Cleanup Recipe Catalysts in JEI ([#1193](https://github.com/Nomi-CEu/Nomi-CEu/pull/1193)) - @IntegerLimit ([`2f7c374`](https://github.com/Nomi-CEu/Nomi-CEu/commit/2f7c374603d0aecc1a2dd02007724492442602ac))
  * Improves Clarity of What can Be Used for Recipes in JEI
* Cleanup Crafting Tables ([#1194](https://github.com/Nomi-CEu/Nomi-CEu/pull/1194)) - @IntegerLimit ([`6484c5e`](https://github.com/Nomi-CEu/Nomi-CEu/commit/6484c5eb768c5d816ec92cb97ef1669de8e54846))
  * Deprecates Extended Crafting's Handheld Crafting Table in favour of Actually Additions' Crafting Table on a Stick
  * Removes Recipe from Unused Double Compressed Crafting Table to Compressed Crafting Table
* Add JEI Input Tooltip for Compressed Coke Clay ([#1154](https://github.com/Nomi-CEu/Nomi-CEu/pull/1154)) - @IntegerLimit ([`fe5e8e6`](https://github.com/Nomi-CEu/Nomi-CEu/commit/fe5e8e61dfb7093559367b1eb82367448edaf58d), [`914becc`](https://github.com/Nomi-CEu/Nomi-CEu/commit/914beccd75509b6a8153298c0fa45531df62e352))
  * States that the Brick Wooden Form is Not Consumed
* Fix DME Machine and JEI Gui Overlap ([#1151](https://github.com/Nomi-CEu/Nomi-CEu/pull/1151)) - @IntegerLimit ([`cb7e811`](https://github.com/Nomi-CEu/Nomi-CEu/commit/cb7e8115cbe4ca749d00f65b0731ed359107cf23), [`654c6e7`](https://github.com/Nomi-CEu/Nomi-CEu/commit/654c6e7945c2e8f64d9a8e120272bf8849ba9b9b))
* Add Creosote & Concrete Buckets to JEI ([#1140](https://github.com/Nomi-CEu/Nomi-CEu/pull/1140)) - @IntegerLimit ([`7a8e761`](https://github.com/Nomi-CEu/Nomi-CEu/commit/7a8e7619ae6f5c779f0cefca0ee41cc9141ef24e))
  * They are used in some Crafting Recipes.
* Misc Thermal Expansion Improvements ([#1127](https://github.com/Nomi-CEu/Nomi-CEu/pull/1127)) - @IntegerLimit ([`9474cca`](https://github.com/Nomi-CEu/Nomi-CEu/commit/9474cca4c5015dde085fa2e43950840d6dc4f35a))
  * Fixes Issues displaying JEI Creative Cell's recipes in JEI
  * Removes Creative Tank and Machines from JEI
  * Cleans up Thermal Upgrade Crafting Recipes
    * Fixes Duplicated and Cluttered Upgrade Recipes
    * Adds Upgrade Crafting Recipes for Dynamos and Portable Tanks

### Mod Updates:
* AE2 Unofficial Extended Life: *v0.56.5 ⇥ v0.56.6* - @IntegerLimit ([`a8d9f66`](https://github.com/Nomi-CEu/Nomi-CEu/commit/a8d9f664a287f0d910751c3500ec2784eb47b7d5))
* Alfheim Lighting Engine: *v1.4 ⇥ v1.5* - @IntegerLimit ([`1d2257f`](https://github.com/Nomi-CEu/Nomi-CEu/commit/1d2257f28f907f254c63192bacaf1aaedc122872))
* CensoredASM: *v5.20 ⇥ v5.28* - @v3ect0rgames, @IntegerLimit ([`86ccc1f`](https://github.com/Nomi-CEu/Nomi-CEu/commit/86ccc1f5e2e5143c8cf777572fce6866d023ef13), [`1cf585a`](https://github.com/Nomi-CEu/Nomi-CEu/commit/1cf585a1d224b69da6a38634c152cd90ede66c45))
* CraftPresence: *v2.5.0 ⇥ v2.5.4* - @v3ect0rgames ([`86ccc1f`](https://github.com/Nomi-CEu/Nomi-CEu/commit/86ccc1f5e2e5143c8cf777572fce6866d023ef13))
* Deep Mob Evolution: *v1.2.2 ⇥ v1.2.3* - @IntegerLimit ([`654c6e7`](https://github.com/Nomi-CEu/Nomi-CEu/commit/654c6e7945c2e8f64d9a8e120272bf8849ba9b9b))
* Extended Crafting: Nomifactory Edition: *v1.7.0.6 ⇥ v1.7.0.7* - @v3ect0rgames ([`86ccc1f`](https://github.com/Nomi-CEu/Nomi-CEu/commit/86ccc1f5e2e5143c8cf777572fce6866d023ef13))
* Had Enough Items: *v4.26.0 ⇥ v4.27.3* - @IntegerLimit, @v3ect0rgames ([`5864797`](https://github.com/Nomi-CEu/Nomi-CEu/commit/5864797db632dd0dcf647d078a730acda106a658), [`86ccc1f`](https://github.com/Nomi-CEu/Nomi-CEu/commit/86ccc1f5e2e5143c8cf777572fce6866d023ef13))
* Inventory Bogo Sorter: *v1.4.8 ⇥ v1.4.9* - @IntegerLimit ([`138b8fe`](https://github.com/Nomi-CEu/Nomi-CEu/commit/138b8fee9772279c639b314971bf1c2e26448bba))
* MixinBooter: *v9.1 ⇥ v10.6* - @IntegerLimit ([`1cf585a`](https://github.com/Nomi-CEu/Nomi-CEu/commit/1cf585a1d224b69da6a38634c152cd90ede66c45))
* Mouse Tweaks Unofficial: *v3.1.4 ⇥ v3.1.5* - @IntegerLimit ([`57cd5b5`](https://github.com/Nomi-CEu/Nomi-CEu/commit/57cd5b5585431b1fdb7d3a6a1ecc8aa4d09ad5e5))
* Nomi Labs: *v0.10.2 ⇥ v0.14.6* - @IntegerLimit, @Mireole ([`37bbdfe`](https://github.com/Nomi-CEu/Nomi-CEu/commit/37bbdfe0a37bc0ad2833c2afae02bc5d7cde1698), [`e6a3912`](https://github.com/Nomi-CEu/Nomi-CEu/commit/e6a39127a7e9446da7168df69bfd6c563fca142c), [`5bb91be`](https://github.com/Nomi-CEu/Nomi-CEu/commit/5bb91be6795918673c5d2752aa4b1ddd08dc364e), ...)
* PackagedAuto: *v1.0.14.54 ⇥ v1.0.18.63* - @v3ect0rgames ([`86ccc1f`](https://github.com/Nomi-CEu/Nomi-CEu/commit/86ccc1f5e2e5143c8cf777572fce6866d023ef13))
* PackagedDraconic: *v1.0.1.16 ⇥ v1.0.2.19* - @v3ect0rgames ([`86ccc1f`](https://github.com/Nomi-CEu/Nomi-CEu/commit/86ccc1f5e2e5143c8cf777572fce6866d023ef13))
* PackagedExCrafting: *v1.0.2.24 ⇥ v1.0.2.27* - @v3ect0rgames ([`86ccc1f`](https://github.com/Nomi-CEu/Nomi-CEu/commit/86ccc1f5e2e5143c8cf777572fce6866d023ef13))
* Red Core: *v0.5.1 ⇥ v0.6* - @IntegerLimit ([`1d2257f`](https://github.com/Nomi-CEu/Nomi-CEu/commit/1d2257f28f907f254c63192bacaf1aaedc122872))
* Storage Drawers: *v5.5.0 ⇥ v5.5.3* - @v3ect0rgames ([`86ccc1f`](https://github.com/Nomi-CEu/Nomi-CEu/commit/86ccc1f5e2e5143c8cf777572fce6866d023ef13))
* UniLib: *v1.0.2 ⇥ v1.0.5* - @v3ect0rgames ([`86ccc1f`](https://github.com/Nomi-CEu/Nomi-CEu/commit/86ccc1f5e2e5143c8cf777572fce6866d023ef13))
* Universal Tweaks: *v1.12.0 ⇥ v1.14.0* - @IntegerLimit ([`6fbf2e8`](https://github.com/Nomi-CEu/Nomi-CEu/commit/6fbf2e8d11883ef14f96b5f4a81835804660d1ee))
* VintageFix: *v0.5.1 ⇥ v0.5.5* - @v3ect0rgames ([`86ccc1f`](https://github.com/Nomi-CEu/Nomi-CEu/commit/86ccc1f5e2e5143c8cf777572fce6866d023ef13))
* VisualOres: *v0.2.5 ⇥ v0.2.6* - @IntegerLimit ([`f9dc5a6`](https://github.com/Nomi-CEu/Nomi-CEu/commit/f9dc5a6fe248115dca39857232866ba33475e603))

### Mod Additions:
* Uber Conduit Probe: *v1.0.3* - @D-Alessian ([`caab28d`](https://github.com/Nomi-CEu/Nomi-CEu/commit/caab28d69e7016785308526141c45c4129654035))

### Other:
* Remove Custom Log4J Config for Servers ([#1237](https://github.com/Nomi-CEu/Nomi-CEu/pull/1237)) - @IntegerLimit ([`072c7b4`](https://github.com/Nomi-CEu/Nomi-CEu/commit/072c7b481e1e04765cff687d14ce3551e7f4bc67))
  * Properly Formats Log Messages in Server Console

## Internal Changes:
* Changelogs: JEI Sub-Category + Better Sorting ([#1288](https://github.com/Nomi-CEu/Nomi-CEu/pull/1288)) - @IntegerLimit ([`60f6258`](https://github.com/Nomi-CEu/Nomi-CEu/commit/60f6258830ec72411cdaa16d505b21224f6bd7c7))
* Add Typo Checking CI Tasks ([#1255](https://github.com/Nomi-CEu/Nomi-CEu/pull/1255)) - @IntegerLimit ([`1520e0f`](https://github.com/Nomi-CEu/Nomi-CEu/commit/1520e0f4efd9f3a4b2758b5de5e274b8c5ea8b5a))
* Fix various typos ([#1250](https://github.com/Nomi-CEu/Nomi-CEu/pull/1250)) - @D-Alessian ([`dd016c7`](https://github.com/Nomi-CEu/Nomi-CEu/commit/dd016c7003680a9c6ded06ac8f46734f7c06a07b))
* Fix Erroring and Double Hides from JEI ([#1200](https://github.com/Nomi-CEu/Nomi-CEu/pull/1200)) - @IntegerLimit ([`392a9af`](https://github.com/Nomi-CEu/Nomi-CEu/commit/392a9affdb84c2f8cee1f4876335688e5c0fdd9a))
* Add Package Specifier to Groovy Scripts ([#1201](https://github.com/Nomi-CEu/Nomi-CEu/pull/1201)) - @IntegerLimit ([`d071d60`](https://github.com/Nomi-CEu/Nomi-CEu/commit/d071d608dc25322ade2854958c2ec1c90bd7f456))
* Rearrange Groovy Folder ([#1195](https://github.com/Nomi-CEu/Nomi-CEu/pull/1195)) - @IntegerLimit ([`5b97920`](https://github.com/Nomi-CEu/Nomi-CEu/commit/5b979202385dcdef6161ed90576562adad303288))
* Fix Crash with Latest CraftTweaker ([#1186](https://github.com/Nomi-CEu/Nomi-CEu/pull/1186)) - @ChromaPIE ([`9820fb6`](https://github.com/Nomi-CEu/Nomi-CEu/commit/9820fb626448281bf6870ce5b26bee9b7c20ccf6))
  * Only matters to players who manually update CraftTweaker
* Fix Tools Compat with Node 22 ([#1161](https://github.com/Nomi-CEu/Nomi-CEu/pull/1161)) - @IntegerLimit ([`ec3076c`](https://github.com/Nomi-CEu/Nomi-CEu/commit/ec3076cfc98fcdf180b96e193e891609f7a3c24a))
* Further Standardize Formatting in Quest Books ([#1134](https://github.com/Nomi-CEu/Nomi-CEu/pull/1134)) - @IntegerLimit ([`a19ca88`](https://github.com/Nomi-CEu/Nomi-CEu/commit/a19ca884f06cc438b5103bdefc187ff4d0d808a9))


**Full Changelog**: [`1.7.3...1.7.4`](https://github.com/Nomi-CEu/Nomi-CEu/compare/1.7.3...1.7.4)
