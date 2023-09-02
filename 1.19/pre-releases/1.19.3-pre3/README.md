<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 1.19.3-pre3 ⌋<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>1.19.3-pre3</td></tr>
<tr><th>Type</th><td>pre-releases</td></tr>
<tr><th>Release time</th><td>2022-11-29T14:28:08+00:00</td></tr>
<tr><th>SHA1</th><td>eca79c580ea848ba4294a4d29ffc3bf37a4c16c6</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/eca79c580ea848ba4294a4d29ffc3bf37a4c16c6/1.19.3-pre3.json">https://piston-meta.mojang.com/v1/packages/eca79c580ea848ba4294a4d29ffc3bf37a4c16c6/1.19.3-pre3.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/a6c6685c661934ba5227cd8bcb484347119aea75/2.json">https://piston-meta.mojang.com/v1/packages/a6c6685c661934ba5227cd8bcb484347119aea75/2.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/323175facb90c05b07dff84b4cff39fd9cab138a/server.jar">https://piston-data.mojang.com/v1/objects/323175facb90c05b07dff84b4cff39fd9cab138a/server.jar</a></td></tr>
<tr><th>Server mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/7987f7f32fc1eb9b3da101feb04bd2dd533c2279/server.txt">https://piston-data.mojang.com/v1/objects/7987f7f32fc1eb9b3da101feb04bd2dd533c2279/server.txt</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/2e935c01cccf2b1d1a7845ec596555685baa49ef/client.jar">https://piston-data.mojang.com/v1/objects/2e935c01cccf2b1d1a7845ec596555685baa49ef/client.jar</a></td></tr>
<tr><th>Client mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/be5166aabd346178403bd95bc6c83aa1cab07915/client.txt">https://piston-data.mojang.com/v1/objects/be5166aabd346178403bd95bc6c83aa1cab07915/client.txt</a></td></tr>
</table></html>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/1.19.3-pre2">1.19.3-pre2</a>
## Registries

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

## Misc

<details><summary>dimensions.txt</summary>

```diff
- C:\Users\pixig\Minecraft-generated-data\1.19\pre-releases\1.19.3-pre2\.data\server\data\minecraft\worldgen\world_preset\amplified.json
- C:\Users\pixig\Minecraft-generated-data\1.19\pre-releases\1.19.3-pre2\.data\server\data\minecraft\worldgen\world_preset\debug_all_block_states.json
- C:\Users\pixig\Minecraft-generated-data\1.19\pre-releases\1.19.3-pre2\.data\server\data\minecraft\worldgen\world_preset\flat.json
- C:\Users\pixig\Minecraft-generated-data\1.19\pre-releases\1.19.3-pre2\.data\server\data\minecraft\worldgen\world_preset\large_biomes.json
- C:\Users\pixig\Minecraft-generated-data\1.19\pre-releases\1.19.3-pre2\.data\server\data\minecraft\worldgen\world_preset\normal.json
- C:\Users\pixig\Minecraft-generated-data\1.19\pre-releases\1.19.3-pre2\.data\server\data\minecraft\worldgen\world_preset\single_biome_surface.json
+ C:\Users\pixig\Minecraft-generated-data\1.19\pre-releases\1.19.3-pre3\.data\server\data\minecraft\worldgen\world_preset\amplified.json
+ C:\Users\pixig\Minecraft-generated-data\1.19\pre-releases\1.19.3-pre3\.data\server\data\minecraft\worldgen\world_preset\debug_all_block_states.json
+ C:\Users\pixig\Minecraft-generated-data\1.19\pre-releases\1.19.3-pre3\.data\server\data\minecraft\worldgen\world_preset\flat.json
+ C:\Users\pixig\Minecraft-generated-data\1.19\pre-releases\1.19.3-pre3\.data\server\data\minecraft\worldgen\world_preset\large_biomes.json
+ C:\Users\pixig\Minecraft-generated-data\1.19\pre-releases\1.19.3-pre3\.data\server\data\minecraft\worldgen\world_preset\normal.json
+ C:\Users\pixig\Minecraft-generated-data\1.19\pre-releases\1.19.3-pre3\.data\server\data\minecraft\worldgen\world_preset\single_biome_surface.json
```

