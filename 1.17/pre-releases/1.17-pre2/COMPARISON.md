## Comparison with [1.17-pre1](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.17-pre1)

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
<table><tr><th></th><th align="left">1.17-pre1</th><th>1.17-pre2</th></tr><tr><td>World version</td><td><code>2716</code></td><td><code>2718</code></td></tr><tr><td>Protocol version</td><td><code>1073741853</code></td><td><code>1073741854</code></td></tr></table>
</details>
<details><summary>Registries</summary>
<details>
<summary>
block.txt
</summary>

```diff
- minecraft:azalea_leaves_flowers
+ minecraft:flowering_azalea_leaves
```

</details>










<details>
<summary>
item.txt
</summary>

```diff
- minecraft:azalea_leaves_flowers
+ minecraft:flowering_azalea_leaves
```

</details>
</details>
<details><summary>Tags</summary>
<details>
<summary>
all_blocks_with_drop.json
</summary>

```diff
- minecraft:azalea_leaves_flowers
+ minecraft:flowering_azalea_leaves
```

</details>






<details>
<summary>
universal_tags/block.json
</summary>

```diff
- minecraft:azalea_leaves_flowers
+ minecraft:flowering_azalea_leaves
```

</details>










<details>
<summary>
universal_tags/item.json
</summary>

```diff
- minecraft:azalea_leaves_flowers
+ minecraft:flowering_azalea_leaves
```

</details>
</details>
<details><summary>Translations</summary>
<details>
<summary>
Keys
</summary>

```diff
- block.minecraft.azalea_leaves_flowers: Flowering Azalea Leaves
+ block.minecraft.flowering_azalea_leaves: Flowering Azalea Leaves
```

</details>
<details>
<summary>
Changes
</summary>

```
commands.debug.started: Started 10 second tick profiling (use '/debug stop' to stop early)
```

</details>
</details>
<details><summary>File structure</summary>
<details>
<summary>
data
</summary>

```diff
- minecraft/loot_tables/blocks/azalea_leaves_flowers.json
+ minecraft/loot_tables/blocks/flowering_azalea_leaves.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
- minecraft/blockstates/azalea_leaves_flowers.json
+ minecraft/blockstates/flowering_azalea_leaves.json
- minecraft/models/block/azalea_leaves_flowers.json
+ minecraft/models/block/flowering_azalea_leaves.json
- minecraft/models/item/azalea_leaves_flowers.json
+ minecraft/models/item/flowering_azalea_leaves.json
- minecraft/textures/block/azalea_leaves_flowers.png
+ minecraft/textures/block/flowering_azalea_leaves.png
```

</details>
</details>
<details><summary>Mappings</summary>
<h2>Server</h2>

<details>
<summary>
Changes
</summary>

```
XXX.data.worldgen.Features$States +1P -1P
```
```
XXX.metrics.profiling.ServerMetricsSamplersProvider +1M | +1P
```
```
XXX.entity.projectile.LargeFireball +1M -1M
```
```
XXX.level.block.Blocks +1P -1P
```
```
XXX.levelgen.structure.NetherFossilFeature$FeatureStart$1 +1M -1M | +1P -1P
```
```
XXX.saveddata.maps.MapDecoration$Type +3M -2M | +1P
```

</details>


















































































































































































































































































































































































































































































































































































































































































































































































































































<details>
<summary>
net.minecraft.util.profiling.metrics.profiling.ServerMetricsSamplersProvider
</summary>

```diff
- void <clinit>()
```

</details>







































































































































































































































































































































































































<details>
<summary>
net.minecraft.world.entity.projectile.LargeFireball
</summary>

```diff
- void <init>(Level,LivingEntity,double,double,double,int)
+ void <init>(Level,LivingEntity,double,double,double)
```

</details>




































































































































































































































































































































































































































































































































































































































































































































































<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherFossilFeature$FeatureStart$1
</summary>

```diff
- void <init>(NetherFossilFeature$FeatureStart,ChunkGenerator)
+ void <init>(NetherFossilFeature$FeatureStart,LevelHeightAccessor)
```

</details>


































































































































<details>
<summary>
net.minecraft.world.level.saveddata.maps.MapDecoration$Type
</summary>

