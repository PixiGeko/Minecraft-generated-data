## Comparison with [26.1-snapshot-5](https://github.com/PixiGeko/Minecraft-generated-data/tree/26.1-snapshot-5)

> [!TIP]
> - [Version data](#version-data)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Translations](#translations)
> - [File structure](#file-structure)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">26.1-snapshot-5</th><th>26.1-snapshot-6</th></tr><tr><td>DataPack version</td><td><pre>98.0</pre></td><td><pre>99.0</pre></td></tr><tr><td>ResourcePack version</td><td><pre>79.0</pre></td><td><pre>80.0</pre></td></tr><tr><td>World version</td><td><pre>4770</pre></td><td><pre>4774</pre></td></tr><tr><td>Protocol version</td><td><pre>1073742115</pre></td><td><pre>1073742116</pre></td></tr></table>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
sound_event
</summary>

```diff
+ minecraft:entity.baby_chicken.step
```

</details>
<details>
<summary>
worldgen/feature
</summary>

```diff
+ minecraft:block_blob
- minecraft:forest_rock
- minecraft:ice_spike
+ minecraft:spike
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
+ minecraft:entity.baby_chicken.step
```

</details>
<details>
<summary>
universal_tags/worldgen/feature.json
</summary>

```diff
+ minecraft:block_blob
- minecraft:forest_rock
- minecraft:ice_spike
+ minecraft:spike
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
+ selecteWorld.backupRequiredTooltip: Loading the world requires taking a backup first
+ selectWorld.backupQuestion.file_fixing_required: Create a backup before upgrading this world?
+ selectWorld.backupWarning.file_fixing_required: This world needs to be upgraded before you can play it. We strongly suggest creating a backup before continuing in case you experience world corruptions.
+ selectWorld.requiresFileFixingTooltip.edit: This world needs to be upgraded to the latest version before you can edit it due to underlying changes to the world format.
+ selectWorld.requiresFileFixingTooltip.play: This world needs to be upgraded to the latest version before you can play it due to underlying changes to the world format.
+ selectWorld.requiresFileFixingTooltip.recreate: This world needs to be upgraded to the latest version before you can recreate it due to underlying changes to the world format.
+ selectWorld.upgrade_and_play: Upgrade and Play
+ selectWorld.waitingForBackup.message: Depending on the size of your world, this may take a while. Please do not close the game or shut off your device.
+ selectWorld.waitingForBackup.title: Creating Backup
+ selectWorld.world_gen_settings_access: Unable to read or access world gen settings file! %s
+ upgradeWorld.done: Upgrading World Completed
+ upgradeWorld.info.converted: Upgraded: %s
+ upgradeWorld.info.file_fix_stage: Stage: %s/%s
+ upgradeWorld.info.scanning: Scanning files...
+ upgradeWorld.info.total: Total: %s
+ upgradeWorld.joinNow: Do you want to join the world now?
+ upgradeWorld.progress.percentage: %s%%
+ upgradeWorld.progress.type.files: Moving files
+ upgradeWorld.progress.type.legacy_structures: Upgrading legacy structures
+ upgradeWorld.progress.type.region: Upgrading regions
+ upgradeWorld.symlink.message: The selected world contains symbolic links.
The required steps to upgrade the world to the current version do not support the use of symbolic links. To upgrade the world, the links need to be resolved first.
+ upgradeWorld.symlink.title: Can't upgrade world
+ upgradeWorld.title: Upgrading World Files
```

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
+ reports/minecraft/components/sound_event/entity.baby_chicken.step.json
+ reports/minecraft/components/worldgen/feature/block_blob.json
- reports/minecraft/components/worldgen/feature/forest_rock.json
- reports/minecraft/components/worldgen/feature/ice_spike.json
+ reports/minecraft/components/worldgen/feature/spike.json
```

</details>
<details>
<summary>
data
</summary>

```diff
+ minecraft/tags/block/beneath_bamboo_podzol_replaceable.json
+ minecraft/tags/block/beneath_tree_podzol_replaceable.json
+ minecraft/tags/block/cannot_replace_below_tree_trunk.json
+ minecraft/tags/block/forest_rock_can_place_on.json
+ minecraft/tags/block/grass_blocks.json
+ minecraft/tags/block/huge_brown_mushroom_can_place_on.json
+ minecraft/tags/block/huge_red_mushroom_can_place_on.json
+ minecraft/tags/block/ice_spike_replaceable.json
+ minecraft/tags/block/moss_blocks.json
+ minecraft/tags/block/mud.json
+ minecraft/tags/block/substrate_overworld.json
+ minecraft/tags/item/grass_blocks.json
+ minecraft/tags/item/moss_blocks.json
+ minecraft/tags/item/mud.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/equipment/trader_llama_baby.json
+ minecraft/shaders/core/item.fsh
+ minecraft/shaders/core/item.vsh
- minecraft/shaders/core/rendertype_entity_alpha.fsh
- minecraft/shaders/core/rendertype_entity_alpha.vsh
- minecraft/shaders/core/rendertype_entity_decal.fsh
- minecraft/shaders/core/rendertype_entity_decal.vsh
- minecraft/shaders/core/rendertype_item_entity_translucent_cull.fsh
- minecraft/shaders/core/rendertype_item_entity_translucent_cull.vsh
+ minecraft/textures/entity/armadillo/armadillo_baby.png
+ minecraft/textures/entity/bear/polarbear_baby.png
+ minecraft/textures/entity/bee/bee_angry_baby.png
+ minecraft/textures/entity/bee/bee_angry_nectar_baby.png
+ minecraft/textures/entity/bee/bee_baby.png
+ minecraft/textures/entity/bee/bee_nectar_baby.png
+ minecraft/textures/entity/camel/camel_baby.png
+ minecraft/textures/entity/equipment/llama_body/trader_llama_baby.png
+ minecraft/textures/entity/fox/fox_baby.png
+ minecraft/textures/entity/fox/fox_sleep_baby.png
+ minecraft/textures/entity/fox/fox_snow_baby.png
+ minecraft/textures/entity/fox/fox_snow_sleep_baby.png
+ minecraft/textures/entity/goat/goat_baby.png
+ minecraft/textures/entity/llama/llama_brown_baby.png
+ minecraft/textures/entity/llama/llama_creamy_baby.png
+ minecraft/textures/entity/llama/llama_gray_baby.png
+ minecraft/textures/entity/llama/llama_white_baby.png
```

</details>
</details>
<hr/>