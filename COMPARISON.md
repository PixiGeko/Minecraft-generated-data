## Comparison with [21w39a](https://github.com/PixiGeko/Minecraft-generated-data/tree/21w39a)

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
<table><tr><th></th><th align="left">21w39a</th><th>21w40a</th></tr><tr><td>World version</td><td><code>2836</code></td><td><code>2838</code></td></tr><tr><td>Protocol version</td><td><code>1073741867</code></td><td><code>1073741868</code></td></tr></table>
</details>
<details><summary>Registries</summary>
<details>
<summary>
block_predicate_type.txt
</summary>

```diff
+ minecraft:true
+ minecraft:would_survive
```

</details>






































<details>
<summary>
worldgen/decorator.txt
</summary>

```diff
- minecraft:block_survives_filter
```

</details>
</details>
<details><summary>Tags</summary>
<details>
<summary>
universal_tags/block_predicate_type.json
</summary>

```diff
+ minecraft:true
+ minecraft:would_survive
```

</details>






































<details>
<summary>
universal_tags/worldgen/decorator.json
</summary>

```diff
- minecraft:block_survives_filter
```

</details>
</details>
<details><summary>Translations</summary>
<details>
<summary>
Keys
</summary>

```diff
- biome.minecraft.badlands_plateau: Badlands Plateau
- biome.minecraft.bamboo_jungle_hills: Bamboo Jungle Hills
- biome.minecraft.birch_forest_hills: Birch Forest Hills
- biome.minecraft.dark_forest_hills: Dark Forest Hills
- biome.minecraft.desert_hills: Desert Hills
- biome.minecraft.desert_lakes: Desert Lakes
+ biome.minecraft.frozen_peaks: Frozen Peaks
- biome.minecraft.giant_spruce_taiga_hills: Giant Spruce Taiga Hills
- biome.minecraft.giant_spruce_taiga: Giant Spruce Taiga
- biome.minecraft.giant_tree_taiga_hills: Giant Tree Taiga Hills
- biome.minecraft.giant_tree_taiga: Giant Tree Taiga
- biome.minecraft.gravelly_mountains: Gravelly Mountains
+ biome.minecraft.grove: Grove
+ biome.minecraft.jagged_peaks: Jagged Peaks
- biome.minecraft.jungle_edge: Jungle Edge
- biome.minecraft.jungle_hills: Jungle Hills
+ biome.minecraft.meadow: Meadow
- biome.minecraft.modified_badlands_plateau: Modified Badlands Plateau
- biome.minecraft.modified_gravelly_mountains: Gravelly Mountains+
- biome.minecraft.modified_jungle_edge: Modified Jungle Edge
- biome.minecraft.modified_jungle: Modified Jungle
- biome.minecraft.modified_wooded_badlands_plateau: Modified Wooded Badlands Plateau
- biome.minecraft.mountain_edge: Mountain Edge
- biome.minecraft.mountains: Mountains
- biome.minecraft.mushroom_field_shore: Mushroom Field Shore
+ biome.minecraft.old_growth_birch_forest: Old Growth Birch Forest
+ biome.minecraft.old_growth_pine_taiga: Old Growth Pine Taiga
+ biome.minecraft.old_growth_spruce_taiga: Old Growth Spruce Taiga
- biome.minecraft.shattered_savanna_plateau: Shattered Savanna Plateau
- biome.minecraft.shattered_savanna: Shattered Savanna
- biome.minecraft.snowy_mountains: Snowy Mountains
+ biome.minecraft.snowy_plains: Snowy Plains
+ biome.minecraft.snowy_slopes: Snowy Slopes
- biome.minecraft.snowy_taiga_hills: Snowy Taiga Hills
- biome.minecraft.snowy_taiga_mountains: Snowy Taiga Mountains
- biome.minecraft.snowy_tundra: Snowy Tundra
+ biome.minecraft.sparse_jungle: Sparse Jungle
- biome.minecraft.stone_shore: Stone Shore
+ biome.minecraft.stony_peaks: Stony Peaks
+ biome.minecraft.stony_shore: Stony Shore
- biome.minecraft.swamp_hills: Swamp Hills
- biome.minecraft.taiga_hills: Taiga Hills
- biome.minecraft.taiga_mountains: Taiga Mountains
- biome.minecraft.tall_birch_forest: Tall Birch Forest
- biome.minecraft.tall_birch_hills: Tall Birch Hills
+ biome.minecraft.windswept_forest: Windswept Forest
+ biome.minecraft.windswept_gravelly_hills: Windswept Gravelly Hills
+ biome.minecraft.windswept_hills: Windswept Hills
+ biome.minecraft.windswept_savanna: Windswept Savanna
- biome.minecraft.wooded_badlands_plateau: Wooded Badlands Plateau
+ biome.minecraft.wooded_badlands: Wooded Badlands
- biome.minecraft.wooded_hills: Wooded Hills
- biome.minecraft.wooded_mountains: Wooded Mountains
```

</details>
</details>
<details><summary>File structure</summary>
<details>
<summary>
generated
</summary>

