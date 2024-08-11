## Comparison with [1.16.3](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.16.3)

- [Version data](#version-data)
- [Translations](#translations)
- [File structure](#file-structure)
- [Mappings](#mappings)
  - [Server](#server)
  - [Client](#client)

<hr/>
<details><summary>Version data</summary>
<table><tr><th></th><th align="left">1.16.3</th><th>1.16.4-pre1</th></tr><tr><td>World version</td><td><code>2580</code></td><td><code>2581</code></td></tr><tr><td>Protocol version</td><td><code>753</code></td><td><code>1073741825</code></td></tr></table>
</details>
<details><summary>Translations</summary>
<details>
<summary>
Keys
</summary>

```diff
+ gui.socialInteractions.empty_hidden: No players hidden in chat
+ gui.socialInteractions.hidden_in_chat: Chat messages from %s will be hidden
+ gui.socialInteractions.hide: %s, Hide in Chat
+ gui.socialInteractions.search_hint: Search...
+ gui.socialInteractions.server_label: %s - %s players
+ gui.socialInteractions.show: %s, Show in Chat
+ gui.socialInteractions.shown_in_chat: Chat messages from %s will be shown
+ gui.socialInteractions.tab_all: All
+ gui.socialInteractions.tab_hidden: Hidden
+ gui.socialInteractions.title: Social Interactions
+ gui.socialInteractions.tooltip.hide: Hide messages from %s in chat
+ gui.socialInteractions.tooltip.show: Show messages from %s in chat
+ key.socialInteractions: Social Interactions Screen
+ multiplayer.disconnect.incompatible: Incompatible client! Please use %s
- multiplayer.disconnect.outdated_client: Outdated client! Please use %s
- multiplayer.disconnect.outdated_server: Outdated server! I'm still on %s
+ multiplayer.socialInteractions.not_available: Social Interactions are only available in Multiplayer worlds
- multiplayer.status.client_out_of_date: Client out of date!
+ multiplayer.status.incompatible: Incompatible version!
- multiplayer.status.server_out_of_date: Server out of date!
+ tutorial.socialInteractions.description: Press %s to open
+ tutorial.socialInteractions.title: Social Interactions
```

</details>
</details>
<details><summary>File structure</summary>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/textures/gui/social_interactions.png
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
- net.minecraft.server.network.TextFilter
- net.minecraft.server.network.TextFilterClient$1
- net.minecraft.server.network.TextFilterClient$PlayerContext
```

</details>
<details>
<summary>
Changes
</summary>

```
net.minecraft.SharedConstants +1M
```
```
XXX.protocol.game.ServerboundEditBookPacket +2M -2M | +1P -1P
```
```
XXX.minecraft.server.MinecraftServer +1M
```
```
XXX.server.commands.EmoteCommands +4M -1M
```
```
XXX.server.level.ServerPlayer +1M | +1P
```
```
XXX.server.level.WorldGenRegion +1P
```
```
XXX.server.network.ServerGamePacketListenerImpl +18M -5M
```

</details>













<details>
<summary>
net.minecraft.SharedConstants
</summary>

```diff
- int getProtocolVersion()
```

</details>





































































































































































































































































































































































































<details>
<summary>
net.minecraft.network.protocol.game.ServerboundEditBookPacket
</summary>

```diff
- int getSlot()
+ InteractionHand getHand()
- void <init>(ItemStack,boolean,int)
+ void <init>(ItemStack,boolean,InteractionHand)
```

</details>
































































<details>
<summary>
net.minecraft.server.MinecraftServer
</summary>

```diff
- TextFilter createTextFilterForPlayer(ServerPlayer)
```

</details>




















<details>
<summary>
net.minecraft.server.commands.EmoteCommands
</summary>

```diff
- Component createMessage(CommandContext,String)
+ int lambda$register$0(CommandContext)
- int lambda$register$2(CommandContext)
- void lambda$null$0(MinecraftServer,CommandContext,Entity,String)
- void lambda$null$1(MinecraftServer,CommandContext,Entity,Optional)
```

</details>

































































<details>
<summary>
net.minecraft.server.level.ServerPlayer
</summary>

```diff
- TextFilter getTextFilter()
```

</details>










<details>
<summary>
net.minecraft.server.network.ServerGamePacketListenerImpl
</summary>

```diff
+ boolean lambda$isPlayerCollidingWithAnythingNew$2(Entity)
+ boolean lambda$isPlayerCollidingWithAnythingNew$3(VoxelShape,VoxelShape)
- boolean lambda$isPlayerCollidingWithAnythingNew$7(Entity)
- boolean lambda$isPlayerCollidingWithAnythingNew$8(VoxelShape,VoxelShape)
+ String lambda$send$4(Packet)
- String lambda$send$9(Packet)
- void filterTextPacket(List,Consumer)
- void filterTextPacket(Object,Consumer,BiFunction)
- void filterTextPacket(String,Consumer)
- void handleChat(String)
- void lambda$filterTextPacket$1(Consumer,Object)
- void lambda$filterTextPacket$2(Consumer,Optional)
- void lambda$filterTextPacket$3(Consumer,Object)
+ void lambda$handleCustomCommandSuggestions$1(ServerboundCommandSuggestionPacket,Suggestions)
- void lambda$handleCustomCommandSuggestions$4(ServerboundCommandSuggestionPacket,Suggestions)
- void lambda$handleEditBook$5(int,List)
- void lambda$handleEditBook$6(int,List)
- void lambda$handlePlaceRecipe$10(ServerboundPlaceRecipePacket,Recipe)
+ void lambda$handlePlaceRecipe$5(ServerboundPlaceRecipePacket,Recipe)
- void lambda$handleSignUpdate$11(ServerboundSignUpdatePacket,List)
- void signBook(String,List,int)
- void updateBookContents(List,int)
- void updateSignText(ServerboundSignUpdatePacket,List)
```

</details>

















































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































<h2>Client</h2>
<details>
<summary>
Classes
</summary>

```diff
- com.mojang.blaze3d.platform.GlStateManager$SourceFactor
+ com.mojang.blaze3d.platform.GlStateManager$StencilFunc
- com.mojang.blaze3d.platform.GlStateManager$StencilState
+ com.mojang.blaze3d.platform.GlStateManager$TexGen
- com.mojang.blaze3d.platform.GlStateManager$TexGenCoord
+ com.mojang.blaze3d.platform.GlStateManager$TexGenState
- com.mojang.blaze3d.platform.GlStateManager$TextureState
+ com.mojang.blaze3d.platform.GlStateManager$Viewport
- com.mojang.blaze3d.platform.GlUtil
+ com.mojang.blaze3d.platform.InputConstants
- com.mojang.blaze3d.platform.InputConstants$1
+ com.mojang.blaze3d.platform.InputConstants$Key
- com.mojang.blaze3d.platform.InputConstants$Type
+ com.mojang.blaze3d.platform.Lighting
- com.mojang.blaze3d.platform.MemoryTracker
+ com.mojang.blaze3d.platform.Monitor
- com.mojang.blaze3d.platform.MonitorCreator
+ com.mojang.blaze3d.platform.NativeImage
- com.mojang.blaze3d.platform.NativeImage$1
+ com.mojang.blaze3d.platform.NativeImage$Format
- com.mojang.blaze3d.platform.NativeImage$InternalGlFormat
+ com.mojang.blaze3d.platform.NativeImage$WriteCallback
- com.mojang.blaze3d.platform.PngInfo
+ com.mojang.blaze3d.platform.PngInfo$1
- com.mojang.blaze3d.platform.PngInfo$StbReader
+ com.mojang.blaze3d.platform.PngInfo$StbReaderBufferedChannel
- com.mojang.blaze3d.platform.PngInfo$StbReaderSeekableByteChannel
+ com.mojang.blaze3d.platform.ScreenManager
- com.mojang.blaze3d.platform.SnooperAccess
+ com.mojang.blaze3d.platform.TextureUtil
- com.mojang.blaze3d.platform.VideoMode
+ com.mojang.blaze3d.platform.Window
- com.mojang.blaze3d.platform.Window$1
+ com.mojang.blaze3d.platform.Window$WindowInitFailed
- com.mojang.blaze3d.platform.WindowEventHandler
+ com.mojang.blaze3d.shaders.AbstractUniform
- com.mojang.blaze3d.shaders.BlendMode
+ com.mojang.blaze3d.shaders.Effect
- com.mojang.blaze3d.shaders.Program
+ com.mojang.blaze3d.shaders.Program$Type
- com.mojang.blaze3d.shaders.ProgramManager
+ com.mojang.blaze3d.shaders.Uniform
- com.mojang.blaze3d.systems.RenderSystem
+ com.mojang.blaze3d.vertex.BufferBuilder
- com.mojang.blaze3d.vertex.BufferBuilder$1
+ com.mojang.blaze3d.vertex.BufferBuilder$DrawState
- com.mojang.blaze3d.vertex.BufferBuilder$State
+ com.mojang.blaze3d.vertex.BufferUploader
- com.mojang.blaze3d.vertex.BufferVertexConsumer
- com.mojang.blaze3d.vertex.DefaultedVertexConsumer
+ com.mojang.blaze3d.vertex.DefaultVertexFormat
+ com.mojang.blaze3d.vertex.PoseStack
- com.mojang.blaze3d.vertex.PoseStack$1
+ com.mojang.blaze3d.vertex.PoseStack$Pose
- com.mojang.blaze3d.vertex.SheetedDecalTextureGenerator
+ com.mojang.blaze3d.vertex.Tesselator
- com.mojang.blaze3d.vertex.VertexBuffer
+ com.mojang.blaze3d.vertex.VertexConsumer
- com.mojang.blaze3d.vertex.VertexFormat
+ com.mojang.blaze3d.vertex.VertexFormatElement
- com.mojang.blaze3d.vertex.VertexFormatElement$Type
+ com.mojang.blaze3d.vertex.VertexFormatElement$Usage
- com.mojang.blaze3d.vertex.VertexFormatElement$Usage$SetupState
+ com.mojang.blaze3d.vertex.VertexMultiConsumer
- com.mojang.blaze3d.vertex.VertexMultiConsumer$Double
+ com.mojang.math.Matrix3f
- com.mojang.math.Matrix4f
+ com.mojang.math.OctahedralGroup
- com.mojang.math.OctahedralGroup$1
+ com.mojang.math.Quaternion
- com.mojang.math.SymmetricGroup3
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
- com.mojang.realmsclient.dto.GuardedSerializer
+ com.mojang.realmsclient.dto.Ops
- com.mojang.realmsclient.dto.PendingInvite
+ com.mojang.realmsclient.dto.PendingInvitesList
- com.mojang.realmsclient.dto.PingResult
+ com.mojang.realmsclient.dto.PlayerInfo
- com.mojang.realmsclient.dto.RealmsDescriptionDto
+ com.mojang.realmsclient.dto.RealmsNews
- com.mojang.realmsclient.dto.RealmsServer
+ com.mojang.realmsclient.dto.RealmsServer$McoServerComparator
- com.mojang.realmsclient.dto.RealmsServer$State
+ com.mojang.realmsclient.dto.RealmsServer$WorldType
- com.mojang.realmsclient.dto.RealmsServerAddress
+ com.mojang.realmsclient.dto.RealmsServerList
- com.mojang.realmsclient.dto.RealmsServerPing
+ com.mojang.realmsclient.dto.RealmsServerPlayerList
- com.mojang.realmsclient.dto.RealmsServerPlayerLists
+ com.mojang.realmsclient.dto.RealmsWorldOptions
- com.mojang.realmsclient.dto.RealmsWorldResetDto
+ com.mojang.realmsclient.dto.ReflectionBasedSerialization
- com.mojang.realmsclient.dto.RegionPingResult
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
+ com.mojang.realmsclient.gui.ErrorCallback
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
- com.mojang.realmsclient.gui.RealmsWorldSlotButton$State
+ com.mojang.realmsclient.gui.RowButton
- com.mojang.realmsclient.gui.screens.RealmsBackupInfoScreen
+ com.mojang.realmsclient.gui.screens.RealmsBackupInfoScreen$BackupInfoList
- com.mojang.realmsclient.gui.screens.RealmsBackupInfoScreen$BackupInfoListEntry
+ com.mojang.realmsclient.gui.screens.RealmsBackupScreen
- com.mojang.realmsclient.gui.screens.RealmsBackupScreen$1
+ com.mojang.realmsclient.gui.screens.RealmsBackupScreen$BackupObjectSelectionList
- com.mojang.realmsclient.gui.screens.RealmsBackupScreen$Entry
+ com.mojang.realmsclient.gui.screens.RealmsBrokenWorldScreen
- com.mojang.realmsclient.gui.screens.RealmsClientOutdatedScreen
+ com.mojang.realmsclient.gui.screens.RealmsConfigureWorldScreen
- com.mojang.realmsclient.gui.screens.RealmsConfigureWorldScreen$1
+ com.mojang.realmsclient.gui.screens.RealmsConfirmScreen
- com.mojang.realmsclient.gui.screens.RealmsCreateRealmScreen
+ com.mojang.realmsclient.gui.screens.RealmsDownloadLatestWorldScreen
- com.mojang.realmsclient.gui.screens.RealmsDownloadLatestWorldScreen$DownloadStatus
+ com.mojang.realmsclient.gui.screens.RealmsGenericErrorScreen
- com.mojang.realmsclient.gui.screens.RealmsInviteScreen
+ com.mojang.realmsclient.gui.screens.RealmsLongConfirmationScreen
- com.mojang.realmsclient.gui.screens.RealmsLongConfirmationScreen$Type
+ com.mojang.realmsclient.gui.screens.RealmsLongRunningMcoTaskScreen
- com.mojang.realmsclient.gui.screens.RealmsNotificationsScreen
+ com.mojang.realmsclient.gui.screens.RealmsNotificationsScreen$1
- com.mojang.realmsclient.gui.screens.RealmsParentalConsentScreen
+ com.mojang.realmsclient.gui.screens.RealmsPendingInvitesScreen
- com.mojang.realmsclient.gui.screens.RealmsPendingInvitesScreen$1
+ com.mojang.realmsclient.gui.screens.RealmsPendingInvitesScreen$2
- com.mojang.realmsclient.gui.screens.RealmsPendingInvitesScreen$3
+ com.mojang.realmsclient.gui.screens.RealmsPendingInvitesScreen$Entry
- com.mojang.realmsclient.gui.screens.RealmsPendingInvitesScreen$Entry$AcceptRowButton
+ com.mojang.realmsclient.gui.screens.RealmsPendingInvitesScreen$Entry$RejectRowButton
- com.mojang.realmsclient.gui.screens.RealmsPendingInvitesScreen$PendingInvitationSelectionList
+ com.mojang.realmsclient.gui.screens.RealmsPlayerScreen
- com.mojang.realmsclient.gui.screens.RealmsPlayerScreen$Entry
+ com.mojang.realmsclient.gui.screens.RealmsPlayerScreen$InvitedObjectSelectionList
- com.mojang.realmsclient.gui.screens.RealmsPlayerScreen$UserAction
+ com.mojang.realmsclient.gui.screens.RealmsResetNormalWorldScreen
- com.mojang.realmsclient.gui.screens.RealmsResetWorldScreen
+ com.mojang.realmsclient.gui.screens.RealmsResetWorldScreen$1
- com.mojang.realmsclient.gui.screens.RealmsResetWorldScreen$2
+ com.mojang.realmsclient.gui.screens.RealmsResetWorldScreen$FrameButton
- com.mojang.realmsclient.gui.screens.RealmsResetWorldScreen$ResetType
+ com.mojang.realmsclient.gui.screens.RealmsResetWorldScreen$ResetWorldInfo
- com.mojang.realmsclient.gui.screens.RealmsScreenWithCallback
+ com.mojang.realmsclient.gui.screens.RealmsSelectFileToUploadScreen
- com.mojang.realmsclient.gui.screens.RealmsSelectFileToUploadScreen$Entry
+ com.mojang.realmsclient.gui.screens.RealmsSelectFileToUploadScreen$WorldSelectionList
- com.mojang.realmsclient.gui.screens.RealmsSelectWorldTemplateScreen
+ com.mojang.realmsclient.gui.screens.RealmsSelectWorldTemplateScreen$1
- com.mojang.realmsclient.gui.screens.RealmsSelectWorldTemplateScreen$Entry
+ com.mojang.realmsclient.gui.screens.RealmsSelectWorldTemplateScreen$WorldTemplateObjectSelectionList
- com.mojang.realmsclient.gui.screens.RealmsSettingsScreen
+ com.mojang.realmsclient.gui.screens.RealmsSlotOptionsScreen
- com.mojang.realmsclient.gui.screens.RealmsSlotOptionsScreen$SettingsSlider
+ com.mojang.realmsclient.gui.screens.RealmsSubscriptionInfoScreen
- com.mojang.realmsclient.gui.screens.RealmsSubscriptionInfoScreen$1
+ com.mojang.realmsclient.gui.screens.RealmsTermsScreen
- com.mojang.realmsclient.gui.screens.RealmsUploadScreen
+ com.mojang.realmsclient.gui.screens.UploadResult
- com.mojang.realmsclient.gui.screens.UploadResult$1
+ com.mojang.realmsclient.gui.screens.UploadResult$Builder
+ com.mojang.realmsclient.KeyCombo
- com.mojang.realmsclient.RealmsMainScreen
+ com.mojang.realmsclient.RealmsMainScreen$1
- com.mojang.realmsclient.RealmsMainScreen$2
+ com.mojang.realmsclient.RealmsMainScreen$3
- com.mojang.realmsclient.RealmsMainScreen$4
+ com.mojang.realmsclient.RealmsMainScreen$5
- com.mojang.realmsclient.RealmsMainScreen$CloseButton
+ com.mojang.realmsclient.RealmsMainScreen$Entry
- com.mojang.realmsclient.RealmsMainScreen$HoveredElement
+ com.mojang.realmsclient.RealmsMainScreen$NewsButton
- com.mojang.realmsclient.RealmsMainScreen$PendingInvitesButton
+ com.mojang.realmsclient.RealmsMainScreen$RealmSelectionList
- com.mojang.realmsclient.RealmsMainScreen$ServerEntry
+ com.mojang.realmsclient.RealmsMainScreen$ShowPopupButton
- com.mojang.realmsclient.RealmsMainScreen$TrialEntry
+ com.mojang.realmsclient.Unit
- com.mojang.realmsclient.util.JsonUtils
+ com.mojang.realmsclient.util.RealmsPersistence
- com.mojang.realmsclient.util.RealmsPersistence$RealmsPersistenceData
+ com.mojang.realmsclient.util.RealmsTextureManager
- com.mojang.realmsclient.util.RealmsTextureManager$1
+ com.mojang.realmsclient.util.RealmsTextureManager$RealmsTexture
- com.mojang.realmsclient.util.RealmsUtil
+ com.mojang.realmsclient.util.RealmsUtil$1
- com.mojang.realmsclient.util.SkinProcessor
+ com.mojang.realmsclient.util.task.CloseServerTask
- com.mojang.realmsclient.util.task.ConnectTask
+ com.mojang.realmsclient.util.task.DownloadTask
- com.mojang.realmsclient.util.task.GetServerDetailsTask
+ com.mojang.realmsclient.util.task.LongRunningTask
- com.mojang.realmsclient.util.task.OpenServerTask
+ com.mojang.realmsclient.util.task.ResettingWorldTask
- com.mojang.realmsclient.util.task.RestoreTask
+ com.mojang.realmsclient.util.task.SwitchMinigameTask
- com.mojang.realmsclient.util.task.SwitchSlotTask
+ com.mojang.realmsclient.util.task.WorldCreationTask
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
- net.minecraft.advancements.critereon.AbstractCriterionTriggerInstance
+ net.minecraft.advancements.critereon.BeeNestDestroyedTrigger
- net.minecraft.advancements.critereon.BeeNestDestroyedTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.BlockPredicate
- net.minecraft.advancements.critereon.BlockPredicate$Builder
+ net.minecraft.advancements.critereon.BredAnimalsTrigger
- net.minecraft.advancements.critereon.BredAnimalsTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.BrewedPotionTrigger
- net.minecraft.advancements.critereon.BrewedPotionTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.ChangeDimensionTrigger
- net.minecraft.advancements.critereon.ChangeDimensionTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.ChanneledLightningTrigger
- net.minecraft.advancements.critereon.ChanneledLightningTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.ConstructBeaconTrigger
- net.minecraft.advancements.critereon.ConstructBeaconTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.ConsumeItemTrigger
- net.minecraft.advancements.critereon.ConsumeItemTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.CuredZombieVillagerTrigger
- net.minecraft.advancements.critereon.CuredZombieVillagerTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.DamagePredicate
- net.minecraft.advancements.critereon.DamagePredicate$Builder
+ net.minecraft.advancements.critereon.DamageSourcePredicate
- net.minecraft.advancements.critereon.DamageSourcePredicate$Builder
+ net.minecraft.advancements.critereon.DeserializationContext
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
+ net.minecraft.advancements.critereon.EntityPredicate$Composite
- net.minecraft.advancements.critereon.EntityTypePredicate
+ net.minecraft.advancements.critereon.EntityTypePredicate$1
- net.minecraft.advancements.critereon.EntityTypePredicate$TagPredicate
+ net.minecraft.advancements.critereon.EntityTypePredicate$TypePredicate
- net.minecraft.advancements.critereon.FilledBucketTrigger
+ net.minecraft.advancements.critereon.FilledBucketTrigger$TriggerInstance
- net.minecraft.advancements.critereon.FishingHookPredicate
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
+ net.minecraft.advancements.critereon.ItemPickedUpByEntityTrigger
- net.minecraft.advancements.critereon.ItemPickedUpByEntityTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.ItemPredicate
- net.minecraft.advancements.critereon.ItemPredicate$Builder
+ net.minecraft.advancements.critereon.ItemUsedOnBlockTrigger
- net.minecraft.advancements.critereon.ItemUsedOnBlockTrigger$TriggerInstance
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
- net.minecraft.advancements.critereon.LootTableTrigger
+ net.minecraft.advancements.critereon.LootTableTrigger$TriggerInstance
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
+ net.minecraft.advancements.critereon.package-info
- net.minecraft.advancements.critereon.PlacedBlockTrigger
+ net.minecraft.advancements.critereon.PlacedBlockTrigger$TriggerInstance
- net.minecraft.advancements.critereon.PlayerHurtEntityTrigger
+ net.minecraft.advancements.critereon.PlayerHurtEntityTrigger$TriggerInstance
- net.minecraft.advancements.critereon.PlayerInteractTrigger
+ net.minecraft.advancements.critereon.PlayerInteractTrigger$TriggerInstance
- net.minecraft.advancements.critereon.PlayerPredicate
+ net.minecraft.advancements.critereon.PlayerPredicate$1
- net.minecraft.advancements.critereon.PlayerPredicate$AdvancementCriterionsPredicate
+ net.minecraft.advancements.critereon.PlayerPredicate$AdvancementDonePredicate
- net.minecraft.advancements.critereon.PlayerPredicate$AdvancementPredicate
+ net.minecraft.advancements.critereon.PlayerPredicate$Builder
- net.minecraft.advancements.critereon.RecipeUnlockedTrigger
+ net.minecraft.advancements.critereon.RecipeUnlockedTrigger$TriggerInstance
- net.minecraft.advancements.critereon.SerializationContext
+ net.minecraft.advancements.critereon.ShotCrossbowTrigger
- net.minecraft.advancements.critereon.ShotCrossbowTrigger$TriggerInstance
+ net.minecraft.advancements.critereon.SimpleCriterionTrigger
- net.minecraft.advancements.critereon.SlideDownBlockTrigger
+ net.minecraft.advancements.critereon.SlideDownBlockTrigger$TriggerInstance
- net.minecraft.advancements.critereon.StatePropertiesPredicate
+ net.minecraft.advancements.critereon.StatePropertiesPredicate$1
- net.minecraft.advancements.critereon.StatePropertiesPredicate$Builder
+ net.minecraft.advancements.critereon.StatePropertiesPredicate$ExactPropertyMatcher
- net.minecraft.advancements.critereon.StatePropertiesPredicate$PropertyMatcher
+ net.minecraft.advancements.critereon.StatePropertiesPredicate$RangedPropertyMatcher
- net.minecraft.advancements.critereon.SummonedEntityTrigger
+ net.minecraft.advancements.critereon.SummonedEntityTrigger$TriggerInstance
- net.minecraft.advancements.critereon.TameAnimalTrigger
+ net.minecraft.advancements.critereon.TameAnimalTrigger$TriggerInstance
- net.minecraft.advancements.critereon.TargetBlockTrigger
+ net.minecraft.advancements.critereon.TargetBlockTrigger$TriggerInstance
- net.minecraft.advancements.critereon.TickTrigger
+ net.minecraft.advancements.critereon.TickTrigger$TriggerInstance
- net.minecraft.advancements.critereon.TradeTrigger
+ net.minecraft.advancements.critereon.TradeTrigger$TriggerInstance
- net.minecraft.advancements.critereon.UsedEnderEyeTrigger
+ net.minecraft.advancements.critereon.UsedEnderEyeTrigger$TriggerInstance
- net.minecraft.advancements.critereon.UsedTotemTrigger
+ net.minecraft.advancements.critereon.UsedTotemTrigger$TriggerInstance
- net.minecraft.advancements.critereon.WrappedMinMaxBounds
- net.minecraft.advancements.CriteriaTriggers
+ net.minecraft.advancements.Criterion
- net.minecraft.advancements.CriterionProgress
+ net.minecraft.advancements.CriterionTrigger
- net.minecraft.advancements.CriterionTrigger$Listener
+ net.minecraft.advancements.CriterionTriggerInstance
- net.minecraft.advancements.DisplayInfo
+ net.minecraft.advancements.FrameType
- net.minecraft.advancements.package-info
- net.minecraft.advancements.RequirementsStrategy
+ net.minecraft.advancements.TreeNodePosition
- net.minecraft.BlockUtil
+ net.minecraft.BlockUtil$FoundRectangle
- net.minecraft.BlockUtil$IntBounds
+ net.minecraft.CharPredicate
- net.minecraft.ChatFormatting
+ net.minecraft.client.AmbientOcclusionStatus
- net.minecraft.client.AttackIndicatorStatus
+ net.minecraft.client.BooleanOption
- net.minecraft.client.Camera
+ net.minecraft.client.CameraType
- net.minecraft.client.ClientBrandRetriever
+ net.minecraft.client.ClientRecipeBook
- net.minecraft.client.CloudStatus
- net.minecraft.client.color.block.BlockColor
+ net.minecraft.client.color.block.BlockColors
- net.minecraft.client.color.block.BlockTintCache
+ net.minecraft.client.color.block.BlockTintCache$1
- net.minecraft.client.color.block.BlockTintCache$LatestCacheInfo
+ net.minecraft.client.color.block.package-info
- net.minecraft.client.color.item.ItemColor
+ net.minecraft.client.color.item.ItemColors
- net.minecraft.client.color.item.package-info
+ net.minecraft.client.ComponentCollector
- net.minecraft.client.CycleOption
+ net.minecraft.client.DebugQueryHandler
- net.minecraft.client.FullscreenResolutionProgressOption
+ net.minecraft.client.Game
- net.minecraft.client.Game$Metrics
+ net.minecraft.client.GraphicsStatus
- net.minecraft.client.GraphicsStatus$1
- net.minecraft.client.gui.chat.ChatListener
+ net.minecraft.client.gui.chat.NarratorChatListener
- net.minecraft.client.gui.chat.OverlayChatListener
- net.minecraft.client.gui.chat.package-info
+ net.minecraft.client.gui.chat.StandardChatListener
+ net.minecraft.client.gui.components.AbstractButton
- net.minecraft.client.gui.components.AbstractOptionSliderButton
+ net.minecraft.client.gui.components.AbstractSelectionList
- net.minecraft.client.gui.components.AbstractSelectionList$1
+ net.minecraft.client.gui.components.AbstractSelectionList$Entry
- net.minecraft.client.gui.components.AbstractSelectionList$SelectionDirection
+ net.minecraft.client.gui.components.AbstractSelectionList$TrackedList
- net.minecraft.client.gui.components.AbstractSliderButton
+ net.minecraft.client.gui.components.AbstractWidget
- net.minecraft.client.gui.components.BossHealthOverlay
+ net.minecraft.client.gui.components.Button
- net.minecraft.client.gui.components.Button$OnPress
+ net.minecraft.client.gui.components.Button$OnTooltip
- net.minecraft.client.gui.components.ChatComponent
+ net.minecraft.client.gui.components.Checkbox
- net.minecraft.client.gui.components.CommandSuggestions
+ net.minecraft.client.gui.components.CommandSuggestions$1
- net.minecraft.client.gui.components.CommandSuggestions$SuggestionsList
+ net.minecraft.client.gui.components.ComponentRenderUtils
- net.minecraft.client.gui.components.ContainerObjectSelectionList
+ net.minecraft.client.gui.components.ContainerObjectSelectionList$Entry
- net.minecraft.client.gui.components.DebugScreenOverlay
+ net.minecraft.client.gui.components.DebugScreenOverlay$1
- net.minecraft.client.gui.components.EditBox
- net.minecraft.client.gui.components.events.AbstractContainerEventHandler
+ net.minecraft.client.gui.components.events.ContainerEventHandler
- net.minecraft.client.gui.components.events.GuiEventListener
+ net.minecraft.client.gui.components.events.package-info
+ net.minecraft.client.gui.components.ImageButton
- net.minecraft.client.gui.components.LerpingBossEvent
+ net.minecraft.client.gui.components.LerpingBossEvent$1
- net.minecraft.client.gui.components.LockIconButton
+ net.minecraft.client.gui.components.LockIconButton$Icon
- net.minecraft.client.gui.components.MultiLineLabel
+ net.minecraft.client.gui.components.MultiLineLabel$1
- net.minecraft.client.gui.components.MultiLineLabel$2
+ net.minecraft.client.gui.components.MultiLineLabel$TextWithWidth
- net.minecraft.client.gui.components.ObjectSelectionList
+ net.minecraft.client.gui.components.ObjectSelectionList$Entry
- net.minecraft.client.gui.components.OptionButton
+ net.minecraft.client.gui.components.OptionsList
- net.minecraft.client.gui.components.OptionsList$Entry
- net.minecraft.client.gui.components.package-info
+ net.minecraft.client.gui.components.PlayerTabOverlay
- net.minecraft.client.gui.components.PlayerTabOverlay$1
+ net.minecraft.client.gui.components.PlayerTabOverlay$PlayerInfoComparator
- net.minecraft.client.gui.components.SliderButton
- net.minecraft.client.gui.components.spectator.package-info
+ net.minecraft.client.gui.components.spectator.SpectatorGui
+ net.minecraft.client.gui.components.StateSwitchingButton
- net.minecraft.client.gui.components.SubtitleOverlay
+ net.minecraft.client.gui.components.SubtitleOverlay$Subtitle
- net.minecraft.client.gui.components.TickableWidget
+ net.minecraft.client.gui.components.toasts.AdvancementToast
- net.minecraft.client.gui.components.toasts.package-info
- net.minecraft.client.gui.components.toasts.RecipeToast
+ net.minecraft.client.gui.components.toasts.SystemToast
- net.minecraft.client.gui.components.toasts.SystemToast$SystemToastIds
+ net.minecraft.client.gui.components.toasts.Toast
- net.minecraft.client.gui.components.toasts.Toast$Visibility
+ net.minecraft.client.gui.components.toasts.ToastComponent
- net.minecraft.client.gui.components.toasts.ToastComponent$1
+ net.minecraft.client.gui.components.toasts.ToastComponent$ToastInstance
- net.minecraft.client.gui.components.toasts.TutorialToast
+ net.minecraft.client.gui.components.toasts.TutorialToast$Icons
+ net.minecraft.client.gui.components.TooltipAccessor
- net.minecraft.client.gui.components.VolumeSlider
+ net.minecraft.client.gui.components.Widget
+ net.minecraft.client.gui.Font
+ net.minecraft.client.gui.font.AllMissingGlyphProvider
- net.minecraft.client.gui.font.FontManager
+ net.minecraft.client.gui.font.FontManager$1
- net.minecraft.client.gui.font.FontSet
+ net.minecraft.client.gui.font.FontTexture
- net.minecraft.client.gui.font.FontTexture$1
+ net.minecraft.client.gui.font.FontTexture$Node
+ net.minecraft.client.gui.font.glyphs.BakedGlyph
- net.minecraft.client.gui.font.glyphs.BakedGlyph$Effect
+ net.minecraft.client.gui.font.glyphs.EmptyGlyph
- net.minecraft.client.gui.font.glyphs.MissingGlyph
- net.minecraft.client.gui.font.glyphs.package-info
+ net.minecraft.client.gui.font.glyphs.WhiteGlyph
+ net.minecraft.client.gui.font.package-info
- net.minecraft.client.gui.font.providers.BitmapProvider
+ net.minecraft.client.gui.font.providers.BitmapProvider$1
- net.minecraft.client.gui.font.providers.BitmapProvider$Builder
+ net.minecraft.client.gui.font.providers.BitmapProvider$Glyph
- net.minecraft.client.gui.font.providers.GlyphProviderBuilder
+ net.minecraft.client.gui.font.providers.GlyphProviderBuilderType
- net.minecraft.client.gui.font.providers.LegacyUnicodeBitmapsProvider
+ net.minecraft.client.gui.font.providers.LegacyUnicodeBitmapsProvider$1
- net.minecraft.client.gui.font.providers.LegacyUnicodeBitmapsProvider$Builder
+ net.minecraft.client.gui.font.providers.LegacyUnicodeBitmapsProvider$Glyph
+ net.minecraft.client.gui.font.providers.package-info
- net.minecraft.client.gui.font.providers.TrueTypeGlyphProviderBuilder
- net.minecraft.client.gui.font.TextFieldHelper
- net.minecraft.client.gui.Font$StringRenderOutput
+ net.minecraft.client.gui.Gui
- net.minecraft.client.gui.GuiComponent
+ net.minecraft.client.gui.MapRenderer
- net.minecraft.client.gui.MapRenderer$1
+ net.minecraft.client.gui.MapRenderer$MapInstance
- net.minecraft.client.gui.package-info
+ net.minecraft.client.gui.screens.AccessibilityOptionsScreen
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
- net.minecraft.client.gui.screens.AlertScreen
+ net.minecraft.client.gui.screens.BackupConfirmScreen
- net.minecraft.client.gui.screens.BackupConfirmScreen$Listener
+ net.minecraft.client.gui.screens.ChatOptionsScreen
- net.minecraft.client.gui.screens.ChatScreen
+ net.minecraft.client.gui.screens.ChatScreen$1
- net.minecraft.client.gui.screens.ConfirmLinkScreen
+ net.minecraft.client.gui.screens.ConfirmScreen
- net.minecraft.client.gui.screens.ConnectScreen
+ net.minecraft.client.gui.screens.ConnectScreen$1
+ net.minecraft.client.gui.screens.controls.ControlList
- net.minecraft.client.gui.screens.controls.ControlList$1
+ net.minecraft.client.gui.screens.controls.ControlList$CategoryEntry
- net.minecraft.client.gui.screens.controls.ControlList$Entry
+ net.minecraft.client.gui.screens.controls.ControlList$KeyEntry
- net.minecraft.client.gui.screens.controls.ControlList$KeyEntry$1
+ net.minecraft.client.gui.screens.controls.ControlList$KeyEntry$2
- net.minecraft.client.gui.screens.controls.ControlsScreen
+ net.minecraft.client.gui.screens.controls.package-info
- net.minecraft.client.gui.screens.CreateBuffetWorldScreen
+ net.minecraft.client.gui.screens.CreateBuffetWorldScreen$1
- net.minecraft.client.gui.screens.CreateBuffetWorldScreen$BiomeList
+ net.minecraft.client.gui.screens.CreateBuffetWorldScreen$BiomeList$Entry
- net.minecraft.client.gui.screens.CreateFlatWorldScreen
+ net.minecraft.client.gui.screens.CreateFlatWorldScreen$1
- net.minecraft.client.gui.screens.CreateFlatWorldScreen$DetailsList
+ net.minecraft.client.gui.screens.CreateFlatWorldScreen$DetailsList$Entry
- net.minecraft.client.gui.screens.DatapackLoadFailureScreen
+ net.minecraft.client.gui.screens.DeathScreen
- net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen
+ net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen$1
- net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen$GameModeIcon
+ net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen$GameModeSlot
- net.minecraft.client.gui.screens.DemoIntroScreen
+ net.minecraft.client.gui.screens.DirectJoinServerScreen
- net.minecraft.client.gui.screens.DisconnectedScreen
+ net.minecraft.client.gui.screens.EditServerScreen
- net.minecraft.client.gui.screens.ErrorScreen
+ net.minecraft.client.gui.screens.GenericDirtMessageScreen
- net.minecraft.client.gui.screens.InBedChatScreen
- net.minecraft.client.gui.screens.inventory.AbstractCommandBlockEditScreen
+ net.minecraft.client.gui.screens.inventory.AbstractCommandBlockEditScreen$1
- net.minecraft.client.gui.screens.inventory.AbstractContainerScreen
+ net.minecraft.client.gui.screens.inventory.AbstractFurnaceScreen
- net.minecraft.client.gui.screens.inventory.AnvilScreen
+ net.minecraft.client.gui.screens.inventory.BeaconScreen
- net.minecraft.client.gui.screens.inventory.BeaconScreen$1
+ net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconCancelButton
- net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconConfirmButton
+ net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconPowerButton
- net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconScreenButton
+ net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconSpriteScreenButton
- net.minecraft.client.gui.screens.inventory.BlastFurnaceScreen
+ net.minecraft.client.gui.screens.inventory.BookEditScreen
- net.minecraft.client.gui.screens.inventory.BookEditScreen$DisplayCache
+ net.minecraft.client.gui.screens.inventory.BookEditScreen$LineInfo
- net.minecraft.client.gui.screens.inventory.BookEditScreen$Pos2i
+ net.minecraft.client.gui.screens.inventory.BookViewScreen
- net.minecraft.client.gui.screens.inventory.BookViewScreen$1
+ net.minecraft.client.gui.screens.inventory.BookViewScreen$BookAccess
- net.minecraft.client.gui.screens.inventory.BookViewScreen$WritableBookAccess
+ net.minecraft.client.gui.screens.inventory.BookViewScreen$WrittenBookAccess
- net.minecraft.client.gui.screens.inventory.BrewingStandScreen
+ net.minecraft.client.gui.screens.inventory.CartographyTableScreen
- net.minecraft.client.gui.screens.inventory.CommandBlockEditScreen
+ net.minecraft.client.gui.screens.inventory.CommandBlockEditScreen$1
- net.minecraft.client.gui.screens.inventory.ContainerScreen
+ net.minecraft.client.gui.screens.inventory.CraftingScreen
- net.minecraft.client.gui.screens.inventory.CreativeInventoryListener
+ net.minecraft.client.gui.screens.inventory.CreativeModeInventoryScreen
- net.minecraft.client.gui.screens.inventory.CreativeModeInventoryScreen$CustomCreativeSlot
+ net.minecraft.client.gui.screens.inventory.CreativeModeInventoryScreen$ItemPickerMenu
- net.minecraft.client.gui.screens.inventory.CreativeModeInventoryScreen$SlotWrapper
+ net.minecraft.client.gui.screens.inventory.DispenserScreen
- net.minecraft.client.gui.screens.inventory.EffectRenderingInventoryScreen
+ net.minecraft.client.gui.screens.inventory.EnchantmentNames
- net.minecraft.client.gui.screens.inventory.EnchantmentScreen
+ net.minecraft.client.gui.screens.inventory.FurnaceScreen
- net.minecraft.client.gui.screens.inventory.GrindstoneScreen
+ net.minecraft.client.gui.screens.inventory.HopperScreen
- net.minecraft.client.gui.screens.inventory.HorseInventoryScreen
+ net.minecraft.client.gui.screens.inventory.InventoryScreen
- net.minecraft.client.gui.screens.inventory.ItemCombinerScreen
+ net.minecraft.client.gui.screens.inventory.JigsawBlockEditScreen
- net.minecraft.client.gui.screens.inventory.JigsawBlockEditScreen$1
+ net.minecraft.client.gui.screens.inventory.JigsawBlockEditScreen$2
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
- net.minecraft.client.gui.screens.packs.package-info
+ net.minecraft.client.gui.screens.packs.PackSelectionModel
- net.minecraft.client.gui.screens.packs.PackSelectionModel$Entry
+ net.minecraft.client.gui.screens.packs.PackSelectionModel$EntryBase
- net.minecraft.client.gui.screens.packs.PackSelectionModel$SelectedPackEntry
+ net.minecraft.client.gui.screens.packs.PackSelectionModel$UnselectedPackEntry
- net.minecraft.client.gui.screens.packs.PackSelectionScreen
+ net.minecraft.client.gui.screens.packs.PackSelectionScreen$Watcher
- net.minecraft.client.gui.screens.packs.TransferableSelectionList
+ net.minecraft.client.gui.screens.packs.TransferableSelectionList$PackEntry
- net.minecraft.client.gui.screens.PauseScreen
+ net.minecraft.client.gui.screens.PopupScreen
- net.minecraft.client.gui.screens.PopupScreen$ButtonOption
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
+ net.minecraft.client.gui.screens.Screen
- net.minecraft.client.gui.screens.ShareToLanScreen
+ net.minecraft.client.gui.screens.SimpleOptionsSubScreen
- net.minecraft.client.gui.screens.SkinCustomizationScreen
- net.minecraft.client.gui.screens.social.PlayerSocialManager
- net.minecraft.client.gui.screens.social.SocialInteractionsScreen
- net.minecraft.client.gui.screens.social.SocialInteractionsScreen$Page
+ net.minecraft.client.gui.screens.SoundOptionsScreen
- net.minecraft.client.gui.screens.TitleScreen
+ net.minecraft.client.gui.screens.VideoSettingsScreen
- net.minecraft.client.gui.screens.WinScreen
+ net.minecraft.client.GuiMessage
- net.minecraft.client.HotbarManager
- net.minecraft.client.KeyboardHandler
+ net.minecraft.client.KeyboardHandler$1
+ net.minecraft.client.KeyMapping
- net.minecraft.client.LogaritmicProgressOption
+ net.minecraft.client.Minecraft
- net.minecraft.client.Minecraft$1
+ net.minecraft.client.Minecraft$ExperimentalDialogType
- net.minecraft.client.Minecraft$ServerStem
+ net.minecraft.client.MouseHandler
- net.minecraft.client.NarratorStatus
+ net.minecraft.client.Option
- net.minecraft.client.Option$1
+ net.minecraft.client.Options
- net.minecraft.client.Options$1
+ net.minecraft.client.Options$2
- net.minecraft.client.ParticleStatus
+ net.minecraft.client.ProgressOption
- net.minecraft.client.RecipeBookCategories
+ net.minecraft.client.RecipeBookCategories$1
- net.minecraft.client.Screenshot
+ net.minecraft.client.Session
- net.minecraft.client.StringSplitter
+ net.minecraft.client.StringSplitter$1
- net.minecraft.client.StringSplitter$FlatComponents
+ net.minecraft.client.StringSplitter$LineBreakFinder
- net.minecraft.client.StringSplitter$LineComponent
+ net.minecraft.client.StringSplitter$LinePosConsumer
- net.minecraft.client.StringSplitter$WidthLimitedCharSink
+ net.minecraft.client.StringSplitter$WidthProvider
- net.minecraft.client.Timer
+ net.minecraft.client.ToggleKeyMapping
- net.minecraft.client.tutorial.Tutorial$TimedToast
- net.minecraft.client.User
+ net.minecraft.client.User$Type
+ net.minecraft.CrashReport
- net.minecraft.CrashReportCategory
+ net.minecraft.CrashReportCategory$Entry
- net.minecraft.CrashReportDetail
+ net.minecraft.DefaultUncaughtExceptionHandler
- net.minecraft.DefaultUncaughtExceptionHandlerWithName
+ net.minecraft.DetectedVersion
- net.minecraft.FieldsAreNonnullByDefault
+ net.minecraft.FileUtil
- net.minecraft.MethodsReturnNonnullByDefault
+ net.minecraft.ReportedException
- net.minecraft.ResourceLocationException
- net.minecraft.server.network.TextFilter
- net.minecraft.server.network.TextFilterClient$1
- net.minecraft.server.network.TextFilterClient$PlayerContext
+ net.minecraft.SharedConstants
- net.minecraft.Util
+ net.minecraft.Util$1
- net.minecraft.Util$3
+ net.minecraft.Util$4
- net.minecraft.Util$5
+ net.minecraft.Util$6
- net.minecraft.Util$7
+ net.minecraft.Util$IdentityStrategy
- net.minecraft.Util$OS
+ net.minecraft.Util$OS$1
- net.minecraft.Util$OS$2
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.screens.worldselection.WorldSelectionList +1M -2M
```
```
XXX.client.multiplayer.ClientPacketListener +1M
```
```
XXX.client.tutorial.Tutorial +4M | +1P
```
```
XXX.protocol.game.ServerboundEditBookPacket +2M -2M | +1P -1P
```
```
XXX.minecraft.server.MinecraftServer +1M
```
```
XXX.server.commands.EmoteCommands +4M -1M
```
```
XXX.server.level.ServerPlayer +1M | +1P
```
```
XXX.server.level.WorldGenRegion +1P
```
```
XXX.server.network.ServerGamePacketListenerImpl +18M -5M
```

</details>









































<details>
<summary>
net.minecraft.client.gui.screens.worldselection.WorldSelectionList
</summary>

```diff
+ int access$900(WorldSelectionList)
+ Logger access$1000()
- Logger access$900()
```

</details>





































































<details>
<summary>
net.minecraft.client.multiplayer.ClientPacketListener
</summary>

```diff
- Collection getOnlinePlayerIds()
```

</details>








































































































































































































































































































































































<details>
<summary>
net.minecraft.client.tutorial.Tutorial
</summary>

```diff
- boolean lambda$removeTimedToast$0(TutorialToast,Tutorial$TimedToast)
- boolean lambda$tick$1(Object)
- void addTimedToast(TutorialToast,int)
- void removeTimedToast(TutorialToast)
```

</details>





















































































































































































































































































































<details>
<summary>
net.minecraft.network.protocol.game.ServerboundEditBookPacket
</summary>

```diff
- int getSlot()
+ InteractionHand getHand()
- void <init>(ItemStack,boolean,int)
+ void <init>(ItemStack,boolean,InteractionHand)
```

</details>






































































<details>
<summary>
net.minecraft.server.MinecraftServer
</summary>

```diff
- TextFilter createTextFilterForPlayer(ServerPlayer)
```

</details>




















<details>
<summary>
net.minecraft.server.commands.EmoteCommands
</summary>

```diff
- Component createMessage(CommandContext,String)
+ int lambda$register$0(CommandContext)
- int lambda$register$2(CommandContext)
- void lambda$null$0(MinecraftServer,CommandContext,Entity,String)
- void lambda$null$1(MinecraftServer,CommandContext,Entity,Optional)
```

</details>

































































<details>
<summary>
net.minecraft.server.level.ServerPlayer
</summary>

```diff
- TextFilter getTextFilter()
```

</details>










<details>
<summary>
net.minecraft.server.network.ServerGamePacketListenerImpl
</summary>

```diff
+ boolean lambda$isPlayerCollidingWithAnythingNew$2(Entity)
+ boolean lambda$isPlayerCollidingWithAnythingNew$3(VoxelShape,VoxelShape)
- boolean lambda$isPlayerCollidingWithAnythingNew$7(Entity)
- boolean lambda$isPlayerCollidingWithAnythingNew$8(VoxelShape,VoxelShape)
+ String lambda$send$4(Packet)
- String lambda$send$9(Packet)
- void filterTextPacket(List,Consumer)
- void filterTextPacket(Object,Consumer,BiFunction)
- void filterTextPacket(String,Consumer)
- void handleChat(String)
- void lambda$filterTextPacket$1(Consumer,Object)
- void lambda$filterTextPacket$2(Consumer,Optional)
- void lambda$filterTextPacket$3(Consumer,Object)
+ void lambda$handleCustomCommandSuggestions$1(ServerboundCommandSuggestionPacket,Suggestions)
- void lambda$handleCustomCommandSuggestions$4(ServerboundCommandSuggestionPacket,Suggestions)
- void lambda$handleEditBook$5(int,List)
- void lambda$handleEditBook$6(int,List)
- void lambda$handlePlaceRecipe$10(ServerboundPlaceRecipePacket,Recipe)
+ void lambda$handlePlaceRecipe$5(ServerboundPlaceRecipePacket,Recipe)
- void lambda$handleSignUpdate$11(ServerboundSignUpdatePacket,List)
- void signBook(String,List,int)
- void updateBookContents(List,int)
- void updateSignText(ServerboundSignUpdatePacket,List)
```

</details>
</details>