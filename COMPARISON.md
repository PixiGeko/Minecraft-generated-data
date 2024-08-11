## Comparison with [19w40a](https://github.com/PixiGeko/Minecraft-generated-data/tree/19w40a)

- [Version data](#version-data)
- [Registries](#registries)
- [Tags](#tags)
- [Commands](#commands)
- [Recipes](#recipes)
- [Translations](#translations)
- [File structure](#file-structure)
- [Mappings](#mappings)
  - [Server](#server)
  - [Client](#client)

<hr/>
<details><summary>Version data</summary>
<table><tr><th></th><th align="left">19w40a</th><th>19w41a</th></tr><tr><td>World version</td><td><code>2208</code></td><td><code>2210</code></td></tr><tr><td>Protocol version</td><td><code>557</code></td><td><code>558</code></td></tr></table>
</details>
<details><summary>Registries</summary>
<details>
<summary>
List
</summary>

```diff
+ block_placer_type.txt
+ block_state_provider_type.txt
+ foliage_placer_type.txt
+ tree_decorator_type.txt
```

</details>



<details>
<summary>
block.txt
</summary>

```diff
- minecraft:bee_hive
+ minecraft:beehive
+ minecraft:honey_block
+ minecraft:honeycomb_block
```

</details>









<details>
<summary>
feature.txt
</summary>

```diff
+ minecraft:acacia_tree
- minecraft:birch_tree
+ minecraft:block_pile
- minecraft:bush
- minecraft:cactus
- minecraft:dead_bush
- minecraft:default_flower
- minecraft:double_plant
+ minecraft:flower
- minecraft:forest_flower
- minecraft:general_forest_flower
- minecraft:grass
- minecraft:hay_pile
- minecraft:hell_fire
- minecraft:ice_pile
- minecraft:jungle_grass
- minecraft:jungle_tree
- minecraft:mega_pine_tree
- minecraft:melon
- minecraft:melon_pile
- minecraft:nether_spring
- minecraft:pine_tree
- minecraft:plain_flower
- minecraft:pumpkin
- minecraft:pumpkin_pile
+ minecraft:random_patch
- minecraft:reed
- minecraft:savanna_tree
- minecraft:snow_pile
- minecraft:spruce_tree
- minecraft:super_birch_tree
- minecraft:swamp_flower
- minecraft:swamp_tree
- minecraft:sweet_berry_bush
- minecraft:taiga_grass
- minecraft:waterlily
```

</details>

<details>
<summary>
item.txt
</summary>

```diff
- minecraft:bee_hive
+ minecraft:beehive
+ minecraft:honey_block
+ minecraft:honeycomb_block
```

</details>





<details>
<summary>
point_of_interest_type.txt
</summary>

```diff
- minecraft:bee_hive
+ minecraft:beehive
```

</details>






<details>
<summary>
sound_event.txt
</summary>

```diff
+ minecraft:block.honey_block.break
+ minecraft:block.honey_block.fall
+ minecraft:block.honey_block.hit
+ minecraft:block.honey_block.place
+ minecraft:block.honey_block.slide
+ minecraft:block.honey_block.step
+ minecraft:entity.iron_golem.damage
+ minecraft:entity.iron_golem.repair
- minecraft:entity.parrot.imitate.panda
```

</details>
</details>
<details><summary>Tags</summary>
<details>
<summary>
List
</summary>

```diff
+ universal_tags/block_placer_type.json
+ universal_tags/block_state_provider_type.json
+ universal_tags/foliage_placer_type.json
+ universal_tags/tree_decorator_type.json
```

</details>

<details>
<summary>
all_blocks_with_drop.json
</summary>

```diff
- minecraft:bee_hive
+ minecraft:beehive
+ minecraft:honey_block
+ minecraft:honeycomb_block
```

</details>







<details>
<summary>
universal_tags/block.json
</summary>

```diff
- minecraft:bee_hive
+ minecraft:beehive
+ minecraft:honey_block
+ minecraft:honeycomb_block
```

</details>









<details>
<summary>
universal_tags/feature.json
</summary>

```diff
+ minecraft:acacia_tree
- minecraft:birch_tree
+ minecraft:block_pile
- minecraft:bush
- minecraft:cactus
- minecraft:dead_bush
- minecraft:default_flower
- minecraft:double_plant
+ minecraft:flower
- minecraft:forest_flower
- minecraft:general_forest_flower
- minecraft:grass
- minecraft:hay_pile
- minecraft:hell_fire
- minecraft:ice_pile
- minecraft:jungle_grass
- minecraft:jungle_tree
- minecraft:mega_pine_tree
- minecraft:melon
- minecraft:melon_pile
- minecraft:nether_spring
- minecraft:pine_tree
- minecraft:plain_flower
- minecraft:pumpkin
- minecraft:pumpkin_pile
+ minecraft:random_patch
- minecraft:reed
- minecraft:savanna_tree
- minecraft:snow_pile
- minecraft:spruce_tree
- minecraft:super_birch_tree
- minecraft:swamp_flower
- minecraft:swamp_tree
- minecraft:sweet_berry_bush
- minecraft:taiga_grass
- minecraft:waterlily
```

</details>

<details>
<summary>
universal_tags/item.json
</summary>

```diff
- minecraft:bee_hive
+ minecraft:beehive
+ minecraft:honey_block
+ minecraft:honeycomb_block
```

</details>





<details>
<summary>
universal_tags/point_of_interest_type.json
</summary>

```diff
- minecraft:bee_hive
+ minecraft:beehive
```

</details>






<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:block.honey_block.break
+ minecraft:block.honey_block.fall
+ minecraft:block.honey_block.hit
+ minecraft:block.honey_block.place
+ minecraft:block.honey_block.slide
+ minecraft:block.honey_block.step
+ minecraft:entity.iron_golem.damage
+ minecraft:entity.iron_golem.repair
- minecraft:entity.parrot.imitate.panda
```

</details>
</details>
<details><summary>Commands</summary>
<details>
<summary>
List
</summary>

```diff
+ spectate.json
```

</details>
</details>
<details><summary>Recipes</summary>
<details>
<summary>
List
</summary>

```diff
- bee_hive.json
+ beehive.json
+ honey_block.json
+ honeycomb_block.json
+ stripped_acacia_wood.json
+ stripped_birch_wood.json
+ stripped_dark_oak_wood.json
+ stripped_jungle_wood.json
+ stripped_oak_wood.json
+ stripped_spruce_wood.json
```

</details>
</details>
<details><summary>Translations</summary>
<details>
<summary>
Keys
</summary>

```diff
- block.minecraft.bee_hive: Bee hive
+ block.minecraft.beehive: Beehive
+ block.minecraft.honey_block: Honey Block
+ block.minecraft.honeycomb_block: Honeycomb Block
+ commands.spectate.not_spectator: %s is not in spectator mode
+ commands.spectate.self: Cannot spectate yourself
+ commands.spectate.success.started: Now spectating %s
+ commands.spectate.success.stopped: No longer spectating an entity
+ options.key.hold: Hold
+ options.key.toggle: Toggle
+ subtitles.block.honey_block.slide: Sliding down a honey block
+ subtitles.entity.iron_golem.damage: Iron Golem breaks
+ subtitles.entity.iron_golem.repair: Iron Golem repaired
```

</details>
</details>
<details><summary>File structure</summary>
<details>
<summary>
data
</summary>

```diff
+ minecraft/advancements/recipes/building_blocks/stripped_acacia_wood.json
+ minecraft/advancements/recipes/building_blocks/stripped_birch_wood.json
+ minecraft/advancements/recipes/building_blocks/stripped_dark_oak_wood.json
+ minecraft/advancements/recipes/building_blocks/stripped_jungle_wood.json
+ minecraft/advancements/recipes/building_blocks/stripped_oak_wood.json
+ minecraft/advancements/recipes/building_blocks/stripped_spruce_wood.json
- minecraft/advancements/recipes/decorations/bee_hive.json
+ minecraft/advancements/recipes/decorations/beehive.json
+ minecraft/advancements/recipes/decorations/honey_block.json
+ minecraft/advancements/recipes/decorations/honeycomb_block.json
- minecraft/loot_tables/blocks/bee_hive.json
+ minecraft/loot_tables/blocks/beehive.json
+ minecraft/loot_tables/blocks/honey_block.json
+ minecraft/loot_tables/blocks/honeycomb_block.json
- minecraft/recipes/bee_hive.json
+ minecraft/recipes/beehive.json
+ minecraft/recipes/honey_block.json
+ minecraft/recipes/honeycomb_block.json
+ minecraft/recipes/stripped_acacia_wood.json
+ minecraft/recipes/stripped_birch_wood.json
+ minecraft/recipes/stripped_dark_oak_wood.json
+ minecraft/recipes/stripped_jungle_wood.json
+ minecraft/recipes/stripped_oak_wood.json
+ minecraft/recipes/stripped_spruce_wood.json
- minecraft/tags/blocks/dirt_like.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
- minecraft/blockstates/bee_hive.json
+ minecraft/blockstates/beehive.json
+ minecraft/blockstates/honey_block.json
+ minecraft/blockstates/honeycomb_block.json
- minecraft/models/block/bee_hive_honey.json
- minecraft/models/block/bee_hive.json
+ minecraft/models/block/beehive_honey.json
+ minecraft/models/block/beehive.json
+ minecraft/models/block/honey_block.json
+ minecraft/models/block/honeycomb_block.json
- minecraft/models/item/bee_hive.json
+ minecraft/models/item/beehive.json
+ minecraft/models/item/honey_block.json
+ minecraft/models/item/honeycomb_block.json
- minecraft/textures/block/bee_hive_end.png
- minecraft/textures/block/bee_hive_front_honey.png
- minecraft/textures/block/bee_hive_front.png
- minecraft/textures/block/bee_hive_side.png
+ minecraft/textures/block/beehive_end.png
+ minecraft/textures/block/beehive_front_honey.png
+ minecraft/textures/block/beehive_front.png
+ minecraft/textures/block/beehive_side.png
+ minecraft/textures/block/honey_block_bottom.png
+ minecraft/textures/block/honey_block_side.png
+ minecraft/textures/block/honey_block_top.png
+ minecraft/textures/block/honeycomb_block.png
- minecraft/textures/entity/iron_golem.png
+ minecraft/textures/entity/iron_golem/iron_golem_crackiness_high.png
+ minecraft/textures/entity/iron_golem/iron_golem_crackiness_low.png
+ minecraft/textures/entity/iron_golem/iron_golem_crackiness_medium.png
+ minecraft/textures/entity/iron_golem/iron_golem.png
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
- net.minecraft.gametest.framework.GameTestGenerator
+ net.minecraft.gametest.framework.GameTestHelper
- net.minecraft.gametest.framework.GameTestInfo
+ net.minecraft.gametest.framework.GameTestListener
- net.minecraft.gametest.framework.GameTestRegistry
+ net.minecraft.gametest.framework.GameTestRunner
- net.minecraft.gametest.framework.GameTestRunner$1
- net.minecraft.gametest.framework.GameTestSequence$Condition
+ net.minecraft.gametest.framework.GameTestServer
- net.minecraft.gametest.framework.GameTestServer$1
+ net.minecraft.gametest.framework.GameTestTicker
- net.minecraft.gametest.framework.GameTestTimeoutException
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
+ net.minecraft.network.chat.Component
- net.minecraft.network.chat.Component$1
+ net.minecraft.network.chat.Component$Serializer
- net.minecraft.network.chat.ComponentUtils
+ net.minecraft.network.chat.ContextAwareComponent
- net.minecraft.network.chat.HoverEvent
+ net.minecraft.network.chat.HoverEvent$Action
- net.minecraft.network.chat.KeybindComponent
+ net.minecraft.network.chat.NbtComponent
- net.minecraft.network.chat.NbtComponent$BlockNbtComponent
+ net.minecraft.network.chat.NbtComponent$EntityNbtComponent
- net.minecraft.network.chat.NbtComponent$StorageNbtComponent
+ net.minecraft.network.chat.package-info
+ net.minecraft.network.chat.ScoreComponent
- net.minecraft.network.chat.SelectorComponent
+ net.minecraft.network.chat.Style
- net.minecraft.network.chat.Style$1
+ net.minecraft.network.chat.Style$Serializer
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
+ net.minecraft.network.protocol.game.ClientboundSetSpawnPositionPacket
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
- net.minecraft.network.protocol.game.DebugPackets
+ net.minecraft.network.protocol.game.DebugVillagerNameGenerator
- net.minecraft.network.protocol.game.package-info
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
- net.minecraft.network.protocol.game.ServerGamePacketListener
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
+ net.minecraft.network.protocol.Packet
- net.minecraft.network.protocol.PacketFlow
+ net.minecraft.network.protocol.PacketUtils
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
- net.minecraft.network.SkipPacketException
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
+ net.minecraft.network.Varint21FrameDecoder
- net.minecraft.network.Varint21LengthFieldPrepender
- net.minecraft.obfuscate.DontObfuscateOrShrink
+ net.minecraft.obfuscate.KeepAfterObfuscation
- net.minecraft.obfuscate.package-info
+ net.minecraft.package-info
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
+ net.minecraft.server.ConsoleInput
- net.minecraft.server.ConsoleInputSource
+ net.minecraft.server.DebugLoggedPrintStream
- net.minecraft.server.Eula
+ net.minecraft.server.LoggedPrintStream
- net.minecraft.server.MinecraftServer
+ net.minecraft.server.MinecraftServer$1
- net.minecraft.server.MinecraftServer$2
+ net.minecraft.server.MinecraftServer$3
- net.minecraft.server.PlayerAdvancements
+ net.minecraft.server.PlayerAdvancements$1
- net.minecraft.server.RunningOnDifferentThreadException
+ net.minecraft.server.ServerAdvancementManager
- net.minecraft.server.ServerFunctionManager
+ net.minecraft.server.ServerFunctionManager$QueuedCommand
- net.minecraft.server.ServerInterface
+ net.minecraft.server.ServerScoreboard
- net.minecraft.server.ServerScoreboard$Method
+ net.minecraft.server.TickTask
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
+ net.minecraft.world.entity.ai.goal.FollowOwnerFlyingGoal
- net.minecraft.world.entity.ai.goal.FollowOwnerGoal
+ net.minecraft.world.entity.ai.goal.FollowParentGoal
- net.minecraft.world.entity.ai.goal.Goal
+ net.minecraft.world.entity.ai.goal.Goal$Flag
- net.minecraft.world.entity.ai.goal.GoalSelector
+ net.minecraft.world.entity.ai.goal.GoalSelector$1
- net.minecraft.world.entity.ai.goal.GoalSelector$2
+ net.minecraft.world.entity.ai.goal.InteractGoal
- net.minecraft.world.entity.ai.goal.JumpGoal
+ net.minecraft.world.entity.ai.goal.LandOnOwnersShoulderGoal
- net.minecraft.world.entity.ai.goal.LeapAtTargetGoal
+ net.minecraft.world.entity.ai.goal.LlamaFollowCaravanGoal
- net.minecraft.world.entity.ai.goal.LookAtPlayerGoal
+ net.minecraft.world.entity.ai.goal.LookAtTradingPlayerGoal
- net.minecraft.world.entity.ai.goal.MeleeAttackGoal
+ net.minecraft.world.entity.ai.goal.MoveBackToVillage
- net.minecraft.world.entity.ai.goal.MoveIndoorsGoal
+ net.minecraft.world.entity.ai.goal.MoveThroughVillageGoal
- net.minecraft.world.entity.ai.goal.MoveToBlockGoal
+ net.minecraft.world.entity.ai.goal.MoveTowardsRestrictionGoal
- net.minecraft.world.entity.ai.goal.MoveTowardsTargetGoal
+ net.minecraft.world.entity.ai.goal.OcelotAttackGoal
- net.minecraft.world.entity.ai.goal.OfferFlowerGoal
+ net.minecraft.world.entity.ai.goal.OpenDoorGoal
+ net.minecraft.world.entity.ai.goal.package-info
- net.minecraft.world.entity.ai.goal.PanicGoal
+ net.minecraft.world.entity.ai.goal.PathfindToRaidGoal
- net.minecraft.world.entity.ai.goal.PlayGoal
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
+ net.minecraft.world.entity.ai.goal.SitGoal
- net.minecraft.world.entity.ai.goal.StrollThroughVillageGoal
+ net.minecraft.world.entity.ai.goal.SwellGoal
- net.minecraft.world.entity.ai.goal.TakeFlowerGoal
- net.minecraft.world.entity.ai.goal.target.DefendVillageTargetGoal
+ net.minecraft.world.entity.ai.goal.target.HurtByTargetGoal
- net.minecraft.world.entity.ai.goal.target.NearestAttackableTargetGoal
+ net.minecraft.world.entity.ai.goal.target.NearestAttackableWitchTargetGoal
- net.minecraft.world.entity.ai.goal.target.NearestHealableRaiderTargetGoal
+ net.minecraft.world.entity.ai.goal.target.NonTameRandomTargetGoal
- net.minecraft.world.entity.ai.goal.target.OwnerHurtByTargetGoal
+ net.minecraft.world.entity.ai.goal.target.OwnerHurtTargetGoal
+ net.minecraft.world.entity.ai.goal.target.package-info
- net.minecraft.world.entity.ai.goal.target.TargetGoal
+ net.minecraft.world.entity.ai.goal.TemptGoal
- net.minecraft.world.entity.ai.goal.TradeWithPlayerGoal
+ net.minecraft.world.entity.ai.goal.TryFindWaterGoal
- net.minecraft.world.entity.ai.goal.UseItemGoal
+ net.minecraft.world.entity.ai.goal.WaterAvoidingRandomFlyingGoal
- net.minecraft.world.entity.ai.goal.WaterAvoidingRandomStrollGoal
+ net.minecraft.world.entity.ai.goal.WrappedGoal
- net.minecraft.world.entity.ai.goal.ZombieAttackGoal
- net.minecraft.world.entity.ai.gossip.GossipContainer
+ net.minecraft.world.entity.ai.gossip.GossipContainer$1
- net.minecraft.world.entity.ai.gossip.GossipContainer$EntityGossips
+ net.minecraft.world.entity.ai.gossip.GossipContainer$GossipEntry
- net.minecraft.world.entity.ai.gossip.GossipType
+ net.minecraft.world.entity.ai.gossip.package-info
- net.minecraft.world.entity.ai.memory.MemoryModuleType
+ net.minecraft.world.entity.ai.memory.MemoryStatus
+ net.minecraft.world.entity.ai.memory.package-info
- net.minecraft.world.entity.ai.memory.WalkTarget
- net.minecraft.world.entity.ai.navigation.FlyingPathNavigation
+ net.minecraft.world.entity.ai.navigation.GroundPathNavigation
+ net.minecraft.world.entity.ai.navigation.package-info
- net.minecraft.world.entity.ai.navigation.PathNavigation
+ net.minecraft.world.entity.ai.navigation.WallClimberNavigation
- net.minecraft.world.entity.ai.navigation.WaterBoundPathNavigation
- net.minecraft.world.entity.ai.package-info
+ net.minecraft.world.entity.ai.sensing.DummySensor
- net.minecraft.world.entity.ai.sensing.GolemSensor
+ net.minecraft.world.entity.ai.sensing.HurtBySensor
- net.minecraft.world.entity.ai.sensing.InteractableDoorsSensor
+ net.minecraft.world.entity.ai.sensing.NearestBedSensor
- net.minecraft.world.entity.ai.sensing.NearestLivingEntitySensor
- net.minecraft.world.entity.ai.sensing.package-info
+ net.minecraft.world.entity.ai.sensing.PlayerSensor
- net.minecraft.world.entity.ai.sensing.SecondaryPoiSensor
+ net.minecraft.world.entity.ai.sensing.Sensing
- net.minecraft.world.entity.ai.sensing.Sensor
+ net.minecraft.world.entity.ai.sensing.SensorType
- net.minecraft.world.entity.ai.sensing.VillagerBabiesSensor
+ net.minecraft.world.entity.ai.sensing.VillagerHostilesSensor
- net.minecraft.world.entity.ai.targeting.package-info
+ net.minecraft.world.entity.ai.targeting.TargetingConditions
- net.minecraft.world.entity.ai.util.package-info
+ net.minecraft.world.entity.ai.util.RandomPos
+ net.minecraft.world.entity.ai.village.package-info
- net.minecraft.world.entity.ai.village.poi.package-info
- net.minecraft.world.entity.ai.village.poi.PoiManager
+ net.minecraft.world.entity.ai.village.poi.PoiManager$DistanceTracker
- net.minecraft.world.entity.ai.village.poi.PoiManager$Occupancy
+ net.minecraft.world.entity.ai.village.poi.PoiRecord
- net.minecraft.world.entity.ai.village.poi.PoiSection
+ net.minecraft.world.entity.ai.village.poi.PoiType
+ net.minecraft.world.entity.ai.village.ReputationEventType
- net.minecraft.world.entity.ai.village.ReputationEventType$1
+ net.minecraft.world.entity.ai.village.VillageSiege
- net.minecraft.world.entity.ai.village.VillageSiege$State
+ net.minecraft.world.entity.ambient.AmbientCreature
- net.minecraft.world.entity.ambient.Bat
+ net.minecraft.world.entity.ambient.package-info
- net.minecraft.world.entity.animal.AbstractFish
+ net.minecraft.world.entity.animal.AbstractFish$FishMoveControl
- net.minecraft.world.entity.animal.AbstractFish$FishSwimGoal
+ net.minecraft.world.entity.animal.AbstractGolem
- net.minecraft.world.entity.animal.AbstractSchoolingFish
+ net.minecraft.world.entity.animal.AbstractSchoolingFish$SchoolSpawnGroupData
- net.minecraft.world.entity.animal.Animal
+ net.minecraft.world.entity.animal.Bee
- net.minecraft.world.entity.animal.Bee$1
+ net.minecraft.world.entity.animal.Bee$BaseBeeGoal
- net.minecraft.world.entity.animal.Bee$BeeAttackGoal
+ net.minecraft.world.entity.animal.Bee$BeeBecomeAngryTargetGoal
- net.minecraft.world.entity.animal.Bee$BeeEnterHiveGoal
+ net.minecraft.world.entity.animal.Bee$BeeGoToBlockGoal
- net.minecraft.world.entity.animal.Bee$BeeGoToHiveGoal
+ net.minecraft.world.entity.animal.Bee$BeeGoToKnownFlowerGoal
- net.minecraft.world.entity.animal.Bee$BeeGrowCropGoal
+ net.minecraft.world.entity.animal.Bee$BeeHurtByOtherGoal
- net.minecraft.world.entity.animal.Bee$BeeLocateHiveGoal
+ net.minecraft.world.entity.animal.Bee$BeeLookControl
- net.minecraft.world.entity.animal.Bee$BeePollinateGoal
+ net.minecraft.world.entity.animal.Bee$BeeWanderGoal
- net.minecraft.world.entity.animal.Cat
+ net.minecraft.world.entity.animal.Cat$CatAvoidEntityGoal
- net.minecraft.world.entity.animal.Cat$CatRelaxOnOwnerGoal
+ net.minecraft.world.entity.animal.Cat$CatTemptGoal
- net.minecraft.world.entity.animal.Chicken
+ net.minecraft.world.entity.animal.Cod
- net.minecraft.world.entity.animal.Cow
+ net.minecraft.world.entity.animal.Dolphin
- net.minecraft.world.entity.animal.Dolphin$1
+ net.minecraft.world.entity.animal.Dolphin$DolphinMoveControl
- net.minecraft.world.entity.animal.Dolphin$DolphinSwimToTreasureGoal
+ net.minecraft.world.entity.animal.Dolphin$DolphinSwimWithPlayerGoal
- net.minecraft.world.entity.animal.Dolphin$PlayWithItemsGoal
+ net.minecraft.world.entity.animal.FlyingAnimal
- net.minecraft.world.entity.animal.Fox
+ net.minecraft.world.entity.animal.Fox$1
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
- net.minecraft.world.level.block.grower.AbstractMegaTreeGrower
+ net.minecraft.world.level.block.grower.AbstractTreeGrower
- net.minecraft.world.level.block.grower.AcaciaTreeGrower
+ net.minecraft.world.level.block.grower.BirchTreeGrower
- net.minecraft.world.level.block.grower.DarkOakTreeGrower
+ net.minecraft.world.level.block.grower.JungleTreeGrower
- net.minecraft.world.level.block.grower.OakTreeGrower
- net.minecraft.world.level.block.grower.package-info
+ net.minecraft.world.level.block.grower.SpruceTreeGrower
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
+ net.minecraft.world.level.block.NetherWartBlock
- net.minecraft.world.level.block.NoteBlock
+ net.minecraft.world.level.block.ObserverBlock
- net.minecraft.world.level.block.OreBlock
+ net.minecraft.world.level.block.package-info
+ net.minecraft.world.level.block.PipeBlock
- net.minecraft.world.level.block.piston.MovingPistonBlock
- net.minecraft.world.level.block.piston.package-info
+ net.minecraft.world.level.block.piston.PistonBaseBlock
- net.minecraft.world.level.block.piston.PistonBaseBlock$1
+ net.minecraft.world.level.block.piston.PistonHeadBlock
- net.minecraft.world.level.block.piston.PistonHeadBlock$1
- net.minecraft.world.level.block.piston.PistonMath$1
+ net.minecraft.world.level.block.piston.PistonMovingBlockEntity
- net.minecraft.world.level.block.piston.PistonMovingBlockEntity$1
+ net.minecraft.world.level.block.piston.PistonStructureResolver
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
- net.minecraft.world.level.block.SoulsandBlock
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
- net.minecraft.world.level.block.state.AbstractStateHolder$1
+ net.minecraft.world.level.block.state.BlockState
- net.minecraft.world.level.block.state.BlockState$1
+ net.minecraft.world.level.block.state.BlockState$Cache
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
- net.minecraft.world.level.block.state.properties.AttachFace
+ net.minecraft.world.level.block.state.properties.BambooLeaves
- net.minecraft.world.level.block.state.properties.BedPart
+ net.minecraft.world.level.block.state.properties.BellAttachType
- net.minecraft.world.level.block.state.properties.BlockStateProperties
+ net.minecraft.world.level.block.state.properties.BooleanProperty
- net.minecraft.world.level.block.state.properties.ChestType
+ net.minecraft.world.level.block.state.properties.ComparatorMode
- net.minecraft.world.level.block.state.properties.DirectionProperty
+ net.minecraft.world.level.block.state.properties.DoorHingeSide
- net.minecraft.world.level.block.state.properties.DoubleBlockHalf
+ net.minecraft.world.level.block.state.properties.EnumProperty
- net.minecraft.world.level.block.state.properties.Half
+ net.minecraft.world.level.block.state.properties.IntegerProperty
- net.minecraft.world.level.block.state.properties.NoteBlockInstrument
- net.minecraft.world.level.block.state.properties.package-info
+ net.minecraft.world.level.block.state.properties.PistonType
- net.minecraft.world.level.block.state.properties.Property
+ net.minecraft.world.level.block.state.properties.RailShape
- net.minecraft.world.level.block.state.properties.RedstoneSide
+ net.minecraft.world.level.block.state.properties.SlabType
- net.minecraft.world.level.block.state.properties.StairsShape
+ net.minecraft.world.level.block.state.properties.StructureMode
- net.minecraft.world.level.block.state.StateDefinition
+ net.minecraft.world.level.block.state.StateDefinition$Builder
- net.minecraft.world.level.block.state.StateDefinition$Factory
+ net.minecraft.world.level.block.state.StateHolder
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
- net.minecraft.world.level.block.VineBlock
+ net.minecraft.world.level.block.VineBlock$1
- net.minecraft.world.level.block.WallBannerBlock
+ net.minecraft.world.level.block.WallBlock
- net.minecraft.world.level.block.WallSignBlock
+ net.minecraft.world.level.block.WallSkullBlock
- net.minecraft.world.level.block.WallTorchBlock
+ net.minecraft.world.level.block.WaterlilyBlock
- net.minecraft.world.level.block.WebBlock
+ net.minecraft.world.level.block.WeightedPressurePlateBlock
- net.minecraft.world.level.block.WetSpongeBlock
+ net.minecraft.world.level.block.WitherRoseBlock
- net.minecraft.world.level.block.WitherSkullBlock
+ net.minecraft.world.level.block.WitherWallSkullBlock
- net.minecraft.world.level.block.WoodButtonBlock
+ net.minecraft.world.level.block.WoolCarpetBlock
+ net.minecraft.world.level.border.BorderChangeListener
- net.minecraft.world.level.border.BorderChangeListener$DelegateBorderChangeListener
+ net.minecraft.world.level.border.BorderStatus
+ net.minecraft.world.level.border.package-info
- net.minecraft.world.level.border.WorldBorder
+ net.minecraft.world.level.border.WorldBorder$1
- net.minecraft.world.level.border.WorldBorder$BorderExtent
+ net.minecraft.world.level.border.WorldBorder$MovingBorderExtent
- net.minecraft.world.level.border.WorldBorder$StaticBorderExtent
- net.minecraft.world.level.chunk.ChunkAccess
+ net.minecraft.world.level.chunk.ChunkBiomeContainer
- net.minecraft.world.level.chunk.ChunkGenerator
+ net.minecraft.world.level.chunk.ChunkGeneratorFactory
- net.minecraft.world.level.chunk.ChunkGeneratorType
+ net.minecraft.world.level.chunk.ChunkSource
- net.minecraft.world.level.chunk.ChunkStatus
+ net.minecraft.world.level.chunk.ChunkStatus$ChunkType
- net.minecraft.world.level.chunk.ChunkStatus$GenerationTask
+ net.minecraft.world.level.chunk.ChunkStatus$LoadingTask
- net.minecraft.world.level.chunk.ChunkStatus$SimpleGenerationTask
+ net.minecraft.world.level.chunk.DataLayer
- net.minecraft.world.level.chunk.EmptyLevelChunk
+ net.minecraft.world.level.chunk.FeatureAccess
- net.minecraft.world.level.chunk.GlobalPalette
+ net.minecraft.world.level.chunk.HashMapPalette
- net.minecraft.world.level.chunk.ImposterProtoChunk
+ net.minecraft.world.level.chunk.LevelChunk
- net.minecraft.world.level.chunk.LevelChunk$EntityCreationType
+ net.minecraft.world.level.chunk.LevelChunkSection
- net.minecraft.world.level.chunk.LightChunkGetter
+ net.minecraft.world.level.chunk.LinearPalette
- net.minecraft.world.level.chunk.OldDataLayer
- net.minecraft.world.level.chunk.package-info
+ net.minecraft.world.level.chunk.Palette
+ net.minecraft.world.level.chunk.PalettedContainer
- net.minecraft.world.level.chunk.PalettedContainer$CountConsumer
- net.minecraft.world.level.chunk.PaletteResize
+ net.minecraft.world.level.chunk.ProtoChunk
- net.minecraft.world.level.chunk.ProtoTickList
+ net.minecraft.world.level.chunk.storage.ChunkSerializer
- net.minecraft.world.level.chunk.storage.ChunkStorage
+ net.minecraft.world.level.chunk.storage.OldChunkStorage
- net.minecraft.world.level.chunk.storage.OldChunkStorage$OldLevelChunk
+ net.minecraft.world.level.chunk.storage.package-info
+ net.minecraft.world.level.chunk.storage.RegionBitmap
- net.minecraft.world.level.chunk.storage.RegionFile
+ net.minecraft.world.level.chunk.storage.RegionFile$ChunkBuffer
- net.minecraft.world.level.chunk.storage.RegionFile$CommitOp
+ net.minecraft.world.level.chunk.storage.RegionFileStorage
- net.minecraft.world.level.chunk.storage.RegionFileVersion
+ net.minecraft.world.level.chunk.storage.RegionFileVersion$StreamWrapper
- net.minecraft.world.level.chunk.storage.SectionStorage
+ net.minecraft.world.level.chunk.UpgradeData
- net.minecraft.world.level.chunk.UpgradeData$1
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixer
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$1
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$2
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$3
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$4
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$5
- net.minecraft.world.level.dimension.Dimension
+ net.minecraft.world.level.dimension.DimensionType
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$1
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$2
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$3
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$4
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$5
+ net.minecraft.world.level.dimension.end.EndDragonFight
+ net.minecraft.world.level.dimension.end.package-info
- net.minecraft.world.level.dimension.end.TheEndDimension
- net.minecraft.world.level.dimension.NetherDimension
+ net.minecraft.world.level.dimension.NetherDimension$1
- net.minecraft.world.level.dimension.NormalDimension
- net.minecraft.world.level.dimension.package-info
- net.minecraft.world.level.levelgen.carver.CanyonWorldCarver
+ net.minecraft.world.level.levelgen.carver.CarverConfiguration
- net.minecraft.world.level.levelgen.carver.CaveWorldCarver
+ net.minecraft.world.level.levelgen.carver.ConfiguredWorldCarver
- net.minecraft.world.level.levelgen.carver.HellCaveWorldCarver
+ net.minecraft.world.level.levelgen.carver.NoneCarverConfiguration
+ net.minecraft.world.level.levelgen.carver.package-info
- net.minecraft.world.level.levelgen.carver.UnderwaterCanyonWorldCarver
+ net.minecraft.world.level.levelgen.carver.UnderwaterCaveWorldCarver
- net.minecraft.world.level.levelgen.carver.WorldCarver
+ net.minecraft.world.level.levelgen.ChunkGeneratorSettings
- net.minecraft.world.level.levelgen.DebugGeneratorSettings
+ net.minecraft.world.level.levelgen.DebugLevelSource
- net.minecraft.world.level.levelgen.feature.AbstractFlowerFeature
- net.minecraft.world.level.levelgen.feature.AbstractSmallTreeFeature
- net.minecraft.world.level.levelgen.feature.AcaciaFeature
+ net.minecraft.world.level.levelgen.feature.BambooFeature
+ net.minecraft.world.level.levelgen.feature.BigTreeFeature$FoliageCoords
+ net.minecraft.world.level.levelgen.feature.BlockBlobConfiguration
- net.minecraft.world.level.levelgen.feature.BlockBlobFeature
+ net.minecraft.world.level.levelgen.feature.BlockPileFeature
- net.minecraft.world.level.levelgen.feature.blockplacers.BlockPlacer
- net.minecraft.world.level.levelgen.feature.blockplacers.ColumnPlacer
- net.minecraft.world.level.levelgen.feature.blockplacers.SimpleBlockPlacer
- net.minecraft.world.level.levelgen.feature.BlueIceFeature
+ net.minecraft.world.level.levelgen.feature.BonusChestFeature
+ net.minecraft.world.level.levelgen.feature.BushConfiguration
+ net.minecraft.world.level.levelgen.feature.CactusFeature
- net.minecraft.world.level.levelgen.feature.configurations.BlockBlobConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.BlockStateConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ChanceRangeDecoratorConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.CountRangeDecoratorConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.DecoratorConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.EndGatewayConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.FeatureRadiusConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.LayerConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.MegaTreeConfiguration$MegaTreeConfigurationBuilder
- net.minecraft.world.level.levelgen.feature.configurations.NoiseDependantDecoratorConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.NoneFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ProbabilityFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration$1
- net.minecraft.world.level.levelgen.feature.configurations.RandomRandomFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SeagrassFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SimpleBlockConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SmallTreeConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SpikeConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.VillageConfiguration
+ net.minecraft.world.level.levelgen.feature.CountFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.DarkOakFeature
+ net.minecraft.world.level.levelgen.feature.DeadBushFeature
+ net.minecraft.world.level.levelgen.feature.DecoratedFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.DecoratedFlowerFeature
+ net.minecraft.world.level.levelgen.feature.DecoratorChanceRange
+ net.minecraft.world.level.levelgen.feature.DecoratorCountRange
+ net.minecraft.world.level.levelgen.feature.DefaultFlowerFeature
- net.minecraft.world.level.levelgen.feature.DesertPyramidFeature
+ net.minecraft.world.level.levelgen.feature.DesertPyramidFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.DesertVillagePools
+ net.minecraft.world.level.levelgen.feature.DesertWellFeature
+ net.minecraft.world.level.levelgen.feature.DoublePlantFeature
+ net.minecraft.world.level.levelgen.feature.EndGatewayFeature
- net.minecraft.world.level.levelgen.feature.EndIslandFeature
+ net.minecraft.world.level.levelgen.feature.EndPodiumFeature
- net.minecraft.world.level.levelgen.feature.FancyTreeFeature
- net.minecraft.world.level.levelgen.feature.Feature
+ net.minecraft.world.level.levelgen.feature.FeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.FillLayerFeature
- net.minecraft.world.level.levelgen.feature.foliageplacers.AcaciaFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.package-info
- net.minecraft.world.level.levelgen.feature.foliageplacers.PineFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.ForestFlowerFeature
- net.minecraft.world.level.levelgen.feature.FossilFeature
+ net.minecraft.world.level.levelgen.feature.GeneralForestFlowerFeature
+ net.minecraft.world.level.levelgen.feature.GrassConfiguration
+ net.minecraft.world.level.levelgen.feature.HellFireFeature
+ net.minecraft.world.level.levelgen.feature.HugeBrownMushroomFeature
+ net.minecraft.world.level.levelgen.feature.IcebergConfiguration
+ net.minecraft.world.level.levelgen.feature.IcePatchFeature
- net.minecraft.world.level.levelgen.feature.IceSpikeFeature
+ net.minecraft.world.level.levelgen.feature.JungleGrassFeature
- net.minecraft.world.level.levelgen.feature.JunglePyramidFeature
+ net.minecraft.world.level.levelgen.feature.JunglePyramidFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.LakeFeature
+ net.minecraft.world.level.levelgen.feature.MelonFeature
+ net.minecraft.world.level.levelgen.feature.MineshaftFeature
- net.minecraft.world.level.levelgen.feature.MineshaftFeature$MineShaftStart
+ net.minecraft.world.level.levelgen.feature.MineshaftFeature$Type
- net.minecraft.world.level.levelgen.feature.MonsterRoomFeature
+ net.minecraft.world.level.levelgen.feature.NetherFortressFeature
- net.minecraft.world.level.levelgen.feature.NetherFortressFeature$NetherBridgeStart
+ net.minecraft.world.level.levelgen.feature.NetherSpringFeature
+ net.minecraft.world.level.levelgen.feature.NoneFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.OreConfiguration
+ net.minecraft.world.level.levelgen.feature.OreFeature
+ net.minecraft.world.level.levelgen.feature.package-info
+ net.minecraft.world.level.levelgen.feature.PineFeature
+ net.minecraft.world.level.levelgen.feature.PumpkinBlockPileFeature
+ net.minecraft.world.level.levelgen.feature.RandomBooleanSelectorFeature
- net.minecraft.world.level.levelgen.feature.RandomPatchFeature
+ net.minecraft.world.level.levelgen.feature.RandomRandomFeature
+ net.minecraft.world.level.levelgen.feature.ReedsFeature
+ net.minecraft.world.level.levelgen.feature.SavannaVillagePools
+ net.minecraft.world.level.levelgen.feature.SeagrassFeature
- net.minecraft.world.level.levelgen.feature.SeaPickleFeature
+ net.minecraft.world.level.levelgen.feature.ShipwreckConfiguration
- net.minecraft.world.level.levelgen.feature.ShipwreckFeature
+ net.minecraft.world.level.levelgen.feature.ShipwreckFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.SimpleRandomSelectorFeature
- net.minecraft.world.level.levelgen.feature.SimulatedFeature
+ net.minecraft.world.level.levelgen.feature.SnowAndFreezeFeature
+ net.minecraft.world.level.levelgen.feature.SpikeFeature
- net.minecraft.world.level.levelgen.feature.SpikeFeature$1
+ net.minecraft.world.level.levelgen.feature.SpikeFeature$EndSpike
- net.minecraft.world.level.levelgen.feature.SpikeFeature$SpikeCacheLoader
+ net.minecraft.world.level.levelgen.feature.SpringConfiguration
+ net.minecraft.world.level.levelgen.feature.SpruceFeature
- net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.ForestFlowerProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.RotatedBlockProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.WeightedStateProvider
- net.minecraft.world.level.levelgen.feature.StrongholdFeature
+ net.minecraft.world.level.levelgen.feature.StrongholdFeature$StrongholdStart
- net.minecraft.world.level.levelgen.feature.StructureFeature
+ net.minecraft.world.level.levelgen.feature.StructureFeature$StructureStartFactory
- net.minecraft.world.level.levelgen.feature.StructurePieceType
- net.minecraft.world.level.levelgen.feature.structures.EmptyPoolElement
+ net.minecraft.world.level.levelgen.feature.structures.FeaturePoolElement
- net.minecraft.world.level.levelgen.feature.structures.JigsawJunction
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement
- net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$1
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$PieceFactory
- net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$PieceState
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$Placer
- net.minecraft.world.level.levelgen.feature.structures.ListPoolElement
+ net.minecraft.world.level.levelgen.feature.structures.package-info
+ net.minecraft.world.level.levelgen.feature.structures.SinglePoolElement
- net.minecraft.world.level.levelgen.feature.structures.StructurePoolElement
+ net.minecraft.world.level.levelgen.feature.structures.StructurePoolElementType
- net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool
+ net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool$Projection
- net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePools
+ net.minecraft.world.level.levelgen.feature.SwampFlowerFeature
+ net.minecraft.world.level.levelgen.feature.SwamplandHutFeature
- net.minecraft.world.level.levelgen.feature.SwamplandHutFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.TaigaGrassFeature
- net.minecraft.world.level.levelgen.feature.treedecorators.AlterGroundDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.CocoaDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.TrunkVineDecorator
+ net.minecraft.world.level.levelgen.feature.VillageFeature
- net.minecraft.world.level.levelgen.feature.VillageFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.VillagePieces
- net.minecraft.world.level.levelgen.feature.VillagePieces$VillagePiece
+ net.minecraft.world.level.levelgen.feature.VinesFeature
- net.minecraft.world.level.levelgen.feature.VoidStartPlatformFeature
+ net.minecraft.world.level.levelgen.feature.WaterlilyFeature
- net.minecraft.world.level.levelgen.flat.FlatLayerInfo
+ net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorSettings
- net.minecraft.world.level.levelgen.flat.package-info
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
+ net.minecraft.world.level.levelgen.package-info
+ net.minecraft.world.level.levelgen.PatrolSpawner
- net.minecraft.world.level.levelgen.PhantomSpawner
- net.minecraft.world.level.levelgen.placement.CarvingMaskDecorator
- net.minecraft.world.level.levelgen.placement.ChanceDecoratorConfiguration
+ net.minecraft.world.level.levelgen.placement.ChanceHeightmapDecorator
- net.minecraft.world.level.levelgen.placement.ChanceHeightmapDoubleDecorator
+ net.minecraft.world.level.levelgen.placement.ChancePassthroughDecorator
- net.minecraft.world.level.levelgen.placement.ChanceTopSolidHeightmapDecorator
+ net.minecraft.world.level.levelgen.placement.ChorusPlantPlacementDecorator
- net.minecraft.world.level.levelgen.placement.ConfiguredDecorator
+ net.minecraft.world.level.levelgen.placement.CountBiasedRangeDecorator
- net.minecraft.world.level.levelgen.placement.CountChanceHeightmapDecorator
+ net.minecraft.world.level.levelgen.placement.CountChanceHeightmapDoubleDecorator
- net.minecraft.world.level.levelgen.placement.CountDepthAverageDecorator
+ net.minecraft.world.level.levelgen.placement.CountHeighmapDoubleDecorator
- net.minecraft.world.level.levelgen.placement.CountHeight64Decorator
+ net.minecraft.world.level.levelgen.placement.CountHeightmap32Decorator
- net.minecraft.world.level.levelgen.placement.CountHeightmapDecorator
+ net.minecraft.world.level.levelgen.placement.CountTopSolidDecorator
- net.minecraft.world.level.levelgen.placement.CountVeryBiasedRangeDecorator
+ net.minecraft.world.level.levelgen.placement.CountWithExtraChanceHeightmapDecorator
- net.minecraft.world.level.levelgen.placement.DarkOakTreePlacementDecorator
+ net.minecraft.world.level.levelgen.placement.DecoratorCarvingMaskConfig
+ net.minecraft.world.level.levelgen.placement.DecoratorFrequency
+ net.minecraft.world.level.levelgen.placement.DecoratorFrequencyWithExtraChance
+ net.minecraft.world.level.levelgen.placement.DecoratorRange
- net.minecraft.world.level.levelgen.placement.FrequencyDecoratorConfiguration
- net.minecraft.world.level.levelgen.placement.IcebergPlacementDecorator
+ net.minecraft.world.level.levelgen.placement.LakeChanceDecoratorConfig
+ net.minecraft.world.level.levelgen.placement.MonsterRoomPlacementDecorator
+ net.minecraft.world.level.levelgen.placement.nether.ChanceRangeDecorator
- net.minecraft.world.level.levelgen.placement.nether.CountRangeDecorator
+ net.minecraft.world.level.levelgen.placement.nether.HellFireDecorator
- net.minecraft.world.level.levelgen.placement.nether.LightGemChanceDecorator
+ net.minecraft.world.level.levelgen.placement.nether.MagmaDecorator
+ net.minecraft.world.level.levelgen.placement.nether.package-info
- net.minecraft.world.level.levelgen.placement.nether.RandomCountRangeDecorator
- net.minecraft.world.level.levelgen.placement.NoiseCountFactorDecoratorConfiguration
- net.minecraft.world.level.levelgen.placement.package-info
- net.minecraft.world.level.levelgen.placement.RangeDecoratorConfiguration
+ net.minecraft.world.level.levelgen.placement.SimpleFeatureDecorator
- net.minecraft.world.level.levelgen.placement.TopSolidHeightMapDecorator
+ net.minecraft.world.level.levelgen.placement.TopSolidHeightMapNoiseBasedDecorator
- net.minecraft.world.level.levelgen.placement.TopSolidHeightMapRangeDecorator
+ net.minecraft.world.level.levelgen.structure.BeardedStructureStart
- net.minecraft.world.level.levelgen.structure.BoundingBox
+ net.minecraft.world.level.levelgen.structure.BoundingBox$1
- net.minecraft.world.level.levelgen.structure.BuriedTreasurePieces
+ net.minecraft.world.level.levelgen.structure.BuriedTreasurePieces$BuriedTreasurePiece
- net.minecraft.world.level.levelgen.structure.DesertPyramidPiece
+ net.minecraft.world.level.levelgen.structure.EndCityPieces
- net.minecraft.world.level.levelgen.structure.EndCityPieces$1
+ net.minecraft.world.level.levelgen.structure.EndCityPieces$2
- net.minecraft.world.level.levelgen.structure.EndCityPieces$3
+ net.minecraft.world.level.levelgen.structure.EndCityPieces$4
- net.minecraft.world.level.levelgen.structure.EndCityPieces$EndCityPiece
+ net.minecraft.world.level.levelgen.structure.EndCityPieces$SectionGenerator
- net.minecraft.world.level.levelgen.structure.IglooPieces
+ net.minecraft.world.level.levelgen.structure.IglooPieces$IglooPiece
- net.minecraft.world.level.levelgen.structure.JunglePyramidPiece
+ net.minecraft.world.level.levelgen.structure.JunglePyramidPiece$1
- net.minecraft.world.level.levelgen.structure.JunglePyramidPiece$MossStoneSelector
+ net.minecraft.world.level.levelgen.structure.LegacyStructureDataHandler
- net.minecraft.world.level.levelgen.structure.MineShaftPieces
+ net.minecraft.world.level.levelgen.structure.MineShaftPieces$1
- net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftCorridor
+ net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftCrossing
- net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftPiece
+ net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftRoom
- net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftStairs
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$1
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$BridgeCrossing
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$BridgeEndFiller
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$BridgeStraight
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleCorridorStairsPiece
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleCorridorTBalconyPiece
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleEntrance
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorCrossingPiece
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorLeftTurnPiece
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorPiece
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorRightTurnPiece
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleStalkRoom
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$MonsterThrone
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$NetherBridgePiece
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$PieceWeight
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$RoomCrossing
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$StairsRoom
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$StartPiece
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$1
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleXRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleXYRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleYRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleYZRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleZRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitSimpleRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitSimpleTopRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$MonumentBuilding
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$MonumentRoomFitter
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentCoreRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXYRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYZRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleZRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentEntryRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentPenthouse
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentPiece
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleTopRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentWingRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$RoomDefinition
- net.minecraft.world.level.levelgen.structure.OceanRuinFeature
+ net.minecraft.world.level.levelgen.structure.OceanRuinFeature$OceanRuinStart
- net.minecraft.world.level.levelgen.structure.OceanRuinFeature$Type
+ net.minecraft.world.level.levelgen.structure.OceanRuinPieces
- net.minecraft.world.level.levelgen.structure.OceanRuinPieces$OceanRuinPiece
+ net.minecraft.world.level.levelgen.structure.package-info
+ net.minecraft.world.level.levelgen.structure.PillagerOutpostPieces
- net.minecraft.world.level.levelgen.structure.PillagerOutpostPieces$PillagerOutpostPiece
+ net.minecraft.world.level.levelgen.structure.PoolElementStructurePiece
- net.minecraft.world.level.levelgen.structure.ScatteredFeaturePiece
+ net.minecraft.world.level.levelgen.structure.ShipwreckPieces
- net.minecraft.world.level.levelgen.structure.ShipwreckPieces$ShipwreckPiece
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$1
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$2
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$3
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$ChestCorridor
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$FillerCorridor
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$FiveCrossing
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$LeftTurn
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$Library
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$PieceWeight
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$PortalRoom
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$PrisonHall
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$RightTurn
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$RoomCrossing
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$SmoothStoneSelector
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$StairsDown
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$StartPiece
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$Straight
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$StraightStairsDown
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$StrongholdPiece
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$StrongholdPiece$SmallDoorType
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$Turn
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
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockIgnoreProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockMatchTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockRotProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockStateMatchTest
+ net.minecraft.world.level.levelgen.structure.templatesystem.GravityProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.JigsawReplacementProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.NopProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.package-info
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
+ net.minecraft.world.level.levelgen.surfacebuilders.BadlandsSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.ConfiguredSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.DefaultSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.ErodedBadlandsSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.FrozenOceanSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.GiantTreeTaigaSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.GravellyMountainSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.MountainSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.NetherSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.NopeSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.package-info
+ net.minecraft.world.level.levelgen.surfacebuilders.ShatteredSavanaSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.SurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.SurfaceBuilderBaseConfiguration
- net.minecraft.world.level.levelgen.surfacebuilders.SurfaceBuilderConfiguration
+ net.minecraft.world.level.levelgen.surfacebuilders.SwampSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.WoodedBadlandsSurfaceBuilder
- net.minecraft.world.level.levelgen.synth.ImprovedNoise
+ net.minecraft.world.level.levelgen.synth.package-info
+ net.minecraft.world.level.levelgen.synth.PerlinNoise
- net.minecraft.world.level.levelgen.synth.PerlinSimplexNoise
+ net.minecraft.world.level.levelgen.synth.SimplexNoise
- net.minecraft.world.level.levelgen.synth.SurfaceNoise
+ net.minecraft.world.level.levelgen.TheEndGeneratorSettings
- net.minecraft.world.level.levelgen.TheEndLevelSource
+ net.minecraft.world.level.levelgen.WorldgenRandom
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
- net.minecraft.world.level.material.EmptyFluid
+ net.minecraft.world.level.material.FlowingFluid
- net.minecraft.world.level.material.FlowingFluid$1
+ net.minecraft.world.level.material.Fluid
- net.minecraft.world.level.material.Fluids
- net.minecraft.world.level.material.FluidState
+ net.minecraft.world.level.material.FluidStateImpl
+ net.minecraft.world.level.material.LavaFluid
- net.minecraft.world.level.material.LavaFluid$Flowing
+ net.minecraft.world.level.material.LavaFluid$Source
- net.minecraft.world.level.material.Material
+ net.minecraft.world.level.material.Material$Builder
- net.minecraft.world.level.material.MaterialColor
+ net.minecraft.world.level.material.package-info
+ net.minecraft.world.level.material.PushReaction
- net.minecraft.world.level.material.WaterFluid
+ net.minecraft.world.level.material.WaterFluid$Flowing
- net.minecraft.world.level.material.WaterFluid$Source
- net.minecraft.world.level.newbiome.area.Area
+ net.minecraft.world.level.newbiome.area.AreaFactory
- net.minecraft.world.level.newbiome.area.LazyArea
+ net.minecraft.world.level.newbiome.area.package-info
- net.minecraft.world.level.newbiome.context.BigContext
+ net.minecraft.world.level.newbiome.context.Context
- net.minecraft.world.level.newbiome.context.LazyAreaContext
+ net.minecraft.world.level.newbiome.context.package-info
- net.minecraft.world.level.newbiome.layer.AddDeepOceanLayer
+ net.minecraft.world.level.newbiome.layer.AddEdgeLayer
- net.minecraft.world.level.newbiome.layer.AddEdgeLayer$CoolWarm
+ net.minecraft.world.level.newbiome.layer.AddEdgeLayer$HeatIce
- net.minecraft.world.level.newbiome.layer.AddEdgeLayer$IntroduceSpecial
+ net.minecraft.world.level.newbiome.layer.AddIslandLayer
- net.minecraft.world.level.newbiome.layer.AddMushroomIslandLayer
+ net.minecraft.world.level.newbiome.layer.AddSnowLayer
- net.minecraft.world.level.newbiome.layer.BiomeEdgeLayer
+ net.minecraft.world.level.newbiome.layer.BiomeInitLayer
- net.minecraft.world.level.newbiome.layer.IslandLayer
+ net.minecraft.world.level.newbiome.layer.Layer
- net.minecraft.world.level.newbiome.layer.Layers
+ net.minecraft.world.level.newbiome.layer.OceanLayer
- net.minecraft.world.level.newbiome.layer.OceanMixerLayer
- net.minecraft.world.level.newbiome.layer.package-info
+ net.minecraft.world.level.newbiome.layer.RareBiomeLargeLayer
- net.minecraft.world.level.newbiome.layer.RareBiomeSpotLayer
+ net.minecraft.world.level.newbiome.layer.RegionHillsLayer
- net.minecraft.world.level.newbiome.layer.RemoveTooMuchOceanLayer
+ net.minecraft.world.level.newbiome.layer.RiverInitLayer
- net.minecraft.world.level.newbiome.layer.RiverLayer
+ net.minecraft.world.level.newbiome.layer.RiverMixerLayer
- net.minecraft.world.level.newbiome.layer.ShoreLayer
+ net.minecraft.world.level.newbiome.layer.SmoothLayer
+ net.minecraft.world.level.newbiome.layer.traits.AreaTransformer0
- net.minecraft.world.level.newbiome.layer.traits.AreaTransformer1
+ net.minecraft.world.level.newbiome.layer.traits.AreaTransformer2
- net.minecraft.world.level.newbiome.layer.traits.BishopTransformer
+ net.minecraft.world.level.newbiome.layer.traits.C0Transformer
- net.minecraft.world.level.newbiome.layer.traits.C1Transformer
+ net.minecraft.world.level.newbiome.layer.traits.CastleTransformer
- net.minecraft.world.level.newbiome.layer.traits.DimensionOffset0Transformer
+ net.minecraft.world.level.newbiome.layer.traits.DimensionOffset1Transformer
- net.minecraft.world.level.newbiome.layer.traits.DimensionTransformer
- net.minecraft.world.level.newbiome.layer.traits.package-info
+ net.minecraft.world.level.newbiome.layer.traits.PixelTransformer
- net.minecraft.world.level.newbiome.layer.ZoomLayer
+ net.minecraft.world.level.newbiome.layer.ZoomLayer$1
+ net.minecraft.world.level.package-info
- net.minecraft.world.level.pathfinder.BinaryHeap
+ net.minecraft.world.level.pathfinder.BlockPathTypes
- net.minecraft.world.level.pathfinder.FlyNodeEvaluator
+ net.minecraft.world.level.pathfinder.Node
- net.minecraft.world.level.pathfinder.NodeEvaluator
- net.minecraft.world.level.pathfinder.package-info
+ net.minecraft.world.level.pathfinder.Path
- net.minecraft.world.level.pathfinder.PathComputationType
+ net.minecraft.world.level.pathfinder.PathFinder
- net.minecraft.world.level.pathfinder.SwimNodeEvaluator
+ net.minecraft.world.level.pathfinder.Target
- net.minecraft.world.level.pathfinder.TurtleNodeEvaluator
+ net.minecraft.world.level.pathfinder.WalkNodeEvaluator
- net.minecraft.world.level.redstone.package-info
+ net.minecraft.world.level.redstone.Redstone
+ net.minecraft.world.level.saveddata.maps.MapBanner
- net.minecraft.world.level.saveddata.maps.MapBanner$1
+ net.minecraft.world.level.saveddata.maps.MapDecoration
- net.minecraft.world.level.saveddata.maps.MapDecoration$Type
+ net.minecraft.world.level.saveddata.maps.MapFrame
- net.minecraft.world.level.saveddata.maps.MapIndex
+ net.minecraft.world.level.saveddata.maps.MapItemSavedData
- net.minecraft.world.level.saveddata.maps.MapItemSavedData$HoldingPlayer
+ net.minecraft.world.level.saveddata.maps.package-info
- net.minecraft.world.level.saveddata.package-info
+ net.minecraft.world.level.saveddata.SaveDataDirtyRunnable
- net.minecraft.world.level.saveddata.SavedData
+ net.minecraft.world.level.storage.CommandStorage
- net.minecraft.world.level.storage.CommandStorage$Container
+ net.minecraft.world.level.storage.DerivedLevelData
- net.minecraft.world.level.storage.DimensionDataStorage
+ net.minecraft.world.level.storage.LevelData
- net.minecraft.world.level.storage.LevelStorage
+ net.minecraft.world.level.storage.LevelStorageException
- net.minecraft.world.level.storage.LevelStorageSource
+ net.minecraft.world.level.storage.LevelStorageSource$1
- net.minecraft.world.level.storage.LevelSummary
+ net.minecraft.world.level.storage.loot.BinomialDistributionGenerator
- net.minecraft.world.level.storage.loot.BinomialDistributionGenerator$Serializer
+ net.minecraft.world.level.storage.loot.BuiltInLootTables
- net.minecraft.world.level.storage.loot.ConstantIntValue
+ net.minecraft.world.level.storage.loot.ConstantIntValue$Serializer
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
+ net.minecraft.world.level.storage.McRegionUpgrader
- net.minecraft.world.level.storage.package-info
- net.minecraft.world.level.storage.PlayerIO
+ net.minecraft.world.level.storage.threaded.package-info
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
XXX.mojang.math.Matrix3f +1M
```
```
XXX.mojang.math.Quaternion +1M -1M
```
```
XXX.mojang.math.Vector3f +1M -1M
```
```
XXX.minecraft.core.BlockPos +1M
```
```
XXX.minecraft.core.BlockPos$MutableBlockPos +1M
```
```
XXX.server.level.ServerLevel +5M -2M
```
```
XXX.util.datafix.DataFixers +2M
```
```
XXX.world.entity.Entity +18M -1M
```
```
XXX.world.entity.FlyingMob +1M -1M
```
```
XXX.world.entity.LivingEntity +3M -1M
```
```
XXX.ai.behavior.MoveToSkySeeingSpot +1M -1M
```
```
XXX.ai.behavior.WeightedList +13M -3M
```
```
XXX.ai.behavior.WeightedList$WeightedEntry +3M
```
```
XXX.entity.animal.Ocelot +1M -1M
```
```
XXX.entity.animal.Parrot +1M -1M
```
```
XXX.animal.horse.AbstractHorse +2M -1M
```
```
XXX.animal.horse.Llama +1M -1M
```
```
XXX.boss.wither.WitherBoss +1M -1M
```
```
XXX.entity.item.FallingBlockEntity +1M -1M
```
```
XXX.entity.monster.Creeper +1M -1M
```
```
XXX.entity.monster.MagmaCube +1M -1M
```
```
XXX.level.biome.BiomeDefaultFeatures +1M | +119P
```
```
XXX.level.block.BeehiveBlock +1M -1M
```
```
XXX.level.block.Blocks +3P -1P
```
```
XXX.levelgen.feature.ChorusPlantFeature +2M -2M
```
```
XXX.levelgen.feature.DiskReplaceFeature +2M -2M
```
```
XXX.levelgen.feature.GroundBushFeature +2M -2M | -2P
```
```
XXX.levelgen.feature.HugeRedMushroomFeature +2M -2M
```
```
XXX.levelgen.feature.KelpFeature +2M -2M
```
```
XXX.levelgen.feature.MegaJungleTreeFeature +4M -4M
```
```
XXX.levelgen.feature.MegaTreeFeature +5M -4M | -4P
```
```
XXX.levelgen.feature.ReplaceBlockFeature +2M -2M
```
```
XXX.levelgen.feature.SimpleBlockFeature +2M -2M
```
```
XXX.levelgen.feature.TreeFeature +3M -8M | -6P
```
```
XXX.levelgen.placement.EmeraldPlacementDecorator +2M -2M
```
```
XXX.levelgen.placement.EndIslandPlacementDecorator +2M -2M
```
```
XXX.levelgen.placement.ForestRockPlacementDecorator +3M -3M
```
```
XXX.levelgen.placement.LakeWaterPlacementDecorator +2M -2M
```
```
XXX.levelgen.placement.NoiseHeightmapDoubleDecorator +3M -3M
```

</details>
<details>
<summary>
com.mojang.math.Matrix3f
</summary>

```diff
- void <init>(float[])
```

</details>
<details>
<summary>
com.mojang.math.Quaternion
</summary>

```diff
+ void <init>()
- void <init>(float[])
```

</details>
<details>
<summary>
com.mojang.math.Vector3f
</summary>

```diff
+ Quaternion rotation(float,boolean)
- Quaternion rotationDegrees(float)
```

</details>













































































































































<details>
<summary>
net.minecraft.core.BlockPos
</summary>

```diff
- Stream betweenClosedStream(BoundingBox)
```

</details>

<details>
<summary>
net.minecraft.core.BlockPos$MutableBlockPos
</summary>

```diff
- void <init>(Entity)
```

</details>











































































































<details>
<summary>
net.minecraft.server.level.ServerLevel
</summary>

```diff
- boolean lambda$clearBlockEvents$15(BoundingBox,BlockEventData)
- void clearBlockEvents(BoundingBox)
- void lambda$tick$6(Entity)
+ void lambda$tick$6(ServerPlayer)
+ void lambda$tick$7(Entity)
- void lambda$wakeUpAllPlayers$7(ServerPlayer)
- void wakeUpAllPlayers()
```

</details>






















































































<details>
<summary>
net.minecraft.util.datafix.DataFixers
</summary>

```diff
- String lambda$addFixers$24(String)
- String lambda$addFixers$25(String)
```

</details>










































































<details>
<summary>
net.minecraft.world.entity.Entity
</summary>

```diff
- BlockPos getBlockPosBelowThatAffectsMyMovement()
- BlockPos getOnPos()
- boolean causeFallDamage(float,float)
- Component getTypeName()
- double getEyeY()
- double getRandomX(double)
- double getRandomY()
- double getRandomZ(double)
- double getX()
- double getX(double)
- double getY()
- double getY(double)
- double getZ()
- double getZ(double)
- float getJumpFactor()
- float getSpeedFactor()
+ void causeFallDamage(float,float)
- void refreshBoundingBox()
- void setPosRaw(double,double,double)
```

</details>





<details>
<summary>
net.minecraft.world.entity.FlyingMob
</summary>

```diff
- boolean causeFallDamage(float,float)
+ void causeFallDamage(float,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.LivingEntity
</summary>

```diff
- boolean causeFallDamage(float,float)
- int calculateFallDamage(float,float)
+ void causeFallDamage(float,float)
- void playBlockFallSound()
```

</details>





























<details>
<summary>
net.minecraft.world.entity.ai.behavior.MoveToSkySeeingSpot
</summary>

```diff
- boolean hasNoBlocksAbove(ServerLevel,LivingEntity,BlockPos)
+ boolean hasNoBlocksAbove(ServerLevel,LivingEntity)
```

</details>
















<details>
<summary>
net.minecraft.world.entity.ai.behavior.WeightedList
</summary>

```diff
- double lambda$shuffle$4(Object)
- Object getOne()
- Object getOne(Random)
- Object lambda$serialize$2(DynamicOps,Function,WeightedList$WeightedEntry)
- Object serialize(DynamicOps,Function)
- Stream streamEntries()
- void <init>(Dynamic,Function)
+ void add(Object,int)
- void lambda$new$1(Function,Dynamic)
+ void lambda$shuffle$0(WeightedList$WeightedEntry)
- void lambda$shuffle$3(Random,WeightedList$WeightedEntry)
+ void shuffle()
- WeightedList add(Object,int)
- WeightedList lambda$null$0(Function,Dynamic,Dynamic)
- WeightedList shuffle()
- WeightedList shuffle(Random)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.behavior.WeightedList$WeightedEntry
</summary>

```diff
- double access$100(WeightedList$WeightedEntry)
- int getWeight()
- void access$200(WeightedList$WeightedEntry,float)
```

</details>














<details>
<summary>
net.minecraft.world.entity.animal.Ocelot
</summary>

```diff
- boolean causeFallDamage(float,float)
+ void causeFallDamage(float,float)
```

</details>







<details>
<summary>
net.minecraft.world.entity.animal.Parrot
</summary>

```diff
- boolean causeFallDamage(float,float)
+ void causeFallDamage(float,float)
```

</details>























<details>
<summary>
net.minecraft.world.entity.animal.horse.AbstractHorse
</summary>

```diff
- boolean causeFallDamage(float,float)
- int calculateFallDamage(float,float)
+ void causeFallDamage(float,float)
```

</details>

<details>
<summary>
net.minecraft.world.entity.animal.horse.Llama
</summary>

```diff
- boolean causeFallDamage(float,float)
+ void causeFallDamage(float,float)
```

</details>

















<details>
<summary>
net.minecraft.world.entity.boss.wither.WitherBoss
</summary>

```diff
- boolean causeFallDamage(float,float)
+ void causeFallDamage(float,float)
```

</details>








<details>
<summary>
net.minecraft.world.entity.item.FallingBlockEntity
</summary>

```diff
- boolean causeFallDamage(float,float)
+ void causeFallDamage(float,float)
```

</details>





<details>
<summary>
net.minecraft.world.entity.monster.Creeper
</summary>

```diff
- boolean causeFallDamage(float,float)
+ void causeFallDamage(float,float)
```

</details>


















<details>
<summary>
net.minecraft.world.entity.monster.MagmaCube
</summary>

```diff
- boolean causeFallDamage(float,float)
+ void causeFallDamage(float,float)
```

</details>




















































































































































































































































































<details>
<summary>
net.minecraft.world.level.biome.BiomeDefaultFeatures
</summary>

```diff
- void <clinit>()
```

</details>
























































<details>
<summary>
net.minecraft.world.level.block.BeehiveBlock
</summary>

```diff
- void releaseBeesAndResetState(Level,BlockState,BlockPos,Player,BeehiveBlockEntity$BeeReleaseStatus)
+ void releaseBeesAndResetState(Level,BlockState,BlockPos,Player)
```

</details>
















































<details>
<summary>
net.minecraft.world.level.levelgen.feature.ChorusPlantFeature
</summary>

```diff
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
- boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,NoneFeatureConfiguration)
- boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,NoneFeatureConfiguration)
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.feature.DiskReplaceFeature
</summary>

```diff
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,DiskConfiguration)
- boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,DiskConfiguration)
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
- boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.GroundBushFeature
</summary>

```diff
- boolean doPlace(LevelSimulatedRW,Random,BlockPos,Set,Set,BoundingBox,TreeConfiguration)
+ boolean doPlace(Set,LevelSimulatedRW,Random,BlockPos,BoundingBox)
+ void <init>(Function,BlockState,BlockState)
- void <init>(Function)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.HugeRedMushroomFeature
</summary>

```diff
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,HugeMushroomFeatureConfig)
- int getTreeRadiusForHeight(int,int,int,int)
- void makeCap(LevelAccessor,Random,BlockPos,int,BlockPos$MutableBlockPos,HugeMushroomFeatureConfiguration)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.KelpFeature
</summary>

```diff
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
- boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,NoneFeatureConfiguration)
- boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,NoneFeatureConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.MegaJungleTreeFeature
</summary>

```diff
- boolean doPlace(LevelSimulatedRW,Random,BlockPos,Set,Set,BoundingBox,MegaTreeConfiguration)
- boolean doPlace(LevelSimulatedRW,Random,BlockPos,Set,Set,BoundingBox,TreeConfiguration)
+ boolean doPlace(Set,LevelSimulatedRW,Random,BlockPos,BoundingBox)
+ void <init>(Function,boolean,int,int,BlockState,BlockState)
- void <init>(Function)
+ void createCrown(LevelSimulatedRW,BlockPos,int,BoundingBox,Set)
- void createCrown(LevelSimulatedRW,Random,BlockPos,int,Set,BoundingBox,TreeConfiguration)
+ void placeVine(LevelSimulatedRW,Random,BlockPos,BooleanProperty)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.MegaTreeFeature
</summary>

```diff
- int calcTreeHeigth(Random,MegaTreeConfiguration)
+ int calcTreeHeigth(Random)
+ void <init>(Function,boolean,int,int,BlockState,BlockState)
- void <init>(Function)
+ void placeDoubleTrunkLeaves(LevelSimulatedRW,BlockPos,int,BoundingBox,Set)
- void placeDoubleTrunkLeaves(LevelSimulatedRW,Random,BlockPos,int,Set,BoundingBox,TreeConfiguration)
+ void placeSingleTrunkLeaves(LevelSimulatedRW,BlockPos,int,BoundingBox,Set)
- void placeSingleTrunkLeaves(LevelSimulatedRW,Random,BlockPos,int,Set,BoundingBox,TreeConfiguration)
- void placeTrunk(LevelSimulatedRW,Random,BlockPos,int,Set,BoundingBox,MegaTreeConfiguration)
```

</details>




<details>
<summary>
net.minecraft.world.level.levelgen.feature.ReplaceBlockFeature
</summary>

```diff
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
- boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,ReplaceBlockConfiguration)
- boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,ReplaceBlockConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.SimpleBlockFeature
</summary>

```diff
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
- boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,SimpleBlockConfiguration)
- boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,SimpleBlockConfiguration)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.TreeFeature
</summary>

```diff
- boolean doPlace(LevelSimulatedRW,Random,BlockPos,Set,Set,BoundingBox,SmallTreeConfiguration)
- boolean doPlace(LevelSimulatedRW,Random,BlockPos,Set,Set,BoundingBox,TreeConfiguration)
+ boolean doPlace(Set,LevelSimulatedRW,Random,BlockPos,BoundingBox)
+ int getTreeHeight(Random)
+ void <clinit>()
+ void <init>(Function,boolean,int,BlockState,BlockState,boolean)
+ void <init>(Function,boolean)
- void <init>(Function)
+ void addHangingVine(LevelSimulatedRW,BlockPos,BooleanProperty)
+ void addVine(LevelWriter,BlockPos,BooleanProperty)
+ void placeCocoa(LevelWriter,int,BlockPos,Direction)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.placement.EmeraldPlacementDecorator
</summary>

```diff
+ Stream place(Random,DecoratorConfiguration,BlockPos)
- Stream place(Random,DecoratorConfiguration,BlockPos)
+ Stream place(Random,NoneDecoratorConfiguration,BlockPos)
- Stream place(Random,NoneDecoratorConfiguration,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.EndIslandPlacementDecorator
</summary>

```diff
+ Stream place(Random,DecoratorConfiguration,BlockPos)
- Stream place(Random,DecoratorConfiguration,BlockPos)
+ Stream place(Random,NoneDecoratorConfiguration,BlockPos)
- Stream place(Random,NoneDecoratorConfiguration,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.ForestRockPlacementDecorator
</summary>

```diff
- BlockPos lambda$getPositions$0(Random,BlockPos,LevelAccessor,int)
+ BlockPos lambda$getPositions$0(Random,LevelAccessor,BlockPos,int)
+ Stream getPositions(LevelAccessor,ChunkGenerator,Random,DecoratorConfiguration,BlockPos)
- Stream getPositions(LevelAccessor,ChunkGenerator,Random,DecoratorConfiguration,BlockPos)
+ Stream getPositions(LevelAccessor,ChunkGenerator,Random,DecoratorFrequency,BlockPos)
- Stream getPositions(LevelAccessor,ChunkGenerator,Random,FrequencyDecoratorConfiguration,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.LakeWaterPlacementDecorator
</summary>

```diff
- Stream getPositions(LevelAccessor,ChunkGenerator,Random,ChanceDecoratorConfiguration,BlockPos)
+ Stream getPositions(LevelAccessor,ChunkGenerator,Random,DecoratorConfiguration,BlockPos)
- Stream getPositions(LevelAccessor,ChunkGenerator,Random,DecoratorConfiguration,BlockPos)
+ Stream getPositions(LevelAccessor,ChunkGenerator,Random,LakeChanceDecoratorConfig,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.NoiseHeightmapDoubleDecorator
</summary>

```diff
- BlockPos lambda$getPositions$0(Random,BlockPos,LevelAccessor,int)
+ BlockPos lambda$getPositions$0(Random,LevelAccessor,BlockPos,int)
+ Stream getPositions(LevelAccessor,ChunkGenerator,Random,DecoratorConfiguration,BlockPos)
- Stream getPositions(LevelAccessor,ChunkGenerator,Random,DecoratorConfiguration,BlockPos)
+ Stream getPositions(LevelAccessor,ChunkGenerator,Random,DecoratorNoiseDependant,BlockPos)
- Stream getPositions(LevelAccessor,ChunkGenerator,Random,NoiseDependantDecoratorConfiguration,BlockPos)
```

</details>
<h2>Client</h2>
<details>
<summary>
Classes
</summary>

```diff
+ com.mojang.blaze3d.platform.GlStateManager$CullState
- com.mojang.blaze3d.platform.GlStateManager$DepthState
+ com.mojang.blaze3d.platform.GlStateManager$DestFactor
- com.mojang.blaze3d.platform.GlStateManager$FboMode
+ com.mojang.blaze3d.platform.GlStateManager$FogMode
- com.mojang.blaze3d.platform.GlStateManager$FogState
+ com.mojang.blaze3d.platform.GlStateManager$LogicOp
- com.mojang.blaze3d.platform.GlStateManager$PolygonOffsetState
+ com.mojang.blaze3d.platform.GlStateManager$SourceFactor
- com.mojang.blaze3d.platform.GlStateManager$StencilFunc
+ com.mojang.blaze3d.platform.GlStateManager$StencilState
- com.mojang.blaze3d.platform.GlStateManager$TexGen
+ com.mojang.blaze3d.platform.GlStateManager$TexGenCoord
- com.mojang.blaze3d.platform.GlStateManager$TexGenState
+ com.mojang.blaze3d.platform.GlStateManager$TextureState
- com.mojang.blaze3d.platform.GlStateManager$Viewport
+ com.mojang.blaze3d.platform.GlUtil
- com.mojang.blaze3d.platform.InputConstants
+ com.mojang.blaze3d.platform.InputConstants$1
- com.mojang.blaze3d.platform.InputConstants$Key
+ com.mojang.blaze3d.platform.InputConstants$Type
- com.mojang.blaze3d.platform.Lighting
+ com.mojang.blaze3d.platform.MemoryTracker
- com.mojang.blaze3d.platform.Monitor
+ com.mojang.blaze3d.platform.MonitorCreator
- com.mojang.blaze3d.platform.NativeImage
+ com.mojang.blaze3d.platform.NativeImage$1
- com.mojang.blaze3d.platform.NativeImage$Format
+ com.mojang.blaze3d.platform.NativeImage$InternalGlFormat
- com.mojang.blaze3d.platform.NativeImage$WriteCallback
+ com.mojang.blaze3d.platform.PngInfo
- com.mojang.blaze3d.platform.PngInfo$1
+ com.mojang.blaze3d.platform.PngInfo$StbReader
- com.mojang.blaze3d.platform.PngInfo$StbReaderBufferedChannel
+ com.mojang.blaze3d.platform.PngInfo$StbReaderSeekableByteChannel
- com.mojang.blaze3d.platform.ScreenManager
+ com.mojang.blaze3d.platform.SnooperAccess
- com.mojang.blaze3d.platform.TextureUtil
+ com.mojang.blaze3d.platform.VideoMode
- com.mojang.blaze3d.platform.Window
+ com.mojang.blaze3d.platform.WindowEventHandler
- com.mojang.blaze3d.shaders.AbstractUniform
+ com.mojang.blaze3d.shaders.BlendMode
- com.mojang.blaze3d.shaders.Effect
+ com.mojang.blaze3d.shaders.Program
- com.mojang.blaze3d.shaders.Program$Type
+ com.mojang.blaze3d.shaders.ProgramManager
- com.mojang.blaze3d.shaders.Uniform
+ com.mojang.blaze3d.systems.RenderSystem
- com.mojang.blaze3d.vertex.BreakingTextureGenerator
+ com.mojang.blaze3d.vertex.BreakingTextureGenerator$1
- com.mojang.blaze3d.vertex.BufferBuilder
+ com.mojang.blaze3d.vertex.BufferBuilder$1
- com.mojang.blaze3d.vertex.BufferBuilder$DrawState
+ com.mojang.blaze3d.vertex.BufferBuilder$State
- com.mojang.blaze3d.vertex.BufferUploader
+ com.mojang.blaze3d.vertex.BufferVertexConsumer
+ com.mojang.blaze3d.vertex.DefaultedVertexConsumer
- com.mojang.blaze3d.vertex.DefaultVertexFormat
- com.mojang.blaze3d.vertex.PoseStack
- com.mojang.blaze3d.vertex.PoseStack$Pose
+ com.mojang.blaze3d.vertex.Tesselator
- com.mojang.blaze3d.vertex.VertexBuffer
+ com.mojang.blaze3d.vertex.VertexConsumer
- com.mojang.blaze3d.vertex.VertexFormat
+ com.mojang.blaze3d.vertex.VertexFormatElement
- com.mojang.blaze3d.vertex.VertexFormatElement$Type
+ com.mojang.blaze3d.vertex.VertexFormatElement$Usage
- com.mojang.blaze3d.vertex.VertexFormatElement$Usage$SetupState
+ com.mojang.blaze3d.vertex.VertexMultiConsumer
- com.mojang.math.Matrix3f
+ com.mojang.math.Matrix4f
- com.mojang.math.Quaternion
+ com.mojang.math.Transformation
- com.mojang.math.Vector3d
+ com.mojang.math.Vector3f
- com.mojang.math.Vector4f
- com.mojang.realmsclient.client.FileDownload
+ com.mojang.realmsclient.client.FileDownload$1
- com.mojang.realmsclient.client.FileDownload$DownloadCountingOutputStream
+ com.mojang.realmsclient.client.FileDownload$ProgressListener
- com.mojang.realmsclient.client.FileDownload$ResourcePackProgressListener
+ com.mojang.realmsclient.client.FileUpload
- com.mojang.realmsclient.client.FileUpload$CustomInputStreamEntity
+ com.mojang.realmsclient.client.Ping
- com.mojang.realmsclient.client.Ping$Region
+ com.mojang.realmsclient.client.RealmsClient
- com.mojang.realmsclient.client.RealmsClient$CompatibleVersionResponse
+ com.mojang.realmsclient.client.RealmsClient$Environment
- com.mojang.realmsclient.client.RealmsClientConfig
+ com.mojang.realmsclient.client.RealmsError
- com.mojang.realmsclient.client.Request
+ com.mojang.realmsclient.client.Request$Delete
- com.mojang.realmsclient.client.Request$Get
+ com.mojang.realmsclient.client.Request$Post
- com.mojang.realmsclient.client.Request$Put
+ com.mojang.realmsclient.client.UploadStatus
- com.mojang.realmsclient.dto.Backup
+ com.mojang.realmsclient.dto.BackupList
- com.mojang.realmsclient.dto.Ops
+ com.mojang.realmsclient.dto.PendingInvite
- com.mojang.realmsclient.dto.PendingInvitesList
+ com.mojang.realmsclient.dto.PingResult
- com.mojang.realmsclient.dto.PlayerInfo
+ com.mojang.realmsclient.dto.RealmsDescriptionDto
- com.mojang.realmsclient.dto.RealmsNews
+ com.mojang.realmsclient.dto.RealmsServer
- com.mojang.realmsclient.dto.RealmsServer$McoServerComparator
+ com.mojang.realmsclient.dto.RealmsServer$State
- com.mojang.realmsclient.dto.RealmsServer$WorldType
+ com.mojang.realmsclient.dto.RealmsServerAddress
- com.mojang.realmsclient.dto.RealmsServerList
+ com.mojang.realmsclient.dto.RealmsServerPing
- com.mojang.realmsclient.dto.RealmsServerPlayerList
+ com.mojang.realmsclient.dto.RealmsServerPlayerLists
- com.mojang.realmsclient.dto.RealmsWorldOptions
+ com.mojang.realmsclient.dto.RealmsWorldResetDto
- com.mojang.realmsclient.dto.RegionPingResult
+ com.mojang.realmsclient.dto.ServerActivity
- com.mojang.realmsclient.dto.ServerActivityList
+ com.mojang.realmsclient.dto.Subscription
- com.mojang.realmsclient.dto.Subscription$SubscriptionType
+ com.mojang.realmsclient.dto.UploadInfo
- com.mojang.realmsclient.dto.ValueObject
+ com.mojang.realmsclient.dto.WorldDownload
- com.mojang.realmsclient.dto.WorldTemplate
+ com.mojang.realmsclient.dto.WorldTemplate$WorldTemplateType
- com.mojang.realmsclient.dto.WorldTemplatePaginatedList
+ com.mojang.realmsclient.exception.RealmsDefaultUncaughtExceptionHandler
- com.mojang.realmsclient.exception.RealmsHttpException
+ com.mojang.realmsclient.exception.RealmsServiceException
- com.mojang.realmsclient.exception.RetryCallException
+ com.mojang.realmsclient.gui.ChatFormatting
- com.mojang.realmsclient.gui.LongRunningTask
+ com.mojang.realmsclient.gui.RealmsConstants
- com.mojang.realmsclient.gui.RealmsDataFetcher
+ com.mojang.realmsclient.gui.RealmsDataFetcher$1
- com.mojang.realmsclient.gui.RealmsDataFetcher$LiveStatsTask
+ com.mojang.realmsclient.gui.RealmsDataFetcher$PendingInviteUpdateTask
- com.mojang.realmsclient.gui.RealmsDataFetcher$ServerListUpdateTask
+ com.mojang.realmsclient.gui.RealmsDataFetcher$Task
- com.mojang.realmsclient.gui.RealmsDataFetcher$TrialAvailabilityTask
+ com.mojang.realmsclient.gui.RealmsDataFetcher$UnreadNewsTask
- com.mojang.realmsclient.gui.RealmsWorldSlotButton
+ com.mojang.realmsclient.gui.RealmsWorldSlotButton$Action
- com.mojang.realmsclient.gui.RealmsWorldSlotButton$Listener
+ com.mojang.realmsclient.gui.RealmsWorldSlotButton$State
- com.mojang.realmsclient.gui.RowButton
+ com.mojang.realmsclient.gui.screens.RealmsBackupInfoScreen
- com.mojang.realmsclient.gui.screens.RealmsBackupInfoScreen$1
+ com.mojang.realmsclient.gui.screens.RealmsBackupInfoScreen$BackupInfoList
- com.mojang.realmsclient.gui.screens.RealmsBackupScreen
+ com.mojang.realmsclient.gui.screens.RealmsBackupScreen$1
- com.mojang.realmsclient.gui.screens.RealmsBackupScreen$2
+ com.mojang.realmsclient.gui.screens.RealmsBackupScreen$3
- com.mojang.realmsclient.gui.screens.RealmsBackupScreen$4
+ com.mojang.realmsclient.gui.screens.RealmsBackupScreen$5
- com.mojang.realmsclient.gui.screens.RealmsBackupScreen$BackupObjectSelectionList
+ com.mojang.realmsclient.gui.screens.RealmsBackupScreen$BackupObjectSelectionListEntry
- com.mojang.realmsclient.gui.screens.RealmsBrokenWorldScreen
+ com.mojang.realmsclient.gui.screens.RealmsBrokenWorldScreen$1
- com.mojang.realmsclient.gui.screens.RealmsBrokenWorldScreen$2
+ com.mojang.realmsclient.gui.screens.RealmsBrokenWorldScreen$DownloadButton
- com.mojang.realmsclient.gui.screens.RealmsBrokenWorldScreen$PlayButton
+ com.mojang.realmsclient.gui.screens.RealmsClientOutdatedScreen
- com.mojang.realmsclient.gui.screens.RealmsClientOutdatedScreen$1
+ com.mojang.realmsclient.gui.screens.RealmsConfigureWorldScreen
- com.mojang.realmsclient.gui.screens.RealmsConfigureWorldScreen$1
+ com.mojang.realmsclient.gui.screens.RealmsConfigureWorldScreen$2
- com.mojang.realmsclient.gui.screens.RealmsConfigureWorldScreen$3
+ com.mojang.realmsclient.gui.screens.RealmsConfigureWorldScreen$4
- com.mojang.realmsclient.gui.screens.RealmsConfigureWorldScreen$5
+ com.mojang.realmsclient.gui.screens.RealmsConfigureWorldScreen$6
- com.mojang.realmsclient.gui.screens.RealmsConfigureWorldScreen$7
+ com.mojang.realmsclient.gui.screens.RealmsConfigureWorldScreen$8
- com.mojang.realmsclient.gui.screens.RealmsConfigureWorldScreen$9
+ com.mojang.realmsclient.gui.screens.RealmsConfirmScreen
- com.mojang.realmsclient.gui.screens.RealmsConfirmScreen$1
+ com.mojang.realmsclient.gui.screens.RealmsConfirmScreen$2
- com.mojang.realmsclient.gui.screens.RealmsCreateRealmScreen
+ com.mojang.realmsclient.gui.screens.RealmsCreateRealmScreen$1
- com.mojang.realmsclient.gui.screens.RealmsCreateRealmScreen$2
+ com.mojang.realmsclient.gui.screens.RealmsCreateTrialScreen
- com.mojang.realmsclient.gui.screens.RealmsCreateTrialScreen$1
+ com.mojang.realmsclient.gui.screens.RealmsCreateTrialScreen$2
- com.mojang.realmsclient.gui.screens.RealmsDownloadLatestWorldScreen
+ com.mojang.realmsclient.gui.screens.RealmsDownloadLatestWorldScreen$1
- com.mojang.realmsclient.gui.screens.RealmsDownloadLatestWorldScreen$DownloadStatus
+ com.mojang.realmsclient.gui.screens.RealmsGenericErrorScreen
- com.mojang.realmsclient.gui.screens.RealmsGenericErrorScreen$1
+ com.mojang.realmsclient.gui.screens.RealmsInviteScreen
- com.mojang.realmsclient.gui.screens.RealmsInviteScreen$1
+ com.mojang.realmsclient.gui.screens.RealmsInviteScreen$2
- com.mojang.realmsclient.gui.screens.RealmsLongConfirmationScreen
+ com.mojang.realmsclient.gui.screens.RealmsLongConfirmationScreen$1
- com.mojang.realmsclient.gui.screens.RealmsLongConfirmationScreen$2
+ com.mojang.realmsclient.gui.screens.RealmsLongConfirmationScreen$3
- com.mojang.realmsclient.gui.screens.RealmsLongConfirmationScreen$Type
+ com.mojang.realmsclient.gui.screens.RealmsLongRunningMcoTaskScreen
- com.mojang.realmsclient.gui.screens.RealmsLongRunningMcoTaskScreen$1
+ com.mojang.realmsclient.gui.screens.RealmsLongRunningMcoTaskScreen$2
- com.mojang.realmsclient.gui.screens.RealmsNotificationsScreen
+ com.mojang.realmsclient.gui.screens.RealmsNotificationsScreen$1
- com.mojang.realmsclient.gui.screens.RealmsParentalConsentScreen
+ com.mojang.realmsclient.gui.screens.RealmsParentalConsentScreen$1
- com.mojang.realmsclient.gui.screens.RealmsParentalConsentScreen$2
+ com.mojang.realmsclient.gui.screens.RealmsParentalConsentScreen$3
- com.mojang.realmsclient.gui.screens.RealmsPendingInvitesScreen
+ com.mojang.realmsclient.gui.screens.RealmsPendingInvitesScreen$1
- com.mojang.realmsclient.gui.screens.RealmsPendingInvitesScreen$2
+ com.mojang.realmsclient.gui.screens.RealmsPendingInvitesScreen$3
- com.mojang.realmsclient.gui.screens.RealmsPendingInvitesScreen$4
+ com.mojang.realmsclient.gui.screens.RealmsPendingInvitesScreen$5
- com.mojang.realmsclient.gui.screens.RealmsPendingInvitesScreen$6
+ com.mojang.realmsclient.gui.screens.RealmsPendingInvitesScreen$PendingInvitationSelectionList
- com.mojang.realmsclient.gui.screens.RealmsPendingInvitesScreen$PendingInvitationSelectionListEntry
+ com.mojang.realmsclient.gui.screens.RealmsPendingInvitesScreen$PendingInvitationSelectionListEntry$AcceptRowButton
- com.mojang.realmsclient.gui.screens.RealmsPendingInvitesScreen$PendingInvitationSelectionListEntry$RejectRowButton
+ com.mojang.realmsclient.gui.screens.RealmsPlayerScreen
- com.mojang.realmsclient.gui.screens.RealmsPlayerScreen$1
+ com.mojang.realmsclient.gui.screens.RealmsPlayerScreen$2
- com.mojang.realmsclient.gui.screens.RealmsPlayerScreen$3
+ com.mojang.realmsclient.gui.screens.RealmsPlayerScreen$4
- com.mojang.realmsclient.gui.screens.RealmsPlayerScreen$InvitedObjectSelectionList
+ com.mojang.realmsclient.gui.screens.RealmsPlayerScreen$InvitedObjectSelectionListEntry
- com.mojang.realmsclient.gui.screens.RealmsResetNormalWorldScreen
+ com.mojang.realmsclient.gui.screens.RealmsResetNormalWorldScreen$1
- com.mojang.realmsclient.gui.screens.RealmsResetNormalWorldScreen$2
+ com.mojang.realmsclient.gui.screens.RealmsResetNormalWorldScreen$3
- com.mojang.realmsclient.gui.screens.RealmsResetNormalWorldScreen$4
+ com.mojang.realmsclient.gui.screens.RealmsResetWorldScreen
- com.mojang.realmsclient.gui.screens.RealmsResetWorldScreen$1
+ com.mojang.realmsclient.gui.screens.RealmsResetWorldScreen$2
- com.mojang.realmsclient.gui.screens.RealmsResetWorldScreen$3
+ com.mojang.realmsclient.gui.screens.RealmsResetWorldScreen$4
- com.mojang.realmsclient.gui.screens.RealmsResetWorldScreen$5
+ com.mojang.realmsclient.gui.screens.RealmsResetWorldScreen$6
- com.mojang.realmsclient.gui.screens.RealmsResetWorldScreen$7
+ com.mojang.realmsclient.gui.screens.RealmsResetWorldScreen$8
- com.mojang.realmsclient.gui.screens.RealmsResetWorldScreen$9
+ com.mojang.realmsclient.gui.screens.RealmsResetWorldScreen$FrameButton
- com.mojang.realmsclient.gui.screens.RealmsResetWorldScreen$ResetType
+ com.mojang.realmsclient.gui.screens.RealmsResetWorldScreen$ResetWorldInfo
- com.mojang.realmsclient.gui.screens.RealmsResourcePackScreen
+ com.mojang.realmsclient.gui.screens.RealmsScreenWithCallback
- com.mojang.realmsclient.gui.screens.RealmsSelectFileToUploadScreen
+ com.mojang.realmsclient.gui.screens.RealmsSelectFileToUploadScreen$1
- com.mojang.realmsclient.gui.screens.RealmsSelectFileToUploadScreen$2
+ com.mojang.realmsclient.gui.screens.RealmsSelectFileToUploadScreen$WorldListEntry
- com.mojang.realmsclient.gui.screens.RealmsSelectFileToUploadScreen$WorldSelectionList
+ com.mojang.realmsclient.gui.screens.RealmsSelectWorldTemplateScreen
- com.mojang.realmsclient.gui.screens.RealmsSelectWorldTemplateScreen$1
+ com.mojang.realmsclient.gui.screens.RealmsSelectWorldTemplateScreen$2
- com.mojang.realmsclient.gui.screens.RealmsSelectWorldTemplateScreen$3
+ com.mojang.realmsclient.gui.screens.RealmsSelectWorldTemplateScreen$4
- com.mojang.realmsclient.gui.screens.RealmsSelectWorldTemplateScreen$5
+ com.mojang.realmsclient.gui.screens.RealmsSelectWorldTemplateScreen$WorldTemplateObjectSelectionList
- com.mojang.realmsclient.gui.screens.RealmsSelectWorldTemplateScreen$WorldTemplateObjectSelectionListEntry
+ com.mojang.realmsclient.gui.screens.RealmsSettingsScreen
- com.mojang.realmsclient.gui.screens.RealmsSettingsScreen$1
+ com.mojang.realmsclient.gui.screens.RealmsSettingsScreen$2
- com.mojang.realmsclient.gui.screens.RealmsSettingsScreen$3
+ com.mojang.realmsclient.gui.screens.RealmsSlotOptionsScreen
- com.mojang.realmsclient.gui.screens.RealmsSlotOptionsScreen$1
+ com.mojang.realmsclient.gui.screens.RealmsSlotOptionsScreen$10
- com.mojang.realmsclient.gui.screens.RealmsSlotOptionsScreen$2
+ com.mojang.realmsclient.gui.screens.RealmsSlotOptionsScreen$3
- com.mojang.realmsclient.gui.screens.RealmsSlotOptionsScreen$4
+ com.mojang.realmsclient.gui.screens.RealmsSlotOptionsScreen$5
- com.mojang.realmsclient.gui.screens.RealmsSlotOptionsScreen$6
+ com.mojang.realmsclient.gui.screens.RealmsSlotOptionsScreen$7
- com.mojang.realmsclient.gui.screens.RealmsSlotOptionsScreen$8
+ com.mojang.realmsclient.gui.screens.RealmsSlotOptionsScreen$9
- com.mojang.realmsclient.gui.screens.RealmsSlotOptionsScreen$SettingsSlider
+ com.mojang.realmsclient.gui.screens.RealmsSubscriptionInfoScreen
- com.mojang.realmsclient.gui.screens.RealmsSubscriptionInfoScreen$1
+ com.mojang.realmsclient.gui.screens.RealmsSubscriptionInfoScreen$2
- com.mojang.realmsclient.gui.screens.RealmsSubscriptionInfoScreen$3
+ com.mojang.realmsclient.gui.screens.RealmsSubscriptionInfoScreen$4
- com.mojang.realmsclient.gui.screens.RealmsTermsScreen
+ com.mojang.realmsclient.gui.screens.RealmsTermsScreen$1
- com.mojang.realmsclient.gui.screens.RealmsTermsScreen$2
+ com.mojang.realmsclient.gui.screens.RealmsUploadScreen
- com.mojang.realmsclient.gui.screens.RealmsUploadScreen$1
+ com.mojang.realmsclient.gui.screens.RealmsUploadScreen$2
- com.mojang.realmsclient.gui.screens.RealmsUploadScreen$Unit
+ com.mojang.realmsclient.gui.screens.UploadResult
- com.mojang.realmsclient.gui.screens.UploadResult$Builder
+ com.mojang.realmsclient.KeyCombo
- com.mojang.realmsclient.RealmsMainScreen
+ com.mojang.realmsclient.RealmsMainScreen$1
- com.mojang.realmsclient.RealmsMainScreen$10
+ com.mojang.realmsclient.RealmsMainScreen$11
- com.mojang.realmsclient.RealmsMainScreen$12
+ com.mojang.realmsclient.RealmsMainScreen$2
- com.mojang.realmsclient.RealmsMainScreen$3
+ com.mojang.realmsclient.RealmsMainScreen$4
- com.mojang.realmsclient.RealmsMainScreen$5
+ com.mojang.realmsclient.RealmsMainScreen$6
- com.mojang.realmsclient.RealmsMainScreen$7
+ com.mojang.realmsclient.RealmsMainScreen$8
- com.mojang.realmsclient.RealmsMainScreen$9
+ com.mojang.realmsclient.RealmsMainScreen$CloseButton
- com.mojang.realmsclient.RealmsMainScreen$NewsButton
+ com.mojang.realmsclient.RealmsMainScreen$PendingInvitesButton
- com.mojang.realmsclient.RealmsMainScreen$RealmSelectionList
+ com.mojang.realmsclient.RealmsMainScreen$RealmSelectionListEntry
- com.mojang.realmsclient.RealmsMainScreen$RealmSelectionListTrialEntry
+ com.mojang.realmsclient.RealmsMainScreen$ShowPopupButton
+ com.mojang.realmsclient.util.JsonUtils
- com.mojang.realmsclient.util.RealmsPersistence
+ com.mojang.realmsclient.util.RealmsPersistence$1
- com.mojang.realmsclient.util.RealmsPersistence$RealmsPersistenceData
+ com.mojang.realmsclient.util.RealmsTasks
- com.mojang.realmsclient.util.RealmsTasks$CloseServerTask
+ com.mojang.realmsclient.util.RealmsTasks$DownloadTask
- com.mojang.realmsclient.util.RealmsTasks$OpenServerTask
+ com.mojang.realmsclient.util.RealmsTasks$RealmsConnectTask
- com.mojang.realmsclient.util.RealmsTasks$RealmsGetServerDetailsTask
+ com.mojang.realmsclient.util.RealmsTasks$ResettingWorldTask
- com.mojang.realmsclient.util.RealmsTasks$RestoreTask
+ com.mojang.realmsclient.util.RealmsTasks$SwitchMinigameTask
- com.mojang.realmsclient.util.RealmsTasks$SwitchSlotTask
+ com.mojang.realmsclient.util.RealmsTasks$TrialCreationTask
- com.mojang.realmsclient.util.RealmsTasks$WorldCreationTask
+ com.mojang.realmsclient.util.RealmsTextureManager
- com.mojang.realmsclient.util.RealmsTextureManager$1
+ com.mojang.realmsclient.util.RealmsTextureManager$RealmsTexture
- com.mojang.realmsclient.util.RealmsUtil
+ com.mojang.realmsclient.util.RealmsUtil$1
- com.mojang.realmsclient.util.SkinProcessor
+ com.mojang.realmsclient.util.TextRenderingUtils
- com.mojang.realmsclient.util.TextRenderingUtils$Line
+ com.mojang.realmsclient.util.TextRenderingUtils$LineSegment
- com.mojang.realmsclient.util.UploadTokenCache
+ net.minecraft.advancements.Advancement
- net.minecraft.advancements.Advancement$1
+ net.minecraft.advancements.Advancement$Builder
- net.minecraft.advancements.AdvancementList
+ net.minecraft.advancements.AdvancementList$Listener
- net.minecraft.advancements.AdvancementProgress
+ net.minecraft.advancements.AdvancementProgress$Serializer
- net.minecraft.advancements.AdvancementRewards
+ net.minecraft.advancements.AdvancementRewards$Builder
- net.minecraft.advancements.AdvancementRewards$Deserializer
+ net.minecraft.advancements.critereon.AbstractCriterionTriggerInstance
- net.minecraft.advancements.critereon.BlockPredicate
+ net.minecraft.advancements.critereon.BlockPredicate$Builder
- net.minecraft.advancements.critereon.BredAnimalsTrigger
+ net.minecraft.advancements.critereon.BredAnimalsTrigger$TriggerInstance
- net.minecraft.advancements.critereon.BrewedPotionTrigger
+ net.minecraft.advancements.critereon.BrewedPotionTrigger$TriggerInstance
- net.minecraft.advancements.critereon.ChangeDimensionTrigger
+ net.minecraft.advancements.critereon.ChangeDimensionTrigger$TriggerInstance
- net.minecraft.advancements.critereon.ChanneledLightningTrigger
+ net.minecraft.advancements.critereon.ChanneledLightningTrigger$TriggerInstance
- net.minecraft.advancements.critereon.ConstructBeaconTrigger
+ net.minecraft.advancements.critereon.ConstructBeaconTrigger$TriggerInstance
- net.minecraft.advancements.critereon.ConsumeItemTrigger
+ net.minecraft.advancements.critereon.ConsumeItemTrigger$TriggerInstance
- net.minecraft.advancements.critereon.CuredZombieVillagerTrigger
+ net.minecraft.advancements.critereon.CuredZombieVillagerTrigger$TriggerInstance
- net.minecraft.advancements.critereon.DamagePredicate
+ net.minecraft.advancements.critereon.DamagePredicate$Builder
- net.minecraft.advancements.critereon.DamageSourcePredicate
+ net.minecraft.advancements.critereon.DamageSourcePredicate$Builder
- net.minecraft.advancements.critereon.DistancePredicate
+ net.minecraft.advancements.critereon.EffectsChangedTrigger
- net.minecraft.advancements.critereon.EffectsChangedTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.EnchantedItemTrigger
- net.minecraft.advancements.critereon.EnchantedItemTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.EnchantmentPredicate
- net.minecraft.advancements.critereon.EnterBlockTrigger
+ net.minecraft.advancements.critereon.EnterBlockTrigger$TriggerInstance
- net.minecraft.advancements.critereon.EntityEquipmentPredicate
+ net.minecraft.advancements.critereon.EntityEquipmentPredicate$Builder
- net.minecraft.advancements.critereon.EntityFlagsPredicate
+ net.minecraft.advancements.critereon.EntityFlagsPredicate$Builder
- net.minecraft.advancements.critereon.EntityHurtPlayerTrigger
+ net.minecraft.advancements.critereon.EntityHurtPlayerTrigger$TriggerInstance
- net.minecraft.advancements.critereon.EntityPredicate
+ net.minecraft.advancements.critereon.EntityPredicate$1
- net.minecraft.advancements.critereon.EntityPredicate$Builder
+ net.minecraft.advancements.critereon.EntityTypePredicate
- net.minecraft.advancements.critereon.EntityTypePredicate$1
+ net.minecraft.advancements.critereon.EntityTypePredicate$TagPredicate
- net.minecraft.advancements.critereon.EntityTypePredicate$TypePredicate
+ net.minecraft.advancements.critereon.FilledBucketTrigger
- net.minecraft.advancements.critereon.FilledBucketTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.FishingRodHookedTrigger
- net.minecraft.advancements.critereon.FishingRodHookedTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.FluidPredicate
- net.minecraft.advancements.critereon.FluidPredicate$Builder
+ net.minecraft.advancements.critereon.ImpossibleTrigger
- net.minecraft.advancements.critereon.ImpossibleTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.InventoryChangeTrigger
- net.minecraft.advancements.critereon.InventoryChangeTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.ItemDurabilityTrigger
- net.minecraft.advancements.critereon.ItemDurabilityTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.ItemPredicate
- net.minecraft.advancements.critereon.ItemPredicate$Builder
+ net.minecraft.advancements.critereon.KilledByCrossbowTrigger
- net.minecraft.advancements.critereon.KilledByCrossbowTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.KilledTrigger
- net.minecraft.advancements.critereon.KilledTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.LevitationTrigger
- net.minecraft.advancements.critereon.LevitationTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.LightPredicate
- net.minecraft.advancements.critereon.LightPredicate$1
+ net.minecraft.advancements.critereon.LightPredicate$Builder
- net.minecraft.advancements.critereon.LocationPredicate
+ net.minecraft.advancements.critereon.LocationPredicate$Builder
- net.minecraft.advancements.critereon.LocationTrigger
+ net.minecraft.advancements.critereon.LocationTrigger$TriggerInstance
- net.minecraft.advancements.critereon.MinMaxBounds
+ net.minecraft.advancements.critereon.MinMaxBounds$BoundsFactory
- net.minecraft.advancements.critereon.MinMaxBounds$BoundsFromReaderFactory
+ net.minecraft.advancements.critereon.MinMaxBounds$Floats
- net.minecraft.advancements.critereon.MinMaxBounds$Ints
+ net.minecraft.advancements.critereon.MobEffectsPredicate
- net.minecraft.advancements.critereon.MobEffectsPredicate$MobEffectInstancePredicate
+ net.minecraft.advancements.critereon.NbtPredicate
- net.minecraft.advancements.critereon.NetherTravelTrigger
+ net.minecraft.advancements.critereon.NetherTravelTrigger$TriggerInstance
- net.minecraft.advancements.critereon.package-info
- net.minecraft.advancements.critereon.PlacedBlockTrigger
+ net.minecraft.advancements.critereon.PlacedBlockTrigger$TriggerInstance
- net.minecraft.advancements.critereon.PlayerHurtEntityTrigger
+ net.minecraft.advancements.critereon.PlayerHurtEntityTrigger$TriggerInstance
- net.minecraft.advancements.critereon.PlayerPredicate
+ net.minecraft.advancements.critereon.PlayerPredicate$1
- net.minecraft.advancements.critereon.PlayerPredicate$AdvancementCriterionsPredicate
+ net.minecraft.advancements.critereon.PlayerPredicate$AdvancementDonePredicate
- net.minecraft.advancements.critereon.PlayerPredicate$AdvancementPredicate
+ net.minecraft.advancements.critereon.PlayerPredicate$Builder
- net.minecraft.advancements.critereon.RecipeUnlockedTrigger
+ net.minecraft.advancements.critereon.RecipeUnlockedTrigger$TriggerInstance
- net.minecraft.advancements.critereon.ShotCrossbowTrigger
+ net.minecraft.advancements.critereon.ShotCrossbowTrigger$TriggerInstance
- net.minecraft.advancements.critereon.SimpleCriterionTrigger
+ net.minecraft.advancements.critereon.StatePropertiesPredicate
- net.minecraft.advancements.critereon.StatePropertiesPredicate$1
+ net.minecraft.advancements.critereon.StatePropertiesPredicate$Builder
- net.minecraft.advancements.critereon.StatePropertiesPredicate$ExactPropertyMatcher
+ net.minecraft.advancements.critereon.StatePropertiesPredicate$PropertyMatcher
- net.minecraft.advancements.critereon.StatePropertiesPredicate$RangedPropertyMatcher
+ net.minecraft.advancements.critereon.SummonedEntityTrigger
- net.minecraft.advancements.critereon.SummonedEntityTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.TameAnimalTrigger
- net.minecraft.advancements.critereon.TameAnimalTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.TickTrigger
- net.minecraft.advancements.critereon.TickTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.TradeTrigger
- net.minecraft.advancements.critereon.TradeTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.UsedEnderEyeTrigger
- net.minecraft.advancements.critereon.UsedEnderEyeTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.UsedTotemTrigger
- net.minecraft.advancements.critereon.UsedTotemTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.WrappedMinMaxBounds
+ net.minecraft.advancements.CriteriaTriggers
- net.minecraft.advancements.Criterion
+ net.minecraft.advancements.CriterionProgress
- net.minecraft.advancements.CriterionTrigger
+ net.minecraft.advancements.CriterionTrigger$Listener
- net.minecraft.advancements.CriterionTriggerInstance
+ net.minecraft.advancements.DisplayInfo
- net.minecraft.advancements.FrameType
+ net.minecraft.advancements.package-info
+ net.minecraft.advancements.RequirementsStrategy
- net.minecraft.advancements.TreeNodePosition
+ net.minecraft.ChatFormatting
- net.minecraft.client.AmbientOcclusionStatus
+ net.minecraft.client.AttackIndicatorStatus
- net.minecraft.client.BooleanOption
+ net.minecraft.client.Camera
- net.minecraft.client.ClientBrandRetriever
+ net.minecraft.client.ClientRecipeBook
- net.minecraft.client.CloudStatus
+ net.minecraft.client.CycleOption
- net.minecraft.client.DebugQueryHandler
+ net.minecraft.client.FullscreenResolutionProgressOption
- net.minecraft.client.Game
+ net.minecraft.client.Game$Metrics
+ net.minecraft.client.gui.screens.achievement.package-info
+ net.minecraft.client.gui.screens.achievement.StatsScreen
- net.minecraft.client.gui.screens.achievement.StatsScreen$1
+ net.minecraft.client.gui.screens.achievement.StatsScreen$GeneralStatisticsList
- net.minecraft.client.gui.screens.achievement.StatsScreen$GeneralStatisticsList$Entry
+ net.minecraft.client.gui.screens.achievement.StatsScreen$ItemStatisticsList
- net.minecraft.client.gui.screens.achievement.StatsScreen$ItemStatisticsList$ItemComparator
+ net.minecraft.client.gui.screens.achievement.StatsScreen$ItemStatisticsList$ItemRow
- net.minecraft.client.gui.screens.achievement.StatsScreen$MobsStatisticsList
+ net.minecraft.client.gui.screens.achievement.StatsScreen$MobsStatisticsList$MobRow
- net.minecraft.client.gui.screens.achievement.StatsUpdateListener
+ net.minecraft.client.gui.screens.advancements.AdvancementsScreen
- net.minecraft.client.gui.screens.advancements.AdvancementTab
+ net.minecraft.client.gui.screens.advancements.AdvancementTabType
- net.minecraft.client.gui.screens.advancements.AdvancementTabType$1
+ net.minecraft.client.gui.screens.advancements.AdvancementWidget
- net.minecraft.client.gui.screens.advancements.AdvancementWidgetType
- net.minecraft.client.gui.screens.advancements.package-info
+ net.minecraft.client.gui.screens.controls.ControlList
- net.minecraft.client.gui.screens.controls.ControlList$1
+ net.minecraft.client.gui.screens.controls.ControlList$CategoryEntry
- net.minecraft.client.gui.screens.controls.ControlList$Entry
+ net.minecraft.client.gui.screens.controls.ControlList$KeyEntry
- net.minecraft.client.gui.screens.controls.ControlList$KeyEntry$1
+ net.minecraft.client.gui.screens.controls.ControlList$KeyEntry$2
- net.minecraft.client.gui.screens.controls.ControlsScreen
+ net.minecraft.client.gui.screens.controls.package-info
- net.minecraft.client.gui.screens.inventory.AbstractCommandBlockEditScreen
+ net.minecraft.client.gui.screens.inventory.AbstractCommandBlockEditScreen$1
- net.minecraft.client.gui.screens.inventory.AbstractCommandBlockEditScreen$SuggestionsList
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
+ net.minecraft.client.gui.screens.inventory.JigsawBlockEditScreen
- net.minecraft.client.gui.screens.inventory.LecternScreen
+ net.minecraft.client.gui.screens.inventory.LecternScreen$1
- net.minecraft.client.gui.screens.inventory.LoomScreen
+ net.minecraft.client.gui.screens.inventory.MenuAccess
- net.minecraft.client.gui.screens.inventory.MerchantScreen
+ net.minecraft.client.gui.screens.inventory.MerchantScreen$TradeOfferButton
- net.minecraft.client.gui.screens.inventory.MinecartCommandBlockEditScreen
+ net.minecraft.client.gui.screens.inventory.package-info
+ net.minecraft.client.gui.screens.inventory.PageButton
- net.minecraft.client.gui.screens.inventory.ShulkerBoxScreen
+ net.minecraft.client.gui.screens.inventory.SignEditScreen
- net.minecraft.client.gui.screens.inventory.SmokerScreen
+ net.minecraft.client.gui.screens.inventory.StonecutterScreen
- net.minecraft.client.gui.screens.inventory.StructureBlockEditScreen
+ net.minecraft.client.gui.screens.inventory.StructureBlockEditScreen$1
- net.minecraft.client.gui.screens.inventory.StructureBlockEditScreen$2
- net.minecraft.client.gui.screens.mco.package-info
+ net.minecraft.client.gui.screens.multiplayer.JoinMultiplayerScreen
+ net.minecraft.client.gui.screens.multiplayer.package-info
- net.minecraft.client.gui.screens.multiplayer.ServerSelectionList
+ net.minecraft.client.gui.screens.multiplayer.ServerSelectionList$Entry
- net.minecraft.client.gui.screens.multiplayer.ServerSelectionList$LANHeader
+ net.minecraft.client.gui.screens.multiplayer.ServerSelectionList$NetworkServerEntry
- net.minecraft.client.gui.screens.multiplayer.ServerSelectionList$OnlineServerEntry
- net.minecraft.client.gui.screens.OptionsSubScreen
+ net.minecraft.client.gui.screens.OutOfMemoryScreen
- net.minecraft.client.gui.screens.Overlay
- net.minecraft.client.gui.screens.package-info
+ net.minecraft.client.gui.screens.PauseScreen
- net.minecraft.client.gui.screens.PresetFlatWorldScreen
+ net.minecraft.client.gui.screens.PresetFlatWorldScreen$PresetInfo
- net.minecraft.client.gui.screens.PresetFlatWorldScreen$PresetsList
+ net.minecraft.client.gui.screens.PresetFlatWorldScreen$PresetsList$Entry
- net.minecraft.client.gui.screens.ProgressScreen
+ net.minecraft.client.gui.screens.ReceivingLevelScreen
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
- net.minecraft.client.gui.screens.Screen
+ net.minecraft.client.gui.screens.ShareToLanScreen
- net.minecraft.client.gui.screens.SkinCustomizationScreen
+ net.minecraft.client.gui.screens.SoundOptionsScreen
+ net.minecraft.client.gui.screens.stream.package-info
- net.minecraft.client.gui.screens.TitleScreen
+ net.minecraft.client.gui.screens.VideoSettingsScreen
- net.minecraft.client.gui.screens.WinScreen
- net.minecraft.client.gui.screens.worldselection.CreateWorldScreen
+ net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$1
- net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$2
- net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$4
- net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$6
- net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$SelectedGameMode
+ net.minecraft.client.gui.screens.worldselection.EditWorldScreen
- net.minecraft.client.gui.screens.worldselection.OptimizeWorldScreen
- net.minecraft.client.gui.screens.worldselection.package-info
+ net.minecraft.client.gui.screens.worldselection.SelectWorldScreen
- net.minecraft.client.gui.screens.worldselection.WorldSelectionList
+ net.minecraft.client.gui.screens.worldselection.WorldSelectionList$WorldListEntry
- net.minecraft.client.gui.spectator.categories.package-info
- net.minecraft.client.gui.spectator.categories.SpectatorPage
+ net.minecraft.client.gui.spectator.categories.TeleportToPlayerMenuCategory
- net.minecraft.client.gui.spectator.categories.TeleportToTeamMenuCategory
+ net.minecraft.client.gui.spectator.categories.TeleportToTeamMenuCategory$TeamSelectionItem
+ net.minecraft.client.gui.spectator.package-info
+ net.minecraft.client.gui.spectator.PlayerMenuItem
- net.minecraft.client.gui.spectator.RootSpectatorMenuCategory
+ net.minecraft.client.gui.spectator.SpectatorMenu
- net.minecraft.client.gui.spectator.SpectatorMenu$1
+ net.minecraft.client.gui.spectator.SpectatorMenu$CloseSpectatorItem
- net.minecraft.client.gui.spectator.SpectatorMenu$ScrollMenuItem
+ net.minecraft.client.gui.spectator.SpectatorMenuCategory
- net.minecraft.client.gui.spectator.SpectatorMenuItem
+ net.minecraft.client.gui.spectator.SpectatorMenuListener
- net.minecraft.client.GuiMessage
+ net.minecraft.client.HotbarManager
- net.minecraft.client.KeyboardHandler
+ net.minecraft.client.KeyboardHandler$1
- net.minecraft.client.KeyMapping
+ net.minecraft.client.KeyMapping$1
- net.minecraft.client.LogaritmicProgressOption
- net.minecraft.client.main.GameConfig
+ net.minecraft.client.main.GameConfig$FolderData
- net.minecraft.client.main.GameConfig$GameData
+ net.minecraft.client.main.GameConfig$ServerData
- net.minecraft.client.main.GameConfig$UserData
+ net.minecraft.client.main.Main
- net.minecraft.client.main.Main$1
+ net.minecraft.client.main.Main$2
- net.minecraft.client.main.Main$3
+ net.minecraft.client.main.package-info
- net.minecraft.client.map.BiomeMapToolChunkCache
+ net.minecraft.client.map.Map
- net.minecraft.client.map.Map$1
+ net.minecraft.client.map.Map$2
- net.minecraft.client.map.Map$3
+ net.minecraft.client.map.Map$4
- net.minecraft.client.map.package-info
+ net.minecraft.client.Minecraft
- net.minecraft.client.Minecraft$1
+ net.minecraft.client.Minecraft$2
+ net.minecraft.client.model.AbstractZombieModel
- net.minecraft.client.model.AgeableListModel
+ net.minecraft.client.model.ArmedModel
- net.minecraft.client.model.ArmorStandArmorModel
+ net.minecraft.client.model.ArmorStandModel
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
- net.minecraft.client.model.ColorableListModel
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
- net.minecraft.client.model.geom.ModelPart
+ net.minecraft.client.model.geom.ModelPart$Cube
- net.minecraft.client.model.geom.ModelPart$Polygon
+ net.minecraft.client.model.geom.ModelPart$Vertex
- net.minecraft.client.model.geom.package-info
+ net.minecraft.client.model.GhastModel
- net.minecraft.client.model.GiantZombieModel
+ net.minecraft.client.model.GuardianModel
- net.minecraft.client.model.HeadedModel
+ net.minecraft.client.model.HorseModel
- net.minecraft.client.model.HumanoidHeadModel
+ net.minecraft.client.model.HumanoidModel
- net.minecraft.client.model.HumanoidModel$1
+ net.minecraft.client.model.HumanoidModel$ArmPose
- net.minecraft.client.model.IllagerModel
+ net.minecraft.client.model.IronGolemModel
- net.minecraft.client.model.LavaSlimeModel
+ net.minecraft.client.model.LeashKnotModel
- net.minecraft.client.model.ListModel
+ net.minecraft.client.model.LlamaModel
- net.minecraft.client.model.LlamaSpitModel
+ net.minecraft.client.model.MinecartModel
- net.minecraft.client.model.Model
+ net.minecraft.client.model.ModelUtils
- net.minecraft.client.model.OcelotModel
+ net.minecraft.client.model.package-info
+ net.minecraft.client.model.PandaModel
- net.minecraft.client.model.ParrotModel
+ net.minecraft.client.model.ParrotModel$1
- net.minecraft.client.model.ParrotModel$State
+ net.minecraft.client.model.PhantomModel
- net.minecraft.client.model.PigModel
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
- net.minecraft.client.model.SlimeModel
+ net.minecraft.client.model.SnowGolemModel
- net.minecraft.client.model.SpiderModel
+ net.minecraft.client.model.SquidModel
- net.minecraft.client.model.TridentModel
+ net.minecraft.client.model.TropicalFishModelA
- net.minecraft.client.model.TropicalFishModelB
+ net.minecraft.client.model.TurtleModel
- net.minecraft.client.model.VexModel
+ net.minecraft.client.model.VillagerHeadModel
- net.minecraft.client.model.VillagerModel
+ net.minecraft.client.model.WitchModel
- net.minecraft.client.model.WitherBossModel
+ net.minecraft.client.model.WolfModel
- net.minecraft.client.model.ZombieModel
+ net.minecraft.client.model.ZombieVillagerModel
- net.minecraft.client.MouseHandler
- net.minecraft.client.multiplayer.ClientAdvancements
+ net.minecraft.client.multiplayer.ClientAdvancements$Listener
- net.minecraft.client.multiplayer.ClientChunkCache
+ net.minecraft.client.multiplayer.ClientChunkCache$1
- net.minecraft.client.multiplayer.ClientChunkCache$Storage
+ net.minecraft.client.multiplayer.ClientHandshakePacketListenerImpl
- net.minecraft.client.multiplayer.ClientPacketListener
+ net.minecraft.client.multiplayer.ClientPacketListener$1
- net.minecraft.client.multiplayer.ClientSuggestionProvider
+ net.minecraft.client.multiplayer.MultiPlayerGameMode
- net.minecraft.client.multiplayer.MultiPlayerLevel
- net.minecraft.client.multiplayer.package-info
+ net.minecraft.client.multiplayer.PlayerInfo
- net.minecraft.client.multiplayer.ServerAddress
+ net.minecraft.client.multiplayer.ServerData
- net.minecraft.client.multiplayer.ServerData$ServerPackStatus
+ net.minecraft.client.multiplayer.ServerList
- net.minecraft.client.multiplayer.ServerStatusPinger
+ net.minecraft.client.multiplayer.ServerStatusPinger$1
- net.minecraft.client.multiplayer.ServerStatusPinger$2
+ net.minecraft.client.multiplayer.ServerStatusPinger$2$1
+ net.minecraft.client.NarratorStatus
- net.minecraft.client.Option
+ net.minecraft.client.Options
- net.minecraft.client.Options$1
+ net.minecraft.client.Options$2
+ net.minecraft.client.package-info
- net.minecraft.client.particle.AttackSweepParticle
+ net.minecraft.client.particle.AttackSweepParticle$1
- net.minecraft.client.particle.AttackSweepParticle$Provider
+ net.minecraft.client.particle.BarrierParticle
- net.minecraft.client.particle.BarrierParticle$1
+ net.minecraft.client.particle.BarrierParticle$Provider
- net.minecraft.client.particle.BreakingItemParticle
+ net.minecraft.client.particle.BreakingItemParticle$1
- net.minecraft.client.particle.BreakingItemParticle$Provider
+ net.minecraft.client.particle.BreakingItemParticle$SlimeProvider
- net.minecraft.client.particle.BreakingItemParticle$SnowballProvider
+ net.minecraft.client.particle.BubbleColumnUpParticle
- net.minecraft.client.particle.BubbleColumnUpParticle$1
+ net.minecraft.client.particle.BubbleColumnUpParticle$Provider
- net.minecraft.client.particle.BubbleParticle
+ net.minecraft.client.particle.BubbleParticle$1
- net.minecraft.client.particle.BubbleParticle$Provider
+ net.minecraft.client.particle.BubblePopParticle
- net.minecraft.client.particle.BubblePopParticle$1
+ net.minecraft.client.particle.BubblePopParticle$Provider
- net.minecraft.client.particle.CampfireSmokeParticle
+ net.minecraft.client.particle.CampfireSmokeParticle$1
- net.minecraft.client.particle.CampfireSmokeParticle$CosyProvider
+ net.minecraft.client.particle.CampfireSmokeParticle$SignalProvider
- net.minecraft.client.particle.CritParticle
+ net.minecraft.client.particle.CritParticle$1
- net.minecraft.client.particle.CritParticle$DamageIndicatorProvider
+ net.minecraft.client.particle.CritParticle$MagicProvider
- net.minecraft.client.particle.CritParticle$Provider
+ net.minecraft.client.particle.DragonBreathParticle
- net.minecraft.client.particle.DragonBreathParticle$1
+ net.minecraft.client.particle.DragonBreathParticle$Provider
- net.minecraft.client.particle.DripParticle
+ net.minecraft.client.particle.DripParticle$1
- net.minecraft.client.particle.DripParticle$CoolingDripHangParticle
+ net.minecraft.client.particle.DripParticle$DripHangParticle
- net.minecraft.client.particle.DripParticle$DripLandParticle
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
+ net.minecraft.client.particle.DripParticle$WaterFallProvider
- net.minecraft.client.particle.DripParticle$WaterHangProvider
+ net.minecraft.client.particle.DustParticle
- net.minecraft.client.particle.DustParticle$1
+ net.minecraft.client.particle.DustParticle$Provider
- net.minecraft.client.particle.EnchantmentTableParticle
+ net.minecraft.client.particle.EnchantmentTableParticle$1
- net.minecraft.client.particle.EnchantmentTableParticle$NautilusProvider
+ net.minecraft.client.particle.EnchantmentTableParticle$Provider
- net.minecraft.client.particle.EndRodParticle
+ net.minecraft.client.particle.EndRodParticle$1
- net.minecraft.client.particle.EndRodParticle$Provider
+ net.minecraft.client.particle.ExplodeParticle
- net.minecraft.client.particle.ExplodeParticle$Provider
+ net.minecraft.client.particle.FallingDustParticle
- net.minecraft.client.particle.FallingDustParticle$1
+ net.minecraft.client.particle.FallingDustParticle$Provider
- net.minecraft.client.particle.FireworkParticles
+ net.minecraft.client.particle.FireworkParticles$1
- net.minecraft.client.particle.FireworkParticles$FlashProvider
+ net.minecraft.client.particle.FireworkParticles$OverlayParticle
- net.minecraft.client.particle.FireworkParticles$SparkParticle
+ net.minecraft.client.particle.FireworkParticles$SparkProvider
- net.minecraft.client.particle.FireworkParticles$Starter
+ net.minecraft.client.particle.FlameParticle
- net.minecraft.client.particle.FlameParticle$1
+ net.minecraft.client.particle.FlameParticle$Provider
- net.minecraft.client.particle.HeartParticle
+ net.minecraft.client.particle.HeartParticle$1
- net.minecraft.client.particle.HeartParticle$AngryVillagerProvider
+ net.minecraft.client.particle.HeartParticle$Provider
- net.minecraft.client.particle.HugeExplosionParticle
+ net.minecraft.client.particle.HugeExplosionParticle$1
- net.minecraft.client.particle.HugeExplosionParticle$Provider
+ net.minecraft.client.particle.HugeExplosionSeedParticle
- net.minecraft.client.particle.HugeExplosionSeedParticle$1
+ net.minecraft.client.particle.HugeExplosionSeedParticle$Provider
- net.minecraft.client.particle.ItemPickupParticle
+ net.minecraft.client.particle.LargeSmokeParticle
- net.minecraft.client.particle.LargeSmokeParticle$Provider
+ net.minecraft.client.particle.LavaParticle
- net.minecraft.client.particle.LavaParticle$1
+ net.minecraft.client.particle.LavaParticle$Provider
- net.minecraft.client.particle.MobAppearanceParticle
+ net.minecraft.client.particle.MobAppearanceParticle$1
- net.minecraft.client.particle.MobAppearanceParticle$Provider
+ net.minecraft.client.particle.NoRenderParticle
- net.minecraft.client.particle.NoteParticle
+ net.minecraft.client.particle.NoteParticle$1
- net.minecraft.client.particle.NoteParticle$Provider
+ net.minecraft.client.particle.package-info
+ net.minecraft.client.particle.Particle
- net.minecraft.client.particle.ParticleDescription
+ net.minecraft.client.particle.ParticleEngine
- net.minecraft.client.particle.ParticleEngine$1
+ net.minecraft.client.particle.ParticleEngine$MutableSpriteSet
- net.minecraft.client.particle.ParticleEngine$SpriteParticleRegistration
+ net.minecraft.client.particle.ParticleProvider
- net.minecraft.client.particle.ParticleRenderType
+ net.minecraft.client.particle.ParticleRenderType$1
- net.minecraft.client.particle.ParticleRenderType$2
+ net.minecraft.client.particle.ParticleRenderType$3
- net.minecraft.client.particle.ParticleRenderType$4
+ net.minecraft.client.particle.ParticleRenderType$5
- net.minecraft.client.particle.ParticleRenderType$6
+ net.minecraft.client.particle.PlayerCloudParticle
- net.minecraft.client.particle.PlayerCloudParticle$1
+ net.minecraft.client.particle.PlayerCloudParticle$Provider
- net.minecraft.client.particle.PlayerCloudParticle$SneezeProvider
+ net.minecraft.client.particle.PortalParticle
- net.minecraft.client.particle.PortalParticle$1
+ net.minecraft.client.particle.PortalParticle$Provider
- net.minecraft.client.particle.SimpleAnimatedParticle
+ net.minecraft.client.particle.SingleQuadParticle
- net.minecraft.client.particle.SmokeParticle
+ net.minecraft.client.particle.SmokeParticle$Provider
- net.minecraft.client.particle.SpellParticle
+ net.minecraft.client.particle.SpellParticle$1
- net.minecraft.client.particle.SpellParticle$AmbientMobProvider
+ net.minecraft.client.particle.SpellParticle$InstantProvider
- net.minecraft.client.particle.SpellParticle$MobProvider
+ net.minecraft.client.particle.SpellParticle$Provider
- net.minecraft.client.particle.SpellParticle$WitchProvider
+ net.minecraft.client.particle.SpitParticle
- net.minecraft.client.particle.SpitParticle$1
+ net.minecraft.client.particle.SpitParticle$Provider
- net.minecraft.client.particle.SplashParticle
+ net.minecraft.client.particle.SplashParticle$1
- net.minecraft.client.particle.SplashParticle$Provider
+ net.minecraft.client.particle.SpriteSet
- net.minecraft.client.particle.SquidInkParticle
+ net.minecraft.client.particle.SquidInkParticle$1
- net.minecraft.client.particle.SquidInkParticle$Provider
+ net.minecraft.client.particle.SuspendedParticle
- net.minecraft.client.particle.SuspendedParticle$1
+ net.minecraft.client.particle.SuspendedParticle$Provider
- net.minecraft.client.particle.SuspendedTownParticle
+ net.minecraft.client.particle.SuspendedTownParticle$1
- net.minecraft.client.particle.SuspendedTownParticle$ComposterFillProvider
+ net.minecraft.client.particle.SuspendedTownParticle$DolphinSpeedProvider
- net.minecraft.client.particle.SuspendedTownParticle$HappyVillagerProvider
+ net.minecraft.client.particle.SuspendedTownParticle$Provider
- net.minecraft.client.particle.TerrainParticle
+ net.minecraft.client.particle.TerrainParticle$Provider
- net.minecraft.client.particle.TextureSheetParticle
+ net.minecraft.client.particle.TotemParticle
- net.minecraft.client.particle.TotemParticle$1
+ net.minecraft.client.particle.TotemParticle$Provider
- net.minecraft.client.particle.TrackingEmitter
+ net.minecraft.client.particle.WakeParticle
- net.minecraft.client.particle.WakeParticle$1
+ net.minecraft.client.particle.WakeParticle$Provider
- net.minecraft.client.particle.WaterCurrentDownParticle
+ net.minecraft.client.particle.WaterCurrentDownParticle$1
- net.minecraft.client.particle.WaterCurrentDownParticle$Provider
+ net.minecraft.client.particle.WaterDropParticle
- net.minecraft.client.particle.WaterDropParticle$Provider
- net.minecraft.client.ParticleStatus
- net.minecraft.client.player.AbstractClientPlayer
+ net.minecraft.client.player.Input
- net.minecraft.client.player.inventory.Hotbar
+ net.minecraft.client.player.inventory.package-info
- net.minecraft.client.player.KeyboardInput
+ net.minecraft.client.player.LocalPlayer
- net.minecraft.client.player.LocalPlayer$1
- net.minecraft.client.player.package-info
+ net.minecraft.client.player.RemotePlayer
+ net.minecraft.client.ProgressOption
- net.minecraft.client.RecipeBookCategories
+ net.minecraft.client.renderer.BiomeColors
- net.minecraft.client.renderer.BiomeColors$ColorResolver
- net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$ChunkTaskResult
+ net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$CompiledChunk
- net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$CompiledChunk$1
+ net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$RenderChunk
- net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$RenderChunk$ChunkCompileTask
+ net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$RenderChunk$RebuildTask
- net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$RenderChunk$ResortTransparencyTask
+ net.minecraft.client.renderer.chunk.package-info
+ net.minecraft.client.renderer.chunk.RenderChunkRegion
- net.minecraft.client.renderer.chunk.VisGraph
+ net.minecraft.client.renderer.chunk.VisGraph$1
- net.minecraft.client.renderer.chunk.VisibilitySet
+ net.minecraft.client.renderer.ChunkBufferBuilderPack
- net.minecraft.client.renderer.CubeMap
- net.minecraft.client.renderer.culling.Frustum
+ net.minecraft.client.renderer.culling.package-info
- net.minecraft.client.renderer.debug.CaveDebugRenderer
+ net.minecraft.client.renderer.debug.ChunkBorderRenderer
- net.minecraft.client.renderer.debug.ChunkDebugRenderer
+ net.minecraft.client.renderer.debug.ChunkDebugRenderer$1
- net.minecraft.client.renderer.debug.ChunkDebugRenderer$ChunkData
+ net.minecraft.client.renderer.debug.CollisionBoxRenderer
- net.minecraft.client.renderer.debug.DebugRenderer
+ net.minecraft.client.renderer.debug.DebugRenderer$SimpleDebugRenderer
- net.minecraft.client.renderer.debug.GameTestDebugRenderer
+ net.minecraft.client.renderer.debug.GameTestDebugRenderer$Marker
- net.minecraft.client.renderer.debug.GoalSelectorDebugRenderer
+ net.minecraft.client.renderer.debug.GoalSelectorDebugRenderer$DebugGoal
- net.minecraft.client.renderer.debug.HeightMapRenderer
+ net.minecraft.client.renderer.debug.LightDebugRenderer
- net.minecraft.client.renderer.debug.NeighborsUpdateRenderer
- net.minecraft.client.renderer.debug.package-info
+ net.minecraft.client.renderer.debug.PathfindingRenderer
- net.minecraft.client.renderer.debug.RaidDebugRenderer
+ net.minecraft.client.renderer.debug.SolidFaceRenderer
- net.minecraft.client.renderer.debug.StructureRenderer
+ net.minecraft.client.renderer.debug.VillageDebugRenderer
- net.minecraft.client.renderer.debug.VillageDebugRenderer$BrainDump
+ net.minecraft.client.renderer.debug.VillageDebugRenderer$PoiInfo
- net.minecraft.client.renderer.debug.WaterDebugRenderer
+ net.minecraft.client.renderer.debug.WorldGenAttemptRenderer
+ net.minecraft.client.renderer.EffectInstance
+ net.minecraft.client.renderer.entity.AbstractHorseRenderer
- net.minecraft.client.renderer.entity.AbstractZombieRenderer
+ net.minecraft.client.renderer.entity.AreaEffectCloudRenderer
- net.minecraft.client.renderer.entity.ArmorStandRenderer
+ net.minecraft.client.renderer.entity.ArrowRenderer
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
- net.minecraft.client.renderer.entity.EvokerFangsRenderer
+ net.minecraft.client.renderer.entity.EvokerRenderer
- net.minecraft.client.renderer.entity.EvokerRenderer$1
+ net.minecraft.client.renderer.entity.ExperienceOrbRenderer
- net.minecraft.client.renderer.entity.FallingBlockRenderer
+ net.minecraft.client.renderer.entity.FireworkEntityRenderer
- net.minecraft.client.renderer.entity.FishingHookRenderer
+ net.minecraft.client.renderer.entity.FoxRenderer
- net.minecraft.client.renderer.entity.GhastRenderer
+ net.minecraft.client.renderer.entity.GiantMobRenderer
- net.minecraft.client.renderer.entity.GuardianRenderer
+ net.minecraft.client.renderer.entity.HorseRenderer
- net.minecraft.client.renderer.entity.HumanoidMobRenderer
+ net.minecraft.client.renderer.entity.HuskRenderer
- net.minecraft.client.renderer.entity.IllagerRenderer
+ net.minecraft.client.renderer.entity.IllusionerRenderer
- net.minecraft.client.renderer.entity.IllusionerRenderer$1
+ net.minecraft.client.renderer.entity.IronGolemRenderer
- net.minecraft.client.renderer.entity.ItemEntityRenderer
+ net.minecraft.client.renderer.entity.ItemFrameRenderer
- net.minecraft.client.renderer.entity.ItemRenderer
- net.minecraft.client.renderer.entity.layers.AbstractArmorLayer
+ net.minecraft.client.renderer.entity.layers.ArrowLayer
- net.minecraft.client.renderer.entity.layers.BeeStingerLayer
+ net.minecraft.client.renderer.entity.layers.CapeLayer
- net.minecraft.client.renderer.entity.layers.CarriedBlockLayer
+ net.minecraft.client.renderer.entity.layers.CatCollarLayer
- net.minecraft.client.renderer.entity.layers.CreeperPowerLayer
+ net.minecraft.client.renderer.entity.layers.CustomHeadLayer
- net.minecraft.client.renderer.entity.layers.Deadmau5EarsLayer
+ net.minecraft.client.renderer.entity.layers.DolphinCarryingItemLayer
- net.minecraft.client.renderer.entity.layers.DrownedOuterLayer
+ net.minecraft.client.renderer.entity.layers.ElytraLayer
- net.minecraft.client.renderer.entity.layers.EnderEyesLayer
+ net.minecraft.client.renderer.entity.layers.EyesLayer
- net.minecraft.client.renderer.entity.layers.FoxHeldItemLayer
+ net.minecraft.client.renderer.entity.layers.HorseArmorLayer
- net.minecraft.client.renderer.entity.layers.HumanoidArmorLayer
+ net.minecraft.client.renderer.entity.layers.HumanoidArmorLayer$1
- net.minecraft.client.renderer.entity.layers.IronGolemCrackinessLayer
+ net.minecraft.client.renderer.entity.LeashKnotRenderer
- net.minecraft.client.renderer.entity.LightningBoltRenderer
+ net.minecraft.client.renderer.entity.LivingEntityRenderer
- net.minecraft.client.renderer.entity.LivingEntityRenderer$1
+ net.minecraft.client.renderer.entity.LlamaRenderer
- net.minecraft.client.renderer.entity.LlamaSpitRenderer
+ net.minecraft.client.renderer.entity.MagmaCubeRenderer
- net.minecraft.client.renderer.entity.MinecartRenderer
+ net.minecraft.client.renderer.entity.MobRenderer
- net.minecraft.client.renderer.entity.MushroomCowRenderer
+ net.minecraft.client.renderer.entity.OcelotRenderer
- net.minecraft.client.renderer.entity.PaintingRenderer
+ net.minecraft.client.renderer.entity.PandaRenderer
- net.minecraft.client.renderer.entity.ParrotRenderer
+ net.minecraft.client.renderer.entity.PhantomRenderer
- net.minecraft.client.renderer.entity.PigRenderer
+ net.minecraft.client.renderer.entity.PigZombieRenderer
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
+ net.minecraft.client.renderer.entity.WitchRenderer
- net.minecraft.client.renderer.entity.WitherBossRenderer
+ net.minecraft.client.renderer.entity.WitherSkeletonRenderer
- net.minecraft.client.renderer.entity.WitherSkullRenderer
+ net.minecraft.client.renderer.entity.WolfRenderer
- net.minecraft.client.renderer.entity.ZombieRenderer
+ net.minecraft.client.renderer.entity.ZombieVillagerRenderer
- net.minecraft.client.renderer.EntityBlockRenderer
+ net.minecraft.client.renderer.FaceInfo
- net.minecraft.client.renderer.FaceInfo$1
+ net.minecraft.client.renderer.FaceInfo$Constants
- net.minecraft.client.renderer.FaceInfo$VertexInfo
+ net.minecraft.client.renderer.FogRenderer
- net.minecraft.client.renderer.FogRenderer$FogMode
+ net.minecraft.client.renderer.GameRenderer
- net.minecraft.client.renderer.ItemInHandRenderer
+ net.minecraft.client.renderer.ItemInHandRenderer$1
- net.minecraft.client.renderer.ItemModelShaper
+ net.minecraft.client.renderer.LevelRenderer
- net.minecraft.client.renderer.LevelRenderer$1
+ net.minecraft.client.renderer.LevelRenderer$RenderChunkInfo
- net.minecraft.client.renderer.LightTexture
+ net.minecraft.client.renderer.MultiBufferSource
- net.minecraft.client.renderer.MultiBufferSource$BufferSource
+ net.minecraft.client.renderer.OutlineBufferSource
- net.minecraft.client.renderer.OutlineBufferSource$1
+ net.minecraft.client.renderer.OutlineBufferSource$EntityOutlineGenerator
- net.minecraft.client.renderer.PanoramaRenderer
+ net.minecraft.client.renderer.PostChain
- net.minecraft.client.renderer.PostPass
+ net.minecraft.client.renderer.Rect2i
- net.minecraft.client.renderer.RenderBuffers
- net.minecraft.client.renderer.RenderStateShard$AlphaStateShard
- net.minecraft.client.renderer.RenderStateShard$CullStateShard
- net.minecraft.client.renderer.RenderStateShard$DiffuseLightingStateShard
- net.minecraft.client.renderer.RenderStateShard$LayeringStateShard
- net.minecraft.client.renderer.RenderStateShard$LineStateShard
- net.minecraft.client.renderer.RenderStateShard$OverlayStateShard
- net.minecraft.client.renderer.RenderStateShard$ShadeModelStateShard
- net.minecraft.client.renderer.RenderStateShard$TextureStateShard
- net.minecraft.client.renderer.RenderStateShard$TransparencyStateShard
- net.minecraft.client.renderer.RenderType$CompositeRenderType
- net.minecraft.client.renderer.RenderType$CompositeState$CompositeStateBuilder
+ net.minecraft.client.renderer.RenderType$EntityState
+ net.minecraft.client.renderer.RenderType$SwirlState
+ net.minecraft.client.Screenshot
- net.minecraft.client.Session
+ net.minecraft.client.Timer
- net.minecraft.client.ToggleKeyMapping
- net.minecraft.CrashReport
+ net.minecraft.CrashReportCategory
- net.minecraft.CrashReportCategory$Entry
+ net.minecraft.CrashReportDetail
- net.minecraft.DefaultUncaughtExceptionHandler
+ net.minecraft.DefaultUncaughtExceptionHandlerWithName
- net.minecraft.DetectedVersion
+ net.minecraft.FieldsAreNonnullByDefault
- net.minecraft.FileUtil
- net.minecraft.gametest.framework.GameTestGenerator
+ net.minecraft.gametest.framework.GameTestHelper
- net.minecraft.gametest.framework.GameTestInfo
+ net.minecraft.gametest.framework.GameTestListener
- net.minecraft.gametest.framework.GameTestRegistry
+ net.minecraft.gametest.framework.GameTestRunner
- net.minecraft.gametest.framework.GameTestRunner$1
- net.minecraft.gametest.framework.GameTestSequence$Condition
+ net.minecraft.gametest.framework.GameTestServer
- net.minecraft.gametest.framework.GameTestServer$1
+ net.minecraft.gametest.framework.GameTestTicker
- net.minecraft.gametest.framework.GameTestTimeoutException
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
+ net.minecraft.MethodsReturnNonnullByDefault
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
+ net.minecraft.network.chat.Component
- net.minecraft.network.chat.Component$1
+ net.minecraft.network.chat.Component$Serializer
- net.minecraft.network.chat.ComponentUtils
+ net.minecraft.network.chat.ContextAwareComponent
- net.minecraft.network.chat.HoverEvent
+ net.minecraft.network.chat.HoverEvent$Action
- net.minecraft.network.chat.KeybindComponent
+ net.minecraft.network.chat.NbtComponent
- net.minecraft.network.chat.NbtComponent$BlockNbtComponent
+ net.minecraft.network.chat.NbtComponent$EntityNbtComponent
- net.minecraft.network.chat.NbtComponent$StorageNbtComponent
+ net.minecraft.network.chat.package-info
+ net.minecraft.network.chat.ScoreComponent
- net.minecraft.network.chat.SelectorComponent
+ net.minecraft.network.chat.Style
- net.minecraft.network.chat.Style$1
+ net.minecraft.network.chat.Style$Serializer
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
+ net.minecraft.network.protocol.game.ClientboundSetSpawnPositionPacket
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
- net.minecraft.network.protocol.game.DebugPackets
+ net.minecraft.network.protocol.game.DebugVillagerNameGenerator
- net.minecraft.network.protocol.game.package-info
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
- net.minecraft.network.protocol.game.ServerGamePacketListener
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
+ net.minecraft.network.protocol.Packet
- net.minecraft.network.protocol.PacketFlow
+ net.minecraft.network.protocol.PacketUtils
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
- net.minecraft.network.SkipPacketException
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
+ net.minecraft.network.Varint21FrameDecoder
- net.minecraft.network.Varint21LengthFieldPrepender
- net.minecraft.obfuscate.DontObfuscateOrShrink
+ net.minecraft.obfuscate.KeepAfterObfuscation
- net.minecraft.obfuscate.package-info
+ net.minecraft.package-info
- net.minecraft.realms.AbstractRealmsButton
+ net.minecraft.realms.DisconnectedRealmsScreen
- net.minecraft.realms.DisconnectedRealmsScreen$1
+ net.minecraft.realms.package-info
- net.minecraft.realms.pluginapi.LoadedRealmsPlugin
- net.minecraft.realms.pluginapi.package-info
+ net.minecraft.realms.pluginapi.RealmsPlugin
+ net.minecraft.realms.RealmListEntry
- net.minecraft.realms.Realms
+ net.minecraft.realms.RealmsAbstractButtonProxy
- net.minecraft.realms.RealmsAnvilLevelStorageSource
+ net.minecraft.realms.RealmsBridge
- net.minecraft.realms.RealmsButton
+ net.minecraft.realms.RealmsButtonProxy
- net.minecraft.realms.RealmsClickableScrolledSelectionList
+ net.minecraft.realms.RealmsClickableScrolledSelectionListProxy
- net.minecraft.realms.RealmsConfirmResultListener
+ net.minecraft.realms.RealmsConnect
- net.minecraft.realms.RealmsConnect$1
+ net.minecraft.realms.RealmsDefaultVertexFormat
- net.minecraft.realms.RealmsEditBox
+ net.minecraft.realms.RealmsGuiEventListener
- net.minecraft.realms.RealmsLabel
+ net.minecraft.realms.RealmsLabelProxy
- net.minecraft.realms.RealmsLevelSummary
+ net.minecraft.realms.RealmsMth
- net.minecraft.realms.RealmsObjectSelectionList
+ net.minecraft.realms.RealmsObjectSelectionListProxy
- net.minecraft.realms.RealmsScreen
+ net.minecraft.realms.RealmsScreenProxy
- net.minecraft.realms.RealmsScrolledSelectionList
+ net.minecraft.realms.RealmsScrolledSelectionListProxy
- net.minecraft.realms.RealmsServerAddress
+ net.minecraft.realms.RealmsSharedConstants
- net.minecraft.realms.RealmsSimpleScrolledSelectionList
+ net.minecraft.realms.RealmsSimpleScrolledSelectionListProxy
- net.minecraft.realms.RealmsSliderButton
+ net.minecraft.realms.RealmsSliderButtonProxy
- net.minecraft.realms.RealmsVertexFormat
+ net.minecraft.realms.RealmsVertexFormatElement
- net.minecraft.realms.RepeatedNarrator
+ net.minecraft.realms.RepeatedNarrator$Params
- net.minecraft.realms.Tezzelator
- net.minecraft.recipebook.package-info
+ net.minecraft.recipebook.PlaceRecipe
- net.minecraft.recipebook.ServerPlaceRecipe
+ net.minecraft.recipebook.ServerPlaceSmeltingRecipe
- net.minecraft.ReportedException
+ net.minecraft.ResourceLocationException
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
- net.minecraft.server.ConsoleInput
+ net.minecraft.server.ConsoleInputSource
- net.minecraft.server.DebugLoggedPrintStream
+ net.minecraft.server.Eula
- net.minecraft.server.LoggedPrintStream
+ net.minecraft.server.MinecraftServer
- net.minecraft.server.MinecraftServer$1
+ net.minecraft.server.MinecraftServer$2
- net.minecraft.server.MinecraftServer$3
+ net.minecraft.server.PlayerAdvancements
- net.minecraft.server.PlayerAdvancements$1
+ net.minecraft.server.RunningOnDifferentThreadException
- net.minecraft.server.ServerAdvancementManager
+ net.minecraft.server.ServerFunctionManager
- net.minecraft.server.ServerFunctionManager$QueuedCommand
+ net.minecraft.server.ServerInterface
- net.minecraft.server.ServerScoreboard
+ net.minecraft.server.ServerScoreboard$Method
- net.minecraft.server.TickTask
- net.minecraft.SharedConstants
+ net.minecraft.Util
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
- net.minecraft.Util$1
+ net.minecraft.Util$IdentityStrategy
- net.minecraft.Util$OS
+ net.minecraft.Util$OS$1
- net.minecraft.Util$OS$2
+ net.minecraft.world.entity.ai.goal.FollowOwnerGoal
- net.minecraft.world.entity.ai.goal.FollowParentGoal
+ net.minecraft.world.entity.ai.goal.Goal
- net.minecraft.world.entity.ai.goal.Goal$Flag
+ net.minecraft.world.entity.ai.goal.GoalSelector
- net.minecraft.world.entity.ai.goal.GoalSelector$1
+ net.minecraft.world.entity.ai.goal.GoalSelector$2
- net.minecraft.world.entity.ai.goal.InteractGoal
+ net.minecraft.world.entity.ai.goal.JumpGoal
- net.minecraft.world.entity.ai.goal.LandOnOwnersShoulderGoal
+ net.minecraft.world.entity.ai.goal.LeapAtTargetGoal
- net.minecraft.world.entity.ai.goal.LlamaFollowCaravanGoal
+ net.minecraft.world.entity.ai.goal.LookAtPlayerGoal
- net.minecraft.world.entity.ai.goal.LookAtTradingPlayerGoal
+ net.minecraft.world.entity.ai.goal.MeleeAttackGoal
- net.minecraft.world.entity.ai.goal.MoveBackToVillage
+ net.minecraft.world.entity.ai.goal.MoveIndoorsGoal
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
+ net.minecraft.world.entity.ai.goal.PlayGoal
- net.minecraft.world.entity.ai.goal.RandomLookAroundGoal
+ net.minecraft.world.entity.ai.goal.RandomStrollGoal
- net.minecraft.world.entity.ai.goal.RandomSwimmingGoal
+ net.minecraft.world.entity.ai.goal.RangedAttackGoal
- net.minecraft.world.entity.ai.goal.RangedBowAttackGoal
+ net.minecraft.world.entity.ai.goal.RangedCrossbowAttackGoal
- net.minecraft.world.entity.ai.goal.RangedCrossbowAttackGoal$CrossbowState
+ net.minecraft.world.entity.ai.goal.RemoveBlockGoal
- net.minecraft.world.entity.ai.goal.RestrictSunGoal
+ net.minecraft.world.entity.ai.goal.RunAroundLikeCrazyGoal
- net.minecraft.world.entity.ai.goal.SitGoal
+ net.minecraft.world.entity.ai.goal.StrollThroughVillageGoal
- net.minecraft.world.entity.ai.goal.SwellGoal
+ net.minecraft.world.entity.ai.goal.TakeFlowerGoal
+ net.minecraft.world.entity.ai.goal.target.DefendVillageTargetGoal
- net.minecraft.world.entity.ai.goal.target.HurtByTargetGoal
+ net.minecraft.world.entity.ai.goal.target.NearestAttackableTargetGoal
- net.minecraft.world.entity.ai.goal.target.NearestAttackableWitchTargetGoal
+ net.minecraft.world.entity.ai.goal.target.NearestHealableRaiderTargetGoal
- net.minecraft.world.entity.ai.goal.target.NonTameRandomTargetGoal
+ net.minecraft.world.entity.ai.goal.target.OwnerHurtByTargetGoal
- net.minecraft.world.entity.ai.goal.target.OwnerHurtTargetGoal
- net.minecraft.world.entity.ai.goal.target.package-info
+ net.minecraft.world.entity.ai.goal.target.TargetGoal
- net.minecraft.world.entity.ai.goal.TemptGoal
+ net.minecraft.world.entity.ai.goal.TradeWithPlayerGoal
- net.minecraft.world.entity.ai.goal.TryFindWaterGoal
+ net.minecraft.world.entity.ai.goal.UseItemGoal
- net.minecraft.world.entity.ai.goal.WaterAvoidingRandomFlyingGoal
+ net.minecraft.world.entity.ai.goal.WaterAvoidingRandomStrollGoal
- net.minecraft.world.entity.ai.goal.WrappedGoal
+ net.minecraft.world.entity.ai.goal.ZombieAttackGoal
+ net.minecraft.world.entity.ai.gossip.GossipContainer
- net.minecraft.world.entity.ai.gossip.GossipContainer$1
+ net.minecraft.world.entity.ai.gossip.GossipContainer$EntityGossips
- net.minecraft.world.entity.ai.gossip.GossipContainer$GossipEntry
+ net.minecraft.world.entity.ai.gossip.GossipType
- net.minecraft.world.entity.ai.gossip.package-info
+ net.minecraft.world.entity.ai.memory.MemoryModuleType
- net.minecraft.world.entity.ai.memory.MemoryStatus
- net.minecraft.world.entity.ai.memory.package-info
+ net.minecraft.world.entity.ai.memory.WalkTarget
+ net.minecraft.world.entity.ai.navigation.FlyingPathNavigation
- net.minecraft.world.entity.ai.navigation.GroundPathNavigation
- net.minecraft.world.entity.ai.navigation.package-info
+ net.minecraft.world.entity.ai.navigation.PathNavigation
- net.minecraft.world.entity.ai.navigation.WallClimberNavigation
+ net.minecraft.world.entity.ai.navigation.WaterBoundPathNavigation
+ net.minecraft.world.entity.ai.package-info
- net.minecraft.world.entity.ai.sensing.DummySensor
+ net.minecraft.world.entity.ai.sensing.GolemSensor
- net.minecraft.world.entity.ai.sensing.HurtBySensor
+ net.minecraft.world.entity.ai.sensing.InteractableDoorsSensor
- net.minecraft.world.entity.ai.sensing.NearestBedSensor
+ net.minecraft.world.entity.ai.sensing.NearestLivingEntitySensor
+ net.minecraft.world.entity.ai.sensing.package-info
- net.minecraft.world.entity.ai.sensing.PlayerSensor
+ net.minecraft.world.entity.ai.sensing.SecondaryPoiSensor
- net.minecraft.world.entity.ai.sensing.Sensing
+ net.minecraft.world.entity.ai.sensing.Sensor
- net.minecraft.world.entity.ai.sensing.SensorType
+ net.minecraft.world.entity.ai.sensing.VillagerBabiesSensor
- net.minecraft.world.entity.ai.sensing.VillagerHostilesSensor
+ net.minecraft.world.entity.ai.targeting.package-info
- net.minecraft.world.entity.ai.targeting.TargetingConditions
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
+ net.minecraft.world.entity.animal.Animal
- net.minecraft.world.entity.animal.Bee
+ net.minecraft.world.entity.animal.Bee$1
- net.minecraft.world.entity.animal.Bee$BaseBeeGoal
+ net.minecraft.world.entity.animal.Bee$BeeAttackGoal
- net.minecraft.world.entity.animal.Bee$BeeBecomeAngryTargetGoal
+ net.minecraft.world.entity.animal.Bee$BeeEnterHiveGoal
- net.minecraft.world.entity.animal.Bee$BeeGoToBlockGoal
+ net.minecraft.world.entity.animal.Bee$BeeGoToHiveGoal
- net.minecraft.world.entity.animal.Bee$BeeGoToKnownFlowerGoal
+ net.minecraft.world.entity.animal.Bee$BeeGrowCropGoal
- net.minecraft.world.entity.animal.Bee$BeeHurtByOtherGoal
+ net.minecraft.world.entity.animal.Bee$BeeLocateHiveGoal
- net.minecraft.world.entity.animal.Bee$BeeLookControl
+ net.minecraft.world.entity.animal.Bee$BeePollinateGoal
- net.minecraft.world.entity.animal.Bee$BeeWanderGoal
+ net.minecraft.world.entity.animal.Cat
- net.minecraft.world.entity.animal.Cat$CatAvoidEntityGoal
+ net.minecraft.world.entity.animal.Cat$CatRelaxOnOwnerGoal
- net.minecraft.world.entity.animal.Cat$CatTemptGoal
+ net.minecraft.world.entity.animal.Chicken
- net.minecraft.world.entity.animal.Cod
+ net.minecraft.world.entity.animal.Cow
- net.minecraft.world.entity.animal.Dolphin
+ net.minecraft.world.entity.animal.Dolphin$1
- net.minecraft.world.entity.animal.Dolphin$DolphinMoveControl
+ net.minecraft.world.entity.animal.Dolphin$DolphinSwimToTreasureGoal
- net.minecraft.world.entity.animal.Dolphin$DolphinSwimWithPlayerGoal
+ net.minecraft.world.entity.animal.Dolphin$PlayWithItemsGoal
- net.minecraft.world.entity.animal.FlyingAnimal
+ net.minecraft.world.entity.animal.Fox
- net.minecraft.world.entity.animal.Fox$1
+ net.minecraft.world.entity.animal.Fox$DefendTrustedTargetGoal
- net.minecraft.world.entity.animal.Fox$FaceplantGoal
+ net.minecraft.world.entity.animal.Fox$FoxAlertableEntitiesSelector
- net.minecraft.world.entity.animal.Fox$FoxBehaviorGoal
+ net.minecraft.world.entity.animal.Fox$FoxBreedGoal
- net.minecraft.world.entity.animal.Fox$FoxEatBerriesGoal
+ net.minecraft.world.entity.animal.Fox$FoxFloatGoal
- net.minecraft.world.entity.animal.Fox$FoxFollowParentGoal
+ net.minecraft.world.entity.animal.Fox$FoxGroupData
- net.minecraft.world.entity.animal.Fox$FoxLookAtPlayerGoal
+ net.minecraft.world.entity.animal.Fox$FoxLookControl
- net.minecraft.world.entity.animal.Fox$FoxMeleeAttackGoal
+ net.minecraft.world.entity.animal.Fox$FoxMoveControl
- net.minecraft.world.entity.animal.Fox$FoxPanicGoal
+ net.minecraft.world.entity.animal.Fox$FoxPounceGoal
- net.minecraft.world.entity.animal.Fox$FoxSearchForItemsGoal
+ net.minecraft.world.entity.animal.Fox$FoxStrollThroughVillageGoal
- net.minecraft.world.entity.animal.Fox$PerchAndSearchGoal
+ net.minecraft.world.entity.animal.Fox$SeekShelterGoal
- net.minecraft.world.entity.animal.Fox$SleepGoal
+ net.minecraft.world.entity.animal.Fox$StalkPreyGoal
- net.minecraft.world.entity.animal.Fox$Type
+ net.minecraft.world.entity.animal.IronGolem
- net.minecraft.world.entity.animal.IronGolem$Crackiness
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
+ net.minecraft.world.level.block.grower.AbstractMegaTreeGrower
- net.minecraft.world.level.block.grower.AbstractTreeGrower
+ net.minecraft.world.level.block.grower.AcaciaTreeGrower
- net.minecraft.world.level.block.grower.BirchTreeGrower
+ net.minecraft.world.level.block.grower.DarkOakTreeGrower
- net.minecraft.world.level.block.grower.JungleTreeGrower
+ net.minecraft.world.level.block.grower.OakTreeGrower
+ net.minecraft.world.level.block.grower.package-info
- net.minecraft.world.level.block.grower.SpruceTreeGrower
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
+ net.minecraft.world.level.block.LogBlock
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
- net.minecraft.world.level.block.NetherWartBlock
+ net.minecraft.world.level.block.NoteBlock
- net.minecraft.world.level.block.ObserverBlock
+ net.minecraft.world.level.block.OreBlock
- net.minecraft.world.level.block.package-info
- net.minecraft.world.level.block.PipeBlock
+ net.minecraft.world.level.block.piston.MovingPistonBlock
+ net.minecraft.world.level.block.piston.package-info
- net.minecraft.world.level.block.piston.PistonBaseBlock
+ net.minecraft.world.level.block.piston.PistonBaseBlock$1
- net.minecraft.world.level.block.piston.PistonHeadBlock
+ net.minecraft.world.level.block.piston.PistonHeadBlock$1
- net.minecraft.world.level.block.piston.PistonMath
- net.minecraft.world.level.block.piston.PistonMovingBlockEntity
+ net.minecraft.world.level.block.piston.PistonMovingBlockEntity$1
- net.minecraft.world.level.block.piston.PistonStructureResolver
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
+ net.minecraft.world.level.block.SoulsandBlock
- net.minecraft.world.level.block.SoundType
+ net.minecraft.world.level.block.SpawnerBlock
- net.minecraft.world.level.block.SpongeBlock
+ net.minecraft.world.level.block.SpreadingSnowyDirtBlock
- net.minecraft.world.level.block.StainedGlassBlock
+ net.minecraft.world.level.block.StainedGlassPaneBlock
- net.minecraft.world.level.block.StairBlock
+ net.minecraft.world.level.block.StairBlock$1
- net.minecraft.world.level.block.StandingSignBlock
- net.minecraft.world.level.block.state.AbstractStateHolder
+ net.minecraft.world.level.block.state.AbstractStateHolder$1
- net.minecraft.world.level.block.state.BlockState
+ net.minecraft.world.level.block.state.BlockState$1
- net.minecraft.world.level.block.state.BlockState$Cache
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
- net.minecraft.world.level.block.state.properties.AbstractProperty
+ net.minecraft.world.level.block.state.properties.AttachFace
- net.minecraft.world.level.block.state.properties.BambooLeaves
+ net.minecraft.world.level.block.state.properties.BedPart
- net.minecraft.world.level.block.state.properties.BellAttachType
+ net.minecraft.world.level.block.state.properties.BlockStateProperties
- net.minecraft.world.level.block.state.properties.BooleanProperty
+ net.minecraft.world.level.block.state.properties.ChestType
- net.minecraft.world.level.block.state.properties.ComparatorMode
+ net.minecraft.world.level.block.state.properties.DirectionProperty
- net.minecraft.world.level.block.state.properties.DoorHingeSide
+ net.minecraft.world.level.block.state.properties.DoubleBlockHalf
- net.minecraft.world.level.block.state.properties.EnumProperty
+ net.minecraft.world.level.block.state.properties.Half
- net.minecraft.world.level.block.state.properties.IntegerProperty
+ net.minecraft.world.level.block.state.properties.NoteBlockInstrument
+ net.minecraft.world.level.block.state.properties.package-info
- net.minecraft.world.level.block.state.properties.PistonType
+ net.minecraft.world.level.block.state.properties.Property
- net.minecraft.world.level.block.state.properties.RailShape
+ net.minecraft.world.level.block.state.properties.RedstoneSide
- net.minecraft.world.level.block.state.properties.SlabType
+ net.minecraft.world.level.block.state.properties.StairsShape
- net.minecraft.world.level.block.state.properties.StructureMode
+ net.minecraft.world.level.block.state.StateDefinition
- net.minecraft.world.level.block.state.StateDefinition$Builder
+ net.minecraft.world.level.block.state.StateDefinition$Factory
- net.minecraft.world.level.block.state.StateHolder
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
+ net.minecraft.world.level.block.VineBlock
- net.minecraft.world.level.block.VineBlock$1
+ net.minecraft.world.level.block.WallBannerBlock
- net.minecraft.world.level.block.WallBlock
+ net.minecraft.world.level.block.WallSignBlock
- net.minecraft.world.level.block.WallSkullBlock
+ net.minecraft.world.level.block.WallTorchBlock
- net.minecraft.world.level.block.WaterlilyBlock
+ net.minecraft.world.level.block.WebBlock
- net.minecraft.world.level.block.WeightedPressurePlateBlock
+ net.minecraft.world.level.block.WetSpongeBlock
- net.minecraft.world.level.block.WitherRoseBlock
+ net.minecraft.world.level.block.WitherSkullBlock
- net.minecraft.world.level.block.WitherWallSkullBlock
+ net.minecraft.world.level.block.WoodButtonBlock
- net.minecraft.world.level.block.WoolCarpetBlock
- net.minecraft.world.level.border.BorderChangeListener
+ net.minecraft.world.level.border.BorderChangeListener$DelegateBorderChangeListener
- net.minecraft.world.level.border.BorderStatus
- net.minecraft.world.level.border.package-info
+ net.minecraft.world.level.border.WorldBorder
- net.minecraft.world.level.border.WorldBorder$1
+ net.minecraft.world.level.border.WorldBorder$BorderExtent
- net.minecraft.world.level.border.WorldBorder$MovingBorderExtent
+ net.minecraft.world.level.border.WorldBorder$StaticBorderExtent
+ net.minecraft.world.level.chunk.ChunkAccess
- net.minecraft.world.level.chunk.ChunkBiomeContainer
+ net.minecraft.world.level.chunk.ChunkGenerator
- net.minecraft.world.level.chunk.ChunkGeneratorFactory
+ net.minecraft.world.level.chunk.ChunkGeneratorType
- net.minecraft.world.level.chunk.ChunkSource
+ net.minecraft.world.level.chunk.ChunkStatus
- net.minecraft.world.level.chunk.ChunkStatus$ChunkType
+ net.minecraft.world.level.chunk.ChunkStatus$GenerationTask
- net.minecraft.world.level.chunk.ChunkStatus$LoadingTask
+ net.minecraft.world.level.chunk.ChunkStatus$SimpleGenerationTask
- net.minecraft.world.level.chunk.DataLayer
+ net.minecraft.world.level.chunk.EmptyLevelChunk
- net.minecraft.world.level.chunk.FeatureAccess
+ net.minecraft.world.level.chunk.GlobalPalette
- net.minecraft.world.level.chunk.HashMapPalette
+ net.minecraft.world.level.chunk.ImposterProtoChunk
- net.minecraft.world.level.chunk.LevelChunk
+ net.minecraft.world.level.chunk.LevelChunk$EntityCreationType
- net.minecraft.world.level.chunk.LevelChunkSection
+ net.minecraft.world.level.chunk.LightChunkGetter
- net.minecraft.world.level.chunk.LinearPalette
+ net.minecraft.world.level.chunk.OldDataLayer
+ net.minecraft.world.level.chunk.package-info
- net.minecraft.world.level.chunk.Palette
- net.minecraft.world.level.chunk.PalettedContainer
+ net.minecraft.world.level.chunk.PalettedContainer$CountConsumer
+ net.minecraft.world.level.chunk.PaletteResize
- net.minecraft.world.level.chunk.ProtoChunk
+ net.minecraft.world.level.chunk.ProtoTickList
- net.minecraft.world.level.chunk.storage.ChunkSerializer
+ net.minecraft.world.level.chunk.storage.ChunkStorage
- net.minecraft.world.level.chunk.storage.OldChunkStorage
+ net.minecraft.world.level.chunk.storage.OldChunkStorage$OldLevelChunk
- net.minecraft.world.level.chunk.storage.package-info
- net.minecraft.world.level.chunk.storage.RegionBitmap
+ net.minecraft.world.level.chunk.storage.RegionFile
- net.minecraft.world.level.chunk.storage.RegionFile$ChunkBuffer
+ net.minecraft.world.level.chunk.storage.RegionFile$CommitOp
- net.minecraft.world.level.chunk.storage.RegionFileStorage
+ net.minecraft.world.level.chunk.storage.RegionFileVersion
- net.minecraft.world.level.chunk.storage.RegionFileVersion$StreamWrapper
+ net.minecraft.world.level.chunk.storage.SectionStorage
- net.minecraft.world.level.chunk.UpgradeData
+ net.minecraft.world.level.chunk.UpgradeData$1
- net.minecraft.world.level.chunk.UpgradeData$BlockFixer
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$1
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$2
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$3
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$4
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$5
+ net.minecraft.world.level.dimension.Dimension
- net.minecraft.world.level.dimension.DimensionType
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$1
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$2
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$3
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$4
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$5
- net.minecraft.world.level.dimension.end.EndDragonFight
- net.minecraft.world.level.dimension.end.package-info
+ net.minecraft.world.level.dimension.end.TheEndDimension
+ net.minecraft.world.level.dimension.NetherDimension
- net.minecraft.world.level.dimension.NetherDimension$1
+ net.minecraft.world.level.dimension.NormalDimension
+ net.minecraft.world.level.dimension.package-info
+ net.minecraft.world.level.levelgen.carver.CanyonWorldCarver
- net.minecraft.world.level.levelgen.carver.CarverConfiguration
+ net.minecraft.world.level.levelgen.carver.CaveWorldCarver
- net.minecraft.world.level.levelgen.carver.ConfiguredWorldCarver
+ net.minecraft.world.level.levelgen.carver.HellCaveWorldCarver
- net.minecraft.world.level.levelgen.carver.NoneCarverConfiguration
- net.minecraft.world.level.levelgen.carver.package-info
+ net.minecraft.world.level.levelgen.carver.UnderwaterCanyonWorldCarver
- net.minecraft.world.level.levelgen.carver.UnderwaterCaveWorldCarver
+ net.minecraft.world.level.levelgen.carver.WorldCarver
- net.minecraft.world.level.levelgen.ChunkGeneratorSettings
+ net.minecraft.world.level.levelgen.DebugGeneratorSettings
- net.minecraft.world.level.levelgen.DebugLevelSource
- net.minecraft.world.level.levelgen.feature.AbstractHugeMushroomFeature
- net.minecraft.world.level.levelgen.feature.BambooFeature
+ net.minecraft.world.level.levelgen.feature.BigTreeFeature
+ net.minecraft.world.level.levelgen.feature.BirchFeature
+ net.minecraft.world.level.levelgen.feature.BlockBlobFeature
- net.minecraft.world.level.levelgen.feature.BlockPileFeature
- net.minecraft.world.level.levelgen.feature.blockplacers.BlockPlacerType
- net.minecraft.world.level.levelgen.feature.blockplacers.DoublePlantPlacer
- net.minecraft.world.level.levelgen.feature.blockplacers.package-info
+ net.minecraft.world.level.levelgen.feature.BlueIceFeature
- net.minecraft.world.level.levelgen.feature.BonusChestFeature
+ net.minecraft.world.level.levelgen.feature.BuriedTreasureConfiguration
+ net.minecraft.world.level.levelgen.feature.BushFeature
+ net.minecraft.world.level.levelgen.feature.CentralSpikedFeature
- net.minecraft.world.level.levelgen.feature.configurations.BlockPileConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.BuriedTreasureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.CountFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.DecoratedFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.DiskConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.FeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.HugeMushroomFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.MegaTreeConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.MineshaftConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.NoneDecoratorConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.OceanRuinConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.OreConfiguration$Predicates
- net.minecraft.world.level.levelgen.feature.configurations.package-info
- net.minecraft.world.level.levelgen.feature.configurations.RandomBooleanFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.RandomPatchConfiguration$GrassConfigurationBuilder
- net.minecraft.world.level.levelgen.feature.configurations.ReplaceBlockConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ShipwreckConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SimpleRandomFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SmallTreeConfiguration$SmallTreeConfigurationBuilder
- net.minecraft.world.level.levelgen.feature.configurations.SpringConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
+ net.minecraft.world.level.levelgen.feature.DarkOakFeature
+ net.minecraft.world.level.levelgen.feature.DecoratedFlowerFeature
+ net.minecraft.world.level.levelgen.feature.DecoratorConfiguration
+ net.minecraft.world.level.levelgen.feature.DecoratorNoiseDependant
- net.minecraft.world.level.levelgen.feature.DefaultFlowerFeature
+ net.minecraft.world.level.levelgen.feature.DesertPyramidFeature
- net.minecraft.world.level.levelgen.feature.DesertPyramidFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.DesertVillagePools
- net.minecraft.world.level.levelgen.feature.DesertWellFeature
+ net.minecraft.world.level.levelgen.feature.DiskConfiguration
+ net.minecraft.world.level.levelgen.feature.DoublePlantConfiguration
+ net.minecraft.world.level.levelgen.feature.EndGatewayConfiguration
- net.minecraft.world.level.levelgen.feature.EndGatewayFeature
+ net.minecraft.world.level.levelgen.feature.EndIslandFeature
- net.minecraft.world.level.levelgen.feature.EndPodiumFeature
- net.minecraft.world.level.levelgen.feature.FancyTreeFeature$FoliageCoords
+ net.minecraft.world.level.levelgen.feature.Feature
+ net.minecraft.world.level.levelgen.feature.FeatureRadius
- net.minecraft.world.level.levelgen.feature.FillLayerFeature
+ net.minecraft.world.level.levelgen.feature.FlowerFeature
- net.minecraft.world.level.levelgen.feature.foliageplacers.BlobFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacerType
- net.minecraft.world.level.levelgen.feature.foliageplacers.SpruceFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.FossilFeature
+ net.minecraft.world.level.levelgen.feature.GrassFeature
+ net.minecraft.world.level.levelgen.feature.HayBlockPileFeature
+ net.minecraft.world.level.levelgen.feature.HellSpringConfiguration
- net.minecraft.world.level.levelgen.feature.HugeBrownMushroomFeature
+ net.minecraft.world.level.levelgen.feature.HugeMushroomFeatureConfig
+ net.minecraft.world.level.levelgen.feature.IceBlockPileFeature
- net.minecraft.world.level.levelgen.feature.IcePatchFeature
+ net.minecraft.world.level.levelgen.feature.IceSpikeFeature
+ net.minecraft.world.level.levelgen.feature.JunglePyramidFeature
- net.minecraft.world.level.levelgen.feature.JunglePyramidFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.JungleTreeFeature
+ net.minecraft.world.level.levelgen.feature.LakeConfiguration
- net.minecraft.world.level.levelgen.feature.LakeFeature
+ net.minecraft.world.level.levelgen.feature.LayerConfiguration
+ net.minecraft.world.level.levelgen.feature.MelonBlockPileFeature
+ net.minecraft.world.level.levelgen.feature.MineshaftConfiguration
- net.minecraft.world.level.levelgen.feature.MineshaftFeature
+ net.minecraft.world.level.levelgen.feature.MineshaftFeature$MineShaftStart
- net.minecraft.world.level.levelgen.feature.MineshaftFeature$Type
+ net.minecraft.world.level.levelgen.feature.MonsterRoomFeature
- net.minecraft.world.level.levelgen.feature.NetherFortressFeature
+ net.minecraft.world.level.levelgen.feature.NetherFortressFeature$NetherBridgeStart
+ net.minecraft.world.level.levelgen.feature.NoneDecoratorConfiguration
+ net.minecraft.world.level.levelgen.feature.OceanRuinConfiguration
+ net.minecraft.world.level.levelgen.feature.OreConfiguration$Predicates
- net.minecraft.world.level.levelgen.feature.OreFeature
- net.minecraft.world.level.levelgen.feature.package-info
+ net.minecraft.world.level.levelgen.feature.PillagerOutpostConfiguration
+ net.minecraft.world.level.levelgen.feature.PlainFlowerFeature
+ net.minecraft.world.level.levelgen.feature.ProbabilityFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.RandomBooleanFeatureConfig
- net.minecraft.world.level.levelgen.feature.RandomBooleanSelectorFeature
+ net.minecraft.world.level.levelgen.feature.RandomFeatureConfig
- net.minecraft.world.level.levelgen.feature.RandomRandomFeature
+ net.minecraft.world.level.levelgen.feature.RandomRandomFeatureConfig
+ net.minecraft.world.level.levelgen.feature.ReplaceBlockConfiguration
+ net.minecraft.world.level.levelgen.feature.SavannaTreeFeature
- net.minecraft.world.level.levelgen.feature.SavannaVillagePools
- net.minecraft.world.level.levelgen.feature.SeagrassFeature
+ net.minecraft.world.level.levelgen.feature.SeagrassFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.SeaPickleFeature
+ net.minecraft.world.level.levelgen.feature.ShipwreckFeature
- net.minecraft.world.level.levelgen.feature.ShipwreckFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.SimpleBlockConfiguration
+ net.minecraft.world.level.levelgen.feature.SimpleRandomFeatureConfig
- net.minecraft.world.level.levelgen.feature.SimpleRandomSelectorFeature
+ net.minecraft.world.level.levelgen.feature.SimulatedFeature
- net.minecraft.world.level.levelgen.feature.SnowAndFreezeFeature
+ net.minecraft.world.level.levelgen.feature.SnowBlockPileFeature
+ net.minecraft.world.level.levelgen.feature.SpikeConfiguration
- net.minecraft.world.level.levelgen.feature.SpikeFeature
+ net.minecraft.world.level.levelgen.feature.SpikeFeature$1
- net.minecraft.world.level.levelgen.feature.SpikeFeature$EndSpike
+ net.minecraft.world.level.levelgen.feature.SpikeFeature$SpikeCacheLoader
- net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProviderType
- net.minecraft.world.level.levelgen.feature.stateproviders.package-info
- net.minecraft.world.level.levelgen.feature.stateproviders.PlainFlowerProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.SimpleStateProvider
+ net.minecraft.world.level.levelgen.feature.StrongholdFeature
- net.minecraft.world.level.levelgen.feature.StrongholdFeature$StrongholdStart
+ net.minecraft.world.level.levelgen.feature.StructureFeature
- net.minecraft.world.level.levelgen.feature.StructureFeature$StructureStartFactory
+ net.minecraft.world.level.levelgen.feature.StructurePieceType
+ net.minecraft.world.level.levelgen.feature.structures.EmptyPoolElement
- net.minecraft.world.level.levelgen.feature.structures.FeaturePoolElement
+ net.minecraft.world.level.levelgen.feature.structures.JigsawJunction
- net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$1
- net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$PieceFactory
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$PieceState
- net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$Placer
+ net.minecraft.world.level.levelgen.feature.structures.ListPoolElement
- net.minecraft.world.level.levelgen.feature.structures.package-info
- net.minecraft.world.level.levelgen.feature.structures.SinglePoolElement
+ net.minecraft.world.level.levelgen.feature.structures.StructurePoolElement
- net.minecraft.world.level.levelgen.feature.structures.StructurePoolElementType
+ net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool
- net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool$Projection
+ net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePools
- net.minecraft.world.level.levelgen.feature.SwamplandHutFeature
+ net.minecraft.world.level.levelgen.feature.SwamplandHutFeature$FeatureStart
+ net.minecraft.world.level.levelgen.feature.SwampTreeFeature
- net.minecraft.world.level.levelgen.feature.treedecorators.BeehiveDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.LeaveVineDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.package-info
- net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecoratorType
+ net.minecraft.world.level.levelgen.feature.VillageConfiguration
- net.minecraft.world.level.levelgen.feature.VillageFeature
+ net.minecraft.world.level.levelgen.feature.VillageFeature$FeatureStart
- net.minecraft.world.level.levelgen.feature.VillagePieces
+ net.minecraft.world.level.levelgen.feature.VillagePieces$VillagePiece
- net.minecraft.world.level.levelgen.feature.VinesFeature
+ net.minecraft.world.level.levelgen.feature.VoidStartPlatformFeature
+ net.minecraft.world.level.levelgen.flat.FlatLayerInfo
- net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorSettings
+ net.minecraft.world.level.levelgen.flat.package-info
+ net.minecraft.world.level.levelgen.FlatLevelSource
- net.minecraft.world.level.levelgen.FlatLevelSource$FlatLevelBiomeWrapper
+ net.minecraft.world.level.levelgen.GenerationStep
- net.minecraft.world.level.levelgen.GenerationStep$Carving
+ net.minecraft.world.level.levelgen.GenerationStep$Decoration
- net.minecraft.world.level.levelgen.Heightmap
+ net.minecraft.world.level.levelgen.Heightmap$Types
- net.minecraft.world.level.levelgen.Heightmap$Usage
+ net.minecraft.world.level.levelgen.NetherGeneratorSettings
- net.minecraft.world.level.levelgen.NetherLevelSource
+ net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator
- net.minecraft.world.level.levelgen.OverworldGeneratorSettings
+ net.minecraft.world.level.levelgen.OverworldLevelSource
- net.minecraft.world.level.levelgen.package-info
- net.minecraft.world.level.levelgen.PatrolSpawner
+ net.minecraft.world.level.levelgen.PhantomSpawner
+ net.minecraft.world.level.levelgen.placement.CarvingMaskDecorator
- net.minecraft.world.level.levelgen.placement.CarvingMaskDecoratorConfiguration
- net.minecraft.world.level.levelgen.placement.ChanceHeightmapDecorator
+ net.minecraft.world.level.levelgen.placement.ChanceHeightmapDoubleDecorator
- net.minecraft.world.level.levelgen.placement.ChancePassthroughDecorator
+ net.minecraft.world.level.levelgen.placement.ChanceTopSolidHeightmapDecorator
- net.minecraft.world.level.levelgen.placement.ChorusPlantPlacementDecorator
+ net.minecraft.world.level.levelgen.placement.ConfiguredDecorator
- net.minecraft.world.level.levelgen.placement.CountBiasedRangeDecorator
+ net.minecraft.world.level.levelgen.placement.CountChanceHeightmapDecorator
- net.minecraft.world.level.levelgen.placement.CountChanceHeightmapDoubleDecorator
+ net.minecraft.world.level.levelgen.placement.CountDepthAverageDecorator
- net.minecraft.world.level.levelgen.placement.CountHeighmapDoubleDecorator
+ net.minecraft.world.level.levelgen.placement.CountHeight64Decorator
- net.minecraft.world.level.levelgen.placement.CountHeightmap32Decorator
+ net.minecraft.world.level.levelgen.placement.CountHeightmapDecorator
- net.minecraft.world.level.levelgen.placement.CountTopSolidDecorator
+ net.minecraft.world.level.levelgen.placement.CountVeryBiasedRangeDecorator
- net.minecraft.world.level.levelgen.placement.CountWithExtraChanceHeightmapDecorator
+ net.minecraft.world.level.levelgen.placement.DarkOakTreePlacementDecorator
+ net.minecraft.world.level.levelgen.placement.DecoratorChance
+ net.minecraft.world.level.levelgen.placement.DecoratorFrequencyChance
+ net.minecraft.world.level.levelgen.placement.DecoratorNoiseCountFactor
- net.minecraft.world.level.levelgen.placement.FrequencyChanceDecoratorConfiguration
- net.minecraft.world.level.levelgen.placement.FrequencyWithExtraChanceDecoratorConfiguration
+ net.minecraft.world.level.levelgen.placement.IcebergPlacementDecorator
+ net.minecraft.world.level.levelgen.placement.MonsterRoomPlacementConfiguration
- net.minecraft.world.level.levelgen.placement.MonsterRoomPlacementDecorator
- net.minecraft.world.level.levelgen.placement.nether.ChanceRangeDecorator
+ net.minecraft.world.level.levelgen.placement.nether.CountRangeDecorator
- net.minecraft.world.level.levelgen.placement.nether.HellFireDecorator
+ net.minecraft.world.level.levelgen.placement.nether.LightGemChanceDecorator
- net.minecraft.world.level.levelgen.placement.nether.MagmaDecorator
- net.minecraft.world.level.levelgen.placement.nether.package-info
+ net.minecraft.world.level.levelgen.placement.nether.RandomCountRangeDecorator
+ net.minecraft.world.level.levelgen.placement.package-info
- net.minecraft.world.level.levelgen.placement.SimpleFeatureDecorator
+ net.minecraft.world.level.levelgen.placement.TopSolidHeightMapDecorator
- net.minecraft.world.level.levelgen.placement.TopSolidHeightMapNoiseBasedDecorator
+ net.minecraft.world.level.levelgen.placement.TopSolidHeightMapRangeDecorator
- net.minecraft.world.level.levelgen.structure.BeardedStructureStart
+ net.minecraft.world.level.levelgen.structure.BoundingBox
- net.minecraft.world.level.levelgen.structure.BoundingBox$1
+ net.minecraft.world.level.levelgen.structure.BuriedTreasurePieces
- net.minecraft.world.level.levelgen.structure.BuriedTreasurePieces$BuriedTreasurePiece
+ net.minecraft.world.level.levelgen.structure.DesertPyramidPiece
- net.minecraft.world.level.levelgen.structure.EndCityPieces
+ net.minecraft.world.level.levelgen.structure.EndCityPieces$1
- net.minecraft.world.level.levelgen.structure.EndCityPieces$2
+ net.minecraft.world.level.levelgen.structure.EndCityPieces$3
- net.minecraft.world.level.levelgen.structure.EndCityPieces$4
+ net.minecraft.world.level.levelgen.structure.EndCityPieces$EndCityPiece
- net.minecraft.world.level.levelgen.structure.EndCityPieces$SectionGenerator
+ net.minecraft.world.level.levelgen.structure.IglooPieces
- net.minecraft.world.level.levelgen.structure.IglooPieces$IglooPiece
+ net.minecraft.world.level.levelgen.structure.JunglePyramidPiece
- net.minecraft.world.level.levelgen.structure.JunglePyramidPiece$1
+ net.minecraft.world.level.levelgen.structure.JunglePyramidPiece$MossStoneSelector
- net.minecraft.world.level.levelgen.structure.LegacyStructureDataHandler
+ net.minecraft.world.level.levelgen.structure.MineShaftPieces
- net.minecraft.world.level.levelgen.structure.MineShaftPieces$1
+ net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftCorridor
- net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftCrossing
+ net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftPiece
- net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftRoom
+ net.minecraft.world.level.levelgen.structure.MineShaftPieces$MineShaftStairs
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$1
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$BridgeCrossing
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$BridgeEndFiller
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$BridgeStraight
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleCorridorStairsPiece
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleCorridorTBalconyPiece
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleEntrance
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorCrossingPiece
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorLeftTurnPiece
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorPiece
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleSmallCorridorRightTurnPiece
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$CastleStalkRoom
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$MonsterThrone
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$NetherBridgePiece
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$PieceWeight
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$RoomCrossing
+ net.minecraft.world.level.levelgen.structure.NetherBridgePieces$StairsRoom
- net.minecraft.world.level.levelgen.structure.NetherBridgePieces$StartPiece
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$1
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleXRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleXYRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleYRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleYZRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitDoubleZRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitSimpleRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$FitSimpleTopRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$MonumentBuilding
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$MonumentRoomFitter
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentCoreRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleXYRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleYZRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentDoubleZRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentEntryRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentPenthouse
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentPiece
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentSimpleTopRoom
+ net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$OceanMonumentWingRoom
- net.minecraft.world.level.levelgen.structure.OceanMonumentPieces$RoomDefinition
+ net.minecraft.world.level.levelgen.structure.OceanRuinFeature
- net.minecraft.world.level.levelgen.structure.OceanRuinFeature$OceanRuinStart
+ net.minecraft.world.level.levelgen.structure.OceanRuinFeature$Type
- net.minecraft.world.level.levelgen.structure.OceanRuinPieces
+ net.minecraft.world.level.levelgen.structure.OceanRuinPieces$OceanRuinPiece
- net.minecraft.world.level.levelgen.structure.package-info
- net.minecraft.world.level.levelgen.structure.PillagerOutpostPieces
+ net.minecraft.world.level.levelgen.structure.PillagerOutpostPieces$PillagerOutpostPiece
- net.minecraft.world.level.levelgen.structure.PoolElementStructurePiece
+ net.minecraft.world.level.levelgen.structure.ScatteredFeaturePiece
- net.minecraft.world.level.levelgen.structure.ShipwreckPieces
+ net.minecraft.world.level.levelgen.structure.ShipwreckPieces$ShipwreckPiece
- net.minecraft.world.level.levelgen.structure.StrongholdPieces
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$1
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$2
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$3
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$ChestCorridor
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$FillerCorridor
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$FiveCrossing
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$LeftTurn
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$Library
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$PieceWeight
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$PortalRoom
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$PrisonHall
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$RightTurn
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$RoomCrossing
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$SmoothStoneSelector
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$StairsDown
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$StartPiece
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$Straight
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$StraightStairsDown
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$StrongholdPiece
- net.minecraft.world.level.levelgen.structure.StrongholdPieces$StrongholdPiece$SmallDoorType
+ net.minecraft.world.level.levelgen.structure.StrongholdPieces$Turn
+ net.minecraft.world.level.levelgen.structure.StructureFeatureIndexSavedData
- net.minecraft.world.level.levelgen.structure.StructureFeatureIO
- net.minecraft.world.level.levelgen.structure.StructurePiece
+ net.minecraft.world.level.levelgen.structure.StructurePiece$1
- net.minecraft.world.level.levelgen.structure.StructurePiece$BlockSelector
+ net.minecraft.world.level.levelgen.structure.StructureStart
- net.minecraft.world.level.levelgen.structure.StructureStart$1
+ net.minecraft.world.level.levelgen.structure.SwamplandHutPiece
- net.minecraft.world.level.levelgen.structure.TemplateStructurePiece
+ net.minecraft.world.level.levelgen.structure.templatesystem.AlwaysTrueTest
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockIgnoreProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockMatchTest
- net.minecraft.world.level.levelgen.structure.templatesystem.BlockRotProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.BlockStateMatchTest
- net.minecraft.world.level.levelgen.structure.templatesystem.GravityProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.JigsawReplacementProcessor
- net.minecraft.world.level.levelgen.structure.templatesystem.NopProcessor
+ net.minecraft.world.level.levelgen.structure.templatesystem.package-info
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
+ net.minecraft.world.level.levelgen.surfacebuilders.ConfiguredSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.DefaultSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.ErodedBadlandsSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.FrozenOceanSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.GiantTreeTaigaSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.GravellyMountainSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.MountainSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.NetherSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.NopeSurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.package-info
- net.minecraft.world.level.levelgen.surfacebuilders.ShatteredSavanaSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.SurfaceBuilder
- net.minecraft.world.level.levelgen.surfacebuilders.SurfaceBuilderBaseConfiguration
+ net.minecraft.world.level.levelgen.surfacebuilders.SurfaceBuilderConfiguration
- net.minecraft.world.level.levelgen.surfacebuilders.SwampSurfaceBuilder
+ net.minecraft.world.level.levelgen.surfacebuilders.WoodedBadlandsSurfaceBuilder
+ net.minecraft.world.level.levelgen.synth.ImprovedNoise
- net.minecraft.world.level.levelgen.synth.package-info
- net.minecraft.world.level.levelgen.synth.PerlinNoise
+ net.minecraft.world.level.levelgen.synth.PerlinSimplexNoise
- net.minecraft.world.level.levelgen.synth.SimplexNoise
+ net.minecraft.world.level.levelgen.synth.SurfaceNoise
- net.minecraft.world.level.levelgen.TheEndGeneratorSettings
+ net.minecraft.world.level.levelgen.TheEndLevelSource
- net.minecraft.world.level.levelgen.WorldgenRandom
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
+ net.minecraft.world.level.material.EmptyFluid
- net.minecraft.world.level.material.FlowingFluid
+ net.minecraft.world.level.material.FlowingFluid$1
- net.minecraft.world.level.material.Fluid
+ net.minecraft.world.level.material.Fluids
+ net.minecraft.world.level.material.FluidState
- net.minecraft.world.level.material.FluidStateImpl
- net.minecraft.world.level.material.LavaFluid
+ net.minecraft.world.level.material.LavaFluid$Flowing
- net.minecraft.world.level.material.LavaFluid$Source
+ net.minecraft.world.level.material.Material
- net.minecraft.world.level.material.Material$Builder
+ net.minecraft.world.level.material.MaterialColor
- net.minecraft.world.level.material.package-info
- net.minecraft.world.level.material.PushReaction
+ net.minecraft.world.level.material.WaterFluid
- net.minecraft.world.level.material.WaterFluid$Flowing
+ net.minecraft.world.level.material.WaterFluid$Source
+ net.minecraft.world.level.newbiome.area.Area
- net.minecraft.world.level.newbiome.area.AreaFactory
+ net.minecraft.world.level.newbiome.area.LazyArea
- net.minecraft.world.level.newbiome.area.package-info
+ net.minecraft.world.level.newbiome.context.BigContext
- net.minecraft.world.level.newbiome.context.Context
+ net.minecraft.world.level.newbiome.context.LazyAreaContext
- net.minecraft.world.level.newbiome.context.package-info
+ net.minecraft.world.level.newbiome.layer.AddDeepOceanLayer
- net.minecraft.world.level.newbiome.layer.AddEdgeLayer
+ net.minecraft.world.level.newbiome.layer.AddEdgeLayer$CoolWarm
- net.minecraft.world.level.newbiome.layer.AddEdgeLayer$HeatIce
+ net.minecraft.world.level.newbiome.layer.AddEdgeLayer$IntroduceSpecial
- net.minecraft.world.level.newbiome.layer.AddIslandLayer
+ net.minecraft.world.level.newbiome.layer.AddMushroomIslandLayer
- net.minecraft.world.level.newbiome.layer.AddSnowLayer
+ net.minecraft.world.level.newbiome.layer.BiomeEdgeLayer
- net.minecraft.world.level.newbiome.layer.BiomeInitLayer
+ net.minecraft.world.level.newbiome.layer.IslandLayer
- net.minecraft.world.level.newbiome.layer.Layer
+ net.minecraft.world.level.newbiome.layer.Layers
- net.minecraft.world.level.newbiome.layer.OceanLayer
+ net.minecraft.world.level.newbiome.layer.OceanMixerLayer
+ net.minecraft.world.level.newbiome.layer.package-info
- net.minecraft.world.level.newbiome.layer.RareBiomeLargeLayer
+ net.minecraft.world.level.newbiome.layer.RareBiomeSpotLayer
- net.minecraft.world.level.newbiome.layer.RegionHillsLayer
+ net.minecraft.world.level.newbiome.layer.RemoveTooMuchOceanLayer
- net.minecraft.world.level.newbiome.layer.RiverInitLayer
+ net.minecraft.world.level.newbiome.layer.RiverLayer
- net.minecraft.world.level.newbiome.layer.RiverMixerLayer
+ net.minecraft.world.level.newbiome.layer.ShoreLayer
- net.minecraft.world.level.newbiome.layer.SmoothLayer
- net.minecraft.world.level.newbiome.layer.traits.AreaTransformer0
+ net.minecraft.world.level.newbiome.layer.traits.AreaTransformer1
- net.minecraft.world.level.newbiome.layer.traits.AreaTransformer2
+ net.minecraft.world.level.newbiome.layer.traits.BishopTransformer
- net.minecraft.world.level.newbiome.layer.traits.C0Transformer
+ net.minecraft.world.level.newbiome.layer.traits.C1Transformer
- net.minecraft.world.level.newbiome.layer.traits.CastleTransformer
+ net.minecraft.world.level.newbiome.layer.traits.DimensionOffset0Transformer
- net.minecraft.world.level.newbiome.layer.traits.DimensionOffset1Transformer
+ net.minecraft.world.level.newbiome.layer.traits.DimensionTransformer
+ net.minecraft.world.level.newbiome.layer.traits.package-info
- net.minecraft.world.level.newbiome.layer.traits.PixelTransformer
+ net.minecraft.world.level.newbiome.layer.ZoomLayer
- net.minecraft.world.level.newbiome.layer.ZoomLayer$1
- net.minecraft.world.level.package-info
+ net.minecraft.world.level.pathfinder.BinaryHeap
- net.minecraft.world.level.pathfinder.BlockPathTypes
+ net.minecraft.world.level.pathfinder.FlyNodeEvaluator
- net.minecraft.world.level.pathfinder.Node
+ net.minecraft.world.level.pathfinder.NodeEvaluator
+ net.minecraft.world.level.pathfinder.package-info
- net.minecraft.world.level.pathfinder.Path
+ net.minecraft.world.level.pathfinder.PathComputationType
- net.minecraft.world.level.pathfinder.PathFinder
+ net.minecraft.world.level.pathfinder.SwimNodeEvaluator
- net.minecraft.world.level.pathfinder.Target
+ net.minecraft.world.level.pathfinder.TurtleNodeEvaluator
- net.minecraft.world.level.pathfinder.WalkNodeEvaluator
+ net.minecraft.world.level.redstone.package-info
- net.minecraft.world.level.redstone.Redstone
- net.minecraft.world.level.saveddata.maps.MapBanner
+ net.minecraft.world.level.saveddata.maps.MapBanner$1
- net.minecraft.world.level.saveddata.maps.MapDecoration
+ net.minecraft.world.level.saveddata.maps.MapDecoration$Type
- net.minecraft.world.level.saveddata.maps.MapFrame
+ net.minecraft.world.level.saveddata.maps.MapIndex
- net.minecraft.world.level.saveddata.maps.MapItemSavedData
+ net.minecraft.world.level.saveddata.maps.MapItemSavedData$HoldingPlayer
- net.minecraft.world.level.saveddata.maps.package-info
+ net.minecraft.world.level.saveddata.package-info
- net.minecraft.world.level.saveddata.SaveDataDirtyRunnable
+ net.minecraft.world.level.saveddata.SavedData
- net.minecraft.world.level.storage.CommandStorage
+ net.minecraft.world.level.storage.CommandStorage$Container
- net.minecraft.world.level.storage.DerivedLevelData
+ net.minecraft.world.level.storage.DimensionDataStorage
- net.minecraft.world.level.storage.LevelData
+ net.minecraft.world.level.storage.LevelStorage
- net.minecraft.world.level.storage.LevelStorageException
+ net.minecraft.world.level.storage.LevelStorageSource
- net.minecraft.world.level.storage.LevelStorageSource$1
+ net.minecraft.world.level.storage.LevelSummary
- net.minecraft.world.level.storage.loot.BinomialDistributionGenerator
+ net.minecraft.world.level.storage.loot.BinomialDistributionGenerator$Serializer
- net.minecraft.world.level.storage.loot.BuiltInLootTables
+ net.minecraft.world.level.storage.loot.ConstantIntValue
- net.minecraft.world.level.storage.loot.ConstantIntValue$Serializer
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
- net.minecraft.world.level.storage.McRegionUpgrader
+ net.minecraft.world.level.storage.package-info
+ net.minecraft.world.level.storage.PlayerIO
- net.minecraft.world.level.storage.threaded.package-info
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
XXX.gui.components.AbstractWidget +1M
```
```
XXX.gui.screens.AccessibilityOptionsScreen -1M | -2P
```
```
XXX.gui.screens.ChatOptionsScreen -1M | -2P
```
```
XXX.gui.screens.LanguageSelectScreen -2P
```
```
XXX.gui.screens.LoadingOverlay +1M -1M
```
```
XXX.gui.screens.MouseSettingsScreen +1M -2M | -1P
```
```
XXX.client.renderer.RenderType +34M -58M | +1P -4P
```
```
XXX.renderer.block.BlockRenderDispatcher +1M -1M
```
```
XXX.renderer.blockentity.BeaconRenderer +2M -2M
```
```
XXX.renderer.blockentity.BellRenderer +2M -2M
```
```
XXX.renderer.blockentity.BlockEntityRenderer +1P -1P
```
```
XXX.renderer.blockentity.ChestRenderer +2M -2M
```
```
XXX.renderer.blockentity.EnchantTableRenderer +2M -2M
```
```
XXX.renderer.blockentity.PistonHeadRenderer +3M -3M
```
```
XXX.renderer.blockentity.SignRenderer +2M -2M
```
```
XXX.renderer.blockentity.StructureBlockRenderer +2M -2M
```
```
XXX.renderer.blockentity.TheEndGatewayRenderer +3M -3M
```
```
XXX.minecraft.core.BlockPos +1M
```
```
XXX.minecraft.core.BlockPos$MutableBlockPos +1M
```
```
XXX.minecraft.sounds.SoundEvents +8P -1P
```
```
XXX.minecraft.tags.BlockTags -1P
```
```
XXX.entity.monster.Blaze +1M -1M
```
```
XXX.entity.npc.Villager +4M -6M
```
```
XXX.entity.player.Player +1M -1M
```
```
XXX.entity.vehicle.MinecartTNT +1M -1M
```
```
XXX.world.item.Items +3P -1P
```
```
XXX.world.level.BlockEventData +1M
```
```
XXX.level.biome.Biome +9M -9M
```
```
XXX.level.block.Block +4M -4M | +2P
```
```
XXX.level.block.Block$Properties +6M -2M | +2P
```
```
XXX.levelgen.feature.AbstractTreeFeature +16M -14M | +1P -1P
```
```
XXX.levelgen.feature.ConfiguredFeature +3M -1M | +1P -1P
```
```
XXX.levelgen.feature.CoralFeature +2M -2M
```
```
XXX.levelgen.feature.DecoratedFeature +2M -2M
```
```
XXX.levelgen.feature.GlowstoneFeature +2M -2M
```
```
XXX.levelgen.feature.IcebergFeature +2M -2M
```
```
XXX.levelgen.feature.MegaPineTreeFeature +4M -7M | -4P
```
```
XXX.levelgen.feature.RandomSelectorFeature +2M -2M
```
```
XXX.levelgen.feature.SpringFeature +2M -2M
```
```
XXX.levelgen.feature.WeightedConfiguredFeature +1M -2M | +2P -3P
```
```
XXX.levelgen.placement.EndGatewayPlacementDecorator +2M -2M
```
```
XXX.levelgen.placement.FeatureDecorator +3M -2M | +1P -1P
```
```
XXX.levelgen.placement.LakeLavaPlacementDecorator +2M -2M
```
```
XXX.levelgen.placement.NoiseHeightmap32Decorator +3M -3M
```
```
XXX.levelgen.placement.NopePlacementDecorator +2M -2M
```

</details>































<details>
<summary>
net.minecraft.client.gui.components.AbstractWidget
</summary>

```diff
- void queueNarration(int)
```

</details>







































<details>
<summary>
net.minecraft.client.gui.screens.AccessibilityOptionsScreen
</summary>

```diff
+ void removed()
```

</details>

<details>
<summary>
net.minecraft.client.gui.screens.ChatOptionsScreen
</summary>

```diff
+ void removed()
```

</details>













<details>
<summary>
net.minecraft.client.gui.screens.LoadingOverlay
</summary>

```diff
+ void drawProgressBar(int,int,int,int,float,float)
- void drawProgressBar(int,int,int,int,float)
```

</details>

<details>
<summary>
net.minecraft.client.gui.screens.MouseSettingsScreen
</summary>

```diff
- void <init>(Screen,Options)
+ void <init>(Screen)
+ void removed()
```

</details>
<details>
<summary>
net.minecraft.client.renderer.RenderType
</summary>

```diff
+ boolean equals(Object)
+ int hashCode()
- RenderType beaconBeam()
- RenderType crumbling(int)
+ RenderType CRUMBLING(int)
- RenderType cutout()
- RenderType cutoutMipped()
- RenderType endPortal(int)
- RenderType entityAlpha(ResourceLocation,float)
- RenderType entityCutout(ResourceLocation)
- RenderType entityCutoutNoCull(ResourceLocation)
- RenderType entityDecal(ResourceLocation)
- RenderType entityForceTranslucent(ResourceLocation)
- RenderType entityGlint()
- RenderType entityNoOutline(ResourceLocation)
- RenderType entitySmoothCutout(ResourceLocation)
- RenderType entitySolid(ResourceLocation)
- RenderType entityTranslucent(ResourceLocation)
- RenderType eyes(ResourceLocation)
+ RenderType EYES(ResourceLocation)
- RenderType getChunkRenderType(BlockState)
+ RenderType getRenderLayer(BlockState)
- RenderType getRenderType(BlockState)
- RenderType getRenderType(ItemStack)
- RenderType glint()
- RenderType leash()
- RenderType lightning()
- RenderType lines()
+ RenderType NEW_ENTITY(ResourceLocation,boolean,boolean,boolean,float,boolean,boolean)
+ RenderType NEW_ENTITY(ResourceLocation,boolean,boolean,boolean)
+ RenderType NEW_ENTITY(ResourceLocation)
- RenderType outline(ResourceLocation)
+ RenderType OUTLINE(ResourceLocation)
+ RenderType PORTAL(int)
+ RenderType POWER_SWIRL(ResourceLocation,float,float)
- RenderType powerSwirl(ResourceLocation,float,float)
- RenderType solid()
+ RenderType TEXT_SEE_THROUGH(ResourceLocation)
- RenderType text(ResourceLocation)
+ RenderType TEXT(ResourceLocation)
- RenderType textSeeThrough(ResourceLocation)
- RenderType translucent()
- RenderType translucentNoCrumbling()
- RenderType waterMask()
- void <init>(String,VertexFormat,int,int,boolean,boolean,Runnable,Runnable)
+ void <init>(String,VertexFormat,int,int,boolean,Runnable,Runnable)
+ void clearGlint()
+ void clearRenderState()
+ void lambda$CRUMBLING$24(Integer)
+ void lambda$CRUMBLING$25(Integer)
+ void lambda$EYES$10(ResourceLocation)
+ void lambda$EYES$11(ResourceLocation)
+ void lambda$NEW_ENTITY$8(RenderType$EntityState)
+ void lambda$NEW_ENTITY$9(RenderType$EntityState)
+ void lambda$OUTLINE$18(ResourceLocation)
+ void lambda$OUTLINE$19(ResourceLocation)
+ void lambda$PORTAL$34(Integer)
+ void lambda$PORTAL$35(Integer)
+ void lambda$POWER_SWIRL$12(RenderType,RenderType$SwirlState)
+ void lambda$POWER_SWIRL$13(RenderType,RenderType$SwirlState)
+ void lambda$static$0()
- void lambda$static$0(HashMap)
+ void lambda$static$1()
- void lambda$static$1(HashMap)
+ void lambda$static$14()
+ void lambda$static$15()
+ void lambda$static$16()
+ void lambda$static$17()
+ void lambda$static$2()
+ void lambda$static$20()
+ void lambda$static$21()
+ void lambda$static$22()
+ void lambda$static$23()
+ void lambda$static$3()
+ void lambda$static$30()
+ void lambda$static$31()
+ void lambda$static$32()
+ void lambda$static$33()
+ void lambda$static$36()
+ void lambda$static$37()
+ void lambda$static$38(HashMap)
+ void lambda$static$39(HashMap)
+ void lambda$static$4()
+ void lambda$static$5()
+ void lambda$static$6()
+ void lambda$static$7()
+ void lambda$TEXT_SEE_THROUGH$28(RenderType,ResourceLocation)
+ void lambda$TEXT_SEE_THROUGH$29(RenderType,ResourceLocation)
+ void lambda$TEXT$26(ResourceLocation)
+ void lambda$TEXT$27(ResourceLocation)
+ void setupGlint(float)
+ void setupRenderState()
```

</details>




<details>
<summary>
net.minecraft.client.renderer.block.BlockRenderDispatcher
</summary>

```diff
+ void renderSingleBlock(BlockState,PoseStack,MultiBufferSource,int,int,int)
- void renderSingleBlock(BlockState,PoseStack,MultiBufferSource,int,int)
```

</details>






























<details>
<summary>
net.minecraft.client.renderer.blockentity.BeaconRenderer
</summary>

```diff
- void render(BeaconBlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int,int)
+ void render(BeaconBlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int)
- void render(BlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int,int)
+ void render(BlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.blockentity.BellRenderer
</summary>

```diff
- void render(BellBlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int,int)
+ void render(BellBlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int)
- void render(BlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int,int)
+ void render(BlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int)
```

</details>

<details>
<summary>
net.minecraft.client.renderer.blockentity.ChestRenderer
</summary>

```diff
- void render(BlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int,int)
+ void render(BlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int)
- void render(PoseStack,VertexConsumer,ModelPart,ModelPart,ModelPart,float,int,int,TextureAtlasSprite)
+ void render(PoseStack,VertexConsumer,ModelPart,ModelPart,ModelPart,float,int,TextureAtlasSprite)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.blockentity.EnchantTableRenderer
</summary>

```diff
- void render(BlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int,int)
+ void render(BlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int)
- void render(EnchantmentTableBlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int,int)
+ void render(EnchantmentTableBlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.blockentity.PistonHeadRenderer
</summary>

```diff
- void render(BlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int,int)
+ void render(BlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int)
- void render(PistonMovingBlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int,int)
+ void render(PistonMovingBlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int)
- void renderBlock(BlockPos,BlockState,PoseStack,MultiBufferSource,Level,boolean,int)
+ void renderBlock(BlockPos,BlockState,PoseStack,MultiBufferSource,Level,boolean)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.blockentity.SignRenderer
</summary>

```diff
- void render(BlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int,int)
+ void render(BlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int)
- void render(SignBlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int,int)
+ void render(SignBlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int)
```

</details>

<details>
<summary>
net.minecraft.client.renderer.blockentity.StructureBlockRenderer
</summary>

```diff
- void render(BlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int,int)
+ void render(BlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int)
- void render(StructureBlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int,int)
+ void render(StructureBlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.blockentity.TheEndGatewayRenderer
</summary>

```diff
- void render(BlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int,int)
+ void render(BlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int)
- void render(TheEndGatewayBlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int,int)
+ void render(TheEndGatewayBlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int)
- void render(TheEndPortalBlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int,int)
+ void render(TheEndPortalBlockEntity,double,double,double,float,PoseStack,MultiBufferSource,int)
```

</details>

























































































































































<details>
<summary>
net.minecraft.core.BlockPos
</summary>

```diff
- Stream betweenClosedStream(BoundingBox)
```

</details>

<details>
<summary>
net.minecraft.core.BlockPos$MutableBlockPos
</summary>

```diff
- void <init>(Entity)
```

</details>




















































































































































































































































































































































































































<details>
<summary>
net.minecraft.world.entity.monster.Blaze
</summary>

```diff
- boolean causeFallDamage(float,float)
+ void causeFallDamage(float,float)
```

</details>
























































<details>
<summary>
net.minecraft.world.entity.npc.Villager
</summary>

```diff
+ boolean lambda$spawnGolemIfNeeded$10(long,Villager)
- boolean lambda$spawnGolemIfNeeded$8(long,Villager)
+ Component getDisplayName()
- Component getTypeName()
- int lambda$countFoodPointsInInventory$7(SimpleContainer,Map$Entry)
+ int lambda$countFoodPointsInInventory$9(SimpleContainer,Map$Entry)
+ void lambda$getDisplayName$7(Style)
+ void lambda$getDisplayName$8(Style)
+ void lambda$spawnGolemIfNeeded$11(long,Villager)
- void lambda$spawnGolemIfNeeded$9(long,Villager)
```

</details>












<details>
<summary>
net.minecraft.world.entity.player.Player
</summary>

```diff
- boolean causeFallDamage(float,float)
+ void causeFallDamage(float,float)
```

</details>

































<details>
<summary>
net.minecraft.world.entity.vehicle.MinecartTNT
</summary>

```diff
- boolean causeFallDamage(float,float)
+ void causeFallDamage(float,float)
```

</details>


































































































































































<details>
<summary>
net.minecraft.world.level.BlockEventData
</summary>

```diff
- int hashCode()
```

</details>


























<details>
<summary>
net.minecraft.world.level.biome.Biome
</summary>

```diff
+ ConfiguredFeature makeComposite(Feature,FeatureConfiguration,FeatureDecorator,DecoratorConfiguration)
+ FeatureConfiguration getStructureConfiguration(StructureFeature)
- FeatureConfiguration getStructureConfiguration(StructureFeature)
- Object lambda$null$10(DynamicOps,Biome$SpawnerData)
+ Object lambda$null$4(DynamicOps,ConfiguredWorldCarver)
- Object lambda$null$5(DynamicOps,ConfiguredWorldCarver)
+ Object lambda$null$6(DynamicOps,ConfiguredFeature)
- Object lambda$null$7(DynamicOps,ConfiguredFeature)
+ Object lambda$null$9(DynamicOps,Biome$SpawnerData)
+ Pair lambda$serialize$10(DynamicOps,Map$Entry)
- Pair lambda$serialize$11(DynamicOps,Map$Entry)
+ Pair lambda$serialize$5(DynamicOps,Map$Entry)
- Pair lambda$serialize$6(DynamicOps,Map$Entry)
+ Pair lambda$serialize$7(DynamicOps,Map$Entry)
- Pair lambda$serialize$9(DynamicOps,Map$Entry)
- String lambda$generate$4(ConfiguredFeature)
- void addStructureStart(ConfiguredFeature)
+ void addStructureStart(StructureFeature,FeatureConfiguration)
```

</details>






























































<details>
<summary>
net.minecraft.world.level.block.Block
</summary>

```diff
+ boolean access$1200(Block)
+ boolean access$1300(Block)
- boolean access$1400(Block)
- boolean access$1500(Block)
+ boolean equalsDirt(Block)
+ boolean equalsStone(Block)
- float getJumpFactor()
- float getSpeedFactor()
```

</details>


<details>
<summary>
net.minecraft.world.level.block.Block$Properties
</summary>

```diff
- Block$Properties jumpFactor(float)
- Block$Properties speedFactor(float)
- boolean access$1300(Block$Properties)
+ boolean access$900(Block$Properties)
- float access$1000(Block$Properties)
- float access$900(Block$Properties)
+ ResourceLocation access$1000(Block$Properties)
- ResourceLocation access$1200(Block$Properties)
```

</details>









































<details>
<summary>
net.minecraft.world.level.levelgen.feature.AbstractTreeFeature
</summary>

```diff
+ boolean isFluidWater(LevelSimulatedReader,BlockPos)
+ boolean isLeaves(LevelSimulatedReader,BlockPos)
- boolean isVine(LevelSimulatedReader,BlockPos)
- boolean lambda$isAirOrLeaves$4(BlockState)
+ boolean lambda$isAirOrLeaves$5(BlockState)
+ boolean lambda$isFluidWater$2(FluidState)
- boolean lambda$isGrassOrDirt$5(BlockState)
+ boolean lambda$isGrassOrDirt$6(BlockState)
- boolean lambda$isGrassOrDirtOrFarmland$6(BlockState)
+ boolean lambda$isGrassOrDirtOrFarmland$7(BlockState)
+ boolean lambda$isLeaves$4(BlockState)
- boolean lambda$isReplaceablePlant$7(BlockState)
+ boolean lambda$isReplaceablePlant$8(BlockState)
- boolean lambda$isVine$2(BlockState)
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration,boolean)
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
- boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
- boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,TreeConfiguration)
- boolean placeLeaf(LevelSimulatedRW,Random,BlockPos,Set,BoundingBox,TreeConfiguration)
- boolean placeLog(LevelSimulatedRW,Random,BlockPos,Set,BoundingBox,TreeConfiguration)
- DiscreteVoxelShape updateLeaves(LevelAccessor,BoundingBox,Set,Set)
+ void <init>(Function,boolean)
- void <init>(Function)
- void lambda$place$8(LevelAccessor,Random,List,List,Set,BoundingBox,TreeDecorator)
- void setBlock(LevelWriter,BlockPos,BlockState,BoundingBox)
+ void setBlock(Set,LevelWriter,BlockPos,BlockState,BoundingBox)
+ void simulate(FeatureSimulator,Random,BlockPos,FeatureConfiguration)
- void simulate(FeatureSimulator,Random,BlockPos,FeatureConfiguration)
- void simulate(FeatureSimulator,Random,BlockPos,TreeConfiguration)
+ void spawnBeehive(LevelAccessor,Random,BlockPos,BoundingBox,List,Biome)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.ConfiguredFeature
</summary>

```diff
- ConfiguredFeature decorated(ConfiguredDecorator)
+ void <init>(Feature,FeatureConfiguration)
- void <init>(Feature,FeatureConfiguration)
- WeightedConfiguredFeature weighted(float)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.CoralFeature
</summary>

```diff
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
- boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,NoneFeatureConfiguration)
- boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,NoneFeatureConfiguration)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.DecoratedFeature
</summary>

```diff
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,DecoratedFeatureConfiguration)
- boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,DecoratedFeatureConfiguration)
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
- boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.GlowstoneFeature
</summary>

```diff
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
- boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,NoneFeatureConfiguration)
- boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,NoneFeatureConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.IcebergFeature
</summary>

```diff
- boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,BlockStateConfiguration)
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
- boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,IcebergConfiguration)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.MegaPineTreeFeature
</summary>

```diff
- boolean doPlace(LevelSimulatedRW,Random,BlockPos,Set,Set,BoundingBox,MegaTreeConfiguration)
- boolean doPlace(LevelSimulatedRW,Random,BlockPos,Set,Set,BoundingBox,TreeConfiguration)
+ boolean doPlace(Set,LevelSimulatedRW,Random,BlockPos,BoundingBox)
+ void <clinit>()
+ void <init>(Function,boolean,boolean)
- void <init>(Function)
+ void createCrown(LevelSimulatedRW,int,int,int,int,Random,BoundingBox,Set)
- void createCrown(LevelSimulatedRW,Random,int,int,int,int,Set,BoundingBox,MegaTreeConfiguration)
+ void placePodzolAt(LevelSimulatedRW,BlockPos)
+ void placePodzolCircle(LevelSimulatedRW,BlockPos)
+ void postPlaceTree(LevelSimulatedRW,Random,BlockPos)
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.feature.RandomSelectorFeature
</summary>

```diff
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
- boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,RandomFeatureConfig)
- boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,RandomFeatureConfiguration)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.SpringFeature
</summary>

```diff
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
- boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,FeatureConfiguration)
+ boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,SpringConfiguration)
- boolean place(LevelAccessor,ChunkGenerator,Random,BlockPos,SpringConfiguration)
```

</details>

<details>
<summary>
net.minecraft.world.level.levelgen.feature.WeightedConfiguredFeature
</summary>

```diff
- void <init>(ConfiguredFeature,float)
+ void <init>(Feature,Dynamic,float)
+ void <init>(Feature,FeatureConfiguration,Float)
```

</details>


<details>
<summary>
net.minecraft.world.level.levelgen.placement.EndGatewayPlacementDecorator
</summary>

```diff
+ Stream getPositions(LevelAccessor,ChunkGenerator,Random,DecoratorConfiguration,BlockPos)
- Stream getPositions(LevelAccessor,ChunkGenerator,Random,DecoratorConfiguration,BlockPos)
+ Stream getPositions(LevelAccessor,ChunkGenerator,Random,NoneDecoratorConfiguration,BlockPos)
- Stream getPositions(LevelAccessor,ChunkGenerator,Random,NoneDecoratorConfiguration,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.FeatureDecorator
</summary>

```diff
+ boolean placeFeature(LevelAccessor,ChunkGenerator,Random,BlockPos,DecoratorConfiguration,ConfiguredFeature)
- boolean placeFeature(LevelAccessor,ChunkGenerator,Random,BlockPos,DecoratorConfiguration,ConfiguredFeature)
- ConfiguredDecorator configured(DecoratorConfiguration)
+ DecoratorConfiguration createSettings(Dynamic)
- DecoratorConfiguration createSettings(Dynamic)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.LakeLavaPlacementDecorator
</summary>

```diff
- Stream getPositions(LevelAccessor,ChunkGenerator,Random,ChanceDecoratorConfiguration,BlockPos)
+ Stream getPositions(LevelAccessor,ChunkGenerator,Random,DecoratorConfiguration,BlockPos)
- Stream getPositions(LevelAccessor,ChunkGenerator,Random,DecoratorConfiguration,BlockPos)
+ Stream getPositions(LevelAccessor,ChunkGenerator,Random,LakeChanceDecoratorConfig,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.NoiseHeightmap32Decorator
</summary>

```diff
- BlockPos lambda$getPositions$0(Random,BlockPos,LevelAccessor,int)
+ BlockPos lambda$getPositions$0(Random,LevelAccessor,BlockPos,int)
+ Stream getPositions(LevelAccessor,ChunkGenerator,Random,DecoratorConfiguration,BlockPos)
- Stream getPositions(LevelAccessor,ChunkGenerator,Random,DecoratorConfiguration,BlockPos)
+ Stream getPositions(LevelAccessor,ChunkGenerator,Random,DecoratorNoiseDependant,BlockPos)
- Stream getPositions(LevelAccessor,ChunkGenerator,Random,NoiseDependantDecoratorConfiguration,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.placement.NopePlacementDecorator
</summary>

```diff
+ Stream place(Random,DecoratorConfiguration,BlockPos)
- Stream place(Random,DecoratorConfiguration,BlockPos)
+ Stream place(Random,NoneDecoratorConfiguration,BlockPos)
- Stream place(Random,NoneDecoratorConfiguration,BlockPos)
```

</details>
</details>