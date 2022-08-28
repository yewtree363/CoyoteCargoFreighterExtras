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

---