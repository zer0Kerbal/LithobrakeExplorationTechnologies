# Changelog

| modName    | Lithobrake Exploration Technologies (LET) by Necrobones                        |
| ---------- | ------------------------------------------------------------------------------ |
| license    | CC-BY-NC-SA-4.0+ARR                                                            |
| author     | NecroBones and zer0Kerbal                                                      |
| forum      | (https://forum.kerbalspaceprogram.com/index.php?/topic/206860-*/)              |
| github     | (https://github.com/zer0Kerbal/zer0Kerbal/LithobrakeExplorationTechnologies)   |
| curseforge | (https://www.curseforge.com/kerbal/ksp-mods/LithobrakeExplorationTechnologies) |
| spacedock  | (https://spacedock.info/mod/93)                                                |
| ckan       | LithobrakeExplorationTechnologies                                              |

* 📌 Pinned
  * can now search for `let`, `letech` and `lithobrake` in editors to see all these parts

## Version 0.5.2.0-release - `<Спасибо Davian Lin>` edition

* Released
  * 16 Jun 2023
  * for Kerbal Space Program 1.12.5
  * by [zer0Kerbal](https://github.com/zer0Kerbal)

### Change Summary 0.5.2.0

* Localize
  * ![Russian (Русский)](https://raw.githubusercontent.com/zer0Kerbal/zer0Kerbal/master/img/RU.png) Russian (Русский)
  * Спасибо [DavianLin](https://github.com/DavianLin)
  * lint, organize, update
  * can now search for `let`, `letech` and `lithobrake` in editors to see all these parts
  * Fix [RealChute.cfg], should have seen the dentist before flight!

### Changes 0.5.2.0

#### Assets 0.5.2.0

* lint and organize
* Update texture pointers from .mbm/tga/pna to .dds

#### Parts 0.5.2.0

* lint and organize
* Add headers
* Update tags

### Compatibility 0.5.2.0

* Fix
  * [RealChute.cfg] 1.0.2.0
  * missing braces, should have seen the dentist before flight!
    * !sound_parachute_open {}
    * !sound_parachute_single {}

#### Config 0.5.2.0

* Add
  * allows for searching editors with `let`
  * [LithobrakeExplorationTechnologies.cfg] v1.0.0.0

#### Localization 0.5.2.0

* Add
  * Russian (Русский)
    * [ru.cfg] v1.0.0.0
    * Спасибо [DavianLin](https://github.com/DavianLin)
  Translation guides
    * [readme-ru.md] v1.0.1.0
    * [quickstart-ru.md] v1.0.0.0
    * Спасибо [evanisrael](https://github/evanisrael)
* Update
  * [readme.md] v2.1.2.1
  * [quickstart.md] v1.0.2.0
  * add header, give credit, organize, and scrape stock dictionary
    * [ru.cfg] v1.0.1.0
    * [en-us.cfg] v1.0.1.0
    * [zh-cn.cfg] v1.0.1.0
* closes #28 - Localization - Russian (Русский) <ru.cfg>
* updates #23 - Localization - Master

#### Documentation 0.5.2.0

* Update
  * [readme.md] v0.5.2.0
  * [Attributions.md] v1.0.8.0
  * [Localizations.md] v1.0.8.0

### Status 0.5.2.0

* Issues
  * closes #111 - Lithobrake Exploration Technologies (LET) 0.5.2.0-release `<Спасибо Davian Lin>` edition
  * closes #112 - 0.5.2.0 Verify Legal Mumbo Jumbo
  * closes #113 - 0.5.2.0 Update Documentation
  * closes #114 - 0.5.2.0 Update Social Media

---

## Version 0.5.1.0-release - `<No More Ghosts and 大胆安全回归>`

* 05 Apr 2022
* For Kerbal Space Program 1.12.3

## Localization 0.5.1.0

* Add Simplified Chinese
  * create <zh-cn.cfg>
  * update docs/
  * update documentation
  * 🧧 xièxiè (谢谢) [beefpatty](https://github.com/beefpatty)
  * closes #26 - Localization - Simplified Chinese (简体中文) <zh-cn.cfg>
  * updated #23 - Localization - Master

## Relocated art assets 0.5.1.0

* delete old art assets that stubbornly didn't move, rather they just copied
  * closes #107 - [Bug 🐞]: Duplicated models/textures

## Update 0.5.1.0

* docs/
* [readme.md]
* [Attribution.md]

### Status 0.5.1.0

* Issues
  * closes #102 - Lithobrake Exploration Technologies (LET) 0.5.1.0-release `<No More Ghosts and 大胆安全回归>`
  * closes #103 - 0.5.1.0 Verify Legal Mumbo Jumbo
  * closes #104 - 0.5.1.0 Update Documentation
  * closes #105 - 0.5.1.0 Update Social Media
  * closes #106 - [Bug 🐞]: Parts not showing up in game

---

## Version 0.5.0.0-adoption - `<Land Boldly and Safely Return>`

* 10 Feb 2022
* For Kerbal Space Program 1.12.3

## Update patches 0.5.0.0

* rename
* add header
* add footer
* add :NEEDS
* add :FOR

## Localization 0.5.0.0

* [en-us.cfg] Additions
  * #LET-door-open = Doors open
  * #LET-door-clos = Doors close
  * #LET-door-togl = Door toggl
  * #LET-light-open = Lights on
  * #LET-light-on = Lights off
  * #LET-light-off = Lights toggle
  * updates #24 - Localization - English (United States) <en-us.cfg>
  * updates #23 - Localization - Master

## Part config updates 0.5.0.0

* closes #65 #66, #67 #68 #69 #70 #71 #72 #73 #74 #75 #76 #77 #78 #79
* General Changes
  * lint pass
  * formatting pass
  * drag cubes
  * thumbs
* [LETpod2m4k]
  * Command Pod
  * reduced [mass] from 5 to 3.6
  * mass = 5 vs 2.6 in mk1-3pod
  * replaced [ModuleAnimateGeneric] with [ModuleLight]
  * [ModuleCommand]
    * add [defaultControlPointDisplayName]
    * add reverse ControlPoint
    * add [hibernation]
    * add [ElectricCharge] = 0.05 consumption
  * [ModuleReactionWheel]
    * reduce [ElectricCharge] consumption from 1.2 to 0.45 (which matches the mk1-3 pod)
  * [ModuleScienceExperiment]
    * localize with stock #
  * [ModuleScienceContainer]
    * localize with stock #
  * Add [ModuleLiftingSurface]
* [LETlander2mX3]
  * Landing Pod
  * reduced [mass] from 2.75 to 1.75
    * mass = 2.75 vs 1.355 in mk2LanderCabin_v2
  * Updated
    * [ModuleAnimateGeneric] for lights
    * [crashTolerance] to 20 from 9 (matches mk2LanderCabin_v2)
    * [maxTemp] to 1200 from 1000 (matches mk2LanderCabin_v2)
  * [ModuleCommand]
    * add [defaultControlPointDisplayName]
    * add ControlPoint
      * Up
      * Forward
      * Reverse
    * add [hibernation]
    * add [ElectricCharge] = 0.05 consumption
  * [ModuleReactionWheel]
    * reduce [ElectricCharge] consumption from 0.75 to 0.45 (which matches the mk1-3 pod)
  * [ModuleScienceExperiment]
    * localize with stock #
  * [ModuleScienceContainer]
    * localize with stock #
  * Add [MonoPropellant] of 40 (to match mk2LanderCabin_v2)
* [LETleg1.cfg]
  * Landing Leg
  * updated [ModuleLight]
  * because of issues, used [ModuleAnimateGeneric] in place of
    * [ModuleLandingLeg]
    * [ModuleWheelBogey]
    * [ModuleWheelLock]
    * [ModuleWheelDeployment]
    * [ModuleWheelSuspension]
    * [ModuleWheelBase]
* [LETleg2.cfg]
  * Landing Leg
  * updated [ModuleLight]
  * because of issues, used [ModuleAnimateGeneric] in place of
    * [ModuleLandingLeg]
    * [ModuleWheelBogey]
    * [ModuleWheelLock]
    * [ModuleWheelDeployment]
    * [ModuleWheelSuspension]
    * [ModuleWheelBase]
* [LETchuteR1.cfg]
  * Radial Parachute
  * update tags
  * Add [preferredStage] = PARACHUTESTAGE
  * [bulkheadProfiles] removed size1 leaving srf
  * [ModuleParachute]
    * Updated [chuteMaxTemp] to 1600 from 650
    * Added [machHeatMultBase] = 0.5
    * Added [chuteThermalMassPerArea] = 0.08
* [LETchute1m.cfg]
  * Stack Parachute
  * update tags
  * Add [preferredStage] = PARACHUTESTAGE
  * [ModuleParachute]
    * Updated [chuteMaxTemp] to 1600 from 650
    * Added [machHeatMultBase] = 0.25
    * Added [chuteThermalMassPerArea] = 0.09
* [LETchute2m.cfg]
  * Stack Parachute
  * update tags
  * Add [preferredStage] = PARACHUTESTAGE
  * [ModuleParachute]
    * Updated [chuteMaxTemp] to 1600 from 650
    * Added [machHeatMultBase] = 0.25
    * Added [chuteThermalMassPerArea] = 0.09
* [LETladderD5m.cfg]
  * Telescoping ladder
  * Add
    * [emissiveConstant] = 0.08
    * Add [thermalMassModifier] = 3.0
* [LETladderD8m.cfg]
  * Telescoping ladder
  * Add
    * [emissiveConstant] = 0.08
    * Add [thermalMassModifier] = 3.0
* [LETladderF1m.cfg]
  * Radial (fixed) ladder
  * Add
    * [emissiveConstant] = 0.08
    * Add [thermalMassModifier] = 3.0
    * Adjust [maxTemp] from 1900 to 2000
* [LETladderF2m.cfg]
  * Radial (fixed) ladder
  * Add
    * [emissiveConstant] = 0.08
    * Add [thermalMassModifier] = 3.0
    * Adjust [maxTemp] from 1900 to 2000
* [LETladderF3m.cfg]
  * Radial (fixed) ladder
  * Add
    * [emissiveConstant] = 0.08
    * Add [thermalMassModifier] = 3.0
    * Adjust [maxTemp] from 1900 to 2000
* [LETbay2mOct1.cfg]
  * Service Bay
    * Add [emissiveConstant] = 0.04
    * Add [thermalMassModifier] = 5.0
    * Adjust [maxTemp] from 2600 to 2900
    * Add
      * [ModuleConductionMultiplier]
      * [modifiedConductionFactor] = 0.001
      * [convectionFluxThreshold]= 500
* [LETbay2mOct2.cfg]
  * Service Bay
    * Add [emissiveConstant] = 0.04
    * Add [thermalMassModifier] = 5.0
    * Adjust [maxTemp] from 2600 to 2900
    * Add
      * [ModuleConductionMultiplier]
      * [modifiedConductionFactor] = 0.001
      * [convectionFluxThreshold]= 500
* [LETbay2mExp.cfg]
  * Service Bay (Rover Garage)
    * Add [emissiveConstant] = 0.04
    * Add [thermalMassModifier] = 5.0
    * Adjust [maxTemp] from 2600 to 2900
    * Add
      * [ModuleConductionMultiplier]
      * [modifiedConductionFactor] = 0.001
      * [convectionFluxThreshold]= 500
* [LETladderF1m.cfg]
  * Radial Ladder
    * [maxTemp] increased to 1900 from 1800
    * Add [emissiveConstant] = 0.8
    * Add [thermalMassModifier] = 3
* [LETladderF2m.cfg]
  * Radial Ladder
    * [maxTemp] increased to 2000 from 1900
    * Add [emissiveConstant] = 0.8
    * Add [thermalMassModifier] = 3
* [LETladderF3m.cfg]
  * Radial Ladder
    * [maxTemp] increased to 2000 from 1900
    * Add [emissiveConstant] = 0.8
    * Add [thermalMassModifier] = 3
* [LETladderD5m.cfg]
  * Retractable Ladder
    * Add [emissiveConstant] = 0.8
    * Add [thermalMassModifier] = 3
* [LETladderD8m.cfg]
  * Retractable Ladder
    * Add [emissiveConstant] = 0.8
    * Add [thermalMassModifier] = 3

## Part Localization 0.5.0.0

* create agency
* create /Localization/ folder
  * create [en-us.cfg]
  * create [quickstart.md]
  * create [readme.md]
* Localized parts:
  * [LETladderF1m.cfg]
  * [LETladderF2m.cfg]
  * [LETladderF3m.cfg]
  * [LETladderD8m.cfg]
  * [LETladderD5m.cfg]
  * [LETchuteR1.cfg]
  * [LETchute2m.cfg]
  * [LETchute1m.cfg]
  * [LETbay2mOct2.cfg]
  * [LETbay2mOct1.cfg]
  * [LETbay2mExp.cfg]
  * [LETpod2m4k.cfg]
  * [LETlander2mX3.cfg]
  * [LETleg2.cfg]
  * [LETleg1.cfg]
* closes #80 - Part Localization
* closes #24 - Localization - English (United States) <en-us.cfg>
* updates #6 - Adoption Documentation
* updates #23 - Localization - Master
* updates #65 #66, #67 #68 #69 #70 #71 #72 #73 #74 #75 #76 #77 #78 #79
* updates #86 - Agent update

## Update texture pointers 0.5.0.0

* .mbm | .tga | .png -->.dds
* updates #65 #66, #67 #68 #69 #70 #71 #72 #73 #74 #75 #76 #77 #78 #79

## Relocated art assets 0.5.0.0

* move textures and models into Assets/
* update MODEL paths in part configs
* updates #65 #66, #67 #68 #69 #70 #71 #72 #73 #74 #75 #76 #77 #78 #79

## Part Thumbnail Images 0.5.0.0

* thumbnail images list
  * [LETladderF2m.cfg]
  * [LETladderF1m.cfg]
  * [LETladderD8m.cfg]
  * [LETladderD5m.cfg]
  * [LETchuteR1.cfg]
  * [LETchute2m.cfg]
  * [LETchute1m.cfg]
  * [LETbay2mOct2.cfg]
  * [LETbay2mOct1.cfg]
  * [LETbay2mExp.cfg]
  * [LETpod2m4k.cfg]
  * [LETlander2mX3.cfg]
  * [LETleg2.cfg]
  * [LETleg1.cfg]
  * [LETladderF3m.cfg]
* create [docs/PartThumbnails.md]
* closes #81 - Part Thumbnail Images

## Parts Missing Manufacturer 0.5.0.0

* [LETleg2.cfg]
* [LETchute1m.cfg]
* [LETbay2mOct2.cfg]
* [LETbay2mOct1.cfg]
* [LETbay2mExp.cfg]
  * closes #82 - Parts Missing Manufacturer

## Status 0.5.0.0

* closes #8 - Release 0.5.0.0-adoption
* closes #7 - Adoption - social media
* closes #6 - Adoption Documentation
* closes #5 - Adoption Legal MumboJumbo
* closes #4 - Adoption - GitHub
* closes #64 - Update Lithobrake Exploration Technologies (LET)

---

## Version 0.4.0.0 (2016-10-12) - KSP 1.2 Update.

* Updated categories for many parts.
* Added KSP 1.2 sound effects and additional variables for landing legs.
* Added transmitter modules to command pods.
* closes #9
* closes #21
  Authored-By: @NecroBones

---

## Version 0.3.6.0 (2016-07-12) - Tweaks

* Added an optional experimental config for RealChute integration (for the radial chute only).
  * To enable, rename "GameData/LETech/Patches/LETech_RealChute.txt" to have "cfg" instead of "txt".
* Removed references to "drogue" in the parachute tags.
* Added parachute deployment sound effects, as per KSP 1.1.3.
* updates #9
* closes #20
  Authored-By: @NecroBones

---

## Version 0.3.5.0 (2016-04-22) - Transparency fix.

* Fixed the "always transparent" problem for bays in the VAB.
* Adjusted the "expanded" 2.5m bay to use transparency only on the doors.
* updates #9
* closes #19
  Authored-By: @NecroBones

---

## Version 0.3.4.0 (2016-04-17) - Tweaks.

* Tweaked leg settings.
* Moved leg wheel colliders to allow for more accurate aerodynamic occlusion.
* Legs reduced in mass quite a bit.
* updates #9
* closes #18

---

## Version 0.3.3.0 (2016-04-01) - KSP 1.1 Hotfix

* Landing leg suspension systems working again. Known issue: Feet float slightly.
* Added search tags to parts.
* updates #9
* closes #17

---

## Version 0.3.2.0 (2016-03-29) - KSP 1.1 Hotfix

* Landing legs updated to not be 100% deadly. Suspension still doesn't work, legs are rigid for now.
* Moved MM configs to "Patches" folder.
* updates #9
* closes #16

---

## Version 0.3.1 (2016-01-11) - Tweaks.

* X3 lander can mass increased.
* Mass, fuel capacity, and cost increased for the "large" variant of the lander cargo bay.
* updates #9
* closes #22

---

## Version 0.3 (2015-11-11) - KSP 1.0.5 update.

* Switched the 4-man capsule's "generic" IVA over to use the Mk3 shuttle's IVA instead, so that all 4 Kerbals are EVA/IVA selectable.
* Moved "CHANGELOG" to the mod's directory.
* Updated bays to use current cargo bay thermal stats and allow door deployment limit.
* Parachutes now use new contract constraints.
* Command pods use new maxTemp and skinMaxTemp values.
* 4-man capsule uses new buoyancy settings.
* updates #9
* closes #15

---

## Version 0.2.1 (2015-08-05) - Alpha fixes.

* Fixed a texture problem that resulted in the 1m and 2m fixed ladders not loading textures.
* Fixed a scaling error with the "large" octagonal bay's doors, causing it to leave gaps when closed.
* Radial parachute's storage case reduced in size by 15%.
* Increased deployed-drag multiplier on all parachutes.
* Added Connected Living Space support.
* Added TweakScale support.
* updates #9
* closes #14

---

## Version 0.2.0.0 (2015-08-03) - Wide Alpha

* Added 3 large parachutes: 1.25m & 2.5m stackable nose cones, and a large radial chute.
* Added 4-man, 2.5m capsule-style command pod.
* Added landing lights to the landing legs.
* Fixed a collider issue with the Expanded 2.5m service bay that prevented use of the floor's attachment node.
* updates #9
* closes #13

---

## Version 0.1.0.0 (2015-07-08) - Initial Alpha

* First release.
* updates #9
* closes #12

---