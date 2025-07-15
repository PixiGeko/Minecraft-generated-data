## Comparison with [22w12a](https://github.com/PixiGeko/Minecraft-generated-data/tree/22w12a)

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
<table><tr><th></th><th align="left">22w12a</th><th>22w13a</th></tr><tr><td>World version</td><td><pre>3082</pre></td><td><pre>3085</pre></td></tr><tr><td>Protocol version</td><td><pre>1073741899</pre></td><td><pre>1073741900</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">22w12a</th><th>22w13a</th></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr></table>
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
+ minecraft:reinforced_deepslate
```

</details>
<details>
<summary>
entity_type
</summary>

```diff
+ minecraft:allay
```

</details>
<details>
<summary>
game_event
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
item
</summary>

```diff
+ minecraft:allay_spawn_egg
+ minecraft:reinforced_deepslate
```

</details>
<details>
<summary>
memory_module_type
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
particle_type
</summary>

```diff
+ minecraft:allay_dust
```

</details>
<details>
<summary>
sound_event
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
<hr/>
<details><summary><b><ins>TAGS</ins></b><a name="tags"></a></summary>
<br/>
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
<hr/>
<details><summary><b><ins>BLOCKS</ins></b><a name="blocks"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
+ reinforced_deepslate.json
```

</details>
</details>
<hr/>
<details><summary><b><ins>RECIPES</ins></b><a name="recipes"></a></summary>
<br/>
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
<hr/>
<details><summary><b><ins>TRANSLATIONS</ins></b><a name="translations"></a></summary>
<br/>
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
<hr/>
<details><summary><b><ins>FILE STRUCTURE</ins></b><a name="file-structure"></a></summary>
<br/>
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
<hr/>
<details><summary><b><ins>MAPPINGS</ins></b><a name="mappings"></a></summary>
<br/>
<h2>Server<a name="server-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
- XXX.ai.behavior.FlyingRandomStroll
+ XXX.ai.behavior.FollowTemptation
- XXX.ai.behavior.GateBehavior
+ XXX.ai.behavior.GateBehavior$OrderPolicy
- XXX.ai.behavior.GateBehavior$RunningPolicy
+ XXX.ai.behavior.GateBehavior$RunningPolicy$1
- XXX.ai.behavior.GateBehavior$RunningPolicy$2
+ XXX.ai.behavior.GiveGiftToHero
- XXX.ai.behavior.GoAndGiveItemsToTarget
+ XXX.ai.behavior.package-info
- XXX.ai.behavior.StayCloseToTarget
+ XXX.ai.behavior.StopAttackingIfTargetInvalid
- XXX.ai.behavior.StopBeingAngryIfTargetDead
+ XXX.ai.behavior.StrollAroundPoi
- XXX.ai.behavior.StrollToPoi
+ XXX.ai.behavior.StrollToPoiList
- XXX.ai.behavior.Swim
+ XXX.ai.behavior.TradeWithVillager
- XXX.ai.behavior.TryFindLand
+ XXX.ai.behavior.TryFindLandNearWater
- XXX.ai.behavior.TryFindWater
+ XXX.ai.behavior.TryLaySpawnOnWaterNearLand
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
- XXX.ai.behavior.WorkAtComposter
+ XXX.ai.behavior.WorkAtPoi
- XXX.ai.behavior.YieldJobSite
- XXX.ai.control.BodyRotationControl
+ XXX.ai.control.Control
- XXX.ai.control.FlyingMoveControl
+ XXX.ai.control.JumpControl
- XXX.ai.control.LookControl
+ XXX.ai.control.MoveControl
- XXX.ai.control.MoveControl$Operation
+ XXX.ai.control.package-info
+ XXX.ai.control.SmoothSwimmingLookControl
- XXX.ai.control.SmoothSwimmingMoveControl
- XXX.ai.goal.AvoidEntityGoal
+ XXX.ai.goal.BegGoal
- XXX.ai.goal.BoatGoals
+ XXX.ai.goal.BreakDoorGoal
- XXX.ai.goal.BreathAirGoal
+ XXX.ai.goal.BreedGoal
- XXX.ai.goal.CatLieOnBedGoal
+ XXX.ai.goal.CatSitOnBlockGoal
- XXX.ai.goal.ClimbOnTopOfPowderSnowGoal
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
- XXX.ai.goal.TemptGoal
+ XXX.ai.goal.TradeWithPlayerGoal
- XXX.ai.goal.TryFindWaterGoal
+ XXX.ai.goal.UseItemGoal
- XXX.ai.goal.WaterAvoidingRandomFlyingGoal
+ XXX.ai.goal.WaterAvoidingRandomStrollGoal
- XXX.ai.goal.WrappedGoal
+ XXX.ai.goal.ZombieAttackGoal
- XXX.ai.gossip.GossipContainer
+ XXX.ai.gossip.GossipContainer$EntityGossips
- XXX.ai.gossip.GossipContainer$GossipEntry
+ XXX.ai.gossip.GossipType
- XXX.ai.gossip.package-info
+ XXX.ai.memory.ExpirableValue
- XXX.ai.memory.MemoryModuleType
+ XXX.ai.memory.MemoryStatus
- XXX.ai.memory.NearestVisibleLivingEntities
- XXX.ai.memory.package-info
+ XXX.ai.memory.WalkTarget
+ XXX.ai.navigation.FlyingPathNavigation
- XXX.ai.navigation.GroundPathNavigation
- XXX.ai.navigation.package-info
+ XXX.ai.navigation.PathNavigation
- XXX.ai.navigation.WallClimberNavigation
+ XXX.ai.navigation.WaterBoundPathNavigation
- XXX.ai.sensing.AdultSensor
+ XXX.ai.sensing.AxolotlAttackablesSensor
- XXX.ai.sensing.DummySensor
+ XXX.ai.sensing.FrogAttackablesSensor
- XXX.ai.sensing.GolemSensor
+ XXX.ai.sensing.HoglinSpecificSensor
- XXX.ai.sensing.HurtBySensor
+ XXX.ai.sensing.IsInWaterSensor
- XXX.ai.sensing.NearestBedSensor
+ XXX.ai.sensing.NearestItemSensor
- XXX.ai.sensing.NearestLivingEntitySensor
+ XXX.ai.sensing.NearestVisibleLivingEntitySensor
+ XXX.ai.sensing.package-info
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
- XXX.ai.sensing.WardenEntitySensor
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
- XXX.animal.allay.AllayAi
- XXX.data.worldgen.AncientCityStructurePieces
- XXX.datafix.fixes.package-info
- XXX.datafix.fixes.SimplestEntityRenameFix
+ XXX.datafix.fixes.SpawnerDataFix
- XXX.datafix.fixes.StatsCounterFix
+ XXX.datafix.fixes.StatsRenameFix
- XXX.datafix.fixes.StriderGravityFix
+ XXX.datafix.fixes.StructureReferenceCountFix
+ XXX.datafix.fixes.StructuresBecomeConfiguredFix
- XXX.datafix.fixes.StructuresBecomeConfiguredFix$Conversion
- XXX.datafix.fixes.StructureSettingsFlattenFix
+ XXX.datafix.fixes.TeamDisplayNameFix
- XXX.datafix.fixes.TrappedChestBlockEntityFix
+ XXX.datafix.fixes.TrappedChestBlockEntityFix$TrappedChestSection
- XXX.datafix.fixes.VillagerDataFix
+ XXX.datafix.fixes.VillagerFollowRangeFix
- XXX.datafix.fixes.VillagerRebuildLevelAndXpFix
+ XXX.datafix.fixes.VillagerTradeFix
- XXX.datafix.fixes.WallPropertyFix
+ XXX.datafix.fixes.WeaponSmithChestLootTableFix
- XXX.datafix.fixes.WorldGenSettingsDisallowOldCustomWorldsFix
+ XXX.datafix.fixes.WorldGenSettingsFix
- XXX.datafix.fixes.WorldGenSettingsFix$StructureFeatureConfiguration
+ XXX.datafix.fixes.WorldGenSettingsHeightAndBiomeFix
- XXX.datafix.fixes.WriteAndReadFix
+ XXX.datafix.fixes.ZombieVillagerRebuildXpFix
- XXX.datafix.schemas.NamespacedSchema
+ XXX.datafix.schemas.NamespacedSchema$1
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
+ XXX.datafix.schemas.V1451_6$1
- XXX.datafix.schemas.V1451_6$2
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
+ XXX.datafix.schemas.V2519
- XXX.datafix.schemas.V2522
+ XXX.datafix.schemas.V2551
- XXX.datafix.schemas.V2568
+ XXX.datafix.schemas.V2571
- XXX.datafix.schemas.V2684
+ XXX.datafix.schemas.V2686
- XXX.datafix.schemas.V2688
+ XXX.datafix.schemas.V2704
- XXX.datafix.schemas.V2707
+ XXX.datafix.schemas.V2831
- XXX.datafix.schemas.V2832
+ XXX.datafix.schemas.V2842
- XXX.datafix.schemas.V3076
+ XXX.datafix.schemas.V3078
- XXX.datafix.schemas.V3081
+ XXX.datafix.schemas.V3082
- XXX.datafix.schemas.V3083
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
+ XXX.entity.animal.Dolphin$DolphinSwimToTreasureGoal
- XXX.entity.animal.Dolphin$DolphinSwimWithPlayerGoal
+ XXX.entity.animal.Dolphin$PlayWithItemsGoal
- XXX.entity.animal.FlyingAnimal
+ XXX.entity.animal.Fox
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
- XXX.entity.animal.Parrot$ParrotWanderGoal
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
- XXX.entity.animal.Squid$SquidFleeGoal
+ XXX.entity.animal.Squid$SquidRandomMovementGoal
- XXX.entity.animal.TropicalFish
+ XXX.entity.animal.TropicalFish$Pattern
- XXX.entity.animal.TropicalFish$TropicalFishGroupData
+ XXX.entity.animal.Turtle
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
- XXX.entity.animal.Wolf$WolfPanicGoal
+ XXX.feature.configurations.BlockColumnConfiguration
- XXX.feature.configurations.BlockColumnConfiguration$Layer
+ XXX.feature.configurations.BlockPileConfiguration
- XXX.feature.configurations.BlockStateConfiguration
+ XXX.feature.configurations.ColumnFeatureConfiguration
- XXX.feature.configurations.CountConfiguration
+ XXX.feature.configurations.DeltaFeatureConfiguration
- XXX.feature.configurations.DiskConfiguration
+ XXX.feature.configurations.DripstoneClusterConfiguration
- XXX.feature.configurations.EndGatewayConfiguration
+ XXX.feature.configurations.FeatureConfiguration
- XXX.feature.configurations.GeodeConfiguration
+ XXX.feature.configurations.HugeMushroomFeatureConfiguration
- XXX.feature.configurations.LargeDripstoneConfiguration
+ XXX.feature.configurations.LayerConfiguration
- XXX.feature.configurations.MultifaceGrowthConfiguration
+ XXX.feature.configurations.NetherForestVegetationConfig
- XXX.feature.configurations.NoneFeatureConfiguration
+ XXX.feature.configurations.OreConfiguration
- XXX.feature.configurations.OreConfiguration$TargetBlockState
+ XXX.feature.configurations.package-info
+ XXX.feature.configurations.PointedDripstoneConfiguration
- XXX.feature.configurations.ProbabilityFeatureConfiguration
+ XXX.feature.configurations.RandomBooleanFeatureConfiguration
- XXX.feature.configurations.RandomFeatureConfiguration
+ XXX.feature.configurations.RandomPatchConfiguration
- XXX.feature.configurations.ReplaceBlockConfiguration
+ XXX.feature.configurations.ReplaceSphereConfiguration
- XXX.feature.configurations.RootSystemConfiguration
+ XXX.feature.configurations.SculkPatchConfiguration
- XXX.feature.configurations.SimpleBlockConfiguration
+ XXX.feature.configurations.SimpleRandomFeatureConfiguration
- XXX.feature.configurations.SpikeConfiguration
+ XXX.feature.configurations.SpringConfiguration
- XXX.feature.configurations.TreeConfiguration
+ XXX.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
- XXX.feature.configurations.TwistingVinesConfig
+ XXX.feature.configurations.UnderwaterMagmaConfiguration
- XXX.feature.configurations.VegetationPatchConfiguration
- XXX.feature.featuresize.FeatureSize
+ XXX.feature.featuresize.FeatureSizeType
- XXX.feature.featuresize.package-info
- XXX.feature.featuresize.ThreeLayersFeatureSize
+ XXX.feature.featuresize.TwoLayersFeatureSize
+ XXX.feature.foliageplacers.AcaciaFoliagePlacer
- XXX.feature.foliageplacers.BlobFoliagePlacer
+ XXX.feature.foliageplacers.BushFoliagePlacer
- XXX.feature.foliageplacers.DarkOakFoliagePlacer
+ XXX.feature.foliageplacers.FancyFoliagePlacer
- XXX.feature.foliageplacers.FoliagePlacer
+ XXX.feature.foliageplacers.FoliagePlacer$FoliageAttachment
- XXX.feature.foliageplacers.FoliagePlacerType
+ XXX.feature.foliageplacers.MegaJungleFoliagePlacer
- XXX.feature.foliageplacers.MegaPineFoliagePlacer
- XXX.feature.foliageplacers.package-info
+ XXX.feature.foliageplacers.PineFoliagePlacer
- XXX.feature.foliageplacers.RandomSpreadFoliagePlacer
+ XXX.feature.foliageplacers.SpruceFoliagePlacer
- XXX.feature.stateproviders.BlockStateProvider
+ XXX.feature.stateproviders.BlockStateProviderType
- XXX.feature.stateproviders.DualNoiseProvider
+ XXX.feature.stateproviders.NoiseBasedStateProvider
- XXX.feature.stateproviders.NoiseProvider
+ XXX.feature.stateproviders.NoiseThresholdProvider
- XXX.feature.stateproviders.package-info
- XXX.feature.stateproviders.RandomizedIntStateProvider
+ XXX.feature.stateproviders.RotatedBlockProvider
- XXX.feature.stateproviders.SimpleStateProvider
+ XXX.feature.stateproviders.WeightedStateProvider
+ XXX.feature.treedecorators.AlterGroundDecorator
- XXX.feature.treedecorators.BeehiveDecorator
+ XXX.feature.treedecorators.CocoaDecorator
- XXX.feature.treedecorators.LeaveVineDecorator
- XXX.feature.treedecorators.package-info
+ XXX.feature.treedecorators.TreeDecorator
- XXX.feature.treedecorators.TreeDecoratorType
+ XXX.feature.treedecorators.TrunkVineDecorator
+ XXX.feature.trunkplacers.BendingTrunkPlacer
- XXX.feature.trunkplacers.DarkOakTrunkPlacer
+ XXX.feature.trunkplacers.FancyTrunkPlacer
- XXX.feature.trunkplacers.FancyTrunkPlacer$FoliageCoords
+ XXX.feature.trunkplacers.ForkingTrunkPlacer
- XXX.feature.trunkplacers.GiantTrunkPlacer
+ XXX.feature.trunkplacers.MegaJungleTrunkPlacer
+ XXX.feature.trunkplacers.package-info
- XXX.feature.trunkplacers.StraightTrunkPlacer
+ XXX.feature.trunkplacers.TrunkPlacer
- XXX.feature.trunkplacers.TrunkPlacerType
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
- XXX.level.levelgen.Beardifier$Rigid
- XXX.level.levelgen.package-info
+ XXX.levelgen.feature.OreFeature
+ XXX.levelgen.feature.package-info
- XXX.levelgen.feature.PointedDripstoneFeature
+ XXX.levelgen.feature.RandomBooleanSelectorFeature
- XXX.levelgen.feature.RandomPatchFeature
+ XXX.levelgen.feature.RandomSelectorFeature
- XXX.levelgen.feature.ReplaceBlobsFeature
+ XXX.levelgen.feature.ReplaceBlockFeature
- XXX.levelgen.feature.RootSystemFeature
+ XXX.levelgen.feature.ScatteredOreFeature
- XXX.levelgen.feature.SculkPatchFeature
- XXX.levelgen.feature.SeagrassFeature
+ XXX.levelgen.feature.SeaPickleFeature
+ XXX.levelgen.feature.SimpleBlockFeature
- XXX.levelgen.feature.SimpleRandomSelectorFeature
+ XXX.levelgen.feature.SnowAndFreezeFeature
- XXX.levelgen.feature.SpikeFeature
+ XXX.levelgen.feature.SpikeFeature$EndSpike
- XXX.levelgen.feature.SpikeFeature$SpikeCacheLoader
+ XXX.levelgen.feature.SpringFeature
- XXX.levelgen.feature.TreeFeature
+ XXX.levelgen.feature.TwistingVinesFeature
- XXX.levelgen.feature.UnderwaterMagmaFeature
+ XXX.levelgen.feature.VegetationPatchFeature
- XXX.levelgen.feature.VinesFeature
+ XXX.levelgen.feature.VoidStartPlatformFeature
- XXX.levelgen.feature.WaterloggedVegetationPatchFeature
+ XXX.levelgen.feature.WeepingVinesFeature
- XXX.levelgen.feature.WeightedPlacedFeature
- XXX.levelgen.flat.FlatLayerInfo
+ XXX.levelgen.flat.FlatLevelGeneratorPreset
- XXX.levelgen.flat.FlatLevelGeneratorPresets
+ XXX.levelgen.flat.FlatLevelGeneratorPresets$Bootstrap
- XXX.levelgen.flat.FlatLevelGeneratorSettings
+ XXX.levelgen.flat.package-info
- XXX.levelgen.heightproviders.BiasedToBottomHeight
+ XXX.levelgen.heightproviders.ConstantHeight
- XXX.levelgen.heightproviders.HeightProvider
+ XXX.levelgen.heightproviders.HeightProviderType
- XXX.levelgen.heightproviders.package-info
- XXX.levelgen.heightproviders.TrapezoidHeight
+ XXX.levelgen.heightproviders.UniformHeight
- XXX.levelgen.heightproviders.VeryBiasedToBottomHeight
+ XXX.levelgen.heightproviders.WeightedListHeight
+ XXX.levelgen.material.MaterialRuleList
+ XXX.levelgen.material.package-info
- XXX.levelgen.material.WorldGenMaterialRule
+ XXX.levelgen.placement.BiomeFilter
- XXX.levelgen.placement.BlockPredicateFilter
+ XXX.levelgen.placement.CarvingMaskPlacement
- XXX.levelgen.placement.CaveSurface
+ XXX.levelgen.placement.CountOnEveryLayerPlacement
- XXX.levelgen.placement.CountPlacement
+ XXX.levelgen.placement.EnvironmentScanPlacement
+ XXX.levelgen.placement.HeightmapPlacement
- XXX.levelgen.placement.HeightRangePlacement
- XXX.levelgen.placement.InSquarePlacement
+ XXX.levelgen.placement.NoiseBasedCountPlacement
- XXX.levelgen.placement.NoiseThresholdCountPlacement
- XXX.levelgen.placement.package-info
+ XXX.levelgen.placement.PlacedFeature
- XXX.levelgen.placement.PlacedFeature$test
+ XXX.levelgen.placement.PlacementContext
- XXX.levelgen.placement.PlacementFilter
+ XXX.levelgen.placement.PlacementModifier
- XXX.levelgen.placement.PlacementModifierType
+ XXX.levelgen.placement.RandomOffsetPlacement
- XXX.levelgen.placement.RarityFilter
+ XXX.levelgen.placement.RepeatingPlacement
- XXX.levelgen.placement.SurfaceRelativeThresholdFilter
+ XXX.levelgen.placement.SurfaceWaterDepthFilter
+ XXX.levelgen.presets.WorldPreset
- XXX.levelgen.presets.WorldPresets
+ XXX.levelgen.presets.WorldPresets$Bootstrap
- XXX.levelgen.structure.BoundingBox
+ XXX.levelgen.structure.BoundingBox$1
+ XXX.levelgen.structure.BuiltinStructures
- XXX.levelgen.structure.BuiltinStructureSets
- XXX.levelgen.structure.LegacyStructureDataHandler
+ XXX.levelgen.structure.package-info
+ XXX.levelgen.structure.PoolElementStructurePiece
- XXX.levelgen.structure.PostPlacementProcessor
+ XXX.levelgen.structure.ScatteredFeaturePiece
- XXX.levelgen.structure.SinglePieceStructure
+ XXX.levelgen.structure.SinglePieceStructure$PieceConstructor
- XXX.levelgen.structure.Structure
+ XXX.levelgen.structure.Structure$GenerationContext
- XXX.levelgen.structure.Structure$GenerationStub
- XXX.levelgen.structure.TerrainAdjustment
- XXX.minecraft.util.OptionEnum
+ XXX.minecraft.util.ParticleUtils
- XXX.minecraft.util.ProgressListener
+ XXX.minecraft.util.SimpleBitStorage
- XXX.minecraft.util.SimpleBitStorage$InitializationException
+ XXX.minecraft.util.SmoothDouble
- XXX.minecraft.util.SortedArraySet
+ XXX.minecraft.util.SortedArraySet$ArrayIterator
- XXX.minecraft.util.SpawnUtil
+ XXX.minecraft.util.StringDecomposer
- XXX.minecraft.util.StringRepresentable
+ XXX.minecraft.util.StringRepresentable$1
- XXX.minecraft.util.StringRepresentable$EnumCodec
- XXX.structure.pieces.package-info
- XXX.structure.pieces.PieceGenerator
+ XXX.structure.pieces.PieceGenerator$Context
- XXX.structure.pieces.PieceGeneratorSupplier
+ XXX.structure.pieces.PieceGeneratorSupplier$Context
- XXX.structure.pieces.PiecesContainer
+ XXX.structure.pieces.StructurePiecesBuilder
+ XXX.structure.pieces.StructurePieceSerializationContext
- XXX.structure.pieces.StructurePieceType
+ XXX.structure.pieces.StructurePieceType$ContextlessType
- XXX.structure.pieces.StructurePieceType$StructureTemplateType
+ XXX.structure.placement.ConcentricRingsStructurePlacement
- XXX.structure.placement.package-info
- XXX.structure.placement.RandomSpreadStructurePlacement
+ XXX.structure.placement.RandomSpreadType
- XXX.structure.placement.RandomSpreadType$1
+ XXX.structure.placement.StructurePlacement
- XXX.structure.placement.StructurePlacement$ExclusionZone
+ XXX.structure.placement.StructurePlacement$FrequencyReducer
- XXX.structure.placement.StructurePlacement$FrequencyReductionMethod
+ XXX.structure.placement.StructurePlacementType
+ XXX.structure.pools.EmptyPoolElement
- XXX.structure.pools.FeaturePoolElement
+ XXX.structure.pools.JigsawJunction
- XXX.structure.pools.JigsawPlacement
+ XXX.structure.pools.JigsawPlacement$PieceFactory
- XXX.structure.pools.JigsawPlacement$PieceState
+ XXX.structure.pools.JigsawPlacement$Placer
- XXX.structure.pools.LegacySinglePoolElement
+ XXX.structure.pools.ListPoolElement
+ XXX.structure.pools.package-info
- XXX.structure.pools.SinglePoolElement
+ XXX.structure.pools.StructurePoolElement
- XXX.structure.pools.StructurePoolElementType
+ XXX.structure.pools.StructureTemplatePool
- XXX.structure.pools.StructureTemplatePool$Projection
- XXX.structure.structures.BuriedTreasurePieces
+ XXX.structure.structures.BuriedTreasurePieces$BuriedTreasurePiece
- XXX.structure.structures.BuriedTreasureStructure
+ XXX.structure.structures.DesertPyramidPiece
- XXX.structure.structures.DesertPyramidStructure
+ XXX.structure.structures.EndCityPieces
- XXX.structure.structures.EndCityPieces$1
+ XXX.structure.structures.EndCityPieces$2
- XXX.structure.structures.EndCityPieces$3
+ XXX.structure.structures.EndCityPieces$4
- XXX.structure.structures.EndCityPieces$EndCityPiece
+ XXX.structure.structures.EndCityPieces$SectionGenerator
- XXX.structure.structures.EndCityStructure
+ XXX.structure.structures.IglooPieces
- XXX.structure.structures.IglooPieces$IglooPiece
+ XXX.structure.structures.IglooStructure
- XXX.structure.structures.JigsawStructure
+ XXX.util.datafix.package-info
+ XXX.village.poi.package-info
+ XXX.village.poi.PoiManager
- XXX.village.poi.PoiManager$DistanceTracker
+ XXX.village.poi.PoiManager$Occupancy
- XXX.village.poi.PoiRecord
+ XXX.village.poi.PoiSection
- XXX.village.poi.PoiType
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
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
- XXX.ai.behavior.FlyingRandomStroll
+ XXX.ai.behavior.FollowTemptation
- XXX.ai.behavior.GateBehavior
+ XXX.ai.behavior.GateBehavior$OrderPolicy
- XXX.ai.behavior.GateBehavior$RunningPolicy
+ XXX.ai.behavior.GateBehavior$RunningPolicy$1
- XXX.ai.behavior.GateBehavior$RunningPolicy$2
+ XXX.ai.behavior.GiveGiftToHero
- XXX.ai.behavior.GoAndGiveItemsToTarget
+ XXX.ai.behavior.package-info
- XXX.ai.behavior.StayCloseToTarget
+ XXX.ai.behavior.StopAttackingIfTargetInvalid
- XXX.ai.behavior.StopBeingAngryIfTargetDead
+ XXX.ai.behavior.StrollAroundPoi
- XXX.ai.behavior.StrollToPoi
+ XXX.ai.behavior.StrollToPoiList
- XXX.ai.behavior.Swim
+ XXX.ai.behavior.TradeWithVillager
- XXX.ai.behavior.TryFindLand
+ XXX.ai.behavior.TryFindLandNearWater
- XXX.ai.behavior.TryFindWater
+ XXX.ai.behavior.TryLaySpawnOnWaterNearLand
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
- XXX.ai.behavior.WorkAtComposter
+ XXX.ai.behavior.WorkAtPoi
- XXX.ai.behavior.YieldJobSite
- XXX.ai.control.BodyRotationControl
+ XXX.ai.control.Control
- XXX.ai.control.FlyingMoveControl
+ XXX.ai.control.JumpControl
- XXX.ai.control.LookControl
+ XXX.ai.control.MoveControl
- XXX.ai.control.MoveControl$Operation
+ XXX.ai.control.package-info
+ XXX.ai.control.SmoothSwimmingLookControl
- XXX.ai.control.SmoothSwimmingMoveControl
- XXX.ai.goal.AvoidEntityGoal
+ XXX.ai.goal.BegGoal
- XXX.ai.goal.BoatGoals
+ XXX.ai.goal.BreakDoorGoal
- XXX.ai.goal.BreathAirGoal
+ XXX.ai.goal.BreedGoal
- XXX.ai.goal.CatLieOnBedGoal
+ XXX.ai.goal.CatSitOnBlockGoal
- XXX.ai.goal.ClimbOnTopOfPowderSnowGoal
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
- XXX.ai.goal.TemptGoal
+ XXX.ai.goal.TradeWithPlayerGoal
- XXX.ai.goal.TryFindWaterGoal
+ XXX.ai.goal.UseItemGoal
- XXX.ai.goal.WaterAvoidingRandomFlyingGoal
+ XXX.ai.goal.WaterAvoidingRandomStrollGoal
- XXX.ai.goal.WrappedGoal
+ XXX.ai.goal.ZombieAttackGoal
- XXX.ai.gossip.GossipContainer
+ XXX.ai.gossip.GossipContainer$EntityGossips
- XXX.ai.gossip.GossipContainer$GossipEntry
+ XXX.ai.gossip.GossipType
- XXX.ai.gossip.package-info
+ XXX.ai.memory.ExpirableValue
- XXX.ai.memory.MemoryModuleType
+ XXX.ai.memory.MemoryStatus
- XXX.ai.memory.NearestVisibleLivingEntities
- XXX.ai.memory.package-info
+ XXX.ai.memory.WalkTarget
+ XXX.ai.navigation.FlyingPathNavigation
- XXX.ai.navigation.GroundPathNavigation
- XXX.ai.navigation.package-info
+ XXX.ai.navigation.PathNavigation
- XXX.ai.navigation.WallClimberNavigation
+ XXX.ai.navigation.WaterBoundPathNavigation
- XXX.ai.sensing.AdultSensor
+ XXX.ai.sensing.AxolotlAttackablesSensor
- XXX.ai.sensing.DummySensor
+ XXX.ai.sensing.FrogAttackablesSensor
- XXX.ai.sensing.GolemSensor
+ XXX.ai.sensing.HoglinSpecificSensor
- XXX.ai.sensing.HurtBySensor
+ XXX.ai.sensing.IsInWaterSensor
- XXX.ai.sensing.NearestBedSensor
+ XXX.ai.sensing.NearestItemSensor
- XXX.ai.sensing.NearestLivingEntitySensor
+ XXX.ai.sensing.NearestVisibleLivingEntitySensor
+ XXX.ai.sensing.package-info
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
- XXX.ai.sensing.WardenEntitySensor
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
- XXX.animal.allay.AllayAi
- XXX.client.model.AllayModel
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
+ XXX.client.model.FrogModel
- XXX.client.model.GhastModel
+ XXX.client.model.GiantZombieModel
- XXX.client.model.GoatModel
+ XXX.client.model.GuardianModel
- XXX.client.model.HeadedModel
+ XXX.client.model.HierarchicalModel
- XXX.client.model.HoglinModel
+ XXX.client.model.HorseModel
- XXX.client.model.HumanoidModel
+ XXX.client.model.HumanoidModel$1
- XXX.client.model.HumanoidModel$ArmPose
+ XXX.client.model.IllagerModel
- XXX.client.model.IronGolemModel
+ XXX.client.model.LavaSlimeModel
- XXX.client.model.LeashKnotModel
+ XXX.client.model.ListModel
- XXX.client.model.LlamaModel
+ XXX.client.model.LlamaSpitModel
- XXX.client.model.MinecartModel
+ XXX.client.model.Model
- XXX.client.model.ModelUtils
+ XXX.client.model.OcelotModel
+ XXX.client.model.package-info
- XXX.client.model.PandaModel
+ XXX.client.model.ParrotModel
- XXX.client.model.ParrotModel$1
+ XXX.client.model.ParrotModel$State
- XXX.client.model.PhantomModel
- XXX.client.model.PiglinModel
+ XXX.client.model.PigModel
+ XXX.client.model.PlayerModel
- XXX.client.model.PolarBearModel
+ XXX.client.model.PufferfishBigModel
- XXX.client.model.PufferfishMidModel
+ XXX.client.model.PufferfishSmallModel
- XXX.client.model.QuadrupedModel
+ XXX.client.model.RabbitModel
- XXX.client.model.RavagerModel
+ XXX.client.model.SalmonModel
- XXX.client.model.SheepFurModel
+ XXX.client.model.SheepModel
- XXX.client.model.ShieldModel
+ XXX.client.model.ShulkerBulletModel
- XXX.client.model.ShulkerModel
+ XXX.client.model.SilverfishModel
- XXX.client.model.SkeletonModel
+ XXX.client.model.SkullModel
- XXX.client.model.SkullModelBase
+ XXX.client.model.SlimeModel
- XXX.client.model.SnowGolemModel
+ XXX.client.model.SpiderModel
- XXX.client.model.SquidModel
+ XXX.client.model.StriderModel
- XXX.client.model.TadpoleModel
+ XXX.client.model.TridentModel
- XXX.client.model.TropicalFishModelA
+ XXX.client.model.TropicalFishModelB
- XXX.client.model.TurtleModel
+ XXX.client.model.VexModel
- XXX.client.model.VillagerHeadModel
+ XXX.client.model.VillagerModel
- XXX.client.model.WardenModel
+ XXX.client.model.WitchModel
- XXX.client.model.WitherBossModel
+ XXX.client.model.WolfModel
- XXX.client.model.ZombieModel
+ XXX.client.model.ZombieVillagerModel
- XXX.client.multiplayer.ClientAdvancements
+ XXX.client.multiplayer.ClientAdvancements$Listener
- XXX.client.multiplayer.ClientChunkCache
+ XXX.client.multiplayer.ClientChunkCache$Storage
- XXX.client.multiplayer.ClientHandshakePacketListenerImpl
+ XXX.client.multiplayer.ClientLevel
- XXX.client.multiplayer.ClientLevel$1
+ XXX.client.multiplayer.ClientLevel$ClientLevelData
- XXX.client.multiplayer.ClientLevel$EntityCallbacks
+ XXX.client.multiplayer.ClientPacketListener
- XXX.client.multiplayer.ClientPacketListener$1
+ XXX.client.multiplayer.ClientSuggestionProvider
- XXX.client.multiplayer.MultiPlayerGameMode
+ XXX.client.multiplayer.package-info
+ XXX.client.multiplayer.PlayerInfo
- XXX.client.multiplayer.ServerData
+ XXX.client.multiplayer.ServerData$ServerPackStatus
- XXX.client.multiplayer.ServerList
+ XXX.client.multiplayer.ServerStatusPinger
- XXX.client.multiplayer.ServerStatusPinger$1
+ XXX.client.multiplayer.ServerStatusPinger$2
- XXX.client.multiplayer.ServerStatusPinger$2$1
- XXX.client.particle.AshParticle
+ XXX.client.particle.AshParticle$Provider
- XXX.client.particle.AttackSweepParticle
+ XXX.client.particle.AttackSweepParticle$Provider
- XXX.client.particle.BaseAshSmokeParticle
+ XXX.client.particle.BlockMarker
- XXX.client.particle.BlockMarker$Provider
+ XXX.client.particle.BreakingItemParticle
- XXX.client.particle.BreakingItemParticle$Provider
+ XXX.client.particle.BreakingItemParticle$SlimeProvider
- XXX.client.particle.BreakingItemParticle$SnowballProvider
+ XXX.client.particle.BubbleColumnUpParticle
- XXX.client.particle.BubbleColumnUpParticle$Provider
+ XXX.client.particle.BubbleParticle
- XXX.client.particle.BubbleParticle$Provider
+ XXX.client.particle.BubblePopParticle
- XXX.client.particle.BubblePopParticle$Provider
+ XXX.client.particle.CampfireSmokeParticle
- XXX.client.particle.CampfireSmokeParticle$CosyProvider
+ XXX.client.particle.CampfireSmokeParticle$SignalProvider
- XXX.client.particle.CritParticle
+ XXX.client.particle.CritParticle$DamageIndicatorProvider
- XXX.client.particle.CritParticle$MagicProvider
+ XXX.client.particle.CritParticle$Provider
- XXX.client.particle.DragonBreathParticle
+ XXX.client.particle.DragonBreathParticle$Provider
- XXX.client.particle.DripParticle
+ XXX.client.particle.DripParticle$CoolingDripHangParticle
- XXX.client.particle.DripParticle$DripHangParticle
+ XXX.client.particle.DripParticle$DripLandParticle
- XXX.client.particle.DripParticle$DripstoneFallAndLandParticle
+ XXX.client.particle.DripParticle$DripstoneLavaFallProvider
- XXX.client.particle.DripParticle$DripstoneLavaHangProvider
+ XXX.client.particle.DripParticle$DripstoneWaterFallProvider
- XXX.client.particle.DripParticle$DripstoneWaterHangProvider
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
+ XXX.client.particle.DripParticle$ObsidianTearFallProvider
- XXX.client.particle.DripParticle$ObsidianTearHangProvider
+ XXX.client.particle.DripParticle$ObsidianTearLandProvider
- XXX.client.particle.DripParticle$SporeBlossomFallProvider
+ XXX.client.particle.DripParticle$WaterFallProvider
- XXX.client.particle.DripParticle$WaterHangProvider
+ XXX.client.particle.DustColorTransitionParticle
- XXX.client.particle.DustColorTransitionParticle$Provider
+ XXX.client.particle.DustParticle
- XXX.client.particle.DustParticle$Provider
+ XXX.client.particle.DustParticleBase
- XXX.client.particle.EnchantmentTableParticle
+ XXX.client.particle.EnchantmentTableParticle$NautilusProvider
- XXX.client.particle.EnchantmentTableParticle$Provider
+ XXX.client.particle.EndRodParticle
- XXX.client.particle.EndRodParticle$Provider
+ XXX.client.particle.ExplodeParticle
- XXX.client.particle.ExplodeParticle$Provider
+ XXX.client.particle.FallingDustParticle
- XXX.client.particle.FallingDustParticle$Provider
+ XXX.client.particle.FireworkParticles
- XXX.client.particle.FireworkParticles$1
+ XXX.client.particle.FireworkParticles$FlashProvider
- XXX.client.particle.FireworkParticles$OverlayParticle
+ XXX.client.particle.FireworkParticles$SparkParticle
- XXX.client.particle.FireworkParticles$SparkProvider
+ XXX.client.particle.FireworkParticles$Starter
- XXX.client.particle.FlameParticle
+ XXX.client.particle.FlameParticle$Provider
- XXX.client.particle.FlameParticle$SmallFlameProvider
+ XXX.client.particle.GlowParticle
- XXX.client.particle.GlowParticle$AllayDustProvider
- XXX.data.worldgen.AncientCityStructurePools
- XXX.datafix.fixes.package-info
- XXX.datafix.fixes.SimplestEntityRenameFix
+ XXX.datafix.fixes.SpawnerDataFix
- XXX.datafix.fixes.StatsCounterFix
+ XXX.datafix.fixes.StatsRenameFix
- XXX.datafix.fixes.StriderGravityFix
+ XXX.datafix.fixes.StructureReferenceCountFix
+ XXX.datafix.fixes.StructuresBecomeConfiguredFix
- XXX.datafix.fixes.StructuresBecomeConfiguredFix$Conversion
- XXX.datafix.fixes.StructureSettingsFlattenFix
+ XXX.datafix.fixes.TeamDisplayNameFix
- XXX.datafix.fixes.TrappedChestBlockEntityFix
+ XXX.datafix.fixes.TrappedChestBlockEntityFix$TrappedChestSection
- XXX.datafix.fixes.VillagerDataFix
+ XXX.datafix.fixes.VillagerFollowRangeFix
- XXX.datafix.fixes.VillagerRebuildLevelAndXpFix
+ XXX.datafix.fixes.VillagerTradeFix
- XXX.datafix.fixes.WallPropertyFix
+ XXX.datafix.fixes.WeaponSmithChestLootTableFix
- XXX.datafix.fixes.WorldGenSettingsDisallowOldCustomWorldsFix
+ XXX.datafix.fixes.WorldGenSettingsFix
- XXX.datafix.fixes.WorldGenSettingsFix$StructureFeatureConfiguration
+ XXX.datafix.fixes.WorldGenSettingsHeightAndBiomeFix
- XXX.datafix.fixes.WriteAndReadFix
+ XXX.datafix.fixes.ZombieVillagerRebuildXpFix
- XXX.datafix.schemas.NamespacedSchema
+ XXX.datafix.schemas.NamespacedSchema$1
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
+ XXX.datafix.schemas.V1451_6$1
- XXX.datafix.schemas.V1451_6$2
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
+ XXX.datafix.schemas.V2519
- XXX.datafix.schemas.V2522
+ XXX.datafix.schemas.V2551
- XXX.datafix.schemas.V2568
+ XXX.datafix.schemas.V2571
- XXX.datafix.schemas.V2684
+ XXX.datafix.schemas.V2686
- XXX.datafix.schemas.V2688
+ XXX.datafix.schemas.V2704
- XXX.datafix.schemas.V2707
+ XXX.datafix.schemas.V2831
- XXX.datafix.schemas.V2832
+ XXX.datafix.schemas.V2842
- XXX.datafix.schemas.V3076
+ XXX.datafix.schemas.V3078
- XXX.datafix.schemas.V3081
+ XXX.datafix.schemas.V3082
- XXX.datafix.schemas.V3083
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
+ XXX.entity.animal.Dolphin$DolphinSwimToTreasureGoal
- XXX.entity.animal.Dolphin$DolphinSwimWithPlayerGoal
+ XXX.entity.animal.Dolphin$PlayWithItemsGoal
- XXX.entity.animal.FlyingAnimal
+ XXX.entity.animal.Fox
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
- XXX.entity.animal.Parrot$ParrotWanderGoal
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
- XXX.entity.animal.Squid$SquidFleeGoal
+ XXX.entity.animal.Squid$SquidRandomMovementGoal
- XXX.entity.animal.TropicalFish
+ XXX.entity.animal.TropicalFish$Pattern
- XXX.entity.animal.TropicalFish$TropicalFishGroupData
+ XXX.entity.animal.Turtle
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
- XXX.entity.animal.Wolf$WolfPanicGoal
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
+ XXX.entity.layers.WardenEmissiveLayer
- XXX.entity.layers.WardenEmissiveLayer$AlphaFunction
+ XXX.feature.configurations.BlockColumnConfiguration
- XXX.feature.configurations.BlockColumnConfiguration$Layer
+ XXX.feature.configurations.BlockPileConfiguration
- XXX.feature.configurations.BlockStateConfiguration
+ XXX.feature.configurations.ColumnFeatureConfiguration
- XXX.feature.configurations.CountConfiguration
+ XXX.feature.configurations.DeltaFeatureConfiguration
- XXX.feature.configurations.DiskConfiguration
+ XXX.feature.configurations.DripstoneClusterConfiguration
- XXX.feature.configurations.EndGatewayConfiguration
+ XXX.feature.configurations.FeatureConfiguration
- XXX.feature.configurations.GeodeConfiguration
+ XXX.feature.configurations.HugeMushroomFeatureConfiguration
- XXX.feature.configurations.LargeDripstoneConfiguration
+ XXX.feature.configurations.LayerConfiguration
- XXX.feature.configurations.MultifaceGrowthConfiguration
+ XXX.feature.configurations.NetherForestVegetationConfig
- XXX.feature.configurations.NoneFeatureConfiguration
+ XXX.feature.configurations.OreConfiguration
- XXX.feature.configurations.OreConfiguration$TargetBlockState
+ XXX.feature.configurations.package-info
+ XXX.feature.configurations.PointedDripstoneConfiguration
- XXX.feature.configurations.ProbabilityFeatureConfiguration
+ XXX.feature.configurations.RandomBooleanFeatureConfiguration
- XXX.feature.configurations.RandomFeatureConfiguration
+ XXX.feature.configurations.RandomPatchConfiguration
- XXX.feature.configurations.ReplaceBlockConfiguration
+ XXX.feature.configurations.ReplaceSphereConfiguration
- XXX.feature.configurations.RootSystemConfiguration
+ XXX.feature.configurations.SculkPatchConfiguration
- XXX.feature.configurations.SimpleBlockConfiguration
+ XXX.feature.configurations.SimpleRandomFeatureConfiguration
- XXX.feature.configurations.SpikeConfiguration
+ XXX.feature.configurations.SpringConfiguration
- XXX.feature.configurations.TreeConfiguration
+ XXX.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
- XXX.feature.configurations.TwistingVinesConfig
+ XXX.feature.configurations.UnderwaterMagmaConfiguration
- XXX.feature.configurations.VegetationPatchConfiguration
- XXX.feature.featuresize.FeatureSize
+ XXX.feature.featuresize.FeatureSizeType
- XXX.feature.featuresize.package-info
- XXX.feature.featuresize.ThreeLayersFeatureSize
+ XXX.feature.featuresize.TwoLayersFeatureSize
+ XXX.feature.foliageplacers.AcaciaFoliagePlacer
- XXX.feature.foliageplacers.BlobFoliagePlacer
+ XXX.feature.foliageplacers.BushFoliagePlacer
- XXX.feature.foliageplacers.DarkOakFoliagePlacer
+ XXX.feature.foliageplacers.FancyFoliagePlacer
- XXX.feature.foliageplacers.FoliagePlacer
+ XXX.feature.foliageplacers.FoliagePlacer$FoliageAttachment
- XXX.feature.foliageplacers.FoliagePlacerType
+ XXX.feature.foliageplacers.MegaJungleFoliagePlacer
- XXX.feature.foliageplacers.MegaPineFoliagePlacer
- XXX.feature.foliageplacers.package-info
+ XXX.feature.foliageplacers.PineFoliagePlacer
- XXX.feature.foliageplacers.RandomSpreadFoliagePlacer
+ XXX.feature.foliageplacers.SpruceFoliagePlacer
- XXX.feature.stateproviders.BlockStateProvider
+ XXX.feature.stateproviders.BlockStateProviderType
- XXX.feature.stateproviders.DualNoiseProvider
+ XXX.feature.stateproviders.NoiseBasedStateProvider
- XXX.feature.stateproviders.NoiseProvider
+ XXX.feature.stateproviders.NoiseThresholdProvider
- XXX.feature.stateproviders.package-info
- XXX.feature.stateproviders.RandomizedIntStateProvider
+ XXX.feature.stateproviders.RotatedBlockProvider
- XXX.feature.stateproviders.SimpleStateProvider
+ XXX.feature.stateproviders.WeightedStateProvider
+ XXX.feature.treedecorators.AlterGroundDecorator
- XXX.feature.treedecorators.BeehiveDecorator
+ XXX.feature.treedecorators.CocoaDecorator
- XXX.feature.treedecorators.LeaveVineDecorator
- XXX.feature.treedecorators.package-info
+ XXX.feature.treedecorators.TreeDecorator
- XXX.feature.treedecorators.TreeDecoratorType
+ XXX.feature.treedecorators.TrunkVineDecorator
+ XXX.feature.trunkplacers.BendingTrunkPlacer
- XXX.feature.trunkplacers.DarkOakTrunkPlacer
+ XXX.feature.trunkplacers.FancyTrunkPlacer
- XXX.feature.trunkplacers.FancyTrunkPlacer$FoliageCoords
+ XXX.feature.trunkplacers.ForkingTrunkPlacer
- XXX.feature.trunkplacers.GiantTrunkPlacer
+ XXX.feature.trunkplacers.MegaJungleTrunkPlacer
+ XXX.feature.trunkplacers.package-info
- XXX.feature.trunkplacers.StraightTrunkPlacer
+ XXX.feature.trunkplacers.TrunkPlacer
- XXX.feature.trunkplacers.TrunkPlacerType
+ XXX.geom.builders.CubeDefinition
- XXX.geom.builders.CubeDeformation
+ XXX.geom.builders.CubeListBuilder
- XXX.geom.builders.LayerDefinition
+ XXX.geom.builders.MaterialDefinition
- XXX.geom.builders.MeshDefinition
+ XXX.geom.builders.package-info
+ XXX.geom.builders.PartDefinition
- XXX.geom.builders.UVPair
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
- XXX.level.levelgen.Beardifier$Rigid
- XXX.level.levelgen.package-info
+ XXX.levelgen.feature.OreFeature
+ XXX.levelgen.feature.package-info
- XXX.levelgen.feature.PointedDripstoneFeature
+ XXX.levelgen.feature.RandomBooleanSelectorFeature
- XXX.levelgen.feature.RandomPatchFeature
+ XXX.levelgen.feature.RandomSelectorFeature
- XXX.levelgen.feature.ReplaceBlobsFeature
+ XXX.levelgen.feature.ReplaceBlockFeature
- XXX.levelgen.feature.RootSystemFeature
+ XXX.levelgen.feature.ScatteredOreFeature
- XXX.levelgen.feature.SculkPatchFeature
- XXX.levelgen.feature.SeagrassFeature
+ XXX.levelgen.feature.SeaPickleFeature
+ XXX.levelgen.feature.SimpleBlockFeature
- XXX.levelgen.feature.SimpleRandomSelectorFeature
+ XXX.levelgen.feature.SnowAndFreezeFeature
- XXX.levelgen.feature.SpikeFeature
+ XXX.levelgen.feature.SpikeFeature$EndSpike
- XXX.levelgen.feature.SpikeFeature$SpikeCacheLoader
+ XXX.levelgen.feature.SpringFeature
- XXX.levelgen.feature.TreeFeature
+ XXX.levelgen.feature.TwistingVinesFeature
- XXX.levelgen.feature.UnderwaterMagmaFeature
+ XXX.levelgen.feature.VegetationPatchFeature
- XXX.levelgen.feature.VinesFeature
+ XXX.levelgen.feature.VoidStartPlatformFeature
- XXX.levelgen.feature.WaterloggedVegetationPatchFeature
+ XXX.levelgen.feature.WeepingVinesFeature
- XXX.levelgen.feature.WeightedPlacedFeature
- XXX.levelgen.flat.FlatLayerInfo
+ XXX.levelgen.flat.FlatLevelGeneratorPreset
- XXX.levelgen.flat.FlatLevelGeneratorPresets
+ XXX.levelgen.flat.FlatLevelGeneratorPresets$Bootstrap
- XXX.levelgen.flat.FlatLevelGeneratorSettings
+ XXX.levelgen.flat.package-info
- XXX.levelgen.heightproviders.BiasedToBottomHeight
+ XXX.levelgen.heightproviders.ConstantHeight
- XXX.levelgen.heightproviders.HeightProvider
+ XXX.levelgen.heightproviders.HeightProviderType
- XXX.levelgen.heightproviders.package-info
- XXX.levelgen.heightproviders.TrapezoidHeight
+ XXX.levelgen.heightproviders.UniformHeight
- XXX.levelgen.heightproviders.VeryBiasedToBottomHeight
+ XXX.levelgen.heightproviders.WeightedListHeight
+ XXX.levelgen.material.MaterialRuleList
+ XXX.levelgen.material.package-info
- XXX.levelgen.material.WorldGenMaterialRule
+ XXX.levelgen.placement.BiomeFilter
- XXX.levelgen.placement.BlockPredicateFilter
+ XXX.levelgen.placement.CarvingMaskPlacement
- XXX.levelgen.placement.CaveSurface
+ XXX.levelgen.placement.CountOnEveryLayerPlacement
- XXX.levelgen.placement.CountPlacement
+ XXX.levelgen.placement.EnvironmentScanPlacement
+ XXX.levelgen.placement.HeightmapPlacement
- XXX.levelgen.placement.HeightRangePlacement
- XXX.levelgen.placement.InSquarePlacement
+ XXX.levelgen.placement.NoiseBasedCountPlacement
- XXX.levelgen.placement.NoiseThresholdCountPlacement
- XXX.levelgen.placement.package-info
+ XXX.levelgen.placement.PlacedFeature
- XXX.levelgen.placement.PlacedFeature$test
+ XXX.levelgen.placement.PlacementContext
- XXX.levelgen.placement.PlacementFilter
+ XXX.levelgen.placement.PlacementModifier
- XXX.levelgen.placement.PlacementModifierType
+ XXX.levelgen.placement.RandomOffsetPlacement
- XXX.levelgen.placement.RarityFilter
+ XXX.levelgen.placement.RepeatingPlacement
- XXX.levelgen.placement.SurfaceRelativeThresholdFilter
+ XXX.levelgen.placement.SurfaceWaterDepthFilter
+ XXX.levelgen.presets.WorldPreset
- XXX.levelgen.presets.WorldPresets
+ XXX.levelgen.presets.WorldPresets$Bootstrap
- XXX.levelgen.structure.BoundingBox
+ XXX.levelgen.structure.BoundingBox$1
+ XXX.levelgen.structure.BuiltinStructures
- XXX.levelgen.structure.BuiltinStructureSets
- XXX.levelgen.structure.LegacyStructureDataHandler
+ XXX.levelgen.structure.package-info
+ XXX.levelgen.structure.PoolElementStructurePiece
- XXX.levelgen.structure.PostPlacementProcessor
+ XXX.levelgen.structure.ScatteredFeaturePiece
- XXX.levelgen.structure.SinglePieceStructure
+ XXX.levelgen.structure.SinglePieceStructure$PieceConstructor
- XXX.levelgen.structure.Structure
+ XXX.levelgen.structure.Structure$GenerationContext
- XXX.levelgen.structure.Structure$GenerationStub
- XXX.levelgen.structure.TerrainAdjustment
+ XXX.minecraft.client.OptionInstance$AltEnum
- XXX.minecraft.client.OptionInstance$CaptionBasedToString
- XXX.minecraft.client.OptionInstance$CycleableValueSet
- XXX.minecraft.client.OptionInstance$SliderableOrCyclableValueSet
+ XXX.minecraft.client.OptionInstance$SliderableValueSet
- XXX.minecraft.client.OptionInstance$TooltipSupplier
+ XXX.minecraft.client.package-info
- XXX.minecraft.util.OptionEnum
+ XXX.minecraft.util.ParticleUtils
- XXX.minecraft.util.ProgressListener
+ XXX.minecraft.util.SimpleBitStorage
- XXX.minecraft.util.SimpleBitStorage$InitializationException
+ XXX.minecraft.util.SmoothDouble
- XXX.minecraft.util.SortedArraySet
+ XXX.minecraft.util.SortedArraySet$ArrayIterator
- XXX.minecraft.util.SpawnUtil
+ XXX.minecraft.util.StringDecomposer
- XXX.minecraft.util.StringRepresentable
+ XXX.minecraft.util.StringRepresentable$1
- XXX.minecraft.util.StringRepresentable$EnumCodec
- XXX.model.dragon.DragonHeadModel
+ XXX.model.dragon.package-info
- XXX.model.geom.EntityModelSet
+ XXX.model.geom.LayerDefinitions
- XXX.model.geom.ModelLayerLocation
+ XXX.model.geom.ModelLayers
- XXX.model.geom.ModelPart
+ XXX.model.geom.ModelPart$Cube
- XXX.model.geom.ModelPart$Polygon
+ XXX.model.geom.ModelPart$Vertex
- XXX.model.geom.ModelPart$Visitor
- XXX.model.geom.package-info
+ XXX.model.geom.PartNames
- XXX.model.geom.PartPose
- XXX.multiplayer.prediction.BlockStatePredictionHandler
+ XXX.multiplayer.prediction.BlockStatePredictionHandler$ServerVerifiedState
+ XXX.multiplayer.prediction.package-info
- XXX.multiplayer.prediction.PredictiveAction
- XXX.multiplayer.resolver.AddressCheck
+ XXX.multiplayer.resolver.AddressCheck$1
- XXX.multiplayer.resolver.package-info
- XXX.multiplayer.resolver.ResolvedServerAddress
+ XXX.multiplayer.resolver.ResolvedServerAddress$1
- XXX.multiplayer.resolver.ServerAddress
+ XXX.multiplayer.resolver.ServerAddressResolver
- XXX.multiplayer.resolver.ServerNameResolver
+ XXX.multiplayer.resolver.ServerRedirectHandler
- XXX.renderer.entity.AllayRenderer
+ XXX.renderer.entity.ArmorStandRenderer
- XXX.renderer.entity.ArrowRenderer
+ XXX.renderer.entity.AxolotlRenderer
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
+ XXX.renderer.entity.DolphinRenderer
- XXX.renderer.entity.DragonFireballRenderer
+ XXX.renderer.entity.DrownedRenderer
- XXX.renderer.entity.ElderGuardianRenderer
+ XXX.renderer.entity.EndCrystalRenderer
- XXX.renderer.entity.EnderDragonRenderer
+ XXX.renderer.entity.EnderDragonRenderer$DragonModel
- XXX.renderer.entity.EndermanRenderer
+ XXX.renderer.entity.EndermiteRenderer
- XXX.renderer.entity.EntityRenderDispatcher
+ XXX.renderer.entity.EntityRenderer
- XXX.renderer.entity.EntityRendererProvider
+ XXX.renderer.entity.EntityRendererProvider$Context
- XXX.renderer.entity.EntityRenderers
+ XXX.renderer.entity.EvokerFangsRenderer
- XXX.renderer.entity.EvokerRenderer
+ XXX.renderer.entity.EvokerRenderer$1
- XXX.renderer.entity.ExperienceOrbRenderer
+ XXX.renderer.entity.FallingBlockRenderer
- XXX.renderer.entity.FireworkEntityRenderer
+ XXX.renderer.entity.FishingHookRenderer
- XXX.renderer.entity.FoxRenderer
+ XXX.renderer.entity.FrogRenderer
- XXX.renderer.entity.GhastRenderer
+ XXX.renderer.entity.GiantMobRenderer
- XXX.renderer.entity.GlowSquidRenderer
+ XXX.renderer.entity.GoatRenderer
- XXX.renderer.entity.GuardianRenderer
+ XXX.renderer.entity.HoglinRenderer
- XXX.renderer.entity.HorseRenderer
+ XXX.renderer.entity.HumanoidMobRenderer
- XXX.renderer.entity.HuskRenderer
+ XXX.renderer.entity.IllagerRenderer
- XXX.renderer.entity.IllusionerRenderer
+ XXX.renderer.entity.IllusionerRenderer$1
- XXX.renderer.entity.IronGolemRenderer
+ XXX.renderer.entity.ItemEntityRenderer
- XXX.renderer.entity.ItemFrameRenderer
+ XXX.renderer.entity.ItemRenderer
- XXX.renderer.entity.LeashKnotRenderer
+ XXX.renderer.entity.LightningBoltRenderer
- XXX.renderer.entity.LivingEntityRenderer
+ XXX.renderer.entity.LivingEntityRenderer$1
- XXX.renderer.entity.LlamaRenderer
+ XXX.renderer.entity.LlamaSpitRenderer
- XXX.renderer.entity.MagmaCubeRenderer
+ XXX.renderer.entity.MinecartRenderer
- XXX.renderer.entity.MobRenderer
+ XXX.renderer.entity.MushroomCowRenderer
- XXX.renderer.entity.NoopRenderer
+ XXX.renderer.entity.OcelotRenderer
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
+ XXX.renderer.entity.TadpoleRenderer
- XXX.renderer.entity.ThrownItemRenderer
+ XXX.renderer.entity.ThrownTridentRenderer
- XXX.renderer.entity.TippableArrowRenderer
+ XXX.renderer.entity.TntMinecartRenderer
- XXX.renderer.entity.TntRenderer
+ XXX.renderer.entity.TropicalFishRenderer
- XXX.renderer.entity.TurtleRenderer
+ XXX.renderer.entity.UndeadHorseRenderer
- XXX.renderer.entity.VexRenderer
+ XXX.renderer.entity.VillagerRenderer
- XXX.renderer.entity.VindicatorRenderer
+ XXX.renderer.entity.VindicatorRenderer$1
- XXX.renderer.entity.WanderingTraderRenderer
+ XXX.renderer.entity.WardenRenderer
- XXX.renderer.entity.WitchRenderer
+ XXX.renderer.entity.WitherBossRenderer
- XXX.renderer.entity.WitherSkeletonRenderer
+ XXX.renderer.entity.WitherSkullRenderer
- XXX.renderer.entity.WolfRenderer
+ XXX.renderer.entity.ZoglinRenderer
- XXX.renderer.entity.ZombieRenderer
+ XXX.renderer.entity.ZombieVillagerRenderer
- XXX.structure.pieces.package-info
- XXX.structure.pieces.PieceGenerator
+ XXX.structure.pieces.PieceGenerator$Context
- XXX.structure.pieces.PieceGeneratorSupplier
+ XXX.structure.pieces.PieceGeneratorSupplier$Context
- XXX.structure.pieces.PiecesContainer
+ XXX.structure.pieces.StructurePiecesBuilder
+ XXX.structure.pieces.StructurePieceSerializationContext
- XXX.structure.pieces.StructurePieceType
+ XXX.structure.pieces.StructurePieceType$ContextlessType
- XXX.structure.pieces.StructurePieceType$StructureTemplateType
+ XXX.structure.placement.ConcentricRingsStructurePlacement
- XXX.structure.placement.package-info
- XXX.structure.placement.RandomSpreadStructurePlacement
+ XXX.structure.placement.RandomSpreadType
- XXX.structure.placement.RandomSpreadType$1
+ XXX.structure.placement.StructurePlacement
- XXX.structure.placement.StructurePlacement$ExclusionZone
+ XXX.structure.placement.StructurePlacement$FrequencyReducer
- XXX.structure.placement.StructurePlacement$FrequencyReductionMethod
+ XXX.structure.placement.StructurePlacementType
+ XXX.structure.pools.EmptyPoolElement
- XXX.structure.pools.FeaturePoolElement
+ XXX.structure.pools.JigsawJunction
- XXX.structure.pools.JigsawPlacement
+ XXX.structure.pools.JigsawPlacement$PieceFactory
- XXX.structure.pools.JigsawPlacement$PieceState
+ XXX.structure.pools.JigsawPlacement$Placer
- XXX.structure.pools.LegacySinglePoolElement
+ XXX.structure.pools.ListPoolElement
+ XXX.structure.pools.package-info
- XXX.structure.pools.SinglePoolElement
+ XXX.structure.pools.StructurePoolElement
- XXX.structure.pools.StructurePoolElementType
+ XXX.structure.pools.StructureTemplatePool
- XXX.structure.pools.StructureTemplatePool$Projection
- XXX.structure.structures.BuriedTreasurePieces
+ XXX.structure.structures.BuriedTreasurePieces$BuriedTreasurePiece
- XXX.structure.structures.BuriedTreasureStructure
+ XXX.structure.structures.DesertPyramidPiece
- XXX.structure.structures.DesertPyramidStructure
+ XXX.structure.structures.EndCityPieces
- XXX.structure.structures.EndCityPieces$1
+ XXX.structure.structures.EndCityPieces$2
- XXX.structure.structures.EndCityPieces$3
+ XXX.structure.structures.EndCityPieces$4
- XXX.structure.structures.EndCityPieces$EndCityPiece
+ XXX.structure.structures.EndCityPieces$SectionGenerator
- XXX.structure.structures.EndCityStructure
+ XXX.structure.structures.IglooPieces
- XXX.structure.structures.IglooPieces$IglooPiece
+ XXX.structure.structures.IglooStructure
- XXX.structure.structures.JigsawStructure
+ XXX.util.datafix.package-info
+ XXX.village.poi.package-info
+ XXX.village.poi.PoiManager
- XXX.village.poi.PoiManager$DistanceTracker
+ XXX.village.poi.PoiManager$Occupancy
- XXX.village.poi.PoiRecord
+ XXX.village.poi.PoiSection
- XXX.village.poi.PoiType
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
<hr/>