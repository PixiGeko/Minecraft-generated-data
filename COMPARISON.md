## Comparison with [20w10a](https://github.com/PixiGeko/Minecraft-generated-data/tree/20w10a)

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
<table><tr><th></th><th align="left">20w10a</th><th>20w11a</th></tr><tr><td>World version</td><td><code>2512</code></td><td><code>2513</code></td></tr><tr><td>Protocol version</td><td><code>705</code></td><td><code>706</code></td></tr></table>
</details>
<details><summary>Registries</summary>
<details>
<summary>
block.txt
</summary>

```diff
+ minecraft:nether_gold_ore
+ minecraft:twisting_vines
+ minecraft:twisting_vines_plant
```

</details>









<details>
<summary>
enchantment.txt
</summary>

```diff
+ minecraft:soul_speed
```

</details>

<details>
<summary>
feature.txt
</summary>

```diff
+ minecraft:twisting_vines
```

</details>


<details>
<summary>
item.txt
</summary>

```diff
+ minecraft:nether_gold_ore
+ minecraft:twisting_vines
```

</details>




<details>
<summary>
particle_type.txt
</summary>

```diff
+ minecraft:soul
```

</details>







<details>
<summary>
sound_event.txt
</summary>

```diff
+ minecraft:block.vine.step
+ minecraft:particle.soul_escape
```

</details>
</details>
<details><summary>Tags</summary>
<details>
<summary>
all_blocks_with_drop.json
</summary>

```diff
+ minecraft:nether_gold_ore
+ minecraft:twisting_vines
+ minecraft:twisting_vines_plant
```

</details>



<details>
<summary>
all_survival_blocks_without_drop.json
</summary>

```diff
+ minecraft:fire
+ minecraft:soul_fire
```

</details>



<details>
<summary>
universal_tags/block.json
</summary>

```diff
+ minecraft:nether_gold_ore
+ minecraft:twisting_vines
+ minecraft:twisting_vines_plant
```

</details>









<details>
<summary>
universal_tags/enchantment.json
</summary>

```diff
+ minecraft:soul_speed
```

</details>

<details>
<summary>
universal_tags/feature.json
</summary>

```diff
+ minecraft:twisting_vines
```

</details>


<details>
<summary>
universal_tags/item.json
</summary>

```diff
+ minecraft:nether_gold_ore
+ minecraft:twisting_vines
```

</details>




<details>
<summary>
universal_tags/particle_type.json
</summary>

```diff
+ minecraft:soul
```

</details>







