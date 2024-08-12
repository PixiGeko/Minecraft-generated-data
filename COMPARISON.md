## Comparison with [22w12a](https://github.com/PixiGeko/Minecraft-generated-data/tree/22w12a)

- [Version data](#version-data)
- [Registries](#registries)
- [Tags](#tags)
- [Recipes](#recipes)
- [Translations](#translations)
- [File structure](#file-structure)
- [Mappings](#mappings)
  - [Server](#server)
  - [Client](#client)

<hr/>
<details><summary>Version data</summary>
<table><tr><th></th><th align="left">22w12a</th><th>22w13a</th></tr><tr><td>World version</td><td><code>3082</code></td><td><code>3085</code></td></tr><tr><td>Protocol version</td><td><code>1073741899</code></td><td><code>1073741900</code></td></tr></table>
</details>
<details><summary>Registries</summary>
<details>
<summary>
block.txt
</summary>

```diff
+ minecraft:reinforced_deepslate
```

</details>






<details>
<summary>
entity_type.txt
</summary>

```diff
+ minecraft:allay
```

</details>


<details>
<summary>
game_event.txt
</summary>

```diff
+ minecraft:block_activate
+ minecraft:block_deactivate
- minecraft:block_press
- minecraft:block_switch
- minecraft:block_unpress
- minecraft:block_unswitch
+ minecraft:drink
- minecraft:drinking_finish
- minecraft:elytra_free_fall
+ minecraft:elytra_glide
+ minecraft:entity_damage
- minecraft:entity_damaged
+ minecraft:entity_die
- minecraft:entity_dying
+ minecraft:entity_interact
- minecraft:entity_killed
+ minecraft:entity_roar
+ minecraft:entity_shake
- minecraft:fishing_rod_cast
- minecraft:fishing_rod_reel_in
+ minecraft:item_interact_finish
+ minecraft:item_interact_start
- minecraft:minecart_moving
- minecraft:mob_interact
+ minecraft:note_block_play
- minecraft:ravager_roar
- minecraft:ring_bell
- minecraft:shulker_close
- minecraft:shulker_open
- minecraft:wolf_shaking
```

</details>


<details>
<summary>
item.txt
</summary>

```diff
+ minecraft:allay_spawn_egg
+ minecraft:reinforced_deepslate
```

</details>






<details>
<summary>
memory_module_type.txt
</summary>

```diff
+ minecraft:item_pickup_cooldown_ticks
+ minecraft:liked_noteblock
+ minecraft:liked_noteblock_cooldown_ticks
+ minecraft:liked_player
```

</details>



<details>
<summary>
particle_type.txt
</summary>

```diff
+ minecraft:allay_dust
```

</details>









<details>
<summary>
sound_event.txt
</summary>

```diff
+ minecraft:entity.allay.ambient_with_item
+ minecraft:entity.allay.ambient_without_item
+ minecraft:entity.allay.death
+ minecraft:entity.allay.flap
+ minecraft:entity.allay.hurt
+ minecraft:entity.allay.item_given
+ minecraft:entity.allay.item_taken
```

</details>
</details>
<details><summary>Tags</summary>
<details>
<summary>
all_blocks_without_drop.json
</summary>

```diff
+ minecraft:reinforced_deepslate
- minecraft:sculk_shrieker
```

</details>
<details>
<summary>
all_blocks_with_drop.json
</summary>

```diff
+ minecraft:sculk_shrieker
```

</details>
<details>
<summary>
all_entities_without_drop.json
</summary>

```diff
+ minecraft:allay
```

</details>

<details>
<summary>
all_living_entities_without_drop.json
</summary>

```diff
+ minecraft:allay
```

</details>
<details>
<summary>
all_survival_blocks_without_drop.json
</summary>

```diff
+ minecraft:reinforced_deepslate
- minecraft:sculk_shrieker
```

</details>


<details>
<summary>
universal_tags/block.json
</summary>

```diff
+ minecraft:reinforced_deepslate
```

</details>






<details>
<summary>
universal_tags/entity_type.json
</summary>

```diff
+ minecraft:allay
```

</details>


<details>
<summary>
universal_tags/game_event.json
</summary>

```diff
+ minecraft:block_activate
+ minecraft:block_deactivate
- minecraft:block_press
- minecraft:block_switch
- minecraft:block_unpress
- minecraft:block_unswitch
+ minecraft:drink
- minecraft:drinking_finish
- minecraft:elytra_free_fall
+ minecraft:elytra_glide
+ minecraft:entity_damage
- minecraft:entity_damaged
+ minecraft:entity_die
- minecraft:entity_dying
+ minecraft:entity_interact
- minecraft:entity_killed
+ minecraft:entity_roar
+ minecraft:entity_shake
- minecraft:fishing_rod_cast
- minecraft:fishing_rod_reel_in
+ minecraft:item_interact_finish
+ minecraft:item_interact_start
- minecraft:minecart_moving
- minecraft:mob_interact
+ minecraft:note_block_play
- minecraft:ravager_roar
- minecraft:ring_bell
- minecraft:shulker_close
- minecraft:shulker_open
- minecraft:wolf_shaking
```

</details>


<details>
<summary>
universal_tags/item.json
</summary>

```diff
+ minecraft:allay_spawn_egg
+ minecraft:reinforced_deepslate
```

</details>






<details>
<summary>
universal_tags/memory_module_type.json
</summary>

```diff
+ minecraft:item_pickup_cooldown_ticks
+ minecraft:liked_noteblock
+ minecraft:liked_noteblock_cooldown_ticks
+ minecraft:liked_player
```

</details>



<details>
<summary>
universal_tags/particle_type.json
</summary>

```diff
+ minecraft:allay_dust
```

</details>









<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:entity.allay.ambient_with_item
+ minecraft:entity.allay.ambient_without_item
+ minecraft:entity.allay.death
+ minecraft:entity.allay.flap
+ minecraft:entity.allay.hurt
+ minecraft:entity.allay.item_given
+ minecraft:entity.allay.item_taken
```

</details>
</details>
<details><summary>Recipes</summary>
<details>
<summary>
acacia_chest_boat.json
</summary>

```
Group: none -> chest_boat
```

</details>

































<details>
<summary>
birch_chest_boat.json
</summary>

```
Group: none -> chest_boat
```

</details>



























































































<details>
<summary>
chest_minecart.json
</summary>

```
Type: minecraft:crafting_shaped -> minecraft:crafting_shapeless
```

</details>





























































































































<details>
<summary>
dark_oak_chest_boat.json
</summary>

```
Group: none -> chest_boat
```

</details>




























































































































<details>
<summary>
furnace_minecart.json
</summary>

```
Type: minecraft:crafting_shaped -> minecraft:crafting_shapeless
```

</details>









































































<details>
<summary>
hopper_minecart.json
</summary>

```
Type: minecraft:crafting_shaped -> minecraft:crafting_shapeless
```

</details>





























<details>
<summary>
jungle_chest_boat.json
</summary>

```
Group: none -> chest_boat
```

</details>





































































































<details>
<summary>
mangrove_chest_boat.json
</summary>

```
Group: none -> chest_boat
```

</details>






































































<details>
<summary>
oak_chest_boat.json
</summary>

```
Group: none -> chest_boat
```

</details>










































































































































































































































































<details>
<summary>
spruce_chest_boat.json
</summary>

```
Group: none -> chest_boat
```

</details>























































<details>
<summary>
tnt_minecart.json
</summary>

```
Type: minecraft:crafting_shaped -> minecraft:crafting_shapeless
```

</details>
</details>
<details><summary>Translations</summary>
<details>
<summary>
Keys
</summary>

```diff
+ advancements.adventure.kill_mob_near_sculk_catalyst.description: Kill a mob near a sculk catalyst
+ advancements.adventure.kill_mob_near_sculk_catalyst.title: It spreads
+ advancements.husbandry.froglights.description: Have all froglights in your inventory
+ advancements.husbandry.froglights.title: With our powers combined!
+ advancements.husbandry.tadpole_in_a_bucket.description: Catch a tadpole in a bucket
+ advancements.husbandry.tadpole_in_a_bucket.title: Bukkit bukkit
+ block.minecraft.reinforced_deepslate: Reinforced Deepslate
+ entity.minecraft.allay: Allay
+ item.minecraft.allay_spawn_egg: Allay Spawn Egg
+ subtitles.entity.allay.ambient_with_item: Allay seeks
+ subtitles.entity.allay.ambient_without_item: Allay yearns
+ subtitles.entity.allay.death: Allay dies
+ subtitles.entity.allay.hurt: Allay hurts
+ subtitles.entity.allay.item_given: Allay chortles
+ subtitles.entity.allay.item_taken: Allay allays
+ subtitles.entity.allay.throw: Allay tosses
```

</details>
</details>
<details><summary>File structure</summary>
<details>
<summary>
generated
</summary>

```diff
+ reports/worldgen/minecraft/worldgen/configured_feature/sculk_patch_ancient_city.json
+ reports/worldgen/minecraft/worldgen/configured_feature/sculk_patch_deep_dark.json
- reports/worldgen/minecraft/worldgen/configured_feature/sculk_patch.json
+ reports/worldgen/minecraft/worldgen/placed_feature/sculk_patch_ancient_city.json
+ reports/worldgen/minecraft/worldgen/placed_feature/sculk_patch_deep_dark.json
- reports/worldgen/minecraft/worldgen/placed_feature/sculk_patch.json
+ reports/worldgen/minecraft/worldgen/processor_list/ancient_city_generic_degradation.json
+ reports/worldgen/minecraft/worldgen/processor_list/ancient_city_start_degradation.json
+ reports/worldgen/minecraft/worldgen/processor_list/ancient_city_walls_degradation.json
+ reports/worldgen/minecraft/worldgen/structure_set/ancient_cities.json
+ reports/worldgen/minecraft/worldgen/structure/ancient_city.json
+ reports/worldgen/minecraft/worldgen/template_pool/ancient_city/city_center.json
+ reports/worldgen/minecraft/worldgen/template_pool/ancient_city/city_center/walls.json
+ reports/worldgen/minecraft/worldgen/template_pool/ancient_city/city/entrance.json
+ reports/worldgen/minecraft/worldgen/template_pool/ancient_city/sculk.json
+ reports/worldgen/minecraft/worldgen/template_pool/ancient_city/structures.json
+ reports/worldgen/minecraft/worldgen/template_pool/ancient_city/walls.json
+ reports/worldgen/minecraft/worldgen/template_pool/ancient_city/walls/no_corners.json
```

</details>
<details>
<summary>
data
</summary>

```diff
+ minecraft/advancements/adventure/kill_mob_near_sculk_catalyst.json
+ minecraft/advancements/husbandry/froglights.json
+ minecraft/advancements/husbandry/tadpole_in_a_bucket.json
+ minecraft/loot_tables/blocks/reinforced_deepslate.json
+ minecraft/loot_tables/chests/ancient_city_ice_box.json
+ minecraft/loot_tables/chests/ancient_city.json
+ minecraft/loot_tables/entities/allay.json
+ minecraft/structures/ancient_city/city_center/city_center_1.nbt
+ minecraft/structures/ancient_city/city_center/city_center_2.nbt
+ minecraft/structures/ancient_city/city_center/city_center_3.nbt
+ minecraft/structures/ancient_city/city_center/walls/bottom_1.nbt
+ minecraft/structures/ancient_city/city_center/walls/bottom_2.nbt
+ minecraft/structures/ancient_city/city_center/walls/bottom_left_corner.nbt
+ minecraft/structures/ancient_city/city_center/walls/bottom_right_corner_1.nbt
+ minecraft/structures/ancient_city/city_center/walls/bottom_right_corner_2.nbt
+ minecraft/structures/ancient_city/city_center/walls/bottom_right_corner.nbt
+ minecraft/structures/ancient_city/city_center/walls/left.nbt
+ minecraft/structures/ancient_city/city_center/walls/right.nbt
+ minecraft/structures/ancient_city/city_center/walls/top_left_corner.nbt
+ minecraft/structures/ancient_city/city_center/walls/top_right_corner.nbt
+ minecraft/structures/ancient_city/city_center/walls/top.nbt
+ minecraft/structures/ancient_city/city/entrance/bottom_piece_1.nbt
+ minecraft/structures/ancient_city/city/entrance/bottom_piece_2.nbt
+ minecraft/structures/ancient_city/city/entrance/bottom_piece_3.nbt
+ minecraft/structures/ancient_city/city/entrance/bottom_piece.nbt
+ minecraft/structures/ancient_city/city/entrance/entrance_connector.nbt
+ minecraft/structures/ancient_city/city/entrance/entrance_path_1.nbt
+ minecraft/structures/ancient_city/city/entrance/entrance_path_2.nbt
+ minecraft/structures/ancient_city/city/entrance/entrance_path_3.nbt
+ minecraft/structures/ancient_city/city/entrance/entrance_path_4.nbt
+ minecraft/structures/ancient_city/city/entrance/entrance_path_5.nbt
+ minecraft/structures/ancient_city/city/entrance/top_piece.nbt
+ minecraft/structures/ancient_city/structures/barracks.nbt
+ minecraft/structures/ancient_city/structures/camp_1.nbt
+ minecraft/structures/ancient_city/structures/camp_2.nbt
+ minecraft/structures/ancient_city/structures/camp_3.nbt
+ minecraft/structures/ancient_city/structures/chamber_1.nbt
+ minecraft/structures/ancient_city/structures/chamber_2.nbt
+ minecraft/structures/ancient_city/structures/chamber_3.nbt
+ minecraft/structures/ancient_city/structures/ice_box_1.nbt
+ minecraft/structures/ancient_city/structures/large_pillar_1.nbt
+ minecraft/structures/ancient_city/structures/large_ruin_1.nbt
+ minecraft/structures/ancient_city/structures/medium_pillar_1.nbt
+ minecraft/structures/ancient_city/structures/medium_ruin_1.nbt
+ minecraft/structures/ancient_city/structures/medium_ruin_2.nbt
+ minecraft/structures/ancient_city/structures/sauna_1.nbt
+ minecraft/structures/ancient_city/structures/small_portal_statue.nbt
+ minecraft/structures/ancient_city/structures/small_ruin_1.nbt
+ minecraft/structures/ancient_city/structures/small_ruin_2.nbt
+ minecraft/structures/ancient_city/structures/small_statue.nbt
+ minecraft/structures/ancient_city/structures/tall_ruin_1.nbt
+ minecraft/structures/ancient_city/structures/tall_ruin_2.nbt
+ minecraft/structures/ancient_city/structures/tall_ruin_3.nbt
+ minecraft/structures/ancient_city/structures/tall_ruin_4.nbt
+ minecraft/structures/ancient_city/walls/intact_corner_wall_1.nbt
+ minecraft/structures/ancient_city/walls/intact_horizontal_wall_1.nbt
+ minecraft/structures/ancient_city/walls/intact_horizontal_wall_2.nbt
+ minecraft/structures/ancient_city/walls/intact_horizontal_wall_bridge.nbt
+ minecraft/structures/ancient_city/walls/intact_horizontal_wall_passage_1.nbt
+ minecraft/structures/ancient_city/walls/intact_horizontal_wall_stairs_1.nbt
+ minecraft/structures/ancient_city/walls/intact_horizontal_wall_stairs_2.nbt
+ minecraft/structures/ancient_city/walls/intact_horizontal_wall_stairs_3.nbt
+ minecraft/structures/ancient_city/walls/intact_horizontal_wall_stairs_4.nbt
+ minecraft/structures/ancient_city/walls/intact_horizontal_wall_stairs_upward.nbt
+ minecraft/structures/ancient_city/walls/intact_intersection_wall_1.nbt
+ minecraft/structures/ancient_city/walls/intact_lshape_wall_1.nbt
+ minecraft/structures/ancient_city/walls/ruined_corner_wall_1.nbt
+ minecraft/structures/ancient_city/walls/ruined_corner_wall_2.nbt
+ minecraft/structures/ancient_city/walls/ruined_horizontal_wall_stairs_1.nbt
+ minecraft/structures/ancient_city/walls/ruined_horizontal_wall_stairs_2.nbt
+ minecraft/structures/ancient_city/walls/ruined_horizontal_wall_stairs_3.nbt
+ minecraft/structures/ancient_city/walls/ruined_horizontal_wall_stairs_4.nbt
+ minecraft/structures/pillager_outpost/feature_cage_with_allays.nbt
+ minecraft/tags/blocks/ancient_city_center_replaceable.json
+ minecraft/tags/blocks/ancient_city_replaceable.json
- minecraft/tags/blocks/carpets.json
+ minecraft/tags/blocks/wool_carpets.json
+ minecraft/tags/game_events/ignore_vibrations_on_occluding_block.json
- minecraft/tags/items/carpets.json
+ minecraft/tags/items/wool_carpets.json
+ minecraft/tags/worldgen/biome/has_structure/ancient_city.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/blockstates/reinforced_deepslate.json
+ minecraft/models/block/reinforced_deepslate.json
+ minecraft/models/block/sculk_shrieker_can_summon.json
+ minecraft/models/block/template_sculk_shrieker.json
+ minecraft/models/item/allay_spawn_egg.json
+ minecraft/models/item/reinforced_deepslate.json
+ minecraft/particles/allay_dust.json
+ minecraft/textures/block/reinforced_deepslate_bottom.png
+ minecraft/textures/block/reinforced_deepslate_side.png
+ minecraft/textures/block/reinforced_deepslate_top.png
+ minecraft/textures/block/sculk_shrieker_can_summon_inner_top.png
+ minecraft/textures/block/sculk_shrieker_can_summon_inner_top.png.mcmeta
+ minecraft/textures/entity/allay/allay.png
- minecraft/textures/entity/warden/warden_ears.png
```

</details>
</details>
<details><summary>Mappings</summary>
<h2>Server</h2>
<details>
<summary>
Classes
</summary>

```diff
- net.minecraft.data.worldgen.AncientCityStructurePieces
- net.minecraft.util.datafix.fixes.package-info
- net.minecraft.util.datafix.fixes.SimplestEntityRenameFix
+ net.minecraft.util.datafix.fixes.SpawnerDataFix
- net.minecraft.util.datafix.fixes.StatsCounterFix
+ net.minecraft.util.datafix.fixes.StatsRenameFix
- net.minecraft.util.datafix.fixes.StriderGravityFix
+ net.minecraft.util.datafix.fixes.StructureReferenceCountFix
+ net.minecraft.util.datafix.fixes.StructuresBecomeConfiguredFix
- net.minecraft.util.datafix.fixes.StructuresBecomeConfiguredFix$Conversion
- net.minecraft.util.datafix.fixes.StructureSettingsFlattenFix
+ net.minecraft.util.datafix.fixes.TeamDisplayNameFix
- net.minecraft.util.datafix.fixes.TrappedChestBlockEntityFix
+ net.minecraft.util.datafix.fixes.TrappedChestBlockEntityFix$TrappedChestSection
- net.minecraft.util.datafix.fixes.VillagerDataFix
+ net.minecraft.util.datafix.fixes.VillagerFollowRangeFix
- net.minecraft.util.datafix.fixes.VillagerRebuildLevelAndXpFix
+ net.minecraft.util.datafix.fixes.VillagerTradeFix
- net.minecraft.util.datafix.fixes.WallPropertyFix
+ net.minecraft.util.datafix.fixes.WeaponSmithChestLootTableFix
- net.minecraft.util.datafix.fixes.WorldGenSettingsDisallowOldCustomWorldsFix
+ net.minecraft.util.datafix.fixes.WorldGenSettingsFix
- net.minecraft.util.datafix.fixes.WorldGenSettingsFix$StructureFeatureConfiguration
+ net.minecraft.util.datafix.fixes.WorldGenSettingsHeightAndBiomeFix
- net.minecraft.util.datafix.fixes.WriteAndReadFix
+ net.minecraft.util.datafix.fixes.ZombieVillagerRebuildXpFix
+ net.minecraft.util.datafix.package-info
- net.minecraft.util.datafix.schemas.NamespacedSchema
+ net.minecraft.util.datafix.schemas.NamespacedSchema$1
- net.minecraft.util.datafix.schemas.V100
+ net.minecraft.util.datafix.schemas.V102
- net.minecraft.util.datafix.schemas.V1022
+ net.minecraft.util.datafix.schemas.V106
- net.minecraft.util.datafix.schemas.V107
+ net.minecraft.util.datafix.schemas.V1125
- net.minecraft.util.datafix.schemas.V135
+ net.minecraft.util.datafix.schemas.V143
- net.minecraft.util.datafix.schemas.V1451
+ net.minecraft.util.datafix.schemas.V1451_1
- net.minecraft.util.datafix.schemas.V1451_2
+ net.minecraft.util.datafix.schemas.V1451_3
- net.minecraft.util.datafix.schemas.V1451_4
+ net.minecraft.util.datafix.schemas.V1451_5
- net.minecraft.util.datafix.schemas.V1451_6
+ net.minecraft.util.datafix.schemas.V1451_6$1
- net.minecraft.util.datafix.schemas.V1451_6$2
+ net.minecraft.util.datafix.schemas.V1451_7
- net.minecraft.util.datafix.schemas.V1460
+ net.minecraft.util.datafix.schemas.V1466
- net.minecraft.util.datafix.schemas.V1470
+ net.minecraft.util.datafix.schemas.V1481
- net.minecraft.util.datafix.schemas.V1483
+ net.minecraft.util.datafix.schemas.V1486
- net.minecraft.util.datafix.schemas.V1510
+ net.minecraft.util.datafix.schemas.V1800
- net.minecraft.util.datafix.schemas.V1801
+ net.minecraft.util.datafix.schemas.V1904
- net.minecraft.util.datafix.schemas.V1906
+ net.minecraft.util.datafix.schemas.V1909
- net.minecraft.util.datafix.schemas.V1920
+ net.minecraft.util.datafix.schemas.V1928
- net.minecraft.util.datafix.schemas.V1929
+ net.minecraft.util.datafix.schemas.V1931
- net.minecraft.util.datafix.schemas.V2100
+ net.minecraft.util.datafix.schemas.V2501
- net.minecraft.util.datafix.schemas.V2502
+ net.minecraft.util.datafix.schemas.V2505
- net.minecraft.util.datafix.schemas.V2509
+ net.minecraft.util.datafix.schemas.V2519
- net.minecraft.util.datafix.schemas.V2522
+ net.minecraft.util.datafix.schemas.V2551
- net.minecraft.util.datafix.schemas.V2568
+ net.minecraft.util.datafix.schemas.V2571
- net.minecraft.util.datafix.schemas.V2684
+ net.minecraft.util.datafix.schemas.V2686
- net.minecraft.util.datafix.schemas.V2688
+ net.minecraft.util.datafix.schemas.V2704
- net.minecraft.util.datafix.schemas.V2707
+ net.minecraft.util.datafix.schemas.V2831
- net.minecraft.util.datafix.schemas.V2832
+ net.minecraft.util.datafix.schemas.V2842
- net.minecraft.util.datafix.schemas.V3076
+ net.minecraft.util.datafix.schemas.V3078
- net.minecraft.util.datafix.schemas.V3081
+ net.minecraft.util.datafix.schemas.V3082
- net.minecraft.util.datafix.schemas.V3083
- net.minecraft.util.OptionEnum
+ net.minecraft.util.ParticleUtils
- net.minecraft.util.ProgressListener
+ net.minecraft.util.SimpleBitStorage
- net.minecraft.util.SimpleBitStorage$InitializationException
+ net.minecraft.util.SmoothDouble
- net.minecraft.util.SortedArraySet
+ net.minecraft.util.SortedArraySet$ArrayIterator
- net.minecraft.util.SpawnUtil
+ net.minecraft.util.StringDecomposer
- net.minecraft.util.StringRepresentable
+ net.minecraft.util.StringRepresentable$1
- net.minecraft.util.StringRepresentable$EnumCodec
- net.minecraft.world.entity.ai.behavior.FlyingRandomStroll
+ net.minecraft.world.entity.ai.behavior.FollowTemptation
- net.minecraft.world.entity.ai.behavior.GateBehavior
+ net.minecraft.world.entity.ai.behavior.GateBehavior$OrderPolicy
- net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy
+ net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$1
- net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$2
+ net.minecraft.world.entity.ai.behavior.GiveGiftToHero
- net.minecraft.world.entity.ai.behavior.GoAndGiveItemsToTarget
+ net.minecraft.world.entity.ai.behavior.package-info
- net.minecraft.world.entity.ai.behavior.StayCloseToTarget
+ net.minecraft.world.entity.ai.behavior.StopAttackingIfTargetInvalid
- net.minecraft.world.entity.ai.behavior.StopBeingAngryIfTargetDead
+ net.minecraft.world.entity.ai.behavior.StrollAroundPoi
- net.minecraft.world.entity.ai.behavior.StrollToPoi
+ net.minecraft.world.entity.ai.behavior.StrollToPoiList
- net.minecraft.world.entity.ai.behavior.Swim
+ net.minecraft.world.entity.ai.behavior.TradeWithVillager
- net.minecraft.world.entity.ai.behavior.TryFindLand
+ net.minecraft.world.entity.ai.behavior.TryFindLandNearWater
- net.minecraft.world.entity.ai.behavior.TryFindWater
+ net.minecraft.world.entity.ai.behavior.TryLaySpawnOnWaterNearLand
- net.minecraft.world.entity.ai.behavior.UpdateActivityFromSchedule
+ net.minecraft.world.entity.ai.behavior.UseBonemeal
- net.minecraft.world.entity.ai.behavior.ValidateNearbyPoi
+ net.minecraft.world.entity.ai.behavior.VictoryStroll
- net.minecraft.world.entity.ai.behavior.VillageBoundRandomStroll
+ net.minecraft.world.entity.ai.behavior.VillagerCalmDown
- net.minecraft.world.entity.ai.behavior.VillagerGoalPackages
+ net.minecraft.world.entity.ai.behavior.VillagerMakeLove
- net.minecraft.world.entity.ai.behavior.VillagerPanicTrigger
+ net.minecraft.world.entity.ai.behavior.WakeUp
- net.minecraft.world.entity.ai.behavior.WorkAtComposter
+ net.minecraft.world.entity.ai.behavior.WorkAtPoi
- net.minecraft.world.entity.ai.behavior.YieldJobSite
- net.minecraft.world.entity.ai.control.BodyRotationControl
+ net.minecraft.world.entity.ai.control.Control
- net.minecraft.world.entity.ai.control.FlyingMoveControl
+ net.minecraft.world.entity.ai.control.JumpControl
- net.minecraft.world.entity.ai.control.LookControl
+ net.minecraft.world.entity.ai.control.MoveControl
- net.minecraft.world.entity.ai.control.MoveControl$Operation
+ net.minecraft.world.entity.ai.control.package-info
+ net.minecraft.world.entity.ai.control.SmoothSwimmingLookControl
- net.minecraft.world.entity.ai.control.SmoothSwimmingMoveControl
- net.minecraft.world.entity.ai.goal.AvoidEntityGoal
+ net.minecraft.world.entity.ai.goal.BegGoal
- net.minecraft.world.entity.ai.goal.BoatGoals
+ net.minecraft.world.entity.ai.goal.BreakDoorGoal
- net.minecraft.world.entity.ai.goal.BreathAirGoal
+ net.minecraft.world.entity.ai.goal.BreedGoal
- net.minecraft.world.entity.ai.goal.CatLieOnBedGoal
+ net.minecraft.world.entity.ai.goal.CatSitOnBlockGoal
- net.minecraft.world.entity.ai.goal.ClimbOnTopOfPowderSnowGoal
+ net.minecraft.world.entity.ai.goal.DolphinJumpGoal
- net.minecraft.world.entity.ai.goal.DoorInteractGoal
+ net.minecraft.world.entity.ai.goal.EatBlockGoal
- net.minecraft.world.entity.ai.goal.FleeSunGoal
+ net.minecraft.world.entity.ai.goal.FloatGoal
- net.minecraft.world.entity.ai.goal.FollowBoatGoal
+ net.minecraft.world.entity.ai.goal.FollowFlockLeaderGoal
- net.minecraft.world.entity.ai.goal.FollowMobGoal
+ net.minecraft.world.entity.ai.goal.FollowOwnerGoal
- net.minecraft.world.entity.ai.goal.FollowParentGoal
+ net.minecraft.world.entity.ai.goal.Goal
- net.minecraft.world.entity.ai.goal.Goal$Flag
+ net.minecraft.world.entity.ai.goal.GoalSelector
- net.minecraft.world.entity.ai.goal.GoalSelector$1
+ net.minecraft.world.entity.ai.goal.GoalSelector$2
- net.minecraft.world.entity.ai.goal.GolemRandomStrollInVillageGoal
+ net.minecraft.world.entity.ai.goal.InteractGoal
- net.minecraft.world.entity.ai.goal.JumpGoal
+ net.minecraft.world.entity.ai.goal.LandOnOwnersShoulderGoal
- net.minecraft.world.entity.ai.goal.LeapAtTargetGoal
+ net.minecraft.world.entity.ai.goal.LlamaFollowCaravanGoal
- net.minecraft.world.entity.ai.goal.LookAtPlayerGoal
+ net.minecraft.world.entity.ai.goal.LookAtTradingPlayerGoal
- net.minecraft.world.entity.ai.goal.MeleeAttackGoal
+ net.minecraft.world.entity.ai.goal.MoveBackToVillageGoal
- net.minecraft.world.entity.ai.goal.MoveThroughVillageGoal
+ net.minecraft.world.entity.ai.goal.MoveToBlockGoal
- net.minecraft.world.entity.ai.goal.MoveTowardsRestrictionGoal
+ net.minecraft.world.entity.ai.goal.MoveTowardsTargetGoal
- net.minecraft.world.entity.ai.goal.OcelotAttackGoal
+ net.minecraft.world.entity.ai.goal.OfferFlowerGoal
- net.minecraft.world.entity.ai.goal.OpenDoorGoal
- net.minecraft.world.entity.ai.goal.package-info
+ net.minecraft.world.entity.ai.goal.PanicGoal
- net.minecraft.world.entity.ai.goal.PathfindToRaidGoal
+ net.minecraft.world.entity.ai.goal.RandomLookAroundGoal
- net.minecraft.world.entity.ai.goal.RandomStrollGoal
+ net.minecraft.world.entity.ai.goal.RandomSwimmingGoal
- net.minecraft.world.entity.ai.goal.RangedAttackGoal
+ net.minecraft.world.entity.ai.goal.RangedBowAttackGoal
- net.minecraft.world.entity.ai.goal.RangedCrossbowAttackGoal
+ net.minecraft.world.entity.ai.goal.RangedCrossbowAttackGoal$CrossbowState
- net.minecraft.world.entity.ai.goal.RemoveBlockGoal
+ net.minecraft.world.entity.ai.goal.RestrictSunGoal
- net.minecraft.world.entity.ai.goal.RunAroundLikeCrazyGoal
+ net.minecraft.world.entity.ai.goal.SitWhenOrderedToGoal
- net.minecraft.world.entity.ai.goal.StrollThroughVillageGoal
+ net.minecraft.world.entity.ai.goal.SwellGoal
+ net.minecraft.world.entity.ai.goal.target.DefendVillageTargetGoal
- net.minecraft.world.entity.ai.goal.target.HurtByTargetGoal
+ net.minecraft.world.entity.ai.goal.target.NearestAttackableTargetGoal
- net.minecraft.world.entity.ai.goal.target.NearestAttackableWitchTargetGoal
+ net.minecraft.world.entity.ai.goal.target.NearestHealableRaiderTargetGoal
- net.minecraft.world.entity.ai.goal.target.NonTameRandomTargetGoal
+ net.minecraft.world.entity.ai.goal.target.OwnerHurtByTargetGoal
- net.minecraft.world.entity.ai.goal.target.OwnerHurtTargetGoal
+ net.minecraft.world.entity.ai.goal.target.package-info
+ net.minecraft.world.entity.ai.goal.target.ResetUniversalAngerTargetGoal
- net.minecraft.world.entity.ai.goal.target.TargetGoal
- net.minecraft.world.entity.ai.goal.TemptGoal
+ net.minecraft.world.entity.ai.goal.TradeWithPlayerGoal
- net.minecraft.world.entity.ai.goal.TryFindWaterGoal
+ net.minecraft.world.entity.ai.goal.UseItemGoal
- net.minecraft.world.entity.ai.goal.WaterAvoidingRandomFlyingGoal
+ net.minecraft.world.entity.ai.goal.WaterAvoidingRandomStrollGoal
- net.minecraft.world.entity.ai.goal.WrappedGoal
+ net.minecraft.world.entity.ai.goal.ZombieAttackGoal
- net.minecraft.world.entity.ai.gossip.GossipContainer
+ net.minecraft.world.entity.ai.gossip.GossipContainer$EntityGossips
- net.minecraft.world.entity.ai.gossip.GossipContainer$GossipEntry
+ net.minecraft.world.entity.ai.gossip.GossipType
- net.minecraft.world.entity.ai.gossip.package-info
+ net.minecraft.world.entity.ai.memory.ExpirableValue
- net.minecraft.world.entity.ai.memory.MemoryModuleType
+ net.minecraft.world.entity.ai.memory.MemoryStatus
- net.minecraft.world.entity.ai.memory.NearestVisibleLivingEntities
- net.minecraft.world.entity.ai.memory.package-info
+ net.minecraft.world.entity.ai.memory.WalkTarget
+ net.minecraft.world.entity.ai.navigation.FlyingPathNavigation
- net.minecraft.world.entity.ai.navigation.GroundPathNavigation
- net.minecraft.world.entity.ai.navigation.package-info
+ net.minecraft.world.entity.ai.navigation.PathNavigation
- net.minecraft.world.entity.ai.navigation.WallClimberNavigation
+ net.minecraft.world.entity.ai.navigation.WaterBoundPathNavigation
+ net.minecraft.world.entity.ai.package-info
- net.minecraft.world.entity.ai.sensing.AdultSensor
+ net.minecraft.world.entity.ai.sensing.AxolotlAttackablesSensor
- net.minecraft.world.entity.ai.sensing.DummySensor
+ net.minecraft.world.entity.ai.sensing.FrogAttackablesSensor
- net.minecraft.world.entity.ai.sensing.GolemSensor
+ net.minecraft.world.entity.ai.sensing.HoglinSpecificSensor
- net.minecraft.world.entity.ai.sensing.HurtBySensor
+ net.minecraft.world.entity.ai.sensing.IsInWaterSensor
- net.minecraft.world.entity.ai.sensing.NearestBedSensor
+ net.minecraft.world.entity.ai.sensing.NearestItemSensor
- net.minecraft.world.entity.ai.sensing.NearestLivingEntitySensor
+ net.minecraft.world.entity.ai.sensing.NearestVisibleLivingEntitySensor
+ net.minecraft.world.entity.ai.sensing.package-info
- net.minecraft.world.entity.ai.sensing.PiglinBruteSpecificSensor
+ net.minecraft.world.entity.ai.sensing.PiglinSpecificSensor
- net.minecraft.world.entity.ai.sensing.PlayerSensor
+ net.minecraft.world.entity.ai.sensing.SecondaryPoiSensor
- net.minecraft.world.entity.ai.sensing.Sensing
+ net.minecraft.world.entity.ai.sensing.Sensor
- net.minecraft.world.entity.ai.sensing.SensorType
+ net.minecraft.world.entity.ai.sensing.TemptingSensor
- net.minecraft.world.entity.ai.sensing.VillagerBabiesSensor
+ net.minecraft.world.entity.ai.sensing.VillagerHostilesSensor
- net.minecraft.world.entity.ai.sensing.WardenEntitySensor
+ net.minecraft.world.entity.ai.targeting.package-info
- net.minecraft.world.entity.ai.targeting.TargetingConditions
- net.minecraft.world.entity.ai.util.AirAndWaterRandomPos
+ net.minecraft.world.entity.ai.util.AirRandomPos
- net.minecraft.world.entity.ai.util.DefaultRandomPos
+ net.minecraft.world.entity.ai.util.GoalUtils
- net.minecraft.world.entity.ai.util.HoverRandomPos
+ net.minecraft.world.entity.ai.util.LandRandomPos
+ net.minecraft.world.entity.ai.util.package-info
- net.minecraft.world.entity.ai.util.RandomPos
- net.minecraft.world.entity.ai.village.package-info
+ net.minecraft.world.entity.ai.village.poi.package-info
+ net.minecraft.world.entity.ai.village.poi.PoiManager
- net.minecraft.world.entity.ai.village.poi.PoiManager$DistanceTracker
+ net.minecraft.world.entity.ai.village.poi.PoiManager$Occupancy
- net.minecraft.world.entity.ai.village.poi.PoiRecord
+ net.minecraft.world.entity.ai.village.poi.PoiSection
- net.minecraft.world.entity.ai.village.poi.PoiType
- net.minecraft.world.entity.ai.village.ReputationEventType
+ net.minecraft.world.entity.ai.village.ReputationEventType$1
- net.minecraft.world.entity.ai.village.VillageSiege
+ net.minecraft.world.entity.ai.village.VillageSiege$State
- net.minecraft.world.entity.ambient.AmbientCreature
+ net.minecraft.world.entity.ambient.Bat
- net.minecraft.world.entity.ambient.package-info
+ net.minecraft.world.entity.animal.AbstractFish
- net.minecraft.world.entity.animal.AbstractFish$FishMoveControl
+ net.minecraft.world.entity.animal.AbstractFish$FishSwimGoal
- net.minecraft.world.entity.animal.AbstractGolem
+ net.minecraft.world.entity.animal.AbstractSchoolingFish
- net.minecraft.world.entity.animal.AbstractSchoolingFish$SchoolSpawnGroupData
- net.minecraft.world.entity.animal.allay.AllayAi
+ net.minecraft.world.entity.animal.Animal
- net.minecraft.world.entity.animal.Bee
+ net.minecraft.world.entity.animal.Bee$1
- net.minecraft.world.entity.animal.Bee$BaseBeeGoal
+ net.minecraft.world.entity.animal.Bee$BeeAttackGoal
- net.minecraft.world.entity.animal.Bee$BeeBecomeAngryTargetGoal
+ net.minecraft.world.entity.animal.Bee$BeeEnterHiveGoal
- net.minecraft.world.entity.animal.Bee$BeeGoToHiveGoal
+ net.minecraft.world.entity.animal.Bee$BeeGoToKnownFlowerGoal
- net.minecraft.world.entity.animal.Bee$BeeGrowCropGoal
+ net.minecraft.world.entity.animal.Bee$BeeHurtByOtherGoal
- net.minecraft.world.entity.animal.Bee$BeeLocateHiveGoal
+ net.minecraft.world.entity.animal.Bee$BeeLookControl
- net.minecraft.world.entity.animal.Bee$BeePollinateGoal
+ net.minecraft.world.entity.animal.Bee$BeeWanderGoal
- net.minecraft.world.entity.animal.Bucketable
+ net.minecraft.world.entity.animal.Cat
- net.minecraft.world.entity.animal.Cat$CatAvoidEntityGoal
+ net.minecraft.world.entity.animal.Cat$CatRelaxOnOwnerGoal
- net.minecraft.world.entity.animal.Cat$CatTemptGoal
+ net.minecraft.world.entity.animal.Chicken
- net.minecraft.world.entity.animal.Cod
+ net.minecraft.world.entity.animal.Cow
- net.minecraft.world.entity.animal.Dolphin
+ net.minecraft.world.entity.animal.Dolphin$DolphinSwimToTreasureGoal
- net.minecraft.world.entity.animal.Dolphin$DolphinSwimWithPlayerGoal
+ net.minecraft.world.entity.animal.Dolphin$PlayWithItemsGoal
- net.minecraft.world.entity.animal.FlyingAnimal
+ net.minecraft.world.entity.animal.Fox
- net.minecraft.world.entity.animal.Fox$DefendTrustedTargetGoal
+ net.minecraft.world.entity.animal.Fox$FaceplantGoal
- net.minecraft.world.entity.animal.Fox$FoxAlertableEntitiesSelector
+ net.minecraft.world.entity.animal.Fox$FoxBehaviorGoal
- net.minecraft.world.entity.animal.Fox$FoxBreedGoal
+ net.minecraft.world.entity.animal.Fox$FoxEatBerriesGoal
- net.minecraft.world.entity.animal.Fox$FoxFloatGoal
+ net.minecraft.world.entity.animal.Fox$FoxFollowParentGoal
- net.minecraft.world.entity.animal.Fox$FoxGroupData
+ net.minecraft.world.entity.animal.Fox$FoxLookAtPlayerGoal
- net.minecraft.world.entity.animal.Fox$FoxLookControl
+ net.minecraft.world.entity.animal.Fox$FoxMeleeAttackGoal
- net.minecraft.world.entity.animal.Fox$FoxMoveControl
+ net.minecraft.world.entity.animal.Fox$FoxPanicGoal
- net.minecraft.world.entity.animal.Fox$FoxPounceGoal
+ net.minecraft.world.entity.animal.Fox$FoxSearchForItemsGoal
- net.minecraft.world.entity.animal.Fox$FoxStrollThroughVillageGoal
+ net.minecraft.world.entity.animal.Fox$PerchAndSearchGoal
- net.minecraft.world.entity.animal.Fox$SeekShelterGoal
+ net.minecraft.world.entity.animal.Fox$SleepGoal
- net.minecraft.world.entity.animal.Fox$StalkPreyGoal
+ net.minecraft.world.entity.animal.Fox$Type
- net.minecraft.world.entity.animal.IronGolem
+ net.minecraft.world.entity.animal.IronGolem$Crackiness
- net.minecraft.world.entity.animal.MushroomCow
+ net.minecraft.world.entity.animal.MushroomCow$MushroomType
- net.minecraft.world.entity.animal.Ocelot
+ net.minecraft.world.entity.animal.Ocelot$OcelotAvoidEntityGoal
- net.minecraft.world.entity.animal.Ocelot$OcelotTemptGoal
+ net.minecraft.world.entity.animal.Panda
- net.minecraft.world.entity.animal.Panda$Gene
+ net.minecraft.world.entity.animal.Panda$PandaAttackGoal
- net.minecraft.world.entity.animal.Panda$PandaAvoidGoal
+ net.minecraft.world.entity.animal.Panda$PandaBreedGoal
- net.minecraft.world.entity.animal.Panda$PandaHurtByTargetGoal
+ net.minecraft.world.entity.animal.Panda$PandaLieOnBackGoal
- net.minecraft.world.entity.animal.Panda$PandaLookAtPlayerGoal
+ net.minecraft.world.entity.animal.Panda$PandaMoveControl
- net.minecraft.world.entity.animal.Panda$PandaPanicGoal
+ net.minecraft.world.entity.animal.Panda$PandaRollGoal
- net.minecraft.world.entity.animal.Panda$PandaSitGoal
+ net.minecraft.world.entity.animal.Panda$PandaSneezeGoal
- net.minecraft.world.entity.animal.Parrot
+ net.minecraft.world.entity.animal.Parrot$1
- net.minecraft.world.entity.animal.Parrot$ParrotWanderGoal
+ net.minecraft.world.entity.animal.Pig
- net.minecraft.world.entity.animal.PolarBear
+ net.minecraft.world.entity.animal.PolarBear$PolarBearAttackPlayersGoal
- net.minecraft.world.entity.animal.PolarBear$PolarBearHurtByTargetGoal
+ net.minecraft.world.entity.animal.PolarBear$PolarBearMeleeAttackGoal
- net.minecraft.world.entity.animal.PolarBear$PolarBearPanicGoal
+ net.minecraft.world.entity.animal.Pufferfish
- net.minecraft.world.entity.animal.Pufferfish$PufferfishPuffGoal
+ net.minecraft.world.entity.animal.Rabbit
- net.minecraft.world.entity.animal.Rabbit$EvilRabbitAttackGoal
+ net.minecraft.world.entity.animal.Rabbit$RabbitAvoidEntityGoal
- net.minecraft.world.entity.animal.Rabbit$RabbitGroupData
+ net.minecraft.world.entity.animal.Rabbit$RabbitJumpControl
- net.minecraft.world.entity.animal.Rabbit$RabbitMoveControl
+ net.minecraft.world.entity.animal.Rabbit$RabbitPanicGoal
- net.minecraft.world.entity.animal.Rabbit$RaidGardenGoal
+ net.minecraft.world.entity.animal.Salmon
- net.minecraft.world.entity.animal.Sheep
+ net.minecraft.world.entity.animal.Sheep$1
- net.minecraft.world.entity.animal.Sheep$2
+ net.minecraft.world.entity.animal.ShoulderRidingEntity
- net.minecraft.world.entity.animal.SnowGolem
+ net.minecraft.world.entity.animal.Squid
- net.minecraft.world.entity.animal.Squid$SquidFleeGoal
+ net.minecraft.world.entity.animal.Squid$SquidRandomMovementGoal
- net.minecraft.world.entity.animal.TropicalFish
+ net.minecraft.world.entity.animal.TropicalFish$Pattern
- net.minecraft.world.entity.animal.TropicalFish$TropicalFishGroupData
+ net.minecraft.world.entity.animal.Turtle
- net.minecraft.world.entity.animal.Turtle$TurtleBreedGoal
+ net.minecraft.world.entity.animal.Turtle$TurtleGoHomeGoal
- net.minecraft.world.entity.animal.Turtle$TurtleGoToWaterGoal
+ net.minecraft.world.entity.animal.Turtle$TurtleLayEggGoal
- net.minecraft.world.entity.animal.Turtle$TurtleMoveControl
+ net.minecraft.world.entity.animal.Turtle$TurtlePanicGoal
- net.minecraft.world.entity.animal.Turtle$TurtlePathNavigation
+ net.minecraft.world.entity.animal.Turtle$TurtleRandomStrollGoal
- net.minecraft.world.entity.animal.Turtle$TurtleTravelGoal
+ net.minecraft.world.entity.animal.WaterAnimal
- net.minecraft.world.entity.animal.Wolf
+ net.minecraft.world.entity.animal.Wolf$WolfAvoidEntityGoal
- net.minecraft.world.entity.animal.Wolf$WolfPanicGoal
- net.minecraft.world.level.levelgen.Beardifier$Rigid
+ net.minecraft.world.level.levelgen.feature.configurations.BlockColumnConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.BlockColumnConfiguration$Layer
+ net.minecraft.world.level.levelgen.feature.configurations.BlockPileConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.BlockStateConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ColumnFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.CountConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.DeltaFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.DiskConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.DripstoneClusterConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.EndGatewayConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.FeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.GeodeConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.HugeMushroomFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.LargeDripstoneConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.LayerConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.MultifaceGrowthConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.NetherForestVegetationConfig
- net.minecraft.world.level.levelgen.feature.configurations.NoneFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration$TargetBlockState
+ net.minecraft.world.level.levelgen.feature.configurations.package-info
+ net.minecraft.world.level.levelgen.feature.configurations.PointedDripstoneConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ProbabilityFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomBooleanFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ReplaceBlockConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ReplaceSphereConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RootSystemConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SculkPatchConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SimpleBlockConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SimpleRandomFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SpikeConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SpringConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
- net.minecraft.world.level.levelgen.feature.configurations.TwistingVinesConfig
+ net.minecraft.world.level.levelgen.feature.configurations.UnderwaterMagmaConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.VegetationPatchConfiguration
- net.minecraft.world.level.levelgen.feature.featuresize.FeatureSize
+ net.minecraft.world.level.levelgen.feature.featuresize.FeatureSizeType
- net.minecraft.world.level.levelgen.feature.featuresize.package-info
- net.minecraft.world.level.levelgen.feature.featuresize.ThreeLayersFeatureSize
+ net.minecraft.world.level.levelgen.feature.featuresize.TwoLayersFeatureSize
+ net.minecraft.world.level.levelgen.feature.foliageplacers.AcaciaFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.BlobFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.BushFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.DarkOakFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FancyFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer$FoliageAttachment
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacerType
+ net.minecraft.world.level.levelgen.feature.foliageplacers.MegaJungleFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.MegaPineFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.package-info
+ net.minecraft.world.level.levelgen.feature.foliageplacers.PineFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.RandomSpreadFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.SpruceFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.OreFeature
+ net.minecraft.world.level.levelgen.feature.package-info
- net.minecraft.world.level.levelgen.feature.PointedDripstoneFeature
+ net.minecraft.world.level.levelgen.feature.RandomBooleanSelectorFeature
- net.minecraft.world.level.levelgen.feature.RandomPatchFeature
+ net.minecraft.world.level.levelgen.feature.RandomSelectorFeature
- net.minecraft.world.level.levelgen.feature.ReplaceBlobsFeature
+ net.minecraft.world.level.levelgen.feature.ReplaceBlockFeature
- net.minecraft.world.level.levelgen.feature.RootSystemFeature
+ net.minecraft.world.level.levelgen.feature.ScatteredOreFeature
- net.minecraft.world.level.levelgen.feature.SculkPatchFeature
- net.minecraft.world.level.levelgen.feature.SeagrassFeature
+ net.minecraft.world.level.levelgen.feature.SeaPickleFeature
+ net.minecraft.world.level.levelgen.feature.SimpleBlockFeature
- net.minecraft.world.level.levelgen.feature.SimpleRandomSelectorFeature
+ net.minecraft.world.level.levelgen.feature.SnowAndFreezeFeature
- net.minecraft.world.level.levelgen.feature.SpikeFeature
+ net.minecraft.world.level.levelgen.feature.SpikeFeature$EndSpike
- net.minecraft.world.level.levelgen.feature.SpikeFeature$SpikeCacheLoader
+ net.minecraft.world.level.levelgen.feature.SpringFeature
- net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProviderType
- net.minecraft.world.level.levelgen.feature.stateproviders.DualNoiseProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.NoiseBasedStateProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.NoiseProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.NoiseThresholdProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.package-info
- net.minecraft.world.level.levelgen.feature.stateproviders.RandomizedIntStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.RotatedBlockProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.SimpleStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.WeightedStateProvider
+ net.minecraft.world.level.levelgen.feature.treedecorators.AlterGroundDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.BeehiveDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.CocoaDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.LeaveVineDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.package-info
+ net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecoratorType
+ net.minecraft.world.level.levelgen.feature.treedecorators.TrunkVineDecorator
- net.minecraft.world.level.levelgen.feature.TreeFeature
+ net.minecraft.world.level.levelgen.feature.trunkplacers.BendingTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.DarkOakTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.FancyTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.FancyTrunkPlacer$FoliageCoords
+ net.minecraft.world.level.levelgen.feature.trunkplacers.ForkingTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.GiantTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.MegaJungleTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.package-info
- net.minecraft.world.level.levelgen.feature.trunkplacers.StraightTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.TrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.TrunkPlacerType
+ net.minecraft.world.level.levelgen.feature.TwistingVinesFeature
- net.minecraft.world.level.levelgen.feature.UnderwaterMagmaFeature
+ net.minecraft.world.level.levelgen.feature.VegetationPatchFeature
- net.minecraft.world.level.levelgen.feature.VinesFeature
+ net.minecraft.world.level.levelgen.feature.VoidStartPlatformFeature
- net.minecraft.world.level.levelgen.feature.WaterloggedVegetationPatchFeature
+ net.minecraft.world.level.levelgen.feature.WeepingVinesFeature
- net.minecraft.world.level.levelgen.feature.WeightedPlacedFeature
- net.minecraft.world.level.levelgen.flat.FlatLayerInfo
+ net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorPreset
- net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorPresets
+ net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorPresets$Bootstrap
- net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorSettings
+ net.minecraft.world.level.levelgen.flat.package-info
- net.minecraft.world.level.levelgen.heightproviders.BiasedToBottomHeight
+ net.minecraft.world.level.levelgen.heightproviders.ConstantHeight
- net.minecraft.world.level.levelgen.heightproviders.HeightProvider
+ net.minecraft.world.level.levelgen.heightproviders.HeightProviderType
- net.minecraft.world.level.levelgen.heightproviders.package-info
- net.minecraft.world.level.levelgen.heightproviders.TrapezoidHeight
+ net.minecraft.world.level.levelgen.heightproviders.UniformHeight
- net.minecraft.world.level.levelgen.heightproviders.VeryBiasedToBottomHeight
+ net.minecraft.world.level.levelgen.heightproviders.WeightedListHeight
+ net.minecraft.world.level.levelgen.material.MaterialRuleList
+ net.minecraft.world.level.levelgen.material.package-info
- net.minecraft.world.level.levelgen.material.WorldGenMaterialRule
- net.minecraft.world.level.levelgen.package-info
+ net.minecraft.world.level.levelgen.placement.BiomeFilter
- net.minecraft.world.level.levelgen.placement.BlockPredicateFilter
+ net.minecraft.world.level.levelgen.placement.CarvingMaskPlacement
- net.minecraft.world.level.levelgen.placement.CaveSurface
+ net.minecraft.world.level.levelgen.placement.CountOnEveryLayerPlacement
- net.minecraft.world.level.levelgen.placement.CountPlacement
+ net.minecraft.world.level.levelgen.placement.EnvironmentScanPlacement
+ net.minecraft.world.level.levelgen.placement.HeightmapPlacement
- net.minecraft.world.level.levelgen.placement.HeightRangePlacement
- net.minecraft.world.level.levelgen.placement.InSquarePlacement
+ net.minecraft.world.level.levelgen.placement.NoiseBasedCountPlacement
- net.minecraft.world.level.levelgen.placement.NoiseThresholdCountPlacement
- net.minecraft.world.level.levelgen.placement.package-info
+ net.minecraft.world.level.levelgen.placement.PlacedFeature
- net.minecraft.world.level.levelgen.placement.PlacedFeature$test
+ net.minecraft.world.level.levelgen.placement.PlacementContext
- net.minecraft.world.level.levelgen.placement.PlacementFilter
+ net.minecraft.world.level.levelgen.placement.PlacementModifier
- net.minecraft.world.level.levelgen.placement.PlacementModifierType
+ net.minecraft.world.level.levelgen.placement.RandomOffsetPlacement
- net.minecraft.world.level.levelgen.placement.RarityFilter
+ net.minecraft.world.level.levelgen.placement.RepeatingPlacement
- net.minecraft.world.level.levelgen.placement.SurfaceRelativeThresholdFilter
+ net.minecraft.world.level.levelgen.placement.SurfaceWaterDepthFilter
+ net.minecraft.world.level.levelgen.presets.WorldPreset
- net.minecraft.world.level.levelgen.presets.WorldPresets
+ net.minecraft.world.level.levelgen.presets.WorldPresets$Bootstrap
- net.minecraft.world.level.levelgen.structure.BoundingBox
+ net.minecraft.world.level.levelgen.structure.BoundingBox$1
+ net.minecraft.world.level.levelgen.structure.BuiltinStructures
- net.minecraft.world.level.levelgen.structure.BuiltinStructureSets
- net.minecraft.world.level.levelgen.structure.LegacyStructureDataHandler
+ net.minecraft.world.level.levelgen.structure.package-info
- net.minecraft.world.level.levelgen.structure.pieces.package-info
- net.minecraft.world.level.levelgen.structure.pieces.PieceGenerator
+ net.minecraft.world.level.levelgen.structure.pieces.PieceGenerator$Context
- net.minecraft.world.level.levelgen.structure.pieces.PieceGeneratorSupplier
+ net.minecraft.world.level.levelgen.structure.pieces.PieceGeneratorSupplier$Context
- net.minecraft.world.level.levelgen.structure.pieces.PiecesContainer
+ net.minecraft.world.level.levelgen.structure.pieces.StructurePiecesBuilder
+ net.minecraft.world.level.levelgen.structure.pieces.StructurePieceSerializationContext
- net.minecraft.world.level.levelgen.structure.pieces.StructurePieceType
+ net.minecraft.world.level.levelgen.structure.pieces.StructurePieceType$ContextlessType
- net.minecraft.world.level.levelgen.structure.pieces.StructurePieceType$StructureTemplateType
+ net.minecraft.world.level.levelgen.structure.placement.ConcentricRingsStructurePlacement
- net.minecraft.world.level.levelgen.structure.placement.package-info
- net.minecraft.world.level.levelgen.structure.placement.RandomSpreadStructurePlacement
+ net.minecraft.world.level.levelgen.structure.placement.RandomSpreadType
- net.minecraft.world.level.levelgen.structure.placement.RandomSpreadType$1
+ net.minecraft.world.level.levelgen.structure.placement.StructurePlacement
- net.minecraft.world.level.levelgen.structure.placement.StructurePlacement$ExclusionZone
+ net.minecraft.world.level.levelgen.structure.placement.StructurePlacement$FrequencyReducer
- net.minecraft.world.level.levelgen.structure.placement.StructurePlacement$FrequencyReductionMethod
+ net.minecraft.world.level.levelgen.structure.placement.StructurePlacementType
+ net.minecraft.world.level.levelgen.structure.PoolElementStructurePiece
+ net.minecraft.world.level.levelgen.structure.pools.EmptyPoolElement
- net.minecraft.world.level.levelgen.structure.pools.FeaturePoolElement
+ net.minecraft.world.level.levelgen.structure.pools.JigsawJunction
- net.minecraft.world.level.levelgen.structure.pools.JigsawPlacement
+ net.minecraft.world.level.levelgen.structure.pools.JigsawPlacement$PieceFactory
- net.minecraft.world.level.levelgen.structure.pools.JigsawPlacement$PieceState
+ net.minecraft.world.level.levelgen.structure.pools.JigsawPlacement$Placer
- net.minecraft.world.level.levelgen.structure.pools.LegacySinglePoolElement
+ net.minecraft.world.level.levelgen.structure.pools.ListPoolElement
+ net.minecraft.world.level.levelgen.structure.pools.package-info
- net.minecraft.world.level.levelgen.structure.pools.SinglePoolElement
+ net.minecraft.world.level.levelgen.structure.pools.StructurePoolElement
- net.minecraft.world.level.levelgen.structure.pools.StructurePoolElementType
+ net.minecraft.world.level.levelgen.structure.pools.StructureTemplatePool
- net.minecraft.world.level.levelgen.structure.pools.StructureTemplatePool$Projection
- net.minecraft.world.level.levelgen.structure.PostPlacementProcessor
+ net.minecraft.world.level.levelgen.structure.ScatteredFeaturePiece
- net.minecraft.world.level.levelgen.structure.SinglePieceStructure
+ net.minecraft.world.level.levelgen.structure.SinglePieceStructure$PieceConstructor
- net.minecraft.world.level.levelgen.structure.Structure
+ net.minecraft.world.level.levelgen.structure.Structure$GenerationContext
- net.minecraft.world.level.levelgen.structure.Structure$GenerationStub
- net.minecraft.world.level.levelgen.structure.structures.BuriedTreasurePieces
+ net.minecraft.world.level.levelgen.structure.structures.BuriedTreasurePieces$BuriedTreasurePiece
- net.minecraft.world.level.levelgen.structure.structures.BuriedTreasureStructure
+ net.minecraft.world.level.levelgen.structure.structures.DesertPyramidPiece
- net.minecraft.world.level.levelgen.structure.structures.DesertPyramidStructure
+ net.minecraft.world.level.levelgen.structure.structures.EndCityPieces
- net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$1
+ net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$2
- net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$3
+ net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$4
- net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$EndCityPiece
+ net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$SectionGenerator
- net.minecraft.world.level.levelgen.structure.structures.EndCityStructure
+ net.minecraft.world.level.levelgen.structure.structures.IglooPieces
- net.minecraft.world.level.levelgen.structure.structures.IglooPieces$IglooPiece
+ net.minecraft.world.level.levelgen.structure.structures.IglooStructure
- net.minecraft.world.level.levelgen.structure.structures.JigsawStructure
- net.minecraft.world.level.levelgen.structure.TerrainAdjustment
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.minecraft.advancements.CriteriaTriggers +1P
```
```
XXX.data.loot.BlockLoot +1M | +1P
```
```
XXX.models.model.TextureMapping +1M
```
```
XXX.data.worldgen.ProcessorLists +3P
```
```
XXX.data.worldgen.Structures +5M | +1P
```
```
XXX.gametest.framework.GameTestHelper +1M
```
```
XXX.minecraft.sounds.SoundEvents +7P
```
```
XXX.minecraft.tags.BiomeTags +1P
```
```
XXX.minecraft.tags.ItemTags +1P -1P
```
```
XXX.minecraft.util.Mth +1M
```
```
XXX.world.entity.EntityType +1P
```
```
XXX.world.entity.HumanoidArm +3M -3M | +2P -1P
```
```
XXX.ai.behavior.BehaviorUtils +1M
```
```
XXX.animal.frog.ShootTongue +1M | +1P -1P
```
```
XXX.animal.frog.ShootTongue$State +1P
```
```
XXX.monster.warden.AngerManagement +3M -5M
```
```
XXX.monster.warden.Warden +7M -6M | -2P
```
```
XXX.monster.warden.WardenAi +1M -1M | +2P
```
```
XXX.entity.vehicle.Minecart +1M
```
```
XXX.entity.vehicle.MinecartCommandBlock +1M
```
```
XXX.entity.vehicle.MinecartFurnace +1M -1M
```
```
XXX.entity.vehicle.MinecartSpawner +1M
```
```
XXX.entity.vehicle.MinecartTNT +1M
```
```
XXX.world.level.StructureManager +1M -1M
```
```
XXX.level.biome.Biome$TemperatureModifier -2M | -1P
```
```
XXX.level.block.NoteBlock +1M -1M
```
```
XXX.level.block.SculkShriekerBlock +1M -2M | +1P
```
```
XXX.level.block.TripWireHookBlock +1M -1M
```
```
XXX.block.entity.SculkSensorBlockEntity +2M -1M
```
```
XXX.level.gameevent.GameEvent +12P -18P
```
```
XXX.gameevent.vibrations.VibrationListener$ReceivingEvent +13M -4M | +1P
```
```
XXX.level.levelgen.Beardifier +7M -3M | -2P
```
```
XXX.level.levelgen.GenerationStep$Decoration -2M | -1P
```
```
XXX.levelgen.structure.StructureSpawnOverride$BoundingBoxType -2M | -1P
```
```
XXX.structure.structures.JungleTempleStructure +1M -2M
```
```
XXX.structure.structures.MineshaftStructure +1M -1M
```
```
XXX.structure.structures.NetherFossilStructure +1M -1M
```
```
XXX.structure.structures.OceanRuinStructure$Type -2M | -1P
```
```
XXX.structure.structures.RuinedPortalStructure +2M -2M
```
```
XXX.structure.structures.ShipwreckStructure +1M -1M
```
```
XXX.structure.structures.StrongholdPieces$FillerCorridor -1M
```
```
XXX.structure.structures.StrongholdPieces$PrisonHall -1M
```
```
XXX.structure.structures.StrongholdPieces$RoomCrossing -1M
```
```
XXX.structure.structures.StrongholdPieces$StairsDown -1M
```
```
XXX.structure.structures.StrongholdPieces$Straight -1M
```
```
XXX.structure.structures.StrongholdPieces$StrongholdPiece -1M
```
```
XXX.structure.structures.StrongholdPieces$Turn -1M
```
```
XXX.structure.structures.WoodlandMansionStructure +2M -3M
```
```
XXX.structure.templatesystem.BlockRotProcessor +5M -1M | +1P
```

</details>
























































































































































































































































<details>
<summary>
net.minecraft.data.loot.BlockLoot
</summary>

```diff
- LootTable$Builder createMangroveLeavesDrops(Block)
```

</details>






















<details>
<summary>
net.minecraft.data.models.model.TextureMapping
</summary>

```diff
- TextureMapping sculkShrieker(boolean)
```

</details>





























<details>
<summary>
net.minecraft.data.worldgen.Structures
</summary>

```diff
- MobCategory lambda$static$0(MobCategory)
- Structure$StructureSettings structure(TagKey,GenerationStep$Decoration,TerrainAdjustment)
- Structure$StructureSettings structure(TagKey,Map,GenerationStep$Decoration,TerrainAdjustment)
- Structure$StructureSettings structure(TagKey,TerrainAdjustment)
- StructureSpawnOverride lambda$static$1(MobCategory)
```

</details>





















<details>
<summary>
net.minecraft.gametest.framework.GameTestHelper
</summary>

```diff
- void assertItemEntityNotPresent(Item,BlockPos,double)
```

</details>
















































































































































































































































































































































































































































<details>
<summary>
net.minecraft.util.Mth
</summary>

```diff
- float cube(float)
```

</details>
























































































































































































<details>
<summary>
net.minecraft.world.entity.HumanoidArm
</summary>

```diff
+ Component getName()
- int getId()
- String getKey()
+ String toString()
+ void <init>(String,int,Component)
- void <init>(String,int,int,String)
```

</details>





























<details>
<summary>
net.minecraft.world.entity.ai.behavior.BehaviorUtils
</summary>

```diff
- void setWalkAndLookTargetMemories(LivingEntity,PositionTracker,float,int)
```

</details>









































<details>
<summary>
net.minecraft.world.entity.animal.frog.ShootTongue
</summary>

```diff
- void eatEntity(ServerLevel,Frog)
```

</details>



































































































<details>
<summary>
net.minecraft.world.entity.monster.warden.AngerManagement
</summary>

```diff
- boolean lambda$getActiveEntity$3(Entity)
+ boolean lambda$getActiveEntity$5(Entity)
- Integer lambda$addAnger$2(int,UUID,Integer)
+ Integer lambda$addAnger$4(int,UUID,Integer)
+ Integer lambda$tick$2(UUID,Integer)
- LivingEntity lambda$getActiveEntity$4(Entity)
+ LivingEntity lambda$getActiveEntity$6(Entity)
+ void lambda$tick$3(UUID)
```

</details>


<details>
<summary>
net.minecraft.world.entity.monster.warden.Warden
</summary>

```diff
+ boolean lambda$increaseAngerAt$2(LivingEntity)
- boolean lambda$increaseAngerAt$4(LivingEntity)
+ Boolean lambda$onSignalReceive$3(Entity,LivingEntity)
- Boolean lambda$onSignalReceive$5(Entity,LivingEntity)
+ Brain$Provider brainProvider()
+ float getEarAnimation(float)
- float getTendrilAnimation(float)
- void lambda$addAdditionalSaveData$1(CompoundTag,Tag)
+ void lambda$readAdditionalSaveData$1(AngerManagement)
- void lambda$readAdditionalSaveData$2(AngerManagement)
- void lambda$readAdditionalSaveData$3(VibrationListener)
- void onSignalReceive(ServerLevel,GameEventListener,BlockPos,GameEvent,Entity,Entity,int)
+ void onSignalReceive(ServerLevel,GameEventListener,BlockPos,GameEvent,Entity,int)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.warden.WardenAi
</summary>

```diff
+ Brain makeBrain(Warden,Brain)
- Brain makeBrain(Warden,Dynamic)
```

</details>



















































<details>
<summary>
net.minecraft.world.entity.vehicle.Minecart
</summary>

```diff
- Item getDropItem()
```

</details>
<details>
<summary>
net.minecraft.world.entity.vehicle.MinecartCommandBlock
</summary>

```diff
- Item getDropItem()
```

</details>
<details>
<summary>
net.minecraft.world.entity.vehicle.MinecartFurnace
</summary>

```diff
- Item getDropItem()
+ void destroy(DamageSource)
```

</details>
<details>
<summary>
net.minecraft.world.entity.vehicle.MinecartSpawner
</summary>

```diff
- Item getDropItem()
```

</details>
<details>
<summary>
net.minecraft.world.entity.vehicle.MinecartTNT
</summary>

```diff
- Item getDropItem()
```

</details>










































































































































































































<details>
<summary>
net.minecraft.world.level.StructureManager
</summary>

```diff
- List startsForStructure(ChunkPos,Predicate)
+ List startsForStructure(SectionPos,Predicate)
```

</details>




<details>
<summary>
net.minecraft.world.level.biome.Biome$TemperatureModifier
</summary>

```diff
+ Biome$TemperatureModifier byName(String)
+ Biome$TemperatureModifier lambda$static$0(Biome$TemperatureModifier)
```

</details>





























































































































<details>
<summary>
net.minecraft.world.level.block.NoteBlock
</summary>

```diff
- void playNote(Entity,Level,BlockPos)
+ void playNote(Level,BlockPos)
```

</details>























<details>
<summary>
net.minecraft.world.level.block.SculkShriekerBlock
</summary>

```diff
- void lambda$getTicker$3(Level,BlockPos,BlockState,SculkShriekerBlockEntity)
+ void lambda$getTicker$4(Level,BlockPos,BlockState,SculkShriekerBlockEntity)
+ void lambda$shriek$3(ServerLevel,BlockPos,BlockState,WardenSpawnTracker)
```

</details>





























<details>
<summary>
net.minecraft.world.level.block.TripWireHookBlock
</summary>

```diff
- void emitState(Level,BlockPos,boolean,boolean,boolean,boolean)
+ void playSound(Level,BlockPos,boolean,boolean,boolean,boolean)
```

</details>








































<details>
<summary>
net.minecraft.world.level.block.entity.SculkSensorBlockEntity
</summary>

```diff
- void onSignalReceive(ServerLevel,GameEventListener,BlockPos,GameEvent,Entity,Entity,int)
+ void onSignalReceive(ServerLevel,GameEventListener,BlockPos,GameEvent,Entity,int)
- void onSignalSchedule()
```

</details>













































































































<details>
<summary>
net.minecraft.world.level.gameevent.vibrations.VibrationListener$ReceivingEvent
</summary>

```diff
+ App lambda$static$0(RecordCodecBuilder$Instance)
- App lambda$static$3(RecordCodecBuilder$Instance)
- boolean lambda$getProjectileOwner$5(Entity)
- Optional getProjectileOwner(ServerLevel)
+ Optional lambda$getEntity$1(ServerLevel)
- Optional lambda$getEntity$4(ServerLevel)
- Optional lambda$getProjectileOwner$7(ServerLevel)
- Optional lambda$static$0(VibrationListener$ReceivingEvent)
- Optional lambda$static$1(VibrationListener$ReceivingEvent)
- Projectile lambda$getProjectileOwner$6(Entity)
- UUID getProjectileOwner(Entity)
- UUID projectileOwnerUuid()
- VibrationListener$ReceivingEvent lambda$static$2(GameEvent,Integer,Vec3,Optional,Optional)
+ void <init>(GameEvent,int,Vec3,UUID,Entity)
- void <init>(GameEvent,int,Vec3,UUID,UUID,Entity)
- void <init>(GameEvent,int,Vec3,UUID,UUID)
+ void <init>(GameEvent,int,Vec3,UUID)
```

</details>



<details>
<summary>
net.minecraft.world.level.levelgen.Beardifier
</summary>

```diff
- Beardifier forStructuresInChunk(StructureManager,ChunkPos)
- boolean isInKernelRange(int)
- boolean lambda$forStructuresInChunk$1(Structure)
- double computeBeardContribution(int,double,int)
- double getBeardContribution(int,int,int,int)
+ double getBeardContribution(int,int,int)
- void <init>(ObjectListIterator,ObjectListIterator)
+ void <init>(StructureManager,ChunkAccess)
- void lambda$forStructuresInChunk$2(ChunkPos,ObjectList,int,int,ObjectList,StructureStart)
+ void lambda$new$1(ChunkPos,int,int,StructureStart)
```

</details>



























<details>
<summary>
net.minecraft.world.level.levelgen.GenerationStep$Decoration
</summary>

```diff
+ GenerationStep$Decoration byName(String)
+ GenerationStep$Decoration lambda$static$0(GenerationStep$Decoration)
```

</details>
































































































<details>
<summary>
net.minecraft.world.level.levelgen.structure.StructureSpawnOverride$BoundingBoxType
</summary>

```diff
+ StructureSpawnOverride$BoundingBoxType byName(String)
+ StructureSpawnOverride$BoundingBoxType[] lambda$static$0()
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.structure.structures.JungleTempleStructure
</summary>

```diff
+ App lambda$static$0(RecordCodecBuilder$Instance)
+ void <init>(HolderSet,Map,GenerationStep$Decoration,boolean)
- void <init>(Structure$StructureSettings)
```

</details>



<details>
<summary>
net.minecraft.world.level.levelgen.structure.structures.MineshaftStructure
</summary>

```diff
+ void <init>(HolderSet,Map,GenerationStep$Decoration,boolean,MineshaftStructure$Type)
- void <init>(Structure$StructureSettings,MineshaftStructure$Type)
```

</details>











<details>
<summary>
net.minecraft.world.level.levelgen.structure.structures.NetherFossilStructure
</summary>

```diff
+ void <init>(HolderSet,Map,GenerationStep$Decoration,boolean,HeightProvider)
- void <init>(Structure$StructureSettings,HeightProvider)
```

</details>














<details>
<summary>
net.minecraft.world.level.levelgen.structure.structures.OceanRuinStructure$Type
</summary>

```diff
+ OceanRuinStructure$Type byName(String)
+ OceanRuinStructure$Type lambda$static$0(OceanRuinStructure$Type)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.structure.structures.RuinedPortalStructure
</summary>

```diff
+ void <init>(HolderSet,Map,GenerationStep$Decoration,boolean,List)
+ void <init>(HolderSet,Map,GenerationStep$Decoration,boolean,RuinedPortalStructure$Setup)
- void <init>(Structure$StructureSettings,List)
- void <init>(Structure$StructureSettings,RuinedPortalStructure$Setup)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.structure.structures.ShipwreckStructure
</summary>

```diff
+ void <init>(HolderSet,Map,GenerationStep$Decoration,boolean,boolean)
- void <init>(Structure$StructureSettings,boolean)
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$FillerCorridor
</summary>

```diff
+ NoiseEffect getNoiseEffect()
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$PrisonHall
</summary>

```diff
+ NoiseEffect getNoiseEffect()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$RoomCrossing
</summary>

```diff
+ NoiseEffect getNoiseEffect()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$StairsDown
</summary>

```diff
+ NoiseEffect getNoiseEffect()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$Straight
</summary>

```diff
+ NoiseEffect getNoiseEffect()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$StrongholdPiece
</summary>

```diff
+ NoiseEffect getNoiseEffect()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$Turn
</summary>

```diff
+ NoiseEffect getNoiseEffect()
```

</details>






<details>
<summary>
net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionStructure
</summary>

```diff
+ App lambda$static$0(RecordCodecBuilder$Instance)
+ void <init>(HolderSet,Map,GenerationStep$Decoration,boolean)
- void <init>(Structure$StructureSettings)
- void lambda$findGenerationPoint$0(Structure$GenerationContext,BlockPos,Rotation,StructurePiecesBuilder)
+ void lambda$findGenerationPoint$1(Structure$GenerationContext,BlockPos,Rotation,StructurePiecesBuilder)
```

</details>



<details>
<summary>
net.minecraft.world.level.levelgen.structure.templatesystem.BlockRotProcessor
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
+ Float lambda$static$0(BlockRotProcessor)
- Float lambda$static$1(BlockRotProcessor)
- Optional lambda$static$0(BlockRotProcessor)
- void <init>(Optional,float)
- void <init>(TagKey,float)
```

</details>
































































































































































































































<h2>Client</h2>
<details>
<summary>
Classes
</summary>

```diff
- net.minecraft.client.model.AllayModel
+ net.minecraft.client.model.AnimationUtils
- net.minecraft.client.model.ArmedModel
+ net.minecraft.client.model.ArmorStandArmorModel
- net.minecraft.client.model.ArmorStandModel
+ net.minecraft.client.model.AxolotlModel
- net.minecraft.client.model.BatModel
+ net.minecraft.client.model.BeeModel
- net.minecraft.client.model.BlazeModel
+ net.minecraft.client.model.BoatModel
- net.minecraft.client.model.BookModel
+ net.minecraft.client.model.CatModel
- net.minecraft.client.model.ChestedHorseModel
+ net.minecraft.client.model.ChickenModel
- net.minecraft.client.model.CodModel
+ net.minecraft.client.model.ColorableAgeableListModel
- net.minecraft.client.model.ColorableHierarchicalModel
+ net.minecraft.client.model.CowModel
- net.minecraft.client.model.CreeperModel
+ net.minecraft.client.model.DolphinModel
- net.minecraft.client.model.dragon.DragonHeadModel
+ net.minecraft.client.model.dragon.package-info
- net.minecraft.client.model.DrownedModel
+ net.minecraft.client.model.ElytraModel
- net.minecraft.client.model.EndermanModel
+ net.minecraft.client.model.EndermiteModel
- net.minecraft.client.model.EntityModel
+ net.minecraft.client.model.EvokerFangsModel
- net.minecraft.client.model.FoxModel
+ net.minecraft.client.model.FrogModel
+ net.minecraft.client.model.geom.builders.CubeDefinition
- net.minecraft.client.model.geom.builders.CubeDeformation
+ net.minecraft.client.model.geom.builders.CubeListBuilder
- net.minecraft.client.model.geom.builders.LayerDefinition
+ net.minecraft.client.model.geom.builders.MaterialDefinition
- net.minecraft.client.model.geom.builders.MeshDefinition
+ net.minecraft.client.model.geom.builders.package-info
+ net.minecraft.client.model.geom.builders.PartDefinition
- net.minecraft.client.model.geom.builders.UVPair
- net.minecraft.client.model.geom.EntityModelSet
+ net.minecraft.client.model.geom.LayerDefinitions
- net.minecraft.client.model.geom.ModelLayerLocation
+ net.minecraft.client.model.geom.ModelLayers
- net.minecraft.client.model.geom.ModelPart
+ net.minecraft.client.model.geom.ModelPart$Cube
- net.minecraft.client.model.geom.ModelPart$Polygon
+ net.minecraft.client.model.geom.ModelPart$Vertex
- net.minecraft.client.model.geom.ModelPart$Visitor
- net.minecraft.client.model.geom.package-info
+ net.minecraft.client.model.geom.PartNames
- net.minecraft.client.model.geom.PartPose
- net.minecraft.client.model.GhastModel
+ net.minecraft.client.model.GiantZombieModel
- net.minecraft.client.model.GoatModel
+ net.minecraft.client.model.GuardianModel
- net.minecraft.client.model.HeadedModel
+ net.minecraft.client.model.HierarchicalModel
- net.minecraft.client.model.HoglinModel
+ net.minecraft.client.model.HorseModel
- net.minecraft.client.model.HumanoidModel
+ net.minecraft.client.model.HumanoidModel$1
- net.minecraft.client.model.HumanoidModel$ArmPose
+ net.minecraft.client.model.IllagerModel
- net.minecraft.client.model.IronGolemModel
+ net.minecraft.client.model.LavaSlimeModel
- net.minecraft.client.model.LeashKnotModel
+ net.minecraft.client.model.ListModel
- net.minecraft.client.model.LlamaModel
+ net.minecraft.client.model.LlamaSpitModel
- net.minecraft.client.model.MinecartModel
+ net.minecraft.client.model.Model
- net.minecraft.client.model.ModelUtils
+ net.minecraft.client.model.OcelotModel
+ net.minecraft.client.model.package-info
- net.minecraft.client.model.PandaModel
+ net.minecraft.client.model.ParrotModel
- net.minecraft.client.model.ParrotModel$1
+ net.minecraft.client.model.ParrotModel$State
- net.minecraft.client.model.PhantomModel
- net.minecraft.client.model.PiglinModel
+ net.minecraft.client.model.PigModel
+ net.minecraft.client.model.PlayerModel
- net.minecraft.client.model.PolarBearModel
+ net.minecraft.client.model.PufferfishBigModel
- net.minecraft.client.model.PufferfishMidModel
+ net.minecraft.client.model.PufferfishSmallModel
- net.minecraft.client.model.QuadrupedModel
+ net.minecraft.client.model.RabbitModel
- net.minecraft.client.model.RavagerModel
+ net.minecraft.client.model.SalmonModel
- net.minecraft.client.model.SheepFurModel
+ net.minecraft.client.model.SheepModel
- net.minecraft.client.model.ShieldModel
+ net.minecraft.client.model.ShulkerBulletModel
- net.minecraft.client.model.ShulkerModel
+ net.minecraft.client.model.SilverfishModel
- net.minecraft.client.model.SkeletonModel
+ net.minecraft.client.model.SkullModel
- net.minecraft.client.model.SkullModelBase
+ net.minecraft.client.model.SlimeModel
- net.minecraft.client.model.SnowGolemModel
+ net.minecraft.client.model.SpiderModel
- net.minecraft.client.model.SquidModel
+ net.minecraft.client.model.StriderModel
- net.minecraft.client.model.TadpoleModel
+ net.minecraft.client.model.TridentModel
- net.minecraft.client.model.TropicalFishModelA
+ net.minecraft.client.model.TropicalFishModelB
- net.minecraft.client.model.TurtleModel
+ net.minecraft.client.model.VexModel
- net.minecraft.client.model.VillagerHeadModel
+ net.minecraft.client.model.VillagerModel
- net.minecraft.client.model.WardenModel
+ net.minecraft.client.model.WitchModel
- net.minecraft.client.model.WitherBossModel
+ net.minecraft.client.model.WolfModel
- net.minecraft.client.model.ZombieModel
+ net.minecraft.client.model.ZombieVillagerModel
- net.minecraft.client.multiplayer.ClientAdvancements
+ net.minecraft.client.multiplayer.ClientAdvancements$Listener
- net.minecraft.client.multiplayer.ClientChunkCache
+ net.minecraft.client.multiplayer.ClientChunkCache$Storage
- net.minecraft.client.multiplayer.ClientHandshakePacketListenerImpl
+ net.minecraft.client.multiplayer.ClientLevel
- net.minecraft.client.multiplayer.ClientLevel$1
+ net.minecraft.client.multiplayer.ClientLevel$ClientLevelData
- net.minecraft.client.multiplayer.ClientLevel$EntityCallbacks
+ net.minecraft.client.multiplayer.ClientPacketListener
- net.minecraft.client.multiplayer.ClientPacketListener$1
+ net.minecraft.client.multiplayer.ClientSuggestionProvider
- net.minecraft.client.multiplayer.MultiPlayerGameMode
+ net.minecraft.client.multiplayer.package-info
+ net.minecraft.client.multiplayer.PlayerInfo
- net.minecraft.client.multiplayer.prediction.BlockStatePredictionHandler
+ net.minecraft.client.multiplayer.prediction.BlockStatePredictionHandler$ServerVerifiedState
+ net.minecraft.client.multiplayer.prediction.package-info
- net.minecraft.client.multiplayer.prediction.PredictiveAction
- net.minecraft.client.multiplayer.resolver.AddressCheck
+ net.minecraft.client.multiplayer.resolver.AddressCheck$1
- net.minecraft.client.multiplayer.resolver.package-info
- net.minecraft.client.multiplayer.resolver.ResolvedServerAddress
+ net.minecraft.client.multiplayer.resolver.ResolvedServerAddress$1
- net.minecraft.client.multiplayer.resolver.ServerAddress
+ net.minecraft.client.multiplayer.resolver.ServerAddressResolver
- net.minecraft.client.multiplayer.resolver.ServerNameResolver
+ net.minecraft.client.multiplayer.resolver.ServerRedirectHandler
- net.minecraft.client.multiplayer.ServerData
+ net.minecraft.client.multiplayer.ServerData$ServerPackStatus
- net.minecraft.client.multiplayer.ServerList
+ net.minecraft.client.multiplayer.ServerStatusPinger
- net.minecraft.client.multiplayer.ServerStatusPinger$1
+ net.minecraft.client.multiplayer.ServerStatusPinger$2
- net.minecraft.client.multiplayer.ServerStatusPinger$2$1
+ net.minecraft.client.OptionInstance$AltEnum
- net.minecraft.client.OptionInstance$CaptionBasedToString
- net.minecraft.client.OptionInstance$CycleableValueSet
- net.minecraft.client.OptionInstance$SliderableOrCyclableValueSet
+ net.minecraft.client.OptionInstance$SliderableValueSet
- net.minecraft.client.OptionInstance$TooltipSupplier
+ net.minecraft.client.package-info
- net.minecraft.client.particle.AshParticle
+ net.minecraft.client.particle.AshParticle$Provider
- net.minecraft.client.particle.AttackSweepParticle
+ net.minecraft.client.particle.AttackSweepParticle$Provider
- net.minecraft.client.particle.BaseAshSmokeParticle
+ net.minecraft.client.particle.BlockMarker
- net.minecraft.client.particle.BlockMarker$Provider
+ net.minecraft.client.particle.BreakingItemParticle
- net.minecraft.client.particle.BreakingItemParticle$Provider
+ net.minecraft.client.particle.BreakingItemParticle$SlimeProvider
- net.minecraft.client.particle.BreakingItemParticle$SnowballProvider
+ net.minecraft.client.particle.BubbleColumnUpParticle
- net.minecraft.client.particle.BubbleColumnUpParticle$Provider
+ net.minecraft.client.particle.BubbleParticle
- net.minecraft.client.particle.BubbleParticle$Provider
+ net.minecraft.client.particle.BubblePopParticle
- net.minecraft.client.particle.BubblePopParticle$Provider
+ net.minecraft.client.particle.CampfireSmokeParticle
- net.minecraft.client.particle.CampfireSmokeParticle$CosyProvider
+ net.minecraft.client.particle.CampfireSmokeParticle$SignalProvider
- net.minecraft.client.particle.CritParticle
+ net.minecraft.client.particle.CritParticle$DamageIndicatorProvider
- net.minecraft.client.particle.CritParticle$MagicProvider
+ net.minecraft.client.particle.CritParticle$Provider
- net.minecraft.client.particle.DragonBreathParticle
+ net.minecraft.client.particle.DragonBreathParticle$Provider
- net.minecraft.client.particle.DripParticle
+ net.minecraft.client.particle.DripParticle$CoolingDripHangParticle
- net.minecraft.client.particle.DripParticle$DripHangParticle
+ net.minecraft.client.particle.DripParticle$DripLandParticle
- net.minecraft.client.particle.DripParticle$DripstoneFallAndLandParticle
+ net.minecraft.client.particle.DripParticle$DripstoneLavaFallProvider
- net.minecraft.client.particle.DripParticle$DripstoneLavaHangProvider
+ net.minecraft.client.particle.DripParticle$DripstoneWaterFallProvider
- net.minecraft.client.particle.DripParticle$DripstoneWaterHangProvider
+ net.minecraft.client.particle.DripParticle$FallAndLandParticle
- net.minecraft.client.particle.DripParticle$FallingParticle
+ net.minecraft.client.particle.DripParticle$HoneyFallAndLandParticle
- net.minecraft.client.particle.DripParticle$HoneyFallProvider
+ net.minecraft.client.particle.DripParticle$HoneyHangProvider
- net.minecraft.client.particle.DripParticle$HoneyLandProvider
+ net.minecraft.client.particle.DripParticle$LavaFallProvider
- net.minecraft.client.particle.DripParticle$LavaHangProvider
+ net.minecraft.client.particle.DripParticle$LavaLandProvider
- net.minecraft.client.particle.DripParticle$NectarFallProvider
+ net.minecraft.client.particle.DripParticle$ObsidianTearFallProvider
- net.minecraft.client.particle.DripParticle$ObsidianTearHangProvider
+ net.minecraft.client.particle.DripParticle$ObsidianTearLandProvider
- net.minecraft.client.particle.DripParticle$SporeBlossomFallProvider
+ net.minecraft.client.particle.DripParticle$WaterFallProvider
- net.minecraft.client.particle.DripParticle$WaterHangProvider
+ net.minecraft.client.particle.DustColorTransitionParticle
- net.minecraft.client.particle.DustColorTransitionParticle$Provider
+ net.minecraft.client.particle.DustParticle
- net.minecraft.client.particle.DustParticle$Provider
+ net.minecraft.client.particle.DustParticleBase
- net.minecraft.client.particle.EnchantmentTableParticle
+ net.minecraft.client.particle.EnchantmentTableParticle$NautilusProvider
- net.minecraft.client.particle.EnchantmentTableParticle$Provider
+ net.minecraft.client.particle.EndRodParticle
- net.minecraft.client.particle.EndRodParticle$Provider
+ net.minecraft.client.particle.ExplodeParticle
- net.minecraft.client.particle.ExplodeParticle$Provider
+ net.minecraft.client.particle.FallingDustParticle
- net.minecraft.client.particle.FallingDustParticle$Provider
+ net.minecraft.client.particle.FireworkParticles
- net.minecraft.client.particle.FireworkParticles$1
+ net.minecraft.client.particle.FireworkParticles$FlashProvider
- net.minecraft.client.particle.FireworkParticles$OverlayParticle
+ net.minecraft.client.particle.FireworkParticles$SparkParticle
- net.minecraft.client.particle.FireworkParticles$SparkProvider
+ net.minecraft.client.particle.FireworkParticles$Starter
- net.minecraft.client.particle.FlameParticle
+ net.minecraft.client.particle.FlameParticle$Provider
- net.minecraft.client.particle.FlameParticle$SmallFlameProvider
+ net.minecraft.client.particle.GlowParticle
- net.minecraft.client.particle.GlowParticle$AllayDustProvider
- net.minecraft.client.renderer.entity.AllayRenderer
+ net.minecraft.client.renderer.entity.ArmorStandRenderer
- net.minecraft.client.renderer.entity.ArrowRenderer
+ net.minecraft.client.renderer.entity.AxolotlRenderer
- net.minecraft.client.renderer.entity.BatRenderer
+ net.minecraft.client.renderer.entity.BeeRenderer
- net.minecraft.client.renderer.entity.BlazeRenderer
+ net.minecraft.client.renderer.entity.BoatRenderer
- net.minecraft.client.renderer.entity.CatRenderer
+ net.minecraft.client.renderer.entity.CaveSpiderRenderer
- net.minecraft.client.renderer.entity.ChestedHorseRenderer
+ net.minecraft.client.renderer.entity.ChickenRenderer
- net.minecraft.client.renderer.entity.CodRenderer
+ net.minecraft.client.renderer.entity.CowRenderer
- net.minecraft.client.renderer.entity.CreeperRenderer
+ net.minecraft.client.renderer.entity.DolphinRenderer
- net.minecraft.client.renderer.entity.DragonFireballRenderer
+ net.minecraft.client.renderer.entity.DrownedRenderer
- net.minecraft.client.renderer.entity.ElderGuardianRenderer
+ net.minecraft.client.renderer.entity.EndCrystalRenderer
- net.minecraft.client.renderer.entity.EnderDragonRenderer
+ net.minecraft.client.renderer.entity.EnderDragonRenderer$DragonModel
- net.minecraft.client.renderer.entity.EndermanRenderer
+ net.minecraft.client.renderer.entity.EndermiteRenderer
- net.minecraft.client.renderer.entity.EntityRenderDispatcher
+ net.minecraft.client.renderer.entity.EntityRenderer
- net.minecraft.client.renderer.entity.EntityRendererProvider
+ net.minecraft.client.renderer.entity.EntityRendererProvider$Context
- net.minecraft.client.renderer.entity.EntityRenderers
+ net.minecraft.client.renderer.entity.EvokerFangsRenderer
- net.minecraft.client.renderer.entity.EvokerRenderer
+ net.minecraft.client.renderer.entity.EvokerRenderer$1
- net.minecraft.client.renderer.entity.ExperienceOrbRenderer
+ net.minecraft.client.renderer.entity.FallingBlockRenderer
- net.minecraft.client.renderer.entity.FireworkEntityRenderer
+ net.minecraft.client.renderer.entity.FishingHookRenderer
- net.minecraft.client.renderer.entity.FoxRenderer
+ net.minecraft.client.renderer.entity.FrogRenderer
- net.minecraft.client.renderer.entity.GhastRenderer
+ net.minecraft.client.renderer.entity.GiantMobRenderer
- net.minecraft.client.renderer.entity.GlowSquidRenderer
+ net.minecraft.client.renderer.entity.GoatRenderer
- net.minecraft.client.renderer.entity.GuardianRenderer
+ net.minecraft.client.renderer.entity.HoglinRenderer
- net.minecraft.client.renderer.entity.HorseRenderer
+ net.minecraft.client.renderer.entity.HumanoidMobRenderer
- net.minecraft.client.renderer.entity.HuskRenderer
+ net.minecraft.client.renderer.entity.IllagerRenderer
- net.minecraft.client.renderer.entity.IllusionerRenderer
+ net.minecraft.client.renderer.entity.IllusionerRenderer$1
- net.minecraft.client.renderer.entity.IronGolemRenderer
+ net.minecraft.client.renderer.entity.ItemEntityRenderer
- net.minecraft.client.renderer.entity.ItemFrameRenderer
+ net.minecraft.client.renderer.entity.ItemRenderer
- net.minecraft.client.renderer.entity.layers.ArrowLayer
+ net.minecraft.client.renderer.entity.layers.BeeStingerLayer
- net.minecraft.client.renderer.entity.layers.CapeLayer
+ net.minecraft.client.renderer.entity.layers.CarriedBlockLayer
- net.minecraft.client.renderer.entity.layers.CatCollarLayer
+ net.minecraft.client.renderer.entity.layers.CreeperPowerLayer
- net.minecraft.client.renderer.entity.layers.CrossedArmsItemLayer
+ net.minecraft.client.renderer.entity.layers.CustomHeadLayer
- net.minecraft.client.renderer.entity.layers.Deadmau5EarsLayer
+ net.minecraft.client.renderer.entity.layers.DolphinCarryingItemLayer
- net.minecraft.client.renderer.entity.layers.DrownedOuterLayer
+ net.minecraft.client.renderer.entity.layers.ElytraLayer
- net.minecraft.client.renderer.entity.layers.EnderEyesLayer
+ net.minecraft.client.renderer.entity.layers.EnergySwirlLayer
- net.minecraft.client.renderer.entity.layers.EyesLayer
+ net.minecraft.client.renderer.entity.layers.FoxHeldItemLayer
- net.minecraft.client.renderer.entity.layers.HorseArmorLayer
+ net.minecraft.client.renderer.entity.layers.HorseMarkingLayer
- net.minecraft.client.renderer.entity.layers.HumanoidArmorLayer
+ net.minecraft.client.renderer.entity.layers.HumanoidArmorLayer$1
- net.minecraft.client.renderer.entity.layers.IronGolemCrackinessLayer
+ net.minecraft.client.renderer.entity.layers.IronGolemFlowerLayer
- net.minecraft.client.renderer.entity.layers.ItemInHandLayer
+ net.minecraft.client.renderer.entity.layers.LlamaDecorLayer
- net.minecraft.client.renderer.entity.layers.MushroomCowMushroomLayer
+ net.minecraft.client.renderer.entity.layers.PandaHoldsItemLayer
- net.minecraft.client.renderer.entity.layers.ParrotOnShoulderLayer
+ net.minecraft.client.renderer.entity.layers.PhantomEyesLayer
- net.minecraft.client.renderer.entity.layers.PlayerItemInHandLayer
+ net.minecraft.client.renderer.entity.layers.RenderLayer
- net.minecraft.client.renderer.entity.layers.SaddleLayer
+ net.minecraft.client.renderer.entity.layers.SheepFurLayer
- net.minecraft.client.renderer.entity.layers.ShulkerHeadLayer
+ net.minecraft.client.renderer.entity.layers.SlimeOuterLayer
- net.minecraft.client.renderer.entity.layers.SnowGolemHeadLayer
+ net.minecraft.client.renderer.entity.layers.SpiderEyesLayer
- net.minecraft.client.renderer.entity.layers.SpinAttackEffectLayer
+ net.minecraft.client.renderer.entity.layers.StrayClothingLayer
- net.minecraft.client.renderer.entity.layers.StuckInBodyLayer
+ net.minecraft.client.renderer.entity.layers.TropicalFishPatternLayer
- net.minecraft.client.renderer.entity.layers.VillagerProfessionLayer
+ net.minecraft.client.renderer.entity.layers.WardenEmissiveLayer
- net.minecraft.client.renderer.entity.layers.WardenEmissiveLayer$AlphaFunction
- net.minecraft.client.renderer.entity.LeashKnotRenderer
+ net.minecraft.client.renderer.entity.LightningBoltRenderer
- net.minecraft.client.renderer.entity.LivingEntityRenderer
+ net.minecraft.client.renderer.entity.LivingEntityRenderer$1
- net.minecraft.client.renderer.entity.LlamaRenderer
+ net.minecraft.client.renderer.entity.LlamaSpitRenderer
- net.minecraft.client.renderer.entity.MagmaCubeRenderer
+ net.minecraft.client.renderer.entity.MinecartRenderer
- net.minecraft.client.renderer.entity.MobRenderer
+ net.minecraft.client.renderer.entity.MushroomCowRenderer
- net.minecraft.client.renderer.entity.NoopRenderer
+ net.minecraft.client.renderer.entity.OcelotRenderer
- net.minecraft.client.renderer.entity.PaintingRenderer
+ net.minecraft.client.renderer.entity.PandaRenderer
- net.minecraft.client.renderer.entity.ParrotRenderer
+ net.minecraft.client.renderer.entity.PhantomRenderer
+ net.minecraft.client.renderer.entity.PiglinRenderer
- net.minecraft.client.renderer.entity.PigRenderer
- net.minecraft.client.renderer.entity.PillagerRenderer
+ net.minecraft.client.renderer.entity.PolarBearRenderer
- net.minecraft.client.renderer.entity.PufferfishRenderer
+ net.minecraft.client.renderer.entity.RabbitRenderer
- net.minecraft.client.renderer.entity.RavagerRenderer
+ net.minecraft.client.renderer.entity.RenderLayerParent
- net.minecraft.client.renderer.entity.SalmonRenderer
+ net.minecraft.client.renderer.entity.SheepRenderer
- net.minecraft.client.renderer.entity.ShulkerBulletRenderer
+ net.minecraft.client.renderer.entity.ShulkerRenderer
- net.minecraft.client.renderer.entity.SilverfishRenderer
+ net.minecraft.client.renderer.entity.SkeletonRenderer
- net.minecraft.client.renderer.entity.SlimeRenderer
+ net.minecraft.client.renderer.entity.SnowGolemRenderer
- net.minecraft.client.renderer.entity.SpectralArrowRenderer
+ net.minecraft.client.renderer.entity.SpiderRenderer
- net.minecraft.client.renderer.entity.SquidRenderer
+ net.minecraft.client.renderer.entity.StrayRenderer
- net.minecraft.client.renderer.entity.StriderRenderer
+ net.minecraft.client.renderer.entity.TadpoleRenderer
- net.minecraft.client.renderer.entity.ThrownItemRenderer
+ net.minecraft.client.renderer.entity.ThrownTridentRenderer
- net.minecraft.client.renderer.entity.TippableArrowRenderer
+ net.minecraft.client.renderer.entity.TntMinecartRenderer
- net.minecraft.client.renderer.entity.TntRenderer
+ net.minecraft.client.renderer.entity.TropicalFishRenderer
- net.minecraft.client.renderer.entity.TurtleRenderer
+ net.minecraft.client.renderer.entity.UndeadHorseRenderer
- net.minecraft.client.renderer.entity.VexRenderer
+ net.minecraft.client.renderer.entity.VillagerRenderer
- net.minecraft.client.renderer.entity.VindicatorRenderer
+ net.minecraft.client.renderer.entity.VindicatorRenderer$1
- net.minecraft.client.renderer.entity.WanderingTraderRenderer
+ net.minecraft.client.renderer.entity.WardenRenderer
- net.minecraft.client.renderer.entity.WitchRenderer
+ net.minecraft.client.renderer.entity.WitherBossRenderer
- net.minecraft.client.renderer.entity.WitherSkeletonRenderer
+ net.minecraft.client.renderer.entity.WitherSkullRenderer
- net.minecraft.client.renderer.entity.WolfRenderer
+ net.minecraft.client.renderer.entity.ZoglinRenderer
- net.minecraft.client.renderer.entity.ZombieRenderer
+ net.minecraft.client.renderer.entity.ZombieVillagerRenderer
- net.minecraft.data.worldgen.AncientCityStructurePools
- net.minecraft.util.datafix.fixes.package-info
- net.minecraft.util.datafix.fixes.SimplestEntityRenameFix
+ net.minecraft.util.datafix.fixes.SpawnerDataFix
- net.minecraft.util.datafix.fixes.StatsCounterFix
+ net.minecraft.util.datafix.fixes.StatsRenameFix
- net.minecraft.util.datafix.fixes.StriderGravityFix
+ net.minecraft.util.datafix.fixes.StructureReferenceCountFix
+ net.minecraft.util.datafix.fixes.StructuresBecomeConfiguredFix
- net.minecraft.util.datafix.fixes.StructuresBecomeConfiguredFix$Conversion
- net.minecraft.util.datafix.fixes.StructureSettingsFlattenFix
+ net.minecraft.util.datafix.fixes.TeamDisplayNameFix
- net.minecraft.util.datafix.fixes.TrappedChestBlockEntityFix
+ net.minecraft.util.datafix.fixes.TrappedChestBlockEntityFix$TrappedChestSection
- net.minecraft.util.datafix.fixes.VillagerDataFix
+ net.minecraft.util.datafix.fixes.VillagerFollowRangeFix
- net.minecraft.util.datafix.fixes.VillagerRebuildLevelAndXpFix
+ net.minecraft.util.datafix.fixes.VillagerTradeFix
- net.minecraft.util.datafix.fixes.WallPropertyFix
+ net.minecraft.util.datafix.fixes.WeaponSmithChestLootTableFix
- net.minecraft.util.datafix.fixes.WorldGenSettingsDisallowOldCustomWorldsFix
+ net.minecraft.util.datafix.fixes.WorldGenSettingsFix
- net.minecraft.util.datafix.fixes.WorldGenSettingsFix$StructureFeatureConfiguration
+ net.minecraft.util.datafix.fixes.WorldGenSettingsHeightAndBiomeFix
- net.minecraft.util.datafix.fixes.WriteAndReadFix
+ net.minecraft.util.datafix.fixes.ZombieVillagerRebuildXpFix
+ net.minecraft.util.datafix.package-info
- net.minecraft.util.datafix.schemas.NamespacedSchema
+ net.minecraft.util.datafix.schemas.NamespacedSchema$1
- net.minecraft.util.datafix.schemas.V100
+ net.minecraft.util.datafix.schemas.V102
- net.minecraft.util.datafix.schemas.V1022
+ net.minecraft.util.datafix.schemas.V106
- net.minecraft.util.datafix.schemas.V107
+ net.minecraft.util.datafix.schemas.V1125
- net.minecraft.util.datafix.schemas.V135
+ net.minecraft.util.datafix.schemas.V143
- net.minecraft.util.datafix.schemas.V1451
+ net.minecraft.util.datafix.schemas.V1451_1
- net.minecraft.util.datafix.schemas.V1451_2
+ net.minecraft.util.datafix.schemas.V1451_3
- net.minecraft.util.datafix.schemas.V1451_4
+ net.minecraft.util.datafix.schemas.V1451_5
- net.minecraft.util.datafix.schemas.V1451_6
+ net.minecraft.util.datafix.schemas.V1451_6$1
- net.minecraft.util.datafix.schemas.V1451_6$2
+ net.minecraft.util.datafix.schemas.V1451_7
- net.minecraft.util.datafix.schemas.V1460
+ net.minecraft.util.datafix.schemas.V1466
- net.minecraft.util.datafix.schemas.V1470
+ net.minecraft.util.datafix.schemas.V1481
- net.minecraft.util.datafix.schemas.V1483
+ net.minecraft.util.datafix.schemas.V1486
- net.minecraft.util.datafix.schemas.V1510
+ net.minecraft.util.datafix.schemas.V1800
- net.minecraft.util.datafix.schemas.V1801
+ net.minecraft.util.datafix.schemas.V1904
- net.minecraft.util.datafix.schemas.V1906
+ net.minecraft.util.datafix.schemas.V1909
- net.minecraft.util.datafix.schemas.V1920
+ net.minecraft.util.datafix.schemas.V1928
- net.minecraft.util.datafix.schemas.V1929
+ net.minecraft.util.datafix.schemas.V1931
- net.minecraft.util.datafix.schemas.V2100
+ net.minecraft.util.datafix.schemas.V2501
- net.minecraft.util.datafix.schemas.V2502
+ net.minecraft.util.datafix.schemas.V2505
- net.minecraft.util.datafix.schemas.V2509
+ net.minecraft.util.datafix.schemas.V2519
- net.minecraft.util.datafix.schemas.V2522
+ net.minecraft.util.datafix.schemas.V2551
- net.minecraft.util.datafix.schemas.V2568
+ net.minecraft.util.datafix.schemas.V2571
- net.minecraft.util.datafix.schemas.V2684
+ net.minecraft.util.datafix.schemas.V2686
- net.minecraft.util.datafix.schemas.V2688
+ net.minecraft.util.datafix.schemas.V2704
- net.minecraft.util.datafix.schemas.V2707
+ net.minecraft.util.datafix.schemas.V2831
- net.minecraft.util.datafix.schemas.V2832
+ net.minecraft.util.datafix.schemas.V2842
- net.minecraft.util.datafix.schemas.V3076
+ net.minecraft.util.datafix.schemas.V3078
- net.minecraft.util.datafix.schemas.V3081
+ net.minecraft.util.datafix.schemas.V3082
- net.minecraft.util.datafix.schemas.V3083
- net.minecraft.util.OptionEnum
+ net.minecraft.util.ParticleUtils
- net.minecraft.util.ProgressListener
+ net.minecraft.util.SimpleBitStorage
- net.minecraft.util.SimpleBitStorage$InitializationException
+ net.minecraft.util.SmoothDouble
- net.minecraft.util.SortedArraySet
+ net.minecraft.util.SortedArraySet$ArrayIterator
- net.minecraft.util.SpawnUtil
+ net.minecraft.util.StringDecomposer
- net.minecraft.util.StringRepresentable
+ net.minecraft.util.StringRepresentable$1
- net.minecraft.util.StringRepresentable$EnumCodec
- net.minecraft.world.entity.ai.behavior.FlyingRandomStroll
+ net.minecraft.world.entity.ai.behavior.FollowTemptation
- net.minecraft.world.entity.ai.behavior.GateBehavior
+ net.minecraft.world.entity.ai.behavior.GateBehavior$OrderPolicy
- net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy
+ net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$1
- net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$2
+ net.minecraft.world.entity.ai.behavior.GiveGiftToHero
- net.minecraft.world.entity.ai.behavior.GoAndGiveItemsToTarget
+ net.minecraft.world.entity.ai.behavior.package-info
- net.minecraft.world.entity.ai.behavior.StayCloseToTarget
+ net.minecraft.world.entity.ai.behavior.StopAttackingIfTargetInvalid
- net.minecraft.world.entity.ai.behavior.StopBeingAngryIfTargetDead
+ net.minecraft.world.entity.ai.behavior.StrollAroundPoi
- net.minecraft.world.entity.ai.behavior.StrollToPoi
+ net.minecraft.world.entity.ai.behavior.StrollToPoiList
- net.minecraft.world.entity.ai.behavior.Swim
+ net.minecraft.world.entity.ai.behavior.TradeWithVillager
- net.minecraft.world.entity.ai.behavior.TryFindLand
+ net.minecraft.world.entity.ai.behavior.TryFindLandNearWater
- net.minecraft.world.entity.ai.behavior.TryFindWater
+ net.minecraft.world.entity.ai.behavior.TryLaySpawnOnWaterNearLand
- net.minecraft.world.entity.ai.behavior.UpdateActivityFromSchedule
+ net.minecraft.world.entity.ai.behavior.UseBonemeal
- net.minecraft.world.entity.ai.behavior.ValidateNearbyPoi
+ net.minecraft.world.entity.ai.behavior.VictoryStroll
- net.minecraft.world.entity.ai.behavior.VillageBoundRandomStroll
+ net.minecraft.world.entity.ai.behavior.VillagerCalmDown
- net.minecraft.world.entity.ai.behavior.VillagerGoalPackages
+ net.minecraft.world.entity.ai.behavior.VillagerMakeLove
- net.minecraft.world.entity.ai.behavior.VillagerPanicTrigger
+ net.minecraft.world.entity.ai.behavior.WakeUp
- net.minecraft.world.entity.ai.behavior.WorkAtComposter
+ net.minecraft.world.entity.ai.behavior.WorkAtPoi
- net.minecraft.world.entity.ai.behavior.YieldJobSite
- net.minecraft.world.entity.ai.control.BodyRotationControl
+ net.minecraft.world.entity.ai.control.Control
- net.minecraft.world.entity.ai.control.FlyingMoveControl
+ net.minecraft.world.entity.ai.control.JumpControl
- net.minecraft.world.entity.ai.control.LookControl
+ net.minecraft.world.entity.ai.control.MoveControl
- net.minecraft.world.entity.ai.control.MoveControl$Operation
+ net.minecraft.world.entity.ai.control.package-info
+ net.minecraft.world.entity.ai.control.SmoothSwimmingLookControl
- net.minecraft.world.entity.ai.control.SmoothSwimmingMoveControl
- net.minecraft.world.entity.ai.goal.AvoidEntityGoal
+ net.minecraft.world.entity.ai.goal.BegGoal
- net.minecraft.world.entity.ai.goal.BoatGoals
+ net.minecraft.world.entity.ai.goal.BreakDoorGoal
- net.minecraft.world.entity.ai.goal.BreathAirGoal
+ net.minecraft.world.entity.ai.goal.BreedGoal
- net.minecraft.world.entity.ai.goal.CatLieOnBedGoal
+ net.minecraft.world.entity.ai.goal.CatSitOnBlockGoal
- net.minecraft.world.entity.ai.goal.ClimbOnTopOfPowderSnowGoal
+ net.minecraft.world.entity.ai.goal.DolphinJumpGoal
- net.minecraft.world.entity.ai.goal.DoorInteractGoal
+ net.minecraft.world.entity.ai.goal.EatBlockGoal
- net.minecraft.world.entity.ai.goal.FleeSunGoal
+ net.minecraft.world.entity.ai.goal.FloatGoal
- net.minecraft.world.entity.ai.goal.FollowBoatGoal
+ net.minecraft.world.entity.ai.goal.FollowFlockLeaderGoal
- net.minecraft.world.entity.ai.goal.FollowMobGoal
+ net.minecraft.world.entity.ai.goal.FollowOwnerGoal
- net.minecraft.world.entity.ai.goal.FollowParentGoal
+ net.minecraft.world.entity.ai.goal.Goal
- net.minecraft.world.entity.ai.goal.Goal$Flag
+ net.minecraft.world.entity.ai.goal.GoalSelector
- net.minecraft.world.entity.ai.goal.GoalSelector$1
+ net.minecraft.world.entity.ai.goal.GoalSelector$2
- net.minecraft.world.entity.ai.goal.GolemRandomStrollInVillageGoal
+ net.minecraft.world.entity.ai.goal.InteractGoal
- net.minecraft.world.entity.ai.goal.JumpGoal
+ net.minecraft.world.entity.ai.goal.LandOnOwnersShoulderGoal
- net.minecraft.world.entity.ai.goal.LeapAtTargetGoal
+ net.minecraft.world.entity.ai.goal.LlamaFollowCaravanGoal
- net.minecraft.world.entity.ai.goal.LookAtPlayerGoal
+ net.minecraft.world.entity.ai.goal.LookAtTradingPlayerGoal
- net.minecraft.world.entity.ai.goal.MeleeAttackGoal
+ net.minecraft.world.entity.ai.goal.MoveBackToVillageGoal
- net.minecraft.world.entity.ai.goal.MoveThroughVillageGoal
+ net.minecraft.world.entity.ai.goal.MoveToBlockGoal
- net.minecraft.world.entity.ai.goal.MoveTowardsRestrictionGoal
+ net.minecraft.world.entity.ai.goal.MoveTowardsTargetGoal
- net.minecraft.world.entity.ai.goal.OcelotAttackGoal
+ net.minecraft.world.entity.ai.goal.OfferFlowerGoal
- net.minecraft.world.entity.ai.goal.OpenDoorGoal
- net.minecraft.world.entity.ai.goal.package-info
+ net.minecraft.world.entity.ai.goal.PanicGoal
- net.minecraft.world.entity.ai.goal.PathfindToRaidGoal
+ net.minecraft.world.entity.ai.goal.RandomLookAroundGoal
- net.minecraft.world.entity.ai.goal.RandomStrollGoal
+ net.minecraft.world.entity.ai.goal.RandomSwimmingGoal
- net.minecraft.world.entity.ai.goal.RangedAttackGoal
+ net.minecraft.world.entity.ai.goal.RangedBowAttackGoal
- net.minecraft.world.entity.ai.goal.RangedCrossbowAttackGoal
+ net.minecraft.world.entity.ai.goal.RangedCrossbowAttackGoal$CrossbowState
- net.minecraft.world.entity.ai.goal.RemoveBlockGoal
+ net.minecraft.world.entity.ai.goal.RestrictSunGoal
- net.minecraft.world.entity.ai.goal.RunAroundLikeCrazyGoal
+ net.minecraft.world.entity.ai.goal.SitWhenOrderedToGoal
- net.minecraft.world.entity.ai.goal.StrollThroughVillageGoal
+ net.minecraft.world.entity.ai.goal.SwellGoal
+ net.minecraft.world.entity.ai.goal.target.DefendVillageTargetGoal
- net.minecraft.world.entity.ai.goal.target.HurtByTargetGoal
+ net.minecraft.world.entity.ai.goal.target.NearestAttackableTargetGoal
- net.minecraft.world.entity.ai.goal.target.NearestAttackableWitchTargetGoal
+ net.minecraft.world.entity.ai.goal.target.NearestHealableRaiderTargetGoal
- net.minecraft.world.entity.ai.goal.target.NonTameRandomTargetGoal
+ net.minecraft.world.entity.ai.goal.target.OwnerHurtByTargetGoal
- net.minecraft.world.entity.ai.goal.target.OwnerHurtTargetGoal
+ net.minecraft.world.entity.ai.goal.target.package-info
+ net.minecraft.world.entity.ai.goal.target.ResetUniversalAngerTargetGoal
- net.minecraft.world.entity.ai.goal.target.TargetGoal
- net.minecraft.world.entity.ai.goal.TemptGoal
+ net.minecraft.world.entity.ai.goal.TradeWithPlayerGoal
- net.minecraft.world.entity.ai.goal.TryFindWaterGoal
+ net.minecraft.world.entity.ai.goal.UseItemGoal
- net.minecraft.world.entity.ai.goal.WaterAvoidingRandomFlyingGoal
+ net.minecraft.world.entity.ai.goal.WaterAvoidingRandomStrollGoal
- net.minecraft.world.entity.ai.goal.WrappedGoal
+ net.minecraft.world.entity.ai.goal.ZombieAttackGoal
- net.minecraft.world.entity.ai.gossip.GossipContainer
+ net.minecraft.world.entity.ai.gossip.GossipContainer$EntityGossips
- net.minecraft.world.entity.ai.gossip.GossipContainer$GossipEntry
+ net.minecraft.world.entity.ai.gossip.GossipType
- net.minecraft.world.entity.ai.gossip.package-info
+ net.minecraft.world.entity.ai.memory.ExpirableValue
- net.minecraft.world.entity.ai.memory.MemoryModuleType
+ net.minecraft.world.entity.ai.memory.MemoryStatus
- net.minecraft.world.entity.ai.memory.NearestVisibleLivingEntities
- net.minecraft.world.entity.ai.memory.package-info
+ net.minecraft.world.entity.ai.memory.WalkTarget
+ net.minecraft.world.entity.ai.navigation.FlyingPathNavigation
- net.minecraft.world.entity.ai.navigation.GroundPathNavigation
- net.minecraft.world.entity.ai.navigation.package-info
+ net.minecraft.world.entity.ai.navigation.PathNavigation
- net.minecraft.world.entity.ai.navigation.WallClimberNavigation
+ net.minecraft.world.entity.ai.navigation.WaterBoundPathNavigation
+ net.minecraft.world.entity.ai.package-info
- net.minecraft.world.entity.ai.sensing.AdultSensor
+ net.minecraft.world.entity.ai.sensing.AxolotlAttackablesSensor
- net.minecraft.world.entity.ai.sensing.DummySensor
+ net.minecraft.world.entity.ai.sensing.FrogAttackablesSensor
- net.minecraft.world.entity.ai.sensing.GolemSensor
+ net.minecraft.world.entity.ai.sensing.HoglinSpecificSensor
- net.minecraft.world.entity.ai.sensing.HurtBySensor
+ net.minecraft.world.entity.ai.sensing.IsInWaterSensor
- net.minecraft.world.entity.ai.sensing.NearestBedSensor
+ net.minecraft.world.entity.ai.sensing.NearestItemSensor
- net.minecraft.world.entity.ai.sensing.NearestLivingEntitySensor
+ net.minecraft.world.entity.ai.sensing.NearestVisibleLivingEntitySensor
+ net.minecraft.world.entity.ai.sensing.package-info
- net.minecraft.world.entity.ai.sensing.PiglinBruteSpecificSensor
+ net.minecraft.world.entity.ai.sensing.PiglinSpecificSensor
- net.minecraft.world.entity.ai.sensing.PlayerSensor
+ net.minecraft.world.entity.ai.sensing.SecondaryPoiSensor
- net.minecraft.world.entity.ai.sensing.Sensing
+ net.minecraft.world.entity.ai.sensing.Sensor
- net.minecraft.world.entity.ai.sensing.SensorType
+ net.minecraft.world.entity.ai.sensing.TemptingSensor
- net.minecraft.world.entity.ai.sensing.VillagerBabiesSensor
+ net.minecraft.world.entity.ai.sensing.VillagerHostilesSensor
- net.minecraft.world.entity.ai.sensing.WardenEntitySensor
+ net.minecraft.world.entity.ai.targeting.package-info
- net.minecraft.world.entity.ai.targeting.TargetingConditions
- net.minecraft.world.entity.ai.util.AirAndWaterRandomPos
+ net.minecraft.world.entity.ai.util.AirRandomPos
- net.minecraft.world.entity.ai.util.DefaultRandomPos
+ net.minecraft.world.entity.ai.util.GoalUtils
- net.minecraft.world.entity.ai.util.HoverRandomPos
+ net.minecraft.world.entity.ai.util.LandRandomPos
+ net.minecraft.world.entity.ai.util.package-info
- net.minecraft.world.entity.ai.util.RandomPos
- net.minecraft.world.entity.ai.village.package-info
+ net.minecraft.world.entity.ai.village.poi.package-info
+ net.minecraft.world.entity.ai.village.poi.PoiManager
- net.minecraft.world.entity.ai.village.poi.PoiManager$DistanceTracker
+ net.minecraft.world.entity.ai.village.poi.PoiManager$Occupancy
- net.minecraft.world.entity.ai.village.poi.PoiRecord
+ net.minecraft.world.entity.ai.village.poi.PoiSection
- net.minecraft.world.entity.ai.village.poi.PoiType
- net.minecraft.world.entity.ai.village.ReputationEventType
+ net.minecraft.world.entity.ai.village.ReputationEventType$1
- net.minecraft.world.entity.ai.village.VillageSiege
+ net.minecraft.world.entity.ai.village.VillageSiege$State
- net.minecraft.world.entity.ambient.AmbientCreature
+ net.minecraft.world.entity.ambient.Bat
- net.minecraft.world.entity.ambient.package-info
+ net.minecraft.world.entity.animal.AbstractFish
- net.minecraft.world.entity.animal.AbstractFish$FishMoveControl
+ net.minecraft.world.entity.animal.AbstractFish$FishSwimGoal
- net.minecraft.world.entity.animal.AbstractGolem
+ net.minecraft.world.entity.animal.AbstractSchoolingFish
- net.minecraft.world.entity.animal.AbstractSchoolingFish$SchoolSpawnGroupData
- net.minecraft.world.entity.animal.allay.AllayAi
+ net.minecraft.world.entity.animal.Animal
- net.minecraft.world.entity.animal.Bee
+ net.minecraft.world.entity.animal.Bee$1
- net.minecraft.world.entity.animal.Bee$BaseBeeGoal
+ net.minecraft.world.entity.animal.Bee$BeeAttackGoal
- net.minecraft.world.entity.animal.Bee$BeeBecomeAngryTargetGoal
+ net.minecraft.world.entity.animal.Bee$BeeEnterHiveGoal
- net.minecraft.world.entity.animal.Bee$BeeGoToHiveGoal
+ net.minecraft.world.entity.animal.Bee$BeeGoToKnownFlowerGoal
- net.minecraft.world.entity.animal.Bee$BeeGrowCropGoal
+ net.minecraft.world.entity.animal.Bee$BeeHurtByOtherGoal
- net.minecraft.world.entity.animal.Bee$BeeLocateHiveGoal
+ net.minecraft.world.entity.animal.Bee$BeeLookControl
- net.minecraft.world.entity.animal.Bee$BeePollinateGoal
+ net.minecraft.world.entity.animal.Bee$BeeWanderGoal
- net.minecraft.world.entity.animal.Bucketable
+ net.minecraft.world.entity.animal.Cat
- net.minecraft.world.entity.animal.Cat$CatAvoidEntityGoal
+ net.minecraft.world.entity.animal.Cat$CatRelaxOnOwnerGoal
- net.minecraft.world.entity.animal.Cat$CatTemptGoal
+ net.minecraft.world.entity.animal.Chicken
- net.minecraft.world.entity.animal.Cod
+ net.minecraft.world.entity.animal.Cow
- net.minecraft.world.entity.animal.Dolphin
+ net.minecraft.world.entity.animal.Dolphin$DolphinSwimToTreasureGoal
- net.minecraft.world.entity.animal.Dolphin$DolphinSwimWithPlayerGoal
+ net.minecraft.world.entity.animal.Dolphin$PlayWithItemsGoal
- net.minecraft.world.entity.animal.FlyingAnimal
+ net.minecraft.world.entity.animal.Fox
- net.minecraft.world.entity.animal.Fox$DefendTrustedTargetGoal
+ net.minecraft.world.entity.animal.Fox$FaceplantGoal
- net.minecraft.world.entity.animal.Fox$FoxAlertableEntitiesSelector
+ net.minecraft.world.entity.animal.Fox$FoxBehaviorGoal
- net.minecraft.world.entity.animal.Fox$FoxBreedGoal
+ net.minecraft.world.entity.animal.Fox$FoxEatBerriesGoal
- net.minecraft.world.entity.animal.Fox$FoxFloatGoal
+ net.minecraft.world.entity.animal.Fox$FoxFollowParentGoal
- net.minecraft.world.entity.animal.Fox$FoxGroupData
+ net.minecraft.world.entity.animal.Fox$FoxLookAtPlayerGoal
- net.minecraft.world.entity.animal.Fox$FoxLookControl
+ net.minecraft.world.entity.animal.Fox$FoxMeleeAttackGoal
- net.minecraft.world.entity.animal.Fox$FoxMoveControl
+ net.minecraft.world.entity.animal.Fox$FoxPanicGoal
- net.minecraft.world.entity.animal.Fox$FoxPounceGoal
+ net.minecraft.world.entity.animal.Fox$FoxSearchForItemsGoal
- net.minecraft.world.entity.animal.Fox$FoxStrollThroughVillageGoal
+ net.minecraft.world.entity.animal.Fox$PerchAndSearchGoal
- net.minecraft.world.entity.animal.Fox$SeekShelterGoal
+ net.minecraft.world.entity.animal.Fox$SleepGoal
- net.minecraft.world.entity.animal.Fox$StalkPreyGoal
+ net.minecraft.world.entity.animal.Fox$Type
- net.minecraft.world.entity.animal.IronGolem
+ net.minecraft.world.entity.animal.IronGolem$Crackiness
- net.minecraft.world.entity.animal.MushroomCow
+ net.minecraft.world.entity.animal.MushroomCow$MushroomType
- net.minecraft.world.entity.animal.Ocelot
+ net.minecraft.world.entity.animal.Ocelot$OcelotAvoidEntityGoal
- net.minecraft.world.entity.animal.Ocelot$OcelotTemptGoal
+ net.minecraft.world.entity.animal.Panda
- net.minecraft.world.entity.animal.Panda$Gene
+ net.minecraft.world.entity.animal.Panda$PandaAttackGoal
- net.minecraft.world.entity.animal.Panda$PandaAvoidGoal
+ net.minecraft.world.entity.animal.Panda$PandaBreedGoal
- net.minecraft.world.entity.animal.Panda$PandaHurtByTargetGoal
+ net.minecraft.world.entity.animal.Panda$PandaLieOnBackGoal
- net.minecraft.world.entity.animal.Panda$PandaLookAtPlayerGoal
+ net.minecraft.world.entity.animal.Panda$PandaMoveControl
- net.minecraft.world.entity.animal.Panda$PandaPanicGoal
+ net.minecraft.world.entity.animal.Panda$PandaRollGoal
- net.minecraft.world.entity.animal.Panda$PandaSitGoal
+ net.minecraft.world.entity.animal.Panda$PandaSneezeGoal
- net.minecraft.world.entity.animal.Parrot
+ net.minecraft.world.entity.animal.Parrot$1
- net.minecraft.world.entity.animal.Parrot$ParrotWanderGoal
+ net.minecraft.world.entity.animal.Pig
- net.minecraft.world.entity.animal.PolarBear
+ net.minecraft.world.entity.animal.PolarBear$PolarBearAttackPlayersGoal
- net.minecraft.world.entity.animal.PolarBear$PolarBearHurtByTargetGoal
+ net.minecraft.world.entity.animal.PolarBear$PolarBearMeleeAttackGoal
- net.minecraft.world.entity.animal.PolarBear$PolarBearPanicGoal
+ net.minecraft.world.entity.animal.Pufferfish
- net.minecraft.world.entity.animal.Pufferfish$PufferfishPuffGoal
+ net.minecraft.world.entity.animal.Rabbit
- net.minecraft.world.entity.animal.Rabbit$EvilRabbitAttackGoal
+ net.minecraft.world.entity.animal.Rabbit$RabbitAvoidEntityGoal
- net.minecraft.world.entity.animal.Rabbit$RabbitGroupData
+ net.minecraft.world.entity.animal.Rabbit$RabbitJumpControl
- net.minecraft.world.entity.animal.Rabbit$RabbitMoveControl
+ net.minecraft.world.entity.animal.Rabbit$RabbitPanicGoal
- net.minecraft.world.entity.animal.Rabbit$RaidGardenGoal
+ net.minecraft.world.entity.animal.Salmon
- net.minecraft.world.entity.animal.Sheep
+ net.minecraft.world.entity.animal.Sheep$1
- net.minecraft.world.entity.animal.Sheep$2
+ net.minecraft.world.entity.animal.ShoulderRidingEntity
- net.minecraft.world.entity.animal.SnowGolem
+ net.minecraft.world.entity.animal.Squid
- net.minecraft.world.entity.animal.Squid$SquidFleeGoal
+ net.minecraft.world.entity.animal.Squid$SquidRandomMovementGoal
- net.minecraft.world.entity.animal.TropicalFish
+ net.minecraft.world.entity.animal.TropicalFish$Pattern
- net.minecraft.world.entity.animal.TropicalFish$TropicalFishGroupData
+ net.minecraft.world.entity.animal.Turtle
- net.minecraft.world.entity.animal.Turtle$TurtleBreedGoal
+ net.minecraft.world.entity.animal.Turtle$TurtleGoHomeGoal
- net.minecraft.world.entity.animal.Turtle$TurtleGoToWaterGoal
+ net.minecraft.world.entity.animal.Turtle$TurtleLayEggGoal
- net.minecraft.world.entity.animal.Turtle$TurtleMoveControl
+ net.minecraft.world.entity.animal.Turtle$TurtlePanicGoal
- net.minecraft.world.entity.animal.Turtle$TurtlePathNavigation
+ net.minecraft.world.entity.animal.Turtle$TurtleRandomStrollGoal
- net.minecraft.world.entity.animal.Turtle$TurtleTravelGoal
+ net.minecraft.world.entity.animal.WaterAnimal
- net.minecraft.world.entity.animal.Wolf
+ net.minecraft.world.entity.animal.Wolf$WolfAvoidEntityGoal
- net.minecraft.world.entity.animal.Wolf$WolfPanicGoal
- net.minecraft.world.level.levelgen.Beardifier$Rigid
+ net.minecraft.world.level.levelgen.feature.configurations.BlockColumnConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.BlockColumnConfiguration$Layer
+ net.minecraft.world.level.levelgen.feature.configurations.BlockPileConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.BlockStateConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ColumnFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.CountConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.DeltaFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.DiskConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.DripstoneClusterConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.EndGatewayConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.FeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.GeodeConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.HugeMushroomFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.LargeDripstoneConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.LayerConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.MultifaceGrowthConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.NetherForestVegetationConfig
- net.minecraft.world.level.levelgen.feature.configurations.NoneFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration$TargetBlockState
+ net.minecraft.world.level.levelgen.feature.configurations.package-info
+ net.minecraft.world.level.levelgen.feature.configurations.PointedDripstoneConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ProbabilityFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomBooleanFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ReplaceBlockConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ReplaceSphereConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RootSystemConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SculkPatchConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SimpleBlockConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SimpleRandomFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SpikeConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SpringConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
- net.minecraft.world.level.levelgen.feature.configurations.TwistingVinesConfig
+ net.minecraft.world.level.levelgen.feature.configurations.UnderwaterMagmaConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.VegetationPatchConfiguration
- net.minecraft.world.level.levelgen.feature.featuresize.FeatureSize
+ net.minecraft.world.level.levelgen.feature.featuresize.FeatureSizeType
- net.minecraft.world.level.levelgen.feature.featuresize.package-info
- net.minecraft.world.level.levelgen.feature.featuresize.ThreeLayersFeatureSize
+ net.minecraft.world.level.levelgen.feature.featuresize.TwoLayersFeatureSize
+ net.minecraft.world.level.levelgen.feature.foliageplacers.AcaciaFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.BlobFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.BushFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.DarkOakFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FancyFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer$FoliageAttachment
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacerType
+ net.minecraft.world.level.levelgen.feature.foliageplacers.MegaJungleFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.MegaPineFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.package-info
+ net.minecraft.world.level.levelgen.feature.foliageplacers.PineFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.RandomSpreadFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.SpruceFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.OreFeature
+ net.minecraft.world.level.levelgen.feature.package-info
- net.minecraft.world.level.levelgen.feature.PointedDripstoneFeature
+ net.minecraft.world.level.levelgen.feature.RandomBooleanSelectorFeature
- net.minecraft.world.level.levelgen.feature.RandomPatchFeature
+ net.minecraft.world.level.levelgen.feature.RandomSelectorFeature
- net.minecraft.world.level.levelgen.feature.ReplaceBlobsFeature
+ net.minecraft.world.level.levelgen.feature.ReplaceBlockFeature
- net.minecraft.world.level.levelgen.feature.RootSystemFeature
+ net.minecraft.world.level.levelgen.feature.ScatteredOreFeature
- net.minecraft.world.level.levelgen.feature.SculkPatchFeature
- net.minecraft.world.level.levelgen.feature.SeagrassFeature
+ net.minecraft.world.level.levelgen.feature.SeaPickleFeature
+ net.minecraft.world.level.levelgen.feature.SimpleBlockFeature
- net.minecraft.world.level.levelgen.feature.SimpleRandomSelectorFeature
+ net.minecraft.world.level.levelgen.feature.SnowAndFreezeFeature
- net.minecraft.world.level.levelgen.feature.SpikeFeature
+ net.minecraft.world.level.levelgen.feature.SpikeFeature$EndSpike
- net.minecraft.world.level.levelgen.feature.SpikeFeature$SpikeCacheLoader
+ net.minecraft.world.level.levelgen.feature.SpringFeature
- net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProviderType
- net.minecraft.world.level.levelgen.feature.stateproviders.DualNoiseProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.NoiseBasedStateProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.NoiseProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.NoiseThresholdProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.package-info
- net.minecraft.world.level.levelgen.feature.stateproviders.RandomizedIntStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.RotatedBlockProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.SimpleStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.WeightedStateProvider
+ net.minecraft.world.level.levelgen.feature.treedecorators.AlterGroundDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.BeehiveDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.CocoaDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.LeaveVineDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.package-info
+ net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecoratorType
+ net.minecraft.world.level.levelgen.feature.treedecorators.TrunkVineDecorator
- net.minecraft.world.level.levelgen.feature.TreeFeature
+ net.minecraft.world.level.levelgen.feature.trunkplacers.BendingTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.DarkOakTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.FancyTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.FancyTrunkPlacer$FoliageCoords
+ net.minecraft.world.level.levelgen.feature.trunkplacers.ForkingTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.GiantTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.MegaJungleTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.package-info
- net.minecraft.world.level.levelgen.feature.trunkplacers.StraightTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.TrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.TrunkPlacerType
+ net.minecraft.world.level.levelgen.feature.TwistingVinesFeature
- net.minecraft.world.level.levelgen.feature.UnderwaterMagmaFeature
+ net.minecraft.world.level.levelgen.feature.VegetationPatchFeature
- net.minecraft.world.level.levelgen.feature.VinesFeature
+ net.minecraft.world.level.levelgen.feature.VoidStartPlatformFeature
- net.minecraft.world.level.levelgen.feature.WaterloggedVegetationPatchFeature
+ net.minecraft.world.level.levelgen.feature.WeepingVinesFeature
- net.minecraft.world.level.levelgen.feature.WeightedPlacedFeature
- net.minecraft.world.level.levelgen.flat.FlatLayerInfo
+ net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorPreset
- net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorPresets
+ net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorPresets$Bootstrap
- net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorSettings
+ net.minecraft.world.level.levelgen.flat.package-info
- net.minecraft.world.level.levelgen.heightproviders.BiasedToBottomHeight
+ net.minecraft.world.level.levelgen.heightproviders.ConstantHeight
- net.minecraft.world.level.levelgen.heightproviders.HeightProvider
+ net.minecraft.world.level.levelgen.heightproviders.HeightProviderType
- net.minecraft.world.level.levelgen.heightproviders.package-info
- net.minecraft.world.level.levelgen.heightproviders.TrapezoidHeight
+ net.minecraft.world.level.levelgen.heightproviders.UniformHeight
- net.minecraft.world.level.levelgen.heightproviders.VeryBiasedToBottomHeight
+ net.minecraft.world.level.levelgen.heightproviders.WeightedListHeight
+ net.minecraft.world.level.levelgen.material.MaterialRuleList
+ net.minecraft.world.level.levelgen.material.package-info
- net.minecraft.world.level.levelgen.material.WorldGenMaterialRule
- net.minecraft.world.level.levelgen.package-info
+ net.minecraft.world.level.levelgen.placement.BiomeFilter
- net.minecraft.world.level.levelgen.placement.BlockPredicateFilter
+ net.minecraft.world.level.levelgen.placement.CarvingMaskPlacement
- net.minecraft.world.level.levelgen.placement.CaveSurface
+ net.minecraft.world.level.levelgen.placement.CountOnEveryLayerPlacement
- net.minecraft.world.level.levelgen.placement.CountPlacement
+ net.minecraft.world.level.levelgen.placement.EnvironmentScanPlacement
+ net.minecraft.world.level.levelgen.placement.HeightmapPlacement
- net.minecraft.world.level.levelgen.placement.HeightRangePlacement
- net.minecraft.world.level.levelgen.placement.InSquarePlacement
+ net.minecraft.world.level.levelgen.placement.NoiseBasedCountPlacement
- net.minecraft.world.level.levelgen.placement.NoiseThresholdCountPlacement
- net.minecraft.world.level.levelgen.placement.package-info
+ net.minecraft.world.level.levelgen.placement.PlacedFeature
- net.minecraft.world.level.levelgen.placement.PlacedFeature$test
+ net.minecraft.world.level.levelgen.placement.PlacementContext
- net.minecraft.world.level.levelgen.placement.PlacementFilter
+ net.minecraft.world.level.levelgen.placement.PlacementModifier
- net.minecraft.world.level.levelgen.placement.PlacementModifierType
+ net.minecraft.world.level.levelgen.placement.RandomOffsetPlacement
- net.minecraft.world.level.levelgen.placement.RarityFilter
+ net.minecraft.world.level.levelgen.placement.RepeatingPlacement
- net.minecraft.world.level.levelgen.placement.SurfaceRelativeThresholdFilter
+ net.minecraft.world.level.levelgen.placement.SurfaceWaterDepthFilter
+ net.minecraft.world.level.levelgen.presets.WorldPreset
- net.minecraft.world.level.levelgen.presets.WorldPresets
+ net.minecraft.world.level.levelgen.presets.WorldPresets$Bootstrap
- net.minecraft.world.level.levelgen.structure.BoundingBox
+ net.minecraft.world.level.levelgen.structure.BoundingBox$1
+ net.minecraft.world.level.levelgen.structure.BuiltinStructures
- net.minecraft.world.level.levelgen.structure.BuiltinStructureSets
- net.minecraft.world.level.levelgen.structure.LegacyStructureDataHandler
+ net.minecraft.world.level.levelgen.structure.package-info
- net.minecraft.world.level.levelgen.structure.pieces.package-info
- net.minecraft.world.level.levelgen.structure.pieces.PieceGenerator
+ net.minecraft.world.level.levelgen.structure.pieces.PieceGenerator$Context
- net.minecraft.world.level.levelgen.structure.pieces.PieceGeneratorSupplier
+ net.minecraft.world.level.levelgen.structure.pieces.PieceGeneratorSupplier$Context
- net.minecraft.world.level.levelgen.structure.pieces.PiecesContainer
+ net.minecraft.world.level.levelgen.structure.pieces.StructurePiecesBuilder
+ net.minecraft.world.level.levelgen.structure.pieces.StructurePieceSerializationContext
- net.minecraft.world.level.levelgen.structure.pieces.StructurePieceType
+ net.minecraft.world.level.levelgen.structure.pieces.StructurePieceType$ContextlessType
- net.minecraft.world.level.levelgen.structure.pieces.StructurePieceType$StructureTemplateType
+ net.minecraft.world.level.levelgen.structure.placement.ConcentricRingsStructurePlacement
- net.minecraft.world.level.levelgen.structure.placement.package-info
- net.minecraft.world.level.levelgen.structure.placement.RandomSpreadStructurePlacement
+ net.minecraft.world.level.levelgen.structure.placement.RandomSpreadType
- net.minecraft.world.level.levelgen.structure.placement.RandomSpreadType$1
+ net.minecraft.world.level.levelgen.structure.placement.StructurePlacement
- net.minecraft.world.level.levelgen.structure.placement.StructurePlacement$ExclusionZone
+ net.minecraft.world.level.levelgen.structure.placement.StructurePlacement$FrequencyReducer
- net.minecraft.world.level.levelgen.structure.placement.StructurePlacement$FrequencyReductionMethod
+ net.minecraft.world.level.levelgen.structure.placement.StructurePlacementType
+ net.minecraft.world.level.levelgen.structure.PoolElementStructurePiece
+ net.minecraft.world.level.levelgen.structure.pools.EmptyPoolElement
- net.minecraft.world.level.levelgen.structure.pools.FeaturePoolElement
+ net.minecraft.world.level.levelgen.structure.pools.JigsawJunction
- net.minecraft.world.level.levelgen.structure.pools.JigsawPlacement
+ net.minecraft.world.level.levelgen.structure.pools.JigsawPlacement$PieceFactory
- net.minecraft.world.level.levelgen.structure.pools.JigsawPlacement$PieceState
+ net.minecraft.world.level.levelgen.structure.pools.JigsawPlacement$Placer
- net.minecraft.world.level.levelgen.structure.pools.LegacySinglePoolElement
+ net.minecraft.world.level.levelgen.structure.pools.ListPoolElement
+ net.minecraft.world.level.levelgen.structure.pools.package-info
- net.minecraft.world.level.levelgen.structure.pools.SinglePoolElement
+ net.minecraft.world.level.levelgen.structure.pools.StructurePoolElement
- net.minecraft.world.level.levelgen.structure.pools.StructurePoolElementType
+ net.minecraft.world.level.levelgen.structure.pools.StructureTemplatePool
- net.minecraft.world.level.levelgen.structure.pools.StructureTemplatePool$Projection
- net.minecraft.world.level.levelgen.structure.PostPlacementProcessor
+ net.minecraft.world.level.levelgen.structure.ScatteredFeaturePiece
- net.minecraft.world.level.levelgen.structure.SinglePieceStructure
+ net.minecraft.world.level.levelgen.structure.SinglePieceStructure$PieceConstructor
- net.minecraft.world.level.levelgen.structure.Structure
+ net.minecraft.world.level.levelgen.structure.Structure$GenerationContext
- net.minecraft.world.level.levelgen.structure.Structure$GenerationStub
- net.minecraft.world.level.levelgen.structure.structures.BuriedTreasurePieces
+ net.minecraft.world.level.levelgen.structure.structures.BuriedTreasurePieces$BuriedTreasurePiece
- net.minecraft.world.level.levelgen.structure.structures.BuriedTreasureStructure
+ net.minecraft.world.level.levelgen.structure.structures.DesertPyramidPiece
- net.minecraft.world.level.levelgen.structure.structures.DesertPyramidStructure
+ net.minecraft.world.level.levelgen.structure.structures.EndCityPieces
- net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$1
+ net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$2
- net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$3
+ net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$4
- net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$EndCityPiece
+ net.minecraft.world.level.levelgen.structure.structures.EndCityPieces$SectionGenerator
- net.minecraft.world.level.levelgen.structure.structures.EndCityStructure
+ net.minecraft.world.level.levelgen.structure.structures.IglooPieces
- net.minecraft.world.level.levelgen.structure.structures.IglooPieces$IglooPiece
+ net.minecraft.world.level.levelgen.structure.structures.IglooStructure
- net.minecraft.world.level.levelgen.structure.structures.JigsawStructure
- net.minecraft.world.level.levelgen.structure.TerrainAdjustment
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.advancements.critereon.KilledTrigger$TriggerInstance +1M
```
```
XXX.minecraft.client.OptionInstance +16M -11M | +2P -1P
```
```
XXX.minecraft.client.OptionInstance$Enum +1M -3M
```
```
XXX.minecraft.client.OptionInstance$IntRangeBase -2M
```
```
XXX.minecraft.client.OptionInstance$LazyEnum +1M -3M
```
```
XXX.minecraft.client.OptionInstance$UnitDouble +3M -5M
```
```
XXX.gui.components.CycleButton$Builder +1M
```
```
XXX.minecraft.core.Direction +8M -9M | +1P -2P
```
```
XXX.minecraft.core.Direction$Axis -1M | +1P -2P
```
```
XXX.core.dispenser.BoatDispenseItemBehavior +1M | +1P
```
```
XXX.core.particles.ParticleTypes +1P
```
```
XXX.data.advancements.HusbandryAdvancements +1P
```
```
XXX.models.model.ModelTemplates +1P
```
```
XXX.models.model.TextureSlot +1P
```
```
XXX.data.recipes.RecipeProvider +1M
```
```
XXX.data.worldgen.StructureSets +1P
```
```
XXX.worldgen.features.CaveFeatures +2P -1P
```
```
XXX.worldgen.placement.CavePlacements +2P -1P
```
```
XXX.minecraft.sounds.SoundEvents +7P
```
```
XXX.minecraft.tags.BiomeTags +1P
```
```
XXX.minecraft.tags.ItemTags +1P -1P
```
```
XXX.minecraft.util.Mth +1M
```
```
XXX.world.entity.EntityType +1P
```
```
XXX.world.entity.HumanoidArm +3M -3M | +2P -1P
```
```
XXX.ai.behavior.BehaviorUtils +1M
```
```
XXX.animal.frog.ShootTongue +1M | +1P -1P
```
```
XXX.animal.frog.ShootTongue$State +1P
```
```
XXX.monster.warden.AngerManagement +3M -5M
```
```
XXX.monster.warden.Warden +7M -6M | -2P
```
```
XXX.monster.warden.WardenAi +1M -1M | +2P
```
```
XXX.entity.vehicle.Minecart +1M
```
```
XXX.entity.vehicle.MinecartCommandBlock +1M
```
```
XXX.entity.vehicle.MinecartFurnace +1M -1M
```
```
XXX.entity.vehicle.MinecartSpawner +1M
```
```
XXX.entity.vehicle.MinecartTNT +1M
```
```
XXX.world.level.StructureManager +1M -1M
```
```
XXX.level.biome.Biome$TemperatureModifier -2M | -1P
```
```
XXX.level.block.NoteBlock +1M -1M
```
```
XXX.level.block.SculkShriekerBlock +1M -2M | +1P
```
```
XXX.level.block.TripWireHookBlock +1M -1M
```
```
XXX.block.entity.SculkSensorBlockEntity +2M -1M
```
```
XXX.level.gameevent.GameEvent +12P -18P
```
```
XXX.gameevent.vibrations.VibrationListener$ReceivingEvent +13M -4M | +1P
```
```
XXX.level.levelgen.Beardifier +7M -3M | -2P
```
```
XXX.level.levelgen.GenerationStep$Decoration -2M | -1P
```
```
XXX.levelgen.structure.StructureSpawnOverride$BoundingBoxType -2M | -1P
```
```
XXX.structure.structures.JungleTempleStructure +1M -2M
```
```
XXX.structure.structures.MineshaftStructure +1M -1M
```
```
XXX.structure.structures.NetherFossilStructure +1M -1M
```
```
XXX.structure.structures.OceanRuinStructure$Type -2M | -1P
```
```
XXX.structure.structures.RuinedPortalStructure +2M -2M
```
```
XXX.structure.structures.ShipwreckStructure +1M -1M
```
```
XXX.structure.structures.StrongholdPieces$FillerCorridor -1M
```
```
XXX.structure.structures.StrongholdPieces$PrisonHall -1M
```
```
XXX.structure.structures.StrongholdPieces$RoomCrossing -1M
```
```
XXX.structure.structures.StrongholdPieces$StairsDown -1M
```
```
XXX.structure.structures.StrongholdPieces$Straight -1M
```
```
XXX.structure.structures.StrongholdPieces$StrongholdPiece -1M
```
```
XXX.structure.structures.StrongholdPieces$Turn -1M
```
```
XXX.structure.structures.WoodlandMansionStructure +2M -3M
```
```
XXX.structure.templatesystem.BlockRotProcessor +5M -1M | +1P
```

</details>





























































































































































































































<details>
<summary>
net.minecraft.advancements.critereon.KilledTrigger$TriggerInstance
</summary>

```diff
- KilledTrigger$TriggerInstance playerKilledEntityNearSculkCatalyst()
```

</details>
















































<details>
<summary>
net.minecraft.client.OptionInstance
</summary>

```diff
+ Component getCaption()
+ Component lambda$createBoolean$2(Boolean)
- Component lambda$createBoolean$2(Component,Boolean)
- Component lambda$forOptionEnum$8(Component,OptionEnum)
- Component lambda$new$3(OptionInstance$CaptionBasedToString,Object)
+ Function noTooltip()
- List lambda$cachedConstantTooltip$6(List,Object)
+ List lambda$noTooltip$3(Object)
- List lambda$noTooltip$4(Object)
- List splitTooltip(Minecraft,Component)
+ Object lambda$set$5(Object)
- Object lambda$set$9(Object)
+ OptionInstance createBoolean(String,Function,boolean,Consumer)
+ OptionInstance createBoolean(String,Function,boolean)
- OptionInstance createBoolean(String,OptionInstance$TooltipSupplierFactory,boolean,Consumer)
- OptionInstance createBoolean(String,OptionInstance$TooltipSupplierFactory,boolean)
- OptionInstance$CaptionBasedToString forOptionEnum()
- OptionInstance$TooltipSupplier lambda$cachedConstantTooltip$7(Component,Minecraft)
+ OptionInstance$TooltipSupplier lambda$noTooltip$4(Minecraft)
- OptionInstance$TooltipSupplier lambda$noTooltip$5(Minecraft)
- OptionInstance$TooltipSupplierFactory cachedConstantTooltip(Component)
- OptionInstance$TooltipSupplierFactory noTooltip()
+ OptionInstance$ValueSet clampingLazyMax(int,IntSupplier)
+ void <init>(String,Function,Function,OptionInstance$ValueSet,Codec,Object,Consumer)
+ void <init>(String,Function,Function,OptionInstance$ValueSet,Object,Consumer)
- void <init>(String,OptionInstance$TooltipSupplierFactory,OptionInstance$CaptionBasedToString,OptionInstance$ValueSet,Codec,Object,Consumer)
- void <init>(String,OptionInstance$TooltipSupplierFactory,OptionInstance$CaptionBasedToString,OptionInstance$ValueSet,Object,Consumer)
```

</details>
<details>
<summary>
net.minecraft.client.OptionInstance$Enum
</summary>

```diff
+ AbstractWidget lambda$createButton$1(OptionInstance$TooltipSupplier,int,int,int,Options,OptionInstance)
- CycleButton$ValueListSupplier valueListSupplier()
+ Function createButton(OptionInstance$TooltipSupplier,Options,int,int,int)
+ void lambda$createButton$0(OptionInstance,Options,CycleButton,Object)
```

</details>
<details>
<summary>
net.minecraft.client.OptionInstance$IntRangeBase
</summary>

```diff
+ AbstractWidget lambda$createButton$0(Options,int,int,int,OptionInstance$TooltipSupplier,OptionInstance)
+ Function createButton(OptionInstance$TooltipSupplier,Options,int,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.OptionInstance$LazyEnum
</summary>

```diff
+ AbstractWidget lambda$createButton$1(OptionInstance$TooltipSupplier,int,int,int,Options,OptionInstance)
- CycleButton$ValueListSupplier valueListSupplier()
+ Function createButton(OptionInstance$TooltipSupplier,Options,int,int,int)
+ void lambda$createButton$0(OptionInstance,Options,CycleButton,Object)
```

</details>
<details>
<summary>
net.minecraft.client.OptionInstance$UnitDouble
</summary>

```diff
+ AbstractWidget lambda$createButton$0(Options,int,int,int,OptionInstance$TooltipSupplier,OptionInstance)
- Double lambda$codec$0(Double)
- Double lambda$codec$1(Boolean)
+ Double lambda$codec$1(Double)
+ Double lambda$codec$2(Boolean)
- Double lambda$codec$2(Either)
+ Double lambda$codec$3(Either)
+ Function createButton(OptionInstance$TooltipSupplier,Options,int,int,int)
```

</details>












































<details>
<summary>
net.minecraft.client.gui.components.CycleButton$Builder
</summary>

```diff
- CycleButton$Builder withValues(CycleButton$ValueListSupplier)
```

</details>



























































































































































































































































































































































































































































































































<details>
<summary>
net.minecraft.core.Direction
</summary>

```diff
- boolean lambda$static$2(Direction)
+ boolean lambda$static$3(Direction)
+ Direction lambda$static$0(Direction)
- Direction lambda$static$6(Direction)
- Direction lambda$static$7(Direction,Direction)
+ Direction lambda$static$7(Direction)
+ Direction lambda$static$8(Direction,Direction)
- Direction[] lambda$static$1(int)
+ Direction[] lambda$static$2(int)
- Direction[] lambda$static$4(int)
+ Direction[] lambda$static$5(int)
- int lambda$static$0(Direction)
+ int lambda$static$1(Direction)
- int lambda$static$3(Direction)
+ int lambda$static$4(Direction)
- Long lambda$static$5(Direction)
+ Long lambda$static$6(Direction)
```

</details>
<details>
<summary>
net.minecraft.core.Direction$Axis
</summary>

```diff
+ Direction$Axis lambda$static$0(Direction$Axis)
```

</details>
























<details>
<summary>
net.minecraft.core.dispenser.BoatDispenseItemBehavior
</summary>

```diff
- void <init>(Boat$Type,boolean)
```

</details>




































































<details>
<summary>
net.minecraft.data.recipes.RecipeProvider
</summary>

```diff
- void chestBoat(Consumer,ItemLike,ItemLike)
```

</details>




































































































































































































































































































































































































































































































<details>
<summary>
net.minecraft.util.Mth
</summary>

```diff
- float cube(float)
```

</details>
























































































































































































<details>
<summary>
net.minecraft.world.entity.HumanoidArm
</summary>

```diff
+ Component getName()
- int getId()
- String getKey()
+ String toString()
+ void <init>(String,int,Component)
- void <init>(String,int,int,String)
```

</details>





























<details>
<summary>
net.minecraft.world.entity.ai.behavior.BehaviorUtils
</summary>

```diff
- void setWalkAndLookTargetMemories(LivingEntity,PositionTracker,float,int)
```

</details>









































<details>
<summary>
net.minecraft.world.entity.animal.frog.ShootTongue
</summary>

```diff
- void eatEntity(ServerLevel,Frog)
```

</details>



































































































<details>
<summary>
net.minecraft.world.entity.monster.warden.AngerManagement
</summary>

```diff
- boolean lambda$getActiveEntity$3(Entity)
+ boolean lambda$getActiveEntity$5(Entity)
- Integer lambda$addAnger$2(int,UUID,Integer)
+ Integer lambda$addAnger$4(int,UUID,Integer)
+ Integer lambda$tick$2(UUID,Integer)
- LivingEntity lambda$getActiveEntity$4(Entity)
+ LivingEntity lambda$getActiveEntity$6(Entity)
+ void lambda$tick$3(UUID)
```

</details>


<details>
<summary>
net.minecraft.world.entity.monster.warden.Warden
</summary>

```diff
+ boolean lambda$increaseAngerAt$2(LivingEntity)
- boolean lambda$increaseAngerAt$4(LivingEntity)
+ Boolean lambda$onSignalReceive$3(Entity,LivingEntity)
- Boolean lambda$onSignalReceive$5(Entity,LivingEntity)
+ Brain$Provider brainProvider()
+ float getEarAnimation(float)
- float getTendrilAnimation(float)
- void lambda$addAdditionalSaveData$1(CompoundTag,Tag)
+ void lambda$readAdditionalSaveData$1(AngerManagement)
- void lambda$readAdditionalSaveData$2(AngerManagement)
- void lambda$readAdditionalSaveData$3(VibrationListener)
- void onSignalReceive(ServerLevel,GameEventListener,BlockPos,GameEvent,Entity,Entity,int)
+ void onSignalReceive(ServerLevel,GameEventListener,BlockPos,GameEvent,Entity,int)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.warden.WardenAi
</summary>

```diff
+ Brain makeBrain(Warden,Brain)
- Brain makeBrain(Warden,Dynamic)
```

</details>



















































<details>
<summary>
net.minecraft.world.entity.vehicle.Minecart
</summary>

```diff
- Item getDropItem()
```

</details>
<details>
<summary>
net.minecraft.world.entity.vehicle.MinecartCommandBlock
</summary>

```diff
- Item getDropItem()
```

</details>
<details>
<summary>
net.minecraft.world.entity.vehicle.MinecartFurnace
</summary>

```diff
- Item getDropItem()
+ void destroy(DamageSource)
```

</details>
<details>
<summary>
net.minecraft.world.entity.vehicle.MinecartSpawner
</summary>

```diff
- Item getDropItem()
```

</details>
<details>
<summary>
net.minecraft.world.entity.vehicle.MinecartTNT
</summary>

```diff
- Item getDropItem()
```

</details>










































































































































































































<details>
<summary>
net.minecraft.world.level.StructureManager
</summary>

```diff
- List startsForStructure(ChunkPos,Predicate)
+ List startsForStructure(SectionPos,Predicate)
```

</details>




<details>
<summary>
net.minecraft.world.level.biome.Biome$TemperatureModifier
</summary>

```diff
+ Biome$TemperatureModifier byName(String)
+ Biome$TemperatureModifier lambda$static$0(Biome$TemperatureModifier)
```

</details>





























































































































<details>
<summary>
net.minecraft.world.level.block.NoteBlock
</summary>

```diff
- void playNote(Entity,Level,BlockPos)
+ void playNote(Level,BlockPos)
```

</details>























<details>
<summary>
net.minecraft.world.level.block.SculkShriekerBlock
</summary>

```diff
- void lambda$getTicker$3(Level,BlockPos,BlockState,SculkShriekerBlockEntity)
+ void lambda$getTicker$4(Level,BlockPos,BlockState,SculkShriekerBlockEntity)
+ void lambda$shriek$3(ServerLevel,BlockPos,BlockState,WardenSpawnTracker)
```

</details>





























<details>
<summary>
net.minecraft.world.level.block.TripWireHookBlock
</summary>

```diff
- void emitState(Level,BlockPos,boolean,boolean,boolean,boolean)
+ void playSound(Level,BlockPos,boolean,boolean,boolean,boolean)
```

</details>








































<details>
<summary>
net.minecraft.world.level.block.entity.SculkSensorBlockEntity
</summary>

```diff
- void onSignalReceive(ServerLevel,GameEventListener,BlockPos,GameEvent,Entity,Entity,int)
+ void onSignalReceive(ServerLevel,GameEventListener,BlockPos,GameEvent,Entity,int)
- void onSignalSchedule()
```

</details>













































































































<details>
<summary>
net.minecraft.world.level.gameevent.vibrations.VibrationListener$ReceivingEvent
</summary>

```diff
+ App lambda$static$0(RecordCodecBuilder$Instance)
- App lambda$static$3(RecordCodecBuilder$Instance)
- boolean lambda$getProjectileOwner$5(Entity)
- Optional getProjectileOwner(ServerLevel)
+ Optional lambda$getEntity$1(ServerLevel)
- Optional lambda$getEntity$4(ServerLevel)
- Optional lambda$getProjectileOwner$7(ServerLevel)
- Optional lambda$static$0(VibrationListener$ReceivingEvent)
- Optional lambda$static$1(VibrationListener$ReceivingEvent)
- Projectile lambda$getProjectileOwner$6(Entity)
- UUID getProjectileOwner(Entity)
- UUID projectileOwnerUuid()
- VibrationListener$ReceivingEvent lambda$static$2(GameEvent,Integer,Vec3,Optional,Optional)
+ void <init>(GameEvent,int,Vec3,UUID,Entity)
- void <init>(GameEvent,int,Vec3,UUID,UUID,Entity)
- void <init>(GameEvent,int,Vec3,UUID,UUID)
+ void <init>(GameEvent,int,Vec3,UUID)
```

</details>



<details>
<summary>
net.minecraft.world.level.levelgen.Beardifier
</summary>

```diff
- Beardifier forStructuresInChunk(StructureManager,ChunkPos)
- boolean isInKernelRange(int)
- boolean lambda$forStructuresInChunk$1(Structure)
- double computeBeardContribution(int,double,int)
- double getBeardContribution(int,int,int,int)
+ double getBeardContribution(int,int,int)
- void <init>(ObjectListIterator,ObjectListIterator)
+ void <init>(StructureManager,ChunkAccess)
- void lambda$forStructuresInChunk$2(ChunkPos,ObjectList,int,int,ObjectList,StructureStart)
+ void lambda$new$1(ChunkPos,int,int,StructureStart)
```

</details>



























<details>
<summary>
net.minecraft.world.level.levelgen.GenerationStep$Decoration
</summary>

```diff
+ GenerationStep$Decoration byName(String)
+ GenerationStep$Decoration lambda$static$0(GenerationStep$Decoration)
```

</details>
































































































<details>
<summary>
net.minecraft.world.level.levelgen.structure.StructureSpawnOverride$BoundingBoxType
</summary>

```diff
+ StructureSpawnOverride$BoundingBoxType byName(String)
+ StructureSpawnOverride$BoundingBoxType[] lambda$static$0()
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.structure.structures.JungleTempleStructure
</summary>

```diff
+ App lambda$static$0(RecordCodecBuilder$Instance)
+ void <init>(HolderSet,Map,GenerationStep$Decoration,boolean)
- void <init>(Structure$StructureSettings)
```

</details>



<details>
<summary>
net.minecraft.world.level.levelgen.structure.structures.MineshaftStructure
</summary>

```diff
+ void <init>(HolderSet,Map,GenerationStep$Decoration,boolean,MineshaftStructure$Type)
- void <init>(Structure$StructureSettings,MineshaftStructure$Type)
```

</details>











<details>
<summary>
net.minecraft.world.level.levelgen.structure.structures.NetherFossilStructure
</summary>

```diff
+ void <init>(HolderSet,Map,GenerationStep$Decoration,boolean,HeightProvider)
- void <init>(Structure$StructureSettings,HeightProvider)
```

</details>














<details>
<summary>
net.minecraft.world.level.levelgen.structure.structures.OceanRuinStructure$Type
</summary>

```diff
+ OceanRuinStructure$Type byName(String)
+ OceanRuinStructure$Type lambda$static$0(OceanRuinStructure$Type)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.structure.structures.RuinedPortalStructure
</summary>

```diff
+ void <init>(HolderSet,Map,GenerationStep$Decoration,boolean,List)
+ void <init>(HolderSet,Map,GenerationStep$Decoration,boolean,RuinedPortalStructure$Setup)
- void <init>(Structure$StructureSettings,List)
- void <init>(Structure$StructureSettings,RuinedPortalStructure$Setup)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.structure.structures.ShipwreckStructure
</summary>

```diff
+ void <init>(HolderSet,Map,GenerationStep$Decoration,boolean,boolean)
- void <init>(Structure$StructureSettings,boolean)
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$FillerCorridor
</summary>

```diff
+ NoiseEffect getNoiseEffect()
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$PrisonHall
</summary>

```diff
+ NoiseEffect getNoiseEffect()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$RoomCrossing
</summary>

```diff
+ NoiseEffect getNoiseEffect()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$StairsDown
</summary>

```diff
+ NoiseEffect getNoiseEffect()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$Straight
</summary>

```diff
+ NoiseEffect getNoiseEffect()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$StrongholdPiece
</summary>

```diff
+ NoiseEffect getNoiseEffect()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.structures.StrongholdPieces$Turn
</summary>

```diff
+ NoiseEffect getNoiseEffect()
```

</details>






<details>
<summary>
net.minecraft.world.level.levelgen.structure.structures.WoodlandMansionStructure
</summary>

```diff
+ App lambda$static$0(RecordCodecBuilder$Instance)
+ void <init>(HolderSet,Map,GenerationStep$Decoration,boolean)
- void <init>(Structure$StructureSettings)
- void lambda$findGenerationPoint$0(Structure$GenerationContext,BlockPos,Rotation,StructurePiecesBuilder)
+ void lambda$findGenerationPoint$1(Structure$GenerationContext,BlockPos,Rotation,StructurePiecesBuilder)
```

</details>



<details>
<summary>
net.minecraft.world.level.levelgen.structure.templatesystem.BlockRotProcessor
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
+ Float lambda$static$0(BlockRotProcessor)
- Float lambda$static$1(BlockRotProcessor)
- Optional lambda$static$0(BlockRotProcessor)
- void <init>(Optional,float)
- void <init>(TagKey,float)
```

</details>
</details>