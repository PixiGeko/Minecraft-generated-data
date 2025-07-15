## Comparison with [19w46a](https://github.com/PixiGeko/Minecraft-generated-data/tree/19w46a)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Translations](#translations)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">19w46a</th><th>19w46b</th></tr><tr><td>World version</td><td><pre>2216</pre></td><td><pre>2217</pre></td></tr><tr><td>Protocol version</td><td><pre>563</pre></td><td><pre>564</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">19w46a</th><th>19w46b</th></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-glfw</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-jemalloc</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-openal</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-opengl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-stb</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl-tinyfd</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr><tr><td>org.lwjgl:lwjgl</td><td><pre>3.2.1</pre></td><td><pre>3.2.2</pre></td></tr></table>
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
+ narration.suggestion: Selected suggestion %d out of %d: %s
+ narration.suggestion.tooltip: Selected suggestion %d out of %d: %s (%s)
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
XXX.entity.animal.Bee$BeeGoToBlockGoal -1M
```
```
XXX.levelgen.flat.FlatLevelGeneratorSettings +1M
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Bee$BeeGoToBlockGoal
</summary>

```diff
+ boolean canBeeContinueToUse()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorSettings
</summary>

```diff
- IllegalArgumentException lambda$fromString$12(ResourceLocation)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
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
- XXX.gui.screens.DeathScreen
+ XXX.gui.screens.DemoIntroScreen
- XXX.gui.screens.DirectJoinServerScreen
+ XXX.gui.screens.DisconnectedScreen
- XXX.gui.screens.EditServerScreen
+ XXX.gui.screens.ErrorScreen
- XXX.gui.screens.GenericDirtMessageScreen
+ XXX.gui.screens.InBedChatScreen
- XXX.gui.screens.LanguageSelectScreen
+ XXX.gui.screens.LanguageSelectScreen$LanguageSelectionList
- XXX.gui.screens.LanguageSelectScreen$LanguageSelectionList$Entry
+ XXX.gui.screens.LevelLoadingScreen
- XXX.gui.screens.LoadingOverlay
+ XXX.gui.screens.LoadingOverlay$LogoTexture
- XXX.gui.screens.MenuScreens
+ XXX.gui.screens.MenuScreens$ScreenConstructor
- XXX.gui.screens.MouseSettingsScreen
+ XXX.gui.screens.OptionsScreen
- XXX.gui.screens.OptionsSubScreen
+ XXX.gui.screens.OutOfMemoryScreen
- XXX.gui.screens.Overlay
+ XXX.gui.screens.PauseScreen
- XXX.gui.screens.PresetFlatWorldScreen
+ XXX.gui.screens.PresetFlatWorldScreen$PresetInfo
- XXX.gui.screens.PresetFlatWorldScreen$PresetsList
+ XXX.gui.screens.PresetFlatWorldScreen$PresetsList$Entry
- XXX.gui.screens.ProgressScreen
+ XXX.gui.screens.ReceivingLevelScreen
- XXX.gui.screens.Screen
+ XXX.gui.screens.ShareToLanScreen
- XXX.gui.screens.SkinCustomizationScreen
+ XXX.gui.screens.SoundOptionsScreen
- XXX.gui.screens.TitleScreen
+ XXX.gui.screens.VideoSettingsScreen
- XXX.gui.screens.WinScreen
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
- XXX.screens.inventory.AbstractCommandBlockEditScreen
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.gui.components.CommandSuggestions +13M -12M | +1P -1P
```
```
XXX.gui.components.CommandSuggestions$SuggestionsList +4M -2M | +1P
```
```
XXX.gui.screens.ChatScreen +1M
```
```
XXX.entity.animal.Bee$BeeGoToBlockGoal -1M
```
```
XXX.levelgen.flat.FlatLevelGeneratorSettings +1M
```

</details>
<details>
<summary>
net.minecraft.client.gui.components.CommandSuggestions
</summary>

```diff
+ boolean access$100(CommandSuggestions)
+ boolean access$1002(CommandSuggestions,boolean)
- boolean access$1102(CommandSuggestions,boolean)
- boolean access$200(CommandSuggestions)
+ CommandSuggestions$SuggestionsList access$1102(CommandSuggestions,CommandSuggestions$SuggestionsList)
- CommandSuggestions$SuggestionsList access$1202(CommandSuggestions,CommandSuggestions$SuggestionsList)
+ EditBox access$300(CommandSuggestions)
- EditBox access$400(CommandSuggestions)
+ Font access$500(CommandSuggestions)
- Font access$600(CommandSuggestions)
+ int access$200(CommandSuggestions)
- int access$300(CommandSuggestions)
+ int access$400(CommandSuggestions)
- int access$500(CommandSuggestions)
+ int access$800(CommandSuggestions)
- int access$900(CommandSuggestions)
+ Minecraft access$700(CommandSuggestions)
- Minecraft access$800(CommandSuggestions)
+ Screen access$600(CommandSuggestions)
- Screen access$700(CommandSuggestions)
- String access$1000(String,String)
+ String access$900(String,String)
- String getNarrationMessage()
+ void showSuggestions()
- void showSuggestions(boolean)
```

</details>
<details>
<summary>
net.minecraft.client.gui.components.CommandSuggestions$SuggestionsList
</summary>

```diff
- String access$100(CommandSuggestions$SuggestionsList)
- String getNarrationMessage()
- void <init>(CommandSuggestions,int,int,int,Suggestions,boolean,CommandSuggestions$1)
- void <init>(CommandSuggestions,int,int,int,Suggestions,boolean)
+ void <init>(CommandSuggestions,int,int,int,Suggestions,CommandSuggestions$1)
+ void <init>(CommandSuggestions,int,int,int,Suggestions)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.ChatScreen
</summary>

```diff
- CommandSuggestions access$000(ChatScreen)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Bee$BeeGoToBlockGoal
</summary>

```diff
+ boolean canBeeContinueToUse()
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorSettings
</summary>

```diff
- IllegalArgumentException lambda$fromString$12(ResourceLocation)
```

</details>
</details>
<hr/>