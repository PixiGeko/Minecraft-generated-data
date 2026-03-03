## Comparison with [26.1-snapshot-10](https://github.com/PixiGeko/Minecraft-generated-data/tree/26.1-snapshot-10)

> [!TIP]
> - [Version data](#version-data)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Items (models)](#items-(models))
> - [Translations](#translations)
> - [File structure](#file-structure)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">26.1-snapshot-10</th><th>26.1-snapshot-11</th></tr><tr><td>DataPack version</td><td><pre>99.3</pre></td><td><pre>100.0</pre></td></tr><tr><td>ResourcePack version</td><td><pre>82.0</pre></td><td><pre>83.0</pre></td></tr><tr><td>World version</td><td><pre>4778</pre></td><td><pre>4779</pre></td></tr><tr><td>Protocol version</td><td><pre>1073742120</pre></td><td><pre>1073742121</pre></td></tr></table>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
sound_event
</summary>

```diff
+ minecraft:entity.baby_pig.eat
+ minecraft:entity.pig_big.eat
+ minecraft:entity.pig_mini.eat
+ minecraft:entity.pig.eat
```

</details>
<details>
<summary>
test_environment_definition_type
</summary>

```diff
+ minecraft:timeline_attributes
```

</details>
<details>
<summary>
worldgen/block_state_provider_type
</summary>

```diff
+ minecraft:rule_based_state_provider
```

</details>
</details>
<hr/>
<details><summary><b><ins>TAGS</ins></b><a name="tags"></a></summary>
<br/>
<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:entity.baby_pig.eat
+ minecraft:entity.pig_big.eat
+ minecraft:entity.pig_mini.eat
+ minecraft:entity.pig.eat
```

</details>
<details>
<summary>
universal_tags/test_environment_definition_type.json
</summary>

```diff
+ minecraft:timeline_attributes
```

</details>
<details>
<summary>
universal_tags/worldgen/block_state_provider_type.json
</summary>

```diff
+ minecraft:rule_based_state_provider
```

</details>
</details>
<hr/>
<details><summary><b><ins>ITEMS (MODELS)</ins></b><a name="items-(models)"></a></summary>
<br/>
<details>
<summary>
Model types
</summary>

```diff
+ minecraft:composite
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
+ subtitles.entity.baby_pig.eat: Baby Pig eats
+ subtitles.entity.pig.eat: Pig eats
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>26.1-snapshot-10</th><th>26.1-snapshot-11</th></tr>
<tr><th align="left"><div style="width:290px">chat_restriction.chat_disabled_by_options.action</div></th><td>Go to Chat Settings screen</td><td>Go to the Chat Settings screen</td></tr>
<tr><th align="left"><div style="width:290px">chat_restriction.disabled_by_launcher</div></th><td>Chat is restricted by launcher</td><td>Chat is restricted by the launcher</td></tr>
<tr><th align="left"><div style="width:290px">restrictions_screen.permission.receive_system_messages.allowed</div></th><td>You can receive system messages from server</td><td>You can receive system messages from the server</td></tr>
<tr><th align="left"><div style="width:290px">restrictions_screen.permission.receive_system_messages.denied</div></th><td>You can't receive system messages from server</td><td>You can't receive system messages from the server</td></tr>
<tr><th align="left"><div style="width:290px">upgradeWorld.aborted.message</div></th><td>This may happen if another program accessed the world during the upgrade.

It may help to restart your computer and trying again. If the issue persists, please consider reporting a bug.</td><td>This may happen if another program accessed the world during the upgrade.

It may help to restart your computer and try again. If the issue persists, please consider reporting a bug.</td></tr>
</table>
<br/>
</details>
</details>
<hr/>
<details><summary><b><ins>FILE STRUCTURE</ins></b><a name="file-structure"></a></summary>
<br/>
<details>
<summary>
generated
</summary>

```diff
+ reports/minecraft/components/sound_event/entity.baby_pig.eat.json
+ reports/minecraft/components/sound_event/entity.pig_big.eat.json
+ reports/minecraft/components/sound_event/entity.pig_mini.eat.json
+ reports/minecraft/components/sound_event/entity.pig.eat.json
+ reports/minecraft/components/test_environment_definition_type/timeline_attributes.json
- reports/minecraft/components/villager_trade/librarian/5/emerald_name_tag.json
+ reports/minecraft/components/villager_trade/librarian/5/emerald_red_candle.json
+ reports/minecraft/components/villager_trade/librarian/5/emerald_yellow_candle.json
+ reports/minecraft/components/villager_trade/wandering_trader/emerald_name_tag.json
+ reports/minecraft/components/worldgen/block_state_provider_type/rule_based_state_provider.json
+ reports/minecraft/components/worldgen/noise/nether/temperature.json
+ reports/minecraft/components/worldgen/noise/nether/vegetation.json
```

</details>
<details>
<summary>
data
</summary>

```diff
+ minecraft/tags/block/prevents_nearby_leaf_decay.json
- minecraft/villager_trade/librarian/5/emerald_name_tag.json
+ minecraft/villager_trade/librarian/5/emerald_red_candle.json
+ minecraft/villager_trade/librarian/5/emerald_yellow_candle.json
+ minecraft/villager_trade/wandering_trader/emerald_name_tag.json
+ minecraft/worldgen/noise/nether/temperature.json
+ minecraft/worldgen/noise/nether/vegetation.json
```

</details>
</details>
<hr/>