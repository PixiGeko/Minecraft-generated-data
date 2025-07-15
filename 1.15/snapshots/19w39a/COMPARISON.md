## Comparison with [19w38b](https://github.com/PixiGeko/Minecraft-generated-data/tree/19w38b)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Tags](#tags)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">19w38b</th><th>19w39a</th></tr><tr><td>World version</td><td><pre>2206</pre></td><td><pre>2207</pre></td></tr><tr><td>Protocol version</td><td><pre>555</pre></td><td><pre>556</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">19w38b</th><th>19w39a</th></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr></table>
</details>
</details>
<hr/>
<details><summary><b><ins>TAGS</ins></b><a name="tags"></a></summary>
<br/>
<details>
<summary>
all_blocks_without_drop.json
</summary>

```diff
- minecraft:attached_melon_stem
- minecraft:attached_pumpkin_stem
```

</details>
<details>
<summary>
all_blocks_with_drop.json
</summary>

```diff
+ minecraft:attached_melon_stem
+ minecraft:attached_pumpkin_stem
```

</details>
<details>
<summary>
all_survival_blocks_without_drop.json
</summary>

```diff
- minecraft:attached_melon_stem
- minecraft:attached_pumpkin_stem
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
- XXX.ai.attributes.Attribute
+ XXX.ai.attributes.AttributeInstance
- XXX.ai.attributes.AttributeModifier
+ XXX.ai.attributes.AttributeModifier$Operation
- XXX.ai.attributes.BaseAttribute
+ XXX.ai.attributes.BaseAttributeMap
- XXX.ai.attributes.ModifiableAttributeInstance
+ XXX.ai.attributes.ModifiableAttributeMap
+ XXX.ai.attributes.package-info
- XXX.ai.attributes.RangedAttribute
- XXX.ai.behavior.AcquirePoi
+ XXX.ai.behavior.AssignProfessionFromJobSite
- XXX.ai.behavior.Behavior
+ XXX.ai.behavior.Behavior$Status
- XXX.ai.behavior.BehaviorUtils
+ XXX.ai.behavior.BlockPosWrapper
- XXX.ai.behavior.Celebrate
+ XXX.ai.behavior.DoNothing
- XXX.ai.behavior.EntityPosWrapper
+ XXX.ai.behavior.GateBehavior
- XXX.ai.behavior.GateBehavior$1
+ XXX.ai.behavior.GateBehavior$OrderPolicy
- XXX.ai.behavior.GateBehavior$RunningPolicy
+ XXX.ai.behavior.GateBehavior$RunningPolicy$1
- XXX.ai.behavior.GateBehavior$RunningPolicy$2
+ XXX.ai.behavior.GiveGiftToHero
- XXX.ai.behavior.GoOutsideToCelebrate
+ XXX.ai.behavior.GoToClosestVillage
- XXX.ai.behavior.HarvestFarmland
+ XXX.ai.behavior.InsideBrownianWalk
- XXX.ai.behavior.InteractWith
+ XXX.ai.behavior.InteractWithDoor
- XXX.ai.behavior.JumpOnBed
+ XXX.ai.behavior.LocateHidingPlace
- XXX.ai.behavior.LocateHidingPlaceDuringRaid
+ XXX.ai.behavior.LookAndFollowTradingPlayerSink
- XXX.ai.behavior.LookAtTargetSink
+ XXX.ai.behavior.MakeLove
- XXX.ai.behavior.MoveToSkySeeingSpot
+ XXX.ai.behavior.MoveToTargetSink
- XXX.ai.behavior.package-info
- XXX.ai.behavior.PickUpItems
+ XXX.ai.behavior.PlayTagWithOtherKids
- XXX.ai.behavior.PositionWrapper
+ XXX.ai.behavior.ReactToBell
- XXX.ai.behavior.ResetProfession
+ XXX.ai.behavior.ResetRaidStatus
- XXX.ai.behavior.RingBell
+ XXX.ai.behavior.RunOne
- XXX.ai.behavior.SetClosestHomeAsWalkTarget
+ XXX.ai.behavior.SetEntityLookTarget
- XXX.ai.behavior.SetHiddenState
+ XXX.ai.behavior.SetLookAndInteract
- XXX.ai.behavior.SetRaidStatus
+ XXX.ai.behavior.SetWalkTargetAwayFromEntity
- XXX.ai.behavior.SetWalkTargetFromBlockMemory
+ XXX.ai.behavior.SetWalkTargetFromLookTarget
- XXX.ai.behavior.ShowTradesToPlayer
+ XXX.ai.behavior.SleepInBed
- XXX.ai.behavior.SocializeAtBell
+ XXX.ai.behavior.StrollAroundPoi
- XXX.ai.behavior.StrollToPoi
+ XXX.ai.behavior.StrollToPoiList
- XXX.ai.behavior.Swim
+ XXX.ai.behavior.TradeWithVillager
- XXX.ai.behavior.UpdateActivityFromSchedule
+ XXX.ai.behavior.ValidateNearbyPoi
- XXX.ai.behavior.VictoryStroll
+ XXX.ai.behavior.VillageBoundRandomStroll
- XXX.ai.behavior.VillagerCalmDown
+ XXX.ai.behavior.VillagerGoalPackages
- XXX.ai.behavior.VillagerPanicTrigger
+ XXX.ai.behavior.WakeUp
- XXX.ai.behavior.WeightedList
+ XXX.ai.behavior.WeightedList$1
- XXX.ai.behavior.WeightedList$WeightedEntry
+ XXX.ai.behavior.WorkAtPoi
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
- XXX.ai.goal.FollowOwnerFlyingGoal
+ XXX.ai.goal.FollowOwnerGoal
- XXX.ai.goal.FollowParentGoal
+ XXX.ai.goal.Goal
- XXX.ai.goal.Goal$Flag
+ XXX.ai.goal.GoalSelector
- XXX.ai.goal.GoalSelector$1
+ XXX.ai.goal.GoalSelector$2
- XXX.ai.goal.InteractGoal
+ XXX.ai.goal.JumpGoal
- XXX.ai.goal.LandOnOwnersShoulderGoal
+ XXX.ai.goal.LeapAtTargetGoal
- XXX.ai.goal.LlamaFollowCaravanGoal
+ XXX.ai.goal.LookAtPlayerGoal
- XXX.ai.goal.LookAtTradingPlayerGoal
+ XXX.ai.goal.MeleeAttackGoal
- XXX.ai.goal.MoveBackToVillage
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
- XXX.ai.goal.SitGoal
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
+ XXX.ai.gossip.GossipContainer
- XXX.ai.gossip.GossipContainer$1
+ XXX.ai.gossip.GossipContainer$EntityGossips
- XXX.ai.gossip.GossipContainer$GossipEntry
+ XXX.ai.gossip.GossipType
- XXX.ai.gossip.package-info
+ XXX.ai.memory.MemoryModuleType
- XXX.ai.memory.MemoryStatus
- XXX.ai.memory.package-info
+ XXX.ai.memory.WalkTarget
+ XXX.ai.navigation.FlyingPathNavigation
- XXX.ai.navigation.GroundPathNavigation
- XXX.ai.navigation.package-info
+ XXX.ai.navigation.PathNavigation
- XXX.ai.navigation.WallClimberNavigation
+ XXX.ai.navigation.WaterBoundPathNavigation
- XXX.ai.sensing.DummySensor
+ XXX.ai.sensing.GolemSensor
- XXX.ai.sensing.HurtBySensor
+ XXX.ai.sensing.InteractableDoorsSensor
- XXX.ai.sensing.NearestBedSensor
+ XXX.ai.sensing.NearestLivingEntitySensor
+ XXX.ai.sensing.package-info
- XXX.ai.sensing.PlayerSensor
+ XXX.ai.sensing.SecondaryPoiSensor
- XXX.ai.sensing.Sensing
+ XXX.ai.sensing.Sensor
- XXX.ai.sensing.SensorType
+ XXX.ai.sensing.VillagerBabiesSensor
- XXX.ai.sensing.VillagerHostilesSensor
+ XXX.ai.targeting.package-info
- XXX.ai.targeting.TargetingConditions
+ XXX.ai.util.package-info
- XXX.ai.util.RandomPos
- XXX.ai.village.package-info
- XXX.ai.village.ReputationEventType
+ XXX.ai.village.ReputationEventType$1
- XXX.ai.village.VillageSiege
+ XXX.ai.village.VillageSiege$State
+ XXX.animal.horse.AbstractChestedHorse
- XXX.animal.horse.AbstractHorse
+ XXX.animal.horse.Donkey
- XXX.animal.horse.Horse
+ XXX.animal.horse.Horse$HorseGroupData
- XXX.animal.horse.Llama
+ XXX.animal.horse.Llama$1
- XXX.animal.horse.Llama$LlamaAttackWolfGoal
+ XXX.animal.horse.Llama$LlamaGroupData
- XXX.animal.horse.Llama$LlamaHurtByTargetGoal
+ XXX.animal.horse.Mule
+ XXX.animal.horse.package-info
- XXX.animal.horse.SkeletonHorse
+ XXX.animal.horse.SkeletonTrapGoal
- XXX.animal.horse.TraderLlama
+ XXX.animal.horse.TraderLlama$TraderLlamaDefendWanderingTraderGoal
- XXX.animal.horse.ZombieHorse
+ XXX.block.entity.AbstractFurnaceBlockEntity
- XXX.block.entity.AbstractFurnaceBlockEntity$1
+ XXX.block.entity.BannerBlockEntity
- XXX.block.entity.BannerPattern
+ XXX.block.entity.BannerPattern$Builder
- XXX.block.entity.BarrelBlockEntity
+ XXX.block.entity.BaseContainerBlockEntity
- XXX.block.entity.BeaconBlockEntity
+ XXX.block.entity.BeaconBlockEntity$1
- XXX.block.entity.BeaconBlockEntity$BeaconBeamSection
+ XXX.block.entity.BedBlockEntity
- XXX.block.entity.BeehiveBlockEntity
+ XXX.block.entity.BeehiveBlockEntity$1
- XXX.block.entity.BeehiveBlockEntity$BeeData
+ XXX.block.entity.BeehiveBlockEntity$BeeReleaseStatus
- XXX.block.entity.BellBlockEntity
+ XXX.block.entity.BlastFurnaceBlockEntity
- XXX.block.entity.BlockEntity
+ XXX.block.entity.BlockEntityType
- XXX.block.entity.BlockEntityType$Builder
+ XXX.block.entity.BrewingStandBlockEntity
- XXX.block.entity.BrewingStandBlockEntity$1
+ XXX.block.entity.CampfireBlockEntity
- XXX.block.entity.ChestBlockEntity
+ XXX.block.entity.CommandBlockEntity
- XXX.block.entity.CommandBlockEntity$1
+ XXX.block.entity.CommandBlockEntity$Mode
- XXX.block.entity.ComparatorBlockEntity
+ XXX.block.entity.ConduitBlockEntity
- XXX.block.entity.DaylightDetectorBlockEntity
+ XXX.block.entity.DispenserBlockEntity
- XXX.block.entity.DropperBlockEntity
+ XXX.block.entity.EnchantmentTableBlockEntity
- XXX.block.entity.EnderChestBlockEntity
+ XXX.block.entity.FurnaceBlockEntity
- XXX.block.entity.Hopper
+ XXX.block.entity.HopperBlockEntity
- XXX.block.entity.JigsawBlockEntity
+ XXX.block.entity.JukeboxBlockEntity
- XXX.block.entity.LecternBlockEntity
+ XXX.block.entity.LecternBlockEntity$1
- XXX.block.entity.LecternBlockEntity$2
+ XXX.block.entity.LidBlockEntity
- XXX.block.entity.package-info
- XXX.block.entity.RandomizableContainerBlockEntity
+ XXX.block.entity.ShulkerBoxBlockEntity
- XXX.block.entity.ShulkerBoxBlockEntity$1
+ XXX.block.entity.ShulkerBoxBlockEntity$AnimationStatus
- XXX.block.entity.SignBlockEntity
+ XXX.block.entity.SkullBlockEntity
- XXX.block.entity.SmokerBlockEntity
+ XXX.block.entity.SpawnerBlockEntity
- XXX.block.entity.SpawnerBlockEntity$1
+ XXX.block.entity.StructureBlockEntity
- XXX.block.entity.StructureBlockEntity$1
+ XXX.block.entity.StructureBlockEntity$UpdateType
- XXX.block.entity.TheEndGatewayBlockEntity
+ XXX.block.entity.TheEndPortalBlockEntity
- XXX.block.entity.TickableBlockEntity
+ XXX.block.entity.TrappedChestBlockEntity
+ XXX.block.grower.AbstractMegaTreeGrower
- XXX.block.grower.AbstractTreeGrower
+ XXX.block.grower.AcaciaTreeGrower
- XXX.block.grower.BirchTreeGrower
+ XXX.block.grower.DarkOakTreeGrower
- XXX.block.grower.JungleTreeGrower
+ XXX.block.grower.OakTreeGrower
+ XXX.block.grower.package-info
- XXX.block.grower.SpruceTreeGrower
+ XXX.block.piston.MovingPistonBlock
+ XXX.block.piston.package-info
- XXX.block.piston.PistonBaseBlock
+ XXX.block.piston.PistonBaseBlock$1
- XXX.block.piston.PistonHeadBlock
+ XXX.block.piston.PistonHeadBlock$1
- XXX.block.piston.PistonMovingBlockEntity
+ XXX.block.piston.PistonMovingBlockEntity$1
- XXX.block.piston.PistonStructureResolver
- XXX.block.state.AbstractStateHolder
+ XXX.block.state.AbstractStateHolder$1
- XXX.block.state.BlockState
+ XXX.block.state.BlockState$1
- XXX.block.state.BlockState$Cache
+ XXX.block.state.package-info
+ XXX.block.state.StateDefinition
- XXX.block.state.StateDefinition$Builder
+ XXX.block.state.StateDefinition$Factory
- XXX.block.state.StateHolder
+ XXX.boss.enderdragon.EndCrystal
- XXX.boss.enderdragon.EnderDragon
+ XXX.boss.enderdragon.package-info
- XXX.boss.wither.package-info
- XXX.boss.wither.WitherBoss
+ XXX.boss.wither.WitherBoss$WitherDoNothingGoal
- XXX.chunk.storage.ChunkSerializer
+ XXX.chunk.storage.ChunkStorage
- XXX.chunk.storage.OldChunkStorage
+ XXX.chunk.storage.OldChunkStorage$OldLevelChunk
- XXX.chunk.storage.package-info
- XXX.chunk.storage.RegionBitmap
+ XXX.chunk.storage.RegionFile
- XXX.chunk.storage.RegionFile$ChunkBuffer
+ XXX.chunk.storage.RegionFile$CommitOp
- XXX.chunk.storage.RegionFileStorage
+ XXX.chunk.storage.RegionFileVersion
- XXX.chunk.storage.RegionFileVersion$StreamWrapper
+ XXX.chunk.storage.SectionStorage
- XXX.core.dispenser.AbstractProjectileDispenseBehavior
+ XXX.core.dispenser.BoatDispenseItemBehavior
- XXX.core.dispenser.DefaultDispenseItemBehavior
+ XXX.core.dispenser.DispenseItemBehavior
- XXX.core.dispenser.DispenseItemBehavior$1
+ XXX.core.dispenser.DispenseItemBehavior$10
- XXX.core.dispenser.DispenseItemBehavior$11
+ XXX.core.dispenser.DispenseItemBehavior$12
- XXX.core.dispenser.DispenseItemBehavior$13
+ XXX.core.dispenser.DispenseItemBehavior$14
- XXX.core.dispenser.DispenseItemBehavior$15
+ XXX.core.dispenser.DispenseItemBehavior$16
- XXX.core.dispenser.DispenseItemBehavior$17
+ XXX.core.dispenser.DispenseItemBehavior$18
- XXX.core.dispenser.DispenseItemBehavior$19
+ XXX.core.dispenser.DispenseItemBehavior$2
- XXX.core.dispenser.DispenseItemBehavior$20
+ XXX.core.dispenser.DispenseItemBehavior$21
- XXX.core.dispenser.DispenseItemBehavior$3
+ XXX.core.dispenser.DispenseItemBehavior$4
- XXX.core.dispenser.DispenseItemBehavior$5
+ XXX.core.dispenser.DispenseItemBehavior$6
- XXX.core.dispenser.DispenseItemBehavior$7
+ XXX.core.dispenser.DispenseItemBehavior$7$1
- XXX.core.dispenser.DispenseItemBehavior$8
+ XXX.core.dispenser.DispenseItemBehavior$8$1
- XXX.core.dispenser.DispenseItemBehavior$9
+ XXX.core.dispenser.OptionalDispenseItemBehavior
+ XXX.core.dispenser.package-info
- XXX.core.dispenser.ShulkerBoxDispenseBehavior
+ XXX.core.particles.BlockParticleOption
- XXX.core.particles.BlockParticleOption$1
+ XXX.core.particles.DustParticleOptions
- XXX.core.particles.DustParticleOptions$1
+ XXX.core.particles.ItemParticleOption
- XXX.core.particles.ItemParticleOption$1
+ XXX.core.particles.package-info
+ XXX.core.particles.ParticleOptions
- XXX.core.particles.ParticleOptions$Deserializer
+ XXX.core.particles.ParticleType
- XXX.core.particles.ParticleTypes
+ XXX.core.particles.SimpleParticleType
- XXX.core.particles.SimpleParticleType$1
- XXX.data.advancements.AdvancementProvider
+ XXX.data.advancements.AdventureAdvancements
- XXX.data.advancements.HusbandryAdvancements
+ XXX.data.advancements.NetherAdvancements
- XXX.data.advancements.package-info
- XXX.data.advancements.StoryAdvancements
+ XXX.data.advancements.TheEndAdvancements
+ XXX.data.info.BlockListReport
- XXX.data.info.CommandsReport
- XXX.data.info.package-info
+ XXX.data.info.RegistryDumpReport
+ XXX.data.loot.BlockLoot
- XXX.data.loot.ChestLoot
+ XXX.data.loot.EntityLoot
- XXX.data.loot.FishingLoot
+ XXX.data.loot.GiftLoot
- XXX.data.loot.LootTableProvider
+ XXX.data.loot.package-info
+ XXX.data.recipes.FinishedRecipe
+ XXX.data.recipes.package-info
- XXX.data.recipes.RecipeProvider
+ XXX.data.recipes.ShapedRecipeBuilder
- XXX.data.recipes.ShapedRecipeBuilder$Result
+ XXX.data.recipes.ShapelessRecipeBuilder
- XXX.data.recipes.ShapelessRecipeBuilder$Result
+ XXX.data.recipes.SimpleCookingRecipeBuilder
- XXX.data.recipes.SimpleCookingRecipeBuilder$Result
+ XXX.data.recipes.SingleItemRecipeBuilder
- XXX.data.recipes.SingleItemRecipeBuilder$Result
+ XXX.data.recipes.SpecialRecipeBuilder
- XXX.data.recipes.SpecialRecipeBuilder$1
- XXX.data.structures.NbtToSnbt
+ XXX.data.structures.package-info
+ XXX.data.structures.SnbtToNbt
- XXX.data.structures.SnbtToNbt$Filter
+ XXX.data.structures.SnbtToNbt$TaskResult
- XXX.data.structures.StructureUpdater
- XXX.data.tags.BlockTagsProvider
+ XXX.data.tags.EntityTypeTagsProvider
- XXX.data.tags.FluidTagsProvider
+ XXX.data.tags.ItemTagsProvider
+ XXX.data.tags.package-info
- XXX.data.tags.TagsProvider
- XXX.dimension.end.DragonRespawnAnimation
+ XXX.dimension.end.DragonRespawnAnimation$1
- XXX.dimension.end.DragonRespawnAnimation$2
+ XXX.dimension.end.DragonRespawnAnimation$3
- XXX.dimension.end.DragonRespawnAnimation$4
+ XXX.dimension.end.DragonRespawnAnimation$5
- XXX.dimension.end.EndDragonFight
- XXX.dimension.end.package-info
+ XXX.dimension.end.TheEndDimension
- XXX.enderdragon.phases.AbstractDragonPhaseInstance
+ XXX.enderdragon.phases.AbstractDragonSittingPhase
- XXX.enderdragon.phases.DragonChargePlayerPhase
+ XXX.enderdragon.phases.DragonDeathPhase
- XXX.enderdragon.phases.DragonHoldingPatternPhase
+ XXX.enderdragon.phases.DragonHoverPhase
- XXX.enderdragon.phases.DragonLandingApproachPhase
+ XXX.enderdragon.phases.DragonLandingPhase
- XXX.enderdragon.phases.DragonPhaseInstance
+ XXX.enderdragon.phases.DragonSittingAttackingPhase
- XXX.enderdragon.phases.DragonSittingFlamingPhase
+ XXX.enderdragon.phases.DragonSittingScanningPhase
- XXX.enderdragon.phases.DragonStrafePlayerPhase
+ XXX.enderdragon.phases.DragonTakeoffPhase
- XXX.enderdragon.phases.EnderDragonPhase
+ XXX.enderdragon.phases.EnderDragonPhaseManager
- XXX.enderdragon.phases.package-info
+ XXX.entity.ai.Brain
+ XXX.entity.ai.package-info
- XXX.entity.ambient.AmbientCreature
+ XXX.entity.ambient.Bat
- XXX.entity.ambient.package-info
+ XXX.entity.animal.AbstractFish
- XXX.entity.animal.AbstractFish$FishMoveControl
+ XXX.entity.animal.AbstractFish$FishSwimGoal
- XXX.entity.animal.AbstractGolem
+ XXX.entity.animal.AbstractSchoolingFish
- XXX.entity.animal.AbstractSchoolingFish$SchoolSpawnGroupData
+ XXX.entity.animal.Animal
- XXX.entity.animal.Bee
+ XXX.entity.animal.Bee$1
- XXX.entity.animal.Bee$BaseBeeGoal
+ XXX.entity.animal.Bee$BeeAttackGoal
- XXX.entity.animal.Bee$BeeBecomeAngryTargetGoal
+ XXX.entity.animal.Bee$BeeEnterHiveGoal
- XXX.entity.animal.Bee$BeeGoToBlockGoal
+ XXX.entity.animal.Bee$BeeGoToHiveGoal
- XXX.entity.animal.Bee$BeeGoToKnownFlowerGoal
+ XXX.entity.animal.Bee$BeeGrowCropGoal
- XXX.entity.animal.Bee$BeeHurtByOtherGoal
+ XXX.entity.animal.Bee$BeeLocateHiveGoal
- XXX.entity.animal.Bee$BeeLookControl
+ XXX.entity.animal.Bee$BeePollinateGoal
- XXX.entity.animal.Bee$BeeWanderGoal
+ XXX.entity.animal.Cat
- XXX.entity.animal.Cat$CatAvoidEntityGoal
+ XXX.entity.animal.Cat$CatRelaxOnOwnerGoal
- XXX.entity.animal.Cat$CatTemptGoal
+ XXX.entity.animal.Chicken
- XXX.entity.animal.Cod
+ XXX.entity.animal.Cow
- XXX.entity.animal.Dolphin
+ XXX.entity.animal.Dolphin$1
- XXX.entity.animal.Dolphin$DolphinMoveControl
+ XXX.entity.animal.Dolphin$DolphinSwimToTreasureGoal
- XXX.entity.animal.Dolphin$DolphinSwimWithPlayerGoal
+ XXX.entity.animal.Dolphin$PlayWithItemsGoal
- XXX.entity.animal.FlyingAnimal
+ XXX.entity.animal.Fox
- XXX.entity.animal.Fox$1
+ XXX.entity.animal.Fox$DefendTrustedTargetGoal
- XXX.entity.animal.Fox$FaceplantGoal
+ XXX.entity.animal.Fox$FoxAlertableEntitiesSelector
- XXX.entity.animal.Fox$FoxBehaviorGoal
+ XXX.entity.animal.Fox$FoxBreedGoal
- XXX.entity.animal.Fox$FoxEatBerriesGoal
+ XXX.entity.animal.Fox$FoxFloatGoal
- XXX.entity.animal.Fox$FoxFollowParentGoal
+ XXX.entity.animal.Fox$FoxGroupData
- XXX.entity.animal.Fox$FoxLookAtPlayerGoal
+ XXX.entity.animal.Fox$FoxLookControl
- XXX.entity.animal.Fox$FoxMeleeAttackGoal
+ XXX.entity.animal.Fox$FoxMoveControl
- XXX.entity.animal.Fox$FoxPanicGoal
+ XXX.entity.animal.Fox$FoxPounceGoal
- XXX.entity.animal.Fox$FoxSearchForItemsGoal
+ XXX.entity.animal.Fox$FoxStrollThroughVillageGoal
- XXX.entity.animal.Fox$PerchAndSearchGoal
+ XXX.entity.animal.Fox$SeekShelterGoal
- XXX.entity.animal.Fox$SleepGoal
+ XXX.entity.animal.Fox$StalkPreyGoal
- XXX.entity.animal.Fox$Type
+ XXX.entity.animal.IronGolem
- XXX.entity.animal.MushroomCow
+ XXX.entity.animal.MushroomCow$MushroomType
- XXX.entity.animal.Ocelot
+ XXX.entity.animal.Ocelot$OcelotAvoidEntityGoal
- XXX.entity.animal.Ocelot$OcelotTemptGoal
- XXX.entity.animal.package-info
+ XXX.entity.animal.Panda
- XXX.entity.animal.Panda$Gene
+ XXX.entity.animal.Panda$PandaAttackGoal
- XXX.entity.animal.Panda$PandaAvoidGoal
+ XXX.entity.animal.Panda$PandaBreedGoal
- XXX.entity.animal.Panda$PandaHurtByTargetGoal
+ XXX.entity.animal.Panda$PandaLieOnBackGoal
- XXX.entity.animal.Panda$PandaLookAtPlayerGoal
+ XXX.entity.animal.Panda$PandaMoveControl
- XXX.entity.animal.Panda$PandaPanicGoal
+ XXX.entity.animal.Panda$PandaRollGoal
- XXX.entity.animal.Panda$PandaSitGoal
+ XXX.entity.animal.Panda$PandaSneezeGoal
- XXX.entity.animal.Parrot
+ XXX.entity.animal.Parrot$1
- XXX.entity.animal.Pig
+ XXX.entity.animal.PolarBear
- XXX.entity.animal.PolarBear$PolarBearAttackPlayersGoal
+ XXX.entity.animal.PolarBear$PolarBearHurtByTargetGoal
- XXX.entity.animal.PolarBear$PolarBearMeleeAttackGoal
+ XXX.entity.animal.PolarBear$PolarBearPanicGoal
- XXX.entity.animal.Pufferfish
+ XXX.entity.animal.Pufferfish$PufferfishPuffGoal
- XXX.entity.animal.Rabbit
+ XXX.entity.animal.Rabbit$EvilRabbitAttackGoal
- XXX.entity.animal.Rabbit$RabbitAvoidEntityGoal
+ XXX.entity.animal.Rabbit$RabbitGroupData
- XXX.entity.animal.Rabbit$RabbitJumpControl
+ XXX.entity.animal.Rabbit$RabbitMoveControl
- XXX.entity.animal.Rabbit$RabbitPanicGoal
+ XXX.entity.animal.Rabbit$RaidGardenGoal
- XXX.entity.animal.Salmon
+ XXX.entity.animal.Sheep
- XXX.entity.animal.Sheep$1
+ XXX.entity.animal.Sheep$2
- XXX.entity.animal.ShoulderRidingEntity
+ XXX.entity.animal.SnowGolem
- XXX.entity.animal.Squid
+ XXX.entity.animal.Squid$1
- XXX.entity.animal.Squid$SquidFleeGoal
+ XXX.entity.animal.Squid$SquidRandomMovementGoal
- XXX.entity.animal.TropicalFish
+ XXX.entity.animal.TropicalFish$1
- XXX.entity.animal.TropicalFish$Pattern
+ XXX.entity.animal.TropicalFish$TropicalFishGroupData
- XXX.entity.animal.Turtle
+ XXX.entity.animal.Turtle$1
- XXX.entity.animal.Turtle$TurtleBreedGoal
+ XXX.entity.animal.Turtle$TurtleGoHomeGoal
- XXX.entity.animal.Turtle$TurtleGoToWaterGoal
+ XXX.entity.animal.Turtle$TurtleLayEggGoal
- XXX.entity.animal.Turtle$TurtleMoveControl
+ XXX.entity.animal.Turtle$TurtlePanicGoal
- XXX.entity.animal.Turtle$TurtlePathNavigation
+ XXX.entity.animal.Turtle$TurtleRandomStrollGoal
- XXX.entity.animal.Turtle$TurtleTemptGoal
+ XXX.entity.animal.Turtle$TurtleTravelGoal
- XXX.entity.animal.WaterAnimal
+ XXX.entity.animal.Wolf
- XXX.entity.animal.Wolf$WolfAvoidEntityGoal
+ XXX.entity.boss.BossMob
- XXX.entity.boss.EnderDragonPart
+ XXX.entity.boss.package-info
+ XXX.entity.decoration.ArmorStand
- XXX.entity.decoration.ArmorStand$1
+ XXX.entity.decoration.HangingEntity
- XXX.entity.decoration.HangingEntity$1
+ XXX.entity.decoration.ItemFrame
- XXX.entity.decoration.ItemFrame$1
+ XXX.entity.decoration.LeashFenceKnotEntity
- XXX.entity.decoration.Motive
- XXX.entity.decoration.package-info
+ XXX.entity.decoration.Painting
+ XXX.entity.fishing.FishingHook
- XXX.entity.fishing.FishingHook$FishHookState
+ XXX.entity.fishing.package-info
- XXX.entity.global.LightningBolt
+ XXX.entity.global.package-info
- XXX.entity.item.FallingBlockEntity
+ XXX.entity.item.ItemEntity
+ XXX.entity.item.package-info
- XXX.entity.item.PrimedTnt
- XXX.entity.monster.AbstractIllager
+ XXX.entity.monster.AbstractIllager$IllagerArmPose
- XXX.entity.monster.AbstractIllager$RaiderOpenDoorGoal
+ XXX.entity.monster.AbstractSkeleton
- XXX.entity.monster.AbstractSkeleton$1
+ XXX.entity.monster.Blaze
- XXX.entity.monster.Blaze$BlazeAttackGoal
+ XXX.entity.monster.CaveSpider
- XXX.entity.monster.Creeper
+ XXX.entity.monster.CrossbowAttackMob
- XXX.entity.monster.Drowned
+ XXX.entity.monster.Drowned$DrownedAttackGoal
- XXX.entity.monster.Drowned$DrownedGoToBeachGoal
+ XXX.entity.monster.Drowned$DrownedGoToWaterGoal
- XXX.entity.monster.Drowned$DrownedMoveControl
+ XXX.entity.monster.Drowned$DrownedSwimUpGoal
- XXX.entity.monster.Drowned$DrownedTridentAttackGoal
+ XXX.entity.monster.ElderGuardian
- XXX.entity.monster.EnderMan
+ XXX.entity.monster.EnderMan$EndermanFreezeWhenLookedAt
- XXX.entity.monster.EnderMan$EndermanLeaveBlockGoal
+ XXX.entity.monster.EnderMan$EndermanLookForPlayerGoal
- XXX.entity.monster.EnderMan$EndermanTakeBlockGoal
+ XXX.entity.monster.Endermite
- XXX.entity.monster.Enemy
+ XXX.entity.monster.Evoker
- XXX.entity.monster.Evoker$1
+ XXX.entity.monster.Evoker$EvokerAttackSpellGoal
- XXX.entity.monster.Evoker$EvokerCastingSpellGoal
+ XXX.entity.monster.Evoker$EvokerSummonSpellGoal
- XXX.entity.monster.Evoker$EvokerWololoSpellGoal
+ XXX.entity.monster.Ghast
- XXX.entity.monster.Ghast$GhastLookGoal
+ XXX.entity.monster.Ghast$GhastMoveControl
- XXX.entity.monster.Ghast$GhastShootFireballGoal
+ XXX.entity.monster.Ghast$RandomFloatAroundGoal
- XXX.entity.monster.Giant
+ XXX.entity.monster.Guardian
- XXX.entity.monster.Guardian$GuardianAttackGoal
+ XXX.entity.monster.Guardian$GuardianAttackSelector
- XXX.entity.monster.Guardian$GuardianMoveControl
+ XXX.entity.monster.Husk
- XXX.entity.monster.Illusioner
+ XXX.entity.monster.Illusioner$1
- XXX.entity.monster.Illusioner$IllusionerBlindnessSpellGoal
+ XXX.entity.monster.Illusioner$IllusionerMirrorSpellGoal
- XXX.entity.monster.MagmaCube
+ XXX.entity.monster.Monster
- XXX.entity.monster.package-info
- XXX.entity.monster.PatrollingMonster
+ XXX.entity.monster.PatrollingMonster$LongDistancePatrolGoal
- XXX.entity.monster.Phantom
+ XXX.entity.monster.Phantom$1
- XXX.entity.monster.Phantom$AttackPhase
+ XXX.entity.monster.Phantom$PhantomAttackPlayerTargetGoal
- XXX.entity.monster.Phantom$PhantomAttackStrategyGoal
+ XXX.entity.monster.Phantom$PhantomBodyRotationControl
- XXX.entity.monster.Phantom$PhantomCircleAroundAnchorGoal
+ XXX.entity.monster.Phantom$PhantomLookControl
- XXX.entity.monster.Phantom$PhantomMoveControl
+ XXX.entity.monster.Phantom$PhantomMoveTargetGoal
- XXX.entity.monster.Phantom$PhantomSweepAttackGoal
+ XXX.entity.monster.PigZombie
- XXX.entity.monster.PigZombie$PigZombieAngerTargetGoal
+ XXX.entity.monster.PigZombie$PigZombieHurtByOtherGoal
- XXX.entity.monster.Pillager
+ XXX.entity.monster.RangedAttackMob
- XXX.entity.monster.Ravager
+ XXX.entity.monster.Ravager$1
- XXX.entity.monster.Ravager$RavagerMeleeAttackGoal
+ XXX.entity.monster.Ravager$RavagerNavigation
- XXX.entity.monster.Ravager$RavagerNodeEvaluator
+ XXX.entity.monster.SharedMonsterAttributes
- XXX.entity.monster.Shulker
+ XXX.entity.monster.Shulker$1
- XXX.entity.monster.Shulker$ShulkerAttackGoal
+ XXX.entity.monster.Shulker$ShulkerBodyRotationControl
- XXX.entity.monster.Shulker$ShulkerDefenseAttackGoal
+ XXX.entity.monster.Shulker$ShulkerNearestAttackGoal
- XXX.entity.monster.Shulker$ShulkerPeekGoal
+ XXX.entity.monster.Silverfish
- XXX.entity.monster.Silverfish$SilverfishMergeWithStoneGoal
+ XXX.entity.monster.Silverfish$SilverfishWakeUpFriendsGoal
- XXX.entity.monster.Skeleton
+ XXX.entity.monster.Slime
- XXX.entity.monster.Slime$SlimeAttackGoal
+ XXX.entity.monster.Slime$SlimeFloatGoal
- XXX.entity.monster.Slime$SlimeKeepOnJumpingGoal
+ XXX.entity.monster.Slime$SlimeMoveControl
- XXX.entity.monster.Slime$SlimeRandomDirectionGoal
+ XXX.entity.monster.SpellcasterIllager
- XXX.entity.monster.SpellcasterIllager$IllagerSpell
+ XXX.entity.monster.SpellcasterIllager$SpellcasterCastingSpellGoal
- XXX.entity.monster.SpellcasterIllager$SpellcasterUseSpellGoal
+ XXX.entity.monster.Spider
- XXX.entity.monster.Spider$SpiderAttackGoal
+ XXX.entity.monster.Spider$SpiderEffectsGroupData
- XXX.entity.monster.Spider$SpiderTargetGoal
+ XXX.entity.monster.Stray
- XXX.entity.monster.Vex
+ XXX.entity.monster.Vex$VexChargeAttackGoal
- XXX.entity.monster.Vex$VexCopyOwnerTargetGoal
+ XXX.entity.monster.Vex$VexMoveControl
- XXX.entity.monster.Vex$VexRandomMoveGoal
+ XXX.entity.monster.Vindicator
- XXX.entity.monster.Vindicator$VindicatorBreakDoorGoal
+ XXX.entity.monster.Vindicator$VindicatorJohnnyAttackGoal
- XXX.entity.monster.Vindicator$VindicatorMeleeAttackGoal
+ XXX.entity.monster.Witch
- XXX.entity.monster.WitherSkeleton
+ XXX.entity.monster.Zombie
- XXX.entity.monster.Zombie$1
+ XXX.entity.monster.Zombie$ZombieAttackTurtleEggGoal
- XXX.entity.monster.Zombie$ZombieGroupData
+ XXX.entity.monster.ZombieVillager
+ XXX.entity.npc.AbstractVillager
- XXX.entity.npc.CatSpawner
+ XXX.entity.npc.ClientSideMerchant
- XXX.entity.npc.Npc
- XXX.entity.npc.package-info
+ XXX.entity.npc.Villager
- XXX.entity.npc.VillagerData
+ XXX.entity.npc.VillagerDataHolder
- XXX.entity.npc.VillagerProfession
+ XXX.entity.npc.VillagerTrades
- XXX.entity.npc.VillagerTrades$DyedArmorForEmeralds
+ XXX.entity.npc.VillagerTrades$EmeraldForItems
- XXX.entity.npc.VillagerTrades$EmeraldsForVillagerTypeItem
+ XXX.entity.npc.VillagerTrades$EnchantBookForEmeralds
- XXX.entity.npc.VillagerTrades$EnchantedItemForEmeralds
+ XXX.entity.npc.VillagerTrades$ItemListing
- XXX.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
+ XXX.entity.npc.VillagerTrades$ItemsForEmeralds
- XXX.entity.npc.VillagerTrades$SuspisciousStewForEmerald
+ XXX.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
- XXX.entity.npc.VillagerTrades$TreasureMapForEmeralds
+ XXX.entity.npc.VillagerType
- XXX.entity.npc.VillagerType$1
+ XXX.entity.npc.WanderingTrader
- XXX.entity.npc.WanderingTrader$WanderToPositionGoal
+ XXX.entity.npc.WanderingTraderSpawner
- XXX.entity.player.Abilities
+ XXX.entity.player.ChatVisiblity
- XXX.entity.player.Inventory
+ XXX.entity.player.package-info
+ XXX.entity.player.Player
- XXX.entity.player.Player$1
+ XXX.entity.player.Player$BedSleepingProblem
- XXX.entity.player.PlayerModelPart
+ XXX.entity.player.StackedContents
- XXX.entity.player.StackedContents$RecipePicker
- XXX.entity.projectile.AbstractArrow
+ XXX.entity.projectile.AbstractArrow$Pickup
- XXX.entity.projectile.AbstractHurtingProjectile
+ XXX.entity.projectile.Arrow
- XXX.entity.projectile.DragonFireball
+ XXX.entity.projectile.EvokerFangs
- XXX.entity.projectile.EyeOfEnder
+ XXX.entity.projectile.Fireball
- XXX.entity.projectile.FireworkRocketEntity
+ XXX.entity.projectile.ItemSupplier
- XXX.entity.projectile.LargeFireball
+ XXX.entity.projectile.LlamaSpit
- XXX.entity.projectile.package-info
- XXX.entity.projectile.Projectile
+ XXX.entity.projectile.ProjectileUtil
- XXX.entity.projectile.ShulkerBullet
+ XXX.entity.projectile.SmallFireball
- XXX.entity.projectile.Snowball
+ XXX.entity.projectile.SpectralArrow
- XXX.entity.projectile.ThrowableItemProjectile
+ XXX.entity.projectile.ThrowableProjectile
- XXX.entity.projectile.ThrownEgg
+ XXX.entity.projectile.ThrownEnderpearl
- XXX.entity.projectile.ThrownExperienceBottle
+ XXX.entity.projectile.ThrownPotion
- XXX.entity.projectile.ThrownTrident
+ XXX.entity.projectile.WitherSkull
+ XXX.entity.raid.package-info
+ XXX.entity.raid.Raid
- XXX.entity.raid.Raid$1
- XXX.entity.raid.Raid$RaiderType
+ XXX.entity.raid.Raid$RaidStatus
+ XXX.entity.raid.Raider
- XXX.entity.raid.Raider$HoldGroundAttackGoal
+ XXX.entity.raid.Raider$ObtainRaidLeaderBannerGoal
- XXX.entity.raid.Raider$RaiderCelebration
+ XXX.entity.raid.Raider$RaiderMoveThroughVillageGoal
- XXX.entity.raid.Raids
- XXX.entity.schedule.Activity
+ XXX.entity.schedule.Keyframe
- XXX.entity.schedule.package-info
- XXX.entity.schedule.Schedule
+ XXX.entity.schedule.ScheduleBuilder
- XXX.entity.schedule.ScheduleBuilder$ActivityTransition
+ XXX.entity.schedule.Timeline
+ XXX.entity.vehicle.AbstractMinecart
- XXX.entity.vehicle.AbstractMinecart$1
+ XXX.entity.vehicle.AbstractMinecart$Type
- XXX.entity.vehicle.AbstractMinecartContainer
+ XXX.entity.vehicle.Boat
- XXX.entity.vehicle.Boat$1
+ XXX.entity.vehicle.Boat$Status
- XXX.entity.vehicle.Boat$Type
+ XXX.entity.vehicle.Minecart
- XXX.entity.vehicle.MinecartChest
+ XXX.entity.vehicle.MinecartCommandBlock
- XXX.entity.vehicle.MinecartCommandBlock$MinecartCommandBase
+ XXX.entity.vehicle.MinecartFurnace
- XXX.entity.vehicle.MinecartHopper
+ XXX.entity.vehicle.MinecartSpawner
- XXX.entity.vehicle.MinecartSpawner$1
+ XXX.entity.vehicle.MinecartTNT
- XXX.entity.vehicle.package-info
+ XXX.feature.structures.EmptyPoolElement
- XXX.feature.structures.FeaturePoolElement
+ XXX.feature.structures.JigsawJunction
- XXX.feature.structures.JigsawPlacement
+ XXX.feature.structures.JigsawPlacement$1
- XXX.feature.structures.JigsawPlacement$PieceFactory
+ XXX.feature.structures.JigsawPlacement$PieceState
- XXX.feature.structures.JigsawPlacement$Placer
+ XXX.feature.structures.ListPoolElement
- XXX.feature.structures.package-info
- XXX.feature.structures.SinglePoolElement
+ XXX.feature.structures.StructurePoolElement
- XXX.feature.structures.StructurePoolElementType
+ XXX.feature.structures.StructureTemplatePool
- XXX.feature.structures.StructureTemplatePool$Projection
+ XXX.feature.structures.StructureTemplatePools
- XXX.gametest.framework.BeforeBatch
+ XXX.gametest.framework.GameTest
- XXX.gametest.framework.GameTestAssertException
+ XXX.gametest.framework.GameTestAssertPosException
- XXX.gametest.framework.GameTestBatch
+ XXX.gametest.framework.GameTestBatchRunner
- XXX.gametest.framework.GameTestBatchRunner$1
+ XXX.gametest.framework.GameTestGenerator
- XXX.gametest.framework.GameTestHelper
+ XXX.gametest.framework.GameTestInfo
- XXX.gametest.framework.GameTestListener
+ XXX.gametest.framework.GameTestRegistry
- XXX.gametest.framework.GameTestRunner
+ XXX.gametest.framework.GameTestRunner$1
- XXX.gametest.framework.GameTestServer
+ XXX.gametest.framework.GameTestServer$1
- XXX.gametest.framework.GameTestTicker
+ XXX.gametest.framework.GameTestTimeoutException
- XXX.gametest.framework.LogTestReporter
+ XXX.gametest.framework.MultipleTestTracker
- XXX.gametest.framework.package-info
- XXX.gametest.framework.StructureUtils
+ XXX.gametest.framework.TeamcityTestReporter
- XXX.gametest.framework.TestClassNameArgument
+ XXX.gametest.framework.TestCommand
- XXX.gametest.framework.TestCommand$TestSummaryDisplayer
+ XXX.gametest.framework.TestFunction
- XXX.gametest.framework.TestFunctionArgument
+ XXX.gametest.framework.TestReporter
+ XXX.goal.target.DefendVillageTargetGoal
- XXX.goal.target.HurtByTargetGoal
+ XXX.goal.target.NearestAttackableTargetGoal
- XXX.goal.target.NearestAttackableWitchTargetGoal
+ XXX.goal.target.NearestHealableRaiderTargetGoal
- XXX.goal.target.NonTameRandomTargetGoal
+ XXX.goal.target.OwnerHurtByTargetGoal
- XXX.goal.target.OwnerHurtTargetGoal
- XXX.goal.target.package-info
+ XXX.goal.target.TargetGoal
- XXX.item.alchemy.package-info
+ XXX.item.alchemy.Potion
- XXX.item.alchemy.PotionBrewing
+ XXX.item.alchemy.PotionBrewing$Mix
+ XXX.item.alchemy.Potions
- XXX.item.alchemy.PotionUtils
+ XXX.item.crafting.AbstractCookingRecipe
- XXX.item.crafting.ArmorDyeRecipe
+ XXX.item.crafting.BannerDuplicateRecipe
- XXX.item.crafting.BlastingRecipe
+ XXX.item.crafting.BookCloningRecipe
- XXX.item.crafting.CampfireCookingRecipe
+ XXX.item.crafting.CraftingRecipe
- XXX.item.crafting.CustomRecipe
+ XXX.item.crafting.FireworkRocketRecipe
- XXX.item.crafting.FireworkStarFadeRecipe
+ XXX.item.crafting.FireworkStarRecipe
- XXX.item.crafting.Ingredient
+ XXX.item.crafting.Ingredient$1
- XXX.item.crafting.Ingredient$ItemValue
+ XXX.item.crafting.Ingredient$TagValue
- XXX.item.crafting.Ingredient$Value
+ XXX.item.crafting.MapCloningRecipe
- XXX.item.crafting.MapExtendingRecipe
- XXX.item.crafting.package-info
+ XXX.item.crafting.Recipe
- XXX.item.crafting.RecipeManager
+ XXX.item.crafting.RecipeSerializer
- XXX.item.crafting.RecipeType
+ XXX.item.crafting.RecipeType$1
- XXX.item.crafting.RepairItemRecipe
+ XXX.item.crafting.ShapedRecipe
- XXX.item.crafting.ShapedRecipe$Serializer
+ XXX.item.crafting.ShapelessRecipe
- XXX.item.crafting.ShapelessRecipe$Serializer
+ XXX.item.crafting.ShieldDecorationRecipe
- XXX.item.crafting.ShulkerBoxColoring
+ XXX.item.crafting.SimpleCookingSerializer
- XXX.item.crafting.SimpleCookingSerializer$CookieBaker
+ XXX.item.crafting.SimpleRecipeSerializer
- XXX.item.crafting.SingleItemRecipe
+ XXX.item.crafting.SingleItemRecipe$Serializer
- XXX.item.crafting.SingleItemRecipe$Serializer$SingleItemMaker
+ XXX.item.crafting.SmeltingRecipe
- XXX.item.crafting.SmokingRecipe
+ XXX.item.crafting.StonecutterRecipe
- XXX.item.crafting.SuspiciousStewRecipe
+ XXX.item.crafting.TippedArrowRecipe
+ XXX.item.enchantment.ArrowDamageEnchantment
- XXX.item.enchantment.ArrowFireEnchantment
+ XXX.item.enchantment.ArrowInfiniteEnchantment
- XXX.item.enchantment.ArrowKnockbackEnchantment
+ XXX.item.enchantment.ArrowPiercingEnchantment
- XXX.item.enchantment.BindingCurseEnchantment
+ XXX.item.enchantment.DamageEnchantment
- XXX.item.enchantment.DigDurabilityEnchantment
+ XXX.item.enchantment.DiggingEnchantment
- XXX.item.enchantment.Enchantment
+ XXX.item.enchantment.Enchantment$Rarity
- XXX.item.enchantment.EnchantmentCategory
+ XXX.item.enchantment.EnchantmentCategory$1
- XXX.item.enchantment.EnchantmentCategory$10
+ XXX.item.enchantment.EnchantmentCategory$11
- XXX.item.enchantment.EnchantmentCategory$12
+ XXX.item.enchantment.EnchantmentCategory$13
- XXX.item.enchantment.EnchantmentCategory$14
+ XXX.item.enchantment.EnchantmentCategory$2
- XXX.item.enchantment.EnchantmentCategory$3
+ XXX.item.enchantment.EnchantmentCategory$4
- XXX.item.enchantment.EnchantmentCategory$5
+ XXX.item.enchantment.EnchantmentCategory$6
- XXX.item.enchantment.EnchantmentCategory$7
+ XXX.item.enchantment.EnchantmentCategory$8
- XXX.item.enchantment.EnchantmentCategory$9
+ XXX.item.enchantment.EnchantmentHelper
- XXX.item.enchantment.EnchantmentHelper$EnchantmentVisitor
+ XXX.item.enchantment.EnchantmentInstance
- XXX.item.enchantment.Enchantments
+ XXX.item.enchantment.FireAspectEnchantment
- XXX.item.enchantment.FishingSpeedEnchantment
+ XXX.item.enchantment.FrostWalkerEnchantment
- XXX.item.enchantment.KnockbackEnchantment
+ XXX.item.enchantment.LootBonusEnchantment
- XXX.item.enchantment.MendingEnchantment
+ XXX.item.enchantment.MultiShotEnchantment
- XXX.item.enchantment.OxygenEnchantment
- XXX.item.enchantment.package-info
+ XXX.item.enchantment.ProtectionEnchantment
- XXX.item.enchantment.ProtectionEnchantment$Type
+ XXX.item.enchantment.QuickChargeEnchantment
- XXX.item.enchantment.SweepingEdgeEnchantment
+ XXX.item.enchantment.ThornsEnchantment
- XXX.item.enchantment.TridentChannelingEnchantment
+ XXX.item.enchantment.TridentImpalerEnchantment
- XXX.item.enchantment.TridentLoyaltyEnchantment
+ XXX.item.enchantment.TridentRiptideEnchantment
- XXX.item.enchantment.UntouchingEnchantment
+ XXX.item.enchantment.VanishingCurseEnchantment
- XXX.item.enchantment.WaterWalkerEnchantment
+ XXX.item.enchantment.WaterWorkerEnchantment
- XXX.item.trading.Merchant
+ XXX.item.trading.MerchantOffer
- XXX.item.trading.MerchantOffers
+ XXX.item.trading.package-info
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
- XXX.level.biome.BadlandsBiome
+ XXX.level.biome.BadlandsPlateauBiome
- XXX.level.biome.BambooJungleBiome
+ XXX.level.biome.BambooJungleHillsBiome
- XXX.level.biome.BeachBiome
+ XXX.level.biome.Biome
- XXX.level.biome.Biome$1
+ XXX.level.biome.Biome$BiomeBuilder
- XXX.level.biome.Biome$BiomeCategory
+ XXX.level.biome.Biome$BiomeTempCategory
- XXX.level.biome.Biome$Precipitation
+ XXX.level.biome.Biome$SpawnerData
- XXX.level.biome.BiomeDefaultFeatures
+ XXX.level.biome.BiomeManager
- XXX.level.biome.BiomeManager$NoiseBiomeSource
+ XXX.level.biome.Biomes
+ XXX.level.biome.BiomeSource
- XXX.level.biome.BiomeSourceSettings
+ XXX.level.biome.BiomeSourceType
- XXX.level.biome.BiomeZoomer
- XXX.level.biome.BirchForestBiome
+ XXX.level.biome.BirchForestHillsBiome
- XXX.level.biome.CheckerboardBiomeSourceSettings
+ XXX.level.biome.CheckerboardColumnBiomeSource
- XXX.level.biome.ColdOceanBiome
+ XXX.level.biome.DarkForestBiome
- XXX.level.biome.DarkForestHillsBiome
+ XXX.level.biome.DeepColdOceanBiome
- XXX.level.biome.DeepFrozenOceanBiome
+ XXX.level.biome.DeepLukeWarmOceanBiome
- XXX.level.biome.DeepOceanBiome
+ XXX.level.biome.DeepWarmOceanBiome
- XXX.level.biome.DesertBiome
+ XXX.level.biome.DesertHillsBiome
- XXX.level.biome.DesertLakesBiome
+ XXX.level.biome.EndBarrensBiome
- XXX.level.biome.EndHighlandsBiome
+ XXX.level.biome.EndMidlandsBiome
- XXX.level.biome.ErodedBadlandsBiome
+ XXX.level.biome.FixedBiomeSource
- XXX.level.biome.FixedBiomeSourceSettings
+ XXX.level.biome.ForestBiome
- XXX.level.biome.ForestFlowerBiome
+ XXX.level.biome.FrozenOceanBiome
- XXX.level.biome.FrozenRiverBiome
+ XXX.level.biome.FuzzyOffsetBiomeZoomer
- XXX.level.biome.FuzzyOffsetConstantColumnBiomeZoomer
+ XXX.level.biome.GiantSpruceTaigaBiome
- XXX.level.biome.GiantSpruceTaigaHillsMutatedBiome
+ XXX.level.biome.GiantTreeTaigaBiome
- XXX.level.biome.GiantTreeTaigaHillsBiome
+ XXX.level.biome.GravellyMountainsBiome
- XXX.level.biome.IceSpikesBiome
+ XXX.level.biome.JungleBiome
- XXX.level.biome.JungleEdgeBiome
+ XXX.level.biome.JungleHillsBiome
- XXX.level.biome.LukeWarmOceanBiome
+ XXX.level.biome.ModifiedBadlandsPlateauBiome
- XXX.level.biome.ModifiedGravellyMountainsBiome
+ XXX.level.biome.ModifiedJungleBiome
- XXX.level.biome.ModifiedJungleEdgeBiome
+ XXX.level.biome.ModifiedWoodedBadlandsPlateauBiome
- XXX.level.biome.MountainBiome
+ XXX.level.biome.MountainEdgeBiome
- XXX.level.biome.MushroomFieldsBiome
+ XXX.level.biome.MushroomFieldsShoreBiome
- XXX.level.biome.NearestNeighborBiomeZoomer
+ XXX.level.biome.NetherBiome
- XXX.level.biome.OceanBiome
+ XXX.level.biome.OverworldBiomeSource
- XXX.level.biome.OverworldBiomeSourceSettings
+ XXX.level.biome.package-info
+ XXX.level.biome.PlainsBiome
- XXX.level.biome.RiverBiome
+ XXX.level.biome.SavannaBiome
- XXX.level.biome.SavannaPlateauBiome
+ XXX.level.biome.ShatteredSavannaBiome
- XXX.level.biome.ShatteredSavannaPlateauBiome
+ XXX.level.biome.SmallEndIslandsBiome
- XXX.level.biome.SnowyBeachBiome
+ XXX.level.biome.SnowyMountainsBiome
- XXX.level.biome.SnowyTaigaBiome
+ XXX.level.biome.SnowyTaigaHillsBiome
- XXX.level.biome.SnowyTaigaMountainsBiome
+ XXX.level.biome.SnowyTundraBiome
- XXX.level.biome.StoneShoreBiome
+ XXX.level.biome.SunflowerPlainsBiome
- XXX.level.biome.SwampBiome
+ XXX.level.biome.SwampHillsBiome
- XXX.level.biome.TaigaBiome
+ XXX.level.biome.TaigaHillsBiome
- XXX.level.biome.TaigaMountainsBiome
+ XXX.level.biome.TallBirchForestBiome
- XXX.level.biome.TallBirchHillsBiome
+ XXX.level.biome.TheEndBiome
- XXX.level.biome.TheEndBiomeSource
+ XXX.level.biome.TheEndBiomeSourceSettings
- XXX.level.biome.TheVoidBiome
+ XXX.level.biome.WarmOceanBiome
- XXX.level.biome.WoodedBadlandsBiome
+ XXX.level.biome.WoodedHillsBiome
- XXX.level.biome.WoodedMountainBiome
- XXX.level.block.AbstractBannerBlock
+ XXX.level.block.AbstractFurnaceBlock
- XXX.level.block.AbstractGlassBlock
+ XXX.level.block.AbstractSkullBlock
- XXX.level.block.AirBlock
+ XXX.level.block.AnvilBlock
- XXX.level.block.AttachedStemBlock
+ XXX.level.block.BambooBlock
- XXX.level.block.BambooSaplingBlock
+ XXX.level.block.BannerBlock
- XXX.level.block.BarrelBlock
+ XXX.level.block.BarrierBlock
- XXX.level.block.BaseCoralFanBlock
+ XXX.level.block.BaseCoralPlantBlock
- XXX.level.block.BaseCoralPlantTypeBlock
+ XXX.level.block.BaseCoralWallFanBlock
- XXX.level.block.BaseEntityBlock
+ XXX.level.block.BasePressurePlateBlock
- XXX.level.block.BaseRailBlock
+ XXX.level.block.BeaconBeamBlock
- XXX.level.block.BeaconBlock
+ XXX.level.block.BedBlock
- XXX.level.block.BedBlock$1
+ XXX.level.block.BedrockBlock
- XXX.level.block.BeehiveBlock
+ XXX.level.block.BeetrootBlock
- XXX.level.block.BellBlock
+ XXX.level.block.BellBlock$1
- XXX.level.block.BlastFurnaceBlock
+ XXX.level.block.Block
- XXX.level.block.Block$1
+ XXX.level.block.Block$2
- XXX.level.block.Block$3
+ XXX.level.block.Block$BlockStatePairKey
- XXX.level.block.Block$OffsetType
+ XXX.level.block.Block$Properties
- XXX.level.block.Blocks
+ XXX.level.block.BonemealableBlock
- XXX.level.block.BrewingStandBlock
+ XXX.level.block.BubbleColumnBlock
- XXX.level.block.BucketPickup
+ XXX.level.block.BushBlock
- XXX.level.block.ButtonBlock
+ XXX.level.block.ButtonBlock$1
- XXX.level.block.CactusBlock
+ XXX.level.block.CakeBlock
- XXX.level.block.CampfireBlock
+ XXX.level.block.CarrotBlock
- XXX.level.block.CartographyTableBlock
+ XXX.level.block.CarvedPumpkinBlock
- XXX.level.block.CauldronBlock
+ XXX.level.block.ChestBlock
- XXX.level.block.ChestBlock$1
+ XXX.level.block.ChestBlock$2
- XXX.level.block.ChestBlock$2$1
+ XXX.level.block.ChestBlock$3
- XXX.level.block.ChestBlock$ChestSearchCallback
+ XXX.level.block.ChorusFlowerBlock
- XXX.level.block.ChorusPlantBlock
+ XXX.level.block.CocoaBlock
- XXX.level.block.CocoaBlock$1
+ XXX.level.block.CommandBlock
- XXX.level.block.ComparatorBlock
+ XXX.level.block.ComposterBlock
- XXX.level.block.ComposterBlock$EmptyContainer
+ XXX.level.block.ComposterBlock$InputContainer
- XXX.level.block.ComposterBlock$OutputContainer
+ XXX.level.block.ConcretePowderBlock
- XXX.level.block.ConduitBlock
+ XXX.level.block.CoralBlock
- XXX.level.block.CoralFanBlock
+ XXX.level.block.CoralPlantBlock
- XXX.level.block.CoralWallFanBlock
+ XXX.level.block.CraftingTableBlock
- XXX.level.block.CropBlock
+ XXX.level.block.CrossCollisionBlock
- XXX.level.block.CrossCollisionBlock$1
+ XXX.level.block.DaylightDetectorBlock
- XXX.level.block.DeadBushBlock
+ XXX.level.block.DetectorRailBlock
- XXX.level.block.DetectorRailBlock$1
+ XXX.level.block.DiodeBlock
- XXX.level.block.DirectionalBlock
+ XXX.level.block.DispenserBlock
- XXX.level.block.DoorBlock
+ XXX.level.block.DoorBlock$1
- XXX.level.block.DoublePlantBlock
+ XXX.level.block.DragonEggBlock
- XXX.level.block.DropperBlock
+ XXX.level.block.EnchantmentTableBlock
+ XXX.level.block.EnderChestBlock
- XXX.level.block.EndGatewayBlock
+ XXX.level.block.EndPortalBlock
- XXX.level.block.EndPortalFrameBlock
+ XXX.level.block.EndRodBlock
- XXX.level.block.EndRodBlock$1
- XXX.level.block.EntityBlock
+ XXX.level.block.FaceAttachedHorizontalDirectionalBlock
- XXX.level.block.FaceAttachedHorizontalDirectionalBlock$1
+ XXX.level.block.FallingBlock
- XXX.level.block.FarmBlock
+ XXX.level.block.FenceBlock
- XXX.level.block.FenceGateBlock
+ XXX.level.block.FenceGateBlock$1
- XXX.level.block.FireBlock
+ XXX.level.block.FletchingTableBlock
- XXX.level.block.FlowerBlock
+ XXX.level.block.FlowerPotBlock
- XXX.level.block.FrostedIceBlock
+ XXX.level.block.FurnaceBlock
- XXX.level.block.GlassBlock
+ XXX.level.block.GlazedTerracottaBlock
- XXX.level.block.GrassBlock
+ XXX.level.block.GrassPathBlock
- XXX.level.block.GravelBlock
+ XXX.level.block.GrindstoneBlock
- XXX.level.block.GrindstoneBlock$1
+ XXX.level.block.HalfTransparentBlock
- XXX.level.block.HayBlock
+ XXX.level.block.HopperBlock
- XXX.level.block.HopperBlock$1
+ XXX.level.block.HorizontalDirectionalBlock
- XXX.level.block.HugeMushroomBlock
+ XXX.level.block.IceBlock
- XXX.level.block.InfestedBlock
+ XXX.level.block.IronBarsBlock
- XXX.level.block.JigsawBlock
+ XXX.level.block.JukeboxBlock
- XXX.level.block.KelpBlock
+ XXX.level.block.KelpPlantBlock
- XXX.level.block.LadderBlock
+ XXX.level.block.LadderBlock$1
- XXX.level.block.Lantern
+ XXX.level.block.LeavesBlock
- XXX.level.block.LecternBlock
+ XXX.level.block.LecternBlock$1
- XXX.level.block.LevelEvent
+ XXX.level.block.LeverBlock
- XXX.level.block.LeverBlock$1
+ XXX.level.block.LiquidBlock
- XXX.level.block.LiquidBlockContainer
+ XXX.level.block.LogBlock
- XXX.level.block.LoomBlock
+ XXX.level.block.MagmaBlock
- XXX.level.block.MelonBlock
+ XXX.level.block.Mirror
- XXX.level.block.Mirror$1
+ XXX.level.block.MushroomBlock
- XXX.level.block.MyceliumBlock
+ XXX.level.block.NetherPortalBlock
- XXX.level.block.NetherPortalBlock$1
+ XXX.level.block.NetherPortalBlock$PortalShape
- XXX.level.block.NetherWartBlock
+ XXX.level.block.NoteBlock
- XXX.level.block.ObserverBlock
+ XXX.level.block.OreBlock
- XXX.level.block.package-info
- XXX.level.block.PipeBlock
+ XXX.level.block.PlayerHeadBlock
- XXX.level.block.PlayerWallHeadBlock
+ XXX.level.block.PotatoBlock
- XXX.level.block.PoweredBlock
+ XXX.level.block.PoweredRailBlock
- XXX.level.block.PoweredRailBlock$1
+ XXX.level.block.PressurePlateBlock
- XXX.level.block.PressurePlateBlock$1
+ XXX.level.block.PressurePlateBlock$Sensitivity
- XXX.level.block.PumpkinBlock
+ XXX.level.block.RailBlock
- XXX.level.block.RailBlock$1
+ XXX.level.block.RailState
- XXX.level.block.RailState$1
- XXX.level.block.RedstoneLampBlock
+ XXX.level.block.RedStoneOreBlock
+ XXX.level.block.RedstoneTorchBlock
- XXX.level.block.RedstoneTorchBlock$Toggle
+ XXX.level.block.RedstoneWallTorchBlock
- XXX.level.block.RedStoneWireBlock
+ XXX.level.block.RedStoneWireBlock$1
- XXX.level.block.RenderShape
+ XXX.level.block.RepeaterBlock
- XXX.level.block.RotatedPillarBlock
+ XXX.level.block.RotatedPillarBlock$1
- XXX.level.block.Rotation
+ XXX.level.block.Rotation$1
- XXX.level.block.SandBlock
+ XXX.level.block.SaplingBlock
- XXX.level.block.ScaffoldingBlock
- XXX.level.block.Seagrass
+ XXX.level.block.SeaPickleBlock
+ XXX.level.block.ShearableDoublePlantBlock
- XXX.level.block.ShulkerBoxBlock
+ XXX.level.block.ShulkerBoxBlock$1
- XXX.level.block.SignBlock
+ XXX.level.block.SimpleWaterloggedBlock
- XXX.level.block.SkullBlock
+ XXX.level.block.SkullBlock$Type
- XXX.level.block.SkullBlock$Types
+ XXX.level.block.SlabBlock
- XXX.level.block.SlabBlock$1
+ XXX.level.block.SlimeBlock
- XXX.level.block.SmithingTableBlock
+ XXX.level.block.SmokerBlock
- XXX.level.block.SnowLayerBlock
+ XXX.level.block.SnowLayerBlock$1
- XXX.level.block.SnowyDirtBlock
+ XXX.level.block.SoulsandBlock
- XXX.level.block.SoundType
+ XXX.level.block.SpawnerBlock
- XXX.level.block.SpongeBlock
+ XXX.level.block.SpreadingSnowyDirtBlock
- XXX.level.block.StainedGlassBlock
+ XXX.level.block.StainedGlassPaneBlock
- XXX.level.block.StairBlock
+ XXX.level.block.StairBlock$1
- XXX.level.block.StandingSignBlock
+ XXX.level.block.StemBlock
- XXX.level.block.StemGrownBlock
+ XXX.level.block.StoneButtonBlock
- XXX.level.block.StonecutterBlock
+ XXX.level.block.StructureBlock
- XXX.level.block.StructureBlock$1
+ XXX.level.block.StructureVoidBlock
- XXX.level.block.SugarCaneBlock
+ XXX.level.block.SweetBerryBushBlock
- XXX.level.block.TallFlowerBlock
+ XXX.level.block.TallGrassBlock
- XXX.level.block.TallSeagrass
+ XXX.level.block.TntBlock
- XXX.level.block.TorchBlock
+ XXX.level.block.TrapDoorBlock
- XXX.level.block.TrapDoorBlock$1
+ XXX.level.block.TrappedChestBlock
- XXX.level.block.TripWireBlock
+ XXX.level.block.TripWireBlock$1
- XXX.level.block.TripWireHookBlock
+ XXX.level.block.TripWireHookBlock$1
- XXX.level.block.TurtleEggBlock
+ XXX.level.block.VineBlock
- XXX.level.block.VineBlock$1
+ XXX.level.block.WallBannerBlock
- XXX.level.block.WallBlock
+ XXX.level.block.WallSignBlock
- XXX.level.block.WallSkullBlock
+ XXX.level.block.WallTorchBlock
- XXX.level.block.WaterlilyBlock
+ XXX.level.block.WebBlock
- XXX.level.block.WeightedPressurePlateBlock
+ XXX.level.block.WetSpongeBlock
- XXX.level.block.WitherRoseBlock
+ XXX.level.block.WitherSkullBlock
- XXX.level.block.WitherWallSkullBlock
+ XXX.level.block.WoodButtonBlock
- XXX.level.block.WoolCarpetBlock
- XXX.level.border.BorderChangeListener
+ XXX.level.border.BorderChangeListener$DelegateBorderChangeListener
- XXX.level.border.BorderStatus
- XXX.level.border.package-info
+ XXX.level.border.WorldBorder
- XXX.level.border.WorldBorder$1
+ XXX.level.border.WorldBorder$BorderExtent
- XXX.level.border.WorldBorder$MovingBorderExtent
+ XXX.level.border.WorldBorder$StaticBorderExtent
+ XXX.level.chunk.ChunkAccess
- XXX.level.chunk.ChunkBiomeContainer
+ XXX.level.chunk.ChunkGenerator
- XXX.level.chunk.ChunkGeneratorFactory
+ XXX.level.chunk.ChunkGeneratorType
- XXX.level.chunk.ChunkSource
+ XXX.level.chunk.ChunkStatus
- XXX.level.chunk.ChunkStatus$ChunkType
+ XXX.level.chunk.ChunkStatus$GenerationTask
- XXX.level.chunk.ChunkStatus$LoadingTask
+ XXX.level.chunk.ChunkStatus$SimpleGenerationTask
- XXX.level.chunk.DataLayer
+ XXX.level.chunk.EmptyLevelChunk
- XXX.level.chunk.FeatureAccess
+ XXX.level.chunk.GlobalPalette
- XXX.level.chunk.HashMapPalette
+ XXX.level.chunk.ImposterProtoChunk
- XXX.level.chunk.LevelChunk
+ XXX.level.chunk.LevelChunk$EntityCreationType
- XXX.level.chunk.LevelChunkSection
+ XXX.level.chunk.LightChunkGetter
- XXX.level.chunk.LinearPalette
+ XXX.level.chunk.OldDataLayer
+ XXX.level.chunk.package-info
- XXX.level.chunk.Palette
- XXX.level.chunk.PalettedContainer
+ XXX.level.chunk.PalettedContainer$CountConsumer
+ XXX.level.chunk.PaletteResize
- XXX.level.chunk.ProtoChunk
+ XXX.level.chunk.ProtoTickList
- XXX.level.chunk.UpgradeData
+ XXX.level.chunk.UpgradeData$1
- XXX.level.chunk.UpgradeData$BlockFixer
+ XXX.level.chunk.UpgradeData$BlockFixers
- XXX.level.chunk.UpgradeData$BlockFixers$1
+ XXX.level.chunk.UpgradeData$BlockFixers$2
- XXX.level.chunk.UpgradeData$BlockFixers$3
+ XXX.level.chunk.UpgradeData$BlockFixers$4
- XXX.level.chunk.UpgradeData$BlockFixers$5
+ XXX.level.dimension.Dimension
- XXX.level.dimension.DimensionType
+ XXX.level.dimension.NetherDimension
- XXX.level.dimension.NetherDimension$1
+ XXX.level.dimension.NormalDimension
+ XXX.level.dimension.package-info
- XXX.level.levelgen.ChunkGeneratorSettings
+ XXX.level.levelgen.DebugGeneratorSettings
- XXX.level.levelgen.DebugLevelSource
+ XXX.level.levelgen.FlatLevelSource
- XXX.level.levelgen.FlatLevelSource$FlatLevelBiomeWrapper
+ XXX.level.levelgen.GenerationStep
- XXX.level.levelgen.GenerationStep$Carving
+ XXX.level.levelgen.GenerationStep$Decoration
- XXX.level.levelgen.Heightmap
+ XXX.level.levelgen.Heightmap$Types
- XXX.level.levelgen.Heightmap$Usage
+ XXX.level.levelgen.NetherGeneratorSettings
- XXX.level.levelgen.NetherLevelSource
+ XXX.level.levelgen.NoiseBasedChunkGenerator
- XXX.level.levelgen.OverworldGeneratorSettings
+ XXX.level.levelgen.OverworldLevelSource
- XXX.level.levelgen.package-info
- XXX.level.levelgen.PatrolSpawner
+ XXX.level.levelgen.PhantomSpawner
- XXX.level.levelgen.TheEndGeneratorSettings
+ XXX.level.levelgen.TheEndLevelSource
- XXX.level.levelgen.WorldgenRandom
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
+ XXX.level.material.Fluids
+ XXX.level.material.FluidState
- XXX.level.material.FluidStateImpl
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
+ XXX.level.storage.LevelStorage
- XXX.level.storage.LevelStorageException
+ XXX.level.storage.LevelStorageSource
- XXX.level.storage.LevelStorageSource$1
+ XXX.level.storage.LevelSummary
- XXX.level.storage.McRegionUpgrader
+ XXX.level.storage.package-info
+ XXX.level.storage.PlayerIO
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
+ XXX.levelgen.carver.CanyonWorldCarver
- XXX.levelgen.carver.CarverConfiguration
+ XXX.levelgen.carver.CaveWorldCarver
- XXX.levelgen.carver.ConfiguredWorldCarver
+ XXX.levelgen.carver.HellCaveWorldCarver
- XXX.levelgen.carver.NoneCarverConfiguration
- XXX.levelgen.carver.package-info
+ XXX.levelgen.carver.UnderwaterCanyonWorldCarver
- XXX.levelgen.carver.UnderwaterCaveWorldCarver
+ XXX.levelgen.carver.WorldCarver
+ XXX.levelgen.feature.AbstractTreeFeature
- XXX.levelgen.feature.BambooFeature
+ XXX.levelgen.feature.BigTreeFeature
- XXX.levelgen.feature.BigTreeFeature$FoliageCoords
+ XXX.levelgen.feature.BirchFeature
- XXX.levelgen.feature.BlockBlobConfiguration
+ XXX.levelgen.feature.BlockBlobFeature
- XXX.levelgen.feature.BlockPileFeature
+ XXX.levelgen.feature.BlueIceFeature
- XXX.levelgen.feature.BonusChestFeature
+ XXX.levelgen.feature.BuriedTreasureConfiguration
- XXX.levelgen.feature.BuriedTreasureFeature
+ XXX.levelgen.feature.BuriedTreasureFeature$BuriedTreasureStart
- XXX.levelgen.feature.BushConfiguration
+ XXX.levelgen.feature.BushFeature
- XXX.levelgen.feature.CactusFeature
+ XXX.levelgen.feature.CentralSpikedFeature
- XXX.levelgen.feature.ChorusPlantFeature
+ XXX.levelgen.feature.ConfiguredFeature
- XXX.levelgen.feature.CoralClawFeature
+ XXX.levelgen.feature.CoralFeature
- XXX.levelgen.feature.CoralMushroomFeature
+ XXX.levelgen.feature.CoralTreeFeature
- XXX.levelgen.feature.CountFeatureConfiguration
+ XXX.levelgen.feature.DarkOakFeature
- XXX.levelgen.feature.DeadBushFeature
+ XXX.levelgen.feature.DecoratedFeature
- XXX.levelgen.feature.DecoratedFeatureConfiguration
+ XXX.levelgen.feature.DecoratedFlowerFeature
- XXX.levelgen.feature.DecoratorChanceRange
+ XXX.levelgen.feature.DecoratorConfiguration
- XXX.levelgen.feature.DecoratorCountRange
+ XXX.levelgen.feature.DecoratorNoiseDependant
- XXX.levelgen.feature.DefaultFlowerFeature
+ XXX.levelgen.feature.DesertPyramidFeature
- XXX.levelgen.feature.DesertPyramidFeature$FeatureStart
+ XXX.levelgen.feature.DesertVillagePools
- XXX.levelgen.feature.DesertWellFeature
+ XXX.levelgen.feature.DiskConfiguration
- XXX.levelgen.feature.DiskReplaceFeature
+ XXX.levelgen.feature.DoublePlantConfiguration
- XXX.levelgen.feature.DoublePlantFeature
+ XXX.levelgen.feature.EndCityFeature
- XXX.levelgen.feature.EndCityFeature$EndCityStart
+ XXX.levelgen.feature.EndGatewayConfiguration
- XXX.levelgen.feature.EndGatewayFeature
+ XXX.levelgen.feature.EndIslandFeature
- XXX.levelgen.feature.EndPodiumFeature
+ XXX.levelgen.feature.Feature
- XXX.levelgen.feature.FeatureConfiguration
+ XXX.levelgen.feature.FeatureRadius
- XXX.levelgen.feature.FillLayerFeature
+ XXX.levelgen.feature.FlowerFeature
- XXX.levelgen.feature.ForestFlowerFeature
+ XXX.levelgen.feature.FossilFeature
- XXX.levelgen.feature.GeneralForestFlowerFeature
+ XXX.levelgen.feature.GlowstoneFeature
- XXX.levelgen.feature.GrassConfiguration
+ XXX.levelgen.feature.GrassFeature
- XXX.levelgen.feature.GroundBushFeature
+ XXX.levelgen.feature.HayBlockPileFeature
- XXX.levelgen.feature.HellFireFeature
+ XXX.levelgen.feature.HellSpringConfiguration
- XXX.levelgen.feature.HugeBrownMushroomFeature
+ XXX.levelgen.feature.HugeMushroomFeatureConfig
- XXX.levelgen.feature.HugeRedMushroomFeature
- XXX.levelgen.feature.IcebergConfiguration
+ XXX.levelgen.feature.IcebergFeature
+ XXX.levelgen.feature.IceBlockPileFeature
- XXX.levelgen.feature.IcePatchFeature
+ XXX.levelgen.feature.IceSpikeFeature
- XXX.levelgen.feature.IglooFeature
+ XXX.levelgen.feature.IglooFeature$FeatureStart
- XXX.levelgen.feature.JungleGrassFeature
+ XXX.levelgen.feature.JunglePyramidFeature
- XXX.levelgen.feature.JunglePyramidFeature$FeatureStart
+ XXX.levelgen.feature.JungleTreeFeature
- XXX.levelgen.feature.KelpFeature
+ XXX.levelgen.feature.LakeConfiguration
- XXX.levelgen.feature.LakeFeature
+ XXX.levelgen.feature.LayerConfiguration
- XXX.levelgen.feature.MegaJungleTreeFeature
+ XXX.levelgen.feature.MegaPineTreeFeature
- XXX.levelgen.feature.MegaTreeFeature
+ XXX.levelgen.feature.MelonBlockPileFeature
- XXX.levelgen.feature.MelonFeature
+ XXX.levelgen.feature.MineshaftConfiguration
- XXX.levelgen.feature.MineshaftFeature
+ XXX.levelgen.feature.MineshaftFeature$MineShaftStart
- XXX.levelgen.feature.MineshaftFeature$Type
+ XXX.levelgen.feature.MonsterRoomFeature
- XXX.levelgen.feature.NetherFortressFeature
+ XXX.levelgen.feature.NetherFortressFeature$NetherBridgeStart
- XXX.levelgen.feature.NetherSpringFeature
+ XXX.levelgen.feature.NoneDecoratorConfiguration
- XXX.levelgen.feature.NoneFeatureConfiguration
+ XXX.levelgen.feature.OceanMonumentFeature
- XXX.levelgen.feature.OceanMonumentFeature$OceanMonumentStart
+ XXX.levelgen.feature.OceanRuinConfiguration
- XXX.levelgen.feature.OreConfiguration
+ XXX.levelgen.feature.OreConfiguration$Predicates
- XXX.levelgen.feature.OreFeature
- XXX.levelgen.feature.package-info
+ XXX.levelgen.feature.PillagerOutpostConfiguration
- XXX.levelgen.feature.PillagerOutpostFeature
+ XXX.levelgen.feature.PillagerOutpostFeature$FeatureStart
- XXX.levelgen.feature.PineFeature
+ XXX.levelgen.feature.PlainFlowerFeature
- XXX.levelgen.feature.PlainVillagePools
+ XXX.levelgen.feature.ProbabilityFeatureConfiguration
- XXX.levelgen.feature.PumpkinBlockPileFeature
+ XXX.levelgen.feature.RandomBooleanFeatureConfig
- XXX.levelgen.feature.RandomBooleanSelectorFeature
+ XXX.levelgen.feature.RandomFeatureConfig
- XXX.levelgen.feature.RandomRandomFeature
+ XXX.levelgen.feature.RandomRandomFeatureConfig
- XXX.levelgen.feature.RandomScatteredFeature
+ XXX.levelgen.feature.RandomSelectorFeature
- XXX.levelgen.feature.ReedsFeature
+ XXX.levelgen.feature.ReplaceBlockConfiguration
- XXX.levelgen.feature.ReplaceBlockFeature
+ XXX.levelgen.feature.SavannaTreeFeature
- XXX.levelgen.feature.SavannaVillagePools
- XXX.levelgen.feature.SeagrassFeature
+ XXX.levelgen.feature.SeagrassFeatureConfiguration
+ XXX.levelgen.feature.SeaPickleFeature
- XXX.levelgen.feature.ShipwreckConfiguration
+ XXX.levelgen.feature.ShipwreckFeature
- XXX.levelgen.feature.ShipwreckFeature$FeatureStart
+ XXX.levelgen.feature.SimpleBlockConfiguration
- XXX.levelgen.feature.SimpleBlockFeature
+ XXX.levelgen.feature.SimpleRandomFeatureConfig
- XXX.levelgen.feature.SimpleRandomSelectorFeature
+ XXX.levelgen.feature.SimulatedFeature
- XXX.levelgen.feature.SnowAndFreezeFeature
+ XXX.levelgen.feature.SnowBlockPileFeature
- XXX.levelgen.feature.SnowyVillagePools
+ XXX.levelgen.feature.SpikeConfiguration
- XXX.levelgen.feature.SpikeFeature
+ XXX.levelgen.feature.SpikeFeature$1
- XXX.levelgen.feature.SpikeFeature$EndSpike
+ XXX.levelgen.feature.SpikeFeature$SpikeCacheLoader
- XXX.levelgen.feature.SpringConfiguration
+ XXX.levelgen.feature.SpringFeature
- XXX.levelgen.feature.SpruceFeature
+ XXX.levelgen.feature.StrongholdFeature
- XXX.levelgen.feature.StrongholdFeature$StrongholdStart
+ XXX.levelgen.feature.StructureFeature
- XXX.levelgen.feature.StructureFeature$StructureStartFactory
+ XXX.levelgen.feature.StructurePieceType
- XXX.levelgen.feature.SwampFlowerFeature
- XXX.levelgen.feature.SwamplandHutFeature
+ XXX.levelgen.feature.SwamplandHutFeature$FeatureStart
+ XXX.levelgen.feature.SwampTreeFeature
- XXX.levelgen.feature.TaigaGrassFeature
+ XXX.levelgen.feature.TaigaVillagePools
- XXX.levelgen.feature.TreeFeature
+ XXX.levelgen.feature.VillageConfiguration
- XXX.levelgen.feature.VillageFeature
+ XXX.levelgen.feature.VillageFeature$FeatureStart
- XXX.levelgen.feature.VillagePieces
+ XXX.levelgen.feature.VillagePieces$VillagePiece
- XXX.levelgen.feature.VinesFeature
+ XXX.levelgen.feature.VoidStartPlatformFeature
- XXX.levelgen.feature.WaterlilyFeature
+ XXX.levelgen.feature.WeightedConfiguredFeature
- XXX.levelgen.feature.WoodlandMansionFeature
+ XXX.levelgen.feature.WoodlandMansionFeature$WoodlandMansionStart
+ XXX.levelgen.flat.FlatLayerInfo
- XXX.levelgen.flat.FlatLevelGeneratorSettings
+ XXX.levelgen.flat.package-info
+ XXX.levelgen.placement.CarvingMaskDecorator
- XXX.levelgen.placement.ChanceHeightmapDecorator
+ XXX.levelgen.placement.ChanceHeightmapDoubleDecorator
- XXX.levelgen.placement.ChancePassthroughDecorator
+ XXX.levelgen.placement.ChanceTopSolidHeightmapDecorator
- XXX.levelgen.placement.ChorusPlantPlacementDecorator
+ XXX.levelgen.placement.ConfiguredDecorator
- XXX.levelgen.placement.CountBiasedRangeDecorator
+ XXX.levelgen.placement.CountChanceHeightmapDecorator
- XXX.levelgen.placement.CountChanceHeightmapDoubleDecorator
+ XXX.levelgen.placement.CountDepthAverageDecorator
- XXX.levelgen.placement.CountHeighmapDoubleDecorator
+ XXX.levelgen.placement.CountHeight64Decorator
- XXX.levelgen.placement.CountHeightmap32Decorator
+ XXX.levelgen.placement.CountHeightmapDecorator
- XXX.levelgen.placement.CountTopSolidDecorator
+ XXX.levelgen.placement.CountVeryBiasedRangeDecorator
- XXX.levelgen.placement.CountWithExtraChanceHeightmapDecorator
+ XXX.levelgen.placement.DarkOakTreePlacementDecorator
- XXX.levelgen.placement.DecoratorCarvingMaskConfig
+ XXX.levelgen.placement.DecoratorChance
- XXX.levelgen.placement.DecoratorFrequency
+ XXX.levelgen.placement.DecoratorFrequencyChance
- XXX.levelgen.placement.DecoratorFrequencyWithExtraChance
+ XXX.levelgen.placement.DecoratorNoiseCountFactor
- XXX.levelgen.placement.DecoratorRange
+ XXX.levelgen.placement.DepthAverageConfigation
- XXX.levelgen.placement.EmeraldPlacementDecorator
+ XXX.levelgen.placement.EndGatewayPlacementDecorator
- XXX.levelgen.placement.EndIslandPlacementDecorator
+ XXX.levelgen.placement.FeatureDecorator
- XXX.levelgen.placement.ForestRockPlacementDecorator
+ XXX.levelgen.placement.IcebergPlacementDecorator
- XXX.levelgen.placement.LakeChanceDecoratorConfig
+ XXX.levelgen.placement.LakeLavaPlacementDecorator
- XXX.levelgen.placement.LakeWaterPlacementDecorator
+ XXX.levelgen.placement.MonsterRoomPlacementConfiguration
- XXX.levelgen.placement.MonsterRoomPlacementDecorator
+ XXX.levelgen.placement.NoiseHeightmap32Decorator
- XXX.levelgen.placement.NoiseHeightmapDoubleDecorator
+ XXX.levelgen.placement.NopePlacementDecorator
+ XXX.levelgen.placement.package-info
- XXX.levelgen.placement.SimpleFeatureDecorator
+ XXX.levelgen.placement.TopSolidHeightMapDecorator
- XXX.levelgen.placement.TopSolidHeightMapNoiseBasedDecorator
+ XXX.levelgen.placement.TopSolidHeightMapRangeDecorator
- XXX.levelgen.structure.BeardedStructureStart
+ XXX.levelgen.structure.BoundingBox
- XXX.levelgen.structure.BoundingBox$1
+ XXX.levelgen.structure.BuriedTreasurePieces
- XXX.levelgen.structure.BuriedTreasurePieces$BuriedTreasurePiece
+ XXX.levelgen.structure.DesertPyramidPiece
- XXX.levelgen.structure.EndCityPieces
+ XXX.levelgen.structure.EndCityPieces$1
- XXX.levelgen.structure.EndCityPieces$2
+ XXX.levelgen.structure.EndCityPieces$3
- XXX.levelgen.structure.EndCityPieces$4
+ XXX.levelgen.structure.EndCityPieces$EndCityPiece
- XXX.levelgen.structure.EndCityPieces$SectionGenerator
+ XXX.levelgen.structure.IglooPieces
- XXX.levelgen.structure.IglooPieces$IglooPiece
+ XXX.levelgen.structure.JunglePyramidPiece
- XXX.levelgen.structure.JunglePyramidPiece$1
+ XXX.levelgen.structure.JunglePyramidPiece$MossStoneSelector
- XXX.levelgen.structure.LegacyStructureDataHandler
+ XXX.levelgen.structure.MineShaftPieces
- XXX.levelgen.structure.MineShaftPieces$1
+ XXX.levelgen.structure.MineShaftPieces$MineShaftCorridor
- XXX.levelgen.structure.MineShaftPieces$MineShaftCrossing
+ XXX.levelgen.structure.MineShaftPieces$MineShaftPiece
- XXX.levelgen.structure.MineShaftPieces$MineShaftRoom
+ XXX.levelgen.structure.MineShaftPieces$MineShaftStairs
- XXX.levelgen.structure.NetherBridgePieces
+ XXX.levelgen.structure.NetherBridgePieces$1
- XXX.levelgen.structure.NetherBridgePieces$BridgeCrossing
+ XXX.levelgen.structure.NetherBridgePieces$BridgeEndFiller
- XXX.levelgen.structure.NetherBridgePieces$BridgeStraight
+ XXX.levelgen.structure.NetherBridgePieces$CastleCorridorStairsPiece
- XXX.levelgen.structure.NetherBridgePieces$CastleCorridorTBalconyPiece
+ XXX.levelgen.structure.NetherBridgePieces$CastleEntrance
- XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorCrossingPiece
+ XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorLeftTurnPiece
- XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorPiece
+ XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorRightTurnPiece
- XXX.levelgen.structure.NetherBridgePieces$CastleStalkRoom
+ XXX.levelgen.structure.NetherBridgePieces$MonsterThrone
- XXX.levelgen.structure.NetherBridgePieces$NetherBridgePiece
+ XXX.levelgen.structure.NetherBridgePieces$PieceWeight
- XXX.levelgen.structure.NetherBridgePieces$RoomCrossing
+ XXX.levelgen.structure.NetherBridgePieces$StairsRoom
- XXX.levelgen.structure.NetherBridgePieces$StartPiece
+ XXX.levelgen.structure.OceanMonumentPieces
- XXX.levelgen.structure.OceanMonumentPieces$1
+ XXX.levelgen.structure.OceanMonumentPieces$FitDoubleXRoom
- XXX.levelgen.structure.OceanMonumentPieces$FitDoubleXYRoom
+ XXX.levelgen.structure.OceanMonumentPieces$FitDoubleYRoom
- XXX.levelgen.structure.OceanMonumentPieces$FitDoubleYZRoom
+ XXX.levelgen.structure.OceanMonumentPieces$FitDoubleZRoom
- XXX.levelgen.structure.OceanMonumentPieces$FitSimpleRoom
+ XXX.levelgen.structure.OceanMonumentPieces$FitSimpleTopRoom
- XXX.levelgen.structure.OceanMonumentPieces$MonumentBuilding
+ XXX.levelgen.structure.OceanMonumentPieces$MonumentRoomFitter
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentCoreRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXYRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYZRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleZRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentEntryRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentPenthouse
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentPiece
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleTopRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentWingRoom
- XXX.levelgen.structure.OceanMonumentPieces$RoomDefinition
+ XXX.levelgen.structure.OceanRuinFeature
- XXX.levelgen.structure.OceanRuinFeature$OceanRuinStart
+ XXX.levelgen.structure.OceanRuinFeature$Type
- XXX.levelgen.structure.OceanRuinPieces
+ XXX.levelgen.structure.OceanRuinPieces$OceanRuinPiece
- XXX.levelgen.structure.package-info
- XXX.levelgen.structure.PillagerOutpostPieces
+ XXX.levelgen.structure.PillagerOutpostPieces$PillagerOutpostPiece
- XXX.levelgen.structure.PoolElementStructurePiece
+ XXX.levelgen.structure.ScatteredFeaturePiece
- XXX.levelgen.structure.ShipwreckPieces
+ XXX.levelgen.structure.ShipwreckPieces$ShipwreckPiece
- XXX.levelgen.structure.StrongholdPieces
+ XXX.levelgen.structure.StrongholdPieces$1
- XXX.levelgen.structure.StrongholdPieces$2
+ XXX.levelgen.structure.StrongholdPieces$3
- XXX.levelgen.structure.StrongholdPieces$ChestCorridor
+ XXX.levelgen.structure.StrongholdPieces$FillerCorridor
- XXX.levelgen.structure.StrongholdPieces$FiveCrossing
+ XXX.levelgen.structure.StrongholdPieces$LeftTurn
- XXX.levelgen.structure.StrongholdPieces$Library
+ XXX.levelgen.structure.StrongholdPieces$PieceWeight
- XXX.levelgen.structure.StrongholdPieces$PortalRoom
+ XXX.levelgen.structure.StrongholdPieces$PrisonHall
- XXX.levelgen.structure.StrongholdPieces$RightTurn
+ XXX.levelgen.structure.StrongholdPieces$RoomCrossing
- XXX.levelgen.structure.StrongholdPieces$SmoothStoneSelector
+ XXX.levelgen.structure.StrongholdPieces$StairsDown
- XXX.levelgen.structure.StrongholdPieces$StartPiece
+ XXX.levelgen.structure.StrongholdPieces$Straight
- XXX.levelgen.structure.StrongholdPieces$StraightStairsDown
+ XXX.levelgen.structure.StrongholdPieces$StrongholdPiece
- XXX.levelgen.structure.StrongholdPieces$StrongholdPiece$SmallDoorType
+ XXX.levelgen.structure.StrongholdPieces$Turn
+ XXX.levelgen.structure.StructureFeatureIndexSavedData
- XXX.levelgen.structure.StructureFeatureIO
- XXX.levelgen.structure.StructurePiece
+ XXX.levelgen.structure.StructurePiece$1
- XXX.levelgen.structure.StructurePiece$BlockSelector
+ XXX.levelgen.structure.StructureStart
- XXX.levelgen.structure.StructureStart$1
+ XXX.levelgen.structure.SwamplandHutPiece
- XXX.levelgen.structure.TemplateStructurePiece
+ XXX.levelgen.structure.WoodlandMansionPieces
- XXX.levelgen.structure.WoodlandMansionPieces$1
+ XXX.levelgen.structure.WoodlandMansionPieces$FirstFloorRoomCollection
- XXX.levelgen.structure.WoodlandMansionPieces$FloorRoomCollection
+ XXX.levelgen.structure.WoodlandMansionPieces$MansionGrid
- XXX.levelgen.structure.WoodlandMansionPieces$MansionPiecePlacer
+ XXX.levelgen.structure.WoodlandMansionPieces$PlacementData
- XXX.levelgen.structure.WoodlandMansionPieces$SecondFloorRoomCollection
+ XXX.levelgen.structure.WoodlandMansionPieces$SimpleGrid
- XXX.levelgen.structure.WoodlandMansionPieces$ThirdFloorRoomCollection
+ XXX.levelgen.structure.WoodlandMansionPieces$WoodlandMansionPiece
- XXX.levelgen.surfacebuilders.BadlandsSurfaceBuilder
+ XXX.levelgen.surfacebuilders.ConfiguredSurfaceBuilder
- XXX.levelgen.surfacebuilders.DefaultSurfaceBuilder
+ XXX.levelgen.surfacebuilders.ErodedBadlandsSurfaceBuilder
- XXX.levelgen.surfacebuilders.FrozenOceanSurfaceBuilder
+ XXX.levelgen.surfacebuilders.GiantTreeTaigaSurfaceBuilder
- XXX.levelgen.surfacebuilders.GravellyMountainSurfaceBuilder
+ XXX.levelgen.surfacebuilders.MountainSurfaceBuilder
- XXX.levelgen.surfacebuilders.NetherSurfaceBuilder
+ XXX.levelgen.surfacebuilders.NopeSurfaceBuilder
- XXX.levelgen.surfacebuilders.package-info
- XXX.levelgen.surfacebuilders.ShatteredSavanaSurfaceBuilder
+ XXX.levelgen.surfacebuilders.SurfaceBuilder
- XXX.levelgen.surfacebuilders.SurfaceBuilderBaseConfiguration
+ XXX.levelgen.surfacebuilders.SurfaceBuilderConfiguration
- XXX.levelgen.surfacebuilders.SwampSurfaceBuilder
+ XXX.levelgen.surfacebuilders.WoodedBadlandsSurfaceBuilder
+ XXX.levelgen.synth.ImprovedNoise
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
- XXX.loot.entries.CompositeEntryBase$Serializer
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
+ XXX.loot.entries.LootPoolEntries$Serializer
- XXX.loot.entries.LootPoolEntry
+ XXX.loot.entries.LootPoolEntryContainer
- XXX.loot.entries.LootPoolEntryContainer$Builder
+ XXX.loot.entries.LootPoolEntryContainer$Serializer
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
- XXX.loot.functions.LootingEnchantFunction
+ XXX.loot.functions.LootingEnchantFunction$1
- XXX.loot.functions.LootingEnchantFunction$Builder
+ XXX.loot.functions.LootingEnchantFunction$Serializer
+ XXX.loot.functions.LootItemConditionalFunction
- XXX.loot.functions.LootItemConditionalFunction$Builder
+ XXX.loot.functions.LootItemConditionalFunction$DummyBuilder
- XXX.loot.functions.LootItemConditionalFunction$Serializer
+ XXX.loot.functions.LootItemFunction
- XXX.loot.functions.LootItemFunction$Builder
+ XXX.loot.functions.LootItemFunction$Serializer
- XXX.loot.functions.LootItemFunctions
+ XXX.loot.functions.LootItemFunctions$Serializer
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
+ XXX.loot.predicates.LocationCheck$Serializer
- XXX.loot.predicates.LootItemBlockStatePropertyCondition
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition$1
- XXX.loot.predicates.LootItemBlockStatePropertyCondition$Builder
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition$Serializer
- XXX.loot.predicates.LootItemCondition
+ XXX.loot.predicates.LootItemCondition$Builder
- XXX.loot.predicates.LootItemCondition$Serializer
+ XXX.loot.predicates.LootItemConditions
- XXX.loot.predicates.LootItemConditions$Serializer
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
- XXX.minecraft.core.BlockPos
+ XXX.minecraft.core.BlockPos$1
- XXX.minecraft.core.BlockPos$2
+ XXX.minecraft.core.BlockPos$3
- XXX.minecraft.core.BlockPos$MutableBlockPos
+ XXX.minecraft.core.BlockPos$PooledMutableBlockPos
- XXX.minecraft.core.BlockSource
+ XXX.minecraft.core.BlockSourceImpl
- XXX.minecraft.core.Cursor3D
+ XXX.minecraft.core.DefaultedRegistry
- XXX.minecraft.core.Direction
+ XXX.minecraft.core.Direction$1
- XXX.minecraft.core.Direction$Axis
+ XXX.minecraft.core.Direction$Axis$1
- XXX.minecraft.core.Direction$Axis$2
+ XXX.minecraft.core.Direction$Axis$3
- XXX.minecraft.core.Direction$AxisDirection
+ XXX.minecraft.core.Direction$Plane
- XXX.minecraft.core.Direction8
+ XXX.minecraft.core.GlobalPos
- XXX.minecraft.core.IdMap
+ XXX.minecraft.core.IdMapper
- XXX.minecraft.core.LocatableSource
+ XXX.minecraft.core.Location
- XXX.minecraft.core.MapFiller
+ XXX.minecraft.core.MappedRegistry
- XXX.minecraft.core.NonNullList
- XXX.minecraft.core.package-info
+ XXX.minecraft.core.Position
- XXX.minecraft.core.PositionImpl
+ XXX.minecraft.core.Registry
- XXX.minecraft.core.Rotations
+ XXX.minecraft.core.SectionPos
- XXX.minecraft.core.SectionPos$1
+ XXX.minecraft.core.SerializableLong
- XXX.minecraft.core.Source
+ XXX.minecraft.core.Vec3i
- XXX.minecraft.core.Vec3i$1
+ XXX.minecraft.core.WritableRegistry
- XXX.minecraft.data.DataGenerator
+ XXX.minecraft.data.DataProvider
- XXX.minecraft.data.HashCache
+ XXX.minecraft.data.Main
- XXX.minecraft.data.package-info
+ XXX.minecraft.locale.Language
- XXX.minecraft.locale.package-info
+ XXX.minecraft.nbt.ByteArrayTag
- XXX.minecraft.nbt.ByteArrayTag$1
- XXX.minecraft.nbt.ByteTag$1
- XXX.minecraft.nbt.CompoundTag$1
+ XXX.minecraft.nbt.DoubleTag
- XXX.minecraft.nbt.DoubleTag$1
- XXX.minecraft.nbt.EndTag$1
+ XXX.minecraft.nbt.FloatTag
- XXX.minecraft.nbt.FloatTag$1
- XXX.minecraft.nbt.IntArrayTag$1
+ XXX.minecraft.nbt.IntTag
- XXX.minecraft.nbt.IntTag$1
- XXX.minecraft.nbt.ListTag
- XXX.minecraft.nbt.LongTag
- XXX.minecraft.nbt.LongTag$Cache
+ XXX.minecraft.nbt.NbtAccounter
- XXX.minecraft.nbt.NbtAccounter$1
+ XXX.minecraft.nbt.NbtIo
- XXX.minecraft.nbt.NbtOps
+ XXX.minecraft.nbt.NbtUtils
- XXX.minecraft.nbt.NumericTag
+ XXX.minecraft.nbt.package-info
+ XXX.minecraft.nbt.ShortTag
- XXX.minecraft.nbt.ShortTag$1
- XXX.minecraft.nbt.StringTag
- XXX.minecraft.nbt.TagType
- XXX.minecraft.nbt.TagTypes
- XXX.minecraft.network.CipherBase
+ XXX.minecraft.network.CipherDecoder
- XXX.minecraft.network.CipherEncoder
+ XXX.minecraft.network.CompressionDecoder
- XXX.minecraft.network.CompressionEncoder
+ XXX.minecraft.network.Connection
- XXX.minecraft.network.Connection$1
+ XXX.minecraft.network.Connection$2
- XXX.minecraft.network.Connection$PacketHolder
+ XXX.minecraft.network.ConnectionProtocol
- XXX.minecraft.network.ConnectionProtocol$1
+ XXX.minecraft.network.ConnectionProtocol$PacketSet
- XXX.minecraft.network.ConnectionProtocol$ProtocolBuilder
+ XXX.minecraft.network.FriendlyByteBuf
- XXX.minecraft.network.PacketDecoder
+ XXX.minecraft.network.PacketEncoder
- XXX.minecraft.network.PacketListener
+ XXX.minecraft.network.SkipPacketException
- XXX.minecraft.network.Varint21FrameDecoder
+ XXX.minecraft.network.Varint21LengthFieldPrepender
- XXX.minecraft.world.package-info
- XXX.mojang.math.Matrix3f
- XXX.mojang.math.Vector3f
- XXX.network.chat.BaseComponent
+ XXX.network.chat.ChatType
- XXX.network.chat.ClickEvent
+ XXX.network.chat.ClickEvent$Action
- XXX.network.chat.Component
+ XXX.network.chat.Component$1
- XXX.network.chat.Component$Serializer
+ XXX.network.chat.ComponentUtils
- XXX.network.chat.ContextAwareComponent
+ XXX.network.chat.HoverEvent
- XXX.network.chat.HoverEvent$Action
+ XXX.network.chat.KeybindComponent
- XXX.network.chat.NbtComponent
+ XXX.network.chat.NbtComponent$BlockNbtComponent
- XXX.network.chat.NbtComponent$EntityNbtComponent
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
- XXX.placement.nether.ChanceRangeDecorator
+ XXX.placement.nether.CountRangeDecorator
- XXX.placement.nether.HellFireDecorator
+ XXX.placement.nether.LightGemChanceDecorator
- XXX.placement.nether.MagmaDecorator
- XXX.placement.nether.package-info
+ XXX.placement.nether.RandomCountRangeDecorator
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
- XXX.state.pattern.BlockInWorld
+ XXX.state.pattern.BlockPattern
- XXX.state.pattern.BlockPattern$BlockCacheLoader
+ XXX.state.pattern.BlockPattern$BlockPatternMatch
- XXX.state.pattern.BlockPattern$PortalInfo
+ XXX.state.pattern.BlockPatternBuilder
- XXX.state.pattern.package-info
+ XXX.state.predicate.BlockMaterialPredicate
- XXX.state.predicate.BlockMaterialPredicate$1
+ XXX.state.predicate.BlockPredicate
- XXX.state.predicate.BlockStatePredicate
+ XXX.state.predicate.package-info
- XXX.state.properties.AbstractProperty
+ XXX.state.properties.AttachFace
- XXX.state.properties.BambooLeaves
+ XXX.state.properties.BedPart
- XXX.state.properties.BellAttachType
+ XXX.state.properties.BlockStateProperties
- XXX.state.properties.BooleanProperty
+ XXX.state.properties.ChestType
- XXX.state.properties.ComparatorMode
+ XXX.state.properties.DirectionProperty
- XXX.state.properties.DoorHingeSide
+ XXX.state.properties.DoubleBlockHalf
- XXX.state.properties.EnumProperty
+ XXX.state.properties.Half
- XXX.state.properties.IntegerProperty
+ XXX.state.properties.NoteBlockInstrument
+ XXX.state.properties.package-info
- XXX.state.properties.PistonType
+ XXX.state.properties.Property
- XXX.state.properties.RailShape
+ XXX.state.properties.RedstoneSide
- XXX.state.properties.SlabType
+ XXX.state.properties.StairsShape
- XXX.state.properties.StructureMode
- XXX.storage.loot.BinomialDistributionGenerator
+ XXX.storage.loot.BinomialDistributionGenerator$Serializer
- XXX.storage.loot.BuiltInLootTables
+ XXX.storage.loot.ConstantIntValue
- XXX.storage.loot.ConstantIntValue$Serializer
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
+ XXX.storage.loot.RandomIntGenerator
- XXX.storage.loot.RandomIntGenerators
+ XXX.storage.loot.RandomValueBounds
- XXX.storage.loot.RandomValueBounds$Serializer
+ XXX.storage.loot.ValidationContext
- XXX.storage.threaded.package-info
+ XXX.structure.templatesystem.AlwaysTrueTest
- XXX.structure.templatesystem.BlockIgnoreProcessor
+ XXX.structure.templatesystem.BlockMatchTest
- XXX.structure.templatesystem.BlockRotProcessor
+ XXX.structure.templatesystem.BlockStateMatchTest
- XXX.structure.templatesystem.GravityProcessor
+ XXX.structure.templatesystem.JigsawReplacementProcessor
- XXX.structure.templatesystem.NopProcessor
+ XXX.structure.templatesystem.package-info
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
+ XXX.structure.templatesystem.StructureTemplate$SimplePalette
- XXX.structure.templatesystem.StructureTemplate$StructureBlockInfo
+ XXX.structure.templatesystem.StructureTemplate$StructureEntityInfo
- XXX.structure.templatesystem.TagMatchTest
+ XXX.village.poi.package-info
+ XXX.village.poi.PoiManager
- XXX.village.poi.PoiManager$DistanceTracker
+ XXX.village.poi.PoiManager$Occupancy
- XXX.village.poi.PoiRecord
+ XXX.village.poi.PoiSection
- XXX.village.poi.PoiType
+ XXX.world.entity.package-info
- XXX.world.entity.ReputationEventHandler
+ XXX.world.entity.SpawnGroupData
- XXX.world.entity.SpawnPlacements
+ XXX.world.entity.SpawnPlacements$Data
- XXX.world.entity.SpawnPlacements$SpawnPredicate
+ XXX.world.entity.SpawnPlacements$Type
- XXX.world.entity.TamableAnimal
+ XXX.world.food.FoodConstants
- XXX.world.food.FoodData
+ XXX.world.food.FoodProperties
- XXX.world.food.FoodProperties$1
+ XXX.world.food.FoodProperties$Builder
- XXX.world.food.Foods
+ XXX.world.food.package-info
- XXX.world.inventory.AbstractContainerMenu
+ XXX.world.inventory.AbstractFurnaceMenu
- XXX.world.inventory.AnvilMenu
+ XXX.world.inventory.AnvilMenu$1
- XXX.world.inventory.AnvilMenu$2
+ XXX.world.inventory.AnvilMenu$3
- XXX.world.inventory.BeaconMenu
+ XXX.world.inventory.BeaconMenu$1
- XXX.world.inventory.BeaconMenu$PaymentSlot
+ XXX.world.inventory.BlastFurnaceMenu
- XXX.world.inventory.BrewingStandMenu
+ XXX.world.inventory.BrewingStandMenu$FuelSlot
- XXX.world.inventory.BrewingStandMenu$IngredientsSlot
+ XXX.world.inventory.BrewingStandMenu$PotionSlot
- XXX.world.inventory.CartographyTableMenu
+ XXX.world.inventory.CartographyTableMenu$1
- XXX.world.inventory.CartographyTableMenu$2
+ XXX.world.inventory.CartographyTableMenu$3
- XXX.world.inventory.CartographyTableMenu$4
+ XXX.world.inventory.CartographyTableMenu$5
- XXX.world.inventory.ChestMenu
+ XXX.world.inventory.ClickType
- XXX.world.inventory.ContainerData
+ XXX.world.inventory.ContainerLevelAccess
- XXX.world.inventory.ContainerLevelAccess$1
+ XXX.world.inventory.ContainerLevelAccess$2
- XXX.world.inventory.ContainerListener
+ XXX.world.inventory.CraftingContainer
- XXX.world.inventory.CraftingMenu
+ XXX.world.inventory.DataSlot
- XXX.world.inventory.DataSlot$1
+ XXX.world.inventory.DataSlot$2
- XXX.world.inventory.DataSlot$3
+ XXX.world.inventory.DispenserMenu
- XXX.world.inventory.EnchantmentMenu
+ XXX.world.inventory.EnchantmentMenu$1
- XXX.world.inventory.EnchantmentMenu$2
+ XXX.world.inventory.EnchantmentMenu$3
- XXX.world.inventory.FurnaceFuelSlot
+ XXX.world.inventory.FurnaceMenu
- XXX.world.inventory.FurnaceResultSlot
+ XXX.world.inventory.GrindstoneMenu
- XXX.world.inventory.GrindstoneMenu$1
+ XXX.world.inventory.GrindstoneMenu$2
- XXX.world.inventory.GrindstoneMenu$3
+ XXX.world.inventory.GrindstoneMenu$4
- XXX.world.inventory.HopperMenu
+ XXX.world.inventory.HorseInventoryMenu
- XXX.world.inventory.HorseInventoryMenu$1
+ XXX.world.inventory.HorseInventoryMenu$2
- XXX.world.inventory.InventoryMenu
+ XXX.world.inventory.InventoryMenu$1
- XXX.world.inventory.InventoryMenu$2
+ XXX.world.inventory.LecternMenu
- XXX.world.inventory.LecternMenu$1
+ XXX.world.inventory.LoomMenu
- XXX.world.inventory.LoomMenu$1
+ XXX.world.inventory.LoomMenu$2
- XXX.world.inventory.LoomMenu$3
+ XXX.world.inventory.LoomMenu$4
- XXX.world.inventory.LoomMenu$5
+ XXX.world.inventory.LoomMenu$6
- XXX.world.inventory.MenuConstructor
+ XXX.world.inventory.MenuType
- XXX.world.inventory.MenuType$MenuSupplier
+ XXX.world.inventory.MerchantContainer
- XXX.world.inventory.MerchantMenu
+ XXX.world.inventory.MerchantResultSlot
- XXX.world.inventory.package-info
- XXX.world.inventory.PlayerEnderChestContainer
+ XXX.world.inventory.RecipeBookMenu
- XXX.world.inventory.RecipeHolder
+ XXX.world.inventory.ResultContainer
- XXX.world.inventory.ResultSlot
+ XXX.world.inventory.ShulkerBoxMenu
- XXX.world.inventory.ShulkerBoxSlot
+ XXX.world.inventory.SimpleContainerData
- XXX.world.inventory.Slot
+ XXX.world.inventory.SmokerMenu
- XXX.world.inventory.StackedContentsCompatible
+ XXX.world.inventory.StonecutterMenu
- XXX.world.inventory.StonecutterMenu$1
+ XXX.world.inventory.StonecutterMenu$2
+ XXX.world.item.AirItem
- XXX.world.item.ArmorItem
+ XXX.world.item.ArmorItem$1
- XXX.world.item.ArmorMaterial
+ XXX.world.item.ArmorMaterials
- XXX.world.item.ArmorStandItem
+ XXX.world.item.ArrowItem
- XXX.world.item.AxeItem
+ XXX.world.item.BannerItem
- XXX.world.item.BannerPatternItem
+ XXX.world.item.BedItem
- XXX.world.item.BlockItem
+ XXX.world.item.BlockPlaceContext
- XXX.world.item.BoatItem
+ XXX.world.item.BoneMealItem
- XXX.world.item.BookItem
+ XXX.world.item.BottleItem
- XXX.world.item.BowItem
+ XXX.world.item.BowlFoodItem
- XXX.world.item.BucketItem
+ XXX.world.item.CarrotOnAStickItem
- XXX.world.item.ChorusFruitItem
+ XXX.world.item.ClockItem
- XXX.world.item.ClockItem$1
+ XXX.world.item.CompassItem
- XXX.world.item.CompassItem$1
+ XXX.world.item.ComplexItem
- XXX.world.item.CreativeModeTab
+ XXX.world.item.CreativeModeTab$1
- XXX.world.item.CreativeModeTab$10
+ XXX.world.item.CreativeModeTab$11
- XXX.world.item.CreativeModeTab$12
+ XXX.world.item.CreativeModeTab$2
- XXX.world.item.CreativeModeTab$3
+ XXX.world.item.CreativeModeTab$4
- XXX.world.item.CreativeModeTab$5
+ XXX.world.item.CreativeModeTab$6
- XXX.world.item.CreativeModeTab$7
+ XXX.world.item.CreativeModeTab$8
- XXX.world.item.CreativeModeTab$9
+ XXX.world.item.CrossbowItem
- XXX.world.item.DebugStickItem
+ XXX.world.item.DiggerItem
- XXX.world.item.DirectionalPlaceContext
+ XXX.world.item.DirectionalPlaceContext$1
- XXX.world.item.DoubleHighBlockItem
+ XXX.world.item.DyeableArmorItem
- XXX.world.item.DyeableHorseArmorItem
+ XXX.world.item.DyeableLeatherItem
+ XXX.world.item.DyeColor
- XXX.world.item.DyeItem
- XXX.world.item.EggItem
+ XXX.world.item.ElytraItem
- XXX.world.item.EmptyMapItem
+ XXX.world.item.EnchantedBookItem
- XXX.world.item.EnchantedGoldenAppleItem
+ XXX.world.item.EndCrystalItem
- XXX.world.item.EnderEyeItem
+ XXX.world.item.EnderpearlItem
- XXX.world.item.ExperienceBottleItem
+ XXX.world.item.FireChargeItem
- XXX.world.item.FireworkRocketItem
+ XXX.world.item.FireworkRocketItem$Shape
- XXX.world.item.FireworkStarItem
+ XXX.world.item.FishBucketItem
- XXX.world.item.FishingRodItem
+ XXX.world.item.FlintAndSteelItem
- XXX.world.item.GameMasterBlockItem
+ XXX.world.item.HangingEntityItem
- XXX.world.item.HoeItem
+ XXX.world.item.HoneyBottleItem
- XXX.world.item.HorseArmorItem
+ XXX.world.item.Item
- XXX.world.item.Item$1
+ XXX.world.item.Item$Properties
- XXX.world.item.ItemCooldowns
+ XXX.world.item.ItemCooldowns$1
- XXX.world.item.ItemCooldowns$CooldownInstance
+ XXX.world.item.ItemFrameItem
- XXX.world.item.ItemNameBlockItem
+ XXX.world.item.ItemPropertyFunction
+ XXX.world.item.Items
- XXX.world.item.ItemStack
- XXX.world.item.KnowledgeBookItem
+ XXX.world.item.LeadItem
- XXX.world.item.LingeringPotionItem
+ XXX.world.item.MapItem
- XXX.world.item.MilkBucketItem
+ XXX.world.item.MinecartItem
- XXX.world.item.MinecartItem$1
+ XXX.world.item.NameTagItem
+ XXX.world.item.package-info
- XXX.world.item.PickaxeItem
+ XXX.world.item.PlayerHeadItem
- XXX.world.item.PotionItem
+ XXX.world.item.ProjectileWeaponItem
- XXX.world.item.ProjectileWeaponItem$Type
+ XXX.world.item.Rarity
- XXX.world.item.RecordItem
+ XXX.world.item.SaddleItem
- XXX.world.item.ScaffoldingBlockItem
+ XXX.world.item.ServerItemCooldowns
- XXX.world.item.ShearsItem
+ XXX.world.item.ShieldItem
- XXX.world.item.ShovelItem
+ XXX.world.item.SignItem
- XXX.world.item.SimpleFoiledItem
+ XXX.world.item.SnowballItem
- XXX.world.item.SpawnEggItem
+ XXX.world.item.SpectralArrowItem
- XXX.world.item.SplashPotionItem
+ XXX.world.item.StandingAndWallBlockItem
- XXX.world.item.SuspiciousStewItem
+ XXX.world.item.SwordItem
- XXX.world.item.ThrowablePotionItem
+ XXX.world.item.Tier
- XXX.world.item.TieredItem
+ XXX.world.item.Tiers
- XXX.world.item.TippedArrowItem
+ XXX.world.item.TooltipFlag
- XXX.world.item.TooltipFlag$Default
+ XXX.world.item.TridentItem
- XXX.world.item.UseAnim
+ XXX.world.item.UseOnContext
- XXX.world.item.WaterLilyBlockItem
+ XXX.world.item.WritableBookItem
- XXX.world.item.WrittenBookItem
- XXX.world.level.BaseCommandBlock
+ XXX.world.level.BaseSpawner
- XXX.world.level.BlockAndBiomeGetter
+ XXX.world.level.BlockEventData
- XXX.world.level.BlockGetter
+ XXX.world.level.ChunkPos
- XXX.world.level.ChunkPos$1
+ XXX.world.level.ChunkTickList
- XXX.world.level.ClipContext
+ XXX.world.level.ClipContext$Block
- XXX.world.level.ClipContext$Fluid
+ XXX.world.level.ClipContext$ShapeGetter
- XXX.world.level.CollisionGetter
+ XXX.world.level.CollisionGetter$1
- XXX.world.level.CustomSpawner
+ XXX.world.level.EmptyBlockGetter
- XXX.world.level.EmptyTickList
+ XXX.world.level.EntityGetter
- XXX.world.level.Explosion
+ XXX.world.level.Explosion$BlockInteraction
- XXX.world.level.FoliageColor
+ XXX.world.level.ForcedChunksSavedData
- XXX.world.level.GameRules
+ XXX.world.level.GameRules$1
- XXX.world.level.GameRules$BooleanValue
+ XXX.world.level.GameRules$GameRuleTypeVisitor
- XXX.world.level.GameRules$IntegerValue
+ XXX.world.level.GameRules$Key
- XXX.world.level.GameRules$Type
+ XXX.world.level.GameRules$Value
- XXX.world.level.GameType
+ XXX.world.level.GrassColor
- XXX.world.level.ItemLike
+ XXX.world.level.Level
- XXX.world.level.LevelAccessor
+ XXX.world.level.LevelConflictException
- XXX.world.level.LevelReader
+ XXX.world.level.LevelSettings
+ XXX.world.level.LevelSimulatedReader
- XXX.world.level.LevelSimulatedRW
- XXX.world.level.LevelType
+ XXX.world.level.LevelWriter
- XXX.world.level.LightLayer
+ XXX.world.level.NaturalSpawner
- XXX.world.level.NaturalSpawner$1
- XXX.world.level.package-info
+ XXX.world.level.PathNavigationRegion
- XXX.world.level.PortalForcer
+ XXX.world.level.ServerTickList
- XXX.world.level.SpawnData
+ XXX.world.level.TickList
- XXX.world.level.TickNextTickData
+ XXX.world.level.TickPriority
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
XXX.mojang.math.Quaternion +2M
```
```
XXX.minecraft.nbt.LongArrayTag +2M -2M | +1P
```
```
XXX.minecraft.nbt.Tag -2M | +1P -2P
```
```
XXX.server.level.BlockDestructionProgress +4M
```
```
XXX.minecraft.util.Mth +3M
```
```
XXX.world.entity.Entity +2M
```
```
XXX.world.entity.LivingEntity -1P
```

