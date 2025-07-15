## Comparison with [20w27a](https://github.com/PixiGeko/Minecraft-generated-data/tree/20w27a)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Recipes](#recipes)
> - [Translations](#translations)
> - [File structure](#file-structure)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">20w27a</th><th>20w28a</th></tr><tr><td>World version</td><td><pre>2569</pre></td><td><pre>2570</pre></td></tr><tr><td>Protocol version</td><td><pre>738</pre></td><td><pre>740</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">20w27a</th><th>20w28a</th></tr><tr><td>com.mojang:datafixerupper</td><td><pre>3.0.25</pre></td><td><pre>4.0.26</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr></table>
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
- biome_source.txt
- biome.txt
- block_placer_type.txt
- block_state_provider_type.txt
- carver.txt
- chunk_generator.txt
- decorator.txt
- feature_size_type.txt
- feature.txt
- foliage_placer_type.txt
- structure_feature.txt
- structure_piece.txt
- structure_pool_element.txt
- structure_processor.txt
- surface_builder.txt
- tree_decorator_type.txt
- trunk_placer_type.txt
+ worldgen/biome_source.txt
+ worldgen/block_placer_type.txt
+ worldgen/block_state_provider_type.txt
+ worldgen/carver.txt
+ worldgen/chunk_generator.txt
+ worldgen/decorator.txt
+ worldgen/feature_size_type.txt
+ worldgen/feature.txt
+ worldgen/foliage_placer_type.txt
+ worldgen/structure_feature.txt
+ worldgen/structure_piece.txt
+ worldgen/structure_pool_element.txt
+ worldgen/structure_processor.txt
+ worldgen/surface_builder.txt
+ worldgen/tree_decorator_type.txt
+ worldgen/trunk_placer_type.txt
```

</details>
<details>
<summary>
memory_module_type
</summary>

```diff
+ minecraft:disable_walk_to_admire_item
+ minecraft:time_trying_to_reach_admire_item
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
- universal_tags/biome_source.json
- universal_tags/biome.json
- universal_tags/block_placer_type.json
- universal_tags/block_state_provider_type.json
- universal_tags/carver.json
- universal_tags/chunk_generator.json
- universal_tags/decorator.json
- universal_tags/feature_size_type.json
- universal_tags/feature.json
- universal_tags/foliage_placer_type.json
- universal_tags/structure_feature.json
- universal_tags/structure_piece.json
- universal_tags/structure_pool_element.json
- universal_tags/structure_processor.json
- universal_tags/surface_builder.json
- universal_tags/tree_decorator_type.json
- universal_tags/trunk_placer_type.json
+ universal_tags/worldgen/biome_source.json
+ universal_tags/worldgen/block_placer_type.json
+ universal_tags/worldgen/block_state_provider_type.json
+ universal_tags/worldgen/carver.json
+ universal_tags/worldgen/chunk_generator.json
+ universal_tags/worldgen/decorator.json
+ universal_tags/worldgen/feature_size_type.json
+ universal_tags/worldgen/feature.json
+ universal_tags/worldgen/foliage_placer_type.json
+ universal_tags/worldgen/structure_feature.json
+ universal_tags/worldgen/structure_piece.json
+ universal_tags/worldgen/structure_pool_element.json
+ universal_tags/worldgen/structure_processor.json
+ universal_tags/worldgen/surface_builder.json
+ universal_tags/worldgen/tree_decorator_type.json
+ universal_tags/worldgen/trunk_placer_type.json
```

</details>
<details>
<summary>
universal_tags/memory_module_type.json
</summary>

```diff
+ minecraft:disable_walk_to_admire_item
+ minecraft:time_trying_to_reach_admire_item
```

</details>
</details>
<hr/>
<details><summary><b><ins>RECIPES</ins></b><a name="recipes"></a></summary>
<br/>
<details>
<summary>
brewing_stand.json
</summary>

```
A: #stone_crafting_materials
B: blaze_rod
C: cobblestone

Previous pattern:
[  | B |  ]
[C | C | C]

New pattern:
[  | B |  ]
[A | A | A]
```

</details>
<details>
<summary>
furnace.json
</summary>

```
A: #furnace_materials
B: #stone_crafting_materials

Previous pattern:
[A | A | A]
[A |   | A]
[A | A | A]

New pattern:
[B | B | B]
[B |   | B]
[B | B | B]
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
+ chat.square_brackets: [%s]
+ command.context.parse_error: %s at position %s: %s
+ commands.list.nameAndId: %s (%s)
+ disconnect.exceeded_packet_rate: Kicked for exceeding packet rate limit
- options.entityDistancePercent: %s%%
+ options.generic_value: %s: %s
+ options.off.composed: %s: OFF
+ options.on.composed: %s: ON
+ options.percent_add_value: %s: +%s%%
+ options.percent_value: %s: %s%%
+ options.pixel_value: %s: %spx
+ potion.withAmplifier: %s %s
+ potion.withDuration: %s (%s)
- selectWorld.hardcoreMode: Hardcore:
- selectWorld.hardcoreMode.info: World is deleted upon death
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>20w27a</th><th>20w28a</th></tr>
<tr><th align="left"><div style="width:290px">selectWorld.mapFeatures</div></th><td>Generate Structures:</td><td>Generate Structures</td></tr>
<tr><th align="left"><div style="width:290px">selectWorld.allowCommands</div></th><td>Allow Cheats:</td><td>Allow Cheats</td></tr>
<tr><th align="left"><div style="width:290px">selectWorld.bonusItems</div></th><td>Bonus Chest:</td><td>Bonus Chest</td></tr>
<tr><th align="left"><div style="width:290px">jigsaw_block.keep_jigsaws</div></th><td>Keep Jigsaws: </td><td>Keep Jigsaws</td></tr>
<tr><th align="left"><div style="width:290px">gamerule.doDaylightCycle</div></th><td>Advance in-game time</td><td>Advance time of day</td></tr>
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
+ minecraft/tags/blocks/base_stone_nether.json
+ minecraft/tags/blocks/base_stone_overworld.json
- minecraft/tags/items/furnace_materials.json
+ minecraft/tags/items/stone_crafting_materials.json
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
- net.minecraft.BlockUtil$FoundRectangle
- net.minecraft.CharPredicate
+ net.minecraft.package-info
- net.minecraft.Util$4
- net.minecraft.Util$6
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
- XXX.block.entity.JigsawBlockEntity$JointType
+ XXX.block.entity.JigsawBlockEntity$RuntimePiece
- XXX.chunk.storage.ChunkSerializer
+ XXX.chunk.storage.ChunkStorage
- XXX.chunk.storage.IOWorker
+ XXX.chunk.storage.IOWorker$PendingStore
- XXX.chunk.storage.IOWorker$Priority
+ XXX.chunk.storage.OldChunkStorage
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
+ XXX.data.models.BlockModelGenerators
- XXX.data.models.BlockModelGenerators$1
+ XXX.data.models.BlockModelGenerators$BlockEntityModelGenerator
- XXX.data.models.BlockModelGenerators$BlockFamilyProvider
+ XXX.data.models.BlockModelGenerators$TintState
- XXX.data.models.BlockModelGenerators$WoodProvider
+ XXX.data.models.ItemModelGenerators
- XXX.data.models.ModelProvider
- XXX.data.models.package-info
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
- XXX.data.recipes.UpgradeRecipeBuilder
+ XXX.data.recipes.UpgradeRecipeBuilder$Result
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
- XXX.data.tags.TagsProvider$1
+ XXX.data.tags.TagsProvider$TagAppender
- XXX.data.worldgen.BastionHoglinStablePools
- XXX.data.worldgen.BastionPieces
- XXX.data.worldgen.BastionTreasureRoomPools
- XXX.data.worldgen.Carvers
- XXX.data.worldgen.Features
- XXX.data.worldgen.Features$Decorators
- XXX.data.worldgen.PillagerOutpostPools
- XXX.data.worldgen.Pools
- XXX.data.worldgen.SavannaVillagePools
- XXX.data.worldgen.StructureFeatures
- XXX.data.worldgen.TaigaVillagePools
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
- XXX.datafix.fixes.PlayerUUIDFix
+ XXX.datafix.fixes.PoiTypeRename
- XXX.datafix.fixes.RecipesFix
+ XXX.datafix.fixes.RecipesRenameFix
- XXX.datafix.fixes.RecipesRenameningFix
+ XXX.datafix.fixes.RedstoneWireConnectionsFix
- XXX.datafix.fixes.References
- XXX.dimension.end.DragonRespawnAnimation
+ XXX.dimension.end.DragonRespawnAnimation$1
- XXX.dimension.end.DragonRespawnAnimation$2
+ XXX.dimension.end.DragonRespawnAnimation$3
- XXX.dimension.end.DragonRespawnAnimation$4
+ XXX.dimension.end.DragonRespawnAnimation$5
- XXX.dimension.end.EndDragonFight
+ XXX.dimension.end.package-info
+ XXX.entity.monster.Strider$StriderGroupData
- XXX.entity.npc.AbstractVillager
+ XXX.entity.npc.CatSpawner
- XXX.entity.npc.ClientSideMerchant
+ XXX.entity.npc.InventoryCarrier
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
+ XXX.entity.projectile.FishingHook
- XXX.entity.projectile.FishingHook$1
+ XXX.entity.projectile.FishingHook$FishHookState
- XXX.entity.projectile.FishingHook$OpenWaterType
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
+ XXX.entity.vehicle.DismountHelper
- XXX.entity.vehicle.Minecart
+ XXX.entity.vehicle.MinecartChest
- XXX.entity.vehicle.MinecartCommandBlock
+ XXX.entity.vehicle.MinecartCommandBlock$MinecartCommandBase
- XXX.entity.vehicle.MinecartFurnace
+ XXX.entity.vehicle.MinecartHopper
- XXX.entity.vehicle.MinecartSpawner
+ XXX.entity.vehicle.MinecartSpawner$1
- XXX.entity.vehicle.MinecartTNT
+ XXX.entity.vehicle.package-info
- XXX.feature.blockplacers.BlockPlacer
+ XXX.feature.blockplacers.BlockPlacerType
- XXX.feature.blockplacers.ColumnPlacer
+ XXX.feature.blockplacers.DoublePlantPlacer
+ XXX.feature.blockplacers.package-info
- XXX.feature.blockplacers.SimpleBlockPlacer
+ XXX.feature.configurations.BuriedTreasureConfiguration
+ XXX.feature.configurations.CountFeatureConfiguration
+ XXX.feature.configurations.DiskConfiguration
- XXX.feature.configurations.EndGatewayConfiguration
+ XXX.feature.configurations.FeatureConfiguration
+ XXX.feature.configurations.MultiJigsawConfiguration
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
- XXX.feature.configurations.RangeDecoratorConfiguration
+ XXX.feature.configurations.ReplaceBlockConfiguration
- XXX.feature.configurations.ReplaceSphereConfiguration
+ XXX.feature.configurations.ReplaceSpheroidConfiguration$Builder
+ XXX.feature.configurations.SeagrassFeatureConfiguration
- XXX.feature.configurations.ShipwreckConfiguration
+ XXX.feature.configurations.SimpleBlockConfiguration
- XXX.feature.configurations.SimpleRandomFeatureConfiguration
+ XXX.feature.configurations.SpikeConfiguration
- XXX.feature.configurations.SpringConfiguration
+ XXX.feature.configurations.StrongholdConfiguration
- XXX.feature.configurations.StructureFeatureConfiguration
+ XXX.feature.configurations.TreeConfiguration
- XXX.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
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
+ XXX.feature.foliageplacers.FoliagePlacer$Factory
- XXX.feature.foliageplacers.FoliagePlacer$FoliageAttachment
+ XXX.feature.foliageplacers.FoliagePlacerType
- XXX.feature.foliageplacers.MegaJungleFoliagePlacer
+ XXX.feature.foliageplacers.MegaPineFoliagePlacer
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
- XXX.feature.structures.LegacySinglePoolElement
+ XXX.feature.structures.ListPoolElement
- XXX.feature.structures.SinglePoolElement
+ XXX.feature.structures.StructurePoolElement
- XXX.feature.structures.StructurePoolElementType
+ XXX.feature.structures.StructureTemplatePool
- XXX.feature.structures.StructureTemplatePool$Projection
+ XXX.feature.structures.StructureTemplatePools
+ XXX.gametest.framework.BeforeBatch
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
+ XXX.gametest.framework.JUnitLikeTestReporter
- XXX.gametest.framework.LogTestReporter
+ XXX.gametest.framework.MultipleTestTracker
- XXX.gametest.framework.MultipleTestTracker$1
- XXX.gametest.framework.package-info
+ XXX.gametest.framework.StructureUtils
- XXX.gametest.framework.StructureUtils$1
+ XXX.gametest.framework.TeamcityTestReporter
- XXX.gametest.framework.TestClassNameArgument
+ XXX.gametest.framework.TestCommand
- XXX.gametest.framework.TestCommand$TestSummaryDisplayer
+ XXX.gametest.framework.TestFunction
- XXX.gametest.framework.TestFunctionArgument
+ XXX.gametest.framework.TestReporter
- XXX.item.alchemy.package-info
+ XXX.item.alchemy.Potion
- XXX.item.alchemy.PotionBrewing
+ XXX.item.alchemy.PotionBrewing$Mix
+ XXX.item.alchemy.Potions
- XXX.item.alchemy.PotionUtils
- XXX.item.context.DirectionalPlaceContext
- XXX.item.context.UseOnContext
+ XXX.level.biome.BadlandsPlateauBiome
+ XXX.level.biome.BambooJungleHillsBiome
+ XXX.level.biome.BeachBiome
+ XXX.level.biome.BiomeDefaultFeatures
- XXX.level.biome.BiomeManager
+ XXX.level.biome.BiomeManager$NoiseBiomeSource
+ XXX.level.biome.Biomes
- XXX.level.biome.BiomeSource
+ XXX.level.biome.BiomeSpecialEffects
- XXX.level.biome.BiomeSpecialEffects$1
+ XXX.level.biome.BiomeSpecialEffects$Builder
- XXX.level.biome.BiomeZoomer
+ XXX.level.biome.BirchForestHillsBiome
- XXX.level.biome.CheckerboardColumnBiomeSource
+ XXX.level.biome.ColdOceanBiome
+ XXX.level.biome.DarkForestBiome
+ XXX.level.biome.DeepColdOceanBiome
+ XXX.level.biome.DeepLukeWarmOceanBiome
+ XXX.level.biome.DeepWarmOceanBiome
+ XXX.level.biome.DesertHillsBiome
+ XXX.level.biome.EndBarrensBiome
+ XXX.level.biome.EndMidlandsBiome
+ XXX.level.biome.FixedBiomeSource
+ XXX.level.biome.ForestFlowerBiome
+ XXX.level.biome.FrozenRiverBiome
- XXX.level.biome.FuzzyOffsetBiomeZoomer
+ XXX.level.biome.FuzzyOffsetConstantColumnBiomeZoomer
+ XXX.level.biome.GiantSpruceTaigaHillsMutatedBiome
+ XXX.level.biome.GiantTreeTaigaHillsBiome
+ XXX.level.biome.IceSpikesBiome
+ XXX.level.biome.JungleEdgeBiome
+ XXX.level.biome.LukeWarmOceanBiome
+ XXX.level.biome.ModifiedGravellyMountainsBiome
+ XXX.level.biome.ModifiedJungleEdgeBiome
+ XXX.level.biome.MountainBiome
+ XXX.level.biome.MushroomFieldsBiome
+ XXX.level.biome.OceanBiome
+ XXX.level.biome.PlainsBiome
+ XXX.level.biome.SavannaBiome
+ XXX.level.biome.ShatteredSavannaBiome
+ XXX.level.biome.SmallEndIslandsBiome
+ XXX.level.biome.SnowyMountainsBiome
+ XXX.level.biome.SnowyTaigaHillsBiome
+ XXX.level.biome.SnowyTundraBiome
+ XXX.level.biome.StoneShoreBiome
+ XXX.level.biome.SwampBiome
+ XXX.level.biome.TaigaBiome
+ XXX.level.biome.TaigaMountainsBiome
+ XXX.level.biome.TallBirchHillsBiome
+ XXX.level.biome.WarmOceanBiome
+ XXX.level.biome.WoodedBadlandsBiome
+ XXX.level.biome.WoodedMountainBiome
+ XXX.level.block.NetherPortalBlock$PortalShape
+ XXX.level.block.NetherrackBlock
- XXX.level.block.NetherSproutsBlock
+ XXX.level.block.NetherVines
- XXX.level.block.NetherWartBlock
- XXX.level.block.NoteBlock
+ XXX.level.block.NyliumBlock
- XXX.level.block.ObserverBlock
+ XXX.level.block.OreBlock
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
- XXX.level.block.RespawnAnchorBlock
+ XXX.level.block.RespawnAnchorBlock$1
- XXX.level.block.RootsBlock
+ XXX.level.block.RotatedPillarBlock
- XXX.level.block.RotatedPillarBlock$1
+ XXX.level.block.Rotation
- XXX.level.block.Rotation$1
+ XXX.level.block.SandBlock
- XXX.level.block.SaplingBlock
+ XXX.level.block.ScaffoldingBlock
+ XXX.level.block.Seagrass
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
- XXX.level.block.SupportType
- XXX.level.block.SupportType$2
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
+ XXX.level.block.TwistingVines
- XXX.level.block.TwistingVinesPlant
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
- XXX.level.border.package-info
- XXX.level.border.WorldBorder
+ XXX.level.border.WorldBorder$1
- XXX.level.border.WorldBorder$BorderExtent
+ XXX.level.border.WorldBorder$MovingBorderExtent
- XXX.level.border.WorldBorder$Settings
+ XXX.level.border.WorldBorder$StaticBorderExtent
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
- XXX.level.dimension.DimensionType
+ XXX.level.dimension.LevelStem
- XXX.level.dimension.package-info
+ XXX.level.levelgen.DebugLevelSource
- XXX.level.levelgen.Decoratable
- XXX.level.portal.package-info
- XXX.level.portal.PortalInfo
- XXX.level.progress.ChunkProgressListener
+ XXX.level.progress.ChunkProgressListenerFactory
- XXX.level.progress.LoggerChunkProgressListener
+ XXX.level.progress.package-info
+ XXX.level.progress.ProcessorChunkProgressListener
- XXX.level.progress.StoringChunkProgressListener
+ XXX.levelgen.feature.BastionHoglinStablePools
+ XXX.levelgen.feature.BastionPieces
+ XXX.levelgen.feature.BastionSharedPools
+ XXX.levelgen.feature.BlockBlobFeature
- XXX.levelgen.feature.BlockPileFeature
+ XXX.levelgen.feature.BlueIceFeature
- XXX.levelgen.feature.BonusChestFeature
+ XXX.levelgen.feature.BuriedTreasureFeature
- XXX.levelgen.feature.BuriedTreasureFeature$BuriedTreasureStart
+ XXX.levelgen.feature.ChorusPlantFeature
- XXX.levelgen.feature.ConfiguredFeature
+ XXX.levelgen.feature.ConfiguredStructureFeature
- XXX.levelgen.feature.CoralClawFeature
+ XXX.levelgen.feature.CoralFeature
- XXX.levelgen.feature.CoralMushroomFeature
+ XXX.levelgen.feature.CoralTreeFeature
- XXX.levelgen.feature.DecoratedFeature
+ XXX.levelgen.feature.DecoratedFlowerFeature
- XXX.levelgen.feature.DefaultFlowerFeature
+ XXX.levelgen.feature.DeltaFeature
- XXX.levelgen.feature.DesertPyramidFeature
+ XXX.levelgen.feature.DesertPyramidFeature$FeatureStart
- XXX.levelgen.feature.JigsawFeature
+ XXX.levelgen.feature.package-info
+ XXX.levelgen.feature.PlainVillagePools
+ XXX.levelgen.feature.RandomSelectorFeature
- XXX.levelgen.feature.ReplaceBlobsFeature
+ XXX.levelgen.feature.ReplaceBlockFeature
- XXX.levelgen.feature.RuinedPortalFeature
+ XXX.levelgen.feature.RuinedPortalFeature$FeatureStart
- XXX.levelgen.feature.RuinedPortalFeature$Type
+ XXX.levelgen.feature.SavannaVillagePools
+ XXX.levelgen.feature.SpikeFeature
- XXX.levelgen.feature.SpikeFeature$1
+ XXX.levelgen.feature.SpikeFeature$EndSpike
- XXX.levelgen.feature.SpikeFeature$SpikeCacheLoader
+ XXX.levelgen.feature.SpringFeature
- XXX.levelgen.feature.StrongholdFeature
+ XXX.levelgen.feature.StrongholdFeature$StrongholdStart
- XXX.levelgen.feature.StructureFeature
+ XXX.levelgen.feature.StructureFeature$StructureStartFactory
- XXX.levelgen.feature.StructurePieceType
+ XXX.levelgen.feature.SwamplandHutFeature
- XXX.levelgen.feature.SwamplandHutFeature$FeatureStart
+ XXX.levelgen.feature.TaigaVillagePools
+ XXX.levelgen.feature.VillageFeature$FeatureStart
+ XXX.levelgen.feature.VillagePieces$VillagePiece
- XXX.levelgen.feature.VinesFeature
+ XXX.levelgen.feature.VoidStartPlatformFeature
- XXX.levelgen.feature.WeepingVinesFeature
+ XXX.levelgen.feature.WeightedConfiguredFeature
- XXX.levelgen.feature.WoodlandMansionFeature
+ XXX.levelgen.feature.WoodlandMansionFeature$WoodlandMansionStart
- XXX.levelgen.placement.BiasedRangeDecorator
- XXX.levelgen.placement.ChanceDecoratorConfiguration
+ XXX.levelgen.placement.ChanceHeightmapDecorator
+ XXX.levelgen.placement.ChancePassthroughDecorator
+ XXX.levelgen.placement.ChorusPlantPlacementDecorator
+ XXX.levelgen.placement.CountBiasedRangeDecorator
+ XXX.levelgen.placement.CountChanceHeightmapDoubleDecorator
- XXX.levelgen.placement.CountDecorator
+ XXX.levelgen.placement.CountHeighmapDoubleDecorator
+ XXX.levelgen.placement.CountHeightmap32Decorator
+ XXX.levelgen.placement.CountTopSolidDecorator
- XXX.levelgen.placement.CountWithExtraChanceDecorator
+ XXX.levelgen.placement.CountWithExtraChanceHeightmapDecorator
- XXX.levelgen.placement.DecoratedDecorator
- XXX.levelgen.placement.DecorationContext
+ XXX.levelgen.placement.DepthAverageConfigation
- XXX.levelgen.placement.DepthAverageDecorator
- XXX.levelgen.placement.EmeraldPlacementDecorator
+ XXX.levelgen.placement.EndGatewayPlacementDecorator
- XXX.levelgen.placement.EndIslandPlacementDecorator
+ XXX.levelgen.placement.FeatureDecorator
+ XXX.levelgen.placement.FrequencyChanceDecoratorConfiguration
- XXX.levelgen.placement.HeightmapDecorator
- XXX.levelgen.placement.IcebergPlacementDecorator
+ XXX.levelgen.placement.LakeLavaPlacementDecorator
- XXX.levelgen.placement.LakeWaterPlacementDecorator
+ XXX.levelgen.placement.MonsterRoomPlacementDecorator
- XXX.levelgen.placement.NoiseCountFactorDecoratorConfiguration
+ XXX.levelgen.placement.NoiseHeightmap32Decorator
+ XXX.levelgen.placement.NopePlacementDecorator
- XXX.levelgen.placement.RangeDecorator
+ XXX.levelgen.placement.SimpleFeatureDecorator
- XXX.levelgen.placement.Spread32Decorator
- XXX.levelgen.placement.TopSolidHeightMapDecorator
+ XXX.levelgen.placement.TopSolidHeightMapNoiseBasedDecorator
+ XXX.levelgen.structure.PillagerOutpostPieces
- XXX.metadata.pack.package-info
- XXX.metadata.pack.PackMetadataSection
+ XXX.metadata.pack.PackMetadataSectionSerializer
- XXX.minecraft.core.BlockPos$5
+ XXX.minecraft.core.BlockPos$MutableBlockPos
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
+ XXX.minecraft.core.FrontAndTop
- XXX.minecraft.core.GlobalPos
+ XXX.minecraft.core.IdMap
- XXX.minecraft.core.IdMapper
+ XXX.minecraft.core.MappedRegistry
- XXX.minecraft.core.NonNullList
+ XXX.minecraft.core.Position
- XXX.minecraft.core.PositionImpl
+ XXX.minecraft.core.Registry
- XXX.minecraft.core.RegistryAccess
- XXX.minecraft.data.DataGenerator
+ XXX.minecraft.data.DataProvider
- XXX.minecraft.data.HashCache
+ XXX.minecraft.data.Main
+ XXX.minecraft.data.package-info
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
- XXX.minecraft.nbt.NbtOps$1
+ XXX.minecraft.nbt.NbtOps$NbtRecordBuilder
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
+ XXX.minecraft.network.PacketDecoder
- XXX.minecraft.network.PacketEncoder
+ XXX.minecraft.network.PacketListener
- XXX.minecraft.network.RateKickingConnection
- XXX.minecraft.obfuscate.DontObfuscateOrShrink
+ XXX.minecraft.obfuscate.KeepAfterObfuscation
- XXX.minecraft.obfuscate.package-info
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
- XXX.minecraft.tags.ItemTags
+ XXX.minecraft.tags.package-info
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
- XXX.minecraft.tags.Tag$TagEntry
+ XXX.minecraft.tags.TagCollection
- XXX.minecraft.tags.TagCollection$1
+ XXX.minecraft.tags.TagContainer
- XXX.minecraft.tags.TagContainer$1
+ XXX.minecraft.tags.TagLoader
- XXX.minecraft.tags.TagManager
- XXX.minecraft.util.BitStorage
+ XXX.minecraft.util.ClassInstanceMultiMap
+ XXX.minecraft.util.Codecs$1
+ XXX.minecraft.util.Codecs$3
- XXX.minecraft.util.Unit
+ XXX.minecraft.util.VisibleForDebug
- XXX.minecraft.util.WeighedRandom
+ XXX.minecraft.util.WeighedRandom$WeighedRandomItem
+ XXX.models.blockstates.BlockStateGenerator
- XXX.models.blockstates.Condition
+ XXX.models.blockstates.Condition$1
- XXX.models.blockstates.Condition$CompositeCondition
+ XXX.models.blockstates.Condition$Operation
- XXX.models.blockstates.Condition$TerminalCondition
+ XXX.models.blockstates.MultiPartGenerator
- XXX.models.blockstates.MultiPartGenerator$1
+ XXX.models.blockstates.MultiPartGenerator$ConditionalEntry
- XXX.models.blockstates.MultiPartGenerator$Entry
+ XXX.models.blockstates.MultiVariantGenerator
- XXX.models.blockstates.package-info
- XXX.models.blockstates.PropertyDispatch
+ XXX.models.blockstates.PropertyDispatch$1
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
+ XXX.monster.piglin.package-info
- XXX.monster.piglin.StopHoldingItemIfNoLongerAdmiring
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
+ XXX.placement.nether.ChanceRangeDecorator
- XXX.placement.nether.CountMultiLayerDecorator
+ XXX.placement.nether.FireDecorator
- XXX.placement.nether.GlowstoneDecorator
+ XXX.placement.nether.MagmaDecorator
+ XXX.protocol.game.ClientboundChunkBlocksUpdatePacket
- XXX.protocol.game.ClientboundSectionBlocksUpdatePacket
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
- XXX.protocol.game.ClientboundSetEquipmentPacket
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
+ XXX.state.properties.SlabType
- XXX.state.properties.StairsShape
+ XXX.state.properties.StructureMode
- XXX.state.properties.WallSide
+ XXX.state.properties.WoodType
+ XXX.util.datafix.DataFixers
- XXX.util.datafix.DataFixers$1
+ XXX.util.datafix.DataFixers$2
- XXX.util.datafix.DataFixTypes
- XXX.util.datafix.PackedBitStorage
+ XXX.world.entity.package-info
- XXX.world.food.FoodConstants
+ XXX.world.food.FoodData
- XXX.world.food.FoodProperties
+ XXX.world.food.FoodProperties$1
- XXX.world.food.FoodProperties$Builder
+ XXX.world.food.Foods
- XXX.world.food.package-info
+ XXX.world.inventory.AbstractContainerMenu
- XXX.world.inventory.AbstractFurnaceMenu
+ XXX.world.inventory.AnvilMenu
- XXX.world.inventory.AnvilMenu$1
+ XXX.world.inventory.BeaconMenu
- XXX.world.inventory.BeaconMenu$1
+ XXX.world.inventory.BeaconMenu$PaymentSlot
- XXX.world.inventory.BlastFurnaceMenu
+ XXX.world.inventory.BrewingStandMenu
- XXX.world.inventory.BrewingStandMenu$FuelSlot
+ XXX.world.inventory.BrewingStandMenu$IngredientsSlot
- XXX.world.inventory.BrewingStandMenu$PotionSlot
+ XXX.world.inventory.CartographyTableMenu
- XXX.world.inventory.CartographyTableMenu$1
+ XXX.world.inventory.CartographyTableMenu$2
- XXX.world.inventory.CartographyTableMenu$3
+ XXX.world.inventory.CartographyTableMenu$4
- XXX.world.inventory.CartographyTableMenu$5
+ XXX.world.inventory.ChestMenu
- XXX.world.inventory.ClickType
+ XXX.world.inventory.ContainerData
- XXX.world.inventory.ContainerLevelAccess
+ XXX.world.inventory.ContainerLevelAccess$1
- XXX.world.inventory.ContainerLevelAccess$2
+ XXX.world.inventory.ContainerListener
- XXX.world.inventory.CraftingContainer
+ XXX.world.inventory.CraftingMenu
- XXX.world.inventory.DataSlot
+ XXX.world.inventory.DataSlot$1
- XXX.world.inventory.DataSlot$2
+ XXX.world.inventory.DataSlot$3
- XXX.world.inventory.DispenserMenu
+ XXX.world.inventory.EnchantmentMenu
- XXX.world.inventory.EnchantmentMenu$1
+ XXX.world.inventory.EnchantmentMenu$2
- XXX.world.inventory.EnchantmentMenu$3
+ XXX.world.inventory.FurnaceFuelSlot
- XXX.world.inventory.FurnaceMenu
+ XXX.world.inventory.FurnaceResultSlot
- XXX.world.inventory.GrindstoneMenu
+ XXX.world.inventory.GrindstoneMenu$1
- XXX.world.inventory.GrindstoneMenu$2
+ XXX.world.inventory.GrindstoneMenu$3
- XXX.world.inventory.GrindstoneMenu$4
+ XXX.world.inventory.HopperMenu
- XXX.world.inventory.HorseInventoryMenu
+ XXX.world.inventory.HorseInventoryMenu$1
- XXX.world.inventory.HorseInventoryMenu$2
+ XXX.world.inventory.InventoryMenu
- XXX.world.inventory.InventoryMenu$1
+ XXX.world.inventory.InventoryMenu$2
- XXX.world.inventory.ItemCombinerMenu
+ XXX.world.inventory.ItemCombinerMenu$1
- XXX.world.inventory.ItemCombinerMenu$2
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
- XXX.world.inventory.RecipeBookType
+ XXX.world.inventory.RecipeHolder
- XXX.world.inventory.ResultContainer
+ XXX.world.inventory.ResultSlot
- XXX.world.inventory.ShulkerBoxMenu
+ XXX.world.inventory.ShulkerBoxSlot
- XXX.world.inventory.SimpleContainerData
+ XXX.world.inventory.Slot
- XXX.world.inventory.SmithingMenu
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
+ XXX.world.item.DirectionalPlaceContext$1
+ XXX.world.item.UseOnContext
- XXX.world.item.Vanishable
+ XXX.world.item.WaterLilyBlockItem
- XXX.world.item.Wearable
+ XXX.world.item.WritableBookItem
- XXX.world.item.WrittenBookItem
+ XXX.world.level.DefaultExplosionDamageCalculator
- XXX.world.level.EmptyBlockGetter
+ XXX.world.level.EmptyTickList
- XXX.world.level.EntityBasedExplosionDamageCalculator
+ XXX.world.level.EntityGetter
- XXX.world.level.Explosion
+ XXX.world.level.Explosion$BlockInteraction
- XXX.world.level.ExplosionDamageCalculator
+ XXX.world.level.FoliageColor
- XXX.world.level.ForcedChunksSavedData
+ XXX.world.level.GameRules
- XXX.world.level.GameRules$1
+ XXX.world.level.GameRules$BooleanValue
- XXX.world.level.GameRules$Category
+ XXX.world.level.GameRules$GameRuleTypeVisitor
- XXX.world.level.GameRules$IntegerValue
+ XXX.world.level.GameRules$Key
- XXX.world.level.GameRules$Type
+ XXX.world.level.GameRules$Value
- XXX.world.level.GameRules$VisitorCaller
+ XXX.world.level.GameType
- XXX.world.level.GrassColor
+ XXX.world.level.ItemLike
- XXX.world.level.Level
+ XXX.world.level.Level$1
- XXX.world.level.LevelAccessor
+ XXX.world.level.LevelReader
- XXX.world.level.LevelSettings
- XXX.world.level.LevelSimulatedReader
+ XXX.world.level.LevelSimulatedRW
+ XXX.world.level.LevelTimeAccess
- XXX.world.level.LevelWriter
+ XXX.world.level.LightLayer
- XXX.world.level.NaturalSpawner
+ XXX.world.level.NaturalSpawner$1
- XXX.world.level.NaturalSpawner$AfterSpawnCallback
+ XXX.world.level.NaturalSpawner$ChunkGetter
- XXX.world.level.NaturalSpawner$SpawnPredicate
+ XXX.world.level.NaturalSpawner$SpawnState
- XXX.world.level.NoiseColumn
+ XXX.world.level.PathNavigationRegion
- XXX.worldgen.biome.BadlandsBiome
- XXX.worldgen.biome.BambooJungleBiome
- XXX.worldgen.biome.BasaltDeltasBiome
- XXX.worldgen.biome.BirchForestBiome
- XXX.worldgen.biome.ColdOceanBiome
- XXX.worldgen.biome.DarkForestBiome
- XXX.worldgen.biome.DeepColdOceanBiome
- XXX.worldgen.biome.DeepLukeWarmOceanBiome
- XXX.worldgen.biome.DeepWarmOceanBiome
- XXX.worldgen.biome.DesertHillsBiome
- XXX.worldgen.biome.EndBarrensBiome
- XXX.worldgen.biome.EndMidlandsBiome
- XXX.worldgen.biome.ForestBiome
- XXX.worldgen.biome.FrozenOceanBiome
- XXX.worldgen.biome.GiantSpruceTaigaBiome
- XXX.worldgen.biome.GiantTreeTaigaBiome
- XXX.worldgen.biome.GravellyMountainsBiome
- XXX.worldgen.biome.JungleBiome
- XXX.worldgen.biome.JungleHillsBiome
- XXX.worldgen.biome.ModifiedBadlandsPlateauBiome
- XXX.worldgen.biome.ModifiedJungleBiome
- XXX.worldgen.biome.ModifiedWoodedBadlandsPlateauBiome
- XXX.worldgen.biome.MountainEdgeBiome
- XXX.worldgen.biome.MushroomFieldsShoreBiome
- XXX.worldgen.biome.OceanBiome
- XXX.worldgen.biome.RiverBiome
- XXX.worldgen.biome.SavannaPlateauBiome
- XXX.worldgen.biome.ShatteredSavannaPlateauBiome
- XXX.worldgen.biome.SnowyBeachBiome
- XXX.worldgen.biome.SnowyTaigaBiome
- XXX.worldgen.biome.SnowyTaigaMountainsBiome
- XXX.worldgen.biome.SoulSandValleyBiome
- XXX.worldgen.biome.SunflowerPlainsBiome
- XXX.worldgen.biome.SwampHillsBiome
- XXX.worldgen.biome.TaigaHillsBiome
- XXX.worldgen.biome.TallBirchForestBiome
- XXX.worldgen.biome.TheEndBiome
- XXX.worldgen.biome.WarmOceanBiome
- XXX.worldgen.biome.WoodedBadlandsBiome
- XXX.worldgen.biome.WoodedMountainBiome
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.minecraft.core.RegistryAccess$RegistryHolder +14M -4M | +2P -2P
```
```
XXX.minecraft.core.SectionPos +7M
```
```
XXX.network.chat.CommonComponents +1M
```
```
XXX.protocol.game.ClientGamePacketListener +1P -1P
```
```
XXX.protocol.game.ClientboundBlockUpdatePacket +1M
```
```
XXX.protocol.game.ClientboundLevelChunkPacket +1M -1M | +1P -1P
```
```
XXX.ai.behavior.AcquirePoi +5M -4M | +1P
```
```
XXX.ai.memory.MemoryModuleType +2P
```
```
XXX.entity.monster.EnderMan$EndermanLookForPlayerGoal +1M -1M
```
```
XXX.monster.piglin.Piglin -1M | -2P
```
```
XXX.world.item.BoneMealItem +1M -1M
```
```
XXX.world.item.EndCrystalItem +1M -1M
```
```
XXX.world.item.FireChargeItem +1M -1M
```
```
XXX.world.item.FlintAndSteelItem +3M -3M
```
```
XXX.world.item.GameMasterBlockItem +1M -1M
```
```
XXX.world.item.HoeItem +2M -2M
```
```
XXX.world.item.LeadItem +1M -1M
```
```
XXX.world.item.MapItem +2M -2M
```
```
XXX.world.item.MinecartItem +1M -1M
```
```
XXX.world.item.StandingAndWallBlockItem +1M -1M
```
```
XXX.world.level.BlockGetter +3M
```
```
XXX.level.biome.MultiNoiseBiomeSource +6M -3M
```
```
XXX.level.block.AbstractFurnaceBlock +1M -1M
```
```
XXX.level.block.AnvilBlock +1M -1M
```
```
XXX.level.block.BambooBlock +1M -1M
```
```
XXX.level.block.BannerBlock +1M -1M
```
```
XXX.level.block.BaseCoralWallFanBlock +1M -1M
```
```
XXX.level.block.BaseFireBlock +4M -3M
```
```
XXX.level.block.BaseRailBlock +1M -1M
```
```
XXX.level.block.BedBlock +1M -1M
```
```
XXX.level.block.BeehiveBlock +1M -1M
```
```
XXX.level.block.BellBlock +1M -1M
```
```
XXX.level.block.CarvedPumpkinBlock +1M -1M
```
```
XXX.level.block.ChainBlock +1M -1M
```
```
XXX.level.block.ChorusPlantBlock +1M -1M
```
```
XXX.level.block.ConduitBlock +1M -1M
```
```
XXX.level.block.DiodeBlock +1M -1M
```
```
XXX.level.block.DispenserBlock +1M -1M
```
```
XXX.level.block.EndRodBlock +1M -1M
```
```
XXX.level.block.EnderChestBlock +1M -1M
```
```
XXX.level.block.FaceAttachedHorizontalDirectionalBlock +1M -1M
```
```
XXX.level.block.FenceBlock +1M -1M
```
```
XXX.level.block.GrowingPlantBodyBlock +1M -1M
```
```
XXX.level.block.HugeMushroomBlock +1M -1M
```
```
XXX.level.block.JigsawBlock +1M -1M
```
```
XXX.level.block.KelpBlock +1M -1M
```
```
XXX.level.block.LadderBlock +1M -1M
```
```
XXX.level.block.Lantern +1M -1M
```
```
XXX.level.block.LecternBlock +1M -1M
```
```
XXX.level.block.NetherPortalBlock -3M
```
```
XXX.block.piston.PistonBaseBlock +1M -1M
```
```
XXX.block.state.BlockBehaviour +1M -1M
```
```
XXX.block.state.BlockBehaviour$BlockStateBase +2M -1M
```
```
XXX.state.pattern.BlockPattern$BlockPatternMatch -1M
```
```
XXX.level.levelgen.GenerationStep$Decoration +1M -5M | -3P
```
```
XXX.levelgen.carver.WorldCarver +1M -2M
```
```
XXX.levelgen.feature.BastionFeature +1M -2M
```
```
XXX.levelgen.feature.NetherFortressFeature$NetherBridgeStart +2M -2M
```
```
XXX.levelgen.feature.OceanMonumentFeature$OceanMonumentStart +2M -2M
```
```
XXX.levelgen.feature.PillagerOutpostFeature +1M -2M
```
```
XXX.levelgen.feature.SeagrassFeature +1M -1M
```
```
XXX.levelgen.feature.ShipwreckFeature$FeatureStart +2M -2M
```
```
XXX.feature.configurations.ColumnFeatureConfiguration +6M -6M | +2P -4P
```
```
XXX.feature.configurations.DecoratedFeatureConfiguration +2M -2M | +1P -1P
```
```
XXX.feature.configurations.DeltaFeatureConfiguration +8M -5M | +2P -3P
```
```
XXX.levelgen.structure.NetherFossilFeature$FeatureStart +2M -2M
```
```
XXX.levelgen.structure.OceanRuinFeature$OceanRuinStart +2M -2M
```
```
XXX.levelgen.structure.PoolElementStructurePiece +2M -2M
```
```
XXX.levelgen.structure.StructureStart$1 +2M -2M
```
```
XXX.structure.templatesystem.StructureProcessorType +3P -1P
```
```
XXX.levelgen.surfacebuilders.SurfaceBuilder +1M -2M | -3P
```
```
XXX.level.storage.McRegionUpgrader +2M -2M
```

</details>
<details>
<summary>
net.minecraft.core.RegistryAccess$RegistryHolder
</summary>

```diff
- boolean lambda$null$3(Map$Entry)
- Codec captureMap(UnboundedMapCodec)
- Codec lambda$null$1(ResourceKey,MapCodec)
- Codec makeDirectCodec()
- DataResult getCodec(ResourceKey)
- DataResult lambda$getCodec$5(RegistryAccess$RegistryData)
- DataResult lambda$getCodec$6(ResourceKey)
- DataResult lambda$makeDirectCodec$0(MappedRegistry)
- DataResult lambda$makeDirectCodec$2(ResourceKey)
- Map access$000(RegistryAccess$RegistryHolder)
- Map lambda$captureMap$4(RegistryAccess$RegistryHolder)
- MappedRegistry createRegistry(ResourceKey)
+ MappedRegistry lambda$static$0(RegistryAccess$RegistryHolder)
+ Registry dimensionTypes()
- void <init>(Map)
+ void <init>(MappedRegistry)
+ void registerDimension(ResourceKey,DimensionType)
- WritableRegistry lambda$registry$7(MappedRegistry)
```

</details>
<details>
<summary>
net.minecraft.core.SectionPos
</summary>

```diff
- BlockPos relativeToBlockPos(short)
- int relativeToBlockX(short)
- int relativeToBlockY(short)
- int relativeToBlockZ(short)
- int sectionRelativeX(short)
- int sectionRelativeY(short)
- int sectionRelativeZ(short)
```

</details>
<details>
<summary>
net.minecraft.network.chat.CommonComponents
</summary>

```diff
- MutableComponent optionStatus(Component,boolean)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundBlockUpdatePacket
</summary>

```diff
- void <init>(BlockPos,BlockState)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundLevelChunkPacket
</summary>

```diff
+ ChunkBiomeContainer getBiomes()
- int[] getBiomes()
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.behavior.AcquirePoi
</summary>

```diff
+ AcquirePoi$JitteredLinearRetry lambda$start$4(PathfinderMob,long,long)
- AcquirePoi$JitteredLinearRetry lambda$start$5(PathfinderMob,long,long)
- void <init>(PoiType,MemoryModuleType,boolean,Optional)
+ void <init>(PoiType,MemoryModuleType,boolean)
- void <init>(PoiType,MemoryModuleType,MemoryModuleType,boolean,Optional)
+ void <init>(PoiType,MemoryModuleType,MemoryModuleType,boolean)
- void lambda$null$3(ServerLevel,PathfinderMob,Byte)
+ void lambda$start$3(PoiManager,BlockPos,PathfinderMob,ServerLevel,PoiType)
- void lambda$start$4(PoiManager,BlockPos,PathfinderMob,ServerLevel,PoiType)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.EnderMan$EndermanLookForPlayerGoal
</summary>

```diff
- void <init>(EnderMan,Predicate)
+ void <init>(EnderMan)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.piglin.Piglin
</summary>

```diff
+ void sendDebugPackets()
```

</details>
<details>
<summary>
net.minecraft.world.item.BoneMealItem
</summary>

```diff
+ InteractionResult useOn(UseOnContext)
- InteractionResult useOn(UseOnContext)
```

</details>
<details>
<summary>
net.minecraft.world.item.EndCrystalItem
</summary>

```diff
+ InteractionResult useOn(UseOnContext)
- InteractionResult useOn(UseOnContext)
```

</details>
<details>
<summary>
net.minecraft.world.item.FireChargeItem
</summary>

```diff
+ InteractionResult useOn(UseOnContext)
- InteractionResult useOn(UseOnContext)
```

</details>
<details>
<summary>
net.minecraft.world.item.FlintAndSteelItem
</summary>

```diff
+ InteractionResult useOn(UseOnContext)
- InteractionResult useOn(UseOnContext)
+ void lambda$useOn$0(UseOnContext,Player)
- void lambda$useOn$0(UseOnContext,Player)
+ void lambda$useOn$1(UseOnContext,Player)
- void lambda$useOn$1(UseOnContext,Player)
```

</details>
<details>
<summary>
net.minecraft.world.item.GameMasterBlockItem
</summary>

```diff
+ BlockState getPlacementState(BlockPlaceContext)
- BlockState getPlacementState(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.item.HoeItem
</summary>

```diff
+ InteractionResult useOn(UseOnContext)
- InteractionResult useOn(UseOnContext)
+ void lambda$useOn$0(UseOnContext,Player)
- void lambda$useOn$0(UseOnContext,Player)
```

</details>
<details>
<summary>
net.minecraft.world.item.LeadItem
</summary>

```diff
+ InteractionResult useOn(UseOnContext)
- InteractionResult useOn(UseOnContext)
```

</details>
<details>
<summary>
net.minecraft.world.item.MapItem
</summary>

```diff
+ InteractionResult useOn(UseOnContext)
- InteractionResult useOn(UseOnContext)
+ ItemStack lockMap(Level,ItemStack)
- void lockMap(Level,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.item.MinecartItem
</summary>

```diff
+ InteractionResult useOn(UseOnContext)
- InteractionResult useOn(UseOnContext)
```

</details>
<details>
<summary>
net.minecraft.world.item.StandingAndWallBlockItem
</summary>

```diff
+ BlockState getPlacementState(BlockPlaceContext)
- BlockState getPlacementState(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.BlockGetter
</summary>

```diff
- double getBlockFloorHeight(BlockPos)
- double getBlockFloorHeight(VoxelShape,Supplier)
- VoxelShape lambda$getBlockFloorHeight$2(BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.MultiNoiseBiomeSource
</summary>

```diff
- Biome lambda$defaultNether$10()
- Biome lambda$defaultNether$11()
- Biome lambda$defaultNether$12()
- Biome lambda$defaultNether$13()
- Biome lambda$defaultNether$9()
+ Float lambda$getNoiseBiome$11(Biome$ClimateParameters,Pair)
- Float lambda$getNoiseBiome$14(Biome$ClimateParameters,Pair)
+ Pair lambda$null$9(Biome,Biome$ClimateParameters)
+ Stream lambda$defaultNether$10(Biome)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.AbstractFurnaceBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.AnvilBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BambooBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BannerBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BaseCoralWallFanBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BaseFireBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
- boolean canBePlacedAt(Level,BlockPos,Direction)
+ boolean canBePlacedAt(LevelAccessor,BlockPos)
- boolean inPortalDimension(Level)
- boolean isPortal(Level,BlockPos,Direction)
+ boolean isPortal(LevelAccessor,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BaseRailBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BedBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BeehiveBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BellBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CarvedPumpkinBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.ChainBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.ChorusPlantBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.ConduitBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.DiodeBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.DispenserBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.EndRodBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.EnderChestBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.FaceAttachedHorizontalDirectionalBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.FenceBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.GrowingPlantBodyBlock
</summary>

```diff
+ boolean canBeReplaced(BlockState,BlockPlaceContext)
- boolean canBeReplaced(BlockState,BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.HugeMushroomBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.JigsawBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.KelpBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.LadderBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.Lantern
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.LecternBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.NetherPortalBlock
</summary>

```diff
+ BlockPattern$BlockPatternMatch getPortalShape(LevelAccessor,BlockPos)
+ boolean trySpawnPortal(LevelAccessor,BlockPos)
+ NetherPortalBlock$PortalShape isPortal(LevelAccessor,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.piston.PistonBaseBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.BlockBehaviour
</summary>

```diff
+ boolean canBeReplaced(BlockState,BlockPlaceContext)
- boolean canBeReplaced(BlockState,BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase
</summary>

```diff
+ boolean canBeReplaced(BlockPlaceContext)
- boolean canBeReplaced(BlockPlaceContext)
- boolean isFaceSturdy(BlockGetter,BlockPos,Direction,SupportType)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.pattern.BlockPattern$BlockPatternMatch
</summary>

```diff
+ BlockPattern$PortalInfo getPortalOutput(Direction,BlockPos,double,Vec3,double)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.GenerationStep$Decoration
</summary>

```diff
+ GenerationStep$Decoration byName(String)
+ GenerationStep$Decoration lambda$static$0(GenerationStep$Decoration)
+ String getName()
+ String getSerializedName()
+ void <init>(String,int,String)
- void <init>(String,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.carver.WorldCarver
</summary>

```diff
+ CarverConfiguration lambda$new$1(ConfiguredWorldCarver)
- ConfiguredWorldCarver configured(CarverConfiguration)
+ ConfiguredWorldCarver lambda$new$0(CarverConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.BastionFeature
</summary>

```diff
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,JigsawConfiguration)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,MultiJigsawConfiguration)
+ StructureFeature$StructureStartFactory getStartFactory()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.NetherFortressFeature$NetherBridgeStart
</summary>

```diff
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,NoneFeatureConfiguration)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,NoneFeatureConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.OceanMonumentFeature$OceanMonumentStart
</summary>

```diff
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,NoneFeatureConfiguration)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,NoneFeatureConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.PillagerOutpostFeature
</summary>

```diff
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,JigsawConfiguration)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,NoneFeatureConfiguration)
+ StructureFeature$StructureStartFactory getStartFactory()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.SeagrassFeature
</summary>

```diff
- boolean place(WorldGenLevel,ChunkGenerator,Random,BlockPos,ProbabilityFeatureConfiguration)
+ boolean place(WorldGenLevel,ChunkGenerator,Random,BlockPos,SeagrassFeatureConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.ShipwreckFeature$FeatureStart
</summary>

```diff
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,ShipwreckConfiguration)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,ShipwreckConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.ColumnFeatureConfiguration
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
+ App lambda$static$4(RecordCodecBuilder$Instance)
+ Integer lambda$null$0(ColumnFeatureConfiguration)
+ Integer lambda$null$1(ColumnFeatureConfiguration)
+ Integer lambda$null$2(ColumnFeatureConfiguration)
+ Integer lambda$null$3(ColumnFeatureConfiguration)
- UniformInt height()
- UniformInt lambda$null$0(ColumnFeatureConfiguration)
- UniformInt lambda$null$1(ColumnFeatureConfiguration)
- UniformInt reach()
+ void <init>(int,int,int,int)
- void <init>(UniformInt,UniformInt)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.DecoratedFeatureConfiguration
</summary>

```diff
+ ConfiguredFeature lambda$null$0(DecoratedFeatureConfiguration)
- Supplier lambda$null$0(DecoratedFeatureConfiguration)
+ void <init>(ConfiguredFeature,ConfiguredDecorator)
- void <init>(Supplier,ConfiguredDecorator)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.DeltaFeatureConfiguration
</summary>

```diff
- App lambda$static$4(RecordCodecBuilder$Instance)
+ App lambda$static$5(RecordCodecBuilder$Instance)
- BlockState contents()
- BlockState rim()
+ Integer lambda$null$2(DeltaFeatureConfiguration)
+ Integer lambda$null$3(DeltaFeatureConfiguration)
+ Integer lambda$null$4(DeltaFeatureConfiguration)
- UniformInt lambda$null$2(DeltaFeatureConfiguration)
- UniformInt lambda$null$3(DeltaFeatureConfiguration)
- UniformInt rimSize()
- UniformInt size()
+ void <init>(BlockState,BlockState,int,int,int)
- void <init>(BlockState,BlockState,UniformInt,UniformInt)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherFossilFeature$FeatureStart
</summary>

```diff
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,NoneFeatureConfiguration)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,NoneFeatureConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.OceanRuinFeature$OceanRuinStart
</summary>

```diff
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,OceanRuinConfiguration)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,OceanRuinConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.PoolElementStructurePiece
</summary>

```diff
+ void <init>(StructureManager,CompoundTag,StructurePieceType)
- void <init>(StructureManager,CompoundTag)
- void <init>(StructureManager,StructurePoolElement,BlockPos,int,Rotation,BoundingBox)
+ void <init>(StructurePieceType,StructureManager,StructurePoolElement,BlockPos,int,Rotation,BoundingBox)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.StructureStart$1
</summary>

```diff
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,MineshaftConfiguration)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,MineshaftConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.surfacebuilders.SurfaceBuilder
</summary>

```diff
- ConfiguredSurfaceBuilder configured(SurfaceBuilderConfiguration)
+ ConfiguredSurfaceBuilder lambda$new$0(SurfaceBuilderConfiguration)
+ SurfaceBuilderConfiguration lambda$new$1(ConfiguredSurfaceBuilder)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.McRegionUpgrader
</summary>

```diff
+ void convertRegion(File,File,BiomeSource,int,int,ProgressListener)
- void convertRegion(RegistryAccess$RegistryHolder,File,File,BiomeSource,int,int,ProgressListener)
+ void convertRegions(File,Iterable,BiomeSource,int,int,ProgressListener)
- void convertRegions(RegistryAccess$RegistryHolder,File,Iterable,BiomeSource,int,int,ProgressListener)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
- net.minecraft.BlockUtil
- net.minecraft.BlockUtil$IntBounds
+ net.minecraft.package-info
- net.minecraft.Util$5
- net.minecraft.Util$7
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
- XXX.block.entity.JigsawBlockEntity$JointType
+ XXX.block.entity.JigsawBlockEntity$RuntimePiece
- XXX.chunk.storage.ChunkSerializer
+ XXX.chunk.storage.ChunkStorage
- XXX.chunk.storage.IOWorker
+ XXX.chunk.storage.IOWorker$PendingStore
- XXX.chunk.storage.IOWorker$Priority
+ XXX.chunk.storage.OldChunkStorage
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
+ XXX.data.models.BlockModelGenerators
- XXX.data.models.BlockModelGenerators$1
+ XXX.data.models.BlockModelGenerators$BlockEntityModelGenerator
- XXX.data.models.BlockModelGenerators$BlockFamilyProvider
+ XXX.data.models.BlockModelGenerators$TintState
- XXX.data.models.BlockModelGenerators$WoodProvider
+ XXX.data.models.ItemModelGenerators
- XXX.data.models.ModelProvider
- XXX.data.models.package-info
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
- XXX.data.recipes.UpgradeRecipeBuilder
+ XXX.data.recipes.UpgradeRecipeBuilder$Result
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
- XXX.data.tags.TagsProvider$1
+ XXX.data.tags.TagsProvider$TagAppender
- XXX.data.worldgen.BastionHoglinStablePools
- XXX.data.worldgen.BastionPieces
- XXX.data.worldgen.BastionTreasureRoomPools
- XXX.data.worldgen.Carvers
- XXX.data.worldgen.Features
- XXX.data.worldgen.Features$Decorators
- XXX.data.worldgen.PillagerOutpostPools
- XXX.data.worldgen.Pools
- XXX.data.worldgen.SavannaVillagePools
- XXX.data.worldgen.StructureFeatures
- XXX.data.worldgen.TaigaVillagePools
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
- XXX.datafix.fixes.PlayerUUIDFix
+ XXX.datafix.fixes.PoiTypeRename
- XXX.datafix.fixes.RecipesFix
+ XXX.datafix.fixes.RecipesRenameFix
- XXX.datafix.fixes.RecipesRenameningFix
+ XXX.datafix.fixes.RedstoneWireConnectionsFix
- XXX.datafix.fixes.References
- XXX.dimension.end.DragonRespawnAnimation
+ XXX.dimension.end.DragonRespawnAnimation$1
- XXX.dimension.end.DragonRespawnAnimation$2
+ XXX.dimension.end.DragonRespawnAnimation$3
- XXX.dimension.end.DragonRespawnAnimation$4
+ XXX.dimension.end.DragonRespawnAnimation$5
- XXX.dimension.end.EndDragonFight
+ XXX.dimension.end.package-info
+ XXX.entity.monster.Strider$StriderGroupData
- XXX.entity.npc.AbstractVillager
+ XXX.entity.npc.CatSpawner
- XXX.entity.npc.ClientSideMerchant
+ XXX.entity.npc.InventoryCarrier
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
+ XXX.entity.projectile.FishingHook
- XXX.entity.projectile.FishingHook$1
+ XXX.entity.projectile.FishingHook$FishHookState
- XXX.entity.projectile.FishingHook$OpenWaterType
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
+ XXX.entity.vehicle.DismountHelper
- XXX.entity.vehicle.Minecart
+ XXX.entity.vehicle.MinecartChest
- XXX.entity.vehicle.MinecartCommandBlock
+ XXX.entity.vehicle.MinecartCommandBlock$MinecartCommandBase
- XXX.entity.vehicle.MinecartFurnace
+ XXX.entity.vehicle.MinecartHopper
- XXX.entity.vehicle.MinecartSpawner
+ XXX.entity.vehicle.MinecartSpawner$1
- XXX.entity.vehicle.MinecartTNT
+ XXX.entity.vehicle.package-info
- XXX.feature.blockplacers.BlockPlacer
+ XXX.feature.blockplacers.BlockPlacerType
- XXX.feature.blockplacers.ColumnPlacer
+ XXX.feature.blockplacers.DoublePlantPlacer
+ XXX.feature.blockplacers.package-info
- XXX.feature.blockplacers.SimpleBlockPlacer
+ XXX.feature.configurations.BuriedTreasureConfiguration
+ XXX.feature.configurations.CountFeatureConfiguration
+ XXX.feature.configurations.DiskConfiguration
- XXX.feature.configurations.EndGatewayConfiguration
+ XXX.feature.configurations.FeatureConfiguration
+ XXX.feature.configurations.MultiJigsawConfiguration
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
- XXX.feature.configurations.RangeDecoratorConfiguration
+ XXX.feature.configurations.ReplaceBlockConfiguration
- XXX.feature.configurations.ReplaceSphereConfiguration
+ XXX.feature.configurations.ReplaceSpheroidConfiguration$Builder
+ XXX.feature.configurations.SeagrassFeatureConfiguration
- XXX.feature.configurations.ShipwreckConfiguration
+ XXX.feature.configurations.SimpleBlockConfiguration
- XXX.feature.configurations.SimpleRandomFeatureConfiguration
+ XXX.feature.configurations.SpikeConfiguration
- XXX.feature.configurations.SpringConfiguration
+ XXX.feature.configurations.StrongholdConfiguration
- XXX.feature.configurations.StructureFeatureConfiguration
+ XXX.feature.configurations.TreeConfiguration
- XXX.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
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
+ XXX.feature.foliageplacers.FoliagePlacer$Factory
- XXX.feature.foliageplacers.FoliagePlacer$FoliageAttachment
+ XXX.feature.foliageplacers.FoliagePlacerType
- XXX.feature.foliageplacers.MegaJungleFoliagePlacer
+ XXX.feature.foliageplacers.MegaPineFoliagePlacer
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
- XXX.feature.structures.LegacySinglePoolElement
+ XXX.feature.structures.ListPoolElement
- XXX.feature.structures.SinglePoolElement
+ XXX.feature.structures.StructurePoolElement
- XXX.feature.structures.StructurePoolElementType
+ XXX.feature.structures.StructureTemplatePool
- XXX.feature.structures.StructureTemplatePool$Projection
+ XXX.feature.structures.StructureTemplatePools
+ XXX.gametest.framework.BeforeBatch
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
+ XXX.gametest.framework.JUnitLikeTestReporter
- XXX.gametest.framework.LogTestReporter
+ XXX.gametest.framework.MultipleTestTracker
- XXX.gametest.framework.MultipleTestTracker$1
- XXX.gametest.framework.package-info
+ XXX.gametest.framework.StructureUtils
- XXX.gametest.framework.StructureUtils$1
+ XXX.gametest.framework.TeamcityTestReporter
- XXX.gametest.framework.TestClassNameArgument
+ XXX.gametest.framework.TestCommand
- XXX.gametest.framework.TestCommand$TestSummaryDisplayer
+ XXX.gametest.framework.TestFunction
- XXX.gametest.framework.TestFunctionArgument
+ XXX.gametest.framework.TestReporter
- XXX.item.alchemy.package-info
+ XXX.item.alchemy.Potion
- XXX.item.alchemy.PotionBrewing
+ XXX.item.alchemy.PotionBrewing$Mix
+ XXX.item.alchemy.Potions
- XXX.item.alchemy.PotionUtils
- XXX.item.context.DirectionalPlaceContext
- XXX.item.context.UseOnContext
+ XXX.level.biome.BadlandsPlateauBiome
+ XXX.level.biome.BambooJungleHillsBiome
+ XXX.level.biome.BeachBiome
+ XXX.level.biome.BiomeDefaultFeatures
- XXX.level.biome.BiomeManager
+ XXX.level.biome.BiomeManager$NoiseBiomeSource
+ XXX.level.biome.Biomes
- XXX.level.biome.BiomeSource
+ XXX.level.biome.BiomeSpecialEffects
- XXX.level.biome.BiomeSpecialEffects$1
+ XXX.level.biome.BiomeSpecialEffects$Builder
- XXX.level.biome.BiomeZoomer
+ XXX.level.biome.BirchForestHillsBiome
- XXX.level.biome.CheckerboardColumnBiomeSource
+ XXX.level.biome.ColdOceanBiome
+ XXX.level.biome.DarkForestBiome
+ XXX.level.biome.DeepColdOceanBiome
+ XXX.level.biome.DeepLukeWarmOceanBiome
+ XXX.level.biome.DeepWarmOceanBiome
+ XXX.level.biome.DesertHillsBiome
+ XXX.level.biome.EndBarrensBiome
+ XXX.level.biome.EndMidlandsBiome
+ XXX.level.biome.FixedBiomeSource
+ XXX.level.biome.ForestFlowerBiome
+ XXX.level.biome.FrozenRiverBiome
- XXX.level.biome.FuzzyOffsetBiomeZoomer
+ XXX.level.biome.FuzzyOffsetConstantColumnBiomeZoomer
+ XXX.level.biome.GiantSpruceTaigaHillsMutatedBiome
+ XXX.level.biome.GiantTreeTaigaHillsBiome
+ XXX.level.biome.IceSpikesBiome
+ XXX.level.biome.JungleEdgeBiome
+ XXX.level.biome.LukeWarmOceanBiome
+ XXX.level.biome.ModifiedGravellyMountainsBiome
+ XXX.level.biome.ModifiedJungleEdgeBiome
+ XXX.level.biome.MountainBiome
+ XXX.level.biome.MushroomFieldsBiome
+ XXX.level.biome.OceanBiome
+ XXX.level.biome.PlainsBiome
+ XXX.level.biome.SavannaBiome
+ XXX.level.biome.ShatteredSavannaBiome
+ XXX.level.biome.SmallEndIslandsBiome
+ XXX.level.biome.SnowyMountainsBiome
+ XXX.level.biome.SnowyTaigaHillsBiome
+ XXX.level.biome.SnowyTundraBiome
+ XXX.level.biome.StoneShoreBiome
+ XXX.level.biome.SwampBiome
+ XXX.level.biome.TaigaBiome
+ XXX.level.biome.TaigaMountainsBiome
+ XXX.level.biome.TallBirchHillsBiome
+ XXX.level.biome.WarmOceanBiome
+ XXX.level.biome.WoodedBadlandsBiome
+ XXX.level.biome.WoodedMountainBiome
+ XXX.level.block.NetherPortalBlock$PortalShape
+ XXX.level.block.NetherrackBlock
- XXX.level.block.NetherSproutsBlock
+ XXX.level.block.NetherVines
- XXX.level.block.NetherWartBlock
- XXX.level.block.NoteBlock
+ XXX.level.block.NyliumBlock
- XXX.level.block.ObserverBlock
+ XXX.level.block.OreBlock
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
- XXX.level.block.RespawnAnchorBlock
+ XXX.level.block.RespawnAnchorBlock$1
- XXX.level.block.RootsBlock
+ XXX.level.block.RotatedPillarBlock
- XXX.level.block.RotatedPillarBlock$1
+ XXX.level.block.Rotation
- XXX.level.block.Rotation$1
+ XXX.level.block.SandBlock
- XXX.level.block.SaplingBlock
+ XXX.level.block.ScaffoldingBlock
+ XXX.level.block.Seagrass
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
- XXX.level.block.SupportType
- XXX.level.block.SupportType$2
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
+ XXX.level.block.TwistingVines
- XXX.level.block.TwistingVinesPlant
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
- XXX.level.border.package-info
- XXX.level.border.WorldBorder
+ XXX.level.border.WorldBorder$1
- XXX.level.border.WorldBorder$BorderExtent
+ XXX.level.border.WorldBorder$MovingBorderExtent
- XXX.level.border.WorldBorder$Settings
+ XXX.level.border.WorldBorder$StaticBorderExtent
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
- XXX.level.dimension.DimensionType
+ XXX.level.dimension.LevelStem
- XXX.level.dimension.package-info
+ XXX.level.levelgen.DebugLevelSource
- XXX.level.levelgen.Decoratable
- XXX.level.portal.package-info
- XXX.level.portal.PortalInfo
- XXX.level.progress.ChunkProgressListener
+ XXX.level.progress.ChunkProgressListenerFactory
- XXX.level.progress.LoggerChunkProgressListener
+ XXX.level.progress.package-info
+ XXX.level.progress.ProcessorChunkProgressListener
- XXX.level.progress.StoringChunkProgressListener
+ XXX.levelgen.feature.BastionHoglinStablePools
+ XXX.levelgen.feature.BastionPieces
+ XXX.levelgen.feature.BastionSharedPools
+ XXX.levelgen.feature.BlockBlobFeature
- XXX.levelgen.feature.BlockPileFeature
+ XXX.levelgen.feature.BlueIceFeature
- XXX.levelgen.feature.BonusChestFeature
+ XXX.levelgen.feature.BuriedTreasureFeature
- XXX.levelgen.feature.BuriedTreasureFeature$BuriedTreasureStart
+ XXX.levelgen.feature.ChorusPlantFeature
- XXX.levelgen.feature.ConfiguredFeature
+ XXX.levelgen.feature.ConfiguredStructureFeature
- XXX.levelgen.feature.CoralClawFeature
+ XXX.levelgen.feature.CoralFeature
- XXX.levelgen.feature.CoralMushroomFeature
+ XXX.levelgen.feature.CoralTreeFeature
- XXX.levelgen.feature.DecoratedFeature
+ XXX.levelgen.feature.DecoratedFlowerFeature
- XXX.levelgen.feature.DefaultFlowerFeature
+ XXX.levelgen.feature.DeltaFeature
- XXX.levelgen.feature.DesertPyramidFeature
+ XXX.levelgen.feature.DesertPyramidFeature$FeatureStart
- XXX.levelgen.feature.JigsawFeature
+ XXX.levelgen.feature.package-info
+ XXX.levelgen.feature.PlainVillagePools
+ XXX.levelgen.feature.RandomSelectorFeature
- XXX.levelgen.feature.ReplaceBlobsFeature
+ XXX.levelgen.feature.ReplaceBlockFeature
- XXX.levelgen.feature.RuinedPortalFeature
+ XXX.levelgen.feature.RuinedPortalFeature$FeatureStart
- XXX.levelgen.feature.RuinedPortalFeature$Type
+ XXX.levelgen.feature.SavannaVillagePools
+ XXX.levelgen.feature.SpikeFeature
- XXX.levelgen.feature.SpikeFeature$1
+ XXX.levelgen.feature.SpikeFeature$EndSpike
- XXX.levelgen.feature.SpikeFeature$SpikeCacheLoader
+ XXX.levelgen.feature.SpringFeature
- XXX.levelgen.feature.StrongholdFeature
+ XXX.levelgen.feature.StrongholdFeature$StrongholdStart
- XXX.levelgen.feature.StructureFeature
+ XXX.levelgen.feature.StructureFeature$StructureStartFactory
- XXX.levelgen.feature.StructurePieceType
+ XXX.levelgen.feature.SwamplandHutFeature
- XXX.levelgen.feature.SwamplandHutFeature$FeatureStart
+ XXX.levelgen.feature.TaigaVillagePools
+ XXX.levelgen.feature.VillageFeature$FeatureStart
+ XXX.levelgen.feature.VillagePieces$VillagePiece
- XXX.levelgen.feature.VinesFeature
+ XXX.levelgen.feature.VoidStartPlatformFeature
- XXX.levelgen.feature.WeepingVinesFeature
+ XXX.levelgen.feature.WeightedConfiguredFeature
- XXX.levelgen.feature.WoodlandMansionFeature
+ XXX.levelgen.feature.WoodlandMansionFeature$WoodlandMansionStart
- XXX.levelgen.placement.BiasedRangeDecorator
- XXX.levelgen.placement.ChanceDecoratorConfiguration
+ XXX.levelgen.placement.ChanceHeightmapDecorator
+ XXX.levelgen.placement.ChancePassthroughDecorator
+ XXX.levelgen.placement.ChorusPlantPlacementDecorator
+ XXX.levelgen.placement.CountBiasedRangeDecorator
+ XXX.levelgen.placement.CountChanceHeightmapDoubleDecorator
- XXX.levelgen.placement.CountDecorator
+ XXX.levelgen.placement.CountHeighmapDoubleDecorator
+ XXX.levelgen.placement.CountHeightmap32Decorator
+ XXX.levelgen.placement.CountTopSolidDecorator
- XXX.levelgen.placement.CountWithExtraChanceDecorator
+ XXX.levelgen.placement.CountWithExtraChanceHeightmapDecorator
- XXX.levelgen.placement.DecoratedDecorator
- XXX.levelgen.placement.DecorationContext
+ XXX.levelgen.placement.DepthAverageConfigation
- XXX.levelgen.placement.DepthAverageDecorator
- XXX.levelgen.placement.EmeraldPlacementDecorator
+ XXX.levelgen.placement.EndGatewayPlacementDecorator
- XXX.levelgen.placement.EndIslandPlacementDecorator
+ XXX.levelgen.placement.FeatureDecorator
+ XXX.levelgen.placement.FrequencyChanceDecoratorConfiguration
- XXX.levelgen.placement.HeightmapDecorator
- XXX.levelgen.placement.IcebergPlacementDecorator
+ XXX.levelgen.placement.LakeLavaPlacementDecorator
- XXX.levelgen.placement.LakeWaterPlacementDecorator
+ XXX.levelgen.placement.MonsterRoomPlacementDecorator
- XXX.levelgen.placement.NoiseCountFactorDecoratorConfiguration
+ XXX.levelgen.placement.NoiseHeightmap32Decorator
+ XXX.levelgen.placement.NopePlacementDecorator
- XXX.levelgen.placement.RangeDecorator
+ XXX.levelgen.placement.SimpleFeatureDecorator
- XXX.levelgen.placement.Spread32Decorator
- XXX.levelgen.placement.TopSolidHeightMapDecorator
+ XXX.levelgen.placement.TopSolidHeightMapNoiseBasedDecorator
+ XXX.levelgen.structure.PillagerOutpostPieces
- XXX.metadata.pack.package-info
- XXX.metadata.pack.PackMetadataSection
+ XXX.metadata.pack.PackMetadataSectionSerializer
- XXX.minecraft.core.BlockPos$5
+ XXX.minecraft.core.BlockPos$MutableBlockPos
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
+ XXX.minecraft.core.FrontAndTop
- XXX.minecraft.core.GlobalPos
+ XXX.minecraft.core.IdMap
- XXX.minecraft.core.IdMapper
+ XXX.minecraft.core.MappedRegistry
- XXX.minecraft.core.NonNullList
+ XXX.minecraft.core.Position
- XXX.minecraft.core.PositionImpl
+ XXX.minecraft.core.Registry
- XXX.minecraft.core.RegistryAccess
- XXX.minecraft.data.DataGenerator
+ XXX.minecraft.data.DataProvider
- XXX.minecraft.data.HashCache
+ XXX.minecraft.data.Main
+ XXX.minecraft.data.package-info
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
- XXX.minecraft.nbt.NbtOps$1
+ XXX.minecraft.nbt.NbtOps$NbtRecordBuilder
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
+ XXX.minecraft.network.PacketDecoder
- XXX.minecraft.network.PacketEncoder
+ XXX.minecraft.network.PacketListener
- XXX.minecraft.network.RateKickingConnection
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
- XXX.minecraft.tags.ItemTags
+ XXX.minecraft.tags.package-info
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
- XXX.minecraft.tags.Tag$TagEntry
+ XXX.minecraft.tags.TagCollection
- XXX.minecraft.tags.TagCollection$1
+ XXX.minecraft.tags.TagContainer
- XXX.minecraft.tags.TagContainer$1
+ XXX.minecraft.tags.TagLoader
- XXX.minecraft.tags.TagManager
- XXX.minecraft.util.BitStorage
+ XXX.minecraft.util.ClassInstanceMultiMap
+ XXX.minecraft.util.Codecs$1
+ XXX.minecraft.util.Codecs$3
- XXX.minecraft.util.Unit
+ XXX.minecraft.util.VisibleForDebug
- XXX.minecraft.util.WeighedRandom
+ XXX.minecraft.util.WeighedRandom$WeighedRandomItem
+ XXX.models.blockstates.BlockStateGenerator
- XXX.models.blockstates.Condition
+ XXX.models.blockstates.Condition$1
- XXX.models.blockstates.Condition$CompositeCondition
+ XXX.models.blockstates.Condition$Operation
- XXX.models.blockstates.Condition$TerminalCondition
+ XXX.models.blockstates.MultiPartGenerator
- XXX.models.blockstates.MultiPartGenerator$1
+ XXX.models.blockstates.MultiPartGenerator$ConditionalEntry
- XXX.models.blockstates.MultiPartGenerator$Entry
+ XXX.models.blockstates.MultiVariantGenerator
- XXX.models.blockstates.package-info
- XXX.models.blockstates.PropertyDispatch
+ XXX.models.blockstates.PropertyDispatch$1
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
+ XXX.monster.piglin.package-info
- XXX.monster.piglin.StopHoldingItemIfNoLongerAdmiring
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
+ XXX.placement.nether.ChanceRangeDecorator
- XXX.placement.nether.CountMultiLayerDecorator
+ XXX.placement.nether.FireDecorator
- XXX.placement.nether.GlowstoneDecorator
+ XXX.placement.nether.MagmaDecorator
+ XXX.protocol.game.ClientboundChunkBlocksUpdatePacket
- XXX.protocol.game.ClientboundSectionBlocksUpdatePacket
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
- XXX.protocol.game.ClientboundSetEquipmentPacket
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
+ XXX.state.properties.SlabType
- XXX.state.properties.StairsShape
+ XXX.state.properties.StructureMode
- XXX.state.properties.WallSide
+ XXX.state.properties.WoodType
+ XXX.util.datafix.DataFixers
- XXX.util.datafix.DataFixers$1
+ XXX.util.datafix.DataFixers$2
- XXX.util.datafix.DataFixTypes
- XXX.util.datafix.PackedBitStorage
+ XXX.world.entity.package-info
- XXX.world.food.FoodConstants
+ XXX.world.food.FoodData
- XXX.world.food.FoodProperties
+ XXX.world.food.FoodProperties$1
- XXX.world.food.FoodProperties$Builder
+ XXX.world.food.Foods
- XXX.world.food.package-info
+ XXX.world.inventory.AbstractContainerMenu
- XXX.world.inventory.AbstractFurnaceMenu
+ XXX.world.inventory.AnvilMenu
- XXX.world.inventory.AnvilMenu$1
+ XXX.world.inventory.BeaconMenu
- XXX.world.inventory.BeaconMenu$1
+ XXX.world.inventory.BeaconMenu$PaymentSlot
- XXX.world.inventory.BlastFurnaceMenu
+ XXX.world.inventory.BrewingStandMenu
- XXX.world.inventory.BrewingStandMenu$FuelSlot
+ XXX.world.inventory.BrewingStandMenu$IngredientsSlot
- XXX.world.inventory.BrewingStandMenu$PotionSlot
+ XXX.world.inventory.CartographyTableMenu
- XXX.world.inventory.CartographyTableMenu$1
+ XXX.world.inventory.CartographyTableMenu$2
- XXX.world.inventory.CartographyTableMenu$3
+ XXX.world.inventory.CartographyTableMenu$4
- XXX.world.inventory.CartographyTableMenu$5
+ XXX.world.inventory.ChestMenu
- XXX.world.inventory.ClickType
+ XXX.world.inventory.ContainerData
- XXX.world.inventory.ContainerLevelAccess
+ XXX.world.inventory.ContainerLevelAccess$1
- XXX.world.inventory.ContainerLevelAccess$2
+ XXX.world.inventory.ContainerListener
- XXX.world.inventory.CraftingContainer
+ XXX.world.inventory.CraftingMenu
- XXX.world.inventory.DataSlot
+ XXX.world.inventory.DataSlot$1
- XXX.world.inventory.DataSlot$2
+ XXX.world.inventory.DataSlot$3
- XXX.world.inventory.DispenserMenu
+ XXX.world.inventory.EnchantmentMenu
- XXX.world.inventory.EnchantmentMenu$1
+ XXX.world.inventory.EnchantmentMenu$2
- XXX.world.inventory.EnchantmentMenu$3
+ XXX.world.inventory.FurnaceFuelSlot
- XXX.world.inventory.FurnaceMenu
+ XXX.world.inventory.FurnaceResultSlot
- XXX.world.inventory.GrindstoneMenu
+ XXX.world.inventory.GrindstoneMenu$1
- XXX.world.inventory.GrindstoneMenu$2
+ XXX.world.inventory.GrindstoneMenu$3
- XXX.world.inventory.GrindstoneMenu$4
+ XXX.world.inventory.HopperMenu
- XXX.world.inventory.HorseInventoryMenu
+ XXX.world.inventory.HorseInventoryMenu$1
- XXX.world.inventory.HorseInventoryMenu$2
+ XXX.world.inventory.InventoryMenu
- XXX.world.inventory.InventoryMenu$1
+ XXX.world.inventory.InventoryMenu$2
- XXX.world.inventory.ItemCombinerMenu
+ XXX.world.inventory.ItemCombinerMenu$1
- XXX.world.inventory.ItemCombinerMenu$2
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
- XXX.world.inventory.RecipeBookType
+ XXX.world.inventory.RecipeHolder
- XXX.world.inventory.ResultContainer
+ XXX.world.inventory.ResultSlot
- XXX.world.inventory.ShulkerBoxMenu
+ XXX.world.inventory.ShulkerBoxSlot
- XXX.world.inventory.SimpleContainerData
+ XXX.world.inventory.Slot
- XXX.world.inventory.SmithingMenu
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
+ XXX.world.item.DirectionalPlaceContext$1
+ XXX.world.item.UseOnContext
- XXX.world.item.Vanishable
+ XXX.world.item.WaterLilyBlockItem
- XXX.world.item.Wearable
+ XXX.world.item.WritableBookItem
- XXX.world.item.WrittenBookItem
+ XXX.world.level.DefaultExplosionDamageCalculator
- XXX.world.level.EmptyBlockGetter
+ XXX.world.level.EmptyTickList
- XXX.world.level.EntityBasedExplosionDamageCalculator
+ XXX.world.level.EntityGetter
- XXX.world.level.Explosion
+ XXX.world.level.Explosion$BlockInteraction
- XXX.world.level.ExplosionDamageCalculator
+ XXX.world.level.FoliageColor
- XXX.world.level.ForcedChunksSavedData
+ XXX.world.level.GameRules
- XXX.world.level.GameRules$1
+ XXX.world.level.GameRules$BooleanValue
- XXX.world.level.GameRules$Category
+ XXX.world.level.GameRules$GameRuleTypeVisitor
- XXX.world.level.GameRules$IntegerValue
+ XXX.world.level.GameRules$Key
- XXX.world.level.GameRules$Type
+ XXX.world.level.GameRules$Value
- XXX.world.level.GameRules$VisitorCaller
+ XXX.world.level.GameType
- XXX.world.level.GrassColor
+ XXX.world.level.ItemLike
- XXX.world.level.Level
+ XXX.world.level.Level$1
- XXX.world.level.LevelAccessor
+ XXX.world.level.LevelReader
- XXX.world.level.LevelSettings
- XXX.world.level.LevelSimulatedReader
+ XXX.world.level.LevelSimulatedRW
+ XXX.world.level.LevelTimeAccess
- XXX.world.level.LevelWriter
+ XXX.world.level.LightLayer
- XXX.world.level.NaturalSpawner
+ XXX.world.level.NaturalSpawner$1
- XXX.world.level.NaturalSpawner$AfterSpawnCallback
+ XXX.world.level.NaturalSpawner$ChunkGetter
- XXX.world.level.NaturalSpawner$SpawnPredicate
+ XXX.world.level.NaturalSpawner$SpawnState
- XXX.world.level.NoiseColumn
+ XXX.world.level.PathNavigationRegion
- XXX.worldgen.biome.BadlandsBiome
- XXX.worldgen.biome.BambooJungleBiome
- XXX.worldgen.biome.BasaltDeltasBiome
- XXX.worldgen.biome.BirchForestBiome
- XXX.worldgen.biome.ColdOceanBiome
- XXX.worldgen.biome.DarkForestBiome
- XXX.worldgen.biome.DeepColdOceanBiome
- XXX.worldgen.biome.DeepLukeWarmOceanBiome
- XXX.worldgen.biome.DeepWarmOceanBiome
- XXX.worldgen.biome.DesertHillsBiome
- XXX.worldgen.biome.EndBarrensBiome
- XXX.worldgen.biome.EndMidlandsBiome
- XXX.worldgen.biome.ForestBiome
- XXX.worldgen.biome.FrozenOceanBiome
- XXX.worldgen.biome.GiantSpruceTaigaBiome
- XXX.worldgen.biome.GiantTreeTaigaBiome
- XXX.worldgen.biome.GravellyMountainsBiome
- XXX.worldgen.biome.JungleBiome
- XXX.worldgen.biome.JungleHillsBiome
- XXX.worldgen.biome.ModifiedBadlandsPlateauBiome
- XXX.worldgen.biome.ModifiedJungleBiome
- XXX.worldgen.biome.ModifiedWoodedBadlandsPlateauBiome
- XXX.worldgen.biome.MountainEdgeBiome
- XXX.worldgen.biome.MushroomFieldsShoreBiome
- XXX.worldgen.biome.OceanBiome
- XXX.worldgen.biome.RiverBiome
- XXX.worldgen.biome.SavannaPlateauBiome
- XXX.worldgen.biome.ShatteredSavannaPlateauBiome
- XXX.worldgen.biome.SnowyBeachBiome
- XXX.worldgen.biome.SnowyTaigaBiome
- XXX.worldgen.biome.SnowyTaigaMountainsBiome
- XXX.worldgen.biome.SoulSandValleyBiome
- XXX.worldgen.biome.SunflowerPlainsBiome
- XXX.worldgen.biome.SwampHillsBiome
- XXX.worldgen.biome.TaigaHillsBiome
- XXX.worldgen.biome.TallBirchForestBiome
- XXX.worldgen.biome.TheEndBiome
- XXX.worldgen.biome.WarmOceanBiome
- XXX.worldgen.biome.WoodedBadlandsBiome
- XXX.worldgen.biome.WoodedMountainBiome
```

</details>
<details>
<summary>
Changes
</summary>

```
net.minecraft.Util +9M -2M
```
```
net.minecraft.Util$3 +3M -2M | +2P
```
```
XXX.minecraft.client.Option +6M -1M | +1P -1P
```
```
XXX.gui.screens.CreateBuffetWorldScreen +4M -3M | +1P
```
```
XXX.gui.screens.CreateBuffetWorldScreen$BiomeList +2M -2M
```
```
XXX.gui.screens.CreateFlatWorldScreen +1M -1M | +1P -1P
```
```
XXX.gui.screens.ShareToLanScreen +1M | +2P
```
```
XXX.screens.inventory.BookEditScreen +1M -1M | +6P
```
```
XXX.screens.inventory.BookViewScreen -1M | +1P
```
```
XXX.screens.worldselection.CreateWorldScreen$SelectedGameMode +2M -2M
```
```
XXX.screens.worldselection.EditGameRulesScreen$BooleanRuleEntry -2M
```
```
XXX.screens.worldselection.EditGameRulesScreen$RuleEntry +1M -1M
```
```
XXX.screens.worldselection.WorldGenSettingsComponent +4M -2M | +1P -1P
```
```
XXX.client.multiplayer.ClientPacketListener +1M -1M
```
```
XXX.client.server.IntegratedServer +1M
```
```
XXX.minecraft.core.RegistryAccess$RegistryHolder +14M -4M | +2P -2P
```
```
XXX.minecraft.core.SectionPos +7M
```
```
XXX.network.chat.CommonComponents +1M
```
```
XXX.protocol.game.ClientGamePacketListener +1P -1P
```
```
XXX.protocol.game.ClientboundBlockUpdatePacket +1M
```
```
XXX.protocol.game.ClientboundLevelChunkPacket +1M -1M | +1P -1P
```
```
XXX.ai.behavior.AcquirePoi +5M -4M | +1P
```
```
XXX.ai.memory.MemoryModuleType +2P
```
```
XXX.entity.monster.EnderMan$EndermanLookForPlayerGoal +1M -1M
```
```
XXX.monster.piglin.Piglin -1M | -2P
```
```
XXX.world.item.BoneMealItem +1M -1M
```
```
XXX.world.item.EndCrystalItem +1M -1M
```
```
XXX.world.item.FireChargeItem +1M -1M
```
```
XXX.world.item.FlintAndSteelItem +3M -3M
```
```
XXX.world.item.GameMasterBlockItem +1M -1M
```
```
XXX.world.item.HoeItem +2M -2M
```
```
XXX.world.item.LeadItem +1M -1M
```
```
XXX.world.item.MapItem +2M -2M
```
```
XXX.world.item.MinecartItem +1M -1M
```
```
XXX.world.item.StandingAndWallBlockItem +1M -1M
```
```
XXX.world.level.BlockGetter +3M
```
```
XXX.level.biome.MultiNoiseBiomeSource +6M -3M
```
```
XXX.level.block.AbstractFurnaceBlock +1M -1M
```
```
XXX.level.block.AnvilBlock +1M -1M
```
```
XXX.level.block.BambooBlock +1M -1M
```
```
XXX.level.block.BannerBlock +1M -1M
```
```
XXX.level.block.BaseCoralWallFanBlock +1M -1M
```
```
XXX.level.block.BaseFireBlock +4M -3M
```
```
XXX.level.block.BaseRailBlock +1M -1M
```
```
XXX.level.block.BedBlock +1M -1M
```
```
XXX.level.block.BeehiveBlock +1M -1M
```
```
XXX.level.block.BellBlock +1M -1M
```
```
XXX.level.block.CarvedPumpkinBlock +1M -1M
```
```
XXX.level.block.ChainBlock +1M -1M
```
```
XXX.level.block.ChorusPlantBlock +1M -1M
```
```
XXX.level.block.ConduitBlock +1M -1M
```
```
XXX.level.block.DiodeBlock +1M -1M
```
```
XXX.level.block.DispenserBlock +1M -1M
```
```
XXX.level.block.EndRodBlock +1M -1M
```
```
XXX.level.block.EnderChestBlock +1M -1M
```
```
XXX.level.block.FaceAttachedHorizontalDirectionalBlock +1M -1M
```
```
XXX.level.block.FenceBlock +1M -1M
```
```
XXX.level.block.GrowingPlantBodyBlock +1M -1M
```
```
XXX.level.block.HugeMushroomBlock +1M -1M
```
```
XXX.level.block.JigsawBlock +1M -1M
```
```
XXX.level.block.KelpBlock +1M -1M
```
```
XXX.level.block.LadderBlock +1M -1M
```
```
XXX.level.block.Lantern +1M -1M
```
```
XXX.level.block.LecternBlock +1M -1M
```
```
XXX.level.block.NetherPortalBlock -3M
```
```
XXX.block.piston.PistonBaseBlock +1M -1M
```
```
XXX.block.state.BlockBehaviour +1M -1M
```
```
XXX.block.state.BlockBehaviour$BlockStateBase +2M -1M
```
```
XXX.state.pattern.BlockPattern$BlockPatternMatch -1M
```
```
XXX.level.levelgen.GenerationStep$Decoration +1M -5M | -3P
```
```
XXX.levelgen.carver.WorldCarver +1M -2M
```
```
XXX.levelgen.feature.BastionFeature +1M -2M
```
```
XXX.levelgen.feature.NetherFortressFeature$NetherBridgeStart +2M -2M
```
```
XXX.levelgen.feature.OceanMonumentFeature$OceanMonumentStart +2M -2M
```
```
XXX.levelgen.feature.PillagerOutpostFeature +1M -2M
```
```
XXX.levelgen.feature.SeagrassFeature +1M -1M
```
```
XXX.levelgen.feature.ShipwreckFeature$FeatureStart +2M -2M
```
```
XXX.feature.configurations.ColumnFeatureConfiguration +6M -6M | +2P -4P
```
```
XXX.feature.configurations.DecoratedFeatureConfiguration +2M -2M | +1P -1P
```
```
XXX.feature.configurations.DeltaFeatureConfiguration +8M -5M | +2P -3P
```
```
XXX.levelgen.structure.NetherFossilFeature$FeatureStart +2M -2M
```
```
XXX.levelgen.structure.OceanRuinFeature$OceanRuinStart +2M -2M
```
```
XXX.levelgen.structure.PoolElementStructurePiece +2M -2M
```
```
XXX.levelgen.structure.StructureStart$1 +2M -2M
```
```
XXX.structure.templatesystem.StructureProcessorType +3P -1P
```
```
XXX.levelgen.surfacebuilders.SurfaceBuilder +1M -2M | -3P
```
```
XXX.level.storage.McRegionUpgrader +2M -2M
```

</details>
<details>
<summary>
net.minecraft.Util
</summary>

```diff
- boolean executeInSequence(BooleanSupplier[])
- boolean runWithRetries(int,String,BooleanSupplier[])
- BooleanSupplier createDeleter(Path)
- BooleanSupplier createFileCreatedCheck(Path)
- BooleanSupplier createFileDeletedCheck(Path)
- BooleanSupplier createRenamer(Path,Path)
- String lambda$sanitizeName$7(CharPredicate,int)
+ String lambda$sanitizeResourceName$7(int)
- String sanitizeName(String,CharPredicate)
+ String sanitizeResourceName(String)
- void safeReplaceFile(Path,Path,Path)
```

</details>
<details>
<summary>
net.minecraft.Util$3
</summary>

```diff
- boolean getAsBoolean()
- String toString()
- void <init>(Path,Path)
+ void <init>(String)
+ void run()
```

</details>
<details>
<summary>
net.minecraft.client.Option
</summary>

```diff
- Component genericValueLabel(Component)
- Component genericValueLabel(int)
- Component getCaption()
- Component percentAddValueLabel(int)
- Component percentValueLabel(double)
- Component pixelValueLabel(int)
+ MutableComponent createCaption()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.CreateBuffetWorldScreen
</summary>

```diff
+ Biome access$102(CreateBuffetWorldScreen,Biome)
- Biome access$202(CreateBuffetWorldScreen,Biome)
+ void <init>(Screen,Consumer,Biome)
- void <init>(Screen,RegistryAccess,Consumer,Biome)
+ void access$300(CreateBuffetWorldScreen)
- void access$400(CreateBuffetWorldScreen)
- WritableRegistry access$100(CreateBuffetWorldScreen)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.CreateBuffetWorldScreen$BiomeList
</summary>

```diff
+ String lambda$new$0(Biome)
- String lambda$new$0(Map$Entry)
+ void lambda$new$1(Biome)
- void lambda$new$1(Map$Entry)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.CreateFlatWorldScreen
</summary>

```diff
- void <init>(CreateWorldScreen,Consumer,FlatLevelGeneratorSettings)
+ void <init>(Screen,Consumer,FlatLevelGeneratorSettings)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.ShareToLanScreen
</summary>

```diff
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.BookEditScreen
</summary>

```diff
+ int strWidth(String)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.BookViewScreen
</summary>

```diff
+ int strWidth(String)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$SelectedGameMode
</summary>

```diff
+ GameType access$700(CreateWorldScreen$SelectedGameMode)
- GameType access$800(CreateWorldScreen$SelectedGameMode)
+ String access$200(CreateWorldScreen$SelectedGameMode)
- String access$300(CreateWorldScreen$SelectedGameMode)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$BooleanRuleEntry
</summary>

```diff
+ MutableComponent access$500(EditGameRulesScreen$BooleanRuleEntry,Component,boolean)
+ MutableComponent createFullMessage(Component,boolean)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$RuleEntry
</summary>

```diff
- List access$1000(EditGameRulesScreen$RuleEntry)
+ List access$1100(EditGameRulesScreen$RuleEntry)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.worldselection.WorldGenSettingsComponent
</summary>

```diff
- OptionalLong parseSeed()
- String toString(OptionalLong)
+ void <init>()
- void <init>(RegistryAccess$RegistryHolder,WorldGenSettings,Optional,OptionalLong)
+ void <init>(RegistryAccess$RegistryHolder,WorldGenSettings)
- void setRegistryHolder(RegistryAccess$RegistryHolder)
```

</details>
<details>
<summary>
net.minecraft.client.multiplayer.ClientPacketListener
</summary>

```diff
+ void handleChunkBlocksUpdate(ClientboundChunkBlocksUpdatePacket)
- void handleChunkBlocksUpdate(ClientboundSectionBlocksUpdatePacket)
```

</details>
<details>
<summary>
net.minecraft.client.server.IntegratedServer
</summary>

```diff
- int getRateLimitPacketsPerSecond()
```

</details>
<details>
<summary>
net.minecraft.core.RegistryAccess$RegistryHolder
</summary>

```diff
- boolean lambda$null$3(Map$Entry)
- Codec captureMap(UnboundedMapCodec)
- Codec lambda$null$1(ResourceKey,MapCodec)
- Codec makeDirectCodec()
- DataResult getCodec(ResourceKey)
- DataResult lambda$getCodec$5(RegistryAccess$RegistryData)
- DataResult lambda$getCodec$6(ResourceKey)
- DataResult lambda$makeDirectCodec$0(MappedRegistry)
- DataResult lambda$makeDirectCodec$2(ResourceKey)
- Map access$000(RegistryAccess$RegistryHolder)
- Map lambda$captureMap$4(RegistryAccess$RegistryHolder)
- MappedRegistry createRegistry(ResourceKey)
+ MappedRegistry lambda$static$0(RegistryAccess$RegistryHolder)
+ Registry dimensionTypes()
- void <init>(Map)
+ void <init>(MappedRegistry)
+ void registerDimension(ResourceKey,DimensionType)
- WritableRegistry lambda$registry$7(MappedRegistry)
```

</details>
<details>
<summary>
net.minecraft.core.SectionPos
</summary>

```diff
- BlockPos relativeToBlockPos(short)
- int relativeToBlockX(short)
- int relativeToBlockY(short)
- int relativeToBlockZ(short)
- int sectionRelativeX(short)
- int sectionRelativeY(short)
- int sectionRelativeZ(short)
```

</details>
<details>
<summary>
net.minecraft.network.chat.CommonComponents
</summary>

```diff
- MutableComponent optionStatus(Component,boolean)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundBlockUpdatePacket
</summary>

```diff
- void <init>(BlockPos,BlockState)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundLevelChunkPacket
</summary>

```diff
+ ChunkBiomeContainer getBiomes()
- int[] getBiomes()
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.behavior.AcquirePoi
</summary>

```diff
+ AcquirePoi$JitteredLinearRetry lambda$start$4(PathfinderMob,long,long)
- AcquirePoi$JitteredLinearRetry lambda$start$5(PathfinderMob,long,long)
- void <init>(PoiType,MemoryModuleType,boolean,Optional)
+ void <init>(PoiType,MemoryModuleType,boolean)
- void <init>(PoiType,MemoryModuleType,MemoryModuleType,boolean,Optional)
+ void <init>(PoiType,MemoryModuleType,MemoryModuleType,boolean)
- void lambda$null$3(ServerLevel,PathfinderMob,Byte)
+ void lambda$start$3(PoiManager,BlockPos,PathfinderMob,ServerLevel,PoiType)
- void lambda$start$4(PoiManager,BlockPos,PathfinderMob,ServerLevel,PoiType)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.EnderMan$EndermanLookForPlayerGoal
</summary>

```diff
- void <init>(EnderMan,Predicate)
+ void <init>(EnderMan)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.piglin.Piglin
</summary>

```diff
+ void sendDebugPackets()
```

</details>
<details>
<summary>
net.minecraft.world.item.BoneMealItem
</summary>

```diff
+ InteractionResult useOn(UseOnContext)
- InteractionResult useOn(UseOnContext)
```

</details>
<details>
<summary>
net.minecraft.world.item.EndCrystalItem
</summary>

```diff
+ InteractionResult useOn(UseOnContext)
- InteractionResult useOn(UseOnContext)
```

</details>
<details>
<summary>
net.minecraft.world.item.FireChargeItem
</summary>

```diff
+ InteractionResult useOn(UseOnContext)
- InteractionResult useOn(UseOnContext)
```

</details>
<details>
<summary>
net.minecraft.world.item.FlintAndSteelItem
</summary>

```diff
+ InteractionResult useOn(UseOnContext)
- InteractionResult useOn(UseOnContext)
+ void lambda$useOn$0(UseOnContext,Player)
- void lambda$useOn$0(UseOnContext,Player)
+ void lambda$useOn$1(UseOnContext,Player)
- void lambda$useOn$1(UseOnContext,Player)
```

</details>
<details>
<summary>
net.minecraft.world.item.GameMasterBlockItem
</summary>

```diff
+ BlockState getPlacementState(BlockPlaceContext)
- BlockState getPlacementState(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.item.HoeItem
</summary>

```diff
+ InteractionResult useOn(UseOnContext)
- InteractionResult useOn(UseOnContext)
+ void lambda$useOn$0(UseOnContext,Player)
- void lambda$useOn$0(UseOnContext,Player)
```

</details>
<details>
<summary>
net.minecraft.world.item.LeadItem
</summary>

```diff
+ InteractionResult useOn(UseOnContext)
- InteractionResult useOn(UseOnContext)
```

</details>
<details>
<summary>
net.minecraft.world.item.MapItem
</summary>

```diff
+ InteractionResult useOn(UseOnContext)
- InteractionResult useOn(UseOnContext)
+ ItemStack lockMap(Level,ItemStack)
- void lockMap(Level,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.item.MinecartItem
</summary>

```diff
+ InteractionResult useOn(UseOnContext)
- InteractionResult useOn(UseOnContext)
```

</details>
<details>
<summary>
net.minecraft.world.item.StandingAndWallBlockItem
</summary>

```diff
+ BlockState getPlacementState(BlockPlaceContext)
- BlockState getPlacementState(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.BlockGetter
</summary>

```diff
- double getBlockFloorHeight(BlockPos)
- double getBlockFloorHeight(VoxelShape,Supplier)
- VoxelShape lambda$getBlockFloorHeight$2(BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.MultiNoiseBiomeSource
</summary>

```diff
- Biome lambda$defaultNether$10()
- Biome lambda$defaultNether$11()
- Biome lambda$defaultNether$12()
- Biome lambda$defaultNether$13()
- Biome lambda$defaultNether$9()
+ Float lambda$getNoiseBiome$11(Biome$ClimateParameters,Pair)
- Float lambda$getNoiseBiome$14(Biome$ClimateParameters,Pair)
+ Pair lambda$null$9(Biome,Biome$ClimateParameters)
+ Stream lambda$defaultNether$10(Biome)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.AbstractFurnaceBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.AnvilBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BambooBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BannerBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BaseCoralWallFanBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BaseFireBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
- boolean canBePlacedAt(Level,BlockPos,Direction)
+ boolean canBePlacedAt(LevelAccessor,BlockPos)
- boolean inPortalDimension(Level)
- boolean isPortal(Level,BlockPos,Direction)
+ boolean isPortal(LevelAccessor,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BaseRailBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BedBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BeehiveBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BellBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CarvedPumpkinBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.ChainBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.ChorusPlantBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.ConduitBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.DiodeBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.DispenserBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.EndRodBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.EnderChestBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.FaceAttachedHorizontalDirectionalBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.FenceBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.GrowingPlantBodyBlock
</summary>

```diff
+ boolean canBeReplaced(BlockState,BlockPlaceContext)
- boolean canBeReplaced(BlockState,BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.HugeMushroomBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.JigsawBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.KelpBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.LadderBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.Lantern
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.LecternBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.NetherPortalBlock
</summary>

```diff
+ BlockPattern$BlockPatternMatch getPortalShape(LevelAccessor,BlockPos)
+ boolean trySpawnPortal(LevelAccessor,BlockPos)
+ NetherPortalBlock$PortalShape isPortal(LevelAccessor,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.piston.PistonBaseBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
- BlockState getStateForPlacement(BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.BlockBehaviour
</summary>

```diff
+ boolean canBeReplaced(BlockState,BlockPlaceContext)
- boolean canBeReplaced(BlockState,BlockPlaceContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase
</summary>

```diff
+ boolean canBeReplaced(BlockPlaceContext)
- boolean canBeReplaced(BlockPlaceContext)
- boolean isFaceSturdy(BlockGetter,BlockPos,Direction,SupportType)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.pattern.BlockPattern$BlockPatternMatch
</summary>

```diff
+ BlockPattern$PortalInfo getPortalOutput(Direction,BlockPos,double,Vec3,double)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.GenerationStep$Decoration
</summary>

```diff
+ GenerationStep$Decoration byName(String)
+ GenerationStep$Decoration lambda$static$0(GenerationStep$Decoration)
+ String getName()
+ String getSerializedName()
+ void <init>(String,int,String)
- void <init>(String,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.carver.WorldCarver
</summary>

```diff
+ CarverConfiguration lambda$new$1(ConfiguredWorldCarver)
- ConfiguredWorldCarver configured(CarverConfiguration)
+ ConfiguredWorldCarver lambda$new$0(CarverConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.BastionFeature
</summary>

```diff
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,JigsawConfiguration)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,MultiJigsawConfiguration)
+ StructureFeature$StructureStartFactory getStartFactory()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.NetherFortressFeature$NetherBridgeStart
</summary>

```diff
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,NoneFeatureConfiguration)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,NoneFeatureConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.OceanMonumentFeature$OceanMonumentStart
</summary>

```diff
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,NoneFeatureConfiguration)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,NoneFeatureConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.PillagerOutpostFeature
</summary>

```diff
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,JigsawConfiguration)
+ boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,NoneFeatureConfiguration)
+ StructureFeature$StructureStartFactory getStartFactory()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.SeagrassFeature
</summary>

```diff
- boolean place(WorldGenLevel,ChunkGenerator,Random,BlockPos,ProbabilityFeatureConfiguration)
+ boolean place(WorldGenLevel,ChunkGenerator,Random,BlockPos,SeagrassFeatureConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.ShipwreckFeature$FeatureStart
</summary>

```diff
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,ShipwreckConfiguration)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,ShipwreckConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.ColumnFeatureConfiguration
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
+ App lambda$static$4(RecordCodecBuilder$Instance)
+ Integer lambda$null$0(ColumnFeatureConfiguration)
+ Integer lambda$null$1(ColumnFeatureConfiguration)
+ Integer lambda$null$2(ColumnFeatureConfiguration)
+ Integer lambda$null$3(ColumnFeatureConfiguration)
- UniformInt height()
- UniformInt lambda$null$0(ColumnFeatureConfiguration)
- UniformInt lambda$null$1(ColumnFeatureConfiguration)
- UniformInt reach()
+ void <init>(int,int,int,int)
- void <init>(UniformInt,UniformInt)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.DecoratedFeatureConfiguration
</summary>

```diff
+ ConfiguredFeature lambda$null$0(DecoratedFeatureConfiguration)
- Supplier lambda$null$0(DecoratedFeatureConfiguration)
+ void <init>(ConfiguredFeature,ConfiguredDecorator)
- void <init>(Supplier,ConfiguredDecorator)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.DeltaFeatureConfiguration
</summary>

```diff
- App lambda$static$4(RecordCodecBuilder$Instance)
+ App lambda$static$5(RecordCodecBuilder$Instance)
- BlockState contents()
- BlockState rim()
+ Integer lambda$null$2(DeltaFeatureConfiguration)
+ Integer lambda$null$3(DeltaFeatureConfiguration)
+ Integer lambda$null$4(DeltaFeatureConfiguration)
- UniformInt lambda$null$2(DeltaFeatureConfiguration)
- UniformInt lambda$null$3(DeltaFeatureConfiguration)
- UniformInt rimSize()
- UniformInt size()
+ void <init>(BlockState,BlockState,int,int,int)
- void <init>(BlockState,BlockState,UniformInt,UniformInt)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherFossilFeature$FeatureStart
</summary>

```diff
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,NoneFeatureConfiguration)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,NoneFeatureConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.OceanRuinFeature$OceanRuinStart
</summary>

```diff
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,OceanRuinConfiguration)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,OceanRuinConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.PoolElementStructurePiece
</summary>

```diff
+ void <init>(StructureManager,CompoundTag,StructurePieceType)
- void <init>(StructureManager,CompoundTag)
- void <init>(StructureManager,StructurePoolElement,BlockPos,int,Rotation,BoundingBox)
+ void <init>(StructurePieceType,StructureManager,StructurePoolElement,BlockPos,int,Rotation,BoundingBox)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.StructureStart$1
</summary>

```diff
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,MineshaftConfiguration)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
- void generatePieces(RegistryAccess,ChunkGenerator,StructureManager,int,int,Biome,MineshaftConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.surfacebuilders.SurfaceBuilder
</summary>

```diff
- ConfiguredSurfaceBuilder configured(SurfaceBuilderConfiguration)
+ ConfiguredSurfaceBuilder lambda$new$0(SurfaceBuilderConfiguration)
+ SurfaceBuilderConfiguration lambda$new$1(ConfiguredSurfaceBuilder)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.McRegionUpgrader
</summary>

```diff
+ void convertRegion(File,File,BiomeSource,int,int,ProgressListener)
- void convertRegion(RegistryAccess$RegistryHolder,File,File,BiomeSource,int,int,ProgressListener)
+ void convertRegions(File,Iterable,BiomeSource,int,int,ProgressListener)
- void convertRegions(RegistryAccess$RegistryHolder,File,Iterable,BiomeSource,int,int,ProgressListener)
```

</details>
</details>
<hr/>