<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:block.vine.step
+ minecraft:particle.soul_escape
```

</details>
</details>
<details><summary>Commands</summary>
<details>
<summary>
locate
</summary>

```diff
+ locate Nether_Fossil
```

</details>
</details>
<details><summary>Translations</summary>
<details>
<summary>
Keys
</summary>

```diff
+ block.minecraft.nether_gold_ore: Nether Gold Ore
+ block.minecraft.twisting_vines_plant: Twisting Vines
+ block.minecraft.twisting_vines: Twisting Vines
+ death.fell.accident.scaffolding: %1$s fell off a scaffolding
+ death.fell.accident.twisting_vines: %1$s fell off some twisting vines
+ enchantment.minecraft.soul_speed: Soul Speed
+ subtitles.particle.soul_escape: Soul escapes
```

</details>
</details>
<details><summary>File structure</summary>
<details>
<summary>
data
</summary>

```diff
+ minecraft/loot_tables/blocks/fire.json
+ minecraft/loot_tables/blocks/nether_gold_ore.json
+ minecraft/loot_tables/blocks/soul_fire.json
+ minecraft/loot_tables/blocks/twisting_vines_plant.json
+ minecraft/loot_tables/blocks/twisting_vines.json
+ minecraft/tags/blocks/gold_ores.json
+ minecraft/tags/blocks/soul_speed_blocks.json
+ minecraft/tags/items/gold_ores.json
+ minecraft/tags/items/piglin_repellents.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/blockstates/nether_gold_ore.json
+ minecraft/blockstates/twisting_vines_plant.json
+ minecraft/blockstates/twisting_vines.json
+ minecraft/models/block/nether_gold_ore.json
+ minecraft/models/block/twisting_vines_plant.json
+ minecraft/models/block/twisting_vines.json
+ minecraft/models/item/nether_gold_ore.json
+ minecraft/models/item/twisting_vines.json
+ minecraft/particles/soul.json
+ minecraft/textures/block/nether_gold_ore.png
+ minecraft/textures/block/twisting_vines_plant.png
+ minecraft/textures/block/twisting_vines.png
+ minecraft/textures/particle/soul_0.png
+ minecraft/textures/particle/soul_1.png
+ minecraft/textures/particle/soul_10.png
+ minecraft/textures/particle/soul_2.png
+ minecraft/textures/particle/soul_3.png
+ minecraft/textures/particle/soul_4.png
+ minecraft/textures/particle/soul_5.png
+ minecraft/textures/particle/soul_6.png
+ minecraft/textures/particle/soul_7.png
+ minecraft/textures/particle/soul_8.png
+ minecraft/textures/particle/soul_9.png
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
- net.minecraft.core.dispenser.AbstractProjectileDispenseBehavior
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
- net.minecraft.core.dispenser.DispenseItemBehavior$19
+ net.minecraft.core.dispenser.DispenseItemBehavior$2
- net.minecraft.core.dispenser.DispenseItemBehavior$20
+ net.minecraft.core.dispenser.DispenseItemBehavior$21
- net.minecraft.core.dispenser.DispenseItemBehavior$22
+ net.minecraft.core.dispenser.DispenseItemBehavior$3
- net.minecraft.core.dispenser.DispenseItemBehavior$4
+ net.minecraft.core.dispenser.DispenseItemBehavior$5
- net.minecraft.core.dispenser.DispenseItemBehavior$6
+ net.minecraft.core.dispenser.DispenseItemBehavior$7
- net.minecraft.core.dispenser.DispenseItemBehavior$7$1
+ net.minecraft.core.dispenser.DispenseItemBehavior$8
- net.minecraft.core.dispenser.DispenseItemBehavior$8$1
+ net.minecraft.core.dispenser.DispenseItemBehavior$9
- net.minecraft.core.dispenser.OptionalDispenseItemBehavior
- net.minecraft.core.dispenser.package-info
+ net.minecraft.core.dispenser.ShulkerBoxDispenseBehavior
+ net.minecraft.core.package-info
- net.minecraft.core.particles.BlockParticleOption
+ net.minecraft.core.particles.BlockParticleOption$1
- net.minecraft.core.particles.DustParticleOptions
+ net.minecraft.core.particles.DustParticleOptions$1
- net.minecraft.core.particles.ItemParticleOption
+ net.minecraft.core.particles.ItemParticleOption$1
- net.minecraft.core.particles.package-info
- net.minecraft.core.particles.ParticleOptions
+ net.minecraft.core.particles.ParticleOptions$Deserializer
- net.minecraft.core.particles.ParticleType
+ net.minecraft.core.particles.ParticleTypes
- net.minecraft.core.particles.SimpleParticleType
+ net.minecraft.core.particles.SimpleParticleType$1
+ net.minecraft.core.WritableRegistry
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
- net.minecraft.network.chat.Component
+ net.minecraft.network.chat.Component$1
- net.minecraft.network.chat.Component$Serializer
+ net.minecraft.network.chat.ComponentUtils
- net.minecraft.network.chat.ContextAwareComponent
+ net.minecraft.network.chat.HoverEvent
- net.minecraft.network.chat.HoverEvent$Action
+ net.minecraft.network.chat.KeybindComponent
- net.minecraft.network.chat.NbtComponent
+ net.minecraft.network.chat.NbtComponent$BlockNbtComponent
- net.minecraft.network.chat.NbtComponent$EntityNbtComponent
+ net.minecraft.network.chat.NbtComponent$StorageNbtComponent
- net.minecraft.network.chat.package-info
- net.minecraft.network.chat.ScoreComponent
+ net.minecraft.network.chat.SelectorComponent
- net.minecraft.network.chat.Style
+ net.minecraft.network.chat.Style$1
- net.minecraft.network.chat.Style$Serializer
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
- net.minecraft.network.protocol.game.ClientboundSetSpawnPositionPacket
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
+ net.minecraft.network.protocol.game.package-info
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
+ net.minecraft.network.protocol.game.ServerGamePacketListener
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
- net.minecraft.network.protocol.Packet
+ net.minecraft.network.protocol.PacketFlow
- net.minecraft.network.protocol.PacketUtils
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
+ net.minecraft.network.SkipPacketException
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
- net.minecraft.network.Varint21FrameDecoder
+ net.minecraft.network.Varint21LengthFieldPrepender
+ net.minecraft.obfuscate.DontObfuscateOrShrink
- net.minecraft.obfuscate.KeepAfterObfuscation
+ net.minecraft.obfuscate.package-info
- net.minecraft.package-info
- net.minecraft.recipebook.package-info
+ net.minecraft.recipebook.PlaceRecipe
- net.minecraft.recipebook.ServerPlaceRecipe
+ net.minecraft.recipebook.ServerPlaceSmeltingRecipe
+ net.minecraft.resources.package-info
+ net.minecraft.resources.ResourceLocation
- net.minecraft.resources.ResourceLocation$Serializer
- net.minecraft.server.Bootstrap
+ net.minecraft.server.bossevents.CustomBossEvent
- net.minecraft.server.bossevents.CustomBossEvents
+ net.minecraft.server.bossevents.package-info
+ net.minecraft.server.ChainedJsonException
- net.minecraft.server.ChainedJsonException$1
+ net.minecraft.server.ChainedJsonException$Entry
- net.minecraft.server.commands.AdvancementCommands
+ net.minecraft.server.commands.AdvancementCommands$1
- net.minecraft.server.commands.AdvancementCommands$Action
+ net.minecraft.server.commands.AdvancementCommands$Action$1
- net.minecraft.server.commands.AdvancementCommands$Action$2
+ net.minecraft.server.commands.AdvancementCommands$Mode
- net.minecraft.server.commands.BanIpCommands
+ net.minecraft.server.commands.BanListCommands
- net.minecraft.server.commands.BanPlayerCommands
+ net.minecraft.server.commands.BossBarCommands
- net.minecraft.server.commands.ClearInventoryCommands
+ net.minecraft.server.commands.CloneCommands
- net.minecraft.server.commands.CloneCommands$CloneBlockInfo
+ net.minecraft.server.commands.CloneCommands$Mode
- net.minecraft.server.commands.data.BlockDataAccessor
+ net.minecraft.server.commands.data.BlockDataAccessor$1
- net.minecraft.server.commands.data.DataAccessor
+ net.minecraft.server.commands.data.DataCommands
- net.minecraft.server.commands.data.DataCommands$DataManipulator
+ net.minecraft.server.commands.data.DataCommands$DataManipulatorDecorator
- net.minecraft.server.commands.data.DataCommands$DataProvider
+ net.minecraft.server.commands.data.EntityDataAccessor
- net.minecraft.server.commands.data.EntityDataAccessor$1
+ net.minecraft.server.commands.data.package-info
+ net.minecraft.server.commands.data.StorageDataAccessor
- net.minecraft.server.commands.data.StorageDataAccessor$1
- net.minecraft.server.commands.DataPackCommand
+ net.minecraft.server.commands.DataPackCommand$Inserter
+ net.minecraft.server.commands.DebugCommand
- net.minecraft.server.commands.DebugMobSpawningCommand
+ net.minecraft.server.commands.DebugPathCommand
- net.minecraft.server.commands.DefaultGameModeCommands
- net.minecraft.server.commands.DeOpCommands
+ net.minecraft.server.commands.DifficultyCommand
- net.minecraft.server.commands.EffectCommands
+ net.minecraft.server.commands.EmoteCommands
- net.minecraft.server.commands.EnchantCommand
+ net.minecraft.server.commands.ExecuteCommand
- net.minecraft.server.commands.ExecuteCommand$CommandNumericPredicate
+ net.minecraft.server.commands.ExecuteCommand$CommandPredicate
- net.minecraft.server.commands.ExperienceCommand
+ net.minecraft.server.commands.ExperienceCommand$Type
- net.minecraft.server.commands.FillCommand
+ net.minecraft.server.commands.FillCommand$Mode
- net.minecraft.server.commands.ForceLoadCommand
+ net.minecraft.server.commands.FunctionCommand
- net.minecraft.server.commands.GameModeCommand
+ net.minecraft.server.commands.GameRuleCommand
- net.minecraft.server.commands.GameRuleCommand$1
+ net.minecraft.server.commands.GiveCommand
- net.minecraft.server.commands.HelpCommand
+ net.minecraft.server.commands.KickCommand
- net.minecraft.server.commands.KillCommand
+ net.minecraft.server.commands.ListPlayersCommand
- net.minecraft.server.commands.LocateBiomeCommand
+ net.minecraft.server.commands.LocateCommand
- net.minecraft.server.commands.LootCommand
+ net.minecraft.server.commands.LootCommand$Callback
- net.minecraft.server.commands.LootCommand$DropConsumer
+ net.minecraft.server.commands.LootCommand$TailProvider
- net.minecraft.server.commands.MsgCommand
+ net.minecraft.server.commands.OpCommand
- net.minecraft.server.commands.package-info
- net.minecraft.server.commands.PardonCommand
+ net.minecraft.server.commands.PardonIpCommand
- net.minecraft.server.commands.ParticleCommand
+ net.minecraft.server.commands.PlaySoundCommand
- net.minecraft.server.commands.PublishCommand
+ net.minecraft.server.commands.RaidCommand
- net.minecraft.server.commands.RecipeCommand
+ net.minecraft.server.commands.ReloadCommand
- net.minecraft.server.commands.ReplaceItemCommand
+ net.minecraft.server.commands.SaveAllCommand
- net.minecraft.server.commands.SaveOffCommand
+ net.minecraft.server.commands.SaveOnCommand
- net.minecraft.server.commands.SayCommand
+ net.minecraft.server.commands.ScheduleCommand
- net.minecraft.server.commands.ScoreboardCommand
+ net.minecraft.server.commands.SeedCommand
- net.minecraft.server.commands.SetBlockCommand
+ net.minecraft.server.commands.SetBlockCommand$Filter
- net.minecraft.server.commands.SetBlockCommand$Mode
+ net.minecraft.server.commands.SetPlayerIdleTimeoutCommand
- net.minecraft.server.commands.SetSpawnCommand
+ net.minecraft.server.commands.SetWorldSpawnCommand
- net.minecraft.server.commands.SpectateCommand
+ net.minecraft.server.commands.SpreadPlayersCommand
- net.minecraft.server.commands.SpreadPlayersCommand$Position
+ net.minecraft.server.commands.StopCommand
- net.minecraft.server.commands.StopSoundCommand
+ net.minecraft.server.commands.SummonCommand
- net.minecraft.server.commands.TagCommand
+ net.minecraft.server.commands.TeamCommand
- net.minecraft.server.commands.TeamMsgCommand
+ net.minecraft.server.commands.TeleportCommand
- net.minecraft.server.commands.TeleportCommand$LookAt
+ net.minecraft.server.commands.TellRawCommand
- net.minecraft.server.commands.TimeCommand
+ net.minecraft.server.commands.TitleCommand
- net.minecraft.server.commands.TriggerCommand
+ net.minecraft.server.commands.WeatherCommand
- net.minecraft.server.commands.WhitelistCommand
+ net.minecraft.server.commands.WorldBorderCommand
- net.minecraft.server.ConsoleInput
+ net.minecraft.server.ConsoleInputSource
- net.minecraft.server.DebugLoggedPrintStream
+ net.minecraft.server.dedicated.DedicatedPlayerList
- net.minecraft.server.dedicated.DedicatedServer
+ net.minecraft.server.dedicated.DedicatedServer$1
- net.minecraft.server.dedicated.DedicatedServer$2
+ net.minecraft.server.dedicated.DedicatedServerProperties
- net.minecraft.server.dedicated.DedicatedServerSettings
- net.minecraft.server.dedicated.package-info
+ net.minecraft.server.dedicated.ServerWatchdog
- net.minecraft.server.dedicated.ServerWatchdog$1
+ net.minecraft.server.dedicated.Settings
- net.minecraft.server.dedicated.Settings$1
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
+ net.minecraft.server.level.ChunkHolder$1
- net.minecraft.server.level.ChunkHolder$ChunkLoadingFailure
+ net.minecraft.server.level.ChunkHolder$ChunkLoadingFailure$1
- net.minecraft.server.level.ChunkHolder$FullChunkStatus
+ net.minecraft.server.level.ChunkHolder$LevelChangeListener
- net.minecraft.server.level.ChunkHolder$PlayerProvider
+ net.minecraft.server.level.ChunkMap
- net.minecraft.server.level.ChunkMap$1
+ net.minecraft.server.level.ChunkMap$2
- net.minecraft.server.level.ChunkMap$DistanceManager
+ net.minecraft.server.level.ChunkMap$TrackedEntity
- net.minecraft.server.level.ChunkTaskPriorityQueue
+ net.minecraft.server.level.ChunkTaskPriorityQueueSorter
- net.minecraft.server.level.ChunkTaskPriorityQueueSorter$1
+ net.minecraft.server.level.ChunkTaskPriorityQueueSorter$Message
- net.minecraft.server.level.ChunkTaskPriorityQueueSorter$Release
+ net.minecraft.server.level.ChunkTracker
- net.minecraft.server.level.ColumnPos
+ net.minecraft.server.level.DemoMode
- net.minecraft.server.level.DerivedServerLevel
+ net.minecraft.server.level.DistanceManager
- net.minecraft.server.level.DistanceManager$ChunkTicketTracker
+ net.minecraft.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
- net.minecraft.server.level.DistanceManager$PlayerTicketTracker
+ net.minecraft.server.level.FeatureSimulator
- net.minecraft.server.level.package-info
- net.minecraft.server.level.PlayerMap
+ net.minecraft.server.level.progress.ChunkProgressListener
- net.minecraft.server.level.progress.ChunkProgressListenerFactory
+ net.minecraft.server.level.progress.LoggerChunkProgressListener
- net.minecraft.server.level.progress.package-info
- net.minecraft.server.level.progress.ProcessorChunkProgressListener
+ net.minecraft.server.level.progress.StoringChunkProgressListener
+ net.minecraft.server.level.SectionTracker
- net.minecraft.server.level.ServerBossEvent
+ net.minecraft.server.level.ServerChunkCache
- net.minecraft.server.level.ServerChunkCache$1
+ net.minecraft.server.level.ServerChunkCache$MainThreadExecutor
- net.minecraft.server.level.ServerEntity
+ net.minecraft.server.level.ServerLevel
- net.minecraft.server.level.ServerPlayer
+ net.minecraft.server.level.ServerPlayerGameMode
- net.minecraft.server.level.ThreadedLevelLightEngine
+ net.minecraft.server.level.ThreadedLevelLightEngine$TaskType
- net.minecraft.server.level.Ticket
+ net.minecraft.server.level.TicketType
- net.minecraft.server.level.WorldGenRegion
+ net.minecraft.server.level.WorldGenTickList
- net.minecraft.server.LoggedPrintStream
+ net.minecraft.server.MinecraftServer
- net.minecraft.server.MinecraftServer$1
+ net.minecraft.server.MinecraftServer$2
- net.minecraft.server.MinecraftServer$3
+ net.minecraft.server.network.LegacyQueryHandler
- net.minecraft.server.network.MemoryServerHandshakePacketListenerImpl
+ net.minecraft.server.network.package-info
+ net.minecraft.server.network.ServerConnectionListener
- net.minecraft.server.network.ServerConnectionListener$1
+ net.minecraft.server.network.ServerConnectionListener$2
- net.minecraft.server.network.ServerConnectionListener$LatencySimulator
+ net.minecraft.server.network.ServerGamePacketListenerImpl
- net.minecraft.server.network.ServerGamePacketListenerImpl$1
+ net.minecraft.server.network.ServerHandshakePacketListenerImpl
- net.minecraft.server.network.ServerHandshakePacketListenerImpl$1
+ net.minecraft.server.network.ServerLoginPacketListenerImpl
- net.minecraft.server.network.ServerLoginPacketListenerImpl$1
+ net.minecraft.server.network.ServerLoginPacketListenerImpl$State
- net.minecraft.server.network.ServerStatusPacketListenerImpl
- net.minecraft.server.package-info
+ net.minecraft.server.packs.AbstractResourcePack
- net.minecraft.server.packs.FileResourcePack
+ net.minecraft.server.packs.FolderResourcePack
- net.minecraft.server.packs.metadata.MetadataSectionSerializer
+ net.minecraft.server.packs.metadata.pack.package-info
+ net.minecraft.server.packs.metadata.pack.PackMetadataSection
- net.minecraft.server.packs.metadata.pack.PackMetadataSectionSerializer
- net.minecraft.server.packs.metadata.package-info
- net.minecraft.server.packs.Pack
+ net.minecraft.server.packs.package-info
+ net.minecraft.server.packs.PackType
- net.minecraft.server.packs.repository.FolderRepositorySource
- net.minecraft.server.packs.repository.package-info
+ net.minecraft.server.packs.repository.PackCompatibility
- net.minecraft.server.packs.repository.PackRepository
+ net.minecraft.server.packs.repository.RepositorySource
- net.minecraft.server.packs.repository.ServerPacksSource
+ net.minecraft.server.packs.repository.UnopenedPack
- net.minecraft.server.packs.repository.UnopenedPack$Position
+ net.minecraft.server.packs.repository.UnopenedPack$UnopenedPackConstructor
- net.minecraft.server.packs.ResourcePackFileNotFoundException
+ net.minecraft.server.packs.resources.FallbackResourceManager
- net.minecraft.server.packs.resources.FallbackResourceManager$LeakedResourceWarningInputStream
- net.minecraft.server.packs.resources.package-info
+ net.minecraft.server.packs.resources.PreparableReloadListener
- net.minecraft.server.packs.resources.PreparableReloadListener$PreparationBarrier
+ net.minecraft.server.packs.resources.ProfiledReloadInstance
- net.minecraft.server.packs.resources.ProfiledReloadInstance$1
+ net.minecraft.server.packs.resources.ProfiledReloadInstance$State
+ net.minecraft.server.packs.resources.ReloadableResourceManager
- net.minecraft.server.packs.resources.ReloadInstance
- net.minecraft.server.packs.resources.Resource
+ net.minecraft.server.packs.resources.ResourceManager
- net.minecraft.server.packs.resources.ResourceManagerReloadListener
+ net.minecraft.server.packs.resources.SimpleJsonResourceReloadListener
- net.minecraft.server.packs.resources.SimplePreparableReloadListener
- net.minecraft.server.packs.resources.SimpleReloadableResourceManager
+ net.minecraft.server.packs.resources.SimpleReloadableResourceManager$FailingReloadInstance
- net.minecraft.server.packs.resources.SimpleReloadableResourceManager$ResourcePackLoadingFailure
+ net.minecraft.server.packs.resources.SimpleReloadInstance
- net.minecraft.server.packs.resources.SimpleReloadInstance$1
+ net.minecraft.server.packs.resources.SimpleReloadInstance$StateFactory
+ net.minecraft.server.packs.resources.SimpleResource
+ net.minecraft.server.packs.VanillaPack
+ net.minecraft.server.PlayerAdvancements
- net.minecraft.server.PlayerAdvancements$1
+ net.minecraft.server.players.BanListEntry
- net.minecraft.server.players.GameProfileCache
+ net.minecraft.server.players.GameProfileCache$1
- net.minecraft.server.players.GameProfileCache$2
+ net.minecraft.server.players.GameProfileCache$GameProfileInfo
- net.minecraft.server.players.GameProfileCache$Serializer
+ net.minecraft.server.players.IpBanList
- net.minecraft.server.players.IpBanListEntry
+ net.minecraft.server.players.OldUsersConverter
- net.minecraft.server.players.OldUsersConverter$1
+ net.minecraft.server.players.OldUsersConverter$2
- net.minecraft.server.players.OldUsersConverter$3
+ net.minecraft.server.players.OldUsersConverter$4
- net.minecraft.server.players.OldUsersConverter$5
+ net.minecraft.server.players.OldUsersConverter$ConversionError
- net.minecraft.server.players.package-info
- net.minecraft.server.players.PlayerList
+ net.minecraft.server.players.PlayerList$1
- net.minecraft.server.players.ServerOpList
+ net.minecraft.server.players.ServerOpListEntry
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
+ net.minecraft.server.RunningOnDifferentThreadException
- net.minecraft.server.ServerAdvancementManager
+ net.minecraft.server.ServerFunctionManager
- net.minecraft.server.ServerFunctionManager$QueuedCommand
+ net.minecraft.server.ServerInterface
- net.minecraft.server.ServerScoreboard
+ net.minecraft.server.ServerScoreboard$Method
- net.minecraft.server.TickTask
- net.minecraft.sounds.package-info
+ net.minecraft.sounds.SoundEvent
- net.minecraft.sounds.SoundEvents
+ net.minecraft.sounds.SoundSource
+ net.minecraft.stats.package-info
+ net.minecraft.stats.RecipeBook
- net.minecraft.stats.ServerRecipeBook
+ net.minecraft.stats.ServerStatsCounter
- net.minecraft.stats.Stat
+ net.minecraft.stats.StatFormatter
+ net.minecraft.stats.Stats
- net.minecraft.stats.StatsCounter
- net.minecraft.stats.StatType
- net.minecraft.tags.BlockTags
+ net.minecraft.tags.BlockTags$Wrapper
- net.minecraft.tags.EntityTypeTags
+ net.minecraft.tags.EntityTypeTags$Wrapper
- net.minecraft.tags.FluidTags
+ net.minecraft.tags.FluidTags$Wrapper
- net.minecraft.tags.ItemTags
+ net.minecraft.tags.ItemTags$Wrapper
+ net.minecraft.tags.package-info
- net.minecraft.tags.SynchronizableTagCollection
+ net.minecraft.tags.Tag
- net.minecraft.tags.Tag$Builder
+ net.minecraft.tags.Tag$Entry
- net.minecraft.tags.Tag$TagEntry
+ net.minecraft.tags.Tag$ValuesEntry
- net.minecraft.tags.TagCollection
+ net.minecraft.tags.TagManager
- net.minecraft.tags.TagManager$Preparations
- net.minecraft.util.BitStorage
+ net.minecraft.util.BlockFinder
+ net.minecraft.world.item.enchantment.package-info
- net.minecraft.world.item.enchantment.SoulSpeedEnchantment
+ net.minecraft.world.item.enchantment.SweepingEdgeEnchantment
- net.minecraft.world.item.enchantment.ThornsEnchantment
+ net.minecraft.world.item.enchantment.TridentChannelingEnchantment
- net.minecraft.world.item.enchantment.TridentImpalerEnchantment
+ net.minecraft.world.item.enchantment.TridentLoyaltyEnchantment
- net.minecraft.world.item.enchantment.TridentRiptideEnchantment
+ net.minecraft.world.item.enchantment.UntouchingEnchantment
- net.minecraft.world.item.enchantment.VanishingCurseEnchantment
+ net.minecraft.world.item.enchantment.WaterWalkerEnchantment
- net.minecraft.world.item.enchantment.WaterWorkerEnchantment
- net.minecraft.world.item.package-info
+ net.minecraft.world.item.trading.Merchant
- net.minecraft.world.item.trading.MerchantOffer
+ net.minecraft.world.item.trading.MerchantOffers
- net.minecraft.world.item.trading.package-info
+ net.minecraft.world.level.BaseCommandBlock
- net.minecraft.world.level.BaseSpawner
- net.minecraft.world.level.biome.AmbientParticleSettings
+ net.minecraft.world.level.biome.BadlandsBiome
- net.minecraft.world.level.biome.BadlandsPlateauBiome
+ net.minecraft.world.level.biome.BambooJungleBiome
- net.minecraft.world.level.biome.BambooJungleHillsBiome
+ net.minecraft.world.level.biome.BeachBiome
- net.minecraft.world.level.biome.Biome
+ net.minecraft.world.level.biome.Biome$1
- net.minecraft.world.level.biome.Biome$BiomeBuilder
+ net.minecraft.world.level.biome.Biome$BiomeCategory
- net.minecraft.world.level.biome.Biome$BiomeTempCategory
+ net.minecraft.world.level.biome.Biome$ClimateParameters
- net.minecraft.world.level.biome.Biome$Precipitation
+ net.minecraft.world.level.biome.Biome$SpawnerData
- net.minecraft.world.level.biome.BiomeDefaultFeatures
+ net.minecraft.world.level.biome.BiomeManager
- net.minecraft.world.level.biome.BiomeManager$NoiseBiomeSource
- net.minecraft.world.level.biome.Biomes
+ net.minecraft.world.level.biome.BiomeSource
- net.minecraft.world.level.biome.BiomeSourceSettings
+ net.minecraft.world.level.biome.BiomeSourceType
- net.minecraft.world.level.biome.BiomeSpecialEffects
+ net.minecraft.world.level.biome.BiomeSpecialEffects$1
- net.minecraft.world.level.biome.BiomeSpecialEffects$Builder
+ net.minecraft.world.level.biome.BiomeZoomer
+ net.minecraft.world.level.biome.BirchForestBiome
- net.minecraft.world.level.biome.BirchForestHillsBiome
+ net.minecraft.world.level.biome.CheckerboardBiomeSourceSettings
- net.minecraft.world.level.biome.CheckerboardColumnBiomeSource
+ net.minecraft.world.level.biome.ColdOceanBiome
- net.minecraft.world.level.biome.CrimsonForestBiome
+ net.minecraft.world.level.biome.DarkForestBiome
- net.minecraft.world.level.biome.DarkForestHillsBiome
+ net.minecraft.world.level.biome.DeepColdOceanBiome
- net.minecraft.world.level.biome.DeepFrozenOceanBiome
+ net.minecraft.world.level.biome.DeepLukeWarmOceanBiome
- net.minecraft.world.level.biome.DeepOceanBiome
+ net.minecraft.world.level.biome.DeepWarmOceanBiome
- net.minecraft.world.level.biome.DesertBiome
+ net.minecraft.world.level.biome.DesertHillsBiome
- net.minecraft.world.level.biome.DesertLakesBiome
+ net.minecraft.world.level.biome.EndBarrensBiome
- net.minecraft.world.level.biome.EndHighlandsBiome
+ net.minecraft.world.level.biome.EndMidlandsBiome
- net.minecraft.world.level.biome.ErodedBadlandsBiome
+ net.minecraft.world.level.biome.FixedBiomeSource
- net.minecraft.world.level.biome.FixedBiomeSourceSettings
+ net.minecraft.world.level.biome.ForestBiome
- net.minecraft.world.level.biome.ForestFlowerBiome
+ net.minecraft.world.level.biome.FrozenOceanBiome
- net.minecraft.world.level.biome.FrozenRiverBiome
+ net.minecraft.world.level.biome.FuzzyOffsetBiomeZoomer
- net.minecraft.world.level.biome.FuzzyOffsetConstantColumnBiomeZoomer
+ net.minecraft.world.level.biome.GiantSpruceTaigaBiome
- net.minecraft.world.level.biome.GiantSpruceTaigaHillsMutatedBiome
+ net.minecraft.world.level.biome.GiantTreeTaigaBiome
- net.minecraft.world.level.biome.GiantTreeTaigaHillsBiome
+ net.minecraft.world.level.biome.GravellyMountainsBiome
- net.minecraft.world.level.biome.IceSpikesBiome
+ net.minecraft.world.level.biome.JungleBiome
- net.minecraft.world.level.biome.JungleEdgeBiome
+ net.minecraft.world.level.biome.JungleHillsBiome
- net.minecraft.world.level.biome.LukeWarmOceanBiome
+ net.minecraft.world.level.biome.ModifiedBadlandsPlateauBiome
- net.minecraft.world.level.biome.ModifiedGravellyMountainsBiome
+ net.minecraft.world.level.biome.ModifiedJungleBiome
- net.minecraft.world.level.biome.ModifiedJungleEdgeBiome
+ net.minecraft.world.level.biome.ModifiedWoodedBadlandsPlateauBiome
- net.minecraft.world.level.biome.MountainBiome
+ net.minecraft.world.level.biome.MountainEdgeBiome
- net.minecraft.world.level.biome.MultiNoiseBiomeSource
+ net.minecraft.world.level.biome.MultiNoiseBiomeSourceSettings
- net.minecraft.world.level.biome.MushroomFieldsBiome
+ net.minecraft.world.level.biome.MushroomFieldsShoreBiome
- net.minecraft.world.level.biome.NearestNeighborBiomeZoomer
+ net.minecraft.world.level.biome.NetherWastesBiome
- net.minecraft.world.level.biome.OceanBiome
+ net.minecraft.world.level.biome.OverworldBiomeSource
- net.minecraft.world.level.biome.OverworldBiomeSourceSettings
+ net.minecraft.world.level.biome.package-info
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
- net.minecraft.world.level.biome.TheEndBiomeSourceSettings
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
+ net.minecraft.world.level.block.BeaconBeamBlock
- net.minecraft.world.level.block.BeaconBlock
+ net.minecraft.world.level.block.BedBlock
- net.minecraft.world.level.block.BedBlock$1
+ net.minecraft.world.level.block.BedrockBlock
- net.minecraft.world.level.block.BeehiveBlock
+ net.minecraft.world.level.block.BeetrootBlock
- net.minecraft.world.level.block.BellBlock
+ net.minecraft.world.level.block.BellBlock$1
- net.minecraft.world.level.block.BlastFurnaceBlock
+ net.minecraft.world.level.block.Block
- net.minecraft.world.level.block.Block$1
+ net.minecraft.world.level.block.Block$2
- net.minecraft.world.level.block.Block$3
+ net.minecraft.world.level.block.Block$BlockStatePairKey
- net.minecraft.world.level.block.Block$OffsetType
+ net.minecraft.world.level.block.Block$Properties
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
- net.minecraft.world.level.block.GoldBlock
+ net.minecraft.world.level.block.GrassBlock
- net.minecraft.world.level.block.GrassPathBlock
+ net.minecraft.world.level.block.GravelBlock
- net.minecraft.world.level.block.GrindstoneBlock
+ net.minecraft.world.level.block.GrindstoneBlock$1
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
- net.minecraft.world.level.block.LogBlock
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
+ net.minecraft.world.level.block.NetherSproutsBlock
- net.minecraft.world.level.block.NetherVines
- net.minecraft.world.level.block.TwistingVinesPlant
+ net.minecraft.world.level.BlockAndTintGetter
- net.minecraft.world.level.BlockEventData
+ net.minecraft.world.level.BlockGetter
- net.minecraft.world.level.ChunkPos
+ net.minecraft.world.level.ChunkPos$1
- net.minecraft.world.level.ChunkTickList
+ net.minecraft.world.level.ClipContext
- net.minecraft.world.level.ClipContext$Block
+ net.minecraft.world.level.ClipContext$Fluid
- net.minecraft.world.level.ClipContext$ShapeGetter
+ net.minecraft.world.level.CollisionGetter
- net.minecraft.world.level.CollisionGetter$1
+ net.minecraft.world.level.ColorResolver
- net.minecraft.world.level.CustomSpawner
+ net.minecraft.world.level.EmptyBlockGetter
- net.minecraft.world.level.EmptyTickList
+ net.minecraft.world.level.EntityGetter
- net.minecraft.world.level.Explosion
+ net.minecraft.world.level.Explosion$BlockInteraction
- net.minecraft.world.level.FoliageColor
+ net.minecraft.world.level.ForcedChunksSavedData
- net.minecraft.world.level.GameRules
+ net.minecraft.world.level.GameRules$1
- net.minecraft.world.level.GameRules$BooleanValue
+ net.minecraft.world.level.GameRules$GameRuleTypeVisitor
- net.minecraft.world.level.GameRules$IntegerValue
+ net.minecraft.world.level.GameRules$Key
- net.minecraft.world.level.GameRules$Type
+ net.minecraft.world.level.GameRules$Value
- net.minecraft.world.level.GameType
+ net.minecraft.world.level.GrassColor
- net.minecraft.world.level.ItemLike
+ net.minecraft.world.level.Level
- net.minecraft.world.level.LevelAccessor
+ net.minecraft.world.level.LevelConflictException
- net.minecraft.world.level.levelgen.carver.CanyonWorldCarver
+ net.minecraft.world.level.levelgen.carver.CarverConfiguration
- net.minecraft.world.level.levelgen.carver.CaveWorldCarver
+ net.minecraft.world.level.levelgen.carver.ConfiguredWorldCarver
- net.minecraft.world.level.levelgen.carver.NetherWorldCarver
+ net.minecraft.world.level.levelgen.carver.NoneCarverConfiguration
+ net.minecraft.world.level.levelgen.carver.package-info
- net.minecraft.world.level.levelgen.carver.UnderwaterCanyonWorldCarver
+ net.minecraft.world.level.levelgen.carver.UnderwaterCaveWorldCarver
- net.minecraft.world.level.levelgen.carver.WorldCarver
- net.minecraft.world.level.levelgen.ChunkGeneratorProvider
+ net.minecraft.world.level.levelgen.ChunkGeneratorSettings
- net.minecraft.world.level.levelgen.DebugGeneratorSettings
+ net.minecraft.world.level.levelgen.DebugLevelSource
- net.minecraft.world.level.levelgen.feature.AbstractFlowerFeature
+ net.minecraft.world.level.levelgen.feature.AbstractHugeMushroomFeature
- net.minecraft.world.level.levelgen.feature.AbstractSmallTreeFeature
+ net.minecraft.world.level.levelgen.feature.AbstractTreeFeature
- net.minecraft.world.level.levelgen.feature.AcaciaFeature
+ net.minecraft.world.level.levelgen.feature.BambooFeature
- net.minecraft.world.level.levelgen.feature.BasaltPillarFeature
+ net.minecraft.world.level.levelgen.feature.BlockBlobFeature
- net.minecraft.world.level.levelgen.feature.BlockPileFeature
+ net.minecraft.world.level.levelgen.feature.BlueIceFeature
- net.minecraft.world.level.levelgen.feature.BonusChestFeature
+ net.minecraft.world.level.levelgen.feature.BuriedTreasureFeature
- net.minecraft.world.level.levelgen.feature.BuriedTreasureFeature$BuriedTreasureStart
+ net.minecraft.world.level.levelgen.feature.ChorusPlantFeature
- net.minecraft.world.level.levelgen.feature.ConfiguredFeature
+ net.minecraft.world.level.levelgen.feature.CoralClawFeature
- net.minecraft.world.level.levelgen.feature.CoralFeature
+ net.minecraft.world.level.levelgen.feature.CoralMushroomFeature
- net.minecraft.world.level.levelgen.feature.CoralTreeFeature
+ net.minecraft.world.level.levelgen.feature.DarkOakFeature
- net.minecraft.world.level.levelgen.feature.DecoratedFeature
+ net.minecraft.world.level.levelgen.feature.DecoratedFlowerFeature
- net.minecraft.world.level.levelgen.feature.DefaultFlowerFeature
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
+ net.minecraft.world.level.levelgen.feature.FancyTreeFeature
- net.minecraft.world.level.levelgen.feature.FancyTreeFeature$FoliageCoords
+ net.minecraft.world.level.levelgen.feature.Feature
- net.minecraft.world.level.levelgen.feature.FillLayerFeature
+ net.minecraft.world.level.levelgen.feature.FossilFeature
- net.minecraft.world.level.levelgen.feature.GlowstoneFeature
+ net.minecraft.world.level.levelgen.feature.GroundBushFeature
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
+ net.minecraft.world.level.levelgen.feature.MegaJungleTreeFeature
- net.minecraft.world.level.levelgen.feature.MegaPineTreeFeature
+ net.minecraft.world.level.levelgen.feature.MegaTreeFeature
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
- net.minecraft.world.level.levelgen.feature.PillagerOutpostFeature
+ net.minecraft.world.level.levelgen.feature.PillagerOutpostFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.PlainVillagePools
+ net.minecraft.world.level.levelgen.feature.RandomBooleanSelectorFeature
- net.minecraft.world.level.levelgen.feature.RandomPatchFeature
+ net.minecraft.world.level.levelgen.feature.RandomRandomFeature
- net.minecraft.world.level.levelgen.feature.RandomScatteredFeature
+ net.minecraft.world.level.levelgen.feature.RandomSelectorFeature
- net.minecraft.world.level.levelgen.feature.ReplaceBlockFeature
+ net.minecraft.world.level.levelgen.feature.SavannaVillagePools
+ net.minecraft.world.level.levelgen.feature.SeagrassFeature
- net.minecraft.world.level.levelgen.feature.SeaPickleFeature
- net.minecraft.world.level.levelgen.feature.ShipwreckFeature
+ net.minecraft.world.level.levelgen.feature.ShipwreckFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.SimpleBlockFeature
+ net.minecraft.world.level.levelgen.feature.SimpleRandomSelectorFeature
- net.minecraft.world.level.levelgen.feature.SimulatedFeature
+ net.minecraft.world.level.levelgen.feature.SnowAndFreezeFeature
- net.minecraft.world.level.levelgen.feature.SnowyVillagePools
+ net.minecraft.world.level.levelgen.feature.SpikeFeature
- net.minecraft.world.level.levelgen.feature.SpikeFeature$1
+ net.minecraft.world.level.levelgen.feature.SpikeFeature$EndSpike
- net.minecraft.world.level.levelgen.feature.SpikeFeature$SpikeCacheLoader
+ net.minecraft.world.level.levelgen.feature.SpringFeature
- net.minecraft.world.level.levelgen.feature.StrongholdFeature
+ net.minecraft.world.level.levelgen.feature.StrongholdFeature$StrongholdStart
- net.minecraft.world.level.levelgen.feature.StructureFeature
+ net.minecraft.world.level.levelgen.feature.StructureFeature$StructureStartFactory
- net.minecraft.world.level.levelgen.feature.StructurePieceType
+ net.minecraft.world.level.levelgen.feature.SwamplandHutFeature
- net.minecraft.world.level.levelgen.feature.SwamplandHutFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.TaigaVillagePools
- net.minecraft.world.level.levelgen.feature.TreeFeature
- net.minecraft.world.level.levelgen.FlatLevelSource
+ net.minecraft.world.level.levelgen.FlatLevelSource$FlatLevelBiomeWrapper
- net.minecraft.world.level.levelgen.GenerationStep
+ net.minecraft.world.level.levelgen.GenerationStep$Carving
- net.minecraft.world.level.levelgen.GenerationStep$Decoration
+ net.minecraft.world.level.levelgen.Heightmap
- net.minecraft.world.level.levelgen.Heightmap$Types
+ net.minecraft.world.level.levelgen.Heightmap$Usage
- net.minecraft.world.level.levelgen.NetherGeneratorSettings
+ net.minecraft.world.level.levelgen.NetherLevelSource
- net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator
+ net.minecraft.world.level.levelgen.OverworldGeneratorSettings
- net.minecraft.world.level.levelgen.OverworldLevelSource
+ net.minecraft.world.level.levelgen.PatrolSpawner
- net.minecraft.world.level.levelgen.PhantomSpawner
+ net.minecraft.world.level.levelgen.TheEndGeneratorSettings
- net.minecraft.world.level.levelgen.TheEndLevelSource
+ net.minecraft.world.level.levelgen.WorldgenRandom
- net.minecraft.world.level.LevelReader
+ net.minecraft.world.level.LevelSettings
+ net.minecraft.world.level.LevelSimulatedReader
- net.minecraft.world.level.LevelSimulatedRW
- net.minecraft.world.level.LevelType
+ net.minecraft.world.level.LevelWriter
- net.minecraft.world.level.LightLayer
+ net.minecraft.world.level.NaturalSpawner
- net.minecraft.world.level.NaturalSpawner$1
+ net.minecraft.world.level.PathNavigationRegion
- net.minecraft.world.level.PortalForcer
+ net.minecraft.world.level.ServerTickList
- net.minecraft.world.level.SpawnData
+ net.minecraft.world.level.TickList
- net.minecraft.world.level.TickNextTickData
+ net.minecraft.world.level.TickPriority
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.minecraft.core.BlockPos +5M -1M
```
```
XXX.minecraft.core.BlockPos$2 +4P -5P
```
```
XXX.minecraft.core.Vec3i -2M
```
```
XXX.datafix.fixes.RenameBiomesFix +1M -1M | +1P
```
```
XXX.world.entity.Entity +1M | -3P
```
```
XXX.ai.behavior.BehaviorUtils +2M -1M
```
```
XXX.ai.behavior.CrossbowAttack -1P
```
```
XXX.ai.behavior.MeleeAttack +4M -2M | -1P
```
```
XXX.ai.behavior.SetWalkTargetFromAttackTargetIfTargetOutOfReach +2M -4M
```
```
XXX.entity.monster.AbstractSkeleton +1M
```
```
XXX.entity.monster.Pillager +1M
```
```
XXX.monster.hoglin.HoglinAi +2M -1M
```
```
XXX.entity.projectile.AbstractArrow -1P
```
```
XXX.item.enchantment.Enchantment +2M
```
```
XXX.item.enchantment.Enchantments +1P
```
```
XXX.level.block.SnowLayerBlock +1M
```
```
XXX.level.block.SoulSandBlock +1M
```
```
XXX.level.block.WeepingVinesPlant -2M | -1P
```
```
XXX.state.properties.BlockStateProperties +1P
```
```
XXX.level.chunk.ChunkGeneratorType +1M -1M
```

</details>




















































































































































<details>
<summary>
net.minecraft.core.BlockPos
</summary>

```diff
- Iterable withinManhattan(BlockPos,int,int,int)
+ Iterator lambda$betweenClosed$3(int,int,int,int,int,int)
- Iterator lambda$betweenClosed$4(int,int,int,int,int,int)
- Iterator lambda$withinManhattan$3(int,int,int,int,BlockPos)
- Optional findClosestMatch(BlockPos,int,int,Predicate)
- Stream withinManhattanStream(BlockPos,int,int,int)
```

</details>

















<details>
<summary>
net.minecraft.core.Vec3i
</summary>

```diff
+ Iterable between(Vec3i,Vec3i)
+ Iterator lambda$between$0(Vec3i,Vec3i)
```

</details>











































































<details>
<summary>
net.minecraft.util.datafix.fixes.RenameBiomesFix
</summary>

```diff
+ void <init>(Schema,boolean,Map)
- void <init>(Schema,boolean,String,Map)
```

</details>










































































<details>
<summary>
net.minecraft.world.entity.Entity
</summary>

```diff
- BlockState getBlockStateOn()
```

</details>


























<details>
<summary>
net.minecraft.world.entity.ai.behavior.BehaviorUtils
</summary>

```diff
+ boolean isAttackTargetVisibleAndInRange(LivingEntity,double)
- boolean isWithinAttackRange(Mob,LivingEntity,int)
- boolean isWithinMeleeAttackRange(LivingEntity,LivingEntity)
```

</details>














<details>
<summary>
net.minecraft.world.entity.ai.behavior.MeleeAttack
</summary>

```diff
- boolean isHoldingUsableProjectileWeapon(Mob)
+ boolean lambda$checkExtraStartConditions$0(Item)
- boolean lambda$isHoldingUsableProjectileWeapon$0(Mob,Item)
- LivingEntity getAttackTarget(Mob)
+ void <init>(double,int)
- void <init>(int)
```

</details>









<details>
<summary>
net.minecraft.world.entity.ai.behavior.SetWalkTargetFromAttackTargetIfTargetOutOfReach
</summary>

```diff
+ double getAttackRange(ItemStack)
+ double getAttackRange(LivingEntity)
+ LivingEntity getAttackTarget(LivingEntity)
- void setWalkAndLookTarget(LivingEntity,LivingEntity)
+ void setWalkTarget(LivingEntity,LivingEntity)
- void start(ServerLevel,Mob,long)
```

</details>



















































































































































































<details>
<summary>
net.minecraft.world.entity.monster.AbstractSkeleton
</summary>

```diff
- boolean canFireProjectileWeapon(ProjectileWeaponItem)
```

</details>




























<details>
<summary>
net.minecraft.world.entity.monster.Pillager
</summary>

```diff
- boolean canFireProjectileWeapon(ProjectileWeaponItem)
```

</details>


























<details>
<summary>
net.minecraft.world.entity.monster.hoglin.HoglinAi
</summary>

```diff
+ boolean hoglinsOutnumberPiglins(Hoglin)
- boolean piglinsOutnumberHoglins(Hoglin)
- boolean wantsToStopFleeing(Hoglin)
```

</details>

































































































































































































<details>
<summary>
net.minecraft.world.item.enchantment.Enchantment
</summary>

```diff
- boolean isDiscoverable()
- boolean isTradeable()
```

</details>









































<details>
<summary>
net.minecraft.world.level.block.SnowLayerBlock
</summary>

```diff
- VoxelShape getBlockSupportShape(BlockState,BlockGetter,BlockPos)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.SoulSandBlock
</summary>