```diff
- boolean shouldTrackCount()
- void <init>(String,int,boolean,boolean)
- void <init>(String,int,boolean,int,boolean)
+ void <init>(String,int,boolean,int)
+ void <init>(String,int,boolean)
```

</details>






























































































































































<h2>Client</h2>
<details>
<summary>
Classes
</summary>

```diff
- net.minecraft.client.gui.chat.ChatListener
+ net.minecraft.client.gui.chat.NarratorChatListener
- net.minecraft.client.gui.chat.OverlayChatListener
- net.minecraft.client.gui.chat.package-info
+ net.minecraft.client.gui.chat.StandardChatListener
+ net.minecraft.client.gui.components.AbstractButton
- net.minecraft.client.gui.components.AbstractOptionSliderButton
+ net.minecraft.client.gui.components.AbstractSelectionList
- net.minecraft.client.gui.components.AbstractSelectionList$Entry
+ net.minecraft.client.gui.components.AbstractSelectionList$SelectionDirection
- net.minecraft.client.gui.components.AbstractSelectionList$TrackedList
+ net.minecraft.client.gui.components.AbstractSliderButton
- net.minecraft.client.gui.components.AbstractWidget
+ net.minecraft.client.gui.components.BossHealthOverlay
- net.minecraft.client.gui.components.BossHealthOverlay$1
+ net.minecraft.client.gui.components.Button
- net.minecraft.client.gui.components.Button$OnPress
+ net.minecraft.client.gui.components.Button$OnTooltip
- net.minecraft.client.gui.components.ChatComponent
+ net.minecraft.client.gui.components.Checkbox
- net.minecraft.client.gui.components.CommandSuggestions
+ net.minecraft.client.gui.components.CommandSuggestions$SuggestionsList
- net.minecraft.client.gui.components.ComponentRenderUtils
+ net.minecraft.client.gui.components.ContainerObjectSelectionList
- net.minecraft.client.gui.components.ContainerObjectSelectionList$Entry
+ net.minecraft.client.gui.components.CycleButton
- net.minecraft.client.gui.components.CycleButton$Builder
+ net.minecraft.client.gui.components.CycleButton$OnValueChange
- net.minecraft.client.gui.components.CycleButton$TooltipSupplier
+ net.minecraft.client.gui.components.CycleButton$ValueListSupplier
- net.minecraft.client.gui.components.CycleButton$ValueListSupplier$1
+ net.minecraft.client.gui.components.CycleButton$ValueListSupplier$2
- net.minecraft.client.gui.components.DebugScreenOverlay
+ net.minecraft.client.gui.components.DebugScreenOverlay$1
- net.minecraft.client.gui.components.EditBox
- net.minecraft.client.gui.components.events.AbstractContainerEventHandler
+ net.minecraft.client.gui.components.events.ContainerEventHandler
- net.minecraft.client.gui.components.events.GuiEventListener
+ net.minecraft.client.gui.components.events.package-info
+ net.minecraft.client.gui.components.ImageButton
- net.minecraft.client.gui.components.LerpingBossEvent
+ net.minecraft.client.gui.components.LockIconButton
- net.minecraft.client.gui.components.LockIconButton$Icon
+ net.minecraft.client.gui.components.MultiLineLabel
- net.minecraft.client.gui.components.MultiLineLabel$1
+ net.minecraft.client.gui.components.MultiLineLabel$2
- net.minecraft.client.gui.components.MultiLineLabel$TextWithWidth
+ net.minecraft.client.gui.components.ObjectSelectionList
- net.minecraft.client.gui.components.ObjectSelectionList$Entry
+ net.minecraft.client.gui.components.OptionsList
- net.minecraft.client.gui.components.OptionsList$Entry
- net.minecraft.client.gui.components.package-info
+ net.minecraft.client.gui.components.PlayerTabOverlay
- net.minecraft.client.gui.components.PlayerTabOverlay$PlayerInfoComparator
+ net.minecraft.client.gui.components.SliderButton
- net.minecraft.client.gui.components.spectator.package-info
+ net.minecraft.client.gui.components.spectator.SpectatorGui
- net.minecraft.client.gui.components.StateSwitchingButton
+ net.minecraft.client.gui.components.SubtitleOverlay
- net.minecraft.client.gui.components.SubtitleOverlay$Subtitle
+ net.minecraft.client.gui.components.toasts.AdvancementToast
+ net.minecraft.client.gui.components.toasts.package-info
- net.minecraft.client.gui.components.toasts.RecipeToast
+ net.minecraft.client.gui.components.toasts.SystemToast
- net.minecraft.client.gui.components.toasts.SystemToast$SystemToastIds
+ net.minecraft.client.gui.components.toasts.Toast
- net.minecraft.client.gui.components.toasts.Toast$Visibility
+ net.minecraft.client.gui.components.toasts.ToastComponent
- net.minecraft.client.gui.components.toasts.ToastComponent$ToastInstance
+ net.minecraft.client.gui.components.toasts.TutorialToast
- net.minecraft.client.gui.components.toasts.TutorialToast$Icons
+ net.minecraft.client.gui.components.TooltipAccessor
- net.minecraft.client.gui.components.VolumeSlider
+ net.minecraft.client.gui.components.Widget
- net.minecraft.client.gui.font.AllMissingGlyphProvider
+ net.minecraft.client.gui.font.FontManager
- net.minecraft.client.gui.font.FontManager$1
+ net.minecraft.client.gui.font.FontSet
- net.minecraft.client.gui.font.FontTexture
+ net.minecraft.client.gui.font.FontTexture$Node
+ net.minecraft.client.gui.font.glyphs.BakedGlyph
- net.minecraft.client.gui.font.glyphs.BakedGlyph$1
- net.minecraft.client.gui.font.TextFieldHelper
- net.minecraft.client.gui.Font$StringRenderOutput
+ net.minecraft.client.gui.Gui
- net.minecraft.client.gui.Gui$HeartType
+ net.minecraft.client.gui.GuiComponent
- net.minecraft.client.gui.MapRenderer
+ net.minecraft.client.gui.MapRenderer$MapInstance
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.client.gui.Font -1P
```
```
XXX.client.renderer.RenderType +4M | +2P
```
```
XXX.metrics.profiling.ServerMetricsSamplersProvider +1M | +1P
```
```
XXX.entity.projectile.LargeFireball +1M -1M
```
```
XXX.level.block.Blocks +1P -1P
```
```
XXX.levelgen.structure.NetherFossilFeature$FeatureStart$1 +1M -1M | +1P -1P
```
```
XXX.saveddata.maps.MapDecoration$Type +3M -2M | +1P
```

