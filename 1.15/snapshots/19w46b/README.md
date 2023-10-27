<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 19w46b ⌋<br/><img width="0" height="0"></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
:warning: This repository is not official, approved, endorsed, associated or connected with Mojang :warning:
<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>19w46b</td></tr>
<tr><th>Type</th><td>snapshots</td></tr>
<tr><th>Release time</th><td>2019-11-14T13:29:24+00:00</td></tr>
<tr><th>SHA1</th><td>18f4384dd05ad7711714742e5c22947a3828d6a2</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/18f4384dd05ad7711714742e5c22947a3828d6a2/19w46b.json">https://piston-meta.mojang.com/v1/packages/18f4384dd05ad7711714742e5c22947a3828d6a2/19w46b.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/58c12b1e2878e0a78719778acb803746450b3f1c/1.15.json">https://piston-meta.mojang.com/v1/packages/58c12b1e2878e0a78719778acb803746450b3f1c/1.15.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/eded6ea3899b67478780576a3b92c6cac867b501/server.jar">https://piston-data.mojang.com/v1/objects/eded6ea3899b67478780576a3b92c6cac867b501/server.jar</a></td></tr>
<tr><th>Server mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/9bd26eb0374965fb38d64b0e024c3a69d5a827b2/server.txt">https://piston-data.mojang.com/v1/objects/9bd26eb0374965fb38d64b0e024c3a69d5a827b2/server.txt</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/d795c91e58fd1c3ef66e5061a0562df4bc480368/client.jar">https://piston-data.mojang.com/v1/objects/d795c91e58fd1c3ef66e5061a0562df4bc480368/client.jar</a></td></tr>
<tr><th>Client mappings</th><td><a href="https://piston-data.mojang.com/v1/objects/3795d3efab29181641253d63fcaa4daf0f809c8a/client.txt">https://piston-data.mojang.com/v1/objects/3795d3efab29181641253d63fcaa4daf0f809c8a/client.txt</a></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
<i>Go to the README.md file to make sure you see the full comparison</i>
<br/><img width="0" height="0"></td></tr>
</table></html>

<br/>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/19w46a">19w46a</a>

# Mappings

### Client




<details><summary>Classes</summary>

```diff
- net.minecraft.client.gui.screens.achievement.package-info
- net.minecraft.client.gui.screens.achievement.StatsScreen
+ net.minecraft.client.gui.screens.achievement.StatsScreen$1
- net.minecraft.client.gui.screens.achievement.StatsScreen$GeneralStatisticsList
+ net.minecraft.client.gui.screens.achievement.StatsScreen$GeneralStatisticsList$Entry
- net.minecraft.client.gui.screens.achievement.StatsScreen$ItemStatisticsList
+ net.minecraft.client.gui.screens.achievement.StatsScreen$ItemStatisticsList$ItemComparator
- net.minecraft.client.gui.screens.achievement.StatsScreen$ItemStatisticsList$ItemRow
+ net.minecraft.client.gui.screens.achievement.StatsScreen$MobsStatisticsList
- net.minecraft.client.gui.screens.achievement.StatsScreen$MobsStatisticsList$MobRow
+ net.minecraft.client.gui.screens.achievement.StatsUpdateListener
- net.minecraft.client.gui.screens.advancements.AdvancementsScreen
+ net.minecraft.client.gui.screens.advancements.AdvancementTab
- net.minecraft.client.gui.screens.advancements.AdvancementTabType
+ net.minecraft.client.gui.screens.advancements.AdvancementTabType$1
- net.minecraft.client.gui.screens.advancements.AdvancementWidget
+ net.minecraft.client.gui.screens.advancements.AdvancementWidgetType
+ net.minecraft.client.gui.screens.advancements.package-info
+ net.minecraft.client.gui.screens.ConfirmLinkScreen
- net.minecraft.client.gui.screens.ConfirmScreen
+ net.minecraft.client.gui.screens.ConnectScreen
- net.minecraft.client.gui.screens.ConnectScreen$1
- net.minecraft.client.gui.screens.controls.ControlList
+ net.minecraft.client.gui.screens.controls.ControlList$1
- net.minecraft.client.gui.screens.controls.ControlList$CategoryEntry
+ net.minecraft.client.gui.screens.controls.ControlList$Entry
- net.minecraft.client.gui.screens.controls.ControlList$KeyEntry
+ net.minecraft.client.gui.screens.controls.ControlList$KeyEntry$1
- net.minecraft.client.gui.screens.controls.ControlList$KeyEntry$2
+ net.minecraft.client.gui.screens.controls.ControlsScreen
- net.minecraft.client.gui.screens.controls.package-info
+ net.minecraft.client.gui.screens.CreateBuffetWorldScreen
- net.minecraft.client.gui.screens.CreateBuffetWorldScreen$1
+ net.minecraft.client.gui.screens.CreateBuffetWorldScreen$BiomeList
- net.minecraft.client.gui.screens.CreateBuffetWorldScreen$BiomeList$Entry
+ net.minecraft.client.gui.screens.CreateFlatWorldScreen
- net.minecraft.client.gui.screens.CreateFlatWorldScreen$1
+ net.minecraft.client.gui.screens.CreateFlatWorldScreen$DetailsList
- net.minecraft.client.gui.screens.CreateFlatWorldScreen$DetailsList$Entry
+ net.minecraft.client.gui.screens.DeathScreen
- net.minecraft.client.gui.screens.DemoIntroScreen
+ net.minecraft.client.gui.screens.DirectJoinServerScreen
- net.minecraft.client.gui.screens.DisconnectedScreen
+ net.minecraft.client.gui.screens.EditServerScreen
- net.minecraft.client.gui.screens.ErrorScreen
+ net.minecraft.client.gui.screens.GenericDirtMessageScreen
- net.minecraft.client.gui.screens.InBedChatScreen
+ net.minecraft.client.gui.screens.inventory.AbstractCommandBlockEditScreen
+ net.minecraft.client.gui.screens.LanguageSelectScreen
- net.minecraft.client.gui.screens.LanguageSelectScreen$LanguageSelectionList
+ net.minecraft.client.gui.screens.LanguageSelectScreen$LanguageSelectionList$Entry
- net.minecraft.client.gui.screens.LevelLoadingScreen
+ net.minecraft.client.gui.screens.LoadingOverlay
- net.minecraft.client.gui.screens.LoadingOverlay$LogoTexture
+ net.minecraft.client.gui.screens.MenuScreens
- net.minecraft.client.gui.screens.MenuScreens$ScreenConstructor
+ net.minecraft.client.gui.screens.MouseSettingsScreen
- net.minecraft.client.gui.screens.OptionsScreen
+ net.minecraft.client.gui.screens.OptionsSubScreen
- net.minecraft.client.gui.screens.OutOfMemoryScreen
+ net.minecraft.client.gui.screens.Overlay
- net.minecraft.client.gui.screens.PauseScreen
+ net.minecraft.client.gui.screens.PresetFlatWorldScreen
- net.minecraft.client.gui.screens.PresetFlatWorldScreen$PresetInfo
+ net.minecraft.client.gui.screens.PresetFlatWorldScreen$PresetsList
- net.minecraft.client.gui.screens.PresetFlatWorldScreen$PresetsList$Entry
+ net.minecraft.client.gui.screens.ProgressScreen
- net.minecraft.client.gui.screens.ReceivingLevelScreen
+ net.minecraft.client.gui.screens.Screen
- net.minecraft.client.gui.screens.ShareToLanScreen
+ net.minecraft.client.gui.screens.SkinCustomizationScreen
- net.minecraft.client.gui.screens.SoundOptionsScreen
+ net.minecraft.client.gui.screens.TitleScreen
- net.minecraft.client.gui.screens.VideoSettingsScreen
+ net.minecraft.client.gui.screens.WinScreen
```

