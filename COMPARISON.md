## Comparison with [25w35a](https://github.com/PixiGeko/Minecraft-generated-data/tree/25w35a)

> [!TIP]
> - [Version data](#version-data)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Items (registry)](#items-(registry))
> - [Translations](#translations)
> - [File structure](#file-structure)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">25w35a</th><th>25w36a</th></tr><tr><td>DataPack version</td><td><pre>{
  "major": 85,
  "minor": 0
}</pre></td><td><pre>{
  "major": 86,
  "minor": 0
}</pre></td></tr><tr><td>ResourcePack version</td><td><pre>{
  "major": 67,
  "minor": 0
}</pre></td><td><pre>{
  "major": 68,
  "minor": 0
}</pre></td></tr><tr><td>World version</td><td><pre>4542</pre></td><td><pre>4545</pre></td></tr><tr><td>Protocol version</td><td><pre>1073742089</pre></td><td><pre>1073742090</pre></td></tr></table>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
entity_type
</summary>

```diff
+ minecraft:mannequin
```

</details>
</details>
<hr/>
<details><summary><b><ins>TAGS</ins></b><a name="tags"></a></summary>
<br/>
<details>
<summary>
all_entities_without_drop.json
</summary>

```diff
+ minecraft:mannequin
```

</details>
<details>
<summary>
all_living_entities_without_drop.json
</summary>

```diff
+ minecraft:mannequin
```

</details>
<details>
<summary>
universal_tags/entity_type.json
</summary>

```diff
+ minecraft:mannequin
```

</details>
</details>
<hr/>
<details><summary><b><ins>ITEMS (REGISTRY)</ins></b><a name="items-(registry)"></a></summary>
<br/>
<details>
<summary>
copper_golem_statue
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w35a</th><th>25w36a</th></tr><tr><td>minecraft:block_state</td><td><pre>/</pre></td><td><pre>{
  "copper_golem_pose": "standing"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
exposed_copper_golem_statue
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w35a</th><th>25w36a</th></tr><tr><td>minecraft:block_state</td><td><pre>/</pre></td><td><pre>{
  "copper_golem_pose": "standing"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
oxidized_copper_golem_statue
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w35a</th><th>25w36a</th></tr><tr><td>minecraft:block_state</td><td><pre>/</pre></td><td><pre>{
  "copper_golem_pose": "standing"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_copper_golem_statue
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w35a</th><th>25w36a</th></tr><tr><td>minecraft:block_state</td><td><pre>/</pre></td><td><pre>{
  "copper_golem_pose": "standing"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_exposed_copper_golem_statue
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w35a</th><th>25w36a</th></tr><tr><td>minecraft:block_state</td><td><pre>/</pre></td><td><pre>{
  "copper_golem_pose": "standing"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_oxidized_copper_golem_statue
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w35a</th><th>25w36a</th></tr><tr><td>minecraft:block_state</td><td><pre>/</pre></td><td><pre>{
  "copper_golem_pose": "standing"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
waxed_weathered_copper_golem_statue
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w35a</th><th>25w36a</th></tr><tr><td>minecraft:block_state</td><td><pre>/</pre></td><td><pre>{
  "copper_golem_pose": "standing"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
weathered_copper_golem_statue
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w35a</th><th>25w36a</th></tr><tr><td>minecraft:block_state</td><td><pre>/</pre></td><td><pre>{
  "copper_golem_pose": "standing"
}</pre></td></tr></table>
<br/>
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
+ commands.spectate.cannot_spectate: %s cannot be spectated
+ entity.minecraft.mannequin: Mannequin
+ entity.minecraft.mannequin.label: NPC
+ key.categories.spectator: Spectator
+ key.spectatorHotbar: Select On Hotbar
+ manageServer.add.title: Add Server
+ manageServer.edit.title: Edit Server Info
+ manageServer.enterIp: Server Address
+ manageServer.enterName: Server Name
+ manageServer.resourcePack: Server Resource Packs
+ manageServer.resourcePack.disabled: Disabled
+ manageServer.resourcePack.enabled: Enabled
+ manageServer.resourcePack.prompt: Prompt
+ multiplayer.disconnect.banned.reason.default: Banned by an operator.
+ multiplayer.status.anonymous_player: Anonymous Player
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>25w35a</th><th>25w36a</th></tr>
<tr><th align="left"><div style="width:290px">advMode.notEnabled</div></th><td>Command blocks are not enabled on this server</td><td>Command blocks are not enabled</td></tr>
<tr><th align="left"><div style="width:290px">argument.block.tag.disallowed</div></th><td>Tags aren't allowed here, only actual blocks</td><td>Tags aren't allowed here; only actual blocks</td></tr>
<tr><th align="left"><div style="width:290px">argument.double.big</div></th><td>Double must not be more than %s, found %s</td><td>Double must not be more than %s: found %s</td></tr>
<tr><th align="left"><div style="width:290px">argument.double.low</div></th><td>Double must not be less than %s, found %s</td><td>Double must not be less than %s: found %s</td></tr>
<tr><th align="left"><div style="width:290px">argument.float.big</div></th><td>Float must not be more than %s, found %s</td><td>Float must not be more than %s: found %s</td></tr>
<tr><th align="left"><div style="width:290px">argument.float.low</div></th><td>Float must not be less than %s, found %s</td><td>Float must not be less than %s: found %s</td></tr>
<tr><th align="left"><div style="width:290px">argument.integer.big</div></th><td>Integer must not be more than %s, found %s</td><td>Integer must not be more than %s: found %s</td></tr>
<tr><th align="left"><div style="width:290px">argument.integer.low</div></th><td>Integer must not be less than %s, found %s</td><td>Integer must not be less than %s: found %s</td></tr>
<tr><th align="left"><div style="width:290px">argument.item.tag.disallowed</div></th><td>Tags aren't allowed here, only actual items</td><td>Tags aren't allowed here; only actual items</td></tr>
<tr><th align="left"><div style="width:290px">argument.long.big</div></th><td>Long must not be more than %s, found %s</td><td>Long must not be more than %s: found %s</td></tr>
<tr><th align="left"><div style="width:290px">argument.long.low</div></th><td>Long must not be less than %s, found %s</td><td>Long must not be less than %s: found %s</td></tr>
<tr><th align="left"><div style="width:290px">argument.range.ints</div></th><td>Only whole numbers allowed, not decimals</td><td>Only whole numbers allowed; not decimals</td></tr>
<tr><th align="left"><div style="width:290px">argument.time.tick_count_too_low</div></th><td>The tick count must not be less than %s, found %s</td><td>The tick count must not be less than %s: found %s</td></tr>
<tr><th align="left"><div style="width:290px">arguments.swizzle.invalid</div></th><td>Invalid swizzle, expected combination of 'x', 'y' and 'z'</td><td>Invalid swizzle: expected combination of 'x', 'y' and 'z'</td></tr>
<tr><th align="left"><div style="width:290px">chat.disabled.invalid_command_signature</div></th><td>Command had unexpected or missing command argument signatures.</td><td>The command had unexpected or missing command argument signatures.</td></tr>
<tr><th align="left"><div style="width:290px">command.unknown.command</div></th><td>Unknown or incomplete command, see below for error</td><td>Unknown or incomplete command. See below for error</td></tr>
<tr><th align="left"><div style="width:290px">commands.attribute.base_value.get.success</div></th><td>Base value of attribute %s for entity %s is %s</td><td>The base value of attribute %s for entity %s is %s</td></tr>
<tr><th align="left"><div style="width:290px">commands.attribute.base_value.reset.success</div></th><td>Base value for attribute %s for entity %s reset to default %s</td><td>The base value for attribute %s for entity %s reset to default %s</td></tr>
<tr><th align="left"><div style="width:290px">commands.attribute.base_value.set.success</div></th><td>Base value for attribute %s for entity %s set to %s</td><td>The base value for attribute %s for entity %s set to %s</td></tr>
<tr><th align="left"><div style="width:290px">commands.attribute.modifier.value.get.success</div></th><td>Value of modifier %s on attribute %s for entity %s is %s</td><td>The value of modifier %s on attribute %s for entity %s is %s</td></tr>
<tr><th align="left"><div style="width:290px">commands.attribute.value.get.success</div></th><td>Value of attribute %s for entity %s is %s</td><td>The value of attribute %s for entity %s is %s</td></tr>
<tr><th align="left"><div style="width:290px">commands.clone.toobig</div></th><td>Too many blocks in the specified area (maximum %s, specified %s)</td><td>Too many blocks in the specified area (maximum %s, but specified %s)</td></tr>
<tr><th align="left"><div style="width:290px">commands.data.modify.expected_list</div></th><td>Expected list, got: %s</td><td>Expected list; got: %s</td></tr>
<tr><th align="left"><div style="width:290px">commands.data.modify.expected_object</div></th><td>Expected object, got: %s</td><td>Expected object; got: %s</td></tr>
<tr><th align="left"><div style="width:290px">commands.data.modify.expected_value</div></th><td>Expected value, got: %s</td><td>Expected value; got: %s</td></tr>
<tr><th align="left"><div style="width:290px">commands.datapack.create.io_failure</div></th><td>Can't create pack with name '%s', check logs</td><td>Can't create pack with name '%s'. Check logs</td></tr>
<tr><th align="left"><div style="width:290px">commands.execute.blocks.toobig</div></th><td>Too many blocks in the specified area (maximum %s, specified %s)</td><td>Too many blocks in the specified area (maximum %s, but specified %s)</td></tr>
<tr><th align="left"><div style="width:290px">commands.execute.conditional.fail_count</div></th><td>Test failed, count: %s</td><td>Test failed. Count: %s</td></tr>
<tr><th align="left"><div style="width:290px">commands.execute.conditional.pass_count</div></th><td>Test passed, count: %s</td><td>Test passed. Count: %s</td></tr>
<tr><th align="left"><div style="width:290px">commands.fill.toobig</div></th><td>Too many blocks in the specified area (maximum %s, specified %s)</td><td>Too many blocks in the specified area (maximum %s, but specified %s)</td></tr>
<tr><th align="left"><div style="width:290px">commands.fillbiome.toobig</div></th><td>Too many blocks in the specified volume (maximum %s, specified %s)</td><td>Too many blocks in the specified volume (maximum %s, but specified %s)</td></tr>
<tr><th align="left"><div style="width:290px">commands.forceload.toobig</div></th><td>Too many chunks in the specified area (maximum %s, specified %s)</td><td>Too many chunks in the specified area (maximum %s, but specified %s)</td></tr>
<tr><th align="left"><div style="width:290px">commands.function.error.argument_not_compound</div></th><td>Invalid argument type: %s, expected Compound</td><td>Invalid argument type: %s. Expected Compound</td></tr>
<tr><th align="left"><div style="width:290px">commands.test.locate.done</div></th><td>Finished locating, found %s structure(s)</td><td>Finished locating: found %s structure(s)</td></tr>
<tr><th align="left"><div style="width:290px">commands.test.locate.started</div></th><td>Started locating test structures, this might take a while...</td><td>Started locating test structures. This might take a while...</td></tr>
<tr><th align="left"><div style="width:290px">commands.tick.query.percentiles</div></th><td>Percentiles: P50: %sms P95: %sms P99: %sms, sample: %s</td><td>Percentiles: P50: %sms P95: %sms P99: %sms. Sample: %s</td></tr>
<tr><th align="left"><div style="width:290px">commands.tick.query.rate.sprinting</div></th><td>Target tick rate: %s per second (ignored, reference only).

Average time per tick: %sms</td><td>Target tick rate: %s per second (ignored; reference only).

Average time per tick: %sms</td></tr>
<tr><th align="left"><div style="width:290px">debug.copy_location.help</div></th><td>F3 + C = Copy location as /tp command, hold F3 + C to crash the game</td><td>F3 + C = Copy location as /tp command, or hold for 10 seconds to crash the game</td></tr>
<tr><th align="left"><div style="width:290px">gamerule.allowEnteringNetherUsingPortals.description</div></th><td>Controls whether players are allowed to enter the Nether or not</td><td>Controls whether players are allowed to enter the Nether.</td></tr>
<tr><th align="left"><div style="width:290px">gamerule.allowFireTicksAwayFromPlayer.description</div></th><td>Controls whether or not fire and lava should be able to tick further than 8 chunks away from any player</td><td>Controls whether fire and lava should be able to tick further than 8 chunks away from any player.</td></tr>
<tr><th align="left"><div style="width:290px">gamerule.commandModificationBlockLimit.description</div></th><td>Number of blocks that can be changed at once by one command, such as fill or clone.</td><td>The number of blocks that can be changed at once by one command, such as fill or clone.</td></tr>
<tr><th align="left"><div style="width:290px">gamerule.doVinesSpread.description</div></th><td>Controls whether or not the Vines block spreads randomly to adjacent blocks. Does not affect other types of vine blocks such as Weeping Vines, Twisting Vines, etc.</td><td>Controls whether the Vines block spreads randomly to adjacent blocks. Does not affect other types of vine blocks such as Weeping Vines, Twisting Vines, etc.</td></tr>
<tr><th align="left"><div style="width:290px">gamerule.pvp.description</div></th><td>Controls whether players are allowed to damage other players or not</td><td>Controls whether players are allowed to damage other players.</td></tr>
<tr><th align="left"><div style="width:290px">gamerule.spawnChunkRadius.description</div></th><td>Amount of chunks that stay loaded around the overworld spawn position.</td><td>The amount of chunks that stay loaded around the overworld spawn position.</td></tr>
<tr><th align="left"><div style="width:290px">gamerule.spawnMonsters.description</div></th><td>Controls whether monsters naturally spawns or not</td><td>Controls whether monsters naturally spawn.</td></tr>
<tr><th align="left"><div style="width:290px">inventory.hotbarInfo</div></th><td>Save hotbar with %1$s+%2$s</td><td>Save hotbar with %1$s + %2$s</td></tr>
<tr><th align="left"><div style="width:290px">inventory.hotbarSaved</div></th><td>Item hotbar saved (restore with %1$s+%2$s)</td><td>Item hotbar saved (restore with %1$s + %2$s)</td></tr>
<tr><th align="left"><div style="width:290px">item.op_block_warning.line2</div></th><td>Use of this item might lead to command execution</td><td>Use of this item might lead to command execution.</td></tr>
<tr><th align="left"><div style="width:290px">key.spectatorOutlines</div></th><td>Highlight Players (Spectators)</td><td>Highlight Players</td></tr>
<tr><th align="left"><div style="width:290px">mco.configure.world.switch.slot.subtitle</div></th><td>This world is empty, choose how to create your world</td><td>This world is empty. Choose how to create your world</td></tr>
<tr><th align="left"><div style="width:290px">mco.errorMessage.connectionFailure</div></th><td>An error occurred, please try again later.</td><td>An error occurred. Please try again later.</td></tr>
<tr><th align="left"><div style="width:290px">mco.errorMessage.realmsService.unknownCompatibility</div></th><td>Could not check compatible version, got response: %s</td><td>Could not check compatible version; got response: %s</td></tr>
<tr><th align="left"><div style="width:290px">mco.snapshotRealmsPopup.message</div></th><td>Realms are now available in Snapshots starting with Snapshot 23w41a. Every Realms subscription comes with a free Snapshot Realm that is separate from your normal Java Realm!</td><td>Realms is now available in Snapshots starting with Snapshot 23w41a. Every Realms subscription comes with a free Snapshot Realm that is separate from your normal Java Realm!</td></tr>
<tr><th align="left"><div style="width:290px">mco.snapshotRealmsPopup.title</div></th><td>Realms now available in Snapshots</td><td>Realms is now available in Snapshots</td></tr>
<tr><th align="left"><div style="width:290px">mco.upload.close.failure</div></th><td>Could not close your Realm, please try again later</td><td>Could not close your Realm. Please try again later.</td></tr>
<tr><th align="left"><div style="width:290px">multiplayer.disconnect.authservers_down</div></th><td>Authentication servers are down. Please try again later, sorry!</td><td>Authentication servers are down. Please try again later. Sorry!</td></tr>
<tr><th align="left"><div style="width:290px">multiplayer.disconnect.bad_chat_index</div></th><td>Detected missed or reordered chat message from server</td><td>Detected a missed or reordered chat message from the server</td></tr>
<tr><th align="left"><div style="width:290px">multiplayer.disconnect.invalid_packet</div></th><td>Server sent an invalid packet</td><td>The server sent an invalid packet</td></tr>
<tr><th align="left"><div style="width:290px">multiplayer.disconnect.missing_tags</div></th><td>Incomplete set of tags received from server.

Please contact server operator.</td><td>Incomplete set of tags received from the server.

Please contact a server operator.</td></tr>
<tr><th align="left"><div style="width:290px">multiplayer.disconnect.transfers_disabled</div></th><td>Server does not accept transfers</td><td>This server does not accept transfers</td></tr>
<tr><th align="left"><div style="width:290px">multiplayer.disconnect.unsigned_chat</div></th><td>Received chat packet with missing or invalid signature.</td><td>Received a chat packet with a missing or invalid signature.</td></tr>
<tr><th align="left"><div style="width:290px">multiplayer.message_not_delivered</div></th><td>Can't deliver chat message, check server logs: %s</td><td>Can't deliver chat message; check server logs: %s</td></tr>
<tr><th align="left"><div style="width:290px">multiplayer.requiredTexturePrompt.disconnect</div></th><td>Server requires a custom resource pack</td><td>This server requires a custom resource pack</td></tr>
<tr><th align="left"><div style="width:290px">narration.component_list.usage</div></th><td>Press Tab to navigate to next element</td><td>Press Tab to navigate to the next element</td></tr>
<tr><th align="left"><div style="width:290px">narration.selection.usage</div></th><td>Press up and down buttons to move to another entry</td><td>Press the up and down buttons to move to another entry</td></tr>
<tr><th align="left"><div style="width:290px">narration.slider.usage.focused</div></th><td>Press left or right keyboard buttons to change value</td><td>Press the left or right keyboard buttons to change the value</td></tr>
<tr><th align="left"><div style="width:290px">narration.slider.usage.hovered</div></th><td>Drag slider to change value</td><td>Drag the slider to change its value</td></tr>
<tr><th align="left"><div style="width:290px">narration.suggestion.usage.fill.fixed</div></th><td>Press Tab to use suggestion</td><td>Press Tab to use the suggestion</td></tr>
<tr><th align="left"><div style="width:290px">narration.suggestion.usage.fill.hidable</div></th><td>Press Tab to use suggestion, or Escape to leave suggestions</td><td>Press Tab to use the suggestion, or Escape to leave suggestions</td></tr>
<tr><th align="left"><div style="width:290px">options.accessibility.narrator_hotkey.mac.tooltip</div></th><td>Allows the Narrator to be toggled on and off with 'Cmd+B'.</td><td>Allows the Narrator to be toggled on and off with 'Cmd + B'.</td></tr>
<tr><th align="left"><div style="width:290px">options.accessibility.narrator_hotkey.tooltip</div></th><td>Allows the Narrator to be toggled on and off with 'Ctrl+B'.</td><td>Allows the Narrator to be toggled on and off with 'Ctrl + B'.</td></tr>
<tr><th align="left"><div style="width:290px">options.chunks</div></th><td>%s chunks</td><td>%s Chunks</td></tr>
<tr><th align="left"><div style="width:290px">parsing.bool.invalid</div></th><td>Invalid boolean, expected 'true' or 'false' but found '%s'</td><td>Invalid boolean: expected 'true' or 'false' but found '%s'</td></tr>
<tr><th align="left"><div style="width:290px">selectWorld.locked</div></th><td>Locked by another running instance of Minecraft</td><td>Locked by another running instance of Minecraft.</td></tr>
<tr><th align="left"><div style="width:290px">selectWorld.tooltip.fromNewerVersion2</div></th><td>loading this world could cause problems!</td><td>and loading it could cause problems!</td></tr>
<tr><th align="left"><div style="width:290px">slot.only_single_allowed</div></th><td>Only single slots allowed, got '%s'</td><td>Only single slots allowed: got '%s'</td></tr>
<tr><th align="left"><div style="width:290px">test_instance.description.batch</div></th><td>Batch: %s</td><td>Environment: %s</td></tr>
<tr><th align="left"><div style="width:290px">test.error.block_property_mismatch</div></th><td>Expected property %s to be %s, was %s</td><td>Expected property %s to be %s; was %s</td></tr>
<tr><th align="left"><div style="width:290px">test.error.block_property_missing</div></th><td>Block property missing, expected property %s to be %s</td><td>Block property missing. Expected property %s to be %s</td></tr>
<tr><th align="left"><div style="width:290px">test.error.entity_property_details</div></th><td>Entity %s failed test: %s, expected: %s, was: %s</td><td>Entity %s failed test: %s; expected: %s; was: %s</td></tr>
<tr><th align="left"><div style="width:290px">test.error.expected_block</div></th><td>Expected block %s, got %s</td><td>Expected block %s; got %s</td></tr>
<tr><th align="left"><div style="width:290px">test.error.expected_block_tag</div></th><td>Expected block in #%s, got %s</td><td>Expected block in #%s; got %s</td></tr>
<tr><th align="left"><div style="width:290px">test.error.expected_entity_count</div></th><td>Expected %s entities of type %s, found %s</td><td>Expected %s entities of type %s: found %s</td></tr>
<tr><th align="left"><div style="width:290px">test.error.expected_entity_data</div></th><td>Expected entity data to be: %s, was: %s</td><td>Expected entity data to be: %s; was: %s</td></tr>
<tr><th align="left"><div style="width:290px">test.error.expected_items_count</div></th><td>Expected %s items of type %s, found %s</td><td>Expected %s items of type %s: found %s</td></tr>
<tr><th align="left"><div style="width:290px">test.error.state_not_equal</div></th><td>Incorrect state. Expected %s, was %s</td><td>Incorrect state. Expected %s; was %s</td></tr>
<tr><th align="left"><div style="width:290px">test.error.value_not_equal</div></th><td>Expected %s to be %s, was %s</td><td>Expected %s to be %s; was %s</td></tr>
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
+ minecraft/loot_table/entities/mannequin.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
- minecraft/shaders/core/position_color_lightmap.fsh
- minecraft/shaders/core/position_color_lightmap.vsh
- minecraft/shaders/core/position_color_tex_lightmap.fsh
- minecraft/shaders/core/position_color_tex_lightmap.vsh
+ minecraft/textures/trims/color_palettes/copper_darker.png
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
- XXX.advancements.critereon.MinMaxBounds$Bounds$1
+ XXX.advancements.critereon.MinMaxBounds$BoundsFactory
+ XXX.advancements.critereon.MinMaxBounds$Doubles
- XXX.advancements.critereon.MinMaxBounds$FloatDegrees
+ XXX.advancements.critereon.package-info
- XXX.advancements.packs.package-info
- XXX.advancements.packs.VanillaAdvancementProvider
+ XXX.advancements.packs.VanillaAdventureAdvancements
- XXX.advancements.packs.VanillaHusbandryAdvancements
+ XXX.advancements.packs.VanillaNetherAdvancements
- XXX.advancements.packs.VanillaStoryAdvancements
+ XXX.advancements.packs.VanillaTheEndAdvancements
- XXX.arguments.blocks.BlockInput
+ XXX.arguments.blocks.BlockPredicateArgument
- XXX.arguments.blocks.BlockPredicateArgument$BlockPredicate
+ XXX.arguments.blocks.BlockPredicateArgument$Result
- XXX.arguments.blocks.BlockPredicateArgument$TagPredicate
+ XXX.arguments.blocks.BlockStateArgument
- XXX.arguments.blocks.BlockStateParser
+ XXX.arguments.blocks.BlockStateParser$BlockResult
- XXX.arguments.blocks.BlockStateParser$TagResult
+ XXX.arguments.blocks.package-info
- XXX.arguments.coordinates.BlockPosArgument
+ XXX.arguments.coordinates.ColumnPosArgument
- XXX.arguments.coordinates.Coordinates
+ XXX.arguments.coordinates.LocalCoordinates
- XXX.arguments.coordinates.package-info
- XXX.arguments.coordinates.RotationArgument
+ XXX.arguments.coordinates.SwizzleArgument
- XXX.arguments.coordinates.Vec2Argument
+ XXX.arguments.coordinates.Vec3Argument
- XXX.arguments.coordinates.WorldCoordinate
+ XXX.arguments.coordinates.WorldCoordinates
+ XXX.arguments.item.ComponentPredicateParser
- XXX.arguments.item.ComponentPredicateParser$ComponentLookupRule
+ XXX.arguments.item.ComponentPredicateParser$Context
- XXX.arguments.item.ComponentPredicateParser$ElementLookupRule
+ XXX.arguments.item.ComponentPredicateParser$PredicateLookupRule
- XXX.arguments.item.ComponentPredicateParser$TagLookupRule
+ XXX.arguments.item.FunctionArgument
- XXX.arguments.item.FunctionArgument$1
+ XXX.arguments.item.FunctionArgument$2
- XXX.arguments.item.FunctionArgument$Result
+ XXX.arguments.item.ItemArgument
- XXX.arguments.item.ItemInput
+ XXX.arguments.item.ItemParser
- XXX.arguments.item.ItemParser$1
+ XXX.arguments.item.ItemParser$ItemResult
- XXX.arguments.item.ItemParser$State
+ XXX.arguments.item.ItemParser$SuggestionsVisitor
- XXX.arguments.item.ItemParser$Visitor
+ XXX.arguments.item.ItemPredicateArgument
- XXX.arguments.item.ItemPredicateArgument$ComponentWrapper
+ XXX.arguments.item.ItemPredicateArgument$Context
- XXX.arguments.item.ItemPredicateArgument$PredicateWrapper
+ XXX.arguments.item.ItemPredicateArgument$Result
- XXX.arguments.item.package-info
- XXX.arguments.selector.EntitySelector
+ XXX.arguments.selector.EntitySelector$1
- XXX.arguments.selector.EntitySelectorParser
- XXX.arguments.selector.package-info
+ XXX.arguments.selector.SelectorPattern
+ XXX.chat.contents.KeybindContents
- XXX.chat.contents.KeybindResolver
+ XXX.chat.contents.NbtContents
- XXX.chat.contents.ObjectContents
+ XXX.chat.contents.package-info
+ XXX.chat.contents.PlainTextContents
- XXX.chat.contents.PlainTextContents$1
+ XXX.chat.contents.PlainTextContents$LiteralContents
- XXX.chat.contents.ScoreContents
+ XXX.chat.contents.SelectorContents
- XXX.chat.contents.TranslatableContents
+ XXX.chat.contents.TranslatableFormatException
- XXX.chat.numbers.BlankFormat
+ XXX.chat.numbers.BlankFormat$1
- XXX.chat.numbers.FixedFormat
+ XXX.chat.numbers.FixedFormat$1
- XXX.chat.numbers.NumberFormat
+ XXX.chat.numbers.NumberFormatType
- XXX.chat.numbers.NumberFormatTypes
+ XXX.chat.numbers.package-info
+ XXX.chat.numbers.StyledFormat
- XXX.chat.numbers.StyledFormat$1
+ XXX.commands.arguments.AngleArgument
- XXX.commands.arguments.AngleArgument$SingleAngle
+ XXX.commands.arguments.ArgumentSignatures
- XXX.commands.arguments.ArgumentSignatures$Entry
+ XXX.commands.arguments.ArgumentSignatures$Signer
- XXX.commands.arguments.ColorArgument
+ XXX.commands.arguments.ComponentArgument
- XXX.commands.arguments.CompoundTagArgument
+ XXX.commands.arguments.DimensionArgument
- XXX.commands.arguments.EntityAnchorArgument
+ XXX.commands.arguments.EntityAnchorArgument$Anchor
- XXX.commands.arguments.EntityArgument
+ XXX.commands.arguments.EntityArgument$Info
- XXX.commands.arguments.EntityArgument$Info$Template
+ XXX.commands.arguments.GameModeArgument
- XXX.commands.arguments.GameProfileArgument
+ XXX.commands.arguments.GameProfileArgument$Result
- XXX.commands.arguments.GameProfileArgument$SelectorResult
+ XXX.commands.arguments.HeightmapTypeArgument
- XXX.commands.arguments.HexColorArgument
+ XXX.commands.arguments.MessageArgument
- XXX.commands.arguments.MessageArgument$Message
+ XXX.commands.arguments.MessageArgument$Part
- XXX.commands.arguments.NbtPathArgument
+ XXX.commands.arguments.NbtPathArgument$AllElementsNode
- XXX.commands.arguments.NbtPathArgument$CompoundChildNode
+ XXX.commands.arguments.NbtPathArgument$IndexedElementNode
- XXX.commands.arguments.NbtPathArgument$MatchElementNode
+ XXX.commands.arguments.NbtPathArgument$MatchObjectNode
- XXX.commands.arguments.NbtPathArgument$MatchRootObjectNode
+ XXX.commands.arguments.NbtPathArgument$NbtPath
- XXX.commands.arguments.NbtPathArgument$Node
+ XXX.commands.arguments.NbtTagArgument
- XXX.commands.arguments.ObjectiveArgument
+ XXX.commands.arguments.ObjectiveCriteriaArgument
- XXX.commands.arguments.OperationArgument
+ XXX.commands.arguments.OperationArgument$Operation
- XXX.commands.arguments.OperationArgument$SimpleOperation
+ XXX.commands.arguments.package-info
+ XXX.commands.arguments.ParticleArgument
- XXX.commands.arguments.RangeArgument
+ XXX.commands.arguments.RangeArgument$Floats
- XXX.commands.arguments.RangeArgument$Ints
+ XXX.commands.arguments.ResourceArgument
- XXX.commands.arguments.ResourceArgument$Info
+ XXX.commands.arguments.ResourceArgument$Info$Template
- XXX.commands.arguments.ResourceKeyArgument
+ XXX.commands.arguments.ResourceKeyArgument$Info
- XXX.commands.arguments.ResourceKeyArgument$Info$Template
+ XXX.commands.arguments.ResourceLocationArgument
- XXX.commands.arguments.ResourceOrIdArgument
+ XXX.commands.arguments.ResourceOrIdArgument$DialogArgument
- XXX.commands.arguments.ResourceOrIdArgument$InlineResult
+ XXX.commands.arguments.ResourceOrIdArgument$LootModifierArgument
- XXX.commands.arguments.ResourceOrIdArgument$LootPredicateArgument
+ XXX.commands.arguments.ResourceOrIdArgument$LootTableArgument
- XXX.commands.arguments.ResourceOrIdArgument$ReferenceResult
+ XXX.commands.arguments.ResourceOrIdArgument$Result
- XXX.commands.arguments.ResourceOrTagArgument
+ XXX.commands.arguments.ResourceOrTagArgument$Info
- XXX.commands.arguments.ResourceOrTagArgument$Info$Template
+ XXX.commands.arguments.ResourceOrTagArgument$ResourceResult
- XXX.commands.arguments.ResourceOrTagArgument$Result
+ XXX.commands.arguments.ResourceOrTagArgument$TagResult
- XXX.commands.arguments.ResourceOrTagKeyArgument
+ XXX.commands.arguments.ResourceOrTagKeyArgument$Info
- XXX.commands.arguments.ResourceOrTagKeyArgument$Info$Template
+ XXX.commands.arguments.ResourceOrTagKeyArgument$ResourceResult
- XXX.commands.arguments.ResourceOrTagKeyArgument$Result
+ XXX.commands.arguments.ResourceOrTagKeyArgument$TagResult
- XXX.commands.arguments.ResourceSelectorArgument
+ XXX.commands.arguments.ResourceSelectorArgument$Info
- XXX.commands.arguments.ResourceSelectorArgument$Info$Template
- XXX.commands.arguments.ScoreboardSlotArgument
+ XXX.commands.arguments.ScoreHolderArgument
- XXX.commands.arguments.ScoreHolderArgument$Info
+ XXX.commands.arguments.ScoreHolderArgument$Info$Template
- XXX.commands.arguments.ScoreHolderArgument$Result
+ XXX.commands.arguments.ScoreHolderArgument$SelectorResult
+ XXX.commands.arguments.SignedArgument
- XXX.commands.arguments.SlotArgument
+ XXX.commands.arguments.SlotsArgument
- XXX.commands.arguments.StringRepresentableArgument
+ XXX.commands.arguments.StyleArgument
- XXX.commands.arguments.TeamArgument
+ XXX.commands.arguments.TemplateMirrorArgument
- XXX.commands.arguments.TemplateRotationArgument
+ XXX.commands.arguments.TimeArgument
- XXX.commands.arguments.TimeArgument$Info
+ XXX.commands.arguments.TimeArgument$Info$Template
- XXX.commands.arguments.UuidArgument
+ XXX.commands.arguments.WaypointArgument
+ XXX.commands.execution.ChainModifiers
- XXX.commands.execution.CommandQueueEntry
+ XXX.commands.execution.CustomCommandExecutor
- XXX.commands.execution.CustomCommandExecutor$CommandAdapter
+ XXX.commands.execution.CustomCommandExecutor$WithErrorHandling
- XXX.commands.execution.CustomModifierExecutor
+ XXX.commands.execution.CustomModifierExecutor$ModifierAdapter
- XXX.commands.execution.EntryAction
+ XXX.commands.execution.ExecutionContext
- XXX.commands.execution.ExecutionControl
+ XXX.commands.execution.ExecutionControl$1
- XXX.commands.execution.Frame
+ XXX.commands.execution.Frame$FrameControl
- XXX.commands.execution.package-info
- XXX.commands.execution.TraceCallbacks
+ XXX.commands.execution.UnboundEntryAction
- XXX.commands.functions.CommandFunction
+ XXX.commands.functions.FunctionBuilder
- XXX.commands.functions.InstantiatedFunction
+ XXX.commands.functions.MacroFunction
- XXX.commands.functions.MacroFunction$Entry
+ XXX.commands.functions.MacroFunction$MacroEntry
- XXX.commands.functions.MacroFunction$PlainTextEntry
+ XXX.commands.functions.package-info
+ XXX.commands.functions.PlainTextFunction
- XXX.commands.functions.StringTemplate
+ XXX.commands.synchronization.ArgumentTypeInfo
- XXX.commands.synchronization.ArgumentTypeInfo$Template
+ XXX.commands.synchronization.ArgumentTypeInfos
- XXX.commands.synchronization.ArgumentUtils
+ XXX.commands.synchronization.package-info
+ XXX.commands.synchronization.SingletonArgumentInfo
- XXX.commands.synchronization.SingletonArgumentInfo$Template
+ XXX.commands.synchronization.SuggestionProviders
- XXX.commands.synchronization.SuggestionProviders$RegisteredSuggestion
- XXX.common.custom.BeeDebugPayload
+ XXX.common.custom.BeeDebugPayload$BeeInfo
- XXX.common.custom.BrainDebugPayload
+ XXX.common.custom.BrainDebugPayload$BrainDump
- XXX.common.custom.BrandPayload
+ XXX.common.custom.BreezeDebugPayload
- XXX.common.custom.BreezeDebugPayload$BreezeInfo
+ XXX.common.custom.CustomPacketPayload
- XXX.common.custom.CustomPacketPayload$1
+ XXX.common.custom.CustomPacketPayload$FallbackProvider
- XXX.common.custom.CustomPacketPayload$Type
+ XXX.common.custom.CustomPacketPayload$TypeAndCodec
- XXX.common.custom.DiscardedPayload
+ XXX.common.custom.GameEventDebugPayload
- XXX.common.custom.GameEventListenerDebugPayload
+ XXX.common.custom.GameTestAddMarkerDebugPayload
- XXX.common.custom.GameTestClearMarkersDebugPayload
+ XXX.common.custom.GoalDebugPayload
- XXX.common.custom.GoalDebugPayload$DebugGoal
+ XXX.common.custom.HiveDebugPayload
- XXX.common.custom.HiveDebugPayload$HiveInfo
+ XXX.common.custom.NeighborUpdatesDebugPayload
+ XXX.common.custom.package-info
- XXX.common.custom.PathfindingDebugPayload
+ XXX.common.custom.PoiAddedDebugPayload
- XXX.common.custom.PoiRemovedDebugPayload
+ XXX.common.custom.PoiTicketCountDebugPayload
- XXX.common.custom.RaidsDebugPayload
+ XXX.common.custom.RedstoneWireOrientationsDebugPayload
- XXX.common.custom.RedstoneWireOrientationsDebugPayload$Wire
+ XXX.common.custom.StructuresDebugPayload
- XXX.common.custom.StructuresDebugPayload$PieceInfo
+ XXX.common.custom.VillageSectionsDebugPayload
- XXX.common.custom.WorldGenAttemptDebugPayload
+ XXX.component.predicates.AttributeModifiersPredicate
- XXX.component.predicates.AttributeModifiersPredicate$EntryPredicate
+ XXX.component.predicates.BundlePredicate
- XXX.component.predicates.ContainerPredicate
+ XXX.component.predicates.CustomDataPredicate
- XXX.component.predicates.DamagePredicate
+ XXX.component.predicates.DataComponentPredicate
- XXX.component.predicates.DataComponentPredicate$Single
+ XXX.component.predicates.DataComponentPredicate$Type
- XXX.component.predicates.DataComponentPredicates
+ XXX.component.predicates.EnchantmentsPredicate
- XXX.component.predicates.EnchantmentsPredicate$Enchantments
+ XXX.component.predicates.EnchantmentsPredicate$StoredEnchantments
- XXX.component.predicates.FireworkExplosionPredicate
+ XXX.component.predicates.FireworkExplosionPredicate$FireworkPredicate
- XXX.component.predicates.FireworksPredicate
+ XXX.component.predicates.JukeboxPlayablePredicate
- XXX.component.predicates.package-info
- XXX.component.predicates.PotionsPredicate
+ XXX.component.predicates.TrimPredicate
- XXX.component.predicates.WritableBookPredicate
+ XXX.component.predicates.WritableBookPredicate$PagePredicate
- XXX.component.predicates.WrittenBookPredicate
+ XXX.component.predicates.WrittenBookPredicate$PagePredicate
- XXX.contents.data.BlockDataSource
+ XXX.contents.data.DataSource
- XXX.contents.data.DataSources
+ XXX.contents.data.EntityDataSource
+ XXX.contents.data.package-info
- XXX.contents.data.StorageDataSource
- XXX.contents.objects.AtlasSprite
+ XXX.contents.objects.ObjectInfo
- XXX.contents.objects.ObjectInfos
- XXX.contents.objects.package-info
+ XXX.contents.objects.PlayerSprite
- XXX.core.cauldron.CauldronInteraction
+ XXX.core.cauldron.CauldronInteraction$InteractionMap
- XXX.core.cauldron.package-info
+ XXX.core.component.DataComponentExactPredicate
- XXX.core.component.DataComponentExactPredicate$Builder
+ XXX.core.component.DataComponentGetter
- XXX.core.component.DataComponentHolder
+ XXX.core.component.DataComponentMap
- XXX.core.component.DataComponentMap$1
+ XXX.core.component.DataComponentMap$2
- XXX.core.component.DataComponentMap$3
+ XXX.core.component.DataComponentMap$Builder
- XXX.core.component.DataComponentMap$Builder$SimpleMap
+ XXX.core.component.DataComponentPatch
- XXX.core.component.DataComponentPatch$1
+ XXX.core.component.DataComponentPatch$2
- XXX.core.component.DataComponentPatch$3
+ XXX.core.component.DataComponentPatch$Builder
- XXX.core.component.DataComponentPatch$CodecGetter
+ XXX.core.component.DataComponentPatch$PatchKey
- XXX.core.component.DataComponentPatch$SplitResult
- XXX.core.component.DataComponents
+ XXX.core.component.DataComponentType
- XXX.core.component.DataComponentType$Builder
+ XXX.core.component.DataComponentType$Builder$SimpleType
- XXX.core.component.package-info
+ XXX.core.component.PatchedDataComponentMap
- XXX.core.component.TypedDataComponent
+ XXX.core.component.TypedDataComponent$1
+ XXX.core.dispenser.BlockSource
- XXX.core.dispenser.BoatDispenseItemBehavior
+ XXX.core.dispenser.DefaultDispenseItemBehavior
- XXX.core.dispenser.DispenseItemBehavior
+ XXX.core.dispenser.DispenseItemBehavior$1
- XXX.core.dispenser.DispenseItemBehavior$10
+ XXX.core.dispenser.DispenseItemBehavior$11
- XXX.core.dispenser.DispenseItemBehavior$12
+ XXX.core.dispenser.DispenseItemBehavior$13
- XXX.core.dispenser.DispenseItemBehavior$14
+ XXX.core.dispenser.DispenseItemBehavior$15
- XXX.core.dispenser.DispenseItemBehavior$2
+ XXX.core.dispenser.DispenseItemBehavior$3
- XXX.core.dispenser.DispenseItemBehavior$4
+ XXX.core.dispenser.DispenseItemBehavior$5
- XXX.core.dispenser.DispenseItemBehavior$6
+ XXX.core.dispenser.DispenseItemBehavior$7
- XXX.core.dispenser.DispenseItemBehavior$8
+ XXX.core.dispenser.DispenseItemBehavior$9
- XXX.core.dispenser.EquipmentDispenseItemBehavior
+ XXX.core.dispenser.MinecartDispenseItemBehavior
- XXX.core.dispenser.OptionalDispenseItemBehavior
- XXX.core.dispenser.package-info
+ XXX.core.dispenser.ProjectileDispenseBehavior
- XXX.core.dispenser.ShearsDispenseItemBehavior
+ XXX.core.dispenser.ShulkerBoxDispenseBehavior
- XXX.core.particles.BlockParticleOption
+ XXX.core.particles.ColorParticleOption
- XXX.core.particles.DustColorTransitionOptions
+ XXX.core.particles.DustParticleOptions
- XXX.core.particles.ExplosionParticleInfo
+ XXX.core.particles.ItemParticleOption
+ XXX.core.particles.package-info
- XXX.core.particles.ParticleLimit
+ XXX.core.particles.ParticleOptions
- XXX.core.particles.ParticleType
+ XXX.core.particles.ParticleTypes
- XXX.core.particles.ParticleTypes$1
- XXX.core.particles.SpellParticleOption
+ XXX.core.particles.TrailParticleOption
- XXX.core.particles.VibrationParticleOption
- XXX.core.registries.BuiltInRegistries
+ XXX.core.registries.BuiltInRegistries$RegistryBootstrap
+ XXX.core.registries.package-info
- XXX.core.registries.Registries
+ XXX.crafting.display.DisplayContentsFactory
- XXX.crafting.display.DisplayContentsFactory$ForRemainders
+ XXX.crafting.display.DisplayContentsFactory$ForStacks
- XXX.crafting.display.FurnaceRecipeDisplay
+ XXX.crafting.display.package-info
+ XXX.crafting.display.RecipeDisplay
- XXX.crafting.display.RecipeDisplay$Type
+ XXX.crafting.display.RecipeDisplayEntry
- XXX.crafting.display.RecipeDisplayId
+ XXX.crafting.display.RecipeDisplays
- XXX.crafting.display.ShapedCraftingRecipeDisplay
+ XXX.crafting.display.ShapelessCraftingRecipeDisplay
- XXX.crafting.display.SlotDisplay
+ XXX.crafting.display.SlotDisplay$AnyFuel
- XXX.crafting.display.SlotDisplay$Composite
+ XXX.crafting.display.SlotDisplay$Empty
- XXX.crafting.display.SlotDisplay$ItemSlotDisplay
+ XXX.crafting.display.SlotDisplay$ItemStackContentsFactory
- XXX.crafting.display.SlotDisplay$ItemStackSlotDisplay
+ XXX.crafting.display.SlotDisplay$SmithingTrimDemoSlotDisplay
- XXX.crafting.display.SlotDisplay$TagSlotDisplay
+ XXX.crafting.display.SlotDisplay$Type
- XXX.crafting.display.SlotDisplay$WithRemainder
+ XXX.crafting.display.SlotDisplayContext
- XXX.crafting.display.SlotDisplays
+ XXX.crafting.display.SmithingRecipeDisplay
- XXX.crafting.display.StonecutterRecipeDisplay
+ XXX.data.advancements.AdvancementProvider
- XXX.data.advancements.AdvancementSubProvider
+ XXX.data.advancements.package-info
+ XXX.data.info.BiomeParametersDumpReport
- XXX.data.info.BlockListReport
+ XXX.data.info.CommandsReport
- XXX.data.info.DatapackStructureReport
+ XXX.data.info.DatapackStructureReport$CustomPackEntry
- XXX.data.info.DatapackStructureReport$Entry
+ XXX.data.info.DatapackStructureReport$Format
- XXX.data.info.DatapackStructureReport$Report
+ XXX.data.info.ItemListReport
- XXX.data.info.package-info
- XXX.data.info.PacketReport
+ XXX.data.info.RegistryDumpReport
+ XXX.data.loot.BlockLootSubProvider
- XXX.data.loot.EntityLootSubProvider
+ XXX.data.loot.LootTableProvider
- XXX.data.loot.LootTableProvider$MissingTableProblem
+ XXX.data.loot.LootTableProvider$SubProviderEntry
- XXX.data.loot.LootTableSubProvider
+ XXX.data.loot.package-info
+ XXX.data.metadata.package-info
- XXX.data.metadata.PackMetadataGenerator
+ XXX.data.recipes.package-info
+ XXX.data.recipes.RecipeBuilder
- XXX.data.recipes.RecipeBuilder$1
+ XXX.data.recipes.RecipeCategory
- XXX.data.recipes.RecipeOutput
+ XXX.data.recipes.RecipeProvider
- XXX.data.recipes.RecipeProvider$FamilyRecipeProvider
+ XXX.data.recipes.RecipeProvider$Runner
- XXX.data.recipes.RecipeProvider$Runner$1
+ XXX.data.recipes.ShapedRecipeBuilder
- XXX.data.recipes.ShapelessRecipeBuilder
+ XXX.data.recipes.SimpleCookingRecipeBuilder
- XXX.data.recipes.SingleItemRecipeBuilder
+ XXX.data.recipes.SmithingTransformRecipeBuilder
- XXX.data.recipes.SmithingTrimRecipeBuilder
+ XXX.data.recipes.SpecialRecipeBuilder
- XXX.data.recipes.TransmuteRecipeBuilder
- XXX.data.registries.package-info
- XXX.data.registries.RegistriesDatapackGenerator
+ XXX.data.registries.RegistryPatchGenerator
- XXX.data.registries.TradeRebalanceRegistries
+ XXX.data.registries.VanillaRegistries
+ XXX.data.structures.NbtToSnbt
- XXX.data.structures.package-info
- XXX.data.structures.SnbtDatafixer
+ XXX.data.structures.SnbtToNbt
- XXX.data.structures.SnbtToNbt$Filter
+ XXX.data.structures.SnbtToNbt$StructureConversionException
- XXX.data.structures.SnbtToNbt$TaskResult
+ XXX.data.structures.StructureUpdater
+ XXX.data.tags.BannerPatternTagsProvider
- XXX.data.tags.BiomeTagsProvider
+ XXX.data.tags.BlockItemTagsProvider
- XXX.data.tags.DamageTypeTagsProvider
+ XXX.data.tags.DialogTagsProvider
- XXX.data.tags.EnchantmentTagsProvider
+ XXX.data.tags.EntityTypeTagsProvider
- XXX.data.tags.FlatLevelGeneratorPresetTagsProvider
+ XXX.data.tags.FluidTagsProvider
- XXX.data.tags.GameEventTagsProvider
+ XXX.data.tags.InstrumentTagsProvider
- XXX.data.tags.IntrinsicHolderTagsProvider
+ XXX.data.tags.KeyTagProvider
+ XXX.data.tags.package-info
- XXX.data.tags.PaintingVariantTagsProvider
+ XXX.data.tags.PoiTypeTagsProvider
- XXX.data.tags.StructureTagsProvider
+ XXX.data.tags.TagAppender
- XXX.data.tags.TagAppender$1
+ XXX.data.tags.TagAppender$2
- XXX.data.tags.TagsProvider
+ XXX.data.tags.TagsProvider$1CombinedData
- XXX.data.tags.TagsProvider$TagLookup
+ XXX.data.tags.TradeRebalanceEnchantmentTagsProvider
- XXX.data.tags.VanillaBlockTagsProvider
+ XXX.data.tags.VanillaBlockTagsProvider$1
- XXX.data.tags.VanillaEnchantmentTagsProvider
+ XXX.data.tags.VanillaItemTagsProvider
- XXX.data.tags.VanillaItemTagsProvider$1
+ XXX.data.tags.VanillaItemTagsProvider$BlockToItemConverter
- XXX.data.tags.WorldPresetTagsProvider
- XXX.data.worldgen.AncientCityStructurePieces
+ XXX.data.worldgen.AncientCityStructurePools
- XXX.data.worldgen.BastionBridgePools
+ XXX.data.worldgen.BastionHoglinStablePools
- XXX.data.worldgen.BastionHousingUnitsPools
+ XXX.data.worldgen.BastionPieces
- XXX.data.worldgen.BastionSharedPools
+ XXX.data.worldgen.BastionTreasureRoomPools
- XXX.data.worldgen.BiomeDefaultFeatures
+ XXX.data.worldgen.BootstrapContext
- XXX.data.worldgen.Carvers
+ XXX.data.worldgen.DesertVillagePools
- XXX.data.worldgen.DimensionTypes
+ XXX.data.worldgen.NoiseData
- XXX.data.worldgen.package-info
- XXX.data.worldgen.PillagerOutpostPools
+ XXX.data.worldgen.PlainVillagePools
- XXX.data.worldgen.Pools
+ XXX.data.worldgen.ProcessorLists
- XXX.data.worldgen.SavannaVillagePools
+ XXX.data.worldgen.SnowyVillagePools
+ XXX.data.worldgen.Structures
- XXX.data.worldgen.StructureSets
- XXX.data.worldgen.SurfaceRuleData
+ XXX.data.worldgen.TaigaVillagePools
- XXX.data.worldgen.TerrainProvider
+ XXX.data.worldgen.TrailRuinsStructurePools
- XXX.data.worldgen.TrialChambersStructurePools
+ XXX.data.worldgen.VillagePools
+ XXX.datafix.fixes.AbstractArrowPickupFix
- XXX.datafix.fixes.AbstractBlockPropertyFix
+ XXX.datafix.fixes.AbstractPoiSectionFix
- XXX.datafix.fixes.AbstractUUIDFix
+ XXX.datafix.fixes.AddFieldFix
- XXX.datafix.fixes.AddFlagIfNotPresentFix
+ XXX.datafix.fixes.AddNewChoices
- XXX.datafix.fixes.AdvancementsFix
+ XXX.datafix.fixes.AdvancementsRenameFix
- XXX.datafix.fixes.AreaEffectCloudDurationScaleFix
+ XXX.datafix.fixes.AreaEffectCloudPotionFix
- XXX.datafix.fixes.AttributeIdPrefixFix
+ XXX.datafix.fixes.AttributeModifierIdFix
- XXX.datafix.fixes.AttributesRenameFix
+ XXX.datafix.fixes.AttributesRenameLegacy
- XXX.datafix.fixes.BannerEntityCustomNameToOverrideComponentFix
+ XXX.datafix.fixes.BannerPatternFormatFix
- XXX.datafix.fixes.BedItemColorFix
+ XXX.datafix.fixes.BeehiveFieldRenameFix
- XXX.datafix.fixes.BiomeFix
+ XXX.datafix.fixes.BitStorageAlignFix
- XXX.datafix.fixes.BlendingDataFix
+ XXX.datafix.fixes.BlendingDataRemoveFromNetherEndFix
- XXX.datafix.fixes.BlockEntityBannerColorFix
+ XXX.datafix.fixes.BlockEntityBlockStateFix
- XXX.datafix.fixes.BlockEntityCustomNameToComponentFix
+ XXX.datafix.fixes.BlockEntityFurnaceBurnTimeFix
- XXX.datafix.fixes.BlockEntityIdFix
+ XXX.datafix.fixes.BlockEntityJukeboxFix
- XXX.datafix.fixes.BlockEntityKeepPacked
+ XXX.datafix.fixes.BlockEntityRenameFix
- XXX.datafix.fixes.BlockEntityShulkerBoxColorFix
+ XXX.datafix.fixes.BlockEntitySignDoubleSidedEditableTextFix
- XXX.datafix.fixes.BlockEntityUUIDFix
+ XXX.datafix.fixes.BlockNameFlatteningFix
- XXX.datafix.fixes.BlockPosFormatAndRenamesFix
+ XXX.datafix.fixes.BlockPropertyRenameAndFix
- XXX.datafix.fixes.BlockRenameFix
+ XXX.datafix.fixes.BlockRenameFix$1
- XXX.datafix.fixes.BlockStateData
+ XXX.datafix.fixes.BlockStateStructureTemplateFix
- XXX.datafix.fixes.BoatSplitFix
+ XXX.datafix.fixes.CarvingStepRemoveFix
- XXX.datafix.fixes.CatTypeFix
+ XXX.datafix.fixes.CauldronRenameFix
- XXX.datafix.fixes.CavesAndCliffsRenames
+ XXX.datafix.fixes.ChestedHorsesInventoryZeroIndexingFix
- XXX.datafix.fixes.ChunkBedBlockEntityInjecterFix
+ XXX.datafix.fixes.ChunkBiomeFix
- XXX.datafix.fixes.ChunkDeleteIgnoredLightDataFix
+ XXX.datafix.fixes.ChunkDeleteLightFix
- XXX.datafix.fixes.ChunkHeightAndBiomeFix
+ XXX.datafix.fixes.ChunkLightRemoveFix
- XXX.datafix.fixes.ChunkPalettedStorageFix
+ XXX.datafix.fixes.ChunkPalettedStorageFix$DataLayer
- XXX.datafix.fixes.ChunkPalettedStorageFix$Direction
+ XXX.datafix.fixes.ChunkPalettedStorageFix$Direction$Axis
- XXX.datafix.fixes.ChunkPalettedStorageFix$Direction$AxisDirection
+ XXX.datafix.fixes.ChunkPalettedStorageFix$MappingConstants
- XXX.datafix.fixes.ChunkPalettedStorageFix$Section
+ XXX.datafix.fixes.ChunkPalettedStorageFix$UpgradeChunk
- XXX.datafix.fixes.ChunkProtoTickListFix
+ XXX.datafix.fixes.ChunkProtoTickListFix$PoorMansPalettedContainer
- XXX.datafix.fixes.ChunkRenamesFix
+ XXX.datafix.fixes.ChunkStatusFix
- XXX.datafix.fixes.ChunkStatusFix2
+ XXX.datafix.fixes.ChunkStructuresTemplateRenameFix
- XXX.datafix.fixes.ChunkTicketUnpackPosFix
+ XXX.datafix.fixes.ChunkToProtochunkFix
- XXX.datafix.fixes.ColorlessShulkerEntityFix
+ XXX.datafix.fixes.ContainerBlockEntityLockPredicateFix
- XXX.datafix.fixes.CopperGolemWeatherStateFix
+ XXX.datafix.fixes.CriteriaRenameFix
- XXX.datafix.fixes.CustomModelDataExpandFix
+ XXX.datafix.fixes.DataComponentRemainderFix
- XXX.datafix.fixes.DecoratedPotFieldRenameFix
+ XXX.datafix.fixes.DropChancesFormatFix
- XXX.datafix.fixes.DropInvalidSignDataFix
+ XXX.datafix.fixes.DyeItemRenameFix
- XXX.datafix.fixes.EffectDurationFix
+ XXX.datafix.fixes.EmptyItemInHotbarFix
- XXX.datafix.fixes.EmptyItemInVillagerTradeFix
+ XXX.datafix.fixes.EntityArmorStandSilentFix
- XXX.datafix.fixes.EntityAttributeBaseValueFix
+ XXX.datafix.fixes.EntityBlockStateFix
- XXX.datafix.fixes.EntityBrushableBlockFieldsRenameFix
+ XXX.datafix.fixes.EntityCatSplitFix
- XXX.datafix.fixes.EntityCodSalmonFix
+ XXX.datafix.fixes.EntityCustomNameToComponentFix
- XXX.datafix.fixes.EntityElderGuardianSplitFix
+ XXX.datafix.fixes.EntityEquipmentToArmorAndHandFix
- XXX.datafix.fixes.EntityFallDistanceFloatToDoubleFix
+ XXX.datafix.fixes.EntityFieldsRenameFix
- XXX.datafix.fixes.EntityGoatMissingStateFix
+ XXX.datafix.fixes.EntityHealthFix
- XXX.datafix.fixes.EntityHorseSaddleFix
+ XXX.datafix.fixes.EntityHorseSplitFix
- XXX.datafix.fixes.EntityIdFix
+ XXX.datafix.fixes.EntityItemFrameDirectionFix
- XXX.datafix.fixes.EntityMinecartIdentifiersFix
+ XXX.datafix.fixes.EntityPaintingItemFrameDirectionFix
- XXX.datafix.fixes.EntityPaintingMotiveFix
+ XXX.datafix.fixes.EntityProjectileOwnerFix
- XXX.datafix.fixes.EntityPufferfishRenameFix
+ XXX.datafix.fixes.EntityRavagerRenameFix
- XXX.datafix.fixes.EntityRedundantChanceTagsFix
+ XXX.datafix.fixes.EntityRenameFix
- XXX.datafix.fixes.EntityRidingToPassengersFix
+ XXX.datafix.fixes.EntitySalmonSizeFix
- XXX.datafix.fixes.EntityShulkerColorFix
+ XXX.datafix.fixes.EntityShulkerRotationFix
- XXX.datafix.fixes.EntitySkeletonSplitFix
+ XXX.datafix.fixes.EntitySpawnerItemVariantComponentFix
- XXX.datafix.fixes.EntitySpawnerItemVariantComponentFix$Fixer
+ XXX.datafix.fixes.EntityStringUuidFix
- XXX.datafix.fixes.EntityTheRenameningFix
+ XXX.datafix.fixes.EntityTippedArrowFix
- XXX.datafix.fixes.EntityUUIDFix
+ XXX.datafix.fixes.EntityVariantFix
- XXX.datafix.fixes.EntityWolfColorFix
+ XXX.datafix.fixes.EntityZombieSplitFix
- XXX.datafix.fixes.EntityZombieVillagerTypeFix
+ XXX.datafix.fixes.EntityZombifiedPiglinRenameFix
- XXX.datafix.fixes.EquipmentFormatFix
+ XXX.datafix.fixes.EquippableAssetRenameFix
- XXX.datafix.fixes.FeatureFlagRemoveFix
+ XXX.datafix.fixes.FilteredBooksFix
- XXX.datafix.fixes.FilteredSignsFix
+ XXX.datafix.fixes.FireResistantToDamageResistantComponentFix
- XXX.datafix.fixes.FixProjectileStoredItem
+ XXX.datafix.fixes.FixProjectileStoredItem$SubFixer
- XXX.datafix.fixes.FixWolfHealth
+ XXX.datafix.fixes.FoodToConsumableFix
+ XXX.datafix.fixes.ForcedChunkToTicketFix
- XXX.datafix.fixes.ForcePoiRebuild
- XXX.datafix.fixes.FurnaceRecipeFix
+ XXX.datafix.fixes.GoatHornIdFix
- XXX.datafix.fixes.GossipUUIDFix
+ XXX.datafix.fixes.HeightmapRenamingFix
- XXX.datafix.fixes.HorseBodyArmorItemFix
+ XXX.datafix.fixes.IglooMetadataRemovalFix
- XXX.datafix.fixes.InlineBlockPosFormatFix
+ XXX.datafix.fixes.InvalidBlockEntityLockFix
- XXX.datafix.fixes.InvalidLockComponentFix
+ XXX.datafix.fixes.ItemBannerColorFix
- XXX.datafix.fixes.ItemCustomNameToComponentFix
+ XXX.datafix.fixes.ItemIdFix
- XXX.datafix.fixes.ItemLoreFix
+ XXX.datafix.fixes.ItemPotionFix
- XXX.datafix.fixes.ItemRenameFix
+ XXX.datafix.fixes.ItemRenameFix$1
- XXX.datafix.fixes.ItemShulkerBoxColorFix
+ XXX.datafix.fixes.ItemSpawnEggFix
- XXX.datafix.fixes.ItemStackComponentizationFix
+ XXX.datafix.fixes.ItemStackComponentizationFix$ItemStackData
- XXX.datafix.fixes.ItemStackCustomNameToOverrideComponentFix
+ XXX.datafix.fixes.ItemStackEnchantmentNamesFix
- XXX.datafix.fixes.ItemStackMapIdFix
+ XXX.datafix.fixes.ItemStackSpawnEggFix
- XXX.datafix.fixes.ItemStackTagFix
+ XXX.datafix.fixes.ItemStackTagRemainderFix
- XXX.datafix.fixes.ItemStackTheFlatteningFix
+ XXX.datafix.fixes.ItemStackUUIDFix
- XXX.datafix.fixes.ItemWaterPotionFix
+ XXX.datafix.fixes.JigsawPropertiesFix
- XXX.datafix.fixes.JigsawRotationFix
+ XXX.datafix.fixes.JukeboxTicksSinceSongStartedFix
- XXX.datafix.fixes.LeavesFix
+ XXX.datafix.fixes.LeavesFix$LeavesSection
- XXX.datafix.fixes.LeavesFix$Section
+ XXX.datafix.fixes.LegacyDimensionIdFix
- XXX.datafix.fixes.LegacyDragonFightFix
+ XXX.datafix.fixes.LegacyHoverEventFix
- XXX.datafix.fixes.LegacyWorldBorderFix
+ XXX.datafix.schemas.package-info
- XXX.datafix.schemas.V4543
+ XXX.datafix.schemas.V501
- XXX.datafix.schemas.V700
+ XXX.datafix.schemas.V701
- XXX.datafix.schemas.V702
+ XXX.datafix.schemas.V703
- XXX.datafix.schemas.V704
+ XXX.datafix.schemas.V704$1
- XXX.datafix.schemas.V705
+ XXX.datafix.schemas.V705$1
- XXX.datafix.schemas.V808
+ XXX.datafix.schemas.V99
- XXX.datafix.schemas.V99$1
+ XXX.enchantment.effects.AddValue
- XXX.enchantment.effects.AllOf
+ XXX.enchantment.effects.AllOf$EntityEffects
- XXX.enchantment.effects.AllOf$LocationBasedEffects
+ XXX.enchantment.effects.AllOf$ValueEffects
- XXX.enchantment.effects.ApplyMobEffect
+ XXX.enchantment.effects.ChangeItemDamage
- XXX.enchantment.effects.DamageEntity
+ XXX.enchantment.effects.DamageImmunity
- XXX.enchantment.effects.EnchantmentAttributeEffect
+ XXX.enchantment.effects.EnchantmentEntityEffect
- XXX.enchantment.effects.EnchantmentLocationBasedEffect
+ XXX.enchantment.effects.EnchantmentValueEffect
- XXX.enchantment.effects.ExplodeEffect
+ XXX.enchantment.effects.Ignite
- XXX.enchantment.effects.MultiplyValue
- XXX.enchantment.effects.package-info
+ XXX.enchantment.effects.PlaySoundEffect
- XXX.enchantment.effects.RemoveBinomial
+ XXX.enchantment.effects.ReplaceBlock
- XXX.enchantment.effects.ReplaceDisk
+ XXX.enchantment.effects.RunFunction
- XXX.enchantment.effects.SetBlockProperties
+ XXX.enchantment.effects.SetValue
- XXX.enchantment.effects.SpawnParticlesEffect
+ XXX.enchantment.effects.SpawnParticlesEffect$PositionSource
- XXX.enchantment.effects.SpawnParticlesEffect$PositionSourceType
+ XXX.enchantment.effects.SpawnParticlesEffect$PositionSourceType$CoordinateSource
- XXX.enchantment.effects.SpawnParticlesEffect$VelocitySource
+ XXX.enchantment.effects.SummonEntityEffect
- XXX.enchantment.providers.EnchantmentProvider
+ XXX.enchantment.providers.EnchantmentProviderTypes
- XXX.enchantment.providers.EnchantmentsByCost
+ XXX.enchantment.providers.EnchantmentsByCostWithDifficulty
+ XXX.enchantment.providers.package-info
- XXX.enchantment.providers.SingleEnchantment
+ XXX.enchantment.providers.TradeRebalanceEnchantmentProviders
- XXX.enchantment.providers.VanillaEnchantmentProviders
- XXX.entity.decoration.Mannequin
+ XXX.entity.player.package-info
- XXX.entity.player.ProfileKeyPair
+ XXX.entity.player.ProfilePublicKey
- XXX.entity.player.ProfilePublicKey$Data
+ XXX.entity.player.ProfilePublicKey$ValidationException
- XXX.entity.player.StackedContents
+ XXX.entity.player.StackedContents$IngredientInfo
- XXX.entity.player.StackedContents$Output
+ XXX.entity.player.StackedContents$RecipePicker
- XXX.entity.player.StackedItemContents
- XXX.entity.projectile.AbstractArrow
+ XXX.entity.projectile.AbstractArrow$Pickup
- XXX.entity.projectile.AbstractHurtingProjectile
+ XXX.entity.projectile.AbstractThrownPotion
- XXX.entity.projectile.Arrow
+ XXX.entity.projectile.DragonFireball
- XXX.entity.projectile.EvokerFangs
+ XXX.entity.projectile.EyeOfEnder
- XXX.entity.projectile.Fireball
+ XXX.entity.projectile.FireworkRocketEntity
- XXX.entity.projectile.FishingHook
+ XXX.entity.projectile.FishingHook$FishHookState
- XXX.entity.projectile.FishingHook$OpenWaterType
+ XXX.entity.projectile.ItemSupplier
- XXX.entity.projectile.LargeFireball
+ XXX.entity.projectile.LlamaSpit
+ XXX.entity.projectile.package-info
- XXX.entity.projectile.Projectile
+ XXX.entity.projectile.Projectile$ProjectileFactory
- XXX.entity.projectile.ProjectileDeflection
+ XXX.entity.projectile.ProjectileUtil
- XXX.entity.projectile.ShulkerBullet
+ XXX.entity.projectile.SmallFireball
- XXX.entity.projectile.Snowball
+ XXX.entity.projectile.SpectralArrow
- XXX.entity.projectile.ThrowableItemProjectile
+ XXX.entity.projectile.ThrowableProjectile
- XXX.entity.projectile.ThrownEgg
+ XXX.entity.projectile.ThrownEnderpearl
- XXX.entity.projectile.ThrownExperienceBottle
+ XXX.entity.projectile.ThrownLingeringPotion
- XXX.entity.projectile.ThrownSplashPotion
+ XXX.entity.projectile.ThrownTrident
- XXX.entity.projectile.WitherSkull
+ XXX.entity.raid.package-info
- XXX.entity.raid.Raid
+ XXX.entity.raid.Raid$1
+ XXX.entity.raid.Raid$RaiderType
- XXX.entity.raid.Raid$RaidStatus
- XXX.entity.raid.Raider
+ XXX.entity.raid.Raider$HoldGroundAttackGoal
- XXX.entity.raid.Raider$ObtainRaidLeaderBannerGoal
+ XXX.entity.raid.Raider$RaiderCelebration
- XXX.entity.raid.Raider$RaiderMoveThroughVillageGoal
+ XXX.entity.raid.Raids
- XXX.entity.raid.Raids$RaidWithId
- XXX.entity.schedule.Activity
+ XXX.entity.schedule.Keyframe
- XXX.entity.schedule.package-info
- XXX.entity.schedule.Schedule
+ XXX.entity.schedule.ScheduleBuilder
- XXX.entity.schedule.ScheduleBuilder$ActivityTransition
+ XXX.entity.schedule.Timeline
+ XXX.entity.variant.BiomeCheck
- XXX.entity.variant.ModelAndTexture
+ XXX.entity.variant.MoonBrightnessCheck
- XXX.entity.variant.package-info
- XXX.entity.variant.PriorityProvider
+ XXX.entity.variant.PriorityProvider$Selector
- XXX.entity.variant.PriorityProvider$SelectorCondition
+ XXX.entity.variant.PriorityProvider$UnpackedEntry
- XXX.entity.variant.SpawnCondition
+ XXX.entity.variant.SpawnConditions
- XXX.entity.variant.SpawnContext
+ XXX.entity.variant.SpawnPrioritySelectors
- XXX.entity.variant.StructureCheck
+ XXX.entity.variant.VariantUtils
+ XXX.entity.vehicle.AbstractBoat
- XXX.entity.vehicle.AbstractBoat$Status
+ XXX.entity.vehicle.AbstractChestBoat
- XXX.entity.vehicle.AbstractMinecart
+ XXX.entity.vehicle.AbstractMinecartContainer
- XXX.entity.vehicle.Boat
+ XXX.entity.vehicle.ChestBoat
- XXX.entity.vehicle.ChestRaft
+ XXX.entity.vehicle.ContainerEntity
- XXX.entity.vehicle.ContainerEntity$1
+ XXX.entity.vehicle.DismountHelper
- XXX.entity.vehicle.Minecart
+ XXX.entity.vehicle.MinecartBehavior
- XXX.entity.vehicle.MinecartChest
+ XXX.entity.vehicle.MinecartCommandBlock
- XXX.entity.vehicle.MinecartCommandBlock$MinecartCommandBase
+ XXX.entity.vehicle.MinecartFurnace
- XXX.entity.vehicle.MinecartHopper
+ XXX.entity.vehicle.MinecartSpawner
- XXX.entity.vehicle.MinecartSpawner$1
+ XXX.entity.vehicle.MinecartTNT
- XXX.entity.vehicle.NewMinecartBehavior
+ XXX.entity.vehicle.NewMinecartBehavior$1
- XXX.entity.vehicle.NewMinecartBehavior$MinecartStep
+ XXX.entity.vehicle.NewMinecartBehavior$StepPartialTicks
- XXX.entity.vehicle.NewMinecartBehavior$TrackIteration
+ XXX.entity.vehicle.OldMinecartBehavior
- XXX.entity.vehicle.OldMinecartBehavior$1
+ XXX.entity.vehicle.package-info
+ XXX.entity.vehicle.Raft
- XXX.entity.vehicle.VehicleEntity
+ XXX.equipment.trim.ArmorTrim
- XXX.equipment.trim.MaterialAssetGroup
+ XXX.equipment.trim.MaterialAssetGroup$AssetInfo
- XXX.equipment.trim.package-info
- XXX.equipment.trim.TrimMaterial
+ XXX.equipment.trim.TrimMaterials
- XXX.equipment.trim.TrimPattern
+ XXX.equipment.trim.TrimPatterns
+ XXX.execution.tasks.BuildContexts
- XXX.execution.tasks.BuildContexts$Continuation
+ XXX.execution.tasks.BuildContexts$TopLevel
- XXX.execution.tasks.BuildContexts$Unbound
+ XXX.execution.tasks.CallFunction
- XXX.execution.tasks.ContinuationTask
+ XXX.execution.tasks.ContinuationTask$TaskProvider
- XXX.execution.tasks.ExecuteCommand
+ XXX.execution.tasks.FallthroughTask
- XXX.execution.tasks.IsolatedCall
+ XXX.execution.tasks.package-info
+ XXX.gametest.framework.BlockBasedTestInstance
- XXX.gametest.framework.BuiltinTestFunctions
+ XXX.gametest.framework.ExhaustedAttemptsException
- XXX.gametest.framework.FailedTestTracker
+ XXX.gametest.framework.FunctionGameTestInstance
- XXX.gametest.framework.GameTestAssertException
+ XXX.gametest.framework.GameTestAssertPosException
- XXX.gametest.framework.GameTestBatch
+ XXX.gametest.framework.GameTestBatchFactory
- XXX.gametest.framework.GameTestBatchFactory$TestDecorator
+ XXX.gametest.framework.GameTestBatchListener
- XXX.gametest.framework.GameTestEnvironments
+ XXX.gametest.framework.GameTestEvent
- XXX.gametest.framework.GameTestException
+ XXX.gametest.framework.GameTestHelper
- XXX.gametest.framework.GameTestHelper$1
+ XXX.gametest.framework.GameTestHelper$2
- XXX.gametest.framework.GameTestHelper$3
+ XXX.gametest.framework.GameTestInfo
- XXX.gametest.framework.GameTestInstance
+ XXX.gametest.framework.GameTestInstances
- XXX.gametest.framework.GameTestListener
+ XXX.gametest.framework.GameTestMainUtil
- XXX.gametest.framework.GameTestRunner
+ XXX.gametest.framework.GameTestRunner$1
- XXX.gametest.framework.GameTestRunner$Builder
+ XXX.gametest.framework.GameTestRunner$GameTestBatcher
- XXX.gametest.framework.GameTestRunner$StructureSpawner
+ XXX.gametest.framework.GameTestSequence
- XXX.gametest.framework.GameTestSequence$Condition
+ XXX.gametest.framework.GameTestServer
- XXX.gametest.framework.GameTestServer$1
+ XXX.gametest.framework.GameTestServer$MockProfileResolver
- XXX.gametest.framework.GameTestServer$MockUserNameToIdResolver
+ XXX.gametest.framework.GameTestTicker
- XXX.gametest.framework.GameTestTicker$State
+ XXX.gametest.framework.GameTestTimeoutException
- XXX.gametest.framework.GeneratedTest
+ XXX.gametest.framework.GlobalTestReporter
- XXX.gametest.framework.JUnitLikeTestReporter
+ XXX.gametest.framework.LogTestReporter
- XXX.gametest.framework.MultipleTestTracker
+ XXX.gametest.framework.MultipleTestTracker$1
- XXX.gametest.framework.package-info
- XXX.gametest.framework.ReportGameListener
+ XXX.gametest.framework.RetryOptions
- XXX.gametest.framework.StructureGridSpawner
+ XXX.gametest.framework.StructureUtils
- XXX.gametest.framework.StructureUtils$1
+ XXX.gametest.framework.TestCommand
- XXX.gametest.framework.TestCommand$TestBatchSummaryDisplayer
+ XXX.gametest.framework.TestCommand$TestSummaryDisplayer
- XXX.gametest.framework.TestData
+ XXX.gametest.framework.TestEnvironmentDefinition
- XXX.gametest.framework.TestEnvironmentDefinition$AllOf
+ XXX.gametest.framework.TestEnvironmentDefinition$Functions
- XXX.gametest.framework.TestEnvironmentDefinition$SetGameRules
+ XXX.gametest.framework.TestEnvironmentDefinition$SetGameRules$Entry
- XXX.gametest.framework.TestEnvironmentDefinition$TimeOfDay
+ XXX.gametest.framework.TestEnvironmentDefinition$Weather
- XXX.gametest.framework.TestEnvironmentDefinition$Weather$Type
+ XXX.gametest.framework.TestFinder
- XXX.gametest.framework.TestFinder$Builder
+ XXX.gametest.framework.TestFunctionLoader
- XXX.gametest.framework.TestInstanceFinder
+ XXX.gametest.framework.TestPosFinder
- XXX.gametest.framework.TestReporter
+ XXX.gametest.framework.UnknownGameTestException
+ XXX.inventory.tooltip.BundleTooltip
+ XXX.inventory.tooltip.package-info
- XXX.inventory.tooltip.TooltipComponent
+ XXX.item.alchemy.package-info
+ XXX.item.alchemy.Potion
- XXX.item.alchemy.PotionBrewing
+ XXX.item.alchemy.PotionBrewing$Builder
- XXX.item.alchemy.PotionBrewing$Mix
+ XXX.item.alchemy.PotionContents
- XXX.item.alchemy.Potions
- XXX.item.component.Bees
+ XXX.item.component.BlockItemStateProperties
- XXX.item.component.BlocksAttacks
+ XXX.item.component.BlocksAttacks$DamageReduction
- XXX.item.component.BlocksAttacks$ItemDamageFunction
+ XXX.item.component.BookContent
- XXX.item.component.BundleContents
+ XXX.item.component.BundleContents$Mutable
- XXX.item.component.ChargedProjectiles
+ XXX.item.component.Consumable
- XXX.item.component.Consumable$Builder
+ XXX.item.component.Consumable$OverrideConsumeSound
- XXX.item.component.ConsumableListener
+ XXX.item.component.Consumables
- XXX.item.component.CustomData
+ XXX.item.component.CustomModelData
- XXX.item.component.DamageResistant
+ XXX.item.component.DeathProtection
- XXX.item.component.DebugStickState
+ XXX.item.component.DyedItemColor
- XXX.item.component.FireworkExplosion
+ XXX.item.component.FireworkExplosion$Shape
- XXX.item.component.Fireworks
+ XXX.item.component.InstrumentComponent
- XXX.item.component.ItemAttributeModifiers
+ XXX.item.component.ItemAttributeModifiers$1
- XXX.item.component.ItemAttributeModifiers$Builder
+ XXX.item.component.ItemAttributeModifiers$Display
- XXX.item.component.ItemAttributeModifiers$Display$Default
+ XXX.item.component.ItemAttributeModifiers$Display$Hidden
- XXX.item.component.ItemAttributeModifiers$Display$OverrideText
+ XXX.item.component.ItemAttributeModifiers$Display$Type
- XXX.item.component.ItemAttributeModifiers$Entry
+ XXX.item.component.ItemContainerContents
- XXX.item.component.ItemContainerContents$Slot
+ XXX.item.component.ItemLore
- XXX.item.component.LodestoneTracker
+ XXX.item.component.MapDecorations
- XXX.item.component.MapDecorations$Entry
+ XXX.item.component.MapItemColor
- XXX.item.component.MapPostProcessing
+ XXX.item.component.OminousBottleAmplifier
- XXX.item.component.package-info
- XXX.item.component.ProvidesTrimMaterial
+ XXX.item.component.ResolvableProfile
- XXX.item.component.ResolvableProfile$Dynamic
+ XXX.item.component.ResolvableProfile$Partial
- XXX.item.component.ResolvableProfile$Static
+ XXX.item.component.SeededContainerLoot
- XXX.item.component.SuspiciousStewEffects
+ XXX.item.component.SuspiciousStewEffects$Entry
- XXX.item.component.Tool
+ XXX.item.component.Tool$Rule
- XXX.item.component.TooltipDisplay
+ XXX.item.component.TooltipProvider
- XXX.item.component.TypedEntityData
+ XXX.item.component.TypedEntityData$1
- XXX.item.component.UseCooldown
+ XXX.item.component.UseRemainder
- XXX.item.component.UseRemainder$OnExtraCreatedRemainder
+ XXX.item.component.Weapon
- XXX.item.component.WritableBookContent
+ XXX.item.component.WrittenBookContent
+ XXX.item.consume_effects.ApplyStatusEffectsConsumeEffect
- XXX.item.consume_effects.ClearAllStatusEffectsConsumeEffect
+ XXX.item.consume_effects.ConsumeEffect
- XXX.item.consume_effects.ConsumeEffect$Type
- XXX.item.consume_effects.package-info
+ XXX.item.consume_effects.PlaySoundConsumeEffect
- XXX.item.consume_effects.RemoveStatusEffectsConsumeEffect
+ XXX.item.consume_effects.TeleportRandomlyConsumeEffect
+ XXX.item.context.BlockPlaceContext
- XXX.item.context.DirectionalPlaceContext
+ XXX.item.context.DirectionalPlaceContext$1
+ XXX.item.context.package-info
- XXX.item.context.UseOnContext
- XXX.item.crafting.AbstractCookingRecipe
+ XXX.item.crafting.AbstractCookingRecipe$Factory
- XXX.item.crafting.AbstractCookingRecipe$Serializer
+ XXX.item.crafting.ArmorDyeRecipe
- XXX.item.crafting.BannerDuplicateRecipe
+ XXX.item.crafting.BlastingRecipe
- XXX.item.crafting.BlastingRecipe$1
+ XXX.item.crafting.BookCloningRecipe
- XXX.item.crafting.CampfireCookingRecipe
+ XXX.item.crafting.CookingBookCategory
- XXX.item.crafting.CraftingBookCategory
+ XXX.item.crafting.CraftingInput
- XXX.item.crafting.CraftingInput$Positioned
+ XXX.item.crafting.CraftingRecipe
- XXX.item.crafting.CraftingRecipe$1
+ XXX.item.crafting.CustomRecipe
- XXX.item.crafting.CustomRecipe$Serializer
+ XXX.item.crafting.CustomRecipe$Serializer$Factory
- XXX.item.crafting.DecoratedPotRecipe
+ XXX.item.crafting.ExtendedRecipeBookCategory
- XXX.item.crafting.FireworkRocketRecipe
+ XXX.item.crafting.FireworkStarFadeRecipe
- XXX.item.crafting.FireworkStarRecipe
+ XXX.item.crafting.Ingredient
- XXX.item.crafting.MapCloningRecipe
+ XXX.item.crafting.MapExtendingRecipe
- XXX.item.crafting.package-info
- XXX.item.crafting.PlacementInfo
+ XXX.item.crafting.Recipe
- XXX.item.crafting.RecipeAccess
+ XXX.item.crafting.RecipeBookCategories
- XXX.item.crafting.RecipeBookCategory
+ XXX.item.crafting.RecipeCache
- XXX.item.crafting.RecipeCache$Entry
+ XXX.item.crafting.RecipeHolder
- XXX.item.crafting.RecipeInput
+ XXX.item.crafting.RecipeManager
- XXX.item.crafting.RecipeManager$1
+ XXX.item.crafting.RecipeManager$CachedCheck
- XXX.item.crafting.RecipeManager$IngredientCollector
+ XXX.item.crafting.RecipeManager$IngredientExtractor
- XXX.item.crafting.RecipeManager$ServerDisplayInfo
+ XXX.item.crafting.RecipeMap
- XXX.item.crafting.RecipePropertySet
+ XXX.item.crafting.RecipeSerializer
- XXX.item.crafting.RecipeType
+ XXX.item.crafting.RecipeType$1
- XXX.item.crafting.RepairItemRecipe
+ XXX.item.crafting.SelectableRecipe
- XXX.item.crafting.SelectableRecipe$SingleInputEntry
+ XXX.item.crafting.SelectableRecipe$SingleInputSet
- XXX.item.crafting.ShapedRecipe
+ XXX.item.crafting.ShapedRecipe$Serializer
- XXX.item.crafting.ShapedRecipePattern
+ XXX.item.crafting.ShapedRecipePattern$Data
- XXX.item.crafting.ShapelessRecipe
+ XXX.item.crafting.ShapelessRecipe$Serializer
- XXX.item.crafting.ShieldDecorationRecipe
+ XXX.item.crafting.SingleItemRecipe
- XXX.item.crafting.SingleItemRecipe$Factory
+ XXX.item.crafting.SingleItemRecipe$Serializer
- XXX.item.crafting.SingleRecipeInput
+ XXX.item.crafting.SmeltingRecipe
- XXX.item.crafting.SmeltingRecipe$1
+ XXX.item.crafting.SmithingRecipe
- XXX.item.crafting.SmithingRecipeInput
+ XXX.item.crafting.SmithingTransformRecipe
- XXX.item.crafting.SmithingTransformRecipe$Serializer
+ XXX.item.crafting.SmithingTrimRecipe
- XXX.item.crafting.SmithingTrimRecipe$Serializer
+ XXX.item.crafting.SmokingRecipe
- XXX.item.crafting.StonecutterRecipe
+ XXX.item.crafting.TippedArrowRecipe
- XXX.item.crafting.TransmuteRecipe
+ XXX.item.crafting.TransmuteRecipe$Serializer
- XXX.item.crafting.TransmuteResult
+ XXX.item.enchantment.ConditionalEffect
- XXX.item.enchantment.Enchantable
+ XXX.item.enchantment.EnchantedItemInUse
- XXX.item.enchantment.Enchantment
+ XXX.item.enchantment.Enchantment$1
- XXX.item.enchantment.Enchantment$Builder
+ XXX.item.enchantment.Enchantment$Cost
- XXX.item.enchantment.Enchantment$EnchantmentDefinition
+ XXX.item.enchantment.EnchantmentEffectComponents
- XXX.item.enchantment.EnchantmentHelper
+ XXX.item.enchantment.EnchantmentHelper$EnchantmentInSlotVisitor
- XXX.item.enchantment.EnchantmentHelper$EnchantmentVisitor
+ XXX.item.enchantment.EnchantmentInstance
+ XXX.item.enchantment.Enchantments
- XXX.item.enchantment.EnchantmentTarget
- XXX.item.enchantment.ItemEnchantments
+ XXX.item.enchantment.ItemEnchantments$Mutable
- XXX.item.enchantment.LevelBasedValue
+ XXX.item.enchantment.LevelBasedValue$Clamped
- XXX.item.enchantment.LevelBasedValue$Constant
+ XXX.item.enchantment.LevelBasedValue$Fraction
- XXX.item.enchantment.LevelBasedValue$LevelsSquared
+ XXX.item.enchantment.LevelBasedValue$Linear
- XXX.item.enchantment.LevelBasedValue$Lookup
+ XXX.item.enchantment.package-info
+ XXX.item.enchantment.Repairable
- XXX.item.enchantment.TargetedConditionalEffect
- XXX.item.equipment.AllowedEntitiesProvider
+ XXX.item.equipment.ArmorMaterial
- XXX.item.equipment.ArmorMaterials
+ XXX.item.equipment.ArmorType
- XXX.item.equipment.EquipmentAsset
+ XXX.item.equipment.EquipmentAssets
- XXX.item.equipment.Equippable
+ XXX.item.equipment.Equippable$Builder
- XXX.item.equipment.package-info
- XXX.item.trading.ItemCost
+ XXX.item.trading.Merchant
- XXX.item.trading.MerchantOffer
+ XXX.item.trading.MerchantOffers
- XXX.item.trading.package-info
+ XXX.jfr.callback.package-info
- XXX.jfr.callback.ProfiledDuration
- XXX.jfr.event.ChunkGenerationEvent
+ XXX.jfr.event.ChunkGenerationEvent$Fields
- XXX.jfr.event.ChunkRegionIoEvent
+ XXX.jfr.event.ChunkRegionIoEvent$Fields
- XXX.jfr.event.ChunkRegionReadEvent
+ XXX.jfr.event.ChunkRegionWriteEvent
- XXX.jfr.event.NetworkSummaryEvent
+ XXX.jfr.event.NetworkSummaryEvent$Fields
- XXX.jfr.event.NetworkSummaryEvent$SumAggregation
- XXX.jfr.event.package-info
+ XXX.jfr.event.PacketEvent
- XXX.jfr.event.PacketEvent$Fields
+ XXX.jfr.event.PacketReceivedEvent
- XXX.jfr.event.PacketSentEvent
+ XXX.jfr.event.ServerTickTimeEvent
- XXX.jfr.event.ServerTickTimeEvent$Fields
+ XXX.jfr.event.StructureGenerationEvent
- XXX.jfr.event.StructureGenerationEvent$Fields
+ XXX.jfr.event.WorldLoadFinishedEvent
- XXX.jfr.parse.JfrStatsParser
+ XXX.jfr.parse.JfrStatsParser$1
- XXX.jfr.parse.JfrStatsParser$MutableCountAndSize
+ XXX.jfr.parse.JfrStatsResult
- XXX.jfr.parse.package-info
+ XXX.jfr.serialize.JfrResultJsonSerializer
- XXX.jfr.serialize.package-info
+ XXX.jfr.stats.ChunkGenStat
- XXX.jfr.stats.ChunkIdentification
+ XXX.jfr.stats.CpuLoadStat
- XXX.jfr.stats.FileIOStat
+ XXX.jfr.stats.FileIOStat$Summary
- XXX.jfr.stats.GcHeapStat
+ XXX.jfr.stats.GcHeapStat$Summary
- XXX.jfr.stats.GcHeapStat$Timing
+ XXX.jfr.stats.IoSummary
- XXX.jfr.stats.IoSummary$CountAndSize
- XXX.jfr.stats.package-info
+ XXX.jfr.stats.PacketIdentification
- XXX.jfr.stats.StructureGenStat
+ XXX.jfr.stats.ThreadAllocationStat
- XXX.jfr.stats.ThreadAllocationStat$Summary
+ XXX.jfr.stats.TickTimeStat
- XXX.jfr.stats.TimedStat
+ XXX.jfr.stats.TimedStatSummary
+ XXX.level.border.BorderStatus
- XXX.level.border.package-info
- XXX.level.border.WorldBorder
+ XXX.level.border.WorldBorder$BorderExtent
- XXX.level.border.WorldBorder$DistancePerDirection
+ XXX.level.border.WorldBorder$MovingBorderExtent
- XXX.level.border.WorldBorder$Settings
+ XXX.level.border.WorldBorder$StaticBorderExtent
+ XXX.level.chunk.BlockColumn
- XXX.level.chunk.BulkSectionAccess
+ XXX.level.chunk.CarvingMask
- XXX.level.chunk.CarvingMask$Mask
+ XXX.level.chunk.ChunkAccess
- XXX.level.chunk.ChunkAccess$ChunkPathElement
+ XXX.level.chunk.ChunkAccess$PackedTicks
- XXX.level.chunk.ChunkGenerator
- XXX.level.chunk.ChunkGenerators
+ XXX.level.chunk.ChunkGeneratorStructureState
+ XXX.level.chunk.ChunkSource
- XXX.level.chunk.Configuration
- XXX.level.chunk.Configuration$Simple
+ XXX.level.chunk.PalettedContainer$CountConsumer
- XXX.level.chunk.PalettedContainer$Data
+ XXX.level.chunk.PalettedContainer$Strategy
+ XXX.level.chunk.PalettedContainer$Strategy$2
- XXX.level.chunk.PalettedContainerRO
+ XXX.level.chunk.PalettedContainerRO$PackedData
- XXX.level.chunk.PalettedContainerRO$Unpacker
+ XXX.level.chunk.ProtoChunk
- XXX.level.chunk.SingleValuePalette
- XXX.level.chunk.Strategy$1
+ XXX.login.custom.CustomQueryAnswerPayload
- XXX.login.custom.CustomQueryPayload
+ XXX.login.custom.DiscardedQueryAnswerPayload
- XXX.login.custom.DiscardedQueryPayload
+ XXX.login.custom.package-info
- XXX.loot.packs.LootData
+ XXX.loot.packs.package-info
+ XXX.loot.packs.TradeRebalanceChestLoot
- XXX.loot.packs.TradeRebalanceLootTableProvider
+ XXX.loot.packs.VanillaArchaeologyLoot
- XXX.loot.packs.VanillaBlockInteractLoot
+ XXX.loot.packs.VanillaBlockLoot
- XXX.loot.packs.VanillaChargedCreeperExplosionLoot
+ XXX.loot.packs.VanillaChargedCreeperExplosionLoot$Entry
- XXX.loot.packs.VanillaChestLoot
+ XXX.loot.packs.VanillaEntityInteractLoot
- XXX.loot.packs.VanillaEntityLoot
+ XXX.loot.packs.VanillaEquipmentLoot
- XXX.loot.packs.VanillaFishingLoot
+ XXX.loot.packs.VanillaGiftLoot
- XXX.loot.packs.VanillaLootTableProvider
+ XXX.loot.packs.VanillaPiglinBarterLoot
- XXX.loot.packs.VanillaShearingLoot
- XXX.metrics.profiling.ActiveMetricsRecorder
+ XXX.metrics.profiling.InactiveMetricsRecorder
- XXX.metrics.profiling.MetricsRecorder
+ XXX.metrics.profiling.package-info
+ XXX.metrics.profiling.ProfilerSamplerAdapter
- XXX.metrics.profiling.ServerMetricsSamplersProvider
+ XXX.metrics.profiling.ServerMetricsSamplersProvider$1
- XXX.metrics.profiling.ServerMetricsSamplersProvider$CpuStats
- XXX.metrics.storage.MetricsPersister
- XXX.metrics.storage.package-info
+ XXX.metrics.storage.RecordedDeviation
- XXX.minecraft.advancements.package-info
+ XXX.minecraft.commands.BrigadierExceptions
- XXX.minecraft.commands.CacheableFunction
+ XXX.minecraft.commands.CommandBuildContext
- XXX.minecraft.commands.CommandBuildContext$1
+ XXX.minecraft.commands.CommandResultCallback
- XXX.minecraft.commands.CommandResultCallback$1
+ XXX.minecraft.commands.Commands
- XXX.minecraft.commands.Commands$1
+ XXX.minecraft.commands.Commands$2
- XXX.minecraft.commands.Commands$2$1
+ XXX.minecraft.commands.Commands$CommandSelection
- XXX.minecraft.commands.Commands$ParseFunction
+ XXX.minecraft.commands.CommandSigningContext
- XXX.minecraft.commands.CommandSigningContext$1
+ XXX.minecraft.commands.CommandSigningContext$SignedArguments
- XXX.minecraft.commands.CommandSource
+ XXX.minecraft.commands.CommandSource$1
- XXX.minecraft.commands.CommandSourceStack
+ XXX.minecraft.commands.ExecutionCommandSource
- XXX.minecraft.commands.FunctionInstantiationException
- XXX.minecraft.commands.package-info
+ XXX.minecraft.commands.ParserUtils
- XXX.minecraft.commands.PermissionSource
+ XXX.minecraft.commands.PermissionSource$Check
- XXX.minecraft.commands.SharedSuggestionProvider
+ XXX.minecraft.commands.SharedSuggestionProvider$ElementSuggestionType
- XXX.minecraft.commands.SharedSuggestionProvider$TextCoordinates
- XXX.minecraft.core.AxisCycle
+ XXX.minecraft.core.AxisCycle$1
- XXX.minecraft.core.AxisCycle$2
+ XXX.minecraft.core.AxisCycle$3
- XXX.minecraft.core.BlockBox
+ XXX.minecraft.core.BlockBox$1
- XXX.minecraft.core.BlockMath
+ XXX.minecraft.core.BlockPos
- XXX.minecraft.core.BlockPos$1
+ XXX.minecraft.core.BlockPos$2
- XXX.minecraft.core.BlockPos$3
+ XXX.minecraft.core.BlockPos$4
- XXX.minecraft.core.BlockPos$5
+ XXX.minecraft.core.BlockPos$6
- XXX.minecraft.core.BlockPos$7
+ XXX.minecraft.core.BlockPos$MutableBlockPos
- XXX.minecraft.core.BlockPos$TraversalNodeStatus
+ XXX.minecraft.core.ClientAsset
- XXX.minecraft.core.Cloner
+ XXX.minecraft.core.Cloner$Factory
- XXX.minecraft.core.Cursor3D
+ XXX.minecraft.core.DefaultedMappedRegistry
- XXX.minecraft.core.DefaultedRegistry
+ XXX.minecraft.core.Direction
- XXX.minecraft.core.Direction$Axis
+ XXX.minecraft.core.Direction$Axis$1
- XXX.minecraft.core.Direction$Axis$2
+ XXX.minecraft.core.Direction$Axis$3
- XXX.minecraft.core.Direction$AxisDirection
+ XXX.minecraft.core.Direction$Plane
- XXX.minecraft.core.Direction8
+ XXX.minecraft.core.FrontAndTop
- XXX.minecraft.core.GlobalPos
+ XXX.minecraft.core.Holder
- XXX.minecraft.core.Holder$Direct
+ XXX.minecraft.core.Holder$Kind
- XXX.minecraft.core.Holder$Reference
+ XXX.minecraft.core.Holder$Reference$Type
- XXX.minecraft.core.HolderGetter
+ XXX.minecraft.core.HolderGetter$Provider
- XXX.minecraft.core.HolderLookup
+ XXX.minecraft.core.HolderLookup$Provider
- XXX.minecraft.core.HolderLookup$Provider$1
+ XXX.minecraft.core.HolderLookup$RegistryLookup
- XXX.minecraft.core.HolderLookup$RegistryLookup$1
+ XXX.minecraft.core.HolderLookup$RegistryLookup$Delegate
- XXX.minecraft.core.HolderOwner
+ XXX.minecraft.core.HolderSet
- XXX.minecraft.core.HolderSet$1
+ XXX.minecraft.core.HolderSet$Direct
- XXX.minecraft.core.HolderSet$ListBacked
+ XXX.minecraft.core.HolderSet$Named
- XXX.minecraft.core.IdMap
+ XXX.minecraft.core.IdMapper
- XXX.minecraft.core.LayeredRegistryAccess
+ XXX.minecraft.core.MappedRegistry
- XXX.minecraft.core.MappedRegistry$1
+ XXX.minecraft.core.MappedRegistry$2
- XXX.minecraft.core.MappedRegistry$3
+ XXX.minecraft.core.MappedRegistry$TagSet
- XXX.minecraft.core.MappedRegistry$TagSet$1
+ XXX.minecraft.core.MappedRegistry$TagSet$2
- XXX.minecraft.core.NonNullList
+ XXX.minecraft.core.package-info
+ XXX.minecraft.core.Position
- XXX.minecraft.core.QuartPos
+ XXX.minecraft.core.RegistrationInfo
- XXX.minecraft.core.Registry
+ XXX.minecraft.core.Registry$1
- XXX.minecraft.core.Registry$PendingTags
+ XXX.minecraft.core.RegistryAccess
- XXX.minecraft.core.RegistryAccess$1
+ XXX.minecraft.core.RegistryAccess$1FrozenAccess
- XXX.minecraft.core.RegistryAccess$Frozen
+ XXX.minecraft.core.RegistryAccess$ImmutableRegistryAccess
- XXX.minecraft.core.RegistryAccess$RegistryEntry
+ XXX.minecraft.core.RegistryCodecs
- XXX.minecraft.core.RegistrySetBuilder
+ XXX.minecraft.core.RegistrySetBuilder$1
- XXX.minecraft.core.RegistrySetBuilder$1Entry
+ XXX.minecraft.core.RegistrySetBuilder$2
- XXX.minecraft.core.RegistrySetBuilder$3
+ XXX.minecraft.core.RegistrySetBuilder$3$1
- XXX.minecraft.core.RegistrySetBuilder$BuildState
+ XXX.minecraft.core.RegistrySetBuilder$BuildState$1
- XXX.minecraft.core.RegistrySetBuilder$EmptyTagLookup
+ XXX.minecraft.core.RegistrySetBuilder$EmptyTagLookupWrapper
- XXX.minecraft.core.RegistrySetBuilder$EmptyTagRegistryLookup
+ XXX.minecraft.core.RegistrySetBuilder$LazyHolder
- XXX.minecraft.core.RegistrySetBuilder$PatchedRegistries
+ XXX.minecraft.core.RegistrySetBuilder$RegisteredValue
- XXX.minecraft.core.RegistrySetBuilder$RegistryBootstrap
+ XXX.minecraft.core.RegistrySetBuilder$RegistryContents
- XXX.minecraft.core.RegistrySetBuilder$RegistryStub
+ XXX.minecraft.core.RegistrySetBuilder$UniversalLookup
- XXX.minecraft.core.RegistrySetBuilder$UniversalOwner
+ XXX.minecraft.core.RegistrySetBuilder$ValueAndHolder
- XXX.minecraft.core.RegistrySynchronization
+ XXX.minecraft.core.RegistrySynchronization$PackedRegistryEntry
- XXX.minecraft.core.Rotations
+ XXX.minecraft.core.Rotations$1
- XXX.minecraft.core.SectionPos
+ XXX.minecraft.core.SectionPos$1
- XXX.minecraft.core.UUIDUtil
+ XXX.minecraft.core.UUIDUtil$1
- XXX.minecraft.core.Vec3i
+ XXX.minecraft.core.WritableRegistry
- XXX.minecraft.data.AtlasIds
+ XXX.minecraft.data.BlockFamilies
- XXX.minecraft.data.BlockFamily
+ XXX.minecraft.data.BlockFamily$Builder
- XXX.minecraft.data.BlockFamily$Variant
+ XXX.minecraft.data.CachedOutput
- XXX.minecraft.data.DataGenerator
+ XXX.minecraft.data.DataGenerator$PackGenerator
- XXX.minecraft.data.DataProvider
+ XXX.minecraft.data.DataProvider$Factory
- XXX.minecraft.data.HashCache
+ XXX.minecraft.data.HashCache$1
- XXX.minecraft.data.HashCache$CacheUpdater
+ XXX.minecraft.data.HashCache$ProviderCache
- XXX.minecraft.data.HashCache$ProviderCacheBuilder
+ XXX.minecraft.data.HashCache$UpdateFunction
- XXX.minecraft.data.HashCache$UpdateResult
+ XXX.minecraft.data.Main
- XXX.minecraft.data.package-info
- XXX.minecraft.data.PackOutput
+ XXX.minecraft.data.PackOutput$PathProvider
- XXX.minecraft.data.PackOutput$Target
- XXX.minecraft.gametest.Main
+ XXX.minecraft.gametest.package-info
- XXX.minecraft.locale.DeprecatedTranslationsInfo
+ XXX.minecraft.locale.Language
- XXX.minecraft.locale.Language$1
+ XXX.minecraft.locale.package-info
- XXX.minecraft.nbt.ByteArrayTag
+ XXX.minecraft.nbt.ByteArrayTag$1
- XXX.minecraft.nbt.ByteTag
+ XXX.minecraft.nbt.ByteTag$1
- XXX.minecraft.nbt.ByteTag$Cache
+ XXX.minecraft.nbt.CollectionTag
- XXX.minecraft.nbt.CollectionTag$1
+ XXX.minecraft.nbt.CompoundTag
- XXX.minecraft.nbt.CompoundTag$1
+ XXX.minecraft.nbt.CompoundTag$2
- XXX.minecraft.nbt.DoubleTag
+ XXX.minecraft.nbt.DoubleTag$1
- XXX.minecraft.nbt.EndTag
+ XXX.minecraft.nbt.EndTag$1
- XXX.minecraft.nbt.FloatTag
+ XXX.minecraft.nbt.FloatTag$1
- XXX.minecraft.nbt.IntArrayTag
+ XXX.minecraft.nbt.IntArrayTag$1
- XXX.minecraft.nbt.IntTag
+ XXX.minecraft.nbt.IntTag$1
- XXX.minecraft.nbt.IntTag$Cache
+ XXX.minecraft.nbt.ListTag
- XXX.minecraft.nbt.ListTag$1
+ XXX.minecraft.nbt.ListTag$2
- XXX.minecraft.nbt.LongArrayTag
+ XXX.minecraft.nbt.LongArrayTag$1
- XXX.minecraft.nbt.LongTag
+ XXX.minecraft.nbt.LongTag$1
- XXX.minecraft.nbt.LongTag$Cache
+ XXX.minecraft.nbt.NbtAccounter
- XXX.minecraft.nbt.NbtAccounterException
+ XXX.minecraft.nbt.NbtException
- XXX.minecraft.nbt.NbtFormatException
+ XXX.minecraft.nbt.NbtIo
- XXX.minecraft.nbt.NbtIo$1
+ XXX.minecraft.nbt.NbtIo$StringFallbackDataOutput
- XXX.minecraft.nbt.NbtOps
+ XXX.minecraft.nbt.NbtOps$1
- XXX.minecraft.nbt.NbtOps$ByteListCollector
+ XXX.minecraft.nbt.NbtOps$GenericListCollector
- XXX.minecraft.nbt.NbtOps$IntListCollector
+ XXX.minecraft.nbt.NbtOps$ListCollector
- XXX.minecraft.nbt.NbtOps$LongListCollector
+ XXX.minecraft.nbt.NbtOps$NbtRecordBuilder
- XXX.minecraft.nbt.NbtUtils
+ XXX.minecraft.nbt.NumericTag
- XXX.minecraft.nbt.package-info
- XXX.minecraft.nbt.PrimitiveTag
+ XXX.minecraft.nbt.ReportedNbtException
- XXX.minecraft.nbt.ShortTag
+ XXX.minecraft.nbt.ShortTag$1
- XXX.minecraft.nbt.ShortTag$Cache
+ XXX.minecraft.nbt.SnbtGrammar
- XXX.minecraft.nbt.SnbtGrammar$1
+ XXX.minecraft.nbt.SnbtGrammar$2
- XXX.minecraft.nbt.SnbtGrammar$3
+ XXX.minecraft.nbt.SnbtGrammar$4
- XXX.minecraft.nbt.SnbtGrammar$5
+ XXX.minecraft.nbt.SnbtGrammar$ArrayPrefix
- XXX.minecraft.nbt.SnbtGrammar$ArrayPrefix$1
+ XXX.minecraft.nbt.SnbtGrammar$ArrayPrefix$2
- XXX.minecraft.nbt.SnbtGrammar$ArrayPrefix$3
+ XXX.minecraft.nbt.SnbtGrammar$Base
- XXX.minecraft.nbt.SnbtGrammar$IntegerLiteral
+ XXX.minecraft.nbt.SnbtGrammar$IntegerSuffix
- XXX.minecraft.nbt.SnbtGrammar$Sign
+ XXX.minecraft.nbt.SnbtGrammar$Signed
- XXX.minecraft.nbt.SnbtGrammar$SignedPrefix
+ XXX.minecraft.nbt.SnbtGrammar$SimpleHexLiteralParseRule
- XXX.minecraft.nbt.SnbtGrammar$TypeSuffix
+ XXX.minecraft.nbt.SnbtOperations
- XXX.minecraft.nbt.SnbtOperations$1
+ XXX.minecraft.nbt.SnbtOperations$2
- XXX.minecraft.nbt.SnbtOperations$3
+ XXX.minecraft.nbt.SnbtOperations$BuiltinKey
- XXX.minecraft.nbt.SnbtOperations$BuiltinOperation
+ XXX.minecraft.nbt.SnbtPrinterTagVisitor
- XXX.minecraft.nbt.StreamTagVisitor
+ XXX.minecraft.nbt.StreamTagVisitor$EntryResult
- XXX.minecraft.nbt.StreamTagVisitor$ValueResult
+ XXX.minecraft.nbt.StringTag
- XXX.minecraft.nbt.StringTag$1
+ XXX.minecraft.nbt.StringTagVisitor
- XXX.minecraft.nbt.Tag
+ XXX.minecraft.nbt.TagParser
- XXX.minecraft.nbt.TagType
+ XXX.minecraft.nbt.TagType$1
- XXX.minecraft.nbt.TagType$2
+ XXX.minecraft.nbt.TagType$StaticSize
- XXX.minecraft.nbt.TagType$VariableSize
+ XXX.minecraft.nbt.TagTypes
- XXX.minecraft.nbt.TagVisitor
+ XXX.minecraft.nbt.TextComponentTagVisitor
+ XXX.minecraft.network.BandwidthDebugMonitor
- XXX.minecraft.network.CipherBase
+ XXX.minecraft.network.CipherDecoder
- XXX.minecraft.network.CipherEncoder
+ XXX.minecraft.network.ClientboundPacketListener
- XXX.minecraft.network.CompressionDecoder
+ XXX.minecraft.network.CompressionEncoder
- XXX.minecraft.network.Connection
+ XXX.minecraft.network.Connection$1
- XXX.minecraft.network.Connection$2
+ XXX.minecraft.network.Connection$3
- XXX.minecraft.network.ConnectionProtocol
+ XXX.minecraft.network.DisconnectionDetails
- XXX.minecraft.network.FriendlyByteBuf
+ XXX.minecraft.network.HandlerNames
- XXX.minecraft.network.HashedPatchMap
+ XXX.minecraft.network.HashedPatchMap$HashGenerator
- XXX.minecraft.network.HashedStack
+ XXX.minecraft.network.HashedStack$1
- XXX.minecraft.network.HashedStack$ActualItem
+ XXX.minecraft.network.HiddenByteBuf
- XXX.minecraft.network.LocalFrameDecoder
+ XXX.minecraft.network.LocalFrameEncoder
- XXX.minecraft.network.LpVec3
+ XXX.minecraft.network.MonitoredLocalFrameDecoder
- XXX.minecraft.network.package-info
- XXX.minecraft.network.PacketBundlePacker
+ XXX.minecraft.network.PacketBundleUnpacker
- XXX.minecraft.network.PacketDecoder
+ XXX.minecraft.network.PacketEncoder
- XXX.minecraft.network.PacketListener
- XXX.minecraft.network.PacketProcessor$ListenerAndPacket
+ XXX.minecraft.network.PacketSendListener
- XXX.minecraft.network.ProtocolInfo
+ XXX.minecraft.network.ProtocolInfo$Details
- XXX.minecraft.network.ProtocolInfo$Details$PacketVisitor
+ XXX.minecraft.network.ProtocolInfo$DetailsProvider
- XXX.minecraft.network.ProtocolSwapHandler
+ XXX.minecraft.network.RateKickingConnection
- XXX.minecraft.network.RegistryFriendlyByteBuf
+ XXX.minecraft.network.ServerboundPacketListener
- XXX.minecraft.network.SkipPacketDecoderException
+ XXX.minecraft.network.SkipPacketEncoderException
- XXX.minecraft.network.SkipPacketException
+ XXX.minecraft.network.TickablePacketListener
- XXX.minecraft.network.UnconfiguredPipelineHandler
+ XXX.minecraft.network.UnconfiguredPipelineHandler$Inbound
- XXX.minecraft.network.UnconfiguredPipelineHandler$InboundConfigurationTask
+ XXX.minecraft.network.UnconfiguredPipelineHandler$Outbound
- XXX.minecraft.network.UnconfiguredPipelineHandler$OutboundConfigurationTask
+ XXX.minecraft.network.Utf8String
- XXX.minecraft.network.VarInt
- XXX.minecraft.network.Varint21FrameDecoder
+ XXX.minecraft.network.Varint21LengthFieldPrepender
+ XXX.minecraft.network.VarLong
- XXX.minecraft.util.BoundedFloatFunction$1
- XXX.minecraft.util.Brightness
+ XXX.minecraft.util.ByIdMap
- XXX.minecraft.util.ByIdMap$OutOfBoundsStrategy
+ XXX.minecraft.util.ClassInstanceMultiMap
- XXX.minecraft.util.ClassTreeIdRegistry
+ XXX.minecraft.util.ColorRGBA
- XXX.minecraft.util.CommonColors
+ XXX.minecraft.util.CommonLinks
- XXX.minecraft.util.CrudeIncrementalIntIdentityHashBiMap
+ XXX.minecraft.util.Crypt
- XXX.minecraft.util.Crypt$ByteArrayToKeyFunction
+ XXX.minecraft.util.Crypt$SaltSignaturePair
- XXX.minecraft.util.Crypt$SaltSupplier
+ XXX.minecraft.util.CryptException
- XXX.minecraft.util.CsvOutput
+ XXX.minecraft.util.CsvOutput$Builder
- XXX.minecraft.util.CubicSampler
+ XXX.minecraft.util.CubicSampler$Vec3Fetcher
- XXX.minecraft.util.CubicSpline
+ XXX.minecraft.util.CubicSpline$1Point
- XXX.minecraft.util.CubicSpline$Builder
+ XXX.minecraft.util.CubicSpline$Constant
- XXX.minecraft.util.CubicSpline$CoordinateVisitor
+ XXX.minecraft.util.CubicSpline$Multipoint
- XXX.minecraft.util.DebugBuffer
+ XXX.minecraft.util.DelegateDataOutput
- XXX.minecraft.util.DependencySorter
+ XXX.minecraft.util.DependencySorter$Entry
- XXX.minecraft.util.DirectoryLock
+ XXX.minecraft.util.DirectoryLock$LockException
- XXX.minecraft.util.EncoderCache
+ XXX.minecraft.util.EncoderCache$1
- XXX.minecraft.util.EncoderCache$2
+ XXX.minecraft.util.EncoderCache$Key
- XXX.minecraft.util.ExceptionCollector
+ XXX.minecraft.util.ExtraCodecs
- XXX.minecraft.util.ExtraCodecs$1
+ XXX.minecraft.util.ExtraCodecs$1ContextRetrievalCodec
- XXX.minecraft.util.ExtraCodecs$2
+ XXX.minecraft.util.ExtraCodecs$3
- XXX.minecraft.util.ExtraCodecs$4
+ XXX.minecraft.util.ExtraCodecs$5
- XXX.minecraft.util.ExtraCodecs$6
+ XXX.minecraft.util.ExtraCodecs$7
- XXX.minecraft.util.ExtraCodecs$LateBoundIdMapper
+ XXX.minecraft.util.ExtraCodecs$StrictUnboundedMapCodec
- XXX.minecraft.util.ExtraCodecs$TagOrElementLocation
+ XXX.minecraft.util.FastBufferedInputStream
- XXX.minecraft.util.FileSystemUtil
+ XXX.minecraft.util.FileZipper
- XXX.minecraft.util.FormattedCharSequence
+ XXX.minecraft.util.FormattedCharSink
- XXX.minecraft.util.FutureChain
+ XXX.minecraft.util.Graph
- XXX.minecraft.util.GsonHelper
+ XXX.minecraft.util.GsonHelper$CountedAppendable
- XXX.minecraft.util.HashOps
+ XXX.minecraft.util.HashOps$ListHashBuilder
- XXX.minecraft.util.HashOps$MapHashBuilder
+ XXX.minecraft.util.HttpUtil
- XXX.minecraft.util.HttpUtil$DownloadProgressListener
+ XXX.minecraft.util.InclusiveRange
- XXX.minecraft.util.KeyDispatchDataCodec
+ XXX.minecraft.util.LazyLoadedValue
- XXX.minecraft.util.LenientJsonParser
+ XXX.minecraft.util.LinearCongruentialGenerator
- XXX.minecraft.util.ListAndDeque
+ XXX.minecraft.util.MemoryReserve
- XXX.minecraft.util.ModCheck
+ XXX.minecraft.util.ModCheck$Confidence
- XXX.minecraft.util.Mth
+ XXX.minecraft.util.NativeModuleLister
- XXX.minecraft.util.NativeModuleLister$NativeModuleInfo
+ XXX.minecraft.util.NativeModuleLister$NativeModuleVersion
- XXX.minecraft.util.NullOps
+ XXX.minecraft.util.NullOps$1
- XXX.minecraft.util.NullOps$NullListBuilder
+ XXX.minecraft.util.NullOps$NullMapBuilder
- XXX.minecraft.util.OptionEnum
+ XXX.minecraft.util.package-info
+ XXX.minecraft.util.ParticleUtils
- XXX.minecraft.util.PlaceholderLookupProvider
+ XXX.minecraft.util.PlaceholderLookupProvider$1
- XXX.minecraft.util.PlaceholderLookupProvider$2
+ XXX.minecraft.util.PlaceholderLookupProvider$UniversalLookup
- XXX.minecraft.util.PngInfo
+ XXX.minecraft.util.ProblemReporter
- XXX.minecraft.util.ProblemReporter$1
+ XXX.minecraft.util.ProblemReporter$Collector
- XXX.minecraft.util.ProblemReporter$Collector$Entry
+ XXX.minecraft.util.ProblemReporter$Collector$ProblemTreeNode
- XXX.minecraft.util.ProblemReporter$ElementReferencePathElement
+ XXX.minecraft.util.ProblemReporter$FieldPathElement
- XXX.minecraft.util.ProblemReporter$IndexedFieldPathElement
+ XXX.minecraft.util.ProblemReporter$IndexedPathElement
- XXX.minecraft.util.ProblemReporter$PathElement
+ XXX.minecraft.util.ProblemReporter$Problem
- XXX.minecraft.util.ProblemReporter$RootElementPathElement
+ XXX.minecraft.util.ProblemReporter$RootFieldPathElement
- XXX.minecraft.util.ProblemReporter$ScopedCollector
+ XXX.minecraft.util.ProgressListener
- XXX.minecraft.util.RandomSource
+ XXX.minecraft.util.RegistryContextSwapper
- XXX.minecraft.util.ResourceLocationPattern
+ XXX.minecraft.util.SegmentedAnglePrecision
- XXX.minecraft.util.SequencedPriorityIterator
+ XXX.minecraft.util.SignatureUpdater
- XXX.minecraft.util.SignatureUpdater$Output
+ XXX.minecraft.util.SignatureValidator
- XXX.minecraft.util.Signer
+ XXX.minecraft.util.SimpleBitStorage
- XXX.minecraft.util.SimpleBitStorage$InitializationException
+ XXX.minecraft.util.SingleKeyCache
- XXX.minecraft.util.SmoothDouble
+ XXX.minecraft.util.SortedArraySet
- XXX.minecraft.util.SortedArraySet$ArrayIterator
+ XXX.minecraft.util.SpawnUtil
- XXX.minecraft.util.SpawnUtil$Strategy
+ XXX.minecraft.util.StaticCache2D
- XXX.minecraft.util.StaticCache2D$Initializer
+ XXX.minecraft.util.StrictJsonParser
- XXX.minecraft.util.StringDecomposer
+ XXX.minecraft.util.StringRepresentable
- XXX.minecraft.util.StringRepresentable$1
+ XXX.minecraft.util.StringRepresentable$EnumCodec
- XXX.minecraft.util.StringRepresentable$StringRepresentableCodec
+ XXX.minecraft.util.StringUtil
- XXX.minecraft.util.TaskChainer
+ XXX.minecraft.util.TaskChainer$1
- XXX.minecraft.util.ThreadingDetector
+ XXX.minecraft.util.TickThrottler
- XXX.minecraft.util.TimeSource
+ XXX.minecraft.util.TimeSource$NanoTimeSource
- XXX.minecraft.util.TimeUtil
+ XXX.minecraft.util.ToFloatFunction
+ XXX.minecraft.util.ToFloatFunction$2
- XXX.minecraft.util.TriState
+ XXX.minecraft.util.Tuple
- XXX.minecraft.util.Unit
+ XXX.minecraft.util.VisibleForDebug
- XXX.minecraft.util.ZeroBitStorage
+ XXX.minecraft.world.BossEvent
- XXX.minecraft.world.BossEvent$BossBarColor
+ XXX.minecraft.world.BossEvent$BossBarOverlay
- XXX.minecraft.world.Clearable
+ XXX.minecraft.world.CompoundContainer
- XXX.minecraft.world.Container
+ XXX.minecraft.world.Container$ContainerIterator
- XXX.minecraft.world.ContainerHelper
+ XXX.minecraft.world.ContainerListener
- XXX.minecraft.world.Containers
+ XXX.minecraft.world.Difficulty
- XXX.minecraft.world.DifficultyInstance
+ XXX.minecraft.world.InteractionHand
- XXX.minecraft.world.InteractionResult
+ XXX.minecraft.world.InteractionResult$Fail
- XXX.minecraft.world.InteractionResult$ItemContext
+ XXX.minecraft.world.InteractionResult$Pass
- XXX.minecraft.world.InteractionResult$Success
+ XXX.minecraft.world.InteractionResult$SwingSource
- XXX.minecraft.world.InteractionResult$TryEmptyHandInteraction
+ XXX.minecraft.world.ItemStackWithSlot
- XXX.minecraft.world.LockCode
+ XXX.minecraft.world.MenuProvider
- XXX.minecraft.world.Nameable
- XXX.minecraft.world.RandomizableContainer
+ XXX.minecraft.world.RandomSequence
- XXX.minecraft.world.RandomSequences
+ XXX.minecraft.world.RandomSequences$DirtyMarkingRandomSource
+ XXX.minecraft.world.SimpleContainer
- XXX.minecraft.world.SimpleMenuProvider
+ XXX.minecraft.world.TickRateManager
- XXX.minecraft.world.WorldlyContainer
+ XXX.minecraft.world.WorldlyContainerHolder
- XXX.monitoring.jmx.MinecraftServerStatistics
+ XXX.monitoring.jmx.MinecraftServerStatistics$AttributeDescription
- XXX.monitoring.jmx.package-info
+ XXX.nbt.visitors.CollectFields
- XXX.nbt.visitors.CollectToTag
+ XXX.nbt.visitors.CollectToTag$CompoundBuilder
- XXX.nbt.visitors.CollectToTag$ContainerBuilder
+ XXX.nbt.visitors.CollectToTag$ListBuilder
- XXX.nbt.visitors.CollectToTag$RootBuilder
+ XXX.nbt.visitors.FieldSelector
- XXX.nbt.visitors.FieldTree
- XXX.nbt.visitors.package-info
+ XXX.nbt.visitors.SkipAll
- XXX.nbt.visitors.SkipAll$1
+ XXX.nbt.visitors.SkipFields
- XXX.network.chat.ChatDecorator
+ XXX.network.chat.ChatType
- XXX.network.chat.ChatType$Bound
+ XXX.network.chat.ChatTypeDecoration
- XXX.network.chat.ChatTypeDecoration$Parameter
+ XXX.network.chat.ChatTypeDecoration$Parameter$Selector
- XXX.network.chat.ClickEvent
+ XXX.network.chat.ClickEvent$Action
- XXX.network.chat.ClickEvent$ChangePage
+ XXX.network.chat.ClickEvent$CopyToClipboard
- XXX.network.chat.ClickEvent$Custom
+ XXX.network.chat.ClickEvent$OpenFile
- XXX.network.chat.ClickEvent$OpenUrl
+ XXX.network.chat.ClickEvent$RunCommand
- XXX.network.chat.ClickEvent$ShowDialog
+ XXX.network.chat.ClickEvent$SuggestCommand
- XXX.network.chat.CommonComponents
+ XXX.network.chat.Component
- XXX.network.chat.ComponentContents
+ XXX.network.chat.ComponentSerialization
- XXX.network.chat.ComponentSerialization$1
+ XXX.network.chat.ComponentSerialization$FuzzyCodec
- XXX.network.chat.ComponentSerialization$StrictEither
+ XXX.network.chat.ComponentUtils
- XXX.network.chat.FilterMask
+ XXX.network.chat.FilterMask$Type
- XXX.network.chat.FontDescription
+ XXX.network.chat.FontDescription$AtlasSprite
- XXX.network.chat.FontDescription$PlayerSprite
+ XXX.network.chat.FontDescription$Resource
- XXX.network.chat.FormattedText
+ XXX.network.chat.FormattedText$1
- XXX.network.chat.FormattedText$2
+ XXX.network.chat.FormattedText$3
- XXX.network.chat.FormattedText$4
+ XXX.network.chat.FormattedText$ContentConsumer
- XXX.network.chat.FormattedText$StyledContentConsumer
+ XXX.network.chat.HoverEvent
- XXX.network.chat.HoverEvent$Action
+ XXX.network.chat.HoverEvent$EntityTooltipInfo
- XXX.network.chat.HoverEvent$ShowEntity
+ XXX.network.chat.HoverEvent$ShowItem
- XXX.network.chat.HoverEvent$ShowText
+ XXX.network.chat.LastSeenMessages
- XXX.network.chat.LastSeenMessages$Packed
+ XXX.network.chat.LastSeenMessages$Update
- XXX.network.chat.LastSeenMessagesTracker
+ XXX.network.chat.LastSeenMessagesTracker$Update
- XXX.network.chat.LastSeenMessagesValidator
+ XXX.network.chat.LastSeenMessagesValidator$ValidationException
- XXX.network.chat.LastSeenTrackedEntry
+ XXX.network.chat.LocalChatSession
- XXX.network.chat.MessageSignature
+ XXX.network.chat.MessageSignature$Packed
- XXX.network.chat.MessageSignatureCache
+ XXX.network.chat.MutableComponent
- XXX.network.chat.OutgoingChatMessage
+ XXX.network.chat.OutgoingChatMessage$Disguised
- XXX.network.chat.OutgoingChatMessage$Player
- XXX.network.chat.package-info
+ XXX.network.chat.PlayerChatMessage
- XXX.network.chat.RemoteChatSession
+ XXX.network.chat.RemoteChatSession$Data
- XXX.network.chat.SignableCommand
+ XXX.network.chat.SignableCommand$Argument
- XXX.network.chat.SignedMessageBody
+ XXX.network.chat.SignedMessageBody$Packed
- XXX.network.chat.SignedMessageChain
+ XXX.network.chat.SignedMessageChain$1
- XXX.network.chat.SignedMessageChain$DecodeException
+ XXX.network.chat.SignedMessageChain$Decoder
- XXX.network.chat.SignedMessageChain$Encoder
+ XXX.network.chat.SignedMessageLink
- XXX.network.chat.SignedMessageValidator
+ XXX.network.chat.SignedMessageValidator$KeyBased
- XXX.network.chat.Style
+ XXX.network.chat.Style$1
- XXX.network.chat.Style$1Collector
+ XXX.network.chat.Style$Serializer
- XXX.network.chat.SubStringSource
+ XXX.network.chat.TextColor
- XXX.network.chat.ThrowingComponent
+ XXX.network.codec.ByteBufCodecs
- XXX.network.codec.ByteBufCodecs$1
+ XXX.network.codec.ByteBufCodecs$10
- XXX.network.codec.ByteBufCodecs$11
+ XXX.network.codec.ByteBufCodecs$12
- XXX.network.codec.ByteBufCodecs$13
+ XXX.network.codec.ByteBufCodecs$14
- XXX.network.codec.ByteBufCodecs$15
+ XXX.network.codec.ByteBufCodecs$16
- XXX.network.codec.ByteBufCodecs$17
+ XXX.network.codec.ByteBufCodecs$18
- XXX.network.codec.ByteBufCodecs$19
+ XXX.network.codec.ByteBufCodecs$2
- XXX.network.codec.ByteBufCodecs$20
+ XXX.network.codec.ByteBufCodecs$21
- XXX.network.codec.ByteBufCodecs$22
+ XXX.network.codec.ByteBufCodecs$23
- XXX.network.codec.ByteBufCodecs$24
+ XXX.network.codec.ByteBufCodecs$25
- XXX.network.codec.ByteBufCodecs$26
+ XXX.network.codec.ByteBufCodecs$27
- XXX.network.codec.ByteBufCodecs$28
+ XXX.network.codec.ByteBufCodecs$29
- XXX.network.codec.ByteBufCodecs$3
+ XXX.network.codec.ByteBufCodecs$30
- XXX.network.codec.ByteBufCodecs$31
+ XXX.network.codec.ByteBufCodecs$32
- XXX.network.codec.ByteBufCodecs$33
+ XXX.network.codec.ByteBufCodecs$34
- XXX.network.codec.ByteBufCodecs$35
+ XXX.network.codec.ByteBufCodecs$4
- XXX.network.codec.ByteBufCodecs$5
+ XXX.network.codec.ByteBufCodecs$6
- XXX.network.codec.ByteBufCodecs$7
+ XXX.network.codec.ByteBufCodecs$8
- XXX.network.codec.ByteBufCodecs$9
+ XXX.network.codec.IdDispatchCodec
- XXX.network.codec.IdDispatchCodec$Builder
+ XXX.network.codec.IdDispatchCodec$DontDecorateException
- XXX.network.codec.IdDispatchCodec$Entry
+ XXX.network.codec.package-info
+ XXX.network.codec.StreamCodec
- XXX.network.codec.StreamCodec$1
+ XXX.network.codec.StreamCodec$10
- XXX.network.codec.StreamCodec$11
+ XXX.network.codec.StreamCodec$12
- XXX.network.codec.StreamCodec$13
+ XXX.network.codec.StreamCodec$14
- XXX.network.codec.StreamCodec$15
+ XXX.network.codec.StreamCodec$16
- XXX.network.codec.StreamCodec$17
+ XXX.network.codec.StreamCodec$2
- XXX.network.codec.StreamCodec$3
+ XXX.network.codec.StreamCodec$4
- XXX.network.codec.StreamCodec$5
+ XXX.network.codec.StreamCodec$6
- XXX.network.codec.StreamCodec$7
+ XXX.network.codec.StreamCodec$8
- XXX.network.codec.StreamCodec$9
+ XXX.network.codec.StreamCodec$CodecOperation
- XXX.network.codec.StreamDecoder
+ XXX.network.codec.StreamEncoder
- XXX.network.codec.StreamMemberEncoder
+ XXX.network.protocol.BundleDelimiterPacket
- XXX.network.protocol.BundlePacket
+ XXX.network.protocol.BundlerInfo
- XXX.network.protocol.BundlerInfo$1
+ XXX.network.protocol.BundlerInfo$1$1
- XXX.network.protocol.BundlerInfo$Bundler
+ XXX.network.protocol.CodecModifier
+ XXX.network.protocol.package-info
- XXX.network.protocol.Packet
+ XXX.network.protocol.PacketFlow
- XXX.network.protocol.PacketType
+ XXX.network.protocol.PacketUtils
- XXX.network.protocol.ProtocolCodecBuilder
+ XXX.network.protocol.ProtocolInfoBuilder
- XXX.network.protocol.ProtocolInfoBuilder$1
+ XXX.network.protocol.ProtocolInfoBuilder$2
- XXX.network.protocol.ProtocolInfoBuilder$3
+ XXX.network.protocol.ProtocolInfoBuilder$CodecEntry
- XXX.network.protocol.ProtocolInfoBuilder$Implementation
+ XXX.network.protocol.SimpleUnboundProtocol
- XXX.network.protocol.UnboundProtocol
+ XXX.network.syncher.EntityDataAccessor
- XXX.network.syncher.EntityDataSerializer
+ XXX.network.syncher.EntityDataSerializer$ForValueType
- XXX.network.syncher.EntityDataSerializers
+ XXX.network.syncher.EntityDataSerializers$1
- XXX.network.syncher.EntityDataSerializers$2
+ XXX.network.syncher.EntityDataSerializers$3
- XXX.packrat.commands.CommandArgumentParser
+ XXX.packrat.commands.CommandArgumentParser$1
- XXX.packrat.commands.CommandArgumentParser$2
+ XXX.packrat.commands.Grammar
- XXX.packrat.commands.GreedyPatternParseRule
+ XXX.packrat.commands.GreedyPredicateParseRule
- XXX.packrat.commands.NumberRunParseRule
+ XXX.packrat.commands.package-info
+ XXX.packrat.commands.ParserBasedArgument
- XXX.packrat.commands.ResourceLocationParseRule
+ XXX.packrat.commands.ResourceLookupRule
- XXX.packrat.commands.ResourceSuggestion
+ XXX.packrat.commands.StringReaderParserState
- XXX.packrat.commands.StringReaderTerms
+ XXX.packrat.commands.StringReaderTerms$1
- XXX.packrat.commands.StringReaderTerms$2
+ XXX.packrat.commands.StringReaderTerms$TerminalCharacters
- XXX.packrat.commands.StringReaderTerms$TerminalWord
+ XXX.packrat.commands.TagParseRule
- XXX.packrat.commands.UnquotedStringParseRule
+ XXX.parsing.packrat.Atom
- XXX.parsing.packrat.CachedParseState
+ XXX.parsing.packrat.CachedParseState$CacheEntry
- XXX.parsing.packrat.CachedParseState$PositionCache
+ XXX.parsing.packrat.CachedParseState$Silent
- XXX.parsing.packrat.CachedParseState$SimpleControl
+ XXX.parsing.packrat.Control
- XXX.parsing.packrat.Control$1
+ XXX.parsing.packrat.DelayedException
- XXX.parsing.packrat.Dictionary
+ XXX.parsing.packrat.Dictionary$Entry
- XXX.parsing.packrat.Dictionary$Reference
+ XXX.parsing.packrat.ErrorCollector
- XXX.parsing.packrat.ErrorCollector$LongestOnly
+ XXX.parsing.packrat.ErrorCollector$LongestOnly$MutableErrorEntry
- XXX.parsing.packrat.ErrorCollector$Nop
+ XXX.parsing.packrat.ErrorEntry
- XXX.parsing.packrat.NamedRule
- XXX.parsing.packrat.package-info
+ XXX.parsing.packrat.ParseState
- XXX.parsing.packrat.Rule
+ XXX.parsing.packrat.Rule$RuleAction
- XXX.parsing.packrat.Rule$SimpleRuleAction
+ XXX.parsing.packrat.Rule$WrappedTerm
- XXX.parsing.packrat.Scope
+ XXX.parsing.packrat.Scope$1
- XXX.parsing.packrat.SuggestionSupplier
+ XXX.parsing.packrat.Term
- XXX.parsing.packrat.Term$1
+ XXX.parsing.packrat.Term$2
- XXX.parsing.packrat.Term$3
+ XXX.parsing.packrat.Term$Alternative
- XXX.parsing.packrat.Term$LookAhead
+ XXX.parsing.packrat.Term$Marker
- XXX.parsing.packrat.Term$Maybe
+ XXX.parsing.packrat.Term$Repeated
- XXX.parsing.packrat.Term$RepeatedWithSeparator
+ XXX.parsing.packrat.Term$Sequence
+ XXX.profiling.jfr.Environment
- XXX.profiling.jfr.JfrProfiler
+ XXX.profiling.jfr.JfrProfiler$1
- XXX.profiling.jfr.JvmProfiler
+ XXX.profiling.jfr.JvmProfiler$NoOpProfiler
+ XXX.profiling.jfr.package-info
- XXX.profiling.jfr.Percentiles
+ XXX.profiling.jfr.SummaryReporter
+ XXX.profiling.metrics.MetricCategory
- XXX.profiling.metrics.MetricSampler
+ XXX.profiling.metrics.MetricSampler$MetricSamplerBuilder
- XXX.profiling.metrics.MetricSampler$SamplerResult
+ XXX.profiling.metrics.MetricSampler$ThresholdTest
- XXX.profiling.metrics.MetricSampler$ValueIncreasedByPercentage
+ XXX.profiling.metrics.MetricsRegistry
- XXX.profiling.metrics.MetricsRegistry$AggregatedMetricSampler
+ XXX.profiling.metrics.MetricsSamplerProvider
+ XXX.profiling.metrics.package-info
- XXX.profiling.metrics.ProfilerMeasured
- XXX.projectile.windcharge.AbstractWindCharge
+ XXX.projectile.windcharge.BreezeWindCharge
+ XXX.projectile.windcharge.package-info
- XXX.projectile.windcharge.WindCharge
- XXX.protocol.common.ClientboundClearDialogPacket
+ XXX.protocol.common.ClientboundCustomPayloadPacket
- XXX.protocol.common.ClientboundCustomReportDetailsPacket
+ XXX.protocol.common.ClientboundDisconnectPacket
- XXX.protocol.common.ClientboundKeepAlivePacket
+ XXX.protocol.common.ClientboundPingPacket
- XXX.protocol.common.ClientboundResourcePackPopPacket
+ XXX.protocol.common.ClientboundResourcePackPushPacket
- XXX.protocol.common.ClientboundServerLinksPacket
+ XXX.protocol.common.ClientboundShowDialogPacket
- XXX.protocol.common.ClientboundStoreCookiePacket
+ XXX.protocol.common.ClientboundTransferPacket
- XXX.protocol.common.ClientboundUpdateTagsPacket
+ XXX.protocol.common.ClientCommonPacketListener
+ XXX.protocol.common.CommonPacketTypes
- XXX.protocol.common.package-info
+ XXX.protocol.common.ServerboundClientInformationPacket
- XXX.protocol.common.ServerboundCustomClickActionPacket
+ XXX.protocol.common.ServerboundCustomPayloadPacket
- XXX.protocol.common.ServerboundKeepAlivePacket
+ XXX.protocol.common.ServerboundPongPacket
- XXX.protocol.common.ServerboundResourcePackPacket
+ XXX.protocol.common.ServerboundResourcePackPacket$Action
- XXX.protocol.common.ServerCommonPacketListener
- XXX.protocol.configuration.ClientboundCodeOfConductPacket
+ XXX.protocol.configuration.ClientboundFinishConfigurationPacket
- XXX.protocol.configuration.ClientboundRegistryDataPacket
+ XXX.protocol.configuration.ClientboundResetChatPacket
- XXX.protocol.configuration.ClientboundSelectKnownPacks
+ XXX.protocol.configuration.ClientboundUpdateEnabledFeaturesPacket
+ XXX.protocol.configuration.ClientConfigurationPacketListener
- XXX.protocol.configuration.ConfigurationPacketTypes
+ XXX.protocol.configuration.ConfigurationProtocols
- XXX.protocol.configuration.package-info
+ XXX.protocol.configuration.ServerboundAcceptCodeOfConductPacket
- XXX.protocol.configuration.ServerboundFinishConfigurationPacket
+ XXX.protocol.configuration.ServerboundSelectKnownPacks
- XXX.protocol.configuration.ServerConfigurationPacketListener
- XXX.protocol.cookie.ClientboundCookieRequestPacket
+ XXX.protocol.cookie.ClientCookiePacketListener
+ XXX.protocol.cookie.CookiePacketTypes
- XXX.protocol.cookie.package-info
+ XXX.protocol.cookie.ServerboundCookieResponsePacket
- XXX.protocol.cookie.ServerCookiePacketListener
- XXX.protocol.game.ClientboundAddEntityPacket
+ XXX.protocol.game.ClientboundAnimatePacket
- XXX.protocol.game.ClientboundAwardStatsPacket
+ XXX.protocol.game.ClientboundBlockChangedAckPacket
- XXX.protocol.game.ClientboundBlockDestructionPacket
+ XXX.protocol.game.ClientboundBlockEntityDataPacket
- XXX.protocol.game.ClientboundBlockEventPacket
+ XXX.protocol.game.ClientboundBlockUpdatePacket
- XXX.protocol.game.ClientboundBossEventPacket
+ XXX.protocol.game.ClientboundBossEventPacket$1
- XXX.protocol.game.ClientboundBossEventPacket$AddOperation
+ XXX.protocol.game.ClientboundBossEventPacket$Handler
- XXX.protocol.game.ClientboundBossEventPacket$Operation
+ XXX.protocol.game.ClientboundBossEventPacket$OperationType
- XXX.protocol.game.ClientboundBossEventPacket$UpdateNameOperation
+ XXX.protocol.game.ClientboundBossEventPacket$UpdateProgressOperation
- XXX.protocol.game.ClientboundBossEventPacket$UpdatePropertiesOperation
+ XXX.protocol.game.ClientboundBossEventPacket$UpdateStyleOperation
- XXX.protocol.game.ClientboundBundleDelimiterPacket
+ XXX.protocol.game.ClientboundBundlePacket
- XXX.protocol.game.ClientboundChangeDifficultyPacket
+ XXX.protocol.game.ClientboundChunkBatchFinishedPacket
- XXX.protocol.game.ClientboundChunkBatchStartPacket
+ XXX.protocol.game.ClientboundChunksBiomesPacket
- XXX.protocol.game.ClientboundChunksBiomesPacket$ChunkBiomeData
+ XXX.protocol.game.ClientboundClearTitlesPacket
- XXX.protocol.game.ClientboundCommandsPacket
+ XXX.protocol.game.ClientboundCommandsPacket$ArgumentNodeStub
- XXX.protocol.game.ClientboundCommandsPacket$Entry
+ XXX.protocol.game.ClientboundCommandsPacket$LiteralNodeStub
- XXX.protocol.game.ClientboundCommandsPacket$NodeBuilder
+ XXX.protocol.game.ClientboundCommandsPacket$NodeInspector
- XXX.protocol.game.ClientboundCommandsPacket$NodeResolver
+ XXX.protocol.game.ClientboundCommandsPacket$NodeStub
- XXX.protocol.game.ClientboundCommandSuggestionsPacket
+ XXX.protocol.game.ClientboundCommandSuggestionsPacket$Entry
- XXX.protocol.game.ClientboundContainerClosePacket
+ XXX.protocol.game.ClientboundContainerSetContentPacket
- XXX.protocol.game.ClientboundContainerSetDataPacket
+ XXX.protocol.game.ClientboundContainerSetSlotPacket
- XXX.protocol.game.ClientboundCooldownPacket
+ XXX.protocol.game.ClientboundCustomChatCompletionsPacket
- XXX.protocol.game.ClientboundCustomChatCompletionsPacket$Action
+ XXX.protocol.game.ClientboundDamageEventPacket
- XXX.protocol.game.ClientboundDebugSamplePacket
+ XXX.protocol.game.ClientboundDeleteChatPacket
- XXX.protocol.game.ClientboundDisguisedChatPacket
+ XXX.protocol.game.ClientboundEntityEventPacket
- XXX.protocol.game.ClientboundEntityPositionSyncPacket
+ XXX.protocol.game.ClientboundExplodePacket
- XXX.protocol.game.ClientboundForgetLevelChunkPacket
+ XXX.protocol.game.ClientboundGameEventPacket
- XXX.protocol.game.ClientboundGameEventPacket$Type
+ XXX.protocol.game.ClientboundHorseScreenOpenPacket
- XXX.protocol.game.ClientboundHurtAnimationPacket
+ XXX.protocol.game.ClientboundInitializeBorderPacket
- XXX.protocol.game.ClientboundLevelChunkPacketData
+ XXX.protocol.game.ClientboundLevelChunkPacketData$BlockEntityInfo
- XXX.protocol.game.ClientboundLevelChunkPacketData$BlockEntityTagOutput
+ XXX.protocol.game.ClientboundLevelChunkWithLightPacket
- XXX.protocol.game.ClientboundLevelEventPacket
+ XXX.protocol.game.ClientboundLevelParticlesPacket
- XXX.protocol.game.ClientboundLightUpdatePacket
+ XXX.protocol.game.ClientboundLightUpdatePacketData
- XXX.protocol.game.ClientboundLoginPacket
+ XXX.protocol.game.ClientboundMapItemDataPacket
- XXX.protocol.game.ClientboundMerchantOffersPacket
+ XXX.protocol.game.ClientboundMoveEntityPacket
- XXX.protocol.game.ClientboundMoveEntityPacket$Pos
+ XXX.protocol.game.ClientboundMoveEntityPacket$PosRot
- XXX.protocol.game.ClientboundMoveEntityPacket$Rot
+ XXX.protocol.game.ClientboundMoveMinecartPacket
- XXX.protocol.game.ClientboundMoveVehiclePacket
+ XXX.protocol.game.ClientboundOpenBookPacket
- XXX.protocol.game.ClientboundOpenScreenPacket
+ XXX.protocol.game.ClientboundOpenSignEditorPacket
- XXX.protocol.game.ClientboundPlaceGhostRecipePacket
+ XXX.protocol.game.ClientboundPlayerAbilitiesPacket
- XXX.protocol.game.ClientboundPlayerChatPacket
+ XXX.protocol.game.ClientboundPlayerCombatEndPacket
- XXX.protocol.game.ClientboundPlayerCombatEnterPacket
+ XXX.protocol.game.ClientboundPlayerCombatKillPacket
- XXX.protocol.game.ClientboundPlayerInfoRemovePacket
+ XXX.protocol.game.ClientboundPlayerInfoUpdatePacket
- XXX.protocol.game.ClientboundPlayerInfoUpdatePacket$Action
+ XXX.protocol.game.ClientboundPlayerInfoUpdatePacket$Action$Reader
- XXX.protocol.game.ClientboundPlayerInfoUpdatePacket$Action$Writer
+ XXX.protocol.game.ClientboundPlayerInfoUpdatePacket$Entry
- XXX.protocol.game.ClientboundPlayerInfoUpdatePacket$EntryBuilder
+ XXX.protocol.game.ClientboundPlayerLookAtPacket
- XXX.protocol.game.ClientboundPlayerPositionPacket
+ XXX.protocol.game.ClientboundPlayerRotationPacket
- XXX.protocol.game.ClientboundProjectilePowerPacket
+ XXX.protocol.game.ClientboundRecipeBookAddPacket
- XXX.protocol.game.ClientboundRecipeBookAddPacket$Entry
+ XXX.protocol.game.ClientboundRecipeBookRemovePacket
- XXX.protocol.game.ClientboundRecipeBookSettingsPacket
+ XXX.protocol.game.ClientboundRemoveEntitiesPacket
- XXX.protocol.game.ClientboundRemoveMobEffectPacket
+ XXX.protocol.game.ClientboundResetScorePacket
- XXX.protocol.game.ClientboundRespawnPacket
+ XXX.protocol.game.ClientboundRotateHeadPacket
- XXX.protocol.game.ClientboundSectionBlocksUpdatePacket
+ XXX.protocol.game.ClientboundSelectAdvancementsTabPacket
- XXX.protocol.game.ClientboundServerDataPacket
+ XXX.protocol.game.ClientboundSetActionBarTextPacket
- XXX.protocol.game.ClientboundSetBorderCenterPacket
+ XXX.protocol.game.ClientboundSetBorderLerpSizePacket
- XXX.protocol.game.ClientboundSetBorderSizePacket
+ XXX.protocol.game.ClientboundSetBorderWarningDelayPacket
- XXX.protocol.game.ClientboundSetBorderWarningDistancePacket
+ XXX.protocol.game.ClientboundSetCameraPacket
- XXX.protocol.game.ClientboundSetChunkCacheCenterPacket
+ XXX.protocol.game.ClientboundSetChunkCacheRadiusPacket
- XXX.protocol.game.ClientboundSetCursorItemPacket
+ XXX.protocol.game.ClientboundSetDefaultSpawnPositionPacket
- XXX.protocol.game.ClientboundSetDisplayObjectivePacket
+ XXX.protocol.game.ClientboundSetEntityDataPacket
- XXX.protocol.game.ClientboundSetEntityLinkPacket
+ XXX.protocol.game.ClientboundSetEntityMotionPacket
- XXX.protocol.game.ClientboundSetEquipmentPacket
+ XXX.protocol.game.ClientboundSetExperiencePacket
- XXX.protocol.game.ClientboundSetHealthPacket
+ XXX.protocol.game.ClientboundSetHeldSlotPacket
- XXX.protocol.game.ClientboundSetObjectivePacket
+ XXX.protocol.game.ClientboundSetPassengersPacket
- XXX.protocol.game.ClientboundSetPlayerInventoryPacket
+ XXX.protocol.game.ClientboundSetPlayerTeamPacket
- XXX.protocol.game.ClientboundSetPlayerTeamPacket$Action
+ XXX.protocol.game.ClientboundSetPlayerTeamPacket$Parameters
- XXX.protocol.game.ClientboundSetScorePacket
+ XXX.protocol.game.ClientboundSetSimulationDistancePacket
- XXX.protocol.game.ClientboundSetSubtitleTextPacket
+ XXX.protocol.game.ClientboundSetTimePacket
+ XXX.protocol.game.ClientboundSetTitlesAnimationPacket
- XXX.protocol.game.ClientboundSetTitleTextPacket
- XXX.protocol.game.ClientboundSoundEntityPacket
+ XXX.protocol.game.ClientboundSoundPacket
- XXX.protocol.game.ClientboundStartConfigurationPacket
+ XXX.protocol.game.ClientboundStopSoundPacket
- XXX.protocol.game.ClientboundSystemChatPacket
+ XXX.protocol.game.ClientboundTabListPacket
- XXX.protocol.game.ClientboundTagQueryPacket
+ XXX.protocol.game.ClientboundTakeItemEntityPacket
- XXX.protocol.game.ClientboundTeleportEntityPacket
+ XXX.protocol.game.ClientboundTestInstanceBlockStatus
- XXX.protocol.game.ClientboundTickingStatePacket
+ XXX.protocol.game.ClientboundTickingStepPacket
- XXX.protocol.game.ClientboundTrackedWaypointPacket
+ XXX.protocol.game.ClientboundTrackedWaypointPacket$Operation
- XXX.protocol.game.ClientboundUpdateAdvancementsPacket
+ XXX.protocol.game.ClientboundUpdateAttributesPacket
- XXX.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
+ XXX.protocol.game.ClientboundUpdateMobEffectPacket
- XXX.protocol.game.ClientboundUpdateRecipesPacket
+ XXX.protocol.game.ClientGamePacketListener
+ XXX.protocol.game.CommonPlayerSpawnInfo
- XXX.protocol.game.DebugEntityNameGenerator
+ XXX.protocol.game.DebugPackets
- XXX.protocol.game.GamePacketTypes
+ XXX.protocol.game.GameProtocols
- XXX.protocol.game.GameProtocols$1
+ XXX.protocol.game.GameProtocols$Context
+ XXX.protocol.game.package-info
- XXX.protocol.game.ServerboundAcceptTeleportationPacket
+ XXX.protocol.game.ServerboundBlockEntityTagQueryPacket
- XXX.protocol.game.ServerboundChangeDifficultyPacket
+ XXX.protocol.game.ServerboundChangeGameModePacket
- XXX.protocol.game.ServerboundChatAckPacket
+ XXX.protocol.game.ServerboundChatCommandPacket
- XXX.protocol.game.ServerboundChatCommandSignedPacket
+ XXX.protocol.game.ServerboundChatPacket
- XXX.protocol.game.ServerboundChatSessionUpdatePacket
+ XXX.protocol.game.ServerboundChunkBatchReceivedPacket
- XXX.protocol.game.ServerboundClientCommandPacket
+ XXX.protocol.game.ServerboundClientCommandPacket$Action
- XXX.protocol.game.ServerboundClientTickEndPacket
+ XXX.protocol.game.ServerboundCommandSuggestionPacket
- XXX.protocol.game.ServerboundConfigurationAcknowledgedPacket
+ XXX.protocol.game.ServerboundContainerButtonClickPacket
- XXX.protocol.game.ServerboundContainerClickPacket
+ XXX.protocol.game.ServerboundContainerClosePacket
- XXX.protocol.game.ServerboundContainerSlotStateChangedPacket
+ XXX.protocol.game.ServerboundDebugSampleSubscriptionPacket
- XXX.protocol.game.ServerboundEditBookPacket
+ XXX.protocol.game.ServerboundEntityTagQueryPacket
- XXX.protocol.game.ServerboundInteractPacket
+ XXX.protocol.game.ServerboundInteractPacket$1
- XXX.protocol.game.ServerboundInteractPacket$Action
+ XXX.protocol.game.ServerboundInteractPacket$ActionType
- XXX.protocol.game.ServerboundInteractPacket$Handler
+ XXX.protocol.game.ServerboundInteractPacket$InteractionAction
- XXX.protocol.game.ServerboundInteractPacket$InteractionAtLocationAction
+ XXX.protocol.game.ServerboundJigsawGeneratePacket
- XXX.protocol.game.ServerboundLockDifficultyPacket
+ XXX.protocol.game.ServerboundMovePlayerPacket
- XXX.protocol.game.ServerboundMovePlayerPacket$Pos
+ XXX.protocol.game.ServerboundMovePlayerPacket$PosRot
- XXX.protocol.game.ServerboundMovePlayerPacket$Rot
+ XXX.protocol.game.ServerboundMovePlayerPacket$StatusOnly
- XXX.protocol.game.ServerboundMoveVehiclePacket
+ XXX.protocol.game.ServerboundPaddleBoatPacket
- XXX.protocol.game.ServerboundPickItemFromBlockPacket
+ XXX.protocol.game.ServerboundPickItemFromEntityPacket
- XXX.protocol.game.ServerboundPlaceRecipePacket
+ XXX.protocol.game.ServerboundPlayerAbilitiesPacket
- XXX.protocol.game.ServerboundPlayerActionPacket
+ XXX.protocol.game.ServerboundPlayerActionPacket$Action
- XXX.protocol.game.ServerboundPlayerCommandPacket
+ XXX.protocol.game.ServerboundPlayerCommandPacket$Action
- XXX.protocol.game.ServerboundPlayerInputPacket
+ XXX.protocol.game.ServerboundPlayerLoadedPacket
- XXX.protocol.game.ServerboundRecipeBookChangeSettingsPacket
+ XXX.protocol.game.ServerboundRecipeBookSeenRecipePacket
- XXX.protocol.game.ServerboundRenameItemPacket
+ XXX.protocol.game.ServerboundSeenAdvancementsPacket
- XXX.protocol.game.ServerboundSeenAdvancementsPacket$Action
+ XXX.protocol.game.ServerboundSelectBundleItemPacket
- XXX.protocol.game.ServerboundSelectTradePacket
+ XXX.protocol.game.ServerboundSetBeaconPacket
- XXX.protocol.game.ServerboundSetCarriedItemPacket
+ XXX.protocol.game.ServerboundSetCommandBlockPacket
- XXX.protocol.game.ServerboundSetCommandMinecartPacket
+ XXX.protocol.game.ServerboundSetCreativeModeSlotPacket
- XXX.protocol.game.ServerboundSetJigsawBlockPacket
+ XXX.protocol.game.ServerboundSetStructureBlockPacket
- XXX.protocol.game.ServerboundSetTestBlockPacket
+ XXX.protocol.game.ServerboundSignUpdatePacket
- XXX.protocol.game.ServerboundSwingPacket
+ XXX.protocol.game.ServerboundTeleportToEntityPacket
- XXX.protocol.game.ServerboundTestInstanceBlockActionPacket
+ XXX.protocol.game.ServerboundTestInstanceBlockActionPacket$Action
- XXX.protocol.game.ServerboundUseItemOnPacket
+ XXX.protocol.game.ServerboundUseItemPacket
- XXX.protocol.game.ServerGamePacketListener
+ XXX.protocol.game.ServerPacketListener
- XXX.protocol.game.VecDeltaCodec
- XXX.protocol.handshake.ClientIntent
+ XXX.protocol.handshake.ClientIntentionPacket
- XXX.protocol.handshake.HandshakePacketTypes
+ XXX.protocol.handshake.HandshakeProtocols
+ XXX.protocol.handshake.package-info
- XXX.protocol.handshake.ServerHandshakePacketListener
+ XXX.protocol.login.ClientboundCustomQueryPacket
- XXX.protocol.login.ClientboundHelloPacket
+ XXX.protocol.login.ClientboundLoginCompressionPacket
- XXX.protocol.login.ClientboundLoginDisconnectPacket
+ XXX.protocol.login.ClientboundLoginFinishedPacket
- XXX.protocol.login.ClientLoginPacketListener
- XXX.protocol.login.LoginPacketTypes
+ XXX.protocol.login.LoginProtocols
- XXX.protocol.login.package-info
+ XXX.protocol.login.ServerboundCustomQueryAnswerPacket
- XXX.protocol.login.ServerboundHelloPacket
+ XXX.protocol.login.ServerboundKeyPacket
- XXX.protocol.login.ServerboundLoginAcknowledgedPacket
- XXX.protocol.login.ServerLoginPacketListener
+ XXX.protocol.ping.ClientboundPongResponsePacket
- XXX.protocol.ping.ClientPongPacketListener
+ XXX.protocol.ping.package-info
- XXX.protocol.ping.PingPacketTypes
- XXX.protocol.ping.ServerboundPingRequestPacket
+ XXX.protocol.ping.ServerPingPacketListener
+ XXX.protocol.status.ClientboundStatusResponsePacket
- XXX.protocol.status.ClientStatusPacketListener
- XXX.protocol.status.package-info
+ XXX.protocol.status.ServerboundStatusRequestPacket
- XXX.protocol.status.ServerStatus
+ XXX.protocol.status.ServerStatus$Favicon
- XXX.protocol.status.ServerStatus$Players
+ XXX.protocol.status.ServerStatus$Version
- XXX.protocol.status.ServerStatusPacketListener
- XXX.protocol.status.StatusPacketTypes
+ XXX.protocol.status.StatusProtocols
+ XXX.recipes.packs.package-info
- XXX.recipes.packs.VanillaRecipeProvider
+ XXX.recipes.packs.VanillaRecipeProvider$Runner
- XXX.recipes.packs.VanillaRecipeProvider$TrimTemplate
- XXX.selector.options.EntitySelectorOptions
+ XXX.selector.options.EntitySelectorOptions$Modifier
- XXX.selector.options.EntitySelectorOptions$Option
+ XXX.selector.options.package-info
+ XXX.synchronization.brigadier.DoubleArgumentInfo
- XXX.synchronization.brigadier.DoubleArgumentInfo$Template
+ XXX.synchronization.brigadier.FloatArgumentInfo
- XXX.synchronization.brigadier.FloatArgumentInfo$Template
+ XXX.synchronization.brigadier.IntegerArgumentInfo
- XXX.synchronization.brigadier.IntegerArgumentInfo$Template
+ XXX.synchronization.brigadier.LongArgumentInfo
- XXX.synchronization.brigadier.LongArgumentInfo$Template
- XXX.synchronization.brigadier.package-info
+ XXX.synchronization.brigadier.StringArgumentSerializer
- XXX.synchronization.brigadier.StringArgumentSerializer$1
+ XXX.synchronization.brigadier.StringArgumentSerializer$Template
+ XXX.util.context.ContextKey
- XXX.util.context.ContextKeySet
+ XXX.util.context.ContextKeySet$Builder
- XXX.util.context.ContextMap
+ XXX.util.context.ContextMap$Builder
- XXX.util.context.package-info
+ XXX.util.datafix.DataFixers
- XXX.util.datafix.DataFixers$1
+ XXX.util.datafix.DataFixers$2
+ XXX.util.datafix.DataFixTypes
- XXX.util.datafix.DataFixTypes$1
- XXX.util.datafix.ExtraDataFixUtils
+ XXX.util.datafix.LegacyComponentDataFixUtils
- XXX.util.datafix.PackedBitStorage
- XXX.util.debugchart.AbstractSampleLogger
+ XXX.util.debugchart.DebugSampleSubscriptionTracker
- XXX.util.debugchart.DebugSampleSubscriptionTracker$SubscriptionRequest
+ XXX.util.debugchart.DebugSampleSubscriptionTracker$SubscriptionStartedAt
- XXX.util.debugchart.LocalSampleLogger
- XXX.util.debugchart.package-info
+ XXX.util.debugchart.RemoteDebugSampleType
- XXX.util.debugchart.RemoteSampleLogger
+ XXX.util.debugchart.SampleLogger
- XXX.util.debugchart.SampleStorage
+ XXX.util.debugchart.TpsDebugDimensions
+ XXX.util.eventlog.EventLogDirectory
- XXX.util.eventlog.EventLogDirectory$CompressedFile
+ XXX.util.eventlog.EventLogDirectory$File
- XXX.util.eventlog.EventLogDirectory$FileId
+ XXX.util.eventlog.EventLogDirectory$FileList
- XXX.util.eventlog.EventLogDirectory$RawFile
+ XXX.util.eventlog.JsonEventLog
- XXX.util.eventlog.JsonEventLog$1
+ XXX.util.eventlog.JsonEventLogReader
- XXX.util.eventlog.JsonEventLogReader$1
+ XXX.util.eventlog.package-info
- XXX.util.parsing.package-info
+ XXX.util.profiling.ActiveProfiler
- XXX.util.profiling.ActiveProfiler$PathEntry
+ XXX.util.profiling.ContinuousProfiler
- XXX.util.profiling.EmptyProfileResults
+ XXX.util.profiling.FilledProfileResults
- XXX.util.profiling.FilledProfileResults$1
+ XXX.util.profiling.FilledProfileResults$CounterCollector
- XXX.util.profiling.InactiveProfiler
+ XXX.util.profiling.package-info
+ XXX.util.profiling.ProfileCollector
+ XXX.util.profiling.Profiler
- XXX.util.profiling.Profiler$Scope
- XXX.util.profiling.ProfileResults
+ XXX.util.profiling.ProfilerFiller
- XXX.util.profiling.ProfilerFiller$CombinedProfileFiller
+ XXX.util.profiling.ProfilerPathEntry
- XXX.util.profiling.ResultField
+ XXX.util.profiling.SingleTickProfiler
- XXX.util.profiling.TracyZoneFiller
+ XXX.util.profiling.TracyZoneFiller$PlotAndValue
- XXX.util.profiling.Zone
+ XXX.util.random.package-info
- XXX.util.random.Weighted
+ XXX.util.random.WeightedList
- XXX.util.random.WeightedList$Builder
+ XXX.util.random.WeightedList$Compact
- XXX.util.random.WeightedList$Flat
+ XXX.util.random.WeightedList$Selector
- XXX.util.random.WeightedRandom
- XXX.util.thread.AbstractConsecutiveExecutor
+ XXX.util.thread.AbstractConsecutiveExecutor$Status
- XXX.util.thread.BlockableEventLoop
+ XXX.util.thread.ConsecutiveExecutor
- XXX.util.thread.NamedThreadFactory
- XXX.util.thread.package-info
+ XXX.util.thread.ParallelMapTransform
- XXX.util.thread.ParallelMapTransform$BatchedTaskSplitter
+ XXX.util.thread.ParallelMapTransform$Container
- XXX.util.thread.ParallelMapTransform$SingleTaskSplitter
+ XXX.util.thread.ParallelMapTransform$SplitterBase
- XXX.util.thread.PriorityConsecutiveExecutor
+ XXX.util.thread.ReentrantBlockableEventLoop
- XXX.util.thread.StrictQueue
+ XXX.util.thread.StrictQueue$FixedPriorityQueue
- XXX.util.thread.StrictQueue$QueueStrictQueue
+ XXX.util.thread.StrictQueue$RunnableWithPriority
- XXX.util.thread.TaskScheduler
+ XXX.util.thread.TaskScheduler$1
+ XXX.util.valueproviders.BiasedToBottomInt
- XXX.util.valueproviders.ClampedInt
+ XXX.util.valueproviders.ClampedNormalFloat
- XXX.util.valueproviders.ClampedNormalInt
+ XXX.util.valueproviders.ConstantFloat
- XXX.util.valueproviders.ConstantInt
+ XXX.util.valueproviders.FloatProvider
- XXX.util.valueproviders.FloatProviderType
+ XXX.util.valueproviders.IntProvider
- XXX.util.valueproviders.IntProviderType
+ XXX.util.valueproviders.MultipliedFloats
+ XXX.util.valueproviders.package-info
- XXX.util.valueproviders.SampledFloat
+ XXX.util.valueproviders.TrapezoidFloat
- XXX.util.valueproviders.UniformFloat
+ XXX.util.valueproviders.UniformInt
- XXX.util.valueproviders.WeightedListInt
- XXX.util.worldupdate.package-info
- XXX.util.worldupdate.WorldUpgrader
+ XXX.util.worldupdate.WorldUpgrader$AbstractUpgrader
- XXX.util.worldupdate.WorldUpgrader$ChunkUpgrader
+ XXX.util.worldupdate.WorldUpgrader$DimensionToUpgrade
- XXX.util.worldupdate.WorldUpgrader$EntityUpgrader
+ XXX.util.worldupdate.WorldUpgrader$FileToUpgrade
- XXX.util.worldupdate.WorldUpgrader$PoiUpgrader
+ XXX.util.worldupdate.WorldUpgrader$SimpleRegionStorageUpgrader
- XXX.world.damagesource.CombatEntry
+ XXX.world.damagesource.CombatRules
- XXX.world.damagesource.CombatTracker
+ XXX.world.damagesource.DamageEffects
- XXX.world.damagesource.DamageScaling
+ XXX.world.damagesource.DamageSource
- XXX.world.damagesource.DamageSource$1
+ XXX.world.damagesource.DamageSources
- XXX.world.damagesource.DamageType
+ XXX.world.damagesource.DamageTypes
- XXX.world.damagesource.DeathMessageType
+ XXX.world.damagesource.FallLocation
- XXX.world.damagesource.package-info
+ XXX.world.effect.AbsorptionMobEffect
- XXX.world.effect.BadOmenMobEffect
+ XXX.world.effect.HealOrHarmMobEffect
- XXX.world.effect.HungerMobEffect
+ XXX.world.effect.InfestedMobEffect
- XXX.world.effect.InstantenousMobEffect
+ XXX.world.effect.MobEffect
- XXX.world.effect.MobEffect$AttributeTemplate
+ XXX.world.effect.MobEffectCategory
- XXX.world.effect.MobEffectInstance
+ XXX.world.effect.MobEffectInstance$BlendState
- XXX.world.effect.MobEffectInstance$Details
- XXX.world.effect.MobEffects
+ XXX.world.effect.MobEffectUtil
+ XXX.world.effect.OozingMobEffect
- XXX.world.effect.OozingMobEffect$NearbySlimes
- XXX.world.effect.package-info
+ XXX.world.effect.PoisonMobEffect
- XXX.world.effect.RaidOmenMobEffect
+ XXX.world.effect.RegenerationMobEffect
- XXX.world.effect.SaturationMobEffect
+ XXX.world.effect.WeavingMobEffect
- XXX.world.effect.WindChargedMobEffect
+ XXX.world.effect.WitherMobEffect
+ XXX.world.entity.AgeableMob
- XXX.world.entity.AgeableMob$AgeableMobGroupData
+ XXX.world.entity.AnimationState
- XXX.world.entity.AreaEffectCloud
+ XXX.world.entity.Attackable
- XXX.world.entity.Avatar
- XXX.world.flag.FeatureElement
+ XXX.world.flag.FeatureFlag
- XXX.world.flag.FeatureFlagRegistry
+ XXX.world.flag.FeatureFlagRegistry$Builder
- XXX.world.flag.FeatureFlags
- XXX.world.flag.FeatureFlagSet
+ XXX.world.flag.FeatureFlagUniverse
+ XXX.world.flag.package-info
- XXX.world.food.FoodConstants
+ XXX.world.food.FoodData
- XXX.world.food.FoodProperties
+ XXX.world.food.FoodProperties$Builder
- XXX.world.food.Foods
+ XXX.world.food.package-info
- XXX.world.inventory.AbstractContainerMenu
+ XXX.world.inventory.AbstractContainerMenu$1
- XXX.world.inventory.AbstractCraftingMenu
+ XXX.world.inventory.AbstractCraftingMenu$1
- XXX.world.inventory.AbstractFurnaceMenu
+ XXX.world.inventory.AbstractFurnaceMenu$1
- XXX.world.inventory.AnvilMenu
+ XXX.world.inventory.ArmorSlot
- XXX.world.inventory.BeaconMenu
+ XXX.world.inventory.BeaconMenu$1
- XXX.world.inventory.BeaconMenu$PaymentSlot
+ XXX.world.inventory.BlastFurnaceMenu
- XXX.world.inventory.BrewingStandMenu
+ XXX.world.inventory.BrewingStandMenu$FuelSlot
- XXX.world.inventory.BrewingStandMenu$IngredientsSlot
+ XXX.world.inventory.BrewingStandMenu$PotionSlot
- XXX.world.inventory.CartographyTableMenu
+ XXX.world.inventory.CartographyTableMenu$1
- XXX.world.inventory.CartographyTableMenu$2
+ XXX.world.inventory.CartographyTableMenu$3
- XXX.world.inventory.CartographyTableMenu$4
+ XXX.world.inventory.CartographyTableMenu$5
- XXX.world.inventory.ChestMenu
+ XXX.world.inventory.ClickAction
- XXX.world.inventory.ClickType
+ XXX.world.inventory.ContainerData
- XXX.world.inventory.ContainerLevelAccess
+ XXX.world.inventory.ContainerLevelAccess$1
- XXX.world.inventory.ContainerLevelAccess$2
+ XXX.world.inventory.ContainerListener
- XXX.world.inventory.ContainerSynchronizer
+ XXX.world.inventory.CrafterMenu
- XXX.world.inventory.CrafterSlot
+ XXX.world.inventory.CraftingContainer
- XXX.world.inventory.CraftingMenu
+ XXX.world.inventory.DataSlot
- XXX.world.inventory.DataSlot$1
+ XXX.world.inventory.DataSlot$2
- XXX.world.inventory.DataSlot$3
+ XXX.world.inventory.DispenserMenu
- XXX.world.inventory.EnchantmentMenu
+ XXX.world.inventory.EnchantmentMenu$1
- XXX.world.inventory.EnchantmentMenu$2
+ XXX.world.inventory.EnchantmentMenu$3
- XXX.world.inventory.FurnaceFuelSlot
+ XXX.world.inventory.FurnaceMenu
- XXX.world.inventory.FurnaceResultSlot
+ XXX.world.inventory.GrindstoneMenu
- XXX.world.inventory.GrindstoneMenu$1
+ XXX.world.inventory.GrindstoneMenu$2
- XXX.world.inventory.GrindstoneMenu$3
+ XXX.world.inventory.GrindstoneMenu$4
- XXX.world.inventory.HopperMenu
+ XXX.world.inventory.HorseInventoryMenu
- XXX.world.inventory.HorseInventoryMenu$1
+ XXX.world.inventory.HorseInventoryMenu$2
- XXX.world.inventory.InventoryMenu
+ XXX.world.inventory.InventoryMenu$1
- XXX.world.inventory.ItemCombinerMenu
+ XXX.world.inventory.ItemCombinerMenu$1
- XXX.world.inventory.ItemCombinerMenu$2
+ XXX.world.inventory.ItemCombinerMenu$3
- XXX.world.inventory.ItemCombinerMenu$4
+ XXX.world.inventory.ItemCombinerMenuSlotDefinition
- XXX.world.inventory.ItemCombinerMenuSlotDefinition$Builder
+ XXX.world.inventory.ItemCombinerMenuSlotDefinition$SlotDefinition
- XXX.world.inventory.LecternMenu
+ XXX.world.inventory.LecternMenu$1
- XXX.world.inventory.LoomMenu
+ XXX.world.inventory.LoomMenu$1
- XXX.world.inventory.LoomMenu$2
+ XXX.world.inventory.LoomMenu$3
- XXX.world.inventory.LoomMenu$4
+ XXX.world.inventory.LoomMenu$5
- XXX.world.inventory.LoomMenu$6
+ XXX.world.inventory.MenuConstructor
- XXX.world.inventory.MenuType
+ XXX.world.inventory.MenuType$MenuSupplier
- XXX.world.inventory.MerchantContainer
+ XXX.world.inventory.MerchantMenu
- XXX.world.inventory.MerchantResultSlot
+ XXX.world.inventory.NonInteractiveResultSlot
- XXX.world.inventory.package-info
- XXX.world.inventory.PlayerEnderChestContainer
+ XXX.world.inventory.RecipeBookMenu
- XXX.world.inventory.RecipeBookMenu$PostPlaceAction
+ XXX.world.inventory.RecipeBookType
- XXX.world.inventory.RecipeCraftingHolder
+ XXX.world.inventory.RemoteSlot
- XXX.world.inventory.RemoteSlot$1
+ XXX.world.inventory.RemoteSlot$Synchronized
- XXX.world.inventory.ResultContainer
+ XXX.world.inventory.ResultSlot
- XXX.world.inventory.ShulkerBoxMenu
+ XXX.world.inventory.ShulkerBoxSlot
- XXX.world.inventory.SimpleContainerData
+ XXX.world.inventory.Slot
- XXX.world.inventory.SlotRange
+ XXX.world.inventory.SlotRange$1
- XXX.world.inventory.SlotRanges
+ XXX.world.inventory.SmithingMenu
- XXX.world.inventory.SmokerMenu
+ XXX.world.inventory.StackedContentsCompatible
- XXX.world.inventory.StonecutterMenu
+ XXX.world.inventory.StonecutterMenu$1
- XXX.world.inventory.StonecutterMenu$2
+ XXX.world.inventory.TransientCraftingContainer
- XXX.world.item.AdventureModePredicate
+ XXX.world.item.AirItem
- XXX.world.item.ArmorStandItem
+ XXX.world.item.ArrowItem
- XXX.world.item.AxeItem
+ XXX.world.item.BannerItem
- XXX.world.item.BedItem
+ XXX.world.item.BlockItem
- XXX.world.item.BoatItem
+ XXX.world.item.BoneMealItem
- XXX.world.item.BoneMealItem$1
+ XXX.world.item.BottleItem
- XXX.world.item.BowItem
+ XXX.world.item.BrushItem
- XXX.world.item.BrushItem$1
+ XXX.world.item.BrushItem$DustParticlesDelta
- XXX.world.item.BucketItem
+ XXX.world.item.BundleItem
- XXX.world.item.BundleItem$1
+ XXX.world.item.CompassItem
- XXX.world.item.CreativeModeTab
+ XXX.world.item.CreativeModeTab$Builder
- XXX.world.item.CreativeModeTab$DisplayItemsGenerator
+ XXX.world.item.CreativeModeTab$ItemDisplayBuilder
- XXX.world.item.CreativeModeTab$ItemDisplayParameters
+ XXX.world.item.CreativeModeTab$Output
- XXX.world.item.CreativeModeTab$Row
+ XXX.world.item.CreativeModeTab$TabVisibility
- XXX.world.item.CreativeModeTab$Type
+ XXX.world.item.CreativeModeTabs
- XXX.world.item.CrossbowItem
+ XXX.world.item.CrossbowItem$ChargeType
- XXX.world.item.CrossbowItem$ChargingSounds
+ XXX.world.item.DebugStickItem
- XXX.world.item.DiscFragmentItem
+ XXX.world.item.DispensibleContainerItem
- XXX.world.item.DoubleHighBlockItem
+ XXX.world.item.DyeColor
- XXX.world.item.DyeItem
+ XXX.world.item.EggItem
- XXX.world.item.EitherHolder
+ XXX.world.item.EmptyMapItem
- XXX.world.item.EndCrystalItem
+ XXX.world.item.EnderEyeItem
- XXX.world.item.EnderpearlItem
+ XXX.world.item.ExperienceBottleItem
- XXX.world.item.FireChargeItem
+ XXX.world.item.FireworkRocketItem
- XXX.world.item.FishingRodItem
+ XXX.world.item.FlintAndSteelItem
- XXX.world.item.FoodOnAStickItem
+ XXX.world.item.GameMasterBlockItem
- XXX.world.item.GlowInkSacItem
+ XXX.world.item.HangingEntityItem
- XXX.world.item.HangingSignItem
+ XXX.world.item.HoeItem
- XXX.world.item.HoneycombItem
+ XXX.world.item.InkSacItem
- XXX.world.item.Instrument
+ XXX.world.item.InstrumentItem
- XXX.world.item.Instruments
+ XXX.world.item.Item
- XXX.world.item.Item$Properties
+ XXX.world.item.Item$TooltipContext
- XXX.world.item.Item$TooltipContext$1
+ XXX.world.item.Item$TooltipContext$2
- XXX.world.item.Item$TooltipContext$3
+ XXX.world.item.ItemCooldowns
- XXX.world.item.ItemCooldowns$CooldownInstance
+ XXX.world.item.ItemDisplayContext
- XXX.world.item.ItemFrameItem
- XXX.world.item.Items
+ XXX.world.item.ItemStack
- XXX.world.item.ItemStack$1
+ XXX.world.item.ItemStack$2
- XXX.world.item.ItemStack$3
+ XXX.world.item.ItemStack$4
- XXX.world.item.ItemStackLinkedSet
+ XXX.world.item.ItemStackLinkedSet$1
- XXX.world.item.ItemUseAnimation
+ XXX.world.item.ItemUtils
+ XXX.world.item.JukeboxPlayable
- XXX.world.item.JukeboxSong
+ XXX.world.item.JukeboxSongPlayer
- XXX.world.item.JukeboxSongPlayer$OnSongChanged
+ XXX.world.item.JukeboxSongs
- XXX.world.item.KnowledgeBookItem
+ XXX.world.item.LeadItem
- XXX.world.item.LingeringPotionItem
+ XXX.world.item.MaceItem
- XXX.world.item.MapItem
+ XXX.world.item.MapItem$1
- XXX.world.item.MinecartItem
+ XXX.world.item.MobBucketItem
- XXX.world.item.NameTagItem
+ XXX.world.item.package-info
+ XXX.world.item.PlaceOnWaterBlockItem
- XXX.world.item.PlayerHeadItem
+ XXX.world.item.PotionItem
- XXX.world.item.ProjectileItem
+ XXX.world.item.ProjectileItem$DispenseConfig
- XXX.world.item.ProjectileItem$DispenseConfig$Builder
+ XXX.world.item.ProjectileItem$PositionFunction
- XXX.world.item.ProjectileWeaponItem
+ XXX.world.item.Rarity
- XXX.world.item.ScaffoldingBlockItem
+ XXX.world.item.ServerItemCooldowns
- XXX.world.item.ShearsItem
+ XXX.world.item.ShieldItem
- XXX.world.item.ShovelItem
+ XXX.world.item.SignApplicator
- XXX.world.item.SignItem
+ XXX.world.item.SmithingTemplateItem
- XXX.world.item.SnowballItem
+ XXX.world.item.SolidBucketItem
- XXX.world.item.SpawnEggItem
+ XXX.world.item.SpectralArrowItem
- XXX.world.item.SplashPotionItem
+ XXX.world.item.SpyglassItem
- XXX.world.item.StandingAndWallBlockItem
+ XXX.world.item.ThrowablePotionItem
- XXX.world.item.TippedArrowItem
+ XXX.world.item.ToolMaterial
- XXX.world.item.TooltipFlag
+ XXX.world.item.TooltipFlag$Default
- XXX.world.item.TridentItem
+ XXX.world.item.WeatheringCopperItems
- XXX.world.item.WindChargeItem
+ XXX.world.item.WritableBookItem
- XXX.world.item.WrittenBookItem
+ XXX.world.level.BaseCommandBlock
- XXX.world.level.BaseCommandBlock$CloseableCommandBlockSource
+ XXX.world.level.BaseSpawner
- XXX.world.level.BlockAndTintGetter
+ XXX.world.level.BlockCollisions
- XXX.world.level.BlockEventData
+ XXX.world.level.BlockGetter
- XXX.world.level.BlockGetter$BlockStepVisitor
+ XXX.world.level.ChunkPos
- XXX.world.level.ChunkPos$1
+ XXX.world.level.ChunkPos$2
- XXX.world.level.ClipBlockStateContext
+ XXX.world.level.ClipContext
- XXX.world.level.ClipContext$Block
+ XXX.world.level.ClipContext$Fluid
- XXX.world.level.ClipContext$ShapeGetter
+ XXX.world.level.CollisionGetter
- XXX.world.level.ColorMapColorUtil
+ XXX.world.level.ColorResolver
- XXX.world.level.CommonLevelAccessor
+ XXX.world.level.CustomSpawner
- XXX.world.level.DataPackConfig
+ XXX.world.level.DryFoliageColor
- XXX.world.level.EmptyBlockAndTintGetter
+ XXX.world.level.EmptyBlockGetter
- XXX.world.level.EntityBasedExplosionDamageCalculator
+ XXX.world.level.EntityGetter
- XXX.world.level.Explosion
+ XXX.world.level.Explosion$BlockInteraction
- XXX.world.level.ExplosionDamageCalculator
+ XXX.world.level.FoliageColor
- XXX.world.level.GameRules
+ XXX.world.level.GameRules$BooleanValue
- XXX.world.level.GameRules$Category
+ XXX.world.level.GameRules$GameRuleTypeVisitor
- XXX.world.level.GameRules$IntegerValue
+ XXX.world.level.GameRules$Key
- XXX.world.level.GameRules$Type
+ XXX.world.level.GameRules$Value
- XXX.world.level.GameRules$VisitorCaller
+ XXX.world.level.GameType
- XXX.world.level.GrassColor
+ XXX.world.level.ItemLike
- XXX.world.level.Level
+ XXX.world.level.Level$1
- XXX.worldgen.biome.BiomeData
+ XXX.worldgen.biome.EndBiomes
- XXX.worldgen.biome.NetherBiomes
+ XXX.worldgen.biome.OverworldBiomes
- XXX.worldgen.biome.package-info
+ XXX.worldgen.features.AquaticFeatures
- XXX.worldgen.features.CaveFeatures
+ XXX.worldgen.features.EndFeatures
- XXX.worldgen.features.FeatureUtils
+ XXX.worldgen.features.MiscOverworldFeatures
- XXX.worldgen.features.NetherFeatures
+ XXX.worldgen.features.OreFeatures
+ XXX.worldgen.features.package-info
- XXX.worldgen.features.PileFeatures
+ XXX.worldgen.features.TreeFeatures
- XXX.worldgen.features.VegetationFeatures
+ XXX.worldgen.placement.AquaticPlacements
- XXX.worldgen.placement.CavePlacements
+ XXX.worldgen.placement.EndPlacements
- XXX.worldgen.placement.MiscOverworldPlacements
+ XXX.worldgen.placement.NetherPlacements
- XXX.worldgen.placement.OrePlacements
+ XXX.worldgen.placement.package-info
+ XXX.worldgen.placement.PlacementUtils
- XXX.worldgen.placement.TreePlacements
+ XXX.worldgen.placement.VegetationPlacements
- XXX.worldgen.placement.VillagePlacements
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.advancements.critereon.MinMaxBounds +2M -11M | +1P -2P
```
```
XXX.server.commands.SpectateCommand +4M -3M | +1P
```
```
XXX.server.level.ServerPlayer +24M -13M | +3P
```
```
XXX.server.players.PlayerList +1M
```
```
XXX.datafix.fixes.References +1P
```
```
XXX.world.entity.EntityType +1P
```
```
XXX.entity.decoration.HangingEntity +3M -2M | -1P
```
```
XXX.entity.decoration.ItemFrame -1M
```
```
XXX.entity.npc.WanderingTraderSpawner +1M -1M
```
```
XXX.entity.player.PlayerModelPart +1M | +1P
```
```
XXX.level.block.CopperGolemStatueBlock +1M
```
```
XXX.level.block.SideChainPartBlock$Neighbor +1P
```
```
XXX.level.block.SideChainPartBlock$SideChainNeighbor +1M
```
```
XXX.level.border.BorderChangeListener +7P -7P
```
```
XXX.level.chunk.HashMapPalette +9M -9M | -2P
```
```
XXX.level.chunk.Palette$Factory +1P -1P
```
```
XXX.level.chunk.PalettedContainer +19M -21M | +1P -3P
```
```
XXX.level.levelgen.PhantomSpawner +1M -1M
```
```
XXX.level.storage.DerivedLevelData +2M -2M
```
```
XXX.phys.shapes.EntityCollisionContext -1M | -1P
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.MinMaxBounds
</summary>

```diff
+ App lambda$createCodec$0(Codec,MinMaxBounds$BoundsFactory,RecordCodecBuilder$Instance)
+ boolean isAllowedInputChat(StringReader)
+ Codec createCodec(Codec,MinMaxBounds$BoundsFactory)
+ Either lambda$createCodec$4(MinMaxBounds)
+ MinMaxBounds fromReader(StringReader,MinMaxBounds$BoundsFromReaderFactory,Function,Supplier,Function)
+ MinMaxBounds lambda$createCodec$1(MinMaxBounds)
+ MinMaxBounds lambda$createCodec$2(MinMaxBounds$BoundsFactory,Number)
+ MinMaxBounds lambda$createCodec$3(MinMaxBounds$BoundsFactory,Either)
- Optional max()
- Optional min()
+ Optional readNumber(StringReader,Function,Supplier)
+ Optional unwrapPoint()
+ StreamCodec createStreamCodec(StreamCodec,MinMaxBounds$BoundsFactory)
```

</details>
<details>
<summary>
net.minecraft.server.commands.SpectateCommand
</summary>

```diff
+ Component lambda$spectate$4(Entity)
+ Component lambda$spectate$5()
- Component lambda$spectate$5(Entity)
- Component lambda$spectate$6()
+ int lambda$register$1(CommandContext)
- int lambda$register$4(CommandContext)
- Message lambda$static$1(Object)
```

</details>
<details>
<summary>
net.minecraft.server.level.ServerPlayer
</summary>

```diff
+ boolean lambda$startSleepInBed$12(Monster)
- boolean lambda$startSleepInBed$14(Monster)
- boolean lambda$tellNeutralMobsThatIDied$10(Mob)
+ boolean lambda$tellNeutralMobsThatIDied$8(Mob)
- boolean setEntityOnShoulder(CompoundTag)
- CompoundTag getShoulderEntityLeft()
- CompoundTag getShoulderEntityRight()
+ Packet lambda$die$7(Component)
- Packet lambda$die$9(Component)
+ Packet lambda$sendSystemMessage$16(Component)
- Packet lambda$sendSystemMessage$18(Component)
+ ServerPlayer$RespawnPosAngle lambda$findRespawnAndUseSpawnBlock$10(BlockPos,Vec3)
+ ServerPlayer$RespawnPosAngle lambda$findRespawnAndUseSpawnBlock$11(BlockPos,Vec3)
- ServerPlayer$RespawnPosAngle lambda$findRespawnAndUseSpawnBlock$12(BlockPos,Vec3)
- ServerPlayer$RespawnPosAngle lambda$findRespawnAndUseSpawnBlock$13(BlockPos,Vec3)
+ Stream lambda$awardRecipesByKey$15(ResourceKey)
- Stream lambda$awardRecipesByKey$17(ResourceKey)
- String lambda$respawnEntityOnShoulder$5()
+ Style lambda$die$6(Component,Style)
- Style lambda$die$8(Component,Style)
- void handleShoulderEntities()
+ void lambda$awardStat$14(int,ScoreAccess)
- void lambda$awardStat$16(int,ScoreAccess)
+ void lambda$drop$17(Inventory,int)
- void lambda$drop$19(Inventory,int)
- void lambda$respawnEntityOnShoulder$6(ServerLevel,Entity)
+ void lambda$startSleepInBed$13(Unit)
- void lambda$startSleepInBed$15(Unit)
- void lambda$tellNeutralMobsThatIDied$11(Mob)
+ void lambda$tellNeutralMobsThatIDied$9(Mob)
+ void lambda$updateScoreForCriteria$5(int,ScoreAccess)
- void lambda$updateScoreForCriteria$7(int,ScoreAccess)
- void playShoulderEntityAmbientSound(CompoundTag)
- void removeEntitiesOnShoulder()
- void respawnEntityOnShoulder(CompoundTag)
- void setShoulderEntityLeft(CompoundTag)
- void setShoulderEntityRight(CompoundTag)
```

</details>
<details>
<summary>
net.minecraft.server.players.PlayerList
</summary>

```diff
- Component getReasonMessage(BanListEntry)
```

</details>
<details>
<summary>
net.minecraft.world.entity.decoration.HangingEntity
</summary>

```diff
- boolean canCoexist(boolean)
- boolean lambda$canCoexist$1(boolean,HangingEntity)
+ boolean lambda$static$0(Entity)
- boolean lambda$survives$0(BlockPos)
+ boolean lambda$survives$1(BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.entity.decoration.ItemFrame
</summary>

```diff
+ boolean lambda$survives$0(Entity)
```

</details>
<details>
<summary>
net.minecraft.world.entity.npc.WanderingTraderSpawner
</summary>

```diff
+ void tick(ServerLevel,boolean,boolean)
- void tick(ServerLevel,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.entity.player.PlayerModelPart
</summary>

```diff
- String getSerializedName()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CopperGolemStatueBlock
</summary>

```diff
- ItemStack getCloneItemStack(LevelReader,BlockPos,BlockState,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SideChainPartBlock$SideChainNeighbor
</summary>

```diff
- boolean isConnectable()
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.HashMapPalette
</summary>

```diff
+ int getSerializedSize()
- int getSerializedSize(IdMap)
- int idFor(Object,PaletteResize)
+ int idFor(Object)
- Palette copy()
+ Palette copy(PaletteResize)
+ Palette create(int,IdMap,PaletteResize,List)
- Palette create(int,List)
+ void <init>(IdMap,int,PaletteResize,CrudeIncrementalIntIdentityHashBiMap)
+ void <init>(IdMap,int,PaletteResize,List)
+ void <init>(IdMap,int,PaletteResize)
- void <init>(int,CrudeIncrementalIntIdentityHashBiMap)
- void <init>(int,List)
- void <init>(int)
- void read(FriendlyByteBuf,IdMap)
+ void read(FriendlyByteBuf)
- void write(FriendlyByteBuf,IdMap)
+ void write(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.PalettedContainer
</summary>

```diff
- App lambda$codec$2(Codec,Object,RecordCodecBuilder$Instance)
+ App lambda$codec$3(Codec,Object,RecordCodecBuilder$Instance)
- Codec codec(Codec,Strategy,Object,PalettedContainerRO$Unpacker)
+ Codec codec(IdMap,Codec,PalettedContainer$Strategy,Object,PalettedContainerRO$Unpacker)
- Codec codecRO(Codec,Strategy,Object)
+ Codec codecRO(IdMap,Codec,PalettedContainer$Strategy,Object)
- Codec codecRW(Codec,Strategy,Object)
+ Codec codecRW(IdMap,Codec,PalettedContainer$Strategy,Object)
- DataResult lambda$codec$3(PalettedContainerRO$Unpacker,Strategy,PalettedContainerRO$PackedData)
+ DataResult lambda$codec$4(PalettedContainerRO$Unpacker,IdMap,PalettedContainer$Strategy,PalettedContainerRO$PackedData)
- DataResult lambda$codecRO$1(Strategy,PalettedContainerRO$PackedData)
+ DataResult lambda$codecRO$2(IdMap,PalettedContainer$Strategy,PalettedContainerRO$PackedData)
+ DataResult unpack(IdMap,PalettedContainer$Strategy,PalettedContainerRO$PackedData)
- DataResult unpack(Strategy,PalettedContainerRO$PackedData)
- int bitsPerEntry()
+ int lambda$new$0(int,Object)
+ int lambda$pack$11(HashMapPalette,int)
+ int lambda$unpack$8(int,Object)
+ int lambda$unpack$9(IdMap,Palette,int)
- int[] reencodeContents(BitStorage,Palette,Palette)
- PalettedContainerRO lambda$codecRO$0(PalettedContainer)
+ PalettedContainerRO lambda$codecRO$1(PalettedContainer)
- PalettedContainerRO$PackedData lambda$codec$4(Strategy,PalettedContainerRO)
+ PalettedContainerRO$PackedData lambda$codec$5(IdMap,PalettedContainer$Strategy,PalettedContainerRO)
+ PalettedContainerRO$PackedData pack(IdMap,PalettedContainer$Strategy)
- PalettedContainerRO$PackedData pack(Strategy)
+ String lambda$unpack$10(SimpleBitStorage$InitializationException)
- String lambda$unpack$6(int,PalettedContainerRO$PackedData)
- String lambda$unpack$8(SimpleBitStorage$InitializationException)
+ void <init>(IdMap,Object,PalettedContainer$Strategy)
+ void <init>(IdMap,PalettedContainer$Strategy,PalettedContainer$Configuration,BitStorage,List)
- void <init>(Object,Strategy)
- void <init>(Strategy,Configuration,BitStorage,Palette)
- void lambda$count$10(PalettedContainer$CountConsumer,Int2IntMap$Entry)
+ void lambda$count$12(Int2IntOpenHashMap,int)
+ void lambda$count$13(PalettedContainer$CountConsumer,Int2IntMap$Entry)
- void lambda$count$9(Int2IntOpenHashMap,int)
- void lambda$getAll$5(Consumer,Palette,int)
+ void lambda$getAll$6(Consumer,Palette,int)
+ void swapPalette(int[],IntUnaryOperator)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.PhantomSpawner
</summary>

```diff
+ void tick(ServerLevel,boolean,boolean)
- void tick(ServerLevel,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.DerivedLevelData
</summary>

```diff
- Optional getLegacyWorldBorderSettings()
- void setLegacyWorldBorderSettings(Optional)
+ void setWorldBorder(WorldBorder$Settings)
+ WorldBorder$Settings getWorldBorder()
```

</details>
<details>
<summary>
net.minecraft.world.phys.shapes.EntityCollisionContext
</summary>

```diff
+ void <clinit>()
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
+ net.minecraft.Optionull
+ net.minecraft.ReportedException
- net.minecraft.ReportType
- net.minecraft.ResourceLocationException
+ net.minecraft.SharedConstants
- net.minecraft.SuppressForbidden
+ net.minecraft.SystemReport
- net.minecraft.TracingExecutor
+ net.minecraft.Util
- net.minecraft.Util$1
+ net.minecraft.Util$10
- net.minecraft.Util$11
+ net.minecraft.Util$2
- net.minecraft.Util$5
+ net.minecraft.Util$6
- net.minecraft.Util$7
+ net.minecraft.Util$8
- net.minecraft.Util$9
+ net.minecraft.Util$OS
- net.minecraft.Util$OS$1
+ net.minecraft.Util$OS$2
- net.minecraft.WorldVersion
+ net.minecraft.WorldVersion$1
- net.minecraft.WorldVersion$Simple
+ XXX.advancements.critereon.AnyBlockInteractionTrigger
- XXX.advancements.critereon.AnyBlockInteractionTrigger$TriggerInstance
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
+ XXX.advancements.critereon.CollectionContentsPredicate
- XXX.advancements.critereon.CollectionContentsPredicate$Multiple
+ XXX.advancements.critereon.CollectionContentsPredicate$Single
- XXX.advancements.critereon.CollectionContentsPredicate$Zero
+ XXX.advancements.critereon.CollectionCountsPredicate
- XXX.advancements.critereon.CollectionCountsPredicate$Entry
+ XXX.advancements.critereon.CollectionCountsPredicate$Multiple
- XXX.advancements.critereon.CollectionCountsPredicate$Single
+ XXX.advancements.critereon.CollectionCountsPredicate$Zero
- XXX.advancements.critereon.CollectionPredicate
+ XXX.advancements.critereon.ConstructBeaconTrigger
- XXX.advancements.critereon.ConstructBeaconTrigger$TriggerInstance
+ XXX.advancements.critereon.ConsumeItemTrigger
- XXX.advancements.critereon.ConsumeItemTrigger$TriggerInstance
+ XXX.advancements.critereon.ContextAwarePredicate
- XXX.advancements.critereon.CriterionValidator
+ XXX.advancements.critereon.CuredZombieVillagerTrigger
- XXX.advancements.critereon.CuredZombieVillagerTrigger$TriggerInstance
+ XXX.advancements.critereon.DamagePredicate
- XXX.advancements.critereon.DamagePredicate$Builder
+ XXX.advancements.critereon.DamageSourcePredicate
- XXX.advancements.critereon.DamageSourcePredicate$Builder
+ XXX.advancements.critereon.DataComponentMatchers
- XXX.advancements.critereon.DataComponentMatchers$Builder
+ XXX.advancements.critereon.DefaultBlockInteractionTrigger
- XXX.advancements.critereon.DefaultBlockInteractionTrigger$TriggerInstance
+ XXX.advancements.critereon.DistancePredicate
- XXX.advancements.critereon.DistanceTrigger
+ XXX.advancements.critereon.DistanceTrigger$TriggerInstance
- XXX.advancements.critereon.EffectsChangedTrigger
+ XXX.advancements.critereon.EffectsChangedTrigger$TriggerInstance
- XXX.advancements.critereon.EnchantedItemTrigger
+ XXX.advancements.critereon.EnchantedItemTrigger$TriggerInstance
- XXX.advancements.critereon.EnchantmentPredicate
+ XXX.advancements.critereon.EnterBlockTrigger
- XXX.advancements.critereon.EnterBlockTrigger$TriggerInstance
+ XXX.advancements.critereon.EntityEquipmentPredicate
- XXX.advancements.critereon.EntityEquipmentPredicate$Builder
+ XXX.advancements.critereon.EntityFlagsPredicate
- XXX.advancements.critereon.EntityFlagsPredicate$Builder
+ XXX.advancements.critereon.EntityHurtPlayerTrigger
- XXX.advancements.critereon.EntityHurtPlayerTrigger$TriggerInstance
+ XXX.advancements.critereon.EntityPredicate
- XXX.advancements.critereon.EntityPredicate$Builder
+ XXX.advancements.critereon.EntityPredicate$LocationWrapper
- XXX.advancements.critereon.EntitySubPredicate
+ XXX.advancements.critereon.EntitySubPredicates
- XXX.advancements.critereon.EntityTypePredicate
+ XXX.advancements.critereon.FallAfterExplosionTrigger
- XXX.advancements.critereon.FallAfterExplosionTrigger$TriggerInstance
+ XXX.advancements.critereon.FilledBucketTrigger
- XXX.advancements.critereon.FilledBucketTrigger$TriggerInstance
+ XXX.advancements.critereon.FishingHookPredicate
- XXX.advancements.critereon.FishingRodHookedTrigger
+ XXX.advancements.critereon.FishingRodHookedTrigger$TriggerInstance
- XXX.advancements.critereon.FluidPredicate
+ XXX.advancements.critereon.FluidPredicate$Builder
- XXX.advancements.critereon.GameTypePredicate
+ XXX.advancements.critereon.ImpossibleTrigger
- XXX.advancements.critereon.ImpossibleTrigger$TriggerInstance
+ XXX.advancements.critereon.InputPredicate
- XXX.advancements.critereon.InventoryChangeTrigger
+ XXX.advancements.critereon.InventoryChangeTrigger$TriggerInstance
- XXX.advancements.critereon.InventoryChangeTrigger$TriggerInstance$Slots
+ XXX.advancements.critereon.ItemDurabilityTrigger
- XXX.advancements.critereon.ItemDurabilityTrigger$TriggerInstance
+ XXX.advancements.critereon.ItemPredicate
- XXX.advancements.critereon.ItemPredicate$Builder
+ XXX.advancements.critereon.ItemUsedOnLocationTrigger
- XXX.advancements.critereon.ItemUsedOnLocationTrigger$TriggerInstance
+ XXX.advancements.critereon.KilledByArrowTrigger
- XXX.advancements.critereon.KilledByArrowTrigger$TriggerInstance
+ XXX.advancements.critereon.KilledTrigger
- XXX.advancements.critereon.KilledTrigger$TriggerInstance
+ XXX.advancements.critereon.LevitationTrigger
- XXX.advancements.critereon.LevitationTrigger$TriggerInstance
+ XXX.advancements.critereon.LightningBoltPredicate
- XXX.advancements.critereon.LightningStrikeTrigger
+ XXX.advancements.critereon.LightningStrikeTrigger$TriggerInstance
+ XXX.advancements.critereon.LightPredicate
- XXX.advancements.critereon.LightPredicate$Builder
- XXX.advancements.critereon.LocationPredicate
+ XXX.advancements.critereon.LocationPredicate$Builder
- XXX.advancements.critereon.LocationPredicate$PositionPredicate
+ XXX.advancements.critereon.LootTableTrigger
- XXX.advancements.critereon.LootTableTrigger$TriggerInstance
+ XXX.advancements.critereon.MinMaxBounds
- XXX.advancements.critereon.MinMaxBounds$Bounds
+ XXX.advancements.critereon.MinMaxBounds$BoundsFactory
- XXX.advancements.critereon.MinMaxBounds$Ints
+ XXX.advancements.critereon.MobEffectsPredicate
- XXX.advancements.critereon.MobEffectsPredicate$Builder
+ XXX.advancements.critereon.MobEffectsPredicate$MobEffectInstancePredicate
- XXX.advancements.critereon.MovementPredicate
+ XXX.advancements.critereon.NbtPredicate
- XXX.advancements.critereon.PickedUpItemTrigger
+ XXX.advancements.critereon.PickedUpItemTrigger$TriggerInstance
- XXX.advancements.critereon.PlayerHurtEntityTrigger
+ XXX.advancements.critereon.PlayerHurtEntityTrigger$TriggerInstance
- XXX.advancements.critereon.PlayerInteractTrigger
+ XXX.advancements.critereon.PlayerInteractTrigger$TriggerInstance
- XXX.advancements.critereon.PlayerPredicate
+ XXX.advancements.critereon.PlayerPredicate$AdvancementCriterionsPredicate
- XXX.advancements.critereon.PlayerPredicate$AdvancementDonePredicate
+ XXX.advancements.critereon.PlayerPredicate$AdvancementPredicate
- XXX.advancements.critereon.PlayerPredicate$Builder
+ XXX.advancements.critereon.PlayerPredicate$StatMatcher
- XXX.advancements.critereon.PlayerTrigger
+ XXX.advancements.critereon.PlayerTrigger$TriggerInstance
- XXX.advancements.critereon.RaiderPredicate
+ XXX.advancements.critereon.RecipeCraftedTrigger
- XXX.advancements.critereon.RecipeCraftedTrigger$TriggerInstance
+ XXX.advancements.critereon.RecipeUnlockedTrigger
- XXX.advancements.critereon.RecipeUnlockedTrigger$TriggerInstance
+ XXX.advancements.critereon.SheepPredicate
- XXX.advancements.critereon.ShotCrossbowTrigger
+ XXX.advancements.critereon.ShotCrossbowTrigger$TriggerInstance
- XXX.advancements.critereon.SimpleCriterionTrigger
+ XXX.advancements.critereon.SimpleCriterionTrigger$SimpleInstance
- XXX.advancements.critereon.SingleComponentItemPredicate
+ XXX.advancements.critereon.SlideDownBlockTrigger
- XXX.advancements.critereon.SlideDownBlockTrigger$TriggerInstance
+ XXX.advancements.critereon.SlimePredicate
- XXX.advancements.critereon.SlotsPredicate
+ XXX.advancements.critereon.StartRidingTrigger
- XXX.advancements.critereon.StartRidingTrigger$TriggerInstance
+ XXX.advancements.critereon.StatePropertiesPredicate
- XXX.advancements.critereon.StatePropertiesPredicate$Builder
+ XXX.advancements.critereon.StatePropertiesPredicate$ExactMatcher
- XXX.advancements.critereon.StatePropertiesPredicate$PropertyMatcher
+ XXX.advancements.critereon.StatePropertiesPredicate$RangedMatcher
- XXX.advancements.critereon.StatePropertiesPredicate$ValueMatcher
+ XXX.advancements.critereon.SummonedEntityTrigger
- XXX.advancements.critereon.SummonedEntityTrigger$TriggerInstance
+ XXX.advancements.critereon.TagPredicate
- XXX.advancements.critereon.TameAnimalTrigger
+ XXX.advancements.critereon.TameAnimalTrigger$TriggerInstance
- XXX.advancements.critereon.TargetBlockTrigger
+ XXX.advancements.critereon.TargetBlockTrigger$TriggerInstance
- XXX.advancements.critereon.TradeTrigger
+ XXX.advancements.critereon.TradeTrigger$TriggerInstance
- XXX.advancements.critereon.UsedEnderEyeTrigger
+ XXX.advancements.critereon.UsedEnderEyeTrigger$TriggerInstance
- XXX.advancements.critereon.UsedTotemTrigger
+ XXX.advancements.critereon.UsedTotemTrigger$TriggerInstance
- XXX.advancements.critereon.UsingItemTrigger
+ XXX.advancements.critereon.UsingItemTrigger$TriggerInstance
+ XXX.advancements.packs.package-info
+ XXX.advancements.packs.VanillaAdvancementProvider
- XXX.advancements.packs.VanillaAdventureAdvancements
+ XXX.advancements.packs.VanillaHusbandryAdvancements
- XXX.advancements.packs.VanillaNetherAdvancements
+ XXX.advancements.packs.VanillaStoryAdvancements
- XXX.advancements.packs.VanillaTheEndAdvancements
- XXX.animation.definitions.ArmadilloAnimation
+ XXX.animation.definitions.BatAnimation
- XXX.animation.definitions.BreezeAnimation
+ XXX.animation.definitions.CamelAnimation
- XXX.animation.definitions.CopperGolemAnimation
+ XXX.animation.definitions.CreakingAnimation
- XXX.animation.definitions.FrogAnimation
+ XXX.animation.definitions.package-info
+ XXX.animation.definitions.SnifferAnimation
- XXX.animation.definitions.WardenAnimation
+ XXX.arguments.blocks.BlockInput
- XXX.arguments.blocks.BlockPredicateArgument
+ XXX.arguments.blocks.BlockPredicateArgument$BlockPredicate
- XXX.arguments.blocks.BlockPredicateArgument$Result
+ XXX.arguments.blocks.BlockPredicateArgument$TagPredicate
- XXX.arguments.blocks.BlockStateArgument
+ XXX.arguments.blocks.BlockStateParser
- XXX.arguments.blocks.BlockStateParser$BlockResult
+ XXX.arguments.blocks.BlockStateParser$TagResult
- XXX.arguments.blocks.package-info
+ XXX.arguments.coordinates.BlockPosArgument
- XXX.arguments.coordinates.ColumnPosArgument
+ XXX.arguments.coordinates.Coordinates
- XXX.arguments.coordinates.LocalCoordinates
+ XXX.arguments.coordinates.package-info
+ XXX.arguments.coordinates.RotationArgument
- XXX.arguments.coordinates.SwizzleArgument
+ XXX.arguments.coordinates.Vec2Argument
- XXX.arguments.coordinates.Vec3Argument
+ XXX.arguments.coordinates.WorldCoordinate
- XXX.arguments.coordinates.WorldCoordinates
- XXX.arguments.item.ComponentPredicateParser
+ XXX.arguments.item.ComponentPredicateParser$ComponentLookupRule
- XXX.arguments.item.ComponentPredicateParser$Context
+ XXX.arguments.item.ComponentPredicateParser$ElementLookupRule
- XXX.arguments.item.ComponentPredicateParser$PredicateLookupRule
+ XXX.arguments.item.ComponentPredicateParser$TagLookupRule
- XXX.arguments.item.FunctionArgument
+ XXX.arguments.item.FunctionArgument$1
- XXX.arguments.item.FunctionArgument$2
+ XXX.arguments.item.FunctionArgument$Result
- XXX.arguments.item.ItemArgument
+ XXX.arguments.item.ItemInput
- XXX.arguments.item.ItemParser
+ XXX.arguments.item.ItemParser$1
- XXX.arguments.item.ItemParser$ItemResult
+ XXX.arguments.item.ItemParser$State
- XXX.arguments.item.ItemParser$SuggestionsVisitor
+ XXX.arguments.item.ItemParser$Visitor
- XXX.arguments.item.ItemPredicateArgument
+ XXX.arguments.item.ItemPredicateArgument$ComponentWrapper
- XXX.arguments.item.ItemPredicateArgument$Context
+ XXX.arguments.item.ItemPredicateArgument$PredicateWrapper
- XXX.arguments.item.ItemPredicateArgument$Result
+ XXX.arguments.item.package-info
+ XXX.arguments.selector.EntitySelector
- XXX.arguments.selector.EntitySelector$1
+ XXX.arguments.selector.EntitySelectorParser
+ XXX.arguments.selector.package-info
- XXX.arguments.selector.SelectorPattern
- XXX.blaze3d.vertex.CompactVectorArray
+ XXX.blaze3d.vertex.DefaultVertexFormat
- XXX.blaze3d.vertex.MeshData
+ XXX.blaze3d.vertex.MeshData$1
- XXX.blaze3d.vertex.MeshData$DrawState
+ XXX.blaze3d.vertex.MeshData$SortState
+ XXX.blaze3d.vertex.package-info
- XXX.blaze3d.vertex.PoseStack
+ XXX.blaze3d.vertex.PoseStack$Pose
- XXX.blaze3d.vertex.SheetedDecalTextureGenerator
+ XXX.blaze3d.vertex.Tesselator
- XXX.blaze3d.vertex.VertexConsumer
+ XXX.blaze3d.vertex.VertexFormat
- XXX.blaze3d.vertex.VertexFormat$Builder
+ XXX.blaze3d.vertex.VertexFormat$IndexType
- XXX.blaze3d.vertex.VertexFormat$Mode
+ XXX.blaze3d.vertex.VertexFormatElement
- XXX.blaze3d.vertex.VertexFormatElement$Type
+ XXX.blaze3d.vertex.VertexFormatElement$Usage
- XXX.blaze3d.vertex.VertexMultiConsumer
+ XXX.blaze3d.vertex.VertexMultiConsumer$Double
- XXX.blaze3d.vertex.VertexMultiConsumer$Multiple
+ XXX.blaze3d.vertex.VertexSorting
- XXX.blaze3d.vertex.VertexSorting$DistanceFunction
+ XXX.block.model.BakedQuad
- XXX.block.model.BlockElement
+ XXX.block.model.BlockElement$Deserializer
- XXX.block.model.BlockElementFace
+ XXX.block.model.BlockElementFace$Deserializer
- XXX.block.model.BlockElementFace$UVs
+ XXX.block.model.BlockElementRotation
- XXX.block.model.BlockModel
+ XXX.block.model.BlockModel$Deserializer
- XXX.block.model.BlockModelDefinition
+ XXX.block.model.BlockModelDefinition$MultiPartDefinition
- XXX.block.model.BlockModelDefinition$SimpleModelSelectors
+ XXX.block.model.BlockModelPart
- XXX.block.model.BlockModelPart$Unbaked
+ XXX.block.model.BlockStateModel
- XXX.block.model.BlockStateModel$SimpleCachedUnbakedRoot
+ XXX.block.model.BlockStateModel$SimpleCachedUnbakedRoot$1
- XXX.block.model.BlockStateModel$Unbaked
+ XXX.block.model.BlockStateModel$UnbakedRoot
- XXX.block.model.FaceBakery
+ XXX.block.model.FaceBakery$1
- XXX.block.model.ItemModelGenerator
+ XXX.block.model.ItemModelGenerator$Span
- XXX.block.model.ItemModelGenerator$SpanFacing
+ XXX.block.model.ItemTransform
- XXX.block.model.ItemTransform$Deserializer
+ XXX.block.model.ItemTransforms
- XXX.block.model.ItemTransforms$1
+ XXX.block.model.ItemTransforms$Deserializer
- XXX.block.model.package-info
- XXX.block.model.SimpleModelWrapper
+ XXX.block.model.SimpleUnbakedGeometry
- XXX.block.model.SingleVariant
+ XXX.block.model.SingleVariant$Unbaked
- XXX.block.model.TextureSlots
+ XXX.block.model.TextureSlots$Data
- XXX.block.model.TextureSlots$Data$Builder
+ XXX.block.model.TextureSlots$Reference
- XXX.block.model.TextureSlots$Resolver
+ XXX.block.model.TextureSlots$SlotContents
- XXX.block.model.TextureSlots$Value
+ XXX.block.model.Variant
- XXX.block.model.Variant$SimpleModelState
+ XXX.block.model.VariantMutator
- XXX.block.model.VariantMutator$VariantProperty
+ XXX.block.model.VariantSelector
- XXX.blockentity.state.BeaconRenderState
- XXX.blockentity.state.BedRenderState
- XXX.blockentity.state.BlockEntityRenderState
- XXX.blockentity.state.BlockEntityWithBoundingBoxRenderState$InvisibleBlockType
- XXX.blockentity.state.CampfireRenderState
- XXX.blockentity.state.ChestRenderState$ChestMaterialType
- XXX.blockentity.state.CopperGolemStatueRenderState
- XXX.blockentity.state.EnchantTableRenderState
- XXX.blockentity.state.EndPortalRenderState
- XXX.blockentity.state.package-info
- XXX.blockentity.state.PistonHeadRenderState
- XXX.blockentity.state.ShulkerBoxRenderState
- XXX.blockentity.state.SkullBlockRenderState
- XXX.blockentity.state.TestInstanceRenderState
- XXX.chat.contents.KeybindContents
+ XXX.chat.contents.KeybindResolver
- XXX.chat.contents.NbtContents
+ XXX.chat.contents.ObjectContents
- XXX.chat.contents.package-info
- XXX.chat.contents.PlainTextContents
+ XXX.chat.contents.PlainTextContents$1
- XXX.chat.contents.PlainTextContents$LiteralContents
+ XXX.chat.contents.ScoreContents
- XXX.chat.contents.SelectorContents
+ XXX.chat.contents.TranslatableContents
- XXX.chat.contents.TranslatableFormatException
+ XXX.chat.numbers.BlankFormat
- XXX.chat.numbers.BlankFormat$1
+ XXX.chat.numbers.FixedFormat
- XXX.chat.numbers.FixedFormat$1
+ XXX.chat.numbers.NumberFormat
- XXX.chat.numbers.NumberFormatType
+ XXX.chat.numbers.NumberFormatTypes
- XXX.chat.numbers.package-info
- XXX.chat.numbers.StyledFormat
+ XXX.chat.numbers.StyledFormat$1
+ XXX.client.animation.AnimationChannel
- XXX.client.animation.AnimationChannel$Interpolation
+ XXX.client.animation.AnimationChannel$Interpolations
- XXX.client.animation.AnimationChannel$Target
+ XXX.client.animation.AnimationChannel$Targets
- XXX.client.animation.AnimationDefinition
+ XXX.client.animation.AnimationDefinition$Builder
- XXX.client.animation.Keyframe
+ XXX.client.animation.KeyframeAnimation
- XXX.client.animation.KeyframeAnimation$Entry
+ XXX.client.animation.KeyframeAnimations
- XXX.client.animation.package-info
+ XXX.client.color.ColorLerper
- XXX.client.color.ColorLerper$Type
- XXX.client.color.package-info
+ XXX.client.data.AtlasProvider
- XXX.client.data.Main
+ XXX.client.data.package-info
- XXX.client.entity.ClientAvatarEntity
- XXX.client.entity.ClientMannequin
- XXX.client.gui.BundleMouseActions
+ XXX.client.gui.ComponentPath
- XXX.client.gui.ComponentPath$Leaf
+ XXX.client.gui.ComponentPath$Path
- XXX.client.gui.Font
+ XXX.client.gui.Font$DisplayMode
- XXX.client.gui.Font$GlyphVisitor
+ XXX.client.gui.Font$GlyphVisitor$1
- XXX.client.gui.Font$PreparedText
+ XXX.client.gui.Font$PreparedTextBuilder
- XXX.client.gui.Font$Provider
+ XXX.client.gui.GlyphSource
- XXX.client.gui.Gui
+ XXX.client.gui.Gui$1DisplayEntry
- XXX.client.gui.Gui$ContextualInfo
+ XXX.client.gui.Gui$HeartType
- XXX.client.gui.Gui$RenderFunction
+ XXX.client.gui.GuiGraphics
- XXX.client.gui.GuiGraphics$OutlineBox
+ XXX.client.gui.GuiGraphics$ScissorStack
- XXX.client.gui.ItemSlotMouseAction
- XXX.client.input.CharacterEvent
- XXX.client.input.InputWithModifiers
- XXX.client.input.MouseButtonEvent
- XXX.client.input.package-info
+ XXX.client.main.GameConfig
- XXX.client.main.GameConfig$FolderData
+ XXX.client.main.GameConfig$GameData
- XXX.client.main.GameConfig$QuickPlayData
+ XXX.client.main.GameConfig$QuickPlayDisabled
- XXX.client.main.GameConfig$QuickPlayMultiplayerData
+ XXX.client.main.GameConfig$QuickPlayRealmsData
- XXX.client.main.GameConfig$QuickPlaySinglePlayerData
+ XXX.client.main.GameConfig$QuickPlayVariant
- XXX.client.main.GameConfig$UserData
+ XXX.client.main.Main
- XXX.client.main.Main$1
+ XXX.client.main.Main$2
+ XXX.client.main.package-info
- XXX.client.main.SilentInitException
- XXX.client.model.AbstractBoatModel
+ XXX.client.model.AbstractEquineModel
- XXX.client.model.AbstractPiglinModel
+ XXX.client.model.AbstractZombieModel
- XXX.client.model.AdultAndBabyModelPair
+ XXX.client.model.AllayModel
- XXX.client.model.AnimationUtils
+ XXX.client.model.ArmadilloModel
- XXX.client.model.ArmedModel
+ XXX.client.model.ArmorStandArmorModel
- XXX.client.model.ArmorStandModel
+ XXX.client.model.ArrowModel
- XXX.client.model.AxolotlModel
+ XXX.client.model.BabyModelTransform
- XXX.client.model.BannerFlagModel
+ XXX.client.model.BannerModel
- XXX.client.model.BatModel
+ XXX.client.model.BeeModel
- XXX.client.model.BeeStingerModel
+ XXX.client.model.BellModel
- XXX.client.model.BellModel$1
+ XXX.client.model.BellModel$State
- XXX.client.model.BlazeModel
+ XXX.client.model.BoatModel
- XXX.client.model.BoggedModel
+ XXX.client.model.BookModel
- XXX.client.model.BookModel$State
+ XXX.client.model.BreezeModel
- XXX.client.model.CamelModel
+ XXX.client.model.CamelSaddleModel
- XXX.client.model.CatModel
+ XXX.client.model.ChestModel
- XXX.client.model.ChickenModel
+ XXX.client.model.CodModel
- XXX.client.model.ColdChickenModel
+ XXX.client.model.ColdCowModel
- XXX.client.model.ColdPigModel
+ XXX.client.model.CopperGolemModel
- XXX.client.model.CopperGolemStatueModel
+ XXX.client.model.CowModel
- XXX.client.model.CreakingModel
+ XXX.client.model.CreeperModel
- XXX.client.model.DolphinModel
+ XXX.client.model.DonkeyModel
- XXX.client.model.DrownedModel
+ XXX.client.model.ElytraModel
- XXX.client.model.EndCrystalModel
+ XXX.client.model.EndermanModel
- XXX.client.model.EndermiteModel
+ XXX.client.model.EntityModel
- XXX.client.model.EquineSaddleModel
+ XXX.client.model.EvokerFangsModel
- XXX.client.model.FelineModel
+ XXX.client.model.FoxModel
- XXX.client.model.FrogModel
+ XXX.client.model.GhastModel
- XXX.client.model.GiantZombieModel
+ XXX.client.model.GoatModel
- XXX.client.model.GuardianModel
- XXX.client.particle.DripParticle$DripstoneLavaHangProvider
- XXX.client.particle.DripParticle$DripstoneWaterHangProvider
- XXX.client.particle.DripParticle$HoneyFallProvider
- XXX.client.particle.DripParticle$HoneyLandProvider
- XXX.client.particle.DripParticle$LavaHangProvider
- XXX.client.particle.DripParticle$NectarFallProvider
- XXX.client.particle.DripParticle$ObsidianTearHangProvider
- XXX.client.particle.DripParticle$SporeBlossomFallProvider
- XXX.client.particle.DripParticle$WaterHangProvider
+ XXX.client.particle.DustColorTransitionParticle
- XXX.client.particle.DustColorTransitionParticle$Provider
+ XXX.client.particle.DustParticle
- XXX.client.particle.DustParticle$Provider
+ XXX.client.particle.DustParticleBase
- XXX.client.particle.DustPlumeParticle
+ XXX.client.particle.DustPlumeParticle$Provider
- XXX.client.particle.ElderGuardianParticle
- XXX.client.particle.ElderGuardianParticleGroup
- XXX.client.particle.ElderGuardianParticleGroup$State
- XXX.client.particle.ItemPickupParticleGroup
- XXX.client.particle.ItemPickupParticleGroup$State
+ XXX.client.particle.LargeSmokeParticle
- XXX.client.particle.LargeSmokeParticle$Provider
+ XXX.client.particle.LavaParticle
- XXX.client.particle.LavaParticle$Provider
+ XXX.client.particle.MobAppearanceParticle
+ XXX.client.particle.NoRenderParticle
- XXX.client.particle.NoRenderParticleGroup
+ XXX.client.particle.package-info
+ XXX.client.particle.ParticleEngine$MutableSpriteSet
- XXX.client.particle.ParticleResources$1ParticleDefinition
- XXX.client.particle.ParticleResources$SpriteParticleRegistration
- XXX.client.particle.QuadParticleGroup
+ XXX.client.particle.ReversePortalParticle
- XXX.client.particle.ReversePortalParticle$ReversePortalProvider
+ XXX.client.particle.RisingParticle
- XXX.client.particle.SculkChargeParticle
+ XXX.client.particle.SculkChargeParticle$Provider
- XXX.client.particle.SculkChargePopParticle
+ XXX.client.particle.SculkChargePopParticle$Provider
- XXX.client.particle.ShriekParticle
+ XXX.client.particle.ShriekParticle$Provider
- XXX.client.particle.SimpleAnimatedParticle
+ XXX.client.particle.SingleQuadParticle
- XXX.client.particle.SingleQuadParticle$FacingCameraMode
+ XXX.client.particle.TextureSheetParticle
- XXX.client.particle.TotemParticle
+ XXX.client.particle.TotemParticle$Provider
- XXX.client.particle.TrackingEmitter
+ XXX.client.particle.TrailParticle
- XXX.client.particle.TrailParticle$Provider
+ XXX.client.particle.TrialSpawnerDetectionParticle
- XXX.client.particle.TrialSpawnerDetectionParticle$Provider
+ XXX.client.particle.VibrationSignalParticle
- XXX.client.particle.VibrationSignalParticle$Provider
+ XXX.client.particle.WakeParticle
- XXX.client.particle.WakeParticle$Provider
+ XXX.client.particle.WaterCurrentDownParticle
- XXX.client.particle.WaterCurrentDownParticle$Provider
+ XXX.client.particle.WaterDropParticle
- XXX.client.particle.WaterDropParticle$Provider
+ XXX.client.particle.WhiteAshParticle
- XXX.client.particle.WhiteAshParticle$Provider
+ XXX.client.particle.WhiteSmokeParticle
- XXX.client.particle.WhiteSmokeParticle$Provider
- XXX.client.player.AbstractClientPlayer
+ XXX.client.player.ClientInput
- XXX.client.player.KeyboardInput
+ XXX.client.player.LocalPlayer
- XXX.client.player.LocalPlayerResolver
- XXX.client.player.package-info
+ XXX.client.player.RemotePlayer
+ XXX.client.profiling.ClientMetricsSamplersProvider
- XXX.client.profiling.package-info
+ XXX.client.quickplay.package-info
+ XXX.client.quickplay.QuickPlay
- XXX.client.quickplay.QuickPlayLog
+ XXX.client.quickplay.QuickPlayLog$1
- XXX.client.quickplay.QuickPlayLog$QuickPlayEntry
+ XXX.client.quickplay.QuickPlayLog$QuickPlayWorld
- XXX.client.quickplay.QuickPlayLog$Type
- XXX.client.renderer.BiomeColors
+ XXX.client.renderer.CachedOrthoProjectionMatrixBuffer
- XXX.client.renderer.CachedPerspectiveProjectionMatrixBuffer
+ XXX.client.renderer.CloudRenderer
- XXX.client.renderer.CloudRenderer$RelativeCameraPos
+ XXX.client.renderer.CloudRenderer$TextureData
- XXX.client.renderer.CubeMap
+ XXX.client.renderer.DimensionSpecialEffects
- XXX.client.renderer.DimensionSpecialEffects$EndEffects
+ XXX.client.renderer.DimensionSpecialEffects$NetherEffects
- XXX.client.renderer.DimensionSpecialEffects$OverworldEffects
+ XXX.client.renderer.DimensionSpecialEffects$SkyType
- XXX.client.renderer.DynamicUniforms
+ XXX.client.renderer.DynamicUniforms$Transform
- XXX.client.renderer.DynamicUniformStorage
+ XXX.client.renderer.DynamicUniformStorage$DynamicUniform
- XXX.client.renderer.EndFlashState
+ XXX.client.renderer.FaceInfo
- XXX.client.renderer.FaceInfo$Constants
+ XXX.client.renderer.FaceInfo$VertexInfo
- XXX.client.renderer.GameRenderer
+ XXX.client.renderer.GlobalSettingsUniform
- XXX.client.renderer.GpuWarnlistManager
+ XXX.client.renderer.GpuWarnlistManager$Preparations
- XXX.client.renderer.ItemBlockRenderTypes
+ XXX.client.renderer.ItemBlockRenderTypes$2
- XXX.client.renderer.ItemInHandRenderer
+ XXX.client.renderer.ItemInHandRenderer$1
- XXX.client.renderer.ItemInHandRenderer$HandRenderSelection
+ XXX.client.renderer.LevelEventHandler
+ XXX.client.renderer.LevelRenderer
- XXX.client.renderer.LevelRenderer$1
+ XXX.client.renderer.LevelRenderer$BrightnessGetter
- XXX.client.renderer.LevelRenderState
- XXX.client.renderer.LevelTargetBundle
+ XXX.client.renderer.LightTexture
+ XXX.client.renderer.MappableRingBuffer
- XXX.client.renderer.MapRenderer
- XXX.client.renderer.MaterialMapper
+ XXX.client.renderer.MultiBufferSource
- XXX.client.renderer.MultiBufferSource$BufferSource
+ XXX.client.renderer.Octree
- XXX.client.renderer.Octree$AxisSorting
+ XXX.client.renderer.Octree$Branch
- XXX.client.renderer.Octree$Leaf
+ XXX.client.renderer.Octree$Node
- XXX.client.renderer.Octree$OctreeVisitor
+ XXX.client.renderer.OrderedSubmitNodeCollector
- XXX.client.renderer.OutlineBufferSource
+ XXX.client.renderer.OutlineBufferSource$EntityOutlineGenerator
- XXX.client.renderer.PanoramaRenderer
- XXX.client.renderer.ParticlesRenderState
+ XXX.client.renderer.PerspectiveProjectionMatrixBuffer
- XXX.client.renderer.PlayerSkinRenderCache
+ XXX.client.renderer.PlayerSkinRenderCache$1
- XXX.client.renderer.PlayerSkinRenderCache$2
+ XXX.client.renderer.PlayerSkinRenderCache$RenderInfo
- XXX.client.renderer.PostChain
+ XXX.client.renderer.PostChain$TargetBundle
- XXX.client.renderer.PostChain$TargetBundle$1
+ XXX.client.renderer.PostChainConfig
- XXX.client.renderer.PostChainConfig$Input
+ XXX.client.renderer.PostChainConfig$InternalTarget
- XXX.client.renderer.PostChainConfig$Pass
+ XXX.client.renderer.PostChainConfig$TargetInput
- XXX.client.renderer.PostChainConfig$TextureInput
+ XXX.client.renderer.PostPass
- XXX.client.renderer.PostPass$Input
+ XXX.client.renderer.PostPass$TargetInput
- XXX.client.renderer.PostPass$TextureInput
- XXX.client.renderer.QuadParticleRenderState$ParticleConsumer
- XXX.client.renderer.SubmitNodeCollector$ParticleGroupRenderer
+ XXX.client.renderer.SubmitNodeStorage
- XXX.client.renderer.SubmitNodeStorage$BlockModelSubmit
+ XXX.client.renderer.SubmitNodeStorage$BlockSubmit
- XXX.client.renderer.SubmitNodeStorage$CustomGeometrySubmit
+ XXX.client.renderer.SubmitNodeStorage$FlameSubmit
- XXX.client.renderer.SubmitNodeStorage$HitboxSubmit
+ XXX.client.renderer.SubmitNodeStorage$ItemSubmit
- XXX.client.renderer.SubmitNodeStorage$LeashSubmit
+ XXX.client.renderer.SubmitNodeStorage$ModelPartSubmit
- XXX.client.renderer.SubmitNodeStorage$ModelSubmit
+ XXX.client.renderer.SubmitNodeStorage$MovingBlockSubmit
- XXX.client.renderer.SubmitNodeStorage$NameTagSubmit
+ XXX.client.renderer.SubmitNodeStorage$ShadowSubmit
- XXX.client.renderer.SubmitNodeStorage$TextSubmit
+ XXX.client.renderer.SubmitNodeStorage$TranslucentModelSubmit
- XXX.client.renderer.UniformValue
+ XXX.client.renderer.UniformValue$FloatUniform
+ XXX.client.renderer.UniformValue$IntUniform
- XXX.client.renderer.UniformValue$IVec3Uniform
- XXX.client.renderer.UniformValue$Matrix4x4Uniform
+ XXX.client.renderer.UniformValue$Type
- XXX.client.renderer.UniformValue$Vec2Uniform
+ XXX.client.renderer.UniformValue$Vec3Uniform
- XXX.client.renderer.UniformValue$Vec4Uniform
+ XXX.client.renderer.ViewArea
- XXX.client.renderer.VirtualScreen
+ XXX.client.renderer.WeatherEffectRenderer
- XXX.client.renderer.WeatherEffectRenderer$ColumnInstance
+ XXX.client.renderer.WorldBorderRenderer
+ XXX.client.resources.package-info
+ XXX.client.resources.SkinManager
- XXX.client.resources.SkinManager$1
+ XXX.client.resources.SkinManager$2
- XXX.client.resources.SkinManager$CacheKey
+ XXX.client.resources.SkinManager$TextureCache
- XXX.client.resources.SplashManager
+ XXX.client.resources.WaypointStyle
- XXX.client.resources.WaypointStyleManager
- XXX.client.searchtree.FullTextSearchTree
+ XXX.client.searchtree.IdSearchTree
- XXX.client.searchtree.IntersectionIterator
+ XXX.client.searchtree.MergingUniqueIterator
+ XXX.client.searchtree.package-info
- XXX.client.searchtree.ResourceLocationSearchTree
+ XXX.client.searchtree.ResourceLocationSearchTree$1
- XXX.client.searchtree.ResourceLocationSearchTree$2
+ XXX.client.searchtree.SearchTree
- XXX.client.searchtree.SuffixArray
- XXX.client.server.IntegratedPlayerList
+ XXX.client.server.IntegratedServer
- XXX.client.server.LanServer
+ XXX.client.server.LanServerDetection
- XXX.client.server.LanServerDetection$LanServerDetector
+ XXX.client.server.LanServerDetection$LanServerList
- XXX.client.server.LanServerPinger
+ XXX.client.server.package-info
- XXX.client.sounds.AudioStream
+ XXX.client.sounds.ChannelAccess
- XXX.client.sounds.ChannelAccess$ChannelHandle
+ XXX.client.sounds.ChunkedSampleByteBuf
- XXX.client.sounds.FiniteAudioStream
+ XXX.client.sounds.FloatSampleSource
- XXX.client.sounds.JOrbisAudioStream
+ XXX.client.sounds.LoopingAudioStream
- XXX.client.sounds.LoopingAudioStream$AudioStreamProvider
+ XXX.client.sounds.LoopingAudioStream$NoCloseBuffer
- XXX.client.sounds.MusicInfo
+ XXX.client.sounds.MusicManager
- XXX.client.sounds.MusicManager$1
+ XXX.client.sounds.MusicManager$MusicFrequency
+ XXX.client.sounds.package-info
- XXX.client.sounds.SoundBufferLibrary
+ XXX.client.sounds.SoundEngine
- XXX.client.sounds.SoundEngine$DeviceCheckState
+ XXX.client.sounds.SoundEngine$PlayResult
- XXX.client.sounds.SoundEngineExecutor
+ XXX.client.sounds.SoundEventListener
- XXX.client.sounds.SoundManager
+ XXX.client.sounds.SoundManager$1
- XXX.client.sounds.SoundManager$2
+ XXX.client.sounds.SoundManager$Preparations
- XXX.client.sounds.SoundManager$Preparations$1
+ XXX.client.sounds.WeighedSoundEvents
- XXX.client.sounds.Weighted
- XXX.client.telemetry.ClientTelemetryManager
+ XXX.client.telemetry.package-info
+ XXX.client.telemetry.TelemetryEventInstance
- XXX.client.telemetry.TelemetryEventLog
+ XXX.client.telemetry.TelemetryEventLogger
- XXX.client.telemetry.TelemetryEventSender
+ XXX.client.telemetry.TelemetryEventType
- XXX.client.telemetry.TelemetryEventType$Builder
+ XXX.client.telemetry.TelemetryLogManager
- XXX.client.telemetry.TelemetryProperty
+ XXX.client.telemetry.TelemetryProperty$Exporter
- XXX.client.telemetry.TelemetryProperty$GameMode
+ XXX.client.telemetry.TelemetryProperty$ServerType
- XXX.client.telemetry.TelemetryPropertyMap
+ XXX.client.telemetry.TelemetryPropertyMap$1
- XXX.client.telemetry.TelemetryPropertyMap$Builder
+ XXX.client.telemetry.WorldSessionTelemetryManager
- XXX.client.tutorial.CompletedTutorialStepInstance
+ XXX.client.tutorial.CraftPlanksTutorialStep
- XXX.client.tutorial.FindTreeTutorialStepInstance
+ XXX.client.tutorial.MovementTutorialStepInstance
- XXX.client.tutorial.OpenInventoryTutorialStep
+ XXX.client.tutorial.package-info
+ XXX.client.tutorial.PunchTreeTutorialStepInstance
- XXX.client.tutorial.Tutorial
+ XXX.client.tutorial.TutorialStepInstance
- XXX.client.tutorial.TutorialSteps
- XXX.client.waypoints.ClientWaypointManager
+ XXX.client.waypoints.package-info
- XXX.client.worldupload.package-info
- XXX.client.worldupload.RealmsCreateWorldFlow
+ XXX.client.worldupload.RealmsUploadCanceledException
- XXX.client.worldupload.RealmsUploadException
+ XXX.client.worldupload.RealmsUploadFailedException
- XXX.client.worldupload.RealmsUploadTooLargeException
+ XXX.client.worldupload.RealmsUploadWorldNotClosedException
- XXX.client.worldupload.RealmsUploadWorldPacker
+ XXX.client.worldupload.RealmsWorldUpload
- XXX.client.worldupload.RealmsWorldUploadStatusTracker
+ XXX.client.worldupload.RealmsWorldUploadStatusTracker$1
+ XXX.color.block.BlockColor
- XXX.color.block.BlockColors
+ XXX.color.block.BlockTintCache
- XXX.color.block.BlockTintCache$CacheData
+ XXX.color.block.BlockTintCache$LatestCacheInfo
- XXX.color.block.package-info
+ XXX.color.item.Constant
- XXX.color.item.CustomModelDataSource
+ XXX.color.item.Dye
- XXX.color.item.Firework
+ XXX.color.item.GrassColorSource
- XXX.color.item.ItemTintSource
+ XXX.color.item.ItemTintSources
- XXX.color.item.MapColor
+ XXX.color.item.package-info
+ XXX.color.item.Potion
- XXX.color.item.TeamColor
- XXX.commands.arguments.AngleArgument
+ XXX.commands.arguments.AngleArgument$SingleAngle
- XXX.commands.arguments.ArgumentSignatures
+ XXX.commands.arguments.ArgumentSignatures$Entry
- XXX.commands.arguments.ArgumentSignatures$Signer
+ XXX.commands.arguments.ColorArgument
- XXX.commands.arguments.ComponentArgument
+ XXX.commands.arguments.CompoundTagArgument
- XXX.commands.arguments.DimensionArgument
+ XXX.commands.arguments.EntityAnchorArgument
- XXX.commands.arguments.EntityAnchorArgument$Anchor
+ XXX.commands.arguments.EntityArgument
- XXX.commands.arguments.EntityArgument$Info
+ XXX.commands.arguments.EntityArgument$Info$Template
- XXX.commands.arguments.GameModeArgument
+ XXX.commands.arguments.GameProfileArgument
- XXX.commands.arguments.GameProfileArgument$Result
+ XXX.commands.arguments.GameProfileArgument$SelectorResult
- XXX.commands.arguments.HeightmapTypeArgument
+ XXX.commands.arguments.HexColorArgument
- XXX.commands.arguments.MessageArgument
+ XXX.commands.arguments.MessageArgument$Message
- XXX.commands.arguments.MessageArgument$Part
+ XXX.commands.arguments.NbtPathArgument
- XXX.commands.arguments.NbtPathArgument$AllElementsNode
+ XXX.commands.arguments.NbtPathArgument$CompoundChildNode
- XXX.commands.arguments.NbtPathArgument$IndexedElementNode
+ XXX.commands.arguments.NbtPathArgument$MatchElementNode
- XXX.commands.arguments.NbtPathArgument$MatchObjectNode
+ XXX.commands.arguments.NbtPathArgument$MatchRootObjectNode
- XXX.commands.arguments.NbtPathArgument$NbtPath
+ XXX.commands.arguments.NbtPathArgument$Node
- XXX.commands.arguments.NbtTagArgument
+ XXX.commands.arguments.ObjectiveArgument
- XXX.commands.arguments.ObjectiveCriteriaArgument
+ XXX.commands.arguments.OperationArgument
- XXX.commands.arguments.OperationArgument$Operation
+ XXX.commands.arguments.OperationArgument$SimpleOperation
- XXX.commands.arguments.package-info
- XXX.commands.arguments.ParticleArgument
+ XXX.commands.arguments.RangeArgument
- XXX.commands.arguments.RangeArgument$Floats
+ XXX.commands.arguments.RangeArgument$Ints
- XXX.commands.arguments.ResourceArgument
+ XXX.commands.arguments.ResourceArgument$Info
- XXX.commands.arguments.ResourceArgument$Info$Template
+ XXX.commands.arguments.ResourceKeyArgument
- XXX.commands.arguments.ResourceKeyArgument$Info
+ XXX.commands.arguments.ResourceKeyArgument$Info$Template
- XXX.commands.arguments.ResourceLocationArgument
+ XXX.commands.arguments.ResourceOrIdArgument
- XXX.commands.arguments.ResourceOrIdArgument$DialogArgument
+ XXX.commands.arguments.ResourceOrIdArgument$InlineResult
- XXX.commands.arguments.ResourceOrIdArgument$LootModifierArgument
+ XXX.commands.arguments.ResourceOrIdArgument$LootPredicateArgument
- XXX.commands.arguments.ResourceOrIdArgument$LootTableArgument
+ XXX.commands.arguments.ResourceOrIdArgument$ReferenceResult
- XXX.commands.arguments.ResourceOrIdArgument$Result
+ XXX.commands.arguments.ResourceOrTagArgument
- XXX.commands.arguments.ResourceOrTagArgument$Info
+ XXX.commands.arguments.ResourceOrTagArgument$Info$Template
- XXX.commands.arguments.ResourceOrTagArgument$ResourceResult
+ XXX.commands.arguments.ResourceOrTagArgument$Result
- XXX.commands.arguments.ResourceOrTagArgument$TagResult
+ XXX.commands.arguments.ResourceOrTagKeyArgument
- XXX.commands.arguments.ResourceOrTagKeyArgument$Info
+ XXX.commands.arguments.ResourceOrTagKeyArgument$Info$Template
- XXX.commands.arguments.ResourceOrTagKeyArgument$ResourceResult
+ XXX.commands.arguments.ResourceOrTagKeyArgument$Result
- XXX.commands.arguments.ResourceOrTagKeyArgument$TagResult
+ XXX.commands.arguments.ResourceSelectorArgument
- XXX.commands.arguments.ResourceSelectorArgument$Info
+ XXX.commands.arguments.ResourceSelectorArgument$Info$Template
+ XXX.commands.arguments.ScoreboardSlotArgument
- XXX.commands.arguments.ScoreHolderArgument
+ XXX.commands.arguments.ScoreHolderArgument$Info
- XXX.commands.arguments.ScoreHolderArgument$Info$Template
+ XXX.commands.arguments.ScoreHolderArgument$Result
- XXX.commands.arguments.ScoreHolderArgument$SelectorResult
- XXX.commands.arguments.SignedArgument
+ XXX.commands.arguments.SlotArgument
- XXX.commands.arguments.SlotsArgument
+ XXX.commands.arguments.StringRepresentableArgument
- XXX.commands.arguments.StyleArgument
+ XXX.commands.arguments.TeamArgument
- XXX.commands.arguments.TemplateMirrorArgument
+ XXX.commands.arguments.TemplateRotationArgument
- XXX.commands.arguments.TimeArgument
+ XXX.commands.arguments.TimeArgument$Info
- XXX.commands.arguments.TimeArgument$Info$Template
+ XXX.commands.arguments.UuidArgument
- XXX.commands.arguments.WaypointArgument
- XXX.commands.execution.ChainModifiers
+ XXX.commands.execution.CommandQueueEntry
- XXX.commands.execution.CustomCommandExecutor
+ XXX.commands.execution.CustomCommandExecutor$CommandAdapter
- XXX.commands.execution.CustomCommandExecutor$WithErrorHandling
+ XXX.commands.execution.CustomModifierExecutor
- XXX.commands.execution.CustomModifierExecutor$ModifierAdapter
+ XXX.commands.execution.EntryAction
- XXX.commands.execution.ExecutionContext
+ XXX.commands.execution.ExecutionControl
- XXX.commands.execution.ExecutionControl$1
+ XXX.commands.execution.Frame
- XXX.commands.execution.Frame$FrameControl
+ XXX.commands.execution.package-info
+ XXX.commands.execution.TraceCallbacks
- XXX.commands.execution.UnboundEntryAction
+ XXX.commands.functions.CommandFunction
- XXX.commands.functions.FunctionBuilder
+ XXX.commands.functions.InstantiatedFunction
- XXX.commands.functions.MacroFunction
+ XXX.commands.functions.MacroFunction$Entry
- XXX.commands.functions.MacroFunction$MacroEntry
+ XXX.commands.functions.MacroFunction$PlainTextEntry
- XXX.commands.functions.package-info
- XXX.commands.functions.PlainTextFunction
+ XXX.commands.functions.StringTemplate
- XXX.commands.synchronization.ArgumentTypeInfo
+ XXX.commands.synchronization.ArgumentTypeInfo$Template
- XXX.commands.synchronization.ArgumentTypeInfos
+ XXX.commands.synchronization.ArgumentUtils
- XXX.commands.synchronization.package-info
- XXX.commands.synchronization.SingletonArgumentInfo
+ XXX.commands.synchronization.SingletonArgumentInfo$Template
- XXX.commands.synchronization.SuggestionProviders
+ XXX.commands.synchronization.SuggestionProviders$RegisteredSuggestion
+ XXX.common.custom.BeeDebugPayload
- XXX.common.custom.BeeDebugPayload$BeeInfo
+ XXX.common.custom.BrainDebugPayload
- XXX.common.custom.BrainDebugPayload$BrainDump
+ XXX.common.custom.BrandPayload
- XXX.common.custom.BreezeDebugPayload
+ XXX.common.custom.BreezeDebugPayload$BreezeInfo
- XXX.common.custom.CustomPacketPayload
+ XXX.common.custom.CustomPacketPayload$1
- XXX.common.custom.CustomPacketPayload$FallbackProvider
+ XXX.common.custom.CustomPacketPayload$Type
- XXX.common.custom.CustomPacketPayload$TypeAndCodec
+ XXX.common.custom.DiscardedPayload
- XXX.common.custom.GameEventDebugPayload
+ XXX.common.custom.GameEventListenerDebugPayload
- XXX.common.custom.GameTestAddMarkerDebugPayload
+ XXX.common.custom.GameTestClearMarkersDebugPayload
- XXX.common.custom.GoalDebugPayload
+ XXX.common.custom.GoalDebugPayload$DebugGoal
- XXX.common.custom.HiveDebugPayload
+ XXX.common.custom.HiveDebugPayload$HiveInfo
- XXX.common.custom.NeighborUpdatesDebugPayload
- XXX.common.custom.package-info
+ XXX.common.custom.PathfindingDebugPayload
- XXX.common.custom.PoiAddedDebugPayload
+ XXX.common.custom.PoiRemovedDebugPayload
- XXX.common.custom.PoiTicketCountDebugPayload
+ XXX.common.custom.RaidsDebugPayload
- XXX.common.custom.RedstoneWireOrientationsDebugPayload
+ XXX.common.custom.RedstoneWireOrientationsDebugPayload$Wire
- XXX.common.custom.StructuresDebugPayload
+ XXX.common.custom.StructuresDebugPayload$PieceInfo
- XXX.common.custom.VillageSectionsDebugPayload
+ XXX.common.custom.WorldGenAttemptDebugPayload
- XXX.component.predicates.AttributeModifiersPredicate
+ XXX.component.predicates.AttributeModifiersPredicate$EntryPredicate
- XXX.component.predicates.BundlePredicate
+ XXX.component.predicates.ContainerPredicate
- XXX.component.predicates.CustomDataPredicate
+ XXX.component.predicates.DamagePredicate
- XXX.component.predicates.DataComponentPredicate
+ XXX.component.predicates.DataComponentPredicate$Single
- XXX.component.predicates.DataComponentPredicate$Type
+ XXX.component.predicates.DataComponentPredicates
- XXX.component.predicates.EnchantmentsPredicate
+ XXX.component.predicates.EnchantmentsPredicate$Enchantments
- XXX.component.predicates.EnchantmentsPredicate$StoredEnchantments
+ XXX.component.predicates.FireworkExplosionPredicate
- XXX.component.predicates.FireworkExplosionPredicate$FireworkPredicate
+ XXX.component.predicates.FireworksPredicate
- XXX.component.predicates.JukeboxPlayablePredicate
+ XXX.component.predicates.package-info
+ XXX.component.predicates.PotionsPredicate
- XXX.component.predicates.TrimPredicate
+ XXX.component.predicates.WritableBookPredicate
- XXX.component.predicates.WritableBookPredicate$PagePredicate
+ XXX.component.predicates.WrittenBookPredicate
- XXX.component.predicates.WrittenBookPredicate$PagePredicate
+ XXX.components.debug.DebugEntryBiome
- XXX.components.debug.DebugEntryCategory
+ XXX.components.debug.DebugEntryChunkGeneration
- XXX.components.debug.DebugEntryChunkRenderStats
+ XXX.components.debug.DebugEntryChunkSourceStats
- XXX.components.debug.DebugEntryEntityRenderStats
+ XXX.components.debug.DebugEntryFps
- XXX.components.debug.DebugEntryGpuUtilization
+ XXX.components.debug.DebugEntryHeightmap
- XXX.components.debug.DebugEntryLight
+ XXX.components.debug.DebugEntryLocalDifficulty
- XXX.components.debug.DebugEntryLookingAtBlock
+ XXX.components.debug.DebugEntryLookingAtEntity
- XXX.components.debug.DebugEntryLookingAtFluid
+ XXX.components.debug.DebugEntryMemory
- XXX.components.debug.DebugEntryMemory$AllocationRateCalculator
+ XXX.components.debug.DebugEntryNoop
- XXX.components.debug.DebugEntryParticleRenderStats
+ XXX.components.debug.DebugEntryPosition
- XXX.components.debug.DebugEntryPosition$1
+ XXX.components.debug.DebugEntryPostEffect
- XXX.components.debug.DebugEntrySectionPosition
+ XXX.components.debug.DebugEntrySimplePerformanceImpactors
- XXX.components.debug.DebugEntrySoundMood
+ XXX.components.debug.DebugEntrySpawnCounts
- XXX.components.debug.DebugEntrySystemSpecs
+ XXX.components.debug.DebugEntryTps
- XXX.components.debug.DebugEntryVersion
+ XXX.components.debug.DebugScreenDisplayer
- XXX.components.debug.DebugScreenEntries
+ XXX.components.debug.DebugScreenEntry
- XXX.components.debug.DebugScreenEntryList
+ XXX.components.debug.DebugScreenEntryList$SerializedOptions
- XXX.components.debug.DebugScreenEntryStatus
+ XXX.components.debug.DebugScreenProfile
- XXX.components.debug.package-info
+ XXX.components.debugchart.AbstractDebugChart
- XXX.components.debugchart.BandwidthDebugChart
+ XXX.components.debugchart.FpsDebugChart
+ XXX.components.debugchart.package-info
- XXX.components.debugchart.PingDebugChart
+ XXX.components.debugchart.ProfilerPieChart
- XXX.components.debugchart.TpsDebugChart
- XXX.components.events.AbstractContainerEventHandler
+ XXX.components.events.ContainerEventHandler
- XXX.components.events.GuiEventListener
+ XXX.components.events.package-info
- XXX.components.spectator.package-info
+ XXX.components.spectator.SpectatorGui
+ XXX.components.tabs.GridLayoutTab
- XXX.components.tabs.LoadingTab
+ XXX.components.tabs.package-info
+ XXX.components.tabs.Tab
- XXX.components.tabs.TabManager
+ XXX.components.tabs.TabNavigationBar
- XXX.components.tabs.TabNavigationBar$Builder
- XXX.components.toasts.AdvancementToast
+ XXX.components.toasts.NowPlayingToast
- XXX.components.toasts.package-info
- XXX.components.toasts.RecipeToast
+ XXX.components.toasts.RecipeToast$Entry
- XXX.components.toasts.SystemToast
+ XXX.components.toasts.SystemToast$SystemToastId
- XXX.components.toasts.Toast
+ XXX.components.toasts.Toast$Visibility
- XXX.components.toasts.ToastManager
+ XXX.components.toasts.ToastManager$ToastInstance
- XXX.components.toasts.TutorialToast
+ XXX.components.toasts.TutorialToast$Icons
+ XXX.contents.data.BlockDataSource
- XXX.contents.data.DataSource
+ XXX.contents.data.DataSources
- XXX.contents.data.EntityDataSource
- XXX.contents.data.package-info
+ XXX.contents.data.StorageDataSource
+ XXX.contents.objects.AtlasSprite
- XXX.contents.objects.ObjectInfo
+ XXX.contents.objects.ObjectInfos
+ XXX.contents.objects.package-info
- XXX.contents.objects.PlayerSprite
+ XXX.core.cauldron.CauldronInteraction
- XXX.core.cauldron.CauldronInteraction$InteractionMap
+ XXX.core.cauldron.package-info
- XXX.core.component.DataComponentExactPredicate
+ XXX.core.component.DataComponentExactPredicate$Builder
- XXX.core.component.DataComponentGetter
+ XXX.core.component.DataComponentHolder
- XXX.core.component.DataComponentMap
+ XXX.core.component.DataComponentMap$1
- XXX.core.component.DataComponentMap$2
+ XXX.core.component.DataComponentMap$3
- XXX.core.component.DataComponentMap$Builder
+ XXX.core.component.DataComponentMap$Builder$SimpleMap
- XXX.core.component.DataComponentPatch
+ XXX.core.component.DataComponentPatch$1
- XXX.core.component.DataComponentPatch$2
+ XXX.core.component.DataComponentPatch$3
- XXX.core.component.DataComponentPatch$Builder
+ XXX.core.component.DataComponentPatch$CodecGetter
- XXX.core.component.DataComponentPatch$PatchKey
+ XXX.core.component.DataComponentPatch$SplitResult
+ XXX.core.component.DataComponents
- XXX.core.component.DataComponentType
+ XXX.core.component.DataComponentType$Builder
- XXX.core.component.DataComponentType$Builder$SimpleType
+ XXX.core.component.package-info
- XXX.core.component.PatchedDataComponentMap
+ XXX.core.component.TypedDataComponent
- XXX.core.component.TypedDataComponent$1
- XXX.core.dispenser.BlockSource
+ XXX.core.dispenser.BoatDispenseItemBehavior
- XXX.core.dispenser.DefaultDispenseItemBehavior
+ XXX.core.dispenser.DispenseItemBehavior
- XXX.core.dispenser.DispenseItemBehavior$1
+ XXX.core.dispenser.DispenseItemBehavior$10
- XXX.core.dispenser.DispenseItemBehavior$11
+ XXX.core.dispenser.DispenseItemBehavior$12
- XXX.core.dispenser.DispenseItemBehavior$13
+ XXX.core.dispenser.DispenseItemBehavior$14
- XXX.core.dispenser.DispenseItemBehavior$15
+ XXX.core.dispenser.DispenseItemBehavior$2
- XXX.core.dispenser.DispenseItemBehavior$3
+ XXX.core.dispenser.DispenseItemBehavior$4
- XXX.core.dispenser.DispenseItemBehavior$5
+ XXX.core.dispenser.DispenseItemBehavior$6
- XXX.core.dispenser.DispenseItemBehavior$7
+ XXX.core.dispenser.DispenseItemBehavior$8
- XXX.core.dispenser.DispenseItemBehavior$9
+ XXX.core.dispenser.EquipmentDispenseItemBehavior
- XXX.core.dispenser.MinecartDispenseItemBehavior
+ XXX.core.dispenser.OptionalDispenseItemBehavior
+ XXX.core.dispenser.package-info
- XXX.core.dispenser.ProjectileDispenseBehavior
+ XXX.core.dispenser.ShearsDispenseItemBehavior
- XXX.core.dispenser.ShulkerBoxDispenseBehavior
+ XXX.core.particles.BlockParticleOption
- XXX.core.particles.ColorParticleOption
+ XXX.core.particles.DustColorTransitionOptions
- XXX.core.particles.DustParticleOptions
+ XXX.core.particles.ExplosionParticleInfo
- XXX.core.particles.ItemParticleOption
- XXX.core.particles.package-info
+ XXX.core.particles.ParticleGroup
- XXX.core.particles.ParticleOptions
+ XXX.core.particles.ParticleType
- XXX.core.particles.ParticleTypes
+ XXX.core.particles.ParticleTypes$1
- XXX.core.particles.PowerParticleOption
- XXX.core.particles.TrailParticleOption
+ XXX.core.particles.VibrationParticleOption
+ XXX.core.registries.BuiltInRegistries
- XXX.core.registries.BuiltInRegistries$RegistryBootstrap
- XXX.core.registries.package-info
+ XXX.core.registries.Registries
+ XXX.crafting.display.DisplayContentsFactory
- XXX.crafting.display.DisplayContentsFactory$ForRemainders
+ XXX.crafting.display.DisplayContentsFactory$ForStacks
- XXX.crafting.display.FurnaceRecipeDisplay
+ XXX.crafting.display.package-info
+ XXX.crafting.display.RecipeDisplay
- XXX.crafting.display.RecipeDisplay$Type
+ XXX.crafting.display.RecipeDisplayEntry
- XXX.crafting.display.RecipeDisplayId
+ XXX.crafting.display.RecipeDisplays
- XXX.crafting.display.ShapedCraftingRecipeDisplay
+ XXX.crafting.display.ShapelessCraftingRecipeDisplay
- XXX.crafting.display.SlotDisplay
+ XXX.crafting.display.SlotDisplay$AnyFuel
- XXX.crafting.display.SlotDisplay$Composite
+ XXX.crafting.display.SlotDisplay$Empty
- XXX.crafting.display.SlotDisplay$ItemSlotDisplay
+ XXX.crafting.display.SlotDisplay$ItemStackContentsFactory
- XXX.crafting.display.SlotDisplay$ItemStackSlotDisplay
+ XXX.crafting.display.SlotDisplay$SmithingTrimDemoSlotDisplay
- XXX.crafting.display.SlotDisplay$TagSlotDisplay
+ XXX.crafting.display.SlotDisplay$Type
- XXX.crafting.display.SlotDisplay$WithRemainder
+ XXX.crafting.display.SlotDisplayContext
- XXX.crafting.display.SlotDisplays
+ XXX.crafting.display.SmithingRecipeDisplay
- XXX.crafting.display.StonecutterRecipeDisplay
- XXX.data.advancements.AdvancementProvider
+ XXX.data.advancements.AdvancementSubProvider
- XXX.data.advancements.package-info
- XXX.data.info.BiomeParametersDumpReport
+ XXX.data.info.BlockListReport
- XXX.data.info.CommandsReport
+ XXX.data.info.DatapackStructureReport
- XXX.data.info.DatapackStructureReport$CustomPackEntry
+ XXX.data.info.DatapackStructureReport$Entry
- XXX.data.info.DatapackStructureReport$Format
+ XXX.data.info.DatapackStructureReport$Report
- XXX.data.info.ItemListReport
+ XXX.data.info.package-info
+ XXX.data.info.PacketReport
- XXX.data.info.RegistryDumpReport
- XXX.data.loot.BlockLootSubProvider
+ XXX.data.loot.EntityLootSubProvider
- XXX.data.loot.LootTableProvider
+ XXX.data.loot.LootTableProvider$MissingTableProblem
- XXX.data.loot.LootTableProvider$SubProviderEntry
+ XXX.data.loot.LootTableSubProvider
- XXX.data.loot.package-info
- XXX.data.metadata.package-info
+ XXX.data.metadata.PackMetadataGenerator
+ XXX.data.models.BlockModelGenerators
- XXX.data.models.BlockModelGenerators$1
+ XXX.data.models.BlockModelGenerators$BlockFamilyProvider
- XXX.data.models.BlockModelGenerators$BlockStateGeneratorSupplier
+ XXX.data.models.BlockModelGenerators$BookSlotModelCacheKey
- XXX.data.models.BlockModelGenerators$PlantType
+ XXX.data.models.BlockModelGenerators$WoodProvider
- XXX.data.models.EquipmentAssetProvider
+ XXX.data.models.ItemModelGenerators
- XXX.data.models.ItemModelGenerators$TrimMaterialData
+ XXX.data.models.ItemModelOutput
- XXX.data.models.ModelProvider
+ XXX.data.models.ModelProvider$BlockStateGeneratorCollector
- XXX.data.models.ModelProvider$ItemInfoCollector
+ XXX.data.models.ModelProvider$SimpleModelCollector
- XXX.data.models.MultiVariant
- XXX.data.models.package-info
+ XXX.data.models.WaypointStyleProvider
- XXX.data.recipes.package-info
- XXX.data.recipes.RecipeBuilder
+ XXX.data.recipes.RecipeBuilder$1
- XXX.data.recipes.RecipeCategory
+ XXX.data.recipes.RecipeOutput
- XXX.data.recipes.RecipeProvider
+ XXX.data.recipes.RecipeProvider$FamilyRecipeProvider
- XXX.data.recipes.RecipeProvider$Runner
+ XXX.data.recipes.RecipeProvider$Runner$1
- XXX.data.recipes.ShapedRecipeBuilder
+ XXX.data.recipes.ShapelessRecipeBuilder
- XXX.data.recipes.SimpleCookingRecipeBuilder
+ XXX.data.recipes.SingleItemRecipeBuilder
- XXX.data.recipes.SmithingTransformRecipeBuilder
+ XXX.data.recipes.SmithingTrimRecipeBuilder
- XXX.data.recipes.SpecialRecipeBuilder
+ XXX.data.recipes.TransmuteRecipeBuilder
+ XXX.data.registries.package-info
+ XXX.data.registries.RegistriesDatapackGenerator
- XXX.data.registries.RegistryPatchGenerator
+ XXX.data.registries.TradeRebalanceRegistries
- XXX.data.registries.VanillaRegistries
- XXX.data.structures.NbtToSnbt
+ XXX.data.structures.package-info
+ XXX.data.structures.SnbtDatafixer
- XXX.data.structures.SnbtToNbt
+ XXX.data.structures.SnbtToNbt$Filter
- XXX.data.structures.SnbtToNbt$StructureConversionException
+ XXX.data.structures.SnbtToNbt$TaskResult
- XXX.data.structures.StructureUpdater
- XXX.data.tags.BannerPatternTagsProvider
+ XXX.data.tags.BiomeTagsProvider
- XXX.data.tags.BlockItemTagsProvider
+ XXX.data.tags.DamageTypeTagsProvider
- XXX.data.tags.DialogTagsProvider
+ XXX.data.tags.EnchantmentTagsProvider
- XXX.data.tags.EntityTypeTagsProvider
+ XXX.data.tags.FlatLevelGeneratorPresetTagsProvider
- XXX.data.tags.FluidTagsProvider
+ XXX.data.tags.GameEventTagsProvider
- XXX.data.tags.InstrumentTagsProvider
+ XXX.data.tags.IntrinsicHolderTagsProvider
- XXX.data.tags.KeyTagProvider
- XXX.data.tags.package-info
+ XXX.data.tags.PaintingVariantTagsProvider
- XXX.data.tags.PoiTypeTagsProvider
+ XXX.data.tags.StructureTagsProvider
- XXX.data.tags.TagAppender
+ XXX.data.tags.TagAppender$1
- XXX.data.tags.TagAppender$2
+ XXX.data.tags.TagsProvider
- XXX.data.tags.TagsProvider$1CombinedData
+ XXX.data.tags.TagsProvider$TagLookup
- XXX.data.tags.TradeRebalanceEnchantmentTagsProvider
+ XXX.data.tags.VanillaBlockTagsProvider
- XXX.data.tags.VanillaBlockTagsProvider$1
+ XXX.data.tags.VanillaEnchantmentTagsProvider
- XXX.data.tags.VanillaItemTagsProvider
+ XXX.data.tags.VanillaItemTagsProvider$1
- XXX.data.tags.VanillaItemTagsProvider$BlockToItemConverter
+ XXX.data.tags.WorldPresetTagsProvider
+ XXX.data.worldgen.AncientCityStructurePieces
- XXX.data.worldgen.AncientCityStructurePools
+ XXX.data.worldgen.BastionBridgePools
- XXX.data.worldgen.BastionHoglinStablePools
+ XXX.data.worldgen.BastionHousingUnitsPools
- XXX.data.worldgen.BastionPieces
+ XXX.data.worldgen.BastionSharedPools
- XXX.data.worldgen.BastionTreasureRoomPools
+ XXX.data.worldgen.BiomeDefaultFeatures
- XXX.data.worldgen.BootstrapContext
+ XXX.data.worldgen.Carvers
- XXX.data.worldgen.DesertVillagePools
+ XXX.data.worldgen.DimensionTypes
- XXX.data.worldgen.NoiseData
+ XXX.data.worldgen.package-info
+ XXX.data.worldgen.PillagerOutpostPools
- XXX.data.worldgen.PlainVillagePools
+ XXX.data.worldgen.Pools
- XXX.data.worldgen.ProcessorLists
+ XXX.data.worldgen.SavannaVillagePools
- XXX.data.worldgen.SnowyVillagePools
- XXX.data.worldgen.Structures
+ XXX.data.worldgen.StructureSets
+ XXX.data.worldgen.SurfaceRuleData
- XXX.data.worldgen.TaigaVillagePools
+ XXX.data.worldgen.TerrainProvider
- XXX.data.worldgen.TrailRuinsStructurePools
+ XXX.data.worldgen.TrialChambersStructurePools
- XXX.data.worldgen.VillagePools
+ XXX.datafix.fixes.AbstractArrowPickupFix
- XXX.datafix.fixes.AbstractBlockPropertyFix
+ XXX.datafix.fixes.AbstractPoiSectionFix
- XXX.datafix.fixes.AbstractUUIDFix
+ XXX.datafix.fixes.AddFieldFix
- XXX.datafix.fixes.AddFlagIfNotPresentFix
+ XXX.datafix.fixes.AddNewChoices
- XXX.datafix.fixes.AdvancementsFix
+ XXX.datafix.fixes.AdvancementsRenameFix
- XXX.datafix.fixes.AreaEffectCloudDurationScaleFix
+ XXX.datafix.fixes.AreaEffectCloudPotionFix
- XXX.datafix.fixes.AttributeIdPrefixFix
+ XXX.datafix.fixes.AttributeModifierIdFix
- XXX.datafix.fixes.AttributesRenameFix
+ XXX.datafix.fixes.AttributesRenameLegacy
- XXX.datafix.fixes.BannerEntityCustomNameToOverrideComponentFix
+ XXX.datafix.fixes.BannerPatternFormatFix
- XXX.datafix.fixes.BedItemColorFix
+ XXX.datafix.fixes.BeehiveFieldRenameFix
- XXX.datafix.fixes.BiomeFix
+ XXX.datafix.fixes.BitStorageAlignFix
- XXX.datafix.fixes.BlendingDataFix
+ XXX.datafix.fixes.BlendingDataRemoveFromNetherEndFix
- XXX.datafix.fixes.BlockEntityBannerColorFix
+ XXX.datafix.fixes.BlockEntityBlockStateFix
- XXX.datafix.fixes.BlockEntityCustomNameToComponentFix
+ XXX.datafix.fixes.BlockEntityFurnaceBurnTimeFix
- XXX.datafix.fixes.BlockEntityIdFix
+ XXX.datafix.fixes.BlockEntityJukeboxFix
- XXX.datafix.fixes.BlockEntityKeepPacked
+ XXX.datafix.fixes.BlockEntityRenameFix
- XXX.datafix.fixes.BlockEntityShulkerBoxColorFix
+ XXX.datafix.fixes.BlockEntitySignDoubleSidedEditableTextFix
- XXX.datafix.fixes.BlockEntityUUIDFix
+ XXX.datafix.fixes.BlockNameFlatteningFix
- XXX.datafix.fixes.BlockPosFormatAndRenamesFix
+ XXX.datafix.fixes.BlockPropertyRenameAndFix
- XXX.datafix.fixes.BlockRenameFix
+ XXX.datafix.fixes.BlockRenameFix$1
- XXX.datafix.fixes.BlockStateData
+ XXX.datafix.fixes.BlockStateStructureTemplateFix
- XXX.datafix.fixes.BoatSplitFix
+ XXX.datafix.fixes.CarvingStepRemoveFix
- XXX.datafix.fixes.CatTypeFix
+ XXX.datafix.fixes.CauldronRenameFix
- XXX.datafix.fixes.CavesAndCliffsRenames
+ XXX.datafix.fixes.ChestedHorsesInventoryZeroIndexingFix
- XXX.datafix.fixes.ChunkBedBlockEntityInjecterFix
+ XXX.datafix.fixes.ChunkBiomeFix
- XXX.datafix.fixes.ChunkDeleteIgnoredLightDataFix
+ XXX.datafix.fixes.ChunkDeleteLightFix
- XXX.datafix.fixes.ChunkHeightAndBiomeFix
+ XXX.datafix.fixes.ChunkLightRemoveFix
- XXX.datafix.fixes.ChunkPalettedStorageFix
+ XXX.datafix.fixes.ChunkPalettedStorageFix$DataLayer
- XXX.datafix.fixes.ChunkPalettedStorageFix$Direction
+ XXX.datafix.fixes.ChunkPalettedStorageFix$Direction$Axis
- XXX.datafix.fixes.ChunkPalettedStorageFix$Direction$AxisDirection
+ XXX.datafix.fixes.ChunkPalettedStorageFix$MappingConstants
- XXX.datafix.fixes.ChunkPalettedStorageFix$Section
+ XXX.datafix.fixes.ChunkPalettedStorageFix$UpgradeChunk
- XXX.datafix.fixes.ChunkProtoTickListFix
+ XXX.datafix.fixes.ChunkProtoTickListFix$PoorMansPalettedContainer
- XXX.datafix.fixes.ChunkRenamesFix
+ XXX.datafix.fixes.ChunkStatusFix
- XXX.datafix.fixes.ChunkStatusFix2
+ XXX.datafix.fixes.ChunkStructuresTemplateRenameFix
- XXX.datafix.fixes.ChunkTicketUnpackPosFix
+ XXX.datafix.fixes.ChunkToProtochunkFix
- XXX.datafix.fixes.ColorlessShulkerEntityFix
+ XXX.datafix.fixes.ContainerBlockEntityLockPredicateFix
- XXX.datafix.fixes.CopperGolemWeatherStateFix
+ XXX.datafix.fixes.CriteriaRenameFix
- XXX.datafix.fixes.CustomModelDataExpandFix
+ XXX.datafix.fixes.DataComponentRemainderFix
- XXX.datafix.fixes.DecoratedPotFieldRenameFix
+ XXX.datafix.fixes.DropChancesFormatFix
- XXX.datafix.fixes.DropInvalidSignDataFix
+ XXX.datafix.fixes.DyeItemRenameFix
- XXX.datafix.fixes.EffectDurationFix
+ XXX.datafix.fixes.EmptyItemInHotbarFix
- XXX.datafix.fixes.EmptyItemInVillagerTradeFix
+ XXX.datafix.fixes.EntityArmorStandSilentFix
- XXX.datafix.fixes.EntityAttributeBaseValueFix
+ XXX.datafix.fixes.EntityBlockStateFix
- XXX.datafix.fixes.EntityBrushableBlockFieldsRenameFix
+ XXX.datafix.fixes.EntityCatSplitFix
- XXX.datafix.fixes.EntityCodSalmonFix
+ XXX.datafix.fixes.EntityCustomNameToComponentFix
- XXX.datafix.fixes.EntityElderGuardianSplitFix
+ XXX.datafix.fixes.EntityEquipmentToArmorAndHandFix
- XXX.datafix.fixes.EntityFallDistanceFloatToDoubleFix
+ XXX.datafix.fixes.EntityFieldsRenameFix
- XXX.datafix.fixes.EntityGoatMissingStateFix
+ XXX.datafix.fixes.EntityHealthFix
- XXX.datafix.fixes.EntityHorseSaddleFix
+ XXX.datafix.fixes.EntityHorseSplitFix
- XXX.datafix.fixes.EntityIdFix
+ XXX.datafix.fixes.EntityItemFrameDirectionFix
- XXX.datafix.fixes.EntityMinecartIdentifiersFix
+ XXX.datafix.fixes.EntityPaintingItemFrameDirectionFix
- XXX.datafix.fixes.EntityPaintingMotiveFix
+ XXX.datafix.fixes.EntityProjectileOwnerFix
- XXX.datafix.fixes.EntityPufferfishRenameFix
+ XXX.datafix.fixes.EntityRavagerRenameFix
- XXX.datafix.fixes.EntityRedundantChanceTagsFix
+ XXX.datafix.fixes.EntityRenameFix
- XXX.datafix.fixes.EntityRidingToPassengersFix
+ XXX.datafix.fixes.EntitySalmonSizeFix
- XXX.datafix.fixes.EntityShulkerColorFix
+ XXX.datafix.fixes.EntityShulkerRotationFix
- XXX.datafix.fixes.EntitySkeletonSplitFix
+ XXX.datafix.fixes.EntitySpawnerItemVariantComponentFix
- XXX.datafix.fixes.EntitySpawnerItemVariantComponentFix$Fixer
+ XXX.datafix.fixes.EntityStringUuidFix
- XXX.datafix.fixes.EntityTheRenameningFix
+ XXX.datafix.fixes.EntityTippedArrowFix
- XXX.datafix.fixes.EntityUUIDFix
+ XXX.datafix.fixes.EntityVariantFix
- XXX.datafix.fixes.EntityWolfColorFix
+ XXX.datafix.fixes.EntityZombieSplitFix
- XXX.datafix.fixes.EntityZombieVillagerTypeFix
+ XXX.datafix.fixes.EntityZombifiedPiglinRenameFix
- XXX.datafix.fixes.EquipmentFormatFix
+ XXX.datafix.fixes.EquippableAssetRenameFix
- XXX.datafix.fixes.FeatureFlagRemoveFix
+ XXX.datafix.fixes.FilteredBooksFix
- XXX.datafix.fixes.FilteredSignsFix
+ XXX.datafix.fixes.FireResistantToDamageResistantComponentFix
- XXX.datafix.fixes.FixProjectileStoredItem
+ XXX.datafix.fixes.FixProjectileStoredItem$SubFixer
- XXX.datafix.fixes.FixWolfHealth
+ XXX.datafix.fixes.FoodToConsumableFix
+ XXX.datafix.fixes.ForcedChunkToTicketFix
- XXX.datafix.fixes.ForcePoiRebuild
- XXX.datafix.fixes.FurnaceRecipeFix
+ XXX.datafix.fixes.GoatHornIdFix
- XXX.datafix.fixes.GossipUUIDFix
+ XXX.datafix.fixes.HeightmapRenamingFix
- XXX.datafix.fixes.HorseBodyArmorItemFix
+ XXX.datafix.fixes.IglooMetadataRemovalFix
- XXX.datafix.fixes.InlineBlockPosFormatFix
+ XXX.datafix.fixes.InvalidBlockEntityLockFix
- XXX.datafix.fixes.InvalidLockComponentFix
+ XXX.datafix.fixes.ItemBannerColorFix
- XXX.datafix.fixes.ItemCustomNameToComponentFix
+ XXX.datafix.fixes.ItemIdFix
- XXX.datafix.fixes.ItemLoreFix
+ XXX.datafix.fixes.ItemPotionFix
- XXX.datafix.fixes.ItemRenameFix
+ XXX.datafix.fixes.ItemRenameFix$1
- XXX.datafix.fixes.ItemShulkerBoxColorFix
+ XXX.datafix.fixes.ItemSpawnEggFix
- XXX.datafix.fixes.ItemStackComponentizationFix
+ XXX.datafix.fixes.ItemStackComponentizationFix$ItemStackData
- XXX.datafix.fixes.ItemStackCustomNameToOverrideComponentFix
+ XXX.datafix.fixes.ItemStackEnchantmentNamesFix
- XXX.datafix.fixes.ItemStackMapIdFix
+ XXX.datafix.fixes.ItemStackSpawnEggFix
- XXX.datafix.fixes.ItemStackTagFix
+ XXX.datafix.fixes.ItemStackTagRemainderFix
- XXX.datafix.fixes.ItemStackTheFlatteningFix
+ XXX.datafix.fixes.ItemStackUUIDFix
- XXX.datafix.fixes.ItemWaterPotionFix
+ XXX.datafix.fixes.JigsawPropertiesFix
- XXX.datafix.fixes.JigsawRotationFix
+ XXX.datafix.fixes.JukeboxTicksSinceSongStartedFix
- XXX.datafix.fixes.LeavesFix
+ XXX.datafix.fixes.LeavesFix$LeavesSection
- XXX.datafix.fixes.LeavesFix$Section
+ XXX.datafix.fixes.LegacyDimensionIdFix
- XXX.datafix.fixes.LegacyDragonFightFix
+ XXX.datafix.fixes.LegacyHoverEventFix
- XXX.datafix.fixes.LegacyWorldBorderFix
+ XXX.datafix.schemas.package-info
- XXX.datafix.schemas.V4543
+ XXX.datafix.schemas.V501
- XXX.datafix.schemas.V700
+ XXX.datafix.schemas.V701
- XXX.datafix.schemas.V702
+ XXX.datafix.schemas.V703
- XXX.datafix.schemas.V704
+ XXX.datafix.schemas.V704$1
- XXX.datafix.schemas.V705
+ XXX.datafix.schemas.V705$1
- XXX.datafix.schemas.V808
+ XXX.datafix.schemas.V99
- XXX.datafix.schemas.V99$1
+ XXX.enchantment.effects.AddValue
- XXX.enchantment.effects.AllOf
+ XXX.enchantment.effects.AllOf$EntityEffects
- XXX.enchantment.effects.AllOf$LocationBasedEffects
+ XXX.enchantment.effects.AllOf$ValueEffects
- XXX.enchantment.effects.ApplyMobEffect
+ XXX.enchantment.effects.ChangeItemDamage
- XXX.enchantment.effects.DamageEntity
+ XXX.enchantment.effects.DamageImmunity
- XXX.enchantment.effects.EnchantmentAttributeEffect
+ XXX.enchantment.effects.EnchantmentEntityEffect
- XXX.enchantment.effects.EnchantmentLocationBasedEffect
+ XXX.enchantment.effects.EnchantmentValueEffect
- XXX.enchantment.effects.ExplodeEffect
+ XXX.enchantment.effects.Ignite
- XXX.enchantment.effects.MultiplyValue
- XXX.enchantment.effects.package-info
+ XXX.enchantment.effects.PlaySoundEffect
- XXX.enchantment.effects.RemoveBinomial
+ XXX.enchantment.effects.ReplaceBlock
- XXX.enchantment.effects.ReplaceDisk
+ XXX.enchantment.effects.RunFunction
- XXX.enchantment.effects.SetBlockProperties
+ XXX.enchantment.effects.SetValue
- XXX.enchantment.effects.SpawnParticlesEffect
+ XXX.enchantment.effects.SpawnParticlesEffect$PositionSource
- XXX.enchantment.effects.SpawnParticlesEffect$PositionSourceType
+ XXX.enchantment.effects.SpawnParticlesEffect$PositionSourceType$CoordinateSource
- XXX.enchantment.effects.SpawnParticlesEffect$VelocitySource
+ XXX.enchantment.effects.SummonEntityEffect
- XXX.enchantment.providers.EnchantmentProvider
+ XXX.enchantment.providers.EnchantmentProviderTypes
- XXX.enchantment.providers.EnchantmentsByCost
+ XXX.enchantment.providers.EnchantmentsByCostWithDifficulty
+ XXX.enchantment.providers.package-info
- XXX.enchantment.providers.SingleEnchantment
+ XXX.enchantment.providers.TradeRebalanceEnchantmentProviders
- XXX.enchantment.providers.VanillaEnchantmentProviders
- XXX.entity.decoration.Mannequin
+ XXX.entity.layers.ArrowLayer
- XXX.entity.layers.BeeStingerLayer
+ XXX.entity.layers.BlockDecorationLayer
- XXX.entity.layers.BreezeEyesLayer
+ XXX.entity.layers.BreezeWindLayer
- XXX.entity.layers.CapeLayer
+ XXX.entity.layers.CarriedBlockLayer
- XXX.entity.layers.CatCollarLayer
+ XXX.entity.layers.CreeperPowerLayer
- XXX.entity.layers.CrossedArmsItemLayer
+ XXX.entity.layers.CustomHeadLayer
- XXX.entity.layers.CustomHeadLayer$Transforms
+ XXX.entity.layers.Deadmau5EarsLayer
- XXX.entity.layers.DolphinCarryingItemLayer
+ XXX.entity.layers.DrownedOuterLayer
- XXX.entity.layers.EnderEyesLayer
+ XXX.entity.layers.EnergySwirlLayer
- XXX.entity.layers.EquipmentLayerRenderer
+ XXX.entity.layers.EquipmentLayerRenderer$LayerTextureKey
- XXX.entity.layers.EquipmentLayerRenderer$TrimSpriteKey
+ XXX.entity.layers.EyesLayer
- XXX.entity.layers.FoxHeldItemLayer
+ XXX.entity.layers.HorseMarkingLayer
- XXX.entity.layers.HumanoidArmorLayer
+ XXX.entity.layers.IronGolemCrackinessLayer
- XXX.entity.layers.IronGolemFlowerLayer
+ XXX.entity.layers.ItemInHandLayer
- XXX.entity.layers.LivingEntityEmissiveLayer
+ XXX.entity.layers.LivingEntityEmissiveLayer$AlphaFunction
- XXX.entity.layers.LlamaDecorLayer
+ XXX.entity.layers.MushroomCowMushroomLayer
- XXX.entity.layers.package-info
- XXX.entity.layers.PandaHoldsItemLayer
+ XXX.entity.layers.ParrotOnShoulderLayer
- XXX.entity.layers.PhantomEyesLayer
+ XXX.entity.layers.PlayerItemInHandLayer
- XXX.entity.layers.RenderLayer
+ XXX.entity.layers.RopesLayer
- XXX.entity.layers.SheepWoolLayer
+ XXX.entity.layers.SheepWoolUndercoatLayer
- XXX.entity.layers.SimpleEquipmentLayer
+ XXX.entity.layers.SkeletonClothingLayer
- XXX.entity.layers.SlimeOuterLayer
+ XXX.entity.layers.SnowGolemHeadLayer
- XXX.entity.layers.SpiderEyesLayer
+ XXX.entity.layers.SpinAttackEffectLayer
- XXX.entity.layers.StuckInBodyLayer
+ XXX.entity.layers.StuckInBodyLayer$PlacementStyle
- XXX.entity.layers.TropicalFishPatternLayer
+ XXX.entity.layers.TropicalFishPatternLayer$1
- XXX.entity.layers.VillagerProfessionLayer
+ XXX.entity.layers.WingsLayer
- XXX.entity.layers.WitchItemLayer
+ XXX.entity.layers.WitherArmorLayer
- XXX.entity.layers.WolfArmorLayer
+ XXX.entity.layers.WolfCollarLayer
- XXX.entity.player.AvatarRenderer
+ XXX.entity.player.package-info
+ XXX.entity.player.package-info
- XXX.entity.player.ProfileKeyPair
+ XXX.entity.player.ProfilePublicKey
- XXX.entity.player.ProfilePublicKey$Data
+ XXX.entity.player.ProfilePublicKey$ValidationException
- XXX.entity.player.StackedContents
+ XXX.entity.player.StackedContents$IngredientInfo
- XXX.entity.player.StackedContents$Output
+ XXX.entity.player.StackedContents$RecipePicker
- XXX.entity.player.StackedItemContents
- XXX.entity.projectile.AbstractArrow
+ XXX.entity.projectile.AbstractArrow$Pickup
- XXX.entity.projectile.AbstractHurtingProjectile
+ XXX.entity.projectile.AbstractThrownPotion
- XXX.entity.projectile.Arrow
+ XXX.entity.projectile.DragonFireball
- XXX.entity.projectile.EvokerFangs
+ XXX.entity.projectile.EyeOfEnder
- XXX.entity.projectile.Fireball
+ XXX.entity.projectile.FireworkRocketEntity
- XXX.entity.projectile.FishingHook
+ XXX.entity.projectile.FishingHook$FishHookState
- XXX.entity.projectile.FishingHook$OpenWaterType
+ XXX.entity.projectile.ItemSupplier
- XXX.entity.projectile.LargeFireball
+ XXX.entity.projectile.LlamaSpit
+ XXX.entity.projectile.package-info
- XXX.entity.projectile.Projectile
+ XXX.entity.projectile.Projectile$ProjectileFactory
- XXX.entity.projectile.ProjectileDeflection
+ XXX.entity.projectile.ProjectileUtil
- XXX.entity.projectile.ShulkerBullet
+ XXX.entity.projectile.SmallFireball
- XXX.entity.projectile.Snowball
+ XXX.entity.projectile.SpectralArrow
- XXX.entity.projectile.ThrowableItemProjectile
+ XXX.entity.projectile.ThrowableProjectile
- XXX.entity.projectile.ThrownEgg
+ XXX.entity.projectile.ThrownEnderpearl
- XXX.entity.projectile.ThrownExperienceBottle
+ XXX.entity.projectile.ThrownLingeringPotion
- XXX.entity.projectile.ThrownSplashPotion
+ XXX.entity.projectile.ThrownTrident
- XXX.entity.projectile.WitherSkull
+ XXX.entity.raid.package-info
- XXX.entity.raid.Raid
+ XXX.entity.raid.Raid$1
+ XXX.entity.raid.Raid$RaiderType
- XXX.entity.raid.Raid$RaidStatus
- XXX.entity.raid.Raider
+ XXX.entity.raid.Raider$HoldGroundAttackGoal
- XXX.entity.raid.Raider$ObtainRaidLeaderBannerGoal
+ XXX.entity.raid.Raider$RaiderCelebration
- XXX.entity.raid.Raider$RaiderMoveThroughVillageGoal
+ XXX.entity.raid.Raids
- XXX.entity.raid.Raids$RaidWithId
- XXX.entity.schedule.Activity
+ XXX.entity.schedule.Keyframe
- XXX.entity.schedule.package-info
- XXX.entity.schedule.Schedule
+ XXX.entity.schedule.ScheduleBuilder
- XXX.entity.schedule.ScheduleBuilder$ActivityTransition
+ XXX.entity.schedule.Timeline
- XXX.entity.state.AllayRenderState
+ XXX.entity.state.ArmadilloRenderState
- XXX.entity.state.ArmedEntityRenderState
+ XXX.entity.state.ArmorStandRenderState
- XXX.entity.state.ArrowRenderState
- XXX.entity.state.package-info
+ XXX.entity.state.PolarBearRenderState
- XXX.entity.state.PufferfishRenderState
+ XXX.entity.state.RabbitRenderState
- XXX.entity.state.RavagerRenderState
+ XXX.entity.state.SalmonRenderState
- XXX.entity.state.ServerHitboxesRenderState
+ XXX.entity.state.SheepRenderState
- XXX.entity.state.ShulkerBulletRenderState
+ XXX.entity.state.ShulkerRenderState
- XXX.entity.state.SkeletonRenderState
+ XXX.entity.state.SlimeRenderState
- XXX.entity.state.SnifferRenderState
+ XXX.entity.state.SnowGolemRenderState
- XXX.entity.state.SquidRenderState
+ XXX.entity.state.StriderRenderState
- XXX.entity.state.TextDisplayEntityRenderState
+ XXX.entity.state.ThrownItemRenderState
- XXX.entity.state.ThrownTridentRenderState
+ XXX.entity.state.TippableArrowRenderState
- XXX.entity.state.TntRenderState
+ XXX.entity.state.TropicalFishRenderState
- XXX.entity.state.TurtleRenderState
+ XXX.entity.state.VexRenderState
- XXX.entity.state.VillagerDataHolderRenderState
+ XXX.entity.state.VillagerRenderState
- XXX.entity.state.WardenRenderState
+ XXX.entity.state.WitchRenderState
- XXX.entity.state.WitherRenderState
+ XXX.entity.state.WitherSkullRenderState
- XXX.entity.state.WolfRenderState
+ XXX.entity.state.ZombieRenderState
- XXX.entity.state.ZombieVillagerRenderState
+ XXX.entity.state.ZombifiedPiglinRenderState
+ XXX.entity.variant.BiomeCheck
- XXX.entity.variant.ModelAndTexture
+ XXX.entity.variant.MoonBrightnessCheck
- XXX.entity.variant.package-info
- XXX.entity.variant.PriorityProvider
+ XXX.entity.variant.PriorityProvider$Selector
- XXX.entity.variant.PriorityProvider$SelectorCondition
+ XXX.entity.variant.PriorityProvider$UnpackedEntry
- XXX.entity.variant.SpawnCondition
+ XXX.entity.variant.SpawnConditions
- XXX.entity.variant.SpawnContext
+ XXX.entity.variant.SpawnPrioritySelectors
- XXX.entity.variant.StructureCheck
+ XXX.entity.variant.VariantUtils
+ XXX.entity.vehicle.AbstractBoat
- XXX.entity.vehicle.AbstractBoat$Status
+ XXX.entity.vehicle.AbstractChestBoat
- XXX.entity.vehicle.AbstractMinecart
+ XXX.entity.vehicle.AbstractMinecartContainer
- XXX.entity.vehicle.Boat
+ XXX.entity.vehicle.ChestBoat
- XXX.entity.vehicle.ChestRaft
+ XXX.entity.vehicle.ContainerEntity
- XXX.entity.vehicle.ContainerEntity$1
+ XXX.entity.vehicle.DismountHelper
- XXX.entity.vehicle.Minecart
+ XXX.entity.vehicle.MinecartBehavior
- XXX.entity.vehicle.MinecartChest
+ XXX.entity.vehicle.MinecartCommandBlock
- XXX.entity.vehicle.MinecartCommandBlock$MinecartCommandBase
+ XXX.entity.vehicle.MinecartFurnace
- XXX.entity.vehicle.MinecartHopper
+ XXX.entity.vehicle.MinecartSpawner
- XXX.entity.vehicle.MinecartSpawner$1
+ XXX.entity.vehicle.MinecartTNT
- XXX.entity.vehicle.NewMinecartBehavior
+ XXX.entity.vehicle.NewMinecartBehavior$1
- XXX.entity.vehicle.NewMinecartBehavior$MinecartStep
+ XXX.entity.vehicle.NewMinecartBehavior$StepPartialTicks
- XXX.entity.vehicle.NewMinecartBehavior$TrackIteration
+ XXX.entity.vehicle.OldMinecartBehavior
- XXX.entity.vehicle.OldMinecartBehavior$1
+ XXX.entity.vehicle.package-info
+ XXX.entity.vehicle.Raft
- XXX.entity.vehicle.VehicleEntity
+ XXX.equipment.trim.ArmorTrim
- XXX.equipment.trim.MaterialAssetGroup
+ XXX.equipment.trim.MaterialAssetGroup$AssetInfo
- XXX.equipment.trim.package-info
- XXX.equipment.trim.TrimMaterial
+ XXX.equipment.trim.TrimMaterials
- XXX.equipment.trim.TrimPattern
+ XXX.equipment.trim.TrimPatterns
- XXX.execution.tasks.BuildContexts
+ XXX.execution.tasks.BuildContexts$Continuation
- XXX.execution.tasks.BuildContexts$TopLevel
+ XXX.execution.tasks.BuildContexts$Unbound
- XXX.execution.tasks.CallFunction
+ XXX.execution.tasks.ContinuationTask
- XXX.execution.tasks.ContinuationTask$TaskProvider
+ XXX.execution.tasks.ExecuteCommand
- XXX.execution.tasks.FallthroughTask
+ XXX.execution.tasks.IsolatedCall
- XXX.execution.tasks.package-info
- XXX.font.glyphs.BakedGlyph
+ XXX.font.glyphs.BakedSheetGlyph
- XXX.font.glyphs.BakedSheetGlyph$EffectInstance
+ XXX.font.glyphs.BakedSheetGlyph$GlyphInstance
- XXX.font.glyphs.EffectGlyph
+ XXX.font.glyphs.EmptyGlyph
- XXX.font.glyphs.EmptyGlyph$1
- XXX.font.glyphs.package-info
+ XXX.font.glyphs.SpecialGlyphs
- XXX.font.glyphs.SpecialGlyphs$1
+ XXX.font.glyphs.SpecialGlyphs$PixelProvider
- XXX.font.providers.BitmapProvider
+ XXX.font.providers.BitmapProvider$Definition
- XXX.font.providers.BitmapProvider$Glyph
+ XXX.font.providers.BitmapProvider$Glyph$1
- XXX.font.providers.FreeTypeUtil
+ XXX.font.providers.GlyphProviderDefinition
- XXX.font.providers.GlyphProviderDefinition$Conditional
+ XXX.font.providers.GlyphProviderDefinition$Loader
- XXX.font.providers.GlyphProviderDefinition$Reference
+ XXX.font.providers.GlyphProviderType
+ XXX.font.providers.package-info
- XXX.font.providers.ProviderReferenceDefinition
+ XXX.font.providers.TrueTypeGlyphProviderDefinition
- XXX.font.providers.TrueTypeGlyphProviderDefinition$Shift
+ XXX.font.providers.UnihexProvider
- XXX.font.providers.UnihexProvider$ByteContents
+ XXX.font.providers.UnihexProvider$Definition
- XXX.font.providers.UnihexProvider$Dimensions
+ XXX.font.providers.UnihexProvider$Glyph
- XXX.font.providers.UnihexProvider$Glyph$1
+ XXX.font.providers.UnihexProvider$Glyph$2
- XXX.font.providers.UnihexProvider$IntContents
+ XXX.font.providers.UnihexProvider$LineData
- XXX.font.providers.UnihexProvider$OverrideRange
+ XXX.font.providers.UnihexProvider$ReaderOutput
- XXX.font.providers.UnihexProvider$ShortContents
- XXX.gametest.framework.BlockBasedTestInstance
+ XXX.gametest.framework.BuiltinTestFunctions
- XXX.gametest.framework.ExhaustedAttemptsException
+ XXX.gametest.framework.FailedTestTracker
- XXX.gametest.framework.FunctionGameTestInstance
+ XXX.gametest.framework.GameTestAssertException
- XXX.gametest.framework.GameTestAssertPosException
+ XXX.gametest.framework.GameTestBatch
- XXX.gametest.framework.GameTestBatchFactory
+ XXX.gametest.framework.GameTestBatchFactory$TestDecorator
- XXX.gametest.framework.GameTestBatchListener
+ XXX.gametest.framework.GameTestEnvironments
- XXX.gametest.framework.GameTestEvent
+ XXX.gametest.framework.GameTestException
- XXX.gametest.framework.GameTestHelper
+ XXX.gametest.framework.GameTestHelper$1
- XXX.gametest.framework.GameTestHelper$2
+ XXX.gametest.framework.GameTestHelper$3
- XXX.gametest.framework.GameTestInfo
+ XXX.gametest.framework.GameTestInstance
- XXX.gametest.framework.GameTestInstances
+ XXX.gametest.framework.GameTestListener
- XXX.gametest.framework.GameTestMainUtil
+ XXX.gametest.framework.GameTestRunner
- XXX.gametest.framework.GameTestRunner$1
+ XXX.gametest.framework.GameTestRunner$Builder
- XXX.gametest.framework.GameTestRunner$GameTestBatcher
+ XXX.gametest.framework.GameTestRunner$StructureSpawner
- XXX.gametest.framework.GameTestSequence
+ XXX.gametest.framework.GameTestSequence$Condition
- XXX.gametest.framework.GameTestServer
+ XXX.gametest.framework.GameTestServer$1
- XXX.gametest.framework.GameTestServer$MockProfileResolver
+ XXX.gametest.framework.GameTestServer$MockUserNameToIdResolver
- XXX.gametest.framework.GameTestTicker
+ XXX.gametest.framework.GameTestTicker$State
- XXX.gametest.framework.GameTestTimeoutException
+ XXX.gametest.framework.GeneratedTest
- XXX.gametest.framework.GlobalTestReporter
+ XXX.gametest.framework.JUnitLikeTestReporter
- XXX.gametest.framework.LogTestReporter
+ XXX.gametest.framework.MultipleTestTracker
- XXX.gametest.framework.MultipleTestTracker$1
+ XXX.gametest.framework.package-info
+ XXX.gametest.framework.ReportGameListener
- XXX.gametest.framework.RetryOptions
+ XXX.gametest.framework.StructureGridSpawner
- XXX.gametest.framework.StructureUtils
+ XXX.gametest.framework.StructureUtils$1
- XXX.gametest.framework.TestCommand
+ XXX.gametest.framework.TestCommand$TestBatchSummaryDisplayer
- XXX.gametest.framework.TestCommand$TestSummaryDisplayer
+ XXX.gametest.framework.TestData
- XXX.gametest.framework.TestEnvironmentDefinition
+ XXX.gametest.framework.TestEnvironmentDefinition$AllOf
- XXX.gametest.framework.TestEnvironmentDefinition$Functions
+ XXX.gametest.framework.TestEnvironmentDefinition$SetGameRules
- XXX.gametest.framework.TestEnvironmentDefinition$SetGameRules$Entry
+ XXX.gametest.framework.TestEnvironmentDefinition$TimeOfDay
- XXX.gametest.framework.TestEnvironmentDefinition$Weather
+ XXX.gametest.framework.TestEnvironmentDefinition$Weather$Type
- XXX.gametest.framework.TestFinder
+ XXX.gametest.framework.TestFinder$Builder
- XXX.gametest.framework.TestFunctionLoader
+ XXX.gametest.framework.TestInstanceFinder
- XXX.gametest.framework.TestPosFinder
+ XXX.gametest.framework.TestReporter
- XXX.gametest.framework.UnknownGameTestException
+ XXX.gui.components.AbstractButton
- XXX.gui.components.AbstractContainerWidget
+ XXX.gui.components.AbstractOptionSliderButton
- XXX.gui.components.AbstractScrollArea
+ XXX.gui.components.AbstractSelectionList
- XXX.gui.components.AbstractSelectionList$1
+ XXX.gui.components.AbstractSelectionList$Entry
- XXX.gui.components.AbstractSelectionList$TrackedList
+ XXX.gui.components.AbstractSliderButton
- XXX.gui.components.AbstractStringWidget
+ XXX.gui.components.AbstractTextAreaWidget
- XXX.gui.components.AbstractWidget
+ XXX.gui.components.BossHealthOverlay
- XXX.gui.components.BossHealthOverlay$1
+ XXX.gui.components.Button
- XXX.gui.components.Button$Builder
+ XXX.gui.components.Button$CreateNarration
- XXX.gui.components.Button$OnPress
+ XXX.gui.components.ChatComponent
- XXX.gui.components.ChatComponent$ChatMethod
+ XXX.gui.components.ChatComponent$ChatMethod$1
- XXX.gui.components.ChatComponent$ChatMethod$2
+ XXX.gui.components.ChatComponent$DelayedMessageDeletion
- XXX.gui.components.ChatComponent$Draft
+ XXX.gui.components.ChatComponent$LineConsumer
- XXX.gui.components.ChatComponent$State
+ XXX.gui.components.Checkbox
- XXX.gui.components.Checkbox$Builder
+ XXX.gui.components.Checkbox$OnValueChange
- XXX.gui.components.CommandSuggestions
+ XXX.gui.components.CommandSuggestions$SuggestionsList
- XXX.gui.components.CommonButtons
+ XXX.gui.components.ComponentRenderUtils
- XXX.gui.components.ContainerObjectSelectionList
+ XXX.gui.components.ContainerObjectSelectionList$1
- XXX.gui.components.ContainerObjectSelectionList$Entry
+ XXX.gui.components.CycleButton
- XXX.gui.components.CycleButton$Builder
+ XXX.gui.components.CycleButton$OnValueChange
- XXX.gui.components.CycleButton$ValueListSupplier
+ XXX.gui.components.CycleButton$ValueListSupplier$1
- XXX.gui.components.CycleButton$ValueListSupplier$2
+ XXX.gui.components.DebugScreenOverlay
- XXX.gui.components.DebugScreenOverlay$1
+ XXX.gui.components.EditBox
- XXX.gui.components.EditBox$TextFormatter
+ XXX.gui.components.FittingMultiLineTextWidget
- XXX.gui.components.FocusableTextWidget
+ XXX.gui.components.FocusableTextWidget$BackgroundFill
- XXX.gui.components.ImageButton
+ XXX.gui.components.ImageWidget
- XXX.gui.components.ImageWidget$Sprite
+ XXX.gui.components.ImageWidget$Texture
- XXX.gui.components.ItemDisplayWidget
+ XXX.gui.components.LerpingBossEvent
- XXX.gui.components.LoadingDotsWidget
+ XXX.gui.components.LockIconButton
- XXX.gui.components.LockIconButton$Icon
+ XXX.gui.components.LogoRenderer
- XXX.gui.components.MultiLineEditBox
+ XXX.gui.components.MultiLineEditBox$Builder
- XXX.gui.components.MultiLineLabel
+ XXX.gui.components.MultiLineLabel$1
- XXX.gui.components.MultiLineLabel$2
+ XXX.gui.components.MultiLineLabel$Align
- XXX.gui.components.MultiLineLabel$Align$1
+ XXX.gui.components.MultiLineLabel$Align$2
- XXX.gui.components.MultiLineLabel$Align$3
+ XXX.gui.components.MultiLineLabel$TextAndWidth
- XXX.gui.components.MultilineTextField
+ XXX.gui.components.MultilineTextField$1
- XXX.gui.components.MultilineTextField$StringView
- XXX.gui.components.MultiLineTextWidget
+ XXX.gui.components.MultiLineTextWidget$CacheKey
+ XXX.gui.components.ObjectSelectionList
- XXX.gui.components.ObjectSelectionList$Entry
+ XXX.gui.components.OptionsList
- XXX.gui.components.OptionsList$Entry
+ XXX.gui.components.OptionsList$OptionEntry
- XXX.gui.components.package-info
- XXX.gui.components.PlainTextButton
+ XXX.gui.components.PlayerFaceRenderer
- XXX.gui.components.PlayerSkinWidget
+ XXX.gui.components.PlayerTabOverlay
- XXX.gui.components.PlayerTabOverlay$HealthState
+ XXX.gui.components.PlayerTabOverlay$ScoreDisplayEntry
- XXX.gui.components.PopupScreen
+ XXX.gui.components.PopupScreen$Builder
- XXX.gui.components.PopupScreen$ButtonOption
+ XXX.gui.components.Renderable
- XXX.gui.components.ScrollableLayout
+ XXX.gui.components.ScrollableLayout$Container
- XXX.gui.components.SplashRenderer
+ XXX.gui.components.SpriteIconButton
- XXX.gui.components.SpriteIconButton$Builder
+ XXX.gui.components.SpriteIconButton$CenteredIcon
- XXX.gui.components.SpriteIconButton$TextAndIcon
+ XXX.gui.components.StateSwitchingButton
- XXX.gui.components.StringWidget
+ XXX.gui.components.StringWidget$TextOverflow
- XXX.gui.components.SubtitleOverlay
+ XXX.gui.components.SubtitleOverlay$SoundPlayedAt
- XXX.gui.components.SubtitleOverlay$Subtitle
+ XXX.gui.components.TabButton
- XXX.gui.components.TabOrderedElement
+ XXX.gui.components.Tooltip
- XXX.gui.components.Whence
+ XXX.gui.components.WidgetSprites
- XXX.gui.components.WidgetTooltipHolder
+ XXX.gui.contextualbar.ContextualBarRenderer
- XXX.gui.contextualbar.ContextualBarRenderer$1
+ XXX.gui.contextualbar.ExperienceBarRenderer
- XXX.gui.contextualbar.JumpableVehicleBarRenderer
+ XXX.gui.contextualbar.LocatorBarRenderer
- XXX.gui.contextualbar.package-info
+ XXX.gui.font.AllMissingGlyphProvider
- XXX.gui.font.AllMissingGlyphProvider$1
+ XXX.gui.font.AtlasGlyphProvider
- XXX.gui.font.AtlasGlyphProvider$1
+ XXX.gui.font.AtlasGlyphProvider$Instance
- XXX.gui.font.CodepointMap
+ XXX.gui.font.CodepointMap$Output
- XXX.gui.font.FontManager
+ XXX.gui.font.FontManager$BuilderId
- XXX.gui.font.FontManager$BuilderResult
+ XXX.gui.font.FontManager$CachedFontProvider
- XXX.gui.font.FontManager$CachedFontProvider$CachedEntry
+ XXX.gui.font.FontManager$FontDefinitionFile
- XXX.gui.font.FontManager$Preparation
+ XXX.gui.font.FontManager$UnresolvedBuilderBundle
- XXX.gui.font.FontOption
+ XXX.gui.font.FontOption$Filter
- XXX.gui.font.FontSet
+ XXX.gui.font.FontSet$1
- XXX.gui.font.FontSet$2
+ XXX.gui.font.FontSet$DelayedBake
- XXX.gui.font.FontSet$SelectedGlyphs
+ XXX.gui.font.FontSet$Source
- XXX.gui.font.FontTexture
+ XXX.gui.font.FontTexture$Node
- XXX.gui.font.GlyphRenderTypes
+ XXX.gui.font.GlyphRenderTypes$1
- XXX.gui.font.GlyphStitcher
+ XXX.gui.font.package-info
+ XXX.gui.font.PlainTextRenderable
- XXX.gui.font.PlayerGlyphProvider
+ XXX.gui.font.PlayerGlyphProvider$1
- XXX.gui.font.PlayerGlyphProvider$1$1
+ XXX.gui.font.PlayerGlyphProvider$Instance
- XXX.gui.font.SingleSpriteSource
+ XXX.gui.font.TextFieldHelper
- XXX.gui.font.TextFieldHelper$CursorStep
+ XXX.gui.font.TextRenderable
- XXX.gui.layouts.AbstractLayout
+ XXX.gui.layouts.AbstractLayout$AbstractChildWrapper
- XXX.gui.layouts.CommonLayouts
+ XXX.gui.layouts.EqualSpacingLayout
- XXX.gui.layouts.EqualSpacingLayout$ChildContainer
+ XXX.gui.layouts.EqualSpacingLayout$Orientation
- XXX.gui.layouts.FrameLayout
+ XXX.gui.layouts.FrameLayout$ChildContainer
- XXX.gui.layouts.GridLayout
+ XXX.gui.layouts.GridLayout$CellInhabitant
- XXX.gui.layouts.GridLayout$RowHelper
+ XXX.gui.layouts.HeaderAndFooterLayout
- XXX.gui.layouts.Layout
+ XXX.gui.layouts.LayoutElement
- XXX.gui.layouts.LayoutSettings
+ XXX.gui.layouts.LayoutSettings$LayoutSettingsImpl
- XXX.gui.layouts.LinearLayout
+ XXX.gui.layouts.LinearLayout$Orientation
+ XXX.gui.layouts.package-info
- XXX.gui.layouts.SpacerElement
- XXX.gui.narration.NarratableEntry
+ XXX.gui.narration.NarratableEntry$NarrationPriority
- XXX.gui.narration.NarratedElementType
+ XXX.gui.narration.NarrationElementOutput
- XXX.gui.narration.NarrationSupplier
+ XXX.gui.narration.NarrationThunk
+ XXX.gui.narration.package-info
- XXX.gui.narration.ScreenNarrationCollector
+ XXX.gui.narration.ScreenNarrationCollector$1
- XXX.gui.narration.ScreenNarrationCollector$EntryKey
+ XXX.gui.narration.ScreenNarrationCollector$NarrationEntry
- XXX.gui.narration.ScreenNarrationCollector$Output
+ XXX.gui.screens.AddRealmPopupScreen
+ XXX.gui.screens.ErrorScreen
- XXX.gui.screens.FaviconTexture
+ XXX.gui.screens.GenericMessageScreen
- XXX.gui.screens.GenericWaitingScreen
+ XXX.gui.screens.InBedChatScreen
- XXX.gui.screens.LevelLoadingScreen
+ XXX.gui.screens.LevelLoadingScreen$Reason
- XXX.gui.screens.LoadingDotsText
+ XXX.gui.screens.LoadingOverlay
- XXX.gui.screens.LoadingOverlay$LogoTexture
+ XXX.gui.screens.package-info
- XXX.gui.screens.RealmsBrokenWorldScreen
+ XXX.gui.screens.RealmsClientOutdatedScreen
- XXX.gui.screens.RealmsConfirmScreen
+ XXX.gui.screens.RealmsCreateRealmScreen
- XXX.gui.screens.RealmsDownloadLatestWorldScreen
+ XXX.gui.screens.RealmsDownloadLatestWorldScreen$DownloadStatus
- XXX.gui.screens.RealmsGenericErrorScreen
+ XXX.gui.screens.RealmsGenericErrorScreen$ErrorMessage
- XXX.gui.screens.RealmsLongRunningMcoConnectTaskScreen
+ XXX.gui.screens.RealmsLongRunningMcoTaskScreen
- XXX.gui.screens.RealmsNotificationsScreen
+ XXX.gui.screens.RealmsNotificationsScreen$1
- XXX.gui.screens.RealmsNotificationsScreen$2
+ XXX.gui.screens.RealmsNotificationsScreen$DataFetcherConfiguration
- XXX.gui.screens.RealmsParentalConsentScreen
+ XXX.gui.screens.RealmsPendingInvitesScreen
- XXX.gui.screens.RealmsPendingInvitesScreen$Entry
+ XXX.gui.screens.RealmsPendingInvitesScreen$PendingInvitationSelectionList
- XXX.gui.screens.RealmsPopups
+ XXX.gui.screens.RealmsResetWorldScreen
- XXX.gui.screens.RealmsResetWorldScreen$1
+ XXX.gui.screens.RealmsResetWorldScreen$FrameButton
- XXX.gui.screens.RealmsSelectFileToUploadScreen
+ XXX.gui.screens.RealmsSelectWorldTemplateScreen
- XXX.gui.screens.RealmsSelectWorldTemplateScreen$1
+ XXX.gui.screens.RealmsSelectWorldTemplateScreen$Entry
- XXX.gui.screens.RealmsSelectWorldTemplateScreen$WorldTemplateList
+ XXX.gui.screens.RealmsTermsScreen
- XXX.gui.screens.RealmsUploadScreen
+ XXX.gui.screens.UploadResult
- XXX.gui.screens.UploadResult$Builder
- XXX.gui.task.DataFetcher
+ XXX.gui.task.DataFetcher$ComputationResult
- XXX.gui.task.DataFetcher$SubscribedTask
+ XXX.gui.task.DataFetcher$Subscription
- XXX.gui.task.DataFetcher$SuccessfulComputationResult
+ XXX.gui.task.DataFetcher$Task
+ XXX.gui.task.package-info
- XXX.gui.task.RepeatedDelayStrategy
+ XXX.gui.task.RepeatedDelayStrategy$1
- XXX.gui.task.RepeatedDelayStrategy$2
+ XXX.inventory.tooltip.BundleTooltip
+ XXX.inventory.tooltip.package-info
- XXX.inventory.tooltip.TooltipComponent
+ XXX.item.alchemy.package-info
+ XXX.item.alchemy.Potion
- XXX.item.alchemy.PotionBrewing
+ XXX.item.alchemy.PotionBrewing$Builder
- XXX.item.alchemy.PotionBrewing$Mix
+ XXX.item.alchemy.PotionContents
- XXX.item.alchemy.Potions
- XXX.item.component.Bees
+ XXX.item.component.BlockItemStateProperties
- XXX.item.component.BlocksAttacks
+ XXX.item.component.BlocksAttacks$DamageReduction
- XXX.item.component.BlocksAttacks$ItemDamageFunction
+ XXX.item.component.BookContent
- XXX.item.component.BundleContents
+ XXX.item.component.BundleContents$Mutable
- XXX.item.component.ChargedProjectiles
+ XXX.item.component.Consumable
- XXX.item.component.Consumable$Builder
+ XXX.item.component.Consumable$OverrideConsumeSound
- XXX.item.component.ConsumableListener
+ XXX.item.component.Consumables
- XXX.item.component.CustomData
+ XXX.item.component.CustomModelData
- XXX.item.component.DamageResistant
+ XXX.item.component.DeathProtection
- XXX.item.component.DebugStickState
+ XXX.item.component.DyedItemColor
- XXX.item.component.FireworkExplosion
+ XXX.item.component.FireworkExplosion$Shape
- XXX.item.component.Fireworks
+ XXX.item.component.InstrumentComponent
- XXX.item.component.ItemAttributeModifiers
+ XXX.item.component.ItemAttributeModifiers$1
- XXX.item.component.ItemAttributeModifiers$Builder
+ XXX.item.component.ItemAttributeModifiers$Display
- XXX.item.component.ItemAttributeModifiers$Display$Default
+ XXX.item.component.ItemAttributeModifiers$Display$Hidden
- XXX.item.component.ItemAttributeModifiers$Display$OverrideText
+ XXX.item.component.ItemAttributeModifiers$Display$Type
- XXX.item.component.ItemAttributeModifiers$Entry
+ XXX.item.component.ItemContainerContents
- XXX.item.component.ItemContainerContents$Slot
+ XXX.item.component.ItemLore
- XXX.item.component.LodestoneTracker
+ XXX.item.component.MapDecorations
- XXX.item.component.MapDecorations$Entry
+ XXX.item.component.MapItemColor
- XXX.item.component.MapPostProcessing
+ XXX.item.component.OminousBottleAmplifier
- XXX.item.component.package-info
- XXX.item.component.ProvidesTrimMaterial
+ XXX.item.component.ResolvableProfile
- XXX.item.component.ResolvableProfile$Dynamic
+ XXX.item.component.ResolvableProfile$Partial
- XXX.item.component.ResolvableProfile$Static
+ XXX.item.component.SeededContainerLoot
- XXX.item.component.SuspiciousStewEffects
+ XXX.item.component.SuspiciousStewEffects$Entry
- XXX.item.component.Tool
+ XXX.item.component.Tool$Rule
- XXX.item.component.TooltipDisplay
+ XXX.item.component.TooltipProvider
- XXX.item.component.TypedEntityData
+ XXX.item.component.TypedEntityData$1
- XXX.item.component.UseCooldown
+ XXX.item.component.UseRemainder
- XXX.item.component.UseRemainder$OnExtraCreatedRemainder
+ XXX.item.component.Weapon
- XXX.item.component.WritableBookContent
+ XXX.item.component.WrittenBookContent
+ XXX.item.consume_effects.ApplyStatusEffectsConsumeEffect
- XXX.item.consume_effects.ClearAllStatusEffectsConsumeEffect
+ XXX.item.consume_effects.ConsumeEffect
- XXX.item.consume_effects.ConsumeEffect$Type
- XXX.item.consume_effects.package-info
+ XXX.item.consume_effects.PlaySoundConsumeEffect
- XXX.item.consume_effects.RemoveStatusEffectsConsumeEffect
+ XXX.item.consume_effects.TeleportRandomlyConsumeEffect
+ XXX.item.context.BlockPlaceContext
- XXX.item.context.DirectionalPlaceContext
+ XXX.item.context.DirectionalPlaceContext$1
+ XXX.item.context.package-info
- XXX.item.context.UseOnContext
- XXX.item.crafting.AbstractCookingRecipe
+ XXX.item.crafting.AbstractCookingRecipe$Factory
- XXX.item.crafting.AbstractCookingRecipe$Serializer
+ XXX.item.crafting.ArmorDyeRecipe
- XXX.item.crafting.BannerDuplicateRecipe
+ XXX.item.crafting.BlastingRecipe
- XXX.item.crafting.BlastingRecipe$1
+ XXX.item.crafting.BookCloningRecipe
- XXX.item.crafting.CampfireCookingRecipe
+ XXX.item.crafting.CookingBookCategory
- XXX.item.crafting.CraftingBookCategory
+ XXX.item.crafting.CraftingInput
- XXX.item.crafting.CraftingInput$Positioned
+ XXX.item.crafting.CraftingRecipe
- XXX.item.crafting.CraftingRecipe$1
+ XXX.item.crafting.CustomRecipe
- XXX.item.crafting.CustomRecipe$Serializer
+ XXX.item.crafting.CustomRecipe$Serializer$Factory
- XXX.item.crafting.DecoratedPotRecipe
+ XXX.item.crafting.ExtendedRecipeBookCategory
- XXX.item.crafting.FireworkRocketRecipe
+ XXX.item.crafting.FireworkStarFadeRecipe
- XXX.item.crafting.FireworkStarRecipe
+ XXX.item.crafting.Ingredient
- XXX.item.crafting.MapCloningRecipe
+ XXX.item.crafting.MapExtendingRecipe
- XXX.item.crafting.package-info
- XXX.item.crafting.PlacementInfo
+ XXX.item.crafting.Recipe
- XXX.item.crafting.RecipeAccess
+ XXX.item.crafting.RecipeBookCategories
- XXX.item.crafting.RecipeBookCategory
+ XXX.item.crafting.RecipeCache
- XXX.item.crafting.RecipeCache$Entry
+ XXX.item.crafting.RecipeHolder
- XXX.item.crafting.RecipeInput
+ XXX.item.crafting.RecipeManager
- XXX.item.crafting.RecipeManager$1
+ XXX.item.crafting.RecipeManager$CachedCheck
- XXX.item.crafting.RecipeManager$IngredientCollector
+ XXX.item.crafting.RecipeManager$IngredientExtractor
- XXX.item.crafting.RecipeManager$ServerDisplayInfo
+ XXX.item.crafting.RecipeMap
- XXX.item.crafting.RecipePropertySet
+ XXX.item.crafting.RecipeSerializer
- XXX.item.crafting.RecipeType
+ XXX.item.crafting.RecipeType$1
- XXX.item.crafting.RepairItemRecipe
+ XXX.item.crafting.SelectableRecipe
- XXX.item.crafting.SelectableRecipe$SingleInputEntry
+ XXX.item.crafting.SelectableRecipe$SingleInputSet
- XXX.item.crafting.ShapedRecipe
+ XXX.item.crafting.ShapedRecipe$Serializer
- XXX.item.crafting.ShapedRecipePattern
+ XXX.item.crafting.ShapedRecipePattern$Data
- XXX.item.crafting.ShapelessRecipe
+ XXX.item.crafting.ShapelessRecipe$Serializer
- XXX.item.crafting.ShieldDecorationRecipe
+ XXX.item.crafting.SingleItemRecipe
- XXX.item.crafting.SingleItemRecipe$Factory
+ XXX.item.crafting.SingleItemRecipe$Serializer
- XXX.item.crafting.SingleRecipeInput
+ XXX.item.crafting.SmeltingRecipe
- XXX.item.crafting.SmeltingRecipe$1
+ XXX.item.crafting.SmithingRecipe
- XXX.item.crafting.SmithingRecipeInput
+ XXX.item.crafting.SmithingTransformRecipe
- XXX.item.crafting.SmithingTransformRecipe$Serializer
+ XXX.item.crafting.SmithingTrimRecipe
- XXX.item.crafting.SmithingTrimRecipe$Serializer
+ XXX.item.crafting.SmokingRecipe
- XXX.item.crafting.StonecutterRecipe
+ XXX.item.crafting.TippedArrowRecipe
- XXX.item.crafting.TransmuteRecipe
+ XXX.item.crafting.TransmuteRecipe$Serializer
- XXX.item.crafting.TransmuteResult
+ XXX.item.enchantment.ConditionalEffect
- XXX.item.enchantment.Enchantable
+ XXX.item.enchantment.EnchantedItemInUse
- XXX.item.enchantment.Enchantment
+ XXX.item.enchantment.Enchantment$1
- XXX.item.enchantment.Enchantment$Builder
+ XXX.item.enchantment.Enchantment$Cost
- XXX.item.enchantment.Enchantment$EnchantmentDefinition
+ XXX.item.enchantment.EnchantmentEffectComponents
- XXX.item.enchantment.EnchantmentHelper
+ XXX.item.enchantment.EnchantmentHelper$EnchantmentInSlotVisitor
- XXX.item.enchantment.EnchantmentHelper$EnchantmentVisitor
+ XXX.item.enchantment.EnchantmentInstance
+ XXX.item.enchantment.Enchantments
- XXX.item.enchantment.EnchantmentTarget
- XXX.item.enchantment.ItemEnchantments
+ XXX.item.enchantment.ItemEnchantments$Mutable
- XXX.item.enchantment.LevelBasedValue
+ XXX.item.enchantment.LevelBasedValue$Clamped
- XXX.item.enchantment.LevelBasedValue$Constant
+ XXX.item.enchantment.LevelBasedValue$Fraction
- XXX.item.enchantment.LevelBasedValue$LevelsSquared
+ XXX.item.enchantment.LevelBasedValue$Linear
- XXX.item.enchantment.LevelBasedValue$Lookup
+ XXX.item.enchantment.package-info
+ XXX.item.enchantment.Repairable
- XXX.item.enchantment.TargetedConditionalEffect
- XXX.item.equipment.AllowedEntitiesProvider
+ XXX.item.equipment.ArmorMaterial
- XXX.item.equipment.ArmorMaterials
+ XXX.item.equipment.ArmorType
- XXX.item.equipment.EquipmentAsset
+ XXX.item.equipment.EquipmentAssets
- XXX.item.equipment.Equippable
+ XXX.item.equipment.Equippable$Builder
- XXX.item.equipment.package-info
- XXX.item.trading.ItemCost
+ XXX.item.trading.Merchant
- XXX.item.trading.MerchantOffer
+ XXX.item.trading.MerchantOffers
- XXX.item.trading.package-info
+ XXX.jfr.callback.package-info
- XXX.jfr.callback.ProfiledDuration
- XXX.jfr.event.ChunkGenerationEvent
+ XXX.jfr.event.ChunkGenerationEvent$Fields
- XXX.jfr.event.ChunkRegionIoEvent
+ XXX.jfr.event.ChunkRegionIoEvent$Fields
- XXX.jfr.event.ChunkRegionReadEvent
+ XXX.jfr.event.ChunkRegionWriteEvent
- XXX.jfr.event.NetworkSummaryEvent
+ XXX.jfr.event.NetworkSummaryEvent$Fields
- XXX.jfr.event.NetworkSummaryEvent$SumAggregation
- XXX.jfr.event.package-info
+ XXX.jfr.event.PacketEvent
- XXX.jfr.event.PacketEvent$Fields
+ XXX.jfr.event.PacketReceivedEvent
- XXX.jfr.event.PacketSentEvent
+ XXX.jfr.event.ServerTickTimeEvent
- XXX.jfr.event.ServerTickTimeEvent$Fields
+ XXX.jfr.event.StructureGenerationEvent
- XXX.jfr.event.StructureGenerationEvent$Fields
+ XXX.jfr.event.WorldLoadFinishedEvent
- XXX.jfr.parse.JfrStatsParser
+ XXX.jfr.parse.JfrStatsParser$1
- XXX.jfr.parse.JfrStatsParser$MutableCountAndSize
+ XXX.jfr.parse.JfrStatsResult
- XXX.jfr.parse.package-info
+ XXX.jfr.serialize.JfrResultJsonSerializer
- XXX.jfr.serialize.package-info
+ XXX.jfr.stats.ChunkGenStat
- XXX.jfr.stats.ChunkIdentification
+ XXX.jfr.stats.CpuLoadStat
- XXX.jfr.stats.FileIOStat
+ XXX.jfr.stats.FileIOStat$Summary
- XXX.jfr.stats.GcHeapStat
+ XXX.jfr.stats.GcHeapStat$Summary
- XXX.jfr.stats.GcHeapStat$Timing
+ XXX.jfr.stats.IoSummary
- XXX.jfr.stats.IoSummary$CountAndSize
- XXX.jfr.stats.package-info
+ XXX.jfr.stats.PacketIdentification
- XXX.jfr.stats.StructureGenStat
+ XXX.jfr.stats.ThreadAllocationStat
- XXX.jfr.stats.ThreadAllocationStat$Summary
+ XXX.jfr.stats.TickTimeStat
- XXX.jfr.stats.TimedStat
+ XXX.jfr.stats.TimedStatSummary
+ XXX.level.border.BorderStatus
- XXX.level.border.package-info
- XXX.level.border.WorldBorder
+ XXX.level.border.WorldBorder$BorderExtent
- XXX.level.border.WorldBorder$DistancePerDirection
+ XXX.level.border.WorldBorder$MovingBorderExtent
- XXX.level.border.WorldBorder$Settings
+ XXX.level.border.WorldBorder$StaticBorderExtent
+ XXX.level.chunk.BlockColumn
- XXX.level.chunk.BulkSectionAccess
+ XXX.level.chunk.CarvingMask
- XXX.level.chunk.CarvingMask$Mask
+ XXX.level.chunk.ChunkAccess
- XXX.level.chunk.ChunkAccess$ChunkPathElement
+ XXX.level.chunk.ChunkAccess$PackedTicks
- XXX.level.chunk.ChunkGenerator
- XXX.level.chunk.ChunkGenerators
+ XXX.level.chunk.ChunkGeneratorStructureState
+ XXX.level.chunk.ChunkSource
- XXX.level.chunk.Configuration
- XXX.level.chunk.Configuration$Simple
+ XXX.level.chunk.PalettedContainer$CountConsumer
- XXX.level.chunk.PalettedContainer$Data
+ XXX.level.chunk.PalettedContainer$Strategy
+ XXX.level.chunk.PalettedContainer$Strategy$2
- XXX.level.chunk.PalettedContainerRO
+ XXX.level.chunk.PalettedContainerRO$PackedData
- XXX.level.chunk.PalettedContainerRO$Unpacker
+ XXX.level.chunk.ProtoChunk
- XXX.level.chunk.SingleValuePalette
- XXX.level.chunk.Strategy$1
- XXX.login.custom.CustomQueryAnswerPayload
+ XXX.login.custom.CustomQueryPayload
- XXX.login.custom.DiscardedQueryAnswerPayload
+ XXX.login.custom.DiscardedQueryPayload
- XXX.login.custom.package-info
+ XXX.loot.packs.LootData
- XXX.loot.packs.package-info
- XXX.loot.packs.TradeRebalanceChestLoot
+ XXX.loot.packs.TradeRebalanceLootTableProvider
- XXX.loot.packs.VanillaArchaeologyLoot
+ XXX.loot.packs.VanillaBlockInteractLoot
- XXX.loot.packs.VanillaBlockLoot
+ XXX.loot.packs.VanillaChargedCreeperExplosionLoot
- XXX.loot.packs.VanillaChargedCreeperExplosionLoot$Entry
+ XXX.loot.packs.VanillaChestLoot
- XXX.loot.packs.VanillaEntityInteractLoot
+ XXX.loot.packs.VanillaEntityLoot
- XXX.loot.packs.VanillaEquipmentLoot
+ XXX.loot.packs.VanillaFishingLoot
- XXX.loot.packs.VanillaGiftLoot
+ XXX.loot.packs.VanillaLootTableProvider
- XXX.loot.packs.VanillaPiglinBarterLoot
+ XXX.loot.packs.VanillaShearingLoot
+ XXX.metadata.animation.AnimationFrame
- XXX.metadata.animation.AnimationMetadataSection
+ XXX.metadata.animation.FrameSize
- XXX.metadata.animation.package-info
- XXX.metadata.animation.VillagerMetadataSection
+ XXX.metadata.animation.VillagerMetadataSection$Hat
+ XXX.metadata.gui.GuiMetadataSection
- XXX.metadata.gui.GuiSpriteScaling
+ XXX.metadata.gui.GuiSpriteScaling$NineSlice
- XXX.metadata.gui.GuiSpriteScaling$NineSlice$Border
+ XXX.metadata.gui.GuiSpriteScaling$Stretch
- XXX.metadata.gui.GuiSpriteScaling$Tile
+ XXX.metadata.gui.GuiSpriteScaling$Type
- XXX.metadata.gui.package-info
+ XXX.metadata.language.LanguageMetadataSection
- XXX.metadata.language.package-info
+ XXX.metadata.texture.package-info
- XXX.metadata.texture.TextureMetadataSection
- XXX.metrics.profiling.ActiveMetricsRecorder
+ XXX.metrics.profiling.InactiveMetricsRecorder
- XXX.metrics.profiling.MetricsRecorder
+ XXX.metrics.profiling.package-info
+ XXX.metrics.profiling.ProfilerSamplerAdapter
- XXX.metrics.profiling.ServerMetricsSamplersProvider
+ XXX.metrics.profiling.ServerMetricsSamplersProvider$1
- XXX.metrics.profiling.ServerMetricsSamplersProvider$CpuStats
- XXX.metrics.storage.MetricsPersister
- XXX.metrics.storage.package-info
+ XXX.metrics.storage.RecordedDeviation
+ XXX.minecraft.advancements.Advancement
- XXX.minecraft.advancements.Advancement$Builder
+ XXX.minecraft.advancements.AdvancementHolder
- XXX.minecraft.advancements.AdvancementNode
+ XXX.minecraft.advancements.AdvancementProgress
- XXX.minecraft.advancements.AdvancementRequirements
+ XXX.minecraft.advancements.AdvancementRequirements$Strategy
- XXX.minecraft.advancements.AdvancementRewards
+ XXX.minecraft.advancements.AdvancementRewards$Builder
- XXX.minecraft.advancements.AdvancementTree
+ XXX.minecraft.advancements.AdvancementTree$Listener
- XXX.minecraft.advancements.AdvancementType
+ XXX.minecraft.advancements.CriteriaTriggers
- XXX.minecraft.advancements.Criterion
+ XXX.minecraft.advancements.CriterionProgress
- XXX.minecraft.advancements.CriterionTrigger
+ XXX.minecraft.advancements.CriterionTrigger$Listener
- XXX.minecraft.advancements.CriterionTriggerInstance
+ XXX.minecraft.advancements.DisplayInfo
- XXX.minecraft.advancements.TreeNodePosition
- XXX.minecraft.client.KeyboardHandler
+ XXX.minecraft.client.KeyboardHandler$1
- XXX.minecraft.client.Minecraft
+ XXX.minecraft.client.Minecraft$1
- XXX.minecraft.client.Minecraft$2
+ XXX.minecraft.client.Minecraft$ChatStatus
- XXX.minecraft.client.Minecraft$ChatStatus$1
+ XXX.minecraft.client.Minecraft$ChatStatus$2
- XXX.minecraft.client.Minecraft$ChatStatus$3
+ XXX.minecraft.client.Minecraft$ChatStatus$4
- XXX.minecraft.client.Minecraft$GameLoadCookie
+ XXX.minecraft.client.MouseHandler
- XXX.minecraft.client.NarratorStatus
+ XXX.minecraft.client.OptionInstance
- XXX.minecraft.client.OptionInstance$AltEnum
+ XXX.minecraft.client.OptionInstance$CaptionBasedToString
- XXX.minecraft.client.OptionInstance$ClampingLazyMaxIntRange
+ XXX.minecraft.client.OptionInstance$CycleableValueSet
- XXX.minecraft.client.OptionInstance$CycleableValueSet$ValueSetter
+ XXX.minecraft.client.OptionInstance$Enum
- XXX.minecraft.client.OptionInstance$IntRange
+ XXX.minecraft.client.OptionInstance$IntRangeBase
- XXX.minecraft.client.OptionInstance$IntRangeBase$1
+ XXX.minecraft.client.OptionInstance$LazyEnum
- XXX.minecraft.client.OptionInstance$OptionInstanceSliderButton
+ XXX.minecraft.client.OptionInstance$SliderableOrCyclableValueSet
- XXX.minecraft.client.OptionInstance$SliderableValueSet
+ XXX.minecraft.client.OptionInstance$TooltipSupplier
- XXX.minecraft.client.OptionInstance$UnitDouble
+ XXX.minecraft.client.OptionInstance$UnitDouble$1
- XXX.minecraft.client.OptionInstance$ValueSet
+ XXX.minecraft.client.Options
- XXX.minecraft.client.Options$1
+ XXX.minecraft.client.Options$2
- XXX.minecraft.client.Options$3
+ XXX.minecraft.client.Options$4
- XXX.minecraft.client.Options$5
+ XXX.minecraft.client.Options$FieldAccess
- XXX.minecraft.client.Options$OptionAccess
+ XXX.minecraft.client.PeriodicNotificationManager
- XXX.minecraft.client.PeriodicNotificationManager$Notification
+ XXX.minecraft.client.PeriodicNotificationManager$NotificationTask
- XXX.minecraft.client.PrioritizeChunkUpdates
+ XXX.minecraft.client.ResourceLoadStateTracker
- XXX.minecraft.client.ResourceLoadStateTracker$RecoveryInfo
+ XXX.minecraft.client.ResourceLoadStateTracker$ReloadReason
- XXX.minecraft.client.ResourceLoadStateTracker$ReloadState
+ XXX.minecraft.client.Screenshot
- XXX.minecraft.client.ScrollWheelHandler
+ XXX.minecraft.client.StringSplitter
- XXX.minecraft.client.StringSplitter$1
+ XXX.minecraft.client.StringSplitter$FlatComponents
- XXX.minecraft.client.StringSplitter$LineBreakFinder
+ XXX.minecraft.client.StringSplitter$LineComponent
- XXX.minecraft.client.StringSplitter$LinePosConsumer
+ XXX.minecraft.client.StringSplitter$WidthLimitedCharSink
- XXX.minecraft.client.StringSplitter$WidthProvider
+ XXX.minecraft.client.ToggleKeyMapping
- XXX.minecraft.client.User
- XXX.minecraft.commands.BrigadierExceptions
+ XXX.minecraft.commands.CacheableFunction
- XXX.minecraft.commands.CommandBuildContext
+ XXX.minecraft.commands.CommandBuildContext$1
- XXX.minecraft.commands.CommandResultCallback
+ XXX.minecraft.commands.CommandResultCallback$1
- XXX.minecraft.commands.Commands
+ XXX.minecraft.commands.Commands$1
- XXX.minecraft.commands.Commands$2
+ XXX.minecraft.commands.Commands$2$1
- XXX.minecraft.commands.Commands$CommandSelection
+ XXX.minecraft.commands.Commands$ParseFunction
- XXX.minecraft.commands.CommandSigningContext
+ XXX.minecraft.commands.CommandSigningContext$1
- XXX.minecraft.commands.CommandSigningContext$SignedArguments
+ XXX.minecraft.commands.CommandSource
- XXX.minecraft.commands.CommandSource$1
+ XXX.minecraft.commands.CommandSourceStack
- XXX.minecraft.commands.ExecutionCommandSource
+ XXX.minecraft.commands.FunctionInstantiationException
+ XXX.minecraft.commands.package-info
- XXX.minecraft.commands.ParserUtils
+ XXX.minecraft.commands.PermissionSource
- XXX.minecraft.commands.PermissionSource$Check
+ XXX.minecraft.commands.SharedSuggestionProvider
- XXX.minecraft.commands.SharedSuggestionProvider$ElementSuggestionType
+ XXX.minecraft.commands.SharedSuggestionProvider$TextCoordinates
+ XXX.minecraft.core.AxisCycle
- XXX.minecraft.core.AxisCycle$1
+ XXX.minecraft.core.AxisCycle$2
- XXX.minecraft.core.AxisCycle$3
+ XXX.minecraft.core.BlockBox
- XXX.minecraft.core.BlockBox$1
+ XXX.minecraft.core.BlockMath
- XXX.minecraft.core.BlockPos
+ XXX.minecraft.core.BlockPos$1
- XXX.minecraft.core.BlockPos$2
+ XXX.minecraft.core.BlockPos$3
- XXX.minecraft.core.BlockPos$4
+ XXX.minecraft.core.BlockPos$5
- XXX.minecraft.core.BlockPos$6
+ XXX.minecraft.core.BlockPos$7
- XXX.minecraft.core.BlockPos$MutableBlockPos
+ XXX.minecraft.core.BlockPos$TraversalNodeStatus
- XXX.minecraft.core.ClientAsset
+ XXX.minecraft.core.Cloner
- XXX.minecraft.core.Cloner$Factory
+ XXX.minecraft.core.Cursor3D
- XXX.minecraft.core.DefaultedMappedRegistry
+ XXX.minecraft.core.DefaultedRegistry
- XXX.minecraft.core.Direction
+ XXX.minecraft.core.Direction$Axis
- XXX.minecraft.core.Direction$Axis$1
+ XXX.minecraft.core.Direction$Axis$2
- XXX.minecraft.core.Direction$Axis$3
+ XXX.minecraft.core.Direction$AxisDirection
- XXX.minecraft.core.Direction$Plane
+ XXX.minecraft.core.Direction8
- XXX.minecraft.core.FrontAndTop
+ XXX.minecraft.core.GlobalPos
- XXX.minecraft.core.Holder
+ XXX.minecraft.core.Holder$Direct
- XXX.minecraft.core.Holder$Kind
+ XXX.minecraft.core.Holder$Reference
- XXX.minecraft.core.Holder$Reference$Type
+ XXX.minecraft.core.HolderGetter
- XXX.minecraft.core.HolderGetter$Provider
+ XXX.minecraft.core.HolderLookup
- XXX.minecraft.core.HolderLookup$Provider
+ XXX.minecraft.core.HolderLookup$Provider$1
- XXX.minecraft.core.HolderLookup$RegistryLookup
+ XXX.minecraft.core.HolderLookup$RegistryLookup$1
- XXX.minecraft.core.HolderLookup$RegistryLookup$Delegate
+ XXX.minecraft.core.HolderOwner
- XXX.minecraft.core.HolderSet
+ XXX.minecraft.core.HolderSet$1
- XXX.minecraft.core.HolderSet$Direct
+ XXX.minecraft.core.HolderSet$ListBacked
- XXX.minecraft.core.HolderSet$Named
+ XXX.minecraft.core.IdMap
- XXX.minecraft.core.IdMapper
+ XXX.minecraft.core.LayeredRegistryAccess
- XXX.minecraft.core.MappedRegistry
+ XXX.minecraft.core.MappedRegistry$1
- XXX.minecraft.core.MappedRegistry$2
+ XXX.minecraft.core.MappedRegistry$3
- XXX.minecraft.core.MappedRegistry$TagSet
+ XXX.minecraft.core.MappedRegistry$TagSet$1
- XXX.minecraft.core.MappedRegistry$TagSet$2
+ XXX.minecraft.core.NonNullList
- XXX.minecraft.core.package-info
- XXX.minecraft.core.Position
+ XXX.minecraft.core.QuartPos
- XXX.minecraft.core.RegistrationInfo
+ XXX.minecraft.core.Registry
- XXX.minecraft.core.Registry$1
+ XXX.minecraft.core.Registry$PendingTags
- XXX.minecraft.core.RegistryAccess
+ XXX.minecraft.core.RegistryAccess$1
- XXX.minecraft.core.RegistryAccess$1FrozenAccess
+ XXX.minecraft.core.RegistryAccess$Frozen
- XXX.minecraft.core.RegistryAccess$ImmutableRegistryAccess
+ XXX.minecraft.core.RegistryAccess$RegistryEntry
- XXX.minecraft.core.RegistryCodecs
+ XXX.minecraft.core.RegistrySetBuilder
- XXX.minecraft.core.RegistrySetBuilder$1
+ XXX.minecraft.core.RegistrySetBuilder$1Entry
- XXX.minecraft.core.RegistrySetBuilder$2
+ XXX.minecraft.core.RegistrySetBuilder$3
- XXX.minecraft.core.RegistrySetBuilder$3$1
+ XXX.minecraft.core.RegistrySetBuilder$BuildState
- XXX.minecraft.core.RegistrySetBuilder$BuildState$1
+ XXX.minecraft.core.RegistrySetBuilder$EmptyTagLookup
- XXX.minecraft.core.RegistrySetBuilder$EmptyTagLookupWrapper
+ XXX.minecraft.core.RegistrySetBuilder$EmptyTagRegistryLookup
- XXX.minecraft.core.RegistrySetBuilder$LazyHolder
+ XXX.minecraft.core.RegistrySetBuilder$PatchedRegistries
- XXX.minecraft.core.RegistrySetBuilder$RegisteredValue
+ XXX.minecraft.core.RegistrySetBuilder$RegistryBootstrap
- XXX.minecraft.core.RegistrySetBuilder$RegistryContents
+ XXX.minecraft.core.RegistrySetBuilder$RegistryStub
- XXX.minecraft.core.RegistrySetBuilder$UniversalLookup
+ XXX.minecraft.core.RegistrySetBuilder$UniversalOwner
- XXX.minecraft.core.RegistrySetBuilder$ValueAndHolder
+ XXX.minecraft.core.RegistrySynchronization
- XXX.minecraft.core.RegistrySynchronization$PackedRegistryEntry
+ XXX.minecraft.core.Rotations
- XXX.minecraft.core.Rotations$1
+ XXX.minecraft.core.SectionPos
- XXX.minecraft.core.SectionPos$1
+ XXX.minecraft.core.UUIDUtil
- XXX.minecraft.core.UUIDUtil$1
+ XXX.minecraft.core.Vec3i
- XXX.minecraft.core.WritableRegistry
+ XXX.minecraft.data.AtlasIds
- XXX.minecraft.data.BlockFamilies
+ XXX.minecraft.data.BlockFamily
- XXX.minecraft.data.BlockFamily$Builder
+ XXX.minecraft.data.BlockFamily$Variant
- XXX.minecraft.data.CachedOutput
+ XXX.minecraft.data.DataGenerator
- XXX.minecraft.data.DataGenerator$PackGenerator
+ XXX.minecraft.data.DataProvider
- XXX.minecraft.data.DataProvider$Factory
+ XXX.minecraft.data.HashCache
- XXX.minecraft.data.HashCache$1
+ XXX.minecraft.data.HashCache$CacheUpdater
- XXX.minecraft.data.HashCache$ProviderCache
+ XXX.minecraft.data.HashCache$ProviderCacheBuilder
- XXX.minecraft.data.HashCache$UpdateFunction
+ XXX.minecraft.data.HashCache$UpdateResult
- XXX.minecraft.data.Main
+ XXX.minecraft.data.package-info
+ XXX.minecraft.data.PackOutput
- XXX.minecraft.data.PackOutput$PathProvider
+ XXX.minecraft.data.PackOutput$Target
+ XXX.minecraft.gametest.Main
- XXX.minecraft.gametest.package-info
+ XXX.minecraft.locale.DeprecatedTranslationsInfo
- XXX.minecraft.locale.Language
+ XXX.minecraft.locale.Language$1
- XXX.minecraft.locale.package-info
+ XXX.minecraft.nbt.ByteArrayTag
- XXX.minecraft.nbt.ByteArrayTag$1
+ XXX.minecraft.nbt.ByteTag
- XXX.minecraft.nbt.ByteTag$1
+ XXX.minecraft.nbt.ByteTag$Cache
- XXX.minecraft.nbt.CollectionTag
+ XXX.minecraft.nbt.CollectionTag$1
- XXX.minecraft.nbt.CompoundTag
+ XXX.minecraft.nbt.CompoundTag$1
- XXX.minecraft.nbt.CompoundTag$2
+ XXX.minecraft.nbt.DoubleTag
- XXX.minecraft.nbt.DoubleTag$1
+ XXX.minecraft.nbt.EndTag
- XXX.minecraft.nbt.EndTag$1
+ XXX.minecraft.nbt.FloatTag
- XXX.minecraft.nbt.FloatTag$1
+ XXX.minecraft.nbt.IntArrayTag
- XXX.minecraft.nbt.IntArrayTag$1
+ XXX.minecraft.nbt.IntTag
- XXX.minecraft.nbt.IntTag$1
+ XXX.minecraft.nbt.IntTag$Cache
- XXX.minecraft.nbt.ListTag
+ XXX.minecraft.nbt.ListTag$1
- XXX.minecraft.nbt.ListTag$2
+ XXX.minecraft.nbt.LongArrayTag
- XXX.minecraft.nbt.LongArrayTag$1
+ XXX.minecraft.nbt.LongTag
- XXX.minecraft.nbt.LongTag$1
+ XXX.minecraft.nbt.LongTag$Cache
- XXX.minecraft.nbt.NbtAccounter
+ XXX.minecraft.nbt.NbtAccounterException
- XXX.minecraft.nbt.NbtException
+ XXX.minecraft.nbt.NbtFormatException
- XXX.minecraft.nbt.NbtIo
+ XXX.minecraft.nbt.NbtIo$1
- XXX.minecraft.nbt.NbtIo$StringFallbackDataOutput
+ XXX.minecraft.nbt.NbtOps
- XXX.minecraft.nbt.NbtOps$1
+ XXX.minecraft.nbt.NbtOps$ByteListCollector
- XXX.minecraft.nbt.NbtOps$GenericListCollector
+ XXX.minecraft.nbt.NbtOps$IntListCollector
- XXX.minecraft.nbt.NbtOps$ListCollector
+ XXX.minecraft.nbt.NbtOps$LongListCollector
- XXX.minecraft.nbt.NbtOps$NbtRecordBuilder
+ XXX.minecraft.nbt.NbtUtils
- XXX.minecraft.nbt.NumericTag
+ XXX.minecraft.nbt.package-info
+ XXX.minecraft.nbt.PrimitiveTag
- XXX.minecraft.nbt.ReportedNbtException
+ XXX.minecraft.nbt.ShortTag
- XXX.minecraft.nbt.ShortTag$1
+ XXX.minecraft.nbt.ShortTag$Cache
- XXX.minecraft.nbt.SnbtGrammar
+ XXX.minecraft.nbt.SnbtGrammar$1
- XXX.minecraft.nbt.SnbtGrammar$2
+ XXX.minecraft.nbt.SnbtGrammar$3
- XXX.minecraft.nbt.SnbtGrammar$4
+ XXX.minecraft.nbt.SnbtGrammar$5
- XXX.minecraft.nbt.SnbtGrammar$ArrayPrefix
+ XXX.minecraft.nbt.SnbtGrammar$ArrayPrefix$1
- XXX.minecraft.nbt.SnbtGrammar$ArrayPrefix$2
+ XXX.minecraft.nbt.SnbtGrammar$ArrayPrefix$3
- XXX.minecraft.nbt.SnbtGrammar$Base
+ XXX.minecraft.nbt.SnbtGrammar$IntegerLiteral
- XXX.minecraft.nbt.SnbtGrammar$IntegerSuffix
+ XXX.minecraft.nbt.SnbtGrammar$Sign
- XXX.minecraft.nbt.SnbtGrammar$Signed
+ XXX.minecraft.nbt.SnbtGrammar$SignedPrefix
- XXX.minecraft.nbt.SnbtGrammar$SimpleHexLiteralParseRule
+ XXX.minecraft.nbt.SnbtGrammar$TypeSuffix
- XXX.minecraft.nbt.SnbtOperations
+ XXX.minecraft.nbt.SnbtOperations$1
- XXX.minecraft.nbt.SnbtOperations$2
+ XXX.minecraft.nbt.SnbtOperations$3
- XXX.minecraft.nbt.SnbtOperations$BuiltinKey
+ XXX.minecraft.nbt.SnbtOperations$BuiltinOperation
- XXX.minecraft.nbt.SnbtPrinterTagVisitor
+ XXX.minecraft.nbt.StreamTagVisitor
- XXX.minecraft.nbt.StreamTagVisitor$EntryResult
+ XXX.minecraft.nbt.StreamTagVisitor$ValueResult
- XXX.minecraft.nbt.StringTag
+ XXX.minecraft.nbt.StringTag$1
- XXX.minecraft.nbt.StringTagVisitor
+ XXX.minecraft.nbt.Tag
- XXX.minecraft.nbt.TagParser
+ XXX.minecraft.nbt.TagType
- XXX.minecraft.nbt.TagType$1
+ XXX.minecraft.nbt.TagType$2
- XXX.minecraft.nbt.TagType$StaticSize
+ XXX.minecraft.nbt.TagType$VariableSize
- XXX.minecraft.nbt.TagTypes
+ XXX.minecraft.nbt.TagVisitor
- XXX.minecraft.nbt.TextComponentTagVisitor
- XXX.minecraft.network.BandwidthDebugMonitor
+ XXX.minecraft.network.CipherBase
- XXX.minecraft.network.CipherDecoder
+ XXX.minecraft.network.CipherEncoder
- XXX.minecraft.network.ClientboundPacketListener
+ XXX.minecraft.network.CompressionDecoder
- XXX.minecraft.network.CompressionEncoder
+ XXX.minecraft.network.Connection
- XXX.minecraft.network.Connection$1
+ XXX.minecraft.network.Connection$2
- XXX.minecraft.network.Connection$3
+ XXX.minecraft.network.ConnectionProtocol
- XXX.minecraft.network.DisconnectionDetails
+ XXX.minecraft.network.FriendlyByteBuf
- XXX.minecraft.network.HandlerNames
+ XXX.minecraft.network.HashedPatchMap
- XXX.minecraft.network.HashedPatchMap$HashGenerator
+ XXX.minecraft.network.HashedStack
- XXX.minecraft.network.HashedStack$1
+ XXX.minecraft.network.HashedStack$ActualItem
- XXX.minecraft.network.HiddenByteBuf
+ XXX.minecraft.network.LocalFrameDecoder
- XXX.minecraft.network.LocalFrameEncoder
+ XXX.minecraft.network.LpVec3
- XXX.minecraft.network.MonitoredLocalFrameDecoder
+ XXX.minecraft.network.package-info
+ XXX.minecraft.network.PacketBundlePacker
- XXX.minecraft.network.PacketBundleUnpacker
+ XXX.minecraft.network.PacketDecoder
- XXX.minecraft.network.PacketEncoder
+ XXX.minecraft.network.PacketListener
- XXX.minecraft.network.PacketProcessor
- XXX.minecraft.network.PacketSendListener
+ XXX.minecraft.network.ProtocolInfo
- XXX.minecraft.network.ProtocolInfo$Details
+ XXX.minecraft.network.ProtocolInfo$Details$PacketVisitor
- XXX.minecraft.network.ProtocolInfo$DetailsProvider
+ XXX.minecraft.network.ProtocolSwapHandler
- XXX.minecraft.network.RateKickingConnection
+ XXX.minecraft.network.RegistryFriendlyByteBuf
- XXX.minecraft.network.ServerboundPacketListener
+ XXX.minecraft.network.SkipPacketDecoderException
- XXX.minecraft.network.SkipPacketEncoderException
+ XXX.minecraft.network.SkipPacketException
- XXX.minecraft.network.TickablePacketListener
+ XXX.minecraft.network.UnconfiguredPipelineHandler
- XXX.minecraft.network.UnconfiguredPipelineHandler$Inbound
+ XXX.minecraft.network.UnconfiguredPipelineHandler$InboundConfigurationTask
- XXX.minecraft.network.UnconfiguredPipelineHandler$Outbound
+ XXX.minecraft.network.UnconfiguredPipelineHandler$OutboundConfigurationTask
- XXX.minecraft.network.Utf8String
+ XXX.minecraft.network.VarInt
+ XXX.minecraft.network.Varint21FrameDecoder
- XXX.minecraft.network.Varint21LengthFieldPrepender
- XXX.minecraft.network.VarLong
- XXX.minecraft.util.BoundedFloatFunction$1
- XXX.minecraft.util.Brightness
+ XXX.minecraft.util.ByIdMap
- XXX.minecraft.util.ByIdMap$OutOfBoundsStrategy
+ XXX.minecraft.util.ClassInstanceMultiMap
- XXX.minecraft.util.ClassTreeIdRegistry
+ XXX.minecraft.util.ColorRGBA
- XXX.minecraft.util.CommonColors
+ XXX.minecraft.util.CommonLinks
- XXX.minecraft.util.CrudeIncrementalIntIdentityHashBiMap
+ XXX.minecraft.util.Crypt
- XXX.minecraft.util.Crypt$ByteArrayToKeyFunction
+ XXX.minecraft.util.Crypt$SaltSignaturePair
- XXX.minecraft.util.Crypt$SaltSupplier
+ XXX.minecraft.util.CryptException
- XXX.minecraft.util.CsvOutput
+ XXX.minecraft.util.CsvOutput$Builder
- XXX.minecraft.util.CubicSampler
+ XXX.minecraft.util.CubicSampler$Vec3Fetcher
- XXX.minecraft.util.CubicSpline
+ XXX.minecraft.util.CubicSpline$1Point
- XXX.minecraft.util.CubicSpline$Builder
+ XXX.minecraft.util.CubicSpline$Constant
- XXX.minecraft.util.CubicSpline$CoordinateVisitor
+ XXX.minecraft.util.CubicSpline$Multipoint
- XXX.minecraft.util.DebugBuffer
+ XXX.minecraft.util.DelegateDataOutput
- XXX.minecraft.util.DependencySorter
+ XXX.minecraft.util.DependencySorter$Entry
- XXX.minecraft.util.DirectoryLock
+ XXX.minecraft.util.DirectoryLock$LockException
- XXX.minecraft.util.EncoderCache
+ XXX.minecraft.util.EncoderCache$1
- XXX.minecraft.util.EncoderCache$2
+ XXX.minecraft.util.EncoderCache$Key
- XXX.minecraft.util.ExceptionCollector
+ XXX.minecraft.util.ExtraCodecs
- XXX.minecraft.util.ExtraCodecs$1
+ XXX.minecraft.util.ExtraCodecs$1ContextRetrievalCodec
- XXX.minecraft.util.ExtraCodecs$2
+ XXX.minecraft.util.ExtraCodecs$3
- XXX.minecraft.util.ExtraCodecs$4
+ XXX.minecraft.util.ExtraCodecs$5
- XXX.minecraft.util.ExtraCodecs$6
+ XXX.minecraft.util.ExtraCodecs$7
- XXX.minecraft.util.ExtraCodecs$LateBoundIdMapper
+ XXX.minecraft.util.ExtraCodecs$StrictUnboundedMapCodec
- XXX.minecraft.util.ExtraCodecs$TagOrElementLocation
+ XXX.minecraft.util.FastBufferedInputStream
- XXX.minecraft.util.FileSystemUtil
+ XXX.minecraft.util.FileZipper
- XXX.minecraft.util.FormattedCharSequence
+ XXX.minecraft.util.FormattedCharSink
- XXX.minecraft.util.FutureChain
+ XXX.minecraft.util.Graph
- XXX.minecraft.util.GsonHelper
+ XXX.minecraft.util.GsonHelper$CountedAppendable
- XXX.minecraft.util.HashOps
+ XXX.minecraft.util.HashOps$ListHashBuilder
- XXX.minecraft.util.HashOps$MapHashBuilder
+ XXX.minecraft.util.HttpUtil
- XXX.minecraft.util.HttpUtil$DownloadProgressListener
+ XXX.minecraft.util.InclusiveRange
- XXX.minecraft.util.KeyDispatchDataCodec
+ XXX.minecraft.util.LazyLoadedValue
- XXX.minecraft.util.LenientJsonParser
+ XXX.minecraft.util.LinearCongruentialGenerator
- XXX.minecraft.util.ListAndDeque
+ XXX.minecraft.util.MemoryReserve
- XXX.minecraft.util.ModCheck
+ XXX.minecraft.util.ModCheck$Confidence
- XXX.minecraft.util.Mth
+ XXX.minecraft.util.NativeModuleLister
- XXX.minecraft.util.NativeModuleLister$NativeModuleInfo
+ XXX.minecraft.util.NativeModuleLister$NativeModuleVersion
- XXX.minecraft.util.NullOps
+ XXX.minecraft.util.NullOps$1
- XXX.minecraft.util.NullOps$NullListBuilder
+ XXX.minecraft.util.NullOps$NullMapBuilder
- XXX.minecraft.util.OptionEnum
+ XXX.minecraft.util.package-info
+ XXX.minecraft.util.ParticleUtils
- XXX.minecraft.util.PlaceholderLookupProvider
+ XXX.minecraft.util.PlaceholderLookupProvider$1
- XXX.minecraft.util.PlaceholderLookupProvider$2
+ XXX.minecraft.util.PlaceholderLookupProvider$UniversalLookup
- XXX.minecraft.util.PngInfo
+ XXX.minecraft.util.ProblemReporter
- XXX.minecraft.util.ProblemReporter$1
+ XXX.minecraft.util.ProblemReporter$Collector
- XXX.minecraft.util.ProblemReporter$Collector$Entry
+ XXX.minecraft.util.ProblemReporter$Collector$ProblemTreeNode
- XXX.minecraft.util.ProblemReporter$ElementReferencePathElement
+ XXX.minecraft.util.ProblemReporter$FieldPathElement
- XXX.minecraft.util.ProblemReporter$IndexedFieldPathElement
+ XXX.minecraft.util.ProblemReporter$IndexedPathElement
- XXX.minecraft.util.ProblemReporter$PathElement
+ XXX.minecraft.util.ProblemReporter$Problem
- XXX.minecraft.util.ProblemReporter$RootElementPathElement
+ XXX.minecraft.util.ProblemReporter$RootFieldPathElement
- XXX.minecraft.util.ProblemReporter$ScopedCollector
+ XXX.minecraft.util.ProgressListener
- XXX.minecraft.util.RandomSource
+ XXX.minecraft.util.RegistryContextSwapper
- XXX.minecraft.util.ResourceLocationPattern
+ XXX.minecraft.util.SegmentedAnglePrecision
- XXX.minecraft.util.SequencedPriorityIterator
+ XXX.minecraft.util.SignatureUpdater
- XXX.minecraft.util.SignatureUpdater$Output
+ XXX.minecraft.util.SignatureValidator
- XXX.minecraft.util.Signer
+ XXX.minecraft.util.SimpleBitStorage
- XXX.minecraft.util.SimpleBitStorage$InitializationException
+ XXX.minecraft.util.SingleKeyCache
- XXX.minecraft.util.SmoothDouble
+ XXX.minecraft.util.SortedArraySet
- XXX.minecraft.util.SortedArraySet$ArrayIterator
+ XXX.minecraft.util.SpawnUtil
- XXX.minecraft.util.SpawnUtil$Strategy
+ XXX.minecraft.util.StaticCache2D
- XXX.minecraft.util.StaticCache2D$Initializer
+ XXX.minecraft.util.StrictJsonParser
- XXX.minecraft.util.StringDecomposer
+ XXX.minecraft.util.StringRepresentable
- XXX.minecraft.util.StringRepresentable$1
+ XXX.minecraft.util.StringRepresentable$EnumCodec
- XXX.minecraft.util.StringRepresentable$StringRepresentableCodec
+ XXX.minecraft.util.StringUtil
- XXX.minecraft.util.TaskChainer
+ XXX.minecraft.util.TaskChainer$1
- XXX.minecraft.util.ThreadingDetector
+ XXX.minecraft.util.TickThrottler
- XXX.minecraft.util.TimeSource
+ XXX.minecraft.util.TimeSource$NanoTimeSource
- XXX.minecraft.util.TimeUtil
+ XXX.minecraft.util.ToFloatFunction
+ XXX.minecraft.util.ToFloatFunction$2
- XXX.minecraft.util.TriState
+ XXX.minecraft.util.Tuple
- XXX.minecraft.util.Unit
+ XXX.minecraft.util.VisibleForDebug
- XXX.minecraft.util.ZeroBitStorage
+ XXX.minecraft.world.BossEvent
- XXX.minecraft.world.BossEvent$BossBarColor
+ XXX.minecraft.world.BossEvent$BossBarOverlay
- XXX.minecraft.world.Clearable
+ XXX.minecraft.world.CompoundContainer
- XXX.minecraft.world.Container
+ XXX.minecraft.world.Container$ContainerIterator
- XXX.minecraft.world.ContainerHelper
+ XXX.minecraft.world.ContainerListener
- XXX.minecraft.world.Containers
+ XXX.minecraft.world.Difficulty
- XXX.minecraft.world.DifficultyInstance
+ XXX.minecraft.world.InteractionHand
- XXX.minecraft.world.InteractionResult
+ XXX.minecraft.world.InteractionResult$Fail
- XXX.minecraft.world.InteractionResult$ItemContext
+ XXX.minecraft.world.InteractionResult$Pass
- XXX.minecraft.world.InteractionResult$Success
+ XXX.minecraft.world.InteractionResult$SwingSource
- XXX.minecraft.world.InteractionResult$TryEmptyHandInteraction
+ XXX.minecraft.world.ItemStackWithSlot
- XXX.minecraft.world.LockCode
+ XXX.minecraft.world.MenuProvider
- XXX.minecraft.world.Nameable
- XXX.minecraft.world.RandomizableContainer
+ XXX.minecraft.world.RandomSequence
- XXX.minecraft.world.RandomSequences
+ XXX.minecraft.world.RandomSequences$DirtyMarkingRandomSource
+ XXX.minecraft.world.SimpleContainer
- XXX.minecraft.world.SimpleMenuProvider
+ XXX.minecraft.world.TickRateManager
- XXX.minecraft.world.WorldlyContainer
+ XXX.minecraft.world.WorldlyContainerHolder
- XXX.model.multipart.CombinedCondition
+ XXX.model.multipart.CombinedCondition$Operation
- XXX.model.multipart.CombinedCondition$Operation$1
+ XXX.model.multipart.CombinedCondition$Operation$2
- XXX.model.multipart.Condition
+ XXX.model.multipart.KeyValueCondition
- XXX.model.multipart.KeyValueCondition$Term
+ XXX.model.multipart.KeyValueCondition$Terms
- XXX.model.multipart.MultiPartModel
+ XXX.model.multipart.MultiPartModel$Selector
- XXX.model.multipart.MultiPartModel$SharedBakedState
+ XXX.model.multipart.MultiPartModel$Unbaked
- XXX.model.multipart.MultiPartModel$Unbaked$1
+ XXX.model.multipart.MultiPartModel$Unbaked$1Key
+ XXX.model.multipart.package-info
- XXX.model.multipart.Selector
- XXX.models.blockstates.BlockModelDefinitionGenerator
+ XXX.models.blockstates.ConditionBuilder
- XXX.models.blockstates.MultiPartGenerator
+ XXX.models.blockstates.MultiPartGenerator$Entry
- XXX.models.blockstates.MultiVariantGenerator
+ XXX.models.blockstates.MultiVariantGenerator$Empty
- XXX.models.blockstates.MultiVariantGenerator$Entry
- XXX.models.blockstates.package-info
+ XXX.models.blockstates.PropertyDispatch
- XXX.models.blockstates.PropertyDispatch$C1
+ XXX.models.blockstates.PropertyDispatch$C2
- XXX.models.blockstates.PropertyDispatch$C3
+ XXX.models.blockstates.PropertyDispatch$C4
- XXX.models.blockstates.PropertyDispatch$C5
+ XXX.models.blockstates.PropertyValueList
+ XXX.models.model.DelegatedModel
- XXX.models.model.ItemModelUtils
+ XXX.models.model.ModelInstance
- XXX.models.model.ModelLocationUtils
+ XXX.models.model.ModelTemplate
- XXX.models.model.ModelTemplates
+ XXX.models.model.package-info
+ XXX.models.model.TexturedModel
- XXX.models.model.TexturedModel$Provider
+ XXX.models.model.TextureMapping
- XXX.models.model.TextureSlot
- XXX.mojang.math.Axis
+ XXX.mojang.math.Constants
- XXX.mojang.math.Divisor
+ XXX.mojang.math.FieldsAreNonnullByDefault
- XXX.mojang.math.GivensParameters
+ XXX.mojang.math.MatrixUtil
- XXX.mojang.math.MethodsReturnNonnullByDefault
+ XXX.mojang.math.OctahedralGroup
- XXX.mojang.math.OctahedralGroup$1
- XXX.mojang.math.package-info
+ XXX.mojang.math.Quadrant
- XXX.mojang.math.SymmetricGroup3
+ XXX.mojang.math.Transformation
- XXX.mojang.realmsclient.package-info
+ XXX.mojang.realmsclient.RealmsAvailability
- XXX.mojang.realmsclient.RealmsAvailability$Result
+ XXX.mojang.realmsclient.RealmsAvailability$Type
- XXX.mojang.realmsclient.RealmsMainScreen
+ XXX.mojang.realmsclient.RealmsMainScreen$1
- XXX.mojang.realmsclient.RealmsMainScreen$2
+ XXX.mojang.realmsclient.RealmsMainScreen$AvailableSnapshotEntry
- XXX.mojang.realmsclient.RealmsMainScreen$CrossButton
+ XXX.mojang.realmsclient.RealmsMainScreen$Entry
- XXX.mojang.realmsclient.RealmsMainScreen$LayoutState
+ XXX.mojang.realmsclient.RealmsMainScreen$NotificationButton
- XXX.mojang.realmsclient.RealmsMainScreen$NotificationMessageEntry
+ XXX.mojang.realmsclient.RealmsMainScreen$ParentEntry
+ XXX.mojang.realmsclient.RealmsMainScreen$RealmsCall
- XXX.mojang.realmsclient.RealmsMainScreen$RealmSelectionList
- XXX.mojang.realmsclient.RealmsMainScreen$ServerEntry
+ XXX.mojang.realmsclient.Unit
- XXX.monitoring.jmx.MinecraftServerStatistics
+ XXX.monitoring.jmx.MinecraftServerStatistics$AttributeDescription
- XXX.monitoring.jmx.package-info
- XXX.nbt.visitors.CollectFields
+ XXX.nbt.visitors.CollectToTag
- XXX.nbt.visitors.CollectToTag$CompoundBuilder
+ XXX.nbt.visitors.CollectToTag$ContainerBuilder
- XXX.nbt.visitors.CollectToTag$ListBuilder
+ XXX.nbt.visitors.CollectToTag$RootBuilder
- XXX.nbt.visitors.FieldSelector
+ XXX.nbt.visitors.FieldTree
+ XXX.nbt.visitors.package-info
- XXX.nbt.visitors.SkipAll
+ XXX.nbt.visitors.SkipAll$1
- XXX.nbt.visitors.SkipFields
+ XXX.network.chat.ChatDecorator
- XXX.network.chat.ChatType
+ XXX.network.chat.ChatType$Bound
- XXX.network.chat.ChatTypeDecoration
+ XXX.network.chat.ChatTypeDecoration$Parameter
- XXX.network.chat.ChatTypeDecoration$Parameter$Selector
+ XXX.network.chat.ClickEvent
- XXX.network.chat.ClickEvent$Action
+ XXX.network.chat.ClickEvent$ChangePage
- XXX.network.chat.ClickEvent$CopyToClipboard
+ XXX.network.chat.ClickEvent$Custom
- XXX.network.chat.ClickEvent$OpenFile
+ XXX.network.chat.ClickEvent$OpenUrl
- XXX.network.chat.ClickEvent$RunCommand
+ XXX.network.chat.ClickEvent$ShowDialog
- XXX.network.chat.ClickEvent$SuggestCommand
+ XXX.network.chat.CommonComponents
- XXX.network.chat.Component
+ XXX.network.chat.ComponentContents
- XXX.network.chat.ComponentSerialization
+ XXX.network.chat.ComponentSerialization$1
- XXX.network.chat.ComponentSerialization$FuzzyCodec
+ XXX.network.chat.ComponentSerialization$StrictEither
- XXX.network.chat.ComponentUtils
+ XXX.network.chat.FilterMask
- XXX.network.chat.FilterMask$Type
+ XXX.network.chat.FontDescription
- XXX.network.chat.FontDescription$AtlasSprite
+ XXX.network.chat.FontDescription$PlayerSprite
- XXX.network.chat.FontDescription$Resource
+ XXX.network.chat.FormattedText
- XXX.network.chat.FormattedText$1
+ XXX.network.chat.FormattedText$2
- XXX.network.chat.FormattedText$3
+ XXX.network.chat.FormattedText$4
- XXX.network.chat.FormattedText$ContentConsumer
+ XXX.network.chat.FormattedText$StyledContentConsumer
- XXX.network.chat.HoverEvent
+ XXX.network.chat.HoverEvent$Action
- XXX.network.chat.HoverEvent$EntityTooltipInfo
+ XXX.network.chat.HoverEvent$ShowEntity
- XXX.network.chat.HoverEvent$ShowItem
+ XXX.network.chat.HoverEvent$ShowText
- XXX.network.chat.LastSeenMessages
+ XXX.network.chat.LastSeenMessages$Packed
- XXX.network.chat.LastSeenMessages$Update
+ XXX.network.chat.LastSeenMessagesTracker
- XXX.network.chat.LastSeenMessagesTracker$Update
+ XXX.network.chat.LastSeenMessagesValidator
- XXX.network.chat.LastSeenMessagesValidator$ValidationException
+ XXX.network.chat.LastSeenTrackedEntry
- XXX.network.chat.LocalChatSession
+ XXX.network.chat.MessageSignature
- XXX.network.chat.MessageSignature$Packed
+ XXX.network.chat.MessageSignatureCache
- XXX.network.chat.MutableComponent
+ XXX.network.chat.OutgoingChatMessage
- XXX.network.chat.OutgoingChatMessage$Disguised
+ XXX.network.chat.OutgoingChatMessage$Player
+ XXX.network.chat.package-info
- XXX.network.chat.PlayerChatMessage
+ XXX.network.chat.RemoteChatSession
- XXX.network.chat.RemoteChatSession$Data
+ XXX.network.chat.SignableCommand
- XXX.network.chat.SignableCommand$Argument
+ XXX.network.chat.SignedMessageBody
- XXX.network.chat.SignedMessageBody$Packed
+ XXX.network.chat.SignedMessageChain
- XXX.network.chat.SignedMessageChain$1
+ XXX.network.chat.SignedMessageChain$DecodeException
- XXX.network.chat.SignedMessageChain$Decoder
+ XXX.network.chat.SignedMessageChain$Encoder
- XXX.network.chat.SignedMessageLink
+ XXX.network.chat.SignedMessageValidator
- XXX.network.chat.SignedMessageValidator$KeyBased
+ XXX.network.chat.Style
- XXX.network.chat.Style$1
+ XXX.network.chat.Style$1Collector
- XXX.network.chat.Style$Serializer
+ XXX.network.chat.SubStringSource
- XXX.network.chat.TextColor
+ XXX.network.chat.ThrowingComponent
- XXX.network.codec.ByteBufCodecs
+ XXX.network.codec.ByteBufCodecs$1
- XXX.network.codec.ByteBufCodecs$10
+ XXX.network.codec.ByteBufCodecs$11
- XXX.network.codec.ByteBufCodecs$12
+ XXX.network.codec.ByteBufCodecs$13
- XXX.network.codec.ByteBufCodecs$14
+ XXX.network.codec.ByteBufCodecs$15
- XXX.network.codec.ByteBufCodecs$16
+ XXX.network.codec.ByteBufCodecs$17
- XXX.network.codec.ByteBufCodecs$18
+ XXX.network.codec.ByteBufCodecs$19
- XXX.network.codec.ByteBufCodecs$2
+ XXX.network.codec.ByteBufCodecs$20
- XXX.network.codec.ByteBufCodecs$21
+ XXX.network.codec.ByteBufCodecs$22
- XXX.network.codec.ByteBufCodecs$23
+ XXX.network.codec.ByteBufCodecs$24
- XXX.network.codec.ByteBufCodecs$25
+ XXX.network.codec.ByteBufCodecs$26
- XXX.network.codec.ByteBufCodecs$27
+ XXX.network.codec.ByteBufCodecs$28
- XXX.network.codec.ByteBufCodecs$29
+ XXX.network.codec.ByteBufCodecs$3
- XXX.network.codec.ByteBufCodecs$30
+ XXX.network.codec.ByteBufCodecs$31
- XXX.network.codec.ByteBufCodecs$32
+ XXX.network.codec.ByteBufCodecs$33
- XXX.network.codec.ByteBufCodecs$34
+ XXX.network.codec.ByteBufCodecs$35
- XXX.network.codec.ByteBufCodecs$4
+ XXX.network.codec.ByteBufCodecs$5
- XXX.network.codec.ByteBufCodecs$6
+ XXX.network.codec.ByteBufCodecs$7
- XXX.network.codec.ByteBufCodecs$8
+ XXX.network.codec.ByteBufCodecs$9
- XXX.network.codec.IdDispatchCodec
+ XXX.network.codec.IdDispatchCodec$Builder
- XXX.network.codec.IdDispatchCodec$DontDecorateException
+ XXX.network.codec.IdDispatchCodec$Entry
- XXX.network.codec.package-info
- XXX.network.codec.StreamCodec
+ XXX.network.codec.StreamCodec$1
- XXX.network.codec.StreamCodec$10
+ XXX.network.codec.StreamCodec$11
- XXX.network.codec.StreamCodec$12
+ XXX.network.codec.StreamCodec$13
- XXX.network.codec.StreamCodec$14
+ XXX.network.codec.StreamCodec$15
- XXX.network.codec.StreamCodec$16
+ XXX.network.codec.StreamCodec$17
- XXX.network.codec.StreamCodec$2
+ XXX.network.codec.StreamCodec$3
- XXX.network.codec.StreamCodec$4
+ XXX.network.codec.StreamCodec$5
- XXX.network.codec.StreamCodec$6
+ XXX.network.codec.StreamCodec$7
- XXX.network.codec.StreamCodec$8
+ XXX.network.codec.StreamCodec$9
- XXX.network.codec.StreamCodec$CodecOperation
+ XXX.network.codec.StreamDecoder
- XXX.network.codec.StreamEncoder
+ XXX.network.codec.StreamMemberEncoder
- XXX.network.protocol.BundleDelimiterPacket
+ XXX.network.protocol.BundlePacket
- XXX.network.protocol.BundlerInfo
+ XXX.network.protocol.BundlerInfo$1
- XXX.network.protocol.BundlerInfo$1$1
+ XXX.network.protocol.BundlerInfo$Bundler
- XXX.network.protocol.CodecModifier
- XXX.network.protocol.package-info
+ XXX.network.protocol.Packet
- XXX.network.protocol.PacketFlow
+ XXX.network.protocol.PacketType
- XXX.network.protocol.PacketUtils
+ XXX.network.protocol.ProtocolCodecBuilder
- XXX.network.protocol.ProtocolInfoBuilder
+ XXX.network.protocol.ProtocolInfoBuilder$1
- XXX.network.protocol.ProtocolInfoBuilder$2
+ XXX.network.protocol.ProtocolInfoBuilder$3
- XXX.network.protocol.ProtocolInfoBuilder$CodecEntry
+ XXX.network.protocol.ProtocolInfoBuilder$Implementation
- XXX.network.protocol.SimpleUnboundProtocol
+ XXX.network.protocol.UnboundProtocol
- XXX.network.syncher.EntityDataAccessor
+ XXX.network.syncher.EntityDataSerializer
- XXX.network.syncher.EntityDataSerializer$ForValueType
+ XXX.network.syncher.EntityDataSerializers
- XXX.network.syncher.EntityDataSerializers$1
+ XXX.network.syncher.EntityDataSerializers$2
- XXX.network.syncher.EntityDataSerializers$3
+ XXX.network.syncher.EntityDataSerializers$4
- XXX.packrat.commands.CommandArgumentParser
+ XXX.packrat.commands.CommandArgumentParser$1
- XXX.packrat.commands.CommandArgumentParser$2
+ XXX.packrat.commands.Grammar
- XXX.packrat.commands.GreedyPatternParseRule
+ XXX.packrat.commands.GreedyPredicateParseRule
- XXX.packrat.commands.NumberRunParseRule
+ XXX.packrat.commands.package-info
+ XXX.packrat.commands.ParserBasedArgument
- XXX.packrat.commands.ResourceLocationParseRule
+ XXX.packrat.commands.ResourceLookupRule
- XXX.packrat.commands.ResourceSuggestion
+ XXX.packrat.commands.StringReaderParserState
- XXX.packrat.commands.StringReaderTerms
+ XXX.packrat.commands.StringReaderTerms$1
- XXX.packrat.commands.StringReaderTerms$2
+ XXX.packrat.commands.StringReaderTerms$TerminalCharacters
- XXX.packrat.commands.StringReaderTerms$TerminalWord
+ XXX.packrat.commands.TagParseRule
- XXX.packrat.commands.UnquotedStringParseRule
+ XXX.parsing.packrat.Atom
- XXX.parsing.packrat.CachedParseState
+ XXX.parsing.packrat.CachedParseState$CacheEntry
- XXX.parsing.packrat.CachedParseState$PositionCache
+ XXX.parsing.packrat.CachedParseState$Silent
- XXX.parsing.packrat.CachedParseState$SimpleControl
+ XXX.parsing.packrat.Control
- XXX.parsing.packrat.Control$1
+ XXX.parsing.packrat.DelayedException
- XXX.parsing.packrat.Dictionary
+ XXX.parsing.packrat.Dictionary$Entry
- XXX.parsing.packrat.Dictionary$Reference
+ XXX.parsing.packrat.ErrorCollector
- XXX.parsing.packrat.ErrorCollector$LongestOnly
+ XXX.parsing.packrat.ErrorCollector$LongestOnly$MutableErrorEntry
- XXX.parsing.packrat.ErrorCollector$Nop
+ XXX.parsing.packrat.ErrorEntry
- XXX.parsing.packrat.NamedRule
- XXX.parsing.packrat.package-info
+ XXX.parsing.packrat.ParseState
- XXX.parsing.packrat.Rule
+ XXX.parsing.packrat.Rule$RuleAction
- XXX.parsing.packrat.Rule$SimpleRuleAction
+ XXX.parsing.packrat.Rule$WrappedTerm
- XXX.parsing.packrat.Scope
+ XXX.parsing.packrat.Scope$1
- XXX.parsing.packrat.SuggestionSupplier
+ XXX.parsing.packrat.Term
- XXX.parsing.packrat.Term$1
+ XXX.parsing.packrat.Term$2
- XXX.parsing.packrat.Term$3
+ XXX.parsing.packrat.Term$Alternative
- XXX.parsing.packrat.Term$LookAhead
+ XXX.parsing.packrat.Term$Marker
- XXX.parsing.packrat.Term$Maybe
+ XXX.parsing.packrat.Term$Repeated
- XXX.parsing.packrat.Term$RepeatedWithSeparator
+ XXX.parsing.packrat.Term$Sequence
- XXX.player.inventory.Hotbar
+ XXX.player.inventory.package-info
+ XXX.profiling.jfr.Environment
- XXX.profiling.jfr.JfrProfiler
+ XXX.profiling.jfr.JfrProfiler$1
- XXX.profiling.jfr.JvmProfiler
+ XXX.profiling.jfr.JvmProfiler$NoOpProfiler
+ XXX.profiling.jfr.package-info
- XXX.profiling.jfr.Percentiles
+ XXX.profiling.jfr.SummaryReporter
+ XXX.profiling.metrics.MetricCategory
- XXX.profiling.metrics.MetricSampler
+ XXX.profiling.metrics.MetricSampler$MetricSamplerBuilder
- XXX.profiling.metrics.MetricSampler$SamplerResult
+ XXX.profiling.metrics.MetricSampler$ThresholdTest
- XXX.profiling.metrics.MetricSampler$ValueIncreasedByPercentage
+ XXX.profiling.metrics.MetricsRegistry
- XXX.profiling.metrics.MetricsRegistry$AggregatedMetricSampler
+ XXX.profiling.metrics.MetricsSamplerProvider
+ XXX.profiling.metrics.package-info
- XXX.profiling.metrics.ProfilerMeasured
- XXX.projectile.windcharge.AbstractWindCharge
+ XXX.projectile.windcharge.BreezeWindCharge
+ XXX.projectile.windcharge.package-info
- XXX.projectile.windcharge.WindCharge
+ XXX.protocol.common.ClientboundClearDialogPacket
- XXX.protocol.common.ClientboundCustomPayloadPacket
+ XXX.protocol.common.ClientboundCustomReportDetailsPacket
- XXX.protocol.common.ClientboundDisconnectPacket
+ XXX.protocol.common.ClientboundKeepAlivePacket
- XXX.protocol.common.ClientboundPingPacket
+ XXX.protocol.common.ClientboundResourcePackPopPacket
- XXX.protocol.common.ClientboundResourcePackPushPacket
+ XXX.protocol.common.ClientboundServerLinksPacket
- XXX.protocol.common.ClientboundShowDialogPacket
+ XXX.protocol.common.ClientboundStoreCookiePacket
- XXX.protocol.common.ClientboundTransferPacket
+ XXX.protocol.common.ClientboundUpdateTagsPacket
- XXX.protocol.common.ClientCommonPacketListener
- XXX.protocol.common.CommonPacketTypes
+ XXX.protocol.common.package-info
- XXX.protocol.common.ServerboundClientInformationPacket
+ XXX.protocol.common.ServerboundCustomClickActionPacket
- XXX.protocol.common.ServerboundCustomPayloadPacket
+ XXX.protocol.common.ServerboundKeepAlivePacket
- XXX.protocol.common.ServerboundPongPacket
+ XXX.protocol.common.ServerboundResourcePackPacket
- XXX.protocol.common.ServerboundResourcePackPacket$Action
+ XXX.protocol.common.ServerCommonPacketListener
+ XXX.protocol.configuration.ClientboundCodeOfConductPacket
- XXX.protocol.configuration.ClientboundFinishConfigurationPacket
+ XXX.protocol.configuration.ClientboundRegistryDataPacket
- XXX.protocol.configuration.ClientboundResetChatPacket
+ XXX.protocol.configuration.ClientboundSelectKnownPacks
- XXX.protocol.configuration.ClientboundUpdateEnabledFeaturesPacket
- XXX.protocol.configuration.ClientConfigurationPacketListener
+ XXX.protocol.configuration.ConfigurationPacketTypes
- XXX.protocol.configuration.ConfigurationProtocols
+ XXX.protocol.configuration.package-info
- XXX.protocol.configuration.ServerboundAcceptCodeOfConductPacket
+ XXX.protocol.configuration.ServerboundFinishConfigurationPacket
- XXX.protocol.configuration.ServerboundSelectKnownPacks
+ XXX.protocol.configuration.ServerConfigurationPacketListener
+ XXX.protocol.cookie.ClientboundCookieRequestPacket
- XXX.protocol.cookie.ClientCookiePacketListener
- XXX.protocol.cookie.CookiePacketTypes
+ XXX.protocol.cookie.package-info
- XXX.protocol.cookie.ServerboundCookieResponsePacket
+ XXX.protocol.cookie.ServerCookiePacketListener
+ XXX.protocol.game.ClientboundAddEntityPacket
- XXX.protocol.game.ClientboundAnimatePacket
+ XXX.protocol.game.ClientboundAwardStatsPacket
- XXX.protocol.game.ClientboundBlockChangedAckPacket
+ XXX.protocol.game.ClientboundBlockDestructionPacket
- XXX.protocol.game.ClientboundBlockEntityDataPacket
+ XXX.protocol.game.ClientboundBlockEventPacket
- XXX.protocol.game.ClientboundBlockUpdatePacket
+ XXX.protocol.game.ClientboundBossEventPacket
- XXX.protocol.game.ClientboundBossEventPacket$1
+ XXX.protocol.game.ClientboundBossEventPacket$AddOperation
- XXX.protocol.game.ClientboundBossEventPacket$Handler
+ XXX.protocol.game.ClientboundBossEventPacket$Operation
- XXX.protocol.game.ClientboundBossEventPacket$OperationType
+ XXX.protocol.game.ClientboundBossEventPacket$UpdateNameOperation
- XXX.protocol.game.ClientboundBossEventPacket$UpdateProgressOperation
+ XXX.protocol.game.ClientboundBossEventPacket$UpdatePropertiesOperation
- XXX.protocol.game.ClientboundBossEventPacket$UpdateStyleOperation
+ XXX.protocol.game.ClientboundBundleDelimiterPacket
- XXX.protocol.game.ClientboundBundlePacket
+ XXX.protocol.game.ClientboundChangeDifficultyPacket
- XXX.protocol.game.ClientboundChunkBatchFinishedPacket
+ XXX.protocol.game.ClientboundChunkBatchStartPacket
- XXX.protocol.game.ClientboundChunksBiomesPacket
+ XXX.protocol.game.ClientboundChunksBiomesPacket$ChunkBiomeData
- XXX.protocol.game.ClientboundClearTitlesPacket
+ XXX.protocol.game.ClientboundCommandsPacket
- XXX.protocol.game.ClientboundCommandsPacket$ArgumentNodeStub
+ XXX.protocol.game.ClientboundCommandsPacket$Entry
- XXX.protocol.game.ClientboundCommandsPacket$LiteralNodeStub
+ XXX.protocol.game.ClientboundCommandsPacket$NodeBuilder
- XXX.protocol.game.ClientboundCommandsPacket$NodeInspector
+ XXX.protocol.game.ClientboundCommandsPacket$NodeResolver
- XXX.protocol.game.ClientboundCommandsPacket$NodeStub
+ XXX.protocol.game.ClientboundCommandSuggestionsPacket
- XXX.protocol.game.ClientboundCommandSuggestionsPacket$Entry
+ XXX.protocol.game.ClientboundContainerClosePacket
- XXX.protocol.game.ClientboundContainerSetContentPacket
+ XXX.protocol.game.ClientboundContainerSetDataPacket
- XXX.protocol.game.ClientboundContainerSetSlotPacket
+ XXX.protocol.game.ClientboundCooldownPacket
- XXX.protocol.game.ClientboundCustomChatCompletionsPacket
+ XXX.protocol.game.ClientboundCustomChatCompletionsPacket$Action
- XXX.protocol.game.ClientboundDamageEventPacket
+ XXX.protocol.game.ClientboundDebugSamplePacket
- XXX.protocol.game.ClientboundDeleteChatPacket
+ XXX.protocol.game.ClientboundDisguisedChatPacket
- XXX.protocol.game.ClientboundEntityEventPacket
+ XXX.protocol.game.ClientboundEntityPositionSyncPacket
- XXX.protocol.game.ClientboundExplodePacket
+ XXX.protocol.game.ClientboundForgetLevelChunkPacket
- XXX.protocol.game.ClientboundGameEventPacket
+ XXX.protocol.game.ClientboundGameEventPacket$Type
- XXX.protocol.game.ClientboundHorseScreenOpenPacket
+ XXX.protocol.game.ClientboundHurtAnimationPacket
- XXX.protocol.game.ClientboundInitializeBorderPacket
+ XXX.protocol.game.ClientboundLevelChunkPacketData
- XXX.protocol.game.ClientboundLevelChunkPacketData$BlockEntityInfo
+ XXX.protocol.game.ClientboundLevelChunkPacketData$BlockEntityTagOutput
- XXX.protocol.game.ClientboundLevelChunkWithLightPacket
+ XXX.protocol.game.ClientboundLevelEventPacket
- XXX.protocol.game.ClientboundLevelParticlesPacket
+ XXX.protocol.game.ClientboundLightUpdatePacket
- XXX.protocol.game.ClientboundLightUpdatePacketData
+ XXX.protocol.game.ClientboundLoginPacket
- XXX.protocol.game.ClientboundMapItemDataPacket
+ XXX.protocol.game.ClientboundMerchantOffersPacket
- XXX.protocol.game.ClientboundMoveEntityPacket
+ XXX.protocol.game.ClientboundMoveEntityPacket$Pos
- XXX.protocol.game.ClientboundMoveEntityPacket$PosRot
+ XXX.protocol.game.ClientboundMoveEntityPacket$Rot
- XXX.protocol.game.ClientboundMoveMinecartPacket
+ XXX.protocol.game.ClientboundMoveVehiclePacket
- XXX.protocol.game.ClientboundOpenBookPacket
+ XXX.protocol.game.ClientboundOpenScreenPacket
- XXX.protocol.game.ClientboundOpenSignEditorPacket
+ XXX.protocol.game.ClientboundPlaceGhostRecipePacket
- XXX.protocol.game.ClientboundPlayerAbilitiesPacket
+ XXX.protocol.game.ClientboundPlayerChatPacket
- XXX.protocol.game.ClientboundPlayerCombatEndPacket
+ XXX.protocol.game.ClientboundPlayerCombatEnterPacket
- XXX.protocol.game.ClientboundPlayerCombatKillPacket
+ XXX.protocol.game.ClientboundPlayerInfoRemovePacket
- XXX.protocol.game.ClientboundPlayerInfoUpdatePacket
+ XXX.protocol.game.ClientboundPlayerInfoUpdatePacket$Action
- XXX.protocol.game.ClientboundPlayerInfoUpdatePacket$Action$Reader
+ XXX.protocol.game.ClientboundPlayerInfoUpdatePacket$Action$Writer
- XXX.protocol.game.ClientboundPlayerInfoUpdatePacket$Entry
+ XXX.protocol.game.ClientboundPlayerInfoUpdatePacket$EntryBuilder
- XXX.protocol.game.ClientboundPlayerLookAtPacket
+ XXX.protocol.game.ClientboundPlayerPositionPacket
- XXX.protocol.game.ClientboundPlayerRotationPacket
+ XXX.protocol.game.ClientboundProjectilePowerPacket
- XXX.protocol.game.ClientboundRecipeBookAddPacket
+ XXX.protocol.game.ClientboundRecipeBookAddPacket$Entry
- XXX.protocol.game.ClientboundRecipeBookRemovePacket
+ XXX.protocol.game.ClientboundRecipeBookSettingsPacket
- XXX.protocol.game.ClientboundRemoveEntitiesPacket
+ XXX.protocol.game.ClientboundRemoveMobEffectPacket
- XXX.protocol.game.ClientboundResetScorePacket
+ XXX.protocol.game.ClientboundRespawnPacket
- XXX.protocol.game.ClientboundRotateHeadPacket
+ XXX.protocol.game.ClientboundSectionBlocksUpdatePacket
- XXX.protocol.game.ClientboundSelectAdvancementsTabPacket
+ XXX.protocol.game.ClientboundServerDataPacket
- XXX.protocol.game.ClientboundSetActionBarTextPacket
+ XXX.protocol.game.ClientboundSetBorderCenterPacket
- XXX.protocol.game.ClientboundSetBorderLerpSizePacket
+ XXX.protocol.game.ClientboundSetBorderSizePacket
- XXX.protocol.game.ClientboundSetBorderWarningDelayPacket
+ XXX.protocol.game.ClientboundSetBorderWarningDistancePacket
- XXX.protocol.game.ClientboundSetCameraPacket
+ XXX.protocol.game.ClientboundSetChunkCacheCenterPacket
- XXX.protocol.game.ClientboundSetChunkCacheRadiusPacket
+ XXX.protocol.game.ClientboundSetCursorItemPacket
- XXX.protocol.game.ClientboundSetDefaultSpawnPositionPacket
+ XXX.protocol.game.ClientboundSetDisplayObjectivePacket
- XXX.protocol.game.ClientboundSetEntityDataPacket
+ XXX.protocol.game.ClientboundSetEntityLinkPacket
- XXX.protocol.game.ClientboundSetEntityMotionPacket
+ XXX.protocol.game.ClientboundSetEquipmentPacket
- XXX.protocol.game.ClientboundSetExperiencePacket
+ XXX.protocol.game.ClientboundSetHealthPacket
- XXX.protocol.game.ClientboundSetHeldSlotPacket
+ XXX.protocol.game.ClientboundSetObjectivePacket
- XXX.protocol.game.ClientboundSetPassengersPacket
+ XXX.protocol.game.ClientboundSetPlayerInventoryPacket
- XXX.protocol.game.ClientboundSetPlayerTeamPacket
+ XXX.protocol.game.ClientboundSetPlayerTeamPacket$Action
- XXX.protocol.game.ClientboundSetPlayerTeamPacket$Parameters
+ XXX.protocol.game.ClientboundSetScorePacket
- XXX.protocol.game.ClientboundSetSimulationDistancePacket
+ XXX.protocol.game.ClientboundSetSubtitleTextPacket
- XXX.protocol.game.ClientboundSetTimePacket
- XXX.protocol.game.ClientboundSetTitlesAnimationPacket
+ XXX.protocol.game.ClientboundSetTitleTextPacket
+ XXX.protocol.game.ClientboundSoundEntityPacket
- XXX.protocol.game.ClientboundSoundPacket
+ XXX.protocol.game.ClientboundStartConfigurationPacket
- XXX.protocol.game.ClientboundStopSoundPacket
+ XXX.protocol.game.ClientboundSystemChatPacket
- XXX.protocol.game.ClientboundTabListPacket
+ XXX.protocol.game.ClientboundTagQueryPacket
- XXX.protocol.game.ClientboundTakeItemEntityPacket
+ XXX.protocol.game.ClientboundTeleportEntityPacket
- XXX.protocol.game.ClientboundTestInstanceBlockStatus
+ XXX.protocol.game.ClientboundTickingStatePacket
- XXX.protocol.game.ClientboundTickingStepPacket
+ XXX.protocol.game.ClientboundTrackedWaypointPacket
- XXX.protocol.game.ClientboundTrackedWaypointPacket$Operation
+ XXX.protocol.game.ClientboundUpdateAdvancementsPacket
- XXX.protocol.game.ClientboundUpdateAttributesPacket
+ XXX.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
- XXX.protocol.game.ClientboundUpdateMobEffectPacket
+ XXX.protocol.game.ClientboundUpdateRecipesPacket
- XXX.protocol.game.ClientGamePacketListener
- XXX.protocol.game.CommonPlayerSpawnInfo
+ XXX.protocol.game.DebugEntityNameGenerator
- XXX.protocol.game.DebugPackets
+ XXX.protocol.game.GamePacketTypes
- XXX.protocol.game.GameProtocols
+ XXX.protocol.game.GameProtocols$1
- XXX.protocol.game.GameProtocols$Context
- XXX.protocol.game.package-info
+ XXX.protocol.game.ServerboundAcceptTeleportationPacket
- XXX.protocol.game.ServerboundBlockEntityTagQueryPacket
+ XXX.protocol.game.ServerboundChangeDifficultyPacket
- XXX.protocol.game.ServerboundChangeGameModePacket
+ XXX.protocol.game.ServerboundChatAckPacket
- XXX.protocol.game.ServerboundChatCommandPacket
+ XXX.protocol.game.ServerboundChatCommandSignedPacket
- XXX.protocol.game.ServerboundChatPacket
+ XXX.protocol.game.ServerboundChatSessionUpdatePacket
- XXX.protocol.game.ServerboundChunkBatchReceivedPacket
+ XXX.protocol.game.ServerboundClientCommandPacket
- XXX.protocol.game.ServerboundClientCommandPacket$Action
+ XXX.protocol.game.ServerboundClientTickEndPacket
- XXX.protocol.game.ServerboundCommandSuggestionPacket
+ XXX.protocol.game.ServerboundConfigurationAcknowledgedPacket
- XXX.protocol.game.ServerboundContainerButtonClickPacket
+ XXX.protocol.game.ServerboundContainerClickPacket
- XXX.protocol.game.ServerboundContainerClosePacket
+ XXX.protocol.game.ServerboundContainerSlotStateChangedPacket
- XXX.protocol.game.ServerboundDebugSampleSubscriptionPacket
+ XXX.protocol.game.ServerboundEditBookPacket
- XXX.protocol.game.ServerboundEntityTagQueryPacket
+ XXX.protocol.game.ServerboundInteractPacket
- XXX.protocol.game.ServerboundInteractPacket$1
+ XXX.protocol.game.ServerboundInteractPacket$Action
- XXX.protocol.game.ServerboundInteractPacket$ActionType
+ XXX.protocol.game.ServerboundInteractPacket$Handler
- XXX.protocol.game.ServerboundInteractPacket$InteractionAction
+ XXX.protocol.game.ServerboundInteractPacket$InteractionAtLocationAction
- XXX.protocol.game.ServerboundJigsawGeneratePacket
+ XXX.protocol.game.ServerboundLockDifficultyPacket
- XXX.protocol.game.ServerboundMovePlayerPacket
+ XXX.protocol.game.ServerboundMovePlayerPacket$Pos
- XXX.protocol.game.ServerboundMovePlayerPacket$PosRot
+ XXX.protocol.game.ServerboundMovePlayerPacket$Rot
- XXX.protocol.game.ServerboundMovePlayerPacket$StatusOnly
+ XXX.protocol.game.ServerboundMoveVehiclePacket
- XXX.protocol.game.ServerboundPaddleBoatPacket
+ XXX.protocol.game.ServerboundPickItemFromBlockPacket
- XXX.protocol.game.ServerboundPickItemFromEntityPacket
+ XXX.protocol.game.ServerboundPlaceRecipePacket
- XXX.protocol.game.ServerboundPlayerAbilitiesPacket
+ XXX.protocol.game.ServerboundPlayerActionPacket
- XXX.protocol.game.ServerboundPlayerActionPacket$Action
+ XXX.protocol.game.ServerboundPlayerCommandPacket
- XXX.protocol.game.ServerboundPlayerCommandPacket$Action
+ XXX.protocol.game.ServerboundPlayerInputPacket
- XXX.protocol.game.ServerboundPlayerLoadedPacket
+ XXX.protocol.game.ServerboundRecipeBookChangeSettingsPacket
- XXX.protocol.game.ServerboundRecipeBookSeenRecipePacket
+ XXX.protocol.game.ServerboundRenameItemPacket
- XXX.protocol.game.ServerboundSeenAdvancementsPacket
+ XXX.protocol.game.ServerboundSeenAdvancementsPacket$Action
- XXX.protocol.game.ServerboundSelectBundleItemPacket
+ XXX.protocol.game.ServerboundSelectTradePacket
- XXX.protocol.game.ServerboundSetBeaconPacket
+ XXX.protocol.game.ServerboundSetCarriedItemPacket
- XXX.protocol.game.ServerboundSetCommandBlockPacket
+ XXX.protocol.game.ServerboundSetCommandMinecartPacket
- XXX.protocol.game.ServerboundSetCreativeModeSlotPacket
+ XXX.protocol.game.ServerboundSetJigsawBlockPacket
- XXX.protocol.game.ServerboundSetStructureBlockPacket
+ XXX.protocol.game.ServerboundSetTestBlockPacket
- XXX.protocol.game.ServerboundSignUpdatePacket
+ XXX.protocol.game.ServerboundSwingPacket
- XXX.protocol.game.ServerboundTeleportToEntityPacket
+ XXX.protocol.game.ServerboundTestInstanceBlockActionPacket
- XXX.protocol.game.ServerboundTestInstanceBlockActionPacket$Action
+ XXX.protocol.game.ServerboundUseItemOnPacket
- XXX.protocol.game.ServerboundUseItemPacket
+ XXX.protocol.game.ServerGamePacketListener
- XXX.protocol.game.ServerPacketListener
+ XXX.protocol.game.VecDeltaCodec
+ XXX.protocol.handshake.ClientIntent
- XXX.protocol.handshake.ClientIntentionPacket
+ XXX.protocol.handshake.HandshakePacketTypes
- XXX.protocol.handshake.HandshakeProtocols
- XXX.protocol.handshake.package-info
+ XXX.protocol.handshake.ServerHandshakePacketListener
- XXX.protocol.login.ClientboundCustomQueryPacket
+ XXX.protocol.login.ClientboundHelloPacket
- XXX.protocol.login.ClientboundLoginCompressionPacket
+ XXX.protocol.login.ClientboundLoginDisconnectPacket
- XXX.protocol.login.ClientboundLoginFinishedPacket
+ XXX.protocol.login.ClientLoginPacketListener
+ XXX.protocol.login.LoginPacketTypes
- XXX.protocol.login.LoginProtocols
+ XXX.protocol.login.package-info
- XXX.protocol.login.ServerboundCustomQueryAnswerPacket
+ XXX.protocol.login.ServerboundHelloPacket
- XXX.protocol.login.ServerboundKeyPacket
+ XXX.protocol.login.ServerboundLoginAcknowledgedPacket
+ XXX.protocol.login.ServerLoginPacketListener
- XXX.protocol.ping.ClientboundPongResponsePacket
+ XXX.protocol.ping.ClientPongPacketListener
- XXX.protocol.ping.package-info
+ XXX.protocol.ping.PingPacketTypes
+ XXX.protocol.ping.ServerboundPingRequestPacket
- XXX.protocol.ping.ServerPingPacketListener
- XXX.protocol.status.ClientboundStatusResponsePacket
+ XXX.protocol.status.ClientStatusPacketListener
+ XXX.protocol.status.package-info
- XXX.protocol.status.ServerboundStatusRequestPacket
+ XXX.protocol.status.ServerStatus
- XXX.protocol.status.ServerStatus$Favicon
+ XXX.protocol.status.ServerStatus$Players
- XXX.protocol.status.ServerStatus$Version
+ XXX.protocol.status.ServerStatusPacketListener
+ XXX.protocol.status.StatusPacketTypes
- XXX.protocol.status.StatusProtocols
- XXX.realmsclient.client.FileDownload
+ XXX.realmsclient.client.FileDownload$DownloadCountingOutputStream
- XXX.realmsclient.client.FileDownload$ProgressListener
+ XXX.realmsclient.client.FileDownload$ResourcePackProgressListener
- XXX.realmsclient.client.FileUpload
+ XXX.realmsclient.client.FileUpload$CustomInputStreamEntity
+ XXX.realmsclient.client.package-info
- XXX.realmsclient.client.Ping
+ XXX.realmsclient.client.Ping$Region
- XXX.realmsclient.client.RealmsClient
+ XXX.realmsclient.client.RealmsClient$CompatibleVersionResponse
- XXX.realmsclient.client.RealmsClient$Environment
+ XXX.realmsclient.client.RealmsClientConfig
- XXX.realmsclient.client.RealmsError
+ XXX.realmsclient.client.RealmsError$AuthenticationError
- XXX.realmsclient.client.RealmsError$CustomError
+ XXX.realmsclient.client.RealmsError$ErrorWithJsonPayload
- XXX.realmsclient.client.RealmsError$ErrorWithRawPayload
+ XXX.realmsclient.client.Request
- XXX.realmsclient.client.Request$Delete
+ XXX.realmsclient.client.Request$Get
- XXX.realmsclient.client.Request$Post
+ XXX.realmsclient.client.Request$Put
- XXX.realmsclient.client.UploadStatus
+ XXX.realmsclient.dto.Backup
- XXX.realmsclient.dto.BackupList
+ XXX.realmsclient.dto.Exclude
- XXX.realmsclient.dto.GuardedSerializer
+ XXX.realmsclient.dto.GuardedSerializer$1
- XXX.realmsclient.dto.Ops
+ XXX.realmsclient.dto.package-info
+ XXX.realmsclient.dto.PendingInvite
- XXX.realmsclient.dto.PendingInvitesList
+ XXX.realmsclient.dto.PingResult
- XXX.realmsclient.dto.PlayerInfo
+ XXX.realmsclient.dto.PreferredRegionsDto
- XXX.realmsclient.dto.RealmsConfigurationDto
+ XXX.realmsclient.dto.RealmsDescriptionDto
- XXX.realmsclient.dto.RealmsJoinInformation
+ XXX.realmsclient.dto.RealmsJoinInformation$RegionData
- XXX.realmsclient.dto.RealmsNews
+ XXX.realmsclient.dto.RealmsNotification
- XXX.realmsclient.dto.RealmsNotification$InfoPopup
+ XXX.realmsclient.dto.RealmsNotification$UrlButton
- XXX.realmsclient.dto.RealmsNotification$VisitUrl
+ XXX.realmsclient.dto.RealmsRegion
- XXX.realmsclient.dto.RealmsRegion$RealmsRegionJsonAdapter
+ XXX.realmsclient.dto.RealmsServer
- XXX.realmsclient.dto.RealmsServer$Compatibility
+ XXX.realmsclient.dto.RealmsServer$McoServerComparator
- XXX.realmsclient.dto.RealmsServer$State
+ XXX.realmsclient.dto.RealmsServer$WorldType
- XXX.realmsclient.dto.RealmsServerList
+ XXX.realmsclient.dto.RealmsServerPlayerLists
- XXX.realmsclient.dto.RealmsSetting
+ XXX.realmsclient.dto.RealmsSlot
- XXX.realmsclient.dto.RealmsSlot$RealmsWorldOptionsJsonAdapter
+ XXX.realmsclient.dto.RealmsSlotUpdateDto
- XXX.realmsclient.dto.RealmsText
+ XXX.realmsclient.dto.RealmsWorldOptions
- XXX.realmsclient.dto.RealmsWorldResetDto
+ XXX.realmsclient.dto.ReflectionBasedSerialization
- XXX.realmsclient.dto.RegionDataDto
+ XXX.realmsclient.dto.RegionPingResult
- XXX.realmsclient.dto.RegionSelectionPreference
+ XXX.realmsclient.dto.RegionSelectionPreference$RegionSelectionPreferenceJsonAdapter
- XXX.realmsclient.dto.RegionSelectionPreferenceDto
+ XXX.realmsclient.dto.ServerActivity
- XXX.realmsclient.dto.ServerActivityList
+ XXX.realmsclient.dto.ServiceQuality
- XXX.realmsclient.dto.ServiceQuality$RealmsServiceQualityJsonAdapter
+ XXX.realmsclient.dto.Subscription
- XXX.realmsclient.dto.Subscription$SubscriptionType
+ XXX.realmsclient.dto.UploadInfo
- XXX.realmsclient.dto.ValueObject
+ XXX.realmsclient.dto.WorldDownload
- XXX.realmsclient.dto.WorldTemplate
+ XXX.realmsclient.dto.WorldTemplate$WorldTemplateType
- XXX.realmsclient.dto.WorldTemplatePaginatedList
- XXX.realmsclient.exception.package-info
- XXX.realmsclient.exception.RealmsDefaultUncaughtExceptionHandler
+ XXX.realmsclient.exception.RealmsHttpException
- XXX.realmsclient.exception.RealmsServiceException
+ XXX.realmsclient.exception.RetryCallException
- XXX.realmsclient.gui.package-info
+ XXX.realmsclient.gui.RealmsDataFetcher
- XXX.realmsclient.gui.RealmsDataFetcher$ServerListData
+ XXX.realmsclient.gui.RealmsNewsManager
- XXX.realmsclient.gui.RealmsServerList
+ XXX.realmsclient.gui.RealmsWorldSlotButton
- XXX.realmsclient.gui.RealmsWorldSlotButton$Action
+ XXX.realmsclient.gui.RealmsWorldSlotButton$State
+ XXX.realmsclient.util.JsonUtils
- XXX.realmsclient.util.LevelType
- XXX.realmsclient.util.package-info
+ XXX.realmsclient.util.RealmsPersistence
- XXX.realmsclient.util.RealmsPersistence$RealmsPersistenceData
+ XXX.realmsclient.util.RealmsTextureManager
- XXX.realmsclient.util.RealmsTextureManager$RealmsTexture
+ XXX.realmsclient.util.RealmsUtil
- XXX.realmsclient.util.RealmsUtil$RealmsIoConsumer
+ XXX.realmsclient.util.RealmsUtil$RealmsIoFunction
- XXX.realmsclient.util.TextRenderingUtils
+ XXX.realmsclient.util.TextRenderingUtils$Line
- XXX.realmsclient.util.TextRenderingUtils$LineSegment
+ XXX.realmsclient.util.UploadTokenCache
- XXX.recipes.packs.package-info
+ XXX.recipes.packs.VanillaRecipeProvider
- XXX.recipes.packs.VanillaRecipeProvider$Runner
+ XXX.recipes.packs.VanillaRecipeProvider$TrimTemplate
- XXX.renderer.block.BlockModelShaper
+ XXX.renderer.block.BlockRenderDispatcher
- XXX.renderer.block.LiquidBlockRenderer
+ XXX.renderer.block.LiquidBlockRenderer$1
- XXX.renderer.block.ModelBlockRenderer
+ XXX.renderer.block.ModelBlockRenderer$1
- XXX.renderer.block.ModelBlockRenderer$AdjacencyInfo
+ XXX.renderer.block.ModelBlockRenderer$AmbientOcclusionRenderStorage
- XXX.renderer.block.ModelBlockRenderer$AmbientVertexRemap
+ XXX.renderer.block.ModelBlockRenderer$Cache
- XXX.renderer.block.ModelBlockRenderer$Cache$1
+ XXX.renderer.block.ModelBlockRenderer$Cache$2
- XXX.renderer.block.ModelBlockRenderer$CommonRenderStorage
+ XXX.renderer.block.ModelBlockRenderer$SizeInfo
- XXX.renderer.block.MovingBlockRenderState
+ XXX.renderer.block.package-info
- XXX.renderer.blockentity.AbstractEndPortalRenderer
- XXX.renderer.blockentity.ConduitRenderer
+ XXX.renderer.blockentity.CopperGolemStatueBlockRenderer
- XXX.renderer.blockentity.DecoratedPotRenderer
+ XXX.renderer.blockentity.EnchantTableRenderer
- XXX.renderer.blockentity.HangingSignRenderer
+ XXX.renderer.blockentity.HangingSignRenderer$AttachmentType
- XXX.renderer.blockentity.HangingSignRenderer$ModelKey
+ XXX.renderer.blockentity.LecternRenderer
- XXX.renderer.blockentity.package-info
- XXX.renderer.blockentity.PistonHeadRenderer
+ XXX.renderer.blockentity.ShelfRenderer
- XXX.renderer.blockentity.ShulkerBoxRenderer
+ XXX.renderer.blockentity.ShulkerBoxRenderer$ShulkerBoxModel
- XXX.renderer.blockentity.SignRenderer
+ XXX.renderer.blockentity.SignRenderer$Models
- XXX.renderer.blockentity.SkullBlockRenderer
+ XXX.renderer.blockentity.SkullBlockRenderer$1
- XXX.renderer.blockentity.SpawnerRenderer
+ XXX.renderer.blockentity.TestInstanceRenderer
- XXX.renderer.blockentity.TheEndGatewayRenderer
+ XXX.renderer.blockentity.TheEndPortalRenderer
- XXX.renderer.blockentity.TrialSpawnerRenderer
+ XXX.renderer.blockentity.VaultRenderer
+ XXX.renderer.chunk.ChunkSectionLayer
- XXX.renderer.chunk.ChunkSectionLayerGroup
+ XXX.renderer.chunk.ChunkSectionsToRender
+ XXX.renderer.chunk.CompiledSectionMesh
- XXX.renderer.chunk.CompiledSectionMesh$1
+ XXX.renderer.chunk.CompiledSectionMesh$2
- XXX.renderer.chunk.CompileTaskDynamicQueue
+ XXX.renderer.chunk.package-info
- XXX.renderer.chunk.RenderRegionCache
+ XXX.renderer.chunk.RenderSectionRegion
- XXX.renderer.chunk.SectionBuffers
+ XXX.renderer.chunk.SectionCompiler
- XXX.renderer.chunk.SectionCompiler$Results
+ XXX.renderer.chunk.SectionCopy
- XXX.renderer.chunk.SectionMesh
+ XXX.renderer.chunk.SectionRenderDispatcher
- XXX.renderer.chunk.SectionRenderDispatcher$RenderSection
+ XXX.renderer.chunk.SectionRenderDispatcher$RenderSection$CompileTask
- XXX.renderer.chunk.SectionRenderDispatcher$RenderSection$RebuildTask
+ XXX.renderer.chunk.SectionRenderDispatcher$RenderSection$ResortTransparencyTask
- XXX.renderer.chunk.SectionRenderDispatcher$SectionTaskResult
+ XXX.renderer.chunk.TranslucencyPointOfView
- XXX.renderer.chunk.VisGraph
+ XXX.renderer.chunk.VisGraph$1
- XXX.renderer.chunk.VisibilitySet
- XXX.renderer.culling.Frustum
+ XXX.renderer.culling.package-info
- XXX.renderer.debug.BeeDebugRenderer
+ XXX.renderer.debug.BeeDebugRenderer$HiveDebugInfo
- XXX.renderer.debug.BrainDebugRenderer
+ XXX.renderer.debug.BrainDebugRenderer$PoiInfo
- XXX.renderer.debug.BreezeDebugRenderer
+ XXX.renderer.debug.ChunkBorderRenderer
- XXX.renderer.debug.ChunkCullingDebugRenderer
+ XXX.renderer.debug.ChunkDebugRenderer
- XXX.renderer.debug.ChunkDebugRenderer$ChunkData
+ XXX.renderer.debug.CollisionBoxRenderer
- XXX.renderer.debug.DebugRenderer
+ XXX.renderer.debug.DebugRenderer$SimpleDebugRenderer
- XXX.renderer.debug.GameEventListenerRenderer
+ XXX.renderer.debug.GameEventListenerRenderer$TrackedGameEvent
- XXX.renderer.debug.GameEventListenerRenderer$TrackedListener
+ XXX.renderer.debug.GameTestDebugRenderer
- XXX.renderer.debug.GameTestDebugRenderer$Marker
+ XXX.renderer.debug.GoalSelectorDebugRenderer
- XXX.renderer.debug.GoalSelectorDebugRenderer$EntityGoalInfo
+ XXX.renderer.debug.HeightMapRenderer
- XXX.renderer.debug.HeightMapRenderer$1
+ XXX.renderer.debug.LightDebugRenderer
- XXX.renderer.debug.LightSectionDebugRenderer
+ XXX.renderer.debug.LightSectionDebugRenderer$SectionData
- XXX.renderer.debug.NeighborsUpdateRenderer
+ XXX.renderer.debug.OctreeDebugRenderer
+ XXX.renderer.debug.package-info
- XXX.renderer.debug.PathfindingRenderer
+ XXX.renderer.debug.RaidDebugRenderer
- XXX.renderer.debug.RedstoneWireOrientationsRenderer
+ XXX.renderer.debug.SolidFaceRenderer
- XXX.renderer.debug.StructureRenderer
+ XXX.renderer.debug.SupportBlockRenderer
- XXX.renderer.debug.VillageSectionsDebugRenderer
+ XXX.renderer.debug.WaterDebugRenderer
- XXX.renderer.debug.WorldGenAttemptRenderer
- XXX.renderer.entity.AbstractBoatRenderer
+ XXX.renderer.entity.AbstractHoglinRenderer
- XXX.renderer.entity.AbstractHorseRenderer
+ XXX.renderer.entity.AbstractMinecartRenderer
- XXX.renderer.entity.AbstractSkeletonRenderer
+ XXX.renderer.entity.AbstractZombieRenderer
- XXX.renderer.entity.AgeableMobRenderer
+ XXX.renderer.entity.AllayRenderer
- XXX.renderer.entity.ArmadilloRenderer
+ XXX.renderer.entity.ArmorModelSet
- XXX.renderer.entity.ArmorModelSet$1
+ XXX.renderer.entity.ArmorStandRenderer
- XXX.renderer.entity.ArrowRenderer
+ XXX.renderer.entity.AxolotlRenderer
- XXX.renderer.entity.BatRenderer
+ XXX.renderer.entity.BeeRenderer
- XXX.renderer.entity.BlazeRenderer
+ XXX.renderer.entity.BoatRenderer
- XXX.renderer.entity.BoggedRenderer
+ XXX.renderer.entity.BreezeRenderer
- XXX.renderer.entity.CamelRenderer
+ XXX.renderer.entity.CatRenderer
- XXX.renderer.entity.CaveSpiderRenderer
+ XXX.renderer.entity.ChickenRenderer
- XXX.renderer.entity.CodRenderer
+ XXX.renderer.entity.CopperGolemRenderer
- XXX.renderer.entity.CowRenderer
+ XXX.renderer.entity.CreakingRenderer
- XXX.renderer.entity.CreeperRenderer
+ XXX.renderer.entity.DisplayRenderer
- XXX.renderer.entity.DisplayRenderer$1
+ XXX.renderer.entity.DisplayRenderer$BlockDisplayRenderer
- XXX.renderer.entity.DisplayRenderer$ItemDisplayRenderer
+ XXX.renderer.entity.DisplayRenderer$TextDisplayRenderer
- XXX.renderer.entity.DolphinRenderer
+ XXX.renderer.entity.DonkeyRenderer
- XXX.renderer.entity.DonkeyRenderer$Type
+ XXX.renderer.entity.DragonFireballRenderer
- XXX.renderer.entity.DrownedRenderer
+ XXX.renderer.entity.ElderGuardianRenderer
- XXX.renderer.entity.EndCrystalRenderer
+ XXX.renderer.entity.EnderDragonRenderer
- XXX.renderer.entity.EndermanRenderer
+ XXX.renderer.entity.EndermiteRenderer
- XXX.renderer.entity.EntityRenderDispatcher
+ XXX.renderer.entity.EntityRenderer
- XXX.renderer.entity.EntityRendererProvider
+ XXX.renderer.entity.EntityRendererProvider$Context
- XXX.renderer.entity.EntityRenderers
+ XXX.renderer.entity.EvokerFangsRenderer
- XXX.renderer.entity.EvokerRenderer
+ XXX.renderer.entity.EvokerRenderer$1
- XXX.renderer.entity.ExperienceOrbRenderer
+ XXX.renderer.entity.FallingBlockRenderer
- XXX.renderer.entity.FireworkEntityRenderer
+ XXX.renderer.entity.FishingHookRenderer
- XXX.renderer.entity.FoxRenderer
+ XXX.renderer.entity.FrogRenderer
- XXX.renderer.entity.GhastRenderer
+ XXX.renderer.entity.GiantMobRenderer
- XXX.renderer.entity.GlowSquidRenderer
+ XXX.renderer.entity.GoatRenderer
- XXX.renderer.entity.GuardianRenderer
+ XXX.renderer.entity.HappyGhastRenderer
- XXX.renderer.entity.HoglinRenderer
+ XXX.renderer.entity.HorseRenderer
- XXX.renderer.entity.HumanoidMobRenderer
+ XXX.renderer.entity.HuskRenderer
- XXX.renderer.entity.IllagerRenderer
+ XXX.renderer.entity.IllusionerRenderer
- XXX.renderer.entity.IllusionerRenderer$1
+ XXX.renderer.entity.IronGolemRenderer
- XXX.renderer.entity.ItemEntityRenderer
+ XXX.renderer.entity.ItemFrameRenderer
- XXX.renderer.entity.ItemRenderer
+ XXX.renderer.entity.LeashKnotRenderer
- XXX.renderer.entity.LightningBoltRenderer
+ XXX.renderer.entity.LivingEntityRenderer
- XXX.renderer.entity.LivingEntityRenderer$1
+ XXX.renderer.entity.LlamaRenderer
- XXX.renderer.entity.LlamaRenderer$1
+ XXX.renderer.entity.LlamaSpitRenderer
- XXX.renderer.entity.MagmaCubeRenderer
+ XXX.renderer.entity.MinecartRenderer
- XXX.renderer.entity.MobRenderer
+ XXX.renderer.entity.MushroomCowRenderer
- XXX.renderer.entity.NoopRenderer
+ XXX.renderer.entity.OcelotRenderer
- XXX.renderer.entity.OminousItemSpawnerRenderer
+ XXX.renderer.entity.package-info
+ XXX.renderer.entity.PaintingRenderer
- XXX.renderer.entity.PaintingRenderer$1
+ XXX.renderer.entity.PandaRenderer
- XXX.renderer.entity.ParrotRenderer
+ XXX.renderer.entity.ParrotRenderer$1
- XXX.renderer.entity.PhantomRenderer
- XXX.renderer.entity.PiglinRenderer
+ XXX.renderer.entity.PigRenderer
+ XXX.renderer.entity.PillagerRenderer
- XXX.renderer.entity.PolarBearRenderer
+ XXX.renderer.entity.PufferfishRenderer
- XXX.renderer.entity.RabbitRenderer
+ XXX.renderer.entity.RabbitRenderer$1
- XXX.renderer.entity.RaftRenderer
+ XXX.renderer.entity.RavagerRenderer
- XXX.renderer.entity.RenderLayerParent
+ XXX.renderer.entity.SalmonRenderer
- XXX.renderer.entity.SalmonRenderer$1
+ XXX.renderer.entity.SheepRenderer
- XXX.renderer.entity.ShulkerBulletRenderer
+ XXX.renderer.entity.ShulkerRenderer
- XXX.renderer.entity.SilverfishRenderer
+ XXX.renderer.entity.SkeletonRenderer
- XXX.renderer.entity.SlimeRenderer
+ XXX.renderer.entity.SnifferRenderer
- XXX.renderer.entity.SnowGolemRenderer
+ XXX.renderer.entity.SpectralArrowRenderer
- XXX.renderer.entity.SpiderRenderer
+ XXX.renderer.entity.SquidRenderer
- XXX.renderer.entity.StrayRenderer
+ XXX.renderer.entity.StriderRenderer
- XXX.renderer.entity.TadpoleRenderer
+ XXX.renderer.entity.ThrownItemRenderer
- XXX.renderer.entity.ThrownTridentRenderer
+ XXX.renderer.entity.TippableArrowRenderer
- XXX.renderer.entity.TntMinecartRenderer
+ XXX.renderer.entity.TntRenderer
- XXX.renderer.entity.TropicalFishRenderer
+ XXX.renderer.entity.TropicalFishRenderer$1
- XXX.renderer.entity.TurtleRenderer
+ XXX.renderer.entity.UndeadHorseRenderer
- XXX.renderer.entity.UndeadHorseRenderer$Type
+ XXX.renderer.entity.VexRenderer
- XXX.renderer.entity.VillagerRenderer
+ XXX.renderer.entity.VindicatorRenderer
- XXX.renderer.entity.VindicatorRenderer$1
+ XXX.renderer.entity.WanderingTraderRenderer
- XXX.renderer.entity.WardenRenderer
+ XXX.renderer.entity.WindChargeRenderer
- XXX.renderer.entity.WitchRenderer
+ XXX.renderer.entity.WitherBossRenderer
- XXX.renderer.entity.WitherSkeletonRenderer
+ XXX.renderer.entity.WitherSkullRenderer
- XXX.renderer.entity.WolfRenderer
+ XXX.renderer.entity.ZoglinRenderer
- XXX.renderer.entity.ZombieRenderer
+ XXX.renderer.entity.ZombieVillagerRenderer
- XXX.renderer.entity.ZombifiedPiglinRenderer
+ XXX.renderer.feature.BlockFeatureRenderer
- XXX.renderer.feature.CustomFeatureRenderer
+ XXX.renderer.feature.FeatureRenderDispatcher
- XXX.renderer.feature.FlameFeatureRenderer
+ XXX.renderer.feature.HitboxFeatureRenderer
- XXX.renderer.feature.ItemFeatureRenderer
+ XXX.renderer.feature.LeashFeatureRenderer
- XXX.renderer.feature.ModelFeatureRenderer
+ XXX.renderer.feature.ModelFeatureRenderer$CrumblingOverlay
- XXX.renderer.feature.ModelPartFeatureRenderer
+ XXX.renderer.feature.NameTagFeatureRenderer
- XXX.renderer.feature.ParticleFeatureRenderer
+ XXX.resources.language.ClientLanguage
- XXX.resources.language.FormattedBidiReorder
+ XXX.resources.language.I18n
- XXX.resources.language.LanguageInfo
+ XXX.resources.language.LanguageManager
- XXX.resources.language.package-info
+ XXX.resources.metadata.package-info
- XXX.resources.model.AtlasManager
+ XXX.resources.model.AtlasManager$AtlasConfig
- XXX.resources.model.AtlasManager$AtlasEntry
+ XXX.resources.model.AtlasManager$PendingStitch
- XXX.resources.model.AtlasManager$PendingStitchResults
+ XXX.resources.model.BlockModelRotation
- XXX.resources.model.BlockModelRotation$WithUvLock
+ XXX.resources.model.BlockStateDefinitions
- XXX.resources.model.BlockStateModelLoader
+ XXX.resources.model.BlockStateModelLoader$LoadedBlockModelDefinition
- XXX.resources.model.BlockStateModelLoader$LoadedModels
+ XXX.resources.model.ClientItemInfoLoader
- XXX.resources.model.ClientItemInfoLoader$LoadedClientInfos
+ XXX.resources.model.ClientItemInfoLoader$PendingLoad
- XXX.resources.model.EquipmentAssetManager
+ XXX.resources.model.EquipmentClientInfo
- XXX.resources.model.EquipmentClientInfo$Builder
+ XXX.resources.model.EquipmentClientInfo$Dyeable
- XXX.resources.model.EquipmentClientInfo$Layer
+ XXX.resources.model.EquipmentClientInfo$LayerType
- XXX.resources.model.Material
+ XXX.resources.model.MaterialSet
- XXX.resources.model.MissingBlockModel
+ XXX.resources.model.ModelBaker
- XXX.resources.model.ModelBaker$SharedOperationKey
+ XXX.resources.model.ModelBakery
- XXX.resources.model.ModelBakery$BakingResult
+ XXX.resources.model.ModelBakery$MissingModels
- XXX.resources.model.ModelBakery$MissingModels$1
+ XXX.resources.model.ModelBakery$ModelBakerImpl
- XXX.resources.model.ModelDebugName
+ XXX.resources.model.ModelDiscovery
- XXX.resources.model.ModelDiscovery$ModelWrapper
+ XXX.resources.model.ModelDiscovery$Slot
- XXX.resources.model.ModelGroupCollector
+ XXX.resources.model.ModelGroupCollector$GroupKey
- XXX.resources.model.ModelManager
+ XXX.resources.model.ModelManager$1
- XXX.resources.model.ModelManager$ReloadState
+ XXX.resources.model.ModelManager$ResolvedModels
- XXX.resources.model.ModelState
- XXX.resources.model.package-info
+ XXX.resources.model.QuadCollection
- XXX.resources.model.QuadCollection$Builder
+ XXX.resources.model.ResolvableModel
- XXX.resources.model.ResolvableModel$Resolver
+ XXX.resources.model.ResolvedModel
- XXX.resources.model.SpriteGetter
+ XXX.resources.model.UnbakedGeometry
- XXX.resources.model.UnbakedModel
+ XXX.resources.model.UnbakedModel$GuiLight
- XXX.resources.model.WeightedVariants
+ XXX.resources.model.WeightedVariants$Unbaked
- XXX.resources.server.DownloadedPackSource
+ XXX.resources.server.DownloadedPackSource$1
- XXX.resources.server.DownloadedPackSource$2
+ XXX.resources.server.DownloadedPackSource$3
- XXX.resources.server.DownloadedPackSource$4
+ XXX.resources.server.DownloadedPackSource$5
- XXX.resources.server.DownloadedPackSource$6
+ XXX.resources.server.DownloadedPackSource$7
- XXX.resources.server.DownloadedPackSource$8
+ XXX.resources.server.package-info
+ XXX.resources.server.PackDownloader
- XXX.resources.server.PackLoadFeedback
+ XXX.resources.server.PackLoadFeedback$FinalResult
- XXX.resources.server.PackLoadFeedback$Update
+ XXX.resources.server.PackReloadConfig
- XXX.resources.server.PackReloadConfig$Callbacks
+ XXX.resources.server.PackReloadConfig$IdAndPath
- XXX.resources.server.ServerPackManager
+ XXX.resources.server.ServerPackManager$1
- XXX.resources.server.ServerPackManager$ActivationStatus
+ XXX.resources.server.ServerPackManager$PackDownloadStatus
- XXX.resources.server.ServerPackManager$PackPromptStatus
+ XXX.resources.server.ServerPackManager$RemovalReason
- XXX.resources.server.ServerPackManager$ServerPackData
- XXX.resources.sounds.AbstractSoundInstance
+ XXX.resources.sounds.AbstractTickableSoundInstance
- XXX.resources.sounds.AmbientSoundHandler
+ XXX.resources.sounds.BeeAggressiveSoundInstance
- XXX.resources.sounds.BeeFlyingSoundInstance
+ XXX.resources.sounds.BeeSoundInstance
- XXX.resources.sounds.BiomeAmbientSoundsHandler
+ XXX.resources.sounds.BiomeAmbientSoundsHandler$LoopSoundInstance
- XXX.resources.sounds.BubbleColumnAmbientSoundHandler
+ XXX.resources.sounds.DirectionalSoundInstance
- XXX.resources.sounds.ElytraOnPlayerSoundInstance
+ XXX.resources.sounds.EntityBoundSoundInstance
- XXX.resources.sounds.GuardianAttackSoundInstance
+ XXX.resources.sounds.MinecartSoundInstance
+ XXX.resources.sounds.package-info
- XXX.resources.sounds.RidingHappyGhastSoundInstance
+ XXX.resources.sounds.RidingMinecartSoundInstance
- XXX.resources.sounds.SimpleSoundInstance
+ XXX.resources.sounds.SnifferSoundInstance
- XXX.resources.sounds.Sound
+ XXX.resources.sounds.Sound$Type
- XXX.resources.sounds.SoundEventRegistration
+ XXX.resources.sounds.SoundEventRegistrationSerializer
- XXX.resources.sounds.SoundInstance
+ XXX.resources.sounds.SoundInstance$Attenuation
- XXX.resources.sounds.TickableSoundInstance
+ XXX.resources.sounds.UnderwaterAmbientSoundHandler
- XXX.resources.sounds.UnderwaterAmbientSoundInstances
+ XXX.resources.sounds.UnderwaterAmbientSoundInstances$SubSound
- XXX.resources.sounds.UnderwaterAmbientSoundInstances$UnderwaterAmbientSoundInstance
- XXX.screens.configuration.package-info
+ XXX.screens.configuration.RealmsBackupInfoScreen
- XXX.screens.configuration.RealmsBackupInfoScreen$BackupInfoList
+ XXX.screens.configuration.RealmsBackupInfoScreen$BackupInfoListEntry
- XXX.screens.configuration.RealmsBackupScreen
+ XXX.screens.configuration.RealmsBackupScreen$1
- XXX.screens.configuration.RealmsBackupScreen$BackupObjectSelectionList
+ XXX.screens.configuration.RealmsBackupScreen$Entry
- XXX.screens.configuration.RealmsConfigurationTab
+ XXX.screens.configuration.RealmsConfigureWorldScreen
- XXX.screens.configuration.RealmsInviteScreen
+ XXX.screens.configuration.RealmsPlayersTab
- XXX.screens.configuration.RealmsPlayersTab$Entry
+ XXX.screens.configuration.RealmsPlayersTab$HeaderEntry
- XXX.screens.configuration.RealmsPlayersTab$InvitedObjectSelectionList
+ XXX.screens.configuration.RealmsPlayersTab$PlayerEntry
- XXX.screens.configuration.RealmsPreferredRegionSelectionScreen
+ XXX.screens.configuration.RealmsPreferredRegionSelectionScreen$RegionSelectionList
- XXX.screens.configuration.RealmsPreferredRegionSelectionScreen$RegionSelectionList$Entry
+ XXX.screens.configuration.RealmsSettingsTab
- XXX.screens.configuration.RealmsSettingsTab$RegionSelection
+ XXX.screens.configuration.RealmsSlotOptionsScreen
- XXX.screens.configuration.RealmsSlotOptionsScreen$SettingsSlider
+ XXX.screens.configuration.RealmsSubscriptionTab
- XXX.screens.configuration.RealmsWorldsTab
+ XXX.screens.configuration.RealmsWorldsTab$1
+ XXX.selector.options.EntitySelectorOptions
- XXX.selector.options.EntitySelectorOptions$Modifier
+ XXX.selector.options.EntitySelectorOptions$Option
- XXX.selector.options.package-info
- XXX.synchronization.brigadier.DoubleArgumentInfo
+ XXX.synchronization.brigadier.DoubleArgumentInfo$Template
- XXX.synchronization.brigadier.FloatArgumentInfo
+ XXX.synchronization.brigadier.FloatArgumentInfo$Template
- XXX.synchronization.brigadier.IntegerArgumentInfo
+ XXX.synchronization.brigadier.IntegerArgumentInfo$Template
- XXX.synchronization.brigadier.LongArgumentInfo
+ XXX.synchronization.brigadier.LongArgumentInfo$Template
+ XXX.synchronization.brigadier.package-info
- XXX.synchronization.brigadier.StringArgumentSerializer
+ XXX.synchronization.brigadier.StringArgumentSerializer$1
- XXX.synchronization.brigadier.StringArgumentSerializer$Template
- XXX.telemetry.events.AggregatedTelemetryEvent
+ XXX.telemetry.events.GameLoadTimesEvent
- XXX.telemetry.events.GameLoadTimesEvent$Measurement
- XXX.telemetry.events.package-info
+ XXX.telemetry.events.PerformanceMetricsEvent
- XXX.telemetry.events.WorldLoadEvent
+ XXX.telemetry.events.WorldLoadEvent$1
- XXX.telemetry.events.WorldLoadTimesEvent
+ XXX.telemetry.events.WorldUnloadEvent
+ XXX.util.context.ContextKey
- XXX.util.context.ContextKeySet
+ XXX.util.context.ContextKeySet$Builder
- XXX.util.context.ContextMap
+ XXX.util.context.ContextMap$Builder
- XXX.util.context.package-info
+ XXX.util.datafix.DataFixers
- XXX.util.datafix.DataFixers$1
+ XXX.util.datafix.DataFixers$2
+ XXX.util.datafix.DataFixTypes
- XXX.util.datafix.DataFixTypes$1
- XXX.util.datafix.ExtraDataFixUtils
+ XXX.util.datafix.LegacyComponentDataFixUtils
- XXX.util.datafix.PackedBitStorage
- XXX.util.debugchart.AbstractSampleLogger
+ XXX.util.debugchart.DebugSampleSubscriptionTracker
- XXX.util.debugchart.DebugSampleSubscriptionTracker$SubscriptionRequest
+ XXX.util.debugchart.DebugSampleSubscriptionTracker$SubscriptionStartedAt
- XXX.util.debugchart.LocalSampleLogger
- XXX.util.debugchart.package-info
+ XXX.util.debugchart.RemoteDebugSampleType
- XXX.util.debugchart.RemoteSampleLogger
+ XXX.util.debugchart.SampleLogger
- XXX.util.debugchart.SampleStorage
+ XXX.util.debugchart.TpsDebugDimensions
+ XXX.util.eventlog.EventLogDirectory
- XXX.util.eventlog.EventLogDirectory$CompressedFile
+ XXX.util.eventlog.EventLogDirectory$File
- XXX.util.eventlog.EventLogDirectory$FileId
+ XXX.util.eventlog.EventLogDirectory$FileList
- XXX.util.eventlog.EventLogDirectory$RawFile
+ XXX.util.eventlog.JsonEventLog
- XXX.util.eventlog.JsonEventLog$1
+ XXX.util.eventlog.JsonEventLogReader
- XXX.util.eventlog.JsonEventLogReader$1
+ XXX.util.eventlog.package-info
- XXX.util.parsing.package-info
+ XXX.util.profiling.ActiveProfiler
- XXX.util.profiling.ActiveProfiler$PathEntry
+ XXX.util.profiling.ContinuousProfiler
- XXX.util.profiling.EmptyProfileResults
+ XXX.util.profiling.FilledProfileResults
- XXX.util.profiling.FilledProfileResults$1
+ XXX.util.profiling.FilledProfileResults$CounterCollector
- XXX.util.profiling.InactiveProfiler
+ XXX.util.profiling.package-info
+ XXX.util.profiling.ProfileCollector
+ XXX.util.profiling.Profiler
- XXX.util.profiling.Profiler$Scope
- XXX.util.profiling.ProfileResults
+ XXX.util.profiling.ProfilerFiller
- XXX.util.profiling.ProfilerFiller$CombinedProfileFiller
+ XXX.util.profiling.ProfilerPathEntry
- XXX.util.profiling.ResultField
+ XXX.util.profiling.SingleTickProfiler
- XXX.util.profiling.TracyZoneFiller
+ XXX.util.profiling.TracyZoneFiller$PlotAndValue
- XXX.util.profiling.Zone
+ XXX.util.random.package-info
- XXX.util.random.Weighted
+ XXX.util.random.WeightedList
- XXX.util.random.WeightedList$Builder
+ XXX.util.random.WeightedList$Compact
- XXX.util.random.WeightedList$Flat
+ XXX.util.random.WeightedList$Selector
- XXX.util.random.WeightedRandom
+ XXX.util.task.CloseServerTask
- XXX.util.task.ConnectTask
+ XXX.util.task.DownloadTask
- XXX.util.task.GetServerDetailsTask
+ XXX.util.task.LongRunningTask
- XXX.util.task.OpenServerTask
+ XXX.util.task.package-info
+ XXX.util.task.RealmCreationTask
- XXX.util.task.ResettingTemplateWorldTask
+ XXX.util.task.ResettingWorldTask
- XXX.util.task.RestoreTask
+ XXX.util.task.SwitchMinigameTask
- XXX.util.task.SwitchSlotTask
- XXX.util.thread.AbstractConsecutiveExecutor
+ XXX.util.thread.AbstractConsecutiveExecutor$Status
- XXX.util.thread.BlockableEventLoop
+ XXX.util.thread.ConsecutiveExecutor
- XXX.util.thread.NamedThreadFactory
- XXX.util.thread.package-info
+ XXX.util.thread.ParallelMapTransform
- XXX.util.thread.ParallelMapTransform$BatchedTaskSplitter
+ XXX.util.thread.ParallelMapTransform$Container
- XXX.util.thread.ParallelMapTransform$SingleTaskSplitter
+ XXX.util.thread.ParallelMapTransform$SplitterBase
- XXX.util.thread.PriorityConsecutiveExecutor
+ XXX.util.thread.ReentrantBlockableEventLoop
- XXX.util.thread.StrictQueue
+ XXX.util.thread.StrictQueue$FixedPriorityQueue
- XXX.util.thread.StrictQueue$QueueStrictQueue
+ XXX.util.thread.StrictQueue$RunnableWithPriority
- XXX.util.thread.TaskScheduler
+ XXX.util.thread.TaskScheduler$1
+ XXX.util.valueproviders.BiasedToBottomInt
- XXX.util.valueproviders.ClampedInt
+ XXX.util.valueproviders.ClampedNormalFloat
- XXX.util.valueproviders.ClampedNormalInt
+ XXX.util.valueproviders.ConstantFloat
- XXX.util.valueproviders.ConstantInt
+ XXX.util.valueproviders.FloatProvider
- XXX.util.valueproviders.FloatProviderType
+ XXX.util.valueproviders.IntProvider
- XXX.util.valueproviders.IntProviderType
+ XXX.util.valueproviders.MultipliedFloats
+ XXX.util.valueproviders.package-info
- XXX.util.valueproviders.SampledFloat
+ XXX.util.valueproviders.TrapezoidFloat
- XXX.util.valueproviders.UniformFloat
+ XXX.util.valueproviders.UniformInt
- XXX.util.valueproviders.WeightedListInt
- XXX.util.worldupdate.package-info
- XXX.util.worldupdate.WorldUpgrader
+ XXX.util.worldupdate.WorldUpgrader$AbstractUpgrader
- XXX.util.worldupdate.WorldUpgrader$ChunkUpgrader
+ XXX.util.worldupdate.WorldUpgrader$DimensionToUpgrade
- XXX.util.worldupdate.WorldUpgrader$EntityUpgrader
+ XXX.util.worldupdate.WorldUpgrader$FileToUpgrade
- XXX.util.worldupdate.WorldUpgrader$PoiUpgrader
+ XXX.util.worldupdate.WorldUpgrader$SimpleRegionStorageUpgrader
- XXX.world.damagesource.CombatEntry
+ XXX.world.damagesource.CombatRules
- XXX.world.damagesource.CombatTracker
+ XXX.world.damagesource.DamageEffects
- XXX.world.damagesource.DamageScaling
+ XXX.world.damagesource.DamageSource
- XXX.world.damagesource.DamageSource$1
+ XXX.world.damagesource.DamageSources
- XXX.world.damagesource.DamageType
+ XXX.world.damagesource.DamageTypes
- XXX.world.damagesource.DeathMessageType
+ XXX.world.damagesource.FallLocation
- XXX.world.damagesource.package-info
+ XXX.world.effect.AbsorptionMobEffect
- XXX.world.effect.BadOmenMobEffect
+ XXX.world.effect.HealOrHarmMobEffect
- XXX.world.effect.HungerMobEffect
+ XXX.world.effect.InfestedMobEffect
- XXX.world.effect.InstantenousMobEffect
+ XXX.world.effect.MobEffect
- XXX.world.effect.MobEffect$AttributeTemplate
+ XXX.world.effect.MobEffectCategory
- XXX.world.effect.MobEffectInstance
+ XXX.world.effect.MobEffectInstance$BlendState
- XXX.world.effect.MobEffectInstance$Details
- XXX.world.effect.MobEffects
+ XXX.world.effect.MobEffectUtil
+ XXX.world.effect.OozingMobEffect
- XXX.world.effect.OozingMobEffect$NearbySlimes
- XXX.world.effect.package-info
+ XXX.world.effect.PoisonMobEffect
- XXX.world.effect.RaidOmenMobEffect
+ XXX.world.effect.RegenerationMobEffect
- XXX.world.effect.SaturationMobEffect
+ XXX.world.effect.WeavingMobEffect
- XXX.world.effect.WindChargedMobEffect
+ XXX.world.effect.WitherMobEffect
+ XXX.world.entity.AgeableMob
- XXX.world.entity.AgeableMob$AgeableMobGroupData
+ XXX.world.entity.AnimationState
- XXX.world.entity.AreaEffectCloud
+ XXX.world.entity.Attackable
- XXX.world.entity.Avatar
- XXX.world.flag.FeatureElement
+ XXX.world.flag.FeatureFlag
- XXX.world.flag.FeatureFlagRegistry
+ XXX.world.flag.FeatureFlagRegistry$Builder
- XXX.world.flag.FeatureFlags
- XXX.world.flag.FeatureFlagSet
+ XXX.world.flag.FeatureFlagUniverse
+ XXX.world.flag.package-info
- XXX.world.food.FoodConstants
+ XXX.world.food.FoodData
- XXX.world.food.FoodProperties
+ XXX.world.food.FoodProperties$Builder
- XXX.world.food.Foods
+ XXX.world.food.package-info
- XXX.world.inventory.AbstractContainerMenu
+ XXX.world.inventory.AbstractContainerMenu$1
- XXX.world.inventory.AbstractCraftingMenu
+ XXX.world.inventory.AbstractCraftingMenu$1
- XXX.world.inventory.AbstractFurnaceMenu
+ XXX.world.inventory.AbstractFurnaceMenu$1
- XXX.world.inventory.AnvilMenu
+ XXX.world.inventory.ArmorSlot
- XXX.world.inventory.BeaconMenu
+ XXX.world.inventory.BeaconMenu$1
- XXX.world.inventory.BeaconMenu$PaymentSlot
+ XXX.world.inventory.BlastFurnaceMenu
- XXX.world.inventory.BrewingStandMenu
+ XXX.world.inventory.BrewingStandMenu$FuelSlot
- XXX.world.inventory.BrewingStandMenu$IngredientsSlot
+ XXX.world.inventory.BrewingStandMenu$PotionSlot
- XXX.world.inventory.CartographyTableMenu
+ XXX.world.inventory.CartographyTableMenu$1
- XXX.world.inventory.CartographyTableMenu$2
+ XXX.world.inventory.CartographyTableMenu$3
- XXX.world.inventory.CartographyTableMenu$4
+ XXX.world.inventory.CartographyTableMenu$5
- XXX.world.inventory.ChestMenu
+ XXX.world.inventory.ClickAction
- XXX.world.inventory.ClickType
+ XXX.world.inventory.ContainerData
- XXX.world.inventory.ContainerLevelAccess
+ XXX.world.inventory.ContainerLevelAccess$1
- XXX.world.inventory.ContainerLevelAccess$2
+ XXX.world.inventory.ContainerListener
- XXX.world.inventory.ContainerSynchronizer
+ XXX.world.inventory.CrafterMenu
- XXX.world.inventory.CrafterSlot
+ XXX.world.inventory.CraftingContainer
- XXX.world.inventory.CraftingMenu
+ XXX.world.inventory.DataSlot
- XXX.world.inventory.DataSlot$1
+ XXX.world.inventory.DataSlot$2
- XXX.world.inventory.DataSlot$3
+ XXX.world.inventory.DispenserMenu
- XXX.world.inventory.EnchantmentMenu
+ XXX.world.inventory.EnchantmentMenu$1
- XXX.world.inventory.EnchantmentMenu$2
+ XXX.world.inventory.EnchantmentMenu$3
- XXX.world.inventory.FurnaceFuelSlot
+ XXX.world.inventory.FurnaceMenu
- XXX.world.inventory.FurnaceResultSlot
+ XXX.world.inventory.GrindstoneMenu
- XXX.world.inventory.GrindstoneMenu$1
+ XXX.world.inventory.GrindstoneMenu$2
- XXX.world.inventory.GrindstoneMenu$3
+ XXX.world.inventory.GrindstoneMenu$4
- XXX.world.inventory.HopperMenu
+ XXX.world.inventory.HorseInventoryMenu
- XXX.world.inventory.HorseInventoryMenu$1
+ XXX.world.inventory.HorseInventoryMenu$2
- XXX.world.inventory.InventoryMenu
+ XXX.world.inventory.InventoryMenu$1
- XXX.world.inventory.ItemCombinerMenu
+ XXX.world.inventory.ItemCombinerMenu$1
- XXX.world.inventory.ItemCombinerMenu$2
+ XXX.world.inventory.ItemCombinerMenu$3
- XXX.world.inventory.ItemCombinerMenu$4
+ XXX.world.inventory.ItemCombinerMenuSlotDefinition
- XXX.world.inventory.ItemCombinerMenuSlotDefinition$Builder
+ XXX.world.inventory.ItemCombinerMenuSlotDefinition$SlotDefinition
- XXX.world.inventory.LecternMenu
+ XXX.world.inventory.LecternMenu$1
- XXX.world.inventory.LoomMenu
+ XXX.world.inventory.LoomMenu$1
- XXX.world.inventory.LoomMenu$2
+ XXX.world.inventory.LoomMenu$3
- XXX.world.inventory.LoomMenu$4
+ XXX.world.inventory.LoomMenu$5
- XXX.world.inventory.LoomMenu$6
+ XXX.world.inventory.MenuConstructor
- XXX.world.inventory.MenuType
+ XXX.world.inventory.MenuType$MenuSupplier
- XXX.world.inventory.MerchantContainer
+ XXX.world.inventory.MerchantMenu
- XXX.world.inventory.MerchantResultSlot
+ XXX.world.inventory.NonInteractiveResultSlot
- XXX.world.inventory.package-info
- XXX.world.inventory.PlayerEnderChestContainer
+ XXX.world.inventory.RecipeBookMenu
- XXX.world.inventory.RecipeBookMenu$PostPlaceAction
+ XXX.world.inventory.RecipeBookType
- XXX.world.inventory.RecipeCraftingHolder
+ XXX.world.inventory.RemoteSlot
- XXX.world.inventory.RemoteSlot$1
+ XXX.world.inventory.RemoteSlot$Synchronized
- XXX.world.inventory.ResultContainer
+ XXX.world.inventory.ResultSlot
- XXX.world.inventory.ShulkerBoxMenu
+ XXX.world.inventory.ShulkerBoxSlot
- XXX.world.inventory.SimpleContainerData
+ XXX.world.inventory.Slot
- XXX.world.inventory.SlotRange
+ XXX.world.inventory.SlotRange$1
- XXX.world.inventory.SlotRanges
+ XXX.world.inventory.SmithingMenu
- XXX.world.inventory.SmokerMenu
+ XXX.world.inventory.StackedContentsCompatible
- XXX.world.inventory.StonecutterMenu
+ XXX.world.inventory.StonecutterMenu$1
- XXX.world.inventory.StonecutterMenu$2
+ XXX.world.inventory.TransientCraftingContainer
- XXX.world.item.AdventureModePredicate
+ XXX.world.item.AirItem
- XXX.world.item.ArmorStandItem
+ XXX.world.item.ArrowItem
- XXX.world.item.AxeItem
+ XXX.world.item.BannerItem
- XXX.world.item.BedItem
+ XXX.world.item.BlockItem
- XXX.world.item.BoatItem
+ XXX.world.item.BoneMealItem
- XXX.world.item.BoneMealItem$1
+ XXX.world.item.BottleItem
- XXX.world.item.BowItem
+ XXX.world.item.BrushItem
- XXX.world.item.BrushItem$1
+ XXX.world.item.BrushItem$DustParticlesDelta
- XXX.world.item.BucketItem
+ XXX.world.item.BundleItem
- XXX.world.item.BundleItem$1
+ XXX.world.item.CompassItem
- XXX.world.item.CreativeModeTab
+ XXX.world.item.CreativeModeTab$Builder
- XXX.world.item.CreativeModeTab$DisplayItemsGenerator
+ XXX.world.item.CreativeModeTab$ItemDisplayBuilder
- XXX.world.item.CreativeModeTab$ItemDisplayParameters
+ XXX.world.item.CreativeModeTab$Output
- XXX.world.item.CreativeModeTab$Row
+ XXX.world.item.CreativeModeTab$TabVisibility
- XXX.world.item.CreativeModeTab$Type
+ XXX.world.item.CreativeModeTabs
- XXX.world.item.CrossbowItem
+ XXX.world.item.CrossbowItem$ChargeType
- XXX.world.item.CrossbowItem$ChargingSounds
+ XXX.world.item.DebugStickItem
- XXX.world.item.DiscFragmentItem
+ XXX.world.item.DispensibleContainerItem
- XXX.world.item.DoubleHighBlockItem
+ XXX.world.item.DyeColor
- XXX.world.item.DyeItem
+ XXX.world.item.EggItem
- XXX.world.item.EitherHolder
+ XXX.world.item.EmptyMapItem
- XXX.world.item.EndCrystalItem
+ XXX.world.item.EnderEyeItem
- XXX.world.item.EnderpearlItem
+ XXX.world.item.ExperienceBottleItem
- XXX.world.item.FireChargeItem
+ XXX.world.item.FireworkRocketItem
- XXX.world.item.FishingRodItem
+ XXX.world.item.FlintAndSteelItem
- XXX.world.item.FoodOnAStickItem
+ XXX.world.item.GameMasterBlockItem
- XXX.world.item.GlowInkSacItem
+ XXX.world.item.HangingEntityItem
- XXX.world.item.HangingSignItem
+ XXX.world.item.HoeItem
- XXX.world.item.HoneycombItem
+ XXX.world.item.InkSacItem
- XXX.world.item.Instrument
+ XXX.world.item.InstrumentItem
- XXX.world.item.Instruments
+ XXX.world.item.Item
- XXX.world.item.Item$Properties
+ XXX.world.item.Item$TooltipContext
- XXX.world.item.Item$TooltipContext$1
+ XXX.world.item.Item$TooltipContext$2
- XXX.world.item.Item$TooltipContext$3
+ XXX.world.item.ItemCooldowns
- XXX.world.item.ItemCooldowns$CooldownInstance
+ XXX.world.item.ItemDisplayContext
- XXX.world.item.ItemFrameItem
- XXX.world.item.Items
+ XXX.world.item.ItemStack
- XXX.world.item.ItemStack$1
+ XXX.world.item.ItemStack$2
- XXX.world.item.ItemStack$3
+ XXX.world.item.ItemStack$4
- XXX.world.item.ItemStackLinkedSet
+ XXX.world.item.ItemStackLinkedSet$1
- XXX.world.item.ItemUseAnimation
+ XXX.world.item.ItemUtils
+ XXX.world.item.JukeboxPlayable
- XXX.world.item.JukeboxSong
+ XXX.world.item.JukeboxSongPlayer
- XXX.world.item.JukeboxSongPlayer$OnSongChanged
+ XXX.world.item.JukeboxSongs
- XXX.world.item.KnowledgeBookItem
+ XXX.world.item.LeadItem
- XXX.world.item.LingeringPotionItem
+ XXX.world.item.MaceItem
- XXX.world.item.MapItem
+ XXX.world.item.MapItem$1
- XXX.world.item.MinecartItem
+ XXX.world.item.MobBucketItem
- XXX.world.item.NameTagItem
+ XXX.world.item.package-info
+ XXX.world.item.PlaceOnWaterBlockItem
- XXX.world.item.PlayerHeadItem
+ XXX.world.item.PotionItem
- XXX.world.item.ProjectileItem
+ XXX.world.item.ProjectileItem$DispenseConfig
- XXX.world.item.ProjectileItem$DispenseConfig$Builder
+ XXX.world.item.ProjectileItem$PositionFunction
- XXX.world.item.ProjectileWeaponItem
+ XXX.world.item.Rarity
- XXX.world.item.ScaffoldingBlockItem
+ XXX.world.item.ServerItemCooldowns
- XXX.world.item.ShearsItem
+ XXX.world.item.ShieldItem
- XXX.world.item.ShovelItem
+ XXX.world.item.SignApplicator
- XXX.world.item.SignItem
+ XXX.world.item.SmithingTemplateItem
- XXX.world.item.SnowballItem
+ XXX.world.item.SolidBucketItem
- XXX.world.item.SpawnEggItem
+ XXX.world.item.SpectralArrowItem
- XXX.world.item.SplashPotionItem
+ XXX.world.item.SpyglassItem
- XXX.world.item.StandingAndWallBlockItem
+ XXX.world.item.ThrowablePotionItem
- XXX.world.item.TippedArrowItem
+ XXX.world.item.ToolMaterial
- XXX.world.item.TooltipFlag
+ XXX.world.item.TooltipFlag$Default
- XXX.world.item.TridentItem
+ XXX.world.item.WeatheringCopperItems
- XXX.world.item.WindChargeItem
+ XXX.world.item.WritableBookItem
- XXX.world.item.WrittenBookItem
+ XXX.world.level.BaseCommandBlock
- XXX.world.level.BaseCommandBlock$CloseableCommandBlockSource
+ XXX.world.level.BaseSpawner
- XXX.world.level.BlockAndTintGetter
+ XXX.world.level.BlockCollisions
- XXX.world.level.BlockEventData
+ XXX.world.level.BlockGetter
- XXX.world.level.BlockGetter$BlockStepVisitor
+ XXX.world.level.ChunkPos
- XXX.world.level.ChunkPos$1
+ XXX.world.level.ChunkPos$2
- XXX.world.level.ClipBlockStateContext
+ XXX.world.level.ClipContext
- XXX.world.level.ClipContext$Block
+ XXX.world.level.ClipContext$Fluid
- XXX.world.level.ClipContext$ShapeGetter
+ XXX.world.level.CollisionGetter
- XXX.world.level.ColorMapColorUtil
+ XXX.world.level.ColorResolver
- XXX.world.level.CommonLevelAccessor
+ XXX.world.level.CustomSpawner
- XXX.world.level.DataPackConfig
+ XXX.world.level.DryFoliageColor
- XXX.world.level.EmptyBlockAndTintGetter
+ XXX.world.level.EmptyBlockGetter
- XXX.world.level.EntityBasedExplosionDamageCalculator
+ XXX.world.level.EntityGetter
- XXX.world.level.Explosion
+ XXX.world.level.Explosion$BlockInteraction
- XXX.world.level.ExplosionDamageCalculator
+ XXX.world.level.FoliageColor
- XXX.world.level.GameRules
+ XXX.world.level.GameRules$BooleanValue
- XXX.world.level.GameRules$Category
+ XXX.world.level.GameRules$GameRuleTypeVisitor
- XXX.world.level.GameRules$IntegerValue
+ XXX.world.level.GameRules$Key
- XXX.world.level.GameRules$Type
+ XXX.world.level.GameRules$Value
- XXX.world.level.GameRules$VisitorCaller
+ XXX.world.level.GameType
- XXX.world.level.GrassColor
+ XXX.world.level.ItemLike
- XXX.world.level.Level
+ XXX.world.level.Level$1
+ XXX.worldgen.biome.BiomeData
- XXX.worldgen.biome.EndBiomes
+ XXX.worldgen.biome.NetherBiomes
- XXX.worldgen.biome.OverworldBiomes
+ XXX.worldgen.biome.package-info
- XXX.worldgen.features.AquaticFeatures
+ XXX.worldgen.features.CaveFeatures
- XXX.worldgen.features.EndFeatures
+ XXX.worldgen.features.FeatureUtils
- XXX.worldgen.features.MiscOverworldFeatures
+ XXX.worldgen.features.NetherFeatures
- XXX.worldgen.features.OreFeatures
- XXX.worldgen.features.package-info
+ XXX.worldgen.features.PileFeatures
- XXX.worldgen.features.TreeFeatures
+ XXX.worldgen.features.VegetationFeatures
- XXX.worldgen.placement.AquaticPlacements
+ XXX.worldgen.placement.CavePlacements
- XXX.worldgen.placement.EndPlacements
+ XXX.worldgen.placement.MiscOverworldPlacements
- XXX.worldgen.placement.NetherPlacements
+ XXX.worldgen.placement.OrePlacements
- XXX.worldgen.placement.package-info
- XXX.worldgen.placement.PlacementUtils
+ XXX.worldgen.placement.TreePlacements
- XXX.worldgen.placement.VegetationPlacements
+ XXX.worldgen.placement.VillagePlacements
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.blaze3d.platform.InputConstants +6M -6M | +7P -2P
```
```
XXX.blaze3d.platform.MacosUtil +3M -3M
```
```
XXX.advancements.critereon.MinMaxBounds$Doubles +4M -11M | +2P -4P
```
```
XXX.minecraft.client.KeyMapping +11M -7M | +1P -10P
```
```
XXX.gui.screens.BackupConfirmScreen +1M -1M
```
```
XXX.gui.screens.ConfirmScreen +1M -1M
```
```
XXX.gui.screens.CreateBuffetWorldScreen$BiomeList$Entry +1M -1M
```
```
XXX.gui.screens.DeathScreen +1M -1M
```
```
XXX.gui.screens.Overlay +1M
```
```
XXX.gui.screens.PresetFlatWorldScreen$PresetsList +1M -1M
```
```
XXX.gui.screens.Screen +3M -10M
```
```
XXX.gui.screens.WinScreen +2M -2M
```
```
XXX.screens.achievement.StatsScreen +1M -1M
```
```
XXX.screens.advancements.AdvancementsScreen +3M -3M
```
```
XXX.screens.debug.GameModeSwitcherScreen +1M -1M
```
```
XXX.screens.inventory.AbstractCommandBlockEditScreen +2M -2M
```
```
XXX.screens.inventory.AbstractContainerScreen +7M -7M
```
```
XXX.screens.inventory.AbstractSignEditScreen +2M -2M
```
```
XXX.screens.inventory.BeaconScreen$BeaconConfirmButton +1M -1M
```
```
XXX.screens.inventory.BookEditScreen +1M -1M
```
```
XXX.screens.inventory.BookViewScreen +2M -2M
```
```
XXX.screens.inventory.StructureBlockEditScreen +2M -2M
```
```
XXX.screens.multiplayer.CodeOfConductScreen +3M -2M | +1P
```
```
XXX.screens.multiplayer.ServerSelectionList$NetworkServerEntry +2M -2M
```
```
XXX.screens.options.VideoSettingsScreen +1M -1M
```
```
XXX.options.controls.KeyBindsScreen +2M -2M
```
```
XXX.screens.packs.TransferableSelectionList +1M -1M
```
```
XXX.screens.recipebook.RecipeBookComponent +7M -7M
```
```
XXX.screens.recipebook.RecipeBookPage +1M -1M
```
```
XXX.screens.recipebook.RecipeButton +1M -1M
```
```
XXX.screens.reporting.ChatReportScreen +1M -1M
```
```
XXX.screens.reporting.ChatSelectionScreen$ChatSelectionList +1M -1M
```
```
XXX.screens.reporting.ChatSelectionScreen$ChatSelectionList$Entry +1M -1M
```
```
XXX.screens.reporting.ChatSelectionScreen$ChatSelectionList$MessageEntry +2M -2M
```
```
XXX.screens.reporting.SkinReportScreen +1M -1M
```
```
XXX.screens.social.SocialInteractionsScreen +1M -1M
```
```
XXX.screens.worldselection.CreateWorldScreen +1M -1M
```
```
XXX.screens.worldselection.SelectWorldScreen +8M -7M
```
```
XXX.client.model.PlayerCapeModel +1M -1M
```
```
XXX.client.model.PlayerModel +2M -2M
```
```
XXX.client.model.SpinAttackEffectModel +1M -1M
```
```
XXX.model.geom.LayerDefinitions +5M -3M
```
```
XXX.model.geom.ModelPart$Vertex +6M -2M | +4P -1P
```
```
XXX.geom.builders.CubeDefinition +2P -2P
```
```
XXX.client.multiplayer.ClientLevel +3M | +1P
```
```
XXX.client.particle.AttackSweepParticle +1M -1M
```
```
XXX.client.particle.BaseAshSmokeParticle +1M -1M
```
```
XXX.client.particle.BlockMarker$Provider +2M -2M
```
```
XXX.client.particle.BreakingItemParticle$CobwebProvider +2M -2M
```
```
XXX.client.particle.BreakingItemParticle$Provider +2M -2M
```
```
XXX.client.particle.BreakingItemParticle$SnowballProvider +2M -2M
```
```
XXX.client.particle.BubbleColumnUpParticle$Provider +2M -2M
```
```
XXX.client.particle.BubbleParticle$Provider +2M -2M
```
```
XXX.client.particle.BubblePopParticle$Provider +2M -2M
```
```
XXX.client.particle.CampfireSmokeParticle$CosyProvider +2M -2M
```
```
XXX.client.particle.CritParticle +2M -2M
```
```
XXX.client.particle.CritParticle$MagicProvider +2M -2M
```
```
XXX.client.particle.DragonBreathParticle +1M -1M
```
```
XXX.client.particle.DripParticle +2M -19M
```
```
XXX.client.particle.DripParticle$DripHangParticle +1M -1M
```
```
XXX.client.particle.DripParticle$DripstoneFallAndLandParticle +1M -1M
```
```
XXX.client.particle.DripParticle$FallingParticle +2M -2M
```
```
XXX.client.particle.EndRodParticle$Provider +2M -2M
```
```
XXX.client.particle.ExplodeParticle$Provider +2M -2M
```
```
XXX.client.particle.FallingDustParticle$Provider +2M -2M
```
```
XXX.client.particle.FallingLeavesParticle$CherryProvider +2M -2M
```
```
XXX.client.particle.FallingLeavesParticle$TintedLeavesProvider +2M -2M
```
```
XXX.client.particle.FireflyParticle$FireflyProvider +2M -2M
```
```
XXX.client.particle.FireworkParticles$OverlayParticle +3M -3M
```
```
XXX.client.particle.FireworkParticles$SparkProvider +2M -2M
```
```
XXX.client.particle.FlameParticle +2M -2M
```
```
XXX.client.particle.FlameParticle$SmallFlameProvider +2M -2M
```
```
XXX.client.particle.FlyStraightTowardsParticle$OminousSpawnProvider +2M -2M
```
```
XXX.client.particle.FlyTowardsPositionParticle$EnchantProvider +2M -2M
```
```
XXX.client.particle.FlyTowardsPositionParticle$VaultConnectionProvider +2M -2M
```
```
XXX.client.particle.GlowParticle$ElectricSparkProvider +2M -2M
```
```
XXX.client.particle.GlowParticle$ScrapeProvider +2M -2M
```
```
XXX.client.particle.GlowParticle$WaxOnProvider +2M -2M
```
```
XXX.client.particle.GustParticle$Provider +2M -2M
```
```
XXX.client.particle.HeartParticle +2M -2M
```
```
XXX.client.particle.HeartParticle$Provider +2M -2M
```
```
XXX.client.particle.HugeExplosionParticle$Provider +2M -2M
```
```
XXX.client.particle.HugeExplosionSeedParticle$Provider +2M -2M
```
```
XXX.client.particle.NoteParticle$Provider +2M -2M
```
```
XXX.client.particle.ParticleEngine +6M -28M | +1P -5P
```
```
XXX.client.particle.ParticleProvider +1P -1P
```
```
XXX.client.particle.ParticleRenderType +1M -2M | +3P -5P
```
```
XXX.client.particle.PlayerCloudParticle$Provider +2M -2M
```
```
XXX.client.particle.PortalParticle +2M -2M
```
```
XXX.client.particle.SnowflakeParticle +1M -1M
```
```
XXX.client.particle.SoulParticle +1M -1M
```
```
XXX.client.particle.SoulParticle$Provider +2M -2M
```
```
XXX.client.particle.SpellParticle$InstantProvider +2M -2M
```
```
XXX.client.particle.SpellParticle$Provider +2M -2M
```
```
XXX.client.particle.SplashParticle +1M -1M
```
```
XXX.client.particle.SpriteSet +1P
```
```
XXX.client.particle.SquidInkParticle$GlowInkProvider +2M -2M
```
```
XXX.client.particle.SuspendedParticle +3M -3M
```
```
XXX.client.particle.SuspendedParticle$SporeBlossomAirProvider +2M -2M
```
```
XXX.client.particle.SuspendedParticle$UnderwaterProvider +2M -2M
```
```
XXX.client.particle.SuspendedTownParticle +2M -2M
```
```
XXX.client.particle.SuspendedTownParticle$DolphinSpeedProvider +2M -2M
```
```
XXX.client.particle.SuspendedTownParticle$HappyVillagerProvider +2M -2M
```
```
XXX.client.particle.TerrainParticle +1M -1M
```
```
XXX.client.particle.TerrainParticle$DustPillarProvider +2M -2M
```
```
XXX.client.renderer.Sheets +1M -2M
```
```
XXX.renderer.blockentity.BannerRenderer +6M -2M
```
```
XXX.renderer.blockentity.BedRenderer +7M -3M
```
```
XXX.renderer.blockentity.BlockEntityRenderDispatcher +3M -1M
```
```
XXX.renderer.blockentity.BlockEntityRenderers +7M -1M
```
```
XXX.renderer.blockentity.ChestRenderer +7M -1M
```
```
XXX.renderer.special.ChestSpecialRenderer +1P -1P
```
```
XXX.renderer.special.CopperGolemStatueSpecialRenderer +1M | +1P
```
```
XXX.client.resources.DefaultPlayerSkin +1M -1M
```
```
XXX.client.resources.PlayerSkin +2M -2M | +1P -1P
```
```
XXX.server.commands.SpectateCommand +4M -3M | +1P
```
```
XXX.server.level.ServerPlayer +24M -13M | +3P
```
```
XXX.server.players.PlayerList +1M
```
```
XXX.datafix.fixes.References +1P
```
```
XXX.world.entity.EntityType +1P
```
```
XXX.entity.decoration.HangingEntity +3M -2M | -1P
```
```
XXX.entity.decoration.ItemFrame -1M
```
```
XXX.entity.npc.WanderingTraderSpawner +1M -1M
```
```
XXX.entity.player.PlayerModelPart +1M | +1P
```
```
XXX.level.block.CopperGolemStatueBlock +1M
```
```
XXX.level.block.SideChainPartBlock$Neighbor +1P
```
```
XXX.level.block.SideChainPartBlock$SideChainNeighbor +1M
```
```
XXX.level.border.BorderChangeListener +7P -7P
```
```
XXX.level.chunk.HashMapPalette +9M -9M | -2P
```
```
XXX.level.chunk.Palette$Factory +1P -1P
```
```
XXX.level.chunk.PalettedContainer +19M -21M | +1P -3P
```
```
XXX.level.levelgen.PhantomSpawner +1M -1M
```
```
XXX.level.storage.DerivedLevelData +2M -2M
```
```
XXX.phys.shapes.EntityCollisionContext -1M | -1P
```

</details>
<details>
<summary>
com.mojang.blaze3d.platform.InputConstants
</summary>

```diff
+ boolean isKeyDown(long,int)
- boolean isKeyDown(Window,int)
+ InputConstants$Key getKey(int,int)
- InputConstants$Key getKey(KeyEvent)
+ void grabOrReleaseMouse(long,int,double,double)
- void grabOrReleaseMouse(Window,int,double,double)
+ void setupKeyboardCallbacks(long,GLFWKeyCallbackI,GLFWCharModsCallbackI)
- void setupKeyboardCallbacks(Window,GLFWKeyCallbackI,GLFWCharModsCallbackI)
+ void setupMouseCallbacks(long,GLFWCursorPosCallbackI,GLFWMouseButtonCallbackI,GLFWScrollCallbackI,GLFWDropCallbackI)
- void setupMouseCallbacks(Window,GLFWCursorPosCallbackI,GLFWMouseButtonCallbackI,GLFWScrollCallbackI,GLFWDropCallbackI)
+ void updateRawMouseInput(long,boolean)
- void updateRawMouseInput(Window,boolean)
```

</details>
<details>
<summary>
com.mojang.blaze3d.platform.MacosUtil
</summary>

```diff
+ Optional getNsWindow(long)
- Optional getNsWindow(Window)
+ void clearResizableBit(long)
- void clearResizableBit(Window)
+ void exitNativeFullscreen(long)
- void exitNativeFullscreen(Window)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.MinMaxBounds$Doubles
</summary>

```diff
+ Double lambda$fromReader$1(Double)
+ Double lambda$squareOpt$0(Double)
- MinMaxBounds$Bounds bounds()
- MinMaxBounds$Bounds boundsSqr()
+ MinMaxBounds$Doubles create(StringReader,Optional,Optional)
+ MinMaxBounds$Doubles fromReader(StringReader,Function)
+ Optional max()
+ Optional maxSq()
+ Optional min()
+ Optional minSq()
+ Optional squareOpt(Optional)
- void <init>(MinMaxBounds$Bounds,MinMaxBounds$Bounds)
- void <init>(MinMaxBounds$Bounds)
+ void <init>(Optional,Optional,Optional,Optional)
+ void <init>(Optional,Optional)
```

</details>
<details>
<summary>
net.minecraft.client.KeyMapping
</summary>

```diff
+ boolean matches(int,int)
- boolean matches(KeyEvent)
+ boolean matchesMouse(int)
- boolean matchesMouse(MouseButtonEvent)
+ Component lambda$createNameSupplier$1(String)
- Component lambda$createNameSupplier$2(String)
- KeyMapping$Category getCategory()
- List lambda$registerMapping$3(InputConstants$Key)
+ String getCategory()
- void <init>(String,InputConstants$Type,int,KeyMapping$Category)
+ void <init>(String,InputConstants$Type,int,String)
- void <init>(String,int,KeyMapping$Category)
+ void <init>(String,int,String)
- void forAllKeyMappings(InputConstants$Key,Consumer)
- void lambda$click$0(KeyMapping)
- void lambda$set$1(boolean,KeyMapping)
+ void lambda$static$0(HashMap)
- void registerMapping(InputConstants$Key)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.BackupConfirmScreen
</summary>

```diff
+ boolean keyPressed(int,int,int)
- boolean keyPressed(KeyEvent)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.ConfirmScreen
</summary>

```diff
+ boolean keyPressed(int,int,int)
- boolean keyPressed(KeyEvent)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.CreateBuffetWorldScreen$BiomeList$Entry
</summary>

```diff
+ boolean mouseClicked(double,double,int,boolean)
- boolean mouseClicked(MouseButtonEvent,boolean)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.DeathScreen
</summary>

```diff
+ boolean mouseClicked(double,double,int,boolean)
- boolean mouseClicked(MouseButtonEvent,boolean)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.Overlay
</summary>

```diff
- void tick()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.PresetFlatWorldScreen$PresetsList
</summary>

```diff
+ boolean keyPressed(int,int,int)
- boolean keyPressed(KeyEvent)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.Screen
</summary>

```diff
+ boolean hasAltDown()
+ boolean hasControlDown()
+ boolean hasShiftDown()
+ boolean isCopy(int)
+ boolean isCut(int)
+ boolean isPaste(int)
+ boolean isSelectAll(int)
+ boolean isValidCharacterForName(String,char,int)
- boolean isValidCharacterForName(String,int,int)
+ boolean keyPressed(int,int,int)
- boolean keyPressed(KeyEvent)
+ FocusNavigationEvent$TabNavigation createTabEvent()
- FocusNavigationEvent$TabNavigation createTabEvent(boolean)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.WinScreen
</summary>

```diff
+ boolean keyPressed(int,int,int)
- boolean keyPressed(KeyEvent)
+ boolean keyReleased(int,int,int)
- boolean keyReleased(KeyEvent)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.achievement.StatsScreen
</summary>

```diff
+ boolean keyPressed(int,int,int)
- boolean keyPressed(KeyEvent)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.advancements.AdvancementsScreen
</summary>

```diff
+ boolean keyPressed(int,int,int)
- boolean keyPressed(KeyEvent)
+ boolean mouseClicked(double,double,int,boolean)
- boolean mouseClicked(MouseButtonEvent,boolean)
+ boolean mouseDragged(double,double,int,double,double)
- boolean mouseDragged(MouseButtonEvent,double,double)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen
</summary>

```diff
+ boolean keyPressed(int,int,int)
- boolean keyPressed(KeyEvent)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.AbstractCommandBlockEditScreen
</summary>

```diff
+ boolean keyPressed(int,int,int)
- boolean keyPressed(KeyEvent)
+ boolean mouseClicked(double,double,int,boolean)
- boolean mouseClicked(MouseButtonEvent,boolean)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.AbstractContainerScreen
</summary>

```diff
+ boolean checkHotbarKeyPressed(int,int)
- boolean checkHotbarKeyPressed(KeyEvent)
+ boolean hasClickedOutside(double,double,int,int,int)
- boolean hasClickedOutside(double,double,int,int)
+ boolean keyPressed(int,int,int)
- boolean keyPressed(KeyEvent)
+ boolean mouseClicked(double,double,int,boolean)
- boolean mouseClicked(MouseButtonEvent,boolean)
+ boolean mouseDragged(double,double,int,double,double)
- boolean mouseDragged(MouseButtonEvent,double,double)
+ boolean mouseReleased(double,double,int)
- boolean mouseReleased(MouseButtonEvent)
+ void checkHotbarMouseClicked(int)
- void checkHotbarMouseClicked(MouseButtonEvent)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.AbstractSignEditScreen
</summary>

```diff
+ boolean charTyped(char,int)
- boolean charTyped(CharacterEvent)
+ boolean keyPressed(int,int,int)
- boolean keyPressed(KeyEvent)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconConfirmButton
</summary>

```diff
+ void onPress()
- void onPress(InputWithModifiers)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.BookEditScreen
</summary>

```diff
+ boolean keyPressed(int,int,int)
- boolean keyPressed(KeyEvent)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.BookViewScreen
</summary>

```diff
+ boolean keyPressed(int,int,int)
- boolean keyPressed(KeyEvent)
+ boolean mouseClicked(double,double,int,boolean)
- boolean mouseClicked(MouseButtonEvent,boolean)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.inventory.StructureBlockEditScreen
</summary>

```diff
+ boolean access$000(StructureBlockEditScreen,String,char,int)
- boolean access$000(StructureBlockEditScreen,String,int,int)
+ boolean keyPressed(int,int,int)
- boolean keyPressed(KeyEvent)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.multiplayer.CodeOfConductScreen
</summary>

```diff
+ void <init>(ServerData,Component,String,BooleanConsumer)
- void <init>(ServerData,Screen,Component,String,BooleanConsumer)
- void <init>(ServerData,Screen,String,BooleanConsumer)
+ void <init>(ServerData,String,BooleanConsumer)
- void tick()
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.multiplayer.ServerSelectionList$NetworkServerEntry
</summary>

```diff
+ boolean keyPressed(int,int,int)
- boolean keyPressed(KeyEvent)
+ boolean mouseClicked(double,double,int,boolean)
- boolean mouseClicked(MouseButtonEvent,boolean)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.options.VideoSettingsScreen
</summary>

```diff
+ boolean mouseClicked(double,double,int,boolean)
- boolean mouseClicked(MouseButtonEvent,boolean)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.options.controls.KeyBindsScreen
</summary>

```diff
+ boolean keyPressed(int,int,int)
- boolean keyPressed(KeyEvent)
+ boolean mouseClicked(double,double,int,boolean)
- boolean mouseClicked(MouseButtonEvent,boolean)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.packs.TransferableSelectionList
</summary>

```diff
+ boolean keyPressed(int,int,int)
- boolean keyPressed(KeyEvent)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.recipebook.RecipeBookComponent
</summary>

```diff
+ boolean charTyped(char,int)
- boolean charTyped(CharacterEvent)
+ boolean hasClickedOutside(double,double,int,int,int,int,int)
- boolean hasClickedOutside(double,double,int,int,int,int)
+ boolean keyPressed(int,int,int)
- boolean keyPressed(KeyEvent)
+ boolean keyReleased(int,int,int)
- boolean keyReleased(KeyEvent)
+ boolean mouseClicked(double,double,int,boolean)
- boolean mouseClicked(MouseButtonEvent,boolean)
+ boolean mouseDragged(double,double,int,double,double)
- boolean mouseDragged(MouseButtonEvent,double,double)
- boolean tryPlaceRecipe(RecipeCollection,RecipeDisplayId,boolean)
+ boolean tryPlaceRecipe(RecipeCollection,RecipeDisplayId)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.recipebook.RecipeBookPage
</summary>

```diff
+ boolean mouseClicked(double,double,int,int,int,int,int,boolean)
- boolean mouseClicked(MouseButtonEvent,int,int,int,int,boolean)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.recipebook.RecipeButton
</summary>

```diff
+ boolean isValidClickButton(int)
- boolean isValidClickButton(MouseButtonInfo)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.reporting.ChatReportScreen
</summary>

```diff
+ boolean mouseReleased(double,double,int)
- boolean mouseReleased(MouseButtonEvent)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.reporting.ChatSelectionScreen$ChatSelectionList
</summary>

```diff
+ boolean keyPressed(int,int,int)
- boolean keyPressed(KeyEvent)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.reporting.ChatSelectionScreen$ChatSelectionList$Entry
</summary>

```diff
+ boolean mouseClicked(double,double,int,boolean)
- boolean mouseClicked(MouseButtonEvent,boolean)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.reporting.ChatSelectionScreen$ChatSelectionList$MessageEntry
</summary>

```diff
+ boolean keyPressed(int,int,int)
- boolean keyPressed(KeyEvent)
+ boolean mouseClicked(double,double,int,boolean)
- boolean mouseClicked(MouseButtonEvent,boolean)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.reporting.SkinReportScreen
</summary>

```diff
+ boolean mouseReleased(double,double,int)
- boolean mouseReleased(MouseButtonEvent)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.social.SocialInteractionsScreen
</summary>

```diff
+ boolean keyPressed(int,int,int)
- boolean keyPressed(KeyEvent)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.worldselection.CreateWorldScreen
</summary>

```diff
+ boolean keyPressed(int,int,int)
- boolean keyPressed(KeyEvent)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.worldselection.SelectWorldScreen
</summary>

```diff
- void createFooterButtons(Consumer,WorldSelectionList)
- void lambda$createFooterButtons$2(WorldSelectionList,Consumer,Button)
- void lambda$createFooterButtons$3(WorldSelectionList,Button)
- void lambda$createFooterButtons$4(WorldSelectionList,Button)
- void lambda$createFooterButtons$5(WorldSelectionList,Button)
- void lambda$createFooterButtons$6(WorldSelectionList,Button)
- void lambda$createFooterButtons$7(Button)
+ void lambda$init$1(Consumer,Button)
- void lambda$init$1(SelectWorldScreen,GuiEventListener)
+ void lambda$init$2(Button)
+ void lambda$init$3(Button)
+ void lambda$init$4(Button)
+ void lambda$init$5(Button)
+ void lambda$init$6(Button)
+ void lambda$init$7(SelectWorldScreen,GuiEventListener)
```

</details>
<details>
<summary>
net.minecraft.client.model.PlayerCapeModel
</summary>

```diff
- void setupAnim(AvatarRenderState)
+ void setupAnim(PlayerRenderState)
```

</details>
<details>
<summary>
net.minecraft.client.model.PlayerModel
</summary>

```diff
- void setupAnim(AvatarRenderState)
+ void setupAnim(PlayerRenderState)
- void translateToHand(AvatarRenderState,HumanoidArm,PoseStack)
+ void translateToHand(PlayerRenderState,HumanoidArm,PoseStack)
```

</details>
<details>
<summary>
net.minecraft.client.model.SpinAttackEffectModel
</summary>

```diff
- void setupAnim(AvatarRenderState)
+ void setupAnim(PlayerRenderState)
```

</details>
<details>
<summary>
net.minecraft.client.model.geom.LayerDefinitions
</summary>

```diff
+ boolean lambda$createRoots$10(ImmutableMap,ModelLayerLocation)
- boolean lambda$createRoots$12(ImmutableMap,ModelLayerLocation)
- LayerDefinition lambda$createRoots$10(LayerDefinition)
+ LayerDefinition lambda$createRoots$8(LayerDefinition)
- LayerDefinition lambda$createRoots$8(MeshTransformer,LayerDefinition)
- LayerDefinition lambda$createRoots$9(MeshTransformer,LayerDefinition)
- void lambda$createRoots$11(ImmutableMap$Builder,LayerDefinition,LayerDefinition,WoodType)
+ void lambda$createRoots$9(ImmutableMap$Builder,LayerDefinition,LayerDefinition,WoodType)
```

</details>
<details>
<summary>
net.minecraft.client.model.geom.ModelPart$Vertex
</summary>

```diff
- float worldX()
- float worldY()
- float worldZ()
- float x()
- float y()
- float z()
+ Vector3f pos()
+ void <init>(Vector3f,float,float)
```

</details>
<details>
<summary>
net.minecraft.client.multiplayer.ClientLevel
</summary>

```diff
- void addBreakingBlockEffect(BlockPos,Direction)
- void lambda$addDestroyBlockEffect$14(BlockPos,BlockState,double,double,double,double,double,double)
- WorldBorder getWorldBorder()
```

</details>
<details>
<summary>
net.minecraft.client.particle.AttackSweepParticle
</summary>

```diff
+ ParticleRenderType getRenderType()
- SingleQuadParticle$Layer getLayer()
```

</details>
<details>
<summary>
net.minecraft.client.particle.BaseAshSmokeParticle
</summary>

```diff
+ ParticleRenderType getRenderType()
- SingleQuadParticle$Layer getLayer()
```

</details>
<details>
<summary>
net.minecraft.client.particle.BlockMarker$Provider
</summary>

```diff
- Particle createParticle(BlockParticleOption,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(BlockParticleOption,ClientLevel,double,double,double,double,double,double)
- Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double)
```

</details>
<details>
<summary>
net.minecraft.client.particle.BreakingItemParticle$CobwebProvider
</summary>

```diff
- Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double)
- Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double)
```

</details>
<details>
<summary>
net.minecraft.client.particle.BreakingItemParticle$Provider
</summary>

```diff
- Particle createParticle(ItemParticleOption,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(ItemParticleOption,ClientLevel,double,double,double,double,double,double)
- Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double)
```

</details>
<details>
<summary>
net.minecraft.client.particle.BreakingItemParticle$SnowballProvider
</summary>

```diff
- Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double)
- Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double)
```

</details>
<details>
<summary>
net.minecraft.client.particle.BubbleColumnUpParticle$Provider
</summary>

```diff
- Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double)
- Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double)
```

</details>
<details>
<summary>
net.minecraft.client.particle.BubbleParticle$Provider
</summary>

```diff
- Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double)
- Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double)
```

</details>
<details>
<summary>
net.minecraft.client.particle.BubblePopParticle$Provider
</summary>

```diff
- Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double)
- Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double)
```

</details>
<details>
<summary>
net.minecraft.client.particle.CampfireSmokeParticle$CosyProvider
</summary>

```diff
- Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double)
- Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double)
```

</details>
<details>
<summary>
net.minecraft.client.particle.CritParticle
</summary>

```diff
+ ParticleRenderType getRenderType()
- SingleQuadParticle$Layer getLayer()
- void <init>(ClientLevel,double,double,double,double,double,double,TextureAtlasSprite)
+ void <init>(ClientLevel,double,double,double,double,double,double)
```

</details>
<details>
<summary>
net.minecraft.client.particle.CritParticle$MagicProvider
</summary>

```diff
- Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double)
- Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double)
```

</details>
<details>
<summary>
net.minecraft.client.particle.DragonBreathParticle
</summary>

```diff
+ ParticleRenderType getRenderType()
- SingleQuadParticle$Layer getLayer()
```

</details>
<details>
<summary>
net.minecraft.client.particle.DripParticle
</summary>

```diff
+ ParticleRenderType getRenderType()
- SingleQuadParticle$Layer getLayer()
+ TextureSheetParticle createDripstoneLavaFallParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double)
+ TextureSheetParticle createDripstoneLavaHangParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double)
+ TextureSheetParticle createDripstoneWaterFallParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double)
+ TextureSheetParticle createDripstoneWaterHangParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double)
+ TextureSheetParticle createHoneyFallParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double)
+ TextureSheetParticle createHoneyHangParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double)
+ TextureSheetParticle createHoneyLandParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double)
+ TextureSheetParticle createLavaFallParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double)
+ TextureSheetParticle createLavaHangParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double)
+ TextureSheetParticle createLavaLandParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double)
+ TextureSheetParticle createNectarFallParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double)
+ TextureSheetParticle createObsidianTearFallParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double)
+ TextureSheetParticle createObsidianTearHangParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double)
+ TextureSheetParticle createObsidianTearLandParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double)
+ TextureSheetParticle createSporeBlossomFallParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double)
+ TextureSheetParticle createWaterFallParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double)
+ TextureSheetParticle createWaterHangParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double)
- void <init>(ClientLevel,double,double,double,Fluid,TextureAtlasSprite)
+ void <init>(ClientLevel,double,double,double,Fluid)
```

</details>
<details>
<summary>
net.minecraft.client.particle.DripParticle$DripHangParticle
</summary>

```diff
- void <init>(ClientLevel,double,double,double,Fluid,ParticleOptions,TextureAtlasSprite)
+ void <init>(ClientLevel,double,double,double,Fluid,ParticleOptions)
```

</details>
<details>
<summary>
net.minecraft.client.particle.DripParticle$DripstoneFallAndLandParticle
</summary>

```diff
- void <init>(ClientLevel,double,double,double,Fluid,ParticleOptions,TextureAtlasSprite)
+ void <init>(ClientLevel,double,double,double,Fluid,ParticleOptions)
```

</details>
<details>
<summary>
net.minecraft.client.particle.DripParticle$FallingParticle
</summary>

```diff
- void <init>(ClientLevel,double,double,double,Fluid,int,TextureAtlasSprite)
+ void <init>(ClientLevel,double,double,double,Fluid,int)
- void <init>(ClientLevel,double,double,double,Fluid,TextureAtlasSprite)
+ void <init>(ClientLevel,double,double,double,Fluid)
```

</details>
<details>
<summary>
net.minecraft.client.particle.EndRodParticle$Provider
</summary>

```diff
- Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double)
- Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double)
```

</details>
<details>
<summary>
net.minecraft.client.particle.ExplodeParticle$Provider
</summary>

```diff
- Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double)
- Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double)
```

</details>
<details>
<summary>
net.minecraft.client.particle.FallingDustParticle$Provider
</summary>

```diff
- Particle createParticle(BlockParticleOption,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(BlockParticleOption,ClientLevel,double,double,double,double,double,double)
- Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double)
```

</details>
<details>
<summary>
net.minecraft.client.particle.FallingLeavesParticle$CherryProvider
</summary>

```diff
- Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double)
- Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double)
```

</details>
<details>
<summary>
net.minecraft.client.particle.FallingLeavesParticle$TintedLeavesProvider
</summary>

```diff
- Particle createParticle(ColorParticleOption,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(ColorParticleOption,ClientLevel,double,double,double,double,double,double)
- Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double)
```

</details>
<details>
<summary>
net.minecraft.client.particle.FireflyParticle$FireflyProvider
</summary>

```diff
- Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double)
- Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double)
```

</details>
<details>
<summary>
net.minecraft.client.particle.FireworkParticles$OverlayParticle
</summary>

```diff
+ ParticleRenderType getRenderType()
- SingleQuadParticle$Layer getLayer()
- void <init>(ClientLevel,double,double,double,TextureAtlasSprite)
+ void <init>(ClientLevel,double,double,double)
- void extract(QuadParticleRenderState,Camera,float)
+ void render(VertexConsumer,Camera,float)
```

</details>
<details>
<summary>
net.minecraft.client.particle.FireworkParticles$SparkProvider
</summary>

```diff
- Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double)
- Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double)
```

</details>
<details>
<summary>
net.minecraft.client.particle.FlameParticle
</summary>

```diff
+ ParticleRenderType getRenderType()
- SingleQuadParticle$Layer getLayer()
- void <init>(ClientLevel,double,double,double,double,double,double,TextureAtlasSprite)
+ void <init>(ClientLevel,double,double,double,double,double,double)
```

</details>
<details>
<summary>
net.minecraft.client.particle.FlameParticle$SmallFlameProvider
</summary>

```diff
- Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double)
- Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double)
```

</details>
<details>
<summary>
net.minecraft.client.particle.FlyStraightTowardsParticle$OminousSpawnProvider
</summary>

```diff
- Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double)
- Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double)
```

</details>
<details>
<summary>
net.minecraft.client.particle.FlyTowardsPositionParticle$EnchantProvider
</summary>

```diff
- Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double)
- Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double)
```

</details>
<details>
<summary>
net.minecraft.client.particle.FlyTowardsPositionParticle$VaultConnectionProvider
</summary>

```diff
- Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double)
- Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double)
```

</details>
<details>
<summary>
net.minecraft.client.particle.GlowParticle$ElectricSparkProvider
</summary>

```diff
- Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double)
- Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double)
```

</details>
<details>
<summary>
net.minecraft.client.particle.GlowParticle$ScrapeProvider
</summary>

```diff
- Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double)
- Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double)
```

</details>
<details>
<summary>
net.minecraft.client.particle.GlowParticle$WaxOnProvider
</summary>

```diff
- Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double)
- Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double)
```

</details>
<details>
<summary>
net.minecraft.client.particle.GustParticle$Provider
</summary>

```diff
- Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double)
- Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double)
```

</details>
<details>
<summary>
net.minecraft.client.particle.HeartParticle
</summary>

```diff
+ ParticleRenderType getRenderType()
- SingleQuadParticle$Layer getLayer()
- void <init>(ClientLevel,double,double,double,TextureAtlasSprite)
+ void <init>(ClientLevel,double,double,double)
```

</details>
<details>
<summary>
net.minecraft.client.particle.HeartParticle$Provider
</summary>

```diff
- Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double)
- Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double)
```

</details>
<details>
<summary>
net.minecraft.client.particle.HugeExplosionParticle$Provider
</summary>

```diff
- Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double)
- Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double)
```

</details>
<details>
<summary>
net.minecraft.client.particle.HugeExplosionSeedParticle$Provider
</summary>

```diff
- Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double)
- Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double)
```

</details>
<details>
<summary>
net.minecraft.client.particle.NoteParticle$Provider
</summary>

```diff
- Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double)
- Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double)
```

</details>
<details>
<summary>
net.minecraft.client.particle.ParticleEngine
</summary>

```diff
+ boolean hasSpaceInParticleLimit(ParticleGroup)
- boolean hasSpaceInParticleLimit(ParticleLimit)
+ CompletableFuture reload(PreparableReloadListener$SharedState,Executor,PreparableReloadListener$PreparationBarrier,Executor)
+ CompletionStage lambda$reload$5(Executor,Map)
+ Map lambda$reload$2(ResourceManager)
+ Optional loadParticleDescription(ResourceLocation,Resource)
+ Particle lambda$register$0(ParticleProvider$Sprite,SpriteSet,ParticleOptions,ClientLevel,double,double,double,double,double,double)
+ ParticleEngine$1ParticleDefinition lambda$reload$3(ResourceLocation,Resource)
- ParticleGroup createParticleGroup(ParticleRenderType)
+ ParticleProvider lambda$register$1(ParticleProvider$Sprite,SpriteSet)
+ Queue lambda$tick$9(ParticleRenderType)
- void <init>(ClientLevel,ParticleResources)
+ void <init>(ClientLevel)
+ void crack(BlockPos,Direction)
+ void destroy(BlockPos,BlockState)
- void extract(ParticlesRenderState,Frustum,Camera,float)
+ void lambda$destroy$11(BlockPos,BlockState,double,double,double,double,double,double)
+ void lambda$reload$4(List,Executor,ResourceLocation,Resource)
+ void lambda$reload$6(SpriteLoader$Preparations,Set,TextureAtlasSprite,ParticleEngine$1ParticleDefinition)
+ void lambda$reload$7(CompletableFuture,CompletableFuture,Void)
- void lambda$tick$0(ParticleRenderType,ParticleGroup)
+ void lambda$tick$8(ParticleRenderType,Queue)
+ void lambda$tickParticleList$10(ParticleGroup)
+ void register(ParticleType,ParticleEngine$SpriteParticleRegistration)
+ void register(ParticleType,ParticleProvider)
+ void register(ParticleType,ParticleProvider$Sprite)
+ void registerProviders()
+ void render(Camera,float,MultiBufferSource$BufferSource)
+ void renderCustomParticles(Camera,float,MultiBufferSource$BufferSource,Queue)
+ void renderParticleType(Camera,float,MultiBufferSource$BufferSource,ParticleRenderType,Queue)
+ void tickParticle(Particle)
+ void tickParticleList(Collection)
+ void updateCount(ParticleGroup,int)
- void updateCount(ParticleLimit,int)
```

</details>
<details>
<summary>
net.minecraft.client.particle.ParticleRenderType
</summary>

```diff
+ RenderType renderType()
+ void <init>(String,RenderType)
- void <init>(String)
```

</details>
<details>
<summary>
net.minecraft.client.particle.PlayerCloudParticle$Provider
</summary>

```diff
- Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double)
- Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double)
```

</details>
<details>
<summary>
net.minecraft.client.particle.PortalParticle
</summary>

```diff
+ ParticleRenderType getRenderType()
- SingleQuadParticle$Layer getLayer()
- void <init>(ClientLevel,double,double,double,double,double,double,TextureAtlasSprite)
+ void <init>(ClientLevel,double,double,double,double,double,double)
```

</details>
<details>
<summary>
net.minecraft.client.particle.SnowflakeParticle
</summary>

```diff
+ ParticleRenderType getRenderType()
- SingleQuadParticle$Layer getLayer()
```

</details>
<details>
<summary>
net.minecraft.client.particle.SoulParticle
</summary>

```diff
+ ParticleRenderType getRenderType()
- SingleQuadParticle$Layer getLayer()
```

</details>
<details>
<summary>
net.minecraft.client.particle.SoulParticle$Provider
</summary>

```diff
- Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double)
- Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double)
```

</details>
<details>
<summary>
net.minecraft.client.particle.SpellParticle$InstantProvider
</summary>

```diff
- Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double)
+ Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double)
- Particle createParticle(SpellParticleOption,ClientLevel,double,double,double,double,double,double,RandomSource)
```

</details>
<details>
<summary>
net.minecraft.client.particle.SpellParticle$Provider
</summary>

```diff
- Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double)
- Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double)
```

</details>
<details>
<summary>
net.minecraft.client.particle.SplashParticle
</summary>

```diff
- void <init>(ClientLevel,double,double,double,double,double,double,TextureAtlasSprite)
+ void <init>(ClientLevel,double,double,double,double,double,double)
```

</details>
<details>
<summary>
net.minecraft.client.particle.SquidInkParticle$GlowInkProvider
</summary>

```diff
- Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double)
- Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double)
```

</details>
<details>
<summary>
net.minecraft.client.particle.SuspendedParticle
</summary>

```diff
+ ParticleRenderType getRenderType()
- SingleQuadParticle$Layer getLayer()
- void <init>(ClientLevel,double,double,double,double,double,double,TextureAtlasSprite)
- void <init>(ClientLevel,double,double,double,TextureAtlasSprite)
+ void <init>(ClientLevel,SpriteSet,double,double,double,double,double,double)
+ void <init>(ClientLevel,SpriteSet,double,double,double)
```

</details>
<details>
<summary>
net.minecraft.client.particle.SuspendedParticle$SporeBlossomAirProvider
</summary>

```diff
- Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double)
- Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double)
```

</details>
<details>
<summary>
net.minecraft.client.particle.SuspendedParticle$UnderwaterProvider
</summary>

```diff
- Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double)
- Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double)
```

</details>
<details>
<summary>
net.minecraft.client.particle.SuspendedTownParticle
</summary>

```diff
+ ParticleRenderType getRenderType()
- SingleQuadParticle$Layer getLayer()
- void <init>(ClientLevel,double,double,double,double,double,double,TextureAtlasSprite)
+ void <init>(ClientLevel,double,double,double,double,double,double)
```

</details>
<details>
<summary>
net.minecraft.client.particle.SuspendedTownParticle$DolphinSpeedProvider
</summary>

```diff
- Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double)
- Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double)
```

</details>
<details>
<summary>
net.minecraft.client.particle.SuspendedTownParticle$HappyVillagerProvider
</summary>

```diff
- Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double)
- Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(SimpleParticleType,ClientLevel,double,double,double,double,double,double)
```

</details>
<details>
<summary>
net.minecraft.client.particle.TerrainParticle
</summary>

```diff
+ ParticleRenderType getRenderType()
- SingleQuadParticle$Layer getLayer()
```

</details>
<details>
<summary>
net.minecraft.client.particle.TerrainParticle$DustPillarProvider
</summary>

```diff
- Particle createParticle(BlockParticleOption,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(BlockParticleOption,ClientLevel,double,double,double,double,double,double)
- Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double,RandomSource)
+ Particle createParticle(ParticleOptions,ClientLevel,double,double,double,double,double,double)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.Sheets
</summary>

```diff
+ Material chooseCopperMaterial(ChestType,CopperChestBlock)
+ Material chooseMaterial(BlockEntity,ChestType,boolean)
- Material chooseMaterial(ChestRenderState$ChestMaterialType,ChestType)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.blockentity.BannerRenderer
</summary>

```diff
- BannerRenderState createRenderState()
- BlockEntityRenderState createRenderState()
- void extractRenderState(BannerBlockEntity,BannerRenderState,float,Vec3,ModelFeatureRenderer$CrumblingOverlay)
- void extractRenderState(BlockEntity,BlockEntityRenderState,float,Vec3,ModelFeatureRenderer$CrumblingOverlay)
+ void submit(BannerBlockEntity,float,PoseStack,int,int,Vec3,ModelFeatureRenderer$CrumblingOverlay,SubmitNodeCollector)
- void submit(BannerRenderState,PoseStack,SubmitNodeCollector)
+ void submit(BlockEntity,float,PoseStack,int,int,Vec3,ModelFeatureRenderer$CrumblingOverlay,SubmitNodeCollector)
- void submit(BlockEntityRenderState,PoseStack,SubmitNodeCollector)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.blockentity.BedRenderer
</summary>

```diff
- BedRenderState createRenderState()
- BlockEntityRenderState createRenderState()
- boolean lambda$extractRenderState$0(LevelAccessor,BlockPos)
+ boolean lambda$submit$0(LevelAccessor,BlockPos)
- void extractRenderState(BedBlockEntity,BedRenderState,float,Vec3,ModelFeatureRenderer$CrumblingOverlay)
- void extractRenderState(BlockEntity,BlockEntityRenderState,float,Vec3,ModelFeatureRenderer$CrumblingOverlay)
+ void submit(BedBlockEntity,float,PoseStack,int,int,Vec3,ModelFeatureRenderer$CrumblingOverlay,SubmitNodeCollector)
- void submit(BedRenderState,PoseStack,SubmitNodeCollector)
+ void submit(BlockEntity,float,PoseStack,int,int,Vec3,ModelFeatureRenderer$CrumblingOverlay,SubmitNodeCollector)
- void submit(BlockEntityRenderState,PoseStack,SubmitNodeCollector)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.blockentity.BlockEntityRenderDispatcher
</summary>

```diff
- BlockEntityRenderer getRenderer(BlockEntityRenderState)
- BlockEntityRenderState tryExtractRenderState(BlockEntity,float,ModelFeatureRenderer$CrumblingOverlay)
+ void submit(BlockEntity,float,PoseStack,ModelFeatureRenderer$CrumblingOverlay,SubmitNodeCollector)
- void submit(BlockEntityRenderState,PoseStack,SubmitNodeCollector)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.blockentity.BlockEntityRenderers
</summary>

```diff
- BlockEntityRenderer lambda$static$0(BlockEntityRendererProvider$Context)
- BlockEntityRenderer lambda$static$1(BlockEntityRendererProvider$Context)
- BlockEntityRenderer lambda$static$2(BlockEntityRendererProvider$Context)
- BlockEntityRenderer lambda$static$3(BlockEntityRendererProvider$Context)
- BlockEntityRenderer lambda$static$4(BlockEntityRendererProvider$Context)
- BlockEntityRenderer lambda$static$5(BlockEntityRendererProvider$Context)
+ void lambda$createEntityRenderers$0(ImmutableMap$Builder,BlockEntityRendererProvider$Context,BlockEntityType,BlockEntityRendererProvider)
- void lambda$createEntityRenderers$6(ImmutableMap$Builder,BlockEntityRendererProvider$Context,BlockEntityType,BlockEntityRendererProvider)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.blockentity.ChestRenderer
</summary>

```diff
- BlockEntityRenderState createRenderState()
- ChestRenderState createRenderState()
- ChestRenderState$ChestMaterialType getChestMaterial(BlockEntity,boolean)
- void extractRenderState(BlockEntity,BlockEntityRenderState,float,Vec3,ModelFeatureRenderer$CrumblingOverlay)
- void extractRenderState(BlockEntity,ChestRenderState,float,Vec3,ModelFeatureRenderer$CrumblingOverlay)
+ void submit(BlockEntity,float,PoseStack,int,int,Vec3,ModelFeatureRenderer$CrumblingOverlay,SubmitNodeCollector)
- void submit(BlockEntityRenderState,PoseStack,SubmitNodeCollector)
- void submit(ChestRenderState,PoseStack,SubmitNodeCollector)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.special.CopperGolemStatueSpecialRenderer
</summary>

```diff
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.client.resources.DefaultPlayerSkin
</summary>

```diff
- PlayerSkin create(String,PlayerModelType)
+ PlayerSkin create(String,PlayerSkin$Model)
```

</details>
<details>
<summary>
net.minecraft.client.resources.PlayerSkin
</summary>

```diff
- PlayerModelType model()
+ PlayerSkin$Model model()
- void <init>(ResourceLocation,String,ResourceLocation,ResourceLocation,PlayerModelType,boolean)
+ void <init>(ResourceLocation,String,ResourceLocation,ResourceLocation,PlayerSkin$Model,boolean)
```

</details>
<details>
<summary>
net.minecraft.server.commands.SpectateCommand
</summary>

```diff
+ Component lambda$spectate$4(Entity)
+ Component lambda$spectate$5()
- Component lambda$spectate$5(Entity)
- Component lambda$spectate$6()
+ int lambda$register$1(CommandContext)
- int lambda$register$4(CommandContext)
- Message lambda$static$1(Object)
```

</details>
<details>
<summary>
net.minecraft.server.level.ServerPlayer
</summary>

```diff
+ boolean lambda$startSleepInBed$12(Monster)
- boolean lambda$startSleepInBed$14(Monster)
- boolean lambda$tellNeutralMobsThatIDied$10(Mob)
+ boolean lambda$tellNeutralMobsThatIDied$8(Mob)
- boolean setEntityOnShoulder(CompoundTag)
- CompoundTag getShoulderEntityLeft()
- CompoundTag getShoulderEntityRight()
+ Packet lambda$die$7(Component)
- Packet lambda$die$9(Component)
+ Packet lambda$sendSystemMessage$16(Component)
- Packet lambda$sendSystemMessage$18(Component)
+ ServerPlayer$RespawnPosAngle lambda$findRespawnAndUseSpawnBlock$10(BlockPos,Vec3)
+ ServerPlayer$RespawnPosAngle lambda$findRespawnAndUseSpawnBlock$11(BlockPos,Vec3)
- ServerPlayer$RespawnPosAngle lambda$findRespawnAndUseSpawnBlock$12(BlockPos,Vec3)
- ServerPlayer$RespawnPosAngle lambda$findRespawnAndUseSpawnBlock$13(BlockPos,Vec3)
+ Stream lambda$awardRecipesByKey$15(ResourceKey)
- Stream lambda$awardRecipesByKey$17(ResourceKey)
- String lambda$respawnEntityOnShoulder$5()
+ Style lambda$die$6(Component,Style)
- Style lambda$die$8(Component,Style)
- void handleShoulderEntities()
+ void lambda$awardStat$14(int,ScoreAccess)
- void lambda$awardStat$16(int,ScoreAccess)
+ void lambda$drop$17(Inventory,int)
- void lambda$drop$19(Inventory,int)
- void lambda$respawnEntityOnShoulder$6(ServerLevel,Entity)
+ void lambda$startSleepInBed$13(Unit)
- void lambda$startSleepInBed$15(Unit)
- void lambda$tellNeutralMobsThatIDied$11(Mob)
+ void lambda$tellNeutralMobsThatIDied$9(Mob)
+ void lambda$updateScoreForCriteria$5(int,ScoreAccess)
- void lambda$updateScoreForCriteria$7(int,ScoreAccess)
- void playShoulderEntityAmbientSound(CompoundTag)
- void removeEntitiesOnShoulder()
- void respawnEntityOnShoulder(CompoundTag)
- void setShoulderEntityLeft(CompoundTag)
- void setShoulderEntityRight(CompoundTag)
```

</details>
<details>
<summary>
net.minecraft.server.players.PlayerList
</summary>

```diff
- Component getReasonMessage(BanListEntry)
```

</details>
<details>
<summary>
net.minecraft.world.entity.decoration.HangingEntity
</summary>

```diff
- boolean canCoexist(boolean)
- boolean lambda$canCoexist$1(boolean,HangingEntity)
+ boolean lambda$static$0(Entity)
- boolean lambda$survives$0(BlockPos)
+ boolean lambda$survives$1(BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.entity.decoration.ItemFrame
</summary>

```diff
+ boolean lambda$survives$0(Entity)
```

</details>
<details>
<summary>
net.minecraft.world.entity.npc.WanderingTraderSpawner
</summary>

```diff
+ void tick(ServerLevel,boolean,boolean)
- void tick(ServerLevel,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.entity.player.PlayerModelPart
</summary>

```diff
- String getSerializedName()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CopperGolemStatueBlock
</summary>

```diff
- ItemStack getCloneItemStack(LevelReader,BlockPos,BlockState,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SideChainPartBlock$SideChainNeighbor
</summary>

```diff
- boolean isConnectable()
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.HashMapPalette
</summary>

```diff
+ int getSerializedSize()
- int getSerializedSize(IdMap)
- int idFor(Object,PaletteResize)
+ int idFor(Object)
- Palette copy()
+ Palette copy(PaletteResize)
+ Palette create(int,IdMap,PaletteResize,List)
- Palette create(int,List)
+ void <init>(IdMap,int,PaletteResize,CrudeIncrementalIntIdentityHashBiMap)
+ void <init>(IdMap,int,PaletteResize,List)
+ void <init>(IdMap,int,PaletteResize)
- void <init>(int,CrudeIncrementalIntIdentityHashBiMap)
- void <init>(int,List)
- void <init>(int)
- void read(FriendlyByteBuf,IdMap)
+ void read(FriendlyByteBuf)
- void write(FriendlyByteBuf,IdMap)
+ void write(FriendlyByteBuf)
```

</details>
<details>
<summary>
net.minecraft.world.level.chunk.PalettedContainer
</summary>

```diff
- App lambda$codec$2(Codec,Object,RecordCodecBuilder$Instance)
+ App lambda$codec$3(Codec,Object,RecordCodecBuilder$Instance)
- Codec codec(Codec,Strategy,Object,PalettedContainerRO$Unpacker)
+ Codec codec(IdMap,Codec,PalettedContainer$Strategy,Object,PalettedContainerRO$Unpacker)
- Codec codecRO(Codec,Strategy,Object)
+ Codec codecRO(IdMap,Codec,PalettedContainer$Strategy,Object)
- Codec codecRW(Codec,Strategy,Object)
+ Codec codecRW(IdMap,Codec,PalettedContainer$Strategy,Object)
- DataResult lambda$codec$3(PalettedContainerRO$Unpacker,Strategy,PalettedContainerRO$PackedData)
+ DataResult lambda$codec$4(PalettedContainerRO$Unpacker,IdMap,PalettedContainer$Strategy,PalettedContainerRO$PackedData)
- DataResult lambda$codecRO$1(Strategy,PalettedContainerRO$PackedData)
+ DataResult lambda$codecRO$2(IdMap,PalettedContainer$Strategy,PalettedContainerRO$PackedData)
+ DataResult unpack(IdMap,PalettedContainer$Strategy,PalettedContainerRO$PackedData)
- DataResult unpack(Strategy,PalettedContainerRO$PackedData)
- int bitsPerEntry()
+ int lambda$new$0(int,Object)
+ int lambda$pack$11(HashMapPalette,int)
+ int lambda$unpack$8(int,Object)
+ int lambda$unpack$9(IdMap,Palette,int)
- int[] reencodeContents(BitStorage,Palette,Palette)
- PalettedContainerRO lambda$codecRO$0(PalettedContainer)
+ PalettedContainerRO lambda$codecRO$1(PalettedContainer)
- PalettedContainerRO$PackedData lambda$codec$4(Strategy,PalettedContainerRO)
+ PalettedContainerRO$PackedData lambda$codec$5(IdMap,PalettedContainer$Strategy,PalettedContainerRO)
+ PalettedContainerRO$PackedData pack(IdMap,PalettedContainer$Strategy)
- PalettedContainerRO$PackedData pack(Strategy)
+ String lambda$unpack$10(SimpleBitStorage$InitializationException)
- String lambda$unpack$6(int,PalettedContainerRO$PackedData)
- String lambda$unpack$8(SimpleBitStorage$InitializationException)
+ void <init>(IdMap,Object,PalettedContainer$Strategy)
+ void <init>(IdMap,PalettedContainer$Strategy,PalettedContainer$Configuration,BitStorage,List)
- void <init>(Object,Strategy)
- void <init>(Strategy,Configuration,BitStorage,Palette)
- void lambda$count$10(PalettedContainer$CountConsumer,Int2IntMap$Entry)
+ void lambda$count$12(Int2IntOpenHashMap,int)
+ void lambda$count$13(PalettedContainer$CountConsumer,Int2IntMap$Entry)
- void lambda$count$9(Int2IntOpenHashMap,int)
- void lambda$getAll$5(Consumer,Palette,int)
+ void lambda$getAll$6(Consumer,Palette,int)
+ void swapPalette(int[],IntUnaryOperator)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.PhantomSpawner
</summary>

```diff
+ void tick(ServerLevel,boolean,boolean)
- void tick(ServerLevel,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.DerivedLevelData
</summary>

```diff
- Optional getLegacyWorldBorderSettings()
- void setLegacyWorldBorderSettings(Optional)
+ void setWorldBorder(WorldBorder$Settings)
+ WorldBorder$Settings getWorldBorder()
```

</details>
<details>
<summary>
net.minecraft.world.phys.shapes.EntityCollisionContext
</summary>

```diff
+ void <clinit>()
```

</details>
</details>
<hr/>