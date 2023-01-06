---
permalink: /Changelog.html
title: The Change Log
description: The Opening Credits, and the closing credits, plus the first of two (or is three) end credit scenes
tags: changes,changelog,change-log,page,kerbal,ksp,zer0Kerbal,zedK
---
<!-- 
hdr-changelog.md v1.0.0.0
Fuel Cells (FUEL)
created: 13 May 2022
updated:
CC BY-ND 4.0 by zer0Kerbal
--># Changelog  
  
| modName    | Fuel Cells (FUEL)                                                 |
| ---------- | ----------------------------------------------------------------- |
| license    | CC-NC-ND-4.0                                                      |
| author     | Ph34rb0t and zer0Kerbal                                           |
| forum      | (https://forum.kerbalspaceprogram.com/index.php?/topic/211277-*/) |
| github     | (https://github.com/zer0Kerbal/FuelCells)                         |
| curseforge | (https://www.curseforge.com/kerbal/ksp-mods/FuelCells)            |
| spacedock  | (https://spacedock.info/mod/3185)                                 |
| ckan       | FuelCells                                                         |

## Version 0.9.99.0-prerelease `<Thank you Ph34rb0t>` edition

* Released
  * 02 Jan 2022
  * for Kerbal Space Program 1.12.4
  * by [zer0Kerbal](http://github.com/zer0Kerbal)

### Adoption by [zer0Kerbal](https://github.com/zer0Kerbal)

### Summary 0.9.99.0

* Adds one new part in five sizes
  * 0.625m, 1.25m, 1.875m, 2.5m and 3.75m
  * each with all the modcons
* Val had some fun with the last can of Fire Engine Red spray paint and a stencil.
* lots of updates and linting
* fully localized (English)
* nodes adjusted and corrected
* could certainly use decorative lights and a new coat of paint
* converted .png --> .dds and added NRM and colormap
* updated all compatibility patches
* allows searching 'fuel' ir 'hbi' in editors

### Archival Releases

* 0.2.0.0-release `<Archival>`
* 0.1.0.0-release `<Archival>`
* closes #7 - Archival Releases
* closes #12 - 0.1.0.0-release
* closes #13 - 0.2.0.0-release

### Part 0.9.99.0

* Asset Updates
  * create Assets/ folder
  * convert from:
    * mesh to MODEL {}
    * .png --> .dds
      * <model000.png> 702kb --> <fuelcell.dds> 1.33mb
  * Add
    * <fuelcell_NRM.dds> 341kb
    * <fuelcell_colormap.dds> 341kb
  * rename
    * models to unique names
      * <model.mu> -- <fuelcell.mu>
    * textures to unique names
  * update
    * model pointers (.png et al to .dds)
    * model texture pointers to new names
  * relocate assets to Assets/
  * eliminate duplicates
  * relocate part.cfg to Parts/
* closes #9 - Part Asset Updates

### Compatibility

* Add
  * <OnDemandFuelCells.cfg> v1.3.0.0
* Update
  * <TweakScake.cfg> v1.1.0.0
* closes #10 - Create <FuelCells.cfg>

### Localization 0.9.99.0

* Add
  * <us-en.cfg> v1.0.0.0
  * Localization/
    * <readme.md> v2.1.2.0
    * <quickstart.md>  v1.0.1.1
* closes #8 - Create Localization directory and contents
* closes #14 - Localization - Master
* updates #15 - English <en-us.cfg>

### Create Legal Mumbo Jumbo 0.9.99.0

* Create Legal Mumbo Jumbo
  * license check
  * offline documentation
  * _Legal
    * screenshots and pdfs
    * adoptionLetters
    * communications concerning
  * _Links/
    * link(s) saved
  * docs/LegalMumboJumbo
    * [License.md]
    * FORUM-##.png's
      * public documentation
  * GitHub: :octocat:
    * LICENSE
    * [license].txt
  * CurseForge
  * SpaceDock
  * CKAN
* closes #11 - Update License

### Documentation 0.9.99.0

* Create Documentation
  * readme
  * deploy to:
    * CurseForge Description page 🤬
    * Forum Original Post 🐰
    * SpaceDock Information page 🌮
  * release notes
  * [changelog.md]
  * update /docs/
* Create GitHub Pages
  * docs/
    * [`_config.yml`]
    * [Attribution.md] v1.0.7.1
    * [ManualInstallation.md] v1.1.8.0
    * [404.md] v1.0.3.2
    * [LegalMumboJumbo.md] v1.0.5.1
    * [Localizations.md] v1.1.7.0
    * [Marketing.md] v1.0.1.0
    * [Notices.md] v1.0.1.0
    * [Disclaimer.md] v1.0.1.0
    * [PartsCatalog.md] v1.1.4.1
    * [Why.md] v1.1.0.0
* closes #5 - Create GitHub Pages

### Create 0.9.99.0

* HeroLogo.png
  * HeroLogo.png
  * copy/convert to HeroLogo.jpg
* closes #6 - Create HeroLogo.png

### Status 0.9.99.0

* Issues
  * closes #1 - Fuel Cells (FUEL) 0.9.99.0-adoption `<Thank you Ph34rb0t>` edition
  * closes #2 - 1.1.99.0 Create Legal Mumbo Jumbo
  * closes #3 - 1.1.99.0 Create Documentation
  * closes #4 - 1.1.99.0 Create Social Media Presence

---

## Version 0.2.0.0-release `<Archival>` edition

* Released
  * 09 Oct 2014
  * for Kerbal Space Program 0.25
  * by Ph34rb0t

* Last release by Ph34rb0t
* No Changelog provided
* Changes by zer0Kerbal
  * split out into three separate part.cfg
  * change category to Electrical
  * adjust nodes (flipped bottom axis), size
  * split out unique resources into <Kerturn.cfg>
    * replace with LFO  

### Status 0.2.0.0

* Issues
  * closes #7 - Archival Releases
  * closes #13 - 0.2.0.0-release

---

## Version 0.1.0.0-release `<Archival>` edition

* Released
  * 22 Jul 2014
  * for Kerbal Space Program 0.23.5
  * by Ph34rb0t

### Creation by Ph34rb0t

* No Changelog provided
* Changes by zer0Kerbal
  * split out into three separate part.cfg
  * change category to Electrical
  * adjust nodes (flipped bottom axis), size
  * split out unique resources into <Kerturn.cfg>
    * replace with LFO

### Status 0.1.0.0

* Issues
  * updates #7 - Archival Releases
  * closes #12 - 0.1.0.0-release

---