<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 1.19.3-pre3 ⌋<br/><img width="0" height="0"></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
:warning: This repository is not official, approved, endorsed, associated or connected with Mojang :warning:
<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>1.19.3-pre3</td></tr>
<tr><th>Type</th><td>pre-releases</td></tr>
<tr><th>Release time</th><td>2022-11-29T14:28:08+00:00</td></tr>
<tr><th>SHA1</th><td>bb3660f6b20cf3275bdd9abd2adba2d64157dda3</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/bb3660f6b20cf3275bdd9abd2adba2d64157dda3/1.19.3-pre3.json">https://piston-meta.mojang.com/v1/packages/bb3660f6b20cf3275bdd9abd2adba2d64157dda3/1.19.3-pre3.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/74d3793f18d13d323c17240cc1d7962af605bd88/2.json">https://piston-meta.mojang.com/v1/packages/74d3793f18d13d323c17240cc1d7962af605bd88/2.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/323175facb90c05b07dff84b4cff39fd9cab138a/server.jar">https://piston-data.mojang.com/v1/objects/323175facb90c05b07dff84b4cff39fd9cab138a/server.jar</a></td></tr>
<tr><th>Server mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/7987f7f32fc1eb9b3da101feb04bd2dd533c2279/server.txt">https://piston-data.mojang.com/v1/objects/7987f7f32fc1eb9b3da101feb04bd2dd533c2279/server.txt</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/2e935c01cccf2b1d1a7845ec596555685baa49ef/client.jar">https://piston-data.mojang.com/v1/objects/2e935c01cccf2b1d1a7845ec596555685baa49ef/client.jar</a></td></tr>
<tr><th>Client mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/be5166aabd346178403bd95bc6c83aa1cab07915/client.txt">https://piston-data.mojang.com/v1/objects/be5166aabd346178403bd95bc6c83aa1cab07915/client.txt</a></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
<i>Go to the README.md file to make sure you see the full comparison</i>
<br/><img width="0" height="0"></td></tr>
</table></html>

<br/>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/1.19.3-pre2">1.19.3-pre2</a>

# Mappings

### Client




<details><summary>Classes</summary>

