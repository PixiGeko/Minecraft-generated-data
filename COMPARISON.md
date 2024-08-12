## Comparison with [24w14a](https://github.com/PixiGeko/Minecraft-generated-data/tree/24w14a)

- [Version data](#version-data)
- [Registries](#registries)
- [Tags](#tags)
- [Translations](#translations)
- [File structure](#file-structure)
- [Mappings](#mappings)
  - [Server](#server)
  - [Client](#client)

<hr/>
<details><summary>Version data</summary>
<table><tr><th></th><th align="left">24w14a</th><th>1.20.5-pre1</th></tr><tr><td>DataPack version</td><td><code>38</code></td><td><code>39</code></td></tr><tr><td>World version</td><td><code>3827</code></td><td><code>3829</code></td></tr><tr><td>Protocol version</td><td><code>1073742008</code></td><td><code>1073742009</code></td></tr></table>
</details>
<details><summary>Registries</summary>
<details>
<summary>
item_sub_predicate_type.txt
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
loot_function_type.txt
</summary>

```diff
+ minecraft:filtered
+ minecraft:modify_contents
+ minecraft:set_custom_model_data
+ minecraft:set_item
```

</details>
</details>
<details><summary>Tags</summary>
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
<details><summary>Translations</summary>
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
<details><summary>File structure</summary>
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
<details><summary>Mappings</summary>
<h2>Server</h2>
<details>
<summary>
Classes
</summary>

```diff
- net.minecraft.advancements.critereon.CollectionContentsPredicate
- net.minecraft.advancements.critereon.CollectionContentsPredicate$Single
- net.minecraft.advancements.critereon.CollectionCountsPredicate
- net.minecraft.advancements.critereon.CollectionCountsPredicate$Multiple
- net.minecraft.advancements.critereon.CollectionCountsPredicate$Zero
- net.minecraft.advancements.critereon.ItemAttributeModifiersPredicate$EntryPredicate
- net.minecraft.advancements.critereon.ItemContainerPredicate
- net.minecraft.advancements.critereon.ItemFireworkExplosionPredicate
- net.minecraft.advancements.critereon.ItemFireworksPredicate
+ net.minecraft.advancements.critereon.ItemPotionsPredicate
- net.minecraft.advancements.critereon.ItemPredicate
+ net.minecraft.advancements.critereon.ItemPredicate$Builder
- net.minecraft.advancements.critereon.ItemSubPredicate
+ net.minecraft.advancements.critereon.ItemSubPredicate$Type
- net.minecraft.advancements.critereon.ItemSubPredicates
- net.minecraft.advancements.critereon.ItemWritableBookPredicate
- net.minecraft.advancements.critereon.ItemWrittenBookPredicate
- net.minecraft.core.component.DataComponentMap$3
+ net.minecraft.core.component.DataComponentMap$Builder
- net.minecraft.core.component.DataComponentMap$Builder$SimpleMap
+ net.minecraft.core.component.DataComponentPatch
- net.minecraft.core.component.DataComponentPatch$1
+ net.minecraft.core.component.DataComponentPatch$Builder
- net.minecraft.core.component.DataComponentPatch$PatchKey
+ net.minecraft.core.component.DataComponentPatch$SplitResult
- net.minecraft.core.component.DataComponentPredicate
+ net.minecraft.core.component.DataComponentPredicate$Builder
+ net.minecraft.core.component.DataComponents
- net.minecraft.core.component.DataComponentType
+ net.minecraft.core.component.DataComponentType$Builder
- net.minecraft.core.component.DataComponentType$Builder$SimpleType
+ net.minecraft.core.component.package-info
- net.minecraft.core.component.PatchedDataComponentMap
+ net.minecraft.core.component.TypedDataComponent
- net.minecraft.core.component.TypedDataComponent$1
- net.minecraft.core.dispenser.BlockSource
+ net.minecraft.core.dispenser.BoatDispenseItemBehavior
- net.minecraft.core.dispenser.DefaultDispenseItemBehavior
+ net.minecraft.core.dispenser.DispenseItemBehavior
- net.minecraft.core.dispenser.DispenseItemBehavior$1
+ net.minecraft.core.dispenser.DispenseItemBehavior$10
- net.minecraft.core.dispenser.DispenseItemBehavior$11
+ net.minecraft.core.dispenser.DispenseItemBehavior$12
- net.minecraft.core.dispenser.DispenseItemBehavior$13
+ net.minecraft.core.dispenser.DispenseItemBehavior$14
- net.minecraft.core.dispenser.DispenseItemBehavior$15
+ net.minecraft.core.dispenser.DispenseItemBehavior$16
- net.minecraft.core.dispenser.DispenseItemBehavior$17
+ net.minecraft.core.dispenser.DispenseItemBehavior$18
- net.minecraft.core.dispenser.DispenseItemBehavior$2
+ net.minecraft.core.dispenser.DispenseItemBehavior$3
- net.minecraft.core.dispenser.DispenseItemBehavior$4
+ net.minecraft.core.dispenser.DispenseItemBehavior$5
- net.minecraft.core.dispenser.DispenseItemBehavior$6
+ net.minecraft.core.dispenser.DispenseItemBehavior$7
- net.minecraft.core.dispenser.DispenseItemBehavior$8
+ net.minecraft.core.dispenser.DispenseItemBehavior$9
- net.minecraft.core.dispenser.OptionalDispenseItemBehavior
- net.minecraft.core.dispenser.package-info
+ net.minecraft.core.dispenser.ProjectileDispenseBehavior
- net.minecraft.core.dispenser.ShearsDispenseItemBehavior
+ net.minecraft.core.dispenser.ShulkerBoxDispenseBehavior
+ net.minecraft.core.package-info
- net.minecraft.core.particles.BlockParticleOption
+ net.minecraft.core.particles.BlockParticleOption$1
+ net.minecraft.core.particles.ColorParticleOption$1
- net.minecraft.core.particles.DustColorTransitionOptions
+ net.minecraft.core.particles.DustColorTransitionOptions$1
+ net.minecraft.core.particles.DustParticleOptions$1
- net.minecraft.core.particles.DustParticleOptionsBase
+ net.minecraft.core.particles.ItemParticleOption
+ net.minecraft.core.particles.package-info
+ net.minecraft.core.particles.ParticleOptions$Deserializer
- net.minecraft.core.particles.ParticleType
+ net.minecraft.core.particles.ParticleTypes
- net.minecraft.core.particles.ParticleTypes$1
+ net.minecraft.core.particles.SculkChargeParticleOptions
+ net.minecraft.core.particles.SimpleParticleType
- net.minecraft.core.registries.BuiltInRegistries
+ net.minecraft.core.registries.BuiltInRegistries$RegistryBootstrap
+ net.minecraft.core.registries.package-info
- net.minecraft.core.registries.Registries
- net.minecraft.data.advancements.AdvancementProvider
+ net.minecraft.data.advancements.AdvancementSubProvider
- net.minecraft.data.advancements.package-info
+ net.minecraft.data.advancements.packs.package-info
+ net.minecraft.data.advancements.packs.UpdateOneTwentyOneAdvancementProvider
- net.minecraft.data.advancements.packs.UpdateOneTwentyOneAdventureAdvancements
+ net.minecraft.data.advancements.packs.VanillaAdvancementProvider
- net.minecraft.data.advancements.packs.VanillaAdventureAdvancements
+ net.minecraft.data.advancements.packs.VanillaHusbandryAdvancements
- net.minecraft.data.advancements.packs.VanillaNetherAdvancements
+ net.minecraft.data.advancements.packs.VanillaStoryAdvancements
- net.minecraft.data.advancements.packs.VanillaTheEndAdvancements
- net.minecraft.data.BlockFamilies
+ net.minecraft.data.BlockFamily
- net.minecraft.data.BlockFamily$Builder
+ net.minecraft.data.BlockFamily$Variant
- net.minecraft.data.CachedOutput
+ net.minecraft.data.DataGenerator
- net.minecraft.data.DataGenerator$PackGenerator
+ net.minecraft.data.DataProvider
- net.minecraft.data.DataProvider$Factory
+ net.minecraft.data.HashCache
- net.minecraft.data.HashCache$1
+ net.minecraft.data.HashCache$CacheUpdater
- net.minecraft.data.HashCache$ProviderCache
+ net.minecraft.data.HashCache$ProviderCacheBuilder
- net.minecraft.data.HashCache$UpdateFunction
+ net.minecraft.data.HashCache$UpdateResult
- net.minecraft.data.info.BiomeParametersDumpReport
+ net.minecraft.data.info.BlockListReport
- net.minecraft.data.info.CommandsReport
+ net.minecraft.data.info.ItemListReport
+ net.minecraft.data.info.package-info
- net.minecraft.data.info.RegistryDumpReport
- net.minecraft.data.loot.BlockLootSubProvider
+ net.minecraft.data.loot.EntityLootSubProvider
- net.minecraft.data.loot.LootTableProvider
+ net.minecraft.data.loot.LootTableProvider$SubProviderEntry
- net.minecraft.data.loot.LootTableSubProvider
+ net.minecraft.data.loot.package-info
- net.minecraft.data.loot.packs.package-info
- net.minecraft.data.loot.packs.TradeRebalanceChestLoot
+ net.minecraft.data.loot.packs.TradeRebalanceLootTableProvider
- net.minecraft.data.loot.packs.UpdateOneTwentyOneBlockLoot
+ net.minecraft.data.loot.packs.UpdateOneTwentyOneChestLoot
- net.minecraft.data.loot.packs.UpdateOneTwentyOneEntityLoot
+ net.minecraft.data.loot.packs.UpdateOneTwentyOneEquipmentLoot
- net.minecraft.data.loot.packs.UpdateOneTwentyOneLootTableProvider
+ net.minecraft.data.loot.packs.UpdateOneTwentyOneShearingLoot
- net.minecraft.data.loot.packs.VanillaArchaeologyLoot
+ net.minecraft.data.loot.packs.VanillaBlockLoot
- net.minecraft.data.loot.packs.VanillaChestLoot
+ net.minecraft.data.loot.packs.VanillaEntityLoot
- net.minecraft.data.loot.packs.VanillaEquipmentLoot
+ net.minecraft.data.loot.packs.VanillaFishingLoot
- net.minecraft.data.loot.packs.VanillaGiftLoot
+ net.minecraft.data.loot.packs.VanillaLootTableProvider
- net.minecraft.data.loot.packs.VanillaPiglinBarterLoot
+ net.minecraft.data.loot.packs.VanillaShearingLoot
- net.minecraft.data.Main
- net.minecraft.data.metadata.package-info
+ net.minecraft.data.metadata.PackMetadataGenerator
+ net.minecraft.data.models.BlockModelGenerators
- net.minecraft.data.models.BlockModelGenerators$1
+ net.minecraft.data.models.BlockModelGenerators$BlockEntityModelGenerator
- net.minecraft.data.models.BlockModelGenerators$BlockFamilyProvider
+ net.minecraft.data.models.BlockModelGenerators$BlockStateGeneratorSupplier
- net.minecraft.data.models.BlockModelGenerators$BookSlotModelCacheKey
+ net.minecraft.data.models.BlockModelGenerators$TintState
- net.minecraft.data.models.BlockModelGenerators$WoodProvider
- net.minecraft.data.models.blockstates.BlockStateGenerator
+ net.minecraft.data.models.blockstates.Condition
- net.minecraft.data.models.blockstates.Condition$CompositeCondition
+ net.minecraft.data.models.blockstates.Condition$Operation
- net.minecraft.data.models.blockstates.Condition$TerminalCondition
+ net.minecraft.data.models.blockstates.MultiPartGenerator
- net.minecraft.data.models.blockstates.MultiPartGenerator$ConditionalEntry
+ net.minecraft.data.models.blockstates.MultiPartGenerator$Entry
- net.minecraft.data.models.blockstates.MultiVariantGenerator
- net.minecraft.data.models.blockstates.package-info
+ net.minecraft.data.models.blockstates.PropertyDispatch
- net.minecraft.data.models.blockstates.PropertyDispatch$C1
+ net.minecraft.data.models.blockstates.PropertyDispatch$C2
- net.minecraft.data.models.blockstates.PropertyDispatch$C3
+ net.minecraft.data.models.blockstates.PropertyDispatch$C4
- net.minecraft.data.models.blockstates.PropertyDispatch$C5
+ net.minecraft.data.models.blockstates.PropertyDispatch$PentaFunction
- net.minecraft.data.models.blockstates.PropertyDispatch$QuadFunction
+ net.minecraft.data.models.blockstates.PropertyDispatch$TriFunction
- net.minecraft.data.models.blockstates.Selector
+ net.minecraft.data.models.blockstates.Variant
- net.minecraft.data.models.blockstates.VariantProperties
+ net.minecraft.data.models.blockstates.VariantProperties$Rotation
- net.minecraft.data.models.blockstates.VariantProperty
+ net.minecraft.data.models.blockstates.VariantProperty$Value
+ net.minecraft.data.models.ItemModelGenerators
- net.minecraft.data.models.ItemModelGenerators$TrimModelData
+ net.minecraft.data.models.model.DelegatedModel
- net.minecraft.data.models.model.ModelLocationUtils
+ net.minecraft.data.models.model.ModelTemplate
- net.minecraft.data.models.model.ModelTemplate$JsonFactory
+ net.minecraft.data.models.model.ModelTemplates
- net.minecraft.data.models.model.package-info
- net.minecraft.data.models.model.TexturedModel
+ net.minecraft.data.models.model.TexturedModel$Provider
- net.minecraft.data.models.model.TextureMapping
+ net.minecraft.data.models.model.TextureSlot
+ net.minecraft.data.models.ModelProvider
+ net.minecraft.data.models.package-info
- net.minecraft.data.package-info
+ net.minecraft.data.PackOutput
- net.minecraft.data.PackOutput$PathProvider
+ net.minecraft.data.PackOutput$Target
- net.minecraft.data.recipes.package-info
+ net.minecraft.data.recipes.packs.BundleRecipeProvider
+ net.minecraft.data.recipes.packs.package-info
- net.minecraft.data.recipes.packs.UpdateOneTwentyOneRecipeProvider
+ net.minecraft.data.recipes.packs.VanillaRecipeProvider
- net.minecraft.data.recipes.packs.VanillaRecipeProvider$TrimTemplate
+ net.minecraft.data.recipes.RecipeBuilder
- net.minecraft.data.recipes.RecipeBuilder$1
+ net.minecraft.data.recipes.RecipeCategory
- net.minecraft.data.recipes.RecipeOutput
+ net.minecraft.data.recipes.RecipeProvider
- net.minecraft.data.recipes.RecipeProvider$1
+ net.minecraft.data.recipes.ShapedRecipeBuilder
- net.minecraft.data.recipes.ShapelessRecipeBuilder
+ net.minecraft.data.recipes.SimpleCookingRecipeBuilder
- net.minecraft.data.recipes.SingleItemRecipeBuilder
+ net.minecraft.data.recipes.SmithingTransformRecipeBuilder
- net.minecraft.data.recipes.SmithingTrimRecipeBuilder
+ net.minecraft.data.recipes.SpecialRecipeBuilder
- net.minecraft.data.registries.package-info
- net.minecraft.data.registries.RegistriesDatapackGenerator
+ net.minecraft.data.registries.RegistryPatchGenerator
- net.minecraft.data.registries.UpdateOneTwentyOneRegistries
+ net.minecraft.data.registries.VanillaRegistries
+ net.minecraft.data.structures.NbtToSnbt
- net.minecraft.data.structures.package-info
- net.minecraft.data.structures.SnbtDatafixer
+ net.minecraft.data.structures.SnbtToNbt
- net.minecraft.data.structures.SnbtToNbt$Filter
+ net.minecraft.data.structures.SnbtToNbt$StructureConversionException
- net.minecraft.data.structures.SnbtToNbt$TaskResult
+ net.minecraft.data.structures.StructureUpdater
+ net.minecraft.data.tags.BannerPatternTagsProvider
- net.minecraft.data.tags.BiomeTagsProvider
+ net.minecraft.data.tags.CatVariantTagsProvider
- net.minecraft.data.tags.DamageTypeTagsProvider
- net.minecraft.data.tags.UpdateOneTwentyOneEntityTypeTagsProvider
+ net.minecraft.data.tags.UpdateOneTwentyOneItemTagsProvider
- net.minecraft.data.tags.UpdateOneTwentyOneStructureTagsProvider
+ net.minecraft.data.tags.VanillaBlockTagsProvider
- net.minecraft.data.tags.VanillaEnchantmentTagsProvider
- net.minecraft.network.codec.ByteBufCodecs$3
+ net.minecraft.network.codec.ByteBufCodecs$4
- net.minecraft.network.codec.ByteBufCodecs$5
+ net.minecraft.network.codec.ByteBufCodecs$6
- net.minecraft.network.codec.ByteBufCodecs$7
+ net.minecraft.network.codec.ByteBufCodecs$8
- net.minecraft.network.codec.ByteBufCodecs$9
+ net.minecraft.network.codec.IdDispatchCodec
- net.minecraft.network.codec.IdDispatchCodec$Builder
+ net.minecraft.network.codec.IdDispatchCodec$Entry
- net.minecraft.network.codec.package-info
- net.minecraft.network.codec.StreamCodec
+ net.minecraft.network.codec.StreamCodec$1
- net.minecraft.network.codec.StreamCodec$10
+ net.minecraft.network.codec.StreamCodec$11
- net.minecraft.network.codec.StreamCodec$12
+ net.minecraft.network.codec.StreamCodec$13
- net.minecraft.network.codec.StreamCodec$2
+ net.minecraft.network.codec.StreamCodec$3
- net.minecraft.network.codec.StreamCodec$4
+ net.minecraft.network.codec.StreamCodec$5
- net.minecraft.network.codec.StreamCodec$6
+ net.minecraft.network.codec.StreamCodec$7
- net.minecraft.network.codec.StreamCodec$8
+ net.minecraft.network.codec.StreamCodec$9
- net.minecraft.network.codec.StreamCodec$CodecOperation
+ net.minecraft.network.codec.StreamDecoder
- net.minecraft.network.codec.StreamEncoder
+ net.minecraft.network.codec.StreamMemberEncoder
+ net.minecraft.network.package-info
- net.minecraft.network.protocol.BundleDelimiterPacket
+ net.minecraft.network.protocol.BundlePacket
- net.minecraft.network.protocol.BundlerInfo
+ net.minecraft.network.protocol.BundlerInfo$1
- net.minecraft.network.protocol.BundlerInfo$1$1
+ net.minecraft.network.protocol.BundlerInfo$Bundler
+ net.minecraft.network.protocol.common.ClientboundCustomPayloadPacket
- net.minecraft.network.protocol.common.ClientboundDisconnectPacket
+ net.minecraft.network.protocol.common.ClientboundKeepAlivePacket
- net.minecraft.network.protocol.common.ClientboundPingPacket
+ net.minecraft.network.protocol.common.ClientboundResourcePackPopPacket
- net.minecraft.network.protocol.common.ClientboundResourcePackPushPacket
+ net.minecraft.network.protocol.common.ClientboundStoreCookiePacket
- net.minecraft.network.protocol.common.ClientboundTransferPacket
+ net.minecraft.network.protocol.common.ClientboundUpdateTagsPacket
- net.minecraft.network.protocol.common.ClientCommonPacketListener
- net.minecraft.network.protocol.common.CommonPacketTypes
- net.minecraft.network.protocol.common.custom.BeeDebugPayload
+ net.minecraft.network.protocol.common.custom.BeeDebugPayload$BeeInfo
- net.minecraft.network.protocol.common.custom.BrainDebugPayload
+ net.minecraft.network.protocol.common.custom.BrainDebugPayload$BrainDump
- net.minecraft.network.protocol.common.custom.BrandPayload
+ net.minecraft.network.protocol.common.custom.BreezeDebugPayload
- net.minecraft.network.protocol.common.custom.BreezeDebugPayload$BreezeInfo
+ net.minecraft.network.protocol.common.custom.CustomPacketPayload
- net.minecraft.network.protocol.common.custom.CustomPacketPayload$1
+ net.minecraft.network.protocol.common.custom.CustomPacketPayload$FallbackProvider
- net.minecraft.network.protocol.common.custom.CustomPacketPayload$Type
+ net.minecraft.network.protocol.common.custom.CustomPacketPayload$TypeAndCodec
- net.minecraft.network.protocol.common.custom.DiscardedPayload
+ net.minecraft.network.protocol.common.custom.GameEventDebugPayload
- net.minecraft.network.protocol.common.custom.GameEventListenerDebugPayload
+ net.minecraft.network.protocol.common.custom.GameTestAddMarkerDebugPayload
- net.minecraft.network.protocol.common.custom.GameTestClearMarkersDebugPayload
+ net.minecraft.network.protocol.common.custom.GoalDebugPayload
- net.minecraft.network.protocol.common.custom.GoalDebugPayload$DebugGoal
+ net.minecraft.network.protocol.common.custom.HiveDebugPayload
- net.minecraft.network.protocol.common.custom.HiveDebugPayload$HiveInfo
+ net.minecraft.network.protocol.common.custom.NeighborUpdatesDebugPayload
+ net.minecraft.network.protocol.common.custom.package-info
- net.minecraft.network.protocol.common.custom.PathfindingDebugPayload
+ net.minecraft.network.protocol.common.custom.PoiAddedDebugPayload
- net.minecraft.network.protocol.common.custom.PoiRemovedDebugPayload
+ net.minecraft.network.protocol.common.custom.PoiTicketCountDebugPayload
- net.minecraft.network.protocol.common.custom.RaidsDebugPayload
+ net.minecraft.network.protocol.common.custom.StructuresDebugPayload
- net.minecraft.network.protocol.common.custom.StructuresDebugPayload$PieceInfo
+ net.minecraft.network.protocol.common.custom.VillageSectionsDebugPayload
- net.minecraft.network.protocol.common.custom.WorldGenAttemptDebugPayload
- net.minecraft.network.protocol.common.package-info
- net.minecraft.network.protocol.common.ServerboundClientInformationPacket
+ net.minecraft.network.protocol.common.ServerboundCustomPayloadPacket
- net.minecraft.network.protocol.common.ServerboundKeepAlivePacket
+ net.minecraft.network.protocol.common.ServerboundPongPacket
- net.minecraft.network.protocol.common.ServerboundResourcePackPacket
+ net.minecraft.network.protocol.common.ServerboundResourcePackPacket$Action
+ net.minecraft.network.protocol.common.ServerCommonPacketListener
- net.minecraft.network.protocol.configuration.ClientboundFinishConfigurationPacket
+ net.minecraft.network.protocol.configuration.ClientboundRegistryDataPacket
- net.minecraft.network.protocol.configuration.ClientboundResetChatPacket
+ net.minecraft.network.protocol.configuration.ClientboundSelectKnownPacks
- net.minecraft.network.protocol.configuration.ClientboundUpdateEnabledFeaturesPacket
+ net.minecraft.network.protocol.configuration.ClientConfigurationPacketListener
+ net.minecraft.network.protocol.configuration.ConfigurationPacketTypes
- net.minecraft.network.protocol.configuration.ConfigurationProtocols
- net.minecraft.network.protocol.configuration.package-info
- net.minecraft.network.protocol.configuration.ServerboundFinishConfigurationPacket
+ net.minecraft.network.protocol.configuration.ServerboundSelectKnownPacks
+ net.minecraft.network.protocol.configuration.ServerConfigurationPacketListener
- net.minecraft.network.protocol.cookie.ClientboundCookieRequestPacket
+ net.minecraft.network.protocol.cookie.ClientCookiePacketListener
+ net.minecraft.network.protocol.cookie.CookiePacketTypes
- net.minecraft.network.protocol.cookie.package-info
+ net.minecraft.network.protocol.cookie.ServerboundCookieResponsePacket
- net.minecraft.network.protocol.cookie.ServerCookiePacketListener
- net.minecraft.network.protocol.game.ClientboundAddEntityPacket
+ net.minecraft.network.protocol.game.ClientboundAddExperienceOrbPacket
- net.minecraft.network.protocol.game.ClientboundAnimatePacket
+ net.minecraft.network.protocol.game.ClientboundAwardStatsPacket
- net.minecraft.network.protocol.game.ClientboundBlockChangedAckPacket
+ net.minecraft.network.protocol.game.ClientboundBlockDestructionPacket
- net.minecraft.network.protocol.game.ClientboundBlockEntityDataPacket
+ net.minecraft.network.protocol.game.ClientboundBlockEventPacket
- net.minecraft.network.protocol.game.ClientboundBlockUpdatePacket
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$1
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket$AddOperation
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$Handler
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket$Operation
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$OperationType
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket$UpdateNameOperation
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$UpdateProgressOperation
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket$UpdatePropertiesOperation
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$UpdateStyleOperation
+ net.minecraft.network.protocol.game.ClientboundBundleDelimiterPacket
- net.minecraft.network.protocol.game.ClientboundBundlePacket
+ net.minecraft.network.protocol.game.ClientboundChangeDifficultyPacket
- net.minecraft.network.protocol.game.ClientboundChunkBatchFinishedPacket
+ net.minecraft.network.protocol.game.ClientboundChunkBatchStartPacket
- net.minecraft.network.protocol.game.ClientboundChunksBiomesPacket
+ net.minecraft.network.protocol.game.ClientboundChunksBiomesPacket$ChunkBiomeData
- net.minecraft.network.protocol.game.ClientboundClearTitlesPacket
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket
- net.minecraft.network.protocol.game.ClientboundCommandsPacket$ArgumentNodeStub
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket$Entry
- net.minecraft.network.protocol.game.ClientboundCommandsPacket$LiteralNodeStub
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket$NodeResolver
- net.minecraft.network.protocol.game.ClientboundCommandsPacket$NodeStub
+ net.minecraft.network.protocol.game.ClientboundCommandSuggestionsPacket
- net.minecraft.network.protocol.game.ClientboundCommandSuggestionsPacket$Entry
+ net.minecraft.network.protocol.game.ClientboundContainerClosePacket
- net.minecraft.network.protocol.game.ClientboundContainerSetContentPacket
+ net.minecraft.network.protocol.game.ClientboundContainerSetDataPacket
- net.minecraft.network.protocol.game.ClientboundContainerSetSlotPacket
+ net.minecraft.network.protocol.game.ClientboundCooldownPacket
- net.minecraft.network.protocol.game.ClientboundCustomChatCompletionsPacket
+ net.minecraft.network.protocol.game.ClientboundCustomChatCompletionsPacket$Action
- net.minecraft.network.protocol.game.ClientboundDamageEventPacket
+ net.minecraft.network.protocol.game.ClientboundDebugSamplePacket
- net.minecraft.network.protocol.game.ClientboundDeleteChatPacket
+ net.minecraft.network.protocol.game.ClientboundDisguisedChatPacket
- net.minecraft.network.protocol.game.ClientboundEntityEventPacket
+ net.minecraft.network.protocol.game.ClientboundExplodePacket
- net.minecraft.network.protocol.game.ClientboundForgetLevelChunkPacket
+ net.minecraft.network.protocol.game.ClientboundGameEventPacket
- net.minecraft.network.protocol.game.ClientboundGameEventPacket$Type
+ net.minecraft.network.protocol.game.ClientboundHorseScreenOpenPacket
- net.minecraft.network.protocol.game.ClientboundHurtAnimationPacket
+ net.minecraft.network.protocol.game.ClientboundInitializeBorderPacket
- net.minecraft.network.protocol.game.ClientboundLevelChunkPacketData
+ net.minecraft.network.protocol.game.ClientboundLevelChunkPacketData$BlockEntityInfo
- net.minecraft.network.protocol.game.ClientboundLevelChunkPacketData$BlockEntityTagOutput
+ net.minecraft.network.protocol.game.ClientboundLevelChunkWithLightPacket
- net.minecraft.network.protocol.game.ClientboundLevelEventPacket
+ net.minecraft.network.protocol.game.ClientboundLevelParticlesPacket
- net.minecraft.network.protocol.game.ClientboundLightUpdatePacket
+ net.minecraft.network.protocol.game.ClientboundLightUpdatePacketData
- net.minecraft.network.protocol.game.ClientboundLoginPacket
+ net.minecraft.network.protocol.game.ClientboundMapItemDataPacket
- net.minecraft.network.protocol.game.ClientboundMerchantOffersPacket
+ net.minecraft.network.protocol.game.ClientboundMoveEntityPacket
- net.minecraft.network.protocol.game.ClientboundMoveEntityPacket$Pos
+ net.minecraft.network.protocol.game.ClientboundMoveEntityPacket$PosRot
- net.minecraft.network.protocol.game.ClientboundMoveEntityPacket$Rot
+ net.minecraft.network.protocol.game.ClientboundMoveVehiclePacket
- net.minecraft.network.protocol.game.ClientboundOpenBookPacket
+ net.minecraft.network.protocol.game.ClientboundOpenScreenPacket
- net.minecraft.network.protocol.game.ClientboundOpenSignEditorPacket
+ net.minecraft.network.protocol.game.ClientboundPlaceGhostRecipePacket
- net.minecraft.network.protocol.game.ClientboundPlayerAbilitiesPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerChatPacket
- net.minecraft.network.protocol.game.ClientboundPlayerCombatEndPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerCombatEnterPacket
- net.minecraft.network.protocol.game.ClientboundPlayerCombatKillPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoRemovePacket
- net.minecraft.network.protocol.game.ClientboundPlayerInfoUpdatePacket
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoUpdatePacket$Action
- net.minecraft.network.protocol.game.ClientboundPlayerInfoUpdatePacket$Action$Reader
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoUpdatePacket$Action$Writer
- net.minecraft.network.protocol.game.ClientboundPlayerInfoUpdatePacket$Entry
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoUpdatePacket$EntryBuilder
- net.minecraft.network.protocol.game.ClientboundPlayerLookAtPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerPositionPacket
- net.minecraft.network.protocol.game.ClientboundProjectilePowerPacket
+ net.minecraft.network.protocol.game.ClientboundRecipePacket
- net.minecraft.network.protocol.game.ClientboundRecipePacket$State
+ net.minecraft.network.protocol.game.ClientboundRemoveEntitiesPacket
- net.minecraft.network.protocol.game.ClientboundRemoveMobEffectPacket
+ net.minecraft.network.protocol.game.ClientboundResetScorePacket
- net.minecraft.network.protocol.game.ClientboundRespawnPacket
+ net.minecraft.network.protocol.game.ClientboundRotateHeadPacket
- net.minecraft.network.protocol.game.ClientboundSectionBlocksUpdatePacket
+ net.minecraft.network.protocol.game.ClientboundSelectAdvancementsTabPacket
- net.minecraft.network.protocol.game.ClientboundServerDataPacket
+ net.minecraft.network.protocol.game.ClientboundSetActionBarTextPacket
- net.minecraft.network.protocol.game.ClientboundSetBorderCenterPacket
+ net.minecraft.network.protocol.game.ClientboundSetBorderLerpSizePacket
- net.minecraft.network.protocol.game.ClientboundSetBorderSizePacket
+ net.minecraft.network.protocol.game.ClientboundSetBorderWarningDelayPacket
- net.minecraft.network.protocol.game.ClientboundSetBorderWarningDistancePacket
+ net.minecraft.network.protocol.game.ClientboundSetCameraPacket
- net.minecraft.network.protocol.game.ClientboundSetCarriedItemPacket
+ net.minecraft.network.protocol.game.ClientboundSetChunkCacheCenterPacket
- net.minecraft.network.protocol.game.ClientboundSetChunkCacheRadiusPacket
+ net.minecraft.network.protocol.game.ClientboundSetDefaultSpawnPositionPacket
- net.minecraft.network.protocol.game.ClientboundSetDisplayObjectivePacket
+ net.minecraft.network.protocol.game.ClientboundSetEntityDataPacket
- net.minecraft.network.protocol.game.ClientboundSetEntityLinkPacket
+ net.minecraft.network.protocol.game.ClientboundSetEntityMotionPacket
- net.minecraft.network.protocol.game.ClientboundSetEquipmentPacket
+ net.minecraft.network.protocol.game.ClientboundSetExperiencePacket
- net.minecraft.network.protocol.game.ClientboundSetHealthPacket
+ net.minecraft.network.protocol.game.ClientboundSetObjectivePacket
- net.minecraft.network.protocol.game.ClientboundSetPassengersPacket
+ net.minecraft.network.protocol.game.ClientboundSetPlayerTeamPacket
- net.minecraft.network.protocol.game.ClientboundSetPlayerTeamPacket$Action
+ net.minecraft.network.protocol.game.ClientboundSetPlayerTeamPacket$Parameters
- net.minecraft.network.protocol.game.ClientboundSetScorePacket
+ net.minecraft.network.protocol.game.ClientboundSetSimulationDistancePacket
- net.minecraft.network.protocol.game.ClientboundSetSubtitleTextPacket
+ net.minecraft.network.protocol.game.ClientboundSetTimePacket
+ net.minecraft.network.protocol.game.ClientboundSetTitlesAnimationPacket
- net.minecraft.network.protocol.game.ClientboundSetTitleTextPacket
- net.minecraft.network.protocol.game.ClientboundSoundEntityPacket
+ net.minecraft.network.protocol.game.ClientboundSoundPacket
- net.minecraft.network.protocol.game.ClientboundStartConfigurationPacket
+ net.minecraft.network.protocol.game.ClientboundStopSoundPacket
- net.minecraft.network.protocol.game.ClientboundSystemChatPacket
+ net.minecraft.network.protocol.game.ClientboundTabListPacket
- net.minecraft.network.protocol.game.ClientboundTagQueryPacket
+ net.minecraft.network.protocol.game.ClientboundTakeItemEntityPacket
- net.minecraft.network.protocol.game.ClientboundTeleportEntityPacket
+ net.minecraft.network.protocol.game.ClientboundTickingStatePacket
- net.minecraft.network.protocol.game.ClientboundTickingStepPacket
+ net.minecraft.network.protocol.game.ClientboundUpdateAdvancementsPacket
- net.minecraft.network.protocol.game.ClientboundUpdateAttributesPacket
+ net.minecraft.network.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
- net.minecraft.network.protocol.game.ClientboundUpdateMobEffectPacket
+ net.minecraft.network.protocol.game.ClientboundUpdateRecipesPacket
+ net.minecraft.network.protocol.game.ClientGamePacketListener
- net.minecraft.network.protocol.game.CommonPlayerSpawnInfo
+ net.minecraft.network.protocol.game.DebugEntityNameGenerator
- net.minecraft.network.protocol.game.DebugPackets
+ net.minecraft.network.protocol.game.GamePacketTypes
- net.minecraft.network.protocol.game.GameProtocols
- net.minecraft.network.protocol.game.package-info
+ net.minecraft.network.protocol.game.ServerboundAcceptTeleportationPacket
- net.minecraft.network.protocol.game.ServerboundBlockEntityTagQueryPacket
+ net.minecraft.network.protocol.game.ServerboundChangeDifficultyPacket
- net.minecraft.network.protocol.game.ServerboundChatAckPacket
+ net.minecraft.network.protocol.game.ServerboundChatCommandPacket
- net.minecraft.network.protocol.game.ServerboundChatCommandSignedPacket
+ net.minecraft.network.protocol.game.ServerboundChatPacket
- net.minecraft.network.protocol.game.ServerboundChatSessionUpdatePacket
+ net.minecraft.network.protocol.game.ServerboundChunkBatchReceivedPacket
- net.minecraft.network.protocol.game.ServerboundClientCommandPacket
+ net.minecraft.network.protocol.game.ServerboundClientCommandPacket$Action
- net.minecraft.network.protocol.game.ServerboundCommandSuggestionPacket
+ net.minecraft.network.protocol.game.ServerboundConfigurationAcknowledgedPacket
- net.minecraft.network.protocol.game.ServerboundContainerButtonClickPacket
+ net.minecraft.network.protocol.game.ServerboundContainerClickPacket
- net.minecraft.network.protocol.game.ServerboundContainerClosePacket
+ net.minecraft.network.protocol.game.ServerboundContainerSlotStateChangedPacket
- net.minecraft.network.protocol.game.ServerboundDebugSampleSubscriptionPacket
+ net.minecraft.network.protocol.game.ServerboundEditBookPacket
- net.minecraft.network.protocol.game.ServerboundEntityTagQueryPacket
+ net.minecraft.network.protocol.game.ServerboundInteractPacket
- net.minecraft.network.protocol.game.ServerboundInteractPacket$1
+ net.minecraft.network.protocol.game.ServerboundInteractPacket$Action
- net.minecraft.network.protocol.game.ServerboundInteractPacket$ActionType
+ net.minecraft.network.protocol.game.ServerboundInteractPacket$Handler
- net.minecraft.network.protocol.game.ServerboundInteractPacket$InteractionAction
+ net.minecraft.network.protocol.game.ServerboundInteractPacket$InteractionAtLocationAction
- net.minecraft.network.protocol.game.ServerboundJigsawGeneratePacket
+ net.minecraft.network.protocol.game.ServerboundLockDifficultyPacket
- net.minecraft.network.protocol.game.ServerboundMovePlayerPacket
+ net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$Pos
- net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$PosRot
+ net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$Rot
- net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$StatusOnly
+ net.minecraft.network.protocol.game.ServerboundMoveVehiclePacket
- net.minecraft.network.protocol.game.ServerboundPaddleBoatPacket
+ net.minecraft.network.protocol.game.ServerboundPickItemPacket
- net.minecraft.network.protocol.game.ServerboundPlaceRecipePacket
+ net.minecraft.network.protocol.game.ServerboundPlayerAbilitiesPacket
- net.minecraft.network.protocol.game.ServerboundPlayerActionPacket
+ net.minecraft.network.protocol.game.ServerboundPlayerActionPacket$Action
- net.minecraft.network.protocol.game.ServerboundPlayerCommandPacket
+ net.minecraft.network.protocol.game.ServerboundPlayerCommandPacket$Action
- net.minecraft.network.protocol.game.ServerboundPlayerInputPacket
+ net.minecraft.network.protocol.game.ServerboundRecipeBookChangeSettingsPacket
- net.minecraft.network.protocol.game.ServerboundRecipeBookSeenRecipePacket
+ net.minecraft.network.protocol.game.ServerboundRenameItemPacket
- net.minecraft.network.protocol.game.ServerboundSeenAdvancementsPacket
+ net.minecraft.network.protocol.game.ServerboundSeenAdvancementsPacket$Action
- net.minecraft.network.protocol.game.ServerboundSelectTradePacket
+ net.minecraft.network.protocol.game.ServerboundSetBeaconPacket
- net.minecraft.network.protocol.game.ServerboundSetCarriedItemPacket
+ net.minecraft.network.protocol.game.ServerboundSetCommandBlockPacket
- net.minecraft.network.protocol.game.ServerboundSetCommandMinecartPacket
+ net.minecraft.network.protocol.game.ServerboundSetCreativeModeSlotPacket
- net.minecraft.network.protocol.game.ServerboundSetJigsawBlockPacket
+ net.minecraft.network.protocol.game.ServerboundSetStructureBlockPacket
- net.minecraft.network.protocol.game.ServerboundSignUpdatePacket
+ net.minecraft.network.protocol.game.ServerboundSwingPacket
- net.minecraft.network.protocol.game.ServerboundTeleportToEntityPacket
+ net.minecraft.network.protocol.game.ServerboundUseItemOnPacket
- net.minecraft.network.protocol.game.ServerboundUseItemPacket
+ net.minecraft.network.protocol.game.ServerGamePacketListener
- net.minecraft.network.protocol.game.ServerPacketListener
+ net.minecraft.network.protocol.game.VecDeltaCodec
+ net.minecraft.network.protocol.handshake.ClientIntent
- net.minecraft.network.protocol.handshake.ClientIntentionPacket
+ net.minecraft.network.protocol.handshake.HandshakePacketTypes
- net.minecraft.network.protocol.handshake.HandshakeProtocols
- net.minecraft.network.protocol.handshake.package-info
+ net.minecraft.network.protocol.handshake.ServerHandshakePacketListener
- net.minecraft.network.protocol.login.ClientboundCustomQueryPacket
+ net.minecraft.network.protocol.login.ClientboundGameProfilePacket
- net.minecraft.network.protocol.login.ClientboundHelloPacket
+ net.minecraft.network.protocol.login.ClientboundLoginCompressionPacket
- net.minecraft.network.protocol.login.ClientboundLoginDisconnectPacket
+ net.minecraft.network.protocol.login.ClientLoginPacketListener
- net.minecraft.network.protocol.login.custom.CustomQueryAnswerPayload
+ net.minecraft.network.protocol.login.custom.CustomQueryPayload
- net.minecraft.network.protocol.login.custom.DiscardedQueryAnswerPayload
+ net.minecraft.network.protocol.login.custom.DiscardedQueryPayload
- net.minecraft.network.protocol.login.custom.package-info
+ net.minecraft.network.protocol.login.LoginPacketTypes
- net.minecraft.network.protocol.login.LoginProtocols
+ net.minecraft.network.protocol.login.package-info
- net.minecraft.network.protocol.login.ServerboundCustomQueryAnswerPacket
+ net.minecraft.network.protocol.login.ServerboundHelloPacket
- net.minecraft.network.protocol.login.ServerboundKeyPacket
+ net.minecraft.network.protocol.login.ServerboundLoginAcknowledgedPacket
+ net.minecraft.network.protocol.login.ServerLoginPacketListener
- net.minecraft.network.protocol.package-info
- net.minecraft.network.protocol.Packet
+ net.minecraft.network.protocol.PacketFlow
- net.minecraft.network.protocol.PacketType
+ net.minecraft.network.protocol.PacketUtils
- net.minecraft.network.protocol.ping.ClientboundPongResponsePacket
+ net.minecraft.network.protocol.ping.ClientPongPacketListener
- net.minecraft.network.protocol.ping.package-info
+ net.minecraft.network.protocol.ping.PingPacketTypes
+ net.minecraft.network.protocol.ping.ServerboundPingRequestPacket
- net.minecraft.network.protocol.ping.ServerPingPacketListener
- net.minecraft.network.protocol.ProtocolCodecBuilder
+ net.minecraft.network.protocol.ProtocolInfoBuilder
- net.minecraft.network.protocol.ProtocolInfoBuilder$CodecEntry
+ net.minecraft.network.protocol.ProtocolInfoBuilder$Implementation
- net.minecraft.network.protocol.status.ClientboundStatusResponsePacket
+ net.minecraft.network.protocol.status.ClientStatusPacketListener
+ net.minecraft.network.protocol.status.package-info
- net.minecraft.network.protocol.status.ServerboundStatusRequestPacket
+ net.minecraft.network.protocol.status.ServerStatus
- net.minecraft.network.protocol.status.ServerStatus$Favicon
+ net.minecraft.network.protocol.status.ServerStatus$Players
- net.minecraft.network.protocol.status.ServerStatus$Version
+ net.minecraft.network.protocol.status.ServerStatusPacketListener
+ net.minecraft.network.protocol.status.StatusPacketTypes
- net.minecraft.network.protocol.status.StatusProtocols
- net.minecraft.network.syncher.EntityDataAccessor
+ net.minecraft.network.syncher.EntityDataSerializer
- net.minecraft.network.syncher.EntityDataSerializer$ForValueType
+ net.minecraft.network.syncher.EntityDataSerializers
- net.minecraft.network.syncher.EntityDataSerializers$1
+ net.minecraft.network.syncher.EntityDataSerializers$2
- net.minecraft.network.syncher.EntityDataSerializers$3
+ net.minecraft.network.syncher.EntityDataSerializers$4
+ net.minecraft.network.syncher.package-info
- net.minecraft.network.syncher.SyncedDataHolder
+ net.minecraft.network.syncher.SynchedEntityData
- net.minecraft.network.syncher.SynchedEntityData$Builder
+ net.minecraft.network.syncher.SynchedEntityData$DataItem
- net.minecraft.network.syncher.SynchedEntityData$DataValue
- net.minecraft.obfuscate.DontObfuscate
+ net.minecraft.obfuscate.package-info
- net.minecraft.package-info
+ net.minecraft.recipebook.package-info
+ net.minecraft.recipebook.PlaceRecipe
- net.minecraft.recipebook.ServerPlaceRecipe
- net.minecraft.references.Blocks
+ net.minecraft.references.Items
- net.minecraft.resources.DelegatingOps
+ net.minecraft.resources.FileToIdConverter
- net.minecraft.resources.HolderSetCodec
- net.minecraft.resources.package-info
+ net.minecraft.resources.RegistryDataLoader
- net.minecraft.resources.RegistryDataLoader$1
+ net.minecraft.resources.RegistryDataLoader$Loader
- net.minecraft.resources.RegistryDataLoader$LoadingFunction
+ net.minecraft.resources.RegistryDataLoader$RegistryData
- net.minecraft.resources.RegistryFileCodec
+ net.minecraft.resources.RegistryFixedCodec
- net.minecraft.resources.RegistryOps
+ net.minecraft.resources.RegistryOps$1
- net.minecraft.resources.RegistryOps$2
+ net.minecraft.resources.RegistryOps$RegistryInfo
- net.minecraft.resources.RegistryOps$RegistryInfoLookup
+ net.minecraft.resources.ResourceKey
- net.minecraft.resources.ResourceKey$InternKey
+ net.minecraft.resources.ResourceLocation
- net.minecraft.resources.ResourceLocation$Dummy
+ net.minecraft.resources.ResourceLocation$Serializer
- net.minecraft.server.advancements.AdvancementVisibilityEvaluator
+ net.minecraft.server.advancements.AdvancementVisibilityEvaluator$Output
- net.minecraft.server.advancements.AdvancementVisibilityEvaluator$VisibilityRule
+ net.minecraft.server.advancements.package-info
+ net.minecraft.server.Bootstrap
- net.minecraft.server.Bootstrap$1
- net.minecraft.server.bossevents.CustomBossEvent
+ net.minecraft.server.bossevents.CustomBossEvents
- net.minecraft.server.bossevents.package-info
+ net.minecraft.server.ChainedJsonException
- net.minecraft.server.ChainedJsonException$Entry
+ net.minecraft.server.chase.ChaseClient
- net.minecraft.server.chase.ChaseClient$TeleportTarget
+ net.minecraft.server.chase.ChaseServer
- net.minecraft.server.chase.ChaseServer$PlayerPosition
+ net.minecraft.server.chase.package-info
- net.minecraft.server.commands.AdvancementCommands
+ net.minecraft.server.commands.AdvancementCommands$Action
- net.minecraft.server.commands.AdvancementCommands$Action$1
+ net.minecraft.server.commands.AdvancementCommands$Action$2
- net.minecraft.server.commands.AdvancementCommands$Mode
+ net.minecraft.server.commands.AttributeCommand
- net.minecraft.server.commands.BanIpCommands
+ net.minecraft.server.commands.BanListCommands
- net.minecraft.server.commands.BanPlayerCommands
+ net.minecraft.server.commands.BossBarCommands
- net.minecraft.server.commands.ChaseCommand
+ net.minecraft.server.commands.ClearInventoryCommands
- net.minecraft.server.commands.CloneCommands
+ net.minecraft.server.commands.CloneCommands$CloneBlockEntityInfo
- net.minecraft.server.commands.CloneCommands$CloneBlockInfo
+ net.minecraft.server.commands.CloneCommands$CommandFunction
- net.minecraft.server.commands.CloneCommands$DimensionAndPosition
+ net.minecraft.server.commands.CloneCommands$Mode
- net.minecraft.server.commands.DamageCommand
- net.minecraft.server.commands.data.BlockDataAccessor
+ net.minecraft.server.commands.data.BlockDataAccessor$1
- net.minecraft.server.commands.data.DataAccessor
+ net.minecraft.server.commands.data.DataCommands
- net.minecraft.server.commands.data.DataCommands$DataManipulator
+ net.minecraft.server.commands.data.DataCommands$DataManipulatorDecorator
- net.minecraft.server.commands.data.DataCommands$DataProvider
+ net.minecraft.server.commands.data.DataCommands$StringProcessor
- net.minecraft.server.commands.data.EntityDataAccessor
+ net.minecraft.server.commands.data.EntityDataAccessor$1
- net.minecraft.server.commands.data.package-info
- net.minecraft.server.commands.data.StorageDataAccessor
+ net.minecraft.server.commands.data.StorageDataAccessor$1
+ net.minecraft.server.commands.DataPackCommand
- net.minecraft.server.commands.DataPackCommand$Inserter
- net.minecraft.server.commands.DebugCommand
+ net.minecraft.server.commands.DebugCommand$TraceCustomExecutor
- net.minecraft.server.commands.DebugCommand$TraceCustomExecutor$1
+ net.minecraft.server.commands.DebugCommand$Tracer
- net.minecraft.server.commands.DebugConfigCommand
+ net.minecraft.server.commands.DebugMobSpawningCommand
- net.minecraft.server.commands.DebugPathCommand
+ net.minecraft.server.commands.DefaultGameModeCommands
+ net.minecraft.server.commands.DeOpCommands
- net.minecraft.server.commands.DifficultyCommand
+ net.minecraft.server.commands.EffectCommands
- net.minecraft.server.commands.EmoteCommands
+ net.minecraft.server.commands.EnchantCommand
- net.minecraft.server.commands.ExecuteCommand
+ net.minecraft.server.commands.ExecuteCommand$CommandGetter
- net.minecraft.server.commands.ExecuteCommand$CommandNumericPredicate
+ net.minecraft.server.commands.ExecuteCommand$CommandPredicate
- net.minecraft.server.commands.ExecuteCommand$ExecuteIfFunctionCustomModifier
+ net.minecraft.server.commands.ExecuteCommand$IntBiPredicate
- net.minecraft.server.commands.ExperienceCommand
+ net.minecraft.server.commands.ExperienceCommand$Type
- net.minecraft.server.commands.FillBiomeCommand
+ net.minecraft.server.commands.FillCommand
- net.minecraft.server.commands.FillCommand$Mode
+ net.minecraft.server.commands.ForceLoadCommand
- net.minecraft.server.commands.FunctionCommand
+ net.minecraft.server.commands.FunctionCommand$1
- net.minecraft.server.commands.FunctionCommand$1Accumulator
+ net.minecraft.server.commands.FunctionCommand$2
- net.minecraft.server.commands.FunctionCommand$3
+ net.minecraft.server.commands.FunctionCommand$4
- net.minecraft.server.commands.FunctionCommand$5
+ net.minecraft.server.commands.FunctionCommand$Callbacks
- net.minecraft.server.commands.FunctionCommand$FunctionCustomExecutor
+ net.minecraft.server.commands.GameModeCommand
- net.minecraft.server.commands.GameRuleCommand
+ net.minecraft.server.commands.GameRuleCommand$1
- net.minecraft.server.commands.GiveCommand
+ net.minecraft.server.commands.HelpCommand
- net.minecraft.server.commands.ItemCommands
+ net.minecraft.server.commands.JfrCommand
- net.minecraft.server.commands.KickCommand
+ net.minecraft.server.commands.KillCommand
- net.minecraft.server.commands.ListPlayersCommand
+ net.minecraft.server.commands.LocateCommand
- net.minecraft.server.commands.LootCommand
+ net.minecraft.server.commands.LootCommand$Callback
- net.minecraft.server.commands.LootCommand$DropConsumer
+ net.minecraft.server.commands.LootCommand$TailProvider
- net.minecraft.server.commands.MsgCommand
+ net.minecraft.server.commands.OpCommand
+ net.minecraft.server.commands.package-info
- net.minecraft.server.commands.PardonCommand
+ net.minecraft.server.commands.PardonIpCommand
- net.minecraft.server.commands.ParticleCommand
+ net.minecraft.server.commands.PerfCommand
- net.minecraft.server.commands.PlaceCommand
+ net.minecraft.server.commands.PlaySoundCommand
- net.minecraft.server.commands.PublishCommand
+ net.minecraft.server.commands.RaidCommand
- net.minecraft.server.commands.RandomCommand
+ net.minecraft.server.commands.RecipeCommand
- net.minecraft.server.commands.ReloadCommand
+ net.minecraft.server.commands.ResetChunksCommand
- net.minecraft.server.commands.ReturnCommand
+ net.minecraft.server.commands.ReturnCommand$ReturnFailCustomExecutor
- net.minecraft.server.commands.ReturnCommand$ReturnFromCommandCustomModifier
+ net.minecraft.server.commands.ReturnCommand$ReturnValueCustomExecutor
- net.minecraft.server.commands.RideCommand
+ net.minecraft.server.commands.SaveAllCommand
- net.minecraft.server.commands.SaveOffCommand
+ net.minecraft.server.commands.SaveOnCommand
- net.minecraft.server.commands.SayCommand
+ net.minecraft.server.commands.ScheduleCommand
- net.minecraft.server.commands.ScoreboardCommand
+ net.minecraft.server.commands.ScoreboardCommand$NumberFormatCommandExecutor
- net.minecraft.server.commands.SeedCommand
+ net.minecraft.server.commands.ServerPackCommand
- net.minecraft.server.commands.SetBlockCommand
+ net.minecraft.server.commands.SetBlockCommand$Filter
- net.minecraft.server.commands.SetBlockCommand$Mode
+ net.minecraft.server.commands.SetPlayerIdleTimeoutCommand
- net.minecraft.server.commands.SetSpawnCommand
+ net.minecraft.server.commands.SetWorldSpawnCommand
- net.minecraft.server.commands.SpawnArmorTrimsCommand
+ net.minecraft.server.commands.SpectateCommand
- net.minecraft.server.commands.SpreadPlayersCommand
+ net.minecraft.server.commands.SpreadPlayersCommand$Position
- net.minecraft.server.commands.StopCommand
+ net.minecraft.server.commands.StopSoundCommand
- net.minecraft.server.commands.SummonCommand
+ net.minecraft.server.commands.TagCommand
- net.minecraft.server.commands.TeamCommand
+ net.minecraft.server.commands.TeamMsgCommand
- net.minecraft.server.commands.TeleportCommand
+ net.minecraft.server.commands.TeleportCommand$LookAt
- net.minecraft.server.commands.TeleportCommand$LookAtEntity
+ net.minecraft.server.commands.TeleportCommand$LookAtPosition
- net.minecraft.server.commands.TellRawCommand
+ net.minecraft.server.commands.TickCommand
- net.minecraft.server.commands.TimeCommand
+ net.minecraft.server.commands.TitleCommand
- net.minecraft.server.commands.TransferCommand
+ net.minecraft.server.commands.TriggerCommand
- net.minecraft.server.commands.WardenSpawnTrackerCommand
+ net.minecraft.server.commands.WeatherCommand
- net.minecraft.server.commands.WhitelistCommand
+ net.minecraft.server.commands.WorldBorderCommand
+ net.minecraft.server.ConsoleInput
- net.minecraft.server.DebugLoggedPrintStream
- net.minecraft.server.dedicated.DedicatedPlayerList
+ net.minecraft.server.dedicated.DedicatedServer
- net.minecraft.server.dedicated.DedicatedServer$1
+ net.minecraft.server.dedicated.DedicatedServerProperties
- net.minecraft.server.dedicated.DedicatedServerProperties$WorldDimensionData
+ net.minecraft.server.dedicated.DedicatedServerSettings
- net.minecraft.server.dedicated.package-info
- net.minecraft.server.dedicated.ServerWatchdog
+ net.minecraft.server.dedicated.ServerWatchdog$1
- net.minecraft.server.dedicated.Settings
+ net.minecraft.server.dedicated.Settings$MutableValue
+ net.minecraft.server.Eula
+ net.minecraft.server.gui.MinecraftServerGui
- net.minecraft.server.gui.MinecraftServerGui$1
+ net.minecraft.server.gui.MinecraftServerGui$2
- net.minecraft.server.gui.package-info
- net.minecraft.server.gui.PlayerListComponent
+ net.minecraft.server.gui.StatsComponent
+ net.minecraft.server.level.BlockDestructionProgress
- net.minecraft.server.level.ChunkHolder
+ net.minecraft.server.level.ChunkHolder$ChunkSaveDebug
- net.minecraft.server.level.ChunkHolder$LevelChangeListener
+ net.minecraft.server.level.ChunkHolder$PlayerProvider
- net.minecraft.server.level.ChunkLevel
+ net.minecraft.server.level.ChunkLevel$1
- net.minecraft.server.level.ChunkMap
+ net.minecraft.server.level.ChunkMap$DistanceManager
- net.minecraft.server.level.ChunkMap$TrackedEntity
+ net.minecraft.server.level.ChunkResult
- net.minecraft.server.level.ChunkResult$Fail
+ net.minecraft.server.level.ChunkResult$Success
- net.minecraft.server.level.ChunkTaskPriorityQueue
+ net.minecraft.server.level.ChunkTaskPriorityQueueSorter
- net.minecraft.server.level.ChunkTaskPriorityQueueSorter$Message
+ net.minecraft.server.level.ChunkTaskPriorityQueueSorter$Release
- net.minecraft.server.level.ChunkTracker
+ net.minecraft.server.level.ChunkTrackingView
- net.minecraft.server.level.ChunkTrackingView$1
+ net.minecraft.server.level.ChunkTrackingView$Positioned
- net.minecraft.server.level.ClientInformation
+ net.minecraft.server.level.ColumnPos
- net.minecraft.server.level.DemoMode
+ net.minecraft.server.level.DistanceManager
- net.minecraft.server.level.DistanceManager$ChunkTicketTracker
+ net.minecraft.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
- net.minecraft.server.level.DistanceManager$PlayerTicketTracker
+ net.minecraft.server.level.FullChunkStatus
- net.minecraft.server.level.package-info
- net.minecraft.server.level.PlayerMap
+ net.minecraft.server.level.PlayerRespawnLogic
+ net.minecraft.server.level.progress.ChunkProgressListener
- net.minecraft.server.level.progress.ChunkProgressListenerFactory
+ net.minecraft.server.level.progress.LoggerChunkProgressListener
- net.minecraft.server.level.progress.package-info
- net.minecraft.server.level.progress.ProcessorChunkProgressListener
+ net.minecraft.server.level.progress.StoringChunkProgressListener
- net.minecraft.server.level.SectionTracker
+ net.minecraft.server.level.ServerBossEvent
- net.minecraft.server.level.ServerChunkCache
+ net.minecraft.server.level.ServerChunkCache$ChunkAndHolder
- net.minecraft.server.level.ServerChunkCache$MainThreadExecutor
+ net.minecraft.server.level.ServerEntity
- net.minecraft.server.level.ServerLevel
+ net.minecraft.server.level.ServerLevel$EntityCallbacks
- net.minecraft.server.level.ServerPlayer
+ net.minecraft.server.level.ServerPlayer$1
- net.minecraft.server.level.ServerPlayer$2
+ net.minecraft.server.level.ServerPlayerGameMode
- net.minecraft.server.level.ThreadedLevelLightEngine
+ net.minecraft.server.level.ThreadedLevelLightEngine$TaskType
- net.minecraft.server.level.Ticket
+ net.minecraft.server.level.TicketType
- net.minecraft.server.level.TickingTracker
+ net.minecraft.server.level.WorldGenRegion
- net.minecraft.server.LoggedPrintStream
+ net.minecraft.server.Main
- net.minecraft.server.Main$1
+ net.minecraft.server.MinecraftServer
- net.minecraft.server.MinecraftServer$1
+ net.minecraft.server.MinecraftServer$ReloadableResources
- net.minecraft.server.MinecraftServer$ServerResourcePackInfo
+ net.minecraft.server.MinecraftServer$TimeProfiler
- net.minecraft.server.MinecraftServer$TimeProfiler$1
+ net.minecraft.server.network.CommonListenerCookie
- net.minecraft.server.network.config.JoinWorldTask
+ net.minecraft.server.network.config.package-info
+ net.minecraft.server.network.config.ServerResourcePackConfigurationTask
- net.minecraft.server.network.config.SynchronizeRegistriesTask
- net.minecraft.server.network.ConfigurationTask
+ net.minecraft.server.network.ConfigurationTask$Type
- net.minecraft.server.network.Filterable
+ net.minecraft.server.network.FilteredText
- net.minecraft.server.network.LegacyProtocolUtils
+ net.minecraft.server.network.LegacyQueryHandler
- net.minecraft.server.network.MemoryServerHandshakePacketListenerImpl
- net.minecraft.server.network.package-info
+ net.minecraft.server.network.PlayerChunkSender
- net.minecraft.server.network.ServerCommonPacketListenerImpl
+ net.minecraft.server.network.ServerConfigurationPacketListenerImpl
- net.minecraft.server.network.ServerConnectionListener
+ net.minecraft.server.network.ServerConnectionListener$1
- net.minecraft.server.network.ServerConnectionListener$2
+ net.minecraft.server.network.ServerConnectionListener$LatencySimulator
- net.minecraft.server.network.ServerConnectionListener$LatencySimulator$DelayedMessage
+ net.minecraft.server.network.ServerGamePacketListenerImpl
- net.minecraft.server.network.ServerGamePacketListenerImpl$1
+ net.minecraft.server.network.ServerGamePacketListenerImpl$2
- net.minecraft.server.network.ServerGamePacketListenerImpl$EntityInteraction
+ net.minecraft.server.network.ServerHandshakePacketListenerImpl
- net.minecraft.server.network.ServerHandshakePacketListenerImpl$1
+ net.minecraft.server.network.ServerLoginPacketListenerImpl
- net.minecraft.server.network.ServerLoginPacketListenerImpl$1
+ net.minecraft.server.network.ServerLoginPacketListenerImpl$State
- net.minecraft.server.network.ServerPlayerConnection
+ net.minecraft.server.network.ServerStatusPacketListenerImpl
- net.minecraft.server.network.TextFilter
+ net.minecraft.server.network.TextFilter$1
- net.minecraft.server.network.TextFilterClient
+ net.minecraft.server.network.TextFilterClient$IgnoreStrategy
- net.minecraft.server.network.TextFilterClient$JoinOrLeaveEncoder
+ net.minecraft.server.network.TextFilterClient$MessageEncoder
- net.minecraft.server.network.TextFilterClient$PlayerContext
+ net.minecraft.server.network.TextFilterClient$RequestFailedException
+ net.minecraft.server.package-info
- net.minecraft.server.packs.AbstractPackResources
+ net.minecraft.server.packs.BuiltInMetadata
- net.minecraft.server.packs.CompositePackResources
+ net.minecraft.server.packs.DownloadCacheCleaner
- net.minecraft.server.packs.DownloadCacheCleaner$1
+ net.minecraft.server.packs.DownloadCacheCleaner$PathAndPriority
- net.minecraft.server.packs.DownloadCacheCleaner$PathAndTime
+ net.minecraft.server.packs.DownloadQueue
- net.minecraft.server.packs.DownloadQueue$BatchConfig
+ net.minecraft.server.packs.DownloadQueue$BatchResult
- net.minecraft.server.packs.DownloadQueue$DownloadRequest
+ net.minecraft.server.packs.DownloadQueue$FileInfoEntry
- net.minecraft.server.packs.DownloadQueue$LogEntry
+ net.minecraft.server.packs.FeatureFlagsMetadataSection
- net.minecraft.server.packs.FilePackResources
+ net.minecraft.server.packs.FilePackResources$FileResourcesSupplier
- net.minecraft.server.packs.FilePackResources$SharedZipFileAccess
- net.minecraft.server.packs.linkfs.DummyFileAttributes
+ net.minecraft.server.packs.linkfs.LinkFileSystem
- net.minecraft.server.packs.linkfs.LinkFileSystem$Builder
+ net.minecraft.server.packs.linkfs.LinkFileSystem$DirectoryEntry
+ net.minecraft.server.packs.linkfs.LinkFSFileStore
- net.minecraft.server.packs.linkfs.LinkFSPath
+ net.minecraft.server.packs.linkfs.LinkFSPath$1
- net.minecraft.server.packs.linkfs.LinkFSPath$2
+ net.minecraft.server.packs.linkfs.LinkFSPath$3
- net.minecraft.server.packs.linkfs.LinkFSProvider
+ net.minecraft.server.packs.linkfs.LinkFSProvider$1
- net.minecraft.server.packs.linkfs.LinkFSProvider$2
+ net.minecraft.server.packs.linkfs.package-info
- net.minecraft.server.packs.linkfs.PathContents
+ net.minecraft.server.packs.linkfs.PathContents$1
- net.minecraft.server.packs.linkfs.PathContents$2
+ net.minecraft.server.packs.linkfs.PathContents$DirectoryContents
- net.minecraft.server.packs.linkfs.PathContents$FileContents
- net.minecraft.server.packs.metadata.MetadataSectionSerializer
+ net.minecraft.server.packs.metadata.MetadataSectionType
- net.minecraft.server.packs.metadata.MetadataSectionType$1
- net.minecraft.server.packs.metadata.pack.package-info
+ net.minecraft.server.packs.metadata.pack.PackMetadataSection
+ net.minecraft.server.packs.metadata.package-info
+ net.minecraft.server.packs.OverlayMetadataSection
- net.minecraft.server.packs.OverlayMetadataSection$OverlayEntry
- net.minecraft.server.packs.package-info
+ net.minecraft.server.packs.PackLocationInfo
- net.minecraft.server.packs.PackResources
+ net.minecraft.server.packs.PackResources$ResourceOutput
- net.minecraft.server.packs.PackSelectionConfig
+ net.minecraft.server.packs.PackType
- net.minecraft.server.packs.PathPackResources
+ net.minecraft.server.packs.PathPackResources$PathResourcesSupplier
+ net.minecraft.server.packs.repository.BuiltInPackSource
- net.minecraft.server.packs.repository.BuiltInPackSource$1
+ net.minecraft.server.packs.repository.FolderRepositorySource
- net.minecraft.server.packs.repository.FolderRepositorySource$FolderPackDetector
+ net.minecraft.server.packs.repository.KnownPack
- net.minecraft.server.packs.repository.Pack
+ net.minecraft.server.packs.repository.Pack$Metadata
- net.minecraft.server.packs.repository.Pack$Position
+ net.minecraft.server.packs.repository.Pack$ResourcesSupplier
+ net.minecraft.server.packs.repository.package-info
- net.minecraft.server.packs.repository.PackCompatibility
+ net.minecraft.server.packs.repository.PackDetector
- net.minecraft.server.packs.repository.PackRepository
+ net.minecraft.server.packs.repository.PackSource
- net.minecraft.server.packs.repository.PackSource$1
+ net.minecraft.server.packs.repository.RepositorySource
- net.minecraft.server.packs.repository.ServerPacksSource
- net.minecraft.server.packs.resources.CloseableResourceManager
+ net.minecraft.server.packs.resources.FallbackResourceManager
- net.minecraft.server.packs.resources.FallbackResourceManager$1ResourceWithSourceAndIndex
+ net.minecraft.server.packs.resources.FallbackResourceManager$EntryStack
- net.minecraft.server.packs.resources.FallbackResourceManager$LeakedResourceWarningInputStream
+ net.minecraft.server.packs.resources.FallbackResourceManager$PackEntry
- net.minecraft.server.packs.resources.FallbackResourceManager$ResourceWithSource
+ net.minecraft.server.packs.resources.IoSupplier
- net.minecraft.server.packs.resources.MultiPackResourceManager
+ net.minecraft.server.packs.resources.package-info
+ net.minecraft.server.packs.resources.PreparableReloadListener
- net.minecraft.server.packs.resources.PreparableReloadListener$PreparationBarrier
+ net.minecraft.server.packs.resources.ProfiledReloadInstance
- net.minecraft.server.packs.resources.ProfiledReloadInstance$State
- net.minecraft.server.packs.resources.ReloadableResourceManager
+ net.minecraft.server.packs.resources.ReloadInstance
+ net.minecraft.server.packs.resources.Resource
- net.minecraft.server.packs.resources.ResourceFilterSection
+ net.minecraft.server.packs.resources.ResourceManager
- net.minecraft.server.packs.resources.ResourceManager$Empty
+ net.minecraft.server.packs.resources.ResourceManagerReloadListener
- net.minecraft.server.packs.resources.ResourceMetadata
+ net.minecraft.server.packs.resources.ResourceMetadata$1
- net.minecraft.server.packs.resources.ResourceMetadata$2
+ net.minecraft.server.packs.resources.ResourceMetadata$Builder
- net.minecraft.server.packs.resources.ResourceMetadata$Builder$1
+ net.minecraft.server.packs.resources.ResourceProvider
- net.minecraft.server.packs.resources.SimpleJsonResourceReloadListener
+ net.minecraft.server.packs.resources.SimplePreparableReloadListener
- net.minecraft.server.packs.resources.SimpleReloadInstance
+ net.minecraft.server.packs.resources.SimpleReloadInstance$1
- net.minecraft.server.packs.resources.SimpleReloadInstance$StateFactory
- net.minecraft.server.packs.VanillaPackResources
+ net.minecraft.server.packs.VanillaPackResourcesBuilder
+ net.minecraft.server.PlayerAdvancements
- net.minecraft.server.PlayerAdvancements$Data
- net.minecraft.server.players.BanListEntry
+ net.minecraft.server.players.GameProfileCache
- net.minecraft.server.players.GameProfileCache$1
+ net.minecraft.server.players.GameProfileCache$GameProfileInfo
- net.minecraft.server.players.IpBanList
+ net.minecraft.server.players.IpBanListEntry
- net.minecraft.server.players.OldUsersConverter
+ net.minecraft.server.players.OldUsersConverter$1
- net.minecraft.server.players.OldUsersConverter$2
+ net.minecraft.server.players.OldUsersConverter$3
- net.minecraft.server.players.OldUsersConverter$4
+ net.minecraft.server.players.OldUsersConverter$5
- net.minecraft.server.players.OldUsersConverter$ConversionError
- net.minecraft.server.players.package-info
+ net.minecraft.server.players.PlayerList
- net.minecraft.server.players.PlayerList$1
+ net.minecraft.server.players.ServerOpList
- net.minecraft.server.players.ServerOpListEntry
+ net.minecraft.server.players.SleepStatus
- net.minecraft.server.players.StoredUserEntry
+ net.minecraft.server.players.StoredUserList
- net.minecraft.server.players.UserBanList
+ net.minecraft.server.players.UserBanListEntry
- net.minecraft.server.players.UserWhiteList
+ net.minecraft.server.players.UserWhiteListEntry
+ net.minecraft.server.rcon.NetworkDataOutputStream
- net.minecraft.server.rcon.package-info
- net.minecraft.server.rcon.PktUtils
+ net.minecraft.server.rcon.RconConsoleSource
+ net.minecraft.server.rcon.thread.GenericThread
- net.minecraft.server.rcon.thread.package-info
- net.minecraft.server.rcon.thread.QueryThreadGs4
+ net.minecraft.server.rcon.thread.QueryThreadGs4$RequestChallenge
- net.minecraft.server.rcon.thread.RconClient
+ net.minecraft.server.rcon.thread.RconThread
+ net.minecraft.server.RegistryLayer
- net.minecraft.server.ReloadableServerRegistries
+ net.minecraft.server.ReloadableServerRegistries$EmptyTagLookupWrapper
- net.minecraft.server.ReloadableServerRegistries$Holder
+ net.minecraft.server.ReloadableServerResources
- net.minecraft.server.ReloadableServerResources$ConfigurableRegistryLookup
+ net.minecraft.server.ReloadableServerResources$ConfigurableRegistryLookup$1
- net.minecraft.server.ReloadableServerResources$MissingTagAccessPolicy
+ net.minecraft.server.RunningOnDifferentThreadException
- net.minecraft.server.ServerAdvancementManager
+ net.minecraft.server.ServerFunctionLibrary
- net.minecraft.server.ServerFunctionManager
+ net.minecraft.server.ServerInfo
- net.minecraft.server.ServerInterface
+ net.minecraft.server.ServerScoreboard
- net.minecraft.server.ServerScoreboard$Method
+ net.minecraft.server.ServerTickRateManager
- net.minecraft.server.Services
+ net.minecraft.server.TickTask
- net.minecraft.server.WorldLoader
+ net.minecraft.server.WorldLoader$DataLoadContext
- net.minecraft.server.WorldLoader$DataLoadOutput
+ net.minecraft.server.WorldLoader$InitConfig
- net.minecraft.server.WorldLoader$PackConfig
+ net.minecraft.server.WorldLoader$ResultFactory
- net.minecraft.server.WorldLoader$WorldDataSupplier
+ net.minecraft.server.WorldStem
+ net.minecraft.sounds.Music
- net.minecraft.sounds.Musics
- net.minecraft.sounds.package-info
+ net.minecraft.sounds.SoundEvent
- net.minecraft.sounds.SoundEvents
+ net.minecraft.sounds.SoundSource
+ net.minecraft.stats.package-info
+ net.minecraft.stats.RecipeBook
- net.minecraft.stats.RecipeBookSettings
+ net.minecraft.stats.RecipeBookSettings$TypeSettings
- net.minecraft.stats.ServerRecipeBook
+ net.minecraft.stats.ServerStatsCounter
- net.minecraft.stats.Stat
+ net.minecraft.stats.StatFormatter
+ net.minecraft.stats.Stats
- net.minecraft.stats.StatsCounter
- net.minecraft.stats.StatType
- net.minecraft.tags.BannerPatternTags
+ net.minecraft.tags.BiomeTags
- net.minecraft.tags.BlockTags
+ net.minecraft.tags.CatVariantTags
- net.minecraft.tags.DamageTypeTags
- net.minecraft.util.datafix.fixes.EmptyItemInVillagerTradeFix
+ net.minecraft.util.datafix.fixes.EntityArmorStandSilentFix
- net.minecraft.util.datafix.fixes.EntityBlockStateFix
+ net.minecraft.util.datafix.fixes.EntityBrushableBlockFieldsRenameFix
- net.minecraft.util.datafix.fixes.EntityCatSplitFix
+ net.minecraft.util.datafix.fixes.EntityCodSalmonFix
- net.minecraft.util.datafix.fixes.EntityCustomNameToComponentFix
+ net.minecraft.util.datafix.fixes.EntityElderGuardianSplitFix
- net.minecraft.util.datafix.fixes.EntityEquipmentToArmorAndHandFix
+ net.minecraft.util.datafix.fixes.EntityGoatMissingStateFix
- net.minecraft.util.datafix.fixes.EntityHealthFix
+ net.minecraft.util.datafix.fixes.EntityHorseSaddleFix
- net.minecraft.util.datafix.fixes.EntityHorseSplitFix
+ net.minecraft.util.datafix.fixes.EntityIdFix
- net.minecraft.util.datafix.fixes.EntityItemFrameDirectionFix
+ net.minecraft.util.datafix.fixes.EntityMinecartIdentifiersFix
- net.minecraft.util.datafix.fixes.EntityPaintingFieldsRenameFix
+ net.minecraft.util.datafix.fixes.EntityPaintingItemFrameDirectionFix
- net.minecraft.util.datafix.fixes.EntityPaintingMotiveFix
+ net.minecraft.util.datafix.fixes.EntityProjectileOwnerFix
- net.minecraft.util.datafix.fixes.EntityPufferfishRenameFix
+ net.minecraft.util.datafix.fixes.EntityRavagerRenameFix
- net.minecraft.util.datafix.fixes.EntityRedundantChanceTagsFix
+ net.minecraft.util.datafix.fixes.EntityRenameFix
- net.minecraft.util.datafix.fixes.EntityRidingToPassengersFix
+ net.minecraft.util.datafix.fixes.EntityShulkerColorFix
- net.minecraft.util.datafix.fixes.EntityShulkerRotationFix
+ net.minecraft.util.datafix.fixes.EntitySkeletonSplitFix
- net.minecraft.util.datafix.fixes.EntityStringUuidFix
+ net.minecraft.util.datafix.fixes.EntityTheRenameningFix
- net.minecraft.util.datafix.fixes.EntityTippedArrowFix
+ net.minecraft.util.datafix.fixes.EntityUUIDFix
- net.minecraft.util.datafix.fixes.EntityVariantFix
+ net.minecraft.util.datafix.fixes.EntityWolfColorFix
- net.minecraft.util.datafix.fixes.EntityZombieSplitFix
+ net.minecraft.util.datafix.fixes.EntityZombieVillagerTypeFix
- net.minecraft.util.datafix.fixes.EntityZombifiedPiglinRenameFix
+ net.minecraft.util.datafix.fixes.FeatureFlagRemoveFix
- net.minecraft.util.datafix.fixes.FilteredBooksFix
+ net.minecraft.util.datafix.fixes.FilteredSignsFix
- net.minecraft.util.datafix.fixes.FixProjectileStoredItem
+ net.minecraft.util.datafix.fixes.FixProjectileStoredItem$SubFixer
- net.minecraft.util.datafix.fixes.ForcePoiRebuild
+ net.minecraft.util.datafix.fixes.FurnaceRecipeFix
- net.minecraft.util.datafix.fixes.GoatHornIdFix
+ net.minecraft.util.datafix.fixes.GossipUUIDFix
- net.minecraft.util.datafix.fixes.HeightmapRenamingFix
+ net.minecraft.util.datafix.fixes.HorseBodyArmorItemFix
- net.minecraft.util.datafix.fixes.IglooMetadataRemovalFix
+ net.minecraft.util.datafix.fixes.ItemBannerColorFix
- net.minecraft.util.datafix.fixes.ItemCustomNameToComponentFix
+ net.minecraft.util.datafix.fixes.ItemIdFix
- net.minecraft.util.datafix.fixes.ItemLoreFix
+ net.minecraft.util.datafix.fixes.ItemPotionFix
- net.minecraft.util.datafix.fixes.ItemRemoveBlockEntityTagFix
+ net.minecraft.util.datafix.fixes.ItemRenameFix
- net.minecraft.util.datafix.fixes.ItemRenameFix$1
+ net.minecraft.util.datafix.fixes.ItemShulkerBoxColorFix
- net.minecraft.util.datafix.fixes.ItemSpawnEggFix
- net.minecraft.util.datafix.fixes.ItemStackComponentizationFix
+ net.minecraft.util.datafix.fixes.ItemStackComponentizationFix$ItemStackData
+ net.minecraft.util.datafix.fixes.ItemStackComponentRemainderFix
- net.minecraft.util.datafix.fixes.ItemStackCustomNameToOverrideComponentFix
+ net.minecraft.util.datafix.fixes.ItemStackEnchantmentNamesFix
- net.minecraft.util.datafix.fixes.ItemStackMapIdFix
+ net.minecraft.util.datafix.fixes.ItemStackSpawnEggFix
- net.minecraft.util.datafix.fixes.ItemStackTagFix
+ net.minecraft.util.datafix.fixes.ItemStackTheFlatteningFix
- net.minecraft.util.datafix.fixes.ItemStackUUIDFix
+ net.minecraft.util.datafix.fixes.ItemWaterPotionFix
- net.minecraft.util.datafix.fixes.ItemWrittenBookPagesStrictJsonFix
+ net.minecraft.util.datafix.fixes.JigsawPropertiesFix
- net.minecraft.util.datafix.fixes.JigsawRotationFix
+ net.minecraft.util.datafix.fixes.LeavesFix
- net.minecraft.util.datafix.fixes.LeavesFix$LeavesSection
+ net.minecraft.util.datafix.fixes.LeavesFix$Section
- net.minecraft.util.datafix.fixes.LegacyDragonFightFix
+ net.minecraft.util.datafix.fixes.LevelDataGeneratorOptionsFix
- net.minecraft.util.datafix.fixes.LevelFlatGeneratorInfoFix
+ net.minecraft.util.datafix.fixes.LevelLegacyWorldGenSettingsFix
- net.minecraft.util.datafix.fixes.LevelUUIDFix
+ net.minecraft.util.datafix.fixes.LodestoneCompassComponentFix
- net.minecraft.util.datafix.fixes.MapBannerBlockPosFormatFix
+ net.minecraft.util.datafix.fixes.MapIdFix
- net.minecraft.util.datafix.fixes.MemoryExpiryDataFix
+ net.minecraft.util.datafix.fixes.MissingDimensionFix
- net.minecraft.util.datafix.fixes.MobEffectIdFix
+ net.minecraft.util.datafix.fixes.MobSpawnerEntityIdentifiersFix
- net.minecraft.util.datafix.fixes.NamedEntityFix
+ net.minecraft.util.datafix.fixes.NamedEntityWriteReadFix
- net.minecraft.util.datafix.fixes.NamespacedTypeRenameFix
+ net.minecraft.util.datafix.fixes.NewVillageFix
- net.minecraft.util.datafix.fixes.ObjectiveDisplayNameFix
+ net.minecraft.util.datafix.fixes.ObjectiveRenderTypeFix
- net.minecraft.util.datafix.fixes.OminousBannerBlockEntityRenameFix
+ net.minecraft.util.datafix.fixes.OminousBannerRenameFix
- net.minecraft.util.datafix.fixes.OptionsAccessibilityOnboardFix
+ net.minecraft.util.datafix.fixes.OptionsAddTextBackgroundFix
- net.minecraft.util.datafix.fixes.OptionsAmbientOcclusionFix
+ net.minecraft.util.datafix.fixes.OptionsForceVBOFix
- net.minecraft.util.datafix.fixes.OptionsKeyLwjgl3Fix
+ net.minecraft.util.datafix.fixes.OptionsKeyTranslationFix
- net.minecraft.util.datafix.fixes.OptionsLowerCaseLanguageFix
+ net.minecraft.util.datafix.fixes.OptionsProgrammerArtFix
- net.minecraft.util.datafix.fixes.OptionsRenameFieldFix
+ net.minecraft.util.datafix.fixes.OverreachingTickFix
- net.minecraft.util.datafix.fixes.ParticleUnflatteningFix
+ net.minecraft.util.datafix.schemas.package-info
- net.minecraft.util.datafix.schemas.V3825
+ net.minecraft.util.datafix.schemas.V501
- net.minecraft.util.datafix.schemas.V700
+ net.minecraft.util.datafix.schemas.V701
- net.minecraft.util.datafix.schemas.V702
+ net.minecraft.util.datafix.schemas.V703
- net.minecraft.util.datafix.schemas.V704
+ net.minecraft.util.datafix.schemas.V704$1
- net.minecraft.util.datafix.schemas.V705
+ net.minecraft.util.datafix.schemas.V705$1
- net.minecraft.util.datafix.schemas.V808
+ net.minecraft.util.datafix.schemas.V99
- net.minecraft.util.datafix.schemas.V99$1
- net.minecraft.util.debugchart.AbstractSampleLogger
+ net.minecraft.util.debugchart.DebugSampleSubscriptionTracker
- net.minecraft.util.debugchart.DebugSampleSubscriptionTracker$SubscriptionRequest
+ net.minecraft.util.debugchart.DebugSampleSubscriptionTracker$SubscriptionStartedAt
- net.minecraft.util.debugchart.LocalSampleLogger
+ net.minecraft.util.debugchart.RemoteDebugSampleType
- net.minecraft.util.debugchart.RemoteSampleLogger
+ net.minecraft.util.debugchart.SampleLogger
- net.minecraft.util.debugchart.SampleStorage
+ net.minecraft.util.debugchart.TpsDebugDimensions
- net.minecraft.util.eventlog.EventLogDirectory
+ net.minecraft.util.eventlog.EventLogDirectory$CompressedFile
- net.minecraft.util.eventlog.EventLogDirectory$File
+ net.minecraft.util.eventlog.EventLogDirectory$FileId
- net.minecraft.util.eventlog.EventLogDirectory$FileList
+ net.minecraft.util.eventlog.EventLogDirectory$RawFile
- net.minecraft.util.eventlog.JsonEventLog
+ net.minecraft.util.eventlog.JsonEventLog$1
- net.minecraft.util.eventlog.JsonEventLogReader
+ net.minecraft.util.eventlog.JsonEventLogReader$1
- net.minecraft.util.eventlog.package-info
+ net.minecraft.util.monitoring.jmx.MinecraftServerStatistics
- net.minecraft.util.monitoring.jmx.MinecraftServerStatistics$AttributeDescription
+ net.minecraft.util.monitoring.jmx.package-info
- net.minecraft.util.NullOps$NullMapBuilder
- net.minecraft.util.package-info
+ net.minecraft.util.parsing.package-info
- net.minecraft.util.parsing.packrat.Atom
+ net.minecraft.util.parsing.packrat.commands.Grammar
- net.minecraft.util.parsing.packrat.commands.package-info
- net.minecraft.util.parsing.packrat.commands.ResourceLocationParseRule
+ net.minecraft.util.parsing.packrat.commands.ResourceLookupRule
- net.minecraft.util.parsing.packrat.commands.ResourceSuggestion
+ net.minecraft.util.parsing.packrat.commands.StringReaderParserState
- net.minecraft.util.parsing.packrat.commands.StringReaderTerms
+ net.minecraft.util.parsing.packrat.commands.StringReaderTerms$TerminalCharacter
- net.minecraft.util.parsing.packrat.commands.StringReaderTerms$TerminalWord
+ net.minecraft.util.parsing.packrat.commands.TagParseRule
+ net.minecraft.util.parsing.packrat.Control
- net.minecraft.util.parsing.packrat.Dictionary
+ net.minecraft.util.parsing.packrat.ErrorCollector
- net.minecraft.util.parsing.packrat.ErrorCollector$LongestOnly
+ net.minecraft.util.parsing.packrat.ErrorEntry
+ net.minecraft.util.parsing.packrat.package-info
- net.minecraft.util.parsing.packrat.ParseState
+ net.minecraft.util.parsing.packrat.ParseState$CacheEntry
- net.minecraft.util.parsing.packrat.ParseState$CacheKey
+ net.minecraft.util.parsing.packrat.Rule
- net.minecraft.util.parsing.packrat.Rule$RuleAction
+ net.minecraft.util.parsing.packrat.Rule$SimpleRuleAction
- net.minecraft.util.parsing.packrat.Rule$WrappedTerm
+ net.minecraft.util.parsing.packrat.Scope
- net.minecraft.util.parsing.packrat.SuggestionSupplier
+ net.minecraft.util.parsing.packrat.Term
- net.minecraft.util.parsing.packrat.Term$1
+ net.minecraft.util.parsing.packrat.Term$2
- net.minecraft.util.parsing.packrat.Term$Alternative
+ net.minecraft.util.parsing.packrat.Term$Marker
- net.minecraft.util.parsing.packrat.Term$Maybe
+ net.minecraft.util.parsing.packrat.Term$Reference
- net.minecraft.util.parsing.packrat.Term$Sequence
- net.minecraft.util.profiling.ActiveProfiler
+ net.minecraft.util.profiling.ActiveProfiler$PathEntry
- net.minecraft.util.profiling.ContinuousProfiler
+ net.minecraft.util.profiling.EmptyProfileResults
- net.minecraft.util.profiling.FilledProfileResults
+ net.minecraft.util.profiling.FilledProfileResults$1
- net.minecraft.util.profiling.FilledProfileResults$CounterCollector
+ net.minecraft.util.profiling.InactiveProfiler
+ net.minecraft.util.profiling.jfr.callback.package-info
- net.minecraft.util.profiling.jfr.callback.ProfiledDuration
+ net.minecraft.util.profiling.jfr.Environment
- net.minecraft.util.profiling.jfr.event.ChunkGenerationEvent
+ net.minecraft.util.profiling.jfr.event.ChunkGenerationEvent$Fields
- net.minecraft.util.profiling.jfr.event.ChunkRegionIoEvent
+ net.minecraft.util.profiling.jfr.event.ChunkRegionIoEvent$Fields
- net.minecraft.util.profiling.jfr.event.ChunkRegionReadEvent
+ net.minecraft.util.profiling.jfr.event.ChunkRegionWriteEvent
- net.minecraft.util.profiling.jfr.event.NetworkSummaryEvent
+ net.minecraft.util.profiling.jfr.event.NetworkSummaryEvent$Fields
- net.minecraft.util.profiling.jfr.event.NetworkSummaryEvent$SumAggregation
- net.minecraft.util.profiling.jfr.event.package-info
+ net.minecraft.util.profiling.jfr.event.PacketEvent
- net.minecraft.util.profiling.jfr.event.PacketEvent$Fields
+ net.minecraft.util.profiling.jfr.event.PacketReceivedEvent
- net.minecraft.util.profiling.jfr.event.PacketSentEvent
+ net.minecraft.util.profiling.jfr.event.ServerTickTimeEvent
- net.minecraft.util.profiling.jfr.event.ServerTickTimeEvent$Fields
+ net.minecraft.util.profiling.jfr.event.WorldLoadFinishedEvent
- net.minecraft.util.profiling.jfr.JfrProfiler
+ net.minecraft.util.profiling.jfr.JfrProfiler$1
- net.minecraft.util.profiling.jfr.JvmProfiler
+ net.minecraft.util.profiling.jfr.JvmProfiler$NoOpProfiler
+ net.minecraft.util.profiling.jfr.package-info
- net.minecraft.util.profiling.jfr.parse.JfrStatsParser
+ net.minecraft.util.profiling.jfr.parse.JfrStatsParser$1
- net.minecraft.util.profiling.jfr.parse.JfrStatsParser$MutableCountAndSize
+ net.minecraft.util.profiling.jfr.parse.JfrStatsResult
- net.minecraft.util.profiling.jfr.parse.package-info
- net.minecraft.util.profiling.jfr.Percentiles
+ net.minecraft.util.profiling.jfr.serialize.JfrResultJsonSerializer
- net.minecraft.util.profiling.jfr.serialize.package-info
+ net.minecraft.util.profiling.jfr.stats.ChunkGenStat
- net.minecraft.util.profiling.jfr.stats.ChunkIdentification
+ net.minecraft.util.profiling.jfr.stats.CpuLoadStat
- net.minecraft.util.profiling.jfr.stats.FileIOStat
+ net.minecraft.util.profiling.jfr.stats.FileIOStat$Summary
- net.minecraft.util.profiling.jfr.stats.GcHeapStat
+ net.minecraft.util.profiling.jfr.stats.GcHeapStat$Summary
- net.minecraft.util.profiling.jfr.stats.GcHeapStat$Timing
+ net.minecraft.util.profiling.jfr.stats.IoSummary
- net.minecraft.util.profiling.jfr.stats.IoSummary$CountAndSize
+ net.minecraft.util.profiling.jfr.stats.package-info
+ net.minecraft.util.profiling.jfr.stats.PacketIdentification
- net.minecraft.util.profiling.jfr.stats.ThreadAllocationStat
+ net.minecraft.util.profiling.jfr.stats.ThreadAllocationStat$Summary
- net.minecraft.util.profiling.jfr.stats.TickTimeStat
+ net.minecraft.util.profiling.jfr.stats.TimedStat
- net.minecraft.util.profiling.jfr.stats.TimedStatSummary
+ net.minecraft.util.profiling.jfr.SummaryReporter
- net.minecraft.util.profiling.metrics.MetricCategory
+ net.minecraft.util.profiling.metrics.MetricSampler
- net.minecraft.util.profiling.metrics.MetricSampler$MetricSamplerBuilder
+ net.minecraft.util.profiling.metrics.MetricSampler$SamplerResult
- net.minecraft.util.profiling.metrics.MetricSampler$ThresholdTest
+ net.minecraft.util.profiling.metrics.MetricSampler$ValueIncreasedByPercentage
- net.minecraft.util.profiling.metrics.MetricsRegistry
+ net.minecraft.util.profiling.metrics.MetricsRegistry$AggregatedMetricSampler
- net.minecraft.util.profiling.metrics.MetricsSamplerProvider
- net.minecraft.util.profiling.metrics.package-info
+ net.minecraft.util.profiling.metrics.ProfilerMeasured
+ net.minecraft.util.profiling.metrics.profiling.ActiveMetricsRecorder
- net.minecraft.util.profiling.metrics.profiling.InactiveMetricsRecorder
+ net.minecraft.util.profiling.metrics.profiling.MetricsRecorder
- net.minecraft.util.profiling.metrics.profiling.package-info
- net.minecraft.util.profiling.metrics.profiling.ProfilerSamplerAdapter
+ net.minecraft.util.profiling.metrics.profiling.ServerMetricsSamplersProvider
- net.minecraft.util.profiling.metrics.profiling.ServerMetricsSamplersProvider$1
+ net.minecraft.util.profiling.metrics.profiling.ServerMetricsSamplersProvider$CpuStats
+ net.minecraft.util.profiling.metrics.storage.MetricsPersister
+ net.minecraft.util.profiling.metrics.storage.package-info
- net.minecraft.util.profiling.metrics.storage.RecordedDeviation
- net.minecraft.util.profiling.package-info
- net.minecraft.util.profiling.ProfileCollector
+ net.minecraft.util.profiling.ProfileResults
- net.minecraft.util.profiling.ProfilerFiller
+ net.minecraft.util.profiling.ProfilerFiller$1
- net.minecraft.util.profiling.ProfilerPathEntry
+ net.minecraft.util.profiling.ResultField
- net.minecraft.util.profiling.SingleTickProfiler
+ net.minecraft.util.random.package-info
+ net.minecraft.util.random.SimpleWeightedRandomList
- net.minecraft.util.random.SimpleWeightedRandomList$Builder
+ net.minecraft.util.random.Weight
- net.minecraft.util.random.WeightedEntry
+ net.minecraft.util.random.WeightedEntry$IntrusiveBase
- net.minecraft.util.random.WeightedEntry$Wrapper
+ net.minecraft.util.random.WeightedRandom
- net.minecraft.util.random.WeightedRandomList
- net.minecraft.util.thread.BlockableEventLoop
+ net.minecraft.util.thread.NamedThreadFactory
- net.minecraft.util.thread.package-info
- net.minecraft.util.thread.ProcessorHandle
+ net.minecraft.util.thread.ProcessorHandle$1
- net.minecraft.util.thread.ProcessorMailbox
+ net.minecraft.util.thread.ReentrantBlockableEventLoop
- net.minecraft.util.thread.StrictQueue
+ net.minecraft.util.thread.StrictQueue$FixedPriorityQueue
- net.minecraft.util.thread.StrictQueue$IntRunnable
+ net.minecraft.util.thread.StrictQueue$QueueStrictQueue
+ net.minecraft.util.valueproviders.BiasedToBottomInt
- net.minecraft.util.valueproviders.ClampedInt
+ net.minecraft.util.valueproviders.ClampedNormalFloat
- net.minecraft.util.valueproviders.ClampedNormalInt
+ net.minecraft.util.valueproviders.ConstantFloat
- net.minecraft.util.valueproviders.ConstantInt
+ net.minecraft.util.valueproviders.FloatProvider
- net.minecraft.util.valueproviders.FloatProviderType
+ net.minecraft.util.valueproviders.IntProvider
- net.minecraft.util.valueproviders.IntProviderType
+ net.minecraft.util.valueproviders.MultipliedFloats
+ net.minecraft.util.valueproviders.package-info
- net.minecraft.util.valueproviders.SampledFloat
+ net.minecraft.util.valueproviders.TrapezoidFloat
- net.minecraft.util.valueproviders.UniformFloat
+ net.minecraft.util.valueproviders.UniformInt
- net.minecraft.util.valueproviders.WeightedListInt
- net.minecraft.util.worldupdate.package-info
- net.minecraft.util.worldupdate.WorldUpgrader
+ net.minecraft.util.worldupdate.WorldUpgrader$AbstractUpgrader
- net.minecraft.util.worldupdate.WorldUpgrader$ChunkUpgrader
+ net.minecraft.util.worldupdate.WorldUpgrader$DimensionToUpgrade
- net.minecraft.util.worldupdate.WorldUpgrader$EntityUpgrader
+ net.minecraft.util.worldupdate.WorldUpgrader$FileToUpgrade
- net.minecraft.util.worldupdate.WorldUpgrader$PoiUpgrader
+ net.minecraft.util.worldupdate.WorldUpgrader$SimpleRegionStorageUpgrader
+ net.minecraft.world.BossEvent
- net.minecraft.world.BossEvent$BossBarColor
+ net.minecraft.world.BossEvent$BossBarOverlay
- net.minecraft.world.Clearable
+ net.minecraft.world.CompoundContainer
- net.minecraft.world.Container
+ net.minecraft.world.ContainerHelper
- net.minecraft.world.ContainerListener
+ net.minecraft.world.Containers
- net.minecraft.world.damagesource.CombatEntry
+ net.minecraft.world.damagesource.CombatRules
- net.minecraft.world.damagesource.CombatTracker
+ net.minecraft.world.damagesource.DamageEffects
- net.minecraft.world.damagesource.DamageScaling
+ net.minecraft.world.damagesource.DamageSource
- net.minecraft.world.damagesource.DamageSource$1
+ net.minecraft.world.damagesource.DamageSources
- net.minecraft.world.damagesource.DamageType
+ net.minecraft.world.damagesource.DamageTypes
- net.minecraft.world.damagesource.DeathMessageType
+ net.minecraft.world.damagesource.FallLocation
- net.minecraft.world.damagesource.package-info
- net.minecraft.world.Difficulty
+ net.minecraft.world.DifficultyInstance
+ net.minecraft.world.effect.AbsorptionMobEffect
- net.minecraft.world.effect.BadOmenMobEffect
+ net.minecraft.world.effect.HealOrHarmMobEffect
- net.minecraft.world.effect.HungerMobEffect
+ net.minecraft.world.effect.InfestedMobEffect
- net.minecraft.world.effect.InstantenousMobEffect
+ net.minecraft.world.effect.MobEffect
- net.minecraft.world.effect.MobEffect$AttributeTemplate
+ net.minecraft.world.effect.MobEffectCategory
- net.minecraft.world.effect.MobEffectInstance
+ net.minecraft.world.effect.MobEffectInstance$BlendState
- net.minecraft.world.effect.MobEffectInstance$Details
- net.minecraft.world.effect.MobEffects
+ net.minecraft.world.effect.MobEffectUtil
+ net.minecraft.world.effect.OozingMobEffect
+ net.minecraft.world.effect.package-info
- net.minecraft.world.effect.PoisonMobEffect
+ net.minecraft.world.effect.RaidOmenMobEffect
- net.minecraft.world.effect.RegenerationMobEffect
+ net.minecraft.world.effect.SaturationMobEffect
- net.minecraft.world.effect.WeavingMobEffect
+ net.minecraft.world.effect.WindChargedMobEffect
- net.minecraft.world.effect.WitherMobEffect
- net.minecraft.world.entity.AgeableMob
+ net.minecraft.world.entity.AgeableMob$AgeableMobGroupData
- net.minecraft.world.entity.AnimationState
+ net.minecraft.world.entity.AreaEffectCloud
- net.minecraft.world.entity.Attackable
+ net.minecraft.world.entity.Crackiness
- net.minecraft.world.entity.Crackiness$Level
+ net.minecraft.world.entity.decoration.ItemFrame$2
- net.minecraft.world.entity.decoration.LeashFenceKnotEntity
- net.minecraft.world.entity.decoration.package-info
+ net.minecraft.world.entity.decoration.Painting
- net.minecraft.world.entity.decoration.PaintingVariant
+ net.minecraft.world.entity.decoration.PaintingVariants
+ net.minecraft.world.entity.Display
- net.minecraft.world.entity.Display$BillboardConstraints
+ net.minecraft.world.entity.Display$BlockDisplay
- net.minecraft.world.entity.Display$BlockDisplay$BlockRenderState
+ net.minecraft.world.entity.Display$ColorInterpolator
- net.minecraft.world.entity.Display$FloatInterpolator
+ net.minecraft.world.entity.Display$GenericInterpolator
- net.minecraft.world.entity.Display$IntInterpolator
+ net.minecraft.world.entity.Display$ItemDisplay
- net.minecraft.world.entity.EquipmentUser
+ net.minecraft.world.entity.ExperienceOrb
- net.minecraft.world.entity.FlyingMob
+ net.minecraft.world.entity.GlowSquid
- net.minecraft.world.entity.HasCustomInventoryScreen
+ net.minecraft.world.entity.HumanoidArm
- net.minecraft.world.entity.Interaction
+ net.minecraft.world.entity.Interaction$PlayerAction
+ net.minecraft.world.entity.item.FallingBlockEntity
- net.minecraft.world.entity.item.ItemEntity
+ net.minecraft.world.entity.item.ItemEntity$1
- net.minecraft.world.entity.ItemBasedSteering
+ net.minecraft.world.entity.ItemSteerable
- net.minecraft.world.entity.LerpingModel
+ net.minecraft.world.entity.LightningBolt
- net.minecraft.world.entity.LivingEntity
+ net.minecraft.world.entity.LivingEntity$1
- net.minecraft.world.entity.LivingEntity$Fallsounds
+ net.minecraft.world.entity.Marker
- net.minecraft.world.entity.Mob
+ net.minecraft.world.entity.Mob$1
- net.minecraft.world.entity.MobCategory
+ net.minecraft.world.entity.MobSpawnType
- net.minecraft.world.entity.MoverType
+ net.minecraft.world.entity.NeutralMob
- net.minecraft.world.entity.OminousItemSpawner
+ net.minecraft.world.entity.OwnableEntity
- net.minecraft.world.entity.PathfinderMob
+ net.minecraft.world.entity.PlayerRideable
- net.minecraft.world.entity.PlayerRideableJumping
+ net.minecraft.world.entity.Pose
- net.minecraft.world.entity.PowerableMob
+ net.minecraft.world.entity.RelativeMovement
- net.minecraft.world.entity.ReputationEventHandler
+ net.minecraft.world.entity.Saddleable
- net.minecraft.world.entity.Shearable
+ net.minecraft.world.entity.SlotAccess
- net.minecraft.world.entity.SlotAccess$1
+ net.minecraft.world.entity.SlotAccess$2
- net.minecraft.world.entity.SlotAccess$3
- net.minecraft.world.InteractionHand
+ net.minecraft.world.InteractionResult
- net.minecraft.world.InteractionResultHolder
+ net.minecraft.world.item.alchemy.Potion
- net.minecraft.world.item.alchemy.PotionBrewing
+ net.minecraft.world.item.Items
- net.minecraft.world.item.ItemStackLinkedSet
+ net.minecraft.world.item.ItemStackLinkedSet$1
- net.minecraft.world.item.ItemUtils
- net.minecraft.world.item.KnowledgeBookItem
+ net.minecraft.world.item.LeadItem
- net.minecraft.world.item.LingeringPotionItem
+ net.minecraft.world.item.MaceItem
- net.minecraft.world.item.MapItem
+ net.minecraft.world.item.MapItem$1
- net.minecraft.world.item.MilkBucketItem
+ net.minecraft.world.item.MinecartItem
- net.minecraft.world.item.MinecartItem$1
+ net.minecraft.world.item.MobBucketItem
- net.minecraft.world.item.NameTagItem
+ net.minecraft.world.item.OminousBottleItem
- net.minecraft.world.item.PickaxeItem
+ net.minecraft.world.item.PlaceOnWaterBlockItem
- net.minecraft.world.item.PlayerHeadItem
+ net.minecraft.world.item.PotionItem
- net.minecraft.world.item.ProjectileItem
+ net.minecraft.world.item.ProjectileItem$DispenseConfig
- net.minecraft.world.item.ProjectileItem$DispenseConfig$Builder
+ net.minecraft.world.item.ProjectileItem$PositionFunction
- net.minecraft.world.item.ProjectileWeaponItem
+ net.minecraft.world.item.Rarity
- net.minecraft.world.item.RecordItem
+ net.minecraft.world.item.SaddleItem
- net.minecraft.world.item.ScaffoldingBlockItem
+ net.minecraft.world.item.ServerItemCooldowns
- net.minecraft.world.item.ShearsItem
+ net.minecraft.world.item.ShieldItem
- net.minecraft.world.item.ShovelItem
+ net.minecraft.world.item.SignApplicator
- net.minecraft.world.item.SignItem
+ net.minecraft.world.item.SmithingTemplateItem
- net.minecraft.world.item.SnowballItem
+ net.minecraft.world.item.SolidBucketItem
- net.minecraft.world.item.SpawnEggItem
+ net.minecraft.world.item.SpectralArrowItem
- net.minecraft.world.item.SplashPotionItem
+ net.minecraft.world.item.SpyglassItem
- net.minecraft.world.item.StandingAndWallBlockItem
+ net.minecraft.world.item.SuspiciousStewItem
- net.minecraft.world.item.SwordItem
+ net.minecraft.world.item.ThrowablePotionItem
- net.minecraft.world.item.Tier
+ net.minecraft.world.item.TieredItem
- net.minecraft.world.item.Tiers
+ net.minecraft.world.item.TippedArrowItem
- net.minecraft.world.item.TooltipFlag
+ net.minecraft.world.item.TooltipFlag$Default
- net.minecraft.world.item.TridentItem
+ net.minecraft.world.item.UseAnim
- net.minecraft.world.item.WindChargeItem
+ net.minecraft.world.item.WritableBookItem
- net.minecraft.world.item.WrittenBookItem
+ net.minecraft.world.ItemInteractionResult
- net.minecraft.world.level.block.entity.EnchantingTableBlockEntity
+ net.minecraft.world.level.block.entity.EnchantmentTableBlockEntity
- net.minecraft.world.level.storage.loot.ContainerComponentManipulator
- net.minecraft.world.level.storage.loot.ContainerComponentManipulators$1
- net.minecraft.world.level.storage.loot.ContainerComponentManipulators$3
+ net.minecraft.world.level.storage.loot.entries.AlternativesEntry
- net.minecraft.world.level.storage.loot.entries.AlternativesEntry$Builder
+ net.minecraft.world.level.storage.loot.entries.ComposableEntryContainer
- net.minecraft.world.level.storage.loot.entries.CompositeEntryBase
+ net.minecraft.world.level.storage.loot.entries.CompositeEntryBase$CompositeEntryConstructor
- net.minecraft.world.level.storage.loot.entries.DynamicLoot
+ net.minecraft.world.level.storage.loot.entries.EmptyLootItem
- net.minecraft.world.level.storage.loot.entries.EntryGroup
+ net.minecraft.world.level.storage.loot.entries.EntryGroup$Builder
- net.minecraft.world.level.storage.loot.entries.LootItem
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntries
- net.minecraft.world.level.storage.loot.entries.LootPoolEntry
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntryContainer
- net.minecraft.world.level.storage.loot.entries.LootPoolEntryContainer$Builder
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntryType
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$1
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$Builder
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$DummyBuilder
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$EntryBase
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$EntryConstructor
- net.minecraft.world.level.storage.loot.entries.NestedLootTable
+ net.minecraft.world.level.storage.loot.entries.package-info
+ net.minecraft.world.level.storage.loot.entries.SequentialEntry
- net.minecraft.world.level.storage.loot.entries.SequentialEntry$Builder
+ net.minecraft.world.level.storage.loot.entries.TagEntry
- net.minecraft.world.level.storage.loot.entries.TagEntry$1
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$BinomialWithBonusCount
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$Formula
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$FormulaType
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$OreDrops
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$UniformBonusCount
- net.minecraft.world.level.storage.loot.functions.ApplyExplosionDecay
+ net.minecraft.world.level.storage.loot.functions.CopyBlockState
- net.minecraft.world.level.storage.loot.functions.CopyBlockState$Builder
+ net.minecraft.world.level.storage.loot.functions.CopyComponentsFunction
- net.minecraft.world.level.storage.loot.functions.CopyComponentsFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.CopyComponentsFunction$Source
- net.minecraft.world.level.storage.loot.functions.CopyCustomDataFunction
+ net.minecraft.world.level.storage.loot.functions.CopyCustomDataFunction$Builder
- net.minecraft.world.level.storage.loot.functions.CopyCustomDataFunction$CopyOperation
+ net.minecraft.world.level.storage.loot.functions.CopyCustomDataFunction$MergeStrategy
- net.minecraft.world.level.storage.loot.functions.CopyCustomDataFunction$MergeStrategy$1
+ net.minecraft.world.level.storage.loot.functions.CopyCustomDataFunction$MergeStrategy$2
- net.minecraft.world.level.storage.loot.functions.CopyCustomDataFunction$MergeStrategy$3
+ net.minecraft.world.level.storage.loot.functions.CopyNameFunction
- net.minecraft.world.level.storage.loot.functions.CopyNameFunction$NameSource
+ net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction
- net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction
- net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction
- net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.FillPlayerHead
- net.minecraft.world.level.storage.loot.functions.FilteredFunction
+ net.minecraft.world.level.storage.loot.functions.package-info
- net.minecraft.world.level.storage.loot.functions.SequenceFunction
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Modifier
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$ModifierBuilder
+ net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction
- net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetBookCoverFunction
- net.minecraft.world.level.storage.loot.functions.SetComponentsFunction
+ net.minecraft.world.level.storage.loot.functions.SetContainerContents
- net.minecraft.world.level.storage.loot.functions.SetContainerContents$Builder
+ net.minecraft.world.level.storage.loot.functions.SetContainerLootTable
- net.minecraft.world.level.storage.loot.functions.SetCustomDataFunction
- net.minecraft.world.level.storage.loot.functions.SetLoreFunction
+ net.minecraft.world.level.storage.loot.functions.SetLoreFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetNameFunction
+ net.minecraft.world.level.storage.loot.functions.SetNameFunction$Target
- net.minecraft.world.level.storage.loot.functions.SetOminousBottleAmplifierFunction
+ net.minecraft.world.level.storage.loot.functions.SetPotionFunction
- net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction
+ net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction$EffectEntry
+ net.minecraft.world.level.storage.loot.functions.SetWritableBookPagesFunction
- net.minecraft.world.level.storage.loot.functions.SetWrittenBookPagesFunction
+ net.minecraft.world.level.storage.loot.functions.SmeltItemFunction
- net.minecraft.world.level.storage.loot.functions.ToggleTooltips
+ net.minecraft.world.level.storage.loot.functions.ToggleTooltips$ComponentToggle
- net.minecraft.world.level.storage.loot.functions.ToggleTooltips$TooltipWither
+ net.minecraft.world.level.storage.loot.IntRange
- net.minecraft.world.level.storage.loot.IntRange$IntChecker
+ net.minecraft.world.level.storage.loot.IntRange$IntLimiter
- net.minecraft.world.level.storage.loot.LootContext
+ net.minecraft.world.level.storage.loot.LootContext$Builder
- net.minecraft.world.level.storage.loot.LootContext$EntityTarget
+ net.minecraft.world.level.storage.loot.LootContext$VisitedEntry
- net.minecraft.world.level.storage.loot.LootContextUser
+ net.minecraft.world.level.storage.loot.LootDataType
- net.minecraft.world.level.storage.loot.LootDataType$Validator
+ net.minecraft.world.level.storage.loot.LootParams
- net.minecraft.world.level.storage.loot.LootParams$Builder
+ net.minecraft.world.level.storage.loot.LootParams$DynamicDrop
- net.minecraft.world.level.storage.loot.LootPool
+ net.minecraft.world.level.storage.loot.LootPool$Builder
- net.minecraft.world.level.storage.loot.LootTable
+ net.minecraft.world.level.storage.loot.LootTable$Builder
- net.minecraft.world.level.storage.loot.package-info
+ net.minecraft.world.level.storage.loot.parameters.LootContextParam
+ net.minecraft.world.level.storage.loot.parameters.LootContextParams
- net.minecraft.world.level.storage.loot.parameters.LootContextParamSet
+ net.minecraft.world.level.storage.loot.parameters.LootContextParamSet$Builder
- net.minecraft.world.level.storage.loot.parameters.LootContextParamSets
- net.minecraft.world.level.storage.loot.parameters.package-info
+ net.minecraft.world.level.storage.loot.predicates.AllOfCondition
- net.minecraft.world.level.storage.loot.predicates.AllOfCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.AnyOfCondition
- net.minecraft.world.level.storage.loot.predicates.AnyOfCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.BonusLevelTableCondition
- net.minecraft.world.level.storage.loot.predicates.CompositeLootItemCondition
+ net.minecraft.world.level.storage.loot.predicates.CompositeLootItemCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.ConditionReference
+ net.minecraft.world.level.storage.loot.predicates.ConditionUserBuilder
- net.minecraft.world.level.storage.loot.predicates.DamageSourceCondition
+ net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition
- net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.ExplosionCondition
- net.minecraft.world.level.storage.loot.predicates.InvertedLootItemCondition
+ net.minecraft.world.level.storage.loot.predicates.LocationCheck
- net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.LootItemCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.LootItemConditions
- net.minecraft.world.level.storage.loot.predicates.LootItemConditionType
- net.minecraft.world.level.storage.loot.predicates.LootItemEntityPropertyCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemKilledByPlayerCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceWithLootingCondition
- net.minecraft.world.level.storage.loot.predicates.MatchTool
- net.minecraft.world.level.storage.loot.predicates.package-info
+ net.minecraft.world.level.storage.loot.predicates.TimeCheck
- net.minecraft.world.level.storage.loot.predicates.TimeCheck$Builder
+ net.minecraft.world.level.storage.loot.predicates.ValueCheckCondition
- net.minecraft.world.level.storage.loot.predicates.WeatherCheck
+ net.minecraft.world.level.storage.loot.predicates.WeatherCheck$Builder
+ net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider
- net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$1
+ net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$2
- net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$Getter
+ net.minecraft.world.level.storage.loot.providers.nbt.LootNbtProviderType
- net.minecraft.world.level.storage.loot.providers.nbt.NbtProvider
+ net.minecraft.world.level.storage.loot.providers.nbt.NbtProviders
+ net.minecraft.world.level.storage.loot.providers.nbt.package-info
- net.minecraft.world.level.storage.loot.providers.nbt.StorageNbtProvider
- net.minecraft.world.level.storage.loot.providers.number.BinomialDistributionGenerator
+ net.minecraft.world.level.storage.loot.providers.number.ConstantValue
- net.minecraft.world.level.storage.loot.providers.number.LootNumberProviderType
+ net.minecraft.world.level.storage.loot.providers.number.NumberProvider
- net.minecraft.world.level.storage.loot.providers.number.NumberProviders
- net.minecraft.world.level.storage.loot.providers.number.package-info
+ net.minecraft.world.level.storage.loot.providers.number.ScoreboardValue
- net.minecraft.world.level.storage.loot.providers.number.StorageValue
+ net.minecraft.world.level.storage.loot.providers.number.UniformGenerator
+ net.minecraft.world.level.storage.loot.providers.score.ContextScoreboardNameProvider
- net.minecraft.world.level.storage.loot.providers.score.FixedScoreboardNameProvider
+ net.minecraft.world.level.storage.loot.providers.score.LootScoreProviderType
- net.minecraft.world.level.storage.loot.providers.score.package-info
- net.minecraft.world.level.storage.loot.providers.score.ScoreboardNameProvider
+ net.minecraft.world.level.storage.loot.providers.score.ScoreboardNameProviders
- net.minecraft.world.level.storage.loot.ValidationContext
+ net.minecraft.world.level.storage.package-info
- net.minecraft.world.level.timers.FunctionCallback
+ net.minecraft.world.level.timers.FunctionCallback$Serializer
- net.minecraft.world.level.timers.FunctionTagCallback
+ net.minecraft.world.level.timers.FunctionTagCallback$Serializer
+ net.minecraft.world.level.timers.package-info
- net.minecraft.world.level.timers.TimerCallback
+ net.minecraft.world.level.timers.TimerCallback$Serializer
- net.minecraft.world.level.timers.TimerCallbacks
+ net.minecraft.world.level.timers.TimerQueue
- net.minecraft.world.level.timers.TimerQueue$Event
- net.minecraft.world.level.validation.ContentValidationException
+ net.minecraft.world.level.validation.DirectoryValidator
- net.minecraft.world.level.validation.DirectoryValidator$1
+ net.minecraft.world.level.validation.ForbiddenSymlinkInfo
+ net.minecraft.world.level.validation.package-info
- net.minecraft.world.level.validation.PathAllowList
+ net.minecraft.world.level.validation.PathAllowList$ConfigEntry
- net.minecraft.world.level.validation.PathAllowList$EntryType
- net.minecraft.world.LockCode
+ net.minecraft.world.MenuProvider
- net.minecraft.world.Nameable
- net.minecraft.world.package-info
+ net.minecraft.world.phys.AABB
- net.minecraft.world.phys.BlockHitResult
+ net.minecraft.world.phys.EntityHitResult
- net.minecraft.world.phys.HitResult
+ net.minecraft.world.phys.HitResult$Type
- net.minecraft.world.phys.package-info
+ net.minecraft.world.phys.shapes.ArrayVoxelShape
- net.minecraft.world.phys.shapes.ArrayVoxelShape$1
+ net.minecraft.world.phys.shapes.BitSetDiscreteVoxelShape
- net.minecraft.world.phys.shapes.BooleanOp
+ net.minecraft.world.phys.shapes.CollisionContext
- net.minecraft.world.phys.shapes.CubePointRange
+ net.minecraft.world.phys.shapes.CubeVoxelShape
- net.minecraft.world.phys.shapes.DiscreteCubeMerger
+ net.minecraft.world.phys.shapes.DiscreteVoxelShape
- net.minecraft.world.phys.shapes.DiscreteVoxelShape$IntFaceConsumer
+ net.minecraft.world.phys.shapes.DiscreteVoxelShape$IntLineConsumer
- net.minecraft.world.phys.shapes.EntityCollisionContext
+ net.minecraft.world.phys.shapes.EntityCollisionContext$1
- net.minecraft.world.phys.shapes.IdenticalMerger
+ net.minecraft.world.phys.shapes.IndexMerger
- net.minecraft.world.phys.shapes.IndexMerger$IndexConsumer
+ net.minecraft.world.phys.shapes.IndirectMerger
- net.minecraft.world.phys.shapes.NonOverlappingMerger
+ net.minecraft.world.phys.shapes.OffsetDoubleList
+ net.minecraft.world.phys.shapes.package-info
- net.minecraft.world.phys.shapes.Shapes
+ net.minecraft.world.phys.shapes.Shapes$DoubleLineConsumer
- net.minecraft.world.phys.shapes.SliceShape
+ net.minecraft.world.phys.shapes.SubShape
- net.minecraft.world.phys.shapes.VoxelShape
- net.minecraft.world.phys.Vec2
+ net.minecraft.world.phys.Vec3
- net.minecraft.world.RandomizableContainer
+ net.minecraft.world.RandomSequence
- net.minecraft.world.RandomSequences
+ net.minecraft.world.RandomSequences$DirtyMarkingRandomSource
+ net.minecraft.world.scores.criteria.ObjectiveCriteria
- net.minecraft.world.scores.criteria.ObjectiveCriteria$RenderType
+ net.minecraft.world.scores.criteria.package-info
- net.minecraft.world.scores.DisplaySlot
+ net.minecraft.world.scores.DisplaySlot$1
- net.minecraft.world.scores.Objective
- net.minecraft.world.scores.package-info
+ net.minecraft.world.scores.PlayerScoreEntry
- net.minecraft.world.scores.PlayerScores
+ net.minecraft.world.scores.PlayerTeam
- net.minecraft.world.scores.ReadOnlyScoreInfo
+ net.minecraft.world.scores.Score
- net.minecraft.world.scores.ScoreAccess
+ net.minecraft.world.scores.Scoreboard
- net.minecraft.world.scores.Scoreboard$1
+ net.minecraft.world.scores.ScoreboardSaveData
+ net.minecraft.world.scores.ScoreHolder
- net.minecraft.world.scores.ScoreHolder$1
+ net.minecraft.world.scores.ScoreHolder$2
- net.minecraft.world.scores.ScoreHolder$3
- net.minecraft.world.scores.Team
+ net.minecraft.world.scores.Team$CollisionRule
- net.minecraft.world.scores.Team$Visibility
+ net.minecraft.world.SimpleContainer
- net.minecraft.world.SimpleMenuProvider
+ net.minecraft.world.TickRateManager
+ net.minecraft.world.ticks.BlackholeTickAccess
- net.minecraft.world.ticks.BlackholeTickAccess$1
+ net.minecraft.world.ticks.BlackholeTickAccess$2
- net.minecraft.world.ticks.ContainerSingleItem
+ net.minecraft.world.ticks.ContainerSingleItem$BlockContainerSingleItem
- net.minecraft.world.ticks.LevelChunkTicks
+ net.minecraft.world.ticks.LevelTickAccess
- net.minecraft.world.ticks.LevelTicks
+ net.minecraft.world.ticks.LevelTicks$PosAndContainerConsumer
- net.minecraft.world.ticks.package-info
- net.minecraft.world.ticks.ProtoChunkTicks
+ net.minecraft.world.ticks.SavedTick
- net.minecraft.world.ticks.SavedTick$1
+ net.minecraft.world.ticks.ScheduledTick
- net.minecraft.world.ticks.ScheduledTick$1
+ net.minecraft.world.ticks.SerializableTickContainer
- net.minecraft.world.ticks.TickAccess
+ net.minecraft.world.ticks.TickContainerAccess
- net.minecraft.world.ticks.TickPriority
+ net.minecraft.world.ticks.WorldGenTickAccess
- net.minecraft.world.WorldlyContainer
+ net.minecraft.world.WorldlyContainerHolder
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











<h2>Client</h2>
<details>
<summary>
Classes
</summary>

```diff
+ com.mojang.blaze3d.audio.OggAudioStream
- net.minecraft.advancements.critereon.CollectionContentsPredicate$Multiple
- net.minecraft.advancements.critereon.CollectionContentsPredicate$Zero
- net.minecraft.advancements.critereon.CollectionCountsPredicate$Entry
- net.minecraft.advancements.critereon.CollectionCountsPredicate$Single
- net.minecraft.advancements.critereon.CollectionPredicate
- net.minecraft.advancements.critereon.ItemAttributeModifiersPredicate
- net.minecraft.advancements.critereon.ItemBundlePredicate
- net.minecraft.advancements.critereon.ItemFireworkExplosionPredicate$FireworkPredicate
- net.minecraft.advancements.critereon.ItemPotionsPredicate
+ net.minecraft.advancements.critereon.ItemPredicate
- net.minecraft.advancements.critereon.ItemPredicate$Builder
+ net.minecraft.advancements.critereon.ItemSubPredicate
- net.minecraft.advancements.critereon.ItemSubPredicate$Type
+ net.minecraft.advancements.critereon.ItemSubPredicates
- net.minecraft.advancements.critereon.ItemTrimPredicate
- net.minecraft.advancements.critereon.ItemWritableBookPredicate$PagePredicate
- net.minecraft.advancements.critereon.ItemWrittenBookPredicate$PagePredicate
- net.minecraft.client.sounds.FiniteAudioStream
- net.minecraft.client.sounds.JOrbisAudioStream
- net.minecraft.core.component.DataComponentMap$Builder
+ net.minecraft.core.component.DataComponentMap$Builder$SimpleMap
- net.minecraft.core.component.DataComponentPatch
+ net.minecraft.core.component.DataComponentPatch$1
- net.minecraft.core.component.DataComponentPatch$Builder
+ net.minecraft.core.component.DataComponentPatch$PatchKey
- net.minecraft.core.component.DataComponentPatch$SplitResult
+ net.minecraft.core.component.DataComponentPredicate
- net.minecraft.core.component.DataComponentPredicate$Builder
- net.minecraft.core.component.DataComponents
+ net.minecraft.core.component.DataComponentType
- net.minecraft.core.component.DataComponentType$Builder
+ net.minecraft.core.component.DataComponentType$Builder$SimpleType
- net.minecraft.core.component.package-info
+ net.minecraft.core.component.PatchedDataComponentMap
- net.minecraft.core.component.TypedDataComponent
+ net.minecraft.core.component.TypedDataComponent$1
+ net.minecraft.core.dispenser.BlockSource
- net.minecraft.core.dispenser.BoatDispenseItemBehavior
+ net.minecraft.core.dispenser.DefaultDispenseItemBehavior
- net.minecraft.core.dispenser.DispenseItemBehavior
+ net.minecraft.core.dispenser.DispenseItemBehavior$1
- net.minecraft.core.dispenser.DispenseItemBehavior$10
+ net.minecraft.core.dispenser.DispenseItemBehavior$11
- net.minecraft.core.dispenser.DispenseItemBehavior$12
+ net.minecraft.core.dispenser.DispenseItemBehavior$13
- net.minecraft.core.dispenser.DispenseItemBehavior$14
+ net.minecraft.core.dispenser.DispenseItemBehavior$15
- net.minecraft.core.dispenser.DispenseItemBehavior$16
+ net.minecraft.core.dispenser.DispenseItemBehavior$17
- net.minecraft.core.dispenser.DispenseItemBehavior$18
+ net.minecraft.core.dispenser.DispenseItemBehavior$2
- net.minecraft.core.dispenser.DispenseItemBehavior$3
+ net.minecraft.core.dispenser.DispenseItemBehavior$4
- net.minecraft.core.dispenser.DispenseItemBehavior$5
+ net.minecraft.core.dispenser.DispenseItemBehavior$6
- net.minecraft.core.dispenser.DispenseItemBehavior$7
+ net.minecraft.core.dispenser.DispenseItemBehavior$8
- net.minecraft.core.dispenser.DispenseItemBehavior$9
+ net.minecraft.core.dispenser.OptionalDispenseItemBehavior
+ net.minecraft.core.dispenser.package-info
- net.minecraft.core.dispenser.ProjectileDispenseBehavior
+ net.minecraft.core.dispenser.ShearsDispenseItemBehavior
- net.minecraft.core.dispenser.ShulkerBoxDispenseBehavior
- net.minecraft.core.package-info
+ net.minecraft.core.particles.BlockParticleOption
+ net.minecraft.core.particles.DustColorTransitionOptions
+ net.minecraft.core.particles.DustParticleOptionsBase
- net.minecraft.core.particles.ItemParticleOption
+ net.minecraft.core.particles.ItemParticleOption$1
- net.minecraft.core.particles.package-info
+ net.minecraft.core.particles.ParticleType
- net.minecraft.core.particles.ParticleTypes
+ net.minecraft.core.particles.ParticleTypes$1
- net.minecraft.core.particles.SculkChargeParticleOptions
+ net.minecraft.core.particles.SculkChargeParticleOptions$1
+ net.minecraft.core.particles.ShriekParticleOption$1
- net.minecraft.core.particles.SimpleParticleType
+ net.minecraft.core.particles.SimpleParticleType$1
+ net.minecraft.core.particles.VibrationParticleOption$1
+ net.minecraft.core.registries.BuiltInRegistries
- net.minecraft.core.registries.BuiltInRegistries$RegistryBootstrap
- net.minecraft.core.registries.package-info
+ net.minecraft.core.registries.Registries
+ net.minecraft.data.advancements.AdvancementProvider
- net.minecraft.data.advancements.AdvancementSubProvider
+ net.minecraft.data.advancements.package-info
- net.minecraft.data.advancements.packs.package-info
- net.minecraft.data.advancements.packs.UpdateOneTwentyOneAdvancementProvider
+ net.minecraft.data.advancements.packs.UpdateOneTwentyOneAdventureAdvancements
- net.minecraft.data.advancements.packs.VanillaAdvancementProvider
+ net.minecraft.data.advancements.packs.VanillaAdventureAdvancements
- net.minecraft.data.advancements.packs.VanillaHusbandryAdvancements
+ net.minecraft.data.advancements.packs.VanillaNetherAdvancements
- net.minecraft.data.advancements.packs.VanillaStoryAdvancements
+ net.minecraft.data.advancements.packs.VanillaTheEndAdvancements
+ net.minecraft.data.BlockFamilies
- net.minecraft.data.BlockFamily
+ net.minecraft.data.BlockFamily$Builder
- net.minecraft.data.BlockFamily$Variant
+ net.minecraft.data.CachedOutput
- net.minecraft.data.DataGenerator
+ net.minecraft.data.DataGenerator$PackGenerator
- net.minecraft.data.DataProvider
+ net.minecraft.data.DataProvider$Factory
- net.minecraft.data.HashCache
+ net.minecraft.data.HashCache$1
- net.minecraft.data.HashCache$CacheUpdater
+ net.minecraft.data.HashCache$ProviderCache
- net.minecraft.data.HashCache$ProviderCacheBuilder
+ net.minecraft.data.HashCache$UpdateFunction
- net.minecraft.data.HashCache$UpdateResult
+ net.minecraft.data.info.BiomeParametersDumpReport
- net.minecraft.data.info.BlockListReport
+ net.minecraft.data.info.CommandsReport
- net.minecraft.data.info.ItemListReport
- net.minecraft.data.info.package-info
+ net.minecraft.data.info.RegistryDumpReport
+ net.minecraft.data.loot.BlockLootSubProvider
- net.minecraft.data.loot.EntityLootSubProvider
+ net.minecraft.data.loot.LootTableProvider
- net.minecraft.data.loot.LootTableProvider$SubProviderEntry
+ net.minecraft.data.loot.LootTableSubProvider
- net.minecraft.data.loot.package-info
+ net.minecraft.data.loot.packs.package-info
+ net.minecraft.data.loot.packs.TradeRebalanceChestLoot
- net.minecraft.data.loot.packs.TradeRebalanceLootTableProvider
+ net.minecraft.data.loot.packs.UpdateOneTwentyOneBlockLoot
- net.minecraft.data.loot.packs.UpdateOneTwentyOneChestLoot
+ net.minecraft.data.loot.packs.UpdateOneTwentyOneEntityLoot
- net.minecraft.data.loot.packs.UpdateOneTwentyOneEquipmentLoot
+ net.minecraft.data.loot.packs.UpdateOneTwentyOneLootTableProvider
- net.minecraft.data.loot.packs.UpdateOneTwentyOneShearingLoot
+ net.minecraft.data.loot.packs.VanillaArchaeologyLoot
- net.minecraft.data.loot.packs.VanillaBlockLoot
+ net.minecraft.data.loot.packs.VanillaChestLoot
- net.minecraft.data.loot.packs.VanillaEntityLoot
+ net.minecraft.data.loot.packs.VanillaEquipmentLoot
- net.minecraft.data.loot.packs.VanillaFishingLoot
+ net.minecraft.data.loot.packs.VanillaGiftLoot
- net.minecraft.data.loot.packs.VanillaLootTableProvider
+ net.minecraft.data.loot.packs.VanillaPiglinBarterLoot
- net.minecraft.data.loot.packs.VanillaShearingLoot
+ net.minecraft.data.Main
+ net.minecraft.data.metadata.package-info
- net.minecraft.data.metadata.PackMetadataGenerator
- net.minecraft.data.models.BlockModelGenerators
+ net.minecraft.data.models.BlockModelGenerators$1
- net.minecraft.data.models.BlockModelGenerators$BlockEntityModelGenerator
+ net.minecraft.data.models.BlockModelGenerators$BlockFamilyProvider
- net.minecraft.data.models.BlockModelGenerators$BlockStateGeneratorSupplier
+ net.minecraft.data.models.BlockModelGenerators$BookSlotModelCacheKey
- net.minecraft.data.models.BlockModelGenerators$TintState
+ net.minecraft.data.models.BlockModelGenerators$WoodProvider
+ net.minecraft.data.models.blockstates.BlockStateGenerator
- net.minecraft.data.models.blockstates.Condition
+ net.minecraft.data.models.blockstates.Condition$CompositeCondition
- net.minecraft.data.models.blockstates.Condition$Operation
+ net.minecraft.data.models.blockstates.Condition$TerminalCondition
- net.minecraft.data.models.blockstates.MultiPartGenerator
+ net.minecraft.data.models.blockstates.MultiPartGenerator$ConditionalEntry
- net.minecraft.data.models.blockstates.MultiPartGenerator$Entry
+ net.minecraft.data.models.blockstates.MultiVariantGenerator
+ net.minecraft.data.models.blockstates.package-info
- net.minecraft.data.models.blockstates.PropertyDispatch
+ net.minecraft.data.models.blockstates.PropertyDispatch$C1
- net.minecraft.data.models.blockstates.PropertyDispatch$C2
+ net.minecraft.data.models.blockstates.PropertyDispatch$C3
- net.minecraft.data.models.blockstates.PropertyDispatch$C4
+ net.minecraft.data.models.blockstates.PropertyDispatch$C5
- net.minecraft.data.models.blockstates.PropertyDispatch$PentaFunction
+ net.minecraft.data.models.blockstates.PropertyDispatch$QuadFunction
- net.minecraft.data.models.blockstates.PropertyDispatch$TriFunction
+ net.minecraft.data.models.blockstates.Selector
- net.minecraft.data.models.blockstates.Variant
+ net.minecraft.data.models.blockstates.VariantProperties
- net.minecraft.data.models.blockstates.VariantProperties$Rotation
+ net.minecraft.data.models.blockstates.VariantProperty
- net.minecraft.data.models.blockstates.VariantProperty$Value
- net.minecraft.data.models.ItemModelGenerators
+ net.minecraft.data.models.ItemModelGenerators$TrimModelData
- net.minecraft.data.models.model.DelegatedModel
+ net.minecraft.data.models.model.ModelLocationUtils
- net.minecraft.data.models.model.ModelTemplate
+ net.minecraft.data.models.model.ModelTemplate$JsonFactory
- net.minecraft.data.models.model.ModelTemplates
+ net.minecraft.data.models.model.package-info
+ net.minecraft.data.models.model.TexturedModel
- net.minecraft.data.models.model.TexturedModel$Provider
+ net.minecraft.data.models.model.TextureMapping
- net.minecraft.data.models.model.TextureSlot
- net.minecraft.data.models.ModelProvider
- net.minecraft.data.models.package-info
+ net.minecraft.data.package-info
- net.minecraft.data.PackOutput
+ net.minecraft.data.PackOutput$PathProvider
- net.minecraft.data.PackOutput$Target
+ net.minecraft.data.recipes.package-info
- net.minecraft.data.recipes.packs.BundleRecipeProvider
- net.minecraft.data.recipes.packs.package-info
+ net.minecraft.data.recipes.packs.UpdateOneTwentyOneRecipeProvider
- net.minecraft.data.recipes.packs.VanillaRecipeProvider
+ net.minecraft.data.recipes.packs.VanillaRecipeProvider$TrimTemplate
- net.minecraft.data.recipes.RecipeBuilder
+ net.minecraft.data.recipes.RecipeBuilder$1
- net.minecraft.data.recipes.RecipeCategory
+ net.minecraft.data.recipes.RecipeOutput
- net.minecraft.data.recipes.RecipeProvider
+ net.minecraft.data.recipes.RecipeProvider$1
- net.minecraft.data.recipes.ShapedRecipeBuilder
+ net.minecraft.data.recipes.ShapelessRecipeBuilder
- net.minecraft.data.recipes.SimpleCookingRecipeBuilder
+ net.minecraft.data.recipes.SingleItemRecipeBuilder
- net.minecraft.data.recipes.SmithingTransformRecipeBuilder
+ net.minecraft.data.recipes.SmithingTrimRecipeBuilder
- net.minecraft.data.recipes.SpecialRecipeBuilder
+ net.minecraft.data.registries.package-info
+ net.minecraft.data.registries.RegistriesDatapackGenerator
- net.minecraft.data.registries.RegistryPatchGenerator
+ net.minecraft.data.registries.UpdateOneTwentyOneRegistries
- net.minecraft.data.registries.VanillaRegistries
- net.minecraft.data.structures.NbtToSnbt
+ net.minecraft.data.structures.package-info
+ net.minecraft.data.structures.SnbtDatafixer
- net.minecraft.data.structures.SnbtToNbt
+ net.minecraft.data.structures.SnbtToNbt$Filter
- net.minecraft.data.structures.SnbtToNbt$StructureConversionException
+ net.minecraft.data.structures.SnbtToNbt$TaskResult
- net.minecraft.data.structures.StructureUpdater
- net.minecraft.data.tags.BannerPatternTagsProvider
+ net.minecraft.data.tags.BiomeTagsProvider
- net.minecraft.data.tags.CatVariantTagsProvider
+ net.minecraft.data.tags.DamageTypeTagsProvider
- net.minecraft.data.tags.EnchantmentTagsProvider
- net.minecraft.data.tags.UpdateOneTwentyOneEnchantmentTagsProvider
+ net.minecraft.data.tags.UpdateOneTwentyOneEntityTypeTagsProvider
- net.minecraft.data.tags.UpdateOneTwentyOneItemTagsProvider
+ net.minecraft.data.tags.UpdateOneTwentyOneStructureTagsProvider
- net.minecraft.data.tags.VanillaBlockTagsProvider
- net.minecraft.network.codec.ByteBufCodecs$28
+ net.minecraft.network.codec.ByteBufCodecs$3
- net.minecraft.network.codec.ByteBufCodecs$4
+ net.minecraft.network.codec.ByteBufCodecs$5
- net.minecraft.network.codec.ByteBufCodecs$6
+ net.minecraft.network.codec.ByteBufCodecs$7
- net.minecraft.network.codec.ByteBufCodecs$8
+ net.minecraft.network.codec.ByteBufCodecs$9
- net.minecraft.network.codec.IdDispatchCodec
+ net.minecraft.network.codec.IdDispatchCodec$Builder
- net.minecraft.network.codec.IdDispatchCodec$Entry
+ net.minecraft.network.codec.package-info
+ net.minecraft.network.codec.StreamCodec
- net.minecraft.network.codec.StreamCodec$1
+ net.minecraft.network.codec.StreamCodec$10
- net.minecraft.network.codec.StreamCodec$11
+ net.minecraft.network.codec.StreamCodec$12
- net.minecraft.network.codec.StreamCodec$13
+ net.minecraft.network.codec.StreamCodec$2
- net.minecraft.network.codec.StreamCodec$3
+ net.minecraft.network.codec.StreamCodec$4
- net.minecraft.network.codec.StreamCodec$5
+ net.minecraft.network.codec.StreamCodec$6
- net.minecraft.network.codec.StreamCodec$7
+ net.minecraft.network.codec.StreamCodec$8
- net.minecraft.network.codec.StreamCodec$9
+ net.minecraft.network.codec.StreamCodec$CodecOperation
- net.minecraft.network.codec.StreamDecoder
+ net.minecraft.network.codec.StreamEncoder
- net.minecraft.network.codec.StreamMemberEncoder
- net.minecraft.network.package-info
+ net.minecraft.network.protocol.BundleDelimiterPacket
- net.minecraft.network.protocol.BundlePacket
+ net.minecraft.network.protocol.BundlerInfo
- net.minecraft.network.protocol.BundlerInfo$1
+ net.minecraft.network.protocol.BundlerInfo$1$1
- net.minecraft.network.protocol.BundlerInfo$Bundler
- net.minecraft.network.protocol.common.ClientboundCustomPayloadPacket
+ net.minecraft.network.protocol.common.ClientboundDisconnectPacket
- net.minecraft.network.protocol.common.ClientboundKeepAlivePacket
+ net.minecraft.network.protocol.common.ClientboundPingPacket
- net.minecraft.network.protocol.common.ClientboundResourcePackPopPacket
+ net.minecraft.network.protocol.common.ClientboundResourcePackPushPacket
- net.minecraft.network.protocol.common.ClientboundStoreCookiePacket
+ net.minecraft.network.protocol.common.ClientboundTransferPacket
- net.minecraft.network.protocol.common.ClientboundUpdateTagsPacket
+ net.minecraft.network.protocol.common.ClientCommonPacketListener
+ net.minecraft.network.protocol.common.CommonPacketTypes
+ net.minecraft.network.protocol.common.custom.BeeDebugPayload
- net.minecraft.network.protocol.common.custom.BeeDebugPayload$BeeInfo
+ net.minecraft.network.protocol.common.custom.BrainDebugPayload
- net.minecraft.network.protocol.common.custom.BrainDebugPayload$BrainDump
+ net.minecraft.network.protocol.common.custom.BrandPayload
- net.minecraft.network.protocol.common.custom.BreezeDebugPayload
+ net.minecraft.network.protocol.common.custom.BreezeDebugPayload$BreezeInfo
- net.minecraft.network.protocol.common.custom.CustomPacketPayload
+ net.minecraft.network.protocol.common.custom.CustomPacketPayload$1
- net.minecraft.network.protocol.common.custom.CustomPacketPayload$FallbackProvider
+ net.minecraft.network.protocol.common.custom.CustomPacketPayload$Type
- net.minecraft.network.protocol.common.custom.CustomPacketPayload$TypeAndCodec
+ net.minecraft.network.protocol.common.custom.DiscardedPayload
- net.minecraft.network.protocol.common.custom.GameEventDebugPayload
+ net.minecraft.network.protocol.common.custom.GameEventListenerDebugPayload
- net.minecraft.network.protocol.common.custom.GameTestAddMarkerDebugPayload
+ net.minecraft.network.protocol.common.custom.GameTestClearMarkersDebugPayload
- net.minecraft.network.protocol.common.custom.GoalDebugPayload
+ net.minecraft.network.protocol.common.custom.GoalDebugPayload$DebugGoal
- net.minecraft.network.protocol.common.custom.HiveDebugPayload
+ net.minecraft.network.protocol.common.custom.HiveDebugPayload$HiveInfo
- net.minecraft.network.protocol.common.custom.NeighborUpdatesDebugPayload
- net.minecraft.network.protocol.common.custom.package-info
+ net.minecraft.network.protocol.common.custom.PathfindingDebugPayload
- net.minecraft.network.protocol.common.custom.PoiAddedDebugPayload
+ net.minecraft.network.protocol.common.custom.PoiRemovedDebugPayload
- net.minecraft.network.protocol.common.custom.PoiTicketCountDebugPayload
+ net.minecraft.network.protocol.common.custom.RaidsDebugPayload
- net.minecraft.network.protocol.common.custom.StructuresDebugPayload
+ net.minecraft.network.protocol.common.custom.StructuresDebugPayload$PieceInfo
- net.minecraft.network.protocol.common.custom.VillageSectionsDebugPayload
+ net.minecraft.network.protocol.common.custom.WorldGenAttemptDebugPayload
+ net.minecraft.network.protocol.common.package-info
+ net.minecraft.network.protocol.common.ServerboundClientInformationPacket
- net.minecraft.network.protocol.common.ServerboundCustomPayloadPacket
+ net.minecraft.network.protocol.common.ServerboundKeepAlivePacket
- net.minecraft.network.protocol.common.ServerboundPongPacket
+ net.minecraft.network.protocol.common.ServerboundResourcePackPacket
- net.minecraft.network.protocol.common.ServerboundResourcePackPacket$Action
- net.minecraft.network.protocol.common.ServerCommonPacketListener
+ net.minecraft.network.protocol.configuration.ClientboundFinishConfigurationPacket
- net.minecraft.network.protocol.configuration.ClientboundRegistryDataPacket
+ net.minecraft.network.protocol.configuration.ClientboundResetChatPacket
- net.minecraft.network.protocol.configuration.ClientboundSelectKnownPacks
+ net.minecraft.network.protocol.configuration.ClientboundUpdateEnabledFeaturesPacket
- net.minecraft.network.protocol.configuration.ClientConfigurationPacketListener
- net.minecraft.network.protocol.configuration.ConfigurationPacketTypes
+ net.minecraft.network.protocol.configuration.ConfigurationProtocols
+ net.minecraft.network.protocol.configuration.package-info
+ net.minecraft.network.protocol.configuration.ServerboundFinishConfigurationPacket
- net.minecraft.network.protocol.configuration.ServerboundSelectKnownPacks
- net.minecraft.network.protocol.configuration.ServerConfigurationPacketListener
+ net.minecraft.network.protocol.cookie.ClientboundCookieRequestPacket
- net.minecraft.network.protocol.cookie.ClientCookiePacketListener
- net.minecraft.network.protocol.cookie.CookiePacketTypes
+ net.minecraft.network.protocol.cookie.package-info
- net.minecraft.network.protocol.cookie.ServerboundCookieResponsePacket
+ net.minecraft.network.protocol.cookie.ServerCookiePacketListener
+ net.minecraft.network.protocol.game.ClientboundAddEntityPacket
- net.minecraft.network.protocol.game.ClientboundAddExperienceOrbPacket
+ net.minecraft.network.protocol.game.ClientboundAnimatePacket
- net.minecraft.network.protocol.game.ClientboundAwardStatsPacket
+ net.minecraft.network.protocol.game.ClientboundBlockChangedAckPacket
- net.minecraft.network.protocol.game.ClientboundBlockDestructionPacket
+ net.minecraft.network.protocol.game.ClientboundBlockEntityDataPacket
- net.minecraft.network.protocol.game.ClientboundBlockEventPacket
+ net.minecraft.network.protocol.game.ClientboundBlockUpdatePacket
- net.minecraft.network.protocol.game.ClientboundBossEventPacket
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket$1
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$AddOperation
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket$Handler
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$Operation
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket$OperationType
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$UpdateNameOperation
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket$UpdateProgressOperation
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$UpdatePropertiesOperation
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket$UpdateStyleOperation
- net.minecraft.network.protocol.game.ClientboundBundleDelimiterPacket
+ net.minecraft.network.protocol.game.ClientboundBundlePacket
- net.minecraft.network.protocol.game.ClientboundChangeDifficultyPacket
+ net.minecraft.network.protocol.game.ClientboundChunkBatchFinishedPacket
- net.minecraft.network.protocol.game.ClientboundChunkBatchStartPacket
+ net.minecraft.network.protocol.game.ClientboundChunksBiomesPacket
- net.minecraft.network.protocol.game.ClientboundChunksBiomesPacket$ChunkBiomeData
+ net.minecraft.network.protocol.game.ClientboundClearTitlesPacket
- net.minecraft.network.protocol.game.ClientboundCommandsPacket
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket$ArgumentNodeStub
- net.minecraft.network.protocol.game.ClientboundCommandsPacket$Entry
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket$LiteralNodeStub
- net.minecraft.network.protocol.game.ClientboundCommandsPacket$NodeResolver
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket$NodeStub
- net.minecraft.network.protocol.game.ClientboundCommandSuggestionsPacket
+ net.minecraft.network.protocol.game.ClientboundCommandSuggestionsPacket$Entry
- net.minecraft.network.protocol.game.ClientboundContainerClosePacket
+ net.minecraft.network.protocol.game.ClientboundContainerSetContentPacket
- net.minecraft.network.protocol.game.ClientboundContainerSetDataPacket
+ net.minecraft.network.protocol.game.ClientboundContainerSetSlotPacket
- net.minecraft.network.protocol.game.ClientboundCooldownPacket
+ net.minecraft.network.protocol.game.ClientboundCustomChatCompletionsPacket
- net.minecraft.network.protocol.game.ClientboundCustomChatCompletionsPacket$Action
+ net.minecraft.network.protocol.game.ClientboundDamageEventPacket
- net.minecraft.network.protocol.game.ClientboundDebugSamplePacket
+ net.minecraft.network.protocol.game.ClientboundDeleteChatPacket
- net.minecraft.network.protocol.game.ClientboundDisguisedChatPacket
+ net.minecraft.network.protocol.game.ClientboundEntityEventPacket
- net.minecraft.network.protocol.game.ClientboundExplodePacket
+ net.minecraft.network.protocol.game.ClientboundForgetLevelChunkPacket
- net.minecraft.network.protocol.game.ClientboundGameEventPacket
+ net.minecraft.network.protocol.game.ClientboundGameEventPacket$Type
- net.minecraft.network.protocol.game.ClientboundHorseScreenOpenPacket
+ net.minecraft.network.protocol.game.ClientboundHurtAnimationPacket
- net.minecraft.network.protocol.game.ClientboundInitializeBorderPacket
+ net.minecraft.network.protocol.game.ClientboundLevelChunkPacketData
- net.minecraft.network.protocol.game.ClientboundLevelChunkPacketData$BlockEntityInfo
+ net.minecraft.network.protocol.game.ClientboundLevelChunkPacketData$BlockEntityTagOutput
- net.minecraft.network.protocol.game.ClientboundLevelChunkWithLightPacket
+ net.minecraft.network.protocol.game.ClientboundLevelEventPacket
- net.minecraft.network.protocol.game.ClientboundLevelParticlesPacket
+ net.minecraft.network.protocol.game.ClientboundLightUpdatePacket
- net.minecraft.network.protocol.game.ClientboundLightUpdatePacketData
+ net.minecraft.network.protocol.game.ClientboundLoginPacket
- net.minecraft.network.protocol.game.ClientboundMapItemDataPacket
+ net.minecraft.network.protocol.game.ClientboundMerchantOffersPacket
- net.minecraft.network.protocol.game.ClientboundMoveEntityPacket
+ net.minecraft.network.protocol.game.ClientboundMoveEntityPacket$Pos
- net.minecraft.network.protocol.game.ClientboundMoveEntityPacket$PosRot
+ net.minecraft.network.protocol.game.ClientboundMoveEntityPacket$Rot
- net.minecraft.network.protocol.game.ClientboundMoveVehiclePacket
+ net.minecraft.network.protocol.game.ClientboundOpenBookPacket
- net.minecraft.network.protocol.game.ClientboundOpenScreenPacket
+ net.minecraft.network.protocol.game.ClientboundOpenSignEditorPacket
- net.minecraft.network.protocol.game.ClientboundPlaceGhostRecipePacket
+ net.minecraft.network.protocol.game.ClientboundPlayerAbilitiesPacket
- net.minecraft.network.protocol.game.ClientboundPlayerChatPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerCombatEndPacket
- net.minecraft.network.protocol.game.ClientboundPlayerCombatEnterPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerCombatKillPacket
- net.minecraft.network.protocol.game.ClientboundPlayerInfoRemovePacket
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoUpdatePacket
- net.minecraft.network.protocol.game.ClientboundPlayerInfoUpdatePacket$Action
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoUpdatePacket$Action$Reader
- net.minecraft.network.protocol.game.ClientboundPlayerInfoUpdatePacket$Action$Writer
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoUpdatePacket$Entry
- net.minecraft.network.protocol.game.ClientboundPlayerInfoUpdatePacket$EntryBuilder
+ net.minecraft.network.protocol.game.ClientboundPlayerLookAtPacket
- net.minecraft.network.protocol.game.ClientboundPlayerPositionPacket
+ net.minecraft.network.protocol.game.ClientboundProjectilePowerPacket
- net.minecraft.network.protocol.game.ClientboundRecipePacket
+ net.minecraft.network.protocol.game.ClientboundRecipePacket$State
- net.minecraft.network.protocol.game.ClientboundRemoveEntitiesPacket
+ net.minecraft.network.protocol.game.ClientboundRemoveMobEffectPacket
- net.minecraft.network.protocol.game.ClientboundResetScorePacket
+ net.minecraft.network.protocol.game.ClientboundRespawnPacket
- net.minecraft.network.protocol.game.ClientboundRotateHeadPacket
+ net.minecraft.network.protocol.game.ClientboundSectionBlocksUpdatePacket
- net.minecraft.network.protocol.game.ClientboundSelectAdvancementsTabPacket
+ net.minecraft.network.protocol.game.ClientboundServerDataPacket
- net.minecraft.network.protocol.game.ClientboundSetActionBarTextPacket
+ net.minecraft.network.protocol.game.ClientboundSetBorderCenterPacket
- net.minecraft.network.protocol.game.ClientboundSetBorderLerpSizePacket
+ net.minecraft.network.protocol.game.ClientboundSetBorderSizePacket
- net.minecraft.network.protocol.game.ClientboundSetBorderWarningDelayPacket
+ net.minecraft.network.protocol.game.ClientboundSetBorderWarningDistancePacket
- net.minecraft.network.protocol.game.ClientboundSetCameraPacket
+ net.minecraft.network.protocol.game.ClientboundSetCarriedItemPacket
- net.minecraft.network.protocol.game.ClientboundSetChunkCacheCenterPacket
+ net.minecraft.network.protocol.game.ClientboundSetChunkCacheRadiusPacket
- net.minecraft.network.protocol.game.ClientboundSetDefaultSpawnPositionPacket
+ net.minecraft.network.protocol.game.ClientboundSetDisplayObjectivePacket
- net.minecraft.network.protocol.game.ClientboundSetEntityDataPacket
+ net.minecraft.network.protocol.game.ClientboundSetEntityLinkPacket
- net.minecraft.network.protocol.game.ClientboundSetEntityMotionPacket
+ net.minecraft.network.protocol.game.ClientboundSetEquipmentPacket
- net.minecraft.network.protocol.game.ClientboundSetExperiencePacket
+ net.minecraft.network.protocol.game.ClientboundSetHealthPacket
- net.minecraft.network.protocol.game.ClientboundSetObjectivePacket
+ net.minecraft.network.protocol.game.ClientboundSetPassengersPacket
- net.minecraft.network.protocol.game.ClientboundSetPlayerTeamPacket
+ net.minecraft.network.protocol.game.ClientboundSetPlayerTeamPacket$Action
- net.minecraft.network.protocol.game.ClientboundSetPlayerTeamPacket$Parameters
+ net.minecraft.network.protocol.game.ClientboundSetScorePacket
- net.minecraft.network.protocol.game.ClientboundSetSimulationDistancePacket
+ net.minecraft.network.protocol.game.ClientboundSetSubtitleTextPacket
- net.minecraft.network.protocol.game.ClientboundSetTimePacket
- net.minecraft.network.protocol.game.ClientboundSetTitlesAnimationPacket
+ net.minecraft.network.protocol.game.ClientboundSetTitleTextPacket
+ net.minecraft.network.protocol.game.ClientboundSoundEntityPacket
- net.minecraft.network.protocol.game.ClientboundSoundPacket
+ net.minecraft.network.protocol.game.ClientboundStartConfigurationPacket
- net.minecraft.network.protocol.game.ClientboundStopSoundPacket
+ net.minecraft.network.protocol.game.ClientboundSystemChatPacket
- net.minecraft.network.protocol.game.ClientboundTabListPacket
+ net.minecraft.network.protocol.game.ClientboundTagQueryPacket
- net.minecraft.network.protocol.game.ClientboundTakeItemEntityPacket
+ net.minecraft.network.protocol.game.ClientboundTeleportEntityPacket
- net.minecraft.network.protocol.game.ClientboundTickingStatePacket
+ net.minecraft.network.protocol.game.ClientboundTickingStepPacket
- net.minecraft.network.protocol.game.ClientboundUpdateAdvancementsPacket
+ net.minecraft.network.protocol.game.ClientboundUpdateAttributesPacket
- net.minecraft.network.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
+ net.minecraft.network.protocol.game.ClientboundUpdateMobEffectPacket
- net.minecraft.network.protocol.game.ClientboundUpdateRecipesPacket
- net.minecraft.network.protocol.game.ClientGamePacketListener
+ net.minecraft.network.protocol.game.CommonPlayerSpawnInfo
- net.minecraft.network.protocol.game.DebugEntityNameGenerator
+ net.minecraft.network.protocol.game.DebugPackets
- net.minecraft.network.protocol.game.GamePacketTypes
+ net.minecraft.network.protocol.game.GameProtocols
+ net.minecraft.network.protocol.game.package-info
- net.minecraft.network.protocol.game.ServerboundAcceptTeleportationPacket
+ net.minecraft.network.protocol.game.ServerboundBlockEntityTagQueryPacket
- net.minecraft.network.protocol.game.ServerboundChangeDifficultyPacket
+ net.minecraft.network.protocol.game.ServerboundChatAckPacket
- net.minecraft.network.protocol.game.ServerboundChatCommandPacket
+ net.minecraft.network.protocol.game.ServerboundChatCommandSignedPacket
- net.minecraft.network.protocol.game.ServerboundChatPacket
+ net.minecraft.network.protocol.game.ServerboundChatSessionUpdatePacket
- net.minecraft.network.protocol.game.ServerboundChunkBatchReceivedPacket
+ net.minecraft.network.protocol.game.ServerboundClientCommandPacket
- net.minecraft.network.protocol.game.ServerboundClientCommandPacket$Action
+ net.minecraft.network.protocol.game.ServerboundCommandSuggestionPacket
- net.minecraft.network.protocol.game.ServerboundConfigurationAcknowledgedPacket
+ net.minecraft.network.protocol.game.ServerboundContainerButtonClickPacket
- net.minecraft.network.protocol.game.ServerboundContainerClickPacket
+ net.minecraft.network.protocol.game.ServerboundContainerClosePacket
- net.minecraft.network.protocol.game.ServerboundContainerSlotStateChangedPacket
+ net.minecraft.network.protocol.game.ServerboundDebugSampleSubscriptionPacket
- net.minecraft.network.protocol.game.ServerboundEditBookPacket
+ net.minecraft.network.protocol.game.ServerboundEntityTagQueryPacket
- net.minecraft.network.protocol.game.ServerboundInteractPacket
+ net.minecraft.network.protocol.game.ServerboundInteractPacket$1
- net.minecraft.network.protocol.game.ServerboundInteractPacket$Action
+ net.minecraft.network.protocol.game.ServerboundInteractPacket$ActionType
- net.minecraft.network.protocol.game.ServerboundInteractPacket$Handler
+ net.minecraft.network.protocol.game.ServerboundInteractPacket$InteractionAction
- net.minecraft.network.protocol.game.ServerboundInteractPacket$InteractionAtLocationAction
+ net.minecraft.network.protocol.game.ServerboundJigsawGeneratePacket
- net.minecraft.network.protocol.game.ServerboundLockDifficultyPacket
+ net.minecraft.network.protocol.game.ServerboundMovePlayerPacket
- net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$Pos
+ net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$PosRot
- net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$Rot
+ net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$StatusOnly
- net.minecraft.network.protocol.game.ServerboundMoveVehiclePacket
+ net.minecraft.network.protocol.game.ServerboundPaddleBoatPacket
- net.minecraft.network.protocol.game.ServerboundPickItemPacket
+ net.minecraft.network.protocol.game.ServerboundPlaceRecipePacket
- net.minecraft.network.protocol.game.ServerboundPlayerAbilitiesPacket
+ net.minecraft.network.protocol.game.ServerboundPlayerActionPacket
- net.minecraft.network.protocol.game.ServerboundPlayerActionPacket$Action
+ net.minecraft.network.protocol.game.ServerboundPlayerCommandPacket
- net.minecraft.network.protocol.game.ServerboundPlayerCommandPacket$Action
+ net.minecraft.network.protocol.game.ServerboundPlayerInputPacket
- net.minecraft.network.protocol.game.ServerboundRecipeBookChangeSettingsPacket
+ net.minecraft.network.protocol.game.ServerboundRecipeBookSeenRecipePacket
- net.minecraft.network.protocol.game.ServerboundRenameItemPacket
+ net.minecraft.network.protocol.game.ServerboundSeenAdvancementsPacket
- net.minecraft.network.protocol.game.ServerboundSeenAdvancementsPacket$Action
+ net.minecraft.network.protocol.game.ServerboundSelectTradePacket
- net.minecraft.network.protocol.game.ServerboundSetBeaconPacket
+ net.minecraft.network.protocol.game.ServerboundSetCarriedItemPacket
- net.minecraft.network.protocol.game.ServerboundSetCommandBlockPacket
+ net.minecraft.network.protocol.game.ServerboundSetCommandMinecartPacket
- net.minecraft.network.protocol.game.ServerboundSetCreativeModeSlotPacket
+ net.minecraft.network.protocol.game.ServerboundSetJigsawBlockPacket
- net.minecraft.network.protocol.game.ServerboundSetStructureBlockPacket
+ net.minecraft.network.protocol.game.ServerboundSignUpdatePacket
- net.minecraft.network.protocol.game.ServerboundSwingPacket
+ net.minecraft.network.protocol.game.ServerboundTeleportToEntityPacket
- net.minecraft.network.protocol.game.ServerboundUseItemOnPacket
+ net.minecraft.network.protocol.game.ServerboundUseItemPacket
- net.minecraft.network.protocol.game.ServerGamePacketListener
+ net.minecraft.network.protocol.game.ServerPacketListener
- net.minecraft.network.protocol.game.VecDeltaCodec
- net.minecraft.network.protocol.handshake.ClientIntent
+ net.minecraft.network.protocol.handshake.ClientIntentionPacket
- net.minecraft.network.protocol.handshake.HandshakePacketTypes
+ net.minecraft.network.protocol.handshake.HandshakeProtocols
+ net.minecraft.network.protocol.handshake.package-info
- net.minecraft.network.protocol.handshake.ServerHandshakePacketListener
+ net.minecraft.network.protocol.login.ClientboundCustomQueryPacket
- net.minecraft.network.protocol.login.ClientboundGameProfilePacket
+ net.minecraft.network.protocol.login.ClientboundHelloPacket
- net.minecraft.network.protocol.login.ClientboundLoginCompressionPacket
+ net.minecraft.network.protocol.login.ClientboundLoginDisconnectPacket
- net.minecraft.network.protocol.login.ClientLoginPacketListener
+ net.minecraft.network.protocol.login.custom.CustomQueryAnswerPayload
- net.minecraft.network.protocol.login.custom.CustomQueryPayload
+ net.minecraft.network.protocol.login.custom.DiscardedQueryAnswerPayload
- net.minecraft.network.protocol.login.custom.DiscardedQueryPayload
+ net.minecraft.network.protocol.login.custom.package-info
- net.minecraft.network.protocol.login.LoginPacketTypes
+ net.minecraft.network.protocol.login.LoginProtocols
- net.minecraft.network.protocol.login.package-info
+ net.minecraft.network.protocol.login.ServerboundCustomQueryAnswerPacket
- net.minecraft.network.protocol.login.ServerboundHelloPacket
+ net.minecraft.network.protocol.login.ServerboundKeyPacket
- net.minecraft.network.protocol.login.ServerboundLoginAcknowledgedPacket
- net.minecraft.network.protocol.login.ServerLoginPacketListener
+ net.minecraft.network.protocol.package-info
+ net.minecraft.network.protocol.Packet
- net.minecraft.network.protocol.PacketFlow
+ net.minecraft.network.protocol.PacketType
- net.minecraft.network.protocol.PacketUtils
+ net.minecraft.network.protocol.ping.ClientboundPongResponsePacket
- net.minecraft.network.protocol.ping.ClientPongPacketListener
+ net.minecraft.network.protocol.ping.package-info
- net.minecraft.network.protocol.ping.PingPacketTypes
- net.minecraft.network.protocol.ping.ServerboundPingRequestPacket
+ net.minecraft.network.protocol.ping.ServerPingPacketListener
+ net.minecraft.network.protocol.ProtocolCodecBuilder
- net.minecraft.network.protocol.ProtocolInfoBuilder
+ net.minecraft.network.protocol.ProtocolInfoBuilder$CodecEntry
- net.minecraft.network.protocol.ProtocolInfoBuilder$Implementation
+ net.minecraft.network.protocol.status.ClientboundStatusResponsePacket
- net.minecraft.network.protocol.status.ClientStatusPacketListener
- net.minecraft.network.protocol.status.package-info
+ net.minecraft.network.protocol.status.ServerboundStatusRequestPacket
- net.minecraft.network.protocol.status.ServerStatus
+ net.minecraft.network.protocol.status.ServerStatus$Favicon
- net.minecraft.network.protocol.status.ServerStatus$Players
+ net.minecraft.network.protocol.status.ServerStatus$Version
- net.minecraft.network.protocol.status.ServerStatusPacketListener
- net.minecraft.network.protocol.status.StatusPacketTypes
+ net.minecraft.network.protocol.status.StatusProtocols
+ net.minecraft.network.syncher.EntityDataAccessor
- net.minecraft.network.syncher.EntityDataSerializer
+ net.minecraft.network.syncher.EntityDataSerializer$ForValueType
- net.minecraft.network.syncher.EntityDataSerializers
+ net.minecraft.network.syncher.EntityDataSerializers$1
- net.minecraft.network.syncher.EntityDataSerializers$2
+ net.minecraft.network.syncher.EntityDataSerializers$3
- net.minecraft.network.syncher.EntityDataSerializers$4
- net.minecraft.network.syncher.package-info
+ net.minecraft.network.syncher.SyncedDataHolder
- net.minecraft.network.syncher.SynchedEntityData
+ net.minecraft.network.syncher.SynchedEntityData$Builder
- net.minecraft.network.syncher.SynchedEntityData$DataItem
+ net.minecraft.network.syncher.SynchedEntityData$DataValue
+ net.minecraft.obfuscate.DontObfuscate
- net.minecraft.obfuscate.package-info
+ net.minecraft.package-info
- net.minecraft.realms.DisconnectedRealmsScreen
- net.minecraft.realms.package-info
+ net.minecraft.realms.RealmsConnect
- net.minecraft.realms.RealmsConnect$1
+ net.minecraft.realms.RealmsLabel
- net.minecraft.realms.RealmsObjectSelectionList
+ net.minecraft.realms.RealmsScreen
- net.minecraft.realms.RepeatedNarrator
+ net.minecraft.realms.RepeatedNarrator$Params
+ net.minecraft.recipebook.package-info
+ net.minecraft.recipebook.PlaceRecipe
- net.minecraft.recipebook.ServerPlaceRecipe
- net.minecraft.references.Blocks
+ net.minecraft.references.Items
- net.minecraft.resources.DelegatingOps
+ net.minecraft.resources.FileToIdConverter
- net.minecraft.resources.HolderSetCodec
- net.minecraft.resources.package-info
+ net.minecraft.resources.RegistryDataLoader
- net.minecraft.resources.RegistryDataLoader$1
+ net.minecraft.resources.RegistryDataLoader$Loader
- net.minecraft.resources.RegistryDataLoader$LoadingFunction
+ net.minecraft.resources.RegistryDataLoader$RegistryData
- net.minecraft.resources.RegistryFileCodec
+ net.minecraft.resources.RegistryFixedCodec
- net.minecraft.resources.RegistryOps
+ net.minecraft.resources.RegistryOps$1
- net.minecraft.resources.RegistryOps$2
+ net.minecraft.resources.RegistryOps$RegistryInfo
- net.minecraft.resources.RegistryOps$RegistryInfoLookup
+ net.minecraft.resources.ResourceKey
- net.minecraft.resources.ResourceKey$InternKey
+ net.minecraft.resources.ResourceLocation
- net.minecraft.resources.ResourceLocation$Dummy
+ net.minecraft.resources.ResourceLocation$Serializer
- net.minecraft.server.advancements.AdvancementVisibilityEvaluator
+ net.minecraft.server.advancements.AdvancementVisibilityEvaluator$Output
- net.minecraft.server.advancements.AdvancementVisibilityEvaluator$VisibilityRule
+ net.minecraft.server.advancements.package-info
+ net.minecraft.server.Bootstrap
- net.minecraft.server.Bootstrap$1
- net.minecraft.server.bossevents.CustomBossEvent
+ net.minecraft.server.bossevents.CustomBossEvents
- net.minecraft.server.bossevents.package-info
+ net.minecraft.server.ChainedJsonException
- net.minecraft.server.ChainedJsonException$Entry
+ net.minecraft.server.chase.ChaseClient
- net.minecraft.server.chase.ChaseClient$TeleportTarget
+ net.minecraft.server.chase.ChaseServer
- net.minecraft.server.chase.ChaseServer$PlayerPosition
+ net.minecraft.server.chase.package-info
- net.minecraft.server.commands.AdvancementCommands
+ net.minecraft.server.commands.AdvancementCommands$Action
- net.minecraft.server.commands.AdvancementCommands$Action$1
+ net.minecraft.server.commands.AdvancementCommands$Action$2
- net.minecraft.server.commands.AdvancementCommands$Mode
+ net.minecraft.server.commands.AttributeCommand
- net.minecraft.server.commands.BanIpCommands
+ net.minecraft.server.commands.BanListCommands
- net.minecraft.server.commands.BanPlayerCommands
+ net.minecraft.server.commands.BossBarCommands
- net.minecraft.server.commands.ChaseCommand
+ net.minecraft.server.commands.ClearInventoryCommands
- net.minecraft.server.commands.CloneCommands
+ net.minecraft.server.commands.CloneCommands$CloneBlockEntityInfo
- net.minecraft.server.commands.CloneCommands$CloneBlockInfo
+ net.minecraft.server.commands.CloneCommands$CommandFunction
- net.minecraft.server.commands.CloneCommands$DimensionAndPosition
+ net.minecraft.server.commands.CloneCommands$Mode
- net.minecraft.server.commands.DamageCommand
- net.minecraft.server.commands.data.BlockDataAccessor
+ net.minecraft.server.commands.data.BlockDataAccessor$1
- net.minecraft.server.commands.data.DataAccessor
+ net.minecraft.server.commands.data.DataCommands
- net.minecraft.server.commands.data.DataCommands$DataManipulator
+ net.minecraft.server.commands.data.DataCommands$DataManipulatorDecorator
- net.minecraft.server.commands.data.DataCommands$DataProvider
+ net.minecraft.server.commands.data.DataCommands$StringProcessor
- net.minecraft.server.commands.data.EntityDataAccessor
+ net.minecraft.server.commands.data.EntityDataAccessor$1
- net.minecraft.server.commands.data.package-info
- net.minecraft.server.commands.data.StorageDataAccessor
+ net.minecraft.server.commands.data.StorageDataAccessor$1
+ net.minecraft.server.commands.DataPackCommand
- net.minecraft.server.commands.DataPackCommand$Inserter
- net.minecraft.server.commands.DebugCommand
+ net.minecraft.server.commands.DebugCommand$TraceCustomExecutor
- net.minecraft.server.commands.DebugCommand$TraceCustomExecutor$1
+ net.minecraft.server.commands.DebugCommand$Tracer
- net.minecraft.server.commands.DebugConfigCommand
+ net.minecraft.server.commands.DebugMobSpawningCommand
- net.minecraft.server.commands.DebugPathCommand
+ net.minecraft.server.commands.DefaultGameModeCommands
+ net.minecraft.server.commands.DeOpCommands
- net.minecraft.server.commands.DifficultyCommand
+ net.minecraft.server.commands.EffectCommands
- net.minecraft.server.commands.EmoteCommands
+ net.minecraft.server.commands.EnchantCommand
- net.minecraft.server.commands.ExecuteCommand
+ net.minecraft.server.commands.ExecuteCommand$CommandGetter
- net.minecraft.server.commands.ExecuteCommand$CommandNumericPredicate
+ net.minecraft.server.commands.ExecuteCommand$CommandPredicate
- net.minecraft.server.commands.ExecuteCommand$ExecuteIfFunctionCustomModifier
+ net.minecraft.server.commands.ExecuteCommand$IntBiPredicate
- net.minecraft.server.commands.ExperienceCommand
+ net.minecraft.server.commands.ExperienceCommand$Type
- net.minecraft.server.commands.FillBiomeCommand
+ net.minecraft.server.commands.FillCommand
- net.minecraft.server.commands.FillCommand$Mode
+ net.minecraft.server.commands.ForceLoadCommand
- net.minecraft.server.commands.FunctionCommand
+ net.minecraft.server.commands.FunctionCommand$1
- net.minecraft.server.commands.FunctionCommand$1Accumulator
+ net.minecraft.server.commands.FunctionCommand$2
- net.minecraft.server.commands.FunctionCommand$3
+ net.minecraft.server.commands.FunctionCommand$4
- net.minecraft.server.commands.FunctionCommand$5
+ net.minecraft.server.commands.FunctionCommand$Callbacks
- net.minecraft.server.commands.FunctionCommand$FunctionCustomExecutor
+ net.minecraft.server.commands.GameModeCommand
- net.minecraft.server.commands.GameRuleCommand
+ net.minecraft.server.commands.GameRuleCommand$1
- net.minecraft.server.commands.GiveCommand
+ net.minecraft.server.commands.HelpCommand
- net.minecraft.server.commands.ItemCommands
+ net.minecraft.server.commands.JfrCommand
- net.minecraft.server.commands.KickCommand
+ net.minecraft.server.commands.KillCommand
- net.minecraft.server.commands.ListPlayersCommand
+ net.minecraft.server.commands.LocateCommand
- net.minecraft.server.commands.LootCommand
+ net.minecraft.server.commands.LootCommand$Callback
- net.minecraft.server.commands.LootCommand$DropConsumer
+ net.minecraft.server.commands.LootCommand$TailProvider
- net.minecraft.server.commands.MsgCommand
+ net.minecraft.server.commands.OpCommand
+ net.minecraft.server.commands.package-info
- net.minecraft.server.commands.PardonCommand
+ net.minecraft.server.commands.PardonIpCommand
- net.minecraft.server.commands.ParticleCommand
+ net.minecraft.server.commands.PerfCommand
- net.minecraft.server.commands.PlaceCommand
+ net.minecraft.server.commands.PlaySoundCommand
- net.minecraft.server.commands.PublishCommand
+ net.minecraft.server.commands.RaidCommand
- net.minecraft.server.commands.RandomCommand
+ net.minecraft.server.commands.RecipeCommand
- net.minecraft.server.commands.ReloadCommand
+ net.minecraft.server.commands.ResetChunksCommand
- net.minecraft.server.commands.ReturnCommand
+ net.minecraft.server.commands.ReturnCommand$ReturnFailCustomExecutor
- net.minecraft.server.commands.ReturnCommand$ReturnFromCommandCustomModifier
+ net.minecraft.server.commands.ReturnCommand$ReturnValueCustomExecutor
- net.minecraft.server.commands.RideCommand
+ net.minecraft.server.commands.SaveAllCommand
- net.minecraft.server.commands.SaveOffCommand
+ net.minecraft.server.commands.SaveOnCommand
- net.minecraft.server.commands.SayCommand
+ net.minecraft.server.commands.ScheduleCommand
- net.minecraft.server.commands.ScoreboardCommand
+ net.minecraft.server.commands.ScoreboardCommand$NumberFormatCommandExecutor
- net.minecraft.server.commands.SeedCommand
+ net.minecraft.server.commands.ServerPackCommand
- net.minecraft.server.commands.SetBlockCommand
+ net.minecraft.server.commands.SetBlockCommand$Filter
- net.minecraft.server.commands.SetBlockCommand$Mode
+ net.minecraft.server.commands.SetPlayerIdleTimeoutCommand
- net.minecraft.server.commands.SetSpawnCommand
+ net.minecraft.server.commands.SetWorldSpawnCommand
- net.minecraft.server.commands.SpawnArmorTrimsCommand
+ net.minecraft.server.commands.SpectateCommand
- net.minecraft.server.commands.SpreadPlayersCommand
+ net.minecraft.server.commands.SpreadPlayersCommand$Position
- net.minecraft.server.commands.StopCommand
+ net.minecraft.server.commands.StopSoundCommand
- net.minecraft.server.commands.SummonCommand
+ net.minecraft.server.commands.TagCommand
- net.minecraft.server.commands.TeamCommand
+ net.minecraft.server.commands.TeamMsgCommand
- net.minecraft.server.commands.TeleportCommand
+ net.minecraft.server.commands.TeleportCommand$LookAt
- net.minecraft.server.commands.TeleportCommand$LookAtEntity
+ net.minecraft.server.commands.TeleportCommand$LookAtPosition
- net.minecraft.server.commands.TellRawCommand
+ net.minecraft.server.commands.TickCommand
- net.minecraft.server.commands.TimeCommand
+ net.minecraft.server.commands.TitleCommand
- net.minecraft.server.commands.TransferCommand
+ net.minecraft.server.commands.TriggerCommand
- net.minecraft.server.commands.WardenSpawnTrackerCommand
+ net.minecraft.server.commands.WeatherCommand
- net.minecraft.server.commands.WhitelistCommand
+ net.minecraft.server.commands.WorldBorderCommand
+ net.minecraft.server.ConsoleInput
- net.minecraft.server.DebugLoggedPrintStream
- net.minecraft.server.dedicated.DedicatedPlayerList
+ net.minecraft.server.dedicated.DedicatedServer
- net.minecraft.server.dedicated.DedicatedServer$1
+ net.minecraft.server.dedicated.DedicatedServerProperties
- net.minecraft.server.dedicated.DedicatedServerProperties$WorldDimensionData
+ net.minecraft.server.dedicated.DedicatedServerSettings
- net.minecraft.server.dedicated.package-info
- net.minecraft.server.dedicated.ServerWatchdog
+ net.minecraft.server.dedicated.ServerWatchdog$1
- net.minecraft.server.dedicated.Settings
+ net.minecraft.server.dedicated.Settings$MutableValue
+ net.minecraft.server.Eula
+ net.minecraft.server.gui.MinecraftServerGui
- net.minecraft.server.gui.MinecraftServerGui$1
+ net.minecraft.server.gui.MinecraftServerGui$2
- net.minecraft.server.gui.package-info
- net.minecraft.server.gui.PlayerListComponent
+ net.minecraft.server.gui.StatsComponent
+ net.minecraft.server.level.BlockDestructionProgress
- net.minecraft.server.level.ChunkHolder
+ net.minecraft.server.level.ChunkHolder$ChunkSaveDebug
- net.minecraft.server.level.ChunkHolder$LevelChangeListener
+ net.minecraft.server.level.ChunkHolder$PlayerProvider
- net.minecraft.server.level.ChunkLevel
+ net.minecraft.server.level.ChunkLevel$1
- net.minecraft.server.level.ChunkMap
+ net.minecraft.server.level.ChunkMap$DistanceManager
- net.minecraft.server.level.ChunkMap$TrackedEntity
+ net.minecraft.server.level.ChunkResult
- net.minecraft.server.level.ChunkResult$Fail
+ net.minecraft.server.level.ChunkResult$Success
- net.minecraft.server.level.ChunkTaskPriorityQueue
+ net.minecraft.server.level.ChunkTaskPriorityQueueSorter
- net.minecraft.server.level.ChunkTaskPriorityQueueSorter$Message
+ net.minecraft.server.level.ChunkTaskPriorityQueueSorter$Release
- net.minecraft.server.level.ChunkTracker
+ net.minecraft.server.level.ChunkTrackingView
- net.minecraft.server.level.ChunkTrackingView$1
+ net.minecraft.server.level.ChunkTrackingView$Positioned
- net.minecraft.server.level.ClientInformation
+ net.minecraft.server.level.ColumnPos
- net.minecraft.server.level.DemoMode
+ net.minecraft.server.level.DistanceManager
- net.minecraft.server.level.DistanceManager$ChunkTicketTracker
+ net.minecraft.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
- net.minecraft.server.level.DistanceManager$PlayerTicketTracker
+ net.minecraft.server.level.FullChunkStatus
- net.minecraft.server.level.package-info
- net.minecraft.server.level.PlayerMap
+ net.minecraft.server.level.PlayerRespawnLogic
+ net.minecraft.server.level.progress.ChunkProgressListener
- net.minecraft.server.level.progress.ChunkProgressListenerFactory
+ net.minecraft.server.level.progress.LoggerChunkProgressListener
- net.minecraft.server.level.progress.package-info
- net.minecraft.server.level.progress.ProcessorChunkProgressListener
+ net.minecraft.server.level.progress.StoringChunkProgressListener
- net.minecraft.server.level.SectionTracker
+ net.minecraft.server.level.ServerBossEvent
- net.minecraft.server.level.ServerChunkCache
+ net.minecraft.server.level.ServerChunkCache$ChunkAndHolder
- net.minecraft.server.level.ServerChunkCache$MainThreadExecutor
+ net.minecraft.server.level.ServerEntity
- net.minecraft.server.level.ServerLevel
+ net.minecraft.server.level.ServerLevel$EntityCallbacks
- net.minecraft.server.level.ServerPlayer
+ net.minecraft.server.level.ServerPlayer$1
- net.minecraft.server.level.ServerPlayer$2
+ net.minecraft.server.level.ServerPlayerGameMode
- net.minecraft.server.level.ThreadedLevelLightEngine
+ net.minecraft.server.level.ThreadedLevelLightEngine$TaskType
- net.minecraft.server.level.Ticket
+ net.minecraft.server.level.TicketType
- net.minecraft.server.level.TickingTracker
+ net.minecraft.server.level.WorldGenRegion
- net.minecraft.server.LoggedPrintStream
+ net.minecraft.server.Main
- net.minecraft.server.Main$1
+ net.minecraft.server.MinecraftServer
- net.minecraft.server.MinecraftServer$1
+ net.minecraft.server.MinecraftServer$ReloadableResources
- net.minecraft.server.MinecraftServer$ServerResourcePackInfo
+ net.minecraft.server.MinecraftServer$TimeProfiler
- net.minecraft.server.MinecraftServer$TimeProfiler$1
+ net.minecraft.server.network.CommonListenerCookie
- net.minecraft.server.network.config.JoinWorldTask
+ net.minecraft.server.network.config.package-info
+ net.minecraft.server.network.config.ServerResourcePackConfigurationTask
- net.minecraft.server.network.config.SynchronizeRegistriesTask
- net.minecraft.server.network.ConfigurationTask
+ net.minecraft.server.network.ConfigurationTask$Type
- net.minecraft.server.network.Filterable
+ net.minecraft.server.network.FilteredText
- net.minecraft.server.network.LegacyProtocolUtils
+ net.minecraft.server.network.LegacyQueryHandler
- net.minecraft.server.network.MemoryServerHandshakePacketListenerImpl
- net.minecraft.server.network.package-info
+ net.minecraft.server.network.PlayerChunkSender
- net.minecraft.server.network.ServerCommonPacketListenerImpl
+ net.minecraft.server.network.ServerConfigurationPacketListenerImpl
- net.minecraft.server.network.ServerConnectionListener
+ net.minecraft.server.network.ServerConnectionListener$1
- net.minecraft.server.network.ServerConnectionListener$2
+ net.minecraft.server.network.ServerConnectionListener$LatencySimulator
- net.minecraft.server.network.ServerConnectionListener$LatencySimulator$DelayedMessage
+ net.minecraft.server.network.ServerGamePacketListenerImpl
- net.minecraft.server.network.ServerGamePacketListenerImpl$1
+ net.minecraft.server.network.ServerGamePacketListenerImpl$2
- net.minecraft.server.network.ServerGamePacketListenerImpl$EntityInteraction
+ net.minecraft.server.network.ServerHandshakePacketListenerImpl
- net.minecraft.server.network.ServerHandshakePacketListenerImpl$1
+ net.minecraft.server.network.ServerLoginPacketListenerImpl
- net.minecraft.server.network.ServerLoginPacketListenerImpl$1
+ net.minecraft.server.network.ServerLoginPacketListenerImpl$State
- net.minecraft.server.network.ServerPlayerConnection
+ net.minecraft.server.network.ServerStatusPacketListenerImpl
- net.minecraft.server.network.TextFilter
+ net.minecraft.server.network.TextFilter$1
- net.minecraft.server.network.TextFilterClient
+ net.minecraft.server.network.TextFilterClient$IgnoreStrategy
- net.minecraft.server.network.TextFilterClient$JoinOrLeaveEncoder
+ net.minecraft.server.network.TextFilterClient$MessageEncoder
- net.minecraft.server.network.TextFilterClient$PlayerContext
+ net.minecraft.server.network.TextFilterClient$RequestFailedException
+ net.minecraft.server.package-info
- net.minecraft.server.packs.AbstractPackResources
+ net.minecraft.server.packs.BuiltInMetadata
- net.minecraft.server.packs.CompositePackResources
+ net.minecraft.server.packs.DownloadCacheCleaner
- net.minecraft.server.packs.DownloadCacheCleaner$1
+ net.minecraft.server.packs.DownloadCacheCleaner$PathAndPriority
- net.minecraft.server.packs.DownloadCacheCleaner$PathAndTime
+ net.minecraft.server.packs.DownloadQueue
- net.minecraft.server.packs.DownloadQueue$BatchConfig
+ net.minecraft.server.packs.DownloadQueue$BatchResult
- net.minecraft.server.packs.DownloadQueue$DownloadRequest
+ net.minecraft.server.packs.DownloadQueue$FileInfoEntry
- net.minecraft.server.packs.DownloadQueue$LogEntry
+ net.minecraft.server.packs.FeatureFlagsMetadataSection
- net.minecraft.server.packs.FilePackResources
+ net.minecraft.server.packs.FilePackResources$FileResourcesSupplier
- net.minecraft.server.packs.FilePackResources$SharedZipFileAccess
- net.minecraft.server.packs.linkfs.DummyFileAttributes
+ net.minecraft.server.packs.linkfs.LinkFileSystem
- net.minecraft.server.packs.linkfs.LinkFileSystem$Builder
+ net.minecraft.server.packs.linkfs.LinkFileSystem$DirectoryEntry
+ net.minecraft.server.packs.linkfs.LinkFSFileStore
- net.minecraft.server.packs.linkfs.LinkFSPath
+ net.minecraft.server.packs.linkfs.LinkFSPath$1
- net.minecraft.server.packs.linkfs.LinkFSPath$2
+ net.minecraft.server.packs.linkfs.LinkFSPath$3
- net.minecraft.server.packs.linkfs.LinkFSProvider
+ net.minecraft.server.packs.linkfs.LinkFSProvider$1
- net.minecraft.server.packs.linkfs.LinkFSProvider$2
+ net.minecraft.server.packs.linkfs.package-info
- net.minecraft.server.packs.linkfs.PathContents
+ net.minecraft.server.packs.linkfs.PathContents$1
- net.minecraft.server.packs.linkfs.PathContents$2
+ net.minecraft.server.packs.linkfs.PathContents$DirectoryContents
- net.minecraft.server.packs.linkfs.PathContents$FileContents
- net.minecraft.server.packs.metadata.MetadataSectionSerializer
+ net.minecraft.server.packs.metadata.MetadataSectionType
- net.minecraft.server.packs.metadata.MetadataSectionType$1
- net.minecraft.server.packs.metadata.pack.package-info
+ net.minecraft.server.packs.metadata.pack.PackMetadataSection
+ net.minecraft.server.packs.metadata.package-info
+ net.minecraft.server.packs.OverlayMetadataSection
- net.minecraft.server.packs.OverlayMetadataSection$OverlayEntry
- net.minecraft.server.packs.package-info
+ net.minecraft.server.packs.PackLocationInfo
- net.minecraft.server.packs.PackResources
+ net.minecraft.server.packs.PackResources$ResourceOutput
- net.minecraft.server.packs.PackSelectionConfig
+ net.minecraft.server.packs.PackType
- net.minecraft.server.packs.PathPackResources
+ net.minecraft.server.packs.PathPackResources$PathResourcesSupplier
+ net.minecraft.server.packs.repository.BuiltInPackSource
- net.minecraft.server.packs.repository.BuiltInPackSource$1
+ net.minecraft.server.packs.repository.FolderRepositorySource
- net.minecraft.server.packs.repository.FolderRepositorySource$FolderPackDetector
+ net.minecraft.server.packs.repository.KnownPack
- net.minecraft.server.packs.repository.Pack
+ net.minecraft.server.packs.repository.Pack$Metadata
- net.minecraft.server.packs.repository.Pack$Position
+ net.minecraft.server.packs.repository.Pack$ResourcesSupplier
+ net.minecraft.server.packs.repository.package-info
- net.minecraft.server.packs.repository.PackCompatibility
+ net.minecraft.server.packs.repository.PackDetector
- net.minecraft.server.packs.repository.PackRepository
+ net.minecraft.server.packs.repository.PackSource
- net.minecraft.server.packs.repository.PackSource$1
+ net.minecraft.server.packs.repository.RepositorySource
- net.minecraft.server.packs.repository.ServerPacksSource
- net.minecraft.server.packs.resources.CloseableResourceManager
+ net.minecraft.server.packs.resources.FallbackResourceManager
- net.minecraft.server.packs.resources.FallbackResourceManager$1ResourceWithSourceAndIndex
+ net.minecraft.server.packs.resources.FallbackResourceManager$EntryStack
- net.minecraft.server.packs.resources.FallbackResourceManager$LeakedResourceWarningInputStream
+ net.minecraft.server.packs.resources.FallbackResourceManager$PackEntry
- net.minecraft.server.packs.resources.FallbackResourceManager$ResourceWithSource
+ net.minecraft.server.packs.resources.IoSupplier
- net.minecraft.server.packs.resources.MultiPackResourceManager
+ net.minecraft.server.packs.resources.package-info
+ net.minecraft.server.packs.resources.PreparableReloadListener
- net.minecraft.server.packs.resources.PreparableReloadListener$PreparationBarrier
+ net.minecraft.server.packs.resources.ProfiledReloadInstance
- net.minecraft.server.packs.resources.ProfiledReloadInstance$State
- net.minecraft.server.packs.resources.ReloadableResourceManager
+ net.minecraft.server.packs.resources.ReloadInstance
+ net.minecraft.server.packs.resources.Resource
- net.minecraft.server.packs.resources.ResourceFilterSection
+ net.minecraft.server.packs.resources.ResourceManager
- net.minecraft.server.packs.resources.ResourceManager$Empty
+ net.minecraft.server.packs.resources.ResourceManagerReloadListener
- net.minecraft.server.packs.resources.ResourceMetadata
+ net.minecraft.server.packs.resources.ResourceMetadata$1
- net.minecraft.server.packs.resources.ResourceMetadata$2
+ net.minecraft.server.packs.resources.ResourceMetadata$Builder
- net.minecraft.server.packs.resources.ResourceMetadata$Builder$1
+ net.minecraft.server.packs.resources.ResourceProvider
- net.minecraft.server.packs.resources.SimpleJsonResourceReloadListener
+ net.minecraft.server.packs.resources.SimplePreparableReloadListener
- net.minecraft.server.packs.resources.SimpleReloadInstance
+ net.minecraft.server.packs.resources.SimpleReloadInstance$1
- net.minecraft.server.packs.resources.SimpleReloadInstance$StateFactory
- net.minecraft.server.packs.VanillaPackResources
+ net.minecraft.server.packs.VanillaPackResourcesBuilder
+ net.minecraft.server.PlayerAdvancements
- net.minecraft.server.PlayerAdvancements$Data
- net.minecraft.server.players.BanListEntry
+ net.minecraft.server.players.GameProfileCache
- net.minecraft.server.players.GameProfileCache$1
+ net.minecraft.server.players.GameProfileCache$GameProfileInfo
- net.minecraft.server.players.IpBanList
+ net.minecraft.server.players.IpBanListEntry
- net.minecraft.server.players.OldUsersConverter
+ net.minecraft.server.players.OldUsersConverter$1
- net.minecraft.server.players.OldUsersConverter$2
+ net.minecraft.server.players.OldUsersConverter$3
- net.minecraft.server.players.OldUsersConverter$4
+ net.minecraft.server.players.OldUsersConverter$5
- net.minecraft.server.players.OldUsersConverter$ConversionError
- net.minecraft.server.players.package-info
+ net.minecraft.server.players.PlayerList
- net.minecraft.server.players.PlayerList$1
+ net.minecraft.server.players.ServerOpList
- net.minecraft.server.players.ServerOpListEntry
+ net.minecraft.server.players.SleepStatus
- net.minecraft.server.players.StoredUserEntry
+ net.minecraft.server.players.StoredUserList
- net.minecraft.server.players.UserBanList
+ net.minecraft.server.players.UserBanListEntry
- net.minecraft.server.players.UserWhiteList
+ net.minecraft.server.players.UserWhiteListEntry
+ net.minecraft.server.rcon.NetworkDataOutputStream
- net.minecraft.server.rcon.package-info
- net.minecraft.server.rcon.PktUtils
+ net.minecraft.server.rcon.RconConsoleSource
+ net.minecraft.server.rcon.thread.GenericThread
- net.minecraft.server.rcon.thread.package-info
- net.minecraft.server.rcon.thread.QueryThreadGs4
+ net.minecraft.server.rcon.thread.QueryThreadGs4$RequestChallenge
- net.minecraft.server.rcon.thread.RconClient
+ net.minecraft.server.rcon.thread.RconThread
+ net.minecraft.server.RegistryLayer
- net.minecraft.server.ReloadableServerRegistries
+ net.minecraft.server.ReloadableServerRegistries$EmptyTagLookupWrapper
- net.minecraft.server.ReloadableServerRegistries$Holder
+ net.minecraft.server.ReloadableServerResources
- net.minecraft.server.ReloadableServerResources$ConfigurableRegistryLookup
+ net.minecraft.server.ReloadableServerResources$ConfigurableRegistryLookup$1
- net.minecraft.server.ReloadableServerResources$MissingTagAccessPolicy
+ net.minecraft.server.RunningOnDifferentThreadException
- net.minecraft.server.ServerAdvancementManager
+ net.minecraft.server.ServerFunctionLibrary
- net.minecraft.server.ServerFunctionManager
+ net.minecraft.server.ServerInfo
- net.minecraft.server.ServerInterface
+ net.minecraft.server.ServerScoreboard
- net.minecraft.server.ServerScoreboard$Method
+ net.minecraft.server.ServerTickRateManager
- net.minecraft.server.Services
+ net.minecraft.server.TickTask
- net.minecraft.server.WorldLoader
+ net.minecraft.server.WorldLoader$DataLoadContext
- net.minecraft.server.WorldLoader$DataLoadOutput
+ net.minecraft.server.WorldLoader$InitConfig
- net.minecraft.server.WorldLoader$PackConfig
+ net.minecraft.server.WorldLoader$ResultFactory
- net.minecraft.server.WorldLoader$WorldDataSupplier
+ net.minecraft.server.WorldStem
+ net.minecraft.sounds.Music
- net.minecraft.sounds.Musics
- net.minecraft.sounds.package-info
+ net.minecraft.sounds.SoundEvent
- net.minecraft.sounds.SoundEvents
+ net.minecraft.sounds.SoundSource
+ net.minecraft.stats.package-info
+ net.minecraft.stats.RecipeBook
- net.minecraft.stats.RecipeBookSettings
+ net.minecraft.stats.RecipeBookSettings$TypeSettings
- net.minecraft.stats.ServerRecipeBook
+ net.minecraft.stats.ServerStatsCounter
- net.minecraft.stats.Stat
+ net.minecraft.stats.StatFormatter
+ net.minecraft.stats.Stats
- net.minecraft.stats.StatsCounter
- net.minecraft.stats.StatType
- net.minecraft.tags.BannerPatternTags
+ net.minecraft.tags.BiomeTags
- net.minecraft.tags.BlockTags
+ net.minecraft.tags.CatVariantTags
- net.minecraft.tags.DamageTypeTags
- net.minecraft.util.datafix.fixes.EmptyItemInVillagerTradeFix
+ net.minecraft.util.datafix.fixes.EntityArmorStandSilentFix
- net.minecraft.util.datafix.fixes.EntityBlockStateFix
+ net.minecraft.util.datafix.fixes.EntityBrushableBlockFieldsRenameFix
- net.minecraft.util.datafix.fixes.EntityCatSplitFix
+ net.minecraft.util.datafix.fixes.EntityCodSalmonFix
- net.minecraft.util.datafix.fixes.EntityCustomNameToComponentFix
+ net.minecraft.util.datafix.fixes.EntityElderGuardianSplitFix
- net.minecraft.util.datafix.fixes.EntityEquipmentToArmorAndHandFix
+ net.minecraft.util.datafix.fixes.EntityGoatMissingStateFix
- net.minecraft.util.datafix.fixes.EntityHealthFix
+ net.minecraft.util.datafix.fixes.EntityHorseSaddleFix
- net.minecraft.util.datafix.fixes.EntityHorseSplitFix
+ net.minecraft.util.datafix.fixes.EntityIdFix
- net.minecraft.util.datafix.fixes.EntityItemFrameDirectionFix
+ net.minecraft.util.datafix.fixes.EntityMinecartIdentifiersFix
- net.minecraft.util.datafix.fixes.EntityPaintingFieldsRenameFix
+ net.minecraft.util.datafix.fixes.EntityPaintingItemFrameDirectionFix
- net.minecraft.util.datafix.fixes.EntityPaintingMotiveFix
+ net.minecraft.util.datafix.fixes.EntityProjectileOwnerFix
- net.minecraft.util.datafix.fixes.EntityPufferfishRenameFix
+ net.minecraft.util.datafix.fixes.EntityRavagerRenameFix
- net.minecraft.util.datafix.fixes.EntityRedundantChanceTagsFix
+ net.minecraft.util.datafix.fixes.EntityRenameFix
- net.minecraft.util.datafix.fixes.EntityRidingToPassengersFix
+ net.minecraft.util.datafix.fixes.EntityShulkerColorFix
- net.minecraft.util.datafix.fixes.EntityShulkerRotationFix
+ net.minecraft.util.datafix.fixes.EntitySkeletonSplitFix
- net.minecraft.util.datafix.fixes.EntityStringUuidFix
+ net.minecraft.util.datafix.fixes.EntityTheRenameningFix
- net.minecraft.util.datafix.fixes.EntityTippedArrowFix
+ net.minecraft.util.datafix.fixes.EntityUUIDFix
- net.minecraft.util.datafix.fixes.EntityVariantFix
+ net.minecraft.util.datafix.fixes.EntityWolfColorFix
- net.minecraft.util.datafix.fixes.EntityZombieSplitFix
+ net.minecraft.util.datafix.fixes.EntityZombieVillagerTypeFix
- net.minecraft.util.datafix.fixes.EntityZombifiedPiglinRenameFix
+ net.minecraft.util.datafix.fixes.FeatureFlagRemoveFix
- net.minecraft.util.datafix.fixes.FilteredBooksFix
+ net.minecraft.util.datafix.fixes.FilteredSignsFix
- net.minecraft.util.datafix.fixes.FixProjectileStoredItem
+ net.minecraft.util.datafix.fixes.FixProjectileStoredItem$SubFixer
- net.minecraft.util.datafix.fixes.ForcePoiRebuild
+ net.minecraft.util.datafix.fixes.FurnaceRecipeFix
- net.minecraft.util.datafix.fixes.GoatHornIdFix
+ net.minecraft.util.datafix.fixes.GossipUUIDFix
- net.minecraft.util.datafix.fixes.HeightmapRenamingFix
+ net.minecraft.util.datafix.fixes.HorseBodyArmorItemFix
- net.minecraft.util.datafix.fixes.IglooMetadataRemovalFix
+ net.minecraft.util.datafix.fixes.ItemBannerColorFix
- net.minecraft.util.datafix.fixes.ItemCustomNameToComponentFix
+ net.minecraft.util.datafix.fixes.ItemIdFix
- net.minecraft.util.datafix.fixes.ItemLoreFix
+ net.minecraft.util.datafix.fixes.ItemPotionFix
- net.minecraft.util.datafix.fixes.ItemRemoveBlockEntityTagFix
+ net.minecraft.util.datafix.fixes.ItemRenameFix
- net.minecraft.util.datafix.fixes.ItemRenameFix$1
+ net.minecraft.util.datafix.fixes.ItemShulkerBoxColorFix
- net.minecraft.util.datafix.fixes.ItemSpawnEggFix
- net.minecraft.util.datafix.fixes.ItemStackComponentizationFix
+ net.minecraft.util.datafix.fixes.ItemStackComponentizationFix$ItemStackData
+ net.minecraft.util.datafix.fixes.ItemStackComponentRemainderFix
- net.minecraft.util.datafix.fixes.ItemStackCustomNameToOverrideComponentFix
+ net.minecraft.util.datafix.fixes.ItemStackEnchantmentNamesFix
- net.minecraft.util.datafix.fixes.ItemStackMapIdFix
+ net.minecraft.util.datafix.fixes.ItemStackSpawnEggFix
- net.minecraft.util.datafix.fixes.ItemStackTagFix
+ net.minecraft.util.datafix.fixes.ItemStackTheFlatteningFix
- net.minecraft.util.datafix.fixes.ItemStackUUIDFix
+ net.minecraft.util.datafix.fixes.ItemWaterPotionFix
- net.minecraft.util.datafix.fixes.ItemWrittenBookPagesStrictJsonFix
+ net.minecraft.util.datafix.fixes.JigsawPropertiesFix
- net.minecraft.util.datafix.fixes.JigsawRotationFix
+ net.minecraft.util.datafix.fixes.LeavesFix
- net.minecraft.util.datafix.fixes.LeavesFix$LeavesSection
+ net.minecraft.util.datafix.fixes.LeavesFix$Section
- net.minecraft.util.datafix.fixes.LegacyDragonFightFix
+ net.minecraft.util.datafix.fixes.LevelDataGeneratorOptionsFix
- net.minecraft.util.datafix.fixes.LevelFlatGeneratorInfoFix
+ net.minecraft.util.datafix.fixes.LevelLegacyWorldGenSettingsFix
- net.minecraft.util.datafix.fixes.LevelUUIDFix
+ net.minecraft.util.datafix.fixes.LodestoneCompassComponentFix
- net.minecraft.util.datafix.fixes.MapBannerBlockPosFormatFix
+ net.minecraft.util.datafix.fixes.MapIdFix
- net.minecraft.util.datafix.fixes.MemoryExpiryDataFix
+ net.minecraft.util.datafix.fixes.MissingDimensionFix
- net.minecraft.util.datafix.fixes.MobEffectIdFix
+ net.minecraft.util.datafix.fixes.MobSpawnerEntityIdentifiersFix
- net.minecraft.util.datafix.fixes.NamedEntityFix
+ net.minecraft.util.datafix.fixes.NamedEntityWriteReadFix
- net.minecraft.util.datafix.fixes.NamespacedTypeRenameFix
+ net.minecraft.util.datafix.fixes.NewVillageFix
- net.minecraft.util.datafix.fixes.ObjectiveDisplayNameFix
+ net.minecraft.util.datafix.fixes.ObjectiveRenderTypeFix
- net.minecraft.util.datafix.fixes.OminousBannerBlockEntityRenameFix
+ net.minecraft.util.datafix.fixes.OminousBannerRenameFix
- net.minecraft.util.datafix.fixes.OptionsAccessibilityOnboardFix
+ net.minecraft.util.datafix.fixes.OptionsAddTextBackgroundFix
- net.minecraft.util.datafix.fixes.OptionsAmbientOcclusionFix
+ net.minecraft.util.datafix.fixes.OptionsForceVBOFix
- net.minecraft.util.datafix.fixes.OptionsKeyLwjgl3Fix
+ net.minecraft.util.datafix.fixes.OptionsKeyTranslationFix
- net.minecraft.util.datafix.fixes.OptionsLowerCaseLanguageFix
+ net.minecraft.util.datafix.fixes.OptionsProgrammerArtFix
- net.minecraft.util.datafix.fixes.OptionsRenameFieldFix
+ net.minecraft.util.datafix.fixes.OverreachingTickFix
- net.minecraft.util.datafix.fixes.ParticleUnflatteningFix
+ net.minecraft.util.datafix.schemas.package-info
- net.minecraft.util.datafix.schemas.V3825
+ net.minecraft.util.datafix.schemas.V501
- net.minecraft.util.datafix.schemas.V700
+ net.minecraft.util.datafix.schemas.V701
- net.minecraft.util.datafix.schemas.V702
+ net.minecraft.util.datafix.schemas.V703
- net.minecraft.util.datafix.schemas.V704
+ net.minecraft.util.datafix.schemas.V704$1
- net.minecraft.util.datafix.schemas.V705
+ net.minecraft.util.datafix.schemas.V705$1
- net.minecraft.util.datafix.schemas.V808
+ net.minecraft.util.datafix.schemas.V99
- net.minecraft.util.datafix.schemas.V99$1
- net.minecraft.util.debugchart.AbstractSampleLogger
+ net.minecraft.util.debugchart.DebugSampleSubscriptionTracker
- net.minecraft.util.debugchart.DebugSampleSubscriptionTracker$SubscriptionRequest
+ net.minecraft.util.debugchart.DebugSampleSubscriptionTracker$SubscriptionStartedAt
- net.minecraft.util.debugchart.LocalSampleLogger
+ net.minecraft.util.debugchart.RemoteDebugSampleType
- net.minecraft.util.debugchart.RemoteSampleLogger
+ net.minecraft.util.debugchart.SampleLogger
- net.minecraft.util.debugchart.SampleStorage
+ net.minecraft.util.debugchart.TpsDebugDimensions
- net.minecraft.util.eventlog.EventLogDirectory
+ net.minecraft.util.eventlog.EventLogDirectory$CompressedFile
- net.minecraft.util.eventlog.EventLogDirectory$File
+ net.minecraft.util.eventlog.EventLogDirectory$FileId
- net.minecraft.util.eventlog.EventLogDirectory$FileList
+ net.minecraft.util.eventlog.EventLogDirectory$RawFile
- net.minecraft.util.eventlog.JsonEventLog
+ net.minecraft.util.eventlog.JsonEventLog$1
- net.minecraft.util.eventlog.JsonEventLogReader
+ net.minecraft.util.eventlog.JsonEventLogReader$1
- net.minecraft.util.eventlog.package-info
+ net.minecraft.util.monitoring.jmx.MinecraftServerStatistics
- net.minecraft.util.monitoring.jmx.MinecraftServerStatistics$AttributeDescription
+ net.minecraft.util.monitoring.jmx.package-info
- net.minecraft.util.NullOps$NullMapBuilder
- net.minecraft.util.package-info
+ net.minecraft.util.parsing.package-info
- net.minecraft.util.parsing.packrat.Atom
+ net.minecraft.util.parsing.packrat.commands.Grammar
- net.minecraft.util.parsing.packrat.commands.package-info
- net.minecraft.util.parsing.packrat.commands.ResourceLocationParseRule
+ net.minecraft.util.parsing.packrat.commands.ResourceLookupRule
- net.minecraft.util.parsing.packrat.commands.ResourceSuggestion
+ net.minecraft.util.parsing.packrat.commands.StringReaderParserState
- net.minecraft.util.parsing.packrat.commands.StringReaderTerms
+ net.minecraft.util.parsing.packrat.commands.StringReaderTerms$TerminalCharacter
- net.minecraft.util.parsing.packrat.commands.StringReaderTerms$TerminalWord
+ net.minecraft.util.parsing.packrat.commands.TagParseRule
+ net.minecraft.util.parsing.packrat.Control
- net.minecraft.util.parsing.packrat.Dictionary
+ net.minecraft.util.parsing.packrat.ErrorCollector
- net.minecraft.util.parsing.packrat.ErrorCollector$LongestOnly
+ net.minecraft.util.parsing.packrat.ErrorEntry
+ net.minecraft.util.parsing.packrat.package-info
- net.minecraft.util.parsing.packrat.ParseState
+ net.minecraft.util.parsing.packrat.ParseState$CacheEntry
- net.minecraft.util.parsing.packrat.ParseState$CacheKey
+ net.minecraft.util.parsing.packrat.Rule
- net.minecraft.util.parsing.packrat.Rule$RuleAction
+ net.minecraft.util.parsing.packrat.Rule$SimpleRuleAction
- net.minecraft.util.parsing.packrat.Rule$WrappedTerm
+ net.minecraft.util.parsing.packrat.Scope
- net.minecraft.util.parsing.packrat.SuggestionSupplier
+ net.minecraft.util.parsing.packrat.Term
- net.minecraft.util.parsing.packrat.Term$1
+ net.minecraft.util.parsing.packrat.Term$2
- net.minecraft.util.parsing.packrat.Term$Alternative
+ net.minecraft.util.parsing.packrat.Term$Marker
- net.minecraft.util.parsing.packrat.Term$Maybe
+ net.minecraft.util.parsing.packrat.Term$Reference
- net.minecraft.util.parsing.packrat.Term$Sequence
- net.minecraft.util.profiling.ActiveProfiler
+ net.minecraft.util.profiling.ActiveProfiler$PathEntry
- net.minecraft.util.profiling.ContinuousProfiler
+ net.minecraft.util.profiling.EmptyProfileResults
- net.minecraft.util.profiling.FilledProfileResults
+ net.minecraft.util.profiling.FilledProfileResults$1
- net.minecraft.util.profiling.FilledProfileResults$CounterCollector
+ net.minecraft.util.profiling.InactiveProfiler
+ net.minecraft.util.profiling.jfr.callback.package-info
- net.minecraft.util.profiling.jfr.callback.ProfiledDuration
+ net.minecraft.util.profiling.jfr.Environment
- net.minecraft.util.profiling.jfr.event.ChunkGenerationEvent
+ net.minecraft.util.profiling.jfr.event.ChunkGenerationEvent$Fields
- net.minecraft.util.profiling.jfr.event.ChunkRegionIoEvent
+ net.minecraft.util.profiling.jfr.event.ChunkRegionIoEvent$Fields
- net.minecraft.util.profiling.jfr.event.ChunkRegionReadEvent
+ net.minecraft.util.profiling.jfr.event.ChunkRegionWriteEvent
- net.minecraft.util.profiling.jfr.event.NetworkSummaryEvent
+ net.minecraft.util.profiling.jfr.event.NetworkSummaryEvent$Fields
- net.minecraft.util.profiling.jfr.event.NetworkSummaryEvent$SumAggregation
- net.minecraft.util.profiling.jfr.event.package-info
+ net.minecraft.util.profiling.jfr.event.PacketEvent
- net.minecraft.util.profiling.jfr.event.PacketEvent$Fields
+ net.minecraft.util.profiling.jfr.event.PacketReceivedEvent
- net.minecraft.util.profiling.jfr.event.PacketSentEvent
+ net.minecraft.util.profiling.jfr.event.ServerTickTimeEvent
- net.minecraft.util.profiling.jfr.event.ServerTickTimeEvent$Fields
+ net.minecraft.util.profiling.jfr.event.WorldLoadFinishedEvent
- net.minecraft.util.profiling.jfr.JfrProfiler
+ net.minecraft.util.profiling.jfr.JfrProfiler$1
- net.minecraft.util.profiling.jfr.JvmProfiler
+ net.minecraft.util.profiling.jfr.JvmProfiler$NoOpProfiler
+ net.minecraft.util.profiling.jfr.package-info
- net.minecraft.util.profiling.jfr.parse.JfrStatsParser
+ net.minecraft.util.profiling.jfr.parse.JfrStatsParser$1
- net.minecraft.util.profiling.jfr.parse.JfrStatsParser$MutableCountAndSize
+ net.minecraft.util.profiling.jfr.parse.JfrStatsResult
- net.minecraft.util.profiling.jfr.parse.package-info
- net.minecraft.util.profiling.jfr.Percentiles
+ net.minecraft.util.profiling.jfr.serialize.JfrResultJsonSerializer
- net.minecraft.util.profiling.jfr.serialize.package-info
+ net.minecraft.util.profiling.jfr.stats.ChunkGenStat
- net.minecraft.util.profiling.jfr.stats.ChunkIdentification
+ net.minecraft.util.profiling.jfr.stats.CpuLoadStat
- net.minecraft.util.profiling.jfr.stats.FileIOStat
+ net.minecraft.util.profiling.jfr.stats.FileIOStat$Summary
- net.minecraft.util.profiling.jfr.stats.GcHeapStat
+ net.minecraft.util.profiling.jfr.stats.GcHeapStat$Summary
- net.minecraft.util.profiling.jfr.stats.GcHeapStat$Timing
+ net.minecraft.util.profiling.jfr.stats.IoSummary
- net.minecraft.util.profiling.jfr.stats.IoSummary$CountAndSize
+ net.minecraft.util.profiling.jfr.stats.package-info
+ net.minecraft.util.profiling.jfr.stats.PacketIdentification
- net.minecraft.util.profiling.jfr.stats.ThreadAllocationStat
+ net.minecraft.util.profiling.jfr.stats.ThreadAllocationStat$Summary
- net.minecraft.util.profiling.jfr.stats.TickTimeStat
+ net.minecraft.util.profiling.jfr.stats.TimedStat
- net.minecraft.util.profiling.jfr.stats.TimedStatSummary
+ net.minecraft.util.profiling.jfr.SummaryReporter
- net.minecraft.util.profiling.metrics.MetricCategory
+ net.minecraft.util.profiling.metrics.MetricSampler
- net.minecraft.util.profiling.metrics.MetricSampler$MetricSamplerBuilder
+ net.minecraft.util.profiling.metrics.MetricSampler$SamplerResult
- net.minecraft.util.profiling.metrics.MetricSampler$ThresholdTest
+ net.minecraft.util.profiling.metrics.MetricSampler$ValueIncreasedByPercentage
- net.minecraft.util.profiling.metrics.MetricsRegistry
+ net.minecraft.util.profiling.metrics.MetricsRegistry$AggregatedMetricSampler
- net.minecraft.util.profiling.metrics.MetricsSamplerProvider
- net.minecraft.util.profiling.metrics.package-info
+ net.minecraft.util.profiling.metrics.ProfilerMeasured
+ net.minecraft.util.profiling.metrics.profiling.ActiveMetricsRecorder
- net.minecraft.util.profiling.metrics.profiling.InactiveMetricsRecorder
+ net.minecraft.util.profiling.metrics.profiling.MetricsRecorder
- net.minecraft.util.profiling.metrics.profiling.package-info
- net.minecraft.util.profiling.metrics.profiling.ProfilerSamplerAdapter
+ net.minecraft.util.profiling.metrics.profiling.ServerMetricsSamplersProvider
- net.minecraft.util.profiling.metrics.profiling.ServerMetricsSamplersProvider$1
+ net.minecraft.util.profiling.metrics.profiling.ServerMetricsSamplersProvider$CpuStats
+ net.minecraft.util.profiling.metrics.storage.MetricsPersister
+ net.minecraft.util.profiling.metrics.storage.package-info
- net.minecraft.util.profiling.metrics.storage.RecordedDeviation
- net.minecraft.util.profiling.package-info
- net.minecraft.util.profiling.ProfileCollector
+ net.minecraft.util.profiling.ProfileResults
- net.minecraft.util.profiling.ProfilerFiller
+ net.minecraft.util.profiling.ProfilerFiller$1
- net.minecraft.util.profiling.ProfilerPathEntry
+ net.minecraft.util.profiling.ResultField
- net.minecraft.util.profiling.SingleTickProfiler
+ net.minecraft.util.random.package-info
+ net.minecraft.util.random.SimpleWeightedRandomList
- net.minecraft.util.random.SimpleWeightedRandomList$Builder
+ net.minecraft.util.random.Weight
- net.minecraft.util.random.WeightedEntry
+ net.minecraft.util.random.WeightedEntry$IntrusiveBase
- net.minecraft.util.random.WeightedEntry$Wrapper
+ net.minecraft.util.random.WeightedRandom
- net.minecraft.util.random.WeightedRandomList
- net.minecraft.util.thread.BlockableEventLoop
+ net.minecraft.util.thread.NamedThreadFactory
- net.minecraft.util.thread.package-info
- net.minecraft.util.thread.ProcessorHandle
+ net.minecraft.util.thread.ProcessorHandle$1
- net.minecraft.util.thread.ProcessorMailbox
+ net.minecraft.util.thread.ReentrantBlockableEventLoop
- net.minecraft.util.thread.StrictQueue
+ net.minecraft.util.thread.StrictQueue$FixedPriorityQueue
- net.minecraft.util.thread.StrictQueue$IntRunnable
+ net.minecraft.util.thread.StrictQueue$QueueStrictQueue
+ net.minecraft.util.valueproviders.BiasedToBottomInt
- net.minecraft.util.valueproviders.ClampedInt
+ net.minecraft.util.valueproviders.ClampedNormalFloat
- net.minecraft.util.valueproviders.ClampedNormalInt
+ net.minecraft.util.valueproviders.ConstantFloat
- net.minecraft.util.valueproviders.ConstantInt
+ net.minecraft.util.valueproviders.FloatProvider
- net.minecraft.util.valueproviders.FloatProviderType
+ net.minecraft.util.valueproviders.IntProvider
- net.minecraft.util.valueproviders.IntProviderType
+ net.minecraft.util.valueproviders.MultipliedFloats
+ net.minecraft.util.valueproviders.package-info
- net.minecraft.util.valueproviders.SampledFloat
+ net.minecraft.util.valueproviders.TrapezoidFloat
- net.minecraft.util.valueproviders.UniformFloat
+ net.minecraft.util.valueproviders.UniformInt
- net.minecraft.util.valueproviders.WeightedListInt
- net.minecraft.util.worldupdate.package-info
- net.minecraft.util.worldupdate.WorldUpgrader
+ net.minecraft.util.worldupdate.WorldUpgrader$AbstractUpgrader
- net.minecraft.util.worldupdate.WorldUpgrader$ChunkUpgrader
+ net.minecraft.util.worldupdate.WorldUpgrader$DimensionToUpgrade
- net.minecraft.util.worldupdate.WorldUpgrader$EntityUpgrader
+ net.minecraft.util.worldupdate.WorldUpgrader$FileToUpgrade
- net.minecraft.util.worldupdate.WorldUpgrader$PoiUpgrader
+ net.minecraft.util.worldupdate.WorldUpgrader$SimpleRegionStorageUpgrader
+ net.minecraft.world.BossEvent
- net.minecraft.world.BossEvent$BossBarColor
+ net.minecraft.world.BossEvent$BossBarOverlay
- net.minecraft.world.Clearable
+ net.minecraft.world.CompoundContainer
- net.minecraft.world.Container
+ net.minecraft.world.ContainerHelper
- net.minecraft.world.ContainerListener
+ net.minecraft.world.Containers
- net.minecraft.world.damagesource.CombatEntry
+ net.minecraft.world.damagesource.CombatRules
- net.minecraft.world.damagesource.CombatTracker
+ net.minecraft.world.damagesource.DamageEffects
- net.minecraft.world.damagesource.DamageScaling
+ net.minecraft.world.damagesource.DamageSource
- net.minecraft.world.damagesource.DamageSource$1
+ net.minecraft.world.damagesource.DamageSources
- net.minecraft.world.damagesource.DamageType
+ net.minecraft.world.damagesource.DamageTypes
- net.minecraft.world.damagesource.DeathMessageType
+ net.minecraft.world.damagesource.FallLocation
- net.minecraft.world.damagesource.package-info
- net.minecraft.world.Difficulty
+ net.minecraft.world.DifficultyInstance
+ net.minecraft.world.effect.AbsorptionMobEffect
- net.minecraft.world.effect.BadOmenMobEffect
+ net.minecraft.world.effect.HealOrHarmMobEffect
- net.minecraft.world.effect.HungerMobEffect
+ net.minecraft.world.effect.InfestedMobEffect
- net.minecraft.world.effect.InstantenousMobEffect
+ net.minecraft.world.effect.MobEffect
- net.minecraft.world.effect.MobEffect$AttributeTemplate
+ net.minecraft.world.effect.MobEffectCategory
- net.minecraft.world.effect.MobEffectInstance
+ net.minecraft.world.effect.MobEffectInstance$BlendState
- net.minecraft.world.effect.MobEffectInstance$Details
- net.minecraft.world.effect.MobEffects
+ net.minecraft.world.effect.MobEffectUtil
+ net.minecraft.world.effect.OozingMobEffect
+ net.minecraft.world.effect.package-info
- net.minecraft.world.effect.PoisonMobEffect
+ net.minecraft.world.effect.RaidOmenMobEffect
- net.minecraft.world.effect.RegenerationMobEffect
+ net.minecraft.world.effect.SaturationMobEffect
- net.minecraft.world.effect.WeavingMobEffect
+ net.minecraft.world.effect.WindChargedMobEffect
- net.minecraft.world.effect.WitherMobEffect
- net.minecraft.world.entity.AgeableMob
+ net.minecraft.world.entity.AgeableMob$AgeableMobGroupData
- net.minecraft.world.entity.AnimationState
+ net.minecraft.world.entity.AreaEffectCloud
- net.minecraft.world.entity.Attackable
+ net.minecraft.world.entity.Crackiness
- net.minecraft.world.entity.Crackiness$Level
+ net.minecraft.world.entity.decoration.ItemFrame$2
- net.minecraft.world.entity.decoration.LeashFenceKnotEntity
- net.minecraft.world.entity.decoration.package-info
+ net.minecraft.world.entity.decoration.Painting
- net.minecraft.world.entity.decoration.PaintingVariant
+ net.minecraft.world.entity.decoration.PaintingVariants
+ net.minecraft.world.entity.Display
- net.minecraft.world.entity.Display$BillboardConstraints
+ net.minecraft.world.entity.Display$BlockDisplay
- net.minecraft.world.entity.Display$BlockDisplay$BlockRenderState
+ net.minecraft.world.entity.Display$ColorInterpolator
- net.minecraft.world.entity.Display$FloatInterpolator
+ net.minecraft.world.entity.Display$GenericInterpolator
- net.minecraft.world.entity.Display$IntInterpolator
+ net.minecraft.world.entity.Display$ItemDisplay
- net.minecraft.world.entity.EquipmentUser
+ net.minecraft.world.entity.ExperienceOrb
- net.minecraft.world.entity.FlyingMob
+ net.minecraft.world.entity.GlowSquid
- net.minecraft.world.entity.HasCustomInventoryScreen
+ net.minecraft.world.entity.HumanoidArm
- net.minecraft.world.entity.Interaction
+ net.minecraft.world.entity.Interaction$PlayerAction
+ net.minecraft.world.entity.item.FallingBlockEntity
- net.minecraft.world.entity.item.ItemEntity
+ net.minecraft.world.entity.item.ItemEntity$1
- net.minecraft.world.entity.ItemBasedSteering
+ net.minecraft.world.entity.ItemSteerable
- net.minecraft.world.entity.LerpingModel
+ net.minecraft.world.entity.LightningBolt
- net.minecraft.world.entity.LivingEntity
+ net.minecraft.world.entity.LivingEntity$1
- net.minecraft.world.entity.LivingEntity$Fallsounds
+ net.minecraft.world.entity.Marker
- net.minecraft.world.entity.Mob
+ net.minecraft.world.entity.Mob$1
- net.minecraft.world.entity.MobCategory
+ net.minecraft.world.entity.MobSpawnType
- net.minecraft.world.entity.MoverType
+ net.minecraft.world.entity.NeutralMob
- net.minecraft.world.entity.OminousItemSpawner
+ net.minecraft.world.entity.OwnableEntity
- net.minecraft.world.entity.PathfinderMob
+ net.minecraft.world.entity.PlayerRideable
- net.minecraft.world.entity.PlayerRideableJumping
+ net.minecraft.world.entity.Pose
- net.minecraft.world.entity.PowerableMob
+ net.minecraft.world.entity.RelativeMovement
- net.minecraft.world.entity.ReputationEventHandler
+ net.minecraft.world.entity.Saddleable
- net.minecraft.world.entity.Shearable
+ net.minecraft.world.entity.SlotAccess
- net.minecraft.world.entity.SlotAccess$1
+ net.minecraft.world.entity.SlotAccess$2
- net.minecraft.world.entity.SlotAccess$3
- net.minecraft.world.InteractionHand
+ net.minecraft.world.InteractionResult
- net.minecraft.world.InteractionResultHolder
+ net.minecraft.world.item.alchemy.Potion
- net.minecraft.world.item.alchemy.PotionBrewing
+ net.minecraft.world.item.Items
- net.minecraft.world.item.ItemStackLinkedSet
+ net.minecraft.world.item.ItemStackLinkedSet$1
- net.minecraft.world.item.ItemUtils
- net.minecraft.world.item.KnowledgeBookItem
+ net.minecraft.world.item.LeadItem
- net.minecraft.world.item.LingeringPotionItem
+ net.minecraft.world.item.MaceItem
- net.minecraft.world.item.MapItem
+ net.minecraft.world.item.MapItem$1
- net.minecraft.world.item.MilkBucketItem
+ net.minecraft.world.item.MinecartItem
- net.minecraft.world.item.MinecartItem$1
+ net.minecraft.world.item.MobBucketItem
- net.minecraft.world.item.NameTagItem
+ net.minecraft.world.item.OminousBottleItem
- net.minecraft.world.item.PickaxeItem
+ net.minecraft.world.item.PlaceOnWaterBlockItem
- net.minecraft.world.item.PlayerHeadItem
+ net.minecraft.world.item.PotionItem
- net.minecraft.world.item.ProjectileItem
+ net.minecraft.world.item.ProjectileItem$DispenseConfig
- net.minecraft.world.item.ProjectileItem$DispenseConfig$Builder
+ net.minecraft.world.item.ProjectileItem$PositionFunction
- net.minecraft.world.item.ProjectileWeaponItem
+ net.minecraft.world.item.Rarity
- net.minecraft.world.item.RecordItem
+ net.minecraft.world.item.SaddleItem
- net.minecraft.world.item.ScaffoldingBlockItem
+ net.minecraft.world.item.ServerItemCooldowns
- net.minecraft.world.item.ShearsItem
+ net.minecraft.world.item.ShieldItem
- net.minecraft.world.item.ShovelItem
+ net.minecraft.world.item.SignApplicator
- net.minecraft.world.item.SignItem
+ net.minecraft.world.item.SmithingTemplateItem
- net.minecraft.world.item.SnowballItem
+ net.minecraft.world.item.SolidBucketItem
- net.minecraft.world.item.SpawnEggItem
+ net.minecraft.world.item.SpectralArrowItem
- net.minecraft.world.item.SplashPotionItem
+ net.minecraft.world.item.SpyglassItem
- net.minecraft.world.item.StandingAndWallBlockItem
+ net.minecraft.world.item.SuspiciousStewItem
- net.minecraft.world.item.SwordItem
+ net.minecraft.world.item.ThrowablePotionItem
- net.minecraft.world.item.Tier
+ net.minecraft.world.item.TieredItem
- net.minecraft.world.item.Tiers
+ net.minecraft.world.item.TippedArrowItem
- net.minecraft.world.item.TooltipFlag
+ net.minecraft.world.item.TooltipFlag$Default
- net.minecraft.world.item.TridentItem
+ net.minecraft.world.item.UseAnim
- net.minecraft.world.item.WindChargeItem
+ net.minecraft.world.item.WritableBookItem
- net.minecraft.world.item.WrittenBookItem
+ net.minecraft.world.ItemInteractionResult
- net.minecraft.world.level.block.entity.EnchantingTableBlockEntity
+ net.minecraft.world.level.block.entity.EnchantmentTableBlockEntity
- net.minecraft.world.level.storage.loot.ContainerComponentManipulator
- net.minecraft.world.level.storage.loot.ContainerComponentManipulators$1
- net.minecraft.world.level.storage.loot.ContainerComponentManipulators$3
+ net.minecraft.world.level.storage.loot.entries.AlternativesEntry
- net.minecraft.world.level.storage.loot.entries.AlternativesEntry$Builder
+ net.minecraft.world.level.storage.loot.entries.ComposableEntryContainer
- net.minecraft.world.level.storage.loot.entries.CompositeEntryBase
+ net.minecraft.world.level.storage.loot.entries.CompositeEntryBase$CompositeEntryConstructor
- net.minecraft.world.level.storage.loot.entries.DynamicLoot
+ net.minecraft.world.level.storage.loot.entries.EmptyLootItem
- net.minecraft.world.level.storage.loot.entries.EntryGroup
+ net.minecraft.world.level.storage.loot.entries.EntryGroup$Builder
- net.minecraft.world.level.storage.loot.entries.LootItem
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntries
- net.minecraft.world.level.storage.loot.entries.LootPoolEntry
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntryContainer
- net.minecraft.world.level.storage.loot.entries.LootPoolEntryContainer$Builder
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntryType
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$1
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$Builder
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$DummyBuilder
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$EntryBase
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$EntryConstructor
- net.minecraft.world.level.storage.loot.entries.NestedLootTable
+ net.minecraft.world.level.storage.loot.entries.package-info
+ net.minecraft.world.level.storage.loot.entries.SequentialEntry
- net.minecraft.world.level.storage.loot.entries.SequentialEntry$Builder
+ net.minecraft.world.level.storage.loot.entries.TagEntry
- net.minecraft.world.level.storage.loot.entries.TagEntry$1
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$BinomialWithBonusCount
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$Formula
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$FormulaType
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$OreDrops
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$UniformBonusCount
- net.minecraft.world.level.storage.loot.functions.ApplyExplosionDecay
+ net.minecraft.world.level.storage.loot.functions.CopyBlockState
- net.minecraft.world.level.storage.loot.functions.CopyBlockState$Builder
+ net.minecraft.world.level.storage.loot.functions.CopyComponentsFunction
- net.minecraft.world.level.storage.loot.functions.CopyComponentsFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.CopyComponentsFunction$Source
- net.minecraft.world.level.storage.loot.functions.CopyCustomDataFunction
+ net.minecraft.world.level.storage.loot.functions.CopyCustomDataFunction$Builder
- net.minecraft.world.level.storage.loot.functions.CopyCustomDataFunction$CopyOperation
+ net.minecraft.world.level.storage.loot.functions.CopyCustomDataFunction$MergeStrategy
- net.minecraft.world.level.storage.loot.functions.CopyCustomDataFunction$MergeStrategy$1
+ net.minecraft.world.level.storage.loot.functions.CopyCustomDataFunction$MergeStrategy$2
- net.minecraft.world.level.storage.loot.functions.CopyCustomDataFunction$MergeStrategy$3
+ net.minecraft.world.level.storage.loot.functions.CopyNameFunction
- net.minecraft.world.level.storage.loot.functions.CopyNameFunction$NameSource
+ net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction
- net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction
- net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction
- net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.FillPlayerHead
- net.minecraft.world.level.storage.loot.functions.FilteredFunction
+ net.minecraft.world.level.storage.loot.functions.package-info
- net.minecraft.world.level.storage.loot.functions.SequenceFunction
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Modifier
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$ModifierBuilder
+ net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction
- net.minecraft.world.level.storage.loot.functions.SetBannerPatternFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetBookCoverFunction
- net.minecraft.world.level.storage.loot.functions.SetComponentsFunction
+ net.minecraft.world.level.storage.loot.functions.SetContainerContents
- net.minecraft.world.level.storage.loot.functions.SetContainerContents$Builder
+ net.minecraft.world.level.storage.loot.functions.SetContainerLootTable
- net.minecraft.world.level.storage.loot.functions.SetCustomDataFunction
- net.minecraft.world.level.storage.loot.functions.SetLoreFunction
+ net.minecraft.world.level.storage.loot.functions.SetLoreFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetNameFunction
+ net.minecraft.world.level.storage.loot.functions.SetNameFunction$Target
- net.minecraft.world.level.storage.loot.functions.SetOminousBottleAmplifierFunction
+ net.minecraft.world.level.storage.loot.functions.SetPotionFunction
- net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction
+ net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction$EffectEntry
+ net.minecraft.world.level.storage.loot.functions.SetWritableBookPagesFunction
- net.minecraft.world.level.storage.loot.functions.SetWrittenBookPagesFunction
+ net.minecraft.world.level.storage.loot.functions.SmeltItemFunction
- net.minecraft.world.level.storage.loot.functions.ToggleTooltips
+ net.minecraft.world.level.storage.loot.functions.ToggleTooltips$ComponentToggle
- net.minecraft.world.level.storage.loot.functions.ToggleTooltips$TooltipWither
+ net.minecraft.world.level.storage.loot.IntRange
- net.minecraft.world.level.storage.loot.IntRange$IntChecker
+ net.minecraft.world.level.storage.loot.IntRange$IntLimiter
- net.minecraft.world.level.storage.loot.LootContext
+ net.minecraft.world.level.storage.loot.LootContext$Builder
- net.minecraft.world.level.storage.loot.LootContext$EntityTarget
+ net.minecraft.world.level.storage.loot.LootContext$VisitedEntry
- net.minecraft.world.level.storage.loot.LootContextUser
+ net.minecraft.world.level.storage.loot.LootDataType
- net.minecraft.world.level.storage.loot.LootDataType$Validator
+ net.minecraft.world.level.storage.loot.LootParams
- net.minecraft.world.level.storage.loot.LootParams$Builder
+ net.minecraft.world.level.storage.loot.LootParams$DynamicDrop
- net.minecraft.world.level.storage.loot.LootPool
+ net.minecraft.world.level.storage.loot.LootPool$Builder
- net.minecraft.world.level.storage.loot.LootTable
+ net.minecraft.world.level.storage.loot.LootTable$Builder
- net.minecraft.world.level.storage.loot.package-info
+ net.minecraft.world.level.storage.loot.parameters.LootContextParam
+ net.minecraft.world.level.storage.loot.parameters.LootContextParams
- net.minecraft.world.level.storage.loot.parameters.LootContextParamSet
+ net.minecraft.world.level.storage.loot.parameters.LootContextParamSet$Builder
- net.minecraft.world.level.storage.loot.parameters.LootContextParamSets
- net.minecraft.world.level.storage.loot.parameters.package-info
+ net.minecraft.world.level.storage.loot.predicates.AllOfCondition
- net.minecraft.world.level.storage.loot.predicates.AllOfCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.AnyOfCondition
- net.minecraft.world.level.storage.loot.predicates.AnyOfCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.BonusLevelTableCondition
- net.minecraft.world.level.storage.loot.predicates.CompositeLootItemCondition
+ net.minecraft.world.level.storage.loot.predicates.CompositeLootItemCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.ConditionReference
+ net.minecraft.world.level.storage.loot.predicates.ConditionUserBuilder
- net.minecraft.world.level.storage.loot.predicates.DamageSourceCondition
+ net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition
- net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.ExplosionCondition
- net.minecraft.world.level.storage.loot.predicates.InvertedLootItemCondition
+ net.minecraft.world.level.storage.loot.predicates.LocationCheck
- net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.LootItemCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.LootItemConditions
- net.minecraft.world.level.storage.loot.predicates.LootItemConditionType
- net.minecraft.world.level.storage.loot.predicates.LootItemEntityPropertyCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemKilledByPlayerCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceWithLootingCondition
- net.minecraft.world.level.storage.loot.predicates.MatchTool
- net.minecraft.world.level.storage.loot.predicates.package-info
+ net.minecraft.world.level.storage.loot.predicates.TimeCheck
- net.minecraft.world.level.storage.loot.predicates.TimeCheck$Builder
+ net.minecraft.world.level.storage.loot.predicates.ValueCheckCondition
- net.minecraft.world.level.storage.loot.predicates.WeatherCheck
+ net.minecraft.world.level.storage.loot.predicates.WeatherCheck$Builder
+ net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider
- net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$1
+ net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$2
- net.minecraft.world.level.storage.loot.providers.nbt.ContextNbtProvider$Getter
+ net.minecraft.world.level.storage.loot.providers.nbt.LootNbtProviderType
- net.minecraft.world.level.storage.loot.providers.nbt.NbtProvider
+ net.minecraft.world.level.storage.loot.providers.nbt.NbtProviders
+ net.minecraft.world.level.storage.loot.providers.nbt.package-info
- net.minecraft.world.level.storage.loot.providers.nbt.StorageNbtProvider
- net.minecraft.world.level.storage.loot.providers.number.BinomialDistributionGenerator
+ net.minecraft.world.level.storage.loot.providers.number.ConstantValue
- net.minecraft.world.level.storage.loot.providers.number.LootNumberProviderType
+ net.minecraft.world.level.storage.loot.providers.number.NumberProvider
- net.minecraft.world.level.storage.loot.providers.number.NumberProviders
- net.minecraft.world.level.storage.loot.providers.number.package-info
+ net.minecraft.world.level.storage.loot.providers.number.ScoreboardValue
- net.minecraft.world.level.storage.loot.providers.number.StorageValue
+ net.minecraft.world.level.storage.loot.providers.number.UniformGenerator
+ net.minecraft.world.level.storage.loot.providers.score.ContextScoreboardNameProvider
- net.minecraft.world.level.storage.loot.providers.score.FixedScoreboardNameProvider
+ net.minecraft.world.level.storage.loot.providers.score.LootScoreProviderType
- net.minecraft.world.level.storage.loot.providers.score.package-info
- net.minecraft.world.level.storage.loot.providers.score.ScoreboardNameProvider
+ net.minecraft.world.level.storage.loot.providers.score.ScoreboardNameProviders
- net.minecraft.world.level.storage.loot.ValidationContext
+ net.minecraft.world.level.storage.package-info
- net.minecraft.world.level.timers.FunctionCallback
+ net.minecraft.world.level.timers.FunctionCallback$Serializer
- net.minecraft.world.level.timers.FunctionTagCallback
+ net.minecraft.world.level.timers.FunctionTagCallback$Serializer
+ net.minecraft.world.level.timers.package-info
- net.minecraft.world.level.timers.TimerCallback
+ net.minecraft.world.level.timers.TimerCallback$Serializer
- net.minecraft.world.level.timers.TimerCallbacks
+ net.minecraft.world.level.timers.TimerQueue
- net.minecraft.world.level.timers.TimerQueue$Event
- net.minecraft.world.level.validation.ContentValidationException
+ net.minecraft.world.level.validation.DirectoryValidator
- net.minecraft.world.level.validation.DirectoryValidator$1
+ net.minecraft.world.level.validation.ForbiddenSymlinkInfo
+ net.minecraft.world.level.validation.package-info
- net.minecraft.world.level.validation.PathAllowList
+ net.minecraft.world.level.validation.PathAllowList$ConfigEntry
- net.minecraft.world.level.validation.PathAllowList$EntryType
- net.minecraft.world.LockCode
+ net.minecraft.world.MenuProvider
- net.minecraft.world.Nameable
- net.minecraft.world.package-info
+ net.minecraft.world.phys.AABB
- net.minecraft.world.phys.BlockHitResult
+ net.minecraft.world.phys.EntityHitResult
- net.minecraft.world.phys.HitResult
+ net.minecraft.world.phys.HitResult$Type
- net.minecraft.world.phys.package-info
+ net.minecraft.world.phys.shapes.ArrayVoxelShape
- net.minecraft.world.phys.shapes.ArrayVoxelShape$1
+ net.minecraft.world.phys.shapes.BitSetDiscreteVoxelShape
- net.minecraft.world.phys.shapes.BooleanOp
+ net.minecraft.world.phys.shapes.CollisionContext
- net.minecraft.world.phys.shapes.CubePointRange
+ net.minecraft.world.phys.shapes.CubeVoxelShape
- net.minecraft.world.phys.shapes.DiscreteCubeMerger
+ net.minecraft.world.phys.shapes.DiscreteVoxelShape
- net.minecraft.world.phys.shapes.DiscreteVoxelShape$IntFaceConsumer
+ net.minecraft.world.phys.shapes.DiscreteVoxelShape$IntLineConsumer
- net.minecraft.world.phys.shapes.EntityCollisionContext
+ net.minecraft.world.phys.shapes.EntityCollisionContext$1
- net.minecraft.world.phys.shapes.IdenticalMerger
+ net.minecraft.world.phys.shapes.IndexMerger
- net.minecraft.world.phys.shapes.IndexMerger$IndexConsumer
+ net.minecraft.world.phys.shapes.IndirectMerger
- net.minecraft.world.phys.shapes.NonOverlappingMerger
+ net.minecraft.world.phys.shapes.OffsetDoubleList
+ net.minecraft.world.phys.shapes.package-info
- net.minecraft.world.phys.shapes.Shapes
+ net.minecraft.world.phys.shapes.Shapes$DoubleLineConsumer
- net.minecraft.world.phys.shapes.SliceShape
+ net.minecraft.world.phys.shapes.SubShape
- net.minecraft.world.phys.shapes.VoxelShape
- net.minecraft.world.phys.Vec2
+ net.minecraft.world.phys.Vec3
- net.minecraft.world.RandomizableContainer
+ net.minecraft.world.RandomSequence
- net.minecraft.world.RandomSequences
+ net.minecraft.world.RandomSequences$DirtyMarkingRandomSource
+ net.minecraft.world.scores.criteria.ObjectiveCriteria
- net.minecraft.world.scores.criteria.ObjectiveCriteria$RenderType
+ net.minecraft.world.scores.criteria.package-info
- net.minecraft.world.scores.DisplaySlot
+ net.minecraft.world.scores.DisplaySlot$1
- net.minecraft.world.scores.Objective
- net.minecraft.world.scores.package-info
+ net.minecraft.world.scores.PlayerScoreEntry
- net.minecraft.world.scores.PlayerScores
+ net.minecraft.world.scores.PlayerTeam
- net.minecraft.world.scores.ReadOnlyScoreInfo
+ net.minecraft.world.scores.Score
- net.minecraft.world.scores.ScoreAccess
+ net.minecraft.world.scores.Scoreboard
- net.minecraft.world.scores.Scoreboard$1
+ net.minecraft.world.scores.ScoreboardSaveData
+ net.minecraft.world.scores.ScoreHolder
- net.minecraft.world.scores.ScoreHolder$1
+ net.minecraft.world.scores.ScoreHolder$2
- net.minecraft.world.scores.ScoreHolder$3
- net.minecraft.world.scores.Team
+ net.minecraft.world.scores.Team$CollisionRule
- net.minecraft.world.scores.Team$Visibility
+ net.minecraft.world.SimpleContainer
- net.minecraft.world.SimpleMenuProvider
+ net.minecraft.world.TickRateManager
+ net.minecraft.world.ticks.BlackholeTickAccess
- net.minecraft.world.ticks.BlackholeTickAccess$1
+ net.minecraft.world.ticks.BlackholeTickAccess$2
- net.minecraft.world.ticks.ContainerSingleItem
+ net.minecraft.world.ticks.ContainerSingleItem$BlockContainerSingleItem
- net.minecraft.world.ticks.LevelChunkTicks
+ net.minecraft.world.ticks.LevelTickAccess
- net.minecraft.world.ticks.LevelTicks
+ net.minecraft.world.ticks.LevelTicks$PosAndContainerConsumer
- net.minecraft.world.ticks.package-info
- net.minecraft.world.ticks.ProtoChunkTicks
+ net.minecraft.world.ticks.SavedTick
- net.minecraft.world.ticks.SavedTick$1
+ net.minecraft.world.ticks.ScheduledTick
- net.minecraft.world.ticks.ScheduledTick$1
+ net.minecraft.world.ticks.SerializableTickContainer
- net.minecraft.world.ticks.TickAccess
+ net.minecraft.world.ticks.TickContainerAccess
- net.minecraft.world.ticks.TickPriority
+ net.minecraft.world.ticks.WorldGenTickAccess
- net.minecraft.world.WorldlyContainer
+ net.minecraft.world.WorldlyContainerHolder
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