```diff
- VoxelShape getBlockSupportShape(BlockState,BlockGetter,BlockPos)
```

</details>





















<details>
<summary>
net.minecraft.world.level.block.WeepingVinesPlant
</summary>

```diff
+ void <clinit>()
+ VoxelShape getShape(BlockState,BlockGetter,BlockPos,CollisionContext)
```

</details>










































































<details>
<summary>
net.minecraft.world.level.chunk.ChunkGeneratorType
</summary>

```diff
+ ChunkGenerator create(Level,BiomeSource,ChunkGeneratorSettings)
- ChunkGenerator create(LevelAccessor,BiomeSource,ChunkGeneratorSettings)
```

</details>























































































































































































































































































































































































































<h2>Client</h2>
<details>
<summary>
Classes
</summary>

```diff
- net.minecraft.client.particle.SimpleAnimatedParticle
+ net.minecraft.client.particle.SingleQuadParticle
- net.minecraft.client.particle.SmokeParticle
+ net.minecraft.client.particle.SmokeParticle$Provider
- net.minecraft.client.particle.SoulParticle
- net.minecraft.client.particle.SoulParticle$Provider
- net.minecraft.core.dispenser.AbstractProjectileDispenseBehavior
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
- net.minecraft.core.dispenser.DispenseItemBehavior$19
+ net.minecraft.core.dispenser.DispenseItemBehavior$2
- net.minecraft.core.dispenser.DispenseItemBehavior$20
+ net.minecraft.core.dispenser.DispenseItemBehavior$21
- net.minecraft.core.dispenser.DispenseItemBehavior$22
+ net.minecraft.core.dispenser.DispenseItemBehavior$3
- net.minecraft.core.dispenser.DispenseItemBehavior$4
+ net.minecraft.core.dispenser.DispenseItemBehavior$5
- net.minecraft.core.dispenser.DispenseItemBehavior$6
+ net.minecraft.core.dispenser.DispenseItemBehavior$7
- net.minecraft.core.dispenser.DispenseItemBehavior$7$1
+ net.minecraft.core.dispenser.DispenseItemBehavior$8
- net.minecraft.core.dispenser.DispenseItemBehavior$8$1
+ net.minecraft.core.dispenser.DispenseItemBehavior$9
- net.minecraft.core.dispenser.OptionalDispenseItemBehavior
- net.minecraft.core.dispenser.package-info
+ net.minecraft.core.dispenser.ShulkerBoxDispenseBehavior
+ net.minecraft.core.package-info
- net.minecraft.core.particles.BlockParticleOption
+ net.minecraft.core.particles.BlockParticleOption$1
- net.minecraft.core.particles.DustParticleOptions
+ net.minecraft.core.particles.DustParticleOptions$1
- net.minecraft.core.particles.ItemParticleOption
+ net.minecraft.core.particles.ItemParticleOption$1
- net.minecraft.core.particles.package-info
- net.minecraft.core.particles.ParticleOptions
+ net.minecraft.core.particles.ParticleOptions$Deserializer
- net.minecraft.core.particles.ParticleType
+ net.minecraft.core.particles.ParticleTypes
- net.minecraft.core.particles.SimpleParticleType
+ net.minecraft.core.particles.SimpleParticleType$1
+ net.minecraft.core.WritableRegistry
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
- net.minecraft.network.chat.Component
+ net.minecraft.network.chat.Component$1
- net.minecraft.network.chat.Component$Serializer
+ net.minecraft.network.chat.ComponentUtils
- net.minecraft.network.chat.ContextAwareComponent
+ net.minecraft.network.chat.HoverEvent
- net.minecraft.network.chat.HoverEvent$Action
+ net.minecraft.network.chat.KeybindComponent
- net.minecraft.network.chat.NbtComponent
+ net.minecraft.network.chat.NbtComponent$BlockNbtComponent
- net.minecraft.network.chat.NbtComponent$EntityNbtComponent
+ net.minecraft.network.chat.NbtComponent$StorageNbtComponent
- net.minecraft.network.chat.package-info
- net.minecraft.network.chat.ScoreComponent
+ net.minecraft.network.chat.SelectorComponent
- net.minecraft.network.chat.Style
+ net.minecraft.network.chat.Style$1
- net.minecraft.network.chat.Style$Serializer
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
- net.minecraft.network.protocol.game.ClientboundSetSpawnPositionPacket
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
+ net.minecraft.network.protocol.game.package-info
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
+ net.minecraft.network.protocol.game.ServerGamePacketListener
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
- net.minecraft.network.protocol.Packet
+ net.minecraft.network.protocol.PacketFlow
- net.minecraft.network.protocol.PacketUtils
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
+ net.minecraft.network.SkipPacketException
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
- net.minecraft.network.Varint21FrameDecoder
+ net.minecraft.network.Varint21LengthFieldPrepender
+ net.minecraft.obfuscate.DontObfuscateOrShrink
- net.minecraft.obfuscate.KeepAfterObfuscation
+ net.minecraft.obfuscate.package-info
- net.minecraft.package-info
+ net.minecraft.realms.DisconnectedRealmsScreen
- net.minecraft.realms.NarrationHelper
- net.minecraft.realms.package-info
+ net.minecraft.realms.RealmsBridge
- net.minecraft.realms.RealmsConnect
+ net.minecraft.realms.RealmsConnect$1
- net.minecraft.realms.RealmsLabel
+ net.minecraft.realms.RealmsObjectSelectionList
- net.minecraft.realms.RealmsScreen
+ net.minecraft.realms.RealmsServerAddress
- net.minecraft.realms.RepeatedNarrator
+ net.minecraft.realms.RepeatedNarrator$Params
- net.minecraft.recipebook.package-info
+ net.minecraft.recipebook.PlaceRecipe
- net.minecraft.recipebook.ServerPlaceRecipe
+ net.minecraft.recipebook.ServerPlaceSmeltingRecipe
+ net.minecraft.resources.package-info
+ net.minecraft.resources.ResourceLocation
- net.minecraft.resources.ResourceLocation$Serializer
- net.minecraft.server.Bootstrap
+ net.minecraft.server.bossevents.CustomBossEvent
- net.minecraft.server.bossevents.CustomBossEvents
+ net.minecraft.server.bossevents.package-info
+ net.minecraft.server.ChainedJsonException
- net.minecraft.server.ChainedJsonException$1
+ net.minecraft.server.ChainedJsonException$Entry
- net.minecraft.server.commands.AdvancementCommands
+ net.minecraft.server.commands.AdvancementCommands$1
- net.minecraft.server.commands.AdvancementCommands$Action
+ net.minecraft.server.commands.AdvancementCommands$Action$1
- net.minecraft.server.commands.AdvancementCommands$Action$2
+ net.minecraft.server.commands.AdvancementCommands$Mode
- net.minecraft.server.commands.BanIpCommands
+ net.minecraft.server.commands.BanListCommands
- net.minecraft.server.commands.BanPlayerCommands
+ net.minecraft.server.commands.BossBarCommands
- net.minecraft.server.commands.ClearInventoryCommands
+ net.minecraft.server.commands.CloneCommands
- net.minecraft.server.commands.CloneCommands$CloneBlockInfo
+ net.minecraft.server.commands.CloneCommands$Mode
- net.minecraft.server.commands.data.BlockDataAccessor
+ net.minecraft.server.commands.data.BlockDataAccessor$1
- net.minecraft.server.commands.data.DataAccessor
+ net.minecraft.server.commands.data.DataCommands
- net.minecraft.server.commands.data.DataCommands$DataManipulator
+ net.minecraft.server.commands.data.DataCommands$DataManipulatorDecorator
- net.minecraft.server.commands.data.DataCommands$DataProvider
+ net.minecraft.server.commands.data.EntityDataAccessor
- net.minecraft.server.commands.data.EntityDataAccessor$1
+ net.minecraft.server.commands.data.package-info
+ net.minecraft.server.commands.data.StorageDataAccessor
- net.minecraft.server.commands.data.StorageDataAccessor$1
- net.minecraft.server.commands.DataPackCommand
+ net.minecraft.server.commands.DataPackCommand$Inserter
+ net.minecraft.server.commands.DebugCommand
- net.minecraft.server.commands.DebugMobSpawningCommand
+ net.minecraft.server.commands.DebugPathCommand
- net.minecraft.server.commands.DefaultGameModeCommands
- net.minecraft.server.commands.DeOpCommands
+ net.minecraft.server.commands.DifficultyCommand
- net.minecraft.server.commands.EffectCommands
+ net.minecraft.server.commands.EmoteCommands
- net.minecraft.server.commands.EnchantCommand
+ net.minecraft.server.commands.ExecuteCommand
- net.minecraft.server.commands.ExecuteCommand$CommandNumericPredicate
+ net.minecraft.server.commands.ExecuteCommand$CommandPredicate
- net.minecraft.server.commands.ExperienceCommand
+ net.minecraft.server.commands.ExperienceCommand$Type
- net.minecraft.server.commands.FillCommand
+ net.minecraft.server.commands.FillCommand$Mode
- net.minecraft.server.commands.ForceLoadCommand
+ net.minecraft.server.commands.FunctionCommand
- net.minecraft.server.commands.GameModeCommand
+ net.minecraft.server.commands.GameRuleCommand
- net.minecraft.server.commands.GameRuleCommand$1
+ net.minecraft.server.commands.GiveCommand
- net.minecraft.server.commands.HelpCommand
+ net.minecraft.server.commands.KickCommand
- net.minecraft.server.commands.KillCommand
+ net.minecraft.server.commands.ListPlayersCommand
- net.minecraft.server.commands.LocateBiomeCommand
+ net.minecraft.server.commands.LocateCommand
- net.minecraft.server.commands.LootCommand
+ net.minecraft.server.commands.LootCommand$Callback
- net.minecraft.server.commands.LootCommand$DropConsumer
+ net.minecraft.server.commands.LootCommand$TailProvider
- net.minecraft.server.commands.MsgCommand
+ net.minecraft.server.commands.OpCommand
- net.minecraft.server.commands.package-info
- net.minecraft.server.commands.PardonCommand
+ net.minecraft.server.commands.PardonIpCommand
- net.minecraft.server.commands.ParticleCommand
+ net.minecraft.server.commands.PlaySoundCommand
- net.minecraft.server.commands.PublishCommand
+ net.minecraft.server.commands.RaidCommand
- net.minecraft.server.commands.RecipeCommand
+ net.minecraft.server.commands.ReloadCommand
- net.minecraft.server.commands.ReplaceItemCommand
+ net.minecraft.server.commands.SaveAllCommand
- net.minecraft.server.commands.SaveOffCommand
+ net.minecraft.server.commands.SaveOnCommand
- net.minecraft.server.commands.SayCommand
+ net.minecraft.server.commands.ScheduleCommand
- net.minecraft.server.commands.ScoreboardCommand
+ net.minecraft.server.commands.SeedCommand
- net.minecraft.server.commands.SetBlockCommand
+ net.minecraft.server.commands.SetBlockCommand$Filter
- net.minecraft.server.commands.SetBlockCommand$Mode
+ net.minecraft.server.commands.SetPlayerIdleTimeoutCommand
- net.minecraft.server.commands.SetSpawnCommand
+ net.minecraft.server.commands.SetWorldSpawnCommand
- net.minecraft.server.commands.SpectateCommand
+ net.minecraft.server.commands.SpreadPlayersCommand
- net.minecraft.server.commands.SpreadPlayersCommand$Position
+ net.minecraft.server.commands.StopCommand
- net.minecraft.server.commands.StopSoundCommand
+ net.minecraft.server.commands.SummonCommand
- net.minecraft.server.commands.TagCommand
+ net.minecraft.server.commands.TeamCommand
- net.minecraft.server.commands.TeamMsgCommand
+ net.minecraft.server.commands.TeleportCommand
- net.minecraft.server.commands.TeleportCommand$LookAt
+ net.minecraft.server.commands.TellRawCommand
- net.minecraft.server.commands.TimeCommand
+ net.minecraft.server.commands.TitleCommand
- net.minecraft.server.commands.TriggerCommand
+ net.minecraft.server.commands.WeatherCommand
- net.minecraft.server.commands.WhitelistCommand
+ net.minecraft.server.commands.WorldBorderCommand
- net.minecraft.server.ConsoleInput
+ net.minecraft.server.ConsoleInputSource
- net.minecraft.server.DebugLoggedPrintStream
+ net.minecraft.server.dedicated.DedicatedPlayerList
- net.minecraft.server.dedicated.DedicatedServer
+ net.minecraft.server.dedicated.DedicatedServer$1
- net.minecraft.server.dedicated.DedicatedServer$2
+ net.minecraft.server.dedicated.DedicatedServerProperties
- net.minecraft.server.dedicated.DedicatedServerSettings
- net.minecraft.server.dedicated.package-info
+ net.minecraft.server.dedicated.ServerWatchdog
- net.minecraft.server.dedicated.ServerWatchdog$1
+ net.minecraft.server.dedicated.Settings
- net.minecraft.server.dedicated.Settings$1
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
+ net.minecraft.server.level.ChunkHolder$1
- net.minecraft.server.level.ChunkHolder$ChunkLoadingFailure
+ net.minecraft.server.level.ChunkHolder$ChunkLoadingFailure$1
- net.minecraft.server.level.ChunkHolder$FullChunkStatus
+ net.minecraft.server.level.ChunkHolder$LevelChangeListener
- net.minecraft.server.level.ChunkHolder$PlayerProvider
+ net.minecraft.server.level.ChunkMap
- net.minecraft.server.level.ChunkMap$1
+ net.minecraft.server.level.ChunkMap$2
- net.minecraft.server.level.ChunkMap$DistanceManager
+ net.minecraft.server.level.ChunkMap$TrackedEntity
- net.minecraft.server.level.ChunkTaskPriorityQueue
+ net.minecraft.server.level.ChunkTaskPriorityQueueSorter
- net.minecraft.server.level.ChunkTaskPriorityQueueSorter$1
+ net.minecraft.server.level.ChunkTaskPriorityQueueSorter$Message
- net.minecraft.server.level.ChunkTaskPriorityQueueSorter$Release
+ net.minecraft.server.level.ChunkTracker
- net.minecraft.server.level.ColumnPos
+ net.minecraft.server.level.DemoMode
- net.minecraft.server.level.DerivedServerLevel
+ net.minecraft.server.level.DistanceManager
- net.minecraft.server.level.DistanceManager$ChunkTicketTracker
+ net.minecraft.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
- net.minecraft.server.level.DistanceManager$PlayerTicketTracker
+ net.minecraft.server.level.FeatureSimulator
- net.minecraft.server.level.package-info
- net.minecraft.server.level.PlayerMap
+ net.minecraft.server.level.progress.ChunkProgressListener
- net.minecraft.server.level.progress.ChunkProgressListenerFactory
+ net.minecraft.server.level.progress.LoggerChunkProgressListener
- net.minecraft.server.level.progress.package-info
- net.minecraft.server.level.progress.ProcessorChunkProgressListener
+ net.minecraft.server.level.progress.StoringChunkProgressListener
+ net.minecraft.server.level.SectionTracker
- net.minecraft.server.level.ServerBossEvent
+ net.minecraft.server.level.ServerChunkCache
- net.minecraft.server.level.ServerChunkCache$1
+ net.minecraft.server.level.ServerChunkCache$MainThreadExecutor
- net.minecraft.server.level.ServerEntity
+ net.minecraft.server.level.ServerLevel
- net.minecraft.server.level.ServerPlayer
+ net.minecraft.server.level.ServerPlayerGameMode
- net.minecraft.server.level.ThreadedLevelLightEngine
+ net.minecraft.server.level.ThreadedLevelLightEngine$TaskType
- net.minecraft.server.level.Ticket
+ net.minecraft.server.level.TicketType
- net.minecraft.server.level.WorldGenRegion
+ net.minecraft.server.level.WorldGenTickList
- net.minecraft.server.LoggedPrintStream
+ net.minecraft.server.MinecraftServer
- net.minecraft.server.MinecraftServer$1
+ net.minecraft.server.MinecraftServer$2
- net.minecraft.server.MinecraftServer$3
+ net.minecraft.server.network.LegacyQueryHandler
- net.minecraft.server.network.MemoryServerHandshakePacketListenerImpl
+ net.minecraft.server.network.package-info
+ net.minecraft.server.network.ServerConnectionListener
- net.minecraft.server.network.ServerConnectionListener$1
+ net.minecraft.server.network.ServerConnectionListener$2
- net.minecraft.server.network.ServerConnectionListener$LatencySimulator
+ net.minecraft.server.network.ServerGamePacketListenerImpl
- net.minecraft.server.network.ServerGamePacketListenerImpl$1
+ net.minecraft.server.network.ServerHandshakePacketListenerImpl
- net.minecraft.server.network.ServerHandshakePacketListenerImpl$1
+ net.minecraft.server.network.ServerLoginPacketListenerImpl
- net.minecraft.server.network.ServerLoginPacketListenerImpl$1
+ net.minecraft.server.network.ServerLoginPacketListenerImpl$State
- net.minecraft.server.network.ServerStatusPacketListenerImpl
- net.minecraft.server.package-info
+ net.minecraft.server.packs.AbstractResourcePack
- net.minecraft.server.packs.FileResourcePack
+ net.minecraft.server.packs.FolderResourcePack
- net.minecraft.server.packs.metadata.MetadataSectionSerializer
+ net.minecraft.server.packs.metadata.pack.package-info
+ net.minecraft.server.packs.metadata.pack.PackMetadataSection
- net.minecraft.server.packs.metadata.pack.PackMetadataSectionSerializer
- net.minecraft.server.packs.metadata.package-info
- net.minecraft.server.packs.Pack
+ net.minecraft.server.packs.package-info
+ net.minecraft.server.packs.PackType
- net.minecraft.server.packs.repository.FolderRepositorySource
- net.minecraft.server.packs.repository.package-info
+ net.minecraft.server.packs.repository.PackCompatibility
- net.minecraft.server.packs.repository.PackRepository
+ net.minecraft.server.packs.repository.RepositorySource
- net.minecraft.server.packs.repository.ServerPacksSource
+ net.minecraft.server.packs.repository.UnopenedPack
- net.minecraft.server.packs.repository.UnopenedPack$Position
+ net.minecraft.server.packs.repository.UnopenedPack$UnopenedPackConstructor
- net.minecraft.server.packs.ResourcePackFileNotFoundException
+ net.minecraft.server.packs.resources.FallbackResourceManager
- net.minecraft.server.packs.resources.FallbackResourceManager$LeakedResourceWarningInputStream
- net.minecraft.server.packs.resources.package-info
+ net.minecraft.server.packs.resources.PreparableReloadListener
- net.minecraft.server.packs.resources.PreparableReloadListener$PreparationBarrier
+ net.minecraft.server.packs.resources.ProfiledReloadInstance
- net.minecraft.server.packs.resources.ProfiledReloadInstance$1
+ net.minecraft.server.packs.resources.ProfiledReloadInstance$State
+ net.minecraft.server.packs.resources.ReloadableResourceManager
- net.minecraft.server.packs.resources.ReloadInstance
- net.minecraft.server.packs.resources.Resource
+ net.minecraft.server.packs.resources.ResourceManager
- net.minecraft.server.packs.resources.ResourceManagerReloadListener
+ net.minecraft.server.packs.resources.SimpleJsonResourceReloadListener
- net.minecraft.server.packs.resources.SimplePreparableReloadListener
- net.minecraft.server.packs.resources.SimpleReloadableResourceManager
+ net.minecraft.server.packs.resources.SimpleReloadableResourceManager$FailingReloadInstance
- net.minecraft.server.packs.resources.SimpleReloadableResourceManager$ResourcePackLoadingFailure
+ net.minecraft.server.packs.resources.SimpleReloadInstance
- net.minecraft.server.packs.resources.SimpleReloadInstance$1
+ net.minecraft.server.packs.resources.SimpleReloadInstance$StateFactory
+ net.minecraft.server.packs.resources.SimpleResource
+ net.minecraft.server.packs.VanillaPack
+ net.minecraft.server.PlayerAdvancements
- net.minecraft.server.PlayerAdvancements$1
+ net.minecraft.server.players.BanListEntry
- net.minecraft.server.players.GameProfileCache
+ net.minecraft.server.players.GameProfileCache$1
- net.minecraft.server.players.GameProfileCache$2
+ net.minecraft.server.players.GameProfileCache$GameProfileInfo
- net.minecraft.server.players.GameProfileCache$Serializer
+ net.minecraft.server.players.IpBanList
- net.minecraft.server.players.IpBanListEntry
+ net.minecraft.server.players.OldUsersConverter
- net.minecraft.server.players.OldUsersConverter$1
+ net.minecraft.server.players.OldUsersConverter$2
- net.minecraft.server.players.OldUsersConverter$3
+ net.minecraft.server.players.OldUsersConverter$4
- net.minecraft.server.players.OldUsersConverter$5
+ net.minecraft.server.players.OldUsersConverter$ConversionError
- net.minecraft.server.players.package-info
- net.minecraft.server.players.PlayerList
+ net.minecraft.server.players.PlayerList$1
- net.minecraft.server.players.ServerOpList
+ net.minecraft.server.players.ServerOpListEntry
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
+ net.minecraft.server.RunningOnDifferentThreadException
- net.minecraft.server.ServerAdvancementManager
+ net.minecraft.server.ServerFunctionManager
- net.minecraft.server.ServerFunctionManager$QueuedCommand
+ net.minecraft.server.ServerInterface
- net.minecraft.server.ServerScoreboard
+ net.minecraft.server.ServerScoreboard$Method
- net.minecraft.server.TickTask
- net.minecraft.sounds.package-info
+ net.minecraft.sounds.SoundEvent
- net.minecraft.sounds.SoundEvents
+ net.minecraft.sounds.SoundSource
+ net.minecraft.stats.package-info
+ net.minecraft.stats.RecipeBook
- net.minecraft.stats.ServerRecipeBook
+ net.minecraft.stats.ServerStatsCounter
- net.minecraft.stats.Stat
+ net.minecraft.stats.StatFormatter
+ net.minecraft.stats.Stats
- net.minecraft.stats.StatsCounter
- net.minecraft.stats.StatType
- net.minecraft.tags.BlockTags
+ net.minecraft.tags.BlockTags$Wrapper
- net.minecraft.tags.EntityTypeTags
+ net.minecraft.tags.EntityTypeTags$Wrapper
- net.minecraft.tags.FluidTags
+ net.minecraft.tags.FluidTags$Wrapper
- net.minecraft.tags.ItemTags
+ net.minecraft.tags.ItemTags$Wrapper
+ net.minecraft.tags.package-info
- net.minecraft.tags.SynchronizableTagCollection
+ net.minecraft.tags.Tag
- net.minecraft.tags.Tag$Builder
+ net.minecraft.tags.Tag$Entry
- net.minecraft.tags.Tag$TagEntry
+ net.minecraft.tags.Tag$ValuesEntry
- net.minecraft.tags.TagCollection
+ net.minecraft.tags.TagManager
- net.minecraft.tags.TagManager$Preparations
- net.minecraft.util.BitStorage
+ net.minecraft.util.BlockFinder
+ net.minecraft.world.item.enchantment.package-info
- net.minecraft.world.item.enchantment.SoulSpeedEnchantment
+ net.minecraft.world.item.enchantment.SweepingEdgeEnchantment
- net.minecraft.world.item.enchantment.ThornsEnchantment
+ net.minecraft.world.item.enchantment.TridentChannelingEnchantment
- net.minecraft.world.item.enchantment.TridentImpalerEnchantment
+ net.minecraft.world.item.enchantment.TridentLoyaltyEnchantment
- net.minecraft.world.item.enchantment.TridentRiptideEnchantment
+ net.minecraft.world.item.enchantment.UntouchingEnchantment
- net.minecraft.world.item.enchantment.VanishingCurseEnchantment
+ net.minecraft.world.item.enchantment.WaterWalkerEnchantment
- net.minecraft.world.item.enchantment.WaterWorkerEnchantment
- net.minecraft.world.item.package-info
+ net.minecraft.world.item.trading.Merchant
- net.minecraft.world.item.trading.MerchantOffer
+ net.minecraft.world.item.trading.MerchantOffers
- net.minecraft.world.item.trading.package-info
+ net.minecraft.world.level.BaseCommandBlock
- net.minecraft.world.level.BaseSpawner
- net.minecraft.world.level.biome.AmbientParticleSettings
+ net.minecraft.world.level.biome.BadlandsBiome
- net.minecraft.world.level.biome.BadlandsPlateauBiome
+ net.minecraft.world.level.biome.BambooJungleBiome
- net.minecraft.world.level.biome.BambooJungleHillsBiome
+ net.minecraft.world.level.biome.BeachBiome
- net.minecraft.world.level.biome.Biome
+ net.minecraft.world.level.biome.Biome$1
- net.minecraft.world.level.biome.Biome$BiomeBuilder
+ net.minecraft.world.level.biome.Biome$BiomeCategory
- net.minecraft.world.level.biome.Biome$BiomeTempCategory
+ net.minecraft.world.level.biome.Biome$ClimateParameters
- net.minecraft.world.level.biome.Biome$Precipitation
+ net.minecraft.world.level.biome.Biome$SpawnerData
- net.minecraft.world.level.biome.BiomeDefaultFeatures
+ net.minecraft.world.level.biome.BiomeManager
- net.minecraft.world.level.biome.BiomeManager$NoiseBiomeSource
- net.minecraft.world.level.biome.Biomes
+ net.minecraft.world.level.biome.BiomeSource
- net.minecraft.world.level.biome.BiomeSourceSettings
+ net.minecraft.world.level.biome.BiomeSourceType
- net.minecraft.world.level.biome.BiomeSpecialEffects
+ net.minecraft.world.level.biome.BiomeSpecialEffects$1
- net.minecraft.world.level.biome.BiomeSpecialEffects$Builder
+ net.minecraft.world.level.biome.BiomeZoomer
+ net.minecraft.world.level.biome.BirchForestBiome
- net.minecraft.world.level.biome.BirchForestHillsBiome
+ net.minecraft.world.level.biome.CheckerboardBiomeSourceSettings
- net.minecraft.world.level.biome.CheckerboardColumnBiomeSource
+ net.minecraft.world.level.biome.ColdOceanBiome
- net.minecraft.world.level.biome.CrimsonForestBiome
+ net.minecraft.world.level.biome.DarkForestBiome
- net.minecraft.world.level.biome.DarkForestHillsBiome
+ net.minecraft.world.level.biome.DeepColdOceanBiome
- net.minecraft.world.level.biome.DeepFrozenOceanBiome
+ net.minecraft.world.level.biome.DeepLukeWarmOceanBiome
- net.minecraft.world.level.biome.DeepOceanBiome
+ net.minecraft.world.level.biome.DeepWarmOceanBiome
- net.minecraft.world.level.biome.DesertBiome
+ net.minecraft.world.level.biome.DesertHillsBiome
- net.minecraft.world.level.biome.DesertLakesBiome
+ net.minecraft.world.level.biome.EndBarrensBiome
- net.minecraft.world.level.biome.EndHighlandsBiome
+ net.minecraft.world.level.biome.EndMidlandsBiome
- net.minecraft.world.level.biome.ErodedBadlandsBiome
+ net.minecraft.world.level.biome.FixedBiomeSource
- net.minecraft.world.level.biome.FixedBiomeSourceSettings
+ net.minecraft.world.level.biome.ForestBiome
- net.minecraft.world.level.biome.ForestFlowerBiome
+ net.minecraft.world.level.biome.FrozenOceanBiome
- net.minecraft.world.level.biome.FrozenRiverBiome
+ net.minecraft.world.level.biome.FuzzyOffsetBiomeZoomer
- net.minecraft.world.level.biome.FuzzyOffsetConstantColumnBiomeZoomer
+ net.minecraft.world.level.biome.GiantSpruceTaigaBiome
- net.minecraft.world.level.biome.GiantSpruceTaigaHillsMutatedBiome
+ net.minecraft.world.level.biome.GiantTreeTaigaBiome
- net.minecraft.world.level.biome.GiantTreeTaigaHillsBiome
+ net.minecraft.world.level.biome.GravellyMountainsBiome
- net.minecraft.world.level.biome.IceSpikesBiome
+ net.minecraft.world.level.biome.JungleBiome
- net.minecraft.world.level.biome.JungleEdgeBiome
+ net.minecraft.world.level.biome.JungleHillsBiome
- net.minecraft.world.level.biome.LukeWarmOceanBiome
+ net.minecraft.world.level.biome.ModifiedBadlandsPlateauBiome
- net.minecraft.world.level.biome.ModifiedGravellyMountainsBiome
+ net.minecraft.world.level.biome.ModifiedJungleBiome
- net.minecraft.world.level.biome.ModifiedJungleEdgeBiome
+ net.minecraft.world.level.biome.ModifiedWoodedBadlandsPlateauBiome
- net.minecraft.world.level.biome.MountainBiome
+ net.minecraft.world.level.biome.MountainEdgeBiome
- net.minecraft.world.level.biome.MultiNoiseBiomeSource
+ net.minecraft.world.level.biome.MultiNoiseBiomeSourceSettings
- net.minecraft.world.level.biome.MushroomFieldsBiome
+ net.minecraft.world.level.biome.MushroomFieldsShoreBiome
- net.minecraft.world.level.biome.NearestNeighborBiomeZoomer
+ net.minecraft.world.level.biome.NetherWastesBiome
- net.minecraft.world.level.biome.OceanBiome
+ net.minecraft.world.level.biome.OverworldBiomeSource
- net.minecraft.world.level.biome.OverworldBiomeSourceSettings
+ net.minecraft.world.level.biome.package-info
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
- net.minecraft.world.level.biome.TheEndBiomeSourceSettings
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
+ net.minecraft.world.level.block.BeaconBeamBlock
- net.minecraft.world.level.block.BeaconBlock
+ net.minecraft.world.level.block.BedBlock
- net.minecraft.world.level.block.BedBlock$1
+ net.minecraft.world.level.block.BedrockBlock
- net.minecraft.world.level.block.BeehiveBlock
+ net.minecraft.world.level.block.BeetrootBlock
- net.minecraft.world.level.block.BellBlock
+ net.minecraft.world.level.block.BellBlock$1
- net.minecraft.world.level.block.BlastFurnaceBlock
+ net.minecraft.world.level.block.Block
- net.minecraft.world.level.block.Block$1
+ net.minecraft.world.level.block.Block$2
- net.minecraft.world.level.block.Block$3
+ net.minecraft.world.level.block.Block$BlockStatePairKey
- net.minecraft.world.level.block.Block$OffsetType
+ net.minecraft.world.level.block.Block$Properties
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
- net.minecraft.world.level.block.GoldBlock
+ net.minecraft.world.level.block.GrassBlock
- net.minecraft.world.level.block.GrassPathBlock
+ net.minecraft.world.level.block.GravelBlock
- net.minecraft.world.level.block.GrindstoneBlock
+ net.minecraft.world.level.block.GrindstoneBlock$1
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
- net.minecraft.world.level.block.LogBlock
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
+ net.minecraft.world.level.block.NetherSproutsBlock
- net.minecraft.world.level.block.NetherVines
- net.minecraft.world.level.block.TwistingVinesPlant
+ net.minecraft.world.level.BlockAndTintGetter
- net.minecraft.world.level.BlockEventData
+ net.minecraft.world.level.BlockGetter
- net.minecraft.world.level.ChunkPos
+ net.minecraft.world.level.ChunkPos$1
- net.minecraft.world.level.ChunkTickList
+ net.minecraft.world.level.ClipContext
- net.minecraft.world.level.ClipContext$Block
+ net.minecraft.world.level.ClipContext$Fluid
- net.minecraft.world.level.ClipContext$ShapeGetter
+ net.minecraft.world.level.CollisionGetter
- net.minecraft.world.level.CollisionGetter$1
+ net.minecraft.world.level.ColorResolver
- net.minecraft.world.level.CustomSpawner
+ net.minecraft.world.level.EmptyBlockGetter
- net.minecraft.world.level.EmptyTickList
+ net.minecraft.world.level.EntityGetter
- net.minecraft.world.level.Explosion
+ net.minecraft.world.level.Explosion$BlockInteraction
- net.minecraft.world.level.FoliageColor
+ net.minecraft.world.level.ForcedChunksSavedData
- net.minecraft.world.level.GameRules
+ net.minecraft.world.level.GameRules$1
- net.minecraft.world.level.GameRules$BooleanValue
+ net.minecraft.world.level.GameRules$GameRuleTypeVisitor
- net.minecraft.world.level.GameRules$IntegerValue
+ net.minecraft.world.level.GameRules$Key
- net.minecraft.world.level.GameRules$Type
+ net.minecraft.world.level.GameRules$Value
- net.minecraft.world.level.GameType
+ net.minecraft.world.level.GrassColor
- net.minecraft.world.level.ItemLike
+ net.minecraft.world.level.Level
- net.minecraft.world.level.LevelAccessor
+ net.minecraft.world.level.LevelConflictException
- net.minecraft.world.level.levelgen.carver.CanyonWorldCarver
+ net.minecraft.world.level.levelgen.carver.CarverConfiguration
- net.minecraft.world.level.levelgen.carver.CaveWorldCarver
+ net.minecraft.world.level.levelgen.carver.ConfiguredWorldCarver
- net.minecraft.world.level.levelgen.carver.NetherWorldCarver
+ net.minecraft.world.level.levelgen.carver.NoneCarverConfiguration
+ net.minecraft.world.level.levelgen.carver.package-info
- net.minecraft.world.level.levelgen.carver.UnderwaterCanyonWorldCarver
+ net.minecraft.world.level.levelgen.carver.UnderwaterCaveWorldCarver
- net.minecraft.world.level.levelgen.carver.WorldCarver
- net.minecraft.world.level.levelgen.ChunkGeneratorProvider
+ net.minecraft.world.level.levelgen.ChunkGeneratorSettings
- net.minecraft.world.level.levelgen.DebugGeneratorSettings
+ net.minecraft.world.level.levelgen.DebugLevelSource
- net.minecraft.world.level.levelgen.feature.AbstractFlowerFeature
+ net.minecraft.world.level.levelgen.feature.AbstractHugeMushroomFeature
- net.minecraft.world.level.levelgen.feature.AbstractSmallTreeFeature
+ net.minecraft.world.level.levelgen.feature.AbstractTreeFeature
- net.minecraft.world.level.levelgen.feature.AcaciaFeature
+ net.minecraft.world.level.levelgen.feature.BambooFeature
- net.minecraft.world.level.levelgen.feature.BasaltPillarFeature
+ net.minecraft.world.level.levelgen.feature.BlockBlobFeature
- net.minecraft.world.level.levelgen.feature.BlockPileFeature
+ net.minecraft.world.level.levelgen.feature.BlueIceFeature
- net.minecraft.world.level.levelgen.feature.BonusChestFeature
+ net.minecraft.world.level.levelgen.feature.BuriedTreasureFeature
- net.minecraft.world.level.levelgen.feature.BuriedTreasureFeature$BuriedTreasureStart
+ net.minecraft.world.level.levelgen.feature.ChorusPlantFeature
- net.minecraft.world.level.levelgen.feature.ConfiguredFeature
+ net.minecraft.world.level.levelgen.feature.CoralClawFeature
- net.minecraft.world.level.levelgen.feature.CoralFeature
+ net.minecraft.world.level.levelgen.feature.CoralMushroomFeature
- net.minecraft.world.level.levelgen.feature.CoralTreeFeature
+ net.minecraft.world.level.levelgen.feature.DarkOakFeature
- net.minecraft.world.level.levelgen.feature.DecoratedFeature
+ net.minecraft.world.level.levelgen.feature.DecoratedFlowerFeature
- net.minecraft.world.level.levelgen.feature.DefaultFlowerFeature
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
+ net.minecraft.world.level.levelgen.feature.FancyTreeFeature
- net.minecraft.world.level.levelgen.feature.FancyTreeFeature$FoliageCoords
+ net.minecraft.world.level.levelgen.feature.Feature
- net.minecraft.world.level.levelgen.feature.FillLayerFeature
+ net.minecraft.world.level.levelgen.feature.FossilFeature
- net.minecraft.world.level.levelgen.feature.GlowstoneFeature
+ net.minecraft.world.level.levelgen.feature.GroundBushFeature
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
+ net.minecraft.world.level.levelgen.feature.MegaJungleTreeFeature
- net.minecraft.world.level.levelgen.feature.MegaPineTreeFeature
+ net.minecraft.world.level.levelgen.feature.MegaTreeFeature
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
- net.minecraft.world.level.levelgen.feature.PillagerOutpostFeature
+ net.minecraft.world.level.levelgen.feature.PillagerOutpostFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.PlainVillagePools
+ net.minecraft.world.level.levelgen.feature.RandomBooleanSelectorFeature
- net.minecraft.world.level.levelgen.feature.RandomPatchFeature
+ net.minecraft.world.level.levelgen.feature.RandomRandomFeature
- net.minecraft.world.level.levelgen.feature.RandomScatteredFeature
+ net.minecraft.world.level.levelgen.feature.RandomSelectorFeature
- net.minecraft.world.level.levelgen.feature.ReplaceBlockFeature
+ net.minecraft.world.level.levelgen.feature.SavannaVillagePools
+ net.minecraft.world.level.levelgen.feature.SeagrassFeature
- net.minecraft.world.level.levelgen.feature.SeaPickleFeature
- net.minecraft.world.level.levelgen.feature.ShipwreckFeature
+ net.minecraft.world.level.levelgen.feature.ShipwreckFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.SimpleBlockFeature
+ net.minecraft.world.level.levelgen.feature.SimpleRandomSelectorFeature
- net.minecraft.world.level.levelgen.feature.SimulatedFeature
+ net.minecraft.world.level.levelgen.feature.SnowAndFreezeFeature
- net.minecraft.world.level.levelgen.feature.SnowyVillagePools
+ net.minecraft.world.level.levelgen.feature.SpikeFeature
- net.minecraft.world.level.levelgen.feature.SpikeFeature$1
+ net.minecraft.world.level.levelgen.feature.SpikeFeature$EndSpike
- net.minecraft.world.level.levelgen.feature.SpikeFeature$SpikeCacheLoader
+ net.minecraft.world.level.levelgen.feature.SpringFeature
- net.minecraft.world.level.levelgen.feature.StrongholdFeature
+ net.minecraft.world.level.levelgen.feature.StrongholdFeature$StrongholdStart
- net.minecraft.world.level.levelgen.feature.StructureFeature
+ net.minecraft.world.level.levelgen.feature.StructureFeature$StructureStartFactory
- net.minecraft.world.level.levelgen.feature.StructurePieceType
+ net.minecraft.world.level.levelgen.feature.SwamplandHutFeature
- net.minecraft.world.level.levelgen.feature.SwamplandHutFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.TaigaVillagePools
- net.minecraft.world.level.levelgen.feature.TreeFeature
- net.minecraft.world.level.levelgen.FlatLevelSource
+ net.minecraft.world.level.levelgen.FlatLevelSource$FlatLevelBiomeWrapper
- net.minecraft.world.level.levelgen.GenerationStep
+ net.minecraft.world.level.levelgen.GenerationStep$Carving
- net.minecraft.world.level.levelgen.GenerationStep$Decoration
+ net.minecraft.world.level.levelgen.Heightmap
- net.minecraft.world.level.levelgen.Heightmap$Types
+ net.minecraft.world.level.levelgen.Heightmap$Usage
- net.minecraft.world.level.levelgen.NetherGeneratorSettings
+ net.minecraft.world.level.levelgen.NetherLevelSource
- net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator
+ net.minecraft.world.level.levelgen.OverworldGeneratorSettings
- net.minecraft.world.level.levelgen.OverworldLevelSource
+ net.minecraft.world.level.levelgen.PatrolSpawner
- net.minecraft.world.level.levelgen.PhantomSpawner
+ net.minecraft.world.level.levelgen.TheEndGeneratorSettings
- net.minecraft.world.level.levelgen.TheEndLevelSource
+ net.minecraft.world.level.levelgen.WorldgenRandom
- net.minecraft.world.level.LevelReader
+ net.minecraft.world.level.LevelSettings
+ net.minecraft.world.level.LevelSimulatedReader
- net.minecraft.world.level.LevelSimulatedRW
- net.minecraft.world.level.LevelType
+ net.minecraft.world.level.LevelWriter
- net.minecraft.world.level.LightLayer
+ net.minecraft.world.level.NaturalSpawner
- net.minecraft.world.level.NaturalSpawner$1
+ net.minecraft.world.level.PathNavigationRegion
- net.minecraft.world.level.PortalForcer
+ net.minecraft.world.level.ServerTickList
- net.minecraft.world.level.SpawnData
+ net.minecraft.world.level.TickList
- net.minecraft.world.level.TickNextTickData
+ net.minecraft.world.level.TickPriority
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.gui.screens.CreateBuffetWorldScreen +1M -1M
```
```
XXX.gui.screens.CreateFlatWorldScreen +1M -3M
```
```
XXX.screens.worldselection.CreateWorldScreen +2M -1M | +1P -1P
```
```
XXX.client.particle.FlameParticle -1M
```
```
XXX.client.player.LocalPlayer +1P
```
```
XXX.client.server.IntegratedServer +1M -1M
```
```
XXX.minecraft.core.BlockPos +5M -1M
```
```
XXX.minecraft.core.BlockPos$2 +4P -5P
```
```
XXX.minecraft.core.Vec3i -2M
```
```
XXX.datafix.fixes.RenameBiomesFix +1M -1M | +1P
```
```
XXX.world.entity.Entity +1M | -3P
```
```
XXX.ai.behavior.BehaviorUtils +2M -1M
```
```
XXX.ai.behavior.CrossbowAttack -1P
```
```
XXX.ai.behavior.MeleeAttack +4M -2M | -1P
```
```
XXX.ai.behavior.SetWalkTargetFromAttackTargetIfTargetOutOfReach +2M -4M
```
```
XXX.entity.monster.AbstractSkeleton +1M
```
```
XXX.entity.monster.Pillager +1M
```
```
XXX.monster.hoglin.HoglinAi +2M -1M
```
```
XXX.entity.projectile.AbstractArrow -1P
```
```
XXX.item.enchantment.Enchantment +2M
```
```
XXX.item.enchantment.Enchantments +1P
```
```
XXX.level.block.SnowLayerBlock +1M
```
```
XXX.level.block.SoulSandBlock +1M
```
```
XXX.level.block.WeepingVinesPlant -2M | -1P
```
```
XXX.state.properties.BlockStateProperties +1P
```
```
XXX.level.chunk.ChunkGeneratorType +1M -1M
```

