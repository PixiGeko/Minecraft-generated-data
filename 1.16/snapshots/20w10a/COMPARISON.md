## Comparison with [20w09a](https://github.com/PixiGeko/Minecraft-generated-data/tree/20w09a)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Blocks](#blocks)
> - [Recipes](#recipes)
> - [Translations](#translations)
> - [File structure](#file-structure)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">20w09a</th><th>20w10a</th></tr><tr><td>World version</td><td><pre>2510</pre></td><td><pre>2512</pre></td></tr><tr><td>Protocol version</td><td><pre>704</pre></td><td><pre>705</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">20w09a</th><th>20w10a</th></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr></table>
</details>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
block
</summary>

```diff
+ minecraft:crimson_hyphae
+ minecraft:stripped_crimson_hyphae
+ minecraft:stripped_warped_hyphae
+ minecraft:warped_hyphae
```

</details>
<details>
<summary>
custom_stat
</summary>

```diff
+ minecraft:interact_with_smithing_table
```

</details>
<details>
<summary>
item
</summary>

```diff
+ minecraft:crimson_hyphae
+ minecraft:stripped_crimson_hyphae
+ minecraft:stripped_warped_hyphae
+ minecraft:warped_hyphae
```

</details>
<details>
<summary>
memory_module_type
</summary>

```diff
+ minecraft:admiring_disabled
+ minecraft:attack_cooling_down
+ minecraft:nearest_repellent
- minecraft:nearest_visible_soul_fire_item
- minecraft:nearest_visible_warped_fungus
- minecraft:was_hit_by_player
```

</details>
<details>
<summary>
menu
</summary>

```diff
+ minecraft:smithing
```

</details>
<details>
<summary>
sound_event
</summary>

```diff
+ minecraft:ambient.crimson_forest.additions
+ minecraft:ambient.crimson_forest.loop
+ minecraft:ambient.crimson_forest.mood
+ minecraft:ambient.nether_wastes.additions
+ minecraft:ambient.nether_wastes.loop
+ minecraft:ambient.nether_wastes.mood
+ minecraft:ambient.soul_sand_valley.additions
+ minecraft:ambient.soul_sand_valley.loop
+ minecraft:ambient.soul_sand_valley.mood
+ minecraft:ambient.warped_forest.additions
+ minecraft:ambient.warped_forest.loop
+ minecraft:ambient.warped_forest.mood
+ minecraft:block.smithing_table.use
```

</details>
</details>
<hr/>
<details><summary><b><ins>TAGS</ins></b><a name="tags"></a></summary>
<br/>
<details>
<summary>
all_blocks_with_drop.json
</summary>

```diff
+ minecraft:crimson_hyphae
+ minecraft:stripped_crimson_hyphae
+ minecraft:stripped_warped_hyphae
+ minecraft:warped_hyphae
```

</details>
<details>
<summary>
universal_tags/block.json
</summary>

```diff
+ minecraft:crimson_hyphae
+ minecraft:stripped_crimson_hyphae
+ minecraft:stripped_warped_hyphae
+ minecraft:warped_hyphae
```

</details>
<details>
<summary>
universal_tags/custom_stat.json
</summary>

```diff
+ minecraft:interact_with_smithing_table
```

</details>
<details>
<summary>
universal_tags/item.json
</summary>

```diff
+ minecraft:crimson_hyphae
+ minecraft:stripped_crimson_hyphae
+ minecraft:stripped_warped_hyphae
+ minecraft:warped_hyphae
```

</details>
<details>
<summary>
universal_tags/memory_module_type.json
</summary>

```diff
+ minecraft:admiring_disabled
+ minecraft:attack_cooling_down
+ minecraft:nearest_repellent
- minecraft:nearest_visible_soul_fire_item
- minecraft:nearest_visible_warped_fungus
- minecraft:was_hit_by_player
```

</details>
<details>
<summary>
universal_tags/menu.json
</summary>

```diff
+ minecraft:smithing
```

</details>
<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:ambient.crimson_forest.additions
+ minecraft:ambient.crimson_forest.loop
+ minecraft:ambient.crimson_forest.mood
+ minecraft:ambient.nether_wastes.additions
+ minecraft:ambient.nether_wastes.loop
+ minecraft:ambient.nether_wastes.mood
+ minecraft:ambient.soul_sand_valley.additions
+ minecraft:ambient.soul_sand_valley.loop
+ minecraft:ambient.soul_sand_valley.mood
+ minecraft:ambient.warped_forest.additions
+ minecraft:ambient.warped_forest.loop
+ minecraft:ambient.warped_forest.mood
+ minecraft:block.smithing_table.use
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
+ crimson_hyphae.json
+ stripped_crimson_hyphae.json
+ stripped_warped_hyphae.json
+ warped_hyphae.json
```

</details>
</details>
<hr/>
<details><summary><b><ins>RECIPES</ins></b><a name="recipes"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
+ crimson_hyphae.json
- netherite_axe.json
- netherite_boots.json
- netherite_chestplate.json
- netherite_helmet.json
- netherite_hoe.json
- netherite_leggings.json
- netherite_pickaxe.json
- netherite_shovel.json
- netherite_sword.json
+ stripped_crimson_hyphae.json
+ stripped_warped_hyphae.json
+ warped_hyphae.json
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
+ block.minecraft.crimson_hyphae: Crimson Hyphae
+ block.minecraft.stripped_crimson_hyphae: Stripped Crimson Hyphae
+ block.minecraft.stripped_warped_hyphae: Stripped Warped Hyphae
+ block.minecraft.warped_hyphae: Warped Hyphae
+ container.upgrade: Upgrade
+ stat.minecraft.interact_with_smithing_table: Interactions with Smithing Table
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>20w09a</th><th>20w10a</th></tr>
<tr><th align="left"><div style="width:290px">selectWorld.backupJoinConfirmButton</div></th><td>Backup and load</td><td>Create backup and load</td></tr>
<tr><th align="left"><div style="width:290px">selectWorld.tooltip.snapshot1</div></th><td>Don't forget to backup this world</td><td>Don't forget to back up this world</td></tr>
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
+ minecraft/advancements/recipes/building_blocks/crimson_hyphae.json
+ minecraft/advancements/recipes/building_blocks/stripped_crimson_hyphae.json
+ minecraft/advancements/recipes/building_blocks/stripped_warped_hyphae.json
+ minecraft/advancements/recipes/building_blocks/warped_hyphae.json
- minecraft/advancements/recipes/combat/netherite_boots.json
- minecraft/advancements/recipes/combat/netherite_chestplate.json
- minecraft/advancements/recipes/combat/netherite_helmet.json
- minecraft/advancements/recipes/combat/netherite_leggings.json
- minecraft/advancements/recipes/combat/netherite_sword.json
- minecraft/advancements/recipes/tools/netherite_axe.json
- minecraft/advancements/recipes/tools/netherite_hoe.json
- minecraft/advancements/recipes/tools/netherite_pickaxe.json
- minecraft/advancements/recipes/tools/netherite_shovel.json
+ minecraft/loot_tables/blocks/crimson_hyphae.json
+ minecraft/loot_tables/blocks/stripped_crimson_hyphae.json
+ minecraft/loot_tables/blocks/stripped_warped_hyphae.json
+ minecraft/loot_tables/blocks/warped_hyphae.json
+ minecraft/recipes/crimson_hyphae.json
- minecraft/recipes/netherite_axe.json
- minecraft/recipes/netherite_boots.json
- minecraft/recipes/netherite_chestplate.json
- minecraft/recipes/netherite_helmet.json
- minecraft/recipes/netherite_hoe.json
- minecraft/recipes/netherite_leggings.json
- minecraft/recipes/netherite_pickaxe.json
- minecraft/recipes/netherite_shovel.json
- minecraft/recipes/netherite_sword.json
+ minecraft/recipes/stripped_crimson_hyphae.json
+ minecraft/recipes/stripped_warped_hyphae.json
+ minecraft/recipes/warped_hyphae.json
+ minecraft/tags/blocks/hoglin_repellents.json
+ minecraft/tags/blocks/piglin_repellents.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/blockstates/crimson_hyphae.json
+ minecraft/blockstates/stripped_crimson_hyphae.json
+ minecraft/blockstates/stripped_warped_hyphae.json
+ minecraft/blockstates/warped_hyphae.json
+ minecraft/models/block/crimson_hyphae.json
- minecraft/models/block/hanging_lantern.json
- minecraft/models/block/hanging_soul_fire_lantern.json
+ minecraft/models/block/lantern_hanging.json
- minecraft/models/block/redstone_ore_on.json
+ minecraft/models/block/soul_fire_lantern_hanging.json
+ minecraft/models/block/stripped_crimson_hyphae.json
+ minecraft/models/block/stripped_warped_hyphae.json
+ minecraft/models/block/template_anvil.json
+ minecraft/models/block/template_chorus_flower.json
+ minecraft/models/block/template_command_block.json
+ minecraft/models/block/template_daylight_detector.json
+ minecraft/models/block/template_four_turtle_eggs.json
+ minecraft/models/block/template_seagrass.json
+ minecraft/models/block/template_single_face.json
+ minecraft/models/block/template_three_turtle_eggs.json
+ minecraft/models/block/template_turtle_egg.json
+ minecraft/models/block/template_two_turtle_eggs.json
+ minecraft/models/block/tinted_flower_pot_cross.json
+ minecraft/models/block/warped_hyphae.json
- minecraft/models/item/brain_coral_wall_fan.json
- minecraft/models/item/bubble_coral_wall_fan.json
+ minecraft/models/item/crimson_hyphae.json
- minecraft/models/item/dead_brain_coral_wall_fan.json
- minecraft/models/item/dead_bubble_coral_wall_fan.json
- minecraft/models/item/dead_fire_coral_wall_fan.json
- minecraft/models/item/dead_horn_coral_wall_fan.json
- minecraft/models/item/dead_tube_coral_wall_fan.json
- minecraft/models/item/fire_coral_wall_fan.json
- minecraft/models/item/horn_coral_wall_fan.json
+ minecraft/models/item/stripped_crimson_hyphae.json
+ minecraft/models/item/stripped_warped_hyphae.json
- minecraft/models/item/tube_coral_wall_fan.json
+ minecraft/models/item/warped_hyphae.json
+ minecraft/textures/gui/container/smithing.png
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
+ net.minecraft.package-info
+ XXX.ai.attributes.Attribute
- XXX.ai.attributes.AttributeInstance
+ XXX.ai.attributes.AttributeModifier
- XXX.ai.attributes.AttributeModifier$Operation
+ XXX.ai.attributes.BaseAttribute
- XXX.ai.attributes.BaseAttributeMap
+ XXX.ai.attributes.ModifiableAttributeInstance
- XXX.ai.attributes.ModifiableAttributeMap
- XXX.ai.attributes.package-info
+ XXX.ai.attributes.RangedAttribute
+ XXX.ai.behavior.AcquirePoi
- XXX.ai.behavior.package-info
+ XXX.ai.behavior.RememberIfHoglinWasKilled
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
+ XXX.ai.behavior.StartHuntingHoglin
+ XXX.ai.behavior.StopHoldingItemIfNoLongerAdmiring
- XXX.ai.behavior.StrollAroundPoi
+ XXX.ai.behavior.StrollToPoi
- XXX.ai.behavior.StrollToPoiList
+ XXX.ai.behavior.Swim
- XXX.ai.behavior.TradeWithVillager
+ XXX.ai.behavior.UpdateActivityFromSchedule
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
- XXX.ai.goal.FollowOwnerGoal
+ XXX.ai.goal.FollowParentGoal
- XXX.ai.goal.Goal
+ XXX.ai.goal.Goal$Flag
- XXX.ai.goal.GoalSelector
+ XXX.ai.goal.GoalSelector$1
- XXX.ai.goal.GoalSelector$2
+ XXX.ai.goal.InteractGoal
- XXX.ai.goal.JumpGoal
+ XXX.ai.goal.LandOnOwnersShoulderGoal
- XXX.ai.goal.LeapAtTargetGoal
+ XXX.ai.goal.LlamaFollowCaravanGoal
- XXX.ai.goal.LookAtPlayerGoal
+ XXX.ai.goal.LookAtTradingPlayerGoal
- XXX.ai.goal.MeleeAttackGoal
+ XXX.ai.goal.MoveBackToVillage
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
- XXX.ai.sensing.DummySensor
+ XXX.ai.sensing.GolemSensor
- XXX.ai.sensing.HoglinSpecificSensor
+ XXX.ai.sensing.HurtBySensor
- XXX.ai.sensing.InteractableDoorsSensor
+ XXX.ai.sensing.NearestBedSensor
- XXX.ai.sensing.NearestItemSensor
+ XXX.ai.sensing.NearestLivingEntitySensor
- XXX.ai.sensing.package-info
- XXX.ai.sensing.PiglinSpecificSensor
+ XXX.ai.sensing.PlayerSensor
- XXX.ai.sensing.SecondaryPoiSensor
+ XXX.ai.sensing.Sensing
- XXX.ai.sensing.Sensor
+ XXX.ai.sensing.SensorType
- XXX.ai.sensing.VillagerBabiesSensor
+ XXX.ai.sensing.VillagerHostilesSensor
- XXX.ai.targeting.package-info
+ XXX.ai.targeting.TargetingConditions
- XXX.ai.util.package-info
+ XXX.ai.util.RandomPos
+ XXX.ai.village.package-info
+ XXX.ai.village.ReputationEventType
- XXX.ai.village.ReputationEventType$1
+ XXX.ai.village.VillageSiege
- XXX.ai.village.VillageSiege$State
- XXX.animal.horse.AbstractChestedHorse
+ XXX.animal.horse.AbstractHorse
- XXX.animal.horse.Donkey
+ XXX.animal.horse.Horse
- XXX.animal.horse.Horse$HorseGroupData
+ XXX.animal.horse.Llama
- XXX.animal.horse.Llama$1
+ XXX.animal.horse.Llama$LlamaAttackWolfGoal
- XXX.animal.horse.Llama$LlamaGroupData
+ XXX.animal.horse.Llama$LlamaHurtByTargetGoal
- XXX.animal.horse.Mule
- XXX.animal.horse.package-info
+ XXX.animal.horse.SkeletonHorse
- XXX.animal.horse.SkeletonTrapGoal
+ XXX.animal.horse.TraderLlama
- XXX.animal.horse.TraderLlama$TraderLlamaDefendWanderingTraderGoal
+ XXX.animal.horse.ZombieHorse
- XXX.block.entity.AbstractFurnaceBlockEntity
+ XXX.block.entity.AbstractFurnaceBlockEntity$1
- XXX.block.entity.BannerBlockEntity
+ XXX.block.entity.BannerPattern
- XXX.block.entity.BannerPattern$Builder
+ XXX.block.entity.BarrelBlockEntity
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
- XXX.block.entity.BlastFurnaceBlockEntity
+ XXX.block.entity.BlockEntity
- XXX.block.entity.BlockEntityType
+ XXX.block.entity.BlockEntityType$Builder
- XXX.block.entity.BrewingStandBlockEntity
+ XXX.block.entity.BrewingStandBlockEntity$1
- XXX.block.entity.CampfireBlockEntity
+ XXX.block.entity.ChestBlockEntity
- XXX.block.entity.CommandBlockEntity
+ XXX.block.entity.CommandBlockEntity$1
- XXX.block.entity.CommandBlockEntity$Mode
+ XXX.block.entity.ComparatorBlockEntity
- XXX.block.entity.ConduitBlockEntity
+ XXX.block.entity.DaylightDetectorBlockEntity
- XXX.block.entity.DispenserBlockEntity
+ XXX.block.entity.DropperBlockEntity
- XXX.block.entity.EnchantmentTableBlockEntity
+ XXX.block.entity.EnderChestBlockEntity
- XXX.block.entity.FurnaceBlockEntity
+ XXX.block.entity.Hopper
- XXX.block.entity.HopperBlockEntity
+ XXX.block.entity.JigsawBlockEntity
- XXX.block.entity.JukeboxBlockEntity
+ XXX.block.entity.LecternBlockEntity
- XXX.block.entity.LecternBlockEntity$1
+ XXX.block.entity.LecternBlockEntity$2
- XXX.block.entity.LidBlockEntity
+ XXX.block.entity.package-info
+ XXX.block.entity.RandomizableContainerBlockEntity
- XXX.block.entity.ShulkerBoxBlockEntity
+ XXX.block.entity.ShulkerBoxBlockEntity$1
- XXX.block.entity.ShulkerBoxBlockEntity$AnimationStatus
+ XXX.block.entity.SignBlockEntity
- XXX.block.entity.SkullBlockEntity
+ XXX.block.entity.SmokerBlockEntity
- XXX.block.entity.SpawnerBlockEntity
+ XXX.block.entity.SpawnerBlockEntity$1
- XXX.block.entity.StructureBlockEntity
+ XXX.block.entity.StructureBlockEntity$1
- XXX.block.entity.StructureBlockEntity$UpdateType
+ XXX.block.entity.TheEndGatewayBlockEntity
- XXX.block.entity.TheEndPortalBlockEntity
+ XXX.block.entity.TickableBlockEntity
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
+ XXX.block.state.AbstractStateHolder
- XXX.block.state.AbstractStateHolder$1
+ XXX.block.state.BlockState
- XXX.block.state.BlockState$1
+ XXX.block.state.BlockState$Cache
- XXX.block.state.package-info
- XXX.block.state.StateDefinition
+ XXX.block.state.StateDefinition$Builder
- XXX.block.state.StateDefinition$Factory
+ XXX.block.state.StateHolder
- XXX.boss.enderdragon.EndCrystal
+ XXX.boss.enderdragon.EnderDragon
- XXX.boss.enderdragon.package-info
+ XXX.boss.wither.package-info
+ XXX.boss.wither.WitherBoss
- XXX.boss.wither.WitherBoss$WitherDoNothingGoal
+ XXX.chunk.storage.ChunkSerializer
- XXX.chunk.storage.ChunkStorage
+ XXX.chunk.storage.IOWorker
- XXX.chunk.storage.IOWorker$1
+ XXX.chunk.storage.IOWorker$PendingStore
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
- XXX.data.models.BlockModelGenerators$1
- XXX.data.models.BlockModelGenerators$BlockFamilyProvider
- XXX.data.models.BlockModelGenerators$WoodProvider
- XXX.data.models.ModelProvider
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
- XXX.datafix.fixes.EntityProjectileOwnerFix
+ XXX.datafix.fixes.EntityPufferfishRenameFix
- XXX.datafix.fixes.EntityRavagerRenameFix
+ XXX.datafix.fixes.EntityRedundantChanceTagsFix
- XXX.datafix.fixes.EntityRenameFix
+ XXX.datafix.fixes.EntityRidingToPassengersFix
- XXX.datafix.fixes.EntityShulkerColorFix
+ XXX.datafix.fixes.EntitySkeletonSplitFix
- XXX.datafix.fixes.EntityStringUuidFix
+ XXX.datafix.fixes.EntityTheRenameningFix
- XXX.datafix.fixes.EntityTippedArrowFix
+ XXX.datafix.fixes.EntityWolfColorFix
- XXX.datafix.fixes.EntityZombieSplitFix
+ XXX.datafix.fixes.EntityZombieVillagerTypeFix
- XXX.datafix.fixes.EntityZombifiedPiglinRenameFix
+ XXX.datafix.fixes.ForcePoiRebuild
- XXX.datafix.fixes.FurnaceRecipeFix
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
- XXX.datafix.fixes.ItemWaterPotionFix
+ XXX.datafix.fixes.ItemWrittenBookPagesStrictJsonFix
- XXX.datafix.fixes.LeavesFix
+ XXX.datafix.fixes.LeavesFix$LeavesSection
- XXX.datafix.fixes.LeavesFix$Section
+ XXX.datafix.fixes.LevelDataGeneratorOptionsFix
- XXX.datafix.fixes.LevelFlatGeneratorInfoFix
+ XXX.datafix.fixes.MapIdFix
- XXX.datafix.fixes.MemoryExpiryDataFix
+ XXX.datafix.fixes.MobSpawnerEntityIdentifiersFix
- XXX.datafix.fixes.NamedEntityFix
+ XXX.datafix.fixes.NewVillageFix
- XXX.datafix.fixes.ObjectiveDisplayNameFix
+ XXX.datafix.fixes.ObjectiveRenderTypeFix
- XXX.datafix.fixes.OptionsAddTextBackgroundFix
+ XXX.datafix.fixes.OptionsForceVBOFix
- XXX.datafix.fixes.OptionsKeyLwjgl3Fix
+ XXX.datafix.fixes.OptionsKeyTranslationFix
- XXX.datafix.fixes.OptionsLowerCaseLanguageFix
+ XXX.datafix.fixes.package-info
+ XXX.datafix.fixes.PoiTypeRename
- XXX.datafix.fixes.RecipesFix
+ XXX.datafix.fixes.RecipesRenameFix
- XXX.datafix.fixes.RecipesRenameningFix
+ XXX.datafix.fixes.References
- XXX.datafix.fixes.RenameBiomesFix
+ XXX.datafix.fixes.RenamedCoralFansFix
- XXX.datafix.fixes.RenamedCoralFix
+ XXX.datafix.fixes.ReorganizePoi
- XXX.datafix.fixes.SavedDataVillageCropFix
+ XXX.datafix.fixes.SimpleEntityRenameFix
- XXX.datafix.fixes.SimplestEntityRenameFix
+ XXX.datafix.fixes.StatsCounterFix
- XXX.datafix.fixes.StructureReferenceCountFix
+ XXX.datafix.fixes.SwimStatsRenameFix
- XXX.datafix.fixes.TeamDisplayNameFix
+ XXX.datafix.fixes.TrappedChestBlockEntityFix
- XXX.datafix.fixes.TrappedChestBlockEntityFix$TrappedChestSection
+ XXX.datafix.fixes.VillagerDataFix
- XXX.datafix.fixes.VillagerRebuildLevelAndXpFix
+ XXX.datafix.fixes.VillagerTradeFix
- XXX.datafix.fixes.WallPropertyFix
+ XXX.datafix.fixes.WriteAndReadFix
- XXX.datafix.fixes.ZombieVillagerRebuildXpFix
+ XXX.datafix.schemas.NamespacedSchema
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
- XXX.dimension.end.DragonRespawnAnimation
+ XXX.dimension.end.DragonRespawnAnimation$1
- XXX.dimension.end.DragonRespawnAnimation$2
+ XXX.dimension.end.DragonRespawnAnimation$3
- XXX.dimension.end.DragonRespawnAnimation$4
+ XXX.dimension.end.DragonRespawnAnimation$5
- XXX.dimension.end.EndDragonFight
- XXX.dimension.end.package-info
+ XXX.dimension.end.TheEndDimension
+ XXX.enderdragon.phases.AbstractDragonPhaseInstance
- XXX.enderdragon.phases.AbstractDragonSittingPhase
+ XXX.enderdragon.phases.DragonChargePlayerPhase
- XXX.enderdragon.phases.DragonDeathPhase
+ XXX.enderdragon.phases.DragonHoldingPatternPhase
- XXX.enderdragon.phases.DragonHoverPhase
+ XXX.enderdragon.phases.DragonLandingApproachPhase
- XXX.enderdragon.phases.DragonLandingPhase
+ XXX.enderdragon.phases.DragonPhaseInstance
- XXX.enderdragon.phases.DragonSittingAttackingPhase
+ XXX.enderdragon.phases.DragonSittingFlamingPhase
- XXX.enderdragon.phases.DragonSittingScanningPhase
+ XXX.enderdragon.phases.DragonStrafePlayerPhase
- XXX.enderdragon.phases.DragonTakeoffPhase
+ XXX.enderdragon.phases.EnderDragonPhase
- XXX.enderdragon.phases.EnderDragonPhaseManager
+ XXX.enderdragon.phases.package-info
- XXX.entity.ai.Brain
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
- XXX.entity.animal.IronGolem$Crackiness
+ XXX.entity.animal.MushroomCow
- XXX.entity.animal.MushroomCow$MushroomType
+ XXX.entity.animal.Ocelot
- XXX.entity.animal.Ocelot$OcelotAvoidEntityGoal
+ XXX.entity.animal.Ocelot$OcelotTemptGoal
+ XXX.entity.animal.package-info
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
+ XXX.entity.animal.Turtle$TurtleTemptGoal
- XXX.entity.animal.Turtle$TurtleTravelGoal
+ XXX.entity.animal.WaterAnimal
- XXX.entity.animal.Wolf
+ XXX.entity.animal.Wolf$WolfAvoidEntityGoal
- XXX.entity.boss.BossMob
+ XXX.entity.boss.EnderDragonPart
- XXX.entity.boss.package-info
- XXX.entity.decoration.ArmorStand
+ XXX.entity.decoration.ArmorStand$1
- XXX.entity.decoration.HangingEntity
+ XXX.entity.decoration.HangingEntity$1
- XXX.entity.decoration.ItemFrame
+ XXX.entity.decoration.ItemFrame$1
- XXX.entity.decoration.LeashFenceKnotEntity
+ XXX.entity.decoration.Motive
+ XXX.entity.decoration.package-info
- XXX.entity.decoration.Painting
- XXX.entity.fishing.FishingHook
+ XXX.entity.fishing.FishingHook$FishHookState
- XXX.entity.fishing.package-info
+ XXX.entity.global.LightningBolt
- XXX.entity.global.package-info
+ XXX.entity.item.FallingBlockEntity
- XXX.entity.item.ItemEntity
- XXX.entity.item.package-info
+ XXX.entity.item.PrimedTnt
+ XXX.entity.monster.AbstractIllager
- XXX.entity.monster.AbstractIllager$IllagerArmPose
+ XXX.entity.monster.AbstractIllager$RaiderOpenDoorGoal
- XXX.entity.monster.AbstractSkeleton
+ XXX.entity.monster.AbstractSkeleton$1
- XXX.entity.monster.Blaze
+ XXX.entity.monster.Blaze$BlazeAttackGoal
- XXX.entity.monster.CaveSpider
+ XXX.entity.monster.Creeper
- XXX.entity.monster.CrossbowAttackMob
+ XXX.entity.monster.Drowned
- XXX.entity.monster.Drowned$DrownedAttackGoal
+ XXX.entity.monster.Drowned$DrownedGoToBeachGoal
- XXX.entity.monster.Drowned$DrownedGoToWaterGoal
+ XXX.entity.monster.Drowned$DrownedMoveControl
- XXX.entity.monster.Drowned$DrownedSwimUpGoal
+ XXX.entity.monster.Drowned$DrownedTridentAttackGoal
- XXX.entity.monster.ElderGuardian
+ XXX.entity.monster.EnderMan
- XXX.entity.monster.EnderMan$EndermanFreezeWhenLookedAt
+ XXX.entity.monster.EnderMan$EndermanLeaveBlockGoal
- XXX.entity.monster.EnderMan$EndermanLookForPlayerGoal
+ XXX.entity.monster.EnderMan$EndermanTakeBlockGoal
- XXX.entity.monster.Endermite
+ XXX.entity.monster.Enemy
- XXX.entity.monster.Evoker
+ XXX.entity.monster.Evoker$1
- XXX.entity.monster.Evoker$EvokerAttackSpellGoal
+ XXX.entity.monster.Evoker$EvokerCastingSpellGoal
- XXX.entity.monster.Evoker$EvokerSummonSpellGoal
+ XXX.entity.monster.Evoker$EvokerWololoSpellGoal
- XXX.entity.monster.Ghast
+ XXX.entity.monster.Ghast$GhastLookGoal
- XXX.entity.monster.Ghast$GhastMoveControl
+ XXX.entity.monster.Ghast$GhastShootFireballGoal
- XXX.entity.monster.Ghast$RandomFloatAroundGoal
+ XXX.entity.monster.Giant
- XXX.entity.monster.Guardian
+ XXX.entity.monster.Guardian$GuardianAttackGoal
- XXX.entity.monster.Guardian$GuardianAttackSelector
+ XXX.entity.monster.Guardian$GuardianMoveControl
- XXX.entity.monster.Husk
+ XXX.entity.monster.Illusioner
- XXX.entity.monster.Illusioner$1
+ XXX.entity.monster.Illusioner$IllusionerBlindnessSpellGoal
- XXX.entity.monster.Illusioner$IllusionerMirrorSpellGoal
+ XXX.entity.monster.MagmaCube
- XXX.entity.monster.Monster
- XXX.entity.monster.package-info
+ XXX.entity.monster.PatrollingMonster
- XXX.entity.monster.PatrollingMonster$LongDistancePatrolGoal
+ XXX.entity.monster.Phantom
- XXX.entity.monster.Phantom$1
+ XXX.entity.monster.Phantom$AttackPhase
- XXX.entity.monster.Phantom$PhantomAttackPlayerTargetGoal
+ XXX.entity.monster.Phantom$PhantomAttackStrategyGoal
- XXX.entity.monster.Phantom$PhantomBodyRotationControl
+ XXX.entity.monster.Phantom$PhantomCircleAroundAnchorGoal
- XXX.entity.monster.Phantom$PhantomLookControl
+ XXX.entity.monster.Phantom$PhantomMoveControl
- XXX.entity.monster.Phantom$PhantomMoveTargetGoal
+ XXX.entity.monster.Phantom$PhantomSweepAttackGoal
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
- XXX.entity.monster.ZombifiedPiglin
+ XXX.entity.monster.ZombifiedPiglin$ZombifiedPiglinAngerTargetGoal
- XXX.entity.monster.ZombifiedPiglin$ZombifiedPiglinHurtByOtherGoal
- XXX.feature.blockplacers.BlockPlacer
+ XXX.feature.blockplacers.BlockPlacerType
- XXX.feature.blockplacers.ColumnPlacer
+ XXX.feature.blockplacers.DoublePlantPlacer
+ XXX.feature.blockplacers.package-info
- XXX.feature.blockplacers.SimpleBlockPlacer
- XXX.feature.configurations.BlockBlobConfiguration
+ XXX.feature.configurations.BlockPileConfiguration
- XXX.feature.configurations.BlockStateConfiguration
+ XXX.feature.configurations.BuriedTreasureConfiguration
- XXX.feature.configurations.ChanceRangeDecoratorConfiguration
+ XXX.feature.configurations.CountFeatureConfiguration
- XXX.feature.configurations.CountRangeDecoratorConfiguration
+ XXX.feature.configurations.DecoratedFeatureConfiguration
- XXX.feature.configurations.DecoratorConfiguration
+ XXX.feature.configurations.DiskConfiguration
- XXX.feature.configurations.EndGatewayConfiguration
+ XXX.feature.configurations.FeatureConfiguration
- XXX.feature.configurations.FeatureRadiusConfiguration
+ XXX.feature.configurations.HugeMushroomFeatureConfiguration
- XXX.feature.configurations.LayerConfiguration
+ XXX.feature.configurations.MegaTreeConfiguration
- XXX.feature.configurations.MegaTreeConfiguration$MegaTreeConfigurationBuilder
+ XXX.feature.configurations.MineshaftConfiguration
- XXX.feature.configurations.NoiseDependantDecoratorConfiguration
+ XXX.feature.configurations.NoneDecoratorConfiguration
- XXX.feature.configurations.NoneFeatureConfiguration
+ XXX.feature.configurations.OceanRuinConfiguration
- XXX.feature.configurations.OreConfiguration
+ XXX.feature.configurations.OreConfiguration$Predicates
+ XXX.feature.configurations.package-info
- XXX.feature.configurations.ProbabilityFeatureConfiguration
+ XXX.feature.configurations.RandomBooleanFeatureConfiguration
- XXX.feature.configurations.RandomFeatureConfiguration
+ XXX.feature.configurations.RandomPatchConfiguration
- XXX.feature.configurations.RandomPatchConfiguration$1
+ XXX.feature.configurations.RandomPatchConfiguration$GrassConfigurationBuilder
- XXX.feature.configurations.RandomRandomFeatureConfiguration
+ XXX.feature.configurations.ReplaceBlockConfiguration
- XXX.feature.configurations.SeagrassFeatureConfiguration
+ XXX.feature.configurations.ShipwreckConfiguration
- XXX.feature.configurations.SimpleBlockConfiguration
+ XXX.feature.configurations.SimpleRandomFeatureConfiguration
- XXX.feature.configurations.SmallTreeConfiguration
+ XXX.feature.configurations.SmallTreeConfiguration$SmallTreeConfigurationBuilder
- XXX.feature.configurations.SpikeConfiguration
+ XXX.feature.configurations.SpringConfiguration
- XXX.feature.configurations.TreeConfiguration
+ XXX.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
- XXX.feature.configurations.VillageConfiguration
- XXX.feature.foliageplacers.AcaciaFoliagePlacer
+ XXX.feature.foliageplacers.BlobFoliagePlacer
- XXX.feature.foliageplacers.FoliagePlacer
+ XXX.feature.foliageplacers.FoliagePlacerType
- XXX.feature.foliageplacers.package-info
- XXX.feature.foliageplacers.PineFoliagePlacer
+ XXX.feature.foliageplacers.SpruceFoliagePlacer
- XXX.feature.stateproviders.BlockStateProvider
+ XXX.feature.stateproviders.BlockStateProviderType
- XXX.feature.stateproviders.ForestFlowerProvider
+ XXX.feature.stateproviders.package-info
+ XXX.feature.stateproviders.PlainFlowerProvider
- XXX.feature.stateproviders.RotatedBlockProvider
+ XXX.feature.stateproviders.SimpleStateProvider
- XXX.feature.stateproviders.WeightedStateProvider
- XXX.feature.structures.EmptyPoolElement
+ XXX.feature.structures.FeaturePoolElement
- XXX.feature.structures.JigsawJunction
+ XXX.feature.structures.JigsawPlacement
- XXX.feature.structures.JigsawPlacement$1
+ XXX.feature.structures.JigsawPlacement$PieceFactory
- XXX.feature.structures.JigsawPlacement$PieceState
+ XXX.feature.structures.JigsawPlacement$Placer
- XXX.feature.structures.ListPoolElement
+ XXX.feature.structures.package-info
+ XXX.feature.structures.SinglePoolElement
- XXX.feature.structures.StructurePoolElement
+ XXX.feature.structures.StructurePoolElementType
- XXX.feature.structures.StructureTemplatePool
+ XXX.feature.structures.StructureTemplatePool$Projection
- XXX.feature.structures.StructureTemplatePools
- XXX.feature.treedecorators.AlterGroundDecorator
+ XXX.feature.treedecorators.BeehiveDecorator
- XXX.feature.treedecorators.CocoaDecorator
+ XXX.feature.treedecorators.LeaveVineDecorator
+ XXX.feature.treedecorators.package-info
- XXX.feature.treedecorators.TreeDecorator
+ XXX.feature.treedecorators.TreeDecoratorType
- XXX.feature.treedecorators.TrunkVineDecorator
- XXX.gametest.framework.BeforeBatch
+ XXX.gametest.framework.GameTest
- XXX.gametest.framework.GameTestAssertException
+ XXX.gametest.framework.GameTestAssertPosException
- XXX.gametest.framework.GameTestBatch
+ XXX.gametest.framework.GameTestBatchRunner
- XXX.gametest.framework.GameTestBatchRunner$1
+ XXX.gametest.framework.GameTestEvent
- XXX.gametest.framework.GameTestGenerator
+ XXX.gametest.framework.GameTestHelper
- XXX.gametest.framework.GameTestInfo
+ XXX.gametest.framework.GameTestListener
- XXX.gametest.framework.GameTestRegistry
+ XXX.gametest.framework.GameTestRunner
- XXX.gametest.framework.GameTestRunner$1
+ XXX.gametest.framework.GameTestSequence
- XXX.gametest.framework.GameTestSequence$Condition
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
- XXX.goal.target.DefendVillageTargetGoal
+ XXX.goal.target.HurtByTargetGoal
- XXX.goal.target.NearestAttackableTargetGoal
+ XXX.goal.target.NearestAttackableWitchTargetGoal
- XXX.goal.target.NearestHealableRaiderTargetGoal
+ XXX.goal.target.NonTameRandomTargetGoal
- XXX.goal.target.OwnerHurtByTargetGoal
+ XXX.goal.target.OwnerHurtTargetGoal
+ XXX.goal.target.package-info
- XXX.goal.target.TargetGoal
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
- XXX.level.block.GrowingPlantBodyBlock
- XXX.level.block.HalfTransparentBlock
+ XXX.level.block.HayBlock
- XXX.level.block.HoneyBlock
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
- XXX.level.block.NetherrackBlock
- XXX.level.block.NetherSproutsBlock
+ XXX.level.block.NetherWartBlock
+ XXX.level.block.NoteBlock
- XXX.level.block.NyliumBlock
+ XXX.level.block.ObserverBlock
- XXX.level.block.OreBlock
+ XXX.level.block.package-info
+ XXX.level.block.PipeBlock
- XXX.level.block.PlayerHeadBlock
+ XXX.level.block.PlayerWallHeadBlock
- XXX.level.block.PotatoBlock
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
+ XXX.level.block.RootsBlock
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
+ XXX.level.block.SoulFireBlock
- XXX.level.block.SoulSandBlock
+ XXX.level.block.SoundType
- XXX.level.block.SpawnerBlock
+ XXX.level.block.SpongeBlock
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
- XXX.level.block.SweetBerryBushBlock
+ XXX.level.block.TallFlowerBlock
- XXX.level.block.TallGrassBlock
+ XXX.level.block.TallSeagrass
- XXX.level.block.TargetBlock
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
+ XXX.level.block.WallBlock$1
- XXX.level.block.WallSignBlock
+ XXX.level.block.WallSkullBlock
- XXX.level.block.WallTorchBlock
+ XXX.level.block.WaterlilyBlock
- XXX.level.block.WebBlock
+ XXX.level.block.WeepingVines
- XXX.level.block.WeepingVinesPlant
+ XXX.level.block.WeightedPressurePlateBlock
- XXX.level.block.WetSpongeBlock
+ XXX.level.block.WitherRoseBlock
- XXX.level.block.WitherSkullBlock
+ XXX.level.block.WitherWallSkullBlock
- XXX.level.block.WoodButtonBlock
+ XXX.level.block.WoolCarpetBlock
+ XXX.level.border.BorderChangeListener
- XXX.level.border.BorderChangeListener$DelegateBorderChangeListener
+ XXX.level.border.BorderStatus
+ XXX.level.border.package-info
- XXX.level.border.WorldBorder
+ XXX.level.border.WorldBorder$1
- XXX.level.border.WorldBorder$BorderExtent
+ XXX.level.border.WorldBorder$MovingBorderExtent
- XXX.level.border.WorldBorder$StaticBorderExtent
- XXX.level.chunk.ChunkAccess
+ XXX.level.chunk.ChunkBiomeContainer
- XXX.level.chunk.ChunkGenerator
+ XXX.level.chunk.ChunkGeneratorFactory
- XXX.level.chunk.ChunkGeneratorType
+ XXX.level.chunk.ChunkSource
- XXX.level.chunk.ChunkStatus
+ XXX.level.chunk.ChunkStatus$ChunkType
- XXX.level.chunk.ChunkStatus$GenerationTask
+ XXX.level.chunk.ChunkStatus$LoadingTask
- XXX.level.chunk.ChunkStatus$SimpleGenerationTask
+ XXX.level.chunk.DataLayer
- XXX.level.chunk.EmptyLevelChunk
+ XXX.level.chunk.FeatureAccess
- XXX.level.chunk.GlobalPalette
+ XXX.level.chunk.HashMapPalette
- XXX.level.chunk.ImposterProtoChunk
+ XXX.level.chunk.LevelChunk
- XXX.level.chunk.LevelChunk$EntityCreationType
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
+ XXX.level.levelgen.package-info
- XXX.level.levelgen.PatrolSpawner
+ XXX.level.levelgen.PhantomSpawner
- XXX.level.levelgen.TheEndGeneratorSettings
+ XXX.level.levelgen.TheEndLevelSource
- XXX.level.levelgen.WorldgenRandom
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
- XXX.level.material.Fluids
- XXX.level.material.FluidState
+ XXX.level.material.FluidStateImpl
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
- XXX.level.storage.LevelStorage
+ XXX.level.storage.LevelStorageException
- XXX.level.storage.LevelStorageSource
+ XXX.level.storage.LevelStorageSource$1
- XXX.level.storage.LevelSummary
+ XXX.level.storage.McRegionUpgrader
- XXX.level.storage.package-info
- XXX.level.storage.PlayerIO
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
+ XXX.levelgen.carver.CanyonWorldCarver
- XXX.levelgen.carver.CarverConfiguration
+ XXX.levelgen.carver.CaveWorldCarver
- XXX.levelgen.carver.ConfiguredWorldCarver
+ XXX.levelgen.carver.NetherWorldCarver
- XXX.levelgen.carver.NoneCarverConfiguration
- XXX.levelgen.carver.package-info
+ XXX.levelgen.carver.UnderwaterCanyonWorldCarver
- XXX.levelgen.carver.UnderwaterCaveWorldCarver
+ XXX.levelgen.carver.WorldCarver
+ XXX.levelgen.feature.AbstractFlowerFeature
- XXX.levelgen.feature.AbstractHugeMushroomFeature
+ XXX.levelgen.feature.AbstractSmallTreeFeature
- XXX.levelgen.feature.AbstractTreeFeature
+ XXX.levelgen.feature.AcaciaFeature
- XXX.levelgen.feature.BambooFeature
+ XXX.levelgen.feature.BasaltPillarFeature
- XXX.levelgen.feature.BlockBlobFeature
+ XXX.levelgen.feature.BlockPileFeature
- XXX.levelgen.feature.BlueIceFeature
+ XXX.levelgen.feature.BonusChestFeature
- XXX.levelgen.feature.BuriedTreasureFeature
+ XXX.levelgen.feature.BuriedTreasureFeature$BuriedTreasureStart
- XXX.levelgen.feature.ChorusPlantFeature
+ XXX.levelgen.feature.ConfiguredFeature
- XXX.levelgen.feature.CoralClawFeature
+ XXX.levelgen.feature.CoralFeature
- XXX.levelgen.feature.CoralMushroomFeature
+ XXX.levelgen.feature.CoralTreeFeature
- XXX.levelgen.feature.DarkOakFeature
+ XXX.levelgen.feature.DecoratedFeature
- XXX.levelgen.feature.DecoratedFlowerFeature
+ XXX.levelgen.feature.DefaultFlowerFeature
- XXX.levelgen.feature.DesertPyramidFeature
+ XXX.levelgen.feature.DesertPyramidFeature$FeatureStart
- XXX.levelgen.feature.DesertVillagePools
+ XXX.levelgen.feature.DesertWellFeature
- XXX.levelgen.feature.DiskReplaceFeature
+ XXX.levelgen.feature.EndCityFeature
- XXX.levelgen.feature.EndCityFeature$EndCityStart
+ XXX.levelgen.feature.EndGatewayFeature
- XXX.levelgen.feature.EndIslandFeature
+ XXX.levelgen.feature.EndPodiumFeature
- XXX.levelgen.feature.FancyTreeFeature
+ XXX.levelgen.feature.FancyTreeFeature$FoliageCoords
- XXX.levelgen.feature.Feature
+ XXX.levelgen.feature.FillLayerFeature
- XXX.levelgen.feature.FossilFeature
+ XXX.levelgen.feature.GlowstoneFeature
- XXX.levelgen.feature.GroundBushFeature
+ XXX.levelgen.feature.HugeBrownMushroomFeature
- XXX.levelgen.feature.HugeFungusConfiguration
+ XXX.levelgen.feature.HugeFungusFeature
- XXX.levelgen.feature.HugeRedMushroomFeature
+ XXX.levelgen.feature.IcebergFeature
+ XXX.levelgen.feature.IcePatchFeature
- XXX.levelgen.feature.IceSpikeFeature
- XXX.levelgen.feature.IglooFeature
+ XXX.levelgen.feature.IglooFeature$FeatureStart
- XXX.levelgen.feature.JunglePyramidFeature
+ XXX.levelgen.feature.JunglePyramidFeature$FeatureStart
- XXX.levelgen.feature.KelpFeature
+ XXX.levelgen.feature.LakeFeature
- XXX.levelgen.feature.MegaJungleTreeFeature
+ XXX.levelgen.feature.MegaPineTreeFeature
- XXX.levelgen.feature.MegaTreeFeature
+ XXX.levelgen.feature.MineshaftFeature
- XXX.levelgen.feature.MineshaftFeature$MineShaftStart
+ XXX.levelgen.feature.MineshaftFeature$Type
- XXX.levelgen.feature.MonsterRoomFeature
+ XXX.levelgen.feature.NetherForestVegetationFeature
- XXX.levelgen.feature.NetherFortressFeature
+ XXX.levelgen.feature.NetherFortressFeature$NetherBridgeStart
- XXX.levelgen.feature.NoOpFeature
+ XXX.levelgen.feature.NoSurfaceOreFeature
- XXX.levelgen.feature.OceanMonumentFeature
+ XXX.levelgen.feature.OceanMonumentFeature$OceanMonumentStart
- XXX.levelgen.feature.OreFeature
+ XXX.levelgen.feature.package-info
+ XXX.levelgen.feature.PillagerOutpostFeature
- XXX.levelgen.feature.PillagerOutpostFeature$FeatureStart
+ XXX.levelgen.feature.PlainVillagePools
- XXX.levelgen.feature.RandomBooleanSelectorFeature
+ XXX.levelgen.feature.RandomPatchFeature
- XXX.levelgen.feature.RandomRandomFeature
+ XXX.levelgen.feature.RandomScatteredFeature
- XXX.levelgen.feature.RandomSelectorFeature
+ XXX.levelgen.feature.ReplaceBlockFeature
- XXX.levelgen.feature.SavannaVillagePools
- XXX.levelgen.feature.SeagrassFeature
+ XXX.levelgen.feature.SeaPickleFeature
+ XXX.levelgen.feature.ShipwreckFeature
- XXX.levelgen.feature.ShipwreckFeature$FeatureStart
+ XXX.levelgen.feature.SimpleBlockFeature
- XXX.levelgen.feature.SimpleRandomSelectorFeature
+ XXX.levelgen.feature.SimulatedFeature
- XXX.levelgen.feature.SnowAndFreezeFeature
+ XXX.levelgen.feature.SnowyVillagePools
- XXX.levelgen.feature.SpikeFeature
+ XXX.levelgen.feature.SpikeFeature$1
- XXX.levelgen.feature.SpikeFeature$EndSpike
+ XXX.levelgen.feature.SpikeFeature$SpikeCacheLoader
- XXX.levelgen.feature.SpringFeature
+ XXX.levelgen.feature.StrongholdFeature
- XXX.levelgen.feature.StrongholdFeature$StrongholdStart
+ XXX.levelgen.feature.StructureFeature
- XXX.levelgen.feature.StructureFeature$StructureStartFactory
+ XXX.levelgen.feature.StructurePieceType
- XXX.levelgen.feature.SwamplandHutFeature
+ XXX.levelgen.feature.SwamplandHutFeature$FeatureStart
- XXX.levelgen.feature.TaigaVillagePools
+ XXX.levelgen.feature.TreeFeature
- XXX.levelgen.feature.VillageFeature
+ XXX.levelgen.feature.VillageFeature$FeatureStart
- XXX.levelgen.feature.VillagePieces
+ XXX.levelgen.feature.VillagePieces$VillagePiece
- XXX.levelgen.feature.VinesFeature
+ XXX.levelgen.feature.VoidStartPlatformFeature
- XXX.levelgen.feature.WeepingVinesFeature
+ XXX.levelgen.feature.WeightedConfiguredFeature
- XXX.levelgen.feature.WoodlandMansionFeature
+ XXX.levelgen.feature.WoodlandMansionFeature$WoodlandMansionStart
- XXX.levelgen.flat.FlatLayerInfo
+ XXX.levelgen.flat.FlatLevelGeneratorSettings
- XXX.levelgen.flat.package-info
- XXX.levelgen.placement.CarvingMaskDecorator
+ XXX.levelgen.placement.CarvingMaskDecoratorConfiguration
- XXX.levelgen.placement.ChanceDecoratorConfiguration
+ XXX.levelgen.placement.ChanceHeightmapDecorator
- XXX.levelgen.placement.ChanceHeightmapDoubleDecorator
+ XXX.levelgen.placement.ChancePassthroughDecorator
- XXX.levelgen.placement.ChanceTopSolidHeightmapDecorator
+ XXX.levelgen.placement.ChorusPlantPlacementDecorator
- XXX.levelgen.placement.ConfiguredDecorator
+ XXX.levelgen.placement.CountBiasedRangeDecorator
- XXX.levelgen.placement.CountChanceHeightmapDecorator
+ XXX.levelgen.placement.CountChanceHeightmapDoubleDecorator
- XXX.levelgen.placement.CountDepthAverageDecorator
+ XXX.levelgen.placement.CountHeighmapDoubleDecorator
- XXX.levelgen.placement.CountHeight64Decorator
+ XXX.levelgen.placement.CountHeightmap32Decorator
- XXX.levelgen.placement.CountHeightmapDecorator
+ XXX.levelgen.placement.CountTopSolidDecorator
- XXX.levelgen.placement.CountVeryBiasedRangeDecorator
+ XXX.levelgen.placement.CountWithExtraChanceHeightmapDecorator
- XXX.levelgen.placement.DarkOakTreePlacementDecorator
+ XXX.levelgen.placement.DepthAverageConfigation
- XXX.levelgen.placement.EmeraldPlacementDecorator
+ XXX.levelgen.placement.EndGatewayPlacementDecorator
- XXX.levelgen.placement.EndIslandPlacementDecorator
+ XXX.levelgen.placement.FeatureDecorator
- XXX.levelgen.placement.ForestRockPlacementDecorator
+ XXX.levelgen.placement.FrequencyChanceDecoratorConfiguration
- XXX.levelgen.placement.FrequencyDecoratorConfiguration
+ XXX.levelgen.placement.FrequencyWithExtraChanceDecoratorConfiguration
- XXX.levelgen.placement.IcebergPlacementDecorator
+ XXX.levelgen.placement.LakeLavaPlacementDecorator
- XXX.levelgen.placement.LakeWaterPlacementDecorator
+ XXX.levelgen.placement.MonsterRoomPlacementDecorator
- XXX.levelgen.placement.NoiseCountFactorDecoratorConfiguration
+ XXX.levelgen.placement.NoiseHeightmap32Decorator
- XXX.levelgen.placement.NoiseHeightmapDoubleDecorator
+ XXX.levelgen.placement.NopePlacementDecorator
- XXX.levelgen.placement.package-info
- XXX.levelgen.placement.RangeDecoratorConfiguration
+ XXX.levelgen.placement.SimpleFeatureDecorator
- XXX.levelgen.placement.TopSolidHeightMapDecorator
+ XXX.levelgen.placement.TopSolidHeightMapNoiseBasedDecorator
- XXX.levelgen.placement.TopSolidHeightMapRangeDecorator
+ XXX.levelgen.structure.BeardedStructureStart
- XXX.levelgen.structure.BoundingBox
+ XXX.levelgen.structure.BoundingBox$1
- XXX.levelgen.structure.BuriedTreasurePieces
+ XXX.levelgen.structure.BuriedTreasurePieces$BuriedTreasurePiece
- XXX.levelgen.structure.DesertPyramidPiece
+ XXX.levelgen.structure.EndCityPieces
- XXX.levelgen.structure.EndCityPieces$1
+ XXX.levelgen.structure.EndCityPieces$2
- XXX.levelgen.structure.EndCityPieces$3
+ XXX.levelgen.structure.EndCityPieces$4
- XXX.levelgen.structure.EndCityPieces$EndCityPiece
+ XXX.levelgen.structure.EndCityPieces$SectionGenerator
- XXX.levelgen.structure.IglooPieces
+ XXX.levelgen.structure.IglooPieces$IglooPiece
- XXX.levelgen.structure.JunglePyramidPiece
+ XXX.levelgen.structure.JunglePyramidPiece$1
- XXX.levelgen.structure.JunglePyramidPiece$MossStoneSelector
+ XXX.levelgen.structure.LegacyStructureDataHandler
- XXX.levelgen.structure.MineShaftPieces
+ XXX.levelgen.structure.MineShaftPieces$1
- XXX.levelgen.structure.MineShaftPieces$MineShaftCorridor
+ XXX.levelgen.structure.MineShaftPieces$MineShaftCrossing
- XXX.levelgen.structure.MineShaftPieces$MineShaftPiece
+ XXX.levelgen.structure.MineShaftPieces$MineShaftRoom
- XXX.levelgen.structure.MineShaftPieces$MineShaftStairs
+ XXX.levelgen.structure.NetherBridgePieces
- XXX.levelgen.structure.NetherBridgePieces$1
+ XXX.levelgen.structure.NetherBridgePieces$BridgeCrossing
- XXX.levelgen.structure.NetherBridgePieces$BridgeEndFiller
+ XXX.levelgen.structure.NetherBridgePieces$BridgeStraight
- XXX.levelgen.structure.NetherBridgePieces$CastleCorridorStairsPiece
+ XXX.levelgen.structure.NetherBridgePieces$CastleCorridorTBalconyPiece
- XXX.levelgen.structure.NetherBridgePieces$CastleEntrance
+ XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorCrossingPiece
- XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorLeftTurnPiece
+ XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorPiece
- XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorRightTurnPiece
+ XXX.levelgen.structure.NetherBridgePieces$CastleStalkRoom
- XXX.levelgen.structure.NetherBridgePieces$MonsterThrone
+ XXX.levelgen.structure.NetherBridgePieces$NetherBridgePiece
- XXX.levelgen.structure.NetherBridgePieces$PieceWeight
+ XXX.levelgen.structure.NetherBridgePieces$RoomCrossing
- XXX.levelgen.structure.NetherBridgePieces$StairsRoom
+ XXX.levelgen.structure.NetherBridgePieces$StartPiece
- XXX.levelgen.structure.NetherFossilFeature
+ XXX.levelgen.structure.NetherFossilFeature$FeatureStart
- XXX.levelgen.structure.NetherFossilPieces
+ XXX.levelgen.structure.NetherFossilPieces$NetherFossilPiece
- XXX.levelgen.structure.OceanMonumentPieces
+ XXX.levelgen.structure.OceanMonumentPieces$1
- XXX.levelgen.structure.OceanMonumentPieces$FitDoubleXRoom
+ XXX.levelgen.structure.OceanMonumentPieces$FitDoubleXYRoom
- XXX.levelgen.structure.OceanMonumentPieces$FitDoubleYRoom
+ XXX.levelgen.structure.OceanMonumentPieces$FitDoubleYZRoom
- XXX.levelgen.structure.OceanMonumentPieces$FitDoubleZRoom
+ XXX.levelgen.structure.OceanMonumentPieces$FitSimpleRoom
- XXX.levelgen.structure.OceanMonumentPieces$FitSimpleTopRoom
+ XXX.levelgen.structure.OceanMonumentPieces$MonumentBuilding
- XXX.levelgen.structure.OceanMonumentPieces$MonumentRoomFitter
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentCoreRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXYRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYZRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleZRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentEntryRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentPenthouse
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentPiece
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleTopRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentWingRoom
+ XXX.levelgen.structure.OceanMonumentPieces$RoomDefinition
- XXX.levelgen.structure.OceanRuinFeature
+ XXX.levelgen.structure.OceanRuinFeature$OceanRuinStart
- XXX.levelgen.structure.OceanRuinFeature$Type
+ XXX.levelgen.structure.OceanRuinPieces
- XXX.levelgen.structure.OceanRuinPieces$OceanRuinPiece
+ XXX.levelgen.structure.package-info
+ XXX.levelgen.structure.PillagerOutpostPieces
- XXX.levelgen.structure.PillagerOutpostPieces$PillagerOutpostPiece
+ XXX.levelgen.structure.PoolElementStructurePiece
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
- XXX.levelgen.structure.StructureFeatureIndexSavedData
+ XXX.levelgen.structure.StructureFeatureIO
+ XXX.levelgen.structure.StructurePiece
- XXX.levelgen.structure.StructurePiece$1
+ XXX.levelgen.structure.StructurePiece$BlockSelector
- XXX.levelgen.structure.StructureStart
+ XXX.levelgen.structure.StructureStart$1
- XXX.levelgen.structure.SwamplandHutPiece
+ XXX.levelgen.structure.TemplateStructurePiece
- XXX.levelgen.structure.WoodlandMansionPieces
+ XXX.levelgen.structure.WoodlandMansionPieces$1
- XXX.levelgen.structure.WoodlandMansionPieces$FirstFloorRoomCollection
+ XXX.levelgen.structure.WoodlandMansionPieces$FloorRoomCollection
- XXX.levelgen.structure.WoodlandMansionPieces$MansionGrid
+ XXX.levelgen.structure.WoodlandMansionPieces$MansionPiecePlacer
- XXX.levelgen.structure.WoodlandMansionPieces$PlacementData
+ XXX.levelgen.structure.WoodlandMansionPieces$SecondFloorRoomCollection
- XXX.levelgen.structure.WoodlandMansionPieces$SimpleGrid
+ XXX.levelgen.structure.WoodlandMansionPieces$ThirdFloorRoomCollection
- XXX.levelgen.structure.WoodlandMansionPieces$WoodlandMansionPiece
+ XXX.levelgen.surfacebuilders.BadlandsSurfaceBuilder
- XXX.levelgen.surfacebuilders.ConfiguredSurfaceBuilder
+ XXX.levelgen.surfacebuilders.DefaultSurfaceBuilder
- XXX.levelgen.surfacebuilders.ErodedBadlandsSurfaceBuilder
+ XXX.levelgen.surfacebuilders.FrozenOceanSurfaceBuilder
- XXX.levelgen.surfacebuilders.GiantTreeTaigaSurfaceBuilder
+ XXX.levelgen.surfacebuilders.GravellyMountainSurfaceBuilder
- XXX.levelgen.surfacebuilders.MountainSurfaceBuilder
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
+ XXX.loot.entries.CompositeEntryBase$Serializer
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
- XXX.loot.entries.LootPoolEntries$Serializer
+ XXX.loot.entries.LootPoolEntry
- XXX.loot.entries.LootPoolEntryContainer
+ XXX.loot.entries.LootPoolEntryContainer$Builder
- XXX.loot.entries.LootPoolEntryContainer$Serializer
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
+ XXX.loot.functions.LootingEnchantFunction
- XXX.loot.functions.LootingEnchantFunction$1
+ XXX.loot.functions.LootingEnchantFunction$Builder
- XXX.loot.functions.LootingEnchantFunction$Serializer
- XXX.loot.functions.LootItemConditionalFunction
+ XXX.loot.functions.LootItemConditionalFunction$Builder
- XXX.loot.functions.LootItemConditionalFunction$DummyBuilder
+ XXX.loot.functions.LootItemConditionalFunction$Serializer
- XXX.loot.functions.LootItemFunction
+ XXX.loot.functions.LootItemFunction$Builder
- XXX.loot.functions.LootItemFunction$Serializer
+ XXX.loot.functions.LootItemFunctions
- XXX.loot.functions.LootItemFunctions$Serializer
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
- XXX.loot.predicates.LocationCheck$Serializer
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition
- XXX.loot.predicates.LootItemBlockStatePropertyCondition$1
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition$Builder
- XXX.loot.predicates.LootItemBlockStatePropertyCondition$Serializer
+ XXX.loot.predicates.LootItemCondition
- XXX.loot.predicates.LootItemCondition$Builder
+ XXX.loot.predicates.LootItemCondition$Serializer
- XXX.loot.predicates.LootItemConditions
+ XXX.loot.predicates.LootItemConditions$Serializer
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
- XXX.minecraft.core.Position
+ XXX.minecraft.core.PositionImpl
- XXX.minecraft.core.Registry
+ XXX.minecraft.core.Rotations
- XXX.minecraft.core.SectionPos
+ XXX.minecraft.core.SectionPos$1
- XXX.minecraft.core.SerializableBoolean
- XXX.minecraft.data.package-info
- XXX.minecraft.locale.Language
+ XXX.minecraft.locale.package-info
- XXX.minecraft.nbt.ByteArrayTag
+ XXX.minecraft.nbt.ByteArrayTag$1
- XXX.minecraft.nbt.ByteTag
+ XXX.minecraft.nbt.ByteTag$1
- XXX.minecraft.nbt.ByteTag$Cache
+ XXX.minecraft.nbt.CollectionTag
- XXX.minecraft.nbt.CompoundTag
+ XXX.minecraft.nbt.CompoundTag$1
- XXX.minecraft.nbt.DoubleTag
+ XXX.minecraft.nbt.DoubleTag$1
- XXX.minecraft.nbt.EndTag
+ XXX.minecraft.nbt.EndTag$1
- XXX.minecraft.nbt.FloatTag
+ XXX.minecraft.nbt.FloatTag$1
- XXX.minecraft.nbt.IntArrayTag
+ XXX.minecraft.nbt.IntArrayTag$1
- XXX.minecraft.nbt.IntTag
+ XXX.minecraft.nbt.IntTag$1
- XXX.minecraft.nbt.IntTag$Cache
+ XXX.minecraft.nbt.ListTag
- XXX.minecraft.nbt.ListTag$1
+ XXX.minecraft.nbt.LongArrayTag
- XXX.minecraft.nbt.LongArrayTag$1
+ XXX.minecraft.nbt.LongTag
- XXX.minecraft.nbt.LongTag$1
+ XXX.minecraft.nbt.LongTag$Cache
- XXX.minecraft.nbt.NbtAccounter
+ XXX.minecraft.nbt.NbtAccounter$1
- XXX.minecraft.nbt.NbtIo
+ XXX.minecraft.nbt.NbtOps
- XXX.minecraft.nbt.NbtUtils
+ XXX.minecraft.nbt.NumericTag
- XXX.minecraft.nbt.package-info
- XXX.minecraft.nbt.ShortTag
+ XXX.minecraft.nbt.ShortTag$1
- XXX.minecraft.nbt.ShortTag$Cache
+ XXX.minecraft.nbt.StringTag
- XXX.minecraft.nbt.StringTag$1
+ XXX.minecraft.nbt.Tag
- XXX.minecraft.nbt.TagParser
+ XXX.minecraft.nbt.TagType
- XXX.minecraft.nbt.TagType$1
+ XXX.minecraft.nbt.TagTypes
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
- XXX.minecraft.network.package-info
+ XXX.minecraft.network.PacketDecoder
- XXX.minecraft.network.PacketEncoder
+ XXX.minecraft.network.PacketListener
- XXX.minecraft.network.SkipPacketException
+ XXX.minecraft.network.Varint21FrameDecoder
- XXX.minecraft.network.Varint21LengthFieldPrepender
- XXX.minecraft.obfuscate.DontObfuscateOrShrink
+ XXX.minecraft.obfuscate.KeepAfterObfuscation
- XXX.minecraft.obfuscate.package-info
+ XXX.minecraft.recipebook.package-info
- XXX.minecraft.recipebook.PlaceRecipe
+ XXX.minecraft.recipebook.ServerPlaceRecipe
- XXX.minecraft.recipebook.ServerPlaceSmeltingRecipe
- XXX.minecraft.resources.package-info
- XXX.minecraft.resources.ResourceLocation
+ XXX.minecraft.resources.ResourceLocation$Serializer
+ XXX.minecraft.server.Bootstrap
- XXX.minecraft.server.ChainedJsonException
+ XXX.minecraft.server.ChainedJsonException$1
- XXX.minecraft.server.ChainedJsonException$Entry
+ XXX.minecraft.server.ConsoleInput
- XXX.minecraft.server.ConsoleInputSource
+ XXX.minecraft.server.DebugLoggedPrintStream
- XXX.minecraft.server.Eula
+ XXX.minecraft.server.LoggedPrintStream
- XXX.minecraft.server.MinecraftServer
+ XXX.minecraft.server.MinecraftServer$1
- XXX.minecraft.server.MinecraftServer$2
+ XXX.minecraft.server.MinecraftServer$3
- XXX.minecraft.server.PlayerAdvancements
+ XXX.minecraft.server.PlayerAdvancements$1
- XXX.minecraft.server.RunningOnDifferentThreadException
+ XXX.minecraft.server.ServerAdvancementManager
- XXX.minecraft.server.ServerFunctionManager
+ XXX.minecraft.server.ServerFunctionManager$QueuedCommand
- XXX.minecraft.server.ServerInterface
+ XXX.minecraft.server.ServerScoreboard
- XXX.minecraft.server.ServerScoreboard$Method
+ XXX.minecraft.server.TickTask
- XXX.minecraft.util.package-info
+ XXX.minecraft.world.BossEvent
- XXX.minecraft.world.BossEvent$BossBarColor
+ XXX.minecraft.world.BossEvent$BossBarOverlay
- XXX.minecraft.world.Clearable
+ XXX.minecraft.world.CompoundContainer
- XXX.minecraft.world.Container
+ XXX.minecraft.world.ContainerHelper
- XXX.minecraft.world.ContainerListener
+ XXX.minecraft.world.Containers
- XXX.minecraft.world.Difficulty
+ XXX.minecraft.world.DifficultyInstance
- XXX.minecraft.world.InteractionHand
+ XXX.minecraft.world.InteractionResult
- XXX.minecraft.world.InteractionResultHolder
+ XXX.minecraft.world.LockCode
- XXX.minecraft.world.MenuProvider
+ XXX.minecraft.world.Nameable
+ XXX.minecraft.world.package-info
- XXX.minecraft.world.ShulkerSharedHelper
+ XXX.minecraft.world.SimpleContainer
- XXX.minecraft.world.SimpleMenuProvider
+ XXX.minecraft.world.Snooper
- XXX.minecraft.world.Snooper$1
+ XXX.minecraft.world.SnooperPopulator
- XXX.minecraft.world.WorldlyContainer
+ XXX.minecraft.world.WorldlyContainerHolder
- XXX.models.blockstates.Condition
- XXX.models.blockstates.Condition$CompositeCondition
- XXX.models.blockstates.Condition$TerminalCondition
- XXX.models.blockstates.MultiPartGenerator$1
- XXX.models.blockstates.MultiPartGenerator$Entry
- XXX.models.blockstates.PropertyDispatch
- XXX.models.blockstates.PropertyDispatch$C1
- XXX.models.blockstates.PropertyDispatch$C3
- XXX.models.blockstates.PropertyDispatch$C5
- XXX.models.blockstates.PropertyDispatch$QuadFunction
- XXX.models.blockstates.PropertyValue
- XXX.models.blockstates.Variant
- XXX.models.blockstates.VariantProperties$Rotation
- XXX.models.blockstates.VariantProperty$Value
- XXX.models.model.DelegatedModel
- XXX.models.model.ModelTemplate
- XXX.models.model.package-info
- XXX.models.model.TexturedModel
- XXX.models.model.TextureMapping
+ XXX.monster.hoglin.Hoglin
- XXX.monster.hoglin.HoglinAi
+ XXX.monster.hoglin.package-info
+ XXX.monster.piglin.Piglin
- XXX.monster.piglin.Piglin$PiglinArmPose
+ XXX.monster.piglin.PiglinAi
- XXX.monster.piglin.RememberIfHoglinWasKilled
- XXX.monster.piglin.StartHuntingHoglin
- XXX.monster.piglin.StopHoldingItemIfNoLongerAdmiring
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
+ XXX.network.chat.package-info
+ XXX.network.chat.ScoreComponent
- XXX.network.chat.SelectorComponent
+ XXX.network.chat.Style
- XXX.network.chat.Style$1
+ XXX.network.chat.Style$Serializer
- XXX.network.chat.TextComponent
+ XXX.network.chat.TranslatableComponent
- XXX.network.chat.TranslatableFormatException
+ XXX.network.protocol.package-info
+ XXX.network.protocol.Packet
- XXX.network.protocol.PacketFlow
+ XXX.network.protocol.PacketUtils
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
+ XXX.placement.nether.ChanceRangeDecorator
- XXX.placement.nether.CountRangeDecorator
+ XXX.placement.nether.FireDecorator
- XXX.placement.nether.LightGemChanceDecorator
+ XXX.placement.nether.MagmaDecorator
+ XXX.placement.nether.package-info
- XXX.placement.nether.RandomCountRangeDecorator
+ XXX.protocol.game.ClientboundAddEntityPacket
- XXX.protocol.game.ClientboundAddExperienceOrbPacket
+ XXX.protocol.game.ClientboundAddGlobalEntityPacket
- XXX.protocol.game.ClientboundAddMobPacket
+ XXX.protocol.game.ClientboundAddPaintingPacket
- XXX.protocol.game.ClientboundAddPlayerPacket
+ XXX.protocol.game.ClientboundAnimatePacket
- XXX.protocol.game.ClientboundAwardStatsPacket
+ XXX.protocol.game.ClientboundBlockBreakAckPacket
- XXX.protocol.game.ClientboundBlockDestructionPacket
+ XXX.protocol.game.ClientboundBlockEntityDataPacket
- XXX.protocol.game.ClientboundBlockEventPacket
+ XXX.protocol.game.ClientboundBlockUpdatePacket
- XXX.protocol.game.ClientboundBossEventPacket
+ XXX.protocol.game.ClientboundBossEventPacket$1
- XXX.protocol.game.ClientboundBossEventPacket$Operation
+ XXX.protocol.game.ClientboundChangeDifficultyPacket
- XXX.protocol.game.ClientboundChatPacket
+ XXX.protocol.game.ClientboundChunkBlocksUpdatePacket
- XXX.protocol.game.ClientboundChunkBlocksUpdatePacket$BlockUpdate
- XXX.protocol.game.ClientboundCommandsPacket
+ XXX.protocol.game.ClientboundCommandsPacket$1
- XXX.protocol.game.ClientboundCommandsPacket$Entry
+ XXX.protocol.game.ClientboundCommandSuggestionsPacket
+ XXX.protocol.game.ClientboundContainerAckPacket
- XXX.protocol.game.ClientboundContainerClosePacket
+ XXX.protocol.game.ClientboundContainerSetContentPacket
- XXX.protocol.game.ClientboundContainerSetDataPacket
+ XXX.protocol.game.ClientboundContainerSetSlotPacket
- XXX.protocol.game.ClientboundCooldownPacket
+ XXX.protocol.game.ClientboundCustomPayloadPacket
- XXX.protocol.game.ClientboundCustomSoundPacket
+ XXX.protocol.game.ClientboundDisconnectPacket
- XXX.protocol.game.ClientboundEntityEventPacket
+ XXX.protocol.game.ClientboundExplodePacket
- XXX.protocol.game.ClientboundForgetLevelChunkPacket
+ XXX.protocol.game.ClientboundGameEventPacket
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
+ XXX.protocol.game.ClientboundSetSpawnPositionPacket
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
- XXX.protocol.game.ClientGamePacketListener
- XXX.protocol.game.DebugEntityNameGenerator
+ XXX.protocol.game.DebugPackets
- XXX.protocol.game.package-info
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
- XXX.protocol.game.ServerGamePacketListener
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
- XXX.server.bossevents.CustomBossEvent
+ XXX.server.bossevents.CustomBossEvents
- XXX.server.bossevents.package-info
+ XXX.server.commands.AdvancementCommands
- XXX.server.commands.AdvancementCommands$1
+ XXX.server.commands.AdvancementCommands$Action
- XXX.server.commands.AdvancementCommands$Action$1
+ XXX.server.commands.AdvancementCommands$Action$2
- XXX.server.commands.AdvancementCommands$Mode
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
+ XXX.server.commands.DeOpCommands
+ XXX.state.pattern.BlockInWorld
- XXX.state.pattern.BlockPattern
+ XXX.state.pattern.BlockPattern$BlockCacheLoader
- XXX.state.pattern.BlockPattern$BlockPatternMatch
+ XXX.state.pattern.BlockPattern$PortalInfo
- XXX.state.pattern.BlockPatternBuilder
+ XXX.state.pattern.package-info
- XXX.state.predicate.BlockMaterialPredicate
+ XXX.state.predicate.BlockMaterialPredicate$1
- XXX.state.predicate.BlockPredicate
+ XXX.state.predicate.BlockStatePredicate
- XXX.state.predicate.package-info
+ XXX.state.properties.AbstractProperty
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
+ XXX.state.properties.EnumProperty
- XXX.state.properties.Half
+ XXX.state.properties.IntegerProperty
- XXX.state.properties.NoteBlockInstrument
- XXX.state.properties.package-info
+ XXX.state.properties.PistonType
- XXX.state.properties.Property
+ XXX.state.properties.RailShape
- XXX.state.properties.RedstoneSide
+ XXX.state.properties.SlabType
- XXX.state.properties.StairsShape
+ XXX.state.properties.StructureMode
- XXX.state.properties.WallSide
+ XXX.state.properties.WoodType
+ XXX.storage.loot.BinomialDistributionGenerator
- XXX.storage.loot.BinomialDistributionGenerator$Serializer
+ XXX.storage.loot.BuiltInLootTables
- XXX.storage.loot.ConstantIntValue
+ XXX.storage.loot.ConstantIntValue$Serializer
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
- XXX.storage.loot.RandomIntGenerator
+ XXX.storage.loot.RandomIntGenerators
- XXX.storage.loot.RandomValueBounds
+ XXX.storage.loot.RandomValueBounds$Serializer
- XXX.storage.loot.ValidationContext
+ XXX.storage.threaded.package-info
- XXX.structure.templatesystem.AlwaysTrueTest
+ XXX.structure.templatesystem.BlockIgnoreProcessor
- XXX.structure.templatesystem.BlockMatchTest
+ XXX.structure.templatesystem.BlockRotProcessor
- XXX.structure.templatesystem.BlockStateMatchTest
+ XXX.structure.templatesystem.GravityProcessor
- XXX.structure.templatesystem.JigsawReplacementProcessor
+ XXX.structure.templatesystem.NopProcessor
- XXX.structure.templatesystem.package-info
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
- XXX.structure.templatesystem.StructureTemplate$SimplePalette
+ XXX.structure.templatesystem.StructureTemplate$StructureBlockInfo
- XXX.structure.templatesystem.StructureTemplate$StructureEntityInfo
+ XXX.structure.templatesystem.TagMatchTest
- XXX.util.datafix.package-info
+ XXX.util.profiling.ActiveProfiler
- XXX.util.profiling.ActiveProfiler$1
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
- XXX.util.worldupdate.package-info
+ XXX.util.worldupdate.WorldUpgrader
- XXX.village.poi.package-info
- XXX.village.poi.PoiManager
+ XXX.village.poi.PoiManager$DistanceTracker
- XXX.village.poi.PoiManager$Occupancy
+ XXX.village.poi.PoiRecord
- XXX.village.poi.PoiSection
+ XXX.village.poi.PoiType
- XXX.world.damagesource.CombatEntry
+ XXX.world.damagesource.CombatRules
- XXX.world.damagesource.CombatTracker
+ XXX.world.damagesource.DamageSource
- XXX.world.damagesource.EntityDamageSource
+ XXX.world.damagesource.IndirectEntityDamageSource
- XXX.world.damagesource.NetherBedDamage
+ XXX.world.damagesource.package-info
- XXX.world.effect.AbsoptionMobEffect
+ XXX.world.effect.AttackDamageMobEffect
- XXX.world.effect.HealthBoostMobEffect
+ XXX.world.effect.InstantenousMobEffect
- XXX.world.effect.MobEffect
+ XXX.world.effect.MobEffectCategory
- XXX.world.effect.MobEffectInstance
- XXX.world.effect.MobEffects
+ XXX.world.effect.MobEffects$1
+ XXX.world.effect.MobEffectUtil
- XXX.world.effect.package-info
+ XXX.world.entity.AgableMob
- XXX.world.entity.AgableMob$AgableMobGroupData
+ XXX.world.entity.AreaEffectCloud
- XXX.world.entity.Entity
+ XXX.world.entity.Entity$1
- XXX.world.entity.Entity$MoveCallback
+ XXX.world.entity.EntityDimensions
- XXX.world.entity.EntityEvent
+ XXX.world.entity.EntitySelector
- XXX.world.entity.EntitySelector$MobCanWearArmourEntitySelector
+ XXX.world.entity.EntityType
- XXX.world.entity.EntityType$Builder
+ XXX.world.entity.EntityType$EntityFactory
- XXX.world.entity.EquipmentSlot
+ XXX.world.entity.EquipmentSlot$Type
- XXX.world.entity.ExperienceOrb
+ XXX.world.entity.FlyingMob
- XXX.world.entity.HumanoidArm
+ XXX.world.entity.LivingEntity
- XXX.world.entity.LivingEntity$1
+ XXX.world.entity.Mob
- XXX.world.entity.Mob$1
+ XXX.world.entity.MobCategory
- XXX.world.entity.MobSpawnType
+ XXX.world.entity.MobType
- XXX.world.entity.MoverType
+ XXX.world.entity.OwnableEntity
- XXX.world.entity.PathfinderMob
+ XXX.world.entity.PlayerRideable
- XXX.world.entity.PlayerRideableJumping
+ XXX.world.entity.Pose
- XXX.world.entity.PowerableMob
+ XXX.world.entity.ReputationEventHandler
- XXX.world.entity.SpawnGroupData
+ XXX.world.entity.SpawnPlacements
- XXX.world.entity.SpawnPlacements$Data
+ XXX.world.entity.SpawnPlacements$SpawnPredicate
- XXX.world.entity.SpawnPlacements$Type
+ XXX.world.entity.TamableAnimal
+ XXX.world.inventory.AnvilMenu$2
- XXX.world.inventory.ItemCombinerMenu$1
- XXX.world.inventory.LecternMenu
+ XXX.world.inventory.LecternMenu$1
- XXX.world.inventory.LoomMenu
+ XXX.world.inventory.LoomMenu$1
- XXX.world.inventory.LoomMenu$2
+ XXX.world.inventory.LoomMenu$3
- XXX.world.inventory.LoomMenu$4
+ XXX.world.inventory.LoomMenu$5
- XXX.world.inventory.LoomMenu$6
+ XXX.world.inventory.MenuConstructor
- XXX.world.inventory.MenuType
+ XXX.world.inventory.MenuType$MenuSupplier
- XXX.world.inventory.MerchantContainer
+ XXX.world.inventory.MerchantMenu
- XXX.world.inventory.MerchantResultSlot
+ XXX.world.inventory.PlayerEnderChestContainer
- XXX.world.inventory.RecipeBookMenu
+ XXX.world.inventory.RecipeHolder
- XXX.world.inventory.ResultContainer
+ XXX.world.inventory.ResultSlot
- XXX.world.inventory.ShulkerBoxMenu
+ XXX.world.inventory.ShulkerBoxSlot
- XXX.world.inventory.SimpleContainerData
+ XXX.world.inventory.Slot
- XXX.world.inventory.SmithingMenu
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
XXX.advancements.critereon.TargetBlockTrigger +2M -2M
```
```
XXX.minecraft.core.BlockPos +1M -1M
```
```
XXX.minecraft.core.BlockPos$MutableBlockPos +3M -6M | -3P
```
```
XXX.minecraft.core.Vec3i +3M
```
```
XXX.server.level.ServerChunkCache +1M -1M
```
```
XXX.server.players.StoredUserList +1M
```
```
XXX.minecraft.stats.Stats +1P
```
```
XXX.ai.behavior.MeleeAttack +1M -6M | +1P -2P
```
```
XXX.entity.projectile.AbstractArrow +1M -3M | -1P
```
```
XXX.entity.projectile.AbstractHurtingProjectile -1M | -2P
```
```
XXX.entity.projectile.FireworkRocketEntity +4M -4M
```
```
XXX.entity.projectile.LargeFireball +1M
```
```
XXX.entity.projectile.Projectile +11M | +1P -2P
```
```
XXX.entity.projectile.Snowball +1M
```
```
XXX.entity.projectile.ThrownEgg +1M
```
```
XXX.world.inventory.AnvilMenu +4M -9M | -4P
```
```
XXX.world.item.HoeItem +2M -8M | +1P -1P
```
```
XXX.world.level.EntityGetter -1M
```
```
XXX.world.level.Level -1M
```
```
XXX.world.level.NaturalSpawner +7M -1M
```
```
XXX.level.biome.BiomeManager +2M -1M
```
```
XXX.level.block.Block +1M -1M
```
```
XXX.level.block.ChorusFlowerBlock +1M -1M
```
```
XXX.level.block.FireBlock +2M
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.TargetBlockTrigger
</summary>

```diff
+ boolean lambda$trigger$0(int,TargetBlockTrigger$TriggerInstance)
- boolean lambda$trigger$0(ServerPlayer,Entity,Vec3,int,TargetBlockTrigger$TriggerInstance)
- void trigger(ServerPlayer,Entity,Vec3,int)
+ void trigger(ServerPlayer,int)
```

</details>
<details>
<summary>
net.minecraft.core.BlockPos
</summary>

```diff
- BlockPos$MutableBlockPos mutable()
+ void <init>(Entity)
```

</details>
<details>
<summary>
net.minecraft.core.BlockPos$MutableBlockPos
</summary>

```diff
+ BlockPos$MutableBlockPos set(Entity)
- BlockPos$MutableBlockPos setWithOffset(Vec3i,Direction)
- BlockPos$MutableBlockPos setWithOffset(Vec3i,int,int,int)
- BlockPos$MutableBlockPos setWithOffset(Vec3i,Vec3i)
+ int getX()
+ int getY()
+ int getZ()
+ void <init>(BlockPos)
+ void <init>(Entity)
```

</details>
<details>
<summary>
net.minecraft.core.Vec3i
</summary>

```diff
- void setX(int)
- void setY(int)
- void setZ(int)
```

</details>
<details>
<summary>
net.minecraft.server.level.ServerChunkCache
</summary>

```diff
+ void lambda$tickChunks$5(long,boolean,MobCategory[],boolean,int,Object2IntMap,BlockPos,int,ChunkHolder)
- void lambda$tickChunks$5(long,boolean,MobCategory[],boolean,int,Object2IntMap,int,ChunkHolder)
```

</details>
<details>
<summary>
net.minecraft.server.players.StoredUserList
</summary>

```diff
- JsonObject lambda$save$0(StoredUserEntry)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.behavior.MeleeAttack
</summary>

```diff
+ boolean canStillUse(ServerLevel,LivingEntity,long)
+ boolean canStillUse(ServerLevel,Mob,long)
+ boolean isHoldingProjectileWeapon(Mob)
- boolean lambda$checkExtraStartConditions$0(Item)
+ boolean lambda$isHoldingProjectileWeapon$0(Item)
+ LivingEntity getAttackTarget(LivingEntity)
+ void meleeAttack(Mob,LivingEntity)
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.AbstractArrow
</summary>

```diff
+ Entity getOwner()
+ void onHit(HitResult)
- void onHitBlock(BlockHitResult)
+ void shootFromRotation(Entity,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.AbstractHurtingProjectile
</summary>

```diff
+ void onHit(HitResult)
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.FireworkRocketEntity
</summary>

```diff
- void <init>(Level,Entity,double,double,double,ItemStack)
- void <init>(Level,ItemStack,Entity,double,double,double,boolean)
+ void lerpMotion(double,double,double)
- void onHitBlock(BlockHitResult)
- void onHitEntity(EntityHitResult)
+ void performHitChecks(HitResult)
+ void shoot(double,double,double,float,float)
+ void shootFromRotation(Entity,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.LargeFireball
</summary>

```diff
- void onHitEntity(EntityHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.Projectile
</summary>

```diff
- Entity getOwner()
- void <init>(EntityType,Level)
- void addAdditionalSaveData(CompoundTag)
- void lerpMotion(double,double,double)
- void onHit(HitResult)
- void onHitBlock(BlockHitResult)
- void onHitEntity(EntityHitResult)
- void readAdditionalSaveData(CompoundTag)
- void setOwner(Entity)
- void shoot(double,double,double,float,float)
- void shootFromRotation(Entity,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.Snowball
</summary>

```diff
- void onHitEntity(EntityHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.ThrownEgg
</summary>

```diff
- void onHitEntity(EntityHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.inventory.AnvilMenu
</summary>

```diff
- boolean isValidBlock(BlockState)
+ Boolean lambda$stillValid$1(Player,Level,BlockPos)
- boolean mayPickup(Player,boolean)
+ boolean stillValid(Player)
+ Container access$100(AnvilMenu)
+ DataSlot access$000(AnvilMenu)
+ int access$200(AnvilMenu)
- ItemStack onTake(Player,ItemStack)
+ ItemStack quickMoveStack(Player,int)
- void lambda$onTake$0(Player,Level,BlockPos)
+ void lambda$removed$0(Player,Level,BlockPos)
+ void removed(Player)
+ void slotsChanged(Container)
```

</details>
<details>
<summary>
net.minecraft.world.item.HoeItem
</summary>

```diff
+ boolean hurtEnemy(ItemStack,LivingEntity,LivingEntity)
+ boolean mineBlock(ItemStack,Level,BlockState,BlockPos,LivingEntity)
+ float getDestroySpeed(ItemStack,BlockState)
+ Multimap getDefaultAttributeModifiers(EquipmentSlot)
+ void <init>(Tier,float,Item$Properties)
- void <init>(Tier,int,float,Item$Properties)
+ void lambda$hurtEnemy$2(LivingEntity)
+ void lambda$mineBlock$0(LivingEntity)
- void lambda$useOn$0(UseOnContext,Player)
+ void lambda$useOn$1(UseOnContext,Player)
```

</details>
<details>
<summary>
net.minecraft.world.level.EntityGetter
</summary>

```diff
+ Player getNearestPlayerIgnoreY(double,double,double)
```

</details>
<details>
<summary>
net.minecraft.world.level.Level
</summary>

```diff
+ boolean extinguishFire(Player,BlockPos,Direction)
```

</details>
<details>
<summary>
net.minecraft.world.level.NaturalSpawner
</summary>

```diff
- boolean isRightDistanceToPlayerAndSpawnPoint(ServerLevel,ChunkAccess,BlockPos$MutableBlockPos,double)
- boolean isValidPositionForMob(ServerLevel,Mob,double)
- boolean isValidSpawnPostitionForType(ServerLevel,ChunkGenerator,Biome$SpawnerData,BlockPos$MutableBlockPos,double)
- Mob getMobForSpawn(ServerLevel,EntityType)
+ void spawnCategoryForChunk(MobCategory,ServerLevel,LevelChunk,BlockPos)
- void spawnCategoryForChunk(MobCategory,ServerLevel,LevelChunk)
- void spawnCategoryForPosition(MobCategory,ServerLevel,BlockPos)
- void spawnCategoryForPosition(MobCategory,ServerLevel,ChunkAccess,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.BiomeManager
</summary>

```diff
+ Biome getNoiseBiome(int,int,int)
- Biome getNoiseBiomeAtPosition(double,double,double)
- Biome getNoiseBiomeAtQuart(int,int,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.Block
</summary>

```diff
+ void onProjectileHit(Level,BlockState,BlockHitResult,Entity)
- void onProjectileHit(Level,BlockState,BlockHitResult,Projectile)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.ChorusFlowerBlock
</summary>

```diff
+ void onProjectileHit(Level,BlockState,BlockHitResult,Entity)
- void onProjectileHit(Level,BlockState,BlockHitResult,Projectile)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.FireBlock
</summary>

```diff
- BlockState getStateForPlacement(BlockPlaceContext)
- VoxelShape getShape(BlockState,BlockGetter,BlockPos,CollisionContext)
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
+ net.minecraft.ReportedException
- net.minecraft.ResourceLocationException
+ net.minecraft.SharedConstants
- net.minecraft.Util
+ net.minecraft.Util$1
- net.minecraft.Util$IdentityStrategy
+ net.minecraft.Util$OS
- net.minecraft.Util$OS$1
+ net.minecraft.Util$OS$2
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
+ XXX.advancements.critereon.DistancePredicate
- XXX.advancements.critereon.EffectsChangedTrigger
+ XXX.advancements.critereon.EffectsChangedTrigger$TriggerInstance
- XXX.advancements.critereon.EnchantedItemTrigger
+ XXX.advancements.critereon.EnchantedItemTrigger$TriggerInstance
- XXX.advancements.critereon.EnchantmentPredicate
+ XXX.advancements.critereon.EnterBlockTrigger
- XXX.advancements.critereon.EnterBlockTrigger$TriggerInstance
+ XXX.advancements.critereon.EntityEquipmentPredicate
- XXX.advancements.critereon.EntityEquipmentPredicate$Builder
+ XXX.advancements.critereon.EntityFlagsPredicate
- XXX.advancements.critereon.EntityFlagsPredicate$Builder
+ XXX.advancements.critereon.EntityHurtPlayerTrigger
- XXX.advancements.critereon.EntityHurtPlayerTrigger$TriggerInstance
+ XXX.advancements.critereon.EntityPredicate
- XXX.advancements.critereon.EntityPredicate$1
+ XXX.advancements.critereon.EntityPredicate$Builder
- XXX.advancements.critereon.EntityTypePredicate
+ XXX.advancements.critereon.EntityTypePredicate$1
- XXX.advancements.critereon.EntityTypePredicate$TagPredicate
+ XXX.advancements.critereon.EntityTypePredicate$TypePredicate
- XXX.advancements.critereon.FilledBucketTrigger
+ XXX.advancements.critereon.FilledBucketTrigger$TriggerInstance
- XXX.advancements.critereon.FishingRodHookedTrigger
+ XXX.advancements.critereon.FishingRodHookedTrigger$TriggerInstance
- XXX.advancements.critereon.FluidPredicate
+ XXX.advancements.critereon.FluidPredicate$Builder
- XXX.advancements.critereon.ImpossibleTrigger
+ XXX.advancements.critereon.ImpossibleTrigger$TriggerInstance
- XXX.advancements.critereon.InventoryChangeTrigger
+ XXX.advancements.critereon.InventoryChangeTrigger$TriggerInstance
- XXX.advancements.critereon.ItemDurabilityTrigger
+ XXX.advancements.critereon.ItemDurabilityTrigger$TriggerInstance
- XXX.advancements.critereon.ItemPredicate
+ XXX.advancements.critereon.ItemPredicate$Builder
- XXX.advancements.critereon.ItemUsedOnBlockTrigger
+ XXX.advancements.critereon.ItemUsedOnBlockTrigger$TriggerInstance
- XXX.advancements.critereon.KilledByCrossbowTrigger
+ XXX.advancements.critereon.KilledByCrossbowTrigger$TriggerInstance
- XXX.advancements.critereon.KilledTrigger
+ XXX.advancements.critereon.KilledTrigger$TriggerInstance
- XXX.advancements.critereon.LevitationTrigger
+ XXX.advancements.critereon.LevitationTrigger$TriggerInstance
- XXX.advancements.critereon.LightPredicate
+ XXX.advancements.critereon.LightPredicate$1
- XXX.advancements.critereon.LightPredicate$Builder
+ XXX.advancements.critereon.LocationPredicate
- XXX.advancements.critereon.LocationPredicate$Builder
+ XXX.advancements.critereon.LocationTrigger
- XXX.advancements.critereon.LocationTrigger$TriggerInstance
+ XXX.advancements.critereon.MinMaxBounds
- XXX.advancements.critereon.MinMaxBounds$BoundsFactory
+ XXX.advancements.critereon.MinMaxBounds$BoundsFromReaderFactory
- XXX.advancements.critereon.MinMaxBounds$Floats
+ XXX.advancements.critereon.MinMaxBounds$Ints
- XXX.advancements.critereon.MobEffectsPredicate
+ XXX.advancements.critereon.MobEffectsPredicate$MobEffectInstancePredicate
- XXX.advancements.critereon.NbtPredicate
+ XXX.advancements.critereon.NetherTravelTrigger
- XXX.advancements.critereon.NetherTravelTrigger$TriggerInstance
+ XXX.advancements.critereon.package-info
+ XXX.advancements.critereon.PlacedBlockTrigger
- XXX.advancements.critereon.PlacedBlockTrigger$TriggerInstance
+ XXX.advancements.critereon.PlayerHurtEntityTrigger
- XXX.advancements.critereon.PlayerHurtEntityTrigger$TriggerInstance
+ XXX.advancements.critereon.PlayerPredicate
- XXX.advancements.critereon.PlayerPredicate$1
+ XXX.advancements.critereon.PlayerPredicate$AdvancementCriterionsPredicate
- XXX.advancements.critereon.PlayerPredicate$AdvancementDonePredicate
+ XXX.advancements.critereon.PlayerPredicate$AdvancementPredicate
- XXX.advancements.critereon.PlayerPredicate$Builder
+ XXX.advancements.critereon.RecipeUnlockedTrigger
- XXX.advancements.critereon.RecipeUnlockedTrigger$TriggerInstance
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
+ XXX.ai.attributes.Attribute
- XXX.ai.attributes.AttributeInstance
+ XXX.ai.attributes.AttributeModifier
- XXX.ai.attributes.AttributeModifier$Operation
+ XXX.ai.attributes.BaseAttribute
- XXX.ai.attributes.BaseAttributeMap
+ XXX.ai.attributes.ModifiableAttributeInstance
- XXX.ai.attributes.ModifiableAttributeMap
- XXX.ai.attributes.package-info
+ XXX.ai.attributes.RangedAttribute
+ XXX.ai.behavior.AcquirePoi
- XXX.ai.behavior.package-info
+ XXX.ai.behavior.RememberIfHoglinWasKilled
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
+ XXX.ai.behavior.StartHuntingHoglin
+ XXX.ai.behavior.StopHoldingItemIfNoLongerAdmiring
- XXX.ai.behavior.StrollAroundPoi
+ XXX.ai.behavior.StrollToPoi
- XXX.ai.behavior.StrollToPoiList
+ XXX.ai.behavior.Swim
- XXX.ai.behavior.TradeWithVillager
+ XXX.ai.behavior.UpdateActivityFromSchedule
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
- XXX.ai.goal.FollowOwnerGoal
+ XXX.ai.goal.FollowParentGoal
- XXX.ai.goal.Goal
+ XXX.ai.goal.Goal$Flag
- XXX.ai.goal.GoalSelector
+ XXX.ai.goal.GoalSelector$1
- XXX.ai.goal.GoalSelector$2
+ XXX.ai.goal.InteractGoal
- XXX.ai.goal.JumpGoal
+ XXX.ai.goal.LandOnOwnersShoulderGoal
- XXX.ai.goal.LeapAtTargetGoal
+ XXX.ai.goal.LlamaFollowCaravanGoal
- XXX.ai.goal.LookAtPlayerGoal
+ XXX.ai.goal.LookAtTradingPlayerGoal
- XXX.ai.goal.MeleeAttackGoal
+ XXX.ai.goal.MoveBackToVillage
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
- XXX.ai.sensing.DummySensor
+ XXX.ai.sensing.GolemSensor
- XXX.ai.sensing.HoglinSpecificSensor
+ XXX.ai.sensing.HurtBySensor
- XXX.ai.sensing.InteractableDoorsSensor
+ XXX.ai.sensing.NearestBedSensor
- XXX.ai.sensing.NearestItemSensor
+ XXX.ai.sensing.NearestLivingEntitySensor
- XXX.ai.sensing.package-info
- XXX.ai.sensing.PiglinSpecificSensor
+ XXX.ai.sensing.PlayerSensor
- XXX.ai.sensing.SecondaryPoiSensor
+ XXX.ai.sensing.Sensing
- XXX.ai.sensing.Sensor
+ XXX.ai.sensing.SensorType
- XXX.ai.sensing.VillagerBabiesSensor
+ XXX.ai.sensing.VillagerHostilesSensor
- XXX.ai.targeting.package-info
+ XXX.ai.targeting.TargetingConditions
- XXX.ai.util.package-info
+ XXX.ai.util.RandomPos
+ XXX.ai.village.package-info
+ XXX.ai.village.ReputationEventType
- XXX.ai.village.ReputationEventType$1
+ XXX.ai.village.VillageSiege
- XXX.ai.village.VillageSiege$State
- XXX.animal.horse.AbstractChestedHorse
+ XXX.animal.horse.AbstractHorse
- XXX.animal.horse.Donkey
+ XXX.animal.horse.Horse
- XXX.animal.horse.Horse$HorseGroupData
+ XXX.animal.horse.Llama
- XXX.animal.horse.Llama$1
+ XXX.animal.horse.Llama$LlamaAttackWolfGoal
- XXX.animal.horse.Llama$LlamaGroupData
+ XXX.animal.horse.Llama$LlamaHurtByTargetGoal
- XXX.animal.horse.Mule
- XXX.animal.horse.package-info
+ XXX.animal.horse.SkeletonHorse
- XXX.animal.horse.SkeletonTrapGoal
+ XXX.animal.horse.TraderLlama
- XXX.animal.horse.TraderLlama$TraderLlamaDefendWanderingTraderGoal
+ XXX.animal.horse.ZombieHorse
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
- XXX.arguments.selector.EntitySelectorParser
- XXX.arguments.selector.package-info
- XXX.block.entity.AbstractFurnaceBlockEntity
+ XXX.block.entity.AbstractFurnaceBlockEntity$1
- XXX.block.entity.BannerBlockEntity
+ XXX.block.entity.BannerPattern
- XXX.block.entity.BannerPattern$Builder
+ XXX.block.entity.BarrelBlockEntity
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
- XXX.block.entity.BlastFurnaceBlockEntity
+ XXX.block.entity.BlockEntity
- XXX.block.entity.BlockEntityType
+ XXX.block.entity.BlockEntityType$Builder
- XXX.block.entity.BrewingStandBlockEntity
+ XXX.block.entity.BrewingStandBlockEntity$1
- XXX.block.entity.CampfireBlockEntity
+ XXX.block.entity.ChestBlockEntity
- XXX.block.entity.CommandBlockEntity
+ XXX.block.entity.CommandBlockEntity$1
- XXX.block.entity.CommandBlockEntity$Mode
+ XXX.block.entity.ComparatorBlockEntity
- XXX.block.entity.ConduitBlockEntity
+ XXX.block.entity.DaylightDetectorBlockEntity
- XXX.block.entity.DispenserBlockEntity
+ XXX.block.entity.DropperBlockEntity
- XXX.block.entity.EnchantmentTableBlockEntity
+ XXX.block.entity.EnderChestBlockEntity
- XXX.block.entity.FurnaceBlockEntity
+ XXX.block.entity.Hopper
- XXX.block.entity.HopperBlockEntity
+ XXX.block.entity.JigsawBlockEntity
- XXX.block.entity.JukeboxBlockEntity
+ XXX.block.entity.LecternBlockEntity
- XXX.block.entity.LecternBlockEntity$1
+ XXX.block.entity.LecternBlockEntity$2
- XXX.block.entity.LidBlockEntity
+ XXX.block.entity.package-info
+ XXX.block.entity.RandomizableContainerBlockEntity
- XXX.block.entity.ShulkerBoxBlockEntity
+ XXX.block.entity.ShulkerBoxBlockEntity$1
- XXX.block.entity.ShulkerBoxBlockEntity$AnimationStatus
+ XXX.block.entity.SignBlockEntity
- XXX.block.entity.SkullBlockEntity
+ XXX.block.entity.SmokerBlockEntity
- XXX.block.entity.SpawnerBlockEntity
+ XXX.block.entity.SpawnerBlockEntity$1
- XXX.block.entity.StructureBlockEntity
+ XXX.block.entity.StructureBlockEntity$1
- XXX.block.entity.StructureBlockEntity$UpdateType
+ XXX.block.entity.TheEndGatewayBlockEntity
- XXX.block.entity.TheEndPortalBlockEntity
+ XXX.block.entity.TickableBlockEntity
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
+ XXX.block.state.AbstractStateHolder
- XXX.block.state.AbstractStateHolder$1
+ XXX.block.state.BlockState
- XXX.block.state.BlockState$1
+ XXX.block.state.BlockState$Cache
- XXX.block.state.package-info
- XXX.block.state.StateDefinition
+ XXX.block.state.StateDefinition$Builder
- XXX.block.state.StateDefinition$Factory
+ XXX.block.state.StateHolder
- XXX.boss.enderdragon.EndCrystal
+ XXX.boss.enderdragon.EnderDragon
- XXX.boss.enderdragon.package-info
+ XXX.boss.wither.package-info
+ XXX.boss.wither.WitherBoss
- XXX.boss.wither.WitherBoss$WitherDoNothingGoal
+ XXX.chunk.storage.ChunkSerializer
- XXX.chunk.storage.ChunkStorage
+ XXX.chunk.storage.IOWorker
- XXX.chunk.storage.IOWorker$1
+ XXX.chunk.storage.IOWorker$PendingStore
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
+ XXX.client.gui.Font
- XXX.client.gui.Gui
+ XXX.client.gui.GuiComponent
- XXX.client.gui.MapRenderer
+ XXX.client.gui.MapRenderer$1
- XXX.client.gui.MapRenderer$MapInstance
- XXX.client.gui.package-info
- XXX.client.main.GameConfig
+ XXX.client.main.GameConfig$FolderData
- XXX.client.main.GameConfig$GameData
+ XXX.client.main.GameConfig$ServerData
- XXX.client.main.GameConfig$UserData
+ XXX.client.main.Main
- XXX.client.main.Main$1
+ XXX.client.main.Main$2
- XXX.client.main.Main$3
- XXX.client.main.package-info
+ XXX.client.main.SilentInitException
+ XXX.client.map.Map
- XXX.client.map.Map$1
+ XXX.client.map.Map$2
- XXX.client.map.Map$3
+ XXX.client.map.package-info
- XXX.client.model.AbstractZombieModel
+ XXX.client.model.AgeableListModel
- XXX.client.model.AnimationUtils
- XXX.client.resources.ClientPackSource$2
+ XXX.client.resources.DefaultClientResourcePack
- XXX.client.resources.DefaultPlayerSkin
+ XXX.client.resources.DirectAssetIndex
- XXX.client.resources.FoliageColorReloadListener
+ XXX.client.resources.GrassColorReloadListener
- XXX.client.resources.LegacyResourcePackAdapter
+ XXX.client.resources.LegacyStuffWrapper
- XXX.client.resources.MobEffectTextureManager
+ XXX.client.resources.PackAdapterV4
- XXX.client.resources.package-info
- XXX.client.resources.PaintingTextureManager
+ XXX.client.resources.SkinManager
- XXX.client.resources.SkinManager$1
+ XXX.client.resources.SkinManager$SkinTextureCallback
- XXX.client.resources.SplashManager
+ XXX.client.resources.TextureAtlasHolder
- XXX.client.resources.UnopenedResourcePack
- XXX.client.searchtree.MutableSearchTree
- XXX.client.searchtree.package-info
+ XXX.client.searchtree.ReloadableIdSearchTree
- XXX.client.searchtree.ReloadableIdSearchTree$IntersectionIterator
+ XXX.client.searchtree.ReloadableSearchTree
- XXX.client.searchtree.ReloadableSearchTree$MergingUniqueIterator
+ XXX.client.searchtree.SearchRegistry
- XXX.client.searchtree.SearchRegistry$Key
+ XXX.client.searchtree.SearchTree
- XXX.client.searchtree.SuffixArray
+ XXX.client.searchtree.SuffixArray$1
+ XXX.client.server.IntegratedPlayerList
- XXX.client.server.IntegratedServer
+ XXX.client.server.LanServer
- XXX.client.server.LanServerDetection
+ XXX.client.server.LanServerDetection$LanServerDetector
- XXX.client.server.LanServerDetection$LanServerList
+ XXX.client.server.LanServerPinger
- XXX.client.server.package-info
+ XXX.client.skins.package-info
- XXX.client.sounds.AudioStream
+ XXX.client.sounds.ChannelAccess
- XXX.client.sounds.ChannelAccess$ChannelHandle
+ XXX.client.sounds.LoopingAudioStream
- XXX.client.sounds.LoopingAudioStream$1
+ XXX.client.sounds.LoopingAudioStream$AudioStreamProvider
- XXX.client.sounds.LoopingAudioStream$NoCloseBuffer
+ XXX.client.sounds.MusicManager
- XXX.client.sounds.MusicManager$Music
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
+ XXX.client.tutorial.CompletedTutorialStepInstance
- XXX.client.tutorial.CraftPlanksTutorialStep
+ XXX.client.tutorial.FindTreeTutorialStepInstance
- XXX.client.tutorial.MovementTutorialStepInstance
+ XXX.client.tutorial.OpenInventoryTutorialStep
- XXX.client.tutorial.package-info
- XXX.client.tutorial.PunchTreeTutorialStepInstance
+ XXX.client.tutorial.Tutorial
- XXX.client.tutorial.TutorialStepInstance
+ XXX.client.tutorial.TutorialSteps
- XXX.color.block.BlockColor
+ XXX.color.block.BlockColors
- XXX.color.block.BlockTintCache
+ XXX.color.block.BlockTintCache$1
- XXX.color.block.BlockTintCache$LatestCacheInfo
+ XXX.color.block.package-info
- XXX.color.item.ItemColor
+ XXX.color.item.ItemColors
- XXX.color.item.package-info
+ XXX.commands.arguments.ColorArgument
- XXX.commands.arguments.ComponentArgument
+ XXX.commands.arguments.CompoundTagArgument
- XXX.commands.arguments.DimensionTypeArgument
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
- XXX.commands.arguments.NbtPathArgument$ListElementFunction
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
+ XXX.commands.arguments.RangeArgument$Floats$Serializer
- XXX.commands.arguments.RangeArgument$Ints
+ XXX.commands.arguments.RangeArgument$Ints$Serializer
- XXX.commands.arguments.RangeArgument$Serializer
+ XXX.commands.arguments.ResourceLocationArgument
- XXX.commands.arguments.ScoreboardSlotArgument
- XXX.commands.arguments.ScoreHolderArgument
+ XXX.commands.arguments.ScoreHolderArgument$Result
- XXX.commands.arguments.ScoreHolderArgument$SelectorResult
+ XXX.commands.arguments.ScoreHolderArgument$Serializer
+ XXX.commands.arguments.SlotArgument
- XXX.commands.arguments.TeamArgument
+ XXX.commands.arguments.TimeArgument
+ XXX.commands.exceptions.package-info
+ XXX.commands.synchronization.ArgumentSerializer
- XXX.commands.synchronization.ArgumentTypes
+ XXX.commands.synchronization.ArgumentTypes$1
- XXX.commands.synchronization.ArgumentTypes$Entry
+ XXX.commands.synchronization.EmptyArgumentSerializer
- XXX.commands.synchronization.package-info
- XXX.commands.synchronization.SuggestionProviders
+ XXX.commands.synchronization.SuggestionProviders$Wrapper
+ XXX.components.events.AbstractContainerEventHandler
- XXX.components.events.ContainerEventHandler
+ XXX.components.events.GuiEventListener
- XXX.components.events.package-info
+ XXX.components.spectator.package-info
- XXX.components.spectator.SpectatorGui
- XXX.components.toasts.AdvancementToast
+ XXX.components.toasts.package-info
+ XXX.components.toasts.RecipeToast
- XXX.components.toasts.SystemToast
+ XXX.components.toasts.SystemToast$SystemToastIds
- XXX.components.toasts.Toast
+ XXX.components.toasts.Toast$Visibility
- XXX.components.toasts.ToastComponent
+ XXX.components.toasts.ToastComponent$1
- XXX.components.toasts.ToastComponent$ToastInstance
+ XXX.components.toasts.TutorialToast
- XXX.components.toasts.TutorialToast$Icons
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
+ XXX.core.dispenser.DispenseItemBehavior$22
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
- XXX.data.loot.package-info
+ XXX.data.loot.PiglinBarterLoot
- XXX.data.models.BlockModelGenerators$1
- XXX.data.models.BlockModelGenerators$BlockFamilyProvider
- XXX.data.models.BlockModelGenerators$WoodProvider
- XXX.data.models.ModelProvider
- XXX.datafix.fixes.EntityProjectileOwnerFix
+ XXX.datafix.fixes.EntityPufferfishRenameFix
- XXX.datafix.fixes.EntityRavagerRenameFix
+ XXX.datafix.fixes.EntityRedundantChanceTagsFix
- XXX.datafix.fixes.EntityRenameFix
+ XXX.datafix.fixes.EntityRidingToPassengersFix
- XXX.datafix.fixes.EntityShulkerColorFix
+ XXX.datafix.fixes.EntitySkeletonSplitFix
- XXX.datafix.fixes.EntityStringUuidFix
+ XXX.datafix.fixes.EntityTheRenameningFix
- XXX.datafix.fixes.EntityTippedArrowFix
+ XXX.datafix.fixes.EntityWolfColorFix
- XXX.datafix.fixes.EntityZombieSplitFix
+ XXX.datafix.fixes.EntityZombieVillagerTypeFix
- XXX.datafix.fixes.EntityZombifiedPiglinRenameFix
+ XXX.datafix.fixes.ForcePoiRebuild
- XXX.datafix.fixes.FurnaceRecipeFix
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
- XXX.datafix.fixes.ItemWaterPotionFix
+ XXX.datafix.fixes.ItemWrittenBookPagesStrictJsonFix
- XXX.datafix.fixes.LeavesFix
+ XXX.datafix.fixes.LeavesFix$LeavesSection
- XXX.datafix.fixes.LeavesFix$Section
+ XXX.datafix.fixes.LevelDataGeneratorOptionsFix
- XXX.datafix.fixes.LevelFlatGeneratorInfoFix
+ XXX.datafix.fixes.MapIdFix
- XXX.datafix.fixes.MemoryExpiryDataFix
+ XXX.datafix.fixes.MobSpawnerEntityIdentifiersFix
- XXX.datafix.fixes.NamedEntityFix
+ XXX.datafix.fixes.NewVillageFix
- XXX.datafix.fixes.ObjectiveDisplayNameFix
+ XXX.datafix.fixes.ObjectiveRenderTypeFix
- XXX.datafix.fixes.OptionsAddTextBackgroundFix
+ XXX.datafix.fixes.OptionsForceVBOFix
- XXX.datafix.fixes.OptionsKeyLwjgl3Fix
+ XXX.datafix.fixes.OptionsKeyTranslationFix
- XXX.datafix.fixes.OptionsLowerCaseLanguageFix
+ XXX.datafix.fixes.package-info
+ XXX.datafix.fixes.PoiTypeRename
- XXX.datafix.fixes.RecipesFix
+ XXX.datafix.fixes.RecipesRenameFix
- XXX.datafix.fixes.RecipesRenameningFix
+ XXX.datafix.fixes.References
- XXX.datafix.fixes.RenameBiomesFix
+ XXX.datafix.fixes.RenamedCoralFansFix
- XXX.datafix.fixes.RenamedCoralFix
+ XXX.datafix.fixes.ReorganizePoi
- XXX.datafix.fixes.SavedDataVillageCropFix
+ XXX.datafix.fixes.SimpleEntityRenameFix
- XXX.datafix.fixes.SimplestEntityRenameFix
+ XXX.datafix.fixes.StatsCounterFix
- XXX.datafix.fixes.StructureReferenceCountFix
+ XXX.datafix.fixes.SwimStatsRenameFix
- XXX.datafix.fixes.TeamDisplayNameFix
+ XXX.datafix.fixes.TrappedChestBlockEntityFix
- XXX.datafix.fixes.TrappedChestBlockEntityFix$TrappedChestSection
+ XXX.datafix.fixes.VillagerDataFix
- XXX.datafix.fixes.VillagerRebuildLevelAndXpFix
+ XXX.datafix.fixes.VillagerTradeFix
- XXX.datafix.fixes.WallPropertyFix
+ XXX.datafix.fixes.WriteAndReadFix
- XXX.datafix.fixes.ZombieVillagerRebuildXpFix
+ XXX.datafix.schemas.NamespacedSchema
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
- XXX.dimension.end.DragonRespawnAnimation
+ XXX.dimension.end.DragonRespawnAnimation$1
- XXX.dimension.end.DragonRespawnAnimation$2
+ XXX.dimension.end.DragonRespawnAnimation$3
- XXX.dimension.end.DragonRespawnAnimation$4
+ XXX.dimension.end.DragonRespawnAnimation$5
- XXX.dimension.end.EndDragonFight
- XXX.dimension.end.package-info
+ XXX.dimension.end.TheEndDimension
+ XXX.enderdragon.phases.AbstractDragonPhaseInstance
- XXX.enderdragon.phases.AbstractDragonSittingPhase
+ XXX.enderdragon.phases.DragonChargePlayerPhase
- XXX.enderdragon.phases.DragonDeathPhase
+ XXX.enderdragon.phases.DragonHoldingPatternPhase
- XXX.enderdragon.phases.DragonHoverPhase
+ XXX.enderdragon.phases.DragonLandingApproachPhase
- XXX.enderdragon.phases.DragonLandingPhase
+ XXX.enderdragon.phases.DragonPhaseInstance
- XXX.enderdragon.phases.DragonSittingAttackingPhase
+ XXX.enderdragon.phases.DragonSittingFlamingPhase
- XXX.enderdragon.phases.DragonSittingScanningPhase
+ XXX.enderdragon.phases.DragonStrafePlayerPhase
- XXX.enderdragon.phases.DragonTakeoffPhase
+ XXX.enderdragon.phases.EnderDragonPhase
- XXX.enderdragon.phases.EnderDragonPhaseManager
+ XXX.enderdragon.phases.package-info
- XXX.entity.ai.Brain
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
- XXX.entity.animal.IronGolem$Crackiness
+ XXX.entity.animal.MushroomCow
- XXX.entity.animal.MushroomCow$MushroomType
+ XXX.entity.animal.Ocelot
- XXX.entity.animal.Ocelot$OcelotAvoidEntityGoal
+ XXX.entity.animal.Ocelot$OcelotTemptGoal
+ XXX.entity.animal.package-info
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
+ XXX.entity.animal.Turtle$TurtleTemptGoal
- XXX.entity.animal.Turtle$TurtleTravelGoal
+ XXX.entity.animal.WaterAnimal
- XXX.entity.animal.Wolf
+ XXX.entity.animal.Wolf$WolfAvoidEntityGoal
- XXX.entity.boss.BossMob
+ XXX.entity.boss.EnderDragonPart
- XXX.entity.boss.package-info
- XXX.entity.decoration.ArmorStand
+ XXX.entity.decoration.ArmorStand$1
- XXX.entity.decoration.HangingEntity
+ XXX.entity.decoration.HangingEntity$1
- XXX.entity.decoration.ItemFrame
+ XXX.entity.decoration.ItemFrame$1
- XXX.entity.decoration.LeashFenceKnotEntity
+ XXX.entity.decoration.Motive
+ XXX.entity.decoration.package-info
- XXX.entity.decoration.Painting
- XXX.entity.fishing.FishingHook
+ XXX.entity.fishing.FishingHook$FishHookState
- XXX.entity.fishing.package-info
+ XXX.entity.global.LightningBolt
- XXX.entity.global.package-info
+ XXX.entity.item.FallingBlockEntity
- XXX.entity.item.ItemEntity
- XXX.entity.item.package-info
+ XXX.entity.item.PrimedTnt
+ XXX.entity.monster.AbstractIllager
- XXX.entity.monster.AbstractIllager$IllagerArmPose
+ XXX.entity.monster.AbstractIllager$RaiderOpenDoorGoal
- XXX.entity.monster.AbstractSkeleton
+ XXX.entity.monster.AbstractSkeleton$1
- XXX.entity.monster.Blaze
+ XXX.entity.monster.Blaze$BlazeAttackGoal
- XXX.entity.monster.CaveSpider
+ XXX.entity.monster.Creeper
- XXX.entity.monster.CrossbowAttackMob
+ XXX.entity.monster.Drowned
- XXX.entity.monster.Drowned$DrownedAttackGoal
+ XXX.entity.monster.Drowned$DrownedGoToBeachGoal
- XXX.entity.monster.Drowned$DrownedGoToWaterGoal
+ XXX.entity.monster.Drowned$DrownedMoveControl
- XXX.entity.monster.Drowned$DrownedSwimUpGoal
+ XXX.entity.monster.Drowned$DrownedTridentAttackGoal
- XXX.entity.monster.ElderGuardian
+ XXX.entity.monster.EnderMan
- XXX.entity.monster.EnderMan$EndermanFreezeWhenLookedAt
+ XXX.entity.monster.EnderMan$EndermanLeaveBlockGoal
- XXX.entity.monster.EnderMan$EndermanLookForPlayerGoal
+ XXX.entity.monster.EnderMan$EndermanTakeBlockGoal
- XXX.entity.monster.Endermite
+ XXX.entity.monster.Enemy
- XXX.entity.monster.Evoker
+ XXX.entity.monster.Evoker$1
- XXX.entity.monster.Evoker$EvokerAttackSpellGoal
+ XXX.entity.monster.Evoker$EvokerCastingSpellGoal
- XXX.entity.monster.Evoker$EvokerSummonSpellGoal
+ XXX.entity.monster.Evoker$EvokerWololoSpellGoal
- XXX.entity.monster.Ghast
+ XXX.entity.monster.Ghast$GhastLookGoal
- XXX.entity.monster.Ghast$GhastMoveControl
+ XXX.entity.monster.Ghast$GhastShootFireballGoal
- XXX.entity.monster.Ghast$RandomFloatAroundGoal
+ XXX.entity.monster.Giant
- XXX.entity.monster.Guardian
+ XXX.entity.monster.Guardian$GuardianAttackGoal
- XXX.entity.monster.Guardian$GuardianAttackSelector
+ XXX.entity.monster.Guardian$GuardianMoveControl
- XXX.entity.monster.Husk
+ XXX.entity.monster.Illusioner
- XXX.entity.monster.Illusioner$1
+ XXX.entity.monster.Illusioner$IllusionerBlindnessSpellGoal
- XXX.entity.monster.Illusioner$IllusionerMirrorSpellGoal
+ XXX.entity.monster.MagmaCube
- XXX.entity.monster.Monster
- XXX.entity.monster.package-info
+ XXX.entity.monster.PatrollingMonster
- XXX.entity.monster.PatrollingMonster$LongDistancePatrolGoal
+ XXX.entity.monster.Phantom
- XXX.entity.monster.Phantom$1
+ XXX.entity.monster.Phantom$AttackPhase
- XXX.entity.monster.Phantom$PhantomAttackPlayerTargetGoal
+ XXX.entity.monster.Phantom$PhantomAttackStrategyGoal
- XXX.entity.monster.Phantom$PhantomBodyRotationControl
+ XXX.entity.monster.Phantom$PhantomCircleAroundAnchorGoal
- XXX.entity.monster.Phantom$PhantomLookControl
+ XXX.entity.monster.Phantom$PhantomMoveControl
- XXX.entity.monster.Phantom$PhantomMoveTargetGoal
+ XXX.entity.monster.Phantom$PhantomSweepAttackGoal
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
- XXX.entity.monster.ZombifiedPiglin
+ XXX.entity.monster.ZombifiedPiglin$ZombifiedPiglinAngerTargetGoal
- XXX.entity.monster.ZombifiedPiglin$ZombifiedPiglinHurtByOtherGoal
- XXX.feature.blockplacers.BlockPlacer
+ XXX.feature.blockplacers.BlockPlacerType
- XXX.feature.blockplacers.ColumnPlacer
+ XXX.feature.blockplacers.DoublePlantPlacer
+ XXX.feature.blockplacers.package-info
- XXX.feature.blockplacers.SimpleBlockPlacer
- XXX.feature.configurations.BlockBlobConfiguration
+ XXX.feature.configurations.BlockPileConfiguration
- XXX.feature.configurations.BlockStateConfiguration
+ XXX.feature.configurations.BuriedTreasureConfiguration
- XXX.feature.configurations.ChanceRangeDecoratorConfiguration
+ XXX.feature.configurations.CountFeatureConfiguration
- XXX.feature.configurations.CountRangeDecoratorConfiguration
+ XXX.feature.configurations.DecoratedFeatureConfiguration
- XXX.feature.configurations.DecoratorConfiguration
+ XXX.feature.configurations.DiskConfiguration
- XXX.feature.configurations.EndGatewayConfiguration
+ XXX.feature.configurations.FeatureConfiguration
- XXX.feature.configurations.FeatureRadiusConfiguration
+ XXX.feature.configurations.HugeMushroomFeatureConfiguration
- XXX.feature.configurations.LayerConfiguration
+ XXX.feature.configurations.MegaTreeConfiguration
- XXX.feature.configurations.MegaTreeConfiguration$MegaTreeConfigurationBuilder
+ XXX.feature.configurations.MineshaftConfiguration
- XXX.feature.configurations.NoiseDependantDecoratorConfiguration
+ XXX.feature.configurations.NoneDecoratorConfiguration
- XXX.feature.configurations.NoneFeatureConfiguration
+ XXX.feature.configurations.OceanRuinConfiguration
- XXX.feature.configurations.OreConfiguration
+ XXX.feature.configurations.OreConfiguration$Predicates
+ XXX.feature.configurations.package-info
- XXX.feature.configurations.ProbabilityFeatureConfiguration
+ XXX.feature.configurations.RandomBooleanFeatureConfiguration
- XXX.feature.configurations.RandomFeatureConfiguration
+ XXX.feature.configurations.RandomPatchConfiguration
- XXX.feature.configurations.RandomPatchConfiguration$1
+ XXX.feature.configurations.RandomPatchConfiguration$GrassConfigurationBuilder
- XXX.feature.configurations.RandomRandomFeatureConfiguration
+ XXX.feature.configurations.ReplaceBlockConfiguration
- XXX.feature.configurations.SeagrassFeatureConfiguration
+ XXX.feature.configurations.ShipwreckConfiguration
- XXX.feature.configurations.SimpleBlockConfiguration
+ XXX.feature.configurations.SimpleRandomFeatureConfiguration
- XXX.feature.configurations.SmallTreeConfiguration
+ XXX.feature.configurations.SmallTreeConfiguration$SmallTreeConfigurationBuilder
- XXX.feature.configurations.SpikeConfiguration
+ XXX.feature.configurations.SpringConfiguration
- XXX.feature.configurations.TreeConfiguration
+ XXX.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
- XXX.feature.configurations.VillageConfiguration
- XXX.feature.foliageplacers.AcaciaFoliagePlacer
+ XXX.feature.foliageplacers.BlobFoliagePlacer
- XXX.feature.foliageplacers.FoliagePlacer
+ XXX.feature.foliageplacers.FoliagePlacerType
- XXX.feature.foliageplacers.package-info
- XXX.feature.foliageplacers.PineFoliagePlacer
+ XXX.feature.foliageplacers.SpruceFoliagePlacer
- XXX.feature.stateproviders.BlockStateProvider
+ XXX.feature.stateproviders.BlockStateProviderType
- XXX.feature.stateproviders.ForestFlowerProvider
+ XXX.feature.stateproviders.package-info
+ XXX.feature.stateproviders.PlainFlowerProvider
- XXX.feature.stateproviders.RotatedBlockProvider
+ XXX.feature.stateproviders.SimpleStateProvider
- XXX.feature.stateproviders.WeightedStateProvider
- XXX.feature.structures.EmptyPoolElement
+ XXX.feature.structures.FeaturePoolElement
- XXX.feature.structures.JigsawJunction
+ XXX.feature.structures.JigsawPlacement
- XXX.feature.structures.JigsawPlacement$1
+ XXX.feature.structures.JigsawPlacement$PieceFactory
- XXX.feature.structures.JigsawPlacement$PieceState
+ XXX.feature.structures.JigsawPlacement$Placer
- XXX.feature.structures.ListPoolElement
+ XXX.feature.structures.package-info
+ XXX.feature.structures.SinglePoolElement
- XXX.feature.structures.StructurePoolElement
+ XXX.feature.structures.StructurePoolElementType
- XXX.feature.structures.StructureTemplatePool
+ XXX.feature.structures.StructureTemplatePool$Projection
- XXX.feature.structures.StructureTemplatePools
- XXX.feature.treedecorators.AlterGroundDecorator
+ XXX.feature.treedecorators.BeehiveDecorator
- XXX.feature.treedecorators.CocoaDecorator
+ XXX.feature.treedecorators.LeaveVineDecorator
+ XXX.feature.treedecorators.package-info
- XXX.feature.treedecorators.TreeDecorator
+ XXX.feature.treedecorators.TreeDecoratorType
- XXX.feature.treedecorators.TrunkVineDecorator
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
+ XXX.goal.target.package-info
- XXX.goal.target.TargetGoal
+ XXX.gui.chat.ChatListener
- XXX.gui.chat.NarratorChatListener
+ XXX.gui.chat.OverlayChatListener
+ XXX.gui.chat.package-info
- XXX.gui.chat.StandardChatListener
- XXX.gui.components.AbstractButton
+ XXX.gui.components.package-info
- XXX.gui.components.TickableWidget
+ XXX.gui.components.VolumeSlider
- XXX.gui.components.Widget
- XXX.gui.font.AllMissingGlyphProvider
+ XXX.gui.font.FontManager
- XXX.gui.font.FontManager$1
+ XXX.gui.font.FontManager$2
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
- XXX.gui.screens.DeathScreen
+ XXX.gui.screens.DemoIntroScreen
- XXX.gui.screens.DirectJoinServerScreen
+ XXX.gui.screens.DisconnectedScreen
- XXX.gui.screens.EditServerScreen
+ XXX.gui.screens.ErrorScreen
- XXX.gui.screens.GenericDirtMessageScreen
+ XXX.gui.screens.InBedChatScreen
- XXX.gui.screens.LanguageSelectScreen
+ XXX.gui.screens.LanguageSelectScreen$LanguageSelectionList
- XXX.gui.screens.LanguageSelectScreen$LanguageSelectionList$Entry
+ XXX.gui.screens.LevelLoadingScreen
- XXX.gui.screens.LoadingOverlay
+ XXX.gui.screens.LoadingOverlay$LogoTexture
- XXX.gui.screens.MenuScreens
+ XXX.gui.screens.MenuScreens$ScreenConstructor
- XXX.gui.screens.MouseSettingsScreen
+ XXX.gui.screens.OptionsScreen
- XXX.gui.screens.OptionsSubScreen
+ XXX.gui.screens.OutOfMemoryScreen
- XXX.gui.screens.Overlay
- XXX.gui.screens.package-info
+ XXX.gui.screens.PauseScreen
- XXX.gui.screens.PresetFlatWorldScreen
+ XXX.gui.screens.PresetFlatWorldScreen$PresetInfo
- XXX.gui.screens.PresetFlatWorldScreen$PresetsList
+ XXX.gui.screens.PresetFlatWorldScreen$PresetsList$Entry
- XXX.gui.screens.ProgressScreen
- XXX.gui.screens.RealmsBackupInfoScreen
+ XXX.gui.screens.RealmsBackupInfoScreen$1
+ XXX.gui.screens.RealmsBackupScreen$2
+ XXX.gui.screens.RealmsBackupScreen$4
+ XXX.gui.screens.RealmsBrokenWorldScreen$2
+ XXX.gui.screens.RealmsBrokenWorldScreen$PlayButton
+ XXX.gui.screens.RealmsClientOutdatedScreen$1
- XXX.gui.screens.RealmsConfigureWorldScreen
+ XXX.gui.screens.RealmsConfigureWorldScreen$1
+ XXX.gui.screens.RealmsConfigureWorldScreen$3
+ XXX.gui.screens.RealmsConfigureWorldScreen$5
+ XXX.gui.screens.RealmsConfigureWorldScreen$7
+ XXX.gui.screens.RealmsConfigureWorldScreen$9
- XXX.gui.screens.RealmsConfirmScreen
+ XXX.gui.screens.RealmsConfirmScreen$1
+ XXX.gui.screens.RealmsCreateRealmScreen
+ XXX.gui.screens.RealmsCreateRealmScreen$2
- XXX.gui.screens.RealmsDownloadLatestWorldScreen
+ XXX.gui.screens.RealmsDownloadLatestWorldScreen$1
+ XXX.gui.screens.RealmsInviteScreen
+ XXX.gui.screens.RealmsInviteScreen$2
- XXX.gui.screens.RealmsLongConfirmationScreen
+ XXX.gui.screens.RealmsLongConfirmationScreen$1
+ XXX.gui.screens.RealmsLongConfirmationScreen$3
+ XXX.gui.screens.RealmsLongRunningMcoTaskScreen$2
+ XXX.gui.screens.RealmsParentalConsentScreen$1
+ XXX.gui.screens.RealmsParentalConsentScreen$3
- XXX.gui.screens.RealmsPendingInvitesScreen
+ XXX.gui.screens.RealmsPendingInvitesScreen$1
- XXX.gui.screens.RealmsPendingInvitesScreen$2
+ XXX.gui.screens.RealmsPendingInvitesScreen$3
+ XXX.gui.screens.RealmsPendingInvitesScreen$5
- XXX.gui.screens.RealmsPendingInvitesScreen$Entry
- XXX.gui.screens.RealmsPendingInvitesScreen$Entry$RejectRowButton
+ XXX.gui.screens.RealmsPendingInvitesScreen$PendingInvitationSelectionList
+ XXX.gui.screens.RealmsPendingInvitesScreen$PendingInvitationSelectionListEntry$AcceptRowButton
+ XXX.gui.screens.RealmsPlayerScreen$2
+ XXX.gui.screens.RealmsPlayerScreen$4
- XXX.gui.screens.RealmsPlayerScreen$InvitedObjectSelectionList
+ XXX.gui.screens.RealmsPlayerScreen$InvitedObjectSelectionListEntry
+ XXX.gui.screens.RealmsResetNormalWorldScreen$1
+ XXX.gui.screens.RealmsResetNormalWorldScreen$3
+ XXX.gui.screens.RealmsResetWorldScreen$4
+ XXX.gui.screens.RealmsResetWorldScreen$6
+ XXX.gui.screens.RealmsResetWorldScreen$8
+ XXX.gui.screens.RealmsResetWorldScreen$FrameButton
- XXX.gui.screens.RealmsResetWorldScreen$ResetType
+ XXX.gui.screens.RealmsResetWorldScreen$ResetWorldInfo
+ XXX.gui.screens.RealmsSelectFileToUploadScreen$1
- XXX.gui.screens.RealmsSelectFileToUploadScreen$Entry
+ XXX.gui.screens.RealmsSelectFileToUploadScreen$WorldListEntry
+ XXX.gui.screens.RealmsSelectWorldTemplateScreen$2
+ XXX.gui.screens.RealmsSelectWorldTemplateScreen$4
- XXX.gui.screens.RealmsSelectWorldTemplateScreen$Entry
+ XXX.gui.screens.RealmsSelectWorldTemplateScreen$WorldTemplateObjectSelectionList
+ XXX.gui.screens.RealmsSettingsScreen$2
+ XXX.gui.screens.RealmsSlotOptionsScreen
+ XXX.gui.screens.RealmsSlotOptionsScreen$10
+ XXX.gui.screens.RealmsSlotOptionsScreen$3
+ XXX.gui.screens.RealmsSlotOptionsScreen$5
+ XXX.gui.screens.RealmsSlotOptionsScreen$7
+ XXX.gui.screens.RealmsSlotOptionsScreen$9
- XXX.gui.screens.RealmsSlotOptionsScreen$SettingsSlider
+ XXX.gui.screens.RealmsSubscriptionInfoScreen
- XXX.gui.screens.RealmsSubscriptionInfoScreen$1
+ XXX.gui.screens.RealmsSubscriptionInfoScreen$2
+ XXX.gui.screens.RealmsSubscriptionInfoScreen$4
+ XXX.gui.screens.RealmsTermsScreen$1
+ XXX.gui.screens.RealmsUploadScreen$2
+ XXX.gui.screens.ReceivingLevelScreen
- XXX.gui.screens.Screen
+ XXX.gui.screens.ShareToLanScreen
- XXX.gui.screens.SkinCustomizationScreen
+ XXX.gui.screens.SoundOptionsScreen
- XXX.gui.screens.TitleScreen
+ XXX.gui.screens.UploadResult
- XXX.gui.screens.UploadResult$1
+ XXX.gui.screens.VideoSettingsScreen
- XXX.gui.screens.WinScreen
+ XXX.gui.spectator.package-info
+ XXX.gui.spectator.PlayerMenuItem
- XXX.gui.spectator.RootSpectatorMenuCategory
+ XXX.gui.spectator.SpectatorMenu
- XXX.gui.spectator.SpectatorMenu$1
+ XXX.gui.spectator.SpectatorMenu$CloseSpectatorItem
- XXX.gui.spectator.SpectatorMenu$ScrollMenuItem
+ XXX.gui.spectator.SpectatorMenuCategory
- XXX.gui.spectator.SpectatorMenuItem
+ XXX.gui.spectator.SpectatorMenuListener
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
- XXX.level.block.GrowingPlantBodyBlock
- XXX.level.block.HalfTransparentBlock
+ XXX.level.block.HayBlock
- XXX.level.block.HoneyBlock
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
- XXX.level.block.NetherrackBlock
- XXX.level.block.NetherSproutsBlock
+ XXX.level.block.NetherWartBlock
+ XXX.level.block.NoteBlock
- XXX.level.block.NyliumBlock
+ XXX.level.block.ObserverBlock
- XXX.level.block.OreBlock
+ XXX.level.block.package-info
+ XXX.level.block.PipeBlock
- XXX.level.block.PlayerHeadBlock
+ XXX.level.block.PlayerWallHeadBlock
- XXX.level.block.PotatoBlock
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
+ XXX.level.block.RootsBlock
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
+ XXX.level.block.SoulFireBlock
- XXX.level.block.SoulSandBlock
+ XXX.level.block.SoundType
- XXX.level.block.SpawnerBlock
+ XXX.level.block.SpongeBlock
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
- XXX.level.block.SweetBerryBushBlock
+ XXX.level.block.TallFlowerBlock
- XXX.level.block.TallGrassBlock
+ XXX.level.block.TallSeagrass
- XXX.level.block.TargetBlock
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
+ XXX.level.block.WallBlock$1
- XXX.level.block.WallSignBlock
+ XXX.level.block.WallSkullBlock
- XXX.level.block.WallTorchBlock
+ XXX.level.block.WaterlilyBlock
- XXX.level.block.WebBlock
+ XXX.level.block.WeepingVines
- XXX.level.block.WeepingVinesPlant
+ XXX.level.block.WeightedPressurePlateBlock
- XXX.level.block.WetSpongeBlock
+ XXX.level.block.WitherRoseBlock
- XXX.level.block.WitherSkullBlock
+ XXX.level.block.WitherWallSkullBlock
- XXX.level.block.WoodButtonBlock
+ XXX.level.block.WoolCarpetBlock
+ XXX.level.border.BorderChangeListener
- XXX.level.border.BorderChangeListener$DelegateBorderChangeListener
+ XXX.level.border.BorderStatus
+ XXX.level.border.package-info
- XXX.level.border.WorldBorder
+ XXX.level.border.WorldBorder$1
- XXX.level.border.WorldBorder$BorderExtent
+ XXX.level.border.WorldBorder$MovingBorderExtent
- XXX.level.border.WorldBorder$StaticBorderExtent
- XXX.level.chunk.ChunkAccess
+ XXX.level.chunk.ChunkBiomeContainer
- XXX.level.chunk.ChunkGenerator
+ XXX.level.chunk.ChunkGeneratorFactory
- XXX.level.chunk.ChunkGeneratorType
+ XXX.level.chunk.ChunkSource
- XXX.level.chunk.ChunkStatus
+ XXX.level.chunk.ChunkStatus$ChunkType
- XXX.level.chunk.ChunkStatus$GenerationTask
+ XXX.level.chunk.ChunkStatus$LoadingTask
- XXX.level.chunk.ChunkStatus$SimpleGenerationTask
+ XXX.level.chunk.DataLayer
- XXX.level.chunk.EmptyLevelChunk
+ XXX.level.chunk.FeatureAccess
- XXX.level.chunk.GlobalPalette
+ XXX.level.chunk.HashMapPalette
- XXX.level.chunk.ImposterProtoChunk
+ XXX.level.chunk.LevelChunk
- XXX.level.chunk.LevelChunk$EntityCreationType
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
+ XXX.level.levelgen.package-info
- XXX.level.levelgen.PatrolSpawner
+ XXX.level.levelgen.PhantomSpawner
- XXX.level.levelgen.TheEndGeneratorSettings
+ XXX.level.levelgen.TheEndLevelSource
- XXX.level.levelgen.WorldgenRandom
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
- XXX.level.material.Fluids
- XXX.level.material.FluidState
+ XXX.level.material.FluidStateImpl
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
- XXX.level.storage.LevelStorage
+ XXX.level.storage.LevelStorageException
- XXX.level.storage.LevelStorageSource
+ XXX.level.storage.LevelStorageSource$1
- XXX.level.storage.LevelSummary
+ XXX.level.storage.McRegionUpgrader
- XXX.level.storage.package-info
- XXX.level.storage.PlayerIO
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
+ XXX.levelgen.carver.CanyonWorldCarver
- XXX.levelgen.carver.CarverConfiguration
+ XXX.levelgen.carver.CaveWorldCarver
- XXX.levelgen.carver.ConfiguredWorldCarver
+ XXX.levelgen.carver.NetherWorldCarver
- XXX.levelgen.carver.NoneCarverConfiguration
- XXX.levelgen.carver.package-info
+ XXX.levelgen.carver.UnderwaterCanyonWorldCarver
- XXX.levelgen.carver.UnderwaterCaveWorldCarver
+ XXX.levelgen.carver.WorldCarver
+ XXX.levelgen.feature.AbstractFlowerFeature
- XXX.levelgen.feature.AbstractHugeMushroomFeature
+ XXX.levelgen.feature.AbstractSmallTreeFeature
- XXX.levelgen.feature.AbstractTreeFeature
+ XXX.levelgen.feature.AcaciaFeature
- XXX.levelgen.feature.BambooFeature
+ XXX.levelgen.feature.BasaltPillarFeature
- XXX.levelgen.feature.BlockBlobFeature
+ XXX.levelgen.feature.BlockPileFeature
- XXX.levelgen.feature.BlueIceFeature
+ XXX.levelgen.feature.BonusChestFeature
- XXX.levelgen.feature.BuriedTreasureFeature
+ XXX.levelgen.feature.BuriedTreasureFeature$BuriedTreasureStart
- XXX.levelgen.feature.ChorusPlantFeature
+ XXX.levelgen.feature.ConfiguredFeature
- XXX.levelgen.feature.CoralClawFeature
+ XXX.levelgen.feature.CoralFeature
- XXX.levelgen.feature.CoralMushroomFeature
+ XXX.levelgen.feature.CoralTreeFeature
- XXX.levelgen.feature.DarkOakFeature
+ XXX.levelgen.feature.DecoratedFeature
- XXX.levelgen.feature.DecoratedFlowerFeature
+ XXX.levelgen.feature.DefaultFlowerFeature
- XXX.levelgen.feature.DesertPyramidFeature
+ XXX.levelgen.feature.DesertPyramidFeature$FeatureStart
- XXX.levelgen.feature.DesertVillagePools
+ XXX.levelgen.feature.DesertWellFeature
- XXX.levelgen.feature.DiskReplaceFeature
+ XXX.levelgen.feature.EndCityFeature
- XXX.levelgen.feature.EndCityFeature$EndCityStart
+ XXX.levelgen.feature.EndGatewayFeature
- XXX.levelgen.feature.EndIslandFeature
+ XXX.levelgen.feature.EndPodiumFeature
- XXX.levelgen.feature.FancyTreeFeature
+ XXX.levelgen.feature.FancyTreeFeature$FoliageCoords
- XXX.levelgen.feature.Feature
+ XXX.levelgen.feature.FillLayerFeature
- XXX.levelgen.feature.FossilFeature
+ XXX.levelgen.feature.GlowstoneFeature
- XXX.levelgen.feature.GroundBushFeature
+ XXX.levelgen.feature.HugeBrownMushroomFeature
- XXX.levelgen.feature.HugeFungusConfiguration
+ XXX.levelgen.feature.HugeFungusFeature
- XXX.levelgen.feature.HugeRedMushroomFeature
+ XXX.levelgen.feature.IcebergFeature
+ XXX.levelgen.feature.IcePatchFeature
- XXX.levelgen.feature.IceSpikeFeature
- XXX.levelgen.feature.IglooFeature
+ XXX.levelgen.feature.IglooFeature$FeatureStart
- XXX.levelgen.feature.JunglePyramidFeature
+ XXX.levelgen.feature.JunglePyramidFeature$FeatureStart
- XXX.levelgen.feature.KelpFeature
+ XXX.levelgen.feature.LakeFeature
- XXX.levelgen.feature.MegaJungleTreeFeature
+ XXX.levelgen.feature.MegaPineTreeFeature
- XXX.levelgen.feature.MegaTreeFeature
+ XXX.levelgen.feature.MineshaftFeature
- XXX.levelgen.feature.MineshaftFeature$MineShaftStart
+ XXX.levelgen.feature.MineshaftFeature$Type
- XXX.levelgen.feature.MonsterRoomFeature
+ XXX.levelgen.feature.NetherForestVegetationFeature
- XXX.levelgen.feature.NetherFortressFeature
+ XXX.levelgen.feature.NetherFortressFeature$NetherBridgeStart
- XXX.levelgen.feature.NoOpFeature
+ XXX.levelgen.feature.NoSurfaceOreFeature
- XXX.levelgen.feature.OceanMonumentFeature
+ XXX.levelgen.feature.OceanMonumentFeature$OceanMonumentStart
- XXX.levelgen.feature.OreFeature
+ XXX.levelgen.feature.package-info
+ XXX.levelgen.feature.PillagerOutpostFeature
- XXX.levelgen.feature.PillagerOutpostFeature$FeatureStart
+ XXX.levelgen.feature.PlainVillagePools
- XXX.levelgen.feature.RandomBooleanSelectorFeature
+ XXX.levelgen.feature.RandomPatchFeature
- XXX.levelgen.feature.RandomRandomFeature
+ XXX.levelgen.feature.RandomScatteredFeature
- XXX.levelgen.feature.RandomSelectorFeature
+ XXX.levelgen.feature.ReplaceBlockFeature
- XXX.levelgen.feature.SavannaVillagePools
- XXX.levelgen.feature.SeagrassFeature
+ XXX.levelgen.feature.SeaPickleFeature
+ XXX.levelgen.feature.ShipwreckFeature
- XXX.levelgen.feature.ShipwreckFeature$FeatureStart
+ XXX.levelgen.feature.SimpleBlockFeature
- XXX.levelgen.feature.SimpleRandomSelectorFeature
+ XXX.levelgen.feature.SimulatedFeature
- XXX.levelgen.feature.SnowAndFreezeFeature
+ XXX.levelgen.feature.SnowyVillagePools
- XXX.levelgen.feature.SpikeFeature
+ XXX.levelgen.feature.SpikeFeature$1
- XXX.levelgen.feature.SpikeFeature$EndSpike
+ XXX.levelgen.feature.SpikeFeature$SpikeCacheLoader
- XXX.levelgen.feature.SpringFeature
+ XXX.levelgen.feature.StrongholdFeature
- XXX.levelgen.feature.StrongholdFeature$StrongholdStart
+ XXX.levelgen.feature.StructureFeature
- XXX.levelgen.feature.StructureFeature$StructureStartFactory
+ XXX.levelgen.feature.StructurePieceType
- XXX.levelgen.feature.SwamplandHutFeature
+ XXX.levelgen.feature.SwamplandHutFeature$FeatureStart
- XXX.levelgen.feature.TaigaVillagePools
+ XXX.levelgen.feature.TreeFeature
- XXX.levelgen.feature.VillageFeature
+ XXX.levelgen.feature.VillageFeature$FeatureStart
- XXX.levelgen.feature.VillagePieces
+ XXX.levelgen.feature.VillagePieces$VillagePiece
- XXX.levelgen.feature.VinesFeature
+ XXX.levelgen.feature.VoidStartPlatformFeature
- XXX.levelgen.feature.WeepingVinesFeature
+ XXX.levelgen.feature.WeightedConfiguredFeature
- XXX.levelgen.feature.WoodlandMansionFeature
+ XXX.levelgen.feature.WoodlandMansionFeature$WoodlandMansionStart
- XXX.levelgen.flat.FlatLayerInfo
+ XXX.levelgen.flat.FlatLevelGeneratorSettings
- XXX.levelgen.flat.package-info
- XXX.levelgen.placement.CarvingMaskDecorator
+ XXX.levelgen.placement.CarvingMaskDecoratorConfiguration
- XXX.levelgen.placement.ChanceDecoratorConfiguration
+ XXX.levelgen.placement.ChanceHeightmapDecorator
- XXX.levelgen.placement.ChanceHeightmapDoubleDecorator
+ XXX.levelgen.placement.ChancePassthroughDecorator
- XXX.levelgen.placement.ChanceTopSolidHeightmapDecorator
+ XXX.levelgen.placement.ChorusPlantPlacementDecorator
- XXX.levelgen.placement.ConfiguredDecorator
+ XXX.levelgen.placement.CountBiasedRangeDecorator
- XXX.levelgen.placement.CountChanceHeightmapDecorator
+ XXX.levelgen.placement.CountChanceHeightmapDoubleDecorator
- XXX.levelgen.placement.CountDepthAverageDecorator
+ XXX.levelgen.placement.CountHeighmapDoubleDecorator
- XXX.levelgen.placement.CountHeight64Decorator
+ XXX.levelgen.placement.CountHeightmap32Decorator
- XXX.levelgen.placement.CountHeightmapDecorator
+ XXX.levelgen.placement.CountTopSolidDecorator
- XXX.levelgen.placement.CountVeryBiasedRangeDecorator
+ XXX.levelgen.placement.CountWithExtraChanceHeightmapDecorator
- XXX.levelgen.placement.DarkOakTreePlacementDecorator
+ XXX.levelgen.placement.DepthAverageConfigation
- XXX.levelgen.placement.EmeraldPlacementDecorator
+ XXX.levelgen.placement.EndGatewayPlacementDecorator
- XXX.levelgen.placement.EndIslandPlacementDecorator
+ XXX.levelgen.placement.FeatureDecorator
- XXX.levelgen.placement.ForestRockPlacementDecorator
+ XXX.levelgen.placement.FrequencyChanceDecoratorConfiguration
- XXX.levelgen.placement.FrequencyDecoratorConfiguration
+ XXX.levelgen.placement.FrequencyWithExtraChanceDecoratorConfiguration
- XXX.levelgen.placement.IcebergPlacementDecorator
+ XXX.levelgen.placement.LakeLavaPlacementDecorator
- XXX.levelgen.placement.LakeWaterPlacementDecorator
+ XXX.levelgen.placement.MonsterRoomPlacementDecorator
- XXX.levelgen.placement.NoiseCountFactorDecoratorConfiguration
+ XXX.levelgen.placement.NoiseHeightmap32Decorator
- XXX.levelgen.placement.NoiseHeightmapDoubleDecorator
+ XXX.levelgen.placement.NopePlacementDecorator
- XXX.levelgen.placement.package-info
- XXX.levelgen.placement.RangeDecoratorConfiguration
+ XXX.levelgen.placement.SimpleFeatureDecorator
- XXX.levelgen.placement.TopSolidHeightMapDecorator
+ XXX.levelgen.placement.TopSolidHeightMapNoiseBasedDecorator
- XXX.levelgen.placement.TopSolidHeightMapRangeDecorator
+ XXX.levelgen.structure.BeardedStructureStart
- XXX.levelgen.structure.BoundingBox
+ XXX.levelgen.structure.BoundingBox$1
- XXX.levelgen.structure.BuriedTreasurePieces
+ XXX.levelgen.structure.BuriedTreasurePieces$BuriedTreasurePiece
- XXX.levelgen.structure.DesertPyramidPiece
+ XXX.levelgen.structure.EndCityPieces
- XXX.levelgen.structure.EndCityPieces$1
+ XXX.levelgen.structure.EndCityPieces$2
- XXX.levelgen.structure.EndCityPieces$3
+ XXX.levelgen.structure.EndCityPieces$4
- XXX.levelgen.structure.EndCityPieces$EndCityPiece
+ XXX.levelgen.structure.EndCityPieces$SectionGenerator
- XXX.levelgen.structure.IglooPieces
+ XXX.levelgen.structure.IglooPieces$IglooPiece
- XXX.levelgen.structure.JunglePyramidPiece
+ XXX.levelgen.structure.JunglePyramidPiece$1
- XXX.levelgen.structure.JunglePyramidPiece$MossStoneSelector
+ XXX.levelgen.structure.LegacyStructureDataHandler
- XXX.levelgen.structure.MineShaftPieces
+ XXX.levelgen.structure.MineShaftPieces$1
- XXX.levelgen.structure.MineShaftPieces$MineShaftCorridor
+ XXX.levelgen.structure.MineShaftPieces$MineShaftCrossing
- XXX.levelgen.structure.MineShaftPieces$MineShaftPiece
+ XXX.levelgen.structure.MineShaftPieces$MineShaftRoom
- XXX.levelgen.structure.MineShaftPieces$MineShaftStairs
+ XXX.levelgen.structure.NetherBridgePieces
- XXX.levelgen.structure.NetherBridgePieces$1
+ XXX.levelgen.structure.NetherBridgePieces$BridgeCrossing
- XXX.levelgen.structure.NetherBridgePieces$BridgeEndFiller
+ XXX.levelgen.structure.NetherBridgePieces$BridgeStraight
- XXX.levelgen.structure.NetherBridgePieces$CastleCorridorStairsPiece
+ XXX.levelgen.structure.NetherBridgePieces$CastleCorridorTBalconyPiece
- XXX.levelgen.structure.NetherBridgePieces$CastleEntrance
+ XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorCrossingPiece
- XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorLeftTurnPiece
+ XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorPiece
- XXX.levelgen.structure.NetherBridgePieces$CastleSmallCorridorRightTurnPiece
+ XXX.levelgen.structure.NetherBridgePieces$CastleStalkRoom
- XXX.levelgen.structure.NetherBridgePieces$MonsterThrone
+ XXX.levelgen.structure.NetherBridgePieces$NetherBridgePiece
- XXX.levelgen.structure.NetherBridgePieces$PieceWeight
+ XXX.levelgen.structure.NetherBridgePieces$RoomCrossing
- XXX.levelgen.structure.NetherBridgePieces$StairsRoom
+ XXX.levelgen.structure.NetherBridgePieces$StartPiece
- XXX.levelgen.structure.NetherFossilFeature
+ XXX.levelgen.structure.NetherFossilFeature$FeatureStart
- XXX.levelgen.structure.NetherFossilPieces
+ XXX.levelgen.structure.NetherFossilPieces$NetherFossilPiece
- XXX.levelgen.structure.OceanMonumentPieces
+ XXX.levelgen.structure.OceanMonumentPieces$1
- XXX.levelgen.structure.OceanMonumentPieces$FitDoubleXRoom
+ XXX.levelgen.structure.OceanMonumentPieces$FitDoubleXYRoom
- XXX.levelgen.structure.OceanMonumentPieces$FitDoubleYRoom
+ XXX.levelgen.structure.OceanMonumentPieces$FitDoubleYZRoom
- XXX.levelgen.structure.OceanMonumentPieces$FitDoubleZRoom
+ XXX.levelgen.structure.OceanMonumentPieces$FitSimpleRoom
- XXX.levelgen.structure.OceanMonumentPieces$FitSimpleTopRoom
+ XXX.levelgen.structure.OceanMonumentPieces$MonumentBuilding
- XXX.levelgen.structure.OceanMonumentPieces$MonumentRoomFitter
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentCoreRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXYRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYZRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleZRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentEntryRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentPenthouse
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentPiece
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleRoom
+ XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleTopRoom
- XXX.levelgen.structure.OceanMonumentPieces$OceanMonumentWingRoom
+ XXX.levelgen.structure.OceanMonumentPieces$RoomDefinition
- XXX.levelgen.structure.OceanRuinFeature
+ XXX.levelgen.structure.OceanRuinFeature$OceanRuinStart
- XXX.levelgen.structure.OceanRuinFeature$Type
+ XXX.levelgen.structure.OceanRuinPieces
- XXX.levelgen.structure.OceanRuinPieces$OceanRuinPiece
+ XXX.levelgen.structure.package-info
+ XXX.levelgen.structure.PillagerOutpostPieces
- XXX.levelgen.structure.PillagerOutpostPieces$PillagerOutpostPiece
+ XXX.levelgen.structure.PoolElementStructurePiece
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
- XXX.levelgen.structure.StructureFeatureIndexSavedData
+ XXX.levelgen.structure.StructureFeatureIO
+ XXX.levelgen.structure.StructurePiece
- XXX.levelgen.structure.StructurePiece$1
+ XXX.levelgen.structure.StructurePiece$BlockSelector
- XXX.levelgen.structure.StructureStart
+ XXX.levelgen.structure.StructureStart$1
- XXX.levelgen.structure.SwamplandHutPiece
+ XXX.levelgen.structure.TemplateStructurePiece
- XXX.levelgen.structure.WoodlandMansionPieces
+ XXX.levelgen.structure.WoodlandMansionPieces$1
- XXX.levelgen.structure.WoodlandMansionPieces$FirstFloorRoomCollection
+ XXX.levelgen.structure.WoodlandMansionPieces$FloorRoomCollection
- XXX.levelgen.structure.WoodlandMansionPieces$MansionGrid
+ XXX.levelgen.structure.WoodlandMansionPieces$MansionPiecePlacer
- XXX.levelgen.structure.WoodlandMansionPieces$PlacementData
+ XXX.levelgen.structure.WoodlandMansionPieces$SecondFloorRoomCollection
- XXX.levelgen.structure.WoodlandMansionPieces$SimpleGrid
+ XXX.levelgen.structure.WoodlandMansionPieces$ThirdFloorRoomCollection
- XXX.levelgen.structure.WoodlandMansionPieces$WoodlandMansionPiece
+ XXX.levelgen.surfacebuilders.BadlandsSurfaceBuilder
- XXX.levelgen.surfacebuilders.ConfiguredSurfaceBuilder
+ XXX.levelgen.surfacebuilders.DefaultSurfaceBuilder
- XXX.levelgen.surfacebuilders.ErodedBadlandsSurfaceBuilder
+ XXX.levelgen.surfacebuilders.FrozenOceanSurfaceBuilder
- XXX.levelgen.surfacebuilders.GiantTreeTaigaSurfaceBuilder
+ XXX.levelgen.surfacebuilders.GravellyMountainSurfaceBuilder
- XXX.levelgen.surfacebuilders.MountainSurfaceBuilder
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
+ XXX.loot.entries.CompositeEntryBase$Serializer
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
- XXX.loot.entries.LootPoolEntries$Serializer
+ XXX.loot.entries.LootPoolEntry
- XXX.loot.entries.LootPoolEntryContainer
+ XXX.loot.entries.LootPoolEntryContainer$Builder
- XXX.loot.entries.LootPoolEntryContainer$Serializer
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
+ XXX.loot.functions.LootingEnchantFunction
- XXX.loot.functions.LootingEnchantFunction$1
+ XXX.loot.functions.LootingEnchantFunction$Builder
- XXX.loot.functions.LootingEnchantFunction$Serializer
- XXX.loot.functions.LootItemConditionalFunction
+ XXX.loot.functions.LootItemConditionalFunction$Builder
- XXX.loot.functions.LootItemConditionalFunction$DummyBuilder
+ XXX.loot.functions.LootItemConditionalFunction$Serializer
- XXX.loot.functions.LootItemFunction
+ XXX.loot.functions.LootItemFunction$Builder
- XXX.loot.functions.LootItemFunction$Serializer
+ XXX.loot.functions.LootItemFunctions
- XXX.loot.functions.LootItemFunctions$Serializer
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
- XXX.loot.predicates.LocationCheck$Serializer
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition
- XXX.loot.predicates.LootItemBlockStatePropertyCondition$1
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition$Builder
- XXX.loot.predicates.LootItemBlockStatePropertyCondition$Serializer
+ XXX.loot.predicates.LootItemCondition
- XXX.loot.predicates.LootItemCondition$Builder
+ XXX.loot.predicates.LootItemCondition$Serializer
- XXX.loot.predicates.LootItemConditions
+ XXX.loot.predicates.LootItemConditions$Serializer
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
- XXX.metadata.animation.AnimationFrame
+ XXX.metadata.animation.AnimationMetadataSection
- XXX.metadata.animation.AnimationMetadataSection$1
+ XXX.metadata.animation.AnimationMetadataSectionSerializer
+ XXX.metadata.animation.package-info
- XXX.metadata.animation.VillagerMetaDataSection
+ XXX.metadata.animation.VillagerMetaDataSection$Hat
- XXX.metadata.animation.VillagerMetadataSectionSerializer
- XXX.metadata.language.LanguageMetadataSection
+ XXX.metadata.language.LanguageMetadataSectionSerializer
- XXX.metadata.language.package-info
- XXX.metadata.texture.package-info
- XXX.metadata.texture.TextureMetadataSection
+ XXX.metadata.texture.TextureMetadataSectionSerializer
- XXX.minecraft.advancements.Advancement
+ XXX.minecraft.advancements.Advancement$1
- XXX.minecraft.advancements.Advancement$Builder
+ XXX.minecraft.advancements.AdvancementList
- XXX.minecraft.advancements.AdvancementList$Listener
+ XXX.minecraft.advancements.AdvancementProgress
- XXX.minecraft.advancements.AdvancementProgress$Serializer
+ XXX.minecraft.advancements.AdvancementRewards
- XXX.minecraft.advancements.AdvancementRewards$Builder
+ XXX.minecraft.advancements.AdvancementRewards$Deserializer
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
- XXX.minecraft.client.CycleOption
+ XXX.minecraft.client.DebugQueryHandler
- XXX.minecraft.client.FullscreenResolutionProgressOption
+ XXX.minecraft.client.Game
- XXX.minecraft.client.Game$Metrics
+ XXX.minecraft.client.GuiMessage
- XXX.minecraft.client.HotbarManager
+ XXX.minecraft.client.KeyboardHandler
- XXX.minecraft.client.KeyboardHandler$1
+ XXX.minecraft.client.KeyMapping
- XXX.minecraft.client.KeyMapping$1
+ XXX.minecraft.client.LogaritmicProgressOption
- XXX.minecraft.client.Minecraft
+ XXX.minecraft.client.Minecraft$1
- XXX.minecraft.client.Minecraft$2
+ XXX.minecraft.client.MouseHandler
- XXX.minecraft.client.NarratorStatus
+ XXX.minecraft.client.Option
- XXX.minecraft.client.Options
+ XXX.minecraft.client.Options$1
- XXX.minecraft.client.Options$2
+ XXX.minecraft.client.ParticleStatus
- XXX.minecraft.client.ProgressOption
+ XXX.minecraft.client.RecipeBookCategories
- XXX.minecraft.client.Screenshot
+ XXX.minecraft.client.Session
- XXX.minecraft.client.Timer
+ XXX.minecraft.client.ToggleKeyMapping
- XXX.minecraft.client.User
+ XXX.minecraft.client.User$Type
+ XXX.minecraft.commands.BrigadierExceptions
- XXX.minecraft.commands.CommandFunction
+ XXX.minecraft.commands.CommandFunction$CacheableFunction
- XXX.minecraft.commands.CommandFunction$CommandEntry
+ XXX.minecraft.commands.CommandFunction$Entry
- XXX.minecraft.commands.CommandFunction$FunctionEntry
+ XXX.minecraft.commands.CommandRuntimeException
+ XXX.minecraft.commands.Commands
- XXX.minecraft.commands.Commands$ParseFunction
- XXX.minecraft.commands.CommandSource
+ XXX.minecraft.commands.CommandSource$1
- XXX.minecraft.commands.CommandSourceStack
- XXX.minecraft.commands.package-info
+ XXX.minecraft.commands.SharedSuggestionProvider
- XXX.minecraft.commands.SharedSuggestionProvider$TextCoordinates
+ XXX.minecraft.core.AxisCycle
- XXX.minecraft.core.AxisCycle$1
+ XXX.minecraft.core.AxisCycle$2
- XXX.minecraft.core.AxisCycle$3
+ XXX.minecraft.core.BlockMath
- XXX.minecraft.core.BlockPos
+ XXX.minecraft.core.BlockPos$1
- XXX.minecraft.core.BlockPos$2
+ XXX.minecraft.core.BlockPos$3
- XXX.minecraft.core.BlockPos$MutableBlockPos
+ XXX.minecraft.core.BlockPos$PooledMutableBlockPos
- XXX.minecraft.core.package-info
- XXX.minecraft.core.SerializableBoolean
+ XXX.minecraft.core.SerializableLong
- XXX.minecraft.core.SerializableUUID
+ XXX.minecraft.core.Source
- XXX.minecraft.core.Vec3i
+ XXX.minecraft.core.Vec3i$1
- XXX.minecraft.core.WritableRegistry
- XXX.minecraft.data.DataGenerator
+ XXX.minecraft.data.DataProvider
- XXX.minecraft.data.HashCache
+ XXX.minecraft.data.Main
+ XXX.minecraft.realms.AbstractRealmsButton
- XXX.minecraft.realms.DisconnectedRealmsScreen
+ XXX.minecraft.realms.DisconnectedRealmsScreen$1
+ XXX.minecraft.realms.Realms
+ XXX.minecraft.realms.RealmsAnvilLevelStorageSource
- XXX.minecraft.realms.RealmsBridge
+ XXX.minecraft.realms.RealmsButton
+ XXX.minecraft.realms.RealmsClickableScrolledSelectionList
+ XXX.minecraft.realms.RealmsConfirmResultListener
+ XXX.minecraft.realms.RealmsEditBox
+ XXX.minecraft.realms.RealmsLabel
+ XXX.minecraft.realms.RealmsLevelSummary
+ XXX.minecraft.realms.RealmsScreen
+ XXX.minecraft.realms.RealmsScrolledSelectionList
+ XXX.minecraft.realms.RealmsSimpleScrolledSelectionList
+ XXX.minecraft.realms.RealmsSliderButton
+ XXX.minecraft.realms.RealmsVertexFormat
+ XXX.minecraft.realms.RepeatedNarrator
- XXX.minecraft.realms.RepeatedNarrator$Params
+ XXX.minecraft.realms.Tezzelator
+ XXX.minecraft.recipebook.package-info
- XXX.minecraft.recipebook.PlaceRecipe
+ XXX.minecraft.recipebook.ServerPlaceRecipe
- XXX.minecraft.recipebook.ServerPlaceSmeltingRecipe
- XXX.minecraft.resources.package-info
- XXX.minecraft.resources.ResourceLocation
+ XXX.minecraft.resources.ResourceLocation$Serializer
+ XXX.minecraft.server.Bootstrap
- XXX.minecraft.server.ChainedJsonException
+ XXX.minecraft.server.ChainedJsonException$1
- XXX.minecraft.server.ChainedJsonException$Entry
+ XXX.minecraft.server.ConsoleInput
- XXX.minecraft.server.ConsoleInputSource
+ XXX.minecraft.server.DebugLoggedPrintStream
- XXX.minecraft.server.Eula
+ XXX.minecraft.server.LoggedPrintStream
- XXX.minecraft.server.MinecraftServer
+ XXX.minecraft.server.MinecraftServer$1
- XXX.minecraft.server.MinecraftServer$2
+ XXX.minecraft.server.MinecraftServer$3
- XXX.minecraft.server.PlayerAdvancements
+ XXX.minecraft.server.PlayerAdvancements$1
- XXX.minecraft.server.RunningOnDifferentThreadException
+ XXX.minecraft.server.ServerAdvancementManager
- XXX.minecraft.server.ServerFunctionManager
+ XXX.minecraft.server.ServerFunctionManager$QueuedCommand
- XXX.minecraft.server.ServerInterface
+ XXX.minecraft.server.ServerScoreboard
- XXX.minecraft.server.ServerScoreboard$Method
+ XXX.minecraft.server.TickTask
- XXX.minecraft.util.package-info
+ XXX.minecraft.world.BossEvent
- XXX.minecraft.world.BossEvent$BossBarColor
+ XXX.minecraft.world.BossEvent$BossBarOverlay
- XXX.minecraft.world.Clearable
+ XXX.minecraft.world.CompoundContainer
- XXX.minecraft.world.Container
+ XXX.minecraft.world.ContainerHelper
- XXX.minecraft.world.ContainerListener
+ XXX.minecraft.world.Containers
- XXX.minecraft.world.Difficulty
+ XXX.minecraft.world.DifficultyInstance
- XXX.minecraft.world.InteractionHand
+ XXX.minecraft.world.InteractionResult
- XXX.minecraft.world.InteractionResultHolder
+ XXX.minecraft.world.LockCode
- XXX.minecraft.world.MenuProvider
+ XXX.minecraft.world.Nameable
+ XXX.minecraft.world.package-info
- XXX.minecraft.world.ShulkerSharedHelper
+ XXX.minecraft.world.SimpleContainer
- XXX.minecraft.world.SimpleMenuProvider
+ XXX.minecraft.world.Snooper
- XXX.minecraft.world.Snooper$1
+ XXX.minecraft.world.SnooperPopulator
- XXX.minecraft.world.WorldlyContainer
+ XXX.minecraft.world.WorldlyContainerHolder
- XXX.models.blockstates.Condition
- XXX.models.blockstates.Condition$CompositeCondition
- XXX.models.blockstates.Condition$TerminalCondition
- XXX.models.blockstates.MultiPartGenerator$1
- XXX.models.blockstates.MultiPartGenerator$Entry
- XXX.models.blockstates.PropertyDispatch
- XXX.models.blockstates.PropertyDispatch$C1
- XXX.models.blockstates.PropertyDispatch$C3
- XXX.models.blockstates.PropertyDispatch$C5
- XXX.models.blockstates.PropertyDispatch$QuadFunction
- XXX.models.blockstates.PropertyValue
- XXX.models.blockstates.Variant
- XXX.models.blockstates.VariantProperties$Rotation
- XXX.models.blockstates.VariantProperty$Value
- XXX.models.model.DelegatedModel
- XXX.models.model.ModelTemplate
- XXX.models.model.package-info
- XXX.models.model.TexturedModel
- XXX.models.model.TextureMapping
+ XXX.mojang.realmsclient.RealmsMainScreen$10
+ XXX.mojang.realmsclient.RealmsMainScreen$12
- XXX.mojang.realmsclient.RealmsMainScreen$2
+ XXX.mojang.realmsclient.RealmsMainScreen$3
- XXX.mojang.realmsclient.RealmsMainScreen$4
+ XXX.mojang.realmsclient.RealmsMainScreen$5
+ XXX.mojang.realmsclient.RealmsMainScreen$7
+ XXX.mojang.realmsclient.RealmsMainScreen$9
- XXX.mojang.realmsclient.RealmsMainScreen$CloseButton
+ XXX.mojang.realmsclient.RealmsMainScreen$RealmSelectionListTrialEntry
- XXX.mojang.realmsclient.RealmsMainScreen$ShowPopupButton
- XXX.mojang.realmsclient.Unit
+ XXX.monster.hoglin.Hoglin
- XXX.monster.hoglin.HoglinAi
+ XXX.monster.hoglin.package-info
+ XXX.monster.piglin.Piglin
- XXX.monster.piglin.Piglin$PiglinArmPose
+ XXX.monster.piglin.PiglinAi
- XXX.monster.piglin.RememberIfHoglinWasKilled
- XXX.monster.piglin.StartHuntingHoglin
- XXX.monster.piglin.StopHoldingItemIfNoLongerAdmiring
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
+ XXX.placement.nether.ChanceRangeDecorator
- XXX.placement.nether.CountRangeDecorator
+ XXX.placement.nether.FireDecorator
- XXX.placement.nether.LightGemChanceDecorator
+ XXX.placement.nether.MagmaDecorator
+ XXX.placement.nether.package-info
- XXX.placement.nether.RandomCountRangeDecorator
+ XXX.realms.pluginapi.LoadedRealmsPlugin
+ XXX.realms.pluginapi.package-info
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
- XXX.realmsclient.dto.ReflectionBasedSerialization
+ XXX.realmsclient.dto.RegionPingResult
+ XXX.realmsclient.dto.ServerActivityList
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
+ XXX.realmsclient.gui.LongRunningTask
+ XXX.realmsclient.gui.RealmsWorldSlotButton$Listener
- XXX.realmsclient.gui.RealmsWorldSlotButton$State
+ XXX.realmsclient.gui.RowButton
+ XXX.realmsclient.util.RealmsPersistence$1
- XXX.realmsclient.util.RealmsPersistence$RealmsPersistenceData
+ XXX.realmsclient.util.RealmsTasks
+ XXX.realmsclient.util.RealmsTasks$DownloadTask
+ XXX.realmsclient.util.RealmsTasks$RealmsConnectTask
+ XXX.realmsclient.util.RealmsTasks$ResettingWorldTask
+ XXX.realmsclient.util.RealmsTasks$SwitchMinigameTask
+ XXX.realmsclient.util.RealmsTasks$WorldCreationTask
- XXX.resourcepacks.entries.package-info
+ XXX.resourcepacks.lists.AvailableResourcePackList
+ XXX.resourcepacks.lists.package-info
- XXX.resourcepacks.lists.ResourcePackList
+ XXX.resourcepacks.lists.ResourcePackList$ResourcePackEntry
- XXX.resourcepacks.lists.SelectedResourcePackList
+ XXX.resources.language.I18n
- XXX.resources.language.Language
+ XXX.resources.language.LanguageManager
- XXX.resources.language.Locale
+ XXX.resources.language.package-info
+ XXX.resources.metadata.package-info
+ XXX.resources.model.BakedModel
- XXX.resources.model.BlockModelRotation
+ XXX.resources.model.BuiltInModel
- XXX.resources.model.Material
+ XXX.resources.model.ModelBakery
- XXX.resources.model.ModelBakery$BlockStateDefinitionException
+ XXX.resources.model.ModelBakery$ModelGroupKey
- XXX.resources.model.ModelManager
+ XXX.resources.model.ModelResourceLocation
- XXX.resources.model.ModelState
+ XXX.resources.model.MultiPartBakedModel
- XXX.resources.model.MultiPartBakedModel$Builder
+ XXX.resources.model.package-info
+ XXX.resources.model.SimpleBakedModel
- XXX.resources.model.SimpleBakedModel$Builder
+ XXX.resources.model.UnbakedModel
- XXX.resources.model.WeightedBakedModel
+ XXX.resources.model.WeightedBakedModel$Builder
- XXX.resources.model.WeightedBakedModel$WeightedModel
+ XXX.resources.sounds.AbstractSoundInstance
- XXX.resources.sounds.AbstractTickableSoundInstance
+ XXX.resources.sounds.AmbientSoundHandler
- XXX.resources.sounds.BeeAggressiveSoundInstance
+ XXX.resources.sounds.BeeFlyingSoundInstance
- XXX.resources.sounds.BeeSoundInstance
- XXX.resources.sounds.BiomeAmbientSoundsHandler$LoopSoundInstance
+ XXX.resources.sounds.BubbleColumnAmbientSoundHandler
- XXX.resources.sounds.ElytraOnPlayerSoundInstance
+ XXX.resources.sounds.EntityBoundSoundInstance
- XXX.resources.sounds.GuardianAttackSoundInstance
+ XXX.resources.sounds.MinecartSoundInstance
+ XXX.resources.sounds.package-info
- XXX.resources.sounds.RidingMinecartSoundInstance
+ XXX.resources.sounds.SimpleSoundInstance
- XXX.resources.sounds.Sound
+ XXX.resources.sounds.Sound$Type
- XXX.resources.sounds.SoundEventRegistration
+ XXX.resources.sounds.SoundEventRegistrationSerializer
- XXX.resources.sounds.SoundInstance
+ XXX.resources.sounds.SoundInstance$Attenuation
- XXX.resources.sounds.TickableSoundInstance
+ XXX.resources.sounds.UnderwaterAmbientSoundHandler
- XXX.resources.sounds.UnderwaterAmbientSoundInstances
+ XXX.resources.sounds.UnderwaterAmbientSoundInstances$SubSound
- XXX.resources.sounds.UnderwaterAmbientSoundInstances$UnderwaterAmbientSoundInstance
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
+ XXX.screens.achievement.package-info
+ XXX.screens.achievement.StatsScreen
- XXX.screens.achievement.StatsScreen$1
+ XXX.screens.achievement.StatsScreen$GeneralStatisticsList
- XXX.screens.achievement.StatsScreen$GeneralStatisticsList$Entry
+ XXX.screens.achievement.StatsScreen$ItemStatisticsList
- XXX.screens.achievement.StatsScreen$ItemStatisticsList$ItemComparator
+ XXX.screens.achievement.StatsScreen$ItemStatisticsList$ItemRow
- XXX.screens.achievement.StatsScreen$MobsStatisticsList
+ XXX.screens.achievement.StatsScreen$MobsStatisticsList$MobRow
- XXX.screens.achievement.StatsUpdateListener
+ XXX.screens.advancements.AdvancementsScreen
- XXX.screens.advancements.AdvancementTab
+ XXX.screens.advancements.AdvancementTabType
- XXX.screens.advancements.AdvancementTabType$1
+ XXX.screens.advancements.AdvancementWidget
- XXX.screens.advancements.AdvancementWidgetType
- XXX.screens.advancements.package-info
+ XXX.screens.controls.ControlList
- XXX.screens.controls.ControlList$1
+ XXX.screens.controls.ControlList$CategoryEntry
- XXX.screens.controls.ControlList$Entry
+ XXX.screens.controls.ControlList$KeyEntry
- XXX.screens.controls.ControlList$KeyEntry$1
+ XXX.screens.controls.ControlList$KeyEntry$2
- XXX.screens.controls.ControlsScreen
+ XXX.screens.controls.package-info
- XXX.screens.inventory.AbstractCommandBlockEditScreen
+ XXX.screens.inventory.AbstractCommandBlockEditScreen$1
- XXX.screens.inventory.AbstractContainerScreen
+ XXX.screens.inventory.AbstractFurnaceScreen
- XXX.screens.inventory.AnvilScreen
+ XXX.screens.inventory.BeaconScreen
- XXX.screens.inventory.BeaconScreen$1
+ XXX.screens.inventory.BeaconScreen$BeaconCancelButton
- XXX.screens.inventory.BeaconScreen$BeaconConfirmButton
+ XXX.screens.inventory.BeaconScreen$BeaconPowerButton
- XXX.screens.inventory.BeaconScreen$BeaconScreenButton
+ XXX.screens.inventory.BeaconScreen$BeaconSpriteScreenButton
- XXX.screens.inventory.BlastFurnaceScreen
+ XXX.screens.inventory.BookEditScreen
- XXX.screens.inventory.BookEditScreen$Pos2i
+ XXX.screens.inventory.BookViewScreen
- XXX.screens.inventory.BookViewScreen$1
+ XXX.screens.inventory.BookViewScreen$BookAccess
- XXX.screens.inventory.BookViewScreen$WritableBookAccess
+ XXX.screens.inventory.BookViewScreen$WrittenBookAccess
- XXX.screens.inventory.BrewingStandScreen
+ XXX.screens.inventory.CartographyTableScreen
- XXX.screens.inventory.CommandBlockEditScreen
+ XXX.screens.inventory.CommandBlockEditScreen$1
- XXX.screens.inventory.ContainerScreen
+ XXX.screens.inventory.CraftingScreen
- XXX.screens.inventory.CreativeInventoryListener
+ XXX.screens.inventory.CreativeModeInventoryScreen
- XXX.screens.inventory.CreativeModeInventoryScreen$CustomCreativeSlot
+ XXX.screens.inventory.CreativeModeInventoryScreen$ItemPickerMenu
- XXX.screens.inventory.CreativeModeInventoryScreen$SlotWrapper
+ XXX.screens.inventory.DispenserScreen
- XXX.screens.inventory.EffectRenderingInventoryScreen
+ XXX.screens.inventory.EnchantmentNames
- XXX.screens.inventory.EnchantmentScreen
+ XXX.screens.inventory.FurnaceScreen
- XXX.screens.inventory.GrindstoneScreen
+ XXX.screens.inventory.HopperScreen
- XXX.screens.inventory.HorseInventoryScreen
+ XXX.screens.inventory.InventoryScreen
- XXX.screens.inventory.ItemCombinerScreen
- XXX.screens.inventory.package-info
- XXX.screens.inventory.SmithingScreen
+ XXX.screens.inventory.SmokerScreen
- XXX.screens.inventory.StonecutterScreen
+ XXX.screens.inventory.StructureBlockEditScreen
- XXX.screens.inventory.StructureBlockEditScreen$1
+ XXX.screens.inventory.StructureBlockEditScreen$2
+ XXX.screens.mco.package-info
- XXX.screens.multiplayer.JoinMultiplayerScreen
+ XXX.screens.multiplayer.package-info
+ XXX.screens.multiplayer.SafetyScreen
- XXX.screens.multiplayer.ServerSelectionList
+ XXX.screens.multiplayer.ServerSelectionList$Entry
- XXX.screens.multiplayer.ServerSelectionList$LANHeader
+ XXX.screens.multiplayer.ServerSelectionList$NetworkServerEntry
- XXX.screens.multiplayer.ServerSelectionList$OnlineServerEntry
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
- XXX.screens.resourcepacks.package-info
+ XXX.screens.resourcepacks.ResourcePackSelectScreen
+ XXX.screens.stream.package-info
- XXX.screens.worldselection.CreateWorldScreen
+ XXX.screens.worldselection.CreateWorldScreen$1
- XXX.screens.worldselection.CreateWorldScreen$2
+ XXX.screens.worldselection.CreateWorldScreen$3
- XXX.screens.worldselection.CreateWorldScreen$4
+ XXX.screens.worldselection.CreateWorldScreen$5
- XXX.screens.worldselection.CreateWorldScreen$6
+ XXX.screens.worldselection.CreateWorldScreen$7
- XXX.screens.worldselection.CreateWorldScreen$SelectedGameMode
+ XXX.screens.worldselection.EditWorldScreen
- XXX.screens.worldselection.OptimizeWorldScreen
- XXX.screens.worldselection.package-info
+ XXX.screens.worldselection.SelectWorldScreen
- XXX.screens.worldselection.WorldSelectionList
+ XXX.screens.worldselection.WorldSelectionList$WorldListEntry
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
+ XXX.server.commands.DeOpCommands
- XXX.spectator.categories.package-info
- XXX.spectator.categories.SpectatorPage
+ XXX.spectator.categories.TeleportToPlayerMenuCategory
- XXX.spectator.categories.TeleportToTeamMenuCategory
+ XXX.spectator.categories.TeleportToTeamMenuCategory$TeamSelectionItem
+ XXX.state.pattern.BlockInWorld
- XXX.state.pattern.BlockPattern
+ XXX.state.pattern.BlockPattern$BlockCacheLoader
- XXX.state.pattern.BlockPattern$BlockPatternMatch
+ XXX.state.pattern.BlockPattern$PortalInfo
- XXX.state.pattern.BlockPatternBuilder
+ XXX.state.pattern.package-info
- XXX.state.predicate.BlockMaterialPredicate
+ XXX.state.predicate.BlockMaterialPredicate$1
- XXX.state.predicate.BlockPredicate
+ XXX.state.predicate.BlockStatePredicate
- XXX.state.predicate.package-info
+ XXX.state.properties.AbstractProperty
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
+ XXX.state.properties.EnumProperty
- XXX.state.properties.Half
+ XXX.state.properties.IntegerProperty
- XXX.state.properties.NoteBlockInstrument
- XXX.state.properties.package-info
+ XXX.state.properties.PistonType
- XXX.state.properties.Property
+ XXX.state.properties.RailShape
- XXX.state.properties.RedstoneSide
+ XXX.state.properties.SlabType
- XXX.state.properties.StairsShape
+ XXX.state.properties.StructureMode
- XXX.state.properties.WallSide
+ XXX.state.properties.WoodType
+ XXX.storage.loot.BinomialDistributionGenerator
- XXX.storage.loot.BinomialDistributionGenerator$Serializer
+ XXX.storage.loot.BuiltInLootTables
- XXX.storage.loot.ConstantIntValue
+ XXX.storage.loot.ConstantIntValue$Serializer
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
- XXX.storage.loot.RandomIntGenerator
+ XXX.storage.loot.RandomIntGenerators
- XXX.storage.loot.RandomValueBounds
+ XXX.storage.loot.RandomValueBounds$Serializer
- XXX.storage.loot.ValidationContext
+ XXX.storage.threaded.package-info
- XXX.structure.templatesystem.AlwaysTrueTest
+ XXX.structure.templatesystem.BlockIgnoreProcessor
- XXX.structure.templatesystem.BlockMatchTest
+ XXX.structure.templatesystem.BlockRotProcessor
- XXX.structure.templatesystem.BlockStateMatchTest
+ XXX.structure.templatesystem.GravityProcessor
- XXX.structure.templatesystem.JigsawReplacementProcessor
+ XXX.structure.templatesystem.NopProcessor
- XXX.structure.templatesystem.package-info
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
- XXX.structure.templatesystem.StructureTemplate$SimplePalette
+ XXX.structure.templatesystem.StructureTemplate$StructureBlockInfo
- XXX.structure.templatesystem.StructureTemplate$StructureEntityInfo
+ XXX.structure.templatesystem.TagMatchTest
- XXX.synchronization.brigadier.BrigadierArgumentSerializers
+ XXX.synchronization.brigadier.DoubleArgumentSerializer
- XXX.synchronization.brigadier.FloatArgumentSerializer
+ XXX.synchronization.brigadier.IntegerArgumentSerializer
- XXX.synchronization.brigadier.LongArgumentSerializer
+ XXX.synchronization.brigadier.package-info
+ XXX.synchronization.brigadier.StringArgumentSerializer
- XXX.synchronization.brigadier.StringArgumentSerializer$1
- XXX.util.datafix.package-info
+ XXX.util.profiling.ActiveProfiler
- XXX.util.profiling.ActiveProfiler$1
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
- XXX.util.task.ConnectTask
- XXX.util.task.GetServerDetailsTask
- XXX.util.task.OpenServerTask
- XXX.util.task.RestoreTask
- XXX.util.task.SwitchSlotTask
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
- XXX.util.worldupdate.package-info
+ XXX.util.worldupdate.WorldUpgrader
- XXX.village.poi.package-info
- XXX.village.poi.PoiManager
+ XXX.village.poi.PoiManager$DistanceTracker
- XXX.village.poi.PoiManager$Occupancy
+ XXX.village.poi.PoiRecord
- XXX.village.poi.PoiSection
+ XXX.village.poi.PoiType
- XXX.world.damagesource.CombatEntry
+ XXX.world.damagesource.CombatRules
- XXX.world.damagesource.CombatTracker
+ XXX.world.damagesource.DamageSource
- XXX.world.damagesource.EntityDamageSource
+ XXX.world.damagesource.IndirectEntityDamageSource
- XXX.world.damagesource.NetherBedDamage
+ XXX.world.damagesource.package-info
- XXX.world.effect.AbsoptionMobEffect
+ XXX.world.effect.AttackDamageMobEffect
- XXX.world.effect.HealthBoostMobEffect
+ XXX.world.effect.InstantenousMobEffect
- XXX.world.effect.MobEffect
+ XXX.world.effect.MobEffectCategory
- XXX.world.effect.MobEffectInstance
- XXX.world.effect.MobEffects
+ XXX.world.effect.MobEffects$1
+ XXX.world.effect.MobEffectUtil
- XXX.world.effect.package-info
+ XXX.world.entity.AgableMob
- XXX.world.entity.AgableMob$AgableMobGroupData
+ XXX.world.entity.AreaEffectCloud
- XXX.world.entity.Entity
+ XXX.world.entity.Entity$1
- XXX.world.entity.Entity$MoveCallback
+ XXX.world.entity.EntityDimensions
- XXX.world.entity.EntityEvent
+ XXX.world.entity.EntitySelector
- XXX.world.entity.EntitySelector$MobCanWearArmourEntitySelector
+ XXX.world.entity.EntityType
- XXX.world.entity.EntityType$Builder
+ XXX.world.entity.EntityType$EntityFactory
- XXX.world.entity.EquipmentSlot
+ XXX.world.entity.EquipmentSlot$Type
- XXX.world.entity.ExperienceOrb
+ XXX.world.entity.FlyingMob
- XXX.world.entity.HumanoidArm
+ XXX.world.entity.LivingEntity
- XXX.world.entity.LivingEntity$1
+ XXX.world.entity.Mob
- XXX.world.entity.Mob$1
+ XXX.world.entity.MobCategory
- XXX.world.entity.MobSpawnType
+ XXX.world.entity.MobType
- XXX.world.entity.MoverType
+ XXX.world.entity.OwnableEntity
- XXX.world.entity.PathfinderMob
+ XXX.world.entity.PlayerRideable
- XXX.world.entity.PlayerRideableJumping
+ XXX.world.entity.Pose
- XXX.world.entity.PowerableMob
+ XXX.world.entity.ReputationEventHandler
- XXX.world.entity.SpawnGroupData
+ XXX.world.entity.SpawnPlacements
- XXX.world.entity.SpawnPlacements$Data
+ XXX.world.entity.SpawnPlacements$SpawnPredicate
- XXX.world.entity.SpawnPlacements$Type
+ XXX.world.entity.TamableAnimal
+ XXX.world.inventory.AnvilMenu$2
- XXX.world.inventory.ItemCombinerMenu$1
- XXX.world.inventory.LecternMenu
+ XXX.world.inventory.LecternMenu$1
- XXX.world.inventory.LoomMenu
+ XXX.world.inventory.LoomMenu$1
- XXX.world.inventory.LoomMenu$2
+ XXX.world.inventory.LoomMenu$3
- XXX.world.inventory.LoomMenu$4
+ XXX.world.inventory.LoomMenu$5
- XXX.world.inventory.LoomMenu$6
+ XXX.world.inventory.MenuConstructor
- XXX.world.inventory.MenuType
+ XXX.world.inventory.MenuType$MenuSupplier
- XXX.world.inventory.MerchantContainer
+ XXX.world.inventory.MerchantMenu
- XXX.world.inventory.MerchantResultSlot
+ XXX.world.inventory.PlayerEnderChestContainer
- XXX.world.inventory.RecipeBookMenu
+ XXX.world.inventory.RecipeHolder
- XXX.world.inventory.ResultContainer
+ XXX.world.inventory.ResultSlot
- XXX.world.inventory.ShulkerBoxMenu
+ XXX.world.inventory.ShulkerBoxSlot
- XXX.world.inventory.SimpleContainerData
+ XXX.world.inventory.Slot
- XXX.world.inventory.SmithingMenu
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
XXX.blaze3d.vertex.VertexFormatElement -2M
```
```
XXX.mojang.realmsclient.RealmsMainScreen +95M -59M | +31P -14P
```
```
XXX.mojang.realmsclient.RealmsMainScreen$NewsButton +1M -3M
```
```
XXX.mojang.realmsclient.RealmsMainScreen$RealmSelectionList +2M
```
```
XXX.realmsclient.dto.RealmsServerPlayerList +1P -1P
```
```
XXX.realmsclient.dto.RealmsWorldOptions +2M -2M | +1P -13P
```
```
XXX.realmsclient.gui.RealmsDataFetcher +8M -10M | +5P -5P
```
```
XXX.realmsclient.gui.RealmsWorldSlotButton +4M -3M | +5P -1P
```
```
XXX.gui.screens.RealmsBackupScreen +22M -15M | +5P -3P
```
```
XXX.gui.screens.RealmsBackupScreen$BackupObjectSelectionList +2M -1M
```
```
XXX.gui.screens.RealmsBrokenWorldScreen +14M -10M | +3P -9P
```
```
XXX.gui.screens.RealmsGenericErrorScreen +4M -5M | +1P -1P
```
```
XXX.gui.screens.RealmsLongRunningMcoTaskScreen +4M -3M | +3P -6P
```
```
XXX.gui.screens.RealmsPlayerScreen +23M -17M | +9P -5P
```
```
XXX.gui.screens.RealmsResetWorldScreen +15M -16M | +10P -5P
```
```
XXX.gui.screens.RealmsResetWorldScreen$2 +1M -3M | +2P -1P
```
```
XXX.gui.screens.RealmsScreenWithCallback +1P -1P
```
```
XXX.gui.screens.RealmsSelectWorldTemplateScreen +31M -15M | +6P -3P
```
```
XXX.gui.screens.RealmsSettingsScreen +4M -3M | +3P -4P
```
```
XXX.gui.screens.RealmsUploadScreen +6M -10M | +6P -6P
```
```
XXX.realmsclient.util.RealmsUtil +2M -2M | +2P -2P
```
```
XXX.realmsclient.util.UploadTokenCache +1P -1P
```
```
XXX.gui.components.AbstractSelectionList -1P
```
```
XXX.gui.components.AbstractSliderButton +1M -2M | -1P
```
```
XXX.client.model.HumanoidModel -1P
```
```
XXX.client.multiplayer.ClientLevel -1M | -1P
```
```
XXX.renderer.entity.AbstractZombieRenderer +2M -2M
```
```
XXX.renderer.entity.LivingEntityRenderer +1M
```
```
XXX.renderer.entity.PiglinRenderer +2M -2M
```
```
XXX.renderer.entity.ZombieVillagerRenderer +2M -2M
```
```
XXX.client.resources.ClientPackSource +10M -5M
```
```
XXX.minecraft.nbt.CompoundTag +3M
```
```
XXX.minecraft.nbt.NbtUtils +2M
```
```
XXX.minecraft.realms.RealmsConnect$1 +3M -1M | +1P
```
```
XXX.minecraft.realms.RealmsObjectSelectionList +3M -19M | -2P
```
```
XXX.server.level.ServerChunkCache +1M -1M
```
```
XXX.server.players.StoredUserList +1M
```
```
XXX.minecraft.stats.Stats +1P
```
```
XXX.ai.behavior.MeleeAttack +1M -6M | +1P -2P
```
```
XXX.entity.projectile.AbstractArrow +1M -3M | -1P
```
```
XXX.entity.projectile.AbstractHurtingProjectile -1M | -2P
```
```
XXX.entity.projectile.FireworkRocketEntity +4M -4M
```
```
XXX.entity.projectile.LargeFireball +1M
```
```
XXX.entity.projectile.Projectile +11M | +1P -2P
```
```
XXX.entity.projectile.Snowball +1M
```
```
XXX.entity.projectile.ThrownEgg +1M
```
```
XXX.world.inventory.AnvilMenu +4M -9M | -4P
```
```
XXX.world.item.HoeItem +2M -8M | +1P -1P
```
```
XXX.world.level.EntityGetter -1M
```
```
XXX.world.level.Level -1M
```
```
XXX.world.level.NaturalSpawner +7M -1M
```
```
XXX.level.biome.BiomeManager +2M -1M
```
```
XXX.level.block.Block +1M -1M
```
```
XXX.level.block.ChorusFlowerBlock +1M -1M
```
```
XXX.level.block.FireBlock +2M
```

</details>
<details>
<summary>
com.mojang.blaze3d.vertex.VertexFormatElement
</summary>

```diff
+ boolean isPosition()
+ int getCount()
```

</details>
<details>
<summary>
com.mojang.realmsclient.RealmsMainScreen
</summary>

```diff
+ boolean access$1102(boolean)
+ boolean access$1302(boolean)
- boolean access$1602(boolean)
+ boolean access$2100(RealmsMainScreen)
+ boolean access$2102(RealmsMainScreen,boolean)
+ boolean access$2300(RealmsMainScreen,RealmsServer)
+ boolean access$2400(RealmsMainScreen)
+ boolean access$2402(RealmsMainScreen,boolean)
+ boolean access$3000()
- boolean access$3100(RealmsMainScreen)
- boolean access$3102(RealmsMainScreen,boolean)
- boolean access$3500(RealmsMainScreen,RealmsServer)
+ boolean access$400(RealmsMainScreen)
- boolean access$4900()
- boolean access$602(boolean)
- boolean access$7000(RealmsMainScreen)
- boolean access$7002(RealmsMainScreen,boolean)
- boolean lambda$updateTeaserImages$12(String)
- boolean lambda$updateTeaserImages$13(ResourceLocation)
+ boolean lambda$updateTeaserImages$6(String)
+ boolean lambda$updateTeaserImages$7(ResourceLocation)
- Button access$2600(RealmsMainScreen)
- Font access$3900(RealmsMainScreen)
- Font access$4400(RealmsMainScreen)
- Font access$5200(RealmsMainScreen)
- Font access$5300(RealmsMainScreen)
- Font access$5400(RealmsMainScreen)
- Font access$5700(RealmsMainScreen)
- Font access$5800(RealmsMainScreen)
- Font access$5900(RealmsMainScreen)
- Font access$6000(RealmsMainScreen)
- Font access$6100(RealmsMainScreen)
- Font access$6200(RealmsMainScreen)
- Font access$6300(RealmsMainScreen)
- Font access$6400(RealmsMainScreen)
- Font access$6500(RealmsMainScreen)
- Font access$6600(RealmsMainScreen)
+ int access$2000(RealmsMainScreen)
+ int access$2002(RealmsMainScreen,int)
+ int access$2500(RealmsMainScreen)
- int access$3000(RealmsMainScreen)
- int access$3002(RealmsMainScreen,int)
+ int access$3300(RealmsMainScreen)
+ int access$3900(RealmsMainScreen)
+ int access$4000(RealmsMainScreen)
- int access$4300(RealmsMainScreen)
- int access$6700(RealmsMainScreen)
- int access$7400(RealmsMainScreen)
- int access$7500(RealmsMainScreen)
+ List access$1600(RealmsMainScreen)
- List access$2300(RealmsMainScreen)
+ Logger access$1200()
- Logger access$700()
+ long access$000(RealmsMainScreen)
+ long access$002(RealmsMainScreen,long)
- long access$2100(RealmsMainScreen)
- long access$2102(RealmsMainScreen,long)
- Minecraft access$1000(RealmsMainScreen)
- Minecraft access$1100(RealmsMainScreen)
- Minecraft access$1200(RealmsMainScreen)
- Minecraft access$1300(RealmsMainScreen)
- Minecraft access$1500(RealmsMainScreen)
- Minecraft access$1700(RealmsMainScreen)
- Minecraft access$1800(RealmsMainScreen)
- Minecraft access$1900(RealmsMainScreen)
- Minecraft access$2700(RealmsMainScreen)
- Minecraft access$2800(RealmsMainScreen)
- Minecraft access$300(RealmsMainScreen)
- Minecraft access$400(RealmsMainScreen)
- Minecraft access$4000(RealmsMainScreen)
- Minecraft access$4200(RealmsMainScreen)
- Minecraft access$5600(RealmsMainScreen)
- Minecraft access$7700(RealmsMainScreen)
- Minecraft access$800(RealmsMainScreen)
- Minecraft access$900(RealmsMainScreen)
+ RealmsButton access$1900(RealmsMainScreen)
+ RealmsDataFetcher access$1500()
- RealmsDataFetcher access$2000()
+ RealmsMainScreen$RealmSelectionList access$1700(RealmsMainScreen)
- RealmsMainScreen$RealmSelectionList access$2400(RealmsMainScreen)
+ RealmsScreen access$500(RealmsMainScreen)
+ RealmsScreen access$900()
+ RealmsScreen access$902(RealmsScreen)
+ RealmsServer access$100(RealmsMainScreen,long)
- RealmsServer access$2200(RealmsMainScreen,long)
- ResourceLocation access$4100()
- ResourceLocation access$5500()
- ResourceLocation access$7600()
- Screen access$100()
- Screen access$102(Screen)
- Screen access$200(RealmsMainScreen)
+ String access$2200(RealmsMainScreen)
+ String access$2202(RealmsMainScreen,String)
- String access$3200(RealmsMainScreen)
- String access$3202(RealmsMainScreen,String)
+ String access$3500(RealmsMainScreen)
- String access$7200(RealmsMainScreen)
+ void <init>(RealmsScreen)
- void <init>(Screen)
+ void access$1000(RealmsMainScreen)
+ void access$1800(RealmsMainScreen,RealmsServer)
+ void access$200(RealmsMainScreen,RealmsServer)
- void access$2500(RealmsMainScreen,RealmsServer)
+ void access$2600(RealmsMainScreen,int,int,int,int)
+ void access$2700(RealmsMainScreen,int,int,int,int)
+ void access$2800(RealmsMainScreen,int,int,int,int,int)
+ void access$2900(RealmsMainScreen,int,int,int,int)
+ void access$300(RealmsMainScreen)
+ void access$3100(RealmsMainScreen,int,int,int,int)
+ void access$3200(RealmsMainScreen,int,int,int,int)
- void access$3300(RealmsMainScreen,RealmsServer)
+ void access$3400(RealmsMainScreen,int,int,int,int,boolean,boolean)
- void access$3400(RealmsMainScreen,RealmsServer)
+ void access$3700(RealmsMainScreen,int,int,boolean,int,int,boolean,boolean)
- void access$3700(RealmsMainScreen)
+ void access$3800(RealmsMainScreen,int,int,int,int,boolean)
+ void access$4100(RealmsMainScreen)
- void access$4500(RealmsMainScreen,int,int,int,int)
- void access$4600(RealmsMainScreen,int,int,int,int)
- void access$4700(RealmsMainScreen,int,int,int,int,int)
- void access$4800(RealmsMainScreen,int,int,int,int)
- void access$500(RealmsMainScreen)
- void access$5000(RealmsMainScreen,int,int,int,int)
- void access$5100(RealmsMainScreen,int,int,int,int)
+ void access$600(RealmsMainScreen)
- void access$6800(RealmsMainScreen,int,int,int,int,boolean,boolean)
- void access$6900(RealmsMainScreen,Button)
+ void access$700(RealmsMainScreen,RealmsServer)
- void access$7100(RealmsMainScreen,int,int,boolean,int,int,boolean,boolean)
- void access$7300(RealmsMainScreen,int,int,int,int,boolean)
- void access$7800(RealmsMainScreen)
+ void access$800(RealmsMainScreen)
+ void browseURL(String)
+ void confirmResult(boolean,int)
+ void connectToServer(RealmsServer,RealmsScreen)
+ void createTrial()
- void lambda$addButtons$3(Button)
- void lambda$addButtons$4(Button)
- void lambda$addButtons$5(Button)
- void lambda$addButtons$6(Button)
- void lambda$addButtons$7(Button)
- void lambda$addButtons$8(Button)
- void lambda$addButtons$9(Button)
- void lambda$charTyped$11(char,KeyCombo)
+ void lambda$charTyped$5(char,KeyCombo)
+ void lambda$configureClicked$4(Minecraft,RealmsServer)
- void lambda$pingRegions$10()
+ void lambda$pingRegions$3()
- void leaveServer(boolean)
+ void onPlay()
- void pendingButtonPress(Button)
+ void play(RealmsServer,RealmsScreen)
- void play(RealmsServer,Screen)
+ void postInit()
```

</details>
<details>
<summary>
com.mojang.realmsclient.RealmsMainScreen$NewsButton
</summary>

```diff
- void lambda$new$0(RealmsMainScreen,Button)
+ void onPress()
+ void render(int,int,float)
+ void tick()
```

</details>
<details>
<summary>
com.mojang.realmsclient.RealmsMainScreen$RealmSelectionList
</summary>

```diff
- void setSelected(AbstractSelectionList$Entry)
- void setSelected(RealmsMainScreen$Entry)
```

</details>
<details>
<summary>
com.mojang.realmsclient.dto.RealmsWorldOptions
</summary>

```diff
- RealmsWorldOptions createDefaults()
- RealmsWorldOptions createEmptyDefaults()
+ RealmsWorldOptions getDefaults()
+ RealmsWorldOptions getEmptyDefaults()
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.RealmsDataFetcher
</summary>

```diff
- boolean access$1002(RealmsDataFetcher,boolean)
+ boolean access$1102(RealmsDataFetcher,boolean)
- boolean access$1202(RealmsDataFetcher,boolean)
+ boolean access$1302(RealmsDataFetcher,boolean)
+ int access$1002(RealmsDataFetcher,int)
- int access$902(RealmsDataFetcher,int)
- Logger access$800()
+ Logger access$900()
- Map access$700(RealmsDataFetcher)
+ Map access$800(RealmsDataFetcher)
- RealmsServerPlayerLists access$1102(RealmsDataFetcher,RealmsServerPlayerLists)
+ RealmsServerPlayerLists access$1202(RealmsDataFetcher,RealmsServerPlayerLists)
- String access$1302(RealmsDataFetcher,String)
+ String access$1402(RealmsDataFetcher,String)
+ void access$700(RealmsDataFetcher,List)
- void initWithSpecificTaskList()
+ void initWithSpecificTaskList(List)
+ void sort(List)
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.RealmsWorldSlotButton
</summary>

```diff
- RealmsWorldSlotButton$State getState()
- void <clinit>()
- void <init>(int,int,int,int,Supplier,Consumer,int,Button$OnPress)
+ void <init>(int,int,int,int,Supplier,Consumer,int,int,RealmsWorldSlotButton$Listener)
- void handleNarration(RealmsServer,String,boolean,boolean,RealmsWorldSlotButton$Action,String)
+ void onPress()
+ void render(int,int,float)
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsBackupScreen
</summary>

```diff
+ Boolean access$302(RealmsBackupScreen,Boolean)
- Boolean access$402(RealmsBackupScreen,Boolean)
- Font access$1100(RealmsBackupScreen)
- Font access$1200(RealmsBackupScreen)
+ int access$1002(int)
+ int access$700(RealmsBackupScreen)
- int access$802(int)
+ List access$200(RealmsBackupScreen)
+ List access$202(RealmsBackupScreen,List)
- List access$300(RealmsBackupScreen)
- List access$302(RealmsBackupScreen,List)
+ Logger access$100()
- Logger access$200()
- Minecraft access$100(RealmsBackupScreen)
- Minecraft access$1400(RealmsBackupScreen)
- Minecraft access$1700(RealmsBackupScreen)
+ RealmsBackupScreen$BackupObjectSelectionList access$400(RealmsBackupScreen)
- RealmsBackupScreen$BackupObjectSelectionList access$500(RealmsBackupScreen)
+ RealmsConfigureWorldScreen access$900(RealmsBackupScreen)
- ResourceLocation access$1300()
- ResourceLocation access$1600()
+ String access$1202(RealmsBackupScreen,String)
- String access$1502(RealmsBackupScreen,String)
- void access$1000(RealmsBackupScreen)
+ void access$1100(RealmsBackupScreen)
+ void access$500(RealmsBackupScreen)
+ void access$800(RealmsBackupScreen,int)
- void access$900(RealmsBackupScreen,int)
+ void confirmResult(boolean,int)
- void lambda$downloadClicked$5(boolean)
- void lambda$init$0(Button)
- void lambda$init$1(Button)
- void lambda$init$2(Button)
- void lambda$init$3(Button)
- void lambda$restoreClicked$4(boolean)
+ void postInit()
+ void tick()
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsBackupScreen$BackupObjectSelectionList
</summary>

```diff
+ int getItemCount()
- void setSelected(AbstractSelectionList$Entry)
- void setSelected(RealmsBackupScreen$Entry)
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsBrokenWorldScreen
</summary>

```diff
+ List access$100()
+ List access$300()
+ RealmsServer access$200(RealmsBrokenWorldScreen)
+ void <init>(RealmsScreen,RealmsMainScreen,long)
- void <init>(Screen,RealmsMainScreen,long)
+ void access$000(RealmsBrokenWorldScreen)
+ void access$400(RealmsBrokenWorldScreen,int)
+ void confirmResult(boolean,int)
- void doSwitchOrReset()
- void lambda$addButtons$2(int,Button)
- void lambda$addButtons$4(int,Button)
- void lambda$addButtons$6(int,Button)
+ void lambda$confirmResult$1()
- void lambda$doSwitchOrReset$10()
- void lambda$downloadWorld$11(int,boolean)
+ void lambda$fetchServerData$0(long)
- void lambda$fetchServerData$7(long)
- void lambda$init$0(Button)
- void lambda$null$1()
- void lambda$null$3(int,boolean)
- void lambda$null$5()
- void lambda$null$8()
- void lambda$null$9()
+ void switchSlot(int)
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsGenericErrorScreen
</summary>

```diff
+ RealmsScreen access$000(RealmsGenericErrorScreen)
+ void <init>(RealmsServiceException,RealmsScreen)
- void <init>(RealmsServiceException,Screen)
+ void <init>(String,RealmsScreen)
- void <init>(String,Screen)
+ void <init>(String,String,RealmsScreen)
- void <init>(String,String,Screen)
- void lambda$init$0(Button)
+ void tick()
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsLongRunningMcoTaskScreen
</summary>

```diff
+ void <init>(RealmsScreen,LongRunningTask)
- void <init>(Screen,LongRunningTask)
+ void access$000(RealmsLongRunningMcoTaskScreen)
- void buttonsClear()
- void lambda$error$1(Button)
- void lambda$init$0(Button)
+ void start()
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsPlayerScreen
</summary>

```diff
- Font access$1200(RealmsPlayerScreen)
- Font access$1800(RealmsPlayerScreen)
- int access$000(RealmsPlayerScreen)
- int access$100(int)
- int access$1002(RealmsPlayerScreen,int)
+ int access$1400(RealmsPlayerScreen)
- int access$1600(RealmsPlayerScreen)
- int access$1700(int)
- int access$200(int)
+ int access$200(RealmsPlayerScreen)
+ int access$202(RealmsPlayerScreen,int)
- int access$300(int)
- int access$400(RealmsPlayerScreen)
+ int access$700(RealmsPlayerScreen)
+ int access$800(RealmsPlayerScreen)
+ RealmsConfigureWorldScreen access$000(RealmsPlayerScreen)
+ RealmsServer access$100(RealmsPlayerScreen)
- RealmsServer access$500(RealmsPlayerScreen)
- String access$600(RealmsPlayerScreen)
+ String access$900(RealmsPlayerScreen)
+ void access$1000(RealmsPlayerScreen)
+ void access$1100(RealmsPlayerScreen,int,int,int,int)
- void access$1100(RealmsPlayerScreen)
+ void access$1200(RealmsPlayerScreen,int,int,int,int)
- void access$1400(RealmsPlayerScreen,int,int,int,int)
- void access$1500(RealmsPlayerScreen,int,int,int,int)
+ void access$300(RealmsPlayerScreen,int)
+ void access$400(RealmsPlayerScreen,int)
+ void access$500(RealmsPlayerScreen,int)
+ void access$600(RealmsPlayerScreen)
- void access$700(RealmsPlayerScreen,int)
- void access$800(RealmsPlayerScreen,int)
- void access$900(RealmsPlayerScreen,int)
+ void confirmResult(boolean,int)
- void lambda$init$0(Button)
- void lambda$init$1(Button)
- void lambda$init$2(Button)
- void lambda$init$3(Button)
- void lambda$uninvite$4(boolean)
+ void tick()
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsResetWorldScreen
</summary>

```diff
+ boolean mouseClicked(double,double,int)
- Minecraft access$000(RealmsResetWorldScreen)
+ RealmsScreen access$000(RealmsResetWorldScreen)
+ RealmsServer access$700(RealmsResetWorldScreen)
+ String access$600(RealmsResetWorldScreen)
+ void <init>(RealmsScreen,RealmsServer,RealmsScreen,String,String,int,String)
+ void <init>(RealmsScreen,RealmsServer,RealmsScreen)
- void <init>(Screen,RealmsServer,Runnable,Runnable)
- void <init>(Screen,RealmsServer,String,String,int,String,Runnable,Runnable)
+ void access$800(RealmsResetWorldScreen,int,int,String,long,String,RealmsResetWorldScreen$ResetType,boolean,boolean)
- void access$900(RealmsResetWorldScreen,int,int,String,ResourceLocation,boolean,boolean)
+ void callback(Object)
+ void confirmResult(boolean,int)
+ void drawFrame(int,int,String,long,String,RealmsResetWorldScreen$ResetType,boolean,boolean)
- void drawFrame(int,int,String,ResourceLocation,boolean,boolean)
- void lambda$init$0(Button)
- void lambda$init$1(Button)
- void lambda$init$2(Button)
- void lambda$init$3(Button)
- void lambda$init$4(Button)
- void lambda$init$5(Button)
- void lambda$init$6(Button)
- void lambda$switchSlot$7()
- void resetWorld(String,WorldTemplate,int,boolean)
+ void setConfirmationId(int)
+ void switchSlot(RealmsScreen)
- void switchSlot(Runnable)
+ WorldTemplatePaginatedList access$200(RealmsResetWorldScreen)
+ WorldTemplatePaginatedList access$300(RealmsResetWorldScreen)
+ WorldTemplatePaginatedList access$400(RealmsResetWorldScreen)
+ WorldTemplatePaginatedList access$500(RealmsResetWorldScreen)
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsResetWorldScreen$2
</summary>

```diff
- void <clinit>()
+ void <init>(RealmsResetWorldScreen,String)
+ void lambda$run$0(WorldTemplatePaginatedList,WorldTemplatePaginatedList,WorldTemplatePaginatedList,WorldTemplatePaginatedList)
+ void run()
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsSelectWorldTemplateScreen
</summary>

```diff
- boolean access$500(RealmsSelectWorldTemplateScreen)
+ boolean access$800(RealmsSelectWorldTemplateScreen)
- boolean hasValidTemplate()
- Either access$000(RealmsSelectWorldTemplateScreen,WorldTemplatePaginatedList,RealmsClient)
+ Either access$400(RealmsSelectWorldTemplateScreen,WorldTemplatePaginatedList,RealmsClient)
- Font access$1300(RealmsSelectWorldTemplateScreen)
- Font access$1400(RealmsSelectWorldTemplateScreen)
- Font access$1500(RealmsSelectWorldTemplateScreen)
- Font access$1600(RealmsSelectWorldTemplateScreen)
- Font access$1900(RealmsSelectWorldTemplateScreen)
- Font access$2000(RealmsSelectWorldTemplateScreen)
+ int access$1200(RealmsSelectWorldTemplateScreen)
+ int access$1202(RealmsSelectWorldTemplateScreen,int)
- int access$600(int)
- int access$800(RealmsSelectWorldTemplateScreen)
- int access$802(RealmsSelectWorldTemplateScreen,int)
+ int lambda$renderMultilineMessage$0(TextRenderingUtils$LineSegment)
- int lambda$renderMultilineMessage$4(TextRenderingUtils$LineSegment)
- List access$402(RealmsSelectWorldTemplateScreen,List)
+ List access$702(RealmsSelectWorldTemplateScreen,List)
- Logger access$200()
+ Logger access$500()
- Minecraft access$100(RealmsSelectWorldTemplateScreen)
- Minecraft access$1800(RealmsSelectWorldTemplateScreen)
- Minecraft access$2200(RealmsSelectWorldTemplateScreen)
- Minecraft access$2400(RealmsSelectWorldTemplateScreen)
- RealmsSelectWorldTemplateScreen$WorldTemplateObjectSelectionList access$300(RealmsSelectWorldTemplateScreen)
+ RealmsSelectWorldTemplateScreen$WorldTemplateObjectSelectionList access$600(RealmsSelectWorldTemplateScreen)
- ResourceLocation access$1700()
- ResourceLocation access$2100()
- ResourceLocation access$2300()
+ String access$1302(RealmsSelectWorldTemplateScreen,String)
- String access$2502(RealmsSelectWorldTemplateScreen,String)
- String access$700(RealmsSelectWorldTemplateScreen)
- String access$702(RealmsSelectWorldTemplateScreen,String)
+ String access$900(RealmsSelectWorldTemplateScreen)
+ String access$902(RealmsSelectWorldTemplateScreen,String)
+ void access$000(RealmsSelectWorldTemplateScreen)
+ void access$100(RealmsSelectWorldTemplateScreen)
+ void access$200(RealmsSelectWorldTemplateScreen)
+ void access$300(RealmsSelectWorldTemplateScreen)
- void access$900(RealmsSelectWorldTemplateScreen)
- void lambda$init$0(Button)
- void lambda$init$1(Button)
- void lambda$init$2(Button)
- void lambda$init$3(Button)
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsSettingsScreen
</summary>

```diff
+ RealmsConfigureWorldScreen access$000(RealmsSettingsScreen)
+ RealmsServer access$100(RealmsSettingsScreen)
+ void confirmResult(boolean,int)
- void lambda$init$0(Button)
- void lambda$init$1(Button)
- void lambda$init$3(Button)
- void lambda$null$2(boolean)
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsUploadScreen
</summary>

```diff
+ double convertToUnit(long,RealmsUploadScreen$Unit)
+ RealmsUploadScreen$Unit getLargestUnit(long)
+ String humanReadableByteCount(long)
+ String humanReadableSize(long,RealmsUploadScreen$Unit)
- void <init>(long,int,RealmsResetWorldScreen,LevelSummary,Runnable)
+ void <init>(long,int,RealmsResetWorldScreen,RealmsLevelSummary)
+ void access$000(RealmsUploadScreen)
+ void access$100(RealmsUploadScreen)
+ void confirmResult(boolean,int)
- void lambda$init$0(Button)
- void lambda$init$1(Button)
- void lambda$init$2()
+ void lambda$null$0(long,UploadResult)
- void lambda$null$3(long,UploadResult)
+ void lambda$upload$1()
- void lambda$upload$4()
```

</details>
<details>
<summary>
com.mojang.realmsclient.util.RealmsUtil
</summary>

```diff
- String convertToAgePresentation(long)
+ String convertToAgePresentation(Long)
- String convertToAgePresentationFromInstant(Date)
+ void browseTo(String)
```

</details>
<details>
<summary>
net.minecraft.client.gui.components.AbstractSliderButton
</summary>

```diff
+ void <init>(int,int,int,int,double)
- void <init>(int,int,int,int,String,double)
+ void <init>(Options,int,int,int,int,double)
```

</details>
<details>
<summary>
net.minecraft.client.multiplayer.ClientLevel
</summary>

```diff
+ void playMoodSounds()
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.AbstractZombieRenderer
</summary>

```diff
- boolean isShaking(LivingEntity)
- boolean isShaking(Zombie)
+ void setupRotations(LivingEntity,PoseStack,float,float,float)
+ void setupRotations(Zombie,PoseStack,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.LivingEntityRenderer
</summary>

```diff
- boolean isShaking(LivingEntity)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.PiglinRenderer
</summary>

```diff
- boolean isShaking(LivingEntity)
- boolean isShaking(Mob)
+ void setupRotations(LivingEntity,PoseStack,float,float,float)
+ void setupRotations(Mob,PoseStack,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.ZombieVillagerRenderer
</summary>

```diff
- boolean isShaking(LivingEntity)
- boolean isShaking(ZombieVillager)
+ void setupRotations(LivingEntity,PoseStack,float,float,float)
+ void setupRotations(ZombieVillager,PoseStack,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.resources.ClientPackSource
</summary>

```diff
- boolean addProgrammerArtPack(Map,UnopenedPack$UnopenedPackConstructor,Supplier)
- CompletionStage lambda$downloadAndSelectResourcePack$2(String,File,Object)
+ CompletionStage lambda$downloadAndSelectResourcePack$3(String,File,Object)
- FolderResourcePack createProgrammerArtDirPack(File)
- Pack createProgrammerArtZipPack(File)
- Pack lambda$addProgrammerArtPack$5(File)
- Pack lambda$addProgrammerArtPack$6(File)
+ Pack lambda$loadPacks$1(File)
- Pack lambda$setServerPack$4(File)
+ Pack lambda$setServerPack$5(File)
- void addProgrammerArtPack(Map,UnopenedPack$UnopenedPackConstructor)
- void lambda$downloadAndSelectResourcePack$1(Minecraft,ProgressScreen)
+ void lambda$downloadAndSelectResourcePack$2(Minecraft,ProgressScreen)
- void lambda$downloadAndSelectResourcePack$3(File,Void,Throwable)
+ void lambda$downloadAndSelectResourcePack$4(File,Void,Throwable)
```

</details>
<details>
<summary>
net.minecraft.nbt.CompoundTag
</summary>

```diff
- boolean hasUUIDArray(String)
- UUID getUUIDFromArray(String)
- void putUUIDAsArray(String,UUID)
```

</details>
<details>
<summary>
net.minecraft.nbt.NbtUtils
</summary>

```diff
- IntArrayTag createUUIDArray(UUID)
- UUID loadUUIDArray(Tag)
```

</details>
<details>
<summary>
net.minecraft.realms.RealmsConnect$1
</summary>

```diff
- void <init>(RealmsConnect,String,String,int,Minecraft)
+ void <init>(RealmsConnect,String,String,int)
- void lambda$run$1(Minecraft,DisconnectedRealmsScreen)
- void lambda$run$2(Minecraft,DisconnectedRealmsScreen)
```

</details>
<details>
<summary>
net.minecraft.realms.RealmsObjectSelectionList
</summary>

```diff
+ boolean removeEntry(RealmListEntry)
+ GuiEventListener getProxy()
- int addEntry(AbstractSelectionList$Entry)
- int addEntry(ObjectSelectionList$Entry)
+ int getScroll()
+ int headerHeight()
+ int itemHeight()
+ int width()
+ int y0()
+ int y1()
+ List children()
+ RealmListEntry getSelected()
+ void addEntry(RealmListEntry)
+ void remove(int)
+ void render(int,int,float)
+ void renderBackground()
+ void renderItem(int,int,int,int,int,int)
+ void renderItem(int,int,int,int,Tezzelator,int,int)
+ void scroll(int)
+ void setLeftPos(int)
+ void setSelected(int)
- void setSelectedItem(int)
```

</details>
<details>
<summary>
net.minecraft.server.level.ServerChunkCache
</summary>

```diff
+ void lambda$tickChunks$5(long,boolean,MobCategory[],boolean,int,Object2IntMap,BlockPos,int,ChunkHolder)
- void lambda$tickChunks$5(long,boolean,MobCategory[],boolean,int,Object2IntMap,int,ChunkHolder)
```

</details>
<details>
<summary>
net.minecraft.server.players.StoredUserList
</summary>

```diff
- JsonObject lambda$save$0(StoredUserEntry)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.behavior.MeleeAttack
</summary>

```diff
+ boolean canStillUse(ServerLevel,LivingEntity,long)
+ boolean canStillUse(ServerLevel,Mob,long)
+ boolean isHoldingProjectileWeapon(Mob)
- boolean lambda$checkExtraStartConditions$0(Item)
+ boolean lambda$isHoldingProjectileWeapon$0(Item)
+ LivingEntity getAttackTarget(LivingEntity)
+ void meleeAttack(Mob,LivingEntity)
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.AbstractArrow
</summary>

```diff
+ Entity getOwner()
+ void onHit(HitResult)
- void onHitBlock(BlockHitResult)
+ void shootFromRotation(Entity,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.AbstractHurtingProjectile
</summary>

```diff
+ void onHit(HitResult)
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.FireworkRocketEntity
</summary>

```diff
- void <init>(Level,Entity,double,double,double,ItemStack)
- void <init>(Level,ItemStack,Entity,double,double,double,boolean)
+ void lerpMotion(double,double,double)
- void onHitBlock(BlockHitResult)
- void onHitEntity(EntityHitResult)
+ void performHitChecks(HitResult)
+ void shoot(double,double,double,float,float)
+ void shootFromRotation(Entity,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.LargeFireball
</summary>

```diff
- void onHitEntity(EntityHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.Projectile
</summary>

```diff
- Entity getOwner()
- void <init>(EntityType,Level)
- void addAdditionalSaveData(CompoundTag)
- void lerpMotion(double,double,double)
- void onHit(HitResult)
- void onHitBlock(BlockHitResult)
- void onHitEntity(EntityHitResult)
- void readAdditionalSaveData(CompoundTag)
- void setOwner(Entity)
- void shoot(double,double,double,float,float)
- void shootFromRotation(Entity,float,float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.Snowball
</summary>

```diff
- void onHitEntity(EntityHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.ThrownEgg
</summary>

```diff
- void onHitEntity(EntityHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.inventory.AnvilMenu
</summary>

```diff
- boolean isValidBlock(BlockState)
+ Boolean lambda$stillValid$1(Player,Level,BlockPos)
- boolean mayPickup(Player,boolean)
+ boolean stillValid(Player)
+ Container access$100(AnvilMenu)
+ DataSlot access$000(AnvilMenu)
+ int access$200(AnvilMenu)
- ItemStack onTake(Player,ItemStack)
+ ItemStack quickMoveStack(Player,int)
- void lambda$onTake$0(Player,Level,BlockPos)
+ void lambda$removed$0(Player,Level,BlockPos)
+ void removed(Player)
+ void slotsChanged(Container)
```

</details>
<details>
<summary>
net.minecraft.world.item.HoeItem
</summary>

```diff
+ boolean hurtEnemy(ItemStack,LivingEntity,LivingEntity)
+ boolean mineBlock(ItemStack,Level,BlockState,BlockPos,LivingEntity)
+ float getDestroySpeed(ItemStack,BlockState)
+ Multimap getDefaultAttributeModifiers(EquipmentSlot)
+ void <init>(Tier,float,Item$Properties)
- void <init>(Tier,int,float,Item$Properties)
+ void lambda$hurtEnemy$2(LivingEntity)
+ void lambda$mineBlock$0(LivingEntity)
- void lambda$useOn$0(UseOnContext,Player)
+ void lambda$useOn$1(UseOnContext,Player)
```

</details>
<details>
<summary>
net.minecraft.world.level.EntityGetter
</summary>

```diff
+ Player getNearestPlayerIgnoreY(double,double,double)
```

</details>
<details>
<summary>
net.minecraft.world.level.Level
</summary>

```diff
+ boolean extinguishFire(Player,BlockPos,Direction)
```

</details>
<details>
<summary>
net.minecraft.world.level.NaturalSpawner
</summary>

```diff
- boolean isRightDistanceToPlayerAndSpawnPoint(ServerLevel,ChunkAccess,BlockPos$MutableBlockPos,double)
- boolean isValidPositionForMob(ServerLevel,Mob,double)
- boolean isValidSpawnPostitionForType(ServerLevel,ChunkGenerator,Biome$SpawnerData,BlockPos$MutableBlockPos,double)
- Mob getMobForSpawn(ServerLevel,EntityType)
+ void spawnCategoryForChunk(MobCategory,ServerLevel,LevelChunk,BlockPos)
- void spawnCategoryForChunk(MobCategory,ServerLevel,LevelChunk)
- void spawnCategoryForPosition(MobCategory,ServerLevel,BlockPos)
- void spawnCategoryForPosition(MobCategory,ServerLevel,ChunkAccess,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.BiomeManager
</summary>

```diff
+ Biome getNoiseBiome(int,int,int)
- Biome getNoiseBiomeAtPosition(double,double,double)
- Biome getNoiseBiomeAtQuart(int,int,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.Block
</summary>

```diff
+ void onProjectileHit(Level,BlockState,BlockHitResult,Entity)
- void onProjectileHit(Level,BlockState,BlockHitResult,Projectile)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.ChorusFlowerBlock
</summary>

```diff
+ void onProjectileHit(Level,BlockState,BlockHitResult,Entity)
- void onProjectileHit(Level,BlockState,BlockHitResult,Projectile)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.FireBlock
</summary>

```diff
- BlockState getStateForPlacement(BlockPlaceContext)
- VoxelShape getShape(BlockState,BlockGetter,BlockPos,CollisionContext)
```

</details>
</details>
<hr/>