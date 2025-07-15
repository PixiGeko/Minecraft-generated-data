## Comparison with [23w14a](https://github.com/PixiGeko/Minecraft-generated-data/tree/23w14a)

> [!TIP]
> - [Version data](#version-data)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Commands](#commands)
> - [Translations](#translations)
> - [File structure](#file-structure)
> - [Misc](#misc)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">23w14a</th><th>23w16a</th></tr><tr><td>DataPack version</td><td><pre>13</pre></td><td><pre>14</pre></td></tr><tr><td>World version</td><td><pre>3445</pre></td><td><pre>3449</pre></td></tr><tr><td>Protocol version</td><td><pre>1073741954</pre></td><td><pre>1073741955</pre></td></tr></table>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
+ creative_mode_tab.txt
```

</details>
<details>
<summary>
chunk_status
</summary>

```diff
- minecraft:heightmaps
+ minecraft:initialize_light
- minecraft:liquid_carvers
```

</details>
<details>
<summary>
item
</summary>

```diff
- minecraft:angler_pottery_shard
+ minecraft:angler_pottery_sherd
- minecraft:archer_pottery_shard
+ minecraft:archer_pottery_sherd
- minecraft:arms_up_pottery_shard
+ minecraft:arms_up_pottery_sherd
- minecraft:blade_pottery_shard
+ minecraft:blade_pottery_sherd
- minecraft:brewer_pottery_shard
+ minecraft:brewer_pottery_sherd
- minecraft:burn_pottery_shard
+ minecraft:burn_pottery_sherd
- minecraft:danger_pottery_shard
+ minecraft:danger_pottery_sherd
- minecraft:explorer_pottery_shard
+ minecraft:explorer_pottery_sherd
- minecraft:friend_pottery_shard
+ minecraft:friend_pottery_sherd
- minecraft:heart_pottery_shard
+ minecraft:heart_pottery_sherd
- minecraft:heartbreak_pottery_shard
+ minecraft:heartbreak_pottery_sherd
- minecraft:howl_pottery_shard
+ minecraft:howl_pottery_sherd
- minecraft:miner_pottery_shard
+ minecraft:miner_pottery_sherd
- minecraft:mourner_pottery_shard
+ minecraft:mourner_pottery_sherd
- minecraft:plenty_pottery_shard
+ minecraft:plenty_pottery_sherd
- minecraft:prize_pottery_shard
+ minecraft:prize_pottery_sherd
- minecraft:sheaf_pottery_shard
+ minecraft:sheaf_pottery_sherd
- minecraft:shelter_pottery_shard
+ minecraft:shelter_pottery_sherd
- minecraft:skull_pottery_shard
+ minecraft:skull_pottery_sherd
- minecraft:snort_pottery_shard
+ minecraft:snort_pottery_sherd
```

</details>
<details>
<summary>
sound_event
</summary>

```diff
+ minecraft:block.sniffer_egg.crack
+ minecraft:block.sniffer_egg.hatch
+ minecraft:block.sniffer_egg.plop
- minecraft:block.sniffer.egg_crack
- minecraft:block.sniffer.egg_hatch
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
+ universal_tags/creative_mode_tab.json
```

</details>
<details>
<summary>
universal_tags/chunk_status.json
</summary>

```diff
- minecraft:heightmaps
+ minecraft:initialize_light
- minecraft:liquid_carvers
```

</details>
<details>
<summary>
universal_tags/item.json
</summary>

```diff
- minecraft:angler_pottery_shard
+ minecraft:angler_pottery_sherd
- minecraft:archer_pottery_shard
+ minecraft:archer_pottery_sherd
- minecraft:arms_up_pottery_shard
+ minecraft:arms_up_pottery_sherd
- minecraft:blade_pottery_shard
+ minecraft:blade_pottery_sherd
- minecraft:brewer_pottery_shard
+ minecraft:brewer_pottery_sherd
- minecraft:burn_pottery_shard
+ minecraft:burn_pottery_sherd
- minecraft:danger_pottery_shard
+ minecraft:danger_pottery_sherd
- minecraft:explorer_pottery_shard
+ minecraft:explorer_pottery_sherd
- minecraft:friend_pottery_shard
+ minecraft:friend_pottery_sherd
- minecraft:heart_pottery_shard
+ minecraft:heart_pottery_sherd
- minecraft:heartbreak_pottery_shard
+ minecraft:heartbreak_pottery_sherd
- minecraft:howl_pottery_shard
+ minecraft:howl_pottery_sherd
- minecraft:miner_pottery_shard
+ minecraft:miner_pottery_sherd
- minecraft:mourner_pottery_shard
+ minecraft:mourner_pottery_sherd
- minecraft:plenty_pottery_shard
+ minecraft:plenty_pottery_sherd
- minecraft:prize_pottery_shard
+ minecraft:prize_pottery_sherd
- minecraft:sheaf_pottery_shard
+ minecraft:sheaf_pottery_sherd
- minecraft:shelter_pottery_shard
+ minecraft:shelter_pottery_sherd
- minecraft:skull_pottery_shard
+ minecraft:skull_pottery_sherd
- minecraft:snort_pottery_shard
+ minecraft:snort_pottery_sherd
```

</details>
<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:block.sniffer_egg.crack
+ minecraft:block.sniffer_egg.hatch
+ minecraft:block.sniffer_egg.plop
- minecraft:block.sniffer.egg_crack
- minecraft:block.sniffer.egg_hatch
```

</details>
</details>
<hr/>
<details><summary><b><ins>COMMANDS</ins></b><a name="commands"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
+ return.txt
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
+ commands.function.success.multiple.result: Executed %s functions
+ commands.function.success.single.result: Function '%2$s' returned %1$s
- item.minecraft.angler_pottery_shard: Angler Pottery Shard
+ item.minecraft.angler_pottery_sherd: Angler Pottery Sherd
- item.minecraft.archer_pottery_shard: Archer Pottery Shard
+ item.minecraft.archer_pottery_sherd: Archer Pottery Sherd
- item.minecraft.arms_up_pottery_shard: Arms Up Pottery Shard
+ item.minecraft.arms_up_pottery_sherd: Arms Up Pottery Sherd
- item.minecraft.blade_pottery_shard: Blade Pottery Shard
+ item.minecraft.blade_pottery_sherd: Blade Pottery Sherd
- item.minecraft.brewer_pottery_shard: Brewer Pottery Shard
+ item.minecraft.brewer_pottery_sherd: Brewer Pottery Sherd
- item.minecraft.burn_pottery_shard: Burn Pottery Shard
+ item.minecraft.burn_pottery_sherd: Burn Pottery Sherd
- item.minecraft.danger_pottery_shard: Danger Pottery Shard
+ item.minecraft.danger_pottery_sherd: Danger Pottery Sherd
- item.minecraft.explorer_pottery_shard: Explorer Pottery Shard
+ item.minecraft.explorer_pottery_sherd: Explorer Pottery Sherd
- item.minecraft.friend_pottery_shard: Friend Pottery Shard
+ item.minecraft.friend_pottery_sherd: Friend Pottery Sherd
- item.minecraft.heart_pottery_shard: Heart Pottery Shard
+ item.minecraft.heart_pottery_sherd: Heart Pottery Sherd
- item.minecraft.heartbreak_pottery_shard: Heartbreak Pottery Shard
+ item.minecraft.heartbreak_pottery_sherd: Heartbreak Pottery Sherd
- item.minecraft.howl_pottery_shard: Howl Pottery Shard
+ item.minecraft.howl_pottery_sherd: Howl Pottery Sherd
- item.minecraft.miner_pottery_shard: Miner Pottery Shard
+ item.minecraft.miner_pottery_sherd: Miner Pottery Sherd
- item.minecraft.mourner_pottery_shard: Mourner Pottery Shard
+ item.minecraft.mourner_pottery_sherd: Mourner Pottery Sherd
- item.minecraft.plenty_pottery_shard: Plenty Pottery Shard
+ item.minecraft.plenty_pottery_sherd: Plenty Pottery Sherd
- item.minecraft.prize_pottery_shard: Prize Pottery Shard
+ item.minecraft.prize_pottery_sherd: Prize Pottery Sherd
- item.minecraft.sheaf_pottery_shard: Sheaf Pottery Shard
+ item.minecraft.sheaf_pottery_sherd: Sheaf Pottery Sherd
- item.minecraft.shelter_pottery_shard: Shelter Pottery Shard
+ item.minecraft.shelter_pottery_sherd: Shelter Pottery Sherd
- item.minecraft.skull_pottery_shard: Skull Pottery Shard
+ item.minecraft.skull_pottery_sherd: Skull Pottery Sherd
- item.minecraft.snort_pottery_shard: Snort Pottery Shard
+ item.minecraft.snort_pottery_sherd: Snort Pottery Sherd
+ subtitles.block.sniffer_egg.crack: Sniffer Egg cracks
+ subtitles.block.sniffer_egg.hatch: Sniffer Egg hatches
+ subtitles.block.sniffer_egg.plop: Sniffer plops
- subtitles.block.sniffer.egg_crack: Sniffer Egg cracks
- subtitles.block.sniffer.egg_hatch: Sniffer Egg hatches
```

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
+ minecraft/loot_tables/archaeology/trail_ruins_common.json
+ minecraft/loot_tables/archaeology/trail_ruins_rare.json
- minecraft/loot_tables/archaeology/trail_ruins.json
- minecraft/structures/trail_ruins/buildings/group_entrance_three_1.nbt
- minecraft/structures/trail_ruins/buildings/group_entrance_two_1.nbt
- minecraft/structures/trail_ruins/buildings/group_entrance_two_2.nbt
+ minecraft/structures/trail_ruins/buildings/group_full_1.nbt
+ minecraft/structures/trail_ruins/buildings/group_full_2.nbt
+ minecraft/structures/trail_ruins/buildings/group_full_3.nbt
+ minecraft/structures/trail_ruins/buildings/group_full_4.nbt
+ minecraft/structures/trail_ruins/buildings/group_full_5.nbt
+ minecraft/structures/trail_ruins/buildings/group_hall_1.nbt
+ minecraft/structures/trail_ruins/buildings/group_hall_2.nbt
+ minecraft/structures/trail_ruins/buildings/group_hall_3.nbt
+ minecraft/structures/trail_ruins/buildings/group_hall_4.nbt
+ minecraft/structures/trail_ruins/buildings/group_hall_5.nbt
+ minecraft/structures/trail_ruins/buildings/group_lower_1.nbt
+ minecraft/structures/trail_ruins/buildings/group_lower_2.nbt
+ minecraft/structures/trail_ruins/buildings/group_lower_3.nbt
+ minecraft/structures/trail_ruins/buildings/group_lower_4.nbt
+ minecraft/structures/trail_ruins/buildings/group_lower_5.nbt
+ minecraft/structures/trail_ruins/buildings/group_room_1.nbt
+ minecraft/structures/trail_ruins/buildings/group_room_2.nbt
+ minecraft/structures/trail_ruins/buildings/group_room_3.nbt
+ minecraft/structures/trail_ruins/buildings/group_room_4.nbt
+ minecraft/structures/trail_ruins/buildings/group_room_5.nbt
- minecraft/structures/trail_ruins/buildings/group_room_one_1.nbt
- minecraft/structures/trail_ruins/buildings/group_room_one_2.nbt
- minecraft/structures/trail_ruins/buildings/group_room_two_1.nbt
- minecraft/structures/trail_ruins/buildings/group_room_two_2.nbt
- minecraft/structures/trail_ruins/buildings/group_room_two_3.nbt
- minecraft/structures/trail_ruins/buildings/group_room_two_4.nbt
- minecraft/structures/trail_ruins/buildings/group_room_two_5.nbt
+ minecraft/structures/trail_ruins/buildings/group_upper_1.nbt
+ minecraft/structures/trail_ruins/buildings/group_upper_2.nbt
+ minecraft/structures/trail_ruins/buildings/group_upper_3.nbt
+ minecraft/structures/trail_ruins/buildings/group_upper_4.nbt
+ minecraft/structures/trail_ruins/buildings/group_upper_5.nbt
+ minecraft/structures/trail_ruins/buildings/large_room_4.nbt
+ minecraft/structures/trail_ruins/buildings/large_room_5.nbt
+ minecraft/structures/trail_ruins/buildings/one_room_5.nbt
+ minecraft/structures/trail_ruins/decor/decor_7.nbt
- minecraft/structures/trail_ruins/roads/road_end_1s.nbt
+ minecraft/structures/trail_ruins/tower/hall_3.nbt
+ minecraft/structures/trail_ruins/tower/hall_4.nbt
+ minecraft/structures/trail_ruins/tower/hall_5.nbt
+ minecraft/structures/trail_ruins/tower/large_hall_3.nbt
+ minecraft/structures/trail_ruins/tower/large_hall_4.nbt
+ minecraft/structures/trail_ruins/tower/large_hall_5.nbt
+ minecraft/structures/trail_ruins/tower/one_room_2.nbt
+ minecraft/structures/trail_ruins/tower/one_room_3.nbt
+ minecraft/structures/trail_ruins/tower/one_room_4.nbt
+ minecraft/structures/trail_ruins/tower/one_room_5.nbt
+ minecraft/structures/trail_ruins/tower/platform_2.nbt
+ minecraft/structures/trail_ruins/tower/platform_3.nbt
+ minecraft/structures/trail_ruins/tower/platform_4.nbt
+ minecraft/structures/trail_ruins/tower/platform_5.nbt
+ minecraft/structures/trail_ruins/tower/stable_2.nbt
+ minecraft/structures/trail_ruins/tower/stable_3.nbt
+ minecraft/structures/trail_ruins/tower/stable_4.nbt
+ minecraft/structures/trail_ruins/tower/stable_5.nbt
+ minecraft/structures/trail_ruins/tower/tower_4.nbt
+ minecraft/structures/trail_ruins/tower/tower_5.nbt
+ minecraft/structures/trail_ruins/tower/tower_top_1.nbt
+ minecraft/structures/trail_ruins/tower/tower_top_2.nbt
+ minecraft/structures/trail_ruins/tower/tower_top_3.nbt
+ minecraft/structures/trail_ruins/tower/tower_top_4.nbt
+ minecraft/structures/trail_ruins/tower/tower_top_5.nbt
+ minecraft/tags/blocks/maintains_farmland.json
+ minecraft/tags/blocks/stone_buttons.json
- minecraft/tags/items/decorated_pot_shards.json
+ minecraft/tags/items/decorated_pot_sherds.json
+ minecraft/tags/items/stone_buttons.json
+ minecraft/tags/items/villager_plantable_seeds.json
+ minecraft/worldgen/processor_list/trail_ruins_houses_archaeology.json
+ minecraft/worldgen/processor_list/trail_ruins_roads_archaeology.json
- minecraft/worldgen/processor_list/trail_ruins_suspicious_sand.json
+ minecraft/worldgen/processor_list/trail_ruins_tower_top_archaeology.json
+ minecraft/worldgen/template_pool/trail_ruins/tower/tower_top.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
- minecraft/models/item/angler_pottery_shard.json
+ minecraft/models/item/angler_pottery_sherd.json
- minecraft/models/item/archer_pottery_shard.json
+ minecraft/models/item/archer_pottery_sherd.json
- minecraft/models/item/arms_up_pottery_shard.json
+ minecraft/models/item/arms_up_pottery_sherd.json
- minecraft/models/item/blade_pottery_shard.json
+ minecraft/models/item/blade_pottery_sherd.json
- minecraft/models/item/brewer_pottery_shard.json
+ minecraft/models/item/brewer_pottery_sherd.json
- minecraft/models/item/burn_pottery_shard.json
+ minecraft/models/item/burn_pottery_sherd.json
- minecraft/models/item/danger_pottery_shard.json
+ minecraft/models/item/danger_pottery_sherd.json
- minecraft/models/item/explorer_pottery_shard.json
+ minecraft/models/item/explorer_pottery_sherd.json
- minecraft/models/item/friend_pottery_shard.json
+ minecraft/models/item/friend_pottery_sherd.json
- minecraft/models/item/heart_pottery_shard.json
+ minecraft/models/item/heart_pottery_sherd.json
- minecraft/models/item/heartbreak_pottery_shard.json
+ minecraft/models/item/heartbreak_pottery_sherd.json
- minecraft/models/item/howl_pottery_shard.json
+ minecraft/models/item/howl_pottery_sherd.json
- minecraft/models/item/miner_pottery_shard.json
+ minecraft/models/item/miner_pottery_sherd.json
- minecraft/models/item/mourner_pottery_shard.json
+ minecraft/models/item/mourner_pottery_sherd.json
- minecraft/models/item/plenty_pottery_shard.json
+ minecraft/models/item/plenty_pottery_sherd.json
- minecraft/models/item/prize_pottery_shard.json
+ minecraft/models/item/prize_pottery_sherd.json
- minecraft/models/item/sheaf_pottery_shard.json
+ minecraft/models/item/sheaf_pottery_sherd.json
- minecraft/models/item/shelter_pottery_shard.json
+ minecraft/models/item/shelter_pottery_sherd.json
- minecraft/models/item/skull_pottery_shard.json
+ minecraft/models/item/skull_pottery_sherd.json
- minecraft/models/item/snort_pottery_shard.json
+ minecraft/models/item/snort_pottery_sherd.json
- minecraft/textures/item/angler_pottery_shard.png
+ minecraft/textures/item/angler_pottery_sherd.png
- minecraft/textures/item/archer_pottery_shard.png
+ minecraft/textures/item/archer_pottery_sherd.png
- minecraft/textures/item/arms_up_pottery_shard.png
+ minecraft/textures/item/arms_up_pottery_sherd.png
- minecraft/textures/item/blade_pottery_shard.png
+ minecraft/textures/item/blade_pottery_sherd.png
- minecraft/textures/item/brewer_pottery_shard.png
+ minecraft/textures/item/brewer_pottery_sherd.png
- minecraft/textures/item/burn_pottery_shard.png
+ minecraft/textures/item/burn_pottery_sherd.png
- minecraft/textures/item/danger_pottery_shard.png
+ minecraft/textures/item/danger_pottery_sherd.png
- minecraft/textures/item/explorer_pottery_shard.png
+ minecraft/textures/item/explorer_pottery_sherd.png
- minecraft/textures/item/friend_pottery_shard.png
+ minecraft/textures/item/friend_pottery_sherd.png
- minecraft/textures/item/heart_pottery_shard.png
+ minecraft/textures/item/heart_pottery_sherd.png
- minecraft/textures/item/heartbreak_pottery_shard.png
+ minecraft/textures/item/heartbreak_pottery_sherd.png
- minecraft/textures/item/howl_pottery_shard.png
+ minecraft/textures/item/howl_pottery_sherd.png
- minecraft/textures/item/miner_pottery_shard.png
+ minecraft/textures/item/miner_pottery_sherd.png
- minecraft/textures/item/mourner_pottery_shard.png
+ minecraft/textures/item/mourner_pottery_sherd.png
- minecraft/textures/item/plenty_pottery_shard.png
+ minecraft/textures/item/plenty_pottery_sherd.png
- minecraft/textures/item/prize_pottery_shard.png
+ minecraft/textures/item/prize_pottery_sherd.png
- minecraft/textures/item/sheaf_pottery_shard.png
+ minecraft/textures/item/sheaf_pottery_sherd.png
- minecraft/textures/item/shelter_pottery_shard.png
+ minecraft/textures/item/shelter_pottery_sherd.png
- minecraft/textures/item/skull_pottery_shard.png
+ minecraft/textures/item/skull_pottery_sherd.png
- minecraft/textures/item/snort_pottery_shard.png
+ minecraft/textures/item/snort_pottery_sherd.png
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
+ Has working bookshelves!
+ Place hanging sign here
+ Remember to brush your... ...teeth
+ Sniff sniff...
+ This sand is sus
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
- XXX.advancements.critereon.RecipeCraftedTrigger$TriggerInstance
+ XXX.animal.allay.Allay$AllayVibrationListenerConfig
- XXX.animal.allay.Allay$JukeboxListener
+ XXX.block.entity.CalibratedSculkSensorBlockEntity$VibrationConfig
- XXX.block.entity.CalibratedSculkSensorBlockEntity$VibrationUser
- XXX.block.entity.SculkSensorBlockEntity
+ XXX.block.entity.SculkSensorBlockEntity$VibrationConfig
- XXX.block.entity.SculkShriekerBlockEntity
- XXX.datafix.fixes.DecoratedPotFieldRenameFix
+ XXX.datafix.fixes.DyeItemRenameFix
- XXX.datafix.fixes.EffectDurationFix
+ XXX.datafix.fixes.EntityArmorStandSilentFix
- XXX.datafix.fixes.EntityBlockStateFix
+ XXX.datafix.fixes.EntityBrushableBlockFieldsRenameFix
- XXX.datafix.fixes.EntityCatSplitFix
+ XXX.datafix.fixes.EntityCodSalmonFix
- XXX.datafix.fixes.EntityCustomNameToComponentFix
+ XXX.datafix.fixes.EntityElderGuardianSplitFix
- XXX.datafix.fixes.EntityEquipmentToArmorAndHandFix
+ XXX.datafix.fixes.EntityGoatMissingStateFix
- XXX.datafix.fixes.EntityHealthFix
+ XXX.datafix.fixes.EntityHorseSaddleFix
- XXX.datafix.fixes.EntityHorseSplitFix
+ XXX.datafix.fixes.EntityIdFix
- XXX.datafix.fixes.EntityItemFrameDirectionFix
+ XXX.datafix.fixes.EntityMinecartIdentifiersFix
- XXX.datafix.fixes.EntityPaintingFieldsRenameFix
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
- XXX.datafix.fixes.EntityVariantFix
+ XXX.datafix.fixes.EntityWolfColorFix
- XXX.datafix.fixes.EntityZombieSplitFix
+ XXX.datafix.fixes.EntityZombieVillagerTypeFix
- XXX.datafix.fixes.EntityZombifiedPiglinRenameFix
+ XXX.datafix.fixes.FeatureFlagRemoveFix
- XXX.datafix.fixes.FilteredBooksFix
+ XXX.datafix.fixes.FilteredSignsFix
- XXX.datafix.fixes.ForcePoiRebuild
+ XXX.datafix.fixes.FurnaceRecipeFix
- XXX.datafix.fixes.GoatHornIdFix
+ XXX.datafix.fixes.GossipUUIDFix
- XXX.datafix.fixes.HeightmapRenamingFix
+ XXX.datafix.fixes.IglooMetadataRemovalFix
- XXX.datafix.fixes.ItemBannerColorFix
+ XXX.datafix.fixes.ItemCustomNameToComponentFix
- XXX.datafix.fixes.ItemIdFix
+ XXX.datafix.fixes.ItemLoreFix
- XXX.datafix.fixes.ItemPotionFix
+ XXX.datafix.fixes.ItemRemoveBlockEntityTagFix
- XXX.datafix.fixes.ItemRenameFix
+ XXX.datafix.fixes.ItemRenameFix$1
- XXX.datafix.fixes.ItemShulkerBoxColorFix
+ XXX.datafix.fixes.ItemSpawnEggFix
- XXX.datafix.fixes.ItemStackEnchantmentNamesFix
+ XXX.datafix.fixes.ItemStackMapIdFix
- XXX.datafix.fixes.ItemStackSpawnEggFix
+ XXX.datafix.fixes.ItemStackTagFix
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
+ XXX.datafix.fixes.NamespacedTypeRenameFix
- XXX.datafix.fixes.NewVillageFix
+ XXX.datafix.fixes.ObjectiveDisplayNameFix
- XXX.datafix.fixes.ObjectiveRenderTypeFix
+ XXX.datafix.fixes.OminousBannerBlockEntityRenameFix
- XXX.datafix.fixes.OminousBannerRenameFix
+ XXX.datafix.fixes.OptionsAccessibilityOnboardFix
- XXX.datafix.fixes.OptionsAddTextBackgroundFix
+ XXX.datafix.fixes.OptionsAmbientOcclusionFix
- XXX.datafix.fixes.OptionsForceVBOFix
+ XXX.datafix.fixes.OptionsKeyLwjgl3Fix
- XXX.datafix.fixes.OptionsKeyTranslationFix
+ XXX.datafix.fixes.OptionsLowerCaseLanguageFix
- XXX.datafix.fixes.OptionsProgrammerArtFix
+ XXX.datafix.fixes.OptionsRenameFieldFix
- XXX.datafix.fixes.OverreachingTickFix
+ XXX.datafix.fixes.package-info
+ XXX.datafix.fixes.PlayerUUIDFix
- XXX.datafix.fixes.PoiTypeRemoveFix
+ XXX.datafix.fixes.PoiTypeRenameFix
- XXX.datafix.fixes.RecipesFix
+ XXX.datafix.fixes.RecipesRenameningFix
- XXX.datafix.fixes.RedstoneWireConnectionsFix
+ XXX.datafix.fixes.References
- XXX.datafix.fixes.RemapChunkStatusFix
+ XXX.datafix.fixes.SimpleEntityRenameFix
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
- XXX.datafix.fixes.VariantRenameFix
+ XXX.datafix.fixes.VillagerDataFix
- XXX.datafix.fixes.VillagerFollowRangeFix
+ XXX.datafix.fixes.VillagerRebuildLevelAndXpFix
- XXX.datafix.fixes.VillagerTradeFix
+ XXX.datafix.fixes.WallPropertyFix
- XXX.datafix.fixes.WeaponSmithChestLootTableFix
+ XXX.datafix.fixes.WorldGenSettingsDisallowOldCustomWorldsFix
- XXX.datafix.fixes.WorldGenSettingsFix
+ XXX.datafix.fixes.WorldGenSettingsFix$StructureFeatureConfiguration
- XXX.datafix.fixes.WorldGenSettingsHeightAndBiomeFix
+ XXX.datafix.fixes.WriteAndReadFix
- XXX.datafix.fixes.ZombieVillagerRebuildXpFix
+ XXX.datafix.schemas.NamespacedSchema
- XXX.datafix.schemas.NamespacedSchema$1
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
- XXX.datafix.schemas.V1451_6$1
+ XXX.datafix.schemas.V1451_6$2
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
+ XXX.datafix.schemas.V3202
- XXX.datafix.schemas.V3203
+ XXX.datafix.schemas.V3204
- XXX.datafix.schemas.V3325
+ XXX.datafix.schemas.V3326
- XXX.datafix.schemas.V3327
+ XXX.datafix.schemas.V3328
- XXX.datafix.schemas.V3438
+ XXX.entity.npc.AbstractVillager
- XXX.entity.npc.CatSpawner
+ XXX.entity.npc.ClientSideMerchant
- XXX.entity.npc.InventoryCarrier
+ XXX.entity.npc.Npc
- XXX.entity.npc.package-info
- XXX.entity.npc.Villager
+ XXX.entity.npc.VillagerData
- XXX.entity.npc.VillagerDataHolder
+ XXX.entity.npc.VillagerProfession
- XXX.entity.npc.VillagerTrades
+ XXX.entity.npc.VillagerTrades$DyedArmorForEmeralds
- XXX.entity.npc.VillagerTrades$EmeraldForItems
+ XXX.entity.npc.VillagerTrades$EmeraldsForVillagerTypeItem
- XXX.entity.npc.VillagerTrades$EnchantBookForEmeralds
+ XXX.entity.npc.VillagerTrades$EnchantedItemForEmeralds
- XXX.entity.npc.VillagerTrades$ItemListing
+ XXX.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
- XXX.entity.npc.VillagerTrades$ItemsForEmeralds
+ XXX.entity.npc.VillagerTrades$SuspiciousStewForEmerald
- XXX.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
+ XXX.entity.npc.VillagerTrades$TreasureMapForEmeralds
- XXX.entity.npc.VillagerType
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
+ XXX.entity.player.ProfileKeyPair
- XXX.entity.player.ProfilePublicKey
+ XXX.entity.player.ProfilePublicKey$Data
- XXX.entity.player.ProfilePublicKey$ValidationException
+ XXX.entity.player.StackedContents
- XXX.entity.player.StackedContents$RecipePicker
- XXX.entity.projectile.AbstractArrow
+ XXX.entity.projectile.AbstractArrow$1
- XXX.entity.projectile.AbstractArrow$Pickup
+ XXX.entity.projectile.AbstractHurtingProjectile
- XXX.entity.projectile.Arrow
+ XXX.entity.projectile.DragonFireball
- XXX.entity.projectile.EvokerFangs
+ XXX.entity.projectile.EyeOfEnder
- XXX.entity.projectile.Fireball
+ XXX.entity.projectile.FireworkRocketEntity
- XXX.entity.projectile.FishingHook
+ XXX.entity.projectile.FishingHook$1
- XXX.entity.projectile.FishingHook$FishHookState
+ XXX.entity.projectile.FishingHook$OpenWaterType
- XXX.entity.projectile.ItemSupplier
+ XXX.entity.projectile.LargeFireball
- XXX.entity.projectile.LlamaSpit
+ XXX.entity.projectile.package-info
+ XXX.entity.projectile.Projectile
- XXX.entity.projectile.ProjectileUtil
+ XXX.entity.projectile.ShulkerBullet
- XXX.entity.projectile.SmallFireball
+ XXX.entity.projectile.Snowball
- XXX.entity.projectile.SpectralArrow
+ XXX.entity.projectile.ThrowableItemProjectile
- XXX.entity.projectile.ThrowableProjectile
+ XXX.entity.projectile.ThrownEgg
- XXX.entity.projectile.ThrownEnderpearl
+ XXX.entity.projectile.ThrownExperienceBottle
- XXX.entity.projectile.ThrownPotion
+ XXX.entity.projectile.ThrownTrident
- XXX.entity.projectile.WitherSkull
- XXX.entity.raid.package-info
- XXX.entity.raid.Raid
+ XXX.entity.raid.Raid$1
+ XXX.entity.raid.Raid$RaiderType
- XXX.entity.raid.Raid$RaidStatus
- XXX.entity.raid.Raider
+ XXX.entity.raid.Raider$HoldGroundAttackGoal
- XXX.entity.raid.Raider$ObtainRaidLeaderBannerGoal
+ XXX.entity.raid.Raider$RaiderCelebration
- XXX.entity.raid.Raider$RaiderMoveThroughVillageGoal
+ XXX.entity.raid.Raids
+ XXX.entity.schedule.Activity
- XXX.entity.schedule.Keyframe
+ XXX.entity.schedule.package-info
+ XXX.entity.schedule.Schedule
- XXX.entity.schedule.ScheduleBuilder
+ XXX.entity.schedule.ScheduleBuilder$ActivityTransition
- XXX.entity.schedule.Timeline
- XXX.entity.vehicle.AbstractMinecart
+ XXX.entity.vehicle.AbstractMinecart$1
- XXX.entity.vehicle.AbstractMinecart$Type
+ XXX.entity.vehicle.AbstractMinecartContainer
- XXX.entity.vehicle.Boat
+ XXX.entity.vehicle.Boat$1
- XXX.entity.vehicle.Boat$Status
+ XXX.entity.vehicle.Boat$Type
- XXX.entity.vehicle.ChestBoat
+ XXX.entity.vehicle.ChestBoat$1
- XXX.entity.vehicle.ContainerEntity
+ XXX.entity.vehicle.ContainerEntity$1
- XXX.entity.vehicle.DismountHelper
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
- XXX.feature.foliageplacers.CherryFoliagePlacer
+ XXX.feature.foliageplacers.DarkOakFoliagePlacer
- XXX.feature.foliageplacers.FancyFoliagePlacer
+ XXX.feature.foliageplacers.FoliagePlacer
- XXX.feature.foliageplacers.FoliagePlacer$FoliageAttachment
+ XXX.feature.foliageplacers.FoliagePlacer$FoliageSetter
- XXX.feature.foliageplacers.FoliagePlacerType
+ XXX.feature.foliageplacers.MegaJungleFoliagePlacer
- XXX.feature.foliageplacers.MegaPineFoliagePlacer
- XXX.feature.foliageplacers.package-info
+ XXX.feature.foliageplacers.PineFoliagePlacer
- XXX.feature.foliageplacers.RandomSpreadFoliagePlacer
+ XXX.feature.foliageplacers.SpruceFoliagePlacer
- XXX.feature.rootplacers.AboveRootPlacement
+ XXX.feature.rootplacers.MangroveRootPlacement
- XXX.feature.rootplacers.MangroveRootPlacer
+ XXX.feature.rootplacers.package-info
+ XXX.feature.rootplacers.RootPlacer
- XXX.feature.rootplacers.RootPlacerType
- XXX.feature.stateproviders.BlockStateProvider
+ XXX.feature.stateproviders.BlockStateProviderType
- XXX.feature.stateproviders.DualNoiseProvider
+ XXX.feature.stateproviders.NoiseBasedStateProvider
- XXX.feature.stateproviders.NoiseProvider
+ XXX.feature.stateproviders.NoiseThresholdProvider
- XXX.feature.stateproviders.package-info
- XXX.feature.stateproviders.RandomizedIntStateProvider
+ XXX.feature.stateproviders.RotatedBlockProvider
- XXX.feature.stateproviders.RuleBasedBlockStateProvider
+ XXX.feature.stateproviders.RuleBasedBlockStateProvider$Rule
- XXX.feature.stateproviders.SimpleStateProvider
+ XXX.feature.stateproviders.WeightedStateProvider
+ XXX.feature.treedecorators.AlterGroundDecorator
- XXX.feature.treedecorators.AttachedToLeavesDecorator
+ XXX.feature.treedecorators.BeehiveDecorator
- XXX.feature.treedecorators.CocoaDecorator
+ XXX.feature.treedecorators.LeaveVineDecorator
- XXX.feature.treedecorators.package-info
- XXX.feature.treedecorators.TreeDecorator
+ XXX.feature.treedecorators.TreeDecorator$Context
- XXX.feature.treedecorators.TreeDecoratorType
+ XXX.feature.treedecorators.TrunkVineDecorator
+ XXX.feature.trunkplacers.BendingTrunkPlacer
- XXX.feature.trunkplacers.CherryTrunkPlacer
+ XXX.feature.trunkplacers.DarkOakTrunkPlacer
- XXX.feature.trunkplacers.FancyTrunkPlacer
+ XXX.feature.trunkplacers.FancyTrunkPlacer$FoliageCoords
- XXX.feature.trunkplacers.ForkingTrunkPlacer
+ XXX.feature.trunkplacers.GiantTrunkPlacer
- XXX.feature.trunkplacers.MegaJungleTrunkPlacer
+ XXX.feature.trunkplacers.package-info
+ XXX.feature.trunkplacers.StraightTrunkPlacer
- XXX.feature.trunkplacers.TrunkPlacer
+ XXX.feature.trunkplacers.TrunkPlacerType
- XXX.feature.trunkplacers.UpwardsBranchingTrunkPlacer
- XXX.gameevent.vibrations.package-info
+ XXX.gameevent.vibrations.VibrationListener
- XXX.gameevent.vibrations.VibrationSystem$Data
- XXX.gameevent.vibrations.VibrationSystem$Ticker
- XXX.inventory.tooltip.BundleTooltip
- XXX.inventory.tooltip.package-info
+ XXX.inventory.tooltip.TooltipComponent
- XXX.item.alchemy.package-info
+ XXX.item.alchemy.Potion
- XXX.item.alchemy.PotionBrewing
+ XXX.item.alchemy.PotionBrewing$Mix
+ XXX.item.alchemy.Potions
- XXX.item.alchemy.PotionUtils
+ XXX.item.armortrim.ArmorTrim
- XXX.item.armortrim.package-info
- XXX.item.armortrim.TrimMaterial
+ XXX.item.armortrim.TrimMaterials
- XXX.item.armortrim.TrimPattern
+ XXX.item.armortrim.TrimPatterns
+ XXX.item.context.BlockPlaceContext
- XXX.item.context.DirectionalPlaceContext
+ XXX.item.context.DirectionalPlaceContext$1
+ XXX.item.context.package-info
- XXX.item.context.UseOnContext
- XXX.item.crafting.AbstractCookingRecipe
+ XXX.item.crafting.ArmorDyeRecipe
- XXX.item.crafting.BannerDuplicateRecipe
+ XXX.item.crafting.BlastingRecipe
- XXX.item.crafting.BookCloningRecipe
+ XXX.item.crafting.CampfireCookingRecipe
- XXX.item.crafting.CookingBookCategory
+ XXX.item.crafting.CraftingBookCategory
- XXX.item.crafting.CraftingRecipe
+ XXX.item.crafting.CustomRecipe
- XXX.item.crafting.DecoratedPotRecipe
+ XXX.item.crafting.FireworkRocketRecipe
- XXX.item.crafting.FireworkStarFadeRecipe
+ XXX.item.crafting.FireworkStarRecipe
- XXX.item.crafting.Ingredient
+ XXX.item.crafting.Ingredient$ItemValue
- XXX.item.crafting.Ingredient$TagValue
+ XXX.item.crafting.Ingredient$Value
- XXX.item.crafting.MapCloningRecipe
+ XXX.item.crafting.MapExtendingRecipe
+ XXX.item.crafting.package-info
- XXX.item.crafting.Recipe
+ XXX.item.crafting.RecipeManager
- XXX.item.crafting.RecipeManager$1
+ XXX.item.crafting.RecipeManager$CachedCheck
- XXX.item.crafting.RecipeSerializer
+ XXX.item.crafting.RecipeType
- XXX.item.crafting.RecipeType$1
+ XXX.item.crafting.RepairItemRecipe
- XXX.item.crafting.ShapedRecipe
+ XXX.item.crafting.ShapedRecipe$Serializer
- XXX.item.crafting.ShapelessRecipe
+ XXX.item.crafting.ShapelessRecipe$Serializer
- XXX.item.crafting.ShieldDecorationRecipe
+ XXX.item.crafting.ShulkerBoxColoring
- XXX.item.crafting.SimpleCookingSerializer
+ XXX.item.crafting.SimpleCookingSerializer$CookieBaker
- XXX.item.crafting.SimpleCraftingRecipeSerializer
+ XXX.item.crafting.SimpleCraftingRecipeSerializer$Factory
- XXX.item.crafting.SingleItemRecipe
+ XXX.item.crafting.SingleItemRecipe$Serializer
- XXX.item.crafting.SingleItemRecipe$Serializer$SingleItemMaker
+ XXX.item.crafting.SmeltingRecipe
- XXX.item.crafting.SmithingRecipe
+ XXX.item.crafting.SmithingTransformRecipe
- XXX.item.crafting.SmithingTransformRecipe$Serializer
+ XXX.item.crafting.SmithingTrimRecipe
- XXX.item.crafting.SmithingTrimRecipe$Serializer
+ XXX.item.crafting.SmokingRecipe
- XXX.item.crafting.StonecutterRecipe
+ XXX.item.crafting.SuspiciousStewRecipe
- XXX.item.crafting.TippedArrowRecipe
- XXX.item.enchantment.ArrowDamageEnchantment
+ XXX.item.enchantment.ArrowFireEnchantment
- XXX.item.enchantment.ArrowInfiniteEnchantment
+ XXX.item.enchantment.ArrowKnockbackEnchantment
- XXX.item.enchantment.ArrowPiercingEnchantment
+ XXX.item.enchantment.BindingCurseEnchantment
- XXX.item.enchantment.DamageEnchantment
+ XXX.item.enchantment.DigDurabilityEnchantment
- XXX.item.enchantment.DiggingEnchantment
+ XXX.item.enchantment.Enchantment
- XXX.item.enchantment.Enchantment$Rarity
+ XXX.item.enchantment.EnchantmentCategory
- XXX.item.enchantment.EnchantmentCategory$1
+ XXX.item.enchantment.EnchantmentCategory$10
- XXX.item.enchantment.EnchantmentCategory$11
+ XXX.item.enchantment.EnchantmentCategory$12
- XXX.item.enchantment.EnchantmentCategory$13
+ XXX.item.enchantment.EnchantmentCategory$14
- XXX.item.enchantment.EnchantmentCategory$2
+ XXX.item.enchantment.EnchantmentCategory$3
- XXX.item.enchantment.EnchantmentCategory$4
+ XXX.item.enchantment.EnchantmentCategory$5
- XXX.item.enchantment.EnchantmentCategory$6
+ XXX.item.enchantment.EnchantmentCategory$7
- XXX.item.enchantment.EnchantmentCategory$8
+ XXX.item.enchantment.EnchantmentCategory$9
- XXX.item.enchantment.EnchantmentHelper
+ XXX.item.enchantment.EnchantmentHelper$EnchantmentVisitor
- XXX.item.enchantment.EnchantmentInstance
+ XXX.item.enchantment.Enchantments
- XXX.item.enchantment.FireAspectEnchantment
+ XXX.item.enchantment.FishingSpeedEnchantment
- XXX.item.enchantment.FrostWalkerEnchantment
+ XXX.item.enchantment.KnockbackEnchantment
- XXX.item.enchantment.LootBonusEnchantment
+ XXX.item.enchantment.MendingEnchantment
- XXX.item.enchantment.MultiShotEnchantment
+ XXX.item.enchantment.OxygenEnchantment
+ XXX.item.enchantment.package-info
- XXX.item.enchantment.ProtectionEnchantment
+ XXX.item.enchantment.ProtectionEnchantment$Type
- XXX.item.enchantment.QuickChargeEnchantment
+ XXX.item.enchantment.SoulSpeedEnchantment
- XXX.item.enchantment.SweepingEdgeEnchantment
+ XXX.item.enchantment.SwiftSneakEnchantment
- XXX.item.enchantment.ThornsEnchantment
+ XXX.item.enchantment.TridentChannelingEnchantment
- XXX.item.enchantment.TridentImpalerEnchantment
+ XXX.item.enchantment.TridentLoyaltyEnchantment
- XXX.item.enchantment.TridentRiptideEnchantment
+ XXX.item.enchantment.UntouchingEnchantment
- XXX.item.enchantment.VanishingCurseEnchantment
+ XXX.item.enchantment.WaterWalkerEnchantment
- XXX.item.enchantment.WaterWorkerEnchantment
+ XXX.item.trading.Merchant
- XXX.item.trading.MerchantOffer
+ XXX.item.trading.MerchantOffers
- XXX.item.trading.package-info
- XXX.level.biome.AmbientAdditionsSettings
+ XXX.level.biome.AmbientMoodSettings
- XXX.level.biome.AmbientParticleSettings
+ XXX.level.biome.Biome
- XXX.level.biome.Biome$1
+ XXX.level.biome.Biome$BiomeBuilder
- XXX.level.biome.Biome$ClimateSettings
+ XXX.level.biome.Biome$Precipitation
- XXX.level.biome.Biome$TemperatureModifier
+ XXX.level.biome.Biome$TemperatureModifier$1
- XXX.level.biome.Biome$TemperatureModifier$2
+ XXX.level.biome.BiomeGenerationSettings
- XXX.level.biome.BiomeGenerationSettings$Builder
+ XXX.level.biome.BiomeGenerationSettings$PlainBuilder
- XXX.level.biome.BiomeManager
+ XXX.level.biome.BiomeManager$NoiseBiomeSource
- XXX.level.biome.BiomeResolver
+ XXX.level.biome.Biomes
+ XXX.level.biome.BiomeSource
- XXX.level.biome.BiomeSources
+ XXX.level.biome.BiomeSpecialEffects
- XXX.level.biome.BiomeSpecialEffects$Builder
+ XXX.level.biome.BiomeSpecialEffects$GrassColorModifier
- XXX.level.biome.BiomeSpecialEffects$GrassColorModifier$1
+ XXX.level.biome.BiomeSpecialEffects$GrassColorModifier$2
- XXX.level.biome.BiomeSpecialEffects$GrassColorModifier$3
- XXX.level.biome.CheckerboardColumnBiomeSource
+ XXX.level.biome.Climate
- XXX.level.biome.Climate$DistanceMetric
+ XXX.level.biome.Climate$Parameter
- XXX.level.biome.Climate$ParameterList
+ XXX.level.biome.Climate$ParameterPoint
- XXX.level.biome.Climate$RTree
+ XXX.level.biome.Climate$RTree$Leaf
- XXX.level.biome.Climate$RTree$Node
+ XXX.level.biome.Climate$RTree$SubTree
- XXX.level.biome.Climate$Sampler
+ XXX.level.biome.Climate$SpawnFinder
- XXX.level.biome.Climate$SpawnFinder$Result
+ XXX.level.biome.Climate$TargetPoint
- XXX.level.biome.FeatureSorter
+ XXX.level.biome.FeatureSorter$1FeatureData
- XXX.level.biome.FeatureSorter$StepFeatureData
+ XXX.level.biome.FixedBiomeSource
- XXX.level.biome.MobSpawnSettings
+ XXX.level.biome.MobSpawnSettings$Builder
- XXX.level.biome.MobSpawnSettings$MobSpawnCost
+ XXX.level.biome.MobSpawnSettings$SpawnerData
- XXX.level.biome.MultiNoiseBiomeSource
+ XXX.level.biome.MultiNoiseBiomeSourceParameterList
- XXX.level.biome.MultiNoiseBiomeSourceParameterList$Preset
+ XXX.level.biome.MultiNoiseBiomeSourceParameterList$Preset$1
- XXX.level.biome.MultiNoiseBiomeSourceParameterList$Preset$2
+ XXX.level.biome.MultiNoiseBiomeSourceParameterList$Preset$SourceProvider
- XXX.level.biome.MultiNoiseBiomeSourceParameterLists
+ XXX.level.biome.OverworldBiomeBuilder
+ XXX.level.biome.package-info
- XXX.level.biome.TheEndBiomeSource
- XXX.level.block.AbstractBannerBlock
+ XXX.level.block.AbstractCandleBlock
- XXX.level.block.AbstractCauldronBlock
+ XXX.level.block.AbstractChestBlock
- XXX.level.block.AbstractFurnaceBlock
+ XXX.level.block.AbstractGlassBlock
- XXX.level.block.AbstractSkullBlock
+ XXX.level.block.AirBlock
- XXX.level.block.AmethystBlock
+ XXX.level.block.AmethystClusterBlock
- XXX.level.block.AmethystClusterBlock$1
+ XXX.level.block.AnvilBlock
- XXX.level.block.AttachedStemBlock
+ XXX.level.block.AzaleaBlock
- XXX.level.block.BambooSaplingBlock
+ XXX.level.block.BambooStalkBlock
- XXX.level.block.BannerBlock
+ XXX.level.block.BarrelBlock
- XXX.level.block.BarrierBlock
+ XXX.level.block.BaseCoralFanBlock
- XXX.level.block.BaseCoralPlantBlock
+ XXX.level.block.BaseCoralPlantTypeBlock
- XXX.level.block.BaseCoralWallFanBlock
+ XXX.level.block.BaseEntityBlock
- XXX.level.block.BaseFireBlock
+ XXX.level.block.BasePressurePlateBlock
- XXX.level.block.BaseRailBlock
+ XXX.level.block.BaseRailBlock$1
- XXX.level.block.BeaconBeamBlock
+ XXX.level.block.BeaconBlock
- XXX.level.block.BedBlock
+ XXX.level.block.BedBlock$1
- XXX.level.block.BeehiveBlock
+ XXX.level.block.BeetrootBlock
- XXX.level.block.BellBlock
+ XXX.level.block.BellBlock$1
- XXX.level.block.BigDripleafBlock
+ XXX.level.block.BigDripleafStemBlock
- XXX.level.block.BigDripleafStemBlock$1
+ XXX.level.block.BlastFurnaceBlock
- XXX.level.block.Block
+ XXX.level.block.Block$1
- XXX.level.block.Block$2
+ XXX.level.block.Block$BlockStatePairKey
- XXX.level.block.Blocks
+ XXX.level.block.BonemealableBlock
- XXX.level.block.BrewingStandBlock
+ XXX.level.block.BrushableBlock
- XXX.level.block.BubbleColumnBlock
+ XXX.level.block.BucketPickup
- XXX.level.block.BuddingAmethystBlock
+ XXX.level.block.BushBlock
- XXX.level.block.ButtonBlock
+ XXX.level.block.ButtonBlock$1
- XXX.level.block.CactusBlock
+ XXX.level.block.CakeBlock
- XXX.level.block.CalibratedSculkSensorBlock
+ XXX.level.block.CampfireBlock
- XXX.level.block.CandleBlock
+ XXX.level.block.CandleCakeBlock
- XXX.level.block.CarpetBlock
+ XXX.level.block.CarrotBlock
- XXX.level.block.CartographyTableBlock
+ XXX.level.block.CarvedPumpkinBlock
- XXX.level.block.CauldronBlock
+ XXX.level.block.CaveVines
- XXX.level.block.CaveVinesBlock
+ XXX.level.block.CaveVinesPlantBlock
- XXX.level.block.CeilingHangingSignBlock
+ XXX.level.block.ChainBlock
- XXX.level.block.ChainBlock$1
+ XXX.level.block.ChangeOverTimeBlock
- XXX.level.block.CherryLeavesBlock
+ XXX.level.block.ChestBlock
- XXX.level.block.ChestBlock$1
+ XXX.level.block.ChestBlock$2
- XXX.level.block.ChestBlock$2$1
+ XXX.level.block.ChestBlock$3
- XXX.level.block.ChestBlock$4
+ XXX.level.block.ChiseledBookShelfBlock
- XXX.level.block.ChiseledBookShelfBlock$1
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
+ XXX.level.block.CryingObsidianBlock
- XXX.level.block.DaylightDetectorBlock
+ XXX.level.block.DeadBushBlock
- XXX.level.block.DecoratedPotBlock
+ XXX.level.block.DetectorRailBlock
- XXX.level.block.DetectorRailBlock$1
+ XXX.level.block.DiodeBlock
- XXX.level.block.DirectionalBlock
+ XXX.level.block.DirtPathBlock
- XXX.level.block.DispenserBlock
+ XXX.level.block.DoorBlock
- XXX.level.block.DoorBlock$1
+ XXX.level.block.DoubleBlockCombiner
- XXX.level.block.DoubleBlockCombiner$BlockType
+ XXX.level.block.DoubleBlockCombiner$Combiner
- XXX.level.block.DoubleBlockCombiner$NeighborCombineResult
+ XXX.level.block.DoubleBlockCombiner$NeighborCombineResult$Double
- XXX.level.block.DoubleBlockCombiner$NeighborCombineResult$Single
+ XXX.level.block.DoublePlantBlock
- XXX.level.block.DragonEggBlock
+ XXX.level.block.DropExperienceBlock
- XXX.level.block.DropperBlock
+ XXX.level.block.EnchantmentTableBlock
- XXX.level.block.EnderChestBlock
- XXX.level.block.EndGatewayBlock
+ XXX.level.block.EndPortalBlock
- XXX.level.block.EndPortalFrameBlock
+ XXX.level.block.EndRodBlock
+ XXX.level.block.EntityBlock
- XXX.level.block.FaceAttachedHorizontalDirectionalBlock
+ XXX.level.block.FaceAttachedHorizontalDirectionalBlock$1
- XXX.level.block.Fallable
+ XXX.level.block.FallingBlock
+ XXX.level.block.FarmableBlock
- XXX.level.block.FarmBlock
- XXX.level.gameevent.GameEvent
+ XXX.level.gameevent.GameEvent$Context
- XXX.level.gameevent.GameEvent$ListenerInfo
+ XXX.level.gameevent.GameEventDispatcher
- XXX.level.gameevent.GameEventListener
+ XXX.level.gameevent.GameEventListener$DeliveryMode
- XXX.level.gameevent.GameEventListener$Holder
+ XXX.level.levelgen.Aquifer
- XXX.level.levelgen.Aquifer$1
+ XXX.level.levelgen.Aquifer$FluidPicker
- XXX.level.levelgen.Aquifer$FluidStatus
+ XXX.level.levelgen.Aquifer$NoiseBasedAquifer
- XXX.level.levelgen.Beardifier
+ XXX.level.levelgen.Beardifier$1
- XXX.level.levelgen.Beardifier$Rigid
+ XXX.level.levelgen.BelowZeroRetrogen
- XXX.level.levelgen.BelowZeroRetrogen$1
+ XXX.level.levelgen.BitRandomSource
- XXX.level.levelgen.Column
+ XXX.level.levelgen.Column$Line
- XXX.level.levelgen.Column$Range
+ XXX.level.levelgen.Column$Ray
- XXX.level.levelgen.DebugLevelSource
+ XXX.level.levelgen.Density
- XXX.level.levelgen.DensityFunction
+ XXX.level.levelgen.DensityFunction$ContextProvider
- XXX.level.levelgen.DensityFunction$FunctionContext
+ XXX.level.levelgen.DensityFunction$NoiseHolder
- XXX.level.levelgen.DensityFunction$SimpleFunction
+ XXX.level.levelgen.DensityFunction$SinglePointContext
- XXX.level.levelgen.DensityFunction$Visitor
+ XXX.level.levelgen.DensityFunctions
- XXX.level.levelgen.DensityFunctions$1
+ XXX.level.levelgen.DensityFunctions$Ap2
- XXX.level.levelgen.DensityFunctions$BeardifierMarker
+ XXX.level.levelgen.DensityFunctions$BeardifierOrMarker
- XXX.level.levelgen.DensityFunctions$BlendAlpha
+ XXX.level.levelgen.DensityFunctions$BlendDensity
- XXX.level.levelgen.DensityFunctions$BlendOffset
+ XXX.level.levelgen.DensityFunctions$Clamp
- XXX.level.levelgen.DensityFunctions$Constant
+ XXX.level.levelgen.DensityFunctions$EndIslandDensityFunction
- XXX.level.levelgen.DensityFunctions$HolderHolder
+ XXX.level.levelgen.DensityFunctions$Mapped
- XXX.level.levelgen.DensityFunctions$Mapped$Type
+ XXX.level.levelgen.DensityFunctions$Marker
- XXX.level.levelgen.DensityFunctions$Marker$Type
+ XXX.level.levelgen.DensityFunctions$MarkerOrMarked
- XXX.level.levelgen.DensityFunctions$MulOrAdd
+ XXX.level.levelgen.DensityFunctions$MulOrAdd$Type
- XXX.level.levelgen.DensityFunctions$Noise
+ XXX.level.levelgen.DensityFunctions$PureTransformer
- XXX.level.levelgen.DensityFunctions$RangeChoice
+ XXX.level.levelgen.DensityFunctions$Shift
- XXX.level.levelgen.DensityFunctions$ShiftA
+ XXX.level.levelgen.DensityFunctions$ShiftB
+ XXX.level.levelgen.DensityFunctions$ShiftedNoise
- XXX.level.levelgen.DensityFunctions$ShiftNoise
- XXX.level.levelgen.DensityFunctions$Spline
+ XXX.level.levelgen.DensityFunctions$Spline$Coordinate
- XXX.level.levelgen.DensityFunctions$Spline$Point
+ XXX.level.levelgen.DensityFunctions$TransformerWithContext
- XXX.level.levelgen.DensityFunctions$TwoArgumentSimpleFunction
+ XXX.level.levelgen.DensityFunctions$TwoArgumentSimpleFunction$Type
- XXX.level.levelgen.DensityFunctions$WeirdScaledSampler
+ XXX.level.levelgen.DensityFunctions$WeirdScaledSampler$RarityValueMapper
- XXX.level.levelgen.DensityFunctions$YClampedGradient
+ XXX.level.levelgen.FlatLevelSource
- XXX.level.levelgen.GenerationStep
+ XXX.level.levelgen.GenerationStep$Carving
- XXX.level.levelgen.GenerationStep$Decoration
+ XXX.level.levelgen.GeodeBlockSettings
- XXX.level.levelgen.GeodeCrackSettings
+ XXX.level.levelgen.GeodeLayerSettings
- XXX.level.levelgen.Heightmap
+ XXX.level.levelgen.Heightmap$Types
- XXX.level.levelgen.Heightmap$Usage
+ XXX.level.levelgen.LegacyRandomSource
- XXX.level.levelgen.LegacyRandomSource$LegacyPositionalRandomFactory
+ XXX.level.levelgen.MarsagliaPolarGaussian
- XXX.level.levelgen.NoiseBasedChunkGenerator
+ XXX.level.levelgen.NoiseChunk
- XXX.level.levelgen.NoiseChunk$1
+ XXX.level.levelgen.NoiseChunk$2
- XXX.level.levelgen.NoiseChunk$BlendAlpha
+ XXX.level.levelgen.NoiseChunk$BlendOffset
- XXX.level.levelgen.NoiseChunk$BlockStateFiller
+ XXX.level.levelgen.NoiseChunk$Cache2D
- XXX.level.levelgen.NoiseChunk$CacheAllInCell
+ XXX.level.levelgen.NoiseChunk$CacheOnce
- XXX.level.levelgen.NoiseChunk$FlatCache
+ XXX.level.levelgen.NoiseChunk$NoiseChunkDensityFunction
- XXX.level.levelgen.NoiseChunk$NoiseInterpolator
+ XXX.level.levelgen.NoiseGeneratorSettings
- XXX.level.levelgen.NoiseRouter
+ XXX.level.levelgen.NoiseRouterData
- XXX.level.levelgen.NoiseRouterData$QuantizedSpaghettiRarity
- XXX.level.levelgen.Noises
+ XXX.level.levelgen.NoiseSettings
+ XXX.level.levelgen.OreVeinifier
- XXX.level.levelgen.OreVeinifier$VeinType
- XXX.level.levelgen.package-info
+ XXX.level.levelgen.PatrolSpawner
- XXX.level.levelgen.PhantomSpawner
+ XXX.level.levelgen.PositionalRandomFactory
- XXX.level.levelgen.RandomState
+ XXX.level.levelgen.RandomState$1
- XXX.level.levelgen.RandomState$1NoiseWiringHelper
+ XXX.level.levelgen.RandomSupport
- XXX.level.levelgen.RandomSupport$Seed128bit
+ XXX.level.levelgen.SingleThreadedRandomSource
- XXX.level.levelgen.SurfaceRules
+ XXX.level.levelgen.SurfaceRules$AbovePreliminarySurface
- XXX.level.levelgen.SurfaceRules$Bandlands
+ XXX.level.levelgen.SurfaceRules$BiomeConditionSource
- XXX.level.levelgen.SurfaceRules$BiomeConditionSource$1BiomeCondition
+ XXX.level.levelgen.SurfaceRules$BlockRuleSource
- XXX.level.levelgen.SurfaceRules$Condition
+ XXX.level.levelgen.SurfaceRules$ConditionSource
- XXX.level.levelgen.SurfaceRules$Context
+ XXX.level.levelgen.SurfaceRules$Context$AbovePreliminarySurfaceCondition
- XXX.level.levelgen.SurfaceRules$Context$HoleCondition
+ XXX.level.levelgen.SurfaceRules$Context$SteepMaterialCondition
- XXX.level.levelgen.SurfaceRules$Context$TemperatureHelperCondition
+ XXX.level.levelgen.SurfaceRules$Hole
- XXX.level.levelgen.SurfaceRules$LazyCondition
+ XXX.level.levelgen.SurfaceRules$LazyXZCondition
- XXX.level.levelgen.SurfaceRules$LazyYCondition
+ XXX.level.levelgen.SurfaceRules$NoiseThresholdConditionSource
- XXX.level.levelgen.SurfaceRules$NoiseThresholdConditionSource$1NoiseThresholdCondition
+ XXX.level.levelgen.SurfaceRules$NotCondition
- XXX.level.levelgen.SurfaceRules$NotConditionSource
+ XXX.level.levelgen.SurfaceRules$RuleSource
- XXX.level.levelgen.SurfaceRules$SequenceRule
+ XXX.level.levelgen.SurfaceRules$SequenceRuleSource
- XXX.level.levelgen.SurfaceRules$StateRule
+ XXX.level.levelgen.SurfaceRules$Steep
- XXX.level.levelgen.SurfaceRules$StoneDepthCheck
+ XXX.level.levelgen.SurfaceRules$StoneDepthCheck$1StoneDepthCondition
- XXX.level.levelgen.SurfaceRules$SurfaceRule
+ XXX.level.levelgen.SurfaceRules$Temperature
- XXX.level.levelgen.SurfaceRules$TestRule
+ XXX.level.levelgen.SurfaceRules$TestRuleSource
- XXX.level.levelgen.SurfaceRules$VerticalGradientConditionSource
+ XXX.level.levelgen.SurfaceRules$VerticalGradientConditionSource$1VerticalGradientCondition
- XXX.level.levelgen.SurfaceRules$WaterConditionSource
+ XXX.level.levelgen.SurfaceRules$WaterConditionSource$1WaterCondition
- XXX.level.levelgen.SurfaceRules$YConditionSource
+ XXX.level.levelgen.SurfaceRules$YConditionSource$1YCondition
- XXX.level.levelgen.SurfaceSystem
+ XXX.level.levelgen.SurfaceSystem$1
- XXX.level.levelgen.ThreadSafeLegacyRandomSource
+ XXX.level.levelgen.VerticalAnchor
- XXX.level.levelgen.VerticalAnchor$AboveBottom
+ XXX.level.levelgen.VerticalAnchor$Absolute
- XXX.level.levelgen.VerticalAnchor$BelowTop
+ XXX.level.levelgen.WorldDimensions
- XXX.level.levelgen.WorldDimensions$1Entry
+ XXX.level.levelgen.WorldDimensions$Complete
+ XXX.level.levelgen.WorldGenerationContext
+ XXX.level.levelgen.WorldgenRandom
- XXX.level.levelgen.WorldgenRandom$Algorithm
- XXX.level.levelgen.WorldGenSettings
- XXX.level.levelgen.WorldOptions
+ XXX.level.levelgen.Xoroshiro128PlusPlus
- XXX.level.levelgen.XoroshiroRandomSource
+ XXX.level.levelgen.XoroshiroRandomSource$XoroshiroPositionalRandomFactory
- XXX.level.lighting.BlockLightEngine
+ XXX.level.lighting.BlockLightSectionStorage
- XXX.level.lighting.BlockLightSectionStorage$BlockDataLayerStorageMap
+ XXX.level.lighting.DataLayerStorageMap
- XXX.level.lighting.DynamicGraphMinFixedPoint
+ XXX.level.lighting.DynamicGraphMinFixedPoint$1
- XXX.level.lighting.LayerLightEngine
+ XXX.level.lighting.LayerLightEventListener
- XXX.level.lighting.LayerLightEventListener$DummyLightLayerEventListener
+ XXX.level.lighting.LayerLightSectionStorage
- XXX.level.lighting.LayerLightSectionStorage$1
- XXX.level.lighting.LeveledPriorityQueue
+ XXX.level.lighting.LeveledPriorityQueue$1
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
- XXX.level.material.FogType
+ XXX.level.material.LavaFluid
- XXX.level.material.LavaFluid$Flowing
+ XXX.level.material.LavaFluid$Source
- XXX.level.material.Material
+ XXX.level.material.Material$Builder
- XXX.levelgen.blending.Blender
+ XXX.levelgen.blending.Blender$1
- XXX.levelgen.blending.Blender$BlendingOutput
+ XXX.levelgen.blending.Blender$CellValueGetter
- XXX.levelgen.blending.Blender$DistanceGetter
+ XXX.levelgen.blending.BlendingData
- XXX.levelgen.blending.BlendingData$BiomeConsumer
+ XXX.levelgen.blending.BlendingData$DensityConsumer
- XXX.levelgen.blending.BlendingData$HeightConsumer
+ XXX.levelgen.blending.package-info
- XXX.levelgen.blockpredicates.AllOfPredicate
+ XXX.levelgen.blockpredicates.AnyOfPredicate
- XXX.levelgen.blockpredicates.BlockPredicate
+ XXX.levelgen.blockpredicates.BlockPredicateType
- XXX.levelgen.blockpredicates.CombiningPredicate
+ XXX.levelgen.blockpredicates.HasSturdyFacePredicate
- XXX.levelgen.blockpredicates.InsideWorldBoundsPredicate
- XXX.levelgen.blockpredicates.MatchingBlocksPredicate
+ XXX.levelgen.blockpredicates.MatchingBlockTagPredicate
+ XXX.levelgen.blockpredicates.MatchingFluidsPredicate
- XXX.levelgen.blockpredicates.NotPredicate
- XXX.levelgen.blockpredicates.package-info
+ XXX.levelgen.blockpredicates.ReplaceablePredicate
- XXX.levelgen.blockpredicates.SolidPredicate
+ XXX.levelgen.blockpredicates.StateTestingPredicate
- XXX.levelgen.blockpredicates.TrueBlockPredicate
+ XXX.levelgen.blockpredicates.WouldSurvivePredicate
+ XXX.levelgen.carver.CanyonCarverConfiguration
- XXX.levelgen.carver.CanyonCarverConfiguration$CanyonShapeConfiguration
+ XXX.levelgen.carver.CanyonWorldCarver
- XXX.levelgen.carver.CarverConfiguration
+ XXX.levelgen.carver.CarverDebugSettings
- XXX.levelgen.carver.CarvingContext
+ XXX.levelgen.carver.CaveCarverConfiguration
- XXX.levelgen.carver.CaveWorldCarver
+ XXX.levelgen.carver.ConfiguredWorldCarver
- XXX.levelgen.carver.NetherWorldCarver
+ XXX.levelgen.carver.package-info
+ XXX.levelgen.carver.WorldCarver
- XXX.levelgen.carver.WorldCarver$CarveSkipChecker
- XXX.levelgen.feature.AbstractHugeMushroomFeature
+ XXX.levelgen.feature.BambooFeature
- XXX.levelgen.feature.BasaltColumnsFeature
+ XXX.levelgen.feature.BasaltPillarFeature
- XXX.levelgen.feature.BlockBlobFeature
+ XXX.levelgen.feature.BlockColumnFeature
- XXX.levelgen.feature.BlockPileFeature
+ XXX.levelgen.feature.BlueIceFeature
- XXX.levelgen.feature.BonusChestFeature
+ XXX.levelgen.feature.ChorusPlantFeature
- XXX.levelgen.feature.ConfiguredFeature
+ XXX.levelgen.feature.CoralClawFeature
- XXX.levelgen.feature.CoralFeature
+ XXX.levelgen.feature.CoralMushroomFeature
- XXX.levelgen.feature.CoralTreeFeature
+ XXX.levelgen.feature.DeltaFeature
- XXX.levelgen.feature.DesertWellFeature
+ XXX.levelgen.feature.DiskFeature
- XXX.levelgen.feature.DripstoneClusterFeature
+ XXX.levelgen.feature.DripstoneUtils
- XXX.levelgen.feature.EndGatewayFeature
+ XXX.levelgen.feature.EndIslandFeature
- XXX.levelgen.feature.EndPodiumFeature
+ XXX.levelgen.feature.Feature
- XXX.levelgen.feature.FeatureCountTracker
+ XXX.levelgen.feature.FeatureCountTracker$1
- XXX.levelgen.feature.FeatureCountTracker$FeatureData
+ XXX.levelgen.feature.FeatureCountTracker$LevelData
- XXX.levelgen.feature.FeaturePlaceContext
+ XXX.levelgen.feature.FillLayerFeature
- XXX.levelgen.feature.FossilFeature
+ XXX.levelgen.feature.FossilFeatureConfiguration
- XXX.levelgen.feature.GeodeFeature
+ XXX.levelgen.feature.GlowstoneFeature
- XXX.levelgen.feature.HugeBrownMushroomFeature
+ XXX.levelgen.feature.HugeFungusConfiguration
- XXX.levelgen.feature.HugeFungusFeature
+ XXX.levelgen.feature.HugeRedMushroomFeature
+ XXX.levelgen.feature.IcebergFeature
- XXX.levelgen.feature.IceSpikeFeature
- XXX.levelgen.feature.KelpFeature
+ XXX.levelgen.feature.LakeFeature
- XXX.levelgen.feature.LakeFeature$Configuration
+ XXX.levelgen.feature.LargeDripstoneFeature
- XXX.levelgen.feature.LargeDripstoneFeature$LargeDripstone
+ XXX.levelgen.feature.LargeDripstoneFeature$WindOffsetter
- XXX.levelgen.feature.MonsterRoomFeature
+ XXX.levelgen.feature.MultifaceGrowthFeature
- XXX.levelgen.feature.NetherForestVegetationFeature
+ XXX.levelgen.feature.NoOpFeature
- XXX.levelgen.feature.OreFeature
+ XXX.levelgen.feature.package-info
+ XXX.levelgen.feature.PointedDripstoneFeature
- XXX.levelgen.feature.RandomBooleanSelectorFeature
+ XXX.levelgen.feature.RandomPatchFeature
- XXX.levelgen.feature.RandomSelectorFeature
+ XXX.levelgen.feature.ReplaceBlobsFeature
- XXX.levelgen.feature.ReplaceBlockFeature
+ XXX.levelgen.feature.RootSystemFeature
- XXX.levelgen.feature.ScatteredOreFeature
+ XXX.levelgen.feature.SculkPatchFeature
+ XXX.levelgen.feature.SeagrassFeature
- XXX.levelgen.feature.SeaPickleFeature
- XXX.levelgen.feature.SimpleBlockFeature
+ XXX.levelgen.feature.SimpleRandomSelectorFeature
- XXX.levelgen.feature.SnowAndFreezeFeature
+ XXX.levelgen.feature.SpikeFeature
- XXX.levelgen.feature.SpikeFeature$EndSpike
+ XXX.levelgen.feature.SpikeFeature$SpikeCacheLoader
- XXX.levelgen.feature.SpringFeature
+ XXX.levelgen.feature.TreeFeature
- XXX.levelgen.feature.TreeFeature$1
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
+ XXX.levelgen.placement.package-info
+ XXX.levelgen.placement.PlacedFeature
- XXX.levelgen.placement.PlacementContext
+ XXX.levelgen.placement.PlacementFilter
- XXX.levelgen.placement.PlacementModifier
+ XXX.levelgen.placement.PlacementModifierType
- XXX.levelgen.placement.RandomOffsetPlacement
+ XXX.levelgen.placement.RarityFilter
- XXX.levelgen.placement.RepeatingPlacement
+ XXX.levelgen.placement.SurfaceRelativeThresholdFilter
- XXX.levelgen.placement.SurfaceWaterDepthFilter
+ XXX.levelgen.presets.package-info
- XXX.levelgen.presets.WorldPreset
+ XXX.levelgen.presets.WorldPresets
- XXX.levelgen.presets.WorldPresets$Bootstrap
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
+ XXX.levelgen.structure.Structure$StructureSettings
- XXX.levelgen.structure.StructureCheck
+ XXX.levelgen.structure.StructureCheckResult
- XXX.levelgen.structure.StructureFeatureIndexSavedData
+ XXX.levelgen.structure.StructurePiece
- XXX.levelgen.structure.StructurePiece$1
+ XXX.levelgen.structure.StructurePiece$BlockSelector
- XXX.levelgen.structure.StructurePieceAccessor
+ XXX.levelgen.structure.StructureSet
- XXX.levelgen.structure.StructureSet$StructureSelectionEntry
+ XXX.levelgen.structure.StructureSpawnOverride
- XXX.levelgen.structure.StructureSpawnOverride$BoundingBoxType
+ XXX.levelgen.structure.StructureStart
- XXX.levelgen.structure.StructureType
+ XXX.levelgen.structure.TemplateStructurePiece
- XXX.levelgen.structure.TerrainAdjustment
+ XXX.levelgen.synth.BlendedNoise
- XXX.levelgen.synth.ImprovedNoise
+ XXX.levelgen.synth.NoiseUtils
- XXX.levelgen.synth.NormalNoise
+ XXX.levelgen.synth.NormalNoise$NoiseParameters
+ XXX.levelgen.synth.package-info
- XXX.levelgen.synth.PerlinNoise
+ XXX.levelgen.synth.PerlinSimplexNoise
- XXX.levelgen.synth.SimplexNoise
- XXX.minecraft.server.ServerFunctionManager$QueuedCommand
+ XXX.minecraft.server.ServerFunctionManager$TraceCallbacks
- XXX.minecraft.server.ServerInterface
+ XXX.minecraft.server.ServerScoreboard
- XXX.minecraft.server.ServerScoreboard$Method
+ XXX.minecraft.server.Services
- XXX.minecraft.server.TickTask
+ XXX.minecraft.server.WorldLoader
- XXX.minecraft.server.WorldLoader$DataLoadContext
+ XXX.minecraft.server.WorldLoader$DataLoadOutput
- XXX.minecraft.server.WorldLoader$InitConfig
+ XXX.minecraft.server.WorldLoader$PackConfig
- XXX.minecraft.server.WorldLoader$ResultFactory
+ XXX.minecraft.server.WorldLoader$WorldDataSupplier
- XXX.minecraft.server.WorldStem
- XXX.monster.warden.package-info
- XXX.monster.warden.WardenAi
+ XXX.monster.warden.WardenSpawnTracker
- XXX.rule.blockentity.AppendLoot
+ XXX.rule.blockentity.AppendStatic
- XXX.rule.blockentity.Clear
- XXX.rule.blockentity.package-info
+ XXX.rule.blockentity.Passthrough
- XXX.rule.blockentity.RuleBlockEntityModifier
+ XXX.rule.blockentity.RuleBlockEntityModifierType
+ XXX.server.advancements.AdvancementVisibilityEvaluator
- XXX.server.advancements.AdvancementVisibilityEvaluator$Output
+ XXX.server.advancements.AdvancementVisibilityEvaluator$VisibilityRule
- XXX.server.advancements.package-info
+ XXX.server.bossevents.CustomBossEvent
- XXX.server.bossevents.CustomBossEvents
+ XXX.server.bossevents.package-info
- XXX.server.chase.ChaseClient
+ XXX.server.chase.ChaseClient$TeleportTarget
- XXX.server.chase.ChaseServer
+ XXX.server.chase.ChaseServer$PlayerPosition
- XXX.server.chase.package-info
+ XXX.server.commands.AdvancementCommands
- XXX.server.commands.AdvancementCommands$Action
+ XXX.server.commands.AdvancementCommands$Action$1
- XXX.server.commands.AdvancementCommands$Action$2
+ XXX.server.commands.AdvancementCommands$Mode
- XXX.server.commands.AttributeCommand
+ XXX.server.commands.BanIpCommands
- XXX.server.commands.BanListCommands
+ XXX.server.commands.BanPlayerCommands
- XXX.server.commands.BossBarCommands
+ XXX.server.commands.ChaseCommand
- XXX.server.commands.ClearInventoryCommands
+ XXX.server.commands.CloneCommands
- XXX.server.commands.CloneCommands$CloneBlockInfo
+ XXX.server.commands.CloneCommands$CommandFunction
- XXX.server.commands.CloneCommands$DimensionAndPosition
+ XXX.server.commands.CloneCommands$Mode
- XXX.server.commands.DamageCommand
+ XXX.server.commands.DataPackCommand
- XXX.server.commands.DataPackCommand$Inserter
- XXX.server.commands.DebugCommand
+ XXX.server.commands.DebugCommand$Tracer
- XXX.server.commands.DebugMobSpawningCommand
+ XXX.server.commands.DebugPathCommand
- XXX.server.commands.DefaultGameModeCommands
+ XXX.server.commands.DeOpCommands
+ XXX.server.commands.DifficultyCommand
- XXX.server.commands.EffectCommands
+ XXX.server.commands.EmoteCommands
- XXX.server.commands.EnchantCommand
+ XXX.server.commands.ExecuteCommand
- XXX.server.commands.ExecuteCommand$CommandNumericPredicate
+ XXX.server.commands.ExecuteCommand$CommandPredicate
- XXX.server.commands.ExperienceCommand
+ XXX.server.commands.ExperienceCommand$Type
- XXX.server.commands.FillBiomeCommand
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
+ XXX.server.commands.JfrCommand
- XXX.server.commands.KickCommand
+ XXX.server.commands.KillCommand
- XXX.server.commands.ListPlayersCommand
+ XXX.server.commands.LocateCommand
- XXX.server.commands.LootCommand
+ XXX.server.commands.LootCommand$Callback
- XXX.server.commands.LootCommand$DropConsumer
+ XXX.server.commands.LootCommand$TailProvider
- XXX.server.commands.MsgCommand
+ XXX.server.commands.OpCommand
- XXX.server.commands.PardonCommand
+ XXX.server.commands.PardonIpCommand
- XXX.server.commands.ParticleCommand
+ XXX.server.commands.PerfCommand
- XXX.server.commands.PlaceCommand
+ XXX.server.commands.PlaySoundCommand
- XXX.server.commands.PublishCommand
+ XXX.server.commands.RaidCommand
- XXX.server.commands.RecipeCommand
+ XXX.server.commands.ReloadCommand
- XXX.server.commands.ResetChunksCommand
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
+ XXX.structure.pools.JigsawPlacement$PieceState
- XXX.structure.pools.JigsawPlacement$Placer
+ XXX.structure.pools.LegacySinglePoolElement
- XXX.structure.pools.ListPoolElement
- XXX.structure.pools.package-info
+ XXX.structure.pools.SinglePoolElement
- XXX.structure.pools.StructurePoolElement
+ XXX.structure.pools.StructurePoolElementType
- XXX.structure.pools.StructureTemplatePool
+ XXX.structure.pools.StructureTemplatePool$Projection
+ XXX.structure.structures.BuriedTreasurePieces
- XXX.structure.structures.BuriedTreasurePieces$BuriedTreasurePiece
+ XXX.structure.structures.BuriedTreasureStructure
- XXX.structure.structures.DesertPyramidPiece
+ XXX.structure.structures.DesertPyramidStructure
- XXX.structure.structures.EndCityPieces
+ XXX.structure.structures.EndCityPieces$1
- XXX.structure.structures.EndCityPieces$2
+ XXX.structure.structures.EndCityPieces$3
- XXX.structure.structures.EndCityPieces$4
+ XXX.structure.structures.EndCityPieces$EndCityPiece
- XXX.structure.structures.EndCityPieces$SectionGenerator
+ XXX.structure.structures.EndCityStructure
- XXX.structure.structures.IglooPieces
+ XXX.structure.structures.IglooPieces$IglooPiece
- XXX.structure.structures.IglooStructure
+ XXX.structure.structures.JigsawStructure
- XXX.structure.structures.JigsawStructure$1
+ XXX.structure.structures.JungleTemplePiece
- XXX.structure.structures.JungleTemplePiece$MossStoneSelector
+ XXX.structure.structures.JungleTempleStructure
- XXX.structure.structures.MineshaftPieces
+ XXX.structure.structures.MineshaftPieces$1
- XXX.structure.structures.MineshaftPieces$MineShaftCorridor
+ XXX.structure.structures.MineshaftPieces$MineShaftCrossing
- XXX.structure.structures.MineshaftPieces$MineShaftPiece
+ XXX.structure.structures.MineshaftPieces$MineShaftRoom
- XXX.structure.structures.MineshaftPieces$MineShaftStairs
+ XXX.structure.structures.MineshaftStructure
- XXX.structure.structures.MineshaftStructure$Type
+ XXX.structure.structures.NetherFortressPieces
- XXX.structure.structures.NetherFortressPieces$1
+ XXX.structure.structures.NetherFortressPieces$BridgeCrossing
- XXX.structure.structures.NetherFortressPieces$BridgeEndFiller
+ XXX.structure.structures.NetherFortressPieces$BridgeStraight
- XXX.structure.structures.NetherFortressPieces$CastleCorridorStairsPiece
+ XXX.structure.structures.NetherFortressPieces$CastleCorridorTBalconyPiece
- XXX.structure.structures.NetherFortressPieces$CastleEntrance
+ XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorCrossingPiece
- XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorLeftTurnPiece
+ XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorPiece
- XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorRightTurnPiece
+ XXX.structure.structures.NetherFortressPieces$CastleStalkRoom
- XXX.structure.structures.NetherFortressPieces$MonsterThrone
+ XXX.structure.structures.NetherFortressPieces$NetherBridgePiece
- XXX.structure.structures.NetherFortressPieces$PieceWeight
+ XXX.structure.structures.NetherFortressPieces$RoomCrossing
- XXX.structure.structures.NetherFortressPieces$StairsRoom
+ XXX.structure.structures.NetherFortressPieces$StartPiece
- XXX.structure.structures.NetherFortressStructure
+ XXX.structure.structures.NetherFossilPieces
- XXX.structure.structures.NetherFossilPieces$NetherFossilPiece
+ XXX.structure.structures.NetherFossilStructure
- XXX.structure.structures.OceanMonumentPieces
+ XXX.structure.structures.OceanMonumentPieces$1
- XXX.structure.structures.OceanMonumentPieces$FitDoubleXRoom
+ XXX.structure.structures.OceanMonumentPieces$FitDoubleXYRoom
- XXX.structure.structures.OceanMonumentPieces$FitDoubleYRoom
+ XXX.structure.structures.OceanMonumentPieces$FitDoubleYZRoom
- XXX.structure.structures.OceanMonumentPieces$FitDoubleZRoom
+ XXX.structure.structures.OceanMonumentPieces$FitSimpleRoom
- XXX.structure.structures.OceanMonumentPieces$FitSimpleTopRoom
+ XXX.structure.structures.OceanMonumentPieces$MonumentBuilding
- XXX.structure.structures.OceanMonumentPieces$MonumentRoomFitter
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentCoreRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleXRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleXYRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleYRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleYZRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleZRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentEntryRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentPenthouse
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentPiece
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentSimpleRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentSimpleTopRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentWingRoom
+ XXX.structure.structures.OceanMonumentPieces$RoomDefinition
- XXX.structure.structures.OceanMonumentStructure
+ XXX.structure.structures.OceanRuinPieces
- XXX.structure.structures.OceanRuinPieces$1
+ XXX.structure.structures.OceanRuinPieces$OceanRuinPiece
- XXX.structure.structures.OceanRuinStructure
+ XXX.structure.structures.OceanRuinStructure$Type
- XXX.structure.structures.package-info
- XXX.structure.structures.RuinedPortalPiece
+ XXX.structure.structures.RuinedPortalPiece$Properties
- XXX.structure.structures.RuinedPortalPiece$VerticalPlacement
+ XXX.structure.structures.RuinedPortalStructure
- XXX.structure.structures.RuinedPortalStructure$Setup
+ XXX.structure.structures.ShipwreckPieces
- XXX.structure.structures.ShipwreckPieces$ShipwreckPiece
+ XXX.structure.structures.ShipwreckStructure
- XXX.structure.structures.StrongholdPieces
+ XXX.structure.structures.StrongholdPieces$1
- XXX.structure.structures.StrongholdPieces$2
+ XXX.structure.structures.StrongholdPieces$3
- XXX.structure.structures.StrongholdPieces$ChestCorridor
+ XXX.structure.structures.StrongholdPieces$FillerCorridor
- XXX.structure.structures.StrongholdPieces$FiveCrossing
+ XXX.structure.structures.StrongholdPieces$LeftTurn
- XXX.structure.structures.StrongholdPieces$Library
+ XXX.structure.structures.StrongholdPieces$PieceWeight
- XXX.structure.structures.StrongholdPieces$PortalRoom
+ XXX.structure.structures.StrongholdPieces$PrisonHall
- XXX.structure.structures.StrongholdPieces$RightTurn
+ XXX.structure.structures.StrongholdPieces$RoomCrossing
- XXX.structure.structures.StrongholdPieces$SmoothStoneSelector
+ XXX.structure.structures.StrongholdPieces$StairsDown
- XXX.structure.structures.StrongholdPieces$StartPiece
+ XXX.structure.structures.StrongholdPieces$Straight
- XXX.structure.structures.StrongholdPieces$StraightStairsDown
+ XXX.structure.structures.StrongholdPieces$StrongholdPiece
- XXX.structure.structures.StrongholdPieces$StrongholdPiece$SmallDoorType
+ XXX.structure.structures.StrongholdPieces$Turn
- XXX.structure.structures.StrongholdStructure
+ XXX.structure.structures.SwampHutPiece
- XXX.structure.structures.SwampHutStructure
+ XXX.structure.structures.WoodlandMansionPieces
- XXX.structure.structures.WoodlandMansionPieces$FirstFloorRoomCollection
+ XXX.structure.structures.WoodlandMansionPieces$FloorRoomCollection
- XXX.structure.structures.WoodlandMansionPieces$MansionGrid
+ XXX.structure.structures.WoodlandMansionPieces$MansionPiecePlacer
- XXX.structure.structures.WoodlandMansionPieces$PlacementData
+ XXX.structure.structures.WoodlandMansionPieces$SecondFloorRoomCollection
- XXX.structure.structures.WoodlandMansionPieces$SimpleGrid
+ XXX.structure.structures.WoodlandMansionPieces$ThirdFloorRoomCollection
- XXX.structure.structures.WoodlandMansionPieces$WoodlandMansionPiece
+ XXX.structure.structures.WoodlandMansionStructure
+ XXX.structure.templatesystem.AlwaysTrueTest
- XXX.structure.templatesystem.AxisAlignedLinearPosTest
+ XXX.structure.templatesystem.BlackstoneReplaceProcessor
- XXX.structure.templatesystem.BlockAgeProcessor
+ XXX.structure.templatesystem.BlockIgnoreProcessor
- XXX.structure.templatesystem.BlockMatchTest
+ XXX.structure.templatesystem.BlockRotProcessor
- XXX.structure.templatesystem.BlockStateMatchTest
+ XXX.structure.templatesystem.CappedProcessor
- XXX.structure.templatesystem.GravityProcessor
+ XXX.structure.templatesystem.JigsawReplacementProcessor
- XXX.structure.templatesystem.LavaSubmergedBlockProcessor
+ XXX.structure.templatesystem.LinearPosTest
- XXX.structure.templatesystem.NopProcessor
+ XXX.structure.templatesystem.package-info
+ XXX.structure.templatesystem.PosAlwaysTrueTest
- XXX.structure.templatesystem.PosRuleTest
+ XXX.structure.templatesystem.PosRuleTestType
- XXX.structure.templatesystem.ProcessorRule
+ XXX.structure.templatesystem.ProtectedBlockProcessor
- XXX.structure.templatesystem.RandomBlockMatchTest
+ XXX.structure.templatesystem.RandomBlockStateMatchTest
- XXX.structure.templatesystem.RuleProcessor
+ XXX.structure.templatesystem.RuleTest
- XXX.structure.templatesystem.RuleTestType
+ XXX.structure.templatesystem.StructurePlaceSettings
- XXX.structure.templatesystem.StructureProcessor
+ XXX.structure.templatesystem.StructureProcessorList
- XXX.structure.templatesystem.StructureProcessorType
+ XXX.structure.templatesystem.StructureTemplate
- XXX.structure.templatesystem.StructureTemplate$1
+ XXX.structure.templatesystem.StructureTemplate$Palette
- XXX.structure.templatesystem.StructureTemplate$SimplePalette
+ XXX.structure.templatesystem.StructureTemplate$StructureBlockInfo
- XXX.structure.templatesystem.StructureTemplate$StructureEntityInfo
+ XXX.structure.templatesystem.StructureTemplateManager
- XXX.structure.templatesystem.StructureTemplateManager$InputStreamOpener
+ XXX.structure.templatesystem.StructureTemplateManager$Source
- XXX.structure.templatesystem.TagMatchTest
- XXX.util.datafix.package-info
+ XXX.world.entity.package-info
+ XXX.world.flag.FeatureElement
- XXX.world.flag.FeatureFlag
+ XXX.world.flag.FeatureFlagRegistry
- XXX.world.flag.FeatureFlagRegistry$Builder
+ XXX.world.flag.FeatureFlags
+ XXX.world.flag.FeatureFlagSet
- XXX.world.flag.FeatureFlagUniverse
- XXX.world.flag.package-info
+ XXX.world.food.FoodConstants
- XXX.world.food.FoodData
+ XXX.world.food.FoodProperties
- XXX.world.food.FoodProperties$Builder
+ XXX.world.food.Foods
- XXX.world.food.package-info
+ XXX.world.inventory.AbstractContainerMenu
- XXX.world.inventory.AbstractContainerMenu$1
+ XXX.world.inventory.AbstractFurnaceMenu
- XXX.world.inventory.AnvilMenu
+ XXX.world.inventory.AnvilMenu$1
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
+ XXX.world.inventory.ClickAction
- XXX.world.inventory.ClickType
+ XXX.world.inventory.ContainerData
- XXX.world.inventory.ContainerLevelAccess
+ XXX.world.inventory.ContainerLevelAccess$1
- XXX.world.inventory.ContainerLevelAccess$2
+ XXX.world.inventory.ContainerListener
- XXX.world.inventory.ContainerSynchronizer
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
+ XXX.world.inventory.ItemCombinerMenu
- XXX.world.inventory.ItemCombinerMenu$1
+ XXX.world.inventory.ItemCombinerMenu$2
- XXX.world.inventory.ItemCombinerMenu$3
+ XXX.world.inventory.ItemCombinerMenuSlotDefinition
- XXX.world.inventory.ItemCombinerMenuSlotDefinition$Builder
+ XXX.world.inventory.ItemCombinerMenuSlotDefinition$SlotDefinition
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
+ XXX.world.inventory.package-info
+ XXX.world.inventory.PlayerEnderChestContainer
- XXX.world.inventory.RecipeBookMenu
+ XXX.world.inventory.RecipeBookType
- XXX.world.inventory.RecipeHolder
+ XXX.world.inventory.ResultContainer
- XXX.world.inventory.ResultSlot
+ XXX.world.inventory.ShulkerBoxMenu
- XXX.world.inventory.ShulkerBoxSlot
+ XXX.world.inventory.SimpleContainerData
- XXX.world.inventory.Slot
+ XXX.world.inventory.SmithingMenu
- XXX.world.inventory.SmokerMenu
+ XXX.world.inventory.StackedContentsCompatible
- XXX.world.inventory.StonecutterMenu
+ XXX.world.inventory.StonecutterMenu$1
- XXX.world.inventory.StonecutterMenu$2
+ XXX.world.item.AdventureModeCheck
- XXX.world.item.AirItem
+ XXX.world.item.ArmorItem
- XXX.world.item.ArmorItem$1
+ XXX.world.item.ArmorItem$Type
- XXX.world.item.ArmorMaterial
+ XXX.world.item.ArmorMaterials
- XXX.world.item.ArmorStandItem
+ XXX.world.item.ArrowItem
- XXX.world.item.AxeItem
+ XXX.world.item.BannerItem
- XXX.world.item.BannerPatternItem
+ XXX.world.item.BedItem
- XXX.world.item.BlockItem
+ XXX.world.item.BoatItem
- XXX.world.item.BoneMealItem
+ XXX.world.item.BookItem
- XXX.world.item.BottleItem
+ XXX.world.item.BowItem
- XXX.world.item.BowlFoodItem
+ XXX.world.item.BrushItem
- XXX.world.item.BrushItem$1
+ XXX.world.item.BrushItem$DustParticlesDelta
- XXX.world.item.BucketItem
+ XXX.world.item.BundleItem
- XXX.world.item.ChorusFruitItem
+ XXX.world.item.CompassItem
- XXX.world.item.ComplexItem
+ XXX.world.item.CreativeModeTab
- XXX.world.item.CreativeModeTab$1
+ XXX.world.item.CreativeModeTab$Builder
- XXX.world.item.CreativeModeTab$DisplayItemsGenerator
+ XXX.world.item.CreativeModeTab$ItemDisplayBuilder
- XXX.world.item.CreativeModeTab$ItemDisplayParameters
+ XXX.world.item.CreativeModeTab$Output
- XXX.world.item.CreativeModeTab$Row
+ XXX.world.item.CreativeModeTab$TabVisibility
- XXX.world.item.CreativeModeTab$Type
+ XXX.world.item.CreativeModeTabs
- XXX.world.item.CrossbowItem
+ XXX.world.item.DebugStickItem
- XXX.world.item.DiggerItem
+ XXX.world.item.DiscFragmentItem
- XXX.world.item.DispensibleContainerItem
+ XXX.world.item.DoubleHighBlockItem
- XXX.world.item.DyeableArmorItem
+ XXX.world.item.DyeableHorseArmorItem
- XXX.world.item.DyeableLeatherItem
- XXX.world.item.DyeColor
+ XXX.world.item.DyeItem
+ XXX.world.item.EggItem
- XXX.world.item.ElytraItem
+ XXX.world.item.EmptyMapItem
- XXX.world.item.EnchantedBookItem
+ XXX.world.item.EnchantedGoldenAppleItem
- XXX.world.item.EndCrystalItem
+ XXX.world.item.EnderEyeItem
- XXX.world.item.EnderpearlItem
+ XXX.world.item.Equipable
- XXX.world.item.ExperienceBottleItem
+ XXX.world.item.FireChargeItem
- XXX.world.item.FireworkRocketItem
+ XXX.world.item.FireworkRocketItem$Shape
- XXX.world.item.FireworkStarItem
+ XXX.world.item.FishingRodItem
- XXX.world.item.FlintAndSteelItem
+ XXX.world.item.FoodOnAStickItem
- XXX.world.item.GameMasterBlockItem
+ XXX.world.item.GlowInkSacItem
- XXX.world.item.HangingEntityItem
+ XXX.world.item.HangingSignItem
- XXX.world.item.HoeItem
+ XXX.world.item.HoneyBottleItem
- XXX.world.item.HoneycombItem
+ XXX.world.item.HorseArmorItem
- XXX.world.item.InkSacItem
+ XXX.world.item.Instrument
- XXX.world.item.InstrumentItem
+ XXX.world.item.Instruments
- XXX.world.item.Item
+ XXX.world.item.Item$1
- XXX.world.item.Item$Properties
+ XXX.world.item.ItemCooldowns
- XXX.world.item.ItemCooldowns$CooldownInstance
+ XXX.world.item.ItemDisplayContext
- XXX.world.item.ItemFrameItem
+ XXX.world.item.ItemNameBlockItem
+ XXX.world.item.Items
- XXX.world.item.ItemStack
+ XXX.world.item.ItemStack$TooltipPart
- XXX.world.item.ItemStackLinkedSet
+ XXX.world.item.ItemStackLinkedSet$1
- XXX.world.item.ItemUtils
- XXX.world.item.KnowledgeBookItem
+ XXX.world.item.LeadItem
- XXX.world.item.LingeringPotionItem
+ XXX.world.item.MapItem
- XXX.world.item.MilkBucketItem
+ XXX.world.item.MinecartItem
- XXX.world.item.MinecartItem$1
+ XXX.world.item.MobBucketItem
- XXX.world.item.NameTagItem
- XXX.world.item.package-info
+ XXX.world.item.PickaxeItem
- XXX.world.item.PlaceOnWaterBlockItem
+ XXX.world.item.PlayerHeadItem
- XXX.world.item.PotionItem
+ XXX.world.item.ProjectileWeaponItem
- XXX.world.item.Rarity
+ XXX.world.item.RecordItem
- XXX.world.item.SaddleItem
+ XXX.world.item.ScaffoldingBlockItem
- XXX.world.item.ServerItemCooldowns
+ XXX.world.item.ShearsItem
- XXX.world.item.ShieldItem
+ XXX.world.item.ShovelItem
- XXX.world.item.SignApplicator
+ XXX.world.item.SignItem
- XXX.world.item.SimpleFoiledItem
+ XXX.world.item.SmithingTemplateItem
- XXX.world.item.SnowballItem
+ XXX.world.item.SolidBucketItem
- XXX.world.item.SpawnEggItem
+ XXX.world.item.SpectralArrowItem
- XXX.world.item.SplashPotionItem
+ XXX.world.item.SpyglassItem
- XXX.world.item.StandingAndWallBlockItem
+ XXX.world.item.SuspiciousStewItem
- XXX.world.item.SwordItem
+ XXX.world.item.ThrowablePotionItem
- XXX.world.item.Tier
+ XXX.world.item.TieredItem
- XXX.world.item.Tiers
+ XXX.world.item.TippedArrowItem
- XXX.world.item.TooltipFlag
+ XXX.world.item.TooltipFlag$Default
- XXX.world.item.TridentItem
+ XXX.world.item.UseAnim
- XXX.world.item.Vanishable
+ XXX.world.item.WritableBookItem
- XXX.world.item.WrittenBookItem
+ XXX.world.level.BaseCommandBlock
- XXX.world.level.BaseSpawner
+ XXX.world.level.BlockAndTintGetter
- XXX.world.level.BlockCollisions
+ XXX.world.level.BlockEventData
- XXX.world.level.BlockGetter
+ XXX.world.level.ChunkPos
- XXX.world.level.ChunkPos$1
+ XXX.world.level.ClipBlockStateContext
- XXX.world.level.ClipContext
+ XXX.world.level.ClipContext$Block
- XXX.world.level.ClipContext$Fluid
+ XXX.world.level.ClipContext$ShapeGetter
- XXX.world.level.CollisionGetter
+ XXX.world.level.ColorResolver
- XXX.world.level.CommonLevelAccessor
+ XXX.world.level.CustomSpawner
- XXX.world.level.DataPackConfig
+ XXX.world.level.EmptyBlockGetter
- XXX.world.level.EntityBasedExplosionDamageCalculator
+ XXX.world.level.EntityGetter
- XXX.world.level.Explosion
+ XXX.world.level.Explosion$BlockInteraction
- XXX.world.level.ExplosionDamageCalculator
+ XXX.world.level.FoliageColor
- XXX.world.level.ForcedChunksSavedData
+ XXX.world.level.GameRules
- XXX.world.level.GameRules$BooleanValue
+ XXX.world.level.GameRules$Category
- XXX.world.level.GameRules$GameRuleTypeVisitor
+ XXX.world.level.GameRules$IntegerValue
- XXX.world.level.GameRules$Key
+ XXX.world.level.GameRules$Type
- XXX.world.level.GameRules$Value
+ XXX.world.level.GameRules$VisitorCaller
- XXX.world.level.GameType
+ XXX.world.level.GrassColor
- XXX.world.level.ItemLike
+ XXX.world.level.Level
- XXX.world.level.Level$1
+ XXX.world.level.Level$2
- XXX.world.level.Level$ExplosionInteraction
+ XXX.world.level.LevelAccessor
- XXX.world.level.LevelHeightAccessor
+ XXX.world.level.LevelHeightAccessor$1
- XXX.world.level.LevelReader
+ XXX.world.level.LevelSettings
+ XXX.world.level.LevelSimulatedReader
- XXX.world.level.LevelSimulatedRW
- XXX.world.level.LevelTimeAccess
+ XXX.world.level.LevelWriter
- XXX.world.level.LightLayer
+ XXX.world.level.LocalMobCapCalculator
- XXX.world.level.LocalMobCapCalculator$MobCounts
+ XXX.world.level.NaturalSpawner
- XXX.world.level.NaturalSpawner$1
+ XXX.world.level.NaturalSpawner$AfterSpawnCallback
- XXX.world.level.NaturalSpawner$ChunkGetter
+ XXX.world.level.NaturalSpawner$SpawnPredicate
- XXX.world.level.NaturalSpawner$SpawnState
+ XXX.world.level.NoiseColumn
- XXX.world.level.PathNavigationRegion
+ XXX.world.level.PotentialCalculator
- XXX.world.level.PotentialCalculator$PointCharge
+ XXX.world.level.ServerLevelAccessor
- XXX.world.level.SignalGetter
+ XXX.world.level.SpawnData
- XXX.world.level.SpawnData$CustomSpawnRules
+ XXX.world.level.StructureManager
- XXX.world.level.WorldDataConfiguration
+ XXX.world.level.WorldGenLevel
```

</details>
<details>
<summary>
Changes
</summary>

```
net.minecraft.SharedConstants +2P
```
```
XXX.minecraft.commands.CommandSourceStack +5M -2M | +1P
```
```
XXX.data.worldgen.ProcessorLists +1M | +3P -1P
```
```
XXX.minecraft.locale.Language +1M
```
```
XXX.network.chat.RemoteChatSession +1M
```
```
XXX.minecraft.server.ServerFunctionManager$ExecutionContext +1M | +1P
```
```
XXX.minecraft.sounds.SoundEvents +1P
```
```
XXX.minecraft.tags.BlockTags +2P
```
```
XXX.minecraft.tags.ItemTags +3P -1P
```
```
XXX.world.entity.Entity +4M -1M
```
```
XXX.village.poi.PoiManager +1M -1M
```
```
XXX.animal.sniffer.Sniffer +1M -1M | -1P
```
```
XXX.level.block.NoteBlock -1M
```
```
XXX.level.block.SculkCatalystBlock -2M | -1P
```
```
XXX.level.block.SculkShriekerBlock -1M
```
```
XXX.level.block.SoundType +1P
```
```
XXX.block.entity.AbstractFurnaceBlockEntity +1M -1M
```
```
XXX.block.entity.SculkCatalystBlockEntity +2M -7M | +1P -2P
```
```
XXX.block.state.BlockBehaviour$BlockStateBase +4M | +3P
```
```
XXX.block.state.BlockBehaviour$Properties +4M | +4P
```
```
XXX.state.properties.NoteBlockInstrument +1M -3M
```
```
XXX.state.properties.SculkSensorPhase +1P
```
```
XXX.level.chunk.DataLayer +3M | +1P
```
```
XXX.level.gameevent.EuclideanGameEventListenerRegistry +1M -1M | +2P
```

</details>
<details>
<summary>
net.minecraft.commands.CommandSourceStack
</summary>

```diff
- CommandSourceStack withReturnValueConsumer(IntConsumer)
+ CompletableFuture lambda$suggestRegistryElements$1(SharedSuggestionProvider$ElementSuggestionType,SuggestionsBuilder,Registry)
- CompletableFuture lambda$suggestRegistryElements$2(SharedSuggestionProvider$ElementSuggestionType,SuggestionsBuilder,Registry)
- IntConsumer getReturnValueConsumer()
- void <init>(CommandSource,Vec3,Vec2,ServerLevel,int,String,Component,MinecraftServer,Entity,boolean,ResultConsumer,EntityAnchorArgument$Anchor,CommandSigningContext,TaskChainer,IntConsumer)
+ void <init>(CommandSource,Vec3,Vec2,ServerLevel,int,String,Component,MinecraftServer,Entity,boolean,ResultConsumer,EntityAnchorArgument$Anchor,CommandSigningContext,TaskChainer)
- void lambda$new$1(int)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.ProcessorLists
</summary>

```diff
- CappedProcessor trailsArchyLootProcessor(ResourceLocation,int)
```

</details>
<details>
<summary>
net.minecraft.locale.Language
</summary>

```diff
- void parseTranslations(BiConsumer,String)
```

</details>
<details>
<summary>
net.minecraft.network.chat.RemoteChatSession
</summary>

```diff
- boolean hasExpired()
```

</details>
<details>
<summary>
net.minecraft.server.ServerFunctionManager$ExecutionContext
</summary>

```diff
- CommandSourceStack wrapSender(CommandSourceStack)
```

</details>
<details>
<summary>
net.minecraft.world.entity.Entity
</summary>

```diff
- boolean walkingOnBlock(boolean,Vec3)
+ void handleStepSounds(BlockPos,BlockState)
- void playMuffledStepSound(BlockState)
- void walkingStepSound(BlockPos,BlockState)
- void waterSwimSound()
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.village.poi.PoiManager
</summary>

```diff
+ void checkConsistencyWithBlocks(ChunkPos,LevelChunkSection)
- void checkConsistencyWithBlocks(SectionPos,LevelChunkSection)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.sniffer.Sniffer
</summary>

```diff
+ boolean canRide(Entity)
- boolean isSearching()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.NoteBlock
</summary>

```diff
+ NoteBlockInstrument lambda$setInstrument$0(LevelAccessor,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SculkCatalystBlock
</summary>

```diff
+ GameEventListener getListener(ServerLevel,BlockEntity)
+ void bloom(ServerLevel,BlockPos,BlockState,RandomSource)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SculkShriekerBlock
</summary>

```diff
+ GameEventListener getListener(ServerLevel,BlockEntity)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity
</summary>

```diff
- void awardUsedRecipes(Player,List)
+ void awardUsedRecipes(Player)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.SculkCatalystBlockEntity
</summary>

```diff
+ boolean handleGameEvent(ServerLevel,GameEvent,GameEvent$Context,Vec3)
- GameEventListener getListener()
+ GameEventListener$DeliveryMode getDeliveryMode()
+ int getListenerRadius()
+ Integer lambda$saveAdditional$0(SculkSpreader$ChargeCursor)
+ PositionSource getListenerSource()
- SculkCatalystBlockEntity$CatalystListener getListener()
+ SculkSpreader getSculkSpreader()
+ void tryAwardItSpreadsAdvancement(LivingEntity)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase
</summary>

```diff
- boolean blocksMotion()
- boolean calculateSolid()
- boolean isSolid()
- NoteBlockInstrument instrument()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.BlockBehaviour$Properties
</summary>

```diff
- BlockBehaviour$Properties forceSolidOff()
- BlockBehaviour$Properties forceSolidOn()
- BlockBehaviour$Properties instrument(NoteBlockInstrument)
- BlockBehaviour$Properties replaceable()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.properties.NoteBlockInstrument
</summary>

```diff
+ boolean requiresAirAbove()
- boolean worksAboveNoteBlock()
+ NoteBlockInstrument byStateBelow(BlockState)
+ Optional byStateAbove(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.DataLayer
</summary>

```diff
- boolean isDefinitelyFilledWith(int)
- boolean isDefinitelyHomogenous()
- byte packFilled(int)
```

</details>
<details>
<summary>
net.minecraft.world.level.gameevent.EuclideanGameEventListenerRegistry
</summary>

```diff
- void <init>(ServerLevel,int,EuclideanGameEventListenerRegistry$OnEmptyAction)
+ void <init>(ServerLevel)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
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
+ net.minecraft.Optionull
- net.minecraft.ReportedException
+ net.minecraft.ResourceLocationException
- net.minecraft.SharedConstants
+ net.minecraft.SystemReport
- net.minecraft.Util
+ net.minecraft.Util$1
- net.minecraft.Util$10
+ net.minecraft.Util$11
- net.minecraft.Util$2
+ net.minecraft.Util$5
- net.minecraft.Util$6
+ net.minecraft.Util$7
- net.minecraft.Util$8
+ net.minecraft.Util$9
- net.minecraft.Util$IdentityStrategy
+ net.minecraft.Util$OS
- net.minecraft.Util$OS$1
+ net.minecraft.Util$OS$2
- net.minecraft.WorldVersion
+ XXX.advancements.critereon.AbstractCriterionTriggerInstance
- XXX.advancements.critereon.BeeNestDestroyedTrigger
+ XXX.advancements.critereon.BeeNestDestroyedTrigger$TriggerInstance
- XXX.advancements.critereon.BlockPredicate
+ XXX.advancements.critereon.BlockPredicate$Builder
- XXX.advancements.critereon.BredAnimalsTrigger
+ XXX.advancements.critereon.BredAnimalsTrigger$TriggerInstance
- XXX.advancements.critereon.BrewedPotionTrigger
+ XXX.advancements.critereon.BrewedPotionTrigger$TriggerInstance
- XXX.advancements.critereon.ChangeDimensionTrigger
+ XXX.advancements.critereon.ChangeDimensionTrigger$TriggerInstance
- XXX.advancements.critereon.ChanneledLightningTrigger
+ XXX.advancements.critereon.ChanneledLightningTrigger$TriggerInstance
- XXX.advancements.critereon.ConstructBeaconTrigger
+ XXX.advancements.critereon.ConstructBeaconTrigger$TriggerInstance
- XXX.advancements.critereon.ConsumeItemTrigger
+ XXX.advancements.critereon.ConsumeItemTrigger$TriggerInstance
- XXX.advancements.critereon.CuredZombieVillagerTrigger
+ XXX.advancements.critereon.CuredZombieVillagerTrigger$TriggerInstance
- XXX.advancements.critereon.DamagePredicate
+ XXX.advancements.critereon.DamagePredicate$Builder
- XXX.advancements.critereon.DamageSourcePredicate
+ XXX.advancements.critereon.DamageSourcePredicate$Builder
- XXX.advancements.critereon.DeserializationContext
+ XXX.advancements.critereon.DistancePredicate
- XXX.advancements.critereon.DistanceTrigger
+ XXX.advancements.critereon.DistanceTrigger$TriggerInstance
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
- XXX.advancements.critereon.EntityPredicate$Builder
+ XXX.advancements.critereon.EntityPredicate$Composite
- XXX.advancements.critereon.EntitySubPredicate
+ XXX.advancements.critereon.EntitySubPredicate$1
- XXX.advancements.critereon.EntitySubPredicate$Type
+ XXX.advancements.critereon.EntitySubPredicate$Types
- XXX.advancements.critereon.EntityTypePredicate
+ XXX.advancements.critereon.EntityTypePredicate$1
- XXX.advancements.critereon.EntityTypePredicate$TagPredicate
+ XXX.advancements.critereon.EntityTypePredicate$TypePredicate
- XXX.advancements.critereon.EntityVariantPredicate
+ XXX.advancements.critereon.EntityVariantPredicate$1
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
+ XXX.advancements.critereon.ItemInteractWithBlockTrigger
- XXX.advancements.critereon.ItemInteractWithBlockTrigger$TriggerInstance
+ XXX.advancements.critereon.ItemPredicate
- XXX.advancements.critereon.ItemPredicate$Builder
+ XXX.advancements.critereon.KilledByCrossbowTrigger
- XXX.advancements.critereon.KilledByCrossbowTrigger$TriggerInstance
+ XXX.advancements.critereon.KilledTrigger
- XXX.advancements.critereon.KilledTrigger$TriggerInstance
+ XXX.advancements.critereon.LevitationTrigger
- XXX.advancements.critereon.LevitationTrigger$TriggerInstance
+ XXX.advancements.critereon.LighthingBoltPredicate
- XXX.advancements.critereon.LightningStrikeTrigger
+ XXX.advancements.critereon.LightningStrikeTrigger$TriggerInstance
+ XXX.advancements.critereon.LightPredicate
- XXX.advancements.critereon.LightPredicate$Builder
- XXX.advancements.critereon.LocationPredicate
+ XXX.advancements.critereon.LocationPredicate$Builder
- XXX.advancements.critereon.LootTableTrigger
+ XXX.advancements.critereon.LootTableTrigger$TriggerInstance
- XXX.advancements.critereon.MinMaxBounds
+ XXX.advancements.critereon.MinMaxBounds$BoundsFactory
- XXX.advancements.critereon.MinMaxBounds$BoundsFromReaderFactory
+ XXX.advancements.critereon.MinMaxBounds$Doubles
- XXX.advancements.critereon.MinMaxBounds$Ints
+ XXX.advancements.critereon.MobEffectsPredicate
- XXX.advancements.critereon.MobEffectsPredicate$MobEffectInstancePredicate
+ XXX.advancements.critereon.NbtPredicate
+ XXX.advancements.critereon.package-info
- XXX.advancements.critereon.PickedUpItemTrigger
+ XXX.advancements.critereon.PickedUpItemTrigger$TriggerInstance
- XXX.advancements.critereon.PlacedBlockTrigger
+ XXX.advancements.critereon.PlacedBlockTrigger$TriggerInstance
- XXX.advancements.critereon.PlayerHurtEntityTrigger
+ XXX.advancements.critereon.PlayerHurtEntityTrigger$TriggerInstance
- XXX.advancements.critereon.PlayerInteractTrigger
+ XXX.advancements.critereon.PlayerInteractTrigger$TriggerInstance
- XXX.advancements.critereon.PlayerPredicate
+ XXX.advancements.critereon.PlayerPredicate$AdvancementCriterionsPredicate
- XXX.advancements.critereon.PlayerPredicate$AdvancementDonePredicate
+ XXX.advancements.critereon.PlayerPredicate$AdvancementPredicate
- XXX.advancements.critereon.PlayerPredicate$Builder
+ XXX.advancements.critereon.PlayerTrigger
- XXX.advancements.critereon.PlayerTrigger$TriggerInstance
- XXX.advancements.critereon.RecipeCraftedTrigger$TriggerInstance
+ XXX.advancements.critereon.RecipeUnlockedTrigger
- XXX.advancements.critereon.RecipeUnlockedTrigger$TriggerInstance
+ XXX.advancements.critereon.SerializationContext
- XXX.advancements.critereon.ShotCrossbowTrigger
+ XXX.advancements.critereon.ShotCrossbowTrigger$TriggerInstance
- XXX.advancements.critereon.SimpleCriterionTrigger
+ XXX.advancements.critereon.SlideDownBlockTrigger
- XXX.advancements.critereon.SlideDownBlockTrigger$TriggerInstance
+ XXX.advancements.critereon.SlimePredicate
- XXX.advancements.critereon.StartRidingTrigger
+ XXX.advancements.critereon.StartRidingTrigger$TriggerInstance
- XXX.advancements.critereon.StatePropertiesPredicate
+ XXX.advancements.critereon.StatePropertiesPredicate$Builder
- XXX.advancements.critereon.StatePropertiesPredicate$ExactPropertyMatcher
+ XXX.advancements.critereon.StatePropertiesPredicate$PropertyMatcher
- XXX.advancements.critereon.StatePropertiesPredicate$RangedPropertyMatcher
+ XXX.advancements.critereon.SummonedEntityTrigger
- XXX.advancements.critereon.SummonedEntityTrigger$TriggerInstance
+ XXX.advancements.critereon.TagPredicate
- XXX.advancements.critereon.TameAnimalTrigger
+ XXX.advancements.critereon.TameAnimalTrigger$TriggerInstance
- XXX.advancements.critereon.TargetBlockTrigger
+ XXX.advancements.critereon.TargetBlockTrigger$TriggerInstance
- XXX.advancements.critereon.TradeTrigger
+ XXX.advancements.critereon.TradeTrigger$TriggerInstance
- XXX.advancements.critereon.UsedEnderEyeTrigger
+ XXX.advancements.critereon.UsedEnderEyeTrigger$TriggerInstance
- XXX.advancements.critereon.UsedTotemTrigger
+ XXX.advancements.critereon.UsedTotemTrigger$TriggerInstance
- XXX.advancements.critereon.UsingItemTrigger
+ XXX.advancements.critereon.UsingItemTrigger$TriggerInstance
- XXX.advancements.critereon.WrappedMinMaxBounds
+ XXX.animal.allay.Allay$AllayVibrationListenerConfig
- XXX.animal.allay.Allay$JukeboxListener
- XXX.animation.definitions.CamelAnimation
+ XXX.animation.definitions.FrogAnimation
- XXX.animation.definitions.package-info
- XXX.animation.definitions.SnifferAnimation
+ XXX.animation.definitions.WardenAnimation
- XXX.blaze3d.platform.IconSet
+ XXX.blaze3d.platform.InputConstants
- XXX.blaze3d.platform.InputConstants$Key
+ XXX.blaze3d.platform.InputConstants$Type
- XXX.blaze3d.platform.Lighting
+ XXX.blaze3d.platform.MacosUtil
- XXX.blaze3d.platform.MemoryTracker
+ XXX.blaze3d.platform.Monitor
- XXX.blaze3d.platform.MonitorCreator
+ XXX.blaze3d.platform.NativeImage
- XXX.blaze3d.platform.NativeImage$Format
+ XXX.blaze3d.platform.NativeImage$InternalGlFormat
- XXX.blaze3d.platform.NativeImage$WriteCallback
+ XXX.blaze3d.platform.package-info
+ XXX.blaze3d.platform.ScreenManager
- XXX.blaze3d.platform.TextureUtil
+ XXX.blaze3d.platform.VideoMode
- XXX.blaze3d.platform.Window
+ XXX.blaze3d.platform.Window$WindowInitFailed
- XXX.blaze3d.platform.WindowEventHandler
- XXX.blaze3d.preprocessor.GlslPreprocessor
+ XXX.blaze3d.preprocessor.GlslPreprocessor$Context
- XXX.blaze3d.preprocessor.package-info
+ XXX.blaze3d.shaders.AbstractUniform
- XXX.blaze3d.shaders.BlendMode
+ XXX.blaze3d.shaders.Effect
- XXX.blaze3d.shaders.EffectProgram
+ XXX.blaze3d.shaders.EffectProgram$1
- XXX.blaze3d.shaders.FogShape
- XXX.blaze3d.shaders.package-info
+ XXX.blaze3d.shaders.Program
- XXX.blaze3d.shaders.Program$Type
+ XXX.blaze3d.shaders.ProgramManager
- XXX.blaze3d.shaders.Shader
+ XXX.blaze3d.shaders.Uniform
- XXX.blaze3d.systems.package-info
+ XXX.blaze3d.systems.RenderSystem
- XXX.blaze3d.systems.RenderSystem$1
+ XXX.blaze3d.systems.RenderSystem$AutoStorageIndexBuffer
- XXX.blaze3d.systems.RenderSystem$AutoStorageIndexBuffer$IndexGenerator
+ XXX.blaze3d.systems.TimerQuery
- XXX.blaze3d.systems.TimerQuery$FrameProfile
+ XXX.blaze3d.systems.TimerQuery$TimerQueryLazyLoader
+ XXX.blaze3d.vertex.BufferBuilder
- XXX.blaze3d.vertex.BufferBuilder$1
+ XXX.blaze3d.vertex.BufferBuilder$DrawState
- XXX.blaze3d.vertex.BufferBuilder$RenderedBuffer
+ XXX.blaze3d.vertex.BufferBuilder$SortState
- XXX.blaze3d.vertex.BufferUploader
+ XXX.blaze3d.vertex.BufferVertexConsumer
+ XXX.blaze3d.vertex.DefaultedVertexConsumer
- XXX.blaze3d.vertex.DefaultVertexFormat
- XXX.blaze3d.vertex.package-info
- XXX.blaze3d.vertex.PoseStack
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
+ XXX.blaze3d.vertex.VertexMultiConsumer$Multiple
- XXX.blaze3d.vertex.VertexSorting
+ XXX.blaze3d.vertex.VertexSorting$DistanceFunction
+ XXX.block.entity.CalibratedSculkSensorBlockEntity$VibrationConfig
- XXX.block.entity.CalibratedSculkSensorBlockEntity$VibrationUser
- XXX.block.entity.SculkSensorBlockEntity
+ XXX.block.entity.SculkSensorBlockEntity$VibrationConfig
- XXX.block.entity.SculkShriekerBlockEntity
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
+ XXX.block.model.ItemOverrides$BakedOverride
- XXX.block.model.ItemOverrides$PropertyMatcher
+ XXX.block.model.ItemTransform
- XXX.block.model.ItemTransform$Deserializer
+ XXX.block.model.ItemTransforms
- XXX.block.model.ItemTransforms$1
+ XXX.block.model.ItemTransforms$Deserializer
- XXX.block.model.MultiVariant
+ XXX.block.model.MultiVariant$Deserializer
+ XXX.block.model.package-info
- XXX.block.model.Variant
+ XXX.block.model.Variant$Deserializer
- XXX.chat.report.AbuseReportSender
+ XXX.chat.report.AbuseReportSender$1
- XXX.chat.report.AbuseReportSender$SendException
+ XXX.chat.report.AbuseReportSender$Services
- XXX.chat.report.BanReason
+ XXX.chat.report.ChatReportBuilder
- XXX.chat.report.ChatReportBuilder$CannotBuildReason
+ XXX.chat.report.ChatReportBuilder$ChatReport
- XXX.chat.report.ChatReportBuilder$Result
+ XXX.chat.report.ChatReportContextBuilder
- XXX.chat.report.ChatReportContextBuilder$Collector
+ XXX.chat.report.ChatReportContextBuilder$Handler
- XXX.chat.report.package-info
- XXX.chat.report.ReportEnvironment
+ XXX.chat.report.ReportEnvironment$Server
- XXX.chat.report.ReportEnvironment$Server$Realm
+ XXX.chat.report.ReportEnvironment$Server$ThirdParty
+ XXX.chat.report.ReportingContext
- XXX.chat.report.ReportReason
+ XXX.client.animation.AnimationChannel
- XXX.client.animation.AnimationChannel$Interpolation
+ XXX.client.animation.AnimationChannel$Interpolations
- XXX.client.animation.AnimationChannel$Target
+ XXX.client.animation.AnimationChannel$Targets
- XXX.client.animation.AnimationDefinition
+ XXX.client.animation.AnimationDefinition$Builder
- XXX.client.animation.Keyframe
+ XXX.client.animation.KeyframeAnimations
+ XXX.client.animation.package-info
+ XXX.client.gui.ComponentPath
- XXX.client.gui.ComponentPath$Leaf
+ XXX.client.gui.ComponentPath$Path
- XXX.client.gui.Font
+ XXX.client.gui.Font$DisplayMode
- XXX.client.gui.Font$StringRenderOutput
+ XXX.client.gui.Gui
- XXX.client.gui.Gui$HeartType
+ XXX.client.gui.GuiComponent
- XXX.client.gui.GuiGraphics$ScissorStack
+ XXX.client.gui.MapRenderer
- XXX.client.gui.MapRenderer$MapInstance
- XXX.client.main.GameConfig
+ XXX.client.main.GameConfig$FolderData
- XXX.client.main.GameConfig$GameData
+ XXX.client.main.GameConfig$QuickPlayData
- XXX.client.main.GameConfig$UserData
+ XXX.client.main.Main
- XXX.client.main.Main$1
+ XXX.client.main.Main$2
- XXX.client.main.Main$3
- XXX.client.main.package-info
+ XXX.client.main.SilentInitException
+ XXX.client.model.AbstractZombieModel
- XXX.client.model.AgeableHierarchicalModel
+ XXX.client.model.AgeableListModel
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
+ XXX.client.model.CamelModel
- XXX.client.model.CatModel
+ XXX.client.model.ChestBoatModel
+ XXX.client.model.ChestedHorseModel
- XXX.client.model.ChestRaftModel
- XXX.client.model.ChickenModel
+ XXX.client.model.CodModel
- XXX.client.model.ColorableAgeableListModel
+ XXX.client.model.ColorableHierarchicalModel
- XXX.client.model.CowModel
+ XXX.client.model.CreeperModel
- XXX.client.model.DolphinModel
+ XXX.client.model.DrownedModel
- XXX.client.model.ElytraModel
+ XXX.client.model.EndermanModel
- XXX.client.model.EndermiteModel
+ XXX.client.model.EntityModel
- XXX.client.model.EvokerFangsModel
+ XXX.client.model.FoxModel
- XXX.client.model.FrogModel
+ XXX.client.model.GhastModel
- XXX.client.model.GiantZombieModel
+ XXX.client.model.GoatModel
- XXX.client.model.GuardianModel
+ XXX.client.model.HeadedModel
- XXX.client.model.HierarchicalModel
+ XXX.client.model.HoglinModel
- XXX.client.model.HorseModel
+ XXX.client.model.HumanoidArmorModel
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
- XXX.client.model.PiglinHeadModel
+ XXX.client.model.PiglinModel
+ XXX.client.model.PigModel
- XXX.client.model.PlayerModel
+ XXX.client.model.PolarBearModel
- XXX.client.model.PufferfishBigModel
+ XXX.client.model.PufferfishMidModel
- XXX.client.model.PufferfishSmallModel
+ XXX.client.model.QuadrupedModel
- XXX.client.model.RabbitModel
+ XXX.client.model.RaftModel
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
- XXX.client.model.SnifferModel
+ XXX.client.model.SnowGolemModel
- XXX.client.model.SpiderModel
+ XXX.client.model.SquidModel
- XXX.client.model.StriderModel
+ XXX.client.model.TadpoleModel
- XXX.client.model.TridentModel
+ XXX.client.model.TropicalFishModelA
- XXX.client.model.TropicalFishModelB
+ XXX.client.model.TurtleModel
- XXX.client.model.VexModel
+ XXX.client.model.VillagerHeadModel
- XXX.client.model.VillagerModel
+ XXX.client.model.WardenModel
- XXX.client.model.WaterPatchModel
+ XXX.client.model.WitchModel
- XXX.client.model.WitherBossModel
+ XXX.client.model.WolfModel
- XXX.client.model.ZombieModel
+ XXX.client.model.ZombieVillagerModel
- XXX.client.multiplayer.AccountProfileKeyPairManager
+ XXX.client.multiplayer.ClientAdvancements
- XXX.client.multiplayer.ClientAdvancements$Listener
+ XXX.client.multiplayer.ClientChunkCache
- XXX.client.multiplayer.ClientChunkCache$Storage
+ XXX.client.multiplayer.ClientHandshakePacketListenerImpl
- XXX.client.multiplayer.ClientLevel
+ XXX.client.multiplayer.ClientLevel$1
- XXX.client.multiplayer.ClientLevel$ClientLevelData
+ XXX.client.multiplayer.ClientLevel$EntityCallbacks
- XXX.client.multiplayer.ClientPacketListener
+ XXX.client.multiplayer.ClientPacketListener$1
- XXX.client.multiplayer.ClientPacketListener$DeferredPacket
+ XXX.client.multiplayer.ClientRegistryLayer
- XXX.client.multiplayer.ClientSuggestionProvider
+ XXX.client.multiplayer.ClientSuggestionProvider$1
- XXX.client.multiplayer.MultiPlayerGameMode
+ XXX.client.multiplayer.package-info
+ XXX.client.multiplayer.PlayerInfo
- XXX.client.multiplayer.ProfileKeyPairManager
+ XXX.client.multiplayer.ProfileKeyPairManager$1
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
- XXX.client.particle.CherryParticle
+ XXX.client.particle.CritParticle
- XXX.client.particle.CritParticle$DamageIndicatorProvider
+ XXX.client.particle.CritParticle$MagicProvider
- XXX.client.particle.CritParticle$Provider
+ XXX.client.particle.DragonBreathParticle
- XXX.client.particle.DragonBreathParticle$Provider
+ XXX.client.particle.DripParticle
- XXX.client.particle.DripParticle$CoolingDripHangParticle
+ XXX.client.particle.DripParticle$DripHangParticle
- XXX.client.particle.DripParticle$DripLandParticle
+ XXX.client.particle.DripParticle$DripstoneFallAndLandParticle
- XXX.client.particle.DripParticle$FallAndLandParticle
+ XXX.client.particle.DripParticle$FallingParticle
- XXX.client.particle.DripParticle$HoneyFallAndLandParticle
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
- XXX.client.particle.GlowParticle$ElectricSparkProvider
+ XXX.client.particle.GlowParticle$GlowSquidProvider
- XXX.client.particle.GlowParticle$ScrapeProvider
+ XXX.client.particle.GlowParticle$WaxOffProvider
- XXX.client.particle.GlowParticle$WaxOnProvider
+ XXX.client.particle.HeartParticle
- XXX.client.particle.HeartParticle$AngryVillagerProvider
+ XXX.client.particle.HeartParticle$Provider
- XXX.client.particle.HugeExplosionParticle
+ XXX.client.particle.HugeExplosionParticle$Provider
- XXX.client.particle.HugeExplosionSeedParticle
+ XXX.client.particle.HugeExplosionSeedParticle$Provider
- XXX.client.particle.ItemPickupParticle
+ XXX.client.particle.LargeSmokeParticle
- XXX.client.particle.LargeSmokeParticle$Provider
+ XXX.client.particle.LavaParticle
- XXX.client.particle.LavaParticle$Provider
+ XXX.client.particle.MobAppearanceParticle
- XXX.client.particle.MobAppearanceParticle$Provider
+ XXX.client.particle.NoRenderParticle
- XXX.client.particle.NoteParticle
+ XXX.client.particle.NoteParticle$Provider
- XXX.client.particle.package-info
- XXX.client.particle.Particle
+ XXX.client.particle.ParticleDescription
- XXX.client.particle.ParticleEngine
+ XXX.client.particle.ParticleEngine$1ParticleDefinition
- XXX.client.particle.ParticleEngine$MutableSpriteSet
+ XXX.client.particle.ParticleEngine$SpriteParticleRegistration
- XXX.client.particle.ParticleProvider
+ XXX.client.particle.ParticleProvider$Sprite
- XXX.client.particle.ParticleRenderType
+ XXX.client.particle.ParticleRenderType$1
- XXX.client.particle.ParticleRenderType$2
+ XXX.client.particle.ParticleRenderType$3
- XXX.client.particle.ParticleRenderType$4
+ XXX.client.particle.ParticleRenderType$5
- XXX.client.particle.ParticleRenderType$6
+ XXX.client.particle.PlayerCloudParticle
- XXX.client.particle.PlayerCloudParticle$Provider
+ XXX.client.particle.PlayerCloudParticle$SneezeProvider
- XXX.client.particle.PortalParticle
+ XXX.client.particle.PortalParticle$Provider
- XXX.client.particle.ReversePortalParticle
+ XXX.client.particle.ReversePortalParticle$ReversePortalProvider
- XXX.client.particle.RisingParticle
+ XXX.client.particle.SculkChargeParticle
- XXX.client.particle.SculkChargeParticle$Provider
+ XXX.client.particle.SculkChargePopParticle
- XXX.client.particle.SculkChargePopParticle$Provider
+ XXX.client.particle.ShriekParticle
- XXX.client.particle.ShriekParticle$Provider
+ XXX.client.particle.SimpleAnimatedParticle
- XXX.client.particle.SingleQuadParticle
+ XXX.client.particle.SmokeParticle
- XXX.client.particle.SmokeParticle$Provider
+ XXX.client.particle.SnowflakeParticle
- XXX.client.particle.SnowflakeParticle$Provider
+ XXX.client.particle.SonicBoomParticle
- XXX.client.particle.SonicBoomParticle$Provider
+ XXX.client.particle.SoulParticle
- XXX.client.particle.SoulParticle$EmissiveProvider
+ XXX.client.particle.SoulParticle$Provider
- XXX.client.particle.SpellParticle
+ XXX.client.particle.SpellParticle$AmbientMobProvider
- XXX.client.particle.SpellParticle$InstantProvider
+ XXX.client.particle.SpellParticle$MobProvider
- XXX.client.particle.SpellParticle$Provider
+ XXX.client.particle.SpellParticle$WitchProvider
- XXX.client.particle.SpitParticle
+ XXX.client.particle.SpitParticle$Provider
- XXX.client.particle.SplashParticle
+ XXX.client.particle.SplashParticle$Provider
- XXX.client.particle.SpriteSet
+ XXX.client.particle.SquidInkParticle
- XXX.client.particle.SquidInkParticle$GlowInkProvider
+ XXX.client.particle.SquidInkParticle$Provider
- XXX.client.particle.SuspendedParticle
+ XXX.client.particle.SuspendedParticle$CrimsonSporeProvider
- XXX.client.particle.SuspendedParticle$SporeBlossomAirProvider
+ XXX.client.particle.SuspendedParticle$SporeBlossomAirProvider$1
- XXX.client.particle.SuspendedParticle$UnderwaterProvider
+ XXX.client.particle.SuspendedParticle$WarpedSporeProvider
- XXX.client.particle.SuspendedTownParticle
+ XXX.client.particle.SuspendedTownParticle$ComposterFillProvider
- XXX.client.particle.SuspendedTownParticle$DolphinSpeedProvider
+ XXX.client.particle.SuspendedTownParticle$EggCrackProvider
- XXX.client.particle.SuspendedTownParticle$HappyVillagerProvider
+ XXX.client.particle.SuspendedTownParticle$Provider
- XXX.client.particle.TerrainParticle
+ XXX.client.particle.TerrainParticle$Provider
- XXX.client.particle.TextureSheetParticle
+ XXX.client.particle.TotemParticle
- XXX.client.particle.TotemParticle$Provider
+ XXX.client.particle.TrackingEmitter
- XXX.client.particle.VibrationSignalParticle
+ XXX.client.particle.VibrationSignalParticle$Provider
- XXX.client.particle.WakeParticle
+ XXX.client.particle.WakeParticle$Provider
- XXX.client.particle.WaterCurrentDownParticle
+ XXX.client.particle.WaterCurrentDownParticle$Provider
- XXX.client.particle.WaterDropParticle
+ XXX.client.particle.WaterDropParticle$Provider
- XXX.client.particle.WhiteAshParticle
+ XXX.client.particle.WhiteAshParticle$Provider
+ XXX.client.player.AbstractClientPlayer
- XXX.client.player.Input
+ XXX.client.player.KeyboardInput
- XXX.client.player.LocalPlayer
- XXX.client.player.package-info
+ XXX.client.player.RemotePlayer
+ XXX.client.profiling.ClientMetricsSamplersProvider
- XXX.client.profiling.package-info
+ XXX.client.quickplay.package-info
+ XXX.client.quickplay.QuickPlay
- XXX.client.quickplay.QuickPlayLog
+ XXX.client.quickplay.QuickPlayLog$1
- XXX.client.quickplay.QuickPlayLog$QuickPlayEntry
+ XXX.client.quickplay.QuickPlayLog$QuickPlayWorld
- XXX.client.quickplay.QuickPlayLog$Type
- XXX.client.renderer.BiomeColors
+ XXX.client.renderer.BlockEntityWithoutLevelRenderer
- XXX.client.renderer.ChunkBufferBuilderPack
+ XXX.client.renderer.CubeMap
- XXX.client.renderer.DimensionSpecialEffects
+ XXX.client.renderer.DimensionSpecialEffects$EndEffects
- XXX.client.renderer.DimensionSpecialEffects$NetherEffects
+ XXX.client.renderer.DimensionSpecialEffects$OverworldEffects
- XXX.client.renderer.DimensionSpecialEffects$SkyType
+ XXX.client.renderer.EffectInstance
- XXX.client.renderer.FaceInfo
+ XXX.client.renderer.FaceInfo$Constants
- XXX.client.renderer.FaceInfo$VertexInfo
+ XXX.client.renderer.FogRenderer
- XXX.client.renderer.FogRenderer$BlindnessFogFunction
+ XXX.client.renderer.FogRenderer$DarknessFogFunction
- XXX.client.renderer.FogRenderer$FogData
+ XXX.client.renderer.FogRenderer$FogMode
- XXX.client.renderer.FogRenderer$MobEffectFogFunction
+ XXX.client.renderer.GameRenderer
- XXX.client.renderer.GameRenderer$1
+ XXX.client.renderer.GameRenderer$ResourceCache
- XXX.client.renderer.GpuWarnlistManager
+ XXX.client.renderer.GpuWarnlistManager$Preparations
- XXX.client.renderer.ItemBlockRenderTypes
+ XXX.client.renderer.ItemInHandRenderer
- XXX.client.renderer.ItemInHandRenderer$1
+ XXX.client.renderer.ItemInHandRenderer$HandRenderSelection
- XXX.client.renderer.ItemModelShaper
+ XXX.client.renderer.LevelRenderer
- XXX.client.renderer.LevelRenderer$RenderChunkInfo
+ XXX.client.renderer.LevelRenderer$RenderChunkStorage
- XXX.client.renderer.LevelRenderer$RenderInfoMap
+ XXX.client.renderer.LevelRenderer$TransparencyShaderException
- XXX.client.renderer.LightTexture
+ XXX.client.renderer.MultiBufferSource
- XXX.client.renderer.MultiBufferSource$BufferSource
+ XXX.client.renderer.OutlineBufferSource
- XXX.client.renderer.OutlineBufferSource$EntityOutlineGenerator
+ XXX.client.renderer.PanoramaRenderer
- XXX.client.renderer.PostChain
+ XXX.client.renderer.PostPass
- XXX.client.renderer.Rect2i
+ XXX.client.renderer.RenderBuffers
- XXX.client.renderer.RenderStateShard
+ XXX.client.renderer.RenderStateShard$BooleanStateShard
- XXX.client.renderer.RenderStateShard$CullStateShard
+ XXX.client.renderer.RenderStateShard$DepthTestStateShard
- XXX.client.renderer.RenderStateShard$EmptyTextureStateShard
+ XXX.client.renderer.RenderStateShard$LayeringStateShard
- XXX.client.renderer.RenderStateShard$LightmapStateShard
+ XXX.client.renderer.RenderStateShard$LineStateShard
- XXX.client.renderer.RenderStateShard$MultiTextureStateShard
+ XXX.client.renderer.RenderStateShard$MultiTextureStateShard$Builder
- XXX.client.renderer.RenderStateShard$OffsetTexturingStateShard
+ XXX.client.renderer.RenderStateShard$OutputStateShard
- XXX.client.renderer.RenderStateShard$OverlayStateShard
+ XXX.client.renderer.RenderStateShard$ShaderStateShard
- XXX.client.renderer.RenderStateShard$TextureStateShard
+ XXX.client.renderer.RenderStateShard$TexturingStateShard
- XXX.client.renderer.RenderStateShard$TransparencyStateShard
+ XXX.client.renderer.RenderStateShard$WriteMaskStateShard
- XXX.client.renderer.RenderType
+ XXX.client.renderer.RenderType$CompositeRenderType
- XXX.client.renderer.RenderType$CompositeState
+ XXX.client.renderer.RenderType$CompositeState$CompositeStateBuilder
- XXX.client.renderer.RenderType$OutlineProperty
+ XXX.client.renderer.RunningTrimmedMean
- XXX.client.renderer.ScreenEffectRenderer
+ XXX.client.renderer.ShaderInstance
- XXX.client.renderer.ShaderInstance$1
+ XXX.client.renderer.Sheets
- XXX.client.renderer.Sheets$1
+ XXX.client.renderer.SpriteCoordinateExpander
- XXX.client.renderer.ViewArea
+ XXX.client.renderer.VirtualScreen
- XXX.color.block.BlockColor
+ XXX.color.block.BlockColors
- XXX.color.block.BlockTintCache
+ XXX.color.block.BlockTintCache$CacheData
- XXX.color.block.BlockTintCache$LatestCacheInfo
+ XXX.color.block.package-info
- XXX.color.item.ItemColor
+ XXX.color.item.ItemColors
- XXX.color.item.package-info
- XXX.datafix.fixes.DecoratedPotFieldRenameFix
+ XXX.datafix.fixes.DyeItemRenameFix
- XXX.datafix.fixes.EffectDurationFix
+ XXX.datafix.fixes.EntityArmorStandSilentFix
- XXX.datafix.fixes.EntityBlockStateFix
+ XXX.datafix.fixes.EntityBrushableBlockFieldsRenameFix
- XXX.datafix.fixes.EntityCatSplitFix
+ XXX.datafix.fixes.EntityCodSalmonFix
- XXX.datafix.fixes.EntityCustomNameToComponentFix
+ XXX.datafix.fixes.EntityElderGuardianSplitFix
- XXX.datafix.fixes.EntityEquipmentToArmorAndHandFix
+ XXX.datafix.fixes.EntityGoatMissingStateFix
- XXX.datafix.fixes.EntityHealthFix
+ XXX.datafix.fixes.EntityHorseSaddleFix
- XXX.datafix.fixes.EntityHorseSplitFix
+ XXX.datafix.fixes.EntityIdFix
- XXX.datafix.fixes.EntityItemFrameDirectionFix
+ XXX.datafix.fixes.EntityMinecartIdentifiersFix
- XXX.datafix.fixes.EntityPaintingFieldsRenameFix
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
- XXX.datafix.fixes.EntityVariantFix
+ XXX.datafix.fixes.EntityWolfColorFix
- XXX.datafix.fixes.EntityZombieSplitFix
+ XXX.datafix.fixes.EntityZombieVillagerTypeFix
- XXX.datafix.fixes.EntityZombifiedPiglinRenameFix
+ XXX.datafix.fixes.FeatureFlagRemoveFix
- XXX.datafix.fixes.FilteredBooksFix
+ XXX.datafix.fixes.FilteredSignsFix
- XXX.datafix.fixes.ForcePoiRebuild
+ XXX.datafix.fixes.FurnaceRecipeFix
- XXX.datafix.fixes.GoatHornIdFix
+ XXX.datafix.fixes.GossipUUIDFix
- XXX.datafix.fixes.HeightmapRenamingFix
+ XXX.datafix.fixes.IglooMetadataRemovalFix
- XXX.datafix.fixes.ItemBannerColorFix
+ XXX.datafix.fixes.ItemCustomNameToComponentFix
- XXX.datafix.fixes.ItemIdFix
+ XXX.datafix.fixes.ItemLoreFix
- XXX.datafix.fixes.ItemPotionFix
+ XXX.datafix.fixes.ItemRemoveBlockEntityTagFix
- XXX.datafix.fixes.ItemRenameFix
+ XXX.datafix.fixes.ItemRenameFix$1
- XXX.datafix.fixes.ItemShulkerBoxColorFix
+ XXX.datafix.fixes.ItemSpawnEggFix
- XXX.datafix.fixes.ItemStackEnchantmentNamesFix
+ XXX.datafix.fixes.ItemStackMapIdFix
- XXX.datafix.fixes.ItemStackSpawnEggFix
+ XXX.datafix.fixes.ItemStackTagFix
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
+ XXX.datafix.fixes.NamespacedTypeRenameFix
- XXX.datafix.fixes.NewVillageFix
+ XXX.datafix.fixes.ObjectiveDisplayNameFix
- XXX.datafix.fixes.ObjectiveRenderTypeFix
+ XXX.datafix.fixes.OminousBannerBlockEntityRenameFix
- XXX.datafix.fixes.OminousBannerRenameFix
+ XXX.datafix.fixes.OptionsAccessibilityOnboardFix
- XXX.datafix.fixes.OptionsAddTextBackgroundFix
+ XXX.datafix.fixes.OptionsAmbientOcclusionFix
- XXX.datafix.fixes.OptionsForceVBOFix
+ XXX.datafix.fixes.OptionsKeyLwjgl3Fix
- XXX.datafix.fixes.OptionsKeyTranslationFix
+ XXX.datafix.fixes.OptionsLowerCaseLanguageFix
- XXX.datafix.fixes.OptionsProgrammerArtFix
+ XXX.datafix.fixes.OptionsRenameFieldFix
- XXX.datafix.fixes.OverreachingTickFix
+ XXX.datafix.fixes.package-info
+ XXX.datafix.fixes.PlayerUUIDFix
- XXX.datafix.fixes.PoiTypeRemoveFix
+ XXX.datafix.fixes.PoiTypeRenameFix
- XXX.datafix.fixes.RecipesFix
+ XXX.datafix.fixes.RecipesRenameningFix
- XXX.datafix.fixes.RedstoneWireConnectionsFix
+ XXX.datafix.fixes.References
- XXX.datafix.fixes.RemapChunkStatusFix
+ XXX.datafix.fixes.SimpleEntityRenameFix
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
- XXX.datafix.fixes.VariantRenameFix
+ XXX.datafix.fixes.VillagerDataFix
- XXX.datafix.fixes.VillagerFollowRangeFix
+ XXX.datafix.fixes.VillagerRebuildLevelAndXpFix
- XXX.datafix.fixes.VillagerTradeFix
+ XXX.datafix.fixes.WallPropertyFix
- XXX.datafix.fixes.WeaponSmithChestLootTableFix
+ XXX.datafix.fixes.WorldGenSettingsDisallowOldCustomWorldsFix
- XXX.datafix.fixes.WorldGenSettingsFix
+ XXX.datafix.fixes.WorldGenSettingsFix$StructureFeatureConfiguration
- XXX.datafix.fixes.WorldGenSettingsHeightAndBiomeFix
+ XXX.datafix.fixes.WriteAndReadFix
- XXX.datafix.fixes.ZombieVillagerRebuildXpFix
+ XXX.datafix.schemas.NamespacedSchema
- XXX.datafix.schemas.NamespacedSchema$1
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
- XXX.datafix.schemas.V1451_6$1
+ XXX.datafix.schemas.V1451_6$2
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
+ XXX.datafix.schemas.V3202
- XXX.datafix.schemas.V3203
+ XXX.datafix.schemas.V3204
- XXX.datafix.schemas.V3325
+ XXX.datafix.schemas.V3326
- XXX.datafix.schemas.V3327
+ XXX.datafix.schemas.V3328
- XXX.datafix.schemas.V3438
+ XXX.entity.npc.AbstractVillager
- XXX.entity.npc.CatSpawner
+ XXX.entity.npc.ClientSideMerchant
- XXX.entity.npc.InventoryCarrier
+ XXX.entity.npc.Npc
- XXX.entity.npc.package-info
- XXX.entity.npc.Villager
+ XXX.entity.npc.VillagerData
- XXX.entity.npc.VillagerDataHolder
+ XXX.entity.npc.VillagerProfession
- XXX.entity.npc.VillagerTrades
+ XXX.entity.npc.VillagerTrades$DyedArmorForEmeralds
- XXX.entity.npc.VillagerTrades$EmeraldForItems
+ XXX.entity.npc.VillagerTrades$EmeraldsForVillagerTypeItem
- XXX.entity.npc.VillagerTrades$EnchantBookForEmeralds
+ XXX.entity.npc.VillagerTrades$EnchantedItemForEmeralds
- XXX.entity.npc.VillagerTrades$ItemListing
+ XXX.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
- XXX.entity.npc.VillagerTrades$ItemsForEmeralds
+ XXX.entity.npc.VillagerTrades$SuspiciousStewForEmerald
- XXX.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
+ XXX.entity.npc.VillagerTrades$TreasureMapForEmeralds
- XXX.entity.npc.VillagerType
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
+ XXX.entity.player.ProfileKeyPair
- XXX.entity.player.ProfilePublicKey
+ XXX.entity.player.ProfilePublicKey$Data
- XXX.entity.player.ProfilePublicKey$ValidationException
+ XXX.entity.player.StackedContents
- XXX.entity.player.StackedContents$RecipePicker
- XXX.entity.projectile.AbstractArrow
+ XXX.entity.projectile.AbstractArrow$1
- XXX.entity.projectile.AbstractArrow$Pickup
+ XXX.entity.projectile.AbstractHurtingProjectile
- XXX.entity.projectile.Arrow
+ XXX.entity.projectile.DragonFireball
- XXX.entity.projectile.EvokerFangs
+ XXX.entity.projectile.EyeOfEnder
- XXX.entity.projectile.Fireball
+ XXX.entity.projectile.FireworkRocketEntity
- XXX.entity.projectile.FishingHook
+ XXX.entity.projectile.FishingHook$1
- XXX.entity.projectile.FishingHook$FishHookState
+ XXX.entity.projectile.FishingHook$OpenWaterType
- XXX.entity.projectile.ItemSupplier
+ XXX.entity.projectile.LargeFireball
- XXX.entity.projectile.LlamaSpit
+ XXX.entity.projectile.package-info
+ XXX.entity.projectile.Projectile
- XXX.entity.projectile.ProjectileUtil
+ XXX.entity.projectile.ShulkerBullet
- XXX.entity.projectile.SmallFireball
+ XXX.entity.projectile.Snowball
- XXX.entity.projectile.SpectralArrow
+ XXX.entity.projectile.ThrowableItemProjectile
- XXX.entity.projectile.ThrowableProjectile
+ XXX.entity.projectile.ThrownEgg
- XXX.entity.projectile.ThrownEnderpearl
+ XXX.entity.projectile.ThrownExperienceBottle
- XXX.entity.projectile.ThrownPotion
+ XXX.entity.projectile.ThrownTrident
- XXX.entity.projectile.WitherSkull
- XXX.entity.raid.package-info
- XXX.entity.raid.Raid
+ XXX.entity.raid.Raid$1
+ XXX.entity.raid.Raid$RaiderType
- XXX.entity.raid.Raid$RaidStatus
- XXX.entity.raid.Raider
+ XXX.entity.raid.Raider$HoldGroundAttackGoal
- XXX.entity.raid.Raider$ObtainRaidLeaderBannerGoal
+ XXX.entity.raid.Raider$RaiderCelebration
- XXX.entity.raid.Raider$RaiderMoveThroughVillageGoal
+ XXX.entity.raid.Raids
+ XXX.entity.schedule.Activity
- XXX.entity.schedule.Keyframe
+ XXX.entity.schedule.package-info
+ XXX.entity.schedule.Schedule
- XXX.entity.schedule.ScheduleBuilder
+ XXX.entity.schedule.ScheduleBuilder$ActivityTransition
- XXX.entity.schedule.Timeline
- XXX.entity.vehicle.AbstractMinecart
+ XXX.entity.vehicle.AbstractMinecart$1
- XXX.entity.vehicle.AbstractMinecart$Type
+ XXX.entity.vehicle.AbstractMinecartContainer
- XXX.entity.vehicle.Boat
+ XXX.entity.vehicle.Boat$1
- XXX.entity.vehicle.Boat$Status
+ XXX.entity.vehicle.Boat$Type
- XXX.entity.vehicle.ChestBoat
+ XXX.entity.vehicle.ChestBoat$1
- XXX.entity.vehicle.ContainerEntity
+ XXX.entity.vehicle.ContainerEntity$1
- XXX.entity.vehicle.DismountHelper
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
- XXX.feature.foliageplacers.CherryFoliagePlacer
+ XXX.feature.foliageplacers.DarkOakFoliagePlacer
- XXX.feature.foliageplacers.FancyFoliagePlacer
+ XXX.feature.foliageplacers.FoliagePlacer
- XXX.feature.foliageplacers.FoliagePlacer$FoliageAttachment
+ XXX.feature.foliageplacers.FoliagePlacer$FoliageSetter
- XXX.feature.foliageplacers.FoliagePlacerType
+ XXX.feature.foliageplacers.MegaJungleFoliagePlacer
- XXX.feature.foliageplacers.MegaPineFoliagePlacer
- XXX.feature.foliageplacers.package-info
+ XXX.feature.foliageplacers.PineFoliagePlacer
- XXX.feature.foliageplacers.RandomSpreadFoliagePlacer
+ XXX.feature.foliageplacers.SpruceFoliagePlacer
- XXX.feature.rootplacers.AboveRootPlacement
+ XXX.feature.rootplacers.MangroveRootPlacement
- XXX.feature.rootplacers.MangroveRootPlacer
+ XXX.feature.rootplacers.package-info
+ XXX.feature.rootplacers.RootPlacer
- XXX.feature.rootplacers.RootPlacerType
- XXX.feature.stateproviders.BlockStateProvider
+ XXX.feature.stateproviders.BlockStateProviderType
- XXX.feature.stateproviders.DualNoiseProvider
+ XXX.feature.stateproviders.NoiseBasedStateProvider
- XXX.feature.stateproviders.NoiseProvider
+ XXX.feature.stateproviders.NoiseThresholdProvider
- XXX.feature.stateproviders.package-info
- XXX.feature.stateproviders.RandomizedIntStateProvider
+ XXX.feature.stateproviders.RotatedBlockProvider
- XXX.feature.stateproviders.RuleBasedBlockStateProvider
+ XXX.feature.stateproviders.RuleBasedBlockStateProvider$Rule
- XXX.feature.stateproviders.SimpleStateProvider
+ XXX.feature.stateproviders.WeightedStateProvider
+ XXX.feature.treedecorators.AlterGroundDecorator
- XXX.feature.treedecorators.AttachedToLeavesDecorator
+ XXX.feature.treedecorators.BeehiveDecorator
- XXX.feature.treedecorators.CocoaDecorator
+ XXX.feature.treedecorators.LeaveVineDecorator
- XXX.feature.treedecorators.package-info
- XXX.feature.treedecorators.TreeDecorator
+ XXX.feature.treedecorators.TreeDecorator$Context
- XXX.feature.treedecorators.TreeDecoratorType
+ XXX.feature.treedecorators.TrunkVineDecorator
+ XXX.feature.trunkplacers.BendingTrunkPlacer
- XXX.feature.trunkplacers.CherryTrunkPlacer
+ XXX.feature.trunkplacers.DarkOakTrunkPlacer
- XXX.feature.trunkplacers.FancyTrunkPlacer
+ XXX.feature.trunkplacers.FancyTrunkPlacer$FoliageCoords
- XXX.feature.trunkplacers.ForkingTrunkPlacer
+ XXX.feature.trunkplacers.GiantTrunkPlacer
- XXX.feature.trunkplacers.MegaJungleTrunkPlacer
+ XXX.feature.trunkplacers.package-info
+ XXX.feature.trunkplacers.StraightTrunkPlacer
- XXX.feature.trunkplacers.TrunkPlacer
+ XXX.feature.trunkplacers.TrunkPlacerType
- XXX.feature.trunkplacers.UpwardsBranchingTrunkPlacer
- XXX.gameevent.vibrations.package-info
+ XXX.gameevent.vibrations.VibrationListener
- XXX.gameevent.vibrations.VibrationSystem$Data
- XXX.gameevent.vibrations.VibrationSystem$Ticker
+ XXX.geom.builders.CubeDefinition
- XXX.geom.builders.CubeDeformation
+ XXX.geom.builders.CubeListBuilder
- XXX.geom.builders.LayerDefinition
+ XXX.geom.builders.MaterialDefinition
- XXX.geom.builders.MeshDefinition
+ XXX.geom.builders.package-info
+ XXX.geom.builders.PartDefinition
- XXX.geom.builders.UVPair
+ XXX.gui.components.AbstractButton
- XXX.gui.components.AbstractOptionSliderButton
+ XXX.gui.components.AbstractScrollWidget
- XXX.gui.components.AbstractSelectionList
+ XXX.gui.components.AbstractSelectionList$1
- XXX.gui.components.AbstractSelectionList$Entry
+ XXX.gui.components.AbstractSelectionList$TrackedList
- XXX.gui.components.AbstractSliderButton
+ XXX.gui.components.AbstractStringWidget
- XXX.gui.components.AbstractWidget
+ XXX.gui.components.AccessibilityOnboardingTextWidget
- XXX.gui.components.BossHealthOverlay
+ XXX.gui.components.BossHealthOverlay$1
- XXX.gui.components.Button
+ XXX.gui.components.Button$Builder
- XXX.gui.components.Button$CreateNarration
+ XXX.gui.components.Button$OnPress
- XXX.gui.components.ChatComponent
+ XXX.gui.components.ChatComponent$DelayedMessageDeletion
- XXX.gui.components.Checkbox
+ XXX.gui.components.CommandSuggestions
- XXX.gui.components.CommandSuggestions$SuggestionsList
+ XXX.gui.components.CommonButtons
- XXX.gui.components.ComponentRenderUtils
+ XXX.gui.components.ContainerObjectSelectionList
- XXX.gui.components.ContainerObjectSelectionList$1
+ XXX.gui.components.ContainerObjectSelectionList$Entry
- XXX.gui.components.CycleButton
+ XXX.gui.components.CycleButton$Builder
- XXX.gui.components.CycleButton$OnValueChange
+ XXX.gui.components.CycleButton$ValueListSupplier
- XXX.gui.components.CycleButton$ValueListSupplier$1
+ XXX.gui.components.CycleButton$ValueListSupplier$2
- XXX.gui.components.DebugScreenOverlay
+ XXX.gui.components.DebugScreenOverlay$1
- XXX.gui.components.DebugScreenOverlay$AllocationRateCalculator
+ XXX.gui.components.EditBox
- XXX.gui.components.ImageButton
+ XXX.gui.components.ImageWidget
- XXX.gui.components.LerpingBossEvent
+ XXX.gui.components.LockIconButton
- XXX.gui.components.LockIconButton$Icon
+ XXX.gui.components.LogoRenderer
- XXX.gui.components.MultiLineEditBox
+ XXX.gui.components.MultiLineLabel
- XXX.gui.components.MultiLineLabel$1
+ XXX.gui.components.MultiLineLabel$2
- XXX.gui.components.MultiLineLabel$TextWithWidth
+ XXX.gui.components.MultilineTextField
- XXX.gui.components.MultilineTextField$1
+ XXX.gui.components.MultilineTextField$StringView
+ XXX.gui.components.MultiLineTextWidget
- XXX.gui.components.MultiLineTextWidget$CacheKey
- XXX.gui.components.ObjectSelectionList
+ XXX.gui.components.ObjectSelectionList$Entry
- XXX.gui.components.OptionsList
+ XXX.gui.components.OptionsList$Entry
- XXX.gui.components.PlainTextButton
+ XXX.gui.components.PlayerFaceRenderer
- XXX.gui.components.PlayerTabOverlay
+ XXX.gui.components.PlayerTabOverlay$HealthState
- XXX.gui.components.Renderable
- XXX.gui.screens.package-info
- XXX.gui.screens.package-info
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
+ XXX.gui.screens.RealmsNotificationsScreen$2
- XXX.gui.screens.RealmsNotificationsScreen$3
+ XXX.gui.screens.RealmsNotificationsScreen$DataFetcherConfiguration
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
- XXX.gui.screens.RealmsResetNormalWorldScreen
+ XXX.gui.screens.RealmsResetWorldScreen
- XXX.gui.screens.RealmsResetWorldScreen$1
+ XXX.gui.screens.RealmsResetWorldScreen$FrameButton
- XXX.gui.screens.RealmsSelectFileToUploadScreen
+ XXX.gui.screens.RealmsSelectFileToUploadScreen$Entry
- XXX.gui.screens.RealmsSelectFileToUploadScreen$WorldSelectionList
+ XXX.gui.screens.RealmsSelectWorldTemplateScreen
- XXX.gui.screens.RealmsSelectWorldTemplateScreen$1
+ XXX.gui.screens.RealmsSelectWorldTemplateScreen$Entry
- XXX.gui.screens.RealmsSelectWorldTemplateScreen$WorldTemplateObjectSelectionList
+ XXX.gui.screens.RealmsSettingsScreen
- XXX.gui.screens.RealmsSlotOptionsScreen
+ XXX.gui.screens.RealmsSlotOptionsScreen$SettingsSlider
- XXX.gui.screens.RealmsSubscriptionInfoScreen
+ XXX.gui.screens.RealmsSubscriptionInfoScreen$1
- XXX.gui.screens.RealmsTermsScreen
+ XXX.gui.screens.RealmsUploadScreen
- XXX.gui.screens.UploadResult
+ XXX.gui.screens.UploadResult$Builder
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
+ XXX.gui.task.DataFetcher
- XXX.gui.task.DataFetcher$ComputationResult
+ XXX.gui.task.DataFetcher$SubscribedTask
- XXX.gui.task.DataFetcher$Subscription
+ XXX.gui.task.DataFetcher$SuccessfulComputationResult
- XXX.gui.task.DataFetcher$Task
- XXX.gui.task.package-info
+ XXX.gui.task.RepeatedDelayStrategy
- XXX.gui.task.RepeatedDelayStrategy$1
+ XXX.gui.task.RepeatedDelayStrategy$2
- XXX.inventory.tooltip.BundleTooltip
+ XXX.inventory.tooltip.package-info
- XXX.inventory.tooltip.package-info
+ XXX.inventory.tooltip.TooltipComponent
- XXX.item.alchemy.package-info
+ XXX.item.alchemy.Potion
- XXX.item.alchemy.PotionBrewing
+ XXX.item.alchemy.PotionBrewing$Mix
+ XXX.item.alchemy.Potions
- XXX.item.alchemy.PotionUtils
+ XXX.item.armortrim.ArmorTrim
- XXX.item.armortrim.package-info
- XXX.item.armortrim.TrimMaterial
+ XXX.item.armortrim.TrimMaterials
- XXX.item.armortrim.TrimPattern
+ XXX.item.armortrim.TrimPatterns
+ XXX.item.context.BlockPlaceContext
- XXX.item.context.DirectionalPlaceContext
+ XXX.item.context.DirectionalPlaceContext$1
+ XXX.item.context.package-info
- XXX.item.context.UseOnContext
- XXX.item.crafting.AbstractCookingRecipe
+ XXX.item.crafting.ArmorDyeRecipe
- XXX.item.crafting.BannerDuplicateRecipe
+ XXX.item.crafting.BlastingRecipe
- XXX.item.crafting.BookCloningRecipe
+ XXX.item.crafting.CampfireCookingRecipe
- XXX.item.crafting.CookingBookCategory
+ XXX.item.crafting.CraftingBookCategory
- XXX.item.crafting.CraftingRecipe
+ XXX.item.crafting.CustomRecipe
- XXX.item.crafting.DecoratedPotRecipe
+ XXX.item.crafting.FireworkRocketRecipe
- XXX.item.crafting.FireworkStarFadeRecipe
+ XXX.item.crafting.FireworkStarRecipe
- XXX.item.crafting.Ingredient
+ XXX.item.crafting.Ingredient$ItemValue
- XXX.item.crafting.Ingredient$TagValue
+ XXX.item.crafting.Ingredient$Value
- XXX.item.crafting.MapCloningRecipe
+ XXX.item.crafting.MapExtendingRecipe
+ XXX.item.crafting.package-info
- XXX.item.crafting.Recipe
+ XXX.item.crafting.RecipeManager
- XXX.item.crafting.RecipeManager$1
+ XXX.item.crafting.RecipeManager$CachedCheck
- XXX.item.crafting.RecipeSerializer
+ XXX.item.crafting.RecipeType
- XXX.item.crafting.RecipeType$1
+ XXX.item.crafting.RepairItemRecipe
- XXX.item.crafting.ShapedRecipe
+ XXX.item.crafting.ShapedRecipe$Serializer
- XXX.item.crafting.ShapelessRecipe
+ XXX.item.crafting.ShapelessRecipe$Serializer
- XXX.item.crafting.ShieldDecorationRecipe
+ XXX.item.crafting.ShulkerBoxColoring
- XXX.item.crafting.SimpleCookingSerializer
+ XXX.item.crafting.SimpleCookingSerializer$CookieBaker
- XXX.item.crafting.SimpleCraftingRecipeSerializer
+ XXX.item.crafting.SimpleCraftingRecipeSerializer$Factory
- XXX.item.crafting.SingleItemRecipe
+ XXX.item.crafting.SingleItemRecipe$Serializer
- XXX.item.crafting.SingleItemRecipe$Serializer$SingleItemMaker
+ XXX.item.crafting.SmeltingRecipe
- XXX.item.crafting.SmithingRecipe
+ XXX.item.crafting.SmithingTransformRecipe
- XXX.item.crafting.SmithingTransformRecipe$Serializer
+ XXX.item.crafting.SmithingTrimRecipe
- XXX.item.crafting.SmithingTrimRecipe$Serializer
+ XXX.item.crafting.SmokingRecipe
- XXX.item.crafting.StonecutterRecipe
+ XXX.item.crafting.SuspiciousStewRecipe
- XXX.item.crafting.TippedArrowRecipe
- XXX.item.enchantment.ArrowDamageEnchantment
+ XXX.item.enchantment.ArrowFireEnchantment
- XXX.item.enchantment.ArrowInfiniteEnchantment
+ XXX.item.enchantment.ArrowKnockbackEnchantment
- XXX.item.enchantment.ArrowPiercingEnchantment
+ XXX.item.enchantment.BindingCurseEnchantment
- XXX.item.enchantment.DamageEnchantment
+ XXX.item.enchantment.DigDurabilityEnchantment
- XXX.item.enchantment.DiggingEnchantment
+ XXX.item.enchantment.Enchantment
- XXX.item.enchantment.Enchantment$Rarity
+ XXX.item.enchantment.EnchantmentCategory
- XXX.item.enchantment.EnchantmentCategory$1
+ XXX.item.enchantment.EnchantmentCategory$10
- XXX.item.enchantment.EnchantmentCategory$11
+ XXX.item.enchantment.EnchantmentCategory$12
- XXX.item.enchantment.EnchantmentCategory$13
+ XXX.item.enchantment.EnchantmentCategory$14
- XXX.item.enchantment.EnchantmentCategory$2
+ XXX.item.enchantment.EnchantmentCategory$3
- XXX.item.enchantment.EnchantmentCategory$4
+ XXX.item.enchantment.EnchantmentCategory$5
- XXX.item.enchantment.EnchantmentCategory$6
+ XXX.item.enchantment.EnchantmentCategory$7
- XXX.item.enchantment.EnchantmentCategory$8
+ XXX.item.enchantment.EnchantmentCategory$9
- XXX.item.enchantment.EnchantmentHelper
+ XXX.item.enchantment.EnchantmentHelper$EnchantmentVisitor
- XXX.item.enchantment.EnchantmentInstance
+ XXX.item.enchantment.Enchantments
- XXX.item.enchantment.FireAspectEnchantment
+ XXX.item.enchantment.FishingSpeedEnchantment
- XXX.item.enchantment.FrostWalkerEnchantment
+ XXX.item.enchantment.KnockbackEnchantment
- XXX.item.enchantment.LootBonusEnchantment
+ XXX.item.enchantment.MendingEnchantment
- XXX.item.enchantment.MultiShotEnchantment
+ XXX.item.enchantment.OxygenEnchantment
+ XXX.item.enchantment.package-info
- XXX.item.enchantment.ProtectionEnchantment
+ XXX.item.enchantment.ProtectionEnchantment$Type
- XXX.item.enchantment.QuickChargeEnchantment
+ XXX.item.enchantment.SoulSpeedEnchantment
- XXX.item.enchantment.SweepingEdgeEnchantment
+ XXX.item.enchantment.SwiftSneakEnchantment
- XXX.item.enchantment.ThornsEnchantment
+ XXX.item.enchantment.TridentChannelingEnchantment
- XXX.item.enchantment.TridentImpalerEnchantment
+ XXX.item.enchantment.TridentLoyaltyEnchantment
- XXX.item.enchantment.TridentRiptideEnchantment
+ XXX.item.enchantment.UntouchingEnchantment
- XXX.item.enchantment.VanishingCurseEnchantment
+ XXX.item.enchantment.WaterWalkerEnchantment
- XXX.item.enchantment.WaterWorkerEnchantment
+ XXX.item.trading.Merchant
- XXX.item.trading.MerchantOffer
+ XXX.item.trading.MerchantOffers
- XXX.item.trading.package-info
- XXX.level.biome.AmbientAdditionsSettings
+ XXX.level.biome.AmbientMoodSettings
- XXX.level.biome.AmbientParticleSettings
+ XXX.level.biome.Biome
- XXX.level.biome.Biome$1
+ XXX.level.biome.Biome$BiomeBuilder
- XXX.level.biome.Biome$ClimateSettings
+ XXX.level.biome.Biome$Precipitation
- XXX.level.biome.Biome$TemperatureModifier
+ XXX.level.biome.Biome$TemperatureModifier$1
- XXX.level.biome.Biome$TemperatureModifier$2
+ XXX.level.biome.BiomeGenerationSettings
- XXX.level.biome.BiomeGenerationSettings$Builder
+ XXX.level.biome.BiomeGenerationSettings$PlainBuilder
- XXX.level.biome.BiomeManager
+ XXX.level.biome.BiomeManager$NoiseBiomeSource
- XXX.level.biome.BiomeResolver
+ XXX.level.biome.Biomes
+ XXX.level.biome.BiomeSource
- XXX.level.biome.BiomeSources
+ XXX.level.biome.BiomeSpecialEffects
- XXX.level.biome.BiomeSpecialEffects$Builder
+ XXX.level.biome.BiomeSpecialEffects$GrassColorModifier
- XXX.level.biome.BiomeSpecialEffects$GrassColorModifier$1
+ XXX.level.biome.BiomeSpecialEffects$GrassColorModifier$2
- XXX.level.biome.BiomeSpecialEffects$GrassColorModifier$3
- XXX.level.biome.CheckerboardColumnBiomeSource
+ XXX.level.biome.Climate
- XXX.level.biome.Climate$DistanceMetric
+ XXX.level.biome.Climate$Parameter
- XXX.level.biome.Climate$ParameterList
+ XXX.level.biome.Climate$ParameterPoint
- XXX.level.biome.Climate$RTree
+ XXX.level.biome.Climate$RTree$Leaf
- XXX.level.biome.Climate$RTree$Node
+ XXX.level.biome.Climate$RTree$SubTree
- XXX.level.biome.Climate$Sampler
+ XXX.level.biome.Climate$SpawnFinder
- XXX.level.biome.Climate$SpawnFinder$Result
+ XXX.level.biome.Climate$TargetPoint
- XXX.level.biome.FeatureSorter
+ XXX.level.biome.FeatureSorter$1FeatureData
- XXX.level.biome.FeatureSorter$StepFeatureData
+ XXX.level.biome.FixedBiomeSource
- XXX.level.biome.MobSpawnSettings
+ XXX.level.biome.MobSpawnSettings$Builder
- XXX.level.biome.MobSpawnSettings$MobSpawnCost
+ XXX.level.biome.MobSpawnSettings$SpawnerData
- XXX.level.biome.MultiNoiseBiomeSource
+ XXX.level.biome.MultiNoiseBiomeSourceParameterList
- XXX.level.biome.MultiNoiseBiomeSourceParameterList$Preset
+ XXX.level.biome.MultiNoiseBiomeSourceParameterList$Preset$1
- XXX.level.biome.MultiNoiseBiomeSourceParameterList$Preset$2
+ XXX.level.biome.MultiNoiseBiomeSourceParameterList$Preset$SourceProvider
- XXX.level.biome.MultiNoiseBiomeSourceParameterLists
+ XXX.level.biome.OverworldBiomeBuilder
+ XXX.level.biome.package-info
- XXX.level.biome.TheEndBiomeSource
- XXX.level.block.AbstractBannerBlock
+ XXX.level.block.AbstractCandleBlock
- XXX.level.block.AbstractCauldronBlock
+ XXX.level.block.AbstractChestBlock
- XXX.level.block.AbstractFurnaceBlock
+ XXX.level.block.AbstractGlassBlock
- XXX.level.block.AbstractSkullBlock
+ XXX.level.block.AirBlock
- XXX.level.block.AmethystBlock
+ XXX.level.block.AmethystClusterBlock
- XXX.level.block.AmethystClusterBlock$1
+ XXX.level.block.AnvilBlock
- XXX.level.block.AttachedStemBlock
+ XXX.level.block.AzaleaBlock
- XXX.level.block.BambooSaplingBlock
+ XXX.level.block.BambooStalkBlock
- XXX.level.block.BannerBlock
+ XXX.level.block.BarrelBlock
- XXX.level.block.BarrierBlock
+ XXX.level.block.BaseCoralFanBlock
- XXX.level.block.BaseCoralPlantBlock
+ XXX.level.block.BaseCoralPlantTypeBlock
- XXX.level.block.BaseCoralWallFanBlock
+ XXX.level.block.BaseEntityBlock
- XXX.level.block.BaseFireBlock
+ XXX.level.block.BasePressurePlateBlock
- XXX.level.block.BaseRailBlock
+ XXX.level.block.BaseRailBlock$1
- XXX.level.block.BeaconBeamBlock
+ XXX.level.block.BeaconBlock
- XXX.level.block.BedBlock
+ XXX.level.block.BedBlock$1
- XXX.level.block.BeehiveBlock
+ XXX.level.block.BeetrootBlock
- XXX.level.block.BellBlock
+ XXX.level.block.BellBlock$1
- XXX.level.block.BigDripleafBlock
+ XXX.level.block.BigDripleafStemBlock
- XXX.level.block.BigDripleafStemBlock$1
+ XXX.level.block.BlastFurnaceBlock
- XXX.level.block.Block
+ XXX.level.block.Block$1
- XXX.level.block.Block$2
+ XXX.level.block.Block$BlockStatePairKey
- XXX.level.block.Blocks
+ XXX.level.block.BonemealableBlock
- XXX.level.block.BrewingStandBlock
+ XXX.level.block.BrushableBlock
- XXX.level.block.BubbleColumnBlock
+ XXX.level.block.BucketPickup
- XXX.level.block.BuddingAmethystBlock
+ XXX.level.block.BushBlock
- XXX.level.block.ButtonBlock
+ XXX.level.block.ButtonBlock$1
- XXX.level.block.CactusBlock
+ XXX.level.block.CakeBlock
- XXX.level.block.CalibratedSculkSensorBlock
+ XXX.level.block.CampfireBlock
- XXX.level.block.CandleBlock
+ XXX.level.block.CandleCakeBlock
- XXX.level.block.CarpetBlock
+ XXX.level.block.CarrotBlock
- XXX.level.block.CartographyTableBlock
+ XXX.level.block.CarvedPumpkinBlock
- XXX.level.block.CauldronBlock
+ XXX.level.block.CaveVines
- XXX.level.block.CaveVinesBlock
+ XXX.level.block.CaveVinesPlantBlock
- XXX.level.block.CeilingHangingSignBlock
+ XXX.level.block.ChainBlock
- XXX.level.block.ChainBlock$1
+ XXX.level.block.ChangeOverTimeBlock
- XXX.level.block.CherryLeavesBlock
+ XXX.level.block.ChestBlock
- XXX.level.block.ChestBlock$1
+ XXX.level.block.ChestBlock$2
- XXX.level.block.ChestBlock$2$1
+ XXX.level.block.ChestBlock$3
- XXX.level.block.ChestBlock$4
+ XXX.level.block.ChiseledBookShelfBlock
- XXX.level.block.ChiseledBookShelfBlock$1
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
+ XXX.level.block.CryingObsidianBlock
- XXX.level.block.DaylightDetectorBlock
+ XXX.level.block.DeadBushBlock
- XXX.level.block.DecoratedPotBlock
+ XXX.level.block.DetectorRailBlock
- XXX.level.block.DetectorRailBlock$1
+ XXX.level.block.DiodeBlock
- XXX.level.block.DirectionalBlock
+ XXX.level.block.DirtPathBlock
- XXX.level.block.DispenserBlock
+ XXX.level.block.DoorBlock
- XXX.level.block.DoorBlock$1
+ XXX.level.block.DoubleBlockCombiner
- XXX.level.block.DoubleBlockCombiner$BlockType
+ XXX.level.block.DoubleBlockCombiner$Combiner
- XXX.level.block.DoubleBlockCombiner$NeighborCombineResult
+ XXX.level.block.DoubleBlockCombiner$NeighborCombineResult$Double
- XXX.level.block.DoubleBlockCombiner$NeighborCombineResult$Single
+ XXX.level.block.DoublePlantBlock
- XXX.level.block.DragonEggBlock
+ XXX.level.block.DropExperienceBlock
- XXX.level.block.DropperBlock
+ XXX.level.block.EnchantmentTableBlock
- XXX.level.block.EnderChestBlock
- XXX.level.block.EndGatewayBlock
+ XXX.level.block.EndPortalBlock
- XXX.level.block.EndPortalFrameBlock
+ XXX.level.block.EndRodBlock
+ XXX.level.block.EntityBlock
- XXX.level.block.FaceAttachedHorizontalDirectionalBlock
+ XXX.level.block.FaceAttachedHorizontalDirectionalBlock$1
- XXX.level.block.Fallable
+ XXX.level.block.FallingBlock
+ XXX.level.block.FarmableBlock
- XXX.level.block.FarmBlock
- XXX.level.gameevent.GameEvent
+ XXX.level.gameevent.GameEvent$Context
- XXX.level.gameevent.GameEvent$ListenerInfo
+ XXX.level.gameevent.GameEventDispatcher
- XXX.level.gameevent.GameEventListener
+ XXX.level.gameevent.GameEventListener$DeliveryMode
- XXX.level.gameevent.GameEventListener$Holder
+ XXX.level.levelgen.Aquifer
- XXX.level.levelgen.Aquifer$1
+ XXX.level.levelgen.Aquifer$FluidPicker
- XXX.level.levelgen.Aquifer$FluidStatus
+ XXX.level.levelgen.Aquifer$NoiseBasedAquifer
- XXX.level.levelgen.Beardifier
+ XXX.level.levelgen.Beardifier$1
- XXX.level.levelgen.Beardifier$Rigid
+ XXX.level.levelgen.BelowZeroRetrogen
- XXX.level.levelgen.BelowZeroRetrogen$1
+ XXX.level.levelgen.BitRandomSource
- XXX.level.levelgen.Column
+ XXX.level.levelgen.Column$Line
- XXX.level.levelgen.Column$Range
+ XXX.level.levelgen.Column$Ray
- XXX.level.levelgen.DebugLevelSource
+ XXX.level.levelgen.Density
- XXX.level.levelgen.DensityFunction
+ XXX.level.levelgen.DensityFunction$ContextProvider
- XXX.level.levelgen.DensityFunction$FunctionContext
+ XXX.level.levelgen.DensityFunction$NoiseHolder
- XXX.level.levelgen.DensityFunction$SimpleFunction
+ XXX.level.levelgen.DensityFunction$SinglePointContext
- XXX.level.levelgen.DensityFunction$Visitor
+ XXX.level.levelgen.DensityFunctions
- XXX.level.levelgen.DensityFunctions$1
+ XXX.level.levelgen.DensityFunctions$Ap2
- XXX.level.levelgen.DensityFunctions$BeardifierMarker
+ XXX.level.levelgen.DensityFunctions$BeardifierOrMarker
- XXX.level.levelgen.DensityFunctions$BlendAlpha
+ XXX.level.levelgen.DensityFunctions$BlendDensity
- XXX.level.levelgen.DensityFunctions$BlendOffset
+ XXX.level.levelgen.DensityFunctions$Clamp
- XXX.level.levelgen.DensityFunctions$Constant
+ XXX.level.levelgen.DensityFunctions$EndIslandDensityFunction
- XXX.level.levelgen.DensityFunctions$HolderHolder
+ XXX.level.levelgen.DensityFunctions$Mapped
- XXX.level.levelgen.DensityFunctions$Mapped$Type
+ XXX.level.levelgen.DensityFunctions$Marker
- XXX.level.levelgen.DensityFunctions$Marker$Type
+ XXX.level.levelgen.DensityFunctions$MarkerOrMarked
- XXX.level.levelgen.DensityFunctions$MulOrAdd
+ XXX.level.levelgen.DensityFunctions$MulOrAdd$Type
- XXX.level.levelgen.DensityFunctions$Noise
+ XXX.level.levelgen.DensityFunctions$PureTransformer
- XXX.level.levelgen.DensityFunctions$RangeChoice
+ XXX.level.levelgen.DensityFunctions$Shift
- XXX.level.levelgen.DensityFunctions$ShiftA
+ XXX.level.levelgen.DensityFunctions$ShiftB
+ XXX.level.levelgen.DensityFunctions$ShiftedNoise
- XXX.level.levelgen.DensityFunctions$ShiftNoise
- XXX.level.levelgen.DensityFunctions$Spline
+ XXX.level.levelgen.DensityFunctions$Spline$Coordinate
- XXX.level.levelgen.DensityFunctions$Spline$Point
+ XXX.level.levelgen.DensityFunctions$TransformerWithContext
- XXX.level.levelgen.DensityFunctions$TwoArgumentSimpleFunction
+ XXX.level.levelgen.DensityFunctions$TwoArgumentSimpleFunction$Type
- XXX.level.levelgen.DensityFunctions$WeirdScaledSampler
+ XXX.level.levelgen.DensityFunctions$WeirdScaledSampler$RarityValueMapper
- XXX.level.levelgen.DensityFunctions$YClampedGradient
+ XXX.level.levelgen.FlatLevelSource
- XXX.level.levelgen.GenerationStep
+ XXX.level.levelgen.GenerationStep$Carving
- XXX.level.levelgen.GenerationStep$Decoration
+ XXX.level.levelgen.GeodeBlockSettings
- XXX.level.levelgen.GeodeCrackSettings
+ XXX.level.levelgen.GeodeLayerSettings
- XXX.level.levelgen.Heightmap
+ XXX.level.levelgen.Heightmap$Types
- XXX.level.levelgen.Heightmap$Usage
+ XXX.level.levelgen.LegacyRandomSource
- XXX.level.levelgen.LegacyRandomSource$LegacyPositionalRandomFactory
+ XXX.level.levelgen.MarsagliaPolarGaussian
- XXX.level.levelgen.NoiseBasedChunkGenerator
+ XXX.level.levelgen.NoiseChunk
- XXX.level.levelgen.NoiseChunk$1
+ XXX.level.levelgen.NoiseChunk$2
- XXX.level.levelgen.NoiseChunk$BlendAlpha
+ XXX.level.levelgen.NoiseChunk$BlendOffset
- XXX.level.levelgen.NoiseChunk$BlockStateFiller
+ XXX.level.levelgen.NoiseChunk$Cache2D
- XXX.level.levelgen.NoiseChunk$CacheAllInCell
+ XXX.level.levelgen.NoiseChunk$CacheOnce
- XXX.level.levelgen.NoiseChunk$FlatCache
+ XXX.level.levelgen.NoiseChunk$NoiseChunkDensityFunction
- XXX.level.levelgen.NoiseChunk$NoiseInterpolator
+ XXX.level.levelgen.NoiseGeneratorSettings
- XXX.level.levelgen.NoiseRouter
+ XXX.level.levelgen.NoiseRouterData
- XXX.level.levelgen.NoiseRouterData$QuantizedSpaghettiRarity
- XXX.level.levelgen.Noises
+ XXX.level.levelgen.NoiseSettings
+ XXX.level.levelgen.OreVeinifier
- XXX.level.levelgen.OreVeinifier$VeinType
- XXX.level.levelgen.package-info
+ XXX.level.levelgen.PatrolSpawner
- XXX.level.levelgen.PhantomSpawner
+ XXX.level.levelgen.PositionalRandomFactory
- XXX.level.levelgen.RandomState
+ XXX.level.levelgen.RandomState$1
- XXX.level.levelgen.RandomState$1NoiseWiringHelper
+ XXX.level.levelgen.RandomSupport
- XXX.level.levelgen.RandomSupport$Seed128bit
+ XXX.level.levelgen.SingleThreadedRandomSource
- XXX.level.levelgen.SurfaceRules
+ XXX.level.levelgen.SurfaceRules$AbovePreliminarySurface
- XXX.level.levelgen.SurfaceRules$Bandlands
+ XXX.level.levelgen.SurfaceRules$BiomeConditionSource
- XXX.level.levelgen.SurfaceRules$BiomeConditionSource$1BiomeCondition
+ XXX.level.levelgen.SurfaceRules$BlockRuleSource
- XXX.level.levelgen.SurfaceRules$Condition
+ XXX.level.levelgen.SurfaceRules$ConditionSource
- XXX.level.levelgen.SurfaceRules$Context
+ XXX.level.levelgen.SurfaceRules$Context$AbovePreliminarySurfaceCondition
- XXX.level.levelgen.SurfaceRules$Context$HoleCondition
+ XXX.level.levelgen.SurfaceRules$Context$SteepMaterialCondition
- XXX.level.levelgen.SurfaceRules$Context$TemperatureHelperCondition
+ XXX.level.levelgen.SurfaceRules$Hole
- XXX.level.levelgen.SurfaceRules$LazyCondition
+ XXX.level.levelgen.SurfaceRules$LazyXZCondition
- XXX.level.levelgen.SurfaceRules$LazyYCondition
+ XXX.level.levelgen.SurfaceRules$NoiseThresholdConditionSource
- XXX.level.levelgen.SurfaceRules$NoiseThresholdConditionSource$1NoiseThresholdCondition
+ XXX.level.levelgen.SurfaceRules$NotCondition
- XXX.level.levelgen.SurfaceRules$NotConditionSource
+ XXX.level.levelgen.SurfaceRules$RuleSource
- XXX.level.levelgen.SurfaceRules$SequenceRule
+ XXX.level.levelgen.SurfaceRules$SequenceRuleSource
- XXX.level.levelgen.SurfaceRules$StateRule
+ XXX.level.levelgen.SurfaceRules$Steep
- XXX.level.levelgen.SurfaceRules$StoneDepthCheck
+ XXX.level.levelgen.SurfaceRules$StoneDepthCheck$1StoneDepthCondition
- XXX.level.levelgen.SurfaceRules$SurfaceRule
+ XXX.level.levelgen.SurfaceRules$Temperature
- XXX.level.levelgen.SurfaceRules$TestRule
+ XXX.level.levelgen.SurfaceRules$TestRuleSource
- XXX.level.levelgen.SurfaceRules$VerticalGradientConditionSource
+ XXX.level.levelgen.SurfaceRules$VerticalGradientConditionSource$1VerticalGradientCondition
- XXX.level.levelgen.SurfaceRules$WaterConditionSource
+ XXX.level.levelgen.SurfaceRules$WaterConditionSource$1WaterCondition
- XXX.level.levelgen.SurfaceRules$YConditionSource
+ XXX.level.levelgen.SurfaceRules$YConditionSource$1YCondition
- XXX.level.levelgen.SurfaceSystem
+ XXX.level.levelgen.SurfaceSystem$1
- XXX.level.levelgen.ThreadSafeLegacyRandomSource
+ XXX.level.levelgen.VerticalAnchor
- XXX.level.levelgen.VerticalAnchor$AboveBottom
+ XXX.level.levelgen.VerticalAnchor$Absolute
- XXX.level.levelgen.VerticalAnchor$BelowTop
+ XXX.level.levelgen.WorldDimensions
- XXX.level.levelgen.WorldDimensions$1Entry
+ XXX.level.levelgen.WorldDimensions$Complete
+ XXX.level.levelgen.WorldGenerationContext
+ XXX.level.levelgen.WorldgenRandom
- XXX.level.levelgen.WorldgenRandom$Algorithm
- XXX.level.levelgen.WorldGenSettings
- XXX.level.levelgen.WorldOptions
+ XXX.level.levelgen.Xoroshiro128PlusPlus
- XXX.level.levelgen.XoroshiroRandomSource
+ XXX.level.levelgen.XoroshiroRandomSource$XoroshiroPositionalRandomFactory
- XXX.level.lighting.BlockLightEngine
+ XXX.level.lighting.BlockLightSectionStorage
- XXX.level.lighting.BlockLightSectionStorage$BlockDataLayerStorageMap
+ XXX.level.lighting.DataLayerStorageMap
- XXX.level.lighting.DynamicGraphMinFixedPoint
+ XXX.level.lighting.DynamicGraphMinFixedPoint$1
- XXX.level.lighting.LayerLightEngine
+ XXX.level.lighting.LayerLightEventListener
- XXX.level.lighting.LayerLightEventListener$DummyLightLayerEventListener
+ XXX.level.lighting.LayerLightSectionStorage
- XXX.level.lighting.LayerLightSectionStorage$1
- XXX.level.lighting.LeveledPriorityQueue
+ XXX.level.lighting.LeveledPriorityQueue$1
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
- XXX.level.material.FogType
+ XXX.level.material.LavaFluid
- XXX.level.material.LavaFluid$Flowing
+ XXX.level.material.LavaFluid$Source
- XXX.level.material.Material
+ XXX.level.material.Material$Builder
- XXX.levelgen.blending.Blender
+ XXX.levelgen.blending.Blender$1
- XXX.levelgen.blending.Blender$BlendingOutput
+ XXX.levelgen.blending.Blender$CellValueGetter
- XXX.levelgen.blending.Blender$DistanceGetter
+ XXX.levelgen.blending.BlendingData
- XXX.levelgen.blending.BlendingData$BiomeConsumer
+ XXX.levelgen.blending.BlendingData$DensityConsumer
- XXX.levelgen.blending.BlendingData$HeightConsumer
+ XXX.levelgen.blending.package-info
- XXX.levelgen.blockpredicates.AllOfPredicate
+ XXX.levelgen.blockpredicates.AnyOfPredicate
- XXX.levelgen.blockpredicates.BlockPredicate
+ XXX.levelgen.blockpredicates.BlockPredicateType
- XXX.levelgen.blockpredicates.CombiningPredicate
+ XXX.levelgen.blockpredicates.HasSturdyFacePredicate
- XXX.levelgen.blockpredicates.InsideWorldBoundsPredicate
- XXX.levelgen.blockpredicates.MatchingBlocksPredicate
+ XXX.levelgen.blockpredicates.MatchingBlockTagPredicate
+ XXX.levelgen.blockpredicates.MatchingFluidsPredicate
- XXX.levelgen.blockpredicates.NotPredicate
- XXX.levelgen.blockpredicates.package-info
+ XXX.levelgen.blockpredicates.ReplaceablePredicate
- XXX.levelgen.blockpredicates.SolidPredicate
+ XXX.levelgen.blockpredicates.StateTestingPredicate
- XXX.levelgen.blockpredicates.TrueBlockPredicate
+ XXX.levelgen.blockpredicates.WouldSurvivePredicate
+ XXX.levelgen.carver.CanyonCarverConfiguration
- XXX.levelgen.carver.CanyonCarverConfiguration$CanyonShapeConfiguration
+ XXX.levelgen.carver.CanyonWorldCarver
- XXX.levelgen.carver.CarverConfiguration
+ XXX.levelgen.carver.CarverDebugSettings
- XXX.levelgen.carver.CarvingContext
+ XXX.levelgen.carver.CaveCarverConfiguration
- XXX.levelgen.carver.CaveWorldCarver
+ XXX.levelgen.carver.ConfiguredWorldCarver
- XXX.levelgen.carver.NetherWorldCarver
+ XXX.levelgen.carver.package-info
+ XXX.levelgen.carver.WorldCarver
- XXX.levelgen.carver.WorldCarver$CarveSkipChecker
- XXX.levelgen.feature.AbstractHugeMushroomFeature
+ XXX.levelgen.feature.BambooFeature
- XXX.levelgen.feature.BasaltColumnsFeature
+ XXX.levelgen.feature.BasaltPillarFeature
- XXX.levelgen.feature.BlockBlobFeature
+ XXX.levelgen.feature.BlockColumnFeature
- XXX.levelgen.feature.BlockPileFeature
+ XXX.levelgen.feature.BlueIceFeature
- XXX.levelgen.feature.BonusChestFeature
+ XXX.levelgen.feature.ChorusPlantFeature
- XXX.levelgen.feature.ConfiguredFeature
+ XXX.levelgen.feature.CoralClawFeature
- XXX.levelgen.feature.CoralFeature
+ XXX.levelgen.feature.CoralMushroomFeature
- XXX.levelgen.feature.CoralTreeFeature
+ XXX.levelgen.feature.DeltaFeature
- XXX.levelgen.feature.DesertWellFeature
+ XXX.levelgen.feature.DiskFeature
- XXX.levelgen.feature.DripstoneClusterFeature
+ XXX.levelgen.feature.DripstoneUtils
- XXX.levelgen.feature.EndGatewayFeature
+ XXX.levelgen.feature.EndIslandFeature
- XXX.levelgen.feature.EndPodiumFeature
+ XXX.levelgen.feature.Feature
- XXX.levelgen.feature.FeatureCountTracker
+ XXX.levelgen.feature.FeatureCountTracker$1
- XXX.levelgen.feature.FeatureCountTracker$FeatureData
+ XXX.levelgen.feature.FeatureCountTracker$LevelData
- XXX.levelgen.feature.FeaturePlaceContext
+ XXX.levelgen.feature.FillLayerFeature
- XXX.levelgen.feature.FossilFeature
+ XXX.levelgen.feature.FossilFeatureConfiguration
- XXX.levelgen.feature.GeodeFeature
+ XXX.levelgen.feature.GlowstoneFeature
- XXX.levelgen.feature.HugeBrownMushroomFeature
+ XXX.levelgen.feature.HugeFungusConfiguration
- XXX.levelgen.feature.HugeFungusFeature
+ XXX.levelgen.feature.HugeRedMushroomFeature
+ XXX.levelgen.feature.IcebergFeature
- XXX.levelgen.feature.IceSpikeFeature
- XXX.levelgen.feature.KelpFeature
+ XXX.levelgen.feature.LakeFeature
- XXX.levelgen.feature.LakeFeature$Configuration
+ XXX.levelgen.feature.LargeDripstoneFeature
- XXX.levelgen.feature.LargeDripstoneFeature$LargeDripstone
+ XXX.levelgen.feature.LargeDripstoneFeature$WindOffsetter
- XXX.levelgen.feature.MonsterRoomFeature
+ XXX.levelgen.feature.MultifaceGrowthFeature
- XXX.levelgen.feature.NetherForestVegetationFeature
+ XXX.levelgen.feature.NoOpFeature
- XXX.levelgen.feature.OreFeature
+ XXX.levelgen.feature.package-info
+ XXX.levelgen.feature.PointedDripstoneFeature
- XXX.levelgen.feature.RandomBooleanSelectorFeature
+ XXX.levelgen.feature.RandomPatchFeature
- XXX.levelgen.feature.RandomSelectorFeature
+ XXX.levelgen.feature.ReplaceBlobsFeature
- XXX.levelgen.feature.ReplaceBlockFeature
+ XXX.levelgen.feature.RootSystemFeature
- XXX.levelgen.feature.ScatteredOreFeature
+ XXX.levelgen.feature.SculkPatchFeature
+ XXX.levelgen.feature.SeagrassFeature
- XXX.levelgen.feature.SeaPickleFeature
- XXX.levelgen.feature.SimpleBlockFeature
+ XXX.levelgen.feature.SimpleRandomSelectorFeature
- XXX.levelgen.feature.SnowAndFreezeFeature
+ XXX.levelgen.feature.SpikeFeature
- XXX.levelgen.feature.SpikeFeature$EndSpike
+ XXX.levelgen.feature.SpikeFeature$SpikeCacheLoader
- XXX.levelgen.feature.SpringFeature
+ XXX.levelgen.feature.TreeFeature
- XXX.levelgen.feature.TreeFeature$1
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
+ XXX.levelgen.placement.package-info
+ XXX.levelgen.placement.PlacedFeature
- XXX.levelgen.placement.PlacementContext
+ XXX.levelgen.placement.PlacementFilter
- XXX.levelgen.placement.PlacementModifier
+ XXX.levelgen.placement.PlacementModifierType
- XXX.levelgen.placement.RandomOffsetPlacement
+ XXX.levelgen.placement.RarityFilter
- XXX.levelgen.placement.RepeatingPlacement
+ XXX.levelgen.placement.SurfaceRelativeThresholdFilter
- XXX.levelgen.placement.SurfaceWaterDepthFilter
+ XXX.levelgen.presets.package-info
- XXX.levelgen.presets.WorldPreset
+ XXX.levelgen.presets.WorldPresets
- XXX.levelgen.presets.WorldPresets$Bootstrap
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
+ XXX.levelgen.structure.Structure$StructureSettings
- XXX.levelgen.structure.StructureCheck
+ XXX.levelgen.structure.StructureCheckResult
- XXX.levelgen.structure.StructureFeatureIndexSavedData
+ XXX.levelgen.structure.StructurePiece
- XXX.levelgen.structure.StructurePiece$1
+ XXX.levelgen.structure.StructurePiece$BlockSelector
- XXX.levelgen.structure.StructurePieceAccessor
+ XXX.levelgen.structure.StructureSet
- XXX.levelgen.structure.StructureSet$StructureSelectionEntry
+ XXX.levelgen.structure.StructureSpawnOverride
- XXX.levelgen.structure.StructureSpawnOverride$BoundingBoxType
+ XXX.levelgen.structure.StructureStart
- XXX.levelgen.structure.StructureType
+ XXX.levelgen.structure.TemplateStructurePiece
- XXX.levelgen.structure.TerrainAdjustment
+ XXX.levelgen.synth.BlendedNoise
- XXX.levelgen.synth.ImprovedNoise
+ XXX.levelgen.synth.NoiseUtils
- XXX.levelgen.synth.NormalNoise
+ XXX.levelgen.synth.NormalNoise$NoiseParameters
+ XXX.levelgen.synth.package-info
- XXX.levelgen.synth.PerlinNoise
+ XXX.levelgen.synth.PerlinSimplexNoise
- XXX.levelgen.synth.SimplexNoise
+ XXX.minecraft.advancements.Advancement
- XXX.minecraft.advancements.Advancement$Builder
+ XXX.minecraft.advancements.AdvancementList
- XXX.minecraft.advancements.AdvancementList$Listener
+ XXX.minecraft.advancements.AdvancementProgress
- XXX.minecraft.advancements.AdvancementProgress$Serializer
+ XXX.minecraft.advancements.AdvancementRewards
- XXX.minecraft.advancements.AdvancementRewards$Builder
+ XXX.minecraft.advancements.CriteriaTriggers
- XXX.minecraft.advancements.Criterion
+ XXX.minecraft.advancements.CriterionProgress
- XXX.minecraft.advancements.CriterionTrigger
+ XXX.minecraft.advancements.CriterionTrigger$Listener
- XXX.minecraft.advancements.CriterionTriggerInstance
+ XXX.minecraft.advancements.DisplayInfo
- XXX.minecraft.advancements.FrameType
- XXX.minecraft.advancements.package-info
+ XXX.minecraft.advancements.RequirementsStrategy
- XXX.minecraft.advancements.TreeNodePosition
+ XXX.minecraft.client.AttackIndicatorStatus
- XXX.minecraft.client.Camera
+ XXX.minecraft.client.Camera$NearPlane
- XXX.minecraft.client.CameraType
+ XXX.minecraft.client.ClientBrandRetriever
- XXX.minecraft.client.ClientRecipeBook
+ XXX.minecraft.client.ClientRecipeBook$1
- XXX.minecraft.client.CloudStatus
+ XXX.minecraft.client.ComponentCollector
- XXX.minecraft.client.DebugQueryHandler
+ XXX.minecraft.client.GameNarrator
- XXX.minecraft.client.GraphicsStatus
+ XXX.minecraft.client.GraphicsStatus$1
- XXX.minecraft.client.GuiMessage
+ XXX.minecraft.client.GuiMessage$Line
- XXX.minecraft.client.GuiMessageTag
+ XXX.minecraft.client.GuiMessageTag$Icon
- XXX.minecraft.client.HotbarManager
+ XXX.minecraft.client.InputType
+ XXX.minecraft.client.KeyboardHandler
- XXX.minecraft.client.KeyboardHandler$1
- XXX.minecraft.client.KeyMapping
+ XXX.minecraft.client.Minecraft
- XXX.minecraft.client.Minecraft$1
+ XXX.minecraft.client.Minecraft$ChatStatus
- XXX.minecraft.client.Minecraft$ChatStatus$1
+ XXX.minecraft.client.Minecraft$ChatStatus$2
- XXX.minecraft.client.Minecraft$ChatStatus$3
+ XXX.minecraft.client.Minecraft$ChatStatus$4
- XXX.minecraft.client.MouseHandler
+ XXX.minecraft.client.NarratorStatus
- XXX.minecraft.client.OptionInstance
+ XXX.minecraft.client.OptionInstance$AltEnum
- XXX.minecraft.client.OptionInstance$CaptionBasedToString
+ XXX.minecraft.client.OptionInstance$ClampingLazyMaxIntRange
- XXX.minecraft.client.OptionInstance$CycleableValueSet
+ XXX.minecraft.client.OptionInstance$CycleableValueSet$ValueSetter
- XXX.minecraft.client.OptionInstance$Enum
+ XXX.minecraft.client.OptionInstance$IntRange
- XXX.minecraft.client.OptionInstance$IntRangeBase
+ XXX.minecraft.client.OptionInstance$IntRangeBase$1
- XXX.minecraft.client.OptionInstance$LazyEnum
+ XXX.minecraft.client.OptionInstance$OptionInstanceSliderButton
- XXX.minecraft.client.OptionInstance$SliderableOrCyclableValueSet
+ XXX.minecraft.client.OptionInstance$SliderableValueSet
- XXX.minecraft.client.OptionInstance$TooltipSupplier
+ XXX.minecraft.client.OptionInstance$UnitDouble
- XXX.minecraft.client.OptionInstance$UnitDouble$1
+ XXX.minecraft.client.OptionInstance$ValueSet
- XXX.minecraft.client.Options
+ XXX.minecraft.client.Options$1
- XXX.minecraft.client.Options$2
+ XXX.minecraft.client.Options$3
- XXX.minecraft.client.Options$4
+ XXX.minecraft.client.Options$FieldAccess
+ XXX.minecraft.client.package-info
- XXX.minecraft.client.ParticleStatus
+ XXX.minecraft.client.PeriodicNotificationManager
- XXX.minecraft.client.PeriodicNotificationManager$Notification
+ XXX.minecraft.client.PeriodicNotificationManager$NotificationTask
- XXX.minecraft.client.PrioritizeChunkUpdates
+ XXX.minecraft.client.Realms32BitWarningStatus
- XXX.minecraft.client.RecipeBookCategories
+ XXX.minecraft.client.RecipeBookCategories$1
- XXX.minecraft.client.ResourceLoadStateTracker
+ XXX.minecraft.client.ResourceLoadStateTracker$RecoveryInfo
- XXX.minecraft.client.ResourceLoadStateTracker$ReloadReason
+ XXX.minecraft.client.ResourceLoadStateTracker$ReloadState
- XXX.minecraft.client.Screenshot
+ XXX.minecraft.client.StringSplitter
- XXX.minecraft.client.StringSplitter$1
+ XXX.minecraft.client.StringSplitter$FlatComponents
- XXX.minecraft.client.StringSplitter$LineBreakFinder
+ XXX.minecraft.client.StringSplitter$LineComponent
- XXX.minecraft.client.StringSplitter$LinePosConsumer
+ XXX.minecraft.client.StringSplitter$WidthLimitedCharSink
- XXX.minecraft.client.StringSplitter$WidthProvider
+ XXX.minecraft.client.Timer
- XXX.minecraft.client.ToggleKeyMapping
+ XXX.minecraft.client.User
- XXX.minecraft.client.User$Type
- XXX.minecraft.server.ServerFunctionManager$QueuedCommand
+ XXX.minecraft.server.ServerFunctionManager$TraceCallbacks
- XXX.minecraft.server.ServerInterface
+ XXX.minecraft.server.ServerScoreboard
- XXX.minecraft.server.ServerScoreboard$Method
+ XXX.minecraft.server.Services
- XXX.minecraft.server.TickTask
+ XXX.minecraft.server.WorldLoader
- XXX.minecraft.server.WorldLoader$DataLoadContext
+ XXX.minecraft.server.WorldLoader$DataLoadOutput
- XXX.minecraft.server.WorldLoader$InitConfig
+ XXX.minecraft.server.WorldLoader$PackConfig
- XXX.minecraft.server.WorldLoader$ResultFactory
+ XXX.minecraft.server.WorldLoader$WorldDataSupplier
- XXX.minecraft.server.WorldStem
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
- XXX.model.multipart.AndCondition
+ XXX.model.multipart.Condition
- XXX.model.multipart.KeyValueCondition
+ XXX.model.multipart.MultiPart
- XXX.model.multipart.MultiPart$Deserializer
+ XXX.model.multipart.OrCondition
- XXX.model.multipart.package-info
- XXX.model.multipart.Selector
+ XXX.model.multipart.Selector$Deserializer
+ XXX.mojang.math.Axis
- XXX.mojang.math.Constants
+ XXX.mojang.math.Divisor
- XXX.mojang.math.FieldsAreNonnullByDefault
+ XXX.mojang.math.GivensParameters
- XXX.mojang.math.MatrixUtil
+ XXX.mojang.math.MethodsReturnNonnullByDefault
- XXX.mojang.math.OctahedralGroup
+ XXX.mojang.math.OctahedralGroup$1
- XXX.mojang.math.package-info
- XXX.mojang.math.SymmetricGroup3
+ XXX.mojang.math.Transformation
+ XXX.mojang.realmsclient.KeyCombo
+ XXX.mojang.realmsclient.package-info
- XXX.mojang.realmsclient.RealmsMainScreen
+ XXX.mojang.realmsclient.RealmsMainScreen$1
- XXX.mojang.realmsclient.RealmsMainScreen$2
+ XXX.mojang.realmsclient.RealmsMainScreen$3
- XXX.mojang.realmsclient.RealmsMainScreen$4
+ XXX.mojang.realmsclient.RealmsMainScreen$5
- XXX.mojang.realmsclient.RealmsMainScreen$ButtonEntry
+ XXX.mojang.realmsclient.RealmsMainScreen$CloseButton
- XXX.mojang.realmsclient.RealmsMainScreen$CrossButton
+ XXX.mojang.realmsclient.RealmsMainScreen$Entry
- XXX.mojang.realmsclient.RealmsMainScreen$NewsButton
+ XXX.mojang.realmsclient.RealmsMainScreen$NotificationMessageEntry
- XXX.mojang.realmsclient.RealmsMainScreen$PendingInvitesButton
- XXX.mojang.realmsclient.RealmsMainScreen$RealmsCall
+ XXX.mojang.realmsclient.RealmsMainScreen$RealmSelectionList
+ XXX.mojang.realmsclient.RealmsMainScreen$ServerEntry
- XXX.mojang.realmsclient.RealmsMainScreen$TrialEntry
+ XXX.mojang.realmsclient.Unit
- XXX.monster.warden.package-info
- XXX.monster.warden.WardenAi
+ XXX.monster.warden.WardenSpawnTracker
+ XXX.multiplayer.chat.ChatListener
- XXX.multiplayer.chat.ChatListener$Message
+ XXX.multiplayer.chat.ChatLog
- XXX.multiplayer.chat.ChatTrustLevel
+ XXX.multiplayer.chat.ChatTrustLevel$1
- XXX.multiplayer.chat.LoggedChatEvent
+ XXX.multiplayer.chat.LoggedChatEvent$Type
- XXX.multiplayer.chat.LoggedChatMessage
+ XXX.multiplayer.chat.LoggedChatMessage$Player
- XXX.multiplayer.chat.LoggedChatMessage$System
+ XXX.multiplayer.chat.package-info
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
- XXX.player.inventory.Hotbar
+ XXX.player.inventory.package-info
- XXX.realmsclient.client.FileDownload
+ XXX.realmsclient.client.FileDownload$DownloadCountingOutputStream
- XXX.realmsclient.client.FileDownload$ProgressListener
+ XXX.realmsclient.client.FileDownload$ResourcePackProgressListener
- XXX.realmsclient.client.FileUpload
+ XXX.realmsclient.client.FileUpload$CustomInputStreamEntity
+ XXX.realmsclient.client.package-info
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
- XXX.realmsclient.dto.Backup
+ XXX.realmsclient.dto.BackupList
- XXX.realmsclient.dto.GuardedSerializer
+ XXX.realmsclient.dto.Ops
- XXX.realmsclient.dto.package-info
- XXX.realmsclient.dto.PendingInvite
+ XXX.realmsclient.dto.PendingInvitesList
- XXX.realmsclient.dto.PingResult
+ XXX.realmsclient.dto.PlayerInfo
- XXX.realmsclient.dto.RealmsDescriptionDto
+ XXX.realmsclient.dto.RealmsNews
- XXX.realmsclient.dto.RealmsNotification
+ XXX.realmsclient.dto.RealmsNotification$VisitUrl
- XXX.realmsclient.dto.RealmsServer
+ XXX.realmsclient.dto.RealmsServer$McoServerComparator
- XXX.realmsclient.dto.RealmsServer$State
+ XXX.realmsclient.dto.RealmsServer$WorldType
- XXX.realmsclient.dto.RealmsServerAddress
+ XXX.realmsclient.dto.RealmsServerList
- XXX.realmsclient.dto.RealmsServerPing
+ XXX.realmsclient.dto.RealmsServerPlayerList
- XXX.realmsclient.dto.RealmsServerPlayerLists
+ XXX.realmsclient.dto.RealmsText
- XXX.realmsclient.dto.RealmsWorldOptions
+ XXX.realmsclient.dto.RealmsWorldResetDto
- XXX.realmsclient.dto.ReflectionBasedSerialization
+ XXX.realmsclient.dto.RegionPingResult
- XXX.realmsclient.dto.ServerActivity
+ XXX.realmsclient.dto.ServerActivityList
- XXX.realmsclient.dto.Subscription
+ XXX.realmsclient.dto.Subscription$SubscriptionType
- XXX.realmsclient.dto.UploadInfo
+ XXX.realmsclient.dto.ValueObject
- XXX.realmsclient.dto.WorldDownload
+ XXX.realmsclient.dto.WorldTemplate
- XXX.realmsclient.dto.WorldTemplate$WorldTemplateType
+ XXX.realmsclient.dto.WorldTemplatePaginatedList
+ XXX.realmsclient.exception.package-info
+ XXX.realmsclient.exception.RealmsDefaultUncaughtExceptionHandler
- XXX.realmsclient.exception.RealmsHttpException
+ XXX.realmsclient.exception.RealmsServiceException
- XXX.realmsclient.exception.RetryCallException
- XXX.realmsclient.gui.ErrorCallback
- XXX.realmsclient.gui.package-info
+ XXX.realmsclient.gui.RealmsDataFetcher
- XXX.realmsclient.gui.RealmsNewsManager
+ XXX.realmsclient.gui.RealmsServerList
- XXX.realmsclient.gui.RealmsWorldSlotButton
+ XXX.realmsclient.gui.RealmsWorldSlotButton$Action
- XXX.realmsclient.gui.RealmsWorldSlotButton$State
+ XXX.realmsclient.gui.RowButton
- XXX.realmsclient.util.JsonUtils
+ XXX.realmsclient.util.LevelType
+ XXX.realmsclient.util.package-info
- XXX.realmsclient.util.RealmsPersistence
+ XXX.realmsclient.util.RealmsPersistence$RealmsPersistenceData
- XXX.realmsclient.util.RealmsTextureManager
+ XXX.realmsclient.util.RealmsTextureManager$RealmsTexture
- XXX.realmsclient.util.RealmsUtil
+ XXX.realmsclient.util.RealmsUtil$1
- XXX.realmsclient.util.TextRenderingUtils
+ XXX.realmsclient.util.TextRenderingUtils$Line
- XXX.realmsclient.util.TextRenderingUtils$LineSegment
+ XXX.realmsclient.util.UploadTokenCache
- XXX.realmsclient.util.WorldGenerationInfo
- XXX.renderer.block.BlockModelShaper
+ XXX.renderer.block.BlockRenderDispatcher
- XXX.renderer.block.BlockRenderDispatcher$1
+ XXX.renderer.block.LiquidBlockRenderer
- XXX.renderer.block.LiquidBlockRenderer$1
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
+ XXX.renderer.blockentity.BannerRenderer
- XXX.renderer.blockentity.BeaconRenderer
+ XXX.renderer.blockentity.BedRenderer
- XXX.renderer.blockentity.BellRenderer
+ XXX.renderer.blockentity.BlockEntityRenderDispatcher
- XXX.renderer.blockentity.BlockEntityRenderer
+ XXX.renderer.blockentity.BlockEntityRendererProvider
- XXX.renderer.blockentity.BlockEntityRendererProvider$Context
+ XXX.renderer.blockentity.BlockEntityRenderers
- XXX.renderer.blockentity.BrightnessCombiner
+ XXX.renderer.blockentity.BrushableBlockRenderer
- XXX.renderer.blockentity.BrushableBlockRenderer$1
+ XXX.renderer.blockentity.CampfireRenderer
- XXX.renderer.blockentity.ChestRenderer
+ XXX.renderer.blockentity.ConduitRenderer
- XXX.renderer.blockentity.DecoratedPotRenderer
+ XXX.renderer.blockentity.EnchantTableRenderer
- XXX.renderer.blockentity.HangingSignRenderer
+ XXX.renderer.blockentity.HangingSignRenderer$HangingSignModel
- XXX.renderer.blockentity.LecternRenderer
+ XXX.renderer.blockentity.package-info
+ XXX.renderer.blockentity.PistonHeadRenderer
- XXX.renderer.blockentity.ShulkerBoxRenderer
+ XXX.renderer.blockentity.SignRenderer
- XXX.renderer.blockentity.SignRenderer$SignModel
+ XXX.renderer.blockentity.SkullBlockRenderer
- XXX.renderer.blockentity.SpawnerRenderer
+ XXX.renderer.blockentity.StructureBlockRenderer
- XXX.renderer.blockentity.StructureBlockRenderer$1
+ XXX.renderer.blockentity.TheEndGatewayRenderer
- XXX.renderer.blockentity.TheEndPortalRenderer
- XXX.renderer.chunk.ChunkRenderDispatcher
+ XXX.renderer.chunk.ChunkRenderDispatcher$ChunkTaskResult
- XXX.renderer.chunk.ChunkRenderDispatcher$CompiledChunk
+ XXX.renderer.chunk.ChunkRenderDispatcher$CompiledChunk$1
- XXX.renderer.chunk.ChunkRenderDispatcher$RenderChunk
+ XXX.renderer.chunk.ChunkRenderDispatcher$RenderChunk$ChunkCompileTask
- XXX.renderer.chunk.ChunkRenderDispatcher$RenderChunk$RebuildTask
+ XXX.renderer.chunk.ChunkRenderDispatcher$RenderChunk$RebuildTask$CompileResults
- XXX.renderer.chunk.ChunkRenderDispatcher$RenderChunk$ResortTransparencyTask
- XXX.renderer.chunk.package-info
+ XXX.renderer.chunk.RenderChunk
- XXX.renderer.chunk.RenderChunkRegion
+ XXX.renderer.chunk.RenderRegionCache
- XXX.renderer.chunk.RenderRegionCache$ChunkInfo
+ XXX.renderer.chunk.VisGraph
- XXX.renderer.chunk.VisGraph$1
+ XXX.renderer.chunk.VisibilitySet
+ XXX.renderer.culling.Frustum
- XXX.renderer.culling.package-info
+ XXX.renderer.debug.BeeDebugRenderer
- XXX.renderer.debug.BeeDebugRenderer$BeeInfo
+ XXX.renderer.debug.BeeDebugRenderer$HiveInfo
- XXX.renderer.debug.BrainDebugRenderer
+ XXX.renderer.debug.BrainDebugRenderer$BrainDump
- XXX.renderer.debug.BrainDebugRenderer$PoiInfo
+ XXX.renderer.debug.ChunkBorderRenderer
- XXX.renderer.debug.ChunkDebugRenderer
+ XXX.renderer.debug.ChunkDebugRenderer$ChunkData
- XXX.renderer.debug.CollisionBoxRenderer
+ XXX.renderer.debug.DebugRenderer
- XXX.renderer.debug.DebugRenderer$SimpleDebugRenderer
+ XXX.renderer.debug.GameEventListenerRenderer
- XXX.renderer.debug.GameEventListenerRenderer$TrackedGameEvent
+ XXX.renderer.debug.GameEventListenerRenderer$TrackedListener
- XXX.renderer.debug.GameTestDebugRenderer
+ XXX.renderer.debug.GameTestDebugRenderer$Marker
- XXX.renderer.debug.GoalSelectorDebugRenderer
+ XXX.renderer.debug.GoalSelectorDebugRenderer$DebugGoal
- XXX.renderer.debug.HeightMapRenderer
+ XXX.renderer.debug.HeightMapRenderer$1
- XXX.renderer.debug.LightDebugRenderer
- XXX.renderer.debug.LightSectionDebugRenderer$1
- XXX.rule.blockentity.AppendLoot
+ XXX.rule.blockentity.AppendStatic
- XXX.rule.blockentity.Clear
- XXX.rule.blockentity.package-info
+ XXX.rule.blockentity.Passthrough
- XXX.rule.blockentity.RuleBlockEntityModifier
+ XXX.rule.blockentity.RuleBlockEntityModifierType
- XXX.screens.multiplayer.JoinMultiplayerScreen
+ XXX.screens.multiplayer.package-info
+ XXX.screens.multiplayer.Realms32bitWarningScreen
- XXX.screens.multiplayer.SafetyScreen
+ XXX.screens.multiplayer.ServerSelectionList
- XXX.screens.multiplayer.ServerSelectionList$Entry
+ XXX.screens.multiplayer.ServerSelectionList$LANHeader
- XXX.screens.multiplayer.ServerSelectionList$NetworkServerEntry
+ XXX.screens.multiplayer.ServerSelectionList$OnlineServerEntry
- XXX.screens.multiplayer.WarningScreen
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
+ XXX.screens.reporting.ChatReportScreen
- XXX.screens.reporting.ChatReportScreen$DiscardReportWarningScreen
+ XXX.screens.reporting.ChatSelectionLogFiller
- XXX.screens.reporting.ChatSelectionLogFiller$Output
+ XXX.screens.reporting.ChatSelectionScreen
- XXX.screens.reporting.ChatSelectionScreen$ChatSelectionList
+ XXX.screens.reporting.ChatSelectionScreen$ChatSelectionList$DividerEntry
- XXX.screens.reporting.ChatSelectionScreen$ChatSelectionList$Entry
+ XXX.screens.reporting.ChatSelectionScreen$ChatSelectionList$Heading
- XXX.screens.reporting.ChatSelectionScreen$ChatSelectionList$MessageEntry
+ XXX.screens.reporting.ChatSelectionScreen$ChatSelectionList$MessageHeadingEntry
- XXX.screens.reporting.ChatSelectionScreen$ChatSelectionList$PaddingEntry
- XXX.screens.reporting.package-info
+ XXX.screens.reporting.ReportReasonSelectionScreen
- XXX.screens.reporting.ReportReasonSelectionScreen$ReasonSelectionList
+ XXX.screens.reporting.ReportReasonSelectionScreen$ReasonSelectionList$Entry
+ XXX.screens.social.package-info
+ XXX.screens.social.PlayerEntry
- XXX.screens.social.PlayerEntry$1
+ XXX.screens.social.PlayerEntry$2
- XXX.screens.social.PlayerEntry$3
+ XXX.screens.social.PlayerSocialManager
- XXX.screens.social.SocialInteractionsPlayerList
+ XXX.screens.social.SocialInteractionsScreen
- XXX.screens.social.SocialInteractionsScreen$1
+ XXX.screens.social.SocialInteractionsScreen$2
- XXX.screens.social.SocialInteractionsScreen$Page
- XXX.screens.telemetry.package-info
- XXX.screens.telemetry.TelemetryEventWidget
+ XXX.screens.telemetry.TelemetryEventWidget$Content
- XXX.screens.telemetry.TelemetryEventWidget$ContentBuilder
+ XXX.screens.telemetry.TelemetryInfoScreen
+ XXX.screens.worldselection.ConfirmExperimentalFeaturesScreen
- XXX.screens.worldselection.ConfirmExperimentalFeaturesScreen$DetailsScreen
+ XXX.screens.worldselection.ConfirmExperimentalFeaturesScreen$DetailsScreen$PackList
- XXX.screens.worldselection.ConfirmExperimentalFeaturesScreen$DetailsScreen$PackListEntry
+ XXX.screens.worldselection.CreateWorldScreen
- XXX.screens.worldselection.CreateWorldScreen$DataPackReloadCookie
+ XXX.screens.worldselection.CreateWorldScreen$GameTab
- XXX.screens.worldselection.CreateWorldScreen$MoreTab
+ XXX.screens.worldselection.CreateWorldScreen$WorldTab
- XXX.screens.worldselection.CreateWorldScreen$WorldTab$1
+ XXX.screens.worldselection.CreateWorldScreen$WorldTab$2
- XXX.screens.worldselection.EditGameRulesScreen
+ XXX.screens.worldselection.EditGameRulesScreen$BooleanRuleEntry
- XXX.screens.worldselection.EditGameRulesScreen$CategoryRuleEntry
+ XXX.screens.worldselection.EditGameRulesScreen$CategoryRuleEntry$1
- XXX.screens.worldselection.EditGameRulesScreen$EntryFactory
+ XXX.screens.worldselection.EditGameRulesScreen$GameRuleEntry
- XXX.screens.worldselection.EditGameRulesScreen$IntegerRuleEntry
+ XXX.screens.worldselection.EditGameRulesScreen$RuleEntry
- XXX.screens.worldselection.EditGameRulesScreen$RuleList
+ XXX.screens.worldselection.EditGameRulesScreen$RuleList$1
- XXX.screens.worldselection.EditWorldScreen
+ XXX.screens.worldselection.ExperimentsScreen
- XXX.screens.worldselection.OptimizeWorldScreen
- XXX.screens.worldselection.package-info
+ XXX.screens.worldselection.PresetEditor
- XXX.screens.worldselection.SelectWorldScreen
+ XXX.screens.worldselection.SwitchGrid
- XXX.screens.worldselection.SwitchGrid$Builder
+ XXX.screens.worldselection.SwitchGrid$InfoUnderneathSettings
- XXX.screens.worldselection.SwitchGrid$LabeledSwitch
+ XXX.screens.worldselection.SwitchGrid$SwitchBuilder
- XXX.screens.worldselection.WorldCreationContext
+ XXX.screens.worldselection.WorldCreationContext$DimensionsUpdater
- XXX.screens.worldselection.WorldCreationContext$OptionsModifier
+ XXX.screens.worldselection.WorldCreationUiState
- XXX.screens.worldselection.WorldCreationUiState$SelectedGameMode
+ XXX.screens.worldselection.WorldCreationUiState$WorldTypeEntry
- XXX.screens.worldselection.WorldOpenFlows
+ XXX.screens.worldselection.WorldOpenFlows$1Data
- XXX.screens.worldselection.WorldSelectionList
+ XXX.screens.worldselection.WorldSelectionList$Entry
- XXX.screens.worldselection.WorldSelectionList$LoadingHeader
+ XXX.screens.worldselection.WorldSelectionList$WorldListEntry
+ XXX.server.advancements.AdvancementVisibilityEvaluator
- XXX.server.advancements.AdvancementVisibilityEvaluator$Output
+ XXX.server.advancements.AdvancementVisibilityEvaluator$VisibilityRule
- XXX.server.advancements.package-info
+ XXX.server.bossevents.CustomBossEvent
- XXX.server.bossevents.CustomBossEvents
+ XXX.server.bossevents.package-info
- XXX.server.chase.ChaseClient
+ XXX.server.chase.ChaseClient$TeleportTarget
- XXX.server.chase.ChaseServer
+ XXX.server.chase.ChaseServer$PlayerPosition
- XXX.server.chase.package-info
+ XXX.server.commands.AdvancementCommands
- XXX.server.commands.AdvancementCommands$Action
+ XXX.server.commands.AdvancementCommands$Action$1
- XXX.server.commands.AdvancementCommands$Action$2
+ XXX.server.commands.AdvancementCommands$Mode
- XXX.server.commands.AttributeCommand
+ XXX.server.commands.BanIpCommands
- XXX.server.commands.BanListCommands
+ XXX.server.commands.BanPlayerCommands
- XXX.server.commands.BossBarCommands
+ XXX.server.commands.ChaseCommand
- XXX.server.commands.ClearInventoryCommands
+ XXX.server.commands.CloneCommands
- XXX.server.commands.CloneCommands$CloneBlockInfo
+ XXX.server.commands.CloneCommands$CommandFunction
- XXX.server.commands.CloneCommands$DimensionAndPosition
+ XXX.server.commands.CloneCommands$Mode
- XXX.server.commands.DamageCommand
+ XXX.server.commands.DataPackCommand
- XXX.server.commands.DataPackCommand$Inserter
- XXX.server.commands.DebugCommand
+ XXX.server.commands.DebugCommand$Tracer
- XXX.server.commands.DebugMobSpawningCommand
+ XXX.server.commands.DebugPathCommand
- XXX.server.commands.DefaultGameModeCommands
+ XXX.server.commands.DeOpCommands
+ XXX.server.commands.DifficultyCommand
- XXX.server.commands.EffectCommands
+ XXX.server.commands.EmoteCommands
- XXX.server.commands.EnchantCommand
+ XXX.server.commands.ExecuteCommand
- XXX.server.commands.ExecuteCommand$CommandNumericPredicate
+ XXX.server.commands.ExecuteCommand$CommandPredicate
- XXX.server.commands.ExperienceCommand
+ XXX.server.commands.ExperienceCommand$Type
- XXX.server.commands.FillBiomeCommand
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
+ XXX.server.commands.JfrCommand
- XXX.server.commands.KickCommand
+ XXX.server.commands.KillCommand
- XXX.server.commands.ListPlayersCommand
+ XXX.server.commands.LocateCommand
- XXX.server.commands.LootCommand
+ XXX.server.commands.LootCommand$Callback
- XXX.server.commands.LootCommand$DropConsumer
+ XXX.server.commands.LootCommand$TailProvider
- XXX.server.commands.MsgCommand
+ XXX.server.commands.OpCommand
- XXX.server.commands.PardonCommand
+ XXX.server.commands.PardonIpCommand
- XXX.server.commands.ParticleCommand
+ XXX.server.commands.PerfCommand
- XXX.server.commands.PlaceCommand
+ XXX.server.commands.PlaySoundCommand
- XXX.server.commands.PublishCommand
+ XXX.server.commands.RaidCommand
- XXX.server.commands.RecipeCommand
+ XXX.server.commands.ReloadCommand
- XXX.server.commands.ResetChunksCommand
- XXX.spectator.categories.package-info
- XXX.spectator.categories.SpectatorPage
+ XXX.spectator.categories.TeleportToPlayerMenuCategory
- XXX.spectator.categories.TeleportToTeamMenuCategory
+ XXX.spectator.categories.TeleportToTeamMenuCategory$TeamSelectionItem
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
+ XXX.structure.pools.JigsawPlacement$PieceState
- XXX.structure.pools.JigsawPlacement$Placer
+ XXX.structure.pools.LegacySinglePoolElement
- XXX.structure.pools.ListPoolElement
- XXX.structure.pools.package-info
+ XXX.structure.pools.SinglePoolElement
- XXX.structure.pools.StructurePoolElement
+ XXX.structure.pools.StructurePoolElementType
- XXX.structure.pools.StructureTemplatePool
+ XXX.structure.pools.StructureTemplatePool$Projection
+ XXX.structure.structures.BuriedTreasurePieces
- XXX.structure.structures.BuriedTreasurePieces$BuriedTreasurePiece
+ XXX.structure.structures.BuriedTreasureStructure
- XXX.structure.structures.DesertPyramidPiece
+ XXX.structure.structures.DesertPyramidStructure
- XXX.structure.structures.EndCityPieces
+ XXX.structure.structures.EndCityPieces$1
- XXX.structure.structures.EndCityPieces$2
+ XXX.structure.structures.EndCityPieces$3
- XXX.structure.structures.EndCityPieces$4
+ XXX.structure.structures.EndCityPieces$EndCityPiece
- XXX.structure.structures.EndCityPieces$SectionGenerator
+ XXX.structure.structures.EndCityStructure
- XXX.structure.structures.IglooPieces
+ XXX.structure.structures.IglooPieces$IglooPiece
- XXX.structure.structures.IglooStructure
+ XXX.structure.structures.JigsawStructure
- XXX.structure.structures.JigsawStructure$1
+ XXX.structure.structures.JungleTemplePiece
- XXX.structure.structures.JungleTemplePiece$MossStoneSelector
+ XXX.structure.structures.JungleTempleStructure
- XXX.structure.structures.MineshaftPieces
+ XXX.structure.structures.MineshaftPieces$1
- XXX.structure.structures.MineshaftPieces$MineShaftCorridor
+ XXX.structure.structures.MineshaftPieces$MineShaftCrossing
- XXX.structure.structures.MineshaftPieces$MineShaftPiece
+ XXX.structure.structures.MineshaftPieces$MineShaftRoom
- XXX.structure.structures.MineshaftPieces$MineShaftStairs
+ XXX.structure.structures.MineshaftStructure
- XXX.structure.structures.MineshaftStructure$Type
+ XXX.structure.structures.NetherFortressPieces
- XXX.structure.structures.NetherFortressPieces$1
+ XXX.structure.structures.NetherFortressPieces$BridgeCrossing
- XXX.structure.structures.NetherFortressPieces$BridgeEndFiller
+ XXX.structure.structures.NetherFortressPieces$BridgeStraight
- XXX.structure.structures.NetherFortressPieces$CastleCorridorStairsPiece
+ XXX.structure.structures.NetherFortressPieces$CastleCorridorTBalconyPiece
- XXX.structure.structures.NetherFortressPieces$CastleEntrance
+ XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorCrossingPiece
- XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorLeftTurnPiece
+ XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorPiece
- XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorRightTurnPiece
+ XXX.structure.structures.NetherFortressPieces$CastleStalkRoom
- XXX.structure.structures.NetherFortressPieces$MonsterThrone
+ XXX.structure.structures.NetherFortressPieces$NetherBridgePiece
- XXX.structure.structures.NetherFortressPieces$PieceWeight
+ XXX.structure.structures.NetherFortressPieces$RoomCrossing
- XXX.structure.structures.NetherFortressPieces$StairsRoom
+ XXX.structure.structures.NetherFortressPieces$StartPiece
- XXX.structure.structures.NetherFortressStructure
+ XXX.structure.structures.NetherFossilPieces
- XXX.structure.structures.NetherFossilPieces$NetherFossilPiece
+ XXX.structure.structures.NetherFossilStructure
- XXX.structure.structures.OceanMonumentPieces
+ XXX.structure.structures.OceanMonumentPieces$1
- XXX.structure.structures.OceanMonumentPieces$FitDoubleXRoom
+ XXX.structure.structures.OceanMonumentPieces$FitDoubleXYRoom
- XXX.structure.structures.OceanMonumentPieces$FitDoubleYRoom
+ XXX.structure.structures.OceanMonumentPieces$FitDoubleYZRoom
- XXX.structure.structures.OceanMonumentPieces$FitDoubleZRoom
+ XXX.structure.structures.OceanMonumentPieces$FitSimpleRoom
- XXX.structure.structures.OceanMonumentPieces$FitSimpleTopRoom
+ XXX.structure.structures.OceanMonumentPieces$MonumentBuilding
- XXX.structure.structures.OceanMonumentPieces$MonumentRoomFitter
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentCoreRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleXRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleXYRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleYRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleYZRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleZRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentEntryRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentPenthouse
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentPiece
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentSimpleRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentSimpleTopRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentWingRoom
+ XXX.structure.structures.OceanMonumentPieces$RoomDefinition
- XXX.structure.structures.OceanMonumentStructure
+ XXX.structure.structures.OceanRuinPieces
- XXX.structure.structures.OceanRuinPieces$1
+ XXX.structure.structures.OceanRuinPieces$OceanRuinPiece
- XXX.structure.structures.OceanRuinStructure
+ XXX.structure.structures.OceanRuinStructure$Type
- XXX.structure.structures.package-info
- XXX.structure.structures.RuinedPortalPiece
+ XXX.structure.structures.RuinedPortalPiece$Properties
- XXX.structure.structures.RuinedPortalPiece$VerticalPlacement
+ XXX.structure.structures.RuinedPortalStructure
- XXX.structure.structures.RuinedPortalStructure$Setup
+ XXX.structure.structures.ShipwreckPieces
- XXX.structure.structures.ShipwreckPieces$ShipwreckPiece
+ XXX.structure.structures.ShipwreckStructure
- XXX.structure.structures.StrongholdPieces
+ XXX.structure.structures.StrongholdPieces$1
- XXX.structure.structures.StrongholdPieces$2
+ XXX.structure.structures.StrongholdPieces$3
- XXX.structure.structures.StrongholdPieces$ChestCorridor
+ XXX.structure.structures.StrongholdPieces$FillerCorridor
- XXX.structure.structures.StrongholdPieces$FiveCrossing
+ XXX.structure.structures.StrongholdPieces$LeftTurn
- XXX.structure.structures.StrongholdPieces$Library
+ XXX.structure.structures.StrongholdPieces$PieceWeight
- XXX.structure.structures.StrongholdPieces$PortalRoom
+ XXX.structure.structures.StrongholdPieces$PrisonHall
- XXX.structure.structures.StrongholdPieces$RightTurn
+ XXX.structure.structures.StrongholdPieces$RoomCrossing
- XXX.structure.structures.StrongholdPieces$SmoothStoneSelector
+ XXX.structure.structures.StrongholdPieces$StairsDown
- XXX.structure.structures.StrongholdPieces$StartPiece
+ XXX.structure.structures.StrongholdPieces$Straight
- XXX.structure.structures.StrongholdPieces$StraightStairsDown
+ XXX.structure.structures.StrongholdPieces$StrongholdPiece
- XXX.structure.structures.StrongholdPieces$StrongholdPiece$SmallDoorType
+ XXX.structure.structures.StrongholdPieces$Turn
- XXX.structure.structures.StrongholdStructure
+ XXX.structure.structures.SwampHutPiece
- XXX.structure.structures.SwampHutStructure
+ XXX.structure.structures.WoodlandMansionPieces
- XXX.structure.structures.WoodlandMansionPieces$FirstFloorRoomCollection
+ XXX.structure.structures.WoodlandMansionPieces$FloorRoomCollection
- XXX.structure.structures.WoodlandMansionPieces$MansionGrid
+ XXX.structure.structures.WoodlandMansionPieces$MansionPiecePlacer
- XXX.structure.structures.WoodlandMansionPieces$PlacementData
+ XXX.structure.structures.WoodlandMansionPieces$SecondFloorRoomCollection
- XXX.structure.structures.WoodlandMansionPieces$SimpleGrid
+ XXX.structure.structures.WoodlandMansionPieces$ThirdFloorRoomCollection
- XXX.structure.structures.WoodlandMansionPieces$WoodlandMansionPiece
+ XXX.structure.structures.WoodlandMansionStructure
+ XXX.structure.templatesystem.AlwaysTrueTest
- XXX.structure.templatesystem.AxisAlignedLinearPosTest
+ XXX.structure.templatesystem.BlackstoneReplaceProcessor
- XXX.structure.templatesystem.BlockAgeProcessor
+ XXX.structure.templatesystem.BlockIgnoreProcessor
- XXX.structure.templatesystem.BlockMatchTest
+ XXX.structure.templatesystem.BlockRotProcessor
- XXX.structure.templatesystem.BlockStateMatchTest
+ XXX.structure.templatesystem.CappedProcessor
- XXX.structure.templatesystem.GravityProcessor
+ XXX.structure.templatesystem.JigsawReplacementProcessor
- XXX.structure.templatesystem.LavaSubmergedBlockProcessor
+ XXX.structure.templatesystem.LinearPosTest
- XXX.structure.templatesystem.NopProcessor
+ XXX.structure.templatesystem.package-info
+ XXX.structure.templatesystem.PosAlwaysTrueTest
- XXX.structure.templatesystem.PosRuleTest
+ XXX.structure.templatesystem.PosRuleTestType
- XXX.structure.templatesystem.ProcessorRule
+ XXX.structure.templatesystem.ProtectedBlockProcessor
- XXX.structure.templatesystem.RandomBlockMatchTest
+ XXX.structure.templatesystem.RandomBlockStateMatchTest
- XXX.structure.templatesystem.RuleProcessor
+ XXX.structure.templatesystem.RuleTest
- XXX.structure.templatesystem.RuleTestType
+ XXX.structure.templatesystem.StructurePlaceSettings
- XXX.structure.templatesystem.StructureProcessor
+ XXX.structure.templatesystem.StructureProcessorList
- XXX.structure.templatesystem.StructureProcessorType
+ XXX.structure.templatesystem.StructureTemplate
- XXX.structure.templatesystem.StructureTemplate$1
+ XXX.structure.templatesystem.StructureTemplate$Palette
- XXX.structure.templatesystem.StructureTemplate$SimplePalette
+ XXX.structure.templatesystem.StructureTemplate$StructureBlockInfo
- XXX.structure.templatesystem.StructureTemplate$StructureEntityInfo
+ XXX.structure.templatesystem.StructureTemplateManager
- XXX.structure.templatesystem.StructureTemplateManager$InputStreamOpener
+ XXX.structure.templatesystem.StructureTemplateManager$Source
- XXX.structure.templatesystem.TagMatchTest
- XXX.util.datafix.package-info
- XXX.util.task.CloseServerTask
+ XXX.util.task.ConnectTask
- XXX.util.task.DownloadTask
+ XXX.util.task.GetServerDetailsTask
- XXX.util.task.LongRunningTask
+ XXX.util.task.OpenServerTask
+ XXX.util.task.package-info
- XXX.util.task.ResettingGeneratedWorldTask
+ XXX.util.task.ResettingTemplateWorldTask
- XXX.util.task.ResettingWorldTask
+ XXX.util.task.RestoreTask
- XXX.util.task.SwitchMinigameTask
+ XXX.util.task.SwitchSlotTask
- XXX.util.task.WorldCreationTask
+ XXX.world.entity.package-info
+ XXX.world.flag.FeatureElement
- XXX.world.flag.FeatureFlag
+ XXX.world.flag.FeatureFlagRegistry
- XXX.world.flag.FeatureFlagRegistry$Builder
+ XXX.world.flag.FeatureFlags
+ XXX.world.flag.FeatureFlagSet
- XXX.world.flag.FeatureFlagUniverse
- XXX.world.flag.package-info
+ XXX.world.food.FoodConstants
- XXX.world.food.FoodData
+ XXX.world.food.FoodProperties
- XXX.world.food.FoodProperties$Builder
+ XXX.world.food.Foods
- XXX.world.food.package-info
+ XXX.world.inventory.AbstractContainerMenu
- XXX.world.inventory.AbstractContainerMenu$1
+ XXX.world.inventory.AbstractFurnaceMenu
- XXX.world.inventory.AnvilMenu
+ XXX.world.inventory.AnvilMenu$1
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
+ XXX.world.inventory.ClickAction
- XXX.world.inventory.ClickType
+ XXX.world.inventory.ContainerData
- XXX.world.inventory.ContainerLevelAccess
+ XXX.world.inventory.ContainerLevelAccess$1
- XXX.world.inventory.ContainerLevelAccess$2
+ XXX.world.inventory.ContainerListener
- XXX.world.inventory.ContainerSynchronizer
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
+ XXX.world.inventory.ItemCombinerMenu
- XXX.world.inventory.ItemCombinerMenu$1
+ XXX.world.inventory.ItemCombinerMenu$2
- XXX.world.inventory.ItemCombinerMenu$3
+ XXX.world.inventory.ItemCombinerMenuSlotDefinition
- XXX.world.inventory.ItemCombinerMenuSlotDefinition$Builder
+ XXX.world.inventory.ItemCombinerMenuSlotDefinition$SlotDefinition
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
+ XXX.world.inventory.package-info
+ XXX.world.inventory.PlayerEnderChestContainer
- XXX.world.inventory.RecipeBookMenu
+ XXX.world.inventory.RecipeBookType
- XXX.world.inventory.RecipeHolder
+ XXX.world.inventory.ResultContainer
- XXX.world.inventory.ResultSlot
+ XXX.world.inventory.ShulkerBoxMenu
- XXX.world.inventory.ShulkerBoxSlot
+ XXX.world.inventory.SimpleContainerData
- XXX.world.inventory.Slot
+ XXX.world.inventory.SmithingMenu
- XXX.world.inventory.SmokerMenu
+ XXX.world.inventory.StackedContentsCompatible
- XXX.world.inventory.StonecutterMenu
+ XXX.world.inventory.StonecutterMenu$1
- XXX.world.inventory.StonecutterMenu$2
+ XXX.world.item.AdventureModeCheck
- XXX.world.item.AirItem
+ XXX.world.item.ArmorItem
- XXX.world.item.ArmorItem$1
+ XXX.world.item.ArmorItem$Type
- XXX.world.item.ArmorMaterial
+ XXX.world.item.ArmorMaterials
- XXX.world.item.ArmorStandItem
+ XXX.world.item.ArrowItem
- XXX.world.item.AxeItem
+ XXX.world.item.BannerItem
- XXX.world.item.BannerPatternItem
+ XXX.world.item.BedItem
- XXX.world.item.BlockItem
+ XXX.world.item.BoatItem
- XXX.world.item.BoneMealItem
+ XXX.world.item.BookItem
- XXX.world.item.BottleItem
+ XXX.world.item.BowItem
- XXX.world.item.BowlFoodItem
+ XXX.world.item.BrushItem
- XXX.world.item.BrushItem$1
+ XXX.world.item.BrushItem$DustParticlesDelta
- XXX.world.item.BucketItem
+ XXX.world.item.BundleItem
- XXX.world.item.ChorusFruitItem
+ XXX.world.item.CompassItem
- XXX.world.item.ComplexItem
+ XXX.world.item.CreativeModeTab
- XXX.world.item.CreativeModeTab$1
+ XXX.world.item.CreativeModeTab$Builder
- XXX.world.item.CreativeModeTab$DisplayItemsGenerator
+ XXX.world.item.CreativeModeTab$ItemDisplayBuilder
- XXX.world.item.CreativeModeTab$ItemDisplayParameters
+ XXX.world.item.CreativeModeTab$Output
- XXX.world.item.CreativeModeTab$Row
+ XXX.world.item.CreativeModeTab$TabVisibility
- XXX.world.item.CreativeModeTab$Type
+ XXX.world.item.CreativeModeTabs
- XXX.world.item.CrossbowItem
+ XXX.world.item.DebugStickItem
- XXX.world.item.DiggerItem
+ XXX.world.item.DiscFragmentItem
- XXX.world.item.DispensibleContainerItem
+ XXX.world.item.DoubleHighBlockItem
- XXX.world.item.DyeableArmorItem
+ XXX.world.item.DyeableHorseArmorItem
- XXX.world.item.DyeableLeatherItem
- XXX.world.item.DyeColor
+ XXX.world.item.DyeItem
+ XXX.world.item.EggItem
- XXX.world.item.ElytraItem
+ XXX.world.item.EmptyMapItem
- XXX.world.item.EnchantedBookItem
+ XXX.world.item.EnchantedGoldenAppleItem
- XXX.world.item.EndCrystalItem
+ XXX.world.item.EnderEyeItem
- XXX.world.item.EnderpearlItem
+ XXX.world.item.Equipable
- XXX.world.item.ExperienceBottleItem
+ XXX.world.item.FireChargeItem
- XXX.world.item.FireworkRocketItem
+ XXX.world.item.FireworkRocketItem$Shape
- XXX.world.item.FireworkStarItem
+ XXX.world.item.FishingRodItem
- XXX.world.item.FlintAndSteelItem
+ XXX.world.item.FoodOnAStickItem
- XXX.world.item.GameMasterBlockItem
+ XXX.world.item.GlowInkSacItem
- XXX.world.item.HangingEntityItem
+ XXX.world.item.HangingSignItem
- XXX.world.item.HoeItem
+ XXX.world.item.HoneyBottleItem
- XXX.world.item.HoneycombItem
+ XXX.world.item.HorseArmorItem
- XXX.world.item.InkSacItem
+ XXX.world.item.Instrument
- XXX.world.item.InstrumentItem
+ XXX.world.item.Instruments
- XXX.world.item.Item
+ XXX.world.item.Item$1
- XXX.world.item.Item$Properties
+ XXX.world.item.ItemCooldowns
- XXX.world.item.ItemCooldowns$CooldownInstance
+ XXX.world.item.ItemDisplayContext
- XXX.world.item.ItemFrameItem
+ XXX.world.item.ItemNameBlockItem
+ XXX.world.item.Items
- XXX.world.item.ItemStack
+ XXX.world.item.ItemStack$TooltipPart
- XXX.world.item.ItemStackLinkedSet
+ XXX.world.item.ItemStackLinkedSet$1
- XXX.world.item.ItemUtils
- XXX.world.item.KnowledgeBookItem
+ XXX.world.item.LeadItem
- XXX.world.item.LingeringPotionItem
+ XXX.world.item.MapItem
- XXX.world.item.MilkBucketItem
+ XXX.world.item.MinecartItem
- XXX.world.item.MinecartItem$1
+ XXX.world.item.MobBucketItem
- XXX.world.item.NameTagItem
- XXX.world.item.package-info
+ XXX.world.item.PickaxeItem
- XXX.world.item.PlaceOnWaterBlockItem
+ XXX.world.item.PlayerHeadItem
- XXX.world.item.PotionItem
+ XXX.world.item.ProjectileWeaponItem
- XXX.world.item.Rarity
+ XXX.world.item.RecordItem
- XXX.world.item.SaddleItem
+ XXX.world.item.ScaffoldingBlockItem
- XXX.world.item.ServerItemCooldowns
+ XXX.world.item.ShearsItem
- XXX.world.item.ShieldItem
+ XXX.world.item.ShovelItem
- XXX.world.item.SignApplicator
+ XXX.world.item.SignItem
- XXX.world.item.SimpleFoiledItem
+ XXX.world.item.SmithingTemplateItem
- XXX.world.item.SnowballItem
+ XXX.world.item.SolidBucketItem
- XXX.world.item.SpawnEggItem
+ XXX.world.item.SpectralArrowItem
- XXX.world.item.SplashPotionItem
+ XXX.world.item.SpyglassItem
- XXX.world.item.StandingAndWallBlockItem
+ XXX.world.item.SuspiciousStewItem
- XXX.world.item.SwordItem
+ XXX.world.item.ThrowablePotionItem
- XXX.world.item.Tier
+ XXX.world.item.TieredItem
- XXX.world.item.Tiers
+ XXX.world.item.TippedArrowItem
- XXX.world.item.TooltipFlag
+ XXX.world.item.TooltipFlag$Default
- XXX.world.item.TridentItem
+ XXX.world.item.UseAnim
- XXX.world.item.Vanishable
+ XXX.world.item.WritableBookItem
- XXX.world.item.WrittenBookItem
+ XXX.world.level.BaseCommandBlock
- XXX.world.level.BaseSpawner
+ XXX.world.level.BlockAndTintGetter
- XXX.world.level.BlockCollisions
+ XXX.world.level.BlockEventData
- XXX.world.level.BlockGetter
+ XXX.world.level.ChunkPos
- XXX.world.level.ChunkPos$1
+ XXX.world.level.ClipBlockStateContext
- XXX.world.level.ClipContext
+ XXX.world.level.ClipContext$Block
- XXX.world.level.ClipContext$Fluid
+ XXX.world.level.ClipContext$ShapeGetter
- XXX.world.level.CollisionGetter
+ XXX.world.level.ColorResolver
- XXX.world.level.CommonLevelAccessor
+ XXX.world.level.CustomSpawner
- XXX.world.level.DataPackConfig
+ XXX.world.level.EmptyBlockGetter
- XXX.world.level.EntityBasedExplosionDamageCalculator
+ XXX.world.level.EntityGetter
- XXX.world.level.Explosion
+ XXX.world.level.Explosion$BlockInteraction
- XXX.world.level.ExplosionDamageCalculator
+ XXX.world.level.FoliageColor
- XXX.world.level.ForcedChunksSavedData
+ XXX.world.level.GameRules
- XXX.world.level.GameRules$BooleanValue
+ XXX.world.level.GameRules$Category
- XXX.world.level.GameRules$GameRuleTypeVisitor
+ XXX.world.level.GameRules$IntegerValue
- XXX.world.level.GameRules$Key
+ XXX.world.level.GameRules$Type
- XXX.world.level.GameRules$Value
+ XXX.world.level.GameRules$VisitorCaller
- XXX.world.level.GameType
+ XXX.world.level.GrassColor
- XXX.world.level.ItemLike
+ XXX.world.level.Level
- XXX.world.level.Level$1
+ XXX.world.level.Level$2
- XXX.world.level.Level$ExplosionInteraction
+ XXX.world.level.LevelAccessor
- XXX.world.level.LevelHeightAccessor
+ XXX.world.level.LevelHeightAccessor$1
- XXX.world.level.LevelReader
+ XXX.world.level.LevelSettings
+ XXX.world.level.LevelSimulatedReader
- XXX.world.level.LevelSimulatedRW
- XXX.world.level.LevelTimeAccess
+ XXX.world.level.LevelWriter
- XXX.world.level.LightLayer
+ XXX.world.level.LocalMobCapCalculator
- XXX.world.level.LocalMobCapCalculator$MobCounts
+ XXX.world.level.NaturalSpawner
- XXX.world.level.NaturalSpawner$1
+ XXX.world.level.NaturalSpawner$AfterSpawnCallback
- XXX.world.level.NaturalSpawner$ChunkGetter
+ XXX.world.level.NaturalSpawner$SpawnPredicate
- XXX.world.level.NaturalSpawner$SpawnState
+ XXX.world.level.NoiseColumn
- XXX.world.level.PathNavigationRegion
+ XXX.world.level.PotentialCalculator
- XXX.world.level.PotentialCalculator$PointCharge
+ XXX.world.level.ServerLevelAccessor
- XXX.world.level.SignalGetter
+ XXX.world.level.SpawnData
- XXX.world.level.SpawnData$CustomSpawnRules
+ XXX.world.level.StructureManager
- XXX.world.level.WorldDataConfiguration
+ XXX.world.level.WorldGenLevel
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.gui.components.StateSwitchingButton +1M -1M
```
```
XXX.gui.components.SubtitleOverlay +1M -1M
```
```
XXX.gui.components.TabButton +3M -3M
```
```
XXX.gui.components.TextAndImageButton +2M -2M
```
```
XXX.components.tabs.TabNavigationBar +1M -1M
```
```
XXX.components.toasts.RecipeToast +1M -1M
```
```
XXX.components.toasts.ToastComponent$ToastInstance +1M -1M
```
```
XXX.components.toasts.TutorialToast$Icons +1M -1M
```
```
XXX.gui.screens.BackupConfirmScreen +1M -1M
```
```
XXX.gui.screens.ChatScreen +1M -1M
```
```
XXX.gui.screens.ConfirmLinkScreen +1M -1M
```
```
XXX.gui.screens.ConnectScreen +1M -1M
```
```
XXX.gui.screens.CreateBuffetWorldScreen +1M -1M
```
```
XXX.gui.screens.CreateBuffetWorldScreen$BiomeList$Entry +1M -1M
```
```
XXX.gui.screens.CreateFlatWorldScreen$DetailsList +1M | +1P
```
```
XXX.gui.screens.CreditsAndAttributionScreen +1M -1M
```
```
XXX.gui.screens.DeathScreen +1M -1M
```
```
XXX.gui.screens.DemoIntroScreen +2M -2M
```
```
XXX.gui.screens.DisconnectedScreen +1M -1M
```
```
XXX.gui.screens.ErrorScreen +1M -1M
```
```
XXX.gui.screens.GenericWaitingScreen +1M -1M
```
```
XXX.gui.screens.LanguageSelectScreen +1M -1M
```
```
XXX.gui.screens.LanguageSelectScreen$LanguageSelectionList$Entry +1M -1M
```
```
XXX.gui.screens.OptionsSubScreen +1M -1M
```
```
XXX.gui.screens.PopupScreen +1M -1M
```
```
XXX.gui.screens.PresetFlatWorldScreen +1M -1M
```
```
XXX.gui.screens.PresetFlatWorldScreen$PresetsList$Entry +4M -3M | +1P
```
```
XXX.gui.screens.ReceivingLevelScreen +1M -1M
```
```
XXX.gui.screens.ShareToLanScreen +1M -1M
```
```
XXX.gui.screens.SkinCustomizationScreen +1M -1M
```
```
XXX.gui.screens.TitleScreen +1M -1M | +1P -1P
```
```
XXX.gui.screens.VideoSettingsScreen +1M -1M
```
```
XXX.screens.achievement.StatsScreen$GeneralStatisticsList +1M -1M
```
```
XXX.screens.achievement.StatsScreen$ItemStatisticsList +4M -4M
```
```
XXX.screens.achievement.StatsScreen$MobsStatisticsList$MobRow +1M -1M
```
```
XXX.screens.advancements.AdvancementTabType +2M -2M
```
```
XXX.screens.advancements.AdvancementWidget +3M -3M
```
```
XXX.screens.advancements.AdvancementsScreen +4M -4M
```
```
XXX.screens.controls.ControlsScreen +1M -1M
```
```
XXX.screens.controls.KeyBindsList$CategoryEntry +1M -1M
```
```
XXX.screens.controls.KeyBindsScreen +1M -1M
```
```
XXX.screens.debug.GameModeSwitcherScreen +2M -5M | +2P -2P
```
```
XXX.screens.debug.GameModeSwitcherScreen$GameModeIcon +3M -3M
```
```
XXX.screens.inventory.AbstractFurnaceScreen +2M -2M
```
```
XXX.screens.inventory.AnvilScreen +4M -4M
```
```
XXX.screens.inventory.BeaconScreen$BeaconPowerButton +1M -1M
```
```
XXX.screens.inventory.BeaconScreen$BeaconSpriteScreenButton +1M -1M
```
```
XXX.screens.inventory.BrewingStandScreen +2M -2M
```
```
XXX.screens.inventory.ContainerScreen +2M -2M
```
```
XXX.screens.inventory.DispenserScreen +2M -2M
```
```
XXX.screens.inventory.HangingSignEditScreen +2M -2M
```
```
XXX.screens.inventory.HorseInventoryScreen +2M -2M
```
```
XXX.screens.inventory.ItemCombinerScreen +3M -3M | +1P -1P
```
```
XXX.screens.inventory.MerchantScreen$TradeOfferButton +1M -1M
```
```
XXX.screens.inventory.PageButton +1M -1M
```
```
XXX.screens.inventory.SignEditScreen +2M -2M
```
```
XXX.screens.inventory.StructureBlockEditScreen +1M -1M
```
```
XXX.inventory.tooltip.BelowOrAboveWidgetTooltipPositioner +1M -1M
```
```
XXX.inventory.tooltip.ClientTooltipComponent +1M -1M
```
```
XXX.inventory.tooltip.DefaultTooltipPositioner +2M -2M
```
```
XXX.inventory.tooltip.TooltipRenderUtil +6M -6M
```
```
XXX.renderer.entity.ItemRenderer -15M
```
```
XXX.core.registries.BuiltInRegistries +1P
```
```
XXX.core.registries.Registries +1P
```
```
XXX.data.loot.BlockLootSubProvider +1M
```
```
XXX.data.models.BlockModelGenerators +1M
```
```
XXX.minecraft.realms.DisconnectedRealmsScreen +1M -1M
```
```
XXX.minecraft.server.ServerFunctionManager$ExecutionContext +1M | +1P
```
```
XXX.minecraft.sounds.SoundEvents +1P
```
```
XXX.minecraft.tags.BlockTags +2P
```
```
XXX.minecraft.tags.ItemTags +3P -1P
```
```
XXX.world.entity.Entity +4M -1M
```
```
XXX.village.poi.PoiManager +1M -1M
```
```
XXX.animal.sniffer.Sniffer +1M -1M | -1P
```
```
XXX.level.block.NoteBlock -1M
```
```
XXX.level.block.SculkCatalystBlock -2M | -1P
```
```
XXX.level.block.SculkShriekerBlock -1M
```
```
XXX.level.block.SoundType +1P
```
```
XXX.block.entity.AbstractFurnaceBlockEntity +1M -1M
```
```
XXX.block.entity.SculkCatalystBlockEntity +2M -7M | +1P -2P
```
```
XXX.block.state.BlockBehaviour$BlockStateBase +4M | +3P
```
```
XXX.block.state.BlockBehaviour$Properties +4M | +4P
```
```
XXX.state.properties.NoteBlockInstrument +1M -3M
```
```
XXX.state.properties.SculkSensorPhase +1P
```
```
XXX.level.chunk.DataLayer +3M | +1P
```
```
XXX.level.gameevent.EuclideanGameEventListenerRegistry +1M -1M | +2P
```

</details>
<details>
<summary>
net.minecraft.client.gui.components.StateSwitchingButton
</summary>

```diff
- void renderWidget(GuiGraphics,int,int,float)
+ void renderWidget(PoseStack,int,int,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.components.SubtitleOverlay
</summary>

```diff
- void render(GuiGraphics)
+ void render(PoseStack)
```

</details>
<details>
<summary>
net.minecraft.client.gui.components.TabButton
</summary>

```diff
- void renderFocusUnderline(GuiGraphics,Font,int)
+ void renderFocusUnderline(PoseStack,Font,int)
- void renderString(GuiGraphics,Font,int)
+ void renderString(PoseStack,Font,int)
- void renderWidget(GuiGraphics,int,int,float)
+ void renderWidget(PoseStack,int,int,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.components.TextAndImageButton
</summary>

```diff
- void renderString(GuiGraphics,Font,int)
+ void renderString(PoseStack,Font,int)
- void renderWidget(GuiGraphics,int,int,float)
+ void renderWidget(PoseStack,int,int,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.components.tabs.TabNavigationBar
</summary>

```diff
- void render(GuiGraphics,int,int,float)
+ void render(PoseStack,int,int,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.components.toasts.RecipeToast
</summary>

```diff
- Toast$Visibility render(GuiGraphics,ToastComponent,long)
+ Toast$Visibility render(PoseStack,ToastComponent,long)
```

</details>
<details>
<summary>
net.minecraft.client.gui.components.toasts.ToastComponent$ToastInstance
</summary>

```diff
- boolean render(int,GuiGraphics)
+ boolean render(int,PoseStack)
```

</details>
<details>
<summary>
net.minecraft.client.gui.components.toasts.TutorialToast$Icons
</summary>

```diff
- void render(GuiGraphics,int,int)
+ void render(PoseStack,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.BackupConfirmScreen
</summary>

```diff
- void render(GuiGraphics,int,int,float)
+ void render(PoseStack,int,int,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.ChatScreen
</summary>

```diff
- void render(GuiGraphics,int,int,float)
+ void render(PoseStack,int,int,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.ConfirmLinkScreen
</summary>

```diff
- void render(GuiGraphics,int,int,float)
+ void render(PoseStack,int,int,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.ConnectScreen
</summary>

```diff
- void render(GuiGraphics,int,int,float)
+ void render(PoseStack,int,int,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.CreateBuffetWorldScreen
</summary>

```diff
- void render(GuiGraphics,int,int,float)
+ void render(PoseStack,int,int,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.CreateBuffetWorldScreen$BiomeList$Entry
</summary>

```diff
- void render(GuiGraphics,int,int,int,int,int,int,int,boolean,float)
+ void render(PoseStack,int,int,int,int,int,int,int,boolean,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.CreateFlatWorldScreen$DetailsList
</summary>

```diff
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.CreditsAndAttributionScreen
</summary>

```diff
- void render(GuiGraphics,int,int,float)
+ void render(PoseStack,int,int,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.DeathScreen
</summary>

```diff
- void render(GuiGraphics,int,int,float)
+ void render(PoseStack,int,int,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.DemoIntroScreen
</summary>

```diff
- void render(GuiGraphics,int,int,float)
+ void render(PoseStack,int,int,float)
- void renderBackground(GuiGraphics)
+ void renderBackground(PoseStack)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.DisconnectedScreen
</summary>

```diff
- void render(GuiGraphics,int,int,float)
+ void render(PoseStack,int,int,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.ErrorScreen
</summary>

```diff
- void render(GuiGraphics,int,int,float)
+ void render(PoseStack,int,int,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.GenericWaitingScreen
</summary>

```diff
- void render(GuiGraphics,int,int,float)
+ void render(PoseStack,int,int,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.LanguageSelectScreen
</summary>

```diff
- void render(GuiGraphics,int,int,float)
+ void render(PoseStack,int,int,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.LanguageSelectScreen$LanguageSelectionList$Entry
</summary>

```diff
- void render(GuiGraphics,int,int,int,int,int,int,int,boolean,float)
+ void render(PoseStack,int,int,int,int,int,int,int,boolean,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.OptionsSubScreen
</summary>

```diff
- void basicListRender(GuiGraphics,OptionsList,int,int,float)
+ void basicListRender(PoseStack,OptionsList,int,int,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.PopupScreen
</summary>

```diff
- void render(GuiGraphics,int,int,float)
+ void render(PoseStack,int,int,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.PresetFlatWorldScreen
</summary>

```diff
- void render(GuiGraphics,int,int,float)
+ void render(PoseStack,int,int,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.PresetFlatWorldScreen$PresetsList$Entry
</summary>

```diff
- void <clinit>()
- void blitSlot(GuiGraphics,int,int,Item)
+ void blitSlot(PoseStack,int,int,Item)
- void blitSlotBg(GuiGraphics,int,int)
+ void blitSlotBg(PoseStack,int,int)
- void render(GuiGraphics,int,int,int,int,int,int,int,boolean,float)
+ void render(PoseStack,int,int,int,int,int,int,int,boolean,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.ReceivingLevelScreen
</summary>

```diff
- void render(GuiGraphics,int,int,float)
+ void render(PoseStack,int,int,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.ShareToLanScreen
</summary>

```diff
- void render(GuiGraphics,int,int,float)
+ void render(PoseStack,int,int,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.SkinCustomizationScreen
</summary>

```diff
- void render(GuiGraphics,int,int,float)
+ void render(PoseStack,int,int,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.TitleScreen
</summary>

```diff
- void render(GuiGraphics,int,int,float)
+ void render(PoseStack,int,int,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.VideoSettingsScreen
</summary>

```diff
- void render(GuiGraphics,int,int,float)
+ void render(PoseStack,int,int,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.achievement.StatsScreen$GeneralStatisticsList
</summary>

```diff
- void renderBackground(GuiGraphics)
+ void renderBackground(PoseStack)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.achievement.StatsScreen$ItemStatisticsList
</summary>

```diff
- void renderBackground(GuiGraphics)
+ void renderBackground(PoseStack)
- void renderDecorations(GuiGraphics,int,int)
+ void renderDecorations(PoseStack,int,int)
- void renderHeader(GuiGraphics,int,int)
+ void renderHeader(PoseStack,int,int)
- void renderMousehoverTooltip(GuiGraphics,Component,int,int)
+ void renderMousehoverTooltip(PoseStack,Component,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.achievement.StatsScreen$MobsStatisticsList$MobRow
</summary>

```diff
- void render(GuiGraphics,int,int,int,int,int,int,int,boolean,float)
+ void render(PoseStack,int,int,int,int,int,int,int,boolean,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.advancements.AdvancementTabType
</summary>

```diff
- void draw(GuiGraphics,int,int,boolean,int)
+ void draw(PoseStack,int,int,boolean,int)
- void drawIcon(GuiGraphics,int,int,int,ItemStack)
+ void drawIcon(PoseStack,int,int,int,ItemRenderer,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.advancements.AdvancementWidget
</summary>

```diff
- void draw(GuiGraphics,int,int)
+ void draw(PoseStack,int,int)
- void drawConnectivity(GuiGraphics,int,int,boolean)
+ void drawConnectivity(PoseStack,int,int,boolean)
- void drawHover(GuiGraphics,int,int,float,int,int)
+ void drawHover(PoseStack,int,int,float,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.advancements.AdvancementsScreen
</summary>

```diff
- void render(GuiGraphics,int,int,float)
+ void render(PoseStack,int,int,float)
- void renderInside(GuiGraphics,int,int,int,int)
+ void renderInside(PoseStack,int,int,int,int)
- void renderTooltips(GuiGraphics,int,int,int,int)
+ void renderTooltips(PoseStack,int,int,int,int)
- void renderWindow(GuiGraphics,int,int)
+ void renderWindow(PoseStack,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.controls.ControlsScreen
</summary>

```diff
- void render(GuiGraphics,int,int,float)
+ void render(PoseStack,int,int,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.controls.KeyBindsList$CategoryEntry
</summary>

```diff
- void render(GuiGraphics,int,int,int,int,int,int,int,boolean,float)
+ void render(PoseStack,int,int,int,int,int,int,int,boolean,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.controls.KeyBindsScreen
</summary>

```diff
- void render(GuiGraphics,int,int,float)
+ void render(PoseStack,int,int,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen
</summary>

```diff
+ ItemRenderer access$000(GameModeSwitcherScreen)
+ void lambda$render$0(PoseStack,GameModeSwitcherScreen$GameModeIcon)
+ void lambda$render$1(GameModeSwitcherScreen$GameModeSlot,GameModeSwitcherScreen$GameModeIcon)
- void render(GuiGraphics,int,int,float)
+ void render(PoseStack,int,int,float)
- void switchToHoveredGameMode(Minecraft,GameModeSwitcherScreen$GameModeIcon)
+ void switchToHoveredGameMode(Minecraft,Optional)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen$GameModeIcon
</summary>

```diff
- GameModeSwitcherScreen$GameModeIcon getFromGameType(GameType)
- GameModeSwitcherScreen$GameModeIcon getNext()
+ Optional getFromGameType(GameType)
+ Optional getNext()
- void drawIcon(GuiGraphics,int,int)
+ void drawIcon(PoseStack,ItemRenderer,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.AbstractFurnaceScreen
</summary>

```diff
- void render(GuiGraphics,int,int,float)
+ void render(PoseStack,int,int,float)
- void renderBg(GuiGraphics,float,int,int)
+ void renderBg(PoseStack,float,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.AnvilScreen
</summary>

```diff
- void renderBg(GuiGraphics,float,int,int)
+ void renderBg(PoseStack,float,int,int)
- void renderErrorIcon(GuiGraphics,int,int)
+ void renderErrorIcon(PoseStack,int,int)
- void renderFg(GuiGraphics,int,int,float)
+ void renderFg(PoseStack,int,int,float)
- void renderLabels(GuiGraphics,int,int)
+ void renderLabels(PoseStack,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconPowerButton
</summary>

```diff
- void renderIcon(GuiGraphics)
+ void renderIcon(PoseStack)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconSpriteScreenButton
</summary>

```diff
- void renderIcon(GuiGraphics)
+ void renderIcon(PoseStack)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.BrewingStandScreen
</summary>

```diff
- void render(GuiGraphics,int,int,float)
+ void render(PoseStack,int,int,float)
- void renderBg(GuiGraphics,float,int,int)
+ void renderBg(PoseStack,float,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.ContainerScreen
</summary>

```diff
- void render(GuiGraphics,int,int,float)
+ void render(PoseStack,int,int,float)
- void renderBg(GuiGraphics,float,int,int)
+ void renderBg(PoseStack,float,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.DispenserScreen
</summary>

```diff
- void render(GuiGraphics,int,int,float)
+ void render(PoseStack,int,int,float)
- void renderBg(GuiGraphics,float,int,int)
+ void renderBg(PoseStack,float,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.HangingSignEditScreen
</summary>

```diff
- void offsetSign(GuiGraphics,BlockState)
+ void offsetSign(PoseStack,BlockState)
- void renderSignBackground(GuiGraphics,BlockState)
+ void renderSignBackground(PoseStack,MultiBufferSource$BufferSource,BlockState)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.HorseInventoryScreen
</summary>

```diff
- void render(GuiGraphics,int,int,float)
+ void render(PoseStack,int,int,float)
- void renderBg(GuiGraphics,float,int,int)
+ void renderBg(PoseStack,float,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.ItemCombinerScreen
</summary>

```diff
- void render(GuiGraphics,int,int,float)
+ void render(PoseStack,int,int,float)
- void renderBg(GuiGraphics,float,int,int)
+ void renderBg(PoseStack,float,int,int)
- void renderFg(GuiGraphics,int,int,float)
+ void renderFg(PoseStack,int,int,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.MerchantScreen$TradeOfferButton
</summary>

```diff
- void renderToolTip(GuiGraphics,int,int)
+ void renderToolTip(PoseStack,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.PageButton
</summary>

```diff
- void renderWidget(GuiGraphics,int,int,float)
+ void renderWidget(PoseStack,int,int,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.SignEditScreen
</summary>

```diff
- void offsetSign(GuiGraphics,BlockState)
+ void offsetSign(PoseStack,BlockState)
- void renderSignBackground(GuiGraphics,BlockState)
+ void renderSignBackground(PoseStack,MultiBufferSource$BufferSource,BlockState)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.StructureBlockEditScreen
</summary>

```diff
- void render(GuiGraphics,int,int,float)
+ void render(PoseStack,int,int,float)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.tooltip.BelowOrAboveWidgetTooltipPositioner
</summary>

```diff
- Vector2ic positionTooltip(int,int,int,int,int,int)
+ Vector2ic positionTooltip(Screen,int,int,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.tooltip.ClientTooltipComponent
</summary>

```diff
- void renderImage(Font,int,int,GuiGraphics)
+ void renderImage(Font,int,int,PoseStack,ItemRenderer)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.tooltip.DefaultTooltipPositioner
</summary>

```diff
- Vector2ic positionTooltip(int,int,int,int,int,int)
+ Vector2ic positionTooltip(Screen,int,int,int,int)
- void positionTooltip(int,int,Vector2i,int,int)
+ void positionTooltip(Screen,Vector2i,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.tooltip.TooltipRenderUtil
</summary>

```diff
- void renderFrameGradient(GuiGraphics,int,int,int,int,int,int,int)
+ void renderFrameGradient(TooltipRenderUtil$BlitPainter,Matrix4f,BufferBuilder,int,int,int,int,int,int,int)
- void renderHorizontalLine(GuiGraphics,int,int,int,int,int)
+ void renderHorizontalLine(TooltipRenderUtil$BlitPainter,Matrix4f,BufferBuilder,int,int,int,int,int)
- void renderRectangle(GuiGraphics,int,int,int,int,int,int)
+ void renderRectangle(TooltipRenderUtil$BlitPainter,Matrix4f,BufferBuilder,int,int,int,int,int,int)
- void renderTooltipBackground(GuiGraphics,int,int,int,int,int)
+ void renderTooltipBackground(TooltipRenderUtil$BlitPainter,Matrix4f,BufferBuilder,int,int,int,int,int)
- void renderVerticalLine(GuiGraphics,int,int,int,int,int)
+ void renderVerticalLine(TooltipRenderUtil$BlitPainter,Matrix4f,BufferBuilder,int,int,int,int,int)
- void renderVerticalLineGradient(GuiGraphics,int,int,int,int,int,int)
+ void renderVerticalLineGradient(TooltipRenderUtil$BlitPainter,Matrix4f,BufferBuilder,int,int,int,int,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.ItemRenderer
</summary>

```diff
+ String lambda$tryRenderGuiItem$0(ItemStack)
+ String lambda$tryRenderGuiItem$1(ItemStack)
+ String lambda$tryRenderGuiItem$2(ItemStack)
+ String lambda$tryRenderGuiItem$3(ItemStack)
+ void renderAndDecorateFakeItem(PoseStack,ItemStack,int,int)
+ void renderAndDecorateItem(PoseStack,ItemStack,int,int,int,int)
+ void renderAndDecorateItem(PoseStack,ItemStack,int,int,int)
+ void renderAndDecorateItem(PoseStack,ItemStack,int,int)
+ void renderAndDecorateItem(PoseStack,LivingEntity,ItemStack,int,int,int)
+ void renderGuiItem(PoseStack,ItemStack,int,int,BakedModel)
+ void renderGuiItem(PoseStack,ItemStack,int,int)
+ void renderGuiItemDecorations(PoseStack,Font,ItemStack,int,int,String)
+ void renderGuiItemDecorations(PoseStack,Font,ItemStack,int,int)
+ void tryRenderGuiItem(PoseStack,LivingEntity,Level,ItemStack,int,int,int,int)
+ void tryRenderGuiItem(PoseStack,LivingEntity,Level,ItemStack,int,int,int)
```

</details>
<details>
<summary>
net.minecraft.data.loot.BlockLootSubProvider
</summary>

```diff
- void <init>(Set,FeatureFlagSet,Map)
```

</details>
<details>
<summary>
net.minecraft.data.models.BlockModelGenerators
</summary>

```diff
- void createGenericCube(Block)
```

</details>
<details>
<summary>
net.minecraft.realms.DisconnectedRealmsScreen
</summary>

```diff
- void render(GuiGraphics,int,int,float)
+ void render(PoseStack,int,int,float)
```

</details>
<details>
<summary>
net.minecraft.server.ServerFunctionManager$ExecutionContext
</summary>

```diff
- CommandSourceStack wrapSender(CommandSourceStack)
```

</details>
<details>
<summary>
net.minecraft.world.entity.Entity
</summary>

```diff
- boolean walkingOnBlock(boolean,Vec3)
+ void handleStepSounds(BlockPos,BlockState)
- void playMuffledStepSound(BlockState)
- void walkingStepSound(BlockPos,BlockState)
- void waterSwimSound()
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.village.poi.PoiManager
</summary>

```diff
+ void checkConsistencyWithBlocks(ChunkPos,LevelChunkSection)
- void checkConsistencyWithBlocks(SectionPos,LevelChunkSection)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.sniffer.Sniffer
</summary>

```diff
+ boolean canRide(Entity)
- boolean isSearching()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.NoteBlock
</summary>

```diff
+ NoteBlockInstrument lambda$setInstrument$0(LevelAccessor,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SculkCatalystBlock
</summary>

```diff
+ GameEventListener getListener(ServerLevel,BlockEntity)
+ void bloom(ServerLevel,BlockPos,BlockState,RandomSource)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SculkShriekerBlock
</summary>

```diff
+ GameEventListener getListener(ServerLevel,BlockEntity)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity
</summary>

```diff
- void awardUsedRecipes(Player,List)
+ void awardUsedRecipes(Player)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.SculkCatalystBlockEntity
</summary>

```diff
+ boolean handleGameEvent(ServerLevel,GameEvent,GameEvent$Context,Vec3)
- GameEventListener getListener()
+ GameEventListener$DeliveryMode getDeliveryMode()
+ int getListenerRadius()
+ Integer lambda$saveAdditional$0(SculkSpreader$ChargeCursor)
+ PositionSource getListenerSource()
- SculkCatalystBlockEntity$CatalystListener getListener()
+ SculkSpreader getSculkSpreader()
+ void tryAwardItSpreadsAdvancement(LivingEntity)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase
</summary>

```diff
- boolean blocksMotion()
- boolean calculateSolid()
- boolean isSolid()
- NoteBlockInstrument instrument()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.BlockBehaviour$Properties
</summary>

```diff
- BlockBehaviour$Properties forceSolidOff()
- BlockBehaviour$Properties forceSolidOn()
- BlockBehaviour$Properties instrument(NoteBlockInstrument)
- BlockBehaviour$Properties replaceable()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.properties.NoteBlockInstrument
</summary>

```diff
+ boolean requiresAirAbove()
- boolean worksAboveNoteBlock()
+ NoteBlockInstrument byStateBelow(BlockState)
+ Optional byStateAbove(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.DataLayer
</summary>

```diff
- boolean isDefinitelyFilledWith(int)
- boolean isDefinitelyHomogenous()
- byte packFilled(int)
```

</details>
<details>
<summary>
net.minecraft.world.level.gameevent.EuclideanGameEventListenerRegistry
</summary>

```diff
- void <init>(ServerLevel,int,EuclideanGameEventListenerRegistry$OnEmptyAction)
+ void <init>(ServerLevel)
```

</details>
</details>
<hr/>