</details>














































































































































































































































































































<details>
<summary>
net.minecraft.client.gui.screens.CreateBuffetWorldScreen
</summary>

```diff
- void <init>(CreateWorldScreen,ChunkGeneratorProvider)
+ void <init>(CreateWorldScreen,CompoundTag)
```

</details>

<details>
<summary>
net.minecraft.client.gui.screens.CreateFlatWorldScreen
</summary>

```diff
+ CompoundTag saveLayers()
- void <init>(CreateWorldScreen,ChunkGeneratorProvider)
+ void <init>(CreateWorldScreen,CompoundTag)
+ void loadLayers(CompoundTag)
```

</details>
















































































<details>
<summary>
net.minecraft.client.gui.screens.worldselection.CreateWorldScreen
</summary>

```diff
+ int access$600(CreateWorldScreen)
- LevelType access$600(CreateWorldScreen)
- LevelType getLevelType()
```

</details>
























































































































<details>
<summary>
net.minecraft.client.particle.FlameParticle
</summary>

```diff
+ void tick()
```

</details>




























































































































































































































































































<details>
<summary>
net.minecraft.client.server.IntegratedServer
</summary>

```diff
- void loadLevel(String,String,long,ChunkGeneratorProvider)
+ void loadLevel(String,String,long,LevelType,JsonElement)
```