</details>

















































































































































































































































































































































































































































































































































































































































<details>
<summary>
net.minecraft.client.renderer.RenderType
</summary>

```diff
- RenderType lambda$static$20(ResourceLocation)
- RenderType lambda$static$21(ResourceLocation)
- RenderType textIntensityPolygonOffset(ResourceLocation)
- RenderType textPolygonOffset(ResourceLocation)
```

</details>

































































































































































































































































































































































































































































































































































































































































































































































































































































































































































































<details>
<summary>
net.minecraft.util.profiling.metrics.profiling.ServerMetricsSamplersProvider
</summary>

```diff
- void <clinit>()
```

</details>







































































































































































































































































































































































































<details>
<summary>
net.minecraft.world.entity.projectile.LargeFireball
</summary>

```diff
- void <init>(Level,LivingEntity,double,double,double,int)
+ void <init>(Level,LivingEntity,double,double,double)
```

</details>




































































































































































































































































































































































































































































































































































































































































































































































<details>
<summary>
net.minecraft.world.level.levelgen.structure.NetherFossilFeature$FeatureStart$1
</summary>

```diff
- void <init>(NetherFossilFeature$FeatureStart,ChunkGenerator)
+ void <init>(NetherFossilFeature$FeatureStart,LevelHeightAccessor)
```

</details>


































































































































<details>
<summary>
net.minecraft.world.level.saveddata.maps.MapDecoration$Type
</summary>

```diff
- boolean shouldTrackCount()
- void <init>(String,int,boolean,boolean)
- void <init>(String,int,boolean,int,boolean)
+ void <init>(String,int,boolean,int)
+ void <init>(String,int,boolean)
```

</details>
</details>