## Comparison with [1.16-pre2](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.16-pre2)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Translations](#translations)
> - [File structure](#file-structure)
> - [Misc](#misc)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">1.16-pre2</th><th>1.16-pre3</th></tr><tr><td>World version</td><td><pre>2557</pre></td><td><pre>2559</pre></td></tr><tr><td>Protocol version</td><td><pre>722</pre></td><td><pre>725</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">1.16-pre2</th><th>1.16-pre3</th></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr></table>
</details>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
+ attribute.txt
- attributes.txt
```

</details>
<details>
<summary>
structure_processor
</summary>

```diff
+ minecraft:lava_submerged_block
```

</details>
</details>
<hr/>
<details><summary><b><ins>TAGS</ins></b><a name="tags"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
+ universal_tags/attribute.json
- universal_tags/attributes.json
```

</details>
<details>
<summary>
all_survival_blocks_without_drop.json
</summary>

```diff
+ minecraft:nether_portal
```

</details>
<details>
<summary>
universal_tags/structure_processor.json
</summary>

```diff
+ minecraft:lava_submerged_block
```

</details>
</details>
<hr/>
<details><summary><b><ins>TRANSLATIONS</ins></b><a name="translations"></a></summary>
<br/>
<details>
<summary>
Keys
</summary>

```diff
+ createWorld.preparing: Preparing for world creation...
- key.swapHands: Swap Item In Hands
+ key.swapOffhand: Swap Item With Offhand
+ selectWorld.data_read: Reading world data...
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>1.16-pre2</th><th>1.16-pre3</th></tr>
<tr><th align="left"><div style="width:290px">selectWorld.backupJoinConfirmButton</div></th><td>Create backup and load</td><td>Create Backup and Load</td></tr>
<tr><th align="left"><div style="width:290px">datapackFailure.safeMode</div></th><td>Safe mode</td><td>Safe Mode</td></tr>
<tr><th align="left"><div style="width:290px">editGamerule.title</div></th><td>Edit game rules</td><td>Edit Game Rules</td></tr>
<tr><th align="left"><div style="width:290px">selectWorld.import_worldgen_settings</div></th><td>Import settings</td><td>Import Settings</td></tr>
<tr><th align="left"><div style="width:290px">generator.single_biome_floating_islands</div></th><td>Floating islands</td><td>Floating Islands</td></tr>
<tr><th align="left"><div style="width:290px">chat.copy.click</div></th><td>Click to copy to Clipboard</td><td>Click to Copy to Clipboard</td></tr>
<tr><th align="left"><div style="width:290px">options.graphics.fabulous.tooltip</div></th><td>"Fabulous" graphics enables screen shaders to draw translucent objects per-pixel.

This may severely impact performance for portable devices and 4k displays.</td><td>"Fabulous" graphics uses screen shaders for drawing weather, clouds and particles behind translucent blocks and water.

This may severely impact performance for portable devices and 4K displays.</td></tr>
<tr><th align="left"><div style="width:290px">options.graphics.fancy.tooltip</div></th><td>"Fancy" graphics balances performance and quality for the majority of machines.</td><td>"Fancy" graphics balances performance and quality for the majority of machines.

Weather, clouds and particles may not appear behind translucent blocks or water.</td></tr>
<tr><th align="left"><div style="width:290px">dataPack.validation.back</div></th><td>Go back</td><td>Go Back</td></tr>
<tr><th align="left"><div style="width:290px">dataPack.validation.reset</div></th><td>Reset to default</td><td>Reset to Default</td></tr>
<tr><th align="left"><div style="width:290px">sign.edit</div></th><td>Edit sign message</td><td>Edit Sign Message</td></tr>
<tr><th align="left"><div style="width:290px">debug.creative_spectator.help</div></th><td>F3 + N = Cycle creative <-> spectator</td><td>F3 + N = Cycle previous gamemode <-> spectator</td></tr>
</table>
<br/>
</details>
</details>
<hr/>
<details><summary><b><ins>FILE STRUCTURE</ins></b><a name="file-structure"></a></summary>
<br/>
<details>
<summary>
data
</summary>

```diff
+ minecraft/loot_tables/blocks/nether_portal.json
- minecraft/structures/bastion/hoglin_stable/stairs/stairs_0_mirrored.nbt
- minecraft/structures/bastion/hoglin_stable/stairs/stairs_2.nbt
- minecraft/structures/bastion/hoglin_stable/stairs/stairs_3.nbt
+ minecraft/tags/blocks/infiniburn_end.json
+ minecraft/tags/blocks/infiniburn_nether.json
+ minecraft/tags/blocks/infiniburn_overworld.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
- minecraft/textures/models/armor/chainmail_piglin_helmet.png
- minecraft/textures/models/armor/diamond_piglin_helmet.png
- minecraft/textures/models/armor/gold_piglin_helmet.png
- minecraft/textures/models/armor/iron_piglin_helmet.png
- minecraft/textures/models/armor/leather_piglin_helmet_overlay.png
- minecraft/textures/models/armor/leather_piglin_helmet.png
- minecraft/textures/models/armor/netherite_piglin_helmet.png
```

</details>
</details>
<hr/>
<details><summary><b><ins>MISC</ins></b><a name="misc"></a></summary>
<br/>
<details>
<summary>
splashes
</summary>

```diff
+ Moderately attractive!
- Sexy!
```

</details>
</details>
<hr/>
<details><summary><b><ins>MAPPINGS</ins></b><a name="mappings"></a></summary>
<br/>
<h2>Server<a name="server-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
- net.minecraft.package-info
- XXX.ai.behavior.AcquirePoi$JitteredLinearRetry
+ XXX.ai.behavior.AnimalMakeLove
- XXX.ai.behavior.AssignProfessionFromJobSite
+ XXX.ai.behavior.BabyFollowAdult
- XXX.ai.behavior.BackUpIfTooClose
+ XXX.ai.behavior.BecomePassiveIfMemoryPresent
- XXX.ai.behavior.Behavior
+ XXX.ai.behavior.Behavior$Status
- XXX.ai.behavior.BehaviorUtils
+ XXX.ai.behavior.BlockPosTracker
- XXX.ai.behavior.CelebrateVillagersSurvivedRaid
+ XXX.ai.behavior.CopyMemoryWithExpiry
- XXX.ai.behavior.CrossbowAttack
+ XXX.ai.behavior.CrossbowAttack$CrossbowState
- XXX.ai.behavior.DismountOrSkipMounting
+ XXX.ai.behavior.DoNothing
- XXX.ai.behavior.EntityTracker
+ XXX.ai.behavior.EraseMemoryIf
- XXX.ai.behavior.GateBehavior
+ XXX.ai.behavior.GateBehavior$1
- XXX.ai.behavior.GateBehavior$OrderPolicy
+ XXX.ai.behavior.GateBehavior$RunningPolicy
- XXX.ai.behavior.GateBehavior$RunningPolicy$1
+ XXX.ai.behavior.GateBehavior$RunningPolicy$2
- XXX.ai.behavior.GiveGiftToHero
+ XXX.ai.behavior.GoOutsideToCelebrate
- XXX.ai.behavior.GoToCelebrateLocation
+ XXX.ai.behavior.GoToClosestVillage
- XXX.ai.behavior.GoToPotentialJobSite
+ XXX.ai.behavior.GoToWantedItem
- XXX.ai.behavior.HarvestFarmland
+ XXX.ai.behavior.InsideBrownianWalk
- XXX.ai.behavior.InteractWith
+ XXX.ai.behavior.InteractWithDoor
- XXX.ai.behavior.JumpOnBed
+ XXX.ai.behavior.LocateHidingPlace
- XXX.ai.behavior.LocateHidingPlaceDuringRaid
+ XXX.ai.behavior.LookAndFollowTradingPlayerSink
- XXX.ai.behavior.LookAtTargetSink
+ XXX.ai.behavior.MeleeAttack
- XXX.ai.behavior.Mount
+ XXX.ai.behavior.MoveToSkySeeingSpot
- XXX.ai.behavior.MoveToTargetSink
- XXX.ai.behavior.package-info
+ XXX.ai.behavior.PlayTagWithOtherKids
- XXX.ai.behavior.PoiCompetitorScan
+ XXX.ai.behavior.PositionTracker
- XXX.ai.behavior.RandomStroll
+ XXX.ai.behavior.ReactToBell
- XXX.ai.behavior.ResetProfession
+ XXX.ai.behavior.ResetRaidStatus
- XXX.ai.behavior.RingBell
+ XXX.ai.behavior.RunIf
- XXX.ai.behavior.RunOne
+ XXX.ai.behavior.RunSometimes
- XXX.ai.behavior.SetClosestHomeAsWalkTarget
+ XXX.ai.behavior.SetEntityLookTarget
- XXX.ai.behavior.SetHiddenState
+ XXX.ai.behavior.SetLookAndInteract
- XXX.ai.behavior.SetRaidStatus
+ XXX.ai.behavior.SetWalkTargetAwayFrom
- XXX.ai.behavior.SetWalkTargetFromAttackTargetIfTargetOutOfReach
+ XXX.ai.behavior.SetWalkTargetFromBlockMemory
- XXX.ai.behavior.SetWalkTargetFromLookTarget
+ XXX.ai.behavior.ShowTradesToPlayer
- XXX.ai.behavior.SleepInBed
+ XXX.ai.behavior.SocializeAtBell
- XXX.ai.behavior.StartAttacking
+ XXX.ai.behavior.StartCelebratingIfTargetDead
- XXX.ai.behavior.StopAttackingIfTargetInvalid
+ XXX.ai.behavior.StopBeingAngryIfTargetDead
- XXX.ai.behavior.StrollAroundPoi
+ XXX.ai.behavior.StrollToPoi
- XXX.ai.behavior.StrollToPoiList
+ XXX.ai.behavior.Swim
- XXX.ai.behavior.TradeWithVillager
+ XXX.ai.behavior.UpdateActivityFromSchedule
- XXX.ai.behavior.UseBonemeal
+ XXX.ai.behavior.ValidateNearbyPoi
- XXX.ai.behavior.VictoryStroll
+ XXX.ai.behavior.VillageBoundRandomStroll
- XXX.ai.behavior.VillagerCalmDown
+ XXX.ai.behavior.VillagerGoalPackages
- XXX.ai.behavior.VillagerMakeLove
+ XXX.ai.behavior.VillagerPanicTrigger
- XXX.ai.behavior.WakeUp
+ XXX.ai.behavior.WeightedList
- XXX.ai.behavior.WeightedList$1
+ XXX.ai.behavior.WeightedList$WeightedEntry
- XXX.ai.behavior.WeightedList$WeightedEntry$1
+ XXX.ai.behavior.WorkAtComposter
- XXX.ai.behavior.WorkAtPoi
+ XXX.ai.behavior.YieldJobSite
+ XXX.ai.control.BodyRotationControl
- XXX.ai.control.Control
+ XXX.ai.control.DolphinLookControl
- XXX.ai.control.FlyingMoveControl
+ XXX.ai.control.JumpControl
- XXX.ai.control.LookControl
+ XXX.ai.control.MoveControl
- XXX.ai.control.MoveControl$Operation
+ XXX.ai.control.package-info
- XXX.ai.goal.AvoidEntityGoal
+ XXX.ai.goal.BegGoal
- XXX.ai.goal.BoatGoals
+ XXX.ai.goal.BreakDoorGoal
- XXX.ai.goal.BreathAirGoal
+ XXX.ai.goal.BreedGoal
- XXX.ai.goal.CatLieOnBedGoal
+ XXX.ai.goal.CatSitOnBlockGoal
- XXX.ai.goal.DolphinJumpGoal
+ XXX.ai.goal.DoorInteractGoal
- XXX.ai.goal.EatBlockGoal
+ XXX.ai.goal.FleeSunGoal
- XXX.ai.goal.FloatGoal
+ XXX.ai.goal.FollowBoatGoal
- XXX.ai.goal.FollowFlockLeaderGoal
+ XXX.ai.goal.FollowMobGoal
- XXX.ai.goal.FollowOwnerGoal
+ XXX.ai.goal.FollowParentGoal
- XXX.ai.goal.Goal
+ XXX.ai.goal.Goal$Flag
- XXX.ai.goal.GoalSelector
+ XXX.ai.goal.GoalSelector$1
- XXX.ai.goal.GoalSelector$2
+ XXX.ai.goal.GolemRandomStrollInVillageGoal
- XXX.ai.goal.InteractGoal
+ XXX.ai.goal.JumpGoal
- XXX.ai.goal.LandOnOwnersShoulderGoal
+ XXX.ai.goal.LeapAtTargetGoal
- XXX.ai.goal.LlamaFollowCaravanGoal
+ XXX.ai.goal.LookAtPlayerGoal
- XXX.ai.goal.LookAtTradingPlayerGoal
+ XXX.ai.goal.MeleeAttackGoal
- XXX.ai.goal.MoveBackToVillageGoal
+ XXX.ai.goal.MoveIndoorsGoal
- XXX.ai.goal.MoveThroughVillageGoal
+ XXX.ai.goal.MoveToBlockGoal
- XXX.ai.goal.MoveTowardsRestrictionGoal
+ XXX.ai.goal.MoveTowardsTargetGoal
- XXX.ai.goal.OcelotAttackGoal
+ XXX.ai.goal.OfferFlowerGoal
- XXX.ai.goal.OpenDoorGoal
- XXX.ai.goal.package-info
+ XXX.ai.goal.PanicGoal
- XXX.ai.goal.PathfindToRaidGoal
+ XXX.ai.goal.PlayGoal
- XXX.ai.goal.RandomLookAroundGoal
+ XXX.ai.goal.RandomStrollGoal
- XXX.ai.goal.RandomSwimmingGoal
+ XXX.ai.goal.RangedAttackGoal
- XXX.ai.goal.RangedBowAttackGoal
+ XXX.ai.goal.RangedCrossbowAttackGoal
- XXX.ai.goal.RangedCrossbowAttackGoal$CrossbowState
+ XXX.ai.goal.RemoveBlockGoal
- XXX.ai.goal.RestrictSunGoal
+ XXX.ai.goal.RunAroundLikeCrazyGoal
- XXX.ai.goal.SitWhenOrderedToGoal
+ XXX.ai.goal.StrollThroughVillageGoal
- XXX.ai.goal.SwellGoal
+ XXX.ai.goal.TakeFlowerGoal
- XXX.ai.goal.TemptGoal
+ XXX.ai.goal.TradeWithPlayerGoal
- XXX.ai.goal.TryFindWaterGoal
+ XXX.ai.goal.UseItemGoal
- XXX.ai.goal.WaterAvoidingRandomFlyingGoal
+ XXX.ai.goal.WaterAvoidingRandomStrollGoal
- XXX.ai.goal.WrappedGoal
+ XXX.ai.goal.ZombieAttackGoal
+ XXX.commands.data.BlockDataAccessor
- XXX.commands.data.BlockDataAccessor$1
+ XXX.commands.data.DataAccessor
- XXX.commands.data.DataCommands
+ XXX.commands.data.DataCommands$DataManipulator
- XXX.commands.data.DataCommands$DataManipulatorDecorator
+ XXX.commands.data.DataCommands$DataProvider
- XXX.commands.data.EntityDataAccessor
+ XXX.commands.data.EntityDataAccessor$1
- XXX.commands.data.package-info
- XXX.commands.data.StorageDataAccessor
+ XXX.commands.data.StorageDataAccessor$1
+ XXX.datafix.fixes.AbstractUUIDFix
- XXX.datafix.fixes.AddNewChoices
+ XXX.datafix.fixes.AdvancementsFix
- XXX.datafix.fixes.AdvancementsRenameFix
+ XXX.datafix.fixes.AttributesRename
- XXX.datafix.fixes.BedBlockEntityInjecter
+ XXX.datafix.fixes.BedItemColorFix
- XXX.datafix.fixes.BeehivePoiRenameFix
+ XXX.datafix.fixes.BiomeFix
- XXX.datafix.fixes.BitStorageAlignFix
+ XXX.datafix.fixes.BlockEntityBannerColorFix
- XXX.datafix.fixes.BlockEntityBlockStateFix
+ XXX.datafix.fixes.BlockEntityCustomNameToComponentFix
- XXX.datafix.fixes.BlockEntityIdFix
+ XXX.datafix.fixes.BlockEntityJukeboxFix
- XXX.datafix.fixes.BlockEntityKeepPacked
+ XXX.datafix.fixes.BlockEntityShulkerBoxColorFix
- XXX.datafix.fixes.BlockEntitySignTextStrictJsonFix
+ XXX.datafix.fixes.BlockEntitySignTextStrictJsonFix$1
- XXX.datafix.fixes.BlockEntityUUIDFix
+ XXX.datafix.fixes.BlockNameFlatteningFix
- XXX.datafix.fixes.BlockRenameFix
+ XXX.datafix.fixes.BlockRenameFix$1
- XXX.datafix.fixes.BlockRenameFixWithJigsaw
+ XXX.datafix.fixes.BlockRenameFixWithJigsaw$1
- XXX.datafix.fixes.BlockStateData
+ XXX.datafix.fixes.BlockStateStructureTemplateFix
- XXX.datafix.fixes.CatTypeFix
+ XXX.datafix.fixes.ChunkBiomeFix
- XXX.datafix.fixes.ChunkLightRemoveFix
+ XXX.datafix.fixes.ChunkPalettedStorageFix
- XXX.datafix.fixes.ChunkPalettedStorageFix$1
+ XXX.datafix.fixes.ChunkPalettedStorageFix$DataLayer
- XXX.datafix.fixes.ChunkPalettedStorageFix$Direction
+ XXX.datafix.fixes.ChunkPalettedStorageFix$Direction$Axis
- XXX.datafix.fixes.ChunkPalettedStorageFix$Direction$AxisDirection
+ XXX.datafix.fixes.ChunkPalettedStorageFix$Section
- XXX.datafix.fixes.ChunkPalettedStorageFix$UpgradeChunk
+ XXX.datafix.fixes.ChunkStatusFix
- XXX.datafix.fixes.ChunkStatusFix2
+ XXX.datafix.fixes.ChunkStructuresTemplateRenameFix
- XXX.datafix.fixes.ChunkToProtochunkFix
+ XXX.datafix.fixes.ColorlessShulkerEntityFix
- XXX.datafix.fixes.DyeItemRenameFix
+ XXX.datafix.fixes.EntityArmorStandSilentFix
- XXX.datafix.fixes.EntityBlockStateFix
+ XXX.datafix.fixes.EntityCatSplitFix
- XXX.datafix.fixes.EntityCodSalmonFix
+ XXX.datafix.fixes.EntityCustomNameToComponentFix
- XXX.datafix.fixes.EntityElderGuardianSplitFix
+ XXX.datafix.fixes.EntityEquipmentToArmorAndHandFix
- XXX.datafix.fixes.EntityHealthFix
+ XXX.datafix.fixes.EntityHorseSaddleFix
- XXX.datafix.fixes.EntityHorseSplitFix
+ XXX.datafix.fixes.EntityIdFix
- XXX.datafix.fixes.EntityItemFrameDirectionFix
+ XXX.datafix.fixes.EntityMinecartIdentifiersFix
- XXX.datafix.fixes.EntityPaintingItemFrameDirectionFix
+ XXX.datafix.fixes.EntityPaintingMotiveFix
- XXX.datafix.fixes.EntityProjectileOwnerFix
+ XXX.datafix.fixes.EntityPufferfishRenameFix
- XXX.datafix.fixes.EntityRavagerRenameFix
+ XXX.datafix.fixes.EntityRedundantChanceTagsFix
- XXX.datafix.fixes.EntityRenameFix
+ XXX.datafix.fixes.EntityRidingToPassengersFix
- XXX.datafix.fixes.EntityShulkerColorFix
+ XXX.datafix.fixes.EntityShulkerRotationFix
- XXX.datafix.fixes.EntitySkeletonSplitFix
+ XXX.datafix.fixes.EntityStringUuidFix
- XXX.datafix.fixes.EntityTheRenameningFix
+ XXX.datafix.fixes.EntityTippedArrowFix
- XXX.datafix.fixes.EntityUUIDFix
+ XXX.datafix.fixes.EntityWolfColorFix
- XXX.datafix.fixes.EntityZombieSplitFix
+ XXX.datafix.fixes.EntityZombieVillagerTypeFix
- XXX.datafix.fixes.EntityZombifiedPiglinRenameFix
+ XXX.datafix.fixes.ForcePoiRebuild
- XXX.datafix.fixes.FurnaceRecipeFix
+ XXX.datafix.fixes.GossipUUIDFix
- XXX.datafix.fixes.HeightmapRenamingFix
+ XXX.datafix.fixes.IglooMetadataRemovalFix
- XXX.datafix.fixes.ItemBannerColorFix
+ XXX.datafix.fixes.ItemCustomNameToComponentFix
- XXX.datafix.fixes.ItemIdFix
+ XXX.datafix.fixes.ItemLoreFix
- XXX.datafix.fixes.ItemPotionFix
+ XXX.datafix.fixes.ItemRenameFix
- XXX.datafix.fixes.ItemRenameFix$1
+ XXX.datafix.fixes.ItemShulkerBoxColorFix
- XXX.datafix.fixes.ItemSpawnEggFix
+ XXX.datafix.fixes.ItemStackEnchantmentNamesFix
- XXX.datafix.fixes.ItemStackMapIdFix
+ XXX.datafix.fixes.ItemStackSpawnEggFix
- XXX.datafix.fixes.ItemStackTheFlatteningFix
+ XXX.datafix.fixes.ItemStackUUIDFix
- XXX.datafix.fixes.ItemWaterPotionFix
+ XXX.datafix.fixes.ItemWrittenBookPagesStrictJsonFix
- XXX.datafix.fixes.JigsawPropertiesFix
+ XXX.datafix.fixes.JigsawRotationFix
- XXX.datafix.fixes.LeavesFix
+ XXX.datafix.fixes.LeavesFix$LeavesSection
- XXX.datafix.fixes.LeavesFix$Section
+ XXX.datafix.fixes.LevelDataGeneratorOptionsFix
- XXX.datafix.fixes.LevelFlatGeneratorInfoFix
+ XXX.datafix.fixes.LevelUUIDFix
- XXX.datafix.fixes.MapIdFix
+ XXX.datafix.fixes.MemoryExpiryDataFix
- XXX.datafix.fixes.MissingDimensionFix
+ XXX.goal.target.DefendVillageTargetGoal
- XXX.goal.target.HurtByTargetGoal
+ XXX.goal.target.NearestAttackableTargetGoal
- XXX.goal.target.NearestAttackableWitchTargetGoal
+ XXX.goal.target.NearestHealableRaiderTargetGoal
- XXX.goal.target.NonTameRandomTargetGoal
+ XXX.goal.target.OwnerHurtByTargetGoal
- XXX.goal.target.OwnerHurtTargetGoal
+ XXX.layer.traits.AreaTransformer0
- XXX.layer.traits.AreaTransformer1
+ XXX.layer.traits.AreaTransformer2
- XXX.layer.traits.BishopTransformer
+ XXX.layer.traits.C0Transformer
- XXX.layer.traits.C1Transformer
+ XXX.layer.traits.CastleTransformer
- XXX.layer.traits.DimensionOffset0Transformer
+ XXX.layer.traits.DimensionOffset1Transformer
- XXX.layer.traits.DimensionTransformer
- XXX.layer.traits.package-info
+ XXX.layer.traits.PixelTransformer
+ XXX.level.lighting.BlockLightEngine
- XXX.level.lighting.BlockLightSectionStorage
+ XXX.level.lighting.BlockLightSectionStorage$BlockDataLayerStorageMap
- XXX.level.lighting.DataLayerStorageMap
+ XXX.level.lighting.DynamicGraphMinFixedPoint
- XXX.level.lighting.DynamicGraphMinFixedPoint$1
+ XXX.level.lighting.DynamicGraphMinFixedPoint$2
- XXX.level.lighting.FlatDataLayer
+ XXX.level.lighting.LayerLightEngine
- XXX.level.lighting.LayerLightEventListener
+ XXX.level.lighting.LayerLightEventListener$DummyLightLayerEventListener
- XXX.level.lighting.LayerLightSectionStorage
+ XXX.level.lighting.LayerLightSectionStorage$1
- XXX.level.lighting.LevelLightEngine
+ XXX.level.lighting.LightEventListener
- XXX.level.lighting.package-info
- XXX.level.lighting.SkyLightEngine
+ XXX.level.lighting.SkyLightSectionStorage
- XXX.level.lighting.SkyLightSectionStorage$1
+ XXX.level.lighting.SkyLightSectionStorage$SkyDataLayerStorageMap
- XXX.level.lighting.SpatialLongSet
+ XXX.level.lighting.SpatialLongSet$InternalMap
+ XXX.level.material.EmptyFluid
- XXX.level.material.FlowingFluid
+ XXX.level.material.FlowingFluid$1
- XXX.level.material.Fluid
- XXX.level.material.Fluids
+ XXX.level.material.FluidState
+ XXX.level.material.LavaFluid
- XXX.level.material.LavaFluid$Flowing
+ XXX.level.material.LavaFluid$Source
- XXX.level.material.Material
+ XXX.level.material.Material$Builder
- XXX.level.material.MaterialColor
+ XXX.level.material.package-info
+ XXX.level.material.PushReaction
- XXX.level.material.WaterFluid
+ XXX.level.material.WaterFluid$Flowing
- XXX.level.material.WaterFluid$Source
- XXX.level.pathfinder.BinaryHeap
+ XXX.level.pathfinder.BlockPathTypes
- XXX.level.pathfinder.FlyNodeEvaluator
+ XXX.level.pathfinder.Node
- XXX.level.pathfinder.NodeEvaluator
- XXX.level.pathfinder.package-info
+ XXX.level.pathfinder.Path
- XXX.level.pathfinder.PathComputationType
+ XXX.level.pathfinder.PathFinder
- XXX.level.pathfinder.SwimNodeEvaluator
+ XXX.level.pathfinder.Target
- XXX.level.pathfinder.TurtleNodeEvaluator
+ XXX.level.pathfinder.WalkNodeEvaluator
+ XXX.level.progress.ChunkProgressListener
- XXX.level.progress.ChunkProgressListenerFactory
+ XXX.level.progress.LoggerChunkProgressListener
- XXX.level.progress.package-info
- XXX.level.progress.ProcessorChunkProgressListener
+ XXX.level.progress.StoringChunkProgressListener
- XXX.level.redstone.package-info
+ XXX.level.redstone.Redstone
- XXX.level.saveddata.package-info
+ XXX.level.saveddata.SaveDataDirtyRunnable
- XXX.level.saveddata.SavedData
+ XXX.level.storage.CommandStorage
- XXX.level.storage.CommandStorage$Container
+ XXX.level.storage.DerivedLevelData
- XXX.level.storage.DimensionDataStorage
+ XXX.level.storage.LevelData
- XXX.level.storage.LevelResource
+ XXX.level.storage.LevelStorageException
- XXX.level.storage.LevelStorageSource
+ XXX.level.storage.LevelStorageSource$LevelStorageAccess
- XXX.level.storage.LevelStorageSource$LevelStorageAccess$1
+ XXX.level.storage.LevelStorageSource$LevelStorageAccess$2
- XXX.level.storage.LevelSummary
+ XXX.level.storage.LevelVersion
- XXX.level.storage.McRegionUpgrader
- XXX.level.storage.package-info
+ XXX.level.storage.PlayerDataStorage
- XXX.level.storage.PrimaryLevelData
+ XXX.level.storage.ServerLevelData
- XXX.level.storage.WorldData
+ XXX.level.storage.WritableLevelData
- XXX.level.timers.FunctionCallback
+ XXX.level.timers.FunctionCallback$Serializer
- XXX.level.timers.FunctionTagCallback
+ XXX.level.timers.FunctionTagCallback$Serializer
- XXX.level.timers.package-info
- XXX.level.timers.TimerCallback
+ XXX.level.timers.TimerCallback$Serializer
- XXX.level.timers.TimerCallbacks
+ XXX.level.timers.TimerQueue
- XXX.level.timers.TimerQueue$1
+ XXX.level.timers.TimerQueue$Event
+ XXX.levelgen.surfacebuilders.BadlandsSurfaceBuilder
- XXX.levelgen.surfacebuilders.BasaltDeltasSurfaceBuilder
+ XXX.levelgen.surfacebuilders.ConfiguredSurfaceBuilder
- XXX.levelgen.surfacebuilders.DefaultSurfaceBuilder
+ XXX.levelgen.surfacebuilders.ErodedBadlandsSurfaceBuilder
- XXX.levelgen.surfacebuilders.FrozenOceanSurfaceBuilder
+ XXX.levelgen.surfacebuilders.GiantTreeTaigaSurfaceBuilder
- XXX.levelgen.surfacebuilders.GravellyMountainSurfaceBuilder
+ XXX.levelgen.surfacebuilders.MountainSurfaceBuilder
- XXX.levelgen.surfacebuilders.NetherCappedSurfaceBuilder
+ XXX.levelgen.surfacebuilders.NetherForestSurfaceBuilder
- XXX.levelgen.surfacebuilders.NetherSurfaceBuilder
+ XXX.levelgen.surfacebuilders.NopeSurfaceBuilder
+ XXX.levelgen.surfacebuilders.package-info
- XXX.levelgen.surfacebuilders.ShatteredSavanaSurfaceBuilder
+ XXX.levelgen.surfacebuilders.SoulSandValleySurfaceBuilder
- XXX.levelgen.surfacebuilders.SurfaceBuilder
+ XXX.levelgen.surfacebuilders.SurfaceBuilderBaseConfiguration
- XXX.levelgen.surfacebuilders.SurfaceBuilderConfiguration
+ XXX.levelgen.surfacebuilders.SwampSurfaceBuilder
- XXX.levelgen.surfacebuilders.WoodedBadlandsSurfaceBuilder
- XXX.levelgen.synth.ImprovedNoise
+ XXX.levelgen.synth.NormalNoise
- XXX.levelgen.synth.package-info
- XXX.levelgen.synth.PerlinNoise
+ XXX.levelgen.synth.PerlinSimplexNoise
- XXX.levelgen.synth.SimplexNoise
+ XXX.levelgen.synth.SurfaceNoise
- XXX.loot.entries.AlternativesEntry
+ XXX.loot.entries.AlternativesEntry$Builder
- XXX.loot.entries.ComposableEntryContainer
+ XXX.loot.entries.CompositeEntryBase
- XXX.loot.entries.CompositeEntryBase$1
+ XXX.loot.entries.CompositeEntryBase$CompositeEntryConstructor
- XXX.loot.entries.DynamicLoot
+ XXX.loot.entries.DynamicLoot$1
- XXX.loot.entries.DynamicLoot$Serializer
+ XXX.loot.entries.EmptyLootItem
- XXX.loot.entries.EmptyLootItem$1
+ XXX.loot.entries.EmptyLootItem$Serializer
- XXX.loot.entries.EntryGroup
+ XXX.loot.entries.EntryGroup$Builder
- XXX.loot.entries.LootItem
+ XXX.loot.entries.LootItem$1
- XXX.loot.entries.LootItem$Serializer
+ XXX.loot.entries.LootPoolEntries
- XXX.loot.entries.LootPoolEntry
+ XXX.loot.entries.LootPoolEntryContainer
- XXX.loot.entries.LootPoolEntryContainer$Builder
+ XXX.loot.entries.LootPoolEntryContainer$Serializer
- XXX.loot.entries.LootPoolEntryType
+ XXX.loot.entries.LootPoolSingletonContainer
- XXX.loot.entries.LootPoolSingletonContainer$1
+ XXX.loot.entries.LootPoolSingletonContainer$Builder
- XXX.loot.entries.LootPoolSingletonContainer$DummyBuilder
+ XXX.loot.entries.LootPoolSingletonContainer$EntryBase
- XXX.loot.entries.LootPoolSingletonContainer$EntryConstructor
+ XXX.loot.entries.LootPoolSingletonContainer$Serializer
- XXX.loot.entries.LootTableReference
+ XXX.loot.entries.LootTableReference$1
- XXX.loot.entries.LootTableReference$Serializer
- XXX.loot.entries.package-info
+ XXX.loot.entries.SequentialEntry
- XXX.loot.entries.SequentialEntry$Builder
+ XXX.loot.entries.TagEntry
- XXX.loot.entries.TagEntry$1
+ XXX.loot.entries.TagEntry$Serializer
+ XXX.loot.functions.ApplyBonusCount
- XXX.loot.functions.ApplyBonusCount$1
+ XXX.loot.functions.ApplyBonusCount$BinomialWithBonusCount
- XXX.loot.functions.ApplyBonusCount$Formula
+ XXX.loot.functions.ApplyBonusCount$FormulaDeserializer
- XXX.loot.functions.ApplyBonusCount$OreDrops
+ XXX.loot.functions.ApplyBonusCount$Serializer
- XXX.loot.functions.ApplyBonusCount$UniformBonusCount
+ XXX.loot.functions.ApplyExplosionDecay
- XXX.loot.functions.ApplyExplosionDecay$1
+ XXX.loot.functions.ApplyExplosionDecay$Serializer
- XXX.loot.functions.CopyBlockState
+ XXX.loot.functions.CopyBlockState$1
- XXX.loot.functions.CopyBlockState$Builder
+ XXX.loot.functions.CopyBlockState$Serializer
- XXX.loot.functions.CopyNameFunction
+ XXX.loot.functions.CopyNameFunction$1
- XXX.loot.functions.CopyNameFunction$NameSource
+ XXX.loot.functions.CopyNameFunction$Serializer
- XXX.loot.functions.CopyNbtFunction
+ XXX.loot.functions.CopyNbtFunction$1
- XXX.loot.functions.CopyNbtFunction$Builder
+ XXX.loot.functions.CopyNbtFunction$CopyOperation
- XXX.loot.functions.CopyNbtFunction$DataSource
+ XXX.loot.functions.CopyNbtFunction$MergeStrategy
- XXX.loot.functions.CopyNbtFunction$MergeStrategy$1
+ XXX.loot.functions.CopyNbtFunction$MergeStrategy$2
- XXX.loot.functions.CopyNbtFunction$MergeStrategy$3
+ XXX.loot.functions.CopyNbtFunction$Serializer
- XXX.loot.functions.EnchantRandomlyFunction
+ XXX.loot.functions.EnchantRandomlyFunction$1
- XXX.loot.functions.EnchantRandomlyFunction$Builder
+ XXX.loot.functions.EnchantRandomlyFunction$Serializer
- XXX.loot.functions.EnchantWithLevelsFunction
+ XXX.loot.functions.EnchantWithLevelsFunction$1
- XXX.loot.functions.EnchantWithLevelsFunction$Builder
+ XXX.loot.functions.EnchantWithLevelsFunction$Serializer
- XXX.loot.functions.ExplorationMapFunction
+ XXX.loot.functions.ExplorationMapFunction$1
- XXX.loot.functions.ExplorationMapFunction$Builder
+ XXX.loot.functions.ExplorationMapFunction$Serializer
- XXX.loot.functions.FillPlayerHead
+ XXX.loot.functions.FillPlayerHead$Serializer
- XXX.loot.functions.FunctionUserBuilder
+ XXX.loot.functions.LimitCount
- XXX.loot.functions.LimitCount$1
+ XXX.loot.functions.LimitCount$Serializer
- XXX.loot.functions.LootingEnchantFunction
+ XXX.loot.functions.LootingEnchantFunction$1
- XXX.loot.functions.LootingEnchantFunction$Builder
+ XXX.loot.functions.LootingEnchantFunction$Serializer
- XXX.loot.functions.LootItemConditionalFunction
+ XXX.loot.functions.LootItemConditionalFunction$Builder
- XXX.loot.functions.LootItemConditionalFunction$DummyBuilder
+ XXX.loot.functions.LootItemConditionalFunction$Serializer
- XXX.loot.functions.LootItemFunction
+ XXX.loot.functions.LootItemFunction$Builder
+ XXX.loot.functions.LootItemFunctions
- XXX.loot.functions.LootItemFunctionType
+ XXX.loot.functions.package-info
- XXX.loot.functions.SetAttributesFunction
+ XXX.loot.functions.SetAttributesFunction$1
- XXX.loot.functions.SetAttributesFunction$Builder
+ XXX.loot.functions.SetAttributesFunction$Modifier
- XXX.loot.functions.SetAttributesFunction$ModifierBuilder
+ XXX.loot.functions.SetAttributesFunction$Serializer
- XXX.loot.functions.SetContainerContents
+ XXX.loot.functions.SetContainerContents$1
- XXX.loot.functions.SetContainerContents$Builder
+ XXX.loot.functions.SetContainerContents$Serializer
- XXX.loot.functions.SetContainerLootTable
+ XXX.loot.functions.SetContainerLootTable$1
- XXX.loot.functions.SetContainerLootTable$Serializer
+ XXX.loot.functions.SetItemCountFunction
- XXX.loot.functions.SetItemCountFunction$1
+ XXX.loot.functions.SetItemCountFunction$Serializer
- XXX.loot.functions.SetItemDamageFunction
+ XXX.loot.functions.SetItemDamageFunction$1
- XXX.loot.functions.SetItemDamageFunction$Serializer
+ XXX.loot.functions.SetLoreFunction
- XXX.loot.functions.SetLoreFunction$Builder
+ XXX.loot.functions.SetLoreFunction$Serializer
- XXX.loot.functions.SetNameFunction
+ XXX.loot.functions.SetNameFunction$1
- XXX.loot.functions.SetNameFunction$Serializer
+ XXX.loot.functions.SetNbtFunction
- XXX.loot.functions.SetNbtFunction$1
+ XXX.loot.functions.SetNbtFunction$Serializer
- XXX.loot.functions.SetStewEffectFunction
+ XXX.loot.functions.SetStewEffectFunction$1
- XXX.loot.functions.SetStewEffectFunction$Builder
+ XXX.loot.functions.SetStewEffectFunction$Serializer
- XXX.loot.functions.SmeltItemFunction
+ XXX.loot.functions.SmeltItemFunction$1
- XXX.loot.functions.SmeltItemFunction$Serializer
+ XXX.loot.parameters.LootContextParam
- XXX.loot.parameters.LootContextParams
- XXX.loot.parameters.LootContextParamSet
+ XXX.loot.parameters.LootContextParamSet$1
- XXX.loot.parameters.LootContextParamSet$Builder
+ XXX.loot.parameters.LootContextParamSets
+ XXX.loot.parameters.package-info
- XXX.loot.predicates.AlternativeLootItemCondition
+ XXX.loot.predicates.AlternativeLootItemCondition$1
- XXX.loot.predicates.AlternativeLootItemCondition$Builder
+ XXX.loot.predicates.AlternativeLootItemCondition$Serializer
- XXX.loot.predicates.BonusLevelTableCondition
+ XXX.loot.predicates.BonusLevelTableCondition$1
- XXX.loot.predicates.BonusLevelTableCondition$Serializer
+ XXX.loot.predicates.ConditionReference
- XXX.loot.predicates.ConditionReference$1
+ XXX.loot.predicates.ConditionReference$Serializer
- XXX.loot.predicates.ConditionUserBuilder
+ XXX.loot.predicates.DamageSourceCondition
- XXX.loot.predicates.DamageSourceCondition$1
+ XXX.loot.predicates.DamageSourceCondition$Serializer
- XXX.loot.predicates.EntityHasScoreCondition
+ XXX.loot.predicates.EntityHasScoreCondition$1
- XXX.loot.predicates.EntityHasScoreCondition$Builder
+ XXX.loot.predicates.EntityHasScoreCondition$Serializer
- XXX.loot.predicates.ExplosionCondition
+ XXX.loot.predicates.ExplosionCondition$Serializer
- XXX.loot.predicates.InvertedLootItemCondition
+ XXX.loot.predicates.InvertedLootItemCondition$1
- XXX.loot.predicates.InvertedLootItemCondition$Serializer
+ XXX.loot.predicates.LocationCheck
- XXX.loot.predicates.LocationCheck$1
+ XXX.loot.predicates.LocationCheck$Serializer
- XXX.loot.predicates.LootItemBlockStatePropertyCondition
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition$1
- XXX.loot.predicates.LootItemBlockStatePropertyCondition$Builder
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition$Serializer
- XXX.loot.predicates.LootItemCondition
+ XXX.loot.predicates.LootItemCondition$Builder
+ XXX.loot.predicates.LootItemConditions
- XXX.loot.predicates.LootItemConditionType
- XXX.loot.predicates.LootItemEntityPropertyCondition
+ XXX.loot.predicates.LootItemEntityPropertyCondition$1
- XXX.loot.predicates.LootItemEntityPropertyCondition$Serializer
+ XXX.loot.predicates.LootItemKilledByPlayerCondition
- XXX.loot.predicates.LootItemKilledByPlayerCondition$Serializer
+ XXX.loot.predicates.LootItemRandomChanceCondition
- XXX.loot.predicates.LootItemRandomChanceCondition$1
+ XXX.loot.predicates.LootItemRandomChanceCondition$Serializer
- XXX.loot.predicates.LootItemRandomChanceWithLootingCondition
+ XXX.loot.predicates.LootItemRandomChanceWithLootingCondition$1
- XXX.loot.predicates.LootItemRandomChanceWithLootingCondition$Serializer
+ XXX.loot.predicates.MatchTool
- XXX.loot.predicates.MatchTool$Serializer
+ XXX.loot.predicates.package-info
+ XXX.loot.predicates.TimeCheck
- XXX.loot.predicates.TimeCheck$1
+ XXX.loot.predicates.TimeCheck$Builder
- XXX.loot.predicates.TimeCheck$Serializer
+ XXX.loot.predicates.WeatherCheck
- XXX.loot.predicates.WeatherCheck$1
+ XXX.loot.predicates.WeatherCheck$Builder
- XXX.loot.predicates.WeatherCheck$Serializer
+ XXX.metadata.pack.package-info
+ XXX.metadata.pack.PackMetadataSection
- XXX.metadata.pack.PackMetadataSectionSerializer
+ XXX.minecraft.obfuscate.DontObfuscateOrShrink
- XXX.minecraft.obfuscate.KeepAfterObfuscation
+ XXX.minecraft.obfuscate.package-info
- XXX.minecraft.recipebook.package-info
+ XXX.minecraft.recipebook.PlaceRecipe
- XXX.minecraft.recipebook.ServerPlaceRecipe
+ XXX.minecraft.recipebook.ServerPlaceSmeltingRecipe
+ XXX.minecraft.resources.DelegatingOps
+ XXX.minecraft.resources.package-info
- XXX.minecraft.resources.RegistryDataPackCodec
+ XXX.minecraft.resources.RegistryFileCodec
- XXX.minecraft.resources.RegistryReadOps
+ XXX.minecraft.resources.RegistryReadOps$1
- XXX.minecraft.resources.RegistryReadOps$ReadCache
+ XXX.minecraft.resources.RegistryWriteOps
- XXX.minecraft.resources.ResourceKey
+ XXX.minecraft.resources.ResourceLocation
- XXX.minecraft.resources.ResourceLocation$Serializer
- XXX.minecraft.server.Bootstrap
+ XXX.minecraft.server.Bootstrap$1
- XXX.minecraft.server.ChainedJsonException
+ XXX.minecraft.server.ChainedJsonException$1
- XXX.minecraft.server.ChainedJsonException$Entry
+ XXX.minecraft.server.ConsoleInput
- XXX.minecraft.server.ConsoleInputSource
+ XXX.minecraft.server.DebugLoggedPrintStream
- XXX.minecraft.server.Eula
+ XXX.minecraft.server.LoggedPrintStream
- XXX.minecraft.server.Main
+ XXX.minecraft.server.Main$1
- XXX.minecraft.server.MinecraftServer
+ XXX.minecraft.server.MinecraftServer$1
- XXX.minecraft.server.MinecraftServer$2
- XXX.minecraft.server.package-info
+ XXX.minecraft.server.PlayerAdvancements
- XXX.minecraft.server.PlayerAdvancements$1
+ XXX.minecraft.server.RunningOnDifferentThreadException
- XXX.minecraft.server.ServerAdvancementManager
+ XXX.minecraft.server.ServerFunctionLibrary
- XXX.minecraft.server.ServerFunctionManager
+ XXX.minecraft.server.ServerFunctionManager$QueuedCommand
- XXX.minecraft.server.ServerInterface
+ XXX.minecraft.server.ServerResources
- XXX.minecraft.server.ServerScoreboard
+ XXX.minecraft.server.ServerScoreboard$Method
- XXX.minecraft.server.TickTask
+ XXX.minecraft.sounds.Music
- XXX.minecraft.sounds.Musics
- XXX.minecraft.sounds.package-info
+ XXX.minecraft.sounds.SoundEvent
- XXX.minecraft.sounds.SoundEvents
+ XXX.minecraft.sounds.SoundSource
+ XXX.minecraft.stats.package-info
+ XXX.minecraft.stats.RecipeBook
- XXX.minecraft.stats.ServerRecipeBook
+ XXX.minecraft.stats.ServerStatsCounter
- XXX.minecraft.stats.Stat
+ XXX.minecraft.stats.StatFormatter
+ XXX.minecraft.stats.Stats
- XXX.minecraft.stats.StatsCounter
- XXX.minecraft.stats.StatType
- XXX.minecraft.tags.BlockTags
+ XXX.minecraft.tags.EntityTypeTags
- XXX.minecraft.tags.FluidTags
+ XXX.minecraft.tags.ItemTags
- XXX.minecraft.tags.SerializationTags
- XXX.minecraft.util.Codecs$1
- XXX.minecraft.util.Codecs$ResultFunction
+ XXX.minecraft.util.CrudeIncrementalIntIdentityHashBiMap
- XXX.minecraft.util.Crypt
+ XXX.minecraft.util.CsvOutput
- XXX.minecraft.util.CsvOutput$1
+ XXX.minecraft.util.CsvOutput$Builder
- XXX.minecraft.util.CubicSampler
+ XXX.minecraft.util.CubicSampler$Vec3Fetcher
- XXX.minecraft.util.DirectoryLock
+ XXX.minecraft.util.DirectoryLock$LockException
- XXX.minecraft.util.ExceptionCollector
+ XXX.minecraft.util.FastColor
- XXX.minecraft.util.FastColor$ARGB32
+ XXX.minecraft.util.FrameTimer
- XXX.minecraft.util.GsonHelper
+ XXX.minecraft.util.HeapDumper
- XXX.minecraft.util.HttpUtil
+ XXX.minecraft.util.InsensitiveStringMap
- XXX.minecraft.util.IntRange
+ XXX.minecraft.util.LazyLoadedValue
- XXX.minecraft.util.LimitedCapacityList
+ XXX.minecraft.util.LinearCongruentialGenerator
- XXX.minecraft.util.LowerCaseEnumTypeAdapterFactory
+ XXX.minecraft.util.LowerCaseEnumTypeAdapterFactory$1
- XXX.minecraft.util.Mth
+ XXX.minecraft.util.ProgressListener
- XXX.minecraft.util.RewindableStream
+ XXX.minecraft.util.RewindableStream$1
- XXX.minecraft.util.SmoothDouble
+ XXX.minecraft.util.SortedArraySet
- XXX.minecraft.util.SortedArraySet$1
+ XXX.minecraft.util.SortedArraySet$ArrayIterator
- XXX.minecraft.util.StringRepresentable
+ XXX.minecraft.util.StringRepresentable$1
- XXX.minecraft.util.StringRepresentable$2
+ XXX.minecraft.util.StringUtil
- XXX.minecraft.util.TimeUtil
+ XXX.minecraft.util.Tuple
- XXX.minecraft.util.Unit
+ XXX.minecraft.util.VisibleForDebug
- XXX.minecraft.util.WeighedRandom
+ XXX.minecraft.util.WeighedRandom$WeighedRandomItem
+ XXX.minecraft.world.package-info
- XXX.network.protocol.package-info
- XXX.network.syncher.EntityDataAccessor
+ XXX.network.syncher.EntityDataSerializer
- XXX.network.syncher.EntityDataSerializers
+ XXX.network.syncher.EntityDataSerializers$1
- XXX.network.syncher.EntityDataSerializers$10
+ XXX.network.syncher.EntityDataSerializers$11
- XXX.network.syncher.EntityDataSerializers$12
+ XXX.network.syncher.EntityDataSerializers$13
- XXX.network.syncher.EntityDataSerializers$14
+ XXX.network.syncher.EntityDataSerializers$15
- XXX.network.syncher.EntityDataSerializers$16
+ XXX.network.syncher.EntityDataSerializers$17
- XXX.network.syncher.EntityDataSerializers$18
+ XXX.network.syncher.EntityDataSerializers$19
- XXX.network.syncher.EntityDataSerializers$2
+ XXX.network.syncher.EntityDataSerializers$3
- XXX.network.syncher.EntityDataSerializers$4
+ XXX.network.syncher.EntityDataSerializers$5
- XXX.network.syncher.EntityDataSerializers$6
+ XXX.network.syncher.EntityDataSerializers$7
- XXX.network.syncher.EntityDataSerializers$8
+ XXX.network.syncher.EntityDataSerializers$9
- XXX.network.syncher.package-info
- XXX.network.syncher.SynchedEntityData
+ XXX.network.syncher.SynchedEntityData$DataItem
- XXX.newbiome.area.Area
+ XXX.newbiome.area.AreaFactory
- XXX.newbiome.area.LazyArea
+ XXX.newbiome.area.package-info
- XXX.newbiome.context.BigContext
+ XXX.newbiome.context.Context
- XXX.newbiome.context.LazyAreaContext
+ XXX.newbiome.context.package-info
- XXX.newbiome.layer.AddDeepOceanLayer
+ XXX.newbiome.layer.AddEdgeLayer
- XXX.newbiome.layer.AddEdgeLayer$CoolWarm
+ XXX.newbiome.layer.AddEdgeLayer$HeatIce
- XXX.newbiome.layer.AddEdgeLayer$IntroduceSpecial
+ XXX.newbiome.layer.AddIslandLayer
- XXX.newbiome.layer.AddMushroomIslandLayer
+ XXX.newbiome.layer.AddSnowLayer
- XXX.newbiome.layer.BiomeEdgeLayer
+ XXX.newbiome.layer.BiomeInitLayer
- XXX.newbiome.layer.IslandLayer
+ XXX.newbiome.layer.Layer
- XXX.newbiome.layer.Layers
+ XXX.newbiome.layer.OceanLayer
- XXX.newbiome.layer.OceanMixerLayer
- XXX.newbiome.layer.package-info
+ XXX.newbiome.layer.RareBiomeLargeLayer
- XXX.newbiome.layer.RareBiomeSpotLayer
+ XXX.newbiome.layer.RegionHillsLayer
- XXX.newbiome.layer.RemoveTooMuchOceanLayer
+ XXX.newbiome.layer.RiverInitLayer
- XXX.newbiome.layer.RiverLayer
+ XXX.newbiome.layer.RiverMixerLayer
- XXX.newbiome.layer.ShoreLayer
+ XXX.newbiome.layer.SmoothLayer
- XXX.newbiome.layer.ZoomLayer
+ XXX.newbiome.layer.ZoomLayer$1
- XXX.packs.metadata.MetadataSectionSerializer
- XXX.packs.metadata.package-info
- XXX.packs.repository.FolderRepositorySource
+ XXX.packs.repository.Pack
- XXX.packs.repository.Pack$PackConstructor
+ XXX.packs.repository.Pack$Position
+ XXX.packs.repository.package-info
- XXX.packs.repository.PackCompatibility
+ XXX.packs.repository.PackRepository
- XXX.packs.repository.PackSource
+ XXX.packs.repository.RepositorySource
- XXX.packs.repository.ServerPacksSource
- XXX.packs.resources.FallbackResourceManager
+ XXX.packs.resources.FallbackResourceManager$LeakedResourceWarningInputStream
- XXX.packs.resources.package-info
- XXX.packs.resources.PreparableReloadListener
+ XXX.packs.resources.PreparableReloadListener$PreparationBarrier
- XXX.packs.resources.ProfiledReloadInstance
+ XXX.packs.resources.ProfiledReloadInstance$1
- XXX.packs.resources.ProfiledReloadInstance$State
- XXX.packs.resources.ReloadableResourceManager
+ XXX.packs.resources.ReloadInstance
+ XXX.packs.resources.Resource
- XXX.packs.resources.ResourceManager
+ XXX.packs.resources.ResourceManager$Empty
- XXX.packs.resources.ResourceManagerReloadListener
+ XXX.packs.resources.SimpleJsonResourceReloadListener
- XXX.packs.resources.SimplePreparableReloadListener
- XXX.packs.resources.SimpleReloadableResourceManager
+ XXX.packs.resources.SimpleReloadableResourceManager$FailingReloadInstance
- XXX.packs.resources.SimpleReloadableResourceManager$ResourcePackLoadingFailure
+ XXX.packs.resources.SimpleReloadInstance
- XXX.packs.resources.SimpleReloadInstance$1
+ XXX.packs.resources.SimpleReloadInstance$StateFactory
+ XXX.packs.resources.SimpleResource
+ XXX.phys.shapes.ArrayVoxelShape
- XXX.phys.shapes.ArrayVoxelShape$1
+ XXX.phys.shapes.BitSetDiscreteVoxelShape
- XXX.phys.shapes.BooleanOp
+ XXX.phys.shapes.CollisionContext
- XXX.phys.shapes.CubePointRange
+ XXX.phys.shapes.CubeVoxelShape
- XXX.phys.shapes.DiscreteCubeMerger
+ XXX.phys.shapes.DiscreteVoxelShape
- XXX.phys.shapes.DiscreteVoxelShape$IntFaceConsumer
+ XXX.phys.shapes.DiscreteVoxelShape$IntLineConsumer
- XXX.phys.shapes.EntityCollisionContext
+ XXX.phys.shapes.EntityCollisionContext$1
- XXX.phys.shapes.IdenticalMerger
+ XXX.phys.shapes.IndexMerger
- XXX.phys.shapes.IndexMerger$IndexConsumer
+ XXX.phys.shapes.IndirectMerger
- XXX.phys.shapes.IntPointRange
+ XXX.phys.shapes.NonOverlappingMerger
- XXX.phys.shapes.OffsetDoubleList
+ XXX.phys.shapes.package-info
+ XXX.phys.shapes.Shapes
- XXX.phys.shapes.Shapes$DoubleLineConsumer
+ XXX.phys.shapes.SliceShape
- XXX.phys.shapes.SubShape
+ XXX.phys.shapes.VoxelShape
- XXX.phys.shapes.WorldRegionIndirectVoxelShape
- XXX.protocol.game.ClientboundHorseScreenOpenPacket
+ XXX.protocol.game.ClientboundKeepAlivePacket
- XXX.protocol.game.ClientboundLevelChunkPacket
+ XXX.protocol.game.ClientboundLevelEventPacket
- XXX.protocol.game.ClientboundLevelParticlesPacket
+ XXX.protocol.game.ClientboundLightUpdatePacket
- XXX.protocol.game.ClientboundLoginPacket
+ XXX.protocol.game.ClientboundMapItemDataPacket
- XXX.protocol.game.ClientboundMerchantOffersPacket
+ XXX.protocol.game.ClientboundMoveEntityPacket
- XXX.protocol.game.ClientboundMoveEntityPacket$Pos
+ XXX.protocol.game.ClientboundMoveEntityPacket$PosRot
- XXX.protocol.game.ClientboundMoveEntityPacket$Rot
+ XXX.protocol.game.ClientboundMoveVehiclePacket
- XXX.protocol.game.ClientboundOpenBookPacket
+ XXX.protocol.game.ClientboundOpenScreenPacket
- XXX.protocol.game.ClientboundOpenSignEditorPacket
+ XXX.protocol.game.ClientboundPlaceGhostRecipePacket
- XXX.protocol.game.ClientboundPlayerAbilitiesPacket
+ XXX.protocol.game.ClientboundPlayerCombatPacket
- XXX.protocol.game.ClientboundPlayerCombatPacket$1
+ XXX.protocol.game.ClientboundPlayerCombatPacket$Event
- XXX.protocol.game.ClientboundPlayerInfoPacket
+ XXX.protocol.game.ClientboundPlayerInfoPacket$1
- XXX.protocol.game.ClientboundPlayerInfoPacket$Action
+ XXX.protocol.game.ClientboundPlayerInfoPacket$PlayerUpdate
- XXX.protocol.game.ClientboundPlayerLookAtPacket
+ XXX.protocol.game.ClientboundPlayerPositionPacket
- XXX.protocol.game.ClientboundPlayerPositionPacket$RelativeArgument
+ XXX.protocol.game.ClientboundRecipePacket
- XXX.protocol.game.ClientboundRecipePacket$State
+ XXX.protocol.game.ClientboundRemoveEntitiesPacket
- XXX.protocol.game.ClientboundRemoveMobEffectPacket
+ XXX.protocol.game.ClientboundResourcePackPacket
- XXX.protocol.game.ClientboundRespawnPacket
+ XXX.protocol.game.ClientboundRotateHeadPacket
- XXX.protocol.game.ClientboundSelectAdvancementsTabPacket
+ XXX.protocol.game.ClientboundSetBorderPacket
- XXX.protocol.game.ClientboundSetBorderPacket$1
+ XXX.protocol.game.ClientboundSetBorderPacket$Type
- XXX.protocol.game.ClientboundSetCameraPacket
+ XXX.protocol.game.ClientboundSetCarriedItemPacket
- XXX.protocol.game.ClientboundSetChunkCacheCenterPacket
+ XXX.protocol.game.ClientboundSetChunkCacheRadiusPacket
- XXX.protocol.game.ClientboundSetDefaultSpawnPositionPacket
+ XXX.protocol.game.ClientboundSetDisplayObjectivePacket
- XXX.protocol.game.ClientboundSetEntityDataPacket
+ XXX.protocol.game.ClientboundSetEntityLinkPacket
- XXX.protocol.game.ClientboundSetEntityMotionPacket
+ XXX.protocol.game.ClientboundSetEquippedItemPacket
- XXX.protocol.game.ClientboundSetExperiencePacket
+ XXX.protocol.game.ClientboundSetHealthPacket
- XXX.protocol.game.ClientboundSetObjectivePacket
+ XXX.protocol.game.ClientboundSetPassengersPacket
- XXX.protocol.game.ClientboundSetPlayerTeamPacket
+ XXX.protocol.game.ClientboundSetScorePacket
- XXX.protocol.game.ClientboundSetTimePacket
+ XXX.protocol.game.ClientboundSetTitlesPacket
- XXX.protocol.game.ClientboundSetTitlesPacket$Type
+ XXX.protocol.game.ClientboundSoundEntityPacket
- XXX.protocol.game.ClientboundSoundPacket
+ XXX.protocol.game.ClientboundStopSoundPacket
- XXX.protocol.game.ClientboundTabListPacket
+ XXX.protocol.game.ClientboundTagQueryPacket
- XXX.protocol.game.ClientboundTakeItemEntityPacket
+ XXX.protocol.game.ClientboundTeleportEntityPacket
- XXX.protocol.game.ClientboundUpdateAdvancementsPacket
+ XXX.protocol.game.ClientboundUpdateAttributesPacket
- XXX.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
+ XXX.protocol.game.ClientboundUpdateMobEffectPacket
- XXX.protocol.game.ClientboundUpdateRecipesPacket
+ XXX.protocol.game.ClientboundUpdateTagsPacket
- XXX.protocol.game.DebugEntityNameGenerator
+ XXX.protocol.game.DebugPackets
+ XXX.protocol.game.package-info
+ XXX.protocol.game.ServerboundAcceptTeleportationPacket
- XXX.protocol.game.ServerboundBlockEntityTagQuery
+ XXX.protocol.game.ServerboundChangeDifficultyPacket
- XXX.protocol.game.ServerboundChatPacket
+ XXX.protocol.game.ServerboundClientCommandPacket
- XXX.protocol.game.ServerboundClientCommandPacket$Action
+ XXX.protocol.game.ServerboundClientInformationPacket
- XXX.protocol.game.ServerboundCommandSuggestionPacket
+ XXX.protocol.game.ServerboundContainerAckPacket
- XXX.protocol.game.ServerboundContainerButtonClickPacket
+ XXX.protocol.game.ServerboundContainerClickPacket
- XXX.protocol.game.ServerboundContainerClosePacket
+ XXX.protocol.game.ServerboundCustomPayloadPacket
- XXX.protocol.game.ServerboundEditBookPacket
+ XXX.protocol.game.ServerboundEntityTagQuery
- XXX.protocol.game.ServerboundInteractPacket
+ XXX.protocol.game.ServerboundInteractPacket$Action
- XXX.protocol.game.ServerboundJigsawGeneratePacket
+ XXX.protocol.game.ServerboundKeepAlivePacket
- XXX.protocol.game.ServerboundLockDifficultyPacket
+ XXX.protocol.game.ServerboundMovePlayerPacket
- XXX.protocol.game.ServerboundMovePlayerPacket$Pos
+ XXX.protocol.game.ServerboundMovePlayerPacket$PosRot
- XXX.protocol.game.ServerboundMovePlayerPacket$Rot
+ XXX.protocol.game.ServerboundMoveVehiclePacket
- XXX.protocol.game.ServerboundPaddleBoatPacket
+ XXX.protocol.game.ServerboundPickItemPacket
- XXX.protocol.game.ServerboundPlaceRecipePacket
+ XXX.protocol.game.ServerboundPlayerAbilitiesPacket
- XXX.protocol.game.ServerboundPlayerActionPacket
+ XXX.protocol.game.ServerboundPlayerActionPacket$Action
- XXX.protocol.game.ServerboundPlayerCommandPacket
+ XXX.protocol.game.ServerboundPlayerCommandPacket$Action
- XXX.protocol.game.ServerboundPlayerInputPacket
+ XXX.protocol.game.ServerboundRecipeBookUpdatePacket
- XXX.protocol.game.ServerboundRecipeBookUpdatePacket$Purpose
+ XXX.protocol.game.ServerboundRenameItemPacket
- XXX.protocol.game.ServerboundResourcePackPacket
+ XXX.protocol.game.ServerboundResourcePackPacket$Action
- XXX.protocol.game.ServerboundSeenAdvancementsPacket
+ XXX.protocol.game.ServerboundSeenAdvancementsPacket$Action
- XXX.protocol.game.ServerboundSelectTradePacket
+ XXX.protocol.game.ServerboundSetBeaconPacket
- XXX.protocol.game.ServerboundSetCarriedItemPacket
+ XXX.protocol.game.ServerboundSetCommandBlockPacket
- XXX.protocol.game.ServerboundSetCommandMinecartPacket
+ XXX.protocol.game.ServerboundSetCreativeModeSlotPacket
- XXX.protocol.game.ServerboundSetJigsawBlockPacket
+ XXX.protocol.game.ServerboundSetStructureBlockPacket
- XXX.protocol.game.ServerboundSignUpdatePacket
+ XXX.protocol.game.ServerboundSwingPacket
- XXX.protocol.game.ServerboundTeleportToEntityPacket
+ XXX.protocol.game.ServerboundUseItemOnPacket
- XXX.protocol.game.ServerboundUseItemPacket
- XXX.protocol.game.ServerGamePacketListener
- XXX.protocol.handshake.ClientIntentionPacket
- XXX.protocol.handshake.package-info
+ XXX.protocol.handshake.ServerHandshakePacketListener
- XXX.protocol.login.ClientboundCustomQueryPacket
+ XXX.protocol.login.ClientboundGameProfilePacket
- XXX.protocol.login.ClientboundHelloPacket
+ XXX.protocol.login.ClientboundLoginCompressionPacket
- XXX.protocol.login.ClientboundLoginDisconnectPacket
+ XXX.protocol.login.ClientLoginPacketListener
+ XXX.protocol.login.package-info
- XXX.protocol.login.ServerboundCustomQueryPacket
+ XXX.protocol.login.ServerboundHelloPacket
- XXX.protocol.login.ServerboundKeyPacket
+ XXX.protocol.login.ServerLoginPacketListener
- XXX.protocol.status.ClientboundPongResponsePacket
+ XXX.protocol.status.ClientboundStatusResponsePacket
+ XXX.protocol.status.ClientStatusPacketListener
+ XXX.protocol.status.package-info
+ XXX.protocol.status.ServerboundPingRequestPacket
- XXX.protocol.status.ServerboundStatusRequestPacket
- XXX.protocol.status.ServerStatus
+ XXX.protocol.status.ServerStatus$Players
- XXX.protocol.status.ServerStatus$Players$Serializer
+ XXX.protocol.status.ServerStatus$Serializer
- XXX.protocol.status.ServerStatus$Version
+ XXX.protocol.status.ServerStatus$Version$Serializer
- XXX.protocol.status.ServerStatusPacketListener
+ XXX.rcon.thread.GenericThread
- XXX.rcon.thread.package-info
- XXX.rcon.thread.QueryThreadGs4
+ XXX.rcon.thread.QueryThreadGs4$RequestChallenge
- XXX.rcon.thread.RconClient
+ XXX.rcon.thread.RconThread
+ XXX.saveddata.maps.MapBanner
- XXX.saveddata.maps.MapBanner$1
+ XXX.saveddata.maps.MapDecoration
- XXX.saveddata.maps.MapDecoration$Type
+ XXX.saveddata.maps.MapFrame
- XXX.saveddata.maps.MapIndex
+ XXX.saveddata.maps.MapItemSavedData
- XXX.saveddata.maps.MapItemSavedData$HoldingPlayer
+ XXX.saveddata.maps.package-info
- XXX.scores.criteria.ObjectiveCriteria
+ XXX.scores.criteria.ObjectiveCriteria$RenderType
- XXX.scores.criteria.package-info
+ XXX.server.bossevents.CustomBossEvent
- XXX.server.bossevents.CustomBossEvents
+ XXX.server.bossevents.package-info
- XXX.server.commands.AdvancementCommands
+ XXX.server.commands.AdvancementCommands$1
- XXX.server.commands.AdvancementCommands$Action
+ XXX.server.commands.AdvancementCommands$Action$1
- XXX.server.commands.AdvancementCommands$Action$2
+ XXX.server.commands.AdvancementCommands$Mode
- XXX.server.commands.AttributeCommand
+ XXX.server.commands.BanIpCommands
- XXX.server.commands.BanListCommands
+ XXX.server.commands.BanPlayerCommands
- XXX.server.commands.BossBarCommands
+ XXX.server.commands.ClearInventoryCommands
- XXX.server.commands.CloneCommands
+ XXX.server.commands.CloneCommands$CloneBlockInfo
- XXX.server.commands.CloneCommands$Mode
+ XXX.server.commands.DataPackCommand
- XXX.server.commands.DataPackCommand$Inserter
- XXX.server.commands.DebugCommand
+ XXX.server.commands.DebugMobSpawningCommand
- XXX.server.commands.DebugPathCommand
+ XXX.server.commands.DefaultGameModeCommands
+ XXX.server.commands.DeOpCommands
- XXX.server.commands.DifficultyCommand
+ XXX.server.commands.EffectCommands
- XXX.server.commands.EmoteCommands
+ XXX.server.commands.EnchantCommand
- XXX.server.commands.ExecuteCommand
+ XXX.server.commands.ExecuteCommand$CommandNumericPredicate
- XXX.server.commands.ExecuteCommand$CommandPredicate
+ XXX.server.commands.ExperienceCommand
- XXX.server.commands.ExperienceCommand$Type
+ XXX.server.commands.FillCommand
- XXX.server.commands.FillCommand$Mode
+ XXX.server.commands.ForceLoadCommand
- XXX.server.commands.FunctionCommand
+ XXX.server.commands.GameModeCommand
- XXX.server.commands.GameRuleCommand
+ XXX.server.commands.GameRuleCommand$1
- XXX.server.commands.GiveCommand
+ XXX.server.commands.HelpCommand
- XXX.server.commands.KickCommand
+ XXX.server.commands.KillCommand
- XXX.server.commands.ListPlayersCommand
+ XXX.server.commands.LocateBiomeCommand
- XXX.server.commands.LocateCommand
+ XXX.server.commands.LootCommand
- XXX.server.commands.LootCommand$Callback
+ XXX.server.commands.LootCommand$DropConsumer
- XXX.server.commands.LootCommand$TailProvider
+ XXX.server.commands.MsgCommand
- XXX.server.commands.OpCommand
+ XXX.server.commands.package-info
+ XXX.server.commands.PardonCommand
- XXX.server.commands.PardonIpCommand
+ XXX.server.commands.ParticleCommand
- XXX.server.commands.PlaySoundCommand
+ XXX.server.commands.PublishCommand
- XXX.server.commands.RaidCommand
+ XXX.server.commands.RecipeCommand
- XXX.server.commands.ReloadCommand
+ XXX.server.commands.ReplaceItemCommand
- XXX.server.commands.SaveAllCommand
+ XXX.server.commands.SaveOffCommand
- XXX.server.commands.SaveOnCommand
+ XXX.server.commands.SayCommand
- XXX.server.commands.ScheduleCommand
+ XXX.server.commands.ScoreboardCommand
- XXX.server.commands.SeedCommand
+ XXX.server.commands.SetBlockCommand
- XXX.server.commands.SetBlockCommand$Filter
+ XXX.server.commands.SetBlockCommand$Mode
- XXX.server.commands.SetPlayerIdleTimeoutCommand
+ XXX.server.commands.SetSpawnCommand
- XXX.server.commands.SetWorldSpawnCommand
+ XXX.server.commands.SpectateCommand
- XXX.server.commands.SpreadPlayersCommand
+ XXX.server.commands.SpreadPlayersCommand$Position
- XXX.server.commands.StopCommand
+ XXX.server.commands.StopSoundCommand
- XXX.server.commands.SummonCommand
+ XXX.server.commands.TagCommand
- XXX.server.commands.TeamCommand
+ XXX.server.commands.TeamMsgCommand
- XXX.server.commands.TeleportCommand
+ XXX.server.commands.TeleportCommand$LookAt
- XXX.server.commands.TellRawCommand
+ XXX.server.commands.TimeCommand
- XXX.server.commands.TitleCommand
+ XXX.server.commands.TriggerCommand
- XXX.server.commands.WeatherCommand
+ XXX.server.commands.WhitelistCommand
- XXX.server.commands.WorldBorderCommand
- XXX.server.dedicated.DedicatedPlayerList
+ XXX.server.dedicated.DedicatedServer
- XXX.server.dedicated.DedicatedServer$1
+ XXX.server.dedicated.DedicatedServerProperties
- XXX.server.dedicated.DedicatedServerSettings
- XXX.server.dedicated.package-info
+ XXX.server.dedicated.ServerWatchdog
- XXX.server.dedicated.ServerWatchdog$1
+ XXX.server.dedicated.Settings
- XXX.server.dedicated.Settings$1
+ XXX.server.dedicated.Settings$MutableValue
+ XXX.server.gui.MinecraftServerGui
- XXX.server.gui.MinecraftServerGui$1
+ XXX.server.gui.MinecraftServerGui$2
- XXX.server.gui.package-info
- XXX.server.gui.PlayerListComponent
+ XXX.server.gui.StatsComponent
+ XXX.server.level.BlockDestructionProgress
- XXX.server.level.ChunkHolder
+ XXX.server.level.ChunkHolder$1
- XXX.server.level.ChunkHolder$ChunkLoadingFailure
+ XXX.server.level.ChunkHolder$ChunkLoadingFailure$1
- XXX.server.level.ChunkHolder$FullChunkStatus
+ XXX.server.level.ChunkHolder$LevelChangeListener
- XXX.server.level.ChunkHolder$PlayerProvider
+ XXX.server.level.ChunkMap
- XXX.server.level.ChunkMap$1
+ XXX.server.level.ChunkMap$2
- XXX.server.level.ChunkMap$DistanceManager
+ XXX.server.level.ChunkMap$TrackedEntity
- XXX.server.level.ChunkTaskPriorityQueue
+ XXX.server.level.ChunkTaskPriorityQueueSorter
- XXX.server.level.ChunkTaskPriorityQueueSorter$1
+ XXX.server.level.ChunkTaskPriorityQueueSorter$Message
- XXX.server.level.ChunkTaskPriorityQueueSorter$Release
+ XXX.server.level.ChunkTracker
- XXX.server.level.ColumnPos
+ XXX.server.level.DemoMode
- XXX.server.level.DistanceManager
+ XXX.server.level.DistanceManager$ChunkTicketTracker
- XXX.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
+ XXX.server.level.DistanceManager$PlayerTicketTracker
- XXX.server.level.FeatureSimulator
- XXX.server.level.package-info
+ XXX.server.level.PlayerMap
- XXX.server.level.PlayerRespawnLogic
+ XXX.server.level.SectionTracker
- XXX.server.level.ServerBossEvent
+ XXX.server.level.ServerChunkCache
- XXX.server.level.ServerChunkCache$1
+ XXX.server.level.ServerChunkCache$MainThreadExecutor
- XXX.server.level.ServerEntity
+ XXX.server.level.ServerLevel
- XXX.server.level.ServerPlayer
+ XXX.server.level.ServerPlayerGameMode
- XXX.server.level.ThreadedLevelLightEngine
+ XXX.server.level.ThreadedLevelLightEngine$TaskType
- XXX.server.level.Ticket
+ XXX.server.level.TicketType
- XXX.server.level.WorldGenRegion
+ XXX.server.level.WorldGenTickList
+ XXX.server.network.LegacyQueryHandler
- XXX.server.network.MemoryServerHandshakePacketListenerImpl
+ XXX.server.network.package-info
+ XXX.server.network.ServerConnectionListener
- XXX.server.network.ServerConnectionListener$1
+ XXX.server.network.ServerConnectionListener$2
- XXX.server.network.ServerConnectionListener$LatencySimulator
+ XXX.server.network.ServerGamePacketListenerImpl
- XXX.server.network.ServerGamePacketListenerImpl$1
+ XXX.server.network.ServerHandshakePacketListenerImpl
- XXX.server.network.ServerHandshakePacketListenerImpl$1
+ XXX.server.network.ServerLoginPacketListenerImpl
- XXX.server.network.ServerLoginPacketListenerImpl$1
+ XXX.server.network.ServerLoginPacketListenerImpl$State
- XXX.server.network.ServerStatusPacketListenerImpl
+ XXX.server.packs.AbstractPackResources
- XXX.server.packs.FilePackResources
+ XXX.server.packs.FolderPackResources
+ XXX.server.packs.package-info
- XXX.server.packs.PackResources
+ XXX.server.packs.PackType
- XXX.server.packs.ResourcePackFileNotFoundException
+ XXX.server.packs.VanillaPackResources
+ XXX.server.players.BanListEntry
- XXX.server.players.GameProfileCache
+ XXX.server.players.GameProfileCache$1
- XXX.server.players.GameProfileCache$2
+ XXX.server.players.GameProfileCache$GameProfileInfo
- XXX.server.players.GameProfileCache$Serializer
+ XXX.server.players.IpBanList
- XXX.server.players.IpBanListEntry
+ XXX.server.players.OldUsersConverter
- XXX.server.players.OldUsersConverter$1
+ XXX.server.players.OldUsersConverter$2
- XXX.server.players.OldUsersConverter$3
+ XXX.server.players.OldUsersConverter$4
- XXX.server.players.OldUsersConverter$5
+ XXX.server.players.OldUsersConverter$ConversionError
- XXX.server.players.package-info
- XXX.server.players.PlayerList
+ XXX.server.players.PlayerList$1
- XXX.server.players.ServerOpList
+ XXX.server.players.ServerOpListEntry
- XXX.server.players.StoredUserEntry
+ XXX.server.players.StoredUserList
- XXX.server.players.UserBanList
+ XXX.server.players.UserBanListEntry
- XXX.server.players.UserWhiteList
+ XXX.server.players.UserWhiteListEntry
+ XXX.server.rcon.NetworkDataOutputStream
- XXX.server.rcon.package-info
- XXX.server.rcon.PktUtils
+ XXX.server.rcon.RconConsoleSource
- XXX.storage.loot.BinomialDistributionGenerator
+ XXX.storage.loot.BinomialDistributionGenerator$Serializer
- XXX.storage.loot.BuiltInLootTables
+ XXX.storage.loot.ConstantIntValue
- XXX.storage.loot.ConstantIntValue$Serializer
+ XXX.storage.loot.Deserializers
- XXX.storage.loot.GsonAdapterFactory
+ XXX.storage.loot.GsonAdapterFactory$1
- XXX.storage.loot.GsonAdapterFactory$Builder
+ XXX.storage.loot.GsonAdapterFactory$DefaultSerializer
- XXX.storage.loot.GsonAdapterFactory$JsonAdapter
+ XXX.storage.loot.IntLimiter
- XXX.storage.loot.IntLimiter$1
+ XXX.storage.loot.IntLimiter$Serializer
- XXX.storage.loot.LootContext
+ XXX.storage.loot.LootContext$1
- XXX.storage.loot.LootContext$Builder
+ XXX.storage.loot.LootContext$DynamicDrop
- XXX.storage.loot.LootContext$EntityTarget
+ XXX.storage.loot.LootContext$EntityTarget$Serializer
- XXX.storage.loot.LootContextUser
+ XXX.storage.loot.LootPool
- XXX.storage.loot.LootPool$1
+ XXX.storage.loot.LootPool$Builder
- XXX.storage.loot.LootPool$Serializer
+ XXX.storage.loot.LootTable
- XXX.storage.loot.LootTable$1
+ XXX.storage.loot.LootTable$Builder
- XXX.storage.loot.LootTable$Serializer
+ XXX.storage.loot.LootTables
- XXX.storage.loot.package-info
- XXX.storage.loot.PredicateManager
+ XXX.storage.loot.PredicateManager$1
- XXX.storage.loot.PredicateManager$CompositePredicate
+ XXX.storage.loot.RandomIntGenerator
- XXX.storage.loot.RandomIntGenerators
+ XXX.storage.loot.RandomValueBounds
- XXX.storage.loot.RandomValueBounds$Serializer
+ XXX.storage.loot.Serializer
- XXX.storage.loot.SerializerType
+ XXX.storage.loot.ValidationContext
+ XXX.storage.threaded.package-info
- XXX.structure.templatesystem.LinearPosTest
+ XXX.structure.templatesystem.NopProcessor
- XXX.structure.templatesystem.package-info
- XXX.structure.templatesystem.PosAlwaysTrueTest
+ XXX.structure.templatesystem.PosRuleTest
- XXX.structure.templatesystem.PosRuleTestType
+ XXX.structure.templatesystem.ProcessorRule
- XXX.structure.templatesystem.RandomBlockMatchTest
+ XXX.structure.templatesystem.RandomBlockStateMatchTest
- XXX.structure.templatesystem.RuleProcessor
+ XXX.structure.templatesystem.RuleTest
- XXX.structure.templatesystem.RuleTestType
+ XXX.structure.templatesystem.StructureManager
- XXX.structure.templatesystem.StructurePlaceSettings
+ XXX.structure.templatesystem.StructureProcessor
- XXX.structure.templatesystem.StructureProcessorType
+ XXX.structure.templatesystem.StructureTemplate
- XXX.structure.templatesystem.StructureTemplate$1
+ XXX.structure.templatesystem.StructureTemplate$Palette
- XXX.structure.templatesystem.StructureTemplate$SimplePalette
+ XXX.structure.templatesystem.StructureTemplate$StructureBlockInfo
- XXX.structure.templatesystem.StructureTemplate$StructureEntityInfo
+ XXX.structure.templatesystem.TagMatchTest
+ XXX.util.datafix.DataFixers
- XXX.util.datafix.DataFixers$1
+ XXX.util.datafix.DataFixers$2
- XXX.util.datafix.DataFixTypes
- XXX.util.datafix.PackedBitStorage
- XXX.world.entity.EntitySelector$MobCanWearArmorEntitySelector
+ XXX.world.entity.EntitySelector$MobCanWearArmourEntitySelector
+ XXX.world.level.package-info
- XXX.world.phys.AABB
+ XXX.world.phys.BlockHitResult
- XXX.world.phys.EntityHitResult
+ XXX.world.phys.HitResult
- XXX.world.phys.HitResult$Type
- XXX.world.phys.package-info
+ XXX.world.phys.PosAndRot
- XXX.world.phys.Vec2
+ XXX.world.phys.Vec3
- XXX.world.scores.Objective
+ XXX.world.scores.package-info
+ XXX.world.scores.PlayerTeam
- XXX.world.scores.Score
+ XXX.world.scores.Scoreboard
- XXX.world.scores.ScoreboardSaveData
+ XXX.world.scores.Team
- XXX.world.scores.Team$CollisionRule
+ XXX.world.scores.Team$Visibility
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.advancements.critereon.SimpleCriterionTrigger -1M
```
```
XXX.commands.arguments.DimensionArgument +1M -1M
```
```
XXX.minecraft.core.MappedRegistry +3M -3M
```
```
XXX.minecraft.core.Registry +3P -2P
```
```
XXX.network.chat.BaseComponent +2M -2M | +1P -1P
```
```
XXX.network.chat.KeybindComponent +3M -3M
```
```
XXX.network.chat.NbtComponent$EntityNbtComponent +3M -3M
```
```
XXX.network.chat.ScoreComponent +3M -3M
```
```
XXX.network.chat.TextComponent +3M -3M
```
```
XXX.protocol.game.ClientboundGameEventPacket +2M -2M | +13P -2P
```
```
XXX.minecraft.tags.StaticTagHelper +1M
```
```
XXX.minecraft.util.ClassInstanceMultiMap +1M
```
```
XXX.datafix.fixes.WorldGenSettingsFix +2M
```
```
XXX.world.entity.Entity +7M -7M | +4P -3P
```
```
XXX.world.entity.LivingEntity +1M
```
```
XXX.world.entity.NeutralMob +5M -2M
```
```
XXX.entity.animal.Bee +1M
```
```
XXX.entity.animal.Fox +1M
```
```
XXX.entity.animal.IronGolem +1M
```
```
XXX.entity.animal.Ocelot +1M
```
```
XXX.entity.animal.Parrot +1M
```
```
XXX.entity.animal.Pig +1M
```
```
XXX.entity.animal.Rabbit +1M
```
```
XXX.entity.item.ItemEntity +1M -1M
```
```
XXX.entity.npc.AbstractVillager +1M -1M
```
```
XXX.entity.npc.VillagerData +6M -4M
```
```
XXX.entity.vehicle.AbstractMinecartContainer +1M -1M
```
```
XXX.world.item.BlockPlaceContext +1M
```
```
XXX.world.level.EntityGetter +1M -1M
```
```
XXX.world.level.NaturalSpawner +1M
```
```
XXX.level.block.BedBlock +1M -1M
```
```
XXX.level.block.TurtleEggBlock +1M
```
```
XXX.level.dimension.LevelStem +1P -1P
```
```
XXX.level.levelgen.WorldGenSettings +2M -1M
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.SimpleCriterionTrigger
</summary>

```diff
+ void trigger(PlayerAdvancements)
```

</details>
<details>
<summary>
net.minecraft.commands.arguments.DimensionArgument
</summary>

```diff
+ ResourceKey getDimension(CommandContext,String)
- ServerLevel getDimension(CommandContext,String)
```

</details>
<details>
<summary>
net.minecraft.core.MappedRegistry
</summary>

```diff
+ Codec dataPackCodec(ResourceKey,Lifecycle,Codec)
- Codec dataPackCodec(ResourceKey,Lifecycle,MapCodec)
+ Codec directCodec(ResourceKey,Lifecycle,Codec)
- Codec directCodec(ResourceKey,Lifecycle,MapCodec)
+ Codec networkCodec(ResourceKey,Lifecycle,Codec)
- Codec networkCodec(ResourceKey,Lifecycle,MapCodec)
```

</details>
<details>
<summary>
net.minecraft.network.chat.BaseComponent
</summary>

```diff
- MutableComponent copy()
+ MutableComponent mutableCopy()
- MutableComponent plainCopy()
+ MutableComponent toMutable()
```

</details>
<details>
<summary>
net.minecraft.network.chat.KeybindComponent
</summary>

```diff
- BaseComponent plainCopy()
+ BaseComponent toMutable()
- KeybindComponent plainCopy()
+ KeybindComponent toMutable()
- MutableComponent plainCopy()
+ MutableComponent toMutable()
```

</details>
<details>
<summary>
net.minecraft.network.chat.NbtComponent$EntityNbtComponent
</summary>

```diff
- BaseComponent plainCopy()
+ BaseComponent toMutable()
- MutableComponent plainCopy()
+ MutableComponent toMutable()
- NbtComponent$EntityNbtComponent plainCopy()
+ NbtComponent$EntityNbtComponent toMutable()
```

</details>
<details>
<summary>
net.minecraft.network.chat.ScoreComponent
</summary>

```diff
- BaseComponent plainCopy()
+ BaseComponent toMutable()
- MutableComponent plainCopy()
+ MutableComponent toMutable()
- ScoreComponent plainCopy()
+ ScoreComponent toMutable()
```

</details>
<details>
<summary>
net.minecraft.network.chat.TextComponent
</summary>

```diff
- BaseComponent plainCopy()
+ BaseComponent toMutable()
- MutableComponent plainCopy()
+ MutableComponent toMutable()
- TextComponent plainCopy()
+ TextComponent toMutable()
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundGameEventPacket
</summary>

```diff
- ClientboundGameEventPacket$Type getEvent()
+ int getEvent()
- void <init>(ClientboundGameEventPacket$Type,float)
+ void <init>(int,float)
```

</details>
<details>
<summary>
net.minecraft.tags.StaticTagHelper
</summary>

```diff
- List getWrappers()
```

</details>
<details>
<summary>
net.minecraft.util.ClassInstanceMultiMap
</summary>

```diff
- List getAllInstances()
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.WorldGenSettingsFix
</summary>

```diff
- Dynamic defaultOverworld(Dynamic,long)
- Object vanillaLevels(Dynamic,long,Dynamic,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.entity.Entity
</summary>

```diff
- boolean isEyeInFluid(Tag)
+ boolean isUnderLiquid(Tag)
+ Entity changeDimension(ResourceKey)
- Entity changeDimension(ServerLevel)
- String lambda$fillCrashReportCategory$2()
+ String lambda$fillCrashReportCategory$6()
- Style lambda$getDisplayName$6(Style)
+ Style lambda$getDisplayName$7(Style)
+ Style lambda$removeAction$2(Style)
- Vec3 getLeashOffset()
- void lambda$teleportTo$7(ServerLevel,Entity)
+ void lambda$teleportTo$8(ServerLevel,Entity)
- void updateFluidOnEyes()
+ void updateUnderWaterState()
```

</details>
<details>
<summary>
net.minecraft.world.entity.LivingEntity
</summary>

```diff
- boolean isAffectedByFluids()
```

</details>
<details>
<summary>
net.minecraft.world.entity.NeutralMob
</summary>

```diff
- boolean isAngryAtAllPlayers(Level)
- void forgetCurrentTargetAndRefreshUniversalAnger()
+ void readPersistentAngerSaveData(Level,CompoundTag)
- void readPersistentAngerSaveData(ServerLevel,CompoundTag)
- void stopBeingAngry()
+ void updatePersistentAnger()
- void updatePersistentAnger(ServerLevel,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Bee
</summary>

```diff
- Vec3 getLeashOffset()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Fox
</summary>

```diff
- Vec3 getLeashOffset()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.IronGolem
</summary>

```diff
- Vec3 getLeashOffset()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Ocelot
</summary>

```diff
- Vec3 getLeashOffset()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Parrot
</summary>

```diff
- Vec3 getLeashOffset()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Pig
</summary>

```diff
- Vec3 getLeashOffset()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Rabbit
</summary>

```diff
- Vec3 getLeashOffset()
```

</details>
<details>
<summary>
net.minecraft.world.entity.item.ItemEntity
</summary>

```diff
+ Entity changeDimension(ResourceKey)
- Entity changeDimension(ServerLevel)
```

</details>
<details>
<summary>
net.minecraft.world.entity.npc.AbstractVillager
</summary>

```diff
+ Entity changeDimension(ResourceKey)
- Entity changeDimension(ServerLevel)
```

</details>
<details>
<summary>
net.minecraft.world.entity.npc.VillagerData
</summary>

```diff
+ App lambda$static$3(RecordCodecBuilder$Instance)
- App lambda$static$5(RecordCodecBuilder$Instance)
+ Integer lambda$null$2(VillagerData)
- Integer lambda$null$4(VillagerData)
+ VillagerProfession lambda$null$1(VillagerData)
- VillagerProfession lambda$null$2()
- VillagerProfession lambda$null$3(VillagerData)
- VillagerType lambda$null$0()
+ VillagerType lambda$null$0(VillagerData)
- VillagerType lambda$null$1(VillagerData)
```

</details>
<details>
<summary>
net.minecraft.world.entity.vehicle.AbstractMinecartContainer
</summary>

```diff
+ Entity changeDimension(ResourceKey)
- Entity changeDimension(ServerLevel)
```

</details>
<details>
<summary>
net.minecraft.world.item.BlockPlaceContext
</summary>

```diff
- void <init>(Player,InteractionHand,ItemStack,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.EntityGetter
</summary>

```diff
- Stream lambda$getEntityCollisions$1(Entity,AABB,Entity)
+ Stream lambda$getEntityCollisions$1(Entity,Entity)
```

</details>
<details>
<summary>
net.minecraft.world.level.NaturalSpawner
</summary>

```diff
- List mobsAt(ServerLevel,StructureFeatureManager,ChunkGenerator,MobCategory,BlockPos,Biome)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BedBlock
</summary>

```diff
+ boolean canSetSpawn(Level,BlockPos)
- boolean canSetSpawn(Level)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.TurtleEggBlock
</summary>

```diff
- boolean isSand(BlockGetter,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.WorldGenSettings
</summary>

```diff
+ DimensionType lambda$withOverworld$2(DimensionType)
- DimensionType lambda$withOverworld$2(LevelStem)
- MappedRegistry withOverworld(MappedRegistry,Supplier,ChunkGenerator)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
- net.minecraft.ChatFormatting
+ net.minecraft.CrashReport
- net.minecraft.CrashReportCategory
+ net.minecraft.CrashReportCategory$Entry
- net.minecraft.CrashReportDetail
+ net.minecraft.DefaultUncaughtExceptionHandler
- net.minecraft.DefaultUncaughtExceptionHandlerWithName
+ net.minecraft.DetectedVersion
- net.minecraft.FieldsAreNonnullByDefault
+ net.minecraft.FileUtil
- net.minecraft.MethodsReturnNonnullByDefault
+ net.minecraft.package-info
+ net.minecraft.ReportedException
- net.minecraft.ResourceLocationException
+ net.minecraft.SharedConstants
- net.minecraft.Util
+ net.minecraft.Util$1
- net.minecraft.Util$3
+ net.minecraft.Util$IdentityStrategy
- net.minecraft.Util$OS
+ net.minecraft.Util$OS$1
- net.minecraft.Util$OS$2
- XXX.advancements.critereon.AbstractCriterionTriggerInstance
+ XXX.advancements.critereon.BeeNestDestroyedTrigger
- XXX.advancements.critereon.BeeNestDestroyedTrigger$TriggerInstance
+ XXX.advancements.critereon.BlockPredicate
- XXX.advancements.critereon.BlockPredicate$Builder
+ XXX.advancements.critereon.BredAnimalsTrigger
- XXX.advancements.critereon.BredAnimalsTrigger$TriggerInstance
+ XXX.advancements.critereon.BrewedPotionTrigger
- XXX.advancements.critereon.BrewedPotionTrigger$TriggerInstance
+ XXX.advancements.critereon.ChangeDimensionTrigger
- XXX.advancements.critereon.ChangeDimensionTrigger$TriggerInstance
+ XXX.advancements.critereon.ChanneledLightningTrigger
- XXX.advancements.critereon.ChanneledLightningTrigger$TriggerInstance
+ XXX.advancements.critereon.ConstructBeaconTrigger
- XXX.advancements.critereon.ConstructBeaconTrigger$TriggerInstance
+ XXX.advancements.critereon.ConsumeItemTrigger
- XXX.advancements.critereon.ConsumeItemTrigger$TriggerInstance
+ XXX.advancements.critereon.CuredZombieVillagerTrigger
- XXX.advancements.critereon.CuredZombieVillagerTrigger$TriggerInstance
+ XXX.advancements.critereon.DamagePredicate
- XXX.advancements.critereon.DamagePredicate$Builder
+ XXX.advancements.critereon.DamageSourcePredicate
- XXX.advancements.critereon.DamageSourcePredicate$Builder
+ XXX.advancements.critereon.DeserializationContext
- XXX.advancements.critereon.DistancePredicate
+ XXX.advancements.critereon.EffectsChangedTrigger
- XXX.advancements.critereon.EffectsChangedTrigger$TriggerInstance
+ XXX.advancements.critereon.EnchantedItemTrigger
- XXX.advancements.critereon.EnchantedItemTrigger$TriggerInstance
+ XXX.advancements.critereon.EnchantmentPredicate
- XXX.advancements.critereon.EnterBlockTrigger
+ XXX.advancements.critereon.EnterBlockTrigger$TriggerInstance
- XXX.advancements.critereon.EntityEquipmentPredicate
+ XXX.advancements.critereon.EntityEquipmentPredicate$Builder
- XXX.advancements.critereon.EntityFlagsPredicate
+ XXX.advancements.critereon.EntityFlagsPredicate$Builder
- XXX.advancements.critereon.EntityHurtPlayerTrigger
+ XXX.advancements.critereon.EntityHurtPlayerTrigger$TriggerInstance
- XXX.advancements.critereon.EntityPredicate
+ XXX.advancements.critereon.EntityPredicate$1
- XXX.advancements.critereon.EntityPredicate$Builder
+ XXX.advancements.critereon.EntityPredicate$Composite
- XXX.advancements.critereon.EntityTypePredicate
+ XXX.advancements.critereon.EntityTypePredicate$1
- XXX.advancements.critereon.EntityTypePredicate$TagPredicate
+ XXX.advancements.critereon.EntityTypePredicate$TypePredicate
- XXX.advancements.critereon.FilledBucketTrigger
+ XXX.advancements.critereon.FilledBucketTrigger$TriggerInstance
- XXX.advancements.critereon.FishingHookPredicate
+ XXX.advancements.critereon.FishingRodHookedTrigger
- XXX.advancements.critereon.FishingRodHookedTrigger$TriggerInstance
+ XXX.advancements.critereon.FluidPredicate
- XXX.advancements.critereon.FluidPredicate$Builder
+ XXX.advancements.critereon.ImpossibleTrigger
- XXX.advancements.critereon.ImpossibleTrigger$TriggerInstance
+ XXX.advancements.critereon.InventoryChangeTrigger
- XXX.advancements.critereon.InventoryChangeTrigger$TriggerInstance
+ XXX.advancements.critereon.ItemDurabilityTrigger
- XXX.advancements.critereon.ItemDurabilityTrigger$TriggerInstance
+ XXX.advancements.critereon.ItemPickedUpByEntityTrigger
- XXX.advancements.critereon.ItemPickedUpByEntityTrigger$TriggerInstance
+ XXX.advancements.critereon.ItemPredicate
- XXX.advancements.critereon.ItemPredicate$Builder
+ XXX.advancements.critereon.ItemUsedOnBlockTrigger
- XXX.advancements.critereon.ItemUsedOnBlockTrigger$TriggerInstance
+ XXX.advancements.critereon.KilledByCrossbowTrigger
- XXX.advancements.critereon.KilledByCrossbowTrigger$TriggerInstance
+ XXX.advancements.critereon.KilledTrigger
- XXX.advancements.critereon.KilledTrigger$TriggerInstance
+ XXX.advancements.critereon.LevitationTrigger
- XXX.advancements.critereon.LevitationTrigger$TriggerInstance
+ XXX.advancements.critereon.LightPredicate
- XXX.advancements.critereon.LightPredicate$1
+ XXX.advancements.critereon.LightPredicate$Builder
- XXX.advancements.critereon.LocationPredicate
+ XXX.advancements.critereon.LocationPredicate$Builder
- XXX.advancements.critereon.LocationTrigger
+ XXX.advancements.critereon.LocationTrigger$TriggerInstance
- XXX.advancements.critereon.LootTableTrigger
+ XXX.advancements.critereon.LootTableTrigger$TriggerInstance
- XXX.advancements.critereon.MinMaxBounds
+ XXX.advancements.critereon.MinMaxBounds$BoundsFactory
- XXX.advancements.critereon.MinMaxBounds$BoundsFromReaderFactory
+ XXX.advancements.critereon.MinMaxBounds$Floats
- XXX.advancements.critereon.MinMaxBounds$Ints
+ XXX.advancements.critereon.MobEffectsPredicate
- XXX.advancements.critereon.MobEffectsPredicate$MobEffectInstancePredicate
+ XXX.advancements.critereon.NbtPredicate
- XXX.advancements.critereon.NetherTravelTrigger
+ XXX.advancements.critereon.NetherTravelTrigger$TriggerInstance
+ XXX.advancements.critereon.package-info
- XXX.advancements.critereon.PlacedBlockTrigger
+ XXX.advancements.critereon.PlacedBlockTrigger$TriggerInstance
- XXX.advancements.critereon.PlayerHurtEntityTrigger
+ XXX.advancements.critereon.PlayerHurtEntityTrigger$TriggerInstance
- XXX.advancements.critereon.PlayerPredicate
+ XXX.advancements.critereon.PlayerPredicate$1
- XXX.advancements.critereon.PlayerPredicate$AdvancementCriterionsPredicate
+ XXX.advancements.critereon.PlayerPredicate$AdvancementDonePredicate
- XXX.advancements.critereon.PlayerPredicate$AdvancementPredicate
+ XXX.advancements.critereon.PlayerPredicate$Builder
- XXX.advancements.critereon.RecipeUnlockedTrigger
+ XXX.advancements.critereon.RecipeUnlockedTrigger$TriggerInstance
- XXX.advancements.critereon.SerializationContext
+ XXX.advancements.critereon.ShotCrossbowTrigger
- XXX.advancements.critereon.ShotCrossbowTrigger$TriggerInstance
+ XXX.advancements.critereon.SimpleCriterionTrigger
- XXX.advancements.critereon.SlideDownBlockTrigger
+ XXX.advancements.critereon.SlideDownBlockTrigger$TriggerInstance
- XXX.advancements.critereon.StatePropertiesPredicate
+ XXX.advancements.critereon.StatePropertiesPredicate$1
- XXX.advancements.critereon.StatePropertiesPredicate$Builder
+ XXX.advancements.critereon.StatePropertiesPredicate$ExactPropertyMatcher
- XXX.advancements.critereon.StatePropertiesPredicate$PropertyMatcher
+ XXX.advancements.critereon.StatePropertiesPredicate$RangedPropertyMatcher
- XXX.advancements.critereon.SummonedEntityTrigger
+ XXX.advancements.critereon.SummonedEntityTrigger$TriggerInstance
- XXX.advancements.critereon.TameAnimalTrigger
+ XXX.advancements.critereon.TameAnimalTrigger$TriggerInstance
- XXX.advancements.critereon.TargetBlockTrigger
+ XXX.advancements.critereon.TargetBlockTrigger$TriggerInstance
- XXX.advancements.critereon.TickTrigger
+ XXX.advancements.critereon.TickTrigger$TriggerInstance
- XXX.advancements.critereon.TradeTrigger
+ XXX.advancements.critereon.TradeTrigger$TriggerInstance
- XXX.advancements.critereon.UsedEnderEyeTrigger
+ XXX.advancements.critereon.UsedEnderEyeTrigger$TriggerInstance
- XXX.advancements.critereon.UsedTotemTrigger
+ XXX.advancements.critereon.UsedTotemTrigger$TriggerInstance
- XXX.advancements.critereon.WrappedMinMaxBounds
- XXX.ai.behavior.AnimalMakeLove
+ XXX.ai.behavior.AssignProfessionFromJobSite
- XXX.ai.behavior.BabyFollowAdult
+ XXX.ai.behavior.BackUpIfTooClose
- XXX.ai.behavior.BecomePassiveIfMemoryPresent
+ XXX.ai.behavior.Behavior
- XXX.ai.behavior.Behavior$Status
+ XXX.ai.behavior.BehaviorUtils
- XXX.ai.behavior.BlockPosTracker
+ XXX.ai.behavior.CelebrateVillagersSurvivedRaid
- XXX.ai.behavior.CopyMemoryWithExpiry
+ XXX.ai.behavior.CrossbowAttack
- XXX.ai.behavior.CrossbowAttack$CrossbowState
+ XXX.ai.behavior.DismountOrSkipMounting
- XXX.ai.behavior.DoNothing
+ XXX.ai.behavior.EntityTracker
- XXX.ai.behavior.EraseMemoryIf
+ XXX.ai.behavior.GateBehavior
- XXX.ai.behavior.GateBehavior$1
+ XXX.ai.behavior.GateBehavior$OrderPolicy
- XXX.ai.behavior.GateBehavior$RunningPolicy
+ XXX.ai.behavior.GateBehavior$RunningPolicy$1
- XXX.ai.behavior.GateBehavior$RunningPolicy$2
+ XXX.ai.behavior.GiveGiftToHero
- XXX.ai.behavior.GoOutsideToCelebrate
+ XXX.ai.behavior.GoToCelebrateLocation
- XXX.ai.behavior.GoToClosestVillage
+ XXX.ai.behavior.GoToPotentialJobSite
- XXX.ai.behavior.GoToWantedItem
+ XXX.ai.behavior.HarvestFarmland
- XXX.ai.behavior.InsideBrownianWalk
+ XXX.ai.behavior.InteractWith
- XXX.ai.behavior.InteractWithDoor
+ XXX.ai.behavior.JumpOnBed
- XXX.ai.behavior.LocateHidingPlace
+ XXX.ai.behavior.LocateHidingPlaceDuringRaid
- XXX.ai.behavior.LookAndFollowTradingPlayerSink
+ XXX.ai.behavior.LookAtTargetSink
- XXX.ai.behavior.MeleeAttack
+ XXX.ai.behavior.Mount
- XXX.ai.behavior.MoveToSkySeeingSpot
+ XXX.ai.behavior.MoveToTargetSink
+ XXX.ai.behavior.package-info
- XXX.ai.behavior.PlayTagWithOtherKids
+ XXX.ai.behavior.PoiCompetitorScan
- XXX.ai.behavior.PositionTracker
+ XXX.ai.behavior.RandomStroll
- XXX.ai.behavior.ReactToBell
+ XXX.ai.behavior.ResetProfession
- XXX.ai.behavior.ResetRaidStatus
+ XXX.ai.behavior.RingBell
- XXX.ai.behavior.RunIf
+ XXX.ai.behavior.RunOne
- XXX.ai.behavior.RunSometimes
+ XXX.ai.behavior.SetClosestHomeAsWalkTarget
- XXX.ai.behavior.SetEntityLookTarget
+ XXX.ai.behavior.SetHiddenState
- XXX.ai.behavior.SetLookAndInteract
+ XXX.ai.behavior.SetRaidStatus
- XXX.ai.behavior.SetWalkTargetAwayFrom
+ XXX.ai.behavior.SetWalkTargetFromAttackTargetIfTargetOutOfReach
- XXX.ai.behavior.SetWalkTargetFromBlockMemory
+ XXX.ai.behavior.SetWalkTargetFromLookTarget
- XXX.ai.behavior.ShowTradesToPlayer
+ XXX.ai.behavior.SleepInBed
- XXX.ai.behavior.SocializeAtBell
+ XXX.ai.behavior.StartAttacking
- XXX.ai.behavior.StartCelebratingIfTargetDead
+ XXX.ai.behavior.StopAttackingIfTargetInvalid
- XXX.ai.behavior.StopBeingAngryIfTargetDead
+ XXX.ai.behavior.StrollAroundPoi
- XXX.ai.behavior.StrollToPoi
+ XXX.ai.behavior.StrollToPoiList
- XXX.ai.behavior.Swim
+ XXX.ai.behavior.TradeWithVillager
- XXX.ai.behavior.UpdateActivityFromSchedule
+ XXX.ai.behavior.UseBonemeal
- XXX.ai.behavior.ValidateNearbyPoi
+ XXX.ai.behavior.VictoryStroll
- XXX.ai.behavior.VillageBoundRandomStroll
+ XXX.ai.behavior.VillagerCalmDown
- XXX.ai.behavior.VillagerGoalPackages
+ XXX.ai.behavior.VillagerMakeLove
- XXX.ai.behavior.VillagerPanicTrigger
+ XXX.ai.behavior.WakeUp
- XXX.ai.behavior.WeightedList
+ XXX.ai.behavior.WeightedList$1
- XXX.ai.behavior.WeightedList$WeightedEntry
+ XXX.ai.behavior.WeightedList$WeightedEntry$1
- XXX.ai.behavior.WorkAtComposter
+ XXX.ai.behavior.WorkAtPoi
- XXX.ai.behavior.YieldJobSite
- XXX.ai.control.BodyRotationControl
+ XXX.ai.control.Control
- XXX.ai.control.DolphinLookControl
+ XXX.ai.control.FlyingMoveControl
- XXX.ai.control.JumpControl
+ XXX.ai.control.LookControl
- XXX.ai.control.MoveControl
+ XXX.ai.control.MoveControl$Operation
- XXX.ai.control.package-info
+ XXX.ai.goal.AvoidEntityGoal
- XXX.ai.goal.BegGoal
+ XXX.ai.goal.BoatGoals
- XXX.ai.goal.BreakDoorGoal
+ XXX.ai.goal.BreathAirGoal
- XXX.ai.goal.BreedGoal
+ XXX.ai.goal.CatLieOnBedGoal
- XXX.ai.goal.CatSitOnBlockGoal
+ XXX.ai.goal.DolphinJumpGoal
- XXX.ai.goal.DoorInteractGoal
+ XXX.ai.goal.EatBlockGoal
- XXX.ai.goal.FleeSunGoal
+ XXX.ai.goal.FloatGoal
- XXX.ai.goal.FollowBoatGoal
+ XXX.ai.goal.FollowFlockLeaderGoal
- XXX.ai.goal.FollowMobGoal
+ XXX.ai.goal.FollowOwnerGoal
- XXX.ai.goal.FollowParentGoal
+ XXX.ai.goal.Goal
- XXX.ai.goal.Goal$Flag
+ XXX.ai.goal.GoalSelector
- XXX.ai.goal.GoalSelector$1
+ XXX.ai.goal.GoalSelector$2
- XXX.ai.goal.GolemRandomStrollInVillageGoal
+ XXX.ai.goal.InteractGoal
- XXX.ai.goal.JumpGoal
+ XXX.ai.goal.LandOnOwnersShoulderGoal
- XXX.ai.goal.LeapAtTargetGoal
+ XXX.ai.goal.LlamaFollowCaravanGoal
- XXX.ai.goal.LookAtPlayerGoal
+ XXX.ai.goal.LookAtTradingPlayerGoal
- XXX.ai.goal.MeleeAttackGoal
+ XXX.ai.goal.MoveBackToVillageGoal
- XXX.ai.goal.MoveIndoorsGoal
+ XXX.ai.goal.MoveThroughVillageGoal
- XXX.ai.goal.MoveToBlockGoal
+ XXX.ai.goal.MoveTowardsRestrictionGoal
- XXX.ai.goal.MoveTowardsTargetGoal
+ XXX.ai.goal.OcelotAttackGoal
- XXX.ai.goal.OfferFlowerGoal
+ XXX.ai.goal.OpenDoorGoal
+ XXX.ai.goal.package-info
- XXX.ai.goal.PanicGoal
+ XXX.ai.goal.PathfindToRaidGoal
- XXX.ai.goal.PlayGoal
+ XXX.ai.goal.RandomLookAroundGoal
- XXX.ai.goal.RandomStrollGoal
+ XXX.ai.goal.RandomSwimmingGoal
- XXX.ai.goal.RangedAttackGoal
+ XXX.ai.goal.RangedBowAttackGoal
- XXX.ai.goal.RangedCrossbowAttackGoal
+ XXX.ai.goal.RangedCrossbowAttackGoal$CrossbowState
- XXX.ai.goal.RemoveBlockGoal
+ XXX.ai.goal.RestrictSunGoal
- XXX.ai.goal.RunAroundLikeCrazyGoal
+ XXX.ai.goal.SitWhenOrderedToGoal
- XXX.ai.goal.StrollThroughVillageGoal
+ XXX.ai.goal.SwellGoal
- XXX.ai.goal.TakeFlowerGoal
+ XXX.ai.goal.TemptGoal
- XXX.ai.goal.TradeWithPlayerGoal
+ XXX.ai.goal.TryFindWaterGoal
- XXX.ai.goal.UseItemGoal
+ XXX.ai.goal.WaterAvoidingRandomFlyingGoal
- XXX.ai.goal.WaterAvoidingRandomStrollGoal
+ XXX.ai.goal.WrappedGoal
- XXX.ai.goal.ZombieAttackGoal
+ XXX.blaze3d.platform.GlStateManager$ClearState
- XXX.blaze3d.platform.GlStateManager$Color
+ XXX.blaze3d.platform.GlStateManager$ColorLogicState
- XXX.blaze3d.platform.GlStateManager$ColorMask
+ XXX.blaze3d.platform.GlStateManager$ColorMaterialState
- XXX.blaze3d.platform.GlStateManager$CullState
+ XXX.blaze3d.platform.GlStateManager$DepthState
- XXX.blaze3d.platform.GlStateManager$DestFactor
+ XXX.blaze3d.platform.GlStateManager$FboBlitMode
- XXX.blaze3d.platform.GlStateManager$FboMode
+ XXX.blaze3d.platform.GlStateManager$FogMode
- XXX.blaze3d.platform.GlStateManager$FogState
+ XXX.blaze3d.platform.GlStateManager$LogicOp
- XXX.blaze3d.platform.GlStateManager$PolygonOffsetState
+ XXX.blaze3d.platform.GlStateManager$SourceFactor
- XXX.blaze3d.platform.GlStateManager$StencilFunc
+ XXX.blaze3d.platform.GlStateManager$StencilState
- XXX.blaze3d.platform.GlStateManager$TexGen
+ XXX.blaze3d.platform.GlStateManager$TexGenCoord
- XXX.blaze3d.platform.GlStateManager$TexGenState
+ XXX.blaze3d.platform.GlStateManager$TextureState
- XXX.blaze3d.platform.GlStateManager$Viewport
+ XXX.blaze3d.platform.GlUtil
- XXX.blaze3d.platform.InputConstants
+ XXX.blaze3d.platform.InputConstants$1
- XXX.blaze3d.platform.InputConstants$Key
+ XXX.blaze3d.platform.InputConstants$Type
- XXX.blaze3d.platform.Lighting
+ XXX.blaze3d.platform.MemoryTracker
- XXX.blaze3d.platform.Monitor
+ XXX.blaze3d.platform.MonitorCreator
- XXX.blaze3d.platform.NativeImage
+ XXX.blaze3d.platform.NativeImage$1
- XXX.blaze3d.platform.NativeImage$Format
+ XXX.blaze3d.platform.NativeImage$InternalGlFormat
- XXX.blaze3d.platform.NativeImage$WriteCallback
+ XXX.blaze3d.platform.PngInfo
- XXX.blaze3d.platform.PngInfo$1
+ XXX.blaze3d.platform.PngInfo$StbReader
- XXX.blaze3d.platform.PngInfo$StbReaderBufferedChannel
+ XXX.blaze3d.platform.PngInfo$StbReaderSeekableByteChannel
- XXX.blaze3d.platform.ScreenManager
+ XXX.blaze3d.platform.SnooperAccess
- XXX.blaze3d.platform.TextureUtil
+ XXX.blaze3d.platform.VideoMode
- XXX.blaze3d.platform.Window
+ XXX.blaze3d.platform.Window$1
- XXX.blaze3d.platform.Window$WindowInitFailed
+ XXX.blaze3d.platform.WindowEventHandler
- XXX.blaze3d.shaders.AbstractUniform
+ XXX.blaze3d.shaders.BlendMode
- XXX.blaze3d.shaders.Effect
+ XXX.blaze3d.shaders.Program
- XXX.blaze3d.shaders.Program$Type
+ XXX.blaze3d.shaders.ProgramManager
- XXX.blaze3d.shaders.Uniform
+ XXX.blaze3d.systems.RenderSystem
- XXX.blaze3d.vertex.BreakingTextureGenerator
+ XXX.blaze3d.vertex.BufferBuilder
- XXX.blaze3d.vertex.BufferBuilder$1
+ XXX.blaze3d.vertex.BufferBuilder$DrawState
- XXX.blaze3d.vertex.BufferBuilder$State
+ XXX.blaze3d.vertex.BufferUploader
- XXX.blaze3d.vertex.BufferVertexConsumer
- XXX.blaze3d.vertex.DefaultedVertexConsumer
+ XXX.blaze3d.vertex.DefaultVertexFormat
+ XXX.blaze3d.vertex.PoseStack
- XXX.blaze3d.vertex.PoseStack$1
+ XXX.blaze3d.vertex.PoseStack$Pose
- XXX.blaze3d.vertex.Tesselator
+ XXX.blaze3d.vertex.VertexBuffer
- XXX.blaze3d.vertex.VertexConsumer
+ XXX.blaze3d.vertex.VertexFormat
- XXX.blaze3d.vertex.VertexFormatElement
+ XXX.blaze3d.vertex.VertexFormatElement$Type
- XXX.blaze3d.vertex.VertexFormatElement$Usage
+ XXX.blaze3d.vertex.VertexFormatElement$Usage$SetupState
- XXX.blaze3d.vertex.VertexMultiConsumer
+ XXX.blaze3d.vertex.VertexMultiConsumer$Double
- XXX.block.model.BakedQuad
+ XXX.block.model.BlockElement
- XXX.block.model.BlockElement$1
+ XXX.block.model.BlockElement$Deserializer
- XXX.block.model.BlockElementFace
+ XXX.block.model.BlockElementFace$Deserializer
- XXX.block.model.BlockElementRotation
+ XXX.block.model.BlockFaceUV
- XXX.block.model.BlockFaceUV$Deserializer
+ XXX.block.model.BlockModel
- XXX.block.model.BlockModel$Deserializer
+ XXX.block.model.BlockModel$GuiLight
- XXX.block.model.BlockModel$LoopException
+ XXX.block.model.BlockModelDefinition
- XXX.block.model.BlockModelDefinition$Context
+ XXX.block.model.BlockModelDefinition$Deserializer
- XXX.block.model.BlockModelDefinition$MissingVariantException
+ XXX.block.model.FaceBakery
- XXX.block.model.FaceBakery$1
+ XXX.block.model.ItemModelGenerator
- XXX.block.model.ItemModelGenerator$1
+ XXX.block.model.ItemModelGenerator$Span
- XXX.block.model.ItemModelGenerator$SpanFacing
+ XXX.block.model.ItemOverride
- XXX.block.model.ItemOverride$Deserializer
+ XXX.block.model.ItemOverrides
- XXX.block.model.ItemTransform
+ XXX.block.model.ItemTransform$Deserializer
- XXX.block.model.ItemTransforms
+ XXX.block.model.ItemTransforms$1
- XXX.block.model.ItemTransforms$Deserializer
+ XXX.block.model.ItemTransforms$TransformType
- XXX.block.model.MultiVariant
+ XXX.block.model.MultiVariant$Deserializer
+ XXX.block.model.package-info
- XXX.block.model.Variant
+ XXX.block.model.Variant$Deserializer
+ XXX.block.statemap.package-info
+ XXX.client.gui.Font
- XXX.client.gui.Font$StringRenderOutput
+ XXX.client.gui.Gui
- XXX.client.gui.GuiComponent
+ XXX.client.gui.MapRenderer
- XXX.client.gui.MapRenderer$1
+ XXX.client.gui.MapRenderer$MapInstance
- XXX.client.gui.package-info
- XXX.client.renderer.EffectInstance
+ XXX.client.renderer.FaceInfo
- XXX.client.renderer.FaceInfo$1
+ XXX.client.renderer.FaceInfo$Constants
- XXX.client.renderer.FaceInfo$VertexInfo
+ XXX.client.renderer.FogRenderer
- XXX.client.renderer.FogRenderer$FogMode
+ XXX.client.renderer.GameRenderer
- XXX.client.renderer.ItemBlockRenderTypes
+ XXX.client.renderer.ItemInHandRenderer
- XXX.client.renderer.ItemInHandRenderer$1
+ XXX.client.renderer.ItemModelShaper
- XXX.client.renderer.LevelRenderer
+ XXX.client.renderer.LevelRenderer$1
- XXX.client.renderer.LevelRenderer$RenderChunkInfo
+ XXX.client.renderer.LevelRenderer$TranparencyShaderException
- XXX.client.renderer.LightTexture
+ XXX.client.renderer.MultiBufferSource
- XXX.client.renderer.MultiBufferSource$BufferSource
+ XXX.client.renderer.OutlineBufferSource
- XXX.client.renderer.OutlineBufferSource$1
+ XXX.client.renderer.OutlineBufferSource$EntityOutlineGenerator
- XXX.client.renderer.PanoramaRenderer
+ XXX.client.renderer.PostChain
- XXX.client.renderer.PostPass
+ XXX.client.renderer.Rect2i
- XXX.client.renderer.RenderBuffers
+ XXX.client.renderer.RenderStateShard
- XXX.client.renderer.RenderStateShard$AlphaStateShard
+ XXX.client.renderer.RenderStateShard$BooleanStateShard
- XXX.client.renderer.RenderStateShard$CullStateShard
+ XXX.client.renderer.RenderStateShard$DepthTestStateShard
- XXX.client.renderer.RenderStateShard$DiffuseLightingStateShard
+ XXX.client.renderer.RenderStateShard$FogStateShard
- XXX.client.renderer.RenderStateShard$LayeringStateShard
+ XXX.client.renderer.RenderStateShard$LightmapStateShard
- XXX.client.renderer.RenderStateShard$LineStateShard
+ XXX.client.renderer.RenderStateShard$OffsetTexturingStateShard
- XXX.client.renderer.RenderStateShard$OutputStateShard
+ XXX.client.renderer.RenderStateShard$OverlayStateShard
- XXX.client.renderer.RenderStateShard$PortalTexturingStateShard
+ XXX.client.renderer.RenderStateShard$ShadeModelStateShard
- XXX.client.renderer.RenderStateShard$TextureStateShard
+ XXX.client.renderer.RenderStateShard$TexturingStateShard
- XXX.client.renderer.RenderStateShard$TransparencyStateShard
+ XXX.client.renderer.RenderStateShard$WriteMaskStateShard
- XXX.client.renderer.RenderType
+ XXX.client.renderer.RenderType$1
- XXX.client.renderer.RenderType$CompositeRenderType
+ XXX.client.renderer.RenderType$CompositeRenderType$EqualsStrategy
- XXX.client.renderer.RenderType$CompositeState
+ XXX.client.renderer.RenderType$CompositeState$CompositeStateBuilder
- XXX.client.renderer.RenderType$OutlineProperty
+ XXX.client.renderer.RunningTrimmedMean
- XXX.client.renderer.ScreenEffectRenderer
+ XXX.client.renderer.Sheets
- XXX.client.renderer.Sheets$1
+ XXX.client.renderer.SpriteCoordinateExpander
- XXX.client.renderer.ViewArea
+ XXX.client.renderer.VirtualScreen
- XXX.color.block.BlockColor
+ XXX.color.block.BlockColors
- XXX.color.block.BlockTintCache
+ XXX.color.block.BlockTintCache$1
- XXX.color.block.BlockTintCache$LatestCacheInfo
+ XXX.color.block.package-info
- XXX.color.item.ItemColor
+ XXX.color.item.ItemColors
- XXX.color.item.package-info
- XXX.commands.data.BlockDataAccessor
+ XXX.commands.data.BlockDataAccessor$1
- XXX.commands.data.DataAccessor
+ XXX.commands.data.DataCommands
- XXX.commands.data.DataCommands$DataManipulator
+ XXX.commands.data.DataCommands$DataManipulatorDecorator
- XXX.commands.data.DataCommands$DataProvider
+ XXX.commands.data.EntityDataAccessor
- XXX.commands.data.EntityDataAccessor$1
+ XXX.commands.data.package-info
+ XXX.commands.data.StorageDataAccessor
- XXX.commands.data.StorageDataAccessor$1
- XXX.components.events.AbstractContainerEventHandler
+ XXX.components.events.ContainerEventHandler
- XXX.components.events.GuiEventListener
+ XXX.components.events.package-info
- XXX.components.spectator.package-info
+ XXX.components.spectator.SpectatorGui
+ XXX.components.toasts.AdvancementToast
- XXX.components.toasts.package-info
- XXX.components.toasts.RecipeToast
+ XXX.components.toasts.SystemToast
- XXX.components.toasts.SystemToast$SystemToastIds
+ XXX.components.toasts.Toast
- XXX.components.toasts.Toast$Visibility
+ XXX.components.toasts.ToastComponent
- XXX.components.toasts.ToastComponent$1
+ XXX.components.toasts.ToastComponent$ToastInstance
- XXX.components.toasts.TutorialToast
+ XXX.components.toasts.TutorialToast$Icons
- XXX.datafix.fixes.AbstractUUIDFix
+ XXX.datafix.fixes.AddNewChoices
- XXX.datafix.fixes.AdvancementsFix
+ XXX.datafix.fixes.AdvancementsRenameFix
- XXX.datafix.fixes.AttributesRename
+ XXX.datafix.fixes.BedBlockEntityInjecter
- XXX.datafix.fixes.BedItemColorFix
+ XXX.datafix.fixes.BeehivePoiRenameFix
- XXX.datafix.fixes.BiomeFix
+ XXX.datafix.fixes.BitStorageAlignFix
- XXX.datafix.fixes.BlockEntityBannerColorFix
+ XXX.datafix.fixes.BlockEntityBlockStateFix
- XXX.datafix.fixes.BlockEntityCustomNameToComponentFix
+ XXX.datafix.fixes.BlockEntityIdFix
- XXX.datafix.fixes.BlockEntityJukeboxFix
+ XXX.datafix.fixes.BlockEntityKeepPacked
- XXX.datafix.fixes.BlockEntityShulkerBoxColorFix
+ XXX.datafix.fixes.BlockEntitySignTextStrictJsonFix
- XXX.datafix.fixes.BlockEntitySignTextStrictJsonFix$1
+ XXX.datafix.fixes.BlockEntityUUIDFix
- XXX.datafix.fixes.BlockNameFlatteningFix
+ XXX.datafix.fixes.BlockRenameFix
- XXX.datafix.fixes.BlockRenameFix$1
+ XXX.datafix.fixes.BlockRenameFixWithJigsaw
- XXX.datafix.fixes.BlockRenameFixWithJigsaw$1
+ XXX.datafix.fixes.BlockStateData
- XXX.datafix.fixes.BlockStateStructureTemplateFix
+ XXX.datafix.fixes.CatTypeFix
- XXX.datafix.fixes.ChunkBiomeFix
+ XXX.datafix.fixes.ChunkLightRemoveFix
- XXX.datafix.fixes.ChunkPalettedStorageFix
+ XXX.datafix.fixes.ChunkPalettedStorageFix$1
- XXX.datafix.fixes.ChunkPalettedStorageFix$DataLayer
+ XXX.datafix.fixes.ChunkPalettedStorageFix$Direction
- XXX.datafix.fixes.ChunkPalettedStorageFix$Direction$Axis
+ XXX.datafix.fixes.ChunkPalettedStorageFix$Direction$AxisDirection
- XXX.datafix.fixes.ChunkPalettedStorageFix$Section
+ XXX.datafix.fixes.ChunkPalettedStorageFix$UpgradeChunk
- XXX.datafix.fixes.ChunkStatusFix
+ XXX.datafix.fixes.ChunkStatusFix2
- XXX.datafix.fixes.ChunkStructuresTemplateRenameFix
+ XXX.datafix.fixes.ChunkToProtochunkFix
- XXX.datafix.fixes.ColorlessShulkerEntityFix
+ XXX.datafix.fixes.DyeItemRenameFix
- XXX.datafix.fixes.EntityArmorStandSilentFix
+ XXX.datafix.fixes.EntityBlockStateFix
- XXX.datafix.fixes.EntityCatSplitFix
+ XXX.datafix.fixes.EntityCodSalmonFix
- XXX.datafix.fixes.EntityCustomNameToComponentFix
+ XXX.datafix.fixes.EntityElderGuardianSplitFix
- XXX.datafix.fixes.EntityEquipmentToArmorAndHandFix
+ XXX.datafix.fixes.EntityHealthFix
- XXX.datafix.fixes.EntityHorseSaddleFix
+ XXX.datafix.fixes.EntityHorseSplitFix
- XXX.datafix.fixes.EntityIdFix
+ XXX.datafix.fixes.EntityItemFrameDirectionFix
- XXX.datafix.fixes.EntityMinecartIdentifiersFix
+ XXX.datafix.fixes.EntityPaintingItemFrameDirectionFix
- XXX.datafix.fixes.EntityPaintingMotiveFix
+ XXX.datafix.fixes.EntityProjectileOwnerFix
- XXX.datafix.fixes.EntityPufferfishRenameFix
+ XXX.datafix.fixes.EntityRavagerRenameFix
- XXX.datafix.fixes.EntityRedundantChanceTagsFix
+ XXX.datafix.fixes.EntityRenameFix
- XXX.datafix.fixes.EntityRidingToPassengersFix
+ XXX.datafix.fixes.EntityShulkerColorFix
- XXX.datafix.fixes.EntityShulkerRotationFix
+ XXX.datafix.fixes.EntitySkeletonSplitFix
- XXX.datafix.fixes.EntityStringUuidFix
+ XXX.datafix.fixes.EntityTheRenameningFix
- XXX.datafix.fixes.EntityTippedArrowFix
+ XXX.datafix.fixes.EntityUUIDFix
- XXX.datafix.fixes.EntityWolfColorFix
+ XXX.datafix.fixes.EntityZombieSplitFix
- XXX.datafix.fixes.EntityZombieVillagerTypeFix
+ XXX.datafix.fixes.EntityZombifiedPiglinRenameFix
- XXX.datafix.fixes.ForcePoiRebuild
+ XXX.datafix.fixes.FurnaceRecipeFix
- XXX.datafix.fixes.GossipUUIDFix
+ XXX.datafix.fixes.HeightmapRenamingFix
- XXX.datafix.fixes.IglooMetadataRemovalFix
+ XXX.datafix.fixes.ItemBannerColorFix
- XXX.datafix.fixes.ItemCustomNameToComponentFix
+ XXX.datafix.fixes.ItemIdFix
- XXX.datafix.fixes.ItemLoreFix
+ XXX.datafix.fixes.ItemPotionFix
- XXX.datafix.fixes.ItemRenameFix
+ XXX.datafix.fixes.ItemRenameFix$1
- XXX.datafix.fixes.ItemShulkerBoxColorFix
+ XXX.datafix.fixes.ItemSpawnEggFix
- XXX.datafix.fixes.ItemStackEnchantmentNamesFix
+ XXX.datafix.fixes.ItemStackMapIdFix
- XXX.datafix.fixes.ItemStackSpawnEggFix
+ XXX.datafix.fixes.ItemStackTheFlatteningFix
- XXX.datafix.fixes.ItemStackUUIDFix
+ XXX.datafix.fixes.ItemWaterPotionFix
- XXX.datafix.fixes.ItemWrittenBookPagesStrictJsonFix
+ XXX.datafix.fixes.JigsawPropertiesFix
- XXX.datafix.fixes.JigsawRotationFix
+ XXX.datafix.fixes.LeavesFix
- XXX.datafix.fixes.LeavesFix$LeavesSection
+ XXX.datafix.fixes.LeavesFix$Section
- XXX.datafix.fixes.LevelDataGeneratorOptionsFix
+ XXX.datafix.fixes.LevelFlatGeneratorInfoFix
- XXX.datafix.fixes.LevelUUIDFix
+ XXX.datafix.fixes.MapIdFix
- XXX.datafix.fixes.MemoryExpiryDataFix
+ XXX.entity.layers.AbstractArmorLayer
- XXX.entity.layers.ArrowLayer
+ XXX.entity.layers.BeeStingerLayer
- XXX.entity.layers.CapeLayer
+ XXX.entity.layers.CarriedBlockLayer
- XXX.entity.layers.CatCollarLayer
+ XXX.entity.layers.CreeperPowerLayer
- XXX.entity.layers.CrossedArmsItemLayer
+ XXX.entity.layers.CustomHeadLayer
- XXX.entity.layers.Deadmau5EarsLayer
+ XXX.entity.layers.DolphinCarryingItemLayer
- XXX.entity.layers.DrownedOuterLayer
+ XXX.entity.layers.ElytraLayer
- XXX.entity.layers.EnderEyesLayer
+ XXX.entity.layers.EnergySwirlLayer
- XXX.entity.layers.EyesLayer
+ XXX.entity.layers.FoxHeldItemLayer
- XXX.entity.layers.HorseArmorLayer
+ XXX.entity.layers.HorseMarkingLayer
- XXX.entity.layers.HumanoidArmorLayer
+ XXX.entity.layers.HumanoidArmorLayer$1
- XXX.entity.layers.IronGolemCrackinessLayer
+ XXX.entity.layers.IronGolemFlowerLayer
- XXX.entity.layers.ItemInHandLayer
+ XXX.entity.layers.LlamaDecorLayer
- XXX.entity.layers.MushroomCowMushroomLayer
+ XXX.entity.layers.PandaHoldsItemLayer
- XXX.entity.layers.ParrotOnShoulderLayer
+ XXX.entity.layers.PhantomEyesLayer
+ XXX.font.glyphs.BakedGlyph
- XXX.font.glyphs.BakedGlyph$Effect
+ XXX.font.glyphs.EmptyGlyph
- XXX.font.glyphs.MissingGlyph
- XXX.font.glyphs.package-info
+ XXX.font.glyphs.WhiteGlyph
- XXX.font.providers.BitmapProvider
+ XXX.font.providers.BitmapProvider$1
- XXX.font.providers.BitmapProvider$Builder
+ XXX.font.providers.BitmapProvider$Glyph
- XXX.font.providers.GlyphProviderBuilder
+ XXX.font.providers.GlyphProviderBuilderType
- XXX.font.providers.LegacyUnicodeBitmapsProvider
+ XXX.font.providers.LegacyUnicodeBitmapsProvider$1
- XXX.font.providers.LegacyUnicodeBitmapsProvider$Builder
+ XXX.font.providers.LegacyUnicodeBitmapsProvider$Glyph
+ XXX.font.providers.package-info
- XXX.font.providers.TrueTypeGlyphProviderBuilder
- XXX.goal.target.DefendVillageTargetGoal
+ XXX.goal.target.HurtByTargetGoal
- XXX.goal.target.NearestAttackableTargetGoal
+ XXX.goal.target.NearestAttackableWitchTargetGoal
- XXX.goal.target.NearestHealableRaiderTargetGoal
+ XXX.goal.target.NonTameRandomTargetGoal
- XXX.goal.target.OwnerHurtByTargetGoal
+ XXX.goal.target.OwnerHurtTargetGoal
- XXX.goal.target.ResetUniversalAngerTargetGoal
- XXX.gui.chat.ChatListener
+ XXX.gui.chat.NarratorChatListener
- XXX.gui.chat.OverlayChatListener
- XXX.gui.chat.package-info
+ XXX.gui.chat.StandardChatListener
+ XXX.gui.components.AbstractButton
- XXX.gui.components.AbstractOptionSliderButton
+ XXX.gui.components.AbstractSelectionList
- XXX.gui.components.AbstractSelectionList$1
+ XXX.gui.components.AbstractSelectionList$Entry
- XXX.gui.components.AbstractSelectionList$TrackedList
+ XXX.gui.components.AbstractSliderButton
- XXX.gui.components.AbstractWidget
+ XXX.gui.components.BossHealthOverlay
- XXX.gui.components.Button
+ XXX.gui.components.Button$OnPress
- XXX.gui.components.Button$OnTooltip
+ XXX.gui.components.ChatComponent
- XXX.gui.components.Checkbox
+ XXX.gui.components.CommandSuggestions
- XXX.gui.components.CommandSuggestions$1
+ XXX.gui.components.CommandSuggestions$SuggestionsList
- XXX.gui.components.ComponentRenderUtils
+ XXX.gui.components.ContainerObjectSelectionList
- XXX.gui.components.ContainerObjectSelectionList$Entry
+ XXX.gui.components.DebugScreenOverlay
- XXX.gui.components.DebugScreenOverlay$1
+ XXX.gui.components.EditBox
- XXX.gui.components.ImageButton
+ XXX.gui.components.LerpingBossEvent
- XXX.gui.components.LerpingBossEvent$1
+ XXX.gui.components.LockIconButton
- XXX.gui.components.LockIconButton$Icon
+ XXX.gui.components.ObjectSelectionList
- XXX.gui.components.ObjectSelectionList$Entry
+ XXX.gui.components.OptionButton
- XXX.gui.components.OptionsList
+ XXX.gui.components.OptionsList$Entry
- XXX.gui.components.package-info
- XXX.gui.components.PlayerTabOverlay
+ XXX.gui.components.PlayerTabOverlay$1
- XXX.gui.components.PlayerTabOverlay$PlayerInfoComparator
+ XXX.gui.components.SliderButton
- XXX.gui.components.StateSwitchingButton
+ XXX.gui.components.SubtitleOverlay
- XXX.gui.components.SubtitleOverlay$Subtitle
+ XXX.gui.components.TickableWidget
- XXX.gui.components.VolumeSlider
+ XXX.gui.components.Widget
+ XXX.gui.font.AllMissingGlyphProvider
- XXX.gui.font.FontManager
+ XXX.gui.font.FontManager$1
- XXX.gui.font.FontSet
+ XXX.gui.font.FontTexture
- XXX.gui.font.FontTexture$1
+ XXX.gui.font.FontTexture$Node
+ XXX.gui.font.package-info
- XXX.gui.font.TextFieldHelper
+ XXX.gui.screens.AccessibilityOptionsScreen
- XXX.gui.screens.AlertScreen
+ XXX.gui.screens.BackupConfirmScreen
- XXX.gui.screens.BackupConfirmScreen$Listener
+ XXX.gui.screens.ChatOptionsScreen
- XXX.gui.screens.ChatScreen
+ XXX.gui.screens.ChatScreen$1
- XXX.gui.screens.ConfirmLinkScreen
+ XXX.gui.screens.ConfirmScreen
- XXX.gui.screens.ConnectScreen
+ XXX.gui.screens.ConnectScreen$1
- XXX.gui.screens.CreateBuffetWorldScreen
+ XXX.gui.screens.CreateBuffetWorldScreen$1
- XXX.gui.screens.CreateBuffetWorldScreen$BiomeList
+ XXX.gui.screens.CreateBuffetWorldScreen$BiomeList$Entry
- XXX.gui.screens.CreateFlatWorldScreen
+ XXX.gui.screens.CreateFlatWorldScreen$1
- XXX.gui.screens.CreateFlatWorldScreen$DetailsList
+ XXX.gui.screens.CreateFlatWorldScreen$DetailsList$Entry
- XXX.gui.screens.DataPackSelectScreen
+ XXX.gui.screens.DataPackSelectScreen$1
+ XXX.gui.screens.RealmsBackupInfoScreen
- XXX.gui.screens.RealmsBackupInfoScreen$BackupInfoList
+ XXX.gui.screens.RealmsBackupInfoScreen$BackupInfoListEntry
- XXX.gui.screens.RealmsBackupScreen
+ XXX.gui.screens.RealmsBackupScreen$1
- XXX.gui.screens.RealmsBackupScreen$BackupObjectSelectionList
+ XXX.gui.screens.RealmsBackupScreen$Entry
- XXX.gui.screens.RealmsBrokenWorldScreen
+ XXX.gui.screens.RealmsClientOutdatedScreen
- XXX.gui.screens.RealmsConfigureWorldScreen
+ XXX.gui.screens.RealmsConfigureWorldScreen$1
- XXX.gui.screens.RealmsConfirmScreen
+ XXX.gui.screens.RealmsCreateRealmScreen
- XXX.gui.screens.RealmsDownloadLatestWorldScreen
+ XXX.gui.screens.RealmsDownloadLatestWorldScreen$DownloadStatus
- XXX.gui.screens.RealmsGenericErrorScreen
+ XXX.gui.screens.RealmsInviteScreen
- XXX.gui.screens.RealmsLongConfirmationScreen
+ XXX.gui.screens.RealmsLongConfirmationScreen$Type
- XXX.gui.screens.RealmsLongRunningMcoTaskScreen
+ XXX.gui.screens.RealmsNotificationsScreen
- XXX.gui.screens.RealmsNotificationsScreen$1
+ XXX.gui.screens.RealmsParentalConsentScreen
- XXX.gui.screens.RealmsPendingInvitesScreen
+ XXX.gui.screens.RealmsPendingInvitesScreen$1
- XXX.gui.screens.RealmsPendingInvitesScreen$2
+ XXX.gui.screens.RealmsPendingInvitesScreen$3
- XXX.gui.screens.RealmsPendingInvitesScreen$Entry
+ XXX.gui.screens.RealmsPendingInvitesScreen$Entry$AcceptRowButton
- XXX.gui.screens.RealmsPendingInvitesScreen$Entry$RejectRowButton
+ XXX.gui.screens.RealmsPendingInvitesScreen$PendingInvitationSelectionList
- XXX.gui.screens.RealmsPlayerScreen
+ XXX.gui.screens.RealmsPlayerScreen$Entry
- XXX.gui.screens.RealmsPlayerScreen$InvitedObjectSelectionList
+ XXX.gui.screens.RealmsResetNormalWorldScreen
- XXX.gui.screens.RealmsResetWorldScreen
+ XXX.gui.screens.RealmsResetWorldScreen$1
- XXX.gui.screens.RealmsResetWorldScreen$2
+ XXX.gui.screens.RealmsResetWorldScreen$FrameButton
- XXX.gui.screens.RealmsResetWorldScreen$ResetType
+ XXX.gui.screens.RealmsResetWorldScreen$ResetWorldInfo
- XXX.gui.screens.RealmsScreenWithCallback
+ XXX.gui.screens.RealmsSelectFileToUploadScreen
- XXX.gui.screens.RealmsSelectFileToUploadScreen$Entry
+ XXX.gui.screens.RealmsSelectFileToUploadScreen$WorldSelectionList
- XXX.gui.screens.RealmsSelectWorldTemplateScreen
+ XXX.gui.screens.RealmsSelectWorldTemplateScreen$1
- XXX.gui.screens.RealmsSelectWorldTemplateScreen$Entry
+ XXX.gui.screens.RealmsSelectWorldTemplateScreen$WorldTemplateObjectSelectionList
- XXX.gui.screens.RealmsSettingsScreen
+ XXX.gui.screens.RealmsSlotOptionsScreen
- XXX.gui.screens.RealmsSlotOptionsScreen$SettingsSlider
+ XXX.gui.screens.RealmsSubscriptionInfoScreen
- XXX.gui.screens.RealmsSubscriptionInfoScreen$1
+ XXX.gui.screens.RealmsTermsScreen
- XXX.gui.screens.RealmsUploadScreen
+ XXX.gui.screens.UploadResult
- XXX.gui.screens.UploadResult$1
+ XXX.gui.screens.UploadResult$Builder
- XXX.layer.traits.AreaTransformer0
+ XXX.layer.traits.AreaTransformer1
- XXX.layer.traits.AreaTransformer2
+ XXX.layer.traits.BishopTransformer
- XXX.layer.traits.C0Transformer
+ XXX.layer.traits.C1Transformer
- XXX.layer.traits.CastleTransformer
+ XXX.layer.traits.DimensionOffset0Transformer
- XXX.layer.traits.DimensionOffset1Transformer
+ XXX.layer.traits.DimensionTransformer
+ XXX.layer.traits.package-info
- XXX.layer.traits.PixelTransformer
- XXX.level.lighting.BlockLightEngine
+ XXX.level.lighting.BlockLightSectionStorage
- XXX.level.lighting.BlockLightSectionStorage$BlockDataLayerStorageMap
+ XXX.level.lighting.DataLayerStorageMap
- XXX.level.lighting.DynamicGraphMinFixedPoint
+ XXX.level.lighting.DynamicGraphMinFixedPoint$1
- XXX.level.lighting.DynamicGraphMinFixedPoint$2
+ XXX.level.lighting.FlatDataLayer
- XXX.level.lighting.LayerLightEngine
+ XXX.level.lighting.LayerLightEventListener
- XXX.level.lighting.LayerLightEventListener$DummyLightLayerEventListener
+ XXX.level.lighting.LayerLightSectionStorage
- XXX.level.lighting.LayerLightSectionStorage$1
+ XXX.level.lighting.LevelLightEngine
- XXX.level.lighting.LightEventListener
+ XXX.level.lighting.package-info
+ XXX.level.lighting.SkyLightEngine
- XXX.level.lighting.SkyLightSectionStorage
+ XXX.level.lighting.SkyLightSectionStorage$1
- XXX.level.lighting.SkyLightSectionStorage$SkyDataLayerStorageMap
+ XXX.level.lighting.SpatialLongSet
- XXX.level.lighting.SpatialLongSet$InternalMap
- XXX.level.material.EmptyFluid
+ XXX.level.material.FlowingFluid
- XXX.level.material.FlowingFluid$1
+ XXX.level.material.Fluid
+ XXX.level.material.Fluids
- XXX.level.material.FluidState
- XXX.level.material.LavaFluid
+ XXX.level.material.LavaFluid$Flowing
- XXX.level.material.LavaFluid$Source
+ XXX.level.material.Material
- XXX.level.material.Material$Builder
+ XXX.level.material.MaterialColor
- XXX.level.material.package-info
- XXX.level.material.PushReaction
+ XXX.level.material.WaterFluid
- XXX.level.material.WaterFluid$Flowing
+ XXX.level.material.WaterFluid$Source
+ XXX.level.pathfinder.BinaryHeap
- XXX.level.pathfinder.BlockPathTypes
+ XXX.level.pathfinder.FlyNodeEvaluator
- XXX.level.pathfinder.Node
+ XXX.level.pathfinder.NodeEvaluator
+ XXX.level.pathfinder.package-info
- XXX.level.pathfinder.Path
+ XXX.level.pathfinder.PathComputationType
- XXX.level.pathfinder.PathFinder
+ XXX.level.pathfinder.SwimNodeEvaluator
- XXX.level.pathfinder.Target
+ XXX.level.pathfinder.TurtleNodeEvaluator
- XXX.level.pathfinder.WalkNodeEvaluator
- XXX.level.progress.ChunkProgressListener
+ XXX.level.progress.ChunkProgressListenerFactory
- XXX.level.progress.LoggerChunkProgressListener
+ XXX.level.progress.package-info
+ XXX.level.progress.ProcessorChunkProgressListener
- XXX.level.progress.StoringChunkProgressListener
+ XXX.level.redstone.package-info
- XXX.level.redstone.Redstone
+ XXX.level.saveddata.package-info
- XXX.level.saveddata.SaveDataDirtyRunnable
+ XXX.level.saveddata.SavedData
- XXX.level.storage.CommandStorage
+ XXX.level.storage.CommandStorage$Container
- XXX.level.storage.DerivedLevelData
+ XXX.level.storage.DimensionDataStorage
- XXX.level.storage.LevelData
+ XXX.level.storage.LevelResource
- XXX.level.storage.LevelStorageException
+ XXX.level.storage.LevelStorageSource
- XXX.level.storage.LevelStorageSource$LevelStorageAccess
+ XXX.level.storage.LevelStorageSource$LevelStorageAccess$1
- XXX.level.storage.LevelStorageSource$LevelStorageAccess$2
+ XXX.level.storage.LevelSummary
- XXX.level.storage.LevelVersion
+ XXX.level.storage.McRegionUpgrader
+ XXX.level.storage.package-info
- XXX.level.storage.PlayerDataStorage
+ XXX.level.storage.PrimaryLevelData
- XXX.level.storage.ServerLevelData
+ XXX.level.storage.WorldData
- XXX.level.storage.WritableLevelData
+ XXX.level.timers.FunctionCallback
- XXX.level.timers.FunctionCallback$Serializer
+ XXX.level.timers.FunctionTagCallback
- XXX.level.timers.FunctionTagCallback$Serializer
+ XXX.level.timers.package-info
+ XXX.level.timers.TimerCallback
- XXX.level.timers.TimerCallback$Serializer
+ XXX.level.timers.TimerCallbacks
- XXX.level.timers.TimerQueue
+ XXX.level.timers.TimerQueue$1
- XXX.level.timers.TimerQueue$Event
- XXX.levelgen.surfacebuilders.BadlandsSurfaceBuilder
+ XXX.levelgen.surfacebuilders.BasaltDeltasSurfaceBuilder
- XXX.levelgen.surfacebuilders.ConfiguredSurfaceBuilder
+ XXX.levelgen.surfacebuilders.DefaultSurfaceBuilder
- XXX.levelgen.surfacebuilders.ErodedBadlandsSurfaceBuilder
+ XXX.levelgen.surfacebuilders.FrozenOceanSurfaceBuilder
- XXX.levelgen.surfacebuilders.GiantTreeTaigaSurfaceBuilder
+ XXX.levelgen.surfacebuilders.GravellyMountainSurfaceBuilder
- XXX.levelgen.surfacebuilders.MountainSurfaceBuilder
+ XXX.levelgen.surfacebuilders.NetherCappedSurfaceBuilder
- XXX.levelgen.surfacebuilders.NetherForestSurfaceBuilder
+ XXX.levelgen.surfacebuilders.NetherSurfaceBuilder
- XXX.levelgen.surfacebuilders.NopeSurfaceBuilder
- XXX.levelgen.surfacebuilders.package-info
+ XXX.levelgen.surfacebuilders.ShatteredSavanaSurfaceBuilder
- XXX.levelgen.surfacebuilders.SoulSandValleySurfaceBuilder
+ XXX.levelgen.surfacebuilders.SurfaceBuilder
- XXX.levelgen.surfacebuilders.SurfaceBuilderBaseConfiguration
+ XXX.levelgen.surfacebuilders.SurfaceBuilderConfiguration
- XXX.levelgen.surfacebuilders.SwampSurfaceBuilder
+ XXX.levelgen.surfacebuilders.WoodedBadlandsSurfaceBuilder
+ XXX.levelgen.synth.ImprovedNoise
- XXX.levelgen.synth.NormalNoise
+ XXX.levelgen.synth.package-info
+ XXX.levelgen.synth.PerlinNoise
- XXX.levelgen.synth.PerlinSimplexNoise
+ XXX.levelgen.synth.SimplexNoise
- XXX.levelgen.synth.SurfaceNoise
+ XXX.loot.entries.AlternativesEntry
- XXX.loot.entries.AlternativesEntry$Builder
+ XXX.loot.entries.ComposableEntryContainer
- XXX.loot.entries.CompositeEntryBase
+ XXX.loot.entries.CompositeEntryBase$1
- XXX.loot.entries.CompositeEntryBase$CompositeEntryConstructor
+ XXX.loot.entries.DynamicLoot
- XXX.loot.entries.DynamicLoot$1
+ XXX.loot.entries.DynamicLoot$Serializer
- XXX.loot.entries.EmptyLootItem
+ XXX.loot.entries.EmptyLootItem$1
- XXX.loot.entries.EmptyLootItem$Serializer
+ XXX.loot.entries.EntryGroup
- XXX.loot.entries.EntryGroup$Builder
+ XXX.loot.entries.LootItem
- XXX.loot.entries.LootItem$1
+ XXX.loot.entries.LootItem$Serializer
- XXX.loot.entries.LootPoolEntries
+ XXX.loot.entries.LootPoolEntry
- XXX.loot.entries.LootPoolEntryContainer
+ XXX.loot.entries.LootPoolEntryContainer$Builder
- XXX.loot.entries.LootPoolEntryContainer$Serializer
+ XXX.loot.entries.LootPoolEntryType
- XXX.loot.entries.LootPoolSingletonContainer
+ XXX.loot.entries.LootPoolSingletonContainer$1
- XXX.loot.entries.LootPoolSingletonContainer$Builder
+ XXX.loot.entries.LootPoolSingletonContainer$DummyBuilder
- XXX.loot.entries.LootPoolSingletonContainer$EntryBase
+ XXX.loot.entries.LootPoolSingletonContainer$EntryConstructor
- XXX.loot.entries.LootPoolSingletonContainer$Serializer
+ XXX.loot.entries.LootTableReference
- XXX.loot.entries.LootTableReference$1
+ XXX.loot.entries.LootTableReference$Serializer
+ XXX.loot.entries.package-info
- XXX.loot.entries.SequentialEntry
+ XXX.loot.entries.SequentialEntry$Builder
- XXX.loot.entries.TagEntry
+ XXX.loot.entries.TagEntry$1
- XXX.loot.entries.TagEntry$Serializer
- XXX.loot.functions.ApplyBonusCount
+ XXX.loot.functions.ApplyBonusCount$1
- XXX.loot.functions.ApplyBonusCount$BinomialWithBonusCount
+ XXX.loot.functions.ApplyBonusCount$Formula
- XXX.loot.functions.ApplyBonusCount$FormulaDeserializer
+ XXX.loot.functions.ApplyBonusCount$OreDrops
- XXX.loot.functions.ApplyBonusCount$Serializer
+ XXX.loot.functions.ApplyBonusCount$UniformBonusCount
- XXX.loot.functions.ApplyExplosionDecay
+ XXX.loot.functions.ApplyExplosionDecay$1
- XXX.loot.functions.ApplyExplosionDecay$Serializer
+ XXX.loot.functions.CopyBlockState
- XXX.loot.functions.CopyBlockState$1
+ XXX.loot.functions.CopyBlockState$Builder
- XXX.loot.functions.CopyBlockState$Serializer
+ XXX.loot.functions.CopyNameFunction
- XXX.loot.functions.CopyNameFunction$1
+ XXX.loot.functions.CopyNameFunction$NameSource
- XXX.loot.functions.CopyNameFunction$Serializer
+ XXX.loot.functions.CopyNbtFunction
- XXX.loot.functions.CopyNbtFunction$1
+ XXX.loot.functions.CopyNbtFunction$Builder
- XXX.loot.functions.CopyNbtFunction$CopyOperation
+ XXX.loot.functions.CopyNbtFunction$DataSource
- XXX.loot.functions.CopyNbtFunction$MergeStrategy
+ XXX.loot.functions.CopyNbtFunction$MergeStrategy$1
- XXX.loot.functions.CopyNbtFunction$MergeStrategy$2
+ XXX.loot.functions.CopyNbtFunction$MergeStrategy$3
- XXX.loot.functions.CopyNbtFunction$Serializer
+ XXX.loot.functions.EnchantRandomlyFunction
- XXX.loot.functions.EnchantRandomlyFunction$1
+ XXX.loot.functions.EnchantRandomlyFunction$Builder
- XXX.loot.functions.EnchantRandomlyFunction$Serializer
+ XXX.loot.functions.EnchantWithLevelsFunction
- XXX.loot.functions.EnchantWithLevelsFunction$1
+ XXX.loot.functions.EnchantWithLevelsFunction$Builder
- XXX.loot.functions.EnchantWithLevelsFunction$Serializer
+ XXX.loot.functions.ExplorationMapFunction
- XXX.loot.functions.ExplorationMapFunction$1
+ XXX.loot.functions.ExplorationMapFunction$Builder
- XXX.loot.functions.ExplorationMapFunction$Serializer
+ XXX.loot.functions.FillPlayerHead
- XXX.loot.functions.FillPlayerHead$Serializer
+ XXX.loot.functions.FunctionUserBuilder
- XXX.loot.functions.LimitCount
+ XXX.loot.functions.LimitCount$1
- XXX.loot.functions.LimitCount$Serializer
+ XXX.loot.functions.LootingEnchantFunction
- XXX.loot.functions.LootingEnchantFunction$1
+ XXX.loot.functions.LootingEnchantFunction$Builder
- XXX.loot.functions.LootingEnchantFunction$Serializer
+ XXX.loot.functions.LootItemConditionalFunction
- XXX.loot.functions.LootItemConditionalFunction$Builder
+ XXX.loot.functions.LootItemConditionalFunction$DummyBuilder
- XXX.loot.functions.LootItemConditionalFunction$Serializer
+ XXX.loot.functions.LootItemFunction
- XXX.loot.functions.LootItemFunction$Builder
- XXX.loot.functions.LootItemFunctions
+ XXX.loot.functions.LootItemFunctionType
- XXX.loot.functions.package-info
+ XXX.loot.functions.SetAttributesFunction
- XXX.loot.functions.SetAttributesFunction$1
+ XXX.loot.functions.SetAttributesFunction$Builder
- XXX.loot.functions.SetAttributesFunction$Modifier
+ XXX.loot.functions.SetAttributesFunction$ModifierBuilder
- XXX.loot.functions.SetAttributesFunction$Serializer
+ XXX.loot.functions.SetContainerContents
- XXX.loot.functions.SetContainerContents$1
+ XXX.loot.functions.SetContainerContents$Builder
- XXX.loot.functions.SetContainerContents$Serializer
+ XXX.loot.functions.SetContainerLootTable
- XXX.loot.functions.SetContainerLootTable$1
+ XXX.loot.functions.SetContainerLootTable$Serializer
- XXX.loot.functions.SetItemCountFunction
+ XXX.loot.functions.SetItemCountFunction$1
- XXX.loot.functions.SetItemCountFunction$Serializer
+ XXX.loot.functions.SetItemDamageFunction
- XXX.loot.functions.SetItemDamageFunction$1
+ XXX.loot.functions.SetItemDamageFunction$Serializer
- XXX.loot.functions.SetLoreFunction
+ XXX.loot.functions.SetLoreFunction$Builder
- XXX.loot.functions.SetLoreFunction$Serializer
+ XXX.loot.functions.SetNameFunction
- XXX.loot.functions.SetNameFunction$1
+ XXX.loot.functions.SetNameFunction$Serializer
- XXX.loot.functions.SetNbtFunction
+ XXX.loot.functions.SetNbtFunction$1
- XXX.loot.functions.SetNbtFunction$Serializer
+ XXX.loot.functions.SetStewEffectFunction
- XXX.loot.functions.SetStewEffectFunction$1
+ XXX.loot.functions.SetStewEffectFunction$Builder
- XXX.loot.functions.SetStewEffectFunction$Serializer
+ XXX.loot.functions.SmeltItemFunction
- XXX.loot.functions.SmeltItemFunction$1
+ XXX.loot.functions.SmeltItemFunction$Serializer
- XXX.loot.parameters.LootContextParam
+ XXX.loot.parameters.LootContextParams
+ XXX.loot.parameters.LootContextParamSet
- XXX.loot.parameters.LootContextParamSet$1
+ XXX.loot.parameters.LootContextParamSet$Builder
- XXX.loot.parameters.LootContextParamSets
- XXX.loot.parameters.package-info
+ XXX.loot.predicates.AlternativeLootItemCondition
- XXX.loot.predicates.AlternativeLootItemCondition$1
+ XXX.loot.predicates.AlternativeLootItemCondition$Builder
- XXX.loot.predicates.AlternativeLootItemCondition$Serializer
+ XXX.loot.predicates.BonusLevelTableCondition
- XXX.loot.predicates.BonusLevelTableCondition$1
+ XXX.loot.predicates.BonusLevelTableCondition$Serializer
- XXX.loot.predicates.ConditionReference
+ XXX.loot.predicates.ConditionReference$1
- XXX.loot.predicates.ConditionReference$Serializer
+ XXX.loot.predicates.ConditionUserBuilder
- XXX.loot.predicates.DamageSourceCondition
+ XXX.loot.predicates.DamageSourceCondition$1
- XXX.loot.predicates.DamageSourceCondition$Serializer
+ XXX.loot.predicates.EntityHasScoreCondition
- XXX.loot.predicates.EntityHasScoreCondition$1
+ XXX.loot.predicates.EntityHasScoreCondition$Builder
- XXX.loot.predicates.EntityHasScoreCondition$Serializer
+ XXX.loot.predicates.ExplosionCondition
- XXX.loot.predicates.ExplosionCondition$Serializer
+ XXX.loot.predicates.InvertedLootItemCondition
- XXX.loot.predicates.InvertedLootItemCondition$1
+ XXX.loot.predicates.InvertedLootItemCondition$Serializer
- XXX.loot.predicates.LocationCheck
+ XXX.loot.predicates.LocationCheck$1
- XXX.loot.predicates.LocationCheck$Serializer
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition
- XXX.loot.predicates.LootItemBlockStatePropertyCondition$1
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition$Builder
- XXX.loot.predicates.LootItemBlockStatePropertyCondition$Serializer
+ XXX.loot.predicates.LootItemCondition
- XXX.loot.predicates.LootItemCondition$Builder
- XXX.loot.predicates.LootItemConditions
+ XXX.loot.predicates.LootItemConditionType
+ XXX.loot.predicates.LootItemEntityPropertyCondition
- XXX.loot.predicates.LootItemEntityPropertyCondition$1
+ XXX.loot.predicates.LootItemEntityPropertyCondition$Serializer
- XXX.loot.predicates.LootItemKilledByPlayerCondition
+ XXX.loot.predicates.LootItemKilledByPlayerCondition$Serializer
- XXX.loot.predicates.LootItemRandomChanceCondition
+ XXX.loot.predicates.LootItemRandomChanceCondition$1
- XXX.loot.predicates.LootItemRandomChanceCondition$Serializer
+ XXX.loot.predicates.LootItemRandomChanceWithLootingCondition
- XXX.loot.predicates.LootItemRandomChanceWithLootingCondition$1
+ XXX.loot.predicates.LootItemRandomChanceWithLootingCondition$Serializer
- XXX.loot.predicates.MatchTool
+ XXX.loot.predicates.MatchTool$Serializer
- XXX.loot.predicates.package-info
- XXX.loot.predicates.TimeCheck
+ XXX.loot.predicates.TimeCheck$1
- XXX.loot.predicates.TimeCheck$Builder
+ XXX.loot.predicates.TimeCheck$Serializer
- XXX.loot.predicates.WeatherCheck
+ XXX.loot.predicates.WeatherCheck$1
- XXX.loot.predicates.WeatherCheck$Builder
+ XXX.loot.predicates.WeatherCheck$Serializer
- XXX.metadata.pack.package-info
- XXX.metadata.pack.PackMetadataSection
+ XXX.metadata.pack.PackMetadataSectionSerializer
+ XXX.minecraft.advancements.Advancement
- XXX.minecraft.advancements.Advancement$1
+ XXX.minecraft.advancements.Advancement$Builder
- XXX.minecraft.advancements.AdvancementList
+ XXX.minecraft.advancements.AdvancementList$Listener
- XXX.minecraft.advancements.AdvancementProgress
+ XXX.minecraft.advancements.AdvancementProgress$Serializer
- XXX.minecraft.advancements.AdvancementRewards
+ XXX.minecraft.advancements.AdvancementRewards$Builder
- XXX.minecraft.advancements.CriteriaTriggers
+ XXX.minecraft.advancements.Criterion
- XXX.minecraft.advancements.CriterionProgress
+ XXX.minecraft.advancements.CriterionTrigger
- XXX.minecraft.advancements.CriterionTrigger$Listener
+ XXX.minecraft.advancements.CriterionTriggerInstance
- XXX.minecraft.advancements.DisplayInfo
+ XXX.minecraft.advancements.FrameType
- XXX.minecraft.advancements.package-info
- XXX.minecraft.advancements.RequirementsStrategy
+ XXX.minecraft.advancements.TreeNodePosition
+ XXX.minecraft.client.AmbientOcclusionStatus
- XXX.minecraft.client.AttackIndicatorStatus
+ XXX.minecraft.client.BooleanOption
- XXX.minecraft.client.Camera
+ XXX.minecraft.client.ClientBrandRetriever
- XXX.minecraft.client.ClientRecipeBook
+ XXX.minecraft.client.CloudStatus
- XXX.minecraft.client.ComponentCollector
+ XXX.minecraft.client.CycleOption
- XXX.minecraft.client.DebugQueryHandler
+ XXX.minecraft.client.FullscreenResolutionProgressOption
- XXX.minecraft.client.Game
+ XXX.minecraft.client.Game$Metrics
- XXX.minecraft.client.GraphicsStatus
+ XXX.minecraft.client.GraphicsStatus$1
- XXX.minecraft.client.GuiMessage
+ XXX.minecraft.client.HotbarManager
+ XXX.minecraft.client.KeyboardHandler
- XXX.minecraft.client.KeyboardHandler$1
- XXX.minecraft.client.KeyMapping
+ XXX.minecraft.client.LogaritmicProgressOption
- XXX.minecraft.client.Minecraft
+ XXX.minecraft.client.Minecraft$1
- XXX.minecraft.client.Minecraft$ExperimentalDialogType
+ XXX.minecraft.client.Minecraft$ServerStem
- XXX.minecraft.client.MouseHandler
+ XXX.minecraft.client.NarratorStatus
- XXX.minecraft.client.Option
+ XXX.minecraft.client.Option$1
- XXX.minecraft.client.Options
+ XXX.minecraft.client.Options$1
- XXX.minecraft.client.Options$2
+ XXX.minecraft.client.ParticleStatus
- XXX.minecraft.client.ProgressOption
+ XXX.minecraft.client.RecipeBookCategories
- XXX.minecraft.client.Screenshot
+ XXX.minecraft.client.Session
- XXX.minecraft.client.StringDecomposer
+ XXX.minecraft.client.StringDecomposer$Output
- XXX.minecraft.client.StringSplitter
+ XXX.minecraft.client.StringSplitter$1
- XXX.minecraft.client.StringSplitter$FlatComponents
+ XXX.minecraft.client.StringSplitter$LineBreakFinder
- XXX.minecraft.client.StringSplitter$LineComponent
+ XXX.minecraft.client.StringSplitter$LinePosConsumer
- XXX.minecraft.client.StringSplitter$WidthLimitedCharSink
+ XXX.minecraft.client.StringSplitter$WidthProvider
- XXX.minecraft.client.Timer
+ XXX.minecraft.client.ToggleKeyMapping
- XXX.minecraft.client.User
+ XXX.minecraft.client.User$Type
- XXX.minecraft.obfuscate.DontObfuscateOrShrink
+ XXX.minecraft.obfuscate.KeepAfterObfuscation
- XXX.minecraft.obfuscate.package-info
- XXX.minecraft.realms.DisconnectedRealmsScreen
+ XXX.minecraft.realms.NarrationHelper
+ XXX.minecraft.realms.package-info
- XXX.minecraft.realms.RealmsBridge
+ XXX.minecraft.realms.RealmsConnect
- XXX.minecraft.realms.RealmsConnect$1
+ XXX.minecraft.realms.RealmsLabel
- XXX.minecraft.realms.RealmsObjectSelectionList
+ XXX.minecraft.realms.RealmsScreen
- XXX.minecraft.realms.RealmsServerAddress
+ XXX.minecraft.realms.RepeatedNarrator
- XXX.minecraft.realms.RepeatedNarrator$Params
+ XXX.minecraft.recipebook.package-info
- XXX.minecraft.recipebook.PlaceRecipe
+ XXX.minecraft.recipebook.ServerPlaceRecipe
- XXX.minecraft.recipebook.ServerPlaceSmeltingRecipe
- XXX.minecraft.resources.DelegatingOps
- XXX.minecraft.resources.package-info
+ XXX.minecraft.resources.RegistryDataPackCodec
- XXX.minecraft.resources.RegistryFileCodec
+ XXX.minecraft.resources.RegistryReadOps
- XXX.minecraft.resources.RegistryReadOps$1
+ XXX.minecraft.resources.RegistryReadOps$ReadCache
- XXX.minecraft.resources.RegistryWriteOps
+ XXX.minecraft.resources.ResourceKey
- XXX.minecraft.resources.ResourceLocation
+ XXX.minecraft.resources.ResourceLocation$Serializer
+ XXX.minecraft.server.Bootstrap
- XXX.minecraft.server.Bootstrap$1
+ XXX.minecraft.server.ChainedJsonException
- XXX.minecraft.server.ChainedJsonException$1
+ XXX.minecraft.server.ChainedJsonException$Entry
- XXX.minecraft.server.ConsoleInput
+ XXX.minecraft.server.ConsoleInputSource
- XXX.minecraft.server.DebugLoggedPrintStream
+ XXX.minecraft.server.Eula
- XXX.minecraft.server.LoggedPrintStream
+ XXX.minecraft.server.Main
- XXX.minecraft.server.Main$1
+ XXX.minecraft.server.MinecraftServer
- XXX.minecraft.server.MinecraftServer$1
+ XXX.minecraft.server.MinecraftServer$2
+ XXX.minecraft.server.package-info
- XXX.minecraft.server.PlayerAdvancements
+ XXX.minecraft.server.PlayerAdvancements$1
- XXX.minecraft.server.RunningOnDifferentThreadException
+ XXX.minecraft.server.ServerAdvancementManager
- XXX.minecraft.server.ServerFunctionLibrary
+ XXX.minecraft.server.ServerFunctionManager
- XXX.minecraft.server.ServerFunctionManager$QueuedCommand
+ XXX.minecraft.server.ServerInterface
- XXX.minecraft.server.ServerResources
+ XXX.minecraft.server.ServerScoreboard
- XXX.minecraft.server.ServerScoreboard$Method
+ XXX.minecraft.server.TickTask
- XXX.minecraft.sounds.Music
+ XXX.minecraft.sounds.Musics
+ XXX.minecraft.sounds.package-info
- XXX.minecraft.sounds.SoundEvent
+ XXX.minecraft.sounds.SoundEvents
- XXX.minecraft.sounds.SoundSource
- XXX.minecraft.stats.package-info
- XXX.minecraft.stats.RecipeBook
+ XXX.minecraft.stats.ServerRecipeBook
- XXX.minecraft.stats.ServerStatsCounter
+ XXX.minecraft.stats.Stat
- XXX.minecraft.stats.StatFormatter
- XXX.minecraft.stats.Stats
+ XXX.minecraft.stats.StatsCounter
+ XXX.minecraft.stats.StatType
+ XXX.minecraft.tags.BlockTags
- XXX.minecraft.tags.EntityTypeTags
+ XXX.minecraft.tags.FluidTags
- XXX.minecraft.tags.ItemTags
+ XXX.minecraft.tags.SerializationTags
- XXX.minecraft.tags.SetTag
- XXX.minecraft.util.Codecs$2
- XXX.minecraft.util.CrudeIncrementalIntIdentityHashBiMap
+ XXX.minecraft.util.Crypt
- XXX.minecraft.util.CsvOutput
+ XXX.minecraft.util.CsvOutput$1
- XXX.minecraft.util.CsvOutput$Builder
+ XXX.minecraft.util.CubicSampler
- XXX.minecraft.util.CubicSampler$Vec3Fetcher
+ XXX.minecraft.util.DirectoryLock
- XXX.minecraft.util.DirectoryLock$LockException
+ XXX.minecraft.util.ExceptionCollector
- XXX.minecraft.util.FastColor
+ XXX.minecraft.util.FastColor$ARGB32
- XXX.minecraft.util.FrameTimer
+ XXX.minecraft.util.GsonHelper
- XXX.minecraft.util.HeapDumper
+ XXX.minecraft.util.HttpUtil
- XXX.minecraft.util.InsensitiveStringMap
+ XXX.minecraft.util.IntRange
- XXX.minecraft.util.LazyLoadedValue
+ XXX.minecraft.util.LimitedCapacityList
- XXX.minecraft.util.LinearCongruentialGenerator
+ XXX.minecraft.util.LowerCaseEnumTypeAdapterFactory
- XXX.minecraft.util.LowerCaseEnumTypeAdapterFactory$1
+ XXX.minecraft.util.Mth
- XXX.minecraft.util.ProgressListener
+ XXX.minecraft.util.RewindableStream
- XXX.minecraft.util.RewindableStream$1
+ XXX.minecraft.util.SmoothDouble
- XXX.minecraft.util.SortedArraySet
+ XXX.minecraft.util.SortedArraySet$1
- XXX.minecraft.util.SortedArraySet$ArrayIterator
+ XXX.minecraft.util.StringRepresentable
- XXX.minecraft.util.StringRepresentable$1
+ XXX.minecraft.util.StringRepresentable$2
- XXX.minecraft.util.StringUtil
+ XXX.minecraft.util.TimeUtil
- XXX.minecraft.util.Tuple
+ XXX.minecraft.util.Unit
- XXX.minecraft.util.VisibleForDebug
+ XXX.minecraft.util.WeighedRandom
- XXX.minecraft.util.WeighedRandom$WeighedRandomItem
- XXX.minecraft.world.package-info
- XXX.model.multipart.AndCondition
+ XXX.model.multipart.Condition
- XXX.model.multipart.KeyValueCondition
+ XXX.model.multipart.MultiPart
- XXX.model.multipart.MultiPart$Deserializer
+ XXX.model.multipart.OrCondition
- XXX.model.multipart.package-info
- XXX.model.multipart.Selector
+ XXX.model.multipart.Selector$Deserializer
- XXX.mojang.math.Matrix3f
+ XXX.mojang.math.Matrix4f
- XXX.mojang.math.OctahedralGroup
+ XXX.mojang.math.OctahedralGroup$1
- XXX.mojang.math.Quaternion
+ XXX.mojang.math.SymmetricGroup3
- XXX.mojang.math.Transformation
+ XXX.mojang.math.Vector3d
- XXX.mojang.math.Vector3f
+ XXX.mojang.math.Vector4f
- XXX.mojang.realmsclient.KeyCombo
+ XXX.mojang.realmsclient.RealmsMainScreen
- XXX.mojang.realmsclient.RealmsMainScreen$1
+ XXX.mojang.realmsclient.RealmsMainScreen$2
- XXX.mojang.realmsclient.RealmsMainScreen$3
+ XXX.mojang.realmsclient.RealmsMainScreen$4
- XXX.mojang.realmsclient.RealmsMainScreen$5
+ XXX.mojang.realmsclient.RealmsMainScreen$CloseButton
- XXX.mojang.realmsclient.RealmsMainScreen$Entry
+ XXX.mojang.realmsclient.RealmsMainScreen$HoveredElement
- XXX.mojang.realmsclient.RealmsMainScreen$NewsButton
+ XXX.mojang.realmsclient.RealmsMainScreen$PendingInvitesButton
- XXX.mojang.realmsclient.RealmsMainScreen$RealmSelectionList
+ XXX.mojang.realmsclient.RealmsMainScreen$ServerEntry
- XXX.mojang.realmsclient.RealmsMainScreen$ShowPopupButton
+ XXX.mojang.realmsclient.RealmsMainScreen$TrialEntry
- XXX.mojang.realmsclient.Unit
+ XXX.network.protocol.package-info
+ XXX.network.syncher.EntityDataAccessor
- XXX.network.syncher.EntityDataSerializer
+ XXX.network.syncher.EntityDataSerializers
- XXX.network.syncher.EntityDataSerializers$1
+ XXX.network.syncher.EntityDataSerializers$10
- XXX.network.syncher.EntityDataSerializers$11
+ XXX.network.syncher.EntityDataSerializers$12
- XXX.network.syncher.EntityDataSerializers$13
+ XXX.network.syncher.EntityDataSerializers$14
- XXX.network.syncher.EntityDataSerializers$15
+ XXX.network.syncher.EntityDataSerializers$16
- XXX.network.syncher.EntityDataSerializers$17
+ XXX.network.syncher.EntityDataSerializers$18
- XXX.network.syncher.EntityDataSerializers$19
+ XXX.network.syncher.EntityDataSerializers$2
- XXX.network.syncher.EntityDataSerializers$3
+ XXX.network.syncher.EntityDataSerializers$4
- XXX.network.syncher.EntityDataSerializers$5
+ XXX.network.syncher.EntityDataSerializers$6
- XXX.network.syncher.EntityDataSerializers$7
+ XXX.network.syncher.EntityDataSerializers$8
- XXX.network.syncher.EntityDataSerializers$9
+ XXX.network.syncher.package-info
+ XXX.network.syncher.SynchedEntityData
- XXX.network.syncher.SynchedEntityData$DataItem
+ XXX.newbiome.area.Area
- XXX.newbiome.area.AreaFactory
+ XXX.newbiome.area.LazyArea
- XXX.newbiome.area.package-info
+ XXX.newbiome.context.BigContext
- XXX.newbiome.context.Context
+ XXX.newbiome.context.LazyAreaContext
- XXX.newbiome.context.package-info
+ XXX.newbiome.layer.AddDeepOceanLayer
- XXX.newbiome.layer.AddEdgeLayer
+ XXX.newbiome.layer.AddEdgeLayer$CoolWarm
- XXX.newbiome.layer.AddEdgeLayer$HeatIce
+ XXX.newbiome.layer.AddEdgeLayer$IntroduceSpecial
- XXX.newbiome.layer.AddIslandLayer
+ XXX.newbiome.layer.AddMushroomIslandLayer
- XXX.newbiome.layer.AddSnowLayer
+ XXX.newbiome.layer.BiomeEdgeLayer
- XXX.newbiome.layer.BiomeInitLayer
+ XXX.newbiome.layer.IslandLayer
- XXX.newbiome.layer.Layer
+ XXX.newbiome.layer.Layers
- XXX.newbiome.layer.OceanLayer
+ XXX.newbiome.layer.OceanMixerLayer
+ XXX.newbiome.layer.package-info
- XXX.newbiome.layer.RareBiomeLargeLayer
+ XXX.newbiome.layer.RareBiomeSpotLayer
- XXX.newbiome.layer.RegionHillsLayer
+ XXX.newbiome.layer.RemoveTooMuchOceanLayer
- XXX.newbiome.layer.RiverInitLayer
+ XXX.newbiome.layer.RiverLayer
- XXX.newbiome.layer.RiverMixerLayer
+ XXX.newbiome.layer.ShoreLayer
- XXX.newbiome.layer.SmoothLayer
+ XXX.newbiome.layer.ZoomLayer
- XXX.newbiome.layer.ZoomLayer$1
+ XXX.packs.metadata.MetadataSectionSerializer
+ XXX.packs.metadata.package-info
+ XXX.packs.repository.FolderRepositorySource
- XXX.packs.repository.Pack
+ XXX.packs.repository.Pack$PackConstructor
- XXX.packs.repository.Pack$Position
- XXX.packs.repository.package-info
+ XXX.packs.repository.PackCompatibility
- XXX.packs.repository.PackRepository
+ XXX.packs.repository.PackSource
- XXX.packs.repository.RepositorySource
+ XXX.packs.repository.ServerPacksSource
+ XXX.packs.resources.FallbackResourceManager
- XXX.packs.resources.FallbackResourceManager$LeakedResourceWarningInputStream
+ XXX.packs.resources.package-info
+ XXX.packs.resources.PreparableReloadListener
- XXX.packs.resources.PreparableReloadListener$PreparationBarrier
+ XXX.packs.resources.ProfiledReloadInstance
- XXX.packs.resources.ProfiledReloadInstance$1
+ XXX.packs.resources.ProfiledReloadInstance$State
+ XXX.packs.resources.ReloadableResourceManager
- XXX.packs.resources.ReloadInstance
- XXX.packs.resources.Resource
+ XXX.packs.resources.ResourceManager
- XXX.packs.resources.ResourceManager$Empty
+ XXX.packs.resources.ResourceManagerReloadListener
- XXX.packs.resources.SimpleJsonResourceReloadListener
+ XXX.packs.resources.SimplePreparableReloadListener
+ XXX.packs.resources.SimpleReloadableResourceManager
- XXX.packs.resources.SimpleReloadableResourceManager$FailingReloadInstance
+ XXX.packs.resources.SimpleReloadableResourceManager$ResourcePackLoadingFailure
- XXX.packs.resources.SimpleReloadInstance
+ XXX.packs.resources.SimpleReloadInstance$1
- XXX.packs.resources.SimpleReloadInstance$StateFactory
- XXX.packs.resources.SimpleResource
- XXX.phys.shapes.ArrayVoxelShape
+ XXX.phys.shapes.ArrayVoxelShape$1
- XXX.phys.shapes.BitSetDiscreteVoxelShape
+ XXX.phys.shapes.BooleanOp
- XXX.phys.shapes.CollisionContext
+ XXX.phys.shapes.CubePointRange
- XXX.phys.shapes.CubeVoxelShape
+ XXX.phys.shapes.DiscreteCubeMerger
- XXX.phys.shapes.DiscreteVoxelShape
+ XXX.phys.shapes.DiscreteVoxelShape$IntFaceConsumer
- XXX.phys.shapes.DiscreteVoxelShape$IntLineConsumer
+ XXX.phys.shapes.EntityCollisionContext
- XXX.phys.shapes.EntityCollisionContext$1
+ XXX.phys.shapes.IdenticalMerger
- XXX.phys.shapes.IndexMerger
+ XXX.phys.shapes.IndexMerger$IndexConsumer
- XXX.phys.shapes.IndirectMerger
+ XXX.phys.shapes.IntPointRange
- XXX.phys.shapes.NonOverlappingMerger
+ XXX.phys.shapes.OffsetDoubleList
- XXX.phys.shapes.package-info
- XXX.phys.shapes.Shapes
+ XXX.phys.shapes.Shapes$DoubleLineConsumer
- XXX.phys.shapes.SliceShape
+ XXX.phys.shapes.SubShape
- XXX.phys.shapes.VoxelShape
+ XXX.phys.shapes.WorldRegionIndirectVoxelShape
- XXX.protocol.game.ClientboundGameEventPacket$Type
+ XXX.protocol.game.ClientboundHorseScreenOpenPacket
- XXX.protocol.game.ClientboundKeepAlivePacket
+ XXX.protocol.game.ClientboundLevelChunkPacket
- XXX.protocol.game.ClientboundLevelEventPacket
+ XXX.protocol.game.ClientboundLevelParticlesPacket
- XXX.protocol.game.ClientboundLightUpdatePacket
+ XXX.protocol.game.ClientboundLoginPacket
- XXX.protocol.game.ClientboundMapItemDataPacket
+ XXX.protocol.game.ClientboundMerchantOffersPacket
- XXX.protocol.game.ClientboundMoveEntityPacket
+ XXX.protocol.game.ClientboundMoveEntityPacket$Pos
- XXX.protocol.game.ClientboundMoveEntityPacket$PosRot
+ XXX.protocol.game.ClientboundMoveEntityPacket$Rot
- XXX.protocol.game.ClientboundMoveVehiclePacket
+ XXX.protocol.game.ClientboundOpenBookPacket
- XXX.protocol.game.ClientboundOpenScreenPacket
+ XXX.protocol.game.ClientboundOpenSignEditorPacket
- XXX.protocol.game.ClientboundPlaceGhostRecipePacket
+ XXX.protocol.game.ClientboundPlayerAbilitiesPacket
- XXX.protocol.game.ClientboundPlayerCombatPacket
+ XXX.protocol.game.ClientboundPlayerCombatPacket$1
- XXX.protocol.game.ClientboundPlayerCombatPacket$Event
+ XXX.protocol.game.ClientboundPlayerInfoPacket
- XXX.protocol.game.ClientboundPlayerInfoPacket$1
+ XXX.protocol.game.ClientboundPlayerInfoPacket$Action
- XXX.protocol.game.ClientboundPlayerInfoPacket$PlayerUpdate
+ XXX.protocol.game.ClientboundPlayerLookAtPacket
- XXX.protocol.game.ClientboundPlayerPositionPacket
+ XXX.protocol.game.ClientboundPlayerPositionPacket$RelativeArgument
- XXX.protocol.game.ClientboundRecipePacket
+ XXX.protocol.game.ClientboundRecipePacket$State
- XXX.protocol.game.ClientboundRemoveEntitiesPacket
+ XXX.protocol.game.ClientboundRemoveMobEffectPacket
- XXX.protocol.game.ClientboundResourcePackPacket
+ XXX.protocol.game.ClientboundRespawnPacket
- XXX.protocol.game.ClientboundRotateHeadPacket
+ XXX.protocol.game.ClientboundSelectAdvancementsTabPacket
- XXX.protocol.game.ClientboundSetBorderPacket
+ XXX.protocol.game.ClientboundSetBorderPacket$1
- XXX.protocol.game.ClientboundSetBorderPacket$Type
+ XXX.protocol.game.ClientboundSetCameraPacket
- XXX.protocol.game.ClientboundSetCarriedItemPacket
+ XXX.protocol.game.ClientboundSetChunkCacheCenterPacket
- XXX.protocol.game.ClientboundSetChunkCacheRadiusPacket
+ XXX.protocol.game.ClientboundSetDefaultSpawnPositionPacket
- XXX.protocol.game.ClientboundSetDisplayObjectivePacket
+ XXX.protocol.game.ClientboundSetEntityDataPacket
- XXX.protocol.game.ClientboundSetEntityLinkPacket
+ XXX.protocol.game.ClientboundSetEntityMotionPacket
- XXX.protocol.game.ClientboundSetEquippedItemPacket
+ XXX.protocol.game.ClientboundSetExperiencePacket
- XXX.protocol.game.ClientboundSetHealthPacket
+ XXX.protocol.game.ClientboundSetObjectivePacket
- XXX.protocol.game.ClientboundSetPassengersPacket
+ XXX.protocol.game.ClientboundSetPlayerTeamPacket
- XXX.protocol.game.ClientboundSetScorePacket
+ XXX.protocol.game.ClientboundSetTimePacket
- XXX.protocol.game.ClientboundSetTitlesPacket
+ XXX.protocol.game.ClientboundSetTitlesPacket$Type
- XXX.protocol.game.ClientboundSoundEntityPacket
+ XXX.protocol.game.ClientboundSoundPacket
- XXX.protocol.game.ClientboundStopSoundPacket
+ XXX.protocol.game.ClientboundTabListPacket
- XXX.protocol.game.ClientboundTagQueryPacket
+ XXX.protocol.game.ClientboundTakeItemEntityPacket
- XXX.protocol.game.ClientboundTeleportEntityPacket
+ XXX.protocol.game.ClientboundUpdateAdvancementsPacket
- XXX.protocol.game.ClientboundUpdateAttributesPacket
+ XXX.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
- XXX.protocol.game.ClientboundUpdateMobEffectPacket
+ XXX.protocol.game.ClientboundUpdateRecipesPacket
- XXX.protocol.game.ClientboundUpdateTagsPacket
+ XXX.protocol.game.DebugEntityNameGenerator
- XXX.protocol.game.DebugPackets
- XXX.protocol.game.package-info
- XXX.protocol.game.ServerboundAcceptTeleportationPacket
+ XXX.protocol.game.ServerboundBlockEntityTagQuery
- XXX.protocol.game.ServerboundChangeDifficultyPacket
+ XXX.protocol.game.ServerboundChatPacket
- XXX.protocol.game.ServerboundClientCommandPacket
+ XXX.protocol.game.ServerboundClientCommandPacket$Action
- XXX.protocol.game.ServerboundClientInformationPacket
+ XXX.protocol.game.ServerboundCommandSuggestionPacket
- XXX.protocol.game.ServerboundContainerAckPacket
+ XXX.protocol.game.ServerboundContainerButtonClickPacket
- XXX.protocol.game.ServerboundContainerClickPacket
+ XXX.protocol.game.ServerboundContainerClosePacket
- XXX.protocol.game.ServerboundCustomPayloadPacket
+ XXX.protocol.game.ServerboundEditBookPacket
- XXX.protocol.game.ServerboundEntityTagQuery
+ XXX.protocol.game.ServerboundInteractPacket
- XXX.protocol.game.ServerboundInteractPacket$Action
+ XXX.protocol.game.ServerboundJigsawGeneratePacket
- XXX.protocol.game.ServerboundKeepAlivePacket
+ XXX.protocol.game.ServerboundLockDifficultyPacket
- XXX.protocol.game.ServerboundMovePlayerPacket
+ XXX.protocol.game.ServerboundMovePlayerPacket$Pos
- XXX.protocol.game.ServerboundMovePlayerPacket$PosRot
+ XXX.protocol.game.ServerboundMovePlayerPacket$Rot
- XXX.protocol.game.ServerboundMoveVehiclePacket
+ XXX.protocol.game.ServerboundPaddleBoatPacket
- XXX.protocol.game.ServerboundPickItemPacket
+ XXX.protocol.game.ServerboundPlaceRecipePacket
- XXX.protocol.game.ServerboundPlayerAbilitiesPacket
+ XXX.protocol.game.ServerboundPlayerActionPacket
- XXX.protocol.game.ServerboundPlayerActionPacket$Action
+ XXX.protocol.game.ServerboundPlayerCommandPacket
- XXX.protocol.game.ServerboundPlayerCommandPacket$Action
+ XXX.protocol.game.ServerboundPlayerInputPacket
- XXX.protocol.game.ServerboundRecipeBookUpdatePacket
+ XXX.protocol.game.ServerboundRecipeBookUpdatePacket$Purpose
- XXX.protocol.game.ServerboundRenameItemPacket
+ XXX.protocol.game.ServerboundResourcePackPacket
- XXX.protocol.game.ServerboundResourcePackPacket$Action
+ XXX.protocol.game.ServerboundSeenAdvancementsPacket
- XXX.protocol.game.ServerboundSeenAdvancementsPacket$Action
+ XXX.protocol.game.ServerboundSelectTradePacket
- XXX.protocol.game.ServerboundSetBeaconPacket
+ XXX.protocol.game.ServerboundSetCarriedItemPacket
- XXX.protocol.game.ServerboundSetCommandBlockPacket
+ XXX.protocol.game.ServerboundSetCommandMinecartPacket
- XXX.protocol.game.ServerboundSetCreativeModeSlotPacket
+ XXX.protocol.game.ServerboundSetJigsawBlockPacket
- XXX.protocol.game.ServerboundSetStructureBlockPacket
+ XXX.protocol.game.ServerboundSignUpdatePacket
- XXX.protocol.game.ServerboundSwingPacket
+ XXX.protocol.game.ServerboundTeleportToEntityPacket
- XXX.protocol.game.ServerboundUseItemOnPacket
+ XXX.protocol.game.ServerboundUseItemPacket
+ XXX.protocol.game.ServerGamePacketListener
+ XXX.protocol.handshake.ClientIntentionPacket
+ XXX.protocol.handshake.package-info
- XXX.protocol.handshake.ServerHandshakePacketListener
+ XXX.protocol.login.ClientboundCustomQueryPacket
- XXX.protocol.login.ClientboundGameProfilePacket
+ XXX.protocol.login.ClientboundHelloPacket
- XXX.protocol.login.ClientboundLoginCompressionPacket
+ XXX.protocol.login.ClientboundLoginDisconnectPacket
- XXX.protocol.login.ClientLoginPacketListener
- XXX.protocol.login.package-info
+ XXX.protocol.login.ServerboundCustomQueryPacket
- XXX.protocol.login.ServerboundHelloPacket
+ XXX.protocol.login.ServerboundKeyPacket
- XXX.protocol.login.ServerLoginPacketListener
+ XXX.protocol.status.ClientboundPongResponsePacket
- XXX.protocol.status.ClientboundStatusResponsePacket
- XXX.protocol.status.ClientStatusPacketListener
- XXX.protocol.status.package-info
- XXX.protocol.status.ServerboundPingRequestPacket
+ XXX.protocol.status.ServerboundStatusRequestPacket
+ XXX.protocol.status.ServerStatus
- XXX.protocol.status.ServerStatus$Players
+ XXX.protocol.status.ServerStatus$Players$Serializer
- XXX.protocol.status.ServerStatus$Serializer
+ XXX.protocol.status.ServerStatus$Version
- XXX.protocol.status.ServerStatus$Version$Serializer
+ XXX.protocol.status.ServerStatusPacketListener
- XXX.rcon.thread.GenericThread
+ XXX.rcon.thread.package-info
+ XXX.rcon.thread.QueryThreadGs4
- XXX.rcon.thread.QueryThreadGs4$RequestChallenge
+ XXX.rcon.thread.RconClient
- XXX.rcon.thread.RconThread
+ XXX.realmsclient.client.FileDownload
- XXX.realmsclient.client.FileDownload$1
+ XXX.realmsclient.client.FileDownload$DownloadCountingOutputStream
- XXX.realmsclient.client.FileDownload$ProgressListener
+ XXX.realmsclient.client.FileDownload$ResourcePackProgressListener
- XXX.realmsclient.client.FileUpload
+ XXX.realmsclient.client.FileUpload$CustomInputStreamEntity
- XXX.realmsclient.client.Ping
+ XXX.realmsclient.client.Ping$Region
- XXX.realmsclient.client.RealmsClient
+ XXX.realmsclient.client.RealmsClient$CompatibleVersionResponse
- XXX.realmsclient.client.RealmsClient$Environment
+ XXX.realmsclient.client.RealmsClientConfig
- XXX.realmsclient.client.RealmsError
+ XXX.realmsclient.client.Request
- XXX.realmsclient.client.Request$Delete
+ XXX.realmsclient.client.Request$Get
- XXX.realmsclient.client.Request$Post
+ XXX.realmsclient.client.Request$Put
- XXX.realmsclient.client.UploadStatus
+ XXX.realmsclient.dto.Backup
- XXX.realmsclient.dto.BackupList
+ XXX.realmsclient.dto.GuardedSerializer
- XXX.realmsclient.dto.Ops
+ XXX.realmsclient.dto.PendingInvite
- XXX.realmsclient.dto.PendingInvitesList
+ XXX.realmsclient.dto.PingResult
- XXX.realmsclient.dto.PlayerInfo
+ XXX.realmsclient.dto.RealmsDescriptionDto
- XXX.realmsclient.dto.RealmsNews
+ XXX.realmsclient.dto.RealmsServer
- XXX.realmsclient.dto.RealmsServer$McoServerComparator
+ XXX.realmsclient.dto.RealmsServer$State
- XXX.realmsclient.dto.RealmsServer$WorldType
+ XXX.realmsclient.dto.RealmsServerAddress
- XXX.realmsclient.dto.RealmsServerList
+ XXX.realmsclient.dto.RealmsServerPing
- XXX.realmsclient.dto.RealmsServerPlayerList
+ XXX.realmsclient.dto.RealmsServerPlayerLists
- XXX.realmsclient.dto.RealmsWorldOptions
+ XXX.realmsclient.dto.RealmsWorldResetDto
- XXX.realmsclient.dto.ReflectionBasedSerialization
+ XXX.realmsclient.dto.RegionPingResult
- XXX.realmsclient.dto.Subscription
+ XXX.realmsclient.dto.Subscription$SubscriptionType
- XXX.realmsclient.dto.UploadInfo
+ XXX.realmsclient.dto.ValueObject
- XXX.realmsclient.dto.WorldDownload
+ XXX.realmsclient.dto.WorldTemplate
- XXX.realmsclient.dto.WorldTemplate$WorldTemplateType
+ XXX.realmsclient.dto.WorldTemplatePaginatedList
- XXX.realmsclient.exception.RealmsDefaultUncaughtExceptionHandler
+ XXX.realmsclient.exception.RealmsHttpException
- XXX.realmsclient.exception.RealmsServiceException
+ XXX.realmsclient.exception.RetryCallException
- XXX.realmsclient.gui.ErrorCallback
+ XXX.realmsclient.gui.RealmsDataFetcher
- XXX.realmsclient.gui.RealmsDataFetcher$1
+ XXX.realmsclient.gui.RealmsDataFetcher$LiveStatsTask
- XXX.realmsclient.gui.RealmsDataFetcher$PendingInviteUpdateTask
+ XXX.realmsclient.gui.RealmsDataFetcher$ServerListUpdateTask
- XXX.realmsclient.gui.RealmsDataFetcher$Task
+ XXX.realmsclient.gui.RealmsDataFetcher$TrialAvailabilityTask
- XXX.realmsclient.gui.RealmsDataFetcher$UnreadNewsTask
+ XXX.realmsclient.gui.RealmsWorldSlotButton
- XXX.realmsclient.gui.RealmsWorldSlotButton$Action
+ XXX.realmsclient.gui.RealmsWorldSlotButton$State
- XXX.realmsclient.gui.RowButton
- XXX.realmsclient.util.JsonUtils
+ XXX.realmsclient.util.RealmsPersistence
- XXX.realmsclient.util.RealmsPersistence$RealmsPersistenceData
+ XXX.realmsclient.util.RealmsTextureManager
- XXX.realmsclient.util.RealmsTextureManager$1
+ XXX.realmsclient.util.RealmsTextureManager$RealmsTexture
- XXX.realmsclient.util.RealmsUtil
+ XXX.realmsclient.util.RealmsUtil$1
- XXX.realmsclient.util.SkinProcessor
+ XXX.realmsclient.util.TextRenderingUtils
- XXX.realmsclient.util.TextRenderingUtils$Line
+ XXX.realmsclient.util.TextRenderingUtils$LineSegment
- XXX.realmsclient.util.UploadTokenCache
- XXX.renderer.banner.package-info
+ XXX.renderer.block.BlockModelShaper
- XXX.renderer.block.BlockRenderDispatcher
+ XXX.renderer.block.BlockRenderDispatcher$1
- XXX.renderer.block.LiquidBlockRenderer
+ XXX.renderer.block.ModelBlockRenderer
- XXX.renderer.block.ModelBlockRenderer$1
+ XXX.renderer.block.ModelBlockRenderer$AdjacencyInfo
- XXX.renderer.block.ModelBlockRenderer$AmbientOcclusionFace
+ XXX.renderer.block.ModelBlockRenderer$AmbientVertexRemap
- XXX.renderer.block.ModelBlockRenderer$Cache
+ XXX.renderer.block.ModelBlockRenderer$Cache$1
- XXX.renderer.block.ModelBlockRenderer$Cache$2
+ XXX.renderer.block.ModelBlockRenderer$SizeInfo
- XXX.renderer.block.package-info
- XXX.renderer.blockentity.BannerRenderer
+ XXX.renderer.blockentity.BeaconRenderer
- XXX.renderer.blockentity.BedRenderer
+ XXX.renderer.blockentity.BellRenderer
- XXX.renderer.blockentity.BlockEntityRenderDispatcher
+ XXX.renderer.blockentity.BlockEntityRenderer
- XXX.renderer.blockentity.BrightnessCombiner
+ XXX.renderer.blockentity.CampfireRenderer
- XXX.renderer.blockentity.ChestRenderer
+ XXX.renderer.blockentity.ConduitRenderer
- XXX.renderer.blockentity.EnchantTableRenderer
+ XXX.renderer.blockentity.LecternRenderer
- XXX.renderer.blockentity.PistonHeadRenderer
+ XXX.renderer.blockentity.ShulkerBoxRenderer
- XXX.renderer.blockentity.SignRenderer
+ XXX.renderer.blockentity.SignRenderer$SignModel
- XXX.renderer.blockentity.SkullBlockRenderer
+ XXX.renderer.blockentity.SkullBlockRenderer$1
- XXX.saveddata.maps.MapBanner
+ XXX.saveddata.maps.MapBanner$1
- XXX.saveddata.maps.MapDecoration
+ XXX.saveddata.maps.MapDecoration$Type
- XXX.saveddata.maps.MapFrame
+ XXX.saveddata.maps.MapIndex
- XXX.saveddata.maps.MapItemSavedData
+ XXX.saveddata.maps.MapItemSavedData$HoldingPlayer
- XXX.saveddata.maps.package-info
+ XXX.scores.criteria.ObjectiveCriteria
- XXX.scores.criteria.ObjectiveCriteria$RenderType
+ XXX.scores.criteria.package-info
- XXX.screens.packs.package-info
+ XXX.screens.packs.PackSelectionModel$Entry
- XXX.screens.packs.PackSelectionModel$EntryBase
+ XXX.screens.packs.PackSelectionModel$SelectedPackEntry
- XXX.screens.packs.PackSelectionModel$UnselectedPackEntry
+ XXX.screens.packs.PackSelectionScreen
- XXX.screens.packs.TransferableSelectionList
+ XXX.screens.packs.TransferableSelectionList$PackEntry
+ XXX.screens.recipebook.AbstractFurnaceRecipeBookComponent
- XXX.screens.recipebook.BlastingRecipeBookComponent
+ XXX.screens.recipebook.GhostRecipe
- XXX.screens.recipebook.GhostRecipe$GhostIngredient
+ XXX.screens.recipebook.OverlayRecipeComponent
- XXX.screens.recipebook.OverlayRecipeComponent$OverlayRecipeButton
+ XXX.screens.recipebook.OverlayRecipeComponent$OverlayRecipeButton$Pos
- XXX.screens.recipebook.OverlayRecipeComponent$OverlaySmeltingRecipeButton
- XXX.screens.recipebook.package-info
+ XXX.screens.recipebook.RecipeBookComponent
- XXX.screens.recipebook.RecipeBookPage
+ XXX.screens.recipebook.RecipeBookTabButton
- XXX.screens.recipebook.RecipeButton
+ XXX.screens.recipebook.RecipeCollection
- XXX.screens.recipebook.RecipeShownListener
+ XXX.screens.recipebook.RecipeUpdateListener
- XXX.screens.recipebook.SmeltingRecipeBookComponent
+ XXX.screens.recipebook.SmokingRecipeBookComponent
+ XXX.screens.stream.package-info
- XXX.screens.worldselection.CreateWorldScreen
+ XXX.screens.worldselection.CreateWorldScreen$1
- XXX.screens.worldselection.CreateWorldScreen$2
+ XXX.screens.worldselection.CreateWorldScreen$3
- XXX.screens.worldselection.CreateWorldScreen$4
+ XXX.screens.worldselection.CreateWorldScreen$5
- XXX.screens.worldselection.CreateWorldScreen$OperationFailedException
+ XXX.screens.worldselection.CreateWorldScreen$SelectedGameMode
- XXX.screens.worldselection.EditGameRulesScreen
+ XXX.screens.worldselection.EditGameRulesScreen$BooleanRuleEntry
- XXX.screens.worldselection.EditGameRulesScreen$BooleanRuleEntry$1
+ XXX.screens.worldselection.EditGameRulesScreen$CategoryRuleEntry
- XXX.screens.worldselection.EditGameRulesScreen$EntryFactory
- XXX.server.bossevents.CustomBossEvent
+ XXX.server.bossevents.CustomBossEvents
- XXX.server.bossevents.package-info
+ XXX.server.commands.AdvancementCommands
- XXX.server.commands.AdvancementCommands$1
+ XXX.server.commands.AdvancementCommands$Action
- XXX.server.commands.AdvancementCommands$Action$1
+ XXX.server.commands.AdvancementCommands$Action$2
- XXX.server.commands.AdvancementCommands$Mode
+ XXX.server.commands.AttributeCommand
- XXX.server.commands.BanIpCommands
+ XXX.server.commands.BanListCommands
- XXX.server.commands.BanPlayerCommands
+ XXX.server.commands.BossBarCommands
- XXX.server.commands.ClearInventoryCommands
+ XXX.server.commands.CloneCommands
- XXX.server.commands.CloneCommands$CloneBlockInfo
+ XXX.server.commands.CloneCommands$Mode
- XXX.server.commands.DataPackCommand
+ XXX.server.commands.DataPackCommand$Inserter
+ XXX.server.commands.DebugCommand
- XXX.server.commands.DebugMobSpawningCommand
+ XXX.server.commands.DebugPathCommand
- XXX.server.commands.DefaultGameModeCommands
- XXX.server.commands.DeOpCommands
+ XXX.server.commands.DifficultyCommand
- XXX.server.commands.EffectCommands
+ XXX.server.commands.EmoteCommands
- XXX.server.commands.EnchantCommand
+ XXX.server.commands.ExecuteCommand
- XXX.server.commands.ExecuteCommand$CommandNumericPredicate
+ XXX.server.commands.ExecuteCommand$CommandPredicate
- XXX.server.commands.ExperienceCommand
+ XXX.server.commands.ExperienceCommand$Type
- XXX.server.commands.FillCommand
+ XXX.server.commands.FillCommand$Mode
- XXX.server.commands.ForceLoadCommand
+ XXX.server.commands.FunctionCommand
- XXX.server.commands.GameModeCommand
+ XXX.server.commands.GameRuleCommand
- XXX.server.commands.GameRuleCommand$1
+ XXX.server.commands.GiveCommand
- XXX.server.commands.HelpCommand
+ XXX.server.commands.KickCommand
- XXX.server.commands.KillCommand
+ XXX.server.commands.ListPlayersCommand
- XXX.server.commands.LocateBiomeCommand
+ XXX.server.commands.LocateCommand
- XXX.server.commands.LootCommand
+ XXX.server.commands.LootCommand$Callback
- XXX.server.commands.LootCommand$DropConsumer
+ XXX.server.commands.LootCommand$TailProvider
- XXX.server.commands.MsgCommand
+ XXX.server.commands.OpCommand
- XXX.server.commands.package-info
- XXX.server.commands.PardonCommand
+ XXX.server.commands.PardonIpCommand
- XXX.server.commands.ParticleCommand
+ XXX.server.commands.PlaySoundCommand
- XXX.server.commands.PublishCommand
+ XXX.server.commands.RaidCommand
- XXX.server.commands.RecipeCommand
+ XXX.server.commands.ReloadCommand
- XXX.server.commands.ReplaceItemCommand
+ XXX.server.commands.SaveAllCommand
- XXX.server.commands.SaveOffCommand
+ XXX.server.commands.SaveOnCommand
- XXX.server.commands.SayCommand
+ XXX.server.commands.ScheduleCommand
- XXX.server.commands.ScoreboardCommand
+ XXX.server.commands.SeedCommand
- XXX.server.commands.SetBlockCommand
+ XXX.server.commands.SetBlockCommand$Filter
- XXX.server.commands.SetBlockCommand$Mode
+ XXX.server.commands.SetPlayerIdleTimeoutCommand
- XXX.server.commands.SetSpawnCommand
+ XXX.server.commands.SetWorldSpawnCommand
- XXX.server.commands.SpectateCommand
+ XXX.server.commands.SpreadPlayersCommand
- XXX.server.commands.SpreadPlayersCommand$Position
+ XXX.server.commands.StopCommand
- XXX.server.commands.StopSoundCommand
+ XXX.server.commands.SummonCommand
- XXX.server.commands.TagCommand
+ XXX.server.commands.TeamCommand
- XXX.server.commands.TeamMsgCommand
+ XXX.server.commands.TeleportCommand
- XXX.server.commands.TeleportCommand$LookAt
+ XXX.server.commands.TellRawCommand
- XXX.server.commands.TimeCommand
+ XXX.server.commands.TitleCommand
- XXX.server.commands.TriggerCommand
+ XXX.server.commands.WeatherCommand
- XXX.server.commands.WhitelistCommand
+ XXX.server.commands.WorldBorderCommand
+ XXX.server.dedicated.DedicatedPlayerList
- XXX.server.dedicated.DedicatedServer
+ XXX.server.dedicated.DedicatedServer$1
- XXX.server.dedicated.DedicatedServerProperties
+ XXX.server.dedicated.DedicatedServerSettings
+ XXX.server.dedicated.package-info
- XXX.server.dedicated.ServerWatchdog
+ XXX.server.dedicated.ServerWatchdog$1
- XXX.server.dedicated.Settings
+ XXX.server.dedicated.Settings$1
- XXX.server.dedicated.Settings$MutableValue
- XXX.server.gui.MinecraftServerGui
+ XXX.server.gui.MinecraftServerGui$1
- XXX.server.gui.MinecraftServerGui$2
+ XXX.server.gui.package-info
+ XXX.server.gui.PlayerListComponent
- XXX.server.gui.StatsComponent
- XXX.server.level.BlockDestructionProgress
+ XXX.server.level.ChunkHolder
- XXX.server.level.ChunkHolder$1
+ XXX.server.level.ChunkHolder$ChunkLoadingFailure
- XXX.server.level.ChunkHolder$ChunkLoadingFailure$1
+ XXX.server.level.ChunkHolder$FullChunkStatus
- XXX.server.level.ChunkHolder$LevelChangeListener
+ XXX.server.level.ChunkHolder$PlayerProvider
- XXX.server.level.ChunkMap
+ XXX.server.level.ChunkMap$1
- XXX.server.level.ChunkMap$2
+ XXX.server.level.ChunkMap$DistanceManager
- XXX.server.level.ChunkMap$TrackedEntity
+ XXX.server.level.ChunkTaskPriorityQueue
- XXX.server.level.ChunkTaskPriorityQueueSorter
+ XXX.server.level.ChunkTaskPriorityQueueSorter$1
- XXX.server.level.ChunkTaskPriorityQueueSorter$Message
+ XXX.server.level.ChunkTaskPriorityQueueSorter$Release
- XXX.server.level.ChunkTracker
+ XXX.server.level.ColumnPos
- XXX.server.level.DemoMode
+ XXX.server.level.DistanceManager
- XXX.server.level.DistanceManager$ChunkTicketTracker
+ XXX.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
- XXX.server.level.DistanceManager$PlayerTicketTracker
+ XXX.server.level.FeatureSimulator
+ XXX.server.level.package-info
- XXX.server.level.PlayerMap
+ XXX.server.level.PlayerRespawnLogic
- XXX.server.level.SectionTracker
+ XXX.server.level.ServerBossEvent
- XXX.server.level.ServerChunkCache
+ XXX.server.level.ServerChunkCache$1
- XXX.server.level.ServerChunkCache$MainThreadExecutor
+ XXX.server.level.ServerEntity
- XXX.server.level.ServerLevel
+ XXX.server.level.ServerPlayer
- XXX.server.level.ServerPlayerGameMode
+ XXX.server.level.ThreadedLevelLightEngine
- XXX.server.level.ThreadedLevelLightEngine$TaskType
+ XXX.server.level.Ticket
- XXX.server.level.TicketType
+ XXX.server.level.WorldGenRegion
- XXX.server.level.WorldGenTickList
- XXX.server.network.LegacyQueryHandler
+ XXX.server.network.MemoryServerHandshakePacketListenerImpl
- XXX.server.network.package-info
- XXX.server.network.ServerConnectionListener
+ XXX.server.network.ServerConnectionListener$1
- XXX.server.network.ServerConnectionListener$2
+ XXX.server.network.ServerConnectionListener$LatencySimulator
- XXX.server.network.ServerGamePacketListenerImpl
+ XXX.server.network.ServerGamePacketListenerImpl$1
- XXX.server.network.ServerHandshakePacketListenerImpl
+ XXX.server.network.ServerHandshakePacketListenerImpl$1
- XXX.server.network.ServerLoginPacketListenerImpl
+ XXX.server.network.ServerLoginPacketListenerImpl$1
- XXX.server.network.ServerLoginPacketListenerImpl$State
+ XXX.server.network.ServerStatusPacketListenerImpl
- XXX.server.packs.AbstractPackResources
+ XXX.server.packs.FilePackResources
- XXX.server.packs.FolderPackResources
- XXX.server.packs.package-info
+ XXX.server.packs.PackResources
- XXX.server.packs.PackType
+ XXX.server.packs.ResourcePackFileNotFoundException
- XXX.server.packs.VanillaPackResources
- XXX.server.players.BanListEntry
+ XXX.server.players.GameProfileCache
- XXX.server.players.GameProfileCache$1
+ XXX.server.players.GameProfileCache$2
- XXX.server.players.GameProfileCache$GameProfileInfo
+ XXX.server.players.GameProfileCache$Serializer
- XXX.server.players.IpBanList
+ XXX.server.players.IpBanListEntry
- XXX.server.players.OldUsersConverter
+ XXX.server.players.OldUsersConverter$1
- XXX.server.players.OldUsersConverter$2
+ XXX.server.players.OldUsersConverter$3
- XXX.server.players.OldUsersConverter$4
+ XXX.server.players.OldUsersConverter$5
- XXX.server.players.OldUsersConverter$ConversionError
+ XXX.server.players.package-info
+ XXX.server.players.PlayerList
- XXX.server.players.PlayerList$1
+ XXX.server.players.ServerOpList
- XXX.server.players.ServerOpListEntry
+ XXX.server.players.StoredUserEntry
- XXX.server.players.StoredUserList
+ XXX.server.players.UserBanList
- XXX.server.players.UserBanListEntry
+ XXX.server.players.UserWhiteList
- XXX.server.players.UserWhiteListEntry
- XXX.server.rcon.NetworkDataOutputStream
+ XXX.server.rcon.package-info
+ XXX.server.rcon.PktUtils
- XXX.server.rcon.RconConsoleSource
+ XXX.storage.loot.BinomialDistributionGenerator
- XXX.storage.loot.BinomialDistributionGenerator$Serializer
+ XXX.storage.loot.BuiltInLootTables
- XXX.storage.loot.ConstantIntValue
+ XXX.storage.loot.ConstantIntValue$Serializer
- XXX.storage.loot.Deserializers
+ XXX.storage.loot.GsonAdapterFactory
- XXX.storage.loot.GsonAdapterFactory$1
+ XXX.storage.loot.GsonAdapterFactory$Builder
- XXX.storage.loot.GsonAdapterFactory$DefaultSerializer
+ XXX.storage.loot.GsonAdapterFactory$JsonAdapter
- XXX.storage.loot.IntLimiter
+ XXX.storage.loot.IntLimiter$1
- XXX.storage.loot.IntLimiter$Serializer
+ XXX.storage.loot.LootContext
- XXX.storage.loot.LootContext$1
+ XXX.storage.loot.LootContext$Builder
- XXX.storage.loot.LootContext$DynamicDrop
+ XXX.storage.loot.LootContext$EntityTarget
- XXX.storage.loot.LootContext$EntityTarget$Serializer
+ XXX.storage.loot.LootContextUser
- XXX.storage.loot.LootPool
+ XXX.storage.loot.LootPool$1
- XXX.storage.loot.LootPool$Builder
+ XXX.storage.loot.LootPool$Serializer
- XXX.storage.loot.LootTable
+ XXX.storage.loot.LootTable$1
- XXX.storage.loot.LootTable$Builder
+ XXX.storage.loot.LootTable$Serializer
- XXX.storage.loot.LootTables
+ XXX.storage.loot.package-info
+ XXX.storage.loot.PredicateManager
- XXX.storage.loot.PredicateManager$1
+ XXX.storage.loot.PredicateManager$CompositePredicate
- XXX.storage.loot.RandomIntGenerator
+ XXX.storage.loot.RandomIntGenerators
- XXX.storage.loot.RandomValueBounds
+ XXX.storage.loot.RandomValueBounds$Serializer
- XXX.storage.loot.Serializer
+ XXX.storage.loot.SerializerType
- XXX.storage.loot.ValidationContext
- XXX.storage.threaded.package-info
- XXX.structure.templatesystem.LavaSubmergedBlockProcessor
+ XXX.structure.templatesystem.LinearPosTest
- XXX.structure.templatesystem.NopProcessor
+ XXX.structure.templatesystem.package-info
+ XXX.structure.templatesystem.PosAlwaysTrueTest
- XXX.structure.templatesystem.PosRuleTest
+ XXX.structure.templatesystem.PosRuleTestType
- XXX.structure.templatesystem.ProcessorRule
+ XXX.structure.templatesystem.RandomBlockMatchTest
- XXX.structure.templatesystem.RandomBlockStateMatchTest
+ XXX.structure.templatesystem.RuleProcessor
- XXX.structure.templatesystem.RuleTest
+ XXX.structure.templatesystem.RuleTestType
- XXX.structure.templatesystem.StructureManager
+ XXX.structure.templatesystem.StructurePlaceSettings
- XXX.structure.templatesystem.StructureProcessor
+ XXX.structure.templatesystem.StructureProcessorType
- XXX.structure.templatesystem.StructureTemplate
+ XXX.structure.templatesystem.StructureTemplate$1
- XXX.structure.templatesystem.StructureTemplate$Palette
+ XXX.structure.templatesystem.StructureTemplate$SimplePalette
- XXX.structure.templatesystem.StructureTemplate$StructureBlockInfo
+ XXX.structure.templatesystem.StructureTemplate$StructureEntityInfo
- XXX.structure.templatesystem.TagMatchTest
- XXX.util.datafix.DataFixers
+ XXX.util.datafix.DataFixers$1
- XXX.util.datafix.DataFixers$2
+ XXX.util.datafix.DataFixTypes
+ XXX.util.datafix.PackedBitStorage
+ XXX.util.task.CloseServerTask
- XXX.util.task.ConnectTask
+ XXX.util.task.DownloadTask
- XXX.util.task.GetServerDetailsTask
+ XXX.util.task.LongRunningTask
- XXX.util.task.OpenServerTask
+ XXX.util.task.ResettingWorldTask
- XXX.util.task.RestoreTask
+ XXX.util.task.SwitchMinigameTask
- XXX.util.task.SwitchSlotTask
+ XXX.util.task.WorldCreationTask
- XXX.world.level.package-info
+ XXX.world.phys.AABB
- XXX.world.phys.BlockHitResult
+ XXX.world.phys.EntityHitResult
- XXX.world.phys.HitResult
+ XXX.world.phys.HitResult$Type
+ XXX.world.phys.package-info
- XXX.world.phys.PosAndRot
+ XXX.world.phys.Vec2
- XXX.world.phys.Vec3
+ XXX.world.scores.Objective
- XXX.world.scores.package-info
- XXX.world.scores.PlayerTeam
+ XXX.world.scores.Score
- XXX.world.scores.Scoreboard
+ XXX.world.scores.ScoreboardSaveData
- XXX.world.scores.Team
+ XXX.world.scores.Team$CollisionRule
- XXX.world.scores.Team$Visibility
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.gui.screens.PresetFlatWorldScreen +2M -2M | +1P -1P
```
```
XXX.gui.screens.ResourcePackSelectScreen +2M -3M
```
```
XXX.screens.inventory.InventoryScreen +1M
```
```
XXX.screens.packs.PackSelectionModel +3M -2M | +2P -1P
```
```
XXX.screens.worldselection.EditGameRulesScreen$IntegerRuleEntry -1M | -2P
```
```
XXX.screens.worldselection.EditWorldScreen +1M -1M
```
```
XXX.screens.worldselection.WorldSelectionList$WorldListEntry +1M
```
```
XXX.model.geom.ModelPart +2M
```
```
XXX.client.multiplayer.ServerStatusPinger +1M -1M
```
```
XXX.minecraft.core.WritableRegistry +1P
```
```
XXX.gametest.framework.GameTestHelper +2M
```
```
XXX.minecraft.nbt.NbtIo -1M
```
```
XXX.network.chat.Component +2P -2P
```
```
XXX.network.chat.NbtComponent$BlockNbtComponent +3M -3M
```
```
XXX.network.chat.NbtComponent$StorageNbtComponent +3M -3M
```
```
XXX.network.chat.SelectorComponent +3M -3M
```
```
XXX.network.chat.TranslatableComponent +3M -3M
```
```
XXX.minecraft.tags.Tag$1 -3M | -2P
```
```
XXX.minecraft.util.Codecs +3M
```
```
XXX.ai.behavior.AcquirePoi +5M -4M | +2P -3P
```
```
XXX.ai.navigation.PathNavigation +1M
```
```
XXX.village.poi.PoiManager +2M -3M
```
```
XXX.entity.animal.Bee$BeeHurtByOtherGoal +1M
```
```
XXX.entity.animal.SnowGolem +1M
```
```
XXX.entity.animal.Wolf +1M
```
```
XXX.entity.monster.Strider +1M
```
```
XXX.entity.monster.Zombie +1M
```
```
XXX.entity.monster.Zombie$ZombieGroupData +1M -1M | +1P
```
```
XXX.entity.monster.ZombifiedPiglin +7M | +2P
```
```
XXX.monster.piglin.PiglinAi +9M -4M
```
```
XXX.entity.player.Player +2M -1M
```
```
XXX.entity.projectile.ThrownEnderpearl +1M -1M | -1P
```
```
XXX.world.level.StructureFeatureManager +2M -1M | +1P -1P
```
```
XXX.level.block.RespawnAnchorBlock -1M
```
```
XXX.level.dimension.DimensionType +15M -16M | +9P -7P
```
```
XXX.levelgen.feature.TreeFeature +2M -1M
```
```
XXX.levelgen.flat.FlatLevelGeneratorSettings +1M
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.PresetFlatWorldScreen
</summary>

```diff
- FlatLevelGeneratorSettings access$402(PresetFlatWorldScreen,FlatLevelGeneratorSettings)
- FlatLevelGeneratorSettings fromString(String,FlatLevelGeneratorSettings)
+ FlatLevelGeneratorSettings fromString(String,StructureSettings)
+ StructureSettings access$402(PresetFlatWorldScreen,StructureSettings)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.ResourcePackSelectScreen
</summary>

```diff
- PackSelectionModel lambda$new$0(PackRepository,Consumer,Runnable)
+ PackSelectionModel lambda$new$1(PackRepository,Options,Runnable,Runnable)
+ void <init>(Screen,Options,PackRepository,Runnable)
- void <init>(Screen,PackRepository,Consumer,File)
+ void lambda$null$0(PackRepository,Options,Runnable,List,List,boolean)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.InventoryScreen
</summary>

```diff
- void lambda$renderEntityInInventory$1(EntityRenderDispatcher,LivingEntity,PoseStack,MultiBufferSource$BufferSource)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.packs.PackSelectionModel
</summary>

```diff
+ void <init>(Runnable,BiConsumer,Collection,Collection,PackSelectionModel$CommitHandler)
- void <init>(Runnable,BiConsumer,PackRepository,Consumer)
- void commit()
+ void commit(boolean)
- void findNewPacks()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$IntegerRuleEntry
</summary>

```diff
+ List children()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.worldselection.EditWorldScreen
</summary>

```diff
+ boolean makeBackupAndShowToast(LevelStorageSource,String)
- void makeBackupAndShowToast(LevelStorageSource,String)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.worldselection.WorldSelectionList$WorldListEntry
</summary>

```diff
- void queueLoadScreen()
```

</details>
<details>
<summary>
net.minecraft.client.model.geom.ModelPart
</summary>

```diff
- ModelPart createShallowCopy()
- void <init>()
```

</details>
<details>
<summary>
net.minecraft.client.multiplayer.ServerStatusPinger
</summary>

```diff
- void pingServer(ServerData,Runnable)
+ void pingServer(ServerData)
```

</details>
<details>
<summary>
net.minecraft.gametest.framework.GameTestHelper
</summary>

```diff
- ItemEntity spawnItem(Item,float,float,float)
- LivingEntity makeAboutToDrown(LivingEntity)
```

</details>
<details>
<summary>
net.minecraft.nbt.NbtIo
</summary>

```diff
+ void safeWrite(CompoundTag,File)
```

</details>
<details>
<summary>
net.minecraft.network.chat.NbtComponent$BlockNbtComponent
</summary>

```diff
- BaseComponent plainCopy()
+ BaseComponent toMutable()
- MutableComponent plainCopy()
+ MutableComponent toMutable()
- NbtComponent$BlockNbtComponent plainCopy()
+ NbtComponent$BlockNbtComponent toMutable()
```

</details>
<details>
<summary>
net.minecraft.network.chat.NbtComponent$StorageNbtComponent
</summary>

```diff
- BaseComponent plainCopy()
+ BaseComponent toMutable()
- MutableComponent plainCopy()
+ MutableComponent toMutable()
- NbtComponent$StorageNbtComponent plainCopy()
+ NbtComponent$StorageNbtComponent toMutable()
```

</details>
<details>
<summary>
net.minecraft.network.chat.SelectorComponent
</summary>

```diff
- BaseComponent plainCopy()
+ BaseComponent toMutable()
- MutableComponent plainCopy()
+ MutableComponent toMutable()
- SelectorComponent plainCopy()
+ SelectorComponent toMutable()
```

</details>
<details>
<summary>
net.minecraft.network.chat.TranslatableComponent
</summary>

```diff
- BaseComponent plainCopy()
+ BaseComponent toMutable()
- MutableComponent plainCopy()
+ MutableComponent toMutable()
- TranslatableComponent plainCopy()
+ TranslatableComponent toMutable()
```

</details>
<details>
<summary>
net.minecraft.tags.Tag$1
</summary>

```diff
+ boolean contains(Object)
+ List getValues()
+ void <init>(Set,ImmutableList)
```

</details>
<details>
<summary>
net.minecraft.util.Codecs
</summary>

```diff
- MapCodec mapResult(MapCodec,Codecs$ResultFunction)
- MapCodec withDefault(MapCodec,Consumer,Supplier)
- MapCodec withName(ResourceKey,MapCodec)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.behavior.AcquirePoi
</summary>

```diff
- AcquirePoi$JitteredLinearRetry lambda$start$4(PathfinderMob,long,long)
+ boolean lambda$null$1(BlockPos,BlockPos)
- boolean lambda$null$2(BlockPos,BlockPos)
+ boolean lambda$start$0(BlockPos)
- boolean lambda$start$0(long,Long2ObjectMap$Entry)
- boolean lambda$start$1(long,BlockPos)
+ boolean lambda$start$3(Long2LongMap$Entry)
+ void lambda$start$2(PoiManager,BlockPos,PathfinderMob,ServerLevel,PoiType)
- void lambda$start$3(PoiManager,BlockPos,PathfinderMob,ServerLevel,PoiType)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.navigation.PathNavigation
</summary>

```diff
- Path createPath(Set,int)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.village.poi.PoiManager
</summary>

```diff
- Optional lambda$getInChunk$2(ChunkPos,Integer)
+ Stream getInSection(Predicate,long,PoiManager$Occupancy)
+ Stream lambda$getInChunk$2(Predicate,ChunkPos,PoiManager$Occupancy,Integer)
- Stream lambda$getInChunk$3(Predicate,PoiManager$Occupancy,Optional)
+ Stream lambda$getInSection$3(Predicate,PoiManager$Occupancy,PoiSection)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Bee$BeeHurtByOtherGoal
</summary>

```diff
- boolean canContinueToUse()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.SnowGolem
</summary>

```diff
- Vec3 getLeashOffset()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Wolf
</summary>

```diff
- Vec3 getLeashOffset()
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Strider
</summary>

```diff
- Vec3 getLeashOffset()
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Zombie
</summary>

```diff
- boolean getSpawnAsBabyOdds(Random)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Zombie$ZombieGroupData
</summary>

```diff
- void <init>(boolean,boolean)
+ void <init>(boolean)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.ZombifiedPiglin
</summary>

```diff
- boolean isAlwaysExperienceDropper()
- boolean lambda$alertOthers$0(ZombifiedPiglin)
- boolean lambda$alertOthers$1(ZombifiedPiglin)
- boolean lambda$alertOthers$2(ZombifiedPiglin)
- void alertOthers()
- void lambda$alertOthers$3(ZombifiedPiglin)
- void maybeAlertOthers()
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.piglin.PiglinAi
</summary>

```diff
- boolean lambda$angerNearbyPiglins$3(boolean,Player,Piglin)
+ boolean lambda$angerNearbyPiglinsThatSee$3(Player,Piglin)
- Optional getNearestVisibleTargetablePlayer(Piglin)
- void angerNearbyPiglins(Player,boolean)
+ void angerNearbyPiglinsThatSee(Player)
- void broadcastUniversalAnger(Piglin)
- void lambda$angerNearbyPiglins$4(Player,Piglin)
+ void lambda$angerNearbyPiglinsThatSee$4(Player,Piglin)
- void lambda$broadcastRetreat$11(LivingEntity,Piglin)
+ void lambda$broadcastRetreat$9(LivingEntity,Piglin)
- void lambda$broadcastUniversalAnger$10(Piglin)
- void lambda$null$9(Piglin,Player)
- void setAngerTargetToNearestTargetablePlayerIfFound(Piglin,LivingEntity)
```

</details>
<details>
<summary>
net.minecraft.world.entity.player.Player
</summary>

```diff
- boolean isAffectedByFluids()
- void removeVehicle()
+ void stopRiding()
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.ThrownEnderpearl
</summary>

```diff
+ Entity changeDimension(ResourceKey)
- Entity changeDimension(ServerLevel)
```

</details>
<details>
<summary>
net.minecraft.world.level.StructureFeatureManager
</summary>

```diff
- StructureFeatureManager forWorldGenRegion(WorldGenRegion)
- void <init>(LevelAccessor,WorldGenSettings)
+ void <init>(ServerLevel,WorldGenSettings)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.RespawnAnchorBlock
</summary>

```diff
+ boolean useShapeForLightOcclusion(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.dimension.DimensionType
</summary>

```diff
+ App lambda$static$4(RecordCodecBuilder$Instance)
- App lambda$static$5(RecordCodecBuilder$Instance)
- boolean bedWorks()
- boolean hasFixedTime()
- boolean hasRaids()
+ boolean isEnd()
+ boolean isNether()
+ boolean isOverworld()
- boolean piglinSafe()
- boolean respawnAnchorWorks()
+ DataResult lambda$null$5(ResourceKey)
+ DataResult lambda$null$7(DimensionType)
+ DataResult lambda$null$9(DimensionType)
+ DataResult lambda$static$10(Either)
+ DataResult lambda$static$11(DimensionType)
+ DataResult lambda$static$6(ResourceKey)
+ DataResult lambda$static$8(DimensionType)
- DimensionType defaultOverworldCaves()
+ DimensionType lambda$defaultDimensions$12()
+ DimensionType lambda$defaultDimensions$13()
- DimensionType lambda$defaultDimensions$6()
- DimensionType lambda$defaultDimensions$7()
+ Float lambda$null$3(DimensionType)
- Float lambda$null$4(DimensionType)
- int logicalHeight()
- ResourceLocation lambda$null$3(DimensionType)
- Tag infiniburn()
- void <init>(OptionalLong,boolean,boolean,boolean,boolean,boolean,boolean,boolean,boolean,boolean,boolean,int,BiomeZoomer,ResourceLocation,float)
- void <init>(OptionalLong,boolean,boolean,boolean,boolean,boolean,boolean,boolean,boolean,boolean,int,ResourceLocation,float)
+ void <init>(OptionalLong,boolean,boolean,boolean,boolean,boolean,float)
+ void <init>(String,OptionalLong,boolean,boolean,boolean,boolean,boolean,boolean,BiomeZoomer,Optional,float)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.TreeFeature
</summary>

```diff
- boolean validTreePos(LevelSimulatedReader,BlockPos)
+ boolean validTreePos(LevelSimulatedRW,BlockPos)
- int getMaxFreeTreeHeight(LevelSimulatedReader,int,BlockPos,TreeConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorSettings
</summary>

```diff
- FlatLevelGeneratorSettings withLayers(List,StructureSettings)
```

</details>
</details>
<hr/>