```diff
- reports/biomes/badlands_plateau.json
- reports/biomes/bamboo_jungle_hills.json
- reports/biomes/birch_forest_hills.json
- reports/biomes/dark_forest_hills.json
- reports/biomes/desert_hills.json
- reports/biomes/desert_lakes.json
+ reports/biomes/frozen_peaks.json
- reports/biomes/giant_spruce_taiga_hills.json
- reports/biomes/giant_spruce_taiga.json
- reports/biomes/giant_tree_taiga_hills.json
- reports/biomes/giant_tree_taiga.json
- reports/biomes/gravelly_mountains.json
+ reports/biomes/jagged_peaks.json
- reports/biomes/jungle_edge.json
- reports/biomes/jungle_hills.json
- reports/biomes/lofty_peaks.json
- reports/biomes/modified_badlands_plateau.json
- reports/biomes/modified_gravelly_mountains.json
- reports/biomes/modified_jungle_edge.json
- reports/biomes/modified_jungle.json
- reports/biomes/modified_wooded_badlands_plateau.json
- reports/biomes/mountain_edge.json
- reports/biomes/mountains.json
- reports/biomes/mushroom_field_shore.json
+ reports/biomes/old_growth_birch_forest.json
+ reports/biomes/old_growth_pine_taiga.json
+ reports/biomes/old_growth_spruce_taiga.json
- reports/biomes/shattered_savanna_plateau.json
- reports/biomes/shattered_savanna.json
- reports/biomes/snowcapped_peaks.json
- reports/biomes/snowy_mountains.json
+ reports/biomes/snowy_plains.json
- reports/biomes/snowy_taiga_hills.json
- reports/biomes/snowy_taiga_mountains.json
- reports/biomes/snowy_tundra.json
+ reports/biomes/sparse_jungle.json
- reports/biomes/stone_shore.json
+ reports/biomes/stony_shore.json
- reports/biomes/swamp_hills.json
- reports/biomes/taiga_hills.json
- reports/biomes/taiga_mountains.json
- reports/biomes/tall_birch_forest.json
- reports/biomes/tall_birch_hills.json
+ reports/biomes/windswept_forest.json
+ reports/biomes/windswept_gravelly_hills.json
+ reports/biomes/windswept_hills.json
+ reports/biomes/windswept_savanna.json
- reports/biomes/wooded_badlands_plateau.json
+ reports/biomes/wooded_badlands.json
- reports/biomes/wooded_hills.json
- reports/biomes/wooded_mountains.json
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
- net.minecraft.network.protocol.game.ClientboundSetSimulationDistancePacket
+ net.minecraft.network.protocol.game.ClientboundSetSubtitleTextPacket
- net.minecraft.network.protocol.game.ClientboundSetTimePacket
- net.minecraft.network.protocol.game.ClientboundSetTitlesAnimationPacket
+ net.minecraft.network.protocol.game.ClientboundSetTitleTextPacket
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
+ net.minecraft.network.protocol.game.ServerboundContainerButtonClickPacket
- net.minecraft.network.protocol.game.ServerboundContainerClickPacket
+ net.minecraft.network.protocol.game.ServerboundContainerClosePacket
- net.minecraft.network.protocol.game.ServerboundCustomPayloadPacket
+ net.minecraft.network.protocol.game.ServerboundEditBookPacket
- net.minecraft.network.protocol.game.ServerboundEntityTagQuery
+ net.minecraft.network.protocol.game.ServerboundInteractPacket
- net.minecraft.network.protocol.game.ServerboundInteractPacket$1
+ net.minecraft.network.protocol.game.ServerboundInteractPacket$Action
- net.minecraft.network.protocol.game.ServerboundInteractPacket$ActionType
+ net.minecraft.network.protocol.game.ServerboundInteractPacket$Handler
- net.minecraft.network.protocol.game.ServerboundInteractPacket$InteractionAction
+ net.minecraft.network.protocol.game.ServerboundInteractPacket$InteractionAtLocationAction
- net.minecraft.network.protocol.game.ServerboundJigsawGeneratePacket
+ net.minecraft.network.protocol.game.ServerboundKeepAlivePacket
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
- net.minecraft.network.protocol.game.ServerboundPongPacket
+ net.minecraft.network.protocol.game.ServerboundRecipeBookChangeSettingsPacket
- net.minecraft.network.protocol.game.ServerboundRecipeBookSeenRecipePacket
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
+ net.minecraft.obfuscate.DontObfuscate
- net.minecraft.obfuscate.package-info
+ net.minecraft.package-info
- net.minecraft.recipebook.package-info
- net.minecraft.recipebook.PlaceRecipe
+ net.minecraft.recipebook.ServerPlaceRecipe
+ net.minecraft.resources.DelegatingOps
+ net.minecraft.resources.package-info
- net.minecraft.resources.RegistryDataPackCodec
+ net.minecraft.resources.RegistryFileCodec
- net.minecraft.resources.RegistryLookupCodec
+ net.minecraft.resources.RegistryReadOps
- net.minecraft.resources.RegistryReadOps$1
+ net.minecraft.resources.RegistryReadOps$ReadCache
- net.minecraft.resources.RegistryReadOps$ResourceAccess
+ net.minecraft.resources.RegistryReadOps$ResourceAccess$1
- net.minecraft.resources.RegistryReadOps$ResourceAccess$MemoryMap
+ net.minecraft.resources.RegistryWriteOps
- net.minecraft.resources.ResourceKey
+ net.minecraft.resources.ResourceLocation
- net.minecraft.resources.ResourceLocation$Serializer
- net.minecraft.server.Bootstrap
+ net.minecraft.server.Bootstrap$1
- net.minecraft.server.bossevents.CustomBossEvent
+ net.minecraft.server.bossevents.CustomBossEvents
- net.minecraft.server.bossevents.package-info
- net.minecraft.server.ChainedJsonException
+ net.minecraft.server.ChainedJsonException$Entry
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
+ net.minecraft.server.commands.DebugCommand$Tracer
- net.minecraft.server.commands.DebugMobSpawningCommand
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
+ net.minecraft.server.commands.ItemCommands
- net.minecraft.server.commands.JfrCommand
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
+ net.minecraft.server.commands.package-info
- net.minecraft.server.commands.PardonCommand
+ net.minecraft.server.commands.PardonIpCommand
- net.minecraft.server.commands.ParticleCommand
+ net.minecraft.server.commands.PerfCommand
- net.minecraft.server.commands.PlaySoundCommand
+ net.minecraft.server.commands.PublishCommand
- net.minecraft.server.commands.RaidCommand
+ net.minecraft.server.commands.RecipeCommand
- net.minecraft.server.commands.ReloadCommand
+ net.minecraft.server.commands.ResetChunksCommand
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
- net.minecraft.server.ConsoleInput
+ net.minecraft.server.DebugLoggedPrintStream
- net.minecraft.server.dedicated.DedicatedPlayerList
+ net.minecraft.server.dedicated.DedicatedServer
- net.minecraft.server.dedicated.DedicatedServer$1
+ net.minecraft.server.dedicated.DedicatedServerProperties
- net.minecraft.server.dedicated.DedicatedServerSettings
+ net.minecraft.server.dedicated.package-info
+ net.minecraft.server.dedicated.ServerWatchdog
- net.minecraft.server.dedicated.ServerWatchdog$1
+ net.minecraft.server.dedicated.Settings
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
+ net.minecraft.server.level.ChunkHolder$ChunkSaveDebug
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
- net.minecraft.server.level.ChunkTaskPriorityQueueSorter$Message
+ net.minecraft.server.level.ChunkTaskPriorityQueueSorter$Release
- net.minecraft.server.level.ChunkTracker
+ net.minecraft.server.level.ColumnPos
- net.minecraft.server.level.DemoMode
+ net.minecraft.server.level.DistanceManager
- net.minecraft.server.level.DistanceManager$ChunkTicketTracker
+ net.minecraft.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
- net.minecraft.server.level.DistanceManager$PlayerTicketTracker
+ net.minecraft.server.level.package-info
+ net.minecraft.server.level.PlayerMap
- net.minecraft.server.level.PlayerRespawnLogic
- net.minecraft.server.level.progress.ChunkProgressListener
+ net.minecraft.server.level.progress.ChunkProgressListenerFactory
- net.minecraft.server.level.progress.LoggerChunkProgressListener
+ net.minecraft.server.level.progress.package-info
+ net.minecraft.server.level.progress.ProcessorChunkProgressListener
- net.minecraft.server.level.progress.StoringChunkProgressListener
+ net.minecraft.server.level.SectionTracker
- net.minecraft.server.level.ServerBossEvent
+ net.minecraft.server.level.ServerChunkCache
- net.minecraft.server.level.ServerChunkCache$ChunkAndHolder
+ net.minecraft.server.level.ServerChunkCache$MainThreadExecutor
- net.minecraft.server.level.ServerEntity
+ net.minecraft.server.level.ServerLevel
- net.minecraft.server.level.ServerLevel$EntityCallbacks
+ net.minecraft.server.level.ServerPlayer
- net.minecraft.server.level.ServerPlayer$1
+ net.minecraft.server.level.ServerPlayer$2
- net.minecraft.server.level.ServerPlayer$3
+ net.minecraft.server.level.ServerPlayerGameMode
- net.minecraft.server.level.ThreadedLevelLightEngine
+ net.minecraft.server.level.ThreadedLevelLightEngine$TaskType
- net.minecraft.server.level.Ticket
+ net.minecraft.server.level.TicketType
- net.minecraft.server.level.TickingTracker
+ net.minecraft.server.level.WorldGenRegion
- net.minecraft.server.level.WorldGenTickList
+ net.minecraft.server.LoggedPrintStream
- net.minecraft.server.Main
+ net.minecraft.server.Main$1
- net.minecraft.server.MinecraftServer
+ net.minecraft.server.MinecraftServer$1
- net.minecraft.server.MinecraftServer$TimeProfiler
+ net.minecraft.server.MinecraftServer$TimeProfiler$1
- net.minecraft.server.network.LegacyQueryHandler
+ net.minecraft.server.network.MemoryServerHandshakePacketListenerImpl
+ net.minecraft.server.network.package-info
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
- net.minecraft.server.network.TextFilter$FilteredText
+ net.minecraft.server.network.TextFilterClient
- net.minecraft.server.network.TextFilterClient$IgnoreStrategy
+ net.minecraft.server.network.TextFilterClient$PlayerContext
- net.minecraft.server.network.TextFilterClient$RequestFailedException
- net.minecraft.server.package-info
+ net.minecraft.server.packs.AbstractPackResources
- net.minecraft.server.packs.FilePackResources
+ net.minecraft.server.packs.FolderPackResources
+ net.minecraft.server.packs.metadata.MetadataSectionSerializer
- net.minecraft.server.packs.metadata.pack.package-info
- net.minecraft.server.packs.metadata.pack.PackMetadataSection
+ net.minecraft.server.packs.metadata.pack.PackMetadataSectionSerializer
+ net.minecraft.server.packs.metadata.package-info
- net.minecraft.server.packs.package-info
- net.minecraft.server.packs.PackResources
+ net.minecraft.server.packs.PackType
+ net.minecraft.server.packs.repository.FolderRepositorySource
- net.minecraft.server.packs.repository.Pack
+ net.minecraft.server.packs.repository.Pack$PackConstructor
- net.minecraft.server.packs.repository.Pack$Position
- net.minecraft.server.packs.repository.package-info
+ net.minecraft.server.packs.repository.PackCompatibility
- net.minecraft.server.packs.repository.PackRepository
+ net.minecraft.server.packs.repository.PackSource
- net.minecraft.server.packs.repository.RepositorySource
+ net.minecraft.server.packs.repository.ServerPacksSource
- net.minecraft.server.packs.ResourcePackFileNotFoundException
+ net.minecraft.server.packs.resources.FallbackResourceManager
- net.minecraft.server.packs.resources.FallbackResourceManager$LeakedResourceWarningInputStream
+ net.minecraft.server.packs.resources.package-info
+ net.minecraft.server.packs.resources.PreparableReloadListener
- net.minecraft.server.packs.resources.PreparableReloadListener$PreparationBarrier
+ net.minecraft.server.packs.resources.ProfiledReloadInstance
- net.minecraft.server.packs.resources.ProfiledReloadInstance$State
- net.minecraft.server.packs.resources.ReloadableResourceManager
+ net.minecraft.server.packs.resources.ReloadInstance
+ net.minecraft.server.packs.resources.Resource
- net.minecraft.server.packs.resources.ResourceManager
+ net.minecraft.server.packs.resources.ResourceManager$Empty
- net.minecraft.server.packs.resources.ResourceManagerReloadListener
+ net.minecraft.server.packs.resources.ResourceProvider
- net.minecraft.server.packs.resources.SimpleJsonResourceReloadListener
+ net.minecraft.server.packs.resources.SimplePreparableReloadListener
+ net.minecraft.server.packs.resources.SimpleReloadableResourceManager
- net.minecraft.server.packs.resources.SimpleReloadableResourceManager$FailingReloadInstance
+ net.minecraft.server.packs.resources.SimpleReloadableResourceManager$ResourcePackLoadingFailure
- net.minecraft.server.packs.resources.SimpleReloadInstance
+ net.minecraft.server.packs.resources.SimpleReloadInstance$1
- net.minecraft.server.packs.resources.SimpleReloadInstance$StateFactory
- net.minecraft.server.packs.resources.SimpleResource
+ net.minecraft.server.packs.VanillaPackResources
- net.minecraft.server.packs.VanillaPackResources$1
- net.minecraft.server.PlayerAdvancements
+ net.minecraft.server.PlayerAdvancements$1
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
- net.minecraft.server.RunningOnDifferentThreadException
+ net.minecraft.server.ServerAdvancementManager
- net.minecraft.server.ServerFunctionLibrary
+ net.minecraft.server.ServerFunctionManager
- net.minecraft.server.ServerFunctionManager$ExecutionContext
+ net.minecraft.server.ServerFunctionManager$QueuedCommand
- net.minecraft.server.ServerFunctionManager$TraceCallbacks
+ net.minecraft.server.ServerInterface
- net.minecraft.server.ServerResources
+ net.minecraft.server.ServerScoreboard
- net.minecraft.server.ServerScoreboard$Method
+ net.minecraft.server.TickTask
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
- net.minecraft.tags.BlockTags
+ net.minecraft.tags.EntityTypeTags
- net.minecraft.tags.FluidTags
+ net.minecraft.tags.GameEventTags
- net.minecraft.tags.ItemTags
+ net.minecraft.tags.package-info
+ net.minecraft.tags.SerializationTags
- net.minecraft.tags.SetTag
+ net.minecraft.tags.StaticTagHelper
- net.minecraft.tags.StaticTagHelper$Wrapper
+ net.minecraft.tags.StaticTags
- net.minecraft.tags.Tag
+ net.minecraft.tags.Tag$Builder
- net.minecraft.tags.Tag$BuilderEntry
+ net.minecraft.tags.Tag$ElementEntry
- net.minecraft.tags.Tag$Entry
+ net.minecraft.tags.Tag$Named
- net.minecraft.tags.Tag$OptionalElementEntry
+ net.minecraft.tags.Tag$OptionalTagEntry
- net.minecraft.tags.Tag$TagEntry
+ net.minecraft.tags.TagCollection
- net.minecraft.tags.TagCollection$1
+ net.minecraft.tags.TagCollection$NetworkPayload
- net.minecraft.tags.TagContainer
+ net.minecraft.tags.TagContainer$1
- net.minecraft.tags.TagContainer$Builder
+ net.minecraft.tags.TagContainer$CollectionConsumer
- net.minecraft.tags.TagLoader
+ net.minecraft.tags.TagManager
- net.minecraft.tags.TagManager$LoaderInfo
- net.minecraft.util.BitStorage
+ net.minecraft.util.ClassInstanceMultiMap
- net.minecraft.util.CrudeIncrementalIntIdentityHashBiMap
+ net.minecraft.util.Crypt
- net.minecraft.util.CryptException
+ net.minecraft.util.CsvOutput
- net.minecraft.util.CsvOutput$Builder
+ net.minecraft.util.CubicSampler
- net.minecraft.util.CubicSampler$Vec3Fetcher
+ net.minecraft.util.CubicSpline
- net.minecraft.util.CubicSpline$Builder
+ net.minecraft.util.CubicSpline$Constant
- net.minecraft.util.datafix.DataFixers
+ net.minecraft.util.datafix.DataFixers$1
- net.minecraft.util.datafix.DataFixers$2
+ net.minecraft.util.datafix.DataFixTypes
- net.minecraft.util.datafix.fixes.AbstractArrowPickupFix
+ net.minecraft.util.datafix.fixes.AbstractUUIDFix
- net.minecraft.util.datafix.fixes.AddFlagIfNotPresentFix
+ net.minecraft.util.datafix.fixes.AddNewChoices
- net.minecraft.util.datafix.fixes.AdvancementsFix
+ net.minecraft.util.datafix.fixes.AdvancementsRenameFix
- net.minecraft.util.datafix.fixes.AttributesRename
+ net.minecraft.util.datafix.fixes.BedBlockEntityInjecter
- net.minecraft.util.datafix.fixes.BedItemColorFix
+ net.minecraft.util.datafix.fixes.BeehivePoiRenameFix
- net.minecraft.util.datafix.fixes.BiomeFix
+ net.minecraft.util.datafix.fixes.BitStorageAlignFix
- net.minecraft.util.datafix.fixes.BlockEntityBannerColorFix
+ net.minecraft.util.datafix.fixes.BlockEntityBlockStateFix
- net.minecraft.util.datafix.fixes.BlockEntityCustomNameToComponentFix
+ net.minecraft.util.datafix.fixes.BlockEntityIdFix
- net.minecraft.util.datafix.fixes.BlockEntityJukeboxFix
+ net.minecraft.util.datafix.fixes.BlockEntityKeepPacked
- net.minecraft.util.datafix.fixes.BlockEntityShulkerBoxColorFix
+ net.minecraft.util.datafix.fixes.BlockEntitySignTextStrictJsonFix
- net.minecraft.util.datafix.fixes.BlockEntitySignTextStrictJsonFix$1
+ net.minecraft.util.datafix.fixes.BlockEntityUUIDFix
- net.minecraft.util.datafix.fixes.BlockNameFlatteningFix
+ net.minecraft.util.datafix.fixes.BlockRenameFix
- net.minecraft.util.datafix.fixes.BlockRenameFix$1
+ net.minecraft.util.datafix.fixes.BlockRenameFixWithJigsaw
- net.minecraft.util.datafix.fixes.BlockRenameFixWithJigsaw$1
+ net.minecraft.util.datafix.fixes.BlockStateData
- net.minecraft.util.datafix.fixes.BlockStateStructureTemplateFix
+ net.minecraft.util.datafix.fixes.CatTypeFix
- net.minecraft.util.datafix.fixes.CauldronRenameFix
+ net.minecraft.util.datafix.PackedBitStorage
- net.minecraft.util.DebugBuffer
+ net.minecraft.util.DirectoryLock
- net.minecraft.util.DirectoryLock$LockException
+ net.minecraft.util.ExceptionCollector
- net.minecraft.util.ExtraCodecs
+ net.minecraft.util.ExtraCodecs$EitherCodec
- net.minecraft.util.ExtraCodecs$XorCodec
+ net.minecraft.util.FastColor
- net.minecraft.util.FastColor$ARGB32
+ net.minecraft.util.FileZipper
- net.minecraft.util.FormattedCharSequence
+ net.minecraft.util.FormattedCharSink
- net.minecraft.util.FrameTimer
+ net.minecraft.util.Graph
- net.minecraft.util.GsonHelper
+ net.minecraft.util.HttpUtil
- net.minecraft.util.InclusiveRange
+ net.minecraft.util.LazyLoadedValue
- net.minecraft.util.LinearCongruentialGenerator
+ net.minecraft.util.LowerCaseEnumTypeAdapterFactory
- net.minecraft.util.LowerCaseEnumTypeAdapterFactory$1
+ net.minecraft.util.MemoryReserve
- net.minecraft.util.Mth
+ net.minecraft.util.NativeModuleLister
- net.minecraft.util.NativeModuleLister$NativeModuleInfo
+ net.minecraft.util.NativeModuleLister$NativeModuleVersion
- net.minecraft.util.ParticleUtils
+ net.minecraft.util.ProgressListener
- net.minecraft.util.RewindableStream
+ net.minecraft.util.RewindableStream$1
- net.minecraft.util.SimpleBitStorage
+ net.minecraft.util.SmoothDouble
- net.minecraft.util.SortedArraySet
+ net.minecraft.util.SortedArraySet$ArrayIterator
- net.minecraft.util.StringDecomposer
+ net.minecraft.util.StringRepresentable
- net.minecraft.util.StringRepresentable$1
+ net.minecraft.util.StringRepresentable$2
- net.minecraft.util.StringUtil
+ net.minecraft.util.TelemetryConstants
- net.minecraft.util.ThreadingDetector
+ net.minecraft.util.TimeUtil
- net.minecraft.util.ToFloatFunction
+ net.minecraft.util.Tuple
- net.minecraft.util.Unit
+ net.minecraft.util.VisibleForDebug
- net.minecraft.util.ZeroBitStorage
+ net.minecraft.world.entity.ai.memory.package-info
- net.minecraft.world.entity.ai.memory.WalkTarget
- net.minecraft.world.entity.ai.navigation.FlyingPathNavigation
+ net.minecraft.world.entity.ai.navigation.GroundPathNavigation
+ net.minecraft.world.entity.ai.navigation.package-info
- net.minecraft.world.entity.ai.navigation.PathNavigation
+ net.minecraft.world.entity.ai.navigation.WallClimberNavigation
- net.minecraft.world.entity.ai.navigation.WaterBoundPathNavigation
- net.minecraft.world.entity.ai.package-info
+ net.minecraft.world.entity.ai.sensing.AdultSensor
- net.minecraft.world.entity.ai.sensing.AxolotlAttackablesSensor
+ net.minecraft.world.entity.ai.sensing.DummySensor
- net.minecraft.world.entity.ai.sensing.GolemSensor
+ net.minecraft.world.entity.ai.sensing.HoglinSpecificSensor
- net.minecraft.world.entity.ai.sensing.HurtBySensor
+ net.minecraft.world.entity.ai.sensing.NearestBedSensor
- net.minecraft.world.entity.ai.sensing.NearestItemSensor
+ net.minecraft.world.entity.ai.sensing.NearestLivingEntitySensor
- net.minecraft.world.entity.ai.sensing.NearestVisibleLivingEntitySensor
+ net.minecraft.world.entity.ai.sensing.package-info
+ net.minecraft.world.entity.ai.sensing.PiglinBruteSpecificSensor
- net.minecraft.world.entity.ai.sensing.PiglinSpecificSensor
+ net.minecraft.world.entity.ai.sensing.PlayerSensor
- net.minecraft.world.entity.ai.sensing.SecondaryPoiSensor
+ net.minecraft.world.entity.ai.sensing.Sensing
- net.minecraft.world.entity.ai.sensing.Sensor
+ net.minecraft.world.entity.ai.sensing.SensorType
- net.minecraft.world.entity.ai.sensing.TemptingSensor
+ net.minecraft.world.entity.ai.sensing.VillagerBabiesSensor
- net.minecraft.world.entity.ai.sensing.VillagerHostilesSensor
+ net.minecraft.world.entity.ai.targeting.package-info
- net.minecraft.world.entity.ai.targeting.TargetingConditions
- net.minecraft.world.entity.ai.util.AirAndWaterRandomPos
+ net.minecraft.world.entity.ai.util.AirRandomPos
- net.minecraft.world.entity.ai.util.DefaultRandomPos
+ net.minecraft.world.entity.ai.util.GoalUtils
- net.minecraft.world.entity.ai.util.HoverRandomPos
+ net.minecraft.world.entity.ai.util.LandRandomPos
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
- net.minecraft.world.entity.animal.axolotl.Axolotl
+ net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlGroupData
- net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlLookControl
+ net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlMoveControl
- net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlPathNavigation
+ net.minecraft.world.entity.animal.axolotl.Axolotl$Variant
- net.minecraft.world.entity.animal.axolotl.AxolotlAi
+ net.minecraft.world.entity.animal.axolotl.package-info
+ net.minecraft.world.entity.animal.axolotl.PlayDead
- net.minecraft.world.entity.animal.axolotl.ValidatePlayDead
- net.minecraft.world.entity.animal.Bee
+ net.minecraft.world.entity.animal.Bee$1
- net.minecraft.world.entity.animal.Bee$BaseBeeGoal
+ net.minecraft.world.entity.animal.Bee$BeeAttackGoal
- net.minecraft.world.entity.animal.Bee$BeeBecomeAngryTargetGoal
+ net.minecraft.world.entity.animal.Bee$BeeEnterHiveGoal
- net.minecraft.world.entity.animal.Bee$BeeGoToHiveGoal
+ net.minecraft.world.entity.animal.Bee$BeeGoToKnownFlowerGoal
- net.minecraft.world.entity.animal.Bee$BeeGrowCropGoal
+ net.minecraft.world.entity.animal.Bee$BeeHurtByOtherGoal
- net.minecraft.world.entity.animal.Bee$BeeLocateHiveGoal
+ net.minecraft.world.entity.animal.Bee$BeeLookControl
- net.minecraft.world.entity.animal.Bee$BeePollinateGoal
+ net.minecraft.world.entity.animal.Bee$BeeWanderGoal
- net.minecraft.world.entity.animal.Bucketable
+ net.minecraft.world.entity.animal.Cat
- net.minecraft.world.entity.animal.Cat$CatAvoidEntityGoal
+ net.minecraft.world.entity.animal.Cat$CatRelaxOnOwnerGoal
- net.minecraft.world.entity.animal.Cat$CatTemptGoal
+ net.minecraft.world.entity.animal.Chicken
- net.minecraft.world.entity.animal.Cod
+ net.minecraft.world.entity.animal.Cow
- net.minecraft.world.entity.animal.Dolphin
+ net.minecraft.world.entity.animal.Dolphin$DolphinSwimToTreasureGoal
- net.minecraft.world.entity.animal.Dolphin$DolphinSwimWithPlayerGoal
+ net.minecraft.world.entity.animal.Dolphin$PlayWithItemsGoal
- net.minecraft.world.entity.animal.FlyingAnimal
+ net.minecraft.world.entity.animal.Fox
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
- net.minecraft.world.entity.animal.goat.Goat
+ net.minecraft.world.entity.animal.goat.Goat$GoatNodeEvaluator
- net.minecraft.world.entity.animal.goat.Goat$GoatPathNavigation
+ net.minecraft.world.entity.animal.goat.GoatAi
- net.minecraft.world.entity.animal.goat.package-info
+ net.minecraft.world.entity.animal.horse.AbstractChestedHorse
- net.minecraft.world.entity.animal.horse.AbstractChestedHorse$1
+ net.minecraft.world.entity.animal.horse.AbstractHorse
- net.minecraft.world.entity.animal.horse.AbstractHorse$1
+ net.minecraft.world.entity.animal.horse.Donkey
- net.minecraft.world.entity.animal.horse.Horse
+ net.minecraft.world.entity.animal.horse.Horse$HorseGroupData
- net.minecraft.world.entity.animal.horse.Llama
+ net.minecraft.world.entity.animal.horse.Llama$LlamaAttackWolfGoal
- net.minecraft.world.entity.animal.horse.Llama$LlamaGroupData
+ net.minecraft.world.entity.animal.horse.Llama$LlamaHurtByTargetGoal
- net.minecraft.world.entity.animal.horse.Markings
+ net.minecraft.world.entity.animal.horse.Mule
- net.minecraft.world.entity.animal.horse.package-info
- net.minecraft.world.entity.animal.horse.SkeletonHorse
+ net.minecraft.world.entity.animal.horse.SkeletonTrapGoal
- net.minecraft.world.entity.animal.horse.TraderLlama
+ net.minecraft.world.entity.animal.horse.TraderLlama$TraderLlamaDefendWanderingTraderGoal
- net.minecraft.world.entity.animal.horse.Variant
+ net.minecraft.world.entity.animal.horse.ZombieHorse
- net.minecraft.world.entity.animal.IronGolem
+ net.minecraft.world.entity.animal.IronGolem$Crackiness
- net.minecraft.world.entity.animal.MushroomCow
+ net.minecraft.world.entity.animal.MushroomCow$MushroomType
- net.minecraft.world.entity.animal.Ocelot
+ net.minecraft.world.entity.animal.Ocelot$OcelotAvoidEntityGoal
- net.minecraft.world.entity.animal.Ocelot$OcelotTemptGoal
+ net.minecraft.world.entity.animal.package-info
+ net.minecraft.world.entity.animal.Panda
- net.minecraft.world.entity.animal.Panda$Gene
+ net.minecraft.world.entity.animal.Panda$PandaAttackGoal
- net.minecraft.world.entity.animal.Panda$PandaAvoidGoal
+ net.minecraft.world.entity.animal.Panda$PandaBreedGoal
- net.minecraft.world.entity.animal.Panda$PandaHurtByTargetGoal
+ net.minecraft.world.entity.animal.Panda$PandaLieOnBackGoal
- net.minecraft.world.entity.animal.Panda$PandaLookAtPlayerGoal
+ net.minecraft.world.entity.animal.Panda$PandaMoveControl
- net.minecraft.world.entity.animal.Panda$PandaPanicGoal
+ net.minecraft.world.entity.animal.Panda$PandaRollGoal
- net.minecraft.world.entity.animal.Panda$PandaSitGoal
+ net.minecraft.world.entity.animal.Panda$PandaSneezeGoal
- net.minecraft.world.entity.animal.Parrot
+ net.minecraft.world.entity.animal.Parrot$1
- net.minecraft.world.entity.animal.Parrot$ParrotWanderGoal
+ net.minecraft.world.entity.animal.Pig
- net.minecraft.world.entity.animal.PolarBear
+ net.minecraft.world.entity.animal.PolarBear$PolarBearAttackPlayersGoal
- net.minecraft.world.entity.animal.PolarBear$PolarBearHurtByTargetGoal
+ net.minecraft.world.entity.animal.PolarBear$PolarBearMeleeAttackGoal
- net.minecraft.world.entity.animal.PolarBear$PolarBearPanicGoal
+ net.minecraft.world.entity.animal.Pufferfish
- net.minecraft.world.entity.animal.Pufferfish$PufferfishPuffGoal
+ net.minecraft.world.entity.animal.Rabbit
- net.minecraft.world.entity.animal.Rabbit$EvilRabbitAttackGoal
+ net.minecraft.world.entity.animal.Rabbit$RabbitAvoidEntityGoal
- net.minecraft.world.entity.animal.Rabbit$RabbitGroupData
+ net.minecraft.world.entity.animal.Rabbit$RabbitJumpControl
- net.minecraft.world.entity.animal.Rabbit$RabbitMoveControl
+ net.minecraft.world.entity.animal.Rabbit$RabbitPanicGoal
- net.minecraft.world.entity.animal.Rabbit$RaidGardenGoal
+ net.minecraft.world.entity.animal.Salmon
- net.minecraft.world.entity.animal.Sheep
+ net.minecraft.world.entity.animal.Sheep$1
- net.minecraft.world.entity.animal.Sheep$2
+ net.minecraft.world.entity.animal.ShoulderRidingEntity
- net.minecraft.world.entity.animal.SnowGolem
+ net.minecraft.world.entity.animal.Squid
- net.minecraft.world.entity.animal.Squid$SquidFleeGoal
+ net.minecraft.world.entity.animal.Squid$SquidRandomMovementGoal
- net.minecraft.world.entity.animal.TropicalFish
+ net.minecraft.world.entity.animal.TropicalFish$Pattern
- net.minecraft.world.entity.animal.TropicalFish$TropicalFishGroupData
+ net.minecraft.world.entity.animal.Turtle
- net.minecraft.world.entity.animal.Turtle$TurtleBreedGoal
+ net.minecraft.world.entity.animal.Turtle$TurtleGoHomeGoal
- net.minecraft.world.entity.animal.Turtle$TurtleGoToWaterGoal
+ net.minecraft.world.entity.animal.Turtle$TurtleLayEggGoal
- net.minecraft.world.entity.animal.Turtle$TurtleMoveControl
+ net.minecraft.world.entity.animal.Turtle$TurtlePanicGoal
- net.minecraft.world.entity.animal.Turtle$TurtlePathNavigation
+ net.minecraft.world.entity.animal.Turtle$TurtleRandomStrollGoal
- net.minecraft.world.entity.animal.Turtle$TurtleTravelGoal
+ net.minecraft.world.entity.animal.WaterAnimal
- net.minecraft.world.entity.animal.Wolf
+ net.minecraft.world.entity.animal.Wolf$WolfAvoidEntityGoal
+ net.minecraft.world.entity.boss.enderdragon.EndCrystal
- net.minecraft.world.entity.boss.enderdragon.EnderDragon
+ net.minecraft.world.entity.boss.enderdragon.package-info
- net.minecraft.world.entity.boss.enderdragon.phases.AbstractDragonPhaseInstance
+ net.minecraft.world.entity.boss.enderdragon.phases.AbstractDragonSittingPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonChargePlayerPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonDeathPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonHoldingPatternPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonHoverPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonLandingApproachPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonLandingPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonPhaseInstance
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonSittingAttackingPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonSittingFlamingPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonSittingScanningPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonStrafePlayerPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonTakeoffPhase
- net.minecraft.world.entity.boss.enderdragon.phases.EnderDragonPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.EnderDragonPhaseManager
- net.minecraft.world.entity.boss.enderdragon.phases.package-info
- net.minecraft.world.entity.boss.EnderDragonPart
+ net.minecraft.world.entity.boss.package-info
- net.minecraft.world.entity.boss.wither.package-info
- net.minecraft.world.entity.boss.wither.WitherBoss
+ net.minecraft.world.entity.boss.wither.WitherBoss$WitherDoNothingGoal
+ net.minecraft.world.entity.decoration.ArmorStand
- net.minecraft.world.entity.decoration.ArmorStand$1
+ net.minecraft.world.entity.decoration.GlowItemFrame
- net.minecraft.world.entity.decoration.HangingEntity
+ net.minecraft.world.entity.decoration.HangingEntity$1
- net.minecraft.world.entity.decoration.ItemFrame
+ net.minecraft.world.entity.decoration.ItemFrame$1
- net.minecraft.world.entity.decoration.ItemFrame$2
+ net.minecraft.world.entity.decoration.LeashFenceKnotEntity
- net.minecraft.world.entity.decoration.Motive
- net.minecraft.world.entity.decoration.package-info
+ net.minecraft.world.entity.decoration.Painting
+ net.minecraft.world.entity.item.FallingBlockEntity
- net.minecraft.world.entity.item.ItemEntity
- net.minecraft.world.entity.item.package-info
+ net.minecraft.world.entity.item.PrimedTnt
+ net.minecraft.world.entity.monster.AbstractIllager
- net.minecraft.world.entity.monster.AbstractIllager$IllagerArmPose
+ net.minecraft.world.entity.monster.AbstractIllager$RaiderOpenDoorGoal
- net.minecraft.world.entity.monster.AbstractSkeleton
+ net.minecraft.world.entity.monster.AbstractSkeleton$1
- net.minecraft.world.entity.monster.Blaze
+ net.minecraft.world.entity.monster.Blaze$BlazeAttackGoal
- net.minecraft.world.entity.monster.CaveSpider
+ net.minecraft.world.entity.monster.Creeper
- net.minecraft.world.entity.monster.CrossbowAttackMob
+ net.minecraft.world.entity.monster.Drowned
- net.minecraft.world.entity.monster.Drowned$DrownedAttackGoal
+ net.minecraft.world.entity.monster.Drowned$DrownedGoToBeachGoal
- net.minecraft.world.entity.monster.Drowned$DrownedGoToWaterGoal
+ net.minecraft.world.entity.monster.Drowned$DrownedMoveControl
- net.minecraft.world.entity.monster.Drowned$DrownedSwimUpGoal
+ net.minecraft.world.entity.monster.Drowned$DrownedTridentAttackGoal
- net.minecraft.world.entity.monster.ElderGuardian
+ net.minecraft.world.entity.monster.EnderMan
- net.minecraft.world.entity.monster.EnderMan$EndermanFreezeWhenLookedAt
+ net.minecraft.world.entity.monster.EnderMan$EndermanLeaveBlockGoal
- net.minecraft.world.entity.monster.EnderMan$EndermanLookForPlayerGoal
+ net.minecraft.world.entity.monster.EnderMan$EndermanTakeBlockGoal
- net.minecraft.world.entity.monster.Endermite
+ net.minecraft.world.entity.monster.Enemy
- net.minecraft.world.entity.monster.Evoker
+ net.minecraft.world.entity.monster.Evoker$EvokerAttackSpellGoal
- net.minecraft.world.entity.monster.Evoker$EvokerCastingSpellGoal
+ net.minecraft.world.entity.monster.Evoker$EvokerSummonSpellGoal
- net.minecraft.world.entity.monster.Evoker$EvokerWololoSpellGoal
+ net.minecraft.world.entity.monster.Ghast
- net.minecraft.world.entity.monster.Ghast$GhastLookGoal
+ net.minecraft.world.entity.monster.Ghast$GhastMoveControl
- net.minecraft.world.entity.monster.Ghast$GhastShootFireballGoal
+ net.minecraft.world.entity.monster.Ghast$RandomFloatAroundGoal
- net.minecraft.world.entity.monster.Giant
+ net.minecraft.world.entity.monster.Guardian
- net.minecraft.world.entity.monster.Guardian$GuardianAttackGoal
+ net.minecraft.world.entity.monster.Guardian$GuardianAttackSelector
- net.minecraft.world.entity.monster.Guardian$GuardianMoveControl
+ net.minecraft.world.entity.monster.hoglin.Hoglin
- net.minecraft.world.entity.monster.hoglin.HoglinAi
+ net.minecraft.world.entity.monster.hoglin.HoglinBase
- net.minecraft.world.entity.monster.hoglin.package-info
+ net.minecraft.world.entity.monster.Husk
- net.minecraft.world.entity.monster.Illusioner
+ net.minecraft.world.entity.monster.Illusioner$IllusionerBlindnessSpellGoal
- net.minecraft.world.entity.monster.Illusioner$IllusionerMirrorSpellGoal
+ net.minecraft.world.entity.monster.MagmaCube
- net.minecraft.world.entity.monster.Monster
+ net.minecraft.world.entity.monster.package-info
+ net.minecraft.world.entity.monster.PatrollingMonster
- net.minecraft.world.entity.monster.PatrollingMonster$LongDistancePatrolGoal
+ net.minecraft.world.entity.monster.Phantom
- net.minecraft.world.entity.monster.Phantom$AttackPhase
+ net.minecraft.world.entity.monster.Phantom$PhantomAttackPlayerTargetGoal
- net.minecraft.world.entity.monster.Phantom$PhantomAttackStrategyGoal
+ net.minecraft.world.entity.monster.Phantom$PhantomBodyRotationControl
- net.minecraft.world.entity.monster.Phantom$PhantomCircleAroundAnchorGoal
+ net.minecraft.world.entity.monster.Phantom$PhantomLookControl
- net.minecraft.world.entity.monster.Phantom$PhantomMoveControl
+ net.minecraft.world.entity.monster.Phantom$PhantomMoveTargetGoal
- net.minecraft.world.entity.monster.Phantom$PhantomSweepAttackGoal
- net.minecraft.world.entity.monster.piglin.AbstractPiglin
- net.minecraft.world.entity.monster.piglin.package-info
+ net.minecraft.world.entity.monster.piglin.Piglin
- net.minecraft.world.entity.monster.piglin.PiglinAi
+ net.minecraft.world.entity.monster.piglin.PiglinArmPose
- net.minecraft.world.entity.monster.piglin.PiglinBrute
+ net.minecraft.world.entity.monster.piglin.PiglinBruteAi
- net.minecraft.world.entity.monster.piglin.RememberIfHoglinWasKilled
+ net.minecraft.world.entity.monster.piglin.StartAdmiringItemIfSeen
- net.minecraft.world.entity.monster.piglin.StartHuntingHoglin
+ net.minecraft.world.entity.monster.piglin.StopAdmiringIfItemTooFarAway
- net.minecraft.world.entity.monster.piglin.StopAdmiringIfTiredOfTryingToReachItem
+ net.minecraft.world.entity.monster.piglin.StopHoldingItemIfNoLongerAdmiring
+ net.minecraft.world.entity.monster.Pillager
- net.minecraft.world.entity.monster.RangedAttackMob
+ net.minecraft.world.entity.monster.Ravager
- net.minecraft.world.entity.monster.Ravager$RavagerMeleeAttackGoal
+ net.minecraft.world.entity.monster.Ravager$RavagerNavigation
- net.minecraft.world.entity.monster.Ravager$RavagerNodeEvaluator
+ net.minecraft.world.entity.monster.Shulker
- net.minecraft.world.entity.monster.Shulker$ShulkerAttackGoal
+ net.minecraft.world.entity.monster.Shulker$ShulkerBodyRotationControl
- net.minecraft.world.entity.monster.Shulker$ShulkerDefenseAttackGoal
+ net.minecraft.world.entity.monster.Shulker$ShulkerLookControl
- net.minecraft.world.entity.monster.Shulker$ShulkerNearestAttackGoal
+ net.minecraft.world.entity.monster.Shulker$ShulkerPeekGoal
- net.minecraft.world.entity.monster.Silverfish
+ net.minecraft.world.entity.monster.Silverfish$SilverfishMergeWithStoneGoal
- net.minecraft.world.entity.monster.Silverfish$SilverfishWakeUpFriendsGoal
+ net.minecraft.world.entity.monster.Skeleton
- net.minecraft.world.entity.monster.Slime
+ net.minecraft.world.entity.monster.Slime$SlimeAttackGoal
- net.minecraft.world.entity.monster.Slime$SlimeFloatGoal
+ net.minecraft.world.entity.monster.Slime$SlimeKeepOnJumpingGoal
- net.minecraft.world.entity.monster.Slime$SlimeMoveControl
+ net.minecraft.world.entity.monster.Slime$SlimeRandomDirectionGoal
- net.minecraft.world.entity.monster.SpellcasterIllager
+ net.minecraft.world.entity.monster.SpellcasterIllager$IllagerSpell
- net.minecraft.world.entity.monster.SpellcasterIllager$SpellcasterCastingSpellGoal
+ net.minecraft.world.entity.monster.SpellcasterIllager$SpellcasterUseSpellGoal
- net.minecraft.world.entity.monster.Spider
+ net.minecraft.world.entity.monster.Spider$SpiderAttackGoal
- net.minecraft.world.entity.monster.Spider$SpiderEffectsGroupData
+ net.minecraft.world.entity.monster.Spider$SpiderTargetGoal
- net.minecraft.world.entity.monster.Stray
+ net.minecraft.world.entity.monster.Strider
- net.minecraft.world.entity.monster.Strider$StriderGoToLavaGoal
+ net.minecraft.world.entity.monster.Strider$StriderPathNavigation
- net.minecraft.world.entity.monster.Vex
+ net.minecraft.world.entity.monster.Vex$VexChargeAttackGoal
- net.minecraft.world.entity.monster.Vex$VexCopyOwnerTargetGoal
+ net.minecraft.world.entity.monster.Vex$VexMoveControl
- net.minecraft.world.entity.monster.Vex$VexRandomMoveGoal
+ net.minecraft.world.entity.monster.Vindicator
- net.minecraft.world.entity.monster.Vindicator$VindicatorBreakDoorGoal
+ net.minecraft.world.entity.monster.Vindicator$VindicatorJohnnyAttackGoal
- net.minecraft.world.entity.monster.Vindicator$VindicatorMeleeAttackGoal
+ net.minecraft.world.entity.monster.Witch
- net.minecraft.world.entity.monster.WitherSkeleton
+ net.minecraft.world.entity.monster.Zoglin
- net.minecraft.world.entity.monster.Zombie
+ net.minecraft.world.entity.monster.Zombie$ZombieAttackTurtleEggGoal
- net.minecraft.world.entity.monster.Zombie$ZombieGroupData
+ net.minecraft.world.entity.monster.ZombieVillager
- net.minecraft.world.entity.monster.ZombifiedPiglin
+ net.minecraft.world.entity.npc.AbstractVillager
- net.minecraft.world.entity.npc.CatSpawner
+ net.minecraft.world.entity.npc.ClientSideMerchant
- net.minecraft.world.entity.npc.InventoryCarrier
+ net.minecraft.world.entity.npc.Npc
- net.minecraft.world.entity.npc.package-info
- net.minecraft.world.entity.npc.Villager
+ net.minecraft.world.entity.npc.VillagerData
- net.minecraft.world.entity.npc.VillagerDataHolder
+ net.minecraft.world.entity.npc.VillagerProfession
- net.minecraft.world.entity.npc.VillagerTrades
+ net.minecraft.world.entity.npc.VillagerTrades$DyedArmorForEmeralds
- net.minecraft.world.entity.npc.VillagerTrades$EmeraldForItems
+ net.minecraft.world.entity.npc.VillagerTrades$EmeraldsForVillagerTypeItem
- net.minecraft.world.entity.npc.VillagerTrades$EnchantBookForEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$EnchantedItemForEmeralds
- net.minecraft.world.entity.npc.VillagerTrades$ItemListing
+ net.minecraft.world.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
- net.minecraft.world.entity.npc.VillagerTrades$ItemsForEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$SuspiciousStewForEmerald
- net.minecraft.world.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$TreasureMapForEmeralds
- net.minecraft.world.entity.npc.VillagerType
+ net.minecraft.world.entity.npc.WanderingTrader
- net.minecraft.world.entity.npc.WanderingTrader$WanderToPositionGoal
+ net.minecraft.world.entity.npc.WanderingTraderSpawner
+ net.minecraft.world.entity.package-info
- net.minecraft.world.entity.player.Abilities
+ net.minecraft.world.entity.player.ChatVisiblity
- net.minecraft.world.entity.player.Inventory
+ net.minecraft.world.entity.player.package-info
+ net.minecraft.world.entity.player.Player
- net.minecraft.world.entity.player.Player$1
+ net.minecraft.world.entity.player.Player$BedSleepingProblem
- net.minecraft.world.entity.player.PlayerModelPart
+ net.minecraft.world.entity.player.StackedContents
- net.minecraft.world.entity.player.StackedContents$RecipePicker
- net.minecraft.world.entity.projectile.AbstractArrow
+ net.minecraft.world.entity.projectile.AbstractArrow$1
- net.minecraft.world.entity.projectile.AbstractArrow$Pickup
+ net.minecraft.world.entity.projectile.AbstractHurtingProjectile
- net.minecraft.world.entity.projectile.Arrow
+ net.minecraft.world.entity.projectile.DragonFireball
- net.minecraft.world.entity.projectile.EvokerFangs
+ net.minecraft.world.entity.projectile.EyeOfEnder
- net.minecraft.world.entity.projectile.Fireball
+ net.minecraft.world.entity.projectile.FireworkRocketEntity
- net.minecraft.world.entity.projectile.FishingHook
+ net.minecraft.world.entity.projectile.FishingHook$1
- net.minecraft.world.entity.projectile.FishingHook$FishHookState
+ net.minecraft.world.entity.projectile.FishingHook$OpenWaterType
- net.minecraft.world.entity.projectile.ItemSupplier
+ net.minecraft.world.entity.projectile.LargeFireball
- net.minecraft.world.entity.projectile.LlamaSpit
+ net.minecraft.world.entity.projectile.package-info
+ net.minecraft.world.entity.projectile.Projectile
- net.minecraft.world.entity.projectile.ProjectileUtil
+ net.minecraft.world.entity.projectile.ShulkerBullet
- net.minecraft.world.entity.projectile.SmallFireball
+ net.minecraft.world.entity.projectile.Snowball
- net.minecraft.world.entity.projectile.SpectralArrow
+ net.minecraft.world.entity.projectile.ThrowableItemProjectile
- net.minecraft.world.entity.projectile.ThrowableProjectile
+ net.minecraft.world.entity.projectile.ThrownEgg
- net.minecraft.world.entity.projectile.ThrownEnderpearl
+ net.minecraft.world.entity.projectile.ThrownExperienceBottle
- net.minecraft.world.entity.projectile.ThrownPotion
+ net.minecraft.world.entity.projectile.ThrownTrident
- net.minecraft.world.entity.projectile.WitherSkull
- net.minecraft.world.entity.raid.package-info
- net.minecraft.world.entity.raid.Raid
+ net.minecraft.world.entity.raid.Raid$1
+ net.minecraft.world.entity.raid.Raid$RaiderType
- net.minecraft.world.entity.raid.Raid$RaidStatus
- net.minecraft.world.entity.raid.Raider
+ net.minecraft.world.entity.raid.Raider$HoldGroundAttackGoal
- net.minecraft.world.entity.raid.Raider$ObtainRaidLeaderBannerGoal
+ net.minecraft.world.entity.raid.Raider$RaiderCelebration
- net.minecraft.world.entity.raid.Raider$RaiderMoveThroughVillageGoal
+ net.minecraft.world.entity.raid.Raids
+ net.minecraft.world.entity.schedule.Activity
- net.minecraft.world.entity.schedule.Keyframe
+ net.minecraft.world.entity.schedule.package-info
+ net.minecraft.world.entity.schedule.Schedule
- net.minecraft.world.entity.schedule.ScheduleBuilder
+ net.minecraft.world.entity.schedule.ScheduleBuilder$ActivityTransition
- net.minecraft.world.entity.schedule.Timeline
- net.minecraft.world.entity.vehicle.AbstractMinecart
+ net.minecraft.world.entity.vehicle.AbstractMinecart$1
- net.minecraft.world.entity.vehicle.AbstractMinecart$Type
+ net.minecraft.world.entity.vehicle.AbstractMinecartContainer
- net.minecraft.world.entity.vehicle.AbstractMinecartContainer$1
+ net.minecraft.world.entity.vehicle.Boat
- net.minecraft.world.entity.vehicle.Boat$1
+ net.minecraft.world.entity.vehicle.Boat$Status
- net.minecraft.world.entity.vehicle.Boat$Type
+ net.minecraft.world.entity.vehicle.DismountHelper
- net.minecraft.world.entity.vehicle.Minecart
+ net.minecraft.world.entity.vehicle.MinecartChest
- net.minecraft.world.entity.vehicle.MinecartCommandBlock
+ net.minecraft.world.entity.vehicle.MinecartCommandBlock$MinecartCommandBase
- net.minecraft.world.entity.vehicle.MinecartFurnace
+ net.minecraft.world.entity.vehicle.MinecartHopper
- net.minecraft.world.entity.vehicle.MinecartSpawner
+ net.minecraft.world.entity.vehicle.MinecartSpawner$1
- net.minecraft.world.entity.vehicle.MinecartTNT
+ net.minecraft.world.entity.vehicle.package-info
- net.minecraft.world.food.FoodConstants
+ net.minecraft.world.food.FoodData
- net.minecraft.world.food.FoodProperties
+ net.minecraft.world.food.FoodProperties$Builder
- net.minecraft.world.food.Foods
+ net.minecraft.world.food.package-info
- net.minecraft.world.inventory.AbstractContainerMenu
+ net.minecraft.world.inventory.AbstractContainerMenu$1
- net.minecraft.world.inventory.AbstractFurnaceMenu
+ net.minecraft.world.inventory.AnvilMenu
- net.minecraft.world.inventory.AnvilMenu$1
+ net.minecraft.world.inventory.BeaconMenu
- net.minecraft.world.inventory.BeaconMenu$1
+ net.minecraft.world.inventory.BeaconMenu$PaymentSlot
- net.minecraft.world.inventory.BlastFurnaceMenu
+ net.minecraft.world.inventory.BrewingStandMenu
- net.minecraft.world.inventory.BrewingStandMenu$FuelSlot
+ net.minecraft.world.inventory.BrewingStandMenu$IngredientsSlot
- net.minecraft.world.inventory.BrewingStandMenu$PotionSlot
+ net.minecraft.world.inventory.CartographyTableMenu
- net.minecraft.world.inventory.CartographyTableMenu$1
+ net.minecraft.world.inventory.CartographyTableMenu$2
- net.minecraft.world.inventory.CartographyTableMenu$3
+ net.minecraft.world.inventory.CartographyTableMenu$4
- net.minecraft.world.inventory.CartographyTableMenu$5
+ net.minecraft.world.inventory.ChestMenu
- net.minecraft.world.inventory.ClickAction
+ net.minecraft.world.inventory.ClickType
- net.minecraft.world.inventory.ContainerData
+ net.minecraft.world.inventory.ContainerLevelAccess
- net.minecraft.world.inventory.ContainerLevelAccess$1
+ net.minecraft.world.inventory.ContainerLevelAccess$2
- net.minecraft.world.inventory.ContainerListener
+ net.minecraft.world.inventory.ContainerSynchronizer
- net.minecraft.world.inventory.CraftingContainer
+ net.minecraft.world.inventory.CraftingMenu
- net.minecraft.world.inventory.DataSlot
+ net.minecraft.world.inventory.DataSlot$1
- net.minecraft.world.inventory.DataSlot$2
+ net.minecraft.world.inventory.DataSlot$3
- net.minecraft.world.inventory.DispenserMenu
+ net.minecraft.world.inventory.EnchantmentMenu
- net.minecraft.world.inventory.EnchantmentMenu$1
+ net.minecraft.world.inventory.EnchantmentMenu$2
- net.minecraft.world.inventory.EnchantmentMenu$3
+ net.minecraft.world.inventory.FurnaceFuelSlot
- net.minecraft.world.inventory.FurnaceMenu
+ net.minecraft.world.inventory.FurnaceResultSlot
- net.minecraft.world.inventory.GrindstoneMenu
+ net.minecraft.world.inventory.GrindstoneMenu$1
- net.minecraft.world.inventory.GrindstoneMenu$2
+ net.minecraft.world.inventory.GrindstoneMenu$3
- net.minecraft.world.inventory.GrindstoneMenu$4
+ net.minecraft.world.inventory.HopperMenu
- net.minecraft.world.inventory.HorseInventoryMenu
+ net.minecraft.world.inventory.HorseInventoryMenu$1
- net.minecraft.world.inventory.HorseInventoryMenu$2
+ net.minecraft.world.inventory.InventoryMenu
- net.minecraft.world.inventory.InventoryMenu$1
+ net.minecraft.world.inventory.InventoryMenu$2
- net.minecraft.world.inventory.ItemCombinerMenu
+ net.minecraft.world.inventory.ItemCombinerMenu$1
- net.minecraft.world.inventory.ItemCombinerMenu$2
+ net.minecraft.world.inventory.LecternMenu
- net.minecraft.world.inventory.LecternMenu$1
+ net.minecraft.world.inventory.LoomMenu
- net.minecraft.world.inventory.LoomMenu$1
+ net.minecraft.world.inventory.LoomMenu$2
- net.minecraft.world.inventory.LoomMenu$3
+ net.minecraft.world.inventory.LoomMenu$4
- net.minecraft.world.inventory.LoomMenu$5
+ net.minecraft.world.inventory.LoomMenu$6
- net.minecraft.world.inventory.MenuConstructor
+ net.minecraft.world.inventory.MenuType
- net.minecraft.world.inventory.MenuType$MenuSupplier
+ net.minecraft.world.inventory.MerchantContainer
- net.minecraft.world.inventory.MerchantMenu
+ net.minecraft.world.inventory.MerchantResultSlot
- net.minecraft.world.inventory.package-info
- net.minecraft.world.inventory.PlayerEnderChestContainer
+ net.minecraft.world.inventory.RecipeBookMenu
- net.minecraft.world.inventory.RecipeBookType
+ net.minecraft.world.inventory.RecipeHolder
- net.minecraft.world.inventory.ResultContainer
+ net.minecraft.world.inventory.ResultSlot
- net.minecraft.world.inventory.ShulkerBoxMenu
+ net.minecraft.world.inventory.ShulkerBoxSlot
- net.minecraft.world.inventory.SimpleContainerData
+ net.minecraft.world.inventory.Slot
- net.minecraft.world.inventory.SmithingMenu
+ net.minecraft.world.inventory.SmokerMenu
- net.minecraft.world.inventory.StackedContentsCompatible
+ net.minecraft.world.inventory.StonecutterMenu
- net.minecraft.world.inventory.StonecutterMenu$1
+ net.minecraft.world.inventory.StonecutterMenu$2
+ net.minecraft.world.inventory.tooltip.BundleTooltip
+ net.minecraft.world.inventory.tooltip.package-info
- net.minecraft.world.inventory.tooltip.TooltipComponent
- net.minecraft.world.item.AdventureModeCheck
+ net.minecraft.world.item.AirItem
+ net.minecraft.world.item.alchemy.package-info
- net.minecraft.world.item.alchemy.Potion
+ net.minecraft.world.item.alchemy.PotionBrewing
- net.minecraft.world.item.alchemy.PotionBrewing$Mix
- net.minecraft.world.item.alchemy.Potions
+ net.minecraft.world.item.alchemy.PotionUtils
- net.minecraft.world.item.ArmorItem
+ net.minecraft.world.item.ArmorItem$1
- net.minecraft.world.item.ArmorMaterial
+ net.minecraft.world.item.ArmorMaterials
- net.minecraft.world.item.ArmorStandItem
+ net.minecraft.world.item.ArrowItem
- net.minecraft.world.item.AxeItem
+ net.minecraft.world.item.BannerItem
- net.minecraft.world.item.BannerPatternItem
+ net.minecraft.world.item.BedItem
- net.minecraft.world.item.BlockItem
+ net.minecraft.world.item.BoatItem
- net.minecraft.world.item.BoneMealItem
+ net.minecraft.world.item.BookItem
- net.minecraft.world.item.BottleItem
+ net.minecraft.world.item.BowItem
- net.minecraft.world.item.BowlFoodItem
+ net.minecraft.world.item.BucketItem
- net.minecraft.world.item.BundleItem
+ net.minecraft.world.item.ChorusFruitItem
- net.minecraft.world.item.CompassItem
+ net.minecraft.world.item.ComplexItem
- net.minecraft.world.item.context.BlockPlaceContext
+ net.minecraft.world.item.context.DirectionalPlaceContext
- net.minecraft.world.item.context.DirectionalPlaceContext$1
- net.minecraft.world.item.context.package-info
+ net.minecraft.world.item.context.UseOnContext
+ net.minecraft.world.item.crafting.AbstractCookingRecipe
- net.minecraft.world.item.crafting.ArmorDyeRecipe
+ net.minecraft.world.item.crafting.BannerDuplicateRecipe
- net.minecraft.world.item.crafting.BlastingRecipe
+ net.minecraft.world.item.crafting.BookCloningRecipe
- net.minecraft.world.item.crafting.CampfireCookingRecipe
+ net.minecraft.world.item.crafting.CraftingRecipe
- net.minecraft.world.item.crafting.CustomRecipe
+ net.minecraft.world.item.crafting.FireworkRocketRecipe
- net.minecraft.world.item.crafting.FireworkStarFadeRecipe
+ net.minecraft.world.item.crafting.FireworkStarRecipe
- net.minecraft.world.item.crafting.Ingredient
+ net.minecraft.world.item.crafting.Ingredient$ItemValue
- net.minecraft.world.item.crafting.Ingredient$TagValue
+ net.minecraft.world.item.crafting.Ingredient$Value
- net.minecraft.world.item.crafting.MapCloningRecipe
+ net.minecraft.world.item.crafting.MapExtendingRecipe
+ net.minecraft.world.item.crafting.package-info
- net.minecraft.world.item.crafting.Recipe
+ net.minecraft.world.item.crafting.RecipeManager
- net.minecraft.world.item.crafting.RecipeSerializer
+ net.minecraft.world.item.crafting.RecipeType
- net.minecraft.world.item.crafting.RecipeType$1
+ net.minecraft.world.item.crafting.RepairItemRecipe
- net.minecraft.world.item.crafting.ShapedRecipe
+ net.minecraft.world.item.crafting.ShapedRecipe$Serializer
- net.minecraft.world.item.crafting.ShapelessRecipe
+ net.minecraft.world.item.crafting.ShapelessRecipe$Serializer
- net.minecraft.world.item.crafting.ShieldDecorationRecipe
+ net.minecraft.world.item.crafting.ShulkerBoxColoring
- net.minecraft.world.item.crafting.SimpleCookingSerializer
+ net.minecraft.world.item.crafting.SimpleCookingSerializer$CookieBaker
- net.minecraft.world.item.crafting.SimpleRecipeSerializer
+ net.minecraft.world.item.crafting.SingleItemRecipe
- net.minecraft.world.item.crafting.SingleItemRecipe$Serializer
+ net.minecraft.world.item.crafting.SingleItemRecipe$Serializer$SingleItemMaker
- net.minecraft.world.item.crafting.SmeltingRecipe
+ net.minecraft.world.item.crafting.SmokingRecipe
- net.minecraft.world.item.crafting.StonecutterRecipe
+ net.minecraft.world.item.crafting.SuspiciousStewRecipe
- net.minecraft.world.item.crafting.TippedArrowRecipe
+ net.minecraft.world.item.crafting.UpgradeRecipe
- net.minecraft.world.item.crafting.UpgradeRecipe$Serializer
- net.minecraft.world.item.CreativeModeTab
+ net.minecraft.world.item.CreativeModeTab$1
- net.minecraft.world.item.CreativeModeTab$10
+ net.minecraft.world.item.CreativeModeTab$11
- net.minecraft.world.item.CreativeModeTab$12
+ net.minecraft.world.item.CreativeModeTab$2
- net.minecraft.world.item.CreativeModeTab$3
+ net.minecraft.world.item.CreativeModeTab$4
- net.minecraft.world.item.CreativeModeTab$5
+ net.minecraft.world.item.CreativeModeTab$6
- net.minecraft.world.item.CreativeModeTab$7
+ net.minecraft.world.item.CreativeModeTab$8
- net.minecraft.world.item.CreativeModeTab$9
+ net.minecraft.world.item.CrossbowItem
- net.minecraft.world.item.DebugStickItem
+ net.minecraft.world.item.DiggerItem
- net.minecraft.world.item.DispensibleContainerItem
+ net.minecraft.world.item.DoubleHighBlockItem
- net.minecraft.world.item.DyeableArmorItem
+ net.minecraft.world.item.DyeableHorseArmorItem
- net.minecraft.world.item.DyeableLeatherItem
- net.minecraft.world.item.DyeColor
+ net.minecraft.world.item.DyeItem
+ net.minecraft.world.item.EggItem
- net.minecraft.world.item.ElytraItem
+ net.minecraft.world.item.EmptyMapItem
- net.minecraft.world.item.EnchantedBookItem
+ net.minecraft.world.item.EnchantedGoldenAppleItem
- net.minecraft.world.item.enchantment.ArrowDamageEnchantment
+ net.minecraft.world.item.enchantment.ArrowFireEnchantment
- net.minecraft.world.item.enchantment.ArrowInfiniteEnchantment
+ net.minecraft.world.item.enchantment.ArrowKnockbackEnchantment
- net.minecraft.world.item.enchantment.ArrowPiercingEnchantment
+ net.minecraft.world.item.enchantment.BindingCurseEnchantment
- net.minecraft.world.item.enchantment.DamageEnchantment
+ net.minecraft.world.item.enchantment.DigDurabilityEnchantment
- net.minecraft.world.item.enchantment.DiggingEnchantment
+ net.minecraft.world.item.enchantment.Enchantment
- net.minecraft.world.item.enchantment.Enchantment$Rarity
+ net.minecraft.world.item.enchantment.EnchantmentCategory
- net.minecraft.world.item.enchantment.EnchantmentCategory$1
+ net.minecraft.world.item.enchantment.EnchantmentCategory$10
- net.minecraft.world.item.enchantment.EnchantmentCategory$11
+ net.minecraft.world.item.enchantment.EnchantmentCategory$12
- net.minecraft.world.item.enchantment.EnchantmentCategory$13
+ net.minecraft.world.item.enchantment.EnchantmentCategory$14
- net.minecraft.world.item.enchantment.EnchantmentCategory$2
+ net.minecraft.world.item.enchantment.EnchantmentCategory$3
- net.minecraft.world.item.enchantment.EnchantmentCategory$4
+ net.minecraft.world.item.enchantment.EnchantmentCategory$5
- net.minecraft.world.item.enchantment.EnchantmentCategory$6
+ net.minecraft.world.item.enchantment.EnchantmentCategory$7
- net.minecraft.world.item.enchantment.EnchantmentCategory$8
+ net.minecraft.world.item.enchantment.EnchantmentCategory$9
- net.minecraft.world.item.enchantment.EnchantmentHelper
+ net.minecraft.world.item.enchantment.EnchantmentHelper$EnchantmentVisitor
- net.minecraft.world.item.enchantment.EnchantmentInstance
+ net.minecraft.world.item.enchantment.Enchantments
- net.minecraft.world.item.enchantment.FireAspectEnchantment
+ net.minecraft.world.item.enchantment.FishingSpeedEnchantment
- net.minecraft.world.item.enchantment.FrostWalkerEnchantment
+ net.minecraft.world.item.enchantment.KnockbackEnchantment
- net.minecraft.world.item.enchantment.LootBonusEnchantment
+ net.minecraft.world.item.enchantment.MendingEnchantment
- net.minecraft.world.item.enchantment.MultiShotEnchantment
+ net.minecraft.world.item.enchantment.OxygenEnchantment
- net.minecraft.world.item.enchantment.package-info
- net.minecraft.world.item.enchantment.ProtectionEnchantment
+ net.minecraft.world.item.enchantment.ProtectionEnchantment$Type
- net.minecraft.world.item.enchantment.QuickChargeEnchantment
+ net.minecraft.world.item.enchantment.SoulSpeedEnchantment
- net.minecraft.world.item.enchantment.SweepingEdgeEnchantment
+ net.minecraft.world.item.enchantment.ThornsEnchantment
- net.minecraft.world.item.enchantment.TridentChannelingEnchantment
+ net.minecraft.world.item.enchantment.TridentImpalerEnchantment
- net.minecraft.world.item.enchantment.TridentLoyaltyEnchantment
+ net.minecraft.world.item.enchantment.TridentRiptideEnchantment
- net.minecraft.world.item.enchantment.UntouchingEnchantment
+ net.minecraft.world.item.enchantment.VanishingCurseEnchantment
- net.minecraft.world.item.enchantment.WaterWalkerEnchantment
+ net.minecraft.world.item.enchantment.WaterWorkerEnchantment
- net.minecraft.world.item.EndCrystalItem
+ net.minecraft.world.item.EnderEyeItem
- net.minecraft.world.item.EnderpearlItem
+ net.minecraft.world.item.ExperienceBottleItem
- net.minecraft.world.item.FireChargeItem
+ net.minecraft.world.item.FireworkRocketItem
- net.minecraft.world.item.FireworkRocketItem$Shape
+ net.minecraft.world.item.FireworkStarItem
- net.minecraft.world.item.FishingRodItem
+ net.minecraft.world.item.FlintAndSteelItem
- net.minecraft.world.item.FoodOnAStickItem
+ net.minecraft.world.item.GameMasterBlockItem
- net.minecraft.world.item.HangingEntityItem
+ net.minecraft.world.item.HoeItem
- net.minecraft.world.item.HoneyBottleItem
+ net.minecraft.world.item.HoneycombItem
- net.minecraft.world.item.HorseArmorItem
+ net.minecraft.world.item.Item
- net.minecraft.world.item.Item$1
+ net.minecraft.world.item.Item$Properties
- net.minecraft.world.item.ItemCooldowns
+ net.minecraft.world.item.ItemCooldowns$CooldownInstance
- net.minecraft.world.item.ItemFrameItem
+ net.minecraft.world.item.ItemNameBlockItem
+ net.minecraft.world.item.Items
- net.minecraft.world.item.ItemStack
+ net.minecraft.world.item.ItemStack$TooltipPart
- net.minecraft.world.item.ItemUtils
- net.minecraft.world.item.KnowledgeBookItem
+ net.minecraft.world.item.LeadItem
- net.minecraft.world.item.LingeringPotionItem
+ net.minecraft.world.item.MapItem
- net.minecraft.world.item.MilkBucketItem
+ net.minecraft.world.item.MinecartItem
- net.minecraft.world.item.MinecartItem$1
+ net.minecraft.world.item.MobBucketItem
- net.minecraft.world.item.NameTagItem
+ net.minecraft.world.item.package-info
+ net.minecraft.world.item.PickaxeItem
- net.minecraft.world.item.PlayerHeadItem
+ net.minecraft.world.item.PotionItem
- net.minecraft.world.item.ProjectileWeaponItem
+ net.minecraft.world.item.Rarity
- net.minecraft.world.item.RecordItem
+ net.minecraft.world.item.SaddleItem
- net.minecraft.world.item.ScaffoldingBlockItem
+ net.minecraft.world.item.ServerItemCooldowns
- net.minecraft.world.item.ShearsItem
+ net.minecraft.world.item.ShieldItem
- net.minecraft.world.item.ShovelItem
+ net.minecraft.world.item.SignItem
- net.minecraft.world.item.SimpleFoiledItem
+ net.minecraft.world.item.SnowballItem
- net.minecraft.world.item.SolidBucketItem
+ net.minecraft.world.item.SpawnEggItem
- net.minecraft.world.item.SpectralArrowItem
+ net.minecraft.world.item.SplashPotionItem
- net.minecraft.world.item.SpyglassItem
+ net.minecraft.world.item.StandingAndWallBlockItem
- net.minecraft.world.item.SuspiciousStewItem
+ net.minecraft.world.item.SwordItem
- net.minecraft.world.item.ThrowablePotionItem
+ net.minecraft.world.item.Tier
- net.minecraft.world.item.TieredItem
+ net.minecraft.world.item.Tiers
- net.minecraft.world.item.TippedArrowItem
+ net.minecraft.world.item.TooltipFlag
- net.minecraft.world.item.TooltipFlag$Default
- net.minecraft.world.item.trading.Merchant
+ net.minecraft.world.item.trading.MerchantOffer
- net.minecraft.world.item.trading.MerchantOffers
+ net.minecraft.world.item.trading.package-info
+ net.minecraft.world.item.TridentItem
- net.minecraft.world.item.UseAnim
+ net.minecraft.world.item.Vanishable
- net.minecraft.world.item.WaterLilyBlockItem
+ net.minecraft.world.item.Wearable
- net.minecraft.world.item.WritableBookItem
+ net.minecraft.world.item.WrittenBookItem
- net.minecraft.world.level.BaseCommandBlock
+ net.minecraft.world.level.BaseSpawner
+ net.minecraft.world.level.biome.AmbientAdditionsSettings
- net.minecraft.world.level.biome.AmbientMoodSettings
+ net.minecraft.world.level.biome.AmbientParticleSettings
- net.minecraft.world.level.biome.Biome
+ net.minecraft.world.level.biome.Biome$1
- net.minecraft.world.level.biome.Biome$BiomeBuilder
+ net.minecraft.world.level.biome.Biome$BiomeCategory
- net.minecraft.world.level.biome.Biome$ClimateSettings
+ net.minecraft.world.level.biome.Biome$Precipitation
- net.minecraft.world.level.biome.Biome$TemperatureModifier
+ net.minecraft.world.level.biome.Biome$TemperatureModifier$1
- net.minecraft.world.level.biome.Biome$TemperatureModifier$2
+ net.minecraft.world.level.biome.BiomeGenerationSettings
- net.minecraft.world.level.biome.BiomeGenerationSettings$Builder
+ net.minecraft.world.level.biome.BiomeManager
- net.minecraft.world.level.biome.BiomeManager$NoiseBiomeSource
+ net.minecraft.world.level.biome.Biomes
+ net.minecraft.world.level.biome.BiomeSource
- net.minecraft.world.level.biome.BiomeSource$1FeatureData
+ net.minecraft.world.level.biome.BiomeSpecialEffects
- net.minecraft.world.level.biome.BiomeSpecialEffects$Builder
+ net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier
- net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$1
+ net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$2
- net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$3
- net.minecraft.world.level.biome.CheckerboardColumnBiomeSource
+ net.minecraft.world.level.biome.Climate
- net.minecraft.world.level.biome.Climate$DistanceMetric
+ net.minecraft.world.level.biome.Climate$Parameter
- net.minecraft.world.level.biome.Climate$ParameterList
+ net.minecraft.world.level.biome.Climate$ParameterPoint
- net.minecraft.world.level.biome.Climate$RTree
+ net.minecraft.world.level.biome.Climate$RTree$Leaf
- net.minecraft.world.level.biome.Climate$RTree$Node
+ net.minecraft.world.level.biome.Climate$RTree$SubTree
- net.minecraft.world.level.biome.Climate$Sampler
+ net.minecraft.world.level.biome.Climate$TargetPoint
- net.minecraft.world.level.biome.FixedBiomeSource
+ net.minecraft.world.level.biome.MobSpawnSettings
- net.minecraft.world.level.biome.MobSpawnSettings$Builder
+ net.minecraft.world.level.biome.MobSpawnSettings$MobSpawnCost
- net.minecraft.world.level.biome.MobSpawnSettings$SpawnerData
+ net.minecraft.world.level.biome.MultiNoiseBiomeSource
- net.minecraft.world.level.biome.MultiNoiseBiomeSource$Preset
+ net.minecraft.world.level.biome.MultiNoiseBiomeSource$PresetInstance
- net.minecraft.world.level.biome.OverworldBiomeBuilder
- net.minecraft.world.level.biome.package-info
+ net.minecraft.world.level.biome.TerrainShaper
- net.minecraft.world.level.biome.TerrainShaper$1
+ net.minecraft.world.level.biome.TerrainShaper$2
- net.minecraft.world.level.biome.TerrainShaper$3
+ net.minecraft.world.level.biome.TerrainShaper$4
- net.minecraft.world.level.biome.TerrainShaper$Point
+ net.minecraft.world.level.biome.TheEndBiomeSource
+ net.minecraft.world.level.block.AbstractBannerBlock
- net.minecraft.world.level.block.AbstractCandleBlock
+ net.minecraft.world.level.block.AbstractCauldronBlock
- net.minecraft.world.level.block.AbstractChestBlock
+ net.minecraft.world.level.block.AbstractFurnaceBlock
- net.minecraft.world.level.block.AbstractGlassBlock
+ net.minecraft.world.level.block.AbstractSkullBlock
- net.minecraft.world.level.block.AirBlock
+ net.minecraft.world.level.block.AmethystBlock
- net.minecraft.world.level.block.AmethystClusterBlock
+ net.minecraft.world.level.block.AmethystClusterBlock$1
- net.minecraft.world.level.block.AnvilBlock
+ net.minecraft.world.level.block.AttachedStemBlock
- net.minecraft.world.level.block.AzaleaBlock
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
+ net.minecraft.world.level.block.BigDripleafBlock
- net.minecraft.world.level.block.BigDripleafStemBlock
+ net.minecraft.world.level.block.BigDripleafStemBlock$1
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
- net.minecraft.world.level.block.BuddingAmethystBlock
+ net.minecraft.world.level.block.BushBlock
- net.minecraft.world.level.block.ButtonBlock
+ net.minecraft.world.level.block.ButtonBlock$1
- net.minecraft.world.level.block.CactusBlock
+ net.minecraft.world.level.block.CakeBlock
- net.minecraft.world.level.block.CampfireBlock
+ net.minecraft.world.level.block.CandleBlock
- net.minecraft.world.level.block.CandleCakeBlock
+ net.minecraft.world.level.block.CarpetBlock
- net.minecraft.world.level.block.CarrotBlock
+ net.minecraft.world.level.block.CartographyTableBlock
- net.minecraft.world.level.block.CarvedPumpkinBlock
+ net.minecraft.world.level.block.CauldronBlock
- net.minecraft.world.level.block.CaveVines
+ net.minecraft.world.level.block.CaveVinesBlock
- net.minecraft.world.level.block.CaveVinesPlantBlock
+ net.minecraft.world.level.block.ChainBlock
- net.minecraft.world.level.block.ChainBlock$1
+ net.minecraft.world.level.block.ChangeOverTimeBlock
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
+ net.minecraft.world.level.block.DirtPathBlock
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
+ net.minecraft.world.level.block.EnderChestBlock
+ net.minecraft.world.level.block.EndGatewayBlock
- net.minecraft.world.level.block.EndPortalBlock
+ net.minecraft.world.level.block.EndPortalFrameBlock
- net.minecraft.world.level.block.EndRodBlock
- net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity
+ net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity$1
- net.minecraft.world.level.block.entity.BannerBlockEntity
+ net.minecraft.world.level.block.entity.BannerPattern
- net.minecraft.world.level.block.entity.BannerPattern$Builder
+ net.minecraft.world.level.block.entity.BarrelBlockEntity
- net.minecraft.world.level.block.entity.BarrelBlockEntity$1
+ net.minecraft.world.level.block.entity.BaseContainerBlockEntity
- net.minecraft.world.level.block.entity.BeaconBlockEntity
+ net.minecraft.world.level.block.entity.BeaconBlockEntity$1
- net.minecraft.world.level.block.entity.BeaconBlockEntity$BeaconBeamSection
+ net.minecraft.world.level.block.entity.BedBlockEntity
- net.minecraft.world.level.block.entity.BeehiveBlockEntity
+ net.minecraft.world.level.block.entity.BeehiveBlockEntity$BeeData
- net.minecraft.world.level.block.entity.BeehiveBlockEntity$BeeReleaseStatus
+ net.minecraft.world.level.block.entity.BellBlockEntity
- net.minecraft.world.level.block.entity.BellBlockEntity$ResonationEndAction
+ net.minecraft.world.level.block.entity.BlastFurnaceBlockEntity
- net.minecraft.world.level.block.entity.BlockEntity
+ net.minecraft.world.level.block.entity.BlockEntityTicker
- net.minecraft.world.level.block.entity.BlockEntityType
+ net.minecraft.world.level.block.entity.BlockEntityType$BlockEntitySupplier
- net.minecraft.world.level.block.entity.BlockEntityType$Builder
+ net.minecraft.world.level.block.entity.BrewingStandBlockEntity
- net.minecraft.world.level.block.entity.BrewingStandBlockEntity$1
+ net.minecraft.world.level.block.entity.CampfireBlockEntity
- net.minecraft.world.level.block.entity.ChestBlockEntity
+ net.minecraft.world.level.block.entity.ChestBlockEntity$1
- net.minecraft.world.level.block.entity.ChestLidController
+ net.minecraft.world.level.block.entity.CommandBlockEntity
- net.minecraft.world.level.block.entity.CommandBlockEntity$1
+ net.minecraft.world.level.block.entity.CommandBlockEntity$Mode
- net.minecraft.world.level.block.entity.ComparatorBlockEntity
+ net.minecraft.world.level.block.entity.ConduitBlockEntity
- net.minecraft.world.level.block.entity.ContainerOpenersCounter
+ net.minecraft.world.level.block.entity.DaylightDetectorBlockEntity
- net.minecraft.world.level.block.entity.DispenserBlockEntity
+ net.minecraft.world.level.block.entity.DropperBlockEntity
- net.minecraft.world.level.block.entity.EnchantmentTableBlockEntity
+ net.minecraft.world.level.block.entity.EnderChestBlockEntity
- net.minecraft.world.level.block.entity.EnderChestBlockEntity$1
+ net.minecraft.world.level.block.entity.FurnaceBlockEntity
- net.minecraft.world.level.block.entity.Hopper
+ net.minecraft.world.level.block.entity.HopperBlockEntity
- net.minecraft.world.level.block.entity.JigsawBlockEntity
+ net.minecraft.world.level.block.entity.JigsawBlockEntity$JointType
- net.minecraft.world.level.block.entity.JukeboxBlockEntity
+ net.minecraft.world.level.block.entity.LecternBlockEntity
- net.minecraft.world.level.block.entity.LecternBlockEntity$1
+ net.minecraft.world.level.block.entity.LecternBlockEntity$2
- net.minecraft.world.level.block.entity.LidBlockEntity
+ net.minecraft.world.level.block.entity.package-info
+ net.minecraft.world.level.block.entity.RandomizableContainerBlockEntity
- net.minecraft.world.level.block.entity.SculkSensorBlockEntity
+ net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity
- net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity$1
+ net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity$AnimationStatus
- net.minecraft.world.level.block.entity.SignBlockEntity
+ net.minecraft.world.level.block.entity.SkullBlockEntity
- net.minecraft.world.level.block.entity.SmokerBlockEntity
+ net.minecraft.world.level.block.entity.SpawnerBlockEntity
- net.minecraft.world.level.block.entity.SpawnerBlockEntity$1
+ net.minecraft.world.level.block.entity.StructureBlockEntity
- net.minecraft.world.level.block.entity.StructureBlockEntity$UpdateType
+ net.minecraft.world.level.block.entity.TheEndGatewayBlockEntity
- net.minecraft.world.level.block.entity.TheEndPortalBlockEntity
+ net.minecraft.world.level.block.entity.TickingBlockEntity
- net.minecraft.world.level.block.entity.TrappedChestBlockEntity
- net.minecraft.world.level.block.EntityBlock
+ net.minecraft.world.level.block.FaceAttachedHorizontalDirectionalBlock
- net.minecraft.world.level.block.FaceAttachedHorizontalDirectionalBlock$1
+ net.minecraft.world.level.block.Fallable
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
- net.minecraft.world.level.block.GameMasterBlock
+ net.minecraft.world.level.block.GlassBlock
- net.minecraft.world.level.block.GlazedTerracottaBlock
+ net.minecraft.world.level.block.GlowLichenBlock
- net.minecraft.world.level.block.GrassBlock
+ net.minecraft.world.level.block.GravelBlock
- net.minecraft.world.level.block.GrindstoneBlock
+ net.minecraft.world.level.block.GrindstoneBlock$1
- net.minecraft.world.level.block.grower.AbstractMegaTreeGrower
+ net.minecraft.world.level.block.grower.AbstractTreeGrower
- net.minecraft.world.level.block.grower.AcaciaTreeGrower
+ net.minecraft.world.level.block.grower.AzaleaTreeGrower
- net.minecraft.world.level.block.grower.BirchTreeGrower
+ net.minecraft.world.level.block.grower.DarkOakTreeGrower
- net.minecraft.world.level.block.grower.JungleTreeGrower
+ net.minecraft.world.level.block.grower.OakTreeGrower
+ net.minecraft.world.level.block.grower.package-info
- net.minecraft.world.level.block.grower.SpruceTreeGrower
- net.minecraft.world.level.block.GrowingPlantBlock
+ net.minecraft.world.level.block.GrowingPlantBodyBlock
- net.minecraft.world.level.block.GrowingPlantHeadBlock
+ net.minecraft.world.level.block.HalfTransparentBlock
- net.minecraft.world.level.block.HangingRootsBlock
+ net.minecraft.world.level.block.HayBlock
- net.minecraft.world.level.block.HoneyBlock
+ net.minecraft.world.level.block.HopperBlock
- net.minecraft.world.level.block.HopperBlock$1
+ net.minecraft.world.level.block.HorizontalDirectionalBlock
- net.minecraft.world.level.block.HugeMushroomBlock
+ net.minecraft.world.level.block.IceBlock
- net.minecraft.world.level.block.InfestedBlock
+ net.minecraft.world.level.block.InfestedRotatedPillarBlock
- net.minecraft.world.level.block.IronBarsBlock
+ net.minecraft.world.level.block.JigsawBlock
- net.minecraft.world.level.block.JukeboxBlock
+ net.minecraft.world.level.block.KelpBlock
- net.minecraft.world.level.block.KelpPlantBlock
+ net.minecraft.world.level.block.LadderBlock
- net.minecraft.world.level.block.LadderBlock$1
+ net.minecraft.world.level.block.LanternBlock
- net.minecraft.world.level.block.LavaCauldronBlock
+ net.minecraft.world.level.block.LayeredCauldronBlock
- net.minecraft.world.level.block.LeavesBlock
+ net.minecraft.world.level.block.LecternBlock
- net.minecraft.world.level.block.LecternBlock$1
+ net.minecraft.world.level.block.LevelEvent
- net.minecraft.world.level.block.LeverBlock
+ net.minecraft.world.level.block.LeverBlock$1
- net.minecraft.world.level.block.LightBlock
+ net.minecraft.world.level.block.LightningRodBlock
- net.minecraft.world.level.block.LiquidBlock
+ net.minecraft.world.level.block.LiquidBlockContainer
- net.minecraft.world.level.block.LoomBlock
+ net.minecraft.world.level.block.MagmaBlock
- net.minecraft.world.level.block.MelonBlock
+ net.minecraft.world.level.block.Mirror
- net.minecraft.world.level.block.Mirror$1
+ net.minecraft.world.level.block.MossBlock
- net.minecraft.world.level.block.MultifaceBlock
+ net.minecraft.world.level.block.MushroomBlock
- net.minecraft.world.level.block.MyceliumBlock
+ net.minecraft.world.level.block.NetherPortalBlock
- net.minecraft.world.level.block.NetherPortalBlock$1
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
- net.minecraft.world.level.block.PointedDripstoneBlock
+ net.minecraft.world.level.block.PotatoBlock
- net.minecraft.world.level.block.PowderSnowBlock
+ net.minecraft.world.level.block.PowderSnowCauldronBlock
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
+ net.minecraft.world.level.block.RespawnAnchorBlock$1
- net.minecraft.world.level.block.RodBlock
+ net.minecraft.world.level.block.RodBlock$1
- net.minecraft.world.level.block.RootedDirtBlock
+ net.minecraft.world.level.block.RootsBlock
- net.minecraft.world.level.block.RotatedPillarBlock
+ net.minecraft.world.level.block.RotatedPillarBlock$1
- net.minecraft.world.level.block.Rotation
+ net.minecraft.world.level.block.Rotation$1
- net.minecraft.world.level.block.SandBlock
+ net.minecraft.world.level.block.SaplingBlock
- net.minecraft.world.level.block.ScaffoldingBlock
+ net.minecraft.world.level.block.SculkSensorBlock
+ net.minecraft.world.level.block.SeagrassBlock
- net.minecraft.world.level.block.SeaPickleBlock
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
- net.minecraft.world.level.block.SmallDripleafBlock
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
+ net.minecraft.world.level.block.SporeBlossomBlock
- net.minecraft.world.level.block.SpreadingSnowyDirtBlock
+ net.minecraft.world.level.block.StainedGlassBlock
- net.minecraft.world.level.block.StainedGlassPaneBlock
+ net.minecraft.world.level.block.StairBlock
- net.minecraft.world.level.block.StairBlock$1
+ net.minecraft.world.level.block.StandingSignBlock
- net.minecraft.world.level.block.state.BlockBehaviour
+ net.minecraft.world.level.block.state.BlockBehaviour$1
- net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase
+ net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase$Cache
- net.minecraft.world.level.block.state.BlockBehaviour$OffsetType
+ net.minecraft.world.level.block.state.BlockBehaviour$Properties
- net.minecraft.world.level.block.state.BlockBehaviour$StateArgumentPredicate
+ net.minecraft.world.level.block.state.BlockBehaviour$StatePredicate
- net.minecraft.world.level.block.state.BlockState
- net.minecraft.world.level.block.state.package-info
+ net.minecraft.world.level.block.state.pattern.BlockInWorld
- net.minecraft.world.level.block.state.pattern.BlockPattern
+ net.minecraft.world.level.block.state.pattern.BlockPattern$BlockCacheLoader
- net.minecraft.world.level.block.state.pattern.BlockPattern$BlockPatternMatch
+ net.minecraft.world.level.block.state.pattern.BlockPatternBuilder
- net.minecraft.world.level.block.state.pattern.package-info
+ net.minecraft.world.level.block.state.predicate.BlockMaterialPredicate
- net.minecraft.world.level.block.state.predicate.BlockMaterialPredicate$1
+ net.minecraft.world.level.block.state.predicate.BlockPredicate
- net.minecraft.world.level.block.state.predicate.BlockStatePredicate
+ net.minecraft.world.level.block.state.predicate.package-info
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
+ net.minecraft.world.level.block.state.properties.DripstoneThickness
- net.minecraft.world.level.block.state.properties.EnumProperty
+ net.minecraft.world.level.block.state.properties.Half
- net.minecraft.world.level.block.state.properties.IntegerProperty
+ net.minecraft.world.level.block.state.properties.NoteBlockInstrument
- net.minecraft.world.level.block.state.properties.package-info
- net.minecraft.world.level.block.state.properties.PistonType
+ net.minecraft.world.level.block.state.properties.Property
- net.minecraft.world.level.block.state.properties.Property$Value
+ net.minecraft.world.level.block.state.properties.RailShape
- net.minecraft.world.level.block.state.properties.RedstoneSide
+ net.minecraft.world.level.block.state.properties.SculkSensorPhase
- net.minecraft.world.level.block.state.properties.SlabType
+ net.minecraft.world.level.block.state.properties.StairsShape
- net.minecraft.world.level.block.state.properties.StructureMode
+ net.minecraft.world.level.block.state.properties.Tilt
- net.minecraft.world.level.block.state.properties.WallSide
+ net.minecraft.world.level.block.state.properties.WoodType
+ net.minecraft.world.level.block.state.StateDefinition
- net.minecraft.world.level.block.state.StateDefinition$Builder
+ net.minecraft.world.level.block.state.StateDefinition$Factory
- net.minecraft.world.level.block.state.StateHolder
+ net.minecraft.world.level.block.state.StateHolder$1
- net.minecraft.world.level.block.StemBlock
+ net.minecraft.world.level.block.StemGrownBlock
- net.minecraft.world.level.block.StoneButtonBlock
+ net.minecraft.world.level.block.StonecutterBlock
- net.minecraft.world.level.block.StructureBlock
+ net.minecraft.world.level.block.StructureBlock$1
- net.minecraft.world.level.block.StructureVoidBlock
+ net.minecraft.world.level.block.SugarCaneBlock
- net.minecraft.world.level.block.SupportType
+ net.minecraft.world.level.block.SupportType$1
- net.minecraft.world.level.block.SupportType$2
+ net.minecraft.world.level.block.SupportType$3
- net.minecraft.world.level.block.SweetBerryBushBlock
+ net.minecraft.world.level.block.TallFlowerBlock
- net.minecraft.world.level.block.TallGrassBlock
+ net.minecraft.world.level.block.TallSeagrassBlock
- net.minecraft.world.level.block.TargetBlock
+ net.minecraft.world.level.block.TintedGlassBlock
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
- net.minecraft.world.level.block.TwistingVinesBlock
+ net.minecraft.world.level.block.TwistingVinesPlantBlock
- net.minecraft.world.level.block.VineBlock
+ net.minecraft.world.level.block.VineBlock$1
- net.minecraft.world.level.block.WallBannerBlock
+ net.minecraft.world.level.block.WallBlock
- net.minecraft.world.level.block.WallBlock$1
+ net.minecraft.world.level.block.WallSignBlock
- net.minecraft.world.level.block.WallSkullBlock
+ net.minecraft.world.level.block.WallTorchBlock
- net.minecraft.world.level.block.WaterlilyBlock
+ net.minecraft.world.level.block.WeatheringCopper
- net.minecraft.world.level.block.WeatheringCopper$WeatherState
+ net.minecraft.world.level.block.WeatheringCopperFullBlock
- net.minecraft.world.level.block.WeatheringCopperSlabBlock
+ net.minecraft.world.level.block.WeatheringCopperStairBlock
- net.minecraft.world.level.block.WebBlock
+ net.minecraft.world.level.block.WeepingVinesBlock
- net.minecraft.world.level.block.WeepingVinesPlantBlock
+ net.minecraft.world.level.block.WeightedPressurePlateBlock
- net.minecraft.world.level.block.WetSpongeBlock
+ net.minecraft.world.level.block.WitherRoseBlock
- net.minecraft.world.level.block.WitherSkullBlock
+ net.minecraft.world.level.block.WitherWallSkullBlock
- net.minecraft.world.level.block.WoodButtonBlock
+ net.minecraft.world.level.block.WoolCarpetBlock
- net.minecraft.world.level.BlockAndTintGetter
+ net.minecraft.world.level.BlockEventData
- net.minecraft.world.level.BlockGetter
+ net.minecraft.world.level.border.BorderChangeListener
- net.minecraft.world.level.border.BorderChangeListener$DelegateBorderChangeListener
+ net.minecraft.world.level.border.BorderStatus
+ net.minecraft.world.level.border.package-info
- net.minecraft.world.level.border.WorldBorder
+ net.minecraft.world.level.border.WorldBorder$BorderExtent
- net.minecraft.world.level.border.WorldBorder$MovingBorderExtent
+ net.minecraft.world.level.border.WorldBorder$Settings
- net.minecraft.world.level.border.WorldBorder$StaticBorderExtent
- net.minecraft.world.level.chunk.BlockColumn
+ net.minecraft.world.level.chunk.BulkSectionAccess
- net.minecraft.world.level.chunk.CarvingMask
+ net.minecraft.world.level.chunk.ChunkAccess
- net.minecraft.world.level.chunk.ChunkGenerator
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
- net.minecraft.world.level.chunk.LevelChunk$1
+ net.minecraft.world.level.chunk.LevelChunk$BoundTickingBlockEntity
- net.minecraft.world.level.chunk.LevelChunk$EntityCreationType
+ net.minecraft.world.level.chunk.LevelChunk$RebindableTickingBlockEntityWrapper
- net.minecraft.world.level.chunk.LevelChunkSection
+ net.minecraft.world.level.chunk.LightChunkGetter
- net.minecraft.world.level.chunk.LinearPalette
+ net.minecraft.world.level.chunk.MissingPaletteEntryException
- net.minecraft.world.level.chunk.package-info
- net.minecraft.world.level.chunk.Palette
+ net.minecraft.world.level.chunk.Palette$Factory
+ net.minecraft.world.level.chunk.PalettedContainer
- net.minecraft.world.level.chunk.PalettedContainer$Configuration
+ net.minecraft.world.level.chunk.PalettedContainer$CountConsumer
- net.minecraft.world.level.chunk.PalettedContainer$Data
+ net.minecraft.world.level.chunk.PalettedContainer$DiscData
- net.minecraft.world.level.chunk.PalettedContainer$Strategy
+ net.minecraft.world.level.chunk.PalettedContainer$Strategy$1
- net.minecraft.world.level.chunk.PalettedContainer$Strategy$2
- net.minecraft.world.level.chunk.PaletteResize
+ net.minecraft.world.level.chunk.ProtoChunk
- net.minecraft.world.level.chunk.ProtoTickList
+ net.minecraft.world.level.chunk.SingleValuePalette
+ net.minecraft.world.level.chunk.storage.ChunkSerializer
- net.minecraft.world.level.chunk.storage.ChunkStorage
+ net.minecraft.world.level.chunk.storage.EntityStorage
- net.minecraft.world.level.chunk.storage.IOWorker
+ net.minecraft.world.level.chunk.storage.IOWorker$PendingStore
- net.minecraft.world.level.chunk.storage.IOWorker$Priority
+ net.minecraft.world.level.chunk.storage.package-info
+ net.minecraft.world.level.chunk.storage.RegionBitmap
- net.minecraft.world.level.chunk.storage.RegionFile
+ net.minecraft.world.level.chunk.storage.RegionFile$ChunkBuffer
- net.minecraft.world.level.chunk.storage.RegionFile$CommitOp
+ net.minecraft.world.level.chunk.storage.RegionFileStorage
- net.minecraft.world.level.chunk.storage.RegionFileVersion
+ net.minecraft.world.level.chunk.storage.RegionFileVersion$StreamWrapper
- net.minecraft.world.level.chunk.storage.SectionStorage
- net.minecraft.world.level.chunk.UpgradeData
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixer
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$1
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$2
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$3
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$4
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$5
+ net.minecraft.world.level.ChunkPos
- net.minecraft.world.level.ChunkPos$1
+ net.minecraft.world.level.ChunkTickList
- net.minecraft.world.level.ChunkTickList$ScheduledTick
+ net.minecraft.world.level.ClipBlockStateContext
- net.minecraft.world.level.ClipContext
+ net.minecraft.world.level.ClipContext$Block
- net.minecraft.world.level.ClipContext$Fluid
+ net.minecraft.world.level.ClipContext$ShapeGetter
- net.minecraft.world.level.CollisionGetter
+ net.minecraft.world.level.CollisionSpliterator
- net.minecraft.world.level.ColorResolver
+ net.minecraft.world.level.CommonLevelAccessor
- net.minecraft.world.level.CustomSpawner
+ net.minecraft.world.level.DataPackConfig
- net.minecraft.world.level.dimension.DimensionDefaults
+ net.minecraft.world.level.dimension.DimensionType
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$1
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$2
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$3
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$4
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$5
+ net.minecraft.world.level.dimension.end.EndDragonFight
- net.minecraft.world.level.dimension.end.package-info
- net.minecraft.world.level.dimension.LevelStem
+ net.minecraft.world.level.dimension.package-info
- net.minecraft.world.level.EmptyBlockGetter
+ net.minecraft.world.level.EmptyTickList
- net.minecraft.world.level.entity.ChunkEntities
+ net.minecraft.world.level.entity.ChunkStatusUpdateListener
- net.minecraft.world.level.entity.EntityAccess
+ net.minecraft.world.level.entity.EntityInLevelCallback
- net.minecraft.world.level.entity.EntityInLevelCallback$1
+ net.minecraft.world.level.entity.EntityLookup
- net.minecraft.world.level.entity.EntityPersistentStorage
+ net.minecraft.world.level.entity.EntitySection
- net.minecraft.world.level.entity.EntitySectionStorage
+ net.minecraft.world.level.entity.EntityTickList
- net.minecraft.world.level.entity.EntityTypeTest
+ net.minecraft.world.level.entity.EntityTypeTest$1
- net.minecraft.world.level.entity.LevelCallback
+ net.minecraft.world.level.entity.LevelEntityGetter
- net.minecraft.world.level.entity.LevelEntityGetterAdapter
+ net.minecraft.world.level.entity.package-info
+ net.minecraft.world.level.entity.PersistentEntitySectionManager
- net.minecraft.world.level.entity.PersistentEntitySectionManager$Callback
+ net.minecraft.world.level.entity.PersistentEntitySectionManager$ChunkLoadStatus
- net.minecraft.world.level.entity.TransientEntitySectionManager
+ net.minecraft.world.level.entity.TransientEntitySectionManager$Callback
- net.minecraft.world.level.entity.Visibility
- net.minecraft.world.level.EntityBasedExplosionDamageCalculator
+ net.minecraft.world.level.EntityGetter
- net.minecraft.world.level.Explosion
+ net.minecraft.world.level.Explosion$BlockInteraction
- net.minecraft.world.level.ExplosionDamageCalculator
+ net.minecraft.world.level.FoliageColor
- net.minecraft.world.level.ForcedChunksSavedData
- net.minecraft.world.level.gameevent.BlockPositionSource
+ net.minecraft.world.level.gameevent.BlockPositionSource$Type
- net.minecraft.world.level.gameevent.EntityPositionSource
+ net.minecraft.world.level.gameevent.EntityPositionSource$Type
- net.minecraft.world.level.gameevent.EuclideanGameEventDispatcher
+ net.minecraft.world.level.gameevent.GameEvent
- net.minecraft.world.level.gameevent.GameEventDispatcher
+ net.minecraft.world.level.gameevent.GameEventDispatcher$1
- net.minecraft.world.level.gameevent.GameEventListener
+ net.minecraft.world.level.gameevent.GameEventListenerRegistrar
- net.minecraft.world.level.gameevent.package-info
- net.minecraft.world.level.gameevent.PositionSource
+ net.minecraft.world.level.gameevent.PositionSourceType
- net.minecraft.world.level.gameevent.vibrations.package-info
+ net.minecraft.world.level.gameevent.vibrations.VibrationListener
- net.minecraft.world.level.gameevent.vibrations.VibrationListener$VibrationListenerConfig
+ net.minecraft.world.level.gameevent.vibrations.VibrationPath
+ net.minecraft.world.level.GameRules
- net.minecraft.world.level.GameRules$BooleanValue
+ net.minecraft.world.level.GameRules$Category
- net.minecraft.world.level.GameRules$GameRuleTypeVisitor
+ net.minecraft.world.level.GameRules$IntegerValue
- net.minecraft.world.level.GameRules$Key
+ net.minecraft.world.level.GameRules$Type
- net.minecraft.world.level.GameRules$Value
+ net.minecraft.world.level.GameRules$VisitorCaller
- net.minecraft.world.level.GameType
+ net.minecraft.world.level.GrassColor
- net.minecraft.world.level.ItemLike
+ net.minecraft.world.level.Level
- net.minecraft.world.level.Level$1
+ net.minecraft.world.level.LevelAccessor
+ net.minecraft.world.level.levelgen.Aquifer
- net.minecraft.world.level.levelgen.Aquifer$1
+ net.minecraft.world.level.levelgen.Aquifer$FluidPicker
- net.minecraft.world.level.levelgen.Aquifer$FluidStatus
+ net.minecraft.world.level.levelgen.Aquifer$NoiseBasedAquifer
- net.minecraft.world.level.levelgen.Beardifier
+ net.minecraft.world.level.levelgen.BitRandomSource
- net.minecraft.world.level.levelgen.blockpredicates.AllOfPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.AnyOfPredicate
- net.minecraft.world.level.levelgen.blockpredicates.BlockPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.BlockPredicateType
- net.minecraft.world.level.levelgen.blockpredicates.CombiningPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.MatchingBlocksPredicate
- net.minecraft.world.level.levelgen.blockpredicates.MatchingFluidsPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.NotPredicate
- net.minecraft.world.level.levelgen.blockpredicates.ReplaceablePredicate
- net.minecraft.world.level.levelgen.blockpredicates.TrueBlockPredicate
- net.minecraft.world.level.levelgen.Column
+ net.minecraft.world.level.levelgen.Column$Line
- net.minecraft.world.level.levelgen.Column$Range
+ net.minecraft.world.level.levelgen.Column$Ray
- net.minecraft.world.level.levelgen.DebugLevelSource
+ net.minecraft.world.level.levelgen.Decoratable
- net.minecraft.world.level.levelgen.Density
+ net.minecraft.world.level.levelgen.DepthBasedRule
+ net.minecraft.world.level.levelgen.feature.configurations.package-info
+ net.minecraft.world.level.levelgen.feature.configurations.SingleBlockStateConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SmallDripstoneConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SpikeConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SpringConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.StrongholdConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.StructureFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
+ net.minecraft.world.level.levelgen.feature.configurations.UnderwaterMagmaConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.VegetationPatchConfiguration
- net.minecraft.world.level.levelgen.feature.featuresize.FeatureSize
+ net.minecraft.world.level.levelgen.feature.featuresize.FeatureSizeType
- net.minecraft.world.level.levelgen.feature.featuresize.package-info
- net.minecraft.world.level.levelgen.feature.featuresize.ThreeLayersFeatureSize
+ net.minecraft.world.level.levelgen.feature.featuresize.TwoLayersFeatureSize
+ net.minecraft.world.level.levelgen.feature.foliageplacers.AcaciaFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.BlobFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.BushFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.DarkOakFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FancyFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer$FoliageAttachment
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacerType
+ net.minecraft.world.level.levelgen.feature.foliageplacers.MegaJungleFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.MegaPineFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.package-info
+ net.minecraft.world.level.levelgen.feature.foliageplacers.PineFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.RandomSpreadFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.SpruceFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.package-info
- net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProviderType
- net.minecraft.world.level.levelgen.feature.stateproviders.DualNoiseProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.NoiseBasedStateProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.NoiseProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.NoiseThresholdProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.package-info
- net.minecraft.world.level.levelgen.feature.stateproviders.RandomizedIntStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.RotatedBlockProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.SimpleStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.WeightedStateProvider
+ net.minecraft.world.level.levelgen.feature.structures.EmptyPoolElement
- net.minecraft.world.level.levelgen.feature.structures.FeaturePoolElement
+ net.minecraft.world.level.levelgen.feature.structures.JigsawJunction
- net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$PieceFactory
- net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$PieceState
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$Placer
- net.minecraft.world.level.levelgen.feature.structures.LegacySinglePoolElement
+ net.minecraft.world.level.levelgen.feature.structures.ListPoolElement
+ net.minecraft.world.level.levelgen.feature.structures.package-info
- net.minecraft.world.level.levelgen.feature.structures.SinglePoolElement
+ net.minecraft.world.level.levelgen.feature.structures.StructurePoolElement
- net.minecraft.world.level.levelgen.feature.structures.StructurePoolElementType
+ net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool
- net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool$Projection
- net.minecraft.world.level.levelgen.feature.treedecorators.AlterGroundDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.BeehiveDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.CocoaDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.LeaveVineDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.package-info
- net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecoratorType
- net.minecraft.world.level.levelgen.feature.treedecorators.TrunkVineDecorator
- net.minecraft.world.level.levelgen.feature.trunkplacers.BendingTrunkPlacer
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
+ net.minecraft.world.level.levelgen.flat.package-info
- net.minecraft.world.level.levelgen.heightproviders.BiasedToBottomHeight
+ net.minecraft.world.level.levelgen.heightproviders.ConstantHeight
- net.minecraft.world.level.levelgen.heightproviders.HeightProvider
+ net.minecraft.world.level.levelgen.heightproviders.HeightProviderType
+ net.minecraft.world.level.levelgen.heightproviders.package-info
- net.minecraft.world.level.levelgen.heightproviders.TrapezoidHeight
+ net.minecraft.world.level.levelgen.heightproviders.UniformHeight
- net.minecraft.world.level.levelgen.heightproviders.VeryBiasedToBottomHeight
- net.minecraft.world.level.levelgen.LegacyRandomSource$LegacyPositionalRandomFactory
- net.minecraft.world.level.levelgen.material.MaterialRuleList
- net.minecraft.world.level.levelgen.material.package-info
+ net.minecraft.world.level.levelgen.material.WorldGenMaterialRule
- net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator
+ net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator$1
- net.minecraft.world.level.levelgen.NoiseChunk
+ net.minecraft.world.level.levelgen.NoiseChunk$BlockStateFiller
- net.minecraft.world.level.levelgen.NoiseChunk$FlatNoiseData
+ net.minecraft.world.level.levelgen.NoiseChunk$InterpolatableNoise
- net.minecraft.world.level.levelgen.NoiseChunk$NoiseFiller
+ net.minecraft.world.level.levelgen.NoiseChunk$NoiseInterpolator
- net.minecraft.world.level.levelgen.NoiseChunk$Sampler
+ net.minecraft.world.level.levelgen.NoiseGeneratorSettings
- net.minecraft.world.level.levelgen.NoiseOctaves
+ net.minecraft.world.level.levelgen.NoiseSampler
- net.minecraft.world.level.levelgen.NoiseSampler$QuantizedSpaghettiRarity
+ net.minecraft.world.level.levelgen.NoiseSampler$VeinType
- net.minecraft.world.level.levelgen.NoiseSamplingSettings
+ net.minecraft.world.level.levelgen.NoiseSettings
- net.minecraft.world.level.levelgen.NoiseSlider
+ net.minecraft.world.level.levelgen.package-info
+ net.minecraft.world.level.levelgen.PatrolSpawner
- net.minecraft.world.level.levelgen.PhantomSpawner
- net.minecraft.world.level.levelgen.placement.BlockFilterConfiguration
+ net.minecraft.world.level.levelgen.placement.BlockFilterDecorator
+ net.minecraft.world.level.levelgen.PositionalRandomFactory
- net.minecraft.world.level.levelgen.RandomSource
- net.minecraft.world.level.levelgen.RandomSupport$Seed128bit
+ net.minecraft.world.level.levelgen.SimpleRandomSource
- net.minecraft.world.level.levelgen.VerticalGradientRule
- net.minecraft.world.level.levelgen.WorldGenerationContext
+ net.minecraft.world.level.levelgen.WorldgenRandom
- net.minecraft.world.level.levelgen.WorldgenRandom$Algorithm
+ net.minecraft.world.level.levelgen.WorldGenSettings
- net.minecraft.world.level.levelgen.XoroshiroRandomSource
- net.minecraft.world.level.LevelHeightAccessor
+ net.minecraft.world.level.LevelReader
- net.minecraft.world.level.LevelSettings
- net.minecraft.world.level.LevelSimulatedReader
+ net.minecraft.world.level.LevelSimulatedRW
+ net.minecraft.world.level.LevelTimeAccess
- net.minecraft.world.level.LevelWriter
+ net.minecraft.world.level.LightLayer
- net.minecraft.world.level.LocalMobCapCalculator
+ net.minecraft.world.level.LocalMobCapCalculator$MobCounts
- net.minecraft.world.level.NaturalSpawner
+ net.minecraft.world.level.NaturalSpawner$1
- net.minecraft.world.level.NaturalSpawner$AfterSpawnCallback
+ net.minecraft.world.level.NaturalSpawner$ChunkGetter
- net.minecraft.world.level.NaturalSpawner$SpawnPredicate
+ net.minecraft.world.level.NaturalSpawner$SpawnState
- net.minecraft.world.level.NoiseColumn
+ net.minecraft.world.level.PathNavigationRegion
- net.minecraft.world.level.PotentialCalculator
+ net.minecraft.world.level.PotentialCalculator$PointCharge
- net.minecraft.world.level.ServerLevelAccessor
+ net.minecraft.world.level.ServerTickList
- net.minecraft.world.level.SpawnData
+ net.minecraft.world.level.SpawnData$CustomSpawnRules
- net.minecraft.world.level.StructureFeatureManager
+ net.minecraft.world.level.TickList
- net.minecraft.world.level.TickNextTickData
+ net.minecraft.world.level.TickPriority
- net.minecraft.world.level.WorldGenLevel
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.data.worldgen.BiomeDefaultFeatures +2M -3M
```
```
XXX.protocol.game.ClientboundBlockEntityDataPacket +1M
```
```
XXX.world.entity.Entity +1P
```
```
XXX.ai.behavior.InteractWith +3M -5M
```
```
XXX.ai.behavior.SetEntityLookTarget +1M -3M | +1P
```
```
XXX.ai.behavior.SetLookAndInteract +3M -3M
```
```
XXX.ai.control.LookControl +1M -1M | +1P -1P
```
```
XXX.ai.goal.ZombieAttackGoal -1M
```
```
XXX.levelgen.feature.RandomPatchFeature -1M
```
```
XXX.feature.configurations.BlockColumnConfiguration +2M -2M | +1P -1P
```
```
XXX.levelgen.placement.FeatureDecorator -1P
```

