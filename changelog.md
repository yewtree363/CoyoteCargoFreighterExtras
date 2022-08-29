# Changelog  

| modName    | Coyote Cargo Freighter (CCF)                                      |
| ---------- | ----------------------------------------------------------------- |
| license    | CC-BY-ND-3.0                                                      |
| author     | dboi88 and zer0Kerbal                                             |
| forum      | (https://forum.kerbalspaceprogram.com/index.php?/topic/209541-*/) |
| github     | (https://github.com/zer0Kerbal/zer0Kerbal/CoyoteCargoFreighter)   |
| curseforge | (https://www.curseforge.com/kerbal/ksp-mods/CoyoteCargoFreighter) |
| spacedock  | (https://spacedock.info/mod/1332)                                 |
| ckan       | CargoFreighter                                                    |

## Version 0.3.99.0 - for KSP 1.12.3 [28-Aug-2022]

This is part of a planned series of updates to this addon. Each update will update some of the parts and patches so that instead of one massive update I can update the addon in a more manageable way.

Part of the complexity is the advanced design of this addon. The addon is designed to be as modular as possible, so that it can be used in a variety of ways.

Another part is `CSI Tools (CSIT)` (library addon) that adds vessel CoM balancing which is being handled seperately.

### Summary 0.3.99.0

* Can now search for `ccf` or `csi` in the editor search bar to find all Coyote Cargo Freighter parts
* Only those parts that are updated will appear in this and subsequent releases
* `ghostparts.cfg` has been temporarily added to attempt to prevent save game spoilage

## Adoption by zer0Kerbal

### Documentation

* Create
  * [x] readme
  * deploy to:
    * [x] CurseForge Description page 🤬
    * [x] Forum Original Post 🐰
    * [x] SpaceDock Information page 🌮
  * [x] release notes
  * [x] [changelog.md]
  * [x] update /docs/

### GitHub Pages

* Create
  * docs/
    * [x] [`_config.yml`]
    * [x] [404.md] v1.0.3.2
    * [x] [Assembly.md] v1.0.0.0
    * [x] [Attribution.md] v1.0.7.1
    * [x] [Disclaimer.md] v1.0.7.1
    * [x] [LegalMumboJumbo.md] v1.0.5.1
    * [x] [Localizations.md] v1.1.7.0
    * [x] [ManualInstallation.md] v1.1.8.0
    * [x] [Marketing.md] v1.0.1.0
    * [x] [Notices.md] v1.0.1.0
    * [x] [PartsCatalog.md] v1.1.4.1
    * [x] [Why.md] v1.1.0.0

### Legal Mumbo Jumbo

* Create
  * [x] license check
  * [x] offline documentation
  * _Legal
    * screenshots and pdfs
    * adoptionLetters
    * communications concerning
  * _Links/
    * link(s) saved
  * docs/LegalMumboJumbo
    * [License.md]
    * FORUM-##.png's
      * [x] public documentation
  * [x] GitHub: :octocat:
    * [x] LICENSE
    * [x] [license].txt
  * [x] CurseForge
  * [x] SpaceDock
  * [x] CKAN

### Part Asset Updates 0.3.99.0

* [x] create Assets/ folder
* [x] convert from mesh to MODEL
* [x] rename
  * [x] models to unique names
  * [x] textures to unique names
* [x] update
  * [x] model pointers (.png et al to .dds)
  * [x] model texture pointers to new names
* [x] relocate assets to Assets/
* [x] eliminate
  * [x] duplicate textures
  * [x] duplicate models
* [x] relocate part.cfg to Parts/
* closes # - Asset Updates

### Config 0.3.99.0

* Add localized tags to parts
* Create CoyoteCargoFreighter.cfg
  * [x] [CoyoteCargoFreighter.cfg] v1.0.0.0
    * [x] adds localized tags to parts

### License

* Update
  * [x] Updated License: GPL-2.0 + CC BY-ND 4.0
    * was: AllRightsReserved

### Social Media Presence

* Create Social Media Presence
  * Kerbal Space Program forum
    * [x] Create new thread/post in "Add-on Development"
    * [x] title: [1.12.x] Coyote Cargo Freighter (CCF) - <0.3.99.0-adoption> - `<Thank you dboi88>` edition [01 Jan 2022]
    * [x] create release post in new thread/post
      * [x] content (readme.htm)
    * original mod's thread/post
      * [x] post link to new thread/post
  * [x] CurseForge
  * [x] Twitter
  * [x] SpaceDock
  * [x] Reddit post
  * [x] Patreon post
  * [ ] promo vid (30 sec)
    * [ ] Youtube
    * [ ] Twitch

### Localization

* Localization directory and contents
  * Create
    * [x] Localization/
      * [x] <en-us.cfg>
      * [x] [readme.md] v2.1.2.0
      * [x] [quickstart.md] v1.0.1.1

### Marketing

* Create
  * [x] HeroLogo.png
* [x] copy/convert to HeroLogo.jpg


* #24 - upstream - contributed by zer0Kerbal
* #27 - 0.3.9.9 adoption - contributed by zer0Kerbal

# [ConnectedLivingSpaces.cfg] 1.0.2.0
* header/footer
* closes #35 - CSIfreightersmallrecycler missing. 
* closes #36 - CLS.cfg referencing wrong module.
- thank you - @BararQ

# [OSE.cfg] 1.0.0.0
* renamed to Workshop.cfg

# [Workshop.cfg] 1.0.1.0
* renamed to OSE.cfg
* header/footer
* closes #34 - OSE.cfg missing opening { and closing } (braces)
- thank you - @BararQ

renamed to more descriptive name
# [MKS.cfg] 1.0.0.0
* renamed to USI-ModularKolonizationSystem.cfg


# [USI-ModularKolonizationSystem.cfg] 1.0.1.0
* renamed from MKS.cfg
* header/footer
* added :FOR[CoyoteCargoFreighter]
* closes #31 - MKS.cfg Errors in ratios. replaced `0.0.` with just `0.`
- thank you - @BararQ

# [USIEdits.cfg] 1.0.1.0
* header/footer
* linting
* added :NEEDS[UmbraSpaceIndustries/Kontainers]
* added :FOR[CoyoteCargoFreighter]


# [KISBay.cfg]
* slot size was set to 100, needs to be 50 #32
* closes #33 - KISBay.cfg slot size was set to 100, needs to be 50
- thank you - @BararQ

# [SmallKISKontainer.cfg]
* slot size was set to 100, needs to be 50 #32
* closes #32 - SmallKISKontainer.cfg slot size was set to 100, needs to be 50
- thank you - @BararQ

renamed to more descriptive name
# [KIS.cfg] 1.0.0.0
* renamed to KerbalInventorySystem.cfg

# [KerbalInventorySystem.cfg] 1.0.1.0
* renamed from KIS.cfg
* header/footer
* added :FOR[CoyoteCargoFreighter]
* closes #58 - KIS.cfg slot size set to 100, please set to 50.
- thank you - @BararQ


# [ExtraplanetaryLaunchpads.cfg] 1.0.0.0
* renamed to ExtraplanetaryLaunchpads.cfg

# [ExtraplanetaryLaunchpads.cfg] 1.0.1.0
* renamed from KIS.cfg
* header/footer
* EX --> EL
* added :FOR[CoyoteCargoFreighter]
* updated :NEEDS[Launchpad,!SimpleConstruction]
* closes #59 - EPL.cfg update

# [SimpleConstruction.cfg] 1.0.0.0
* Add SimpleConstruction! support
* [MetalOre] --> [Ore] (should need any other change)
* closes #60 - Add SimpleConstruction!

@PART[OSE_Workshop]:NEEDS[Launchpad]

ExtraplanetaryLaunchpads
SimpleConstruction

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