```diff
- net.minecraft.client.telemetry.events.WorldLoadEvent
+ net.minecraft.client.telemetry.events.WorldLoadEvent$1
- net.minecraft.client.telemetry.events.WorldLoadEvent$WorldLoadEventCallbacks
- net.minecraft.network.chat.ChatDecorator
+ net.minecraft.network.chat.ChatType
- net.minecraft.network.chat.ChatType$Bound
+ net.minecraft.network.chat.ChatType$BoundNetwork
- net.minecraft.network.chat.ChatTypeDecoration
+ net.minecraft.network.chat.ChatTypeDecoration$Parameter
- net.minecraft.network.chat.ChatTypeDecoration$Parameter$Selector
+ net.minecraft.network.chat.ClickEvent
- net.minecraft.network.chat.ClickEvent$Action
+ net.minecraft.network.chat.CommonComponents
- net.minecraft.network.chat.Component
+ net.minecraft.network.chat.Component$Serializer
- net.minecraft.network.chat.ComponentContents
+ net.minecraft.network.chat.ComponentContents$1
- net.minecraft.network.chat.ComponentUtils
+ net.minecraft.network.chat.contents.BlockDataSource
- net.minecraft.network.chat.contents.DataSource
+ net.minecraft.network.chat.contents.EntityDataSource
- net.minecraft.network.chat.contents.KeybindContents
+ net.minecraft.network.chat.contents.KeybindResolver
- net.minecraft.network.chat.contents.LiteralContents
+ net.minecraft.network.chat.contents.NbtContents
+ net.minecraft.network.chat.contents.package-info
- net.minecraft.network.chat.contents.ScoreContents
+ net.minecraft.network.chat.contents.SelectorContents
- net.minecraft.network.chat.contents.StorageDataSource
+ net.minecraft.network.chat.contents.TranslatableContents
- net.minecraft.network.chat.contents.TranslatableFormatException
+ net.minecraft.network.chat.FilterMask
- net.minecraft.network.chat.FilterMask$1
+ net.minecraft.network.chat.FilterMask$Type
- net.minecraft.network.chat.FormattedText
+ net.minecraft.network.chat.FormattedText$1
- net.minecraft.network.chat.FormattedText$2
+ net.minecraft.network.chat.FormattedText$3
- net.minecraft.network.chat.FormattedText$4
+ net.minecraft.network.chat.FormattedText$ContentConsumer
- net.minecraft.network.chat.FormattedText$StyledContentConsumer
+ net.minecraft.network.chat.HoverEvent
- net.minecraft.network.chat.HoverEvent$Action
+ net.minecraft.network.chat.HoverEvent$EntityTooltipInfo
- net.minecraft.network.chat.HoverEvent$ItemStackInfo
+ net.minecraft.network.chat.LastSeenMessages
- net.minecraft.network.chat.LastSeenMessages$Packed
+ net.minecraft.network.chat.LastSeenMessages$Update
- net.minecraft.network.chat.LastSeenMessagesTracker
+ net.minecraft.network.chat.LastSeenMessagesTracker$Update
- net.minecraft.network.chat.LastSeenMessagesValidator
+ net.minecraft.network.chat.LastSeenTrackedEntry
- net.minecraft.network.chat.LocalChatSession
+ net.minecraft.network.chat.MessageSignature
- net.minecraft.network.chat.MessageSignature$Packed
+ net.minecraft.network.chat.MessageSignatureCache
- net.minecraft.network.chat.MutableComponent
+ net.minecraft.network.chat.OutgoingChatMessage
- net.minecraft.network.chat.OutgoingChatMessage$Disguised
+ net.minecraft.network.chat.OutgoingChatMessage$Player
- net.minecraft.network.chat.package-info
- net.minecraft.network.chat.PlayerChatMessage
+ net.minecraft.network.chat.RemoteChatSession
- net.minecraft.network.chat.RemoteChatSession$Data
+ net.minecraft.network.chat.SignableCommand
- net.minecraft.network.chat.SignableCommand$Argument
+ net.minecraft.network.chat.SignedMessageBody
- net.minecraft.network.chat.SignedMessageBody$Packed
+ net.minecraft.network.chat.SignedMessageChain
- net.minecraft.network.chat.SignedMessageChain$DecodeException
+ net.minecraft.network.chat.SignedMessageChain$Decoder
- net.minecraft.network.chat.SignedMessageChain$Encoder
+ net.minecraft.network.chat.SignedMessageLink
- net.minecraft.network.chat.SignedMessageValidator
+ net.minecraft.network.chat.SignedMessageValidator$KeyBased
- net.minecraft.network.chat.Style
+ net.minecraft.network.chat.Style$1
- net.minecraft.network.chat.Style$1Collector
+ net.minecraft.network.chat.Style$Serializer
- net.minecraft.network.chat.SubStringSource
+ net.minecraft.network.chat.TextColor
- net.minecraft.network.chat.ThrowingComponent
+ net.minecraft.network.FriendlyByteBuf$Reader
- net.minecraft.network.FriendlyByteBuf$Writer
+ net.minecraft.network.package-info
+ net.minecraft.network.PacketDecoder
- net.minecraft.network.PacketEncoder
+ net.minecraft.network.PacketListener
- net.minecraft.network.PacketSendListener
+ net.minecraft.network.PacketSendListener$1
- net.minecraft.network.PacketSendListener$2
- net.minecraft.network.protocol.game.ClientboundAddEntityPacket
+ net.minecraft.network.protocol.game.ClientboundAddExperienceOrbPacket
- net.minecraft.network.protocol.game.ClientboundAddPlayerPacket
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
- net.minecraft.network.protocol.game.ClientboundChangeDifficultyPacket
+ net.minecraft.network.protocol.game.ClientboundClearTitlesPacket
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket
- net.minecraft.network.protocol.game.ClientboundCommandsPacket$ArgumentNodeStub
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket$Entry
- net.minecraft.network.protocol.game.ClientboundCommandsPacket$LiteralNodeStub
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket$NodeResolver
- net.minecraft.network.protocol.game.ClientboundCommandsPacket$NodeStub
- net.minecraft.network.protocol.game.ClientboundCommandSuggestionsPacket
+ net.minecraft.network.protocol.game.ClientboundContainerClosePacket
- net.minecraft.network.protocol.game.ClientboundContainerSetContentPacket
+ net.minecraft.network.protocol.game.ClientboundContainerSetDataPacket
- net.minecraft.network.protocol.game.ClientboundContainerSetSlotPacket
+ net.minecraft.network.protocol.game.ClientboundCooldownPacket
- net.minecraft.network.protocol.game.ClientboundCustomChatCompletionsPacket
+ net.minecraft.network.protocol.game.ClientboundCustomChatCompletionsPacket$Action
- net.minecraft.network.protocol.game.ClientboundCustomPayloadPacket
+ net.minecraft.network.protocol.game.ClientGamePacketListener
- net.minecraft.network.protocol.Packet
+ net.minecraft.network.protocol.PacketFlow
- net.minecraft.network.protocol.PacketUtils
+ net.minecraft.network.RateKickingConnection
- net.minecraft.network.SkipPacketException
+ net.minecraft.network.TickablePacketListener
- net.minecraft.network.Varint21FrameDecoder
+ net.minecraft.network.Varint21LengthFieldPrepender
```

