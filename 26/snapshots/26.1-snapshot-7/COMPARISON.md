## Comparison with [26.1-snapshot-6](https://github.com/PixiGeko/Minecraft-generated-data/tree/26.1-snapshot-6)

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
<table><tr><th></th><th align="left">26.1-snapshot-6</th><th>26.1-snapshot-7</th></tr><tr><td>DataPack version</td><td><pre>99.0</pre></td><td><pre>99.1</pre></td></tr><tr><td>ResourcePack version</td><td><pre>80.0</pre></td><td><pre>81.0</pre></td></tr><tr><td>World version</td><td><pre>4774</pre></td><td><pre>4775</pre></td></tr><tr><td>Protocol version</td><td><pre>1073742116</pre></td><td><pre>1073742117</pre></td></tr></table>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
data_component_type
</summary>

```diff
+ minecraft:cat/sound_variant
+ minecraft:chicken/sound_variant
+ minecraft:cow/sound_variant
+ minecraft:pig/sound_variant
```

</details>
<details>
<summary>
sound_event
</summary>

```diff
+ minecraft:block.note_block.trumpet
+ minecraft:block.note_block.trumpet_exposed
+ minecraft:block.note_block.trumpet_oxidized
+ minecraft:block.note_block.trumpet_weathered
+ minecraft:entity.cat_royal.ambient
+ minecraft:entity.cat_royal.beg_for_food
+ minecraft:entity.cat_royal.death
+ minecraft:entity.cat_royal.eat
+ minecraft:entity.cat_royal.hiss
+ minecraft:entity.cat_royal.hurt
+ minecraft:entity.cat_royal.purr
+ minecraft:entity.cat_royal.purreow
+ minecraft:entity.cat_royal.stray_ambient
+ minecraft:entity.chicken_picky.ambient
+ minecraft:entity.chicken_picky.death
+ minecraft:entity.chicken_picky.hurt
+ minecraft:entity.cow_moody.ambient
+ minecraft:entity.cow_moody.death
+ minecraft:entity.cow_moody.hurt
+ minecraft:entity.cow_moody.step
+ minecraft:entity.pig_big.ambient
+ minecraft:entity.pig_big.death
+ minecraft:entity.pig_big.hurt
+ minecraft:entity.pig_mini.ambient
+ minecraft:entity.pig_mini.death
+ minecraft:entity.pig_mini.hurt
```

</details>
</details>
<hr/>
<details><summary><b><ins>TAGS</ins></b><a name="tags"></a></summary>
<br/>
<details>
<summary>
universal_tags/data_component_type.json
</summary>

```diff
+ minecraft:cat/sound_variant
+ minecraft:chicken/sound_variant
+ minecraft:cow/sound_variant
+ minecraft:pig/sound_variant
```