</details>


















































































<details>
<summary>
net.minecraft.core.BlockPos
</summary>

```diff
- Iterable withinManhattan(BlockPos,int,int,int)
+ Iterator lambda$betweenClosed$3(int,int,int,int,int,int)
- Iterator lambda$betweenClosed$4(int,int,int,int,int,int)
- Iterator lambda$withinManhattan$3(int,int,int,int,BlockPos)
- Optional findClosestMatch(BlockPos,int,int,Predicate)
- Stream withinManhattanStream(BlockPos,int,int,int)
```

</details>

















<details>
<summary>
net.minecraft.core.Vec3i
</summary>

```diff
+ Iterable between(Vec3i,Vec3i)
+ Iterator lambda$between$0(Vec3i,Vec3i)
```

</details>











































































<details>
<summary>
net.minecraft.util.datafix.fixes.RenameBiomesFix
</summary>

```diff
+ void <init>(Schema,boolean,Map)
- void <init>(Schema,boolean,String,Map)
```

</details>










































































<details>
<summary>
net.minecraft.world.entity.Entity
</summary>

```diff
- BlockState getBlockStateOn()
```

</details>


























<details>
<summary>
net.minecraft.world.entity.ai.behavior.BehaviorUtils
</summary>

```diff
+ boolean isAttackTargetVisibleAndInRange(LivingEntity,double)
- boolean isWithinAttackRange(Mob,LivingEntity,int)
- boolean isWithinMeleeAttackRange(LivingEntity,LivingEntity)
```

