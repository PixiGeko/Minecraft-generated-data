## Comparison with [19w41a](https://github.com/PixiGeko/Minecraft-generated-data/tree/19w41a)

- [Version data](#version-data)
- [Translations](#translations)
- [File structure](#file-structure)
- [Mappings](#mappings)
  - [Server](#server)
  - [Client](#client)

<hr/>
<details><summary>Version data</summary>
<table><tr><th></th><th align="left">19w41a</th><th>19w42a</th></tr><tr><td>World version</td><td><code>2210</code></td><td><code>2212</code></td></tr><tr><td>Protocol version</td><td><code>558</code></td><td><code>559</code></td></tr></table>
</details>
<details><summary>Translations</summary>
<details>
<summary>
Keys
</summary>

```diff
+ chat.copy.click: Click to copy to Clipboard
```

</details>
<details>
<summary>
Changes
</summary>

```
block.minecraft.bee_nest: Bee nNest
```

</details>
</details>
<details><summary>File structure</summary>
<details>
<summary>
data
</summary>

```diff
+ minecraft/tags/items/lectern_books.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
- minecraft/textures/block/wax_block.png
- minecraft/textures/entity/chest/christmas_double.png
+ minecraft/textures/entity/chest/christmas_left.png
+ minecraft/textures/entity/chest/christmas_right.png
- minecraft/textures/entity/chest/normal_double.png
+ minecraft/textures/entity/chest/normal_left.png
+ minecraft/textures/entity/chest/normal_right.png
- minecraft/textures/entity/chest/trapped_double.png
+ minecraft/textures/entity/chest/trapped_left.png
+ minecraft/textures/entity/chest/trapped_right.png
- minecraft/textures/item/crystallized_honey.png
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
- net.minecraft.data.loot.package-info
- net.minecraft.data.Main
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
+ net.minecraft.network.protocol.game.DebugPackets
- net.minecraft.network.protocol.game.DebugVillagerNameGenerator
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
- net.minecraft.server.commands.DebugPathCommand
+ net.minecraft.server.commands.DefaultGameModeCommands
- net.minecraft.server.commands.DeOpCommands
- net.minecraft.server.commands.DifficultyCommand
+ net.minecraft.server.commands.EffectCommands
- net.minecraft.server.commands.EmoteCommands
+ net.minecraft.server.commands.EnchantCommand
- net.minecraft.server.commands.ExecuteCommand
+ net.minecraft.server.commands.ExecuteCommand$CommandNumericPredicate
- net.minecraft.server.commands.ExecuteCommand$CommandPredicate
+ net.minecraft.server.commands.ExperienceCommand
- net.minecraft.server.commands.ExperienceCommand$Type
+ net.minecraft.server.commands.FillCommand
- net.minecraft.server.commands.FillCommand$Mode
+ net.minecraft.server.commands.ForceLoadCommand
- net.minecraft.server.commands.FunctionCommand
+ net.minecraft.server.commands.GameModeCommand
- net.minecraft.server.commands.GameRuleCommand
+ net.minecraft.server.commands.GameRuleCommand$1
- net.minecraft.server.commands.GiveCommand
+ net.minecraft.server.commands.HelpCommand
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
- net.minecraft.server.players.StoredUserList$1
+ net.minecraft.server.players.StoredUserList$Serializer
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
+ net.minecraft.util.ClassInstanceMultiMap
- net.minecraft.util.CrudeIncrementalIntIdentityHashBiMap
+ net.minecraft.util.Crypt
- net.minecraft.util.CsvOutput
+ net.minecraft.util.CsvOutput$1
- net.minecraft.util.CsvOutput$Builder
+ net.minecraft.util.datafix.DataFixers
- net.minecraft.util.datafix.DataFixers$1
+ net.minecraft.util.datafix.DataFixers$2
- net.minecraft.util.datafix.DataFixTypes
- net.minecraft.util.datafix.fixes.AddNewChoices
+ net.minecraft.util.datafix.fixes.AdvancementsFix
- net.minecraft.util.datafix.fixes.BedBlockEntityInjecter
+ net.minecraft.util.datafix.fixes.BedItemColorFix
- net.minecraft.util.datafix.fixes.BeehivePoiRenameFix
+ net.minecraft.util.datafix.fixes.BiomeFix
- net.minecraft.util.datafix.fixes.BlockEntityBannerColorFix
+ net.minecraft.util.datafix.fixes.BlockEntityBlockStateFix
- net.minecraft.util.datafix.fixes.BlockEntityCustomNameToComponentFix
+ net.minecraft.util.datafix.fixes.BlockEntityIdFix
- net.minecraft.util.datafix.fixes.BlockEntityJukeboxFix
+ net.minecraft.util.datafix.fixes.BlockEntityKeepPacked
- net.minecraft.util.datafix.fixes.BlockEntityShulkerBoxColorFix
+ net.minecraft.util.datafix.fixes.BlockEntitySignTextStrictJsonFix
- net.minecraft.util.datafix.fixes.BlockEntitySignTextStrictJsonFix$1
+ net.minecraft.util.datafix.fixes.BlockNameFlatteningFix
- net.minecraft.util.datafix.fixes.BlockRenameFix
+ net.minecraft.util.datafix.fixes.BlockRenameFix$1
- net.minecraft.util.datafix.fixes.BlockStateData
+ net.minecraft.util.datafix.fixes.BlockStateStructureTemplateFix
- net.minecraft.util.datafix.fixes.CatTypeFix
+ net.minecraft.util.datafix.fixes.ChunkBiomeFix
- net.minecraft.util.datafix.fixes.ChunkLightRemoveFix
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$1
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$DataLayer
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction$Axis
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction$AxisDirection
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Section
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$UpgradeChunk
+ net.minecraft.util.datafix.fixes.ChunkStatusFix
- net.minecraft.util.datafix.fixes.ChunkStatusFix2
+ net.minecraft.util.datafix.fixes.ChunkStructuresTemplateRenameFix
- net.minecraft.util.datafix.fixes.ChunkToProtochunkFix
+ net.minecraft.util.datafix.fixes.ColorlessShulkerEntityFix
- net.minecraft.util.datafix.fixes.DyeItemRenameFix
+ net.minecraft.util.datafix.fixes.EntityArmorStandSilentFix
- net.minecraft.util.datafix.fixes.EntityBlockStateFix
+ net.minecraft.util.datafix.fixes.EntityCatSplitFix
- net.minecraft.util.datafix.fixes.EntityCodSalmonFix
+ net.minecraft.util.datafix.fixes.EntityCustomNameToComponentFix
- net.minecraft.util.datafix.fixes.EntityElderGuardianSplitFix
+ net.minecraft.util.datafix.fixes.EntityEquipmentToArmorAndHandFix
- net.minecraft.util.datafix.fixes.EntityHealthFix
+ net.minecraft.util.datafix.fixes.EntityHorseSaddleFix
- net.minecraft.util.datafix.fixes.EntityHorseSplitFix
+ net.minecraft.util.datafix.fixes.EntityIdFix
- net.minecraft.util.datafix.fixes.EntityItemFrameDirectionFix
+ net.minecraft.util.datafix.fixes.EntityMinecartIdentifiersFix
- net.minecraft.util.datafix.fixes.EntityPaintingItemFrameDirectionFix
+ net.minecraft.util.datafix.fixes.EntityPaintingMotiveFix
- net.minecraft.util.datafix.fixes.EntityPufferfishRenameFix
+ net.minecraft.util.datafix.fixes.EntityRavagerRenameFix
- net.minecraft.util.datafix.fixes.EntityRedundantChanceTagsFix
+ net.minecraft.util.datafix.fixes.EntityRenameFix
- net.minecraft.util.datafix.fixes.EntityRidingToPassengersFix
+ net.minecraft.util.datafix.fixes.EntityShulkerColorFix
- net.minecraft.util.datafix.fixes.EntitySkeletonSplitFix
+ net.minecraft.util.datafix.fixes.EntityStringUuidFix
- net.minecraft.util.datafix.fixes.EntityTheRenameningFix
+ net.minecraft.util.datafix.fixes.EntityTippedArrowFix
- net.minecraft.util.datafix.fixes.EntityWolfColorFix
+ net.minecraft.util.datafix.fixes.EntityZombieSplitFix
- net.minecraft.util.datafix.fixes.EntityZombieVillagerTypeFix
+ net.minecraft.util.datafix.fixes.ForcePoiRebuild
- net.minecraft.util.datafix.fixes.HeightmapRenamingFix
+ net.minecraft.util.datafix.fixes.IglooMetadataRemovalFix
- net.minecraft.util.datafix.fixes.ItemBannerColorFix
+ net.minecraft.util.datafix.fixes.ItemCustomNameToComponentFix
- net.minecraft.util.datafix.fixes.ItemIdFix
+ net.minecraft.util.datafix.fixes.ItemLoreFix
- net.minecraft.util.datafix.fixes.ItemPotionFix
+ net.minecraft.util.datafix.fixes.ItemRenameFix
- net.minecraft.util.datafix.fixes.ItemRenameFix$1
+ net.minecraft.util.datafix.fixes.ItemShulkerBoxColorFix
- net.minecraft.util.datafix.fixes.ItemSpawnEggFix
+ net.minecraft.util.datafix.fixes.ItemStackEnchantmentNamesFix
- net.minecraft.util.datafix.fixes.ItemStackMapIdFix
+ net.minecraft.util.datafix.fixes.ItemStackSpawnEggFix
- net.minecraft.util.datafix.fixes.ItemStackTheFlatteningFix
+ net.minecraft.util.datafix.fixes.ItemWaterPotionFix
- net.minecraft.util.datafix.fixes.ItemWrittenBookPagesStrictJsonFix
+ net.minecraft.util.datafix.fixes.LeavesFix
- net.minecraft.util.datafix.fixes.LeavesFix$LeavesSection
+ net.minecraft.util.datafix.fixes.LeavesFix$Section
- net.minecraft.util.datafix.fixes.LevelDataGeneratorOptionsFix
+ net.minecraft.util.datafix.fixes.LevelFlatGeneratorInfoFix
- net.minecraft.util.datafix.fixes.MapIdFix
+ net.minecraft.util.datafix.fixes.MobSpawnerEntityIdentifiersFix
- net.minecraft.util.datafix.fixes.NamedEntityFix
+ net.minecraft.util.datafix.fixes.NewVillageFix
- net.minecraft.util.datafix.fixes.ObjectiveDisplayNameFix
+ net.minecraft.util.datafix.fixes.ObjectiveRenderTypeFix
- net.minecraft.util.datafix.fixes.OptionsAddTextBackgroundFix
+ net.minecraft.util.datafix.fixes.OptionsForceVBOFix
- net.minecraft.util.datafix.fixes.OptionsKeyLwjgl3Fix
+ net.minecraft.util.datafix.fixes.OptionsKeyTranslationFix
- net.minecraft.util.datafix.fixes.OptionsLowerCaseLanguageFix
+ net.minecraft.util.datafix.fixes.PoiTypeRename
- net.minecraft.util.datafix.fixes.RecipesFix
+ net.minecraft.util.datafix.fixes.RecipesRenameningFix
- net.minecraft.util.datafix.fixes.References
+ net.minecraft.util.datafix.fixes.RenamedCoralFansFix
- net.minecraft.util.datafix.fixes.RenamedCoralFix
+ net.minecraft.util.datafix.fixes.ReorganizePoi
- net.minecraft.util.datafix.fixes.SavedDataVillageCropFix
+ net.minecraft.util.datafix.fixes.SimpleEntityRenameFix
- net.minecraft.util.datafix.fixes.SimplestEntityRenameFix
+ net.minecraft.util.datafix.fixes.StatsCounterFix
- net.minecraft.util.datafix.fixes.StructureReferenceCountFix
- net.minecraft.util.datafix.OminousBannerBlockEntityRenameFix
+ net.minecraft.util.datafix.OminousBannerRenameFix
+ net.minecraft.util.Deserializer
- net.minecraft.util.FrameTimer
+ net.minecraft.util.GsonHelper
- net.minecraft.util.HttpUtil
+ net.minecraft.util.InsensitiveStringMap
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
- net.minecraft.util.SmoothDouble
+ net.minecraft.util.StringRepresentable
- net.minecraft.util.StringUtil
+ net.minecraft.util.Tuple
- net.minecraft.util.Unit
+ net.minecraft.util.VisibleForDebug
- net.minecraft.util.WeighedRandom
+ net.minecraft.util.WeighedRandom$WeighedRandomItem
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.mojang.math.Vector3f +3P -1P
```
```
XXX.core.dispenser.DispenseItemBehavior$11 -1M
```
```
XXX.core.dispenser.DispenseItemBehavior$20 -1M | -1P
```
```
XXX.minecraft.world.InteractionResult +2M | +1P
```
```
XXX.world.entity.Entity +3M -3M
```
```
XXX.world.entity.LivingEntity +1M
```
```
XXX.entity.projectile.AbstractHurtingProjectile +1M | -1P
```
```
XXX.level.block.BarrelBlock +1M -1M
```
```
XXX.level.block.BeaconBlock +1M -1M
```
```
XXX.level.block.BeehiveBlock +1M -1M
```
```
XXX.level.block.BellBlock +1M -1M
```
```
XXX.level.block.BrewingStandBlock +1M -1M
```
```
XXX.level.block.ButtonBlock +1M -1M
```
```
XXX.level.block.CampfireBlock +1M -1M
```
```
XXX.level.block.CartographyTableBlock +1M -1M
```
```
XXX.level.block.CauldronBlock +1M -1M
```
```
XXX.level.block.ComparatorBlock +1M -1M
```
```
XXX.level.block.DoorBlock +1M -1M
```
```
XXX.level.block.FenceGateBlock +1M -1M
```
```
XXX.level.block.HopperBlock +1M -1M
```
```
XXX.level.block.JukeboxBlock +1M -1M
```
```
XXX.level.block.LeverBlock +1M -1M
```
```
XXX.level.block.NoteBlock +1M -1M
```
```
XXX.level.block.RedStoneOreBlock +1M -1M
```
```
XXX.level.block.RepeaterBlock +1M -1M
```
```
XXX.level.block.StructureBlock +1M -1M
```
```
XXX.level.block.SweetBerryBushBlock +1M -1M
```
```
XXX.level.block.TntBlock +1M -1M
```
```
XXX.level.block.TrapDoorBlock +1M -1M
```
```
XXX.block.piston.MovingPistonBlock +1M -1M
```
```
XXX.block.piston.PistonMovingBlockEntity$1 +1P
```
```
XXX.levelgen.structure.StructureStart +1M
```

</details>






































































































































































<details>
<summary>
net.minecraft.core.dispenser.DispenseItemBehavior$11
</summary>

```diff
+ void lambda$execute$0(ItemStack,SmallFireball)
```

</details>




<details>
<summary>
net.minecraft.core.dispenser.DispenseItemBehavior$20
</summary>

```diff
+ ItemStack takeLiquid(BlockSource,ItemStack,ItemStack)
```

</details>
















































<details>
<summary>
net.minecraft.world.InteractionResult
</summary>

```diff
- boolean consumesAction()
- boolean shouldSwing()
```

</details>
















<details>
<summary>
net.minecraft.world.entity.Entity
</summary>

```diff
- float getBlockJumpFactor()
- float getBlockSpeedFactor()
+ float getJumpFactor()
+ float getSpeedFactor()
- void reapplyPosition()
+ void refreshBoundingBox()
```

</details>






<details>
<summary>
net.minecraft.world.entity.LivingEntity
</summary>

```diff
- void swing(InteractionHand,boolean)
```

</details>
































































































































































































































































































<details>
<summary>
net.minecraft.world.entity.projectile.AbstractHurtingProjectile
</summary>

```diff
- void onHit(HitResult)
```

</details>
















































































































































































































































































<details>
<summary>
net.minecraft.world.level.block.BarrelBlock
</summary>

```diff
+ boolean use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>




<details>
<summary>
net.minecraft.world.level.block.BeaconBlock
</summary>

```diff
+ boolean use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.BeehiveBlock
</summary>

```diff
+ boolean use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BellBlock
</summary>

```diff
+ boolean use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>





<details>
<summary>
net.minecraft.world.level.block.BrewingStandBlock
</summary>

```diff
+ boolean use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.ButtonBlock
</summary>

```diff
+ boolean use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.CampfireBlock
</summary>

```diff
+ boolean use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CartographyTableBlock
</summary>

```diff
+ boolean use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CauldronBlock
</summary>

```diff
+ boolean use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>





<details>
<summary>
net.minecraft.world.level.block.ComparatorBlock
</summary>

```diff
+ boolean use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>










<details>
<summary>
net.minecraft.world.level.block.DoorBlock
</summary>

```diff
+ boolean use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>








<details>
<summary>
net.minecraft.world.level.block.FenceGateBlock
</summary>

```diff
+ boolean use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>








<details>
<summary>
net.minecraft.world.level.block.HopperBlock
</summary>

```diff
+ boolean use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>



<details>
<summary>
net.minecraft.world.level.block.JukeboxBlock
</summary>

```diff
+ boolean use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>




<details>
<summary>
net.minecraft.world.level.block.LeverBlock
</summary>

```diff
+ boolean use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>







<details>
<summary>
net.minecraft.world.level.block.NoteBlock
</summary>

```diff
+ boolean use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>








<details>
<summary>
net.minecraft.world.level.block.RedStoneOreBlock
</summary>

```diff
+ boolean use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>



<details>
<summary>
net.minecraft.world.level.block.RepeaterBlock
</summary>

```diff
+ boolean use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>



















<details>
<summary>
net.minecraft.world.level.block.StructureBlock
</summary>

```diff
+ boolean use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.SweetBerryBushBlock
</summary>

```diff
+ boolean use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.TntBlock
</summary>

```diff
+ boolean use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.TrapDoorBlock
</summary>

```diff
+ boolean use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>














































<details>
<summary>
net.minecraft.world.level.block.piston.MovingPistonBlock
</summary>

```diff
+ boolean use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>



































































































































































































































































<details>
<summary>
net.minecraft.world.level.levelgen.structure.StructureStart
</summary>

```diff
- int getReferences()
```

</details>
















































































































































































































































<h2>Client</h2>
<details>
<summary>
Classes
</summary>

```diff
+ net.minecraft.client.renderer.banner.BannerTextures
- net.minecraft.client.renderer.banner.BannerTextures$1
+ net.minecraft.client.renderer.banner.BannerTextures$TextureCache
- net.minecraft.client.renderer.banner.BannerTextures$TimestampedBannerTexture
+ net.minecraft.client.renderer.banner.package-info
- net.minecraft.client.renderer.block.BlockModelShaper
+ net.minecraft.client.renderer.block.BlockRenderDispatcher
- net.minecraft.client.renderer.block.BlockRenderDispatcher$1
+ net.minecraft.client.renderer.block.LiquidBlockRenderer
+ net.minecraft.client.renderer.block.model.BakedQuad
- net.minecraft.client.renderer.block.model.BlockElement
+ net.minecraft.client.renderer.block.model.BlockElement$1
- net.minecraft.client.renderer.block.model.BlockElement$Deserializer
+ net.minecraft.client.renderer.block.model.BlockElementFace
- net.minecraft.client.renderer.block.model.BlockElementFace$Deserializer
+ net.minecraft.client.renderer.block.model.BlockElementRotation
- net.minecraft.client.renderer.block.model.BlockFaceUV
+ net.minecraft.client.renderer.block.model.BlockFaceUV$Deserializer
- net.minecraft.client.renderer.block.model.BlockModel
+ net.minecraft.client.renderer.block.model.BlockModel$1
- net.minecraft.client.renderer.block.model.BlockModel$Bookkeep
+ net.minecraft.client.renderer.block.model.BlockModel$Deserializer
- net.minecraft.client.renderer.block.model.BlockModel$LoopException
+ net.minecraft.client.renderer.block.model.BlockModelDefinition
- net.minecraft.client.renderer.block.model.BlockModelDefinition$Context
+ net.minecraft.client.renderer.block.model.BlockModelDefinition$Deserializer
- net.minecraft.client.renderer.block.model.BlockModelDefinition$MissingVariantException
+ net.minecraft.client.renderer.block.model.FaceBakery
- net.minecraft.client.renderer.block.model.FaceBakery$1
+ net.minecraft.client.renderer.block.model.ItemModelGenerator
- net.minecraft.client.renderer.block.model.ItemModelGenerator$1
+ net.minecraft.client.renderer.block.model.ItemModelGenerator$Span
- net.minecraft.client.renderer.block.model.ItemModelGenerator$SpanFacing
+ net.minecraft.client.renderer.block.model.ItemOverride
- net.minecraft.client.renderer.block.model.ItemOverride$Deserializer
+ net.minecraft.client.renderer.block.model.ItemOverrides
- net.minecraft.client.renderer.block.model.ItemTransform
+ net.minecraft.client.renderer.block.model.ItemTransform$Deserializer
- net.minecraft.client.renderer.block.model.ItemTransforms
+ net.minecraft.client.renderer.block.model.ItemTransforms$1
- net.minecraft.client.renderer.block.model.ItemTransforms$Deserializer
+ net.minecraft.client.renderer.block.model.ItemTransforms$TransformType
- net.minecraft.client.renderer.block.model.multipart.AndCondition
+ net.minecraft.client.renderer.block.model.multipart.Condition
- net.minecraft.client.renderer.block.model.multipart.KeyValueCondition
+ net.minecraft.client.renderer.block.model.multipart.MultiPart
- net.minecraft.client.renderer.block.model.multipart.MultiPart$Deserializer
+ net.minecraft.client.renderer.block.model.multipart.OrCondition
- net.minecraft.client.renderer.block.model.multipart.package-info
- net.minecraft.client.renderer.block.model.multipart.Selector
+ net.minecraft.client.renderer.block.model.multipart.Selector$Deserializer
- net.minecraft.client.renderer.block.model.MultiVariant
+ net.minecraft.client.renderer.block.model.MultiVariant$Deserializer
+ net.minecraft.client.renderer.block.model.package-info
- net.minecraft.client.renderer.block.model.Variant
+ net.minecraft.client.renderer.block.model.Variant$Deserializer
- net.minecraft.client.renderer.block.ModelBlockRenderer
+ net.minecraft.client.renderer.block.ModelBlockRenderer$1
- net.minecraft.client.renderer.block.ModelBlockRenderer$AdjacencyInfo
+ net.minecraft.client.renderer.block.ModelBlockRenderer$AmbientOcclusionFace
- net.minecraft.client.renderer.block.ModelBlockRenderer$AmbientVertexRemap
+ net.minecraft.client.renderer.block.ModelBlockRenderer$Cache
- net.minecraft.client.renderer.block.ModelBlockRenderer$Cache$1
+ net.minecraft.client.renderer.block.ModelBlockRenderer$Cache$2
- net.minecraft.client.renderer.block.ModelBlockRenderer$SizeInfo
- net.minecraft.client.renderer.block.package-info
+ net.minecraft.client.renderer.block.statemap.package-info
- net.minecraft.client.renderer.blockentity.BannerRenderer
+ net.minecraft.client.renderer.blockentity.BeaconRenderer
- net.minecraft.client.renderer.blockentity.BedRenderer
+ net.minecraft.client.renderer.blockentity.BellRenderer
- net.minecraft.client.renderer.blockentity.BlockEntityRenderDispatcher
+ net.minecraft.client.renderer.blockentity.BlockEntityRenderer
- net.minecraft.client.renderer.blockentity.CampfireRenderer
+ net.minecraft.client.renderer.blockentity.ChestRenderer
- net.minecraft.client.renderer.blockentity.ChestRenderer$1
- net.minecraft.client.renderer.entity.layers.EyesLayer
+ net.minecraft.client.renderer.entity.layers.FoxHeldItemLayer
- net.minecraft.client.renderer.entity.layers.HorseArmorLayer
+ net.minecraft.client.renderer.entity.layers.HumanoidArmorLayer
- net.minecraft.client.renderer.entity.layers.HumanoidArmorLayer$1
+ net.minecraft.client.renderer.entity.layers.IronGolemCrackinessLayer
- net.minecraft.client.renderer.entity.layers.IronGolemFlowerLayer
+ net.minecraft.client.renderer.entity.layers.ItemInHandLayer
- net.minecraft.client.renderer.entity.layers.LlamaDecorLayer
+ net.minecraft.client.renderer.entity.layers.MushroomCowMushroomLayer
- net.minecraft.client.renderer.entity.layers.PandaHoldsItemLayer
+ net.minecraft.client.renderer.entity.layers.ParrotOnShoulderLayer
- net.minecraft.client.renderer.entity.layers.PhantomEyesLayer
+ net.minecraft.client.renderer.entity.layers.PigSaddleLayer
- net.minecraft.client.renderer.entity.layers.RenderLayer
+ net.minecraft.client.renderer.entity.layers.SheepFurLayer
- net.minecraft.client.renderer.entity.layers.ShulkerHeadLayer
+ net.minecraft.client.renderer.entity.layers.ShulkerHeadLayer$1
- net.minecraft.client.renderer.entity.layers.SlimeOuterLayer
+ net.minecraft.client.renderer.entity.layers.SnowGolemHeadLayer
- net.minecraft.client.renderer.entity.layers.SpiderEyesLayer
+ net.minecraft.client.renderer.entity.layers.SpinAttackEffectLayer
- net.minecraft.client.renderer.ItemBlockRenderTypes
+ net.minecraft.client.renderer.ItemInHandRenderer
- net.minecraft.client.renderer.ItemInHandRenderer$1
+ net.minecraft.client.renderer.ItemModelShaper
- net.minecraft.client.renderer.LevelRenderer
+ net.minecraft.client.renderer.LevelRenderer$1
- net.minecraft.client.renderer.LevelRenderer$RenderChunkInfo
+ net.minecraft.client.renderer.LightTexture
- net.minecraft.client.renderer.MultiBufferSource
+ net.minecraft.client.renderer.MultiBufferSource$BufferSource
- net.minecraft.client.renderer.OutlineBufferSource
+ net.minecraft.client.renderer.OutlineBufferSource$1
- net.minecraft.client.renderer.OutlineBufferSource$EntityOutlineGenerator
+ net.minecraft.client.renderer.PanoramaRenderer
- net.minecraft.client.renderer.PostChain
+ net.minecraft.client.renderer.PostPass
- net.minecraft.client.renderer.Rect2i
+ net.minecraft.client.renderer.RenderBuffers
- net.minecraft.client.renderer.RenderStateShard
+ net.minecraft.client.renderer.RenderStateShard$AlphaStateShard
- net.minecraft.client.renderer.RenderStateShard$BooleanStateShard
+ net.minecraft.client.renderer.RenderStateShard$CullStateShard
- net.minecraft.client.renderer.RenderStateShard$DepthTestStateShard
+ net.minecraft.client.renderer.RenderStateShard$DiffuseLightingStateShard
- net.minecraft.client.renderer.RenderStateShard$FogStateShard
+ net.minecraft.client.renderer.RenderStateShard$LayeringStateShard
- net.minecraft.client.renderer.RenderStateShard$LightmapStateShard
+ net.minecraft.client.renderer.RenderStateShard$LineStateShard
- net.minecraft.client.renderer.RenderStateShard$OffsetTexturingStateShard
+ net.minecraft.client.renderer.RenderStateShard$TextureStateShard
- net.minecraft.client.renderer.RenderStateShard$TexturingStateShard
+ net.minecraft.client.renderer.RenderStateShard$TransparencyStateShard
- net.minecraft.client.renderer.RenderStateShard$WriteMaskStateShard
+ net.minecraft.client.renderer.RenderType
- net.minecraft.client.renderer.RenderType$1
+ net.minecraft.client.renderer.RenderType$CompositeRenderType
- net.minecraft.client.renderer.RenderType$CompositeState
+ net.minecraft.client.renderer.RenderType$CompositeState$CompositeStateBuilder
- net.minecraft.client.renderer.ScreenEffectRenderer
+ net.minecraft.client.renderer.ViewArea
- net.minecraft.client.renderer.VirtualScreen
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
- net.minecraft.data.loot.package-info
- net.minecraft.data.Main
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
+ net.minecraft.network.protocol.game.DebugPackets
- net.minecraft.network.protocol.game.DebugVillagerNameGenerator
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
+ net.minecraft.realms.AbstractRealmsButton
- net.minecraft.realms.DisconnectedRealmsScreen
+ net.minecraft.realms.DisconnectedRealmsScreen$1
- net.minecraft.realms.package-info
+ net.minecraft.realms.pluginapi.LoadedRealmsPlugin
+ net.minecraft.realms.pluginapi.package-info
- net.minecraft.realms.pluginapi.RealmsPlugin
- net.minecraft.realms.RealmListEntry
+ net.minecraft.realms.Realms
- net.minecraft.realms.RealmsAbstractButtonProxy
+ net.minecraft.realms.RealmsAnvilLevelStorageSource
- net.minecraft.realms.RealmsBridge
+ net.minecraft.realms.RealmsButton
- net.minecraft.realms.RealmsButtonProxy
+ net.minecraft.realms.RealmsClickableScrolledSelectionList
- net.minecraft.realms.RealmsClickableScrolledSelectionListProxy
+ net.minecraft.realms.RealmsConfirmResultListener
- net.minecraft.realms.RealmsConnect
+ net.minecraft.realms.RealmsConnect$1
- net.minecraft.realms.RealmsDefaultVertexFormat
+ net.minecraft.realms.RealmsEditBox
- net.minecraft.realms.RealmsGuiEventListener
+ net.minecraft.realms.RealmsLabel
- net.minecraft.realms.RealmsLabelProxy
+ net.minecraft.realms.RealmsLevelSummary
- net.minecraft.realms.RealmsMth
+ net.minecraft.realms.RealmsObjectSelectionList
- net.minecraft.realms.RealmsObjectSelectionListProxy
+ net.minecraft.realms.RealmsScreen
- net.minecraft.realms.RealmsScreenProxy
+ net.minecraft.realms.RealmsScrolledSelectionList
- net.minecraft.realms.RealmsScrolledSelectionListProxy
+ net.minecraft.realms.RealmsServerAddress
- net.minecraft.realms.RealmsSharedConstants
+ net.minecraft.realms.RealmsSimpleScrolledSelectionList
- net.minecraft.realms.RealmsSimpleScrolledSelectionListProxy
+ net.minecraft.realms.RealmsSliderButton
- net.minecraft.realms.RealmsSliderButtonProxy
+ net.minecraft.realms.RealmsVertexFormat
- net.minecraft.realms.RealmsVertexFormatElement
+ net.minecraft.realms.RepeatedNarrator
- net.minecraft.realms.RepeatedNarrator$Params
+ net.minecraft.realms.Tezzelator
+ net.minecraft.recipebook.package-info
- net.minecraft.recipebook.PlaceRecipe
+ net.minecraft.recipebook.ServerPlaceRecipe
- net.minecraft.recipebook.ServerPlaceSmeltingRecipe
- net.minecraft.resources.package-info
- net.minecraft.resources.ResourceLocation
+ net.minecraft.resources.ResourceLocation$Serializer
+ net.minecraft.server.Bootstrap
- net.minecraft.server.bossevents.CustomBossEvent
+ net.minecraft.server.bossevents.CustomBossEvents
- net.minecraft.server.bossevents.package-info
- net.minecraft.server.ChainedJsonException
+ net.minecraft.server.ChainedJsonException$1
- net.minecraft.server.ChainedJsonException$Entry
+ net.minecraft.server.commands.AdvancementCommands
- net.minecraft.server.commands.AdvancementCommands$1
+ net.minecraft.server.commands.AdvancementCommands$Action
- net.minecraft.server.commands.AdvancementCommands$Action$1
+ net.minecraft.server.commands.AdvancementCommands$Action$2
- net.minecraft.server.commands.AdvancementCommands$Mode
+ net.minecraft.server.commands.BanIpCommands
- net.minecraft.server.commands.BanListCommands
+ net.minecraft.server.commands.BanPlayerCommands
- net.minecraft.server.commands.BossBarCommands
+ net.minecraft.server.commands.ClearInventoryCommands
- net.minecraft.server.commands.CloneCommands
+ net.minecraft.server.commands.CloneCommands$CloneBlockInfo
- net.minecraft.server.commands.CloneCommands$Mode
+ net.minecraft.server.commands.data.BlockDataAccessor
- net.minecraft.server.commands.data.BlockDataAccessor$1
+ net.minecraft.server.commands.data.DataAccessor
- net.minecraft.server.commands.data.DataCommands
+ net.minecraft.server.commands.data.DataCommands$DataManipulator
- net.minecraft.server.commands.data.DataCommands$DataManipulatorDecorator
+ net.minecraft.server.commands.data.DataCommands$DataProvider
- net.minecraft.server.commands.data.EntityDataAccessor
+ net.minecraft.server.commands.data.EntityDataAccessor$1
- net.minecraft.server.commands.data.package-info
- net.minecraft.server.commands.data.StorageDataAccessor
+ net.minecraft.server.commands.data.StorageDataAccessor$1
+ net.minecraft.server.commands.DataPackCommand
- net.minecraft.server.commands.DataPackCommand$Inserter
- net.minecraft.server.commands.DebugCommand
+ net.minecraft.server.commands.DebugPathCommand
- net.minecraft.server.commands.DefaultGameModeCommands
+ net.minecraft.server.commands.DeOpCommands
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
- net.minecraft.server.commands.LocateCommand
+ net.minecraft.server.commands.LootCommand
- net.minecraft.server.commands.LootCommand$Callback
+ net.minecraft.server.commands.LootCommand$DropConsumer
- net.minecraft.server.commands.LootCommand$TailProvider
+ net.minecraft.server.commands.MsgCommand
- net.minecraft.server.commands.OpCommand
+ net.minecraft.server.commands.package-info
+ net.minecraft.server.commands.PardonCommand
- net.minecraft.server.commands.PardonIpCommand
+ net.minecraft.server.commands.ParticleCommand
- net.minecraft.server.commands.PlaySoundCommand
+ net.minecraft.server.commands.PublishCommand
- net.minecraft.server.commands.RaidCommand
+ net.minecraft.server.commands.RecipeCommand
- net.minecraft.server.commands.ReloadCommand
+ net.minecraft.server.commands.ReplaceItemCommand
- net.minecraft.server.commands.SaveAllCommand
+ net.minecraft.server.commands.SaveOffCommand
- net.minecraft.server.commands.SaveOnCommand
+ net.minecraft.server.commands.SayCommand
- net.minecraft.server.commands.ScheduleCommand
+ net.minecraft.server.commands.ScoreboardCommand
- net.minecraft.server.commands.SeedCommand
+ net.minecraft.server.commands.SetBlockCommand
- net.minecraft.server.commands.SetBlockCommand$Filter
+ net.minecraft.server.commands.SetBlockCommand$Mode
- net.minecraft.server.commands.SetPlayerIdleTimeoutCommand
+ net.minecraft.server.commands.SetSpawnCommand
- net.minecraft.server.commands.SetWorldSpawnCommand
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
- net.minecraft.server.commands.TellRawCommand
+ net.minecraft.server.commands.TimeCommand
- net.minecraft.server.commands.TitleCommand
+ net.minecraft.server.commands.TriggerCommand
- net.minecraft.server.commands.WeatherCommand
+ net.minecraft.server.commands.WhitelistCommand
- net.minecraft.server.commands.WorldBorderCommand
+ net.minecraft.server.ConsoleInput
- net.minecraft.server.ConsoleInputSource
+ net.minecraft.server.DebugLoggedPrintStream
- net.minecraft.server.dedicated.DedicatedPlayerList
+ net.minecraft.server.dedicated.DedicatedServer
- net.minecraft.server.dedicated.DedicatedServer$1
+ net.minecraft.server.dedicated.DedicatedServer$2
- net.minecraft.server.dedicated.DedicatedServerProperties
+ net.minecraft.server.dedicated.DedicatedServerSettings
+ net.minecraft.server.dedicated.package-info
- net.minecraft.server.dedicated.ServerWatchdog
+ net.minecraft.server.dedicated.ServerWatchdog$1
- net.minecraft.server.dedicated.Settings
+ net.minecraft.server.dedicated.Settings$1
- net.minecraft.server.dedicated.Settings$MutableValue
- net.minecraft.server.Eula
- net.minecraft.server.gui.MinecraftServerGui
+ net.minecraft.server.gui.MinecraftServerGui$1
- net.minecraft.server.gui.MinecraftServerGui$2
+ net.minecraft.server.gui.package-info
+ net.minecraft.server.gui.PlayerListComponent
- net.minecraft.server.gui.StatsComponent
- net.minecraft.server.level.BlockDestructionProgress
+ net.minecraft.server.level.ChunkHolder
- net.minecraft.server.level.ChunkHolder$1
+ net.minecraft.server.level.ChunkHolder$ChunkLoadingFailure
- net.minecraft.server.level.ChunkHolder$ChunkLoadingFailure$1
+ net.minecraft.server.level.ChunkHolder$FullChunkStatus
- net.minecraft.server.level.ChunkHolder$LevelChangeListener
+ net.minecraft.server.level.ChunkHolder$PlayerProvider
- net.minecraft.server.level.ChunkMap
+ net.minecraft.server.level.ChunkMap$1
- net.minecraft.server.level.ChunkMap$2
+ net.minecraft.server.level.ChunkMap$DistanceManager
- net.minecraft.server.level.ChunkMap$TrackedEntity
+ net.minecraft.server.level.ChunkTaskPriorityQueue
- net.minecraft.server.level.ChunkTaskPriorityQueueSorter
+ net.minecraft.server.level.ChunkTaskPriorityQueueSorter$1
- net.minecraft.server.level.ChunkTaskPriorityQueueSorter$Message
+ net.minecraft.server.level.ChunkTaskPriorityQueueSorter$Release
- net.minecraft.server.level.ChunkTracker
+ net.minecraft.server.level.ColumnPos
- net.minecraft.server.level.DemoMode
+ net.minecraft.server.level.DerivedServerLevel
- net.minecraft.server.level.DistanceManager
+ net.minecraft.server.level.DistanceManager$ChunkTicketTracker
- net.minecraft.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
+ net.minecraft.server.level.DistanceManager$PlayerTicketTracker
- net.minecraft.server.level.FeatureSimulator
+ net.minecraft.server.level.package-info
+ net.minecraft.server.level.PlayerMap
- net.minecraft.server.level.progress.ChunkProgressListener
+ net.minecraft.server.level.progress.ChunkProgressListenerFactory
- net.minecraft.server.level.progress.LoggerChunkProgressListener
+ net.minecraft.server.level.progress.package-info
+ net.minecraft.server.level.progress.ProcessorChunkProgressListener
- net.minecraft.server.level.progress.StoringChunkProgressListener
- net.minecraft.server.level.SectionTracker
+ net.minecraft.server.level.ServerBossEvent
- net.minecraft.server.level.ServerChunkCache
+ net.minecraft.server.level.ServerChunkCache$1
- net.minecraft.server.level.ServerChunkCache$MainThreadExecutor
+ net.minecraft.server.level.ServerEntity
- net.minecraft.server.level.ServerLevel
+ net.minecraft.server.level.ServerPlayer
- net.minecraft.server.level.ServerPlayerGameMode
+ net.minecraft.server.level.ThreadedLevelLightEngine
- net.minecraft.server.level.ThreadedLevelLightEngine$TaskType
+ net.minecraft.server.level.Ticket
- net.minecraft.server.level.TicketType
+ net.minecraft.server.level.WorldGenRegion
- net.minecraft.server.level.WorldGenTickList
+ net.minecraft.server.LoggedPrintStream
- net.minecraft.server.MinecraftServer
+ net.minecraft.server.MinecraftServer$1
- net.minecraft.server.MinecraftServer$2
+ net.minecraft.server.MinecraftServer$3
- net.minecraft.server.network.LegacyQueryHandler
+ net.minecraft.server.network.MemoryServerHandshakePacketListenerImpl
- net.minecraft.server.network.package-info
- net.minecraft.server.network.ServerConnectionListener
+ net.minecraft.server.network.ServerConnectionListener$1
- net.minecraft.server.network.ServerConnectionListener$2
+ net.minecraft.server.network.ServerConnectionListener$LatencySimulator
- net.minecraft.server.network.ServerGamePacketListenerImpl
+ net.minecraft.server.network.ServerGamePacketListenerImpl$1
- net.minecraft.server.network.ServerHandshakePacketListenerImpl
+ net.minecraft.server.network.ServerHandshakePacketListenerImpl$1
- net.minecraft.server.network.ServerLoginPacketListenerImpl
+ net.minecraft.server.network.ServerLoginPacketListenerImpl$1
- net.minecraft.server.network.ServerLoginPacketListenerImpl$State
+ net.minecraft.server.network.ServerStatusPacketListenerImpl
+ net.minecraft.server.package-info
- net.minecraft.server.packs.AbstractResourcePack
+ net.minecraft.server.packs.FileResourcePack
- net.minecraft.server.packs.FolderResourcePack
+ net.minecraft.server.packs.metadata.MetadataSectionSerializer
- net.minecraft.server.packs.metadata.pack.package-info
- net.minecraft.server.packs.metadata.pack.PackMetadataSection
+ net.minecraft.server.packs.metadata.pack.PackMetadataSectionSerializer
+ net.minecraft.server.packs.metadata.package-info
+ net.minecraft.server.packs.Pack
- net.minecraft.server.packs.package-info
- net.minecraft.server.packs.PackType
+ net.minecraft.server.packs.repository.FolderRepositorySource
+ net.minecraft.server.packs.repository.package-info
- net.minecraft.server.packs.repository.PackCompatibility
+ net.minecraft.server.packs.repository.PackRepository
- net.minecraft.server.packs.repository.RepositorySource
+ net.minecraft.server.packs.repository.ServerPacksSource
- net.minecraft.server.packs.repository.UnopenedPack
+ net.minecraft.server.packs.repository.UnopenedPack$Position
- net.minecraft.server.packs.repository.UnopenedPack$UnopenedPackConstructor
+ net.minecraft.server.packs.ResourcePackFileNotFoundException
- net.minecraft.server.packs.resources.FallbackResourceManager
+ net.minecraft.server.packs.resources.FallbackResourceManager$LeakedResourceWarningInputStream
+ net.minecraft.server.packs.resources.package-info
- net.minecraft.server.packs.resources.PreparableReloadListener
+ net.minecraft.server.packs.resources.PreparableReloadListener$PreparationBarrier
- net.minecraft.server.packs.resources.ProfiledReloadInstance
+ net.minecraft.server.packs.resources.ProfiledReloadInstance$1
- net.minecraft.server.packs.resources.ProfiledReloadInstance$State
- net.minecraft.server.packs.resources.ReloadableResourceManager
+ net.minecraft.server.packs.resources.ReloadInstance
+ net.minecraft.server.packs.resources.Resource
- net.minecraft.server.packs.resources.ResourceManager
+ net.minecraft.server.packs.resources.ResourceManagerReloadListener
- net.minecraft.server.packs.resources.SimpleJsonResourceReloadListener
+ net.minecraft.server.packs.resources.SimplePreparableReloadListener
+ net.minecraft.server.packs.resources.SimpleReloadableResourceManager
- net.minecraft.server.packs.resources.SimpleReloadInstance
+ net.minecraft.server.packs.resources.SimpleReloadInstance$1
- net.minecraft.server.packs.resources.SimpleReloadInstance$StateFactory
- net.minecraft.server.packs.resources.SimpleResource
- net.minecraft.server.packs.VanillaPack
- net.minecraft.server.PlayerAdvancements
+ net.minecraft.server.PlayerAdvancements$1
- net.minecraft.server.players.BanListEntry
+ net.minecraft.server.players.GameProfileCache
- net.minecraft.server.players.GameProfileCache$1
+ net.minecraft.server.players.GameProfileCache$2
- net.minecraft.server.players.GameProfileCache$GameProfileInfo
+ net.minecraft.server.players.GameProfileCache$Serializer
- net.minecraft.server.players.IpBanList
+ net.minecraft.server.players.IpBanListEntry
- net.minecraft.server.players.OldUsersConverter
+ net.minecraft.server.players.OldUsersConverter$1
- net.minecraft.server.players.OldUsersConverter$2
+ net.minecraft.server.players.OldUsersConverter$3
- net.minecraft.server.players.OldUsersConverter$4
+ net.minecraft.server.players.OldUsersConverter$5
- net.minecraft.server.players.OldUsersConverter$ConversionError
+ net.minecraft.server.players.package-info
+ net.minecraft.server.players.PlayerList
- net.minecraft.server.players.PlayerList$1
+ net.minecraft.server.players.ServerOpList
- net.minecraft.server.players.ServerOpListEntry
+ net.minecraft.server.players.StoredUserEntry
- net.minecraft.server.players.StoredUserList
+ net.minecraft.server.players.StoredUserList$1
- net.minecraft.server.players.StoredUserList$Serializer
+ net.minecraft.server.players.UserBanList
- net.minecraft.server.players.UserBanListEntry
+ net.minecraft.server.players.UserWhiteList
- net.minecraft.server.players.UserWhiteListEntry
- net.minecraft.server.rcon.NetworkDataOutputStream
+ net.minecraft.server.rcon.package-info
+ net.minecraft.server.rcon.PktUtils
- net.minecraft.server.rcon.RconConsoleSource
- net.minecraft.server.rcon.thread.GenericThread
+ net.minecraft.server.rcon.thread.package-info
+ net.minecraft.server.rcon.thread.QueryThreadGs4
- net.minecraft.server.rcon.thread.QueryThreadGs4$RequestChallenge
+ net.minecraft.server.rcon.thread.RconClient
- net.minecraft.server.rcon.thread.RconThread
- net.minecraft.server.RunningOnDifferentThreadException
+ net.minecraft.server.ServerAdvancementManager
- net.minecraft.server.ServerFunctionManager
+ net.minecraft.server.ServerFunctionManager$QueuedCommand
- net.minecraft.server.ServerInterface
+ net.minecraft.server.ServerScoreboard
- net.minecraft.server.ServerScoreboard$Method
+ net.minecraft.server.TickTask
+ net.minecraft.sounds.package-info
- net.minecraft.sounds.SoundEvent
+ net.minecraft.sounds.SoundEvents
- net.minecraft.sounds.SoundSource
- net.minecraft.stats.package-info
- net.minecraft.stats.RecipeBook
+ net.minecraft.stats.ServerRecipeBook
- net.minecraft.stats.ServerStatsCounter
+ net.minecraft.stats.Stat
- net.minecraft.stats.StatFormatter
- net.minecraft.stats.Stats
+ net.minecraft.stats.StatsCounter
+ net.minecraft.stats.StatType
+ net.minecraft.tags.BlockTags
- net.minecraft.tags.BlockTags$Wrapper
+ net.minecraft.tags.EntityTypeTags
- net.minecraft.tags.EntityTypeTags$Wrapper
+ net.minecraft.tags.FluidTags
- net.minecraft.tags.FluidTags$Wrapper
+ net.minecraft.tags.ItemTags
- net.minecraft.tags.ItemTags$Wrapper
- net.minecraft.tags.package-info
+ net.minecraft.tags.SynchronizableTagCollection
- net.minecraft.tags.Tag
+ net.minecraft.tags.Tag$Builder
- net.minecraft.tags.Tag$Entry
+ net.minecraft.tags.Tag$TagEntry
- net.minecraft.tags.Tag$ValuesEntry
+ net.minecraft.tags.TagCollection
- net.minecraft.tags.TagManager
+ net.minecraft.tags.TagManager$Preparations
+ net.minecraft.util.BitStorage
- net.minecraft.util.ClassInstanceMultiMap
+ net.minecraft.util.CrudeIncrementalIntIdentityHashBiMap
- net.minecraft.util.Crypt
+ net.minecraft.util.CsvOutput
- net.minecraft.util.CsvOutput$1
+ net.minecraft.util.CsvOutput$Builder
- net.minecraft.util.datafix.DataFixers
+ net.minecraft.util.datafix.DataFixers$1
- net.minecraft.util.datafix.DataFixers$2
+ net.minecraft.util.datafix.DataFixTypes
+ net.minecraft.util.datafix.fixes.AddNewChoices
- net.minecraft.util.datafix.fixes.AdvancementsFix
+ net.minecraft.util.datafix.fixes.BedBlockEntityInjecter
- net.minecraft.util.datafix.fixes.BedItemColorFix
+ net.minecraft.util.datafix.fixes.BeehivePoiRenameFix
- net.minecraft.util.datafix.fixes.BiomeFix
+ net.minecraft.util.datafix.fixes.BlockEntityBannerColorFix
- net.minecraft.util.datafix.fixes.BlockEntityBlockStateFix
+ net.minecraft.util.datafix.fixes.BlockEntityCustomNameToComponentFix
- net.minecraft.util.datafix.fixes.BlockEntityIdFix
+ net.minecraft.util.datafix.fixes.BlockEntityJukeboxFix
- net.minecraft.util.datafix.fixes.BlockEntityKeepPacked
+ net.minecraft.util.datafix.fixes.BlockEntityShulkerBoxColorFix
- net.minecraft.util.datafix.fixes.BlockEntitySignTextStrictJsonFix
+ net.minecraft.util.datafix.fixes.BlockEntitySignTextStrictJsonFix$1
- net.minecraft.util.datafix.fixes.BlockNameFlatteningFix
+ net.minecraft.util.datafix.fixes.BlockRenameFix
- net.minecraft.util.datafix.fixes.BlockRenameFix$1
+ net.minecraft.util.datafix.fixes.BlockStateData
- net.minecraft.util.datafix.fixes.BlockStateStructureTemplateFix
+ net.minecraft.util.datafix.fixes.CatTypeFix
- net.minecraft.util.datafix.fixes.ChunkBiomeFix
+ net.minecraft.util.datafix.fixes.ChunkLightRemoveFix
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$1
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$DataLayer
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction$Axis
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Direction$AxisDirection
- net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$Section
+ net.minecraft.util.datafix.fixes.ChunkPalettedStorageFix$UpgradeChunk
- net.minecraft.util.datafix.fixes.ChunkStatusFix
+ net.minecraft.util.datafix.fixes.ChunkStatusFix2
- net.minecraft.util.datafix.fixes.ChunkStructuresTemplateRenameFix
+ net.minecraft.util.datafix.fixes.ChunkToProtochunkFix
- net.minecraft.util.datafix.fixes.ColorlessShulkerEntityFix
+ net.minecraft.util.datafix.fixes.DyeItemRenameFix
- net.minecraft.util.datafix.fixes.EntityArmorStandSilentFix
+ net.minecraft.util.datafix.fixes.EntityBlockStateFix
- net.minecraft.util.datafix.fixes.EntityCatSplitFix
+ net.minecraft.util.datafix.fixes.EntityCodSalmonFix
- net.minecraft.util.datafix.fixes.EntityCustomNameToComponentFix
+ net.minecraft.util.datafix.fixes.EntityElderGuardianSplitFix
- net.minecraft.util.datafix.fixes.EntityEquipmentToArmorAndHandFix
+ net.minecraft.util.datafix.fixes.EntityHealthFix
- net.minecraft.util.datafix.fixes.EntityHorseSaddleFix
+ net.minecraft.util.datafix.fixes.EntityHorseSplitFix
- net.minecraft.util.datafix.fixes.EntityIdFix
+ net.minecraft.util.datafix.fixes.EntityItemFrameDirectionFix
- net.minecraft.util.datafix.fixes.EntityMinecartIdentifiersFix
+ net.minecraft.util.datafix.fixes.EntityPaintingItemFrameDirectionFix
- net.minecraft.util.datafix.fixes.EntityPaintingMotiveFix
+ net.minecraft.util.datafix.fixes.EntityPufferfishRenameFix
- net.minecraft.util.datafix.fixes.EntityRavagerRenameFix
+ net.minecraft.util.datafix.fixes.EntityRedundantChanceTagsFix
- net.minecraft.util.datafix.fixes.EntityRenameFix
+ net.minecraft.util.datafix.fixes.EntityRidingToPassengersFix
- net.minecraft.util.datafix.fixes.EntityShulkerColorFix
+ net.minecraft.util.datafix.fixes.EntitySkeletonSplitFix
- net.minecraft.util.datafix.fixes.EntityStringUuidFix
+ net.minecraft.util.datafix.fixes.EntityTheRenameningFix
- net.minecraft.util.datafix.fixes.EntityTippedArrowFix
+ net.minecraft.util.datafix.fixes.EntityWolfColorFix
- net.minecraft.util.datafix.fixes.EntityZombieSplitFix
+ net.minecraft.util.datafix.fixes.EntityZombieVillagerTypeFix
- net.minecraft.util.datafix.fixes.ForcePoiRebuild
+ net.minecraft.util.datafix.fixes.HeightmapRenamingFix
- net.minecraft.util.datafix.fixes.IglooMetadataRemovalFix
+ net.minecraft.util.datafix.fixes.ItemBannerColorFix
- net.minecraft.util.datafix.fixes.ItemCustomNameToComponentFix
+ net.minecraft.util.datafix.fixes.ItemIdFix
- net.minecraft.util.datafix.fixes.ItemLoreFix
+ net.minecraft.util.datafix.fixes.ItemPotionFix
- net.minecraft.util.datafix.fixes.ItemRenameFix
+ net.minecraft.util.datafix.fixes.ItemRenameFix$1
- net.minecraft.util.datafix.fixes.ItemShulkerBoxColorFix
+ net.minecraft.util.datafix.fixes.ItemSpawnEggFix
- net.minecraft.util.datafix.fixes.ItemStackEnchantmentNamesFix
+ net.minecraft.util.datafix.fixes.ItemStackMapIdFix
- net.minecraft.util.datafix.fixes.ItemStackSpawnEggFix
+ net.minecraft.util.datafix.fixes.ItemStackTheFlatteningFix
- net.minecraft.util.datafix.fixes.ItemWaterPotionFix
+ net.minecraft.util.datafix.fixes.ItemWrittenBookPagesStrictJsonFix
- net.minecraft.util.datafix.fixes.LeavesFix
+ net.minecraft.util.datafix.fixes.LeavesFix$LeavesSection
- net.minecraft.util.datafix.fixes.LeavesFix$Section
+ net.minecraft.util.datafix.fixes.LevelDataGeneratorOptionsFix
- net.minecraft.util.datafix.fixes.LevelFlatGeneratorInfoFix
+ net.minecraft.util.datafix.fixes.MapIdFix
- net.minecraft.util.datafix.fixes.MobSpawnerEntityIdentifiersFix
+ net.minecraft.util.datafix.fixes.NamedEntityFix
- net.minecraft.util.datafix.fixes.NewVillageFix
+ net.minecraft.util.datafix.fixes.ObjectiveDisplayNameFix
- net.minecraft.util.datafix.fixes.ObjectiveRenderTypeFix
+ net.minecraft.util.datafix.fixes.OptionsAddTextBackgroundFix
- net.minecraft.util.datafix.fixes.OptionsForceVBOFix
+ net.minecraft.util.datafix.fixes.OptionsKeyLwjgl3Fix
- net.minecraft.util.datafix.fixes.OptionsKeyTranslationFix
+ net.minecraft.util.datafix.fixes.OptionsLowerCaseLanguageFix
- net.minecraft.util.datafix.fixes.PoiTypeRename
+ net.minecraft.util.datafix.fixes.RecipesFix
- net.minecraft.util.datafix.fixes.RecipesRenameningFix
+ net.minecraft.util.datafix.fixes.References
- net.minecraft.util.datafix.fixes.RenamedCoralFansFix
+ net.minecraft.util.datafix.fixes.RenamedCoralFix
- net.minecraft.util.datafix.fixes.ReorganizePoi
+ net.minecraft.util.datafix.fixes.SavedDataVillageCropFix
- net.minecraft.util.datafix.fixes.SimpleEntityRenameFix
+ net.minecraft.util.datafix.fixes.SimplestEntityRenameFix
- net.minecraft.util.datafix.fixes.StatsCounterFix
+ net.minecraft.util.datafix.OminousBannerBlockEntityRenameFix
- net.minecraft.util.datafix.OminousBannerRenameFix
- net.minecraft.util.Deserializer
+ net.minecraft.util.FrameTimer
- net.minecraft.util.GsonHelper
+ net.minecraft.util.HttpUtil
- net.minecraft.util.InsensitiveStringMap
+ net.minecraft.util.LazyLoadedValue
- net.minecraft.util.LimitedCapacityList
+ net.minecraft.util.LinearCongruentialGenerator
- net.minecraft.util.LowerCaseEnumTypeAdapterFactory
+ net.minecraft.util.LowerCaseEnumTypeAdapterFactory$1
- net.minecraft.util.Mth
+ net.minecraft.util.ProgressListener
- net.minecraft.util.RewindableStream
+ net.minecraft.util.RewindableStream$1
- net.minecraft.util.Serializable
+ net.minecraft.util.SmoothDouble
- net.minecraft.util.StringRepresentable
+ net.minecraft.util.StringUtil
- net.minecraft.util.Tuple
+ net.minecraft.util.Unit
- net.minecraft.util.VisibleForDebug
+ net.minecraft.util.WeighedRandom
- net.minecraft.util.WeighedRandom$WeighedRandomItem
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.blaze3d.vertex.DefaultVertexFormat +1P
```
```
XXX.mojang.math.Quaternion -1M
```
```
XXX.mojang.math.Vector4f +1M | +4P -1P
```
```
XXX.gui.components.ChatComponent +1M
```
```
XXX.client.model.ColorableListModel +1M -1M
```
```
XXX.client.model.ListModel -1M
```
```
XXX.client.model.ZombieModel +2M -2M
```
```
XXX.core.dispenser.DispenseItemBehavior$11 -1M
```
```
XXX.core.dispenser.DispenseItemBehavior$20 -1M | -1P
```
```
XXX.minecraft.world.InteractionResultHolder +2M -3M | -1P
```
```
XXX.entity.player.Player +3M
```
```
XXX.world.item.LeadItem +1M -1M
```
```
XXX.level.block.AbstractFurnaceBlock +1M -1M
```
```
XXX.level.block.AnvilBlock +1M -1M
```
```
XXX.level.block.BedBlock +1M -1M
```
```
XXX.level.block.Block +1M -1M
```
```
XXX.level.block.CakeBlock +2M -2M
```
```
XXX.level.block.ChestBlock +1M -1M
```
```
XXX.level.block.CommandBlock +1M -1M
```
```
XXX.level.block.ComposterBlock +1M -1M
```
```
XXX.level.block.CraftingTableBlock +1M -1M
```
```
XXX.level.block.DaylightDetectorBlock +1M -1M
```
```
XXX.level.block.DispenserBlock +1M -1M
```
```
XXX.level.block.DragonEggBlock +1M -1M
```
```
XXX.level.block.EnchantmentTableBlock +1M -1M
```
```
XXX.level.block.EnderChestBlock +1M -1M
```
```
XXX.level.block.FenceBlock +1M -1M
```
```
XXX.level.block.FletchingTableBlock +1M -1M
```
```
XXX.level.block.FlowerPotBlock +1M -1M
```
```
XXX.level.block.GrindstoneBlock +1M -1M
```
```
XXX.level.block.JigsawBlock +1M -1M
```
```
XXX.level.block.LecternBlock +1M -1M
```
```
XXX.level.block.LoomBlock +1M -1M
```
```
XXX.level.block.PumpkinBlock +1M -1M
```
```
XXX.level.block.ShulkerBoxBlock +1M -1M
```
```
XXX.level.block.SignBlock +1M -1M
```
```
XXX.level.block.SmithingTableBlock +1M -1M
```
```
XXX.level.block.StairBlock +1M -1M
```
```
XXX.level.block.StonecutterBlock +1M -1M
```
```
XXX.block.piston.PistonMath +1M -3M
```
```
XXX.block.piston.PistonMovingBlockEntity +5M -6M
```
```
XXX.block.piston.PistonStructureResolver +1M
```
```
XXX.block.state.BlockState +1M -1M
```

</details>























































<details>
<summary>
com.mojang.math.Quaternion
</summary>

```diff
+ Quaternion copy()
```

</details>

<details>
<summary>
com.mojang.math.Vector4f
</summary>

```diff
- float multiplyRow(int,Matrix4f,float,float,float,float)
```

</details>














































































































































































































































<details>
<summary>
net.minecraft.client.gui.components.ChatComponent
</summary>

```diff
- boolean isChatVisible()
```

</details>




























































































































































<details>
<summary>
net.minecraft.client.model.ColorableListModel
</summary>

```diff
- void <init>()
+ void <init>(Function)
```

</details>











<details>
<summary>
net.minecraft.client.model.ListModel
</summary>

```diff
+ void <init>(Function)
```

</details>





















<details>
<summary>
net.minecraft.client.model.ZombieModel
</summary>

```diff
- void <init>(float,boolean)
- void <init>(float,float,int,int)
+ void <init>(Function,float,boolean)
+ void <init>(Function,float,float,int,int)
```

</details>









































































































































































































































































































































































<details>
<summary>
net.minecraft.core.dispenser.DispenseItemBehavior$11
</summary>

```diff
+ void lambda$execute$0(ItemStack,SmallFireball)
```

</details>




<details>
<summary>
net.minecraft.core.dispenser.DispenseItemBehavior$20
</summary>

```diff
+ ItemStack takeLiquid(BlockSource,ItemStack,ItemStack)
```

</details>

















































<details>
<summary>
net.minecraft.world.InteractionResultHolder
</summary>

```diff
+ boolean shouldSwingOnSuccess()
- InteractionResultHolder consume(Object)
+ InteractionResultHolder successNoSwing(Object)
+ void <init>(InteractionResult,Object,boolean)
- void <init>(InteractionResult,Object)
```

</details>



















































































































































































































































































































<details>
<summary>
net.minecraft.world.entity.player.Player
</summary>

```diff
- boolean tryToStartFallFlying()
- void startFallFlying()
- void stopFallFlying()
```

</details>

























































































































<details>
<summary>
net.minecraft.world.item.LeadItem
</summary>

```diff
+ boolean bindPlayerMobs(Player,Level,BlockPos)
- InteractionResult bindPlayerMobs(Player,Level,BlockPos)
```

</details>






















































































































































<details>
<summary>
net.minecraft.world.level.block.AbstractFurnaceBlock
</summary>

```diff
+ boolean use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.AnvilBlock
</summary>

```diff
+ boolean use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>







<details>
<summary>
net.minecraft.world.level.block.BedBlock
</summary>

```diff
+ boolean use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>



<details>
<summary>
net.minecraft.world.level.block.Block
</summary>

```diff
+ boolean use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>







<details>
<summary>
net.minecraft.world.level.block.CakeBlock
</summary>

```diff
+ boolean eat(LevelAccessor,BlockPos,BlockState,Player)
+ boolean use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult eat(LevelAccessor,BlockPos,BlockState,Player)
- InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>


<details>
<summary>
net.minecraft.world.level.block.ChestBlock
</summary>

```diff
+ boolean use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>




<details>
<summary>
net.minecraft.world.level.block.CommandBlock
</summary>

```diff
+ boolean use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.ComposterBlock
</summary>

```diff
+ boolean use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>




<details>
<summary>
net.minecraft.world.level.block.CraftingTableBlock
</summary>

```diff
+ boolean use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.DaylightDetectorBlock
</summary>

```diff
+ boolean use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>


<details>
<summary>
net.minecraft.world.level.block.DispenserBlock
</summary>

```diff
+ boolean use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.DragonEggBlock
</summary>

```diff
+ boolean use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.EnchantmentTableBlock
</summary>

```diff
+ boolean use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>


<details>
<summary>
net.minecraft.world.level.block.EnderChestBlock
</summary>

```diff
+ boolean use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>


<details>
<summary>
net.minecraft.world.level.block.FenceBlock
</summary>

```diff
+ boolean use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.FletchingTableBlock
</summary>

```diff
+ boolean use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.FlowerPotBlock
</summary>

```diff
+ boolean use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>



<details>
<summary>
net.minecraft.world.level.block.GrindstoneBlock
</summary>

```diff
+ boolean use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>





<details>
<summary>
net.minecraft.world.level.block.JigsawBlock
</summary>

```diff
+ boolean use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>



<details>
<summary>
net.minecraft.world.level.block.LecternBlock
</summary>

```diff
+ boolean use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>



<details>
<summary>
net.minecraft.world.level.block.LoomBlock
</summary>

```diff
+ boolean use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>











<details>
<summary>
net.minecraft.world.level.block.PumpkinBlock
</summary>

```diff
+ boolean use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>











<details>
<summary>
net.minecraft.world.level.block.ShulkerBoxBlock
</summary>

```diff
+ boolean use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SignBlock
</summary>

```diff
+ boolean use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>



<details>
<summary>
net.minecraft.world.level.block.SmithingTableBlock
</summary>

```diff
+ boolean use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>





<details>
<summary>
net.minecraft.world.level.block.StairBlock
</summary>

```diff
+ boolean use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>


<details>
<summary>
net.minecraft.world.level.block.StonecutterBlock
</summary>

```diff
+ boolean use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
- InteractionResult use(BlockState,Level,BlockPos,Player,InteractionHand,BlockHitResult)
```

</details>






















































<details>
<summary>
net.minecraft.world.level.block.piston.PistonMath
</summary>

```diff
+ AABB getEntityMovementAreaInFront(AABB,Direction,double)
+ AABB getEntityMovementAreaOnTop(AABB)
- AABB getMovementArea(AABB,Direction,double)
+ List getEntityMovementAreas(boolean,AABB,Direction,double)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.piston.PistonMovingBlockEntity
</summary>

```diff
+ AABB findIntersectingAABB(AABB,List)
+ boolean entitiesOnSurfaceMoveWithBlock()
- boolean isStickyForEntities()
+ boolean isStickyForEntitities(Block)
- boolean lambda$moveStuckEntities$1(AABB,Entity)
- boolean matchesStickyCritera(AABB,Entity)
+ double getDeltaX(AABB,Direction,AABB)
+ double getDeltaY(AABB,Direction,AABB)
+ double getDeltaZ(AABB,Direction,AABB)
- void moveEntityByPiston(Direction,Entity,double,Direction)
- void moveStuckEntities(float)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.piston.PistonStructureResolver
</summary>

```diff
- boolean canStickToEachOther(Block,Block)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.state.BlockState
</summary>

```diff
+ boolean use(Level,Player,InteractionHand,BlockHitResult)
- InteractionResult use(Level,Player,InteractionHand,BlockHitResult)
```

</details>
</details>