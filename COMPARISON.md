## Comparison with [20w20b](https://github.com/PixiGeko/Minecraft-generated-data/tree/20w20b)

- [Version data](#version-data)
- [Registries](#registries)
- [Tags](#tags)
- [Commands](#commands)
- [Translations](#translations)
- [File structure](#file-structure)
- [Mappings](#mappings)
  - [Server](#server)
  - [Client](#client)

<hr/>
<details><summary>Version data</summary>
<table><tr><th></th><th align="left">20w20b</th><th>20w21a</th></tr><tr><td>World version</td><td><code>2537</code></td><td><code>2554</code></td></tr><tr><td>Protocol version</td><td><code>717</code></td><td><code>718</code></td></tr></table>
</details>
<details><summary>Registries</summary>
<details>
<summary>
List
</summary>

```diff
- biome_source_type.txt
+ biome_source.txt
+ chunk_generator.txt
- dimension_type.txt
```

</details>






<details>
<summary>
block_state_provider_type.txt
</summary>

```diff
+ minecraft:rotated_block_provider
```

</details>






<details>
<summary>
feature.txt
</summary>

```diff
- minecraft:bastion_remnant
- minecraft:buried_treasure
- minecraft:desert_pyramid
- minecraft:end_city
- minecraft:igloo
- minecraft:jungle_temple
- minecraft:mineshaft
- minecraft:nether_bridge
- minecraft:nether_fossil
- minecraft:ocean_monument
- minecraft:ocean_ruin
- minecraft:pillager_outpost
- minecraft:ruined_portal
- minecraft:shipwreck
- minecraft:stronghold
- minecraft:swamp_hut
- minecraft:village
- minecraft:woodland_mansion
```

</details>

















<details>
<summary>
sound_event.txt
</summary>

```diff
+ minecraft:entity.donkey.eat
+ minecraft:entity.fox.teleport
+ minecraft:entity.mule.angry
+ minecraft:entity.mule.eat
+ minecraft:entity.parrot.imitate.hoglin
+ minecraft:entity.parrot.imitate.piglin
+ minecraft:entity.parrot.imitate.zoglin
```

</details>
</details>
<details><summary>Tags</summary>
<details>
<summary>
List
</summary>

```diff
- universal_tags/biome_source_type.json
+ universal_tags/biome_source.json
+ universal_tags/chunk_generator.json
- universal_tags/dimension_type.json
```

</details>












<details>
<summary>
universal_tags/block_state_provider_type.json
</summary>

```diff
+ minecraft:rotated_block_provider
```

</details>






<details>
<summary>
universal_tags/feature.json
</summary>

```diff
- minecraft:bastion_remnant
- minecraft:buried_treasure
- minecraft:desert_pyramid
- minecraft:end_city
- minecraft:igloo
- minecraft:jungle_temple
- minecraft:mineshaft
- minecraft:nether_bridge
- minecraft:nether_fossil
- minecraft:ocean_monument
- minecraft:ocean_ruin
- minecraft:pillager_outpost
- minecraft:ruined_portal
- minecraft:shipwreck
- minecraft:stronghold
- minecraft:swamp_hut
- minecraft:village
- minecraft:woodland_mansion
```

</details>

















<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:entity.donkey.eat
+ minecraft:entity.fox.teleport
+ minecraft:entity.mule.angry
+ minecraft:entity.mule.eat
+ minecraft:entity.parrot.imitate.hoglin
+ minecraft:entity.parrot.imitate.piglin
+ minecraft:entity.parrot.imitate.zoglin
```

</details>
</details>
<details><summary>Commands</summary>
<details>
<summary>
locate
</summary>

```diff
+ locate bastion_remnant
- locate Bastion_Remnant
+ locate buried_treasure
- locate Buried_Treasure
+ locate desert_pyramid
- locate Desert_Pyramid
+ locate endcity
- locate EndCity
+ locate fortress
- locate Fortress
+ locate igloo
- locate Igloo
+ locate jungle_pyramid
- locate Jungle_Pyramid
+ locate mansion
- locate Mansion
+ locate mineshaft
- locate Mineshaft
+ locate monument
- locate Monument
+ locate nether_fossil
- locate Nether_Fossil
+ locate ocean_ruin
- locate Ocean_Ruin
+ locate pillager_outpost
- locate Pillager_Outpost
+ locate ruined_portal
- locate Ruined_Portal
+ locate shipwreck
- locate Shipwreck
+ locate stronghold
- locate Stronghold
+ locate swamp_hut
- locate Swamp_Hut
+ locate village
- locate Village
```

</details>

























<details>
<summary>
spreadplayers
</summary>

```diff
+ spreadplayers <center: vec2> <spreadDistance: float> <maxRange: float> under <maxHeight: integer> <respectTeams: bool> <targets: entity>
```

</details>
</details>
<details><summary>Translations</summary>
<details>
<summary>
Keys
</summary>

```diff
- createWorld.customize.buffet.generator: Please select a generator type
- createWorld.customize.buffet.generatortype: World generator:
- generator.buffet: Buffet
+ generator.custom: Custom
+ generator.large_biomes: Large Biomes
- generator.largeBiomes: Large Biomes
- generator.minecraft.caves: Caves
- generator.minecraft.floating_islands: Floating Islands
- generator.minecraft.surface: Surface
+ generator.single_biome_caves: Caves
+ generator.single_biome_floating_islands: Floating islands
+ generator.single_biome_surface: Single Biome
+ selectWorld.backupQuestion.experimental: Worlds using Experimental Settings are not supported
+ selectWorld.backupWarning.experimental: This world uses experimental settings that could stop working at any time. We cannot guarantee it will load or work. Here be dragons!
+ selectWorld.edit.export_worldgen_settings: Export World Generation Settings
+ selectWorld.edit.export_worldgen_settings.failure: Export failed
+ selectWorld.edit.export_worldgen_settings.success: Exported
+ selectWorld.import_worldgen_settings: Import settings
+ selectWorld.import_worldgen_settings.deprecated.question: Some features used are deprecated and will stop working in the future. Do you wish to proceed?
+ selectWorld.import_worldgen_settings.deprecated.title: Warning! These settings are using deprecated features
+ selectWorld.import_worldgen_settings.experimental.question: These settings are experimental and could one day stop working. Do you wish to proceed?
+ selectWorld.import_worldgen_settings.experimental.title: Warning! These settings are using experimental features
+ selectWorld.import_worldgen_settings.failure: Error importing settings
+ selectWorld.import_worldgen_settings.select_file: Select settings file (.json)
+ selectWorld.tooltip.experimental: This world is using experimental settings
+ subtitles.block.portal.travel: Portal noise fades
+ subtitles.block.portal.trigger: Portal noise intensifies
+ subtitles.entity.cat.purr: Cat purrs
+ subtitles.entity.donkey.eat: Donkey eats
+ subtitles.entity.fox.teleport: Fox teleports
- subtitles.entity.horse.land: Horse lands
+ subtitles.entity.mule.angry: Mule neighs
+ subtitles.entity.mule.eat: Mule eats
+ subtitles.entity.parrot.imitate.hoglin: Parrot growls
+ subtitles.entity.parrot.imitate.piglin: Parrot snorts
+ subtitles.entity.parrot.imitate.zoglin: Parrot growls
+ subtitles.entity.zombie.attack_wooden_door: Door shakes
+ subtitles.entity.zombie.break_wooden_door: Door breaks
+ subtitles.ui.cartography_table.take_result: Map drawn
+ subtitles.ui.loom.take_result: Loom used
+ subtitles.ui.stonecutter.take_result: Stonecutter used
+ title.multiplayer.disabled: Multiplayer is disabled, please check your launcher settings.
```

</details>
<details>
<summary>
Changes
</summary>

```
generator.customized: Old Customized
subtitles.block.blastfurnace.fire_crackle: Blast fFurnace crackles
subtitles.block.enchantment_table.use: Enchanting tTable used
subtitles.block.respawn_anchor.charge: Respawn aAnchor is charged
subtitles.block.respawn_anchor.deplete: Respawn aAnchor depletes
subtitles.block.respawn_anchor.set_spawn: Respawn aAnchor sets spawn
subtitles.entity.turtle.egg_break: Turtle eEgg breaks
subtitles.entity.turtle.egg_crack: Turtle eEgg cracks
subtitles.entity.turtle.egg_hatch: Turtle eEgg hatches
subtitles.entity.zombie_villager.converted: Zombie Villager vociferates
subtitles.entity.zombie_villager.cure: Zombie Villager snuffles
```

</details>
</details>
<details><summary>File structure</summary>
<details>
<summary>
assets
</summary>

```diff
- minecraft/textures/gui/title/mojang.png
+ minecraft/textures/gui/title/mojangstudios.png
+ minecraft/textures/item/nether_sprouts.png
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
+ net.minecraft.core.MapFiller
- net.minecraft.core.MappedRegistry
+ net.minecraft.core.NonNullList
- net.minecraft.core.particles.package-info
- net.minecraft.core.particles.SimpleParticleType
+ net.minecraft.core.particles.SimpleParticleType$1
- net.minecraft.core.Position
+ net.minecraft.core.PositionImpl
- net.minecraft.core.Registry
- net.minecraft.core.RegistryAccess$RegistryHolder
+ net.minecraft.core.Rotations
- net.minecraft.core.SectionPos
+ net.minecraft.core.SectionPos$1
+ net.minecraft.data.advancements.AdvancementProvider
- net.minecraft.data.advancements.AdventureAdvancements
+ net.minecraft.data.advancements.HusbandryAdvancements
- net.minecraft.data.advancements.NetherAdvancements
+ net.minecraft.data.advancements.package-info
+ net.minecraft.data.advancements.StoryAdvancements
- net.minecraft.data.advancements.TheEndAdvancements
+ net.minecraft.data.DataGenerator
- net.minecraft.data.DataProvider
+ net.minecraft.data.HashCache
- net.minecraft.data.info.BlockListReport
+ net.minecraft.data.info.CommandsReport
+ net.minecraft.data.info.package-info
- net.minecraft.data.info.RegistryDumpReport
- net.minecraft.data.loot.BlockLoot
+ net.minecraft.data.loot.ChestLoot
- net.minecraft.data.loot.EntityLoot
+ net.minecraft.data.loot.FishingLoot
- net.minecraft.data.loot.GiftLoot
+ net.minecraft.data.loot.LootTableProvider
+ net.minecraft.data.loot.package-info
- net.minecraft.data.loot.PiglinBarterLoot
- net.minecraft.data.Main
- net.minecraft.data.models.BlockModelGenerators
+ net.minecraft.data.models.BlockModelGenerators$1
- net.minecraft.data.models.BlockModelGenerators$BlockEntityModelGenerator
+ net.minecraft.data.models.BlockModelGenerators$BlockFamilyProvider
- net.minecraft.data.models.BlockModelGenerators$TintState
+ net.minecraft.data.models.BlockModelGenerators$WoodProvider
- net.minecraft.data.models.blockstates.BlockStateGenerator
+ net.minecraft.data.models.blockstates.Condition
- net.minecraft.data.models.blockstates.Condition$1
+ net.minecraft.data.models.blockstates.Condition$CompositeCondition
- net.minecraft.data.models.blockstates.Condition$Operation
+ net.minecraft.data.models.blockstates.Condition$TerminalCondition
- net.minecraft.data.models.blockstates.MultiPartGenerator
+ net.minecraft.data.models.blockstates.MultiPartGenerator$1
- net.minecraft.data.models.blockstates.MultiPartGenerator$ConditionalEntry
+ net.minecraft.data.models.blockstates.MultiPartGenerator$Entry
- net.minecraft.data.models.blockstates.MultiVariantGenerator
- net.minecraft.data.models.blockstates.package-info
+ net.minecraft.data.models.blockstates.PropertyDispatch
- net.minecraft.data.models.blockstates.PropertyDispatch$1
+ net.minecraft.data.models.blockstates.PropertyDispatch$C1
- net.minecraft.data.models.blockstates.PropertyDispatch$C2
+ net.minecraft.data.models.blockstates.PropertyDispatch$C3
- net.minecraft.data.models.blockstates.PropertyDispatch$C4
+ net.minecraft.data.models.blockstates.PropertyDispatch$C5
- net.minecraft.data.models.blockstates.PropertyDispatch$PentaFunction
+ net.minecraft.data.models.blockstates.PropertyDispatch$QuadFunction
- net.minecraft.data.models.blockstates.PropertyDispatch$TriFunction
+ net.minecraft.data.models.blockstates.PropertyValue
- net.minecraft.data.models.blockstates.Selector
+ net.minecraft.data.models.blockstates.Variant
- net.minecraft.data.models.blockstates.VariantProperties
+ net.minecraft.data.models.blockstates.VariantProperties$Rotation
- net.minecraft.data.models.blockstates.VariantProperty
+ net.minecraft.data.models.blockstates.VariantProperty$Value
- net.minecraft.data.models.ItemModelGenerators
+ net.minecraft.data.models.model.DelegatedModel
- net.minecraft.data.models.model.ModelLocationUtils
+ net.minecraft.data.models.model.ModelTemplate
- net.minecraft.data.models.model.ModelTemplates
+ net.minecraft.data.models.model.package-info
+ net.minecraft.data.models.model.TexturedModel
- net.minecraft.data.models.model.TexturedModel$Provider
+ net.minecraft.data.models.model.TextureMapping
- net.minecraft.data.models.model.TextureSlot
+ net.minecraft.data.models.ModelProvider
- net.minecraft.data.models.package-info
+ net.minecraft.data.package-info
- net.minecraft.data.recipes.FinishedRecipe
- net.minecraft.data.recipes.package-info
+ net.minecraft.data.recipes.RecipeProvider
- net.minecraft.data.recipes.ShapedRecipeBuilder
+ net.minecraft.data.recipes.ShapedRecipeBuilder$Result
- net.minecraft.data.recipes.ShapelessRecipeBuilder
+ net.minecraft.data.recipes.ShapelessRecipeBuilder$Result
- net.minecraft.data.recipes.SimpleCookingRecipeBuilder
+ net.minecraft.data.recipes.SimpleCookingRecipeBuilder$Result
- net.minecraft.data.recipes.SingleItemRecipeBuilder
+ net.minecraft.data.recipes.SingleItemRecipeBuilder$Result
- net.minecraft.data.recipes.SpecialRecipeBuilder
+ net.minecraft.data.recipes.SpecialRecipeBuilder$1
+ net.minecraft.data.structures.NbtToSnbt
- net.minecraft.data.structures.package-info
- net.minecraft.data.structures.SnbtToNbt
+ net.minecraft.data.structures.SnbtToNbt$Filter
- net.minecraft.data.structures.SnbtToNbt$TaskResult
+ net.minecraft.data.structures.StructureUpdater
+ net.minecraft.data.tags.BlockTagsProvider
- net.minecraft.data.tags.EntityTypeTagsProvider
+ net.minecraft.data.tags.FluidTagsProvider
- net.minecraft.data.tags.ItemTagsProvider
- net.minecraft.data.tags.package-info
+ net.minecraft.data.tags.TagsProvider
- net.minecraft.data.tags.TagsProvider$1
+ net.minecraft.data.tags.TagsProvider$TagAppender
+ net.minecraft.gametest.framework.BeforeBatch
- net.minecraft.gametest.framework.GameTest
+ net.minecraft.gametest.framework.GameTestAssertException
- net.minecraft.gametest.framework.GameTestAssertPosException
+ net.minecraft.gametest.framework.GameTestBatch
- net.minecraft.gametest.framework.GameTestBatchRunner
+ net.minecraft.gametest.framework.GameTestBatchRunner$1
- net.minecraft.gametest.framework.GameTestEvent
+ net.minecraft.gametest.framework.GameTestGenerator
- net.minecraft.gametest.framework.GameTestHelper
+ net.minecraft.gametest.framework.GameTestInfo
- net.minecraft.gametest.framework.GameTestListener
+ net.minecraft.gametest.framework.GameTestRegistry
- net.minecraft.gametest.framework.GameTestRunner
+ net.minecraft.gametest.framework.GameTestRunner$1
- net.minecraft.gametest.framework.GameTestSequence
+ net.minecraft.gametest.framework.GameTestSequence$Condition
- net.minecraft.gametest.framework.GameTestServer
+ net.minecraft.gametest.framework.GameTestServer$1
- net.minecraft.gametest.framework.GameTestTicker
+ net.minecraft.gametest.framework.GameTestTimeoutException
- net.minecraft.gametest.framework.JUnitLikeTestReporter
+ net.minecraft.gametest.framework.LogTestReporter
- net.minecraft.gametest.framework.MultipleTestTracker
+ net.minecraft.gametest.framework.package-info
+ net.minecraft.gametest.framework.StructureUtils
- net.minecraft.gametest.framework.TeamcityTestReporter
+ net.minecraft.gametest.framework.TestClassNameArgument
- net.minecraft.gametest.framework.TestCommand
+ net.minecraft.gametest.framework.TestCommand$TestSummaryDisplayer
- net.minecraft.gametest.framework.TestFunction
+ net.minecraft.gametest.framework.TestFunctionArgument
- net.minecraft.gametest.framework.TestReporter
- net.minecraft.locale.Language
+ net.minecraft.locale.package-info
- net.minecraft.nbt.ByteArrayTag
+ net.minecraft.nbt.ByteArrayTag$1
- net.minecraft.nbt.ByteTag
+ net.minecraft.nbt.ByteTag$1
- net.minecraft.nbt.ByteTag$Cache
+ net.minecraft.nbt.CollectionTag
- net.minecraft.nbt.CompoundTag
+ net.minecraft.nbt.CompoundTag$1
- net.minecraft.nbt.DoubleTag
+ net.minecraft.nbt.DoubleTag$1
- net.minecraft.nbt.EndTag
+ net.minecraft.nbt.EndTag$1
- net.minecraft.nbt.FloatTag
+ net.minecraft.nbt.FloatTag$1
- net.minecraft.nbt.IntArrayTag
+ net.minecraft.nbt.IntArrayTag$1
- net.minecraft.nbt.IntTag
+ net.minecraft.nbt.IntTag$1
- net.minecraft.nbt.IntTag$Cache
+ net.minecraft.nbt.ListTag
- net.minecraft.nbt.ListTag$1
+ net.minecraft.nbt.LongArrayTag
- net.minecraft.nbt.LongArrayTag$1
+ net.minecraft.nbt.LongTag
- net.minecraft.nbt.LongTag$1
+ net.minecraft.nbt.LongTag$Cache
- net.minecraft.nbt.NbtAccounter
+ net.minecraft.nbt.NbtAccounter$1
- net.minecraft.nbt.NbtIo
+ net.minecraft.nbt.NbtOps
- net.minecraft.nbt.NbtOps$1
- net.minecraft.nbt.NbtUtils
+ net.minecraft.nbt.NumericTag
- net.minecraft.nbt.package-info
- net.minecraft.nbt.ShortTag
+ net.minecraft.nbt.ShortTag$1
- net.minecraft.nbt.ShortTag$Cache
+ net.minecraft.nbt.StringTag
- net.minecraft.nbt.StringTag$1
+ net.minecraft.nbt.Tag
- net.minecraft.nbt.TagParser
+ net.minecraft.nbt.TagType
- net.minecraft.nbt.TagType$1
+ net.minecraft.nbt.TagTypes
+ net.minecraft.network.chat.BaseComponent
- net.minecraft.network.chat.ChatType
+ net.minecraft.network.chat.ClickEvent
- net.minecraft.network.chat.ClickEvent$Action
+ net.minecraft.network.chat.CommonComponents
- net.minecraft.network.chat.Component
+ net.minecraft.network.chat.Component$ContentConsumer
- net.minecraft.network.chat.Component$Serializer
+ net.minecraft.network.chat.Component$StyledContentConsumer
- net.minecraft.network.chat.ComponentUtils
+ net.minecraft.network.chat.ContextAwareComponent
- net.minecraft.network.chat.HoverEvent
+ net.minecraft.network.chat.HoverEvent$Action
- net.minecraft.network.chat.HoverEvent$EntityTooltipInfo
+ net.minecraft.network.chat.HoverEvent$ItemStackInfo
- net.minecraft.network.chat.KeybindComponent
+ net.minecraft.network.chat.MutableComponent
- net.minecraft.network.chat.NbtComponent
+ net.minecraft.network.chat.NbtComponent$BlockNbtComponent
- net.minecraft.network.chat.NbtComponent$EntityNbtComponent
+ net.minecraft.network.chat.NbtComponent$StorageNbtComponent
+ net.minecraft.network.chat.package-info
- net.minecraft.network.chat.ScoreComponent
+ net.minecraft.network.chat.SelectorComponent
- net.minecraft.network.chat.Style
+ net.minecraft.network.chat.Style$1
- net.minecraft.network.chat.Style$Serializer
+ net.minecraft.network.chat.TextColor
- net.minecraft.network.chat.TextComponent
+ net.minecraft.network.chat.TranslatableComponent
- net.minecraft.network.chat.TranslatableFormatException
+ net.minecraft.network.CipherBase
- net.minecraft.network.CipherDecoder
+ net.minecraft.network.CipherEncoder
- net.minecraft.network.CompressionDecoder
+ net.minecraft.network.CompressionEncoder
- net.minecraft.network.Connection
+ net.minecraft.network.Connection$1
- net.minecraft.network.Connection$2
+ net.minecraft.network.Connection$PacketHolder
- net.minecraft.network.ConnectionProtocol
+ net.minecraft.network.ConnectionProtocol$1
- net.minecraft.network.ConnectionProtocol$PacketSet
+ net.minecraft.network.ConnectionProtocol$ProtocolBuilder
- net.minecraft.network.FriendlyByteBuf
- net.minecraft.network.package-info
+ net.minecraft.network.PacketDecoder
- net.minecraft.network.PacketEncoder
+ net.minecraft.network.PacketListener
+ net.minecraft.network.protocol.game.ClientboundAddEntityPacket
- net.minecraft.network.protocol.game.ClientboundAddExperienceOrbPacket
+ net.minecraft.network.protocol.game.ClientboundAddGlobalEntityPacket
- net.minecraft.network.protocol.game.ClientboundAddMobPacket
+ net.minecraft.network.protocol.game.ClientboundAddPaintingPacket
- net.minecraft.network.protocol.game.ClientboundAddPlayerPacket
+ net.minecraft.network.protocol.game.ClientboundAnimatePacket
- net.minecraft.network.protocol.game.ClientboundAwardStatsPacket
+ net.minecraft.network.protocol.game.ClientboundBlockBreakAckPacket
- net.minecraft.network.protocol.game.ClientboundBlockDestructionPacket
+ net.minecraft.network.protocol.game.ClientboundBlockEntityDataPacket
- net.minecraft.network.protocol.game.ClientboundBlockEventPacket
+ net.minecraft.network.protocol.game.ClientboundBlockUpdatePacket
- net.minecraft.network.protocol.game.ClientboundBossEventPacket
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket$1
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$Operation
+ net.minecraft.network.protocol.game.ClientboundChangeDifficultyPacket
- net.minecraft.network.protocol.game.ClientboundChatPacket
+ net.minecraft.network.protocol.game.ClientboundChunkBlocksUpdatePacket
- net.minecraft.network.protocol.game.ClientboundChunkBlocksUpdatePacket$BlockUpdate
- net.minecraft.network.protocol.game.ClientboundCommandsPacket
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket$1
- net.minecraft.network.protocol.game.ClientboundCommandsPacket$Entry
+ net.minecraft.network.protocol.game.ClientboundCommandSuggestionsPacket
+ net.minecraft.network.protocol.game.ClientboundContainerAckPacket
- net.minecraft.network.protocol.game.ClientboundContainerClosePacket
+ net.minecraft.network.protocol.game.ClientboundContainerSetContentPacket
- net.minecraft.network.protocol.game.ClientboundContainerSetDataPacket
+ net.minecraft.network.protocol.game.ClientboundContainerSetSlotPacket
- net.minecraft.network.protocol.game.ClientboundCooldownPacket
+ net.minecraft.network.protocol.game.ClientboundCustomPayloadPacket
- net.minecraft.network.protocol.game.ClientboundCustomSoundPacket
+ net.minecraft.network.protocol.game.ClientboundDisconnectPacket
- net.minecraft.network.protocol.game.ClientboundEntityEventPacket
+ net.minecraft.network.protocol.game.ClientboundExplodePacket
- net.minecraft.network.protocol.game.ClientboundForgetLevelChunkPacket
+ net.minecraft.network.protocol.game.ClientboundGameEventPacket
- net.minecraft.network.protocol.game.ClientboundHorseScreenOpenPacket
+ net.minecraft.network.protocol.game.ClientboundKeepAlivePacket
- net.minecraft.network.protocol.game.ClientboundLevelChunkPacket
+ net.minecraft.network.protocol.game.ClientboundLevelEventPacket
- net.minecraft.network.protocol.game.ClientboundLevelParticlesPacket
+ net.minecraft.network.protocol.game.ClientboundLightUpdatePacket
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
+ net.minecraft.network.protocol.game.ClientboundPlayerCombatPacket
- net.minecraft.network.protocol.game.ClientboundPlayerCombatPacket$1
+ net.minecraft.network.protocol.game.ClientboundPlayerCombatPacket$Event
- net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$1
- net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$Action
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$PlayerUpdate
- net.minecraft.network.protocol.game.ClientboundPlayerLookAtPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerPositionPacket
- net.minecraft.network.protocol.game.ClientboundPlayerPositionPacket$RelativeArgument
+ net.minecraft.network.protocol.game.ClientboundRecipePacket
- net.minecraft.network.protocol.game.ClientboundRecipePacket$State
+ net.minecraft.network.protocol.game.ClientboundRemoveEntitiesPacket
- net.minecraft.network.protocol.game.ClientboundRemoveMobEffectPacket
+ net.minecraft.network.protocol.game.ClientboundResourcePackPacket
- net.minecraft.network.protocol.game.ClientboundRespawnPacket
+ net.minecraft.network.protocol.game.ClientboundRotateHeadPacket
- net.minecraft.network.protocol.game.ClientboundSelectAdvancementsTabPacket
+ net.minecraft.network.protocol.game.ClientboundSetBorderPacket
- net.minecraft.network.protocol.game.ClientboundSetBorderPacket$1
+ net.minecraft.network.protocol.game.ClientboundSetBorderPacket$Type
- net.minecraft.network.protocol.game.ClientboundSetCameraPacket
+ net.minecraft.network.protocol.game.ClientboundSetCarriedItemPacket
- net.minecraft.network.protocol.game.ClientboundSetChunkCacheCenterPacket
+ net.minecraft.network.protocol.game.ClientboundSetChunkCacheRadiusPacket
- net.minecraft.network.protocol.game.ClientboundSetDefaultSpawnPositionPacket
+ net.minecraft.network.protocol.game.ClientboundSetDisplayObjectivePacket
- net.minecraft.network.protocol.game.ClientboundSetEntityDataPacket
+ net.minecraft.network.protocol.game.ClientboundSetEntityLinkPacket
- net.minecraft.network.protocol.game.ClientboundSetEntityMotionPacket
+ net.minecraft.network.protocol.game.ClientboundSetEquippedItemPacket
- net.minecraft.network.protocol.game.ClientboundSetExperiencePacket
+ net.minecraft.network.protocol.game.ClientboundSetHealthPacket
- net.minecraft.network.protocol.game.ClientboundSetObjectivePacket
+ net.minecraft.network.protocol.game.ClientboundSetPassengersPacket
- net.minecraft.network.protocol.game.ClientboundSetPlayerTeamPacket
+ net.minecraft.network.protocol.game.ClientboundSetScorePacket
- net.minecraft.network.protocol.game.ClientboundSetTimePacket
+ net.minecraft.network.protocol.game.ClientboundSetTitlesPacket
- net.minecraft.network.protocol.game.ClientboundSetTitlesPacket$Type
+ net.minecraft.network.protocol.game.ClientboundSoundEntityPacket
- net.minecraft.network.protocol.game.ClientboundSoundPacket
+ net.minecraft.network.protocol.game.ClientboundStopSoundPacket
- net.minecraft.network.protocol.game.ClientboundTabListPacket
+ net.minecraft.network.protocol.game.ClientboundTagQueryPacket
- net.minecraft.network.protocol.game.ClientboundTakeItemEntityPacket
+ net.minecraft.network.protocol.game.ClientboundTeleportEntityPacket
- net.minecraft.network.protocol.game.ClientboundUpdateAdvancementsPacket
+ net.minecraft.network.protocol.game.ClientboundUpdateAttributesPacket
- net.minecraft.network.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
+ net.minecraft.network.protocol.game.ClientboundUpdateMobEffectPacket
- net.minecraft.network.protocol.game.ClientboundUpdateRecipesPacket
+ net.minecraft.network.protocol.game.ClientboundUpdateTagsPacket
- net.minecraft.network.protocol.game.ClientGamePacketListener
- net.minecraft.network.protocol.game.DebugEntityNameGenerator
+ net.minecraft.network.protocol.game.DebugPackets
+ net.minecraft.network.protocol.game.package-info
+ net.minecraft.network.protocol.game.ServerboundAcceptTeleportationPacket
- net.minecraft.network.protocol.game.ServerboundBlockEntityTagQuery
+ net.minecraft.network.protocol.game.ServerboundChangeDifficultyPacket
- net.minecraft.network.protocol.game.ServerboundChatPacket
+ net.minecraft.network.protocol.game.ServerboundClientCommandPacket
- net.minecraft.network.protocol.game.ServerboundClientCommandPacket$Action
+ net.minecraft.network.protocol.game.ServerboundClientInformationPacket
- net.minecraft.network.protocol.game.ServerboundCommandSuggestionPacket
+ net.minecraft.network.protocol.game.ServerboundContainerAckPacket
- net.minecraft.network.protocol.game.ServerboundContainerButtonClickPacket
+ net.minecraft.network.protocol.game.ServerboundContainerClickPacket
- net.minecraft.network.protocol.game.ServerboundContainerClosePacket
+ net.minecraft.network.protocol.game.ServerboundCustomPayloadPacket
- net.minecraft.network.protocol.game.ServerboundEditBookPacket
+ net.minecraft.network.protocol.game.ServerboundEntityTagQuery
- net.minecraft.network.protocol.game.ServerboundInteractPacket
+ net.minecraft.network.protocol.game.ServerboundInteractPacket$Action
- net.minecraft.network.protocol.game.ServerboundJigsawGeneratePacket
+ net.minecraft.network.protocol.game.ServerboundKeepAlivePacket
- net.minecraft.network.protocol.game.ServerboundLockDifficultyPacket
+ net.minecraft.network.protocol.game.ServerboundMovePlayerPacket
- net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$Pos
+ net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$PosRot
- net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$Rot
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
+ net.minecraft.network.protocol.game.ServerboundRecipeBookUpdatePacket
- net.minecraft.network.protocol.game.ServerboundRecipeBookUpdatePacket$Purpose
+ net.minecraft.network.protocol.game.ServerboundRenameItemPacket
- net.minecraft.network.protocol.game.ServerboundResourcePackPacket
+ net.minecraft.network.protocol.game.ServerboundResourcePackPacket$Action
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
- net.minecraft.network.protocol.game.ServerGamePacketListener
- net.minecraft.network.protocol.handshake.ClientIntentionPacket
- net.minecraft.network.protocol.handshake.package-info
+ net.minecraft.network.protocol.handshake.ServerHandshakePacketListener
- net.minecraft.network.protocol.login.ClientboundCustomQueryPacket
+ net.minecraft.network.protocol.login.ClientboundGameProfilePacket
- net.minecraft.network.protocol.login.ClientboundHelloPacket
+ net.minecraft.network.protocol.login.ClientboundLoginCompressionPacket
- net.minecraft.network.protocol.login.ClientboundLoginDisconnectPacket
+ net.minecraft.network.protocol.login.ClientLoginPacketListener
+ net.minecraft.network.protocol.login.package-info
- net.minecraft.network.protocol.login.ServerboundCustomQueryPacket
+ net.minecraft.network.protocol.login.ServerboundHelloPacket
- net.minecraft.network.protocol.login.ServerboundKeyPacket
+ net.minecraft.network.protocol.login.ServerLoginPacketListener
- net.minecraft.network.protocol.package-info
+ net.minecraft.network.protocol.Packet
- net.minecraft.network.protocol.PacketFlow
+ net.minecraft.network.protocol.PacketUtils
- net.minecraft.network.protocol.status.ClientboundPongResponsePacket
+ net.minecraft.network.protocol.status.ClientboundStatusResponsePacket
+ net.minecraft.network.protocol.status.ClientStatusPacketListener
+ net.minecraft.network.protocol.status.package-info
+ net.minecraft.network.protocol.status.ServerboundPingRequestPacket
- net.minecraft.network.protocol.status.ServerboundStatusRequestPacket
- net.minecraft.network.protocol.status.ServerStatus
+ net.minecraft.network.protocol.status.ServerStatus$Players
- net.minecraft.network.protocol.status.ServerStatus$Players$Serializer
+ net.minecraft.network.protocol.status.ServerStatus$Serializer
- net.minecraft.network.protocol.status.ServerStatus$Version
+ net.minecraft.network.protocol.status.ServerStatus$Version$Serializer
- net.minecraft.network.protocol.status.ServerStatusPacketListener
- net.minecraft.network.SkipPacketException
- net.minecraft.network.syncher.EntityDataAccessor
+ net.minecraft.network.syncher.EntityDataSerializer
- net.minecraft.network.syncher.EntityDataSerializers
+ net.minecraft.network.syncher.EntityDataSerializers$1
- net.minecraft.network.syncher.EntityDataSerializers$10
+ net.minecraft.network.syncher.EntityDataSerializers$11
- net.minecraft.network.syncher.EntityDataSerializers$12
+ net.minecraft.network.syncher.EntityDataSerializers$13
- net.minecraft.network.syncher.EntityDataSerializers$14
+ net.minecraft.network.syncher.EntityDataSerializers$15
- net.minecraft.network.syncher.EntityDataSerializers$16
+ net.minecraft.network.syncher.EntityDataSerializers$17
- net.minecraft.network.syncher.EntityDataSerializers$18
+ net.minecraft.network.syncher.EntityDataSerializers$19
- net.minecraft.network.syncher.EntityDataSerializers$2
+ net.minecraft.network.syncher.EntityDataSerializers$3
- net.minecraft.network.syncher.EntityDataSerializers$4
+ net.minecraft.network.syncher.EntityDataSerializers$5
- net.minecraft.network.syncher.EntityDataSerializers$6
+ net.minecraft.network.syncher.EntityDataSerializers$7
- net.minecraft.network.syncher.EntityDataSerializers$8
+ net.minecraft.network.syncher.EntityDataSerializers$9
- net.minecraft.network.syncher.package-info
- net.minecraft.network.syncher.SynchedEntityData
+ net.minecraft.network.syncher.SynchedEntityData$DataItem
+ net.minecraft.network.Varint21FrameDecoder
- net.minecraft.network.Varint21LengthFieldPrepender
+ net.minecraft.obfuscate.DontObfuscateOrShrink
- net.minecraft.obfuscate.KeepAfterObfuscation
+ net.minecraft.obfuscate.package-info
- net.minecraft.package-info
- net.minecraft.recipebook.package-info
+ net.minecraft.recipebook.PlaceRecipe
- net.minecraft.recipebook.ServerPlaceRecipe
+ net.minecraft.recipebook.ServerPlaceSmeltingRecipe
+ net.minecraft.server.level.DerivedServerLevel
- net.minecraft.server.level.DistanceManager
+ net.minecraft.server.level.DistanceManager$ChunkTicketTracker
- net.minecraft.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
+ net.minecraft.server.level.DistanceManager$PlayerTicketTracker
- net.minecraft.server.level.FeatureSimulator
+ net.minecraft.server.level.PlayerMap
- net.minecraft.server.level.PlayerRespawnLogic
- net.minecraft.util.datafix.DataFixers
+ net.minecraft.util.datafix.DataFixers$1
- net.minecraft.util.datafix.DataFixers$2
+ net.minecraft.util.datafix.DataFixTypes
- net.minecraft.util.datafix.fixes.OminousBannerBlockEntityRenameFix
- net.minecraft.util.datafix.fixes.WorldGenSettingsFix
+ net.minecraft.util.datafix.OminousBannerBlockEntityRenameFix
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
+ net.minecraft.util.Deserializer
- net.minecraft.util.DirectoryLock
+ net.minecraft.util.DirectoryLock$LockException
- net.minecraft.util.ExceptionCollector
+ net.minecraft.util.FastColor
- net.minecraft.util.FastColor$ARGB32
+ net.minecraft.util.FrameTimer
- net.minecraft.util.GsonHelper
+ net.minecraft.util.HttpUtil
- net.minecraft.util.InsensitiveStringMap
+ net.minecraft.util.IntRange
- net.minecraft.util.LazyLoadedValue
+ net.minecraft.util.LimitedCapacityList
- net.minecraft.util.LinearCongruentialGenerator
+ net.minecraft.util.LowerCaseEnumTypeAdapterFactory
- net.minecraft.util.LowerCaseEnumTypeAdapterFactory$1
+ net.minecraft.util.Mth
- net.minecraft.util.ProgressListener
+ net.minecraft.util.RewindableStream
- net.minecraft.util.RewindableStream$1
+ net.minecraft.util.Serializable
+ net.minecraft.util.SmoothDouble
- net.minecraft.util.SortedArraySet
+ net.minecraft.util.SortedArraySet$1
- net.minecraft.util.SortedArraySet$ArrayIterator
+ net.minecraft.util.StringRepresentable
- net.minecraft.util.StringRepresentable$1
- net.minecraft.util.StringUtil
+ net.minecraft.util.TimeUtil
- net.minecraft.util.Tuple
+ net.minecraft.util.Unit
- net.minecraft.util.VisibleForDebug
+ net.minecraft.util.WeighedRandom
- net.minecraft.util.WeighedRandom$WeighedRandomItem
- net.minecraft.world.entity.ai.attributes.Attribute
+ net.minecraft.world.entity.ai.attributes.AttributeInstance
- net.minecraft.world.entity.ai.attributes.AttributeMap
+ net.minecraft.world.entity.ai.attributes.AttributeModifier
- net.minecraft.world.entity.ai.attributes.AttributeModifier$Operation
+ net.minecraft.world.entity.ai.attributes.Attributes
+ net.minecraft.world.entity.ai.attributes.AttributeSupplier
- net.minecraft.world.entity.ai.attributes.AttributeSupplier$Builder
- net.minecraft.world.entity.ai.attributes.DefaultAttributes
- net.minecraft.world.entity.ai.attributes.package-info
+ net.minecraft.world.entity.ai.attributes.RangedAttribute
+ net.minecraft.world.entity.ai.behavior.AcquirePoi
- net.minecraft.world.entity.ai.behavior.AnimalMakeLove
+ net.minecraft.world.entity.ai.behavior.AssignProfessionFromJobSite
- net.minecraft.world.entity.ai.behavior.BackUpIfTooClose
+ net.minecraft.world.entity.ai.behavior.BecomePassiveIfMemoryPresent
- net.minecraft.world.entity.ai.behavior.Behavior
+ net.minecraft.world.entity.ai.behavior.Behavior$Status
- net.minecraft.world.entity.ai.behavior.BehaviorUtils
+ net.minecraft.world.entity.ai.behavior.BlockPosTracker
- net.minecraft.world.entity.ai.behavior.CelebrateVillagersSurvivedRaid
+ net.minecraft.world.entity.ai.behavior.CopyMemoryWithExpiry
- net.minecraft.world.entity.ai.behavior.CrossbowAttack
+ net.minecraft.world.entity.ai.behavior.CrossbowAttack$CrossbowState
- net.minecraft.world.entity.ai.behavior.DismountOrSkipMounting
+ net.minecraft.world.entity.ai.behavior.DoNothing
- net.minecraft.world.entity.ai.behavior.EntityTracker
+ net.minecraft.world.entity.ai.behavior.EraseMemoryIf
- net.minecraft.world.entity.ai.behavior.GateBehavior
+ net.minecraft.world.entity.ai.behavior.GateBehavior$1
- net.minecraft.world.entity.ai.behavior.GateBehavior$OrderPolicy
+ net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy
- net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$1
+ net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$2
- net.minecraft.world.entity.ai.behavior.GiveGiftToHero
+ net.minecraft.world.entity.ai.behavior.GoOutsideToCelebrate
- net.minecraft.world.entity.ai.behavior.GoToCelebrateLocation
+ net.minecraft.world.entity.ai.behavior.GoToClosestVillage
- net.minecraft.world.entity.ai.behavior.GoToWantedItem
+ net.minecraft.world.entity.ai.behavior.HarvestFarmland
- net.minecraft.world.entity.ai.behavior.InsideBrownianWalk
+ net.minecraft.world.entity.ai.behavior.InteractWith
- net.minecraft.world.entity.ai.behavior.InteractWithDoor
+ net.minecraft.world.entity.ai.behavior.JumpOnBed
- net.minecraft.world.entity.ai.behavior.LocateHidingPlace
+ net.minecraft.world.entity.ai.behavior.LocateHidingPlaceDuringRaid
- net.minecraft.world.entity.ai.behavior.LookAndFollowTradingPlayerSink
+ net.minecraft.world.entity.ai.behavior.LookAtTargetSink
- net.minecraft.world.entity.ai.behavior.MeleeAttack
+ net.minecraft.world.entity.ai.behavior.Mount
- net.minecraft.world.entity.ai.behavior.MoveToSkySeeingSpot
+ net.minecraft.world.entity.ai.behavior.MoveToTargetSink
- net.minecraft.world.entity.ai.behavior.PlayTagWithOtherKids
+ net.minecraft.world.entity.ai.behavior.PositionTracker
- net.minecraft.world.entity.ai.behavior.RandomStroll
+ net.minecraft.world.entity.ai.behavior.ReactToBell
- net.minecraft.world.entity.ai.behavior.ResetProfession
+ net.minecraft.world.entity.ai.behavior.ResetRaidStatus
- net.minecraft.world.entity.ai.behavior.RingBell
+ net.minecraft.world.entity.ai.behavior.RunIf
- net.minecraft.world.entity.ai.behavior.RunOne
+ net.minecraft.world.entity.ai.behavior.RunSometimes
- net.minecraft.world.entity.ai.behavior.SetClosestHomeAsWalkTarget
+ net.minecraft.world.entity.ai.behavior.SetEntityLookTarget
- net.minecraft.world.entity.ai.behavior.SetHiddenState
+ net.minecraft.world.entity.ai.behavior.SetLookAndInteract
- net.minecraft.world.entity.ai.behavior.SetRaidStatus
+ net.minecraft.world.entity.ai.behavior.SetWalkTargetAwayFrom
- net.minecraft.world.entity.ai.behavior.SetWalkTargetFromAttackTargetIfTargetOutOfReach
+ net.minecraft.world.entity.ai.behavior.SetWalkTargetFromBlockMemory
- net.minecraft.world.entity.ai.behavior.SetWalkTargetFromLookTarget
+ net.minecraft.world.entity.ai.behavior.ShowTradesToPlayer
- net.minecraft.world.entity.ai.behavior.SleepInBed
+ net.minecraft.world.entity.ai.behavior.SocializeAtBell
- net.minecraft.world.entity.ai.behavior.StartAttacking
+ net.minecraft.world.entity.ai.behavior.StartCelebratingIfTargetDead
- net.minecraft.world.entity.ai.behavior.StopAttackingIfTargetInvalid
+ net.minecraft.world.entity.ai.behavior.StopBeingAngryIfTargetDead
- net.minecraft.world.entity.ai.behavior.StrollAroundPoi
+ net.minecraft.world.entity.ai.behavior.StrollToPoi
- net.minecraft.world.entity.ai.behavior.StrollToPoiList
+ net.minecraft.world.entity.ai.behavior.Swim
- net.minecraft.world.entity.ai.behavior.TradeWithVillager
+ net.minecraft.world.entity.ai.behavior.UpdateActivityFromSchedule
- net.minecraft.world.entity.ai.behavior.UseBonemeal
+ net.minecraft.world.entity.ai.behavior.ValidateNearbyPoi
- net.minecraft.world.entity.ai.behavior.VictoryStroll
+ net.minecraft.world.entity.ai.behavior.VillageBoundRandomStroll
- net.minecraft.world.entity.ai.behavior.VillagerCalmDown
+ net.minecraft.world.entity.ai.behavior.VillagerGoalPackages
- net.minecraft.world.entity.ai.behavior.VillagerMakeLove
+ net.minecraft.world.entity.ai.behavior.VillagerPanicTrigger
- net.minecraft.world.entity.ai.behavior.WakeUp
+ net.minecraft.world.entity.ai.behavior.WeightedList
- net.minecraft.world.entity.ai.behavior.WeightedList$1
+ net.minecraft.world.entity.ai.behavior.WeightedList$WeightedEntry
- net.minecraft.world.entity.ai.behavior.WeightedList$WeightedEntry$1
- net.minecraft.world.entity.ai.Brain$MemoryValue
- net.minecraft.world.level.biome.AmbientAdditionsSettings
+ net.minecraft.world.level.biome.AmbientMoodSettings
- net.minecraft.world.level.biome.AmbientParticleSettings
+ net.minecraft.world.level.biome.BadlandsBiome
- net.minecraft.world.level.biome.BadlandsPlateauBiome
+ net.minecraft.world.level.biome.BambooJungleBiome
- net.minecraft.world.level.biome.BambooJungleHillsBiome
+ net.minecraft.world.level.biome.BasaltDeltasBiome
- net.minecraft.world.level.biome.BeachBiome
+ net.minecraft.world.level.biome.Biome
- net.minecraft.world.level.biome.Biome$1
+ net.minecraft.world.level.biome.Biome$BiomeBuilder
- net.minecraft.world.level.biome.Biome$BiomeCategory
+ net.minecraft.world.level.biome.Biome$BiomeTempCategory
- net.minecraft.world.level.biome.Biome$ClimateParameters
+ net.minecraft.world.level.biome.Biome$MobSpawnCost
- net.minecraft.world.level.biome.Biome$Precipitation
+ net.minecraft.world.level.biome.Biome$SpawnerData
- net.minecraft.world.level.biome.BiomeDefaultFeatures
+ net.minecraft.world.level.biome.BiomeManager
- net.minecraft.world.level.biome.BiomeManager$NoiseBiomeSource
+ net.minecraft.world.level.biome.BiomeSource
- net.minecraft.world.level.biome.MushroomFieldsBiome
+ net.minecraft.world.level.biome.MushroomFieldsShoreBiome
- net.minecraft.world.level.biome.NearestNeighborBiomeZoomer
+ net.minecraft.world.level.biome.NetherWastesBiome
- net.minecraft.world.level.biome.OceanBiome
+ net.minecraft.world.level.biome.OverworldBiomeSource
+ net.minecraft.world.level.biome.package-info
- net.minecraft.world.level.biome.PlainsBiome
+ net.minecraft.world.level.biome.RiverBiome
- net.minecraft.world.level.biome.SavannaBiome
+ net.minecraft.world.level.biome.SavannaPlateauBiome
- net.minecraft.world.level.biome.ShatteredSavannaBiome
+ net.minecraft.world.level.biome.ShatteredSavannaPlateauBiome
- net.minecraft.world.level.biome.SmallEndIslandsBiome
+ net.minecraft.world.level.biome.SnowyBeachBiome
- net.minecraft.world.level.biome.SnowyMountainsBiome
+ net.minecraft.world.level.biome.SnowyTaigaBiome
- net.minecraft.world.level.biome.SnowyTaigaHillsBiome
+ net.minecraft.world.level.biome.SnowyTaigaMountainsBiome
- net.minecraft.world.level.biome.SnowyTundraBiome
+ net.minecraft.world.level.biome.SoulSandValleyBiome
- net.minecraft.world.level.biome.StoneShoreBiome
+ net.minecraft.world.level.biome.SunflowerPlainsBiome
- net.minecraft.world.level.biome.SwampBiome
+ net.minecraft.world.level.biome.SwampHillsBiome
- net.minecraft.world.level.biome.TaigaBiome
+ net.minecraft.world.level.biome.TaigaHillsBiome
- net.minecraft.world.level.biome.TaigaMountainsBiome
+ net.minecraft.world.level.biome.TallBirchForestBiome
- net.minecraft.world.level.biome.TallBirchHillsBiome
+ net.minecraft.world.level.biome.TheEndBiome
- net.minecraft.world.level.biome.TheEndBiomeSource
+ net.minecraft.world.level.biome.TheVoidBiome
- net.minecraft.world.level.biome.WarmOceanBiome
+ net.minecraft.world.level.biome.WarpedForestBiome
- net.minecraft.world.level.biome.WoodedBadlandsBiome
+ net.minecraft.world.level.biome.WoodedHillsBiome
- net.minecraft.world.level.biome.WoodedMountainBiome
- net.minecraft.world.level.block.AbstractBannerBlock
+ net.minecraft.world.level.block.AbstractChestBlock
- net.minecraft.world.level.block.AbstractFurnaceBlock
+ net.minecraft.world.level.block.AbstractGlassBlock
- net.minecraft.world.level.block.AbstractSkullBlock
+ net.minecraft.world.level.block.AirBlock
- net.minecraft.world.level.block.AnvilBlock
+ net.minecraft.world.level.block.AttachedStemBlock
- net.minecraft.world.level.block.BambooBlock
+ net.minecraft.world.level.block.BambooSaplingBlock
- net.minecraft.world.level.block.BannerBlock
+ net.minecraft.world.level.block.BarrelBlock
- net.minecraft.world.level.block.BarrierBlock
+ net.minecraft.world.level.block.BaseCoralFanBlock
- net.minecraft.world.level.block.BaseCoralPlantBlock
+ net.minecraft.world.level.block.BaseCoralPlantTypeBlock
- net.minecraft.world.level.block.BaseCoralWallFanBlock
+ net.minecraft.world.level.block.BaseEntityBlock
- net.minecraft.world.level.block.BaseFireBlock
+ net.minecraft.world.level.block.BasePressurePlateBlock
- net.minecraft.world.level.block.BaseRailBlock
+ net.minecraft.world.level.block.BaseRailBlock$1
- net.minecraft.world.level.block.BeaconBeamBlock
+ net.minecraft.world.level.block.BeaconBlock
- net.minecraft.world.level.block.BedBlock
+ net.minecraft.world.level.block.BedBlock$1
- net.minecraft.world.level.block.BeehiveBlock
+ net.minecraft.world.level.block.BeetrootBlock
- net.minecraft.world.level.block.BellBlock
+ net.minecraft.world.level.block.BellBlock$1
- net.minecraft.world.level.block.BlastFurnaceBlock
+ net.minecraft.world.level.block.Block
- net.minecraft.world.level.block.Block$1
+ net.minecraft.world.level.block.Block$2
- net.minecraft.world.level.block.Block$BlockStatePairKey
+ net.minecraft.world.level.block.Blocks
- net.minecraft.world.level.block.BonemealableBlock
+ net.minecraft.world.level.block.BrewingStandBlock
- net.minecraft.world.level.block.BubbleColumnBlock
+ net.minecraft.world.level.block.BucketPickup
- net.minecraft.world.level.block.BushBlock
+ net.minecraft.world.level.block.ButtonBlock
- net.minecraft.world.level.block.ButtonBlock$1
+ net.minecraft.world.level.block.CactusBlock
- net.minecraft.world.level.block.CakeBlock
+ net.minecraft.world.level.block.CampfireBlock
- net.minecraft.world.level.block.CarrotBlock
+ net.minecraft.world.level.block.CartographyTableBlock
- net.minecraft.world.level.block.CarvedPumpkinBlock
+ net.minecraft.world.level.block.CauldronBlock
- net.minecraft.world.level.block.ChainBlock
+ net.minecraft.world.level.block.ChestBlock
- net.minecraft.world.level.block.ChestBlock$1
+ net.minecraft.world.level.block.ChestBlock$2
- net.minecraft.world.level.block.ChestBlock$2$1
+ net.minecraft.world.level.block.ChestBlock$3
- net.minecraft.world.level.block.ChestBlock$4
+ net.minecraft.world.level.block.ChorusFlowerBlock
- net.minecraft.world.level.block.ChorusPlantBlock
+ net.minecraft.world.level.block.CocoaBlock
- net.minecraft.world.level.block.CocoaBlock$1
+ net.minecraft.world.level.block.CommandBlock
- net.minecraft.world.level.block.ComparatorBlock
+ net.minecraft.world.level.block.ComposterBlock
- net.minecraft.world.level.block.ComposterBlock$EmptyContainer
+ net.minecraft.world.level.block.ComposterBlock$InputContainer
- net.minecraft.world.level.block.ComposterBlock$OutputContainer
+ net.minecraft.world.level.block.ConcretePowderBlock
- net.minecraft.world.level.block.ConduitBlock
+ net.minecraft.world.level.block.CoralBlock
- net.minecraft.world.level.block.CoralFanBlock
+ net.minecraft.world.level.block.CoralPlantBlock
- net.minecraft.world.level.block.CoralWallFanBlock
+ net.minecraft.world.level.block.CraftingTableBlock
- net.minecraft.world.level.block.CropBlock
+ net.minecraft.world.level.block.CrossCollisionBlock
- net.minecraft.world.level.block.CrossCollisionBlock$1
+ net.minecraft.world.level.block.CryingObsidianBlock
- net.minecraft.world.level.block.DaylightDetectorBlock
+ net.minecraft.world.level.block.DeadBushBlock
- net.minecraft.world.level.block.DetectorRailBlock
+ net.minecraft.world.level.block.DetectorRailBlock$1
- net.minecraft.world.level.block.DiodeBlock
+ net.minecraft.world.level.block.DirectionalBlock
- net.minecraft.world.level.block.DispenserBlock
+ net.minecraft.world.level.block.DoorBlock
- net.minecraft.world.level.block.DoorBlock$1
+ net.minecraft.world.level.block.DoubleBlockCombiner
- net.minecraft.world.level.block.DoubleBlockCombiner$BlockType
+ net.minecraft.world.level.block.DoubleBlockCombiner$Combiner
- net.minecraft.world.level.block.DoubleBlockCombiner$NeighborCombineResult
+ net.minecraft.world.level.block.DoubleBlockCombiner$NeighborCombineResult$Double
- net.minecraft.world.level.block.DoubleBlockCombiner$NeighborCombineResult$Single
+ net.minecraft.world.level.block.DoublePlantBlock
- net.minecraft.world.level.block.DragonEggBlock
+ net.minecraft.world.level.block.DropperBlock
- net.minecraft.world.level.block.EnchantmentTableBlock
- net.minecraft.world.level.block.EnderChestBlock
+ net.minecraft.world.level.block.EndGatewayBlock
- net.minecraft.world.level.block.EndPortalBlock
+ net.minecraft.world.level.block.EndPortalFrameBlock
- net.minecraft.world.level.block.EndRodBlock
+ net.minecraft.world.level.block.EndRodBlock$1
+ net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity
- net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity$1
+ net.minecraft.world.level.block.entity.BannerBlockEntity
- net.minecraft.world.level.block.entity.BannerPattern
+ net.minecraft.world.level.block.entity.BannerPattern$Builder
- net.minecraft.world.level.block.entity.BarrelBlockEntity
+ net.minecraft.world.level.block.entity.BaseContainerBlockEntity
- net.minecraft.world.level.block.entity.BeaconBlockEntity
+ net.minecraft.world.level.block.entity.BeaconBlockEntity$1
- net.minecraft.world.level.block.entity.BeaconBlockEntity$BeaconBeamSection
+ net.minecraft.world.level.block.entity.BedBlockEntity
- net.minecraft.world.level.block.entity.BeehiveBlockEntity
+ net.minecraft.world.level.block.entity.BeehiveBlockEntity$1
- net.minecraft.world.level.block.entity.BeehiveBlockEntity$BeeData
+ net.minecraft.world.level.block.entity.BeehiveBlockEntity$BeeReleaseStatus
- net.minecraft.world.level.block.entity.BellBlockEntity
+ net.minecraft.world.level.block.entity.BlastFurnaceBlockEntity
- net.minecraft.world.level.block.entity.BlockEntity
+ net.minecraft.world.level.block.entity.BlockEntityType
- net.minecraft.world.level.block.entity.BlockEntityType$Builder
+ net.minecraft.world.level.block.entity.BrewingStandBlockEntity
- net.minecraft.world.level.block.entity.BrewingStandBlockEntity$1
+ net.minecraft.world.level.block.entity.CampfireBlockEntity
- net.minecraft.world.level.block.entity.ChestBlockEntity
+ net.minecraft.world.level.block.entity.CommandBlockEntity
- net.minecraft.world.level.block.entity.CommandBlockEntity$1
+ net.minecraft.world.level.block.entity.CommandBlockEntity$Mode
- net.minecraft.world.level.block.entity.ComparatorBlockEntity
+ net.minecraft.world.level.block.entity.ConduitBlockEntity
- net.minecraft.world.level.block.entity.DaylightDetectorBlockEntity
+ net.minecraft.world.level.block.entity.DispenserBlockEntity
- net.minecraft.world.level.block.entity.DropperBlockEntity
+ net.minecraft.world.level.block.entity.EnchantmentTableBlockEntity
- net.minecraft.world.level.block.entity.EnderChestBlockEntity
+ net.minecraft.world.level.block.entity.FurnaceBlockEntity
- net.minecraft.world.level.block.entity.Hopper
+ net.minecraft.world.level.block.entity.HopperBlockEntity
- net.minecraft.world.level.block.entity.JigsawBlockEntity
+ net.minecraft.world.level.block.entity.JigsawBlockEntity$JointType
- net.minecraft.world.level.block.entity.JigsawBlockEntity$RuntimePiece
+ net.minecraft.world.level.block.entity.JukeboxBlockEntity
- net.minecraft.world.level.block.entity.LecternBlockEntity
+ net.minecraft.world.level.block.entity.LecternBlockEntity$1
- net.minecraft.world.level.block.entity.LecternBlockEntity$2
+ net.minecraft.world.level.block.entity.LidBlockEntity
- net.minecraft.world.level.block.entity.package-info
- net.minecraft.world.level.block.entity.RandomizableContainerBlockEntity
+ net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity
- net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity$1
+ net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity$AnimationStatus
- net.minecraft.world.level.block.entity.SignBlockEntity
+ net.minecraft.world.level.block.entity.SkullBlockEntity
- net.minecraft.world.level.block.entity.SmokerBlockEntity
+ net.minecraft.world.level.block.entity.SpawnerBlockEntity
- net.minecraft.world.level.block.entity.SpawnerBlockEntity$1
+ net.minecraft.world.level.block.entity.StructureBlockEntity
- net.minecraft.world.level.block.entity.StructureBlockEntity$1
+ net.minecraft.world.level.block.entity.StructureBlockEntity$UpdateType
- net.minecraft.world.level.block.entity.TheEndGatewayBlockEntity
+ net.minecraft.world.level.block.entity.TheEndPortalBlockEntity
- net.minecraft.world.level.block.entity.TickableBlockEntity
+ net.minecraft.world.level.block.entity.TrappedChestBlockEntity
+ net.minecraft.world.level.block.EntityBlock
- net.minecraft.world.level.block.FaceAttachedHorizontalDirectionalBlock
+ net.minecraft.world.level.block.FaceAttachedHorizontalDirectionalBlock$1
- net.minecraft.world.level.block.FallingBlock
+ net.minecraft.world.level.block.FarmBlock
- net.minecraft.world.level.block.FenceBlock
+ net.minecraft.world.level.block.FenceGateBlock
- net.minecraft.world.level.block.FenceGateBlock$1
+ net.minecraft.world.level.block.FireBlock
- net.minecraft.world.level.block.FletchingTableBlock
+ net.minecraft.world.level.block.FlowerBlock
- net.minecraft.world.level.block.FlowerPotBlock
+ net.minecraft.world.level.block.FrostedIceBlock
- net.minecraft.world.level.block.FungusBlock
+ net.minecraft.world.level.block.FurnaceBlock
- net.minecraft.world.level.block.GlassBlock
+ net.minecraft.world.level.block.GlazedTerracottaBlock
- net.minecraft.world.level.block.GrassBlock
+ net.minecraft.world.level.block.GrassPathBlock
- net.minecraft.world.level.block.GravelBlock
+ net.minecraft.world.level.block.GrindstoneBlock
- net.minecraft.world.level.block.GrindstoneBlock$1
+ net.minecraft.world.level.block.grower.AbstractMegaTreeGrower
- net.minecraft.world.level.block.grower.AbstractTreeGrower
+ net.minecraft.world.level.block.grower.AcaciaTreeGrower
- net.minecraft.world.level.block.grower.BirchTreeGrower
+ net.minecraft.world.level.block.grower.DarkOakTreeGrower
- net.minecraft.world.level.block.grower.JungleTreeGrower
+ net.minecraft.world.level.block.grower.OakTreeGrower
+ net.minecraft.world.level.block.grower.package-info
- net.minecraft.world.level.block.grower.SpruceTreeGrower
+ net.minecraft.world.level.block.GrowingPlantBlock
- net.minecraft.world.level.block.GrowingPlantBodyBlock
+ net.minecraft.world.level.block.GrowingPlantHeadBlock
- net.minecraft.world.level.block.HalfTransparentBlock
+ net.minecraft.world.level.block.HayBlock
- net.minecraft.world.level.block.HoneyBlock
+ net.minecraft.world.level.block.HopperBlock
- net.minecraft.world.level.block.HopperBlock$1
+ net.minecraft.world.level.block.HorizontalDirectionalBlock
- net.minecraft.world.level.block.HugeMushroomBlock
+ net.minecraft.world.level.block.IceBlock
- net.minecraft.world.level.block.InfestedBlock
+ net.minecraft.world.level.block.IronBarsBlock
- net.minecraft.world.level.block.JigsawBlock
+ net.minecraft.world.level.block.JukeboxBlock
- net.minecraft.world.level.block.KelpBlock
+ net.minecraft.world.level.block.KelpPlantBlock
- net.minecraft.world.level.block.LadderBlock
+ net.minecraft.world.level.block.LadderBlock$1
- net.minecraft.world.level.block.Lantern
+ net.minecraft.world.level.block.LeavesBlock
- net.minecraft.world.level.block.LecternBlock
+ net.minecraft.world.level.block.LecternBlock$1
- net.minecraft.world.level.block.LevelEvent
+ net.minecraft.world.level.block.LeverBlock
- net.minecraft.world.level.block.LeverBlock$1
+ net.minecraft.world.level.block.LiquidBlock
- net.minecraft.world.level.block.LiquidBlockContainer
+ net.minecraft.world.level.block.LoomBlock
- net.minecraft.world.level.block.MagmaBlock
+ net.minecraft.world.level.block.MelonBlock
- net.minecraft.world.level.block.Mirror
+ net.minecraft.world.level.block.Mirror$1
- net.minecraft.world.level.block.MushroomBlock
+ net.minecraft.world.level.block.MyceliumBlock
- net.minecraft.world.level.block.NetherPortalBlock
+ net.minecraft.world.level.block.NetherPortalBlock$1
- net.minecraft.world.level.block.NetherPortalBlock$PortalShape
- net.minecraft.world.level.block.NetherrackBlock
+ net.minecraft.world.level.block.NetherSproutsBlock
- net.minecraft.world.level.block.NetherVines
+ net.minecraft.world.level.block.NetherWartBlock
+ net.minecraft.world.level.block.NoteBlock
- net.minecraft.world.level.block.NyliumBlock
+ net.minecraft.world.level.block.ObserverBlock
- net.minecraft.world.level.block.OreBlock
- net.minecraft.world.level.block.package-info
+ net.minecraft.world.level.block.PipeBlock
+ net.minecraft.world.level.block.piston.MovingPistonBlock
+ net.minecraft.world.level.block.piston.package-info
- net.minecraft.world.level.block.piston.PistonBaseBlock
+ net.minecraft.world.level.block.piston.PistonBaseBlock$1
- net.minecraft.world.level.block.piston.PistonHeadBlock
+ net.minecraft.world.level.block.piston.PistonHeadBlock$1
- net.minecraft.world.level.block.piston.PistonMath
+ net.minecraft.world.level.block.piston.PistonMath$1
- net.minecraft.world.level.block.piston.PistonMovingBlockEntity
+ net.minecraft.world.level.block.piston.PistonMovingBlockEntity$1
- net.minecraft.world.level.block.piston.PistonStructureResolver
- net.minecraft.world.level.block.PlayerHeadBlock
+ net.minecraft.world.level.block.PlayerWallHeadBlock
- net.minecraft.world.level.block.PotatoBlock
+ net.minecraft.world.level.block.PoweredBlock
- net.minecraft.world.level.block.PoweredRailBlock
+ net.minecraft.world.level.block.PoweredRailBlock$1
- net.minecraft.world.level.block.PressurePlateBlock
+ net.minecraft.world.level.block.PressurePlateBlock$1
- net.minecraft.world.level.block.PressurePlateBlock$Sensitivity
+ net.minecraft.world.level.block.PumpkinBlock
- net.minecraft.world.level.block.RailBlock
+ net.minecraft.world.level.block.RailBlock$1
- net.minecraft.world.level.block.RailState
+ net.minecraft.world.level.block.RailState$1
+ net.minecraft.world.level.block.RedstoneLampBlock
- net.minecraft.world.level.block.RedStoneOreBlock
- net.minecraft.world.level.block.RedstoneTorchBlock
+ net.minecraft.world.level.block.RedstoneTorchBlock$Toggle
- net.minecraft.world.level.block.RedstoneWallTorchBlock
+ net.minecraft.world.level.block.RedStoneWireBlock
- net.minecraft.world.level.block.RedStoneWireBlock$1
+ net.minecraft.world.level.block.RenderShape
- net.minecraft.world.level.block.RepeaterBlock
+ net.minecraft.world.level.block.RespawnAnchorBlock
- net.minecraft.world.level.block.RootsBlock
+ net.minecraft.world.level.block.RotatedPillarBlock
- net.minecraft.world.level.block.RotatedPillarBlock$1
+ net.minecraft.world.level.block.Rotation
- net.minecraft.world.level.block.Rotation$1
+ net.minecraft.world.level.block.SandBlock
- net.minecraft.world.level.block.SaplingBlock
+ net.minecraft.world.level.block.ScaffoldingBlock
+ net.minecraft.world.level.block.Seagrass
- net.minecraft.world.level.block.SeaPickleBlock
- net.minecraft.world.level.block.ShearableDoublePlantBlock
+ net.minecraft.world.level.block.ShulkerBoxBlock
- net.minecraft.world.level.block.ShulkerBoxBlock$1
+ net.minecraft.world.level.block.SignBlock
- net.minecraft.world.level.block.SimpleWaterloggedBlock
+ net.minecraft.world.level.block.SkullBlock
- net.minecraft.world.level.block.SkullBlock$Type
+ net.minecraft.world.level.block.SkullBlock$Types
- net.minecraft.world.level.block.SlabBlock
+ net.minecraft.world.level.block.SlabBlock$1
- net.minecraft.world.level.block.SlimeBlock
+ net.minecraft.world.level.block.SmithingTableBlock
- net.minecraft.world.level.block.SmokerBlock
+ net.minecraft.world.level.block.SnowLayerBlock
- net.minecraft.world.level.block.SnowLayerBlock$1
+ net.minecraft.world.level.block.SnowyDirtBlock
- net.minecraft.world.level.block.SoulFireBlock
+ net.minecraft.world.level.block.SoulSandBlock
- net.minecraft.world.level.block.SoundType
+ net.minecraft.world.level.block.SpawnerBlock
- net.minecraft.world.level.block.SpongeBlock
+ net.minecraft.world.level.block.SpreadingSnowyDirtBlock
- net.minecraft.world.level.block.StainedGlassBlock
+ net.minecraft.world.level.block.StainedGlassPaneBlock
- net.minecraft.world.level.block.StairBlock
+ net.minecraft.world.level.block.StairBlock$1
- net.minecraft.world.level.block.StandingSignBlock
+ net.minecraft.world.level.block.state.AbstractStateHolder$1
- net.minecraft.world.level.block.state.BlockBehaviour
+ net.minecraft.world.level.block.state.BlockBehaviour$1
- net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase
+ net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase$Cache
- net.minecraft.world.level.block.state.BlockBehaviour$OffsetType
+ net.minecraft.world.level.block.state.BlockBehaviour$Properties
- net.minecraft.world.level.block.state.BlockBehaviour$StateArgumentPredicate
+ net.minecraft.world.level.block.state.BlockBehaviour$StatePredicate
- net.minecraft.world.level.block.state.BlockState
+ net.minecraft.world.level.block.state.package-info
- net.minecraft.world.level.block.state.pattern.BlockInWorld
+ net.minecraft.world.level.block.state.pattern.BlockPattern
- net.minecraft.world.level.block.state.pattern.BlockPattern$BlockCacheLoader
+ net.minecraft.world.level.block.state.pattern.BlockPattern$BlockPatternMatch
- net.minecraft.world.level.block.state.pattern.BlockPattern$PortalInfo
+ net.minecraft.world.level.block.state.pattern.BlockPatternBuilder
- net.minecraft.world.level.block.state.pattern.package-info
+ net.minecraft.world.level.block.state.predicate.BlockMaterialPredicate
- net.minecraft.world.level.block.state.predicate.BlockMaterialPredicate$1
+ net.minecraft.world.level.block.state.predicate.BlockPredicate
- net.minecraft.world.level.block.state.predicate.BlockStatePredicate
+ net.minecraft.world.level.block.state.predicate.package-info
+ net.minecraft.world.level.block.state.StateDefinition
- net.minecraft.world.level.block.state.StateDefinition$Builder
+ net.minecraft.world.level.block.state.StateDefinition$Factory
- net.minecraft.world.level.block.state.StateDefinition$PropertiesCodec
- net.minecraft.world.level.block.state.StateHolder$1
+ net.minecraft.world.level.block.StemBlock
- net.minecraft.world.level.block.StemGrownBlock
+ net.minecraft.world.level.block.StoneButtonBlock
- net.minecraft.world.level.block.StonecutterBlock
+ net.minecraft.world.level.block.StructureBlock
- net.minecraft.world.level.block.StructureBlock$1
+ net.minecraft.world.level.block.StructureVoidBlock
- net.minecraft.world.level.block.SugarCaneBlock
+ net.minecraft.world.level.block.SweetBerryBushBlock
- net.minecraft.world.level.block.TallFlowerBlock
+ net.minecraft.world.level.block.TallGrassBlock
- net.minecraft.world.level.block.TallSeagrass
+ net.minecraft.world.level.block.TargetBlock
- net.minecraft.world.level.block.TntBlock
+ net.minecraft.world.level.block.TorchBlock
- net.minecraft.world.level.block.TrapDoorBlock
+ net.minecraft.world.level.block.TrapDoorBlock$1
- net.minecraft.world.level.block.TrappedChestBlock
+ net.minecraft.world.level.block.TripWireBlock
- net.minecraft.world.level.block.TripWireBlock$1
+ net.minecraft.world.level.block.TripWireHookBlock
- net.minecraft.world.level.block.TripWireHookBlock$1
+ net.minecraft.world.level.block.TurtleEggBlock
- net.minecraft.world.level.block.TwistingVines
+ net.minecraft.world.level.block.TwistingVinesPlant
- net.minecraft.world.level.block.VineBlock
+ net.minecraft.world.level.block.VineBlock$1
- net.minecraft.world.level.block.WallBannerBlock
+ net.minecraft.world.level.block.WallBlock
- net.minecraft.world.level.block.WallBlock$1
+ net.minecraft.world.level.block.WallSignBlock
- net.minecraft.world.level.block.WallSkullBlock
+ net.minecraft.world.level.block.WallTorchBlock
- net.minecraft.world.level.block.WaterlilyBlock
+ net.minecraft.world.level.block.WebBlock
- net.minecraft.world.level.block.WeepingVines
+ net.minecraft.world.level.block.WeepingVinesPlant
- net.minecraft.world.level.block.WeightedPressurePlateBlock
+ net.minecraft.world.level.block.WetSpongeBlock
- net.minecraft.world.level.block.WitherRoseBlock
+ net.minecraft.world.level.block.WitherSkullBlock
- net.minecraft.world.level.block.WitherWallSkullBlock
+ net.minecraft.world.level.block.WoodButtonBlock
- net.minecraft.world.level.block.WoolCarpetBlock
+ net.minecraft.world.level.dimension.Dimension
- net.minecraft.world.level.dimension.DimensionType
- net.minecraft.world.level.dimension.end.package-info
+ net.minecraft.world.level.dimension.end.TheEndDimension
+ net.minecraft.world.level.dimension.NetherDimension
+ net.minecraft.world.level.dimension.NormalDimension
+ net.minecraft.world.level.dimension.package-info
- net.minecraft.world.level.Level$1
+ net.minecraft.world.level.LevelAccessor
- net.minecraft.world.level.levelgen.feature.configurations.StrongholdConfiguration
- net.minecraft.world.level.levelgen.feature.ConfiguredStructureFeature
+ net.minecraft.world.level.levelgen.feature.CoralClawFeature
- net.minecraft.world.level.levelgen.feature.CoralFeature
+ net.minecraft.world.level.levelgen.feature.CoralMushroomFeature
- net.minecraft.world.level.levelgen.feature.CoralTreeFeature
+ net.minecraft.world.level.levelgen.feature.DecoratedFeature
- net.minecraft.world.level.levelgen.feature.DecoratedFlowerFeature
+ net.minecraft.world.level.levelgen.feature.DefaultFlowerFeature
- net.minecraft.world.level.levelgen.feature.DeltaFeature
+ net.minecraft.world.level.levelgen.feature.DesertPyramidFeature
- net.minecraft.world.level.levelgen.feature.DesertPyramidFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.DesertVillagePools
- net.minecraft.world.level.levelgen.feature.DesertWellFeature
+ net.minecraft.world.level.levelgen.feature.DiskReplaceFeature
- net.minecraft.world.level.levelgen.feature.EndCityFeature
+ net.minecraft.world.level.levelgen.feature.EndCityFeature$EndCityStart
- net.minecraft.world.level.levelgen.feature.EndGatewayFeature
+ net.minecraft.world.level.levelgen.feature.EndIslandFeature
- net.minecraft.world.level.levelgen.feature.EndPodiumFeature
+ net.minecraft.world.level.levelgen.feature.Feature
- net.minecraft.world.level.levelgen.feature.FillLayerFeature
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer$Factory
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer$FoliageAttachment
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacerType
+ net.minecraft.world.level.levelgen.feature.foliageplacers.MegaJungleFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.MegaPineFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.package-info
+ net.minecraft.world.level.levelgen.feature.foliageplacers.PineFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.SpruceFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.FossilFeature
- net.minecraft.world.level.levelgen.feature.GlowstoneFeature
+ net.minecraft.world.level.levelgen.feature.HugeBrownMushroomFeature
- net.minecraft.world.level.levelgen.feature.HugeFungusConfiguration
+ net.minecraft.world.level.levelgen.feature.HugeFungusFeature
- net.minecraft.world.level.levelgen.feature.HugeRedMushroomFeature
+ net.minecraft.world.level.levelgen.feature.IcebergFeature
+ net.minecraft.world.level.levelgen.feature.IcePatchFeature
- net.minecraft.world.level.levelgen.feature.IceSpikeFeature
- net.minecraft.world.level.levelgen.feature.IglooFeature
+ net.minecraft.world.level.levelgen.feature.IglooFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.JunglePyramidFeature
+ net.minecraft.world.level.levelgen.feature.JunglePyramidFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.KelpFeature
+ net.minecraft.world.level.levelgen.feature.LakeFeature
- net.minecraft.world.level.levelgen.feature.MineshaftFeature
+ net.minecraft.world.level.levelgen.feature.MineshaftFeature$MineShaftStart
- net.minecraft.world.level.levelgen.feature.MineshaftFeature$Type
+ net.minecraft.world.level.levelgen.feature.MonsterRoomFeature
- net.minecraft.world.level.levelgen.feature.NetherForestVegetationFeature
+ net.minecraft.world.level.levelgen.feature.NetherFortressFeature
- net.minecraft.world.level.levelgen.feature.NetherFortressFeature$NetherBridgeStart
+ net.minecraft.world.level.levelgen.feature.NoOpFeature
- net.minecraft.world.level.levelgen.feature.NoSurfaceOreFeature
+ net.minecraft.world.level.levelgen.feature.OceanMonumentFeature
- net.minecraft.world.level.levelgen.feature.OceanMonumentFeature$OceanMonumentStart
+ net.minecraft.world.level.levelgen.feature.OreFeature
- net.minecraft.world.level.levelgen.feature.package-info
- net.minecraft.world.level.levelgen.feature.PillagerOutpostFeature
+ net.minecraft.world.level.levelgen.feature.PillagerOutpostFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.PlainVillagePools
+ net.minecraft.world.level.levelgen.feature.RandomBooleanSelectorFeature
- net.minecraft.world.level.levelgen.feature.RandomPatchFeature
+ net.minecraft.world.level.levelgen.feature.RandomRandomFeature
+ net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProviderType
+ net.minecraft.world.level.levelgen.feature.stateproviders.ForestFlowerProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.package-info
- net.minecraft.world.level.levelgen.feature.stateproviders.PlainFlowerProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.RotatedBlockProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.SimpleStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.WeightedStateProvider
+ net.minecraft.world.level.levelgen.feature.structures.EmptyPoolElement
- net.minecraft.world.level.levelgen.feature.structures.FeaturePoolElement
+ net.minecraft.world.level.levelgen.feature.structures.JigsawJunction
- net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$1
- net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$PieceFactory
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$PieceState
- net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$Placer
+ net.minecraft.world.level.levelgen.feature.structures.LegacySinglePoolElement
- net.minecraft.world.level.levelgen.feature.structures.ListPoolElement
+ net.minecraft.world.level.levelgen.feature.structures.package-info
+ net.minecraft.world.level.levelgen.feature.structures.SinglePoolElement
- net.minecraft.world.level.levelgen.feature.structures.StructurePoolElement
+ net.minecraft.world.level.levelgen.feature.structures.StructurePoolElementType
- net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool
+ net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool$Projection
- net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePools
- net.minecraft.world.level.levelgen.feature.treedecorators.AlterGroundDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.BeehiveDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.CocoaDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.LeaveVineDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.package-info
- net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecoratorType
- net.minecraft.world.level.levelgen.feature.treedecorators.TrunkVineDecorator
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
- net.minecraft.world.level.levelgen.flat.FlatLayerInfo
+ net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorSettings
- net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorSettings$1
+ net.minecraft.world.level.levelgen.FlatLevelSource$FlatLevelBiomeWrapper
- net.minecraft.world.level.levelgen.GenerationStep
+ net.minecraft.world.level.levelgen.GenerationStep$Carving
- net.minecraft.world.level.levelgen.GenerationStep$Decoration
+ net.minecraft.world.level.levelgen.Heightmap
- net.minecraft.world.level.levelgen.Heightmap$Types
+ net.minecraft.world.level.levelgen.Heightmap$Usage
+ net.minecraft.world.level.levelgen.NetherLevelSource
- net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator
+ net.minecraft.world.level.levelgen.NoiseGeneratorSettings
- net.minecraft.world.level.levelgen.NoiseGeneratorSettings$1
- net.minecraft.world.level.levelgen.NoiseSamplingSettings
- net.minecraft.world.level.levelgen.NoiseSlideSettings
+ net.minecraft.world.level.levelgen.OverworldLevelSource
- net.minecraft.world.level.levelgen.structure.package-info
+ net.minecraft.world.level.levelgen.structure.StructureFeatureIndexSavedData
- net.minecraft.world.level.levelgen.structure.StructurePiece
+ net.minecraft.world.level.levelgen.structure.StructurePiece$1
- net.minecraft.world.level.levelgen.structure.StructurePiece$BlockSelector
+ net.minecraft.world.level.levelgen.structure.StructureStart
- net.minecraft.world.level.levelgen.structure.StructureStart$1
+ net.minecraft.world.level.levelgen.structure.SwamplandHutPiece
- net.minecraft.world.level.levelgen.structure.TemplateStructurePiece
+ net.minecraft.world.level.levelgen.structure.templatesystem.AlwaysTrueTest
- net.minecraft.world.level.levelgen.structure.templatesystem.AxisAlignedLinearPosTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlackstoneReplaceProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockAgeProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockIgnoreProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockMatchTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockRotProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockStateMatchTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.GravityProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.JigsawReplacementProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.LinearPosTest
- net.minecraft.world.level.levelgen.structure.templatesystem.NopProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.package-info
+ net.minecraft.world.level.levelgen.structure.templatesystem.PosAlwaysTrueTest
- net.minecraft.world.level.levelgen.structure.templatesystem.PosRuleTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.PosRuleTestType
- net.minecraft.world.level.levelgen.structure.templatesystem.ProcessorRule
+ net.minecraft.world.level.levelgen.structure.templatesystem.RandomBlockMatchTest
- net.minecraft.world.level.levelgen.structure.templatesystem.RandomBlockStateMatchTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.RuleProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.RuleTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.RuleTestType
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureManager
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructurePlaceSettings
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureProcessorType
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$1
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$Palette
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$SimplePalette
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$StructureBlockInfo
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$StructureEntityInfo
- net.minecraft.world.level.levelgen.structure.templatesystem.TagMatchTest
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$1
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$FirstFloorRoomCollection
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$FloorRoomCollection
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$MansionGrid
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$MansionPiecePlacer
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$PlacementData
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$SecondFloorRoomCollection
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$SimpleGrid
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$ThirdFloorRoomCollection
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$WoodlandMansionPiece
- net.minecraft.world.level.levelgen.surfacebuilders.BadlandsSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.BasaltDeltasSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.ConfiguredSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.DefaultSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.ErodedBadlandsSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.FrozenOceanSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.GiantTreeTaigaSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.GravellyMountainSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.MountainSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.NetherCappedSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.NetherForestSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.NetherSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.NopeSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.package-info
+ net.minecraft.world.level.levelgen.surfacebuilders.ShatteredSavanaSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.SoulSandValleySurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.SurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.SurfaceBuilderBaseConfiguration
+ net.minecraft.world.level.levelgen.surfacebuilders.SurfaceBuilderConfiguration
- net.minecraft.world.level.levelgen.surfacebuilders.SwampSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.WoodedBadlandsSurfaceBuilder
+ net.minecraft.world.level.levelgen.synth.ImprovedNoise
- net.minecraft.world.level.levelgen.synth.NormalNoise
+ net.minecraft.world.level.levelgen.synth.package-info
+ net.minecraft.world.level.levelgen.synth.PerlinNoise
- net.minecraft.world.level.levelgen.synth.PerlinSimplexNoise
+ net.minecraft.world.level.levelgen.synth.SimplexNoise
- net.minecraft.world.level.levelgen.synth.SurfaceNoise
+ net.minecraft.world.level.levelgen.WorldGenSettings$BuffetGeneratorType
+ net.minecraft.world.level.levelgen.WorldGenSettings$Preset
- net.minecraft.world.level.LevelReader
+ net.minecraft.world.level.LevelSettings
+ net.minecraft.world.level.LevelSimulatedReader
- net.minecraft.world.level.LevelSimulatedRW
- net.minecraft.world.level.LevelWriter
- net.minecraft.world.level.lighting.BlockLightEngine
+ net.minecraft.world.level.lighting.BlockLightSectionStorage
- net.minecraft.world.level.lighting.BlockLightSectionStorage$BlockDataLayerStorageMap
+ net.minecraft.world.level.lighting.DataLayerStorageMap
- net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint
+ net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint$1
- net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint$2
+ net.minecraft.world.level.lighting.FlatDataLayer
- net.minecraft.world.level.lighting.LayerLightEngine
+ net.minecraft.world.level.lighting.LayerLightEventListener
- net.minecraft.world.level.lighting.LayerLightEventListener$DummyLightLayerEventListener
+ net.minecraft.world.level.lighting.LayerLightSectionStorage
- net.minecraft.world.level.lighting.LayerLightSectionStorage$1
+ net.minecraft.world.level.lighting.LevelLightEngine
- net.minecraft.world.level.lighting.LightEventListener
+ net.minecraft.world.level.lighting.package-info
+ net.minecraft.world.level.lighting.SkyLightEngine
- net.minecraft.world.level.lighting.SkyLightSectionStorage
+ net.minecraft.world.level.lighting.SkyLightSectionStorage$1
- net.minecraft.world.level.lighting.SkyLightSectionStorage$SkyDataLayerStorageMap
+ net.minecraft.world.level.lighting.SpatialLongSet
- net.minecraft.world.level.lighting.SpatialLongSet$InternalMap
+ net.minecraft.world.level.LightLayer
- net.minecraft.world.level.material.EmptyFluid
+ net.minecraft.world.level.material.FlowingFluid
- net.minecraft.world.level.material.FlowingFluid$1
+ net.minecraft.world.level.material.Fluid
- net.minecraft.world.level.material.FluidState
+ net.minecraft.world.level.material.FluidStateImpl
- net.minecraft.world.level.NaturalSpawner
+ net.minecraft.world.level.NaturalSpawner$1
- net.minecraft.world.level.NaturalSpawner$AfterSpawnCallback
+ net.minecraft.world.level.NaturalSpawner$ChunkGetter
- net.minecraft.world.level.NaturalSpawner$SpawnPredicate
+ net.minecraft.world.level.NaturalSpawner$SpawnState
- net.minecraft.world.level.NoiseColumn
+ net.minecraft.world.level.PathNavigationRegion
- net.minecraft.world.level.PortalForcer
+ net.minecraft.world.level.PotentialCalculator
- net.minecraft.world.level.PotentialCalculator$PointCharge
+ net.minecraft.world.level.ServerTickList
- net.minecraft.world.level.SpawnData
- net.minecraft.world.level.storage.LevelVersion
+ net.minecraft.world.level.storage.loot.BinomialDistributionGenerator
- net.minecraft.world.level.storage.loot.BinomialDistributionGenerator$Serializer
+ net.minecraft.world.level.storage.loot.BuiltInLootTables
- net.minecraft.world.level.storage.loot.ConstantIntValue
+ net.minecraft.world.level.storage.loot.ConstantIntValue$Serializer
- net.minecraft.world.level.storage.loot.Deserializers
- net.minecraft.world.level.storage.loot.entries.AlternativesEntry
+ net.minecraft.world.level.storage.loot.entries.AlternativesEntry$Builder
- net.minecraft.world.level.storage.loot.entries.ComposableEntryContainer
+ net.minecraft.world.level.storage.loot.entries.CompositeEntryBase
- net.minecraft.world.level.storage.loot.entries.CompositeEntryBase$1
+ net.minecraft.world.level.storage.loot.entries.CompositeEntryBase$CompositeEntryConstructor
- net.minecraft.world.level.storage.loot.entries.CompositeEntryBase$Serializer
+ net.minecraft.world.level.storage.loot.entries.DynamicLoot
- net.minecraft.world.level.storage.loot.entries.DynamicLoot$1
+ net.minecraft.world.level.storage.loot.entries.DynamicLoot$Serializer
- net.minecraft.world.level.storage.loot.entries.EmptyLootItem
+ net.minecraft.world.level.storage.loot.entries.EmptyLootItem$1
- net.minecraft.world.level.storage.loot.entries.EmptyLootItem$Serializer
+ net.minecraft.world.level.storage.loot.entries.EntryGroup
- net.minecraft.world.level.storage.loot.entries.EntryGroup$Builder
+ net.minecraft.world.level.storage.loot.entries.LootItem
- net.minecraft.world.level.storage.loot.entries.LootItem$1
+ net.minecraft.world.level.storage.loot.entries.LootItem$Serializer
- net.minecraft.world.level.storage.loot.entries.LootPoolEntries
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntries$Serializer
- net.minecraft.world.level.storage.loot.entries.LootPoolEntry
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntryContainer
- net.minecraft.world.level.storage.loot.entries.LootPoolEntryContainer$Builder
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntryContainer$Serializer
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$1
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$Builder
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$DummyBuilder
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$EntryBase
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$EntryConstructor
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$Serializer
+ net.minecraft.world.level.storage.loot.entries.LootTableReference
- net.minecraft.world.level.storage.loot.entries.LootTableReference$1
+ net.minecraft.world.level.storage.loot.entries.LootTableReference$Serializer
+ net.minecraft.world.level.storage.loot.entries.package-info
- net.minecraft.world.level.storage.loot.entries.SequentialEntry
+ net.minecraft.world.level.storage.loot.entries.SequentialEntry$Builder
- net.minecraft.world.level.storage.loot.entries.TagEntry
+ net.minecraft.world.level.storage.loot.entries.TagEntry$1
- net.minecraft.world.level.storage.loot.entries.TagEntry$Serializer
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$1
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$BinomialWithBonusCount
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$Formula
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$FormulaDeserializer
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$OreDrops
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$Serializer
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$UniformBonusCount
- net.minecraft.world.level.storage.loot.functions.ApplyExplosionDecay
+ net.minecraft.world.level.storage.loot.functions.ApplyExplosionDecay$1
- net.minecraft.world.level.storage.loot.functions.ApplyExplosionDecay$Serializer
+ net.minecraft.world.level.storage.loot.functions.CopyBlockState
- net.minecraft.world.level.storage.loot.functions.CopyBlockState$1
+ net.minecraft.world.level.storage.loot.functions.CopyBlockState$Builder
- net.minecraft.world.level.storage.loot.functions.CopyBlockState$Serializer
+ net.minecraft.world.level.storage.loot.functions.CopyNameFunction
- net.minecraft.world.level.storage.loot.functions.CopyNameFunction$1
+ net.minecraft.world.level.storage.loot.functions.CopyNameFunction$NameSource
- net.minecraft.world.level.storage.loot.functions.CopyNameFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$1
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$Builder
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$CopyOperation
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$DataSource
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$1
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$2
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$3
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction
- net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction$1
+ net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction$Builder
- net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction
- net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction$1
+ net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction$Builder
- net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction
- net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction$1
+ net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction$Builder
- net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.FillPlayerHead
- net.minecraft.world.level.storage.loot.functions.FillPlayerHead$Serializer
+ net.minecraft.world.level.storage.loot.functions.FunctionUserBuilder
- net.minecraft.world.level.storage.loot.functions.LimitCount
+ net.minecraft.world.level.storage.loot.functions.LimitCount$1
- net.minecraft.world.level.storage.loot.functions.LimitCount$Serializer
- net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction
+ net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction$1
- net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction
- net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$DummyBuilder
- net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.LootItemFunction
- net.minecraft.world.level.storage.loot.functions.LootItemFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.LootItemFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.LootItemFunctions
+ net.minecraft.world.level.storage.loot.functions.LootItemFunctions$Serializer
+ net.minecraft.world.level.storage.loot.functions.package-info
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$1
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Modifier
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$ModifierBuilder
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SetContainerContents
+ net.minecraft.world.level.storage.loot.functions.SetContainerContents$1
- net.minecraft.world.level.storage.loot.functions.SetContainerContents$Builder
+ net.minecraft.world.level.storage.loot.functions.SetContainerContents$Serializer
- net.minecraft.world.level.storage.loot.functions.SetContainerLootTable
+ net.minecraft.world.level.storage.loot.functions.SetContainerLootTable$1
- net.minecraft.world.level.storage.loot.functions.SetContainerLootTable$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetItemCountFunction
- net.minecraft.world.level.storage.loot.functions.SetItemCountFunction$1
+ net.minecraft.world.level.storage.loot.functions.SetItemCountFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SetItemDamageFunction
+ net.minecraft.world.level.storage.loot.functions.SetItemDamageFunction$1
- net.minecraft.world.level.storage.loot.functions.SetItemDamageFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetLoreFunction
- net.minecraft.world.level.storage.loot.functions.SetLoreFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetLoreFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SetNameFunction
+ net.minecraft.world.level.storage.loot.functions.SetNameFunction$1
- net.minecraft.world.level.storage.loot.functions.SetNameFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetNbtFunction
- net.minecraft.world.level.storage.loot.functions.SetNbtFunction$1
+ net.minecraft.world.level.storage.loot.functions.SetNbtFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction
+ net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction$1
- net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SmeltItemFunction
+ net.minecraft.world.level.storage.loot.functions.SmeltItemFunction$1
- net.minecraft.world.level.storage.loot.functions.SmeltItemFunction$Serializer
+ net.minecraft.world.level.storage.loot.IntLimiter
- net.minecraft.world.level.storage.loot.IntLimiter$1
+ net.minecraft.world.level.storage.loot.IntLimiter$Serializer
- net.minecraft.world.level.storage.loot.LootContext
+ net.minecraft.world.level.storage.loot.LootContext$1
- net.minecraft.world.level.storage.loot.LootContext$Builder
+ net.minecraft.world.level.storage.loot.LootContext$DynamicDrop
- net.minecraft.world.level.storage.loot.LootContext$EntityTarget
+ net.minecraft.world.level.storage.loot.LootContext$EntityTarget$Serializer
- net.minecraft.world.level.storage.loot.LootContextUser
+ net.minecraft.world.level.storage.loot.LootPool
- net.minecraft.world.level.storage.loot.LootPool$1
+ net.minecraft.world.level.storage.loot.LootPool$Builder
- net.minecraft.world.level.storage.loot.LootPool$Serializer
+ net.minecraft.world.level.storage.loot.LootTable
- net.minecraft.world.level.storage.loot.LootTable$1
+ net.minecraft.world.level.storage.loot.LootTable$Builder
- net.minecraft.world.level.storage.loot.LootTable$Serializer
+ net.minecraft.world.level.storage.loot.LootTables
- net.minecraft.world.level.storage.loot.package-info
+ net.minecraft.world.level.storage.loot.parameters.LootContextParam
- net.minecraft.world.level.storage.loot.parameters.LootContextParams
- net.minecraft.world.level.storage.loot.parameters.LootContextParamSet
+ net.minecraft.world.level.storage.loot.parameters.LootContextParamSet$1
- net.minecraft.world.level.storage.loot.parameters.LootContextParamSet$Builder
+ net.minecraft.world.level.storage.loot.parameters.LootContextParamSets
+ net.minecraft.world.level.storage.loot.parameters.package-info
- net.minecraft.world.level.storage.loot.PredicateManager
- net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition
+ net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition$1
- net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.BonusLevelTableCondition
+ net.minecraft.world.level.storage.loot.predicates.BonusLevelTableCondition$1
- net.minecraft.world.level.storage.loot.predicates.BonusLevelTableCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.ConditionReference
- net.minecraft.world.level.storage.loot.predicates.ConditionReference$Serializer
+ net.minecraft.world.level.storage.loot.predicates.ConditionUserBuilder
- net.minecraft.world.level.storage.loot.predicates.DamageSourceCondition
+ net.minecraft.world.level.storage.loot.predicates.DamageSourceCondition$1
- net.minecraft.world.level.storage.loot.predicates.DamageSourceCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition
- net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition$1
+ net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.ExplosionCondition
- net.minecraft.world.level.storage.loot.predicates.ExplosionCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.InvertedLootItemCondition
- net.minecraft.world.level.storage.loot.predicates.InvertedLootItemCondition$1
+ net.minecraft.world.level.storage.loot.predicates.InvertedLootItemCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.LocationCheck
+ net.minecraft.world.level.storage.loot.predicates.LocationCheck$Serializer
- net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition$1
- net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.LootItemCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.LootItemCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.LootItemConditions
- net.minecraft.world.level.storage.loot.predicates.LootItemConditions$Serializer
+ net.minecraft.world.level.storage.loot.predicates.LootItemEntityPropertyCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemEntityPropertyCondition$1
+ net.minecraft.world.level.storage.loot.predicates.LootItemEntityPropertyCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.LootItemKilledByPlayerCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemKilledByPlayerCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceCondition$1
- net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceWithLootingCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceWithLootingCondition$1
+ net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceWithLootingCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.MatchTool
+ net.minecraft.world.level.storage.loot.predicates.MatchTool$Serializer
- net.minecraft.world.level.storage.loot.predicates.package-info
- net.minecraft.world.level.storage.loot.predicates.TimeCheck
+ net.minecraft.world.level.storage.loot.predicates.TimeCheck$1
- net.minecraft.world.level.storage.loot.predicates.TimeCheck$Builder
+ net.minecraft.world.level.storage.loot.predicates.TimeCheck$Serializer
- net.minecraft.world.level.storage.loot.predicates.WeatherCheck
+ net.minecraft.world.level.storage.loot.predicates.WeatherCheck$1
- net.minecraft.world.level.storage.loot.predicates.WeatherCheck$Builder
+ net.minecraft.world.level.storage.loot.predicates.WeatherCheck$Serializer
+ net.minecraft.world.level.storage.loot.RandomIntGenerator
- net.minecraft.world.level.storage.loot.RandomIntGenerators
+ net.minecraft.world.level.storage.loot.RandomValueBounds
- net.minecraft.world.level.storage.loot.RandomValueBounds$Serializer
+ net.minecraft.world.level.storage.loot.ValidationContext
+ net.minecraft.world.level.storage.McRegionUpgrader
+ net.minecraft.world.level.storage.package-info
- net.minecraft.world.level.storage.PlayerDataStorage
+ net.minecraft.world.level.storage.PrimaryLevelData
- net.minecraft.world.level.storage.ServerLevelData
- net.minecraft.world.level.storage.threaded.package-info
+ net.minecraft.world.level.storage.WorldData
- net.minecraft.world.level.storage.WritableLevelData
+ net.minecraft.world.level.StructureFeatureManager
- net.minecraft.world.level.TickList
+ net.minecraft.world.level.TickNextTickData
- net.minecraft.world.level.TickPriority
+ net.minecraft.world.level.timers.FunctionCallback
- net.minecraft.world.level.timers.FunctionCallback$Serializer
+ net.minecraft.world.level.timers.FunctionTagCallback
- net.minecraft.world.level.timers.FunctionTagCallback$Serializer
+ net.minecraft.world.level.timers.package-info
+ net.minecraft.world.level.timers.TimerCallback
- net.minecraft.world.level.timers.TimerCallback$Serializer
+ net.minecraft.world.level.timers.TimerCallbacks
- net.minecraft.world.level.timers.TimerQueue
+ net.minecraft.world.level.timers.TimerQueue$1
- net.minecraft.world.level.timers.TimerQueue$Event
+ net.minecraft.world.level.WorldGenLevel
- net.minecraft.world.package-info
+ net.minecraft.world.phys.AABB
- net.minecraft.world.phys.BlockHitResult
+ net.minecraft.world.phys.EntityHitResult
- net.minecraft.world.phys.HitResult
+ net.minecraft.world.phys.HitResult$Type
+ net.minecraft.world.phys.package-info
- net.minecraft.world.phys.PosAndRot
- net.minecraft.world.phys.shapes.ArrayVoxelShape
+ net.minecraft.world.phys.shapes.ArrayVoxelShape$1
- net.minecraft.world.phys.shapes.BitSetDiscreteVoxelShape
+ net.minecraft.world.phys.shapes.BooleanOp
- net.minecraft.world.phys.shapes.CollisionContext
+ net.minecraft.world.phys.shapes.CubePointRange
- net.minecraft.world.phys.shapes.CubeVoxelShape
+ net.minecraft.world.phys.shapes.DiscreteCubeMerger
- net.minecraft.world.phys.shapes.DiscreteVoxelShape
+ net.minecraft.world.phys.shapes.DiscreteVoxelShape$IntFaceConsumer
- net.minecraft.world.phys.shapes.DiscreteVoxelShape$IntLineConsumer
+ net.minecraft.world.phys.shapes.EntityCollisionContext
- net.minecraft.world.phys.shapes.EntityCollisionContext$1
+ net.minecraft.world.phys.shapes.IdenticalMerger
- net.minecraft.world.phys.shapes.IndexMerger
+ net.minecraft.world.phys.shapes.IndexMerger$IndexConsumer
- net.minecraft.world.phys.shapes.IndirectMerger
+ net.minecraft.world.phys.shapes.IntPointRange
- net.minecraft.world.phys.shapes.NonOverlappingMerger
+ net.minecraft.world.phys.shapes.OffsetDoubleList
- net.minecraft.world.phys.shapes.package-info
- net.minecraft.world.phys.shapes.Shapes
+ net.minecraft.world.phys.shapes.Shapes$DoubleLineConsumer
- net.minecraft.world.phys.shapes.SliceShape
+ net.minecraft.world.phys.shapes.SubShape
- net.minecraft.world.phys.shapes.VoxelShape
+ net.minecraft.world.phys.shapes.WorldRegionIndirectVoxelShape
+ net.minecraft.world.phys.Vec2
- net.minecraft.world.phys.Vec3
+ net.minecraft.world.scores.criteria.ObjectiveCriteria
- net.minecraft.world.scores.criteria.ObjectiveCriteria$RenderType
+ net.minecraft.world.scores.criteria.package-info
+ net.minecraft.world.scores.Objective
- net.minecraft.world.scores.package-info
- net.minecraft.world.scores.PlayerTeam
+ net.minecraft.world.scores.Score
- net.minecraft.world.scores.Scoreboard
+ net.minecraft.world.scores.ScoreboardSaveData
- net.minecraft.world.scores.Team
+ net.minecraft.world.scores.Team$CollisionRule
- net.minecraft.world.scores.Team$Visibility
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
XXX.advancements.critereon.ChangeDimensionTrigger$TriggerInstance +5M -5M | +2P -2P
```
```
XXX.advancements.critereon.LocationPredicate +5M -3M | +2P -1P
```
```
XXX.minecraft.commands.CommandSource +1P -1P
```
```
XXX.minecraft.commands.CommandSourceStack +1M
```
```
XXX.commands.arguments.DimensionTypeArgument +3M -4M
```
```
XXX.minecraft.core.DefaultedRegistry +2M -2M
```
```
XXX.minecraft.core.SerializableLong +2M -2M | +1P
```
```
XXX.minecraft.core.WritableRegistry +2M -1M | +2P -2P
```
```
XXX.core.particles.ParticleTypes +2M -1M | +1P
```
```
XXX.minecraft.resources.ResourceLocation +4M -2M | +1P
```
```
XXX.server.commands.SpreadPlayersCommand$Position +2M -2M
```
```
XXX.server.level.ServerPlayer +13M -12M | +1P -1P
```
```
XXX.server.level.WorldGenRegion -1M | +1P -1P
```
```
XXX.server.players.PlayerList +4M -5M | +1P
```
```
XXX.minecraft.sounds.SoundEvents +7P
```
```
XXX.minecraft.tags.Tag +5M
```
```
XXX.datafix.fixes.AbstractUUIDFix +11M -11M
```
```
XXX.datafix.fixes.AttributesRename +7M -7M
```
```
XXX.datafix.fixes.BlockEntityBannerColorFix +5M -5M
```
```
XXX.datafix.fixes.BlockEntityCustomNameToComponentFix +1M -1M
```
```
XXX.datafix.fixes.BlockEntityShulkerBoxColorFix +1M -1M
```
```
XXX.datafix.fixes.BlockNameFlatteningFix +1M -1M
```
```
XXX.datafix.fixes.ChunkBiomeFix +1M -1M
```
```
XXX.datafix.fixes.ChunkPalettedStorageFix +15M -15M | +11P -11P
```
```
XXX.datafix.fixes.ChunkPalettedStorageFix$Section +4M -4M | +2P -2P
```
```
XXX.datafix.fixes.ChunkStructuresTemplateRenameFix +2M -2M
```
```
XXX.datafix.fixes.ColorlessShulkerEntityFix +1M -1M
```
```
XXX.datafix.fixes.EntityArmorStandSilentFix +1M -1M
```
```
XXX.datafix.fixes.EntityCatSplitFix +1M -1M
```
```
XXX.datafix.fixes.EntityCustomNameToComponentFix +2M -2M
```
```
XXX.datafix.fixes.EntityEquipmentToArmorAndHandFix +1M -1M
```
```
XXX.datafix.fixes.EntityIdFix +1M -1M
```
```
XXX.datafix.fixes.EntityMinecartIdentifiersFix +4M -3M
```
```
XXX.datafix.fixes.EntityPaintingMotiveFix +1M -1M
```
```
XXX.datafix.fixes.EntityRedundantChanceTagsFix +3M -3M
```
```
XXX.datafix.fixes.EntityRidingToPassengersFix +3M -3M
```
```
XXX.datafix.fixes.EntityShulkerRotationFix +2M -2M
```
```
XXX.datafix.fixes.EntityStringUuidFix +1M -1M
```
```
XXX.datafix.fixes.EntityWolfColorFix +2M -2M
```
```
XXX.datafix.fixes.EntityZombieVillagerTypeFix +1M -1M
```
```
XXX.datafix.fixes.ForcePoiRebuild +4M -4M
```
```
XXX.datafix.fixes.GossipUUIDFix +3M -3M
```
```
XXX.datafix.fixes.IglooMetadataRemovalFix +4M -4M
```
```
XXX.datafix.fixes.ItemCustomNameToComponentFix +1M -1M
```
```
XXX.datafix.fixes.ItemLoreFix +4M -4M
```
```
XXX.datafix.fixes.ItemRenameFix +1M -1M
```
```
XXX.datafix.fixes.ItemStackEnchantmentNamesFix +4M -4M
```
```
XXX.datafix.fixes.ItemStackUUIDFix +6M -6M
```
```
XXX.datafix.fixes.ItemWrittenBookPagesStrictJsonFix +3M -3M
```
```
XXX.datafix.fixes.JigsawRotationFix +2M -2M
```
```
XXX.datafix.fixes.LeavesFix$LeavesSection +1M -1M
```
```
XXX.datafix.fixes.LevelDataGeneratorOptionsFix +7M -6M
```
```
XXX.datafix.fixes.LevelUUIDFix +12M -12M
```
```
XXX.datafix.fixes.MemoryExpiryDataFix +4M -4M
```
```
XXX.datafix.fixes.ObjectiveDisplayNameFix +3M -3M
```
```
XXX.datafix.fixes.OptionsAddTextBackgroundFix +2M -2M
```
```
XXX.datafix.fixes.OptionsKeyLwjgl3Fix +2M -2M
```
```
XXX.datafix.fixes.OptionsLowerCaseLanguageFix +1M -1M
```
```
XXX.datafix.fixes.PoiTypeRename +9M -9M
```
```
XXX.datafix.fixes.RecipesRenameFix +1M -1M
```
```
XXX.datafix.fixes.RedstoneWireConnectionsFix +6M -10M
```
```
XXX.datafix.fixes.RenameBiomesFix +1M -1M
```
```
XXX.datafix.fixes.SavedDataUUIDFix +6M -6M
```
```
XXX.datafix.fixes.SimpleEntityRenameFix +1P -1P
```
```
XXX.datafix.fixes.StatsCounterFix +1M -1M
```
```
XXX.datafix.fixes.StructureReferenceCountFix +2M -2M
```
```
XXX.datafix.fixes.TeamDisplayNameFix +3M -3M
```
```
XXX.datafix.fixes.VillagerFollowRangeFix +3M -3M
```
```
XXX.datafix.schemas.NamespacedSchema +2M | +2P
```
```
XXX.datafix.schemas.V704$1 +1M -1M
```
```
XXX.datafix.schemas.V705$1 +1M -1M
```
```
XXX.datafix.schemas.V99 +4M -4M
```
```
XXX.world.entity.Entity +2M -2M | -1P
```
```
XXX.entity.ai.Brain +13M -6M | +2P
```
```
XXX.ai.goal.MeleeAttackGoal +4M | +4P -4P
```
```
XXX.ai.gossip.GossipContainer +5M -4M
```
```
XXX.ai.memory.ExpirableValue +5M -3M
```
```
XXX.village.poi.PoiSection +13M -11M
```
```
XXX.entity.animal.AbstractFish +1M
```
```
XXX.animal.horse.AbstractChestedHorse -1M
```
```
XXX.animal.horse.Donkey +2M
```
```
XXX.monster.hoglin.HoglinAi +1M -1M
```
```
XXX.monster.piglin.Piglin +2M -1M
```
```
XXX.monster.piglin.PiglinAi +1M -2M | -1P
```
```
XXX.entity.npc.Villager +10M -8M
```
```
XXX.entity.npc.WanderingTraderSpawner +5M -5M | -1P
```
```
XXX.entity.projectile.ThrownEnderpearl +1M -1M
```
```
XXX.world.item.CompassItem +3M -1M | +1P
```
```
XXX.world.item.ItemStack +9M -4M | +1P
```
```
XXX.world.level.GameRules +4M -2M
```
```
XXX.level.biome.BiomeSpecialEffects +10M | +1P
```
```
XXX.level.biome.FixedBiomeSource +3M | +1P
```
```
XXX.level.biome.MultiNoiseBiomeSource +18M -4M | +4P
```
```
XXX.state.properties.Property +12M | +4P -2P
```
```
XXX.level.border.WorldBorder$Settings +1M -1M
```
```
XXX.level.chunk.ProtoChunk +2M -1M
```
```
XXX.chunk.storage.SectionStorage +7M -5M | +1P -2P
```
```
XXX.level.levelgen.DebugLevelSource +3M -1M | +2P -1P
```
```
XXX.level.levelgen.WorldGenSettings +11M -24M | +3P -8P
```
```
XXX.levelgen.carver.CanyonWorldCarver +1M -1M
```
```
XXX.levelgen.carver.CaveWorldCarver +1M -1M
```
```
XXX.levelgen.carver.NetherWorldCarver +1M -1M
```
```
XXX.levelgen.carver.UnderwaterCanyonWorldCarver +1M -1M
```
```
XXX.levelgen.carver.WorldCarver +4M -2M | +1P -1P
```
```
XXX.levelgen.feature.AbstractFlowerFeature +1M -1M
```
```
XXX.levelgen.feature.BambooFeature +1M -1M
```
```
XXX.levelgen.feature.BasaltPillarFeature +1M -1M
```
```
XXX.levelgen.feature.BastionFeature +3M -8M
```
```
XXX.levelgen.feature.BlockBlobFeature +1M -1M
```
```
XXX.levelgen.feature.BlueIceFeature +1M -1M
```
```
XXX.levelgen.feature.BuriedTreasureFeature +3M -4M
```
```
XXX.levelgen.feature.ChorusPlantFeature +1M -1M
```
```
XXX.levelgen.feature.RandomSelectorFeature +1M -1M
```
```
XXX.levelgen.feature.ReplaceBlockFeature +1M -1M
```
```
XXX.levelgen.feature.RuinedPortalFeature$FeatureStart +2M -1M
```
```
XXX.levelgen.feature.SeagrassFeature +1M -1M
```
```
XXX.levelgen.feature.ShipwreckFeature$FeatureStart +2M -1M
```
```
XXX.levelgen.feature.SimpleRandomSelectorFeature +1M -1M
```
```
XXX.levelgen.feature.SnowAndFreezeFeature +1M -1M
```
```
XXX.levelgen.feature.SpikeFeature +1M -1M
```
```
XXX.levelgen.feature.SpikeFeature$EndSpike +7M -2M | +1P
```
```
XXX.levelgen.feature.SpringFeature +1M -1M
```
```
XXX.levelgen.feature.StrongholdFeature$StrongholdStart +2M -1M
```
```
XXX.levelgen.feature.SwamplandHutFeature +1M -5M
```
```
XXX.levelgen.feature.TwistingVinesFeature +1M -1M
```
```
XXX.levelgen.feature.VillageFeature$FeatureStart +2M -1M
```
```
XXX.levelgen.feature.VoidStartPlatformFeature +1M -1M
```
```
XXX.levelgen.feature.WeightedConfiguredFeature +4M -2M | +1P
```
```
XXX.levelgen.feature.WoodlandMansionFeature$WoodlandMansionStart +3M -2M
```
```
XXX.feature.blockplacers.BlockPlacerType +3M -3M | +1P -1P
```
```
XXX.feature.blockplacers.DoublePlantPlacer +3M -2M | +2P
```
```
XXX.feature.configurations.BlockPileConfiguration +2M -2M | +1P
```
```
XXX.feature.configurations.BuriedTreasureConfiguration +2M -2M | +1P
```
```
XXX.feature.configurations.ColumnFeatureConfiguration +6M -2M | +1P
```
```
XXX.feature.configurations.CountFeatureConfiguration +2M -2M | +1P
```
```
XXX.feature.configurations.DecoratedFeatureConfiguration +4M -2M | +1P
```
```
XXX.feature.configurations.DeltaFeatureConfiguration +7M -2M | +1P
```
```
XXX.feature.configurations.DiskConfiguration +6M -3M | +1P
```
```
XXX.feature.configurations.FeatureConfiguration -1P
```
```
XXX.feature.configurations.HugeMushroomFeatureConfiguration +5M -2M | +1P
```
```
XXX.feature.configurations.LayerConfiguration +4M -2M | +1P
```
```
XXX.feature.configurations.MultiJigsawConfiguration +4M -4M | +1P
```
```
XXX.feature.configurations.NoneDecoratorConfiguration +2M -2M | +2P
```
```
XXX.feature.configurations.OceanRuinConfiguration +5M -2M | +1P
```
```
XXX.feature.configurations.OreConfiguration$Predicates +3M -1M | +2P
```
```
XXX.feature.configurations.RandomBooleanFeatureConfiguration +4M -2M | +1P
```
```
XXX.feature.configurations.RandomPatchConfiguration +14M -4M | +1P
```
```
XXX.feature.configurations.ReplaceBlockConfiguration +4M -2M | +1P
```
```
XXX.feature.configurations.SeagrassFeatureConfiguration +4M -2M | +1P
```
```
XXX.feature.configurations.SimpleBlockConfiguration +6M -6M | +1P
```
```
XXX.feature.configurations.SpikeConfiguration +6M -4M | +1P
```
```
XXX.feature.configurations.TreeConfiguration +11M -4M | +1P
```
```
XXX.feature.featuresize.FeatureSizeType +3M -3M | +1P -1P
```
```
XXX.feature.featuresize.TwoLayersFeatureSize +6M -3M | +1P
```
```
XXX.feature.foliageplacers.AcaciaFoliagePlacer +3M -1M | +1P
```
```
XXX.feature.foliageplacers.BushFoliagePlacer +3M -1M | +1P
```
```
XXX.feature.foliageplacers.FancyFoliagePlacer +2M -1M | +1P
```
```
XXX.levelgen.placement.CarvingMaskDecoratorConfiguration +4M -2M | +1P
```
```
XXX.levelgen.placement.ChanceHeightmapDecorator +1M -1M
```
```
XXX.levelgen.placement.ChancePassthroughDecorator +1M -1M
```
```
XXX.levelgen.placement.ChorusPlantPlacementDecorator +1M -1M
```
```
XXX.levelgen.placement.CountBiasedRangeDecorator +1M -1M
```
```
XXX.levelgen.placement.CountChanceHeightmapDoubleDecorator +1M -1M
```
```
XXX.levelgen.placement.CountHeighmapDoubleDecorator +1M -1M
```
```
XXX.levelgen.placement.CountHeightmap32Decorator +1M -1M
```
```
XXX.levelgen.placement.CountTopSolidDecorator +1M -1M
```
```
XXX.levelgen.placement.CountWithExtraChanceHeightmapDecorator +1M -1M
```
```
XXX.levelgen.placement.DepthAverageConfigation +5M -2M | +1P
```
```
XXX.levelgen.placement.EndGatewayPlacementDecorator +1M -1M
```
```
XXX.levelgen.placement.FeatureDecorator +5M -3M | +1P -1P
```
```
XXX.levelgen.placement.FrequencyChanceDecoratorConfiguration +4M -2M | +1P
```
```
XXX.levelgen.placement.FrequencyWithExtraChanceDecoratorConfiguration +5M -2M | +1P
```
```
XXX.levelgen.placement.LakeLavaPlacementDecorator +1M -1M
```
```
XXX.levelgen.placement.MonsterRoomPlacementDecorator +1M -1M
```
```
XXX.levelgen.placement.NoiseHeightmap32Decorator +1M -1M
```
```
XXX.levelgen.placement.NopePlacementDecorator +1M -1M
```
```
XXX.levelgen.placement.SimpleFeatureDecorator +1M -1M
```
```
XXX.levelgen.placement.TopSolidHeightMapNoiseBasedDecorator +1M -1M
```
```
XXX.placement.nether.ChanceRangeDecorator +1M -1M
```
```
XXX.placement.nether.FireDecorator +1M -1M
```
```
XXX.placement.nether.MagmaDecorator +1M -1M
```
```
XXX.levelgen.structure.NetherFossilFeature$FeatureStart +2M -1M
```
```
XXX.levelgen.structure.OceanRuinFeature$OceanRuinStart +2M -1M
```
```
XXX.levelgen.structure.PoolElementStructurePiece +2M | +1P
```
```
XXX.levelgen.structure.RuinedPortalPiece$Properties +9M -2M | +1P
```
```
XXX.saveddata.maps.MapItemSavedData +4M -1M | +2P -1P
```
```
XXX.level.storage.DerivedLevelData -2M
```
```
XXX.level.storage.LevelStorageSource$LevelStorageAccess +4M -1M
```

</details>





























<details>
<summary>
net.minecraft.advancements.critereon.ChangeDimensionTrigger$TriggerInstance
</summary>

```diff
+ boolean matches(DimensionType,DimensionType)
- boolean matches(ResourceKey,ResourceKey)
+ ChangeDimensionTrigger$TriggerInstance changedDimension(DimensionType,DimensionType)
- ChangeDimensionTrigger$TriggerInstance changedDimension(ResourceKey,ResourceKey)
+ ChangeDimensionTrigger$TriggerInstance changedDimensionFrom(DimensionType)
- ChangeDimensionTrigger$TriggerInstance changedDimensionFrom(ResourceKey)
+ ChangeDimensionTrigger$TriggerInstance changedDimensionTo(DimensionType)
- ChangeDimensionTrigger$TriggerInstance changedDimensionTo(ResourceKey)
+ void <init>(EntityPredicate$Composite,DimensionType,DimensionType)
- void <init>(EntityPredicate$Composite,ResourceKey,ResourceKey)
```

</details>































<details>
<summary>
net.minecraft.advancements.critereon.LocationPredicate
</summary>

```diff
+ JsonSyntaxException lambda$fromJson$0(ResourceLocation)
- JsonSyntaxException lambda$fromJson$2(ResourceLocation)
+ LocationPredicate inDimension(DimensionType)
- LocationPredicate inDimension(ResourceKey)
- ResourceKey lambda$fromJson$1(ResourceLocation)
+ void <init>(MinMaxBounds$Floats,MinMaxBounds$Floats,MinMaxBounds$Floats,Biome,StructureFeature,DimensionType,Boolean,LightPredicate,BlockPredicate,FluidPredicate)
- void <init>(MinMaxBounds$Floats,MinMaxBounds$Floats,MinMaxBounds$Floats,Biome,StructureFeature,ResourceKey,Boolean,LightPredicate,BlockPredicate,FluidPredicate)
- void lambda$serializeToJson$0(JsonObject,JsonElement)
```

</details>
































<details>
<summary>
net.minecraft.commands.CommandSourceStack
</summary>

```diff
- RegistryAccess registryAccess()
```

</details>



<details>
<summary>
net.minecraft.commands.arguments.DimensionTypeArgument
</summary>

```diff
+ CommandSyntaxException lambda$parse$2(ResourceLocation)
+ DimensionType getDimension(CommandContext,String)
+ DimensionType parse(StringReader)
- ResourceKey getDimension(CommandContext,String)
- ResourceLocation parse(StringReader)
+ String lambda$static$0(DimensionType)
- String lambda$static$0(ResourceKey)
```

</details>



























































<details>
<summary>
net.minecraft.core.DefaultedRegistry
</summary>

```diff
- Object registerMapping(int,ResourceKey,Object)
+ Object registerMapping(int,ResourceLocation,Object)
- void <init>(String,ResourceKey,Lifecycle)
+ void <init>(String)
```

</details>







<details>
<summary>
net.minecraft.core.SerializableLong
</summary>

```diff
- Long lambda$static$0(SerializableLong)
+ Object serialize(DynamicOps)
+ SerializableLong of(Dynamic)
- void <clinit>()
```

</details>

<details>
<summary>
net.minecraft.core.WritableRegistry
</summary>

```diff
- String toString()
+ void <init>()
- void <init>(ResourceKey,Lifecycle)
```

</details>






















<details>
<summary>
net.minecraft.core.particles.ParticleTypes
</summary>

```diff
- Codec lambda$static$0(ParticleType)
- ParticleType register(String,ParticleOptions$Deserializer,Function)
+ ParticleType register(String,ParticleOptions$Deserializer)
```

</details>
<details>
<summary>
net.minecraft.resources.ResourceLocation
</summary>

```diff
+ boolean lambda$isValidNamespace$1(int)
+ boolean lambda$isValidPath$0(int)
- boolean validNamespaceChar(char)
- boolean validPathChar(char)
- DataResult read(String)
- String toDebugFileName()
```

</details>




















































<details>
<summary>
net.minecraft.server.commands.SpreadPlayersCommand$Position
</summary>

```diff
- boolean isSafe(BlockGetter,int)
+ boolean isSafe(BlockGetter)
- int getSpawnY(BlockGetter,int)
+ int getSpawnY(BlockGetter)
```

</details>




































<details>
<summary>
net.minecraft.server.level.ServerPlayer
</summary>

```diff
+ boolean lambda$startSleepInBed$3(Monster)
- boolean lambda$startSleepInBed$4(Monster)
+ DimensionType getRespawnDimension()
+ Entity changeDimension(DimensionType)
- Entity changeDimension(ResourceKey)
- ResourceKey getRespawnDimension()
+ Style lambda$null$1(Component,Style)
- Style lambda$null$2(Component,Style)
- void lambda$addAdditionalSaveData$0(CompoundTag,Tag)
+ void lambda$awardStat$5(int,Score)
- void lambda$awardStat$6(int,Score)
+ void lambda$die$2(Component,Future)
- void lambda$die$3(Component,Future)
+ void lambda$sendMessage$6(ChatType,Component,Future)
- void lambda$sendMessage$7(ChatType,Component,UUID,Future)
+ void lambda$startSleepInBed$4(Unit)
- void lambda$startSleepInBed$5(Unit)
+ void lambda$updateScoreForCriteria$0(int,Score)
- void lambda$updateScoreForCriteria$1(int,Score)
- void sendMessage(Component,ChatType,UUID)
+ void sendMessage(Component,ChatType)
- void sendMessage(Component,UUID)
+ void sendMessage(Component)
+ void setRespawnPosition(DimensionType,BlockPos,boolean,boolean)
- void setRespawnPosition(ResourceKey,BlockPos,boolean,boolean)
```

</details>


<details>
<summary>
net.minecraft.server.level.WorldGenRegion
</summary>

```diff
+ Dimension getDimension()
```

</details>









































<details>
<summary>
net.minecraft.server.players.PlayerList
</summary>

```diff
+ void <init>(MinecraftServer,PlayerDataStorage,int)
- void <init>(MinecraftServer,RegistryAccess$RegistryHolder,PlayerDataStorage,int)
+ void broadcast(Player,double,double,double,double,DimensionType,Packet)
- void broadcast(Player,double,double,double,double,ResourceKey,Packet)
+ void broadcastAll(Packet,DimensionType)
- void broadcastAll(Packet,ResourceKey)
+ void broadcastMessage(Component,boolean)
- void broadcastMessage(Component,ChatType,UUID)
+ void broadcastMessage(Component)
```

</details>





















<details>
<summary>
net.minecraft.tags.Tag
</summary>

```diff
- Codec codec(Supplier)
- DataResult lambda$codec$1(Supplier,ResourceLocation)
- DataResult lambda$codec$3(Supplier,Tag)
- DataResult lambda$null$0(ResourceLocation)
- DataResult lambda$null$2(Tag)
```

</details>









<details>
<summary>
net.minecraft.util.datafix.fixes.AbstractUUIDFix
</summary>

```diff
+ Dynamic lambda$replaceUUIDLeastMost$3(Dynamic,String,String,String,Dynamic)
- Dynamic lambda$replaceUUIDLeastMost$3(Dynamic,String,String,String,Dynamic)
+ Dynamic lambda$replaceUUIDMLTag$2(Dynamic,String,String,Dynamic)
- Dynamic lambda$replaceUUIDMLTag$2(Dynamic,String,String,Dynamic)
+ Dynamic lambda$replaceUUIDString$1(Dynamic,String,String,Dynamic)
- Dynamic lambda$replaceUUIDString$1(Dynamic,String,String,Dynamic)
+ Optional createUUIDFromLongs(Dynamic,String,String)
- Optional createUUIDFromLongs(Dynamic,String,String)
+ Optional createUUIDFromML(Dynamic)
- Optional createUUIDFromML(Dynamic)
+ Optional createUUIDFromString(Dynamic,String)
- Optional createUUIDFromString(Dynamic,String)
+ Optional createUUIDTag(Dynamic,long,long)
- Optional createUUIDTag(Dynamic,long,long)
+ Optional lambda$createUUIDFromString$4(Dynamic,Dynamic)
- Optional lambda$createUUIDFromString$4(Dynamic,Dynamic)
+ Optional replaceUUIDLeastMost(Dynamic,String,String)
- Optional replaceUUIDLeastMost(Dynamic,String,String)
+ Optional replaceUUIDMLTag(Dynamic,String,String)
- Optional replaceUUIDMLTag(Dynamic,String,String)
+ Optional replaceUUIDString(Dynamic,String,String)
- Optional replaceUUIDString(Dynamic,String,String)
```

</details>

<details>
<summary>
net.minecraft.util.datafix.fixes.AttributesRename
</summary>

```diff
+ Dynamic fixName(Dynamic)
- Dynamic fixName(Dynamic)
+ Dynamic lambda$fixEntity$9(Dynamic)
- Dynamic lambda$fixEntity$9(Dynamic)
+ Dynamic lambda$fixItemStackTag$5(Dynamic)
- Dynamic lambda$fixItemStackTag$5(Dynamic)
+ Dynamic lambda$null$2(Dynamic)
- Dynamic lambda$null$2(Dynamic)
+ Dynamic lambda$null$4(Dynamic)
- Dynamic lambda$null$4(Dynamic)
+ Dynamic lambda$null$6(Dynamic)
- Dynamic lambda$null$6(Dynamic)
+ Dynamic lambda$null$8(Dynamic)
- Dynamic lambda$null$8(Dynamic)
```

</details>


<details>
<summary>
net.minecraft.util.datafix.fixes.BlockEntityBannerColorFix
</summary>

```diff
+ Dynamic fixTag(Dynamic)
- Dynamic fixTag(Dynamic)
+ Dynamic lambda$fixTag$0(Dynamic)
- Dynamic lambda$fixTag$0(Dynamic)
+ Dynamic lambda$fixTag$4(Dynamic)
- Dynamic lambda$fixTag$4(Dynamic)
+ Dynamic lambda$null$1(Dynamic)
- Dynamic lambda$null$1(Dynamic)
+ Dynamic lambda$null$2(Dynamic)
- Dynamic lambda$null$2(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.BlockEntityCustomNameToComponentFix
</summary>

```diff
+ Dynamic lambda$null$0(Typed,OpticFinder,Dynamic)
- Dynamic lambda$null$0(Typed,OpticFinder,Dynamic)
```

</details>

<details>
<summary>
net.minecraft.util.datafix.fixes.BlockEntityShulkerBoxColorFix
</summary>

```diff
+ Dynamic lambda$fix$0(Dynamic)
- Dynamic lambda$fix$0(Dynamic)
```

</details>

<details>
<summary>
net.minecraft.util.datafix.fixes.BlockNameFlatteningFix
</summary>

```diff
+ Function lambda$makeRule$3(DynamicOps)
- Function lambda$makeRule$3(DynamicOps)
```

</details>



<details>
<summary>
net.minecraft.util.datafix.fixes.ChunkBiomeFix
</summary>

```diff
+ Dynamic lambda$null$0(Dynamic)
- Dynamic lambda$null$0(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix
</summary>

```diff
+ Dynamic access$000()
- Dynamic access$000()
+ Dynamic access$1000()
- Dynamic access$1000()
+ Dynamic access$1400()
- Dynamic access$1400()
+ Dynamic access$1500()
- Dynamic access$1500()
+ Dynamic access$1600()
- Dynamic access$1600()
+ Dynamic access$1700()
- Dynamic access$1700()
+ Dynamic access$1800()
- Dynamic access$1800()
+ Dynamic access$1900()
- Dynamic access$1900()
+ Dynamic access$400()
- Dynamic access$400()
+ Dynamic access$500()
- Dynamic access$500()
+ Dynamic access$600()
- Dynamic access$600()
+ Dynamic fix(Dynamic)
- Dynamic fix(Dynamic)
+ int idFor(CrudeIncrementalIntIdentityHashBiMap,Dynamic)
- int idFor(CrudeIncrementalIntIdentityHashBiMap,Dynamic)
+ String getName(Dynamic)
- String getName(Dynamic)
+ String getProperty(Dynamic,String)
- String getProperty(Dynamic,String)
```

</details>


<details>
<summary>
net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Section
</summary>

```diff
+ Dynamic getBlock(int)
- Dynamic getBlock(int)
+ Dynamic write()
- Dynamic write()
+ void <init>(Dynamic)
- void <init>(Dynamic)
+ void setBlock(int,Dynamic)
- void setBlock(int,Dynamic)
```

</details>

<details>
<summary>
net.minecraft.util.datafix.fixes.ChunkStructuresTemplateRenameFix
</summary>

```diff
+ Dynamic fixTag(Dynamic,Dynamic)
- Dynamic fixTag(Dynamic,Dynamic)
+ Dynamic lambda$null$0(Typed,Dynamic)
- Dynamic lambda$null$0(Typed,Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.ColorlessShulkerEntityFix
</summary>

```diff
+ Dynamic lambda$fix$0(Dynamic)
- Dynamic lambda$fix$0(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.EntityArmorStandSilentFix
</summary>

```diff
+ Dynamic fixTag(Dynamic)
- Dynamic fixTag(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.EntityCatSplitFix
</summary>

```diff
+ Pair getNewNameAndTag(String,Dynamic)
- Pair getNewNameAndTag(String,Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.EntityCustomNameToComponentFix
</summary>

```diff
+ Dynamic fixTagCustomName(Dynamic)
- Dynamic fixTagCustomName(Dynamic)
+ Dynamic lambda$null$0(Typed,OpticFinder,Dynamic)
- Dynamic lambda$null$0(Typed,OpticFinder,Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.EntityEquipmentToArmorAndHandFix
</summary>

```diff
+ Dynamic lambda$null$1(Dynamic)
- Dynamic lambda$null$1(Dynamic)
```

</details>

<details>
<summary>
net.minecraft.util.datafix.fixes.EntityIdFix
</summary>

```diff
+ Function lambda$makeRule$3(DynamicOps)
- Function lambda$makeRule$3(DynamicOps)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.EntityMinecartIdentifiersFix
</summary>

```diff
- DataResult lambda$null$0(TaggedChoice$TaggedChoiceType,String,Dynamic)
+ Function lambda$makeRule$2(TaggedChoice$TaggedChoiceType,TaggedChoice$TaggedChoiceType,DynamicOps)
- Function lambda$makeRule$3(TaggedChoice$TaggedChoiceType,TaggedChoice$TaggedChoiceType,DynamicOps)
+ IllegalStateException lambda$null$0()
- IllegalStateException lambda$null$1()
+ Pair lambda$null$1(TaggedChoice$TaggedChoiceType,DynamicOps,TaggedChoice$TaggedChoiceType,Pair)
- Pair lambda$null$2(TaggedChoice$TaggedChoiceType,DynamicOps,TaggedChoice$TaggedChoiceType,Pair)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.EntityPaintingMotiveFix
</summary>

```diff
+ Dynamic fixTag(Dynamic)
- Dynamic fixTag(Dynamic)
```

</details>

<details>
<summary>
net.minecraft.util.datafix.fixes.EntityRedundantChanceTagsFix
</summary>

```diff
+ Dynamic lambda$null$0(Dynamic)
- Dynamic lambda$null$0(Dynamic)
+ Dynamic lambda$null$1(Dynamic)
- Dynamic lambda$null$1(Dynamic)
+ Dynamic lambda$null$2(Dynamic)
- Dynamic lambda$null$2(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.EntityRidingToPassengersFix
</summary>

```diff
+ Either lambda$null$2(Type,DynamicOps,OpticFinder,OpticFinder,Pair)
- Either lambda$null$2(Type,DynamicOps,OpticFinder,OpticFinder,Pair)
+ Function lambda$cap$6(Type,OpticFinder,OpticFinder,Type,OpticFinder,DynamicOps)
- Function lambda$cap$6(Type,OpticFinder,OpticFinder,Type,OpticFinder,DynamicOps)
+ Pair lambda$null$5(Type,DynamicOps,OpticFinder,OpticFinder,Type,OpticFinder,Pair)
- Pair lambda$null$5(Type,DynamicOps,OpticFinder,OpticFinder,Type,OpticFinder,Pair)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.EntityShulkerRotationFix
</summary>

```diff
+ Double lambda$fixTag$0(Dynamic)
- Double lambda$fixTag$0(Dynamic)
+ Dynamic fixTag(Dynamic)
- Dynamic fixTag(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.EntityStringUuidFix
</summary>

```diff
+ Dynamic lambda$null$0(Dynamic)
- Dynamic lambda$null$0(Dynamic)
```

</details>

<details>
<summary>
net.minecraft.util.datafix.fixes.EntityWolfColorFix
</summary>

```diff
+ Dynamic fixTag(Dynamic)
- Dynamic fixTag(Dynamic)
+ Dynamic lambda$fixTag$0(Dynamic)
- Dynamic lambda$fixTag$0(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.EntityZombieVillagerTypeFix
</summary>

```diff
+ Dynamic fixTag(Dynamic)
- Dynamic fixTag(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.ForcePoiRebuild
</summary>

```diff
+ Dynamic cap(Dynamic)
- Dynamic cap(Dynamic)
+ Dynamic lambda$cap$4(Dynamic)
- Dynamic lambda$cap$4(Dynamic)
+ Dynamic lambda$null$2(Dynamic)
- Dynamic lambda$null$2(Dynamic)
+ Function lambda$makeRule$1(DynamicOps)
- Function lambda$makeRule$1(DynamicOps)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.GossipUUIDFix
</summary>

```diff
+ Dynamic lambda$fix$3(Dynamic)
- Dynamic lambda$fix$3(Dynamic)
+ Dynamic lambda$null$0(Dynamic)
- Dynamic lambda$null$0(Dynamic)
+ Dynamic lambda$null$2(Dynamic)
- Dynamic lambda$null$2(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.IglooMetadataRemovalFix
</summary>

```diff
+ boolean isIglooPiece(Dynamic)
- boolean isIglooPiece(Dynamic)
+ boolean lambda$null$1(Dynamic)
- boolean lambda$null$1(Dynamic)
+ Dynamic fixTag(Dynamic)
- Dynamic fixTag(Dynamic)
+ Dynamic removeIglooPieces(Dynamic)
- Dynamic removeIglooPieces(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.ItemCustomNameToComponentFix
</summary>

```diff
+ Dynamic fixTag(Dynamic)
- Dynamic fixTag(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.ItemLoreFix
</summary>

```diff
+ Dynamic lambda$fixLoreList$5(Dynamic)
- Dynamic lambda$fixLoreList$5(Dynamic)
+ Dynamic lambda$null$0(Dynamic)
- Dynamic lambda$null$0(Dynamic)
+ Dynamic lambda$null$1(Dynamic)
- Dynamic lambda$null$1(Dynamic)
+ Dynamic lambda$null$2(Dynamic)
- Dynamic lambda$null$2(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.ItemRenameFix
</summary>

```diff
+ Function lambda$makeRule$1(DynamicOps)
- Function lambda$makeRule$1(DynamicOps)
```

</details>

<details>
<summary>
net.minecraft.util.datafix.fixes.ItemStackEnchantmentNamesFix
</summary>

```diff
+ Dynamic fixTag(Dynamic)
- Dynamic fixTag(Dynamic)
+ Dynamic lambda$fixTag$7(Dynamic)
- Dynamic lambda$fixTag$7(Dynamic)
+ Dynamic lambda$null$3(Dynamic)
- Dynamic lambda$null$3(Dynamic)
+ Dynamic lambda$null$5(Dynamic)
- Dynamic lambda$null$5(Dynamic)
```

</details>

<details>
<summary>
net.minecraft.util.datafix.fixes.ItemStackUUIDFix
</summary>

```diff
+ Dynamic lambda$null$1(Typed,OpticFinder,Dynamic)
- Dynamic lambda$null$1(Typed,OpticFinder,Dynamic)
+ Dynamic lambda$null$4(Dynamic)
- Dynamic lambda$null$4(Dynamic)
+ Dynamic lambda$updateAttributeModifiers$5(Dynamic,Dynamic)
- Dynamic lambda$updateAttributeModifiers$5(Dynamic,Dynamic)
+ Dynamic lambda$updateSkullOwner$6(Dynamic)
- Dynamic lambda$updateSkullOwner$6(Dynamic)
+ Dynamic updateAttributeModifiers(Dynamic)
- Dynamic updateAttributeModifiers(Dynamic)
+ Dynamic updateSkullOwner(Dynamic)
- Dynamic updateSkullOwner(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.ItemWrittenBookPagesStrictJsonFix
</summary>

```diff
+ Dynamic fixTag(Dynamic)
- Dynamic fixTag(Dynamic)
+ Dynamic lambda$fixTag$2(Dynamic,Dynamic)
- Dynamic lambda$fixTag$2(Dynamic,Dynamic)
+ Dynamic lambda$null$0(Dynamic)
- Dynamic lambda$null$0(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.JigsawRotationFix
</summary>

```diff
+ Dynamic fix(Dynamic)
- Dynamic fix(Dynamic)
+ Dynamic lambda$fix$0(Dynamic)
- Dynamic lambda$fix$0(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.LeavesFix$LeavesSection
</summary>

```diff
+ Dynamic makeLeafTag(Dynamic,String,boolean,int)
- Dynamic makeLeafTag(Dynamic,String,boolean,int)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.LevelDataGeneratorOptionsFix
</summary>

```diff
- DataResult lambda$null$1(Type,Dynamic)
+ Dynamic convert(String,DynamicOps)
- Dynamic convert(String,DynamicOps)
+ IllegalStateException lambda$null$1()
- IllegalStateException lambda$null$2()
+ Object lambda$convert$3(DynamicOps,Pair)
- Object lambda$convert$4(DynamicOps,Pair)
+ Pair lambda$convert$5(DynamicOps,Map$Entry)
- Pair lambda$convert$6(DynamicOps,Map$Entry)
+ Pair lambda$null$4(DynamicOps,Map$Entry)
- Pair lambda$null$5(DynamicOps,Map$Entry)
+ Typed lambda$makeRule$2(Type,Typed)
- Typed lambda$makeRule$3(Type,Typed)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.LevelUUIDFix
</summary>

```diff
+ Dynamic lambda$null$0(Dynamic)
- Dynamic lambda$null$0(Dynamic)
+ Dynamic lambda$null$10(Dynamic)
- Dynamic lambda$null$10(Dynamic)
+ Dynamic lambda$null$3(Dynamic)
- Dynamic lambda$null$3(Dynamic)
+ Dynamic lambda$null$4(Dynamic)
- Dynamic lambda$null$4(Dynamic)
+ Dynamic lambda$null$7(Dynamic)
- Dynamic lambda$null$7(Dynamic)
+ Dynamic lambda$null$8(Dynamic)
- Dynamic lambda$null$8(Dynamic)
+ Dynamic lambda$null$9(Dynamic,Dynamic)
- Dynamic lambda$null$9(Dynamic,Dynamic)
+ Dynamic lambda$updateCustomBossEvents$12(Dynamic)
- Dynamic lambda$updateCustomBossEvents$12(Dynamic)
+ Dynamic lambda$updateDragonFight$6(Dynamic)
- Dynamic lambda$updateDragonFight$6(Dynamic)
+ Dynamic updateCustomBossEvents(Dynamic)
- Dynamic updateCustomBossEvents(Dynamic)
+ Dynamic updateDragonFight(Dynamic)
- Dynamic updateDragonFight(Dynamic)
+ Dynamic updateWanderingTrader(Dynamic)
- Dynamic updateWanderingTrader(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.MemoryExpiryDataFix
</summary>

```diff
+ Dynamic fixTag(Dynamic)
- Dynamic fixTag(Dynamic)
+ Dynamic updateBrain(Dynamic)
- Dynamic updateBrain(Dynamic)
+ Dynamic updateMemories(Dynamic)
- Dynamic updateMemories(Dynamic)
+ Dynamic wrapMemoryValue(Dynamic)
- Dynamic wrapMemoryValue(Dynamic)
```

</details>

<details>
<summary>
net.minecraft.util.datafix.fixes.ObjectiveDisplayNameFix
</summary>

```diff
+ Dynamic lambda$null$1(Dynamic,Dynamic)
- Dynamic lambda$null$1(Dynamic,Dynamic)
+ Dynamic lambda$null$2(Dynamic)
- Dynamic lambda$null$2(Dynamic)
+ Function lambda$makeRule$4(DynamicOps)
- Function lambda$makeRule$4(DynamicOps)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.OptionsAddTextBackgroundFix
</summary>

```diff
+ Dynamic lambda$null$0(Dynamic,String)
- Dynamic lambda$null$0(Dynamic,String)
+ Dynamic lambda$null$1(Dynamic)
- Dynamic lambda$null$1(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.OptionsKeyLwjgl3Fix
</summary>

```diff
+ Dynamic lambda$null$2(Dynamic,Map)
- Dynamic lambda$null$2(Dynamic,Map)
+ Dynamic lambda$null$3(Dynamic)
- Dynamic lambda$null$3(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.OptionsLowerCaseLanguageFix
</summary>

```diff
+ Dynamic lambda$null$0(Dynamic)
- Dynamic lambda$null$0(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.PoiTypeRename
</summary>

```diff
+ Dynamic cap(Dynamic)
- Dynamic cap(Dynamic)
+ Dynamic lambda$cap$5(Dynamic)
- Dynamic lambda$cap$5(Dynamic)
+ Dynamic lambda$null$2(Dynamic)
- Dynamic lambda$null$2(Dynamic)
+ Dynamic lambda$null$3(Dynamic)
- Dynamic lambda$null$3(Dynamic)
+ Dynamic lambda$null$6(Dynamic)
- Dynamic lambda$null$6(Dynamic)
+ Dynamic lambda$null$7(Dynamic)
- Dynamic lambda$null$7(Dynamic)
+ Dynamic lambda$renameRecords$8(Dynamic,Stream)
- Dynamic lambda$renameRecords$8(Dynamic,Stream)
+ Function lambda$makeRule$1(DynamicOps)
- Function lambda$makeRule$1(DynamicOps)
+ Optional renameRecords(Dynamic)
- Optional renameRecords(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.RecipesRenameFix
</summary>

```diff
+ Function lambda$makeRule$1(DynamicOps)
- Function lambda$makeRule$1(DynamicOps)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.RedstoneWireConnectionsFix
</summary>

```diff
- Dynamic lambda$null$1(String,Dynamic)
- Dynamic lambda$null$2(String,Dynamic)
- Dynamic lambda$null$3(String,Dynamic)
- Dynamic lambda$null$4(String,Dynamic)
+ Dynamic lambda$null$5(String,Dynamic)
+ Dynamic lambda$null$6(String,Dynamic)
+ Dynamic lambda$null$7(String,Dynamic)
+ Dynamic lambda$null$8(String,Dynamic)
- Dynamic lambda$updateRedstoneConnections$5(Dynamic)
+ Dynamic lambda$updateRedstoneConnections$9(Dynamic)
+ Dynamic updateRedstoneConnections(Dynamic)
- Dynamic updateRedstoneConnections(Dynamic)
+ String lambda$null$1()
+ String lambda$null$2()
+ String lambda$null$3()
+ String lambda$null$4()
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.RenameBiomesFix
</summary>

```diff
+ Function lambda$makeRule$2(DynamicOps)
- Function lambda$makeRule$2(DynamicOps)
```

</details>

<details>
<summary>
net.minecraft.util.datafix.fixes.SavedDataUUIDFix
</summary>

```diff
+ Dynamic lambda$null$0(Dynamic)
- Dynamic lambda$null$0(Dynamic)
+ Dynamic lambda$null$1(Dynamic)
- Dynamic lambda$null$1(Dynamic)
+ Dynamic lambda$null$2(Dynamic)
- Dynamic lambda$null$2(Dynamic)
+ Dynamic lambda$null$3(Dynamic)
- Dynamic lambda$null$3(Dynamic)
+ Dynamic lambda$null$4(Dynamic)
- Dynamic lambda$null$4(Dynamic)
+ Dynamic lambda$null$5(Dynamic)
- Dynamic lambda$null$5(Dynamic)
```

</details>

<details>
<summary>
net.minecraft.util.datafix.fixes.StatsCounterFix
</summary>

```diff
+ Dynamic lambda$null$0(Dynamic,Dynamic)
- Dynamic lambda$null$0(Dynamic,Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.StructureReferenceCountFix
</summary>

```diff
+ Dynamic lambda$setCountToAtLeastOne$2(Dynamic)
- Dynamic lambda$setCountToAtLeastOne$2(Dynamic)
+ Dynamic setCountToAtLeastOne(Dynamic)
- Dynamic setCountToAtLeastOne(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.TeamDisplayNameFix
</summary>

```diff
+ Dynamic lambda$null$1(Dynamic,Dynamic)
- Dynamic lambda$null$1(Dynamic,Dynamic)
+ Dynamic lambda$null$2(Dynamic)
- Dynamic lambda$null$2(Dynamic)
+ Function lambda$makeRule$4(DynamicOps)
- Function lambda$makeRule$4(DynamicOps)
```

</details>

<details>
<summary>
net.minecraft.util.datafix.fixes.VillagerFollowRangeFix
</summary>

```diff
+ Dynamic fixValue(Dynamic)
- Dynamic fixValue(Dynamic)
+ Dynamic lambda$fixValue$1(Dynamic,Dynamic)
- Dynamic lambda$fixValue$1(Dynamic,Dynamic)
+ Dynamic lambda$null$0(Dynamic)
- Dynamic lambda$null$0(Dynamic)
```

</details>



<details>
<summary>
net.minecraft.util.datafix.schemas.NamespacedSchema
</summary>

```diff
- Type namespacedString()
- void <clinit>()
```

</details>



<details>
<summary>
net.minecraft.util.datafix.schemas.V704$1
</summary>

```diff
+ Object apply(DynamicOps,Object)
- Object apply(DynamicOps,Object)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.schemas.V705$1
</summary>

```diff
+ Object apply(DynamicOps,Object)
- Object apply(DynamicOps,Object)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.schemas.V99
</summary>

```diff
+ Dynamic lambda$addNames$35(Dynamic,Map,String,Dynamic)
- Dynamic lambda$addNames$35(Dynamic,Map,String,Dynamic)
+ Dynamic lambda$null$33(Dynamic,Map,Dynamic)
- Dynamic lambda$null$33(Dynamic,Map,Dynamic)
+ Dynamic lambda$null$34(Dynamic,String,Dynamic)
- Dynamic lambda$null$34(Dynamic,String,Dynamic)
+ Object addNames(Dynamic,Map,String)
- Object addNames(Dynamic,Map,String)
```

</details>









































<details>
<summary>
net.minecraft.world.entity.Entity
</summary>

```diff
+ Entity changeDimension(DimensionType)
- Entity changeDimension(ResourceKey)
- void sendMessage(Component,UUID)
+ void sendMessage(Component)
```

</details>



















<details>
<summary>
net.minecraft.world.entity.ai.Brain
</summary>

```diff
+ boolean lambda$isMemoryValue$0(Object,Object)
- boolean lambda$isMemoryValue$1(Object,Object)
- Brain$MemoryValue lambda$memories$0(Map$Entry)
- Brain$Provider provider(Collection,Collection)
- Codec codec(Collection,Collection)
- DataResult serializeStart(DynamicOps)
- Logger access$000()
+ Map lambda$addActivityAndRemoveMemoriesWhenStopped$1(Integer)
- Map lambda$addActivityAndRemoveMemoriesWhenStopped$2(Integer)
+ Object serialize(DynamicOps)
+ Set lambda$addActivityAndRemoveMemoriesWhenStopped$2(Activity)
- Set lambda$addActivityAndRemoveMemoriesWhenStopped$3(Activity)
- Stream access$200(Brain)
- Stream memories()
- void <clinit>()
+ void <init>(Collection,Collection,Dynamic)
- void <init>(Collection,Collection,ImmutableList,Supplier)
- void access$500(Brain,MemoryModuleType,Optional)
+ void readMemory(MemoryModuleType,Dynamic)
```

</details>





















<details>
<summary>
net.minecraft.world.entity.ai.goal.MeleeAttackGoal
</summary>

```diff
- boolean isTimeToAttack()
- int getAttackInterval()
- int getTicksUntilNextAttack()
- void resetAttackCooldown()
```

</details>






















<details>
<summary>
net.minecraft.world.entity.ai.gossip.GossipContainer
</summary>

```diff
+ Dynamic lambda$store$6(DynamicOps,GossipContainer$GossipEntry)
- Dynamic lambda$store$6(DynamicOps,GossipContainer$GossipEntry)
+ Dynamic store(DynamicOps)
- Dynamic store(DynamicOps)
- Stream lambda$update$7(DataResult)
+ void lambda$update$7(GossipContainer$GossipEntry)
- void lambda$update$8(GossipContainer$GossipEntry)
+ void update(Dynamic)
- void update(Dynamic)
```

</details>


<details>
<summary>
net.minecraft.world.entity.ai.memory.ExpirableValue
</summary>

```diff
- App lambda$codec$3(Codec,RecordCodecBuilder$Instance)
- Codec codec(Codec)
- ExpirableValue lambda$null$2(Object,Optional)
- Object lambda$null$0(ExpirableValue)
+ Object serialize(DynamicOps)
- Optional lambda$null$1(ExpirableValue)
+ void <init>(Function,Dynamic)
+ void <init>(Object)
```

</details>




















<details>
<summary>
net.minecraft.world.entity.ai.village.poi.PoiSection
</summary>

```diff
- App lambda$codec$2(Runnable,RecordCodecBuilder$Instance)
+ boolean lambda$getRecords$1(Predicate,Map$Entry)
- boolean lambda$getRecords$4(Predicate,Map$Entry)
- Boolean lambda$null$0(PoiSection)
- Codec codec(Runnable)
- List lambda$null$1(PoiSection)
+ Object lambda$add$3(PoiType)
+ Object lambda$add$4(BlockPos)
- Object lambda$add$6(PoiType)
- Object lambda$add$7(BlockPos)
+ Object lambda$serialize$6(DynamicOps,PoiRecord)
+ Object serialize(DynamicOps)
+ PoiRecord lambda$null$7(BlockPos,PoiType,int)
- PoiRecord lambda$null$9(BlockPos,PoiType,int)
- PoiSection lambda$codec$3(Runnable)
+ Set lambda$add$5(PoiType)
- Set lambda$add$8(PoiType)
+ Stream lambda$getRecords$2(Map$Entry)
- Stream lambda$getRecords$5(Map$Entry)
- void <init>(Runnable,boolean,List)
+ void <init>(Runnable,Dynamic)
+ void lambda$new$0(Runnable,Dynamic)
- void lambda$refresh$10(Short2ObjectMap,BlockPos,PoiType)
+ void lambda$refresh$8(Short2ObjectMap,BlockPos,PoiType)
```

</details>


<details>
<summary>
net.minecraft.world.entity.animal.AbstractFish
</summary>

```diff
- void playStepSound(BlockPos,BlockState)
```

</details>






























































<details>
<summary>
net.minecraft.world.entity.animal.horse.AbstractChestedHorse
</summary>

```diff
+ SoundEvent getAngrySound()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.horse.Donkey
</summary>

```diff
- SoundEvent getAngrySound()
- SoundEvent getEatingSound()
```

</details>
























































































<details>
<summary>
net.minecraft.world.entity.monster.hoglin.HoglinAi
</summary>

```diff
- Brain makeBrain(Brain)
+ Brain makeBrain(Dynamic)
```

</details>

<details>
<summary>
net.minecraft.world.entity.monster.piglin.Piglin
</summary>

```diff
+ Brain makeBrain(Dynamic)
- Brain makeBrain(Dynamic)
- Brain$Provider brainProvider()
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.piglin.PiglinAi
</summary>

```diff
+ Behavior admireHeldItem()
- Brain makeBrain(Piglin,Brain)
+ Brain makeBrain(Piglin,Dynamic)
```

</details>





<details>
<summary>
net.minecraft.world.entity.npc.Villager
</summary>

```diff
+ boolean lambda$getPlayerReputation$6(GossipType)
- boolean lambda$getPlayerReputation$7(GossipType)
+ boolean lambda$spawnGolemIfNeeded$8(long,Villager)
- boolean lambda$spawnGolemIfNeeded$9(long,Villager)
+ boolean lambda$tellWitnessesThatIWasMurdered$3(LivingEntity)
- boolean lambda$tellWitnessesThatIWasMurdered$4(LivingEntity)
+ Brain makeBrain(Dynamic)
- Brain makeBrain(Dynamic)
- Brain$Provider brainProvider()
+ int lambda$countFoodPointsInInventory$7(SimpleContainer,Map$Entry)
- int lambda$countFoodPointsInInventory$8(SimpleContainer,Map$Entry)
- void lambda$addAdditionalSaveData$3(CompoundTag,Tag)
+ void lambda$releasePoi$5(MinecraftServer,MemoryModuleType,GlobalPos)
- void lambda$releasePoi$6(MinecraftServer,MemoryModuleType,GlobalPos)
- void lambda$spawnGolemIfNeeded$10(long,Villager)
+ void lambda$spawnGolemIfNeeded$9(long,Villager)
+ void lambda$tellWitnessesThatIWasMurdered$4(ServerLevel,Entity,LivingEntity)
- void lambda$tellWitnessesThatIWasMurdered$5(ServerLevel,Entity,LivingEntity)
```

</details>









<details>
<summary>
net.minecraft.world.entity.npc.WanderingTraderSpawner
</summary>

```diff
+ BlockPos findSpawnPositionNear(BlockPos,int)
- BlockPos findSpawnPositionNear(LevelReader,BlockPos,int)
- boolean hasEnoughSpace(BlockGetter,BlockPos)
+ boolean hasEnoughSpace(BlockPos)
+ boolean spawn()
- boolean spawn(ServerLevel)
- int tick(ServerLevel,boolean,boolean)
+ void <init>(ServerLevel,ServerLevelData)
- void <init>(ServerLevelData)
+ void tick()
```

</details>


















<details>
<summary>
net.minecraft.world.entity.projectile.ThrownEnderpearl
</summary>

```diff
+ Entity changeDimension(DimensionType)
- Entity changeDimension(ResourceKey)
```

</details>













































































<details>
<summary>
net.minecraft.world.item.CompassItem
</summary>

```diff
- void <clinit>()
+ void addLodestoneTags(Dimension,BlockPos,CompoundTag)
- void addLodestoneTags(RegistryAccess,DimensionType,BlockPos,CompoundTag)
- void lambda$addLodestoneTags$0(CompoundTag,Tag)
```

</details>



























<details>
<summary>
net.minecraft.world.item.ItemStack
</summary>

```diff
- App lambda$static$3(RecordCodecBuilder$Instance)
- Integer lambda$null$1(ItemStack)
- Item lambda$null$0(ItemStack)
+ MutableComponent lambda$expandBlockState$2(MutableComponent)
- MutableComponent lambda$expandBlockState$6(MutableComponent)
- Optional lambda$null$2(ItemStack)
+ Style lambda$getDisplayName$3(Style)
- Style lambda$getDisplayName$7(Style)
- void <init>(ItemLike,int,Optional)
+ void lambda$appendEnchantmentNames$1(List,CompoundTag,Enchantment)
- void lambda$appendEnchantmentNames$5(List,CompoundTag,Enchantment)
+ void lambda$static$0(DecimalFormat)
- void lambda$static$4(DecimalFormat)
```

</details>
























































































<details>
<summary>
net.minecraft.world.level.GameRules
</summary>

```diff
- void <init>(DynamicLike)
- void <init>(GameRules,MinecraftServer)
+ void lambda$loadFromTag$5(CompoundTag,GameRules$Key,GameRules$Value)
- void lambda$loadFromTag$5(DynamicLike,GameRules$Key,GameRules$Value)
+ void loadFromTag(CompoundTag)
- void loadFromTag(DynamicLike)
```

</details>






<details>
<summary>
net.minecraft.world.level.biome.BiomeSpecialEffects
</summary>

```diff
- App lambda$static$8(RecordCodecBuilder$Instance)
- Integer lambda$null$0(BiomeSpecialEffects)
- Integer lambda$null$1(BiomeSpecialEffects)
- Integer lambda$null$2(BiomeSpecialEffects)
- Optional lambda$null$3(BiomeSpecialEffects)
- Optional lambda$null$4(BiomeSpecialEffects)
- Optional lambda$null$5(BiomeSpecialEffects)
- Optional lambda$null$6(BiomeSpecialEffects)
- Optional lambda$null$7(BiomeSpecialEffects)
- void <clinit>()
```

</details>











<details>
<summary>
net.minecraft.world.level.biome.FixedBiomeSource
</summary>

```diff
- Biome lambda$static$0(FixedBiomeSource)
- Codec codec()
- void <clinit>()
```

</details>











<details>
<summary>
net.minecraft.world.level.biome.MultiNoiseBiomeSource
</summary>

```diff
- App lambda$null$1(RecordCodecBuilder$Instance)
- App lambda$static$3(RecordCodecBuilder$Instance)
- boolean stable(long)
- Codec codec()
- Either lambda$null$6(MultiNoiseBiomeSource,MultiNoiseBiomeSource$Preset)
- Either lambda$null$7(MultiNoiseBiomeSource)
- Either lambda$static$8(MultiNoiseBiomeSource)
- Float lambda$getNoiseBiome$11(Biome$ClimateParameters,Pair)
+ Float lambda$getNoiseBiome$2(Biome$ClimateParameters,Pair)
- List lambda$null$2(MultiNoiseBiomeSource)
- Long lambda$null$0(MultiNoiseBiomeSource)
- MultiNoiseBiomeSource access$000(long)
- MultiNoiseBiomeSource defaultNether(long)
- MultiNoiseBiomeSource lambda$null$4(Pair)
- MultiNoiseBiomeSource lambda$static$5(Either)
+ MultiNoiseBiomeSource of(long,List)
+ Pair lambda$null$0(Biome,Biome$ClimateParameters)
- Pair lambda$null$9(Biome,Biome$ClimateParameters)
- Stream lambda$defaultNether$10(Biome)
+ Stream lambda$of$1(Biome)
- void <clinit>()
- void <init>(long,List,Optional)
```

</details>








<details>
<summary>
net.minecraft.world.level.block.state.properties.Property
</summary>

```diff
- boolean equals(Object)
- Class getValueClass()
- Codec codec()
- DataResult lambda$new$1(String)
- DataResult lambda$null$0(String)
- DataResult parseValue(DynamicOps,StateHolder,Object)
- int generateHashCode()
- int hashCode()
- StateHolder lambda$parseValue$2(StateHolder,Comparable)
- String getName()
- String toString()
- void <init>(String,Class)
```

</details>







<details>
<summary>
net.minecraft.world.level.border.WorldBorder$Settings
</summary>

```diff
+ WorldBorder$Settings read(CompoundTag,WorldBorder$Settings)
- WorldBorder$Settings read(DynamicLike,WorldBorder$Settings)
```

</details>













<details>
<summary>
net.minecraft.world.level.chunk.ProtoChunk
</summary>

```diff
- BitSet getOrCreateCarvingMask(GenerationStep$Carving)
+ BitSet lambda$getCarvingMask$5(GenerationStep$Carving)
- BitSet lambda$getOrCreateCarvingMask$5(GenerationStep$Carving)
```

</details>












<details>
<summary>
net.minecraft.world.level.chunk.storage.SectionStorage
</summary>

```diff
+ Dynamic writeColumn(ChunkPos,DynamicOps)
- Dynamic writeColumn(ChunkPos,DynamicOps)
+ int getVersion(Dynamic)
- int getVersion(Dynamic)
+ Object lambda$readColumn$2(long,Dynamic)
- Optional lambda$readColumn$2(long,Dynamic)
- void <init>(File,Function,Function,DataFixer,DataFixTypes,boolean)
+ void <init>(File,Serializer,BiFunction,Function,DataFixer,DataFixTypes,boolean)
- void lambda$writeColumn$4(long)
- void lambda$writeColumn$5(Map,DynamicOps,String,Object)
+ void readColumn(ChunkPos,DynamicOps,Object)
- void readColumn(ChunkPos,DynamicOps,Object)
```

</details>



<details>
<summary>
net.minecraft.world.level.levelgen.DebugLevelSource
</summary>

```diff
- Codec codec()
- DebugLevelSource lambda$static$0()
+ Stream lambda$static$0(Block)
- Stream lambda$static$1(Block)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.WorldGenSettings
</summary>

```diff
- App lambda$static$1(RecordCodecBuilder$Instance)
+ Biome lambda$null$1(Dynamic)
+ Biome[] lambda$createBuffetBiomeSource$3(int)
+ BiomeSource createBuffetBiomeSource(DynamicLike,long)
- boolean stable()
+ ChunkGenerator defaultEndGenerator(long)
+ ChunkGenerator defaultNetherGenerator(long)
+ ChunkGenerator make(WorldGenSettings$LevelType,Dynamic,long)
+ CompoundTag serialize()
- DataResult guardExperimental()
+ Dynamic createBuffetSettings(WorldGenSettings$BuffetGeneratorType,Set)
+ FlatLevelGeneratorSettings parseFlatSettings()
- LinkedHashMap dimensions()
- LinkedHashMap withOverworld(LinkedHashMap,ChunkGenerator)
+ Map access$300()
+ Map generators()
- NoiseBasedChunkGenerator makeDefaultOverworld(long)
+ Object getRegistryValue(DynamicLike,Registry,Object)
+ Optional lambda$make$0(String)
- Optional lambda$null$0(WorldGenSettings)
+ Pair parseBuffetSettings()
+ Stream lambda$createBuffetBiomeSource$2(Stream)
- String lambda$create$2(String)
- void <init>(long,boolean,boolean,LinkedHashMap,Optional)
- void <init>(long,boolean,boolean,LinkedHashMap)
+ void <init>(long,boolean,boolean,WorldGenSettings$LevelType,Dynamic,ChunkGenerator,String,boolean)
+ void <init>(long,boolean,boolean,WorldGenSettings$LevelType,Dynamic,ChunkGenerator)
- WorldGenSettings create(Properties)
+ WorldGenSettings fromBuffetSettings(WorldGenSettings$BuffetGeneratorType,Set)
+ WorldGenSettings fromFlatSettings(FlatLevelGeneratorSettings)
+ WorldGenSettings read(Properties)
+ WorldGenSettings readWorldGenSettings(CompoundTag,DataFixer,int)
+ WorldGenSettings withPreset(WorldGenSettings$Preset)
+ WorldGenSettings withProvider(WorldGenSettings$LevelType,Dynamic,ChunkGenerator)
+ WorldGenSettings$Preset preset()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.carver.CanyonWorldCarver
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.carver.CaveWorldCarver
</summary>

```diff
- void <init>(Codec,int)
+ void <init>(Function,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.carver.NetherWorldCarver
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.carver.UnderwaterCanyonWorldCarver
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.carver.WorldCarver
</summary>

```diff
+ CarverConfiguration createSettings(Dynamic)
- CarverConfiguration lambda$new$1(ConfiguredWorldCarver)
- Codec configuredCodec()
- ConfiguredWorldCarver lambda$new$0(CarverConfiguration)
- void <init>(Codec,int)
+ void <init>(Function,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.AbstractFlowerFeature
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.BambooFeature
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.BasaltPillarFeature
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.BastionFeature
</summary>

```diff
+ boolean isFeatureChunk(BiomeManager,ChunkGenerator,long,WorldgenRandom,int,int,Biome,ChunkPos)
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,FeatureConfiguration)
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,MultiJigsawConfiguration)
+ boolean supportsProjection()
+ int getLookupRange()
+ int getRandomSalt(ChunkGeneratorSettings)
+ int getSeparation(ChunkGeneratorSettings)
+ int getSpacing(ChunkGeneratorSettings)
+ String getFeatureName()
- void <init>(Codec)
+ void <init>(Function)
```

</details>



<details>
<summary>
net.minecraft.world.level.levelgen.feature.BlockBlobFeature
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.BlueIceFeature
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.BuriedTreasureFeature
</summary>

```diff
+ boolean isFeatureChunk(BiomeManager,ChunkGenerator,long,WorldgenRandom,int,int,Biome,ChunkPos)
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,BuriedTreasureConfiguration)
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,FeatureConfiguration)
+ int getLookupRange()
+ String getFeatureName()
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.ChorusPlantFeature
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.RandomSelectorFeature
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.ReplaceBlockFeature
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.RuinedPortalFeature$FeatureStart
</summary>

```diff
- void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
- void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,RuinedPortalConfiguration)
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.SeagrassFeature
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.ShipwreckFeature$FeatureStart
</summary>

```diff
- void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
- void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,ShipwreckConfiguration)
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.SimpleRandomSelectorFeature
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.SnowAndFreezeFeature
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.SpikeFeature
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.SpikeFeature$EndSpike
</summary>

```diff
- App lambda$static$5(RecordCodecBuilder$Instance)
- Boolean lambda$null$4(SpikeFeature$EndSpike)
+ Dynamic serialize(DynamicOps)
- Integer lambda$null$0(SpikeFeature$EndSpike)
- Integer lambda$null$1(SpikeFeature$EndSpike)
- Integer lambda$null$2(SpikeFeature$EndSpike)
- Integer lambda$null$3(SpikeFeature$EndSpike)
+ SpikeFeature$EndSpike deserialize(Dynamic)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.SpringFeature
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.StrongholdFeature$StrongholdStart
</summary>

```diff
- void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
- void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,NoneFeatureConfiguration)
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.SwamplandHutFeature
</summary>

```diff
+ boolean isSwamphut(StructureFeatureManager,BlockPos)
+ int getLookupRange()
+ int getRandomSalt(ChunkGeneratorSettings)
+ String getFeatureName()
- void <init>(Codec)
+ void <init>(Function)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.TwistingVinesFeature
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.VillageFeature$FeatureStart
</summary>

```diff
- void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
- void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,JigsawConfiguration)
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.VoidStartPlatformFeature
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.WeightedConfiguredFeature
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
- ConfiguredFeature lambda$null$0(WeightedConfiguredFeature)
+ Dynamic serialize(DynamicOps)
- Float lambda$null$1(WeightedConfiguredFeature)
- void <clinit>()
+ WeightedConfiguredFeature deserialize(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.WoodlandMansionFeature$WoodlandMansionStart
</summary>

```diff
- void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
- void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,NoneFeatureConfiguration)
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome)
- void placeInChunk(WorldGenLevel,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos)
+ void postProcess(WorldGenLevel,StructureFeatureManager,ChunkGenerator,Random,BoundingBox,ChunkPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.blockplacers.BlockPlacerType
</summary>

```diff
+ BlockPlacer deserialize(Dynamic)
- BlockPlacerType register(String,Codec)
+ BlockPlacerType register(String,Function)
- Codec codec()
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.blockplacers.DoublePlantPlacer
</summary>

```diff
- BlockPlacerType type()
- DoublePlantPlacer lambda$static$0()
+ Object serialize(DynamicOps)
- void <clinit>()
+ void <init>(Dynamic)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.BlockPileConfiguration
</summary>

```diff
+ BlockPileConfiguration deserialize(Dynamic)
- BlockStateProvider lambda$static$0(BlockPileConfiguration)
+ Dynamic serialize(DynamicOps)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.BuriedTreasureConfiguration
</summary>

```diff
+ BuriedTreasureConfiguration deserialize(Dynamic)
+ Dynamic serialize(DynamicOps)
- Float lambda$static$0(BuriedTreasureConfiguration)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.ColumnFeatureConfiguration
</summary>

```diff
- App lambda$static$4(RecordCodecBuilder$Instance)
+ ColumnFeatureConfiguration deserialize(Dynamic)
+ Dynamic serialize(DynamicOps)
- Integer lambda$null$0(ColumnFeatureConfiguration)
- Integer lambda$null$1(ColumnFeatureConfiguration)
- Integer lambda$null$2(ColumnFeatureConfiguration)
- Integer lambda$null$3(ColumnFeatureConfiguration)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.CountFeatureConfiguration
</summary>

```diff
+ CountFeatureConfiguration deserialize(Dynamic)
+ Dynamic serialize(DynamicOps)
- Integer lambda$static$0(CountFeatureConfiguration)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.DecoratedFeatureConfiguration
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
- ConfiguredDecorator lambda$null$1(DecoratedFeatureConfiguration)
- ConfiguredFeature lambda$null$0(DecoratedFeatureConfiguration)
+ DecoratedFeatureConfiguration deserialize(Dynamic)
+ Dynamic serialize(DynamicOps)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.DeltaFeatureConfiguration
</summary>

```diff
- App lambda$static$5(RecordCodecBuilder$Instance)
- BlockState lambda$null$0(DeltaFeatureConfiguration)
- BlockState lambda$null$1(DeltaFeatureConfiguration)
+ DeltaFeatureConfiguration deserialize(Dynamic)
+ Dynamic serialize(DynamicOps)
- Integer lambda$null$2(DeltaFeatureConfiguration)
- Integer lambda$null$3(DeltaFeatureConfiguration)
- Integer lambda$null$4(DeltaFeatureConfiguration)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.DiskConfiguration
</summary>

```diff
- App lambda$static$4(RecordCodecBuilder$Instance)
- BlockState lambda$null$0(DiskConfiguration)
+ DiskConfiguration deserialize(Dynamic)
+ Dynamic serialize(DynamicOps)
- Integer lambda$null$1(DiskConfiguration)
- Integer lambda$null$2(DiskConfiguration)
- List lambda$null$3(DiskConfiguration)
+ Object lambda$serialize$0(DynamicOps,BlockState)
- void <clinit>()
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.HugeMushroomFeatureConfiguration
</summary>

```diff
- App lambda$static$3(RecordCodecBuilder$Instance)
- BlockStateProvider lambda$null$0(HugeMushroomFeatureConfiguration)
- BlockStateProvider lambda$null$1(HugeMushroomFeatureConfiguration)
+ Dynamic serialize(DynamicOps)
+ HugeMushroomFeatureConfiguration deserialize(Dynamic)
- Integer lambda$null$2(HugeMushroomFeatureConfiguration)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.LayerConfiguration
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
- BlockState lambda$null$1(LayerConfiguration)
+ Dynamic serialize(DynamicOps)
- Integer lambda$null$0(LayerConfiguration)
+ LayerConfiguration deserialize(Dynamic)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.MultiJigsawConfiguration
</summary>

```diff
+ Dynamic serialize(DynamicOps)
+ JigsawConfiguration lambda$new$0(Map$Entry)
- JigsawConfiguration lambda$new$1(Map$Entry)
- List lambda$static$0(MultiJigsawConfiguration)
+ MultiJigsawConfiguration deserialize(Dynamic)
+ Object lambda$serialize$1(DynamicOps,JigsawConfiguration)
- void <clinit>()
- void <init>(List)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.NoneDecoratorConfiguration
</summary>

```diff
+ Dynamic serialize(DynamicOps)
+ NoneDecoratorConfiguration deserialize(Dynamic)
- NoneDecoratorConfiguration lambda$static$0()
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.OceanRuinConfiguration
</summary>

```diff
- App lambda$static$3(RecordCodecBuilder$Instance)
+ Dynamic serialize(DynamicOps)
- Float lambda$null$1(OceanRuinConfiguration)
- Float lambda$null$2(OceanRuinConfiguration)
+ OceanRuinConfiguration deserialize(Dynamic)
- OceanRuinFeature$Type lambda$null$0(OceanRuinConfiguration)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration$Predicates
</summary>

```diff
- boolean lambda$static$1(BlockState)
+ OreConfiguration$Predicates lambda$static$1(OreConfiguration$Predicates)
- OreConfiguration$Predicates lambda$static$2(OreConfiguration$Predicates)
- String getSerializedName()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.RandomBooleanFeatureConfiguration
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
- ConfiguredFeature lambda$null$0(RandomBooleanFeatureConfiguration)
- ConfiguredFeature lambda$null$1(RandomBooleanFeatureConfiguration)
+ Dynamic serialize(DynamicOps)
+ RandomBooleanFeatureConfiguration deserialize(Dynamic)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration
</summary>

```diff
- App lambda$static$11(RecordCodecBuilder$Instance)
- BlockPlacer lambda$null$1(RandomPatchConfiguration)
- BlockStateProvider lambda$null$0(RandomPatchConfiguration)
- Boolean lambda$null$10(RandomPatchConfiguration)
- Boolean lambda$null$8(RandomPatchConfiguration)
- Boolean lambda$null$9(RandomPatchConfiguration)
+ Dynamic serialize(DynamicOps)
- Integer lambda$null$4(RandomPatchConfiguration)
- Integer lambda$null$5(RandomPatchConfiguration)
- Integer lambda$null$6(RandomPatchConfiguration)
- Integer lambda$null$7(RandomPatchConfiguration)
- List lambda$null$2(RandomPatchConfiguration)
- List lambda$null$3(RandomPatchConfiguration)
+ Object lambda$serialize$0(DynamicOps,Block)
+ Object lambda$serialize$1(DynamicOps,BlockState)
+ RandomPatchConfiguration deserialize(Dynamic)
- void <clinit>()
- void <init>(BlockStateProvider,BlockPlacer,List,List,int,int,int,int,boolean,boolean,boolean)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.ReplaceBlockConfiguration
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
- BlockState lambda$null$0(ReplaceBlockConfiguration)
- BlockState lambda$null$1(ReplaceBlockConfiguration)
+ Dynamic serialize(DynamicOps)
+ ReplaceBlockConfiguration deserialize(Dynamic)
- void <clinit>()
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.SeagrassFeatureConfiguration
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
- Double lambda$null$1(SeagrassFeatureConfiguration)
+ Dynamic serialize(DynamicOps)
- Integer lambda$null$0(SeagrassFeatureConfiguration)
+ SeagrassFeatureConfiguration deserialize(Dynamic)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.SimpleBlockConfiguration
</summary>

```diff
- App lambda$static$4(RecordCodecBuilder$Instance)
- BlockState lambda$null$0(SimpleBlockConfiguration)
+ Dynamic serialize(DynamicOps)
- List lambda$null$1(SimpleBlockConfiguration)
- List lambda$null$2(SimpleBlockConfiguration)
- List lambda$null$3(SimpleBlockConfiguration)
+ Object lambda$serialize$0(DynamicOps,BlockState)
+ Object lambda$serialize$1(DynamicOps,BlockState)
+ Object lambda$serialize$2(DynamicOps,BlockState)
+ SimpleBlockConfiguration deserialize(Dynamic)
- void <clinit>()
+ void <init>(BlockState,BlockState[],BlockState[],BlockState[])
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.SpikeConfiguration
</summary>

```diff
- App lambda$static$3(RecordCodecBuilder$Instance)
- Boolean lambda$null$0(SpikeConfiguration)
+ Dynamic serialize(DynamicOps)
+ Integer lambda$deserialize$1(Dynamic)
- List lambda$null$1(SpikeConfiguration)
+ Object lambda$serialize$0(DynamicOps,SpikeFeature$EndSpike)
- Optional lambda$null$2(SpikeConfiguration)
+ SpikeConfiguration deserialize(Dynamic)
- void <clinit>()
- void <init>(boolean,List,Optional)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration
</summary>

```diff
- App lambda$static$9(RecordCodecBuilder$Instance)
- BlockStateProvider lambda$null$0(TreeConfiguration)
- BlockStateProvider lambda$null$1(TreeConfiguration)
- Boolean lambda$null$7(TreeConfiguration)
+ Dynamic serialize(DynamicOps)
- FeatureSize lambda$null$4(TreeConfiguration)
- FoliagePlacer lambda$null$2(TreeConfiguration)
- Heightmap$Types lambda$null$8(TreeConfiguration)
- Integer lambda$null$6(TreeConfiguration)
- List lambda$null$5(TreeConfiguration)
+ Object lambda$serialize$0(DynamicOps,TreeDecorator)
+ TreeConfiguration deserialize(Dynamic)
+ TreeDecorator lambda$deserialize$1(Dynamic)
- TrunkPlacer lambda$null$3(TreeConfiguration)
- void <clinit>()
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.featuresize.FeatureSizeType
</summary>

```diff
- Codec codec()
+ FeatureSize deserialize(Dynamic)
- FeatureSizeType register(String,Codec)
+ FeatureSizeType register(String,Function)
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.featuresize.TwoLayersFeatureSize
</summary>

```diff
- App lambda$static$3(RecordCodecBuilder$Instance)
- FeatureSizeType type()
- Integer lambda$null$0(TwoLayersFeatureSize)
- Integer lambda$null$1(TwoLayersFeatureSize)
- Integer lambda$null$2(TwoLayersFeatureSize)
+ Object serialize(DynamicOps)
+ OptionalInt lambda$new$0(Number)
- void <clinit>()
+ void <init>(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.AcaciaFoliagePlacer
</summary>

```diff
- App lambda$static$0(RecordCodecBuilder$Instance)
- FoliagePlacerType type()
- void <clinit>()
+ void <init>(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.BushFoliagePlacer
</summary>

```diff
- App lambda$static$0(RecordCodecBuilder$Instance)
- FoliagePlacerType type()
- void <clinit>()
+ void <init>(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.FancyFoliagePlacer
</summary>

```diff
- App lambda$static$0(RecordCodecBuilder$Instance)
- void <clinit>()
+ void <init>(Dynamic)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.placement.CarvingMaskDecoratorConfiguration
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
+ CarvingMaskDecoratorConfiguration deserialize(Dynamic)
+ Dynamic serialize(DynamicOps)
- Float lambda$null$1(CarvingMaskDecoratorConfiguration)
- GenerationStep$Carving lambda$null$0(CarvingMaskDecoratorConfiguration)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.ChanceHeightmapDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.ChancePassthroughDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.ChorusPlantPlacementDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.CountBiasedRangeDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.CountChanceHeightmapDoubleDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.CountHeighmapDoubleDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.CountHeightmap32Decorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.CountTopSolidDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.CountWithExtraChanceHeightmapDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.DepthAverageConfigation
</summary>

```diff
- App lambda$static$3(RecordCodecBuilder$Instance)
+ DepthAverageConfigation deserialize(Dynamic)
+ Dynamic serialize(DynamicOps)
- Integer lambda$null$0(DepthAverageConfigation)
- Integer lambda$null$1(DepthAverageConfigation)
- Integer lambda$null$2(DepthAverageConfigation)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.EndGatewayPlacementDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.FeatureDecorator
</summary>

```diff
- Codec configuredCodec()
- ConfiguredDecorator lambda$new$0(DecoratorConfiguration)
+ DecoratorConfiguration createSettings(Dynamic)
- DecoratorConfiguration lambda$new$1(ConfiguredDecorator)
- void <init>(Codec)
+ void <init>(Function)
+ void lambda$placeFeature$0(ConfiguredFeature,WorldGenLevel,StructureFeatureManager,ChunkGenerator,Random,AtomicBoolean,BlockPos)
- void lambda$placeFeature$2(ConfiguredFeature,WorldGenLevel,StructureFeatureManager,ChunkGenerator,Random,AtomicBoolean,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.FrequencyChanceDecoratorConfiguration
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
+ Dynamic serialize(DynamicOps)
- Float lambda$null$1(FrequencyChanceDecoratorConfiguration)
+ FrequencyChanceDecoratorConfiguration deserialize(Dynamic)
- Integer lambda$null$0(FrequencyChanceDecoratorConfiguration)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.FrequencyWithExtraChanceDecoratorConfiguration
</summary>

```diff
- App lambda$static$3(RecordCodecBuilder$Instance)
+ Dynamic serialize(DynamicOps)
- Float lambda$null$1(FrequencyWithExtraChanceDecoratorConfiguration)
+ FrequencyWithExtraChanceDecoratorConfiguration deserialize(Dynamic)
- Integer lambda$null$0(FrequencyWithExtraChanceDecoratorConfiguration)
- Integer lambda$null$2(FrequencyWithExtraChanceDecoratorConfiguration)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.LakeLavaPlacementDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.MonsterRoomPlacementDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.NoiseHeightmap32Decorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.NopePlacementDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.SimpleFeatureDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.TopSolidHeightMapNoiseBasedDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.nether.ChanceRangeDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.nether.FireDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.nether.MagmaDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
























<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherFossilFeature$FeatureStart
</summary>

```diff
- void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
- void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,NoneFeatureConfiguration)
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome)
```

</details>













<details>
<summary>
net.minecraft.world.level.levelgen.structure.OceanRuinFeature$OceanRuinStart
</summary>

```diff
- void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
- void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,OceanRuinConfiguration)
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome)
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.structure.PoolElementStructurePiece
</summary>

```diff
- void <clinit>()
- void lambda$addAdditionalSaveData$1(CompoundTag,Tag)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.RuinedPortalPiece$Properties
</summary>

```diff
- App lambda$static$6(RecordCodecBuilder$Instance)
- Boolean lambda$null$0(RuinedPortalPiece$Properties)
- Boolean lambda$null$2(RuinedPortalPiece$Properties)
- Boolean lambda$null$3(RuinedPortalPiece$Properties)
- Boolean lambda$null$4(RuinedPortalPiece$Properties)
- Boolean lambda$null$5(RuinedPortalPiece$Properties)
- Float lambda$null$1(RuinedPortalPiece$Properties)
+ Object serialize(DynamicOps)
- void <clinit>()
- void <init>(boolean,float,boolean,boolean,boolean,boolean)
+ void <init>(Dynamic)
```

</details>






















































<details>
<summary>
net.minecraft.world.level.saveddata.maps.MapItemSavedData
</summary>

```diff
- IllegalArgumentException lambda$load$0(CompoundTag)
- void <clinit>()
- void lambda$save$1(CompoundTag,Tag)
+ void setProperties(int,int,int,boolean,boolean,DimensionType)
- void setProperties(int,int,int,boolean,boolean,ResourceKey)
```

</details>


<details>
<summary>
net.minecraft.world.level.storage.DerivedLevelData
</summary>

```diff
+ CompoundTag getDimensionData()
+ void setDimensionData(CompoundTag)
```

</details>


<details>
<summary>
net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess
</summary>

```diff
- DataResult exportWorldGenSettings()
- DataResult lambda$exportWorldGenSettings$2(JsonElement)
+ File getDimensionPath(DimensionType)
- File getDimensionPath(ResourceKey)
- WorldData lambda$getDataTag$1(File,DataFixer)
```

</details>

<h2>Client</h2>
<details>
<summary>
Classes
</summary>

```diff
- net.minecraft.client.gui.components.Button$OnTooltip
+ net.minecraft.client.gui.components.ChatComponent
- net.minecraft.client.gui.components.Checkbox
+ net.minecraft.client.gui.components.CommandSuggestions
- net.minecraft.client.gui.components.CommandSuggestions$1
+ net.minecraft.client.gui.components.CommandSuggestions$SuggestionsList
- net.minecraft.client.gui.components.ComponentRenderUtils
+ net.minecraft.client.gui.components.ContainerObjectSelectionList
- net.minecraft.client.gui.components.ContainerObjectSelectionList$Entry
+ net.minecraft.client.gui.components.DebugScreenOverlay
- net.minecraft.client.gui.components.DebugScreenOverlay$1
+ net.minecraft.client.gui.components.EditBox
+ net.minecraft.client.gui.components.events.AbstractContainerEventHandler
- net.minecraft.client.gui.components.events.ContainerEventHandler
+ net.minecraft.client.gui.components.events.GuiEventListener
- net.minecraft.client.gui.components.events.package-info
- net.minecraft.client.gui.components.ImageButton
+ net.minecraft.client.gui.components.LerpingBossEvent
- net.minecraft.client.gui.components.LerpingBossEvent$1
+ net.minecraft.client.gui.components.LockIconButton
- net.minecraft.client.gui.components.LockIconButton$Icon
+ net.minecraft.client.gui.components.ObjectSelectionList
- net.minecraft.client.gui.components.ObjectSelectionList$Entry
+ net.minecraft.client.gui.components.OptionButton
- net.minecraft.client.gui.components.OptionsList
+ net.minecraft.client.gui.components.OptionsList$Entry
+ net.minecraft.client.gui.components.package-info
- net.minecraft.client.gui.components.PlayerTabOverlay
+ net.minecraft.client.gui.components.PlayerTabOverlay$1
- net.minecraft.client.gui.components.PlayerTabOverlay$PlayerInfoComparator
+ net.minecraft.client.gui.components.ScrolledSelectionList
- net.minecraft.client.gui.components.SliderButton
+ net.minecraft.client.gui.components.spectator.package-info
- net.minecraft.client.gui.components.spectator.SpectatorGui
+ net.minecraft.client.gui.components.StateSwitchingButton
- net.minecraft.client.gui.components.SubtitleOverlay
+ net.minecraft.client.gui.components.SubtitleOverlay$Subtitle
- net.minecraft.client.gui.components.TickableWidget
- net.minecraft.client.gui.components.toasts.AdvancementToast
+ net.minecraft.client.gui.components.toasts.package-info
+ net.minecraft.client.gui.components.toasts.RecipeToast
- net.minecraft.client.gui.components.toasts.SystemToast
+ net.minecraft.client.gui.components.toasts.SystemToast$SystemToastIds
- net.minecraft.client.gui.components.toasts.Toast
+ net.minecraft.client.gui.components.toasts.Toast$Visibility
- net.minecraft.client.gui.components.toasts.ToastComponent
+ net.minecraft.client.gui.components.toasts.ToastComponent$1
- net.minecraft.client.gui.components.toasts.ToastComponent$ToastInstance
+ net.minecraft.client.gui.components.toasts.TutorialToast
- net.minecraft.client.gui.components.toasts.TutorialToast$Icons
+ net.minecraft.client.gui.components.VolumeSlider
- net.minecraft.client.gui.components.Widget
- net.minecraft.client.gui.font.AllMissingGlyphProvider
+ net.minecraft.client.gui.font.FontManager
- net.minecraft.client.gui.font.FontManager$1
+ net.minecraft.client.gui.font.FontSet
- net.minecraft.client.gui.font.FontTexture
+ net.minecraft.client.gui.font.FontTexture$1
- net.minecraft.client.gui.font.FontTexture$Node
- net.minecraft.client.gui.font.glyphs.BakedGlyph
+ net.minecraft.client.gui.font.glyphs.BakedGlyph$Effect
- net.minecraft.client.gui.font.glyphs.EmptyGlyph
+ net.minecraft.client.gui.font.glyphs.MissingGlyph
+ net.minecraft.client.gui.font.glyphs.package-info
- net.minecraft.client.gui.font.glyphs.WhiteGlyph
- net.minecraft.client.gui.font.package-info
+ net.minecraft.client.gui.font.providers.BitmapProvider
- net.minecraft.client.gui.font.providers.BitmapProvider$1
+ net.minecraft.client.gui.font.providers.BitmapProvider$Builder
- net.minecraft.client.gui.font.providers.BitmapProvider$Glyph
+ net.minecraft.client.gui.font.providers.GlyphProviderBuilder
- net.minecraft.client.gui.font.providers.GlyphProviderBuilderType
+ net.minecraft.client.gui.font.providers.LegacyUnicodeBitmapsProvider
- net.minecraft.client.gui.font.providers.LegacyUnicodeBitmapsProvider$1
+ net.minecraft.client.gui.font.providers.LegacyUnicodeBitmapsProvider$Builder
- net.minecraft.client.gui.font.providers.LegacyUnicodeBitmapsProvider$Glyph
- net.minecraft.client.gui.font.providers.package-info
+ net.minecraft.client.gui.font.providers.TrueTypeGlyphProviderBuilder
+ net.minecraft.client.gui.font.TextFieldHelper
+ net.minecraft.client.gui.package-info
- net.minecraft.client.gui.screens.AccessibilityOptionsScreen
- net.minecraft.client.gui.screens.achievement.package-info
- net.minecraft.client.gui.screens.achievement.StatsScreen
+ net.minecraft.client.gui.screens.achievement.StatsScreen$1
- net.minecraft.client.gui.screens.achievement.StatsScreen$GeneralStatisticsList
+ net.minecraft.client.gui.screens.achievement.StatsScreen$GeneralStatisticsList$Entry
- net.minecraft.client.gui.screens.achievement.StatsScreen$ItemStatisticsList
+ net.minecraft.client.gui.screens.achievement.StatsScreen$ItemStatisticsList$ItemComparator
- net.minecraft.client.gui.screens.achievement.StatsScreen$ItemStatisticsList$ItemRow
+ net.minecraft.client.gui.screens.achievement.StatsScreen$MobsStatisticsList
- net.minecraft.client.gui.screens.achievement.StatsScreen$MobsStatisticsList$MobRow
+ net.minecraft.client.gui.screens.achievement.StatsUpdateListener
- net.minecraft.client.gui.screens.advancements.AdvancementsScreen
+ net.minecraft.client.gui.screens.advancements.AdvancementTab
- net.minecraft.client.gui.screens.advancements.AdvancementTabType
+ net.minecraft.client.gui.screens.advancements.AdvancementTabType$1
- net.minecraft.client.gui.screens.advancements.AdvancementWidget
+ net.minecraft.client.gui.screens.advancements.AdvancementWidgetType
+ net.minecraft.client.gui.screens.advancements.package-info
+ net.minecraft.client.gui.screens.AlertScreen
- net.minecraft.client.gui.screens.BackupConfirmScreen
+ net.minecraft.client.gui.screens.BackupConfirmScreen$Listener
- net.minecraft.client.gui.screens.ChatOptionsScreen
+ net.minecraft.client.gui.screens.ChatScreen
- net.minecraft.client.gui.screens.ChatScreen$1
+ net.minecraft.client.gui.screens.ConfirmLinkScreen
- net.minecraft.client.gui.screens.ConfirmScreen
+ net.minecraft.client.gui.screens.ConnectScreen
- net.minecraft.client.gui.screens.ConnectScreen$1
- net.minecraft.client.gui.screens.controls.ControlList
+ net.minecraft.client.gui.screens.controls.ControlList$1
- net.minecraft.client.gui.screens.controls.ControlList$CategoryEntry
+ net.minecraft.client.gui.screens.controls.ControlList$Entry
- net.minecraft.client.gui.screens.controls.ControlList$KeyEntry
+ net.minecraft.client.gui.screens.controls.ControlList$KeyEntry$1
- net.minecraft.client.gui.screens.controls.ControlList$KeyEntry$2
+ net.minecraft.client.gui.screens.controls.ControlsScreen
- net.minecraft.client.gui.screens.controls.package-info
+ net.minecraft.client.gui.screens.CreateBuffetWorldScreen
- net.minecraft.client.gui.screens.CreateBuffetWorldScreen$1
+ net.minecraft.client.gui.screens.CreateBuffetWorldScreen$BiomeList
- net.minecraft.client.gui.screens.CreateBuffetWorldScreen$BiomeList$Entry
+ net.minecraft.client.gui.screens.CreateFlatWorldScreen
- net.minecraft.client.gui.screens.CreateFlatWorldScreen$1
+ net.minecraft.client.gui.screens.CreateFlatWorldScreen$DetailsList
- net.minecraft.client.gui.screens.CreateFlatWorldScreen$DetailsList$Entry
+ net.minecraft.client.gui.screens.DeathScreen
+ net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen
- net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen$1
+ net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen$GameModeIcon
- net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen$GameModeSlot
- net.minecraft.client.gui.screens.DemoIntroScreen
+ net.minecraft.client.gui.screens.DirectJoinServerScreen
- net.minecraft.client.gui.screens.DisconnectedScreen
+ net.minecraft.client.gui.screens.EditServerScreen
- net.minecraft.client.gui.screens.ErrorScreen
+ net.minecraft.client.gui.screens.GenericDirtMessageScreen
- net.minecraft.client.gui.screens.InBedChatScreen
+ net.minecraft.client.gui.screens.inventory.AbstractCommandBlockEditScreen
- net.minecraft.client.gui.screens.inventory.AbstractCommandBlockEditScreen$1
+ net.minecraft.client.gui.screens.inventory.AbstractContainerScreen
- net.minecraft.client.gui.screens.inventory.AbstractFurnaceScreen
+ net.minecraft.client.gui.screens.inventory.AnvilScreen
- net.minecraft.client.gui.screens.inventory.BeaconScreen
+ net.minecraft.client.gui.screens.inventory.BeaconScreen$1
- net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconCancelButton
+ net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconConfirmButton
- net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconPowerButton
+ net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconScreenButton
- net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconSpriteScreenButton
+ net.minecraft.client.gui.screens.inventory.BlastFurnaceScreen
- net.minecraft.client.gui.screens.inventory.BookEditScreen
+ net.minecraft.client.gui.screens.inventory.BookEditScreen$DisplayCache
- net.minecraft.client.gui.screens.inventory.BookEditScreen$LineInfo
+ net.minecraft.client.gui.screens.inventory.BookEditScreen$Pos2i
- net.minecraft.client.gui.screens.inventory.BookViewScreen
+ net.minecraft.client.gui.screens.inventory.BookViewScreen$1
- net.minecraft.client.gui.screens.inventory.BookViewScreen$BookAccess
+ net.minecraft.client.gui.screens.inventory.BookViewScreen$WritableBookAccess
- net.minecraft.client.gui.screens.inventory.BookViewScreen$WrittenBookAccess
+ net.minecraft.client.gui.screens.inventory.BrewingStandScreen
- net.minecraft.client.gui.screens.inventory.CartographyTableScreen
+ net.minecraft.client.gui.screens.inventory.CommandBlockEditScreen
- net.minecraft.client.gui.screens.inventory.CommandBlockEditScreen$1
+ net.minecraft.client.gui.screens.inventory.ContainerScreen
- net.minecraft.client.gui.screens.inventory.CraftingScreen
+ net.minecraft.client.gui.screens.inventory.CreativeInventoryListener
- net.minecraft.client.gui.screens.inventory.CreativeModeInventoryScreen
+ net.minecraft.client.gui.screens.inventory.CreativeModeInventoryScreen$CustomCreativeSlot
- net.minecraft.client.gui.screens.inventory.CreativeModeInventoryScreen$ItemPickerMenu
+ net.minecraft.client.gui.screens.inventory.CreativeModeInventoryScreen$SlotWrapper
- net.minecraft.client.gui.screens.inventory.DispenserScreen
+ net.minecraft.client.gui.screens.inventory.EffectRenderingInventoryScreen
- net.minecraft.client.gui.screens.inventory.EnchantmentNames
+ net.minecraft.client.gui.screens.inventory.EnchantmentScreen
- net.minecraft.client.gui.screens.inventory.FurnaceScreen
+ net.minecraft.client.gui.screens.inventory.GrindstoneScreen
- net.minecraft.client.gui.screens.inventory.HopperScreen
+ net.minecraft.client.gui.screens.inventory.HorseInventoryScreen
- net.minecraft.client.gui.screens.inventory.InventoryScreen
+ net.minecraft.client.gui.screens.inventory.ItemCombinerScreen
- net.minecraft.client.gui.screens.inventory.JigsawBlockEditScreen
+ net.minecraft.client.gui.screens.inventory.JigsawBlockEditScreen$1
- net.minecraft.client.gui.screens.inventory.LecternScreen
+ net.minecraft.client.gui.screens.inventory.LecternScreen$1
- net.minecraft.client.gui.screens.inventory.LoomScreen
+ net.minecraft.client.gui.screens.inventory.MenuAccess
- net.minecraft.client.gui.screens.inventory.MerchantScreen
+ net.minecraft.client.gui.screens.inventory.MerchantScreen$TradeOfferButton
- net.minecraft.client.gui.screens.inventory.MinecartCommandBlockEditScreen
- net.minecraft.client.gui.screens.inventory.package-info
+ net.minecraft.client.gui.screens.inventory.PageButton
- net.minecraft.client.gui.screens.inventory.ShulkerBoxScreen
+ net.minecraft.client.gui.screens.inventory.SignEditScreen
- net.minecraft.client.gui.screens.inventory.SmithingScreen
+ net.minecraft.client.gui.screens.inventory.SmokerScreen
- net.minecraft.client.gui.screens.inventory.StonecutterScreen
+ net.minecraft.client.gui.screens.inventory.StructureBlockEditScreen
- net.minecraft.client.gui.screens.inventory.StructureBlockEditScreen$1
+ net.minecraft.client.gui.screens.inventory.StructureBlockEditScreen$2
+ net.minecraft.client.gui.screens.LanguageSelectScreen
- net.minecraft.client.gui.screens.LanguageSelectScreen$LanguageSelectionList
+ net.minecraft.client.gui.screens.LanguageSelectScreen$LanguageSelectionList$Entry
- net.minecraft.client.gui.screens.LevelLoadingScreen
+ net.minecraft.client.gui.screens.LoadingOverlay
- net.minecraft.client.gui.screens.LoadingOverlay$LogoTexture
+ net.minecraft.client.gui.screens.mco.package-info
+ net.minecraft.client.gui.screens.MenuScreens
- net.minecraft.client.gui.screens.MenuScreens$ScreenConstructor
+ net.minecraft.client.gui.screens.MouseSettingsScreen
- net.minecraft.client.gui.screens.multiplayer.JoinMultiplayerScreen
+ net.minecraft.client.gui.screens.multiplayer.package-info
+ net.minecraft.client.gui.screens.multiplayer.SafetyScreen
- net.minecraft.client.gui.screens.multiplayer.ServerSelectionList
+ net.minecraft.client.gui.screens.multiplayer.ServerSelectionList$Entry
- net.minecraft.client.gui.screens.multiplayer.ServerSelectionList$LANHeader
+ net.minecraft.client.gui.screens.multiplayer.ServerSelectionList$NetworkServerEntry
- net.minecraft.client.gui.screens.multiplayer.ServerSelectionList$OnlineServerEntry
- net.minecraft.client.gui.screens.OptionsScreen
+ net.minecraft.client.gui.screens.OptionsSubScreen
- net.minecraft.client.gui.screens.OutOfMemoryScreen
+ net.minecraft.client.gui.screens.Overlay
- net.minecraft.client.gui.screens.package-info
- net.minecraft.client.gui.screens.PauseScreen
+ net.minecraft.client.gui.screens.PresetFlatWorldScreen
- net.minecraft.client.gui.screens.PresetFlatWorldScreen$PresetInfo
+ net.minecraft.client.gui.screens.PresetFlatWorldScreen$PresetsList
- net.minecraft.client.gui.screens.PresetFlatWorldScreen$PresetsList$Entry
+ net.minecraft.client.gui.screens.ProgressScreen
- net.minecraft.client.gui.screens.ReceivingLevelScreen
+ net.minecraft.client.gui.screens.recipebook.AbstractFurnaceRecipeBookComponent
- net.minecraft.client.gui.screens.recipebook.BlastingRecipeBookComponent
+ net.minecraft.client.gui.screens.recipebook.GhostRecipe
- net.minecraft.client.gui.screens.recipebook.GhostRecipe$GhostIngredient
+ net.minecraft.client.gui.screens.recipebook.OverlayRecipeComponent
- net.minecraft.client.gui.screens.recipebook.OverlayRecipeComponent$OverlayRecipeButton
+ net.minecraft.client.gui.screens.recipebook.OverlayRecipeComponent$OverlayRecipeButton$Pos
- net.minecraft.client.gui.screens.recipebook.OverlayRecipeComponent$OverlaySmeltingRecipeButton
- net.minecraft.client.gui.screens.recipebook.package-info
+ net.minecraft.client.gui.screens.recipebook.RecipeBookComponent
- net.minecraft.client.gui.screens.recipebook.RecipeBookPage
+ net.minecraft.client.gui.screens.recipebook.RecipeBookTabButton
- net.minecraft.client.gui.screens.recipebook.RecipeButton
+ net.minecraft.client.gui.screens.recipebook.RecipeCollection
- net.minecraft.client.gui.screens.recipebook.RecipeShownListener
+ net.minecraft.client.gui.screens.recipebook.RecipeUpdateListener
- net.minecraft.client.gui.screens.recipebook.SmeltingRecipeBookComponent
+ net.minecraft.client.gui.screens.recipebook.SmokingRecipeBookComponent
- net.minecraft.client.gui.screens.resourcepacks.entries.package-info
+ net.minecraft.client.gui.screens.resourcepacks.lists.AvailableResourcePackList
+ net.minecraft.client.gui.screens.resourcepacks.lists.package-info
- net.minecraft.client.gui.screens.resourcepacks.lists.ResourcePackList
+ net.minecraft.client.gui.screens.resourcepacks.lists.ResourcePackList$ResourcePackEntry
- net.minecraft.client.gui.screens.resourcepacks.lists.SelectedResourcePackList
- net.minecraft.client.gui.screens.resourcepacks.package-info
+ net.minecraft.client.gui.screens.resourcepacks.ResourcePackSelectScreen
+ net.minecraft.client.gui.screens.Screen
- net.minecraft.client.gui.screens.ShareToLanScreen
+ net.minecraft.client.gui.screens.SkinCustomizationScreen
- net.minecraft.client.gui.screens.SoundOptionsScreen
+ net.minecraft.client.gui.screens.stream.package-info
+ net.minecraft.client.gui.screens.TitleScreen
- net.minecraft.client.gui.screens.VideoSettingsScreen
+ net.minecraft.client.gui.screens.WinScreen
- net.minecraft.client.gui.screens.worldselection.CreateWorldScreen
+ net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$1
- net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$2
+ net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$3
- net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$4
+ net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$5
- net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$SelectedGameMode
+ net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen
- net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$BooleanRuleEntry
+ net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$BooleanRuleEntry$1
- net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$CategoryRuleEntry
+ net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$EntryFactory
- net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$IntegerRuleEntry
+ net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$RuleEntry
- net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$RuleList
+ net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$RuleList$1
- net.minecraft.client.gui.screens.worldselection.EditWorldScreen
+ net.minecraft.client.gui.screens.worldselection.OptimizeWorldScreen
- net.minecraft.client.gui.screens.worldselection.SelectWorldScreen
+ net.minecraft.client.gui.screens.worldselection.WorldGenSettingsComponent
- net.minecraft.client.gui.screens.worldselection.WorldGenSettingsComponent$1
+ net.minecraft.client.gui.screens.worldselection.WorldGenSettingsComponent$2
- net.minecraft.client.gui.screens.worldselection.WorldGenSettingsComponent$3
+ net.minecraft.client.gui.screens.worldselection.WorldGenSettingsComponent$PresetEditor
- net.minecraft.client.gui.screens.worldselection.WorldPreset$1
- net.minecraft.client.gui.screens.worldselection.WorldPreset$3
- net.minecraft.client.gui.screens.worldselection.WorldPreset$5
- net.minecraft.client.gui.screens.worldselection.WorldPreset$7
- net.minecraft.client.gui.screens.worldselection.WorldPreset$PresetEditor
+ net.minecraft.core.MappedRegistry
- net.minecraft.core.NonNullList
+ net.minecraft.core.particles.package-info
- net.minecraft.core.particles.ParticleTypes$1
+ net.minecraft.core.particles.SimpleParticleType
- net.minecraft.core.particles.SimpleParticleType$1
+ net.minecraft.core.Position
- net.minecraft.core.PositionImpl
+ net.minecraft.core.Registry
- net.minecraft.core.RegistryAccess
- net.minecraft.core.Rotations
+ net.minecraft.core.SectionPos
- net.minecraft.core.SectionPos$1
+ net.minecraft.core.SerializableBoolean
- net.minecraft.data.advancements.AdvancementProvider
+ net.minecraft.data.advancements.AdventureAdvancements
- net.minecraft.data.advancements.HusbandryAdvancements
+ net.minecraft.data.advancements.NetherAdvancements
- net.minecraft.data.advancements.package-info
- net.minecraft.data.advancements.StoryAdvancements
+ net.minecraft.data.advancements.TheEndAdvancements
- net.minecraft.data.DataGenerator
+ net.minecraft.data.DataProvider
- net.minecraft.data.HashCache
+ net.minecraft.data.info.BlockListReport
- net.minecraft.data.info.CommandsReport
- net.minecraft.data.info.package-info
+ net.minecraft.data.info.RegistryDumpReport
+ net.minecraft.data.loot.BlockLoot
- net.minecraft.data.loot.ChestLoot
+ net.minecraft.data.loot.EntityLoot
- net.minecraft.data.loot.FishingLoot
+ net.minecraft.data.loot.GiftLoot
- net.minecraft.data.loot.LootTableProvider
- net.minecraft.data.loot.package-info
+ net.minecraft.data.loot.PiglinBarterLoot
+ net.minecraft.data.Main
+ net.minecraft.data.models.BlockModelGenerators
- net.minecraft.data.models.BlockModelGenerators$1
+ net.minecraft.data.models.BlockModelGenerators$BlockEntityModelGenerator
- net.minecraft.data.models.BlockModelGenerators$BlockFamilyProvider
+ net.minecraft.data.models.BlockModelGenerators$TintState
- net.minecraft.data.models.BlockModelGenerators$WoodProvider
+ net.minecraft.data.models.blockstates.BlockStateGenerator
- net.minecraft.data.models.blockstates.Condition
+ net.minecraft.data.models.blockstates.Condition$1
- net.minecraft.data.models.blockstates.Condition$CompositeCondition
+ net.minecraft.data.models.blockstates.Condition$Operation
- net.minecraft.data.models.blockstates.Condition$TerminalCondition
+ net.minecraft.data.models.blockstates.MultiPartGenerator
- net.minecraft.data.models.blockstates.MultiPartGenerator$1
+ net.minecraft.data.models.blockstates.MultiPartGenerator$ConditionalEntry
- net.minecraft.data.models.blockstates.MultiPartGenerator$Entry
+ net.minecraft.data.models.blockstates.MultiVariantGenerator
+ net.minecraft.data.models.blockstates.package-info
- net.minecraft.data.models.blockstates.PropertyDispatch
+ net.minecraft.data.models.blockstates.PropertyDispatch$1
- net.minecraft.data.models.blockstates.PropertyDispatch$C1
+ net.minecraft.data.models.blockstates.PropertyDispatch$C2
- net.minecraft.data.models.blockstates.PropertyDispatch$C3
+ net.minecraft.data.models.blockstates.PropertyDispatch$C4
- net.minecraft.data.models.blockstates.PropertyDispatch$C5
+ net.minecraft.data.models.blockstates.PropertyDispatch$PentaFunction
- net.minecraft.data.models.blockstates.PropertyDispatch$QuadFunction
+ net.minecraft.data.models.blockstates.PropertyDispatch$TriFunction
- net.minecraft.data.models.blockstates.PropertyValue
+ net.minecraft.data.models.blockstates.Selector
- net.minecraft.data.models.blockstates.Variant
+ net.minecraft.data.models.blockstates.VariantProperties
- net.minecraft.data.models.blockstates.VariantProperties$Rotation
+ net.minecraft.data.models.blockstates.VariantProperty
- net.minecraft.data.models.blockstates.VariantProperty$Value
+ net.minecraft.data.models.ItemModelGenerators
- net.minecraft.data.models.model.DelegatedModel
+ net.minecraft.data.models.model.ModelLocationUtils
- net.minecraft.data.models.model.ModelTemplate
+ net.minecraft.data.models.model.ModelTemplates
- net.minecraft.data.models.model.package-info
- net.minecraft.data.models.model.TexturedModel
+ net.minecraft.data.models.model.TexturedModel$Provider
- net.minecraft.data.models.model.TextureMapping
+ net.minecraft.data.models.model.TextureSlot
- net.minecraft.data.models.ModelProvider
+ net.minecraft.data.models.package-info
- net.minecraft.data.package-info
+ net.minecraft.data.recipes.FinishedRecipe
+ net.minecraft.data.recipes.package-info
- net.minecraft.data.recipes.RecipeProvider
+ net.minecraft.data.recipes.ShapedRecipeBuilder
- net.minecraft.data.recipes.ShapedRecipeBuilder$Result
+ net.minecraft.data.recipes.ShapelessRecipeBuilder
- net.minecraft.data.recipes.ShapelessRecipeBuilder$Result
+ net.minecraft.data.recipes.SimpleCookingRecipeBuilder
- net.minecraft.data.recipes.SimpleCookingRecipeBuilder$Result
+ net.minecraft.data.recipes.SingleItemRecipeBuilder
- net.minecraft.data.recipes.SingleItemRecipeBuilder$Result
+ net.minecraft.data.recipes.SpecialRecipeBuilder
- net.minecraft.data.recipes.SpecialRecipeBuilder$1
- net.minecraft.data.structures.NbtToSnbt
+ net.minecraft.data.structures.package-info
+ net.minecraft.data.structures.SnbtToNbt
- net.minecraft.data.structures.SnbtToNbt$Filter
+ net.minecraft.data.structures.SnbtToNbt$TaskResult
- net.minecraft.data.structures.StructureUpdater
- net.minecraft.data.tags.BlockTagsProvider
+ net.minecraft.data.tags.EntityTypeTagsProvider
- net.minecraft.data.tags.FluidTagsProvider
+ net.minecraft.data.tags.ItemTagsProvider
+ net.minecraft.data.tags.package-info
- net.minecraft.data.tags.TagsProvider
+ net.minecraft.data.tags.TagsProvider$1
- net.minecraft.data.tags.TagsProvider$TagAppender
- net.minecraft.gametest.framework.BeforeBatch
+ net.minecraft.gametest.framework.GameTest
- net.minecraft.gametest.framework.GameTestAssertException
+ net.minecraft.gametest.framework.GameTestAssertPosException
- net.minecraft.gametest.framework.GameTestBatch
+ net.minecraft.gametest.framework.GameTestBatchRunner
- net.minecraft.gametest.framework.GameTestBatchRunner$1
+ net.minecraft.gametest.framework.GameTestEvent
- net.minecraft.gametest.framework.GameTestGenerator
+ net.minecraft.gametest.framework.GameTestHelper
- net.minecraft.gametest.framework.GameTestInfo
+ net.minecraft.gametest.framework.GameTestListener
- net.minecraft.gametest.framework.GameTestRegistry
+ net.minecraft.gametest.framework.GameTestRunner
- net.minecraft.gametest.framework.GameTestRunner$1
+ net.minecraft.gametest.framework.GameTestSequence
- net.minecraft.gametest.framework.GameTestSequence$Condition
+ net.minecraft.gametest.framework.GameTestServer
- net.minecraft.gametest.framework.GameTestServer$1
+ net.minecraft.gametest.framework.GameTestTicker
- net.minecraft.gametest.framework.GameTestTimeoutException
+ net.minecraft.gametest.framework.JUnitLikeTestReporter
- net.minecraft.gametest.framework.LogTestReporter
+ net.minecraft.gametest.framework.MultipleTestTracker
- net.minecraft.gametest.framework.package-info
- net.minecraft.gametest.framework.StructureUtils
+ net.minecraft.gametest.framework.TeamcityTestReporter
- net.minecraft.gametest.framework.TestClassNameArgument
+ net.minecraft.gametest.framework.TestCommand
- net.minecraft.gametest.framework.TestCommand$TestSummaryDisplayer
+ net.minecraft.gametest.framework.TestFunction
- net.minecraft.gametest.framework.TestFunctionArgument
+ net.minecraft.gametest.framework.TestReporter
+ net.minecraft.locale.Language
- net.minecraft.locale.package-info
+ net.minecraft.nbt.ByteArrayTag
- net.minecraft.nbt.ByteArrayTag$1
+ net.minecraft.nbt.ByteTag
- net.minecraft.nbt.ByteTag$1
+ net.minecraft.nbt.ByteTag$Cache
- net.minecraft.nbt.CollectionTag
+ net.minecraft.nbt.CompoundTag
- net.minecraft.nbt.CompoundTag$1
+ net.minecraft.nbt.DoubleTag
- net.minecraft.nbt.DoubleTag$1
+ net.minecraft.nbt.EndTag
- net.minecraft.nbt.EndTag$1
+ net.minecraft.nbt.FloatTag
- net.minecraft.nbt.FloatTag$1
+ net.minecraft.nbt.IntArrayTag
- net.minecraft.nbt.IntArrayTag$1
+ net.minecraft.nbt.IntTag
- net.minecraft.nbt.IntTag$1
+ net.minecraft.nbt.IntTag$Cache
- net.minecraft.nbt.ListTag
+ net.minecraft.nbt.ListTag$1
- net.minecraft.nbt.LongArrayTag
+ net.minecraft.nbt.LongArrayTag$1
- net.minecraft.nbt.LongTag
+ net.minecraft.nbt.LongTag$1
- net.minecraft.nbt.LongTag$Cache
+ net.minecraft.nbt.NbtAccounter
- net.minecraft.nbt.NbtAccounter$1
+ net.minecraft.nbt.NbtIo
- net.minecraft.nbt.NbtOps
- net.minecraft.nbt.NbtOps$NbtRecordBuilder
+ net.minecraft.nbt.NbtUtils
- net.minecraft.nbt.NumericTag
+ net.minecraft.nbt.package-info
+ net.minecraft.nbt.ShortTag
- net.minecraft.nbt.ShortTag$1
+ net.minecraft.nbt.ShortTag$Cache
- net.minecraft.nbt.StringTag
+ net.minecraft.nbt.StringTag$1
- net.minecraft.nbt.Tag
+ net.minecraft.nbt.TagParser
- net.minecraft.nbt.TagType
+ net.minecraft.nbt.TagType$1
- net.minecraft.nbt.TagTypes
- net.minecraft.network.chat.BaseComponent
+ net.minecraft.network.chat.ChatType
- net.minecraft.network.chat.ClickEvent
+ net.minecraft.network.chat.ClickEvent$Action
- net.minecraft.network.chat.CommonComponents
+ net.minecraft.network.chat.Component
- net.minecraft.network.chat.Component$ContentConsumer
+ net.minecraft.network.chat.Component$Serializer
- net.minecraft.network.chat.Component$StyledContentConsumer
+ net.minecraft.network.chat.ComponentUtils
- net.minecraft.network.chat.ContextAwareComponent
+ net.minecraft.network.chat.HoverEvent
- net.minecraft.network.chat.HoverEvent$Action
+ net.minecraft.network.chat.HoverEvent$EntityTooltipInfo
- net.minecraft.network.chat.HoverEvent$ItemStackInfo
+ net.minecraft.network.chat.KeybindComponent
- net.minecraft.network.chat.MutableComponent
+ net.minecraft.network.chat.NbtComponent
- net.minecraft.network.chat.NbtComponent$BlockNbtComponent
+ net.minecraft.network.chat.NbtComponent$EntityNbtComponent
- net.minecraft.network.chat.NbtComponent$StorageNbtComponent
- net.minecraft.network.chat.package-info
+ net.minecraft.network.chat.ScoreComponent
- net.minecraft.network.chat.SelectorComponent
+ net.minecraft.network.chat.Style
- net.minecraft.network.chat.Style$1
+ net.minecraft.network.chat.Style$Serializer
- net.minecraft.network.chat.TextColor
+ net.minecraft.network.chat.TextComponent
- net.minecraft.network.chat.TranslatableComponent
+ net.minecraft.network.chat.TranslatableFormatException
- net.minecraft.network.CipherBase
+ net.minecraft.network.CipherDecoder
- net.minecraft.network.CipherEncoder
+ net.minecraft.network.CompressionDecoder
- net.minecraft.network.CompressionEncoder
+ net.minecraft.network.Connection
- net.minecraft.network.Connection$1
+ net.minecraft.network.Connection$2
- net.minecraft.network.Connection$PacketHolder
+ net.minecraft.network.ConnectionProtocol
- net.minecraft.network.ConnectionProtocol$1
+ net.minecraft.network.ConnectionProtocol$PacketSet
- net.minecraft.network.ConnectionProtocol$ProtocolBuilder
+ net.minecraft.network.FriendlyByteBuf
+ net.minecraft.network.package-info
- net.minecraft.network.PacketDecoder
+ net.minecraft.network.PacketEncoder
- net.minecraft.network.PacketListener
- net.minecraft.network.protocol.game.ClientboundAddEntityPacket
+ net.minecraft.network.protocol.game.ClientboundAddExperienceOrbPacket
- net.minecraft.network.protocol.game.ClientboundAddGlobalEntityPacket
+ net.minecraft.network.protocol.game.ClientboundAddMobPacket
- net.minecraft.network.protocol.game.ClientboundAddPaintingPacket
+ net.minecraft.network.protocol.game.ClientboundAddPlayerPacket
- net.minecraft.network.protocol.game.ClientboundAnimatePacket
+ net.minecraft.network.protocol.game.ClientboundAwardStatsPacket
- net.minecraft.network.protocol.game.ClientboundBlockBreakAckPacket
+ net.minecraft.network.protocol.game.ClientboundBlockDestructionPacket
- net.minecraft.network.protocol.game.ClientboundBlockEntityDataPacket
+ net.minecraft.network.protocol.game.ClientboundBlockEventPacket
- net.minecraft.network.protocol.game.ClientboundBlockUpdatePacket
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$1
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket$Operation
- net.minecraft.network.protocol.game.ClientboundChangeDifficultyPacket
+ net.minecraft.network.protocol.game.ClientboundChatPacket
- net.minecraft.network.protocol.game.ClientboundChunkBlocksUpdatePacket
+ net.minecraft.network.protocol.game.ClientboundChunkBlocksUpdatePacket$BlockUpdate
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket
- net.minecraft.network.protocol.game.ClientboundCommandsPacket$1
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket$Entry
- net.minecraft.network.protocol.game.ClientboundCommandSuggestionsPacket
- net.minecraft.network.protocol.game.ClientboundContainerAckPacket
+ net.minecraft.network.protocol.game.ClientboundContainerClosePacket
- net.minecraft.network.protocol.game.ClientboundContainerSetContentPacket
+ net.minecraft.network.protocol.game.ClientboundContainerSetDataPacket
- net.minecraft.network.protocol.game.ClientboundContainerSetSlotPacket
+ net.minecraft.network.protocol.game.ClientboundCooldownPacket
- net.minecraft.network.protocol.game.ClientboundCustomPayloadPacket
+ net.minecraft.network.protocol.game.ClientboundCustomSoundPacket
- net.minecraft.network.protocol.game.ClientboundDisconnectPacket
+ net.minecraft.network.protocol.game.ClientboundEntityEventPacket
- net.minecraft.network.protocol.game.ClientboundExplodePacket
+ net.minecraft.network.protocol.game.ClientboundForgetLevelChunkPacket
- net.minecraft.network.protocol.game.ClientboundGameEventPacket
+ net.minecraft.network.protocol.game.ClientboundHorseScreenOpenPacket
- net.minecraft.network.protocol.game.ClientboundKeepAlivePacket
+ net.minecraft.network.protocol.game.ClientboundLevelChunkPacket
- net.minecraft.network.protocol.game.ClientboundLevelEventPacket
+ net.minecraft.network.protocol.game.ClientboundLevelParticlesPacket
- net.minecraft.network.protocol.game.ClientboundLightUpdatePacket
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
- net.minecraft.network.protocol.game.ClientboundPlayerCombatPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerCombatPacket$1
- net.minecraft.network.protocol.game.ClientboundPlayerCombatPacket$Event
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket
- net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$1
+ net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$Action
- net.minecraft.network.protocol.game.ClientboundPlayerInfoPacket$PlayerUpdate
+ net.minecraft.network.protocol.game.ClientboundPlayerLookAtPacket
- net.minecraft.network.protocol.game.ClientboundPlayerPositionPacket
+ net.minecraft.network.protocol.game.ClientboundPlayerPositionPacket$RelativeArgument
- net.minecraft.network.protocol.game.ClientboundRecipePacket
+ net.minecraft.network.protocol.game.ClientboundRecipePacket$State
- net.minecraft.network.protocol.game.ClientboundRemoveEntitiesPacket
+ net.minecraft.network.protocol.game.ClientboundRemoveMobEffectPacket
- net.minecraft.network.protocol.game.ClientboundResourcePackPacket
+ net.minecraft.network.protocol.game.ClientboundRespawnPacket
- net.minecraft.network.protocol.game.ClientboundRotateHeadPacket
+ net.minecraft.network.protocol.game.ClientboundSelectAdvancementsTabPacket
- net.minecraft.network.protocol.game.ClientboundSetBorderPacket
+ net.minecraft.network.protocol.game.ClientboundSetBorderPacket$1
- net.minecraft.network.protocol.game.ClientboundSetBorderPacket$Type
+ net.minecraft.network.protocol.game.ClientboundSetCameraPacket
- net.minecraft.network.protocol.game.ClientboundSetCarriedItemPacket
+ net.minecraft.network.protocol.game.ClientboundSetChunkCacheCenterPacket
- net.minecraft.network.protocol.game.ClientboundSetChunkCacheRadiusPacket
+ net.minecraft.network.protocol.game.ClientboundSetDefaultSpawnPositionPacket
- net.minecraft.network.protocol.game.ClientboundSetDisplayObjectivePacket
+ net.minecraft.network.protocol.game.ClientboundSetEntityDataPacket
- net.minecraft.network.protocol.game.ClientboundSetEntityLinkPacket
+ net.minecraft.network.protocol.game.ClientboundSetEntityMotionPacket
- net.minecraft.network.protocol.game.ClientboundSetEquippedItemPacket
+ net.minecraft.network.protocol.game.ClientboundSetExperiencePacket
- net.minecraft.network.protocol.game.ClientboundSetHealthPacket
+ net.minecraft.network.protocol.game.ClientboundSetObjectivePacket
- net.minecraft.network.protocol.game.ClientboundSetPassengersPacket
+ net.minecraft.network.protocol.game.ClientboundSetPlayerTeamPacket
- net.minecraft.network.protocol.game.ClientboundSetScorePacket
+ net.minecraft.network.protocol.game.ClientboundSetTimePacket
- net.minecraft.network.protocol.game.ClientboundSetTitlesPacket
+ net.minecraft.network.protocol.game.ClientboundSetTitlesPacket$Type
- net.minecraft.network.protocol.game.ClientboundSoundEntityPacket
+ net.minecraft.network.protocol.game.ClientboundSoundPacket
- net.minecraft.network.protocol.game.ClientboundStopSoundPacket
+ net.minecraft.network.protocol.game.ClientboundTabListPacket
- net.minecraft.network.protocol.game.ClientboundTagQueryPacket
+ net.minecraft.network.protocol.game.ClientboundTakeItemEntityPacket
- net.minecraft.network.protocol.game.ClientboundTeleportEntityPacket
+ net.minecraft.network.protocol.game.ClientboundUpdateAdvancementsPacket
- net.minecraft.network.protocol.game.ClientboundUpdateAttributesPacket
+ net.minecraft.network.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
- net.minecraft.network.protocol.game.ClientboundUpdateMobEffectPacket
+ net.minecraft.network.protocol.game.ClientboundUpdateRecipesPacket
- net.minecraft.network.protocol.game.ClientboundUpdateTagsPacket
+ net.minecraft.network.protocol.game.ClientGamePacketListener
+ net.minecraft.network.protocol.game.DebugEntityNameGenerator
- net.minecraft.network.protocol.game.DebugPackets
- net.minecraft.network.protocol.game.package-info
- net.minecraft.network.protocol.game.ServerboundAcceptTeleportationPacket
+ net.minecraft.network.protocol.game.ServerboundBlockEntityTagQuery
- net.minecraft.network.protocol.game.ServerboundChangeDifficultyPacket
+ net.minecraft.network.protocol.game.ServerboundChatPacket
- net.minecraft.network.protocol.game.ServerboundClientCommandPacket
+ net.minecraft.network.protocol.game.ServerboundClientCommandPacket$Action
- net.minecraft.network.protocol.game.ServerboundClientInformationPacket
+ net.minecraft.network.protocol.game.ServerboundCommandSuggestionPacket
- net.minecraft.network.protocol.game.ServerboundContainerAckPacket
+ net.minecraft.network.protocol.game.ServerboundContainerButtonClickPacket
- net.minecraft.network.protocol.game.ServerboundContainerClickPacket
+ net.minecraft.network.protocol.game.ServerboundContainerClosePacket
- net.minecraft.network.protocol.game.ServerboundCustomPayloadPacket
+ net.minecraft.network.protocol.game.ServerboundEditBookPacket
- net.minecraft.network.protocol.game.ServerboundEntityTagQuery
+ net.minecraft.network.protocol.game.ServerboundInteractPacket
- net.minecraft.network.protocol.game.ServerboundInteractPacket$Action
+ net.minecraft.network.protocol.game.ServerboundJigsawGeneratePacket
- net.minecraft.network.protocol.game.ServerboundKeepAlivePacket
+ net.minecraft.network.protocol.game.ServerboundLockDifficultyPacket
- net.minecraft.network.protocol.game.ServerboundMovePlayerPacket
+ net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$Pos
- net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$PosRot
+ net.minecraft.network.protocol.game.ServerboundMovePlayerPacket$Rot
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
- net.minecraft.network.protocol.game.ServerboundRecipeBookUpdatePacket
+ net.minecraft.network.protocol.game.ServerboundRecipeBookUpdatePacket$Purpose
- net.minecraft.network.protocol.game.ServerboundRenameItemPacket
+ net.minecraft.network.protocol.game.ServerboundResourcePackPacket
- net.minecraft.network.protocol.game.ServerboundResourcePackPacket$Action
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
+ net.minecraft.network.protocol.game.ServerGamePacketListener
+ net.minecraft.network.protocol.handshake.ClientIntentionPacket
+ net.minecraft.network.protocol.handshake.package-info
- net.minecraft.network.protocol.handshake.ServerHandshakePacketListener
+ net.minecraft.network.protocol.login.ClientboundCustomQueryPacket
- net.minecraft.network.protocol.login.ClientboundGameProfilePacket
+ net.minecraft.network.protocol.login.ClientboundHelloPacket
- net.minecraft.network.protocol.login.ClientboundLoginCompressionPacket
+ net.minecraft.network.protocol.login.ClientboundLoginDisconnectPacket
- net.minecraft.network.protocol.login.ClientLoginPacketListener
- net.minecraft.network.protocol.login.package-info
+ net.minecraft.network.protocol.login.ServerboundCustomQueryPacket
- net.minecraft.network.protocol.login.ServerboundHelloPacket
+ net.minecraft.network.protocol.login.ServerboundKeyPacket
- net.minecraft.network.protocol.login.ServerLoginPacketListener
+ net.minecraft.network.protocol.package-info
- net.minecraft.network.protocol.Packet
+ net.minecraft.network.protocol.PacketFlow
- net.minecraft.network.protocol.PacketUtils
+ net.minecraft.network.protocol.status.ClientboundPongResponsePacket
- net.minecraft.network.protocol.status.ClientboundStatusResponsePacket
- net.minecraft.network.protocol.status.ClientStatusPacketListener
- net.minecraft.network.protocol.status.package-info
- net.minecraft.network.protocol.status.ServerboundPingRequestPacket
+ net.minecraft.network.protocol.status.ServerboundStatusRequestPacket
+ net.minecraft.network.protocol.status.ServerStatus
- net.minecraft.network.protocol.status.ServerStatus$Players
+ net.minecraft.network.protocol.status.ServerStatus$Players$Serializer
- net.minecraft.network.protocol.status.ServerStatus$Serializer
+ net.minecraft.network.protocol.status.ServerStatus$Version
- net.minecraft.network.protocol.status.ServerStatus$Version$Serializer
+ net.minecraft.network.protocol.status.ServerStatusPacketListener
+ net.minecraft.network.SkipPacketException
+ net.minecraft.network.syncher.EntityDataAccessor
- net.minecraft.network.syncher.EntityDataSerializer
+ net.minecraft.network.syncher.EntityDataSerializers
- net.minecraft.network.syncher.EntityDataSerializers$1
+ net.minecraft.network.syncher.EntityDataSerializers$10
- net.minecraft.network.syncher.EntityDataSerializers$11
+ net.minecraft.network.syncher.EntityDataSerializers$12
- net.minecraft.network.syncher.EntityDataSerializers$13
+ net.minecraft.network.syncher.EntityDataSerializers$14
- net.minecraft.network.syncher.EntityDataSerializers$15
+ net.minecraft.network.syncher.EntityDataSerializers$16
- net.minecraft.network.syncher.EntityDataSerializers$17
+ net.minecraft.network.syncher.EntityDataSerializers$18
- net.minecraft.network.syncher.EntityDataSerializers$19
+ net.minecraft.network.syncher.EntityDataSerializers$2
- net.minecraft.network.syncher.EntityDataSerializers$3
+ net.minecraft.network.syncher.EntityDataSerializers$4
- net.minecraft.network.syncher.EntityDataSerializers$5
+ net.minecraft.network.syncher.EntityDataSerializers$6
- net.minecraft.network.syncher.EntityDataSerializers$7
+ net.minecraft.network.syncher.EntityDataSerializers$8
- net.minecraft.network.syncher.EntityDataSerializers$9
+ net.minecraft.network.syncher.package-info
+ net.minecraft.network.syncher.SynchedEntityData
- net.minecraft.network.syncher.SynchedEntityData$DataItem
- net.minecraft.network.Varint21FrameDecoder
+ net.minecraft.network.Varint21LengthFieldPrepender
- net.minecraft.obfuscate.DontObfuscateOrShrink
+ net.minecraft.obfuscate.KeepAfterObfuscation
- net.minecraft.obfuscate.package-info
+ net.minecraft.package-info
- net.minecraft.realms.DisconnectedRealmsScreen
+ net.minecraft.realms.NarrationHelper
+ net.minecraft.realms.package-info
- net.minecraft.realms.RealmsBridge
+ net.minecraft.realms.RealmsConnect
- net.minecraft.realms.RealmsConnect$1
+ net.minecraft.realms.RealmsLabel
- net.minecraft.realms.RealmsObjectSelectionList
+ net.minecraft.realms.RealmsScreen
- net.minecraft.realms.RealmsServerAddress
+ net.minecraft.realms.RepeatedNarrator
- net.minecraft.realms.RepeatedNarrator$Params
+ net.minecraft.recipebook.package-info
- net.minecraft.recipebook.PlaceRecipe
+ net.minecraft.recipebook.ServerPlaceRecipe
- net.minecraft.recipebook.ServerPlaceSmeltingRecipe
- net.minecraft.resources.ResourceKey
+ net.minecraft.server.level.DistanceManager
- net.minecraft.server.level.DistanceManager$ChunkTicketTracker
+ net.minecraft.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
- net.minecraft.server.level.DistanceManager$PlayerTicketTracker
+ net.minecraft.server.level.FeatureSimulator
- net.minecraft.server.level.PlayerMap
+ net.minecraft.util.datafix.DataFixers
- net.minecraft.util.datafix.DataFixers$1
+ net.minecraft.util.datafix.DataFixers$2
- net.minecraft.util.datafix.DataFixTypes
- net.minecraft.util.datafix.fixes.OminousBannerRenameFix
- net.minecraft.util.datafix.fixes.WorldGenSettingsFix$StructureFeatureConfiguration
+ net.minecraft.util.datafix.OminousBannerRenameFix
- net.minecraft.util.datafix.PackedBitStorage
- net.minecraft.util.datafix.schemas.NamespacedSchema$1
+ net.minecraft.util.datafix.schemas.V100
- net.minecraft.util.datafix.schemas.V102
+ net.minecraft.util.datafix.schemas.V1022
- net.minecraft.util.datafix.schemas.V106
+ net.minecraft.util.datafix.schemas.V107
- net.minecraft.util.datafix.schemas.V1125
+ net.minecraft.util.datafix.schemas.V135
- net.minecraft.util.datafix.schemas.V143
+ net.minecraft.util.datafix.schemas.V1451
- net.minecraft.util.datafix.schemas.V1451_1
+ net.minecraft.util.datafix.schemas.V1451_2
- net.minecraft.util.datafix.schemas.V1451_3
+ net.minecraft.util.datafix.schemas.V1451_4
- net.minecraft.util.datafix.schemas.V1451_5
+ net.minecraft.util.datafix.schemas.V1451_6
- net.minecraft.util.datafix.schemas.V1451_7
+ net.minecraft.util.datafix.schemas.V1460
- net.minecraft.util.datafix.schemas.V1466
+ net.minecraft.util.datafix.schemas.V1470
- net.minecraft.util.datafix.schemas.V1481
+ net.minecraft.util.datafix.schemas.V1483
- net.minecraft.util.datafix.schemas.V1486
+ net.minecraft.util.datafix.schemas.V1510
- net.minecraft.util.datafix.schemas.V1800
+ net.minecraft.util.datafix.schemas.V1801
- net.minecraft.util.datafix.schemas.V1904
+ net.minecraft.util.datafix.schemas.V1906
- net.minecraft.util.datafix.schemas.V1909
+ net.minecraft.util.datafix.schemas.V1920
- net.minecraft.util.datafix.schemas.V1928
+ net.minecraft.util.datafix.schemas.V1929
- net.minecraft.util.datafix.schemas.V1931
+ net.minecraft.util.datafix.schemas.V2100
- net.minecraft.util.datafix.schemas.V2501
+ net.minecraft.util.datafix.schemas.V2502
- net.minecraft.util.datafix.schemas.V2505
+ net.minecraft.util.datafix.schemas.V2509
- net.minecraft.util.datafix.schemas.V2519
+ net.minecraft.util.datafix.schemas.V2522
- net.minecraft.util.datafix.schemas.V2551
+ net.minecraft.util.DirectoryLock
- net.minecraft.util.DirectoryLock$LockException
+ net.minecraft.util.ExceptionCollector
- net.minecraft.util.FastColor
+ net.minecraft.util.FastColor$ARGB32
- net.minecraft.util.FrameTimer
+ net.minecraft.util.GsonHelper
- net.minecraft.util.HttpUtil
+ net.minecraft.util.InsensitiveStringMap
- net.minecraft.util.IntRange
+ net.minecraft.util.LazyLoadedValue
- net.minecraft.util.LimitedCapacityList
+ net.minecraft.util.LinearCongruentialGenerator
- net.minecraft.util.LowerCaseEnumTypeAdapterFactory
+ net.minecraft.util.LowerCaseEnumTypeAdapterFactory$1
- net.minecraft.util.Mth
+ net.minecraft.util.ProgressListener
- net.minecraft.util.RewindableStream
+ net.minecraft.util.RewindableStream$1
+ net.minecraft.util.Serializer
- net.minecraft.util.SmoothDouble
+ net.minecraft.util.SortedArraySet
- net.minecraft.util.SortedArraySet$1
+ net.minecraft.util.SortedArraySet$ArrayIterator
- net.minecraft.util.StringRepresentable
- net.minecraft.util.StringRepresentable$2
+ net.minecraft.util.StringUtil
- net.minecraft.util.TimeUtil
+ net.minecraft.util.Tuple
- net.minecraft.util.Unit
+ net.minecraft.util.VisibleForDebug
- net.minecraft.util.WeighedRandom
+ net.minecraft.util.WeighedRandom$WeighedRandomItem
+ net.minecraft.world.entity.ai.attributes.Attribute
- net.minecraft.world.entity.ai.attributes.AttributeInstance
+ net.minecraft.world.entity.ai.attributes.AttributeMap
- net.minecraft.world.entity.ai.attributes.AttributeModifier
+ net.minecraft.world.entity.ai.attributes.AttributeModifier$Operation
- net.minecraft.world.entity.ai.attributes.Attributes
- net.minecraft.world.entity.ai.attributes.AttributeSupplier
+ net.minecraft.world.entity.ai.attributes.AttributeSupplier$Builder
+ net.minecraft.world.entity.ai.attributes.DefaultAttributes
+ net.minecraft.world.entity.ai.attributes.package-info
- net.minecraft.world.entity.ai.attributes.RangedAttribute
- net.minecraft.world.entity.ai.behavior.AcquirePoi
+ net.minecraft.world.entity.ai.behavior.AnimalMakeLove
- net.minecraft.world.entity.ai.behavior.AssignProfessionFromJobSite
+ net.minecraft.world.entity.ai.behavior.BackUpIfTooClose
- net.minecraft.world.entity.ai.behavior.BecomePassiveIfMemoryPresent
+ net.minecraft.world.entity.ai.behavior.Behavior
- net.minecraft.world.entity.ai.behavior.Behavior$Status
+ net.minecraft.world.entity.ai.behavior.BehaviorUtils
- net.minecraft.world.entity.ai.behavior.BlockPosTracker
+ net.minecraft.world.entity.ai.behavior.CelebrateVillagersSurvivedRaid
- net.minecraft.world.entity.ai.behavior.CopyMemoryWithExpiry
+ net.minecraft.world.entity.ai.behavior.CrossbowAttack
- net.minecraft.world.entity.ai.behavior.CrossbowAttack$CrossbowState
+ net.minecraft.world.entity.ai.behavior.DismountOrSkipMounting
- net.minecraft.world.entity.ai.behavior.DoNothing
+ net.minecraft.world.entity.ai.behavior.EntityTracker
- net.minecraft.world.entity.ai.behavior.EraseMemoryIf
+ net.minecraft.world.entity.ai.behavior.GateBehavior
- net.minecraft.world.entity.ai.behavior.GateBehavior$1
+ net.minecraft.world.entity.ai.behavior.GateBehavior$OrderPolicy
- net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy
+ net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$1
- net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$2
+ net.minecraft.world.entity.ai.behavior.GiveGiftToHero
- net.minecraft.world.entity.ai.behavior.GoOutsideToCelebrate
+ net.minecraft.world.entity.ai.behavior.GoToCelebrateLocation
- net.minecraft.world.entity.ai.behavior.GoToClosestVillage
+ net.minecraft.world.entity.ai.behavior.GoToWantedItem
- net.minecraft.world.entity.ai.behavior.HarvestFarmland
+ net.minecraft.world.entity.ai.behavior.InsideBrownianWalk
- net.minecraft.world.entity.ai.behavior.InteractWith
+ net.minecraft.world.entity.ai.behavior.InteractWithDoor
- net.minecraft.world.entity.ai.behavior.JumpOnBed
+ net.minecraft.world.entity.ai.behavior.LocateHidingPlace
- net.minecraft.world.entity.ai.behavior.LocateHidingPlaceDuringRaid
+ net.minecraft.world.entity.ai.behavior.LookAndFollowTradingPlayerSink
- net.minecraft.world.entity.ai.behavior.LookAtTargetSink
+ net.minecraft.world.entity.ai.behavior.MeleeAttack
- net.minecraft.world.entity.ai.behavior.Mount
+ net.minecraft.world.entity.ai.behavior.MoveToSkySeeingSpot
- net.minecraft.world.entity.ai.behavior.MoveToTargetSink
+ net.minecraft.world.entity.ai.behavior.PlayTagWithOtherKids
- net.minecraft.world.entity.ai.behavior.PositionTracker
+ net.minecraft.world.entity.ai.behavior.RandomStroll
- net.minecraft.world.entity.ai.behavior.ReactToBell
+ net.minecraft.world.entity.ai.behavior.ResetProfession
- net.minecraft.world.entity.ai.behavior.ResetRaidStatus
+ net.minecraft.world.entity.ai.behavior.RingBell
- net.minecraft.world.entity.ai.behavior.RunIf
+ net.minecraft.world.entity.ai.behavior.RunOne
- net.minecraft.world.entity.ai.behavior.RunSometimes
+ net.minecraft.world.entity.ai.behavior.SetClosestHomeAsWalkTarget
- net.minecraft.world.entity.ai.behavior.SetEntityLookTarget
+ net.minecraft.world.entity.ai.behavior.SetHiddenState
- net.minecraft.world.entity.ai.behavior.SetLookAndInteract
+ net.minecraft.world.entity.ai.behavior.SetRaidStatus
- net.minecraft.world.entity.ai.behavior.SetWalkTargetAwayFrom
+ net.minecraft.world.entity.ai.behavior.SetWalkTargetFromAttackTargetIfTargetOutOfReach
- net.minecraft.world.entity.ai.behavior.SetWalkTargetFromBlockMemory
+ net.minecraft.world.entity.ai.behavior.SetWalkTargetFromLookTarget
- net.minecraft.world.entity.ai.behavior.ShowTradesToPlayer
+ net.minecraft.world.entity.ai.behavior.SleepInBed
- net.minecraft.world.entity.ai.behavior.SocializeAtBell
+ net.minecraft.world.entity.ai.behavior.StartAttacking
- net.minecraft.world.entity.ai.behavior.StartCelebratingIfTargetDead
+ net.minecraft.world.entity.ai.behavior.StopAttackingIfTargetInvalid
- net.minecraft.world.entity.ai.behavior.StopBeingAngryIfTargetDead
+ net.minecraft.world.entity.ai.behavior.StrollAroundPoi
- net.minecraft.world.entity.ai.behavior.StrollToPoi
+ net.minecraft.world.entity.ai.behavior.StrollToPoiList
- net.minecraft.world.entity.ai.behavior.Swim
+ net.minecraft.world.entity.ai.behavior.TradeWithVillager
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
- net.minecraft.world.entity.ai.behavior.WeightedList
+ net.minecraft.world.entity.ai.behavior.WeightedList$1
- net.minecraft.world.entity.ai.behavior.WeightedList$WeightedEntry
- net.minecraft.world.entity.ai.Brain$1
- net.minecraft.world.entity.ai.Brain$Provider
+ net.minecraft.world.level.biome.AmbientAdditionsSettings
- net.minecraft.world.level.biome.AmbientMoodSettings
+ net.minecraft.world.level.biome.AmbientParticleSettings
- net.minecraft.world.level.biome.BadlandsBiome
+ net.minecraft.world.level.biome.BadlandsPlateauBiome
- net.minecraft.world.level.biome.BambooJungleBiome
+ net.minecraft.world.level.biome.BambooJungleHillsBiome
- net.minecraft.world.level.biome.BasaltDeltasBiome
+ net.minecraft.world.level.biome.BeachBiome
- net.minecraft.world.level.biome.Biome
+ net.minecraft.world.level.biome.Biome$1
- net.minecraft.world.level.biome.Biome$BiomeBuilder
+ net.minecraft.world.level.biome.Biome$BiomeCategory
- net.minecraft.world.level.biome.Biome$BiomeTempCategory
+ net.minecraft.world.level.biome.Biome$ClimateParameters
- net.minecraft.world.level.biome.Biome$MobSpawnCost
+ net.minecraft.world.level.biome.Biome$Precipitation
- net.minecraft.world.level.biome.Biome$SpawnerData
+ net.minecraft.world.level.biome.BiomeDefaultFeatures
- net.minecraft.world.level.biome.BiomeManager
+ net.minecraft.world.level.biome.BiomeManager$NoiseBiomeSource
- net.minecraft.world.level.biome.BiomeSource
+ net.minecraft.world.level.biome.BiomeSourceType
- net.minecraft.world.level.biome.MultiNoiseBiomeSource$Preset
+ net.minecraft.world.level.biome.MushroomFieldsBiome
- net.minecraft.world.level.biome.MushroomFieldsShoreBiome
+ net.minecraft.world.level.biome.NearestNeighborBiomeZoomer
- net.minecraft.world.level.biome.NetherWastesBiome
+ net.minecraft.world.level.biome.OceanBiome
- net.minecraft.world.level.biome.OverworldBiomeSource
- net.minecraft.world.level.biome.package-info
+ net.minecraft.world.level.biome.PlainsBiome
- net.minecraft.world.level.biome.RiverBiome
+ net.minecraft.world.level.biome.SavannaBiome
- net.minecraft.world.level.biome.SavannaPlateauBiome
+ net.minecraft.world.level.biome.ShatteredSavannaBiome
- net.minecraft.world.level.biome.ShatteredSavannaPlateauBiome
+ net.minecraft.world.level.biome.SmallEndIslandsBiome
- net.minecraft.world.level.biome.SnowyBeachBiome
+ net.minecraft.world.level.biome.SnowyMountainsBiome
- net.minecraft.world.level.biome.SnowyTaigaBiome
+ net.minecraft.world.level.biome.SnowyTaigaHillsBiome
- net.minecraft.world.level.biome.SnowyTaigaMountainsBiome
+ net.minecraft.world.level.biome.SnowyTundraBiome
- net.minecraft.world.level.biome.SoulSandValleyBiome
+ net.minecraft.world.level.biome.StoneShoreBiome
- net.minecraft.world.level.biome.SunflowerPlainsBiome
+ net.minecraft.world.level.biome.SwampBiome
- net.minecraft.world.level.biome.SwampHillsBiome
+ net.minecraft.world.level.biome.TaigaBiome
- net.minecraft.world.level.biome.TaigaHillsBiome
+ net.minecraft.world.level.biome.TaigaMountainsBiome
- net.minecraft.world.level.biome.TallBirchForestBiome
+ net.minecraft.world.level.biome.TallBirchHillsBiome
- net.minecraft.world.level.biome.TheEndBiome
+ net.minecraft.world.level.biome.TheEndBiomeSource
- net.minecraft.world.level.biome.TheVoidBiome
+ net.minecraft.world.level.biome.WarmOceanBiome
- net.minecraft.world.level.biome.WarpedForestBiome
+ net.minecraft.world.level.biome.WoodedBadlandsBiome
- net.minecraft.world.level.biome.WoodedHillsBiome
+ net.minecraft.world.level.biome.WoodedMountainBiome
+ net.minecraft.world.level.block.AbstractBannerBlock
- net.minecraft.world.level.block.AbstractChestBlock
+ net.minecraft.world.level.block.AbstractFurnaceBlock
- net.minecraft.world.level.block.AbstractGlassBlock
+ net.minecraft.world.level.block.AbstractSkullBlock
- net.minecraft.world.level.block.AirBlock
+ net.minecraft.world.level.block.AnvilBlock
- net.minecraft.world.level.block.AttachedStemBlock
+ net.minecraft.world.level.block.BambooBlock
- net.minecraft.world.level.block.BambooSaplingBlock
+ net.minecraft.world.level.block.BannerBlock
- net.minecraft.world.level.block.BarrelBlock
+ net.minecraft.world.level.block.BarrierBlock
- net.minecraft.world.level.block.BaseCoralFanBlock
+ net.minecraft.world.level.block.BaseCoralPlantBlock
- net.minecraft.world.level.block.BaseCoralPlantTypeBlock
+ net.minecraft.world.level.block.BaseCoralWallFanBlock
- net.minecraft.world.level.block.BaseEntityBlock
+ net.minecraft.world.level.block.BaseFireBlock
- net.minecraft.world.level.block.BasePressurePlateBlock
+ net.minecraft.world.level.block.BaseRailBlock
- net.minecraft.world.level.block.BaseRailBlock$1
+ net.minecraft.world.level.block.BeaconBeamBlock
- net.minecraft.world.level.block.BeaconBlock
+ net.minecraft.world.level.block.BedBlock
- net.minecraft.world.level.block.BedBlock$1
+ net.minecraft.world.level.block.BeehiveBlock
- net.minecraft.world.level.block.BeetrootBlock
+ net.minecraft.world.level.block.BellBlock
- net.minecraft.world.level.block.BellBlock$1
+ net.minecraft.world.level.block.BlastFurnaceBlock
- net.minecraft.world.level.block.Block
+ net.minecraft.world.level.block.Block$1
- net.minecraft.world.level.block.Block$2
+ net.minecraft.world.level.block.Block$BlockStatePairKey
- net.minecraft.world.level.block.Blocks
+ net.minecraft.world.level.block.BonemealableBlock
- net.minecraft.world.level.block.BrewingStandBlock
+ net.minecraft.world.level.block.BubbleColumnBlock
- net.minecraft.world.level.block.BucketPickup
+ net.minecraft.world.level.block.BushBlock
- net.minecraft.world.level.block.ButtonBlock
+ net.minecraft.world.level.block.ButtonBlock$1
- net.minecraft.world.level.block.CactusBlock
+ net.minecraft.world.level.block.CakeBlock
- net.minecraft.world.level.block.CampfireBlock
+ net.minecraft.world.level.block.CarrotBlock
- net.minecraft.world.level.block.CartographyTableBlock
+ net.minecraft.world.level.block.CarvedPumpkinBlock
- net.minecraft.world.level.block.CauldronBlock
+ net.minecraft.world.level.block.ChainBlock
- net.minecraft.world.level.block.ChestBlock
+ net.minecraft.world.level.block.ChestBlock$1
- net.minecraft.world.level.block.ChestBlock$2
+ net.minecraft.world.level.block.ChestBlock$2$1
- net.minecraft.world.level.block.ChestBlock$3
+ net.minecraft.world.level.block.ChestBlock$4
- net.minecraft.world.level.block.ChorusFlowerBlock
+ net.minecraft.world.level.block.ChorusPlantBlock
- net.minecraft.world.level.block.CocoaBlock
+ net.minecraft.world.level.block.CocoaBlock$1
- net.minecraft.world.level.block.CommandBlock
+ net.minecraft.world.level.block.ComparatorBlock
- net.minecraft.world.level.block.ComposterBlock
+ net.minecraft.world.level.block.ComposterBlock$EmptyContainer
- net.minecraft.world.level.block.ComposterBlock$InputContainer
+ net.minecraft.world.level.block.ComposterBlock$OutputContainer
- net.minecraft.world.level.block.ConcretePowderBlock
+ net.minecraft.world.level.block.ConduitBlock
- net.minecraft.world.level.block.CoralBlock
+ net.minecraft.world.level.block.CoralFanBlock
- net.minecraft.world.level.block.CoralPlantBlock
+ net.minecraft.world.level.block.CoralWallFanBlock
- net.minecraft.world.level.block.CraftingTableBlock
+ net.minecraft.world.level.block.CropBlock
- net.minecraft.world.level.block.CrossCollisionBlock
+ net.minecraft.world.level.block.CrossCollisionBlock$1
- net.minecraft.world.level.block.CryingObsidianBlock
+ net.minecraft.world.level.block.DaylightDetectorBlock
- net.minecraft.world.level.block.DeadBushBlock
+ net.minecraft.world.level.block.DetectorRailBlock
- net.minecraft.world.level.block.DetectorRailBlock$1
+ net.minecraft.world.level.block.DiodeBlock
- net.minecraft.world.level.block.DirectionalBlock
+ net.minecraft.world.level.block.DispenserBlock
- net.minecraft.world.level.block.DoorBlock
+ net.minecraft.world.level.block.DoorBlock$1
- net.minecraft.world.level.block.DoubleBlockCombiner
+ net.minecraft.world.level.block.DoubleBlockCombiner$BlockType
- net.minecraft.world.level.block.DoubleBlockCombiner$Combiner
+ net.minecraft.world.level.block.DoubleBlockCombiner$NeighborCombineResult
- net.minecraft.world.level.block.DoubleBlockCombiner$NeighborCombineResult$Double
+ net.minecraft.world.level.block.DoubleBlockCombiner$NeighborCombineResult$Single
- net.minecraft.world.level.block.DoublePlantBlock
+ net.minecraft.world.level.block.DragonEggBlock
- net.minecraft.world.level.block.DropperBlock
+ net.minecraft.world.level.block.EnchantmentTableBlock
+ net.minecraft.world.level.block.EnderChestBlock
- net.minecraft.world.level.block.EndGatewayBlock
+ net.minecraft.world.level.block.EndPortalBlock
- net.minecraft.world.level.block.EndPortalFrameBlock
+ net.minecraft.world.level.block.EndRodBlock
- net.minecraft.world.level.block.EndRodBlock$1
- net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity
+ net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity$1
- net.minecraft.world.level.block.entity.BannerBlockEntity
+ net.minecraft.world.level.block.entity.BannerPattern
- net.minecraft.world.level.block.entity.BannerPattern$Builder
+ net.minecraft.world.level.block.entity.BarrelBlockEntity
- net.minecraft.world.level.block.entity.BaseContainerBlockEntity
+ net.minecraft.world.level.block.entity.BeaconBlockEntity
- net.minecraft.world.level.block.entity.BeaconBlockEntity$1
+ net.minecraft.world.level.block.entity.BeaconBlockEntity$BeaconBeamSection
- net.minecraft.world.level.block.entity.BedBlockEntity
+ net.minecraft.world.level.block.entity.BeehiveBlockEntity
- net.minecraft.world.level.block.entity.BeehiveBlockEntity$1
+ net.minecraft.world.level.block.entity.BeehiveBlockEntity$BeeData
- net.minecraft.world.level.block.entity.BeehiveBlockEntity$BeeReleaseStatus
+ net.minecraft.world.level.block.entity.BellBlockEntity
- net.minecraft.world.level.block.entity.BlastFurnaceBlockEntity
+ net.minecraft.world.level.block.entity.BlockEntity
- net.minecraft.world.level.block.entity.BlockEntityType
+ net.minecraft.world.level.block.entity.BlockEntityType$Builder
- net.minecraft.world.level.block.entity.BrewingStandBlockEntity
+ net.minecraft.world.level.block.entity.BrewingStandBlockEntity$1
- net.minecraft.world.level.block.entity.CampfireBlockEntity
+ net.minecraft.world.level.block.entity.ChestBlockEntity
- net.minecraft.world.level.block.entity.CommandBlockEntity
+ net.minecraft.world.level.block.entity.CommandBlockEntity$1
- net.minecraft.world.level.block.entity.CommandBlockEntity$Mode
+ net.minecraft.world.level.block.entity.ComparatorBlockEntity
- net.minecraft.world.level.block.entity.ConduitBlockEntity
+ net.minecraft.world.level.block.entity.DaylightDetectorBlockEntity
- net.minecraft.world.level.block.entity.DispenserBlockEntity
+ net.minecraft.world.level.block.entity.DropperBlockEntity
- net.minecraft.world.level.block.entity.EnchantmentTableBlockEntity
+ net.minecraft.world.level.block.entity.EnderChestBlockEntity
- net.minecraft.world.level.block.entity.FurnaceBlockEntity
+ net.minecraft.world.level.block.entity.Hopper
- net.minecraft.world.level.block.entity.HopperBlockEntity
+ net.minecraft.world.level.block.entity.JigsawBlockEntity
- net.minecraft.world.level.block.entity.JigsawBlockEntity$JointType
+ net.minecraft.world.level.block.entity.JigsawBlockEntity$RuntimePiece
- net.minecraft.world.level.block.entity.JukeboxBlockEntity
+ net.minecraft.world.level.block.entity.LecternBlockEntity
- net.minecraft.world.level.block.entity.LecternBlockEntity$1
+ net.minecraft.world.level.block.entity.LecternBlockEntity$2
- net.minecraft.world.level.block.entity.LidBlockEntity
+ net.minecraft.world.level.block.entity.package-info
+ net.minecraft.world.level.block.entity.RandomizableContainerBlockEntity
- net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity
+ net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity$1
- net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity$AnimationStatus
+ net.minecraft.world.level.block.entity.SignBlockEntity
- net.minecraft.world.level.block.entity.SkullBlockEntity
+ net.minecraft.world.level.block.entity.SmokerBlockEntity
- net.minecraft.world.level.block.entity.SpawnerBlockEntity
+ net.minecraft.world.level.block.entity.SpawnerBlockEntity$1
- net.minecraft.world.level.block.entity.StructureBlockEntity
+ net.minecraft.world.level.block.entity.StructureBlockEntity$1
- net.minecraft.world.level.block.entity.StructureBlockEntity$UpdateType
+ net.minecraft.world.level.block.entity.TheEndGatewayBlockEntity
- net.minecraft.world.level.block.entity.TheEndPortalBlockEntity
+ net.minecraft.world.level.block.entity.TickableBlockEntity
- net.minecraft.world.level.block.entity.TrappedChestBlockEntity
- net.minecraft.world.level.block.EntityBlock
+ net.minecraft.world.level.block.FaceAttachedHorizontalDirectionalBlock
- net.minecraft.world.level.block.FaceAttachedHorizontalDirectionalBlock$1
+ net.minecraft.world.level.block.FallingBlock
- net.minecraft.world.level.block.FarmBlock
+ net.minecraft.world.level.block.FenceBlock
- net.minecraft.world.level.block.FenceGateBlock
+ net.minecraft.world.level.block.FenceGateBlock$1
- net.minecraft.world.level.block.FireBlock
+ net.minecraft.world.level.block.FletchingTableBlock
- net.minecraft.world.level.block.FlowerBlock
+ net.minecraft.world.level.block.FlowerPotBlock
- net.minecraft.world.level.block.FrostedIceBlock
+ net.minecraft.world.level.block.FungusBlock
- net.minecraft.world.level.block.FurnaceBlock
+ net.minecraft.world.level.block.GlassBlock
- net.minecraft.world.level.block.GlazedTerracottaBlock
+ net.minecraft.world.level.block.GrassBlock
- net.minecraft.world.level.block.GrassPathBlock
+ net.minecraft.world.level.block.GravelBlock
- net.minecraft.world.level.block.GrindstoneBlock
+ net.minecraft.world.level.block.GrindstoneBlock$1
- net.minecraft.world.level.block.grower.AbstractMegaTreeGrower
+ net.minecraft.world.level.block.grower.AbstractTreeGrower
- net.minecraft.world.level.block.grower.AcaciaTreeGrower
+ net.minecraft.world.level.block.grower.BirchTreeGrower
- net.minecraft.world.level.block.grower.DarkOakTreeGrower
+ net.minecraft.world.level.block.grower.JungleTreeGrower
- net.minecraft.world.level.block.grower.OakTreeGrower
- net.minecraft.world.level.block.grower.package-info
+ net.minecraft.world.level.block.grower.SpruceTreeGrower
- net.minecraft.world.level.block.GrowingPlantBlock
+ net.minecraft.world.level.block.GrowingPlantBodyBlock
- net.minecraft.world.level.block.GrowingPlantHeadBlock
+ net.minecraft.world.level.block.HalfTransparentBlock
- net.minecraft.world.level.block.HayBlock
+ net.minecraft.world.level.block.HoneyBlock
- net.minecraft.world.level.block.HopperBlock
+ net.minecraft.world.level.block.HopperBlock$1
- net.minecraft.world.level.block.HorizontalDirectionalBlock
+ net.minecraft.world.level.block.HugeMushroomBlock
- net.minecraft.world.level.block.IceBlock
+ net.minecraft.world.level.block.InfestedBlock
- net.minecraft.world.level.block.IronBarsBlock
+ net.minecraft.world.level.block.JigsawBlock
- net.minecraft.world.level.block.JukeboxBlock
+ net.minecraft.world.level.block.KelpBlock
- net.minecraft.world.level.block.KelpPlantBlock
+ net.minecraft.world.level.block.LadderBlock
- net.minecraft.world.level.block.LadderBlock$1
+ net.minecraft.world.level.block.Lantern
- net.minecraft.world.level.block.LeavesBlock
+ net.minecraft.world.level.block.LecternBlock
- net.minecraft.world.level.block.LecternBlock$1
+ net.minecraft.world.level.block.LevelEvent
- net.minecraft.world.level.block.LeverBlock
+ net.minecraft.world.level.block.LeverBlock$1
- net.minecraft.world.level.block.LiquidBlock
+ net.minecraft.world.level.block.LiquidBlockContainer
- net.minecraft.world.level.block.LoomBlock
+ net.minecraft.world.level.block.MagmaBlock
- net.minecraft.world.level.block.MelonBlock
+ net.minecraft.world.level.block.Mirror
- net.minecraft.world.level.block.Mirror$1
+ net.minecraft.world.level.block.MushroomBlock
- net.minecraft.world.level.block.MyceliumBlock
+ net.minecraft.world.level.block.NetherPortalBlock
- net.minecraft.world.level.block.NetherPortalBlock$1
+ net.minecraft.world.level.block.NetherPortalBlock$PortalShape
+ net.minecraft.world.level.block.NetherrackBlock
- net.minecraft.world.level.block.NetherSproutsBlock
+ net.minecraft.world.level.block.NetherVines
- net.minecraft.world.level.block.NetherWartBlock
- net.minecraft.world.level.block.NoteBlock
+ net.minecraft.world.level.block.NyliumBlock
- net.minecraft.world.level.block.ObserverBlock
+ net.minecraft.world.level.block.OreBlock
+ net.minecraft.world.level.block.package-info
- net.minecraft.world.level.block.PipeBlock
- net.minecraft.world.level.block.piston.MovingPistonBlock
- net.minecraft.world.level.block.piston.package-info
+ net.minecraft.world.level.block.piston.PistonBaseBlock
- net.minecraft.world.level.block.piston.PistonBaseBlock$1
+ net.minecraft.world.level.block.piston.PistonHeadBlock
- net.minecraft.world.level.block.piston.PistonHeadBlock$1
+ net.minecraft.world.level.block.piston.PistonMath
- net.minecraft.world.level.block.piston.PistonMath$1
+ net.minecraft.world.level.block.piston.PistonMovingBlockEntity
- net.minecraft.world.level.block.piston.PistonMovingBlockEntity$1
+ net.minecraft.world.level.block.piston.PistonStructureResolver
+ net.minecraft.world.level.block.PlayerHeadBlock
- net.minecraft.world.level.block.PlayerWallHeadBlock
+ net.minecraft.world.level.block.PotatoBlock
- net.minecraft.world.level.block.PoweredBlock
+ net.minecraft.world.level.block.PoweredRailBlock
- net.minecraft.world.level.block.PoweredRailBlock$1
+ net.minecraft.world.level.block.PressurePlateBlock
- net.minecraft.world.level.block.PressurePlateBlock$1
+ net.minecraft.world.level.block.PressurePlateBlock$Sensitivity
- net.minecraft.world.level.block.PumpkinBlock
+ net.minecraft.world.level.block.RailBlock
- net.minecraft.world.level.block.RailBlock$1
+ net.minecraft.world.level.block.RailState
- net.minecraft.world.level.block.RailState$1
- net.minecraft.world.level.block.RedstoneLampBlock
+ net.minecraft.world.level.block.RedStoneOreBlock
+ net.minecraft.world.level.block.RedstoneTorchBlock
- net.minecraft.world.level.block.RedstoneTorchBlock$Toggle
+ net.minecraft.world.level.block.RedstoneWallTorchBlock
- net.minecraft.world.level.block.RedStoneWireBlock
+ net.minecraft.world.level.block.RedStoneWireBlock$1
- net.minecraft.world.level.block.RenderShape
+ net.minecraft.world.level.block.RepeaterBlock
- net.minecraft.world.level.block.RespawnAnchorBlock
+ net.minecraft.world.level.block.RootsBlock
- net.minecraft.world.level.block.RotatedPillarBlock
+ net.minecraft.world.level.block.RotatedPillarBlock$1
- net.minecraft.world.level.block.Rotation
+ net.minecraft.world.level.block.Rotation$1
- net.minecraft.world.level.block.SandBlock
+ net.minecraft.world.level.block.SaplingBlock
- net.minecraft.world.level.block.ScaffoldingBlock
- net.minecraft.world.level.block.Seagrass
+ net.minecraft.world.level.block.SeaPickleBlock
+ net.minecraft.world.level.block.ShearableDoublePlantBlock
- net.minecraft.world.level.block.ShulkerBoxBlock
+ net.minecraft.world.level.block.ShulkerBoxBlock$1
- net.minecraft.world.level.block.SignBlock
+ net.minecraft.world.level.block.SimpleWaterloggedBlock
- net.minecraft.world.level.block.SkullBlock
+ net.minecraft.world.level.block.SkullBlock$Type
- net.minecraft.world.level.block.SkullBlock$Types
+ net.minecraft.world.level.block.SlabBlock
- net.minecraft.world.level.block.SlabBlock$1
+ net.minecraft.world.level.block.SlimeBlock
- net.minecraft.world.level.block.SmithingTableBlock
+ net.minecraft.world.level.block.SmokerBlock
- net.minecraft.world.level.block.SnowLayerBlock
+ net.minecraft.world.level.block.SnowLayerBlock$1
- net.minecraft.world.level.block.SnowyDirtBlock
+ net.minecraft.world.level.block.SoulFireBlock
- net.minecraft.world.level.block.SoulSandBlock
+ net.minecraft.world.level.block.SoundType
- net.minecraft.world.level.block.SpawnerBlock
+ net.minecraft.world.level.block.SpongeBlock
- net.minecraft.world.level.block.SpreadingSnowyDirtBlock
+ net.minecraft.world.level.block.StainedGlassBlock
- net.minecraft.world.level.block.StainedGlassPaneBlock
+ net.minecraft.world.level.block.StairBlock
- net.minecraft.world.level.block.StairBlock$1
+ net.minecraft.world.level.block.StandingSignBlock
+ net.minecraft.world.level.block.state.AbstractStateHolder
+ net.minecraft.world.level.block.state.BlockBehaviour
- net.minecraft.world.level.block.state.BlockBehaviour$1
+ net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase
- net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase$Cache
+ net.minecraft.world.level.block.state.BlockBehaviour$OffsetType
- net.minecraft.world.level.block.state.BlockBehaviour$Properties
+ net.minecraft.world.level.block.state.BlockBehaviour$StateArgumentPredicate
- net.minecraft.world.level.block.state.BlockBehaviour$StatePredicate
+ net.minecraft.world.level.block.state.BlockState
- net.minecraft.world.level.block.state.package-info
+ net.minecraft.world.level.block.state.pattern.BlockInWorld
- net.minecraft.world.level.block.state.pattern.BlockPattern
+ net.minecraft.world.level.block.state.pattern.BlockPattern$BlockCacheLoader
- net.minecraft.world.level.block.state.pattern.BlockPattern$BlockPatternMatch
+ net.minecraft.world.level.block.state.pattern.BlockPattern$PortalInfo
- net.minecraft.world.level.block.state.pattern.BlockPatternBuilder
+ net.minecraft.world.level.block.state.pattern.package-info
- net.minecraft.world.level.block.state.predicate.BlockMaterialPredicate
+ net.minecraft.world.level.block.state.predicate.BlockMaterialPredicate$1
- net.minecraft.world.level.block.state.predicate.BlockPredicate
+ net.minecraft.world.level.block.state.predicate.BlockStatePredicate
- net.minecraft.world.level.block.state.predicate.package-info
+ net.minecraft.world.level.block.state.properties.AbstractProperty
- net.minecraft.world.level.block.state.StateDefinition
+ net.minecraft.world.level.block.state.StateDefinition$Builder
- net.minecraft.world.level.block.state.StateDefinition$Factory
- net.minecraft.world.level.block.StemBlock
+ net.minecraft.world.level.block.StemGrownBlock
- net.minecraft.world.level.block.StoneButtonBlock
+ net.minecraft.world.level.block.StonecutterBlock
- net.minecraft.world.level.block.StructureBlock
+ net.minecraft.world.level.block.StructureBlock$1
- net.minecraft.world.level.block.StructureVoidBlock
+ net.minecraft.world.level.block.SugarCaneBlock
- net.minecraft.world.level.block.SweetBerryBushBlock
+ net.minecraft.world.level.block.TallFlowerBlock
- net.minecraft.world.level.block.TallGrassBlock
+ net.minecraft.world.level.block.TallSeagrass
- net.minecraft.world.level.block.TargetBlock
+ net.minecraft.world.level.block.TntBlock
- net.minecraft.world.level.block.TorchBlock
+ net.minecraft.world.level.block.TrapDoorBlock
- net.minecraft.world.level.block.TrapDoorBlock$1
+ net.minecraft.world.level.block.TrappedChestBlock
- net.minecraft.world.level.block.TripWireBlock
+ net.minecraft.world.level.block.TripWireBlock$1
- net.minecraft.world.level.block.TripWireHookBlock
+ net.minecraft.world.level.block.TripWireHookBlock$1
- net.minecraft.world.level.block.TurtleEggBlock
+ net.minecraft.world.level.block.TwistingVines
- net.minecraft.world.level.block.TwistingVinesPlant
+ net.minecraft.world.level.block.VineBlock
- net.minecraft.world.level.block.VineBlock$1
+ net.minecraft.world.level.block.WallBannerBlock
- net.minecraft.world.level.block.WallBlock
+ net.minecraft.world.level.block.WallBlock$1
- net.minecraft.world.level.block.WallSignBlock
+ net.minecraft.world.level.block.WallSkullBlock
- net.minecraft.world.level.block.WallTorchBlock
+ net.minecraft.world.level.block.WaterlilyBlock
- net.minecraft.world.level.block.WebBlock
+ net.minecraft.world.level.block.WeepingVines
- net.minecraft.world.level.block.WeepingVinesPlant
+ net.minecraft.world.level.block.WeightedPressurePlateBlock
- net.minecraft.world.level.block.WetSpongeBlock
+ net.minecraft.world.level.block.WitherRoseBlock
- net.minecraft.world.level.block.WitherSkullBlock
+ net.minecraft.world.level.block.WitherWallSkullBlock
- net.minecraft.world.level.block.WoodButtonBlock
+ net.minecraft.world.level.block.WoolCarpetBlock
+ net.minecraft.world.level.dimension.DimensionType
+ net.minecraft.world.level.dimension.end.package-info
+ net.minecraft.world.level.dimension.NetherDimension$1
- net.minecraft.world.level.dimension.package-info
- net.minecraft.world.level.LevelAccessor
+ net.minecraft.world.level.levelgen.ChunkGeneratorSettings
- net.minecraft.world.level.levelgen.feature.configurations.StructureFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.CoralClawFeature
+ net.minecraft.world.level.levelgen.feature.CoralFeature
- net.minecraft.world.level.levelgen.feature.CoralMushroomFeature
+ net.minecraft.world.level.levelgen.feature.CoralTreeFeature
- net.minecraft.world.level.levelgen.feature.DecoratedFeature
+ net.minecraft.world.level.levelgen.feature.DecoratedFlowerFeature
- net.minecraft.world.level.levelgen.feature.DefaultFlowerFeature
+ net.minecraft.world.level.levelgen.feature.DeltaFeature
- net.minecraft.world.level.levelgen.feature.DesertPyramidFeature
+ net.minecraft.world.level.levelgen.feature.DesertPyramidFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.DesertVillagePools
+ net.minecraft.world.level.levelgen.feature.DesertWellFeature
- net.minecraft.world.level.levelgen.feature.DiskReplaceFeature
+ net.minecraft.world.level.levelgen.feature.EndCityFeature
- net.minecraft.world.level.levelgen.feature.EndCityFeature$EndCityStart
+ net.minecraft.world.level.levelgen.feature.EndGatewayFeature
- net.minecraft.world.level.levelgen.feature.EndIslandFeature
+ net.minecraft.world.level.levelgen.feature.EndPodiumFeature
- net.minecraft.world.level.levelgen.feature.Feature
+ net.minecraft.world.level.levelgen.feature.FillLayerFeature
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer$FoliageAttachment
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacerType
- net.minecraft.world.level.levelgen.feature.foliageplacers.MegaJungleFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.MegaPineFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.package-info
- net.minecraft.world.level.levelgen.feature.foliageplacers.PineFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.SpruceFoliagePlacer
- net.minecraft.world.level.levelgen.feature.FossilFeature
+ net.minecraft.world.level.levelgen.feature.GlowstoneFeature
- net.minecraft.world.level.levelgen.feature.HugeBrownMushroomFeature
+ net.minecraft.world.level.levelgen.feature.HugeFungusConfiguration
- net.minecraft.world.level.levelgen.feature.HugeFungusFeature
+ net.minecraft.world.level.levelgen.feature.HugeRedMushroomFeature
- net.minecraft.world.level.levelgen.feature.IcebergFeature
- net.minecraft.world.level.levelgen.feature.IcePatchFeature
+ net.minecraft.world.level.levelgen.feature.IceSpikeFeature
+ net.minecraft.world.level.levelgen.feature.IglooFeature
- net.minecraft.world.level.levelgen.feature.IglooFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.JunglePyramidFeature
- net.minecraft.world.level.levelgen.feature.JunglePyramidFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.KelpFeature
- net.minecraft.world.level.levelgen.feature.LakeFeature
+ net.minecraft.world.level.levelgen.feature.MineshaftFeature
- net.minecraft.world.level.levelgen.feature.MineshaftFeature$MineShaftStart
+ net.minecraft.world.level.levelgen.feature.MineshaftFeature$Type
- net.minecraft.world.level.levelgen.feature.MonsterRoomFeature
+ net.minecraft.world.level.levelgen.feature.NetherForestVegetationFeature
- net.minecraft.world.level.levelgen.feature.NetherFortressFeature
+ net.minecraft.world.level.levelgen.feature.NetherFortressFeature$NetherBridgeStart
- net.minecraft.world.level.levelgen.feature.NoOpFeature
+ net.minecraft.world.level.levelgen.feature.NoSurfaceOreFeature
- net.minecraft.world.level.levelgen.feature.OceanMonumentFeature
+ net.minecraft.world.level.levelgen.feature.OceanMonumentFeature$OceanMonumentStart
- net.minecraft.world.level.levelgen.feature.OreFeature
+ net.minecraft.world.level.levelgen.feature.package-info
+ net.minecraft.world.level.levelgen.feature.PillagerOutpostFeature
- net.minecraft.world.level.levelgen.feature.PillagerOutpostFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.PlainVillagePools
- net.minecraft.world.level.levelgen.feature.RandomBooleanSelectorFeature
+ net.minecraft.world.level.levelgen.feature.RandomPatchFeature
- net.minecraft.world.level.levelgen.feature.RandomRandomFeature
+ net.minecraft.world.level.levelgen.feature.RandomScatteredFeature
- net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProviderType
- net.minecraft.world.level.levelgen.feature.stateproviders.ForestFlowerProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.package-info
+ net.minecraft.world.level.levelgen.feature.stateproviders.PlainFlowerProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.RotatedBlockProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.SimpleStateProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.WeightedStateProvider
- net.minecraft.world.level.levelgen.feature.structures.EmptyPoolElement
+ net.minecraft.world.level.levelgen.feature.structures.FeaturePoolElement
- net.minecraft.world.level.levelgen.feature.structures.JigsawJunction
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement
- net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$1
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$PieceFactory
- net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$PieceState
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$Placer
- net.minecraft.world.level.levelgen.feature.structures.LegacySinglePoolElement
+ net.minecraft.world.level.levelgen.feature.structures.ListPoolElement
- net.minecraft.world.level.levelgen.feature.structures.package-info
- net.minecraft.world.level.levelgen.feature.structures.SinglePoolElement
+ net.minecraft.world.level.levelgen.feature.structures.StructurePoolElement
- net.minecraft.world.level.levelgen.feature.structures.StructurePoolElementType
+ net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool
- net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool$Projection
+ net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePools
+ net.minecraft.world.level.levelgen.feature.treedecorators.AlterGroundDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.BeehiveDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.CocoaDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.LeaveVineDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.package-info
+ net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecoratorType
+ net.minecraft.world.level.levelgen.feature.treedecorators.TrunkVineDecorator
+ net.minecraft.world.level.levelgen.feature.trunkplacers.DarkOakTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.FancyTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.FancyTrunkPlacer$FoliageCoords
- net.minecraft.world.level.levelgen.feature.trunkplacers.ForkingTrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.GiantTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.MegaJungleTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.package-info
+ net.minecraft.world.level.levelgen.feature.trunkplacers.StraightTrunkPlacer
- net.minecraft.world.level.levelgen.feature.trunkplacers.TrunkPlacer
+ net.minecraft.world.level.levelgen.feature.trunkplacers.TrunkPlacerType
+ net.minecraft.world.level.levelgen.flat.FlatLayerInfo
- net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorSettings
+ net.minecraft.world.level.levelgen.GenerationStep
- net.minecraft.world.level.levelgen.GenerationStep$Carving
+ net.minecraft.world.level.levelgen.GenerationStep$Decoration
- net.minecraft.world.level.levelgen.Heightmap
+ net.minecraft.world.level.levelgen.Heightmap$Types
- net.minecraft.world.level.levelgen.Heightmap$Usage
+ net.minecraft.world.level.levelgen.NetherGeneratorSettings
+ net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator
- net.minecraft.world.level.levelgen.NoiseGeneratorSettings
- net.minecraft.world.level.levelgen.NoiseGeneratorSettings$Preset
- net.minecraft.world.level.levelgen.NoiseSettings
+ net.minecraft.world.level.levelgen.OverworldGeneratorSettings
+ net.minecraft.world.level.levelgen.structure.package-info
- net.minecraft.world.level.levelgen.structure.StructureFeatureIndexSavedData
+ net.minecraft.world.level.levelgen.structure.StructureFeatureIO
+ net.minecraft.world.level.levelgen.structure.StructurePiece
- net.minecraft.world.level.levelgen.structure.StructurePiece$1
+ net.minecraft.world.level.levelgen.structure.StructurePiece$BlockSelector
- net.minecraft.world.level.levelgen.structure.StructureStart
+ net.minecraft.world.level.levelgen.structure.StructureStart$1
- net.minecraft.world.level.levelgen.structure.SwamplandHutPiece
+ net.minecraft.world.level.levelgen.structure.TemplateStructurePiece
- net.minecraft.world.level.levelgen.structure.templatesystem.AlwaysTrueTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.AxisAlignedLinearPosTest
- net.minecraft.world.level.levelgen.structure.templatesystem.BlackstoneReplaceProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockAgeProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockIgnoreProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockMatchTest
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockRotProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockStateMatchTest
- net.minecraft.world.level.levelgen.structure.templatesystem.GravityProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.JigsawReplacementProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.LinearPosTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.NopProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.package-info
- net.minecraft.world.level.levelgen.structure.templatesystem.PosAlwaysTrueTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.PosRuleTest
- net.minecraft.world.level.levelgen.structure.templatesystem.PosRuleTestType
+ net.minecraft.world.level.levelgen.structure.templatesystem.ProcessorRule
- net.minecraft.world.level.levelgen.structure.templatesystem.RandomBlockMatchTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.RandomBlockStateMatchTest
- net.minecraft.world.level.levelgen.structure.templatesystem.RuleProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.RuleTest
- net.minecraft.world.level.levelgen.structure.templatesystem.RuleTestType
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureManager
- net.minecraft.world.level.levelgen.structure.templatesystem.StructurePlaceSettings
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureProcessorType
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$1
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$Palette
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$SimplePalette
+ net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$StructureBlockInfo
- net.minecraft.world.level.levelgen.structure.templatesystem.StructureTemplate$StructureEntityInfo
+ net.minecraft.world.level.levelgen.structure.templatesystem.TagMatchTest
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$1
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$FirstFloorRoomCollection
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$FloorRoomCollection
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$MansionGrid
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$MansionPiecePlacer
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$PlacementData
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$SecondFloorRoomCollection
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$SimpleGrid
+ net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$ThirdFloorRoomCollection
- net.minecraft.world.level.levelgen.structure.WoodlandMansionPieces$WoodlandMansionPiece
- net.minecraft.world.level.levelgen.StructureSettings
+ net.minecraft.world.level.levelgen.surfacebuilders.BadlandsSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.BasaltDeltasSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.ConfiguredSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.DefaultSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.ErodedBadlandsSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.FrozenOceanSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.GiantTreeTaigaSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.GravellyMountainSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.MountainSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.NetherCappedSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.NetherForestSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.NetherSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.NopeSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.package-info
- net.minecraft.world.level.levelgen.surfacebuilders.ShatteredSavanaSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.SoulSandValleySurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.SurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.SurfaceBuilderBaseConfiguration
- net.minecraft.world.level.levelgen.surfacebuilders.SurfaceBuilderConfiguration
+ net.minecraft.world.level.levelgen.surfacebuilders.SwampSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.WoodedBadlandsSurfaceBuilder
- net.minecraft.world.level.levelgen.synth.ImprovedNoise
+ net.minecraft.world.level.levelgen.synth.NormalNoise
- net.minecraft.world.level.levelgen.synth.package-info
- net.minecraft.world.level.levelgen.synth.PerlinNoise
+ net.minecraft.world.level.levelgen.synth.PerlinSimplexNoise
- net.minecraft.world.level.levelgen.synth.SimplexNoise
+ net.minecraft.world.level.levelgen.synth.SurfaceNoise
+ net.minecraft.world.level.levelgen.TheEndLevelSource
+ net.minecraft.world.level.levelgen.WorldGenSettings$1
+ net.minecraft.world.level.levelgen.WorldGenSettings$LevelType
+ net.minecraft.world.level.LevelReader
- net.minecraft.world.level.LevelSettings
- net.minecraft.world.level.LevelSimulatedReader
+ net.minecraft.world.level.LevelSimulatedRW
+ net.minecraft.world.level.LevelWriter
+ net.minecraft.world.level.lighting.BlockLightEngine
- net.minecraft.world.level.lighting.BlockLightSectionStorage
+ net.minecraft.world.level.lighting.BlockLightSectionStorage$BlockDataLayerStorageMap
- net.minecraft.world.level.lighting.DataLayerStorageMap
+ net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint
- net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint$1
+ net.minecraft.world.level.lighting.DynamicGraphMinFixedPoint$2
- net.minecraft.world.level.lighting.FlatDataLayer
+ net.minecraft.world.level.lighting.LayerLightEngine
- net.minecraft.world.level.lighting.LayerLightEventListener
+ net.minecraft.world.level.lighting.LayerLightEventListener$DummyLightLayerEventListener
- net.minecraft.world.level.lighting.LayerLightSectionStorage
+ net.minecraft.world.level.lighting.LayerLightSectionStorage$1
- net.minecraft.world.level.lighting.LevelLightEngine
+ net.minecraft.world.level.lighting.LightEventListener
- net.minecraft.world.level.lighting.package-info
- net.minecraft.world.level.lighting.SkyLightEngine
+ net.minecraft.world.level.lighting.SkyLightSectionStorage
- net.minecraft.world.level.lighting.SkyLightSectionStorage$1
+ net.minecraft.world.level.lighting.SkyLightSectionStorage$SkyDataLayerStorageMap
- net.minecraft.world.level.lighting.SpatialLongSet
+ net.minecraft.world.level.lighting.SpatialLongSet$InternalMap
- net.minecraft.world.level.LightLayer
+ net.minecraft.world.level.material.EmptyFluid
- net.minecraft.world.level.material.FlowingFluid
+ net.minecraft.world.level.material.FlowingFluid$1
- net.minecraft.world.level.material.Fluid
+ net.minecraft.world.level.material.FluidState
+ net.minecraft.world.level.NaturalSpawner
- net.minecraft.world.level.NaturalSpawner$1
+ net.minecraft.world.level.NaturalSpawner$AfterSpawnCallback
- net.minecraft.world.level.NaturalSpawner$ChunkGetter
+ net.minecraft.world.level.NaturalSpawner$SpawnPredicate
- net.minecraft.world.level.NaturalSpawner$SpawnState
+ net.minecraft.world.level.NoiseColumn
- net.minecraft.world.level.PathNavigationRegion
+ net.minecraft.world.level.PortalForcer
- net.minecraft.world.level.PotentialCalculator
+ net.minecraft.world.level.PotentialCalculator$PointCharge
- net.minecraft.world.level.ServerTickList
+ net.minecraft.world.level.SpawnData
- net.minecraft.world.level.storage.loot.BinomialDistributionGenerator
+ net.minecraft.world.level.storage.loot.BinomialDistributionGenerator$Serializer
- net.minecraft.world.level.storage.loot.BuiltInLootTables
+ net.minecraft.world.level.storage.loot.ConstantIntValue
- net.minecraft.world.level.storage.loot.ConstantIntValue$Serializer
+ net.minecraft.world.level.storage.loot.Deserializers
+ net.minecraft.world.level.storage.loot.entries.AlternativesEntry
- net.minecraft.world.level.storage.loot.entries.AlternativesEntry$Builder
+ net.minecraft.world.level.storage.loot.entries.ComposableEntryContainer
- net.minecraft.world.level.storage.loot.entries.CompositeEntryBase
+ net.minecraft.world.level.storage.loot.entries.CompositeEntryBase$1
- net.minecraft.world.level.storage.loot.entries.CompositeEntryBase$CompositeEntryConstructor
+ net.minecraft.world.level.storage.loot.entries.CompositeEntryBase$Serializer
- net.minecraft.world.level.storage.loot.entries.DynamicLoot
+ net.minecraft.world.level.storage.loot.entries.DynamicLoot$1
- net.minecraft.world.level.storage.loot.entries.DynamicLoot$Serializer
+ net.minecraft.world.level.storage.loot.entries.EmptyLootItem
- net.minecraft.world.level.storage.loot.entries.EmptyLootItem$1
+ net.minecraft.world.level.storage.loot.entries.EmptyLootItem$Serializer
- net.minecraft.world.level.storage.loot.entries.EntryGroup
+ net.minecraft.world.level.storage.loot.entries.EntryGroup$Builder
- net.minecraft.world.level.storage.loot.entries.LootItem
+ net.minecraft.world.level.storage.loot.entries.LootItem$1
- net.minecraft.world.level.storage.loot.entries.LootItem$Serializer
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntries
- net.minecraft.world.level.storage.loot.entries.LootPoolEntries$Serializer
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntry
- net.minecraft.world.level.storage.loot.entries.LootPoolEntryContainer
+ net.minecraft.world.level.storage.loot.entries.LootPoolEntryContainer$Builder
- net.minecraft.world.level.storage.loot.entries.LootPoolEntryContainer$Serializer
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$1
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$Builder
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$DummyBuilder
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$EntryBase
- net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$EntryConstructor
+ net.minecraft.world.level.storage.loot.entries.LootPoolSingletonContainer$Serializer
- net.minecraft.world.level.storage.loot.entries.LootTableReference
+ net.minecraft.world.level.storage.loot.entries.LootTableReference$1
- net.minecraft.world.level.storage.loot.entries.LootTableReference$Serializer
- net.minecraft.world.level.storage.loot.entries.package-info
+ net.minecraft.world.level.storage.loot.entries.SequentialEntry
- net.minecraft.world.level.storage.loot.entries.SequentialEntry$Builder
+ net.minecraft.world.level.storage.loot.entries.TagEntry
- net.minecraft.world.level.storage.loot.entries.TagEntry$1
+ net.minecraft.world.level.storage.loot.entries.TagEntry$Serializer
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$1
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$BinomialWithBonusCount
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$Formula
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$FormulaDeserializer
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$OreDrops
+ net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$Serializer
- net.minecraft.world.level.storage.loot.functions.ApplyBonusCount$UniformBonusCount
+ net.minecraft.world.level.storage.loot.functions.ApplyExplosionDecay
- net.minecraft.world.level.storage.loot.functions.ApplyExplosionDecay$1
+ net.minecraft.world.level.storage.loot.functions.ApplyExplosionDecay$Serializer
- net.minecraft.world.level.storage.loot.functions.CopyBlockState
+ net.minecraft.world.level.storage.loot.functions.CopyBlockState$1
- net.minecraft.world.level.storage.loot.functions.CopyBlockState$Builder
+ net.minecraft.world.level.storage.loot.functions.CopyBlockState$Serializer
- net.minecraft.world.level.storage.loot.functions.CopyNameFunction
+ net.minecraft.world.level.storage.loot.functions.CopyNameFunction$1
- net.minecraft.world.level.storage.loot.functions.CopyNameFunction$NameSource
+ net.minecraft.world.level.storage.loot.functions.CopyNameFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$1
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$CopyOperation
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$DataSource
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$1
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$2
- net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$MergeStrategy$3
+ net.minecraft.world.level.storage.loot.functions.CopyNbtFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction
+ net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction$1
- net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.EnchantRandomlyFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction
+ net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction$1
- net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.EnchantWithLevelsFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction
+ net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction$1
- net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction$Builder
+ net.minecraft.world.level.storage.loot.functions.ExplorationMapFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.FillPlayerHead
+ net.minecraft.world.level.storage.loot.functions.FillPlayerHead$Serializer
- net.minecraft.world.level.storage.loot.functions.FunctionUserBuilder
+ net.minecraft.world.level.storage.loot.functions.LimitCount
- net.minecraft.world.level.storage.loot.functions.LimitCount$1
+ net.minecraft.world.level.storage.loot.functions.LimitCount$Serializer
+ net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction
- net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction$1
+ net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction$Builder
- net.minecraft.world.level.storage.loot.functions.LootingEnchantFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction
+ net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$Builder
- net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$DummyBuilder
+ net.minecraft.world.level.storage.loot.functions.LootItemConditionalFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.LootItemFunction
+ net.minecraft.world.level.storage.loot.functions.LootItemFunction$Builder
- net.minecraft.world.level.storage.loot.functions.LootItemFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.LootItemFunctions
- net.minecraft.world.level.storage.loot.functions.LootItemFunctions$Serializer
- net.minecraft.world.level.storage.loot.functions.package-info
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$1
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Modifier
+ net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$ModifierBuilder
- net.minecraft.world.level.storage.loot.functions.SetAttributesFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetContainerContents
- net.minecraft.world.level.storage.loot.functions.SetContainerContents$1
+ net.minecraft.world.level.storage.loot.functions.SetContainerContents$Builder
- net.minecraft.world.level.storage.loot.functions.SetContainerContents$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetContainerLootTable
- net.minecraft.world.level.storage.loot.functions.SetContainerLootTable$1
+ net.minecraft.world.level.storage.loot.functions.SetContainerLootTable$Serializer
- net.minecraft.world.level.storage.loot.functions.SetItemCountFunction
+ net.minecraft.world.level.storage.loot.functions.SetItemCountFunction$1
- net.minecraft.world.level.storage.loot.functions.SetItemCountFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetItemDamageFunction
- net.minecraft.world.level.storage.loot.functions.SetItemDamageFunction$1
+ net.minecraft.world.level.storage.loot.functions.SetItemDamageFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SetLoreFunction
+ net.minecraft.world.level.storage.loot.functions.SetLoreFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetLoreFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetNameFunction
- net.minecraft.world.level.storage.loot.functions.SetNameFunction$1
+ net.minecraft.world.level.storage.loot.functions.SetNameFunction$Serializer
- net.minecraft.world.level.storage.loot.functions.SetNbtFunction
+ net.minecraft.world.level.storage.loot.functions.SetNbtFunction$1
- net.minecraft.world.level.storage.loot.functions.SetNbtFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction
- net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction$1
+ net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction$Builder
- net.minecraft.world.level.storage.loot.functions.SetStewEffectFunction$Serializer
+ net.minecraft.world.level.storage.loot.functions.SmeltItemFunction
- net.minecraft.world.level.storage.loot.functions.SmeltItemFunction$1
+ net.minecraft.world.level.storage.loot.functions.SmeltItemFunction$Serializer
- net.minecraft.world.level.storage.loot.IntLimiter
+ net.minecraft.world.level.storage.loot.IntLimiter$1
- net.minecraft.world.level.storage.loot.IntLimiter$Serializer
+ net.minecraft.world.level.storage.loot.LootContext
- net.minecraft.world.level.storage.loot.LootContext$1
+ net.minecraft.world.level.storage.loot.LootContext$Builder
- net.minecraft.world.level.storage.loot.LootContext$DynamicDrop
+ net.minecraft.world.level.storage.loot.LootContext$EntityTarget
- net.minecraft.world.level.storage.loot.LootContext$EntityTarget$Serializer
+ net.minecraft.world.level.storage.loot.LootContextUser
- net.minecraft.world.level.storage.loot.LootPool
+ net.minecraft.world.level.storage.loot.LootPool$1
- net.minecraft.world.level.storage.loot.LootPool$Builder
+ net.minecraft.world.level.storage.loot.LootPool$Serializer
- net.minecraft.world.level.storage.loot.LootTable
+ net.minecraft.world.level.storage.loot.LootTable$1
- net.minecraft.world.level.storage.loot.LootTable$Builder
+ net.minecraft.world.level.storage.loot.LootTable$Serializer
- net.minecraft.world.level.storage.loot.LootTables
+ net.minecraft.world.level.storage.loot.package-info
- net.minecraft.world.level.storage.loot.parameters.LootContextParam
+ net.minecraft.world.level.storage.loot.parameters.LootContextParams
+ net.minecraft.world.level.storage.loot.parameters.LootContextParamSet
- net.minecraft.world.level.storage.loot.parameters.LootContextParamSet$1
+ net.minecraft.world.level.storage.loot.parameters.LootContextParamSet$Builder
- net.minecraft.world.level.storage.loot.parameters.LootContextParamSets
- net.minecraft.world.level.storage.loot.parameters.package-info
+ net.minecraft.world.level.storage.loot.PredicateManager
+ net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition
- net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition$1
+ net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.AlternativeLootItemCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.BonusLevelTableCondition
- net.minecraft.world.level.storage.loot.predicates.BonusLevelTableCondition$1
+ net.minecraft.world.level.storage.loot.predicates.BonusLevelTableCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.ConditionReference
+ net.minecraft.world.level.storage.loot.predicates.ConditionReference$Serializer
- net.minecraft.world.level.storage.loot.predicates.ConditionUserBuilder
+ net.minecraft.world.level.storage.loot.predicates.DamageSourceCondition
- net.minecraft.world.level.storage.loot.predicates.DamageSourceCondition$1
+ net.minecraft.world.level.storage.loot.predicates.DamageSourceCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition
+ net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition$1
- net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.EntityHasScoreCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.ExplosionCondition
+ net.minecraft.world.level.storage.loot.predicates.ExplosionCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.InvertedLootItemCondition
+ net.minecraft.world.level.storage.loot.predicates.InvertedLootItemCondition$1
- net.minecraft.world.level.storage.loot.predicates.InvertedLootItemCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.LocationCheck
- net.minecraft.world.level.storage.loot.predicates.LocationCheck$Serializer
+ net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition$1
+ net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition$Builder
- net.minecraft.world.level.storage.loot.predicates.LootItemBlockStatePropertyCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.LootItemCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemCondition$Builder
+ net.minecraft.world.level.storage.loot.predicates.LootItemCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.LootItemConditions
+ net.minecraft.world.level.storage.loot.predicates.LootItemConditions$Serializer
- net.minecraft.world.level.storage.loot.predicates.LootItemEntityPropertyCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemEntityPropertyCondition$1
- net.minecraft.world.level.storage.loot.predicates.LootItemEntityPropertyCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.LootItemKilledByPlayerCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemKilledByPlayerCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceCondition
- net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceCondition$1
+ net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceCondition$Serializer
- net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceWithLootingCondition
+ net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceWithLootingCondition$1
- net.minecraft.world.level.storage.loot.predicates.LootItemRandomChanceWithLootingCondition$Serializer
+ net.minecraft.world.level.storage.loot.predicates.MatchTool
- net.minecraft.world.level.storage.loot.predicates.MatchTool$Serializer
+ net.minecraft.world.level.storage.loot.predicates.package-info
+ net.minecraft.world.level.storage.loot.predicates.TimeCheck
- net.minecraft.world.level.storage.loot.predicates.TimeCheck$1
+ net.minecraft.world.level.storage.loot.predicates.TimeCheck$Builder
- net.minecraft.world.level.storage.loot.predicates.TimeCheck$Serializer
+ net.minecraft.world.level.storage.loot.predicates.WeatherCheck
- net.minecraft.world.level.storage.loot.predicates.WeatherCheck$1
+ net.minecraft.world.level.storage.loot.predicates.WeatherCheck$Builder
- net.minecraft.world.level.storage.loot.predicates.WeatherCheck$Serializer
- net.minecraft.world.level.storage.loot.RandomIntGenerator
+ net.minecraft.world.level.storage.loot.RandomIntGenerators
- net.minecraft.world.level.storage.loot.RandomValueBounds
+ net.minecraft.world.level.storage.loot.RandomValueBounds$Serializer
- net.minecraft.world.level.storage.loot.ValidationContext
- net.minecraft.world.level.storage.McRegionUpgrader
- net.minecraft.world.level.storage.package-info
+ net.minecraft.world.level.storage.PlayerDataStorage
- net.minecraft.world.level.storage.PrimaryLevelData
+ net.minecraft.world.level.storage.ServerLevelData
+ net.minecraft.world.level.storage.threaded.package-info
- net.minecraft.world.level.storage.WorldData
+ net.minecraft.world.level.storage.WritableLevelData
- net.minecraft.world.level.StructureFeatureManager
+ net.minecraft.world.level.TickList
- net.minecraft.world.level.TickNextTickData
+ net.minecraft.world.level.TickPriority
- net.minecraft.world.level.timers.FunctionCallback
+ net.minecraft.world.level.timers.FunctionCallback$Serializer
- net.minecraft.world.level.timers.FunctionTagCallback
+ net.minecraft.world.level.timers.FunctionTagCallback$Serializer
- net.minecraft.world.level.timers.package-info
- net.minecraft.world.level.timers.TimerCallback
+ net.minecraft.world.level.timers.TimerCallback$Serializer
- net.minecraft.world.level.timers.TimerCallbacks
+ net.minecraft.world.level.timers.TimerQueue
- net.minecraft.world.level.timers.TimerQueue$1
+ net.minecraft.world.level.timers.TimerQueue$Event
- net.minecraft.world.level.WorldGenLevel
+ net.minecraft.world.package-info
- net.minecraft.world.phys.AABB
+ net.minecraft.world.phys.BlockHitResult
- net.minecraft.world.phys.EntityHitResult
+ net.minecraft.world.phys.HitResult
- net.minecraft.world.phys.HitResult$Type
- net.minecraft.world.phys.package-info
+ net.minecraft.world.phys.PosAndRot
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
- net.minecraft.world.phys.shapes.IntPointRange
+ net.minecraft.world.phys.shapes.NonOverlappingMerger
- net.minecraft.world.phys.shapes.OffsetDoubleList
+ net.minecraft.world.phys.shapes.package-info
+ net.minecraft.world.phys.shapes.Shapes
- net.minecraft.world.phys.shapes.Shapes$DoubleLineConsumer
+ net.minecraft.world.phys.shapes.SliceShape
- net.minecraft.world.phys.shapes.SubShape
+ net.minecraft.world.phys.shapes.VoxelShape
- net.minecraft.world.phys.shapes.WorldRegionIndirectVoxelShape
- net.minecraft.world.phys.Vec2
+ net.minecraft.world.phys.Vec3
- net.minecraft.world.scores.criteria.ObjectiveCriteria
+ net.minecraft.world.scores.criteria.ObjectiveCriteria$RenderType
- net.minecraft.world.scores.criteria.package-info
- net.minecraft.world.scores.Objective
+ net.minecraft.world.scores.package-info
+ net.minecraft.world.scores.PlayerTeam
- net.minecraft.world.scores.Score
+ net.minecraft.world.scores.Scoreboard
- net.minecraft.world.scores.ScoreboardSaveData
+ net.minecraft.world.scores.Team
- net.minecraft.world.scores.Team$CollisionRule
+ net.minecraft.world.scores.Team$Visibility
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
XXX.advancements.critereon.ChangeDimensionTrigger$TriggerInstance +5M -5M | +2P -2P
```
```
XXX.advancements.critereon.LocationPredicate +5M -3M | +2P -1P
```
```
XXX.minecraft.client.Minecraft +4M | +2P
```
```
XXX.client.gui.GuiComponent +1M -1M
```
```
XXX.gui.chat.ChatListener +1P -1P
```
```
XXX.gui.chat.OverlayChatListener +1M -1M
```
```
XXX.gui.components.Button +5M | +2P
```
```
XXX.client.multiplayer.ClientLevel +3M
```
```
XXX.minecraft.commands.CommandSource$1 +1M -1M
```
```
XXX.minecraft.commands.SharedSuggestionProvider +1P
```
```
XXX.minecraft.core.BlockPos +3M -5M | +1P
```
```
XXX.minecraft.core.Direction$Axis +1P
```
```
XXX.minecraft.core.GlobalPos +5M -8M | +2P -1P
```
```
XXX.minecraft.core.SerializableUUID +6M -4M | +1P
```
```
XXX.minecraft.core.Vec3i +3M | +1P
```
```
XXX.core.particles.BlockParticleOption +3M
```
```
XXX.core.particles.DustParticleOptions +5M | +1P
```
```
XXX.core.particles.ItemParticleOption +3M
```
```
XXX.core.particles.ParticleType +1P
```
```
XXX.minecraft.server.Main +1M
```
```
XXX.minecraft.server.MinecraftServer +5M -4M | +1P
```
```
XXX.server.commands.LocateCommand +3M -20M
```
```
XXX.server.commands.SpreadPlayersCommand +4M -3M
```
```
XXX.server.dedicated.DedicatedPlayerList +1M -1M
```
```
XXX.server.level.ServerLevel +10M -4M | +4P -1P
```
```
XXX.server.rcon.RconConsoleSource +1M -1M
```
```
XXX.minecraft.sounds.Music +6M | +1P
```
```
XXX.minecraft.sounds.SoundEvent +2M | +1P
```
```
XXX.datafix.fixes.AddNewChoices +1M -1M
```
```
XXX.datafix.fixes.AdvancementsRenameFix +3M -3M
```
```
XXX.datafix.fixes.BedBlockEntityInjecter +2M -2M
```
```
XXX.datafix.fixes.BitStorageAlignFix +7M -7M
```
```
XXX.datafix.fixes.BlockEntityIdFix +1M -1M
```
```
XXX.datafix.fixes.BlockEntityKeepPacked +1M -1M
```
```
XXX.datafix.fixes.BlockEntitySignTextStrictJsonFix +2M -2M
```
```
XXX.datafix.fixes.BlockEntityUUIDFix +4M -4M
```
```
XXX.datafix.fixes.BlockRenameFix +2M -2M
```
```
XXX.datafix.fixes.BlockRenameFixWithJigsaw +2M -2M
```
```
XXX.datafix.fixes.BlockStateData +3M -3M | +2P -2P
```
```
XXX.datafix.fixes.CatTypeFix +1M -1M
```
```
XXX.datafix.fixes.ChunkLightRemoveFix +1M -1M
```
```
XXX.datafix.fixes.ChunkPalettedStorageFix$UpgradeChunk +8M -8M | +1P -1P
```
```
XXX.datafix.fixes.ChunkToProtochunkFix +8M -5M
```
```
XXX.datafix.fixes.EntityBlockStateFix +4M -4M
```
```
XXX.datafix.fixes.EntityElderGuardianSplitFix +1M -1M
```
```
XXX.datafix.fixes.EntityHealthFix +1M -1M
```
```
XXX.datafix.fixes.EntityItemFrameDirectionFix +1M -1M
```
```
XXX.datafix.fixes.EntityPaintingItemFrameDirectionFix +3M -3M
```
```
XXX.datafix.fixes.EntityProjectileOwnerFix +5M -5M
```
```
XXX.datafix.fixes.EntityRenameFix +3M -3M
```
```
XXX.datafix.fixes.EntityShulkerColorFix +1M -1M
```
```
XXX.datafix.fixes.EntitySkeletonSplitFix +1M -1M
```
```
XXX.datafix.fixes.EntityUUIDFix +28M -28M
```
```
XXX.datafix.fixes.EntityZombieSplitFix +1M -1M
```
```
XXX.datafix.fixes.FurnaceRecipeFix +2M -2M
```
```
XXX.datafix.fixes.HeightmapRenamingFix +1M -1M
```
```
XXX.datafix.fixes.ItemSpawnEggFix +3M -2M
```
```
XXX.datafix.fixes.JigsawPropertiesFix +1M -1M
```
```
XXX.datafix.fixes.LeavesFix +1M -1M
```
```
XXX.datafix.fixes.LeavesFix$Section +3M -3M | +1P -1P
```
```
XXX.datafix.fixes.LevelFlatGeneratorInfoFix +2M -2M
```
```
XXX.datafix.fixes.MapIdFix +1M -1M
```
```
XXX.datafix.fixes.MobSpawnerEntityIdentifiersFix +2M -2M
```
```
XXX.datafix.fixes.NewVillageFix +5M -5M
```
```
XXX.datafix.fixes.ObjectiveRenderTypeFix +2M -2M
```
```
XXX.datafix.fixes.OptionsForceVBOFix +1M -1M
```
```
XXX.datafix.fixes.OptionsKeyTranslationFix +3M -3M
```
```
XXX.datafix.fixes.PlayerUUIDFix +2M -2M
```
```
XXX.datafix.fixes.References +1P -1P
```
```
XXX.datafix.fixes.ReorganizePoi +2M -2M
```
```
XXX.datafix.fixes.SavedDataVillageCropFix +6M -6M
```
```
XXX.datafix.fixes.SimplestEntityRenameFix +2M -2M
```
```
XXX.datafix.fixes.StriderGravityFix +1M -1M
```
```
XXX.datafix.fixes.VillagerRebuildLevelAndXpFix +3M -3M
```
```
XXX.datafix.fixes.WallPropertyFix +4M -4M
```
```
XXX.datafix.fixes.ZombieVillagerRebuildXpFix +1M -1M
```
```
XXX.datafix.schemas.V99$1 +1M -1M
```
```
XXX.util.worldupdate.WorldUpgrader +6M -4M | +1P
```
```
XXX.world.entity.EntityType -1M
```
```
XXX.world.entity.LivingEntity +10M -8M
```
```
XXX.world.entity.MobCategory +1M | +1P
```
```
XXX.ai.gossip.GossipContainer$GossipEntry +3M -5M | +1P -1P
```
```
XXX.ai.memory.MemoryModuleType +2M -2M | +1P -1P
```
```
XXX.village.poi.PoiRecord +5M -2M
```
```
XXX.animal.horse.AbstractHorse +1M
```
```
XXX.animal.horse.Horse +1M
```
```
XXX.animal.horse.Llama +1M
```
```
XXX.animal.horse.Mule +2M
```
```
XXX.entity.item.ItemEntity +1M -1M
```
```
XXX.entity.monster.Zoglin +2M -1M
```
```
XXX.entity.monster.ZombieVillager +1M
```
```
XXX.monster.hoglin.Hoglin +2M -1M
```
```
XXX.entity.npc.AbstractVillager +1M -1M
```
```
XXX.entity.npc.VillagerData +4M -2M | +1P
```
```
XXX.entity.npc.VillagerTrades$TreasureMapForEmeralds +1M -1M | +1P -1P
```
```
XXX.entity.vehicle.AbstractMinecartContainer +1M -1M
```
```
XXX.world.item.MapItem +1M -1M
```
```
XXX.world.level.BaseCommandBlock +1M -1M
```
```
XXX.world.level.Level +1M -4M | +2P -1P
```
```
XXX.level.biome.CheckerboardColumnBiomeSource +6M -1M | +3P -1P
```
```
XXX.level.biome.CrimsonForestBiome -3M
```
```
XXX.block.state.StateHolder +15M -2M | +5P -8P
```
```
XXX.level.chunk.ChunkAccess -1M
```
```
XXX.level.chunk.ChunkGenerator +9M -10M | +6P -1P
```
```
XXX.level.chunk.ImposterProtoChunk +1M
```
```
XXX.level.levelgen.FlatLevelSource +3M -7M | +1P -3P
```
```
XXX.levelgen.carver.CarverConfiguration -1P
```
```
XXX.levelgen.carver.ConfiguredWorldCarver +2M -3M | +1P
```
```
XXX.levelgen.carver.NoneCarverConfiguration +2M -2M | +2P
```
```
XXX.levelgen.carver.UnderwaterCaveWorldCarver +1M -1M
```
```
XXX.levelgen.feature.AbstractHugeMushroomFeature +1M -1M
```
```
XXX.levelgen.feature.BasaltColumnsFeature +1M -1M
```
```
XXX.levelgen.feature.BastionFeature$FeatureStart +2M -1M
```
```
XXX.levelgen.feature.BlockPileFeature +1M -1M
```
```
XXX.levelgen.feature.BonusChestFeature +1M -1M
```
```
XXX.levelgen.feature.BuriedTreasureFeature$BuriedTreasureStart +2M -1M
```
```
XXX.levelgen.feature.ConfiguredFeature +1M -3M | +2P
```
```
XXX.levelgen.feature.ReplaceBlobsFeature +1M -1M
```
```
XXX.levelgen.feature.RuinedPortalFeature +1M -6M
```
```
XXX.levelgen.feature.RuinedPortalFeature$Type +1M | +1P
```
```
XXX.levelgen.feature.SeaPickleFeature +1M -1M
```
```
XXX.levelgen.feature.ShipwreckFeature +1M -6M
```
```
XXX.levelgen.feature.SimpleBlockFeature +1M -1M
```
```
XXX.levelgen.feature.StrongholdFeature +3M -9M | -4P
```
```
XXX.levelgen.feature.StructureFeature +17M -18M | +22P -2P
```
```
XXX.levelgen.feature.SwamplandHutFeature$FeatureStart +2M -1M
```
```
XXX.levelgen.feature.TreeFeature +1M -1M
```
```
XXX.levelgen.feature.VillageFeature +1M -7M
```
```
XXX.levelgen.feature.VinesFeature +1M -1M
```
```
XXX.levelgen.feature.WeepingVinesFeature +1M -1M
```
```
XXX.levelgen.feature.WoodlandMansionFeature +3M -7M
```
```
XXX.feature.blockplacers.BlockPlacer +2M -1M | +2P -1P
```
```
XXX.feature.blockplacers.ColumnPlacer +5M -2M | +1P
```
```
XXX.feature.blockplacers.SimpleBlockPlacer +3M -2M | +2P
```
```
XXX.feature.configurations.BlockBlobConfiguration +4M -2M | +1P
```
```
XXX.feature.configurations.BlockStateConfiguration +2M -2M | +1P
```
```
XXX.feature.configurations.ChanceRangeDecoratorConfiguration +6M -2M | +1P
```
```
XXX.feature.configurations.CountRangeDecoratorConfiguration +6M -2M | +1P
```
```
XXX.feature.configurations.DecoratorConfiguration -1P
```
```
XXX.feature.configurations.EndGatewayConfiguration +4M -6M | +1P
```
```
XXX.feature.configurations.FeatureRadiusConfiguration +2M -2M | +1P
```
```
XXX.feature.configurations.JigsawConfiguration +4M -4M | +1P
```
```
XXX.feature.configurations.MineshaftConfiguration +4M -2M | +1P
```
```
XXX.feature.configurations.NoiseDependantDecoratorConfiguration +5M -2M | +1P
```
```
XXX.feature.configurations.NoneFeatureConfiguration +2M -2M | +2P
```
```
XXX.feature.configurations.OreConfiguration +5M -2M | +1P
```
```
XXX.feature.configurations.ProbabilityFeatureConfiguration +3M -2M | +1P
```
```
XXX.feature.configurations.RandomFeatureConfiguration +4M -3M | +1P
```
```
XXX.feature.configurations.RandomRandomFeatureConfiguration +4M -3M | +1P
```
```
XXX.feature.configurations.ReplaceSpheroidConfiguration +6M -2M | +1P
```
```
XXX.feature.configurations.RuinedPortalConfiguration +2M -3M | +1P
```
```
XXX.feature.configurations.ShipwreckConfiguration +2M -2M | +1P
```
```
XXX.feature.configurations.SimpleRandomFeatureConfiguration +2M -3M | +1P
```
```
XXX.feature.configurations.SpringConfiguration +7M -3M | +1P
```
```
XXX.feature.featuresize.FeatureSize +6M -3M | +2P -1P
```
```
XXX.feature.featuresize.ThreeLayersFeatureSize +8M -3M | +1P
```
```
XXX.feature.foliageplacers.BlobFoliagePlacer +5M -2M | +1P
```
```
XXX.feature.foliageplacers.DarkOakFoliagePlacer +3M -2M | +1P
```
```
XXX.feature.foliageplacers.FoliagePlacer +7M -2M | +2P -1P
```
```
XXX.levelgen.placement.CarvingMaskDecorator +1M -1M
```
```
XXX.levelgen.placement.ChanceDecoratorConfiguration +2M -2M | +1P
```
```
XXX.levelgen.placement.ChanceHeightmapDoubleDecorator +1M -1M
```
```
XXX.levelgen.placement.ChanceTopSolidHeightmapDecorator +1M -1M
```
```
XXX.levelgen.placement.ConfiguredDecorator +2M -3M | +1P
```
```
XXX.levelgen.placement.CountChanceHeightmapDecorator +1M -1M
```
```
XXX.levelgen.placement.CountDepthAverageDecorator +1M -1M
```
```
XXX.levelgen.placement.CountHeight64Decorator +1M -1M
```
```
XXX.levelgen.placement.CountHeightmapDecorator +1M -1M
```
```
XXX.levelgen.placement.CountVeryBiasedRangeDecorator +1M -1M
```
```
XXX.levelgen.placement.DarkOakTreePlacementDecorator +1M -1M
```
```
XXX.levelgen.placement.EmeraldPlacementDecorator +1M -1M
```
```
XXX.levelgen.placement.EndIslandPlacementDecorator +1M -1M
```
```
XXX.levelgen.placement.ForestRockPlacementDecorator +1M -1M
```
```
XXX.levelgen.placement.FrequencyDecoratorConfiguration +2M -2M | +1P
```
```
XXX.levelgen.placement.IcebergPlacementDecorator +1M -1M
```
```
XXX.levelgen.placement.LakeWaterPlacementDecorator +1M -1M
```
```
XXX.levelgen.placement.NoiseCountFactorDecoratorConfiguration +6M -2M | +2P
```
```
XXX.levelgen.placement.NoiseHeightmapDoubleDecorator +1M -1M
```
```
XXX.levelgen.placement.RangeDecoratorConfiguration +4M -2M | +1P
```
```
XXX.levelgen.placement.TopSolidHeightMapDecorator +1M -1M
```
```
XXX.levelgen.placement.TopSolidHeightMapRangeDecorator +1M -1M
```
```
XXX.placement.nether.CountRangeDecorator +1M -1M
```
```
XXX.placement.nether.LightGemChanceDecorator +1M -1M
```
```
XXX.placement.nether.RandomCountRangeDecorator +1M -1M
```
```
XXX.levelgen.structure.IglooPieces +1M -1M
```
```
XXX.levelgen.structure.NetherFossilFeature +1M -6M
```
```
XXX.levelgen.structure.OceanRuinFeature +1M -6M
```
```
XXX.levelgen.structure.OceanRuinFeature$Type +1M | +1P
```
```
XXX.levelgen.structure.RuinedPortalPiece +3M -1M | +1P
```
```
XXX.level.storage.LevelStorageSource +8M -2M | +2P
```
```
XXX.level.storage.LevelSummary +3M -2M | +3P -10P
```

</details>








































































































































































<details>
<summary>
net.minecraft.advancements.critereon.ChangeDimensionTrigger$TriggerInstance
</summary>

```diff
+ boolean matches(DimensionType,DimensionType)
- boolean matches(ResourceKey,ResourceKey)
+ ChangeDimensionTrigger$TriggerInstance changedDimension(DimensionType,DimensionType)
- ChangeDimensionTrigger$TriggerInstance changedDimension(ResourceKey,ResourceKey)
+ ChangeDimensionTrigger$TriggerInstance changedDimensionFrom(DimensionType)
- ChangeDimensionTrigger$TriggerInstance changedDimensionFrom(ResourceKey)
+ ChangeDimensionTrigger$TriggerInstance changedDimensionTo(DimensionType)
- ChangeDimensionTrigger$TriggerInstance changedDimensionTo(ResourceKey)
+ void <init>(EntityPredicate$Composite,DimensionType,DimensionType)
- void <init>(EntityPredicate$Composite,ResourceKey,ResourceKey)
```

</details>































<details>
<summary>
net.minecraft.advancements.critereon.LocationPredicate
</summary>

```diff
+ JsonSyntaxException lambda$fromJson$0(ResourceLocation)
- JsonSyntaxException lambda$fromJson$2(ResourceLocation)
+ LocationPredicate inDimension(DimensionType)
- LocationPredicate inDimension(ResourceKey)
- ResourceKey lambda$fromJson$1(ResourceLocation)
+ void <init>(MinMaxBounds$Floats,MinMaxBounds$Floats,MinMaxBounds$Floats,Biome,StructureFeature,DimensionType,Boolean,LightPredicate,BlockPredicate,FluidPredicate)
- void <init>(MinMaxBounds$Floats,MinMaxBounds$Floats,MinMaxBounds$Floats,Biome,StructureFeature,ResourceKey,Boolean,LightPredicate,BlockPredicate,FluidPredicate)
- void lambda$serializeToJson$0(JsonObject,JsonElement)
```

</details>





































<details>
<summary>
net.minecraft.client.Minecraft
</summary>

```diff
- boolean allowsChat()
- boolean allowsMultiplayer()
- boolean isBlocked(UUID)
- void openChatScreen(String)
```

</details>



















<details>
<summary>
net.minecraft.client.gui.GuiComponent
</summary>

```diff
- void fillGradient(Matrix4f,BufferBuilder,int,int,int,int,int,int,int)
+ void fillGradient(Matrix4f,int,int,int,int,int,int)
```

</details>


<details>
<summary>
net.minecraft.client.gui.chat.OverlayChatListener
</summary>

```diff
- void handle(ChatType,Component,UUID)
+ void handle(ChatType,Component)
```

</details>





<details>
<summary>
net.minecraft.client.gui.components.Button
</summary>

```diff
- void <clinit>()
- void <init>(int,int,int,int,Component,Button$OnPress,Button$OnTooltip)
- void lambda$static$0(Button,PoseStack,int,int)
- void renderButton(PoseStack,int,int,float)
- void renderToolTip(PoseStack,int,int)
```

</details>




































































<details>
<summary>
net.minecraft.client.multiplayer.ClientLevel
</summary>

```diff
- RegistryAccess registryAccess()
- void setGameTime(long)
- void tickTime()
```

</details>















































































































































































































































































































































































<details>
<summary>
net.minecraft.commands.CommandSource$1
</summary>

```diff
- void sendMessage(Component,UUID)
+ void sendMessage(Component)
```

</details>



























































<details>
<summary>
net.minecraft.core.BlockPos
</summary>

```diff
+ BlockPos deserialize(Dynamic)
- BlockPos lambda$null$0(int[])
- DataResult lambda$static$1(IntStream)
- IntStream lambda$static$2(BlockPos)
+ Object serialize(DynamicOps)
+ void lambda$deserialize$0(int[],int)
+ void lambda$deserialize$1(int[],int)
+ void lambda$deserialize$2(int[],int)
```

</details>









<details>
<summary>
net.minecraft.core.GlobalPos
</summary>

```diff
- App lambda$static$0(RecordCodecBuilder$Instance)
+ DimensionType dimension()
+ GlobalPos lambda$null$0(DimensionType,BlockPos)
+ GlobalPos of(DimensionType,BlockPos)
+ GlobalPos of(Dynamic)
- GlobalPos of(ResourceKey,BlockPos)
+ IllegalArgumentException lambda$of$2()
+ Object serialize(DynamicOps)
+ Optional lambda$of$1(Dynamic,DimensionType)
- ResourceKey dimension()
- void <clinit>()
+ void <init>(DimensionType,BlockPos)
- void <init>(ResourceKey,BlockPos)
```

</details>


<details>
<summary>
net.minecraft.core.SerializableUUID
</summary>

```diff
- DataResult lambda$static$1(IntStream)
- IntStream lambda$static$2(SerializableUUID)
+ Object serialize(DynamicOps,UUID)
+ Object serialize(DynamicOps)
- SerializableUUID lambda$null$0(int[])
+ SerializableUUID of(Dynamic)
- SerializableUUID of(Dynamic)
+ UUID readUUID(Dynamic)
- UUID readUUID(Dynamic)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.core.Vec3i
</summary>

```diff
- DataResult lambda$static$1(IntStream)
- IntStream lambda$static$2(Vec3i)
- Vec3i lambda$null$0(int[])
```

</details>


















<details>
<summary>
net.minecraft.core.particles.BlockParticleOption
</summary>

```diff
- BlockParticleOption lambda$codec$0(ParticleType,BlockState)
- BlockState lambda$codec$1(BlockParticleOption)
- Codec codec(ParticleType)
```

</details>
<details>
<summary>
net.minecraft.core.particles.DustParticleOptions
</summary>

```diff
- App lambda$static$4(RecordCodecBuilder$Instance)
- Float lambda$null$0(DustParticleOptions)
- Float lambda$null$1(DustParticleOptions)
- Float lambda$null$2(DustParticleOptions)
- Float lambda$null$3(DustParticleOptions)
```

</details>
<details>
<summary>
net.minecraft.core.particles.ItemParticleOption
</summary>

```diff
- Codec codec(ParticleType)
- ItemParticleOption lambda$codec$0(ParticleType,ItemStack)
- ItemStack lambda$codec$1(ItemParticleOption)
```

</details>








<details>
<summary>
net.minecraft.server.Main
</summary>

```diff
- void forceUpgrade(LevelStorageSource$LevelStorageAccess,DataFixer,boolean,BooleanSupplier)
```

</details>
<details>
<summary>
net.minecraft.server.MinecraftServer
</summary>

```diff
- RegistryAccess registryAccess()
+ ServerLevel getLevel(DimensionType)
- ServerLevel getLevel(ResourceKey)
- void convertFromRegionFormatIfNeeded(LevelStorageSource$LevelStorageAccess)
+ void ensureLevelConversion(LevelStorageSource$LevelStorageAccess,DataFixer,boolean,boolean,BooleanSupplier)
- void sendMessage(Component,UUID)
+ void sendMessage(Component)
+ void setInitialSpawn(ServerLevel,Dimension,ServerLevelData,boolean,boolean)
- void setInitialSpawn(ServerLevel,ServerLevelData,boolean,boolean,boolean)
```

</details>





























<details>
<summary>
net.minecraft.server.commands.LocateCommand
</summary>

```diff
+ int lambda$register$1(CommandContext)
- int lambda$register$1(Map$Entry,CommandContext)
+ int lambda$register$10(CommandContext)
+ int lambda$register$11(CommandContext)
+ int lambda$register$12(CommandContext)
+ int lambda$register$13(CommandContext)
+ int lambda$register$14(CommandContext)
+ int lambda$register$15(CommandContext)
+ int lambda$register$16(CommandContext)
+ int lambda$register$17(CommandContext)
+ int lambda$register$18(CommandContext)
+ int lambda$register$2(CommandContext)
+ int lambda$register$3(CommandContext)
+ int lambda$register$4(CommandContext)
+ int lambda$register$5(CommandContext)
+ int lambda$register$6(CommandContext)
+ int lambda$register$7(CommandContext)
+ int lambda$register$8(CommandContext)
+ int lambda$register$9(CommandContext)
+ int locate(CommandSourceStack,String)
- int locate(CommandSourceStack,StructureFeature)
+ Style lambda$showLocateResult$19(BlockPos,Style)
- Style lambda$showLocateResult$2(BlockPos,Style)
```

</details>














<details>
<summary>
net.minecraft.server.commands.SpreadPlayersCommand
</summary>

```diff
+ double setPlayerPositions(Collection,ServerLevel,SpreadPlayersCommand$Position[],boolean)
- double setPlayerPositions(Collection,ServerLevel,SpreadPlayersCommand$Position[],int,boolean)
- int lambda$register$4(CommandContext)
+ int spreadPlayers(CommandSourceStack,Vec2,float,float,boolean,Collection)
- int spreadPlayers(CommandSourceStack,Vec2,float,float,int,boolean,Collection)
- void spreadPositions(Vec2,double,ServerLevel,Random,double,double,double,double,int,SpreadPlayersCommand$Position[],boolean)
+ void spreadPositions(Vec2,double,ServerLevel,Random,double,double,double,double,SpreadPlayersCommand$Position[],boolean)
```

</details>














<details>
<summary>
net.minecraft.server.dedicated.DedicatedPlayerList
</summary>

```diff
+ void <init>(DedicatedServer,PlayerDataStorage)
- void <init>(DedicatedServer,RegistryAccess$RegistryHolder,PlayerDataStorage)
```

</details>






















<details>
<summary>
net.minecraft.server.level.ServerLevel
</summary>

```diff
+ BlockPos findNearestMapFeature(String,BlockPos,int,boolean)
- BlockPos findNearestMapFeature(StructureFeature,BlockPos,int,boolean)
+ BlockPos getDimensionSpecificSpawn()
- EndDragonFight dragonFight()
- RegistryAccess registryAccess()
- void <init>(MinecraftServer,Executor,LevelStorageSource$LevelStorageAccess,ServerLevelData,DimensionType,ChunkProgressListener,ChunkGenerator,boolean,long,List,boolean)
+ void <init>(MinecraftServer,Executor,LevelStorageSource$LevelStorageAccess,ServerLevelData,DimensionType,ChunkProgressListener,ChunkGenerator,boolean,long)
- void lambda$makeObsidianPlatform$16(ServerLevel,BlockPos)
- void lambda$makeObsidianPlatform$17(ServerLevel,BlockPos)
- void makeObsidianPlatform(ServerLevel)
- void setDayTime(long)
+ void setGameTime(long)
- void tickCustomSpawners(boolean,boolean)
- void tickTime()
```

</details>



















































<details>
<summary>
net.minecraft.server.rcon.RconConsoleSource
</summary>

```diff
- void sendMessage(Component,UUID)
+ void sendMessage(Component)
```

</details>



<details>
<summary>
net.minecraft.sounds.Music
</summary>

```diff
- App lambda$static$4(RecordCodecBuilder$Instance)
- Boolean lambda$null$3(Music)
- Integer lambda$null$1(Music)
- Integer lambda$null$2(Music)
- SoundEvent lambda$null$0(Music)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.sounds.SoundEvent
</summary>

```diff
- ResourceLocation lambda$static$0(SoundEvent)
- void <clinit>()
```

</details>




















<details>
<summary>
net.minecraft.util.datafix.fixes.AddNewChoices
</summary>

```diff
+ Function lambda$cap$1(TaggedChoice$TaggedChoiceType,DynamicOps)
- Function lambda$cap$1(TaggedChoice$TaggedChoiceType,DynamicOps)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.AdvancementsRenameFix
</summary>

```diff
+ Dynamic lambda$null$0(Dynamic,String,Dynamic)
- Dynamic lambda$null$0(Dynamic,String,Dynamic)
+ Dynamic lambda$null$2(Dynamic)
- Dynamic lambda$null$2(Dynamic)
+ Pair lambda$null$1(Dynamic,Pair)
- Pair lambda$null$1(Dynamic,Pair)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.BedBlockEntityInjecter
</summary>

```diff
+ Function lambda$cap$1(DynamicOps)
- Function lambda$cap$1(DynamicOps)
+ Integer lambda$null$2(Dynamic)
- Integer lambda$null$2(Dynamic)
```

</details>

<details>
<summary>
net.minecraft.util.datafix.fixes.BitStorageAlignFix
</summary>

```diff
+ Dynamic lambda$null$2(Dynamic,Dynamic)
- Dynamic lambda$null$2(Dynamic,Dynamic)
+ Dynamic lambda$null$4(Dynamic,Dynamic)
- Dynamic lambda$null$4(Dynamic,Dynamic)
+ Dynamic lambda$null$7(Dynamic,int,Dynamic)
- Dynamic lambda$null$7(Dynamic,int,Dynamic)
+ Dynamic lambda$null$8(int,Dynamic)
- Dynamic lambda$null$8(int,Dynamic)
+ Dynamic lambda$updateHeightmaps$5(Dynamic)
- Dynamic lambda$updateHeightmaps$5(Dynamic)
+ Dynamic updateBitStorage(Dynamic,Dynamic,int,int)
- Dynamic updateBitStorage(Dynamic,Dynamic,int,int)
+ Pair lambda$null$3(Dynamic,Pair)
- Pair lambda$null$3(Dynamic,Pair)
```

</details>

<details>
<summary>
net.minecraft.util.datafix.fixes.BlockEntityIdFix
</summary>

```diff
+ Function lambda$makeRule$3(DynamicOps)
- Function lambda$makeRule$3(DynamicOps)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.BlockEntityKeepPacked
</summary>

```diff
+ Dynamic fixTag(Dynamic)
- Dynamic fixTag(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.BlockEntitySignTextStrictJsonFix
</summary>

```diff
+ Dynamic lambda$fix$0(Dynamic)
- Dynamic lambda$fix$0(Dynamic)
+ Dynamic updateLine(Dynamic,String)
- Dynamic updateLine(Dynamic,String)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.BlockEntityUUIDFix
</summary>

```diff
+ Dynamic lambda$updateSkull$1(Dynamic)
- Dynamic lambda$updateSkull$1(Dynamic)
+ Dynamic lambda$updateSkull$2(Dynamic,Dynamic)
- Dynamic lambda$updateSkull$2(Dynamic,Dynamic)
+ Dynamic updateConduit(Dynamic)
- Dynamic updateConduit(Dynamic)
+ Dynamic updateSkull(Dynamic)
- Dynamic updateSkull(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.BlockRenameFix
</summary>

```diff
+ Dynamic lambda$null$2(Dynamic)
- Dynamic lambda$null$2(Dynamic)
+ Function lambda$makeRule$1(DynamicOps)
- Function lambda$makeRule$1(DynamicOps)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.BlockRenameFixWithJigsaw
</summary>

```diff
+ Dynamic lambda$null$1(Dynamic,Dynamic)
- Dynamic lambda$null$1(Dynamic,Dynamic)
+ Dynamic lambda$null$2(Dynamic)
- Dynamic lambda$null$2(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.BlockStateData
</summary>

```diff
+ Dynamic getTag(int)
- Dynamic getTag(int)
+ Dynamic parse(String)
- Dynamic parse(String)
+ Dynamic upgradeBlockStateTag(Dynamic)
- Dynamic upgradeBlockStateTag(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.CatTypeFix
</summary>

```diff
+ Dynamic fixTag(Dynamic)
- Dynamic fixTag(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.ChunkLightRemoveFix
</summary>

```diff
+ Dynamic lambda$null$0(Dynamic)
- Dynamic lambda$null$0(Dynamic)
```

</details>



<details>
<summary>
net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$UpgradeChunk
</summary>

```diff
+ Dynamic getBlock(int)
- Dynamic getBlock(int)
+ Dynamic getBlockEntity(int)
- Dynamic getBlockEntity(int)
+ Dynamic removeBlockEntity(int)
- Dynamic removeBlockEntity(int)
+ Dynamic write()
- Dynamic write()
+ void <init>(Dynamic)
- void <init>(Dynamic)
+ void lambda$null$0(Dynamic)
- void lambda$null$0(Dynamic)
+ void lambda$null$2(Dynamic)
- void lambda$null$2(Dynamic)
+ void setBlock(int,Dynamic)
- void setBlock(int,Dynamic)
```

</details>

<details>
<summary>
net.minecraft.util.datafix.fixes.ChunkToProtochunkFix
</summary>

```diff
+ Dynamic lambda$null$0(Dynamic,int)
- Dynamic lambda$null$4(Dynamic,ShortList)
+ IllegalStateException lambda$null$2()
- IllegalStateException lambda$null$5()
- Optional lambda$null$0(Typed)
- Optional lambda$null$1(Dynamic)
- ShortArrayList lambda$null$2(int)
+ Typed lambda$makeRule$4(OpticFinder,Type,OpticFinder,Typed)
- Typed lambda$makeRule$7(OpticFinder,Type,OpticFinder,Typed)
+ Typed lambda$null$3(OpticFinder,Type,Typed)
- Typed lambda$null$6(OpticFinder,Type,Typed)
+ void lambda$null$1(List,Dynamic,Dynamic)
- void lambda$null$3(List,Dynamic)
```

</details>

<details>
<summary>
net.minecraft.util.datafix.fixes.EntityBlockStateFix
</summary>

```diff
+ Either lambda$updateFallingBlock$10(Dynamic,Either)
- Either lambda$updateFallingBlock$10(Dynamic,Either)
+ Integer lambda$null$8(Dynamic)
- Integer lambda$null$8(Dynamic)
+ Integer lambda$null$9(Dynamic,Unit)
- Integer lambda$null$9(Dynamic,Unit)
+ Pair lambda$updateBlockToBlockState$12(Dynamic,String,Pair)
- Pair lambda$updateBlockToBlockState$12(Dynamic,String,Pair)
```

</details>

<details>
<summary>
net.minecraft.util.datafix.fixes.EntityElderGuardianSplitFix
</summary>

```diff
+ Pair getNewNameAndTag(String,Dynamic)
- Pair getNewNameAndTag(String,Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.EntityHealthFix
</summary>

```diff
+ Dynamic fixTag(Dynamic)
- Dynamic fixTag(Dynamic)
```

</details>

<details>
<summary>
net.minecraft.util.datafix.fixes.EntityItemFrameDirectionFix
</summary>

```diff
+ Dynamic fixTag(Dynamic)
- Dynamic fixTag(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.EntityPaintingItemFrameDirectionFix
</summary>

```diff
+ Dynamic doFix(Dynamic,boolean,boolean)
- Dynamic doFix(Dynamic,boolean,boolean)
+ Dynamic lambda$null$0(Dynamic)
- Dynamic lambda$null$0(Dynamic)
+ Dynamic lambda$null$3(Dynamic)
- Dynamic lambda$null$3(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.EntityProjectileOwnerFix
</summary>

```diff
+ Dynamic setUUID(Dynamic,long,long)
- Dynamic setUUID(Dynamic,long,long)
+ Dynamic updateItemPotion(Dynamic)
- Dynamic updateItemPotion(Dynamic)
+ Dynamic updateOwnerArrow(Dynamic)
- Dynamic updateOwnerArrow(Dynamic)
+ Dynamic updateOwnerLlamaSpit(Dynamic)
- Dynamic updateOwnerLlamaSpit(Dynamic)
+ Dynamic updateOwnerThrowable(Dynamic)
- Dynamic updateOwnerThrowable(Dynamic)
```

</details>

<details>
<summary>
net.minecraft.util.datafix.fixes.EntityRenameFix
</summary>

```diff
+ Function lambda$makeRule$1(TaggedChoice$TaggedChoiceType,TaggedChoice$TaggedChoiceType,DynamicOps)
- Function lambda$makeRule$1(TaggedChoice$TaggedChoiceType,TaggedChoice$TaggedChoiceType,DynamicOps)
+ Pair lambda$null$0(TaggedChoice$TaggedChoiceType,DynamicOps,TaggedChoice$TaggedChoiceType,Pair)
- Pair lambda$null$0(TaggedChoice$TaggedChoiceType,DynamicOps,TaggedChoice$TaggedChoiceType,Pair)
+ Typed getEntity(Object,DynamicOps,Type)
- Typed getEntity(Object,DynamicOps,Type)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.EntityShulkerColorFix
</summary>

```diff
+ Dynamic fixTag(Dynamic)
- Dynamic fixTag(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.EntitySkeletonSplitFix
</summary>

```diff
+ Pair getNewNameAndTag(String,Dynamic)
- Pair getNewNameAndTag(String,Dynamic)
```

</details>

<details>
<summary>
net.minecraft.util.datafix.fixes.EntityUUIDFix
</summary>

```diff
+ Dynamic lambda$null$1(Dynamic)
- Dynamic lambda$null$1(Dynamic)
+ Dynamic lambda$null$10(Dynamic)
- Dynamic lambda$null$10(Dynamic)
+ Dynamic lambda$null$11(Dynamic,Dynamic)
- Dynamic lambda$null$11(Dynamic,Dynamic)
+ Dynamic lambda$null$12(Dynamic)
- Dynamic lambda$null$12(Dynamic)
+ Dynamic lambda$null$2(Dynamic)
- Dynamic lambda$null$2(Dynamic)
+ Dynamic lambda$null$3(Dynamic)
- Dynamic lambda$null$3(Dynamic)
+ Dynamic lambda$null$5(Dynamic)
- Dynamic lambda$null$5(Dynamic)
+ Dynamic lambda$null$6(Dynamic)
- Dynamic lambda$null$6(Dynamic)
+ Dynamic lambda$updateFox$7(Dynamic,Dynamic)
- Dynamic lambda$updateFox$7(Dynamic,Dynamic)
+ Dynamic lambda$updateFox$8(Dynamic,Dynamic)
- Dynamic lambda$updateFox$8(Dynamic,Dynamic)
+ Dynamic lambda$updateLivingEntity$13(Dynamic,Dynamic)
- Dynamic lambda$updateLivingEntity$13(Dynamic,Dynamic)
+ Dynamic lambda$updateMob$9(Dynamic)
- Dynamic lambda$updateMob$9(Dynamic)
+ Dynamic lambda$updatePiglin$4(Dynamic)
- Dynamic lambda$updatePiglin$4(Dynamic)
+ Dynamic lambda$updateProjectile$14(Dynamic,Dynamic)
- Dynamic lambda$updateProjectile$14(Dynamic,Dynamic)
+ Dynamic updateAnimal(Dynamic)
- Dynamic updateAnimal(Dynamic)
+ Dynamic updateAnimalOwner(Dynamic)
- Dynamic updateAnimalOwner(Dynamic)
+ Dynamic updateAreaEffectCloud(Dynamic)
- Dynamic updateAreaEffectCloud(Dynamic)
+ Dynamic updateEntityUUID(Dynamic)
- Dynamic updateEntityUUID(Dynamic)
+ Dynamic updateEvokerFangs(Dynamic)
- Dynamic updateEvokerFangs(Dynamic)
+ Dynamic updateFox(Dynamic)
- Dynamic updateFox(Dynamic)
+ Dynamic updateHurtBy(Dynamic)
- Dynamic updateHurtBy(Dynamic)
+ Dynamic updateItem(Dynamic)
- Dynamic updateItem(Dynamic)
+ Dynamic updateLivingEntity(Dynamic)
- Dynamic updateLivingEntity(Dynamic)
+ Dynamic updateMob(Dynamic)
- Dynamic updateMob(Dynamic)
+ Dynamic updatePiglin(Dynamic)
- Dynamic updatePiglin(Dynamic)
+ Dynamic updateProjectile(Dynamic)
- Dynamic updateProjectile(Dynamic)
+ Dynamic updateShulkerBullet(Dynamic)
- Dynamic updateShulkerBullet(Dynamic)
+ Dynamic updateZombieVillager(Dynamic)
- Dynamic updateZombieVillager(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.EntityZombieSplitFix
</summary>

```diff
+ Pair getNewNameAndTag(String,Dynamic)
- Pair getNewNameAndTag(String,Dynamic)
```

</details>

<details>
<summary>
net.minecraft.util.datafix.fixes.FurnaceRecipeFix
</summary>

```diff
+ void lambda$null$4(List,int,Object)
- void lambda$null$4(List,int,Pair)
+ void lambda$updateFurnaceContents$5(Type,List,int,Dynamic)
- void lambda$updateFurnaceContents$5(Type,List,int,Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.HeightmapRenamingFix
</summary>

```diff
+ Dynamic fix(Dynamic)
- Dynamic fix(Dynamic)
```

</details>




<details>
<summary>
net.minecraft.util.datafix.fixes.ItemSpawnEggFix
</summary>

```diff
- DataResult lambda$null$4(Type,Dynamic,String,Dynamic)
+ IllegalStateException lambda$null$4()
- IllegalStateException lambda$null$5()
+ Typed lambda$makeRule$5(OpticFinder,OpticFinder,OpticFinder,OpticFinder,OpticFinder,Typed)
- Typed lambda$makeRule$6(OpticFinder,OpticFinder,OpticFinder,OpticFinder,OpticFinder,Type,Typed)
```

</details>



<details>
<summary>
net.minecraft.util.datafix.fixes.JigsawPropertiesFix
</summary>

```diff
+ Dynamic fixTag(Dynamic)
- Dynamic fixTag(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.LeavesFix
</summary>

```diff
+ Dynamic lambda$null$5(int[],Dynamic)
- Dynamic lambda$null$5(int[],Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.LeavesFix$Section
</summary>

```diff
+ Dynamic lambda$write$1(Dynamic)
- Dynamic lambda$write$1(Dynamic)
+ Pair lambda$write$2(Dynamic)
- Pair lambda$write$2(Dynamic)
+ void readStorage(Dynamic)
- void readStorage(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.LevelFlatGeneratorInfoFix
</summary>

```diff
+ Dynamic fix(Dynamic)
- Dynamic fix(Dynamic)
+ Dynamic lambda$fix$1(Dynamic)
- Dynamic lambda$fix$1(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.MapIdFix
</summary>

```diff
+ Dynamic lambda$null$0(Dynamic)
- Dynamic lambda$null$0(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.MobSpawnerEntityIdentifiersFix
</summary>

```diff
+ Dynamic fix(Dynamic)
- Dynamic fix(Dynamic)
+ Dynamic lambda$fix$0(Dynamic)
- Dynamic lambda$fix$0(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.NewVillageFix
</summary>

```diff
+ Dynamic lambda$null$11(Dynamic)
- Dynamic lambda$null$11(Dynamic)
+ Dynamic lambda$null$12(Dynamic)
- Dynamic lambda$null$12(Dynamic)
+ Dynamic lambda$null$5(Dynamic,Dynamic)
- Dynamic lambda$null$5(Dynamic,Dynamic)
+ Dynamic lambda$null$6(Dynamic)
- Dynamic lambda$null$6(Dynamic)
+ Dynamic lambda$null$7(Dynamic)
- Dynamic lambda$null$7(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.ObjectiveRenderTypeFix
</summary>

```diff
+ Dynamic lambda$null$0(Dynamic)
- Dynamic lambda$null$0(Dynamic)
+ Function lambda$makeRule$2(DynamicOps)
- Function lambda$makeRule$2(DynamicOps)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.OptionsForceVBOFix
</summary>

```diff
+ Dynamic lambda$null$0(Dynamic)
- Dynamic lambda$null$0(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.OptionsKeyTranslationFix
</summary>

```diff
+ Dynamic lambda$null$1(Dynamic,Map)
- Dynamic lambda$null$1(Dynamic,Map)
+ Dynamic lambda$null$2(Dynamic)
- Dynamic lambda$null$2(Dynamic)
+ Pair lambda$null$0(Dynamic,Map$Entry)
- Pair lambda$null$0(Dynamic,Map$Entry)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.PlayerUUIDFix
</summary>

```diff
+ Dynamic lambda$null$0(Dynamic)
- Dynamic lambda$null$0(Dynamic)
+ Dynamic lambda$null$2(Dynamic)
- Dynamic lambda$null$2(Dynamic)
```

</details>




<details>
<summary>
net.minecraft.util.datafix.fixes.ReorganizePoi
</summary>

```diff
+ Dynamic cap(Dynamic)
- Dynamic cap(Dynamic)
+ Function lambda$makeRule$1(DynamicOps)
- Function lambda$makeRule$1(DynamicOps)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.SavedDataVillageCropFix
</summary>

```diff
+ Dynamic fixTag(Dynamic)
- Dynamic fixTag(Dynamic)
+ Dynamic lambda$updateChildren$0(Dynamic)
- Dynamic lambda$updateChildren$0(Dynamic)
+ Dynamic updateChildren(Dynamic)
- Dynamic updateChildren(Dynamic)
+ Dynamic updateCrop(Dynamic,String)
- Dynamic updateCrop(Dynamic,String)
+ Dynamic updateDoubleField(Dynamic)
- Dynamic updateDoubleField(Dynamic)
+ Dynamic updateSingleField(Dynamic)
- Dynamic updateSingleField(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.SimplestEntityRenameFix
</summary>

```diff
+ Function lambda$makeRule$2(TaggedChoice$TaggedChoiceType,TaggedChoice$TaggedChoiceType,DynamicOps)
- Function lambda$makeRule$2(TaggedChoice$TaggedChoiceType,TaggedChoice$TaggedChoiceType,DynamicOps)
+ Function lambda$makeRule$4(DynamicOps)
- Function lambda$makeRule$4(DynamicOps)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.StriderGravityFix
</summary>

```diff
+ Dynamic fixTag(Dynamic)
- Dynamic fixTag(Dynamic)
```

</details>



<details>
<summary>
net.minecraft.util.datafix.fixes.VillagerRebuildLevelAndXpFix
</summary>

```diff
+ Dynamic lambda$addLevel$5(int,Dynamic)
- Dynamic lambda$addLevel$5(int,Dynamic)
+ Dynamic lambda$addXpFromLevel$6(int,Dynamic)
- Dynamic lambda$addXpFromLevel$6(int,Dynamic)
+ Dynamic lambda$null$4(int,Dynamic)
- Dynamic lambda$null$4(int,Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.WallPropertyFix
</summary>

```diff
+ Dynamic fixWallProperty(Dynamic,String)
- Dynamic fixWallProperty(Dynamic,String)
+ Dynamic lambda$fixWallProperty$1(Dynamic)
- Dynamic lambda$fixWallProperty$1(Dynamic)
+ Dynamic lambda$upgradeBlockStateTag$2(Dynamic)
- Dynamic lambda$upgradeBlockStateTag$2(Dynamic)
+ Dynamic upgradeBlockStateTag(Dynamic)
- Dynamic upgradeBlockStateTag(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.util.datafix.fixes.ZombieVillagerRebuildXpFix
</summary>

```diff
+ Dynamic lambda$fix$0(Dynamic)
- Dynamic lambda$fix$0(Dynamic)
```

</details>






<details>
<summary>
net.minecraft.util.datafix.schemas.V99$1
</summary>

```diff
+ Object apply(DynamicOps,Object)
- Object apply(DynamicOps,Object)
```

</details>
















<details>
<summary>
net.minecraft.util.worldupdate.WorldUpgrader
</summary>

```diff
+ boolean lambda$getAllChunkPos$2(File,String)
- boolean lambda$getAllChunkPos$3(File,String)
+ DimensionDataStorage lambda$work$1()
- DimensionDataStorage lambda$work$2()
- DimensionType lambda$new$0(Map$Entry)
- ImmutableMap dimensionTypes()
+ List getAllChunkPos(DimensionType)
- List getAllChunkPos(ResourceKey)
+ void lambda$new$0(Thread,Throwable)
- void lambda$new$1(Thread,Throwable)
```

</details>



























<details>
<summary>
net.minecraft.world.entity.EntityType
</summary>

```diff
+ Logger access$000()
```

</details>




<details>
<summary>
net.minecraft.world.entity.LivingEntity
</summary>

```diff
+ Boolean lambda$checkBedExists$6(BlockPos)
- Boolean lambda$checkBedExists$7(BlockPos)
+ boolean lambda$isHolding$4(Item,Item)
- boolean lambda$isHolding$5(Item,Item)
+ Brain makeBrain(Dynamic)
- Brain makeBrain(Dynamic)
- Brain$Provider brainProvider()
+ Vec3 lambda$null$7(BlockPos)
- Vec3 lambda$null$8(BlockPos)
- void lambda$addAdditionalSaveData$2(CompoundTag,Tag)
+ void lambda$hurt$3(LivingEntity)
- void lambda$hurt$4(LivingEntity)
+ void lambda$stopSleeping$8(BlockPos)
- void lambda$stopSleeping$9(BlockPos)
+ void lambda$tickEffects$2(MobEffectInstance)
- void lambda$tickEffects$3(MobEffectInstance)
+ void lambda$updateFallFlying$5(LivingEntity)
- void lambda$updateFallFlying$6(LivingEntity)
```

</details>

<details>
<summary>
net.minecraft.world.entity.MobCategory
</summary>

```diff
- String getSerializedName()
```

</details>























































<details>
<summary>
net.minecraft.world.entity.ai.gossip.GossipContainer$GossipEntry
</summary>

```diff
- DataResult load(Dynamic)
+ Dynamic store(DynamicOps)
- Dynamic store(DynamicOps)
+ GossipContainer$GossipEntry lambda$null$0(UUID,GossipType,Number)
+ Optional lambda$load$2(Dynamic,GossipType)
+ Optional lambda$null$1(Dynamic,GossipType,UUID)
+ Optional load(Dynamic)
- void <init>(SerializableUUID,GossipType,int)
```

</details>

<details>
<summary>
net.minecraft.world.entity.ai.memory.MemoryModuleType
</summary>

```diff
- MemoryModuleType register(String,Codec)
+ MemoryModuleType register(String,Optional)
- Optional getCodec()
+ Optional getDeserializer()
```

</details>



















<details>
<summary>
net.minecraft.world.entity.ai.village.poi.PoiRecord
</summary>

```diff
- App lambda$codec$3(Runnable,RecordCodecBuilder$Instance)
- BlockPos lambda$null$0(PoiRecord)
- Codec codec(Runnable)
- Integer lambda$null$2(PoiRecord)
+ Object serialize(DynamicOps)
- PoiType lambda$null$1(PoiRecord)
+ void <init>(Dynamic,Runnable)
```

</details>


































































<details>
<summary>
net.minecraft.world.entity.animal.horse.AbstractHorse
</summary>

```diff
- SoundEvent getEatingSound()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.horse.Horse
</summary>

```diff
- SoundEvent getEatingSound()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.horse.Llama
</summary>

```diff
- SoundEvent getEatingSound()
```

</details>


<details>
<summary>
net.minecraft.world.entity.animal.horse.Mule
</summary>

```diff
- SoundEvent getAngrySound()
- SoundEvent getEatingSound()
```

</details>























<details>
<summary>
net.minecraft.world.entity.item.ItemEntity
</summary>

```diff
+ Entity changeDimension(DimensionType)
- Entity changeDimension(ResourceKey)
```

</details>























































<details>
<summary>
net.minecraft.world.entity.monster.Zoglin
</summary>

```diff
+ Brain makeBrain(Dynamic)
- Brain makeBrain(Dynamic)
- Brain$Provider brainProvider()
```

</details>

<details>
<summary>
net.minecraft.world.entity.monster.ZombieVillager
</summary>

```diff
- void lambda$addAdditionalSaveData$0(CompoundTag,Tag)
```

</details>

<details>
<summary>
net.minecraft.world.entity.monster.hoglin.Hoglin
</summary>

```diff
+ Brain makeBrain(Dynamic)
- Brain makeBrain(Dynamic)
- Brain$Provider brainProvider()
```

</details>






<details>
<summary>
net.minecraft.world.entity.npc.AbstractVillager
</summary>

```diff
+ Entity changeDimension(DimensionType)
- Entity changeDimension(ResourceKey)
```

</details>


<details>
<summary>
net.minecraft.world.entity.npc.VillagerData
</summary>

```diff
- App lambda$static$3(RecordCodecBuilder$Instance)
- Integer lambda$null$2(VillagerData)
+ Object serialize(DynamicOps)
- VillagerProfession lambda$null$1(VillagerData)
- VillagerType lambda$null$0(VillagerData)
+ void <init>(Dynamic)
```

</details>






<details>
<summary>
net.minecraft.world.entity.npc.VillagerTrades$TreasureMapForEmeralds
</summary>

```diff
+ void <init>(int,String,MapDecoration$Type,int,int)
- void <init>(int,StructureFeature,MapDecoration$Type,int,int)
```

</details>


































<details>
<summary>
net.minecraft.world.entity.vehicle.AbstractMinecartContainer
</summary>

```diff
+ Entity changeDimension(DimensionType)
- Entity changeDimension(ResourceKey)
```

</details>






























































































<details>
<summary>
net.minecraft.world.item.MapItem
</summary>

```diff
+ MapItemSavedData createAndStoreSavedData(ItemStack,Level,int,int,int,boolean,boolean,DimensionType)
- MapItemSavedData createAndStoreSavedData(ItemStack,Level,int,int,int,boolean,boolean,ResourceKey)
```

</details>









































































<details>
<summary>
net.minecraft.world.level.BaseCommandBlock
</summary>

```diff
- void sendMessage(Component,UUID)
+ void sendMessage(Component)
```

</details>


















<details>
<summary>
net.minecraft.world.level.Level
</summary>

```diff
+ Dimension getDimension()
- ResourceKey dimension()
+ void setDayTime(long)
+ void setGameTime(long)
+ void tickTime()
```

</details>



<details>
<summary>
net.minecraft.world.level.biome.CheckerboardColumnBiomeSource
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
- Codec codec()
- Integer lambda$null$1(CheckerboardColumnBiomeSource)
- List lambda$null$0(CheckerboardColumnBiomeSource)
- void <clinit>()
+ void <init>(Biome[],int)
- void <init>(List,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.CrimsonForestBiome
</summary>

```diff
+ Double lambda$new$0(Random)
+ Double lambda$new$1(Random)
+ Double lambda$new$2(Random)
```

</details>



















<details>
<summary>
net.minecraft.world.level.block.state.StateHolder
</summary>

```diff
- boolean hasProperty(Property)
- Codec codec(Codec,Function)
- Codec lambda$codec$1(Function,Object)
- Collection getProperties()
- Comparable getValue(Property)
- ImmutableMap getValues()
- Map makeNeighbourValues(Property,Comparable)
- Object cycle(Property)
- Object findNextInCollection(Collection,Object)
- Object lambda$codec$0(StateHolder)
- Object setValue(Property,Comparable)
- Optional getOptionalValue(Property)
+ StateHolder setValueHelper(StateHolder,Property,String,String,String)
+ String getName(Property,Comparable)
- String toString()
- void <init>(Object,ImmutableMap,MapCodec)
- void populateNeighbours(Map)
```

</details>

















<details>
<summary>
net.minecraft.world.level.chunk.ChunkAccess
</summary>

```diff
+ BitSet getCarvingMask(GenerationStep$Carving)
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.ChunkGenerator
</summary>

```diff
+ Biome getCarvingOrDecorationBiome(BiomeManager,BlockPos)
+ Biome lambda$applyCarvers$0(BiomeManager,BlockPos)
+ BlockPos findNearestMapFeature(ServerLevel,String,BlockPos,int,boolean)
- BlockPos findNearestMapFeature(ServerLevel,StructureFeature,BlockPos,int,boolean)
+ boolean canGenerateStructure(StructureFeature)
- boolean hasStronghold(ChunkPos)
+ boolean isBiomeValidStartForStructure(Biome,StructureFeature)
+ ChunkGeneratorSettings getSettings()
+ FeatureConfiguration getStructureConfiguration(Biome,StructureFeature)
- StructureSettings getSettings()
- void <clinit>()
- void <init>(BiomeSource,BiomeSource,StructureSettings,long)
+ void <init>(BiomeSource,ChunkGeneratorSettings)
- void <init>(BiomeSource,StructureSettings)
- void createStructure(ConfiguredStructureFeature,StructureFeatureManager,ChunkAccess,StructureManager,long,ChunkPos,Biome)
+ void createStructures(StructureFeatureManager,BiomeManager,ChunkAccess,ChunkGenerator,StructureManager,long)
- void createStructures(StructureFeatureManager,ChunkAccess,StructureManager,long)
- void generateStrongholds()
+ void tickCustomSpawners(ServerLevel,boolean,boolean)
```

</details>





<details>
<summary>
net.minecraft.world.level.chunk.ImposterProtoChunk
</summary>

```diff
- BitSet getOrCreateCarvingMask(GenerationStep$Carving)
```

</details>























<details>
<summary>
net.minecraft.world.level.levelgen.FlatLevelSource
</summary>

```diff
+ Biome getBiomeFromSettings()
+ Biome getCarvingOrDecorationBiome(BiomeManager,BlockPos)
+ BlockPos findNearestMapFeature(ServerLevel,String,BlockPos,int,boolean)
+ boolean canGenerateStructure(StructureFeature)
+ boolean isBiomeValidStartForStructure(Biome,StructureFeature)
- Codec codec()
+ FeatureConfiguration getStructureConfiguration(Biome,StructureFeature)
- FlatLevelGeneratorSettings settings()
- void <clinit>()
+ void tickCustomSpawners(ServerLevel,boolean,boolean)
```

</details>



<details>
<summary>
net.minecraft.world.level.levelgen.carver.ConfiguredWorldCarver
</summary>

```diff
+ ConfiguredWorldCarver deserialize(Dynamic)
+ Dynamic serialize(DynamicOps)
- void <clinit>()
+ void <init>(WorldCarver,Dynamic)
- WorldCarver lambda$static$0(ConfiguredWorldCarver)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.carver.NoneCarverConfiguration
</summary>

```diff
+ Dynamic serialize(DynamicOps)
+ NoneCarverConfiguration deserialize(Dynamic)
- NoneCarverConfiguration lambda$static$0()
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.carver.UnderwaterCaveWorldCarver
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.AbstractHugeMushroomFeature
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.BasaltColumnsFeature
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.BastionFeature$FeatureStart
</summary>

```diff
- void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
- void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,MultiJigsawConfiguration)
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome)
```

</details>



<details>
<summary>
net.minecraft.world.level.levelgen.feature.BlockPileFeature
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.BonusChestFeature
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.BuriedTreasureFeature$BuriedTreasureStart
</summary>

```diff
- void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,BuriedTreasureConfiguration)
- void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.ConfiguredFeature
</summary>

```diff
+ ConfiguredFeature deserialize(Dynamic)
+ Dynamic serialize(DynamicOps)
- Feature lambda$static$0(ConfiguredFeature)
+ void <init>(Feature,Dynamic)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.ReplaceBlobsFeature
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.RuinedPortalFeature
</summary>

```diff
+ int getLookupRange()
+ int getRandomSalt(ChunkGeneratorSettings)
+ int getSeparation(ChunkGeneratorSettings)
+ int getSpacing(ChunkGeneratorSettings)
+ String getFeatureName()
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.RuinedPortalFeature$Type
</summary>

```diff
- String getSerializedName()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.SeaPickleFeature
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.ShipwreckFeature
</summary>

```diff
+ int getLookupRange()
+ int getRandomSalt(ChunkGeneratorSettings)
+ int getSeparation(ChunkGeneratorSettings)
+ int getSpacing(ChunkGeneratorSettings)
+ String getFeatureName()
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.SimpleBlockFeature
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>




<details>
<summary>
net.minecraft.world.level.levelgen.feature.StrongholdFeature
</summary>

```diff
+ BlockPos getNearestGeneratedFeature(ServerLevel,ChunkGenerator,BlockPos,int,boolean)
+ boolean featureChunk(BiomeManager,ChunkGenerator,long,WorldgenRandom,int,int,Biome)
+ boolean isFeatureChunk(BiomeManager,ChunkGenerator,long,WorldgenRandom,int,int,Biome,ChunkPos)
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,FeatureConfiguration)
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,NoneFeatureConfiguration)
+ int getLookupRange()
+ List access$000(StrongholdFeature)
+ String getFeatureName()
- void <init>(Codec)
+ void <init>(Function)
+ void generatePositions(ChunkGenerator,long)
+ void reset()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.StructureFeature
</summary>

```diff
- BlockPos getNearestGeneratedFeature(LevelReader,StructureFeatureManager,BlockPos,int,boolean,long,StructureFeatureConfiguration)
+ BlockPos getNearestGeneratedFeature(ServerLevel,ChunkGenerator,BlockPos,int,boolean)
+ boolean featureChunk(BiomeManager,ChunkGenerator,long,WorldgenRandom,int,int,Biome)
+ boolean isFeatureChunk(BiomeManager,ChunkGenerator,long,WorldgenRandom,int,int,Biome,ChunkPos)
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,FeatureConfiguration)
+ boolean isInsideBoundingFeature(StructureFeatureManager,BlockPos)
+ boolean isInsideFeature(StructureFeatureManager,BlockPos)
+ boolean lambda$getStructureAt$1(BlockPos,StructureStart)
+ boolean lambda$getStructureAt$3(boolean,BlockPos,StructureStart)
+ boolean lambda$null$2(BlockPos,StructurePiece)
+ boolean place(WorldGenLevel,StructureFeatureManager,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
+ boolean supportsProjection()
+ ChunkPos getPotentialFeatureChunk(ChunkGeneratorSettings,long,WorldgenRandom,int,int)
- ChunkPos getPotentialFeatureChunk(StructureFeatureConfiguration,long,WorldgenRandom,int,int)
- Codec configuredStructureCodec()
+ ConfiguredFeature configured(FeatureConfiguration)
- ConfiguredStructureFeature configured(FeatureConfiguration)
- ConfiguredStructureFeature lambda$new$0(FeatureConfiguration)
- FeatureConfiguration lambda$new$1(ConfiguredStructureFeature)
- GenerationStep$Decoration step()
+ int getRandomSalt(ChunkGeneratorSettings)
+ int getSeparation(ChunkGeneratorSettings)
+ int getSpacing(ChunkGeneratorSettings)
- List getSpecialAnimals()
- List getSpecialEnemies()
+ Object lambda$place$0(WorldGenLevel,StructureFeatureManager,ChunkGenerator,Random,int,int,int,int,StructureStart)
- String getFeatureName()
- StructureFeature register(String,StructureFeature,GenerationStep$Decoration)
- StructureStart createStart(int,int,BoundingBox,int,long)
- StructureStart generate(ChunkGenerator,BiomeSource,StructureManager,long,ChunkPos,Biome,int,WorldgenRandom,StructureFeatureConfiguration,FeatureConfiguration)
+ StructureStart getStructureAt(StructureFeatureManager,BlockPos,boolean)
- StructureStart loadStaticStart(StructureManager,CompoundTag,long)
- void <init>(Codec)
+ void <init>(Function)
- void bootstrap()
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.SwamplandHutFeature$FeatureStart
</summary>

```diff
- void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,FeatureConfiguration)
- void generatePieces(ChunkGenerator,StructureManager,int,int,Biome,NoneFeatureConfiguration)
+ void generatePieces(ChunkGenerator,StructureManager,int,int,Biome)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.TreeFeature
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.VillageFeature
</summary>

```diff
+ boolean supportsProjection()
+ int getLookupRange()
+ int getRandomSalt(ChunkGeneratorSettings)
+ int getSeparation(ChunkGeneratorSettings)
+ int getSpacing(ChunkGeneratorSettings)
+ String getFeatureName()
- void <init>(Codec)
+ void <init>(Function)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.VinesFeature
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.WeepingVinesFeature
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.WoodlandMansionFeature
</summary>

```diff
+ boolean isFeatureChunk(BiomeManager,ChunkGenerator,long,WorldgenRandom,int,int,Biome,ChunkPos)
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,FeatureConfiguration)
- boolean isFeatureChunk(ChunkGenerator,BiomeSource,long,WorldgenRandom,int,int,Biome,ChunkPos,NoneFeatureConfiguration)
+ int getLookupRange()
+ int getRandomSalt(ChunkGeneratorSettings)
+ int getSeparation(ChunkGeneratorSettings)
+ int getSpacing(ChunkGeneratorSettings)
+ String getFeatureName()
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.blockplacers.BlockPlacer
</summary>

```diff
- void <clinit>()
- void <init>()
+ void <init>(BlockPlacerType)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.blockplacers.ColumnPlacer
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
- BlockPlacerType type()
- Integer lambda$null$0(ColumnPlacer)
- Integer lambda$null$1(ColumnPlacer)
+ Object serialize(DynamicOps)
- void <clinit>()
+ void <init>(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.blockplacers.SimpleBlockPlacer
</summary>

```diff
- BlockPlacerType type()
+ Object serialize(DynamicOps)
- SimpleBlockPlacer lambda$static$0()
- void <clinit>()
+ void <init>(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.BlockBlobConfiguration
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
+ BlockBlobConfiguration deserialize(Dynamic)
- BlockState lambda$null$0(BlockBlobConfiguration)
+ Dynamic serialize(DynamicOps)
- Integer lambda$null$1(BlockBlobConfiguration)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.BlockStateConfiguration
</summary>

```diff
- BlockState lambda$static$0(BlockStateConfiguration)
+ BlockStateConfiguration deserialize(Dynamic)
+ Dynamic serialize(DynamicOps)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.ChanceRangeDecoratorConfiguration
</summary>

```diff
- App lambda$static$4(RecordCodecBuilder$Instance)
+ ChanceRangeDecoratorConfiguration deserialize(Dynamic)
+ Dynamic serialize(DynamicOps)
- Float lambda$null$0(ChanceRangeDecoratorConfiguration)
- Integer lambda$null$1(ChanceRangeDecoratorConfiguration)
- Integer lambda$null$2(ChanceRangeDecoratorConfiguration)
- Integer lambda$null$3(ChanceRangeDecoratorConfiguration)
- void <clinit>()
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.CountRangeDecoratorConfiguration
</summary>

```diff
- App lambda$static$4(RecordCodecBuilder$Instance)
+ CountRangeDecoratorConfiguration deserialize(Dynamic)
+ Dynamic serialize(DynamicOps)
- Integer lambda$null$0(CountRangeDecoratorConfiguration)
- Integer lambda$null$1(CountRangeDecoratorConfiguration)
- Integer lambda$null$2(CountRangeDecoratorConfiguration)
- Integer lambda$null$3(CountRangeDecoratorConfiguration)
- void <clinit>()
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.EndGatewayConfiguration
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
+ BlockPos lambda$null$1(Number,Number,Number)
- Boolean lambda$null$1(EndGatewayConfiguration)
+ Dynamic serialize(DynamicOps)
+ EndGatewayConfiguration deserialize(Dynamic)
+ Object lambda$serialize$0(DynamicOps,BlockPos)
+ Optional lambda$deserialize$3(Dynamic,Number)
- Optional lambda$null$0(EndGatewayConfiguration)
+ Optional lambda$null$2(Dynamic,Number,Number)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.FeatureRadiusConfiguration
</summary>

```diff
+ Dynamic serialize(DynamicOps)
+ FeatureRadiusConfiguration deserialize(Dynamic)
- Integer lambda$static$0(FeatureRadiusConfiguration)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.JigsawConfiguration
</summary>

```diff
- App lambda$static$0(RecordCodecBuilder$Instance)
+ Dynamic serialize(DynamicOps)
+ JigsawConfiguration deserialize(Dynamic)
- ResourceLocation getStartPool()
+ String getStartPool()
- void <clinit>()
- void <init>(ResourceLocation,int)
+ void <init>(String,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.MineshaftConfiguration
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
- Double lambda$null$0(MineshaftConfiguration)
+ Dynamic serialize(DynamicOps)
+ MineshaftConfiguration deserialize(Dynamic)
- MineshaftFeature$Type lambda$null$1(MineshaftConfiguration)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.NoiseDependantDecoratorConfiguration
</summary>

```diff
- App lambda$static$3(RecordCodecBuilder$Instance)
- Double lambda$null$0(NoiseDependantDecoratorConfiguration)
+ Dynamic serialize(DynamicOps)
- Integer lambda$null$1(NoiseDependantDecoratorConfiguration)
- Integer lambda$null$2(NoiseDependantDecoratorConfiguration)
+ NoiseDependantDecoratorConfiguration deserialize(Dynamic)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.NoneFeatureConfiguration
</summary>

```diff
+ Dynamic serialize(DynamicOps)
+ NoneFeatureConfiguration deserialize(Dynamic)
- NoneFeatureConfiguration lambda$static$0()
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration
</summary>

```diff
- App lambda$static$3(RecordCodecBuilder$Instance)
- BlockState lambda$null$1(OreConfiguration)
+ Dynamic serialize(DynamicOps)
- Integer lambda$null$2(OreConfiguration)
+ OreConfiguration deserialize(Dynamic)
- OreConfiguration$Predicates lambda$null$0(OreConfiguration)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.ProbabilityFeatureConfiguration
</summary>

```diff
- App lambda$static$1(RecordCodecBuilder$Instance)
+ Dynamic serialize(DynamicOps)
- Float lambda$null$0(ProbabilityFeatureConfiguration)
+ ProbabilityFeatureConfiguration deserialize(Dynamic)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.RandomFeatureConfiguration
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
- ConfiguredFeature lambda$null$1(RandomFeatureConfiguration)
+ Dynamic serialize(DynamicOps)
- List lambda$null$0(RandomFeatureConfiguration)
+ Object lambda$serialize$0(DynamicOps,WeightedConfiguredFeature)
+ RandomFeatureConfiguration deserialize(Dynamic)
- void <clinit>()
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.RandomRandomFeatureConfiguration
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
+ Dynamic serialize(DynamicOps)
- Integer lambda$null$1(RandomRandomFeatureConfiguration)
- List lambda$null$0(RandomRandomFeatureConfiguration)
+ Object lambda$serialize$0(DynamicOps,ConfiguredFeature)
+ RandomRandomFeatureConfiguration deserialize(Dynamic)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.ReplaceSpheroidConfiguration
</summary>

```diff
- App lambda$static$4(RecordCodecBuilder$Instance)
- BlockState lambda$null$0(ReplaceSpheroidConfiguration)
- BlockState lambda$null$1(ReplaceSpheroidConfiguration)
+ Dynamic serialize(DynamicOps)
+ ReplaceSpheroidConfiguration deserialize(Dynamic)
- Vec3i lambda$null$2(ReplaceSpheroidConfiguration)
- Vec3i lambda$null$3(ReplaceSpheroidConfiguration)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.RuinedPortalConfiguration
</summary>

```diff
+ Dynamic serialize(DynamicOps)
+ RuinedPortalConfiguration deserialize(Dynamic)
- RuinedPortalFeature$Type lambda$static$0(RuinedPortalConfiguration)
- void <clinit>()
+ void <init>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.ShipwreckConfiguration
</summary>

```diff
- Boolean lambda$static$0(ShipwreckConfiguration)
+ Dynamic serialize(DynamicOps)
+ ShipwreckConfiguration deserialize(Dynamic)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.SimpleRandomFeatureConfiguration
</summary>

```diff
+ Dynamic serialize(DynamicOps)
- List lambda$static$0(SimpleRandomFeatureConfiguration)
+ Object lambda$serialize$0(DynamicOps,ConfiguredFeature)
+ SimpleRandomFeatureConfiguration deserialize(Dynamic)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.SpringConfiguration
</summary>

```diff
- App lambda$static$5(RecordCodecBuilder$Instance)
+ Block lambda$deserialize$0(Dynamic)
- Boolean lambda$null$1(SpringConfiguration)
+ Dynamic serialize(DynamicOps)
- FluidState lambda$null$0(SpringConfiguration)
- Integer lambda$null$2(SpringConfiguration)
- Integer lambda$null$3(SpringConfiguration)
- Set lambda$null$4(SpringConfiguration)
+ SpringConfiguration deserialize(Dynamic)
- void <clinit>()
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.featuresize.FeatureSize
</summary>

```diff
+ Object serialize(DynamicOps)
- Optional lambda$minClippedHeightCodec$1(OptionalInt)
- OptionalInt lambda$minClippedHeightCodec$0(Optional)
- OptionalInt lambda$minClippedHeightCodec$2(FeatureSize)
- RecordCodecBuilder minClippedHeightCodec()
- void <clinit>()
+ void <init>(FeatureSizeType,OptionalInt)
- void <init>(OptionalInt)
+ void lambda$serialize$0(ImmutableMap$Builder,DynamicOps,int)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.featuresize.ThreeLayersFeatureSize
</summary>

```diff
- App lambda$static$5(RecordCodecBuilder$Instance)
- FeatureSizeType type()
- Integer lambda$null$0(ThreeLayersFeatureSize)
- Integer lambda$null$1(ThreeLayersFeatureSize)
- Integer lambda$null$2(ThreeLayersFeatureSize)
- Integer lambda$null$3(ThreeLayersFeatureSize)
- Integer lambda$null$4(ThreeLayersFeatureSize)
+ Object serialize(DynamicOps)
+ OptionalInt lambda$new$0(Number)
- void <clinit>()
+ void <init>(Dynamic)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.BlobFoliagePlacer
</summary>

```diff
- App lambda$static$0(RecordCodecBuilder$Instance)
- FoliagePlacerType type()
- Integer lambda$blobParts$1(BlobFoliagePlacer)
+ Object serialize(DynamicOps)
- Products$P5 blobParts(RecordCodecBuilder$Instance)
- void <clinit>()
+ void <init>(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.DarkOakFoliagePlacer
</summary>

```diff
- App lambda$static$0(RecordCodecBuilder$Instance)
- FoliagePlacerType type()
+ Object serialize(DynamicOps)
- void <clinit>()
+ void <init>(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer
</summary>

```diff
- Integer lambda$foliagePlacerParts$0(FoliagePlacer)
- Integer lambda$foliagePlacerParts$1(FoliagePlacer)
- Integer lambda$foliagePlacerParts$2(FoliagePlacer)
- Integer lambda$foliagePlacerParts$3(FoliagePlacer)
+ Object serialize(DynamicOps)
- Products$P4 foliagePlacerParts(RecordCodecBuilder$Instance)
- void <clinit>()
+ void <init>(int,int,int,int,FoliagePlacerType)
- void <init>(int,int,int,int)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.placement.CarvingMaskDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.ChanceDecoratorConfiguration
</summary>

```diff
+ ChanceDecoratorConfiguration deserialize(Dynamic)
+ Dynamic serialize(DynamicOps)
- Integer lambda$static$0(ChanceDecoratorConfiguration)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.ChanceHeightmapDoubleDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.ChanceTopSolidHeightmapDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.ConfiguredDecorator
</summary>

```diff
+ ConfiguredDecorator deserialize(Dynamic)
+ Dynamic serialize(DynamicOps)
- FeatureDecorator lambda$static$0(ConfiguredDecorator)
- void <clinit>()
+ void <init>(FeatureDecorator,Dynamic)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.CountChanceHeightmapDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.CountDepthAverageDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.CountHeight64Decorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.CountHeightmapDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.CountVeryBiasedRangeDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.DarkOakTreePlacementDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.EmeraldPlacementDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.EndIslandPlacementDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.ForestRockPlacementDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.FrequencyDecoratorConfiguration
</summary>

```diff
+ Dynamic serialize(DynamicOps)
+ FrequencyDecoratorConfiguration deserialize(Dynamic)
- Integer lambda$static$0(FrequencyDecoratorConfiguration)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.IcebergPlacementDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.LakeWaterPlacementDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.NoiseCountFactorDecoratorConfiguration
</summary>

```diff
- App lambda$static$4(RecordCodecBuilder$Instance)
- Double lambda$null$1(NoiseCountFactorDecoratorConfiguration)
- Double lambda$null$2(NoiseCountFactorDecoratorConfiguration)
+ Dynamic serialize(DynamicOps)
- Heightmap$Types lambda$null$3(NoiseCountFactorDecoratorConfiguration)
- Integer lambda$null$0(NoiseCountFactorDecoratorConfiguration)
+ NoiseCountFactorDecoratorConfiguration deserialize(Dynamic)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.NoiseHeightmapDoubleDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.RangeDecoratorConfiguration
</summary>

```diff
- App lambda$static$2(RecordCodecBuilder$Instance)
+ Dynamic serialize(DynamicOps)
- Integer lambda$null$0(RangeDecoratorConfiguration)
- Integer lambda$null$1(RangeDecoratorConfiguration)
+ RangeDecoratorConfiguration deserialize(Dynamic)
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.TopSolidHeightMapDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.TopSolidHeightMapRangeDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.nether.CountRangeDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.nether.LightGemChanceDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.nether.RandomCountRangeDecorator
</summary>

```diff
- void <init>(Codec)
+ void <init>(Function)
```

</details>







<details>
<summary>
net.minecraft.world.level.levelgen.structure.IglooPieces
</summary>

```diff
+ void addPieces(StructureManager,BlockPos,Rotation,List,Random,NoneFeatureConfiguration)
- void addPieces(StructureManager,BlockPos,Rotation,List,Random)
```

</details>















<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherFossilFeature
</summary>

```diff
+ int getLookupRange()
+ int getRandomSalt(ChunkGeneratorSettings)
+ int getSeparation(ChunkGeneratorSettings)
+ int getSpacing(ChunkGeneratorSettings)
+ String getFeatureName()
- void <init>(Codec)
+ void <init>(Function)
```

</details>













<details>
<summary>
net.minecraft.world.level.levelgen.structure.OceanRuinFeature
</summary>

```diff
+ int getLookupRange()
+ int getRandomSalt(ChunkGeneratorSettings)
+ int getSeparation(ChunkGeneratorSettings)
+ int getSpacing(ChunkGeneratorSettings)
+ String getFeatureName()
- void <init>(Codec)
+ void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.OceanRuinFeature$Type
</summary>

```diff
- String getSerializedName()
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.structure.RuinedPortalPiece
</summary>

```diff
- void <clinit>()
- void lambda$addAdditionalSaveData$0(CompoundTag,Tag)
+ void lambda$postProcess$0(Random,WorldGenLevel,BlockPos)
- void lambda$postProcess$1(Random,WorldGenLevel,BlockPos)
```

</details>




























































<details>
<summary>
net.minecraft.world.level.storage.LevelStorageSource
</summary>

```diff
- BiFunction access$800(LevelStorageSource,File,boolean)
- BiFunction levelSummaryReader(File,boolean)
- Gson access$900()
- LevelSummary lambda$levelSummaryReader$0(File,boolean,File,DataFixer)
- Object access$300(LevelStorageSource,File,BiFunction)
- Object readLevelData(File,BiFunction)
- Pair readWorldGenSettings(Dynamic,DataFixer,int)
- WorldData access$1000(File,DataFixer)
+ WorldData access$300(LevelStorageSource,File)
+ WorldData getLevelData(File)
```

</details>

<details>
<summary>
net.minecraft.world.level.storage.LevelSummary
</summary>

```diff
- boolean experimental()
+ long getSizeOnDisk()
- void <init>(LevelSettings,LevelVersion,String,boolean,boolean,File,Lifecycle)
+ void <init>(WorldData,String,String,long,boolean,boolean,File)
- WorldGenSettings worldGenSettings()
```

</details>
</details>