</details>


<details><summary>net.minecraft.client.GameNarrator</summary>

```diff
+ void say(Component)
+ void sayChat(Component)
- void sayChatNow(Supplier)
```

</details>


<details><summary>net.minecraft.client.gui.components.ImageButton</summary>

```diff
- void setPosition(int,int)
```

</details>


<details><summary>net.minecraft.client.gui.screens.InBedChatScreen</summary>

```diff
+ boolean charTyped(char,int)
+ void render(PoseStack,int,int,float)
```

</details>


<details><summary>net.minecraft.client.model.VexModel</summary>

```diff
+ void offsetStackPosition(PoseStack,boolean)
- void offsetSwordPivot(PoseStack)
- void offsetSwordPosition(PoseStack)
- void rotateSwordWithArm(PoseStack)
```

</details>


<details><summary>net.minecraft.client.multiplayer.ClientLevel</summary>

```diff
- void playCustomSound(Player,Vec3,ResourceLocation,SoundSource,float,float,double,long)
+ void playSeededSound(Player,double,double,double,Holder,SoundSource,float,float,long)
- void playSeededSound(Player,double,double,double,SoundEvent,SoundSource,float,float,long)
```

</details>


<details><summary>net.minecraft.client.multiplayer.ClientPacketListener</summary>

```diff
- void handleCustomSoundEvent(ClientboundCustomSoundPacket)
```

</details>


<details><summary>net.minecraft.client.multiplayer.chat.ChatListener</summary>

```diff
- Component lambda$narrateChatMessage$3(ChatType$Bound,Component)
```

</details>


<details><summary>net.minecraft.client.resources.sounds.BiomeAmbientSoundsHandler</summary>

```diff
+ BiomeAmbientSoundsHandler$LoopSoundInstance lambda$tick$0(Holder,Biome,BiomeAmbientSoundsHandler$LoopSoundInstance)
- BiomeAmbientSoundsHandler$LoopSoundInstance lambda$tick$0(SoundEvent,Biome,BiomeAmbientSoundsHandler$LoopSoundInstance)
+ void lambda$tick$1(Biome,Holder)
- void lambda$tick$1(Biome,SoundEvent)
```

</details>


<details><summary>net.minecraft.client.resources.sounds.SimpleSoundInstance</summary>

```diff
+ SimpleSoundInstance forUI(Holder,float)
```

</details>


<details><summary>net.minecraft.client.sounds.WeighedSoundEvents</summary>

```diff
- ResourceLocation getResourceLocation()
```

</details>


<details><summary>net.minecraft.client.telemetry.events.PerformanceMetricsEvent</summary>

```diff
+ void <init>()
- void <init>(TelemetryEventSender)
- void lambda$send$0(TelemetryPropertyMap$Builder)
+ void lambda$sendEvent$0(TelemetryPropertyMap$Builder)
- void send(TelemetryEventSender)
- void sendEvent()
+ void sendEvent(TelemetryEventSender)
- void tick()
+ void tick(TelemetryEventSender)
```

</details>


<details><summary>net.minecraft.client.telemetry.events.WorldUnloadEvent</summary>

```diff
- void loadedWorld()
+ void onPlayerInfoReceived()
```

</details>


<details><summary>net.minecraft.commands.CommandSourceStack</summary>

```diff
- Collection getAvailableSoundEvents()
+ Stream getAvailableSounds()
```

</details>


<details><summary>net.minecraft.commands.arguments.NbtPathArgument</summary>

```diff
- boolean lambda$createTagPredicate$1(CompoundTag,Tag)
+ boolean lambda$createTagPredicate$3(CompoundTag,Tag)
+ Message lambda$static$1(Object)
+ Message lambda$static$2(Object)
```

</details>


<details><summary>net.minecraft.core.Registry</summary>

```diff
+ Holder$Reference registerForHolder(Registry,ResourceKey,Object)
+ Holder$Reference registerForHolder(Registry,ResourceLocation,Object)
```

</details>


<details><summary>net.minecraft.nbt.DoubleTag</summary>

```diff
+ int sizeInBits()
```

</details>


<details><summary>net.minecraft.nbt.EndTag</summary>

```diff
+ int sizeInBits()
```

</details>


<details><summary>net.minecraft.nbt.FloatTag</summary>

```diff
+ int sizeInBits()
```

