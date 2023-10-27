<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 1.17-pre2 ⌋<br/><img width="0" height="0"></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
:warning: This repository is not official, approved, endorsed, associated or connected with Mojang :warning:
<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>1.17-pre2</td></tr>
<tr><th>Type</th><td>pre-releases</td></tr>
<tr><th>Release time</th><td>2021-05-31T15:54:05+00:00</td></tr>
<tr><th>SHA1</th><td>76f54994dc32298f0743e2a9031ad1bba04cf753</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/76f54994dc32298f0743e2a9031ad1bba04cf753/1.17-pre2.json">https://piston-meta.mojang.com/v1/packages/76f54994dc32298f0743e2a9031ad1bba04cf753/1.17-pre2.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/f425401a00adf0112fde624ee80c66333530f8a1/1.17.json">https://piston-meta.mojang.com/v1/packages/f425401a00adf0112fde624ee80c66333530f8a1/1.17.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/d8756c67ce3b3fe20d0510afb3e22fa16310b2e6/server.jar">https://piston-data.mojang.com/v1/objects/d8756c67ce3b3fe20d0510afb3e22fa16310b2e6/server.jar</a></td></tr>
<tr><th>Server mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/f79c9cad034152d13c8fab69c441eb06138aacc6/server.txt">https://piston-data.mojang.com/v1/objects/f79c9cad034152d13c8fab69c441eb06138aacc6/server.txt</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/72ebf53f36151a9c2657dca80f72a97c0917d3ce/client.jar">https://piston-data.mojang.com/v1/objects/72ebf53f36151a9c2657dca80f72a97c0917d3ce/client.jar</a></td></tr>
<tr><th>Client mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/c3fc5f17f6a63498078cbcc72872e78c500120f6/client.txt">https://piston-data.mojang.com/v1/objects/c3fc5f17f6a63498078cbcc72872e78c500120f6/client.txt</a></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
<i>Go to the README.md file to make sure you see the full comparison</i>
<br/><img width="0" height="0"></td></tr>
</table></html>

<br/>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/1.17-pre1">1.17-pre1</a>

# Mappings

### Client




<details><summary>Classes</summary>