</details>












































































































































































































































































<details>
<summary>
net.minecraft.data.worldgen.BiomeDefaultFeatures
</summary>

```diff
+ void addBerryBushes(BiomeGenerationSettings$Builder)
- void addCommonBerryBushes(BiomeGenerationSettings$Builder)
- void addRareBerryBushes(BiomeGenerationSettings$Builder)
+ void addSparseBerryBushes(BiomeGenerationSettings$Builder)
+ void caveWaterSpawns(MobSpawnSettings$Builder)
```

</details>



























































































<details>
<summary>
net.minecraft.network.protocol.game.ClientboundBlockEntityDataPacket
</summary>

```diff
- ClientboundBlockEntityDataPacket create(BlockEntity,Function)
```

</details>




























































































































































































































































































<details>
<summary>
net.minecraft.world.entity.ai.behavior.InteractWith
</summary>

```diff
- boolean canInteract(LivingEntity,LivingEntity)
- boolean lambda$start$3(LivingEntity,LivingEntity)
+ boolean lambda$start$3(LivingEntity)
+ boolean lambda$start$5(LivingEntity,LivingEntity)
+ LivingEntity lambda$start$4(LivingEntity)
- void lambda$start$4(Brain,LivingEntity)
+ void lambda$start$6(Brain,LivingEntity)
+ void lambda$start$7(LivingEntity,Brain,List)
```

