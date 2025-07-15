## Comparison with [22w45a](https://github.com/PixiGeko/Minecraft-generated-data/tree/22w45a)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Blocks](#blocks)
> - [Commands](#commands)
> - [Translations](#translations)
> - [File structure](#file-structure)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">22w45a</th><th>22w46a</th></tr><tr><td>World version</td><td><pre>3208</pre></td><td><pre>3210</pre></td></tr><tr><td>Protocol version</td><td><pre>1073741931</pre></td><td><pre>1073741932</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">22w45a</th><th>22w46a</th></tr><tr><td>com.google.code.gson:gson</td><td><pre>2.9.1</pre></td><td><pre>2.10</pre></td></tr><tr><td>com.mojang:authlib</td><td><pre>3.13.56</pre></td><td><pre>3.15.28</pre></td></tr></table>
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
+ minecraft:piglin_head
+ minecraft:piglin_wall_head
```

</details>
<details>
<summary>
item
</summary>

```diff
+ minecraft:piglin_head
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
+ minecraft:piglin_wall_head
```

</details>
<details>
<summary>
all_blocks_with_drop.json
</summary>

```diff
+ minecraft:piglin_head
```

</details>
<details>
<summary>
universal_tags/block.json
</summary>

```diff
+ minecraft:piglin_head
+ minecraft:piglin_wall_head
```

</details>
<details>
<summary>
universal_tags/item.json
</summary>

```diff
+ minecraft:piglin_head
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
+ piglin_head.json
+ piglin_wall_head.json
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
+ fillbiome.txt
```

</details>
<details>
<summary>
execute
</summary>

```diff
+ execute if biome <pos: block_pos> <biome: resource_or_tag>
+ execute unless biome <pos: block_pos> <biome: resource_or_tag>
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
+ block.minecraft.piglin_head: Piglin Head
+ block.minecraft.piglin_wall_head: Piglin Wall Head
+ commands.fillbiome.success: Biomes set between %s, %s, %s and %s, %s, %s
+ commands.fillbiome.toobig: Too many blocks in the specified volume (maximum %s, specified %s)
+ options.telemetry: Telemetry Data
+ options.telemetry.button: Data Collection
+ options.telemetry.button.tooltip: "%s" includes only the required data.
"%s" includes optional, as well as the required data.
+ options.telemetry.state.all: All
+ options.telemetry.state.minimal: Minimal
+ options.telemetry.state.none: None
+ telemetry_info.button.give_feedback: Give Feedback
+ telemetry_info.button.show_data: Open My Data
+ telemetry_info.property_title: Included Data
+ telemetry_info.screen.description: Collecting this data helps us improve Minecraft by guiding us in directions that are relevant to our players.
You can also send in additional feedback to help us keep improving Minecraft.
+ telemetry_info.screen.title: Telemetry Data Collection
+ telemetry.event.optional: %s (Optional)
+ telemetry.event.performance_metrics.description: Knowing the overall performance profile of Minecraft helps us tune and optimize the game for a wide range of machine specifications and operating systems. 
Game version is included to help us compare the performance profile for new versions of Minecraft.
+ telemetry.event.performance_metrics.title: Performance Metrics
+ telemetry.event.required: %s (Required)
+ telemetry.event.world_load_times.description: It’s important for us to understand how long it takes to join a world, and how that changes over time. For example, when we add new features or do larger technical changes, we need to see what impact that had on load times.
+ telemetry.event.world_load_times.title: World Load Times
+ telemetry.event.world_loaded.description: Knowing how players play Minecraft (such as Game Mode, client or server modded, and game version) allows us to focus game updates to improve the areas that players care about most.
The World Loaded event is pair with the World Unloaded event to calculate how long the play session has lasted.
+ telemetry.event.world_loaded.title: World Loaded
+ telemetry.event.world_unloaded.description: This event is paired with the World Loaded event to calculate how long the world session has lasted.
The duration (in seconds and ticks) is measured when a world session has ended (quitting to title, disconnecting from a server).
+ telemetry.event.world_unloaded.title: World Unloaded
+ telemetry.property.client_id.title: Client ID
+ telemetry.property.client_modded.title: Client Modded
+ telemetry.property.dedicated_memory_kb.title: Dedicated Memory (kB)
+ telemetry.property.event_timestamp_utc.title: Event Timestamp (UTC)
+ telemetry.property.frame_rate_samples.title: Frame Rate Samples (FPS)
+ telemetry.property.game_mode.title: Game Mode
+ telemetry.property.game_version.title: Game Version
+ telemetry.property.minecraft_session_id.title: Minecraft Session ID
+ telemetry.property.new_world.title: New World
+ telemetry.property.number_of_samples.title: Sample Count
+ telemetry.property.operating_system.title: Operating System
+ telemetry.property.opt_in.title: Opt-In
+ telemetry.property.platform.title: Platform
+ telemetry.property.render_distance.title: Render Distance
+ telemetry.property.render_time_samples.title: Render Time Samples
+ telemetry.property.seconds_since_load.title: Time Since Load (Seconds)
+ telemetry.property.server_modded.title: Server Modded
+ telemetry.property.server_type.title: Server Type
+ telemetry.property.ticks_since_load.title: Time Since Load (Ticks)
+ telemetry.property.used_memory_samples.title: Used Random Access Memory
+ telemetry.property.user_id.title: User ID
+ telemetry.property.world_load_time_ms.title: World Load Time (Milliseconds)
+ telemetry.property.world_session_id.title: World Session ID
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>22w45a</th><th>22w46a</th></tr>
<tr><th align="left"><div style="width:290px">advancements.husbandry.make_a_sign_glow.description</div></th><td>Make the text of a Sign glow</td><td>Make the text of any kind of sign glow</td></tr>
<tr><th align="left"><div style="width:290px">gamerule.blockExplosionDropDecay</div></th><td>Drops from explosions caused by blocks decay</td><td>In block interaction explosions, some blocks won't drop their loot</td></tr>
<tr><th align="left"><div style="width:290px">gamerule.mobExplosionDropDecay</div></th><td>Drops from explosions caused by mobs decay</td><td>In mob explosions, some blocks won't drop their loot</td></tr>
<tr><th align="left"><div style="width:290px">gamerule.tntExplosionDropDecay</div></th><td>Drops from explosions caused by TNT decay</td><td>In TNT explosions, some blocks won't drop their loot</td></tr>
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
+ minecraft/datapacks/update_1_20/data/minecraft/advancements/husbandry/bred_all_animals.json
+ minecraft/datapacks/update_1_20/data/minecraft/advancements/husbandry/breed_an_animal.json
+ minecraft/datapacks/update_1_20/data/minecraft/advancements/husbandry/root.json
+ minecraft/datapacks/update_1_20/data/minecraft/loot_tables/blocks/piglin_head.json
+ minecraft/datapacks/update_1_20/data/minecraft/tags/blocks/all_signs.json
+ minecraft/loot_tables/blocks/piglin_head.json
+ minecraft/tags/blocks/all_signs.json
- minecraft/tags/blocks/stripped_logs.json
- minecraft/tags/items/stripped_logs.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/atlases/banner_patterns.json
+ minecraft/atlases/beds.json
+ minecraft/atlases/blocks.json
+ minecraft/atlases/chests.json
+ minecraft/atlases/mob_effects.json
+ minecraft/atlases/paintings.json
+ minecraft/atlases/particles.json
+ minecraft/atlases/shield_patterns.json
+ minecraft/atlases/shulker_boxes.json
+ minecraft/atlases/signs.json
+ minecraft/blockstates/piglin_head.json
+ minecraft/blockstates/piglin_wall_head.json
+ minecraft/models/block/chiseled_bookshelf_empty_slot_bottom_left.json
+ minecraft/models/block/chiseled_bookshelf_empty_slot_bottom_mid.json
+ minecraft/models/block/chiseled_bookshelf_empty_slot_bottom_right.json
+ minecraft/models/block/chiseled_bookshelf_empty_slot_top_left.json
+ minecraft/models/block/chiseled_bookshelf_empty_slot_top_mid.json
+ minecraft/models/block/chiseled_bookshelf_empty_slot_top_right.json
+ minecraft/models/block/chiseled_bookshelf_inventory.json
+ minecraft/models/block/chiseled_bookshelf_occupied_slot_bottom_left.json
+ minecraft/models/block/chiseled_bookshelf_occupied_slot_bottom_mid.json
+ minecraft/models/block/chiseled_bookshelf_occupied_slot_bottom_right.json
+ minecraft/models/block/chiseled_bookshelf_occupied_slot_top_left.json
+ minecraft/models/block/chiseled_bookshelf_occupied_slot_top_mid.json
+ minecraft/models/block/chiseled_bookshelf_occupied_slot_top_right.json
- minecraft/models/block/chiseled_bookshelf_stage0.json
- minecraft/models/block/chiseled_bookshelf_stage1.json
- minecraft/models/block/chiseled_bookshelf_stage2.json
- minecraft/models/block/chiseled_bookshelf_stage3.json
- minecraft/models/block/chiseled_bookshelf_stage4.json
- minecraft/models/block/chiseled_bookshelf_stage5.json
- minecraft/models/block/chiseled_bookshelf_stage6.json
+ minecraft/models/block/chiseled_bookshelf.json
+ minecraft/models/block/template_chiseled_bookshelf_slot_bottom_left.json
+ minecraft/models/block/template_chiseled_bookshelf_slot_bottom_mid.json
+ minecraft/models/block/template_chiseled_bookshelf_slot_bottom_right.json
+ minecraft/models/block/template_chiseled_bookshelf_slot_top_left.json
+ minecraft/models/block/template_chiseled_bookshelf_slot_top_mid.json
+ minecraft/models/block/template_chiseled_bookshelf_slot_top_right.json
- minecraft/models/block/template_chiseled_bookshelf.json
+ minecraft/models/item/piglin_head.json
+ minecraft/textures/block/chiseled_bookshelf_empty.png
+ minecraft/textures/block/chiseled_bookshelf_occupied.png
- minecraft/textures/block/chiseled_bookshelf_stage0.png
- minecraft/textures/block/chiseled_bookshelf_stage1.png
- minecraft/textures/block/chiseled_bookshelf_stage2.png
- minecraft/textures/block/chiseled_bookshelf_stage3.png
- minecraft/textures/block/chiseled_bookshelf_stage4.png
- minecraft/textures/block/chiseled_bookshelf_stage5.png
- minecraft/textures/block/chiseled_bookshelf_stage6.png
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
- XXX.advancements.packs.UpdateOneTwentyAdvancements
+ XXX.chat.contents.BlockDataSource
- XXX.chat.contents.DataSource
+ XXX.chat.contents.EntityDataSource
- XXX.chat.contents.KeybindContents
+ XXX.chat.contents.KeybindResolver
- XXX.chat.contents.LiteralContents
+ XXX.chat.contents.NbtContents
+ XXX.chat.contents.package-info
- XXX.chat.contents.ScoreContents
+ XXX.chat.contents.SelectorContents
- XXX.chat.contents.StorageDataSource
+ XXX.chat.contents.TranslatableContents
- XXX.chat.contents.TranslatableFormatException
- XXX.data.models.BlockModelGenerators$TintState
+ XXX.data.models.BlockModelGenerators$WoodProvider
- XXX.data.models.ItemModelGenerators
+ XXX.data.models.ModelProvider
- XXX.data.models.package-info
- XXX.data.recipes.CraftingRecipeBuilder
+ XXX.data.recipes.CraftingRecipeBuilder$1
- XXX.data.recipes.CraftingRecipeBuilder$CraftingResult
+ XXX.data.recipes.FinishedRecipe
+ XXX.data.recipes.package-info
- XXX.data.recipes.RecipeBuilder
+ XXX.data.recipes.RecipeCategory
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
+ XXX.data.recipes.UpgradeRecipeBuilder
- XXX.data.recipes.UpgradeRecipeBuilder$Result
- XXX.data.registries.package-info
- XXX.data.registries.RegistriesDatapackGenerator
+ XXX.data.registries.VanillaRegistries
+ XXX.data.structures.NbtToSnbt
+ XXX.data.structures.package-info
- XXX.data.structures.SnbtToNbt
+ XXX.data.structures.SnbtToNbt$Filter
- XXX.data.structures.SnbtToNbt$StructureConversionException
+ XXX.data.structures.SnbtToNbt$TaskResult
- XXX.data.structures.StructureUpdater
- XXX.data.tags.BannerPatternTagsProvider
+ XXX.data.tags.BiomeTagsProvider
- XXX.data.tags.CatVariantTagsProvider
+ XXX.data.tags.EntityTypeTagsProvider
- XXX.data.tags.FlatLevelGeneratorPresetTagsProvider
+ XXX.data.tags.FluidTagsProvider
- XXX.data.tags.GameEventTagsProvider
+ XXX.data.tags.InstrumentTagsProvider
- XXX.data.tags.IntrinsicHolderTagsProvider
+ XXX.data.tags.IntrinsicHolderTagsProvider$IntrinsicTagAppender
- XXX.data.tags.ItemTagsProvider
+ XXX.data.tags.package-info
+ XXX.data.tags.PaintingVariantTagsProvider
- XXX.data.tags.PoiTypeTagsProvider
+ XXX.data.tags.StructureTagsProvider
- XXX.data.tags.TagsProvider
+ XXX.data.tags.TagsProvider$TagAppender
- XXX.data.tags.UpdateOneTwentyBlockTagsProvider
+ XXX.data.tags.UpdateOneTwentyItemTagsProvider
- XXX.data.tags.VanillaBlockTagsProvider
+ XXX.data.tags.VanillaItemTagsProvider
- XXX.data.tags.WorldPresetTagsProvider
- XXX.data.worldgen.AncientCityStructurePieces
+ XXX.data.worldgen.AncientCityStructurePools
- XXX.data.worldgen.BastionBridgePools
+ XXX.data.worldgen.BastionHoglinStablePools
- XXX.data.worldgen.BastionHousingUnitsPools
+ XXX.data.worldgen.BastionPieces
- XXX.data.worldgen.BastionSharedPools
+ XXX.data.worldgen.BastionTreasureRoomPools
- XXX.data.worldgen.BiomeDefaultFeatures
+ XXX.data.worldgen.BootstapContext
- XXX.data.worldgen.Carvers
+ XXX.data.worldgen.DesertVillagePools
- XXX.data.worldgen.DimensionTypes
+ XXX.data.worldgen.NoiseData
- XXX.data.worldgen.package-info
- XXX.data.worldgen.PillagerOutpostPools
+ XXX.data.worldgen.PlainVillagePools
- XXX.data.worldgen.Pools
+ XXX.data.worldgen.ProcessorLists
- XXX.data.worldgen.SavannaVillagePools
+ XXX.data.worldgen.SnowyVillagePools
+ XXX.data.worldgen.Structures
- XXX.data.worldgen.StructureSets
- XXX.data.worldgen.SurfaceRuleData
+ XXX.data.worldgen.TaigaVillagePools
- XXX.data.worldgen.TerrainProvider
+ XXX.data.worldgen.VillagePools
- XXX.datafix.fixes.AbstractArrowPickupFix
+ XXX.datafix.fixes.AbstractPoiSectionFix
- XXX.datafix.fixes.AbstractUUIDFix
+ XXX.datafix.fixes.AddFlagIfNotPresentFix
- XXX.datafix.fixes.AddNewChoices
+ XXX.datafix.fixes.AdvancementsFix
- XXX.datafix.fixes.AdvancementsRenameFix
+ XXX.datafix.fixes.AttributesRename
- XXX.datafix.fixes.BedItemColorFix
+ XXX.datafix.fixes.BiomeFix
- XXX.datafix.fixes.BitStorageAlignFix
+ XXX.datafix.fixes.BlendingDataFix
- XXX.datafix.fixes.BlendingDataRemoveFromNetherEndFix
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
- XXX.datafix.fixes.CavesAndCliffsRenames
+ XXX.datafix.fixes.ChunkBedBlockEntityInjecterFix
- XXX.datafix.fixes.ChunkBiomeFix
+ XXX.datafix.fixes.ChunkDeleteIgnoredLightDataFix
- XXX.datafix.fixes.ChunkHeightAndBiomeFix
+ XXX.datafix.fixes.ChunkLightRemoveFix
- XXX.datafix.fixes.ChunkPalettedStorageFix
+ XXX.datafix.fixes.ChunkPalettedStorageFix$1
- XXX.datafix.fixes.ChunkPalettedStorageFix$DataLayer
+ XXX.datafix.fixes.ChunkPalettedStorageFix$Direction
- XXX.datafix.fixes.ChunkPalettedStorageFix$Direction$Axis
+ XXX.datafix.fixes.ChunkPalettedStorageFix$Direction$AxisDirection
- XXX.datafix.fixes.ChunkPalettedStorageFix$Section
+ XXX.datafix.fixes.ChunkPalettedStorageFix$UpgradeChunk
- XXX.datafix.fixes.ChunkProtoTickListFix
+ XXX.datafix.fixes.ChunkProtoTickListFix$PoorMansPalettedContainer
- XXX.datafix.fixes.ChunkRenamesFix
+ XXX.datafix.fixes.ChunkStatusFix
- XXX.datafix.fixes.ChunkStatusFix2
+ XXX.datafix.fixes.ChunkStructuresTemplateRenameFix
- XXX.datafix.fixes.ChunkToProtochunkFix
+ XXX.datafix.fixes.ColorlessShulkerEntityFix
- XXX.datafix.fixes.CriteriaRenameFix
+ XXX.datafix.fixes.DyeItemRenameFix
- XXX.datafix.fixes.EntityArmorStandSilentFix
+ XXX.datafix.fixes.EntityBlockStateFix
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
+ XXX.datafix.fixes.FilteredBooksFix
- XXX.datafix.fixes.FilteredSignsFix
+ XXX.datafix.fixes.ForcePoiRebuild
- XXX.datafix.fixes.FurnaceRecipeFix
+ XXX.datafix.fixes.GoatHornIdFix
- XXX.datafix.fixes.GossipUUIDFix
+ XXX.datafix.fixes.HeightmapRenamingFix
- XXX.datafix.fixes.IglooMetadataRemovalFix
+ XXX.datafix.fixes.ItemBannerColorFix
- XXX.datafix.fixes.ItemCustomNameToComponentFix
+ XXX.datafix.fixes.ItemIdFix
- XXX.datafix.fixes.ItemLoreFix
+ XXX.datafix.fixes.ItemPotionFix
- XXX.datafix.fixes.ItemRemoveBlockEntityTagFix
+ XXX.datafix.fixes.ItemRenameFix
- XXX.datafix.fixes.ItemRenameFix$1
+ XXX.datafix.fixes.ItemShulkerBoxColorFix
- XXX.datafix.fixes.ItemSpawnEggFix
+ XXX.datafix.fixes.ItemStackEnchantmentNamesFix
- XXX.datafix.fixes.ItemStackMapIdFix
+ XXX.datafix.fixes.ItemStackSpawnEggFix
- XXX.datafix.fixes.ItemStackTagFix
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
- XXX.datafix.fixes.OptionsProgrammerArtFix
+ XXX.datafix.fixes.OptionsRenameFieldFix
- XXX.datafix.fixes.OverreachingTickFix
- XXX.datafix.fixes.package-info
+ XXX.datafix.fixes.PlayerUUIDFix
- XXX.datafix.fixes.PoiTypeRemoveFix
+ XXX.datafix.fixes.PoiTypeRenameFix
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
- XXX.datafix.fixes.SimpleRenameFix
+ XXX.datafix.fixes.SimplestEntityRenameFix
- XXX.datafix.fixes.SpawnerDataFix
+ XXX.datafix.fixes.StatsCounterFix
- XXX.datafix.fixes.StatsRenameFix
+ XXX.datafix.fixes.StriderGravityFix
- XXX.datafix.fixes.StructureReferenceCountFix
- XXX.datafix.fixes.StructuresBecomeConfiguredFix
+ XXX.datafix.fixes.StructuresBecomeConfiguredFix$Conversion
+ XXX.datafix.fixes.StructureSettingsFlattenFix
- XXX.datafix.fixes.TeamDisplayNameFix
+ XXX.datafix.fixes.TrappedChestBlockEntityFix
- XXX.datafix.fixes.TrappedChestBlockEntityFix$TrappedChestSection
+ XXX.datafix.fixes.VariantRenameFix
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
- XXX.datafix.schemas.package-info
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
+ XXX.datafix.schemas.V3202
- XXX.datafix.schemas.V3203
+ XXX.datafix.schemas.V3204
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
- XXX.gametest.framework.AfterBatch
+ XXX.gametest.framework.BeforeBatch
- XXX.gametest.framework.ExhaustedAttemptsException
+ XXX.gametest.framework.GameTest
- XXX.gametest.framework.GameTestAssertException
+ XXX.gametest.framework.GameTestAssertPosException
- XXX.gametest.framework.GameTestBatch
+ XXX.gametest.framework.GameTestBatchRunner
- XXX.gametest.framework.GameTestBatchRunner$1
+ XXX.gametest.framework.GameTestEvent
- XXX.gametest.framework.GameTestGenerator
+ XXX.gametest.framework.GameTestHelper
- XXX.gametest.framework.GameTestHelper$1
+ XXX.gametest.framework.GameTestHelper$2
- XXX.gametest.framework.GameTestInfo
+ XXX.gametest.framework.GameTestListener
- XXX.gametest.framework.GameTestRegistry
+ XXX.gametest.framework.GameTestRunner
- XXX.gametest.framework.GameTestSequence
+ XXX.gametest.framework.GameTestSequence$Condition
- XXX.gametest.framework.GameTestServer
+ XXX.gametest.framework.GameTestServer$1
- XXX.gametest.framework.GameTestTicker
+ XXX.gametest.framework.GameTestTimeoutException
- XXX.gametest.framework.GlobalTestReporter
+ XXX.gametest.framework.JUnitLikeTestReporter
- XXX.gametest.framework.LogTestReporter
+ XXX.gametest.framework.MultipleTestTracker
- XXX.gametest.framework.MultipleTestTracker$1
+ XXX.gametest.framework.package-info
+ XXX.gametest.framework.ReportGameListener
- XXX.gametest.framework.StructureUtils
+ XXX.gametest.framework.StructureUtils$1
- XXX.gametest.framework.TeamcityTestReporter
+ XXX.gametest.framework.TestClassNameArgument
- XXX.gametest.framework.TestCommand
+ XXX.gametest.framework.TestCommand$TestSummaryDisplayer
- XXX.gametest.framework.TestFunction
+ XXX.gametest.framework.TestFunctionArgument
- XXX.gametest.framework.TestReporter
+ XXX.level.block.BambooBlock
- XXX.level.block.BambooSaplingBlock
- XXX.level.block.ChorusFlowerBlock
+ XXX.level.block.ChorusPlantBlock
- XXX.level.block.CocoaBlock
+ XXX.level.block.CocoaBlock$1
- XXX.level.block.CommandBlock
+ XXX.level.block.ComparatorBlock
- XXX.level.block.ComposterBlock
+ XXX.level.block.ComposterBlock$EmptyContainer
- XXX.level.block.ComposterBlock$InputContainer
+ XXX.level.block.ComposterBlock$OutputContainer
- XXX.level.block.ConcretePowderBlock
+ XXX.level.block.ConduitBlock
- XXX.level.block.CoralBlock
+ XXX.level.block.CoralFanBlock
- XXX.level.block.CoralPlantBlock
+ XXX.level.block.CoralWallFanBlock
- XXX.level.block.CraftingTableBlock
+ XXX.level.block.CropBlock
- XXX.level.block.CrossCollisionBlock
+ XXX.level.block.CrossCollisionBlock$1
- XXX.level.block.CryingObsidianBlock
+ XXX.level.block.DaylightDetectorBlock
- XXX.level.block.DeadBushBlock
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
- XXX.level.block.FarmBlock
+ XXX.level.block.FenceBlock
- XXX.level.block.FenceGateBlock
+ XXX.level.block.FenceGateBlock$1
- XXX.level.block.FireBlock
+ XXX.level.block.FletchingTableBlock
- XXX.level.block.FlowerBlock
+ XXX.level.block.FlowerPotBlock
- XXX.level.block.FrogspawnBlock
+ XXX.level.block.FrostedIceBlock
- XXX.level.block.FungusBlock
+ XXX.level.block.FurnaceBlock
- XXX.level.block.GameMasterBlock
+ XXX.level.block.GlassBlock
- XXX.level.block.GlazedTerracottaBlock
+ XXX.level.block.GlowLichenBlock
- XXX.level.block.GrassBlock
+ XXX.level.block.GravelBlock
- XXX.level.block.GrindstoneBlock
+ XXX.level.block.GrindstoneBlock$1
- XXX.level.block.GrowingPlantBlock
+ XXX.level.block.GrowingPlantBodyBlock
- XXX.level.block.GrowingPlantHeadBlock
+ XXX.level.block.HalfTransparentBlock
- XXX.level.block.HangingRootsBlock
+ XXX.level.block.HayBlock
- XXX.level.block.HoneyBlock
+ XXX.level.block.HopperBlock
- XXX.level.block.HopperBlock$1
+ XXX.level.block.HorizontalDirectionalBlock
- XXX.level.block.HugeMushroomBlock
+ XXX.level.block.IceBlock
- XXX.level.block.InfestedBlock
+ XXX.level.block.InfestedRotatedPillarBlock
- XXX.level.block.IronBarsBlock
+ XXX.level.block.JigsawBlock
- XXX.level.block.JukeboxBlock
+ XXX.level.block.KelpBlock
- XXX.level.block.KelpPlantBlock
+ XXX.level.block.LadderBlock
- XXX.level.block.LadderBlock$1
+ XXX.level.block.LanternBlock
- XXX.level.block.LavaCauldronBlock
+ XXX.level.block.LayeredCauldronBlock
- XXX.level.block.LeavesBlock
+ XXX.level.block.LecternBlock
- XXX.level.block.LecternBlock$1
+ XXX.level.block.LevelEvent
- XXX.level.block.LeverBlock
+ XXX.level.block.LeverBlock$1
- XXX.level.block.LightBlock
+ XXX.level.block.LightningRodBlock
- XXX.level.block.LiquidBlock
+ XXX.level.block.LiquidBlockContainer
- XXX.level.block.LoomBlock
+ XXX.level.block.MagmaBlock
- XXX.level.block.MangroveLeavesBlock
+ XXX.level.block.MangrovePropaguleBlock
- XXX.level.block.MangroveRootsBlock
+ XXX.level.block.MelonBlock
- XXX.level.block.Mirror
+ XXX.level.block.Mirror$1
- XXX.level.block.MossBlock
+ XXX.level.block.MudBlock
- XXX.level.block.MultifaceBlock
+ XXX.level.block.MultifaceSpreader
- XXX.level.block.MultifaceSpreader$DefaultSpreaderConfig
+ XXX.level.block.MultifaceSpreader$SpreadConfig
- XXX.level.block.MultifaceSpreader$SpreadPos
+ XXX.level.block.MultifaceSpreader$SpreadPredicate
- XXX.level.block.MultifaceSpreader$SpreadType
+ XXX.level.block.MultifaceSpreader$SpreadType$1
- XXX.level.block.MultifaceSpreader$SpreadType$2
+ XXX.level.block.MultifaceSpreader$SpreadType$3
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
+ XXX.minecraft.data.package-info
- XXX.minecraft.locale.Language
+ XXX.minecraft.locale.Language$1
- XXX.minecraft.locale.package-info
+ XXX.minecraft.nbt.ByteArrayTag
- XXX.minecraft.nbt.ByteArrayTag$1
+ XXX.minecraft.nbt.ByteTag
- XXX.minecraft.nbt.ByteTag$1
+ XXX.minecraft.nbt.ByteTag$Cache
- XXX.minecraft.nbt.CollectionTag
+ XXX.minecraft.nbt.CompoundTag
- XXX.minecraft.nbt.CompoundTag$1
+ XXX.minecraft.nbt.CompoundTag$2
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
+ XXX.minecraft.nbt.ListTag$2
- XXX.minecraft.nbt.LongArrayTag
+ XXX.minecraft.nbt.LongArrayTag$1
- XXX.minecraft.nbt.LongTag
+ XXX.minecraft.nbt.LongTag$1
- XXX.minecraft.nbt.LongTag$Cache
+ XXX.minecraft.nbt.NbtAccounter
- XXX.minecraft.nbt.NbtAccounter$1
+ XXX.minecraft.nbt.NbtIo
- XXX.minecraft.nbt.NbtIo$1
+ XXX.minecraft.nbt.NbtOps
- XXX.minecraft.nbt.NbtOps$1
+ XXX.minecraft.nbt.NbtOps$ByteListCollector
- XXX.minecraft.nbt.NbtOps$HeterogenousListCollector
+ XXX.minecraft.nbt.NbtOps$HomogenousListCollector
- XXX.minecraft.nbt.NbtOps$InitialListCollector
+ XXX.minecraft.nbt.NbtOps$IntListCollector
- XXX.minecraft.nbt.NbtOps$ListCollector
+ XXX.minecraft.nbt.NbtOps$LongListCollector
- XXX.minecraft.nbt.NbtOps$NbtRecordBuilder
+ XXX.minecraft.nbt.NbtUtils
- XXX.minecraft.nbt.NumericTag
+ XXX.minecraft.nbt.package-info
+ XXX.minecraft.nbt.ShortTag
- XXX.minecraft.nbt.ShortTag$1
+ XXX.minecraft.nbt.ShortTag$Cache
- XXX.minecraft.nbt.SnbtPrinterTagVisitor
+ XXX.minecraft.nbt.StreamTagVisitor
- XXX.minecraft.nbt.StreamTagVisitor$EntryResult
+ XXX.minecraft.nbt.StreamTagVisitor$ValueResult
- XXX.minecraft.nbt.StringTag
+ XXX.minecraft.nbt.StringTag$1
- XXX.minecraft.nbt.StringTagVisitor
+ XXX.minecraft.nbt.Tag
- XXX.minecraft.nbt.TagParser
+ XXX.minecraft.nbt.TagType
- XXX.minecraft.nbt.TagType$1
+ XXX.minecraft.nbt.TagType$2
- XXX.minecraft.nbt.TagType$StaticSize
+ XXX.minecraft.nbt.TagType$VariableSize
- XXX.minecraft.nbt.TagTypes
+ XXX.minecraft.nbt.TagVisitor
- XXX.minecraft.nbt.TextComponentTagVisitor
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
- XXX.minecraft.network.ConnectionProtocol$PacketSet
+ XXX.minecraft.network.ConnectionProtocol$ProtocolBuilder
- XXX.minecraft.network.FriendlyByteBuf
+ XXX.minecraft.network.FriendlyByteBuf$Reader
- XXX.minecraft.network.FriendlyByteBuf$Writer
+ XXX.minecraft.network.package-info
+ XXX.minecraft.network.PacketDecoder
- XXX.minecraft.network.PacketEncoder
+ XXX.minecraft.network.PacketListener
- XXX.minecraft.network.PacketSendListener
+ XXX.minecraft.network.PacketSendListener$1
- XXX.minecraft.network.PacketSendListener$2
+ XXX.minecraft.network.RateKickingConnection
- XXX.minecraft.network.SkipPacketException
+ XXX.minecraft.network.TickablePacketListener
- XXX.minecraft.network.Varint21FrameDecoder
+ XXX.minecraft.network.Varint21LengthFieldPrepender
- XXX.minecraft.obfuscate.DontObfuscate
+ XXX.minecraft.obfuscate.package-info
+ XXX.minecraft.recipebook.package-info
+ XXX.minecraft.recipebook.PlaceRecipe
- XXX.minecraft.recipebook.ServerPlaceRecipe
- XXX.minecraft.resources.DelegatingOps
+ XXX.minecraft.resources.FileToIdConverter
- XXX.minecraft.resources.HolderSetCodec
+ XXX.minecraft.resources.package-info
+ XXX.minecraft.resources.RegistryDataLoader
- XXX.minecraft.resources.RegistryDataLoader$1
+ XXX.minecraft.resources.RegistryDataLoader$Loader
- XXX.minecraft.resources.RegistryDataLoader$RegistryData
+ XXX.minecraft.resources.RegistryFileCodec
- XXX.minecraft.resources.RegistryFixedCodec
+ XXX.minecraft.resources.RegistryOps
- XXX.minecraft.resources.RegistryOps$1
+ XXX.minecraft.resources.RegistryOps$2
- XXX.minecraft.resources.RegistryOps$RegistryInfo
+ XXX.minecraft.resources.RegistryOps$RegistryInfoLookup
- XXX.minecraft.resources.ResourceKey
+ XXX.minecraft.resources.ResourceKey$InternKey
- XXX.minecraft.resources.ResourceLocation
+ XXX.minecraft.resources.ResourceLocation$Dummy
- XXX.minecraft.resources.ResourceLocation$Serializer
- XXX.minecraft.server.Bootstrap
+ XXX.minecraft.server.Bootstrap$1
- XXX.minecraft.server.ChainedJsonException
+ XXX.minecraft.server.ChainedJsonException$Entry
- XXX.minecraft.server.ConsoleInput
+ XXX.minecraft.server.DebugLoggedPrintStream
- XXX.minecraft.server.Eula
+ XXX.minecraft.server.LoggedPrintStream
- XXX.minecraft.server.Main
+ XXX.minecraft.server.Main$1
- XXX.minecraft.server.MinecraftServer
+ XXX.minecraft.server.MinecraftServer$1
- XXX.minecraft.server.MinecraftServer$ReloadableResources
+ XXX.minecraft.server.MinecraftServer$ServerResourcePackInfo
- XXX.minecraft.server.MinecraftServer$TimeProfiler
+ XXX.minecraft.server.MinecraftServer$TimeProfiler$1
- XXX.minecraft.server.PlayerAdvancements
+ XXX.minecraft.server.PlayerAdvancements$1
- XXX.minecraft.server.RegistryLayer
+ XXX.minecraft.server.ReloadableServerResources
- XXX.minecraft.server.RunningOnDifferentThreadException
+ XXX.minecraft.server.ServerAdvancementManager
- XXX.minecraft.server.ServerFunctionLibrary
+ XXX.minecraft.server.ServerFunctionManager
- XXX.minecraft.server.ServerFunctionManager$ExecutionContext
+ XXX.minecraft.server.ServerFunctionManager$QueuedCommand
- XXX.minecraft.server.ServerFunctionManager$TraceCallbacks
+ XXX.minecraft.server.ServerInterface
- XXX.minecraft.server.ServerScoreboard
+ XXX.minecraft.server.ServerScoreboard$Method
- XXX.minecraft.server.Services
+ XXX.minecraft.server.TickTask
- XXX.minecraft.server.WorldLoader
+ XXX.minecraft.server.WorldLoader$DataLoadContext
- XXX.minecraft.server.WorldLoader$DataLoadOutput
+ XXX.minecraft.server.WorldLoader$InitConfig
- XXX.minecraft.server.WorldLoader$PackConfig
+ XXX.minecraft.server.WorldLoader$ResultFactory
- XXX.minecraft.server.WorldLoader$WorldDataSupplier
+ XXX.minecraft.server.WorldStem
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
+ XXX.minecraft.tags.BannerPatternTags
- XXX.minecraft.tags.BiomeTags
+ XXX.minecraft.tags.BlockTags
- XXX.minecraft.tags.CatVariantTags
+ XXX.minecraft.tags.EntityTypeTags
- XXX.minecraft.tags.FlatLevelGeneratorPresetTags
+ XXX.minecraft.tags.FluidTags
- XXX.minecraft.tags.GameEventTags
+ XXX.minecraft.tags.InstrumentTags
- XXX.minecraft.tags.ItemTags
- XXX.minecraft.tags.package-info
+ XXX.minecraft.tags.PaintingVariantTags
- XXX.minecraft.tags.PoiTypeTags
+ XXX.minecraft.tags.StructureTags
- XXX.minecraft.tags.TagBuilder
+ XXX.minecraft.tags.TagEntry
- XXX.minecraft.tags.TagEntry$Lookup
+ XXX.minecraft.tags.TagFile
- XXX.minecraft.tags.TagKey
+ XXX.minecraft.tags.TagLoader
- XXX.minecraft.tags.TagLoader$1
+ XXX.minecraft.tags.TagLoader$EntryWithSource
- XXX.minecraft.tags.TagManager
+ XXX.minecraft.tags.TagManager$LoadResult
- XXX.minecraft.tags.TagNetworkSerialization
+ XXX.minecraft.tags.TagNetworkSerialization$NetworkPayload
- XXX.minecraft.tags.TagNetworkSerialization$TagOutput
+ XXX.minecraft.tags.WorldPresetTags
- XXX.minecraft.util.AbortableIterationConsumer$Continuation
+ XXX.minecraft.util.BitStorage
- XXX.minecraft.util.ClassInstanceMultiMap
+ XXX.minecraft.util.CrudeIncrementalIntIdentityHashBiMap
- XXX.minecraft.util.Crypt
+ XXX.minecraft.util.Crypt$ByteArrayToKeyFunction
- XXX.minecraft.util.Crypt$SaltSignaturePair
+ XXX.minecraft.util.Crypt$SaltSupplier
- XXX.minecraft.util.CryptException
+ XXX.minecraft.util.CsvOutput
- XXX.minecraft.util.CsvOutput$Builder
+ XXX.minecraft.util.CubicSampler
- XXX.minecraft.util.CubicSampler$Vec3Fetcher
+ XXX.minecraft.util.CubicSpline
- XXX.minecraft.util.CubicSpline$1Point
+ XXX.minecraft.util.CubicSpline$Builder
- XXX.minecraft.util.CubicSpline$Constant
+ XXX.minecraft.util.CubicSpline$CoordinateVisitor
- XXX.minecraft.util.CubicSpline$Multipoint
+ XXX.minecraft.util.DebugBuffer
- XXX.minecraft.util.DirectoryLock
+ XXX.minecraft.util.DirectoryLock$LockException
- XXX.minecraft.util.ExceptionCollector
+ XXX.minecraft.util.ExtraCodecs
- XXX.minecraft.util.ExtraCodecs$1
+ XXX.minecraft.util.ExtraCodecs$1ContextRetrievalCodec
- XXX.minecraft.util.ExtraCodecs$2
+ XXX.minecraft.util.ExtraCodecs$3
- XXX.minecraft.util.ExtraCodecs$4
+ XXX.minecraft.util.ExtraCodecs$EitherCodec
- XXX.minecraft.util.ExtraCodecs$LazyInitializedCodec
+ XXX.minecraft.util.ExtraCodecs$TagOrElementLocation
- XXX.minecraft.util.ExtraCodecs$XorCodec
+ XXX.minecraft.util.FastBufferedInputStream
- XXX.minecraft.util.FastColor
+ XXX.minecraft.util.FastColor$ARGB32
- XXX.minecraft.util.FileZipper
+ XXX.minecraft.util.FormattedCharSequence
- XXX.minecraft.util.FormattedCharSink
+ XXX.minecraft.util.FrameTimer
- XXX.minecraft.util.FutureChain
+ XXX.minecraft.util.Graph
- XXX.minecraft.util.GsonHelper
+ XXX.minecraft.util.HttpUtil
- XXX.minecraft.util.InclusiveRange
+ XXX.minecraft.util.KeyDispatchDataCodec
- XXX.minecraft.util.LazyLoadedValue
+ XXX.minecraft.util.LinearCongruentialGenerator
- XXX.minecraft.util.LowerCaseEnumTypeAdapterFactory
+ XXX.minecraft.util.LowerCaseEnumTypeAdapterFactory$1
- XXX.minecraft.util.MemoryReserve
+ XXX.minecraft.util.ModCheck
- XXX.minecraft.util.ModCheck$Confidence
+ XXX.minecraft.util.Mth
- XXX.minecraft.util.NativeModuleLister
+ XXX.minecraft.util.NativeModuleLister$NativeModuleInfo
- XXX.minecraft.util.NativeModuleLister$NativeModuleVersion
+ XXX.minecraft.util.OptionEnum
- XXX.minecraft.util.ParticleUtils
+ XXX.minecraft.util.ProgressListener
- XXX.minecraft.util.RandomSource
+ XXX.minecraft.util.TelemetryConstants
- XXX.minecraft.util.ThreadingDetector
+ XXX.minecraft.util.TimeSource
- XXX.minecraft.util.TimeSource$NanoTimeSource
+ XXX.minecraft.util.TimeUtil
- XXX.minecraft.util.ToFloatFunction
+ XXX.minecraft.util.ToFloatFunction$1
- XXX.minecraft.util.ToFloatFunction$2
+ XXX.minecraft.util.Tuple
- XXX.minecraft.util.Unit
+ XXX.minecraft.util.VisibleForDebug
- XXX.minecraft.util.ZeroBitStorage
- XXX.models.blockstates.BlockStateGenerator
+ XXX.models.blockstates.Condition
- XXX.models.blockstates.Condition$CompositeCondition
+ XXX.models.blockstates.Condition$Operation
- XXX.models.blockstates.Condition$TerminalCondition
+ XXX.models.blockstates.MultiPartGenerator
- XXX.models.blockstates.MultiPartGenerator$ConditionalEntry
+ XXX.models.blockstates.MultiPartGenerator$Entry
- XXX.models.blockstates.MultiVariantGenerator
- XXX.models.blockstates.package-info
+ XXX.models.blockstates.PropertyDispatch
- XXX.models.blockstates.PropertyDispatch$C1
+ XXX.models.blockstates.PropertyDispatch$C2
- XXX.models.blockstates.PropertyDispatch$C3
+ XXX.models.blockstates.PropertyDispatch$C4
- XXX.models.blockstates.PropertyDispatch$C5
+ XXX.models.blockstates.PropertyDispatch$PentaFunction
- XXX.models.blockstates.PropertyDispatch$QuadFunction
+ XXX.models.blockstates.PropertyDispatch$TriFunction
- XXX.models.blockstates.Selector
+ XXX.models.blockstates.Variant
- XXX.models.blockstates.VariantProperties
+ XXX.models.blockstates.VariantProperties$Rotation
- XXX.models.blockstates.VariantProperty
+ XXX.models.blockstates.VariantProperty$Value
+ XXX.models.model.DelegatedModel
- XXX.models.model.ModelLocationUtils
+ XXX.models.model.ModelTemplate
- XXX.models.model.ModelTemplates
+ XXX.models.model.package-info
+ XXX.models.model.TexturedModel
- XXX.models.model.TexturedModel$Provider
+ XXX.models.model.TextureMapping
- XXX.models.model.TextureSlot
- XXX.nbt.visitors.CollectFields
+ XXX.nbt.visitors.CollectToTag
- XXX.nbt.visitors.FieldSelector
+ XXX.nbt.visitors.FieldTree
+ XXX.nbt.visitors.package-info
- XXX.nbt.visitors.SkipAll
+ XXX.nbt.visitors.SkipAll$1
- XXX.nbt.visitors.SkipFields
- XXX.network.chat.ChatDecorator
+ XXX.network.chat.ChatType
- XXX.network.chat.ChatType$Bound
+ XXX.network.chat.ChatType$BoundNetwork
- XXX.network.chat.ChatTypeDecoration
+ XXX.network.chat.ChatTypeDecoration$Parameter
- XXX.network.chat.ChatTypeDecoration$Parameter$Selector
+ XXX.network.chat.ClickEvent
- XXX.network.chat.ClickEvent$Action
+ XXX.network.chat.CommonComponents
- XXX.network.chat.Component
+ XXX.network.chat.Component$Serializer
- XXX.network.chat.ComponentContents
+ XXX.network.chat.ComponentContents$1
- XXX.network.chat.ComponentUtils
+ XXX.network.chat.FilterMask
- XXX.network.chat.FilterMask$1
+ XXX.network.chat.FilterMask$Type
- XXX.network.chat.FormattedText
+ XXX.network.chat.FormattedText$1
- XXX.network.chat.FormattedText$2
+ XXX.network.chat.FormattedText$3
- XXX.network.chat.FormattedText$4
+ XXX.network.chat.FormattedText$ContentConsumer
- XXX.network.chat.FormattedText$StyledContentConsumer
+ XXX.network.chat.HoverEvent
- XXX.network.chat.HoverEvent$Action
+ XXX.network.chat.HoverEvent$EntityTooltipInfo
- XXX.network.chat.HoverEvent$ItemStackInfo
+ XXX.network.chat.LastSeenMessages
- XXX.network.chat.LastSeenMessages$Packed
+ XXX.network.chat.LastSeenMessages$Update
- XXX.network.chat.LastSeenMessagesTracker
+ XXX.network.chat.LastSeenMessagesTracker$Update
- XXX.network.chat.LastSeenMessagesValidator
+ XXX.network.chat.LastSeenTrackedEntry
- XXX.network.chat.LocalChatSession
+ XXX.network.chat.MessageSignature
- XXX.network.chat.MessageSignature$Packed
+ XXX.network.chat.MessageSignatureCache
- XXX.network.chat.MutableComponent
+ XXX.network.chat.OutgoingChatMessage
- XXX.network.chat.OutgoingChatMessage$Disguised
+ XXX.network.chat.OutgoingChatMessage$Player
- XXX.network.chat.package-info
- XXX.network.chat.PlayerChatMessage
+ XXX.network.chat.RemoteChatSession
- XXX.network.chat.RemoteChatSession$Data
+ XXX.network.chat.SignableCommand
- XXX.network.chat.SignableCommand$Argument
+ XXX.network.chat.SignedMessageBody
- XXX.network.chat.SignedMessageBody$Packed
+ XXX.network.chat.SignedMessageChain
- XXX.network.chat.SignedMessageChain$DecodeException
+ XXX.network.chat.SignedMessageChain$Decoder
- XXX.network.chat.SignedMessageChain$Encoder
+ XXX.network.chat.SignedMessageLink
- XXX.network.chat.SignedMessageValidator
+ XXX.network.chat.SignedMessageValidator$KeyBased
- XXX.network.chat.Style
+ XXX.network.chat.Style$1
- XXX.network.chat.Style$1Collector
+ XXX.network.chat.Style$Serializer
- XXX.network.chat.SubStringSource
+ XXX.network.chat.TextColor
- XXX.network.chat.ThrowingComponent
- XXX.network.protocol.package-info
- XXX.network.protocol.Packet
+ XXX.network.protocol.PacketFlow
- XXX.network.protocol.PacketUtils
- XXX.network.syncher.EntityDataAccessor
+ XXX.network.syncher.EntityDataSerializer
- XXX.network.syncher.EntityDataSerializer$1
+ XXX.network.syncher.EntityDataSerializer$ForValueType
- XXX.network.syncher.EntityDataSerializers
+ XXX.network.syncher.EntityDataSerializers$1
- XXX.network.syncher.EntityDataSerializers$2
+ XXX.network.syncher.EntityDataSerializers$3
- XXX.network.syncher.EntityDataSerializers$4
+ XXX.network.syncher.EntityDataSerializers$5
- XXX.network.syncher.EntityDataSerializers$6
+ XXX.network.syncher.EntityDataSerializers$7
+ XXX.network.syncher.package-info
- XXX.network.syncher.SynchedEntityData
+ XXX.network.syncher.SynchedEntityData$DataItem
- XXX.network.syncher.SynchedEntityData$DataValue
- XXX.packs.resources.package-info
+ XXX.packs.resources.ResourceFilterSection$ResourceLocationPattern
- XXX.packs.resources.ResourceManager
+ XXX.packs.resources.ResourceManager$Empty
- XXX.packs.resources.ResourceManagerReloadListener
+ XXX.packs.resources.ResourceMetadata
- XXX.packs.resources.ResourceMetadata$1
+ XXX.packs.resources.ResourceMetadata$2
- XXX.packs.resources.ResourceProvider
+ XXX.packs.resources.SimpleJsonResourceReloadListener
- XXX.packs.resources.SimplePreparableReloadListener
+ XXX.packs.resources.SimpleReloadInstance
- XXX.packs.resources.SimpleReloadInstance$1
+ XXX.packs.resources.SimpleReloadInstance$StateFactory
- XXX.protocol.game.ClientboundAddEntityPacket
+ XXX.protocol.game.ClientboundAddExperienceOrbPacket
- XXX.protocol.game.ClientboundAddPlayerPacket
+ XXX.protocol.game.ClientboundAnimatePacket
- XXX.protocol.game.ClientboundAwardStatsPacket
+ XXX.protocol.game.ClientboundBlockChangedAckPacket
- XXX.protocol.game.ClientboundBlockDestructionPacket
+ XXX.protocol.game.ClientboundBlockEntityDataPacket
- XXX.protocol.game.ClientboundBlockEventPacket
+ XXX.protocol.game.ClientboundBlockUpdatePacket
- XXX.protocol.game.ClientboundBossEventPacket
+ XXX.protocol.game.ClientboundBossEventPacket$1
- XXX.protocol.game.ClientboundBossEventPacket$AddOperation
+ XXX.protocol.game.ClientboundBossEventPacket$Handler
- XXX.protocol.game.ClientboundBossEventPacket$Operation
+ XXX.protocol.game.ClientboundBossEventPacket$OperationType
- XXX.protocol.game.ClientboundBossEventPacket$UpdateNameOperation
+ XXX.protocol.game.ClientboundBossEventPacket$UpdateProgressOperation
- XXX.protocol.game.ClientboundBossEventPacket$UpdatePropertiesOperation
+ XXX.protocol.game.ClientboundBossEventPacket$UpdateStyleOperation
- XXX.protocol.game.ClientboundChangeDifficultyPacket
+ XXX.protocol.game.ClientboundClearTitlesPacket
+ XXX.protocol.game.ClientboundCommandsPacket
- XXX.protocol.game.ClientboundCommandsPacket$ArgumentNodeStub
+ XXX.protocol.game.ClientboundCommandsPacket$Entry
- XXX.protocol.game.ClientboundCommandsPacket$LiteralNodeStub
+ XXX.protocol.game.ClientboundCommandsPacket$NodeResolver
- XXX.protocol.game.ClientboundCommandsPacket$NodeStub
- XXX.protocol.game.ClientboundCommandSuggestionsPacket
+ XXX.protocol.game.ClientboundContainerClosePacket
- XXX.protocol.game.ClientboundContainerSetContentPacket
+ XXX.protocol.game.ClientboundContainerSetDataPacket
- XXX.protocol.game.ClientboundContainerSetSlotPacket
+ XXX.protocol.game.ClientboundCooldownPacket
- XXX.protocol.game.ClientboundCustomChatCompletionsPacket
+ XXX.protocol.game.ClientboundCustomChatCompletionsPacket$Action
- XXX.protocol.game.ClientboundCustomPayloadPacket
+ XXX.protocol.game.ClientboundCustomSoundPacket
- XXX.protocol.game.ClientboundDeleteChatPacket
+ XXX.protocol.game.ClientboundDisconnectPacket
- XXX.protocol.game.ClientboundDisguisedChatPacket
+ XXX.protocol.game.ClientboundEntityEventPacket
- XXX.protocol.game.ClientboundExplodePacket
+ XXX.protocol.game.ClientboundForgetLevelChunkPacket
- XXX.protocol.game.ClientboundGameEventPacket
+ XXX.protocol.game.ClientboundGameEventPacket$Type
- XXX.protocol.game.ClientboundHorseScreenOpenPacket
+ XXX.protocol.game.ClientboundInitializeBorderPacket
- XXX.protocol.game.ClientboundKeepAlivePacket
+ XXX.protocol.game.ClientboundLevelChunkPacketData
- XXX.protocol.game.ClientboundLevelChunkPacketData$BlockEntityInfo
+ XXX.protocol.game.ClientboundLevelChunkPacketData$BlockEntityTagOutput
- XXX.protocol.game.ClientboundLevelChunkWithLightPacket
+ XXX.protocol.game.ClientboundLevelEventPacket
- XXX.protocol.game.ClientboundLevelParticlesPacket
+ XXX.protocol.game.ClientboundLightUpdatePacket
- XXX.protocol.game.ClientboundLightUpdatePacketData
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
- XXX.protocol.game.ClientboundPingPacket
+ XXX.protocol.game.ClientboundPlaceGhostRecipePacket
- XXX.protocol.game.ClientboundPlayerAbilitiesPacket
+ XXX.protocol.game.ClientboundPlayerChatPacket
- XXX.protocol.game.ClientboundPlayerCombatEndPacket
+ XXX.protocol.game.ClientboundPlayerCombatEnterPacket
- XXX.protocol.game.ClientboundPlayerCombatKillPacket
+ XXX.protocol.game.ClientboundPlayerInfoRemovePacket
- XXX.protocol.game.ClientboundPlayerInfoUpdatePacket
+ XXX.protocol.game.ClientboundPlayerInfoUpdatePacket$Action
- XXX.protocol.game.ClientboundPlayerInfoUpdatePacket$Action$Reader
+ XXX.protocol.game.ClientboundPlayerInfoUpdatePacket$Action$Writer
- XXX.protocol.game.ClientboundPlayerInfoUpdatePacket$Entry
+ XXX.protocol.game.ClientboundPlayerInfoUpdatePacket$EntryBuilder
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
- XXX.protocol.game.ClientboundSectionBlocksUpdatePacket
+ XXX.protocol.game.ClientboundSelectAdvancementsTabPacket
- XXX.protocol.game.ClientboundServerDataPacket
+ XXX.protocol.game.ClientboundSetActionBarTextPacket
- XXX.protocol.game.ClientboundSetBorderCenterPacket
+ XXX.protocol.game.ClientboundSetBorderLerpSizePacket
- XXX.protocol.game.ClientboundSetBorderSizePacket
+ XXX.protocol.game.ClientboundSetBorderWarningDelayPacket
- XXX.protocol.game.ClientboundSetBorderWarningDistancePacket
+ XXX.protocol.game.ClientboundSetCameraPacket
- XXX.protocol.game.ClientboundSetCarriedItemPacket
+ XXX.protocol.game.ClientboundSetChunkCacheCenterPacket
- XXX.protocol.game.ClientboundSetChunkCacheRadiusPacket
+ XXX.protocol.game.ClientboundSetDefaultSpawnPositionPacket
- XXX.protocol.game.ClientboundSetDisplayObjectivePacket
+ XXX.protocol.game.ClientboundSetEntityDataPacket
- XXX.protocol.game.ClientboundSetEntityLinkPacket
+ XXX.protocol.game.ClientboundSetEntityMotionPacket
- XXX.protocol.game.ClientboundSetEquipmentPacket
+ XXX.protocol.game.ClientboundSetExperiencePacket
- XXX.protocol.game.ClientboundSetHealthPacket
+ XXX.protocol.game.ClientboundSetObjectivePacket
- XXX.protocol.game.ClientboundSetPassengersPacket
+ XXX.protocol.game.ClientboundSetPlayerTeamPacket
- XXX.protocol.game.ClientboundSetPlayerTeamPacket$Action
+ XXX.protocol.game.ClientboundSetPlayerTeamPacket$Parameters
- XXX.protocol.game.ClientboundSetScorePacket
+ XXX.protocol.game.ClientboundSetSimulationDistancePacket
- XXX.protocol.game.ClientboundSetSubtitleTextPacket
+ XXX.protocol.game.ClientboundSetTimePacket
+ XXX.protocol.game.ClientboundSetTitlesAnimationPacket
- XXX.protocol.game.ClientboundSetTitleTextPacket
- XXX.protocol.game.ClientboundSoundEntityPacket
+ XXX.protocol.game.ClientboundSoundPacket
- XXX.protocol.game.ClientboundStopSoundPacket
+ XXX.protocol.game.ClientboundSystemChatPacket
- XXX.protocol.game.ClientboundTabListPacket
+ XXX.protocol.game.ClientboundTagQueryPacket
- XXX.protocol.game.ClientboundTakeItemEntityPacket
+ XXX.protocol.game.ClientboundTeleportEntityPacket
- XXX.protocol.game.ClientboundUpdateAdvancementsPacket
+ XXX.protocol.game.ClientboundUpdateAttributesPacket
- XXX.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
+ XXX.protocol.game.ClientboundUpdateEnabledFeaturesPacket
- XXX.protocol.game.ClientboundUpdateMobEffectPacket
+ XXX.protocol.game.ClientboundUpdateRecipesPacket
- XXX.protocol.game.ClientboundUpdateTagsPacket
+ XXX.protocol.game.ClientGamePacketListener
+ XXX.protocol.game.DebugEntityNameGenerator
- XXX.protocol.game.DebugPackets
+ XXX.protocol.game.package-info
+ XXX.protocol.game.ServerboundAcceptTeleportationPacket
- XXX.protocol.game.ServerboundBlockEntityTagQuery
+ XXX.protocol.game.ServerboundChangeDifficultyPacket
- XXX.protocol.game.ServerboundChatAckPacket
+ XXX.protocol.game.ServerboundChatCommandPacket
- XXX.protocol.game.ServerboundChatPacket
+ XXX.protocol.game.ServerboundChatSessionUpdatePacket
- XXX.protocol.game.ServerboundClientCommandPacket
+ XXX.protocol.game.ServerboundClientCommandPacket$Action
- XXX.protocol.game.ServerboundClientInformationPacket
+ XXX.protocol.game.ServerboundCommandSuggestionPacket
- XXX.protocol.game.ServerboundContainerButtonClickPacket
+ XXX.protocol.game.ServerboundContainerClickPacket
- XXX.protocol.game.ServerboundContainerClosePacket
+ XXX.protocol.game.ServerboundCustomPayloadPacket
- XXX.protocol.game.ServerboundEditBookPacket
+ XXX.protocol.game.ServerboundEntityTagQuery
- XXX.protocol.game.ServerboundInteractPacket
+ XXX.protocol.game.ServerboundInteractPacket$1
- XXX.protocol.game.ServerboundInteractPacket$Action
+ XXX.protocol.game.ServerboundInteractPacket$ActionType
- XXX.protocol.game.ServerboundInteractPacket$Handler
+ XXX.protocol.game.ServerboundInteractPacket$InteractionAction
- XXX.protocol.game.ServerboundInteractPacket$InteractionAtLocationAction
+ XXX.protocol.game.ServerboundJigsawGeneratePacket
- XXX.protocol.game.ServerboundKeepAlivePacket
+ XXX.protocol.game.ServerboundLockDifficultyPacket
- XXX.protocol.game.ServerboundMovePlayerPacket
+ XXX.protocol.game.ServerboundMovePlayerPacket$Pos
- XXX.protocol.game.ServerboundMovePlayerPacket$PosRot
+ XXX.protocol.game.ServerboundMovePlayerPacket$Rot
- XXX.protocol.game.ServerboundMovePlayerPacket$StatusOnly
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
+ XXX.protocol.game.ServerboundPongPacket
- XXX.protocol.game.ServerboundRecipeBookChangeSettingsPacket
+ XXX.protocol.game.ServerboundRecipeBookSeenRecipePacket
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
- XXX.protocol.game.ServerPacketListener
- XXX.protocol.game.VecDeltaCodec
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
- XXX.rcon.thread.GenericThread
+ XXX.rcon.thread.package-info
+ XXX.rcon.thread.QueryThreadGs4
- XXX.rcon.thread.QueryThreadGs4$RequestChallenge
+ XXX.rcon.thread.RconClient
- XXX.rcon.thread.RconThread
- XXX.recipes.packs.BundleRecipeProvider
+ XXX.recipes.packs.package-info
+ XXX.recipes.packs.UpdateOneTwentyRecipeProvider
- XXX.recipes.packs.VanillaRecipeProvider
- XXX.server.bossevents.CustomBossEvent
+ XXX.server.bossevents.CustomBossEvents
- XXX.server.bossevents.package-info
+ XXX.server.chase.ChaseClient
- XXX.server.chase.ChaseClient$TeleportTarget
+ XXX.server.chase.ChaseServer
- XXX.server.chase.ChaseServer$PlayerPosition
+ XXX.server.chase.package-info
- XXX.server.commands.AdvancementCommands
+ XXX.server.commands.AdvancementCommands$Action
- XXX.server.commands.AdvancementCommands$Action$1
+ XXX.server.commands.AdvancementCommands$Action$2
- XXX.server.commands.AdvancementCommands$Mode
+ XXX.server.commands.AttributeCommand
- XXX.server.commands.BanIpCommands
+ XXX.server.commands.BanListCommands
- XXX.server.commands.BanPlayerCommands
+ XXX.server.commands.BossBarCommands
- XXX.server.commands.ChaseCommand
+ XXX.server.commands.ClearInventoryCommands
- XXX.server.commands.CloneCommands
+ XXX.server.commands.CloneCommands$CloneBlockInfo
- XXX.server.commands.CloneCommands$Mode
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
- XXX.util.datafix.DataFixerOptimizationOption
+ XXX.util.datafix.DataFixers
- XXX.util.datafix.DataFixers$1
+ XXX.util.datafix.DataFixers$2
- XXX.util.datafix.DataFixers$3
+ XXX.util.datafix.DataFixTypes
+ XXX.util.datafix.package-info
+ XXX.util.datafix.PackedBitStorage
- XXX.util.eventlog.EventLogDirectory$CompressedFile
- XXX.util.eventlog.EventLogDirectory$FileId
- XXX.util.eventlog.EventLogDirectory$RawFile
- XXX.util.eventlog.JsonEventLog$1
- XXX.util.eventlog.JsonEventLogReader$1
+ XXX.world.item.StackInventory
- XXX.worldgen.biome.Biomes
+ XXX.worldgen.biome.EndBiomes
- XXX.worldgen.biome.NetherBiomes
+ XXX.worldgen.biome.OverworldBiomes
- XXX.worldgen.biome.package-info
+ XXX.worldgen.features.AquaticFeatures
- XXX.worldgen.features.CaveFeatures
+ XXX.worldgen.features.EndFeatures
- XXX.worldgen.features.FeatureUtils
+ XXX.worldgen.features.MiscOverworldFeatures
- XXX.worldgen.features.NetherFeatures
+ XXX.worldgen.features.OreFeatures
+ XXX.worldgen.features.package-info
- XXX.worldgen.features.PileFeatures
+ XXX.worldgen.features.TreeFeatures
- XXX.worldgen.features.VegetationFeatures
+ XXX.worldgen.placement.AquaticPlacements
- XXX.worldgen.placement.CavePlacements
+ XXX.worldgen.placement.EndPlacements
- XXX.worldgen.placement.MiscOverworldPlacements
+ XXX.worldgen.placement.NetherPlacements
- XXX.worldgen.placement.OrePlacements
+ XXX.worldgen.placement.package-info
+ XXX.worldgen.placement.PlacementUtils
- XXX.worldgen.placement.TreePlacements
+ XXX.worldgen.placement.VegetationPlacements
- XXX.worldgen.placement.VillagePlacements
```

</details>
<details>
<summary>
Changes
</summary>

```
net.minecraft.SharedConstants +1P
```
```
XXX.arguments.selector.EntitySelector +5M -3M | +1P
```
```
XXX.arguments.selector.EntitySelectorParser +9M -10M | -1P
```
```
XXX.advancements.packs.VanillaHusbandryAdvancements +5M
```
```
XXX.data.models.BlockModelGenerators +9M -6M | +1P
```
```
XXX.server.level.ChunkMap +1M
```
```
XXX.server.level.ServerLevel +4M -1M
```
```
XXX.world.effect.MobEffectInstance -2M | -1P
```
```
XXX.world.item.CreativeModeTab +2M -2M | +2P -2P
```
```
XXX.world.item.CreativeModeTab$ItemDisplayBuilder -2M | +2P -2P
```
```
XXX.world.item.ItemStackLinkedSet +2M | +1P -1P
```
```
XXX.world.level.Level +3M -1M
```
```
XXX.level.block.BedBlock +1M -1M
```
```
XXX.level.block.Blocks +2P
```
```
XXX.level.block.ChiseledBookShelfBlock +6M -3M | +3P -2P
```
```
XXX.block.entity.ChiseledBookShelfBlockEntity +5M -13M | +1P -1P
```
```
XXX.block.entity.SkullBlockEntity +2M -2M | +2P -2P
```
```
XXX.state.properties.BlockStateProperties +7P -2P
```
```
XXX.level.entity.EntityLookup +1M -1M
```
```
XXX.level.entity.EntitySection +2M -2M
```
```
XXX.level.entity.LevelEntityGetter +2P -2P
```

</details>
<details>
<summary>
net.minecraft.commands.arguments.selector.EntitySelector
</summary>

```diff
+ boolean lambda$findEntities$0(CommandSourceStack,Entity)
- boolean lambda$findEntities$1(CommandSourceStack,Entity)
+ boolean lambda$getPredicate$1(AABB,Entity)
- boolean lambda$getPredicate$2(AABB,Entity)
+ boolean lambda$getPredicate$2(Vec3,Entity)
- boolean lambda$getPredicate$3(Vec3,Entity)
- int getResultLimit()
- void lambda$static$0(Vec3,List)
```

</details>
<details>
<summary>
net.minecraft.commands.arguments.selector.EntitySelectorParser
</summary>

```diff
- boolean lambda$createRotationPredicate$12(ToDoubleFunction,double,double,Entity)
+ boolean lambda$createRotationPredicate$13(ToDoubleFunction,double,double,Entity)
- boolean lambda$finalizePredicates$11(Entity)
+ boolean lambda$finalizePredicates$12(Entity)
- boolean lambda$new$8(Entity)
+ boolean lambda$new$9(Entity)
- CompletableFuture lambda$static$7(SuggestionsBuilder,Consumer)
+ CompletableFuture lambda$static$8(SuggestionsBuilder,Consumer)
- int lambda$static$2(Vec3,Entity,Entity)
+ int lambda$static$3(Vec3,Entity,Entity)
- int lambda$static$4(Vec3,Entity,Entity)
+ int lambda$static$5(Vec3,Entity,Entity)
+ Vec3 lambda$getSelector$11(Vec3)
- Vec3 lambda$getSelector$9(Vec3)
+ void lambda$static$2(Vec3,List)
- void lambda$static$3(Vec3,List)
+ void lambda$static$4(Vec3,List)
- void lambda$static$5(Vec3,List)
+ void lambda$static$7(Vec3,List)
```

</details>
<details>
<summary>
net.minecraft.data.advancements.packs.VanillaHusbandryAdvancements
</summary>

```diff
- Advancement createBreedAllAnimalsAdvancement(Advancement,Consumer)
- Advancement createBreedAnAnimalAdvancement(Advancement,Consumer)
- Advancement createRoot(Consumer)
- EntityType[] getBreedableAnimals()
- EntityType[] getIndirectlyBreedableAnimals()
```

</details>
<details>
<summary>
net.minecraft.data.models.BlockModelGenerators
</summary>

```diff
- ResourceLocation lambda$addBookSlotModel$47(ModelTemplate,String,TextureMapping,BlockModelGenerators$BookSlotModelCacheKey)
+ ResourceLocation lambda$createChiseledBookshelf$45(Integer)
+ Variant lambda$createChiseledBookshelf$46(List,Integer)
+ Variant lambda$createJigsaw$48(FrontAndTop)
- Variant lambda$createJigsaw$49(FrontAndTop)
+ Variant lambda$createRespawnAnchor$47(ResourceLocation[],Integer)
- Variant lambda$createRespawnAnchor$48(ResourceLocation[],Integer)
- void addBookSlotModel(MultiPartGenerator,Condition$TerminalCondition,VariantProperties$Rotation,BooleanProperty,ModelTemplate,boolean)
- void addSlotStateAndRotationVariants(MultiPartGenerator,Condition$TerminalCondition,VariantProperties$Rotation)
- void lambda$addSlotStateAndRotationVariants$46(MultiPartGenerator,Condition$TerminalCondition,VariantProperties$Rotation,BooleanProperty,ModelTemplate)
- void lambda$createChiseledBookshelf$45(MultiPartGenerator,ResourceLocation,Direction,VariantProperties$Rotation)
+ void lambda$run$49(BlockFamily)
- void lambda$run$50(BlockFamily)
+ void lambda$run$50(SpawnEggItem)
- void lambda$run$51(SpawnEggItem)
```

</details>
<details>
<summary>
net.minecraft.server.level.ChunkMap
</summary>

```diff
- void resendChunk(ChunkAccess)
```

</details>
<details>
<summary>
net.minecraft.server.level.ServerLevel
</summary>

```diff
- AbortableIterationConsumer$Continuation lambda$getEntities$11(Predicate,List,int,Entity)
- List getPlayers(Predicate,int)
- void getEntities(EntityTypeTest,Predicate,List,int)
- void getEntities(EntityTypeTest,Predicate,List)
+ void lambda$getEntities$11(Predicate,List,Entity)
```

</details>
<details>
<summary>
net.minecraft.world.effect.MobEffectInstance
</summary>

```diff
+ boolean isNoCounter()
+ void setNoCounter(boolean)
```

</details>
<details>
<summary>
net.minecraft.world.item.CreativeModeTab
</summary>

```diff
- Collection getDisplayItems()
- Collection getSearchTabDisplayItems()
+ ItemStackLinkedSet getDisplayItems()
+ ItemStackLinkedSet getSearchTabDisplayItems()
```

</details>
<details>
<summary>
net.minecraft.world.item.CreativeModeTab$ItemDisplayBuilder
</summary>

```diff
+ ItemStackLinkedSet getSearchTabContents()
+ ItemStackLinkedSet getTabContents()
```

</details>
<details>
<summary>
net.minecraft.world.item.ItemStackLinkedSet
</summary>

```diff
- int hashStackAndTag(ItemStack)
- Set createTypeAndTagSet()
```

</details>
<details>
<summary>
net.minecraft.world.level.Level
</summary>

```diff
- AbortableIterationConsumer$Continuation lambda$getEntities$2(Predicate,List,int,EntityTypeTest,Entity)
- void getEntities(EntityTypeTest,AABB,Predicate,List,int)
- void getEntities(EntityTypeTest,AABB,Predicate,List)
+ void lambda$getEntities$2(Predicate,List,EntityTypeTest,Entity)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BedBlock
</summary>

```diff
- Optional findStandUpPosition(EntityType,CollisionGetter,BlockPos,Direction,float)
+ Optional findStandUpPosition(EntityType,CollisionGetter,BlockPos,float)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.ChiseledBookShelfBlock
</summary>

```diff
- int getHitSlot(Vec2)
- int getSection(float)
- InteractionResult tryAddBook(Level,BlockPos,Player,ChiseledBookShelfBlockEntity,ItemStack,int)
+ InteractionResult tryAddBook(Level,BlockPos,Player,ChiseledBookShelfBlockEntity,ItemStack)
- InteractionResult tryRemoveBook(Level,BlockPos,Player,ChiseledBookShelfBlockEntity,int)
+ InteractionResult tryRemoveBook(Level,BlockPos,Player,ChiseledBookShelfBlockEntity)
- Optional getRelativeHitCoordinatesForBlockFace(BlockHitResult,Direction)
- void lambda$createBlockStateDefinition$0(StateDefinition$Builder,Property)
+ void lambda$onRemove$0(Level,BlockPos,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.ChiseledBookShelfBlockEntity
</summary>

```diff
+ boolean addBook(ItemStack)
+ boolean hasAnyMatching(Predicate)
+ boolean hasAnyOf(Set)
+ boolean isFull()
+ boolean lambda$countItem$0(Item,ItemStack)
+ boolean lambda$hasAnyOf$1(Set,ItemStack)
- ClientboundBlockEntityDataPacket getUpdatePacket()
- CompoundTag getUpdateTag()
+ int bookCount()
- int count()
+ int countItem(Item)
+ ItemStack removeBook()
+ List removeAllBooksWithoutBlockStateUpdate()
+ NonNullList asNonNullList(StackInventory)
- Packet getUpdatePacket()
+ void setChanged()
+ void updateBlockState()
- void updateState(int)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.SkullBlockEntity
</summary>

```diff
- float getAnimation(float)
+ float getMouthAnimation(float)
- void animation(Level,BlockPos,BlockState,SkullBlockEntity)
+ void dragonHeadAnimation(Level,BlockPos,BlockState,SkullBlockEntity)
```

</details>
<details>
<summary>
net.minecraft.world.level.entity.EntityLookup
</summary>

```diff
- void getEntities(EntityTypeTest,AbortableIterationConsumer)
+ void getEntities(EntityTypeTest,Consumer)
```

</details>
<details>
<summary>
net.minecraft.world.level.entity.EntitySection
</summary>

```diff
- AbortableIterationConsumer$Continuation getEntities(AABB,AbortableIterationConsumer)
- AbortableIterationConsumer$Continuation getEntities(EntityTypeTest,AABB,AbortableIterationConsumer)
+ void getEntities(AABB,Consumer)
+ void getEntities(EntityTypeTest,AABB,Consumer)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
+ net.minecraft.package-info
- XXX.advancements.packs.UpdateOneTwentyVanillaAdvancementProvider
+ XXX.animation.definitions.CamelAnimation
- XXX.animation.definitions.FrogAnimation
- XXX.animation.definitions.package-info
+ XXX.animation.definitions.WardenAnimation
- XXX.atlas.sources.package-info
- XXX.atlas.sources.SingleFile
- XXX.atlas.sources.Unstitcher
- XXX.atlas.sources.Unstitcher$Region
+ XXX.block.model.BakedQuad
- XXX.block.model.BlockElement
+ XXX.block.model.BlockElement$1
- XXX.block.model.BlockElement$Deserializer
+ XXX.block.model.BlockElementFace
- XXX.block.model.BlockElementFace$Deserializer
+ XXX.block.model.BlockElementRotation
- XXX.block.model.BlockFaceUV
+ XXX.block.model.BlockFaceUV$Deserializer
- XXX.block.model.BlockModel
+ XXX.block.model.BlockModel$Deserializer
- XXX.block.model.BlockModel$GuiLight
+ XXX.block.model.BlockModel$LoopException
- XXX.block.model.BlockModelDefinition
+ XXX.block.model.BlockModelDefinition$Context
- XXX.block.model.BlockModelDefinition$Deserializer
+ XXX.block.model.BlockModelDefinition$MissingVariantException
- XXX.block.model.FaceBakery
+ XXX.block.model.FaceBakery$1
- XXX.block.model.ItemModelGenerator
+ XXX.block.model.ItemModelGenerator$1
- XXX.block.model.ItemModelGenerator$Span
+ XXX.block.model.ItemModelGenerator$SpanFacing
- XXX.block.model.ItemOverride
+ XXX.block.model.ItemOverride$Deserializer
- XXX.block.model.ItemOverride$Predicate
+ XXX.block.model.ItemOverrides
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
- XXX.chat.contents.BlockDataSource
+ XXX.chat.contents.DataSource
- XXX.chat.contents.EntityDataSource
+ XXX.chat.contents.KeybindContents
- XXX.chat.contents.KeybindResolver
+ XXX.chat.contents.LiteralContents
- XXX.chat.contents.NbtContents
- XXX.chat.contents.package-info
+ XXX.chat.contents.ScoreContents
- XXX.chat.contents.SelectorContents
+ XXX.chat.contents.StorageDataSource
- XXX.chat.contents.TranslatableContents
+ XXX.chat.contents.TranslatableFormatException
+ XXX.chat.report.AbuseReportSender
- XXX.chat.report.AbuseReportSender$1
+ XXX.chat.report.AbuseReportSender$SendException
- XXX.chat.report.AbuseReportSender$Services
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
- XXX.client.animation.AnimationChannel
+ XXX.client.animation.AnimationChannel$Interpolation
- XXX.client.animation.AnimationChannel$Interpolations
+ XXX.client.animation.AnimationChannel$Target
- XXX.client.animation.AnimationChannel$Targets
+ XXX.client.animation.AnimationDefinition
- XXX.client.animation.AnimationDefinition$Builder
+ XXX.client.animation.Keyframe
- XXX.client.animation.KeyframeAnimations
+ XXX.client.animation.package-info
+ XXX.client.gui.Font
- XXX.client.gui.Font$DisplayMode
+ XXX.client.gui.Font$StringRenderOutput
- XXX.client.gui.Gui
+ XXX.client.gui.Gui$HeartType
- XXX.client.gui.GuiComponent
+ XXX.client.gui.MapRenderer
- XXX.client.gui.MapRenderer$MapInstance
- XXX.client.gui.package-info
+ XXX.client.model.package-info
- XXX.client.model.PiglinModel
+ XXX.client.model.PlayerModel
- XXX.client.model.PolarBearModel
+ XXX.client.model.PufferfishBigModel
- XXX.client.model.PufferfishMidModel
+ XXX.client.model.PufferfishSmallModel
- XXX.client.model.QuadrupedModel
+ XXX.client.model.RabbitModel
- XXX.client.model.RaftModel
+ XXX.client.model.RavagerModel
- XXX.client.model.SalmonModel
+ XXX.client.model.SheepFurModel
- XXX.client.model.SheepModel
+ XXX.client.model.ShieldModel
- XXX.client.model.ShulkerBulletModel
+ XXX.client.model.ShulkerModel
- XXX.client.model.SilverfishModel
+ XXX.client.model.SkeletonModel
- XXX.client.model.SkullModel
+ XXX.client.model.SkullModelBase
- XXX.client.model.SlimeModel
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
- XXX.client.multiplayer.ClientRegistryLayer
+ XXX.client.multiplayer.ClientSuggestionProvider
- XXX.client.multiplayer.ClientSuggestionProvider$1
+ XXX.client.multiplayer.MultiPlayerGameMode
+ XXX.client.multiplayer.package-info
- XXX.client.multiplayer.PlayerInfo
+ XXX.client.multiplayer.ProfileKeyPairManager
- XXX.client.multiplayer.ProfileKeyPairManager$1
+ XXX.client.multiplayer.ServerData
- XXX.client.multiplayer.ServerData$ServerPackStatus
+ XXX.client.multiplayer.ServerList
- XXX.client.multiplayer.ServerStatusPinger
+ XXX.client.multiplayer.ServerStatusPinger$1
- XXX.client.multiplayer.ServerStatusPinger$2
+ XXX.client.multiplayer.ServerStatusPinger$2$1
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
+ XXX.client.particle.ParticleRenderType
- XXX.client.particle.ParticleRenderType$1
+ XXX.client.particle.ParticleRenderType$2
- XXX.client.particle.ParticleRenderType$3
+ XXX.client.particle.ParticleRenderType$4
- XXX.client.particle.ParticleRenderType$5
+ XXX.client.particle.ParticleRenderType$6
- XXX.client.particle.PlayerCloudParticle
+ XXX.client.particle.PlayerCloudParticle$Provider
- XXX.client.particle.PlayerCloudParticle$SneezeProvider
+ XXX.client.particle.PortalParticle
- XXX.client.particle.PortalParticle$Provider
+ XXX.client.particle.ReversePortalParticle
- XXX.client.particle.ReversePortalParticle$ReversePortalProvider
+ XXX.client.particle.RisingParticle
- XXX.client.particle.SculkChargeParticle
+ XXX.client.particle.SculkChargeParticle$Provider
- XXX.client.particle.SculkChargePopParticle
+ XXX.client.particle.SculkChargePopParticle$Provider
- XXX.client.particle.ShriekParticle
+ XXX.client.particle.ShriekParticle$Provider
- XXX.client.particle.SimpleAnimatedParticle
+ XXX.client.particle.SingleQuadParticle
- XXX.client.particle.SmokeParticle
+ XXX.client.particle.SmokeParticle$Provider
- XXX.client.particle.SnowflakeParticle
+ XXX.client.particle.SnowflakeParticle$Provider
- XXX.client.particle.SonicBoomParticle
+ XXX.client.particle.SonicBoomParticle$Provider
- XXX.client.particle.SoulParticle
+ XXX.client.particle.SoulParticle$EmissiveProvider
- XXX.client.particle.SoulParticle$Provider
+ XXX.client.particle.SpellParticle
- XXX.client.particle.SpellParticle$AmbientMobProvider
+ XXX.client.particle.SpellParticle$InstantProvider
- XXX.client.particle.SpellParticle$MobProvider
+ XXX.client.particle.SpellParticle$Provider
- XXX.client.particle.SpellParticle$WitchProvider
+ XXX.client.particle.SpitParticle
- XXX.client.particle.SpitParticle$Provider
+ XXX.client.particle.SplashParticle
- XXX.client.particle.SplashParticle$Provider
+ XXX.client.particle.SpriteSet
- XXX.client.particle.SquidInkParticle
+ XXX.client.particle.SquidInkParticle$GlowInkProvider
- XXX.client.particle.SquidInkParticle$Provider
+ XXX.client.particle.SuspendedParticle
- XXX.client.particle.SuspendedParticle$CrimsonSporeProvider
+ XXX.client.particle.SuspendedParticle$SporeBlossomAirProvider
- XXX.client.particle.SuspendedParticle$SporeBlossomAirProvider$1
+ XXX.client.particle.SuspendedParticle$UnderwaterProvider
- XXX.client.particle.SuspendedParticle$WarpedSporeProvider
+ XXX.client.particle.SuspendedTownParticle
- XXX.client.particle.SuspendedTownParticle$ComposterFillProvider
+ XXX.client.particle.SuspendedTownParticle$DolphinSpeedProvider
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
+ XXX.client.renderer.BiomeColors
- XXX.client.renderer.BlockEntityWithoutLevelRenderer
+ XXX.client.renderer.ChunkBufferBuilderPack
- XXX.client.renderer.CubeMap
+ XXX.client.renderer.DimensionSpecialEffects
- XXX.client.renderer.DimensionSpecialEffects$EndEffects
+ XXX.client.renderer.DimensionSpecialEffects$NetherEffects
- XXX.client.renderer.DimensionSpecialEffects$OverworldEffects
+ XXX.client.renderer.DimensionSpecialEffects$SkyType
- XXX.client.renderer.EffectInstance
+ XXX.client.renderer.FaceInfo
- XXX.client.renderer.FaceInfo$Constants
+ XXX.client.renderer.FaceInfo$VertexInfo
- XXX.client.renderer.FogRenderer
+ XXX.client.renderer.FogRenderer$BlindnessFogFunction
- XXX.client.renderer.FogRenderer$DarknessFogFunction
+ XXX.client.renderer.FogRenderer$FogData
- XXX.client.renderer.FogRenderer$FogMode
+ XXX.client.renderer.FogRenderer$MobEffectFogFunction
- XXX.client.renderer.GameRenderer
+ XXX.client.renderer.GameRenderer$1
- XXX.client.renderer.GameRenderer$ResourceCache
+ XXX.client.renderer.GpuWarnlistManager
- XXX.client.renderer.GpuWarnlistManager$Preparations
+ XXX.client.renderer.ItemBlockRenderTypes
- XXX.client.renderer.ItemInHandRenderer
+ XXX.client.renderer.ItemInHandRenderer$1
- XXX.client.renderer.ItemInHandRenderer$HandRenderSelection
+ XXX.client.renderer.ItemModelShaper
- XXX.client.renderer.LevelRenderer
+ XXX.client.renderer.LevelRenderer$RenderChunkInfo
- XXX.client.renderer.LevelRenderer$RenderChunkStorage
+ XXX.client.renderer.LevelRenderer$RenderInfoMap
- XXX.client.renderer.LevelRenderer$TransparencyShaderException
+ XXX.client.renderer.LightTexture
- XXX.client.renderer.MultiBufferSource
+ XXX.client.renderer.MultiBufferSource$BufferSource
- XXX.client.renderer.OutlineBufferSource
+ XXX.client.renderer.OutlineBufferSource$EntityOutlineGenerator
+ XXX.client.renderer.package-info
- XXX.client.renderer.PanoramaRenderer
+ XXX.client.renderer.PostChain
- XXX.client.renderer.PostPass
+ XXX.client.renderer.Rect2i
- XXX.client.renderer.RenderBuffers
+ XXX.client.renderer.RenderStateShard
- XXX.client.renderer.RenderStateShard$BooleanStateShard
+ XXX.client.renderer.RenderStateShard$CullStateShard
- XXX.client.renderer.RenderStateShard$DepthTestStateShard
+ XXX.client.renderer.RenderStateShard$EmptyTextureStateShard
- XXX.client.renderer.RenderStateShard$LayeringStateShard
+ XXX.client.renderer.RenderStateShard$LightmapStateShard
- XXX.client.renderer.RenderStateShard$LineStateShard
+ XXX.client.renderer.RenderStateShard$MultiTextureStateShard
- XXX.client.renderer.RenderStateShard$MultiTextureStateShard$Builder
+ XXX.client.renderer.RenderStateShard$OffsetTexturingStateShard
- XXX.client.renderer.RenderStateShard$OutputStateShard
+ XXX.client.renderer.RenderStateShard$OverlayStateShard
- XXX.client.renderer.RenderStateShard$ShaderStateShard
+ XXX.client.renderer.RenderStateShard$TextureStateShard
- XXX.client.renderer.RenderStateShard$TexturingStateShard
+ XXX.client.renderer.RenderStateShard$TransparencyStateShard
- XXX.client.renderer.RenderStateShard$WriteMaskStateShard
+ XXX.client.renderer.RenderType
- XXX.client.renderer.RenderType$CompositeRenderType
+ XXX.client.renderer.RenderType$CompositeState
- XXX.client.renderer.RenderType$CompositeState$CompositeStateBuilder
+ XXX.client.renderer.RenderType$OutlineProperty
- XXX.client.renderer.RunningTrimmedMean
+ XXX.client.renderer.ScreenEffectRenderer
- XXX.client.renderer.ShaderInstance
+ XXX.client.renderer.ShaderInstance$1
- XXX.client.renderer.Sheets
+ XXX.client.renderer.Sheets$1
- XXX.client.renderer.SpriteCoordinateExpander
+ XXX.client.renderer.ViewArea
- XXX.client.renderer.VirtualScreen
- XXX.client.resources.ClientPackSource
+ XXX.client.resources.DefaultPlayerSkin
- XXX.client.resources.DefaultPlayerSkin$ModelType
+ XXX.client.resources.DefaultPlayerSkin$SkinType
- XXX.client.resources.DownloadedPackSource
+ XXX.client.resources.FoliageColorReloadListener
- XXX.client.resources.GrassColorReloadListener
+ XXX.client.resources.IndexedAssetSource
- XXX.client.resources.LegacyStuffWrapper
+ XXX.client.resources.MobEffectTextureManager
- XXX.client.resources.PaintingTextureManager
+ XXX.client.resources.SkinManager
- XXX.client.resources.SkinManager$1
+ XXX.client.resources.SkinManager$2
- XXX.client.resources.SkinManager$SkinTextureCallback
+ XXX.client.resources.SplashManager
- XXX.client.resources.TextureAtlasHolder
- XXX.client.telemetry.ClientTelemetryManager
- XXX.client.telemetry.TelemetryEventLog
- XXX.client.telemetry.TelemetryEventSender
- XXX.client.telemetry.TelemetryEventType$Builder
- XXX.client.telemetry.TelemetryProperty
- XXX.client.telemetry.TelemetryProperty$GameMode
- XXX.client.telemetry.TelemetryPropertyMap
- XXX.client.telemetry.TelemetryPropertyMap$Builder
- XXX.color.block.BlockColor
+ XXX.color.block.BlockColors
- XXX.color.block.BlockTintCache
+ XXX.color.block.BlockTintCache$CacheData
- XXX.color.block.BlockTintCache$LatestCacheInfo
+ XXX.color.block.package-info
- XXX.color.item.ItemColor
+ XXX.color.item.ItemColors
- XXX.color.item.package-info
- XXX.components.events.AbstractContainerEventHandler
+ XXX.components.events.ContainerEventHandler
- XXX.components.events.GuiEventListener
+ XXX.components.events.package-info
- XXX.components.spectator.package-info
+ XXX.components.spectator.SpectatorGui
+ XXX.components.toasts.AdvancementToast
+ XXX.components.toasts.package-info
- XXX.components.toasts.RecipeToast
+ XXX.components.toasts.SystemToast
- XXX.components.toasts.SystemToast$SystemToastIds
+ XXX.components.toasts.Toast
- XXX.components.toasts.Toast$Visibility
+ XXX.components.toasts.ToastComponent
- XXX.components.toasts.ToastComponent$ToastInstance
+ XXX.components.toasts.TutorialToast
- XXX.components.toasts.TutorialToast$Icons
- XXX.data.models.BlockModelGenerators$BookSlotModelCacheKey
+ XXX.data.models.BlockModelGenerators$TintState
- XXX.data.models.BlockModelGenerators$WoodProvider
+ XXX.data.models.ItemModelGenerators
- XXX.data.models.ModelProvider
+ XXX.data.models.package-info
+ XXX.data.recipes.CraftingRecipeBuilder
- XXX.data.recipes.CraftingRecipeBuilder$1
+ XXX.data.recipes.CraftingRecipeBuilder$CraftingResult
- XXX.data.recipes.FinishedRecipe
- XXX.data.recipes.package-info
+ XXX.data.recipes.RecipeBuilder
- XXX.data.recipes.RecipeCategory
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
- XXX.data.recipes.UpgradeRecipeBuilder
+ XXX.data.recipes.UpgradeRecipeBuilder$Result
+ XXX.data.registries.package-info
+ XXX.data.registries.RegistriesDatapackGenerator
- XXX.data.registries.VanillaRegistries
- XXX.data.structures.NbtToSnbt
- XXX.data.structures.package-info
+ XXX.data.structures.SnbtToNbt
- XXX.data.structures.SnbtToNbt$Filter
+ XXX.data.structures.SnbtToNbt$StructureConversionException
- XXX.data.structures.SnbtToNbt$TaskResult
+ XXX.data.structures.StructureUpdater
+ XXX.data.tags.BannerPatternTagsProvider
- XXX.data.tags.BiomeTagsProvider
+ XXX.data.tags.CatVariantTagsProvider
- XXX.data.tags.EntityTypeTagsProvider
+ XXX.data.tags.FlatLevelGeneratorPresetTagsProvider
- XXX.data.tags.FluidTagsProvider
+ XXX.data.tags.GameEventTagsProvider
- XXX.data.tags.InstrumentTagsProvider
+ XXX.data.tags.IntrinsicHolderTagsProvider
- XXX.data.tags.IntrinsicHolderTagsProvider$IntrinsicTagAppender
+ XXX.data.tags.ItemTagsProvider
- XXX.data.tags.package-info
- XXX.data.tags.PaintingVariantTagsProvider
+ XXX.data.tags.PoiTypeTagsProvider
- XXX.data.tags.StructureTagsProvider
+ XXX.data.tags.TagsProvider
- XXX.data.tags.TagsProvider$TagAppender
+ XXX.data.tags.UpdateOneTwentyBlockTagsProvider
- XXX.data.tags.UpdateOneTwentyItemTagsProvider
+ XXX.data.tags.VanillaBlockTagsProvider
- XXX.data.tags.VanillaItemTagsProvider
+ XXX.data.tags.WorldPresetTagsProvider
+ XXX.data.worldgen.AncientCityStructurePieces
- XXX.data.worldgen.AncientCityStructurePools
+ XXX.data.worldgen.BastionBridgePools
- XXX.data.worldgen.BastionHoglinStablePools
+ XXX.data.worldgen.BastionHousingUnitsPools
- XXX.data.worldgen.BastionPieces
+ XXX.data.worldgen.BastionSharedPools
- XXX.data.worldgen.BastionTreasureRoomPools
+ XXX.data.worldgen.BiomeDefaultFeatures
- XXX.data.worldgen.BootstapContext
+ XXX.data.worldgen.Carvers
- XXX.data.worldgen.DesertVillagePools
+ XXX.data.worldgen.DimensionTypes
- XXX.data.worldgen.NoiseData
+ XXX.data.worldgen.package-info
+ XXX.data.worldgen.PillagerOutpostPools
- XXX.data.worldgen.PlainVillagePools
+ XXX.data.worldgen.Pools
- XXX.data.worldgen.ProcessorLists
+ XXX.data.worldgen.SavannaVillagePools
- XXX.data.worldgen.SnowyVillagePools
- XXX.data.worldgen.Structures
+ XXX.data.worldgen.StructureSets
+ XXX.data.worldgen.SurfaceRuleData
- XXX.data.worldgen.TaigaVillagePools
+ XXX.data.worldgen.TerrainProvider
- XXX.data.worldgen.VillagePools
- XXX.datafix.fixes.AbstractArrowPickupFix
+ XXX.datafix.fixes.AbstractPoiSectionFix
- XXX.datafix.fixes.AbstractUUIDFix
+ XXX.datafix.fixes.AddFlagIfNotPresentFix
- XXX.datafix.fixes.AddNewChoices
+ XXX.datafix.fixes.AdvancementsFix
- XXX.datafix.fixes.AdvancementsRenameFix
+ XXX.datafix.fixes.AttributesRename
- XXX.datafix.fixes.BedItemColorFix
+ XXX.datafix.fixes.BiomeFix
- XXX.datafix.fixes.BitStorageAlignFix
+ XXX.datafix.fixes.BlendingDataFix
- XXX.datafix.fixes.BlendingDataRemoveFromNetherEndFix
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
- XXX.datafix.fixes.CavesAndCliffsRenames
+ XXX.datafix.fixes.ChunkBedBlockEntityInjecterFix
- XXX.datafix.fixes.ChunkBiomeFix
+ XXX.datafix.fixes.ChunkDeleteIgnoredLightDataFix
- XXX.datafix.fixes.ChunkHeightAndBiomeFix
+ XXX.datafix.fixes.ChunkLightRemoveFix
- XXX.datafix.fixes.ChunkPalettedStorageFix
+ XXX.datafix.fixes.ChunkPalettedStorageFix$1
- XXX.datafix.fixes.ChunkPalettedStorageFix$DataLayer
+ XXX.datafix.fixes.ChunkPalettedStorageFix$Direction
- XXX.datafix.fixes.ChunkPalettedStorageFix$Direction$Axis
+ XXX.datafix.fixes.ChunkPalettedStorageFix$Direction$AxisDirection
- XXX.datafix.fixes.ChunkPalettedStorageFix$Section
+ XXX.datafix.fixes.ChunkPalettedStorageFix$UpgradeChunk
- XXX.datafix.fixes.ChunkProtoTickListFix
+ XXX.datafix.fixes.ChunkProtoTickListFix$PoorMansPalettedContainer
- XXX.datafix.fixes.ChunkRenamesFix
+ XXX.datafix.fixes.ChunkStatusFix
- XXX.datafix.fixes.ChunkStatusFix2
+ XXX.datafix.fixes.ChunkStructuresTemplateRenameFix
- XXX.datafix.fixes.ChunkToProtochunkFix
+ XXX.datafix.fixes.ColorlessShulkerEntityFix
- XXX.datafix.fixes.CriteriaRenameFix
+ XXX.datafix.fixes.DyeItemRenameFix
- XXX.datafix.fixes.EntityArmorStandSilentFix
+ XXX.datafix.fixes.EntityBlockStateFix
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
+ XXX.datafix.fixes.FilteredBooksFix
- XXX.datafix.fixes.FilteredSignsFix
+ XXX.datafix.fixes.ForcePoiRebuild
- XXX.datafix.fixes.FurnaceRecipeFix
+ XXX.datafix.fixes.GoatHornIdFix
- XXX.datafix.fixes.GossipUUIDFix
+ XXX.datafix.fixes.HeightmapRenamingFix
- XXX.datafix.fixes.IglooMetadataRemovalFix
+ XXX.datafix.fixes.ItemBannerColorFix
- XXX.datafix.fixes.ItemCustomNameToComponentFix
+ XXX.datafix.fixes.ItemIdFix
- XXX.datafix.fixes.ItemLoreFix
+ XXX.datafix.fixes.ItemPotionFix
- XXX.datafix.fixes.ItemRemoveBlockEntityTagFix
+ XXX.datafix.fixes.ItemRenameFix
- XXX.datafix.fixes.ItemRenameFix$1
+ XXX.datafix.fixes.ItemShulkerBoxColorFix
- XXX.datafix.fixes.ItemSpawnEggFix
+ XXX.datafix.fixes.ItemStackEnchantmentNamesFix
- XXX.datafix.fixes.ItemStackMapIdFix
+ XXX.datafix.fixes.ItemStackSpawnEggFix
- XXX.datafix.fixes.ItemStackTagFix
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
- XXX.datafix.fixes.OptionsProgrammerArtFix
+ XXX.datafix.fixes.OptionsRenameFieldFix
- XXX.datafix.fixes.OverreachingTickFix
- XXX.datafix.fixes.package-info
+ XXX.datafix.fixes.PlayerUUIDFix
- XXX.datafix.fixes.PoiTypeRemoveFix
+ XXX.datafix.fixes.PoiTypeRenameFix
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
- XXX.datafix.fixes.SimpleRenameFix
+ XXX.datafix.fixes.SimplestEntityRenameFix
- XXX.datafix.fixes.SpawnerDataFix
+ XXX.datafix.fixes.StatsCounterFix
- XXX.datafix.fixes.StatsRenameFix
+ XXX.datafix.fixes.StriderGravityFix
- XXX.datafix.fixes.StructureReferenceCountFix
- XXX.datafix.fixes.StructuresBecomeConfiguredFix
+ XXX.datafix.fixes.StructuresBecomeConfiguredFix$Conversion
+ XXX.datafix.fixes.StructureSettingsFlattenFix
- XXX.datafix.fixes.TeamDisplayNameFix
+ XXX.datafix.fixes.TrappedChestBlockEntityFix
- XXX.datafix.fixes.TrappedChestBlockEntityFix$TrappedChestSection
+ XXX.datafix.fixes.VariantRenameFix
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
- XXX.datafix.schemas.package-info
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
+ XXX.datafix.schemas.V3202
- XXX.datafix.schemas.V3203
+ XXX.datafix.schemas.V3204
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
+ XXX.entity.layers.package-info
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
+ XXX.entity.layers.WardenEmissiveLayer$DrawSelector
- XXX.entity.layers.WitchItemLayer
+ XXX.entity.layers.WitherArmorLayer
- XXX.entity.layers.WolfCollarLayer
- XXX.entity.player.package-info
+ XXX.entity.player.PlayerRenderer
- XXX.font.glyphs.BakedGlyph
+ XXX.font.glyphs.BakedGlyph$1
- XXX.font.glyphs.BakedGlyph$Effect
+ XXX.font.glyphs.EmptyGlyph
+ XXX.font.glyphs.package-info
- XXX.font.glyphs.SpecialGlyphs
+ XXX.font.glyphs.SpecialGlyphs$1
- XXX.font.glyphs.SpecialGlyphs$PixelProvider
+ XXX.font.providers.BitmapProvider
- XXX.font.providers.BitmapProvider$Builder
+ XXX.font.providers.BitmapProvider$Glyph
- XXX.font.providers.BitmapProvider$Glyph$1
+ XXX.font.providers.GlyphProviderBuilder
- XXX.font.providers.GlyphProviderBuilderType
+ XXX.font.providers.LegacyUnicodeBitmapsProvider
- XXX.font.providers.LegacyUnicodeBitmapsProvider$Builder
+ XXX.font.providers.LegacyUnicodeBitmapsProvider$Glyph
- XXX.font.providers.LegacyUnicodeBitmapsProvider$Glyph$1
+ XXX.font.providers.LegacyUnicodeBitmapsProvider$Sheet
+ XXX.font.providers.package-info
- XXX.font.providers.TrueTypeGlyphProviderBuilder
+ XXX.gametest.framework.AfterBatch
- XXX.gametest.framework.BeforeBatch
+ XXX.gametest.framework.ExhaustedAttemptsException
- XXX.gametest.framework.GameTest
+ XXX.gametest.framework.GameTestAssertException
- XXX.gametest.framework.GameTestAssertPosException
+ XXX.gametest.framework.GameTestBatch
- XXX.gametest.framework.GameTestBatchRunner
+ XXX.gametest.framework.GameTestBatchRunner$1
- XXX.gametest.framework.GameTestEvent
+ XXX.gametest.framework.GameTestGenerator
- XXX.gametest.framework.GameTestHelper
+ XXX.gametest.framework.GameTestHelper$1
- XXX.gametest.framework.GameTestHelper$2
+ XXX.gametest.framework.GameTestInfo
- XXX.gametest.framework.GameTestListener
+ XXX.gametest.framework.GameTestRegistry
- XXX.gametest.framework.GameTestRunner
+ XXX.gametest.framework.GameTestSequence
- XXX.gametest.framework.GameTestSequence$Condition
+ XXX.gametest.framework.GameTestServer
- XXX.gametest.framework.GameTestServer$1
+ XXX.gametest.framework.GameTestTicker
- XXX.gametest.framework.GameTestTimeoutException
+ XXX.gametest.framework.GlobalTestReporter
- XXX.gametest.framework.JUnitLikeTestReporter
+ XXX.gametest.framework.LogTestReporter
- XXX.gametest.framework.MultipleTestTracker
+ XXX.gametest.framework.MultipleTestTracker$1
- XXX.gametest.framework.package-info
- XXX.gametest.framework.ReportGameListener
+ XXX.gametest.framework.StructureUtils
- XXX.gametest.framework.StructureUtils$1
+ XXX.gametest.framework.TeamcityTestReporter
- XXX.gametest.framework.TestClassNameArgument
+ XXX.gametest.framework.TestCommand
- XXX.gametest.framework.TestCommand$TestSummaryDisplayer
+ XXX.gametest.framework.TestFunction
- XXX.gametest.framework.TestFunctionArgument
+ XXX.gametest.framework.TestReporter
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
- XXX.gui.components.AbstractContainerWidget
+ XXX.gui.components.AbstractContainerWidget$AbstractChildWrapper
- XXX.gui.components.AbstractOptionSliderButton
+ XXX.gui.components.AbstractScrollWidget
- XXX.gui.components.AbstractSelectionList
+ XXX.gui.components.AbstractSelectionList$Entry
- XXX.gui.components.AbstractSelectionList$SelectionDirection
+ XXX.gui.components.AbstractSelectionList$TrackedList
- XXX.gui.components.AbstractSliderButton
+ XXX.gui.components.AbstractWidget
- XXX.gui.components.BossHealthOverlay
+ XXX.gui.components.BossHealthOverlay$1
- XXX.gui.components.Button
+ XXX.gui.components.Button$Builder
- XXX.gui.components.Button$CreateNarration
+ XXX.gui.components.Button$OnPress
- XXX.gui.components.CenteredStringWidget
+ XXX.gui.components.ChatComponent
- XXX.gui.components.ChatComponent$DelayedMessageDeletion
+ XXX.gui.components.Checkbox
- XXX.gui.components.CommandSuggestions
+ XXX.gui.components.CommandSuggestions$SuggestionsList
- XXX.gui.components.ComponentRenderUtils
+ XXX.gui.components.ContainerObjectSelectionList
- XXX.gui.components.ContainerObjectSelectionList$Entry
+ XXX.gui.components.CycleButton
- XXX.gui.components.CycleButton$Builder
+ XXX.gui.components.CycleButton$OnValueChange
- XXX.gui.components.CycleButton$ValueListSupplier
+ XXX.gui.components.CycleButton$ValueListSupplier$1
- XXX.gui.components.CycleButton$ValueListSupplier$2
+ XXX.gui.components.DebugScreenOverlay
- XXX.gui.components.DebugScreenOverlay$1
+ XXX.gui.components.DebugScreenOverlay$AllocationRateCalculator
- XXX.gui.components.EditBox
+ XXX.gui.components.FrameWidget
- XXX.gui.components.FrameWidget$ChildContainer
+ XXX.gui.components.GridWidget
- XXX.gui.components.GridWidget$CellInhabitant
- XXX.gui.components.MultilineTextField
+ XXX.gui.components.MultilineTextField$1
- XXX.gui.components.MultilineTextField$StringView
+ XXX.gui.components.ObjectSelectionList
- XXX.gui.components.ObjectSelectionList$Entry
+ XXX.gui.components.OptionsList
- XXX.gui.components.OptionsList$Entry
- XXX.gui.components.package-info
+ XXX.gui.components.PlainTextButton
- XXX.gui.components.PlayerFaceRenderer
+ XXX.gui.components.PlayerTabOverlay
- XXX.gui.components.PlayerTabOverlay$HealthState
+ XXX.gui.components.Renderable
- XXX.gui.components.SpacerWidget
+ XXX.gui.components.StateSwitchingButton
- XXX.gui.components.SubtitleOverlay
+ XXX.gui.components.SubtitleOverlay$Subtitle
- XXX.gui.components.Tooltip
+ XXX.gui.components.Whence
- XXX.gui.font.AllMissingGlyphProvider
+ XXX.gui.font.FontManager
- XXX.gui.font.FontManager$1
+ XXX.gui.font.FontSet
- XXX.gui.font.FontSet$GlyphInfoFilter
+ XXX.gui.font.FontTexture
- XXX.gui.font.FontTexture$Node
- XXX.gui.font.package-info
+ XXX.gui.font.TextFieldHelper
- XXX.gui.font.TextFieldHelper$1
+ XXX.gui.font.TextFieldHelper$CursorStep
- XXX.gui.narration.NarratableEntry
+ XXX.gui.narration.NarratableEntry$NarrationPriority
- XXX.gui.narration.NarratedElementType
+ XXX.gui.narration.NarrationElementOutput
- XXX.gui.narration.NarrationSupplier
+ XXX.gui.narration.NarrationThunk
+ XXX.gui.narration.package-info
- XXX.gui.narration.ScreenNarrationCollector
+ XXX.gui.narration.ScreenNarrationCollector$1
- XXX.gui.narration.ScreenNarrationCollector$EntryKey
+ XXX.gui.narration.ScreenNarrationCollector$NarrationEntry
- XXX.gui.narration.ScreenNarrationCollector$Output
+ XXX.gui.screens.AccessibilityOptionsScreen
- XXX.gui.screens.AlertScreen
+ XXX.gui.screens.BackupConfirmScreen
- XXX.gui.screens.BackupConfirmScreen$Listener
+ XXX.gui.screens.BanNoticeScreen
- XXX.gui.screens.ChatOptionsScreen
+ XXX.gui.screens.ChatScreen
- XXX.gui.screens.ChatScreen$1
+ XXX.gui.screens.ConfirmLinkScreen
- XXX.gui.screens.ConfirmScreen
+ XXX.gui.screens.ConnectScreen
- XXX.gui.screens.ConnectScreen$1
+ XXX.gui.screens.CreateBuffetWorldScreen
- XXX.gui.screens.CreateBuffetWorldScreen$BiomeList
+ XXX.gui.screens.CreateBuffetWorldScreen$BiomeList$Entry
- XXX.gui.screens.CreateFlatWorldScreen
+ XXX.gui.screens.CreateFlatWorldScreen$DetailsList
- XXX.gui.screens.CreateFlatWorldScreen$DetailsList$Entry
+ XXX.gui.screens.DatapackLoadFailureScreen
- XXX.gui.screens.DeathScreen
+ XXX.gui.screens.DemoIntroScreen
- XXX.gui.screens.DirectJoinServerScreen
+ XXX.gui.screens.DisconnectedScreen
- XXX.gui.screens.EditServerScreen
+ XXX.gui.screens.ErrorScreen
- XXX.gui.screens.GenericDirtMessageScreen
+ XXX.gui.screens.GenericWaitingScreen
- XXX.gui.screens.InBedChatScreen
+ XXX.gui.screens.LanguageSelectScreen
- XXX.gui.screens.LanguageSelectScreen$LanguageSelectionList
+ XXX.gui.screens.LanguageSelectScreen$LanguageSelectionList$Entry
- XXX.gui.screens.LevelLoadingScreen
+ XXX.gui.screens.LoadingDotsText
- XXX.gui.screens.LoadingOverlay
+ XXX.gui.screens.LoadingOverlay$LogoTexture
- XXX.gui.screens.MenuScreens
+ XXX.gui.screens.MenuScreens$ScreenConstructor
- XXX.gui.screens.MouseSettingsScreen
+ XXX.gui.screens.OnlineOptionsScreen
- XXX.gui.screens.OptionsScreen
+ XXX.gui.screens.OptionsSubScreen
- XXX.gui.screens.OutOfMemoryScreen
+ XXX.gui.screens.Overlay
- XXX.gui.screens.package-info
- XXX.gui.screens.PauseScreen
+ XXX.gui.screens.PopupScreen
- XXX.gui.screens.PopupScreen$ButtonOption
+ XXX.gui.screens.PresetFlatWorldScreen
- XXX.gui.screens.PresetFlatWorldScreen$PresetsList
+ XXX.gui.screens.PresetFlatWorldScreen$PresetsList$Entry
- XXX.gui.screens.ProgressScreen
+ XXX.gui.screens.ReceivingLevelScreen
- XXX.gui.screens.Screen
+ XXX.gui.screens.Screen$NarratableSearchResult
- XXX.gui.screens.ShareToLanScreen
+ XXX.gui.screens.SimpleOptionsSubScreen
- XXX.gui.screens.SkinCustomizationScreen
+ XXX.gui.screens.SoundOptionsScreen
- XXX.gui.screens.TitleScreen
+ XXX.gui.screens.TitleScreen$WarningLabel
- XXX.gui.screens.VideoSettingsScreen
+ XXX.gui.screens.WinScreen
- XXX.gui.screens.WinScreen$CreditsReader
+ XXX.inventory.tooltip.ClientBundleTooltip
- XXX.inventory.tooltip.ClientBundleTooltip$Texture
+ XXX.inventory.tooltip.ClientTextTooltip
- XXX.inventory.tooltip.ClientTooltipComponent
+ XXX.inventory.tooltip.package-info
+ XXX.level.block.BambooBlock
- XXX.level.block.BambooSaplingBlock
- XXX.level.block.ChorusFlowerBlock
+ XXX.level.block.ChorusPlantBlock
- XXX.level.block.CocoaBlock
+ XXX.level.block.CocoaBlock$1
- XXX.level.block.CommandBlock
+ XXX.level.block.ComparatorBlock
- XXX.level.block.ComposterBlock
+ XXX.level.block.ComposterBlock$EmptyContainer
- XXX.level.block.ComposterBlock$InputContainer
+ XXX.level.block.ComposterBlock$OutputContainer
- XXX.level.block.ConcretePowderBlock
+ XXX.level.block.ConduitBlock
- XXX.level.block.CoralBlock
+ XXX.level.block.CoralFanBlock
- XXX.level.block.CoralPlantBlock
+ XXX.level.block.CoralWallFanBlock
- XXX.level.block.CraftingTableBlock
+ XXX.level.block.CropBlock
- XXX.level.block.CrossCollisionBlock
+ XXX.level.block.CrossCollisionBlock$1
- XXX.level.block.CryingObsidianBlock
+ XXX.level.block.DaylightDetectorBlock
- XXX.level.block.DeadBushBlock
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
- XXX.level.block.FarmBlock
+ XXX.level.block.FenceBlock
- XXX.level.block.FenceGateBlock
+ XXX.level.block.FenceGateBlock$1
- XXX.level.block.FireBlock
+ XXX.level.block.FletchingTableBlock
- XXX.level.block.FlowerBlock
+ XXX.level.block.FlowerPotBlock
- XXX.level.block.FrogspawnBlock
+ XXX.level.block.FrostedIceBlock
- XXX.level.block.FungusBlock
+ XXX.level.block.FurnaceBlock
- XXX.level.block.GameMasterBlock
+ XXX.level.block.GlassBlock
- XXX.level.block.GlazedTerracottaBlock
+ XXX.level.block.GlowLichenBlock
- XXX.level.block.GrassBlock
+ XXX.level.block.GravelBlock
- XXX.level.block.GrindstoneBlock
+ XXX.level.block.GrindstoneBlock$1
- XXX.level.block.GrowingPlantBlock
+ XXX.level.block.GrowingPlantBodyBlock
- XXX.level.block.GrowingPlantHeadBlock
+ XXX.level.block.HalfTransparentBlock
- XXX.level.block.HangingRootsBlock
+ XXX.level.block.HayBlock
- XXX.level.block.HoneyBlock
+ XXX.level.block.HopperBlock
- XXX.level.block.HopperBlock$1
+ XXX.level.block.HorizontalDirectionalBlock
- XXX.level.block.HugeMushroomBlock
+ XXX.level.block.IceBlock
- XXX.level.block.InfestedBlock
+ XXX.level.block.InfestedRotatedPillarBlock
- XXX.level.block.IronBarsBlock
+ XXX.level.block.JigsawBlock
- XXX.level.block.JukeboxBlock
+ XXX.level.block.KelpBlock
- XXX.level.block.KelpPlantBlock
+ XXX.level.block.LadderBlock
- XXX.level.block.LadderBlock$1
+ XXX.level.block.LanternBlock
- XXX.level.block.LavaCauldronBlock
+ XXX.level.block.LayeredCauldronBlock
- XXX.level.block.LeavesBlock
+ XXX.level.block.LecternBlock
- XXX.level.block.LecternBlock$1
+ XXX.level.block.LevelEvent
- XXX.level.block.LeverBlock
+ XXX.level.block.LeverBlock$1
- XXX.level.block.LightBlock
+ XXX.level.block.LightningRodBlock
- XXX.level.block.LiquidBlock
+ XXX.level.block.LiquidBlockContainer
- XXX.level.block.LoomBlock
+ XXX.level.block.MagmaBlock
- XXX.level.block.MangroveLeavesBlock
+ XXX.level.block.MangrovePropaguleBlock
- XXX.level.block.MangroveRootsBlock
+ XXX.level.block.MelonBlock
- XXX.level.block.Mirror
+ XXX.level.block.Mirror$1
- XXX.level.block.MossBlock
+ XXX.level.block.MudBlock
- XXX.level.block.MultifaceBlock
+ XXX.level.block.MultifaceSpreader
- XXX.level.block.MultifaceSpreader$DefaultSpreaderConfig
+ XXX.level.block.MultifaceSpreader$SpreadConfig
- XXX.level.block.MultifaceSpreader$SpreadPos
+ XXX.level.block.MultifaceSpreader$SpreadPredicate
- XXX.level.block.MultifaceSpreader$SpreadType
+ XXX.level.block.MultifaceSpreader$SpreadType$1
- XXX.level.block.MultifaceSpreader$SpreadType$2
+ XXX.level.block.MultifaceSpreader$SpreadType$3
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
+ XXX.metadata.animation.AnimationFrame
- XXX.metadata.animation.AnimationMetadataSection
+ XXX.metadata.animation.AnimationMetadataSection$1
- XXX.metadata.animation.AnimationMetadataSection$FrameOutput
+ XXX.metadata.animation.AnimationMetadataSectionSerializer
- XXX.metadata.animation.FrameSize
- XXX.metadata.animation.package-info
+ XXX.metadata.animation.VillagerMetaDataSection
- XXX.metadata.animation.VillagerMetaDataSection$Hat
+ XXX.metadata.animation.VillagerMetadataSectionSerializer
+ XXX.metadata.language.LanguageMetadataSection
- XXX.metadata.language.LanguageMetadataSectionSerializer
+ XXX.metadata.language.package-info
+ XXX.metadata.texture.package-info
+ XXX.metadata.texture.TextureMetadataSection
- XXX.metadata.texture.TextureMetadataSectionSerializer
+ XXX.minecraft.client.ClientTelemetryManager$1
+ XXX.minecraft.client.CloudStatus
- XXX.minecraft.client.ComponentCollector
+ XXX.minecraft.client.DebugQueryHandler
- XXX.minecraft.client.Game
+ XXX.minecraft.client.Game$Metrics
- XXX.minecraft.client.GameNarrator
+ XXX.minecraft.client.GraphicsStatus
- XXX.minecraft.client.GraphicsStatus$1
+ XXX.minecraft.client.GuiMessage
- XXX.minecraft.client.GuiMessage$Line
+ XXX.minecraft.client.GuiMessageTag
- XXX.minecraft.client.GuiMessageTag$Icon
+ XXX.minecraft.client.HotbarManager
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
+ XXX.minecraft.client.Session
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
- XXX.minecraft.data.package-info
+ XXX.minecraft.locale.Language
- XXX.minecraft.locale.Language$1
+ XXX.minecraft.locale.package-info
- XXX.minecraft.nbt.ByteArrayTag
+ XXX.minecraft.nbt.ByteArrayTag$1
- XXX.minecraft.nbt.ByteTag
+ XXX.minecraft.nbt.ByteTag$1
- XXX.minecraft.nbt.ByteTag$Cache
+ XXX.minecraft.nbt.CollectionTag
- XXX.minecraft.nbt.CompoundTag
+ XXX.minecraft.nbt.CompoundTag$1
- XXX.minecraft.nbt.CompoundTag$2
+ XXX.minecraft.nbt.DoubleTag
- XXX.minecraft.nbt.DoubleTag$1
+ XXX.minecraft.nbt.EndTag
- XXX.minecraft.nbt.EndTag$1
+ XXX.minecraft.nbt.FloatTag
- XXX.minecraft.nbt.FloatTag$1
+ XXX.minecraft.nbt.IntArrayTag
- XXX.minecraft.nbt.IntArrayTag$1
+ XXX.minecraft.nbt.IntTag
- XXX.minecraft.nbt.IntTag$1
+ XXX.minecraft.nbt.IntTag$Cache
- XXX.minecraft.nbt.ListTag
+ XXX.minecraft.nbt.ListTag$1
- XXX.minecraft.nbt.ListTag$2
+ XXX.minecraft.nbt.LongArrayTag
- XXX.minecraft.nbt.LongArrayTag$1
+ XXX.minecraft.nbt.LongTag
- XXX.minecraft.nbt.LongTag$1
+ XXX.minecraft.nbt.LongTag$Cache
- XXX.minecraft.nbt.NbtAccounter
+ XXX.minecraft.nbt.NbtAccounter$1
- XXX.minecraft.nbt.NbtIo
+ XXX.minecraft.nbt.NbtIo$1
- XXX.minecraft.nbt.NbtOps
+ XXX.minecraft.nbt.NbtOps$1
- XXX.minecraft.nbt.NbtOps$ByteListCollector
+ XXX.minecraft.nbt.NbtOps$HeterogenousListCollector
- XXX.minecraft.nbt.NbtOps$HomogenousListCollector
+ XXX.minecraft.nbt.NbtOps$InitialListCollector
- XXX.minecraft.nbt.NbtOps$IntListCollector
+ XXX.minecraft.nbt.NbtOps$ListCollector
- XXX.minecraft.nbt.NbtOps$LongListCollector
+ XXX.minecraft.nbt.NbtOps$NbtRecordBuilder
- XXX.minecraft.nbt.NbtUtils
+ XXX.minecraft.nbt.NumericTag
- XXX.minecraft.nbt.package-info
- XXX.minecraft.nbt.ShortTag
+ XXX.minecraft.nbt.ShortTag$1
- XXX.minecraft.nbt.ShortTag$Cache
+ XXX.minecraft.nbt.SnbtPrinterTagVisitor
- XXX.minecraft.nbt.StreamTagVisitor
+ XXX.minecraft.nbt.StreamTagVisitor$EntryResult
- XXX.minecraft.nbt.StreamTagVisitor$ValueResult
+ XXX.minecraft.nbt.StringTag
- XXX.minecraft.nbt.StringTag$1
+ XXX.minecraft.nbt.StringTagVisitor
- XXX.minecraft.nbt.Tag
+ XXX.minecraft.nbt.TagParser
- XXX.minecraft.nbt.TagType
+ XXX.minecraft.nbt.TagType$1
- XXX.minecraft.nbt.TagType$2
+ XXX.minecraft.nbt.TagType$StaticSize
- XXX.minecraft.nbt.TagType$VariableSize
+ XXX.minecraft.nbt.TagTypes
- XXX.minecraft.nbt.TagVisitor
+ XXX.minecraft.nbt.TextComponentTagVisitor
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
+ XXX.minecraft.network.ConnectionProtocol$PacketSet
- XXX.minecraft.network.ConnectionProtocol$ProtocolBuilder
+ XXX.minecraft.network.FriendlyByteBuf
- XXX.minecraft.network.FriendlyByteBuf$Reader
+ XXX.minecraft.network.FriendlyByteBuf$Writer
- XXX.minecraft.network.package-info
- XXX.minecraft.network.PacketDecoder
+ XXX.minecraft.network.PacketEncoder
- XXX.minecraft.network.PacketListener
+ XXX.minecraft.network.PacketSendListener
- XXX.minecraft.network.PacketSendListener$1
+ XXX.minecraft.network.PacketSendListener$2
- XXX.minecraft.network.RateKickingConnection
+ XXX.minecraft.network.SkipPacketException
- XXX.minecraft.network.TickablePacketListener
+ XXX.minecraft.network.Varint21FrameDecoder
- XXX.minecraft.network.Varint21LengthFieldPrepender
+ XXX.minecraft.obfuscate.DontObfuscate
- XXX.minecraft.obfuscate.package-info
- XXX.minecraft.realms.DisconnectedRealmsScreen
- XXX.minecraft.realms.package-info
+ XXX.minecraft.realms.RealmsConnect
- XXX.minecraft.realms.RealmsConnect$1
+ XXX.minecraft.realms.RealmsLabel
- XXX.minecraft.realms.RealmsObjectSelectionList
+ XXX.minecraft.realms.RealmsScreen
- XXX.minecraft.realms.RepeatedNarrator
+ XXX.minecraft.realms.RepeatedNarrator$Params
+ XXX.minecraft.recipebook.package-info
+ XXX.minecraft.recipebook.PlaceRecipe
- XXX.minecraft.recipebook.ServerPlaceRecipe
- XXX.minecraft.resources.DelegatingOps
+ XXX.minecraft.resources.FileToIdConverter
- XXX.minecraft.resources.HolderSetCodec
+ XXX.minecraft.resources.package-info
+ XXX.minecraft.resources.RegistryDataLoader
- XXX.minecraft.resources.RegistryDataLoader$1
+ XXX.minecraft.resources.RegistryDataLoader$Loader
- XXX.minecraft.resources.RegistryDataLoader$RegistryData
+ XXX.minecraft.resources.RegistryFileCodec
- XXX.minecraft.resources.RegistryFixedCodec
+ XXX.minecraft.resources.RegistryOps
- XXX.minecraft.resources.RegistryOps$1
+ XXX.minecraft.resources.RegistryOps$2
- XXX.minecraft.resources.RegistryOps$RegistryInfo
+ XXX.minecraft.resources.RegistryOps$RegistryInfoLookup
- XXX.minecraft.resources.ResourceKey
+ XXX.minecraft.resources.ResourceKey$InternKey
- XXX.minecraft.resources.ResourceLocation
+ XXX.minecraft.resources.ResourceLocation$Dummy
- XXX.minecraft.resources.ResourceLocation$Serializer
- XXX.minecraft.server.Bootstrap
+ XXX.minecraft.server.Bootstrap$1
- XXX.minecraft.server.ChainedJsonException
+ XXX.minecraft.server.ChainedJsonException$Entry
- XXX.minecraft.server.ConsoleInput
+ XXX.minecraft.server.DebugLoggedPrintStream
- XXX.minecraft.server.Eula
+ XXX.minecraft.server.LoggedPrintStream
- XXX.minecraft.server.Main
+ XXX.minecraft.server.Main$1
- XXX.minecraft.server.MinecraftServer
+ XXX.minecraft.server.MinecraftServer$1
- XXX.minecraft.server.MinecraftServer$ReloadableResources
+ XXX.minecraft.server.MinecraftServer$ServerResourcePackInfo
- XXX.minecraft.server.MinecraftServer$TimeProfiler
+ XXX.minecraft.server.MinecraftServer$TimeProfiler$1
- XXX.minecraft.server.PlayerAdvancements
+ XXX.minecraft.server.PlayerAdvancements$1
- XXX.minecraft.server.RegistryLayer
+ XXX.minecraft.server.ReloadableServerResources
- XXX.minecraft.server.RunningOnDifferentThreadException
+ XXX.minecraft.server.ServerAdvancementManager
- XXX.minecraft.server.ServerFunctionLibrary
+ XXX.minecraft.server.ServerFunctionManager
- XXX.minecraft.server.ServerFunctionManager$ExecutionContext
+ XXX.minecraft.server.ServerFunctionManager$QueuedCommand
- XXX.minecraft.server.ServerFunctionManager$TraceCallbacks
+ XXX.minecraft.server.ServerInterface
- XXX.minecraft.server.ServerScoreboard
+ XXX.minecraft.server.ServerScoreboard$Method
- XXX.minecraft.server.Services
+ XXX.minecraft.server.TickTask
- XXX.minecraft.server.WorldLoader
+ XXX.minecraft.server.WorldLoader$DataLoadContext
- XXX.minecraft.server.WorldLoader$DataLoadOutput
+ XXX.minecraft.server.WorldLoader$InitConfig
- XXX.minecraft.server.WorldLoader$PackConfig
+ XXX.minecraft.server.WorldLoader$ResultFactory
- XXX.minecraft.server.WorldLoader$WorldDataSupplier
+ XXX.minecraft.server.WorldStem
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
+ XXX.minecraft.tags.BannerPatternTags
- XXX.minecraft.tags.BiomeTags
+ XXX.minecraft.tags.BlockTags
- XXX.minecraft.tags.CatVariantTags
+ XXX.minecraft.tags.EntityTypeTags
- XXX.minecraft.tags.FlatLevelGeneratorPresetTags
+ XXX.minecraft.tags.FluidTags
- XXX.minecraft.tags.GameEventTags
+ XXX.minecraft.tags.InstrumentTags
- XXX.minecraft.tags.ItemTags
- XXX.minecraft.tags.package-info
+ XXX.minecraft.tags.PaintingVariantTags
- XXX.minecraft.tags.PoiTypeTags
+ XXX.minecraft.tags.StructureTags
- XXX.minecraft.tags.TagBuilder
+ XXX.minecraft.tags.TagEntry
- XXX.minecraft.tags.TagEntry$Lookup
+ XXX.minecraft.tags.TagFile
- XXX.minecraft.tags.TagKey
+ XXX.minecraft.tags.TagLoader
- XXX.minecraft.tags.TagLoader$1
+ XXX.minecraft.tags.TagLoader$EntryWithSource
- XXX.minecraft.tags.TagManager
+ XXX.minecraft.tags.TagManager$LoadResult
- XXX.minecraft.tags.TagNetworkSerialization
+ XXX.minecraft.tags.TagNetworkSerialization$NetworkPayload
- XXX.minecraft.tags.TagNetworkSerialization$TagOutput
+ XXX.minecraft.tags.WorldPresetTags
- XXX.minecraft.util.AbortableIterationConsumer$Continuation
+ XXX.minecraft.util.BitStorage
- XXX.minecraft.util.ClassInstanceMultiMap
+ XXX.minecraft.util.CrudeIncrementalIntIdentityHashBiMap
- XXX.minecraft.util.Crypt
+ XXX.minecraft.util.Crypt$ByteArrayToKeyFunction
- XXX.minecraft.util.Crypt$SaltSignaturePair
+ XXX.minecraft.util.Crypt$SaltSupplier
- XXX.minecraft.util.CryptException
+ XXX.minecraft.util.CsvOutput
- XXX.minecraft.util.CsvOutput$Builder
+ XXX.minecraft.util.CubicSampler
- XXX.minecraft.util.CubicSampler$Vec3Fetcher
+ XXX.minecraft.util.CubicSpline
- XXX.minecraft.util.CubicSpline$1Point
+ XXX.minecraft.util.CubicSpline$Builder
- XXX.minecraft.util.CubicSpline$Constant
+ XXX.minecraft.util.CubicSpline$CoordinateVisitor
- XXX.minecraft.util.CubicSpline$Multipoint
+ XXX.minecraft.util.DebugBuffer
- XXX.minecraft.util.DirectoryLock
+ XXX.minecraft.util.DirectoryLock$LockException
- XXX.minecraft.util.ExceptionCollector
+ XXX.minecraft.util.ExtraCodecs
- XXX.minecraft.util.ExtraCodecs$1
+ XXX.minecraft.util.ExtraCodecs$1ContextRetrievalCodec
- XXX.minecraft.util.ExtraCodecs$2
+ XXX.minecraft.util.ExtraCodecs$3
- XXX.minecraft.util.ExtraCodecs$4
+ XXX.minecraft.util.ExtraCodecs$EitherCodec
- XXX.minecraft.util.ExtraCodecs$LazyInitializedCodec
+ XXX.minecraft.util.ExtraCodecs$TagOrElementLocation
- XXX.minecraft.util.ExtraCodecs$XorCodec
+ XXX.minecraft.util.FastBufferedInputStream
- XXX.minecraft.util.FastColor
+ XXX.minecraft.util.FastColor$ARGB32
- XXX.minecraft.util.FileZipper
+ XXX.minecraft.util.FormattedCharSequence
- XXX.minecraft.util.FormattedCharSink
+ XXX.minecraft.util.FrameTimer
- XXX.minecraft.util.FutureChain
+ XXX.minecraft.util.Graph
- XXX.minecraft.util.GsonHelper
+ XXX.minecraft.util.HttpUtil
- XXX.minecraft.util.InclusiveRange
+ XXX.minecraft.util.KeyDispatchDataCodec
- XXX.minecraft.util.LazyLoadedValue
+ XXX.minecraft.util.LinearCongruentialGenerator
- XXX.minecraft.util.LowerCaseEnumTypeAdapterFactory
+ XXX.minecraft.util.LowerCaseEnumTypeAdapterFactory$1
- XXX.minecraft.util.MemoryReserve
+ XXX.minecraft.util.ModCheck
- XXX.minecraft.util.ModCheck$Confidence
+ XXX.minecraft.util.Mth
- XXX.minecraft.util.NativeModuleLister
+ XXX.minecraft.util.NativeModuleLister$NativeModuleInfo
- XXX.minecraft.util.NativeModuleLister$NativeModuleVersion
+ XXX.minecraft.util.OptionEnum
- XXX.minecraft.util.ParticleUtils
+ XXX.minecraft.util.ProgressListener
- XXX.minecraft.util.RandomSource
+ XXX.minecraft.util.TelemetryConstants
- XXX.minecraft.util.ThreadingDetector
+ XXX.minecraft.util.TimeSource
- XXX.minecraft.util.TimeSource$NanoTimeSource
+ XXX.minecraft.util.TimeUtil
- XXX.minecraft.util.ToFloatFunction
+ XXX.minecraft.util.ToFloatFunction$1
- XXX.minecraft.util.ToFloatFunction$2
+ XXX.minecraft.util.Tuple
- XXX.minecraft.util.Unit
+ XXX.minecraft.util.VisibleForDebug
- XXX.minecraft.util.ZeroBitStorage
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
+ XXX.models.blockstates.BlockStateGenerator
- XXX.models.blockstates.Condition
+ XXX.models.blockstates.Condition$CompositeCondition
- XXX.models.blockstates.Condition$Operation
+ XXX.models.blockstates.Condition$TerminalCondition
- XXX.models.blockstates.MultiPartGenerator
+ XXX.models.blockstates.MultiPartGenerator$ConditionalEntry
- XXX.models.blockstates.MultiPartGenerator$Entry
+ XXX.models.blockstates.MultiVariantGenerator
+ XXX.models.blockstates.package-info
- XXX.models.blockstates.PropertyDispatch
+ XXX.models.blockstates.PropertyDispatch$C1
- XXX.models.blockstates.PropertyDispatch$C2
+ XXX.models.blockstates.PropertyDispatch$C3
- XXX.models.blockstates.PropertyDispatch$C4
+ XXX.models.blockstates.PropertyDispatch$C5
- XXX.models.blockstates.PropertyDispatch$PentaFunction
+ XXX.models.blockstates.PropertyDispatch$QuadFunction
- XXX.models.blockstates.PropertyDispatch$TriFunction
+ XXX.models.blockstates.Selector
- XXX.models.blockstates.Variant
+ XXX.models.blockstates.VariantProperties
- XXX.models.blockstates.VariantProperties$Rotation
+ XXX.models.blockstates.VariantProperty
- XXX.models.blockstates.VariantProperty$Value
- XXX.models.model.DelegatedModel
+ XXX.models.model.ModelLocationUtils
- XXX.models.model.ModelTemplate
+ XXX.models.model.ModelTemplates
- XXX.models.model.package-info
- XXX.models.model.TexturedModel
+ XXX.models.model.TexturedModel$Provider
- XXX.models.model.TextureMapping
+ XXX.models.model.TextureSlot
- XXX.multiplayer.chat.ChatListener
+ XXX.multiplayer.chat.ChatListener$Message
- XXX.multiplayer.chat.ChatLog
+ XXX.multiplayer.chat.ChatTrustLevel
- XXX.multiplayer.chat.ChatTrustLevel$1
+ XXX.multiplayer.chat.LoggedChatEvent
- XXX.multiplayer.chat.LoggedChatEvent$Type
+ XXX.multiplayer.chat.LoggedChatMessage
- XXX.multiplayer.chat.LoggedChatMessage$Player
+ XXX.multiplayer.chat.LoggedChatMessage$System
- XXX.multiplayer.chat.package-info
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
+ XXX.nbt.visitors.CollectFields
- XXX.nbt.visitors.CollectToTag
+ XXX.nbt.visitors.FieldSelector
- XXX.nbt.visitors.FieldTree
- XXX.nbt.visitors.package-info
+ XXX.nbt.visitors.SkipAll
- XXX.nbt.visitors.SkipAll$1
+ XXX.nbt.visitors.SkipFields
+ XXX.network.chat.ChatDecorator
- XXX.network.chat.ChatType
+ XXX.network.chat.ChatType$Bound
- XXX.network.chat.ChatType$BoundNetwork
+ XXX.network.chat.ChatTypeDecoration
- XXX.network.chat.ChatTypeDecoration$Parameter
+ XXX.network.chat.ChatTypeDecoration$Parameter$Selector
- XXX.network.chat.ClickEvent
+ XXX.network.chat.ClickEvent$Action
- XXX.network.chat.CommonComponents
+ XXX.network.chat.Component
- XXX.network.chat.Component$Serializer
+ XXX.network.chat.ComponentContents
- XXX.network.chat.ComponentContents$1
+ XXX.network.chat.ComponentUtils
- XXX.network.chat.FilterMask
+ XXX.network.chat.FilterMask$1
- XXX.network.chat.FilterMask$Type
+ XXX.network.chat.FormattedText
- XXX.network.chat.FormattedText$1
+ XXX.network.chat.FormattedText$2
- XXX.network.chat.FormattedText$3
+ XXX.network.chat.FormattedText$4
- XXX.network.chat.FormattedText$ContentConsumer
+ XXX.network.chat.FormattedText$StyledContentConsumer
- XXX.network.chat.HoverEvent
+ XXX.network.chat.HoverEvent$Action
- XXX.network.chat.HoverEvent$EntityTooltipInfo
+ XXX.network.chat.HoverEvent$ItemStackInfo
- XXX.network.chat.LastSeenMessages
+ XXX.network.chat.LastSeenMessages$Packed
- XXX.network.chat.LastSeenMessages$Update
+ XXX.network.chat.LastSeenMessagesTracker
- XXX.network.chat.LastSeenMessagesTracker$Update
+ XXX.network.chat.LastSeenMessagesValidator
- XXX.network.chat.LastSeenTrackedEntry
+ XXX.network.chat.LocalChatSession
- XXX.network.chat.MessageSignature
+ XXX.network.chat.MessageSignature$Packed
- XXX.network.chat.MessageSignatureCache
+ XXX.network.chat.MutableComponent
- XXX.network.chat.OutgoingChatMessage
+ XXX.network.chat.OutgoingChatMessage$Disguised
- XXX.network.chat.OutgoingChatMessage$Player
+ XXX.network.chat.package-info
+ XXX.network.chat.PlayerChatMessage
- XXX.network.chat.RemoteChatSession
+ XXX.network.chat.RemoteChatSession$Data
- XXX.network.chat.SignableCommand
+ XXX.network.chat.SignableCommand$Argument
- XXX.network.chat.SignedMessageBody
+ XXX.network.chat.SignedMessageBody$Packed
- XXX.network.chat.SignedMessageChain
+ XXX.network.chat.SignedMessageChain$DecodeException
- XXX.network.chat.SignedMessageChain$Decoder
+ XXX.network.chat.SignedMessageChain$Encoder
- XXX.network.chat.SignedMessageLink
+ XXX.network.chat.SignedMessageValidator
- XXX.network.chat.SignedMessageValidator$KeyBased
+ XXX.network.chat.Style
- XXX.network.chat.Style$1
+ XXX.network.chat.Style$1Collector
- XXX.network.chat.Style$Serializer
+ XXX.network.chat.SubStringSource
- XXX.network.chat.TextColor
+ XXX.network.chat.ThrowingComponent
+ XXX.network.protocol.package-info
+ XXX.network.protocol.Packet
- XXX.network.protocol.PacketFlow
+ XXX.network.protocol.PacketUtils
+ XXX.network.syncher.EntityDataAccessor
- XXX.network.syncher.EntityDataSerializer
+ XXX.network.syncher.EntityDataSerializer$1
- XXX.network.syncher.EntityDataSerializer$ForValueType
+ XXX.network.syncher.EntityDataSerializers
- XXX.network.syncher.EntityDataSerializers$1
+ XXX.network.syncher.EntityDataSerializers$2
- XXX.network.syncher.EntityDataSerializers$3
+ XXX.network.syncher.EntityDataSerializers$4
- XXX.network.syncher.EntityDataSerializers$5
+ XXX.network.syncher.EntityDataSerializers$6
- XXX.network.syncher.EntityDataSerializers$7
- XXX.network.syncher.package-info
+ XXX.network.syncher.SynchedEntityData
- XXX.network.syncher.SynchedEntityData$DataItem
+ XXX.network.syncher.SynchedEntityData$DataValue
- XXX.packs.resources.package-info
+ XXX.packs.resources.ResourceFilterSection$ResourceLocationPattern
- XXX.packs.resources.ResourceManager
+ XXX.packs.resources.ResourceManager$Empty
- XXX.packs.resources.ResourceManagerReloadListener
+ XXX.packs.resources.ResourceMetadata
- XXX.packs.resources.ResourceMetadata$1
+ XXX.packs.resources.ResourceMetadata$2
- XXX.packs.resources.ResourceProvider
+ XXX.packs.resources.SimpleJsonResourceReloadListener
- XXX.packs.resources.SimplePreparableReloadListener
+ XXX.packs.resources.SimpleReloadInstance
- XXX.packs.resources.SimpleReloadInstance$1
+ XXX.packs.resources.SimpleReloadInstance$StateFactory
- XXX.player.inventory.Hotbar
+ XXX.player.inventory.package-info
+ XXX.protocol.game.ClientboundAddEntityPacket
- XXX.protocol.game.ClientboundAddExperienceOrbPacket
+ XXX.protocol.game.ClientboundAddPlayerPacket
- XXX.protocol.game.ClientboundAnimatePacket
+ XXX.protocol.game.ClientboundAwardStatsPacket
- XXX.protocol.game.ClientboundBlockChangedAckPacket
+ XXX.protocol.game.ClientboundBlockDestructionPacket
- XXX.protocol.game.ClientboundBlockEntityDataPacket
+ XXX.protocol.game.ClientboundBlockEventPacket
- XXX.protocol.game.ClientboundBlockUpdatePacket
+ XXX.protocol.game.ClientboundBossEventPacket
- XXX.protocol.game.ClientboundBossEventPacket$1
+ XXX.protocol.game.ClientboundBossEventPacket$AddOperation
- XXX.protocol.game.ClientboundBossEventPacket$Handler
+ XXX.protocol.game.ClientboundBossEventPacket$Operation
- XXX.protocol.game.ClientboundBossEventPacket$OperationType
+ XXX.protocol.game.ClientboundBossEventPacket$UpdateNameOperation
- XXX.protocol.game.ClientboundBossEventPacket$UpdateProgressOperation
+ XXX.protocol.game.ClientboundBossEventPacket$UpdatePropertiesOperation
- XXX.protocol.game.ClientboundBossEventPacket$UpdateStyleOperation
+ XXX.protocol.game.ClientboundChangeDifficultyPacket
- XXX.protocol.game.ClientboundClearTitlesPacket
- XXX.protocol.game.ClientboundCommandsPacket
+ XXX.protocol.game.ClientboundCommandsPacket$ArgumentNodeStub
- XXX.protocol.game.ClientboundCommandsPacket$Entry
+ XXX.protocol.game.ClientboundCommandsPacket$LiteralNodeStub
- XXX.protocol.game.ClientboundCommandsPacket$NodeResolver
+ XXX.protocol.game.ClientboundCommandsPacket$NodeStub
+ XXX.protocol.game.ClientboundCommandSuggestionsPacket
- XXX.protocol.game.ClientboundContainerClosePacket
+ XXX.protocol.game.ClientboundContainerSetContentPacket
- XXX.protocol.game.ClientboundContainerSetDataPacket
+ XXX.protocol.game.ClientboundContainerSetSlotPacket
- XXX.protocol.game.ClientboundCooldownPacket
+ XXX.protocol.game.ClientboundCustomChatCompletionsPacket
- XXX.protocol.game.ClientboundCustomChatCompletionsPacket$Action
+ XXX.protocol.game.ClientboundCustomPayloadPacket
- XXX.protocol.game.ClientboundCustomSoundPacket
+ XXX.protocol.game.ClientboundDeleteChatPacket
- XXX.protocol.game.ClientboundDisconnectPacket
+ XXX.protocol.game.ClientboundDisguisedChatPacket
- XXX.protocol.game.ClientboundEntityEventPacket
+ XXX.protocol.game.ClientboundExplodePacket
- XXX.protocol.game.ClientboundForgetLevelChunkPacket
+ XXX.protocol.game.ClientboundGameEventPacket
- XXX.protocol.game.ClientboundGameEventPacket$Type
+ XXX.protocol.game.ClientboundHorseScreenOpenPacket
- XXX.protocol.game.ClientboundInitializeBorderPacket
+ XXX.protocol.game.ClientboundKeepAlivePacket
- XXX.protocol.game.ClientboundLevelChunkPacketData
+ XXX.protocol.game.ClientboundLevelChunkPacketData$BlockEntityInfo
- XXX.protocol.game.ClientboundLevelChunkPacketData$BlockEntityTagOutput
+ XXX.protocol.game.ClientboundLevelChunkWithLightPacket
- XXX.protocol.game.ClientboundLevelEventPacket
+ XXX.protocol.game.ClientboundLevelParticlesPacket
- XXX.protocol.game.ClientboundLightUpdatePacket
+ XXX.protocol.game.ClientboundLightUpdatePacketData
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
+ XXX.protocol.game.ClientboundPingPacket
- XXX.protocol.game.ClientboundPlaceGhostRecipePacket
+ XXX.protocol.game.ClientboundPlayerAbilitiesPacket
- XXX.protocol.game.ClientboundPlayerChatPacket
+ XXX.protocol.game.ClientboundPlayerCombatEndPacket
- XXX.protocol.game.ClientboundPlayerCombatEnterPacket
+ XXX.protocol.game.ClientboundPlayerCombatKillPacket
- XXX.protocol.game.ClientboundPlayerInfoRemovePacket
+ XXX.protocol.game.ClientboundPlayerInfoUpdatePacket
- XXX.protocol.game.ClientboundPlayerInfoUpdatePacket$Action
+ XXX.protocol.game.ClientboundPlayerInfoUpdatePacket$Action$Reader
- XXX.protocol.game.ClientboundPlayerInfoUpdatePacket$Action$Writer
+ XXX.protocol.game.ClientboundPlayerInfoUpdatePacket$Entry
- XXX.protocol.game.ClientboundPlayerInfoUpdatePacket$EntryBuilder
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
+ XXX.protocol.game.ClientboundSectionBlocksUpdatePacket
- XXX.protocol.game.ClientboundSelectAdvancementsTabPacket
+ XXX.protocol.game.ClientboundServerDataPacket
- XXX.protocol.game.ClientboundSetActionBarTextPacket
+ XXX.protocol.game.ClientboundSetBorderCenterPacket
- XXX.protocol.game.ClientboundSetBorderLerpSizePacket
+ XXX.protocol.game.ClientboundSetBorderSizePacket
- XXX.protocol.game.ClientboundSetBorderWarningDelayPacket
+ XXX.protocol.game.ClientboundSetBorderWarningDistancePacket
- XXX.protocol.game.ClientboundSetCameraPacket
+ XXX.protocol.game.ClientboundSetCarriedItemPacket
- XXX.protocol.game.ClientboundSetChunkCacheCenterPacket
+ XXX.protocol.game.ClientboundSetChunkCacheRadiusPacket
- XXX.protocol.game.ClientboundSetDefaultSpawnPositionPacket
+ XXX.protocol.game.ClientboundSetDisplayObjectivePacket
- XXX.protocol.game.ClientboundSetEntityDataPacket
+ XXX.protocol.game.ClientboundSetEntityLinkPacket
- XXX.protocol.game.ClientboundSetEntityMotionPacket
+ XXX.protocol.game.ClientboundSetEquipmentPacket
- XXX.protocol.game.ClientboundSetExperiencePacket
+ XXX.protocol.game.ClientboundSetHealthPacket
- XXX.protocol.game.ClientboundSetObjectivePacket
+ XXX.protocol.game.ClientboundSetPassengersPacket
- XXX.protocol.game.ClientboundSetPlayerTeamPacket
+ XXX.protocol.game.ClientboundSetPlayerTeamPacket$Action
- XXX.protocol.game.ClientboundSetPlayerTeamPacket$Parameters
+ XXX.protocol.game.ClientboundSetScorePacket
- XXX.protocol.game.ClientboundSetSimulationDistancePacket
+ XXX.protocol.game.ClientboundSetSubtitleTextPacket
- XXX.protocol.game.ClientboundSetTimePacket
- XXX.protocol.game.ClientboundSetTitlesAnimationPacket
+ XXX.protocol.game.ClientboundSetTitleTextPacket
+ XXX.protocol.game.ClientboundSoundEntityPacket
- XXX.protocol.game.ClientboundSoundPacket
+ XXX.protocol.game.ClientboundStopSoundPacket
- XXX.protocol.game.ClientboundSystemChatPacket
+ XXX.protocol.game.ClientboundTabListPacket
- XXX.protocol.game.ClientboundTagQueryPacket
+ XXX.protocol.game.ClientboundTakeItemEntityPacket
- XXX.protocol.game.ClientboundTeleportEntityPacket
+ XXX.protocol.game.ClientboundUpdateAdvancementsPacket
- XXX.protocol.game.ClientboundUpdateAttributesPacket
+ XXX.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
- XXX.protocol.game.ClientboundUpdateEnabledFeaturesPacket
+ XXX.protocol.game.ClientboundUpdateMobEffectPacket
- XXX.protocol.game.ClientboundUpdateRecipesPacket
+ XXX.protocol.game.ClientboundUpdateTagsPacket
- XXX.protocol.game.ClientGamePacketListener
- XXX.protocol.game.DebugEntityNameGenerator
+ XXX.protocol.game.DebugPackets
- XXX.protocol.game.package-info
- XXX.protocol.game.ServerboundAcceptTeleportationPacket
+ XXX.protocol.game.ServerboundBlockEntityTagQuery
- XXX.protocol.game.ServerboundChangeDifficultyPacket
+ XXX.protocol.game.ServerboundChatAckPacket
- XXX.protocol.game.ServerboundChatCommandPacket
+ XXX.protocol.game.ServerboundChatPacket
- XXX.protocol.game.ServerboundChatSessionUpdatePacket
+ XXX.protocol.game.ServerboundClientCommandPacket
- XXX.protocol.game.ServerboundClientCommandPacket$Action
+ XXX.protocol.game.ServerboundClientInformationPacket
- XXX.protocol.game.ServerboundCommandSuggestionPacket
+ XXX.protocol.game.ServerboundContainerButtonClickPacket
- XXX.protocol.game.ServerboundContainerClickPacket
+ XXX.protocol.game.ServerboundContainerClosePacket
- XXX.protocol.game.ServerboundCustomPayloadPacket
+ XXX.protocol.game.ServerboundEditBookPacket
- XXX.protocol.game.ServerboundEntityTagQuery
+ XXX.protocol.game.ServerboundInteractPacket
- XXX.protocol.game.ServerboundInteractPacket$1
+ XXX.protocol.game.ServerboundInteractPacket$Action
- XXX.protocol.game.ServerboundInteractPacket$ActionType
+ XXX.protocol.game.ServerboundInteractPacket$Handler
- XXX.protocol.game.ServerboundInteractPacket$InteractionAction
+ XXX.protocol.game.ServerboundInteractPacket$InteractionAtLocationAction
- XXX.protocol.game.ServerboundJigsawGeneratePacket
+ XXX.protocol.game.ServerboundKeepAlivePacket
- XXX.protocol.game.ServerboundLockDifficultyPacket
+ XXX.protocol.game.ServerboundMovePlayerPacket
- XXX.protocol.game.ServerboundMovePlayerPacket$Pos
+ XXX.protocol.game.ServerboundMovePlayerPacket$PosRot
- XXX.protocol.game.ServerboundMovePlayerPacket$Rot
+ XXX.protocol.game.ServerboundMovePlayerPacket$StatusOnly
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
- XXX.protocol.game.ServerboundPongPacket
+ XXX.protocol.game.ServerboundRecipeBookChangeSettingsPacket
- XXX.protocol.game.ServerboundRecipeBookSeenRecipePacket
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
+ XXX.protocol.game.ServerPacketListener
+ XXX.protocol.game.VecDeltaCodec
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
+ XXX.recipes.packs.BundleRecipeProvider
- XXX.recipes.packs.package-info
- XXX.recipes.packs.UpdateOneTwentyRecipeProvider
+ XXX.recipes.packs.VanillaRecipeProvider
+ XXX.renderer.block.BlockModelShaper
- XXX.renderer.block.BlockRenderDispatcher
+ XXX.renderer.block.BlockRenderDispatcher$1
- XXX.renderer.block.LiquidBlockRenderer
+ XXX.renderer.block.LiquidBlockRenderer$1
- XXX.renderer.block.ModelBlockRenderer
+ XXX.renderer.block.ModelBlockRenderer$1
- XXX.renderer.block.ModelBlockRenderer$AdjacencyInfo
+ XXX.renderer.block.ModelBlockRenderer$AmbientOcclusionFace
- XXX.renderer.block.ModelBlockRenderer$AmbientVertexRemap
+ XXX.renderer.block.ModelBlockRenderer$Cache
- XXX.renderer.block.ModelBlockRenderer$Cache$1
+ XXX.renderer.block.ModelBlockRenderer$Cache$2
- XXX.renderer.block.ModelBlockRenderer$SizeInfo
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
+ XXX.renderer.blockentity.CampfireRenderer
- XXX.renderer.blockentity.ChestRenderer
+ XXX.renderer.blockentity.ConduitRenderer
- XXX.renderer.blockentity.EnchantTableRenderer
+ XXX.renderer.blockentity.HangingSignRenderer
- XXX.renderer.blockentity.HangingSignRenderer$HangingSignModel
+ XXX.renderer.blockentity.LecternRenderer
- XXX.renderer.blockentity.package-info
- XXX.renderer.blockentity.PistonHeadRenderer
+ XXX.renderer.blockentity.ShulkerBoxRenderer
- XXX.renderer.blockentity.SignRenderer
+ XXX.renderer.blockentity.SignRenderer$SignModel
- XXX.renderer.blockentity.SkullBlockRenderer
+ XXX.renderer.blockentity.SpawnerRenderer
- XXX.renderer.blockentity.StructureBlockRenderer
+ XXX.renderer.blockentity.StructureBlockRenderer$1
- XXX.renderer.blockentity.TheEndGatewayRenderer
+ XXX.renderer.blockentity.TheEndPortalRenderer
+ XXX.renderer.chunk.ChunkRenderDispatcher
- XXX.renderer.chunk.ChunkRenderDispatcher$ChunkTaskResult
+ XXX.renderer.chunk.ChunkRenderDispatcher$CompiledChunk
- XXX.renderer.chunk.ChunkRenderDispatcher$CompiledChunk$1
+ XXX.renderer.chunk.ChunkRenderDispatcher$RenderChunk
- XXX.renderer.chunk.ChunkRenderDispatcher$RenderChunk$ChunkCompileTask
+ XXX.renderer.chunk.ChunkRenderDispatcher$RenderChunk$RebuildTask
- XXX.renderer.chunk.ChunkRenderDispatcher$RenderChunk$RebuildTask$CompileResults
+ XXX.renderer.chunk.ChunkRenderDispatcher$RenderChunk$ResortTransparencyTask
+ XXX.renderer.chunk.package-info
- XXX.renderer.chunk.RenderChunk
+ XXX.renderer.chunk.RenderChunkRegion
- XXX.renderer.chunk.RenderRegionCache
+ XXX.renderer.chunk.RenderRegionCache$ChunkInfo
- XXX.renderer.chunk.VisGraph
+ XXX.renderer.chunk.VisGraph$1
- XXX.renderer.chunk.VisibilitySet
- XXX.renderer.culling.Frustum
+ XXX.renderer.culling.package-info
- XXX.renderer.debug.BeeDebugRenderer
+ XXX.renderer.debug.BeeDebugRenderer$BeeInfo
- XXX.renderer.debug.BeeDebugRenderer$HiveInfo
+ XXX.renderer.debug.BrainDebugRenderer
- XXX.renderer.debug.BrainDebugRenderer$BrainDump
+ XXX.renderer.debug.BrainDebugRenderer$PoiInfo
- XXX.renderer.debug.ChunkBorderRenderer
+ XXX.renderer.debug.ChunkDebugRenderer
- XXX.renderer.debug.ChunkDebugRenderer$ChunkData
+ XXX.renderer.debug.CollisionBoxRenderer
- XXX.renderer.debug.DebugRenderer
+ XXX.renderer.debug.DebugRenderer$SimpleDebugRenderer
- XXX.renderer.debug.GameEventListenerRenderer
+ XXX.renderer.debug.GameEventListenerRenderer$TrackedGameEvent
- XXX.renderer.debug.GameEventListenerRenderer$TrackedListener
+ XXX.renderer.debug.GameTestDebugRenderer
- XXX.renderer.debug.GameTestDebugRenderer$Marker
+ XXX.renderer.debug.GoalSelectorDebugRenderer
- XXX.renderer.debug.GoalSelectorDebugRenderer$DebugGoal
+ XXX.renderer.debug.HeightMapRenderer
- XXX.renderer.debug.HeightMapRenderer$1
+ XXX.renderer.debug.LightDebugRenderer
- XXX.renderer.debug.NeighborsUpdateRenderer
- XXX.renderer.debug.package-info
+ XXX.renderer.debug.PathfindingRenderer
- XXX.renderer.debug.RaidDebugRenderer
+ XXX.renderer.debug.SolidFaceRenderer
- XXX.renderer.debug.StructureRenderer
+ XXX.renderer.debug.VillageSectionsDebugRenderer
- XXX.renderer.debug.WaterDebugRenderer
+ XXX.renderer.debug.WorldGenAttemptRenderer
+ XXX.renderer.entity.AbstractHorseRenderer
- XXX.renderer.entity.AbstractZombieRenderer
+ XXX.renderer.entity.AllayRenderer
- XXX.renderer.entity.ArmorStandRenderer
+ XXX.renderer.entity.ArrowRenderer
- XXX.renderer.entity.AxolotlRenderer
+ XXX.renderer.entity.BatRenderer
- XXX.renderer.entity.BeeRenderer
+ XXX.renderer.entity.BlazeRenderer
- XXX.renderer.entity.BoatRenderer
+ XXX.renderer.entity.CamelRenderer
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
- XXX.renderer.entity.package-info
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
+ XXX.renderer.item.ClampedItemPropertyFunction
- XXX.renderer.item.CompassItemPropertyFunction
+ XXX.renderer.item.CompassItemPropertyFunction$CompassTarget
- XXX.renderer.item.CompassItemPropertyFunction$CompassWobble
+ XXX.renderer.item.ItemProperties
- XXX.renderer.item.ItemProperties$1
+ XXX.renderer.item.ItemPropertyFunction
- XXX.renderer.item.package-info
- XXX.renderer.texture.AbstractTexture
+ XXX.renderer.texture.DynamicTexture
- XXX.renderer.texture.HttpTexture
+ XXX.renderer.texture.MipmapGenerator
- XXX.renderer.texture.MissingTextureAtlasSprite
+ XXX.renderer.texture.OverlayTexture
+ XXX.renderer.texture.package-info
- XXX.renderer.texture.PreloadedTexture
+ XXX.renderer.texture.SimpleTexture
- XXX.renderer.texture.SimpleTexture$TextureImage
+ XXX.renderer.texture.SpriteContents
- XXX.renderer.texture.SpriteContents$AnimatedTexture
+ XXX.renderer.texture.SpriteContents$FrameInfo
- XXX.renderer.texture.SpriteContents$InterpolationData
+ XXX.renderer.texture.SpriteContents$Ticker
- XXX.renderer.texture.SpriteLoader
+ XXX.renderer.texture.SpriteLoader$Preparations
- XXX.renderer.texture.SpriteTicker
+ XXX.renderer.texture.Stitcher
- XXX.renderer.texture.Stitcher$Entry
+ XXX.renderer.texture.Stitcher$Holder
- XXX.renderer.texture.Stitcher$Region
+ XXX.renderer.texture.Stitcher$SpriteLoader
- XXX.renderer.texture.StitcherException
+ XXX.renderer.texture.TextureAtlas
- XXX.renderer.texture.TextureAtlasSprite
+ XXX.renderer.texture.TextureAtlasSprite$1
- XXX.renderer.texture.TextureAtlasSprite$Ticker
+ XXX.renderer.texture.TextureManager
- XXX.renderer.texture.Tickable
+ XXX.resources.language.ClientLanguage
- XXX.resources.language.FormattedBidiReorder
+ XXX.resources.language.I18n
- XXX.resources.language.LanguageInfo
+ XXX.resources.language.LanguageManager
- XXX.resources.language.package-info
- XXX.resources.metadata.package-info
- XXX.resources.model.AtlasSet
+ XXX.resources.model.AtlasSet$AtlasEntry
- XXX.screens.achievement.package-info
+ XXX.screens.achievement.StatsScreen
- XXX.screens.achievement.StatsScreen$GeneralStatisticsList
+ XXX.screens.achievement.StatsScreen$GeneralStatisticsList$Entry
- XXX.screens.achievement.StatsScreen$ItemStatisticsList
+ XXX.screens.achievement.StatsScreen$ItemStatisticsList$ItemRow
- XXX.screens.achievement.StatsScreen$ItemStatisticsList$ItemRowComparator
+ XXX.screens.achievement.StatsScreen$MobsStatisticsList
- XXX.screens.achievement.StatsScreen$MobsStatisticsList$MobRow
+ XXX.screens.achievement.StatsUpdateListener
- XXX.screens.advancements.AdvancementsScreen
+ XXX.screens.advancements.AdvancementTab
- XXX.screens.advancements.AdvancementTabType
+ XXX.screens.advancements.AdvancementTabType$1
- XXX.screens.advancements.AdvancementWidget
+ XXX.screens.advancements.AdvancementWidgetType
+ XXX.screens.advancements.package-info
- XXX.screens.controls.ControlsScreen
+ XXX.screens.controls.KeyBindsList
- XXX.screens.controls.KeyBindsList$CategoryEntry
+ XXX.screens.controls.KeyBindsList$CategoryEntry$1
- XXX.screens.controls.KeyBindsList$Entry
+ XXX.screens.controls.KeyBindsList$KeyEntry
- XXX.screens.controls.KeyBindsScreen
+ XXX.screens.controls.package-info
- XXX.screens.debug.GameModeSwitcherScreen
+ XXX.screens.debug.GameModeSwitcherScreen$1
- XXX.screens.debug.GameModeSwitcherScreen$GameModeIcon
+ XXX.screens.debug.GameModeSwitcherScreen$GameModeSlot
- XXX.screens.debug.package-info
+ XXX.screens.inventory.AbstractCommandBlockEditScreen
- XXX.screens.inventory.AbstractCommandBlockEditScreen$1
+ XXX.screens.inventory.AbstractContainerScreen
- XXX.screens.inventory.AbstractFurnaceScreen
+ XXX.screens.inventory.AbstractSignEditScreen
- XXX.screens.inventory.AnvilScreen
+ XXX.screens.inventory.BeaconScreen
- XXX.screens.inventory.BeaconScreen$1
+ XXX.screens.inventory.BeaconScreen$BeaconButton
- XXX.screens.inventory.BeaconScreen$BeaconCancelButton
+ XXX.screens.inventory.BeaconScreen$BeaconConfirmButton
- XXX.screens.inventory.BeaconScreen$BeaconPowerButton
+ XXX.screens.inventory.BeaconScreen$BeaconScreenButton
- XXX.screens.inventory.BeaconScreen$BeaconSpriteScreenButton
+ XXX.screens.inventory.BeaconScreen$BeaconUpgradePowerButton
- XXX.screens.inventory.BlastFurnaceScreen
+ XXX.screens.inventory.BookEditScreen
- XXX.screens.inventory.BookEditScreen$DisplayCache
+ XXX.screens.inventory.BookEditScreen$LineInfo
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
+ XXX.screens.inventory.HangingSignEditScreen
- XXX.screens.inventory.HopperScreen
+ XXX.screens.inventory.HorseInventoryScreen
- XXX.screens.inventory.InventoryScreen
+ XXX.screens.inventory.ItemCombinerScreen
- XXX.screens.inventory.JigsawBlockEditScreen
+ XXX.screens.inventory.JigsawBlockEditScreen$1
- XXX.screens.inventory.LecternScreen
+ XXX.screens.inventory.LecternScreen$1
- XXX.screens.inventory.LoomScreen
+ XXX.screens.inventory.MenuAccess
- XXX.screens.inventory.MerchantScreen
+ XXX.screens.inventory.MerchantScreen$TradeOfferButton
- XXX.screens.inventory.MinecartCommandBlockEditScreen
- XXX.screens.inventory.package-info
+ XXX.screens.inventory.PageButton
- XXX.screens.inventory.ShulkerBoxScreen
+ XXX.screens.inventory.SignEditScreen
- XXX.screens.inventory.SmithingScreen
+ XXX.screens.inventory.SmokerScreen
- XXX.screens.inventory.StonecutterScreen
+ XXX.screens.inventory.StructureBlockEditScreen
- XXX.screens.inventory.StructureBlockEditScreen$1
+ XXX.screens.inventory.StructureBlockEditScreen$2
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
- XXX.screens.telemetry.TelemetryEventWidget$ContentBuilder
- XXX.server.bossevents.CustomBossEvent
+ XXX.server.bossevents.CustomBossEvents
- XXX.server.bossevents.package-info
+ XXX.server.chase.ChaseClient
- XXX.server.chase.ChaseClient$TeleportTarget
+ XXX.server.chase.ChaseServer
- XXX.server.chase.ChaseServer$PlayerPosition
+ XXX.server.chase.package-info
- XXX.server.commands.AdvancementCommands
+ XXX.server.commands.AdvancementCommands$Action
- XXX.server.commands.AdvancementCommands$Action$1
+ XXX.server.commands.AdvancementCommands$Action$2
- XXX.server.commands.AdvancementCommands$Mode
+ XXX.server.commands.AttributeCommand
- XXX.server.commands.BanIpCommands
+ XXX.server.commands.BanListCommands
- XXX.server.commands.BanPlayerCommands
+ XXX.server.commands.BossBarCommands
- XXX.server.commands.ChaseCommand
+ XXX.server.commands.ClearInventoryCommands
- XXX.server.commands.CloneCommands
+ XXX.server.commands.CloneCommands$CloneBlockInfo
- XXX.server.commands.CloneCommands$Mode
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
- XXX.telemetry.events.AggregatedTelemetryEvent
- XXX.telemetry.events.package-info
- XXX.telemetry.events.TelemetryEventProducer
- XXX.telemetry.events.WorldLoadEvent$1
- XXX.telemetry.events.WorldLoadTimesEvent
- XXX.texture.atlas.package-info
- XXX.texture.atlas.SpriteResourceLoader$1
- XXX.texture.atlas.SpriteSource$Output
- XXX.texture.atlas.SpriteSourceType
- XXX.util.datafix.DataFixerOptimizationOption
+ XXX.util.datafix.DataFixers
- XXX.util.datafix.DataFixers$1
+ XXX.util.datafix.DataFixers$2
- XXX.util.datafix.DataFixers$3
+ XXX.util.datafix.DataFixTypes
+ XXX.util.datafix.package-info
+ XXX.util.datafix.PackedBitStorage
- XXX.util.eventlog.EventLogDirectory$CompressedFile
- XXX.util.eventlog.EventLogDirectory$FileId
- XXX.util.eventlog.EventLogDirectory$RawFile
- XXX.util.eventlog.JsonEventLog$1
- XXX.util.eventlog.JsonEventLogReader$1
+ XXX.world.item.StackInventory
+ XXX.worldgen.biome.Biomes
- XXX.worldgen.biome.EndBiomes
+ XXX.worldgen.biome.NetherBiomes
- XXX.worldgen.biome.OverworldBiomes
+ XXX.worldgen.biome.package-info
- XXX.worldgen.features.AquaticFeatures
+ XXX.worldgen.features.CaveFeatures
- XXX.worldgen.features.EndFeatures
+ XXX.worldgen.features.FeatureUtils
- XXX.worldgen.features.MiscOverworldFeatures
+ XXX.worldgen.features.NetherFeatures
- XXX.worldgen.features.OreFeatures
- XXX.worldgen.features.package-info
+ XXX.worldgen.features.PileFeatures
- XXX.worldgen.features.TreeFeatures
+ XXX.worldgen.features.VegetationFeatures
- XXX.worldgen.placement.AquaticPlacements
+ XXX.worldgen.placement.CavePlacements
- XXX.worldgen.placement.EndPlacements
+ XXX.worldgen.placement.MiscOverworldPlacements
- XXX.worldgen.placement.NetherPlacements
+ XXX.worldgen.placement.OrePlacements
- XXX.worldgen.placement.package-info
- XXX.worldgen.placement.PlacementUtils
+ XXX.worldgen.placement.TreePlacements
- XXX.worldgen.placement.VegetationPlacements
+ XXX.worldgen.placement.VillagePlacements
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.blaze3d.platform.NativeImage +1M -1M
```
```
XXX.mojang.realmsclient.RealmsMainScreen -1M
```
```
XXX.gui.screens.RealmsBrokenWorldScreen -1M
```
```
XXX.gui.screens.RealmsConfigureWorldScreen -1M
```
```
XXX.gui.screens.RealmsPlayerScreen -1M
```
```
XXX.gui.screens.RealmsResetNormalWorldScreen -1M
```
```
XXX.gui.screens.RealmsSelectFileToUploadScreen -1M
```
```
XXX.gui.screens.RealmsSlotOptionsScreen -1M
```
```
XXX.gui.screens.RealmsSubscriptionInfoScreen -1M
```
```
XXX.gui.screens.RealmsTermsScreen -1M
```
```
net.minecraft.SharedConstants +1P
```
```
XXX.screens.worldselection.WorldGenSettingsComponent +2M -2M | +1P -1P
```
```
XXX.client.model.FrogModel +1P
```
```
XXX.resources.model.ModelManager +20M -28M
```
```
XXX.minecraft.core.UUIDUtil +3M -2M | +1P
```
```
XXX.server.level.ChunkMap +1M
```
```
XXX.server.level.ServerLevel +4M -1M
```
```
XXX.world.effect.MobEffectInstance -2M | -1P
```
```
XXX.world.item.CreativeModeTab +2M -2M | +2P -2P
```
```
XXX.world.item.CreativeModeTab$ItemDisplayBuilder -2M | +2P -2P
```
```
XXX.world.item.ItemStackLinkedSet +2M | +1P -1P
```
```
XXX.world.level.Level +3M -1M
```
```
XXX.level.block.BedBlock +1M -1M
```
```
XXX.level.block.Blocks +2P
```
```
XXX.level.block.ChiseledBookShelfBlock +6M -3M | +3P -2P
```
```
XXX.block.entity.ChiseledBookShelfBlockEntity +5M -13M | +1P -1P
```
```
XXX.block.entity.SkullBlockEntity +2M -2M | +2P -2P
```
```
XXX.state.properties.BlockStateProperties +7P -2P
```
```
XXX.level.entity.EntityLookup +1M -1M
```
```
XXX.level.entity.EntitySection +2M -2M
```
```
XXX.level.entity.LevelEntityGetter +2P -2P
```

</details>
<details>
<summary>
com.mojang.blaze3d.platform.NativeImage
</summary>

```diff
- void copyRect(NativeImage,int,int,int,int,int,int,boolean,boolean)
+ void writeToFile(String)
```

</details>
<details>
<summary>
com.mojang.realmsclient.RealmsMainScreen
</summary>

```diff
+ void removed()
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsBrokenWorldScreen
</summary>

```diff
+ void removed()
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsConfigureWorldScreen
</summary>

```diff
+ void removed()
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsPlayerScreen
</summary>

```diff
+ void removed()
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsResetNormalWorldScreen
</summary>

```diff
+ void removed()
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsSelectFileToUploadScreen
</summary>

```diff
+ void removed()
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsSlotOptionsScreen
</summary>

```diff
+ void removed()
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsSubscriptionInfoScreen
</summary>

```diff
+ void removed()
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsTermsScreen
</summary>

```diff
+ void removed()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.worldselection.WorldGenSettingsComponent
</summary>

```diff
- String toString(OptionalLong)
+ void <init>(WorldCreationContext,Optional,long)
- void <init>(WorldCreationContext,Optional,OptionalLong)
+ void <init>(WorldCreationContext,Optional)
```

</details>
<details>
<summary>
net.minecraft.client.resources.model.ModelManager
</summary>

```diff
+ AtlasSet$StitchResult lambda$reload$10(Map$Entry)
- AtlasSet$StitchResult lambda$reload$2(Map$Entry)
- CompletableFuture[] lambda$loadModels$19(int)
+ CompletableFuture[] lambda$loadModels$27(int)
- CompletableFuture[] lambda$reload$1(int)
+ CompletableFuture[] lambda$reload$9(int)
- CompletionStage lambda$loadBlockModels$10(Executor,Map)
+ CompletionStage lambda$loadBlockModels$18(Executor,Map)
- CompletionStage lambda$loadBlockStates$14(Executor,Map)
+ CompletionStage lambda$loadBlockStates$22(Executor,Map)
+ CompletionStage lambda$reload$13(ModelManager$ReloadState)
- CompletionStage lambda$reload$5(ModelManager$ReloadState)
+ Map lambda$loadBlockModels$15(ResourceManager)
+ Map lambda$loadBlockModels$17(List)
- Map lambda$loadBlockModels$7(ResourceManager)
- Map lambda$loadBlockModels$9(List)
- Map lambda$loadBlockStates$11(ResourceManager)
- Map lambda$loadBlockStates$13(List)
+ Map lambda$loadBlockStates$19(ResourceManager)
+ Map lambda$loadBlockStates$21(List)
+ Map lambda$static$0(ResourceManager)
+ Map lambda$static$1(ResourceManager)
+ Map lambda$static$2(ResourceManager)
+ Map lambda$static$3(ResourceManager)
+ Map lambda$static$4(ResourceManager)
+ Map lambda$static$5(ResourceManager)
+ Map lambda$static$6(ResourceManager)
+ Map lambda$static$7(ResourceManager)
- ModelBakery lambda$reload$0(ProfilerFiller,Map,Map)
+ ModelBakery lambda$reload$8(ProfilerFiller,Map,Map)
+ ModelManager$ReloadState lambda$reload$11(ProfilerFiller,Map,CompletableFuture,Void)
+ ModelManager$ReloadState lambda$reload$12(ModelManager$ReloadState,Void)
- ModelManager$ReloadState lambda$reload$3(ProfilerFiller,Map,CompletableFuture,Void)
- ModelManager$ReloadState lambda$reload$4(ModelManager$ReloadState,Void)
+ Pair lambda$loadBlockModels$16(Map$Entry)
- Pair lambda$loadBlockModels$8(Map$Entry)
- Pair lambda$loadBlockStates$12(Map$Entry)
+ Pair lambda$loadBlockStates$20(Map$Entry)
- String lambda$loadModels$16(Material)
+ String lambda$loadModels$24(Material)
- TextureAtlasSprite lambda$loadModels$15(Map,Multimap,ResourceLocation,Material)
+ TextureAtlasSprite lambda$loadModels$23(Map,Multimap,ResourceLocation,Material)
- void lambda$loadModels$17(ResourceLocation,Collection)
- void lambda$loadModels$18(Map,BakedModel,Map,BlockState)
+ void lambda$loadModels$25(ResourceLocation,Collection)
+ void lambda$loadModels$26(Map,BakedModel,Map,BlockState)
+ void lambda$reload$14(ProfilerFiller,ModelManager$ReloadState)
- void lambda$reload$6(ProfilerFiller,ModelManager$ReloadState)
```

</details>
<details>
<summary>
net.minecraft.core.UUIDUtil
</summary>

```diff
- DataResult lambda$static$3(String)
+ UUID lambda$static$3(UUID)
+ UUID lambda$static$5(Either)
- UUID lambda$static$5(UUID)
- UUID lambda$static$6(Either)
```

</details>
<details>
<summary>
net.minecraft.server.level.ChunkMap
</summary>

```diff
- void resendChunk(ChunkAccess)
```

</details>
<details>
<summary>
net.minecraft.server.level.ServerLevel
</summary>

```diff
- AbortableIterationConsumer$Continuation lambda$getEntities$11(Predicate,List,int,Entity)
- List getPlayers(Predicate,int)
- void getEntities(EntityTypeTest,Predicate,List,int)
- void getEntities(EntityTypeTest,Predicate,List)
+ void lambda$getEntities$11(Predicate,List,Entity)
```

</details>
<details>
<summary>
net.minecraft.world.effect.MobEffectInstance
</summary>

```diff
+ boolean isNoCounter()
+ void setNoCounter(boolean)
```

</details>
<details>
<summary>
net.minecraft.world.item.CreativeModeTab
</summary>

```diff
- Collection getDisplayItems()
- Collection getSearchTabDisplayItems()
+ ItemStackLinkedSet getDisplayItems()
+ ItemStackLinkedSet getSearchTabDisplayItems()
```

</details>
<details>
<summary>
net.minecraft.world.item.CreativeModeTab$ItemDisplayBuilder
</summary>

```diff
+ ItemStackLinkedSet getSearchTabContents()
+ ItemStackLinkedSet getTabContents()
```

</details>
<details>
<summary>
net.minecraft.world.item.ItemStackLinkedSet
</summary>

```diff
- int hashStackAndTag(ItemStack)
- Set createTypeAndTagSet()
```

</details>
<details>
<summary>
net.minecraft.world.level.Level
</summary>

```diff
- AbortableIterationConsumer$Continuation lambda$getEntities$2(Predicate,List,int,EntityTypeTest,Entity)
- void getEntities(EntityTypeTest,AABB,Predicate,List,int)
- void getEntities(EntityTypeTest,AABB,Predicate,List)
+ void lambda$getEntities$2(Predicate,List,EntityTypeTest,Entity)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BedBlock
</summary>

```diff
- Optional findStandUpPosition(EntityType,CollisionGetter,BlockPos,Direction,float)
+ Optional findStandUpPosition(EntityType,CollisionGetter,BlockPos,float)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.ChiseledBookShelfBlock
</summary>

```diff
- int getHitSlot(Vec2)
- int getSection(float)
- InteractionResult tryAddBook(Level,BlockPos,Player,ChiseledBookShelfBlockEntity,ItemStack,int)
+ InteractionResult tryAddBook(Level,BlockPos,Player,ChiseledBookShelfBlockEntity,ItemStack)
- InteractionResult tryRemoveBook(Level,BlockPos,Player,ChiseledBookShelfBlockEntity,int)
+ InteractionResult tryRemoveBook(Level,BlockPos,Player,ChiseledBookShelfBlockEntity)
- Optional getRelativeHitCoordinatesForBlockFace(BlockHitResult,Direction)
- void lambda$createBlockStateDefinition$0(StateDefinition$Builder,Property)
+ void lambda$onRemove$0(Level,BlockPos,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.ChiseledBookShelfBlockEntity
</summary>

```diff
+ boolean addBook(ItemStack)
+ boolean hasAnyMatching(Predicate)
+ boolean hasAnyOf(Set)
+ boolean isFull()
+ boolean lambda$countItem$0(Item,ItemStack)
+ boolean lambda$hasAnyOf$1(Set,ItemStack)
- ClientboundBlockEntityDataPacket getUpdatePacket()
- CompoundTag getUpdateTag()
+ int bookCount()
- int count()
+ int countItem(Item)
+ ItemStack removeBook()
+ List removeAllBooksWithoutBlockStateUpdate()
+ NonNullList asNonNullList(StackInventory)
- Packet getUpdatePacket()
+ void setChanged()
+ void updateBlockState()
- void updateState(int)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.SkullBlockEntity
</summary>

```diff
- float getAnimation(float)
+ float getMouthAnimation(float)
- void animation(Level,BlockPos,BlockState,SkullBlockEntity)
+ void dragonHeadAnimation(Level,BlockPos,BlockState,SkullBlockEntity)
```

</details>
<details>
<summary>
net.minecraft.world.level.entity.EntityLookup
</summary>

```diff
- void getEntities(EntityTypeTest,AbortableIterationConsumer)
+ void getEntities(EntityTypeTest,Consumer)
```

</details>
<details>
<summary>
net.minecraft.world.level.entity.EntitySection
</summary>

```diff
- AbortableIterationConsumer$Continuation getEntities(AABB,AbortableIterationConsumer)
- AbortableIterationConsumer$Continuation getEntities(EntityTypeTest,AABB,AbortableIterationConsumer)
+ void getEntities(AABB,Consumer)
+ void getEntities(EntityTypeTest,AABB,Consumer)
```

</details>
</details>
<hr/>