</details>
<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:block.note_block.trumpet
+ minecraft:block.note_block.trumpet_exposed
+ minecraft:block.note_block.trumpet_oxidized
+ minecraft:block.note_block.trumpet_weathered
+ minecraft:entity.cat_royal.ambient
+ minecraft:entity.cat_royal.beg_for_food
+ minecraft:entity.cat_royal.death
+ minecraft:entity.cat_royal.eat
+ minecraft:entity.cat_royal.hiss
+ minecraft:entity.cat_royal.hurt
+ minecraft:entity.cat_royal.purr
+ minecraft:entity.cat_royal.purreow
+ minecraft:entity.cat_royal.stray_ambient
+ minecraft:entity.chicken_picky.ambient
+ minecraft:entity.chicken_picky.death
+ minecraft:entity.chicken_picky.hurt
+ minecraft:entity.cow_moody.ambient
+ minecraft:entity.cow_moody.death
+ minecraft:entity.cow_moody.hurt
+ minecraft:entity.cow_moody.step
+ minecraft:entity.pig_big.ambient
+ minecraft:entity.pig_big.death
+ minecraft:entity.pig_big.hurt
+ minecraft:entity.pig_mini.ambient
+ minecraft:entity.pig_mini.death
+ minecraft:entity.pig_mini.hurt
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
+ minecraft:cat_sound_variant
+ minecraft:chicken_sound_variant
+ minecraft:cow_sound_variant
+ minecraft:pig_sound_variant
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
+ chat_restriction.chat_and_commands_disabled_by_options: Chat is restricted in client settings.
+ chat_restriction.chat_disabled_by_options: Player chat is restricted in client settings.
+ chat_restriction.chat_disabled_by_options.action: Go to Chat Settings screen
+ chat_restriction.disabled_by_launcher: Chat is restricted by launcher
+ chat_restriction.disabled_by_profile: Chat is restricted by profile settings.
+ chat_restriction.disabled_by_profile.action: Go to your profile settings
+ chat_screen.commands_not_allowed: Sending commands is not allowed
+ chat_screen.messages_not_allowed: Sending chat messages is not allowed
+ chat_screen.restricted: Chat is restricted. Click this message for details.
+ chat_screen.restricted.narration: Chat is restricted. Go to the Restrictions screen in World Options.
+ gui.socialInteractions.tooltip.report.chat_disabled_or_blocked: This player can't be reported because chat is disabled or blocked
+ restrictions_screen.button: Restrictions...
+ restrictions_screen.permission.receive_player_messages.allowed: You can receive messages from players
+ restrictions_screen.permission.receive_player_messages.denied: You can't receive messages from players
+ restrictions_screen.permission.receive_system_messages.allowed: You can receive system messages from server
+ restrictions_screen.permission.receive_system_messages.denied: You can't receive system messages from server
+ restrictions_screen.permission.send_commands.allowed: You can send commands
+ restrictions_screen.permission.send_commands.denied: You can't send commands
+ restrictions_screen.permission.send_messages.allowed: You can send chat messages
+ restrictions_screen.permission.send_messages.denied: You can't send chat messages
+ restrictions_screen.title: Restrictions
+ subtitles.entity.baby_horse.land: Foal lands
+ upgradeWorld.aborted.message: This may happen if another program accessed the world during the upgrade.
It may help to restart your computer and trying again. If the issue persists, please consider reporting a bug.
+ upgradeWorld.aborted.reportBug: Report a Bug
+ upgradeWorld.aborted.title: Failed to upgrade the world
+ upgradeWorld.failed_cleanup.message: The world was successfully upgraded to the current version and is now available in the world list.
We encountered issues when cleaning up outdated data, therefore the name of the world folder has changed to %s.
+ upgradeWorld.failed_cleanup.title: Successfully upgraded the world
```

</details>
<details>
<summary>
Changes
</summary>
<br/>
<table>
<tr><th>Name</th><th>26.1-snapshot-6</th><th>26.1-snapshot-7</th></tr>
<tr><th align="left"><div style="width:290px">selectWorld.backupWarning.file_fixing_required</div></th><td>This world needs to be upgraded before you can play it. We strongly suggest creating a backup before continuing in case you experience world corruptions.</td><td>This world needs to be upgraded before you can play it. We strongly suggest creating a backup before continuing in case you experience world corruption.</td></tr>
<tr><th align="left"><div style="width:290px">selectWorld.backupWarning.snapshot</div></th><td>This world was last played in version %s; you are on version %s. Please make a backup in case you experience world corruptions.</td><td>This world was last played in version %s; you are on version %s. Please make a backup in case you experience world corruption.</td></tr>
<tr><th align="left"><div style="width:290px">selectWorld.world_gen_settings_access</div></th><td>Unable to read or access world gen settings file! %s</td><td>Unable to read or access the world gen settings file! %s</td></tr>
<tr><th align="left"><div style="width:290px">upgradeWorld.symlink.title</div></th><td>Can't upgrade world</td><td>Can't upgrade the world</td></tr>
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
+ reports/minecraft/components/cat_sound_variant/classic.json
+ reports/minecraft/components/cat_sound_variant/royal.json
+ reports/minecraft/components/chicken_sound_variant/classic.json
+ reports/minecraft/components/chicken_sound_variant/picky.json
+ reports/minecraft/components/cow_sound_variant/classic.json
+ reports/minecraft/components/cow_sound_variant/moody.json
+ reports/minecraft/components/data_component_type/cat/sound_variant.json
+ reports/minecraft/components/data_component_type/chicken/sound_variant.json
+ reports/minecraft/components/data_component_type/cow/sound_variant.json
+ reports/minecraft/components/data_component_type/pig/sound_variant.json
+ reports/minecraft/components/pig_sound_variant/big.json
+ reports/minecraft/components/pig_sound_variant/classic.json
+ reports/minecraft/components/pig_sound_variant/mini.json
+ reports/minecraft/components/sound_event/block.note_block.trumpet_exposed.json
+ reports/minecraft/components/sound_event/block.note_block.trumpet_oxidized.json
+ reports/minecraft/components/sound_event/block.note_block.trumpet_weathered.json
+ reports/minecraft/components/sound_event/block.note_block.trumpet.json
+ reports/minecraft/components/sound_event/entity.cat_royal.ambient.json
+ reports/minecraft/components/sound_event/entity.cat_royal.beg_for_food.json
+ reports/minecraft/components/sound_event/entity.cat_royal.death.json
+ reports/minecraft/components/sound_event/entity.cat_royal.eat.json
+ reports/minecraft/components/sound_event/entity.cat_royal.hiss.json
+ reports/minecraft/components/sound_event/entity.cat_royal.hurt.json
+ reports/minecraft/components/sound_event/entity.cat_royal.purr.json
+ reports/minecraft/components/sound_event/entity.cat_royal.purreow.json
+ reports/minecraft/components/sound_event/entity.cat_royal.stray_ambient.json
+ reports/minecraft/components/sound_event/entity.chicken_picky.ambient.json
+ reports/minecraft/components/sound_event/entity.chicken_picky.death.json
+ reports/minecraft/components/sound_event/entity.chicken_picky.hurt.json
+ reports/minecraft/components/sound_event/entity.cow_moody.ambient.json
+ reports/minecraft/components/sound_event/entity.cow_moody.death.json
+ reports/minecraft/components/sound_event/entity.cow_moody.hurt.json
+ reports/minecraft/components/sound_event/entity.cow_moody.step.json
+ reports/minecraft/components/sound_event/entity.pig_big.ambient.json
+ reports/minecraft/components/sound_event/entity.pig_big.death.json
+ reports/minecraft/components/sound_event/entity.pig_big.hurt.json
+ reports/minecraft/components/sound_event/entity.pig_mini.ambient.json
+ reports/minecraft/components/sound_event/entity.pig_mini.death.json
+ reports/minecraft/components/sound_event/entity.pig_mini.hurt.json
```