</details>


<details><summary>net.minecraft.nbt.IntArrayTag</summary>

```diff
+ int sizeInBits()
```

</details>


<details><summary>net.minecraft.nbt.IntTag</summary>

```diff
+ int sizeInBits()
```

</details>


<details><summary>net.minecraft.nbt.LongArrayTag</summary>

```diff
+ int sizeInBits()
```

</details>


<details><summary>net.minecraft.nbt.LongTag</summary>

```diff
+ int sizeInBits()
```

</details>


<details><summary>net.minecraft.nbt.StringTag</summary>

```diff
+ int sizeInBits()
```

</details>


<details><summary>net.minecraft.network.FriendlyByteBuf</summary>

```diff
+ Holder readById(IdMap,FriendlyByteBuf$Reader)
+ void writeId(IdMap,Holder,FriendlyByteBuf$Writer)
```

</details>


<details><summary>net.minecraft.network.syncher.SynchedEntityData</summary>

```diff
- void clearDirty()
```

</details>


<details><summary>net.minecraft.server.commands.ExecuteCommand</summary>

```diff
+ ArgumentBuilder lambda$addConditionals$54(CommandNode,boolean,DataCommands$DataProvider,ArgumentBuilder)
- ArgumentBuilder lambda$addConditionals$55(CommandNode,boolean,DataCommands$DataProvider,ArgumentBuilder)
+ boolean lambda$addConditionals$37(CommandContext)
- boolean lambda$addConditionals$40(CommandContext)
+ boolean lambda$addConditionals$40(Integer,Integer)
+ boolean lambda$addConditionals$41(CommandContext)
- boolean lambda$addConditionals$41(Integer,Integer)
- boolean lambda$addConditionals$42(CommandContext)
+ boolean lambda$addConditionals$42(Integer,Integer)
+ boolean lambda$addConditionals$43(CommandContext)
- boolean lambda$addConditionals$43(Integer,Integer)
- boolean lambda$addConditionals$44(CommandContext)
+ boolean lambda$addConditionals$44(Integer,Integer)
+ boolean lambda$addConditionals$45(CommandContext)
- boolean lambda$addConditionals$45(Integer,Integer)
- boolean lambda$addConditionals$46(CommandContext)
+ boolean lambda$addConditionals$46(Integer,Integer)
+ boolean lambda$addConditionals$47(CommandContext)
- boolean lambda$addConditionals$47(Integer,Integer)
- boolean lambda$addConditionals$49(CommandContext)
+ boolean lambda$addConditionals$51(CommandContext)
- boolean lambda$addConditionals$52(CommandContext)
+ Collection lambda$addConditional$57(boolean,ExecuteCommand$CommandPredicate,CommandContext)
- Collection lambda$addConditional$58(boolean,ExecuteCommand$CommandPredicate,CommandContext)
+ Collection lambda$addConditionals$49(boolean,CommandContext)
- Collection lambda$addConditionals$50(boolean,CommandContext)
+ Collection lambda$addConditionals$52(boolean,DataCommands$DataProvider,CommandContext)
- Collection lambda$addConditionals$53(boolean,DataCommands$DataProvider,CommandContext)
+ Collection lambda$addIfBlocksConditional$59(boolean,boolean,CommandContext)
- Collection lambda$addIfBlocksConditional$60(boolean,boolean,CommandContext)
+ int lambda$addConditional$58(boolean,ExecuteCommand$CommandPredicate,CommandContext)
- int lambda$addConditional$59(boolean,ExecuteCommand$CommandPredicate,CommandContext)
+ int lambda$addConditionals$50(CommandContext)
- int lambda$addConditionals$51(CommandContext)
+ int lambda$addConditionals$53(DataCommands$DataProvider,CommandContext)
- int lambda$addConditionals$54(DataCommands$DataProvider,CommandContext)
+ int lambda$addIfBlocksConditional$60(boolean,CommandContext)
- int lambda$addIfBlocksConditional$62(boolean,CommandContext)
+ int lambda$createNumericConditionalHandler$55(ExecuteCommand$CommandNumericPredicate,CommandContext)
- int lambda$createNumericConditionalHandler$57(ExecuteCommand$CommandNumericPredicate,CommandContext)
- Tag lambda$storeData$36(IntFunction,int)
+ void lambda$storeData$36(DataAccessor,boolean,NbtPathArgument$NbtPath,IntFunction,CommandContext,boolean,int)
- void lambda$storeData$37(DataAccessor,boolean,NbtPathArgument$NbtPath,IntFunction,CommandContext,boolean,int)
```

</details>


