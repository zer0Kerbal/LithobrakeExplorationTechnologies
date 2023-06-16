---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---
<!-- ManualInstallation.md v1.0.3.0
Lithobrake Exploration Technology (LET)
created: 01 Feb 2022
updated: 15 Jun 2023

TEMPLATE: ManualInstallation.md v1.1.9.1
created: 01 Feb 2022
updated: 26 Apr 2023

based upon work by Lisias -->
## [Lithobrake Exploration Technology (LET)][mod]

A parts pack for exploring other worlds, and returning home. Pods, large legs, large chutes, service bays, long ladders, etc for Kerbal Space Program.

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the `NecroBones` folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/NecroBones/LithobrakeExplorationTechnologies`
* Extract the package's `NecroBones/` folder into your KSP's as follows:
  * `<PACKAGE>/NecroBones` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/NecroBones/LithobrakeExplorationTechnologies`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/NecroBones/LithobrakeExplorationTechnologies`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/NecroBones/LithobrakeExplorationTechnologies`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  [GameData]
    [NecroBones]
      [LithobrakeExplorationTechnologies]
        [Agencies]
          ...
        [Assets]
          ...
        [Compatibility]
          ...
      + [Config]
        ...
        [Localization]
          ...
        [Parts]
          ...
        #.#.#.#.htm
        CC-BY-NC-SA-4.0+ARR.txt
        changelog.md
        LithobrakeExplorationTechnologies.version
        readme.htm
      * Attributions.htm
      * ManualInstallation.htm
    ...
    * ModuleManager.ConfigCache
  * KSP.log
  ...
```

### Dependencies

* none

THIS FILE: CC BY-ND 4.0 by [zer0Kerbal](https://github.com/zer0Kerbal)
  used with express permission from zer0Kerbal

[mod]: https://www.curseforge.com/kerbal/ksp-mods/LithobrakeExplorationTechnology "Lithobrake Exploration Technology (LET)"