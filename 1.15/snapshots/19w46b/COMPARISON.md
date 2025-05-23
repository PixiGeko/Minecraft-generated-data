## Comparison with [19w46a](https://github.com/PixiGeko/Minecraft-generated-data/tree/19w46a)

- [Version data](#version-data)
- [Translations](#translations)
- [Mappings](#mappings)
  - [Server](#server)
  - [Client](#client)

<hr/>
<details><summary>Version data</summary>
<table><tr><th></th><th align="left">19w46a</th><th>19w46b</th></tr><tr><td>World version</td><td><code>2216</code></td><td><code>2217</code></td></tr><tr><td>Protocol version</td><td><code>563</code></td><td><code>564</code></td></tr></table>
</details>
<details><summary>Translations</summary>
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
<details><summary>Mappings</summary>
<h2>Server</h2>

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

































































































































































































































































































































<h2>Client</h2>
<details>
<summary>
Classes
</summary>

```diff
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
- net.minecraft.client.gui.screens.DeathScreen
+ net.minecraft.client.gui.screens.DemoIntroScreen
- net.minecraft.client.gui.screens.DirectJoinServerScreen
+ net.minecraft.client.gui.screens.DisconnectedScreen
- net.minecraft.client.gui.screens.EditServerScreen
+ net.minecraft.client.gui.screens.ErrorScreen
- net.minecraft.client.gui.screens.GenericDirtMessageScreen
+ net.minecraft.client.gui.screens.InBedChatScreen
- net.minecraft.client.gui.screens.inventory.AbstractCommandBlockEditScreen
- net.minecraft.client.gui.screens.LanguageSelectScreen
+ net.minecraft.client.gui.screens.LanguageSelectScreen$LanguageSelectionList
- net.minecraft.client.gui.screens.LanguageSelectScreen$LanguageSelectionList$Entry
+ net.minecraft.client.gui.screens.LevelLoadingScreen
- net.minecraft.client.gui.screens.LoadingOverlay
+ net.minecraft.client.gui.screens.LoadingOverlay$LogoTexture
- net.minecraft.client.gui.screens.MenuScreens
+ net.minecraft.client.gui.screens.MenuScreens$ScreenConstructor
- net.minecraft.client.gui.screens.MouseSettingsScreen
+ net.minecraft.client.gui.screens.OptionsScreen
- net.minecraft.client.gui.screens.OptionsSubScreen
+ net.minecraft.client.gui.screens.OutOfMemoryScreen
- net.minecraft.client.gui.screens.Overlay
+ net.minecraft.client.gui.screens.PauseScreen
- net.minecraft.client.gui.screens.PresetFlatWorldScreen
+ net.minecraft.client.gui.screens.PresetFlatWorldScreen$PresetInfo
- net.minecraft.client.gui.screens.PresetFlatWorldScreen$PresetsList
+ net.minecraft.client.gui.screens.PresetFlatWorldScreen$PresetsList$Entry
- net.minecraft.client.gui.screens.ProgressScreen
+ net.minecraft.client.gui.screens.ReceivingLevelScreen
- net.minecraft.client.gui.screens.Screen
+ net.minecraft.client.gui.screens.ShareToLanScreen
- net.minecraft.client.gui.screens.SkinCustomizationScreen
+ net.minecraft.client.gui.screens.SoundOptionsScreen
- net.minecraft.client.gui.screens.TitleScreen
+ net.minecraft.client.gui.screens.VideoSettingsScreen
- net.minecraft.client.gui.screens.WinScreen
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