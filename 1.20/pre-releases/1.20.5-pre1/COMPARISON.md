## Comparison with [24w14a](https://github.com/PixiGeko/Minecraft-generated-data/tree/24w14a)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Translations](#translations)
> - [File structure](#file-structure)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">24w14a</th><th>1.20.5-pre1</th></tr><tr><td>DataPack version</td><td><pre>38</pre></td><td><pre>39</pre></td></tr><tr><td>World version</td><td><pre>3827</pre></td><td><pre>3829</pre></td></tr><tr><td>Protocol version</td><td><pre>1073742008</pre></td><td><pre>1073742009</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
🗒️ List
</summary>

```diff
+ org.jcraft:jorbis V0.0.17
- org.lwjgl:lwjgl-freetype (natives-macos-patch) V3.3.3
+ org.lwjgl:lwjgl-freetype (natives-macos) V3.3.3
```

</details>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">24w14a</th><th>1.20.5-pre1</th></tr><tr><td>com.mojang:authlib</td><td><pre>6.0.52</pre></td><td><pre>6.0.54</pre></td></tr><tr><td>com.mojang:datafixerupper</td><td><pre>7.0.13</pre></td><td><pre>7.0.14</pre></td></tr></table>
</details>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
item_sub_predicate_type
</summary>

```diff
+ minecraft:attribute_modifiers
+ minecraft:bundle_contents
+ minecraft:container
+ minecraft:firework_explosion
+ minecraft:fireworks
+ minecraft:trim
+ minecraft:writable_book_content
+ minecraft:written_book_content
```

</details>
<details>
<summary>
loot_function_type
</summary>

```diff
+ minecraft:filtered
+ minecraft:modify_contents
+ minecraft:set_custom_model_data
+ minecraft:set_item
```

</details>
</details>
<hr/>
<details><summary><b><ins>TAGS</ins></b><a name="tags"></a></summary>
<br/>
<details>
<summary>
universal_tags/item_sub_predicate_type.json
</summary>

```diff
+ minecraft:attribute_modifiers
+ minecraft:bundle_contents
+ minecraft:container
+ minecraft:firework_explosion
+ minecraft:fireworks
+ minecraft:trim
+ minecraft:writable_book_content
+ minecraft:written_book_content
```

</details>
<details>
<summary>
universal_tags/loot_function_type.json
</summary>

```diff
+ minecraft:filtered
+ minecraft:modify_contents
+ minecraft:set_custom_model_data
+ minecraft:set_item
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
+ advancements.adventure.brush_armadillo.description: Get Armadillo Scutes from an Armadillo using a Brush
+ advancements.adventure.brush_armadillo.title: Isn't it Scute?
+ advancements.adventure.revaulting.description: Unlock an Ominous Vault with an Ominous Trial Key
+ advancements.adventure.revaulting.title: Revaulting
+ advancements.husbandry.remove_wolf_armor.description: Remove Wolf Armor from a Wolf using Shears
+ advancements.husbandry.remove_wolf_armor.title: Snip it!
+ advancements.husbandry.repair_wolf_armor.description: Repair a damaged Wolf Armor using Armadillo Scutes
+ advancements.husbandry.repair_wolf_armor.title: Good as New
+ advancements.husbandry.whole_pack.description: Tame one of each Wolf variant
+ advancements.husbandry.whole_pack.title: The Whole Pack
+ arguments.item.malformed: Malformed item: '%s'
+ block.minecraft.banner.flow.black: Black Flow
+ block.minecraft.banner.flow.blue: Blue Flow
+ block.minecraft.banner.flow.brown: Brown Flow
+ block.minecraft.banner.flow.cyan: Cyan Flow
+ block.minecraft.banner.flow.gray: Gray Flow
+ block.minecraft.banner.flow.green: Green Flow
+ block.minecraft.banner.flow.light_blue: Light Blue Flow
+ block.minecraft.banner.flow.light_gray: Light Gray Flow
+ block.minecraft.banner.flow.lime: Lime Flow
+ block.minecraft.banner.flow.magenta: Magenta Flow
+ block.minecraft.banner.flow.orange: Orange Flow
+ block.minecraft.banner.flow.pink: Pink Flow
+ block.minecraft.banner.flow.purple: Purple Flow
+ block.minecraft.banner.flow.red: Red Flow
+ block.minecraft.banner.flow.white: White Flow
+ block.minecraft.banner.flow.yellow: Yellow Flow
+ block.minecraft.banner.guster.black: Black Guster
+ block.minecraft.banner.guster.blue: Blue Guster
+ block.minecraft.banner.guster.brown: Brown Guster
+ block.minecraft.banner.guster.cyan: Cyan Guster
+ block.minecraft.banner.guster.gray: Gray Guster
+ block.minecraft.banner.guster.green: Green Guster
+ block.minecraft.banner.guster.light_blue: Light Blue Guster
+ block.minecraft.banner.guster.light_gray: Light Gray Guster
+ block.minecraft.banner.guster.lime: Lime Guster
+ block.minecraft.banner.guster.magenta: Magenta Guster
+ block.minecraft.banner.guster.orange: Orange Guster
+ block.minecraft.banner.guster.pink: Pink Guster
+ block.minecraft.banner.guster.purple: Purple Guster
+ block.minecraft.banner.guster.red: Red Guster
+ block.minecraft.banner.guster.white: White Guster
+ block.minecraft.banner.guster.yellow: Yellow Guster
+ particle.invalidOptions: Can't parse particle options: %s
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
+ minecraft/advancements/adventure/brush_armadillo.json
+ minecraft/advancements/husbandry/remove_wolf_armor.json
+ minecraft/advancements/husbandry/repair_wolf_armor.json
+ minecraft/advancements/husbandry/whole_pack.json
+ minecraft/datapacks/update_1_21/data/minecraft/advancements/adventure/revaulting.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/equipment/trial_chamber_melee.json
+ minecraft/datapacks/update_1_21/data/minecraft/loot_tables/equipment/trial_chamber_ranged.json
+ minecraft/datapacks/update_1_21/data/minecraft/tags/enchantment/tooltip_order.json
+ minecraft/datapacks/update_1_21/data/minecraft/tags/entity_types/punchable_projectiles.json
+ minecraft/datapacks/update_1_21/data/minecraft/tags/items/breaks_decorated_pots.json
- minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/trial_chambers/chamber/addon/c6.json
+ minecraft/datapacks/update_1_21/data/minecraft/worldgen/template_pool/trial_chambers/chamber/assembly.json
+ minecraft/loot_tables/equipment/trial_chamber_melee.json
+ minecraft/loot_tables/equipment/trial_chamber_ranged.json
- minecraft/structures/trial_chambers/chamber/addon/c6_chest.nbt
- minecraft/structures/trial_chambers/chamber/addon/c6_column_full.nbt
- minecraft/structures/trial_chambers/chamber/addon/c6_column_tall_wide.nbt
- minecraft/structures/trial_chambers/chamber/addon/c6_column_tall.nbt
- minecraft/structures/trial_chambers/chamber/addon/c6_cover_long.nbt
- minecraft/structures/trial_chambers/chamber/addon/c6_cover_short.nbt
- minecraft/structures/trial_chambers/chamber/addon/c6_cover_small_1.nbt
- minecraft/structures/trial_chambers/chamber/addon/c6_cover_small_2.nbt
- minecraft/structures/trial_chambers/chamber/addon/c6_cover_small_3.nbt
- minecraft/structures/trial_chambers/chamber/addon/c6_cover_small.nbt
- minecraft/structures/trial_chambers/chamber/addon/c6_cover.nbt
- minecraft/structures/trial_chambers/chamber/addon/c6_melee_spawner.nbt
- minecraft/structures/trial_chambers/chamber/addon/c6_ranged_column_short_wide.nbt
- minecraft/structures/trial_chambers/chamber/addon/c6_ranged_column_short.nbt
- minecraft/structures/trial_chambers/chamber/addon/c6_stairs.nbt
- minecraft/structures/trial_chambers/chamber/addon/c6_wide_platform.nbt
+ minecraft/structures/trial_chambers/chamber/assembly.nbt
+ minecraft/structures/trial_chambers/chamber/assembly/cover_1.nbt
+ minecraft/structures/trial_chambers/chamber/assembly/cover_2.nbt
+ minecraft/structures/trial_chambers/chamber/assembly/cover_3.nbt
+ minecraft/structures/trial_chambers/chamber/assembly/cover_4.nbt
+ minecraft/structures/trial_chambers/chamber/assembly/cover_5.nbt
+ minecraft/structures/trial_chambers/chamber/assembly/cover_6.nbt
+ minecraft/structures/trial_chambers/chamber/assembly/full_column.nbt
+ minecraft/structures/trial_chambers/chamber/assembly/hanging_1.nbt
+ minecraft/structures/trial_chambers/chamber/assembly/hanging_2.nbt
+ minecraft/structures/trial_chambers/chamber/assembly/hanging_3.nbt
+ minecraft/structures/trial_chambers/chamber/assembly/hanging_4.nbt
+ minecraft/structures/trial_chambers/chamber/assembly/left_staircase_1.nbt
+ minecraft/structures/trial_chambers/chamber/assembly/left_staircase_2.nbt
+ minecraft/structures/trial_chambers/chamber/assembly/left_staircase_3.nbt
+ minecraft/structures/trial_chambers/chamber/assembly/platform_1.nbt
+ minecraft/structures/trial_chambers/chamber/assembly/right_staircase_1.nbt
+ minecraft/structures/trial_chambers/chamber/assembly/right_staircase_2.nbt
+ minecraft/structures/trial_chambers/chamber/assembly/right_staircase_3.nbt
+ minecraft/structures/trial_chambers/chamber/assembly/spawner_1.nbt
+ minecraft/structures/trial_chambers/chamber/assembly/spawner_trap_1.nbt
- minecraft/structures/trial_chambers/chamber/chamber_6.nbt
+ minecraft/structures/trial_chambers/dispensers/floor_dispenser.nbt
+ minecraft/structures/trial_chambers/dispensers/wall_dispenser.nbt
+ minecraft/structures/trial_chambers/intersection/intersection_3.nbt
+ minecraft/tags/enchantment/tooltip_order.json
+ minecraft/tags/entity_types/punchable_projectiles.json
- minecraft/tags/items/tools.json
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
- XXX.advancements.critereon.CollectionContentsPredicate
- XXX.advancements.critereon.CollectionContentsPredicate$Single
- XXX.advancements.critereon.CollectionCountsPredicate
- XXX.advancements.critereon.CollectionCountsPredicate$Multiple
- XXX.advancements.critereon.CollectionCountsPredicate$Zero
- XXX.advancements.critereon.ItemAttributeModifiersPredicate$EntryPredicate
- XXX.advancements.critereon.ItemContainerPredicate
- XXX.advancements.critereon.ItemFireworkExplosionPredicate
- XXX.advancements.critereon.ItemFireworksPredicate
+ XXX.advancements.critereon.ItemPotionsPredicate
- XXX.advancements.critereon.ItemPredicate
+ XXX.advancements.critereon.ItemPredicate$Builder
- XXX.advancements.critereon.ItemSubPredicate
+ XXX.advancements.critereon.ItemSubPredicate$Type
- XXX.advancements.critereon.ItemSubPredicates
- XXX.advancements.critereon.ItemWritableBookPredicate
- XXX.advancements.critereon.ItemWrittenBookPredicate
+ XXX.advancements.packs.package-info
+ XXX.advancements.packs.UpdateOneTwentyOneAdvancementProvider
- XXX.advancements.packs.UpdateOneTwentyOneAdventureAdvancements
+ XXX.advancements.packs.VanillaAdvancementProvider
- XXX.advancements.packs.VanillaAdventureAdvancements
+ XXX.advancements.packs.VanillaHusbandryAdvancements
- XXX.advancements.packs.VanillaNetherAdvancements
+ XXX.advancements.packs.VanillaStoryAdvancements
- XXX.advancements.packs.VanillaTheEndAdvancements
- XXX.block.entity.EnchantingTableBlockEntity
+ XXX.block.entity.EnchantmentTableBlockEntity
- XXX.commands.data.BlockDataAccessor
+ XXX.commands.data.BlockDataAccessor$1
- XXX.commands.data.DataAccessor
+ XXX.commands.data.DataCommands
- XXX.commands.data.DataCommands$DataManipulator
+ XXX.commands.data.DataCommands$DataManipulatorDecorator
- XXX.commands.data.DataCommands$DataProvider
+ XXX.commands.data.DataCommands$StringProcessor
- XXX.commands.data.EntityDataAccessor
+ XXX.commands.data.EntityDataAccessor$1
- XXX.commands.data.package-info
- XXX.commands.data.StorageDataAccessor
+ XXX.commands.data.StorageDataAccessor$1
- XXX.common.custom.BeeDebugPayload
+ XXX.common.custom.BeeDebugPayload$BeeInfo
- XXX.common.custom.BrainDebugPayload
+ XXX.common.custom.BrainDebugPayload$BrainDump
- XXX.common.custom.BrandPayload
+ XXX.common.custom.BreezeDebugPayload
- XXX.common.custom.BreezeDebugPayload$BreezeInfo
+ XXX.common.custom.CustomPacketPayload
- XXX.common.custom.CustomPacketPayload$1
+ XXX.common.custom.CustomPacketPayload$FallbackProvider
- XXX.common.custom.CustomPacketPayload$Type
+ XXX.common.custom.CustomPacketPayload$TypeAndCodec
- XXX.common.custom.DiscardedPayload
+ XXX.common.custom.GameEventDebugPayload
- XXX.common.custom.GameEventListenerDebugPayload
+ XXX.common.custom.GameTestAddMarkerDebugPayload
- XXX.common.custom.GameTestClearMarkersDebugPayload
+ XXX.common.custom.GoalDebugPayload
- XXX.common.custom.GoalDebugPayload$DebugGoal
+ XXX.common.custom.HiveDebugPayload
- XXX.common.custom.HiveDebugPayload$HiveInfo
+ XXX.common.custom.NeighborUpdatesDebugPayload
+ XXX.common.custom.package-info
- XXX.common.custom.PathfindingDebugPayload
+ XXX.common.custom.PoiAddedDebugPayload
- XXX.common.custom.PoiRemovedDebugPayload
+ XXX.common.custom.PoiTicketCountDebugPayload
- XXX.common.custom.RaidsDebugPayload
+ XXX.common.custom.StructuresDebugPayload
- XXX.common.custom.StructuresDebugPayload$PieceInfo
+ XXX.common.custom.VillageSectionsDebugPayload
- XXX.common.custom.WorldGenAttemptDebugPayload
- XXX.core.component.DataComponentMap$3
+ XXX.core.component.DataComponentMap$Builder
- XXX.core.component.DataComponentMap$Builder$SimpleMap
+ XXX.core.component.DataComponentPatch
- XXX.core.component.DataComponentPatch$1
+ XXX.core.component.DataComponentPatch$Builder
- XXX.core.component.DataComponentPatch$PatchKey
+ XXX.core.component.DataComponentPatch$SplitResult
- XXX.core.component.DataComponentPredicate
+ XXX.core.component.DataComponentPredicate$Builder
+ XXX.core.component.DataComponents
- XXX.core.component.DataComponentType
+ XXX.core.component.DataComponentType$Builder
- XXX.core.component.DataComponentType$Builder$SimpleType
+ XXX.core.component.package-info
- XXX.core.component.PatchedDataComponentMap
+ XXX.core.component.TypedDataComponent
- XXX.core.component.TypedDataComponent$1
- XXX.core.dispenser.BlockSource
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
- XXX.core.dispenser.DispenseItemBehavior$2
+ XXX.core.dispenser.DispenseItemBehavior$3
- XXX.core.dispenser.DispenseItemBehavior$4
+ XXX.core.dispenser.DispenseItemBehavior$5
- XXX.core.dispenser.DispenseItemBehavior$6
+ XXX.core.dispenser.DispenseItemBehavior$7
- XXX.core.dispenser.DispenseItemBehavior$8
+ XXX.core.dispenser.DispenseItemBehavior$9
- XXX.core.dispenser.OptionalDispenseItemBehavior
- XXX.core.dispenser.package-info
+ XXX.core.dispenser.ProjectileDispenseBehavior
- XXX.core.dispenser.ShearsDispenseItemBehavior
+ XXX.core.dispenser.ShulkerBoxDispenseBehavior
- XXX.core.particles.BlockParticleOption
+ XXX.core.particles.BlockParticleOption$1
+ XXX.core.particles.ColorParticleOption$1
- XXX.core.particles.DustColorTransitionOptions
+ XXX.core.particles.DustColorTransitionOptions$1
+ XXX.core.particles.DustParticleOptions$1
- XXX.core.particles.DustParticleOptionsBase
+ XXX.core.particles.ItemParticleOption
+ XXX.core.particles.package-info
+ XXX.core.particles.ParticleOptions$Deserializer
- XXX.core.particles.ParticleType
+ XXX.core.particles.ParticleTypes
- XXX.core.particles.ParticleTypes$1
+ XXX.core.particles.SculkChargeParticleOptions
+ XXX.core.particles.SimpleParticleType
- XXX.core.registries.BuiltInRegistries
+ XXX.core.registries.BuiltInRegistries$RegistryBootstrap
+ XXX.core.registries.package-info
- XXX.core.registries.Registries
- XXX.data.advancements.AdvancementProvider
+ XXX.data.advancements.AdvancementSubProvider
- XXX.data.advancements.package-info
- XXX.data.info.BiomeParametersDumpReport
+ XXX.data.info.BlockListReport
- XXX.data.info.CommandsReport
+ XXX.data.info.ItemListReport
+ XXX.data.info.package-info
- XXX.data.info.RegistryDumpReport
- XXX.data.loot.BlockLootSubProvider
+ XXX.data.loot.EntityLootSubProvider
- XXX.data.loot.LootTableProvider
+ XXX.data.loot.LootTableProvider$SubProviderEntry
- XXX.data.loot.LootTableSubProvider
+ XXX.data.loot.package-info
- XXX.data.metadata.package-info
+ XXX.data.metadata.PackMetadataGenerator
+ XXX.data.models.BlockModelGenerators
- XXX.data.models.BlockModelGenerators$1
+ XXX.data.models.BlockModelGenerators$BlockEntityModelGenerator
- XXX.data.models.BlockModelGenerators$BlockFamilyProvider
+ XXX.data.models.BlockModelGenerators$BlockStateGeneratorSupplier
- XXX.data.models.BlockModelGenerators$BookSlotModelCacheKey
+ XXX.data.models.BlockModelGenerators$TintState
- XXX.data.models.BlockModelGenerators$WoodProvider
+ XXX.data.models.ItemModelGenerators
- XXX.data.models.ItemModelGenerators$TrimModelData
+ XXX.data.models.ModelProvider
+ XXX.data.models.package-info
- XXX.data.recipes.package-info
+ XXX.data.recipes.RecipeBuilder
- XXX.data.recipes.RecipeBuilder$1
+ XXX.data.recipes.RecipeCategory
- XXX.data.recipes.RecipeOutput
+ XXX.data.recipes.RecipeProvider
- XXX.data.recipes.RecipeProvider$1
+ XXX.data.recipes.ShapedRecipeBuilder
- XXX.data.recipes.ShapelessRecipeBuilder
+ XXX.data.recipes.SimpleCookingRecipeBuilder
- XXX.data.recipes.SingleItemRecipeBuilder
+ XXX.data.recipes.SmithingTransformRecipeBuilder
- XXX.data.recipes.SmithingTrimRecipeBuilder
+ XXX.data.recipes.SpecialRecipeBuilder
- XXX.data.registries.package-info
- XXX.data.registries.RegistriesDatapackGenerator
+ XXX.data.registries.RegistryPatchGenerator
- XXX.data.registries.UpdateOneTwentyOneRegistries
+ XXX.data.registries.VanillaRegistries
+ XXX.data.structures.NbtToSnbt
- XXX.data.structures.package-info
- XXX.data.structures.SnbtDatafixer
+ XXX.data.structures.SnbtToNbt
- XXX.data.structures.SnbtToNbt$Filter
+ XXX.data.structures.SnbtToNbt$StructureConversionException
- XXX.data.structures.SnbtToNbt$TaskResult
+ XXX.data.structures.StructureUpdater
+ XXX.data.tags.BannerPatternTagsProvider
- XXX.data.tags.BiomeTagsProvider
+ XXX.data.tags.CatVariantTagsProvider
- XXX.data.tags.DamageTypeTagsProvider
- XXX.data.tags.UpdateOneTwentyOneEntityTypeTagsProvider
+ XXX.data.tags.UpdateOneTwentyOneItemTagsProvider
- XXX.data.tags.UpdateOneTwentyOneStructureTagsProvider
+ XXX.data.tags.VanillaBlockTagsProvider
- XXX.data.tags.VanillaEnchantmentTagsProvider
- XXX.datafix.fixes.EmptyItemInVillagerTradeFix
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
- XXX.datafix.fixes.FixProjectileStoredItem
+ XXX.datafix.fixes.FixProjectileStoredItem$SubFixer
- XXX.datafix.fixes.ForcePoiRebuild
+ XXX.datafix.fixes.FurnaceRecipeFix
- XXX.datafix.fixes.GoatHornIdFix
+ XXX.datafix.fixes.GossipUUIDFix
- XXX.datafix.fixes.HeightmapRenamingFix
+ XXX.datafix.fixes.HorseBodyArmorItemFix
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
- XXX.datafix.fixes.ItemStackComponentizationFix
+ XXX.datafix.fixes.ItemStackComponentizationFix$ItemStackData
+ XXX.datafix.fixes.ItemStackComponentRemainderFix
- XXX.datafix.fixes.ItemStackCustomNameToOverrideComponentFix
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
- XXX.datafix.fixes.LegacyDragonFightFix
+ XXX.datafix.fixes.LevelDataGeneratorOptionsFix
- XXX.datafix.fixes.LevelFlatGeneratorInfoFix
+ XXX.datafix.fixes.LevelLegacyWorldGenSettingsFix
- XXX.datafix.fixes.LevelUUIDFix
+ XXX.datafix.fixes.LodestoneCompassComponentFix
- XXX.datafix.fixes.MapBannerBlockPosFormatFix
+ XXX.datafix.fixes.MapIdFix
- XXX.datafix.fixes.MemoryExpiryDataFix
+ XXX.datafix.fixes.MissingDimensionFix
- XXX.datafix.fixes.MobEffectIdFix
+ XXX.datafix.fixes.MobSpawnerEntityIdentifiersFix
- XXX.datafix.fixes.NamedEntityFix
+ XXX.datafix.fixes.NamedEntityWriteReadFix
- XXX.datafix.fixes.NamespacedTypeRenameFix
+ XXX.datafix.fixes.NewVillageFix
- XXX.datafix.fixes.ObjectiveDisplayNameFix
+ XXX.datafix.fixes.ObjectiveRenderTypeFix
- XXX.datafix.fixes.OminousBannerBlockEntityRenameFix
+ XXX.datafix.fixes.OminousBannerRenameFix
- XXX.datafix.fixes.OptionsAccessibilityOnboardFix
+ XXX.datafix.fixes.OptionsAddTextBackgroundFix
- XXX.datafix.fixes.OptionsAmbientOcclusionFix
+ XXX.datafix.fixes.OptionsForceVBOFix
- XXX.datafix.fixes.OptionsKeyLwjgl3Fix
+ XXX.datafix.fixes.OptionsKeyTranslationFix
- XXX.datafix.fixes.OptionsLowerCaseLanguageFix
+ XXX.datafix.fixes.OptionsProgrammerArtFix
- XXX.datafix.fixes.OptionsRenameFieldFix
+ XXX.datafix.fixes.OverreachingTickFix
- XXX.datafix.fixes.ParticleUnflatteningFix
+ XXX.datafix.schemas.package-info
- XXX.datafix.schemas.V3825
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
+ XXX.entity.decoration.ItemFrame$2
- XXX.entity.decoration.LeashFenceKnotEntity
- XXX.entity.decoration.package-info
+ XXX.entity.decoration.Painting
- XXX.entity.decoration.PaintingVariant
+ XXX.entity.decoration.PaintingVariants
+ XXX.entity.item.FallingBlockEntity
- XXX.entity.item.ItemEntity
+ XXX.entity.item.ItemEntity$1
+ XXX.item.alchemy.Potion
- XXX.item.alchemy.PotionBrewing
+ XXX.jfr.callback.package-info
- XXX.jfr.callback.ProfiledDuration
- XXX.jfr.event.ChunkGenerationEvent
+ XXX.jfr.event.ChunkGenerationEvent$Fields
- XXX.jfr.event.ChunkRegionIoEvent
+ XXX.jfr.event.ChunkRegionIoEvent$Fields
- XXX.jfr.event.ChunkRegionReadEvent
+ XXX.jfr.event.ChunkRegionWriteEvent
- XXX.jfr.event.NetworkSummaryEvent
+ XXX.jfr.event.NetworkSummaryEvent$Fields
- XXX.jfr.event.NetworkSummaryEvent$SumAggregation
- XXX.jfr.event.package-info
+ XXX.jfr.event.PacketEvent
- XXX.jfr.event.PacketEvent$Fields
+ XXX.jfr.event.PacketReceivedEvent
- XXX.jfr.event.PacketSentEvent
+ XXX.jfr.event.ServerTickTimeEvent
- XXX.jfr.event.ServerTickTimeEvent$Fields
+ XXX.jfr.event.WorldLoadFinishedEvent
- XXX.jfr.parse.JfrStatsParser
+ XXX.jfr.parse.JfrStatsParser$1
- XXX.jfr.parse.JfrStatsParser$MutableCountAndSize
+ XXX.jfr.parse.JfrStatsResult
- XXX.jfr.parse.package-info
+ XXX.jfr.serialize.JfrResultJsonSerializer
- XXX.jfr.serialize.package-info
+ XXX.jfr.stats.ChunkGenStat
- XXX.jfr.stats.ChunkIdentification
+ XXX.jfr.stats.CpuLoadStat
- XXX.jfr.stats.FileIOStat
+ XXX.jfr.stats.FileIOStat$Summary
- XXX.jfr.stats.GcHeapStat
+ XXX.jfr.stats.GcHeapStat$Summary
- XXX.jfr.stats.GcHeapStat$Timing
+ XXX.jfr.stats.IoSummary
- XXX.jfr.stats.IoSummary$CountAndSize
+ XXX.jfr.stats.package-info
+ XXX.jfr.stats.PacketIdentification
- XXX.jfr.stats.ThreadAllocationStat
+ XXX.jfr.stats.ThreadAllocationStat$Summary
- XXX.jfr.stats.TickTimeStat
+ XXX.jfr.stats.TimedStat
- XXX.jfr.stats.TimedStatSummary
+ XXX.level.progress.ChunkProgressListener
- XXX.level.progress.ChunkProgressListenerFactory
+ XXX.level.progress.LoggerChunkProgressListener
- XXX.level.progress.package-info
- XXX.level.progress.ProcessorChunkProgressListener
+ XXX.level.progress.StoringChunkProgressListener
+ XXX.level.storage.package-info
- XXX.level.timers.FunctionCallback
+ XXX.level.timers.FunctionCallback$Serializer
- XXX.level.timers.FunctionTagCallback
+ XXX.level.timers.FunctionTagCallback$Serializer
+ XXX.level.timers.package-info
- XXX.level.timers.TimerCallback
+ XXX.level.timers.TimerCallback$Serializer
- XXX.level.timers.TimerCallbacks
+ XXX.level.timers.TimerQueue
- XXX.level.timers.TimerQueue$Event
- XXX.level.validation.ContentValidationException
+ XXX.level.validation.DirectoryValidator
- XXX.level.validation.DirectoryValidator$1
+ XXX.level.validation.ForbiddenSymlinkInfo
+ XXX.level.validation.package-info
- XXX.level.validation.PathAllowList
+ XXX.level.validation.PathAllowList$ConfigEntry
- XXX.level.validation.PathAllowList$EntryType
- XXX.login.custom.CustomQueryAnswerPayload
+ XXX.login.custom.CustomQueryPayload
- XXX.login.custom.DiscardedQueryAnswerPayload
+ XXX.login.custom.DiscardedQueryPayload
- XXX.login.custom.package-info
+ XXX.loot.entries.AlternativesEntry
- XXX.loot.entries.AlternativesEntry$Builder
+ XXX.loot.entries.ComposableEntryContainer
- XXX.loot.entries.CompositeEntryBase
+ XXX.loot.entries.CompositeEntryBase$CompositeEntryConstructor
- XXX.loot.entries.DynamicLoot
+ XXX.loot.entries.EmptyLootItem
- XXX.loot.entries.EntryGroup
+ XXX.loot.entries.EntryGroup$Builder
- XXX.loot.entries.LootItem
+ XXX.loot.entries.LootPoolEntries
- XXX.loot.entries.LootPoolEntry
+ XXX.loot.entries.LootPoolEntryContainer
- XXX.loot.entries.LootPoolEntryContainer$Builder
+ XXX.loot.entries.LootPoolEntryType
- XXX.loot.entries.LootPoolSingletonContainer
+ XXX.loot.entries.LootPoolSingletonContainer$1
- XXX.loot.entries.LootPoolSingletonContainer$Builder
+ XXX.loot.entries.LootPoolSingletonContainer$DummyBuilder
- XXX.loot.entries.LootPoolSingletonContainer$EntryBase
+ XXX.loot.entries.LootPoolSingletonContainer$EntryConstructor
- XXX.loot.entries.NestedLootTable
+ XXX.loot.entries.package-info
+ XXX.loot.entries.SequentialEntry
- XXX.loot.entries.SequentialEntry$Builder
+ XXX.loot.entries.TagEntry
- XXX.loot.entries.TagEntry$1
- XXX.loot.functions.ApplyBonusCount
+ XXX.loot.functions.ApplyBonusCount$BinomialWithBonusCount
- XXX.loot.functions.ApplyBonusCount$Formula
+ XXX.loot.functions.ApplyBonusCount$FormulaType
- XXX.loot.functions.ApplyBonusCount$OreDrops
+ XXX.loot.functions.ApplyBonusCount$UniformBonusCount
- XXX.loot.functions.ApplyExplosionDecay
+ XXX.loot.functions.CopyBlockState
- XXX.loot.functions.CopyBlockState$Builder
+ XXX.loot.functions.CopyComponentsFunction
- XXX.loot.functions.CopyComponentsFunction$Builder
+ XXX.loot.functions.CopyComponentsFunction$Source
- XXX.loot.functions.CopyCustomDataFunction
+ XXX.loot.functions.CopyCustomDataFunction$Builder
- XXX.loot.functions.CopyCustomDataFunction$CopyOperation
+ XXX.loot.functions.CopyCustomDataFunction$MergeStrategy
- XXX.loot.functions.CopyCustomDataFunction$MergeStrategy$1
+ XXX.loot.functions.CopyCustomDataFunction$MergeStrategy$2
- XXX.loot.functions.CopyCustomDataFunction$MergeStrategy$3
+ XXX.loot.functions.CopyNameFunction
- XXX.loot.functions.CopyNameFunction$NameSource
+ XXX.loot.functions.EnchantRandomlyFunction
- XXX.loot.functions.EnchantRandomlyFunction$Builder
+ XXX.loot.functions.EnchantWithLevelsFunction
- XXX.loot.functions.EnchantWithLevelsFunction$Builder
+ XXX.loot.functions.ExplorationMapFunction
- XXX.loot.functions.ExplorationMapFunction$Builder
+ XXX.loot.functions.FillPlayerHead
- XXX.loot.functions.FilteredFunction
+ XXX.loot.functions.package-info
- XXX.loot.functions.SequenceFunction
+ XXX.loot.functions.SetAttributesFunction
- XXX.loot.functions.SetAttributesFunction$Builder
+ XXX.loot.functions.SetAttributesFunction$Modifier
- XXX.loot.functions.SetAttributesFunction$ModifierBuilder
+ XXX.loot.functions.SetBannerPatternFunction
- XXX.loot.functions.SetBannerPatternFunction$Builder
+ XXX.loot.functions.SetBookCoverFunction
- XXX.loot.functions.SetComponentsFunction
+ XXX.loot.functions.SetContainerContents
- XXX.loot.functions.SetContainerContents$Builder
+ XXX.loot.functions.SetContainerLootTable
- XXX.loot.functions.SetCustomDataFunction
- XXX.loot.functions.SetLoreFunction
+ XXX.loot.functions.SetLoreFunction$Builder
- XXX.loot.functions.SetNameFunction
+ XXX.loot.functions.SetNameFunction$Target
- XXX.loot.functions.SetOminousBottleAmplifierFunction
+ XXX.loot.functions.SetPotionFunction
- XXX.loot.functions.SetStewEffectFunction
+ XXX.loot.functions.SetStewEffectFunction$Builder
- XXX.loot.functions.SetStewEffectFunction$EffectEntry
+ XXX.loot.functions.SetWritableBookPagesFunction
- XXX.loot.functions.SetWrittenBookPagesFunction
+ XXX.loot.functions.SmeltItemFunction
- XXX.loot.functions.ToggleTooltips
+ XXX.loot.functions.ToggleTooltips$ComponentToggle
- XXX.loot.functions.ToggleTooltips$TooltipWither
- XXX.loot.packs.package-info
- XXX.loot.packs.TradeRebalanceChestLoot
+ XXX.loot.packs.TradeRebalanceLootTableProvider
- XXX.loot.packs.UpdateOneTwentyOneBlockLoot
+ XXX.loot.packs.UpdateOneTwentyOneChestLoot
- XXX.loot.packs.UpdateOneTwentyOneEntityLoot
+ XXX.loot.packs.UpdateOneTwentyOneEquipmentLoot
- XXX.loot.packs.UpdateOneTwentyOneLootTableProvider
+ XXX.loot.packs.UpdateOneTwentyOneShearingLoot
- XXX.loot.packs.VanillaArchaeologyLoot
+ XXX.loot.packs.VanillaBlockLoot
- XXX.loot.packs.VanillaChestLoot
+ XXX.loot.packs.VanillaEntityLoot
- XXX.loot.packs.VanillaEquipmentLoot
+ XXX.loot.packs.VanillaFishingLoot
- XXX.loot.packs.VanillaGiftLoot
+ XXX.loot.packs.VanillaLootTableProvider
- XXX.loot.packs.VanillaPiglinBarterLoot
+ XXX.loot.packs.VanillaShearingLoot
+ XXX.loot.parameters.LootContextParam
+ XXX.loot.parameters.LootContextParams
- XXX.loot.parameters.LootContextParamSet
+ XXX.loot.parameters.LootContextParamSet$Builder
- XXX.loot.parameters.LootContextParamSets
- XXX.loot.parameters.package-info
+ XXX.loot.predicates.AllOfCondition
- XXX.loot.predicates.AllOfCondition$Builder
+ XXX.loot.predicates.AnyOfCondition
- XXX.loot.predicates.AnyOfCondition$Builder
+ XXX.loot.predicates.BonusLevelTableCondition
- XXX.loot.predicates.CompositeLootItemCondition
+ XXX.loot.predicates.CompositeLootItemCondition$Builder
- XXX.loot.predicates.ConditionReference
+ XXX.loot.predicates.ConditionUserBuilder
- XXX.loot.predicates.DamageSourceCondition
+ XXX.loot.predicates.EntityHasScoreCondition
- XXX.loot.predicates.EntityHasScoreCondition$Builder
+ XXX.loot.predicates.ExplosionCondition
- XXX.loot.predicates.InvertedLootItemCondition
+ XXX.loot.predicates.LocationCheck
- XXX.loot.predicates.LootItemBlockStatePropertyCondition
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition$Builder
- XXX.loot.predicates.LootItemCondition
+ XXX.loot.predicates.LootItemCondition$Builder
+ XXX.loot.predicates.LootItemConditions
- XXX.loot.predicates.LootItemConditionType
- XXX.loot.predicates.LootItemEntityPropertyCondition
+ XXX.loot.predicates.LootItemKilledByPlayerCondition
- XXX.loot.predicates.LootItemRandomChanceCondition
+ XXX.loot.predicates.LootItemRandomChanceWithLootingCondition
- XXX.loot.predicates.MatchTool
- XXX.loot.predicates.package-info
+ XXX.loot.predicates.TimeCheck
- XXX.loot.predicates.TimeCheck$Builder
+ XXX.loot.predicates.ValueCheckCondition
- XXX.loot.predicates.WeatherCheck
+ XXX.loot.predicates.WeatherCheck$Builder
- XXX.metadata.pack.package-info
+ XXX.metadata.pack.PackMetadataSection
+ XXX.metrics.profiling.ActiveMetricsRecorder
- XXX.metrics.profiling.InactiveMetricsRecorder
+ XXX.metrics.profiling.MetricsRecorder
- XXX.metrics.profiling.package-info
- XXX.metrics.profiling.ProfilerSamplerAdapter
+ XXX.metrics.profiling.ServerMetricsSamplersProvider
- XXX.metrics.profiling.ServerMetricsSamplersProvider$1
+ XXX.metrics.profiling.ServerMetricsSamplersProvider$CpuStats
+ XXX.metrics.storage.MetricsPersister
+ XXX.metrics.storage.package-info
- XXX.metrics.storage.RecordedDeviation
+ XXX.minecraft.core.package-info
- XXX.minecraft.data.BlockFamilies
+ XXX.minecraft.data.BlockFamily
- XXX.minecraft.data.BlockFamily$Builder
+ XXX.minecraft.data.BlockFamily$Variant
- XXX.minecraft.data.CachedOutput
+ XXX.minecraft.data.DataGenerator
- XXX.minecraft.data.DataGenerator$PackGenerator
+ XXX.minecraft.data.DataProvider
- XXX.minecraft.data.DataProvider$Factory
+ XXX.minecraft.data.HashCache
- XXX.minecraft.data.HashCache$1
+ XXX.minecraft.data.HashCache$CacheUpdater
- XXX.minecraft.data.HashCache$ProviderCache
+ XXX.minecraft.data.HashCache$ProviderCacheBuilder
- XXX.minecraft.data.HashCache$UpdateFunction
+ XXX.minecraft.data.HashCache$UpdateResult
- XXX.minecraft.data.Main
- XXX.minecraft.data.package-info
+ XXX.minecraft.data.PackOutput
- XXX.minecraft.data.PackOutput$PathProvider
+ XXX.minecraft.data.PackOutput$Target
+ XXX.minecraft.network.package-info
- XXX.minecraft.obfuscate.DontObfuscate
+ XXX.minecraft.obfuscate.package-info
+ XXX.minecraft.recipebook.package-info
+ XXX.minecraft.recipebook.PlaceRecipe
- XXX.minecraft.recipebook.ServerPlaceRecipe
- XXX.minecraft.references.Blocks
+ XXX.minecraft.references.Items
- XXX.minecraft.resources.DelegatingOps
+ XXX.minecraft.resources.FileToIdConverter
- XXX.minecraft.resources.HolderSetCodec
- XXX.minecraft.resources.package-info
+ XXX.minecraft.resources.RegistryDataLoader
- XXX.minecraft.resources.RegistryDataLoader$1
+ XXX.minecraft.resources.RegistryDataLoader$Loader
- XXX.minecraft.resources.RegistryDataLoader$LoadingFunction
+ XXX.minecraft.resources.RegistryDataLoader$RegistryData
- XXX.minecraft.resources.RegistryFileCodec
+ XXX.minecraft.resources.RegistryFixedCodec
- XXX.minecraft.resources.RegistryOps
+ XXX.minecraft.resources.RegistryOps$1
- XXX.minecraft.resources.RegistryOps$2
+ XXX.minecraft.resources.RegistryOps$RegistryInfo
- XXX.minecraft.resources.RegistryOps$RegistryInfoLookup
+ XXX.minecraft.resources.ResourceKey
- XXX.minecraft.resources.ResourceKey$InternKey
+ XXX.minecraft.resources.ResourceLocation
- XXX.minecraft.resources.ResourceLocation$Dummy
+ XXX.minecraft.resources.ResourceLocation$Serializer
+ XXX.minecraft.server.Bootstrap
- XXX.minecraft.server.Bootstrap$1
+ XXX.minecraft.server.ChainedJsonException
- XXX.minecraft.server.ChainedJsonException$Entry
+ XXX.minecraft.server.ConsoleInput
- XXX.minecraft.server.DebugLoggedPrintStream
+ XXX.minecraft.server.Eula
- XXX.minecraft.server.LoggedPrintStream
+ XXX.minecraft.server.Main
- XXX.minecraft.server.Main$1
+ XXX.minecraft.server.MinecraftServer
- XXX.minecraft.server.MinecraftServer$1
+ XXX.minecraft.server.MinecraftServer$ReloadableResources
- XXX.minecraft.server.MinecraftServer$ServerResourcePackInfo
+ XXX.minecraft.server.MinecraftServer$TimeProfiler
- XXX.minecraft.server.MinecraftServer$TimeProfiler$1
+ XXX.minecraft.server.package-info
+ XXX.minecraft.server.PlayerAdvancements
- XXX.minecraft.server.PlayerAdvancements$Data
+ XXX.minecraft.server.RegistryLayer
- XXX.minecraft.server.ReloadableServerRegistries
+ XXX.minecraft.server.ReloadableServerRegistries$EmptyTagLookupWrapper
- XXX.minecraft.server.ReloadableServerRegistries$Holder
+ XXX.minecraft.server.ReloadableServerResources
- XXX.minecraft.server.ReloadableServerResources$ConfigurableRegistryLookup
+ XXX.minecraft.server.ReloadableServerResources$ConfigurableRegistryLookup$1
- XXX.minecraft.server.ReloadableServerResources$MissingTagAccessPolicy
+ XXX.minecraft.server.RunningOnDifferentThreadException
- XXX.minecraft.server.ServerAdvancementManager
+ XXX.minecraft.server.ServerFunctionLibrary
- XXX.minecraft.server.ServerFunctionManager
+ XXX.minecraft.server.ServerInfo
- XXX.minecraft.server.ServerInterface
+ XXX.minecraft.server.ServerScoreboard
- XXX.minecraft.server.ServerScoreboard$Method
+ XXX.minecraft.server.ServerTickRateManager
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
- XXX.minecraft.tags.BannerPatternTags
+ XXX.minecraft.tags.BiomeTags
- XXX.minecraft.tags.BlockTags
+ XXX.minecraft.tags.CatVariantTags
- XXX.minecraft.tags.DamageTypeTags
- XXX.minecraft.util.NullOps$NullMapBuilder
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
+ XXX.minecraft.world.ItemInteractionResult
- XXX.minecraft.world.LockCode
+ XXX.minecraft.world.MenuProvider
- XXX.minecraft.world.Nameable
- XXX.minecraft.world.package-info
- XXX.minecraft.world.RandomizableContainer
+ XXX.minecraft.world.RandomSequence
- XXX.minecraft.world.RandomSequences
+ XXX.minecraft.world.RandomSequences$DirtyMarkingRandomSource
+ XXX.minecraft.world.SimpleContainer
- XXX.minecraft.world.SimpleMenuProvider
+ XXX.minecraft.world.TickRateManager
- XXX.minecraft.world.WorldlyContainer
+ XXX.minecraft.world.WorldlyContainerHolder
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
- XXX.models.model.ModelTemplate$JsonFactory
+ XXX.models.model.ModelTemplates
- XXX.models.model.package-info
- XXX.models.model.TexturedModel
+ XXX.models.model.TexturedModel$Provider
- XXX.models.model.TextureMapping
+ XXX.models.model.TextureSlot
+ XXX.monitoring.jmx.MinecraftServerStatistics
- XXX.monitoring.jmx.MinecraftServerStatistics$AttributeDescription
+ XXX.monitoring.jmx.package-info
- XXX.network.codec.ByteBufCodecs$3
+ XXX.network.codec.ByteBufCodecs$4
- XXX.network.codec.ByteBufCodecs$5
+ XXX.network.codec.ByteBufCodecs$6
- XXX.network.codec.ByteBufCodecs$7
+ XXX.network.codec.ByteBufCodecs$8
- XXX.network.codec.ByteBufCodecs$9
+ XXX.network.codec.IdDispatchCodec
- XXX.network.codec.IdDispatchCodec$Builder
+ XXX.network.codec.IdDispatchCodec$Entry
- XXX.network.codec.package-info
- XXX.network.codec.StreamCodec
+ XXX.network.codec.StreamCodec$1
- XXX.network.codec.StreamCodec$10
+ XXX.network.codec.StreamCodec$11
- XXX.network.codec.StreamCodec$12
+ XXX.network.codec.StreamCodec$13
- XXX.network.codec.StreamCodec$2
+ XXX.network.codec.StreamCodec$3
- XXX.network.codec.StreamCodec$4
+ XXX.network.codec.StreamCodec$5
- XXX.network.codec.StreamCodec$6
+ XXX.network.codec.StreamCodec$7
- XXX.network.codec.StreamCodec$8
+ XXX.network.codec.StreamCodec$9
- XXX.network.codec.StreamCodec$CodecOperation
+ XXX.network.codec.StreamDecoder
- XXX.network.codec.StreamEncoder
+ XXX.network.codec.StreamMemberEncoder
- XXX.network.config.JoinWorldTask
+ XXX.network.config.package-info
+ XXX.network.config.ServerResourcePackConfigurationTask
- XXX.network.config.SynchronizeRegistriesTask
- XXX.network.protocol.BundleDelimiterPacket
+ XXX.network.protocol.BundlePacket
- XXX.network.protocol.BundlerInfo
+ XXX.network.protocol.BundlerInfo$1
- XXX.network.protocol.BundlerInfo$1$1
+ XXX.network.protocol.BundlerInfo$Bundler
- XXX.network.protocol.package-info
- XXX.network.protocol.Packet
+ XXX.network.protocol.PacketFlow
- XXX.network.protocol.PacketType
+ XXX.network.protocol.PacketUtils
- XXX.network.protocol.ProtocolCodecBuilder
+ XXX.network.protocol.ProtocolInfoBuilder
- XXX.network.protocol.ProtocolInfoBuilder$CodecEntry
+ XXX.network.protocol.ProtocolInfoBuilder$Implementation
- XXX.network.syncher.EntityDataAccessor
+ XXX.network.syncher.EntityDataSerializer
- XXX.network.syncher.EntityDataSerializer$ForValueType
+ XXX.network.syncher.EntityDataSerializers
- XXX.network.syncher.EntityDataSerializers$1
+ XXX.network.syncher.EntityDataSerializers$2
- XXX.network.syncher.EntityDataSerializers$3
+ XXX.network.syncher.EntityDataSerializers$4
+ XXX.network.syncher.package-info
- XXX.network.syncher.SyncedDataHolder
+ XXX.network.syncher.SynchedEntityData
- XXX.network.syncher.SynchedEntityData$Builder
+ XXX.network.syncher.SynchedEntityData$DataItem
- XXX.network.syncher.SynchedEntityData$DataValue
+ XXX.packrat.commands.Grammar
- XXX.packrat.commands.package-info
- XXX.packrat.commands.ResourceLocationParseRule
+ XXX.packrat.commands.ResourceLookupRule
- XXX.packrat.commands.ResourceSuggestion
+ XXX.packrat.commands.StringReaderParserState
- XXX.packrat.commands.StringReaderTerms
+ XXX.packrat.commands.StringReaderTerms$TerminalCharacter
- XXX.packrat.commands.StringReaderTerms$TerminalWord
+ XXX.packrat.commands.TagParseRule
- XXX.packs.linkfs.DummyFileAttributes
+ XXX.packs.linkfs.LinkFileSystem
- XXX.packs.linkfs.LinkFileSystem$Builder
+ XXX.packs.linkfs.LinkFileSystem$DirectoryEntry
+ XXX.packs.linkfs.LinkFSFileStore
- XXX.packs.linkfs.LinkFSPath
+ XXX.packs.linkfs.LinkFSPath$1
- XXX.packs.linkfs.LinkFSPath$2
+ XXX.packs.linkfs.LinkFSPath$3
- XXX.packs.linkfs.LinkFSProvider
+ XXX.packs.linkfs.LinkFSProvider$1
- XXX.packs.linkfs.LinkFSProvider$2
+ XXX.packs.linkfs.package-info
- XXX.packs.linkfs.PathContents
+ XXX.packs.linkfs.PathContents$1
- XXX.packs.linkfs.PathContents$2
+ XXX.packs.linkfs.PathContents$DirectoryContents
- XXX.packs.linkfs.PathContents$FileContents
- XXX.packs.metadata.MetadataSectionSerializer
+ XXX.packs.metadata.MetadataSectionType
- XXX.packs.metadata.MetadataSectionType$1
+ XXX.packs.metadata.package-info
+ XXX.packs.repository.BuiltInPackSource
- XXX.packs.repository.BuiltInPackSource$1
+ XXX.packs.repository.FolderRepositorySource
- XXX.packs.repository.FolderRepositorySource$FolderPackDetector
+ XXX.packs.repository.KnownPack
- XXX.packs.repository.Pack
+ XXX.packs.repository.Pack$Metadata
- XXX.packs.repository.Pack$Position
+ XXX.packs.repository.Pack$ResourcesSupplier
+ XXX.packs.repository.package-info
- XXX.packs.repository.PackCompatibility
+ XXX.packs.repository.PackDetector
- XXX.packs.repository.PackRepository
+ XXX.packs.repository.PackSource
- XXX.packs.repository.PackSource$1
+ XXX.packs.repository.RepositorySource
- XXX.packs.repository.ServerPacksSource
- XXX.packs.resources.CloseableResourceManager
+ XXX.packs.resources.FallbackResourceManager
- XXX.packs.resources.FallbackResourceManager$1ResourceWithSourceAndIndex
+ XXX.packs.resources.FallbackResourceManager$EntryStack
- XXX.packs.resources.FallbackResourceManager$LeakedResourceWarningInputStream
+ XXX.packs.resources.FallbackResourceManager$PackEntry
- XXX.packs.resources.FallbackResourceManager$ResourceWithSource
+ XXX.packs.resources.IoSupplier
- XXX.packs.resources.MultiPackResourceManager
+ XXX.packs.resources.package-info
+ XXX.packs.resources.PreparableReloadListener
- XXX.packs.resources.PreparableReloadListener$PreparationBarrier
+ XXX.packs.resources.ProfiledReloadInstance
- XXX.packs.resources.ProfiledReloadInstance$State
- XXX.packs.resources.ReloadableResourceManager
+ XXX.packs.resources.ReloadInstance
+ XXX.packs.resources.Resource
- XXX.packs.resources.ResourceFilterSection
+ XXX.packs.resources.ResourceManager
- XXX.packs.resources.ResourceManager$Empty
+ XXX.packs.resources.ResourceManagerReloadListener
- XXX.packs.resources.ResourceMetadata
+ XXX.packs.resources.ResourceMetadata$1
- XXX.packs.resources.ResourceMetadata$2
+ XXX.packs.resources.ResourceMetadata$Builder
- XXX.packs.resources.ResourceMetadata$Builder$1
+ XXX.packs.resources.ResourceProvider
- XXX.packs.resources.SimpleJsonResourceReloadListener
+ XXX.packs.resources.SimplePreparableReloadListener
- XXX.packs.resources.SimpleReloadInstance
+ XXX.packs.resources.SimpleReloadInstance$1
- XXX.packs.resources.SimpleReloadInstance$StateFactory
- XXX.parsing.packrat.Atom
+ XXX.parsing.packrat.Control
- XXX.parsing.packrat.Dictionary
+ XXX.parsing.packrat.ErrorCollector
- XXX.parsing.packrat.ErrorCollector$LongestOnly
+ XXX.parsing.packrat.ErrorEntry
+ XXX.parsing.packrat.package-info
- XXX.parsing.packrat.ParseState
+ XXX.parsing.packrat.ParseState$CacheEntry
- XXX.parsing.packrat.ParseState$CacheKey
+ XXX.parsing.packrat.Rule
- XXX.parsing.packrat.Rule$RuleAction
+ XXX.parsing.packrat.Rule$SimpleRuleAction
- XXX.parsing.packrat.Rule$WrappedTerm
+ XXX.parsing.packrat.Scope
- XXX.parsing.packrat.SuggestionSupplier
+ XXX.parsing.packrat.Term
- XXX.parsing.packrat.Term$1
+ XXX.parsing.packrat.Term$2
- XXX.parsing.packrat.Term$Alternative
+ XXX.parsing.packrat.Term$Marker
- XXX.parsing.packrat.Term$Maybe
+ XXX.parsing.packrat.Term$Reference
- XXX.parsing.packrat.Term$Sequence
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
+ XXX.profiling.jfr.Environment
- XXX.profiling.jfr.JfrProfiler
+ XXX.profiling.jfr.JfrProfiler$1
- XXX.profiling.jfr.JvmProfiler
+ XXX.profiling.jfr.JvmProfiler$NoOpProfiler
+ XXX.profiling.jfr.package-info
- XXX.profiling.jfr.Percentiles
+ XXX.profiling.jfr.SummaryReporter
- XXX.profiling.metrics.MetricCategory
+ XXX.profiling.metrics.MetricSampler
- XXX.profiling.metrics.MetricSampler$MetricSamplerBuilder
+ XXX.profiling.metrics.MetricSampler$SamplerResult
- XXX.profiling.metrics.MetricSampler$ThresholdTest
+ XXX.profiling.metrics.MetricSampler$ValueIncreasedByPercentage
- XXX.profiling.metrics.MetricsRegistry
+ XXX.profiling.metrics.MetricsRegistry$AggregatedMetricSampler
- XXX.profiling.metrics.MetricsSamplerProvider
- XXX.profiling.metrics.package-info
+ XXX.profiling.metrics.ProfilerMeasured
+ XXX.protocol.common.ClientboundCustomPayloadPacket
- XXX.protocol.common.ClientboundDisconnectPacket
+ XXX.protocol.common.ClientboundKeepAlivePacket
- XXX.protocol.common.ClientboundPingPacket
+ XXX.protocol.common.ClientboundResourcePackPopPacket
- XXX.protocol.common.ClientboundResourcePackPushPacket
+ XXX.protocol.common.ClientboundStoreCookiePacket
- XXX.protocol.common.ClientboundTransferPacket
+ XXX.protocol.common.ClientboundUpdateTagsPacket
- XXX.protocol.common.ClientCommonPacketListener
- XXX.protocol.common.CommonPacketTypes
- XXX.protocol.common.package-info
- XXX.protocol.common.ServerboundClientInformationPacket
+ XXX.protocol.common.ServerboundCustomPayloadPacket
- XXX.protocol.common.ServerboundKeepAlivePacket
+ XXX.protocol.common.ServerboundPongPacket
- XXX.protocol.common.ServerboundResourcePackPacket
+ XXX.protocol.common.ServerboundResourcePackPacket$Action
+ XXX.protocol.common.ServerCommonPacketListener
- XXX.protocol.configuration.ClientboundFinishConfigurationPacket
+ XXX.protocol.configuration.ClientboundRegistryDataPacket
- XXX.protocol.configuration.ClientboundResetChatPacket
+ XXX.protocol.configuration.ClientboundSelectKnownPacks
- XXX.protocol.configuration.ClientboundUpdateEnabledFeaturesPacket
+ XXX.protocol.configuration.ClientConfigurationPacketListener
+ XXX.protocol.configuration.ConfigurationPacketTypes
- XXX.protocol.configuration.ConfigurationProtocols
- XXX.protocol.configuration.package-info
- XXX.protocol.configuration.ServerboundFinishConfigurationPacket
+ XXX.protocol.configuration.ServerboundSelectKnownPacks
+ XXX.protocol.configuration.ServerConfigurationPacketListener
- XXX.protocol.cookie.ClientboundCookieRequestPacket
+ XXX.protocol.cookie.ClientCookiePacketListener
+ XXX.protocol.cookie.CookiePacketTypes
- XXX.protocol.cookie.package-info
+ XXX.protocol.cookie.ServerboundCookieResponsePacket
- XXX.protocol.cookie.ServerCookiePacketListener
- XXX.protocol.game.ClientboundAddEntityPacket
+ XXX.protocol.game.ClientboundAddExperienceOrbPacket
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
+ XXX.protocol.game.ClientboundBundleDelimiterPacket
- XXX.protocol.game.ClientboundBundlePacket
+ XXX.protocol.game.ClientboundChangeDifficultyPacket
- XXX.protocol.game.ClientboundChunkBatchFinishedPacket
+ XXX.protocol.game.ClientboundChunkBatchStartPacket
- XXX.protocol.game.ClientboundChunksBiomesPacket
+ XXX.protocol.game.ClientboundChunksBiomesPacket$ChunkBiomeData
- XXX.protocol.game.ClientboundClearTitlesPacket
+ XXX.protocol.game.ClientboundCommandsPacket
- XXX.protocol.game.ClientboundCommandsPacket$ArgumentNodeStub
+ XXX.protocol.game.ClientboundCommandsPacket$Entry
- XXX.protocol.game.ClientboundCommandsPacket$LiteralNodeStub
+ XXX.protocol.game.ClientboundCommandsPacket$NodeResolver
- XXX.protocol.game.ClientboundCommandsPacket$NodeStub
+ XXX.protocol.game.ClientboundCommandSuggestionsPacket
- XXX.protocol.game.ClientboundCommandSuggestionsPacket$Entry
+ XXX.protocol.game.ClientboundContainerClosePacket
- XXX.protocol.game.ClientboundContainerSetContentPacket
+ XXX.protocol.game.ClientboundContainerSetDataPacket
- XXX.protocol.game.ClientboundContainerSetSlotPacket
+ XXX.protocol.game.ClientboundCooldownPacket
- XXX.protocol.game.ClientboundCustomChatCompletionsPacket
+ XXX.protocol.game.ClientboundCustomChatCompletionsPacket$Action
- XXX.protocol.game.ClientboundDamageEventPacket
+ XXX.protocol.game.ClientboundDebugSamplePacket
- XXX.protocol.game.ClientboundDeleteChatPacket
+ XXX.protocol.game.ClientboundDisguisedChatPacket
- XXX.protocol.game.ClientboundEntityEventPacket
+ XXX.protocol.game.ClientboundExplodePacket
- XXX.protocol.game.ClientboundForgetLevelChunkPacket
+ XXX.protocol.game.ClientboundGameEventPacket
- XXX.protocol.game.ClientboundGameEventPacket$Type
+ XXX.protocol.game.ClientboundHorseScreenOpenPacket
- XXX.protocol.game.ClientboundHurtAnimationPacket
+ XXX.protocol.game.ClientboundInitializeBorderPacket
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
- XXX.protocol.game.ClientboundProjectilePowerPacket
+ XXX.protocol.game.ClientboundRecipePacket
- XXX.protocol.game.ClientboundRecipePacket$State
+ XXX.protocol.game.ClientboundRemoveEntitiesPacket
- XXX.protocol.game.ClientboundRemoveMobEffectPacket
+ XXX.protocol.game.ClientboundResetScorePacket
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
- XXX.protocol.game.ClientboundStartConfigurationPacket
+ XXX.protocol.game.ClientboundStopSoundPacket
- XXX.protocol.game.ClientboundSystemChatPacket
+ XXX.protocol.game.ClientboundTabListPacket
- XXX.protocol.game.ClientboundTagQueryPacket
+ XXX.protocol.game.ClientboundTakeItemEntityPacket
- XXX.protocol.game.ClientboundTeleportEntityPacket
+ XXX.protocol.game.ClientboundTickingStatePacket
- XXX.protocol.game.ClientboundTickingStepPacket
+ XXX.protocol.game.ClientboundUpdateAdvancementsPacket
- XXX.protocol.game.ClientboundUpdateAttributesPacket
+ XXX.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
- XXX.protocol.game.ClientboundUpdateMobEffectPacket
+ XXX.protocol.game.ClientboundUpdateRecipesPacket
+ XXX.protocol.game.ClientGamePacketListener
- XXX.protocol.game.CommonPlayerSpawnInfo
+ XXX.protocol.game.DebugEntityNameGenerator
- XXX.protocol.game.DebugPackets
+ XXX.protocol.game.GamePacketTypes
- XXX.protocol.game.GameProtocols
- XXX.protocol.game.package-info
+ XXX.protocol.game.ServerboundAcceptTeleportationPacket
- XXX.protocol.game.ServerboundBlockEntityTagQueryPacket
+ XXX.protocol.game.ServerboundChangeDifficultyPacket
- XXX.protocol.game.ServerboundChatAckPacket
+ XXX.protocol.game.ServerboundChatCommandPacket
- XXX.protocol.game.ServerboundChatCommandSignedPacket
+ XXX.protocol.game.ServerboundChatPacket
- XXX.protocol.game.ServerboundChatSessionUpdatePacket
+ XXX.protocol.game.ServerboundChunkBatchReceivedPacket
- XXX.protocol.game.ServerboundClientCommandPacket
+ XXX.protocol.game.ServerboundClientCommandPacket$Action
- XXX.protocol.game.ServerboundCommandSuggestionPacket
+ XXX.protocol.game.ServerboundConfigurationAcknowledgedPacket
- XXX.protocol.game.ServerboundContainerButtonClickPacket
+ XXX.protocol.game.ServerboundContainerClickPacket
- XXX.protocol.game.ServerboundContainerClosePacket
+ XXX.protocol.game.ServerboundContainerSlotStateChangedPacket
- XXX.protocol.game.ServerboundDebugSampleSubscriptionPacket
+ XXX.protocol.game.ServerboundEditBookPacket
- XXX.protocol.game.ServerboundEntityTagQueryPacket
+ XXX.protocol.game.ServerboundInteractPacket
- XXX.protocol.game.ServerboundInteractPacket$1
+ XXX.protocol.game.ServerboundInteractPacket$Action
- XXX.protocol.game.ServerboundInteractPacket$ActionType
+ XXX.protocol.game.ServerboundInteractPacket$Handler
- XXX.protocol.game.ServerboundInteractPacket$InteractionAction
+ XXX.protocol.game.ServerboundInteractPacket$InteractionAtLocationAction
- XXX.protocol.game.ServerboundJigsawGeneratePacket
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
+ XXX.protocol.game.ServerboundRecipeBookChangeSettingsPacket
- XXX.protocol.game.ServerboundRecipeBookSeenRecipePacket
+ XXX.protocol.game.ServerboundRenameItemPacket
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
+ XXX.protocol.game.ServerGamePacketListener
- XXX.protocol.game.ServerPacketListener
+ XXX.protocol.game.VecDeltaCodec
+ XXX.protocol.handshake.ClientIntent
- XXX.protocol.handshake.ClientIntentionPacket
+ XXX.protocol.handshake.HandshakePacketTypes
- XXX.protocol.handshake.HandshakeProtocols
- XXX.protocol.handshake.package-info
+ XXX.protocol.handshake.ServerHandshakePacketListener
- XXX.protocol.login.ClientboundCustomQueryPacket
+ XXX.protocol.login.ClientboundGameProfilePacket
- XXX.protocol.login.ClientboundHelloPacket
+ XXX.protocol.login.ClientboundLoginCompressionPacket
- XXX.protocol.login.ClientboundLoginDisconnectPacket
+ XXX.protocol.login.ClientLoginPacketListener
+ XXX.protocol.login.LoginPacketTypes
- XXX.protocol.login.LoginProtocols
+ XXX.protocol.login.package-info
- XXX.protocol.login.ServerboundCustomQueryAnswerPacket
+ XXX.protocol.login.ServerboundHelloPacket
- XXX.protocol.login.ServerboundKeyPacket
+ XXX.protocol.login.ServerboundLoginAcknowledgedPacket
+ XXX.protocol.login.ServerLoginPacketListener
- XXX.protocol.ping.ClientboundPongResponsePacket
+ XXX.protocol.ping.ClientPongPacketListener
- XXX.protocol.ping.package-info
+ XXX.protocol.ping.PingPacketTypes
+ XXX.protocol.ping.ServerboundPingRequestPacket
- XXX.protocol.ping.ServerPingPacketListener
- XXX.protocol.status.ClientboundStatusResponsePacket
+ XXX.protocol.status.ClientStatusPacketListener
+ XXX.protocol.status.package-info
- XXX.protocol.status.ServerboundStatusRequestPacket
+ XXX.protocol.status.ServerStatus
- XXX.protocol.status.ServerStatus$Favicon
+ XXX.protocol.status.ServerStatus$Players
- XXX.protocol.status.ServerStatus$Version
+ XXX.protocol.status.ServerStatusPacketListener
+ XXX.protocol.status.StatusPacketTypes
- XXX.protocol.status.StatusProtocols
+ XXX.providers.nbt.ContextNbtProvider
- XXX.providers.nbt.ContextNbtProvider$1
+ XXX.providers.nbt.ContextNbtProvider$2
- XXX.providers.nbt.ContextNbtProvider$Getter
+ XXX.providers.nbt.LootNbtProviderType
- XXX.providers.nbt.NbtProvider
+ XXX.providers.nbt.NbtProviders
+ XXX.providers.nbt.package-info
- XXX.providers.nbt.StorageNbtProvider
- XXX.providers.number.BinomialDistributionGenerator
+ XXX.providers.number.ConstantValue
- XXX.providers.number.LootNumberProviderType
+ XXX.providers.number.NumberProvider
- XXX.providers.number.NumberProviders
- XXX.providers.number.package-info
+ XXX.providers.number.ScoreboardValue
- XXX.providers.number.StorageValue
+ XXX.providers.number.UniformGenerator
+ XXX.providers.score.ContextScoreboardNameProvider
- XXX.providers.score.FixedScoreboardNameProvider
+ XXX.providers.score.LootScoreProviderType
- XXX.providers.score.package-info
- XXX.providers.score.ScoreboardNameProvider
+ XXX.providers.score.ScoreboardNameProviders
+ XXX.rcon.thread.GenericThread
- XXX.rcon.thread.package-info
- XXX.rcon.thread.QueryThreadGs4
+ XXX.rcon.thread.QueryThreadGs4$RequestChallenge
- XXX.rcon.thread.RconClient
+ XXX.rcon.thread.RconThread
+ XXX.recipes.packs.BundleRecipeProvider
+ XXX.recipes.packs.package-info
- XXX.recipes.packs.UpdateOneTwentyOneRecipeProvider
+ XXX.recipes.packs.VanillaRecipeProvider
- XXX.recipes.packs.VanillaRecipeProvider$TrimTemplate
+ XXX.scores.criteria.ObjectiveCriteria
- XXX.scores.criteria.ObjectiveCriteria$RenderType
+ XXX.scores.criteria.package-info
- XXX.server.advancements.AdvancementVisibilityEvaluator
+ XXX.server.advancements.AdvancementVisibilityEvaluator$Output
- XXX.server.advancements.AdvancementVisibilityEvaluator$VisibilityRule
+ XXX.server.advancements.package-info
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
+ XXX.server.commands.CloneCommands$CloneBlockEntityInfo
- XXX.server.commands.CloneCommands$CloneBlockInfo
+ XXX.server.commands.CloneCommands$CommandFunction
- XXX.server.commands.CloneCommands$DimensionAndPosition
+ XXX.server.commands.CloneCommands$Mode
- XXX.server.commands.DamageCommand
+ XXX.server.commands.DataPackCommand
- XXX.server.commands.DataPackCommand$Inserter
- XXX.server.commands.DebugCommand
+ XXX.server.commands.DebugCommand$TraceCustomExecutor
- XXX.server.commands.DebugCommand$TraceCustomExecutor$1
+ XXX.server.commands.DebugCommand$Tracer
- XXX.server.commands.DebugConfigCommand
+ XXX.server.commands.DebugMobSpawningCommand
- XXX.server.commands.DebugPathCommand
+ XXX.server.commands.DefaultGameModeCommands
+ XXX.server.commands.DeOpCommands
- XXX.server.commands.DifficultyCommand
+ XXX.server.commands.EffectCommands
- XXX.server.commands.EmoteCommands
+ XXX.server.commands.EnchantCommand
- XXX.server.commands.ExecuteCommand
+ XXX.server.commands.ExecuteCommand$CommandGetter
- XXX.server.commands.ExecuteCommand$CommandNumericPredicate
+ XXX.server.commands.ExecuteCommand$CommandPredicate
- XXX.server.commands.ExecuteCommand$ExecuteIfFunctionCustomModifier
+ XXX.server.commands.ExecuteCommand$IntBiPredicate
- XXX.server.commands.ExperienceCommand
+ XXX.server.commands.ExperienceCommand$Type
- XXX.server.commands.FillBiomeCommand
+ XXX.server.commands.FillCommand
- XXX.server.commands.FillCommand$Mode
+ XXX.server.commands.ForceLoadCommand
- XXX.server.commands.FunctionCommand
+ XXX.server.commands.FunctionCommand$1
- XXX.server.commands.FunctionCommand$1Accumulator
+ XXX.server.commands.FunctionCommand$2
- XXX.server.commands.FunctionCommand$3
+ XXX.server.commands.FunctionCommand$4
- XXX.server.commands.FunctionCommand$5
+ XXX.server.commands.FunctionCommand$Callbacks
- XXX.server.commands.FunctionCommand$FunctionCustomExecutor
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
+ XXX.server.commands.package-info
- XXX.server.commands.PardonCommand
+ XXX.server.commands.PardonIpCommand
- XXX.server.commands.ParticleCommand
+ XXX.server.commands.PerfCommand
- XXX.server.commands.PlaceCommand
+ XXX.server.commands.PlaySoundCommand
- XXX.server.commands.PublishCommand
+ XXX.server.commands.RaidCommand
- XXX.server.commands.RandomCommand
+ XXX.server.commands.RecipeCommand
- XXX.server.commands.ReloadCommand
+ XXX.server.commands.ResetChunksCommand
- XXX.server.commands.ReturnCommand
+ XXX.server.commands.ReturnCommand$ReturnFailCustomExecutor
- XXX.server.commands.ReturnCommand$ReturnFromCommandCustomModifier
+ XXX.server.commands.ReturnCommand$ReturnValueCustomExecutor
- XXX.server.commands.RideCommand
+ XXX.server.commands.SaveAllCommand
- XXX.server.commands.SaveOffCommand
+ XXX.server.commands.SaveOnCommand
- XXX.server.commands.SayCommand
+ XXX.server.commands.ScheduleCommand
- XXX.server.commands.ScoreboardCommand
+ XXX.server.commands.ScoreboardCommand$NumberFormatCommandExecutor
- XXX.server.commands.SeedCommand
+ XXX.server.commands.ServerPackCommand
- XXX.server.commands.SetBlockCommand
+ XXX.server.commands.SetBlockCommand$Filter
- XXX.server.commands.SetBlockCommand$Mode
+ XXX.server.commands.SetPlayerIdleTimeoutCommand
- XXX.server.commands.SetSpawnCommand
+ XXX.server.commands.SetWorldSpawnCommand
- XXX.server.commands.SpawnArmorTrimsCommand
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
- XXX.server.commands.TeleportCommand$LookAtEntity
+ XXX.server.commands.TeleportCommand$LookAtPosition
- XXX.server.commands.TellRawCommand
+ XXX.server.commands.TickCommand
- XXX.server.commands.TimeCommand
+ XXX.server.commands.TitleCommand
- XXX.server.commands.TransferCommand
+ XXX.server.commands.TriggerCommand
- XXX.server.commands.WardenSpawnTrackerCommand
+ XXX.server.commands.WeatherCommand
- XXX.server.commands.WhitelistCommand
+ XXX.server.commands.WorldBorderCommand
- XXX.server.dedicated.DedicatedPlayerList
+ XXX.server.dedicated.DedicatedServer
- XXX.server.dedicated.DedicatedServer$1
+ XXX.server.dedicated.DedicatedServerProperties
- XXX.server.dedicated.DedicatedServerProperties$WorldDimensionData
+ XXX.server.dedicated.DedicatedServerSettings
- XXX.server.dedicated.package-info
- XXX.server.dedicated.ServerWatchdog
+ XXX.server.dedicated.ServerWatchdog$1
- XXX.server.dedicated.Settings
+ XXX.server.dedicated.Settings$MutableValue
+ XXX.server.gui.MinecraftServerGui
- XXX.server.gui.MinecraftServerGui$1
+ XXX.server.gui.MinecraftServerGui$2
- XXX.server.gui.package-info
- XXX.server.gui.PlayerListComponent
+ XXX.server.gui.StatsComponent
+ XXX.server.level.BlockDestructionProgress
- XXX.server.level.ChunkHolder
+ XXX.server.level.ChunkHolder$ChunkSaveDebug
- XXX.server.level.ChunkHolder$LevelChangeListener
+ XXX.server.level.ChunkHolder$PlayerProvider
- XXX.server.level.ChunkLevel
+ XXX.server.level.ChunkLevel$1
- XXX.server.level.ChunkMap
+ XXX.server.level.ChunkMap$DistanceManager
- XXX.server.level.ChunkMap$TrackedEntity
+ XXX.server.level.ChunkResult
- XXX.server.level.ChunkResult$Fail
+ XXX.server.level.ChunkResult$Success
- XXX.server.level.ChunkTaskPriorityQueue
+ XXX.server.level.ChunkTaskPriorityQueueSorter
- XXX.server.level.ChunkTaskPriorityQueueSorter$Message
+ XXX.server.level.ChunkTaskPriorityQueueSorter$Release
- XXX.server.level.ChunkTracker
+ XXX.server.level.ChunkTrackingView
- XXX.server.level.ChunkTrackingView$1
+ XXX.server.level.ChunkTrackingView$Positioned
- XXX.server.level.ClientInformation
+ XXX.server.level.ColumnPos
- XXX.server.level.DemoMode
+ XXX.server.level.DistanceManager
- XXX.server.level.DistanceManager$ChunkTicketTracker
+ XXX.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
- XXX.server.level.DistanceManager$PlayerTicketTracker
+ XXX.server.level.FullChunkStatus
- XXX.server.level.package-info
- XXX.server.level.PlayerMap
+ XXX.server.level.PlayerRespawnLogic
- XXX.server.level.SectionTracker
+ XXX.server.level.ServerBossEvent
- XXX.server.level.ServerChunkCache
+ XXX.server.level.ServerChunkCache$ChunkAndHolder
- XXX.server.level.ServerChunkCache$MainThreadExecutor
+ XXX.server.level.ServerEntity
- XXX.server.level.ServerLevel
+ XXX.server.level.ServerLevel$EntityCallbacks
- XXX.server.level.ServerPlayer
+ XXX.server.level.ServerPlayer$1
- XXX.server.level.ServerPlayer$2
+ XXX.server.level.ServerPlayerGameMode
- XXX.server.level.ThreadedLevelLightEngine
+ XXX.server.level.ThreadedLevelLightEngine$TaskType
- XXX.server.level.Ticket
+ XXX.server.level.TicketType
- XXX.server.level.TickingTracker
+ XXX.server.level.WorldGenRegion
+ XXX.server.network.CommonListenerCookie
- XXX.server.network.ConfigurationTask
+ XXX.server.network.ConfigurationTask$Type
- XXX.server.network.Filterable
+ XXX.server.network.FilteredText
- XXX.server.network.LegacyProtocolUtils
+ XXX.server.network.LegacyQueryHandler
- XXX.server.network.MemoryServerHandshakePacketListenerImpl
- XXX.server.network.package-info
+ XXX.server.network.PlayerChunkSender
- XXX.server.network.ServerCommonPacketListenerImpl
+ XXX.server.network.ServerConfigurationPacketListenerImpl
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
- XXX.server.network.TextFilterClient
+ XXX.server.network.TextFilterClient$IgnoreStrategy
- XXX.server.network.TextFilterClient$JoinOrLeaveEncoder
+ XXX.server.network.TextFilterClient$MessageEncoder
- XXX.server.network.TextFilterClient$PlayerContext
+ XXX.server.network.TextFilterClient$RequestFailedException
- XXX.server.packs.AbstractPackResources
+ XXX.server.packs.BuiltInMetadata
- XXX.server.packs.CompositePackResources
+ XXX.server.packs.DownloadCacheCleaner
- XXX.server.packs.DownloadCacheCleaner$1
+ XXX.server.packs.DownloadCacheCleaner$PathAndPriority
- XXX.server.packs.DownloadCacheCleaner$PathAndTime
+ XXX.server.packs.DownloadQueue
- XXX.server.packs.DownloadQueue$BatchConfig
+ XXX.server.packs.DownloadQueue$BatchResult
- XXX.server.packs.DownloadQueue$DownloadRequest
+ XXX.server.packs.DownloadQueue$FileInfoEntry
- XXX.server.packs.DownloadQueue$LogEntry
+ XXX.server.packs.FeatureFlagsMetadataSection
- XXX.server.packs.FilePackResources
+ XXX.server.packs.FilePackResources$FileResourcesSupplier
- XXX.server.packs.FilePackResources$SharedZipFileAccess
+ XXX.server.packs.OverlayMetadataSection
- XXX.server.packs.OverlayMetadataSection$OverlayEntry
- XXX.server.packs.package-info
+ XXX.server.packs.PackLocationInfo
- XXX.server.packs.PackResources
+ XXX.server.packs.PackResources$ResourceOutput
- XXX.server.packs.PackSelectionConfig
+ XXX.server.packs.PackType
- XXX.server.packs.PathPackResources
+ XXX.server.packs.PathPackResources$PathResourcesSupplier
- XXX.server.packs.VanillaPackResources
+ XXX.server.packs.VanillaPackResourcesBuilder
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
- XXX.storage.loot.ContainerComponentManipulator
- XXX.storage.loot.ContainerComponentManipulators$1
- XXX.storage.loot.ContainerComponentManipulators$3
+ XXX.storage.loot.IntRange
- XXX.storage.loot.IntRange$IntChecker
+ XXX.storage.loot.IntRange$IntLimiter
- XXX.storage.loot.LootContext
+ XXX.storage.loot.LootContext$Builder
- XXX.storage.loot.LootContext$EntityTarget
+ XXX.storage.loot.LootContext$VisitedEntry
- XXX.storage.loot.LootContextUser
+ XXX.storage.loot.LootDataType
- XXX.storage.loot.LootDataType$Validator
+ XXX.storage.loot.LootParams
- XXX.storage.loot.LootParams$Builder
+ XXX.storage.loot.LootParams$DynamicDrop
- XXX.storage.loot.LootPool
+ XXX.storage.loot.LootPool$Builder
- XXX.storage.loot.LootTable
+ XXX.storage.loot.LootTable$Builder
- XXX.storage.loot.package-info
- XXX.storage.loot.ValidationContext
- XXX.util.debugchart.AbstractSampleLogger
+ XXX.util.debugchart.DebugSampleSubscriptionTracker
- XXX.util.debugchart.DebugSampleSubscriptionTracker$SubscriptionRequest
+ XXX.util.debugchart.DebugSampleSubscriptionTracker$SubscriptionStartedAt
- XXX.util.debugchart.LocalSampleLogger
+ XXX.util.debugchart.RemoteDebugSampleType
- XXX.util.debugchart.RemoteSampleLogger
+ XXX.util.debugchart.SampleLogger
- XXX.util.debugchart.SampleStorage
+ XXX.util.debugchart.TpsDebugDimensions
- XXX.util.eventlog.EventLogDirectory
+ XXX.util.eventlog.EventLogDirectory$CompressedFile
- XXX.util.eventlog.EventLogDirectory$File
+ XXX.util.eventlog.EventLogDirectory$FileId
- XXX.util.eventlog.EventLogDirectory$FileList
+ XXX.util.eventlog.EventLogDirectory$RawFile
- XXX.util.eventlog.JsonEventLog
+ XXX.util.eventlog.JsonEventLog$1
- XXX.util.eventlog.JsonEventLogReader
+ XXX.util.eventlog.JsonEventLogReader$1
- XXX.util.eventlog.package-info
+ XXX.util.parsing.package-info
- XXX.util.profiling.ActiveProfiler
+ XXX.util.profiling.ActiveProfiler$PathEntry
- XXX.util.profiling.ContinuousProfiler
+ XXX.util.profiling.EmptyProfileResults
- XXX.util.profiling.FilledProfileResults
+ XXX.util.profiling.FilledProfileResults$1
- XXX.util.profiling.FilledProfileResults$CounterCollector
+ XXX.util.profiling.InactiveProfiler
- XXX.util.profiling.package-info
- XXX.util.profiling.ProfileCollector
+ XXX.util.profiling.ProfileResults
- XXX.util.profiling.ProfilerFiller
+ XXX.util.profiling.ProfilerFiller$1
- XXX.util.profiling.ProfilerPathEntry
+ XXX.util.profiling.ResultField
- XXX.util.profiling.SingleTickProfiler
+ XXX.util.random.package-info
+ XXX.util.random.SimpleWeightedRandomList
- XXX.util.random.SimpleWeightedRandomList$Builder
+ XXX.util.random.Weight
- XXX.util.random.WeightedEntry
+ XXX.util.random.WeightedEntry$IntrusiveBase
- XXX.util.random.WeightedEntry$Wrapper
+ XXX.util.random.WeightedRandom
- XXX.util.random.WeightedRandomList
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
+ XXX.util.valueproviders.BiasedToBottomInt
- XXX.util.valueproviders.ClampedInt
+ XXX.util.valueproviders.ClampedNormalFloat
- XXX.util.valueproviders.ClampedNormalInt
+ XXX.util.valueproviders.ConstantFloat
- XXX.util.valueproviders.ConstantInt
+ XXX.util.valueproviders.FloatProvider
- XXX.util.valueproviders.FloatProviderType
+ XXX.util.valueproviders.IntProvider
- XXX.util.valueproviders.IntProviderType
+ XXX.util.valueproviders.MultipliedFloats
+ XXX.util.valueproviders.package-info
- XXX.util.valueproviders.SampledFloat
+ XXX.util.valueproviders.TrapezoidFloat
- XXX.util.valueproviders.UniformFloat
+ XXX.util.valueproviders.UniformInt
- XXX.util.valueproviders.WeightedListInt
- XXX.util.worldupdate.package-info
- XXX.util.worldupdate.WorldUpgrader
+ XXX.util.worldupdate.WorldUpgrader$AbstractUpgrader
- XXX.util.worldupdate.WorldUpgrader$ChunkUpgrader
+ XXX.util.worldupdate.WorldUpgrader$DimensionToUpgrade
- XXX.util.worldupdate.WorldUpgrader$EntityUpgrader
+ XXX.util.worldupdate.WorldUpgrader$FileToUpgrade
- XXX.util.worldupdate.WorldUpgrader$PoiUpgrader
+ XXX.util.worldupdate.WorldUpgrader$SimpleRegionStorageUpgrader
- XXX.world.damagesource.CombatEntry
+ XXX.world.damagesource.CombatRules
- XXX.world.damagesource.CombatTracker
+ XXX.world.damagesource.DamageEffects
- XXX.world.damagesource.DamageScaling
+ XXX.world.damagesource.DamageSource
- XXX.world.damagesource.DamageSource$1
+ XXX.world.damagesource.DamageSources
- XXX.world.damagesource.DamageType
+ XXX.world.damagesource.DamageTypes
- XXX.world.damagesource.DeathMessageType
+ XXX.world.damagesource.FallLocation
- XXX.world.damagesource.package-info
+ XXX.world.effect.AbsorptionMobEffect
- XXX.world.effect.BadOmenMobEffect
+ XXX.world.effect.HealOrHarmMobEffect
- XXX.world.effect.HungerMobEffect
+ XXX.world.effect.InfestedMobEffect
- XXX.world.effect.InstantenousMobEffect
+ XXX.world.effect.MobEffect
- XXX.world.effect.MobEffect$AttributeTemplate
+ XXX.world.effect.MobEffectCategory
- XXX.world.effect.MobEffectInstance
+ XXX.world.effect.MobEffectInstance$BlendState
- XXX.world.effect.MobEffectInstance$Details
- XXX.world.effect.MobEffects
+ XXX.world.effect.MobEffectUtil
+ XXX.world.effect.OozingMobEffect
+ XXX.world.effect.package-info
- XXX.world.effect.PoisonMobEffect
+ XXX.world.effect.RaidOmenMobEffect
- XXX.world.effect.RegenerationMobEffect
+ XXX.world.effect.SaturationMobEffect
- XXX.world.effect.WeavingMobEffect
+ XXX.world.effect.WindChargedMobEffect
- XXX.world.effect.WitherMobEffect
- XXX.world.entity.AgeableMob
+ XXX.world.entity.AgeableMob$AgeableMobGroupData
- XXX.world.entity.AnimationState
+ XXX.world.entity.AreaEffectCloud
- XXX.world.entity.Attackable
+ XXX.world.entity.Crackiness
- XXX.world.entity.Crackiness$Level
+ XXX.world.entity.Display
- XXX.world.entity.Display$BillboardConstraints
+ XXX.world.entity.Display$BlockDisplay
- XXX.world.entity.Display$BlockDisplay$BlockRenderState
+ XXX.world.entity.Display$ColorInterpolator
- XXX.world.entity.Display$FloatInterpolator
+ XXX.world.entity.Display$GenericInterpolator
- XXX.world.entity.Display$IntInterpolator
+ XXX.world.entity.Display$ItemDisplay
- XXX.world.entity.EquipmentUser
+ XXX.world.entity.ExperienceOrb
- XXX.world.entity.FlyingMob
+ XXX.world.entity.GlowSquid
- XXX.world.entity.HasCustomInventoryScreen
+ XXX.world.entity.HumanoidArm
- XXX.world.entity.Interaction
+ XXX.world.entity.Interaction$PlayerAction
- XXX.world.entity.ItemBasedSteering
+ XXX.world.entity.ItemSteerable
- XXX.world.entity.LerpingModel
+ XXX.world.entity.LightningBolt
- XXX.world.entity.LivingEntity
+ XXX.world.entity.LivingEntity$1
- XXX.world.entity.LivingEntity$Fallsounds
+ XXX.world.entity.Marker
- XXX.world.entity.Mob
+ XXX.world.entity.Mob$1
- XXX.world.entity.MobCategory
+ XXX.world.entity.MobSpawnType
- XXX.world.entity.MoverType
+ XXX.world.entity.NeutralMob
- XXX.world.entity.OminousItemSpawner
+ XXX.world.entity.OwnableEntity
- XXX.world.entity.PathfinderMob
+ XXX.world.entity.PlayerRideable
- XXX.world.entity.PlayerRideableJumping
+ XXX.world.entity.Pose
- XXX.world.entity.PowerableMob
+ XXX.world.entity.RelativeMovement
- XXX.world.entity.ReputationEventHandler
+ XXX.world.entity.Saddleable
- XXX.world.entity.Shearable
+ XXX.world.entity.SlotAccess
- XXX.world.entity.SlotAccess$1
+ XXX.world.entity.SlotAccess$2
- XXX.world.entity.SlotAccess$3
+ XXX.world.item.Items
- XXX.world.item.ItemStackLinkedSet
+ XXX.world.item.ItemStackLinkedSet$1
- XXX.world.item.ItemUtils
- XXX.world.item.KnowledgeBookItem
+ XXX.world.item.LeadItem
- XXX.world.item.LingeringPotionItem
+ XXX.world.item.MaceItem
- XXX.world.item.MapItem
+ XXX.world.item.MapItem$1
- XXX.world.item.MilkBucketItem
+ XXX.world.item.MinecartItem
- XXX.world.item.MinecartItem$1
+ XXX.world.item.MobBucketItem
- XXX.world.item.NameTagItem
+ XXX.world.item.OminousBottleItem
- XXX.world.item.PickaxeItem
+ XXX.world.item.PlaceOnWaterBlockItem
- XXX.world.item.PlayerHeadItem
+ XXX.world.item.PotionItem
- XXX.world.item.ProjectileItem
+ XXX.world.item.ProjectileItem$DispenseConfig
- XXX.world.item.ProjectileItem$DispenseConfig$Builder
+ XXX.world.item.ProjectileItem$PositionFunction
- XXX.world.item.ProjectileWeaponItem
+ XXX.world.item.Rarity
- XXX.world.item.RecordItem
+ XXX.world.item.SaddleItem
- XXX.world.item.ScaffoldingBlockItem
+ XXX.world.item.ServerItemCooldowns
- XXX.world.item.ShearsItem
+ XXX.world.item.ShieldItem
- XXX.world.item.ShovelItem
+ XXX.world.item.SignApplicator
- XXX.world.item.SignItem
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
- XXX.world.item.WindChargeItem
+ XXX.world.item.WritableBookItem
- XXX.world.item.WrittenBookItem
+ XXX.world.phys.AABB
- XXX.world.phys.BlockHitResult
+ XXX.world.phys.EntityHitResult
- XXX.world.phys.HitResult
+ XXX.world.phys.HitResult$Type
- XXX.world.phys.package-info
- XXX.world.phys.Vec2
+ XXX.world.phys.Vec3
- XXX.world.scores.DisplaySlot
+ XXX.world.scores.DisplaySlot$1
- XXX.world.scores.Objective
- XXX.world.scores.package-info
+ XXX.world.scores.PlayerScoreEntry
- XXX.world.scores.PlayerScores
+ XXX.world.scores.PlayerTeam
- XXX.world.scores.ReadOnlyScoreInfo
+ XXX.world.scores.Score
- XXX.world.scores.ScoreAccess
+ XXX.world.scores.Scoreboard
- XXX.world.scores.Scoreboard$1
+ XXX.world.scores.ScoreboardSaveData
+ XXX.world.scores.ScoreHolder
- XXX.world.scores.ScoreHolder$1
+ XXX.world.scores.ScoreHolder$2
- XXX.world.scores.ScoreHolder$3
- XXX.world.scores.Team
+ XXX.world.scores.Team$CollisionRule
- XXX.world.scores.Team$Visibility
+ XXX.world.ticks.BlackholeTickAccess
- XXX.world.ticks.BlackholeTickAccess$1
+ XXX.world.ticks.BlackholeTickAccess$2
- XXX.world.ticks.ContainerSingleItem
+ XXX.world.ticks.ContainerSingleItem$BlockContainerSingleItem
- XXX.world.ticks.LevelChunkTicks
+ XXX.world.ticks.LevelTickAccess
- XXX.world.ticks.LevelTicks
+ XXX.world.ticks.LevelTicks$PosAndContainerConsumer
- XXX.world.ticks.package-info
- XXX.world.ticks.ProtoChunkTicks
+ XXX.world.ticks.SavedTick
- XXX.world.ticks.SavedTick$1
+ XXX.world.ticks.ScheduledTick
- XXX.world.ticks.ScheduledTick$1
+ XXX.world.ticks.SerializableTickContainer
- XXX.world.ticks.TickAccess
+ XXX.world.ticks.TickContainerAccess
- XXX.world.ticks.TickPriority
+ XXX.world.ticks.WorldGenTickAccess
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.advancements.critereon.EntityEquipmentPredicate +2M -1M | +1P
```
```
XXX.advancements.critereon.NbtPredicate -2P
```
```
XXX.arguments.item.ItemParser$1 +1P -1P
```
```
XXX.core.particles.ShriekParticleOption -1M | -1P
```
```
XXX.core.particles.VibrationParticleOption +3M -2M | +1P -1P
```
```
XXX.gametest.framework.TestCommand +11M -10M
```
```
XXX.network.codec.ByteBufCodecs +1P
```
```
XXX.network.codec.ByteBufCodecs$10 +1M -1M | +1P
```
```
XXX.network.codec.ByteBufCodecs$12 +3M -3M | +1P -1P
```
```
XXX.network.codec.ByteBufCodecs$14 +5M -3M | +2P
```
```
XXX.network.codec.ByteBufCodecs$16 +2M -2M
```
```
XXX.network.codec.ByteBufCodecs$18 +3M -3M | +1P -3P
```
```
XXX.network.codec.ByteBufCodecs$21 +5M -3M | +2P -2P
```
```
XXX.network.codec.ByteBufCodecs$23 +3M -3M | +1P -2P
```
```
XXX.network.codec.ByteBufCodecs$25 +3M -5M | +3P -4P
```
```
XXX.network.codec.ByteBufCodecs$27 +5M -1M | -1P
```
```
XXX.minecraft.tags.EntityTypeTags +1P
```
```
XXX.minecraft.util.ExtraCodecs +76M -72M | +2P
```
```
XXX.minecraft.util.FastColor +1M
```
```
XXX.minecraft.util.FastColor$ARGB32 +1M
```
```
XXX.datafix.fixes.References +2P
```
```
XXX.datafix.schemas.V100 +2M -1M
```
```
XXX.datafix.schemas.V1928 -1M
```
```
XXX.world.entity.Entity +5M -2M
```
```
XXX.animal.axolotl.Axolotl +1M
```
```
XXX.entity.monster.Zoglin +1M
```
```
XXX.monster.breeze.Breeze +1M
```
```
XXX.monster.hoglin.Hoglin +1M
```
```
XXX.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds +1M -1M
```
```
XXX.entity.projectile.AbstractArrow +2M
```
```
XXX.entity.projectile.AbstractHurtingProjectile +1M -3M
```
```
XXX.entity.projectile.DragonFireball -1M
```
```
XXX.world.food.FoodData +1M
```
```
XXX.world.inventory.BrewingStandMenu$IngredientsSlot +1M -2M | +1P
```
```
XXX.world.item.ItemStack$3 +5M -1M | +1P -1P
```
```
XXX.item.armortrim.ArmorTrim +1M -1M
```
```
XXX.item.component.BundleContents$Mutable +1M
```
```
XXX.item.component.FireworkExplosion +1M -1M
```
```
XXX.item.component.Fireworks +1M -1M
```
```
XXX.item.component.Unbreakable +1M -1M
```
```
XXX.item.component.WrittenBookContent -1P
```
```
XXX.item.enchantment.ItemEnchantments$Mutable +1P -1P
```
```
XXX.item.enchantment.WindBurstEnchantment$WindBurstEnchantmentDamageCalculator +1M -1M
```
```
XXX.world.level.Level +1P
```
```
XXX.world.level.SpawnData +2M -2M | +1P -1P
```
```
XXX.level.block.DispenserBlock +1M -1M | +1P
```
```
XXX.level.block.DropperBlock +1M -1M
```
```
XXX.block.entity.BrewingStandBlockEntity +1M -1M
```
```
XXX.level.levelgen.Beardifier +1M -1M
```
```
XXX.loot.functions.ListOperation +2M | +1P
```
```
XXX.loot.functions.LootItemConditionalFunction +1P
```
```
XXX.loot.functions.LootItemFunctions +4P
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.EntityEquipmentPredicate
</summary>

```diff
- Optional body()
- void <init>(Optional,Optional,Optional,Optional,Optional,Optional,Optional)
+ void <init>(Optional,Optional,Optional,Optional,Optional,Optional)
```

</details>
<details>
<summary>
net.minecraft.core.particles.ShriekParticleOption
</summary>

```diff
+ String writeToString(HolderLookup$Provider)
```

</details>
<details>
<summary>
net.minecraft.core.particles.VibrationParticleOption
</summary>

```diff
+ App lambda$static$0(RecordCodecBuilder$Instance)
- App lambda$static$2(RecordCodecBuilder$Instance)
- DataResult lambda$static$1(PositionSource)
- String lambda$static$0()
+ String writeToString(HolderLookup$Provider)
```

</details>
<details>
<summary>
net.minecraft.gametest.framework.TestCommand
</summary>

```diff
+ boolean lambda$say$38(ServerPlayer)
- boolean lambda$say$39(ServerPlayer)
+ boolean lambda$toGameTestInfo$32(CommandSourceStack,TestFunction)
- boolean lambda$toGameTestInfo$33(CommandSourceStack,TestFunction)
+ Component lambda$say$37(String)
- Component lambda$say$38(String)
+ Component lambda$showPos$35(String,Component)
- Component lambda$showPos$36(String,Component)
+ GameTestInfo lambda$toGameTestInfo$33(int,CommandSourceStack,RetryOptions,TestFunction)
- GameTestInfo lambda$toGameTestInfo$34(int,CommandSourceStack,RetryOptions,TestFunction)
- int lambda$register$30(CommandContext)
+ Optional lambda$toGameTestInfos$31(CommandSourceStack,RetryOptions,BlockPos)
- Optional lambda$toGameTestInfos$32(CommandSourceStack,RetryOptions,BlockPos)
+ void lambda$createNewStructure$34(ServerLevel,BlockPos)
- void lambda$createNewStructure$35(ServerLevel,BlockPos)
+ void lambda$resetGameTestInfo$30(Entity)
- void lambda$resetGameTestInfo$31(Entity)
+ void lambda$say$39(String,ChatFormatting,ServerPlayer)
- void lambda$say$40(String,ChatFormatting,ServerPlayer)
+ void lambda$trackAndStartRunner$36(GameTestInfo)
- void lambda$trackAndStartRunner$37(GameTestInfo)
```

</details>
<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$10
</summary>

```diff
+ void <init>()
- void <init>(int)
```

</details>
<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$12
</summary>

```diff
- String decode(ByteBuf)
+ Tag decode(ByteBuf)
- void <init>(int)
+ void <init>(Supplier)
- void encode(ByteBuf,String)
+ void encode(ByteBuf,Tag)
```

</details>
<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$14
</summary>

```diff
- DecoderException lambda$decode$0(Tag,String)
- EncoderException lambda$encode$1(Object,String)
- Object decode(RegistryFriendlyByteBuf)
+ Optional decode(ByteBuf)
+ void <init>()
- void <init>(StreamCodec,Codec)
+ void encode(ByteBuf,Optional)
- void encode(RegistryFriendlyByteBuf,Object)
```

</details>
<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$16
</summary>

```diff
+ Quaternionf decode(ByteBuf)
- Vector3f decode(ByteBuf)
+ void encode(ByteBuf,Quaternionf)
- void encode(ByteBuf,Vector3f)
```

</details>
<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$18
</summary>

```diff
+ Collection decode(ByteBuf)
- Optional decode(ByteBuf)
+ void <init>(int,IntFunction,StreamCodec)
- void <init>(StreamCodec)
+ void encode(ByteBuf,Collection)
- void encode(ByteBuf,Optional)
```

</details>
<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$21
</summary>

```diff
- Either decode(ByteBuf)
+ Object decode(ByteBuf)
+ void <init>(IntFunction,ToIntFunction)
- void <init>(StreamCodec,StreamCodec)
- void encode(ByteBuf,Either)
+ void encode(ByteBuf,Object)
- void lambda$encode$0(ByteBuf,StreamCodec,Object)
- void lambda$encode$1(ByteBuf,StreamCodec,Object)
```

</details>
<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$23
</summary>

```diff
+ Holder decode(RegistryFriendlyByteBuf)
- Object decode(RegistryFriendlyByteBuf)
- void <init>(Function,ResourceKey)
+ void <init>(ResourceKey,StreamCodec)
+ void encode(RegistryFriendlyByteBuf,Holder)
- void encode(RegistryFriendlyByteBuf,Object)
```

</details>
<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$25
</summary>

```diff
- HolderSet decode(RegistryFriendlyByteBuf)
+ PropertyMap decode(ByteBuf)
+ String lambda$decode$0(ByteBuf)
+ void <init>()
- void <init>(ResourceKey)
+ void encode(ByteBuf,PropertyMap)
- void encode(RegistryFriendlyByteBuf,HolderSet)
+ void lambda$encode$1(ByteBuf,String)
```

</details>
<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$27
</summary>

```diff
- GameProfile decode(ByteBuf)
- Object decode(Object)
+ void <clinit>()
- void <init>()
- void encode(ByteBuf,GameProfile)
- void encode(Object,Object)
```

</details>
<details>
<summary>
net.minecraft.util.ExtraCodecs
</summary>

```diff
+ App lambda$intervalCodec$19(Codec,String,String,RecordCodecBuilder$Instance)
- App lambda$intervalCodec$23(Codec,String,String,RecordCodecBuilder$Instance)
+ App lambda$static$10(RecordCodecBuilder$Instance)
- App lambda$static$13(RecordCodecBuilder$Instance)
+ App lambda$static$60(RecordCodecBuilder$Instance)
- App lambda$static$64(RecordCodecBuilder$Instance)
+ App lambda$static$68(RecordCodecBuilder$Instance)
+ App lambda$static$71(RecordCodecBuilder$Instance)
- App lambda$static$72(RecordCodecBuilder$Instance)
- App lambda$static$75(RecordCodecBuilder$Instance)
+ BitSet lambda$static$56(LongStream)
- BitSet lambda$static$60(LongStream)
+ DataResult lambda$ensureHomogenous$43(Function,Collection)
- DataResult lambda$ensureHomogenous$47(Function,Collection)
+ DataResult lambda$floatRangeMinExclusiveWithMessage$36(float,float,Function,Float)
- DataResult lambda$floatRangeMinExclusiveWithMessage$40(float,float,Function,Float)
+ DataResult lambda$idResolverCodec$26(Integer)
+ DataResult lambda$idResolverCodec$27(IntFunction,Integer)
+ DataResult lambda$idResolverCodec$29(ToIntFunction,int,Object)
- DataResult lambda$idResolverCodec$30(Integer)
- DataResult lambda$idResolverCodec$31(IntFunction,Integer)
- DataResult lambda$idResolverCodec$33(ToIntFunction,int,Object)
+ DataResult lambda$intervalCodec$16(BiFunction,List)
+ DataResult lambda$intervalCodec$17(BiFunction,List)
- DataResult lambda$intervalCodec$20(BiFunction,List)
+ DataResult lambda$intervalCodec$20(BiFunction,Pair)
- DataResult lambda$intervalCodec$21(BiFunction,List)
+ DataResult lambda$intervalCodec$22(BiFunction,Object)
+ DataResult lambda$intervalCodec$23(BiFunction,Either)
- DataResult lambda$intervalCodec$24(BiFunction,Pair)
- DataResult lambda$intervalCodec$26(BiFunction,Object)
- DataResult lambda$intervalCodec$27(BiFunction,Either)
+ DataResult lambda$intRangeWithMessage$31(int,int,Function,Integer)
- DataResult lambda$intRangeWithMessage$35(int,int,Function,Integer)
+ DataResult lambda$nonEmptyHolderSet$41(HolderSet)
- DataResult lambda$nonEmptyHolderSet$45(HolderSet)
+ DataResult lambda$nonEmptyList$39(List)
- DataResult lambda$nonEmptyList$43(List)
+ DataResult lambda$sizeLimitedMap$77(int,Map)
- DataResult lambda$sizeLimitedMap$81(int,Map)
+ DataResult lambda$static$12(List)
+ DataResult lambda$static$15(Integer)
- DataResult lambda$static$15(List)
- DataResult lambda$static$19(Integer)
+ DataResult lambda$static$45(String)
+ DataResult lambda$static$48(String)
- DataResult lambda$static$49(String)
+ DataResult lambda$static$50(String)
- DataResult lambda$static$52(String)
+ DataResult lambda$static$53(String)
- DataResult lambda$static$54(String)
- DataResult lambda$static$57(String)
+ DataResult lambda$static$67(String)
- DataResult lambda$static$71(String)
+ DataResult lambda$static$73(String)
+ DataResult lambda$static$75(String)
- DataResult lambda$static$77(String)
- DataResult lambda$static$83(String)
- DataResult lambda$static$9(List)
+ DataResult lambda$temporalCodec$46(DateTimeFormatter,String)
- DataResult lambda$temporalCodec$50(DateTimeFormatter,String)
+ Either lambda$intervalCodec$24(Function,Function,Object)
- Either lambda$intervalCodec$28(Function,Function,Object)
+ Either lambda$static$65(PropertyMap)
- Either lambda$static$69(PropertyMap)
+ ExtraCodecs$TagOrElementLocation lambda$static$51(ResourceLocation)
+ ExtraCodecs$TagOrElementLocation lambda$static$52(ResourceLocation)
- ExtraCodecs$TagOrElementLocation lambda$static$55(ResourceLocation)
- ExtraCodecs$TagOrElementLocation lambda$static$56(ResourceLocation)
- Float lambda$static$11(AxisAngle4f)
+ Float lambda$static$8(AxisAngle4f)
+ GameProfile lambda$static$70(GameProfile,PropertyMap)
- GameProfile lambda$static$74(GameProfile,PropertyMap)
- Integer lambda$static$17(Vector4f)
+ List lambda$intervalCodec$18(Function,Function,Object)
- List lambda$intervalCodec$22(Function,Function,Object)
- List lambda$static$10(Quaternionf)
+ List lambda$static$13(Matrix4f)
- List lambda$static$16(Matrix4f)
+ List lambda$static$7(Quaternionf)
- List lambda$static$7(Vector4f)
+ LongStream lambda$static$57(BitSet)
- LongStream lambda$static$61(BitSet)
+ Matrix4f lambda$static$11(List)
- Matrix4f lambda$static$14(List)
+ Optional lambda$static$55(OptionalLong)
+ Optional lambda$static$58(Property)
- Optional lambda$static$59(OptionalLong)
- Optional lambda$static$62(Property)
+ OptionalLong lambda$static$54(Optional)
- OptionalLong lambda$static$58(Optional)
+ Pair lambda$intervalCodec$21(Function,Function,Object)
- Pair lambda$intervalCodec$25(Function,Function,Object)
+ Property lambda$static$59(String,String,Optional)
- Property lambda$static$63(String,String,Optional)
+ PropertyMap lambda$static$64(Either)
- PropertyMap lambda$static$68(Either)
+ Quaternionf lambda$static$5(List)
- Quaternionf lambda$static$8(List)
+ String lambda$ensureHomogenous$42(Object,Object,Object)
- String lambda$ensureHomogenous$46(Object,Object,Object)
+ String lambda$floatRangeMinExclusiveWithMessage$35(Function,Float)
- String lambda$floatRangeMinExclusiveWithMessage$39(Function,Float)
+ String lambda$idResolverCodec$25(Integer)
+ String lambda$idResolverCodec$28(Object)
- String lambda$idResolverCodec$29(Integer)
- String lambda$idResolverCodec$32(Object)
+ String lambda$intRange$34(int,int,Integer)
- String lambda$intRange$38(int,int,Integer)
+ String lambda$intRangeWithMessage$30(Function,Integer)
- String lambda$intRangeWithMessage$34(Function,Integer)
+ String lambda$nonEmptyHolderSet$40()
- String lambda$nonEmptyHolderSet$44()
+ String lambda$nonEmptyList$38()
- String lambda$nonEmptyList$42()
+ String lambda$sizeLimitedMap$76(Map,int)
- String lambda$sizeLimitedMap$80(Map,int)
+ String lambda$static$14(Integer)
- String lambda$static$18(Integer)
+ String lambda$static$32(Integer)
+ String lambda$static$33(Integer)
- String lambda$static$36(Integer)
+ String lambda$static$37(Float)
- String lambda$static$37(Integer)
- String lambda$static$41(Float)
+ String lambda$static$44(String,PatternSyntaxException)
+ String lambda$static$47()
- String lambda$static$48(String,PatternSyntaxException)
+ String lambda$static$49(byte[])
- String lambda$static$51()
- String lambda$static$53(byte[])
+ String lambda$static$66(String)
- String lambda$static$70(String)
+ String lambda$static$72()
+ String lambda$static$74(String)
- String lambda$static$76()
- String lambda$static$82(String)
- Vector3f lambda$static$12(AxisAngle4f)
+ Vector3f lambda$static$9(AxisAngle4f)
- Vector4f lambda$static$5(List)
+ void lambda$static$61(PropertyMap,String,List)
+ void lambda$static$62(PropertyMap,Map)
+ void lambda$static$63(PropertyMap,List)
- void lambda$static$65(PropertyMap,String,List)
- void lambda$static$66(PropertyMap,Map)
- void lambda$static$67(PropertyMap,List)
+ void lambda$static$69(GameProfile,String,Property)
- void lambda$static$73(GameProfile,String,Property)
```

</details>
<details>
<summary>
net.minecraft.util.FastColor
</summary>

```diff
- int as8BitChannel(float)
```

</details>
<details>
<summary>
net.minecraft.util.FastColor$ARGB32
</summary>

```diff
- int colorFromFloat(float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.schemas.V100
</summary>

```diff
- TypeTemplate lambda$registerEntities$4(Schema,String)
+ TypeTemplate lambda$registerTypes$4(Schema)
- TypeTemplate lambda$registerTypes$5(Schema)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.schemas.V1928
</summary>

```diff
+ TypeTemplate equipment(Schema)
```

</details>
<details>
<summary>
net.minecraft.world.entity.Entity
</summary>

```diff
+ boolean lambda$countPlayerPassengers$16(Entity)
- boolean lambda$countPlayerPassengers$18(Entity)
- boolean lambda$getPassengerClosestTo$15(Entity)
- double lambda$getPassengerClosestTo$16(Vec3,Entity)
+ Iterator lambda$getIndirectPassengers$15()
- Iterator lambda$getIndirectPassengers$17()
- Optional getPassengerClosestTo(Vec3)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.axolotl.Axolotl
</summary>

```diff
- LivingEntity getTarget()
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Zoglin
</summary>

```diff
- LivingEntity getTarget()
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.breeze.Breeze
</summary>

```diff
- LivingEntity getTarget()
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.hoglin.Hoglin
</summary>

```diff
- LivingEntity getTarget()
```

</details>
<details>
<summary>
net.minecraft.world.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
</summary>

```diff
- boolean lambda$getOffer$0(Entity,Holder$Reference)
+ boolean lambda$getOffer$0(Holder$Reference)
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.AbstractArrow
</summary>

```diff
- boolean isPickable()
- SlotAccess getSlot(int)
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.AbstractHurtingProjectile
</summary>

```diff
+ boolean hurt(DamageSource,float)
+ boolean isPickable()
+ float getPickRadius()
- void onPunch(Entity)
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.DragonFireball
</summary>

```diff
+ boolean isPickable()
```

</details>
<details>
<summary>
net.minecraft.world.food.FoodData
</summary>

```diff
- void add(int,float)
```

</details>
<details>
<summary>
net.minecraft.world.inventory.BrewingStandMenu$IngredientsSlot
</summary>

```diff
+ int getMaxStackSize()
+ void <init>(Container,int,int,int)
- void <init>(PotionBrewing,Container,int,int,int)
```

</details>
<details>
<summary>
net.minecraft.world.item.ItemStack$3
</summary>

```diff
- ItemStack decode(RegistryFriendlyByteBuf)
- Object decode(Object)
+ void <clinit>()
- void <init>(StreamCodec)
- void encode(Object,Object)
- void encode(RegistryFriendlyByteBuf,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.item.armortrim.ArmorTrim
</summary>

```diff
+ void addToTooltip(Consumer,TooltipFlag)
- void addToTooltip(Item$TooltipContext,Consumer,TooltipFlag)
```

</details>
<details>
<summary>
net.minecraft.world.item.component.BundleContents$Mutable
</summary>

```diff
- BundleContents$Mutable clearItems()
```

</details>
<details>
<summary>
net.minecraft.world.item.component.FireworkExplosion
</summary>

```diff
+ void addToTooltip(Consumer,TooltipFlag)
- void addToTooltip(Item$TooltipContext,Consumer,TooltipFlag)
```

</details>
<details>
<summary>
net.minecraft.world.item.component.Fireworks
</summary>

```diff
+ void addToTooltip(Consumer,TooltipFlag)
- void addToTooltip(Item$TooltipContext,Consumer,TooltipFlag)
```

</details>
<details>
<summary>
net.minecraft.world.item.component.Unbreakable
</summary>

```diff
+ void addToTooltip(Consumer,TooltipFlag)
- void addToTooltip(Item$TooltipContext,Consumer,TooltipFlag)
```

</details>
<details>
<summary>
net.minecraft.world.item.enchantment.WindBurstEnchantment$WindBurstEnchantmentDamageCalculator
</summary>

```diff
+ float getKnockbackMultiplier()
- float getKnockbackMultiplier(Entity)
```

</details>
<details>
<summary>
net.minecraft.world.level.SpawnData
</summary>

```diff
- Optional equipment()
+ Optional equipmentLootTable()
- Optional getEquipment()
+ Optional getEquipmentLootTable()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.DispenserBlock
</summary>

```diff
+ DispenseItemBehavior getDispenseMethod(ItemStack)
- DispenseItemBehavior getDispenseMethod(Level,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.DropperBlock
</summary>

```diff
+ DispenseItemBehavior getDispenseMethod(ItemStack)
- DispenseItemBehavior getDispenseMethod(Level,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.BrewingStandBlockEntity
</summary>

```diff
+ boolean isBrewable(NonNullList)
- boolean isBrewable(PotionBrewing,NonNullList)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.Beardifier
</summary>

```diff
- double getBuryContribution(double,double,double)
+ double getBuryContribution(int,int,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.ListOperation
</summary>

```diff
- List apply(List,List)
- void <clinit>()
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
+ net.minecraft.package-info
- XXX.advancements.critereon.CollectionContentsPredicate$Multiple
- XXX.advancements.critereon.CollectionContentsPredicate$Zero
- XXX.advancements.critereon.CollectionCountsPredicate$Entry
- XXX.advancements.critereon.CollectionCountsPredicate$Single
- XXX.advancements.critereon.CollectionPredicate
- XXX.advancements.critereon.ItemAttributeModifiersPredicate
- XXX.advancements.critereon.ItemBundlePredicate
- XXX.advancements.critereon.ItemFireworkExplosionPredicate$FireworkPredicate
- XXX.advancements.critereon.ItemPotionsPredicate
+ XXX.advancements.critereon.ItemPredicate
- XXX.advancements.critereon.ItemPredicate$Builder
+ XXX.advancements.critereon.ItemSubPredicate
- XXX.advancements.critereon.ItemSubPredicate$Type
+ XXX.advancements.critereon.ItemSubPredicates
- XXX.advancements.critereon.ItemTrimPredicate
- XXX.advancements.critereon.ItemWritableBookPredicate$PagePredicate
- XXX.advancements.critereon.ItemWrittenBookPredicate$PagePredicate
- XXX.advancements.packs.package-info
- XXX.advancements.packs.UpdateOneTwentyOneAdvancementProvider
+ XXX.advancements.packs.UpdateOneTwentyOneAdventureAdvancements
- XXX.advancements.packs.VanillaAdvancementProvider
+ XXX.advancements.packs.VanillaAdventureAdvancements
- XXX.advancements.packs.VanillaHusbandryAdvancements
+ XXX.advancements.packs.VanillaNetherAdvancements
- XXX.advancements.packs.VanillaStoryAdvancements
+ XXX.advancements.packs.VanillaTheEndAdvancements
+ XXX.blaze3d.audio.OggAudioStream
- XXX.block.entity.EnchantingTableBlockEntity
+ XXX.block.entity.EnchantmentTableBlockEntity
- XXX.client.sounds.FiniteAudioStream
- XXX.client.sounds.JOrbisAudioStream
- XXX.commands.data.BlockDataAccessor
+ XXX.commands.data.BlockDataAccessor$1
- XXX.commands.data.DataAccessor
+ XXX.commands.data.DataCommands
- XXX.commands.data.DataCommands$DataManipulator
+ XXX.commands.data.DataCommands$DataManipulatorDecorator
- XXX.commands.data.DataCommands$DataProvider
+ XXX.commands.data.DataCommands$StringProcessor
- XXX.commands.data.EntityDataAccessor
+ XXX.commands.data.EntityDataAccessor$1
- XXX.commands.data.package-info
- XXX.commands.data.StorageDataAccessor
+ XXX.commands.data.StorageDataAccessor$1
+ XXX.common.custom.BeeDebugPayload
- XXX.common.custom.BeeDebugPayload$BeeInfo
+ XXX.common.custom.BrainDebugPayload
- XXX.common.custom.BrainDebugPayload$BrainDump
+ XXX.common.custom.BrandPayload
- XXX.common.custom.BreezeDebugPayload
+ XXX.common.custom.BreezeDebugPayload$BreezeInfo
- XXX.common.custom.CustomPacketPayload
+ XXX.common.custom.CustomPacketPayload$1
- XXX.common.custom.CustomPacketPayload$FallbackProvider
+ XXX.common.custom.CustomPacketPayload$Type
- XXX.common.custom.CustomPacketPayload$TypeAndCodec
+ XXX.common.custom.DiscardedPayload
- XXX.common.custom.GameEventDebugPayload
+ XXX.common.custom.GameEventListenerDebugPayload
- XXX.common.custom.GameTestAddMarkerDebugPayload
+ XXX.common.custom.GameTestClearMarkersDebugPayload
- XXX.common.custom.GoalDebugPayload
+ XXX.common.custom.GoalDebugPayload$DebugGoal
- XXX.common.custom.HiveDebugPayload
+ XXX.common.custom.HiveDebugPayload$HiveInfo
- XXX.common.custom.NeighborUpdatesDebugPayload
- XXX.common.custom.package-info
+ XXX.common.custom.PathfindingDebugPayload
- XXX.common.custom.PoiAddedDebugPayload
+ XXX.common.custom.PoiRemovedDebugPayload
- XXX.common.custom.PoiTicketCountDebugPayload
+ XXX.common.custom.RaidsDebugPayload
- XXX.common.custom.StructuresDebugPayload
+ XXX.common.custom.StructuresDebugPayload$PieceInfo
- XXX.common.custom.VillageSectionsDebugPayload
+ XXX.common.custom.WorldGenAttemptDebugPayload
- XXX.core.component.DataComponentMap$Builder
+ XXX.core.component.DataComponentMap$Builder$SimpleMap
- XXX.core.component.DataComponentPatch
+ XXX.core.component.DataComponentPatch$1
- XXX.core.component.DataComponentPatch$Builder
+ XXX.core.component.DataComponentPatch$PatchKey
- XXX.core.component.DataComponentPatch$SplitResult
+ XXX.core.component.DataComponentPredicate
- XXX.core.component.DataComponentPredicate$Builder
- XXX.core.component.DataComponents
+ XXX.core.component.DataComponentType
- XXX.core.component.DataComponentType$Builder
+ XXX.core.component.DataComponentType$Builder$SimpleType
- XXX.core.component.package-info
+ XXX.core.component.PatchedDataComponentMap
- XXX.core.component.TypedDataComponent
+ XXX.core.component.TypedDataComponent$1
+ XXX.core.dispenser.BlockSource
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
+ XXX.core.dispenser.DispenseItemBehavior$2
- XXX.core.dispenser.DispenseItemBehavior$3
+ XXX.core.dispenser.DispenseItemBehavior$4
- XXX.core.dispenser.DispenseItemBehavior$5
+ XXX.core.dispenser.DispenseItemBehavior$6
- XXX.core.dispenser.DispenseItemBehavior$7
+ XXX.core.dispenser.DispenseItemBehavior$8
- XXX.core.dispenser.DispenseItemBehavior$9
+ XXX.core.dispenser.OptionalDispenseItemBehavior
+ XXX.core.dispenser.package-info
- XXX.core.dispenser.ProjectileDispenseBehavior
+ XXX.core.dispenser.ShearsDispenseItemBehavior
- XXX.core.dispenser.ShulkerBoxDispenseBehavior
+ XXX.core.particles.BlockParticleOption
+ XXX.core.particles.DustColorTransitionOptions
+ XXX.core.particles.DustParticleOptionsBase
- XXX.core.particles.ItemParticleOption
+ XXX.core.particles.ItemParticleOption$1
- XXX.core.particles.package-info
+ XXX.core.particles.ParticleType
- XXX.core.particles.ParticleTypes
+ XXX.core.particles.ParticleTypes$1
- XXX.core.particles.SculkChargeParticleOptions
+ XXX.core.particles.SculkChargeParticleOptions$1
+ XXX.core.particles.ShriekParticleOption$1
- XXX.core.particles.SimpleParticleType
+ XXX.core.particles.SimpleParticleType$1
+ XXX.core.particles.VibrationParticleOption$1
+ XXX.core.registries.BuiltInRegistries
- XXX.core.registries.BuiltInRegistries$RegistryBootstrap
- XXX.core.registries.package-info
+ XXX.core.registries.Registries
+ XXX.data.advancements.AdvancementProvider
- XXX.data.advancements.AdvancementSubProvider
+ XXX.data.advancements.package-info
+ XXX.data.info.BiomeParametersDumpReport
- XXX.data.info.BlockListReport
+ XXX.data.info.CommandsReport
- XXX.data.info.ItemListReport
- XXX.data.info.package-info
+ XXX.data.info.RegistryDumpReport
+ XXX.data.loot.BlockLootSubProvider
- XXX.data.loot.EntityLootSubProvider
+ XXX.data.loot.LootTableProvider
- XXX.data.loot.LootTableProvider$SubProviderEntry
+ XXX.data.loot.LootTableSubProvider
- XXX.data.loot.package-info
+ XXX.data.metadata.package-info
- XXX.data.metadata.PackMetadataGenerator
- XXX.data.models.BlockModelGenerators
+ XXX.data.models.BlockModelGenerators$1
- XXX.data.models.BlockModelGenerators$BlockEntityModelGenerator
+ XXX.data.models.BlockModelGenerators$BlockFamilyProvider
- XXX.data.models.BlockModelGenerators$BlockStateGeneratorSupplier
+ XXX.data.models.BlockModelGenerators$BookSlotModelCacheKey
- XXX.data.models.BlockModelGenerators$TintState
+ XXX.data.models.BlockModelGenerators$WoodProvider
- XXX.data.models.ItemModelGenerators
+ XXX.data.models.ItemModelGenerators$TrimModelData
- XXX.data.models.ModelProvider
- XXX.data.models.package-info
+ XXX.data.recipes.package-info
- XXX.data.recipes.RecipeBuilder
+ XXX.data.recipes.RecipeBuilder$1
- XXX.data.recipes.RecipeCategory
+ XXX.data.recipes.RecipeOutput
- XXX.data.recipes.RecipeProvider
+ XXX.data.recipes.RecipeProvider$1
- XXX.data.recipes.ShapedRecipeBuilder
+ XXX.data.recipes.ShapelessRecipeBuilder
- XXX.data.recipes.SimpleCookingRecipeBuilder
+ XXX.data.recipes.SingleItemRecipeBuilder
- XXX.data.recipes.SmithingTransformRecipeBuilder
+ XXX.data.recipes.SmithingTrimRecipeBuilder
- XXX.data.recipes.SpecialRecipeBuilder
+ XXX.data.registries.package-info
+ XXX.data.registries.RegistriesDatapackGenerator
- XXX.data.registries.RegistryPatchGenerator
+ XXX.data.registries.UpdateOneTwentyOneRegistries
- XXX.data.registries.VanillaRegistries
- XXX.data.structures.NbtToSnbt
+ XXX.data.structures.package-info
+ XXX.data.structures.SnbtDatafixer
- XXX.data.structures.SnbtToNbt
+ XXX.data.structures.SnbtToNbt$Filter
- XXX.data.structures.SnbtToNbt$StructureConversionException
+ XXX.data.structures.SnbtToNbt$TaskResult
- XXX.data.structures.StructureUpdater
- XXX.data.tags.BannerPatternTagsProvider
+ XXX.data.tags.BiomeTagsProvider
- XXX.data.tags.CatVariantTagsProvider
+ XXX.data.tags.DamageTypeTagsProvider
- XXX.data.tags.EnchantmentTagsProvider
- XXX.data.tags.UpdateOneTwentyOneEnchantmentTagsProvider
+ XXX.data.tags.UpdateOneTwentyOneEntityTypeTagsProvider
- XXX.data.tags.UpdateOneTwentyOneItemTagsProvider
+ XXX.data.tags.UpdateOneTwentyOneStructureTagsProvider
- XXX.data.tags.VanillaBlockTagsProvider
- XXX.datafix.fixes.EmptyItemInVillagerTradeFix
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
- XXX.datafix.fixes.FixProjectileStoredItem
+ XXX.datafix.fixes.FixProjectileStoredItem$SubFixer
- XXX.datafix.fixes.ForcePoiRebuild
+ XXX.datafix.fixes.FurnaceRecipeFix
- XXX.datafix.fixes.GoatHornIdFix
+ XXX.datafix.fixes.GossipUUIDFix
- XXX.datafix.fixes.HeightmapRenamingFix
+ XXX.datafix.fixes.HorseBodyArmorItemFix
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
- XXX.datafix.fixes.ItemStackComponentizationFix
+ XXX.datafix.fixes.ItemStackComponentizationFix$ItemStackData
+ XXX.datafix.fixes.ItemStackComponentRemainderFix
- XXX.datafix.fixes.ItemStackCustomNameToOverrideComponentFix
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
- XXX.datafix.fixes.LegacyDragonFightFix
+ XXX.datafix.fixes.LevelDataGeneratorOptionsFix
- XXX.datafix.fixes.LevelFlatGeneratorInfoFix
+ XXX.datafix.fixes.LevelLegacyWorldGenSettingsFix
- XXX.datafix.fixes.LevelUUIDFix
+ XXX.datafix.fixes.LodestoneCompassComponentFix
- XXX.datafix.fixes.MapBannerBlockPosFormatFix
+ XXX.datafix.fixes.MapIdFix
- XXX.datafix.fixes.MemoryExpiryDataFix
+ XXX.datafix.fixes.MissingDimensionFix
- XXX.datafix.fixes.MobEffectIdFix
+ XXX.datafix.fixes.MobSpawnerEntityIdentifiersFix
- XXX.datafix.fixes.NamedEntityFix
+ XXX.datafix.fixes.NamedEntityWriteReadFix
- XXX.datafix.fixes.NamespacedTypeRenameFix
+ XXX.datafix.fixes.NewVillageFix
- XXX.datafix.fixes.ObjectiveDisplayNameFix
+ XXX.datafix.fixes.ObjectiveRenderTypeFix
- XXX.datafix.fixes.OminousBannerBlockEntityRenameFix
+ XXX.datafix.fixes.OminousBannerRenameFix
- XXX.datafix.fixes.OptionsAccessibilityOnboardFix
+ XXX.datafix.fixes.OptionsAddTextBackgroundFix
- XXX.datafix.fixes.OptionsAmbientOcclusionFix
+ XXX.datafix.fixes.OptionsForceVBOFix
- XXX.datafix.fixes.OptionsKeyLwjgl3Fix
+ XXX.datafix.fixes.OptionsKeyTranslationFix
- XXX.datafix.fixes.OptionsLowerCaseLanguageFix
+ XXX.datafix.fixes.OptionsProgrammerArtFix
- XXX.datafix.fixes.OptionsRenameFieldFix
+ XXX.datafix.fixes.OverreachingTickFix
- XXX.datafix.fixes.ParticleUnflatteningFix
+ XXX.datafix.schemas.package-info
- XXX.datafix.schemas.V3825
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
+ XXX.entity.decoration.ItemFrame$2
- XXX.entity.decoration.LeashFenceKnotEntity
- XXX.entity.decoration.package-info
+ XXX.entity.decoration.Painting
- XXX.entity.decoration.PaintingVariant
+ XXX.entity.decoration.PaintingVariants
+ XXX.entity.item.FallingBlockEntity
- XXX.entity.item.ItemEntity
+ XXX.entity.item.ItemEntity$1
+ XXX.item.alchemy.Potion
- XXX.item.alchemy.PotionBrewing
+ XXX.jfr.callback.package-info
- XXX.jfr.callback.ProfiledDuration
- XXX.jfr.event.ChunkGenerationEvent
+ XXX.jfr.event.ChunkGenerationEvent$Fields
- XXX.jfr.event.ChunkRegionIoEvent
+ XXX.jfr.event.ChunkRegionIoEvent$Fields
- XXX.jfr.event.ChunkRegionReadEvent
+ XXX.jfr.event.ChunkRegionWriteEvent
- XXX.jfr.event.NetworkSummaryEvent
+ XXX.jfr.event.NetworkSummaryEvent$Fields
- XXX.jfr.event.NetworkSummaryEvent$SumAggregation
- XXX.jfr.event.package-info
+ XXX.jfr.event.PacketEvent
- XXX.jfr.event.PacketEvent$Fields
+ XXX.jfr.event.PacketReceivedEvent
- XXX.jfr.event.PacketSentEvent
+ XXX.jfr.event.ServerTickTimeEvent
- XXX.jfr.event.ServerTickTimeEvent$Fields
+ XXX.jfr.event.WorldLoadFinishedEvent
- XXX.jfr.parse.JfrStatsParser
+ XXX.jfr.parse.JfrStatsParser$1
- XXX.jfr.parse.JfrStatsParser$MutableCountAndSize
+ XXX.jfr.parse.JfrStatsResult
- XXX.jfr.parse.package-info
+ XXX.jfr.serialize.JfrResultJsonSerializer
- XXX.jfr.serialize.package-info
+ XXX.jfr.stats.ChunkGenStat
- XXX.jfr.stats.ChunkIdentification
+ XXX.jfr.stats.CpuLoadStat
- XXX.jfr.stats.FileIOStat
+ XXX.jfr.stats.FileIOStat$Summary
- XXX.jfr.stats.GcHeapStat
+ XXX.jfr.stats.GcHeapStat$Summary
- XXX.jfr.stats.GcHeapStat$Timing
+ XXX.jfr.stats.IoSummary
- XXX.jfr.stats.IoSummary$CountAndSize
+ XXX.jfr.stats.package-info
+ XXX.jfr.stats.PacketIdentification
- XXX.jfr.stats.ThreadAllocationStat
+ XXX.jfr.stats.ThreadAllocationStat$Summary
- XXX.jfr.stats.TickTimeStat
+ XXX.jfr.stats.TimedStat
- XXX.jfr.stats.TimedStatSummary
+ XXX.level.progress.ChunkProgressListener
- XXX.level.progress.ChunkProgressListenerFactory
+ XXX.level.progress.LoggerChunkProgressListener
- XXX.level.progress.package-info
- XXX.level.progress.ProcessorChunkProgressListener
+ XXX.level.progress.StoringChunkProgressListener
+ XXX.level.storage.package-info
- XXX.level.timers.FunctionCallback
+ XXX.level.timers.FunctionCallback$Serializer
- XXX.level.timers.FunctionTagCallback
+ XXX.level.timers.FunctionTagCallback$Serializer
+ XXX.level.timers.package-info
- XXX.level.timers.TimerCallback
+ XXX.level.timers.TimerCallback$Serializer
- XXX.level.timers.TimerCallbacks
+ XXX.level.timers.TimerQueue
- XXX.level.timers.TimerQueue$Event
- XXX.level.validation.ContentValidationException
+ XXX.level.validation.DirectoryValidator
- XXX.level.validation.DirectoryValidator$1
+ XXX.level.validation.ForbiddenSymlinkInfo
+ XXX.level.validation.package-info
- XXX.level.validation.PathAllowList
+ XXX.level.validation.PathAllowList$ConfigEntry
- XXX.level.validation.PathAllowList$EntryType
+ XXX.login.custom.CustomQueryAnswerPayload
- XXX.login.custom.CustomQueryPayload
+ XXX.login.custom.DiscardedQueryAnswerPayload
- XXX.login.custom.DiscardedQueryPayload
+ XXX.login.custom.package-info
+ XXX.loot.entries.AlternativesEntry
- XXX.loot.entries.AlternativesEntry$Builder
+ XXX.loot.entries.ComposableEntryContainer
- XXX.loot.entries.CompositeEntryBase
+ XXX.loot.entries.CompositeEntryBase$CompositeEntryConstructor
- XXX.loot.entries.DynamicLoot
+ XXX.loot.entries.EmptyLootItem
- XXX.loot.entries.EntryGroup
+ XXX.loot.entries.EntryGroup$Builder
- XXX.loot.entries.LootItem
+ XXX.loot.entries.LootPoolEntries
- XXX.loot.entries.LootPoolEntry
+ XXX.loot.entries.LootPoolEntryContainer
- XXX.loot.entries.LootPoolEntryContainer$Builder
+ XXX.loot.entries.LootPoolEntryType
- XXX.loot.entries.LootPoolSingletonContainer
+ XXX.loot.entries.LootPoolSingletonContainer$1
- XXX.loot.entries.LootPoolSingletonContainer$Builder
+ XXX.loot.entries.LootPoolSingletonContainer$DummyBuilder
- XXX.loot.entries.LootPoolSingletonContainer$EntryBase
+ XXX.loot.entries.LootPoolSingletonContainer$EntryConstructor
- XXX.loot.entries.NestedLootTable
+ XXX.loot.entries.package-info
+ XXX.loot.entries.SequentialEntry
- XXX.loot.entries.SequentialEntry$Builder
+ XXX.loot.entries.TagEntry
- XXX.loot.entries.TagEntry$1
- XXX.loot.functions.ApplyBonusCount
+ XXX.loot.functions.ApplyBonusCount$BinomialWithBonusCount
- XXX.loot.functions.ApplyBonusCount$Formula
+ XXX.loot.functions.ApplyBonusCount$FormulaType
- XXX.loot.functions.ApplyBonusCount$OreDrops
+ XXX.loot.functions.ApplyBonusCount$UniformBonusCount
- XXX.loot.functions.ApplyExplosionDecay
+ XXX.loot.functions.CopyBlockState
- XXX.loot.functions.CopyBlockState$Builder
+ XXX.loot.functions.CopyComponentsFunction
- XXX.loot.functions.CopyComponentsFunction$Builder
+ XXX.loot.functions.CopyComponentsFunction$Source
- XXX.loot.functions.CopyCustomDataFunction
+ XXX.loot.functions.CopyCustomDataFunction$Builder
- XXX.loot.functions.CopyCustomDataFunction$CopyOperation
+ XXX.loot.functions.CopyCustomDataFunction$MergeStrategy
- XXX.loot.functions.CopyCustomDataFunction$MergeStrategy$1
+ XXX.loot.functions.CopyCustomDataFunction$MergeStrategy$2
- XXX.loot.functions.CopyCustomDataFunction$MergeStrategy$3
+ XXX.loot.functions.CopyNameFunction
- XXX.loot.functions.CopyNameFunction$NameSource
+ XXX.loot.functions.EnchantRandomlyFunction
- XXX.loot.functions.EnchantRandomlyFunction$Builder
+ XXX.loot.functions.EnchantWithLevelsFunction
- XXX.loot.functions.EnchantWithLevelsFunction$Builder
+ XXX.loot.functions.ExplorationMapFunction
- XXX.loot.functions.ExplorationMapFunction$Builder
+ XXX.loot.functions.FillPlayerHead
- XXX.loot.functions.FilteredFunction
+ XXX.loot.functions.package-info
- XXX.loot.functions.SequenceFunction
+ XXX.loot.functions.SetAttributesFunction
- XXX.loot.functions.SetAttributesFunction$Builder
+ XXX.loot.functions.SetAttributesFunction$Modifier
- XXX.loot.functions.SetAttributesFunction$ModifierBuilder
+ XXX.loot.functions.SetBannerPatternFunction
- XXX.loot.functions.SetBannerPatternFunction$Builder
+ XXX.loot.functions.SetBookCoverFunction
- XXX.loot.functions.SetComponentsFunction
+ XXX.loot.functions.SetContainerContents
- XXX.loot.functions.SetContainerContents$Builder
+ XXX.loot.functions.SetContainerLootTable
- XXX.loot.functions.SetCustomDataFunction
- XXX.loot.functions.SetLoreFunction
+ XXX.loot.functions.SetLoreFunction$Builder
- XXX.loot.functions.SetNameFunction
+ XXX.loot.functions.SetNameFunction$Target
- XXX.loot.functions.SetOminousBottleAmplifierFunction
+ XXX.loot.functions.SetPotionFunction
- XXX.loot.functions.SetStewEffectFunction
+ XXX.loot.functions.SetStewEffectFunction$Builder
- XXX.loot.functions.SetStewEffectFunction$EffectEntry
+ XXX.loot.functions.SetWritableBookPagesFunction
- XXX.loot.functions.SetWrittenBookPagesFunction
+ XXX.loot.functions.SmeltItemFunction
- XXX.loot.functions.ToggleTooltips
+ XXX.loot.functions.ToggleTooltips$ComponentToggle
- XXX.loot.functions.ToggleTooltips$TooltipWither
+ XXX.loot.packs.package-info
+ XXX.loot.packs.TradeRebalanceChestLoot
- XXX.loot.packs.TradeRebalanceLootTableProvider
+ XXX.loot.packs.UpdateOneTwentyOneBlockLoot
- XXX.loot.packs.UpdateOneTwentyOneChestLoot
+ XXX.loot.packs.UpdateOneTwentyOneEntityLoot
- XXX.loot.packs.UpdateOneTwentyOneEquipmentLoot
+ XXX.loot.packs.UpdateOneTwentyOneLootTableProvider
- XXX.loot.packs.UpdateOneTwentyOneShearingLoot
+ XXX.loot.packs.VanillaArchaeologyLoot
- XXX.loot.packs.VanillaBlockLoot
+ XXX.loot.packs.VanillaChestLoot
- XXX.loot.packs.VanillaEntityLoot
+ XXX.loot.packs.VanillaEquipmentLoot
- XXX.loot.packs.VanillaFishingLoot
+ XXX.loot.packs.VanillaGiftLoot
- XXX.loot.packs.VanillaLootTableProvider
+ XXX.loot.packs.VanillaPiglinBarterLoot
- XXX.loot.packs.VanillaShearingLoot
+ XXX.loot.parameters.LootContextParam
+ XXX.loot.parameters.LootContextParams
- XXX.loot.parameters.LootContextParamSet
+ XXX.loot.parameters.LootContextParamSet$Builder
- XXX.loot.parameters.LootContextParamSets
- XXX.loot.parameters.package-info
+ XXX.loot.predicates.AllOfCondition
- XXX.loot.predicates.AllOfCondition$Builder
+ XXX.loot.predicates.AnyOfCondition
- XXX.loot.predicates.AnyOfCondition$Builder
+ XXX.loot.predicates.BonusLevelTableCondition
- XXX.loot.predicates.CompositeLootItemCondition
+ XXX.loot.predicates.CompositeLootItemCondition$Builder
- XXX.loot.predicates.ConditionReference
+ XXX.loot.predicates.ConditionUserBuilder
- XXX.loot.predicates.DamageSourceCondition
+ XXX.loot.predicates.EntityHasScoreCondition
- XXX.loot.predicates.EntityHasScoreCondition$Builder
+ XXX.loot.predicates.ExplosionCondition
- XXX.loot.predicates.InvertedLootItemCondition
+ XXX.loot.predicates.LocationCheck
- XXX.loot.predicates.LootItemBlockStatePropertyCondition
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition$Builder
- XXX.loot.predicates.LootItemCondition
+ XXX.loot.predicates.LootItemCondition$Builder
+ XXX.loot.predicates.LootItemConditions
- XXX.loot.predicates.LootItemConditionType
- XXX.loot.predicates.LootItemEntityPropertyCondition
+ XXX.loot.predicates.LootItemKilledByPlayerCondition
- XXX.loot.predicates.LootItemRandomChanceCondition
+ XXX.loot.predicates.LootItemRandomChanceWithLootingCondition
- XXX.loot.predicates.MatchTool
- XXX.loot.predicates.package-info
+ XXX.loot.predicates.TimeCheck
- XXX.loot.predicates.TimeCheck$Builder
+ XXX.loot.predicates.ValueCheckCondition
- XXX.loot.predicates.WeatherCheck
+ XXX.loot.predicates.WeatherCheck$Builder
- XXX.metadata.pack.package-info
+ XXX.metadata.pack.PackMetadataSection
+ XXX.metrics.profiling.ActiveMetricsRecorder
- XXX.metrics.profiling.InactiveMetricsRecorder
+ XXX.metrics.profiling.MetricsRecorder
- XXX.metrics.profiling.package-info
- XXX.metrics.profiling.ProfilerSamplerAdapter
+ XXX.metrics.profiling.ServerMetricsSamplersProvider
- XXX.metrics.profiling.ServerMetricsSamplersProvider$1
+ XXX.metrics.profiling.ServerMetricsSamplersProvider$CpuStats
+ XXX.metrics.storage.MetricsPersister
+ XXX.metrics.storage.package-info
- XXX.metrics.storage.RecordedDeviation
- XXX.minecraft.core.package-info
+ XXX.minecraft.data.BlockFamilies
- XXX.minecraft.data.BlockFamily
+ XXX.minecraft.data.BlockFamily$Builder
- XXX.minecraft.data.BlockFamily$Variant
+ XXX.minecraft.data.CachedOutput
- XXX.minecraft.data.DataGenerator
+ XXX.minecraft.data.DataGenerator$PackGenerator
- XXX.minecraft.data.DataProvider
+ XXX.minecraft.data.DataProvider$Factory
- XXX.minecraft.data.HashCache
+ XXX.minecraft.data.HashCache$1
- XXX.minecraft.data.HashCache$CacheUpdater
+ XXX.minecraft.data.HashCache$ProviderCache
- XXX.minecraft.data.HashCache$ProviderCacheBuilder
+ XXX.minecraft.data.HashCache$UpdateFunction
- XXX.minecraft.data.HashCache$UpdateResult
+ XXX.minecraft.data.Main
+ XXX.minecraft.data.package-info
- XXX.minecraft.data.PackOutput
+ XXX.minecraft.data.PackOutput$PathProvider
- XXX.minecraft.data.PackOutput$Target
- XXX.minecraft.network.package-info
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
- XXX.minecraft.references.Blocks
+ XXX.minecraft.references.Items
- XXX.minecraft.resources.DelegatingOps
+ XXX.minecraft.resources.FileToIdConverter
- XXX.minecraft.resources.HolderSetCodec
- XXX.minecraft.resources.package-info
+ XXX.minecraft.resources.RegistryDataLoader
- XXX.minecraft.resources.RegistryDataLoader$1
+ XXX.minecraft.resources.RegistryDataLoader$Loader
- XXX.minecraft.resources.RegistryDataLoader$LoadingFunction
+ XXX.minecraft.resources.RegistryDataLoader$RegistryData
- XXX.minecraft.resources.RegistryFileCodec
+ XXX.minecraft.resources.RegistryFixedCodec
- XXX.minecraft.resources.RegistryOps
+ XXX.minecraft.resources.RegistryOps$1
- XXX.minecraft.resources.RegistryOps$2
+ XXX.minecraft.resources.RegistryOps$RegistryInfo
- XXX.minecraft.resources.RegistryOps$RegistryInfoLookup
+ XXX.minecraft.resources.ResourceKey
- XXX.minecraft.resources.ResourceKey$InternKey
+ XXX.minecraft.resources.ResourceLocation
- XXX.minecraft.resources.ResourceLocation$Dummy
+ XXX.minecraft.resources.ResourceLocation$Serializer
+ XXX.minecraft.server.Bootstrap
- XXX.minecraft.server.Bootstrap$1
+ XXX.minecraft.server.ChainedJsonException
- XXX.minecraft.server.ChainedJsonException$Entry
+ XXX.minecraft.server.ConsoleInput
- XXX.minecraft.server.DebugLoggedPrintStream
+ XXX.minecraft.server.Eula
- XXX.minecraft.server.LoggedPrintStream
+ XXX.minecraft.server.Main
- XXX.minecraft.server.Main$1
+ XXX.minecraft.server.MinecraftServer
- XXX.minecraft.server.MinecraftServer$1
+ XXX.minecraft.server.MinecraftServer$ReloadableResources
- XXX.minecraft.server.MinecraftServer$ServerResourcePackInfo
+ XXX.minecraft.server.MinecraftServer$TimeProfiler
- XXX.minecraft.server.MinecraftServer$TimeProfiler$1
+ XXX.minecraft.server.package-info
+ XXX.minecraft.server.PlayerAdvancements
- XXX.minecraft.server.PlayerAdvancements$Data
+ XXX.minecraft.server.RegistryLayer
- XXX.minecraft.server.ReloadableServerRegistries
+ XXX.minecraft.server.ReloadableServerRegistries$EmptyTagLookupWrapper
- XXX.minecraft.server.ReloadableServerRegistries$Holder
+ XXX.minecraft.server.ReloadableServerResources
- XXX.minecraft.server.ReloadableServerResources$ConfigurableRegistryLookup
+ XXX.minecraft.server.ReloadableServerResources$ConfigurableRegistryLookup$1
- XXX.minecraft.server.ReloadableServerResources$MissingTagAccessPolicy
+ XXX.minecraft.server.RunningOnDifferentThreadException
- XXX.minecraft.server.ServerAdvancementManager
+ XXX.minecraft.server.ServerFunctionLibrary
- XXX.minecraft.server.ServerFunctionManager
+ XXX.minecraft.server.ServerInfo
- XXX.minecraft.server.ServerInterface
+ XXX.minecraft.server.ServerScoreboard
- XXX.minecraft.server.ServerScoreboard$Method
+ XXX.minecraft.server.ServerTickRateManager
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
- XXX.minecraft.tags.BannerPatternTags
+ XXX.minecraft.tags.BiomeTags
- XXX.minecraft.tags.BlockTags
+ XXX.minecraft.tags.CatVariantTags
- XXX.minecraft.tags.DamageTypeTags
- XXX.minecraft.util.NullOps$NullMapBuilder
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
+ XXX.minecraft.world.ItemInteractionResult
- XXX.minecraft.world.LockCode
+ XXX.minecraft.world.MenuProvider
- XXX.minecraft.world.Nameable
- XXX.minecraft.world.package-info
- XXX.minecraft.world.RandomizableContainer
+ XXX.minecraft.world.RandomSequence
- XXX.minecraft.world.RandomSequences
+ XXX.minecraft.world.RandomSequences$DirtyMarkingRandomSource
+ XXX.minecraft.world.SimpleContainer
- XXX.minecraft.world.SimpleMenuProvider
+ XXX.minecraft.world.TickRateManager
- XXX.minecraft.world.WorldlyContainer
+ XXX.minecraft.world.WorldlyContainerHolder
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
+ XXX.models.model.ModelTemplate$JsonFactory
- XXX.models.model.ModelTemplates
+ XXX.models.model.package-info
+ XXX.models.model.TexturedModel
- XXX.models.model.TexturedModel$Provider
+ XXX.models.model.TextureMapping
- XXX.models.model.TextureSlot
+ XXX.monitoring.jmx.MinecraftServerStatistics
- XXX.monitoring.jmx.MinecraftServerStatistics$AttributeDescription
+ XXX.monitoring.jmx.package-info
- XXX.network.codec.ByteBufCodecs$28
+ XXX.network.codec.ByteBufCodecs$3
- XXX.network.codec.ByteBufCodecs$4
+ XXX.network.codec.ByteBufCodecs$5
- XXX.network.codec.ByteBufCodecs$6
+ XXX.network.codec.ByteBufCodecs$7
- XXX.network.codec.ByteBufCodecs$8
+ XXX.network.codec.ByteBufCodecs$9
- XXX.network.codec.IdDispatchCodec
+ XXX.network.codec.IdDispatchCodec$Builder
- XXX.network.codec.IdDispatchCodec$Entry
+ XXX.network.codec.package-info
+ XXX.network.codec.StreamCodec
- XXX.network.codec.StreamCodec$1
+ XXX.network.codec.StreamCodec$10
- XXX.network.codec.StreamCodec$11
+ XXX.network.codec.StreamCodec$12
- XXX.network.codec.StreamCodec$13
+ XXX.network.codec.StreamCodec$2
- XXX.network.codec.StreamCodec$3
+ XXX.network.codec.StreamCodec$4
- XXX.network.codec.StreamCodec$5
+ XXX.network.codec.StreamCodec$6
- XXX.network.codec.StreamCodec$7
+ XXX.network.codec.StreamCodec$8
- XXX.network.codec.StreamCodec$9
+ XXX.network.codec.StreamCodec$CodecOperation
- XXX.network.codec.StreamDecoder
+ XXX.network.codec.StreamEncoder
- XXX.network.codec.StreamMemberEncoder
- XXX.network.config.JoinWorldTask
+ XXX.network.config.package-info
+ XXX.network.config.ServerResourcePackConfigurationTask
- XXX.network.config.SynchronizeRegistriesTask
+ XXX.network.protocol.BundleDelimiterPacket
- XXX.network.protocol.BundlePacket
+ XXX.network.protocol.BundlerInfo
- XXX.network.protocol.BundlerInfo$1
+ XXX.network.protocol.BundlerInfo$1$1
- XXX.network.protocol.BundlerInfo$Bundler
+ XXX.network.protocol.package-info
+ XXX.network.protocol.Packet
- XXX.network.protocol.PacketFlow
+ XXX.network.protocol.PacketType
- XXX.network.protocol.PacketUtils
+ XXX.network.protocol.ProtocolCodecBuilder
- XXX.network.protocol.ProtocolInfoBuilder
+ XXX.network.protocol.ProtocolInfoBuilder$CodecEntry
- XXX.network.protocol.ProtocolInfoBuilder$Implementation
+ XXX.network.syncher.EntityDataAccessor
- XXX.network.syncher.EntityDataSerializer
+ XXX.network.syncher.EntityDataSerializer$ForValueType
- XXX.network.syncher.EntityDataSerializers
+ XXX.network.syncher.EntityDataSerializers$1
- XXX.network.syncher.EntityDataSerializers$2
+ XXX.network.syncher.EntityDataSerializers$3
- XXX.network.syncher.EntityDataSerializers$4
- XXX.network.syncher.package-info
+ XXX.network.syncher.SyncedDataHolder
- XXX.network.syncher.SynchedEntityData
+ XXX.network.syncher.SynchedEntityData$Builder
- XXX.network.syncher.SynchedEntityData$DataItem
+ XXX.network.syncher.SynchedEntityData$DataValue
+ XXX.packrat.commands.Grammar
- XXX.packrat.commands.package-info
- XXX.packrat.commands.ResourceLocationParseRule
+ XXX.packrat.commands.ResourceLookupRule
- XXX.packrat.commands.ResourceSuggestion
+ XXX.packrat.commands.StringReaderParserState
- XXX.packrat.commands.StringReaderTerms
+ XXX.packrat.commands.StringReaderTerms$TerminalCharacter
- XXX.packrat.commands.StringReaderTerms$TerminalWord
+ XXX.packrat.commands.TagParseRule
- XXX.packs.linkfs.DummyFileAttributes
+ XXX.packs.linkfs.LinkFileSystem
- XXX.packs.linkfs.LinkFileSystem$Builder
+ XXX.packs.linkfs.LinkFileSystem$DirectoryEntry
+ XXX.packs.linkfs.LinkFSFileStore
- XXX.packs.linkfs.LinkFSPath
+ XXX.packs.linkfs.LinkFSPath$1
- XXX.packs.linkfs.LinkFSPath$2
+ XXX.packs.linkfs.LinkFSPath$3
- XXX.packs.linkfs.LinkFSProvider
+ XXX.packs.linkfs.LinkFSProvider$1
- XXX.packs.linkfs.LinkFSProvider$2
+ XXX.packs.linkfs.package-info
- XXX.packs.linkfs.PathContents
+ XXX.packs.linkfs.PathContents$1
- XXX.packs.linkfs.PathContents$2
+ XXX.packs.linkfs.PathContents$DirectoryContents
- XXX.packs.linkfs.PathContents$FileContents
- XXX.packs.metadata.MetadataSectionSerializer
+ XXX.packs.metadata.MetadataSectionType
- XXX.packs.metadata.MetadataSectionType$1
+ XXX.packs.metadata.package-info
+ XXX.packs.repository.BuiltInPackSource
- XXX.packs.repository.BuiltInPackSource$1
+ XXX.packs.repository.FolderRepositorySource
- XXX.packs.repository.FolderRepositorySource$FolderPackDetector
+ XXX.packs.repository.KnownPack
- XXX.packs.repository.Pack
+ XXX.packs.repository.Pack$Metadata
- XXX.packs.repository.Pack$Position
+ XXX.packs.repository.Pack$ResourcesSupplier
+ XXX.packs.repository.package-info
- XXX.packs.repository.PackCompatibility
+ XXX.packs.repository.PackDetector
- XXX.packs.repository.PackRepository
+ XXX.packs.repository.PackSource
- XXX.packs.repository.PackSource$1
+ XXX.packs.repository.RepositorySource
- XXX.packs.repository.ServerPacksSource
- XXX.packs.resources.CloseableResourceManager
+ XXX.packs.resources.FallbackResourceManager
- XXX.packs.resources.FallbackResourceManager$1ResourceWithSourceAndIndex
+ XXX.packs.resources.FallbackResourceManager$EntryStack
- XXX.packs.resources.FallbackResourceManager$LeakedResourceWarningInputStream
+ XXX.packs.resources.FallbackResourceManager$PackEntry
- XXX.packs.resources.FallbackResourceManager$ResourceWithSource
+ XXX.packs.resources.IoSupplier
- XXX.packs.resources.MultiPackResourceManager
+ XXX.packs.resources.package-info
+ XXX.packs.resources.PreparableReloadListener
- XXX.packs.resources.PreparableReloadListener$PreparationBarrier
+ XXX.packs.resources.ProfiledReloadInstance
- XXX.packs.resources.ProfiledReloadInstance$State
- XXX.packs.resources.ReloadableResourceManager
+ XXX.packs.resources.ReloadInstance
+ XXX.packs.resources.Resource
- XXX.packs.resources.ResourceFilterSection
+ XXX.packs.resources.ResourceManager
- XXX.packs.resources.ResourceManager$Empty
+ XXX.packs.resources.ResourceManagerReloadListener
- XXX.packs.resources.ResourceMetadata
+ XXX.packs.resources.ResourceMetadata$1
- XXX.packs.resources.ResourceMetadata$2
+ XXX.packs.resources.ResourceMetadata$Builder
- XXX.packs.resources.ResourceMetadata$Builder$1
+ XXX.packs.resources.ResourceProvider
- XXX.packs.resources.SimpleJsonResourceReloadListener
+ XXX.packs.resources.SimplePreparableReloadListener
- XXX.packs.resources.SimpleReloadInstance
+ XXX.packs.resources.SimpleReloadInstance$1
- XXX.packs.resources.SimpleReloadInstance$StateFactory
- XXX.parsing.packrat.Atom
+ XXX.parsing.packrat.Control
- XXX.parsing.packrat.Dictionary
+ XXX.parsing.packrat.ErrorCollector
- XXX.parsing.packrat.ErrorCollector$LongestOnly
+ XXX.parsing.packrat.ErrorEntry
+ XXX.parsing.packrat.package-info
- XXX.parsing.packrat.ParseState
+ XXX.parsing.packrat.ParseState$CacheEntry
- XXX.parsing.packrat.ParseState$CacheKey
+ XXX.parsing.packrat.Rule
- XXX.parsing.packrat.Rule$RuleAction
+ XXX.parsing.packrat.Rule$SimpleRuleAction
- XXX.parsing.packrat.Rule$WrappedTerm
+ XXX.parsing.packrat.Scope
- XXX.parsing.packrat.SuggestionSupplier
+ XXX.parsing.packrat.Term
- XXX.parsing.packrat.Term$1
+ XXX.parsing.packrat.Term$2
- XXX.parsing.packrat.Term$Alternative
+ XXX.parsing.packrat.Term$Marker
- XXX.parsing.packrat.Term$Maybe
+ XXX.parsing.packrat.Term$Reference
- XXX.parsing.packrat.Term$Sequence
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
+ XXX.profiling.jfr.Environment
- XXX.profiling.jfr.JfrProfiler
+ XXX.profiling.jfr.JfrProfiler$1
- XXX.profiling.jfr.JvmProfiler
+ XXX.profiling.jfr.JvmProfiler$NoOpProfiler
+ XXX.profiling.jfr.package-info
- XXX.profiling.jfr.Percentiles
+ XXX.profiling.jfr.SummaryReporter
- XXX.profiling.metrics.MetricCategory
+ XXX.profiling.metrics.MetricSampler
- XXX.profiling.metrics.MetricSampler$MetricSamplerBuilder
+ XXX.profiling.metrics.MetricSampler$SamplerResult
- XXX.profiling.metrics.MetricSampler$ThresholdTest
+ XXX.profiling.metrics.MetricSampler$ValueIncreasedByPercentage
- XXX.profiling.metrics.MetricsRegistry
+ XXX.profiling.metrics.MetricsRegistry$AggregatedMetricSampler
- XXX.profiling.metrics.MetricsSamplerProvider
- XXX.profiling.metrics.package-info
+ XXX.profiling.metrics.ProfilerMeasured
- XXX.protocol.common.ClientboundCustomPayloadPacket
+ XXX.protocol.common.ClientboundDisconnectPacket
- XXX.protocol.common.ClientboundKeepAlivePacket
+ XXX.protocol.common.ClientboundPingPacket
- XXX.protocol.common.ClientboundResourcePackPopPacket
+ XXX.protocol.common.ClientboundResourcePackPushPacket
- XXX.protocol.common.ClientboundStoreCookiePacket
+ XXX.protocol.common.ClientboundTransferPacket
- XXX.protocol.common.ClientboundUpdateTagsPacket
+ XXX.protocol.common.ClientCommonPacketListener
+ XXX.protocol.common.CommonPacketTypes
+ XXX.protocol.common.package-info
+ XXX.protocol.common.ServerboundClientInformationPacket
- XXX.protocol.common.ServerboundCustomPayloadPacket
+ XXX.protocol.common.ServerboundKeepAlivePacket
- XXX.protocol.common.ServerboundPongPacket
+ XXX.protocol.common.ServerboundResourcePackPacket
- XXX.protocol.common.ServerboundResourcePackPacket$Action
- XXX.protocol.common.ServerCommonPacketListener
+ XXX.protocol.configuration.ClientboundFinishConfigurationPacket
- XXX.protocol.configuration.ClientboundRegistryDataPacket
+ XXX.protocol.configuration.ClientboundResetChatPacket
- XXX.protocol.configuration.ClientboundSelectKnownPacks
+ XXX.protocol.configuration.ClientboundUpdateEnabledFeaturesPacket
- XXX.protocol.configuration.ClientConfigurationPacketListener
- XXX.protocol.configuration.ConfigurationPacketTypes
+ XXX.protocol.configuration.ConfigurationProtocols
+ XXX.protocol.configuration.package-info
+ XXX.protocol.configuration.ServerboundFinishConfigurationPacket
- XXX.protocol.configuration.ServerboundSelectKnownPacks
- XXX.protocol.configuration.ServerConfigurationPacketListener
+ XXX.protocol.cookie.ClientboundCookieRequestPacket
- XXX.protocol.cookie.ClientCookiePacketListener
- XXX.protocol.cookie.CookiePacketTypes
+ XXX.protocol.cookie.package-info
- XXX.protocol.cookie.ServerboundCookieResponsePacket
+ XXX.protocol.cookie.ServerCookiePacketListener
+ XXX.protocol.game.ClientboundAddEntityPacket
- XXX.protocol.game.ClientboundAddExperienceOrbPacket
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
- XXX.protocol.game.ClientboundBundleDelimiterPacket
+ XXX.protocol.game.ClientboundBundlePacket
- XXX.protocol.game.ClientboundChangeDifficultyPacket
+ XXX.protocol.game.ClientboundChunkBatchFinishedPacket
- XXX.protocol.game.ClientboundChunkBatchStartPacket
+ XXX.protocol.game.ClientboundChunksBiomesPacket
- XXX.protocol.game.ClientboundChunksBiomesPacket$ChunkBiomeData
+ XXX.protocol.game.ClientboundClearTitlesPacket
- XXX.protocol.game.ClientboundCommandsPacket
+ XXX.protocol.game.ClientboundCommandsPacket$ArgumentNodeStub
- XXX.protocol.game.ClientboundCommandsPacket$Entry
+ XXX.protocol.game.ClientboundCommandsPacket$LiteralNodeStub
- XXX.protocol.game.ClientboundCommandsPacket$NodeResolver
+ XXX.protocol.game.ClientboundCommandsPacket$NodeStub
- XXX.protocol.game.ClientboundCommandSuggestionsPacket
+ XXX.protocol.game.ClientboundCommandSuggestionsPacket$Entry
- XXX.protocol.game.ClientboundContainerClosePacket
+ XXX.protocol.game.ClientboundContainerSetContentPacket
- XXX.protocol.game.ClientboundContainerSetDataPacket
+ XXX.protocol.game.ClientboundContainerSetSlotPacket
- XXX.protocol.game.ClientboundCooldownPacket
+ XXX.protocol.game.ClientboundCustomChatCompletionsPacket
- XXX.protocol.game.ClientboundCustomChatCompletionsPacket$Action
+ XXX.protocol.game.ClientboundDamageEventPacket
- XXX.protocol.game.ClientboundDebugSamplePacket
+ XXX.protocol.game.ClientboundDeleteChatPacket
- XXX.protocol.game.ClientboundDisguisedChatPacket
+ XXX.protocol.game.ClientboundEntityEventPacket
- XXX.protocol.game.ClientboundExplodePacket
+ XXX.protocol.game.ClientboundForgetLevelChunkPacket
- XXX.protocol.game.ClientboundGameEventPacket
+ XXX.protocol.game.ClientboundGameEventPacket$Type
- XXX.protocol.game.ClientboundHorseScreenOpenPacket
+ XXX.protocol.game.ClientboundHurtAnimationPacket
- XXX.protocol.game.ClientboundInitializeBorderPacket
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
+ XXX.protocol.game.ClientboundProjectilePowerPacket
- XXX.protocol.game.ClientboundRecipePacket
+ XXX.protocol.game.ClientboundRecipePacket$State
- XXX.protocol.game.ClientboundRemoveEntitiesPacket
+ XXX.protocol.game.ClientboundRemoveMobEffectPacket
- XXX.protocol.game.ClientboundResetScorePacket
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
+ XXX.protocol.game.ClientboundStartConfigurationPacket
- XXX.protocol.game.ClientboundStopSoundPacket
+ XXX.protocol.game.ClientboundSystemChatPacket
- XXX.protocol.game.ClientboundTabListPacket
+ XXX.protocol.game.ClientboundTagQueryPacket
- XXX.protocol.game.ClientboundTakeItemEntityPacket
+ XXX.protocol.game.ClientboundTeleportEntityPacket
- XXX.protocol.game.ClientboundTickingStatePacket
+ XXX.protocol.game.ClientboundTickingStepPacket
- XXX.protocol.game.ClientboundUpdateAdvancementsPacket
+ XXX.protocol.game.ClientboundUpdateAttributesPacket
- XXX.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
+ XXX.protocol.game.ClientboundUpdateMobEffectPacket
- XXX.protocol.game.ClientboundUpdateRecipesPacket
- XXX.protocol.game.ClientGamePacketListener
+ XXX.protocol.game.CommonPlayerSpawnInfo
- XXX.protocol.game.DebugEntityNameGenerator
+ XXX.protocol.game.DebugPackets
- XXX.protocol.game.GamePacketTypes
+ XXX.protocol.game.GameProtocols
+ XXX.protocol.game.package-info
- XXX.protocol.game.ServerboundAcceptTeleportationPacket
+ XXX.protocol.game.ServerboundBlockEntityTagQueryPacket
- XXX.protocol.game.ServerboundChangeDifficultyPacket
+ XXX.protocol.game.ServerboundChatAckPacket
- XXX.protocol.game.ServerboundChatCommandPacket
+ XXX.protocol.game.ServerboundChatCommandSignedPacket
- XXX.protocol.game.ServerboundChatPacket
+ XXX.protocol.game.ServerboundChatSessionUpdatePacket
- XXX.protocol.game.ServerboundChunkBatchReceivedPacket
+ XXX.protocol.game.ServerboundClientCommandPacket
- XXX.protocol.game.ServerboundClientCommandPacket$Action
+ XXX.protocol.game.ServerboundCommandSuggestionPacket
- XXX.protocol.game.ServerboundConfigurationAcknowledgedPacket
+ XXX.protocol.game.ServerboundContainerButtonClickPacket
- XXX.protocol.game.ServerboundContainerClickPacket
+ XXX.protocol.game.ServerboundContainerClosePacket
- XXX.protocol.game.ServerboundContainerSlotStateChangedPacket
+ XXX.protocol.game.ServerboundDebugSampleSubscriptionPacket
- XXX.protocol.game.ServerboundEditBookPacket
+ XXX.protocol.game.ServerboundEntityTagQueryPacket
- XXX.protocol.game.ServerboundInteractPacket
+ XXX.protocol.game.ServerboundInteractPacket$1
- XXX.protocol.game.ServerboundInteractPacket$Action
+ XXX.protocol.game.ServerboundInteractPacket$ActionType
- XXX.protocol.game.ServerboundInteractPacket$Handler
+ XXX.protocol.game.ServerboundInteractPacket$InteractionAction
- XXX.protocol.game.ServerboundInteractPacket$InteractionAtLocationAction
+ XXX.protocol.game.ServerboundJigsawGeneratePacket
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
- XXX.protocol.game.ServerboundRecipeBookChangeSettingsPacket
+ XXX.protocol.game.ServerboundRecipeBookSeenRecipePacket
- XXX.protocol.game.ServerboundRenameItemPacket
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
+ XXX.protocol.game.ServerPacketListener
- XXX.protocol.game.VecDeltaCodec
- XXX.protocol.handshake.ClientIntent
+ XXX.protocol.handshake.ClientIntentionPacket
- XXX.protocol.handshake.HandshakePacketTypes
+ XXX.protocol.handshake.HandshakeProtocols
+ XXX.protocol.handshake.package-info
- XXX.protocol.handshake.ServerHandshakePacketListener
+ XXX.protocol.login.ClientboundCustomQueryPacket
- XXX.protocol.login.ClientboundGameProfilePacket
+ XXX.protocol.login.ClientboundHelloPacket
- XXX.protocol.login.ClientboundLoginCompressionPacket
+ XXX.protocol.login.ClientboundLoginDisconnectPacket
- XXX.protocol.login.ClientLoginPacketListener
- XXX.protocol.login.LoginPacketTypes
+ XXX.protocol.login.LoginProtocols
- XXX.protocol.login.package-info
+ XXX.protocol.login.ServerboundCustomQueryAnswerPacket
- XXX.protocol.login.ServerboundHelloPacket
+ XXX.protocol.login.ServerboundKeyPacket
- XXX.protocol.login.ServerboundLoginAcknowledgedPacket
- XXX.protocol.login.ServerLoginPacketListener
+ XXX.protocol.ping.ClientboundPongResponsePacket
- XXX.protocol.ping.ClientPongPacketListener
+ XXX.protocol.ping.package-info
- XXX.protocol.ping.PingPacketTypes
- XXX.protocol.ping.ServerboundPingRequestPacket
+ XXX.protocol.ping.ServerPingPacketListener
+ XXX.protocol.status.ClientboundStatusResponsePacket
- XXX.protocol.status.ClientStatusPacketListener
- XXX.protocol.status.package-info
+ XXX.protocol.status.ServerboundStatusRequestPacket
- XXX.protocol.status.ServerStatus
+ XXX.protocol.status.ServerStatus$Favicon
- XXX.protocol.status.ServerStatus$Players
+ XXX.protocol.status.ServerStatus$Version
- XXX.protocol.status.ServerStatusPacketListener
- XXX.protocol.status.StatusPacketTypes
+ XXX.protocol.status.StatusProtocols
+ XXX.providers.nbt.ContextNbtProvider
- XXX.providers.nbt.ContextNbtProvider$1
+ XXX.providers.nbt.ContextNbtProvider$2
- XXX.providers.nbt.ContextNbtProvider$Getter
+ XXX.providers.nbt.LootNbtProviderType
- XXX.providers.nbt.NbtProvider
+ XXX.providers.nbt.NbtProviders
+ XXX.providers.nbt.package-info
- XXX.providers.nbt.StorageNbtProvider
- XXX.providers.number.BinomialDistributionGenerator
+ XXX.providers.number.ConstantValue
- XXX.providers.number.LootNumberProviderType
+ XXX.providers.number.NumberProvider
- XXX.providers.number.NumberProviders
- XXX.providers.number.package-info
+ XXX.providers.number.ScoreboardValue
- XXX.providers.number.StorageValue
+ XXX.providers.number.UniformGenerator
+ XXX.providers.score.ContextScoreboardNameProvider
- XXX.providers.score.FixedScoreboardNameProvider
+ XXX.providers.score.LootScoreProviderType
- XXX.providers.score.package-info
- XXX.providers.score.ScoreboardNameProvider
+ XXX.providers.score.ScoreboardNameProviders
+ XXX.rcon.thread.GenericThread
- XXX.rcon.thread.package-info
- XXX.rcon.thread.QueryThreadGs4
+ XXX.rcon.thread.QueryThreadGs4$RequestChallenge
- XXX.rcon.thread.RconClient
+ XXX.rcon.thread.RconThread
- XXX.recipes.packs.BundleRecipeProvider
- XXX.recipes.packs.package-info
+ XXX.recipes.packs.UpdateOneTwentyOneRecipeProvider
- XXX.recipes.packs.VanillaRecipeProvider
+ XXX.recipes.packs.VanillaRecipeProvider$TrimTemplate
+ XXX.scores.criteria.ObjectiveCriteria
- XXX.scores.criteria.ObjectiveCriteria$RenderType
+ XXX.scores.criteria.package-info
- XXX.server.advancements.AdvancementVisibilityEvaluator
+ XXX.server.advancements.AdvancementVisibilityEvaluator$Output
- XXX.server.advancements.AdvancementVisibilityEvaluator$VisibilityRule
+ XXX.server.advancements.package-info
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
+ XXX.server.commands.CloneCommands$CloneBlockEntityInfo
- XXX.server.commands.CloneCommands$CloneBlockInfo
+ XXX.server.commands.CloneCommands$CommandFunction
- XXX.server.commands.CloneCommands$DimensionAndPosition
+ XXX.server.commands.CloneCommands$Mode
- XXX.server.commands.DamageCommand
+ XXX.server.commands.DataPackCommand
- XXX.server.commands.DataPackCommand$Inserter
- XXX.server.commands.DebugCommand
+ XXX.server.commands.DebugCommand$TraceCustomExecutor
- XXX.server.commands.DebugCommand$TraceCustomExecutor$1
+ XXX.server.commands.DebugCommand$Tracer
- XXX.server.commands.DebugConfigCommand
+ XXX.server.commands.DebugMobSpawningCommand
- XXX.server.commands.DebugPathCommand
+ XXX.server.commands.DefaultGameModeCommands
+ XXX.server.commands.DeOpCommands
- XXX.server.commands.DifficultyCommand
+ XXX.server.commands.EffectCommands
- XXX.server.commands.EmoteCommands
+ XXX.server.commands.EnchantCommand
- XXX.server.commands.ExecuteCommand
+ XXX.server.commands.ExecuteCommand$CommandGetter
- XXX.server.commands.ExecuteCommand$CommandNumericPredicate
+ XXX.server.commands.ExecuteCommand$CommandPredicate
- XXX.server.commands.ExecuteCommand$ExecuteIfFunctionCustomModifier
+ XXX.server.commands.ExecuteCommand$IntBiPredicate
- XXX.server.commands.ExperienceCommand
+ XXX.server.commands.ExperienceCommand$Type
- XXX.server.commands.FillBiomeCommand
+ XXX.server.commands.FillCommand
- XXX.server.commands.FillCommand$Mode
+ XXX.server.commands.ForceLoadCommand
- XXX.server.commands.FunctionCommand
+ XXX.server.commands.FunctionCommand$1
- XXX.server.commands.FunctionCommand$1Accumulator
+ XXX.server.commands.FunctionCommand$2
- XXX.server.commands.FunctionCommand$3
+ XXX.server.commands.FunctionCommand$4
- XXX.server.commands.FunctionCommand$5
+ XXX.server.commands.FunctionCommand$Callbacks
- XXX.server.commands.FunctionCommand$FunctionCustomExecutor
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
+ XXX.server.commands.package-info
- XXX.server.commands.PardonCommand
+ XXX.server.commands.PardonIpCommand
- XXX.server.commands.ParticleCommand
+ XXX.server.commands.PerfCommand
- XXX.server.commands.PlaceCommand
+ XXX.server.commands.PlaySoundCommand
- XXX.server.commands.PublishCommand
+ XXX.server.commands.RaidCommand
- XXX.server.commands.RandomCommand
+ XXX.server.commands.RecipeCommand
- XXX.server.commands.ReloadCommand
+ XXX.server.commands.ResetChunksCommand
- XXX.server.commands.ReturnCommand
+ XXX.server.commands.ReturnCommand$ReturnFailCustomExecutor
- XXX.server.commands.ReturnCommand$ReturnFromCommandCustomModifier
+ XXX.server.commands.ReturnCommand$ReturnValueCustomExecutor
- XXX.server.commands.RideCommand
+ XXX.server.commands.SaveAllCommand
- XXX.server.commands.SaveOffCommand
+ XXX.server.commands.SaveOnCommand
- XXX.server.commands.SayCommand
+ XXX.server.commands.ScheduleCommand
- XXX.server.commands.ScoreboardCommand
+ XXX.server.commands.ScoreboardCommand$NumberFormatCommandExecutor
- XXX.server.commands.SeedCommand
+ XXX.server.commands.ServerPackCommand
- XXX.server.commands.SetBlockCommand
+ XXX.server.commands.SetBlockCommand$Filter
- XXX.server.commands.SetBlockCommand$Mode
+ XXX.server.commands.SetPlayerIdleTimeoutCommand
- XXX.server.commands.SetSpawnCommand
+ XXX.server.commands.SetWorldSpawnCommand
- XXX.server.commands.SpawnArmorTrimsCommand
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
- XXX.server.commands.TeleportCommand$LookAtEntity
+ XXX.server.commands.TeleportCommand$LookAtPosition
- XXX.server.commands.TellRawCommand
+ XXX.server.commands.TickCommand
- XXX.server.commands.TimeCommand
+ XXX.server.commands.TitleCommand
- XXX.server.commands.TransferCommand
+ XXX.server.commands.TriggerCommand
- XXX.server.commands.WardenSpawnTrackerCommand
+ XXX.server.commands.WeatherCommand
- XXX.server.commands.WhitelistCommand
+ XXX.server.commands.WorldBorderCommand
- XXX.server.dedicated.DedicatedPlayerList
+ XXX.server.dedicated.DedicatedServer
- XXX.server.dedicated.DedicatedServer$1
+ XXX.server.dedicated.DedicatedServerProperties
- XXX.server.dedicated.DedicatedServerProperties$WorldDimensionData
+ XXX.server.dedicated.DedicatedServerSettings
- XXX.server.dedicated.package-info
- XXX.server.dedicated.ServerWatchdog
+ XXX.server.dedicated.ServerWatchdog$1
- XXX.server.dedicated.Settings
+ XXX.server.dedicated.Settings$MutableValue
+ XXX.server.gui.MinecraftServerGui
- XXX.server.gui.MinecraftServerGui$1
+ XXX.server.gui.MinecraftServerGui$2
- XXX.server.gui.package-info
- XXX.server.gui.PlayerListComponent
+ XXX.server.gui.StatsComponent
+ XXX.server.level.BlockDestructionProgress
- XXX.server.level.ChunkHolder
+ XXX.server.level.ChunkHolder$ChunkSaveDebug
- XXX.server.level.ChunkHolder$LevelChangeListener
+ XXX.server.level.ChunkHolder$PlayerProvider
- XXX.server.level.ChunkLevel
+ XXX.server.level.ChunkLevel$1
- XXX.server.level.ChunkMap
+ XXX.server.level.ChunkMap$DistanceManager
- XXX.server.level.ChunkMap$TrackedEntity
+ XXX.server.level.ChunkResult
- XXX.server.level.ChunkResult$Fail
+ XXX.server.level.ChunkResult$Success
- XXX.server.level.ChunkTaskPriorityQueue
+ XXX.server.level.ChunkTaskPriorityQueueSorter
- XXX.server.level.ChunkTaskPriorityQueueSorter$Message
+ XXX.server.level.ChunkTaskPriorityQueueSorter$Release
- XXX.server.level.ChunkTracker
+ XXX.server.level.ChunkTrackingView
- XXX.server.level.ChunkTrackingView$1
+ XXX.server.level.ChunkTrackingView$Positioned
- XXX.server.level.ClientInformation
+ XXX.server.level.ColumnPos
- XXX.server.level.DemoMode
+ XXX.server.level.DistanceManager
- XXX.server.level.DistanceManager$ChunkTicketTracker
+ XXX.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
- XXX.server.level.DistanceManager$PlayerTicketTracker
+ XXX.server.level.FullChunkStatus
- XXX.server.level.package-info
- XXX.server.level.PlayerMap
+ XXX.server.level.PlayerRespawnLogic
- XXX.server.level.SectionTracker
+ XXX.server.level.ServerBossEvent
- XXX.server.level.ServerChunkCache
+ XXX.server.level.ServerChunkCache$ChunkAndHolder
- XXX.server.level.ServerChunkCache$MainThreadExecutor
+ XXX.server.level.ServerEntity
- XXX.server.level.ServerLevel
+ XXX.server.level.ServerLevel$EntityCallbacks
- XXX.server.level.ServerPlayer
+ XXX.server.level.ServerPlayer$1
- XXX.server.level.ServerPlayer$2
+ XXX.server.level.ServerPlayerGameMode
- XXX.server.level.ThreadedLevelLightEngine
+ XXX.server.level.ThreadedLevelLightEngine$TaskType
- XXX.server.level.Ticket
+ XXX.server.level.TicketType
- XXX.server.level.TickingTracker
+ XXX.server.level.WorldGenRegion
+ XXX.server.network.CommonListenerCookie
- XXX.server.network.ConfigurationTask
+ XXX.server.network.ConfigurationTask$Type
- XXX.server.network.Filterable
+ XXX.server.network.FilteredText
- XXX.server.network.LegacyProtocolUtils
+ XXX.server.network.LegacyQueryHandler
- XXX.server.network.MemoryServerHandshakePacketListenerImpl
- XXX.server.network.package-info
+ XXX.server.network.PlayerChunkSender
- XXX.server.network.ServerCommonPacketListenerImpl
+ XXX.server.network.ServerConfigurationPacketListenerImpl
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
- XXX.server.network.TextFilterClient
+ XXX.server.network.TextFilterClient$IgnoreStrategy
- XXX.server.network.TextFilterClient$JoinOrLeaveEncoder
+ XXX.server.network.TextFilterClient$MessageEncoder
- XXX.server.network.TextFilterClient$PlayerContext
+ XXX.server.network.TextFilterClient$RequestFailedException
- XXX.server.packs.AbstractPackResources
+ XXX.server.packs.BuiltInMetadata
- XXX.server.packs.CompositePackResources
+ XXX.server.packs.DownloadCacheCleaner
- XXX.server.packs.DownloadCacheCleaner$1
+ XXX.server.packs.DownloadCacheCleaner$PathAndPriority
- XXX.server.packs.DownloadCacheCleaner$PathAndTime
+ XXX.server.packs.DownloadQueue
- XXX.server.packs.DownloadQueue$BatchConfig
+ XXX.server.packs.DownloadQueue$BatchResult
- XXX.server.packs.DownloadQueue$DownloadRequest
+ XXX.server.packs.DownloadQueue$FileInfoEntry
- XXX.server.packs.DownloadQueue$LogEntry
+ XXX.server.packs.FeatureFlagsMetadataSection
- XXX.server.packs.FilePackResources
+ XXX.server.packs.FilePackResources$FileResourcesSupplier
- XXX.server.packs.FilePackResources$SharedZipFileAccess
+ XXX.server.packs.OverlayMetadataSection
- XXX.server.packs.OverlayMetadataSection$OverlayEntry
- XXX.server.packs.package-info
+ XXX.server.packs.PackLocationInfo
- XXX.server.packs.PackResources
+ XXX.server.packs.PackResources$ResourceOutput
- XXX.server.packs.PackSelectionConfig
+ XXX.server.packs.PackType
- XXX.server.packs.PathPackResources
+ XXX.server.packs.PathPackResources$PathResourcesSupplier
- XXX.server.packs.VanillaPackResources
+ XXX.server.packs.VanillaPackResourcesBuilder
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
- XXX.storage.loot.ContainerComponentManipulator
- XXX.storage.loot.ContainerComponentManipulators$1
- XXX.storage.loot.ContainerComponentManipulators$3
+ XXX.storage.loot.IntRange
- XXX.storage.loot.IntRange$IntChecker
+ XXX.storage.loot.IntRange$IntLimiter
- XXX.storage.loot.LootContext
+ XXX.storage.loot.LootContext$Builder
- XXX.storage.loot.LootContext$EntityTarget
+ XXX.storage.loot.LootContext$VisitedEntry
- XXX.storage.loot.LootContextUser
+ XXX.storage.loot.LootDataType
- XXX.storage.loot.LootDataType$Validator
+ XXX.storage.loot.LootParams
- XXX.storage.loot.LootParams$Builder
+ XXX.storage.loot.LootParams$DynamicDrop
- XXX.storage.loot.LootPool
+ XXX.storage.loot.LootPool$Builder
- XXX.storage.loot.LootTable
+ XXX.storage.loot.LootTable$Builder
- XXX.storage.loot.package-info
- XXX.storage.loot.ValidationContext
- XXX.util.debugchart.AbstractSampleLogger
+ XXX.util.debugchart.DebugSampleSubscriptionTracker
- XXX.util.debugchart.DebugSampleSubscriptionTracker$SubscriptionRequest
+ XXX.util.debugchart.DebugSampleSubscriptionTracker$SubscriptionStartedAt
- XXX.util.debugchart.LocalSampleLogger
+ XXX.util.debugchart.RemoteDebugSampleType
- XXX.util.debugchart.RemoteSampleLogger
+ XXX.util.debugchart.SampleLogger
- XXX.util.debugchart.SampleStorage
+ XXX.util.debugchart.TpsDebugDimensions
- XXX.util.eventlog.EventLogDirectory
+ XXX.util.eventlog.EventLogDirectory$CompressedFile
- XXX.util.eventlog.EventLogDirectory$File
+ XXX.util.eventlog.EventLogDirectory$FileId
- XXX.util.eventlog.EventLogDirectory$FileList
+ XXX.util.eventlog.EventLogDirectory$RawFile
- XXX.util.eventlog.JsonEventLog
+ XXX.util.eventlog.JsonEventLog$1
- XXX.util.eventlog.JsonEventLogReader
+ XXX.util.eventlog.JsonEventLogReader$1
- XXX.util.eventlog.package-info
+ XXX.util.parsing.package-info
- XXX.util.profiling.ActiveProfiler
+ XXX.util.profiling.ActiveProfiler$PathEntry
- XXX.util.profiling.ContinuousProfiler
+ XXX.util.profiling.EmptyProfileResults
- XXX.util.profiling.FilledProfileResults
+ XXX.util.profiling.FilledProfileResults$1
- XXX.util.profiling.FilledProfileResults$CounterCollector
+ XXX.util.profiling.InactiveProfiler
- XXX.util.profiling.package-info
- XXX.util.profiling.ProfileCollector
+ XXX.util.profiling.ProfileResults
- XXX.util.profiling.ProfilerFiller
+ XXX.util.profiling.ProfilerFiller$1
- XXX.util.profiling.ProfilerPathEntry
+ XXX.util.profiling.ResultField
- XXX.util.profiling.SingleTickProfiler
+ XXX.util.random.package-info
+ XXX.util.random.SimpleWeightedRandomList
- XXX.util.random.SimpleWeightedRandomList$Builder
+ XXX.util.random.Weight
- XXX.util.random.WeightedEntry
+ XXX.util.random.WeightedEntry$IntrusiveBase
- XXX.util.random.WeightedEntry$Wrapper
+ XXX.util.random.WeightedRandom
- XXX.util.random.WeightedRandomList
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
+ XXX.util.valueproviders.BiasedToBottomInt
- XXX.util.valueproviders.ClampedInt
+ XXX.util.valueproviders.ClampedNormalFloat
- XXX.util.valueproviders.ClampedNormalInt
+ XXX.util.valueproviders.ConstantFloat
- XXX.util.valueproviders.ConstantInt
+ XXX.util.valueproviders.FloatProvider
- XXX.util.valueproviders.FloatProviderType
+ XXX.util.valueproviders.IntProvider
- XXX.util.valueproviders.IntProviderType
+ XXX.util.valueproviders.MultipliedFloats
+ XXX.util.valueproviders.package-info
- XXX.util.valueproviders.SampledFloat
+ XXX.util.valueproviders.TrapezoidFloat
- XXX.util.valueproviders.UniformFloat
+ XXX.util.valueproviders.UniformInt
- XXX.util.valueproviders.WeightedListInt
- XXX.util.worldupdate.package-info
- XXX.util.worldupdate.WorldUpgrader
+ XXX.util.worldupdate.WorldUpgrader$AbstractUpgrader
- XXX.util.worldupdate.WorldUpgrader$ChunkUpgrader
+ XXX.util.worldupdate.WorldUpgrader$DimensionToUpgrade
- XXX.util.worldupdate.WorldUpgrader$EntityUpgrader
+ XXX.util.worldupdate.WorldUpgrader$FileToUpgrade
- XXX.util.worldupdate.WorldUpgrader$PoiUpgrader
+ XXX.util.worldupdate.WorldUpgrader$SimpleRegionStorageUpgrader
- XXX.world.damagesource.CombatEntry
+ XXX.world.damagesource.CombatRules
- XXX.world.damagesource.CombatTracker
+ XXX.world.damagesource.DamageEffects
- XXX.world.damagesource.DamageScaling
+ XXX.world.damagesource.DamageSource
- XXX.world.damagesource.DamageSource$1
+ XXX.world.damagesource.DamageSources
- XXX.world.damagesource.DamageType
+ XXX.world.damagesource.DamageTypes
- XXX.world.damagesource.DeathMessageType
+ XXX.world.damagesource.FallLocation
- XXX.world.damagesource.package-info
+ XXX.world.effect.AbsorptionMobEffect
- XXX.world.effect.BadOmenMobEffect
+ XXX.world.effect.HealOrHarmMobEffect
- XXX.world.effect.HungerMobEffect
+ XXX.world.effect.InfestedMobEffect
- XXX.world.effect.InstantenousMobEffect
+ XXX.world.effect.MobEffect
- XXX.world.effect.MobEffect$AttributeTemplate
+ XXX.world.effect.MobEffectCategory
- XXX.world.effect.MobEffectInstance
+ XXX.world.effect.MobEffectInstance$BlendState
- XXX.world.effect.MobEffectInstance$Details
- XXX.world.effect.MobEffects
+ XXX.world.effect.MobEffectUtil
+ XXX.world.effect.OozingMobEffect
+ XXX.world.effect.package-info
- XXX.world.effect.PoisonMobEffect
+ XXX.world.effect.RaidOmenMobEffect
- XXX.world.effect.RegenerationMobEffect
+ XXX.world.effect.SaturationMobEffect
- XXX.world.effect.WeavingMobEffect
+ XXX.world.effect.WindChargedMobEffect
- XXX.world.effect.WitherMobEffect
- XXX.world.entity.AgeableMob
+ XXX.world.entity.AgeableMob$AgeableMobGroupData
- XXX.world.entity.AnimationState
+ XXX.world.entity.AreaEffectCloud
- XXX.world.entity.Attackable
+ XXX.world.entity.Crackiness
- XXX.world.entity.Crackiness$Level
+ XXX.world.entity.Display
- XXX.world.entity.Display$BillboardConstraints
+ XXX.world.entity.Display$BlockDisplay
- XXX.world.entity.Display$BlockDisplay$BlockRenderState
+ XXX.world.entity.Display$ColorInterpolator
- XXX.world.entity.Display$FloatInterpolator
+ XXX.world.entity.Display$GenericInterpolator
- XXX.world.entity.Display$IntInterpolator
+ XXX.world.entity.Display$ItemDisplay
- XXX.world.entity.EquipmentUser
+ XXX.world.entity.ExperienceOrb
- XXX.world.entity.FlyingMob
+ XXX.world.entity.GlowSquid
- XXX.world.entity.HasCustomInventoryScreen
+ XXX.world.entity.HumanoidArm
- XXX.world.entity.Interaction
+ XXX.world.entity.Interaction$PlayerAction
- XXX.world.entity.ItemBasedSteering
+ XXX.world.entity.ItemSteerable
- XXX.world.entity.LerpingModel
+ XXX.world.entity.LightningBolt
- XXX.world.entity.LivingEntity
+ XXX.world.entity.LivingEntity$1
- XXX.world.entity.LivingEntity$Fallsounds
+ XXX.world.entity.Marker
- XXX.world.entity.Mob
+ XXX.world.entity.Mob$1
- XXX.world.entity.MobCategory
+ XXX.world.entity.MobSpawnType
- XXX.world.entity.MoverType
+ XXX.world.entity.NeutralMob
- XXX.world.entity.OminousItemSpawner
+ XXX.world.entity.OwnableEntity
- XXX.world.entity.PathfinderMob
+ XXX.world.entity.PlayerRideable
- XXX.world.entity.PlayerRideableJumping
+ XXX.world.entity.Pose
- XXX.world.entity.PowerableMob
+ XXX.world.entity.RelativeMovement
- XXX.world.entity.ReputationEventHandler
+ XXX.world.entity.Saddleable
- XXX.world.entity.Shearable
+ XXX.world.entity.SlotAccess
- XXX.world.entity.SlotAccess$1
+ XXX.world.entity.SlotAccess$2
- XXX.world.entity.SlotAccess$3
+ XXX.world.item.Items
- XXX.world.item.ItemStackLinkedSet
+ XXX.world.item.ItemStackLinkedSet$1
- XXX.world.item.ItemUtils
- XXX.world.item.KnowledgeBookItem
+ XXX.world.item.LeadItem
- XXX.world.item.LingeringPotionItem
+ XXX.world.item.MaceItem
- XXX.world.item.MapItem
+ XXX.world.item.MapItem$1
- XXX.world.item.MilkBucketItem
+ XXX.world.item.MinecartItem
- XXX.world.item.MinecartItem$1
+ XXX.world.item.MobBucketItem
- XXX.world.item.NameTagItem
+ XXX.world.item.OminousBottleItem
- XXX.world.item.PickaxeItem
+ XXX.world.item.PlaceOnWaterBlockItem
- XXX.world.item.PlayerHeadItem
+ XXX.world.item.PotionItem
- XXX.world.item.ProjectileItem
+ XXX.world.item.ProjectileItem$DispenseConfig
- XXX.world.item.ProjectileItem$DispenseConfig$Builder
+ XXX.world.item.ProjectileItem$PositionFunction
- XXX.world.item.ProjectileWeaponItem
+ XXX.world.item.Rarity
- XXX.world.item.RecordItem
+ XXX.world.item.SaddleItem
- XXX.world.item.ScaffoldingBlockItem
+ XXX.world.item.ServerItemCooldowns
- XXX.world.item.ShearsItem
+ XXX.world.item.ShieldItem
- XXX.world.item.ShovelItem
+ XXX.world.item.SignApplicator
- XXX.world.item.SignItem
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
- XXX.world.item.WindChargeItem
+ XXX.world.item.WritableBookItem
- XXX.world.item.WrittenBookItem
+ XXX.world.phys.AABB
- XXX.world.phys.BlockHitResult
+ XXX.world.phys.EntityHitResult
- XXX.world.phys.HitResult
+ XXX.world.phys.HitResult$Type
- XXX.world.phys.package-info
- XXX.world.phys.Vec2
+ XXX.world.phys.Vec3
- XXX.world.scores.DisplaySlot
+ XXX.world.scores.DisplaySlot$1
- XXX.world.scores.Objective
- XXX.world.scores.package-info
+ XXX.world.scores.PlayerScoreEntry
- XXX.world.scores.PlayerScores
+ XXX.world.scores.PlayerTeam
- XXX.world.scores.ReadOnlyScoreInfo
+ XXX.world.scores.Score
- XXX.world.scores.ScoreAccess
+ XXX.world.scores.Scoreboard
- XXX.world.scores.Scoreboard$1
+ XXX.world.scores.ScoreboardSaveData
+ XXX.world.scores.ScoreHolder
- XXX.world.scores.ScoreHolder$1
+ XXX.world.scores.ScoreHolder$2
- XXX.world.scores.ScoreHolder$3
- XXX.world.scores.Team
+ XXX.world.scores.Team$CollisionRule
- XXX.world.scores.Team$Visibility
+ XXX.world.ticks.BlackholeTickAccess
- XXX.world.ticks.BlackholeTickAccess$1
+ XXX.world.ticks.BlackholeTickAccess$2
- XXX.world.ticks.ContainerSingleItem
+ XXX.world.ticks.ContainerSingleItem$BlockContainerSingleItem
- XXX.world.ticks.LevelChunkTicks
+ XXX.world.ticks.LevelTickAccess
- XXX.world.ticks.LevelTicks
+ XXX.world.ticks.LevelTicks$PosAndContainerConsumer
- XXX.world.ticks.package-info
- XXX.world.ticks.ProtoChunkTicks
+ XXX.world.ticks.SavedTick
- XXX.world.ticks.SavedTick$1
+ XXX.world.ticks.ScheduledTick
- XXX.world.ticks.ScheduledTick$1
+ XXX.world.ticks.SerializableTickContainer
- XXX.world.ticks.TickAccess
+ XXX.world.ticks.TickContainerAccess
- XXX.world.ticks.TickPriority
+ XXX.world.ticks.WorldGenTickAccess
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.advancements.critereon.EntityEquipmentPredicate$Builder +1M | +1P
```
```
XXX.advancements.critereon.EntitySubPredicates +1M
```
```
XXX.gui.screens.TitleScreen +1M
```
```
XXX.client.multiplayer.ClientCommonPacketListenerImpl +3M -2M
```
```
XXX.client.particle.SpellParticle +1M | +1P
```
```
XXX.commands.arguments.ParticleArgument +2M -1M | +1P
```
```
XXX.arguments.item.ItemParser +3M | +1P
```
```
XXX.core.component.DataComponentMap +1M
```
```
XXX.core.component.DataComponentMap$2 +1M -1M | +2P -2P
```
```
XXX.core.particles.ColorParticleOption -3M | -1P
```
```
XXX.core.particles.DustParticleOptions -1P
```
```
XXX.core.particles.ParticleOptions -1P
```
```
XXX.gametest.framework.StructureUtils +7M -5M | +1P
```
```
XXX.gametest.framework.TestCommand$Runner +4M
```
```
XXX.gametest.framework.TestFinder$Builder +3M -1M
```
```
XXX.minecraft.nbt.TagParser +1P
```
```
XXX.network.codec.ByteBufCodecs$11 +3M -3M | -1P
```
```
XXX.network.codec.ByteBufCodecs$13 +3M -5M | +1P -2P
```
```
XXX.network.codec.ByteBufCodecs$15 +2M -2M
```
```
XXX.network.codec.ByteBufCodecs$17 +3M -3M | -1P
```
```
XXX.network.codec.ByteBufCodecs$19 +3M -4M | +1P -2P
```
```
XXX.network.codec.ByteBufCodecs$20 +4M -5M | +4P -2P
```
```
XXX.network.codec.ByteBufCodecs$22 +3M -4M | +2P -2P
```
```
XXX.network.codec.ByteBufCodecs$24 +4M -3M | +2P -2P
```
```
XXX.network.codec.ByteBufCodecs$26 +4M -2M | +4P
```
```
XXX.minecraft.tags.EntityTypeTags +1P
```
```
XXX.minecraft.util.ExtraCodecs +76M -72M | +2P
```
```
XXX.minecraft.util.FastColor +1M
```
```
XXX.minecraft.util.FastColor$ARGB32 +1M
```
```
XXX.datafix.fixes.References +2P
```
```
XXX.datafix.schemas.V100 +2M -1M
```
```
XXX.datafix.schemas.V1928 -1M
```
```
XXX.world.entity.Entity +5M -2M
```
```
XXX.animal.axolotl.Axolotl +1M
```
```
XXX.entity.monster.Zoglin +1M
```
```
XXX.monster.breeze.Breeze +1M
```
```
XXX.monster.hoglin.Hoglin +1M
```
```
XXX.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds +1M -1M
```
```
XXX.entity.projectile.AbstractArrow +2M
```
```
XXX.entity.projectile.AbstractHurtingProjectile +1M -3M
```
```
XXX.entity.projectile.DragonFireball -1M
```
```
XXX.world.food.FoodData +1M
```
```
XXX.world.inventory.BrewingStandMenu$IngredientsSlot +1M -2M | +1P
```
```
XXX.world.item.ItemStack$3 +5M -1M | +1P -1P
```
```
XXX.item.armortrim.ArmorTrim +1M -1M
```
```
XXX.item.component.BundleContents$Mutable +1M
```
```
XXX.item.component.FireworkExplosion +1M -1M
```
```
XXX.item.component.Fireworks +1M -1M
```
```
XXX.item.component.Unbreakable +1M -1M
```
```
XXX.item.component.WrittenBookContent -1P
```
```
XXX.item.enchantment.ItemEnchantments$Mutable +1P -1P
```
```
XXX.item.enchantment.WindBurstEnchantment$WindBurstEnchantmentDamageCalculator +1M -1M
```
```
XXX.world.level.Level +1P
```
```
XXX.world.level.SpawnData +2M -2M | +1P -1P
```
```
XXX.level.block.DispenserBlock +1M -1M | +1P
```
```
XXX.level.block.DropperBlock +1M -1M
```
```
XXX.block.entity.BrewingStandBlockEntity +1M -1M
```
```
XXX.level.levelgen.Beardifier +1M -1M
```
```
XXX.loot.functions.ListOperation +2M | +1P
```
```
XXX.loot.functions.LootItemConditionalFunction +1P
```
```
XXX.loot.functions.LootItemFunctions +4P
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.EntityEquipmentPredicate$Builder
</summary>

```diff
- EntityEquipmentPredicate$Builder body(ItemPredicate$Builder)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.EntitySubPredicates
</summary>

```diff
- EntitySubPredicate wolfVariant(HolderSet)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.TitleScreen
</summary>

```diff
- void fadeWidgets(float)
```

</details>
<details>
<summary>
net.minecraft.client.multiplayer.ClientCommonPacketListenerImpl
</summary>

```diff
+ Screen lambda$createDisconnectScreen$5()
- Screen lambda$createDisconnectScreen$6()
+ String lambda$fillListenerSpecificCrashDetails$3()
- String lambda$fillListenerSpecificCrashDetails$5()
- void lambda$handleTransfer$3(ClientboundTransferPacket)
```

</details>
<details>
<summary>
net.minecraft.client.particle.SpellParticle
</summary>

```diff
- void setAlpha(float)
```

</details>
<details>
<summary>
net.minecraft.commands.arguments.ParticleArgument
</summary>

```diff
+ CommandSyntaxException lambda$readParticleType$1(StringReader,ResourceLocation)
- CommandSyntaxException lambda$readParticleType$2(StringReader,ResourceLocation)
- Message lambda$static$1(Object)
```

</details>
<details>
<summary>
net.minecraft.commands.arguments.item.ItemParser
</summary>

```diff
- CommandSyntaxException lambda$validateComponents$5(StringReader,String)
- Message lambda$static$4(Object)
- void validateComponents(StringReader,Holder,DataComponentMap)
```

</details>
<details>
<summary>
net.minecraft.core.component.DataComponentMap
</summary>

```diff
- DataComponentMap composite(DataComponentMap,DataComponentMap)
```

</details>
<details>
<summary>
net.minecraft.core.component.DataComponentMap$2
</summary>

```diff
- void <init>(DataComponentMap,DataComponentMap)
+ void <init>(DataComponentMap,Predicate)
```

</details>
<details>
<summary>
net.minecraft.core.particles.ColorParticleOption
</summary>

```diff
+ int as32BitChannel(float)
+ String writeToString(HolderLookup$Provider)
+ void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.gametest.framework.StructureUtils
</summary>

```diff
- boolean lambda$findStructureBlocks$10(ServerLevel,BlockPos)
+ boolean lambda$findStructureBlocks$8(ServerLevel,BlockPos)
- boolean lambda$findStructureByTestFunction$9(String,StructureBlockEntity)
+ boolean lambda$lookedAtStructureBlockPos$11(Vec3,Vec3,StructureBlockEntity)
- boolean lambda$lookedAtStructureBlockPos$12(Vec3,Vec3,StructureBlockEntity)
+ boolean lambda$radiusStructureBlockPos$9(ServerLevel,BlockPos)
- BoundingBox getBoundingBoxAtGround(BlockPos,int,ServerLevel)
+ Optional lambda$lookedAtStructureBlockPos$10(ServerLevel,BlockPos)
- Optional lambda$lookedAtStructureBlockPos$11(ServerLevel,BlockPos)
- Stream findStructureByTestFunction(BlockPos,int,ServerLevel,String)
+ Stream radiusStructureBlockPos(int,Vec3,ServerLevel)
- StructureBlockEntity lambda$findStructureByTestFunction$8(ServerLevel,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.gametest.framework.TestCommand$Runner
</summary>

```diff
- Component lambda$locate$7(Component)
- int locate()
- Style lambda$locate$6(String,Style)
- void lambda$locate$8(BlockPos,MutableInt,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.gametest.framework.TestFinder$Builder
</summary>

```diff
- Object locateByName(CommandContext,String)
- Stream lambda$locateByName$14(BlockPos,CommandSourceStack,String)
- Stream lambda$radius$3(BlockPos,int,CommandSourceStack)
+ Stream lambda$radius$3(int,CommandSourceStack)
```

</details>
<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$11
</summary>

```diff
- byte[] decode(ByteBuf)
+ String decode(ByteBuf)
- void <init>()
+ void <init>(int)
- void encode(ByteBuf,byte[])
+ void encode(ByteBuf,String)
```

</details>
<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$13
</summary>

```diff
+ DecoderException lambda$decode$0(Tag,String)
+ EncoderException lambda$encode$1(Object,String)
+ Object decode(RegistryFriendlyByteBuf)
- Tag decode(ByteBuf)
+ void <init>(StreamCodec,Codec)
- void <init>(Supplier)
- void encode(ByteBuf,Tag)
+ void encode(RegistryFriendlyByteBuf,Object)
```

</details>
<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$15
</summary>

```diff
- Optional decode(ByteBuf)
+ Vector3f decode(ByteBuf)
- void encode(ByteBuf,Optional)
+ void encode(ByteBuf,Vector3f)
```

</details>
<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$17
</summary>

```diff
+ Optional decode(ByteBuf)
- Quaternionf decode(ByteBuf)
- void <init>()
+ void <init>(StreamCodec)
+ void encode(ByteBuf,Optional)
- void encode(ByteBuf,Quaternionf)
```

</details>
<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$19
</summary>

```diff
- Collection decode(ByteBuf)
+ Map decode(ByteBuf)
- void <init>(int,IntFunction,StreamCodec)
+ void <init>(int,StreamCodec,StreamCodec,IntFunction)
- void encode(ByteBuf,Collection)
+ void encode(ByteBuf,Map)
+ void lambda$encode$0(StreamCodec,ByteBuf,StreamCodec,Object,Object)
```

</details>
<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$20
</summary>

```diff
+ Either decode(ByteBuf)
- Map decode(ByteBuf)
- void <init>(int,StreamCodec,StreamCodec,IntFunction)
+ void <init>(StreamCodec,StreamCodec)
+ void encode(ByteBuf,Either)
- void encode(ByteBuf,Map)
+ void lambda$encode$0(ByteBuf,StreamCodec,Object)
- void lambda$encode$0(StreamCodec,ByteBuf,StreamCodec,Object,Object)
+ void lambda$encode$1(ByteBuf,StreamCodec,Object)
```

</details>
<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$22
</summary>

```diff
+ IdMap getRegistryOrThrow(RegistryFriendlyByteBuf)
- Object decode(ByteBuf)
+ Object decode(RegistryFriendlyByteBuf)
+ void <init>(Function,ResourceKey)
- void <init>(IntFunction,ToIntFunction)
- void encode(ByteBuf,Object)
+ void encode(RegistryFriendlyByteBuf,Object)
```

</details>
<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$24
</summary>

```diff
- Holder decode(RegistryFriendlyByteBuf)
+ HolderSet decode(RegistryFriendlyByteBuf)
- IdMap getRegistryOrThrow(RegistryFriendlyByteBuf)
- void <init>(ResourceKey,StreamCodec)
+ void <init>(ResourceKey)
- void encode(RegistryFriendlyByteBuf,Holder)
+ void encode(RegistryFriendlyByteBuf,HolderSet)
```

</details>
<details>
<summary>
net.minecraft.network.codec.ByteBufCodecs$26
</summary>

```diff
+ GameProfile decode(ByteBuf)
- PropertyMap decode(ByteBuf)
- String lambda$decode$0(ByteBuf)
+ void encode(ByteBuf,GameProfile)
- void encode(ByteBuf,PropertyMap)
- void lambda$encode$1(ByteBuf,String)
```

</details>
<details>
<summary>
net.minecraft.util.ExtraCodecs
</summary>

```diff
+ App lambda$intervalCodec$19(Codec,String,String,RecordCodecBuilder$Instance)
- App lambda$intervalCodec$23(Codec,String,String,RecordCodecBuilder$Instance)
+ App lambda$static$10(RecordCodecBuilder$Instance)
- App lambda$static$13(RecordCodecBuilder$Instance)
+ App lambda$static$60(RecordCodecBuilder$Instance)
- App lambda$static$64(RecordCodecBuilder$Instance)
+ App lambda$static$68(RecordCodecBuilder$Instance)
+ App lambda$static$71(RecordCodecBuilder$Instance)
- App lambda$static$72(RecordCodecBuilder$Instance)
- App lambda$static$75(RecordCodecBuilder$Instance)
+ BitSet lambda$static$56(LongStream)
- BitSet lambda$static$60(LongStream)
+ DataResult lambda$ensureHomogenous$43(Function,Collection)
- DataResult lambda$ensureHomogenous$47(Function,Collection)
+ DataResult lambda$floatRangeMinExclusiveWithMessage$36(float,float,Function,Float)
- DataResult lambda$floatRangeMinExclusiveWithMessage$40(float,float,Function,Float)
+ DataResult lambda$idResolverCodec$26(Integer)
+ DataResult lambda$idResolverCodec$27(IntFunction,Integer)
+ DataResult lambda$idResolverCodec$29(ToIntFunction,int,Object)
- DataResult lambda$idResolverCodec$30(Integer)
- DataResult lambda$idResolverCodec$31(IntFunction,Integer)
- DataResult lambda$idResolverCodec$33(ToIntFunction,int,Object)
+ DataResult lambda$intervalCodec$16(BiFunction,List)
+ DataResult lambda$intervalCodec$17(BiFunction,List)
- DataResult lambda$intervalCodec$20(BiFunction,List)
+ DataResult lambda$intervalCodec$20(BiFunction,Pair)
- DataResult lambda$intervalCodec$21(BiFunction,List)
+ DataResult lambda$intervalCodec$22(BiFunction,Object)
+ DataResult lambda$intervalCodec$23(BiFunction,Either)
- DataResult lambda$intervalCodec$24(BiFunction,Pair)
- DataResult lambda$intervalCodec$26(BiFunction,Object)
- DataResult lambda$intervalCodec$27(BiFunction,Either)
+ DataResult lambda$intRangeWithMessage$31(int,int,Function,Integer)
- DataResult lambda$intRangeWithMessage$35(int,int,Function,Integer)
+ DataResult lambda$nonEmptyHolderSet$41(HolderSet)
- DataResult lambda$nonEmptyHolderSet$45(HolderSet)
+ DataResult lambda$nonEmptyList$39(List)
- DataResult lambda$nonEmptyList$43(List)
+ DataResult lambda$sizeLimitedMap$77(int,Map)
- DataResult lambda$sizeLimitedMap$81(int,Map)
+ DataResult lambda$static$12(List)
+ DataResult lambda$static$15(Integer)
- DataResult lambda$static$15(List)
- DataResult lambda$static$19(Integer)
+ DataResult lambda$static$45(String)
+ DataResult lambda$static$48(String)
- DataResult lambda$static$49(String)
+ DataResult lambda$static$50(String)
- DataResult lambda$static$52(String)
+ DataResult lambda$static$53(String)
- DataResult lambda$static$54(String)
- DataResult lambda$static$57(String)
+ DataResult lambda$static$67(String)
- DataResult lambda$static$71(String)
+ DataResult lambda$static$73(String)
+ DataResult lambda$static$75(String)
- DataResult lambda$static$77(String)
- DataResult lambda$static$83(String)
- DataResult lambda$static$9(List)
+ DataResult lambda$temporalCodec$46(DateTimeFormatter,String)
- DataResult lambda$temporalCodec$50(DateTimeFormatter,String)
+ Either lambda$intervalCodec$24(Function,Function,Object)
- Either lambda$intervalCodec$28(Function,Function,Object)
+ Either lambda$static$65(PropertyMap)
- Either lambda$static$69(PropertyMap)
+ ExtraCodecs$TagOrElementLocation lambda$static$51(ResourceLocation)
+ ExtraCodecs$TagOrElementLocation lambda$static$52(ResourceLocation)
- ExtraCodecs$TagOrElementLocation lambda$static$55(ResourceLocation)
- ExtraCodecs$TagOrElementLocation lambda$static$56(ResourceLocation)
- Float lambda$static$11(AxisAngle4f)
+ Float lambda$static$8(AxisAngle4f)
+ GameProfile lambda$static$70(GameProfile,PropertyMap)
- GameProfile lambda$static$74(GameProfile,PropertyMap)
- Integer lambda$static$17(Vector4f)
+ List lambda$intervalCodec$18(Function,Function,Object)
- List lambda$intervalCodec$22(Function,Function,Object)
- List lambda$static$10(Quaternionf)
+ List lambda$static$13(Matrix4f)
- List lambda$static$16(Matrix4f)
+ List lambda$static$7(Quaternionf)
- List lambda$static$7(Vector4f)
+ LongStream lambda$static$57(BitSet)
- LongStream lambda$static$61(BitSet)
+ Matrix4f lambda$static$11(List)
- Matrix4f lambda$static$14(List)
+ Optional lambda$static$55(OptionalLong)
+ Optional lambda$static$58(Property)
- Optional lambda$static$59(OptionalLong)
- Optional lambda$static$62(Property)
+ OptionalLong lambda$static$54(Optional)
- OptionalLong lambda$static$58(Optional)
+ Pair lambda$intervalCodec$21(Function,Function,Object)
- Pair lambda$intervalCodec$25(Function,Function,Object)
+ Property lambda$static$59(String,String,Optional)
- Property lambda$static$63(String,String,Optional)
+ PropertyMap lambda$static$64(Either)
- PropertyMap lambda$static$68(Either)
+ Quaternionf lambda$static$5(List)
- Quaternionf lambda$static$8(List)
+ String lambda$ensureHomogenous$42(Object,Object,Object)
- String lambda$ensureHomogenous$46(Object,Object,Object)
+ String lambda$floatRangeMinExclusiveWithMessage$35(Function,Float)
- String lambda$floatRangeMinExclusiveWithMessage$39(Function,Float)
+ String lambda$idResolverCodec$25(Integer)
+ String lambda$idResolverCodec$28(Object)
- String lambda$idResolverCodec$29(Integer)
- String lambda$idResolverCodec$32(Object)
+ String lambda$intRange$34(int,int,Integer)
- String lambda$intRange$38(int,int,Integer)
+ String lambda$intRangeWithMessage$30(Function,Integer)
- String lambda$intRangeWithMessage$34(Function,Integer)
+ String lambda$nonEmptyHolderSet$40()
- String lambda$nonEmptyHolderSet$44()
+ String lambda$nonEmptyList$38()
- String lambda$nonEmptyList$42()
+ String lambda$sizeLimitedMap$76(Map,int)
- String lambda$sizeLimitedMap$80(Map,int)
+ String lambda$static$14(Integer)
- String lambda$static$18(Integer)
+ String lambda$static$32(Integer)
+ String lambda$static$33(Integer)
- String lambda$static$36(Integer)
+ String lambda$static$37(Float)
- String lambda$static$37(Integer)
- String lambda$static$41(Float)
+ String lambda$static$44(String,PatternSyntaxException)
+ String lambda$static$47()
- String lambda$static$48(String,PatternSyntaxException)
+ String lambda$static$49(byte[])
- String lambda$static$51()
- String lambda$static$53(byte[])
+ String lambda$static$66(String)
- String lambda$static$70(String)
+ String lambda$static$72()
+ String lambda$static$74(String)
- String lambda$static$76()
- String lambda$static$82(String)
- Vector3f lambda$static$12(AxisAngle4f)
+ Vector3f lambda$static$9(AxisAngle4f)
- Vector4f lambda$static$5(List)
+ void lambda$static$61(PropertyMap,String,List)
+ void lambda$static$62(PropertyMap,Map)
+ void lambda$static$63(PropertyMap,List)
- void lambda$static$65(PropertyMap,String,List)
- void lambda$static$66(PropertyMap,Map)
- void lambda$static$67(PropertyMap,List)
+ void lambda$static$69(GameProfile,String,Property)
- void lambda$static$73(GameProfile,String,Property)
```

</details>
<details>
<summary>
net.minecraft.util.FastColor
</summary>

```diff
- int as8BitChannel(float)
```

</details>
<details>
<summary>
net.minecraft.util.FastColor$ARGB32
</summary>

```diff
- int colorFromFloat(float,float,float,float)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.schemas.V100
</summary>

```diff
- TypeTemplate lambda$registerEntities$4(Schema,String)
+ TypeTemplate lambda$registerTypes$4(Schema)
- TypeTemplate lambda$registerTypes$5(Schema)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.schemas.V1928
</summary>

```diff
+ TypeTemplate equipment(Schema)
```

</details>
<details>
<summary>
net.minecraft.world.entity.Entity
</summary>

```diff
+ boolean lambda$countPlayerPassengers$16(Entity)
- boolean lambda$countPlayerPassengers$18(Entity)
- boolean lambda$getPassengerClosestTo$15(Entity)
- double lambda$getPassengerClosestTo$16(Vec3,Entity)
+ Iterator lambda$getIndirectPassengers$15()
- Iterator lambda$getIndirectPassengers$17()
- Optional getPassengerClosestTo(Vec3)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.axolotl.Axolotl
</summary>

```diff
- LivingEntity getTarget()
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Zoglin
</summary>

```diff
- LivingEntity getTarget()
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.breeze.Breeze
</summary>

```diff
- LivingEntity getTarget()
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.hoglin.Hoglin
</summary>

```diff
- LivingEntity getTarget()
```

</details>
<details>
<summary>
net.minecraft.world.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
</summary>

```diff
- boolean lambda$getOffer$0(Entity,Holder$Reference)
+ boolean lambda$getOffer$0(Holder$Reference)
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.AbstractArrow
</summary>

```diff
- boolean isPickable()
- SlotAccess getSlot(int)
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.AbstractHurtingProjectile
</summary>

```diff
+ boolean hurt(DamageSource,float)
+ boolean isPickable()
+ float getPickRadius()
- void onPunch(Entity)
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.DragonFireball
</summary>

```diff
+ boolean isPickable()
```

</details>
<details>
<summary>
net.minecraft.world.food.FoodData
</summary>

```diff
- void add(int,float)
```

</details>
<details>
<summary>
net.minecraft.world.inventory.BrewingStandMenu$IngredientsSlot
</summary>

```diff
+ int getMaxStackSize()
+ void <init>(Container,int,int,int)
- void <init>(PotionBrewing,Container,int,int,int)
```

</details>
<details>
<summary>
net.minecraft.world.item.ItemStack$3
</summary>

```diff
- ItemStack decode(RegistryFriendlyByteBuf)
- Object decode(Object)
+ void <clinit>()
- void <init>(StreamCodec)
- void encode(Object,Object)
- void encode(RegistryFriendlyByteBuf,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.item.armortrim.ArmorTrim
</summary>

```diff
+ void addToTooltip(Consumer,TooltipFlag)
- void addToTooltip(Item$TooltipContext,Consumer,TooltipFlag)
```

</details>
<details>
<summary>
net.minecraft.world.item.component.BundleContents$Mutable
</summary>

```diff
- BundleContents$Mutable clearItems()
```

</details>
<details>
<summary>
net.minecraft.world.item.component.FireworkExplosion
</summary>

```diff
+ void addToTooltip(Consumer,TooltipFlag)
- void addToTooltip(Item$TooltipContext,Consumer,TooltipFlag)
```

</details>
<details>
<summary>
net.minecraft.world.item.component.Fireworks
</summary>

```diff
+ void addToTooltip(Consumer,TooltipFlag)
- void addToTooltip(Item$TooltipContext,Consumer,TooltipFlag)
```

</details>
<details>
<summary>
net.minecraft.world.item.component.Unbreakable
</summary>

```diff
+ void addToTooltip(Consumer,TooltipFlag)
- void addToTooltip(Item$TooltipContext,Consumer,TooltipFlag)
```

</details>
<details>
<summary>
net.minecraft.world.item.enchantment.WindBurstEnchantment$WindBurstEnchantmentDamageCalculator
</summary>

```diff
+ float getKnockbackMultiplier()
- float getKnockbackMultiplier(Entity)
```

</details>
<details>
<summary>
net.minecraft.world.level.SpawnData
</summary>

```diff
- Optional equipment()
+ Optional equipmentLootTable()
- Optional getEquipment()
+ Optional getEquipmentLootTable()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.DispenserBlock
</summary>

```diff
+ DispenseItemBehavior getDispenseMethod(ItemStack)
- DispenseItemBehavior getDispenseMethod(Level,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.DropperBlock
</summary>

```diff
+ DispenseItemBehavior getDispenseMethod(ItemStack)
- DispenseItemBehavior getDispenseMethod(Level,ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.BrewingStandBlockEntity
</summary>

```diff
+ boolean isBrewable(NonNullList)
- boolean isBrewable(PotionBrewing,NonNullList)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.Beardifier
</summary>

```diff
- double getBuryContribution(double,double,double)
+ double getBuryContribution(int,int,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.functions.ListOperation
</summary>

```diff
- List apply(List,List)
- void <clinit>()
```

</details>
</details>
<hr/>