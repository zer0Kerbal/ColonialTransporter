---
permalink: /ManualInstallation.html
title: Manual Installation
description: the flat-pack Kiea instructions, written in Kerbalese, unusally present
tags: installation,directions,page,kerbal,ksp,zer0Kerbal,zedK
---

<!-- ManualInstallation.md v1.1.8.1
ColonialTransporter (ABBV)
created: 01 Oct 2019
updated: 29 Jul 2022 -->

<!-- based upon work by Lisias -->

# ColonialTransporter (ABBV)

[Home](./index.md)

***BLURB***

## Installation Instructions

### Using CurseForge/OverWolf app or CKAN

You should be all good! (check for latest version on CurseForge)

### If Downloaded from CurseForge/OverWolf manual download

To install, place the `LazTek` folder inside your Kerbal Space Program's GameData folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/LazTek/ColonialTransporter`
* Extract the package's `LazTek/` folder into your KSP's GameData folder as follows:
  * `<PACKAGE>/LazTek` --> `<KSP_ROOT>/GameData`
    * Overwrite any preexisting folder/file(s).
  * you should end up with `<KSP_ROOT>/GameData/LazTek/ColonialTransporter`

### If Downloaded from SpaceDock / GitHub / other

To install, place the `GameData` folder inside your Kerbal Space Program folder:

* **REMOVE ANY OLD VERSIONS OF THE PRODUCT BEFORE INSTALLING**
  * Delete `<KSP_ROOT>/GameData/LazTek/ColonialTransporter`
* Extract the package's `GameData` folder into your KSP's root folder as follows:
  * `<PACKAGE>/GameData` --> `<KSP_ROOT>`
    * Overwrite any preexisting file.
  * you should end up with `<KSP_ROOT>/GameData/LazTek/ColonialTransporter`

## The following file layout must be present after installation

```markdown
<KSP_ROOT>
  + [GameData]
    + [LazTekDev]
      + [Agencies]
        ...
      + [Flags]
        ...
      + [Config]
        ...
      + [Localization]
        ...
      ...
    + [ColonialTransporter]
      + [Compatibility]
        ...
      + [Config]
        ...
      + [Contracts]
        ...
      + [Localization]
        ...
      + [Parts]
        ...
      * #.#.#.#.htm
      * Attributions.htm
      * changelog.md
      * CC-BY-ND-4.0.txt
      * ManualInstallation.htm
      * readme.htm
      * ColonialTransporter.version
    ...
    * ModuleManager.ConfigCache
  * KSP.log
  ...
```

### Dependencies

* [LazTek Dev (LTD)][LTD]

[LTD]: https://github.com/zer0Kerbal/LazTekDev "LazTek Dev (LTD)"
