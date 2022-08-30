---
permalink: /Changelog.html
title: The Change Log
description: The Opening Credits, and the closing credits, plus the first of two (or is three) end credit scenes
tags: changes,changelog,change-log,page,kerbal,ksp,zer0Kerbal,zedK
---

<!-- 
hdr-changelog.md v1.0.0.0
Coyote Cargo Freighter (CCF)
created: 13 May 2022
updated:
CC BY-ND 4.0 by zer0Kerbal
--># Changelog  

| modName    | Coyote Cargo Freighter (CCF)                                      |
| ---------- | ----------------------------------------------------------------- |
| license    | CC-BY-ND-3.0                                                      |
| author     | dboi88 and zer0Kerbal                                             |
| forum      | (https://forum.kerbalspaceprogram.com/index.php?/topic/209541-*/) |
| github     | (https://github.com/zer0Kerbal/zer0Kerbal/CoyoteCargoFreighter)   |
| curseforge | (https://www.curseforge.com/kerbal/ksp-mods/CoyoteCargoFreighter) |
| spacedock  | (https://spacedock.info/mod/1332)                                 |
| ckan       | CargoFreighter                                                    |

## Version 0.3.99.0-adoption `<Thank you dboi88>` edition

* 28 Aug 2022
* Released for KSP 1.12.3

This is part of a planned series of updates to this addon. Each update will update some of the parts and patches so that instead of one massive update I can update the addon in a more manageable way.

Part of the complexity is the advanced design of this addon. The addon is designed to be as modular as possible, so that it can be used in a variety of ways.

Another factor is `CSI Tools (CSIT)` (library addon) that adds vessel CoM balancing which is being handled seperately.

### Summary 0.3.99.0

* Can now search for `ccf` or `csi` in the editor search bar to find all Coyote Cargo Freighter parts
* Only those parts that are updated will appear in this and subsequent releases
  * Parts refreshed (initially) in this release include: ccf-bridge, ccf-aquarium, ccf-bay-cargo, ccf-docking-500, ccf-engine, ccf-bay-evaprep, ccf-greenhouse, ccf-grinder, ccf-hab-common, ccf-hull,
* `ghostparts.cfg` has been temporarily added to attempt to prevent save game spoilage but will not be *haunting* for long

## Adoption by zer0Kerbal

### Documentation

* Create
  * readme
  * deploy to:
    * CurseForge Description page 🤬
    * Forum Original Post 🐰
    * SpaceDock Information page 🌮
  * release notes
  * [changelog.md]
  * update /docs/
* closes #50 - Update changelog
* closes #49 - Update release.md
* closes #48 - Update readme.md
* closes #26 - # folder restructure

### GitHub Pages

* Create
  * docs/
    * [`_config.yml`]
    * [404.md] v1.0.3.2
    * [Assembly.md] v1.0.0.0
    * [Attribution.md] v1.0.7.1
    * [Disclaimer.md] v1.0.7.1
    * [LegalMumboJumbo.md] v1.0.5.1
    * [Localizations.md] v1.1.7.0
    * [ManualInstallation.md] v1.1.8.0
    * [Marketing.md] v1.0.1.0
    * [Notices.md] v1.0.1.0
    * [PartsCatalog.md] v1.1.4.1
    * [Why.md] v1.1.0.0
* closes #67 - Create GitHub Pages

### Legal Mumbo Jumbo

* Create
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

### Part Asset Updates 0.3.99.0

* create Assets/ folder
* convert from mesh to MODEL
* rename
  * models to unique names
  * textures to unique names
* update
  * model pointers (.png et al to .dds)
  * model texture pointers to new names
* relocate assets to Assets/
* eliminate
  * duplicate textures
  * duplicate models
* relocate part.cfg to Parts/
* Add
  * DRAG_CUBE
  * thumbs
* closes #70 - Part Asset Updates

### Parts 0.3.99.0

* Update
  * Docking Port title and description same as Cargo Bay
  * Localization of part modules (started)
  * Linting / Organization
  * part file names
    * Aquarium.cfg --> ccf-aquarium
    * CargoBay.cfg--> ccf-bay-cargo.cfg
    * commandbridge.cfg --> ccf-bridge.cfg
    * dockingport5m.cfg --> ccf-docking-500.cfg
    * Engine.cfg --> ccf-engine.cfg
    * evaprep.cfg --> ccf-bay-evaprep.cfg
    * FreighterHull.cfg --> ccf-hull.cfg
    * Greenhouse.cfg --> ccf-greenhouse.cfg
    * grinder.cfg --> ccf-grinder.cfg
    * HabCommon.cfg --> ccf-hab-common.cfg
  * part names
    * CSIcommandbridge --> ccf-bridge
    * CSIfreighterAquarium --> ccf-aquarium
    * CSIfreighterCargoBay --> ccf-bay-cargo
    * CSIfreighterdocking5m --> ccf-docking-500
    * CISfreighterengine --> ccf-engine
    * CSIfreighterevaprep --> ccf-bay-evaprep
    * CSIfreightergreenhouse --> ccf-greenhouse
    * CSIfreightergrinder --> ccf-grinder
    * CSIfreighterhabcommon --> ccf-hab-common
    * CSIfreighterhull--> ccf-hull
* closes #40 - Check Dependencies

### Config 0.3.99.0

* Add localized tags to parts
* Create
  * <ghostparts.cfg> - will not be haunting for long
  * CoyoteCargoFreighter.cfg
    * <CoyoteCargoFreighter.cfg> v1.0.0.0
      * adds localized tags to parts
* closes #71 - Create `<CoyoteCargoFreighter.cfg>`

### License

* Update
  * Updated License: GPL-2.0 + CC BY-ND 4.0
    * was: AllRightsReserved
* closes #72 - Update License

### Code 0.3.99.0

* Split code out
  * into CSITools  
* closes #51 - Split mod in twain

### Social Media Presence

* Create Social Media Presence
  * Kerbal Space Program forum
    * Create new thread/post in "Add-on Development"
    * title: [1.12.x] Coyote Cargo Freighter (CCF) - <0.3.99.0-adoption> - `<Thank you dboi88>` edition [01 Jan 2022]
    * create release post in new thread/post
      * content (readme.htm)
    * original mod's thread/post
      * post link to new thread/post
  * CurseForge
  * Twitter
  * SpaceDock
  * Reddit post
  * Patreon post
* closes #39 - Update images

### Localization

* Localization directory and contents
  * Create
    * Localization/
      * <en-us.cfg>
      * [readme.md] v2.1.2.0
      * [quickstart.md] v1.0.1.1
* closes #69 - Create Localization directory and contents
* closes #92 - Part Localization
* closes #75 - English <us-en.cfg>
* updates #74 - Localization - Master

### Marketing

* Create
  * HeroLogo.png
* copy/convert to HeroLogo.jpg
* closes #68 - Create HeroLogo.png

### Compatibility 0.3.99.0

* Linting
* Add
  * <SimpleConstruction.cfg> 1.1.0.0
    * Add SimpleConstruction! support
    * [MetalOre] --> [Ore] (shouldn't need any other change)
    * closes #60 - Add SimpleConstruction! support
    * closes #55 - SimpleConstruction! configs
  * <CSITools.cfg> v1.0.0.0
    * move all CSI part modules into it
    * updates #99 - [CSITools.cfg]
  * <USILifeSupport.cfg> v1.0.0.0
    * move all USILifeSupport part modules into it
    * updates #100 - USILifeSupport
  * <USI-Karbonite.cfg> v1.0.0.0
    * move all USI-Karbonite part modules into it
    * updates #101 - USI-Karbonite
  * <Hanger.cfg> v1.0.0.0
    * move all Hanger part modules into it
    * updates #102 - Hanger
  * <Firespitter.cfg> v1.0.0.0
    * move all Firespitter part modules into it
    * updates #103 - Firespitter
* Update
  * <ConnectedLivingSpaces.cfg> v1.0.2.0
    * Added
      * :FOR[CoyoteCargoFreighter]
      * header
    * renamed from <CLS.cfg>
    * thank you - @BararQ
    * closes #35 - CLS.cfg CSIfreightersmallrecycler missing
    * closes #36 - CLS.cfg referencing wrong module.
  * <ExtraplanetaryLaunchpads.cfg> v1.1.1.0
    * Added
      * ccf-greenhouse patch
      * :FOR[CoyoteCargoFreighter]
      * header
    * split ELWorkshop into groups based upon [ProductivityFactor]
  * <Workshop.cfg> v1.0.1.0
    * renamed from <OSE.cfg>
    * Added
      * :NEEDS[Workshop]
      * :FOR[CoyoteCargoFreighter]
      * header
    * closes #34 - OSE.cfg missing opening { and closing } (braces)
    * thank you - @BararQ
  * <USI-ModularKolonizationSystem.cfg> v1.0.0.0
    * renamed from <MKS.cfg]>
    * closes #31 - MKS.cfg Errors in ratios. replaced `0.0.` with just `0.`
    * thank you - @BararQ
  * <USIEdits.cfg> v1.0.1.0
    * Added
      * :NEEDS[UmbraSpaceIndustries/Kontainers]
      * :FOR[CoyoteCargoFreighter]
      * header
  * <KISBay.cfg>
    * slot size was set to 100, needs to be 50
    * closes #33 - KISBay.cfg slot size was set to 100, needs to be 50
    * thank you - @BararQ
  * <SmallKISKontainer.cfg>
    * slot size was set to 100, needs to be 50
    * closes #32 - SmallKISKontainer.cfg slot size was set to 100, needs to be 50
    * thank you - @BararQ
  * <KerbalInventorySystem.cfg> v1.0.1.0
    * renamed from <KIS.cfg>
    * Added
      * :FOR[CoyoteCargoFreighter]
      * header
    * closes #58 - KIS.cfg slot size set to 100, please set to 50.
    * thank you - @BararQ
  * <ExtraplanetaryLaunchpads.cfg> 1.1.1.0
    * renamed from <EPL.cfg>
    * Added
      * :FOR[CoyoteCargoFreighter]
      * header
    * updated
      * :NEEDS[Launchpad,!SimpleConstruction]
      * EX --> EL
    * closes #59 - EPL.cfg update

### Status 0.3.99.0

* Issues
  * closes #64 - Coyote Cargo Freighter (CCF) 0.3.99.0-adoption `<Thank you dboi88>` edition
  * closes #65 - 0.3.99.0 Create Legal Mumbo Jumbo
  * closes #66 - 0.3.99.0 Create Social Media Presence
  * closes #73 - 0.3.99.0 Create Documentation
* PR's
  * closes #24 - upstream - contributed by zer0Kerbal
  * closes #27 - 0.3.9.9 adoption - contributed by zer0Kerbal
* Duplicate
  * closes #6 - Adoption - Legal MumboJumbo
  * closes #5 - Adoption - Social
  * closes #4 - Adoption - Documentation
  * closes #3 - Adoption - Repo
  * closes #62 - MoarKerbal support  * closes #25 - Adoption

---

## Version 0.3.1

* 2017-12-26
* Released for Kerbal Space Program 1.3.1

* Recompile for 1.3.1
* dependency updates

---

## Version 0.2.4

* 2017-08-09
* Released for Kerbal Space Program 1.3.0

* Fixed Craft Files

---

## Version 0.2.3

* 2017-06-03
* Released for Kerbal Space Program 1.3.0

* Updated To KSP 1.3
* Added Docking Feature To Kontainers & Rear Truss
* Added New Docking Port - Size 3 (To Match Kontainers)
* Added New Custom Plugin - CSI Tools
  * Removed USI Weight Balancing Features
  * Added New Custom Weight Balancing Feature
* Fixed Crew Transfer Bugs (for good this time)
* Added Temp IVA's For All Crewed Parts
* Added New Custom Animated Docking Port PartModule

---

## Version 0.2.2

* 2017-05-04
* Released for Kerbal Space Program 1.3.0

* Fixed
  * slight misalignment on Hanger Bay
  * missing side panels on greenhouse module
  * Crew Transfer Fix
* Added Crew Hatches & Ladders To Recyler, Workshop

---

## Version 0.2.1

* 2017-05-03
* Released for Kerbal Space Program 1.2.2

* Crew Transfer Fix

---

## Version 0.2.0

* 2017-05-01
* Released for Kerbal Space Program 1.2.2

* Fixed node direction on grinder module for EPL (sorry if this messes your ships up)
* Fixed node location on MedBay (sorry if this messes your ships up)
* Fixed node location on Passenger Cabin (sorry if this messes your ships up)
* Fixed various spelling mistakes
* Updated USI-Tools Dependency
* Fixed Size differences on cargo bay number decals
* ReSized textures to integers of 2 for dds compressions and MIP maps
* Converted Textures to DDS format (some minor quality losses but much better performance)
* Add MIP maps for all texture (the ships edges and lines should now look a lot better when zooming out) - New Engine Technology! - more career friendly Karbonite/Karboundrum/EC mix with brand new FX 14,000,000 per refuel (vs previous 250,000,000)[won't break existing ships if you empty out the excess karborundum new capacity 3500 units] - Added custom Engine FX Modules and particles
* Fixed Pick-Up orientation of small modules plus node location (sorry if this messes your ships up)
* Fixed texture on Small KIS Kontainer For EVA Rack
* Fixed textures not showing part preview windows for small EVA rack kontainers
* Fixed normal maps for EVA rack kontainers
* Fixed dynamic meshes on EVA KIS Kontainer
* Fixed HangerBay Pick-Up orientation (sorry if this messes your ships up)
* Added attach nodes to the inside of Cargo Bays & HangerBay - Added support for allista's Hanger Mod configs included for the CargoBay & HangerBay (dock crafts while retaining complete COM balance and low part count)
* Added nodes for docking ports to top bottom and sides of freighter hull - Added custom CSI Freighter catagory for all freighter parts
* Added Coyote Industries agency and associated images
* Increased node strength on rear engine to match joint strength of rest of ship (feel free to try landing it now ;))
* Fixed Z fighting issues on small greenhouse emissive mesh

---

## Version 0.1.7

* 2017-04-22
* Released for Kerbal Space Program 1.2.2

Minor Career Fixes

---

## Version 0.1.6

* 2017-04-22
* Released for Kerbal Space Program 1.2.2

* No changelog provided

---
