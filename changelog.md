2.0.2 (2018-03-14) - RCS fixes
 - Rebalanced the smaller monopropellant tanks to match their stock counterparts.

2.0.1 (2018-03-13) - Minor fixes.
 - Removed shrouds from nuclear tanks and added them to the color-switcher (just one color currently)
 - Removed extraneous IFS/FS/B9 configs from the size-0 tanks.

2.0 (2018-03-12) - Overhaul for 1.4
 - Altered color/mesh switching to use new 1.4 stock switcher (except the radial tanks).
 - Note: Saved colors in existing vessels may need to be manually updated or relaunched to correct.
 - Removed most end-cap shrouds.

1.12.1 (2017-04-09) - MFT fix.
 - Corrected some MM patch issues for ModularFuelTanks.

1.12 (2017-04-07) - Tweaks & Fixes.
 - Corrected a typo that was preventing the B9PartSwitch patches from applying correctly on the radial tanks.
 - Slightly increased the performance of the 2m/3m stack decouplers, and increased their propellant maximums.
 - Changed ModularFuelTanks config to use consolidated wildcard patch.
 - Removed "cryogenic" tank type assignments from the MFT configs.
 - Stack decouplers in sizes 1.25m, 2.5m, and 3.75m collider updates, now actually hollow.

1.11 (2016-10-10) - KSP 1.2 update.
 - Includes a "Kerbal X Plus" sample rocket, provided by StevieC (untested on my side, so far).
 - Updated categories for decouplers.

1.10 (2016-06-04) - Update.
 - Altered switcher priorities for mesh switching, to match fuel switching rules.
 - Added color choices from some adjacent diameters to the 1.25m and 2.5m tanks.

1.9.3 (2016-05-10) - Tweaks.
 - Altered the color-switching rules to be based on variables rather than part names, for more flexibility and support for part duplication.

1.9.2 (2016-05-07) - Fuel Switching Tweaks.
 - Added InterstellarFuelSwitch 2.0.2 flags to re-tie radial tank texture to fuel type.
 - Reduced dry mass of radial tanks when containing MonoPropellant, to better match stock tanks (Firespitter and InterstellarFuelSwitch).

1.9.1 (2016-05-06) - Fuel Switching Tweaks.
 - Added minimum tech requirements for some fuels in the fuel switchers, when using InterstellarFuelSwitch 2.0.1+.
 - InterstellarFuelSwitch GUI names updated for IFS 2.0.1.
 - InterstellarFuelSwitch prioritized ahead of B9PartSwitch to take advantage of tech levels. 

1.9 (2016-05-06) - Update.
 - Nuclear (single-propellant) tanks capacity increased to match total units for LFO tanks. Names updated accordingly.
 - B9PartSwitch fuel-switching enabled for most tanks, Switching config overhauled:
   - Firespitter and InterstellarFuelSwitch support still included, of course.
   - Calculated values will differ somewhat from the FS/IFS values, for cost, capacity, etc. This is normal.
   - Radial tanks with texture-switching still rely on FS/IFS for now. Non-switching if only B9 is installed.
   - B9 mesh switching has been set not to regenerate drag cubes while attaching in the editors.
 - Crossfeed available (globally!) for radially attached parts, enable button added to radial tanks.

1.8.3 (2016-04-29) - Hotfix + Tweaks.
 - Various small clean-ups in the fuel-switching config.
 - Fixed a mistake in 1.8.2 that was preventing InterstellarFuelSwitch integration from working correctly.
 - Started on FuelSwitch compatibility with B9PartSwitch, currently mixed module configuration.

1.8.2 (2016-04-28) - Mesh switching compatibility
 - Added support for B9PartSwitch. Firespitter and InterstellarFuelSwitch still work too, of course.

1.8.1 (2016-04-24) - KSP 1.1 minor update.
 - Fix for fuel-switching to properly disable when something else is adding it (such as CryoEngines), relating to change in ModuleManager's logic.

