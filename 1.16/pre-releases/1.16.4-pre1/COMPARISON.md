## Comparison with [1.16.3](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.16.3)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Translations](#translations)
> - [File structure](#file-structure)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">1.16.3</th><th>1.16.4-pre1</th></tr><tr><td>World version</td><td><pre>2580</pre></td><td><pre>2581</pre></td></tr><tr><td>Protocol version</td><td><pre>753</pre></td><td><pre>1073741825</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">1.16.3</th><th>1.16.4-pre1</th></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr></table>
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
<hr/>
<details><summary><b><ins>FILE STRUCTURE</ins></b><a name="file-structure"></a></summary>
<br/>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/textures/gui/social_interactions.png
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
- XXX.server.network.TextFilter
- XXX.server.network.TextFilterClient$1
- XXX.server.network.TextFilterClient$PlayerContext
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
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
- net.minecraft.BlockUtil
+ net.minecraft.BlockUtil$FoundRectangle
- net.minecraft.BlockUtil$IntBounds
+ net.minecraft.CharPredicate
- net.minecraft.ChatFormatting
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
- XXX.advancements.critereon.AbstractCriterionTriggerInstance
+ XXX.advancements.critereon.BeeNestDestroyedTrigger
- XXX.advancements.critereon.BeeNestDestroyedTrigger$TriggerInstance
+ XXX.advancements.critereon.BlockPredicate
- XXX.advancements.critereon.BlockPredicate$Builder
+ XXX.advancements.critereon.BredAnimalsTrigger
- XXX.advancements.critereon.BredAnimalsTrigger$TriggerInstance
+ XXX.advancements.critereon.BrewedPotionTrigger
- XXX.advancements.critereon.BrewedPotionTrigger$TriggerInstance
+ XXX.advancements.critereon.ChangeDimensionTrigger
- XXX.advancements.critereon.ChangeDimensionTrigger$TriggerInstance
+ XXX.advancements.critereon.ChanneledLightningTrigger
- XXX.advancements.critereon.ChanneledLightningTrigger$TriggerInstance
+ XXX.advancements.critereon.ConstructBeaconTrigger
- XXX.advancements.critereon.ConstructBeaconTrigger$TriggerInstance
+ XXX.advancements.critereon.ConsumeItemTrigger
- XXX.advancements.critereon.ConsumeItemTrigger$TriggerInstance
+ XXX.advancements.critereon.CuredZombieVillagerTrigger
- XXX.advancements.critereon.CuredZombieVillagerTrigger$TriggerInstance
+ XXX.advancements.critereon.DamagePredicate
- XXX.advancements.critereon.DamagePredicate$Builder
+ XXX.advancements.critereon.DamageSourcePredicate
- XXX.advancements.critereon.DamageSourcePredicate$Builder
+ XXX.advancements.critereon.DeserializationContext
- XXX.advancements.critereon.DistancePredicate
+ XXX.advancements.critereon.EffectsChangedTrigger
- XXX.advancements.critereon.EffectsChangedTrigger$TriggerInstance
+ XXX.advancements.critereon.EnchantedItemTrigger
- XXX.advancements.critereon.EnchantedItemTrigger$TriggerInstance
+ XXX.advancements.critereon.EnchantmentPredicate
- XXX.advancements.critereon.EnterBlockTrigger
+ XXX.advancements.critereon.EnterBlockTrigger$TriggerInstance
- XXX.advancements.critereon.EntityEquipmentPredicate
+ XXX.advancements.critereon.EntityEquipmentPredicate$Builder
- XXX.advancements.critereon.EntityFlagsPredicate
+ XXX.advancements.critereon.EntityFlagsPredicate$Builder
- XXX.advancements.critereon.EntityHurtPlayerTrigger
+ XXX.advancements.critereon.EntityHurtPlayerTrigger$TriggerInstance
- XXX.advancements.critereon.EntityPredicate
+ XXX.advancements.critereon.EntityPredicate$1
- XXX.advancements.critereon.EntityPredicate$Builder
+ XXX.advancements.critereon.EntityPredicate$Composite
- XXX.advancements.critereon.EntityTypePredicate
+ XXX.advancements.critereon.EntityTypePredicate$1
- XXX.advancements.critereon.EntityTypePredicate$TagPredicate
+ XXX.advancements.critereon.EntityTypePredicate$TypePredicate
- XXX.advancements.critereon.FilledBucketTrigger
+ XXX.advancements.critereon.FilledBucketTrigger$TriggerInstance
- XXX.advancements.critereon.FishingHookPredicate
+ XXX.advancements.critereon.FishingRodHookedTrigger
- XXX.advancements.critereon.FishingRodHookedTrigger$TriggerInstance
+ XXX.advancements.critereon.FluidPredicate
- XXX.advancements.critereon.FluidPredicate$Builder
+ XXX.advancements.critereon.ImpossibleTrigger
- XXX.advancements.critereon.ImpossibleTrigger$TriggerInstance
+ XXX.advancements.critereon.InventoryChangeTrigger
- XXX.advancements.critereon.InventoryChangeTrigger$TriggerInstance
+ XXX.advancements.critereon.ItemDurabilityTrigger
- XXX.advancements.critereon.ItemDurabilityTrigger$TriggerInstance
+ XXX.advancements.critereon.ItemPickedUpByEntityTrigger
- XXX.advancements.critereon.ItemPickedUpByEntityTrigger$TriggerInstance
+ XXX.advancements.critereon.ItemPredicate
- XXX.advancements.critereon.ItemPredicate$Builder
+ XXX.advancements.critereon.ItemUsedOnBlockTrigger
- XXX.advancements.critereon.ItemUsedOnBlockTrigger$TriggerInstance
+ XXX.advancements.critereon.KilledByCrossbowTrigger
- XXX.advancements.critereon.KilledByCrossbowTrigger$TriggerInstance
+ XXX.advancements.critereon.KilledTrigger
- XXX.advancements.critereon.KilledTrigger$TriggerInstance
+ XXX.advancements.critereon.LevitationTrigger
- XXX.advancements.critereon.LevitationTrigger$TriggerInstance
+ XXX.advancements.critereon.LightPredicate
- XXX.advancements.critereon.LightPredicate$1
+ XXX.advancements.critereon.LightPredicate$Builder
- XXX.advancements.critereon.LocationPredicate
+ XXX.advancements.critereon.LocationPredicate$Builder
- XXX.advancements.critereon.LocationTrigger
+ XXX.advancements.critereon.LocationTrigger$TriggerInstance
- XXX.advancements.critereon.LootTableTrigger
+ XXX.advancements.critereon.LootTableTrigger$TriggerInstance
- XXX.advancements.critereon.MinMaxBounds
+ XXX.advancements.critereon.MinMaxBounds$BoundsFactory
- XXX.advancements.critereon.MinMaxBounds$BoundsFromReaderFactory
+ XXX.advancements.critereon.MinMaxBounds$Floats
- XXX.advancements.critereon.MinMaxBounds$Ints
+ XXX.advancements.critereon.MobEffectsPredicate
- XXX.advancements.critereon.MobEffectsPredicate$MobEffectInstancePredicate
+ XXX.advancements.critereon.NbtPredicate
- XXX.advancements.critereon.NetherTravelTrigger
+ XXX.advancements.critereon.NetherTravelTrigger$TriggerInstance
+ XXX.advancements.critereon.package-info
- XXX.advancements.critereon.PlacedBlockTrigger
+ XXX.advancements.critereon.PlacedBlockTrigger$TriggerInstance
- XXX.advancements.critereon.PlayerHurtEntityTrigger
+ XXX.advancements.critereon.PlayerHurtEntityTrigger$TriggerInstance
- XXX.advancements.critereon.PlayerInteractTrigger
+ XXX.advancements.critereon.PlayerInteractTrigger$TriggerInstance
- XXX.advancements.critereon.PlayerPredicate
+ XXX.advancements.critereon.PlayerPredicate$1
- XXX.advancements.critereon.PlayerPredicate$AdvancementCriterionsPredicate
+ XXX.advancements.critereon.PlayerPredicate$AdvancementDonePredicate
- XXX.advancements.critereon.PlayerPredicate$AdvancementPredicate
+ XXX.advancements.critereon.PlayerPredicate$Builder
- XXX.advancements.critereon.RecipeUnlockedTrigger
+ XXX.advancements.critereon.RecipeUnlockedTrigger$TriggerInstance
- XXX.advancements.critereon.SerializationContext
+ XXX.advancements.critereon.ShotCrossbowTrigger
- XXX.advancements.critereon.ShotCrossbowTrigger$TriggerInstance
+ XXX.advancements.critereon.SimpleCriterionTrigger
- XXX.advancements.critereon.SlideDownBlockTrigger
+ XXX.advancements.critereon.SlideDownBlockTrigger$TriggerInstance
- XXX.advancements.critereon.StatePropertiesPredicate
+ XXX.advancements.critereon.StatePropertiesPredicate$1
- XXX.advancements.critereon.StatePropertiesPredicate$Builder
+ XXX.advancements.critereon.StatePropertiesPredicate$ExactPropertyMatcher
- XXX.advancements.critereon.StatePropertiesPredicate$PropertyMatcher
+ XXX.advancements.critereon.StatePropertiesPredicate$RangedPropertyMatcher
- XXX.advancements.critereon.SummonedEntityTrigger
+ XXX.advancements.critereon.SummonedEntityTrigger$TriggerInstance
- XXX.advancements.critereon.TameAnimalTrigger
+ XXX.advancements.critereon.TameAnimalTrigger$TriggerInstance
- XXX.advancements.critereon.TargetBlockTrigger
+ XXX.advancements.critereon.TargetBlockTrigger$TriggerInstance
- XXX.advancements.critereon.TickTrigger
+ XXX.advancements.critereon.TickTrigger$TriggerInstance
- XXX.advancements.critereon.TradeTrigger
+ XXX.advancements.critereon.TradeTrigger$TriggerInstance
- XXX.advancements.critereon.UsedEnderEyeTrigger
+ XXX.advancements.critereon.UsedEnderEyeTrigger$TriggerInstance
- XXX.advancements.critereon.UsedTotemTrigger
+ XXX.advancements.critereon.UsedTotemTrigger$TriggerInstance
- XXX.advancements.critereon.WrappedMinMaxBounds
- XXX.blaze3d.platform.GlStateManager$SourceFactor
+ XXX.blaze3d.platform.GlStateManager$StencilFunc
- XXX.blaze3d.platform.GlStateManager$StencilState
+ XXX.blaze3d.platform.GlStateManager$TexGen
- XXX.blaze3d.platform.GlStateManager$TexGenCoord
+ XXX.blaze3d.platform.GlStateManager$TexGenState
- XXX.blaze3d.platform.GlStateManager$TextureState
+ XXX.blaze3d.platform.GlStateManager$Viewport
- XXX.blaze3d.platform.GlUtil
+ XXX.blaze3d.platform.InputConstants
- XXX.blaze3d.platform.InputConstants$1
+ XXX.blaze3d.platform.InputConstants$Key
- XXX.blaze3d.platform.InputConstants$Type
+ XXX.blaze3d.platform.Lighting
- XXX.blaze3d.platform.MemoryTracker
+ XXX.blaze3d.platform.Monitor
- XXX.blaze3d.platform.MonitorCreator
+ XXX.blaze3d.platform.NativeImage
- XXX.blaze3d.platform.NativeImage$1
+ XXX.blaze3d.platform.NativeImage$Format
- XXX.blaze3d.platform.NativeImage$InternalGlFormat
+ XXX.blaze3d.platform.NativeImage$WriteCallback
- XXX.blaze3d.platform.PngInfo
+ XXX.blaze3d.platform.PngInfo$1
- XXX.blaze3d.platform.PngInfo$StbReader
+ XXX.blaze3d.platform.PngInfo$StbReaderBufferedChannel
- XXX.blaze3d.platform.PngInfo$StbReaderSeekableByteChannel
+ XXX.blaze3d.platform.ScreenManager
- XXX.blaze3d.platform.SnooperAccess
+ XXX.blaze3d.platform.TextureUtil
- XXX.blaze3d.platform.VideoMode
+ XXX.blaze3d.platform.Window
- XXX.blaze3d.platform.Window$1
+ XXX.blaze3d.platform.Window$WindowInitFailed
- XXX.blaze3d.platform.WindowEventHandler
+ XXX.blaze3d.shaders.AbstractUniform
- XXX.blaze3d.shaders.BlendMode
+ XXX.blaze3d.shaders.Effect
- XXX.blaze3d.shaders.Program
+ XXX.blaze3d.shaders.Program$Type
- XXX.blaze3d.shaders.ProgramManager
+ XXX.blaze3d.shaders.Uniform
- XXX.blaze3d.systems.RenderSystem
+ XXX.blaze3d.vertex.BufferBuilder
- XXX.blaze3d.vertex.BufferBuilder$1
+ XXX.blaze3d.vertex.BufferBuilder$DrawState
- XXX.blaze3d.vertex.BufferBuilder$State
+ XXX.blaze3d.vertex.BufferUploader
- XXX.blaze3d.vertex.BufferVertexConsumer
- XXX.blaze3d.vertex.DefaultedVertexConsumer
+ XXX.blaze3d.vertex.DefaultVertexFormat
+ XXX.blaze3d.vertex.PoseStack
- XXX.blaze3d.vertex.PoseStack$1
+ XXX.blaze3d.vertex.PoseStack$Pose
- XXX.blaze3d.vertex.SheetedDecalTextureGenerator
+ XXX.blaze3d.vertex.Tesselator
- XXX.blaze3d.vertex.VertexBuffer
+ XXX.blaze3d.vertex.VertexConsumer
- XXX.blaze3d.vertex.VertexFormat
+ XXX.blaze3d.vertex.VertexFormatElement
- XXX.blaze3d.vertex.VertexFormatElement$Type
+ XXX.blaze3d.vertex.VertexFormatElement$Usage
- XXX.blaze3d.vertex.VertexFormatElement$Usage$SetupState
+ XXX.blaze3d.vertex.VertexMultiConsumer
- XXX.blaze3d.vertex.VertexMultiConsumer$Double
+ XXX.client.gui.Font
- XXX.client.gui.Font$StringRenderOutput
+ XXX.client.gui.Gui
- XXX.client.gui.GuiComponent
+ XXX.client.gui.MapRenderer
- XXX.client.gui.MapRenderer$1
+ XXX.client.gui.MapRenderer$MapInstance
- XXX.client.gui.package-info
- XXX.client.tutorial.Tutorial$TimedToast
- XXX.color.block.BlockColor
+ XXX.color.block.BlockColors
- XXX.color.block.BlockTintCache
+ XXX.color.block.BlockTintCache$1
- XXX.color.block.BlockTintCache$LatestCacheInfo
+ XXX.color.block.package-info
- XXX.color.item.ItemColor
+ XXX.color.item.ItemColors
- XXX.color.item.package-info
- XXX.components.events.AbstractContainerEventHandler
+ XXX.components.events.ContainerEventHandler
- XXX.components.events.GuiEventListener
+ XXX.components.events.package-info
- XXX.components.spectator.package-info
+ XXX.components.spectator.SpectatorGui
+ XXX.components.toasts.AdvancementToast
- XXX.components.toasts.package-info
- XXX.components.toasts.RecipeToast
+ XXX.components.toasts.SystemToast
- XXX.components.toasts.SystemToast$SystemToastIds
+ XXX.components.toasts.Toast
- XXX.components.toasts.Toast$Visibility
+ XXX.components.toasts.ToastComponent
- XXX.components.toasts.ToastComponent$1
+ XXX.components.toasts.ToastComponent$ToastInstance
- XXX.components.toasts.TutorialToast
+ XXX.components.toasts.TutorialToast$Icons
+ XXX.font.glyphs.BakedGlyph
- XXX.font.glyphs.BakedGlyph$Effect
+ XXX.font.glyphs.EmptyGlyph
- XXX.font.glyphs.MissingGlyph
- XXX.font.glyphs.package-info
+ XXX.font.glyphs.WhiteGlyph
- XXX.font.providers.BitmapProvider
+ XXX.font.providers.BitmapProvider$1
- XXX.font.providers.BitmapProvider$Builder
+ XXX.font.providers.BitmapProvider$Glyph
- XXX.font.providers.GlyphProviderBuilder
+ XXX.font.providers.GlyphProviderBuilderType
- XXX.font.providers.LegacyUnicodeBitmapsProvider
+ XXX.font.providers.LegacyUnicodeBitmapsProvider$1
- XXX.font.providers.LegacyUnicodeBitmapsProvider$Builder
+ XXX.font.providers.LegacyUnicodeBitmapsProvider$Glyph
+ XXX.font.providers.package-info
- XXX.font.providers.TrueTypeGlyphProviderBuilder
- XXX.gui.chat.ChatListener
+ XXX.gui.chat.NarratorChatListener
- XXX.gui.chat.OverlayChatListener
- XXX.gui.chat.package-info
+ XXX.gui.chat.StandardChatListener
+ XXX.gui.components.AbstractButton
- XXX.gui.components.AbstractOptionSliderButton
+ XXX.gui.components.AbstractSelectionList
- XXX.gui.components.AbstractSelectionList$1
+ XXX.gui.components.AbstractSelectionList$Entry
- XXX.gui.components.AbstractSelectionList$SelectionDirection
+ XXX.gui.components.AbstractSelectionList$TrackedList
- XXX.gui.components.AbstractSliderButton
+ XXX.gui.components.AbstractWidget
- XXX.gui.components.BossHealthOverlay
+ XXX.gui.components.Button
- XXX.gui.components.Button$OnPress
+ XXX.gui.components.Button$OnTooltip
- XXX.gui.components.ChatComponent
+ XXX.gui.components.Checkbox
- XXX.gui.components.CommandSuggestions
+ XXX.gui.components.CommandSuggestions$1
- XXX.gui.components.CommandSuggestions$SuggestionsList
+ XXX.gui.components.ComponentRenderUtils
- XXX.gui.components.ContainerObjectSelectionList
+ XXX.gui.components.ContainerObjectSelectionList$Entry
- XXX.gui.components.DebugScreenOverlay
+ XXX.gui.components.DebugScreenOverlay$1
- XXX.gui.components.EditBox
+ XXX.gui.components.ImageButton
- XXX.gui.components.LerpingBossEvent
+ XXX.gui.components.LerpingBossEvent$1
- XXX.gui.components.LockIconButton
+ XXX.gui.components.LockIconButton$Icon
- XXX.gui.components.MultiLineLabel
+ XXX.gui.components.MultiLineLabel$1
- XXX.gui.components.MultiLineLabel$2
+ XXX.gui.components.MultiLineLabel$TextWithWidth
- XXX.gui.components.ObjectSelectionList
+ XXX.gui.components.ObjectSelectionList$Entry
- XXX.gui.components.OptionButton
+ XXX.gui.components.OptionsList
- XXX.gui.components.OptionsList$Entry
- XXX.gui.components.package-info
+ XXX.gui.components.PlayerTabOverlay
- XXX.gui.components.PlayerTabOverlay$1
+ XXX.gui.components.PlayerTabOverlay$PlayerInfoComparator
- XXX.gui.components.SliderButton
+ XXX.gui.components.StateSwitchingButton
- XXX.gui.components.SubtitleOverlay
+ XXX.gui.components.SubtitleOverlay$Subtitle
- XXX.gui.components.TickableWidget
+ XXX.gui.components.TooltipAccessor
- XXX.gui.components.VolumeSlider
+ XXX.gui.components.Widget
+ XXX.gui.font.AllMissingGlyphProvider
- XXX.gui.font.FontManager
+ XXX.gui.font.FontManager$1
- XXX.gui.font.FontSet
+ XXX.gui.font.FontTexture
- XXX.gui.font.FontTexture$1
+ XXX.gui.font.FontTexture$Node
+ XXX.gui.font.package-info
- XXX.gui.font.TextFieldHelper
+ XXX.gui.screens.AccessibilityOptionsScreen
- XXX.gui.screens.AlertScreen
+ XXX.gui.screens.BackupConfirmScreen
- XXX.gui.screens.BackupConfirmScreen$Listener
+ XXX.gui.screens.ChatOptionsScreen
- XXX.gui.screens.ChatScreen
+ XXX.gui.screens.ChatScreen$1
- XXX.gui.screens.ConfirmLinkScreen
+ XXX.gui.screens.ConfirmScreen
- XXX.gui.screens.ConnectScreen
+ XXX.gui.screens.ConnectScreen$1
- XXX.gui.screens.CreateBuffetWorldScreen
+ XXX.gui.screens.CreateBuffetWorldScreen$1
- XXX.gui.screens.CreateBuffetWorldScreen$BiomeList
+ XXX.gui.screens.CreateBuffetWorldScreen$BiomeList$Entry
- XXX.gui.screens.CreateFlatWorldScreen
+ XXX.gui.screens.CreateFlatWorldScreen$1
- XXX.gui.screens.CreateFlatWorldScreen$DetailsList
+ XXX.gui.screens.CreateFlatWorldScreen$DetailsList$Entry
- XXX.gui.screens.DatapackLoadFailureScreen
+ XXX.gui.screens.DeathScreen
- XXX.gui.screens.DemoIntroScreen
+ XXX.gui.screens.DirectJoinServerScreen
- XXX.gui.screens.DisconnectedScreen
+ XXX.gui.screens.EditServerScreen
- XXX.gui.screens.ErrorScreen
+ XXX.gui.screens.GenericDirtMessageScreen
- XXX.gui.screens.InBedChatScreen
+ XXX.gui.screens.LanguageSelectScreen
- XXX.gui.screens.LanguageSelectScreen$LanguageSelectionList
+ XXX.gui.screens.LanguageSelectScreen$LanguageSelectionList$Entry
- XXX.gui.screens.LevelLoadingScreen
+ XXX.gui.screens.LoadingOverlay
- XXX.gui.screens.LoadingOverlay$LogoTexture
+ XXX.gui.screens.MenuScreens
- XXX.gui.screens.MenuScreens$ScreenConstructor
+ XXX.gui.screens.MouseSettingsScreen
- XXX.gui.screens.OptionsScreen
+ XXX.gui.screens.OptionsSubScreen
- XXX.gui.screens.OutOfMemoryScreen
+ XXX.gui.screens.Overlay
- XXX.gui.screens.package-info
- XXX.gui.screens.PauseScreen
+ XXX.gui.screens.PopupScreen
- XXX.gui.screens.PopupScreen$ButtonOption
+ XXX.gui.screens.PresetFlatWorldScreen
- XXX.gui.screens.PresetFlatWorldScreen$PresetInfo
+ XXX.gui.screens.PresetFlatWorldScreen$PresetsList
- XXX.gui.screens.PresetFlatWorldScreen$PresetsList$Entry
+ XXX.gui.screens.ProgressScreen
- XXX.gui.screens.RealmsBackupInfoScreen
+ XXX.gui.screens.RealmsBackupInfoScreen$BackupInfoList
- XXX.gui.screens.RealmsBackupInfoScreen$BackupInfoListEntry
+ XXX.gui.screens.RealmsBackupScreen
- XXX.gui.screens.RealmsBackupScreen$1
+ XXX.gui.screens.RealmsBackupScreen$BackupObjectSelectionList
- XXX.gui.screens.RealmsBackupScreen$Entry
+ XXX.gui.screens.RealmsBrokenWorldScreen
- XXX.gui.screens.RealmsClientOutdatedScreen
+ XXX.gui.screens.RealmsConfigureWorldScreen
- XXX.gui.screens.RealmsConfigureWorldScreen$1
+ XXX.gui.screens.RealmsConfirmScreen
- XXX.gui.screens.RealmsCreateRealmScreen
+ XXX.gui.screens.RealmsDownloadLatestWorldScreen
- XXX.gui.screens.RealmsDownloadLatestWorldScreen$DownloadStatus
+ XXX.gui.screens.RealmsGenericErrorScreen
- XXX.gui.screens.RealmsInviteScreen
+ XXX.gui.screens.RealmsLongConfirmationScreen
- XXX.gui.screens.RealmsLongConfirmationScreen$Type
+ XXX.gui.screens.RealmsLongRunningMcoTaskScreen
- XXX.gui.screens.RealmsNotificationsScreen
+ XXX.gui.screens.RealmsNotificationsScreen$1
- XXX.gui.screens.RealmsParentalConsentScreen
+ XXX.gui.screens.RealmsPendingInvitesScreen
- XXX.gui.screens.RealmsPendingInvitesScreen$1
+ XXX.gui.screens.RealmsPendingInvitesScreen$2
- XXX.gui.screens.RealmsPendingInvitesScreen$3
+ XXX.gui.screens.RealmsPendingInvitesScreen$Entry
- XXX.gui.screens.RealmsPendingInvitesScreen$Entry$AcceptRowButton
+ XXX.gui.screens.RealmsPendingInvitesScreen$Entry$RejectRowButton
- XXX.gui.screens.RealmsPendingInvitesScreen$PendingInvitationSelectionList
+ XXX.gui.screens.RealmsPlayerScreen
- XXX.gui.screens.RealmsPlayerScreen$Entry
+ XXX.gui.screens.RealmsPlayerScreen$InvitedObjectSelectionList
- XXX.gui.screens.RealmsPlayerScreen$UserAction
+ XXX.gui.screens.RealmsResetNormalWorldScreen
- XXX.gui.screens.RealmsResetWorldScreen
+ XXX.gui.screens.RealmsResetWorldScreen$1
- XXX.gui.screens.RealmsResetWorldScreen$2
+ XXX.gui.screens.RealmsResetWorldScreen$FrameButton
- XXX.gui.screens.RealmsResetWorldScreen$ResetType
+ XXX.gui.screens.RealmsResetWorldScreen$ResetWorldInfo
- XXX.gui.screens.RealmsScreenWithCallback
+ XXX.gui.screens.RealmsSelectFileToUploadScreen
- XXX.gui.screens.RealmsSelectFileToUploadScreen$Entry
+ XXX.gui.screens.RealmsSelectFileToUploadScreen$WorldSelectionList
- XXX.gui.screens.RealmsSelectWorldTemplateScreen
+ XXX.gui.screens.RealmsSelectWorldTemplateScreen$1
- XXX.gui.screens.RealmsSelectWorldTemplateScreen$Entry
+ XXX.gui.screens.RealmsSelectWorldTemplateScreen$WorldTemplateObjectSelectionList
- XXX.gui.screens.RealmsSettingsScreen
+ XXX.gui.screens.RealmsSlotOptionsScreen
- XXX.gui.screens.RealmsSlotOptionsScreen$SettingsSlider
+ XXX.gui.screens.RealmsSubscriptionInfoScreen
- XXX.gui.screens.RealmsSubscriptionInfoScreen$1
+ XXX.gui.screens.RealmsTermsScreen
- XXX.gui.screens.RealmsUploadScreen
- XXX.gui.screens.ReceivingLevelScreen
+ XXX.gui.screens.Screen
- XXX.gui.screens.ShareToLanScreen
+ XXX.gui.screens.SimpleOptionsSubScreen
- XXX.gui.screens.SkinCustomizationScreen
+ XXX.gui.screens.SoundOptionsScreen
- XXX.gui.screens.TitleScreen
+ XXX.gui.screens.UploadResult
- XXX.gui.screens.UploadResult$1
+ XXX.gui.screens.UploadResult$Builder
+ XXX.gui.screens.VideoSettingsScreen
- XXX.gui.screens.WinScreen
+ XXX.minecraft.advancements.Advancement
- XXX.minecraft.advancements.Advancement$1
+ XXX.minecraft.advancements.Advancement$Builder
- XXX.minecraft.advancements.AdvancementList
+ XXX.minecraft.advancements.AdvancementList$Listener
- XXX.minecraft.advancements.AdvancementProgress
+ XXX.minecraft.advancements.AdvancementProgress$Serializer
- XXX.minecraft.advancements.AdvancementRewards
+ XXX.minecraft.advancements.AdvancementRewards$Builder
- XXX.minecraft.advancements.CriteriaTriggers
+ XXX.minecraft.advancements.Criterion
- XXX.minecraft.advancements.CriterionProgress
+ XXX.minecraft.advancements.CriterionTrigger
- XXX.minecraft.advancements.CriterionTrigger$Listener
+ XXX.minecraft.advancements.CriterionTriggerInstance
- XXX.minecraft.advancements.DisplayInfo
+ XXX.minecraft.advancements.FrameType
- XXX.minecraft.advancements.package-info
- XXX.minecraft.advancements.RequirementsStrategy
+ XXX.minecraft.advancements.TreeNodePosition
+ XXX.minecraft.client.AmbientOcclusionStatus
- XXX.minecraft.client.AttackIndicatorStatus
+ XXX.minecraft.client.BooleanOption
- XXX.minecraft.client.Camera
+ XXX.minecraft.client.CameraType
- XXX.minecraft.client.ClientBrandRetriever
+ XXX.minecraft.client.ClientRecipeBook
- XXX.minecraft.client.CloudStatus
+ XXX.minecraft.client.ComponentCollector
- XXX.minecraft.client.CycleOption
+ XXX.minecraft.client.DebugQueryHandler
- XXX.minecraft.client.FullscreenResolutionProgressOption
+ XXX.minecraft.client.Game
- XXX.minecraft.client.Game$Metrics
+ XXX.minecraft.client.GraphicsStatus
- XXX.minecraft.client.GraphicsStatus$1
+ XXX.minecraft.client.GuiMessage
- XXX.minecraft.client.HotbarManager
- XXX.minecraft.client.KeyboardHandler
+ XXX.minecraft.client.KeyboardHandler$1
+ XXX.minecraft.client.KeyMapping
- XXX.minecraft.client.LogaritmicProgressOption
+ XXX.minecraft.client.Minecraft
- XXX.minecraft.client.Minecraft$1
+ XXX.minecraft.client.Minecraft$ExperimentalDialogType
- XXX.minecraft.client.Minecraft$ServerStem
+ XXX.minecraft.client.MouseHandler
- XXX.minecraft.client.NarratorStatus
+ XXX.minecraft.client.Option
- XXX.minecraft.client.Option$1
+ XXX.minecraft.client.Options
- XXX.minecraft.client.Options$1
+ XXX.minecraft.client.Options$2
- XXX.minecraft.client.ParticleStatus
+ XXX.minecraft.client.ProgressOption
- XXX.minecraft.client.RecipeBookCategories
+ XXX.minecraft.client.RecipeBookCategories$1
- XXX.minecraft.client.Screenshot
+ XXX.minecraft.client.Session
- XXX.minecraft.client.StringSplitter
+ XXX.minecraft.client.StringSplitter$1
- XXX.minecraft.client.StringSplitter$FlatComponents
+ XXX.minecraft.client.StringSplitter$LineBreakFinder
- XXX.minecraft.client.StringSplitter$LineComponent
+ XXX.minecraft.client.StringSplitter$LinePosConsumer
- XXX.minecraft.client.StringSplitter$WidthLimitedCharSink
+ XXX.minecraft.client.StringSplitter$WidthProvider
- XXX.minecraft.client.Timer
+ XXX.minecraft.client.ToggleKeyMapping
- XXX.minecraft.client.User
+ XXX.minecraft.client.User$Type
+ XXX.mojang.math.Matrix3f
- XXX.mojang.math.Matrix4f
+ XXX.mojang.math.OctahedralGroup
- XXX.mojang.math.OctahedralGroup$1
+ XXX.mojang.math.Quaternion
- XXX.mojang.math.SymmetricGroup3
+ XXX.mojang.math.Transformation
- XXX.mojang.math.Vector3d
+ XXX.mojang.math.Vector3f
- XXX.mojang.math.Vector4f
+ XXX.mojang.realmsclient.KeyCombo
- XXX.mojang.realmsclient.RealmsMainScreen
+ XXX.mojang.realmsclient.RealmsMainScreen$1
- XXX.mojang.realmsclient.RealmsMainScreen$2
+ XXX.mojang.realmsclient.RealmsMainScreen$3
- XXX.mojang.realmsclient.RealmsMainScreen$4
+ XXX.mojang.realmsclient.RealmsMainScreen$5
- XXX.mojang.realmsclient.RealmsMainScreen$CloseButton
+ XXX.mojang.realmsclient.RealmsMainScreen$Entry
- XXX.mojang.realmsclient.RealmsMainScreen$HoveredElement
+ XXX.mojang.realmsclient.RealmsMainScreen$NewsButton
- XXX.mojang.realmsclient.RealmsMainScreen$PendingInvitesButton
+ XXX.mojang.realmsclient.RealmsMainScreen$RealmSelectionList
- XXX.mojang.realmsclient.RealmsMainScreen$ServerEntry
+ XXX.mojang.realmsclient.RealmsMainScreen$ShowPopupButton
- XXX.mojang.realmsclient.RealmsMainScreen$TrialEntry
+ XXX.mojang.realmsclient.Unit
- XXX.realmsclient.client.FileDownload
+ XXX.realmsclient.client.FileDownload$1
- XXX.realmsclient.client.FileDownload$DownloadCountingOutputStream
+ XXX.realmsclient.client.FileDownload$ProgressListener
- XXX.realmsclient.client.FileDownload$ResourcePackProgressListener
+ XXX.realmsclient.client.FileUpload
- XXX.realmsclient.client.FileUpload$CustomInputStreamEntity
+ XXX.realmsclient.client.Ping
- XXX.realmsclient.client.Ping$Region
+ XXX.realmsclient.client.RealmsClient
- XXX.realmsclient.client.RealmsClient$CompatibleVersionResponse
+ XXX.realmsclient.client.RealmsClient$Environment
- XXX.realmsclient.client.RealmsClientConfig
+ XXX.realmsclient.client.RealmsError
- XXX.realmsclient.client.Request
+ XXX.realmsclient.client.Request$Delete
- XXX.realmsclient.client.Request$Get
+ XXX.realmsclient.client.Request$Post
- XXX.realmsclient.client.Request$Put
+ XXX.realmsclient.client.UploadStatus
- XXX.realmsclient.dto.Backup
+ XXX.realmsclient.dto.BackupList
- XXX.realmsclient.dto.GuardedSerializer
+ XXX.realmsclient.dto.Ops
- XXX.realmsclient.dto.PendingInvite
+ XXX.realmsclient.dto.PendingInvitesList
- XXX.realmsclient.dto.PingResult
+ XXX.realmsclient.dto.PlayerInfo
- XXX.realmsclient.dto.RealmsDescriptionDto
+ XXX.realmsclient.dto.RealmsNews
- XXX.realmsclient.dto.RealmsServer
+ XXX.realmsclient.dto.RealmsServer$McoServerComparator
- XXX.realmsclient.dto.RealmsServer$State
+ XXX.realmsclient.dto.RealmsServer$WorldType
- XXX.realmsclient.dto.RealmsServerAddress
+ XXX.realmsclient.dto.RealmsServerList
- XXX.realmsclient.dto.RealmsServerPing
+ XXX.realmsclient.dto.RealmsServerPlayerList
- XXX.realmsclient.dto.RealmsServerPlayerLists
+ XXX.realmsclient.dto.RealmsWorldOptions
- XXX.realmsclient.dto.RealmsWorldResetDto
+ XXX.realmsclient.dto.ReflectionBasedSerialization
- XXX.realmsclient.dto.RegionPingResult
+ XXX.realmsclient.dto.Subscription
- XXX.realmsclient.dto.Subscription$SubscriptionType
+ XXX.realmsclient.dto.UploadInfo
- XXX.realmsclient.dto.ValueObject
+ XXX.realmsclient.dto.WorldDownload
- XXX.realmsclient.dto.WorldTemplate
+ XXX.realmsclient.dto.WorldTemplate$WorldTemplateType
- XXX.realmsclient.dto.WorldTemplatePaginatedList
+ XXX.realmsclient.exception.RealmsDefaultUncaughtExceptionHandler
- XXX.realmsclient.exception.RealmsHttpException
+ XXX.realmsclient.exception.RealmsServiceException
- XXX.realmsclient.exception.RetryCallException
+ XXX.realmsclient.gui.ErrorCallback
- XXX.realmsclient.gui.RealmsDataFetcher
+ XXX.realmsclient.gui.RealmsDataFetcher$1
- XXX.realmsclient.gui.RealmsDataFetcher$LiveStatsTask
+ XXX.realmsclient.gui.RealmsDataFetcher$PendingInviteUpdateTask
- XXX.realmsclient.gui.RealmsDataFetcher$ServerListUpdateTask
+ XXX.realmsclient.gui.RealmsDataFetcher$Task
- XXX.realmsclient.gui.RealmsDataFetcher$TrialAvailabilityTask
+ XXX.realmsclient.gui.RealmsDataFetcher$UnreadNewsTask
- XXX.realmsclient.gui.RealmsWorldSlotButton
+ XXX.realmsclient.gui.RealmsWorldSlotButton$Action
- XXX.realmsclient.gui.RealmsWorldSlotButton$State
+ XXX.realmsclient.gui.RowButton
- XXX.realmsclient.util.JsonUtils
+ XXX.realmsclient.util.RealmsPersistence
- XXX.realmsclient.util.RealmsPersistence$RealmsPersistenceData
+ XXX.realmsclient.util.RealmsTextureManager
- XXX.realmsclient.util.RealmsTextureManager$1
+ XXX.realmsclient.util.RealmsTextureManager$RealmsTexture
- XXX.realmsclient.util.RealmsUtil
+ XXX.realmsclient.util.RealmsUtil$1
- XXX.realmsclient.util.SkinProcessor
+ XXX.realmsclient.util.TextRenderingUtils
- XXX.realmsclient.util.TextRenderingUtils$Line
+ XXX.realmsclient.util.TextRenderingUtils$LineSegment
- XXX.realmsclient.util.UploadTokenCache
+ XXX.screens.achievement.package-info
+ XXX.screens.achievement.StatsScreen
- XXX.screens.achievement.StatsScreen$1
+ XXX.screens.achievement.StatsScreen$GeneralStatisticsList
- XXX.screens.achievement.StatsScreen$GeneralStatisticsList$Entry
+ XXX.screens.achievement.StatsScreen$ItemStatisticsList
- XXX.screens.achievement.StatsScreen$ItemStatisticsList$ItemComparator
+ XXX.screens.achievement.StatsScreen$ItemStatisticsList$ItemRow
- XXX.screens.achievement.StatsScreen$MobsStatisticsList
+ XXX.screens.achievement.StatsScreen$MobsStatisticsList$MobRow
- XXX.screens.achievement.StatsUpdateListener
+ XXX.screens.advancements.AdvancementsScreen
- XXX.screens.advancements.AdvancementTab
+ XXX.screens.advancements.AdvancementTabType
- XXX.screens.advancements.AdvancementTabType$1
+ XXX.screens.advancements.AdvancementWidget
- XXX.screens.advancements.AdvancementWidgetType
- XXX.screens.advancements.package-info
+ XXX.screens.controls.ControlList
- XXX.screens.controls.ControlList$1
+ XXX.screens.controls.ControlList$CategoryEntry
- XXX.screens.controls.ControlList$Entry
+ XXX.screens.controls.ControlList$KeyEntry
- XXX.screens.controls.ControlList$KeyEntry$1
+ XXX.screens.controls.ControlList$KeyEntry$2
- XXX.screens.controls.ControlsScreen
+ XXX.screens.controls.package-info
- XXX.screens.debug.GameModeSwitcherScreen
+ XXX.screens.debug.GameModeSwitcherScreen$1
- XXX.screens.debug.GameModeSwitcherScreen$GameModeIcon
+ XXX.screens.debug.GameModeSwitcherScreen$GameModeSlot
- XXX.screens.inventory.AbstractCommandBlockEditScreen
+ XXX.screens.inventory.AbstractCommandBlockEditScreen$1
- XXX.screens.inventory.AbstractContainerScreen
+ XXX.screens.inventory.AbstractFurnaceScreen
- XXX.screens.inventory.AnvilScreen
+ XXX.screens.inventory.BeaconScreen
- XXX.screens.inventory.BeaconScreen$1
+ XXX.screens.inventory.BeaconScreen$BeaconCancelButton
- XXX.screens.inventory.BeaconScreen$BeaconConfirmButton
+ XXX.screens.inventory.BeaconScreen$BeaconPowerButton
- XXX.screens.inventory.BeaconScreen$BeaconScreenButton
+ XXX.screens.inventory.BeaconScreen$BeaconSpriteScreenButton
- XXX.screens.inventory.BlastFurnaceScreen
+ XXX.screens.inventory.BookEditScreen
- XXX.screens.inventory.BookEditScreen$DisplayCache
+ XXX.screens.inventory.BookEditScreen$LineInfo
- XXX.screens.inventory.BookEditScreen$Pos2i
+ XXX.screens.inventory.BookViewScreen
- XXX.screens.inventory.BookViewScreen$1
+ XXX.screens.inventory.BookViewScreen$BookAccess
- XXX.screens.inventory.BookViewScreen$WritableBookAccess
+ XXX.screens.inventory.BookViewScreen$WrittenBookAccess
- XXX.screens.inventory.BrewingStandScreen
+ XXX.screens.inventory.CartographyTableScreen
- XXX.screens.inventory.CommandBlockEditScreen
+ XXX.screens.inventory.CommandBlockEditScreen$1
- XXX.screens.inventory.ContainerScreen
+ XXX.screens.inventory.CraftingScreen
- XXX.screens.inventory.CreativeInventoryListener
+ XXX.screens.inventory.CreativeModeInventoryScreen
- XXX.screens.inventory.CreativeModeInventoryScreen$CustomCreativeSlot
+ XXX.screens.inventory.CreativeModeInventoryScreen$ItemPickerMenu
- XXX.screens.inventory.CreativeModeInventoryScreen$SlotWrapper
+ XXX.screens.inventory.DispenserScreen
- XXX.screens.inventory.EffectRenderingInventoryScreen
+ XXX.screens.inventory.EnchantmentNames
- XXX.screens.inventory.EnchantmentScreen
+ XXX.screens.inventory.FurnaceScreen
- XXX.screens.inventory.GrindstoneScreen
+ XXX.screens.inventory.HopperScreen
- XXX.screens.inventory.HorseInventoryScreen
+ XXX.screens.inventory.InventoryScreen
- XXX.screens.inventory.ItemCombinerScreen
+ XXX.screens.inventory.JigsawBlockEditScreen
- XXX.screens.inventory.JigsawBlockEditScreen$1
+ XXX.screens.inventory.JigsawBlockEditScreen$2
- XXX.screens.inventory.LecternScreen
+ XXX.screens.inventory.LecternScreen$1
- XXX.screens.inventory.LoomScreen
+ XXX.screens.inventory.MenuAccess
- XXX.screens.inventory.MerchantScreen
+ XXX.screens.inventory.MerchantScreen$TradeOfferButton
- XXX.screens.inventory.MinecartCommandBlockEditScreen
- XXX.screens.inventory.package-info
+ XXX.screens.inventory.PageButton
- XXX.screens.inventory.ShulkerBoxScreen
+ XXX.screens.inventory.SignEditScreen
- XXX.screens.inventory.SmithingScreen
+ XXX.screens.inventory.SmokerScreen
- XXX.screens.inventory.StonecutterScreen
+ XXX.screens.inventory.StructureBlockEditScreen
- XXX.screens.inventory.StructureBlockEditScreen$1
+ XXX.screens.inventory.StructureBlockEditScreen$2
+ XXX.screens.mco.package-info
- XXX.screens.multiplayer.JoinMultiplayerScreen
+ XXX.screens.multiplayer.package-info
+ XXX.screens.multiplayer.SafetyScreen
- XXX.screens.multiplayer.ServerSelectionList
+ XXX.screens.multiplayer.ServerSelectionList$Entry
- XXX.screens.multiplayer.ServerSelectionList$LANHeader
+ XXX.screens.multiplayer.ServerSelectionList$NetworkServerEntry
- XXX.screens.multiplayer.ServerSelectionList$OnlineServerEntry
- XXX.screens.packs.package-info
+ XXX.screens.packs.PackSelectionModel
- XXX.screens.packs.PackSelectionModel$Entry
+ XXX.screens.packs.PackSelectionModel$EntryBase
- XXX.screens.packs.PackSelectionModel$SelectedPackEntry
+ XXX.screens.packs.PackSelectionModel$UnselectedPackEntry
- XXX.screens.packs.PackSelectionScreen
+ XXX.screens.packs.PackSelectionScreen$Watcher
- XXX.screens.packs.TransferableSelectionList
+ XXX.screens.packs.TransferableSelectionList$PackEntry
+ XXX.screens.recipebook.AbstractFurnaceRecipeBookComponent
- XXX.screens.recipebook.BlastingRecipeBookComponent
+ XXX.screens.recipebook.GhostRecipe
- XXX.screens.recipebook.GhostRecipe$GhostIngredient
+ XXX.screens.recipebook.OverlayRecipeComponent
- XXX.screens.recipebook.OverlayRecipeComponent$OverlayRecipeButton
+ XXX.screens.recipebook.OverlayRecipeComponent$OverlayRecipeButton$Pos
- XXX.screens.recipebook.OverlayRecipeComponent$OverlaySmeltingRecipeButton
- XXX.screens.recipebook.package-info
+ XXX.screens.recipebook.RecipeBookComponent
- XXX.screens.recipebook.RecipeBookPage
+ XXX.screens.recipebook.RecipeBookTabButton
- XXX.screens.recipebook.RecipeButton
+ XXX.screens.recipebook.RecipeCollection
- XXX.screens.recipebook.RecipeShownListener
+ XXX.screens.recipebook.RecipeUpdateListener
- XXX.screens.recipebook.SmeltingRecipeBookComponent
+ XXX.screens.recipebook.SmokingRecipeBookComponent
- XXX.screens.social.PlayerSocialManager
- XXX.screens.social.SocialInteractionsScreen
- XXX.screens.social.SocialInteractionsScreen$Page
- XXX.server.network.TextFilter
- XXX.server.network.TextFilterClient$1
- XXX.server.network.TextFilterClient$PlayerContext
+ XXX.util.task.CloseServerTask
- XXX.util.task.ConnectTask
+ XXX.util.task.DownloadTask
- XXX.util.task.GetServerDetailsTask
+ XXX.util.task.LongRunningTask
- XXX.util.task.OpenServerTask
+ XXX.util.task.ResettingWorldTask
- XXX.util.task.RestoreTask
+ XXX.util.task.SwitchMinigameTask
- XXX.util.task.SwitchSlotTask
+ XXX.util.task.WorldCreationTask
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
<hr/>