## Comparison with [1.19.3-pre2](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.19.3-pre2)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Translations](#translations)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">1.19.3-pre2</th><th>1.19.3-pre3</th></tr><tr><td>World version</td><td><pre>3212</pre></td><td><pre>3213</pre></td></tr><tr><td>Protocol version</td><td><pre>1073741934</pre></td><td><pre>1073741935</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">1.19.3-pre2</th><th>1.19.3-pre3</th></tr><tr><td>com.mojang:authlib</td><td><pre>3.15.28</pre></td><td><pre>3.16.29</pre></td></tr></table>
</details>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
sound_event
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
<hr/>
<details><summary><b><ins>TAGS</ins></b><a name="tags"></a></summary>
<br/>
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
<hr/>
<details><summary><b><ins>TRANSLATIONS</ins></b><a name="translations"></a></summary>
<br/>
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
<hr/>
<details><summary><b><ins>MAPPINGS</ins></b><a name="mappings"></a></summary>
<br/>
<h2>Server<a name="server-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
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
+ XXX.network.protocol.Packet
- XXX.network.protocol.PacketFlow
+ XXX.network.protocol.PacketUtils
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
- XXX.protocol.game.ClientGamePacketListener
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
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
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
+ XXX.network.protocol.Packet
- XXX.network.protocol.PacketFlow
+ XXX.network.protocol.PacketUtils
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
- XXX.protocol.game.ClientGamePacketListener
+ XXX.telemetry.events.WorldLoadEvent
- XXX.telemetry.events.WorldLoadEvent$1
+ XXX.telemetry.events.WorldLoadEvent$WorldLoadEventCallbacks
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
<hr/>