1.8 (2016-04-02) - KSP 1.1 minor update.
 - Added search tags.
 - Updated included copies of dependencies to 1.1 compatible versions.

1.7 (2016-03-11) Minor fixes, removal of deprecated parts.
 - Corrected capitalization of "ModularFuelTanks" in the fuel-switching rules.
 - Added MonoPropellant as a choice for LFO tanks in the fuel-switching rules.
 - Slightly increased the Oscar-A/C/D dry masses to match mass ratios of larger tanks.
 - Removed the deprecated parts (deprecated as of FTP 1.0) from this pack.
    - Still available via optional compatibility pack "Fuel Tanks Plus Deprecated".
    - These parts were disabled in FTP more than 6 months ago. Deprecation pack only needed for vessels built before then.
    - Available in these locations:
        - http://spacedock.info/mod/387/Fuel%20Tanks%20Plus%20Deprecated
        - http://ksp.necrobones.com/files/FuelTanksPlus/
        - CKAN
 - Moved ModuleManager patches to a "Patches" folder.

1.6 (2016-01-11) - Tweaks.
 - Increased propellant and thrust for 2.5m and 3.75m decouplers.
 - Sharpened the appearance of the checkered 1.25m long tank (Mercury setting).

1.5 (2015-12-17) - Tweaks.
 - Rewrote the fuel-switching config.
    - Should play more nicely with other mods that affect fuel switching.
    - Consolidated patches to reduce complexity.
    - Capacities standardized based on mass, so some values will have changed slightly.
 - Added "FuelTanksPlus_ATM.cfg" with settings to attempt to disable or dissuade ActiveTextureManagement for this mod.
    - Can optionally be deleted to return to ATM defaults.
    - ATM known to occasionally have caching issues with remapped/shared textures in my mods.
    - FuelTanksPlus is already very memory efficient and uses DDS, so ATM doesn't help much for this case.
    - May need to delete ATM's cache if using ATM and some textures still aren't appearing.
 - Replaced some placeholder images with smaller versions that will be more obvious when reassignment fails.
 - Corrected a typo with Agency mentality.

1.4 (2015-12-04) - Update.
 - Added stack decouplers with built-in separation motors, and color-changing capability.

1.3.1 (2015-11-11) - Tweaks.
 - Corrected the fuel-switching capacities for the 0.625m tanks.
 - Added missing placeholder textures in Size1 category.

1.3 (2015-10-21) - Update.
 - Adjusted MM configs so that color switching buttons appear after fuel switching in menus.
 - Added 0.625 semi-spherical cap tank.
 - Added 1.25m semi-spherical bottom tank.
 - Added "half height" monopropellant tanks for 0.625m, 1.25m, 2.5m, and 3.75m.
 - Minor consolidation in TweakScale configs.

1.2.2 (2015-10-08) - Tweaks.
 - Renamed the 0.625m red variant "Titan", after the thrust vectoring tanks on the Centaur/Titan LOWER STAGE rocket boosters.
 - Corrected the attachment node size on the adapter fuel tanks.
 - Moved the 0.625m-1.25m adapter tank to the "Miniaturization" tech node.
 - Moved the 1.25m-2.5m adapter tank down to the "Fuel Systems" tech node.

1.2.1 (2015-09-14) - Tweaks.
 - Renamed the 0.625m red variant "Centaur", after the thrust vectoring tanks on the Centaur rocket boosters.
 - Added missing TweakScale settings for 1.25m nose cones.

1.2 (2015-08-31) - Minor update.
 - Corrected a texture alignment problem with the 0.625m tanks when using reduced texture resolution.
 - Added new red color option to the 0.625m tanks.
 - Added a second, shorter 3.75m to 2.5m adapter tank. 
 - Added mod support settings for adapter tanks.
    - Added TweakScale (adapter) settings.
    - Added Modular Fuel Tanks settings.
    - Added Fuel Switch settings.

1.1.1 (2015-08-27) - Hotfix
 - Corrected the transparent meshes in the FL-T50 fuel tank.