```diff
+ net.minecraft.client.gui.chat.ChatListener
- net.minecraft.client.gui.chat.NarratorChatListener
+ net.minecraft.client.gui.chat.OverlayChatListener
+ net.minecraft.client.gui.chat.package-info
- net.minecraft.client.gui.chat.StandardChatListener
- net.minecraft.client.gui.components.AbstractButton
+ net.minecraft.client.gui.components.AbstractOptionSliderButton
- net.minecraft.client.gui.components.AbstractSelectionList
+ net.minecraft.client.gui.components.AbstractSelectionList$Entry
- net.minecraft.client.gui.components.AbstractSelectionList$SelectionDirection
+ net.minecraft.client.gui.components.AbstractSelectionList$TrackedList
- net.minecraft.client.gui.components.AbstractSliderButton
+ net.minecraft.client.gui.components.AbstractWidget
- net.minecraft.client.gui.components.BossHealthOverlay
+ net.minecraft.client.gui.components.BossHealthOverlay$1
- net.minecraft.client.gui.components.Button
+ net.minecraft.client.gui.components.Button$OnPress
- net.minecraft.client.gui.components.Button$OnTooltip
+ net.minecraft.client.gui.components.ChatComponent
- net.minecraft.client.gui.components.Checkbox
+ net.minecraft.client.gui.components.CommandSuggestions
- net.minecraft.client.gui.components.CommandSuggestions$SuggestionsList
+ net.minecraft.client.gui.components.ComponentRenderUtils
- net.minecraft.client.gui.components.ContainerObjectSelectionList
+ net.minecraft.client.gui.components.ContainerObjectSelectionList$Entry
- net.minecraft.client.gui.components.CycleButton
+ net.minecraft.client.gui.components.CycleButton$Builder
- net.minecraft.client.gui.components.CycleButton$OnValueChange
+ net.minecraft.client.gui.components.CycleButton$TooltipSupplier
- net.minecraft.client.gui.components.CycleButton$ValueListSupplier
+ net.minecraft.client.gui.components.CycleButton$ValueListSupplier$1
- net.minecraft.client.gui.components.CycleButton$ValueListSupplier$2
+ net.minecraft.client.gui.components.DebugScreenOverlay
- net.minecraft.client.gui.components.DebugScreenOverlay$1
+ net.minecraft.client.gui.components.EditBox
+ net.minecraft.client.gui.components.events.AbstractContainerEventHandler
- net.minecraft.client.gui.components.events.ContainerEventHandler
+ net.minecraft.client.gui.components.events.GuiEventListener
- net.minecraft.client.gui.components.events.package-info
- net.minecraft.client.gui.components.ImageButton
+ net.minecraft.client.gui.components.LerpingBossEvent
- net.minecraft.client.gui.components.LockIconButton
+ net.minecraft.client.gui.components.LockIconButton$Icon
- net.minecraft.client.gui.components.MultiLineLabel
+ net.minecraft.client.gui.components.MultiLineLabel$1
- net.minecraft.client.gui.components.MultiLineLabel$2
+ net.minecraft.client.gui.components.MultiLineLabel$TextWithWidth
- net.minecraft.client.gui.components.ObjectSelectionList
+ net.minecraft.client.gui.components.ObjectSelectionList$Entry
- net.minecraft.client.gui.components.OptionsList
+ net.minecraft.client.gui.components.OptionsList$Entry
+ net.minecraft.client.gui.components.package-info
- net.minecraft.client.gui.components.PlayerTabOverlay
+ net.minecraft.client.gui.components.PlayerTabOverlay$PlayerInfoComparator
- net.minecraft.client.gui.components.SliderButton
+ net.minecraft.client.gui.components.spectator.package-info
- net.minecraft.client.gui.components.spectator.SpectatorGui
+ net.minecraft.client.gui.components.StateSwitchingButton
- net.minecraft.client.gui.components.SubtitleOverlay
+ net.minecraft.client.gui.components.SubtitleOverlay$Subtitle
- net.minecraft.client.gui.components.toasts.AdvancementToast
- net.minecraft.client.gui.components.toasts.package-info
+ net.minecraft.client.gui.components.toasts.RecipeToast
- net.minecraft.client.gui.components.toasts.SystemToast
+ net.minecraft.client.gui.components.toasts.SystemToast$SystemToastIds
- net.minecraft.client.gui.components.toasts.Toast
+ net.minecraft.client.gui.components.toasts.Toast$Visibility
- net.minecraft.client.gui.components.toasts.ToastComponent
+ net.minecraft.client.gui.components.toasts.ToastComponent$ToastInstance
- net.minecraft.client.gui.components.toasts.TutorialToast
+ net.minecraft.client.gui.components.toasts.TutorialToast$Icons
- net.minecraft.client.gui.components.TooltipAccessor
+ net.minecraft.client.gui.components.VolumeSlider
- net.minecraft.client.gui.components.Widget
+ net.minecraft.client.gui.font.AllMissingGlyphProvider
- net.minecraft.client.gui.font.FontManager
+ net.minecraft.client.gui.font.FontManager$1
- net.minecraft.client.gui.font.FontSet
+ net.minecraft.client.gui.font.FontTexture
- net.minecraft.client.gui.font.FontTexture$Node
- net.minecraft.client.gui.font.glyphs.BakedGlyph
+ net.minecraft.client.gui.font.glyphs.BakedGlyph$1
+ net.minecraft.client.gui.font.TextFieldHelper
+ net.minecraft.client.gui.Font$StringRenderOutput
- net.minecraft.client.gui.Gui
+ net.minecraft.client.gui.Gui$HeartType
- net.minecraft.client.gui.GuiComponent
+ net.minecraft.client.gui.MapRenderer
- net.minecraft.client.gui.MapRenderer$MapInstance
```

</details>


<details><summary>net.minecraft.client.renderer.RenderType</summary>

```diff
+ RenderType lambda$static$20(ResourceLocation)
+ RenderType lambda$static$21(ResourceLocation)
+ RenderType textIntensityPolygonOffset(ResourceLocation)
+ RenderType textPolygonOffset(ResourceLocation)
```

</details>


<details><summary>net.minecraft.util.profiling.metrics.profiling.ServerMetricsSamplersProvider</summary>

```diff
+ void <clinit>()
```

</details>


