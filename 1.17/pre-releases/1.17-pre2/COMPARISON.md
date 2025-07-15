## Comparison with [1.17-pre1](https://github.com/PixiGeko/Minecraft-generated-data/tree/1.17-pre1)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Blocks](#blocks)
> - [Translations](#translations)
> - [File structure](#file-structure)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">1.17-pre1</th><th>1.17-pre2</th></tr><tr><td>World version</td><td><pre>2716</pre></td><td><pre>2718</pre></td></tr><tr><td>Protocol version</td><td><pre>1073741853</pre></td><td><pre>1073741854</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">1.17-pre1</th><th>1.17-pre2</th></tr><tr><td>com.github.oshi:oshi-core</td><td><pre>5.3.4</pre></td><td><pre>5.7.4</pre></td></tr><tr><td>net.java.dev.jna:jna-platform</td><td><pre>5.6.0</pre></td><td><pre>5.8.0</pre></td></tr><tr><td>net.java.dev.jna:jna</td><td><pre>5.6.0</pre></td><td><pre>5.8.0</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr></table>
</details>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
block
</summary>

```diff
- minecraft:azalea_leaves_flowers
+ minecraft:flowering_azalea_leaves
```

</details>
<details>
<summary>
item
</summary>

```diff
- minecraft:azalea_leaves_flowers
+ minecraft:flowering_azalea_leaves
```

</details>
</details>
<hr/>
<details><summary><b><ins>TAGS</ins></b><a name="tags"></a></summary>
<br/>
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
<hr/>
<details><summary><b><ins>BLOCKS</ins></b><a name="blocks"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
- azalea_leaves_flowers.json
+ flowering_azalea_leaves.json
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
- block.minecraft.azalea_leaves_flowers: Flowering Azalea Leaves
+ block.minecraft.flowering_azalea_leaves: Flowering Azalea Leaves
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>1.17-pre1</th><th>1.17-pre2</th></tr>
<tr><th align="left"><div style="width:290px">commands.debug.started</div></th><td>Started 10 second tick profiling (use '/debug stop' to stop early)</td><td>Started tick profiling</td></tr>
</table>
<br/>
</details>
</details>
<hr/>
<details><summary><b><ins>FILE STRUCTURE</ins></b><a name="file-structure"></a></summary>
<br/>
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
<hr/>
<details><summary><b><ins>MAPPINGS</ins></b><a name="mappings"></a></summary>
<br/>
<h2>Server<a name="server-mappings"></a></h2>
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
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
- XXX.client.gui.Font$StringRenderOutput
+ XXX.client.gui.Gui
- XXX.client.gui.Gui$HeartType
+ XXX.client.gui.GuiComponent
- XXX.client.gui.MapRenderer
+ XXX.client.gui.MapRenderer$MapInstance
- XXX.components.events.AbstractContainerEventHandler
+ XXX.components.events.ContainerEventHandler
- XXX.components.events.GuiEventListener
+ XXX.components.events.package-info
- XXX.components.spectator.package-info
+ XXX.components.spectator.SpectatorGui
+ XXX.components.toasts.AdvancementToast
+ XXX.components.toasts.package-info
- XXX.components.toasts.RecipeToast
+ XXX.components.toasts.SystemToast
- XXX.components.toasts.SystemToast$SystemToastIds
+ XXX.components.toasts.Toast
- XXX.components.toasts.Toast$Visibility
+ XXX.components.toasts.ToastComponent
- XXX.components.toasts.ToastComponent$ToastInstance
+ XXX.components.toasts.TutorialToast
- XXX.components.toasts.TutorialToast$Icons
+ XXX.font.glyphs.BakedGlyph
- XXX.font.glyphs.BakedGlyph$1
- XXX.gui.chat.ChatListener
+ XXX.gui.chat.NarratorChatListener
- XXX.gui.chat.OverlayChatListener
- XXX.gui.chat.package-info
+ XXX.gui.chat.StandardChatListener
+ XXX.gui.components.AbstractButton
- XXX.gui.components.AbstractOptionSliderButton
+ XXX.gui.components.AbstractSelectionList
- XXX.gui.components.AbstractSelectionList$Entry
+ XXX.gui.components.AbstractSelectionList$SelectionDirection
- XXX.gui.components.AbstractSelectionList$TrackedList
+ XXX.gui.components.AbstractSliderButton
- XXX.gui.components.AbstractWidget
+ XXX.gui.components.BossHealthOverlay
- XXX.gui.components.BossHealthOverlay$1
+ XXX.gui.components.Button
- XXX.gui.components.Button$OnPress
+ XXX.gui.components.Button$OnTooltip
- XXX.gui.components.ChatComponent
+ XXX.gui.components.Checkbox
- XXX.gui.components.CommandSuggestions
+ XXX.gui.components.CommandSuggestions$SuggestionsList
- XXX.gui.components.ComponentRenderUtils
+ XXX.gui.components.ContainerObjectSelectionList
- XXX.gui.components.ContainerObjectSelectionList$Entry
+ XXX.gui.components.CycleButton
- XXX.gui.components.CycleButton$Builder
+ XXX.gui.components.CycleButton$OnValueChange
- XXX.gui.components.CycleButton$TooltipSupplier
+ XXX.gui.components.CycleButton$ValueListSupplier
- XXX.gui.components.CycleButton$ValueListSupplier$1
+ XXX.gui.components.CycleButton$ValueListSupplier$2
- XXX.gui.components.DebugScreenOverlay
+ XXX.gui.components.DebugScreenOverlay$1
- XXX.gui.components.EditBox
+ XXX.gui.components.ImageButton
- XXX.gui.components.LerpingBossEvent
+ XXX.gui.components.LockIconButton
- XXX.gui.components.LockIconButton$Icon
+ XXX.gui.components.MultiLineLabel
- XXX.gui.components.MultiLineLabel$1
+ XXX.gui.components.MultiLineLabel$2
- XXX.gui.components.MultiLineLabel$TextWithWidth
+ XXX.gui.components.ObjectSelectionList
- XXX.gui.components.ObjectSelectionList$Entry
+ XXX.gui.components.OptionsList
- XXX.gui.components.OptionsList$Entry
- XXX.gui.components.package-info
+ XXX.gui.components.PlayerTabOverlay
- XXX.gui.components.PlayerTabOverlay$PlayerInfoComparator
+ XXX.gui.components.SliderButton
- XXX.gui.components.StateSwitchingButton
+ XXX.gui.components.SubtitleOverlay
- XXX.gui.components.SubtitleOverlay$Subtitle
+ XXX.gui.components.TooltipAccessor
- XXX.gui.components.VolumeSlider
+ XXX.gui.components.Widget
- XXX.gui.font.AllMissingGlyphProvider
+ XXX.gui.font.FontManager
- XXX.gui.font.FontManager$1
+ XXX.gui.font.FontSet
- XXX.gui.font.FontTexture
+ XXX.gui.font.FontTexture$Node
- XXX.gui.font.TextFieldHelper
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
<hr/>