1.1 (2015-08-27) - Fixes, New things.
 - Added a blue "Delta" variant at the 1.25m size, historically inspired by Delta, Delta II, etc.
 - Renamed 2.5m colors, to be more historically minded with regards to Delta IV and Delta IV Heavy.
    - The blue color is renamed from "Delta" to "Blue"
    - The orange color is renamed from "Jumbo" to "Delta"
 - Corrected the base (dry) mass of the triangular probe tank.
 - Added 2.5m to 3.75m adapter tank.
 - Added 1.25m to 2.5m adapter tank.
 - Added 0.625m to 1.25m adapter tank.

1.0.5 (2015-08-23) - Bug fix.
 - Moved README and CHANGELOG to mod's folder.
 - Fixed a problem with one of the RP-400 radial tank's fuel combinations having a dry mass of 125 tons.
 - Lowered the dry mass of radial tanks for non-monopropellant configurations.

1.0.4 (2015-07-31) - Tweaks.
 - Now including a (disabled by default) Module Manager config for re-enabling deprecated parts in the VAB/SPH.
    - This should not be relied upon as a long-term solution. 
 - Corrected a mistake with dry-mass of the FLT-50-FTP tank in the fuel switching config. 

1.0.3 (2015-07-18) - Tweaks.
 - Will now start including ModuleManager and the InterstellerFuelSwitch folders in the zip archive.
 - Addressed an issue with the old deprecated parts showing up in the manufacturer's tab.
 - Added warnings to deprecated parts' descriptions, just in case they show up in a menu somewhere.

1.0.2 (2015-07-17) - Tweaks.
 - Fix for small probe tanks to use InterstellarFuelSwitch properly for appearance changes.

1.0.1 (2015-07-17) - Tweaks.
 - Added more preferential use of InterstellarFuelSwitch over the Firespitter system for all switchers.
 - Interstellar is now preferred over Firespitter, but either will work. 

1.0 (2015-07-17) - Major Overhaul.
 - Updated to version "1.0" to indicate large-scale overhaul (major version revision).
 - Consolidated same-size tanks into single menu objects, with tweakables to choose appearance.
 - Now requires Module Manager and the Firespitter Core as dependencies to function.
 - Old single-color tanks are deprecated, but temporarily included for compatiblity. 
    - Will not be re-usable in VAB from menus, but saved vessels will still load with a warning. 
    - PLEASE DISCONTINUE USE ASAP, from both saved vessels and deployed vessels in the world.
    - Replace with new versions from the menus, to use the new features.
    - These will be removed in a subsequent update, eventually.
 - Added color options to tank sizes that were "missing", now that the options no longer spams the menus.
 - New additional color choices:
    - size 0: White/Black
    - Size 1: Black
    - Size 2: Black, White/Black
    - Size 3: Black, White/Black, Orange
 - Fuel switching turned on by default. 
    - Will still use Interstellar Fuel Switch if available, otherwise defaults to FSfuelSwitch.
    - Radial canister tanks switch fuels with color selection.
    - Small "probe" tanks now have choices between LFO, Xenon, or Monopropellant.
    - "Nuclear" tanks now have LF, Oxidizer, Monopropellant, and Xenon options, but remain single-propellant tanks.
 - Various minor mesh/texture fixes.
 - Restored flag and agency icons to PNG format instead of DDS.

0.11.2 (2015-07-06) - Minor update.
 - Corrected a mistake in Modular Fuel Tanks config for the cube tanks.
 - Added an optional "FuelTanksPlus_RemoveShrouds" ModuleManager config. To disable auto-shrouds, change from "txt" to "cfg".

0.11.1 (2015-06-14) - One more tank!
 - Added white 3.75m 2x tank.
 - Added missing MFT/IFS configs for the 3.75m nuke tank.

0.11 (2015-06-12) - New things.
 - Added support for Modular Fuel Systems (Modular Fuel Tanks).
 - Added support for Deadly Reentry.
 - Added white and orange double-length 2.5m tanks.
 - Added 3.75m nuclear (LF-only) tank (one length for now). 
 - Reconverted textures to DDS format (again).