</details>
<details>
<summary>
com.mojang.math.Quaternion
</summary>

```diff
- void mul(float)
- void normalize()
```

</details>
<details>
<summary>
net.minecraft.nbt.LongArrayTag
</summary>

```diff
- TagType getType()
- void <clinit>()
+ void <init>()
+ void load(DataInput,int,NbtAccounter)
```

</details>
<details>
<summary>
net.minecraft.nbt.Tag
</summary>

```diff
+ String getTagTypeName(int)
+ Tag newTag(byte)
```

</details>
<details>
<summary>
net.minecraft.server.level.BlockDestructionProgress
</summary>

```diff
- boolean equals(Object)
- int compareTo(BlockDestructionProgress)
- int compareTo(Object)
- int hashCode()
```

</details>
<details>
<summary>
net.minecraft.util.Mth
</summary>

```diff
- float fastInvSqrt(float)
- float rotlerp(float,float,float)
- float rotWrap(double)
```

</details>
<details>
<summary>
net.minecraft.world.entity.Entity
</summary>

```diff
- int getTeamColor()
- void setPosAndOldPos(double,double,double)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
- XXX.ai.attributes.Attribute
+ XXX.ai.attributes.AttributeInstance
- XXX.ai.attributes.AttributeModifier
+ XXX.ai.attributes.AttributeModifier$Operation
- XXX.ai.attributes.BaseAttribute
+ XXX.ai.attributes.BaseAttributeMap
- XXX.ai.attributes.ModifiableAttributeInstance
+ XXX.ai.attributes.ModifiableAttributeMap
+ XXX.ai.attributes.package-info
- XXX.ai.attributes.RangedAttribute
- XXX.ai.behavior.AcquirePoi
+ XXX.ai.behavior.AssignProfessionFromJobSite
- XXX.ai.behavior.Behavior
+ XXX.ai.behavior.Behavior$Status
- XXX.ai.behavior.BehaviorUtils
+ XXX.ai.behavior.BlockPosWrapper
- XXX.ai.behavior.Celebrate
+ XXX.ai.behavior.DoNothing
- XXX.ai.behavior.EntityPosWrapper
+ XXX.ai.behavior.GateBehavior
- XXX.ai.behavior.GateBehavior$1
+ XXX.ai.behavior.GateBehavior$OrderPolicy
- XXX.ai.behavior.GateBehavior$RunningPolicy
+ XXX.ai.behavior.GateBehavior$RunningPolicy$1
- XXX.ai.behavior.GateBehavior$RunningPolicy$2
+ XXX.ai.behavior.GiveGiftToHero
- XXX.ai.behavior.GoOutsideToCelebrate
+ XXX.ai.behavior.GoToClosestVillage
- XXX.ai.behavior.HarvestFarmland
+ XXX.ai.behavior.InsideBrownianWalk
- XXX.ai.behavior.InteractWith
+ XXX.ai.behavior.InteractWithDoor
- XXX.ai.behavior.JumpOnBed
+ XXX.ai.behavior.LocateHidingPlace
- XXX.ai.behavior.LocateHidingPlaceDuringRaid
+ XXX.ai.behavior.LookAndFollowTradingPlayerSink
- XXX.ai.behavior.LookAtTargetSink
+ XXX.ai.behavior.MakeLove
- XXX.ai.behavior.MoveToSkySeeingSpot
+ XXX.ai.behavior.MoveToTargetSink
- XXX.ai.behavior.package-info
- XXX.ai.behavior.PickUpItems
+ XXX.ai.behavior.PlayTagWithOtherKids
- XXX.ai.behavior.PositionWrapper
+ XXX.ai.behavior.ReactToBell
- XXX.ai.behavior.ResetProfession
+ XXX.ai.behavior.ResetRaidStatus
- XXX.ai.behavior.RingBell
+ XXX.ai.behavior.RunOne
- XXX.ai.behavior.SetClosestHomeAsWalkTarget
+ XXX.ai.behavior.SetEntityLookTarget
- XXX.ai.behavior.SetHiddenState
+ XXX.ai.behavior.SetLookAndInteract
- XXX.ai.behavior.SetRaidStatus
+ XXX.ai.behavior.SetWalkTargetAwayFromEntity
- XXX.ai.behavior.SetWalkTargetFromBlockMemory
+ XXX.ai.behavior.SetWalkTargetFromLookTarget
- XXX.ai.behavior.ShowTradesToPlayer
+ XXX.ai.behavior.SleepInBed
- XXX.ai.behavior.SocializeAtBell
+ XXX.ai.behavior.StrollAroundPoi
- XXX.ai.behavior.StrollToPoi
+ XXX.ai.behavior.StrollToPoiList
- XXX.ai.behavior.Swim
+ XXX.ai.behavior.TradeWithVillager
- XXX.ai.behavior.UpdateActivityFromSchedule
+ XXX.ai.behavior.ValidateNearbyPoi
- XXX.ai.behavior.VictoryStroll
+ XXX.ai.behavior.VillageBoundRandomStroll
- XXX.ai.behavior.VillagerCalmDown
+ XXX.ai.behavior.VillagerGoalPackages
- XXX.ai.behavior.VillagerPanicTrigger
+ XXX.ai.behavior.WakeUp
- XXX.ai.behavior.WeightedList
+ XXX.ai.behavior.WeightedList$1
- XXX.ai.behavior.WeightedList$WeightedEntry
+ XXX.ai.behavior.WorkAtPoi
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
- XXX.ai.goal.FollowOwnerFlyingGoal
+ XXX.ai.goal.FollowOwnerGoal
- XXX.ai.goal.FollowParentGoal
+ XXX.ai.goal.Goal
- XXX.ai.goal.Goal$Flag
+ XXX.ai.goal.GoalSelector
- XXX.ai.goal.GoalSelector$1
+ XXX.ai.goal.GoalSelector$2
- XXX.ai.goal.InteractGoal
+ XXX.ai.goal.JumpGoal
- XXX.ai.goal.LandOnOwnersShoulderGoal
+ XXX.ai.goal.LeapAtTargetGoal
- XXX.ai.goal.LlamaFollowCaravanGoal
+ XXX.ai.goal.LookAtPlayerGoal
- XXX.ai.goal.LookAtTradingPlayerGoal
+ XXX.ai.goal.MeleeAttackGoal
- XXX.ai.goal.MoveBackToVillage
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
- XXX.ai.goal.SitGoal
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
+ XXX.ai.gossip.GossipContainer
- XXX.ai.gossip.GossipContainer$1
+ XXX.ai.gossip.GossipContainer$EntityGossips
- XXX.ai.gossip.GossipContainer$GossipEntry
+ XXX.ai.gossip.GossipType
- XXX.ai.gossip.package-info
+ XXX.ai.memory.MemoryModuleType
- XXX.ai.memory.MemoryStatus
- XXX.ai.memory.package-info
+ XXX.ai.memory.WalkTarget
+ XXX.ai.navigation.FlyingPathNavigation
- XXX.ai.navigation.GroundPathNavigation
- XXX.ai.navigation.package-info
+ XXX.ai.navigation.PathNavigation
- XXX.ai.navigation.WallClimberNavigation
+ XXX.ai.navigation.WaterBoundPathNavigation
- XXX.ai.sensing.DummySensor
+ XXX.ai.sensing.GolemSensor
- XXX.ai.sensing.HurtBySensor
+ XXX.ai.sensing.InteractableDoorsSensor
- XXX.ai.sensing.NearestBedSensor
+ XXX.ai.sensing.NearestLivingEntitySensor
+ XXX.ai.sensing.package-info
- XXX.ai.sensing.PlayerSensor
+ XXX.ai.sensing.SecondaryPoiSensor
- XXX.ai.sensing.Sensing
+ XXX.ai.sensing.Sensor
- XXX.ai.sensing.SensorType
+ XXX.ai.sensing.VillagerBabiesSensor
- XXX.ai.sensing.VillagerHostilesSensor
+ XXX.ai.targeting.package-info
- XXX.ai.targeting.TargetingConditions
+ XXX.ai.util.package-info
- XXX.ai.util.RandomPos
- XXX.ai.village.package-info
- XXX.ai.village.ReputationEventType
+ XXX.ai.village.ReputationEventType$1
- XXX.ai.village.VillageSiege
+ XXX.ai.village.VillageSiege$State
+ XXX.animal.horse.AbstractChestedHorse
- XXX.animal.horse.AbstractHorse
+ XXX.animal.horse.Donkey
- XXX.animal.horse.Horse
+ XXX.animal.horse.Horse$HorseGroupData
- XXX.animal.horse.Llama
+ XXX.animal.horse.Llama$1
- XXX.animal.horse.Llama$LlamaAttackWolfGoal
+ XXX.animal.horse.Llama$LlamaGroupData
- XXX.animal.horse.Llama$LlamaHurtByTargetGoal
+ XXX.animal.horse.Mule
+ XXX.animal.horse.package-info
- XXX.animal.horse.SkeletonHorse
+ XXX.animal.horse.SkeletonTrapGoal
- XXX.animal.horse.TraderLlama
+ XXX.animal.horse.TraderLlama$TraderLlamaDefendWanderingTraderGoal
- XXX.animal.horse.ZombieHorse
+ XXX.blaze3d.platform.ClipboardManager
- XXX.blaze3d.platform.DebugMemoryUntracker
+ XXX.blaze3d.platform.DisplayData
+ XXX.blaze3d.platform.TextureUtil
- XXX.blaze3d.platform.VideoMode
+ XXX.blaze3d.platform.Window
- XXX.blaze3d.platform.WindowEventHandler
+ XXX.blaze3d.shaders.AbstractUniform
- XXX.blaze3d.shaders.BlendMode
+ XXX.blaze3d.shaders.Effect
- XXX.blaze3d.shaders.Program
+ XXX.blaze3d.shaders.Program$Type
- XXX.blaze3d.shaders.ProgramManager
+ XXX.blaze3d.shaders.Uniform
- XXX.blaze3d.systems.RenderSystem
+ XXX.blaze3d.systems.RenderSystem$Profile
+ XXX.blaze3d.systems.RenderSystem$Profile$2
- XXX.blaze3d.vertex.BreakingTextureGenerator$1
+ XXX.blaze3d.vertex.BufferBuilder
- XXX.blaze3d.vertex.BufferBuilder$1
+ XXX.blaze3d.vertex.BufferBuilder$DrawState
- XXX.blaze3d.vertex.BufferBuilder$State
+ XXX.blaze3d.vertex.BufferUploader
- XXX.blaze3d.vertex.BufferVertexConsumer
- XXX.blaze3d.vertex.DefaultedVertexConsumer
- XXX.blaze3d.vertex.PoseStack
+ XXX.blaze3d.vertex.Tesselator
- XXX.blaze3d.vertex.VertexBuffer
+ XXX.blaze3d.vertex.VertexFormatElement
- XXX.blaze3d.vertex.VertexFormatElement$Type
+ XXX.blaze3d.vertex.VertexFormatElement$Usage
- XXX.blaze3d.vertex.VertexFormatElement$Usage$SetupState
+ XXX.block.entity.AbstractFurnaceBlockEntity
- XXX.block.entity.AbstractFurnaceBlockEntity$1
+ XXX.block.entity.BannerBlockEntity
- XXX.block.entity.BannerPattern
+ XXX.block.entity.BannerPattern$Builder
- XXX.block.entity.BarrelBlockEntity
+ XXX.block.entity.BaseContainerBlockEntity
- XXX.block.entity.BeaconBlockEntity
+ XXX.block.entity.BeaconBlockEntity$1
- XXX.block.entity.BeaconBlockEntity$BeaconBeamSection
+ XXX.block.entity.BedBlockEntity
- XXX.block.entity.BeehiveBlockEntity
+ XXX.block.entity.BeehiveBlockEntity$1
- XXX.block.entity.BeehiveBlockEntity$BeeData
+ XXX.block.entity.BeehiveBlockEntity$BeeReleaseStatus
- XXX.block.entity.BellBlockEntity
+ XXX.block.entity.BlastFurnaceBlockEntity
- XXX.block.entity.BlockEntity
+ XXX.block.entity.BlockEntityType
- XXX.block.entity.BlockEntityType$Builder
+ XXX.block.entity.BrewingStandBlockEntity
- XXX.block.entity.BrewingStandBlockEntity$1
+ XXX.block.entity.CampfireBlockEntity
- XXX.block.entity.ChestBlockEntity
+ XXX.block.entity.CommandBlockEntity
- XXX.block.entity.CommandBlockEntity$1
+ XXX.block.entity.CommandBlockEntity$Mode
- XXX.block.entity.ComparatorBlockEntity
+ XXX.block.entity.ConduitBlockEntity
- XXX.block.entity.DaylightDetectorBlockEntity
+ XXX.block.entity.DispenserBlockEntity
- XXX.block.entity.DropperBlockEntity
+ XXX.block.entity.EnchantmentTableBlockEntity
- XXX.block.entity.EnderChestBlockEntity
+ XXX.block.entity.FurnaceBlockEntity
- XXX.block.entity.Hopper
+ XXX.block.entity.HopperBlockEntity
- XXX.block.entity.JigsawBlockEntity
+ XXX.block.entity.JukeboxBlockEntity
- XXX.block.entity.LecternBlockEntity
+ XXX.block.entity.LecternBlockEntity$1
- XXX.block.entity.LecternBlockEntity$2
+ XXX.block.entity.LidBlockEntity
- XXX.block.entity.package-info
- XXX.block.entity.RandomizableContainerBlockEntity
+ XXX.block.entity.ShulkerBoxBlockEntity
- XXX.block.entity.ShulkerBoxBlockEntity$1
+ XXX.block.entity.ShulkerBoxBlockEntity$AnimationStatus
- XXX.block.entity.SignBlockEntity
+ XXX.block.entity.SkullBlockEntity
- XXX.block.entity.SmokerBlockEntity
+ XXX.block.entity.SpawnerBlockEntity
- XXX.block.entity.SpawnerBlockEntity$1
+ XXX.block.entity.StructureBlockEntity
- XXX.block.entity.StructureBlockEntity$1
+ XXX.block.entity.StructureBlockEntity$UpdateType
- XXX.block.entity.TheEndGatewayBlockEntity
+ XXX.block.entity.TheEndPortalBlockEntity
- XXX.block.entity.TickableBlockEntity
+ XXX.block.entity.TrappedChestBlockEntity
+ XXX.block.grower.AbstractMegaTreeGrower
- XXX.block.grower.AbstractTreeGrower
+ XXX.block.grower.AcaciaTreeGrower
- XXX.block.grower.BirchTreeGrower
+ XXX.block.grower.DarkOakTreeGrower
- XXX.block.grower.JungleTreeGrower
+ XXX.block.grower.OakTreeGrower
+ XXX.block.grower.package-info
- XXX.block.grower.SpruceTreeGrower
+ XXX.block.model.FaceBakery
- XXX.block.model.FaceBakery$1
+ XXX.block.model.FaceBakery$2
+ XXX.block.model.FaceBakery$4
+ XXX.block.model.FaceBakery$Rotation
+ XXX.block.piston.MovingPistonBlock
+ XXX.block.piston.package-info
- XXX.block.piston.PistonBaseBlock
+ XXX.block.piston.PistonBaseBlock$1
- XXX.block.piston.PistonHeadBlock
+ XXX.block.piston.PistonHeadBlock$1
- XXX.block.piston.PistonMovingBlockEntity
+ XXX.block.piston.PistonMovingBlockEntity$1
- XXX.block.piston.PistonStructureResolver
- XXX.block.state.AbstractStateHolder
+ XXX.block.state.AbstractStateHolder$1
- XXX.block.state.BlockState
+ XXX.block.state.BlockState$1
- XXX.block.state.BlockState$Cache
+ XXX.block.state.package-info
+ XXX.block.state.StateDefinition
- XXX.block.state.StateDefinition$Builder
+ XXX.block.state.StateDefinition$Factory
- XXX.block.state.StateHolder
+ XXX.boss.enderdragon.EndCrystal
- XXX.boss.enderdragon.EnderDragon
+ XXX.boss.enderdragon.package-info
- XXX.boss.wither.package-info
- XXX.boss.wither.WitherBoss
+ XXX.boss.wither.WitherBoss$WitherDoNothingGoal
- XXX.chunk.storage.ChunkSerializer
+ XXX.chunk.storage.ChunkStorage
- XXX.chunk.storage.OldChunkStorage
+ XXX.chunk.storage.OldChunkStorage$OldLevelChunk
- XXX.chunk.storage.package-info
- XXX.chunk.storage.RegionBitmap
+ XXX.chunk.storage.RegionFile
- XXX.chunk.storage.RegionFile$ChunkBuffer
+ XXX.chunk.storage.RegionFile$CommitOp
- XXX.chunk.storage.RegionFileStorage
+ XXX.chunk.storage.RegionFileVersion
- XXX.chunk.storage.RegionFileVersion$StreamWrapper
+ XXX.chunk.storage.SectionStorage
+ XXX.client.gui.Font$Effect
- XXX.client.model.AgeableListModel
- XXX.client.model.ColorableListModel
- XXX.client.model.DrownedModel
+ XXX.client.model.ElytraModel
- XXX.client.model.EndermanModel
+ XXX.client.model.EndermiteModel
- XXX.client.model.EntityModel
+ XXX.client.model.EvokerFangsModel
- XXX.client.model.FoxModel
+ XXX.client.model.GhastModel
- XXX.client.model.GiantZombieModel
+ XXX.client.model.GuardianModel
- XXX.client.model.HeadedModel
- XXX.client.model.ListModel
+ XXX.client.model.LlamaModel
- XXX.client.model.LlamaSpitModel
+ XXX.client.model.MinecartModel
- XXX.client.model.Model
+ XXX.client.model.ModelUtils
- XXX.client.model.OcelotModel
+ XXX.client.model.package-info
+ XXX.client.model.PandaModel
- XXX.client.model.ParrotModel
+ XXX.client.model.ParrotModel$1
- XXX.client.model.ParrotModel$State
+ XXX.client.model.PhantomModel
- XXX.client.model.PigModel
+ XXX.client.model.PillagerModel
+ XXX.client.model.SilverfishModel
- XXX.client.model.SkeletonModel
+ XXX.client.model.SkullModel
- XXX.client.model.SlimeModel
+ XXX.client.model.SnowGolemModel
- XXX.client.model.SpiderModel
+ XXX.client.model.SquidModel
- XXX.client.model.TridentModel
+ XXX.client.model.TropicalFishModelA
- XXX.client.model.TropicalFishModelB
+ XXX.client.model.TurtleModel
- XXX.client.model.VillagerModel
+ XXX.client.model.WitchModel
- XXX.client.model.WitherBossModel
+ XXX.client.model.WolfModel
- XXX.client.model.ZombieModel
+ XXX.client.model.ZombieVillagerModel
- XXX.client.multiplayer.ClientAdvancements
+ XXX.client.multiplayer.ClientAdvancements$Listener
- XXX.client.multiplayer.ClientChunkCache
+ XXX.client.multiplayer.ClientChunkCache$1
- XXX.client.multiplayer.ClientChunkCache$Storage
+ XXX.client.multiplayer.ClientHandshakePacketListenerImpl
- XXX.client.multiplayer.ClientPacketListener
+ XXX.client.multiplayer.ClientPacketListener$1
- XXX.client.multiplayer.ClientSuggestionProvider
+ XXX.client.multiplayer.MultiPlayerGameMode
- XXX.client.multiplayer.MultiPlayerLevel
- XXX.client.multiplayer.package-info
+ XXX.client.multiplayer.PlayerInfo
- XXX.client.multiplayer.ServerAddress
+ XXX.client.multiplayer.ServerData
- XXX.client.multiplayer.ServerData$ServerPackStatus
+ XXX.client.multiplayer.ServerList
- XXX.client.multiplayer.ServerStatusPinger
+ XXX.client.multiplayer.ServerStatusPinger$1
- XXX.client.multiplayer.ServerStatusPinger$2
+ XXX.client.multiplayer.ServerStatusPinger$2$1
- XXX.client.particle.AttackSweepParticle
+ XXX.client.particle.AttackSweepParticle$1
- XXX.client.particle.AttackSweepParticle$Provider
+ XXX.client.particle.BarrierParticle
- XXX.client.particle.BarrierParticle$1
+ XXX.client.particle.BarrierParticle$Provider
- XXX.client.particle.BreakingItemParticle
+ XXX.client.particle.BreakingItemParticle$1
- XXX.client.particle.BreakingItemParticle$Provider
+ XXX.client.particle.BreakingItemParticle$SlimeProvider
- XXX.client.particle.BreakingItemParticle$SnowballProvider
+ XXX.client.particle.BubbleColumnUpParticle
- XXX.client.particle.BubbleColumnUpParticle$1
+ XXX.client.particle.BubbleColumnUpParticle$Provider
- XXX.client.particle.BubbleParticle
+ XXX.client.particle.BubbleParticle$1
- XXX.client.particle.BubbleParticle$Provider
+ XXX.client.particle.BubblePopParticle
- XXX.client.particle.BubblePopParticle$1
+ XXX.client.particle.BubblePopParticle$Provider
- XXX.client.particle.CampfireSmokeParticle
+ XXX.client.particle.CampfireSmokeParticle$1
- XXX.client.particle.CampfireSmokeParticle$CosyProvider
+ XXX.client.particle.CampfireSmokeParticle$SignalProvider
- XXX.client.particle.CritParticle
+ XXX.client.particle.CritParticle$1
- XXX.client.particle.CritParticle$DamageIndicatorProvider
+ XXX.client.particle.CritParticle$MagicProvider
- XXX.client.particle.CritParticle$Provider
+ XXX.client.particle.DragonBreathParticle
- XXX.client.particle.DragonBreathParticle$1
+ XXX.client.particle.DragonBreathParticle$Provider
- XXX.client.particle.DripParticle
+ XXX.client.particle.DripParticle$1
- XXX.client.particle.DripParticle$CoolingDripHangParticle
+ XXX.client.particle.DripParticle$DripHangParticle
- XXX.client.particle.DripParticle$DripLandParticle
+ XXX.client.particle.DripParticle$FallAndLandParticle
- XXX.client.particle.DripParticle$FallingParticle
+ XXX.client.particle.DripParticle$HoneyFallAndLandParticle
- XXX.client.particle.DripParticle$HoneyFallProvider
+ XXX.client.particle.DripParticle$HoneyHangProvider
- XXX.client.particle.DripParticle$HoneyLandProvider
+ XXX.client.particle.DripParticle$LavaFallProvider
- XXX.client.particle.DripParticle$LavaHangProvider
+ XXX.client.particle.DripParticle$LavaLandProvider
- XXX.client.particle.DripParticle$NectarFallProvider
+ XXX.client.particle.DripParticle$WaterFallProvider
- XXX.client.particle.DripParticle$WaterHangProvider
+ XXX.client.particle.DustParticle
- XXX.client.particle.DustParticle$1
+ XXX.client.particle.DustParticle$Provider
- XXX.client.particle.EnchantmentTableParticle
+ XXX.client.particle.EnchantmentTableParticle$1
- XXX.client.particle.EnchantmentTableParticle$NautilusProvider
+ XXX.client.particle.EnchantmentTableParticle$Provider
- XXX.client.particle.EndRodParticle
+ XXX.client.particle.EndRodParticle$1
- XXX.client.particle.EndRodParticle$Provider
+ XXX.client.particle.ExplodeParticle
- XXX.client.particle.ExplodeParticle$Provider
+ XXX.client.particle.FallingDustParticle
- XXX.client.particle.FallingDustParticle$1
+ XXX.client.particle.FallingDustParticle$Provider
- XXX.client.particle.FireworkParticles
+ XXX.client.particle.FireworkParticles$1
- XXX.client.particle.FireworkParticles$FlashProvider
+ XXX.client.particle.FireworkParticles$OverlayParticle
- XXX.client.particle.FireworkParticles$SparkParticle
+ XXX.client.particle.FireworkParticles$SparkProvider
- XXX.client.particle.FireworkParticles$Starter
+ XXX.client.particle.FlameParticle
- XXX.client.particle.FlameParticle$1
+ XXX.client.particle.FlameParticle$Provider
- XXX.client.particle.HeartParticle
+ XXX.client.particle.HeartParticle$1
- XXX.client.particle.HeartParticle$AngryVillagerProvider
+ XXX.client.particle.HeartParticle$Provider
- XXX.client.particle.HugeExplosionParticle
+ XXX.client.particle.HugeExplosionParticle$1
- XXX.client.particle.HugeExplosionParticle$Provider
+ XXX.client.particle.HugeExplosionSeedParticle
- XXX.client.particle.HugeExplosionSeedParticle$1
+ XXX.client.particle.HugeExplosionSeedParticle$Provider
- XXX.client.particle.ItemPickupParticle
+ XXX.client.particle.LargeSmokeParticle
- XXX.client.particle.LargeSmokeParticle$Provider
+ XXX.client.particle.LavaParticle
- XXX.client.particle.LavaParticle$1
+ XXX.client.particle.LavaParticle$Provider
- XXX.client.particle.MobAppearanceParticle
+ XXX.client.particle.MobAppearanceParticle$1
- XXX.client.particle.MobAppearanceParticle$Provider
+ XXX.client.particle.NoRenderParticle
- XXX.client.particle.NoteParticle
+ XXX.client.particle.NoteParticle$1
- XXX.client.particle.NoteParticle$Provider
+ XXX.client.particle.package-info
+ XXX.client.particle.Particle
- XXX.client.particle.ParticleDescription
+ XXX.client.particle.ParticleEngine
- XXX.client.particle.ParticleEngine$1
+ XXX.client.particle.ParticleEngine$MutableSpriteSet
- XXX.client.particle.ParticleEngine$SpriteParticleRegistration
+ XXX.client.particle.ParticleProvider
- XXX.client.particle.ParticleRenderType
+ XXX.client.particle.ParticleRenderType$1
- XXX.client.particle.ParticleRenderType$2
+ XXX.client.particle.ParticleRenderType$3
- XXX.client.particle.ParticleRenderType$4
+ XXX.client.particle.ParticleRenderType$5
- XXX.client.particle.ParticleRenderType$6
+ XXX.client.particle.PlayerCloudParticle
- XXX.client.particle.PlayerCloudParticle$1
+ XXX.client.particle.PlayerCloudParticle$Provider
- XXX.client.particle.PlayerCloudParticle$SneezeProvider
+ XXX.client.particle.PortalParticle
- XXX.client.particle.PortalParticle$1
+ XXX.client.particle.PortalParticle$Provider
- XXX.client.particle.SimpleAnimatedParticle
+ XXX.client.particle.SingleQuadParticle
- XXX.client.particle.SmokeParticle
+ XXX.client.particle.SmokeParticle$Provider
- XXX.client.particle.SpellParticle
+ XXX.client.particle.SpellParticle$1
- XXX.client.particle.SpellParticle$AmbientMobProvider
+ XXX.client.particle.SpellParticle$InstantProvider
- XXX.client.particle.SpellParticle$MobProvider
+ XXX.client.particle.SpellParticle$Provider
- XXX.client.particle.SpellParticle$WitchProvider
+ XXX.client.particle.SpitParticle
- XXX.client.particle.SpitParticle$1
+ XXX.client.particle.SpitParticle$Provider
- XXX.client.particle.SplashParticle
+ XXX.client.particle.SplashParticle$1
- XXX.client.particle.SplashParticle$Provider
+ XXX.client.particle.SpriteSet
- XXX.client.particle.SquidInkParticle
+ XXX.client.particle.SquidInkParticle$1
- XXX.client.particle.SquidInkParticle$Provider
+ XXX.client.particle.SuspendedParticle
- XXX.client.particle.SuspendedParticle$1
+ XXX.client.particle.SuspendedParticle$Provider
- XXX.client.particle.SuspendedTownParticle
+ XXX.client.particle.SuspendedTownParticle$1
- XXX.client.particle.SuspendedTownParticle$ComposterFillProvider
+ XXX.client.particle.SuspendedTownParticle$DolphinSpeedProvider
- XXX.client.particle.SuspendedTownParticle$HappyVillagerProvider
+ XXX.client.particle.SuspendedTownParticle$Provider
- XXX.client.particle.TerrainParticle
+ XXX.client.particle.TerrainParticle$Provider
- XXX.client.particle.TextureSheetParticle
+ XXX.client.particle.TotemParticle
- XXX.client.particle.TotemParticle$1
+ XXX.client.particle.TotemParticle$Provider
- XXX.client.particle.TrackingEmitter
+ XXX.client.particle.WakeParticle
- XXX.client.particle.WakeParticle$1
+ XXX.client.particle.WakeParticle$Provider
- XXX.client.particle.WaterCurrentDownParticle
+ XXX.client.particle.WaterCurrentDownParticle$1
- XXX.client.particle.WaterCurrentDownParticle$Provider
+ XXX.client.particle.WaterDropParticle
- XXX.client.particle.WaterDropParticle$Provider
- XXX.client.player.AbstractClientPlayer
+ XXX.client.player.Input
- XXX.client.player.KeyboardInput
+ XXX.client.player.LocalPlayer
- XXX.client.player.LocalPlayer$1
- XXX.client.player.package-info
+ XXX.client.player.RemotePlayer
+ XXX.client.renderer.BiomeColors
- XXX.client.renderer.BiomeColors$ColorResolver
+ XXX.client.renderer.ChunkBufferBuilderPack
- XXX.client.renderer.CubeMap
+ XXX.client.renderer.EffectInstance
- XXX.client.renderer.EntityBlockRenderer
+ XXX.client.renderer.FaceInfo
- XXX.client.renderer.FaceInfo$1
+ XXX.client.renderer.FaceInfo$Constants
- XXX.client.renderer.FaceInfo$VertexInfo
+ XXX.client.renderer.FogRenderer
- XXX.client.renderer.FogRenderer$FogMode
- XXX.client.renderer.MultiBufferSource$BufferSource
- XXX.client.renderer.RenderType
- XXX.client.renderer.RenderType$StatefullRenderType
- XXX.client.renderer.ScreenEffectRenderer
+ XXX.client.renderer.ViewArea
- XXX.client.renderer.VirtualScreen
+ XXX.core.dispenser.AbstractProjectileDispenseBehavior
- XXX.core.dispenser.BoatDispenseItemBehavior
+ XXX.core.dispenser.DefaultDispenseItemBehavior
- XXX.core.dispenser.DispenseItemBehavior
+ XXX.core.dispenser.DispenseItemBehavior$1
- XXX.core.dispenser.DispenseItemBehavior$10
+ XXX.core.dispenser.DispenseItemBehavior$11
- XXX.core.dispenser.DispenseItemBehavior$12
+ XXX.core.dispenser.DispenseItemBehavior$13
- XXX.core.dispenser.DispenseItemBehavior$14
+ XXX.core.dispenser.DispenseItemBehavior$15
- XXX.core.dispenser.DispenseItemBehavior$16
+ XXX.core.dispenser.DispenseItemBehavior$17
- XXX.core.dispenser.DispenseItemBehavior$18
+ XXX.core.dispenser.DispenseItemBehavior$19
- XXX.core.dispenser.DispenseItemBehavior$2
+ XXX.core.dispenser.DispenseItemBehavior$20
- XXX.core.dispenser.DispenseItemBehavior$21
+ XXX.core.dispenser.DispenseItemBehavior$3
- XXX.core.dispenser.DispenseItemBehavior$4
+ XXX.core.dispenser.DispenseItemBehavior$5
- XXX.core.dispenser.DispenseItemBehavior$6
+ XXX.core.dispenser.DispenseItemBehavior$7
- XXX.core.dispenser.DispenseItemBehavior$7$1
+ XXX.core.dispenser.DispenseItemBehavior$8
- XXX.core.dispenser.DispenseItemBehavior$8$1
+ XXX.core.dispenser.DispenseItemBehavior$9
- XXX.core.dispenser.OptionalDispenseItemBehavior
- XXX.core.dispenser.package-info
+ XXX.core.dispenser.ShulkerBoxDispenseBehavior
- XXX.core.particles.BlockParticleOption
+ XXX.core.particles.BlockParticleOption$1
- XXX.core.particles.DustParticleOptions
+ XXX.core.particles.DustParticleOptions$1
- XXX.core.particles.ItemParticleOption
+ XXX.core.particles.ItemParticleOption$1
- XXX.core.particles.package-info
- XXX.core.particles.ParticleOptions
+ XXX.core.particles.ParticleOptions$Deserializer
- XXX.core.particles.ParticleType
+ XXX.core.particles.ParticleTypes
- XXX.core.particles.SimpleParticleType
+ XXX.core.particles.SimpleParticleType$1
+ XXX.data.advancements.AdvancementProvider
- XXX.data.advancements.AdventureAdvancements
+ XXX.data.advancements.HusbandryAdvancements
- XXX.data.advancements.NetherAdvancements
+ XXX.data.advancements.package-info
+ XXX.data.advancements.StoryAdvancements
- XXX.data.advancements.TheEndAdvancements
- XXX.data.info.BlockListReport
+ XXX.data.info.CommandsReport
+ XXX.data.info.package-info
- XXX.data.info.RegistryDumpReport
- XXX.data.loot.BlockLoot
+ XXX.data.loot.ChestLoot
- XXX.data.loot.EntityLoot
+ XXX.data.loot.FishingLoot
- XXX.data.loot.GiftLoot
+ XXX.data.loot.LootTableProvider
- XXX.data.loot.package-info
- XXX.data.recipes.FinishedRecipe
- XXX.data.recipes.package-info
+ XXX.data.recipes.RecipeProvider
- XXX.data.recipes.ShapedRecipeBuilder
+ XXX.data.recipes.ShapedRecipeBuilder$Result
- XXX.data.recipes.ShapelessRecipeBuilder
+ XXX.data.recipes.ShapelessRecipeBuilder$Result
- XXX.data.recipes.SimpleCookingRecipeBuilder
+ XXX.data.recipes.SimpleCookingRecipeBuilder$Result
- XXX.data.recipes.SingleItemRecipeBuilder
+ XXX.data.recipes.SingleItemRecipeBuilder$Result
- XXX.data.recipes.SpecialRecipeBuilder
+ XXX.data.recipes.SpecialRecipeBuilder$1
+ XXX.data.structures.NbtToSnbt
- XXX.data.structures.package-info
- XXX.data.structures.SnbtToNbt
+ XXX.data.structures.SnbtToNbt$Filter
- XXX.data.structures.SnbtToNbt$TaskResult
+ XXX.data.structures.StructureUpdater
+ XXX.data.tags.BlockTagsProvider
- XXX.data.tags.EntityTypeTagsProvider
+ XXX.data.tags.FluidTagsProvider
- XXX.data.tags.ItemTagsProvider
- XXX.data.tags.package-info
+ XXX.data.tags.TagsProvider
- XXX.dimension.end.DragonRespawnAnimation
+ XXX.dimension.end.DragonRespawnAnimation$1
- XXX.dimension.end.DragonRespawnAnimation$2
+ XXX.dimension.end.DragonRespawnAnimation$3
- XXX.dimension.end.DragonRespawnAnimation$4
+ XXX.dimension.end.DragonRespawnAnimation$5
- XXX.dimension.end.EndDragonFight
- XXX.dimension.end.package-info
+ XXX.dimension.end.TheEndDimension
- XXX.enderdragon.phases.AbstractDragonPhaseInstance
+ XXX.enderdragon.phases.AbstractDragonSittingPhase
- XXX.enderdragon.phases.DragonChargePlayerPhase
+ XXX.enderdragon.phases.DragonDeathPhase
- XXX.enderdragon.phases.DragonHoldingPatternPhase
+ XXX.enderdragon.phases.DragonHoverPhase
- XXX.enderdragon.phases.DragonLandingApproachPhase
+ XXX.enderdragon.phases.DragonLandingPhase
- XXX.enderdragon.phases.DragonPhaseInstance
+ XXX.enderdragon.phases.DragonSittingAttackingPhase
- XXX.enderdragon.phases.DragonSittingFlamingPhase
+ XXX.enderdragon.phases.DragonSittingScanningPhase
- XXX.enderdragon.phases.DragonStrafePlayerPhase
+ XXX.enderdragon.phases.DragonTakeoffPhase
- XXX.enderdragon.phases.EnderDragonPhase
+ XXX.enderdragon.phases.EnderDragonPhaseManager
- XXX.enderdragon.phases.package-info
+ XXX.entity.ai.Brain
+ XXX.entity.ai.package-info
- XXX.entity.ambient.AmbientCreature
+ XXX.entity.ambient.Bat
- XXX.entity.ambient.package-info
+ XXX.entity.animal.AbstractFish
- XXX.entity.animal.AbstractFish$FishMoveControl
+ XXX.entity.animal.AbstractFish$FishSwimGoal
- XXX.entity.animal.AbstractGolem
+ XXX.entity.animal.AbstractSchoolingFish
- XXX.entity.animal.AbstractSchoolingFish$SchoolSpawnGroupData
+ XXX.entity.animal.Animal
- XXX.entity.animal.Bee
+ XXX.entity.animal.Bee$1
- XXX.entity.animal.Bee$BaseBeeGoal
+ XXX.entity.animal.Bee$BeeAttackGoal
- XXX.entity.animal.Bee$BeeBecomeAngryTargetGoal
+ XXX.entity.animal.Bee$BeeEnterHiveGoal
- XXX.entity.animal.Bee$BeeGoToBlockGoal
+ XXX.entity.animal.Bee$BeeGoToHiveGoal
- XXX.entity.animal.Bee$BeeGoToKnownFlowerGoal
+ XXX.entity.animal.Bee$BeeGrowCropGoal
- XXX.entity.animal.Bee$BeeHurtByOtherGoal
+ XXX.entity.animal.Bee$BeeLocateHiveGoal
- XXX.entity.animal.Bee$BeeLookControl
+ XXX.entity.animal.Bee$BeePollinateGoal
- XXX.entity.animal.Bee$BeeWanderGoal
+ XXX.entity.animal.Cat
- XXX.entity.animal.Cat$CatAvoidEntityGoal
+ XXX.entity.animal.Cat$CatRelaxOnOwnerGoal
- XXX.entity.animal.Cat$CatTemptGoal
+ XXX.entity.animal.Chicken
- XXX.entity.animal.Cod
+ XXX.entity.animal.Cow
- XXX.entity.animal.Dolphin
+ XXX.entity.animal.Dolphin$1
- XXX.entity.animal.Dolphin$DolphinMoveControl
+ XXX.entity.animal.Dolphin$DolphinSwimToTreasureGoal
- XXX.entity.animal.Dolphin$DolphinSwimWithPlayerGoal
+ XXX.entity.animal.Dolphin$PlayWithItemsGoal
- XXX.entity.animal.FlyingAnimal
+ XXX.entity.animal.Fox
- XXX.entity.animal.Fox$1
+ XXX.entity.animal.Fox$DefendTrustedTargetGoal
- XXX.entity.animal.Fox$FaceplantGoal
+ XXX.entity.animal.Fox$FoxAlertableEntitiesSelector
- XXX.entity.animal.Fox$FoxBehaviorGoal
+ XXX.entity.animal.Fox$FoxBreedGoal
- XXX.entity.animal.Fox$FoxEatBerriesGoal
+ XXX.entity.animal.Fox$FoxFloatGoal
- XXX.entity.animal.Fox$FoxFollowParentGoal
+ XXX.entity.animal.Fox$FoxGroupData
- XXX.entity.animal.Fox$FoxLookAtPlayerGoal
+ XXX.entity.animal.Fox$FoxLookControl
- XXX.entity.animal.Fox$FoxMeleeAttackGoal
+ XXX.entity.animal.Fox$FoxMoveControl
- XXX.entity.animal.Fox$FoxPanicGoal
+ XXX.entity.animal.Fox$FoxPounceGoal
- XXX.entity.animal.Fox$FoxSearchForItemsGoal
+ XXX.entity.animal.Fox$FoxStrollThroughVillageGoal
- XXX.entity.animal.Fox$PerchAndSearchGoal
+ XXX.entity.animal.Fox$SeekShelterGoal
- XXX.entity.animal.Fox$SleepGoal
+ XXX.entity.animal.Fox$StalkPreyGoal
- XXX.entity.animal.Fox$Type
+ XXX.entity.animal.IronGolem
- XXX.entity.animal.MushroomCow
+ XXX.entity.animal.MushroomCow$MushroomType
- XXX.entity.animal.Ocelot
+ XXX.entity.animal.Ocelot$OcelotAvoidEntityGoal
- XXX.entity.animal.Ocelot$OcelotTemptGoal
- XXX.entity.animal.package-info
+ XXX.entity.animal.Panda
- XXX.entity.animal.Panda$Gene
+ XXX.entity.animal.Panda$PandaAttackGoal
- XXX.entity.animal.Panda$PandaAvoidGoal
+ XXX.entity.animal.Panda$PandaBreedGoal
- XXX.entity.animal.Panda$PandaHurtByTargetGoal
+ XXX.entity.animal.Panda$PandaLieOnBackGoal
- XXX.entity.animal.Panda$PandaLookAtPlayerGoal
+ XXX.entity.animal.Panda$PandaMoveControl
- XXX.entity.animal.Panda$PandaPanicGoal
+ XXX.entity.animal.Panda$PandaRollGoal
- XXX.entity.animal.Panda$PandaSitGoal
+ XXX.entity.animal.Panda$PandaSneezeGoal
- XXX.entity.animal.Parrot
+ XXX.entity.animal.Parrot$1
- XXX.entity.animal.Pig
+ XXX.entity.animal.PolarBear
- XXX.entity.animal.PolarBear$PolarBearAttackPlayersGoal
+ XXX.entity.animal.PolarBear$PolarBearHurtByTargetGoal
- XXX.entity.animal.PolarBear$PolarBearMeleeAttackGoal
+ XXX.entity.animal.PolarBear$PolarBearPanicGoal
- XXX.entity.animal.Pufferfish
+ XXX.entity.animal.Pufferfish$PufferfishPuffGoal
- XXX.entity.animal.Rabbit
+ XXX.entity.animal.Rabbit$EvilRabbitAttackGoal
- XXX.entity.animal.Rabbit$RabbitAvoidEntityGoal
+ XXX.entity.animal.Rabbit$RabbitGroupData
- XXX.entity.animal.Rabbit$RabbitJumpControl
+ XXX.entity.animal.Rabbit$RabbitMoveControl
- XXX.entity.animal.Rabbit$RabbitPanicGoal
+ XXX.entity.animal.Rabbit$RaidGardenGoal
- XXX.entity.animal.Salmon
+ XXX.entity.animal.Sheep
- XXX.entity.animal.Sheep$1
+ XXX.entity.animal.Sheep$2
- XXX.entity.animal.ShoulderRidingEntity
+ XXX.entity.animal.SnowGolem
- XXX.entity.animal.Squid
+ XXX.entity.animal.Squid$1
- XXX.entity.animal.Squid$SquidFleeGoal
+ XXX.entity.animal.Squid$SquidRandomMovementGoal
- XXX.entity.animal.TropicalFish
+ XXX.entity.animal.TropicalFish$1
- XXX.entity.animal.TropicalFish$Pattern
+ XXX.entity.animal.TropicalFish$TropicalFishGroupData
- XXX.entity.animal.Turtle
+ XXX.entity.animal.Turtle$1
- XXX.entity.animal.Turtle$TurtleBreedGoal
+ XXX.entity.animal.Turtle$TurtleGoHomeGoal
- XXX.entity.animal.Turtle$TurtleGoToWaterGoal
+ XXX.entity.animal.Turtle$TurtleLayEggGoal
- XXX.entity.animal.Turtle$TurtleMoveControl
+ XXX.entity.animal.Turtle$TurtlePanicGoal
- XXX.entity.animal.Turtle$TurtlePathNavigation
+ XXX.entity.animal.Turtle$TurtleRandomStrollGoal
- XXX.entity.animal.Turtle$TurtleTemptGoal
+ XXX.entity.animal.Turtle$TurtleTravelGoal
- XXX.entity.animal.WaterAnimal
+ XXX.entity.animal.Wolf
- XXX.entity.animal.Wolf$WolfAvoidEntityGoal
+ XXX.entity.boss.BossMob
- XXX.entity.boss.EnderDragonPart
+ XXX.entity.boss.package-info
+ XXX.entity.decoration.ArmorStand
- XXX.entity.decoration.ArmorStand$1
+ XXX.entity.decoration.HangingEntity
- XXX.entity.decoration.HangingEntity$1
+ XXX.entity.decoration.ItemFrame
- XXX.entity.decoration.ItemFrame$1
+ XXX.entity.decoration.LeashFenceKnotEntity
- XXX.entity.decoration.Motive
- XXX.entity.decoration.package-info
+ XXX.entity.decoration.Painting
+ XXX.entity.fishing.FishingHook
- XXX.entity.fishing.FishingHook$FishHookState
+ XXX.entity.fishing.package-info
- XXX.entity.global.LightningBolt
+ XXX.entity.global.package-info
- XXX.entity.item.FallingBlockEntity
+ XXX.entity.item.ItemEntity
+ XXX.entity.item.package-info
- XXX.entity.item.PrimedTnt
+ XXX.entity.layers.EnderDragonDeathLayer
- XXX.entity.layers.FoxHeldItemLayer
+ XXX.entity.layers.HorseArmorLayer
- XXX.entity.layers.HumanoidArmorLayer
+ XXX.entity.layers.HumanoidArmorLayer$1
- XXX.entity.layers.IronGolemFlowerLayer
+ XXX.entity.layers.ItemInHandLayer
- XXX.entity.layers.LlamaDecorLayer
+ XXX.entity.layers.MushroomCowMushroomLayer
- XXX.entity.layers.PandaHoldsItemLayer
+ XXX.entity.layers.ParrotOnShoulderLayer
- XXX.entity.layers.PhantomEyesLayer
+ XXX.entity.layers.PigSaddleLayer
- XXX.entity.layers.RenderLayer
+ XXX.entity.layers.SheepFurLayer
- XXX.entity.layers.ShulkerHeadLayer
+ XXX.entity.layers.ShulkerHeadLayer$1
- XXX.entity.layers.SlimeOuterLayer
+ XXX.entity.layers.SnowGolemHeadLayer
- XXX.entity.layers.SpiderEyesLayer
+ XXX.entity.layers.SpinAttackEffectLayer
- XXX.entity.layers.SpinnyLayer
+ XXX.entity.layers.StrayClothingLayer
- XXX.entity.layers.StuckInBodyLayer
+ XXX.entity.layers.TropicalFishPatternLayer
- XXX.entity.layers.VillagerProfessionLayer
- XXX.entity.monster.AbstractIllager
+ XXX.entity.monster.AbstractIllager$IllagerArmPose
- XXX.entity.monster.AbstractIllager$RaiderOpenDoorGoal
+ XXX.entity.monster.AbstractSkeleton
- XXX.entity.monster.AbstractSkeleton$1
+ XXX.entity.monster.Blaze
- XXX.entity.monster.Blaze$BlazeAttackGoal
+ XXX.entity.monster.CaveSpider
- XXX.entity.monster.Creeper
+ XXX.entity.monster.CrossbowAttackMob
- XXX.entity.monster.Drowned
+ XXX.entity.monster.Drowned$DrownedAttackGoal
- XXX.entity.monster.Drowned$DrownedGoToBeachGoal
+ XXX.entity.monster.Drowned$DrownedGoToWaterGoal
- XXX.entity.monster.Drowned$DrownedMoveControl
+ XXX.entity.monster.Drowned$DrownedSwimUpGoal
- XXX.entity.monster.Drowned$DrownedTridentAttackGoal
+ XXX.entity.monster.ElderGuardian
- XXX.entity.monster.EnderMan
+ XXX.entity.monster.EnderMan$EndermanFreezeWhenLookedAt
- XXX.entity.monster.EnderMan$EndermanLeaveBlockGoal
+ XXX.entity.monster.EnderMan$EndermanLookForPlayerGoal
- XXX.entity.monster.EnderMan$EndermanTakeBlockGoal
+ XXX.entity.monster.Endermite
- XXX.entity.monster.Enemy
+ XXX.entity.monster.Evoker
- XXX.entity.monster.Evoker$1
+ XXX.entity.monster.Evoker$EvokerAttackSpellGoal
- XXX.entity.monster.Evoker$EvokerCastingSpellGoal
+ XXX.entity.monster.Evoker$EvokerSummonSpellGoal
- XXX.entity.monster.Evoker$EvokerWololoSpellGoal
+ XXX.entity.monster.Ghast
- XXX.entity.monster.Ghast$GhastLookGoal
+ XXX.entity.monster.Ghast$GhastMoveControl
- XXX.entity.monster.Ghast$GhastShootFireballGoal
+ XXX.entity.monster.Ghast$RandomFloatAroundGoal
- XXX.entity.monster.Giant
+ XXX.entity.monster.Guardian
- XXX.entity.monster.Guardian$GuardianAttackGoal
+ XXX.entity.monster.Guardian$GuardianAttackSelector
- XXX.entity.monster.Guardian$GuardianMoveControl
+ XXX.entity.monster.Husk
- XXX.entity.monster.Illusioner
+ XXX.entity.monster.Illusioner$1
- XXX.entity.monster.Illusioner$IllusionerBlindnessSpellGoal
+ XXX.entity.monster.Illusioner$IllusionerMirrorSpellGoal
- XXX.entity.monster.MagmaCube
+ XXX.entity.monster.Monster
- XXX.entity.monster.package-info
- XXX.entity.monster.PatrollingMonster
+ XXX.entity.monster.PatrollingMonster$LongDistancePatrolGoal
- XXX.entity.monster.Phantom
+ XXX.entity.monster.Phantom$1
- XXX.entity.monster.Phantom$AttackPhase
+ XXX.entity.monster.Phantom$PhantomAttackPlayerTargetGoal
- XXX.entity.monster.Phantom$PhantomAttackStrategyGoal
+ XXX.entity.monster.Phantom$PhantomBodyRotationControl
- XXX.entity.monster.Phantom$PhantomCircleAroundAnchorGoal
+ XXX.entity.monster.Phantom$PhantomLookControl
- XXX.entity.monster.Phantom$PhantomMoveControl
+ XXX.entity.monster.Phantom$PhantomMoveTargetGoal
- XXX.entity.monster.Phantom$PhantomSweepAttackGoal
+ XXX.entity.monster.PigZombie
- XXX.entity.monster.PigZombie$PigZombieAngerTargetGoal
+ XXX.entity.monster.PigZombie$PigZombieHurtByOtherGoal
- XXX.entity.monster.Pillager
+ XXX.entity.monster.RangedAttackMob
- XXX.entity.monster.Ravager
+ XXX.entity.monster.Ravager$1
- XXX.entity.monster.Ravager$RavagerMeleeAttackGoal
+ XXX.entity.monster.Ravager$RavagerNavigation
- XXX.entity.monster.Ravager$RavagerNodeEvaluator
+ XXX.entity.monster.SharedMonsterAttributes
- XXX.entity.monster.Shulker
+ XXX.entity.monster.Shulker$1
- XXX.entity.monster.Shulker$ShulkerAttackGoal
+ XXX.entity.monster.Shulker$ShulkerBodyRotationControl
- XXX.entity.monster.Shulker$ShulkerDefenseAttackGoal
+ XXX.entity.monster.Shulker$ShulkerNearestAttackGoal
- XXX.entity.monster.Shulker$ShulkerPeekGoal
+ XXX.entity.monster.Silverfish
- XXX.entity.monster.Silverfish$SilverfishMergeWithStoneGoal
+ XXX.entity.monster.Silverfish$SilverfishWakeUpFriendsGoal
- XXX.entity.monster.Skeleton
+ XXX.entity.monster.Slime
- XXX.entity.monster.Slime$SlimeAttackGoal
+ XXX.entity.monster.Slime$SlimeFloatGoal
- XXX.entity.monster.Slime$SlimeKeepOnJumpingGoal
+ XXX.entity.monster.Slime$SlimeMoveControl
- XXX.entity.monster.Slime$SlimeRandomDirectionGoal
+ XXX.entity.monster.SpellcasterIllager
- XXX.entity.monster.SpellcasterIllager$IllagerSpell
+ XXX.entity.monster.SpellcasterIllager$SpellcasterCastingSpellGoal
- XXX.entity.monster.SpellcasterIllager$SpellcasterUseSpellGoal
+ XXX.entity.monster.Spider
- XXX.entity.monster.Spider$SpiderAttackGoal
+ XXX.entity.monster.Spider$SpiderEffectsGroupData
- XXX.entity.monster.Spider$SpiderTargetGoal
+ XXX.entity.monster.Stray
- XXX.entity.monster.Vex
+ XXX.entity.monster.Vex$VexChargeAttackGoal
- XXX.entity.monster.Vex$VexCopyOwnerTargetGoal
+ XXX.entity.monster.Vex$VexMoveControl
- XXX.entity.monster.Vex$VexRandomMoveGoal
+ XXX.entity.monster.Vindicator
- XXX.entity.monster.Vindicator$VindicatorBreakDoorGoal
+ XXX.entity.monster.Vindicator$VindicatorJohnnyAttackGoal
- XXX.entity.monster.Vindicator$VindicatorMeleeAttackGoal
+ XXX.entity.monster.Witch
- XXX.entity.monster.WitherSkeleton
+ XXX.entity.monster.Zombie
- XXX.entity.monster.Zombie$1
+ XXX.entity.monster.Zombie$ZombieAttackTurtleEggGoal
- XXX.entity.monster.Zombie$ZombieGroupData
+ XXX.entity.monster.ZombieVillager
+ XXX.entity.npc.AbstractVillager
- XXX.entity.npc.CatSpawner
+ XXX.entity.npc.ClientSideMerchant
- XXX.entity.npc.Npc
- XXX.entity.npc.package-info
+ XXX.entity.npc.Villager
- XXX.entity.npc.VillagerData
+ XXX.entity.npc.VillagerDataHolder
- XXX.entity.npc.VillagerProfession
+ XXX.entity.npc.VillagerTrades
- XXX.entity.npc.VillagerTrades$DyedArmorForEmeralds
+ XXX.entity.npc.VillagerTrades$EmeraldForItems
- XXX.entity.npc.VillagerTrades$EmeraldsForVillagerTypeItem
+ XXX.entity.npc.VillagerTrades$EnchantBookForEmeralds
- XXX.entity.npc.VillagerTrades$EnchantedItemForEmeralds
+ XXX.entity.npc.VillagerTrades$ItemListing
- XXX.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
+ XXX.entity.npc.VillagerTrades$ItemsForEmeralds
- XXX.entity.npc.VillagerTrades$SuspisciousStewForEmerald
+ XXX.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
- XXX.entity.npc.VillagerTrades$TreasureMapForEmeralds
+ XXX.entity.npc.VillagerType
- XXX.entity.npc.VillagerType$1
+ XXX.entity.npc.WanderingTrader
- XXX.entity.npc.WanderingTrader$WanderToPositionGoal
+ XXX.entity.npc.WanderingTraderSpawner
- XXX.entity.player.Abilities
+ XXX.entity.player.ChatVisiblity
- XXX.entity.player.Inventory
+ XXX.entity.player.package-info
+ XXX.entity.player.Player
- XXX.entity.player.Player$1
+ XXX.entity.player.Player$BedSleepingProblem
- XXX.entity.player.PlayerModelPart
+ XXX.entity.player.StackedContents
- XXX.entity.player.StackedContents$RecipePicker
- XXX.entity.projectile.AbstractArrow
+ XXX.entity.projectile.AbstractArrow$Pickup
- XXX.entity.projectile.AbstractHurtingProjectile
+ XXX.entity.projectile.Arrow
- XXX.entity.projectile.DragonFireball
+ XXX.entity.projectile.EvokerFangs
- XXX.entity.projectile.EyeOfEnder
+ XXX.entity.projectile.Fireball
- XXX.entity.projectile.FireworkRocketEntity
+ XXX.entity.projectile.ItemSupplier
- XXX.entity.projectile.LargeFireball
+ XXX.entity.projectile.LlamaSpit
- XXX.entity.projectile.package-info
- XXX.entity.projectile.Projectile
+ XXX.entity.projectile.ProjectileUtil
- XXX.entity.projectile.ShulkerBullet
+ XXX.entity.projectile.SmallFireball
- XXX.entity.projectile.Snowball
+ XXX.entity.projectile.SpectralArrow
- XXX.entity.projectile.ThrowableItemProjectile
+ XXX.entity.projectile.ThrowableProjectile
- XXX.entity.projectile.ThrownEgg
+ XXX.entity.projectile.ThrownEnderpearl
- XXX.entity.projectile.ThrownExperienceBottle
+ XXX.entity.projectile.ThrownPotion
- XXX.entity.projectile.ThrownTrident
+ XXX.entity.projectile.WitherSkull
+ XXX.entity.raid.package-info
+ XXX.entity.raid.Raid
- XXX.entity.raid.Raid$1
- XXX.entity.raid.Raid$RaiderType
+ XXX.entity.raid.Raid$RaidStatus
+ XXX.entity.raid.Raider
- XXX.entity.raid.Raider$HoldGroundAttackGoal
+ XXX.entity.raid.Raider$ObtainRaidLeaderBannerGoal
- XXX.entity.raid.Raider$RaiderCelebration
+ XXX.entity.raid.Raider$RaiderMoveThroughVillageGoal
- XXX.entity.raid.Raids
- XXX.entity.schedule.Activity
+ XXX.entity.schedule.Keyframe
- XXX.entity.schedule.package-info
- XXX.entity.schedule.Schedule
+ XXX.entity.schedule.ScheduleBuilder
- XXX.entity.schedule.ScheduleBuilder$ActivityTransition
+ XXX.entity.schedule.Timeline
+ XXX.entity.vehicle.AbstractMinecart
- XXX.entity.vehicle.AbstractMinecart$1
+ XXX.entity.vehicle.AbstractMinecart$Type
- XXX.entity.vehicle.AbstractMinecartContainer
+ XXX.entity.vehicle.Boat
- XXX.entity.vehicle.Boat$1
+ XXX.entity.vehicle.Boat$Status
- XXX.entity.vehicle.Boat$Type
+ XXX.entity.vehicle.Minecart
- XXX.entity.vehicle.MinecartChest
+ XXX.entity.vehicle.MinecartCommandBlock
- XXX.entity.vehicle.MinecartCommandBlock$MinecartCommandBase
+ XXX.entity.vehicle.MinecartFurnace
- XXX.entity.vehicle.MinecartHopper
+ XXX.entity.vehicle.MinecartSpawner
- XXX.entity.vehicle.MinecartSpawner$1
+ XXX.entity.vehicle.MinecartTNT
- XXX.entity.vehicle.package-info
+ XXX.feature.structures.EmptyPoolElement
- XXX.feature.structures.FeaturePoolElement
+ XXX.feature.structures.JigsawJunction
- XXX.feature.structures.JigsawPlacement
+ XXX.feature.structures.JigsawPlacement$1
- XXX.feature.structures.JigsawPlacement$PieceFactory
+ XXX.feature.structures.JigsawPlacement$PieceState
- XXX.feature.structures.JigsawPlacement$Placer
+ XXX.feature.structures.ListPoolElement
- XXX.feature.structures.package-info
- XXX.feature.structures.SinglePoolElement
+ XXX.feature.structures.StructurePoolElement
- XXX.feature.structures.StructurePoolElementType
+ XXX.feature.structures.StructureTemplatePool
- XXX.feature.structures.StructureTemplatePool$Projection
+ XXX.feature.structures.StructureTemplatePools
- XXX.font.glyphs.BakedGlyph$Effect
+ XXX.font.glyphs.EmptyGlyph
- XXX.font.glyphs.MissingGlyph
+ XXX.gametest.framework.BeforeBatch
- XXX.gametest.framework.GameTest
+ XXX.gametest.framework.GameTestAssertException
- XXX.gametest.framework.GameTestAssertPosException
+ XXX.gametest.framework.GameTestBatch
- XXX.gametest.framework.GameTestBatchRunner
+ XXX.gametest.framework.GameTestBatchRunner$1
- XXX.gametest.framework.GameTestGenerator
+ XXX.gametest.framework.GameTestHelper
- XXX.gametest.framework.GameTestInfo
+ XXX.gametest.framework.GameTestListener
- XXX.gametest.framework.GameTestRegistry
+ XXX.gametest.framework.GameTestRunner
- XXX.gametest.framework.GameTestRunner$1
+ XXX.gametest.framework.GameTestServer
- XXX.gametest.framework.GameTestServer$1
+ XXX.gametest.framework.GameTestTicker
- XXX.gametest.framework.GameTestTimeoutException
+ XXX.gametest.framework.LogTestReporter
- XXX.gametest.framework.MultipleTestTracker
+ XXX.gametest.framework.package-info
+ XXX.gametest.framework.StructureUtils
- XXX.gametest.framework.TeamcityTestReporter
+ XXX.gametest.framework.TestClassNameArgument
- XXX.gametest.framework.TestCommand
+ XXX.gametest.framework.TestCommand$TestSummaryDisplayer
- XXX.gametest.framework.TestFunction
+ XXX.gametest.framework.TestFunctionArgument
- XXX.gametest.framework.TestReporter
+ XXX.goal.target.DefendVillageTargetGoal
- XXX.goal.target.HurtByTargetGoal
+ XXX.goal.target.NearestAttackableTargetGoal
- XXX.goal.target.NearestAttackableWitchTargetGoal
+ XXX.goal.target.NearestHealableRaiderTargetGoal
- XXX.goal.target.NonTameRandomTargetGoal
+ XXX.goal.target.OwnerHurtByTargetGoal
- XXX.goal.target.OwnerHurtTargetGoal
- XXX.goal.target.package-info
+ XXX.goal.target.TargetGoal
- XXX.item.alchemy.package-info
+ XXX.item.alchemy.Potion
- XXX.item.alchemy.PotionBrewing
+ XXX.item.alchemy.PotionBrewing$Mix
+ XXX.item.alchemy.Potions
- XXX.item.alchemy.PotionUtils
+ XXX.item.crafting.AbstractCookingRecipe
- XXX.item.crafting.ArmorDyeRecipe
+ XXX.item.crafting.BannerDuplicateRecipe
- XXX.item.crafting.BlastingRecipe
+ XXX.item.crafting.BookCloningRecipe
- XXX.item.crafting.CampfireCookingRecipe
+ XXX.item.crafting.CraftingRecipe
- XXX.item.crafting.CustomRecipe
+ XXX.item.crafting.FireworkRocketRecipe
- XXX.item.crafting.FireworkStarFadeRecipe
+ XXX.item.crafting.FireworkStarRecipe
- XXX.item.crafting.Ingredient
+ XXX.item.crafting.Ingredient$1
- XXX.item.crafting.Ingredient$ItemValue
+ XXX.item.crafting.Ingredient$TagValue
- XXX.item.crafting.Ingredient$Value
+ XXX.item.crafting.MapCloningRecipe
- XXX.item.crafting.MapExtendingRecipe
- XXX.item.crafting.package-info
+ XXX.item.crafting.Recipe
- XXX.item.crafting.RecipeManager
+ XXX.item.crafting.RecipeSerializer
- XXX.item.crafting.RecipeType
+ XXX.item.crafting.RecipeType$1
- XXX.item.crafting.RepairItemRecipe
+ XXX.item.crafting.ShapedRecipe
- XXX.item.crafting.ShapedRecipe$Serializer
+ XXX.item.crafting.ShapelessRecipe
- XXX.item.crafting.ShapelessRecipe$Serializer
+ XXX.item.crafting.ShieldDecorationRecipe
- XXX.item.crafting.ShulkerBoxColoring
+ XXX.item.crafting.SimpleCookingSerializer
- XXX.item.crafting.SimpleCookingSerializer$CookieBaker
+ XXX.item.crafting.SimpleRecipeSerializer
- XXX.item.crafting.SingleItemRecipe
+ XXX.item.crafting.SingleItemRecipe$Serializer
- XXX.item.crafting.SingleItemRecipe$Serializer$SingleItemMaker
+ XXX.item.crafting.SmeltingRecipe
- XXX.item.crafting.SmokingRecipe
+ XXX.item.crafting.StonecutterRecipe
- XXX.item.crafting.SuspiciousStewRecipe
+ XXX.item.crafting.TippedArrowRecipe
+ XXX.item.enchantment.ArrowDamageEnchantment
- XXX.item.enchantment.ArrowFireEnchantment
+ XXX.item.enchantment.ArrowInfiniteEnchantment
- XXX.item.enchantment.ArrowKnockbackEnchantment
+ XXX.item.enchantment.ArrowPiercingEnchantment
- XXX.item.enchantment.BindingCurseEnchantment
+ XXX.item.enchantment.DamageEnchantment
- XXX.item.enchantment.DigDurabilityEnchantment
+ XXX.item.enchantment.DiggingEnchantment
- XXX.item.enchantment.Enchantment
+ XXX.item.enchantment.Enchantment$Rarity
- XXX.item.enchantment.EnchantmentCategory
+ XXX.item.enchantment.EnchantmentCategory$1
- XXX.item.enchantment.EnchantmentCategory$10
+ XXX.item.enchantment.EnchantmentCategory$11
- XXX.item.enchantment.EnchantmentCategory$12
+ XXX.item.enchantment.EnchantmentCategory$13
- XXX.item.enchantment.EnchantmentCategory$14
+ XXX.item.enchantment.EnchantmentCategory$2
- XXX.item.enchantment.EnchantmentCategory$3
+ XXX.item.enchantment.EnchantmentCategory$4
- XXX.item.enchantment.EnchantmentCategory$5
+ XXX.item.enchantment.EnchantmentCategory$6
- XXX.item.enchantment.EnchantmentCategory$7
+ XXX.item.enchantment.EnchantmentCategory$8
- XXX.item.enchantment.EnchantmentCategory$9
+ XXX.item.enchantment.EnchantmentHelper
- XXX.item.enchantment.EnchantmentHelper$EnchantmentVisitor
+ XXX.item.enchantment.EnchantmentInstance
- XXX.item.enchantment.Enchantments
+ XXX.item.enchantment.FireAspectEnchantment
- XXX.item.enchantment.FishingSpeedEnchantment
+ XXX.item.enchantment.FrostWalkerEnchantment
- XXX.item.enchantment.KnockbackEnchantment
+ XXX.item.enchantment.LootBonusEnchantment
- XXX.item.enchantment.MendingEnchantment
+ XXX.item.enchantment.MultiShotEnchantment
- XXX.item.enchantment.OxygenEnchantment
- XXX.item.enchantment.package-info
+ XXX.item.enchantment.ProtectionEnchantment
- XXX.item.enchantment.ProtectionEnchantment$Type
+ XXX.item.enchantment.QuickChargeEnchantment
- XXX.item.enchantment.SweepingEdgeEnchantment
+ XXX.item.enchantment.ThornsEnchantment
- XXX.item.enchantment.TridentChannelingEnchantment
+ XXX.item.enchantment.TridentImpalerEnchantment
- XXX.item.enchantment.TridentLoyaltyEnchantment
+ XXX.item.enchantment.TridentRiptideEnchantment
- XXX.item.enchantment.UntouchingEnchantment
+ XXX.item.enchantment.VanishingCurseEnchantment
- XXX.item.enchantment.WaterWalkerEnchantment
+ XXX.item.enchantment.WaterWorkerEnchantment
- XXX.item.trading.Merchant
+ XXX.item.trading.MerchantOffer
- XXX.item.trading.MerchantOffers
+ XXX.item.trading.package-info
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
- XXX.level.biome.BadlandsBiome
+ XXX.level.biome.BadlandsPlateauBiome
- XXX.level.biome.BambooJungleBiome
+ XXX.level.biome.BambooJungleHillsBiome
- XXX.level.biome.BeachBiome
+ XXX.level.biome.Biome
- XXX.level.biome.Biome$1
+ XXX.level.biome.Biome$BiomeBuilder
- XXX.level.biome.Biome$BiomeCategory
+ XXX.level.biome.Biome$BiomeTempCategory
- XXX.level.biome.Biome$Precipitation
+ XXX.level.biome.Biome$SpawnerData
- XXX.level.biome.BiomeDefaultFeatures
+ XXX.level.biome.BiomeManager
- XXX.level.biome.BiomeManager$NoiseBiomeSource
+ XXX.level.biome.Biomes
+ XXX.level.biome.BiomeSource
- XXX.level.biome.BiomeSourceSettings
+ XXX.level.biome.BiomeSourceType
- XXX.level.biome.BiomeZoomer
- XXX.level.biome.BirchForestBiome
+ XXX.level.biome.BirchForestHillsBiome
- XXX.level.biome.CheckerboardBiomeSourceSettings
+ XXX.level.biome.CheckerboardColumnBiomeSource
- XXX.level.biome.ColdOceanBiome
+ XXX.level.biome.DarkForestBiome
- XXX.level.biome.DarkForestHillsBiome
+ XXX.level.biome.DeepColdOceanBiome
- XXX.level.biome.DeepFrozenOceanBiome
+ XXX.level.biome.DeepLukeWarmOceanBiome
- XXX.level.biome.DeepOceanBiome
+ XXX.level.biome.DeepWarmOceanBiome
- XXX.level.biome.DesertBiome
+ XXX.level.biome.DesertHillsBiome
- XXX.level.biome.DesertLakesBiome
+ XXX.level.biome.EndBarrensBiome
- XXX.level.biome.EndHighlandsBiome
+ XXX.level.biome.EndMidlandsBiome
- XXX.level.biome.ErodedBadlandsBiome
+ XXX.level.biome.FixedBiomeSource
- XXX.level.biome.FixedBiomeSourceSettings
+ XXX.level.biome.ForestBiome
- XXX.level.biome.ForestFlowerBiome
+ XXX.level.biome.FrozenOceanBiome
- XXX.level.biome.FrozenRiverBiome
+ XXX.level.biome.FuzzyOffsetBiomeZoomer
- XXX.level.biome.FuzzyOffsetConstantColumnBiomeZoomer
+ XXX.level.biome.GiantSpruceTaigaBiome
- XXX.level.biome.GiantSpruceTaigaHillsMutatedBiome
+ XXX.level.biome.GiantTreeTaigaBiome
- XXX.level.biome.GiantTreeTaigaHillsBiome
+ XXX.level.biome.GravellyMountainsBiome
- XXX.level.biome.IceSpikesBiome
+ XXX.level.biome.JungleBiome
- XXX.level.biome.JungleEdgeBiome
+ XXX.level.biome.JungleHillsBiome
- XXX.level.biome.LukeWarmOceanBiome
+ XXX.level.biome.ModifiedBadlandsPlateauBiome
- XXX.level.biome.ModifiedGravellyMountainsBiome
+ XXX.level.biome.ModifiedJungleBiome
- XXX.level.biome.ModifiedJungleEdgeBiome
+ XXX.level.biome.ModifiedWoodedBadlandsPlateauBiome
- XXX.level.biome.MountainBiome
+ XXX.level.biome.MountainEdgeBiome
- XXX.level.biome.MushroomFieldsBiome
+ XXX.level.biome.MushroomFieldsShoreBiome
- XXX.level.biome.NearestNeighborBiomeZoomer
+ XXX.level.biome.NetherBiome
- XXX.level.biome.OceanBiome
+ XXX.level.biome.OverworldBiomeSource
- XXX.level.biome.OverworldBiomeSourceSettings
+ XXX.level.biome.package-info
+ XXX.level.biome.PlainsBiome
- XXX.level.biome.RiverBiome
+ XXX.level.biome.SavannaBiome
- XXX.level.biome.SavannaPlateauBiome
+ XXX.level.biome.ShatteredSavannaBiome
- XXX.level.biome.ShatteredSavannaPlateauBiome
+ XXX.level.biome.SmallEndIslandsBiome
- XXX.level.biome.SnowyBeachBiome
+ XXX.level.biome.SnowyMountainsBiome
- XXX.level.biome.SnowyTaigaBiome
+ XXX.level.biome.SnowyTaigaHillsBiome
- XXX.level.biome.SnowyTaigaMountainsBiome
+ XXX.level.biome.SnowyTundraBiome
- XXX.level.biome.StoneShoreBiome
+ XXX.level.biome.SunflowerPlainsBiome
- XXX.level.biome.SwampBiome
+ XXX.level.biome.SwampHillsBiome
- XXX.level.biome.TaigaBiome
+ XXX.level.biome.TaigaHillsBiome
- XXX.level.biome.TaigaMountainsBiome
+ XXX.level.biome.TallBirchForestBiome
- XXX.level.biome.TallBirchHillsBiome
+ XXX.level.biome.TheEndBiome
- XXX.level.biome.TheEndBiomeSource
+ XXX.level.biome.TheEndBiomeSourceSettings
- XXX.level.biome.TheVoidBiome
+ XXX.level.biome.WarmOceanBiome
- XXX.level.biome.WoodedBadlandsBiome
+ XXX.level.biome.WoodedHillsBiome
- XXX.level.biome.WoodedMountainBiome
- XXX.level.block.AbstractBannerBlock
+ XXX.level.block.AbstractFurnaceBlock
- XXX.level.block.AbstractGlassBlock
+ XXX.level.block.AbstractSkullBlock
- XXX.level.block.AirBlock
+ XXX.level.block.AnvilBlock
- XXX.level.block.AttachedStemBlock
+ XXX.level.block.BambooBlock
- XXX.level.block.BambooSaplingBlock
+ XXX.level.block.BannerBlock
- XXX.level.block.BarrelBlock
+ XXX.level.block.BarrierBlock
- XXX.level.block.BaseCoralFanBlock
+ XXX.level.block.BaseCoralPlantBlock
- XXX.level.block.BaseCoralPlantTypeBlock
+ XXX.level.block.BaseCoralWallFanBlock
- XXX.level.block.BaseEntityBlock
+ XXX.level.block.BasePressurePlateBlock
- XXX.level.block.BaseRailBlock
+ XXX.level.block.BeaconBeamBlock
- XXX.level.block.BeaconBlock
+ XXX.level.block.BedBlock
- XXX.level.block.BedBlock$1
+ XXX.level.block.BedrockBlock
- XXX.level.block.BeehiveBlock
+ XXX.level.block.BeetrootBlock
- XXX.level.block.BellBlock
+ XXX.level.block.BellBlock$1
- XXX.level.block.BlastFurnaceBlock
+ XXX.level.block.Block
- XXX.level.block.Block$1
+ XXX.level.block.Block$2
- XXX.level.block.Block$3
+ XXX.level.block.Block$BlockStatePairKey
- XXX.level.block.Block$OffsetType
+ XXX.level.block.Block$Properties
- XXX.level.block.Blocks
+ XXX.level.block.BonemealableBlock
- XXX.level.block.BrewingStandBlock
+ XXX.level.block.BubbleColumnBlock
- XXX.level.block.BucketPickup
+ XXX.level.block.BushBlock
- XXX.level.block.ButtonBlock
+ XXX.level.block.ButtonBlock$1
- XXX.level.block.CactusBlock
+ XXX.level.block.CakeBlock
- XXX.level.block.CampfireBlock
+ XXX.level.block.CarrotBlock
- XXX.level.block.CartographyTableBlock
+ XXX.level.block.CarvedPumpkinBlock
- XXX.level.block.CauldronBlock
+ XXX.level.block.ChestBlock
- XXX.level.block.ChestBlock$1
+ XXX.level.block.ChestBlock$2
- XXX.level.block.ChestBlock$2$1
+ XXX.level.block.ChestBlock$3
- XXX.level.block.ChestBlock$ChestSearchCallback
+ XXX.level.block.ChorusFlowerBlock
- XXX.level.block.ChorusPlantBlock
+ XXX.level.block.CocoaBlock
- XXX.level.block.CocoaBlock$1
+ XXX.level.block.CommandBlock
- XXX.level.block.ComparatorBlock
+ XXX.level.block.ComposterBlock
- XXX.level.block.ComposterBlock$EmptyContainer
+ XXX.level.block.ComposterBlock$InputContainer
- XXX.level.block.ComposterBlock$OutputContainer
+ XXX.level.block.ConcretePowderBlock
- XXX.level.block.ConduitBlock
+ XXX.level.block.CoralBlock
- XXX.level.block.CoralFanBlock
+ XXX.level.block.CoralPlantBlock
- XXX.level.block.CoralWallFanBlock
+ XXX.level.block.CraftingTableBlock
- XXX.level.block.CropBlock
+ XXX.level.block.CrossCollisionBlock
- XXX.level.block.CrossCollisionBlock$1
+ XXX.level.block.DaylightDetectorBlock
- XXX.level.block.DeadBushBlock
+ XXX.level.block.DetectorRailBlock
- XXX.level.block.DetectorRailBlock$1
+ XXX.level.block.DiodeBlock
- XXX.level.block.DirectionalBlock
+ XXX.level.block.DispenserBlock
- XXX.level.block.DoorBlock
+ XXX.level.block.DoorBlock$1
- XXX.level.block.DoublePlantBlock
+ XXX.level.block.DragonEggBlock
- XXX.level.block.DropperBlock
+ XXX.level.block.EnchantmentTableBlock
+ XXX.level.block.EnderChestBlock
- XXX.level.block.EndGatewayBlock
+ XXX.level.block.EndPortalBlock
- XXX.level.block.EndPortalFrameBlock
+ XXX.level.block.EndRodBlock
- XXX.level.block.EndRodBlock$1
- XXX.level.block.EntityBlock
+ XXX.level.block.FaceAttachedHorizontalDirectionalBlock
- XXX.level.block.FaceAttachedHorizontalDirectionalBlock$1
+ XXX.level.block.FallingBlock
- XXX.level.block.FarmBlock
+ XXX.level.block.FenceBlock
- XXX.level.block.FenceGateBlock
+ XXX.level.block.FenceGateBlock$1
- XXX.level.block.FireBlock
+ XXX.level.block.FletchingTableBlock
- XXX.level.block.FlowerBlock
+ XXX.level.block.FlowerPotBlock
- XXX.level.block.FrostedIceBlock
+ XXX.level.block.FurnaceBlock
- XXX.level.block.GlassBlock
+ XXX.level.block.GlazedTerracottaBlock
- XXX.level.block.GrassBlock
+ XXX.level.block.GrassPathBlock
- XXX.level.block.GravelBlock
+ XXX.level.block.GrindstoneBlock
- XXX.level.block.GrindstoneBlock$1
+ XXX.level.block.HalfTransparentBlock
- XXX.level.block.HayBlock
+ XXX.level.block.HopperBlock
- XXX.level.block.HopperBlock$1
+ XXX.level.block.HorizontalDirectionalBlock
- XXX.level.block.HugeMushroomBlock
+ XXX.level.block.IceBlock
- XXX.level.block.InfestedBlock
+ XXX.level.block.IronBarsBlock
- XXX.level.block.JigsawBlock
+ XXX.level.block.JukeboxBlock
- XXX.level.block.KelpBlock
+ XXX.level.block.KelpPlantBlock
- XXX.level.block.LadderBlock
+ XXX.level.block.LadderBlock$1
- XXX.level.block.Lantern
+ XXX.level.block.LeavesBlock
- XXX.level.block.LecternBlock
+ XXX.level.block.LecternBlock$1
- XXX.level.block.LevelEvent
+ XXX.level.block.LeverBlock
- XXX.level.block.LeverBlock$1
+ XXX.level.block.LiquidBlock
- XXX.level.block.LiquidBlockContainer
+ XXX.level.block.LogBlock
- XXX.level.block.LoomBlock
+ XXX.level.block.MagmaBlock
- XXX.level.block.MelonBlock
+ XXX.level.block.Mirror
- XXX.level.block.Mirror$1
+ XXX.level.block.MushroomBlock
- XXX.level.block.MyceliumBlock
+ XXX.level.block.NetherPortalBlock
- XXX.level.block.NetherPortalBlock$1
+ XXX.level.block.NetherPortalBlock$PortalShape
- XXX.level.block.NetherWartBlock
+ XXX.level.block.NoteBlock
- XXX.level.block.ObserverBlock
+ XXX.level.block.OreBlock
- XXX.level.block.package-info
- XXX.level.block.PipeBlock
+ XXX.level.block.PlayerHeadBlock
- XXX.level.block.PlayerWallHeadBlock
+ XXX.level.block.PotatoBlock
- XXX.level.block.PoweredBlock
+ XXX.level.block.PoweredRailBlock
- XXX.level.block.PoweredRailBlock$1
+ XXX.level.block.PressurePlateBlock
- XXX.level.block.PressurePlateBlock$1
+ XXX.level.block.PressurePlateBlock$Sensitivity
- XXX.level.block.PumpkinBlock
+ XXX.level.block.RailBlock
- XXX.level.block.RailBlock$1
+ XXX.level.block.RailState
- XXX.level.block.RailState$1
- XXX.level.block.RedstoneLampBlock
+ XXX.level.block.RedStoneOreBlock
+ XXX.level.block.RedstoneTorchBlock
- XXX.level.block.RedstoneTorchBlock$Toggle
+ XXX.level.block.RedstoneWallTorchBlock
- XXX.level.block.RedStoneWireBlock
+ XXX.level.block.RedStoneWireBlock$1
- XXX.level.block.RenderShape
+ XXX.level.block.RepeaterBlock
- XXX.level.block.RotatedPillarBlock
+ XXX.level.block.RotatedPillarBlock$1
- XXX.level.block.Rotation
+ XXX.level.block.Rotation$1
- XXX.level.block.SandBlock
+ XXX.level.block.SaplingBlock
- XXX.level.block.ScaffoldingBlock
- XXX.level.block.Seagrass
+ XXX.level.block.SeaPickleBlock
+ XXX.level.block.ShearableDoublePlantBlock
- XXX.level.block.ShulkerBoxBlock
+ XXX.level.block.ShulkerBoxBlock$1
- XXX.level.block.SignBlock
+ XXX.level.block.SimpleWaterloggedBlock
- XXX.level.block.SkullBlock
+ XXX.level.block.SkullBlock$Type
- XXX.level.block.SkullBlock$Types
+ XXX.level.block.SlabBlock
- XXX.level.block.SlabBlock$1
+ XXX.level.block.SlimeBlock
- XXX.level.block.SmithingTableBlock
+ XXX.level.block.SmokerBlock
- XXX.level.block.SnowLayerBlock
+ XXX.level.block.SnowLayerBlock$1
- XXX.level.block.SnowyDirtBlock
+ XXX.level.block.SoulsandBlock
- XXX.level.block.SoundType
+ XXX.level.block.SpawnerBlock
- XXX.level.block.SpongeBlock
+ XXX.level.block.SpreadingSnowyDirtBlock
- XXX.level.block.StainedGlassBlock
+ XXX.level.block.StainedGlassPaneBlock
- XXX.level.block.StairBlock
+ XXX.level.block.StairBlock$1
- XXX.level.block.StandingSignBlock
+ XXX.level.block.StemBlock
- XXX.level.block.StemGrownBlock
+ XXX.level.block.StoneButtonBlock
- XXX.level.block.StonecutterBlock
+ XXX.level.block.StructureBlock
- XXX.level.block.StructureBlock$1
+ XXX.level.block.StructureVoidBlock
- XXX.level.block.SugarCaneBlock
+ XXX.level.block.SweetBerryBushBlock
- XXX.level.block.TallFlowerBlock
+ XXX.level.block.TallGrassBlock
- XXX.level.block.TallSeagrass
+ XXX.level.block.TntBlock
- XXX.level.block.TorchBlock
+ XXX.level.block.TrapDoorBlock
- XXX.level.block.TrapDoorBlock$1
+ XXX.level.block.TrappedChestBlock
- XXX.level.block.TripWireBlock
+ XXX.level.block.TripWireBlock$1
- XXX.level.block.TripWireHookBlock
+ XXX.level.block.TripWireHookBlock$1
- XXX.level.block.TurtleEggBlock
+ XXX.level.block.VineBlock
- XXX.level.block.VineBlock$1
+ XXX.level.block.WallBannerBlock
- XXX.level.block.WallBlock
+ XXX.level.block.WallSignBlock
- XXX.level.block.WallSkullBlock
+ XXX.level.block.WallTorchBlock
- XXX.level.block.WaterlilyBlock
+ XXX.level.block.WebBlock
- XXX.level.block.WeightedPressurePlateBlock
+ XXX.level.block.WetSpongeBlock
- XXX.level.block.WitherRoseBlock
+ XXX.level.block.WitherSkullBlock
- XXX.level.block.WitherWallSkullBlock
+ XXX.level.block.WoodButtonBlock
- XXX.level.block.WoolCarpetBlock
- XXX.level.border.BorderChangeListener
+ XXX.level.border.BorderChangeListener$DelegateBorderChangeListener
- XXX.level.border.BorderStatus
- XXX.level.border.package-info
+ XXX.level.border.WorldBorder
- XXX.level.border.WorldBorder$1
+ XXX.level.border.WorldBorder$BorderExtent
- XXX.level.border.WorldBorder$MovingBorderExtent
+ XXX.level.border.WorldBorder$StaticBorderExtent
+ XXX.level.chunk.ChunkAccess
- XXX.level.chunk.ChunkBiomeContainer
+ XXX.level.chunk.ChunkGenerator
- XXX.level.chunk.ChunkGeneratorFactory
+ XXX.level.chunk.ChunkGeneratorType
- XXX.level.chunk.ChunkSource
+ XXX.level.chunk.ChunkStatus
- XXX.level.chunk.ChunkStatus$ChunkType
+ XXX.level.chunk.ChunkStatus$GenerationTask
- XXX.level.chunk.ChunkStatus$LoadingTask
+ XXX.level.chunk.ChunkStatus$SimpleGenerationTask
- XXX.level.chunk.DataLayer
+ XXX.level.chunk.EmptyLevelChunk
- XXX.level.chunk.FeatureAccess
+ XXX.level.chunk.GlobalPalette
- XXX.level.chunk.HashMapPalette
+ XXX.level.chunk.ImposterProtoChunk
- XXX.level.chunk.LevelChunk
+ XXX.level.chunk.LevelChunk$EntityCreationType
- XXX.level.chunk.LevelChunkSection
+ XXX.level.chunk.LightChunkGetter
- XXX.level.chunk.LinearPalette
+ XXX.level.chunk.OldDataLayer
+ XXX.level.chunk.package-info
- XXX.level.chunk.Palette
- XXX.level.chunk.PalettedContainer
+ XXX.level.chunk.PalettedContainer$CountConsumer
+ XXX.level.chunk.PaletteResize
- XXX.level.chunk.ProtoChunk
+ XXX.level.chunk.ProtoTickList
- XXX.level.chunk.UpgradeData
+ XXX.level.chunk.UpgradeData$1
- XXX.level.chunk.UpgradeData$BlockFixer
+ XXX.level.chunk.UpgradeData$BlockFixers
- XXX.level.chunk.UpgradeData$BlockFixers$1
+ XXX.level.chunk.UpgradeData$BlockFixers$2
- XXX.level.chunk.UpgradeData$BlockFixers$3
+ XXX.level.chunk.UpgradeData$BlockFixers$4
- XXX.level.chunk.UpgradeData$BlockFixers$5
+ XXX.level.dimension.Dimension
- XXX.level.dimension.DimensionType
+ XXX.level.dimension.NetherDimension
- XXX.level.dimension.NetherDimension$1
+ XXX.level.dimension.NormalDimension
+ XXX.level.dimension.package-info
- XXX.level.levelgen.ChunkGeneratorSettings
+ XXX.level.levelgen.DebugGeneratorSettings
- XXX.level.levelgen.DebugLevelSource
+ XXX.level.levelgen.FlatLevelSource
- XXX.level.levelgen.FlatLevelSource$FlatLevelBiomeWrapper
+ XXX.level.levelgen.GenerationStep
- XXX.level.levelgen.GenerationStep$Carving
+ XXX.level.levelgen.GenerationStep$Decoration
- XXX.level.levelgen.Heightmap
+ XXX.level.levelgen.Heightmap$Types
- XXX.level.levelgen.Heightmap$Usage
+ XXX.level.levelgen.NetherGeneratorSettings
- XXX.level.levelgen.NetherLevelSource
+ XXX.level.levelgen.NoiseBasedChunkGenerator
- XXX.level.levelgen.OverworldGeneratorSettings
+ XXX.level.levelgen.OverworldLevelSource
- XXX.level.levelgen.package-info
- XXX.level.levelgen.PatrolSpawner
+ XXX.level.levelgen.PhantomSpawner
- XXX.level.levelgen.TheEndGeneratorSettings
+ XXX.level.levelgen.TheEndLevelSource
- XXX.level.levelgen.WorldgenRandom
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
+ XXX.level.material.Fluids
+ XXX.level.material.FluidState
- XXX.level.material.FluidStateImpl
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
+ XXX.level.storage.LevelStorage
- XXX.level.storage.LevelStorageException
+ XXX.level.storage.LevelStorageSource
- XXX.level.storage.LevelStorageSource$1
+ XXX.level.storage.LevelSummary
- XXX.level.storage.McRegionUpgrader
+ XXX.level.storage.package-info
+ XXX.level.storage.PlayerIO
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
+ XXX.levelgen.carver.CanyonWorldCarver
- XXX.levelgen.carver.CarverConfiguration
+ XXX.levelgen.carver.CaveWorldCarver
- XXX.levelgen.carver.ConfiguredWorldCarver
+ XXX.levelgen.carver.HellCaveWorldCarver
- XXX.levelgen.carver.NoneCarverConfiguration
- XXX.levelgen.carver.package-info
+ XXX.levelgen.carver.UnderwaterCanyonWorldCarver
- XXX.levelgen.carver.UnderwaterCaveWorldCarver
+ XXX.levelgen.carver.WorldCarver
+ XXX.levelgen.feature.AbstractTreeFeature
- XXX.levelgen.feature.BambooFeature
+ XXX.levelgen.feature.BigTreeFeature
- XXX.levelgen.feature.BigTreeFeature$FoliageCoords
+ XXX.levelgen.feature.BirchFeature
- XXX.levelgen.feature.BlockBlobConfiguration
+ XXX.levelgen.feature.BlockBlobFeature
- XXX.levelgen.feature.BlockPileFeature
+ XXX.levelgen.feature.BlueIceFeature
- XXX.levelgen.feature.BonusChestFeature
+ XXX.levelgen.feature.BuriedTreasureConfiguration
- XXX.levelgen.feature.BuriedTreasureFeature
+ XXX.levelgen.feature.BuriedTreasureFeature$BuriedTreasureStart
- XXX.levelgen.feature.BushConfiguration
+ XXX.levelgen.feature.BushFeature
- XXX.levelgen.feature.CactusFeature
+ XXX.levelgen.feature.CentralSpikedFeature
- XXX.levelgen.feature.ChorusPlantFeature
+ XXX.levelgen.feature.ConfiguredFeature
- XXX.levelgen.feature.CoralClawFeature
+ XXX.levelgen.feature.CoralFeature
- XXX.levelgen.feature.CoralMushroomFeature
+ XXX.levelgen.feature.CoralTreeFeature
- XXX.levelgen.feature.CountFeatureConfiguration
+ XXX.levelgen.feature.DarkOakFeature
- XXX.levelgen.feature.DeadBushFeature
+ XXX.levelgen.feature.DecoratedFeature
- XXX.levelgen.feature.DecoratedFeatureConfiguration
+ XXX.levelgen.feature.DecoratedFlowerFeature
- XXX.levelgen.feature.DecoratorChanceRange
+ XXX.levelgen.feature.DecoratorConfiguration
- XXX.levelgen.feature.DecoratorCountRange
+ XXX.levelgen.feature.DecoratorNoiseDependant
- XXX.levelgen.feature.DefaultFlowerFeature
+ XXX.levelgen.feature.DesertPyramidFeature
- XXX.levelgen.feature.DesertPyramidFeature$FeatureStart
+ XXX.levelgen.feature.DesertVillagePools
- XXX.levelgen.feature.DesertWellFeature
+ XXX.levelgen.feature.DiskConfiguration
- XXX.levelgen.feature.DiskReplaceFeature
+ XXX.levelgen.feature.DoublePlantConfiguration
- XXX.levelgen.feature.DoublePlantFeature
+ XXX.levelgen.feature.EndCityFeature
- XXX.levelgen.feature.EndCityFeature$EndCityStart
+ XXX.levelgen.feature.EndGatewayConfiguration
- XXX.levelgen.feature.EndGatewayFeature
+ XXX.levelgen.feature.EndIslandFeature
- XXX.levelgen.feature.EndPodiumFeature
+ XXX.levelgen.feature.Feature
- XXX.levelgen.feature.FeatureConfiguration
+ XXX.levelgen.feature.FeatureRadius
- XXX.levelgen.feature.FillLayerFeature
+ XXX.levelgen.feature.FlowerFeature
- XXX.levelgen.feature.ForestFlowerFeature
+ XXX.levelgen.feature.FossilFeature
- XXX.levelgen.feature.GeneralForestFlowerFeature
+ XXX.levelgen.feature.GlowstoneFeature
- XXX.levelgen.feature.GrassConfiguration
+ XXX.levelgen.feature.GrassFeature
- XXX.levelgen.feature.GroundBushFeature
+ XXX.levelgen.feature.HayBlockPileFeature
- XXX.levelgen.feature.HellFireFeature
+ XXX.levelgen.feature.HellSpringConfiguration
- XXX.levelgen.feature.HugeBrownMushroomFeature
+ XXX.levelgen.feature.HugeMushroomFeatureConfig
- XXX.levelgen.feature.HugeRedMushroomFeature
- XXX.levelgen.feature.IcebergConfiguration
+ XXX.levelgen.feature.IcebergFeature
+ XXX.levelgen.feature.IceBlockPileFeature
- XXX.levelgen.feature.IcePatchFeature
+ XXX.levelgen.feature.IceSpikeFeature
- XXX.levelgen.feature.IglooFeature
+ XXX.levelgen.feature.IglooFeature$FeatureStart
- XXX.levelgen.feature.JungleGrassFeature
+ XXX.levelgen.feature.JunglePyramidFeature
- XXX.levelgen.feature.JunglePyramidFeature$FeatureStart
+ XXX.levelgen.feature.JungleTreeFeature
- XXX.levelgen.feature.KelpFeature
+ XXX.levelgen.feature.LakeConfiguration
- XXX.levelgen.feature.LakeFeature
+ XXX.levelgen.feature.LayerConfiguration
- XXX.levelgen.feature.MegaJungleTreeFeature
+ XXX.levelgen.feature.MegaPineTreeFeature
- XXX.levelgen.feature.MegaTreeFeature
+ XXX.levelgen.feature.MelonBlockPileFeature
- XXX.levelgen.feature.MelonFeature
+ XXX.levelgen.feature.MineshaftConfiguration
- XXX.levelgen.feature.MineshaftFeature
+ XXX.levelgen.feature.MineshaftFeature$MineShaftStart
- XXX.levelgen.feature.MineshaftFeature$Type
+ XXX.levelgen.feature.MonsterRoomFeature
- XXX.levelgen.feature.NetherFortressFeature
+ XXX.levelgen.feature.NetherFortressFeature$NetherBridgeStart
- XXX.levelgen.feature.NetherSpringFeature
+ XXX.levelgen.feature.NoneDecoratorConfiguration
- XXX.levelgen.feature.NoneFeatureConfiguration
+ XXX.levelgen.feature.OceanMonumentFeature
- XXX.levelgen.feature.OceanMonumentFeature$OceanMonumentStart
+ XXX.levelgen.feature.OceanRuinConfiguration
- XXX.levelgen.feature.OreConfiguration
+ XXX.levelgen.feature.OreConfiguration$Predicates
- XXX.levelgen.feature.OreFeature
- XXX.levelgen.feature.package-info
+ XXX.levelgen.feature.PillagerOutpostConfiguration
- XXX.levelgen.feature.PillagerOutpostFeature
+ XXX.levelgen.feature.PillagerOutpostFeature$FeatureStart
- XXX.levelgen.feature.PineFeature
+ XXX.levelgen.feature.PlainFlowerFeature
- XXX.levelgen.feature.PlainVillagePools
+ XXX.levelgen.feature.ProbabilityFeatureConfiguration
- XXX.levelgen.feature.PumpkinBlockPileFeature
+ XXX.levelgen.feature.RandomBooleanFeatureConfig
- XXX.levelgen.feature.RandomBooleanSelectorFeature
+ XXX.levelgen.feature.RandomFeatureConfig
- XXX.levelgen.feature.RandomRandomFeature
+ XXX.levelgen.feature.RandomRandomFeatureConfig
- XXX.levelgen.feature.RandomScatteredFeature
+ XXX.levelgen.feature.RandomSelectorFeature
- XXX.levelgen.feature.ReedsFeature
+ XXX.levelgen.feature.ReplaceBlockConfiguration
- XXX.levelgen.feature.ReplaceBlockFeature
+ XXX.levelgen.feature.SavannaTreeFeature
- XXX.levelgen.feature.SavannaVillagePools
- XXX.levelgen.feature.SeagrassFeature
+ XXX.levelgen.feature.SeagrassFeatureConfiguration
+ XXX.levelgen.feature.SeaPickleFeature
- XXX.levelgen.feature.ShipwreckConfiguration
+ XXX.levelgen.feature.ShipwreckFeature
- XXX.levelgen.feature.ShipwreckFeature$FeatureStart
+ XXX.levelgen.feature.SimpleBlockConfiguration
- XXX.levelgen.feature.SimpleBlockFeature
+ XXX.levelgen.feature.SimpleRandomFeatureConfig
- XXX.levelgen.feature.SimpleRandomSelectorFeature
+ XXX.levelgen.feature.SimulatedFeature
- XXX.levelgen.feature.SnowAndFreezeFeature
+ XXX.levelgen.feature.SnowBlockPileFeature
- XXX.levelgen.feature.SnowyVillagePools
+ XXX.levelgen.feature.SpikeConfiguration
- XXX.levelgen.feature.SpikeFeature
+ XXX.levelgen.feature.SpikeFeature$1
- XXX.levelgen.feature.SpikeFeature$EndSpike
+ XXX.levelgen.feature.SpikeFeature$SpikeCacheLoader
- XXX.levelgen.feature.SpringConfiguration
+ XXX.levelgen.feature.SpringFeature
- XXX.levelgen.feature.SpruceFeature
+ XXX.levelgen.feature.StrongholdFeature
- XXX.levelgen.feature.StrongholdFeature$StrongholdStart
+ XXX.levelgen.feature.StructureFeature
- XXX.levelgen.feature.StructureFeature$StructureStartFactory
+ XXX.levelgen.feature.StructurePieceType
- XXX.levelgen.feature.SwampFlowerFeature
- XXX.levelgen.feature.SwamplandHutFeature
+ XXX.levelgen.feature.SwamplandHutFeature$FeatureStart
+ XXX.levelgen.feature.SwampTreeFeature
- XXX.levelgen.feature.TaigaGrassFeature
+ XXX.levelgen.feature.TaigaVillagePools
- XXX.levelgen.feature.TreeFeature
+ XXX.levelgen.feature.VillageConfiguration
- XXX.levelgen.feature.VillageFeature
+ XXX.levelgen.feature.VillageFeature$FeatureStart
- XXX.levelgen.feature.VillagePieces
+ XXX.levelgen.feature.VillagePieces$VillagePiece
- XXX.levelgen.feature.VinesFeature
+ XXX.levelgen.feature.VoidStartPlatformFeature
- XXX.levelgen.feature.WaterlilyFeature
+ XXX.levelgen.feature.WeightedConfiguredFeature
- XXX.levelgen.feature.WoodlandMansionFeature
+ XXX.levelgen.feature.WoodlandMansionFeature$WoodlandMansionStart
+ XXX.levelgen.flat.FlatLayerInfo
- XXX.levelgen.flat.FlatLevelGeneratorSettings
+ XXX.levelgen.flat.package-info
+ XXX.levelgen.placement.CarvingMaskDecorator
- XXX.levelgen.placement.ChanceHeightmapDecorator
+ XXX.levelgen.placement.ChanceHeightmapDoubleDecorator
- XXX.levelgen.placement.ChancePassthroughDecorator
+ XXX.levelgen.placement.ChanceTopSolidHeightmapDecorator
- XXX.levelgen.placement.ChorusPlantPlacementDecorator
+ XXX.levelgen.placement.ConfiguredDecorator
- XXX.levelgen.placement.CountBiasedRangeDecorator
+ XXX.levelgen.placement.CountChanceHeightmapDecorator
- XXX.levelgen.placement.CountChanceHeightmapDoubleDecorator
+ XXX.levelgen.placement.CountDepthAverageDecorator
- XXX.levelgen.placement.CountHeighmapDoubleDecorator
+ XXX.levelgen.placement.CountHeight64Decorator
- XXX.levelgen.placement.CountHeightmap32Decorator
+ XXX.levelgen.placement.CountHeightmapDecorator
- XXX.levelgen.placement.CountTopSolidDecorator
+ XXX.levelgen.placement.CountVeryBiasedRangeDecorator
- XXX.levelgen.placement.CountWithExtraChanceHeightmapDecorator
+ XXX.levelgen.placement.DarkOakTreePlacementDecorator
- XXX.levelgen.placement.DecoratorCarvingMaskConfig
+ XXX.levelgen.placement.DecoratorChance
- XXX.levelgen.placement.DecoratorFrequency
+ XXX.levelgen.placement.DecoratorFrequencyChance
- XXX.levelgen.placement.DecoratorFrequencyWithExtraChance
+ XXX.levelgen.placement.DecoratorNoiseCountFactor
- XXX.levelgen.placement.DecoratorRange
+ XXX.levelgen.placement.DepthAverageConfigation
- XXX.levelgen.placement.EmeraldPlacementDecorator
+ XXX.levelgen.placement.EndGatewayPlacementDecorator
- XXX.levelgen.placement.EndIslandPlacementDecorator
+ XXX.levelgen.placement.FeatureDecorator
- XXX.levelgen.placement.ForestRockPlacementDecorator
+ XXX.levelgen.placement.IcebergPlacementDecorator
- XXX.levelgen.placement.LakeChanceDecoratorConfig
+ XXX.levelgen.placement.LakeLavaPlacementDecorator
- XXX.levelgen.placement.LakeWaterPlacementDecorator
+ XXX.levelgen.placement.MonsterRoomPlacementConfiguration
- XXX.levelgen.placement.MonsterRoomPlacementDecorator
+ XXX.levelgen.placement.NoiseHeightmap32Decorator
- XXX.levelgen.placement.NoiseHeightmapDoubleDecorator
+ XXX.levelgen.placement.NopePlacementDecorator
+ XXX.levelgen.placement.package-info
- XXX.levelgen.placement.SimpleFeatureDecorator
+ XXX.levelgen.placement.TopSolidHeightMapDecorator
- XXX.levelgen.placement.TopSolidHeightMapNoiseBasedDecorator
+ XXX.levelgen.placement.TopSolidHeightMapRangeDecorator
- XXX.levelgen.structure.BeardedStructureStart
+ XXX.levelgen.structure.BoundingBox
- XXX.levelgen.structure.BoundingBox$1
+ XXX.levelgen.structure.BuriedTreasurePieces
- XXX.levelgen.structure.BuriedTreasurePieces$BuriedTreasurePiece
+ XXX.levelgen.structure.DesertPyramidPiece
- XXX.levelgen.structure.EndCityPieces
+ XXX.levelgen.structure.EndCityPieces$1
- XXX.levelgen.structure.EndCityPieces$2
+ XXX.levelgen.structure.EndCityPieces$3
- XXX.levelgen.structure.EndCityPieces$4
+ XXX.levelgen.structure.EndCityPieces$EndCityPiece
- XXX.levelgen.structure.EndCityPieces$SectionGenerator
+ XXX.levelgen.structure.IglooPieces
- XXX.levelgen.structure.IglooPieces$IglooPiece
+ XXX.levelgen.structure.JunglePyramidPiece
- XXX.levelgen.structure.JunglePyramidPiece$1
+ XXX.levelgen.structure.JunglePyramidPiece$MossStoneSelector
- XXX.levelgen.structure.LegacyStructureDataHandler
+ XXX.levelgen.structure.MineShaftPieces
- XXX.levelgen.structure.MineShaftPieces$1
+ XXX.levelgen.structure.MineShaftPieces$MineShaftCorridor
- XXX.levelgen.structure.MineShaftPieces$MineShaftCrossing
+ XXX.levelgen.structure.MineShaftPieces$MineShaftPiece
- XXX.levelgen.structure.MineShaftPieces$MineShaftRoom
+ XXX.levelgen.structure.MineShaftPieces$MineShaftStairs
- XXX.levelgen.structure.NetherBridgePieces
+ XXX.levelgen.structure.NetherBridgePieces$1
- XXX.levelgen.structure.NetherBridgePieces$BridgeCrossing
+ XXX.levelgen.structure.NetherBridgePieces$BridgeEndFiller
- XXX.levelgen.structure.NetherBridgePieces$BridgeStraight
+ XXX.levelgen.structure.NetherBridgePieces$CastleCorridorStairsPiece
- XXX.levelgen.structure.NetherBridgePieces$CastleCorridorTBalconyPiece
+ XXX.levelgen.structure.NetherBridgePieces$CastleEntrance
- XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorCrossingPiece
+ XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorLeftTurnPiece
- XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorPiece
+ XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorRightTurnPiece
- XXX.levelgen.structure.NetherBridgePieces$CastleStalkRoom
+ XXX.levelgen.structure.NetherBridgePieces$MonsterThrone
- XXX.levelgen.structure.NetherBridgePieces$NetherBridgePiece
+ XXX.levelgen.structure.NetherBridgePieces$PieceWeight
- XXX.levelgen.structure.NetherBridgePieces$RoomCrossing
+ XXX.levelgen.structure.NetherBridgePieces$StairsRoom
- XXX.levelgen.structure.NetherBridgePieces$StartPiece
+ XXX.levelgen.structure.OceanMonumentPieces
- XXX.levelgen.structure.OceanMonumentPieces$1
+ XXX.levelgen.structure.OceanMonumentPieces$FitDoubleXRoom
- XXX.levelgen.structure.OceanMonumentPieces$FitDoubleXYRoom
+ XXX.levelgen.structure.OceanMonumentPieces$FitDoubleYRoom
- XXX.levelgen.structure.OceanMonumentPieces$FitDoubleYZRoom
+ XXX.levelgen.structure.OceanMonumentPieces$FitDoubleZRoom
- XXX.levelgen.structure.OceanMonumentPieces$FitSimpleRoom
+ XXX.levelgen.structure.OceanMonumentPieces$FitSimpleTopRoom
- XXX.levelgen.structure.OceanMonumentPieces$MonumentBuilding
+ XXX.levelgen.structure.OceanMonumentPieces$MonumentRoomFitter
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentCoreRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXYRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYZRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleZRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentEntryRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentPenthouse
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentPiece
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleTopRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentWingRoom
- XXX.levelgen.structure.OceanMonumentPieces$RoomDefinition
+ XXX.levelgen.structure.OceanRuinFeature
- XXX.levelgen.structure.OceanRuinFeature$OceanRuinStart
+ XXX.levelgen.structure.OceanRuinFeature$Type
- XXX.levelgen.structure.OceanRuinPieces
+ XXX.levelgen.structure.OceanRuinPieces$OceanRuinPiece
- XXX.levelgen.structure.package-info
- XXX.levelgen.structure.PillagerOutpostPieces
+ XXX.levelgen.structure.PillagerOutpostPieces$PillagerOutpostPiece
- XXX.levelgen.structure.PoolElementStructurePiece
+ XXX.levelgen.structure.ScatteredFeaturePiece
- XXX.levelgen.structure.ShipwreckPieces
+ XXX.levelgen.structure.ShipwreckPieces$ShipwreckPiece
- XXX.levelgen.structure.StrongholdPieces
+ XXX.levelgen.structure.StrongholdPieces$1
- XXX.levelgen.structure.StrongholdPieces$2
+ XXX.levelgen.structure.StrongholdPieces$3
- XXX.levelgen.structure.StrongholdPieces$ChestCorridor
+ XXX.levelgen.structure.StrongholdPieces$FillerCorridor
- XXX.levelgen.structure.StrongholdPieces$FiveCrossing
+ XXX.levelgen.structure.StrongholdPieces$LeftTurn
- XXX.levelgen.structure.StrongholdPieces$Library
+ XXX.levelgen.structure.StrongholdPieces$PieceWeight
- XXX.levelgen.structure.StrongholdPieces$PortalRoom
+ XXX.levelgen.structure.StrongholdPieces$PrisonHall
- XXX.levelgen.structure.StrongholdPieces$RightTurn
+ XXX.levelgen.structure.StrongholdPieces$RoomCrossing
- XXX.levelgen.structure.StrongholdPieces$SmoothStoneSelector
+ XXX.levelgen.structure.StrongholdPieces$StairsDown
- XXX.levelgen.structure.StrongholdPieces$StartPiece
+ XXX.levelgen.structure.StrongholdPieces$Straight
- XXX.levelgen.structure.StrongholdPieces$StraightStairsDown
+ XXX.levelgen.structure.StrongholdPieces$StrongholdPiece
- XXX.levelgen.structure.StrongholdPieces$StrongholdPiece$SmallDoorType
+ XXX.levelgen.structure.StrongholdPieces$Turn
+ XXX.levelgen.structure.StructureFeatureIndexSavedData
- XXX.levelgen.structure.StructureFeatureIO
- XXX.levelgen.structure.StructurePiece
+ XXX.levelgen.structure.StructurePiece$1
- XXX.levelgen.structure.StructurePiece$BlockSelector
+ XXX.levelgen.structure.StructureStart
- XXX.levelgen.structure.StructureStart$1
+ XXX.levelgen.structure.SwamplandHutPiece
- XXX.levelgen.structure.TemplateStructurePiece
+ XXX.levelgen.structure.WoodlandMansionPieces
- XXX.levelgen.structure.WoodlandMansionPieces$1
+ XXX.levelgen.structure.WoodlandMansionPieces$FirstFloorRoomCollection
- XXX.levelgen.structure.WoodlandMansionPieces$FloorRoomCollection
+ XXX.levelgen.structure.WoodlandMansionPieces$MansionGrid
- XXX.levelgen.structure.WoodlandMansionPieces$MansionPiecePlacer
+ XXX.levelgen.structure.WoodlandMansionPieces$PlacementData
- XXX.levelgen.structure.WoodlandMansionPieces$SecondFloorRoomCollection
+ XXX.levelgen.structure.WoodlandMansionPieces$SimpleGrid
- XXX.levelgen.structure.WoodlandMansionPieces$ThirdFloorRoomCollection
+ XXX.levelgen.structure.WoodlandMansionPieces$WoodlandMansionPiece
- XXX.levelgen.surfacebuilders.BadlandsSurfaceBuilder
+ XXX.levelgen.surfacebuilders.ConfiguredSurfaceBuilder
- XXX.levelgen.surfacebuilders.DefaultSurfaceBuilder
+ XXX.levelgen.surfacebuilders.ErodedBadlandsSurfaceBuilder
- XXX.levelgen.surfacebuilders.FrozenOceanSurfaceBuilder
+ XXX.levelgen.surfacebuilders.GiantTreeTaigaSurfaceBuilder
- XXX.levelgen.surfacebuilders.GravellyMountainSurfaceBuilder
+ XXX.levelgen.surfacebuilders.MountainSurfaceBuilder
- XXX.levelgen.surfacebuilders.NetherSurfaceBuilder
+ XXX.levelgen.surfacebuilders.NopeSurfaceBuilder
- XXX.levelgen.surfacebuilders.package-info
- XXX.levelgen.surfacebuilders.ShatteredSavanaSurfaceBuilder
+ XXX.levelgen.surfacebuilders.SurfaceBuilder
- XXX.levelgen.surfacebuilders.SurfaceBuilderBaseConfiguration
+ XXX.levelgen.surfacebuilders.SurfaceBuilderConfiguration
- XXX.levelgen.surfacebuilders.SwampSurfaceBuilder
+ XXX.levelgen.surfacebuilders.WoodedBadlandsSurfaceBuilder
+ XXX.levelgen.synth.ImprovedNoise
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
- XXX.loot.entries.CompositeEntryBase$Serializer
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
+ XXX.loot.entries.LootPoolEntries$Serializer
- XXX.loot.entries.LootPoolEntry
+ XXX.loot.entries.LootPoolEntryContainer
- XXX.loot.entries.LootPoolEntryContainer$Builder
+ XXX.loot.entries.LootPoolEntryContainer$Serializer
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
- XXX.loot.functions.LootingEnchantFunction
+ XXX.loot.functions.LootingEnchantFunction$1
- XXX.loot.functions.LootingEnchantFunction$Builder
+ XXX.loot.functions.LootingEnchantFunction$Serializer
+ XXX.loot.functions.LootItemConditionalFunction
- XXX.loot.functions.LootItemConditionalFunction$Builder
+ XXX.loot.functions.LootItemConditionalFunction$DummyBuilder
- XXX.loot.functions.LootItemConditionalFunction$Serializer
+ XXX.loot.functions.LootItemFunction
- XXX.loot.functions.LootItemFunction$Builder
+ XXX.loot.functions.LootItemFunction$Serializer
- XXX.loot.functions.LootItemFunctions
+ XXX.loot.functions.LootItemFunctions$Serializer
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
+ XXX.loot.predicates.LocationCheck$Serializer
- XXX.loot.predicates.LootItemBlockStatePropertyCondition
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition$1
- XXX.loot.predicates.LootItemBlockStatePropertyCondition$Builder
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition$Serializer
- XXX.loot.predicates.LootItemCondition
+ XXX.loot.predicates.LootItemCondition$Builder
- XXX.loot.predicates.LootItemCondition$Serializer
+ XXX.loot.predicates.LootItemConditions
- XXX.loot.predicates.LootItemConditions$Serializer
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
+ XXX.minecraft.client.package-info
- XXX.minecraft.core.BlockMath
+ XXX.minecraft.core.BlockPos
- XXX.minecraft.core.BlockPos$1
+ XXX.minecraft.core.BlockPos$2
- XXX.minecraft.core.BlockPos$3
+ XXX.minecraft.core.BlockPos$MutableBlockPos
- XXX.minecraft.core.BlockPos$PooledMutableBlockPos
+ XXX.minecraft.core.BlockSource
- XXX.minecraft.core.BlockSourceImpl
+ XXX.minecraft.core.Cursor3D
- XXX.minecraft.core.DefaultedRegistry
+ XXX.minecraft.core.Direction
- XXX.minecraft.core.Direction$1
+ XXX.minecraft.core.Direction$Axis
- XXX.minecraft.core.Direction$Axis$1
+ XXX.minecraft.core.Direction$Axis$2
- XXX.minecraft.core.Direction$Axis$3
+ XXX.minecraft.core.Direction$AxisDirection
- XXX.minecraft.core.Direction$Plane
+ XXX.minecraft.core.Direction8
- XXX.minecraft.core.GlobalPos
+ XXX.minecraft.core.IdMap
- XXX.minecraft.core.IdMapper
+ XXX.minecraft.core.LocatableSource
- XXX.minecraft.core.Location
+ XXX.minecraft.core.MapFiller
- XXX.minecraft.core.MappedRegistry
+ XXX.minecraft.core.NonNullList
+ XXX.minecraft.core.package-info
- XXX.minecraft.core.Position
+ XXX.minecraft.core.PositionImpl
- XXX.minecraft.core.Registry
+ XXX.minecraft.core.Rotations
- XXX.minecraft.core.SectionPos
+ XXX.minecraft.core.SectionPos$1
- XXX.minecraft.core.SerializableLong
+ XXX.minecraft.core.Source
- XXX.minecraft.core.Vec3i
+ XXX.minecraft.core.Vec3i$1
- XXX.minecraft.core.WritableRegistry
+ XXX.minecraft.data.DataGenerator
- XXX.minecraft.data.DataProvider
+ XXX.minecraft.data.HashCache
- XXX.minecraft.data.Main
+ XXX.minecraft.data.package-info
- XXX.minecraft.locale.Language
+ XXX.minecraft.locale.package-info
- XXX.minecraft.nbt.ByteArrayTag
- XXX.minecraft.nbt.ByteTag$Cache
- XXX.minecraft.nbt.DoubleTag
- XXX.minecraft.nbt.FloatTag
- XXX.minecraft.nbt.IntTag
- XXX.minecraft.nbt.IntTag$Cache
+ XXX.minecraft.nbt.ListTag
- XXX.minecraft.nbt.ListTag$1
- XXX.minecraft.nbt.LongArrayTag$1
+ XXX.minecraft.nbt.LongTag
- XXX.minecraft.nbt.LongTag$1
- XXX.minecraft.nbt.NbtAccounter
+ XXX.minecraft.nbt.NbtAccounter$1
- XXX.minecraft.nbt.NbtIo
+ XXX.minecraft.nbt.NbtOps
- XXX.minecraft.nbt.NbtUtils
+ XXX.minecraft.nbt.NumericTag
- XXX.minecraft.nbt.package-info
- XXX.minecraft.nbt.ShortTag
- XXX.minecraft.nbt.ShortTag$Cache
+ XXX.minecraft.nbt.StringTag
- XXX.minecraft.nbt.StringTag$1
- XXX.minecraft.nbt.TagType$1
+ XXX.minecraft.network.CipherBase
- XXX.minecraft.network.CipherDecoder
+ XXX.minecraft.network.CipherEncoder
- XXX.minecraft.network.CompressionDecoder
+ XXX.minecraft.network.CompressionEncoder
- XXX.minecraft.network.Connection
+ XXX.minecraft.network.Connection$1
- XXX.minecraft.network.Connection$2
+ XXX.minecraft.network.Connection$PacketHolder
- XXX.minecraft.network.ConnectionProtocol
+ XXX.minecraft.network.ConnectionProtocol$1
- XXX.minecraft.network.ConnectionProtocol$PacketSet
+ XXX.minecraft.network.ConnectionProtocol$ProtocolBuilder
- XXX.minecraft.network.FriendlyByteBuf
+ XXX.minecraft.network.PacketDecoder
- XXX.minecraft.network.PacketEncoder
+ XXX.minecraft.network.PacketListener
- XXX.minecraft.network.SkipPacketException
+ XXX.minecraft.network.Varint21FrameDecoder
- XXX.minecraft.network.Varint21LengthFieldPrepender
- XXX.minecraft.world.package-info
- XXX.model.dragon.DragonHeadModel
+ XXX.model.dragon.DragonModel
+ XXX.model.dragon.package-info
- XXX.model.geom.ModelPart
+ XXX.model.geom.ModelPart$Cube
- XXX.model.geom.ModelPart$Polygon
+ XXX.model.geom.ModelPart$Vertex
- XXX.model.geom.package-info
- XXX.mojang.math.Matrix3f
+ XXX.mojang.math.Matrix4f
- XXX.mojang.math.Quaternion
+ XXX.network.chat.BaseComponent
- XXX.network.chat.ChatType
+ XXX.network.chat.ClickEvent
- XXX.network.chat.ClickEvent$Action
+ XXX.network.chat.Component
- XXX.network.chat.Component$1
+ XXX.network.chat.Component$Serializer
- XXX.network.chat.ComponentUtils
+ XXX.network.chat.ContextAwareComponent
- XXX.network.chat.HoverEvent
+ XXX.network.chat.HoverEvent$Action
- XXX.network.chat.KeybindComponent
+ XXX.network.chat.NbtComponent
- XXX.network.chat.NbtComponent$BlockNbtComponent
+ XXX.network.chat.NbtComponent$EntityNbtComponent
- XXX.network.chat.NbtComponent$StorageNbtComponent
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
- XXX.placement.nether.ChanceRangeDecorator
+ XXX.placement.nether.CountRangeDecorator
- XXX.placement.nether.HellFireDecorator
+ XXX.placement.nether.LightGemChanceDecorator
- XXX.placement.nether.MagmaDecorator
- XXX.placement.nether.package-info
+ XXX.placement.nether.RandomCountRangeDecorator
- XXX.player.inventory.Hotbar
+ XXX.player.inventory.package-info
+ XXX.renderer.banner.BannerTextures
- XXX.renderer.banner.BannerTextures$1
+ XXX.renderer.banner.BannerTextures$TextureCache
- XXX.renderer.banner.BannerTextures$TimestampedBannerTexture
+ XXX.renderer.banner.package-info
+ XXX.renderer.blockentity.BeaconRenderer
- XXX.renderer.blockentity.BedRenderer
+ XXX.renderer.blockentity.BellRenderer
- XXX.renderer.blockentity.BlockEntityRenderDispatcher
+ XXX.renderer.blockentity.BlockEntityRenderer
- XXX.renderer.blockentity.CampfireRenderer
+ XXX.renderer.blockentity.ChestRenderer
- XXX.renderer.blockentity.ConduitRenderer
+ XXX.renderer.blockentity.EnchantTableRenderer
- XXX.renderer.blockentity.LecternRenderer
+ XXX.renderer.blockentity.PistonHeadRenderer
- XXX.renderer.blockentity.ShulkerBoxRenderer
+ XXX.renderer.blockentity.ShulkerBoxRenderer$1
+ XXX.renderer.culling.Culler
- XXX.renderer.culling.Frustum
+ XXX.renderer.culling.FrustumData
+ XXX.renderer.entity.ArmedModel
- XXX.renderer.entity.ArmorStandRenderer
+ XXX.renderer.entity.ArrowRenderer
- XXX.renderer.entity.BatRenderer
+ XXX.renderer.entity.BeeRenderer
- XXX.renderer.entity.BlazeRenderer
+ XXX.renderer.entity.BoatRenderer
- XXX.renderer.entity.CatRenderer
+ XXX.renderer.entity.CaveSpiderRenderer
- XXX.renderer.entity.ChestedHorseRenderer
+ XXX.renderer.entity.ChickenRenderer
- XXX.renderer.entity.CodRenderer
+ XXX.renderer.entity.CowRenderer
- XXX.renderer.entity.CreeperRenderer
+ XXX.renderer.entity.DefaultRenderer
+ XXX.renderer.entity.DolphinRenderer
- XXX.renderer.entity.DragonFireballRenderer
+ XXX.renderer.entity.DrownedRenderer
- XXX.renderer.entity.ElderGuardianRenderer
+ XXX.renderer.entity.EndCrystalRenderer
- XXX.renderer.entity.EnderDragonRenderer
+ XXX.renderer.entity.HorseRenderer
- XXX.renderer.entity.HumanoidMobRenderer
+ XXX.renderer.entity.HuskRenderer
- XXX.renderer.entity.IllagerRenderer
+ XXX.renderer.entity.IllusionerRenderer
- XXX.renderer.entity.IllusionerRenderer$1
+ XXX.renderer.entity.IronGolemRenderer
- XXX.renderer.entity.ItemEntityRenderer
+ XXX.renderer.entity.ItemFrameRenderer
- XXX.renderer.entity.ItemRenderer
+ XXX.renderer.entity.LavaSlimeRenderer
- XXX.renderer.entity.MinecartRenderer
+ XXX.renderer.entity.MobRenderer
- XXX.renderer.entity.MushroomCowRenderer
+ XXX.renderer.entity.OcelotRenderer
- XXX.renderer.entity.PaintingRenderer
+ XXX.renderer.entity.PandaRenderer
- XXX.renderer.entity.ParrotRenderer
+ XXX.renderer.entity.PhantomRenderer
- XXX.renderer.entity.PigRenderer
+ XXX.renderer.entity.PigZombieRenderer
- XXX.renderer.entity.PillagerRenderer
+ XXX.renderer.entity.PolarBearRenderer
- XXX.renderer.entity.PufferfishRenderer
+ XXX.renderer.entity.RabbitRenderer
- XXX.renderer.entity.RavagerRenderer
+ XXX.renderer.entity.RenderLayerParent
- XXX.renderer.entity.SalmonRenderer
+ XXX.renderer.entity.SheepRenderer
- XXX.renderer.entity.ShulkerBulletRenderer
+ XXX.renderer.entity.ShulkerRenderer
+ XXX.renderer.entity.VillagerProfessionLayer
- XXX.renderer.texture.AbstractTexture
+ XXX.renderer.texture.DynamicTexture
- XXX.renderer.texture.HttpTexture
+ XXX.renderer.texture.LayeredColorMaskTexture
- XXX.renderer.texture.LayeredTexture
+ XXX.renderer.texture.MissingTextureAtlasSprite
- XXX.renderer.texture.OverlayTexture
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
- XXX.state.pattern.BlockInWorld
+ XXX.state.pattern.BlockPattern
- XXX.state.pattern.BlockPattern$BlockCacheLoader
+ XXX.state.pattern.BlockPattern$BlockPatternMatch
- XXX.state.pattern.BlockPattern$PortalInfo
+ XXX.state.pattern.BlockPatternBuilder
- XXX.state.pattern.package-info
+ XXX.state.predicate.BlockMaterialPredicate
- XXX.state.predicate.BlockMaterialPredicate$1
+ XXX.state.predicate.BlockPredicate
- XXX.state.predicate.BlockStatePredicate
+ XXX.state.predicate.package-info
- XXX.state.properties.AbstractProperty
+ XXX.state.properties.AttachFace
- XXX.state.properties.BambooLeaves
+ XXX.state.properties.BedPart
- XXX.state.properties.BellAttachType
+ XXX.state.properties.BlockStateProperties
- XXX.state.properties.BooleanProperty
+ XXX.state.properties.ChestType
- XXX.state.properties.ComparatorMode
+ XXX.state.properties.DirectionProperty
- XXX.state.properties.DoorHingeSide
+ XXX.state.properties.DoubleBlockHalf
- XXX.state.properties.EnumProperty
+ XXX.state.properties.Half
- XXX.state.properties.IntegerProperty
+ XXX.state.properties.NoteBlockInstrument
+ XXX.state.properties.package-info
- XXX.state.properties.PistonType
+ XXX.state.properties.Property
- XXX.state.properties.RailShape
+ XXX.state.properties.RedstoneSide
- XXX.state.properties.SlabType
+ XXX.state.properties.StairsShape
- XXX.state.properties.StructureMode
- XXX.storage.loot.BinomialDistributionGenerator
+ XXX.storage.loot.BinomialDistributionGenerator$Serializer
- XXX.storage.loot.BuiltInLootTables
+ XXX.storage.loot.ConstantIntValue
- XXX.storage.loot.ConstantIntValue$Serializer
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
+ XXX.storage.loot.RandomIntGenerator
- XXX.storage.loot.RandomIntGenerators
+ XXX.storage.loot.RandomValueBounds
- XXX.storage.loot.RandomValueBounds$Serializer
+ XXX.storage.loot.ValidationContext
- XXX.storage.threaded.package-info
+ XXX.structure.templatesystem.AlwaysTrueTest
- XXX.structure.templatesystem.BlockIgnoreProcessor
+ XXX.structure.templatesystem.BlockMatchTest
- XXX.structure.templatesystem.BlockRotProcessor
+ XXX.structure.templatesystem.BlockStateMatchTest
- XXX.structure.templatesystem.GravityProcessor
+ XXX.structure.templatesystem.JigsawReplacementProcessor
- XXX.structure.templatesystem.NopProcessor
+ XXX.structure.templatesystem.package-info
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
+ XXX.structure.templatesystem.StructureTemplate$SimplePalette
- XXX.structure.templatesystem.StructureTemplate$StructureBlockInfo
+ XXX.structure.templatesystem.StructureTemplate$StructureEntityInfo
- XXX.structure.templatesystem.TagMatchTest
+ XXX.texture.custom.package-info
+ XXX.village.poi.package-info
+ XXX.village.poi.PoiManager
- XXX.village.poi.PoiManager$DistanceTracker
+ XXX.village.poi.PoiManager$Occupancy
- XXX.village.poi.PoiRecord
+ XXX.village.poi.PoiSection
- XXX.village.poi.PoiType
+ XXX.world.entity.package-info
- XXX.world.entity.ReputationEventHandler
+ XXX.world.entity.SpawnGroupData
- XXX.world.entity.SpawnPlacements
+ XXX.world.entity.SpawnPlacements$Data
- XXX.world.entity.SpawnPlacements$SpawnPredicate
+ XXX.world.entity.SpawnPlacements$Type
- XXX.world.entity.TamableAnimal
+ XXX.world.food.FoodConstants
- XXX.world.food.FoodData
+ XXX.world.food.FoodProperties
- XXX.world.food.FoodProperties$1
+ XXX.world.food.FoodProperties$Builder
- XXX.world.food.Foods
+ XXX.world.food.package-info
- XXX.world.inventory.AbstractContainerMenu
+ XXX.world.inventory.AbstractFurnaceMenu
- XXX.world.inventory.AnvilMenu
+ XXX.world.inventory.AnvilMenu$1
- XXX.world.inventory.AnvilMenu$2
+ XXX.world.inventory.AnvilMenu$3
- XXX.world.inventory.BeaconMenu
+ XXX.world.inventory.BeaconMenu$1
- XXX.world.inventory.BeaconMenu$PaymentSlot
+ XXX.world.inventory.BlastFurnaceMenu
- XXX.world.inventory.BrewingStandMenu
+ XXX.world.inventory.BrewingStandMenu$FuelSlot
- XXX.world.inventory.BrewingStandMenu$IngredientsSlot
+ XXX.world.inventory.BrewingStandMenu$PotionSlot
- XXX.world.inventory.CartographyTableMenu
+ XXX.world.inventory.CartographyTableMenu$1
- XXX.world.inventory.CartographyTableMenu$2
+ XXX.world.inventory.CartographyTableMenu$3
- XXX.world.inventory.CartographyTableMenu$4
+ XXX.world.inventory.CartographyTableMenu$5
- XXX.world.inventory.ChestMenu
+ XXX.world.inventory.ClickType
- XXX.world.inventory.ContainerData
+ XXX.world.inventory.ContainerLevelAccess
- XXX.world.inventory.ContainerLevelAccess$1
+ XXX.world.inventory.ContainerLevelAccess$2
- XXX.world.inventory.ContainerListener
+ XXX.world.inventory.CraftingContainer
- XXX.world.inventory.CraftingMenu
+ XXX.world.inventory.DataSlot
- XXX.world.inventory.DataSlot$1
+ XXX.world.inventory.DataSlot$2
- XXX.world.inventory.DataSlot$3
+ XXX.world.inventory.DispenserMenu
- XXX.world.inventory.EnchantmentMenu
+ XXX.world.inventory.EnchantmentMenu$1
- XXX.world.inventory.EnchantmentMenu$2
+ XXX.world.inventory.EnchantmentMenu$3
- XXX.world.inventory.FurnaceFuelSlot
+ XXX.world.inventory.FurnaceMenu
- XXX.world.inventory.FurnaceResultSlot
+ XXX.world.inventory.GrindstoneMenu
- XXX.world.inventory.GrindstoneMenu$1
+ XXX.world.inventory.GrindstoneMenu$2
- XXX.world.inventory.GrindstoneMenu$3
+ XXX.world.inventory.GrindstoneMenu$4
- XXX.world.inventory.HopperMenu
+ XXX.world.inventory.HorseInventoryMenu
- XXX.world.inventory.HorseInventoryMenu$1
+ XXX.world.inventory.HorseInventoryMenu$2
- XXX.world.inventory.InventoryMenu
+ XXX.world.inventory.InventoryMenu$1
- XXX.world.inventory.InventoryMenu$2
+ XXX.world.inventory.LecternMenu
- XXX.world.inventory.LecternMenu$1
+ XXX.world.inventory.LoomMenu
- XXX.world.inventory.LoomMenu$1
+ XXX.world.inventory.LoomMenu$2
- XXX.world.inventory.LoomMenu$3
+ XXX.world.inventory.LoomMenu$4
- XXX.world.inventory.LoomMenu$5
+ XXX.world.inventory.LoomMenu$6
- XXX.world.inventory.MenuConstructor
+ XXX.world.inventory.MenuType
- XXX.world.inventory.MenuType$MenuSupplier
+ XXX.world.inventory.MerchantContainer
- XXX.world.inventory.MerchantMenu
+ XXX.world.inventory.MerchantResultSlot
- XXX.world.inventory.package-info
- XXX.world.inventory.PlayerEnderChestContainer
+ XXX.world.inventory.RecipeBookMenu
- XXX.world.inventory.RecipeHolder
+ XXX.world.inventory.ResultContainer
- XXX.world.inventory.ResultSlot
+ XXX.world.inventory.ShulkerBoxMenu
- XXX.world.inventory.ShulkerBoxSlot
+ XXX.world.inventory.SimpleContainerData
- XXX.world.inventory.Slot
+ XXX.world.inventory.SmokerMenu
- XXX.world.inventory.StackedContentsCompatible
+ XXX.world.inventory.StonecutterMenu
- XXX.world.inventory.StonecutterMenu$1
+ XXX.world.inventory.StonecutterMenu$2
+ XXX.world.item.AirItem
- XXX.world.item.ArmorItem
+ XXX.world.item.ArmorItem$1
- XXX.world.item.ArmorMaterial
+ XXX.world.item.ArmorMaterials
- XXX.world.item.ArmorStandItem
+ XXX.world.item.ArrowItem
- XXX.world.item.AxeItem
+ XXX.world.item.BannerItem
- XXX.world.item.BannerPatternItem
+ XXX.world.item.BedItem
- XXX.world.item.BlockItem
+ XXX.world.item.BlockPlaceContext
- XXX.world.item.BoatItem
+ XXX.world.item.BoneMealItem
- XXX.world.item.BookItem
+ XXX.world.item.BottleItem
- XXX.world.item.BowItem
+ XXX.world.item.BowlFoodItem
- XXX.world.item.BucketItem
+ XXX.world.item.CarrotOnAStickItem
- XXX.world.item.ChorusFruitItem
+ XXX.world.item.ClockItem
- XXX.world.item.ClockItem$1
+ XXX.world.item.CompassItem
- XXX.world.item.CompassItem$1
+ XXX.world.item.ComplexItem
- XXX.world.item.CreativeModeTab
+ XXX.world.item.CreativeModeTab$1
- XXX.world.item.CreativeModeTab$10
+ XXX.world.item.CreativeModeTab$11
- XXX.world.item.CreativeModeTab$12
+ XXX.world.item.CreativeModeTab$2
- XXX.world.item.CreativeModeTab$3
+ XXX.world.item.CreativeModeTab$4
- XXX.world.item.CreativeModeTab$5
+ XXX.world.item.CreativeModeTab$6
- XXX.world.item.CreativeModeTab$7
+ XXX.world.item.CreativeModeTab$8
- XXX.world.item.CreativeModeTab$9
+ XXX.world.item.CrossbowItem
- XXX.world.item.DebugStickItem
+ XXX.world.item.DiggerItem
- XXX.world.item.DirectionalPlaceContext
+ XXX.world.item.DirectionalPlaceContext$1
- XXX.world.item.DoubleHighBlockItem
+ XXX.world.item.DyeableArmorItem
- XXX.world.item.DyeableHorseArmorItem
+ XXX.world.item.DyeableLeatherItem
+ XXX.world.item.DyeColor
- XXX.world.item.DyeItem
- XXX.world.item.EggItem
+ XXX.world.item.ElytraItem
- XXX.world.item.EmptyMapItem
+ XXX.world.item.EnchantedBookItem
- XXX.world.item.EnchantedGoldenAppleItem
+ XXX.world.item.EndCrystalItem
- XXX.world.item.EnderEyeItem
+ XXX.world.item.EnderpearlItem
- XXX.world.item.ExperienceBottleItem
+ XXX.world.item.FireChargeItem
- XXX.world.item.FireworkRocketItem
+ XXX.world.item.FireworkRocketItem$Shape
- XXX.world.item.FireworkStarItem
+ XXX.world.item.FishBucketItem
- XXX.world.item.FishingRodItem
+ XXX.world.item.FlintAndSteelItem
- XXX.world.item.GameMasterBlockItem
+ XXX.world.item.HangingEntityItem
- XXX.world.item.HoeItem
+ XXX.world.item.HoneyBottleItem
- XXX.world.item.HorseArmorItem
+ XXX.world.item.Item
- XXX.world.item.Item$1
+ XXX.world.item.Item$Properties
- XXX.world.item.ItemCooldowns
+ XXX.world.item.ItemCooldowns$1
- XXX.world.item.ItemCooldowns$CooldownInstance
+ XXX.world.item.ItemFrameItem
- XXX.world.item.ItemNameBlockItem
+ XXX.world.item.ItemPropertyFunction
+ XXX.world.item.Items
- XXX.world.item.ItemStack
- XXX.world.item.KnowledgeBookItem
+ XXX.world.item.LeadItem
- XXX.world.item.LingeringPotionItem
+ XXX.world.item.MapItem
- XXX.world.item.MilkBucketItem
+ XXX.world.item.MinecartItem
- XXX.world.item.MinecartItem$1
+ XXX.world.item.NameTagItem
+ XXX.world.item.package-info
- XXX.world.item.PickaxeItem
+ XXX.world.item.PlayerHeadItem
- XXX.world.item.PotionItem
+ XXX.world.item.ProjectileWeaponItem
- XXX.world.item.ProjectileWeaponItem$Type
+ XXX.world.item.Rarity
- XXX.world.item.RecordItem
+ XXX.world.item.SaddleItem
- XXX.world.item.ScaffoldingBlockItem
+ XXX.world.item.ServerItemCooldowns
- XXX.world.item.ShearsItem
+ XXX.world.item.ShieldItem
- XXX.world.item.ShovelItem
+ XXX.world.item.SignItem
- XXX.world.item.SimpleFoiledItem
+ XXX.world.item.SnowballItem
- XXX.world.item.SpawnEggItem
+ XXX.world.item.SpectralArrowItem
- XXX.world.item.SplashPotionItem
+ XXX.world.item.StandingAndWallBlockItem
- XXX.world.item.SuspiciousStewItem
+ XXX.world.item.SwordItem
- XXX.world.item.ThrowablePotionItem
+ XXX.world.item.Tier
- XXX.world.item.TieredItem
+ XXX.world.item.Tiers
- XXX.world.item.TippedArrowItem
+ XXX.world.item.TooltipFlag
- XXX.world.item.TooltipFlag$Default
+ XXX.world.item.TridentItem
- XXX.world.item.UseAnim
+ XXX.world.item.UseOnContext
- XXX.world.item.WaterLilyBlockItem
+ XXX.world.item.WritableBookItem
- XXX.world.item.WrittenBookItem
- XXX.world.level.BaseCommandBlock
+ XXX.world.level.BaseSpawner
- XXX.world.level.BlockAndBiomeGetter
+ XXX.world.level.BlockEventData
- XXX.world.level.BlockGetter
+ XXX.world.level.ChunkPos
- XXX.world.level.ChunkPos$1
+ XXX.world.level.ChunkTickList
- XXX.world.level.ClipContext
+ XXX.world.level.ClipContext$Block
- XXX.world.level.ClipContext$Fluid
+ XXX.world.level.ClipContext$ShapeGetter
- XXX.world.level.CollisionGetter
+ XXX.world.level.CollisionGetter$1
- XXX.world.level.CustomSpawner
+ XXX.world.level.EmptyBlockGetter
- XXX.world.level.EmptyTickList
+ XXX.world.level.EntityGetter
- XXX.world.level.Explosion
+ XXX.world.level.Explosion$BlockInteraction
- XXX.world.level.FoliageColor
+ XXX.world.level.ForcedChunksSavedData
- XXX.world.level.GameRules
+ XXX.world.level.GameRules$1
- XXX.world.level.GameRules$BooleanValue
+ XXX.world.level.GameRules$GameRuleTypeVisitor
- XXX.world.level.GameRules$IntegerValue
+ XXX.world.level.GameRules$Key
- XXX.world.level.GameRules$Type
+ XXX.world.level.GameRules$Value
- XXX.world.level.GameType
+ XXX.world.level.GrassColor
- XXX.world.level.ItemLike
+ XXX.world.level.Level
- XXX.world.level.LevelAccessor
+ XXX.world.level.LevelConflictException
- XXX.world.level.LevelReader
+ XXX.world.level.LevelSettings
+ XXX.world.level.LevelSimulatedReader
- XXX.world.level.LevelSimulatedRW
- XXX.world.level.LevelType
+ XXX.world.level.LevelWriter
- XXX.world.level.LightLayer
+ XXX.world.level.NaturalSpawner
- XXX.world.level.NaturalSpawner$1
- XXX.world.level.package-info
+ XXX.world.level.PathNavigationRegion
- XXX.world.level.PortalForcer
+ XXX.world.level.ServerTickList
- XXX.world.level.SpawnData
+ XXX.world.level.TickList
- XXX.world.level.TickNextTickData
+ XXX.world.level.TickPriority
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
XXX.blaze3d.platform.GLX -1M
```
```
XXX.blaze3d.vertex.VertexFormat -7M | +1P -4P
```
```
XXX.mojang.math.Vector4f +3M -3M
```
```
XXX.minecraft.client.KeyboardHandler -1M
```
```
XXX.client.gui.Font +5M -3M
```
```
XXX.client.gui.GuiComponent +1M
```
```
XXX.gui.font.FontSet +1M | +1P
```
```
XXX.client.model.ArmorStandArmorModel -1M
```
```
XXX.client.model.BatModel +1M -2M
```
```
XXX.client.model.BlazeModel +1M -1M | +1P
```
```
XXX.client.model.BookModel +2M -4M
```
```
XXX.client.model.ChestedHorseModel +3M -3M
```
```
XXX.client.model.CodModel +1M -1M
```
```
XXX.client.model.CreeperModel +1M -1M
```
```
XXX.client.model.HumanoidHeadModel +1M -1M
```
```
XXX.client.model.IllagerModel +2M -3M | -1P
```
```
XXX.client.model.LavaSlimeModel +4M -2M | +1P
```
```
XXX.client.model.PolarBearModel -2M
```
```
XXX.client.model.PufferfishMidModel +1M -1M
```
```
XXX.client.model.QuadrupedModel +3M -3M | -2P
```
```
XXX.client.model.RavagerModel +1M -3M
```
```
XXX.client.model.ShieldModel +1M -1M
```
```
XXX.client.model.ShulkerModel +1M -2M
```
```
XXX.client.model.VexModel +1M -3M
```
```
XXX.client.renderer.ItemInHandRenderer +11M -20M | -1P
```
```
XXX.client.renderer.LightTexture +1M -1M
```
```
XXX.renderer.block.ModelBlockRenderer +8M -9M
```
```
XXX.block.model.BlockModel +3M -3M
```
```
XXX.block.model.ItemTransform +1M
```
```
XXX.block.model.ItemTransforms -2M | -9P
```
```
XXX.block.model.MultiVariant +1M -1M
```
```
XXX.block.model.Variant +2M -2M | +1P -1P
```
```
XXX.renderer.blockentity.BannerRenderer +3M -3M
```
```
XXX.renderer.blockentity.SkullBlockRenderer +4M -5M | -1P
```
```
XXX.renderer.blockentity.SpawnerRenderer +3M -4M
```
```
XXX.renderer.blockentity.TheEndPortalRenderer +5M -4M | -3P
```
```
XXX.renderer.chunk.ChunkRenderDispatcher +5M -3M | +5P -3P
```
```
XXX.renderer.entity.AbstractZombieRenderer +2M -2M
```
```
XXX.renderer.entity.EndermanRenderer +6M -4M
```
```
XXX.renderer.entity.EntityRenderDispatcher +16M -13M | +1P -4P
```
```
XXX.renderer.entity.EvokerFangsRenderer +2M -2M
```
```
XXX.renderer.entity.EvokerRenderer$1 +3M -3M
```
```
XXX.renderer.entity.FallingBlockRenderer +2M -2M
```
```
XXX.renderer.entity.FishingHookRenderer +3M -2M
```
```
XXX.renderer.entity.GhastRenderer +2M -2M
```
```
XXX.renderer.entity.GuardianRenderer +8M -7M
```
```
XXX.renderer.entity.LightningBoltRenderer +3M -2M
```
```
XXX.renderer.entity.LlamaSpitRenderer +2M -2M
```
```
XXX.renderer.entity.SlimeRenderer +6M -6M
```
```
XXX.renderer.entity.SquidRenderer +2M -2M
```
```
XXX.renderer.entity.ThrownItemRenderer +1M -1M
```
```
XXX.renderer.entity.TntRenderer +2M -2M
```
```
XXX.renderer.entity.TurtleRenderer +4M -4M
```
```
XXX.renderer.entity.VexRenderer +2M -2M
```
```
XXX.renderer.entity.WanderingTraderRenderer +2M -2M
```
```
XXX.renderer.entity.WitherBossRenderer +2M -2M
```
```
XXX.renderer.entity.WitherSkullRenderer +2M -3M
```
```
XXX.entity.layers.AbstractArmorLayer +4M -8M | -6P
```
```
XXX.entity.layers.BeeStingerLayer +1M -4M
```
```
XXX.entity.layers.CarriedBlockLayer +2M -3M
```
```
XXX.entity.layers.CreeperPowerLayer +3M -3M
```
```
XXX.entity.layers.Deadmau5EarsLayer +2M -3M
```
```
XXX.entity.layers.DrownedOuterLayer +2M -3M
```
```
XXX.entity.layers.EnderEyesLayer +1M -3M
```
```
XXX.entity.layers.WitchItemLayer +2M -3M
```
```
XXX.entity.layers.WolfCollarLayer +2M -3M
```
```
XXX.resources.model.BlockModelRotation +3M -7M
```
```
XXX.resources.model.ModelBakery +25M -24M | +7P
```
```
XXX.resources.model.UnbakedModel +1P -1P
```
```
XXX.minecraft.nbt.ByteTag +5M -2M | +3P
```
```
XXX.minecraft.nbt.CompoundTag +8M -4M | +1P
```
```
XXX.minecraft.nbt.EndTag +2M -3M | +2P
```
```
XXX.minecraft.nbt.IntArrayTag +2M -2M | +1P
```
```
XXX.minecraft.nbt.TagParser +1M -1M
```
```
XXX.minecraft.realms.RealmsVertexFormat -11M
```
```
XXX.minecraft.realms.Tezzelator +2M -6M
```
```
XXX.server.level.BlockDestructionProgress +4M
```
```
XXX.minecraft.util.Mth +3M
```
```
XXX.world.entity.Entity +2M
```
```
XXX.world.entity.LivingEntity -1P
```