<details><summary>net.minecraft.world.entity.projectile.LargeFireball</summary>

```diff
+ void <init>(Level,LivingEntity,double,double,double,int)
- void <init>(Level,LivingEntity,double,double,double)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.structure.NetherFossilFeature$FeatureStart$1</summary>

```diff
+ void <init>(NetherFossilFeature$FeatureStart,ChunkGenerator)
- void <init>(NetherFossilFeature$FeatureStart,LevelHeightAccessor)
```

</details>


<details><summary>net.minecraft.world.level.saveddata.maps.MapDecoration$Type</summary>

```diff
+ boolean shouldTrackCount()
+ void <init>(String,int,boolean,boolean)
+ void <init>(String,int,boolean,int,boolean)
- void <init>(String,int,boolean,int)
- void <init>(String,int,boolean)
```

</details>


### Server




<details><summary>net.minecraft.util.profiling.metrics.profiling.ServerMetricsSamplersProvider</summary>

```diff
+ void <clinit>()
```

</details>


<details><summary>net.minecraft.world.entity.projectile.LargeFireball</summary>

```diff
+ void <init>(Level,LivingEntity,double,double,double,int)
- void <init>(Level,LivingEntity,double,double,double)
```

</details>


<details><summary>net.minecraft.world.level.levelgen.structure.NetherFossilFeature$FeatureStart$1</summary>

```diff
+ void <init>(NetherFossilFeature$FeatureStart,ChunkGenerator)
- void <init>(NetherFossilFeature$FeatureStart,LevelHeightAccessor)
```

</details>


<details><summary>net.minecraft.world.level.saveddata.maps.MapDecoration$Type</summary>

```diff
+ boolean shouldTrackCount()
+ void <init>(String,int,boolean,boolean)
+ void <init>(String,int,boolean,int,boolean)
- void <init>(String,int,boolean,int)
- void <init>(String,int,boolean)
```

</details>


# Folder structure

<details><summary>data/</summary>

```diff
- minecraft/loot_tables/blocks/azalea_leaves_flowers.json
+ minecraft/loot_tables/blocks/flowering_azalea_leaves.json
```

</details>


<details><summary>assets/</summary>

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


# Registries

<details><summary>block.txt</summary>

```diff
- minecraft:azalea_leaves_flowers
+ minecraft:flowering_azalea_leaves
```

</details>


<details><summary>item.txt</summary>

```diff
- minecraft:azalea_leaves_flowers
+ minecraft:flowering_azalea_leaves
```

</details>


# Tags

<details><summary>blocks/flowers.json</summary>

```diff
- minecraft:azalea_leaves_flowers
+ minecraft:flowering_azalea_leaves
```

</details>


<details><summary>blocks/leaves.json</summary>

```diff
- minecraft:azalea_leaves_flowers
+ minecraft:flowering_azalea_leaves
```

</details>


<details><summary>blocks/mineable/hoe.json</summary>

```diff
- minecraft:azalea_leaves_flowers
+ minecraft:flowering_azalea_leaves
```

</details>


<details><summary>items/flowers.json</summary>

```diff
- minecraft:azalea_leaves_flowers
+ minecraft:flowering_azalea_leaves
```

</details>


<details><summary>items/leaves.json</summary>

```diff
- minecraft:azalea_leaves_flowers
+ minecraft:flowering_azalea_leaves
```

</details>


# Translations

<details><summary>Keys</summary>

```diff
- block.minecraft.azalea_leaves_flowers
+ block.minecraft.flowering_azalea_leaves
```

</details>


# Misc

<details><summary>loot_tables.txt</summary>

```diff
- blocks/azalea_leaves_flowers.json
+ blocks/flowering_azalea_leaves.json
```

</details>


<details><summary>textures.txt</summary>

```diff
- block/azalea_leaves_flowers.png
+ block/flowering_azalea_leaves.png
```

</details>


# Version data

<details><summary>libraries.txt</summary>

```diff
- com.github.oshi:oshi-core:5.3.4
+ com.github.oshi:oshi-core:5.7.4
- net.java.dev.jna:jna-platform:5.6.0
+ net.java.dev.jna:jna-platform:5.8.0
- net.java.dev.jna:jna:5.6.0
+ net.java.dev.jna:jna:5.8.0
```

</details>