</details>














<details>
<summary>
net.minecraft.world.entity.ai.behavior.SetEntityLookTarget
</summary>

```diff
- boolean lambda$checkExtraStartConditions$4(LivingEntity,LivingEntity)
+ boolean lambda$start$4(LivingEntity,LivingEntity)
+ void lambda$start$5(Brain,LivingEntity)
+ void lambda$start$6(LivingEntity,Brain,List)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.behavior.SetLookAndInteract
</summary>

```diff
+ List getVisibleEntities(LivingEntity)
- NearestVisibleLivingEntities getVisibleEntities(LivingEntity)
- Optional lambda$start$3(LivingEntity,NearestVisibleLivingEntities)
+ void lambda$start$3(Brain,LivingEntity)
- void lambda$start$4(Brain,LivingEntity)
+ void lambda$start$4(LivingEntity,Brain,List)
```

</details>



















<details>
<summary>
net.minecraft.world.entity.ai.control.LookControl
</summary>

```diff
+ boolean isHasWanted()
- boolean isLookingAtTarget()
```

</details>

































<details>
<summary>
net.minecraft.world.entity.ai.goal.ZombieAttackGoal
</summary>

```diff
+ boolean requiresUpdateEveryTick()
```

</details>

























































<details>
<summary>
net.minecraft.world.level.levelgen.feature.RandomPatchFeature
</summary>

```diff
+ boolean isValid(LevelAccessor,BlockPos,RandomPatchConfiguration)
```

</details>

















<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.BlockColumnConfiguration
</summary>

```diff
- BlockPredicate allowedPlacement()
+ boolean allowWater()
- void <init>(List,Direction,BlockPredicate,boolean)
+ void <init>(List,Direction,boolean,boolean)
```

</details>













































































































































































































































































































































<h2>Client</h2>
<details>
<summary>
Classes
</summary>

```diff
- net.minecraft.network.protocol.game.ClientboundSetSubtitleTextPacket
+ net.minecraft.network.protocol.game.ClientboundSetTimePacket
+ net.minecraft.network.protocol.game.ClientboundSetTitlesAnimationPacket
- net.minecraft.network.protocol.game.ClientboundSetTitleTextPacket
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
- net.minecraft.network.protocol.game.ServerboundContainerButtonClickPacket
+ net.minecraft.network.protocol.game.ServerboundContainerClickPacket
- net.minecraft.network.protocol.game.ServerboundContainerClosePacket
+ net.minecraft.network.protocol.game.ServerboundCustomPayloadPacket
- net.minecraft.network.protocol.game.ServerboundEditBookPacket
+ net.minecraft.network.protocol.game.ServerboundEntityTagQuery
- net.minecraft.network.protocol.game.ServerboundInteractPacket
+ net.minecraft.network.protocol.game.ServerboundInteractPacket$1
- net.minecraft.network.protocol.game.ServerboundInteractPacket$Action
+ net.minecraft.network.protocol.game.ServerboundInteractPacket$ActionType
- net.minecraft.network.protocol.game.ServerboundInteractPacket$Handler
+ net.minecraft.network.protocol.game.ServerboundInteractPacket$InteractionAction
- net.minecraft.network.protocol.game.ServerboundInteractPacket$InteractionAtLocationAction
+ net.minecraft.network.protocol.game.ServerboundJigsawGeneratePacket
- net.minecraft.network.protocol.game.ServerboundKeepAlivePacket
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
+ net.minecraft.network.protocol.game.ServerboundPongPacket
- net.minecraft.network.protocol.game.ServerboundRecipeBookChangeSettingsPacket
+ net.minecraft.network.protocol.game.ServerboundRecipeBookSeenRecipePacket
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
- net.minecraft.obfuscate.DontObfuscate
+ net.minecraft.obfuscate.package-info
- net.minecraft.package-info
+ net.minecraft.realms.DisconnectedRealmsScreen
+ net.minecraft.realms.package-info
- net.minecraft.realms.RealmsConnect
+ net.minecraft.realms.RealmsConnect$1
- net.minecraft.realms.RealmsLabel
+ net.minecraft.realms.RealmsObjectSelectionList
- net.minecraft.realms.RealmsScreen
+ net.minecraft.realms.RepeatedNarrator
- net.minecraft.realms.RepeatedNarrator$Params
- net.minecraft.recipebook.package-info
- net.minecraft.recipebook.PlaceRecipe
+ net.minecraft.recipebook.ServerPlaceRecipe
+ net.minecraft.resources.DelegatingOps
+ net.minecraft.resources.package-info
- net.minecraft.resources.RegistryDataPackCodec
+ net.minecraft.resources.RegistryFileCodec
- net.minecraft.resources.RegistryLookupCodec
+ net.minecraft.resources.RegistryReadOps
- net.minecraft.resources.RegistryReadOps$1
+ net.minecraft.resources.RegistryReadOps$ReadCache
- net.minecraft.resources.RegistryReadOps$ResourceAccess
+ net.minecraft.resources.RegistryReadOps$ResourceAccess$1
- net.minecraft.resources.RegistryReadOps$ResourceAccess$MemoryMap
+ net.minecraft.resources.RegistryWriteOps
- net.minecraft.resources.ResourceKey
+ net.minecraft.resources.ResourceLocation
- net.minecraft.resources.ResourceLocation$Serializer
- net.minecraft.server.Bootstrap
+ net.minecraft.server.Bootstrap$1
- net.minecraft.server.bossevents.CustomBossEvent
+ net.minecraft.server.bossevents.CustomBossEvents
- net.minecraft.server.bossevents.package-info
- net.minecraft.server.ChainedJsonException
+ net.minecraft.server.ChainedJsonException$Entry
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
+ net.minecraft.server.commands.DebugCommand$Tracer
- net.minecraft.server.commands.DebugMobSpawningCommand
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
+ net.minecraft.server.commands.ItemCommands
- net.minecraft.server.commands.JfrCommand
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
+ net.minecraft.server.commands.package-info
- net.minecraft.server.commands.PardonCommand
+ net.minecraft.server.commands.PardonIpCommand
- net.minecraft.server.commands.ParticleCommand
+ net.minecraft.server.commands.PerfCommand
- net.minecraft.server.commands.PlaySoundCommand
+ net.minecraft.server.commands.PublishCommand
- net.minecraft.server.commands.RaidCommand
+ net.minecraft.server.commands.RecipeCommand
- net.minecraft.server.commands.ReloadCommand
+ net.minecraft.server.commands.ResetChunksCommand
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
- net.minecraft.server.ConsoleInput
+ net.minecraft.server.DebugLoggedPrintStream
- net.minecraft.server.dedicated.DedicatedPlayerList
+ net.minecraft.server.dedicated.DedicatedServer
- net.minecraft.server.dedicated.DedicatedServer$1
+ net.minecraft.server.dedicated.DedicatedServerProperties
- net.minecraft.server.dedicated.DedicatedServerSettings
+ net.minecraft.server.dedicated.package-info
+ net.minecraft.server.dedicated.ServerWatchdog
- net.minecraft.server.dedicated.ServerWatchdog$1
+ net.minecraft.server.dedicated.Settings
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
+ net.minecraft.server.level.ChunkHolder$ChunkSaveDebug
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
- net.minecraft.server.level.ChunkTaskPriorityQueueSorter$Message
+ net.minecraft.server.level.ChunkTaskPriorityQueueSorter$Release
- net.minecraft.server.level.ChunkTracker
+ net.minecraft.server.level.ColumnPos
- net.minecraft.server.level.DemoMode
+ net.minecraft.server.level.DistanceManager
- net.minecraft.server.level.DistanceManager$ChunkTicketTracker
+ net.minecraft.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
- net.minecraft.server.level.DistanceManager$PlayerTicketTracker
+ net.minecraft.server.level.package-info
+ net.minecraft.server.level.PlayerMap
- net.minecraft.server.level.PlayerRespawnLogic
- net.minecraft.server.level.progress.ChunkProgressListener
+ net.minecraft.server.level.progress.ChunkProgressListenerFactory
- net.minecraft.server.level.progress.LoggerChunkProgressListener
+ net.minecraft.server.level.progress.package-info
+ net.minecraft.server.level.progress.ProcessorChunkProgressListener
- net.minecraft.server.level.progress.StoringChunkProgressListener
+ net.minecraft.server.level.SectionTracker
- net.minecraft.server.level.ServerBossEvent
+ net.minecraft.server.level.ServerChunkCache
- net.minecraft.server.level.ServerChunkCache$ChunkAndHolder
+ net.minecraft.server.level.ServerChunkCache$MainThreadExecutor
- net.minecraft.server.level.ServerEntity
+ net.minecraft.server.level.ServerLevel
- net.minecraft.server.level.ServerLevel$EntityCallbacks
+ net.minecraft.server.level.ServerPlayer
- net.minecraft.server.level.ServerPlayer$1
+ net.minecraft.server.level.ServerPlayer$2
- net.minecraft.server.level.ServerPlayer$3
+ net.minecraft.server.level.ServerPlayerGameMode
- net.minecraft.server.level.ThreadedLevelLightEngine
+ net.minecraft.server.level.ThreadedLevelLightEngine$TaskType
- net.minecraft.server.level.Ticket
+ net.minecraft.server.level.TicketType
- net.minecraft.server.level.TickingTracker
+ net.minecraft.server.level.WorldGenRegion
- net.minecraft.server.level.WorldGenTickList
+ net.minecraft.server.LoggedPrintStream
- net.minecraft.server.Main
+ net.minecraft.server.Main$1
- net.minecraft.server.MinecraftServer
+ net.minecraft.server.MinecraftServer$1
- net.minecraft.server.MinecraftServer$TimeProfiler
+ net.minecraft.server.MinecraftServer$TimeProfiler$1
- net.minecraft.server.network.LegacyQueryHandler
+ net.minecraft.server.network.MemoryServerHandshakePacketListenerImpl
+ net.minecraft.server.network.package-info
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
- net.minecraft.server.network.TextFilter$FilteredText
+ net.minecraft.server.network.TextFilterClient
- net.minecraft.server.network.TextFilterClient$IgnoreStrategy
+ net.minecraft.server.network.TextFilterClient$PlayerContext
- net.minecraft.server.network.TextFilterClient$RequestFailedException
- net.minecraft.server.package-info
+ net.minecraft.server.packs.AbstractPackResources
- net.minecraft.server.packs.FilePackResources
+ net.minecraft.server.packs.FolderPackResources
+ net.minecraft.server.packs.metadata.MetadataSectionSerializer
- net.minecraft.server.packs.metadata.pack.package-info
- net.minecraft.server.packs.metadata.pack.PackMetadataSection
+ net.minecraft.server.packs.metadata.pack.PackMetadataSectionSerializer
+ net.minecraft.server.packs.metadata.package-info
- net.minecraft.server.packs.package-info
- net.minecraft.server.packs.PackResources
+ net.minecraft.server.packs.PackType
+ net.minecraft.server.packs.repository.FolderRepositorySource
- net.minecraft.server.packs.repository.Pack
+ net.minecraft.server.packs.repository.Pack$PackConstructor
- net.minecraft.server.packs.repository.Pack$Position
- net.minecraft.server.packs.repository.package-info
+ net.minecraft.server.packs.repository.PackCompatibility
- net.minecraft.server.packs.repository.PackRepository
+ net.minecraft.server.packs.repository.PackSource
- net.minecraft.server.packs.repository.RepositorySource
+ net.minecraft.server.packs.repository.ServerPacksSource
- net.minecraft.server.packs.ResourcePackFileNotFoundException
+ net.minecraft.server.packs.resources.FallbackResourceManager
- net.minecraft.server.packs.resources.FallbackResourceManager$LeakedResourceWarningInputStream
+ net.minecraft.server.packs.resources.package-info
+ net.minecraft.server.packs.resources.PreparableReloadListener
- net.minecraft.server.packs.resources.PreparableReloadListener$PreparationBarrier
+ net.minecraft.server.packs.resources.ProfiledReloadInstance
- net.minecraft.server.packs.resources.ProfiledReloadInstance$State
- net.minecraft.server.packs.resources.ReloadableResourceManager
+ net.minecraft.server.packs.resources.ReloadInstance
+ net.minecraft.server.packs.resources.Resource
- net.minecraft.server.packs.resources.ResourceManager
+ net.minecraft.server.packs.resources.ResourceManager$Empty
- net.minecraft.server.packs.resources.ResourceManagerReloadListener
+ net.minecraft.server.packs.resources.ResourceProvider
- net.minecraft.server.packs.resources.SimpleJsonResourceReloadListener
+ net.minecraft.server.packs.resources.SimplePreparableReloadListener
+ net.minecraft.server.packs.resources.SimpleReloadableResourceManager
- net.minecraft.server.packs.resources.SimpleReloadableResourceManager$FailingReloadInstance
+ net.minecraft.server.packs.resources.SimpleReloadableResourceManager$ResourcePackLoadingFailure
- net.minecraft.server.packs.resources.SimpleReloadInstance
+ net.minecraft.server.packs.resources.SimpleReloadInstance$1
- net.minecraft.server.packs.resources.SimpleReloadInstance$StateFactory
- net.minecraft.server.packs.resources.SimpleResource
+ net.minecraft.server.packs.VanillaPackResources
- net.minecraft.server.packs.VanillaPackResources$1
- net.minecraft.server.PlayerAdvancements
+ net.minecraft.server.PlayerAdvancements$1
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
- net.minecraft.server.RunningOnDifferentThreadException
+ net.minecraft.server.ServerAdvancementManager
- net.minecraft.server.ServerFunctionLibrary
+ net.minecraft.server.ServerFunctionManager
- net.minecraft.server.ServerFunctionManager$ExecutionContext
+ net.minecraft.server.ServerFunctionManager$QueuedCommand
- net.minecraft.server.ServerFunctionManager$TraceCallbacks
+ net.minecraft.server.ServerInterface
- net.minecraft.server.ServerResources
+ net.minecraft.server.ServerScoreboard
- net.minecraft.server.ServerScoreboard$Method
+ net.minecraft.server.TickTask
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
- net.minecraft.tags.BlockTags
+ net.minecraft.tags.EntityTypeTags
- net.minecraft.tags.FluidTags
+ net.minecraft.tags.GameEventTags
- net.minecraft.tags.ItemTags
+ net.minecraft.tags.package-info
+ net.minecraft.tags.SerializationTags
- net.minecraft.tags.SetTag
+ net.minecraft.tags.StaticTagHelper
- net.minecraft.tags.StaticTagHelper$Wrapper
+ net.minecraft.tags.StaticTags
- net.minecraft.tags.Tag
+ net.minecraft.tags.Tag$Builder
- net.minecraft.tags.Tag$BuilderEntry
+ net.minecraft.tags.Tag$ElementEntry
- net.minecraft.tags.Tag$Entry
+ net.minecraft.tags.Tag$Named
- net.minecraft.tags.Tag$OptionalElementEntry
+ net.minecraft.tags.Tag$OptionalTagEntry
- net.minecraft.tags.Tag$TagEntry
+ net.minecraft.tags.TagCollection
- net.minecraft.tags.TagCollection$1
+ net.minecraft.tags.TagCollection$NetworkPayload
- net.minecraft.tags.TagContainer
+ net.minecraft.tags.TagContainer$1
- net.minecraft.tags.TagContainer$Builder
+ net.minecraft.tags.TagContainer$CollectionConsumer
- net.minecraft.tags.TagLoader
+ net.minecraft.tags.TagManager
- net.minecraft.tags.TagManager$LoaderInfo
- net.minecraft.util.BitStorage
+ net.minecraft.util.ClassInstanceMultiMap
- net.minecraft.util.CrudeIncrementalIntIdentityHashBiMap
+ net.minecraft.util.Crypt
- net.minecraft.util.CryptException
+ net.minecraft.util.CsvOutput
- net.minecraft.util.CsvOutput$Builder
+ net.minecraft.util.CubicSampler
- net.minecraft.util.CubicSampler$Vec3Fetcher
+ net.minecraft.util.CubicSpline
- net.minecraft.util.CubicSpline$Builder
+ net.minecraft.util.CubicSpline$Constant
- net.minecraft.util.datafix.DataFixers
+ net.minecraft.util.datafix.DataFixers$1
- net.minecraft.util.datafix.DataFixers$2
+ net.minecraft.util.datafix.DataFixTypes
- net.minecraft.util.datafix.fixes.AbstractArrowPickupFix
+ net.minecraft.util.datafix.fixes.AbstractUUIDFix
- net.minecraft.util.datafix.fixes.AddFlagIfNotPresentFix
+ net.minecraft.util.datafix.fixes.AddNewChoices
- net.minecraft.util.datafix.fixes.AdvancementsFix
+ net.minecraft.util.datafix.fixes.AdvancementsRenameFix
- net.minecraft.util.datafix.fixes.AttributesRename
+ net.minecraft.util.datafix.fixes.BedBlockEntityInjecter
- net.minecraft.util.datafix.fixes.BedItemColorFix
+ net.minecraft.util.datafix.fixes.BeehivePoiRenameFix
- net.minecraft.util.datafix.fixes.BiomeFix
+ net.minecraft.util.datafix.fixes.BitStorageAlignFix
- net.minecraft.util.datafix.fixes.BlockEntityBannerColorFix
+ net.minecraft.util.datafix.fixes.BlockEntityBlockStateFix
- net.minecraft.util.datafix.fixes.BlockEntityCustomNameToComponentFix
+ net.minecraft.util.datafix.fixes.BlockEntityIdFix
- net.minecraft.util.datafix.fixes.BlockEntityJukeboxFix
+ net.minecraft.util.datafix.fixes.BlockEntityKeepPacked
- net.minecraft.util.datafix.fixes.BlockEntityShulkerBoxColorFix
+ net.minecraft.util.datafix.fixes.BlockEntitySignTextStrictJsonFix
- net.minecraft.util.datafix.fixes.BlockEntitySignTextStrictJsonFix$1
+ net.minecraft.util.datafix.fixes.BlockEntityUUIDFix
- net.minecraft.util.datafix.fixes.BlockNameFlatteningFix
+ net.minecraft.util.datafix.fixes.BlockRenameFix
- net.minecraft.util.datafix.fixes.BlockRenameFix$1
+ net.minecraft.util.datafix.fixes.BlockRenameFixWithJigsaw
- net.minecraft.util.datafix.fixes.BlockRenameFixWithJigsaw$1
+ net.minecraft.util.datafix.fixes.BlockStateData
- net.minecraft.util.datafix.fixes.BlockStateStructureTemplateFix
+ net.minecraft.util.datafix.fixes.CatTypeFix
- net.minecraft.util.datafix.fixes.CauldronRenameFix
+ net.minecraft.util.datafix.PackedBitStorage
- net.minecraft.util.DebugBuffer
+ net.minecraft.util.DirectoryLock
- net.minecraft.util.DirectoryLock$LockException
+ net.minecraft.util.ExceptionCollector
- net.minecraft.util.ExtraCodecs
+ net.minecraft.util.ExtraCodecs$EitherCodec
- net.minecraft.util.ExtraCodecs$XorCodec
+ net.minecraft.util.FastColor
- net.minecraft.util.FastColor$ARGB32
+ net.minecraft.util.FileZipper
- net.minecraft.util.FormattedCharSequence
+ net.minecraft.util.FormattedCharSink
- net.minecraft.util.FrameTimer
+ net.minecraft.util.Graph
- net.minecraft.util.GsonHelper
+ net.minecraft.util.HttpUtil
- net.minecraft.util.InclusiveRange
+ net.minecraft.util.LazyLoadedValue
- net.minecraft.util.LinearCongruentialGenerator
+ net.minecraft.util.LowerCaseEnumTypeAdapterFactory
- net.minecraft.util.LowerCaseEnumTypeAdapterFactory$1
+ net.minecraft.util.MemoryReserve
- net.minecraft.util.Mth
+ net.minecraft.util.NativeModuleLister
- net.minecraft.util.NativeModuleLister$NativeModuleInfo
+ net.minecraft.util.NativeModuleLister$NativeModuleVersion
- net.minecraft.util.ParticleUtils
+ net.minecraft.util.ProgressListener
- net.minecraft.util.RewindableStream
+ net.minecraft.util.RewindableStream$1
- net.minecraft.util.SimpleBitStorage
+ net.minecraft.util.SmoothDouble
- net.minecraft.util.SortedArraySet
+ net.minecraft.util.SortedArraySet$ArrayIterator
- net.minecraft.util.StringDecomposer
+ net.minecraft.util.StringRepresentable
- net.minecraft.util.StringRepresentable$1
+ net.minecraft.util.StringRepresentable$2
- net.minecraft.util.StringUtil
+ net.minecraft.util.TelemetryConstants
- net.minecraft.util.ThreadingDetector
+ net.minecraft.util.TimeUtil
- net.minecraft.util.ToFloatFunction
+ net.minecraft.util.Tuple
- net.minecraft.util.Unit
+ net.minecraft.util.VisibleForDebug
- net.minecraft.util.ZeroBitStorage
+ net.minecraft.world.entity.ai.memory.package-info
- net.minecraft.world.entity.ai.memory.WalkTarget
- net.minecraft.world.entity.ai.navigation.FlyingPathNavigation
+ net.minecraft.world.entity.ai.navigation.GroundPathNavigation
+ net.minecraft.world.entity.ai.navigation.package-info
- net.minecraft.world.entity.ai.navigation.PathNavigation
+ net.minecraft.world.entity.ai.navigation.WallClimberNavigation
- net.minecraft.world.entity.ai.navigation.WaterBoundPathNavigation
- net.minecraft.world.entity.ai.package-info
+ net.minecraft.world.entity.ai.sensing.AdultSensor
- net.minecraft.world.entity.ai.sensing.AxolotlAttackablesSensor
+ net.minecraft.world.entity.ai.sensing.DummySensor
- net.minecraft.world.entity.ai.sensing.GolemSensor
+ net.minecraft.world.entity.ai.sensing.HoglinSpecificSensor
- net.minecraft.world.entity.ai.sensing.HurtBySensor
+ net.minecraft.world.entity.ai.sensing.NearestBedSensor
- net.minecraft.world.entity.ai.sensing.NearestItemSensor
+ net.minecraft.world.entity.ai.sensing.NearestLivingEntitySensor
- net.minecraft.world.entity.ai.sensing.NearestVisibleLivingEntitySensor
+ net.minecraft.world.entity.ai.sensing.package-info
+ net.minecraft.world.entity.ai.sensing.PiglinBruteSpecificSensor
- net.minecraft.world.entity.ai.sensing.PiglinSpecificSensor
+ net.minecraft.world.entity.ai.sensing.PlayerSensor
- net.minecraft.world.entity.ai.sensing.SecondaryPoiSensor
+ net.minecraft.world.entity.ai.sensing.Sensing
- net.minecraft.world.entity.ai.sensing.Sensor
+ net.minecraft.world.entity.ai.sensing.SensorType
- net.minecraft.world.entity.ai.sensing.TemptingSensor
+ net.minecraft.world.entity.ai.sensing.VillagerBabiesSensor
- net.minecraft.world.entity.ai.sensing.VillagerHostilesSensor
+ net.minecraft.world.entity.ai.targeting.package-info
- net.minecraft.world.entity.ai.targeting.TargetingConditions
- net.minecraft.world.entity.ai.util.AirAndWaterRandomPos
+ net.minecraft.world.entity.ai.util.AirRandomPos
- net.minecraft.world.entity.ai.util.DefaultRandomPos
+ net.minecraft.world.entity.ai.util.GoalUtils
- net.minecraft.world.entity.ai.util.HoverRandomPos
+ net.minecraft.world.entity.ai.util.LandRandomPos
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
- net.minecraft.world.entity.animal.axolotl.Axolotl
+ net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlGroupData
- net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlLookControl
+ net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlMoveControl
- net.minecraft.world.entity.animal.axolotl.Axolotl$AxolotlPathNavigation
+ net.minecraft.world.entity.animal.axolotl.Axolotl$Variant
- net.minecraft.world.entity.animal.axolotl.AxolotlAi
+ net.minecraft.world.entity.animal.axolotl.package-info
+ net.minecraft.world.entity.animal.axolotl.PlayDead
- net.minecraft.world.entity.animal.axolotl.ValidatePlayDead
- net.minecraft.world.entity.animal.Bee
+ net.minecraft.world.entity.animal.Bee$1
- net.minecraft.world.entity.animal.Bee$BaseBeeGoal
+ net.minecraft.world.entity.animal.Bee$BeeAttackGoal
- net.minecraft.world.entity.animal.Bee$BeeBecomeAngryTargetGoal
+ net.minecraft.world.entity.animal.Bee$BeeEnterHiveGoal
- net.minecraft.world.entity.animal.Bee$BeeGoToHiveGoal
+ net.minecraft.world.entity.animal.Bee$BeeGoToKnownFlowerGoal
- net.minecraft.world.entity.animal.Bee$BeeGrowCropGoal
+ net.minecraft.world.entity.animal.Bee$BeeHurtByOtherGoal
- net.minecraft.world.entity.animal.Bee$BeeLocateHiveGoal
+ net.minecraft.world.entity.animal.Bee$BeeLookControl
- net.minecraft.world.entity.animal.Bee$BeePollinateGoal
+ net.minecraft.world.entity.animal.Bee$BeeWanderGoal
- net.minecraft.world.entity.animal.Bucketable
+ net.minecraft.world.entity.animal.Cat
- net.minecraft.world.entity.animal.Cat$CatAvoidEntityGoal
+ net.minecraft.world.entity.animal.Cat$CatRelaxOnOwnerGoal
- net.minecraft.world.entity.animal.Cat$CatTemptGoal
+ net.minecraft.world.entity.animal.Chicken
- net.minecraft.world.entity.animal.Cod
+ net.minecraft.world.entity.animal.Cow
- net.minecraft.world.entity.animal.Dolphin
+ net.minecraft.world.entity.animal.Dolphin$DolphinSwimToTreasureGoal
- net.minecraft.world.entity.animal.Dolphin$DolphinSwimWithPlayerGoal
+ net.minecraft.world.entity.animal.Dolphin$PlayWithItemsGoal
- net.minecraft.world.entity.animal.FlyingAnimal
+ net.minecraft.world.entity.animal.Fox
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
- net.minecraft.world.entity.animal.goat.Goat
+ net.minecraft.world.entity.animal.goat.Goat$GoatNodeEvaluator
- net.minecraft.world.entity.animal.goat.Goat$GoatPathNavigation
+ net.minecraft.world.entity.animal.goat.GoatAi
- net.minecraft.world.entity.animal.goat.package-info
+ net.minecraft.world.entity.animal.horse.AbstractChestedHorse
- net.minecraft.world.entity.animal.horse.AbstractChestedHorse$1
+ net.minecraft.world.entity.animal.horse.AbstractHorse
- net.minecraft.world.entity.animal.horse.AbstractHorse$1
+ net.minecraft.world.entity.animal.horse.Donkey
- net.minecraft.world.entity.animal.horse.Horse
+ net.minecraft.world.entity.animal.horse.Horse$HorseGroupData
- net.minecraft.world.entity.animal.horse.Llama
+ net.minecraft.world.entity.animal.horse.Llama$LlamaAttackWolfGoal
- net.minecraft.world.entity.animal.horse.Llama$LlamaGroupData
+ net.minecraft.world.entity.animal.horse.Llama$LlamaHurtByTargetGoal
- net.minecraft.world.entity.animal.horse.Markings
+ net.minecraft.world.entity.animal.horse.Mule
- net.minecraft.world.entity.animal.horse.package-info
- net.minecraft.world.entity.animal.horse.SkeletonHorse
+ net.minecraft.world.entity.animal.horse.SkeletonTrapGoal
- net.minecraft.world.entity.animal.horse.TraderLlama
+ net.minecraft.world.entity.animal.horse.TraderLlama$TraderLlamaDefendWanderingTraderGoal
- net.minecraft.world.entity.animal.horse.Variant
+ net.minecraft.world.entity.animal.horse.ZombieHorse
- net.minecraft.world.entity.animal.IronGolem
+ net.minecraft.world.entity.animal.IronGolem$Crackiness
- net.minecraft.world.entity.animal.MushroomCow
+ net.minecraft.world.entity.animal.MushroomCow$MushroomType
- net.minecraft.world.entity.animal.Ocelot
+ net.minecraft.world.entity.animal.Ocelot$OcelotAvoidEntityGoal
- net.minecraft.world.entity.animal.Ocelot$OcelotTemptGoal
+ net.minecraft.world.entity.animal.package-info
+ net.minecraft.world.entity.animal.Panda
- net.minecraft.world.entity.animal.Panda$Gene
+ net.minecraft.world.entity.animal.Panda$PandaAttackGoal
- net.minecraft.world.entity.animal.Panda$PandaAvoidGoal
+ net.minecraft.world.entity.animal.Panda$PandaBreedGoal
- net.minecraft.world.entity.animal.Panda$PandaHurtByTargetGoal
+ net.minecraft.world.entity.animal.Panda$PandaLieOnBackGoal
- net.minecraft.world.entity.animal.Panda$PandaLookAtPlayerGoal
+ net.minecraft.world.entity.animal.Panda$PandaMoveControl
- net.minecraft.world.entity.animal.Panda$PandaPanicGoal
+ net.minecraft.world.entity.animal.Panda$PandaRollGoal
- net.minecraft.world.entity.animal.Panda$PandaSitGoal
+ net.minecraft.world.entity.animal.Panda$PandaSneezeGoal
- net.minecraft.world.entity.animal.Parrot
+ net.minecraft.world.entity.animal.Parrot$1
- net.minecraft.world.entity.animal.Parrot$ParrotWanderGoal
+ net.minecraft.world.entity.animal.Pig
- net.minecraft.world.entity.animal.PolarBear
+ net.minecraft.world.entity.animal.PolarBear$PolarBearAttackPlayersGoal
- net.minecraft.world.entity.animal.PolarBear$PolarBearHurtByTargetGoal
+ net.minecraft.world.entity.animal.PolarBear$PolarBearMeleeAttackGoal
- net.minecraft.world.entity.animal.PolarBear$PolarBearPanicGoal
+ net.minecraft.world.entity.animal.Pufferfish
- net.minecraft.world.entity.animal.Pufferfish$PufferfishPuffGoal
+ net.minecraft.world.entity.animal.Rabbit
- net.minecraft.world.entity.animal.Rabbit$EvilRabbitAttackGoal
+ net.minecraft.world.entity.animal.Rabbit$RabbitAvoidEntityGoal
- net.minecraft.world.entity.animal.Rabbit$RabbitGroupData
+ net.minecraft.world.entity.animal.Rabbit$RabbitJumpControl
- net.minecraft.world.entity.animal.Rabbit$RabbitMoveControl
+ net.minecraft.world.entity.animal.Rabbit$RabbitPanicGoal
- net.minecraft.world.entity.animal.Rabbit$RaidGardenGoal
+ net.minecraft.world.entity.animal.Salmon
- net.minecraft.world.entity.animal.Sheep
+ net.minecraft.world.entity.animal.Sheep$1
- net.minecraft.world.entity.animal.Sheep$2
+ net.minecraft.world.entity.animal.ShoulderRidingEntity
- net.minecraft.world.entity.animal.SnowGolem
+ net.minecraft.world.entity.animal.Squid
- net.minecraft.world.entity.animal.Squid$SquidFleeGoal
+ net.minecraft.world.entity.animal.Squid$SquidRandomMovementGoal
- net.minecraft.world.entity.animal.TropicalFish
+ net.minecraft.world.entity.animal.TropicalFish$Pattern
- net.minecraft.world.entity.animal.TropicalFish$TropicalFishGroupData
+ net.minecraft.world.entity.animal.Turtle
- net.minecraft.world.entity.animal.Turtle$TurtleBreedGoal
+ net.minecraft.world.entity.animal.Turtle$TurtleGoHomeGoal
- net.minecraft.world.entity.animal.Turtle$TurtleGoToWaterGoal
+ net.minecraft.world.entity.animal.Turtle$TurtleLayEggGoal
- net.minecraft.world.entity.animal.Turtle$TurtleMoveControl
+ net.minecraft.world.entity.animal.Turtle$TurtlePanicGoal
- net.minecraft.world.entity.animal.Turtle$TurtlePathNavigation
+ net.minecraft.world.entity.animal.Turtle$TurtleRandomStrollGoal
- net.minecraft.world.entity.animal.Turtle$TurtleTravelGoal
+ net.minecraft.world.entity.animal.WaterAnimal
- net.minecraft.world.entity.animal.Wolf
+ net.minecraft.world.entity.animal.Wolf$WolfAvoidEntityGoal
+ net.minecraft.world.entity.boss.enderdragon.EndCrystal
- net.minecraft.world.entity.boss.enderdragon.EnderDragon
+ net.minecraft.world.entity.boss.enderdragon.package-info
- net.minecraft.world.entity.boss.enderdragon.phases.AbstractDragonPhaseInstance
+ net.minecraft.world.entity.boss.enderdragon.phases.AbstractDragonSittingPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonChargePlayerPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonDeathPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonHoldingPatternPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonHoverPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonLandingApproachPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonLandingPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonPhaseInstance
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonSittingAttackingPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonSittingFlamingPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonSittingScanningPhase
- net.minecraft.world.entity.boss.enderdragon.phases.DragonStrafePlayerPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.DragonTakeoffPhase
- net.minecraft.world.entity.boss.enderdragon.phases.EnderDragonPhase
+ net.minecraft.world.entity.boss.enderdragon.phases.EnderDragonPhaseManager
- net.minecraft.world.entity.boss.enderdragon.phases.package-info
- net.minecraft.world.entity.boss.EnderDragonPart
+ net.minecraft.world.entity.boss.package-info
- net.minecraft.world.entity.boss.wither.package-info
- net.minecraft.world.entity.boss.wither.WitherBoss
+ net.minecraft.world.entity.boss.wither.WitherBoss$WitherDoNothingGoal
+ net.minecraft.world.entity.decoration.ArmorStand
- net.minecraft.world.entity.decoration.ArmorStand$1
+ net.minecraft.world.entity.decoration.GlowItemFrame
- net.minecraft.world.entity.decoration.HangingEntity
+ net.minecraft.world.entity.decoration.HangingEntity$1
- net.minecraft.world.entity.decoration.ItemFrame
+ net.minecraft.world.entity.decoration.ItemFrame$1
- net.minecraft.world.entity.decoration.ItemFrame$2
+ net.minecraft.world.entity.decoration.LeashFenceKnotEntity
- net.minecraft.world.entity.decoration.Motive
- net.minecraft.world.entity.decoration.package-info
+ net.minecraft.world.entity.decoration.Painting
+ net.minecraft.world.entity.item.FallingBlockEntity
- net.minecraft.world.entity.item.ItemEntity
- net.minecraft.world.entity.item.package-info
+ net.minecraft.world.entity.item.PrimedTnt
+ net.minecraft.world.entity.monster.AbstractIllager
- net.minecraft.world.entity.monster.AbstractIllager$IllagerArmPose
+ net.minecraft.world.entity.monster.AbstractIllager$RaiderOpenDoorGoal
- net.minecraft.world.entity.monster.AbstractSkeleton
+ net.minecraft.world.entity.monster.AbstractSkeleton$1
- net.minecraft.world.entity.monster.Blaze
+ net.minecraft.world.entity.monster.Blaze$BlazeAttackGoal
- net.minecraft.world.entity.monster.CaveSpider
+ net.minecraft.world.entity.monster.Creeper
- net.minecraft.world.entity.monster.CrossbowAttackMob
+ net.minecraft.world.entity.monster.Drowned
- net.minecraft.world.entity.monster.Drowned$DrownedAttackGoal
+ net.minecraft.world.entity.monster.Drowned$DrownedGoToBeachGoal
- net.minecraft.world.entity.monster.Drowned$DrownedGoToWaterGoal
+ net.minecraft.world.entity.monster.Drowned$DrownedMoveControl
- net.minecraft.world.entity.monster.Drowned$DrownedSwimUpGoal
+ net.minecraft.world.entity.monster.Drowned$DrownedTridentAttackGoal
- net.minecraft.world.entity.monster.ElderGuardian
+ net.minecraft.world.entity.monster.EnderMan
- net.minecraft.world.entity.monster.EnderMan$EndermanFreezeWhenLookedAt
+ net.minecraft.world.entity.monster.EnderMan$EndermanLeaveBlockGoal
- net.minecraft.world.entity.monster.EnderMan$EndermanLookForPlayerGoal
+ net.minecraft.world.entity.monster.EnderMan$EndermanTakeBlockGoal
- net.minecraft.world.entity.monster.Endermite
+ net.minecraft.world.entity.monster.Enemy
- net.minecraft.world.entity.monster.Evoker
+ net.minecraft.world.entity.monster.Evoker$EvokerAttackSpellGoal
- net.minecraft.world.entity.monster.Evoker$EvokerCastingSpellGoal
+ net.minecraft.world.entity.monster.Evoker$EvokerSummonSpellGoal
- net.minecraft.world.entity.monster.Evoker$EvokerWololoSpellGoal
+ net.minecraft.world.entity.monster.Ghast
- net.minecraft.world.entity.monster.Ghast$GhastLookGoal
+ net.minecraft.world.entity.monster.Ghast$GhastMoveControl
- net.minecraft.world.entity.monster.Ghast$GhastShootFireballGoal
+ net.minecraft.world.entity.monster.Ghast$RandomFloatAroundGoal
- net.minecraft.world.entity.monster.Giant
+ net.minecraft.world.entity.monster.Guardian
- net.minecraft.world.entity.monster.Guardian$GuardianAttackGoal
+ net.minecraft.world.entity.monster.Guardian$GuardianAttackSelector
- net.minecraft.world.entity.monster.Guardian$GuardianMoveControl
+ net.minecraft.world.entity.monster.hoglin.Hoglin
- net.minecraft.world.entity.monster.hoglin.HoglinAi
+ net.minecraft.world.entity.monster.hoglin.HoglinBase
- net.minecraft.world.entity.monster.hoglin.package-info
+ net.minecraft.world.entity.monster.Husk
- net.minecraft.world.entity.monster.Illusioner
+ net.minecraft.world.entity.monster.Illusioner$IllusionerBlindnessSpellGoal
- net.minecraft.world.entity.monster.Illusioner$IllusionerMirrorSpellGoal
+ net.minecraft.world.entity.monster.MagmaCube
- net.minecraft.world.entity.monster.Monster
+ net.minecraft.world.entity.monster.package-info
+ net.minecraft.world.entity.monster.PatrollingMonster
- net.minecraft.world.entity.monster.PatrollingMonster$LongDistancePatrolGoal
+ net.minecraft.world.entity.monster.Phantom
- net.minecraft.world.entity.monster.Phantom$AttackPhase
+ net.minecraft.world.entity.monster.Phantom$PhantomAttackPlayerTargetGoal
- net.minecraft.world.entity.monster.Phantom$PhantomAttackStrategyGoal
+ net.minecraft.world.entity.monster.Phantom$PhantomBodyRotationControl
- net.minecraft.world.entity.monster.Phantom$PhantomCircleAroundAnchorGoal
+ net.minecraft.world.entity.monster.Phantom$PhantomLookControl
- net.minecraft.world.entity.monster.Phantom$PhantomMoveControl
+ net.minecraft.world.entity.monster.Phantom$PhantomMoveTargetGoal
- net.minecraft.world.entity.monster.Phantom$PhantomSweepAttackGoal
- net.minecraft.world.entity.monster.piglin.AbstractPiglin
- net.minecraft.world.entity.monster.piglin.package-info
+ net.minecraft.world.entity.monster.piglin.Piglin
- net.minecraft.world.entity.monster.piglin.PiglinAi
+ net.minecraft.world.entity.monster.piglin.PiglinArmPose
- net.minecraft.world.entity.monster.piglin.PiglinBrute
+ net.minecraft.world.entity.monster.piglin.PiglinBruteAi
- net.minecraft.world.entity.monster.piglin.RememberIfHoglinWasKilled
+ net.minecraft.world.entity.monster.piglin.StartAdmiringItemIfSeen
- net.minecraft.world.entity.monster.piglin.StartHuntingHoglin
+ net.minecraft.world.entity.monster.piglin.StopAdmiringIfItemTooFarAway
- net.minecraft.world.entity.monster.piglin.StopAdmiringIfTiredOfTryingToReachItem
+ net.minecraft.world.entity.monster.piglin.StopHoldingItemIfNoLongerAdmiring
+ net.minecraft.world.entity.monster.Pillager
- net.minecraft.world.entity.monster.RangedAttackMob
+ net.minecraft.world.entity.monster.Ravager
- net.minecraft.world.entity.monster.Ravager$RavagerMeleeAttackGoal
+ net.minecraft.world.entity.monster.Ravager$RavagerNavigation
- net.minecraft.world.entity.monster.Ravager$RavagerNodeEvaluator
+ net.minecraft.world.entity.monster.Shulker
- net.minecraft.world.entity.monster.Shulker$ShulkerAttackGoal
+ net.minecraft.world.entity.monster.Shulker$ShulkerBodyRotationControl
- net.minecraft.world.entity.monster.Shulker$ShulkerDefenseAttackGoal
+ net.minecraft.world.entity.monster.Shulker$ShulkerLookControl
- net.minecraft.world.entity.monster.Shulker$ShulkerNearestAttackGoal
+ net.minecraft.world.entity.monster.Shulker$ShulkerPeekGoal
- net.minecraft.world.entity.monster.Silverfish
+ net.minecraft.world.entity.monster.Silverfish$SilverfishMergeWithStoneGoal
- net.minecraft.world.entity.monster.Silverfish$SilverfishWakeUpFriendsGoal
+ net.minecraft.world.entity.monster.Skeleton
- net.minecraft.world.entity.monster.Slime
+ net.minecraft.world.entity.monster.Slime$SlimeAttackGoal
- net.minecraft.world.entity.monster.Slime$SlimeFloatGoal
+ net.minecraft.world.entity.monster.Slime$SlimeKeepOnJumpingGoal
- net.minecraft.world.entity.monster.Slime$SlimeMoveControl
+ net.minecraft.world.entity.monster.Slime$SlimeRandomDirectionGoal
- net.minecraft.world.entity.monster.SpellcasterIllager
+ net.minecraft.world.entity.monster.SpellcasterIllager$IllagerSpell
- net.minecraft.world.entity.monster.SpellcasterIllager$SpellcasterCastingSpellGoal
+ net.minecraft.world.entity.monster.SpellcasterIllager$SpellcasterUseSpellGoal
- net.minecraft.world.entity.monster.Spider
+ net.minecraft.world.entity.monster.Spider$SpiderAttackGoal
- net.minecraft.world.entity.monster.Spider$SpiderEffectsGroupData
+ net.minecraft.world.entity.monster.Spider$SpiderTargetGoal
- net.minecraft.world.entity.monster.Stray
+ net.minecraft.world.entity.monster.Strider
- net.minecraft.world.entity.monster.Strider$StriderGoToLavaGoal
+ net.minecraft.world.entity.monster.Strider$StriderPathNavigation
- net.minecraft.world.entity.monster.Vex
+ net.minecraft.world.entity.monster.Vex$VexChargeAttackGoal
- net.minecraft.world.entity.monster.Vex$VexCopyOwnerTargetGoal
+ net.minecraft.world.entity.monster.Vex$VexMoveControl
- net.minecraft.world.entity.monster.Vex$VexRandomMoveGoal
+ net.minecraft.world.entity.monster.Vindicator
- net.minecraft.world.entity.monster.Vindicator$VindicatorBreakDoorGoal
+ net.minecraft.world.entity.monster.Vindicator$VindicatorJohnnyAttackGoal
- net.minecraft.world.entity.monster.Vindicator$VindicatorMeleeAttackGoal
+ net.minecraft.world.entity.monster.Witch
- net.minecraft.world.entity.monster.WitherSkeleton
+ net.minecraft.world.entity.monster.Zoglin
- net.minecraft.world.entity.monster.Zombie
+ net.minecraft.world.entity.monster.Zombie$ZombieAttackTurtleEggGoal
- net.minecraft.world.entity.monster.Zombie$ZombieGroupData
+ net.minecraft.world.entity.monster.ZombieVillager
- net.minecraft.world.entity.monster.ZombifiedPiglin
+ net.minecraft.world.entity.npc.AbstractVillager
- net.minecraft.world.entity.npc.CatSpawner
+ net.minecraft.world.entity.npc.ClientSideMerchant
- net.minecraft.world.entity.npc.InventoryCarrier
+ net.minecraft.world.entity.npc.Npc
- net.minecraft.world.entity.npc.package-info
- net.minecraft.world.entity.npc.Villager
+ net.minecraft.world.entity.npc.VillagerData
- net.minecraft.world.entity.npc.VillagerDataHolder
+ net.minecraft.world.entity.npc.VillagerProfession
- net.minecraft.world.entity.npc.VillagerTrades
+ net.minecraft.world.entity.npc.VillagerTrades$DyedArmorForEmeralds
- net.minecraft.world.entity.npc.VillagerTrades$EmeraldForItems
+ net.minecraft.world.entity.npc.VillagerTrades$EmeraldsForVillagerTypeItem
- net.minecraft.world.entity.npc.VillagerTrades$EnchantBookForEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$EnchantedItemForEmeralds
- net.minecraft.world.entity.npc.VillagerTrades$ItemListing
+ net.minecraft.world.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
- net.minecraft.world.entity.npc.VillagerTrades$ItemsForEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$SuspiciousStewForEmerald
- net.minecraft.world.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$TreasureMapForEmeralds
- net.minecraft.world.entity.npc.VillagerType
+ net.minecraft.world.entity.npc.WanderingTrader
- net.minecraft.world.entity.npc.WanderingTrader$WanderToPositionGoal
+ net.minecraft.world.entity.npc.WanderingTraderSpawner
+ net.minecraft.world.entity.package-info
- net.minecraft.world.entity.player.Abilities
+ net.minecraft.world.entity.player.ChatVisiblity
- net.minecraft.world.entity.player.Inventory
+ net.minecraft.world.entity.player.package-info
+ net.minecraft.world.entity.player.Player
- net.minecraft.world.entity.player.Player$1
+ net.minecraft.world.entity.player.Player$BedSleepingProblem
- net.minecraft.world.entity.player.PlayerModelPart
+ net.minecraft.world.entity.player.StackedContents
- net.minecraft.world.entity.player.StackedContents$RecipePicker
- net.minecraft.world.entity.projectile.AbstractArrow
+ net.minecraft.world.entity.projectile.AbstractArrow$1
- net.minecraft.world.entity.projectile.AbstractArrow$Pickup
+ net.minecraft.world.entity.projectile.AbstractHurtingProjectile
- net.minecraft.world.entity.projectile.Arrow
+ net.minecraft.world.entity.projectile.DragonFireball
- net.minecraft.world.entity.projectile.EvokerFangs
+ net.minecraft.world.entity.projectile.EyeOfEnder
- net.minecraft.world.entity.projectile.Fireball
+ net.minecraft.world.entity.projectile.FireworkRocketEntity
- net.minecraft.world.entity.projectile.FishingHook
+ net.minecraft.world.entity.projectile.FishingHook$1
- net.minecraft.world.entity.projectile.FishingHook$FishHookState
+ net.minecraft.world.entity.projectile.FishingHook$OpenWaterType
- net.minecraft.world.entity.projectile.ItemSupplier
+ net.minecraft.world.entity.projectile.LargeFireball
- net.minecraft.world.entity.projectile.LlamaSpit
+ net.minecraft.world.entity.projectile.package-info
+ net.minecraft.world.entity.projectile.Projectile
- net.minecraft.world.entity.projectile.ProjectileUtil
+ net.minecraft.world.entity.projectile.ShulkerBullet
- net.minecraft.world.entity.projectile.SmallFireball
+ net.minecraft.world.entity.projectile.Snowball
- net.minecraft.world.entity.projectile.SpectralArrow
+ net.minecraft.world.entity.projectile.ThrowableItemProjectile
- net.minecraft.world.entity.projectile.ThrowableProjectile
+ net.minecraft.world.entity.projectile.ThrownEgg
- net.minecraft.world.entity.projectile.ThrownEnderpearl
+ net.minecraft.world.entity.projectile.ThrownExperienceBottle
- net.minecraft.world.entity.projectile.ThrownPotion
+ net.minecraft.world.entity.projectile.ThrownTrident
- net.minecraft.world.entity.projectile.WitherSkull
- net.minecraft.world.entity.raid.package-info
- net.minecraft.world.entity.raid.Raid
+ net.minecraft.world.entity.raid.Raid$1
+ net.minecraft.world.entity.raid.Raid$RaiderType
- net.minecraft.world.entity.raid.Raid$RaidStatus
- net.minecraft.world.entity.raid.Raider
+ net.minecraft.world.entity.raid.Raider$HoldGroundAttackGoal
- net.minecraft.world.entity.raid.Raider$ObtainRaidLeaderBannerGoal
+ net.minecraft.world.entity.raid.Raider$RaiderCelebration
- net.minecraft.world.entity.raid.Raider$RaiderMoveThroughVillageGoal
+ net.minecraft.world.entity.raid.Raids
+ net.minecraft.world.entity.schedule.Activity
- net.minecraft.world.entity.schedule.Keyframe
+ net.minecraft.world.entity.schedule.package-info
+ net.minecraft.world.entity.schedule.Schedule
- net.minecraft.world.entity.schedule.ScheduleBuilder
+ net.minecraft.world.entity.schedule.ScheduleBuilder$ActivityTransition
- net.minecraft.world.entity.schedule.Timeline
- net.minecraft.world.entity.vehicle.AbstractMinecart
+ net.minecraft.world.entity.vehicle.AbstractMinecart$1
- net.minecraft.world.entity.vehicle.AbstractMinecart$Type
+ net.minecraft.world.entity.vehicle.AbstractMinecartContainer
- net.minecraft.world.entity.vehicle.AbstractMinecartContainer$1
+ net.minecraft.world.entity.vehicle.Boat
- net.minecraft.world.entity.vehicle.Boat$1
+ net.minecraft.world.entity.vehicle.Boat$Status
- net.minecraft.world.entity.vehicle.Boat$Type
+ net.minecraft.world.entity.vehicle.DismountHelper
- net.minecraft.world.entity.vehicle.Minecart
+ net.minecraft.world.entity.vehicle.MinecartChest
- net.minecraft.world.entity.vehicle.MinecartCommandBlock
+ net.minecraft.world.entity.vehicle.MinecartCommandBlock$MinecartCommandBase
- net.minecraft.world.entity.vehicle.MinecartFurnace
+ net.minecraft.world.entity.vehicle.MinecartHopper
- net.minecraft.world.entity.vehicle.MinecartSpawner
+ net.minecraft.world.entity.vehicle.MinecartSpawner$1
- net.minecraft.world.entity.vehicle.MinecartTNT
+ net.minecraft.world.entity.vehicle.package-info
- net.minecraft.world.food.FoodConstants
+ net.minecraft.world.food.FoodData
- net.minecraft.world.food.FoodProperties
+ net.minecraft.world.food.FoodProperties$Builder
- net.minecraft.world.food.Foods
+ net.minecraft.world.food.package-info
- net.minecraft.world.inventory.AbstractContainerMenu
+ net.minecraft.world.inventory.AbstractContainerMenu$1
- net.minecraft.world.inventory.AbstractFurnaceMenu
+ net.minecraft.world.inventory.AnvilMenu
- net.minecraft.world.inventory.AnvilMenu$1
+ net.minecraft.world.inventory.BeaconMenu
- net.minecraft.world.inventory.BeaconMenu$1
+ net.minecraft.world.inventory.BeaconMenu$PaymentSlot
- net.minecraft.world.inventory.BlastFurnaceMenu
+ net.minecraft.world.inventory.BrewingStandMenu
- net.minecraft.world.inventory.BrewingStandMenu$FuelSlot
+ net.minecraft.world.inventory.BrewingStandMenu$IngredientsSlot
- net.minecraft.world.inventory.BrewingStandMenu$PotionSlot
+ net.minecraft.world.inventory.CartographyTableMenu
- net.minecraft.world.inventory.CartographyTableMenu$1
+ net.minecraft.world.inventory.CartographyTableMenu$2
- net.minecraft.world.inventory.CartographyTableMenu$3
+ net.minecraft.world.inventory.CartographyTableMenu$4
- net.minecraft.world.inventory.CartographyTableMenu$5
+ net.minecraft.world.inventory.ChestMenu
- net.minecraft.world.inventory.ClickAction
+ net.minecraft.world.inventory.ClickType
- net.minecraft.world.inventory.ContainerData
+ net.minecraft.world.inventory.ContainerLevelAccess
- net.minecraft.world.inventory.ContainerLevelAccess$1
+ net.minecraft.world.inventory.ContainerLevelAccess$2
- net.minecraft.world.inventory.ContainerListener
+ net.minecraft.world.inventory.ContainerSynchronizer
- net.minecraft.world.inventory.CraftingContainer
+ net.minecraft.world.inventory.CraftingMenu
- net.minecraft.world.inventory.DataSlot
+ net.minecraft.world.inventory.DataSlot$1
- net.minecraft.world.inventory.DataSlot$2
+ net.minecraft.world.inventory.DataSlot$3
- net.minecraft.world.inventory.DispenserMenu
+ net.minecraft.world.inventory.EnchantmentMenu
- net.minecraft.world.inventory.EnchantmentMenu$1
+ net.minecraft.world.inventory.EnchantmentMenu$2
- net.minecraft.world.inventory.EnchantmentMenu$3
+ net.minecraft.world.inventory.FurnaceFuelSlot
- net.minecraft.world.inventory.FurnaceMenu
+ net.minecraft.world.inventory.FurnaceResultSlot
- net.minecraft.world.inventory.GrindstoneMenu
+ net.minecraft.world.inventory.GrindstoneMenu$1
- net.minecraft.world.inventory.GrindstoneMenu$2
+ net.minecraft.world.inventory.GrindstoneMenu$3
- net.minecraft.world.inventory.GrindstoneMenu$4
+ net.minecraft.world.inventory.HopperMenu
- net.minecraft.world.inventory.HorseInventoryMenu
+ net.minecraft.world.inventory.HorseInventoryMenu$1
- net.minecraft.world.inventory.HorseInventoryMenu$2
+ net.minecraft.world.inventory.InventoryMenu
- net.minecraft.world.inventory.InventoryMenu$1
+ net.minecraft.world.inventory.InventoryMenu$2
- net.minecraft.world.inventory.ItemCombinerMenu
+ net.minecraft.world.inventory.ItemCombinerMenu$1
- net.minecraft.world.inventory.ItemCombinerMenu$2
+ net.minecraft.world.inventory.LecternMenu
- net.minecraft.world.inventory.LecternMenu$1
+ net.minecraft.world.inventory.LoomMenu
- net.minecraft.world.inventory.LoomMenu$1
+ net.minecraft.world.inventory.LoomMenu$2
- net.minecraft.world.inventory.LoomMenu$3
+ net.minecraft.world.inventory.LoomMenu$4
- net.minecraft.world.inventory.LoomMenu$5
+ net.minecraft.world.inventory.LoomMenu$6
- net.minecraft.world.inventory.MenuConstructor
+ net.minecraft.world.inventory.MenuType
- net.minecraft.world.inventory.MenuType$MenuSupplier
+ net.minecraft.world.inventory.MerchantContainer
- net.minecraft.world.inventory.MerchantMenu
+ net.minecraft.world.inventory.MerchantResultSlot
- net.minecraft.world.inventory.package-info
- net.minecraft.world.inventory.PlayerEnderChestContainer
+ net.minecraft.world.inventory.RecipeBookMenu
- net.minecraft.world.inventory.RecipeBookType
+ net.minecraft.world.inventory.RecipeHolder
- net.minecraft.world.inventory.ResultContainer
+ net.minecraft.world.inventory.ResultSlot
- net.minecraft.world.inventory.ShulkerBoxMenu
+ net.minecraft.world.inventory.ShulkerBoxSlot
- net.minecraft.world.inventory.SimpleContainerData
+ net.minecraft.world.inventory.Slot
- net.minecraft.world.inventory.SmithingMenu
+ net.minecraft.world.inventory.SmokerMenu
- net.minecraft.world.inventory.StackedContentsCompatible
+ net.minecraft.world.inventory.StonecutterMenu
- net.minecraft.world.inventory.StonecutterMenu$1
+ net.minecraft.world.inventory.StonecutterMenu$2
+ net.minecraft.world.inventory.tooltip.BundleTooltip
+ net.minecraft.world.inventory.tooltip.package-info
- net.minecraft.world.inventory.tooltip.TooltipComponent
- net.minecraft.world.item.AdventureModeCheck
+ net.minecraft.world.item.AirItem
+ net.minecraft.world.item.alchemy.package-info
- net.minecraft.world.item.alchemy.Potion
+ net.minecraft.world.item.alchemy.PotionBrewing
- net.minecraft.world.item.alchemy.PotionBrewing$Mix
- net.minecraft.world.item.alchemy.Potions
+ net.minecraft.world.item.alchemy.PotionUtils
- net.minecraft.world.item.ArmorItem
+ net.minecraft.world.item.ArmorItem$1
- net.minecraft.world.item.ArmorMaterial
+ net.minecraft.world.item.ArmorMaterials
- net.minecraft.world.item.ArmorStandItem
+ net.minecraft.world.item.ArrowItem
- net.minecraft.world.item.AxeItem
+ net.minecraft.world.item.BannerItem
- net.minecraft.world.item.BannerPatternItem
+ net.minecraft.world.item.BedItem
- net.minecraft.world.item.BlockItem
+ net.minecraft.world.item.BoatItem
- net.minecraft.world.item.BoneMealItem
+ net.minecraft.world.item.BookItem
- net.minecraft.world.item.BottleItem
+ net.minecraft.world.item.BowItem
- net.minecraft.world.item.BowlFoodItem
+ net.minecraft.world.item.BucketItem
- net.minecraft.world.item.BundleItem
+ net.minecraft.world.item.ChorusFruitItem
- net.minecraft.world.item.CompassItem
+ net.minecraft.world.item.ComplexItem
- net.minecraft.world.item.context.BlockPlaceContext
+ net.minecraft.world.item.context.DirectionalPlaceContext
- net.minecraft.world.item.context.DirectionalPlaceContext$1
- net.minecraft.world.item.context.package-info
+ net.minecraft.world.item.context.UseOnContext
+ net.minecraft.world.item.crafting.AbstractCookingRecipe
- net.minecraft.world.item.crafting.ArmorDyeRecipe
+ net.minecraft.world.item.crafting.BannerDuplicateRecipe
- net.minecraft.world.item.crafting.BlastingRecipe
+ net.minecraft.world.item.crafting.BookCloningRecipe
- net.minecraft.world.item.crafting.CampfireCookingRecipe
+ net.minecraft.world.item.crafting.CraftingRecipe
- net.minecraft.world.item.crafting.CustomRecipe
+ net.minecraft.world.item.crafting.FireworkRocketRecipe
- net.minecraft.world.item.crafting.FireworkStarFadeRecipe
+ net.minecraft.world.item.crafting.FireworkStarRecipe
- net.minecraft.world.item.crafting.Ingredient
+ net.minecraft.world.item.crafting.Ingredient$ItemValue
- net.minecraft.world.item.crafting.Ingredient$TagValue
+ net.minecraft.world.item.crafting.Ingredient$Value
- net.minecraft.world.item.crafting.MapCloningRecipe
+ net.minecraft.world.item.crafting.MapExtendingRecipe
+ net.minecraft.world.item.crafting.package-info
- net.minecraft.world.item.crafting.Recipe
+ net.minecraft.world.item.crafting.RecipeManager
- net.minecraft.world.item.crafting.RecipeSerializer
+ net.minecraft.world.item.crafting.RecipeType
- net.minecraft.world.item.crafting.RecipeType$1
+ net.minecraft.world.item.crafting.RepairItemRecipe
- net.minecraft.world.item.crafting.ShapedRecipe
+ net.minecraft.world.item.crafting.ShapedRecipe$Serializer
- net.minecraft.world.item.crafting.ShapelessRecipe
+ net.minecraft.world.item.crafting.ShapelessRecipe$Serializer
- net.minecraft.world.item.crafting.ShieldDecorationRecipe
+ net.minecraft.world.item.crafting.ShulkerBoxColoring
- net.minecraft.world.item.crafting.SimpleCookingSerializer
+ net.minecraft.world.item.crafting.SimpleCookingSerializer$CookieBaker
- net.minecraft.world.item.crafting.SimpleRecipeSerializer
+ net.minecraft.world.item.crafting.SingleItemRecipe
- net.minecraft.world.item.crafting.SingleItemRecipe$Serializer
+ net.minecraft.world.item.crafting.SingleItemRecipe$Serializer$SingleItemMaker
- net.minecraft.world.item.crafting.SmeltingRecipe
+ net.minecraft.world.item.crafting.SmokingRecipe
- net.minecraft.world.item.crafting.StonecutterRecipe
+ net.minecraft.world.item.crafting.SuspiciousStewRecipe
- net.minecraft.world.item.crafting.TippedArrowRecipe
+ net.minecraft.world.item.crafting.UpgradeRecipe
- net.minecraft.world.item.crafting.UpgradeRecipe$Serializer
- net.minecraft.world.item.CreativeModeTab
+ net.minecraft.world.item.CreativeModeTab$1
- net.minecraft.world.item.CreativeModeTab$10
+ net.minecraft.world.item.CreativeModeTab$11
- net.minecraft.world.item.CreativeModeTab$12
+ net.minecraft.world.item.CreativeModeTab$2
- net.minecraft.world.item.CreativeModeTab$3
+ net.minecraft.world.item.CreativeModeTab$4
- net.minecraft.world.item.CreativeModeTab$5
+ net.minecraft.world.item.CreativeModeTab$6
- net.minecraft.world.item.CreativeModeTab$7
+ net.minecraft.world.item.CreativeModeTab$8
- net.minecraft.world.item.CreativeModeTab$9
+ net.minecraft.world.item.CrossbowItem
- net.minecraft.world.item.DebugStickItem
+ net.minecraft.world.item.DiggerItem
- net.minecraft.world.item.DispensibleContainerItem
+ net.minecraft.world.item.DoubleHighBlockItem
- net.minecraft.world.item.DyeableArmorItem
+ net.minecraft.world.item.DyeableHorseArmorItem
- net.minecraft.world.item.DyeableLeatherItem
- net.minecraft.world.item.DyeColor
+ net.minecraft.world.item.DyeItem
+ net.minecraft.world.item.EggItem
- net.minecraft.world.item.ElytraItem
+ net.minecraft.world.item.EmptyMapItem
- net.minecraft.world.item.EnchantedBookItem
+ net.minecraft.world.item.EnchantedGoldenAppleItem
- net.minecraft.world.item.enchantment.ArrowDamageEnchantment
+ net.minecraft.world.item.enchantment.ArrowFireEnchantment
- net.minecraft.world.item.enchantment.ArrowInfiniteEnchantment
+ net.minecraft.world.item.enchantment.ArrowKnockbackEnchantment
- net.minecraft.world.item.enchantment.ArrowPiercingEnchantment
+ net.minecraft.world.item.enchantment.BindingCurseEnchantment
- net.minecraft.world.item.enchantment.DamageEnchantment
+ net.minecraft.world.item.enchantment.DigDurabilityEnchantment
- net.minecraft.world.item.enchantment.DiggingEnchantment
+ net.minecraft.world.item.enchantment.Enchantment
- net.minecraft.world.item.enchantment.Enchantment$Rarity
+ net.minecraft.world.item.enchantment.EnchantmentCategory
- net.minecraft.world.item.enchantment.EnchantmentCategory$1
+ net.minecraft.world.item.enchantment.EnchantmentCategory$10
- net.minecraft.world.item.enchantment.EnchantmentCategory$11
+ net.minecraft.world.item.enchantment.EnchantmentCategory$12
- net.minecraft.world.item.enchantment.EnchantmentCategory$13
+ net.minecraft.world.item.enchantment.EnchantmentCategory$14
- net.minecraft.world.item.enchantment.EnchantmentCategory$2
+ net.minecraft.world.item.enchantment.EnchantmentCategory$3
- net.minecraft.world.item.enchantment.EnchantmentCategory$4
+ net.minecraft.world.item.enchantment.EnchantmentCategory$5
- net.minecraft.world.item.enchantment.EnchantmentCategory$6
+ net.minecraft.world.item.enchantment.EnchantmentCategory$7
- net.minecraft.world.item.enchantment.EnchantmentCategory$8
+ net.minecraft.world.item.enchantment.EnchantmentCategory$9
- net.minecraft.world.item.enchantment.EnchantmentHelper
+ net.minecraft.world.item.enchantment.EnchantmentHelper$EnchantmentVisitor
- net.minecraft.world.item.enchantment.EnchantmentInstance
+ net.minecraft.world.item.enchantment.Enchantments
- net.minecraft.world.item.enchantment.FireAspectEnchantment
+ net.minecraft.world.item.enchantment.FishingSpeedEnchantment
- net.minecraft.world.item.enchantment.FrostWalkerEnchantment
+ net.minecraft.world.item.enchantment.KnockbackEnchantment
- net.minecraft.world.item.enchantment.LootBonusEnchantment
+ net.minecraft.world.item.enchantment.MendingEnchantment
- net.minecraft.world.item.enchantment.MultiShotEnchantment
+ net.minecraft.world.item.enchantment.OxygenEnchantment
- net.minecraft.world.item.enchantment.package-info
- net.minecraft.world.item.enchantment.ProtectionEnchantment
+ net.minecraft.world.item.enchantment.ProtectionEnchantment$Type
- net.minecraft.world.item.enchantment.QuickChargeEnchantment
+ net.minecraft.world.item.enchantment.SoulSpeedEnchantment
- net.minecraft.world.item.enchantment.SweepingEdgeEnchantment
+ net.minecraft.world.item.enchantment.ThornsEnchantment
- net.minecraft.world.item.enchantment.TridentChannelingEnchantment
+ net.minecraft.world.item.enchantment.TridentImpalerEnchantment
- net.minecraft.world.item.enchantment.TridentLoyaltyEnchantment
+ net.minecraft.world.item.enchantment.TridentRiptideEnchantment
- net.minecraft.world.item.enchantment.UntouchingEnchantment
+ net.minecraft.world.item.enchantment.VanishingCurseEnchantment
- net.minecraft.world.item.enchantment.WaterWalkerEnchantment
+ net.minecraft.world.item.enchantment.WaterWorkerEnchantment
- net.minecraft.world.item.EndCrystalItem
+ net.minecraft.world.item.EnderEyeItem
- net.minecraft.world.item.EnderpearlItem
+ net.minecraft.world.item.ExperienceBottleItem
- net.minecraft.world.item.FireChargeItem
+ net.minecraft.world.item.FireworkRocketItem
- net.minecraft.world.item.FireworkRocketItem$Shape
+ net.minecraft.world.item.FireworkStarItem
- net.minecraft.world.item.FishingRodItem
+ net.minecraft.world.item.FlintAndSteelItem
- net.minecraft.world.item.FoodOnAStickItem
+ net.minecraft.world.item.GameMasterBlockItem
- net.minecraft.world.item.HangingEntityItem
+ net.minecraft.world.item.HoeItem
- net.minecraft.world.item.HoneyBottleItem
+ net.minecraft.world.item.HoneycombItem
- net.minecraft.world.item.HorseArmorItem
+ net.minecraft.world.item.Item
- net.minecraft.world.item.Item$1
+ net.minecraft.world.item.Item$Properties
- net.minecraft.world.item.ItemCooldowns
+ net.minecraft.world.item.ItemCooldowns$CooldownInstance
- net.minecraft.world.item.ItemFrameItem
+ net.minecraft.world.item.ItemNameBlockItem
+ net.minecraft.world.item.Items
- net.minecraft.world.item.ItemStack
+ net.minecraft.world.item.ItemStack$TooltipPart
- net.minecraft.world.item.ItemUtils
- net.minecraft.world.item.KnowledgeBookItem
+ net.minecraft.world.item.LeadItem
- net.minecraft.world.item.LingeringPotionItem
+ net.minecraft.world.item.MapItem
- net.minecraft.world.item.MilkBucketItem
+ net.minecraft.world.item.MinecartItem
- net.minecraft.world.item.MinecartItem$1
+ net.minecraft.world.item.MobBucketItem
- net.minecraft.world.item.NameTagItem
+ net.minecraft.world.item.package-info
+ net.minecraft.world.item.PickaxeItem
- net.minecraft.world.item.PlayerHeadItem
+ net.minecraft.world.item.PotionItem
- net.minecraft.world.item.ProjectileWeaponItem
+ net.minecraft.world.item.Rarity
- net.minecraft.world.item.RecordItem
+ net.minecraft.world.item.SaddleItem
- net.minecraft.world.item.ScaffoldingBlockItem
+ net.minecraft.world.item.ServerItemCooldowns
- net.minecraft.world.item.ShearsItem
+ net.minecraft.world.item.ShieldItem
- net.minecraft.world.item.ShovelItem
+ net.minecraft.world.item.SignItem
- net.minecraft.world.item.SimpleFoiledItem
+ net.minecraft.world.item.SnowballItem
- net.minecraft.world.item.SolidBucketItem
+ net.minecraft.world.item.SpawnEggItem
- net.minecraft.world.item.SpectralArrowItem
+ net.minecraft.world.item.SplashPotionItem
- net.minecraft.world.item.SpyglassItem
+ net.minecraft.world.item.StandingAndWallBlockItem
- net.minecraft.world.item.SuspiciousStewItem
+ net.minecraft.world.item.SwordItem
- net.minecraft.world.item.ThrowablePotionItem
+ net.minecraft.world.item.Tier
- net.minecraft.world.item.TieredItem
+ net.minecraft.world.item.Tiers
- net.minecraft.world.item.TippedArrowItem
+ net.minecraft.world.item.TooltipFlag
- net.minecraft.world.item.TooltipFlag$Default
- net.minecraft.world.item.trading.Merchant
+ net.minecraft.world.item.trading.MerchantOffer
- net.minecraft.world.item.trading.MerchantOffers
+ net.minecraft.world.item.trading.package-info
+ net.minecraft.world.item.TridentItem
- net.minecraft.world.item.UseAnim
+ net.minecraft.world.item.Vanishable
- net.minecraft.world.item.WaterLilyBlockItem
+ net.minecraft.world.item.Wearable
- net.minecraft.world.item.WritableBookItem
+ net.minecraft.world.item.WrittenBookItem
- net.minecraft.world.level.BaseCommandBlock
+ net.minecraft.world.level.BaseSpawner
+ net.minecraft.world.level.biome.AmbientAdditionsSettings
- net.minecraft.world.level.biome.AmbientMoodSettings
+ net.minecraft.world.level.biome.AmbientParticleSettings
- net.minecraft.world.level.biome.Biome
+ net.minecraft.world.level.biome.Biome$1
- net.minecraft.world.level.biome.Biome$BiomeBuilder
+ net.minecraft.world.level.biome.Biome$BiomeCategory
- net.minecraft.world.level.biome.Biome$ClimateSettings
+ net.minecraft.world.level.biome.Biome$Precipitation
- net.minecraft.world.level.biome.Biome$TemperatureModifier
+ net.minecraft.world.level.biome.Biome$TemperatureModifier$1
- net.minecraft.world.level.biome.Biome$TemperatureModifier$2
+ net.minecraft.world.level.biome.BiomeGenerationSettings
- net.minecraft.world.level.biome.BiomeGenerationSettings$Builder
+ net.minecraft.world.level.biome.BiomeManager
- net.minecraft.world.level.biome.BiomeManager$NoiseBiomeSource
+ net.minecraft.world.level.biome.Biomes
+ net.minecraft.world.level.biome.BiomeSource
- net.minecraft.world.level.biome.BiomeSource$1FeatureData
+ net.minecraft.world.level.biome.BiomeSpecialEffects
- net.minecraft.world.level.biome.BiomeSpecialEffects$Builder
+ net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier
- net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$1
+ net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$2
- net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$3
- net.minecraft.world.level.biome.CheckerboardColumnBiomeSource
+ net.minecraft.world.level.biome.Climate
- net.minecraft.world.level.biome.Climate$DistanceMetric
+ net.minecraft.world.level.biome.Climate$Parameter
- net.minecraft.world.level.biome.Climate$ParameterList
+ net.minecraft.world.level.biome.Climate$ParameterPoint
- net.minecraft.world.level.biome.Climate$RTree
+ net.minecraft.world.level.biome.Climate$RTree$Leaf
- net.minecraft.world.level.biome.Climate$RTree$Node
+ net.minecraft.world.level.biome.Climate$RTree$SubTree
- net.minecraft.world.level.biome.Climate$Sampler
+ net.minecraft.world.level.biome.Climate$TargetPoint
- net.minecraft.world.level.biome.FixedBiomeSource
+ net.minecraft.world.level.biome.MobSpawnSettings
- net.minecraft.world.level.biome.MobSpawnSettings$Builder
+ net.minecraft.world.level.biome.MobSpawnSettings$MobSpawnCost
- net.minecraft.world.level.biome.MobSpawnSettings$SpawnerData
+ net.minecraft.world.level.biome.MultiNoiseBiomeSource
- net.minecraft.world.level.biome.MultiNoiseBiomeSource$Preset
+ net.minecraft.world.level.biome.MultiNoiseBiomeSource$PresetInstance
- net.minecraft.world.level.biome.OverworldBiomeBuilder
- net.minecraft.world.level.biome.package-info
+ net.minecraft.world.level.biome.TerrainShaper
- net.minecraft.world.level.biome.TerrainShaper$1
+ net.minecraft.world.level.biome.TerrainShaper$2
- net.minecraft.world.level.biome.TerrainShaper$3
+ net.minecraft.world.level.biome.TerrainShaper$4
- net.minecraft.world.level.biome.TerrainShaper$Point
+ net.minecraft.world.level.biome.TheEndBiomeSource
+ net.minecraft.world.level.block.AbstractBannerBlock
- net.minecraft.world.level.block.AbstractCandleBlock
+ net.minecraft.world.level.block.AbstractCauldronBlock
- net.minecraft.world.level.block.AbstractChestBlock
+ net.minecraft.world.level.block.AbstractFurnaceBlock
- net.minecraft.world.level.block.AbstractGlassBlock
+ net.minecraft.world.level.block.AbstractSkullBlock
- net.minecraft.world.level.block.AirBlock
+ net.minecraft.world.level.block.AmethystBlock
- net.minecraft.world.level.block.AmethystClusterBlock
+ net.minecraft.world.level.block.AmethystClusterBlock$1
- net.minecraft.world.level.block.AnvilBlock
+ net.minecraft.world.level.block.AttachedStemBlock
- net.minecraft.world.level.block.AzaleaBlock
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
+ net.minecraft.world.level.block.BigDripleafBlock
- net.minecraft.world.level.block.BigDripleafStemBlock
+ net.minecraft.world.level.block.BigDripleafStemBlock$1
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
- net.minecraft.world.level.block.BuddingAmethystBlock
+ net.minecraft.world.level.block.BushBlock
- net.minecraft.world.level.block.ButtonBlock
+ net.minecraft.world.level.block.ButtonBlock$1
- net.minecraft.world.level.block.CactusBlock
+ net.minecraft.world.level.block.CakeBlock
- net.minecraft.world.level.block.CampfireBlock
+ net.minecraft.world.level.block.CandleBlock
- net.minecraft.world.level.block.CandleCakeBlock
+ net.minecraft.world.level.block.CarpetBlock
- net.minecraft.world.level.block.CarrotBlock
+ net.minecraft.world.level.block.CartographyTableBlock
- net.minecraft.world.level.block.CarvedPumpkinBlock
+ net.minecraft.world.level.block.CauldronBlock
- net.minecraft.world.level.block.CaveVines
+ net.minecraft.world.level.block.CaveVinesBlock
- net.minecraft.world.level.block.CaveVinesPlantBlock
+ net.minecraft.world.level.block.ChainBlock
- net.minecraft.world.level.block.ChainBlock$1
+ net.minecraft.world.level.block.ChangeOverTimeBlock
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
+ net.minecraft.world.level.block.DirtPathBlock
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
+ net.minecraft.world.level.block.EnderChestBlock
+ net.minecraft.world.level.block.EndGatewayBlock
- net.minecraft.world.level.block.EndPortalBlock
+ net.minecraft.world.level.block.EndPortalFrameBlock
- net.minecraft.world.level.block.EndRodBlock
- net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity
+ net.minecraft.world.level.block.entity.AbstractFurnaceBlockEntity$1
- net.minecraft.world.level.block.entity.BannerBlockEntity
+ net.minecraft.world.level.block.entity.BannerPattern
- net.minecraft.world.level.block.entity.BannerPattern$Builder
+ net.minecraft.world.level.block.entity.BarrelBlockEntity
- net.minecraft.world.level.block.entity.BarrelBlockEntity$1
+ net.minecraft.world.level.block.entity.BaseContainerBlockEntity
- net.minecraft.world.level.block.entity.BeaconBlockEntity
+ net.minecraft.world.level.block.entity.BeaconBlockEntity$1
- net.minecraft.world.level.block.entity.BeaconBlockEntity$BeaconBeamSection
+ net.minecraft.world.level.block.entity.BedBlockEntity
- net.minecraft.world.level.block.entity.BeehiveBlockEntity
+ net.minecraft.world.level.block.entity.BeehiveBlockEntity$BeeData
- net.minecraft.world.level.block.entity.BeehiveBlockEntity$BeeReleaseStatus
+ net.minecraft.world.level.block.entity.BellBlockEntity
- net.minecraft.world.level.block.entity.BellBlockEntity$ResonationEndAction
+ net.minecraft.world.level.block.entity.BlastFurnaceBlockEntity
- net.minecraft.world.level.block.entity.BlockEntity
+ net.minecraft.world.level.block.entity.BlockEntityTicker
- net.minecraft.world.level.block.entity.BlockEntityType
+ net.minecraft.world.level.block.entity.BlockEntityType$BlockEntitySupplier
- net.minecraft.world.level.block.entity.BlockEntityType$Builder
+ net.minecraft.world.level.block.entity.BrewingStandBlockEntity
- net.minecraft.world.level.block.entity.BrewingStandBlockEntity$1
+ net.minecraft.world.level.block.entity.CampfireBlockEntity
- net.minecraft.world.level.block.entity.ChestBlockEntity
+ net.minecraft.world.level.block.entity.ChestBlockEntity$1
- net.minecraft.world.level.block.entity.ChestLidController
+ net.minecraft.world.level.block.entity.CommandBlockEntity
- net.minecraft.world.level.block.entity.CommandBlockEntity$1
+ net.minecraft.world.level.block.entity.CommandBlockEntity$Mode
- net.minecraft.world.level.block.entity.ComparatorBlockEntity
+ net.minecraft.world.level.block.entity.ConduitBlockEntity
- net.minecraft.world.level.block.entity.ContainerOpenersCounter
+ net.minecraft.world.level.block.entity.DaylightDetectorBlockEntity
- net.minecraft.world.level.block.entity.DispenserBlockEntity
+ net.minecraft.world.level.block.entity.DropperBlockEntity
- net.minecraft.world.level.block.entity.EnchantmentTableBlockEntity
+ net.minecraft.world.level.block.entity.EnderChestBlockEntity
- net.minecraft.world.level.block.entity.EnderChestBlockEntity$1
+ net.minecraft.world.level.block.entity.FurnaceBlockEntity
- net.minecraft.world.level.block.entity.Hopper
+ net.minecraft.world.level.block.entity.HopperBlockEntity
- net.minecraft.world.level.block.entity.JigsawBlockEntity
+ net.minecraft.world.level.block.entity.JigsawBlockEntity$JointType
- net.minecraft.world.level.block.entity.JukeboxBlockEntity
+ net.minecraft.world.level.block.entity.LecternBlockEntity
- net.minecraft.world.level.block.entity.LecternBlockEntity$1
+ net.minecraft.world.level.block.entity.LecternBlockEntity$2
- net.minecraft.world.level.block.entity.LidBlockEntity
+ net.minecraft.world.level.block.entity.package-info
+ net.minecraft.world.level.block.entity.RandomizableContainerBlockEntity
- net.minecraft.world.level.block.entity.SculkSensorBlockEntity
+ net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity
- net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity$1
+ net.minecraft.world.level.block.entity.ShulkerBoxBlockEntity$AnimationStatus
- net.minecraft.world.level.block.entity.SignBlockEntity
+ net.minecraft.world.level.block.entity.SkullBlockEntity
- net.minecraft.world.level.block.entity.SmokerBlockEntity
+ net.minecraft.world.level.block.entity.SpawnerBlockEntity
- net.minecraft.world.level.block.entity.SpawnerBlockEntity$1
+ net.minecraft.world.level.block.entity.StructureBlockEntity
- net.minecraft.world.level.block.entity.StructureBlockEntity$UpdateType
+ net.minecraft.world.level.block.entity.TheEndGatewayBlockEntity
- net.minecraft.world.level.block.entity.TheEndPortalBlockEntity
+ net.minecraft.world.level.block.entity.TickingBlockEntity
- net.minecraft.world.level.block.entity.TrappedChestBlockEntity
- net.minecraft.world.level.block.EntityBlock
+ net.minecraft.world.level.block.FaceAttachedHorizontalDirectionalBlock
- net.minecraft.world.level.block.FaceAttachedHorizontalDirectionalBlock$1
+ net.minecraft.world.level.block.Fallable
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
- net.minecraft.world.level.block.GameMasterBlock
+ net.minecraft.world.level.block.GlassBlock
- net.minecraft.world.level.block.GlazedTerracottaBlock
+ net.minecraft.world.level.block.GlowLichenBlock
- net.minecraft.world.level.block.GrassBlock
+ net.minecraft.world.level.block.GravelBlock
- net.minecraft.world.level.block.GrindstoneBlock
+ net.minecraft.world.level.block.GrindstoneBlock$1
- net.minecraft.world.level.block.grower.AbstractMegaTreeGrower
+ net.minecraft.world.level.block.grower.AbstractTreeGrower
- net.minecraft.world.level.block.grower.AcaciaTreeGrower
+ net.minecraft.world.level.block.grower.AzaleaTreeGrower
- net.minecraft.world.level.block.grower.BirchTreeGrower
+ net.minecraft.world.level.block.grower.DarkOakTreeGrower
- net.minecraft.world.level.block.grower.JungleTreeGrower
+ net.minecraft.world.level.block.grower.OakTreeGrower
+ net.minecraft.world.level.block.grower.package-info
- net.minecraft.world.level.block.grower.SpruceTreeGrower
- net.minecraft.world.level.block.GrowingPlantBlock
+ net.minecraft.world.level.block.GrowingPlantBodyBlock
- net.minecraft.world.level.block.GrowingPlantHeadBlock
+ net.minecraft.world.level.block.HalfTransparentBlock
- net.minecraft.world.level.block.HangingRootsBlock
+ net.minecraft.world.level.block.HayBlock
- net.minecraft.world.level.block.HoneyBlock
+ net.minecraft.world.level.block.HopperBlock
- net.minecraft.world.level.block.HopperBlock$1
+ net.minecraft.world.level.block.HorizontalDirectionalBlock
- net.minecraft.world.level.block.HugeMushroomBlock
+ net.minecraft.world.level.block.IceBlock
- net.minecraft.world.level.block.InfestedBlock
+ net.minecraft.world.level.block.InfestedRotatedPillarBlock
- net.minecraft.world.level.block.IronBarsBlock
+ net.minecraft.world.level.block.JigsawBlock
- net.minecraft.world.level.block.JukeboxBlock
+ net.minecraft.world.level.block.KelpBlock
- net.minecraft.world.level.block.KelpPlantBlock
+ net.minecraft.world.level.block.LadderBlock
- net.minecraft.world.level.block.LadderBlock$1
+ net.minecraft.world.level.block.LanternBlock
- net.minecraft.world.level.block.LavaCauldronBlock
+ net.minecraft.world.level.block.LayeredCauldronBlock
- net.minecraft.world.level.block.LeavesBlock
+ net.minecraft.world.level.block.LecternBlock
- net.minecraft.world.level.block.LecternBlock$1
+ net.minecraft.world.level.block.LevelEvent
- net.minecraft.world.level.block.LeverBlock
+ net.minecraft.world.level.block.LeverBlock$1
- net.minecraft.world.level.block.LightBlock
+ net.minecraft.world.level.block.LightningRodBlock
- net.minecraft.world.level.block.LiquidBlock
+ net.minecraft.world.level.block.LiquidBlockContainer
- net.minecraft.world.level.block.LoomBlock
+ net.minecraft.world.level.block.MagmaBlock
- net.minecraft.world.level.block.MelonBlock
+ net.minecraft.world.level.block.Mirror
- net.minecraft.world.level.block.Mirror$1
+ net.minecraft.world.level.block.MossBlock
- net.minecraft.world.level.block.MultifaceBlock
+ net.minecraft.world.level.block.MushroomBlock
- net.minecraft.world.level.block.MyceliumBlock
+ net.minecraft.world.level.block.NetherPortalBlock
- net.minecraft.world.level.block.NetherPortalBlock$1
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
- net.minecraft.world.level.block.PointedDripstoneBlock
+ net.minecraft.world.level.block.PotatoBlock
- net.minecraft.world.level.block.PowderSnowBlock
+ net.minecraft.world.level.block.PowderSnowCauldronBlock
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
+ net.minecraft.world.level.block.RespawnAnchorBlock$1
- net.minecraft.world.level.block.RodBlock
+ net.minecraft.world.level.block.RodBlock$1
- net.minecraft.world.level.block.RootedDirtBlock
+ net.minecraft.world.level.block.RootsBlock
- net.minecraft.world.level.block.RotatedPillarBlock
+ net.minecraft.world.level.block.RotatedPillarBlock$1
- net.minecraft.world.level.block.Rotation
+ net.minecraft.world.level.block.Rotation$1
- net.minecraft.world.level.block.SandBlock
+ net.minecraft.world.level.block.SaplingBlock
- net.minecraft.world.level.block.ScaffoldingBlock
+ net.minecraft.world.level.block.SculkSensorBlock
+ net.minecraft.world.level.block.SeagrassBlock
- net.minecraft.world.level.block.SeaPickleBlock
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
- net.minecraft.world.level.block.SmallDripleafBlock
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
+ net.minecraft.world.level.block.SporeBlossomBlock
- net.minecraft.world.level.block.SpreadingSnowyDirtBlock
+ net.minecraft.world.level.block.StainedGlassBlock
- net.minecraft.world.level.block.StainedGlassPaneBlock
+ net.minecraft.world.level.block.StairBlock
- net.minecraft.world.level.block.StairBlock$1
+ net.minecraft.world.level.block.StandingSignBlock
- net.minecraft.world.level.block.state.BlockBehaviour
+ net.minecraft.world.level.block.state.BlockBehaviour$1
- net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase
+ net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase$Cache
- net.minecraft.world.level.block.state.BlockBehaviour$OffsetType
+ net.minecraft.world.level.block.state.BlockBehaviour$Properties
- net.minecraft.world.level.block.state.BlockBehaviour$StateArgumentPredicate
+ net.minecraft.world.level.block.state.BlockBehaviour$StatePredicate
- net.minecraft.world.level.block.state.BlockState
- net.minecraft.world.level.block.state.package-info
+ net.minecraft.world.level.block.state.pattern.BlockInWorld
- net.minecraft.world.level.block.state.pattern.BlockPattern
+ net.minecraft.world.level.block.state.pattern.BlockPattern$BlockCacheLoader
- net.minecraft.world.level.block.state.pattern.BlockPattern$BlockPatternMatch
+ net.minecraft.world.level.block.state.pattern.BlockPatternBuilder
- net.minecraft.world.level.block.state.pattern.package-info
+ net.minecraft.world.level.block.state.predicate.BlockMaterialPredicate
- net.minecraft.world.level.block.state.predicate.BlockMaterialPredicate$1
+ net.minecraft.world.level.block.state.predicate.BlockPredicate
- net.minecraft.world.level.block.state.predicate.BlockStatePredicate
+ net.minecraft.world.level.block.state.predicate.package-info
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
+ net.minecraft.world.level.block.state.properties.DripstoneThickness
- net.minecraft.world.level.block.state.properties.EnumProperty
+ net.minecraft.world.level.block.state.properties.Half
- net.minecraft.world.level.block.state.properties.IntegerProperty
+ net.minecraft.world.level.block.state.properties.NoteBlockInstrument
- net.minecraft.world.level.block.state.properties.package-info
- net.minecraft.world.level.block.state.properties.PistonType
+ net.minecraft.world.level.block.state.properties.Property
- net.minecraft.world.level.block.state.properties.Property$Value
+ net.minecraft.world.level.block.state.properties.RailShape
- net.minecraft.world.level.block.state.properties.RedstoneSide
+ net.minecraft.world.level.block.state.properties.SculkSensorPhase
- net.minecraft.world.level.block.state.properties.SlabType
+ net.minecraft.world.level.block.state.properties.StairsShape
- net.minecraft.world.level.block.state.properties.StructureMode
+ net.minecraft.world.level.block.state.properties.Tilt
- net.minecraft.world.level.block.state.properties.WallSide
+ net.minecraft.world.level.block.state.properties.WoodType
+ net.minecraft.world.level.block.state.StateDefinition
- net.minecraft.world.level.block.state.StateDefinition$Builder
+ net.minecraft.world.level.block.state.StateDefinition$Factory
- net.minecraft.world.level.block.state.StateHolder
+ net.minecraft.world.level.block.state.StateHolder$1
- net.minecraft.world.level.block.StemBlock
+ net.minecraft.world.level.block.StemGrownBlock
- net.minecraft.world.level.block.StoneButtonBlock
+ net.minecraft.world.level.block.StonecutterBlock
- net.minecraft.world.level.block.StructureBlock
+ net.minecraft.world.level.block.StructureBlock$1
- net.minecraft.world.level.block.StructureVoidBlock
+ net.minecraft.world.level.block.SugarCaneBlock
- net.minecraft.world.level.block.SupportType
+ net.minecraft.world.level.block.SupportType$1
- net.minecraft.world.level.block.SupportType$2
+ net.minecraft.world.level.block.SupportType$3
- net.minecraft.world.level.block.SweetBerryBushBlock
+ net.minecraft.world.level.block.TallFlowerBlock
- net.minecraft.world.level.block.TallGrassBlock
+ net.minecraft.world.level.block.TallSeagrassBlock
- net.minecraft.world.level.block.TargetBlock
+ net.minecraft.world.level.block.TintedGlassBlock
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
- net.minecraft.world.level.block.TwistingVinesBlock
+ net.minecraft.world.level.block.TwistingVinesPlantBlock
- net.minecraft.world.level.block.VineBlock
+ net.minecraft.world.level.block.VineBlock$1
- net.minecraft.world.level.block.WallBannerBlock
+ net.minecraft.world.level.block.WallBlock
- net.minecraft.world.level.block.WallBlock$1
+ net.minecraft.world.level.block.WallSignBlock
- net.minecraft.world.level.block.WallSkullBlock
+ net.minecraft.world.level.block.WallTorchBlock
- net.minecraft.world.level.block.WaterlilyBlock
+ net.minecraft.world.level.block.WeatheringCopper
- net.minecraft.world.level.block.WeatheringCopper$WeatherState
+ net.minecraft.world.level.block.WeatheringCopperFullBlock
- net.minecraft.world.level.block.WeatheringCopperSlabBlock
+ net.minecraft.world.level.block.WeatheringCopperStairBlock
- net.minecraft.world.level.block.WebBlock
+ net.minecraft.world.level.block.WeepingVinesBlock
- net.minecraft.world.level.block.WeepingVinesPlantBlock
+ net.minecraft.world.level.block.WeightedPressurePlateBlock
- net.minecraft.world.level.block.WetSpongeBlock
+ net.minecraft.world.level.block.WitherRoseBlock
- net.minecraft.world.level.block.WitherSkullBlock
+ net.minecraft.world.level.block.WitherWallSkullBlock
- net.minecraft.world.level.block.WoodButtonBlock
+ net.minecraft.world.level.block.WoolCarpetBlock
- net.minecraft.world.level.BlockAndTintGetter
+ net.minecraft.world.level.BlockEventData
- net.minecraft.world.level.BlockGetter
+ net.minecraft.world.level.border.BorderChangeListener
- net.minecraft.world.level.border.BorderChangeListener$DelegateBorderChangeListener
+ net.minecraft.world.level.border.BorderStatus
+ net.minecraft.world.level.border.package-info
- net.minecraft.world.level.border.WorldBorder
+ net.minecraft.world.level.border.WorldBorder$BorderExtent
- net.minecraft.world.level.border.WorldBorder$MovingBorderExtent
+ net.minecraft.world.level.border.WorldBorder$Settings
- net.minecraft.world.level.border.WorldBorder$StaticBorderExtent
- net.minecraft.world.level.chunk.BlockColumn
+ net.minecraft.world.level.chunk.BulkSectionAccess
- net.minecraft.world.level.chunk.CarvingMask
+ net.minecraft.world.level.chunk.ChunkAccess
- net.minecraft.world.level.chunk.ChunkGenerator
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
- net.minecraft.world.level.chunk.LevelChunk$1
+ net.minecraft.world.level.chunk.LevelChunk$BoundTickingBlockEntity
- net.minecraft.world.level.chunk.LevelChunk$EntityCreationType
+ net.minecraft.world.level.chunk.LevelChunk$RebindableTickingBlockEntityWrapper
- net.minecraft.world.level.chunk.LevelChunkSection
+ net.minecraft.world.level.chunk.LightChunkGetter
- net.minecraft.world.level.chunk.LinearPalette
+ net.minecraft.world.level.chunk.MissingPaletteEntryException
- net.minecraft.world.level.chunk.package-info
- net.minecraft.world.level.chunk.Palette
+ net.minecraft.world.level.chunk.Palette$Factory
+ net.minecraft.world.level.chunk.PalettedContainer
- net.minecraft.world.level.chunk.PalettedContainer$Configuration
+ net.minecraft.world.level.chunk.PalettedContainer$CountConsumer
- net.minecraft.world.level.chunk.PalettedContainer$Data
+ net.minecraft.world.level.chunk.PalettedContainer$DiscData
- net.minecraft.world.level.chunk.PalettedContainer$Strategy
+ net.minecraft.world.level.chunk.PalettedContainer$Strategy$1
- net.minecraft.world.level.chunk.PalettedContainer$Strategy$2
- net.minecraft.world.level.chunk.PaletteResize
+ net.minecraft.world.level.chunk.ProtoChunk
- net.minecraft.world.level.chunk.ProtoTickList
+ net.minecraft.world.level.chunk.SingleValuePalette
+ net.minecraft.world.level.chunk.storage.ChunkSerializer
- net.minecraft.world.level.chunk.storage.ChunkStorage
+ net.minecraft.world.level.chunk.storage.EntityStorage
- net.minecraft.world.level.chunk.storage.IOWorker
+ net.minecraft.world.level.chunk.storage.IOWorker$PendingStore
- net.minecraft.world.level.chunk.storage.IOWorker$Priority
+ net.minecraft.world.level.chunk.storage.package-info
+ net.minecraft.world.level.chunk.storage.RegionBitmap
- net.minecraft.world.level.chunk.storage.RegionFile
+ net.minecraft.world.level.chunk.storage.RegionFile$ChunkBuffer
- net.minecraft.world.level.chunk.storage.RegionFile$CommitOp
+ net.minecraft.world.level.chunk.storage.RegionFileStorage
- net.minecraft.world.level.chunk.storage.RegionFileVersion
+ net.minecraft.world.level.chunk.storage.RegionFileVersion$StreamWrapper
- net.minecraft.world.level.chunk.storage.SectionStorage
- net.minecraft.world.level.chunk.UpgradeData
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixer
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$1
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$2
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$3
- net.minecraft.world.level.chunk.UpgradeData$BlockFixers$4
+ net.minecraft.world.level.chunk.UpgradeData$BlockFixers$5
+ net.minecraft.world.level.ChunkPos
- net.minecraft.world.level.ChunkPos$1
+ net.minecraft.world.level.ChunkTickList
- net.minecraft.world.level.ChunkTickList$ScheduledTick
+ net.minecraft.world.level.ClipBlockStateContext
- net.minecraft.world.level.ClipContext
+ net.minecraft.world.level.ClipContext$Block
- net.minecraft.world.level.ClipContext$Fluid
+ net.minecraft.world.level.ClipContext$ShapeGetter
- net.minecraft.world.level.CollisionGetter
+ net.minecraft.world.level.CollisionSpliterator
- net.minecraft.world.level.ColorResolver
+ net.minecraft.world.level.CommonLevelAccessor
- net.minecraft.world.level.CustomSpawner
+ net.minecraft.world.level.DataPackConfig
- net.minecraft.world.level.dimension.DimensionDefaults
+ net.minecraft.world.level.dimension.DimensionType
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$1
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$2
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$3
+ net.minecraft.world.level.dimension.end.DragonRespawnAnimation$4
- net.minecraft.world.level.dimension.end.DragonRespawnAnimation$5
+ net.minecraft.world.level.dimension.end.EndDragonFight
- net.minecraft.world.level.dimension.end.package-info
- net.minecraft.world.level.dimension.LevelStem
+ net.minecraft.world.level.dimension.package-info
- net.minecraft.world.level.EmptyBlockGetter
+ net.minecraft.world.level.EmptyTickList
- net.minecraft.world.level.entity.ChunkEntities
+ net.minecraft.world.level.entity.ChunkStatusUpdateListener
- net.minecraft.world.level.entity.EntityAccess
+ net.minecraft.world.level.entity.EntityInLevelCallback
- net.minecraft.world.level.entity.EntityInLevelCallback$1
+ net.minecraft.world.level.entity.EntityLookup
- net.minecraft.world.level.entity.EntityPersistentStorage
+ net.minecraft.world.level.entity.EntitySection
- net.minecraft.world.level.entity.EntitySectionStorage
+ net.minecraft.world.level.entity.EntityTickList
- net.minecraft.world.level.entity.EntityTypeTest
+ net.minecraft.world.level.entity.EntityTypeTest$1
- net.minecraft.world.level.entity.LevelCallback
+ net.minecraft.world.level.entity.LevelEntityGetter
- net.minecraft.world.level.entity.LevelEntityGetterAdapter
+ net.minecraft.world.level.entity.package-info
+ net.minecraft.world.level.entity.PersistentEntitySectionManager
- net.minecraft.world.level.entity.PersistentEntitySectionManager$Callback
+ net.minecraft.world.level.entity.PersistentEntitySectionManager$ChunkLoadStatus
- net.minecraft.world.level.entity.TransientEntitySectionManager
+ net.minecraft.world.level.entity.TransientEntitySectionManager$Callback
- net.minecraft.world.level.entity.Visibility
- net.minecraft.world.level.EntityBasedExplosionDamageCalculator
+ net.minecraft.world.level.EntityGetter
- net.minecraft.world.level.Explosion
+ net.minecraft.world.level.Explosion$BlockInteraction
- net.minecraft.world.level.ExplosionDamageCalculator
+ net.minecraft.world.level.FoliageColor
- net.minecraft.world.level.ForcedChunksSavedData
- net.minecraft.world.level.gameevent.BlockPositionSource
+ net.minecraft.world.level.gameevent.BlockPositionSource$Type
- net.minecraft.world.level.gameevent.EntityPositionSource
+ net.minecraft.world.level.gameevent.EntityPositionSource$Type
- net.minecraft.world.level.gameevent.EuclideanGameEventDispatcher
+ net.minecraft.world.level.gameevent.GameEvent
- net.minecraft.world.level.gameevent.GameEventDispatcher
+ net.minecraft.world.level.gameevent.GameEventDispatcher$1
- net.minecraft.world.level.gameevent.GameEventListener
+ net.minecraft.world.level.gameevent.GameEventListenerRegistrar
- net.minecraft.world.level.gameevent.package-info
- net.minecraft.world.level.gameevent.PositionSource
+ net.minecraft.world.level.gameevent.PositionSourceType
- net.minecraft.world.level.gameevent.vibrations.package-info
+ net.minecraft.world.level.gameevent.vibrations.VibrationListener
- net.minecraft.world.level.gameevent.vibrations.VibrationListener$VibrationListenerConfig
+ net.minecraft.world.level.gameevent.vibrations.VibrationPath
+ net.minecraft.world.level.GameRules
- net.minecraft.world.level.GameRules$BooleanValue
+ net.minecraft.world.level.GameRules$Category
- net.minecraft.world.level.GameRules$GameRuleTypeVisitor
+ net.minecraft.world.level.GameRules$IntegerValue
- net.minecraft.world.level.GameRules$Key
+ net.minecraft.world.level.GameRules$Type
- net.minecraft.world.level.GameRules$Value
+ net.minecraft.world.level.GameRules$VisitorCaller
- net.minecraft.world.level.GameType
+ net.minecraft.world.level.GrassColor
- net.minecraft.world.level.ItemLike
+ net.minecraft.world.level.Level
- net.minecraft.world.level.Level$1
+ net.minecraft.world.level.LevelAccessor
+ net.minecraft.world.level.levelgen.Aquifer
- net.minecraft.world.level.levelgen.Aquifer$1
+ net.minecraft.world.level.levelgen.Aquifer$FluidPicker
- net.minecraft.world.level.levelgen.Aquifer$FluidStatus
+ net.minecraft.world.level.levelgen.Aquifer$NoiseBasedAquifer
- net.minecraft.world.level.levelgen.Beardifier
+ net.minecraft.world.level.levelgen.BitRandomSource
- net.minecraft.world.level.levelgen.blockpredicates.AllOfPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.AnyOfPredicate
- net.minecraft.world.level.levelgen.blockpredicates.BlockPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.BlockPredicateType
- net.minecraft.world.level.levelgen.blockpredicates.CombiningPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.MatchingBlocksPredicate
- net.minecraft.world.level.levelgen.blockpredicates.MatchingFluidsPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.NotPredicate
- net.minecraft.world.level.levelgen.blockpredicates.ReplaceablePredicate
- net.minecraft.world.level.levelgen.blockpredicates.TrueBlockPredicate
- net.minecraft.world.level.levelgen.Column
+ net.minecraft.world.level.levelgen.Column$Line
- net.minecraft.world.level.levelgen.Column$Range
+ net.minecraft.world.level.levelgen.Column$Ray
- net.minecraft.world.level.levelgen.DebugLevelSource
+ net.minecraft.world.level.levelgen.Decoratable
- net.minecraft.world.level.levelgen.Density
+ net.minecraft.world.level.levelgen.DepthBasedRule
+ net.minecraft.world.level.levelgen.feature.configurations.package-info
+ net.minecraft.world.level.levelgen.feature.configurations.SingleBlockStateConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SmallDripstoneConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.SpikeConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.SpringConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.StrongholdConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.StructureFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
+ net.minecraft.world.level.levelgen.feature.configurations.UnderwaterMagmaConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.VegetationPatchConfiguration
- net.minecraft.world.level.levelgen.feature.featuresize.FeatureSize
+ net.minecraft.world.level.levelgen.feature.featuresize.FeatureSizeType
- net.minecraft.world.level.levelgen.feature.featuresize.package-info
- net.minecraft.world.level.levelgen.feature.featuresize.ThreeLayersFeatureSize
+ net.minecraft.world.level.levelgen.feature.featuresize.TwoLayersFeatureSize
+ net.minecraft.world.level.levelgen.feature.foliageplacers.AcaciaFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.BlobFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.BushFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.DarkOakFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FancyFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacer$FoliageAttachment
- net.minecraft.world.level.levelgen.feature.foliageplacers.FoliagePlacerType
+ net.minecraft.world.level.levelgen.feature.foliageplacers.MegaJungleFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.MegaPineFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.package-info
+ net.minecraft.world.level.levelgen.feature.foliageplacers.PineFoliagePlacer
- net.minecraft.world.level.levelgen.feature.foliageplacers.RandomSpreadFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.foliageplacers.SpruceFoliagePlacer
+ net.minecraft.world.level.levelgen.feature.package-info
- net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.BlockStateProviderType
- net.minecraft.world.level.levelgen.feature.stateproviders.DualNoiseProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.NoiseBasedStateProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.NoiseProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.NoiseThresholdProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.package-info
- net.minecraft.world.level.levelgen.feature.stateproviders.RandomizedIntStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.RotatedBlockProvider
- net.minecraft.world.level.levelgen.feature.stateproviders.SimpleStateProvider
+ net.minecraft.world.level.levelgen.feature.stateproviders.WeightedStateProvider
+ net.minecraft.world.level.levelgen.feature.structures.EmptyPoolElement
- net.minecraft.world.level.levelgen.feature.structures.FeaturePoolElement
+ net.minecraft.world.level.levelgen.feature.structures.JigsawJunction
- net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$PieceFactory
- net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$PieceState
+ net.minecraft.world.level.levelgen.feature.structures.JigsawPlacement$Placer
- net.minecraft.world.level.levelgen.feature.structures.LegacySinglePoolElement
+ net.minecraft.world.level.levelgen.feature.structures.ListPoolElement
+ net.minecraft.world.level.levelgen.feature.structures.package-info
- net.minecraft.world.level.levelgen.feature.structures.SinglePoolElement
+ net.minecraft.world.level.levelgen.feature.structures.StructurePoolElement
- net.minecraft.world.level.levelgen.feature.structures.StructurePoolElementType
+ net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool
- net.minecraft.world.level.levelgen.feature.structures.StructureTemplatePool$Projection
- net.minecraft.world.level.levelgen.feature.treedecorators.AlterGroundDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.BeehiveDecorator
- net.minecraft.world.level.levelgen.feature.treedecorators.CocoaDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.LeaveVineDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.package-info
- net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecorator
+ net.minecraft.world.level.levelgen.feature.treedecorators.TreeDecoratorType
- net.minecraft.world.level.levelgen.feature.treedecorators.TrunkVineDecorator
- net.minecraft.world.level.levelgen.feature.trunkplacers.BendingTrunkPlacer
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
+ net.minecraft.world.level.levelgen.flat.package-info
- net.minecraft.world.level.levelgen.heightproviders.BiasedToBottomHeight
+ net.minecraft.world.level.levelgen.heightproviders.ConstantHeight
- net.minecraft.world.level.levelgen.heightproviders.HeightProvider
+ net.minecraft.world.level.levelgen.heightproviders.HeightProviderType
+ net.minecraft.world.level.levelgen.heightproviders.package-info
- net.minecraft.world.level.levelgen.heightproviders.TrapezoidHeight
+ net.minecraft.world.level.levelgen.heightproviders.UniformHeight
- net.minecraft.world.level.levelgen.heightproviders.VeryBiasedToBottomHeight
- net.minecraft.world.level.levelgen.LegacyRandomSource$LegacyPositionalRandomFactory
- net.minecraft.world.level.levelgen.material.MaterialRuleList
- net.minecraft.world.level.levelgen.material.package-info
+ net.minecraft.world.level.levelgen.material.WorldGenMaterialRule
- net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator
+ net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator$1
- net.minecraft.world.level.levelgen.NoiseChunk
+ net.minecraft.world.level.levelgen.NoiseChunk$BlockStateFiller
- net.minecraft.world.level.levelgen.NoiseChunk$FlatNoiseData
+ net.minecraft.world.level.levelgen.NoiseChunk$InterpolatableNoise
- net.minecraft.world.level.levelgen.NoiseChunk$NoiseFiller
+ net.minecraft.world.level.levelgen.NoiseChunk$NoiseInterpolator
- net.minecraft.world.level.levelgen.NoiseChunk$Sampler
+ net.minecraft.world.level.levelgen.NoiseGeneratorSettings
- net.minecraft.world.level.levelgen.NoiseOctaves
+ net.minecraft.world.level.levelgen.NoiseSampler
- net.minecraft.world.level.levelgen.NoiseSampler$QuantizedSpaghettiRarity
+ net.minecraft.world.level.levelgen.NoiseSampler$VeinType
- net.minecraft.world.level.levelgen.NoiseSamplingSettings
+ net.minecraft.world.level.levelgen.NoiseSettings
- net.minecraft.world.level.levelgen.NoiseSlider
+ net.minecraft.world.level.levelgen.package-info
+ net.minecraft.world.level.levelgen.PatrolSpawner
- net.minecraft.world.level.levelgen.PhantomSpawner
- net.minecraft.world.level.levelgen.placement.BlockFilterConfiguration
+ net.minecraft.world.level.levelgen.placement.BlockFilterDecorator
+ net.minecraft.world.level.levelgen.PositionalRandomFactory
- net.minecraft.world.level.levelgen.RandomSource
- net.minecraft.world.level.levelgen.RandomSupport$Seed128bit
+ net.minecraft.world.level.levelgen.SimpleRandomSource
- net.minecraft.world.level.levelgen.VerticalGradientRule
- net.minecraft.world.level.levelgen.WorldGenerationContext
+ net.minecraft.world.level.levelgen.WorldgenRandom
- net.minecraft.world.level.levelgen.WorldgenRandom$Algorithm
+ net.minecraft.world.level.levelgen.WorldGenSettings
- net.minecraft.world.level.levelgen.XoroshiroRandomSource
- net.minecraft.world.level.LevelHeightAccessor
+ net.minecraft.world.level.LevelReader
- net.minecraft.world.level.LevelSettings
- net.minecraft.world.level.LevelSimulatedReader
+ net.minecraft.world.level.LevelSimulatedRW
+ net.minecraft.world.level.LevelTimeAccess
- net.minecraft.world.level.LevelWriter
+ net.minecraft.world.level.LightLayer
- net.minecraft.world.level.LocalMobCapCalculator
+ net.minecraft.world.level.LocalMobCapCalculator$MobCounts
- net.minecraft.world.level.NaturalSpawner
+ net.minecraft.world.level.NaturalSpawner$1
- net.minecraft.world.level.NaturalSpawner$AfterSpawnCallback
+ net.minecraft.world.level.NaturalSpawner$ChunkGetter
- net.minecraft.world.level.NaturalSpawner$SpawnPredicate
+ net.minecraft.world.level.NaturalSpawner$SpawnState
- net.minecraft.world.level.NoiseColumn
+ net.minecraft.world.level.PathNavigationRegion
- net.minecraft.world.level.PotentialCalculator
+ net.minecraft.world.level.PotentialCalculator$PointCharge
- net.minecraft.world.level.ServerLevelAccessor
+ net.minecraft.world.level.ServerTickList
- net.minecraft.world.level.SpawnData
+ net.minecraft.world.level.SpawnData$CustomSpawnRules
- net.minecraft.world.level.StructureFeatureManager
+ net.minecraft.world.level.TickList
- net.minecraft.world.level.TickNextTickData
+ net.minecraft.world.level.TickPriority
- net.minecraft.world.level.WorldGenLevel
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.client.multiplayer.ClientPacketListener +1M | +1P
```
```
XXX.data.loot.FishingLoot +1P -5P
```
```
XXX.data.worldgen.Features +2M -2M | +7P -3P
```
```
XXX.protocol.game.ClientGamePacketListener +1P
```
```
XXX.protocol.game.ClientboundLoginPacket +2M -1M | +1P
```
```
XXX.world.entity.Entity +1P
```
```
XXX.ai.behavior.InteractWith +3M -5M
```
```
XXX.ai.behavior.SetEntityLookTarget +1M -3M | +1P
```
```
XXX.ai.behavior.SetLookAndInteract +3M -3M
```
```
XXX.ai.control.LookControl +1M -1M | +1P -1P
```
```
XXX.ai.goal.ZombieAttackGoal -1M
```
```
XXX.levelgen.feature.RandomPatchFeature -1M
```
```
XXX.feature.configurations.BlockColumnConfiguration +2M -2M | +1P -1P
```
```
XXX.levelgen.placement.FeatureDecorator -1P
```

</details>

































































































































































































































































































































































































































































































































































<details>
<summary>
net.minecraft.client.multiplayer.ClientPacketListener
</summary>

```diff
- void handleSetSimulationDistance(ClientboundSetSimulationDistancePacket)
```

</details>

























































































































































































































































































































































































































































































































































<details>
<summary>
net.minecraft.data.worldgen.Features
</summary>

```diff
- RandomPatchConfiguration simplePatchConfiguration(ConfiguredFeature,List,int)
- RandomPatchConfiguration simplePatchConfiguration(ConfiguredFeature,List)
+ RandomPatchConfiguration simplePatchConfiguration(ConfiguredFeature,Set,int)
+ RandomPatchConfiguration simplePatchConfiguration(ConfiguredFeature,Set)
```

</details>















































































































<details>
<summary>
net.minecraft.network.protocol.game.ClientboundLoginPacket
</summary>

```diff
- int simulationDistance()
+ void <init>(int,boolean,GameType,GameType,Set,RegistryAccess$RegistryHolder,DimensionType,ResourceKey,long,int,int,boolean,boolean,boolean,boolean)
- void <init>(int,boolean,GameType,GameType,Set,RegistryAccess$RegistryHolder,DimensionType,ResourceKey,long,int,int,int,boolean,boolean,boolean,boolean)
```

</details>







































































































































































































































































<details>
<summary>
net.minecraft.world.entity.ai.behavior.InteractWith
</summary>

```diff
- boolean canInteract(LivingEntity,LivingEntity)
- boolean lambda$start$3(LivingEntity,LivingEntity)
+ boolean lambda$start$3(LivingEntity)
+ boolean lambda$start$5(LivingEntity,LivingEntity)
+ LivingEntity lambda$start$4(LivingEntity)
- void lambda$start$4(Brain,LivingEntity)
+ void lambda$start$6(Brain,LivingEntity)
+ void lambda$start$7(LivingEntity,Brain,List)
```

</details>














<details>
<summary>
net.minecraft.world.entity.ai.behavior.SetEntityLookTarget
</summary>

```diff
- boolean lambda$checkExtraStartConditions$4(LivingEntity,LivingEntity)
+ boolean lambda$start$4(LivingEntity,LivingEntity)
+ void lambda$start$5(Brain,LivingEntity)
+ void lambda$start$6(LivingEntity,Brain,List)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.behavior.SetLookAndInteract
</summary>