</details>
<details>
<summary>
com.mojang.blaze3d.platform.GLX
</summary>

```diff
+ void _pollEvents()
```

</details>
<details>
<summary>
com.mojang.blaze3d.vertex.VertexFormat
</summary>

```diff
+ boolean hasColor()
+ boolean hasNormal()
+ boolean hasUv(int)
+ int getColorOffset()
+ int getNormalOffset()
+ int getOffset(int)
+ int getUvOffset(int)
```

</details>
<details>
<summary>
com.mojang.math.Vector4f
</summary>

```diff
- boolean normalize()
- float dot(Vector4f)
+ float w()
- void perspectiveDivide()
+ void set(float,float,float,float)
+ void transform(Quaternion)
```

</details>
<details>
<summary>
net.minecraft.client.KeyboardHandler
</summary>

```diff
+ void handleModelDebugHotkeys(int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.Font
</summary>

```diff
- float renderText(String,float,float,int,boolean,Matrix4f,MultiBufferSource,boolean,int,int)
+ float renderText(String,float,float,int,boolean)
- int drawInBatch(String,float,float,int,boolean,Matrix4f,MultiBufferSource,boolean,int,int)
- int drawInternal(String,float,float,int,boolean,Matrix4f,MultiBufferSource,boolean,int,int)
+ int drawInternal(String,float,float,int,boolean)
- int drawInternal(String,float,float,int,Matrix4f,boolean)
+ void renderChar(BakedGlyph,boolean,boolean,float,float,float,BufferBuilder,float,float,float,float)
- void renderChar(BakedGlyph,boolean,boolean,float,float,float,Matrix4f,VertexConsumer,float,float,float,float,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.GuiComponent
</summary>

```diff
- void fill(Matrix4f,int,int,int,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.font.FontSet
</summary>

```diff
- BakedGlyph whiteGlyph()
```

</details>
<details>
<summary>
net.minecraft.client.model.ArmorStandArmorModel
</summary>

```diff
+ void <init>()
```

</details>
<details>
<summary>
net.minecraft.client.model.BatModel
</summary>

```diff
- Iterable parts()
+ void render(Bat,float,float,float,float,float,float)
+ void render(Entity,float,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.model.BlazeModel
</summary>

```diff
- Iterable parts()
+ void render(Entity,float,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.model.BookModel
</summary>

```diff
+ void lambda$render$0(float,ModelPart)
- void lambda$render$0(PoseStack,VertexConsumer,float,int,TextureAtlasSprite,ModelPart)
+ void lambda$render$1(BufferBuilder,float,int,int,TextureAtlasSprite,ModelPart)
+ void render(BufferBuilder,float,int,int,TextureAtlasSprite)
+ void render(float)
- void render(PoseStack,VertexConsumer,float,int,TextureAtlasSprite)
```

</details>
<details>
<summary>
net.minecraft.client.model.ChestedHorseModel
</summary>

```diff
+ void render(AbstractChestedHorse,float,float,float,float,float,float)
+ void render(AbstractHorse,float,float,float,float,float,float)
+ void render(Entity,float,float,float,float,float,float)
- void setupAnim(AbstractChestedHorse,float,float,float,float,float,float)
- void setupAnim(AbstractHorse,float,float,float,float,float,float)
- void setupAnim(Entity,float,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.model.CodModel
</summary>

```diff
- Iterable parts()
+ void render(Entity,float,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.model.CreeperModel
</summary>

```diff
- Iterable parts()
+ void render(Entity,float,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.model.HumanoidHeadModel
</summary>

```diff
+ void render(float,float,float,float,float,float)
- void render(PoseStack,VertexConsumer,float,float,float,float,int)
```

</details>
<details>
<summary>
net.minecraft.client.model.IllagerModel
</summary>

```diff
- Iterable parts()
+ void render(AbstractIllager,float,float,float,float,float,float)
+ void render(Entity,float,float,float,float,float,float)
- void translateToHand(float,HumanoidArm,PoseStack)
+ void translateToHand(float,HumanoidArm)
```

</details>
<details>
<summary>
net.minecraft.client.model.LavaSlimeModel
</summary>

```diff
- ImmutableList parts()
- Iterable parts()
+ void render(Entity,float,float,float,float,float,float)
+ void render(Slime,float,float,float,float,float,float)
- void setupAnim(Entity,float,float,float,float,float,float)
- void setupAnim(Slime,float,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.model.PolarBearModel
</summary>

```diff
+ void render(Entity,float,float,float,float,float,float)
+ void render(PolarBear,float,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.model.PufferfishMidModel
</summary>

```diff
- Iterable parts()
+ void render(Entity,float,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.model.QuadrupedModel
</summary>

```diff
- Iterable bodyParts()
- Iterable headParts()
- void <init>(int,float,boolean,float,float,float,float,int)
+ void <init>(int,float)
+ void render(Entity,float,float,float,float,float,float)
+ void render(QuadrupedModel,float)
```

</details>
<details>
<summary>
net.minecraft.client.model.RavagerModel
</summary>

```diff
- Iterable parts()
+ void render(Entity,float,float,float,float,float,float)
+ void render(Ravager,float,float,float,float,float,float)
+ void render(RavagerModel,float)
```

</details>
<details>
<summary>
net.minecraft.client.model.ShieldModel
</summary>

```diff
+ void render()
- void render(PoseStack,VertexConsumer,int)
```

</details>
<details>
<summary>
net.minecraft.client.model.ShulkerModel
</summary>

```diff
- Iterable parts()
+ void render(Entity,float,float,float,float,float,float)
+ void render(Shulker,float,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.model.VexModel
</summary>

```diff
- Iterable bodyParts()
+ void render(Entity,float,float,float,float,float,float)
+ void render(LivingEntity,float,float,float,float,float,float)
+ void render(Vex,float,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.ItemInHandRenderer
</summary>

```diff
+ void applyEatTransform(float,HumanoidArm,ItemStack)
- void applyEatTransform(PoseStack,float,HumanoidArm,ItemStack)
+ void applyItemArmAttackTransform(HumanoidArm,float)
- void applyItemArmAttackTransform(PoseStack,HumanoidArm,float)
+ void applyItemArmTransform(HumanoidArm,float)
- void applyItemArmTransform(PoseStack,HumanoidArm,float)
+ void enableLight(float,float)
+ void render(float)
- void renderArmWithItem(AbstractClientPlayer,float,float,InteractionHand,float,ItemStack,float,PoseStack,MultiBufferSource)
+ void renderArmWithItem(AbstractClientPlayer,float,float,InteractionHand,float,ItemStack,float)
+ void renderFire()
- void renderHandsWithItems(float,PoseStack,MultiBufferSource$BufferSource)
- void renderItem(LivingEntity,ItemStack,ItemTransforms$TransformType,boolean,PoseStack,MultiBufferSource)
+ void renderItem(LivingEntity,ItemStack,ItemTransforms$TransformType,boolean)
+ void renderItem(LivingEntity,ItemStack,ItemTransforms$TransformType)
+ void renderMap(ItemStack)
- void renderMap(PoseStack,MultiBufferSource,ItemStack)
+ void renderMapHand(HumanoidArm)
- void renderMapHand(PoseStack,MultiBufferSource,HumanoidArm)
+ void renderMapHands()
+ void renderOneHandedMap(float,HumanoidArm,float,ItemStack)
- void renderOneHandedMap(PoseStack,MultiBufferSource,float,HumanoidArm,float,ItemStack)
+ void renderPlayerArm(float,float,HumanoidArm)
- void renderPlayerArm(PoseStack,MultiBufferSource,float,float,HumanoidArm)
+ void renderScreenEffect(float)
+ void renderTex(TextureAtlasSprite)
+ void renderTwoHandedMap(float,float,float)
- void renderTwoHandedMap(PoseStack,MultiBufferSource,float,float,float)
+ void renderWater(float)
+ void setLightValue()
+ void setPlayerBob(float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.LightTexture
</summary>

```diff
- void <init>(GameRenderer,Minecraft)
+ void <init>(GameRenderer)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.block.ModelBlockRenderer
</summary>

```diff
+ boolean tesselateBlock(BlockAndBiomeGetter,BakedModel,BlockState,BlockPos,BufferBuilder,boolean,Random,long)
- boolean tesselateBlock(BlockAndBiomeGetter,BakedModel,BlockState,BlockPos,PoseStack,VertexConsumer,boolean,Random,long)
+ boolean tesselateWithAO(BlockAndBiomeGetter,BakedModel,BlockState,BlockPos,BufferBuilder,boolean,Random,long)
- boolean tesselateWithAO(BlockAndBiomeGetter,BakedModel,BlockState,BlockPos,PoseStack,VertexConsumer,boolean,Random,long)
+ boolean tesselateWithoutAO(BlockAndBiomeGetter,BakedModel,BlockState,BlockPos,BufferBuilder,boolean,Random,long)
- boolean tesselateWithoutAO(BlockAndBiomeGetter,BakedModel,BlockState,BlockPos,PoseStack,VertexConsumer,boolean,Random,long)
- void putQuadData(BlockAndBiomeGetter,BlockState,BlockPos,VertexConsumer,Matrix4f,BakedQuad,float,float,float,float,int,int,int,int)
+ void renderModel(BakedModel,float,float,float,float)
+ void renderModel(BlockState,BakedModel,float,float,float,float)
- void renderModel(Matrix4f,VertexConsumer,BlockState,BakedModel,float,float,float,int)
+ void renderModelFaceAO(BlockAndBiomeGetter,BlockState,BlockPos,BufferBuilder,List,float[],BitSet,ModelBlockRenderer$AmbientOcclusionFace)
- void renderModelFaceAO(BlockAndBiomeGetter,BlockState,BlockPos,PoseStack,VertexConsumer,List,float[],BitSet,ModelBlockRenderer$AmbientOcclusionFace)
+ void renderModelFaceFlat(BlockAndBiomeGetter,BlockState,BlockPos,int,boolean,BufferBuilder,List,BitSet)
- void renderModelFaceFlat(BlockAndBiomeGetter,BlockState,BlockPos,int,boolean,PoseStack,VertexConsumer,List,BitSet)
+ void renderQuadList(float,float,float,float,List)
- void renderQuadList(Matrix4f,VertexConsumer,float,float,float,List,int)
+ void renderSingleBlock(BakedModel,BlockState,float,boolean)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.block.model.BlockModel
</summary>

```diff
- BakedModel bake(ModelBakery,BlockModel,Function,ModelState,ResourceLocation)
+ BakedModel bake(ModelBakery,BlockModel,Function,ModelState)
- BakedModel bake(ModelBakery,Function,ModelState,ResourceLocation)
+ BakedModel bake(ModelBakery,Function,ModelState)
- BakedQuad bakeFace(BlockElement,BlockElementFace,TextureAtlasSprite,Direction,ModelState,ResourceLocation)
+ BakedQuad bakeFace(BlockElement,BlockElementFace,TextureAtlasSprite,Direction,ModelState)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.block.model.ItemTransform
</summary>

```diff
- void apply(boolean,PoseStack)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.block.model.ItemTransforms
</summary>

```diff
+ void apply(ItemTransform,boolean)
+ void apply(ItemTransforms$TransformType)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.block.model.MultiVariant
</summary>

```diff
- BakedModel bake(ModelBakery,Function,ModelState,ResourceLocation)
+ BakedModel bake(ModelBakery,Function,ModelState)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.block.model.Variant
</summary>

```diff
+ BlockModelRotation getRotation()
- Transformation getRotation()
+ void <init>(ResourceLocation,BlockModelRotation,boolean,int)
- void <init>(ResourceLocation,Transformation,boolean,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.blockentity.BannerRenderer
</summary>

```diff
+ void <init>()
- void <init>(BlockEntityRenderDispatcher)
- void render(BannerBlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int)
- void render(BlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int)
+ void renderToBuffer(BannerBlockEntity,double,double,double,float,int,RenderType,BufferBuilder,int,int)
+ void renderToBuffer(BlockEntity,double,double,double,float,int,RenderType,BufferBuilder,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.blockentity.SkullBlockRenderer
</summary>

```diff
+ void <init>()
- void <init>(BlockEntityRenderDispatcher)
+ void init(BlockEntityRenderDispatcher)
+ void render(BlockEntity,double,double,double,float,int,RenderType)
- void render(BlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int)
+ void render(SkullBlockEntity,double,double,double,float,int,RenderType)
- void render(SkullBlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int)
- void renderSkull(Direction,float,SkullBlock$Type,GameProfile,float,PoseStack,MultiBufferSource,int)
+ void renderSkull(float,float,float,Direction,float,SkullBlock$Type,GameProfile,int,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.blockentity.SpawnerRenderer
</summary>

```diff
+ void <init>()
- void <init>(BlockEntityRenderDispatcher)
+ void render(BaseSpawner,double,double,double,float)
+ void render(BlockEntity,double,double,double,float,int,RenderType)
- void render(BlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int)
+ void render(SpawnerBlockEntity,double,double,double,float,int,RenderType)
- void render(SpawnerBlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.blockentity.TheEndPortalRenderer
</summary>

```diff
+ FloatBuffer getBuffer(float,float,float,float)
+ void <init>()
- void <init>(BlockEntityRenderDispatcher)
+ void render(BlockEntity,double,double,double,float,int,RenderType)
- void render(BlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int)
+ void render(TheEndPortalBlockEntity,double,double,double,float,int,RenderType)
- void render(TheEndPortalBlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int)
- void renderCube(TheEndPortalBlockEntity,double,double,double,float,float,VertexConsumer)
- void renderFace(TheEndPortalBlockEntity,VertexConsumer,Direction,double,double,double,double,double,double,double,double,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.chunk.ChunkRenderDispatcher
</summary>

```diff
- ChunkBufferBuilderPack fixedBuffers()
+ CompletionStage lambda$uploadChunkLayer$5(BufferBuilder,VertexBuffer,Void)
- CompletionStage lambda$uploadChunkLayer$6(BufferBuilder,VertexBuffer,Void)
- void <init>(Level,LevelRenderer,Executor,boolean,ChunkBufferBuilderPack)
+ void <init>(Level,LevelRenderer,Executor,boolean)
- void lambda$schedule$4(ChunkRenderDispatcher$RenderChunk$ChunkCompileTask)
+ void lambda$uploadChunkLayer$4()
- void lambda$uploadChunkLayer$5()
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.AbstractZombieRenderer
</summary>

```diff
+ void setupRotations(LivingEntity,float,float,float)
- void setupRotations(LivingEntity,PoseStack,float,float,float)
+ void setupRotations(Zombie,float,float,float)
- void setupRotations(Zombie,PoseStack,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.EndermanRenderer
</summary>

```diff
- Vec3 getRenderOffset(EnderMan,double,double,double,float)
- Vec3 getRenderOffset(Entity,double,double,double,float)
- void render(EnderMan,double,double,double,float,float,PoseStack,MultiBufferSource)
+ void render(EnderMan,double,double,double,float,float)
- void render(Entity,double,double,double,float,float,PoseStack,MultiBufferSource)
+ void render(Entity,double,double,double,float,float)
- void render(LivingEntity,double,double,double,float,float,PoseStack,MultiBufferSource)
+ void render(LivingEntity,double,double,double,float,float)
- void render(Mob,double,double,double,float,float,PoseStack,MultiBufferSource)
+ void render(Mob,double,double,double,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.EntityRenderDispatcher
</summary>

```diff
+ boolean hasSecondPass(Entity)
+ boolean shouldRender(Entity,Culler,double,double,double)
- boolean shouldRender(Entity,Frustum,double,double,double)
+ boolean shouldRenderShadow()
- double distanceToSqr(Entity)
+ EntityRenderer getRenderer(Class)
- void <clinit>()
- void <init>(TextureManager,ItemRenderer,ReloadableResourceManager,Font,Options)
+ void <init>(TextureManager,ItemRenderer,ReloadableResourceManager)
- void fireVertex(Matrix4f,VertexConsumer,float,float,float,float,float)
- void prepare(Level,Camera,Entity)
+ void prepare(Level,Font,Camera,Entity,Options)
+ void register(Class,EntityRenderer)
- void register(EntityType,EntityRenderer)
- void registerRenderers(ItemRenderer,ReloadableResourceManager)
+ void render(Entity,double,double,double,float,float,boolean)
- void render(Entity,double,double,double,float,float,PoseStack,MultiBufferSource)
+ void render(Entity,float,boolean)
- void render(Entity,float)
- void renderBlockShadow(Matrix4f,VertexConsumer,LevelReader,BlockPos,double,double,double,float,float)
- void renderBox(PoseStack,VertexConsumer,Entity,float,float,float)
- void renderFlame(PoseStack,MultiBufferSource,Entity)
+ void renderHitbox(Entity,double,double,double,float,float)
- void renderHitbox(PoseStack,VertexConsumer,Entity,float)
+ void renderSecondPass(Entity,float)
- void renderShadow(PoseStack,MultiBufferSource,Entity,float,float,LevelReader,float)
+ void setPosition(double,double,double)
+ void setSolidRendering(boolean)
- void shadowVertex(Matrix4f,VertexConsumer,float,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.EvokerFangsRenderer
</summary>

```diff
- void render(Entity,double,double,double,float,float,PoseStack,MultiBufferSource)
+ void render(Entity,double,double,double,float,float)
- void render(EvokerFangs,double,double,double,float,float,PoseStack,MultiBufferSource)
+ void render(EvokerFangs,double,double,double,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.EvokerRenderer$1
</summary>

```diff
+ void render(Entity,float,float,float,float,float,float,float)
+ void render(LivingEntity,float,float,float,float,float,float,float)
- void render(PoseStack,MultiBufferSource,int,Entity,float,float,float,float,float,float,float)
- void render(PoseStack,MultiBufferSource,int,LivingEntity,float,float,float,float,float,float,float)
- void render(PoseStack,MultiBufferSource,int,SpellcasterIllager,float,float,float,float,float,float,float)
+ void render(SpellcasterIllager,float,float,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.FallingBlockRenderer
</summary>

```diff
- void render(Entity,double,double,double,float,float,PoseStack,MultiBufferSource)
+ void render(Entity,double,double,double,float,float)
- void render(FallingBlockEntity,double,double,double,float,float,PoseStack,MultiBufferSource)
+ void render(FallingBlockEntity,double,double,double,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.FishingHookRenderer
</summary>

```diff
- void render(Entity,double,double,double,float,float,PoseStack,MultiBufferSource)
+ void render(Entity,double,double,double,float,float)
- void render(FishingHook,double,double,double,float,float,PoseStack,MultiBufferSource)
+ void render(FishingHook,double,double,double,float,float)
- void stringVertex(float,float,float,VertexConsumer,Matrix4f,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.GhastRenderer
</summary>

```diff
+ void scale(Ghast,float)
- void scale(Ghast,PoseStack,float)
+ void scale(LivingEntity,float)
- void scale(LivingEntity,PoseStack,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.GuardianRenderer
</summary>

```diff
+ boolean shouldRender(Entity,Culler,double,double,double)
- boolean shouldRender(Entity,Frustum,double,double,double)
+ boolean shouldRender(Guardian,Culler,double,double,double)
- boolean shouldRender(Guardian,Frustum,double,double,double)
+ boolean shouldRender(Mob,Culler,double,double,double)
- boolean shouldRender(Mob,Frustum,double,double,double)
- void render(Entity,double,double,double,float,float,PoseStack,MultiBufferSource)
+ void render(Entity,double,double,double,float,float)
- void render(Guardian,double,double,double,float,float,PoseStack,MultiBufferSource)
+ void render(Guardian,double,double,double,float,float)
- void render(LivingEntity,double,double,double,float,float,PoseStack,MultiBufferSource)
+ void render(LivingEntity,double,double,double,float,float)
- void render(Mob,double,double,double,float,float,PoseStack,MultiBufferSource)
+ void render(Mob,double,double,double,float,float)
- void vertex(VertexConsumer,Matrix4f,float,float,float,int,int,int,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.LightningBoltRenderer
</summary>

```diff
- void quad(Matrix4f,VertexConsumer,float,float,int,float,float,float,float,float,float,float,boolean,boolean,boolean,boolean)
- void render(Entity,double,double,double,float,float,PoseStack,MultiBufferSource)
+ void render(Entity,double,double,double,float,float)
- void render(LightningBolt,double,double,double,float,float,PoseStack,MultiBufferSource)
+ void render(LightningBolt,double,double,double,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.LlamaSpitRenderer
</summary>

```diff
- void render(Entity,double,double,double,float,float,PoseStack,MultiBufferSource)
+ void render(Entity,double,double,double,float,float)
- void render(LlamaSpit,double,double,double,float,float,PoseStack,MultiBufferSource)
+ void render(LlamaSpit,double,double,double,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.SlimeRenderer
</summary>

```diff
- void render(Entity,double,double,double,float,float,PoseStack,MultiBufferSource)
+ void render(Entity,double,double,double,float,float)
- void render(LivingEntity,double,double,double,float,float,PoseStack,MultiBufferSource)
+ void render(LivingEntity,double,double,double,float,float)
- void render(Mob,double,double,double,float,float,PoseStack,MultiBufferSource)
+ void render(Mob,double,double,double,float,float)
- void render(Slime,double,double,double,float,float,PoseStack,MultiBufferSource)
+ void render(Slime,double,double,double,float,float)
+ void scale(LivingEntity,float)
- void scale(LivingEntity,PoseStack,float)
+ void scale(Slime,float)
- void scale(Slime,PoseStack,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.SquidRenderer
</summary>

```diff
+ void setupRotations(LivingEntity,float,float,float)
- void setupRotations(LivingEntity,PoseStack,float,float,float)
+ void setupRotations(Squid,float,float,float)
- void setupRotations(Squid,PoseStack,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.ThrownItemRenderer
</summary>

```diff
- void render(Entity,double,double,double,float,float,PoseStack,MultiBufferSource)
+ void render(Entity,double,double,double,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.TntRenderer
</summary>

```diff
- void render(Entity,double,double,double,float,float,PoseStack,MultiBufferSource)
+ void render(Entity,double,double,double,float,float)
- void render(PrimedTnt,double,double,double,float,float,PoseStack,MultiBufferSource)
+ void render(PrimedTnt,double,double,double,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.TurtleRenderer
</summary>

```diff
- void render(Entity,double,double,double,float,float,PoseStack,MultiBufferSource)
+ void render(Entity,double,double,double,float,float)
- void render(LivingEntity,double,double,double,float,float,PoseStack,MultiBufferSource)
+ void render(LivingEntity,double,double,double,float,float)
- void render(Mob,double,double,double,float,float,PoseStack,MultiBufferSource)
+ void render(Mob,double,double,double,float,float)
- void render(Turtle,double,double,double,float,float,PoseStack,MultiBufferSource)
+ void render(Turtle,double,double,double,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.VexRenderer
</summary>

```diff
+ void scale(LivingEntity,float)
- void scale(LivingEntity,PoseStack,float)
+ void scale(Vex,float)
- void scale(Vex,PoseStack,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.WanderingTraderRenderer
</summary>

```diff
+ void scale(LivingEntity,float)
- void scale(LivingEntity,PoseStack,float)
+ void scale(WanderingTrader,float)
- void scale(WanderingTrader,PoseStack,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.WitherBossRenderer
</summary>

```diff
+ void scale(LivingEntity,float)
- void scale(LivingEntity,PoseStack,float)
+ void scale(WitherBoss,float)
- void scale(WitherBoss,PoseStack,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.WitherSkullRenderer
</summary>

```diff
+ float rotlerp(float,float,float)
- void render(Entity,double,double,double,float,float,PoseStack,MultiBufferSource)
+ void render(Entity,double,double,double,float,float)
- void render(WitherSkull,double,double,double,float,float,PoseStack,MultiBufferSource)
+ void render(WitherSkull,double,double,double,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.layers.AbstractArmorLayer
</summary>

```diff
+ boolean colorsOnDamage()
+ ResourceLocation getArmorLocation(ArmorItem,boolean)
+ void render(Entity,float,float,float,float,float,float,float)
+ void render(LivingEntity,float,float,float,float,float,float,float)
- void render(PoseStack,MultiBufferSource,int,Entity,float,float,float,float,float,float,float)
- void render(PoseStack,MultiBufferSource,int,LivingEntity,float,float,float,float,float,float,float)
+ void renderArmorPiece(LivingEntity,float,float,float,float,float,float,float,EquipmentSlot)
- void renderArmorPiece(PoseStack,MultiBufferSource,LivingEntity,float,float,float,float,float,float,float,EquipmentSlot,int)
+ void renderFoil(Consumer,Entity,EntityModel,float,float,float,float,float,float,float)
- void renderModel(PoseStack,MultiBufferSource,int,ArmorItem,boolean,HumanoidModel,boolean,float,float,float,String)
+ void resetColor()
+ void setColor(float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.layers.BeeStingerLayer
</summary>

```diff
+ boolean colorsOnDamage()
+ void postRenderStuckItem()
+ void preRenderStuckItem(LivingEntity)
+ void renderStuckItem(Entity,float,float,float,float)
- void renderStuckItem(PoseStack,MultiBufferSource,Entity,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.layers.CarriedBlockLayer
</summary>

```diff
+ boolean colorsOnDamage()
+ void render(EnderMan,float,float,float,float,float,float,float)
+ void render(Entity,float,float,float,float,float,float,float)
- void render(PoseStack,MultiBufferSource,int,EnderMan,float,float,float,float,float,float,float)
- void render(PoseStack,MultiBufferSource,int,Entity,float,float,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.layers.CreeperPowerLayer
</summary>

```diff
+ boolean colorsOnDamage()
- EntityModel model()
- float xOffset(float)
- ResourceLocation getTextureLocation()
+ void render(Creeper,float,float,float,float,float,float,float)
+ void render(Entity,float,float,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.layers.Deadmau5EarsLayer
</summary>

```diff
+ boolean colorsOnDamage()
+ void render(AbstractClientPlayer,float,float,float,float,float,float,float)
+ void render(Entity,float,float,float,float,float,float,float)
- void render(PoseStack,MultiBufferSource,int,AbstractClientPlayer,float,float,float,float,float,float,float)
- void render(PoseStack,MultiBufferSource,int,Entity,float,float,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.layers.DrownedOuterLayer
</summary>

```diff
+ boolean colorsOnDamage()
+ void render(Entity,float,float,float,float,float,float,float)
- void render(PoseStack,MultiBufferSource,int,Entity,float,float,float,float,float,float,float)
- void render(PoseStack,MultiBufferSource,int,Zombie,float,float,float,float,float,float,float)
+ void render(Zombie,float,float,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.layers.EnderEyesLayer
</summary>

```diff
+ boolean colorsOnDamage()
- ResourceLocation getTextureLocation()
+ void render(Entity,float,float,float,float,float,float,float)
+ void render(LivingEntity,float,float,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.layers.WitchItemLayer
</summary>

```diff
+ boolean colorsOnDamage()
+ void render(Entity,float,float,float,float,float,float,float)
+ void render(LivingEntity,float,float,float,float,float,float,float)
- void render(PoseStack,MultiBufferSource,int,Entity,float,float,float,float,float,float,float)
- void render(PoseStack,MultiBufferSource,int,LivingEntity,float,float,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.layers.WolfCollarLayer
</summary>

```diff
+ boolean colorsOnDamage()
+ void render(Entity,float,float,float,float,float,float,float)
- void render(PoseStack,MultiBufferSource,int,Entity,float,float,float,float,float,float,float)
- void render(PoseStack,MultiBufferSource,int,Wolf,float,float,float,float,float,float,float)
+ void render(Wolf,float,float,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.resources.model.BlockModelRotation
</summary>

```diff
+ BlockModelRotation getRotation()
- BlockModelRotation lambda$static$1(BlockModelRotation)
+ BlockModelRotation lambda$static$2(BlockModelRotation)
+ Direction rotate(Direction)
+ int lambda$static$0(BlockModelRotation)
+ int rotateVertexIndex(Direction,int)
- Integer lambda$static$0(BlockModelRotation)
+ Integer lambda$static$1(BlockModelRotation)
+ Quaternion getRotationQuaternion()
- Transformation getRotation()
```

</details>
<details>
<summary>
net.minecraft.client.resources.model.ModelBakery
</summary>

```diff
+ boolean lambda$null$19(Pair,Map$Entry)
- boolean lambda$null$20(Pair,Map$Entry)
+ boolean lambda$predicate$11(Block,Map,BlockState)
- boolean lambda$predicate$12(Block,Map,BlockState)
+ ModelBakery$ModelGroupKey lambda$loadModel$14(ModelBakery$ModelGroupKey)
- ModelBakery$ModelGroupKey lambda$loadModel$15(ModelBakery$ModelGroupKey)
+ ModelBakery$ModelGroupKey lambda$null$16(BlockState,MultiPart,List)
- ModelBakery$ModelGroupKey lambda$null$17(BlockState,MultiPart,List)
+ ModelBakery$ModelGroupKey lambda$null$18(BlockState,MultiVariant,List)
- ModelBakery$ModelGroupKey lambda$null$19(BlockState,MultiVariant,List)
+ Pair lambda$loadModel$15(Resource)
- Pair lambda$loadModel$16(Resource)
- ResourceLocation lambda$static$1(ResourceLocation)
+ Set lambda$null$22(ModelBakery$ModelGroupKey)
- Set lambda$null$23(ModelBakery$ModelGroupKey)
+ StateDefinition lambda$loadModel$12(ResourceLocation)
- StateDefinition lambda$loadModel$13(ResourceLocation)
+ Stream lambda$new$8(Set,UnbakedModel)
- Stream lambda$new$9(Set,UnbakedModel)
+ void lambda$loadModel$13(Map,ResourceLocation,BlockState)
- void lambda$loadModel$14(Map,ResourceLocation,BlockState)
+ void lambda$loadModel$17(Map,MultiPart,List,BlockState)
- void lambda$loadModel$18(Map,MultiPart,List,BlockState)
+ void lambda$loadModel$21(ImmutableList,StateDefinition,Map,List,MultiPart,Pair,BlockModelDefinition,ResourceLocation,Pair,String,MultiVariant)
- void lambda$loadModel$22(ImmutableList,StateDefinition,Map,List,MultiPart,Pair,BlockModelDefinition,ResourceLocation,Pair,String,MultiVariant)
+ void lambda$loadModel$23(Map,ResourceLocation,Pair,Map,ModelResourceLocation,BlockState)
- void lambda$loadModel$24(Map,ResourceLocation,Pair,Map,ModelResourceLocation,BlockState)
+ void lambda$loadModel$24(ModelBakery$ModelGroupKey,Set)
- void lambda$loadModel$25(ModelBakery$ModelGroupKey,Set)
- void lambda$new$10(String)
+ void lambda$new$4(Object2IntOpenHashMap)
- void lambda$new$5(Object2IntOpenHashMap)
+ void lambda$new$6(ResourceLocation,StateDefinition)
+ void lambda$new$7(BlockState)
- void lambda$new$7(ResourceLocation,StateDefinition)
- void lambda$new$8(BlockState)
+ void lambda$new$9(String)
+ void lambda$null$20(Map,MultiVariant,List,MultiPart,Pair,BlockModelDefinition,BlockState)
- void lambda$null$21(Map,MultiVariant,List,MultiPart,Pair,BlockModelDefinition,BlockState)
+ void lambda$null$5(ResourceLocation,BlockState)
- void lambda$null$6(ResourceLocation,BlockState)
+ void lambda$registerModelGroup$25(int,BlockState)
- void lambda$registerModelGroup$26(int,BlockState)
+ void lambda$static$1(HashSet)
+ void lambda$static$2(BlockModel)
- void lambda$static$2(HashSet)
- void lambda$static$4(BlockModel)
+ void lambda$uploadTextures$10(ResourceLocation)
- void lambda$uploadTextures$11(ResourceLocation)
```

</details>
<details>
<summary>
net.minecraft.nbt.ByteTag
</summary>

```diff
- ByteTag valueOf(boolean)
- ByteTag valueOf(byte)
- TagType getType()
- void <clinit>()
+ void <init>()
- void <init>(byte,ByteTag$1)
+ void load(DataInput,int,NbtAccounter)
```

</details>
<details>
<summary>
net.minecraft.nbt.CompoundTag
</summary>

```diff
- byte access$000(DataInput,NbtAccounter)
+ CrashReport createReport(String,int,ClassCastException)
- CrashReport createReport(String,TagType,ClassCastException)
- String access$100(DataInput,NbtAccounter)
+ String lambda$createReport$1(int)
- Tag access$200(TagType,String,DataInput,int,NbtAccounter)
+ Tag readNamedTagData(byte,String,DataInput,int,NbtAccounter)
- Tag readNamedTagData(TagType,String,DataInput,int,NbtAccounter)
- TagType getType()
- void <init>(Map,CompoundTag$1)
- void <init>(Map)
+ void load(DataInput,int,NbtAccounter)
```

</details>
<details>
<summary>
net.minecraft.nbt.EndTag
</summary>

```diff
+ boolean equals(Object)
+ int hashCode()
- TagType getType()
- void <clinit>()
+ void load(DataInput,int,NbtAccounter)
```

</details>
<details>
<summary>
net.minecraft.nbt.IntArrayTag
</summary>

```diff
- TagType getType()
- void <clinit>()
+ void <init>()
+ void load(DataInput,int,NbtAccounter)
```

</details>
<details>
<summary>
net.minecraft.nbt.TagParser
</summary>

```diff
+ List readArray(byte,byte)
- List readArray(TagType,TagType)
```

</details>
<details>
<summary>
net.minecraft.realms.RealmsVertexFormat
</summary>

```diff
+ boolean hasColor()
+ boolean hasNormal()
+ boolean hasUv(int)
+ int getColorOffset()
+ int getElementCount()
+ int getIntegerSize()
+ int getNormalOffset()
+ int getOffset(int)
+ int getUvOffset(int)
+ int getVertexSize()
+ RealmsVertexFormatElement getElement(int)
```

</details>
<details>
<summary>
net.minecraft.realms.Tezzelator
</summary>

```diff
+ BufferBuilder color(int,int,int,int)
- Tezzelator color(int,int,int,int)
+ Tezzelator tex(double,double)
- Tezzelator tex(float,float)
+ void color(float,float,float,float)
+ void normal(float,float,float)
+ void offset(double,double,double)
+ void tex2(short,short)
```

</details>
<details>
<summary>
net.minecraft.server.level.BlockDestructionProgress
</summary>

```diff
- boolean equals(Object)
- int compareTo(BlockDestructionProgress)
- int compareTo(Object)
- int hashCode()
```

</details>
<details>
<summary>
net.minecraft.util.Mth
</summary>

```diff
- float fastInvSqrt(float)
- float rotlerp(float,float,float)
- float rotWrap(double)
```

</details>
<details>
<summary>
net.minecraft.world.entity.Entity
</summary>

```diff
- int getTeamColor()
- void setPosAndOldPos(double,double,double)
```

</details>
</details>
<hr/>