<details><summary>net.minecraft.sounds.Musics</summary>

```diff
+ Music createGameMusic(Holder)
- Music createGameMusic(SoundEvent)
```

</details>


<details><summary>net.minecraft.sounds.SoundEvents</summary>

```diff
+ Holder register(ResourceLocation,ResourceLocation,float)
+ Holder$Reference lambda$registerGoatHornSoundVariants$0(int)
+ Holder$Reference registerForHolder(ResourceLocation,ResourceLocation)
+ Holder$Reference registerForHolder(ResourceLocation)
+ Holder$Reference registerForHolder(String)
- SoundEvent lambda$registerGoatHornSoundVariants$0(int)
+ SoundEvent register(ResourceLocation,ResourceLocation)
+ SoundEvent register(ResourceLocation)
- SoundEvent register(String,float)
```

</details>


<details><summary>net.minecraft.world.level.biome.AmbientMoodSettings</summary>

```diff
+ Holder getSoundEvent()
+ Holder lambda$static$0(AmbientMoodSettings)
- SoundEvent getSoundEvent()
- SoundEvent lambda$static$0(AmbientMoodSettings)
+ void <init>(Holder,int,int,double)
- void <init>(SoundEvent,int,int,double)
```

</details>


### Server




<details><summary>Classes</summary>