</details>

## Version data

<details><summary>libraries.txt</summary>

```diff
- com.mojang:authlib:3.15.28
+ com.mojang:authlib:3.16.29
```

</details>

## Mappings









































































































































































































































































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
+ Button leaveBedButton
+ boolean charTyped(char,int)
+ void render(PoseStack,int,int,float)
```

</details>






















































































































































































<details><summary>net.minecraft.client.model.VexModel</summary>

```diff
+ ModelPart head
+ void offsetStackPosition(PoseStack,boolean)
- void offsetSwordPivot(PoseStack)
- void offsetSwordPosition(PoseStack)
- void rotateSwordWithArm(PoseStack)
```

</details>




















<details><summary>net.minecraft.client.multiplayer.ClientLevel</summary>

```diff
+ void playSeededSound(SoundSource,float,float,long)
- void playCustomSound(SoundSource,float,float,double,long)
- void playSeededSound(SoundSource,float,float,long)
```

</details>


<details><summary>net.minecraft.client.multiplayer.ClientPacketListener</summary>

```diff
- void handleCustomSoundEvent(ClientboundCustomSoundPacket)
```

</details>








<details><summary>net.minecraft.client.multiplayer.chat.ChatListener</summary>

```diff
- Component lambda$narrateChatMessage$3(Component)
```

</details>
























































































































































































































































































































































































<details><summary>net.minecraft.client.resources.sounds.BiomeAmbientSoundsHandler</summary>

```diff
+ BiomeAmbientSoundsHandler$LoopSoundInstance lambda$tick$0(BiomeAmbientSoundsHandler$LoopSoundInstance)
+ void lambda$tick$1(Holder)
- BiomeAmbientSoundsHandler$LoopSoundInstance lambda$tick$0(BiomeAmbientSoundsHandler$LoopSoundInstance)
- void lambda$tick$1(SoundEvent)
```

</details>




<details><summary>net.minecraft.client.resources.sounds.SimpleSoundInstance</summary>

```diff
+ SimpleSoundInstance forUI(Holder,float)
```

</details>



























<details><summary>net.minecraft.client.sounds.WeighedSoundEvents</summary>

```diff
- RandomSource random
- ResourceLocation location
- ResourceLocation getResourceLocation()
```

</details>










<details><summary>net.minecraft.client.telemetry.events.PerformanceMetricsEvent</summary>

```diff
- TelemetryEventSender eventSender
+ void <init>()
+ void lambda$sendEvent$0(TelemetryPropertyMap$Builder)
+ void sendEvent(TelemetryEventSender)
+ void tick(TelemetryEventSender)
- void <init>(TelemetryEventSender)
- void lambda$send$0(TelemetryPropertyMap$Builder)
- void send(TelemetryEventSender)
- void sendEvent()
- void tick()
```

</details>

<details><summary>net.minecraft.client.telemetry.events.WorldUnloadEvent</summary>

```diff
+ int NOT_TRACKING_TIME
+ void onPlayerInfoReceived()
- void loadedWorld()
```

</details>

















<details><summary>net.minecraft.commands.CommandSourceStack</summary>

```diff
+ Stream getAvailableSounds()
- Collection getAvailableSoundEvents()
```

</details>



<details><summary>net.minecraft.commands.SharedSuggestionProvider</summary>

```diff
+ Stream getAvailableSounds()
- Collection getAvailableSoundEvents()
```

</details>












<details><summary>net.minecraft.commands.arguments.NbtPathArgument</summary>

```diff
+ DynamicCommandExceptionType ERROR_EXPECTED_LIST
+ DynamicCommandExceptionType ERROR_INVALID_INDEX
+ SimpleCommandExceptionType ERROR_DATA_TOO_DEEP
+ SimpleCommandExceptionType ERROR_DATA_TOO_LARGE
+ boolean lambda$createTagPredicate$3(Tag)
+ Message lambda$static$1(Object)
+ Message lambda$static$2(Object)
- boolean lambda$createTagPredicate$1(Tag)
```

</details>























































































<details><summary>net.minecraft.core.Registry</summary>

```diff
+ Holder wrapAsHolder(java.lang.Object)
+ Holder$Reference registerForHolder(Object)
+ Holder$Reference registerForHolder(Object)
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
+ Holder readById(FriendlyByteBuf$Reader)
+ void writeId(FriendlyByteBuf$Writer)
```

</details>










































































































<details><summary>net.minecraft.network.syncher.SynchedEntityData</summary>

```diff
- void clearDirty()
```

</details>

























































<details><summary>net.minecraft.server.commands.ExecuteCommand</summary>

```diff
+ ArgumentBuilder lambda$addConditionals$54(ArgumentBuilder)
+ boolean lambda$addConditionals$37(CommandContext)
+ boolean lambda$addConditionals$40(Integer)
+ boolean lambda$addConditionals$41(CommandContext)
+ boolean lambda$addConditionals$42(Integer)
+ boolean lambda$addConditionals$43(CommandContext)
+ boolean lambda$addConditionals$44(Integer)
+ boolean lambda$addConditionals$45(CommandContext)
+ boolean lambda$addConditionals$46(Integer)
+ boolean lambda$addConditionals$47(CommandContext)
+ boolean lambda$addConditionals$51(CommandContext)
+ Collection lambda$addConditional$57(CommandContext)
+ Collection lambda$addConditionals$49(CommandContext)
+ Collection lambda$addConditionals$52(CommandContext)
+ Collection lambda$addIfBlocksConditional$59(CommandContext)
+ int lambda$addConditional$58(CommandContext)
+ int lambda$addConditionals$50(CommandContext)
+ int lambda$addConditionals$53(CommandContext)
+ int lambda$addIfBlocksConditional$60(CommandContext)
+ int lambda$createNumericConditionalHandler$55(CommandContext)
+ void lambda$storeData$36(CommandContext,boolean,int)
- ArgumentBuilder lambda$addConditionals$55(ArgumentBuilder)
- boolean lambda$addConditionals$40(CommandContext)
- boolean lambda$addConditionals$41(Integer)
- boolean lambda$addConditionals$42(CommandContext)
- boolean lambda$addConditionals$43(Integer)
- boolean lambda$addConditionals$44(CommandContext)
- boolean lambda$addConditionals$45(Integer)
- boolean lambda$addConditionals$46(CommandContext)
- boolean lambda$addConditionals$47(Integer)
- boolean lambda$addConditionals$49(CommandContext)
- boolean lambda$addConditionals$52(CommandContext)
- Collection lambda$addConditional$58(CommandContext)
- Collection lambda$addConditionals$50(CommandContext)
- Collection lambda$addConditionals$53(CommandContext)
- Collection lambda$addIfBlocksConditional$60(CommandContext)
- int lambda$addConditional$59(CommandContext)
- int lambda$addConditionals$51(CommandContext)
- int lambda$addConditionals$54(CommandContext)
- int lambda$addIfBlocksConditional$62(CommandContext)
- int lambda$createNumericConditionalHandler$57(CommandContext)
- Tag lambda$storeData$36(IntFunction,int)
- void lambda$storeData$37(CommandContext,boolean,int)
```

</details>


































































<details><summary>net.minecraft.server.level.ServerEntity</summary>

```diff
+ List trackedDataValues
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
+ Holder$Reference AMBIENT_BASALT_DELTAS_ADDITIONS
+ Holder$Reference AMBIENT_BASALT_DELTAS_LOOP
+ Holder$Reference AMBIENT_BASALT_DELTAS_MOOD
+ Holder$Reference AMBIENT_CAVE
+ Holder$Reference AMBIENT_CRIMSON_FOREST_ADDITIONS
+ Holder$Reference AMBIENT_CRIMSON_FOREST_LOOP
+ Holder$Reference AMBIENT_CRIMSON_FOREST_MOOD
+ Holder$Reference AMBIENT_NETHER_WASTES_ADDITIONS
+ Holder$Reference AMBIENT_NETHER_WASTES_LOOP
+ Holder$Reference AMBIENT_NETHER_WASTES_MOOD
+ Holder$Reference AMBIENT_SOUL_SAND_VALLEY_ADDITIONS
+ Holder$Reference AMBIENT_SOUL_SAND_VALLEY_LOOP
+ Holder$Reference AMBIENT_SOUL_SAND_VALLEY_MOOD
+ Holder$Reference AMBIENT_WARPED_FOREST_ADDITIONS
+ Holder$Reference AMBIENT_WARPED_FOREST_LOOP
+ Holder$Reference AMBIENT_WARPED_FOREST_MOOD
+ Holder$Reference MUSIC_BIOME_BASALT_DELTAS
+ Holder$Reference MUSIC_BIOME_CRIMSON_FOREST
+ Holder$Reference MUSIC_BIOME_DEEP_DARK
+ Holder$Reference MUSIC_BIOME_DRIPSTONE_CAVES
+ Holder$Reference MUSIC_BIOME_FROZEN_PEAKS
+ Holder$Reference MUSIC_BIOME_GROVE
+ Holder$Reference MUSIC_BIOME_JAGGED_PEAKS
+ Holder$Reference MUSIC_BIOME_JUNGLE_AND_FOREST
+ Holder$Reference MUSIC_BIOME_LUSH_CAVES
+ Holder$Reference MUSIC_BIOME_MEADOW
+ Holder$Reference MUSIC_BIOME_NETHER_WASTES
+ Holder$Reference MUSIC_BIOME_OLD_GROWTH_TAIGA
+ Holder$Reference MUSIC_BIOME_SNOWY_SLOPES
+ Holder$Reference MUSIC_BIOME_SOUL_SAND_VALLEY
+ Holder$Reference MUSIC_BIOME_STONY_PEAKS
+ Holder$Reference MUSIC_BIOME_SWAMP
+ Holder$Reference MUSIC_BIOME_WARPED_FOREST
+ Holder$Reference MUSIC_CREATIVE
+ Holder$Reference MUSIC_CREDITS
+ Holder$Reference MUSIC_DRAGON
+ Holder$Reference MUSIC_END
+ Holder$Reference MUSIC_GAME
+ Holder$Reference MUSIC_MENU
+ Holder$Reference MUSIC_UNDER_WATER
+ Holder$Reference NOTE_BLOCK_BANJO
+ Holder$Reference NOTE_BLOCK_BASEDRUM
+ Holder$Reference NOTE_BLOCK_BASS
+ Holder$Reference NOTE_BLOCK_BELL
+ Holder$Reference NOTE_BLOCK_BIT
+ Holder$Reference NOTE_BLOCK_CHIME
+ Holder$Reference NOTE_BLOCK_COW_BELL
+ Holder$Reference NOTE_BLOCK_DIDGERIDOO
+ Holder$Reference NOTE_BLOCK_FLUTE
+ Holder$Reference NOTE_BLOCK_GUITAR
+ Holder$Reference NOTE_BLOCK_HARP
+ Holder$Reference NOTE_BLOCK_HAT
+ Holder$Reference NOTE_BLOCK_IMITATE_CREEPER
+ Holder$Reference NOTE_BLOCK_IMITATE_ENDER_DRAGON
+ Holder$Reference NOTE_BLOCK_IMITATE_PIGLIN
+ Holder$Reference NOTE_BLOCK_IMITATE_SKELETON
+ Holder$Reference NOTE_BLOCK_IMITATE_WITHER_SKELETON
+ Holder$Reference NOTE_BLOCK_IMITATE_ZOMBIE
+ Holder$Reference NOTE_BLOCK_IRON_XYLOPHONE
+ Holder$Reference NOTE_BLOCK_PLING
+ Holder$Reference NOTE_BLOCK_SNARE
+ Holder$Reference NOTE_BLOCK_XYLOPHONE
+ Holder$Reference RAID_HORN
+ Holder$Reference RESPAWN_ANCHOR_DEPLETE
+ Holder$Reference UI_BUTTON_CLICK
- SoundEvent AMBIENT_BASALT_DELTAS_ADDITIONS
- SoundEvent AMBIENT_BASALT_DELTAS_LOOP
- SoundEvent AMBIENT_BASALT_DELTAS_MOOD
- SoundEvent AMBIENT_CAVE
- SoundEvent AMBIENT_CRIMSON_FOREST_ADDITIONS
- SoundEvent AMBIENT_CRIMSON_FOREST_LOOP
- SoundEvent AMBIENT_CRIMSON_FOREST_MOOD
- SoundEvent AMBIENT_NETHER_WASTES_ADDITIONS
- SoundEvent AMBIENT_NETHER_WASTES_LOOP
- SoundEvent AMBIENT_NETHER_WASTES_MOOD
- SoundEvent AMBIENT_SOUL_SAND_VALLEY_ADDITIONS
- SoundEvent AMBIENT_SOUL_SAND_VALLEY_LOOP
- SoundEvent AMBIENT_SOUL_SAND_VALLEY_MOOD
- SoundEvent AMBIENT_WARPED_FOREST_ADDITIONS
- SoundEvent AMBIENT_WARPED_FOREST_LOOP
- SoundEvent AMBIENT_WARPED_FOREST_MOOD
- SoundEvent MUSIC_BIOME_BASALT_DELTAS
- SoundEvent MUSIC_BIOME_CRIMSON_FOREST
- SoundEvent MUSIC_BIOME_DEEP_DARK
- SoundEvent MUSIC_BIOME_DRIPSTONE_CAVES
- SoundEvent MUSIC_BIOME_FROZEN_PEAKS
- SoundEvent MUSIC_BIOME_GROVE
- SoundEvent MUSIC_BIOME_JAGGED_PEAKS
- SoundEvent MUSIC_BIOME_JUNGLE_AND_FOREST
- SoundEvent MUSIC_BIOME_LUSH_CAVES
- SoundEvent MUSIC_BIOME_MEADOW
- SoundEvent MUSIC_BIOME_NETHER_WASTES
- SoundEvent MUSIC_BIOME_OLD_GROWTH_TAIGA
- SoundEvent MUSIC_BIOME_SNOWY_SLOPES
- SoundEvent MUSIC_BIOME_SOUL_SAND_VALLEY
- SoundEvent MUSIC_BIOME_STONY_PEAKS
- SoundEvent MUSIC_BIOME_SWAMP
- SoundEvent MUSIC_BIOME_WARPED_FOREST
- SoundEvent MUSIC_CREATIVE
- SoundEvent MUSIC_CREDITS
- SoundEvent MUSIC_DRAGON
- SoundEvent MUSIC_END
- SoundEvent MUSIC_GAME
- SoundEvent MUSIC_MENU
- SoundEvent MUSIC_UNDER_WATER
- SoundEvent NOTE_BLOCK_BANJO
- SoundEvent NOTE_BLOCK_BASEDRUM
- SoundEvent NOTE_BLOCK_BASS
- SoundEvent NOTE_BLOCK_BELL
- SoundEvent NOTE_BLOCK_BIT
- SoundEvent NOTE_BLOCK_CHIME
- SoundEvent NOTE_BLOCK_COW_BELL
- SoundEvent NOTE_BLOCK_DIDGERIDOO
- SoundEvent NOTE_BLOCK_FLUTE
- SoundEvent NOTE_BLOCK_GUITAR
- SoundEvent NOTE_BLOCK_HARP
- SoundEvent NOTE_BLOCK_HAT
- SoundEvent NOTE_BLOCK_IRON_XYLOPHONE
- SoundEvent NOTE_BLOCK_PLING
- SoundEvent NOTE_BLOCK_SNARE
- SoundEvent NOTE_BLOCK_XYLOPHONE
- SoundEvent RAID_HORN
- SoundEvent RESPAWN_ANCHOR_DEPLETE
- SoundEvent UI_BUTTON_CLICK
+ Holder register(ResourceLocation,float)
+ Holder$Reference lambda$registerGoatHornSoundVariants$0(int)
+ Holder$Reference registerForHolder(ResourceLocation)
+ Holder$Reference registerForHolder(ResourceLocation)
+ Holder$Reference registerForHolder(String)
+ SoundEvent register(ResourceLocation)
+ SoundEvent register(ResourceLocation)
- SoundEvent lambda$registerGoatHornSoundVariants$0(int)
- SoundEvent register(String,float)
```

</details>






































































































































































































































































































































































































































































































































































































































































































































































































































































































































































<details><summary>net.minecraft.world.level.biome.AmbientMoodSettings</summary>

```diff
+ Holder soundEvent
- SoundEvent soundEvent
+ Holder getSoundEvent()
+ Holder lambda$static$0(AmbientMoodSettings)
+ void <init>(Holder,int,int,double)
- SoundEvent getSoundEvent()
- SoundEvent lambda$static$0(AmbientMoodSettings)
- void <init>(SoundEvent,int,int,double)
```

</details>

























































































































































































































































































































































































































































































































































































































































































































































































































































































































<details><summary>Added and removed classes</summary>

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

















































































































<details><summary>net.minecraft.commands.CommandSourceStack</summary>

```diff
+ Stream getAvailableSounds()
- Collection getAvailableSoundEvents()
```

</details>



<details><summary>net.minecraft.commands.SharedSuggestionProvider</summary>

```diff
+ Stream getAvailableSounds()
- Collection getAvailableSoundEvents()
```

</details>












<details><summary>net.minecraft.commands.arguments.NbtPathArgument</summary>

```diff
+ DynamicCommandExceptionType ERROR_EXPECTED_LIST
+ DynamicCommandExceptionType ERROR_INVALID_INDEX
+ SimpleCommandExceptionType ERROR_DATA_TOO_DEEP
+ SimpleCommandExceptionType ERROR_DATA_TOO_LARGE
+ boolean lambda$createTagPredicate$3(Tag)
+ Message lambda$static$1(Object)
+ Message lambda$static$2(Object)
- boolean lambda$createTagPredicate$1(Tag)
```

</details>























































































<details><summary>net.minecraft.core.Registry</summary>

```diff
+ Holder wrapAsHolder(java.lang.Object)
+ Holder$Reference registerForHolder(Object)
+ Holder$Reference registerForHolder(Object)
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
+ Holder readById(FriendlyByteBuf$Reader)
+ void writeId(FriendlyByteBuf$Writer)
```

</details>










































































































<details><summary>net.minecraft.network.syncher.SynchedEntityData</summary>

```diff
- void clearDirty()
```

</details>

























































































<details><summary>net.minecraft.server.commands.data.DataCommands</summary>

```diff
- DynamicCommandExceptionType ERROR_EXPECTED_LIST
- DynamicCommandExceptionType ERROR_INVALID_INDEX
+ ArgumentBuilder lambda$decorateModification$22(ArgumentBuilder)
+ ArgumentBuilder lambda$decorateModification$23(DataCommands$DataManipulator)
+ ArgumentBuilder lambda$decorateModification$25(DataCommands$DataManipulator)
+ ArgumentBuilder lambda$decorateModification$26(ArgumentBuilder)
+ ArgumentBuilder lambda$register$11(ArgumentBuilder)
+ ArgumentBuilder lambda$register$7(ArgumentBuilder)
+ boolean lambda$register$5(CommandSourceStack)
+ DataCommands$DataProvider lambda$static$3(Function)
+ DataCommands$DataProvider lambda$static$4(Function)
+ int lambda$decorateModification$20(CommandContext)
+ int lambda$decorateModification$21(CommandContext)
+ int lambda$decorateModification$24(CommandContext)
+ int lambda$register$14(List)
+ int lambda$register$15(List)
+ int lambda$register$6(CommandContext)
+ int lambda$register$9(CommandContext)
+ void lambda$register$19(DataCommands$DataManipulatorDecorator)
- ArgumentBuilder lambda$decorateModification$24(ArgumentBuilder)
- ArgumentBuilder lambda$decorateModification$25(DataCommands$DataManipulator)
- ArgumentBuilder lambda$decorateModification$27(DataCommands$DataManipulator)
- ArgumentBuilder lambda$decorateModification$28(ArgumentBuilder)
- ArgumentBuilder lambda$register$15(ArgumentBuilder)
- ArgumentBuilder lambda$register$9(ArgumentBuilder)
- boolean lambda$register$7(CommandSourceStack)
- DataCommands$DataProvider lambda$static$5(Function)
- DataCommands$DataProvider lambda$static$6(Function)
- int insertAtIndex(List)
- int lambda$decorateModification$22(CommandContext)
- int lambda$decorateModification$23(CommandContext)
- int lambda$decorateModification$26(CommandContext)
- int lambda$register$11(CommandContext)
- int lambda$register$14(CommandContext)
- int lambda$register$19(List)
- int lambda$register$20(List)
- Message lambda$static$3(Object)
- Message lambda$static$4(Object)
- void lambda$register$21(DataCommands$DataManipulatorDecorator)
```

</details>






























<details><summary>net.minecraft.server.level.ServerLevel</summary>

```diff
+ void playSeededSound(SoundSource,float,float,long)
- void playCustomSound(SoundSource,float,float,double,long)
- void playSeededSound(SoundSource,float,float,long)
```

</details>

















































































<details><summary>net.minecraft.sounds.Music</summary>

```diff
+ Holder event
- SoundEvent event
+ Holder getEvent()
+ Holder lambda$static$0(Music)
+ void <init>(Holder,int,int,boolean)
- SoundEvent getEvent()
- SoundEvent lambda$static$0(Music)
- void <init>(SoundEvent,int,int,boolean)
```

</details>

<details><summary>net.minecraft.sounds.SoundEvent</summary>

```diff
+ Codec CODEC
+ Codec DIRECT_CODEC
+ App lambda$static$0(RecordCodecBuilder$Instance)
+ Optional fixedRange()
+ SoundEvent create(Optional)
+ SoundEvent lambda$create$1(Float)
+ SoundEvent lambda$create$2(ResourceLocation)
+ SoundEvent readFromNetwork(FriendlyByteBuf)
+ void <clinit>()
+ void writeToNetwork(FriendlyByteBuf)
- float legacySoundRange(float)
```

</details>








































































































































































































































































































































































































































































































































































































































































































<details><summary>net.minecraft.world.entity.player.Player</summary>

```diff
+ void doCloseContainer()
```

</details>

































































































































<details><summary>net.minecraft.world.item.Instrument</summary>

```diff
+ Holder soundEvent
- SoundEvent soundEvent
+ Holder soundEvent()
+ void <init>(Holder,int,float)
- SoundEvent soundEvent()
- void <init>(SoundEvent,int,float)
```

</details>













































































































<details><summary>net.minecraft.world.level.Level</summary>

```diff
+ void playSeededSound(net.minecraft.world.entity.player.Player,double,double,double,net.minecraft.core.Holder,net.minecraft.sounds.SoundSource,float,float,long)
- void playCustomSound(net.minecraft.world.entity.player.Player,net.minecraft.world.phys.Vec3,net.minecraft.resources.ResourceLocation,net.minecraft.sounds.SoundSource,float,float,double,long)
- void playSeededSound(net.minecraft.world.entity.player.Player,double,double,double,net.minecraft.sounds.SoundEvent,net.minecraft.sounds.SoundSource,float,float,long)
+ void playSeededSound(SoundSource,float,float,long)
- void playCustomSound(SoundSource,float,float,double)
```

</details>
















<details><summary>net.minecraft.world.level.biome.AmbientAdditionsSettings</summary>

```diff
+ Holder soundEvent
- SoundEvent soundEvent
+ Holder getSoundEvent()
+ Holder lambda$static$0(AmbientAdditionsSettings)
+ void <init>(Holder,double)
- SoundEvent getSoundEvent()
- SoundEvent lambda$static$0(AmbientAdditionsSettings)
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
+ Object trySetValue(Comparable)
```

</details>















<details><summary>net.minecraft.world.level.block.state.properties.NoteBlockInstrument</summary>

```diff
+ Holder soundEvent
- SoundEvent soundEvent
+ Holder getSoundEvent()
+ void <init>(NoteBlockInstrument$Type)
- SoundEvent getSoundEvent()
- void <init>(NoteBlockInstrument$Type)
```

</details>









































































































































































































































































































































































































































































































































































































































<details><summary>Added and removed classes</summary>

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

<br/>
<html><table>
<tr><td colspan="2" align="center"><img width="5000" height="0"><br/>
<a href="https://github.com/PixiGeko/Minecraft-generated-data">Minecraft-generated-data</a>
<br/><img width="0" height="0"></td></tr>
<tr><td colspan="2" align="center"><img width="5000" height="0"><br/>
:warning: This repository is not official, approved, endorsed, associated or connected with Mojang :warning:
<br/><img width="0" height="0"></td></tr>
</table></html>
<br/>