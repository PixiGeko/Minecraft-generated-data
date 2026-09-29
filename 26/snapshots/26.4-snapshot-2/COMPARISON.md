## Comparison with [26.4-snapshot-1](https://github.com/PixiGeko/Minecraft-generated-data/tree/26.4-snapshot-1)

> [!TIP]
> - [Version data](#version-data)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Datapacks](#datapacks)
> - [Translations](#translations)
> - [File structure](#file-structure)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">26.4-snapshot-1</th><th>26.4-snapshot-2</th></tr><tr><td>DataPack version</td><td><pre>122.0</pre></td><td><pre>122.1</pre></td></tr><tr><td>ResourcePack version</td><td><pre>98.0</pre></td><td><pre>99.0</pre></td></tr><tr><td>World version</td><td><pre>5119</pre></td><td><pre>5120</pre></td></tr><tr><td>Protocol version</td><td><pre>1073742163</pre></td><td><pre>1073742164</pre></td></tr></table>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
+ rule_test_type.txt
- rule_test.txt
```

</details>
<details>
<summary>
block_predicate_type
</summary>

```diff
+ minecraft:below_heightmap
```

</details>
<details>
<summary>
environment_attribute
</summary>

```diff
+ minecraft:visual/has_sky_occluder
```

</details>
<details>
<summary>
sound_event
</summary>

```diff
+ minecraft:entity.zombie_nautilus.riding
```

</details>
</details>
<hr/>
<details><summary><b><ins>TAGS</ins></b><a name="tags"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
+ universal_tags/rule_test_type.json
- universal_tags/rule_test.json
```

</details>
<details>
<summary>
universal_tags/block_predicate_type.json
</summary>

```diff
+ minecraft:below_heightmap
```

</details>
<details>
<summary>
universal_tags/environment_attribute.json
</summary>

```diff
+ minecraft:visual/has_sky_occluder
```

</details>
<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:entity.zombie_nautilus.riding
```

</details>
</details>
<hr/>
<details><summary><b><ins>DATAPACKS</ins></b><a name="datapacks"></a></summary>
<br/>
<details>
<summary>
[registries] List
</summary>

```diff
- minecraft:rule_test
+ minecraft:rule_test_type
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
+ options.improvedTransparency.oitWithImprovedFog.tooltip: An experimental approach that uses an order-independent transparency algorithm to avoid graphical issues normally present when looking through multiple layers of translucent objects.
This option will also blend the sky background and the clouds with render distance-based fog to make the boundary between the terrain and the sky invisible.
This will impact performance.
+ subtitles.entity.zombie_nautilus.riding: Zombie Nautilus bubbles
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>26.4-snapshot-1</th><th>26.4-snapshot-2</th></tr>
<tr><th align="left"><div style="width:290px">advancement.advancementNotFound</div></th><td>Unknown advancement: %s</td><td>Unknown advancement '%s'</td></tr>
<tr><th align="left"><div style="width:290px">advancements.husbandry.uh_oh.title</div></th><td>Uh Oh</td><td>Uh-Oh</td></tr>
<tr><th align="left"><div style="width:290px">advancements.nether.distract_piglin.title</div></th><td>Oh Shiny</td><td>Oooh, Shiny!</td></tr>
<tr><th align="left"><div style="width:290px">argument.anchor.invalid</div></th><td>Invalid entity anchor position %s</td><td>Invalid entity anchor position '%s'</td></tr>
<tr><th align="left"><div style="width:290px">argument.component.invalid</div></th><td>Invalid chat component: %s</td><td>Invalid chat component '%s'</td></tr>
<tr><th align="left"><div style="width:290px">argument.gamemode.invalid</div></th><td>Unknown game mode: %s</td><td>Unknown game mode '%s'</td></tr>
<tr><th align="left"><div style="width:290px">argument.id.unknown</div></th><td>Unknown ID: %s</td><td>Unknown ID '%s'</td></tr>
<tr><th align="left"><div style="width:290px">argument.style.invalid</div></th><td>Invalid style: %s</td><td>Invalid style '%s'</td></tr>
<tr><th align="left"><div style="width:290px">argument.swing_animation.invalid</div></th><td>Unknown swing animation type: %s</td><td>Unknown swing animation type '%s'</td></tr>
<tr><th align="left"><div style="width:290px">arguments.function.unknown</div></th><td>Unknown function %s</td><td>Unknown function '%s'</td></tr>
<tr><th align="left"><div style="width:290px">chat_restriction.chat_disabled_by_options.action</div></th><td>Go to the Chat Settings screen</td><td>Go to the Chat Settings Screen</td></tr>
<tr><th align="left"><div style="width:290px">chat_screen.title</div></th><td>Chat screen</td><td>Chat Screen</td></tr>
<tr><th align="left"><div style="width:290px">chat.copy.click</div></th><td>Click to Copy to Clipboard</td><td>Click to copy to clipboard</td></tr>
<tr><th align="left"><div style="width:290px">command.compute.result.named.invalid</div></th><td>%s returned invalid value (%s)</td><td>%s returned an invalid value (%s)</td></tr>
<tr><th align="left"><div style="width:290px">command.compute.result.unnamed.invalid</div></th><td>Number provider returned invalid value (%s)</td><td>Number provider returned an invalid value (%s)</td></tr>
<tr><th align="left"><div style="width:290px">commands.data.modify.invalid_index</div></th><td>Invalid list index: %s</td><td>Invalid list index '%s'</td></tr>
<tr><th align="left"><div style="width:290px">commands.function.error.argument_not_compound</div></th><td>Invalid argument type: %s. Expected Compound</td><td>Invalid argument type '%s'. Expected Compound</td></tr>
<tr><th align="left"><div style="width:290px">commands.item.source.no_such_slot.unnamed</div></th><td>The source does not have specified slots</td><td>The source does not have the specified slots</td></tr>
<tr><th align="left"><div style="width:290px">commands.item.target.failed</div></th><td>No targets accepted items into specified slots</td><td>No targets accepted items into the specified slots</td></tr>
<tr><th align="left"><div style="width:290px">commands.item.target.failed.known_item</div></th><td>No targets accepted item %s into specified slots</td><td>No targets accepted item %s into the specified slots</td></tr>
<tr><th align="left"><div style="width:290px">commands.item.target.no_such_slot.unnamed</div></th><td>The target does not have specified slots</td><td>The target does not have the specified slots</td></tr>
<tr><th align="left"><div style="width:290px">commands.posteffect.list.success</div></th><td>Player %s has %s post effects: %s</td><td>Player %s has %s post effect(s): %s</td></tr>
<tr><th align="left"><div style="width:290px">commands.spreadplayers.failed.invalid.height</div></th><td>Invalid maxHeight %s; expected higher than world minimum %s</td><td>Invalid maxHeight '%s'; expected higher than world minimum %s</td></tr>
<tr><th align="left"><div style="width:290px">disconnect.loginFailedInfo.invalidSession</div></th><td>Invalid session (Try restarting your game and the launcher)</td><td>Invalid session (try restarting your game and the launcher)</td></tr>
<tr><th align="left"><div style="width:290px">gamerule.doMobLoot.description</div></th><td>Controls resource drops from mobs, including experience orbs.</td><td>Controls resource drops from mobs, including Experience Orbs.</td></tr>
<tr><th align="left"><div style="width:290px">gamerule.doTileDrops.description</div></th><td>Controls resource drops from blocks, including experience orbs.</td><td>Controls resource drops from blocks, including Experience Orbs.</td></tr>
<tr><th align="left"><div style="width:290px">gui.recipebook.moreRecipes</div></th><td>Right Click for More</td><td>Right-Click for More</td></tr>
<tr><th align="left"><div style="width:290px">item_modifier.unknown</div></th><td>Unknown item modifier: %s</td><td>Unknown item modifier '%s'</td></tr>
<tr><th align="left"><div style="width:290px">jigsaw_block.final_state</div></th><td>Turns into:</td><td>Turns Into:</td></tr>
<tr><th align="left"><div style="width:290px">mco.configure.world.invite_codes.subtitle</div></th><td>You can add up to %s invite codes and share them so people can join your Realm</td><td>You can create up to %s invite codes and share them so people can join your Realm</td></tr>
<tr><th align="left"><div style="width:290px">mco.snapshotRealmsPopup.message</div></th><td>Realms is now available in Snapshots starting with Snapshot 23w41a. Every Realms subscription comes with a free Snapshot Realm that is separate from your normal Java Realm!</td><td>Realms is now available in snapshots starting with Snapshot 23w41a. Every Realms subscription comes with a free Snapshot Realm that is separate from your normal Java Realm!</td></tr>
<tr><th align="left"><div style="width:290px">mco.snapshotRealmsPopup.title</div></th><td>Realms is now available in Snapshots</td><td>Realms is now available in snapshots</td></tr>
<tr><th align="left"><div style="width:290px">multiplayer.socialInteractions.not_available</div></th><td>Social Interactions are only available in Multiplayer worlds</td><td>Social Interactions are only available in multiplayer worlds</td></tr>
<tr><th align="left"><div style="width:290px">narration.button.usage.hovered</div></th><td>Left click to activate</td><td>Left-click to activate</td></tr>
<tr><th align="left"><div style="width:290px">narration.checkbox.usage.hovered</div></th><td>Left click to toggle</td><td>Left-click to toggle</td></tr>
<tr><th align="left"><div style="width:290px">narration.checkbox.usage.hovered.check</div></th><td>Left click to check</td><td>Left-click to check</td></tr>
<tr><th align="left"><div style="width:290px">narration.checkbox.usage.hovered.uncheck</div></th><td>Left click to uncheck</td><td>Left-click to uncheck</td></tr>
<tr><th align="left"><div style="width:290px">narration.cycle_button.usage.hovered</div></th><td>Left click to switch to %s</td><td>Left-click to switch to %s</td></tr>
<tr><th align="left"><div style="width:290px">narration.link.usage.hovered</div></th><td>Left click to follow the link</td><td>Left-click to follow the link</td></tr>
<tr><th align="left"><div style="width:290px">narration.recipe.usage</div></th><td>Left click to select</td><td>Left-click to select</td></tr>
<tr><th align="left"><div style="width:290px">narration.recipe.usage.more</div></th><td>Right click to show more recipes</td><td>Right-click to show more recipes</td></tr>
<tr><th align="left"><div style="width:290px">options.ctrlClickEmulatesRightClick</div></th><td>Right Click Emulation</td><td>Right-Click Emulation</td></tr>
<tr><th align="left"><div style="width:290px">options.debugGuiScale.tooltip</div></th><td>Overrides the debug overlay with a different GUI scale than the rest of the game</td><td>Overrides the debug overlay with a different GUI scale than the rest of the game.</td></tr>
<tr><th align="left"><div style="width:290px">options.directionalAudio.off.tooltip</div></th><td>Classic Stereo sound.</td><td>Classic stereo sound.</td></tr>
<tr><th align="left"><div style="width:290px">options.fullscreen.entry</div></th><td>%sx%s@%s (%sbit)</td><td>%sx%s@%s (%s-bit)</td></tr>
<tr><th align="left"><div style="width:290px">options.fullscreen.unavailable</div></th><td>Setting unavailable</td><td>Setting Unavailable</td></tr>
<tr><th align="left"><div style="width:290px">options.hideMatchedNames.tooltip</div></th><td>3rd-party Servers may send chat messages in non-standard formats.

With this option on, hidden players will be matched based on chat sender names.</td><td>Third-party servers may send chat messages in non-standard formats.

With this option on, hidden players will be matched based on chat sender names.</td></tr>
<tr><th align="left"><div style="width:290px">options.inactivityFpsLimit</div></th><td>Reduce fps when</td><td>Reduce FPS When</td></tr>
<tr><th align="left"><div style="width:290px">options.inGameNotification.tooltip</div></th><td>Show Friend notifications in-game</td><td>Show friend notifications in-game</td></tr>
<tr><th align="left"><div style="width:290px">options.macFullscreenMenuVisibility.tooltip</div></th><td>Whether the macOS Menu bar and Dock can be revealed by moving the mouse to the edge of the screen while in non-exclusive fullscreen.</td><td>Whether the macOS menu bar and Dock can be revealed by moving the mouse to the edge of the screen while in non-exclusive fullscreen.</td></tr>
<tr><th align="left"><div style="width:290px">options.vignette.tooltip</div></th><td>This is a subtle texture over the game screen used for reducing brightness towards the edges of the screen and warning about the world border.</td><td>This is a subtle texture over the game screen used for reducing brightness toward the edges of the screen and warning about the world border.</td></tr>
<tr><th align="left"><div style="width:290px">options.worldOptions.guest.command_access.disabled.scope.tooltip</div></th><td>Cannot change the command access of players joining your world when the world's multiplayer scope is set to "Off".</td><td>Cannot change the command access of players joining your world when "LAN" is set to "OFF".</td></tr>
<tr><th align="left"><div style="width:290px">options.worldOptions.guest.command_access.tooltip</div></th><td>Controls whether players that join your world can use commands or not.</td><td>Controls whether players that join your world can use commands.</td></tr>
<tr><th align="left"><div style="width:290px">options.worldOptions.guest.force_game_mode.off.scope.tooltip</div></th><td>Cannot change this setting when the world's multiplayer scope is set to "Off".</td><td>Cannot change this setting when "LAN" is set to "OFF".</td></tr>
<tr><th align="left"><div style="width:290px">particle.notFound</div></th><td>Unknown particle: %s</td><td>Unknown particle '%s'</td></tr>
<tr><th align="left"><div style="width:290px">predicate.unknown</div></th><td>Unknown predicate: %s</td><td>Unknown predicate '%s'</td></tr>
<tr><th align="left"><div style="width:290px">recipe.notFound</div></th><td>Unknown recipe: %s</td><td>Unknown recipe '%s'</td></tr>
<tr><th align="left"><div style="width:290px">selectWorld.backupQuestion.experimental</div></th><td>Worlds using Experimental Settings are not supported</td><td>Worlds using experimental settings are not supported</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.block.anvil.destroy</div></th><td>Anvil destroyed</td><td>Anvil breaks</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.block.anvil.land</div></th><td>Anvil landed</td><td>Anvil lands</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.block.anvil.use</div></th><td>Anvil used</td><td>Anvil is used</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.block.beacon.power_select</div></th><td>Beacon power selected</td><td>Beacon power is selected</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.block.chest.locked</div></th><td>Chest locked</td><td>Chest lock clangs</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.block.composter.empty</div></th><td>Composter emptied</td><td>Composter empties</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.block.composter.fill</div></th><td>Composter filled</td><td>Composter is filled</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.block.dispenser.dispense</div></th><td>Dispensed item</td><td>Dispenser dispenses item</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.block.dispenser.fail</div></th><td>Dispenser failed</td><td>Dispenser fails</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.block.enchantment_table.use</div></th><td>Enchanting Table used</td><td>Enchanting Table is used</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.block.fire.extinguish</div></th><td>Fire extinguished</td><td>Fire extinguishes</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.block.generic.place</div></th><td>Block placed</td><td>Block is placed</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.block.grindstone.use</div></th><td>Grindstone used</td><td>Grindstone is used</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.block.growing_plant.crop</div></th><td>Plant cropped</td><td>Plant is cropped</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.block.honey_block.slide</div></th><td>Sliding down a honey block</td><td>Sliding down a Honey Block</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.block.shelf.place_item</div></th><td>Item placed</td><td>Item is placed</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.block.shelf.take_item</div></th><td>Item taken</td><td>Item is taken</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.block.smithing_table.use</div></th><td>Smithing Table used</td><td>Smithing Table is used</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.chiseled_bookshelf.insert</div></th><td>Book placed</td><td>Book is placed</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.chiseled_bookshelf.insert_enchanted</div></th><td>Enchanted Book placed</td><td>Enchanted Book is placed</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.chiseled_bookshelf.take</div></th><td>Book taken</td><td>Book is taken</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.chiseled_bookshelf.take_enchanted</div></th><td>Enchanted Book taken</td><td>Enchanted Book is taken</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.allay.hurt</div></th><td>Allay hurts</td><td>Allay is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.armadillo.hurt</div></th><td>Armadillo hurts</td><td>Armadillo is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.armor_stand.fall</div></th><td>Something fell</td><td>Something falls</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.arrow.hit_player</div></th><td>Player hit</td><td>Player is hit</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.arrow.shoot</div></th><td>Arrow fired</td><td>Arrow is fired</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.axolotl.hurt</div></th><td>Axolotl hurts</td><td>Axolotl is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.baby_cat.hurt</div></th><td>Kitten hurts</td><td>Kitten is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.baby_chicken.hurts</div></th><td>Chick hurts</td><td>Chick is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.baby_horse.hurt</div></th><td>Foal hurts</td><td>Foal is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.baby_nautilus.hurt</div></th><td>Baby Nautilus hurts</td><td>Baby Nautilus is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.baby_nautilus.hurt_land</div></th><td>Baby Nautilus hurts</td><td>Baby Nautilus is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.baby_pig.hurt</div></th><td>Baby Pig hurts</td><td>Baby Pig is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.baby_wolf.hurt</div></th><td>Puppy hurts</td><td>Puppy is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.bat.hurt</div></th><td>Bat hurts</td><td>Bat is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.bee.hurt</div></th><td>Bee hurts</td><td>Bee is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.blaze.hurt</div></th><td>Blaze hurts</td><td>Blaze is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.bogged.hurt</div></th><td>Bogged hurts</td><td>Bogged is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.breeze.hurt</div></th><td>Breeze hurts</td><td>Breeze is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.camel_husk.hurt</div></th><td>Camel Husk hurts</td><td>Camel Husk is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.camel_husk.saddle</div></th><td>Saddle equips</td><td>Saddle is equipped</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.camel.hurt</div></th><td>Camel hurts</td><td>Camel is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.camel.saddle</div></th><td>Saddle equips</td><td>Saddle is equipped</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.cat.hurt</div></th><td>Cat hurts</td><td>Cat is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.chicken.hurt</div></th><td>Chicken hurts</td><td>Chicken is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.cod.hurt</div></th><td>Cod hurts</td><td>Cod is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.copper_golem_oxidized.hurt</div></th><td>Copper Golem hurts</td><td>Copper Golem is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.copper_golem_weathered.hurt</div></th><td>Copper Golem hurts</td><td>Copper Golem is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.copper_golem.hurt</div></th><td>Copper Golem hurts</td><td>Copper Golem is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.cow.hurt</div></th><td>Cow hurts</td><td>Cow is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.creeper.hurt</div></th><td>Creeper hurts</td><td>Creeper is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.dolphin.hurt</div></th><td>Dolphin hurts</td><td>Dolphin is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.donkey.chest</div></th><td>Donkey Chest equips</td><td>Donkey Chest is equipped</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.donkey.hurt</div></th><td>Donkey hurts</td><td>Donkey is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.drowned.hurt</div></th><td>Drowned hurts</td><td>Drowned is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.elder_guardian.hurt</div></th><td>Elder Guardian hurts</td><td>Elder Guardian is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.ender_dragon.hurt</div></th><td>Dragon hurts</td><td>Dragon is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.enderman.hurt</div></th><td>Enderman hurts</td><td>Enderman is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.endermite.hurt</div></th><td>Endermite hurts</td><td>Endermite is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.evoker.hurt</div></th><td>Evoker hurts</td><td>Evoker is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.evoker.prepare_summon</div></th><td>Evoker prepares summoning</td><td>Evoker prepares to summon</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.evoker.prepare_wololo</div></th><td>Evoker prepares charming</td><td>Evoker prepares to charm</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.fishing_bobber.retrieve</div></th><td>Bobber retrieved</td><td>Bobber is retrieved</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.fishing_bobber.throw</div></th><td>Bobber thrown</td><td>Bobber is thrown</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.fox.aggro</div></th><td>Fox angers</td><td>Fox gets angry</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.fox.hurt</div></th><td>Fox hurts</td><td>Fox is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.frog.hurt</div></th><td>Frog hurts</td><td>Frog is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.generic.big_fall</div></th><td>Something fell</td><td>Something falls</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.generic.hurt</div></th><td>Something hurts</td><td>Something is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.ghast.hurt</div></th><td>Ghast hurts</td><td>Ghast is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.ghastling.hurt</div></th><td>Ghastling hurts</td><td>Ghastling is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.glow_item_frame.add_item</div></th><td>Glow Item Frame fills</td><td>Glow Item Frame is filled</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.glow_item_frame.break</div></th><td>Glow Item Frame broken</td><td>Glow Item Frame breaks</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.glow_item_frame.place</div></th><td>Glow Item Frame placed</td><td>Glow Item Frame is placed</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.glow_squid.hurt</div></th><td>Glow Squid hurts</td><td>Glow Squid is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.goat.hurt</div></th><td>Goat hurts</td><td>Goat is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.guardian.hurt</div></th><td>Guardian hurts</td><td>Guardian is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.happy_ghast.equip</div></th><td>Harness equips</td><td>Harness is equipped</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.happy_ghast.hurt</div></th><td>Happy Ghast hurts</td><td>Happy Ghast is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.happy_ghast.unequip</div></th><td>Harness unequips</td><td>Harness is unequipped</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.hoglin.hurt</div></th><td>Hoglin hurts</td><td>Hoglin is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.horse.armor</div></th><td>Horse armor equips</td><td>Horse armor is equipped</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.horse.hurt</div></th><td>Horse hurts</td><td>Horse is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.horse.saddle</div></th><td>Saddle equips</td><td>Saddle is equipped</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.husk.hurt</div></th><td>Husk hurts</td><td>Husk is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.illusioner.hurt</div></th><td>Illusioner hurts</td><td>Illusioner is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.iron_golem.hurt</div></th><td>Iron Golem hurts</td><td>Iron Golem is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.iron_golem.repair</div></th><td>Iron Golem repaired</td><td>Iron Golem is repaired</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.item_frame.add_item</div></th><td>Item Frame fills</td><td>Item Frame is filled</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.item_frame.break</div></th><td>Item Frame broken</td><td>Item Frame breaks</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.item_frame.place</div></th><td>Item Frame placed</td><td>Item Frame is placed</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.leash_knot.break</div></th><td>Leash Knot broken</td><td>Leash Knot breaks</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.leash_knot.place</div></th><td>Leash Knot tied</td><td>Leash Knot is tied</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.llama.chest</div></th><td>Llama Chest equips</td><td>Llama Chest is equipped</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.llama.hurt</div></th><td>Llama hurts</td><td>Llama is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.magma_cube.hurt</div></th><td>Magma Cube hurts</td><td>Magma Cube is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.mule.chest</div></th><td>Mule Chest equips</td><td>Mule Chest is equipped</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.mule.hurt</div></th><td>Mule hurts</td><td>Mule is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.nautilus.hurt</div></th><td>Nautilus hurts</td><td>Nautilus is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.nautilus.hurt_land</div></th><td>Nautilus hurts</td><td>Nautilus is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.painting.break</div></th><td>Painting broken</td><td>Painting breaks</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.painting.place</div></th><td>Painting placed</td><td>Painting is placed</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.panda.hurt</div></th><td>Panda hurts</td><td>Panda is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.parched.hurt</div></th><td>Parched hurts</td><td>Parched is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.parrot.hurts</div></th><td>Parrot hurts</td><td>Parrot is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.parrot.imitate.wither</div></th><td>Parrot angers</td><td>Parrot gets angry</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.phantom.hurt</div></th><td>Phantom hurts</td><td>Phantom is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.pig.hurt</div></th><td>Pig hurts</td><td>Pig is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.pig.saddle</div></th><td>Saddle equips</td><td>Saddle is equipped</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.piglin_brute.hurt</div></th><td>Piglin Brute hurts</td><td>Piglin Brute is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.piglin.hurt</div></th><td>Piglin hurts</td><td>Piglin is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.pillager.hurt</div></th><td>Pillager hurts</td><td>Pillager is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.player.burp</div></th><td>Burp</td><td>Player burps</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.player.hurt</div></th><td>Player hurts</td><td>Player is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.player.hurt_drown</div></th><td>Player drowning</td><td>Player is drowning</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.player.hurt_on_fire</div></th><td>Player burns</td><td>Player is burning</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.polar_bear.hurt</div></th><td>Polar Bear hurts</td><td>Polar Bear is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.potion.throw</div></th><td>Bottle thrown</td><td>Bottle is thrown</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.puffer_fish.hurt</div></th><td>Pufferfish hurts</td><td>Pufferfish is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.rabbit.hurt</div></th><td>Rabbit hurts</td><td>Rabbit is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.ravager.hurt</div></th><td>Ravager hurts</td><td>Ravager is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.salmon.hurt</div></th><td>Salmon hurts</td><td>Salmon is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.sheep.hurt</div></th><td>Sheep hurts</td><td>Sheep is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.shulker.hurt</div></th><td>Shulker hurts</td><td>Shulker is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.silverfish.hurt</div></th><td>Silverfish hurts</td><td>Silverfish is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.skeleton_horse.hurt</div></th><td>Skeleton Horse hurts</td><td>Skeleton Horse is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.skeleton.hurt</div></th><td>Skeleton hurts</td><td>Skeleton is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.slime.hurt</div></th><td>Slime hurts</td><td>Slime is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.small_sulfur_cube.hurt</div></th><td>Small Sulfur Cube hurts</td><td>Small Sulfur Cube is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.sniffer.hurt</div></th><td>Sniffer hurts</td><td>Sniffer is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.snow_golem.hurt</div></th><td>Snow Golem hurts</td><td>Snow Golem is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.spider.hurt</div></th><td>Spider hurts</td><td>Spider is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.squid.hurt</div></th><td>Squid hurts</td><td>Squid is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.stray.hurt</div></th><td>Stray hurts</td><td>Stray is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.strider.hurt</div></th><td>Strider hurts</td><td>Strider is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.sulfur_cube.hurt</div></th><td>Sulfur Cube hurts</td><td>Sulfur Cube is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.tadpole.hurt</div></th><td>Tadpole hurts</td><td>Tadpole is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.tropical_fish.hurt</div></th><td>Tropical Fish hurts</td><td>Tropical Fish is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.turtle.hurt</div></th><td>Turtle hurts</td><td>Turtle is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.turtle.hurt_baby</div></th><td>Baby Turtle hurts</td><td>Baby Turtle is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.vex.hurt</div></th><td>Vex hurts</td><td>Vex is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.villager.hurt</div></th><td>Villager hurts</td><td>Villager is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.vindicator.hurt</div></th><td>Vindicator hurts</td><td>Vindicator is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.wandering_trader.hurt</div></th><td>Wandering Trader hurts</td><td>Wandering Trader is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.warden.hurt</div></th><td>Warden hurts</td><td>Warden is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.witch.hurt</div></th><td>Witch hurts</td><td>Witch is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.wither_skeleton.hurt</div></th><td>Wither Skeleton hurts</td><td>Wither Skeleton is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.wither.ambient</div></th><td>Wither angers</td><td>Wither gets angry</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.wither.hurt</div></th><td>Wither hurts</td><td>Wither is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.wolf.hurt</div></th><td>Wolf hurts</td><td>Wolf is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.zoglin.hurt</div></th><td>Zoglin hurts</td><td>Zoglin is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.zombie_horse.hurt</div></th><td>Zombie Horse hurts</td><td>Zombie Horse is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.zombie_nautilus.hurt</div></th><td>Zombie Nautilus hurts</td><td>Zombie Nautilus is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.zombie_nautilus.hurt_land</div></th><td>Zombie Nautilus hurts</td><td>Zombie Nautilus is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.zombie_villager.hurt</div></th><td>Zombie Villager hurts</td><td>Zombie Villager is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.zombie.destroy_egg</div></th><td>Turtle Egg stomped</td><td>Turtle Egg is stomped</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.zombie.hurt</div></th><td>Zombie hurts</td><td>Zombie is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.entity.zombified_piglin.hurt</div></th><td>Zombified Piglin hurts</td><td>Zombified Piglin is hurt</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.item.armor.equip</div></th><td>Gear equips</td><td>Gear is equipped</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.item.armor.equip_nautilus</div></th><td>Nautilus Armor equips</td><td>Nautilus Armor is equipped</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.item.armor.unequip_nautilus</div></th><td>Nautilus Armor unequips</td><td>Nautilus Armor is unequipped</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.item.brush.brushing.gravel.complete</div></th><td>Brushing Gravel completed</td><td>Brushing Gravel is completed</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.item.brush.brushing.sand.complete</div></th><td>Brushing Sand completed</td><td>Brushing Sand is completed</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.item.bucket.fill_axolotl</div></th><td>Axolotl scooped</td><td>Axolotl is scooped</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.item.bucket.fill_fish</div></th><td>Fish captured</td><td>Fish is captured</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.item.bucket.fill_sulfur_cube</div></th><td>Sulfur Cube scooped</td><td>Sulfur Cube is scooped</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.item.bucket.fill_tadpole</div></th><td>Tadpole captured</td><td>Tadpole is captured</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.item.bundle.insert</div></th><td>Item packed</td><td>Item is packed</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.item.bundle.insert_fail</div></th><td>Bundle full</td><td>Bundle rejects an item</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.item.bundle.remove_one</div></th><td>Item unpacked</td><td>Item is unpacked</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.item.crop.plant</div></th><td>Crop planted</td><td>Crop is planted</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.item.flintandsteel.use</div></th><td>Flint and Steel click</td><td>Flint and Steel clicks</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.item.nautilus_saddle_equip</div></th><td>Saddle equips</td><td>Saddle is equipped</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.item.nautilus_saddle_underwater_equip</div></th><td>Saddle equips</td><td>Saddle is equipped</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.item.nether_wart.plant</div></th><td>Crop planted</td><td>Crop is planted</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.item.underwater_saddle.equip</div></th><td>Saddle equips</td><td>Saddle is equipped</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.ui.cartography_table.take_result</div></th><td>Map drawn</td><td>Map is drawn</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.ui.hud.bubble_pop</div></th><td>Breath meter dropping</td><td>Breath meter drops</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.ui.loom.take_result</div></th><td>Loom used</td><td>Loom is used</td></tr>
<tr><th align="left"><div style="width:290px">subtitles.ui.stonecutter.take_result</div></th><td>Stonecutter used</td><td>Stonecutter is used</td></tr>
<tr><th align="left"><div style="width:290px">telemetry.event.world_loaded.description</div></th><td>Knowing how players play Minecraft (such as Game Mode, client or server modded, and game version) allows us to focus game updates to improve the areas that players care about most.

The World Loaded event is paired with the World Unloaded event to calculate how long the play session has lasted.</td><td>Knowing how players play Minecraft (such as game mode, client or server modded, and game version) allows us to focus game updates to improve the areas that players care about most.

The World Loaded event is paired with the World Unloaded event to calculate how long the play session has lasted.</td></tr>
<tr><th align="left"><div style="width:290px">test.error.sequence.invalid_tick</div></th><td>Succeeded in invalid tick: expected %s</td><td>Succeeded in an invalid tick: expected %s</td></tr>
<tr><th align="left"><div style="width:290px">test.player.coordinates</div></th><td>Player coordinates: [%s, %s, %s] in %s</td><td>Player coordinates: %s, %s, %s in %s</td></tr>
<tr><th align="left"><div style="width:290px">test.run.coordinates</div></th><td>Test coordinates: [%s, %s, %s] in %s</td><td>Test coordinates: %s, %s, %s in %s</td></tr>
<tr><th align="left"><div style="width:290px">title.multiplayer.other</div></th><td>Multiplayer (3rd-party Server)</td><td>Multiplayer (Third-party Server)</td></tr>
<tr><th align="left"><div style="width:290px">tutorial.bundleInsert.description</div></th><td>Right Click to add items</td><td>Right-click to add items</td></tr>
</table>
<br/>
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
+ minecraft/shaders/core/blit_clouds.fsh
- minecraft/shaders/core/screenquad.vsh
+ minecraft/shaders/core/screentriangle.vsh
+ minecraft/shaders/core/sky_occluder.fsh
+ minecraft/shaders/core/sky_occluder.vsh
+ minecraft/shaders/include/fullscreen_triangle.glsl
```

</details>
</details>
<hr/>