```diff
+ List getVisibleEntities(LivingEntity)
- NearestVisibleLivingEntities getVisibleEntities(LivingEntity)
- Optional lambda$start$3(LivingEntity,NearestVisibleLivingEntities)
+ void lambda$start$3(Brain,LivingEntity)
- void lambda$start$4(Brain,LivingEntity)
+ void lambda$start$4(LivingEntity,Brain,List)
```

</details>



















<details>
<summary>
net.minecraft.world.entity.ai.control.LookControl
</summary>

```diff
+ boolean isHasWanted()
- boolean isLookingAtTarget()
```

</details>

































<details>
<summary>
net.minecraft.world.entity.ai.goal.ZombieAttackGoal
</summary>

```diff
+ boolean requiresUpdateEveryTick()
```

</details>

























































<details>
<summary>
net.minecraft.world.level.levelgen.feature.RandomPatchFeature
</summary>

```diff
+ boolean isValid(LevelAccessor,BlockPos,RandomPatchConfiguration)
```

</details>

















<details>
<summary>
net.minecraft.world.level.levelgen.feature.configurations.BlockColumnConfiguration
</summary>

```diff
- BlockPredicate allowedPlacement()
+ boolean allowWater()
- void <init>(List,Direction,BlockPredicate,boolean)
+ void <init>(List,Direction,boolean,boolean)
```

</details>
</details>