</details>
<details>
<summary>
data
</summary>

```diff
+ minecraft/cat_sound_variant/classic.json
+ minecraft/cat_sound_variant/royal.json
+ minecraft/chicken_sound_variant/classic.json
+ minecraft/chicken_sound_variant/picky.json
+ minecraft/cow_sound_variant/classic.json
+ minecraft/cow_sound_variant/moody.json
+ minecraft/pig_sound_variant/big.json
+ minecraft/pig_sound_variant/classic.json
+ minecraft/pig_sound_variant/mini.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/textures/entity/equipment/humanoid_baby/chainmail.png
+ minecraft/textures/entity/equipment/humanoid_baby/copper.png
+ minecraft/textures/entity/equipment/humanoid_baby/diamond.png
+ minecraft/textures/entity/equipment/humanoid_baby/gold.png
+ minecraft/textures/entity/equipment/humanoid_baby/iron.png
+ minecraft/textures/entity/equipment/humanoid_baby/leather_overlay.png
+ minecraft/textures/entity/equipment/humanoid_baby/leather.png
+ minecraft/textures/entity/equipment/humanoid_baby/netherite.png
+ minecraft/textures/entity/equipment/humanoid_baby/turtle_scute.png
+ minecraft/textures/entity/piglin/piglin_baby.png
+ minecraft/textures/entity/piglin/zombified_piglin_baby.png
+ minecraft/textures/entity/villager/baby/desert.png
+ minecraft/textures/entity/villager/baby/jungle.png
+ minecraft/textures/entity/villager/baby/plains.png
+ minecraft/textures/entity/villager/baby/savanna.png
+ minecraft/textures/entity/villager/baby/snow.png
+ minecraft/textures/entity/villager/baby/swamp.png
+ minecraft/textures/entity/villager/baby/taiga.png
+ minecraft/textures/entity/villager/villager_baby.png
+ minecraft/textures/entity/zombie_villager/baby/desert.png
+ minecraft/textures/entity/zombie_villager/baby/jungle.png
+ minecraft/textures/entity/zombie_villager/baby/plains.png
+ minecraft/textures/entity/zombie_villager/baby/savanna.png
+ minecraft/textures/entity/zombie_villager/baby/snow.png
+ minecraft/textures/entity/zombie_villager/baby/swamp.png
+ minecraft/textures/entity/zombie_villager/baby/taiga.png
+ minecraft/textures/entity/zombie_villager/zombie_villager_baby.png
+ minecraft/textures/entity/zombie/drowned_baby.png
+ minecraft/textures/entity/zombie/drowned_outer_layer_baby.png
+ minecraft/textures/entity/zombie/husk_baby.png
+ minecraft/textures/entity/zombie/zombie_baby.png
```

</details>
</details>
<hr/>