```diff
- net.minecraft.network.chat.ChatDecorator
+ net.minecraft.network.chat.ChatType
- net.minecraft.network.chat.ChatType$Bound
+ net.minecraft.network.chat.ChatType$BoundNetwork
- net.minecraft.network.chat.ChatTypeDecoration
+ net.minecraft.network.chat.ChatTypeDecoration$Parameter
- net.minecraft.network.chat.ChatTypeDecoration$Parameter$Selector
+ net.minecraft.network.chat.ClickEvent
- net.minecraft.network.chat.ClickEvent$Action
+ net.minecraft.network.chat.CommonComponents
- net.minecraft.network.chat.Component
+ net.minecraft.network.chat.Component$Serializer
- net.minecraft.network.chat.ComponentContents
+ net.minecraft.network.chat.ComponentContents$1
- net.minecraft.network.chat.ComponentUtils
+ net.minecraft.network.chat.contents.BlockDataSource
- net.minecraft.network.chat.contents.DataSource
+ net.minecraft.network.chat.contents.EntityDataSource
- net.minecraft.network.chat.contents.KeybindContents
+ net.minecraft.network.chat.contents.KeybindResolver
- net.minecraft.network.chat.contents.LiteralContents
+ net.minecraft.network.chat.contents.NbtContents
+ net.minecraft.network.chat.contents.package-info
- net.minecraft.network.chat.contents.ScoreContents
+ net.minecraft.network.chat.contents.SelectorContents
- net.minecraft.network.chat.contents.StorageDataSource
+ net.minecraft.network.chat.contents.TranslatableContents
- net.minecraft.network.chat.contents.TranslatableFormatException
+ net.minecraft.network.chat.FilterMask
- net.minecraft.network.chat.FilterMask$1
+ net.minecraft.network.chat.FilterMask$Type
- net.minecraft.network.chat.FormattedText
+ net.minecraft.network.chat.FormattedText$1
- net.minecraft.network.chat.FormattedText$2
+ net.minecraft.network.chat.FormattedText$3
- net.minecraft.network.chat.FormattedText$4
+ net.minecraft.network.chat.FormattedText$ContentConsumer
- net.minecraft.network.chat.FormattedText$StyledContentConsumer
+ net.minecraft.network.chat.HoverEvent
- net.minecraft.network.chat.HoverEvent$Action
+ net.minecraft.network.chat.HoverEvent$EntityTooltipInfo
- net.minecraft.network.chat.HoverEvent$ItemStackInfo
+ net.minecraft.network.chat.LastSeenMessages
- net.minecraft.network.chat.LastSeenMessages$Packed
+ net.minecraft.network.chat.LastSeenMessages$Update
- net.minecraft.network.chat.LastSeenMessagesTracker
+ net.minecraft.network.chat.LastSeenMessagesTracker$Update
- net.minecraft.network.chat.LastSeenMessagesValidator
+ net.minecraft.network.chat.LastSeenTrackedEntry
- net.minecraft.network.chat.LocalChatSession
+ net.minecraft.network.chat.MessageSignature
- net.minecraft.network.chat.MessageSignature$Packed
+ net.minecraft.network.chat.MessageSignatureCache
- net.minecraft.network.chat.MutableComponent
+ net.minecraft.network.chat.OutgoingChatMessage
- net.minecraft.network.chat.OutgoingChatMessage$Disguised
+ net.minecraft.network.chat.OutgoingChatMessage$Player
- net.minecraft.network.chat.package-info
- net.minecraft.network.chat.PlayerChatMessage
+ net.minecraft.network.chat.RemoteChatSession
- net.minecraft.network.chat.RemoteChatSession$Data
+ net.minecraft.network.chat.SignableCommand
- net.minecraft.network.chat.SignableCommand$Argument
+ net.minecraft.network.chat.SignedMessageBody
- net.minecraft.network.chat.SignedMessageBody$Packed
+ net.minecraft.network.chat.SignedMessageChain
- net.minecraft.network.chat.SignedMessageChain$DecodeException
+ net.minecraft.network.chat.SignedMessageChain$Decoder
- net.minecraft.network.chat.SignedMessageChain$Encoder
+ net.minecraft.network.chat.SignedMessageLink
- net.minecraft.network.chat.SignedMessageValidator
+ net.minecraft.network.chat.SignedMessageValidator$KeyBased
- net.minecraft.network.chat.Style
+ net.minecraft.network.chat.Style$1
- net.minecraft.network.chat.Style$1Collector
+ net.minecraft.network.chat.Style$Serializer
- net.minecraft.network.chat.SubStringSource
+ net.minecraft.network.chat.TextColor
- net.minecraft.network.chat.ThrowingComponent
+ net.minecraft.network.FriendlyByteBuf$Reader
- net.minecraft.network.FriendlyByteBuf$Writer
+ net.minecraft.network.package-info
+ net.minecraft.network.PacketDecoder
- net.minecraft.network.PacketEncoder
+ net.minecraft.network.PacketListener
- net.minecraft.network.PacketSendListener
+ net.minecraft.network.PacketSendListener$1
- net.minecraft.network.PacketSendListener$2
- net.minecraft.network.protocol.game.ClientboundAddEntityPacket
+ net.minecraft.network.protocol.game.ClientboundAddExperienceOrbPacket
- net.minecraft.network.protocol.game.ClientboundAddPlayerPacket
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
- net.minecraft.network.protocol.game.ClientboundChangeDifficultyPacket
+ net.minecraft.network.protocol.game.ClientboundClearTitlesPacket
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket
- net.minecraft.network.protocol.game.ClientboundCommandsPacket$ArgumentNodeStub
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket$Entry
- net.minecraft.network.protocol.game.ClientboundCommandsPacket$LiteralNodeStub
+ net.minecraft.network.protocol.game.ClientboundCommandsPacket$NodeResolver
- net.minecraft.network.protocol.game.ClientboundCommandsPacket$NodeStub
- net.minecraft.network.protocol.game.ClientboundCommandSuggestionsPacket
+ net.minecraft.network.protocol.game.ClientboundContainerClosePacket
- net.minecraft.network.protocol.game.ClientboundContainerSetContentPacket
+ net.minecraft.network.protocol.game.ClientboundContainerSetDataPacket
- net.minecraft.network.protocol.game.ClientboundContainerSetSlotPacket
+ net.minecraft.network.protocol.game.ClientboundCooldownPacket
- net.minecraft.network.protocol.game.ClientboundCustomChatCompletionsPacket
+ net.minecraft.network.protocol.game.ClientboundCustomChatCompletionsPacket$Action
- net.minecraft.network.protocol.game.ClientboundCustomPayloadPacket
+ net.minecraft.network.protocol.game.ClientGamePacketListener
- net.minecraft.network.protocol.Packet
+ net.minecraft.network.protocol.PacketFlow
- net.minecraft.network.protocol.PacketUtils
+ net.minecraft.network.RateKickingConnection
- net.minecraft.network.SkipPacketException
+ net.minecraft.network.TickablePacketListener
- net.minecraft.network.Varint21FrameDecoder
+ net.minecraft.network.Varint21LengthFieldPrepender
```

</details>


<details><summary>net.minecraft.commands.CommandSourceStack</summary>

```diff
- Collection getAvailableSoundEvents()
+ Stream getAvailableSounds()
```

</details>


<details><summary>net.minecraft.commands.arguments.NbtPathArgument</summary>

```diff
- boolean lambda$createTagPredicate$1(CompoundTag,Tag)
+ boolean lambda$createTagPredicate$3(CompoundTag,Tag)
+ Message lambda$static$1(Object)
+ Message lambda$static$2(Object)
```

</details>


<details><summary>net.minecraft.core.Registry</summary>

```diff
+ Holder$Reference registerForHolder(Registry,ResourceKey,Object)
+ Holder$Reference registerForHolder(Registry,ResourceLocation,Object)
```