0.10.1 (2015-05-28) - Appearance tweaks.
 - Altered sheen/specular on nuclear LF tanks, and size 3 "silver" tanks.
 - corrected a mesh mistake on the 2.5m nuclear tanks.

0.10 (2015-05-22) - More tanks.
 - Added a pair of 1.25m nose cone fuel tanks.
 - Added 3 tiers of single-propellant radial tanks (LF, Oxidizer, or MonoProp)

0.9.1 (2015-05-19) - Hot fix.
 - Fixed Interstellar Fuel Switch config for S3-10800 tank.

0.9 (2015-05-19) - Balance tweaks, Nuclear tanks
 - Re-balanced the Oscar-like tanks to correspond to the Oscar-B changes.
 - Adjusted Interstellar Fuel Switch config to not load if CryoEngines is installed (so Cryo can do the right thing).
 - Added LF-only tanks (1.25m and 2.5m) for use with nuclear engines.

0.8.2 (2015-05-08) - Fixes, 1.0.2 tweaks
 - Tweaked attachment node priority order on many tanks for easier attachment in the VAB.
 - Changed the "fuel switching" configs to support Interstellar Fuel Switch.

0.8.1 (2015-05-01) - Fixes, 1.0.1 tweaks
 - Corrected the S3-2400 Titan nose tank to be in Large Volume Containment tech node.
 - Converted textures to DDS format.

0.8 (2015-04-28) - Beta + KSP 1.0 updates
 - Corrected Xenon options for Fuel Switcher.
 - KSP 1.0 fixes, including but not limited to:
    - Costs, max temps, and tech tree assignments of all fuel tanks
    - Mass adjustments on 0.625m and 3.75m tanks
    - Capacity adjustments on tanks close to Oscar-B
    - Fixed bottom attachment nodes
    - Added attachment profile settings
    - Increased scale of "triangular" tanks by 25% to make them align nicely with the small cubes.

0.7.1 (2015-03-25) - Beta
 - Corrected fuel capacity of the FL-T50 fuel tank.

0.7 (2015-03-19) - Beta
 - Moved the 3.75m nose cone tanks to the "Very Heavy Rocketry" tech node (alongside the other 3.75m tanks)
 - Corrected the attachment node size for the 3.75m nose cone tanks.
 - Added "bottom" dome parts for external tanks, in both 2.5m and 3.75m.
 - Added FL-T50 fuel tank.

0.6 (2015-03-02) - Beta, tweaks
 - Adjusted normals (light/shadow angles) on many of the fuel tanks.

0.5 (2015-02-18) - Beta, probes
 - Added several probe/satellite tanks:
    - Three LFO "cube" tanks in varying sizes.
    - Two "triangular" tanks, one with LFO and the other with Xenon.
 - Added support for Fuel Switcher.

0.4 (2015-02-07) - Beta
 - Fixed the cap-shrouds to be hidden from the menu icons for the 1.25m tanks.
 - Changed TweakScale config to use wildcards instead of duplicating settings for every tank.
 - Altered appearance of the grey "Oscar" 0.62m tank to have fewer ribs.
 - Renamed most tanks to have better name sorting alongside the stock tanks. 
 - Mildly increased torque/breaking strength on 1.25m, 2.5m, and 3.75m cylindrical tanks.
 - Added three more 0.625m "Oscar" tanks in several sizes, with a spread of mass/fuel/size ratios to fill the gaps.
 - Added Orange/White 2.5m and 3.75m tanks that are 3/4 the length of the longest stock tanks in those sizes.
 - Added white 2.5m and 3.75m tanks that are half the length of the smallest stock tanks in those sizes.

0.3 (2015-02-02) - Beta, more tanks
 - Added three 0.625m tanks.

0.2.1 (2015-01-28) - Beta fixes
 - Removed excess oxidizer from fueled nose cones.

0.2 (2015-01-28) - More tanks!
 - Added three 1.25m tanks.

0.1 (2015-01-23) - Initial Beta
 - First release.