</details>


<details><summary>net.minecraft.client.gui.components.CommandSuggestions</summary>

```diff
- boolean access$100(CommandSuggestions)
- boolean access$1002(CommandSuggestions,boolean)
+ boolean access$1102(CommandSuggestions,boolean)
+ boolean access$200(CommandSuggestions)
- CommandSuggestions$SuggestionsList access$1102(CommandSuggestions,CommandSuggestions$SuggestionsList)
+ CommandSuggestions$SuggestionsList access$1202(CommandSuggestions,CommandSuggestions$SuggestionsList)
- EditBox access$300(CommandSuggestions)
+ EditBox access$400(CommandSuggestions)
- Font access$500(CommandSuggestions)
+ Font access$600(CommandSuggestions)
- int access$200(CommandSuggestions)
+ int access$300(CommandSuggestions)
- int access$400(CommandSuggestions)
+ int access$500(CommandSuggestions)
- int access$800(CommandSuggestions)
+ int access$900(CommandSuggestions)
- Minecraft access$700(CommandSuggestions)
+ Minecraft access$800(CommandSuggestions)
- Screen access$600(CommandSuggestions)
+ Screen access$700(CommandSuggestions)
+ String access$1000(String,String)
- String access$900(String,String)
+ String getNarrationMessage()
- void showSuggestions()
+ void showSuggestions(boolean)
```

</details>


<details><summary>net.minecraft.client.gui.components.CommandSuggestions$SuggestionsList</summary>

```diff
+ String access$100(CommandSuggestions$SuggestionsList)
+ String getNarrationMessage()
+ void <init>(CommandSuggestions,int,int,int,Suggestions,boolean,CommandSuggestions$1)
+ void <init>(CommandSuggestions,int,int,int,Suggestions,boolean)
- void <init>(CommandSuggestions,int,int,int,Suggestions,CommandSuggestions$1)
- void <init>(CommandSuggestions,int,int,int,Suggestions)
```

</details>


<details><summary>net.minecraft.client.gui.screens.ChatScreen</summary>

```diff
+ CommandSuggestions access$000(ChatScreen)
```

</details>


<details><summary>net.minecraft.world.entity.animal.Bee$BeeGoToBlockGoal</summary>

```diff
- boolean canBeeContinueToUse()
```

</details>


<details><summary>net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorSettings</summary>

```diff
+ IllegalArgumentException lambda$fromString$12(ResourceLocation)
```

</details>


### Server




<details><summary>net.minecraft.world.entity.animal.Bee$BeeGoToBlockGoal</summary>

```diff
- boolean canBeeContinueToUse()
```

</details>


<details><summary>net.minecraft.world.level.levelgen.flat.FlatLevelGeneratorSettings</summary>

```diff
+ IllegalArgumentException lambda$fromString$12(ResourceLocation)
```

</details>


# Translations

<details><summary>Keys</summary>

```diff
+ narration.suggestion
+ narration.suggestion.tooltip
```

</details>