</details>


<details><summary>net.minecraft.nbt.DoubleTag</summary>

```diff
+ int sizeInBits()
```

</details>


<details><summary>net.minecraft.nbt.EndTag</summary>

```diff
+ int sizeInBits()
```

</details>


<details><summary>net.minecraft.nbt.FloatTag</summary>

```diff
+ int sizeInBits()
```

</details>


<details><summary>net.minecraft.nbt.IntArrayTag</summary>

```diff
+ int sizeInBits()
```

</details>


<details><summary>net.minecraft.nbt.IntTag</summary>

```diff
+ int sizeInBits()
```

</details>


<details><summary>net.minecraft.nbt.LongArrayTag</summary>

```diff
+ int sizeInBits()
```

</details>


<details><summary>net.minecraft.nbt.LongTag</summary>

```diff
+ int sizeInBits()
```

</details>


<details><summary>net.minecraft.nbt.StringTag</summary>

```diff
+ int sizeInBits()
```

</details>


<details><summary>net.minecraft.network.FriendlyByteBuf</summary>

```diff
+ Holder readById(IdMap,FriendlyByteBuf$Reader)
+ void writeId(IdMap,Holder,FriendlyByteBuf$Writer)
```

</details>


<details><summary>net.minecraft.network.syncher.SynchedEntityData</summary>

```diff
- void clearDirty()
```

</details>


<details><summary>net.minecraft.server.commands.data.DataCommands</summary>

```diff
+ ArgumentBuilder lambda$decorateModification$22(DataCommands$DataProvider,DataCommands$DataProvider,DataCommands$DataManipulator,ArgumentBuilder)
+ ArgumentBuilder lambda$decorateModification$23(DataCommands$DataProvider,DataCommands$DataProvider,DataCommands$DataManipulator)
- ArgumentBuilder lambda$decorateModification$24(DataCommands$DataProvider,DataCommands$DataProvider,DataCommands$DataManipulator,ArgumentBuilder)
+ ArgumentBuilder lambda$decorateModification$25(DataCommands$DataProvider,DataCommands$DataManipulator)
- ArgumentBuilder lambda$decorateModification$25(DataCommands$DataProvider,DataCommands$DataProvider,DataCommands$DataManipulator)
+ ArgumentBuilder lambda$decorateModification$26(BiConsumer,DataCommands$DataProvider,ArgumentBuilder)
- ArgumentBuilder lambda$decorateModification$27(DataCommands$DataProvider,DataCommands$DataManipulator)
- ArgumentBuilder lambda$decorateModification$28(BiConsumer,DataCommands$DataProvider,ArgumentBuilder)
+ ArgumentBuilder lambda$register$11(DataCommands$DataProvider,ArgumentBuilder)
- ArgumentBuilder lambda$register$15(DataCommands$DataProvider,ArgumentBuilder)
+ ArgumentBuilder lambda$register$7(DataCommands$DataProvider,ArgumentBuilder)
- ArgumentBuilder lambda$register$9(DataCommands$DataProvider,ArgumentBuilder)
+ boolean lambda$register$5(CommandSourceStack)
- boolean lambda$register$7(CommandSourceStack)
+ DataCommands$DataProvider lambda$static$3(Function)
+ DataCommands$DataProvider lambda$static$4(Function)
- DataCommands$DataProvider lambda$static$5(Function)
- DataCommands$DataProvider lambda$static$6(Function)
- int insertAtIndex(int,CompoundTag,NbtPathArgument$NbtPath,List)
+ int lambda$decorateModification$20(DataCommands$DataProvider,DataCommands$DataProvider,DataCommands$DataManipulator,CommandContext)
+ int lambda$decorateModification$21(DataCommands$DataProvider,DataCommands$DataProvider,DataCommands$DataManipulator,CommandContext)
- int lambda$decorateModification$22(DataCommands$DataProvider,DataCommands$DataProvider,DataCommands$DataManipulator,CommandContext)
- int lambda$decorateModification$23(DataCommands$DataProvider,DataCommands$DataProvider,DataCommands$DataManipulator,CommandContext)
+ int lambda$decorateModification$24(DataCommands$DataProvider,DataCommands$DataManipulator,CommandContext)
- int lambda$decorateModification$26(DataCommands$DataProvider,DataCommands$DataManipulator,CommandContext)
- int lambda$register$11(DataCommands$DataProvider,CommandContext)
+ int lambda$register$14(CommandContext,CompoundTag,NbtPathArgument$NbtPath,List)
- int lambda$register$14(DataCommands$DataProvider,CommandContext)
+ int lambda$register$15(CommandContext,CompoundTag,NbtPathArgument$NbtPath,List)
- int lambda$register$19(CommandContext,CompoundTag,NbtPathArgument$NbtPath,List)
- int lambda$register$20(CommandContext,CompoundTag,NbtPathArgument$NbtPath,List)
+ int lambda$register$6(DataCommands$DataProvider,CommandContext)
+ int lambda$register$9(DataCommands$DataProvider,CommandContext)
- Message lambda$static$3(Object)
- Message lambda$static$4(Object)
+ void lambda$register$19(ArgumentBuilder,DataCommands$DataManipulatorDecorator)
- void lambda$register$21(ArgumentBuilder,DataCommands$DataManipulatorDecorator)
```