</details>














<details>
<summary>
net.minecraft.world.entity.ai.behavior.MeleeAttack
</summary>

```diff
- boolean isHoldingUsableProjectileWeapon(Mob)
+ boolean lambda$checkExtraStartConditions$0(Item)
- boolean lambda$isHoldingUsableProjectileWeapon$0(Mob,Item)
- LivingEntity getAttackTarget(Mob)
+ void <init>(double,int)
- void <init>(int)
```

</details>









<details>
<summary>
net.minecraft.world.entity.ai.behavior.SetWalkTargetFromAttackTargetIfTargetOutOfReach
</summary>

```diff
+ double getAttackRange(ItemStack)
+ double getAttackRange(LivingEntity)
+ LivingEntity getAttackTarget(LivingEntity)
- void setWalkAndLookTarget(LivingEntity,LivingEntity)
+ void setWalkTarget(LivingEntity,LivingEntity)
- void start(ServerLevel,Mob,long)
```

</details>



















































































































































































<details>
<summary>
net.minecraft.world.entity.monster.AbstractSkeleton
</summary>

```diff
- boolean canFireProjectileWeapon(ProjectileWeaponItem)
```

</details>




























<details>
<summary>
net.minecraft.world.entity.monster.Pillager
</summary>

```diff
- boolean canFireProjectileWeapon(ProjectileWeaponItem)
```

