## Comparison with [1.19.3-pre2](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.19.3-pre2)

- [Version data](#version-data)
- [Registries](#registries)
- [Tags](#tags)
- [Translations](#translations)
- [Mappings](#mappings)
  - [Server](#server)
  - [Client](#client)

<hr/>
<details><summary>Version data</summary>
<table><tr><th></th><th align="left">1.19.3-pre2</th><th>1.19.3-pre3</th></tr><tr><td>World version</td><td><code>3212</code></td><td><code>3213</code></td></tr><tr><td>Protocol version</td><td><code>1073741934</code></td><td><code>1073741935</code></td></tr></table>
</details>
<details><summary>Registries</summary>
<details>
<summary>
sound_event.txt
</summary>

```diff
+ minecraft:block.note_block.imitate.creeper
+ minecraft:block.note_block.imitate.ender_dragon
+ minecraft:block.note_block.imitate.piglin
+ minecraft:block.note_block.imitate.skeleton
+ minecraft:block.note_block.imitate.wither_skeleton
+ minecraft:block.note_block.imitate.zombie
```

</details>
</details>
<details><summary>Tags</summary>
<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:block.note_block.imitate.creeper
+ minecraft:block.note_block.imitate.ender_dragon
+ minecraft:block.note_block.imitate.piglin
+ minecraft:block.note_block.imitate.skeleton
+ minecraft:block.note_block.imitate.wither_skeleton
+ minecraft:block.note_block.imitate.zombie
```

</details>
</details>
<details><summary>Translations</summary>
<details>
<summary>
Keys
</summary>

```diff
+ arguments.nbtpath.too_deep: Resulting NBT too deeply nested
+ arguments.nbtpath.too_large: Resulting NBT too large
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
+ net.minecraft.network.chat.ChatDecorator
- net.minecraft.network.chat.ChatType
+ net.minecraft.network.chat.ChatType$Bound
- net.minecraft.network.chat.ChatType$BoundNetwork
+ net.minecraft.network.chat.ChatTypeDecoration
- net.minecraft.network.chat.ChatTypeDecoration$Parameter
+ net.minecraft.network.chat.ChatTypeDecoration$Parameter$Selector
- net.minecraft.network.chat.ClickEvent
+ net.minecraft.network.chat.ClickEvent$Action
- net.minecraft.network.chat.CommonComponents
+ net.minecraft.network.chat.Component
- net.minecraft.network.chat.Component$Serializer
+ net.minecraft.network.chat.ComponentContents
- net.minecraft.network.chat.ComponentContents$1
+ net.minecraft.network.chat.ComponentUtils
- net.minecraft.network.chat.contents.BlockDataSource
+ net.minecraft.network.chat.contents.DataSource
- net.minecraft.network.chat.contents.EntityDataSource
+ net.minecraft.network.chat.contents.KeybindContents
- net.minecraft.network.chat.contents.KeybindResolver
+ net.minecraft.network.chat.contents.LiteralContents
- net.minecraft.network.chat.contents.NbtContents
- net.minecraft.network.chat.contents.package-info
+ net.minecraft.network.chat.contents.ScoreContents
- net.minecraft.network.chat.contents.SelectorContents
+ net.minecraft.network.chat.contents.StorageDataSource
- net.minecraft.network.chat.contents.TranslatableContents
+ net.minecraft.network.chat.contents.TranslatableFormatException
- net.minecraft.network.chat.FilterMask
+ net.minecraft.network.chat.FilterMask$1
- net.minecraft.network.chat.FilterMask$Type
+ net.minecraft.network.chat.FormattedText
- net.minecraft.network.chat.FormattedText$1
+ net.minecraft.network.chat.FormattedText$2
- net.minecraft.network.chat.FormattedText$3
+ net.minecraft.network.chat.FormattedText$4
- net.minecraft.network.chat.FormattedText$ContentConsumer
+ net.minecraft.network.chat.FormattedText$StyledContentConsumer
- net.minecraft.network.chat.HoverEvent
+ net.minecraft.network.chat.HoverEvent$Action
- net.minecraft.network.chat.HoverEvent$EntityTooltipInfo
+ net.minecraft.network.chat.HoverEvent$ItemStackInfo
- net.minecraft.network.chat.LastSeenMessages
+ net.minecraft.network.chat.LastSeenMessages$Packed
- net.minecraft.network.chat.LastSeenMessages$Update
+ net.minecraft.network.chat.LastSeenMessagesTracker
- net.minecraft.network.chat.LastSeenMessagesTracker$Update
+ net.minecraft.network.chat.LastSeenMessagesValidator
- net.minecraft.network.chat.LastSeenTrackedEntry
+ net.minecraft.network.chat.LocalChatSession
- net.minecraft.network.chat.MessageSignature
+ net.minecraft.network.chat.MessageSignature$Packed
- net.minecraft.network.chat.MessageSignatureCache
+ net.minecraft.network.chat.MutableComponent
- net.minecraft.network.chat.OutgoingChatMessage
+ net.minecraft.network.chat.OutgoingChatMessage$Disguised
- net.minecraft.network.chat.OutgoingChatMessage$Player
+ net.minecraft.network.chat.package-info
+ net.minecraft.network.chat.PlayerChatMessage
- net.minecraft.network.chat.RemoteChatSession
+ net.minecraft.network.chat.RemoteChatSession$Data
- net.minecraft.network.chat.SignableCommand
+ net.minecraft.network.chat.SignableCommand$Argument
- net.minecraft.network.chat.SignedMessageBody
+ net.minecraft.network.chat.SignedMessageBody$Packed
- net.minecraft.network.chat.SignedMessageChain
+ net.minecraft.network.chat.SignedMessageChain$DecodeException
- net.minecraft.network.chat.SignedMessageChain$Decoder
+ net.minecraft.network.chat.SignedMessageChain$Encoder
- net.minecraft.network.chat.SignedMessageLink
+ net.minecraft.network.chat.SignedMessageValidator
- net.minecraft.network.chat.SignedMessageValidator$KeyBased
+ net.minecraft.network.chat.Style
- net.minecraft.network.chat.Style$1
+ net.minecraft.network.chat.Style$1Collector
- net.minecraft.network.chat.Style$Serializer
+ net.minecraft.network.chat.SubStringSource
- net.minecraft.network.chat.TextColor
+ net.minecraft.network.chat.ThrowingComponent
- net.minecraft.network.FriendlyByteBuf$Reader
+ net.minecraft.network.FriendlyByteBuf$Writer
- net.minecraft.network.package-info
- net.minecraft.network.PacketDecoder
+ net.minecraft.network.PacketEncoder
- net.minecraft.network.PacketListener
+ net.minecraft.network.PacketSendListener
- net.minecraft.network.PacketSendListener$1
+ net.minecraft.network.PacketSendListener$2
+ net.minecraft.network.protocol.game.ClientboundAddEntityPacket
- net.minecraft.network.protocol.game.ClientboundAddExperienceOrbPacket
+ net.minecraft.network.protocol.game.ClientboundAddPlayerPacket
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
+ net.minecraft.network.protocol.game.ClientboundChangeDifficultyPacket
- net.minecraft.network.protocol.game.ClientboundClearTitlesPacket
- net.minecraft.network.protocol.game.ClientboundCommandsPacket
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket$ArgumentNodeStub
- net.minecraft.network.protocol.game.ClientboundCommandsPacket$Entry
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket$LiteralNodeStub
- net.minecraft.network.protocol.game.ClientboundCommandsPacket$NodeResolver
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket$NodeStub
+ net.minecraft.network.protocol.game.ClientboundCommandSuggestionsPacket
- net.minecraft.network.protocol.game.ClientboundContainerClosePacket
+ net.minecraft.network.protocol.game.ClientboundContainerSetContentPacket
- net.minecraft.network.protocol.game.ClientboundContainerSetDataPacket
+ net.minecraft.network.protocol.game.ClientboundContainerSetSlotPacket
- net.minecraft.network.protocol.game.ClientboundCooldownPacket
+ net.minecraft.network.protocol.game.ClientboundCustomChatCompletionsPacket
- net.minecraft.network.protocol.game.ClientboundCustomChatCompletionsPacket$Action
+ net.minecraft.network.protocol.game.ClientboundCustomPayloadPacket
- net.minecraft.network.protocol.game.ClientGamePacketListener
+ net.minecraft.network.protocol.Packet
- net.minecraft.network.protocol.PacketFlow
+ net.minecraft.network.protocol.PacketUtils
- net.minecraft.network.RateKickingConnection
+ net.minecraft.network.SkipPacketException
- net.minecraft.network.TickablePacketListener
+ net.minecraft.network.Varint21FrameDecoder
- net.minecraft.network.Varint21LengthFieldPrepender
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.minecraft.commands.CommandSourceStack +1M -1M
```
```
XXX.minecraft.commands.SharedSuggestionProvider +1P -1P
```
```
XXX.commands.arguments.NbtPathArgument +3M -1M | +4P
```
```
XXX.minecraft.core.Registry +2M | +1P
```
```
XXX.minecraft.nbt.DoubleTag +1M
```
```
XXX.minecraft.nbt.EndTag +1M
```
```
XXX.minecraft.nbt.FloatTag +1M
```
```
XXX.minecraft.nbt.IntArrayTag +1M
```
```
XXX.minecraft.nbt.IntTag +1M
```
```
XXX.minecraft.nbt.LongArrayTag +1M
```
```
XXX.minecraft.nbt.LongTag +1M
```
```
XXX.minecraft.nbt.StringTag +1M
```
```
XXX.minecraft.network.FriendlyByteBuf +2M
```
```
XXX.network.syncher.SynchedEntityData -1M
```
```
XXX.commands.data.DataCommands +17M -20M | -2P
```
```
XXX.server.level.ServerLevel +1M -2M
```
```
XXX.minecraft.sounds.Music +3M -3M | +1P -1P
```
```
XXX.minecraft.sounds.SoundEvent +8M -1M | +2P
```
```
XXX.entity.player.Player +1M
```
```
XXX.world.item.Instrument +2M -2M | +1P -1P
```
```
XXX.world.level.Level +1M -1M | +1P -2P
```
```
XXX.level.biome.AmbientAdditionsSettings +3M -3M | +1P -1P
```
```
XXX.level.biome.BiomeSpecialEffects$Builder +1M -1M
```
```
XXX.block.state.StateHolder +1M
```
```
XXX.state.properties.NoteBlockInstrument +2M -2M | +1P -1P
```

</details>
















































































































<details>
<summary>
net.minecraft.commands.CommandSourceStack
</summary>

```diff
+ Collection getAvailableSoundEvents()
- Stream getAvailableSounds()
```

</details>














<details>
<summary>
net.minecraft.commands.arguments.NbtPathArgument
</summary>

```diff
+ boolean lambda$createTagPredicate$1(CompoundTag,Tag)
- boolean lambda$createTagPredicate$3(CompoundTag,Tag)
- Message lambda$static$1(Object)
- Message lambda$static$2(Object)
```

</details>






















































































<details>
<summary>
net.minecraft.core.Registry
</summary>

```diff
- Holder$Reference registerForHolder(Registry,ResourceKey,Object)
- Holder$Reference registerForHolder(Registry,ResourceLocation,Object)
```

</details>




















































































































































































<details>
<summary>
net.minecraft.nbt.DoubleTag
</summary>

```diff
- int sizeInBits()
```

</details>
<details>
<summary>
net.minecraft.nbt.EndTag
</summary>

```diff
- int sizeInBits()
```

</details>
<details>
<summary>
net.minecraft.nbt.FloatTag
</summary>

```diff
- int sizeInBits()
```

</details>
<details>
<summary>
net.minecraft.nbt.IntArrayTag
</summary>

```diff
- int sizeInBits()
```

</details>
<details>
<summary>
net.minecraft.nbt.IntTag
</summary>

```diff
- int sizeInBits()
```

</details>


<details>
<summary>
net.minecraft.nbt.LongArrayTag
</summary>

```diff
- int sizeInBits()
```

</details>
<details>
<summary>
net.minecraft.nbt.LongTag
</summary>

```diff
- int sizeInBits()
```

</details>












<details>
<summary>
net.minecraft.nbt.StringTag
</summary>

```diff
- int sizeInBits()
```

</details>
















<details>
<summary>
net.minecraft.network.FriendlyByteBuf
</summary>

```diff
- Holder readById(IdMap,FriendlyByteBuf$Reader)
- void writeId(IdMap,Holder,FriendlyByteBuf$Writer)
```

</details>









































































































<details>
<summary>
net.minecraft.network.syncher.SynchedEntityData
</summary>

```diff
+ void clearDirty()
```

</details>
























































































<details>
<summary>
net.minecraft.server.commands.data.DataCommands
</summary>

```diff
- ArgumentBuilder lambda$decorateModification$22(DataCommands$DataProvider,DataCommands$DataProvider,DataCommands$DataManipulator,ArgumentBuilder)
- ArgumentBuilder lambda$decorateModification$23(DataCommands$DataProvider,DataCommands$DataProvider,DataCommands$DataManipulator)
+ ArgumentBuilder lambda$decorateModification$24(DataCommands$DataProvider,DataCommands$DataProvider,DataCommands$DataManipulator,ArgumentBuilder)
- ArgumentBuilder lambda$decorateModification$25(DataCommands$DataProvider,DataCommands$DataManipulator)
+ ArgumentBuilder lambda$decorateModification$25(DataCommands$DataProvider,DataCommands$DataProvider,DataCommands$DataManipulator)
- ArgumentBuilder lambda$decorateModification$26(BiConsumer,DataCommands$DataProvider,ArgumentBuilder)
+ ArgumentBuilder lambda$decorateModification$27(DataCommands$DataProvider,DataCommands$DataManipulator)
+ ArgumentBuilder lambda$decorateModification$28(BiConsumer,DataCommands$DataProvider,ArgumentBuilder)
- ArgumentBuilder lambda$register$11(DataCommands$DataProvider,ArgumentBuilder)
+ ArgumentBuilder lambda$register$15(DataCommands$DataProvider,ArgumentBuilder)
- ArgumentBuilder lambda$register$7(DataCommands$DataProvider,ArgumentBuilder)
+ ArgumentBuilder lambda$register$9(DataCommands$DataProvider,ArgumentBuilder)
- boolean lambda$register$5(CommandSourceStack)
+ boolean lambda$register$7(CommandSourceStack)
- DataCommands$DataProvider lambda$static$3(Function)
- DataCommands$DataProvider lambda$static$4(Function)
+ DataCommands$DataProvider lambda$static$5(Function)
+ DataCommands$DataProvider lambda$static$6(Function)
+ int insertAtIndex(int,CompoundTag,NbtPathArgument$NbtPath,List)
- int lambda$decorateModification$20(DataCommands$DataProvider,DataCommands$DataProvider,DataCommands$DataManipulator,CommandContext)
- int lambda$decorateModification$21(DataCommands$DataProvider,DataCommands$DataProvider,DataCommands$DataManipulator,CommandContext)
+ int lambda$decorateModification$22(DataCommands$DataProvider,DataCommands$DataProvider,DataCommands$DataManipulator,CommandContext)
+ int lambda$decorateModification$23(DataCommands$DataProvider,DataCommands$DataProvider,DataCommands$DataManipulator,CommandContext)
- int lambda$decorateModification$24(DataCommands$DataProvider,DataCommands$DataManipulator,CommandContext)
+ int lambda$decorateModification$26(DataCommands$DataProvider,DataCommands$DataManipulator,CommandContext)
+ int lambda$register$11(DataCommands$DataProvider,CommandContext)
- int lambda$register$14(CommandContext,CompoundTag,NbtPathArgument$NbtPath,List)
+ int lambda$register$14(DataCommands$DataProvider,CommandContext)
- int lambda$register$15(CommandContext,CompoundTag,NbtPathArgument$NbtPath,List)
+ int lambda$register$19(CommandContext,CompoundTag,NbtPathArgument$NbtPath,List)
+ int lambda$register$20(CommandContext,CompoundTag,NbtPathArgument$NbtPath,List)
- int lambda$register$6(DataCommands$DataProvider,CommandContext)
- int lambda$register$9(DataCommands$DataProvider,CommandContext)
+ Message lambda$static$3(Object)
+ Message lambda$static$4(Object)
- void lambda$register$19(ArgumentBuilder,DataCommands$DataManipulatorDecorator)
+ void lambda$register$21(ArgumentBuilder,DataCommands$DataManipulatorDecorator)
```

</details>





























<details>
<summary>
net.minecraft.server.level.ServerLevel
</summary>

```diff
+ void playCustomSound(Player,Vec3,ResourceLocation,SoundSource,float,float,double,long)
- void playSeededSound(Player,double,double,double,Holder,SoundSource,float,float,long)
+ void playSeededSound(Player,double,double,double,SoundEvent,SoundSource,float,float,long)
```

</details>
















































































<details>
<summary>
net.minecraft.sounds.Music
</summary>

```diff
- Holder getEvent()
- Holder lambda$static$0(Music)
+ SoundEvent getEvent()
+ SoundEvent lambda$static$0(Music)
- void <init>(Holder,int,int,boolean)
+ void <init>(SoundEvent,int,int,boolean)
```

</details>
<details>
<summary>
net.minecraft.sounds.SoundEvent
</summary>

```diff
- App lambda$static$0(RecordCodecBuilder$Instance)
+ float legacySoundRange(float)
- Optional fixedRange()
- SoundEvent create(ResourceLocation,Optional)
- SoundEvent lambda$create$1(ResourceLocation,Float)
- SoundEvent lambda$create$2(ResourceLocation)
- SoundEvent readFromNetwork(FriendlyByteBuf)
- void <clinit>()
- void writeToNetwork(FriendlyByteBuf)
```

</details>







































































































































































































































































































































































































































































































































































































































































































<details>
<summary>
net.minecraft.world.entity.player.Player
</summary>

```diff
- void doCloseContainer()
```

</details>
































































































































<details>
<summary>
net.minecraft.world.item.Instrument
</summary>

```diff
- Holder soundEvent()
+ SoundEvent soundEvent()
- void <init>(Holder,int,float)
+ void <init>(SoundEvent,int,float)
```

</details>












































































































<details>
<summary>
net.minecraft.world.level.Level
</summary>

```diff
+ void playCustomSound(Player,Vec3,ResourceLocation,SoundSource,float,float,double)
- void playSeededSound(Player,double,double,double,SoundEvent,SoundSource,float,float,long)
```

</details>















<details>
<summary>
net.minecraft.world.level.biome.AmbientAdditionsSettings
</summary>

```diff
- Holder getSoundEvent()
- Holder lambda$static$0(AmbientAdditionsSettings)
+ SoundEvent getSoundEvent()
+ SoundEvent lambda$static$0(AmbientAdditionsSettings)
- void <init>(Holder,double)
+ void <init>(SoundEvent,double)
```

</details>









<details>
<summary>
net.minecraft.world.level.biome.BiomeSpecialEffects$Builder
</summary>

```diff
- BiomeSpecialEffects$Builder ambientLoopSound(Holder)
+ BiomeSpecialEffects$Builder ambientLoopSound(SoundEvent)
```

</details>






















































































































































































































































<details>
<summary>
net.minecraft.world.level.block.state.StateHolder
</summary>

```diff
- Object trySetValue(Property,Comparable)
```

</details>














<details>
<summary>
net.minecraft.world.level.block.state.properties.NoteBlockInstrument
</summary>

```diff
- Holder getSoundEvent()
+ SoundEvent getSoundEvent()
- void <init>(String,int,String,Holder,NoteBlockInstrument$Type)
+ void <init>(String,int,String,SoundEvent,NoteBlockInstrument$Type)
```

</details>








































































































































































































































































































































































































































































































































































































































<h2>Client</h2>
<details>
<summary>
Classes
</summary>

```diff
+ net.minecraft.client.telemetry.events.WorldLoadEvent
- net.minecraft.client.telemetry.events.WorldLoadEvent$1
+ net.minecraft.client.telemetry.events.WorldLoadEvent$WorldLoadEventCallbacks
+ net.minecraft.network.chat.ChatDecorator
- net.minecraft.network.chat.ChatType
+ net.minecraft.network.chat.ChatType$Bound
- net.minecraft.network.chat.ChatType$BoundNetwork
+ net.minecraft.network.chat.ChatTypeDecoration
- net.minecraft.network.chat.ChatTypeDecoration$Parameter
+ net.minecraft.network.chat.ChatTypeDecoration$Parameter$Selector
- net.minecraft.network.chat.ClickEvent
+ net.minecraft.network.chat.ClickEvent$Action
- net.minecraft.network.chat.CommonComponents
+ net.minecraft.network.chat.Component
- net.minecraft.network.chat.Component$Serializer
+ net.minecraft.network.chat.ComponentContents
- net.minecraft.network.chat.ComponentContents$1
+ net.minecraft.network.chat.ComponentUtils
- net.minecraft.network.chat.contents.BlockDataSource
+ net.minecraft.network.chat.contents.DataSource
- net.minecraft.network.chat.contents.EntityDataSource
+ net.minecraft.network.chat.contents.KeybindContents
- net.minecraft.network.chat.contents.KeybindResolver
+ net.minecraft.network.chat.contents.LiteralContents
- net.minecraft.network.chat.contents.NbtContents
- net.minecraft.network.chat.contents.package-info
+ net.minecraft.network.chat.contents.ScoreContents
- net.minecraft.network.chat.contents.SelectorContents
+ net.minecraft.network.chat.contents.StorageDataSource
- net.minecraft.network.chat.contents.TranslatableContents
+ net.minecraft.network.chat.contents.TranslatableFormatException
- net.minecraft.network.chat.FilterMask
+ net.minecraft.network.chat.FilterMask$1
- net.minecraft.network.chat.FilterMask$Type
+ net.minecraft.network.chat.FormattedText
- net.minecraft.network.chat.FormattedText$1
+ net.minecraft.network.chat.FormattedText$2
- net.minecraft.network.chat.FormattedText$3
+ net.minecraft.network.chat.FormattedText$4
- net.minecraft.network.chat.FormattedText$ContentConsumer
+ net.minecraft.network.chat.FormattedText$StyledContentConsumer
- net.minecraft.network.chat.HoverEvent
+ net.minecraft.network.chat.HoverEvent$Action
- net.minecraft.network.chat.HoverEvent$EntityTooltipInfo
+ net.minecraft.network.chat.HoverEvent$ItemStackInfo
- net.minecraft.network.chat.LastSeenMessages
+ net.minecraft.network.chat.LastSeenMessages$Packed
- net.minecraft.network.chat.LastSeenMessages$Update
+ net.minecraft.network.chat.LastSeenMessagesTracker
- net.minecraft.network.chat.LastSeenMessagesTracker$Update
+ net.minecraft.network.chat.LastSeenMessagesValidator
- net.minecraft.network.chat.LastSeenTrackedEntry
+ net.minecraft.network.chat.LocalChatSession
- net.minecraft.network.chat.MessageSignature
+ net.minecraft.network.chat.MessageSignature$Packed
- net.minecraft.network.chat.MessageSignatureCache
+ net.minecraft.network.chat.MutableComponent
- net.minecraft.network.chat.OutgoingChatMessage
+ net.minecraft.network.chat.OutgoingChatMessage$Disguised
- net.minecraft.network.chat.OutgoingChatMessage$Player
+ net.minecraft.network.chat.package-info
+ net.minecraft.network.chat.PlayerChatMessage
- net.minecraft.network.chat.RemoteChatSession
+ net.minecraft.network.chat.RemoteChatSession$Data
- net.minecraft.network.chat.SignableCommand
+ net.minecraft.network.chat.SignableCommand$Argument
- net.minecraft.network.chat.SignedMessageBody
+ net.minecraft.network.chat.SignedMessageBody$Packed
- net.minecraft.network.chat.SignedMessageChain
+ net.minecraft.network.chat.SignedMessageChain$DecodeException
- net.minecraft.network.chat.SignedMessageChain$Decoder
+ net.minecraft.network.chat.SignedMessageChain$Encoder
- net.minecraft.network.chat.SignedMessageLink
+ net.minecraft.network.chat.SignedMessageValidator
- net.minecraft.network.chat.SignedMessageValidator$KeyBased
+ net.minecraft.network.chat.Style
- net.minecraft.network.chat.Style$1
+ net.minecraft.network.chat.Style$1Collector
- net.minecraft.network.chat.Style$Serializer
+ net.minecraft.network.chat.SubStringSource
- net.minecraft.network.chat.TextColor
+ net.minecraft.network.chat.ThrowingComponent
- net.minecraft.network.FriendlyByteBuf$Reader
+ net.minecraft.network.FriendlyByteBuf$Writer
- net.minecraft.network.package-info
- net.minecraft.network.PacketDecoder
+ net.minecraft.network.PacketEncoder
- net.minecraft.network.PacketListener
+ net.minecraft.network.PacketSendListener
- net.minecraft.network.PacketSendListener$1
+ net.minecraft.network.PacketSendListener$2
+ net.minecraft.network.protocol.game.ClientboundAddEntityPacket
- net.minecraft.network.protocol.game.ClientboundAddExperienceOrbPacket
+ net.minecraft.network.protocol.game.ClientboundAddPlayerPacket
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
+ net.minecraft.network.protocol.game.ClientboundChangeDifficultyPacket
- net.minecraft.network.protocol.game.ClientboundClearTitlesPacket
- net.minecraft.network.protocol.game.ClientboundCommandsPacket
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket$ArgumentNodeStub
- net.minecraft.network.protocol.game.ClientboundCommandsPacket$Entry
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket$LiteralNodeStub
- net.minecraft.network.protocol.game.ClientboundCommandsPacket$NodeResolver
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket$NodeStub
+ net.minecraft.network.protocol.game.ClientboundCommandSuggestionsPacket
- net.minecraft.network.protocol.game.ClientboundContainerClosePacket
+ net.minecraft.network.protocol.game.ClientboundContainerSetContentPacket
- net.minecraft.network.protocol.game.ClientboundContainerSetDataPacket
+ net.minecraft.network.protocol.game.ClientboundContainerSetSlotPacket
- net.minecraft.network.protocol.game.ClientboundCooldownPacket
+ net.minecraft.network.protocol.game.ClientboundCustomChatCompletionsPacket
- net.minecraft.network.protocol.game.ClientboundCustomChatCompletionsPacket$Action
+ net.minecraft.network.protocol.game.ClientboundCustomPayloadPacket
- net.minecraft.network.protocol.game.ClientGamePacketListener
+ net.minecraft.network.protocol.Packet
- net.minecraft.network.protocol.PacketFlow
+ net.minecraft.network.protocol.PacketUtils
- net.minecraft.network.RateKickingConnection
+ net.minecraft.network.SkipPacketException
- net.minecraft.network.TickablePacketListener
+ net.minecraft.network.Varint21FrameDecoder
- net.minecraft.network.Varint21LengthFieldPrepender
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.minecraft.client.GameNarrator +2M -1M
```
```
XXX.gui.components.ImageButton -1M
```
```
XXX.gui.screens.InBedChatScreen +2M | +1P
```
```
XXX.client.model.VexModel +1M -3M | +1P
```
```
XXX.client.multiplayer.ClientLevel +1M -2M
```
```
XXX.client.multiplayer.ClientPacketListener -1M
```
```
XXX.multiplayer.chat.ChatListener -1M
```
```
XXX.resources.sounds.BiomeAmbientSoundsHandler +2M -2M
```
```
XXX.resources.sounds.SimpleSoundInstance +1M
```
```
XXX.client.sounds.WeighedSoundEvents -1M | -2P
```
```
XXX.telemetry.events.PerformanceMetricsEvent +4M -5M | -1P
```
```
XXX.telemetry.events.WorldUnloadEvent +1M -1M | +1P
```
```
XXX.minecraft.commands.CommandSourceStack +1M -1M
```
```
XXX.minecraft.commands.SharedSuggestionProvider +1P -1P
```
```
XXX.commands.arguments.NbtPathArgument +3M -1M | +4P
```
```
XXX.minecraft.core.Registry +2M | +1P
```
```
XXX.minecraft.nbt.DoubleTag +1M
```
```
XXX.minecraft.nbt.EndTag +1M
```
```
XXX.minecraft.nbt.FloatTag +1M
```
```
XXX.minecraft.nbt.IntArrayTag +1M
```
```
XXX.minecraft.nbt.IntTag +1M
```
```
XXX.minecraft.nbt.LongArrayTag +1M
```
```
XXX.minecraft.nbt.LongTag +1M
```
```
XXX.minecraft.nbt.StringTag +1M
```
```
XXX.minecraft.network.FriendlyByteBuf +2M
```
```
XXX.network.syncher.SynchedEntityData -1M
```
```
XXX.server.commands.ExecuteCommand +21M -22M
```
```
XXX.server.level.ServerEntity +1P
```
```
XXX.minecraft.sounds.Musics +1M -1M
```
```
XXX.minecraft.sounds.SoundEvents +7M -2M | +65P -59P
```
```
XXX.level.biome.AmbientMoodSettings +3M -3M | +1P -1P
```

</details>








































































































































































































































































<details>
<summary>
net.minecraft.client.GameNarrator
</summary>

```diff
- void say(Component)
- void sayChat(Component)
+ void sayChatNow(Supplier)
```

</details>






































































<details>
<summary>
net.minecraft.client.gui.components.ImageButton
</summary>

```diff
+ void setPosition(int,int)
```

</details>





























































<details>
<summary>
net.minecraft.client.gui.screens.InBedChatScreen
</summary>

```diff
- boolean charTyped(char,int)
- void render(PoseStack,int,int,float)
```

</details>





















































































































































































<details>
<summary>
net.minecraft.client.model.VexModel
</summary>

```diff
- void offsetStackPosition(PoseStack,boolean)
+ void offsetSwordPivot(PoseStack)
+ void offsetSwordPosition(PoseStack)
+ void rotateSwordWithArm(PoseStack)
```

</details>



















<details>
<summary>
net.minecraft.client.multiplayer.ClientLevel
</summary>

```diff
+ void playCustomSound(Player,Vec3,ResourceLocation,SoundSource,float,float,double,long)
- void playSeededSound(Player,double,double,double,Holder,SoundSource,float,float,long)
+ void playSeededSound(Player,double,double,double,SoundEvent,SoundSource,float,float,long)
```

</details>

<details>
<summary>
net.minecraft.client.multiplayer.ClientPacketListener
</summary>

```diff
+ void handleCustomSoundEvent(ClientboundCustomSoundPacket)
```

</details>







<details>
<summary>
net.minecraft.client.multiplayer.chat.ChatListener
</summary>

```diff
+ Component lambda$narrateChatMessage$3(ChatType$Bound,Component)
```

</details>























































































































































































































































































































































































<details>
<summary>
net.minecraft.client.resources.sounds.BiomeAmbientSoundsHandler
</summary>

```diff
- BiomeAmbientSoundsHandler$LoopSoundInstance lambda$tick$0(Holder,Biome,BiomeAmbientSoundsHandler$LoopSoundInstance)
+ BiomeAmbientSoundsHandler$LoopSoundInstance lambda$tick$0(SoundEvent,Biome,BiomeAmbientSoundsHandler$LoopSoundInstance)
- void lambda$tick$1(Biome,Holder)
+ void lambda$tick$1(Biome,SoundEvent)
```

</details>



<details>
<summary>
net.minecraft.client.resources.sounds.SimpleSoundInstance
</summary>

```diff
- SimpleSoundInstance forUI(Holder,float)
```

</details>


























<details>
<summary>
net.minecraft.client.sounds.WeighedSoundEvents
</summary>

```diff
+ ResourceLocation getResourceLocation()
```

</details>









<details>
<summary>
net.minecraft.client.telemetry.events.PerformanceMetricsEvent
</summary>

```diff
- void <init>()
+ void <init>(TelemetryEventSender)
+ void lambda$send$0(TelemetryPropertyMap$Builder)
- void lambda$sendEvent$0(TelemetryPropertyMap$Builder)
+ void send(TelemetryEventSender)
+ void sendEvent()
- void sendEvent(TelemetryEventSender)
+ void tick()
- void tick(TelemetryEventSender)
```

</details>
<details>
<summary>
net.minecraft.client.telemetry.events.WorldUnloadEvent
</summary>

```diff
+ void loadedWorld()
- void onPlayerInfoReceived()
```

</details>
















<details>
<summary>
net.minecraft.commands.CommandSourceStack
</summary>

```diff
+ Collection getAvailableSoundEvents()
- Stream getAvailableSounds()
```

</details>














<details>
<summary>
net.minecraft.commands.arguments.NbtPathArgument
</summary>

```diff
+ boolean lambda$createTagPredicate$1(CompoundTag,Tag)
- boolean lambda$createTagPredicate$3(CompoundTag,Tag)
- Message lambda$static$1(Object)
- Message lambda$static$2(Object)
```

</details>






















































































<details>
<summary>
net.minecraft.core.Registry
</summary>

```diff
- Holder$Reference registerForHolder(Registry,ResourceKey,Object)
- Holder$Reference registerForHolder(Registry,ResourceLocation,Object)
```

</details>




















































































































































































<details>
<summary>
net.minecraft.nbt.DoubleTag
</summary>

```diff
- int sizeInBits()
```

</details>
<details>
<summary>
net.minecraft.nbt.EndTag
</summary>

```diff
- int sizeInBits()
```

</details>
<details>
<summary>
net.minecraft.nbt.FloatTag
</summary>

```diff
- int sizeInBits()
```

</details>
<details>
<summary>
net.minecraft.nbt.IntArrayTag
</summary>

```diff
- int sizeInBits()
```

</details>
<details>
<summary>
net.minecraft.nbt.IntTag
</summary>

```diff
- int sizeInBits()
```

</details>


<details>
<summary>
net.minecraft.nbt.LongArrayTag
</summary>

```diff
- int sizeInBits()
```

</details>
<details>
<summary>
net.minecraft.nbt.LongTag
</summary>

```diff
- int sizeInBits()
```

</details>












<details>
<summary>
net.minecraft.nbt.StringTag
</summary>

```diff
- int sizeInBits()
```

</details>
















<details>
<summary>
net.minecraft.network.FriendlyByteBuf
</summary>

```diff
- Holder readById(IdMap,FriendlyByteBuf$Reader)
- void writeId(IdMap,Holder,FriendlyByteBuf$Writer)
```

</details>









































































































<details>
<summary>
net.minecraft.network.syncher.SynchedEntityData
</summary>

```diff
+ void clearDirty()
```

</details>
























































<details>
<summary>
net.minecraft.server.commands.ExecuteCommand
</summary>

```diff
- ArgumentBuilder lambda$addConditionals$54(CommandNode,boolean,DataCommands$DataProvider,ArgumentBuilder)
+ ArgumentBuilder lambda$addConditionals$55(CommandNode,boolean,DataCommands$DataProvider,ArgumentBuilder)
- boolean lambda$addConditionals$37(CommandContext)
+ boolean lambda$addConditionals$40(CommandContext)
- boolean lambda$addConditionals$40(Integer,Integer)
- boolean lambda$addConditionals$41(CommandContext)
+ boolean lambda$addConditionals$41(Integer,Integer)
+ boolean lambda$addConditionals$42(CommandContext)
- boolean lambda$addConditionals$42(Integer,Integer)
- boolean lambda$addConditionals$43(CommandContext)
+ boolean lambda$addConditionals$43(Integer,Integer)
+ boolean lambda$addConditionals$44(CommandContext)
- boolean lambda$addConditionals$44(Integer,Integer)
- boolean lambda$addConditionals$45(CommandContext)
+ boolean lambda$addConditionals$45(Integer,Integer)
+ boolean lambda$addConditionals$46(CommandContext)
- boolean lambda$addConditionals$46(Integer,Integer)
- boolean lambda$addConditionals$47(CommandContext)
+ boolean lambda$addConditionals$47(Integer,Integer)
+ boolean lambda$addConditionals$49(CommandContext)
- boolean lambda$addConditionals$51(CommandContext)
+ boolean lambda$addConditionals$52(CommandContext)
- Collection lambda$addConditional$57(boolean,ExecuteCommand$CommandPredicate,CommandContext)
+ Collection lambda$addConditional$58(boolean,ExecuteCommand$CommandPredicate,CommandContext)
- Collection lambda$addConditionals$49(boolean,CommandContext)
+ Collection lambda$addConditionals$50(boolean,CommandContext)
- Collection lambda$addConditionals$52(boolean,DataCommands$DataProvider,CommandContext)
+ Collection lambda$addConditionals$53(boolean,DataCommands$DataProvider,CommandContext)
- Collection lambda$addIfBlocksConditional$59(boolean,boolean,CommandContext)
+ Collection lambda$addIfBlocksConditional$60(boolean,boolean,CommandContext)
- int lambda$addConditional$58(boolean,ExecuteCommand$CommandPredicate,CommandContext)
+ int lambda$addConditional$59(boolean,ExecuteCommand$CommandPredicate,CommandContext)
- int lambda$addConditionals$50(CommandContext)
+ int lambda$addConditionals$51(CommandContext)
- int lambda$addConditionals$53(DataCommands$DataProvider,CommandContext)
+ int lambda$addConditionals$54(DataCommands$DataProvider,CommandContext)
- int lambda$addIfBlocksConditional$60(boolean,CommandContext)
+ int lambda$addIfBlocksConditional$62(boolean,CommandContext)
- int lambda$createNumericConditionalHandler$55(ExecuteCommand$CommandNumericPredicate,CommandContext)
+ int lambda$createNumericConditionalHandler$57(ExecuteCommand$CommandNumericPredicate,CommandContext)
+ Tag lambda$storeData$36(IntFunction,int)
- void lambda$storeData$36(DataAccessor,boolean,NbtPathArgument$NbtPath,IntFunction,CommandContext,boolean,int)
+ void lambda$storeData$37(DataAccessor,boolean,NbtPathArgument$NbtPath,IntFunction,CommandContext,boolean,int)
```

</details>



















































































































































<details>
<summary>
net.minecraft.sounds.Musics
</summary>

```diff
- Music createGameMusic(Holder)
+ Music createGameMusic(SoundEvent)
```

</details>
<details>
<summary>
net.minecraft.sounds.SoundEvents
</summary>

```diff
- Holder register(ResourceLocation,ResourceLocation,float)
- Holder$Reference lambda$registerGoatHornSoundVariants$0(int)
- Holder$Reference registerForHolder(ResourceLocation,ResourceLocation)
- Holder$Reference registerForHolder(ResourceLocation)
- Holder$Reference registerForHolder(String)
+ SoundEvent lambda$registerGoatHornSoundVariants$0(int)
- SoundEvent register(ResourceLocation,ResourceLocation)
- SoundEvent register(ResourceLocation)
+ SoundEvent register(String,float)
```

</details>





































































































































































































































































































































































































































































































































































































































































































































































































































































































































































<details>
<summary>
net.minecraft.world.level.biome.AmbientMoodSettings
</summary>

```diff
- Holder getSoundEvent()
- Holder lambda$static$0(AmbientMoodSettings)
+ SoundEvent getSoundEvent()
+ SoundEvent lambda$static$0(AmbientMoodSettings)
- void <init>(Holder,int,int,double)
+ void <init>(SoundEvent,int,int,double)
```

</details>
</details>