</details>


<details><summary>net.minecraft.server.level.ServerLevel</summary>

```diff
- void playCustomSound(Player,Vec3,ResourceLocation,SoundSource,float,float,double,long)
+ void playSeededSound(Player,double,double,double,Holder,SoundSource,float,float,long)
- void playSeededSound(Player,double,double,double,SoundEvent,SoundSource,float,float,long)
```

</details>


<details><summary>net.minecraft.sounds.Music</summary>

```diff
+ Holder getEvent()
+ Holder lambda$static$0(Music)
- SoundEvent getEvent()
- SoundEvent lambda$static$0(Music)
+ void <init>(Holder,int,int,boolean)
- void <init>(SoundEvent,int,int,boolean)
```

</details>


<details><summary>net.minecraft.sounds.SoundEvent</summary>

```diff
+ App lambda$static$0(RecordCodecBuilder$Instance)
- float legacySoundRange(float)
+ Optional fixedRange()
+ SoundEvent create(ResourceLocation,Optional)
+ SoundEvent lambda$create$1(ResourceLocation,Float)
+ SoundEvent lambda$create$2(ResourceLocation)
+ SoundEvent readFromNetwork(FriendlyByteBuf)
+ void <clinit>()
+ void writeToNetwork(FriendlyByteBuf)
```

</details>


<details><summary>net.minecraft.world.entity.player.Player</summary>

```diff
+ void doCloseContainer()
```

</details>


<details><summary>net.minecraft.world.item.Instrument</summary>

```diff
+ Holder soundEvent()
- SoundEvent soundEvent()
+ void <init>(Holder,int,float)
- void <init>(SoundEvent,int,float)
```

</details>


<details><summary>net.minecraft.world.level.Level</summary>

```diff
- void playCustomSound(Player,Vec3,ResourceLocation,SoundSource,float,float,double)
+ void playSeededSound(Player,double,double,double,SoundEvent,SoundSource,float,float,long)
```

</details>


<details><summary>net.minecraft.world.level.biome.AmbientAdditionsSettings</summary>

```diff
+ Holder getSoundEvent()
+ Holder lambda$static$0(AmbientAdditionsSettings)
- SoundEvent getSoundEvent()
- SoundEvent lambda$static$0(AmbientAdditionsSettings)
+ void <init>(Holder,double)
- void <init>(SoundEvent,double)
```

</details>


<details><summary>net.minecraft.world.level.biome.BiomeSpecialEffects$Builder</summary>

```diff
+ BiomeSpecialEffects$Builder ambientLoopSound(Holder)
- BiomeSpecialEffects$Builder ambientLoopSound(SoundEvent)
```

</details>


<details><summary>net.minecraft.world.level.block.state.StateHolder</summary>

```diff
+ Object trySetValue(Property,Comparable)
```

</details>


<details><summary>net.minecraft.world.level.block.state.properties.NoteBlockInstrument</summary>

```diff
+ Holder getSoundEvent()
- SoundEvent getSoundEvent()
+ void <init>(String,int,String,Holder,NoteBlockInstrument$Type)
- void <init>(String,int,String,SoundEvent,NoteBlockInstrument$Type)
```

</details>


# Registries

<details><summary>sound_event.txt</summary>

```diff
+ minecraft:block.note_block.imitate.creeper
+ minecraft:block.note_block.imitate.ender_dragon
+ minecraft:block.note_block.imitate.piglin
+ minecraft:block.note_block.imitate.skeleton
+ minecraft:block.note_block.imitate.wither_skeleton
+ minecraft:block.note_block.imitate.zombie
```

</details>


# Translations

<details><summary>Keys</summary>

```diff
+ arguments.nbtpath.too_deep
+ arguments.nbtpath.too_large
```

</details>


# Version data

<details><summary>libraries.txt</summary>

```diff
- com.mojang:authlib:3.15.28
+ com.mojang:authlib:3.16.29
```

</details>