</details>


























<details>
<summary>
net.minecraft.world.entity.monster.hoglin.HoglinAi
</summary>

```diff
+ boolean hoglinsOutnumberPiglins(Hoglin)
- boolean piglinsOutnumberHoglins(Hoglin)
- boolean wantsToStopFleeing(Hoglin)
```

</details>

































































































































































































<details>
<summary>
net.minecraft.world.item.enchantment.Enchantment
</summary>

```diff
- boolean isDiscoverable()
- boolean isTradeable()
```

</details>









































<details>
<summary>
net.minecraft.world.level.block.SnowLayerBlock
</summary>

```diff
- VoxelShape getBlockSupportShape(BlockState,BlockGetter,BlockPos)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.SoulSandBlock
</summary>

```diff
- VoxelShape getBlockSupportShape(BlockState,BlockGetter,BlockPos)
```

</details>





















<details>
<summary>
net.minecraft.world.level.block.WeepingVinesPlant
</summary>

```diff
+ void <clinit>()
+ VoxelShape getShape(BlockState,BlockGetter,BlockPos,CollisionContext)
```

</details>










































































<details>
<summary>
net.minecraft.world.level.chunk.ChunkGeneratorType
</summary>

```diff
+ ChunkGenerator create(Level,BiomeSource,ChunkGeneratorSettings)
- ChunkGenerator create(LevelAccessor,BiomeSource,ChunkGeneratorSettings)
```

</details>
</details>