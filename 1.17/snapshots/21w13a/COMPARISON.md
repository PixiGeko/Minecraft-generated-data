## Comparison with [21w11a](https://github.com/PixiGeko/Minecraft-generated-data/tree/21w11a)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Blocks](#blocks)
> - [Translations](#translations)
> - [File structure](#file-structure)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">21w11a</th><th>21w13a</th></tr><tr><td>World version</td><td><pre>2703</pre></td><td><pre>2705</pre></td></tr><tr><td>Protocol version</td><td><pre>1073741843</pre></td><td><pre>1073741844</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">21w11a</th><th>21w13a</th></tr><tr><td>com.mojang:brigadier</td><td><pre>1.0.17</pre></td><td><pre>1.0.18</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr></table>
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
+ float_provider_type.txt
+ height_provider_type.txt
+ int_provider_type.txt
- worldgen/float_provider_type.txt
```

</details>
<details>
<summary>
activity
</summary>

```diff
+ minecraft:long_jump
```

</details>
<details>
<summary>
block
</summary>

```diff
+ minecraft:light
```

</details>
<details>
<summary>
entity_type
</summary>

```diff
+ minecraft:goat
```

</details>
<details>
<summary>
item
</summary>

```diff
+ minecraft:goat_spawn_egg
+ minecraft:light
```

</details>
<details>
<summary>
memory_module_type
</summary>

```diff
+ minecraft:has_hunting_cooldown
+ minecraft:long_jump_cooling_down
+ minecraft:long_jump_mid_jump
+ minecraft:nearest_attackable
```

</details>
<details>
<summary>
particle_type
</summary>

```diff
+ minecraft:light
```

</details>
<details>
<summary>
sensor_type
</summary>

```diff
+ minecraft:axolotl_attackables
- minecraft:axolotl_hostiles
+ minecraft:goat_temptations
```

</details>
<details>
<summary>
sound_event
</summary>

```diff
+ minecraft:entity.goat.ambient
+ minecraft:entity.goat.death
+ minecraft:entity.goat.hurt
+ minecraft:entity.goat.milk
+ minecraft:entity.goat.prepare_ram
+ minecraft:entity.goat.screaming.ambient
+ minecraft:entity.goat.screaming.death
+ minecraft:entity.goat.screaming.hurt
+ minecraft:entity.goat.screaming.milk
+ minecraft:entity.goat.screaming.ram
+ minecraft:entity.goat.step
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
+ universal_tags/float_provider_type.json
+ universal_tags/height_provider_type.json
+ universal_tags/int_provider_type.json
- universal_tags/worldgen/float_provider_type.json
```

</details>
<details>
<summary>
all_blocks_without_drop.json
</summary>

```diff
+ minecraft:light
```

</details>
<details>
<summary>
all_entities_without_drop.json
</summary>

```diff
+ minecraft:goat
```

</details>
<details>
<summary>
all_living_entities_without_drop.json
</summary>

```diff
+ minecraft:goat
```

</details>
<details>
<summary>
universal_tags/activity.json
</summary>

```diff
+ minecraft:long_jump
```

</details>
<details>
<summary>
universal_tags/block.json
</summary>

```diff
+ minecraft:light
```

</details>
<details>
<summary>
universal_tags/entity_type.json
</summary>

```diff
+ minecraft:goat
```

</details>
<details>
<summary>
universal_tags/item.json
</summary>

```diff
+ minecraft:goat_spawn_egg
+ minecraft:light
```

</details>
<details>
<summary>
universal_tags/memory_module_type.json
</summary>

```diff
+ minecraft:has_hunting_cooldown
+ minecraft:long_jump_cooling_down
+ minecraft:long_jump_mid_jump
+ minecraft:nearest_attackable
```

</details>
<details>
<summary>
universal_tags/particle_type.json
</summary>

```diff
+ minecraft:light
```

</details>
<details>
<summary>
universal_tags/sensor_type.json
</summary>

```diff
+ minecraft:axolotl_attackables
- minecraft:axolotl_hostiles
+ minecraft:goat_temptations
```

</details>
<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:entity.goat.ambient
+ minecraft:entity.goat.death
+ minecraft:entity.goat.hurt
+ minecraft:entity.goat.milk
+ minecraft:entity.goat.prepare_ram
+ minecraft:entity.goat.screaming.ambient
+ minecraft:entity.goat.screaming.death
+ minecraft:entity.goat.screaming.hurt
+ minecraft:entity.goat.screaming.milk
+ minecraft:entity.goat.screaming.ram
+ minecraft:entity.goat.step
```

</details>
</details>
<hr/>
<details><summary><b><ins>BLOCKS</ins></b><a name="blocks"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
+ light.json
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
+ block.minecraft.light: Light
+ entity.minecraft.goat: Goat
+ item.minecraft.goat_spawn_egg: Goat Spawn Egg
+ options.darkMojangStudiosBackgroundColor: Monochrome Logo
+ options.darkMojangStudiosBackgroundColor.tooltip: Changes the Mojang Studios loading screen background color to black.
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>21w11a</th><th>21w13a</th></tr>
<tr><th align="left"><div style="width:290px">build.tooHigh</div></th><td>Height limit for building is %s blocks</td><td>Height limit for building is %s</td></tr>
<tr><th align="left"><div style="width:290px">advancements.story.shiny_gear.title</div></th><td>Cover Me With Diamonds</td><td>Cover Me with Diamonds</td></tr>
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
+ minecraft/loot_tables/entities/goat.json
+ minecraft/tags/blocks/dirt.json
+ minecraft/tags/blocks/snow.json
+ minecraft/tags/entity_types/axolotl_hunt_targets.json
- minecraft/tags/entity_types/axolotl_tempted_hostiles.json
+ minecraft/tags/entity_types/freeze_hurts_extra_types.json
+ minecraft/tags/entity_types/freeze_immune_entity_types.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/blockstates/light.json
+ minecraft/models/block/light.json
+ minecraft/models/item/goat_spawn_egg.json
+ minecraft/models/item/light_00.json
+ minecraft/models/item/light_01.json
+ minecraft/models/item/light_02.json
+ minecraft/models/item/light_03.json
+ minecraft/models/item/light_04.json
+ minecraft/models/item/light_05.json
+ minecraft/models/item/light_06.json
+ minecraft/models/item/light_07.json
+ minecraft/models/item/light_08.json
+ minecraft/models/item/light_09.json
+ minecraft/models/item/light_10.json
+ minecraft/models/item/light_11.json
+ minecraft/models/item/light_12.json
+ minecraft/models/item/light_13.json
+ minecraft/models/item/light_14.json
+ minecraft/models/item/light_15.json
+ minecraft/models/item/light.json
+ minecraft/particles/light.json
- minecraft/textures/block/calibrated_sculk_sensor_side.png
- minecraft/textures/block/calibrated_sculk_sensor_top.png
- minecraft/textures/entity/arrow.png
+ minecraft/textures/entity/goat/goat.png
- minecraft/textures/entity/zombie/zombie_villager.png
+ minecraft/textures/item/light_00.png
+ minecraft/textures/item/light_01.png
+ minecraft/textures/item/light_02.png
+ minecraft/textures/item/light_03.png
+ minecraft/textures/item/light_04.png
+ minecraft/textures/item/light_05.png
+ minecraft/textures/item/light_06.png
+ minecraft/textures/item/light_07.png
+ minecraft/textures/item/light_08.png
+ minecraft/textures/item/light_09.png
+ minecraft/textures/item/light_10.png
+ minecraft/textures/item/light_11.png
+ minecraft/textures/item/light_12.png
+ minecraft/textures/item/light_13.png
+ minecraft/textures/item/light_14.png
+ minecraft/textures/item/light_15.png
+ minecraft/textures/item/light.png
- minecraft/textures/item/ruby.png
- minecraft/textures/models/armor/piglin_leather_layer_1_overlay.png
- minecraft/textures/models/armor/piglin_leather_layer_1.png
- minecraft/textures/particle/footprint.png
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
- net.minecraft.BlockUtil
+ net.minecraft.BlockUtil$FoundRectangle
- net.minecraft.BlockUtil$IntBounds
+ net.minecraft.CharPredicate
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
+ net.minecraft.Util$4
- net.minecraft.Util$5
+ net.minecraft.Util$6
- net.minecraft.Util$7
+ net.minecraft.Util$8
- net.minecraft.Util$9
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
- XXX.advancements.critereon.PlayerInteractTrigger
+ XXX.advancements.critereon.PlayerInteractTrigger$TriggerInstance
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
- XXX.ai.behavior.CountDownCooldownTicks
+ XXX.ai.behavior.CrossbowAttack
- XXX.ai.behavior.CrossbowAttack$CrossbowState
+ XXX.ai.behavior.DismountOrSkipMounting
- XXX.ai.behavior.DoNothing
+ XXX.ai.behavior.EntityTracker
- XXX.ai.behavior.EraseMemoryIf
+ XXX.ai.behavior.FollowTemptation
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
- XXX.ai.behavior.LongJumpToRandomPos
- XXX.ai.behavior.ShufflingList
- XXX.ai.behavior.ShufflingList$WeightedEntry
+ XXX.ai.behavior.WeightedList
+ XXX.ai.behavior.WeightedList$WeightedEntry
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
+ XXX.ai.goal.TemptGoal
- XXX.ai.goal.TradeWithPlayerGoal
+ XXX.ai.goal.TryFindWaterGoal
- XXX.ai.goal.UseItemGoal
+ XXX.ai.goal.WaterAvoidingRandomFlyingGoal
- XXX.ai.goal.WaterAvoidingRandomStrollGoal
+ XXX.ai.goal.WrappedGoal
- XXX.ai.goal.ZombieAttackGoal
+ XXX.ai.gossip.GossipContainer
- XXX.ai.gossip.GossipContainer$1
+ XXX.ai.gossip.GossipContainer$EntityGossips
- XXX.ai.gossip.GossipContainer$GossipEntry
+ XXX.ai.gossip.GossipType
- XXX.ai.gossip.package-info
+ XXX.ai.memory.ExpirableValue
- XXX.ai.memory.MemoryModuleType
+ XXX.ai.memory.MemoryStatus
+ XXX.ai.memory.package-info
- XXX.ai.memory.WalkTarget
- XXX.ai.navigation.FlyingPathNavigation
+ XXX.ai.navigation.GroundPathNavigation
+ XXX.ai.navigation.package-info
- XXX.ai.navigation.PathNavigation
+ XXX.ai.navigation.WallClimberNavigation
- XXX.ai.navigation.WaterBoundPathNavigation
+ XXX.ai.sensing.AdultSensor
- XXX.ai.sensing.AxolotlAttackablesSensor
+ XXX.ai.sensing.DummySensor
- XXX.ai.sensing.GolemSensor
+ XXX.ai.sensing.HoglinSpecificSensor
- XXX.ai.sensing.NearestVisibleLivingEntitySensor
+ XXX.ai.sensing.package-info
+ XXX.ai.sensing.PiglinBruteSpecificSensor
- XXX.ai.sensing.PiglinSpecificSensor
+ XXX.ai.sensing.PlayerSensor
- XXX.ai.sensing.SecondaryPoiSensor
+ XXX.ai.sensing.Sensing
- XXX.ai.sensing.Sensor
+ XXX.ai.sensing.SensorType
- XXX.ai.sensing.TemptingSensor
+ XXX.ai.sensing.VillagerBabiesSensor
- XXX.ai.sensing.VillagerHostilesSensor
+ XXX.ai.targeting.package-info
- XXX.ai.targeting.TargetingConditions
- XXX.ai.util.AirAndWaterRandomPos
+ XXX.ai.util.AirRandomPos
- XXX.ai.util.DefaultRandomPos
+ XXX.ai.util.GoalUtils
- XXX.ai.util.HoverRandomPos
+ XXX.ai.util.LandRandomPos
+ XXX.ai.util.package-info
- XXX.ai.util.RandomPos
- XXX.ai.village.package-info
- XXX.ai.village.ReputationEventType
+ XXX.ai.village.ReputationEventType$1
- XXX.ai.village.VillageSiege
+ XXX.ai.village.VillageSiege$State
- XXX.animal.axolotl.Axolotl
+ XXX.animal.axolotl.Axolotl$AxolotlGroupData
- XXX.animal.axolotl.Axolotl$AxolotlLookControl
+ XXX.animal.axolotl.Axolotl$AxolotlMoveControl
- XXX.animal.axolotl.Axolotl$AxolotlPathNavigation
+ XXX.animal.axolotl.Axolotl$Variant
- XXX.animal.axolotl.AxolotlAi
+ XXX.animal.axolotl.package-info
+ XXX.animal.axolotl.PlayDead
- XXX.animal.axolotl.ValidatePlayDead
- XXX.animal.goat.Goat
- XXX.animal.goat.package-info
+ XXX.arguments.blocks.BlockInput
- XXX.arguments.blocks.BlockPredicateArgument
+ XXX.arguments.blocks.BlockPredicateArgument$1
- XXX.arguments.blocks.BlockPredicateArgument$BlockPredicate
+ XXX.arguments.blocks.BlockPredicateArgument$Result
- XXX.arguments.blocks.BlockPredicateArgument$TagPredicate
+ XXX.arguments.blocks.BlockStateArgument
- XXX.arguments.blocks.BlockStateParser
+ XXX.arguments.blocks.package-info
- XXX.arguments.coordinates.BlockPosArgument
+ XXX.arguments.coordinates.ColumnPosArgument
- XXX.arguments.coordinates.Coordinates
+ XXX.arguments.coordinates.LocalCoordinates
- XXX.arguments.coordinates.package-info
- XXX.arguments.coordinates.RotationArgument
+ XXX.arguments.coordinates.SwizzleArgument
- XXX.arguments.coordinates.Vec2Argument
+ XXX.arguments.coordinates.Vec3Argument
- XXX.arguments.coordinates.WorldCoordinate
+ XXX.arguments.coordinates.WorldCoordinates
+ XXX.arguments.item.FunctionArgument
- XXX.arguments.item.FunctionArgument$1
+ XXX.arguments.item.FunctionArgument$2
- XXX.arguments.item.FunctionArgument$Result
+ XXX.arguments.item.ItemArgument
- XXX.arguments.item.ItemInput
+ XXX.arguments.item.ItemParser
- XXX.arguments.item.ItemPredicateArgument
+ XXX.arguments.item.ItemPredicateArgument$ItemPredicate
- XXX.arguments.item.ItemPredicateArgument$Result
+ XXX.arguments.item.ItemPredicateArgument$TagPredicate
- XXX.arguments.item.package-info
- XXX.arguments.selector.EntitySelector
+ XXX.arguments.selector.EntitySelector$1
- XXX.arguments.selector.EntitySelectorParser
- XXX.arguments.selector.package-info
+ XXX.block.entity.AbstractFurnaceBlockEntity
- XXX.block.entity.AbstractFurnaceBlockEntity$1
+ XXX.block.entity.BannerBlockEntity
- XXX.block.entity.BannerPattern
+ XXX.block.entity.BannerPattern$Builder
- XXX.block.entity.BarrelBlockEntity
+ XXX.block.entity.BarrelBlockEntity$1
- XXX.block.entity.BaseContainerBlockEntity
+ XXX.block.entity.BeaconBlockEntity
- XXX.block.entity.BeaconBlockEntity$1
+ XXX.block.entity.BeaconBlockEntity$BeaconBeamSection
- XXX.block.entity.BedBlockEntity
+ XXX.block.entity.BeehiveBlockEntity
- XXX.block.entity.BeehiveBlockEntity$1
+ XXX.block.entity.BeehiveBlockEntity$BeeData
- XXX.block.entity.BeehiveBlockEntity$BeeReleaseStatus
+ XXX.block.entity.BellBlockEntity
- XXX.block.entity.BellBlockEntity$ResonationEndAction
+ XXX.block.entity.BlastFurnaceBlockEntity
- XXX.block.entity.BlockEntity
+ XXX.block.entity.BlockEntityTicker
- XXX.block.entity.BlockEntityType
+ XXX.block.entity.BlockEntityType$BlockEntitySupplier
- XXX.block.entity.BlockEntityType$Builder
+ XXX.block.entity.BrewingStandBlockEntity
- XXX.block.entity.BrewingStandBlockEntity$1
+ XXX.block.entity.CampfireBlockEntity
- XXX.block.entity.ChestBlockEntity
+ XXX.block.entity.ChestBlockEntity$1
- XXX.block.entity.ChestLidController
+ XXX.block.entity.CommandBlockEntity
- XXX.block.entity.CommandBlockEntity$1
+ XXX.block.entity.CommandBlockEntity$Mode
- XXX.block.entity.ComparatorBlockEntity
+ XXX.block.entity.ConduitBlockEntity
- XXX.block.entity.ContainerOpenersCounter
+ XXX.block.entity.DaylightDetectorBlockEntity
- XXX.block.entity.DispenserBlockEntity
+ XXX.block.entity.DropperBlockEntity
- XXX.block.entity.EnchantmentTableBlockEntity
+ XXX.block.entity.EnderChestBlockEntity
- XXX.block.entity.EnderChestBlockEntity$1
+ XXX.block.entity.FurnaceBlockEntity
- XXX.block.entity.Hopper
+ XXX.block.entity.HopperBlockEntity
- XXX.block.entity.JigsawBlockEntity
+ XXX.block.entity.JigsawBlockEntity$JointType
- XXX.block.entity.JukeboxBlockEntity
+ XXX.block.entity.LecternBlockEntity
- XXX.block.entity.LecternBlockEntity$1
+ XXX.block.entity.LecternBlockEntity$2
- XXX.block.entity.LidBlockEntity
+ XXX.block.entity.package-info
+ XXX.block.entity.RandomizableContainerBlockEntity
- XXX.block.entity.SculkSensorBlockEntity
+ XXX.block.entity.ShulkerBoxBlockEntity
- XXX.block.entity.ShulkerBoxBlockEntity$1
+ XXX.block.entity.ShulkerBoxBlockEntity$AnimationStatus
- XXX.block.entity.SignBlockEntity
+ XXX.block.entity.SkullBlockEntity
- XXX.block.entity.SmokerBlockEntity
+ XXX.block.entity.SpawnerBlockEntity
- XXX.block.entity.SpawnerBlockEntity$1
+ XXX.block.entity.StructureBlockEntity
- XXX.block.entity.StructureBlockEntity$UpdateType
+ XXX.block.entity.TheEndGatewayBlockEntity
- XXX.block.entity.TheEndPortalBlockEntity
+ XXX.block.entity.TickingBlockEntity
- XXX.block.entity.TrappedChestBlockEntity
- XXX.block.grower.AbstractMegaTreeGrower
+ XXX.block.grower.AbstractTreeGrower
- XXX.block.grower.AcaciaTreeGrower
+ XXX.block.grower.BirchTreeGrower
- XXX.block.grower.DarkOakTreeGrower
+ XXX.block.grower.JungleTreeGrower
- XXX.block.grower.OakTreeGrower
- XXX.block.grower.package-info
+ XXX.block.grower.SpruceTreeGrower
- XXX.block.piston.MovingPistonBlock
- XXX.block.piston.package-info
+ XXX.block.piston.PistonBaseBlock
- XXX.block.piston.PistonBaseBlock$1
+ XXX.block.piston.PistonHeadBlock
- XXX.block.piston.PistonHeadBlock$1
+ XXX.block.piston.PistonMath
- XXX.block.piston.PistonMath$1
+ XXX.block.piston.PistonMovingBlockEntity
- XXX.block.piston.PistonMovingBlockEntity$1
+ XXX.block.piston.PistonStructureResolver
+ XXX.block.state.BlockBehaviour
- XXX.block.state.BlockBehaviour$1
+ XXX.block.state.BlockBehaviour$BlockStateBase
- XXX.block.state.BlockBehaviour$BlockStateBase$Cache
+ XXX.block.state.BlockBehaviour$OffsetType
- XXX.block.state.BlockBehaviour$Properties
+ XXX.block.state.BlockBehaviour$StateArgumentPredicate
- XXX.block.state.BlockBehaviour$StatePredicate
+ XXX.block.state.BlockState
+ XXX.block.state.package-info
- XXX.block.state.StateDefinition
+ XXX.block.state.StateDefinition$Builder
- XXX.block.state.StateDefinition$Factory
+ XXX.block.state.StateHolder
- XXX.block.state.StateHolder$1
+ XXX.chunk.storage.ChunkSerializer
- XXX.chunk.storage.ChunkStorage
+ XXX.chunk.storage.EntityStorage
- XXX.chunk.storage.IOWorker
+ XXX.chunk.storage.IOWorker$PendingStore
- XXX.chunk.storage.IOWorker$Priority
+ XXX.chunk.storage.OldChunkStorage
- XXX.chunk.storage.OldChunkStorage$1
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
- XXX.commands.arguments.AngleArgument
+ XXX.commands.arguments.AngleArgument$1
- XXX.commands.arguments.AngleArgument$SingleAngle
+ XXX.commands.arguments.ColorArgument
- XXX.commands.arguments.ComponentArgument
+ XXX.commands.arguments.CompoundTagArgument
- XXX.commands.arguments.DimensionArgument
+ XXX.commands.arguments.EntityAnchorArgument
- XXX.commands.arguments.EntityAnchorArgument$Anchor
+ XXX.commands.arguments.EntityArgument
- XXX.commands.arguments.EntityArgument$Serializer
+ XXX.commands.arguments.EntitySummonArgument
- XXX.commands.arguments.GameProfileArgument
+ XXX.commands.arguments.GameProfileArgument$Result
- XXX.commands.arguments.GameProfileArgument$SelectorResult
+ XXX.commands.arguments.ItemEnchantmentArgument
- XXX.commands.arguments.MessageArgument
+ XXX.commands.arguments.MessageArgument$Message
- XXX.commands.arguments.MessageArgument$Part
+ XXX.commands.arguments.MobEffectArgument
- XXX.commands.arguments.NbtPathArgument
+ XXX.commands.arguments.NbtPathArgument$AllElementsNode
- XXX.commands.arguments.NbtPathArgument$CompoundChildNode
+ XXX.commands.arguments.NbtPathArgument$IndexedElementNode
- XXX.commands.arguments.NbtPathArgument$MatchElementNode
+ XXX.commands.arguments.NbtPathArgument$MatchObjectNode
- XXX.commands.arguments.NbtPathArgument$MatchRootObjectNode
+ XXX.commands.arguments.NbtPathArgument$NbtPath
- XXX.commands.arguments.NbtPathArgument$Node
+ XXX.commands.arguments.NbtTagArgument
- XXX.commands.arguments.ObjectiveArgument
+ XXX.commands.arguments.ObjectiveCriteriaArgument
- XXX.commands.arguments.OperationArgument
+ XXX.commands.arguments.OperationArgument$Operation
- XXX.commands.arguments.OperationArgument$SimpleOperation
+ XXX.commands.arguments.package-info
+ XXX.commands.arguments.ParticleArgument
- XXX.commands.arguments.RangeArgument
+ XXX.commands.arguments.RangeArgument$Floats
- XXX.commands.arguments.RangeArgument$Ints
+ XXX.commands.arguments.ResourceLocationArgument
- XXX.commands.arguments.ScoreboardSlotArgument
- XXX.commands.arguments.ScoreHolderArgument
+ XXX.commands.arguments.ScoreHolderArgument$Result
- XXX.commands.arguments.ScoreHolderArgument$SelectorResult
+ XXX.commands.arguments.ScoreHolderArgument$Serializer
+ XXX.commands.arguments.SlotArgument
- XXX.commands.arguments.TeamArgument
+ XXX.commands.arguments.TimeArgument
- XXX.commands.arguments.UuidArgument
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
+ XXX.commands.exceptions.package-info
+ XXX.datafix.fixes.AbstractArrowPickupFix
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
- XXX.datafix.fixes.CauldronRenameFix
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
+ XXX.datafix.fixes.MobSpawnerEntityIdentifiersFix
- XXX.datafix.fixes.NamedEntityFix
+ XXX.datafix.fixes.NewVillageFix
- XXX.datafix.fixes.ObjectiveDisplayNameFix
+ XXX.datafix.fixes.ObjectiveRenderTypeFix
- XXX.datafix.fixes.OminousBannerBlockEntityRenameFix
+ XXX.datafix.fixes.OminousBannerRenameFix
- XXX.datafix.fixes.OptionsAddTextBackgroundFix
+ XXX.datafix.fixes.OptionsForceVBOFix
- XXX.datafix.fixes.OptionsKeyLwjgl3Fix
+ XXX.datafix.fixes.OptionsKeyTranslationFix
- XXX.datafix.fixes.OptionsLowerCaseLanguageFix
+ XXX.datafix.fixes.OptionsRenameFieldFix
+ XXX.datafix.fixes.package-info
- XXX.datafix.fixes.PlayerUUIDFix
+ XXX.datafix.fixes.PoiTypeRename
- XXX.datafix.fixes.RecipesFix
+ XXX.datafix.fixes.RecipesRenameFix
- XXX.datafix.fixes.RecipesRenameningFix
+ XXX.datafix.fixes.RedstoneWireConnectionsFix
- XXX.datafix.fixes.References
+ XXX.datafix.fixes.RemoveGolemGossipFix
- XXX.datafix.fixes.RenameBiomesFix
+ XXX.datafix.fixes.RenamedCoralFansFix
- XXX.datafix.fixes.RenamedCoralFix
+ XXX.datafix.fixes.ReorganizePoi
- XXX.datafix.fixes.SavedDataFeaturePoolElementFix
+ XXX.datafix.fixes.SavedDataUUIDFix
- XXX.datafix.fixes.SavedDataVillageCropFix
+ XXX.datafix.fixes.SimpleEntityRenameFix
- XXX.datafix.fixes.SimplestEntityRenameFix
+ XXX.datafix.fixes.StatsCounterFix
- XXX.datafix.fixes.StriderGravityFix
+ XXX.datafix.fixes.StructureReferenceCountFix
- XXX.datafix.fixes.SwimStatsRenameFix
+ XXX.datafix.fixes.TeamDisplayNameFix
- XXX.datafix.fixes.TrappedChestBlockEntityFix
+ XXX.datafix.fixes.TrappedChestBlockEntityFix$TrappedChestSection
- XXX.datafix.fixes.VillagerDataFix
+ XXX.datafix.fixes.VillagerFollowRangeFix
- XXX.datafix.fixes.VillagerRebuildLevelAndXpFix
+ XXX.datafix.fixes.VillagerTradeFix
- XXX.datafix.fixes.WallPropertyFix
+ XXX.datafix.fixes.WorldGenSettingsFix
- XXX.datafix.fixes.WorldGenSettingsFix$StructureFeatureConfiguration
+ XXX.datafix.fixes.WriteAndReadFix
- XXX.datafix.fixes.ZombieVillagerRebuildXpFix
+ XXX.datafix.schemas.NamespacedSchema
- XXX.datafix.schemas.NamespacedSchema$1
- XXX.datafix.schemas.package-info
+ XXX.datafix.schemas.V100
- XXX.datafix.schemas.V102
+ XXX.datafix.schemas.V1022
- XXX.datafix.schemas.V106
+ XXX.datafix.schemas.V107
- XXX.datafix.schemas.V1125
+ XXX.datafix.schemas.V135
- XXX.datafix.schemas.V143
+ XXX.datafix.schemas.V1451
- XXX.datafix.schemas.V1451_1
+ XXX.datafix.schemas.V1451_2
- XXX.datafix.schemas.V1451_3
+ XXX.datafix.schemas.V1451_4
- XXX.datafix.schemas.V1451_5
+ XXX.datafix.schemas.V1451_6
- XXX.datafix.schemas.V1451_7
+ XXX.datafix.schemas.V1460
- XXX.datafix.schemas.V1460$1
+ XXX.datafix.schemas.V1466
- XXX.datafix.schemas.V1470
+ XXX.datafix.schemas.V1481
- XXX.datafix.schemas.V1483
+ XXX.datafix.schemas.V1486
- XXX.datafix.schemas.V1510
+ XXX.datafix.schemas.V1800
- XXX.datafix.schemas.V1801
+ XXX.datafix.schemas.V1904
- XXX.datafix.schemas.V1906
+ XXX.datafix.schemas.V1909
- XXX.datafix.schemas.V1920
+ XXX.datafix.schemas.V1928
- XXX.datafix.schemas.V1929
+ XXX.datafix.schemas.V1931
- XXX.datafix.schemas.V2100
+ XXX.datafix.schemas.V2501
- XXX.datafix.schemas.V2502
+ XXX.datafix.schemas.V2505
- XXX.datafix.schemas.V2509
+ XXX.datafix.schemas.V2519
- XXX.datafix.schemas.V2522
+ XXX.datafix.schemas.V2551
- XXX.datafix.schemas.V2568
- XXX.datafix.schemas.V501
+ XXX.datafix.schemas.V700
- XXX.datafix.schemas.V701
+ XXX.datafix.schemas.V702
- XXX.datafix.schemas.V703
+ XXX.datafix.schemas.V704
- XXX.datafix.schemas.V704$1
+ XXX.datafix.schemas.V705
- XXX.datafix.schemas.V705$1
+ XXX.datafix.schemas.V808
- XXX.datafix.schemas.V99
+ XXX.datafix.schemas.V99$1
- XXX.entity.ai.package-info
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
- XXX.entity.animal.Bee$BeeGoToHiveGoal
+ XXX.entity.animal.Bee$BeeGoToKnownFlowerGoal
- XXX.entity.animal.Bee$BeeGrowCropGoal
+ XXX.entity.animal.Bee$BeeHurtByOtherGoal
- XXX.entity.animal.Bee$BeeLocateHiveGoal
+ XXX.entity.animal.Bee$BeeLookControl
- XXX.entity.animal.Bee$BeePollinateGoal
+ XXX.entity.animal.Bee$BeeWanderGoal
- XXX.entity.animal.Bucketable
+ XXX.entity.animal.Cat
- XXX.entity.animal.Cat$CatAvoidEntityGoal
+ XXX.entity.animal.Cat$CatRelaxOnOwnerGoal
- XXX.entity.animal.Cat$CatTemptGoal
+ XXX.entity.animal.Chicken
- XXX.entity.animal.Cod
+ XXX.entity.animal.Cow
- XXX.entity.animal.Dolphin
+ XXX.entity.animal.Dolphin$1
- XXX.entity.animal.Dolphin$DolphinSwimToTreasureGoal
+ XXX.entity.animal.Dolphin$DolphinSwimWithPlayerGoal
- XXX.entity.animal.Dolphin$PlayWithItemsGoal
+ XXX.entity.animal.FlyingAnimal
- XXX.entity.animal.Fox
+ XXX.entity.animal.Fox$1
- XXX.entity.animal.Fox$DefendTrustedTargetGoal
+ XXX.entity.animal.Fox$FaceplantGoal
- XXX.entity.animal.Fox$FoxAlertableEntitiesSelector
+ XXX.entity.animal.Fox$FoxBehaviorGoal
- XXX.entity.animal.Fox$FoxBreedGoal
+ XXX.entity.animal.Fox$FoxEatBerriesGoal
- XXX.entity.animal.Fox$FoxFloatGoal
+ XXX.entity.animal.Fox$FoxFollowParentGoal
- XXX.entity.animal.Fox$FoxGroupData
+ XXX.entity.animal.Fox$FoxLookAtPlayerGoal
- XXX.entity.animal.Fox$FoxLookControl
+ XXX.entity.animal.Fox$FoxMeleeAttackGoal
- XXX.entity.animal.Fox$FoxMoveControl
+ XXX.entity.animal.Fox$FoxPanicGoal
- XXX.entity.animal.Fox$FoxPounceGoal
+ XXX.entity.animal.Fox$FoxSearchForItemsGoal
- XXX.entity.animal.Fox$FoxStrollThroughVillageGoal
+ XXX.entity.animal.Fox$PerchAndSearchGoal
- XXX.entity.animal.Fox$SeekShelterGoal
+ XXX.entity.animal.Fox$SleepGoal
- XXX.entity.animal.Fox$StalkPreyGoal
+ XXX.entity.animal.Fox$Type
- XXX.entity.animal.IronGolem
+ XXX.entity.animal.IronGolem$Crackiness
- XXX.entity.animal.MushroomCow
+ XXX.entity.animal.MushroomCow$MushroomType
- XXX.entity.animal.Ocelot
+ XXX.entity.animal.Ocelot$OcelotAvoidEntityGoal
- XXX.entity.animal.Ocelot$OcelotTemptGoal
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
- XXX.entity.animal.Turtle$TurtleTravelGoal
+ XXX.entity.animal.WaterAnimal
- XXX.entity.animal.Wolf
+ XXX.entity.animal.Wolf$WolfAvoidEntityGoal
- XXX.goal.target.DefendVillageTargetGoal
+ XXX.goal.target.HurtByTargetGoal
- XXX.goal.target.NearestAttackableTargetGoal
+ XXX.goal.target.NearestAttackableWitchTargetGoal
- XXX.goal.target.NearestHealableRaiderTargetGoal
+ XXX.goal.target.NonTameRandomTargetGoal
- XXX.goal.target.OwnerHurtByTargetGoal
+ XXX.goal.target.OwnerHurtTargetGoal
- XXX.goal.target.package-info
- XXX.goal.target.ResetUniversalAngerTargetGoal
+ XXX.goal.target.TargetGoal
- XXX.level.block.LightBlock
+ XXX.level.block.LightningRodBlock
- XXX.level.block.LiquidBlock
+ XXX.level.block.LiquidBlockContainer
- XXX.level.block.LoomBlock
+ XXX.level.block.MagmaBlock
- XXX.level.block.MelonBlock
+ XXX.level.block.Mirror
- XXX.level.block.Mirror$1
+ XXX.level.block.MossBlock
- XXX.level.block.MultifaceBlock
+ XXX.level.block.MushroomBlock
- XXX.level.block.MyceliumBlock
+ XXX.level.block.NetherPortalBlock
- XXX.level.block.NetherPortalBlock$1
- XXX.level.block.NetherrackBlock
+ XXX.level.block.NetherSproutsBlock
- XXX.level.block.NetherVines
+ XXX.level.block.NetherWartBlock
+ XXX.level.block.NoteBlock
- XXX.level.block.NyliumBlock
+ XXX.level.block.ObserverBlock
- XXX.level.block.OreBlock
+ XXX.level.block.package-info
+ XXX.level.block.PipeBlock
- XXX.level.block.PlayerHeadBlock
+ XXX.level.block.PlayerWallHeadBlock
- XXX.level.block.PointedDripstoneBlock
+ XXX.level.block.PotatoBlock
- XXX.level.block.PowderSnowBlock
+ XXX.level.block.PoweredBlock
- XXX.level.block.PoweredRailBlock
+ XXX.level.block.PoweredRailBlock$1
- XXX.level.block.PressurePlateBlock
+ XXX.level.block.PressurePlateBlock$1
- XXX.level.block.PressurePlateBlock$Sensitivity
+ XXX.level.block.PumpkinBlock
- XXX.level.block.RailBlock
+ XXX.level.block.RailBlock$1
- XXX.level.block.RailState
+ XXX.level.block.RailState$1
+ XXX.level.block.RedstoneLampBlock
- XXX.level.block.RedStoneOreBlock
- XXX.level.block.RedstoneTorchBlock
+ XXX.level.block.RedstoneTorchBlock$Toggle
- XXX.level.block.RedstoneWallTorchBlock
+ XXX.level.block.RedStoneWireBlock
- XXX.level.block.RedStoneWireBlock$1
+ XXX.level.block.RenderShape
- XXX.level.block.RepeaterBlock
+ XXX.level.block.RespawnAnchorBlock
- XXX.level.block.RespawnAnchorBlock$1
+ XXX.level.block.RodBlock
- XXX.level.block.RodBlock$1
+ XXX.level.block.RootedDirtBlock
- XXX.level.block.RootsBlock
+ XXX.level.block.RotatedPillarBlock
- XXX.level.block.RotatedPillarBlock$1
+ XXX.level.block.Rotation
- XXX.level.block.Rotation$1
+ XXX.level.block.SandBlock
- XXX.level.block.SaplingBlock
+ XXX.level.block.ScaffoldingBlock
- XXX.level.block.SculkSensorBlock
- XXX.level.block.SeagrassBlock
+ XXX.level.block.SeaPickleBlock
+ XXX.level.block.ShulkerBoxBlock
- XXX.level.block.ShulkerBoxBlock$1
+ XXX.level.block.SignBlock
- XXX.level.block.SimpleWaterloggedBlock
+ XXX.level.block.SkullBlock
- XXX.level.block.SkullBlock$Type
+ XXX.level.block.SkullBlock$Types
- XXX.level.block.SlabBlock
+ XXX.level.block.SlabBlock$1
- XXX.level.block.SlimeBlock
+ XXX.level.block.SmallDripleafBlock
- XXX.level.block.SmithingTableBlock
+ XXX.level.block.SmokerBlock
- XXX.level.block.SnowLayerBlock
+ XXX.level.block.SnowLayerBlock$1
- XXX.level.block.SnowyDirtBlock
+ XXX.level.block.SoulFireBlock
- XXX.level.block.SoulSandBlock
+ XXX.level.block.SoundType
- XXX.level.block.SpawnerBlock
+ XXX.level.block.SpongeBlock
- XXX.level.block.SporeBlossomBlock
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
+ XXX.level.block.SupportType
- XXX.level.block.SupportType$1
+ XXX.level.block.SupportType$2
- XXX.level.block.SupportType$3
+ XXX.level.block.SweetBerryBushBlock
- XXX.level.block.TallFlowerBlock
+ XXX.level.block.TallGrassBlock
- XXX.level.block.TallSeagrassBlock
+ XXX.level.block.TargetBlock
- XXX.level.block.TintedGlassBlock
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
+ XXX.level.block.TwistingVinesBlock
- XXX.level.block.TwistingVinesPlantBlock
+ XXX.level.block.VineBlock
- XXX.level.block.VineBlock$1
+ XXX.level.block.WallBannerBlock
- XXX.level.block.WallBlock
+ XXX.level.block.WallBlock$1
- XXX.level.block.WallSignBlock
+ XXX.level.block.WallSkullBlock
- XXX.level.block.WallTorchBlock
+ XXX.level.block.WaterlilyBlock
- XXX.level.block.WeatheringCopper
+ XXX.level.block.WeatheringCopper$WeatherState
- XXX.level.block.WeatheringCopperFullBlock
+ XXX.level.block.WeatheringCopperSlabBlock
- XXX.level.block.WeatheringCopperStairBlock
+ XXX.level.block.WebBlock
- XXX.level.block.WeepingVinesBlock
+ XXX.level.block.WeepingVinesPlantBlock
- XXX.level.block.WeightedPressurePlateBlock
+ XXX.level.block.WetSpongeBlock
- XXX.level.block.WitherRoseBlock
+ XXX.level.block.WitherSkullBlock
- XXX.level.block.WitherWallSkullBlock
+ XXX.level.block.WoodButtonBlock
- XXX.level.block.WoolCarpetBlock
+ XXX.level.border.BorderChangeListener
- XXX.level.border.BorderChangeListener$DelegateBorderChangeListener
+ XXX.level.border.BorderStatus
- XXX.level.border.package-info
- XXX.level.border.WorldBorder
+ XXX.level.border.WorldBorder$1
- XXX.level.border.WorldBorder$BorderExtent
+ XXX.level.border.WorldBorder$MovingBorderExtent
- XXX.level.border.WorldBorder$Settings
+ XXX.level.border.WorldBorder$StaticBorderExtent
+ XXX.level.chunk.BulkSectionAccess
- XXX.level.chunk.ChunkAccess
+ XXX.level.chunk.ChunkBiomeContainer
- XXX.level.chunk.ChunkGenerator
+ XXX.level.chunk.ChunkSource
- XXX.level.chunk.ChunkStatus
+ XXX.level.chunk.ChunkStatus$ChunkType
- XXX.level.chunk.ChunkStatus$GenerationTask
+ XXX.level.chunk.ChunkStatus$LoadingTask
- XXX.level.chunk.ChunkStatus$SimpleGenerationTask
+ XXX.level.chunk.DataLayer
- XXX.level.chunk.EmptyLevelChunk
+ XXX.level.chunk.EmptyLevelChunk$EmptyChunkBiomeContainer
- XXX.level.chunk.FeatureAccess
+ XXX.level.chunk.GlobalPalette
- XXX.level.chunk.HashMapPalette
+ XXX.level.chunk.ImposterProtoChunk
- XXX.level.chunk.LevelChunk
+ XXX.level.chunk.LevelChunk$1
- XXX.level.chunk.LevelChunk$BoundTickingBlockEntity
+ XXX.level.chunk.LevelChunk$EntityCreationType
- XXX.level.chunk.LevelChunk$RebindableTickingBlockEntityWrapper
+ XXX.level.chunk.LevelChunkSection
- XXX.level.chunk.LightChunkGetter
+ XXX.level.chunk.LinearPalette
- XXX.level.chunk.OldDataLayer
- XXX.level.chunk.package-info
+ XXX.level.chunk.Palette
+ XXX.level.chunk.PalettedContainer
- XXX.level.chunk.PalettedContainer$CountConsumer
- XXX.level.chunk.PaletteResize
+ XXX.level.chunk.ProtoChunk
- XXX.level.chunk.ProtoTickList
+ XXX.level.chunk.UpgradeData
- XXX.level.chunk.UpgradeData$1
+ XXX.level.chunk.UpgradeData$BlockFixer
- XXX.level.chunk.UpgradeData$BlockFixers
+ XXX.level.chunk.UpgradeData$BlockFixers$1
- XXX.level.chunk.UpgradeData$BlockFixers$2
+ XXX.level.chunk.UpgradeData$BlockFixers$3
- XXX.level.chunk.UpgradeData$BlockFixers$4
+ XXX.level.chunk.UpgradeData$BlockFixers$5
- XXX.level.progress.ChunkProgressListener
+ XXX.level.progress.ChunkProgressListenerFactory
- XXX.level.progress.LoggerChunkProgressListener
+ XXX.level.progress.package-info
+ XXX.level.progress.ProcessorChunkProgressListener
- XXX.level.progress.StoringChunkProgressListener
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
- XXX.levelgen.carver.CanyonWorldCarver
+ XXX.levelgen.carver.CarverConfiguration
- XXX.levelgen.carver.CarverDebugSettings
+ XXX.levelgen.carver.CarvingContext
- XXX.levelgen.carver.CaveCarverConfiguration
- XXX.levelgen.heightproviders.BiasedToBottomHeight
- XXX.levelgen.heightproviders.HeightProvider
- XXX.levelgen.heightproviders.UniformHeight
- XXX.levelgen.structure.OceanRuinPieces$1
+ XXX.levelgen.structure.OceanRuinPieces$OceanRuinPiece
- XXX.levelgen.structure.PoolElementStructurePiece
+ XXX.levelgen.structure.RuinedPortalPiece
- XXX.levelgen.structure.RuinedPortalPiece$Properties
+ XXX.levelgen.structure.RuinedPortalPiece$VerticalPlacement
- XXX.levelgen.structure.ScatteredFeaturePiece
+ XXX.levelgen.structure.ShipwreckPieces
- XXX.levelgen.structure.ShipwreckPieces$ShipwreckPiece
+ XXX.levelgen.structure.StrongholdPieces
- XXX.levelgen.structure.StrongholdPieces$1
+ XXX.levelgen.structure.StrongholdPieces$2
- XXX.levelgen.structure.StrongholdPieces$3
+ XXX.levelgen.structure.StrongholdPieces$ChestCorridor
- XXX.levelgen.structure.StrongholdPieces$FillerCorridor
+ XXX.levelgen.structure.StrongholdPieces$FiveCrossing
- XXX.levelgen.structure.StrongholdPieces$LeftTurn
+ XXX.levelgen.structure.StrongholdPieces$Library
- XXX.levelgen.structure.StrongholdPieces$PieceWeight
+ XXX.levelgen.structure.StrongholdPieces$PortalRoom
- XXX.levelgen.structure.StrongholdPieces$PrisonHall
+ XXX.levelgen.structure.StrongholdPieces$RightTurn
- XXX.levelgen.structure.StrongholdPieces$RoomCrossing
+ XXX.levelgen.structure.StrongholdPieces$SmoothStoneSelector
- XXX.levelgen.structure.StrongholdPieces$StairsDown
+ XXX.levelgen.structure.StrongholdPieces$StartPiece
- XXX.levelgen.structure.StrongholdPieces$Straight
+ XXX.levelgen.structure.StrongholdPieces$StraightStairsDown
- XXX.levelgen.structure.StrongholdPieces$StrongholdPiece
+ XXX.levelgen.structure.StrongholdPieces$StrongholdPiece$SmallDoorType
- XXX.levelgen.structure.StrongholdPieces$Turn
+ XXX.levelgen.structure.StructureFeatureIndexSavedData
- XXX.levelgen.structure.StructurePiece
+ XXX.levelgen.structure.StructurePiece$1
- XXX.levelgen.structure.StructurePiece$BlockSelector
+ XXX.metadata.pack.package-info
+ XXX.metadata.pack.PackMetadataSection
- XXX.metadata.pack.PackMetadataSectionSerializer
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
+ XXX.minecraft.commands.BrigadierExceptions
- XXX.minecraft.commands.CommandFunction
+ XXX.minecraft.commands.CommandFunction$CacheableFunction
- XXX.minecraft.commands.CommandFunction$CommandEntry
+ XXX.minecraft.commands.CommandFunction$Entry
- XXX.minecraft.commands.CommandFunction$FunctionEntry
+ XXX.minecraft.commands.CommandRuntimeException
+ XXX.minecraft.commands.Commands
- XXX.minecraft.commands.Commands$CommandSelection
+ XXX.minecraft.commands.Commands$ParseFunction
- XXX.minecraft.commands.CommandSource
+ XXX.minecraft.commands.CommandSource$1
- XXX.minecraft.commands.CommandSourceStack
- XXX.minecraft.commands.SharedSuggestionProvider
+ XXX.minecraft.commands.SharedSuggestionProvider$TextCoordinates
+ XXX.minecraft.obfuscate.KeepAfterObfuscation
- XXX.minecraft.obfuscate.package-info
- XXX.minecraft.recipebook.package-info
- XXX.minecraft.recipebook.PlaceRecipe
+ XXX.minecraft.recipebook.ServerPlaceRecipe
+ XXX.minecraft.resources.DelegatingOps
+ XXX.minecraft.resources.package-info
- XXX.minecraft.resources.RegistryDataPackCodec
+ XXX.minecraft.resources.RegistryFileCodec
- XXX.minecraft.resources.RegistryLookupCodec
+ XXX.minecraft.resources.RegistryReadOps
- XXX.minecraft.resources.RegistryReadOps$1
+ XXX.minecraft.resources.RegistryReadOps$ReadCache
- XXX.minecraft.resources.RegistryReadOps$ResourceAccess
+ XXX.minecraft.resources.RegistryReadOps$ResourceAccess$1
- XXX.minecraft.resources.RegistryReadOps$ResourceAccess$MemoryMap
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
+ XXX.minecraft.sounds.Music
- XXX.minecraft.sounds.Musics
- XXX.minecraft.sounds.package-info
+ XXX.minecraft.sounds.SoundEvent
- XXX.minecraft.sounds.SoundEvents
+ XXX.minecraft.sounds.SoundSource
+ XXX.minecraft.stats.package-info
+ XXX.minecraft.stats.RecipeBook
- XXX.minecraft.stats.RecipeBookSettings
+ XXX.minecraft.stats.RecipeBookSettings$TypeSettings
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
+ XXX.minecraft.tags.GameEventTags
- XXX.minecraft.tags.ItemTags
- XXX.minecraft.tags.package-info
+ XXX.minecraft.tags.SerializationTags
- XXX.minecraft.tags.SetTag
+ XXX.minecraft.tags.StaticTagHelper
- XXX.minecraft.tags.StaticTagHelper$1
+ XXX.minecraft.tags.StaticTagHelper$Wrapper
- XXX.minecraft.tags.StaticTags
+ XXX.minecraft.tags.Tag
- XXX.minecraft.tags.Tag$1
+ XXX.minecraft.tags.Tag$Builder
- XXX.minecraft.tags.Tag$BuilderEntry
+ XXX.minecraft.tags.Tag$ElementEntry
- XXX.minecraft.tags.Tag$Entry
+ XXX.minecraft.tags.Tag$Named
- XXX.minecraft.tags.Tag$OptionalElementEntry
+ XXX.minecraft.tags.Tag$OptionalTagEntry
- XXX.minecraft.tags.Tag$TagEntry
+ XXX.minecraft.tags.TagCollection
- XXX.minecraft.tags.TagCollection$1
+ XXX.minecraft.tags.TagCollection$NetworkPayload
- XXX.minecraft.tags.TagContainer
+ XXX.minecraft.tags.TagContainer$1
- XXX.minecraft.tags.TagContainer$Builder
+ XXX.minecraft.tags.TagContainer$CollectionConsumer
- XXX.minecraft.tags.TagLoader
+ XXX.minecraft.tags.TagManager
- XXX.minecraft.tags.TagManager$1
+ XXX.minecraft.tags.TagManager$LoaderInfo
+ XXX.minecraft.util.BitStorage
+ XXX.minecraft.util.CrudeIncrementalIntIdentityHashBiMap
- XXX.minecraft.util.Crypt
+ XXX.minecraft.util.CryptException
- XXX.minecraft.util.CsvOutput
+ XXX.minecraft.util.CsvOutput$1
- XXX.minecraft.util.CsvOutput$Builder
+ XXX.minecraft.util.CubicSampler
- XXX.minecraft.util.CubicSampler$Vec3Fetcher
+ XXX.minecraft.util.DebugBuffer
- XXX.minecraft.util.DirectoryLock
+ XXX.minecraft.util.DirectoryLock$LockException
- XXX.minecraft.util.ExceptionCollector
+ XXX.minecraft.util.ExtraCodecs
+ XXX.minecraft.util.FloatProviderType
+ XXX.minecraft.util.GlslPreprocessor
+ XXX.minecraft.util.GlslPreprocessor$Context
- XXX.minecraft.util.GsonHelper
+ XXX.minecraft.util.HeapDumper
- XXX.minecraft.util.HttpUtil
+ XXX.minecraft.util.IntRange
- XXX.minecraft.util.package-info
+ XXX.minecraft.util.Tuple
+ XXX.minecraft.util.UniformInt
- XXX.minecraft.util.Unit
+ XXX.minecraft.util.VisibleForDebug
- XXX.minecraft.util.WeighedRandom
+ XXX.minecraft.util.WeighedRandom$WeighedRandomItem
+ XXX.minecraft.world.package-info
- XXX.mojang.math.Constants
- XXX.mojang.math.MethodsReturnNonnullByDefault
+ XXX.mojang.math.OctahedralGroup
- XXX.mojang.math.OctahedralGroup$1
+ XXX.mojang.math.Quaternion
- XXX.mojang.math.SymmetricGroup3
+ XXX.mojang.math.Transformation
- XXX.mojang.math.Vector3d
+ XXX.monitoring.jmx.MinecraftServerStatistics
- XXX.monitoring.jmx.MinecraftServerStatistics$1
+ XXX.monitoring.jmx.MinecraftServerStatistics$AttributeDescription
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
+ XXX.packs.resources.package-info
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
+ XXX.packs.resources.ResourceProvider
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
+ XXX.phys.shapes.NonOverlappingMerger
- XXX.phys.shapes.OffsetDoubleList
- XXX.phys.shapes.package-info
+ XXX.phys.shapes.Shapes
- XXX.phys.shapes.Shapes$DoubleLineConsumer
+ XXX.phys.shapes.SliceShape
- XXX.phys.shapes.SubShape
+ XXX.phys.shapes.VoxelShape
+ XXX.profiling.registry.MeasuredMetric
- XXX.profiling.registry.MeasurementCategory
+ XXX.profiling.registry.MeasurementRegistry
- XXX.profiling.registry.Metric
- XXX.profiling.registry.package-info
+ XXX.profiling.registry.ProfilerMeasured
+ XXX.rcon.thread.GenericThread
- XXX.rcon.thread.package-info
- XXX.rcon.thread.QueryThreadGs4
+ XXX.rcon.thread.QueryThreadGs4$RequestChallenge
- XXX.rcon.thread.RconClient
+ XXX.rcon.thread.RconThread
+ XXX.scores.criteria.ObjectiveCriteria
- XXX.scores.criteria.ObjectiveCriteria$RenderType
+ XXX.scores.criteria.package-info
+ XXX.selector.options.EntitySelectorOptions
- XXX.selector.options.EntitySelectorOptions$1
+ XXX.selector.options.EntitySelectorOptions$Modifier
- XXX.selector.options.EntitySelectorOptions$Option
+ XXX.selector.options.package-info
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
+ XXX.server.commands.ItemCommands
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
- XXX.server.commands.SpreadPlayersCommand$1
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
- XXX.server.level.ChunkHolder$ChunkSaveDebug
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
+ XXX.server.level.package-info
+ XXX.server.level.PlayerMap
- XXX.server.level.PlayerRespawnLogic
+ XXX.server.level.SectionTracker
- XXX.server.level.ServerBossEvent
+ XXX.server.level.ServerChunkCache
- XXX.server.level.ServerChunkCache$1
+ XXX.server.level.ServerChunkCache$MainThreadExecutor
- XXX.server.level.ServerEntity
+ XXX.server.level.ServerLevel
- XXX.server.level.ServerLevel$1
+ XXX.server.level.ServerLevel$EntityCallbacks
- XXX.server.level.ServerPlayer
+ XXX.server.level.ServerPlayer$1
- XXX.server.level.ServerPlayer$2
+ XXX.server.level.ServerPlayer$3
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
- XXX.server.network.ServerConnectionListener$LatencySimulator$DelayedMessage
+ XXX.server.network.ServerGamePacketListenerImpl
- XXX.server.network.ServerGamePacketListenerImpl$1
+ XXX.server.network.ServerGamePacketListenerImpl$2
- XXX.server.network.ServerGamePacketListenerImpl$EntityInteraction
+ XXX.server.network.ServerHandshakePacketListenerImpl
- XXX.server.network.ServerHandshakePacketListenerImpl$1
+ XXX.server.network.ServerLoginPacketListenerImpl
- XXX.server.network.ServerLoginPacketListenerImpl$1
+ XXX.server.network.ServerLoginPacketListenerImpl$State
- XXX.server.network.ServerPlayerConnection
+ XXX.server.network.ServerStatusPacketListenerImpl
- XXX.server.network.TextFilter
+ XXX.server.network.TextFilter$1
- XXX.server.network.TextFilter$FilteredText
+ XXX.server.network.TextFilterClient
- XXX.server.network.TextFilterClient$1
+ XXX.server.network.TextFilterClient$IgnoreStrategy
- XXX.server.network.TextFilterClient$PlayerContext
+ XXX.server.network.TextFilterClient$RequestFailedException
- XXX.server.packs.AbstractPackResources
+ XXX.server.packs.FilePackResources
- XXX.server.packs.FolderPackResources
+ XXX.server.packs.package-info
+ XXX.server.packs.PackResources
- XXX.server.packs.PackType
+ XXX.server.packs.ResourcePackFileNotFoundException
- XXX.server.packs.VanillaPackResources
+ XXX.server.packs.VanillaPackResources$1
- XXX.server.players.BanListEntry
+ XXX.server.players.GameProfileCache
- XXX.server.players.GameProfileCache$1
+ XXX.server.players.GameProfileCache$GameProfileInfo
- XXX.server.players.IpBanList
+ XXX.server.players.IpBanListEntry
- XXX.server.players.OldUsersConverter
+ XXX.server.players.OldUsersConverter$1
- XXX.server.players.OldUsersConverter$2
+ XXX.server.players.OldUsersConverter$3
- XXX.server.players.OldUsersConverter$4
+ XXX.server.players.OldUsersConverter$5
- XXX.server.players.OldUsersConverter$ConversionError
- XXX.server.players.package-info
+ XXX.server.players.PlayerList
- XXX.server.players.PlayerList$1
+ XXX.server.players.ServerOpList
- XXX.server.players.ServerOpListEntry
+ XXX.server.players.SleepStatus
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
- XXX.state.pattern.BlockInWorld
+ XXX.state.pattern.BlockPattern
- XXX.state.pattern.BlockPattern$BlockCacheLoader
+ XXX.state.pattern.BlockPattern$BlockPatternMatch
- XXX.state.pattern.BlockPatternBuilder
+ XXX.state.pattern.package-info
- XXX.state.predicate.BlockMaterialPredicate
+ XXX.state.predicate.BlockMaterialPredicate$1
- XXX.state.predicate.BlockPredicate
+ XXX.state.predicate.BlockStatePredicate
- XXX.state.predicate.package-info
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
- XXX.state.properties.DripstoneThickness
+ XXX.state.properties.EnumProperty
- XXX.state.properties.Half
+ XXX.state.properties.IntegerProperty
- XXX.state.properties.NoteBlockInstrument
- XXX.state.properties.package-info
+ XXX.state.properties.PistonType
- XXX.state.properties.Property
+ XXX.state.properties.Property$1
- XXX.state.properties.Property$Value
+ XXX.state.properties.RailShape
- XXX.state.properties.RedstoneSide
+ XXX.state.properties.SculkSensorPhase
- XXX.state.properties.SlabType
+ XXX.state.properties.StairsShape
- XXX.state.properties.StructureMode
+ XXX.state.properties.Tilt
- XXX.state.properties.WallSide
+ XXX.state.properties.WoodType
+ XXX.storage.threaded.package-info
+ XXX.util.datafix.DataFixers
- XXX.util.datafix.DataFixers$1
+ XXX.util.datafix.DataFixers$2
- XXX.util.datafix.DataFixTypes
- XXX.util.datafix.package-info
- XXX.util.datafix.PackedBitStorage
+ XXX.util.profiling.ActiveProfiler
- XXX.util.profiling.ActiveProfiler$PathEntry
+ XXX.util.profiling.ContinuousProfiler
- XXX.util.profiling.EmptyProfileResults
+ XXX.util.profiling.FilledProfileResults
- XXX.util.profiling.FilledProfileResults$1
+ XXX.util.profiling.FilledProfileResults$CounterCollector
- XXX.util.profiling.InactiveProfiler
- XXX.util.profiling.package-info
+ XXX.util.profiling.ProfileCollector
- XXX.util.profiling.ProfileResults
+ XXX.util.profiling.ProfilerFiller
- XXX.util.profiling.ProfilerFiller$1
+ XXX.util.profiling.ProfilerPathEntry
- XXX.util.profiling.ResultField
+ XXX.util.profiling.SingleTickProfiler
- XXX.util.random.package-info
- XXX.util.random.SimpleWeightedRandomList$Builder
- XXX.util.random.WeightedEntry
- XXX.util.random.WeightedEntry$IntrusiveBase
- XXX.util.random.WeightedRandom
+ XXX.util.thread.BlockableEventLoop
- XXX.util.thread.NamedThreadFactory
+ XXX.util.thread.package-info
+ XXX.util.thread.ProcessorHandle
- XXX.util.thread.ProcessorHandle$1
+ XXX.util.thread.ProcessorMailbox
- XXX.util.thread.ReentrantBlockableEventLoop
+ XXX.util.thread.StrictQueue
- XXX.util.thread.StrictQueue$FixedPriorityQueue
+ XXX.util.thread.StrictQueue$IntRunnable
- XXX.util.thread.StrictQueue$QueueStrictQueue
- XXX.util.valueproviders.ClampedNormalFloat
- XXX.util.valueproviders.ConstantInt
- XXX.util.valueproviders.FloatProviderType
- XXX.util.valueproviders.IntProviderType
- XXX.util.valueproviders.package-info
- XXX.util.valueproviders.UniformFloat
+ XXX.village.poi.package-info
+ XXX.village.poi.PoiManager
- XXX.village.poi.PoiManager$DistanceTracker
+ XXX.village.poi.PoiManager$Occupancy
- XXX.village.poi.PoiRecord
+ XXX.village.poi.PoiSection
- XXX.village.poi.PoiType
- XXX.world.phys.AABB
+ XXX.world.phys.BlockHitResult
- XXX.world.phys.EntityHitResult
+ XXX.world.phys.HitResult
- XXX.world.phys.HitResult$Type
+ XXX.world.phys.package-info
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
XXX.mojang.math.Matrix3f +17M | +1P
```
```
XXX.mojang.math.Vector4f +11M
```
```
XXX.minecraft.core.Cursor3D +4P
```
```
XXX.minecraft.core.IdMapper +1P
```
```
XXX.minecraft.core.QuartPos +3P
```
```
XXX.minecraft.core.SectionPos +17P
```
```
XXX.core.particles.ParticleTypes +1P
```
```
XXX.data.models.BlockModelGenerators +1M
```
```
XXX.data.worldgen.BiomeDefaultFeatures +2M -1M
```
```
XXX.data.worldgen.Features$States +1P
```
```
XXX.gametest.framework.GameTestServer +1P
```
```
XXX.gametest.framework.StructureUtils +2P
```
```
XXX.gametest.framework.TestCommand +9P
```
```
XXX.minecraft.locale.Language +1P
```
```
XXX.minecraft.nbt.ListTag +1P
```
```
XXX.minecraft.nbt.LongArrayTag +1P
```
```
XXX.minecraft.nbt.LongTag +1P
```
```
XXX.minecraft.nbt.LongTag$Cache +2P
```
```
XXX.minecraft.nbt.SnbtPrinterTagVisitor +7P
```
```
XXX.minecraft.nbt.Tag +19P
```
```
XXX.minecraft.nbt.TextComponentTagVisitor +8P
```
```
XXX.minecraft.network.Varint21LengthFieldPrepender +1P
```
```
XXX.protocol.game.ClientboundBossEventPacket +3P
```
```
XXX.protocol.game.ClientboundCommandsPacket +7P
```
```
XXX.protocol.game.ClientboundContainerSetSlotPacket +2P
```
```
XXX.protocol.game.ClientboundCustomPayloadPacket +1P
```
```
XXX.protocol.game.ClientboundGameEventPacket +5P
```
```
XXX.protocol.game.ClientboundMoveEntityPacket +1P
```
```
XXX.protocol.game.ClientboundSectionBlocksUpdatePacket +1P
```
```
XXX.protocol.game.ClientboundSetObjectivePacket +3P
```
```
XXX.protocol.game.ClientboundSetPlayerTeamPacket +7P
```
```
XXX.protocol.game.ClientboundStopSoundPacket +2P
```
```
XXX.protocol.game.ClientboundUpdateMobEffectPacket +3P
```
```
XXX.protocol.game.ServerboundClientInformationPacket +1P
```
```
XXX.protocol.game.ServerboundPlayerInputPacket +2P
```
```
XXX.protocol.game.ServerboundSignUpdatePacket +1P
```
```
XXX.protocol.handshake.ClientIntentionPacket +1P
```
```
XXX.protocol.login.ClientboundCustomQueryPacket +1P
```
```
XXX.protocol.login.ServerboundCustomQueryPacket +1P
```
```
XXX.protocol.status.ServerStatus +2P
```
```
XXX.network.syncher.SynchedEntityData +2P
```
```
XXX.minecraft.util.LinearCongruentialGenerator +2P
```
```
XXX.minecraft.util.ParticleUtils +2M -2M
```
```
XXX.minecraft.util.StringDecomposer +1P
```
```
XXX.minecraft.util.TimeUtil +1M -1M
```
```
XXX.minecraft.world.Container +1P
```
```
XXX.minecraft.world.Snooper +3P
```
```
XXX.world.damagesource.CombatTracker +2P
```
```
XXX.world.entity.AgeableMob +2P
```
```
XXX.world.entity.AreaEffectCloud +2P
```
```
XXX.world.entity.EntityType +3P
```
```
XXX.world.entity.ExperienceOrb +1M | +5P
```
```
XXX.world.entity.ItemBasedSteering +2P
```
```
XXX.world.entity.LightningBolt +1P
```
```
XXX.world.entity.Pose +1P
```
```
XXX.ai.behavior.AcquirePoi +3P
```
```
XXX.ai.behavior.AnimalMakeLove +3P
```
```
XXX.ai.behavior.PlayTagWithOtherKids +6P
```
```
XXX.ai.behavior.RingBell +2P
```
```
XXX.ai.behavior.SetClosestHomeAsWalkTarget +4P
```
```
XXX.ai.behavior.SetHiddenState +1P
```
```
XXX.ai.behavior.SetWalkTargetFromAttackTargetIfTargetOutOfReach +1P
```
```
XXX.ai.behavior.SleepInBed +1P
```
```
XXX.ai.behavior.StopAttackingIfTargetInvalid +6M -1M | +2P
```
```
XXX.ai.behavior.StrollAroundPoi +3P
```
```
XXX.ai.behavior.TradeWithVillager +2P
```
```
XXX.ai.behavior.ValidateNearbyPoi +1P
```
```
XXX.ai.behavior.VillageBoundRandomStroll +2P
```
```
XXX.ai.behavior.VillagerGoalPackages +1P
```
```
XXX.ai.control.BodyRotationControl +3P
```
```
XXX.ai.goal.EatBlockGoal +1P
```
```
XXX.ai.goal.FollowFlockLeaderGoal +1P
```
```
XXX.ai.goal.FollowOwnerGoal +4P
```
```
XXX.ai.goal.GoalSelector +1P
```
```
XXX.ai.goal.LlamaFollowCaravanGoal +1P
```
```
XXX.ai.goal.MoveBackToVillageGoal +2P
```
```
XXX.ai.sensing.NearestItemSensor +3P
```
```
XXX.animal.horse.Llama +2P
```
```
XXX.enderdragon.phases.DragonSittingAttackingPhase +1P
```
```
XXX.enderdragon.phases.DragonSittingScanningPhase +4P
```
```
XXX.entity.decoration.ArmorStand +12P
```
```
XXX.entity.decoration.LeashFenceKnotEntity +1P
```
```
XXX.entity.item.PrimedTnt +1P
```
```
XXX.entity.monster.Drowned +1P
```
```
XXX.entity.monster.EnderMan +3P -1P
```
```
XXX.entity.monster.Enemy +6P
```
```
XXX.entity.monster.Illusioner +3P
```
```
XXX.entity.monster.Phantom +1P
```
```
XXX.entity.monster.Shulker +2M | +8P
```
```
XXX.entity.monster.Skeleton +1M | +1P
```
```
XXX.entity.monster.Strider +3P
```
```
XXX.entity.monster.Vex +2P
```
```
XXX.entity.monster.Zombie +5P
```
```
XXX.entity.monster.ZombifiedPiglin +4P -3P
```
```
XXX.monster.hoglin.HoglinAi +15P -2P
```
```
XXX.monster.piglin.AbstractPiglin +1P
```
```
XXX.monster.piglin.PiglinAi +35P -6P
```
```
XXX.monster.piglin.PiglinBrute +3P
```
```
XXX.entity.npc.CatSpawner +1P
```
```
XXX.entity.npc.Villager +10P
```
```
XXX.entity.npc.VillagerTrades +14P
```
```
XXX.entity.player.Inventory +5P
```
```
XXX.entity.projectile.AbstractArrow +4P
```
```
XXX.entity.projectile.Arrow +3P
```
```
XXX.entity.projectile.EvokerFangs +3P
```
```
XXX.entity.projectile.FishingHook +1P
```
```
XXX.entity.projectile.ThrownPotion +2P
```
```
XXX.entity.raid.Raid +21P
```
```
XXX.entity.vehicle.AbstractMinecart +1P
```
```
XXX.entity.vehicle.MinecartCommandBlock +1P
```
```
XXX.entity.vehicle.MinecartTNT +1P
```
```
XXX.world.food.FoodConstants +26P
```
```
XXX.world.inventory.AnvilMenu +9P
```
```
XXX.world.inventory.BeaconMenu +7P
```
```
XXX.world.inventory.BrewingStandMenu +10P
```
```
XXX.world.inventory.CartographyTableMenu +7P
```
```
XXX.world.inventory.ChestMenu +1P
```
```
XXX.world.inventory.CraftingMenu +7P
```
```
XXX.world.inventory.HopperMenu +1P
```
```
XXX.world.inventory.InventoryMenu +11P
```
```
XXX.world.inventory.LecternMenu +6P
```
```
XXX.world.inventory.LoomMenu +4P
```
```
XXX.world.inventory.StonecutterMenu +6P
```
```
XXX.world.item.BlockItem +2P
```
```
XXX.world.item.BoneMealItem +3P
```
```
XXX.world.item.BundleItem +3P
```
```
XXX.world.item.CompassItem +3P
```
```
XXX.world.item.DyeableLeatherItem +3P
```
```
XXX.world.item.EnchantedBookItem +1P
```
```
XXX.world.item.HoneyBottleItem +1P
```
```
XXX.world.item.HorseArmorItem +1P
```
```
XXX.world.item.Items +1M | +2P
```
```
XXX.world.item.MapItem +4P
```
```
XXX.world.item.PickaxeItem +1P
```
```
XXX.world.item.PotionItem +1P
```
```
XXX.world.item.ShieldItem +3P
```
```
XXX.world.item.TridentItem +3P
```
```
XXX.world.item.WrittenBookItem +13P
```
```
XXX.item.alchemy.PotionBrewing +1P
```
```
XXX.item.alchemy.PotionUtils +4P
```
```
XXX.item.crafting.ShapedRecipe +2M -1M
```
```
XXX.item.enchantment.DamageEnchantment +3P
```
```
XXX.world.level.BlockGetter +1M
```
```
XXX.world.level.CommonLevelAccessor +1M
```
```
XXX.world.level.GameRules +1P
```
```
XXX.world.level.GameType +1P
```
```
XXX.world.level.LevelSimulatedReader +1P
```
```
XXX.world.level.NaturalSpawner +1M -1M | +3P
```
```
XXX.world.level.SpawnData +2P
```
```
XXX.level.biome.FuzzyOffsetBiomeZoomer +3P
```
```
XXX.level.biome.MobSpawnSettings +2M -2M | +2P
```
```
XXX.level.biome.MobSpawnSettings$Builder +1M -1M
```
```
XXX.level.biome.MobSpawnSettings$SpawnerData +2M -2M
```
```
XXX.level.biome.TheEndBiomeSource +3P
```
```
XXX.level.block.AbstractCauldronBlock +5P
```
```
XXX.level.block.AttachedStemBlock +1P
```
```
XXX.level.block.BambooBlock +8P
```
```
XXX.level.block.BaseCoralPlantBlock +1P
```
```
XXX.level.block.BaseFireBlock +2P
```
```
XXX.level.block.BedBlock +2P
```
```
XXX.level.block.BeehiveBlock +2P
```
```
XXX.level.block.BellBlock +1P
```
```
XXX.level.block.BigDripleafBlock -2M | +6P
```
```
XXX.level.block.Block +15P
```
```
XXX.level.block.Blocks +1P
```
```
XXX.level.block.CakeBlock +3P
```
```
XXX.level.block.CandleBlock +1M | +2P
```
```
XXX.level.block.CaveVinesBlock +1P
```
```
XXX.level.block.ChainBlock +2P
```
```
XXX.level.block.ChangeOverTimeBlock +1P
```
```
XXX.level.block.ConduitBlock +1P
```
```
XXX.level.block.CropBlock +1P
```
```
XXX.level.block.DetectorRailBlock +1P
```
```
XXX.level.block.DoorBlock +1P
```
```
XXX.level.block.FarmBlock +1P
```
```
XXX.level.block.FireBlock +9P
```
```
XXX.level.block.FlowerBlock +1P
```
```
XXX.level.block.FrostedIceBlock +3P
```
```
XXX.level.block.LeavesBlock +2P
```
```
XXX.level.block.LeverBlock +3P
```
```
XXX.level.dimension.DimensionType +1P
```
```
XXX.dimension.end.EndDragonFight +8P
```
```
XXX.level.gameevent.GameEvent +1P
```
```
XXX.level.levelgen.Aquifer +1M | +11P
```
```
XXX.level.levelgen.Beardifier +2P
```
```
XXX.level.levelgen.Decoratable +1M -1M
```
```
XXX.level.levelgen.NoiseBasedChunkGenerator +1M -1M
```
```
XXX.level.levelgen.NoiseSampler +1P
```
```
XXX.level.levelgen.VerticalAnchor$AboveBottom +1M
```
```
XXX.level.levelgen.VerticalAnchor$BelowTop +1M
```
```
XXX.levelgen.carver.CanyonCarverConfiguration +6M -13M | +2P -10P
```
```
XXX.levelgen.feature.BasaltColumnsFeature +4P
```
```
XXX.levelgen.feature.BuriedTreasureFeature +1P
```
```
XXX.levelgen.feature.EndCityFeature +1P
```
```
XXX.levelgen.feature.EndPodiumFeature +4P
```
```
XXX.levelgen.feature.HugeFungusFeature +1P
```
```
XXX.levelgen.feature.IglooFeature$FeatureStart +1M -1M
```
```
XXX.levelgen.feature.JigsawFeature$FeatureStart +1M -1M
```
```
XXX.levelgen.feature.JunglePyramidFeature$FeatureStart +1M -1M
```
```
XXX.levelgen.feature.LargeDripstoneFeature$WindOffsetter +2M -2M
```
```
XXX.levelgen.feature.MineshaftFeature$MineShaftStart +1M -1M
```
```
XXX.levelgen.feature.NetherFortressFeature +1M -1M | +1P -1P
```
```
XXX.levelgen.feature.OceanMonumentFeature +1M -1M | +1P -1P
```
```
XXX.levelgen.feature.RuinedPortalFeature +7P
```
```
XXX.levelgen.feature.SpikeFeature +2P
```
```
XXX.levelgen.feature.StrongholdFeature$StrongholdStart +1M -1M
```
```
XXX.levelgen.feature.StructureFeature$StructureStartFactory +1P -1P
```
```
XXX.levelgen.feature.SwamplandHutFeature +2M -2M | +2P -2P
```
```
XXX.levelgen.feature.TreeFeature +7M -3M | +1P
```
```
XXX.levelgen.feature.VoidStartPlatformFeature +2P
```
```
XXX.feature.configurations.CountConfiguration +2M -2M | +1P -1P
```
```
XXX.feature.configurations.DiskConfiguration +2M -2M | +1P -1P
```
```
XXX.feature.configurations.GrowingPlantConfiguration +2M -3M | +1P -1P
```
```
XXX.feature.configurations.LargeDripstoneConfiguration +6M -6M | +5P -5P
```
```
XXX.feature.foliageplacers.AcaciaFoliagePlacer +2M -2M
```
```
XXX.feature.foliageplacers.BushFoliagePlacer +2M -2M
```
```
XXX.feature.foliageplacers.FancyFoliagePlacer +2M -2M
```
```
XXX.feature.foliageplacers.FoliagePlacer$FoliageAttachment +1M -1M | +1P -1P
```
```
XXX.feature.foliageplacers.MegaJungleFoliagePlacer +2M -2M
```
```
XXX.feature.foliageplacers.PineFoliagePlacer +3M -3M | +1P -1P
```
```
XXX.feature.foliageplacers.SpruceFoliagePlacer +3M -3M | +1P -1P
```
```
XXX.feature.stateproviders.WeightedStateProvider +4M -5M | +1P -1P
```
```
XXX.feature.treedecorators.AlterGroundDecorator +4M -4M
```
```
XXX.feature.treedecorators.CocoaDecorator +2M -2M
```
```
XXX.feature.treedecorators.TreeDecorator +1M -2M | +1P -1P
```
```
XXX.feature.treedecorators.TrunkVineDecorator +2M -2M
```
```
XXX.feature.trunkplacers.BendingTrunkPlacer +3M -3M | +1P -1P
```
```
XXX.feature.trunkplacers.FancyTrunkPlacer +4M -3M | +4P
```
```
XXX.feature.trunkplacers.ForkingTrunkPlacer +1M -1M
```
```
XXX.feature.trunkplacers.MegaJungleTrunkPlacer +1M -1M
```
```
XXX.feature.trunkplacers.TrunkPlacer +4M -4M | +4P -1P
```
```
XXX.levelgen.structure.EndCityPieces +8M -10M | +1P -2P
```
```
XXX.levelgen.structure.IglooPieces$IglooPiece +3M -1M | -2P
```
```
XXX.levelgen.structure.MineShaftPieces$MineShaftCrossing +2M -2M
```
```
XXX.levelgen.structure.MineShaftPieces$MineShaftRoom +1M -1M
```
```
XXX.levelgen.structure.NetherBridgePieces +2M -2M | +2P
```
```
XXX.levelgen.structure.NetherBridgePieces$BridgeCrossing +3M -3M | +3P
```
```
XXX.levelgen.structure.NetherBridgePieces$BridgeStraight +2M -2M | +3P
```
```
XXX.levelgen.structure.NetherBridgePieces$CastleCorridorTBalconyPiece +2M -2M | +3P
```
```
XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorCrossingPiece +2M -2M | +3P
```
```
XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorPiece +2M -2M | +3P
```
```
XXX.levelgen.structure.NetherBridgePieces$CastleStalkRoom +2M -2M | +3P
```
```
XXX.levelgen.structure.NetherBridgePieces$NetherBridgePiece +6M -6M
```
```
XXX.levelgen.structure.NetherBridgePieces$RoomCrossing +2M -2M | +3P
```
```
XXX.levelgen.structure.NetherFossilFeature$FeatureStart +1M -1M
```
```
XXX.levelgen.structure.NetherFossilPieces$NetherFossilPiece +2M -1M | -2P
```
```
XXX.levelgen.structure.StructureStart +10M -3M | +2P -1P
```
```
XXX.levelgen.structure.WoodlandMansionPieces$MansionGrid +16P
```
```
XXX.levelgen.structure.WoodlandMansionPieces$WoodlandMansionPiece +4M -1M | -3P
```
```
XXX.structure.templatesystem.StructureManager +3P
```
```
XXX.levelgen.surfacebuilders.DefaultSurfaceBuilder +1P
```
```
XXX.levelgen.synth.PerlinNoise +1P
```
```
XXX.level.lighting.DataLayerStorageMap +1P
```
```
XXX.level.lighting.FlatDataLayer +1P
```
```
XXX.level.lighting.LayerLightSectionStorage +3P
```
```
XXX.level.lighting.LevelLightEngine +2P
```
```
XXX.level.material.FlowingFluid +1P
```
```
XXX.level.material.LavaFluid +1P
```
```
XXX.newbiome.layer.Layers +6P
```
```
XXX.level.pathfinder.WalkNodeEvaluator +1P
```
```
XXX.level.portal.PortalForcer +13P
```
```
XXX.level.portal.PortalShape +4P
```
```
XXX.level.redstone.Redstone +3P
```
```
XXX.saveddata.maps.MapIndex +1P
```
```
XXX.level.storage.McRegionUpgrader +1P
```
```
XXX.level.storage.PrimaryLevelData +1P
```
```
XXX.level.storage.WorldData +2P
```
```
XXX.providers.nbt.ContextNbtProvider +1P
```

</details>
<details>
<summary>
com.mojang.math.Matrix3f
</summary>

```diff
- boolean invert()
- float adjugateAndDet()
- float determinant()
- float trace()
- int bufferIndex(int,int)
- Matrix3f createScaleMatrix(float,float,float)
- void add(Matrix3f)
- void load(FloatBuffer,boolean)
- void load(FloatBuffer)
- void loadTransposed(FloatBuffer)
- void mul(float)
- void mul(Quaternion)
- void sortSingularValues(Matrix3f,Quaternion)
- void store(FloatBuffer,boolean)
- void store(FloatBuffer)
- void storeTransposed(FloatBuffer)
- void sub(Matrix3f)
```

</details>
<details>
<summary>
com.mojang.math.Vector4f
</summary>

```diff
- boolean normalize()
- float dot(Vector4f)
- float w()
- void <init>(Vector3f)
- void add(float,float,float,float)
- void lerp(Vector4f,float)
- void mul(float)
- void mul(Vector3f)
- void perspectiveDivide()
- void set(float,float,float,float)
- void transform(Quaternion)
```

</details>
<details>
<summary>
net.minecraft.data.models.BlockModelGenerators
</summary>

```diff
- void createLightBlockItems()
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.BiomeDefaultFeatures
</summary>

```diff
+ void ambientSpawns(MobSpawnSettings$Builder)
- void caveSpawns(MobSpawnSettings$Builder)
- void caveWaterSpawns(MobSpawnSettings$Builder)
```

</details>
<details>
<summary>
net.minecraft.util.ParticleUtils
</summary>

```diff
+ void spawnParticlesAlongAxis(Direction$Axis,Level,BlockPos,double,ParticleOptions,IntRange)
- void spawnParticlesAlongAxis(Direction$Axis,Level,BlockPos,double,ParticleOptions,UniformInt)
+ void spawnParticlesOnBlockFaces(Level,BlockPos,ParticleOptions,IntRange)
- void spawnParticlesOnBlockFaces(Level,BlockPos,ParticleOptions,UniformInt)
```

</details>
<details>
<summary>
net.minecraft.util.TimeUtil
</summary>

```diff
+ IntRange rangeOfSeconds(int,int)
- UniformInt rangeOfSeconds(int,int)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ExperienceOrb
</summary>

```diff
- int repairPlayerItems(Player,int)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.behavior.StopAttackingIfTargetInvalid
</summary>

```diff
+ boolean lambda$new$0(LivingEntity)
- boolean lambda$new$1(LivingEntity)
- boolean lambda$new$2(LivingEntity)
- void <init>(Consumer)
- void <init>(Predicate,Consumer)
- void lambda$new$0(Mob)
- void lambda$new$3(Mob)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Shulker
</summary>

```diff
- void onSyncedDataUpdated(EntityDataAccessor)
- void setAttachFace(Direction)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Skeleton
</summary>

```diff
- boolean isShaking()
```

</details>
<details>
<summary>
net.minecraft.world.item.Items
</summary>

```diff
- Item registerBlock(Block,CreativeModeTab,Block[])
```

</details>
<details>
<summary>
net.minecraft.world.item.crafting.ShapedRecipe
</summary>

```diff
- Item itemFromJson(JsonObject)
+ ItemStack itemFromJson(JsonObject)
- ItemStack itemStackFromJson(JsonObject)
```

</details>
<details>
<summary>
net.minecraft.world.level.BlockGetter
</summary>

```diff
- Optional getBlockEntity(BlockPos,BlockEntityType)
```

</details>
<details>
<summary>
net.minecraft.world.level.CommonLevelAccessor
</summary>

```diff
- Optional getBlockEntity(BlockPos,BlockEntityType)
```

</details>
<details>
<summary>
net.minecraft.world.level.NaturalSpawner
</summary>

```diff
+ List mobsAt(ServerLevel,StructureFeatureManager,ChunkGenerator,MobCategory,BlockPos,Biome)
- WeightedRandomList mobsAt(ServerLevel,StructureFeatureManager,ChunkGenerator,MobCategory,BlockPos,Biome)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.MobSpawnSettings
</summary>

```diff
+ List getMobs(MobCategory)
+ List lambda$static$1(MobCategory)
- WeightedRandomList getMobs(MobCategory)
- WeightedRandomList lambda$static$1(MobCategory)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.MobSpawnSettings$Builder
</summary>

```diff
+ List lambda$build$2(Map$Entry)
- WeightedRandomList lambda$build$2(Map$Entry)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.MobSpawnSettings$SpawnerData
</summary>

```diff
- App lambda$static$3(RecordCodecBuilder$Instance)
+ App lambda$static$4(RecordCodecBuilder$Instance)
+ Integer lambda$null$3(MobSpawnSettings$SpawnerData)
- void <init>(EntityType,Weight,int,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BigDripleafBlock
</summary>

```diff
+ VoxelShape getLeafShape(BlockState)
+ VoxelShape getStemShape(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CandleBlock
</summary>

```diff
- boolean canBeLit(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.Aquifer
</summary>

```diff
- boolean isLavaLevel(int)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.Decoratable
</summary>

```diff
- Object count(IntProvider)
+ Object count(UniformInt)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator
</summary>

```diff
+ List getMobsAt(Biome,StructureFeatureManager,MobCategory,BlockPos)
- WeightedRandomList getMobsAt(Biome,StructureFeatureManager,MobCategory,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.VerticalAnchor$AboveBottom
</summary>

```diff
- String toString()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.VerticalAnchor$BelowTop
</summary>

```diff
- String toString()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.carver.CanyonCarverConfiguration
</summary>

```diff
+ App lambda$static$1(RecordCodecBuilder$Instance)
- App lambda$static$3(RecordCodecBuilder$Instance)
- CanyonCarverConfiguration$CanyonShapeConfiguration lambda$null$2(CanyonCarverConfiguration)
- CarverConfiguration lambda$null$0(CanyonCarverConfiguration)
+ float getVerticalRadiusCenterFactor()
+ float getVerticalRadiusDefaultFactor()
+ Float lambda$null$0(CanyonCarverConfiguration)
+ FloatProvider getDistanceFactor()
+ FloatProvider getHorizontalRadiusFactor()
+ FloatProvider getThickness()
+ FloatProvider getVerticalRotation()
- FloatProvider lambda$null$1(CanyonCarverConfiguration)
+ int getWidthSmoothness()
+ UniformInt getYScale()
+ VerticalAnchor getBottomInclusive()
+ VerticalAnchor getTopInclusive()
- void <init>(CarverConfiguration,FloatProvider,CanyonCarverConfiguration$CanyonShapeConfiguration)
+ void <init>(float,CarverDebugSettings,VerticalAnchor,VerticalAnchor,UniformInt,FloatProvider,FloatProvider,FloatProvider,int,FloatProvider,float,float)
- void <init>(float,HeightProvider,FloatProvider,VerticalAnchor,CarverDebugSettings,FloatProvider,CanyonCarverConfiguration$CanyonShapeConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.IglooFeature$FeatureStart
</summary>

```diff
+ void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
- void <init>(StructureFeature,ChunkPos,int,long)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.JigsawFeature$FeatureStart
</summary>

```diff
+ void <init>(JigsawFeature,ChunkPos,BoundingBox,int,long)
- void <init>(JigsawFeature,ChunkPos,int,long)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.JunglePyramidFeature$FeatureStart
</summary>

```diff
+ void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
- void <init>(StructureFeature,ChunkPos,int,long)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature$WindOffsetter
</summary>

```diff
+ void <init>(int,Random,FloatProvider,LargeDripstoneFeature$1)
- void <init>(int,Random,FloatProvider,LargeDripstoneFeature$1)
+ void <init>(int,Random,FloatProvider)
- void <init>(int,Random,FloatProvider)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.MineshaftFeature$MineShaftStart
</summary>

```diff
+ void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
- void <init>(StructureFeature,ChunkPos,int,long)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.NetherFortressFeature
</summary>

```diff
+ List getSpecialEnemies()
- WeightedRandomList getSpecialEnemies()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.OceanMonumentFeature
</summary>

```diff
+ List getSpecialEnemies()
- WeightedRandomList getSpecialEnemies()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.StrongholdFeature$StrongholdStart
</summary>

```diff
+ void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
- void <init>(StructureFeature,ChunkPos,int,long)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.SwamplandHutFeature
</summary>

```diff
+ List getSpecialAnimals()
+ List getSpecialEnemies()
- WeightedRandomList getSpecialAnimals()
- WeightedRandomList getSpecialEnemies()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.TreeFeature
</summary>

```diff
- boolean doPlace(WorldGenLevel,Random,BlockPos,BiConsumer,BiConsumer,TreeConfiguration)
+ boolean doPlace(WorldGenLevel,Random,BlockPos,Set,Set,BoundingBox,TreeConfiguration)
- Boolean lambda$place$11(WorldGenLevel,Set,Set,BoundingBox)
- void lambda$doPlace$6(TreeConfiguration,WorldGenLevel,BiConsumer,Random,int,int,int,FoliagePlacer$FoliageAttachment)
+ void lambda$doPlace$6(TreeConfiguration,WorldGenLevel,Random,int,int,int,Set,BoundingBox,FoliagePlacer$FoliageAttachment)
- void lambda$place$10(WorldGenLevel,BiConsumer,Random,List,List,TreeDecorator)
- void lambda$place$7(Set,WorldGenLevel,BlockPos,BlockState)
+ void lambda$place$7(WorldGenLevel,Random,List,List,Set,BoundingBox,TreeDecorator)
- void lambda$place$8(Set,WorldGenLevel,BlockPos,BlockState)
- void lambda$place$9(Set,WorldGenLevel,BlockPos,BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.CountConfiguration
</summary>

```diff
- IntProvider count()
+ UniformInt count()
- void <init>(IntProvider)
+ void <init>(UniformInt)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.DiskConfiguration
</summary>

```diff
- IntProvider lambda$null$1(DiskConfiguration)
+ UniformInt lambda$null$1(DiskConfiguration)
- void <init>(BlockState,IntProvider,int,List)
+ void <init>(BlockState,UniformInt,int,List)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.GrowingPlantConfiguration
</summary>

```diff
- SimpleWeightedRandomList lambda$null$0(GrowingPlantConfiguration)
- void <init>(SimpleWeightedRandomList,Direction,BlockStateProvider,BlockStateProvider,boolean)
+ void <init>(UniformInt,Direction,BlockStateProvider,BlockStateProvider,boolean)
+ void <init>(WeightedList,Direction,BlockStateProvider,BlockStateProvider,boolean)
+ WeightedList lambda$null$0(GrowingPlantConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.LargeDripstoneConfiguration
</summary>

```diff
+ FloatProvider lambda$null$2(LargeDripstoneConfiguration)
- FloatProvider lambda$null$2(LargeDripstoneConfiguration)
+ FloatProvider lambda$null$4(LargeDripstoneConfiguration)
- FloatProvider lambda$null$4(LargeDripstoneConfiguration)
+ FloatProvider lambda$null$5(LargeDripstoneConfiguration)
- FloatProvider lambda$null$5(LargeDripstoneConfiguration)
+ FloatProvider lambda$null$6(LargeDripstoneConfiguration)
- FloatProvider lambda$null$6(LargeDripstoneConfiguration)
- IntProvider lambda$null$1(LargeDripstoneConfiguration)
+ UniformInt lambda$null$1(LargeDripstoneConfiguration)
- void <init>(int,IntProvider,FloatProvider,float,FloatProvider,FloatProvider,FloatProvider,int,float)
+ void <init>(int,UniformInt,FloatProvider,float,FloatProvider,FloatProvider,FloatProvider,int,float)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.AcaciaFoliagePlacer
</summary>

```diff
- void <init>(IntProvider,IntProvider)
+ void <init>(UniformInt,UniformInt)
- void createFoliage(LevelSimulatedReader,BiConsumer,Random,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,int)
+ void createFoliage(LevelSimulatedRW,Random,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,Set,int,BoundingBox)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.BushFoliagePlacer
</summary>

```diff
- void <init>(IntProvider,IntProvider,int)
+ void <init>(UniformInt,UniformInt,int)
- void createFoliage(LevelSimulatedReader,BiConsumer,Random,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,int)
+ void createFoliage(LevelSimulatedRW,Random,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,Set,int,BoundingBox)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.FancyFoliagePlacer
</summary>

```diff
- void <init>(IntProvider,IntProvider,int)
+ void <init>(UniformInt,UniformInt,int)
- void createFoliage(LevelSimulatedReader,BiConsumer,Random,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,int)
+ void createFoliage(LevelSimulatedRW,Random,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,Set,int,BoundingBox)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer$FoliageAttachment
</summary>

```diff
+ BlockPos foliagePos()
- BlockPos pos()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.MegaJungleFoliagePlacer
</summary>

```diff
- void <init>(IntProvider,IntProvider,int)
+ void <init>(UniformInt,UniformInt,int)
- void createFoliage(LevelSimulatedReader,BiConsumer,Random,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,int)
+ void createFoliage(LevelSimulatedRW,Random,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,Set,int,BoundingBox)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.PineFoliagePlacer
</summary>

```diff
- IntProvider lambda$null$0(PineFoliagePlacer)
+ UniformInt lambda$null$0(PineFoliagePlacer)
- void <init>(IntProvider,IntProvider,IntProvider)
+ void <init>(UniformInt,UniformInt,UniformInt)
- void createFoliage(LevelSimulatedReader,BiConsumer,Random,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,int)
+ void createFoliage(LevelSimulatedRW,Random,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,Set,int,BoundingBox)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.SpruceFoliagePlacer
</summary>

```diff
- IntProvider lambda$null$0(SpruceFoliagePlacer)
+ UniformInt lambda$null$0(SpruceFoliagePlacer)
- void <init>(IntProvider,IntProvider,IntProvider)
+ void <init>(UniformInt,UniformInt,UniformInt)
- void createFoliage(LevelSimulatedReader,BiConsumer,Random,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,int)
+ void createFoliage(LevelSimulatedRW,Random,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,Set,int,BoundingBox)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.stateproviders.WeightedStateProvider
</summary>

```diff
- DataResult create(SimpleWeightedRandomList)
+ DataResult create(WeightedList)
- SimpleWeightedRandomList lambda$static$0(WeightedStateProvider)
+ void <init>()
- void <init>(SimpleWeightedRandomList)
- void <init>(SimpleWeightedRandomList$Builder)
+ void <init>(WeightedList)
+ WeightedList lambda$static$0(WeightedStateProvider)
+ WeightedStateProvider add(BlockState,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.treedecorators.AlterGroundDecorator
</summary>

```diff
- void lambda$place$2(LevelSimulatedReader,BiConsumer,Random,BlockPos)
+ void lambda$place$2(WorldGenLevel,Random,BlockPos)
- void place(LevelSimulatedReader,BiConsumer,Random,List,List)
+ void place(WorldGenLevel,Random,List,List,Set,BoundingBox)
- void placeBlockAt(LevelSimulatedReader,BiConsumer,Random,BlockPos)
+ void placeBlockAt(LevelSimulatedRW,Random,BlockPos)
- void placeCircle(LevelSimulatedReader,BiConsumer,Random,BlockPos)
+ void placeCircle(LevelSimulatedRW,Random,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.treedecorators.CocoaDecorator
</summary>

```diff
- void lambda$place$2(Random,LevelSimulatedReader,BiConsumer,BlockPos)
+ void lambda$place$2(Random,WorldGenLevel,Set,BoundingBox,BlockPos)
- void place(LevelSimulatedReader,BiConsumer,Random,List,List)
+ void place(WorldGenLevel,Random,List,List,Set,BoundingBox)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecorator
</summary>

```diff
- void placeVine(BiConsumer,BlockPos,BooleanProperty)
+ void placeVine(LevelWriter,BlockPos,BooleanProperty,Set,BoundingBox)
+ void setBlock(LevelWriter,BlockPos,BlockState,Set,BoundingBox)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.treedecorators.TrunkVineDecorator
</summary>

```diff
- void lambda$place$1(Random,LevelSimulatedReader,BiConsumer,BlockPos)
+ void lambda$place$1(Random,WorldGenLevel,Set,BoundingBox,BlockPos)
- void place(LevelSimulatedReader,BiConsumer,Random,List,List)
+ void place(WorldGenLevel,Random,List,List,Set,BoundingBox)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.trunkplacers.BendingTrunkPlacer
</summary>

```diff
- IntProvider lambda$null$1(BendingTrunkPlacer)
- List placeTrunk(LevelSimulatedReader,BiConsumer,Random,int,BlockPos,TreeConfiguration)
+ List placeTrunk(LevelSimulatedRW,Random,int,BlockPos,Set,BoundingBox,TreeConfiguration)
+ UniformInt lambda$null$1(BendingTrunkPlacer)
- void <init>(int,int,int,int,IntProvider)
+ void <init>(int,int,int,int,UniformInt)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.trunkplacers.FancyTrunkPlacer
</summary>

```diff
- BlockState lambda$makeLimb$1(BlockPos,BlockPos,BlockState)
- boolean makeLimb(LevelSimulatedReader,BiConsumer,Random,BlockPos,BlockPos,boolean,TreeConfiguration)
+ boolean makeLimb(LevelSimulatedRW,Random,BlockPos,BlockPos,boolean,Set,BoundingBox,TreeConfiguration)
- List placeTrunk(LevelSimulatedReader,BiConsumer,Random,int,BlockPos,TreeConfiguration)
+ List placeTrunk(LevelSimulatedRW,Random,int,BlockPos,Set,BoundingBox,TreeConfiguration)
- void makeBranches(LevelSimulatedReader,BiConsumer,Random,int,BlockPos,List,TreeConfiguration)
+ void makeBranches(LevelSimulatedRW,Random,int,BlockPos,List,Set,BoundingBox,TreeConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.trunkplacers.ForkingTrunkPlacer
</summary>

```diff
- List placeTrunk(LevelSimulatedReader,BiConsumer,Random,int,BlockPos,TreeConfiguration)
+ List placeTrunk(LevelSimulatedRW,Random,int,BlockPos,Set,BoundingBox,TreeConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.trunkplacers.MegaJungleTrunkPlacer
</summary>

```diff
- List placeTrunk(LevelSimulatedReader,BiConsumer,Random,int,BlockPos,TreeConfiguration)
+ List placeTrunk(LevelSimulatedRW,Random,int,BlockPos,Set,BoundingBox,TreeConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.trunkplacers.TrunkPlacer
</summary>

```diff
- boolean placeLog(LevelSimulatedReader,BiConsumer,Random,BlockPos,TreeConfiguration,Function)
- boolean placeLog(LevelSimulatedReader,BiConsumer,Random,BlockPos,TreeConfiguration)
+ boolean placeLog(LevelSimulatedRW,Random,BlockPos,Set,BoundingBox,TreeConfiguration)
- void placeLogIfFree(LevelSimulatedReader,BiConsumer,Random,BlockPos$MutableBlockPos,TreeConfiguration)
+ void placeLogIfFree(LevelSimulatedRW,Random,BlockPos$MutableBlockPos,Set,BoundingBox,TreeConfiguration)
+ void setBlock(LevelWriter,BlockPos,BlockState,BoundingBox)
- void setDirtAt(LevelSimulatedReader,BiConsumer,Random,BlockPos,TreeConfiguration)
+ void setDirtAt(LevelSimulatedRW,Random,BlockPos,TreeConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.EndCityPieces
</summary>

```diff
- boolean access$300(StructureManager,EndCityPieces$SectionGenerator,int,EndCityPieces$EndCityPiece,BlockPos,List,Random)
+ boolean access$500(StructureManager,EndCityPieces$SectionGenerator,int,EndCityPieces$EndCityPiece,BlockPos,List,Random)
- EndCityPieces$EndCityPiece access$000(StructureManager,EndCityPieces$EndCityPiece,BlockPos,String,Rotation,boolean)
- EndCityPieces$EndCityPiece access$100(List,EndCityPieces$EndCityPiece)
+ EndCityPieces$EndCityPiece access$200(StructureManager,EndCityPieces$EndCityPiece,BlockPos,String,Rotation,boolean)
+ EndCityPieces$EndCityPiece access$300(List,EndCityPieces$EndCityPiece)
- EndCityPieces$SectionGenerator access$200()
+ EndCityPieces$SectionGenerator access$400()
- EndCityPieces$SectionGenerator access$500()
- EndCityPieces$SectionGenerator access$600()
+ EndCityPieces$SectionGenerator access$800()
+ EndCityPieces$SectionGenerator access$900()
+ List access$1000()
- List access$400()
+ List access$600()
- List access$800()
+ StructurePlaceSettings access$000()
+ StructurePlaceSettings access$100()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.IglooPieces$IglooPiece
</summary>

```diff
- BlockPos makePosition(ResourceLocation,BlockPos,int)
- StructurePlaceSettings lambda$new$0(CompoundTag,ResourceLocation)
- StructurePlaceSettings makeSettings(Rotation,ResourceLocation)
+ void loadTemplate(StructureManager)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftCrossing
</summary>

```diff
+ BoundingBox findCrossing(List,Random,int,int,int,Direction)
- BoundingBox findCrossing(StructurePieceAccessor,Random,int,int,int,Direction)
+ void addChildren(StructurePiece,List,Random)
- void addChildren(StructurePiece,StructurePieceAccessor,Random)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftRoom
</summary>

```diff
+ void addChildren(StructurePiece,List,Random)
- void addChildren(StructurePiece,StructurePieceAccessor,Random)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherBridgePieces
</summary>

```diff
+ NetherBridgePieces$NetherBridgePiece access$000(NetherBridgePieces$PieceWeight,List,Random,int,int,int,Direction,int)
- NetherBridgePieces$NetherBridgePiece access$000(NetherBridgePieces$PieceWeight,StructurePieceAccessor,Random,int,int,int,Direction,int)
+ NetherBridgePieces$NetherBridgePiece findAndCreateBridgePieceFactory(NetherBridgePieces$PieceWeight,List,Random,int,int,int,Direction,int)
- NetherBridgePieces$NetherBridgePiece findAndCreateBridgePieceFactory(NetherBridgePieces$PieceWeight,StructurePieceAccessor,Random,int,int,int,Direction,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherBridgePieces$BridgeCrossing
</summary>

```diff
+ NetherBridgePieces$BridgeCrossing createPiece(List,int,int,int,Direction,int)
- NetherBridgePieces$BridgeCrossing createPiece(StructurePieceAccessor,int,int,int,Direction,int)
- void <init>(int,int,Direction)
+ void <init>(Random,int,int)
+ void addChildren(StructurePiece,List,Random)
- void addChildren(StructurePiece,StructurePieceAccessor,Random)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherBridgePieces$BridgeStraight
</summary>

```diff
+ NetherBridgePieces$BridgeStraight createPiece(List,Random,int,int,int,Direction,int)
- NetherBridgePieces$BridgeStraight createPiece(StructurePieceAccessor,Random,int,int,int,Direction,int)
+ void addChildren(StructurePiece,List,Random)
- void addChildren(StructurePiece,StructurePieceAccessor,Random)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleCorridorTBalconyPiece
</summary>

```diff
+ NetherBridgePieces$CastleCorridorTBalconyPiece createPiece(List,int,int,int,Direction,int)
- NetherBridgePieces$CastleCorridorTBalconyPiece createPiece(StructurePieceAccessor,int,int,int,Direction,int)
+ void addChildren(StructurePiece,List,Random)
- void addChildren(StructurePiece,StructurePieceAccessor,Random)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorCrossingPiece
</summary>

```diff
+ NetherBridgePieces$CastleSmallCorridorCrossingPiece createPiece(List,int,int,int,Direction,int)
- NetherBridgePieces$CastleSmallCorridorCrossingPiece createPiece(StructurePieceAccessor,int,int,int,Direction,int)
+ void addChildren(StructurePiece,List,Random)
- void addChildren(StructurePiece,StructurePieceAccessor,Random)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorPiece
</summary>

```diff
+ NetherBridgePieces$CastleSmallCorridorPiece createPiece(List,int,int,int,Direction,int)
- NetherBridgePieces$CastleSmallCorridorPiece createPiece(StructurePieceAccessor,int,int,int,Direction,int)
+ void addChildren(StructurePiece,List,Random)
- void addChildren(StructurePiece,StructurePieceAccessor,Random)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleStalkRoom
</summary>

```diff
+ NetherBridgePieces$CastleStalkRoom createPiece(List,int,int,int,Direction,int)
- NetherBridgePieces$CastleStalkRoom createPiece(StructurePieceAccessor,int,int,int,Direction,int)
+ void addChildren(StructurePiece,List,Random)
- void addChildren(StructurePiece,StructurePieceAccessor,Random)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherBridgePieces$NetherBridgePiece
</summary>

```diff
+ NetherBridgePieces$NetherBridgePiece generatePiece(NetherBridgePieces$StartPiece,List,List,Random,int,int,int,Direction,int)
- NetherBridgePieces$NetherBridgePiece generatePiece(NetherBridgePieces$StartPiece,List,StructurePieceAccessor,Random,int,int,int,Direction,int)
+ StructurePiece generateAndAddPiece(NetherBridgePieces$StartPiece,List,Random,int,int,int,Direction,int,boolean)
- StructurePiece generateAndAddPiece(NetherBridgePieces$StartPiece,StructurePieceAccessor,Random,int,int,int,Direction,int,boolean)
+ StructurePiece generateChildForward(NetherBridgePieces$StartPiece,List,Random,int,int,boolean)
- StructurePiece generateChildForward(NetherBridgePieces$StartPiece,StructurePieceAccessor,Random,int,int,boolean)
+ StructurePiece generateChildLeft(NetherBridgePieces$StartPiece,List,Random,int,int,boolean)
- StructurePiece generateChildLeft(NetherBridgePieces$StartPiece,StructurePieceAccessor,Random,int,int,boolean)
+ StructurePiece generateChildRight(NetherBridgePieces$StartPiece,List,Random,int,int,boolean)
- StructurePiece generateChildRight(NetherBridgePieces$StartPiece,StructurePieceAccessor,Random,int,int,boolean)
- void <init>(StructurePieceType,int,BoundingBox)
+ void <init>(StructurePieceType,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherBridgePieces$RoomCrossing
</summary>

```diff
+ NetherBridgePieces$RoomCrossing createPiece(List,int,int,int,Direction,int)
- NetherBridgePieces$RoomCrossing createPiece(StructurePieceAccessor,int,int,int,Direction,int)
+ void addChildren(StructurePiece,List,Random)
- void addChildren(StructurePiece,StructurePieceAccessor,Random)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherFossilFeature$FeatureStart
</summary>

```diff
+ void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
- void <init>(StructureFeature,ChunkPos,int,long)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherFossilPieces$NetherFossilPiece
</summary>

```diff
- StructurePlaceSettings lambda$new$0(CompoundTag,ResourceLocation)
- StructurePlaceSettings makeSettings(Rotation)
+ void loadTemplate(StructureManager)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.StructureStart
</summary>

```diff
- boolean hasNoPieces()
- boolean isInsidePiece(BlockPos)
- IllegalStateException lambda$getBoundingBox$0()
- StructurePiece findCollisionPiece(BoundingBox)
- StructurePiece findCollisionPiece(List,BoundingBox)
+ void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
- void <init>(StructureFeature,ChunkPos,int,long)
- void addPiece(StructurePiece)
+ void calculateBoundingBox()
- void clearPieces()
- void invalidateCache()
+ void lambda$createTag$0(CompoundTag,Tag)
- void offsetPiecesVertically(int)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$WoodlandMansionPiece
</summary>

```diff
- ResourceLocation makeLocation(String)
- ResourceLocation makeTemplateLocation()
- StructurePlaceSettings lambda$new$0(CompoundTag,ResourceLocation)
- StructurePlaceSettings makeSettings(Mirror,Rotation)
+ void loadTemplate(StructureManager)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
- net.minecraft.package-info
- XXX.ai.behavior.AnimalPanic
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
+ XXX.ai.behavior.CountDownTemptationTicks
- XXX.ai.behavior.CrossbowAttack
+ XXX.ai.behavior.CrossbowAttack$CrossbowState
- XXX.ai.behavior.DismountOrSkipMounting
+ XXX.ai.behavior.DoNothing
- XXX.ai.behavior.EntityTracker
+ XXX.ai.behavior.EraseMemoryIf
- XXX.ai.behavior.FollowTemptation
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
- XXX.ai.behavior.LongJumpMidJump
- XXX.ai.behavior.LongJumpToRandomPos$PossibleJump
- XXX.ai.behavior.ShufflingList$1
- XXX.ai.behavior.ShufflingList$WeightedEntry$1
+ XXX.ai.behavior.WeightedList$1
+ XXX.ai.behavior.WeightedList$WeightedEntry$1
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
+ XXX.ai.goal.TakeFlowerGoal
- XXX.ai.goal.TemptGoal
+ XXX.ai.goal.TradeWithPlayerGoal
- XXX.ai.goal.TryFindWaterGoal
+ XXX.ai.goal.UseItemGoal
- XXX.ai.goal.WaterAvoidingRandomFlyingGoal
+ XXX.ai.goal.WaterAvoidingRandomStrollGoal
- XXX.ai.goal.WrappedGoal
+ XXX.ai.goal.ZombieAttackGoal
- XXX.ai.gossip.GossipContainer
+ XXX.ai.gossip.GossipContainer$1
- XXX.ai.gossip.GossipContainer$EntityGossips
+ XXX.ai.gossip.GossipContainer$GossipEntry
- XXX.ai.gossip.GossipType
+ XXX.ai.gossip.package-info
- XXX.ai.memory.ExpirableValue
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
- XXX.ai.sensing.AdultSensor
+ XXX.ai.sensing.AxolotlHostileSensor
- XXX.ai.sensing.DummySensor
+ XXX.ai.sensing.GolemSensor
- XXX.ai.sensing.HoglinSpecificSensor
+ XXX.ai.sensing.HostilesSensor
- XXX.ai.sensing.package-info
- XXX.ai.sensing.PiglinBruteSpecificSensor
+ XXX.ai.sensing.PiglinSpecificSensor
- XXX.ai.sensing.PlayerSensor
+ XXX.ai.sensing.SecondaryPoiSensor
- XXX.ai.sensing.Sensing
+ XXX.ai.sensing.Sensor
- XXX.ai.sensing.SensorType
+ XXX.ai.sensing.TemptingSensor
- XXX.ai.sensing.VillagerBabiesSensor
+ XXX.ai.sensing.VillagerHostilesSensor
- XXX.ai.targeting.package-info
+ XXX.ai.targeting.TargetingConditions
+ XXX.ai.util.AirAndWaterRandomPos
- XXX.ai.util.AirRandomPos
+ XXX.ai.util.DefaultRandomPos
- XXX.ai.util.GoalUtils
+ XXX.ai.util.HoverRandomPos
- XXX.ai.util.LandRandomPos
- XXX.ai.util.package-info
+ XXX.ai.util.RandomPos
+ XXX.ai.village.package-info
+ XXX.ai.village.ReputationEventType
- XXX.ai.village.ReputationEventType$1
+ XXX.ai.village.VillageSiege
- XXX.ai.village.VillageSiege$State
+ XXX.animal.axolotl.Axolotl
- XXX.animal.axolotl.Axolotl$AxolotlGroupData
+ XXX.animal.axolotl.Axolotl$AxolotlLookControl
- XXX.animal.axolotl.Axolotl$AxolotlMoveControl
+ XXX.animal.axolotl.Axolotl$AxolotlPathNavigation
- XXX.animal.axolotl.Axolotl$Variant
+ XXX.animal.axolotl.AxolotlAi
- XXX.animal.axolotl.package-info
- XXX.animal.axolotl.PlayDead
+ XXX.animal.axolotl.ValidatePlayDead
- XXX.animal.goat.GoatAi
- XXX.arguments.blocks.BlockInput
+ XXX.arguments.blocks.BlockPredicateArgument
- XXX.arguments.blocks.BlockPredicateArgument$1
+ XXX.arguments.blocks.BlockPredicateArgument$BlockPredicate
- XXX.arguments.blocks.BlockPredicateArgument$Result
+ XXX.arguments.blocks.BlockPredicateArgument$TagPredicate
- XXX.arguments.blocks.BlockStateArgument
+ XXX.arguments.blocks.BlockStateParser
- XXX.arguments.blocks.package-info
+ XXX.arguments.coordinates.BlockPosArgument
- XXX.arguments.coordinates.ColumnPosArgument
+ XXX.arguments.coordinates.Coordinates
- XXX.arguments.coordinates.LocalCoordinates
+ XXX.arguments.coordinates.package-info
+ XXX.arguments.coordinates.RotationArgument
- XXX.arguments.coordinates.SwizzleArgument
+ XXX.arguments.coordinates.Vec2Argument
- XXX.arguments.coordinates.Vec3Argument
+ XXX.arguments.coordinates.WorldCoordinate
- XXX.arguments.coordinates.WorldCoordinates
- XXX.arguments.item.FunctionArgument
+ XXX.arguments.item.FunctionArgument$1
- XXX.arguments.item.FunctionArgument$2
+ XXX.arguments.item.FunctionArgument$Result
- XXX.arguments.item.ItemArgument
+ XXX.arguments.item.ItemInput
- XXX.arguments.item.ItemParser
+ XXX.arguments.item.ItemPredicateArgument
- XXX.arguments.item.ItemPredicateArgument$ItemPredicate
+ XXX.arguments.item.ItemPredicateArgument$Result
- XXX.arguments.item.ItemPredicateArgument$TagPredicate
+ XXX.arguments.item.package-info
+ XXX.arguments.selector.EntitySelector
- XXX.arguments.selector.EntitySelector$1
+ XXX.arguments.selector.EntitySelectorParser
+ XXX.arguments.selector.package-info
- XXX.blaze3d.audio.Channel
+ XXX.blaze3d.audio.Library
- XXX.blaze3d.audio.Library$1
+ XXX.blaze3d.audio.Library$ChannelPool
- XXX.blaze3d.audio.Library$CountingChannelPool
+ XXX.blaze3d.audio.Library$Pool
- XXX.blaze3d.audio.Listener
+ XXX.blaze3d.audio.OggAudioStream
- XXX.blaze3d.audio.OggAudioStream$OutputConcat
+ XXX.blaze3d.audio.OpenAlUtil
- XXX.blaze3d.audio.SoundBuffer
- XXX.blaze3d.font.package-info
- XXX.blaze3d.platform.ClipboardManager
+ XXX.blaze3d.platform.DebugMemoryUntracker
- XXX.blaze3d.platform.DisplayData
- XXX.blaze3d.platform.GlConst
+ XXX.blaze3d.platform.GLX
- XXX.blaze3d.platform.package-info
- XXX.blaze3d.preprocessor.GlslPreprocessor$1
- XXX.blaze3d.preprocessor.package-info
+ XXX.blaze3d.shaders.AbstractUniform
- XXX.blaze3d.shaders.BlendMode
+ XXX.blaze3d.shaders.Effect
- XXX.blaze3d.shaders.EffectProgram
+ XXX.blaze3d.shaders.EffectProgram$1
- XXX.blaze3d.shaders.Program
+ XXX.blaze3d.shaders.Program$Type
- XXX.blaze3d.shaders.ProgramManager
+ XXX.blaze3d.shaders.Shader
- XXX.blaze3d.shaders.Uniform
- XXX.blaze3d.systems.package-info
+ XXX.blaze3d.vertex.BufferBuilder
- XXX.blaze3d.vertex.BufferBuilder$1
+ XXX.blaze3d.vertex.BufferBuilder$DrawState
- XXX.blaze3d.vertex.BufferBuilder$SortState
+ XXX.blaze3d.vertex.BufferUploader
- XXX.blaze3d.vertex.BufferVertexConsumer
- XXX.blaze3d.vertex.DefaultedVertexConsumer
+ XXX.blaze3d.vertex.DefaultVertexFormat
- XXX.blaze3d.vertex.package-info
+ XXX.blaze3d.vertex.PoseStack
- XXX.blaze3d.vertex.PoseStack$1
+ XXX.blaze3d.vertex.PoseStack$Pose
- XXX.blaze3d.vertex.SheetedDecalTextureGenerator
+ XXX.blaze3d.vertex.Tesselator
- XXX.blaze3d.vertex.VertexBuffer
+ XXX.blaze3d.vertex.VertexConsumer
- XXX.blaze3d.vertex.VertexFormat
+ XXX.blaze3d.vertex.VertexFormat$1
- XXX.blaze3d.vertex.VertexFormat$IndexType
+ XXX.blaze3d.vertex.VertexFormat$Mode
- XXX.blaze3d.vertex.VertexFormatElement
+ XXX.blaze3d.vertex.VertexFormatElement$Type
- XXX.blaze3d.vertex.VertexFormatElement$Usage
+ XXX.blaze3d.vertex.VertexFormatElement$Usage$ClearState
- XXX.blaze3d.vertex.VertexFormatElement$Usage$SetupState
+ XXX.blaze3d.vertex.VertexMultiConsumer
- XXX.blaze3d.vertex.VertexMultiConsumer$Double
- XXX.block.entity.AbstractFurnaceBlockEntity
+ XXX.block.entity.AbstractFurnaceBlockEntity$1
- XXX.block.entity.BannerBlockEntity
+ XXX.block.entity.BannerPattern
- XXX.block.entity.BannerPattern$Builder
+ XXX.block.entity.BarrelBlockEntity
- XXX.block.entity.BarrelBlockEntity$1
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
+ XXX.block.entity.BellBlockEntity$ResonationEndAction
- XXX.block.entity.BlastFurnaceBlockEntity
+ XXX.block.entity.BlockEntity
- XXX.block.entity.BlockEntityTicker
+ XXX.block.entity.BlockEntityType
- XXX.block.entity.BlockEntityType$BlockEntitySupplier
+ XXX.block.entity.BlockEntityType$Builder
- XXX.block.entity.BrewingStandBlockEntity
+ XXX.block.entity.BrewingStandBlockEntity$1
- XXX.block.entity.CampfireBlockEntity
+ XXX.block.entity.ChestBlockEntity
- XXX.block.entity.ChestBlockEntity$1
+ XXX.block.entity.ChestLidController
- XXX.block.entity.CommandBlockEntity
+ XXX.block.entity.CommandBlockEntity$1
- XXX.block.entity.CommandBlockEntity$Mode
+ XXX.block.entity.ComparatorBlockEntity
- XXX.block.entity.ConduitBlockEntity
+ XXX.block.entity.ContainerOpenersCounter
- XXX.block.entity.DaylightDetectorBlockEntity
+ XXX.block.entity.DispenserBlockEntity
- XXX.block.entity.DropperBlockEntity
+ XXX.block.entity.EnchantmentTableBlockEntity
- XXX.block.entity.EnderChestBlockEntity
+ XXX.block.entity.EnderChestBlockEntity$1
- XXX.block.entity.FurnaceBlockEntity
+ XXX.block.entity.Hopper
- XXX.block.entity.HopperBlockEntity
+ XXX.block.entity.JigsawBlockEntity
- XXX.block.entity.JigsawBlockEntity$JointType
+ XXX.block.entity.JukeboxBlockEntity
- XXX.block.entity.LecternBlockEntity
+ XXX.block.entity.LecternBlockEntity$1
- XXX.block.entity.LecternBlockEntity$2
+ XXX.block.entity.LidBlockEntity
- XXX.block.entity.package-info
- XXX.block.entity.RandomizableContainerBlockEntity
+ XXX.block.entity.SculkSensorBlockEntity
- XXX.block.entity.ShulkerBoxBlockEntity
+ XXX.block.entity.ShulkerBoxBlockEntity$1
- XXX.block.entity.ShulkerBoxBlockEntity$AnimationStatus
+ XXX.block.entity.SignBlockEntity
- XXX.block.entity.SkullBlockEntity
+ XXX.block.entity.SmokerBlockEntity
- XXX.block.entity.SpawnerBlockEntity
+ XXX.block.entity.SpawnerBlockEntity$1
- XXX.block.entity.StructureBlockEntity
+ XXX.block.entity.StructureBlockEntity$UpdateType
- XXX.block.entity.TheEndGatewayBlockEntity
+ XXX.block.entity.TheEndPortalBlockEntity
- XXX.block.entity.TickingBlockEntity
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
+ XXX.block.model.ItemOverride$Predicate
- XXX.block.model.ItemOverrides
+ XXX.block.model.ItemOverrides$1
- XXX.block.model.ItemOverrides$BakedOverride
+ XXX.block.model.ItemOverrides$PropertyMatcher
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
+ XXX.block.piston.MovingPistonBlock
+ XXX.block.piston.package-info
- XXX.block.piston.PistonBaseBlock
+ XXX.block.piston.PistonBaseBlock$1
- XXX.block.piston.PistonHeadBlock
+ XXX.block.piston.PistonHeadBlock$1
- XXX.block.piston.PistonMath
+ XXX.block.piston.PistonMath$1
- XXX.block.piston.PistonMovingBlockEntity
+ XXX.block.piston.PistonMovingBlockEntity$1
- XXX.block.piston.PistonStructureResolver
- XXX.block.state.BlockBehaviour
+ XXX.block.state.BlockBehaviour$1
- XXX.block.state.BlockBehaviour$BlockStateBase
+ XXX.block.state.BlockBehaviour$BlockStateBase$Cache
- XXX.block.state.BlockBehaviour$OffsetType
+ XXX.block.state.BlockBehaviour$Properties
- XXX.block.state.BlockBehaviour$StateArgumentPredicate
+ XXX.block.state.BlockBehaviour$StatePredicate
- XXX.block.state.BlockState
- XXX.block.state.package-info
+ XXX.block.state.StateDefinition
- XXX.block.state.StateDefinition$Builder
+ XXX.block.state.StateDefinition$Factory
- XXX.block.state.StateHolder
+ XXX.block.state.StateHolder$1
+ XXX.block.statemap.package-info
- XXX.chunk.storage.ChunkSerializer
+ XXX.chunk.storage.ChunkStorage
- XXX.chunk.storage.EntityStorage
+ XXX.chunk.storage.IOWorker
- XXX.chunk.storage.IOWorker$PendingStore
+ XXX.chunk.storage.IOWorker$Priority
- XXX.chunk.storage.OldChunkStorage
+ XXX.chunk.storage.OldChunkStorage$1
- XXX.chunk.storage.OldChunkStorage$OldLevelChunk
+ XXX.chunk.storage.package-info
+ XXX.chunk.storage.RegionBitmap
- XXX.chunk.storage.RegionFile
+ XXX.chunk.storage.RegionFile$ChunkBuffer
- XXX.chunk.storage.RegionFile$CommitOp
+ XXX.chunk.storage.RegionFileStorage
- XXX.chunk.storage.RegionFileVersion
+ XXX.chunk.storage.RegionFileVersion$StreamWrapper
- XXX.chunk.storage.SectionStorage
+ XXX.client.map.Map$1
+ XXX.client.map.Map$3
+ XXX.client.model.AbstractZombieModel
- XXX.client.model.AgeableListModel
+ XXX.client.model.AnimationUtils
- XXX.client.model.ArmedModel
+ XXX.client.model.ArmorStandArmorModel
- XXX.client.model.ArmorStandModel
+ XXX.client.model.AxolotlModel
- XXX.client.model.BatModel
+ XXX.client.model.BeeModel
- XXX.client.model.BlazeModel
+ XXX.client.model.BoatModel
- XXX.client.model.BookModel
+ XXX.client.model.CatModel
- XXX.client.model.ChestedHorseModel
+ XXX.client.model.ChickenModel
- XXX.client.model.CodModel
+ XXX.client.model.ColorableAgeableListModel
- XXX.client.model.ColorableHierarchicalModel
+ XXX.client.model.CowModel
- XXX.client.model.CreeperModel
+ XXX.client.model.DolphinModel
- XXX.client.model.DrownedModel
+ XXX.client.model.ElytraModel
- XXX.client.model.EndermanModel
+ XXX.client.model.EndermiteModel
- XXX.client.model.EntityModel
+ XXX.client.model.EvokerFangsModel
- XXX.client.model.FoxModel
+ XXX.client.model.GhastModel
- XXX.client.model.GiantZombieModel
- XXX.client.multiplayer.ClientPacketListener
+ XXX.client.multiplayer.ClientPacketListener$1
- XXX.client.multiplayer.ClientSuggestionProvider
+ XXX.client.multiplayer.MultiPlayerGameMode
+ XXX.client.multiplayer.package-info
- XXX.client.multiplayer.PlayerInfo
+ XXX.client.multiplayer.ServerAddress
- XXX.client.multiplayer.ServerData
+ XXX.client.multiplayer.ServerData$ServerPackStatus
- XXX.client.multiplayer.ServerList
+ XXX.client.multiplayer.ServerStatusPinger
- XXX.client.multiplayer.ServerStatusPinger$1
+ XXX.client.multiplayer.ServerStatusPinger$2
- XXX.client.multiplayer.ServerStatusPinger$2$1
+ XXX.client.particle.AshParticle
- XXX.client.particle.AshParticle$Provider
+ XXX.client.particle.AttackSweepParticle
- XXX.client.particle.AttackSweepParticle$1
+ XXX.client.particle.AttackSweepParticle$Provider
+ XXX.client.particle.BarrierParticle$1
- XXX.client.particle.StationaryItemParticle
- XXX.client.particle.StationaryItemParticle$BarrierProvider
- XXX.client.renderer.package-info
+ XXX.client.resources.AssetIndex
- XXX.client.resources.ClientPackSource
+ XXX.client.resources.ClientPackSource$1
- XXX.client.resources.ClientPackSource$2
+ XXX.client.resources.DefaultClientPackResources
- XXX.client.resources.DefaultPlayerSkin
+ XXX.client.resources.DirectAssetIndex
- XXX.client.resources.FoliageColorReloadListener
+ XXX.client.resources.GrassColorReloadListener
- XXX.client.resources.LegacyPackResourcesAdapter
+ XXX.client.resources.LegacyStuffWrapper
- XXX.client.resources.MobEffectTextureManager
+ XXX.client.resources.PackResourcesAdapterV4
- XXX.client.resources.PaintingTextureManager
+ XXX.client.resources.SkinManager
- XXX.client.resources.SkinManager$1
+ XXX.client.resources.SkinManager$SkinTextureCallback
- XXX.client.resources.SplashManager
+ XXX.client.resources.TextureAtlasHolder
+ XXX.client.sounds.AudioStream
- XXX.client.sounds.ChannelAccess
+ XXX.client.sounds.ChannelAccess$ChannelHandle
- XXX.client.sounds.LoopingAudioStream
+ XXX.client.sounds.LoopingAudioStream$1
- XXX.client.sounds.LoopingAudioStream$AudioStreamProvider
+ XXX.client.sounds.LoopingAudioStream$NoCloseBuffer
- XXX.client.sounds.MusicManager
- XXX.client.sounds.package-info
+ XXX.client.sounds.SoundBufferLibrary
- XXX.client.sounds.SoundEngine
+ XXX.client.sounds.SoundEngineExecutor
- XXX.client.sounds.SoundEventListener
+ XXX.client.sounds.SoundManager
- XXX.client.sounds.SoundManager$1
+ XXX.client.sounds.SoundManager$2
- XXX.client.sounds.SoundManager$Preparations
+ XXX.client.sounds.SoundManager$Preparations$1
- XXX.client.sounds.WeighedSoundEvents
+ XXX.client.sounds.Weighted
+ XXX.client.tutorial.BundleTutorial
- XXX.client.tutorial.CompletedTutorialStepInstance
+ XXX.client.tutorial.CraftPlanksTutorialStep
- XXX.client.tutorial.FindTreeTutorialStepInstance
+ XXX.client.tutorial.MovementTutorialStepInstance
- XXX.client.tutorial.OpenInventoryTutorialStep
+ XXX.client.tutorial.package-info
+ XXX.client.tutorial.PunchTreeTutorialStepInstance
- XXX.client.tutorial.Tutorial
+ XXX.client.tutorial.Tutorial$1
- XXX.client.tutorial.Tutorial$TimedToast
+ XXX.client.tutorial.TutorialStepInstance
- XXX.client.tutorial.TutorialSteps
+ XXX.commands.arguments.AngleArgument
- XXX.commands.arguments.AngleArgument$1
+ XXX.commands.arguments.AngleArgument$SingleAngle
- XXX.commands.arguments.ColorArgument
+ XXX.commands.arguments.ComponentArgument
- XXX.commands.arguments.CompoundTagArgument
+ XXX.commands.arguments.DimensionArgument
- XXX.commands.arguments.EntityAnchorArgument
+ XXX.commands.arguments.EntityAnchorArgument$Anchor
- XXX.commands.arguments.EntityArgument
+ XXX.commands.arguments.EntityArgument$Serializer
- XXX.commands.arguments.EntitySummonArgument
+ XXX.commands.arguments.GameProfileArgument
- XXX.commands.arguments.GameProfileArgument$Result
+ XXX.commands.arguments.GameProfileArgument$SelectorResult
- XXX.commands.arguments.ItemEnchantmentArgument
+ XXX.commands.arguments.MessageArgument
- XXX.commands.arguments.MessageArgument$Message
+ XXX.commands.arguments.MessageArgument$Part
- XXX.commands.arguments.MobEffectArgument
+ XXX.commands.arguments.NbtPathArgument
- XXX.commands.arguments.NbtPathArgument$AllElementsNode
+ XXX.commands.arguments.NbtPathArgument$CompoundChildNode
- XXX.commands.arguments.NbtPathArgument$IndexedElementNode
+ XXX.commands.arguments.NbtPathArgument$MatchElementNode
- XXX.commands.arguments.NbtPathArgument$MatchObjectNode
+ XXX.commands.arguments.NbtPathArgument$MatchRootObjectNode
- XXX.commands.arguments.NbtPathArgument$NbtPath
+ XXX.commands.arguments.NbtPathArgument$Node
- XXX.commands.arguments.NbtTagArgument
+ XXX.commands.arguments.ObjectiveArgument
- XXX.commands.arguments.ObjectiveCriteriaArgument
+ XXX.commands.arguments.OperationArgument
- XXX.commands.arguments.OperationArgument$Operation
+ XXX.commands.arguments.OperationArgument$SimpleOperation
- XXX.commands.arguments.package-info
- XXX.commands.arguments.ParticleArgument
+ XXX.commands.arguments.RangeArgument
- XXX.commands.arguments.RangeArgument$Floats
+ XXX.commands.arguments.RangeArgument$Ints
- XXX.commands.arguments.ResourceLocationArgument
+ XXX.commands.arguments.ScoreboardSlotArgument
+ XXX.commands.arguments.ScoreHolderArgument
- XXX.commands.arguments.ScoreHolderArgument$Result
+ XXX.commands.arguments.ScoreHolderArgument$SelectorResult
- XXX.commands.arguments.ScoreHolderArgument$Serializer
- XXX.commands.arguments.SlotArgument
+ XXX.commands.arguments.TeamArgument
- XXX.commands.arguments.TimeArgument
+ XXX.commands.arguments.UuidArgument
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
- XXX.datafix.fixes.AbstractArrowPickupFix
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
+ XXX.datafix.fixes.CauldronRenameFix
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
+ XXX.datafix.fixes.MissingDimensionFix
- XXX.datafix.fixes.MobSpawnerEntityIdentifiersFix
+ XXX.datafix.fixes.NamedEntityFix
- XXX.datafix.fixes.NewVillageFix
+ XXX.datafix.fixes.ObjectiveDisplayNameFix
- XXX.datafix.fixes.ObjectiveRenderTypeFix
+ XXX.datafix.fixes.OminousBannerBlockEntityRenameFix
- XXX.datafix.fixes.OminousBannerRenameFix
+ XXX.datafix.fixes.OptionsAddTextBackgroundFix
- XXX.datafix.fixes.OptionsForceVBOFix
+ XXX.datafix.fixes.OptionsKeyLwjgl3Fix
- XXX.datafix.fixes.OptionsKeyTranslationFix
+ XXX.datafix.fixes.OptionsLowerCaseLanguageFix
- XXX.datafix.fixes.OptionsRenameFieldFix
- XXX.datafix.fixes.package-info
+ XXX.datafix.fixes.PlayerUUIDFix
- XXX.datafix.fixes.PoiTypeRename
+ XXX.datafix.fixes.RecipesFix
- XXX.datafix.fixes.RecipesRenameFix
+ XXX.datafix.fixes.RecipesRenameningFix
- XXX.datafix.fixes.RedstoneWireConnectionsFix
+ XXX.datafix.fixes.References
- XXX.datafix.fixes.RemoveGolemGossipFix
+ XXX.datafix.fixes.RenameBiomesFix
- XXX.datafix.fixes.RenamedCoralFansFix
+ XXX.datafix.fixes.RenamedCoralFix
- XXX.datafix.fixes.ReorganizePoi
+ XXX.datafix.fixes.SavedDataFeaturePoolElementFix
- XXX.datafix.fixes.SavedDataUUIDFix
+ XXX.datafix.fixes.SavedDataVillageCropFix
- XXX.datafix.fixes.SimpleEntityRenameFix
+ XXX.datafix.fixes.SimplestEntityRenameFix
- XXX.datafix.fixes.StatsCounterFix
+ XXX.datafix.fixes.StriderGravityFix
- XXX.datafix.fixes.StructureReferenceCountFix
+ XXX.datafix.fixes.SwimStatsRenameFix
- XXX.datafix.fixes.TeamDisplayNameFix
+ XXX.datafix.fixes.TrappedChestBlockEntityFix
- XXX.datafix.fixes.TrappedChestBlockEntityFix$TrappedChestSection
+ XXX.datafix.fixes.VillagerDataFix
- XXX.datafix.fixes.VillagerFollowRangeFix
+ XXX.datafix.fixes.VillagerRebuildLevelAndXpFix
- XXX.datafix.fixes.VillagerTradeFix
+ XXX.datafix.fixes.WallPropertyFix
- XXX.datafix.fixes.WorldGenSettingsFix
+ XXX.datafix.fixes.WorldGenSettingsFix$StructureFeatureConfiguration
- XXX.datafix.fixes.WriteAndReadFix
+ XXX.datafix.fixes.ZombieVillagerRebuildXpFix
- XXX.datafix.schemas.NamespacedSchema
+ XXX.datafix.schemas.NamespacedSchema$1
+ XXX.datafix.schemas.package-info
- XXX.datafix.schemas.V100
+ XXX.datafix.schemas.V102
- XXX.datafix.schemas.V1022
+ XXX.datafix.schemas.V106
- XXX.datafix.schemas.V107
+ XXX.datafix.schemas.V1125
- XXX.datafix.schemas.V135
+ XXX.datafix.schemas.V143
- XXX.datafix.schemas.V1451
+ XXX.datafix.schemas.V1451_1
- XXX.datafix.schemas.V1451_2
+ XXX.datafix.schemas.V1451_3
- XXX.datafix.schemas.V1451_4
+ XXX.datafix.schemas.V1451_5
- XXX.datafix.schemas.V1451_6
+ XXX.datafix.schemas.V1451_7
- XXX.datafix.schemas.V1460
+ XXX.datafix.schemas.V1460$1
- XXX.datafix.schemas.V1466
+ XXX.datafix.schemas.V1470
- XXX.datafix.schemas.V1481
+ XXX.datafix.schemas.V1483
- XXX.datafix.schemas.V1486
+ XXX.datafix.schemas.V1510
- XXX.datafix.schemas.V1800
+ XXX.datafix.schemas.V1801
- XXX.datafix.schemas.V1904
+ XXX.datafix.schemas.V1906
- XXX.datafix.schemas.V1909
+ XXX.datafix.schemas.V1920
- XXX.datafix.schemas.V1928
+ XXX.datafix.schemas.V1929
- XXX.datafix.schemas.V1931
+ XXX.datafix.schemas.V2100
- XXX.datafix.schemas.V2501
+ XXX.datafix.schemas.V2502
- XXX.datafix.schemas.V2505
+ XXX.datafix.schemas.V2509
- XXX.datafix.schemas.V2519
+ XXX.datafix.schemas.V2522
- XXX.datafix.schemas.V2551
+ XXX.datafix.schemas.V2568
- XXX.datafix.schemas.V2571
- XXX.datafix.schemas.V2704
+ XXX.datafix.schemas.V501
- XXX.datafix.schemas.V700
+ XXX.datafix.schemas.V701
- XXX.datafix.schemas.V702
+ XXX.datafix.schemas.V703
- XXX.datafix.schemas.V704
+ XXX.datafix.schemas.V704$1
- XXX.datafix.schemas.V705
+ XXX.datafix.schemas.V705$1
- XXX.datafix.schemas.V808
+ XXX.datafix.schemas.V99
- XXX.datafix.schemas.V99$1
+ XXX.entity.ai.package-info
+ XXX.entity.ambient.AmbientCreature
- XXX.entity.ambient.Bat
+ XXX.entity.ambient.package-info
- XXX.entity.animal.AbstractFish
+ XXX.entity.animal.AbstractFish$FishMoveControl
- XXX.entity.animal.AbstractFish$FishSwimGoal
+ XXX.entity.animal.AbstractGolem
- XXX.entity.animal.AbstractSchoolingFish
+ XXX.entity.animal.AbstractSchoolingFish$SchoolSpawnGroupData
- XXX.entity.animal.Animal
+ XXX.entity.animal.Bee
- XXX.entity.animal.Bee$1
+ XXX.entity.animal.Bee$BaseBeeGoal
- XXX.entity.animal.Bee$BeeAttackGoal
+ XXX.entity.animal.Bee$BeeBecomeAngryTargetGoal
- XXX.entity.animal.Bee$BeeEnterHiveGoal
+ XXX.entity.animal.Bee$BeeGoToHiveGoal
- XXX.entity.animal.Bee$BeeGoToKnownFlowerGoal
+ XXX.entity.animal.Bee$BeeGrowCropGoal
- XXX.entity.animal.Bee$BeeHurtByOtherGoal
+ XXX.entity.animal.Bee$BeeLocateHiveGoal
- XXX.entity.animal.Bee$BeeLookControl
+ XXX.entity.animal.Bee$BeePollinateGoal
- XXX.entity.animal.Bee$BeeWanderGoal
+ XXX.entity.animal.Bucketable
- XXX.entity.animal.Cat
+ XXX.entity.animal.Cat$CatAvoidEntityGoal
- XXX.entity.animal.Cat$CatRelaxOnOwnerGoal
+ XXX.entity.animal.Cat$CatTemptGoal
- XXX.entity.animal.Chicken
+ XXX.entity.animal.Cod
- XXX.entity.animal.Cow
+ XXX.entity.animal.Dolphin
- XXX.entity.animal.Dolphin$1
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
- XXX.entity.animal.IronGolem$Crackiness
+ XXX.entity.animal.MushroomCow
- XXX.entity.animal.MushroomCow$MushroomType
+ XXX.entity.animal.Ocelot
- XXX.entity.animal.Ocelot$OcelotAvoidEntityGoal
+ XXX.entity.animal.Ocelot$OcelotTemptGoal
- XXX.entity.animal.Panda
+ XXX.entity.animal.Panda$Gene
- XXX.entity.animal.Panda$PandaAttackGoal
+ XXX.entity.animal.Panda$PandaAvoidGoal
- XXX.entity.animal.Panda$PandaBreedGoal
+ XXX.entity.animal.Panda$PandaHurtByTargetGoal
- XXX.entity.animal.Panda$PandaLieOnBackGoal
+ XXX.entity.animal.Panda$PandaLookAtPlayerGoal
- XXX.entity.animal.Panda$PandaMoveControl
+ XXX.entity.animal.Panda$PandaPanicGoal
- XXX.entity.animal.Panda$PandaRollGoal
+ XXX.entity.animal.Panda$PandaSitGoal
- XXX.entity.animal.Panda$PandaSneezeGoal
+ XXX.entity.animal.Parrot
- XXX.entity.animal.Parrot$1
+ XXX.entity.animal.Pig
- XXX.entity.animal.PolarBear
+ XXX.entity.animal.PolarBear$PolarBearAttackPlayersGoal
- XXX.entity.animal.PolarBear$PolarBearHurtByTargetGoal
+ XXX.entity.animal.PolarBear$PolarBearMeleeAttackGoal
- XXX.entity.animal.PolarBear$PolarBearPanicGoal
+ XXX.entity.animal.Pufferfish
- XXX.entity.animal.Pufferfish$PufferfishPuffGoal
+ XXX.entity.animal.Rabbit
- XXX.entity.animal.Rabbit$EvilRabbitAttackGoal
+ XXX.entity.animal.Rabbit$RabbitAvoidEntityGoal
- XXX.entity.animal.Rabbit$RabbitGroupData
+ XXX.entity.animal.Rabbit$RabbitJumpControl
- XXX.entity.animal.Rabbit$RabbitMoveControl
+ XXX.entity.animal.Rabbit$RabbitPanicGoal
- XXX.entity.animal.Rabbit$RaidGardenGoal
+ XXX.entity.animal.Salmon
- XXX.entity.animal.Sheep
+ XXX.entity.animal.Sheep$1
- XXX.entity.animal.Sheep$2
+ XXX.entity.animal.ShoulderRidingEntity
- XXX.entity.animal.SnowGolem
+ XXX.entity.animal.Squid
- XXX.entity.animal.Squid$1
+ XXX.entity.animal.Squid$SquidFleeGoal
- XXX.entity.animal.Squid$SquidRandomMovementGoal
+ XXX.entity.animal.TropicalFish
- XXX.entity.animal.TropicalFish$1
+ XXX.entity.animal.TropicalFish$Pattern
- XXX.entity.animal.TropicalFish$TropicalFishGroupData
+ XXX.entity.animal.Turtle
- XXX.entity.animal.Turtle$1
+ XXX.entity.animal.Turtle$TurtleBreedGoal
- XXX.entity.animal.Turtle$TurtleGoHomeGoal
+ XXX.entity.animal.Turtle$TurtleGoToWaterGoal
- XXX.entity.animal.Turtle$TurtleLayEggGoal
+ XXX.entity.animal.Turtle$TurtleMoveControl
- XXX.entity.animal.Turtle$TurtlePanicGoal
+ XXX.entity.animal.Turtle$TurtlePathNavigation
- XXX.entity.animal.Turtle$TurtleRandomStrollGoal
+ XXX.entity.animal.Turtle$TurtleTravelGoal
- XXX.entity.animal.WaterAnimal
+ XXX.entity.animal.Wolf
- XXX.entity.animal.Wolf$WolfAvoidEntityGoal
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
- XXX.entity.layers.package-info
+ XXX.entity.layers.PandaHoldsItemLayer
- XXX.entity.layers.ParrotOnShoulderLayer
+ XXX.entity.layers.PhantomEyesLayer
- XXX.entity.layers.PlayerItemInHandLayer
+ XXX.entity.layers.RenderLayer
- XXX.entity.layers.SaddleLayer
+ XXX.entity.layers.SheepFurLayer
- XXX.entity.layers.ShulkerHeadLayer
+ XXX.entity.layers.SlimeOuterLayer
- XXX.entity.layers.SnowGolemHeadLayer
+ XXX.entity.layers.SpiderEyesLayer
- XXX.entity.layers.SpinAttackEffectLayer
+ XXX.entity.layers.StrayClothingLayer
- XXX.entity.layers.StuckInBodyLayer
+ XXX.entity.layers.TropicalFishPatternLayer
- XXX.entity.layers.VillagerProfessionLayer
+ XXX.entity.layers.WitchItemLayer
- XXX.entity.layers.WitherArmorLayer
+ XXX.entity.layers.WolfCollarLayer
+ XXX.entity.player.package-info
- XXX.entity.player.PlayerRenderer
+ XXX.goal.target.DefendVillageTargetGoal
- XXX.goal.target.HurtByTargetGoal
+ XXX.goal.target.NearestAttackableTargetGoal
- XXX.goal.target.NearestAttackableWitchTargetGoal
+ XXX.goal.target.NearestHealableRaiderTargetGoal
- XXX.goal.target.NonTameRandomTargetGoal
+ XXX.goal.target.OwnerHurtByTargetGoal
- XXX.goal.target.OwnerHurtTargetGoal
+ XXX.goal.target.package-info
+ XXX.goal.target.ResetUniversalAngerTargetGoal
- XXX.goal.target.TargetGoal
- XXX.gui.screens.package-info
- XXX.gui.screens.package-info
- XXX.gui.screens.RealmsBackupInfoScreen
+ XXX.gui.screens.RealmsBackupInfoScreen$BackupInfoList
- XXX.gui.screens.RealmsBackupInfoScreen$BackupInfoListEntry
+ XXX.gui.screens.RealmsBackupScreen
- XXX.gui.screens.RealmsBackupScreen$1
+ XXX.gui.screens.RealmsBackupScreen$BackupObjectSelectionList
- XXX.gui.screens.RealmsBackupScreen$Entry
+ XXX.gui.screens.RealmsBrokenWorldScreen
- XXX.gui.screens.RealmsClientOutdatedScreen
+ XXX.gui.screens.RealmsConfigureWorldScreen
- XXX.gui.screens.RealmsConfigureWorldScreen$1
+ XXX.gui.screens.RealmsConfirmScreen
- XXX.gui.screens.RealmsCreateRealmScreen
+ XXX.gui.screens.RealmsDownloadLatestWorldScreen
- XXX.gui.screens.RealmsDownloadLatestWorldScreen$DownloadStatus
+ XXX.gui.screens.RealmsGenericErrorScreen
- XXX.gui.screens.RealmsInviteScreen
+ XXX.gui.screens.RealmsLongConfirmationScreen
- XXX.gui.screens.RealmsLongConfirmationScreen$Type
+ XXX.gui.screens.RealmsLongRunningMcoTaskScreen
- XXX.gui.screens.RealmsNotificationsScreen
+ XXX.gui.screens.RealmsNotificationsScreen$1
- XXX.gui.screens.RealmsParentalConsentScreen
+ XXX.gui.screens.RealmsPendingInvitesScreen
- XXX.gui.screens.RealmsPendingInvitesScreen$1
+ XXX.gui.screens.RealmsPendingInvitesScreen$2
- XXX.gui.screens.RealmsPendingInvitesScreen$3
+ XXX.gui.screens.RealmsPendingInvitesScreen$Entry
- XXX.gui.screens.RealmsPendingInvitesScreen$Entry$AcceptRowButton
+ XXX.gui.screens.RealmsPendingInvitesScreen$Entry$RejectRowButton
- XXX.gui.screens.RealmsPendingInvitesScreen$PendingInvitationSelectionList
+ XXX.gui.screens.RealmsPlayerScreen
- XXX.gui.screens.RealmsPlayerScreen$Entry
+ XXX.gui.screens.RealmsPlayerScreen$InvitedObjectSelectionList
- XXX.gui.screens.RealmsPlayerScreen$UserAction
+ XXX.gui.screens.RealmsResetNormalWorldScreen
- XXX.gui.screens.RealmsResetWorldScreen
+ XXX.gui.screens.RealmsResetWorldScreen$1
- XXX.gui.screens.RealmsResetWorldScreen$FrameButton
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
- XXX.level.block.LightningRodBlock
+ XXX.level.block.LiquidBlock
- XXX.level.block.LiquidBlockContainer
+ XXX.level.block.LoomBlock
- XXX.level.block.MagmaBlock
+ XXX.level.block.MelonBlock
- XXX.level.block.Mirror
+ XXX.level.block.Mirror$1
- XXX.level.block.MossBlock
+ XXX.level.block.MultifaceBlock
- XXX.level.block.MushroomBlock
+ XXX.level.block.MyceliumBlock
- XXX.level.block.NetherPortalBlock
+ XXX.level.block.NetherPortalBlock$1
+ XXX.level.block.NetherrackBlock
- XXX.level.block.NetherSproutsBlock
+ XXX.level.block.NetherVines
- XXX.level.block.NetherWartBlock
- XXX.level.block.NoteBlock
+ XXX.level.block.NyliumBlock
- XXX.level.block.ObserverBlock
+ XXX.level.block.OreBlock
- XXX.level.block.package-info
- XXX.level.block.PipeBlock
+ XXX.level.block.PlayerHeadBlock
- XXX.level.block.PlayerWallHeadBlock
+ XXX.level.block.PointedDripstoneBlock
- XXX.level.block.PotatoBlock
+ XXX.level.block.PowderSnowBlock
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
- XXX.level.block.RespawnAnchorBlock
+ XXX.level.block.RespawnAnchorBlock$1
- XXX.level.block.RodBlock
+ XXX.level.block.RodBlock$1
- XXX.level.block.RootedDirtBlock
+ XXX.level.block.RootsBlock
- XXX.level.block.RotatedPillarBlock
+ XXX.level.block.RotatedPillarBlock$1
- XXX.level.block.Rotation
+ XXX.level.block.Rotation$1
- XXX.level.block.SandBlock
+ XXX.level.block.SaplingBlock
- XXX.level.block.ScaffoldingBlock
+ XXX.level.block.SculkSensorBlock
+ XXX.level.block.SeagrassBlock
- XXX.level.block.SeaPickleBlock
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
- XXX.level.block.SmallDripleafBlock
+ XXX.level.block.SmithingTableBlock
- XXX.level.block.SmokerBlock
+ XXX.level.block.SnowLayerBlock
- XXX.level.block.SnowLayerBlock$1
+ XXX.level.block.SnowyDirtBlock
- XXX.level.block.SoulFireBlock
+ XXX.level.block.SoulSandBlock
- XXX.level.block.SoundType
+ XXX.level.block.SpawnerBlock
- XXX.level.block.SpongeBlock
+ XXX.level.block.SporeBlossomBlock
- XXX.level.block.SpreadingSnowyDirtBlock
+ XXX.level.block.StainedGlassBlock
- XXX.level.block.StainedGlassPaneBlock
+ XXX.level.block.StairBlock
- XXX.level.block.StairBlock$1
+ XXX.level.block.StandingSignBlock
- XXX.level.block.StemBlock
+ XXX.level.block.StemGrownBlock
- XXX.level.block.StoneButtonBlock
+ XXX.level.block.StonecutterBlock
- XXX.level.block.StructureBlock
+ XXX.level.block.StructureBlock$1
- XXX.level.block.StructureVoidBlock
+ XXX.level.block.SugarCaneBlock
- XXX.level.block.SupportType
+ XXX.level.block.SupportType$1
- XXX.level.block.SupportType$2
+ XXX.level.block.SupportType$3
- XXX.level.block.SweetBerryBushBlock
+ XXX.level.block.TallFlowerBlock
- XXX.level.block.TallGrassBlock
+ XXX.level.block.TallSeagrassBlock
- XXX.level.block.TargetBlock
+ XXX.level.block.TintedGlassBlock
- XXX.level.block.TntBlock
+ XXX.level.block.TorchBlock
- XXX.level.block.TrapDoorBlock
+ XXX.level.block.TrapDoorBlock$1
- XXX.level.block.TrappedChestBlock
+ XXX.level.block.TripWireBlock
- XXX.level.block.TripWireBlock$1
+ XXX.level.block.TripWireHookBlock
- XXX.level.block.TripWireHookBlock$1
+ XXX.level.block.TurtleEggBlock
- XXX.level.block.TwistingVinesBlock
+ XXX.level.block.TwistingVinesPlantBlock
- XXX.level.block.VineBlock
+ XXX.level.block.VineBlock$1
- XXX.level.block.WallBannerBlock
+ XXX.level.block.WallBlock
- XXX.level.block.WallBlock$1
+ XXX.level.block.WallSignBlock
- XXX.level.block.WallSkullBlock
+ XXX.level.block.WallTorchBlock
- XXX.level.block.WaterlilyBlock
+ XXX.level.block.WeatheringCopper
- XXX.level.block.WeatheringCopper$WeatherState
+ XXX.level.block.WeatheringCopperFullBlock
- XXX.level.block.WeatheringCopperSlabBlock
+ XXX.level.block.WeatheringCopperStairBlock
- XXX.level.block.WebBlock
+ XXX.level.block.WeepingVinesBlock
- XXX.level.block.WeepingVinesPlantBlock
+ XXX.level.block.WeightedPressurePlateBlock
- XXX.level.block.WetSpongeBlock
+ XXX.level.block.WitherRoseBlock
- XXX.level.block.WitherSkullBlock
+ XXX.level.block.WitherWallSkullBlock
- XXX.level.block.WoodButtonBlock
+ XXX.level.block.WoolCarpetBlock
- XXX.level.border.BorderChangeListener
+ XXX.level.border.BorderChangeListener$DelegateBorderChangeListener
- XXX.level.border.BorderStatus
+ XXX.level.border.package-info
+ XXX.level.border.WorldBorder
- XXX.level.border.WorldBorder$1
+ XXX.level.border.WorldBorder$BorderExtent
- XXX.level.border.WorldBorder$MovingBorderExtent
+ XXX.level.border.WorldBorder$Settings
- XXX.level.border.WorldBorder$StaticBorderExtent
- XXX.level.chunk.BulkSectionAccess
+ XXX.level.chunk.ChunkAccess
- XXX.level.chunk.ChunkBiomeContainer
+ XXX.level.chunk.ChunkGenerator
- XXX.level.chunk.ChunkSource
+ XXX.level.chunk.ChunkStatus
- XXX.level.chunk.ChunkStatus$ChunkType
+ XXX.level.chunk.ChunkStatus$GenerationTask
- XXX.level.chunk.ChunkStatus$LoadingTask
+ XXX.level.chunk.ChunkStatus$SimpleGenerationTask
- XXX.level.chunk.DataLayer
+ XXX.level.chunk.EmptyLevelChunk
- XXX.level.chunk.EmptyLevelChunk$EmptyChunkBiomeContainer
+ XXX.level.chunk.FeatureAccess
- XXX.level.chunk.GlobalPalette
+ XXX.level.chunk.HashMapPalette
- XXX.level.chunk.ImposterProtoChunk
+ XXX.level.chunk.LevelChunk
- XXX.level.chunk.LevelChunk$1
+ XXX.level.chunk.LevelChunk$BoundTickingBlockEntity
- XXX.level.chunk.LevelChunk$EntityCreationType
+ XXX.level.chunk.LevelChunk$RebindableTickingBlockEntityWrapper
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
- XXX.level.dimension.DimensionDefaults
+ XXX.level.progress.ChunkProgressListener
- XXX.level.progress.ChunkProgressListenerFactory
+ XXX.level.progress.LoggerChunkProgressListener
- XXX.level.progress.package-info
- XXX.level.progress.ProcessorChunkProgressListener
+ XXX.level.progress.StoringChunkProgressListener
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
- XXX.levelgen.carver.CanyonCarverConfiguration$CanyonShapeConfiguration
+ XXX.levelgen.carver.CanyonWorldCarver
- XXX.levelgen.carver.CarverConfiguration
+ XXX.levelgen.carver.CarverDebugSettings
- XXX.levelgen.carver.CarvingContext
- XXX.levelgen.heightproviders.ConstantHeight
- XXX.levelgen.heightproviders.HeightProviderType
- XXX.levelgen.heightproviders.package-info
- XXX.levelgen.structure.OceanRuinPieces$OceanRuinPiece
+ XXX.levelgen.structure.PoolElementStructurePiece
- XXX.levelgen.structure.RuinedPortalPiece
+ XXX.levelgen.structure.RuinedPortalPiece$Properties
- XXX.levelgen.structure.RuinedPortalPiece$VerticalPlacement
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
- XXX.levelgen.structure.StructureFeatureIndexSavedData
+ XXX.levelgen.structure.StructurePiece
- XXX.levelgen.structure.StructurePiece$1
+ XXX.levelgen.structure.StructurePiece$BlockSelector
- XXX.levelgen.structure.StructurePieceAccessor
- XXX.metadata.animation.AnimationFrame
+ XXX.metadata.animation.AnimationMetadataSection
- XXX.metadata.animation.AnimationMetadataSection$1
+ XXX.metadata.animation.AnimationMetadataSection$FrameOutput
- XXX.metadata.animation.AnimationMetadataSectionSerializer
- XXX.metadata.animation.package-info
+ XXX.metadata.animation.VillagerMetaDataSection
- XXX.metadata.animation.VillagerMetaDataSection$Hat
+ XXX.metadata.animation.VillagerMetadataSectionSerializer
+ XXX.metadata.language.LanguageMetadataSection
- XXX.metadata.language.LanguageMetadataSectionSerializer
+ XXX.metadata.language.package-info
- XXX.metadata.pack.package-info
- XXX.metadata.pack.PackMetadataSection
+ XXX.metadata.pack.PackMetadataSectionSerializer
+ XXX.metadata.texture.package-info
+ XXX.metadata.texture.TextureMetadataSection
- XXX.metadata.texture.TextureMetadataSectionSerializer
- XXX.minecraft.client.package-info
- XXX.minecraft.commands.BrigadierExceptions
+ XXX.minecraft.commands.CommandFunction
- XXX.minecraft.commands.CommandFunction$CacheableFunction
+ XXX.minecraft.commands.CommandFunction$CommandEntry
- XXX.minecraft.commands.CommandFunction$Entry
+ XXX.minecraft.commands.CommandFunction$FunctionEntry
- XXX.minecraft.commands.CommandRuntimeException
- XXX.minecraft.commands.Commands
+ XXX.minecraft.commands.Commands$CommandSelection
- XXX.minecraft.commands.Commands$ParseFunction
+ XXX.minecraft.commands.CommandSource
- XXX.minecraft.commands.CommandSource$1
+ XXX.minecraft.commands.CommandSourceStack
+ XXX.minecraft.commands.SharedSuggestionProvider
- XXX.minecraft.commands.SharedSuggestionProvider$TextCoordinates
- XXX.minecraft.obfuscate.DontObfuscate
+ XXX.minecraft.obfuscate.DontObfuscateOrShrink
+ XXX.minecraft.obfuscate.package-info
+ XXX.minecraft.realms.DisconnectedRealmsScreen
- XXX.minecraft.realms.NarrationHelper
- XXX.minecraft.realms.package-info
+ XXX.minecraft.realms.RealmsBridge
- XXX.minecraft.realms.RealmsConnect
+ XXX.minecraft.realms.RealmsConnect$1
- XXX.minecraft.realms.RealmsLabel
+ XXX.minecraft.realms.RealmsObjectSelectionList
- XXX.minecraft.realms.RealmsScreen
+ XXX.minecraft.realms.RealmsServerAddress
- XXX.minecraft.realms.RepeatedNarrator
+ XXX.minecraft.realms.RepeatedNarrator$Params
+ XXX.minecraft.recipebook.package-info
+ XXX.minecraft.recipebook.PlaceRecipe
- XXX.minecraft.recipebook.ServerPlaceRecipe
- XXX.minecraft.resources.DelegatingOps
- XXX.minecraft.resources.package-info
+ XXX.minecraft.resources.RegistryDataPackCodec
- XXX.minecraft.resources.RegistryFileCodec
+ XXX.minecraft.resources.RegistryLookupCodec
- XXX.minecraft.resources.RegistryReadOps
+ XXX.minecraft.resources.RegistryReadOps$1
- XXX.minecraft.resources.RegistryReadOps$ReadCache
+ XXX.minecraft.resources.RegistryReadOps$ResourceAccess
- XXX.minecraft.resources.RegistryReadOps$ResourceAccess$1
+ XXX.minecraft.resources.RegistryReadOps$ResourceAccess$MemoryMap
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
- XXX.minecraft.sounds.Music
+ XXX.minecraft.sounds.Musics
+ XXX.minecraft.sounds.package-info
- XXX.minecraft.sounds.SoundEvent
+ XXX.minecraft.sounds.SoundEvents
- XXX.minecraft.sounds.SoundSource
- XXX.minecraft.stats.package-info
- XXX.minecraft.stats.RecipeBook
+ XXX.minecraft.stats.RecipeBookSettings
- XXX.minecraft.stats.RecipeBookSettings$TypeSettings
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
- XXX.minecraft.tags.GameEventTags
+ XXX.minecraft.tags.ItemTags
+ XXX.minecraft.tags.package-info
- XXX.minecraft.tags.SerializationTags
+ XXX.minecraft.tags.SetTag
- XXX.minecraft.tags.StaticTagHelper
+ XXX.minecraft.tags.StaticTagHelper$1
- XXX.minecraft.tags.StaticTagHelper$Wrapper
+ XXX.minecraft.tags.StaticTags
- XXX.minecraft.tags.Tag
+ XXX.minecraft.tags.Tag$1
- XXX.minecraft.tags.Tag$Builder
+ XXX.minecraft.tags.Tag$BuilderEntry
- XXX.minecraft.tags.Tag$ElementEntry
+ XXX.minecraft.tags.Tag$Entry
- XXX.minecraft.tags.Tag$Named
+ XXX.minecraft.tags.Tag$OptionalElementEntry
- XXX.minecraft.tags.Tag$OptionalTagEntry
+ XXX.minecraft.tags.Tag$TagEntry
- XXX.minecraft.tags.TagCollection
+ XXX.minecraft.tags.TagCollection$1
- XXX.minecraft.tags.TagCollection$NetworkPayload
+ XXX.minecraft.tags.TagContainer
- XXX.minecraft.tags.TagContainer$1
+ XXX.minecraft.tags.TagContainer$Builder
- XXX.minecraft.tags.TagContainer$CollectionConsumer
+ XXX.minecraft.tags.TagLoader
- XXX.minecraft.tags.TagManager
+ XXX.minecraft.tags.TagManager$1
- XXX.minecraft.tags.TagManager$LoaderInfo
- XXX.minecraft.util.BitStorage
+ XXX.minecraft.util.ClampedNormalFloat
+ XXX.minecraft.util.ConstantFloat
- XXX.minecraft.util.CrudeIncrementalIntIdentityHashBiMap
+ XXX.minecraft.util.Crypt
- XXX.minecraft.util.CryptException
+ XXX.minecraft.util.CsvOutput
- XXX.minecraft.util.CsvOutput$1
+ XXX.minecraft.util.CsvOutput$Builder
- XXX.minecraft.util.CubicSampler
+ XXX.minecraft.util.CubicSampler$Vec3Fetcher
- XXX.minecraft.util.DebugBuffer
+ XXX.minecraft.util.DirectoryLock
- XXX.minecraft.util.DirectoryLock$LockException
+ XXX.minecraft.util.ExceptionCollector
- XXX.minecraft.util.ExtraCodecs
+ XXX.minecraft.util.ExtraCodecs$1
+ XXX.minecraft.util.FloatProvider
+ XXX.minecraft.util.GlslPreprocessor$1
+ XXX.minecraft.util.GsonHelper
- XXX.minecraft.util.HeapDumper
+ XXX.minecraft.util.HttpUtil
+ XXX.minecraft.util.package-info
+ XXX.minecraft.util.TrapezoidFloat
- XXX.minecraft.util.Tuple
+ XXX.minecraft.util.UniformFloat
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
- XXX.mojang.blaze3d.FieldsAreNonnullByDefault
- XXX.mojang.math.FieldsAreNonnullByDefault
+ XXX.mojang.math.Matrix3f
- XXX.mojang.math.Matrix4f
- XXX.mojang.math.package-info
+ XXX.mojang.realmsclient.KeyCombo
- XXX.mojang.realmsclient.package-info
- XXX.mojang.realmsclient.RealmsMainScreen
+ XXX.mojang.realmsclient.RealmsMainScreen$1
- XXX.mojang.realmsclient.RealmsMainScreen$2
+ XXX.mojang.realmsclient.RealmsMainScreen$3
- XXX.mojang.realmsclient.RealmsMainScreen$4
+ XXX.mojang.realmsclient.RealmsMainScreen$5
- XXX.mojang.realmsclient.RealmsMainScreen$CloseButton
+ XXX.mojang.realmsclient.RealmsMainScreen$Entry
- XXX.mojang.realmsclient.RealmsMainScreen$HoveredElement
+ XXX.mojang.realmsclient.RealmsMainScreen$NewsButton
- XXX.mojang.realmsclient.RealmsMainScreen$PendingInvitesButton
+ XXX.mojang.realmsclient.RealmsMainScreen$RealmSelectionList
- XXX.mojang.realmsclient.RealmsMainScreen$ServerEntry
+ XXX.mojang.realmsclient.RealmsMainScreen$ShowPopupButton
- XXX.mojang.realmsclient.RealmsMainScreen$TrialEntry
+ XXX.mojang.realmsclient.Unit
- XXX.monitoring.jmx.MinecraftServerStatistics
+ XXX.monitoring.jmx.MinecraftServerStatistics$1
- XXX.monitoring.jmx.MinecraftServerStatistics$AttributeDescription
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
- XXX.packs.resources.package-info
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
- XXX.packs.resources.ResourceProvider
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
- XXX.phys.shapes.NonOverlappingMerger
+ XXX.phys.shapes.OffsetDoubleList
+ XXX.phys.shapes.package-info
- XXX.phys.shapes.Shapes
+ XXX.phys.shapes.Shapes$DoubleLineConsumer
- XXX.phys.shapes.SliceShape
+ XXX.phys.shapes.SubShape
- XXX.phys.shapes.VoxelShape
- XXX.profiling.registry.MeasuredMetric
+ XXX.profiling.registry.MeasurementCategory
- XXX.profiling.registry.MeasurementRegistry
+ XXX.profiling.registry.Metric
+ XXX.profiling.registry.package-info
- XXX.profiling.registry.ProfilerMeasured
- XXX.rcon.thread.GenericThread
+ XXX.rcon.thread.package-info
+ XXX.rcon.thread.QueryThreadGs4
- XXX.rcon.thread.QueryThreadGs4$RequestChallenge
+ XXX.rcon.thread.RconClient
- XXX.rcon.thread.RconThread
- XXX.realmsclient.client.FileDownload
+ XXX.realmsclient.client.FileDownload$1
- XXX.realmsclient.client.FileDownload$DownloadCountingOutputStream
+ XXX.realmsclient.client.FileDownload$ProgressListener
- XXX.realmsclient.client.FileDownload$ResourcePackProgressListener
+ XXX.realmsclient.client.FileUpload
- XXX.realmsclient.client.FileUpload$CustomInputStreamEntity
- XXX.realmsclient.client.package-info
+ XXX.realmsclient.client.Ping
- XXX.realmsclient.client.Ping$Region
+ XXX.realmsclient.client.RealmsClient
- XXX.realmsclient.client.RealmsClient$CompatibleVersionResponse
+ XXX.realmsclient.client.RealmsClient$Environment
- XXX.realmsclient.client.RealmsClientConfig
+ XXX.realmsclient.client.RealmsError
- XXX.realmsclient.client.Request
+ XXX.realmsclient.client.Request$Delete
- XXX.realmsclient.client.Request$Get
+ XXX.realmsclient.client.Request$Post
- XXX.realmsclient.client.Request$Put
+ XXX.realmsclient.client.UploadStatus
- XXX.realmsclient.dto.package-info
- XXX.realmsclient.dto.ServerActivity
+ XXX.realmsclient.exception.RealmsDefaultUncaughtExceptionHandler
- XXX.realmsclient.exception.RealmsHttpException
+ XXX.realmsclient.exception.RealmsServiceException
- XXX.realmsclient.exception.RetryCallException
- XXX.realmsclient.util.package-info
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
- XXX.renderer.entity.GoatRenderer
+ XXX.renderer.entity.GuardianRenderer
- XXX.renderer.entity.HoglinRenderer
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
+ XXX.renderer.entity.LeashKnotRenderer
- XXX.renderer.entity.LightningBoltRenderer
+ XXX.renderer.entity.LivingEntityRenderer
- XXX.renderer.entity.LivingEntityRenderer$1
+ XXX.renderer.entity.LlamaRenderer
- XXX.renderer.entity.LlamaSpitRenderer
+ XXX.renderer.entity.MagmaCubeRenderer
- XXX.renderer.entity.MinecartRenderer
+ XXX.renderer.entity.MobRenderer
- XXX.renderer.entity.MushroomCowRenderer
+ XXX.renderer.entity.OcelotRenderer
+ XXX.renderer.entity.package-info
- XXX.renderer.entity.PaintingRenderer
+ XXX.renderer.entity.PandaRenderer
- XXX.renderer.entity.ParrotRenderer
+ XXX.renderer.entity.PhantomRenderer
+ XXX.renderer.entity.PiglinRenderer
- XXX.renderer.entity.PigRenderer
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
- XXX.renderer.entity.SilverfishRenderer
+ XXX.renderer.entity.SkeletonRenderer
- XXX.renderer.entity.SlimeRenderer
+ XXX.renderer.entity.SnowGolemRenderer
- XXX.renderer.entity.SpectralArrowRenderer
+ XXX.renderer.entity.SpiderRenderer
- XXX.renderer.entity.SquidRenderer
+ XXX.renderer.entity.StrayRenderer
- XXX.renderer.entity.StriderRenderer
+ XXX.renderer.entity.ThrownItemRenderer
- XXX.renderer.entity.ThrownTridentRenderer
+ XXX.renderer.entity.TippableArrowRenderer
- XXX.renderer.entity.TntMinecartRenderer
+ XXX.renderer.entity.TntRenderer
- XXX.renderer.entity.TropicalFishRenderer
+ XXX.renderer.entity.TurtleRenderer
- XXX.renderer.entity.UndeadHorseRenderer
+ XXX.renderer.entity.VexRenderer
- XXX.renderer.entity.VillagerRenderer
+ XXX.renderer.entity.VindicatorRenderer
- XXX.renderer.entity.VindicatorRenderer$1
+ XXX.renderer.entity.WanderingTraderRenderer
- XXX.renderer.entity.WitchRenderer
+ XXX.renderer.entity.WitherBossRenderer
- XXX.renderer.entity.WitherSkeletonRenderer
+ XXX.renderer.entity.WitherSkullRenderer
- XXX.renderer.entity.WolfRenderer
+ XXX.renderer.entity.ZoglinRenderer
- XXX.renderer.entity.ZombieRenderer
+ XXX.renderer.entity.ZombieVillagerRenderer
- XXX.renderer.item.ItemProperties
+ XXX.renderer.item.ItemProperties$1
- XXX.renderer.item.ItemProperties$2
+ XXX.renderer.item.ItemProperties$CompassWobble
- XXX.renderer.item.ItemPropertyFunction
+ XXX.renderer.item.package-info
+ XXX.renderer.texture.AbstractTexture
- XXX.renderer.texture.AtlasSet
+ XXX.renderer.texture.DynamicTexture
- XXX.renderer.texture.HttpTexture
+ XXX.renderer.texture.MipmapGenerator
- XXX.renderer.texture.MissingTextureAtlasSprite
+ XXX.renderer.texture.OverlayTexture
- XXX.renderer.texture.package-info
- XXX.renderer.texture.PreloadedTexture
+ XXX.renderer.texture.SimpleTexture
- XXX.renderer.texture.SimpleTexture$TextureImage
+ XXX.renderer.texture.Stitcher
- XXX.renderer.texture.Stitcher$Holder
+ XXX.renderer.texture.Stitcher$Region
- XXX.renderer.texture.Stitcher$SpriteLoader
+ XXX.renderer.texture.StitcherException
- XXX.renderer.texture.TextureAtlas
+ XXX.renderer.texture.TextureAtlas$Preparations
- XXX.renderer.texture.TextureAtlasSprite
+ XXX.renderer.texture.TextureAtlasSprite$1
- XXX.renderer.texture.TextureAtlasSprite$AnimatedTexture
+ XXX.renderer.texture.TextureAtlasSprite$FrameInfo
- XXX.renderer.texture.TextureAtlasSprite$Info
+ XXX.renderer.texture.TextureAtlasSprite$InterpolationData
- XXX.renderer.texture.TextureManager
+ XXX.renderer.texture.Tickable
- XXX.resources.language.ClientLanguage
+ XXX.resources.language.FormattedBidiReorder
- XXX.resources.language.I18n
+ XXX.resources.language.LanguageInfo
- XXX.resources.language.LanguageManager
+ XXX.resources.language.package-info
- XXX.resources.metadata.package-info
- XXX.resources.model.BakedModel
+ XXX.resources.model.BlockModelRotation
- XXX.resources.model.BuiltInModel
+ XXX.resources.model.Material
- XXX.resources.model.ModelBakery
+ XXX.resources.model.ModelBakery$BlockStateDefinitionException
- XXX.resources.model.ModelBakery$ModelGroupKey
+ XXX.resources.model.ModelManager
- XXX.resources.model.ModelResourceLocation
+ XXX.resources.model.ModelState
- XXX.resources.model.MultiPartBakedModel
+ XXX.resources.model.MultiPartBakedModel$Builder
- XXX.resources.model.SimpleBakedModel
+ XXX.resources.model.SimpleBakedModel$Builder
- XXX.resources.model.UnbakedModel
+ XXX.resources.model.WeightedBakedModel
- XXX.resources.model.WeightedBakedModel$Builder
+ XXX.resources.model.WeightedBakedModel$WeightedModel
- XXX.scores.criteria.ObjectiveCriteria
+ XXX.scores.criteria.ObjectiveCriteria$RenderType
- XXX.scores.criteria.package-info
+ XXX.screens.mco.package-info
- XXX.screens.multiplayer.JoinMultiplayerScreen
+ XXX.screens.multiplayer.package-info
+ XXX.screens.multiplayer.SafetyScreen
- XXX.screens.multiplayer.ServerSelectionList
+ XXX.screens.multiplayer.ServerSelectionList$Entry
- XXX.screens.multiplayer.ServerSelectionList$LANHeader
+ XXX.screens.multiplayer.ServerSelectionList$NetworkServerEntry
- XXX.screens.multiplayer.ServerSelectionList$OnlineServerEntry
- XXX.screens.packs.package-info
+ XXX.screens.packs.PackSelectionModel
- XXX.screens.packs.PackSelectionModel$Entry
+ XXX.screens.packs.PackSelectionModel$EntryBase
- XXX.screens.packs.PackSelectionModel$SelectedPackEntry
+ XXX.screens.packs.PackSelectionModel$UnselectedPackEntry
- XXX.screens.packs.PackSelectionScreen
+ XXX.screens.packs.PackSelectionScreen$Watcher
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
- XXX.screens.social.package-info
+ XXX.screens.social.PlayerEntry
- XXX.screens.social.PlayerEntry$1
+ XXX.screens.social.PlayerEntry$2
- XXX.screens.social.PlayerSocialManager
+ XXX.screens.social.SocialInteractionsPlayerList
- XXX.screens.social.SocialInteractionsScreen
+ XXX.screens.social.SocialInteractionsScreen$1
- XXX.screens.social.SocialInteractionsScreen$2
+ XXX.screens.social.SocialInteractionsScreen$Page
+ XXX.screens.stream.package-info
- XXX.selector.options.EntitySelectorOptions
+ XXX.selector.options.EntitySelectorOptions$1
- XXX.selector.options.EntitySelectorOptions$Modifier
+ XXX.selector.options.EntitySelectorOptions$Option
- XXX.selector.options.package-info
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
- XXX.server.commands.ItemCommands
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
+ XXX.server.commands.SpreadPlayersCommand$1
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
+ XXX.server.level.ChunkHolder$ChunkSaveDebug
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
- XXX.server.level.package-info
- XXX.server.level.PlayerMap
+ XXX.server.level.PlayerRespawnLogic
- XXX.server.level.SectionTracker
+ XXX.server.level.ServerBossEvent
- XXX.server.level.ServerChunkCache
+ XXX.server.level.ServerChunkCache$1
- XXX.server.level.ServerChunkCache$MainThreadExecutor
+ XXX.server.level.ServerEntity
- XXX.server.level.ServerLevel
+ XXX.server.level.ServerLevel$1
- XXX.server.level.ServerLevel$EntityCallbacks
+ XXX.server.level.ServerPlayer
- XXX.server.level.ServerPlayer$1
+ XXX.server.level.ServerPlayer$2
- XXX.server.level.ServerPlayer$3
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
+ XXX.server.network.ServerConnectionListener$LatencySimulator$DelayedMessage
- XXX.server.network.ServerGamePacketListenerImpl
+ XXX.server.network.ServerGamePacketListenerImpl$1
- XXX.server.network.ServerGamePacketListenerImpl$2
+ XXX.server.network.ServerGamePacketListenerImpl$EntityInteraction
- XXX.server.network.ServerHandshakePacketListenerImpl
+ XXX.server.network.ServerHandshakePacketListenerImpl$1
- XXX.server.network.ServerLoginPacketListenerImpl
+ XXX.server.network.ServerLoginPacketListenerImpl$1
- XXX.server.network.ServerLoginPacketListenerImpl$State
+ XXX.server.network.ServerPlayerConnection
- XXX.server.network.ServerStatusPacketListenerImpl
+ XXX.server.network.TextFilter
- XXX.server.network.TextFilter$1
+ XXX.server.network.TextFilter$FilteredText
- XXX.server.network.TextFilterClient
+ XXX.server.network.TextFilterClient$1
- XXX.server.network.TextFilterClient$IgnoreStrategy
+ XXX.server.network.TextFilterClient$PlayerContext
- XXX.server.network.TextFilterClient$RequestFailedException
+ XXX.server.packs.AbstractPackResources
- XXX.server.packs.FilePackResources
+ XXX.server.packs.FolderPackResources
- XXX.server.packs.package-info
- XXX.server.packs.PackResources
+ XXX.server.packs.PackType
- XXX.server.packs.ResourcePackFileNotFoundException
+ XXX.server.packs.VanillaPackResources
- XXX.server.packs.VanillaPackResources$1
+ XXX.server.players.BanListEntry
- XXX.server.players.GameProfileCache
+ XXX.server.players.GameProfileCache$1
- XXX.server.players.GameProfileCache$GameProfileInfo
+ XXX.server.players.IpBanList
- XXX.server.players.IpBanListEntry
+ XXX.server.players.OldUsersConverter
- XXX.server.players.OldUsersConverter$1
+ XXX.server.players.OldUsersConverter$2
- XXX.server.players.OldUsersConverter$3
+ XXX.server.players.OldUsersConverter$4
- XXX.server.players.OldUsersConverter$5
+ XXX.server.players.OldUsersConverter$ConversionError
+ XXX.server.players.package-info
- XXX.server.players.PlayerList
+ XXX.server.players.PlayerList$1
- XXX.server.players.ServerOpList
+ XXX.server.players.ServerOpListEntry
- XXX.server.players.SleepStatus
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
+ XXX.state.pattern.BlockInWorld
- XXX.state.pattern.BlockPattern
+ XXX.state.pattern.BlockPattern$BlockCacheLoader
- XXX.state.pattern.BlockPattern$BlockPatternMatch
+ XXX.state.pattern.BlockPatternBuilder
- XXX.state.pattern.package-info
+ XXX.state.predicate.BlockMaterialPredicate
- XXX.state.predicate.BlockMaterialPredicate$1
+ XXX.state.predicate.BlockPredicate
- XXX.state.predicate.BlockStatePredicate
+ XXX.state.predicate.package-info
- XXX.state.properties.AttachFace
+ XXX.state.properties.BambooLeaves
- XXX.state.properties.BedPart
+ XXX.state.properties.BellAttachType
- XXX.state.properties.BlockStateProperties
+ XXX.state.properties.BooleanProperty
- XXX.state.properties.ChestType
+ XXX.state.properties.ComparatorMode
- XXX.state.properties.DirectionProperty
+ XXX.state.properties.DoorHingeSide
- XXX.state.properties.DoubleBlockHalf
+ XXX.state.properties.DripstoneThickness
- XXX.state.properties.EnumProperty
+ XXX.state.properties.Half
- XXX.state.properties.IntegerProperty
+ XXX.state.properties.NoteBlockInstrument
+ XXX.state.properties.package-info
- XXX.state.properties.PistonType
+ XXX.state.properties.Property
- XXX.state.properties.Property$1
+ XXX.state.properties.Property$Value
- XXX.state.properties.RailShape
+ XXX.state.properties.RedstoneSide
- XXX.state.properties.SculkSensorPhase
+ XXX.state.properties.SlabType
- XXX.state.properties.StairsShape
+ XXX.state.properties.StructureMode
- XXX.state.properties.Tilt
+ XXX.state.properties.WallSide
- XXX.state.properties.WoodType
- XXX.util.datafix.DataFixers
+ XXX.util.datafix.DataFixers$1
- XXX.util.datafix.DataFixers$2
+ XXX.util.datafix.DataFixTypes
+ XXX.util.datafix.package-info
+ XXX.util.datafix.PackedBitStorage
- XXX.util.profiling.ActiveProfiler
+ XXX.util.profiling.ActiveProfiler$PathEntry
- XXX.util.profiling.ContinuousProfiler
+ XXX.util.profiling.EmptyProfileResults
- XXX.util.profiling.FilledProfileResults
+ XXX.util.profiling.FilledProfileResults$1
- XXX.util.profiling.FilledProfileResults$CounterCollector
+ XXX.util.profiling.InactiveProfiler
+ XXX.util.profiling.package-info
- XXX.util.profiling.ProfileCollector
+ XXX.util.profiling.ProfileResults
- XXX.util.profiling.ProfilerFiller
+ XXX.util.profiling.ProfilerFiller$1
- XXX.util.profiling.ProfilerPathEntry
+ XXX.util.profiling.ResultField
- XXX.util.profiling.SingleTickProfiler
- XXX.util.random.SimpleWeightedRandomList
- XXX.util.random.Weight
- XXX.util.random.WeightedEntry$1
- XXX.util.random.WeightedEntry$Wrapper
- XXX.util.random.WeightedRandomList
+ XXX.util.task.CloseServerTask
- XXX.util.task.ConnectTask
+ XXX.util.task.DownloadTask
- XXX.util.task.GetServerDetailsTask
+ XXX.util.task.LongRunningTask
- XXX.util.task.OpenServerTask
- XXX.util.task.package-info
+ XXX.util.task.ResettingGeneratedWorldTask
- XXX.util.task.ResettingTemplateWorldTask
+ XXX.util.task.ResettingWorldTask
- XXX.util.task.RestoreTask
+ XXX.util.task.SwitchMinigameTask
- XXX.util.task.SwitchSlotTask
+ XXX.util.task.WorldCreationTask
- XXX.util.thread.BlockableEventLoop
+ XXX.util.thread.NamedThreadFactory
- XXX.util.thread.package-info
- XXX.util.thread.ProcessorHandle
+ XXX.util.thread.ProcessorHandle$1
- XXX.util.thread.ProcessorMailbox
+ XXX.util.thread.ReentrantBlockableEventLoop
- XXX.util.thread.StrictQueue
+ XXX.util.thread.StrictQueue$FixedPriorityQueue
- XXX.util.thread.StrictQueue$IntRunnable
+ XXX.util.thread.StrictQueue$QueueStrictQueue
- XXX.util.valueproviders.ConstantFloat
- XXX.util.valueproviders.FloatProvider
- XXX.util.valueproviders.IntProvider
- XXX.util.valueproviders.TrapezoidFloat
- XXX.util.valueproviders.UniformInt
- XXX.village.poi.package-info
- XXX.village.poi.PoiManager
+ XXX.village.poi.PoiManager$DistanceTracker
- XXX.village.poi.PoiManager$Occupancy
+ XXX.village.poi.PoiRecord
- XXX.village.poi.PoiSection
+ XXX.village.poi.PoiType
+ XXX.world.phys.AABB
- XXX.world.phys.BlockHitResult
+ XXX.world.phys.EntityHitResult
- XXX.world.phys.HitResult
+ XXX.world.phys.HitResult$Type
- XXX.world.phys.package-info
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
XXX.mojang.blaze3d.Blaze3D +3M
```
```
XXX.blaze3d.font.GlyphInfo +1M
```
```
XXX.blaze3d.pipeline.RenderTarget +1M | +4P
```
```
XXX.blaze3d.platform.GlStateManager +10M | +1P
```
```
XXX.blaze3d.platform.GlStateManager$Viewport +4M
```
```
XXX.blaze3d.platform.InputConstants +1M | +125P
```
```
XXX.blaze3d.platform.Lighting +1M
```
```
XXX.blaze3d.platform.NativeImage +8M | +4P
```
```
XXX.blaze3d.platform.NativeImage$Format +14M
```
```
XXX.blaze3d.platform.PngInfo$StbReaderBufferedChannel +1P
```
```
XXX.blaze3d.platform.TextureUtil +2M | +2P
```
```
XXX.mojang.math.OctahedralGroup +2M
```
```
XXX.mojang.math.Quaternion +9M
```
```
XXX.mojang.math.Transformation +4M
```
```
XXX.mojang.math.Vector3f +5M -3M
```
```
XXX.realmsclient.dto.RealmsWorldOptions +11P
```
```
XXX.realmsclient.dto.UploadInfo +2P
```
```
XXX.realmsclient.util.RealmsUtil +1M | +3P
```
```
XXX.realmsclient.util.TextRenderingUtils$Line +1M
```
```
XXX.realmsclient.util.UploadTokenCache +1M
```
```
net.minecraft.FileUtil +1P
```
```
net.minecraft.SharedConstants +81P
```
```
XXX.minecraft.client.Camera +1P
```
```
XXX.minecraft.client.ClientBrandRetriever +1P
```
```
XXX.minecraft.client.KeyMapping +7P
```
```
XXX.minecraft.client.Minecraft +1P
```
```
XXX.color.block.BlockColors +1P
```
```
XXX.color.item.ItemColors +1P
```
```
XXX.client.gui.Font +1P
```
```
XXX.client.gui.Gui +6P
```
```
XXX.client.gui.MapRenderer +2M -3M | +2P
```
```
XXX.client.gui.MapRenderer$MapInstance -1M
```
```
XXX.gui.components.AbstractWidget +2P
```
```
XXX.gui.components.ChatComponent +1P
```
```
XXX.gui.components.DebugScreenOverlay +7P
```
```
XXX.gui.components.EditBox +10P
```
```
XXX.gui.components.LerpingBossEvent +1P
```
```
XXX.gui.components.SubtitleOverlay +1P
```
```
XXX.components.toasts.RecipeToast +1P
```
```
XXX.components.toasts.TutorialToast +4P
```
```
XXX.gui.font.FontManager +1P
```
```
XXX.font.glyphs.MissingGlyph +2P
```
```
XXX.font.providers.LegacyUnicodeBitmapsProvider +3P
```
```
XXX.gui.screens.ChatScreen +1P
```
```
XXX.gui.screens.ConnectScreen +1P
```
```
XXX.gui.screens.CreateFlatWorldScreen +7P
```
```
XXX.gui.screens.LevelLoadingScreen +1P
```
```
XXX.gui.screens.PauseScreen +3P
```
```
XXX.gui.screens.TitleScreen +2P
```
```
XXX.gui.screens.WinScreen +1P
```
```
XXX.screens.debug.GameModeSwitcherScreen +6P
```
```
XXX.screens.debug.GameModeSwitcherScreen$GameModeIcon +2P
```
```
XXX.screens.inventory.AbstractContainerScreen +5P
```
```
XXX.inventory.tooltip.ClientBundleTooltip +5P
```
```
XXX.spectator.categories.SpectatorPage +1P
```
```
XXX.client.model.GuardianModel +4P
```
```
XXX.client.model.HorseModel +17P
```
```
XXX.client.model.LavaSlimeModel +1P
```
```
XXX.client.model.LlamaSpitModel +1P
```
```
XXX.client.model.OcelotModel +21P
```
```
XXX.client.model.ParrotModel +1P
```
```
XXX.client.model.PlayerModel +6P
```
```
XXX.client.model.RabbitModel +5P
```
```
XXX.client.model.SalmonModel +2P
```
```
XXX.client.model.ShulkerBulletModel +1P
```
```
XXX.client.model.SilverfishModel +1P
```
```
XXX.client.model.SpiderModel +6P
```
```
XXX.client.model.StriderModel +6P
```
```
XXX.client.model.TurtleModel +1P
```
```
XXX.client.model.WolfModel +4P
```
```
XXX.model.geom.ModelLayers +2P
```
```
XXX.model.geom.PartNames +57P
```
```
XXX.client.particle.DragonBreathParticle +8P
```
```
XXX.client.particle.ItemPickupParticle +1P
```
```
XXX.client.player.AbstractClientPlayer +11P
```
```
XXX.client.player.KeyboardInput +1P
```
```
XXX.client.profiling.ActiveClientMetricsLogger +1P
```
```
XXX.profiling.storage.MetricsPersister +3P
```
```
XXX.client.renderer.FogRenderer +2P
```
```
XXX.client.renderer.GameRenderer +1M | +3P
```
```
XXX.client.renderer.LightTexture +3P
```
```
XXX.client.renderer.RenderType +6P
```
```
XXX.client.renderer.ShaderInstance +3P
```
```
XXX.renderer.blockentity.BeaconRenderer +1P
```
```
XXX.renderer.blockentity.BellRenderer +1P
```
```
XXX.renderer.blockentity.ChestRenderer +3P
```
```
XXX.renderer.blockentity.SignRenderer +3P
```
```
XXX.renderer.blockentity.TheEndGatewayRenderer +2M -1M
```
```
XXX.renderer.chunk.VisGraph +8P
```
```
XXX.renderer.debug.BeeDebugRenderer +26P
```
```
XXX.renderer.debug.GameTestDebugRenderer +1P
```
```
XXX.renderer.debug.GoalSelectorDebugRenderer +1P
```
```
XXX.renderer.debug.HeightMapRenderer +2P
```
```
XXX.renderer.debug.LightDebugRenderer +1P
```
```
XXX.renderer.debug.PathfindingRenderer +8P
```
```
XXX.renderer.debug.VillageSectionsDebugRenderer +1P
```
```
XXX.renderer.entity.EntityRenderers +1P
```
```
XXX.resources.sounds.BeeSoundInstance +3P
```
```
XXX.resources.sounds.ElytraOnPlayerSoundInstance +1P
```
```
XXX.resources.sounds.GuardianAttackSoundInstance +4P
```
```
XXX.resources.sounds.RidingMinecartSoundInstance +2P
```
```
XXX.resources.sounds.UnderwaterAmbientSoundInstances$UnderwaterAmbientSoundInstance +1P
```
```
XXX.client.searchtree.SuffixArray +2P
```
```
XXX.client.server.IntegratedServer +1P
```
```
XXX.synchronization.brigadier.BrigadierArgumentSerializers +2P
```
```
XXX.minecraft.core.BlockPos +1P
```
```
XXX.minecraft.core.FrontAndTop +1M
```
```
XXX.minecraft.core.Registry +25M -23M | +4P
```
```
XXX.core.particles.DustParticleOptionsBase +2P
```
```
XXX.minecraft.data.BlockFamilies +2P
```
```
XXX.data.worldgen.Carvers +3P
```
```
XXX.data.worldgen.Features +2M | +22P
```
```
XXX.gametest.framework.GameTestBatch +1P
```
```
XXX.gametest.framework.GameTestRunner +5P
```
```
XXX.gametest.framework.GameTestSequence$Condition +1P
```
```
XXX.gametest.framework.MultipleTestTracker +5P
```
```
XXX.minecraft.nbt.ByteArrayTag +1P
```
```
XXX.minecraft.nbt.ByteTag +1P
```
```
XXX.minecraft.nbt.CompoundTag +2P
```
```
XXX.minecraft.nbt.DoubleTag +1P
```
```
XXX.minecraft.nbt.EndTag +1P
```
```
XXX.minecraft.nbt.FloatTag +1P
```
```
XXX.minecraft.nbt.IntArrayTag +1P
```
```
XXX.minecraft.nbt.IntTag +1P
```
```
XXX.minecraft.nbt.IntTag$Cache +2P
```
```
XXX.minecraft.nbt.NbtUtils +7P
```
```
XXX.minecraft.nbt.ShortTag +1P
```
```
XXX.minecraft.nbt.ShortTag$Cache +2P
```
```
XXX.minecraft.nbt.StringTag +5P
```
```
XXX.minecraft.nbt.TagParser +6P
```
```
XXX.minecraft.network.CompressionDecoder +1P
```
```
XXX.minecraft.network.Connection +1P
```
```
XXX.minecraft.network.ConnectionProtocol +2P
```
```
XXX.minecraft.network.FriendlyByteBuf +5P
```
```
XXX.network.chat.NbtComponent +1P
```
```
XXX.network.chat.ScoreComponent +1P
```
```
XXX.network.chat.TextColor +1P
```
```
XXX.protocol.game.ClientboundAddEntityPacket +2P
```
```
XXX.protocol.game.ClientboundAnimatePacket +6P
```
```
XXX.protocol.game.ClientboundBlockEntityDataPacket +13P
```
```
XXX.protocol.game.ClientboundCustomSoundPacket +1P
```
```
XXX.protocol.game.ClientboundLevelChunkPacket +1P
```
```
XXX.protocol.game.ClientboundLoginPacket +1P
```
```
XXX.protocol.game.ClientboundPlayerAbilitiesPacket +4P
```
```
XXX.protocol.game.ClientboundResourcePackPacket +1P
```
```
XXX.protocol.game.ClientboundSetEquipmentPacket +1P
```
```
XXX.protocol.game.ClientboundSoundPacket +1P
```
```
XXX.protocol.game.ServerboundChatPacket +1P
```
```
XXX.protocol.game.ServerboundCustomPayloadPacket +1P
```
```
XXX.protocol.game.ServerboundPlayerAbilitiesPacket +1P
```
```
XXX.protocol.game.ServerboundSetCommandBlockPacket +3P
```
```
XXX.protocol.game.ServerboundSetStructureBlockPacket +3P
```
```
XXX.minecraft.util.FrameTimer +1P
```
```
XXX.minecraft.util.Mth +16P
```
```
XXX.minecraft.util.SortedArraySet +1P
```
```
XXX.minecraft.world.DifficultyInstance +3P
```
```
XXX.minecraft.world.LockCode +1P
```
```
XXX.world.damagesource.CombatRules +5P
```
```
XXX.world.entity.Entity +22P
```
```
XXX.world.entity.EntityEvent +57P
```
```
XXX.world.entity.LivingEntity +2M | +20P
```
```
XXX.world.entity.Mob +9P
```
```
XXX.world.entity.MobCategory +1P
```
```
XXX.world.entity.NeutralMob +2P
```
```
XXX.entity.ai.Brain +1P
```
```
XXX.ai.attributes.Attribute +1P
```
```
XXX.ai.behavior.AcquirePoi$JitteredLinearRetry +3P
```
```
XXX.ai.behavior.Mount +1P
```
```
XXX.ai.behavior.MoveToTargetSink +1P
```
```
XXX.ai.behavior.RandomStroll +2P
```
```
XXX.ai.behavior.RunSometimes +2M -2M | +1P -1P
```
```
XXX.ai.behavior.ShowTradesToPlayer +2P
```
```
XXX.ai.behavior.SocializeAtBell +1P
```
```
XXX.ai.behavior.UseBonemeal +1P
```
```
XXX.ai.behavior.VillagerCalmDown +1P
```
```
XXX.ai.behavior.VillagerMakeLove +2P
```
```
XXX.ai.behavior.WorkAtPoi +2P
```
```
XXX.ai.control.MoveControl +3P
```
```
XXX.ai.control.SmoothSwimmingLookControl +2P
```
```
XXX.ai.goal.BreakDoorGoal +1P
```
```
XXX.ai.goal.FollowParentGoal +3P
```
```
XXX.ai.goal.GolemRandomStrollInVillageGoal +4P
```
```
XXX.ai.goal.MeleeAttackGoal +1P
```
```
XXX.ai.goal.RandomStrollGoal +1P
```
```
XXX.ai.goal.RangedCrossbowAttackGoal +1P -1P
```
```
XXX.ai.goal.RemoveBlockGoal +1P
```
```
XXX.ai.goal.StrollThroughVillageGoal +1P
```
```
XXX.ai.sensing.NearestBedSensor +3P
```
```
XXX.animal.horse.AbstractChestedHorse +1P
```
```
XXX.animal.horse.AbstractHorse +12P
```
```
XXX.animal.horse.SkeletonHorse +1P
```
```
XXX.boss.enderdragon.EnderDragon +3P
```
```
XXX.enderdragon.phases.DragonChargePlayerPhase +1P
```
```
XXX.enderdragon.phases.DragonSittingFlamingPhase +3P
```
```
XXX.enderdragon.phases.DragonStrafePlayerPhase +1P
```
```
XXX.boss.wither.WitherBoss +1P
```
```
XXX.entity.decoration.ItemFrame +1P
```
```
XXX.entity.item.ItemEntity +3P
```
```
XXX.entity.monster.AbstractSkeleton +1M
```
```
XXX.entity.monster.Endermite +1P
```
```
XXX.entity.monster.Guardian +1P
```
```
XXX.entity.monster.PatrollingMonster$LongDistancePatrolGoal +1P
```
```
XXX.entity.monster.Pillager +3P
```
```
XXX.entity.monster.Ravager +8P
```
```
XXX.entity.monster.Slime +2P
```
```
XXX.entity.monster.Spider +1P
```
```
XXX.entity.monster.Vindicator +1P
```
```
XXX.entity.monster.Zoglin +10P
```
```
XXX.entity.monster.ZombieVillager +4P
```
```
XXX.monster.hoglin.Hoglin +8P
```
```
XXX.monster.hoglin.HoglinBase +1P
```
```
XXX.monster.piglin.Piglin +9P
```
```
XXX.monster.piglin.PiglinBruteAi +10P
```
```
XXX.entity.npc.AbstractVillager +2P
```
```
XXX.entity.npc.VillagerData +2P
```
```
XXX.entity.npc.WanderingTrader +1P
```
```
XXX.entity.npc.WanderingTraderSpawner +7P
```
```
XXX.entity.player.Player +11P
```
```
XXX.entity.player.StackedContents +1P
```
```
XXX.entity.projectile.DragonFireball +1P
```
```
XXX.entity.projectile.ShulkerBullet +1P
```
```
XXX.entity.raid.Raids +1P
```
```
XXX.entity.schedule.Activity +1P
```
```
XXX.entity.schedule.Schedule +2P
```
```
XXX.entity.vehicle.Boat +6P
```
```
XXX.entity.vehicle.MinecartHopper +1P
```
```
XXX.world.food.Foods +1M -1M
```
```
XXX.world.inventory.AbstractContainerMenu +8P
```
```
XXX.world.inventory.AbstractFurnaceMenu +9P
```
```
XXX.world.inventory.DispenserMenu +5P
```
```
XXX.world.inventory.GrindstoneMenu +8P
```
```
XXX.world.inventory.ItemCombinerMenu +7P
```
```
XXX.world.inventory.MerchantMenu +11P
```
```
XXX.world.inventory.ShulkerBoxMenu +1P
```
```
XXX.world.item.BannerItem +1P
```
```
XXX.world.item.BowItem +2P
```
```
XXX.world.item.CrossbowItem +8P
```
```
XXX.world.item.FireworkRocketItem +10P
```
```
XXX.world.item.Item +3P
```
```
XXX.world.item.ItemStack +14P
```
```
XXX.world.item.ItemUtils -1M
```
```
XXX.world.item.KnowledgeBookItem +1P
```
```
XXX.world.item.MilkBucketItem +1P
```
```
XXX.world.item.PlayerHeadItem +1P
```
```
XXX.world.item.SpyglassItem +2P
```
```
XXX.world.item.SuspiciousStewItem +3P
```
```
XXX.item.crafting.Ingredient -1M
```
```
XXX.item.enchantment.ThornsEnchantment +1P
```
```
XXX.world.level.BaseSpawner +3P -1P
```
```
XXX.world.level.ChunkPos +7P
```
```
XXX.world.level.Explosion +1P
```
```
XXX.world.level.ForcedChunksSavedData +2P
```
```
XXX.world.level.Level +7P
```
```
XXX.world.level.ServerTickList +1P
```
```
XXX.world.level.StructureFeatureManager +2M -3M
```
```
XXX.level.biome.Biome +1P
```
```
XXX.level.block.AbstractCandleBlock +3M | +1P
```
```
XXX.level.block.AnvilBlock +2P
```
```
XXX.level.block.AzaleaBlock +2M | +1P
```
```
XXX.level.block.BambooSaplingBlock +1P
```
```
XXX.level.block.BeetrootBlock +1P
```
```
XXX.level.block.BigDripleafStemBlock +1M | +1P
```
```
XXX.level.block.BubbleColumnBlock +1P
```
```
XXX.level.block.BuddingAmethystBlock +1P
```
```
XXX.level.block.ButtonBlock +4P
```
```
XXX.level.block.CactusBlock +2P
```
```
XXX.level.block.CampfireBlock +1P
```
```
XXX.level.block.CandleCakeBlock +1P
```
```
XXX.level.block.ChestBlock +3P
```
```
XXX.level.block.ChorusFlowerBlock +1P
```
```
XXX.level.block.CocoaBlock +10P
```
```
XXX.level.block.ComposterBlock +4P
```
```
XXX.level.block.CoralPlantBlock +1P
```
```
XXX.level.block.DeadBushBlock +1P
```
```
XXX.level.block.DispenserBlock +1P
```
```
XXX.level.block.FlowerPotBlock +1P
```
```
XXX.level.block.FungusBlock +1P
```
```
XXX.level.block.GrowingPlantHeadBlock +1P
```
```
XXX.level.block.HoneyBlock +4P
```
```
XXX.level.block.KelpBlock +1P
```
```
XXX.level.block.LadderBlock +1P
```
```
XXX.level.block.LayeredCauldronBlock +4P
```
```
XXX.level.block.LecternBlock +1P
```
```
XXX.level.block.LevelEvent +70P
```
```
XXX.level.levelgen.Cavifier +2P
```
```
XXX.level.levelgen.DebugLevelSource +3P
```
```
XXX.level.levelgen.DepthBasedReplacingBaseStoneSource +2P
```
```
XXX.level.levelgen.SimpleRandomSource +6P
```
```
XXX.level.levelgen.VerticalAnchor$Absolute +1M
```
```
XXX.levelgen.carver.CaveWorldCarver +4M -3M
```
```
XXX.levelgen.carver.NetherWorldCarver +1M -1M
```
```
XXX.levelgen.feature.BastionFeature +1P
```
```
XXX.levelgen.feature.BuriedTreasureFeature$BuriedTreasureStart +1M -1M
```
```
XXX.levelgen.feature.DeltaFeature +1P
```
```
XXX.levelgen.feature.DesertPyramidFeature$FeatureStart +1M -1M
```
```
XXX.levelgen.feature.EndCityFeature$EndCityStart +1M -1M
```
```
XXX.levelgen.feature.JigsawFeature +1M -1M
```
```
XXX.levelgen.feature.LargeDripstoneFeature +1M -1M
```
```
XXX.levelgen.feature.NetherFortressFeature$NetherBridgeStart +1M -1M
```
```
XXX.levelgen.feature.OceanMonumentFeature$OceanMonumentStart +1M -3M | -1P
```
```
XXX.levelgen.feature.PillagerOutpostFeature +1M -1M | +1P -1P
```
```
XXX.levelgen.feature.RuinedPortalFeature$FeatureStart +1M -1M
```
```
XXX.levelgen.feature.ScatteredOreFeature +1P
```
```
XXX.levelgen.feature.ShipwreckFeature$FeatureStart +1M -1M
```
```
XXX.levelgen.feature.StructureFeature +3M -3M | +1P
```
```
XXX.levelgen.feature.SwamplandHutFeature$FeatureStart +1M -1M
```
```
XXX.levelgen.feature.WoodlandMansionFeature$WoodlandMansionStart +1M -1M
```
```
XXX.feature.configurations.ColumnFeatureConfiguration +5M -5M | +2P -2P
```
```
XXX.feature.configurations.DeltaFeatureConfiguration +5M -5M | +2P -2P
```
```
XXX.feature.configurations.DripstoneClusterConfiguration +6M -6M | +5P -5P
```
```
XXX.feature.configurations.ReplaceSphereConfiguration +3M -3M | +1P -1P
```
```
XXX.feature.configurations.VegetationPatchConfiguration +3M -3M | +2P -2P
```
```
XXX.feature.featuresize.FeatureSize +1P
```
```
XXX.feature.foliageplacers.BlobFoliagePlacer +2M -2M
```
```
XXX.feature.foliageplacers.DarkOakFoliagePlacer +2M -2M
```
```
XXX.feature.foliageplacers.FoliagePlacer +6M -6M | +3P -3P
```
```
XXX.feature.foliageplacers.MegaPineFoliagePlacer +3M -3M | +1P -1P
```
```
XXX.feature.foliageplacers.RandomSpreadFoliagePlacer +3M -3M | +1P -1P
```
```
XXX.feature.stateproviders.RandomizedIntStateProvider +3M -3M | +1P -1P
```
```
XXX.feature.structures.JigsawPlacement +1M -1M
```
```
XXX.feature.structures.ListPoolElement +4M -1M
```
```
XXX.feature.structures.StructureTemplatePool +2M -1M | +1P
```
```
XXX.feature.treedecorators.BeehiveDecorator +2M -1M
```
```
XXX.feature.treedecorators.LeaveVineDecorator +3M -3M
```
```
XXX.feature.trunkplacers.DarkOakTrunkPlacer +1M -1M
```
```
XXX.feature.trunkplacers.GiantTrunkPlacer +2M -2M
```
```
XXX.feature.trunkplacers.StraightTrunkPlacer +1M -1M
```
```
XXX.levelgen.structure.BoundingBox +11M -4M | +7P -6P
```
```
XXX.levelgen.structure.EndCityPieces$EndCityPiece +4M -1M | -3P
```
```
XXX.levelgen.structure.IglooPieces +1M -1M | +1P
```
```
XXX.levelgen.structure.MineShaftPieces +3M -3M | +6P
```
```
XXX.levelgen.structure.MineShaftPieces$MineShaftCorridor +2M -2M
```
```
XXX.levelgen.structure.MineShaftPieces$MineShaftPiece +1M -1M
```
```
XXX.levelgen.structure.MineShaftPieces$MineShaftStairs +2M -2M
```
```
XXX.levelgen.structure.NetherBridgePieces$BridgeEndFiller +1M -1M | +3P
```
```
XXX.levelgen.structure.NetherBridgePieces$CastleCorridorStairsPiece +2M -2M | +3P
```
```
XXX.levelgen.structure.NetherBridgePieces$CastleEntrance +2M -2M | +3P
```
```
XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorLeftTurnPiece +2M -2M | +3P
```
```
XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorRightTurnPiece +2M -2M | +3P
```
```
XXX.levelgen.structure.NetherBridgePieces$MonsterThrone +1M -1M | +3P
```
```
XXX.levelgen.structure.NetherBridgePieces$StairsRoom +2M -2M | +3P
```
```
XXX.levelgen.structure.NetherFossilPieces +1M -1M
```
```
XXX.levelgen.structure.NoiseAffectingStructureStart +2M -2M
```
```
XXX.levelgen.structure.OceanMonumentPieces$MonumentBuilding +5P
```
```
XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentPiece +2M -2M | +12P
```
```
XXX.levelgen.structure.OceanRuinFeature$OceanRuinStart +1M -1M
```
```
XXX.levelgen.structure.OceanRuinPieces +4M -4M
```
```
XXX.levelgen.structure.StructureStart$1 +2M -1M
```
```
XXX.levelgen.structure.TemplateStructurePiece +3M -3M | +1P
```
```
XXX.structure.templatesystem.BlockAgeProcessor +3P
```
```
XXX.structure.templatesystem.StructureTemplate +12P
```
```
XXX.levelgen.surfacebuilders.BadlandsSurfaceBuilder +1P
```
```
XXX.levelgen.synth.ImprovedNoise +1P
```
```
XXX.levelgen.synth.NormalNoise +2P
```
```
XXX.level.lighting.DynamicGraphMinFixedPoint +1P
```
```
XXX.level.lighting.LayerLightEngine +2P
```
```
XXX.level.lighting.SpatialLongSet$InternalMap +1P
```
```
XXX.level.material.FluidState +2P
```
```
XXX.level.material.Material +1P -1P
```
```
XXX.newbiome.context.LazyAreaContext +1P
```
```
XXX.newbiome.layer.LayerBiomes +68P
```
```
XXX.newbiome.layer.ZoomLayer +2P
```
```
XXX.level.pathfinder.PathFinder +2P
```
```
XXX.saveddata.maps.MapItemSavedData +3P
```
```
XXX.level.storage.CommandStorage +1P
```
```
XXX.level.storage.CommandStorage$Container +1P
```
```
XXX.level.storage.LevelStorageSource +1P
```
```
XXX.loot.entries.LootPoolSingletonContainer +2P
```
```
XXX.loot.functions.ExplorationMapFunction +4P
```
```
XXX.loot.functions.LootingEnchantFunction +1P
```

</details>
<details>
<summary>
com.mojang.blaze3d.Blaze3D
</summary>

```diff
- void <init>()
- void process(RenderPipeline,float)
- void render(RenderPipeline,float)
```

</details>
<details>
<summary>
com.mojang.blaze3d.font.GlyphInfo
</summary>

```diff
- float getBearingY()
```

</details>
<details>
<summary>
com.mojang.blaze3d.pipeline.RenderTarget
</summary>

```diff
- void bindRead()
```

</details>
<details>
<summary>
com.mojang.blaze3d.platform.GlStateManager
</summary>

```diff
- int getBoundFramebuffer()
- int glGenRenderbuffers()
- void _glBindRenderbuffer(int,int)
- void _glCopyTexSubImage2D(int,int,int,int,int,int,int,int)
- void _glDeleteRenderbuffers(int)
- void _glDrawPixels(int,int,int,int,long)
- void _glFramebufferRenderbuffer(int,int,int,int)
- void _glRenderbufferStorage(int,int,int,int)
- void _readPixels(int,int,int,int,int,int,long)
- void <init>()
```

</details>
<details>
<summary>
com.mojang.blaze3d.platform.GlStateManager$Viewport
</summary>

```diff
- int height()
- int width()
- int x()
- int y()
```

</details>
<details>
<summary>
com.mojang.blaze3d.platform.InputConstants
</summary>

```diff
- void <init>()
```

</details>
<details>
<summary>
com.mojang.blaze3d.platform.Lighting
</summary>

```diff
- void <init>()
```

</details>
<details>
<summary>
com.mojang.blaze3d.platform.NativeImage
</summary>

```diff
- byte getBlueOrLuminance(int,int)
- byte getGreenOrLuminance(int,int)
- byte getRedOrLuminance(int,int)
- void blendPixel(int,int,int)
- void downloadDepthBuffer(float)
- void drawPixels()
- void setPixelLuminance(int,int,byte)
- void writeToFile(String)
```

</details>
<details>
<summary>
com.mojang.blaze3d.platform.NativeImage$Format
</summary>

```diff
- boolean hasBlue()
- boolean hasGreen()
- boolean hasLuminance()
- boolean hasLuminanceOrBlue()
- boolean hasLuminanceOrGreen()
- boolean hasLuminanceOrRed()
- boolean hasRed()
- int blueOffset()
- int greenOffset()
- int luminanceOffset()
- int luminanceOrBlueOffset()
- int luminanceOrGreenOffset()
- int luminanceOrRedOffset()
- int redOffset()
```

</details>
<details>
<summary>
com.mojang.blaze3d.platform.TextureUtil
</summary>

```diff
- void <init>()
- void writeAsPNG(String,int,int,int,int)
```

</details>
<details>
<summary>
com.mojang.math.OctahedralGroup
</summary>

```diff
- Matrix3f transformation()
- OctahedralGroup inverse()
```

</details>
<details>
<summary>
com.mojang.math.Quaternion
</summary>

```diff
- Quaternion fromXYZ(float,float,float)
- Quaternion fromXYZ(Vector3f)
- Quaternion fromXYZDegrees(Vector3f)
- Quaternion fromYXZ(float,float,float)
- Vector3f toXYZ()
- Vector3f toXYZDegrees()
- Vector3f toYXZ()
- Vector3f toYXZDegrees()
- void slerp(Quaternion,float)
```

</details>
<details>
<summary>
com.mojang.math.Transformation
</summary>

```diff
- Quaternion getRightRotation()
- Transformation slerp(Transformation,float)
- Vector3f getScale()
- Vector3f getTranslation()
```

</details>
<details>
<summary>
com.mojang.math.Vector3f
</summary>

```diff
+ DataResult lambda$static$1(DoubleStream)
- DataResult lambda$static$1(List)
+ DoubleStream lambda$static$2(Vector3f)
- List lambda$static$2(Vector3f)
+ Vector3f lambda$null$0(double[])
- Vector3f lambda$null$0(List)
- void clamp(Vector3f,Vector3f)
- void load(Vector3f)
```

</details>
<details>
<summary>
com.mojang.realmsclient.util.RealmsUtil
</summary>

```diff
- void <init>()
```

</details>
<details>
<summary>
com.mojang.realmsclient.util.TextRenderingUtils$Line
</summary>

```diff
- void <init>(TextRenderingUtils$LineSegment[])
```

</details>
<details>
<summary>
com.mojang.realmsclient.util.UploadTokenCache
</summary>

```diff
- void <init>()
```

</details>
<details>
<summary>
net.minecraft.client.gui.MapRenderer
</summary>

```diff
+ MapItemSavedData retrieveMapFromRenderer(int)
- RenderType access$300()
+ RenderType access$400()
- TextureManager access$200(MapRenderer)
+ TextureManager access$300(MapRenderer)
```

</details>
<details>
<summary>
net.minecraft.client.gui.MapRenderer$MapInstance
</summary>

```diff
+ MapItemSavedData access$200(MapRenderer$MapInstance)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.GameRenderer
</summary>

```diff
- boolean isPanoramicMode()
```

</details>
<details>
<summary>
net.minecraft.client.renderer.blockentity.TheEndGatewayRenderer
</summary>

```diff
+ float getOffset()
- float getOffsetDown()
- float getOffsetUp()
```

</details>
<details>
<summary>
net.minecraft.core.FrontAndTop
</summary>

```diff
- void lambda$static$0(Int2ObjectOpenHashMap)
```

</details>
<details>
<summary>
net.minecraft.core.Registry
</summary>

```diff
+ BlockPlacerType lambda$static$43()
- BlockPlacerType lambda$static$45()
+ BlockStateProviderType lambda$static$42()
- BlockStateProviderType lambda$static$44()
+ Codec lambda$static$48()
+ Codec lambda$static$49()
- Codec lambda$static$50()
- Codec lambda$static$51()
+ DataResult lambda$decode$54(Number)
- DataResult lambda$decode$56(Number)
+ DataResult lambda$decode$56(Pair)
- DataResult lambda$decode$58(Pair)
+ Feature lambda$static$38()
- Feature lambda$static$40()
+ FeatureDecorator lambda$static$41()
- FeatureDecorator lambda$static$43()
+ FeatureSizeType lambda$static$47()
- FeatureSizeType lambda$static$49()
- FloatProviderType lambda$static$35()
+ FloatProviderType lambda$static$36()
+ FoliagePlacerType lambda$static$44()
- FoliagePlacerType lambda$static$46()
- HeightProviderType lambda$static$37()
- IntProviderType lambda$static$36()
+ Object lambda$keys$57(DynamicOps,ResourceLocation)
- Object lambda$keys$59(DynamicOps,ResourceLocation)
+ Pair lambda$decode$55(DynamicOps,Object)
- Pair lambda$decode$57(DynamicOps,Object)
+ StructureFeature lambda$static$39()
- StructureFeature lambda$static$41()
+ StructurePieceType lambda$static$40()
- StructurePieceType lambda$static$42()
+ StructurePoolElementType lambda$static$51()
- StructurePoolElementType lambda$static$53()
+ StructureProcessorType lambda$static$50()
- StructureProcessorType lambda$static$52()
+ SurfaceBuilder lambda$static$35()
- SurfaceBuilder lambda$static$38()
+ TreeDecoratorType lambda$static$46()
- TreeDecoratorType lambda$static$48()
+ TrunkPlacerType lambda$static$45()
- TrunkPlacerType lambda$static$47()
+ void lambda$checkRegistry$53(WritableRegistry,WritableRegistry)
- void lambda$checkRegistry$55(WritableRegistry,WritableRegistry)
+ void lambda$static$52(ResourceLocation,Supplier)
- void lambda$static$54(ResourceLocation,Supplier)
+ WorldCarver lambda$static$37()
- WorldCarver lambda$static$39()
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.Features
</summary>

```diff
- SimpleWeightedRandomList$Builder access$000()
- SimpleWeightedRandomList$Builder weightedBlockStateBuilder()
```

</details>
<details>
<summary>
net.minecraft.world.entity.LivingEntity
</summary>

```diff
- boolean shouldDiscardFriction()
- void setDiscardFriction(boolean)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.behavior.RunSometimes
</summary>

```diff
+ void <init>(Behavior,boolean,IntRange)
- void <init>(Behavior,boolean,UniformInt)
+ void <init>(Behavior,IntRange)
- void <init>(Behavior,UniformInt)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.AbstractSkeleton
</summary>

```diff
- boolean isShaking()
```

</details>
<details>
<summary>
net.minecraft.world.food.Foods
</summary>

```diff
+ FoodProperties stew(int)
- FoodProperties$Builder stew(int)
```

</details>
<details>
<summary>
net.minecraft.world.item.ItemUtils
</summary>

```diff
+ Optional bucketMobPickup(Player,InteractionHand,LivingEntity,SoundEvent,Supplier)
```

</details>
<details>
<summary>
net.minecraft.world.item.crafting.Ingredient
</summary>

```diff
+ JsonSyntaxException lambda$valueFromJson$8(ResourceLocation)
```

</details>
<details>
<summary>
net.minecraft.world.level.StructureFeatureManager
</summary>

```diff
+ boolean lambda$getStructureAt$3(BlockPos,StructureStart)
- boolean lambda$getStructureAt$4(boolean,BlockPos,StructureStart)
+ boolean lambda$getStructureAt$5(boolean,BlockPos,StructureStart)
- boolean lambda$null$3(BlockPos,StructurePiece)
+ boolean lambda$null$4(BlockPos,StructurePiece)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.AbstractCandleBlock
</summary>

```diff
- boolean canBeLit(BlockState)
- boolean isLit(BlockState)
- void lambda$extinguish$1(LevelAccessor,BlockPos,Vec3)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.AzaleaBlock
</summary>

```diff
- void <clinit>()
- VoxelShape getBlockSupportShape(BlockState,BlockGetter,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BigDripleafStemBlock
</summary>

```diff
- ItemStack getCloneItemStack(BlockGetter,BlockPos,BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.VerticalAnchor$Absolute
</summary>

```diff
- String toString()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.carver.CaveWorldCarver
</summary>

```diff
- boolean carve(CarvingContext,CaveCarverConfiguration,ChunkAccess,Function,Random,int,ChunkPos,BitSet)
- boolean isStartChunk(CaveCarverConfiguration,Random)
+ int getCaveY(CarvingContext,Random)
+ void createRoom(CarvingContext,CarverConfiguration,ChunkAccess,Function,long,int,double,double,double,float,double,BitSet,WorldCarver$CarveSkipChecker)
- void createRoom(CarvingContext,CaveCarverConfiguration,ChunkAccess,Function,long,int,double,double,double,float,double,BitSet,WorldCarver$CarveSkipChecker)
+ void createTunnel(CarvingContext,CarverConfiguration,ChunkAccess,Function,long,int,double,double,double,double,double,float,float,float,int,int,double,BitSet,WorldCarver$CarveSkipChecker)
- void createTunnel(CarvingContext,CaveCarverConfiguration,ChunkAccess,Function,long,int,double,double,double,double,double,float,float,float,int,int,double,BitSet,WorldCarver$CarveSkipChecker)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.carver.NetherWorldCarver
</summary>

```diff
- boolean carveBlock(CarvingContext,CaveCarverConfiguration,ChunkAccess,Function,BitSet,Random,BlockPos$MutableBlockPos,BlockPos$MutableBlockPos,int,MutableBoolean)
+ int getCaveY(CarvingContext,Random)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.BuriedTreasureFeature$BuriedTreasureStart
</summary>

```diff
+ void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
- void <init>(StructureFeature,ChunkPos,int,long)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.DesertPyramidFeature$FeatureStart
</summary>

```diff
+ void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
- void <init>(StructureFeature,ChunkPos,int,long)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.EndCityFeature$EndCityStart
</summary>

```diff
+ void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
- void <init>(StructureFeature,ChunkPos,int,long)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.JigsawFeature
</summary>

```diff
+ StructureStart lambda$getStartFactory$0(StructureFeature,ChunkPos,BoundingBox,int,long)
- StructureStart lambda$getStartFactory$0(StructureFeature,ChunkPos,int,long)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.LargeDripstoneFeature
</summary>

```diff
+ LargeDripstoneFeature$LargeDripstone makeDripstone(BlockPos,boolean,Random,int,FloatProvider,FloatProvider)
- LargeDripstoneFeature$LargeDripstone makeDripstone(BlockPos,boolean,Random,int,FloatProvider,FloatProvider)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.NetherFortressFeature$NetherBridgeStart
</summary>

```diff
+ void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
- void <init>(StructureFeature,ChunkPos,int,long)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.OceanMonumentFeature$OceanMonumentStart
</summary>

```diff
+ void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
- void <init>(StructureFeature,ChunkPos,int,long)
+ void generatePieces(ChunkPos)
+ void placeInChunk(WorldGenLevel,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.PillagerOutpostFeature
</summary>

```diff
+ List getSpecialEnemies()
- WeightedRandomList getSpecialEnemies()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.RuinedPortalFeature$FeatureStart
</summary>

```diff
+ void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
- void <init>(StructureFeature,ChunkPos,int,long)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.ShipwreckFeature$FeatureStart
</summary>

```diff
+ void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
- void <init>(StructureFeature,ChunkPos,int,long)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.StructureFeature
</summary>

```diff
+ List getSpecialAnimals()
+ List getSpecialEnemies()
+ StructureStart createStart(ChunkPos,BoundingBox,int,long)
- StructureStart createStart(ChunkPos,int,long)
- WeightedRandomList getSpecialAnimals()
- WeightedRandomList getSpecialEnemies()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.SwamplandHutFeature$FeatureStart
</summary>

```diff
+ void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
- void <init>(StructureFeature,ChunkPos,int,long)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.WoodlandMansionFeature$WoodlandMansionStart
</summary>

```diff
+ void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
- void <init>(StructureFeature,ChunkPos,int,long)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.ColumnFeatureConfiguration
</summary>

```diff
- IntProvider height()
- IntProvider lambda$null$0(ColumnFeatureConfiguration)
- IntProvider lambda$null$1(ColumnFeatureConfiguration)
- IntProvider reach()
+ UniformInt height()
+ UniformInt lambda$null$0(ColumnFeatureConfiguration)
+ UniformInt lambda$null$1(ColumnFeatureConfiguration)
+ UniformInt reach()
- void <init>(IntProvider,IntProvider)
+ void <init>(UniformInt,UniformInt)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.DeltaFeatureConfiguration
</summary>

```diff
- IntProvider lambda$null$2(DeltaFeatureConfiguration)
- IntProvider lambda$null$3(DeltaFeatureConfiguration)
- IntProvider rimSize()
- IntProvider size()
+ UniformInt lambda$null$2(DeltaFeatureConfiguration)
+ UniformInt lambda$null$3(DeltaFeatureConfiguration)
+ UniformInt rimSize()
+ UniformInt size()
- void <init>(BlockState,BlockState,IntProvider,IntProvider)
+ void <init>(BlockState,BlockState,UniformInt,UniformInt)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.DripstoneClusterConfiguration
</summary>

```diff
+ FloatProvider lambda$null$6(DripstoneClusterConfiguration)
- FloatProvider lambda$null$6(DripstoneClusterConfiguration)
+ FloatProvider lambda$null$7(DripstoneClusterConfiguration)
- FloatProvider lambda$null$7(DripstoneClusterConfiguration)
- IntProvider lambda$null$1(DripstoneClusterConfiguration)
- IntProvider lambda$null$2(DripstoneClusterConfiguration)
- IntProvider lambda$null$5(DripstoneClusterConfiguration)
+ UniformInt lambda$null$1(DripstoneClusterConfiguration)
+ UniformInt lambda$null$2(DripstoneClusterConfiguration)
+ UniformInt lambda$null$5(DripstoneClusterConfiguration)
- void <init>(int,IntProvider,IntProvider,int,int,IntProvider,FloatProvider,FloatProvider,float,int,int)
+ void <init>(int,UniformInt,UniformInt,int,int,UniformInt,FloatProvider,FloatProvider,float,int,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.ReplaceSphereConfiguration
</summary>

```diff
- IntProvider lambda$null$2(ReplaceSphereConfiguration)
- IntProvider radius()
+ UniformInt lambda$null$2(ReplaceSphereConfiguration)
+ UniformInt radius()
- void <init>(BlockState,BlockState,IntProvider)
+ void <init>(BlockState,BlockState,UniformInt)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.VegetationPatchConfiguration
</summary>

```diff
- IntProvider lambda$null$4(VegetationPatchConfiguration)
- IntProvider lambda$null$8(VegetationPatchConfiguration)
+ UniformInt lambda$null$4(VegetationPatchConfiguration)
+ UniformInt lambda$null$8(VegetationPatchConfiguration)
- void <init>(ResourceLocation,BlockStateProvider,Supplier,CaveSurface,IntProvider,float,int,float,IntProvider,float)
+ void <init>(ResourceLocation,BlockStateProvider,Supplier,CaveSurface,UniformInt,float,int,float,UniformInt,float)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.BlobFoliagePlacer
</summary>

```diff
- void <init>(IntProvider,IntProvider,int)
+ void <init>(UniformInt,UniformInt,int)
- void createFoliage(LevelSimulatedReader,BiConsumer,Random,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,int)
+ void createFoliage(LevelSimulatedRW,Random,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,Set,int,BoundingBox)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.DarkOakFoliagePlacer
</summary>

```diff
- void <init>(IntProvider,IntProvider)
+ void <init>(UniformInt,UniformInt)
- void createFoliage(LevelSimulatedReader,BiConsumer,Random,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,int)
+ void createFoliage(LevelSimulatedRW,Random,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,Set,int,BoundingBox)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer
</summary>

```diff
- IntProvider lambda$foliagePlacerParts$0(FoliagePlacer)
- IntProvider lambda$foliagePlacerParts$1(FoliagePlacer)
+ UniformInt lambda$foliagePlacerParts$0(FoliagePlacer)
+ UniformInt lambda$foliagePlacerParts$1(FoliagePlacer)
- void <init>(IntProvider,IntProvider)
+ void <init>(UniformInt,UniformInt)
- void createFoliage(LevelSimulatedReader,BiConsumer,Random,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int)
+ void createFoliage(LevelSimulatedRW,Random,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,Set,BoundingBox)
- void placeLeavesRow(LevelSimulatedReader,BiConsumer,Random,TreeConfiguration,BlockPos,int,int,boolean)
+ void placeLeavesRow(LevelSimulatedRW,Random,TreeConfiguration,BlockPos,int,Set,int,boolean,BoundingBox)
- void tryPlaceLeaf(LevelSimulatedReader,BiConsumer,Random,TreeConfiguration,BlockPos)
+ void tryPlaceLeaf(LevelSimulatedRW,Random,TreeConfiguration,Set,BoundingBox,BlockPos$MutableBlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.MegaPineFoliagePlacer
</summary>

```diff
- IntProvider lambda$null$0(MegaPineFoliagePlacer)
+ UniformInt lambda$null$0(MegaPineFoliagePlacer)
- void <init>(IntProvider,IntProvider,IntProvider)
+ void <init>(UniformInt,UniformInt,UniformInt)
- void createFoliage(LevelSimulatedReader,BiConsumer,Random,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,int)
+ void createFoliage(LevelSimulatedRW,Random,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,Set,int,BoundingBox)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.RandomSpreadFoliagePlacer
</summary>

```diff
- IntProvider lambda$null$0(RandomSpreadFoliagePlacer)
+ UniformInt lambda$null$0(RandomSpreadFoliagePlacer)
- void <init>(IntProvider,IntProvider,IntProvider,int)
+ void <init>(UniformInt,UniformInt,UniformInt,int)
- void createFoliage(LevelSimulatedReader,BiConsumer,Random,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,int)
+ void createFoliage(LevelSimulatedRW,Random,TreeConfiguration,int,FoliagePlacer$FoliageAttachment,int,int,Set,int,BoundingBox)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.stateproviders.RandomizedIntStateProvider
</summary>

```diff
- IntProvider lambda$null$2(RandomizedIntStateProvider)
+ UniformInt lambda$null$2(RandomizedIntStateProvider)
- void <init>(BlockStateProvider,IntegerProperty,IntProvider)
+ void <init>(BlockStateProvider,IntegerProperty,UniformInt)
- void <init>(BlockStateProvider,String,IntProvider)
+ void <init>(BlockStateProvider,String,UniformInt)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement
</summary>

```diff
+ void addPieces(RegistryAccess,JigsawConfiguration,JigsawPlacement$PieceFactory,ChunkGenerator,StructureManager,BlockPos,List,Random,boolean,boolean,LevelHeightAccessor)
- void addPieces(RegistryAccess,JigsawConfiguration,JigsawPlacement$PieceFactory,ChunkGenerator,StructureManager,BlockPos,StructurePieceAccessor,Random,boolean,boolean,LevelHeightAccessor)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.structures.ListPoolElement
</summary>

```diff
- boolean lambda$getBoundingBox$2(StructurePoolElement)
- BoundingBox lambda$getBoundingBox$3(StructureManager,BlockPos,Rotation,StructurePoolElement)
- IllegalStateException lambda$getBoundingBox$4()
+ void lambda$setProjectionOnEachElement$2(StructureTemplatePool$Projection,StructurePoolElement)
- void lambda$setProjectionOnEachElement$5(StructureTemplatePool$Projection,StructurePoolElement)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool
</summary>

```diff
- boolean lambda$getMaxSize$2(StructurePoolElement)
+ int lambda$getMaxSize$2(StructureManager,StructurePoolElement)
- int lambda$getMaxSize$3(StructureManager,StructurePoolElement)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.treedecorators.BeehiveDecorator
</summary>

```diff
- void lambda$place$2(Random,BeehiveBlockEntity)
- void place(LevelSimulatedReader,BiConsumer,Random,List,List)
+ void place(WorldGenLevel,Random,List,List,Set,BoundingBox)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.treedecorators.LeaveVineDecorator
</summary>

```diff
- void addHangingVine(LevelSimulatedReader,BlockPos,BooleanProperty,BiConsumer)
+ void addHangingVine(LevelSimulatedRW,BlockPos,BooleanProperty,Set,BoundingBox)
- void lambda$place$1(Random,LevelSimulatedReader,BiConsumer,BlockPos)
+ void lambda$place$1(Random,WorldGenLevel,Set,BoundingBox,BlockPos)
- void place(LevelSimulatedReader,BiConsumer,Random,List,List)
+ void place(WorldGenLevel,Random,List,List,Set,BoundingBox)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.trunkplacers.DarkOakTrunkPlacer
</summary>

```diff
- List placeTrunk(LevelSimulatedReader,BiConsumer,Random,int,BlockPos,TreeConfiguration)
+ List placeTrunk(LevelSimulatedRW,Random,int,BlockPos,Set,BoundingBox,TreeConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.trunkplacers.GiantTrunkPlacer
</summary>

```diff
- List placeTrunk(LevelSimulatedReader,BiConsumer,Random,int,BlockPos,TreeConfiguration)
+ List placeTrunk(LevelSimulatedRW,Random,int,BlockPos,Set,BoundingBox,TreeConfiguration)
- void placeLogIfFreeWithOffset(LevelSimulatedReader,BiConsumer,Random,BlockPos$MutableBlockPos,TreeConfiguration,BlockPos,int,int,int)
+ void placeLogIfFreeWithOffset(LevelSimulatedRW,Random,BlockPos$MutableBlockPos,Set,BoundingBox,TreeConfiguration,BlockPos,int,int,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.trunkplacers.StraightTrunkPlacer
</summary>

```diff
- List placeTrunk(LevelSimulatedReader,BiConsumer,Random,int,BlockPos,TreeConfiguration)
+ List placeTrunk(LevelSimulatedRW,Random,int,BlockPos,Set,BoundingBox,TreeConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.BoundingBox
</summary>

```diff
+ BoundingBox createProper(int,int,int,int,int,int)
+ BoundingBox createProper(Vec3i,Vec3i)
- BoundingBox encapsulate(BoundingBox)
- BoundingBox fromCorners(Vec3i,Vec3i)
+ BoundingBox getUnknownBox()
- BoundingBox inflate(int)
- int maxX()
- int maxY()
- int maxZ()
- int minX()
- int minY()
- int minZ()
- Optional encapsulatingBoxes(Iterable)
- Optional encapsulatingPositions(Iterable)
+ void expand(BoundingBox)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.EndCityPieces$EndCityPiece
</summary>

```diff
- ResourceLocation makeResourceLocation(String)
- ResourceLocation makeTemplateLocation()
- StructurePlaceSettings lambda$new$0(CompoundTag,ResourceLocation)
- StructurePlaceSettings makeSettings(boolean,Rotation)
+ void loadTemplate(StructureManager)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.IglooPieces
</summary>

```diff
+ void addPieces(StructureManager,BlockPos,Rotation,List,Random)
- void addPieces(StructureManager,BlockPos,Rotation,StructurePieceAccessor,Random)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.MineShaftPieces
</summary>

```diff
+ MineShaftPieces$MineShaftPiece access$100(StructurePiece,List,Random,int,int,int,Direction,int)
- MineShaftPieces$MineShaftPiece access$100(StructurePiece,StructurePieceAccessor,Random,int,int,int,Direction,int)
+ MineShaftPieces$MineShaftPiece createRandomShaftPiece(List,Random,int,int,int,Direction,int,MineshaftFeature$Type)
- MineShaftPieces$MineShaftPiece createRandomShaftPiece(StructurePieceAccessor,Random,int,int,int,Direction,int,MineshaftFeature$Type)
+ MineShaftPieces$MineShaftPiece generateAndAddPiece(StructurePiece,List,Random,int,int,int,Direction,int)
- MineShaftPieces$MineShaftPiece generateAndAddPiece(StructurePiece,StructurePieceAccessor,Random,int,int,int,Direction,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftCorridor
</summary>

```diff
+ BoundingBox findCorridorSize(List,Random,int,int,int,Direction)
- BoundingBox findCorridorSize(StructurePieceAccessor,Random,int,int,int,Direction)
+ void addChildren(StructurePiece,List,Random)
- void addChildren(StructurePiece,StructurePieceAccessor,Random)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftPiece
</summary>

```diff
- void <init>(StructurePieceType,int,MineshaftFeature$Type,BoundingBox)
+ void <init>(StructurePieceType,int,MineshaftFeature$Type)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftStairs
</summary>

```diff
+ BoundingBox findStairs(List,Random,int,int,int,Direction)
- BoundingBox findStairs(StructurePieceAccessor,Random,int,int,int,Direction)
+ void addChildren(StructurePiece,List,Random)
- void addChildren(StructurePiece,StructurePieceAccessor,Random)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherBridgePieces$BridgeEndFiller
</summary>

```diff
+ NetherBridgePieces$BridgeEndFiller createPiece(List,Random,int,int,int,Direction,int)
- NetherBridgePieces$BridgeEndFiller createPiece(StructurePieceAccessor,Random,int,int,int,Direction,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleCorridorStairsPiece
</summary>

```diff
+ NetherBridgePieces$CastleCorridorStairsPiece createPiece(List,int,int,int,Direction,int)
- NetherBridgePieces$CastleCorridorStairsPiece createPiece(StructurePieceAccessor,int,int,int,Direction,int)
+ void addChildren(StructurePiece,List,Random)
- void addChildren(StructurePiece,StructurePieceAccessor,Random)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleEntrance
</summary>

```diff
+ NetherBridgePieces$CastleEntrance createPiece(List,Random,int,int,int,Direction,int)
- NetherBridgePieces$CastleEntrance createPiece(StructurePieceAccessor,Random,int,int,int,Direction,int)
+ void addChildren(StructurePiece,List,Random)
- void addChildren(StructurePiece,StructurePieceAccessor,Random)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorLeftTurnPiece
</summary>

```diff
+ NetherBridgePieces$CastleSmallCorridorLeftTurnPiece createPiece(List,Random,int,int,int,Direction,int)
- NetherBridgePieces$CastleSmallCorridorLeftTurnPiece createPiece(StructurePieceAccessor,Random,int,int,int,Direction,int)
+ void addChildren(StructurePiece,List,Random)
- void addChildren(StructurePiece,StructurePieceAccessor,Random)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorRightTurnPiece
</summary>

```diff
+ NetherBridgePieces$CastleSmallCorridorRightTurnPiece createPiece(List,Random,int,int,int,Direction,int)
- NetherBridgePieces$CastleSmallCorridorRightTurnPiece createPiece(StructurePieceAccessor,Random,int,int,int,Direction,int)
+ void addChildren(StructurePiece,List,Random)
- void addChildren(StructurePiece,StructurePieceAccessor,Random)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherBridgePieces$MonsterThrone
</summary>

```diff
+ NetherBridgePieces$MonsterThrone createPiece(List,int,int,int,int,Direction)
- NetherBridgePieces$MonsterThrone createPiece(StructurePieceAccessor,int,int,int,int,Direction)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherBridgePieces$StairsRoom
</summary>

```diff
+ NetherBridgePieces$StairsRoom createPiece(List,int,int,int,int,Direction)
- NetherBridgePieces$StairsRoom createPiece(StructurePieceAccessor,int,int,int,int,Direction)
+ void addChildren(StructurePiece,List,Random)
- void addChildren(StructurePiece,StructurePieceAccessor,Random)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherFossilPieces
</summary>

```diff
+ void addPieces(StructureManager,List,Random,BlockPos)
- void addPieces(StructureManager,StructurePieceAccessor,Random,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.NoiseAffectingStructureStart
</summary>

```diff
- BoundingBox getBoundingBox()
+ void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
- void <init>(StructureFeature,ChunkPos,int,long)
+ void calculateBoundingBox()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentPiece
</summary>

```diff
- BoundingBox makeBoundingBox(Direction,OceanMonumentPieces$RoomDefinition,int,int,int)
+ void <init>(StructurePieceType,Direction,BoundingBox)
- void <init>(StructurePieceType,Direction,int,BoundingBox)
+ void <init>(StructurePieceType,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.OceanRuinFeature$OceanRuinStart
</summary>

```diff
+ void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
- void <init>(StructureFeature,ChunkPos,int,long)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.OceanRuinPieces
</summary>

```diff
- List allPositions(Random,BlockPos)
+ List allPositions(Random,int,int)
+ void addClusterRuins(StructureManager,Random,Rotation,BlockPos,OceanRuinConfiguration,List)
- void addClusterRuins(StructureManager,Random,Rotation,BlockPos,OceanRuinConfiguration,StructurePieceAccessor)
+ void addPiece(StructureManager,BlockPos,Rotation,List,Random,OceanRuinConfiguration,boolean,float)
- void addPiece(StructureManager,BlockPos,Rotation,StructurePieceAccessor,Random,OceanRuinConfiguration,boolean,float)
+ void addPieces(StructureManager,BlockPos,Rotation,List,Random,OceanRuinConfiguration)
- void addPieces(StructureManager,BlockPos,Rotation,StructurePieceAccessor,Random,OceanRuinConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.StructureStart$1
</summary>

```diff
- boolean isValid()
+ void <init>(StructureFeature,ChunkPos,BoundingBox,int,long)
- void <init>(StructureFeature,ChunkPos,int,long)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.TemplateStructurePiece
</summary>

```diff
- ResourceLocation makeTemplateLocation()
- void <init>(StructurePieceType,CompoundTag,ServerLevel,Function)
+ void <init>(StructurePieceType,CompoundTag)
- void <init>(StructurePieceType,int,StructureManager,ResourceLocation,String,StructurePlaceSettings,BlockPos)
+ void <init>(StructurePieceType,int)
+ void setup(StructureTemplate,BlockPos,StructurePlaceSettings)
```

</details>
</details>
<hr/>