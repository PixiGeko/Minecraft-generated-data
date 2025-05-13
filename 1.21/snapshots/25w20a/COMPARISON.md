## Comparison with [25w19a](https://github.com/PixiGeko/Minecraft-generated-data/tree/25w19a)

> [!TIP]
> - [Version data](#version-data)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Items (registry)](#items-(registry))
> - [Commands](#commands)
> - [Recipes](#recipes)
> - [Datapacks](#datapacks)
> - [Translations](#translations)
> - [Packets](#packets)
> - [File structure](#file-structure)
> - [Credits](#credits)
> - [Mojang Studios](#credits-mojang-studios)
>     - [Mojang Studios Leadership](#credits-mojang-studios-mojang-studios-leadership)
>     - [Design](#credits-mojang-studios-design)
>     - [Programming](#credits-mojang-studios-programming)
>     - [Production](#credits-mojang-studios-production)
>     - [Visual Arts](#credits-mojang-studios-visual-arts)
>     - [Audio](#credits-mojang-studios-audio)
>     - [Quality Assessment](#credits-mojang-studios-quality-assessment)
>     - [Operations](#credits-mojang-studios-operations)
>     - [Player Care](#credits-mojang-studios-player-care)
>     - [Data Analytics](#credits-mojang-studios-data-analytics)
>     - [Business Management & Licensing](#credits-mojang-studios-business-management-&-licensing)
>     - [Brand Management](#credits-mojang-studios-brand-management)
>     - [Communications](#credits-mojang-studios-communications)
>     - [Marketing](#credits-mojang-studios-marketing)
>     - [Finance](#credits-mojang-studios-finance)
> - [Development Partner - Blackbird Interactive](#credits-development-partner---blackbird-interactive)
>     - [Main](#credits-development-partner---blackbird-interactive-main)
> - [Development Partner - Disbelief](#credits-development-partner---disbelief)
>     - [Main](#credits-development-partner---disbelief-main)
> - [Mojang Studios Alumni](#credits-mojang-studios-alumni)
>     - [Main](#credits-mojang-studios-alumni-main)
> - [Studios Quality Alumni](#credits-studios-quality-alumni)
>     - [Main](#credits-studios-quality-alumni-main)
> - [Development Partner - Blackbird Interactive Alumni](#credits-development-partner---blackbird-interactive-alumni)
>     - [Main](#credits-development-partner---blackbird-interactive-alumni-main)
> - [Development Partner - SiProgs Alumni](#credits-development-partner---siprogs-alumni)
>     - [Main](#credits-development-partner---siprogs-alumni-main)
> - [Development Partner - Skybox Alumni](#credits-development-partner---skybox-alumni)
>     - [Main](#credits-development-partner---skybox-alumni-main)
> - [Misc](#misc)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">25w19a</th><th>25w20a</th></tr><tr><td>DataPack version</td><td><pre>76</pre></td><td><pre>77</pre></td></tr><tr><td>ResourcePack version</td><td><pre>60</pre></td><td><pre>61</pre></td></tr><tr><td>World version</td><td><pre>4427</pre></td><td><pre>4428</pre></td></tr><tr><td>Protocol version</td><td><pre>1073742073</pre></td><td><pre>1073742074</pre></td></tr></table>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
+ dialog_body_type.txt
+ dialog_type.txt
+ input_control_type.txt
+ submit_method_type.txt
```

</details>
<details>
<summary>
command_argument_type
</summary>

```diff
+ minecraft:dialog
```

</details>
<details>
<summary>
item
</summary>

```diff
+ minecraft:music_disc_tears
```

</details>
<details>
<summary>
sound_event
</summary>

```diff
+ minecraft:music_disc.tears
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
+ universal_tags/dialog_body_type.json
+ universal_tags/dialog_type.json
+ universal_tags/input_control_type.json
+ universal_tags/submit_method_type.json
```

</details>
<details>
<summary>
universal_tags/command_argument_type.json
</summary>

```diff
+ minecraft:dialog
```

</details>
<details>
<summary>
universal_tags/item.json
</summary>

```diff
+ minecraft:music_disc_tears
```

</details>
<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:music_disc.tears
```

</details>
</details>
<hr/>
<details><summary><b><ins>ITEMS (REGISTRY)</ins></b><a name="items-(registry)"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
+ music_disc_tears.json
```

</details>
<details>
<summary>
black_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w19a</th><th>25w20a</th></tr><tr><td>minecraft:equippable</td><td><pre>{
  "allowed_entities": [
    "minecraft:llama",
    "minecraft:trader_llama"
  ],
  "asset_id": "minecraft:black_carpet",
  "equip_sound": "minecraft:entity.llama.swag",
  "slot": "body"
}</pre></td><td><pre>{
  "allowed_entities": [
    "minecraft:llama",
    "minecraft:trader_llama"
  ],
  "asset_id": "minecraft:black_carpet",
  "can_be_sheared": true,
  "equip_sound": "minecraft:entity.llama.swag",
  "slot": "body"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
black_harness
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w19a</th><th>25w20a</th></tr><tr><td>minecraft:equippable</td><td><pre>{
  "allowed_entities": "#minecraft:can_equip_harness",
  "asset_id": "minecraft:black_harness",
  "equip_on_interact": true,
  "equip_sound": "minecraft:entity.happy_ghast.equip",
  "slot": "body"
}</pre></td><td><pre>{
  "allowed_entities": "#minecraft:can_equip_harness",
  "asset_id": "minecraft:black_harness",
  "can_be_sheared": true,
  "equip_on_interact": true,
  "equip_sound": "minecraft:entity.happy_ghast.equip",
  "shearing_sound": "minecraft:entity.happy_ghast.unequip",
  "slot": "body"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w19a</th><th>25w20a</th></tr><tr><td>minecraft:equippable</td><td><pre>{
  "allowed_entities": [
    "minecraft:llama",
    "minecraft:trader_llama"
  ],
  "asset_id": "minecraft:blue_carpet",
  "equip_sound": "minecraft:entity.llama.swag",
  "slot": "body"
}</pre></td><td><pre>{
  "allowed_entities": [
    "minecraft:llama",
    "minecraft:trader_llama"
  ],
  "asset_id": "minecraft:blue_carpet",
  "can_be_sheared": true,
  "equip_sound": "minecraft:entity.llama.swag",
  "slot": "body"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
blue_harness
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w19a</th><th>25w20a</th></tr><tr><td>minecraft:equippable</td><td><pre>{
  "allowed_entities": "#minecraft:can_equip_harness",
  "asset_id": "minecraft:blue_harness",
  "equip_on_interact": true,
  "equip_sound": "minecraft:entity.happy_ghast.equip",
  "slot": "body"
}</pre></td><td><pre>{
  "allowed_entities": "#minecraft:can_equip_harness",
  "asset_id": "minecraft:blue_harness",
  "can_be_sheared": true,
  "equip_on_interact": true,
  "equip_sound": "minecraft:entity.happy_ghast.equip",
  "shearing_sound": "minecraft:entity.happy_ghast.unequip",
  "slot": "body"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w19a</th><th>25w20a</th></tr><tr><td>minecraft:equippable</td><td><pre>{
  "allowed_entities": [
    "minecraft:llama",
    "minecraft:trader_llama"
  ],
  "asset_id": "minecraft:brown_carpet",
  "equip_sound": "minecraft:entity.llama.swag",
  "slot": "body"
}</pre></td><td><pre>{
  "allowed_entities": [
    "minecraft:llama",
    "minecraft:trader_llama"
  ],
  "asset_id": "minecraft:brown_carpet",
  "can_be_sheared": true,
  "equip_sound": "minecraft:entity.llama.swag",
  "slot": "body"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
brown_harness
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w19a</th><th>25w20a</th></tr><tr><td>minecraft:equippable</td><td><pre>{
  "allowed_entities": "#minecraft:can_equip_harness",
  "asset_id": "minecraft:brown_harness",
  "equip_on_interact": true,
  "equip_sound": "minecraft:entity.happy_ghast.equip",
  "slot": "body"
}</pre></td><td><pre>{
  "allowed_entities": "#minecraft:can_equip_harness",
  "asset_id": "minecraft:brown_harness",
  "can_be_sheared": true,
  "equip_on_interact": true,
  "equip_sound": "minecraft:entity.happy_ghast.equip",
  "shearing_sound": "minecraft:entity.happy_ghast.unequip",
  "slot": "body"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w19a</th><th>25w20a</th></tr><tr><td>minecraft:equippable</td><td><pre>{
  "allowed_entities": [
    "minecraft:llama",
    "minecraft:trader_llama"
  ],
  "asset_id": "minecraft:cyan_carpet",
  "equip_sound": "minecraft:entity.llama.swag",
  "slot": "body"
}</pre></td><td><pre>{
  "allowed_entities": [
    "minecraft:llama",
    "minecraft:trader_llama"
  ],
  "asset_id": "minecraft:cyan_carpet",
  "can_be_sheared": true,
  "equip_sound": "minecraft:entity.llama.swag",
  "slot": "body"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
cyan_harness
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w19a</th><th>25w20a</th></tr><tr><td>minecraft:equippable</td><td><pre>{
  "allowed_entities": "#minecraft:can_equip_harness",
  "asset_id": "minecraft:cyan_harness",
  "equip_on_interact": true,
  "equip_sound": "minecraft:entity.happy_ghast.equip",
  "slot": "body"
}</pre></td><td><pre>{
  "allowed_entities": "#minecraft:can_equip_harness",
  "asset_id": "minecraft:cyan_harness",
  "can_be_sheared": true,
  "equip_on_interact": true,
  "equip_sound": "minecraft:entity.happy_ghast.equip",
  "shearing_sound": "minecraft:entity.happy_ghast.unequip",
  "slot": "body"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
diamond_horse_armor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w19a</th><th>25w20a</th></tr><tr><td>minecraft:equippable</td><td><pre>{
  "allowed_entities": "#minecraft:can_wear_horse_armor",
  "asset_id": "minecraft:diamond",
  "damage_on_hurt": false,
  "equip_sound": "minecraft:entity.horse.armor",
  "slot": "body"
}</pre></td><td><pre>{
  "allowed_entities": "#minecraft:can_wear_horse_armor",
  "asset_id": "minecraft:diamond",
  "can_be_sheared": true,
  "damage_on_hurt": false,
  "equip_sound": "minecraft:entity.horse.armor",
  "slot": "body"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
golden_horse_armor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w19a</th><th>25w20a</th></tr><tr><td>minecraft:equippable</td><td><pre>{
  "allowed_entities": "#minecraft:can_wear_horse_armor",
  "asset_id": "minecraft:gold",
  "damage_on_hurt": false,
  "equip_sound": "minecraft:entity.horse.armor",
  "slot": "body"
}</pre></td><td><pre>{
  "allowed_entities": "#minecraft:can_wear_horse_armor",
  "asset_id": "minecraft:gold",
  "can_be_sheared": true,
  "damage_on_hurt": false,
  "equip_sound": "minecraft:entity.horse.armor",
  "slot": "body"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w19a</th><th>25w20a</th></tr><tr><td>minecraft:equippable</td><td><pre>{
  "allowed_entities": [
    "minecraft:llama",
    "minecraft:trader_llama"
  ],
  "asset_id": "minecraft:gray_carpet",
  "equip_sound": "minecraft:entity.llama.swag",
  "slot": "body"
}</pre></td><td><pre>{
  "allowed_entities": [
    "minecraft:llama",
    "minecraft:trader_llama"
  ],
  "asset_id": "minecraft:gray_carpet",
  "can_be_sheared": true,
  "equip_sound": "minecraft:entity.llama.swag",
  "slot": "body"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
gray_harness
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w19a</th><th>25w20a</th></tr><tr><td>minecraft:equippable</td><td><pre>{
  "allowed_entities": "#minecraft:can_equip_harness",
  "asset_id": "minecraft:gray_harness",
  "equip_on_interact": true,
  "equip_sound": "minecraft:entity.happy_ghast.equip",
  "slot": "body"
}</pre></td><td><pre>{
  "allowed_entities": "#minecraft:can_equip_harness",
  "asset_id": "minecraft:gray_harness",
  "can_be_sheared": true,
  "equip_on_interact": true,
  "equip_sound": "minecraft:entity.happy_ghast.equip",
  "shearing_sound": "minecraft:entity.happy_ghast.unequip",
  "slot": "body"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w19a</th><th>25w20a</th></tr><tr><td>minecraft:equippable</td><td><pre>{
  "allowed_entities": [
    "minecraft:llama",
    "minecraft:trader_llama"
  ],
  "asset_id": "minecraft:green_carpet",
  "equip_sound": "minecraft:entity.llama.swag",
  "slot": "body"
}</pre></td><td><pre>{
  "allowed_entities": [
    "minecraft:llama",
    "minecraft:trader_llama"
  ],
  "asset_id": "minecraft:green_carpet",
  "can_be_sheared": true,
  "equip_sound": "minecraft:entity.llama.swag",
  "slot": "body"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
green_harness
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w19a</th><th>25w20a</th></tr><tr><td>minecraft:equippable</td><td><pre>{
  "allowed_entities": "#minecraft:can_equip_harness",
  "asset_id": "minecraft:green_harness",
  "equip_on_interact": true,
  "equip_sound": "minecraft:entity.happy_ghast.equip",
  "slot": "body"
}</pre></td><td><pre>{
  "allowed_entities": "#minecraft:can_equip_harness",
  "asset_id": "minecraft:green_harness",
  "can_be_sheared": true,
  "equip_on_interact": true,
  "equip_sound": "minecraft:entity.happy_ghast.equip",
  "shearing_sound": "minecraft:entity.happy_ghast.unequip",
  "slot": "body"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
iron_horse_armor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w19a</th><th>25w20a</th></tr><tr><td>minecraft:equippable</td><td><pre>{
  "allowed_entities": "#minecraft:can_wear_horse_armor",
  "asset_id": "minecraft:iron",
  "damage_on_hurt": false,
  "equip_sound": "minecraft:entity.horse.armor",
  "slot": "body"
}</pre></td><td><pre>{
  "allowed_entities": "#minecraft:can_wear_horse_armor",
  "asset_id": "minecraft:iron",
  "can_be_sheared": true,
  "damage_on_hurt": false,
  "equip_sound": "minecraft:entity.horse.armor",
  "slot": "body"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
leather_horse_armor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w19a</th><th>25w20a</th></tr><tr><td>minecraft:equippable</td><td><pre>{
  "allowed_entities": "#minecraft:can_wear_horse_armor",
  "asset_id": "minecraft:leather",
  "damage_on_hurt": false,
  "equip_sound": "minecraft:entity.horse.armor",
  "slot": "body"
}</pre></td><td><pre>{
  "allowed_entities": "#minecraft:can_wear_horse_armor",
  "asset_id": "minecraft:leather",
  "can_be_sheared": true,
  "damage_on_hurt": false,
  "equip_sound": "minecraft:entity.horse.armor",
  "slot": "body"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w19a</th><th>25w20a</th></tr><tr><td>minecraft:equippable</td><td><pre>{
  "allowed_entities": [
    "minecraft:llama",
    "minecraft:trader_llama"
  ],
  "asset_id": "minecraft:light_blue_carpet",
  "equip_sound": "minecraft:entity.llama.swag",
  "slot": "body"
}</pre></td><td><pre>{
  "allowed_entities": [
    "minecraft:llama",
    "minecraft:trader_llama"
  ],
  "asset_id": "minecraft:light_blue_carpet",
  "can_be_sheared": true,
  "equip_sound": "minecraft:entity.llama.swag",
  "slot": "body"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_blue_harness
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w19a</th><th>25w20a</th></tr><tr><td>minecraft:equippable</td><td><pre>{
  "allowed_entities": "#minecraft:can_equip_harness",
  "asset_id": "minecraft:light_blue_harness",
  "equip_on_interact": true,
  "equip_sound": "minecraft:entity.happy_ghast.equip",
  "slot": "body"
}</pre></td><td><pre>{
  "allowed_entities": "#minecraft:can_equip_harness",
  "asset_id": "minecraft:light_blue_harness",
  "can_be_sheared": true,
  "equip_on_interact": true,
  "equip_sound": "minecraft:entity.happy_ghast.equip",
  "shearing_sound": "minecraft:entity.happy_ghast.unequip",
  "slot": "body"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w19a</th><th>25w20a</th></tr><tr><td>minecraft:equippable</td><td><pre>{
  "allowed_entities": [
    "minecraft:llama",
    "minecraft:trader_llama"
  ],
  "asset_id": "minecraft:light_gray_carpet",
  "equip_sound": "minecraft:entity.llama.swag",
  "slot": "body"
}</pre></td><td><pre>{
  "allowed_entities": [
    "minecraft:llama",
    "minecraft:trader_llama"
  ],
  "asset_id": "minecraft:light_gray_carpet",
  "can_be_sheared": true,
  "equip_sound": "minecraft:entity.llama.swag",
  "slot": "body"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
light_gray_harness
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w19a</th><th>25w20a</th></tr><tr><td>minecraft:equippable</td><td><pre>{
  "allowed_entities": "#minecraft:can_equip_harness",
  "asset_id": "minecraft:light_gray_harness",
  "equip_on_interact": true,
  "equip_sound": "minecraft:entity.happy_ghast.equip",
  "slot": "body"
}</pre></td><td><pre>{
  "allowed_entities": "#minecraft:can_equip_harness",
  "asset_id": "minecraft:light_gray_harness",
  "can_be_sheared": true,
  "equip_on_interact": true,
  "equip_sound": "minecraft:entity.happy_ghast.equip",
  "shearing_sound": "minecraft:entity.happy_ghast.unequip",
  "slot": "body"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w19a</th><th>25w20a</th></tr><tr><td>minecraft:equippable</td><td><pre>{
  "allowed_entities": [
    "minecraft:llama",
    "minecraft:trader_llama"
  ],
  "asset_id": "minecraft:lime_carpet",
  "equip_sound": "minecraft:entity.llama.swag",
  "slot": "body"
}</pre></td><td><pre>{
  "allowed_entities": [
    "minecraft:llama",
    "minecraft:trader_llama"
  ],
  "asset_id": "minecraft:lime_carpet",
  "can_be_sheared": true,
  "equip_sound": "minecraft:entity.llama.swag",
  "slot": "body"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
lime_harness
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w19a</th><th>25w20a</th></tr><tr><td>minecraft:equippable</td><td><pre>{
  "allowed_entities": "#minecraft:can_equip_harness",
  "asset_id": "minecraft:lime_harness",
  "equip_on_interact": true,
  "equip_sound": "minecraft:entity.happy_ghast.equip",
  "slot": "body"
}</pre></td><td><pre>{
  "allowed_entities": "#minecraft:can_equip_harness",
  "asset_id": "minecraft:lime_harness",
  "can_be_sheared": true,
  "equip_on_interact": true,
  "equip_sound": "minecraft:entity.happy_ghast.equip",
  "shearing_sound": "minecraft:entity.happy_ghast.unequip",
  "slot": "body"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w19a</th><th>25w20a</th></tr><tr><td>minecraft:equippable</td><td><pre>{
  "allowed_entities": [
    "minecraft:llama",
    "minecraft:trader_llama"
  ],
  "asset_id": "minecraft:magenta_carpet",
  "equip_sound": "minecraft:entity.llama.swag",
  "slot": "body"
}</pre></td><td><pre>{
  "allowed_entities": [
    "minecraft:llama",
    "minecraft:trader_llama"
  ],
  "asset_id": "minecraft:magenta_carpet",
  "can_be_sheared": true,
  "equip_sound": "minecraft:entity.llama.swag",
  "slot": "body"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
magenta_harness
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w19a</th><th>25w20a</th></tr><tr><td>minecraft:equippable</td><td><pre>{
  "allowed_entities": "#minecraft:can_equip_harness",
  "asset_id": "minecraft:magenta_harness",
  "equip_on_interact": true,
  "equip_sound": "minecraft:entity.happy_ghast.equip",
  "slot": "body"
}</pre></td><td><pre>{
  "allowed_entities": "#minecraft:can_equip_harness",
  "asset_id": "minecraft:magenta_harness",
  "can_be_sheared": true,
  "equip_on_interact": true,
  "equip_sound": "minecraft:entity.happy_ghast.equip",
  "shearing_sound": "minecraft:entity.happy_ghast.unequip",
  "slot": "body"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w19a</th><th>25w20a</th></tr><tr><td>minecraft:equippable</td><td><pre>{
  "allowed_entities": [
    "minecraft:llama",
    "minecraft:trader_llama"
  ],
  "asset_id": "minecraft:orange_carpet",
  "equip_sound": "minecraft:entity.llama.swag",
  "slot": "body"
}</pre></td><td><pre>{
  "allowed_entities": [
    "minecraft:llama",
    "minecraft:trader_llama"
  ],
  "asset_id": "minecraft:orange_carpet",
  "can_be_sheared": true,
  "equip_sound": "minecraft:entity.llama.swag",
  "slot": "body"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
orange_harness
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w19a</th><th>25w20a</th></tr><tr><td>minecraft:equippable</td><td><pre>{
  "allowed_entities": "#minecraft:can_equip_harness",
  "asset_id": "minecraft:orange_harness",
  "equip_on_interact": true,
  "equip_sound": "minecraft:entity.happy_ghast.equip",
  "slot": "body"
}</pre></td><td><pre>{
  "allowed_entities": "#minecraft:can_equip_harness",
  "asset_id": "minecraft:orange_harness",
  "can_be_sheared": true,
  "equip_on_interact": true,
  "equip_sound": "minecraft:entity.happy_ghast.equip",
  "shearing_sound": "minecraft:entity.happy_ghast.unequip",
  "slot": "body"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w19a</th><th>25w20a</th></tr><tr><td>minecraft:equippable</td><td><pre>{
  "allowed_entities": [
    "minecraft:llama",
    "minecraft:trader_llama"
  ],
  "asset_id": "minecraft:pink_carpet",
  "equip_sound": "minecraft:entity.llama.swag",
  "slot": "body"
}</pre></td><td><pre>{
  "allowed_entities": [
    "minecraft:llama",
    "minecraft:trader_llama"
  ],
  "asset_id": "minecraft:pink_carpet",
  "can_be_sheared": true,
  "equip_sound": "minecraft:entity.llama.swag",
  "slot": "body"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
pink_harness
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w19a</th><th>25w20a</th></tr><tr><td>minecraft:equippable</td><td><pre>{
  "allowed_entities": "#minecraft:can_equip_harness",
  "asset_id": "minecraft:pink_harness",
  "equip_on_interact": true,
  "equip_sound": "minecraft:entity.happy_ghast.equip",
  "slot": "body"
}</pre></td><td><pre>{
  "allowed_entities": "#minecraft:can_equip_harness",
  "asset_id": "minecraft:pink_harness",
  "can_be_sheared": true,
  "equip_on_interact": true,
  "equip_sound": "minecraft:entity.happy_ghast.equip",
  "shearing_sound": "minecraft:entity.happy_ghast.unequip",
  "slot": "body"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w19a</th><th>25w20a</th></tr><tr><td>minecraft:equippable</td><td><pre>{
  "allowed_entities": [
    "minecraft:llama",
    "minecraft:trader_llama"
  ],
  "asset_id": "minecraft:purple_carpet",
  "equip_sound": "minecraft:entity.llama.swag",
  "slot": "body"
}</pre></td><td><pre>{
  "allowed_entities": [
    "minecraft:llama",
    "minecraft:trader_llama"
  ],
  "asset_id": "minecraft:purple_carpet",
  "can_be_sheared": true,
  "equip_sound": "minecraft:entity.llama.swag",
  "slot": "body"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
purple_harness
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w19a</th><th>25w20a</th></tr><tr><td>minecraft:equippable</td><td><pre>{
  "allowed_entities": "#minecraft:can_equip_harness",
  "asset_id": "minecraft:purple_harness",
  "equip_on_interact": true,
  "equip_sound": "minecraft:entity.happy_ghast.equip",
  "slot": "body"
}</pre></td><td><pre>{
  "allowed_entities": "#minecraft:can_equip_harness",
  "asset_id": "minecraft:purple_harness",
  "can_be_sheared": true,
  "equip_on_interact": true,
  "equip_sound": "minecraft:entity.happy_ghast.equip",
  "shearing_sound": "minecraft:entity.happy_ghast.unequip",
  "slot": "body"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w19a</th><th>25w20a</th></tr><tr><td>minecraft:equippable</td><td><pre>{
  "allowed_entities": [
    "minecraft:llama",
    "minecraft:trader_llama"
  ],
  "asset_id": "minecraft:red_carpet",
  "equip_sound": "minecraft:entity.llama.swag",
  "slot": "body"
}</pre></td><td><pre>{
  "allowed_entities": [
    "minecraft:llama",
    "minecraft:trader_llama"
  ],
  "asset_id": "minecraft:red_carpet",
  "can_be_sheared": true,
  "equip_sound": "minecraft:entity.llama.swag",
  "slot": "body"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
red_harness
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w19a</th><th>25w20a</th></tr><tr><td>minecraft:equippable</td><td><pre>{
  "allowed_entities": "#minecraft:can_equip_harness",
  "asset_id": "minecraft:red_harness",
  "equip_on_interact": true,
  "equip_sound": "minecraft:entity.happy_ghast.equip",
  "slot": "body"
}</pre></td><td><pre>{
  "allowed_entities": "#minecraft:can_equip_harness",
  "asset_id": "minecraft:red_harness",
  "can_be_sheared": true,
  "equip_on_interact": true,
  "equip_sound": "minecraft:entity.happy_ghast.equip",
  "shearing_sound": "minecraft:entity.happy_ghast.unequip",
  "slot": "body"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
saddle
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w19a</th><th>25w20a</th></tr><tr><td>minecraft:equippable</td><td><pre>{
  "allowed_entities": "#minecraft:can_equip_saddle",
  "asset_id": "minecraft:saddle",
  "equip_on_interact": true,
  "equip_sound": "minecraft:entity.horse.saddle",
  "slot": "saddle"
}</pre></td><td><pre>{
  "allowed_entities": "#minecraft:can_equip_saddle",
  "asset_id": "minecraft:saddle",
  "can_be_sheared": true,
  "equip_on_interact": true,
  "equip_sound": "minecraft:entity.horse.saddle",
  "slot": "saddle"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w19a</th><th>25w20a</th></tr><tr><td>minecraft:equippable</td><td><pre>{
  "allowed_entities": [
    "minecraft:llama",
    "minecraft:trader_llama"
  ],
  "asset_id": "minecraft:white_carpet",
  "equip_sound": "minecraft:entity.llama.swag",
  "slot": "body"
}</pre></td><td><pre>{
  "allowed_entities": [
    "minecraft:llama",
    "minecraft:trader_llama"
  ],
  "asset_id": "minecraft:white_carpet",
  "can_be_sheared": true,
  "equip_sound": "minecraft:entity.llama.swag",
  "slot": "body"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
white_harness
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w19a</th><th>25w20a</th></tr><tr><td>minecraft:equippable</td><td><pre>{
  "allowed_entities": "#minecraft:can_equip_harness",
  "asset_id": "minecraft:white_harness",
  "equip_on_interact": true,
  "equip_sound": "minecraft:entity.happy_ghast.equip",
  "slot": "body"
}</pre></td><td><pre>{
  "allowed_entities": "#minecraft:can_equip_harness",
  "asset_id": "minecraft:white_harness",
  "can_be_sheared": true,
  "equip_on_interact": true,
  "equip_sound": "minecraft:entity.happy_ghast.equip",
  "shearing_sound": "minecraft:entity.happy_ghast.unequip",
  "slot": "body"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
wolf_armor
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w19a</th><th>25w20a</th></tr><tr><td>minecraft:equippable</td><td><pre>{
  "allowed_entities": "minecraft:wolf",
  "asset_id": "minecraft:armadillo_scute",
  "equip_sound": "minecraft:item.armor.equip_wolf",
  "slot": "body"
}</pre></td><td><pre>{
  "allowed_entities": "minecraft:wolf",
  "asset_id": "minecraft:armadillo_scute",
  "can_be_sheared": true,
  "equip_sound": "minecraft:item.armor.equip_wolf",
  "shearing_sound": "minecraft:item.armor.unequip_wolf",
  "slot": "body"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_carpet
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w19a</th><th>25w20a</th></tr><tr><td>minecraft:equippable</td><td><pre>{
  "allowed_entities": [
    "minecraft:llama",
    "minecraft:trader_llama"
  ],
  "asset_id": "minecraft:yellow_carpet",
  "equip_sound": "minecraft:entity.llama.swag",
  "slot": "body"
}</pre></td><td><pre>{
  "allowed_entities": [
    "minecraft:llama",
    "minecraft:trader_llama"
  ],
  "asset_id": "minecraft:yellow_carpet",
  "can_be_sheared": true,
  "equip_sound": "minecraft:entity.llama.swag",
  "slot": "body"
}</pre></td></tr></table>
<br/>
</details>
<details>
<summary>
yellow_harness
</summary>
<br/>
<b>COMPONENTS</b>

<table><tr><th></th><th align="left">25w19a</th><th>25w20a</th></tr><tr><td>minecraft:equippable</td><td><pre>{
  "allowed_entities": "#minecraft:can_equip_harness",
  "asset_id": "minecraft:yellow_harness",
  "equip_on_interact": true,
  "equip_sound": "minecraft:entity.happy_ghast.equip",
  "slot": "body"
}</pre></td><td><pre>{
  "allowed_entities": "#minecraft:can_equip_harness",
  "asset_id": "minecraft:yellow_harness",
  "can_be_sheared": true,
  "equip_on_interact": true,
  "equip_sound": "minecraft:entity.happy_ghast.equip",
  "shearing_sound": "minecraft:entity.happy_ghast.unequip",
  "slot": "body"
}</pre></td></tr></table>
<br/>
</details>
</details>
<hr/>
<details><summary><b><ins>COMMANDS</ins></b><a name="commands"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
+ dialog.txt
```

</details>
</details>
<hr/>
<details><summary><b><ins>RECIPES</ins></b><a name="recipes"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
+ saddle.json
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
+ minecraft:dialog
+ minecraft:dialog_body_type
+ minecraft:dialog_type
+ minecraft:input_control_type
+ minecraft:submit_method_type
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
+ commands.dialog.clear.multiple: Cleared dialog for %s players
+ commands.dialog.clear.single: Cleared dialog for %s
+ commands.dialog.show.multiple: Displayed dialog to %s players
+ commands.dialog.show.single: Displayed dialog to %s
+ item.minecraft.music_disc_tears: Music Disc
+ item.minecraft.music_disc_tears.desc: Amos Roddy - Tears
+ jukebox_song.minecraft.tears: Amos Roddy - Tears
+ mco.connect.region: Server region: %s
+ menu.custom_options: Custom Options...
+ menu.custom_options.title: Custom Options
+ menu.custom_options.tooltip: Note: Custom options are provided by third-party servers and/or content.
Handle with care!
+ menu.custom_screen_info.button_narration: This is a custom screen. Learn more.
+ menu.custom_screen_info.contents: The contents of this screen are controlled by third-party servers and maps that are not owned, operated, or supervised by Mojang Studios or Microsoft.

Handle with care! Always be careful when following links and never give away your pesonal information, including login details.

If this screen prevents you from playing, you can also disconnect from server by using button below.
+ menu.custom_screen_info.disconnect: Custom screen rejected
+ menu.custom_screen_info.title: Note about custom screens
+ menu.custom_screen_info.tooltip: This is a custom screen. Click here to learn more.
+ multiplayer.confirm_command.parse_errors: You are trying to execute an unrecognized or invalid command.
Are you sure?
Command: %s
+ multiplayer.confirm_command.permissions_required: You are trying to execute a command that requires elevated permissions.
This might negatively affect your game.
Are you sure?
Command: %s
+ multiplayer.confirm_command.title: Confirm Command Execution
+ music.game.a_familiar_room: Aaron Cherof - A Familiar Room
+ music.game.an_ordinary_day: Kumi Tanioka - An Ordinary Day
+ music.game.ancestry: Lena Raine - Ancestry
+ music.game.below_and_above: Amos Roddy - Below and Above
+ music.game.broken_clocks: Amos Roddy - Broken Clocks
+ music.game.bromeliad: Aaron Cherof - Bromeliad
+ music.game.clark: C418 - Clark
+ music.game.comforting_memories: Kumi Tanioka - Comforting Memories
+ music.game.creative.aria_math: C418 - Aria Math
+ music.game.creative.biome_fest: C418 - Biome Fest
+ music.game.creative.blind_spots: C418 - Blind Spots
+ music.game.creative.dreiton: C418 - Dreiton
+ music.game.creative.haunt_muskie: C418 - Haunt Muskie
+ music.game.creative.taswell: C418 - Taswell
+ music.game.crescent_dunes: Aaron Cherof - Crescent Dunes
+ music.game.danny: C418 - Danny
+ music.game.deeper: Lena Raine - Deeper
+ music.game.dry_hands: C418 - Dry Hands
+ music.game.echo_in_the_wind: Aaron Cherof - Echo in the Wind
+ music.game.eld_unknown: Lena Raine - Eld Unknown
+ music.game.end.alpha: C418 - Alpha
+ music.game.end.boss: C418 - Boss
+ music.game.end.the_end: C418 - The End
+ music.game.endless: Lena Raine - Endless
+ music.game.featherfall: Aaron Cherof - Featherfall
+ music.game.fireflies: Amos Roddy - Fireflies
+ music.game.floating_dream: Kumi Tanioka - Floating Dream
+ music.game.haggstrom: C418 - Haggstrom
+ music.game.infinite_amethyst: Lena Raine - Infinite Amethyst
+ music.game.key: C418 - Key
+ music.game.komorebi: Kumi Tanioka - komorebi
+ music.game.left_to_bloom: Lena Raine - Left to Bloom
+ music.game.lilypad: Amos Roddy - Lilypad
+ music.game.living_mice: C418 - Living Mice
+ music.game.mice_on_venus: C418 - Mice On Venus
+ music.game.minecraft: C418 - Minecraft
+ music.game.nether.ballad_of_the_cats: C418 - Ballad of the Cats
+ music.game.nether.concrete_halls: C418 - Concrete Halls
+ music.game.nether.crimson_forest.chrysopoeia: Lena Raine - Chrysopoeia
+ music.game.nether.dead_voxel: C418 - Dead Voxel
+ music.game.nether.nether_wastes.rubedo: Lena Raine - Rubedo
+ music.game.nether.soulsand_valley.so_below: Lena Raine - So Below
+ music.game.nether.warmth: C418 - Warmth
+ music.game.one_more_day: Lena Raine - One More Day
+ music.game.os_piano: Amos Roddy - O's Piano
+ music.game.oxygene: C418 - Oxygene
+ music.game.pokopoko: Kumi Tanioka - pokopoko
+ music.game.puzzlebox: Aaron Cherof - Puzzlebox
+ music.game.stand_tall: Lena Raine - Stand Tall
+ music.game.subwoofer_lullaby: C418 - Subwoofer Lullaby
+ music.game.swamp.aerie: Lena Raine - Aerie
+ music.game.swamp.firebugs: Lena Raine - Firebugs
+ music.game.swamp.labyrinthine: Lena Raine - Labryinthine
+ music.game.sweden: C418 - Sweden
+ music.game.watcher: Aaron Cherof - Watcher
+ music.game.water.axolotl: C418 - Axolotl
+ music.game.water.dragon_fish: C418 - Dragon Fish
+ music.game.water.shuniji: C418 - Shuniji
+ music.game.wending: Lena Raine - Wending
+ music.game.wet_hands: C418 - Wet Hands
+ music.game.yakusoku: Kumi Tanioka - yakusoku
+ music.menu.beginning_2: C418 - Beginning 2
+ music.menu.floating_trees: C418 - Floating Trees
+ music.menu.moog_city_2: C418 - Moog City 2
+ music.menu.mutation: C418 - Mutation
+ narration.item: Item: %s
+ options.music_frequency: Music Frequency
+ options.music_frequency.constant: Constant
+ options.music_frequency.default: Default
+ options.music_frequency.frequent: Frequent
+ options.music_frequency.tooltip: Changes how frequently music plays while in a game world.
+ options.showNowPlayingToast: Show Music Toast
+ options.showNowPlayingToast.tooltip: Displays a toast whenever a song starts playing. The same toast is constantly displayed in the in-game pause menu while a song is playing.
```

</details>
</details>
<hr/>
<details><summary><b><ins>PACKETS</ins></b><a name="packets"></a></summary>
<br/>
<details>
<summary>
[client] configuration
</summary>

```diff
+ minecraft:clear_dialog
+ minecraft:show_dialog
```

</details>
<details>
<summary>
[client] play
</summary>

```diff
+ minecraft:clear_dialog
+ minecraft:show_dialog
```

</details>
<details>
<summary>
[server] play
</summary>

```diff
+ minecraft:change_game_mode
+ minecraft:custom_click_action
```

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
+ minecraft/advancement/recipes/combat/saddle.json
+ minecraft/dialog/custom_options.json
+ minecraft/dialog/server_links.json
+ minecraft/jukebox_song/tears.json
+ minecraft/recipe/saddle.json
+ minecraft/tags/dialog/pause_screen_additions.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/items/music_disc_tears.json
+ minecraft/models/item/music_disc_tears.json
+ minecraft/textures/gui/sprites/dialog/warning_button_disabled.png
+ minecraft/textures/gui/sprites/dialog/warning_button_highlighted.png
+ minecraft/textures/gui/sprites/dialog/warning_button.png
+ minecraft/textures/gui/sprites/icon/music_notes.png
+ minecraft/textures/gui/sprites/icon/music_notes.png.mcmeta
+ minecraft/textures/gui/sprites/toast/now_playing.png
+ minecraft/textures/gui/sprites/toast/now_playing.png.mcmeta
+ minecraft/textures/item/music_disc_tears.png
```

</details>
</details>
<hr/>
<details><summary><b><ins>CREDITS</ins></b><a name="credits"></a></summary>
<br/>
<details>
<summary>
🗒️ Sections
</summary>

```diff
- Development Partner - CSI Interfusion Inc
+ Development Partner - Sprung Studios Ltd
+ Development Partner - Sprung Studios Ltd Alumni
```

</details>
<h1>Mojang Studios<a name="credits-mojang-studios"></a></h1>
<h3>Mojang Studios Leadership<a name="credits-mojang-studios-mojang-studios-leadership"></a></h3>
<details>
<summary>
🗒️ Titles
</summary>

```diff
- Franchise Strategic Advisor
- Head of Brand & Entertainment
+ Head of Brand, Growth & Partnerships
+ Head of Franchise Product Strategy
- Head of Games Expansion
- Head of Growth Products & Partnerships
+ Head of People Operations
+ Studio Head
- Studio Head of Mojang Studios
```

</details>
<h3>Design<a name="credits-mojang-studios-design"></a></h3>
<details>
<summary>
🗒️ Titles
</summary>

```diff
+ Creative Director, Entertainment
- Creative Director, Original Content
- Creative Leads
+ Creative Managers
- Design Director
+ Design Directors
+ Narrative Director, Entertainment
- Narrative Editor
- User Experience Design Director
+ User Experience Design Directors
- User Experience Writer
```

</details>
<details>
<summary>
Design Managers
</summary>

```diff
+ Art Usher
- Isak de Jong
+ Jesper Staafjord
- Oskar Hansson Wettergren
- Sherin Kwan
```

</details>
<details>
<summary>
Lead Game Designers
</summary>

```diff
+ Cory Scheviak
+ Daniel Jansson
+ Matthew Gatland
```

</details>
<details>
<summary>
Game Designers
</summary>

```diff
- Art Usher
- Cole Phillips
+ Colton Phillips
- Cory Scheviak
- Daniel Jansson
+ Giuseppe Libonati (Insight Global, Inc)
- Jacob Presley (Insight Global, Inc)
- Jesper Westlund
+ Kyle Wood (Insight Global, Inc)
- Matthew Gatland
```

</details>
<details>
<summary>
User Experience Design Leads
</summary>

```diff
- Carlos Lidón
```

</details>
<details>
<summary>
User Experience Designers
</summary>

```diff
- Clory Luo (Formosa)
+ Jem Alexander
+ Karolin Pettersson
- Rowel Ocampo (Allegis Group Services, Inc)
- Sarah Mack (Digital Intelligence Systems, LLC)
- Shaun Basil Mendonsa
- William Hollowell
```

</details>
<h3>Programming<a name="credits-mojang-studios-programming"></a></h3>
<details>
<summary>
🗒️ Titles
</summary>

```diff
+ Engineering Director
- Engineering Director, Bedrock Platform
+ Engineering Director, Franchise Technologies and Services
- Engineering Directors
+ Engineering Directors, Bedrock Platform
```

</details>
<details>
<summary>
Technical Directors
</summary>

```diff
- Daniel Johansson
- James S Yarrow
+ Stefan Annell
```

</details>
<details>
<summary>
Engineering Managers
</summary>

```diff
- Brian Schwartz
- Elizabeth Carty (Insight Global, Inc)
+ Elvira Melentyeva
+ Henrik Savenstedt
- Jeff McKune
+ Joel Bergman
+ Jonas Jonsson
- Mikael Stenelund
+ Nick Horvath
- Rose Higgins
- Sue Loh
+ Tanya Reinhardt (Ascendion, Inc)
```

</details>
<details>
<summary>
Lead Software Engineers
</summary>

```diff
+ Brian Schwartz
- Dan Posluns
+ Henning Erlandsen
- Joel Bergman
+ Loren Hoffman
+ Max Bouchez
+ River Gillis
- Robert Goins
+ Torbjörn Allard
```

</details>
<details>
<summary>
Technical Leads
</summary>

```diff
+ Dan Mauk
+ Garrett Allen
+ James S Yarrow
+ Jeffrey Kumley
+ Joe Brockhaus
+ Nick Burlingame
- Niclas Unnervik
+ Robert Sanchez
- Stefan Annell
+ Sue Loh
- Torbjörn Allard
```

</details>
<details>
<summary>
Software Engineers
</summary>

```diff
- Aaron Ward (Insight Global, Inc)
+ Abhishek Talati (Ascendion, Inc)
- Adam Granzer (TEKsystems, Inc)
+ Adrian Ferrer (Insight Global, Inc)
- Ajit Belkunde (Ascendion  Inc)
+ Ajit Belkunde (Ascendion, Inc)
+ Alex Schuldberg
+ Ali Yassiry (Netlight)
+ Alvee Akash (Ascendion, Inc)
- Ashish Sharma (Ascendion  Inc)
+ Ashwin Brahmarouthu (Ascendion, Inc)
- Bjarni Gudmundsson
+ Bryan DeNosky
- Bryan DeNosky (Murphy & Associates, Inc)
- Chris Dauchot (Insight Global, Inc)
+ Chris Mhley
+ Chris Sedar
+ Christian Adåker
- Dan Mauk
- David Karlehagen
- Delia Varzariu (Globant)
+ Dmytro Safonov
+ Dominic DaCosta
+ Elisabeth Gangenes
- Elliot Strait (Ascendion, Inc)
- Emily Yellen
+ Emma Villemoes
+ Eric Grimsborn (Netlight)
+ Eric Walston
- Erik Broes
- Esther Peters (Ascendion, Inc)
- Evin Watson (Insight Global, Inc)
- Fernando Cerdeira (Globant)
- Francisco A Garcia Cebada
+ Francisco Alejandro Garcia Cebada
- Gabriel Gerhardsson
- Garrett Allen
- Geof Sawaya (Ascendion, Inc)
+ Guilherme Recchi Cardozo
+ Gunnar Headley
- Gustaf Zetterlund
+ Gustav Taxén
- Håkan Jonson
- Hector Llanos III
+ Hector M Llanos III
+ Hedvig Fahlstedt (Netlight)
- Herbert Mocke (Ascendion, Inc)
+ Huanyu Shao
+ Hugo Hägglund
+ Ian Gaither
- Ian Gaither (Insight Global, Inc)
+ Isaiah Dickison (Insight Global, Inc)
+ Jacob Presley (Insight Global, Inc)
+ Jaime Vargas
+ James Friedenberg (Insight Global, Inc)
- Jason Chionh
- Javi Romero (Globant)
- Jay Sharma (Insight Global, Inc)
- Jeffrey Kumley
- Joe Brockhaus
+ Johan Yngman
- John Graf (Collabera, LLC)
+ John Littlewood (Mirado Consulting)
- John-Philip Johansson
+ Jonas Johansson
- Joseph Kichline
- Juliana Montes
- Khaled Fahmy  (Ascendion, Inc)
- Kiran Beersing-Vasquez
+ Kiran Beersing-Vasquez (Netlight)
+ Kirsten Springer
+ Kyle Schwaneke
+ Markus Winroth
+ Martin Hornqvist
+ Matthew Clohessy
- Matthew Moses (Ascendion, Inc)
- Matthew Phair
- Mattias Selin
+ Max Perea Düring
- Maxime Bouchez
+ Michael Seydl
- Michel Miranda (Globant)
+ Michelle Rosenbarker (Insight Global, Inc)
- Mike Carlson
- Mykhalio Ostapysko (Globant)
- Nat Meo (Ascendion, Inc)
+ Natalie Mueller
- Nick Burlingame
- Nikita Zetilov
- Niklas Ekman
+ Niklas Erhard Olsson
- Nirali Vadera (Ascendion, Inc)
+ Nishith Gadhiya (Ascendion, Inc)
+ Oscar Andersson (Netlight)
- Oskar Pedersen
+ Parth Parikh (Ascendion, Inc)
- Patrick Szafranko (Ascendion, Inc)
- Pavel Grebnev
+ Per Ersson
- Peter Larsson
- Petter Holmberg
- Pouya Ashraf
+ Pouya Ashraf (Netlight)
- Prashant Sharma (Ascendion, Inc)
+ Ragnar Rova
- River Gillis
- Robert Hurley (Ascendion, Inc)
- Robert Sanchez
- Robin Somers
- Rodrick Edwards
- Roger Duke (Insight Global, Inc)
+ Sam Hallam
- Samantha Hallam
- Samuel Smethurst (Ascendion, Inc)
+ Sarmis Streanga (Globant)
- Sarmis-Stefan Streanga (Globant)
- Sean Reilly
+ Soundar B (Ascendion, Inc)
- Stephen Trigger (Insight Global, Inc)
+ Tejas Shah
+ Tobias Bexelius
- Tommy Wallberg
+ Trancy Xiaoying Zhu
- Tushar Patil (Ascendion  Inc)
+ Tushar Patil (Ascendion, Inc)
- Udit Gandhi (Ascendion, Inc)
- Vinay Kumar S B (Ascendion  Inc)
+ Vinay Kumar S B (Ascendion, Inc)
+ Vincent Telleria
+ Vishnu Kumar (Ascendion, Inc)
- Volodymyr Belianinov (Ascendion, Inc)
- Will Van Keulen
- William Harmon (Insight Global, Inc)
+ Yeabsira Mekonnen
+ Zawar Alam (Ascendion, Inc)
- Zeshan Ahmed (Ascendion, Inc)
```

</details>
<h3>Production<a name="credits-mojang-studios-production"></a></h3>
<details>
<summary>
🗒️ Titles
</summary>

```diff
- Director of Ecosystem Experiences
+ Director of Trust and Safety
+ Head of Franchise Technologies and Services
- Localization
+ Organizational Coach
- Organizational Coaches
+ Principal Producers
+ Product Directors, Franchise Technologies and Services
+ Production Managers
```

</details>
<details>
<summary>
Executive Producers
</summary>

```diff
- Chloe Brennan
+ Hai Shi
- Kayla Kinnunen
+ Nikoo Jorjani
```

</details>
<details>
<summary>
Director of Bedrock Platform
</summary>

```diff
+ Dave Cohen
- Michael McManus
```

</details>
<details>
<summary>
Director of Creator
</summary>

```diff
+ Kayla Kinnunen
- Travis Howland
```

</details>
<details>
<summary>
Director of Minecraft Launcher
</summary>

```diff
+ David Marc Siegel
- David Siegel
```

</details>
<details>
<summary>
Director of Minecraft Online & Marketplace
</summary>

```diff
- Jessica Zahn
+ Travis Howland
```

</details>
<details>
<summary>
Production Directors
</summary>

```diff
+ Bryant Hawthorne
- Donald Brinkman
- Jaime Vargas
- Melinda Knight
+ Mike Ammerlaan
- Tyler Jeffers (Formosa)
```

</details>
<details>
<summary>
Production Leads
</summary>

```diff
- Micah Myerscough
- Sarah Carton
```

</details>
<details>
<summary>
Producers
</summary>

```diff
+ Aaron Hughes (Insight Global, Inc)
- Allan Contreras (Insight Global, Inc)
- Anna Lundgren
- Annica Strand
- Aqsa Rauf (Apex Systems, Inc)
+ Barrett Livingston
- Carolin Szymaniak
- Charlotte Angantyr
+ Dawn Boughton (Apex Systems, Inc)
- Dejan Dimic
- Eliot Lee
+ Ellen Karlsten
- Emily Steele (Formosa)
+ Eric Karlshammar
+ Gareth Young
- Grace Jung-Stanley (Allegis Group Services, Inc)
+ Heesung Koo
- Hillary Good (Aquent, LLC)
+ Hillary Good (Simplicity Consulting Inc.)
- Isaac Barron (Globant)
+ Jennifer Boespflug Dotson (Insight Global, Inc)
- Jennifer Dotson (Insight Global, Inc)
- Josefine Brink
+ Kev Katona (Insight Global, Inc)
- Luis Qiang Liu
- Marc Watson
+ Marie Bustgaard
- Marie Bustgaard Granlund
- Megan Rodes (Formosa)
- Natalie Selin
- Nikoo Jorjani
+ Rakiv Joy
+ Sarah Von Reis
- Seyit Ivhed
+ Sofia Gothlin
- Steph Huske (TEKsystems, Inc)
- Tess Kearney (Formosa)
- Tina Lin (Ascendion, Inc)
```

</details>
<details>
<summary>
Media Producers
</summary>

```diff
- André Angerbjörn
+ Andreas Dea Svensson
- Ines Quintanar Cardenas
+ Johan Björnung Kvarnemo
- Johan Kvarnemo
+ Sandra Schöön
```

</details>
<details>
<summary>
Product Manager Leads
</summary>

```diff
+ Anna Lundgren
- Carlos Figueiredo
+ Divya Babuji
- Nick Horvath
```

</details>
<details>
<summary>
Product Managers
</summary>

```diff
+ Ahmed Asif
- Andrea Lam-Flannery
+ August Carow
+ Carolina Broberg (Netlight)
+ Dejan Dimic
+ Eliot Lee
- Erica Lares (Apex Systems, Inc)
+ Grace Jung (Allegis Group Services, Inc)
+ Kara Kono
+ Katie Ellison
+ Malte Tammerström
+ Marc Watson
+ Micah Myerscough
- Mike Ammerlaan
+ Nick Ljungqvist (MVP Global AB)
+ Rachel Ji
- Stephen A Scott
+ Stephen Scott
- Su Liu
+ Tia Dalupan
+ Tori Tippin
+ Zerelina Mukherjee
```

</details>
<details>
<summary>
Release Managers
</summary>

```diff
+ Kristian Björk Grimberg
```

</details>
<details>
<summary>
Technical Writers
</summary>

```diff
+ Jeff Kim (Insight Global, Inc)
- Jim Seaman (Insight Global, Inc)
```

</details>
<details>
<summary>
Technical Program Managers
</summary>

```diff
+ Andrea Lam-Flannery
+ Aqsa Rauf (Apex Systems, Inc)
- Aysha Davis (Cyborg Mobile LLC)
+ Benjamin Fall
- Beth Carty (Insight Global, Inc)
+ Bobby Ou (my3Twelve, LLC)
- Brynn Medelsohn (Insight Global, Inc)
+ Brynn Mendelsohn (Insight Global, Inc)
+ Chloe Li (my3Twelve, LLC)
+ David Jho (my3Twelve, LLC)
- Devarshi Hazarika
- DJ Stiner
- Dom Arcamone
+ Dylan Kesselring
- Dylan Kesselring (Insight Global, Inc)
+ Elizabeth Carty (Insight Global, Inc)
- Eloise Espel
- Erfon Haubenstock
+ Garbo Chan (my3Twelve, LLC)
- Hai Shi
- Heesung Koo
- Henning Erlandsen
- James Friedenberg (Insight Global, Inc)
+ Jered Dowden (Ascendion, Inc)
- Joshua Mueller (Apex Systems, Inc)
- Kara Kono
- Katie Ellison
+ Mabel Chan (my3Twelve, LLC)
- Quinn Richter
- Rachel Ji
- Stephen Frothingham (Wimmer Solutions)
- Tia Dalupan
+ Timothy Mehta (Aquent, LLC)
+ Tina Lin (Ascendion, Inc)
- Tori Tippin
```

</details>
<details>
<summary>
Playtest Coordinator
</summary>

```diff
- Axel Savage
+ Jonathan Carroll (Insight Global, Inc)
```

</details>
<h3>Visual Arts<a name="credits-mojang-studios-visual-arts"></a></h3>
<details>
<summary>
🗒️ Titles
</summary>

```diff
+ Art Manager
- Creative Manager
- Technical Artist
+ Technical Artists
```

</details>
<details>
<summary>
Creative Leads
</summary>

```diff
- Antti Meriluoto
```

</details>
<details>
<summary>
Art Directors
</summary>

```diff
- Lynwood Montgomery (Formosa)
+ Sherin Kwan
- Telemachus Stavropoulos
+ Ullis Linder
- Viktor Blanke
```

</details>
<details>
<summary>
Artist Leads
</summary>

```diff
+ Meagan Dumford
+ Michael Neumann
- Michael Ray Neumann
```

</details>
<details>
<summary>
Artists
</summary>

```diff
- Aleesa Tana (Formosa)
+ Amelie Bjurenhed
- Andrea Sanchez Sepulveda (Formosa)
- Brendan 'Sully' Sullivan
+ Celene Presto (Harvey Nash, Inc)
- Celene Tolentino (Harvey Nash, Inc)
+ Chase Farthing (Allegis Group Services, Inc)
+ Christina Dolan (Aquent, LLC)
- Claire Selvog (Formosa)
- Erin Biafore (Formosa)
- Florian Decupper
- Jei Ling (Formosa)
- Kailey Hara (Formosa)
- Kate Anderson (Formosa)
- Linus Chan (Formosa)
+ Margarita Sanchez (Allegis Group Services, Inc)
- Mariana Salimena
- Mark Eash Hershberger (Formosa)
- Mark Reyes (Formosa)
+ Noam Briner
- Patrick Rodes (Formosa)
+ Rodrigo Corvalan Vivedes
- Rudy Solidarios (Formosa)
- Salinee Goldenberg (Formosa)
- Sarah Corean (Formosa)
- Sarah Martino (Formosa)
+ Scott Jobe (Allegis Group Services, Inc)
- William Thomas
```

</details>
<details>
<summary>
Product Designers
</summary>

```diff
- Affe Piran
- Kelsey Ranallo
- Lisa Dahlström
+ Ro Ocampo (Allegis Group Services, Inc)
+ Timothy Lusk (Allegis Group Services, Inc)
```

</details>
<details>
<summary>
Graphic Designers
</summary>

```diff
- Adrian Leon (Formosa)
- Dalila Copeland (Formosa)
+ Isak de Jong
- Javier Rodriguez (Formosa)
- Meagan Dumford
```

</details>
<h3>Audio<a name="credits-mojang-studios-audio"></a></h3>
<details>
<summary>
🗒️ Titles
</summary>

```diff
+ Music Supervisors
```

</details>
<details>
<summary>
Sound Designers
</summary>

```diff
- Magnus Mikander
+ Sandra Karlsson
```

</details>
<h3>Quality Assessment<a name="credits-mojang-studios-quality-assessment"></a></h3>
<details>
<summary>
🗒️ Titles
</summary>

```diff
- Quality Analysts
+ Quality Director, Franchise Technologies and Services
+ Test Director
- Test Directors
```

</details>
<details>
<summary>
Quality Engineers
</summary>

```diff
+ Alyssa Liu
+ Dalrek Davis
+ Michelle Hyde
+ Tom French
```

</details>
<details>
<summary>
Quality Assessment Specialists
</summary>

```diff
- Kristian Björk Grimberg
```

</details>
<details>
<summary>
Program Managers
</summary>

```diff
+ Onur Unaldi
```

</details>
<details>
<summary>
Test Managers
</summary>

```diff
- Benjamin Sousa (Experis)
+ Emily Lovering (Experis)
- Ian S. Nelson (Experis)
- Łukasz Mikusek (Lionbridge)
+ Raasahn Browder (Experis)
```

</details>
<details>
<summary>
Team Leads
</summary>

```diff
+ Iwona Cieśla (Lionbridge)
- Kamil Kostrzewa (Lionbridge)
+ Paulina Pałdyna (Lionbridge)
+ Witold Matejewski (Lionbridge)
- Zuzanna Gieszcz (Lionbridge)
```

</details>
<details>
<summary>
Test Leads
</summary>

```diff
- Alan Aclon (Insight Global, Inc)
+ Benjamin Sousa (Experis)
```

</details>
<details>
<summary>
Test Automation Engineers
</summary>

```diff
+ Marcin Cudny (Lionbridge)
```

</details>
<details>
<summary>
Software Test Engineers
</summary>

```diff
+ Albert Wujkowski (Lionbridge)
+ Alex Vue (Experis)
+ Amelia Rozborska (Lionbridge)
+ Bartłomiej Krupiński (Lionbridge)
+ Bartosz Kacprzak (Lionbridge)
- Chris Youngs (Insight Global, Inc)
+ Damian Galicki (Lionbridge)
+ Daniel Posiadała (Lionbridge)
+ Gabriel Mróz (Lionbridge)
- Iwona Cieśla (Lionbridge)
+ Jakub Budzyński (Lionbridge)
- Jared Lesczynski (Experis)
- Kinga Izdebska (Lionbridge)
- Konrad Czaplewski (Lionbridge)
- Marcin Morel (Lionbridge)
- Mateusz Janiszewski (Lionbridge)
- Michał Tomaszewski (Lionbridge)
+ Mikaela Reed (Experis)
+ Mikołaj Gruźliński (Lionbridge)
- Paulina Pałdyna (Lionbridge)
- Robert Alvarez (Experis)
- Tevis Campbell (Experis)
+ Weronika Szajnfeld (Lionbridge)
- Witold Matejewski (Lionbridge)
```

</details>
<details>
<summary>
Test Associates
</summary>

```diff
- Albert Wujkowski (Lionbridge)
+ Aleksander Sierocinski (Lionbridge)
+ Aleksander Zygier (Lionbridge)
+ Alex Nissen (Insight Global, Inc)
- Amelia Rozborska (Lionbridge)
+ Aneta Woźnica (Lionbridge)
+ Antoni Kostrzewa (Lionbridge)
+ Arkadiusz Czarnecki (Lionbridge)
- Arkadiusz Grzanka (Lionbridge)
- Bartłomiej Krupiński (Lionbridge)
+ Bartłomiej Truszkowski (Lionbridge)
+ Bartlomiej Wysocki
- Bartosz Kacprzak (Lionbridge)
+ Bartosz Paciorkiewicz (Lionbridge)
+ Bartosz Staszczak (Lionbridge)
+ Casper Sparks (Insight Global, Inc)
- Damian Bartak (Lionbridge)
- Damian Galicki (Lionbridge)
+ Damian Rokosz (Lionbridge)
- Daniel Posiadała (Lionbridge)
+ Dawid Gryczan (Lionbridge)
+ Emir Ali Misiratov (Lionbridge)
- Evan Armstrong (Experis)
- Gabriel Mróz (Lionbridge)
+ Hayden Dalton (Lionbridge)
- Heorhii Lystopad (Lionbridge)
- Ignacy Kukliński (Lionbridge)
+ Igor Grabski (Lionbridge)
+ Igor Niewiadomski (Lionbridge)
+ Jakub Byliniak (Lionbridge)
- Jakub Kliś (Lionbridge)
+ Jakub Łuckiewicz (Lionbridge)
+ Jakub Piekart (Lionbridge)
+ Jakub Puzio (Lionbridge)
+ Jakub Sierociński (Lionbridge)
+ Jakub Tabiszewski (Lionbridge)
+ Jakub Zgajewski (Lionbridge)
+ Jan Górski (Lionbridge)
+ Jarosław Gasiński (Lionbridge)
+ Jessica Stephenson (Lionbridge)
- John Castro Chico
+ Julia Jóźwiak (Lionbridge)
+ Kacper Bujakowski (Lionbridge)
- Kacper Lędzion (Lionbridge)
+ Kacper Paś (Lionbridge)
- Kacper Pućka (Lionbridge)
- Kacper Stalewski (Lionbridge)
- Kamil Wiktorowski (Lionbridge)
+ Karol Kopeć (Lionbridge)
- Karol Mikusek (Lionbridge)
+ Karolina Pietraś (Lionbridge)
+ Karolina Zaleszczyk (Lionbridge)
+ Khaya Mvimbi (Lionbridge)
+ Kyrylo Kunytskyi (Lionbridge)
+ Łukasz Majchrowski (Lionbridge)
+ Maciej Bielecki (Lionbridge)
+ Maciej Michaluk (Lionbridge)
+ Maciej Pieszalski (Lionbridge)
+ Maciej Ruciński (Lionbridge)
+ Maciej Wójcik (Lionbridge)
+ Malichi Wilson (Lionbridge)
- Marcin Cudny (Lionbridge)
+ Marcin Słoniewski (Lionbridge)
+ Mateusz Borowski (Lionbridge)
+ Mateusz Iwaniuk (Lionbridge)
- Mikołaj Gruźliński (Lionbridge)
- Mikołaj Szadkowski (Lionbridge)
+ Milena Olesiejuk (Lionbridge)
+ Natalia Walczyńska (Lionbridge)
- Nicholas Latino
+ Odo Przęczka (Lionbridge)
+ Patrycja Dwojak (Lionbridge)
+ Piotr Kruszewicz (Lionbridge)
+ Piotr Mudryk (Lionbridge)
+ Platon Ogarev (Lionbridge)
- Rafał Gołębiewski (Lionbridge)
+ Rafał Gołębiowski (Lionbridge)
- Rion Cox (Lionbridge)
- Rob Thomas
+ Sabina Ocaya Gamon (Lionbridge)
+ Samanta Giedraityte (Lionbridge)
+ Samantha Glass (Insight Global, Inc)
- Sophie James (Lionbridge)
+ Tomasz Kubajka (Lionbridge)
- Weronika Szajnfeld (Lionbridge)
+ Wiktor Wrona (Lionbridge)
+ Wiktoria Błaszkiewicz (Lionbridge)
+ Wiktoria Brodzik (Lionbridge)
+ Wiktoria Hałatkiewicz (Lionbridge)
+ Wyat Simmons (Lionbridge)
+ Zuzanna Krężlewicz (Lionbridge)
```

</details>
<h3>Operations<a name="credits-mojang-studios-operations"></a></h3>
<details>
<summary>
🗒️ Titles
</summary>

```diff
- Automation Support
+ DevOps Engineer
- Office Manager
+ Operations Director
+ Operations Director, Global
- Operations Directors, Global
- Operations Manager, Global
- Player Operations Director
```

</details>
<details>
<summary>
Operations Managers
</summary>

```diff
+ Sheila Ho
```

</details>
<details>
<summary>
People Operations Managers
</summary>

```diff
+ Aleksandra Ola Zajac
+ Joël Älveroth
- Mira Aboulhoson
```

</details>
<details>
<summary>
Human Resources
</summary>

```diff
- Aleksandra Ola Zajac
- Alexandra Ward
- Jonas Bergelli
- Katarina Starendal
+ Line Thomson
- Marie Tolf
- Milica Tesic Stojanovic
- Richard Nelleus
- Sheila Ho
- Ulrika Wörding
+ Yvonne Zarrin Manesh
```

</details>
<details>
<summary>
Talent Acquisition
</summary>

```diff
+ Adam Conder (Insight Global, Inc)
- Elnaz Tajahmadi Tabrizi
- Eman Lakhani (Insight Global, Inc)
+ Sofia Andersson
```

</details>
<details>
<summary>
Executive Business Administrators
</summary>

```diff
+ Dinah Divinagracia
+ Francine Jordan
- Francine Jordan (Simplicity Consulting Inc)
```

</details>
<details>
<summary>
IT Managers
</summary>

```diff
- Adam MacDowall
```

</details>
<details>
<summary>
IT
</summary>

```diff
+ Aaron Brindell (Experis)
+ Aaron Ingram (Experis)
+ Adam Barnette (Experis)
- Anton Wu
+ Brian Hein (Experis)
- Cesar Sima Falck
- Dacke Blixt
+ Dacke Blixt (Techfactory, AB)
+ Eric Filarski (My3Twelve, LLC)
+ Hannah Feilberg-Maiti (Techfactory, AB)
+ Matthew Cha (my3Twelve, LLC)
- Morris Kellokoski
+ Tim Foster (my3Twelve, LLC)
- Zelda Karttunen
+ Zelda Karttunen (Academic Work IT AB)
```

</details>
<h3>Player Care<a name="credits-mojang-studios-player-care"></a></h3>
<details>
<summary>
🗒️ Titles
</summary>

```diff
+ Player Support Operations Manager
```

</details>
<details>
<summary>
Player Support Program Leads
</summary>

```diff
+ Alexandru Giuglea
+ Erfon Haubenstock
```

</details>
<details>
<summary>
Player Support
</summary>

```diff
+ Angel De Aguiar (Apex Systems, Inc)
+ Arturo Gutierrez (Apex Systems, Inc)
+ Briana Acosta (Apex Systems, Inc)
+ Caleb Masters (Apex Systems, Inc)
+ Chirs Lok (Apex Systems, Inc)
+ Chris Eells (Apex Systems, Inc)
- Dan Coronel (Apex Systems, Inc)
+ Daniel Coronel (Apex Systems, Inc)
+ Gabriel Gonzales (Apex Systems, Inc)
+ Julia Osobampo (Apex Systems, Inc)
- Justin Putnam (Apex Systems, Inc)
+ Karoline Malik (Apex Systems, Inc)
+ Mara Croesy (Apex Systems, Inc)
+ Melinda Morales (Apex Systems, Inc)
+ Mey Saechao (Apex Systems, Inc)
+ Raul Garza (Apex Systems, Inc)
+ Sarah Wylie (Apex Systems, Inc)
+ Whitney Okafor (Apex Systems, Inc)
```

</details>
<h3>Data Analytics<a name="credits-mojang-studios-data-analytics"></a></h3>
<details>
<summary>
🗒️ Titles
</summary>

```diff
+ Data and Analytics Lead
- Data Science and Analytics Manager
+ Data Science and Analytics Managers
```

</details>
<details>
<summary>
Analytics Environment Engineering
</summary>

```diff
+ Lucas Neubert (Ascendion, Inc)
+ Ryan Cox (Ascendion, Inc)
- Saif Adeeb (Ascendion, Inc)
+ Whitney King (Fractal Analytics Inc)
```

</details>
<details>
<summary>
Data Science
</summary>

```diff
+ Axel Orrenius
- Erin Michet
- Jonathan Bush (KellyMitchell Group, LLC)
- Julianne Toto (Kelly Management Services, Inc)
+ Kent Go (Aquent, LLC)
+ Kyle Iman
- Matilda Eriksson
+ Matilda Tamm
- Max Davidson
- Miguel Fierro
+ Pujeethaa Jakka
- Pujeethaa Jakka (Apex Systems, Inc)
- Ricardo Silva Oquendo (KellyMitchell Group, LLC)
+ Siva Balantrapu (Hitachi Digital Services LLC)
+ Tiana Ramirez (KellyMitchell Group, LLC)
+ Usama Bin Salim (Agility Partners  LLC)
+ Victor Fong (Ascendion, Inc)
```

</details>
<details>
<summary>
Data Engineering
</summary>

```diff
- Smitha Menon
```

</details>
<h3>Business Management & Licensing<a name="credits-mojang-studios-business-management-&-licensing"></a></h3>
<details>
<summary>
🗒️ Titles
</summary>

```diff
+ Business Development Manager Leads
- Business Director, Operations
+ Business Directors, Operations
+ Program Director, Franchise Development
+ Program Manager Lead
- Strategy Director
+ Technical Program Managers
```

</details>
<details>
<summary>
Program Director, Consumer Products
</summary>

```diff
- Federico San Martin
+ Hanna Willis
```

</details>
<details>
<summary>
Program Directors
</summary>

```diff
+ Sonal Majmudar
```

</details>
<details>
<summary>
Business Directors
</summary>

```diff
- Hanna Willis
+ Tim Gould
```

</details>
<details>
<summary>
Business Development Managers
</summary>

```diff
+ Albert Pastore
+ Amy Barenblat (Iconma LLC)
- Inga Chamberlain
- Maru Zamora
+ MaryKate Mullen (Allegis Global Services, Inc)
- Nick Gallagher (Digital Intelligence Systems, LLC)
- Rebecca A Miller
+ Roger Villegas (Allegis Global Services, Inc)
- Ryan Eng (Aerotek, Inc)
+ Timothy Norton (Ascendion, Inc)
```

</details>
<details>
<summary>
Program Managers
</summary>

```diff
- Aaron Hughes (Insight Global, Inc)
- Adam Conder (Insight Global, Inc)
+ Alex Luschen
+ Anita Collins (Excelsior Staffing LLC)
- Aria Azizi
+ Bethany Gager (Apex Systems, Inc)
- Bobby Ou (my3Twelve, LLC)
+ Chris Dauchot (Insight Global, Inc)
- David Jho (my3Twelve, LLC)
- Felix Huang Jr. (Insight Global, Inc)
- Garbo Chan (my3Twelve, LLC)
- Julie Olden
- Mabel Chan (my3Twelve, LLC)
- Stuart U (my3Twelve, LLC)
+ Susan Morales (Apex Systems, Inc)
- Susie Tinker
```

</details>
<details>
<summary>
Business Managers
</summary>

```diff
+ Brandon H Kim
- Brandon H Kim (Insight Global, Inc)
- Dana Friesen (Insight Global, Inc)
- David K Lau
+ David K. Lau
- Fredrika Wessman
+ Janet Cunningham
- Janet Cunningham (Harvey Nash, Inc)
+ Lori Merritt (SGF USA LLC)
- Sarah Souza (Epitec Inc)
- Stephanie Turl (JeffreyM Consulting, LLC)
+ Stephanie Turl (Simplicity Consulting Inc.)
```

</details>
<h3>Brand Management<a name="credits-mojang-studios-brand-management"></a></h3>
<details>
<summary>
🗒️ Titles
</summary>

```diff
+ Brand Analyst
+ Brand Strategist
```

</details>
<h3>Communications<a name="credits-mojang-studios-communications"></a></h3>
<details>
<summary>
🗒️ Titles
</summary>

```diff
- Chief Storyteller
- Content Manager
+ Content Managers
+ Publishing Editor
- Publishing Editors
```

</details>
<details>
<summary>
Communications Managers
</summary>

```diff
+ Cristina Anderca
+ Cynthia Park (Assembly Media, Inc)
- Hollis Wacker-Leja
- Katie Guo (Assembly Media, Inc)
- Zulai Serrano
+ Zulai Serrano Shimamoto
```

</details>
<details>
<summary>
Creative Writers
</summary>

```diff
- Cristina Anderca
+ Julius Olofsson
+ Linn Viberg
- Linn Wiberg
```

</details>
<details>
<summary>
Social Media Managers
</summary>

```diff
+ Angelica Batth (Kforce, Inc)
+ Cassandra Jones (Cypress Human Capital)
- Chad Oetken (Troy Consulting LLC)
- Matt Pearsall (Aston Carter, Inc)
- Sarah Beecroft (JeffreyM Consulting, LLC)
- Will Chang (Randstad)
+ Will Mowery (Harvey Nash, Inc)
+ William Chang (Randstad)
```

</details>
<details>
<summary>
Community Managers
</summary>

```diff
- DèJa Easter (Apex Systems, Inc)
+ Emily Hayes (Averro LLC)
- Nadine Ebri (Apex Systems, Inc)
+ Sophia Lyon
```

</details>
<h3>Marketing<a name="credits-mojang-studios-marketing"></a></h3>
<details>
<summary>
🗒️ Titles
</summary>

```diff
+ Marketing Content Managers
```

</details>
<details>
<summary>
Head of Marketing
</summary>

```diff
+ Jeanie DuMont
- Jessica Freeman
```

</details>
<details>
<summary>
Marketing Directors
</summary>

```diff
+ Gaylord Escalona
- Jeanie DuMont
```

</details>
<details>
<summary>
Marketing Managers
</summary>

```diff
+ Amanda Correia
+ Amy Vuong (Cypress Human Capital)
- Barrett Livingston (Apex Systems, Inc)
- Cori Anne Montero
+ Emily Orrson (Unfollow Media)
- Gaylord Escalona
- Janis Fein (Ascendion Inc)
+ Janis Fein (Ascendion, Inc)
+ Makayla Mota (Harvey Nash, Inc)
+ Nicolas Sherman (Nextant LLC)
+ Sam Brody
- Sam Brody (Ten Gun Design, Inc)
+ Shari Gari (Aquent, LLC)
+ Terry Lewis (Ten Gun Design, Inc)
```

</details>
<details>
<summary>
Web Content Authors & QA
</summary>

```diff
+ Arvapally Bharath (HCL Technologies)
- Deepak Bahadoor (HCL Technologies)
+ Jack Markley (HCL Technologies)
```

</details>
<h3>Finance<a name="credits-mojang-studios-finance"></a></h3>
<details>
<summary>
🗒️ Titles
</summary>

```diff
+ Financial Accountant
- Financial Accountants
- Financial Consultant
+ Financial Consultants
```

</details>
<details>
<summary>
Finance Managers
</summary>

```diff
+ Felix Huang Jr.
+ Mikkel Flækøy
```

</details>
<h1>Development Partner - Blackbird Interactive<a name="credits-development-partner---blackbird-interactive"></a></h1>
<h3>Main<a name="credits-development-partner---blackbird-interactive-main"></a></h3>
<details>
<summary>
🗒️ Titles
</summary>

```diff
+ Producer
- Producers
- Quality Assurance Analysts
- Quality Assurance Director
+ Studio Technical Director
- Technical Director
- UI Artist
- UX Designer
+ Vice President, Development
- Vice President, Stategic Projects
```

</details>
<details>
<summary>
Programmers
</summary>

```diff
- Aaron Freytag
- Ben Jones
- Curtis Hodgins
- Darren Grant
- Dylan Reviczky
- Jacky Cai
- Jakob Trounce
+ Jc Fowles
+ Sabrina Korsch-Sharma
- Zehao Lu
```

</details>
<h1>Development Partner - Disbelief<a name="credits-development-partner---disbelief"></a></h1>
<h3>Main<a name="credits-development-partner---disbelief-main"></a></h3>
<details>
<summary>
🗒️ Titles
</summary>

```diff
+ Art Director
- Senior Programmer
+ Senior Programmers
+ Senior Technical Artist
+ Technical Artist
```

</details>
<details>
<summary>
Programmers
</summary>

```diff
+ Abhijit Zala
- Caden Parker
+ Hugo Machado
```

</details>
<h1>Mojang Studios Alumni<a name="credits-mojang-studios-alumni"></a></h1>
<h3>Main<a name="credits-mojang-studios-alumni-main"></a></h3>
<details>
<summary>
🗒️ Titles
</summary>

```diff
+ Administrative Support
+ Chief Storyteller
- Creative Lead
+ Creative Leads
+ Director of Bedrock Platform
+ Director of Minecraft Online & Marketplace
- Financial Consultant
+ Financial Consultants
- Graphic Designer
+ Graphic Designers
+ Head of Games Expansion
+ Head of Marketing
+ IT Managers
+ Localization
+ Media Producers
+ People Operations Director
- Product Manager
+ Product Managers
- Production Director
+ Production Directors
- Production Manager
+ Production Managers
+ Publishing Editor
+ Software Test Engineers
+ Studio Head
- Studio Head of Mojang Studios
+ Team Leads
+ Test Associates
+ Test Lead
+ Test Managers
+ User Experience Writer
```

</details>
<details>
<summary>
Chief of Staff
</summary>

```diff
+ Yassal Sundman
```

</details>
<details>
<summary>
Design Managers
</summary>

```diff
+ Oskar Hansson Wettergren
```

</details>
<details>
<summary>
Game Designers
</summary>

```diff
+ Jesper Westlund
```

</details>
<details>
<summary>
Technical Directors
</summary>

```diff
+ Daniel Johansson
```

</details>
<details>
<summary>
Engineering Managers
</summary>

```diff
+ Mikael Stenelund
+ Rose Higgins
```

</details>
<details>
<summary>
Lead Software Engineers
</summary>

```diff
+ Dan Posluns
+ Robert Goins
```

</details>
<details>
<summary>
Technical Leads
</summary>

```diff
+ Niclas Unnervik
```

</details>
<details>
<summary>
Software Engineers
</summary>

```diff
+ Aaron Ward (Insight Global, Inc)
+ Adam Granzer (TEKsystems, Inc)
+ Alex Baird (Collabera, LLC)
- Alex Baird (Collabera, LLC) (Software Development)
+ Ali Alidoust
+ Ashish Sharma (Ascendion Inc)
+ Bjarni Gudmundsson
+ David Karlehagen
+ Delia Varzariu (Globant)
+ Elliot Strait (Ascendion, Inc)
+ Emily Yellen
+ Erik Broes
+ Esther Peters (Ascendion, Inc)
+ Evin Watson (Insight Global, Inc)
+ Fernando Cerdeira (Globant)
+ Gabriel Gerhardsson
+ Gabriel Gessle
+ Geof Sawaya (Ascendion, Inc)
+ Gustaf Zetterlund
+ Håkan Jonson
+ Helena Hjertén
+ Herbert Mocke (Ascendion, Inc)
+ Jason Chionh
+ Javi Romero (Globant)
+ Jay Sharma (Insight Global, Inc)
+ John Graf (Collabera, LLC)
+ John-Philip Johansson
+ Joseph Kichline
+ Juliana Montes
+ Khaled Fahmy (Ascendion, Inc)
+ Matthew Moses (Ascendion, Inc)
+ Matthew Phair
+ Mattias Selin
+ Michel Miranda (Globant)
+ Mikael Persson
+ Mike Carlson
+ Mykhalio Ostapysko (Globant)
+ Nat Meo (Ascendion, Inc)
+ Nikita Zetilov
+ Niklas Ekman
+ Oskar Pedersen
+ Patrick Szafranko (Ascendion, Inc)
+ Pavel Grebnev
+ Peter Larsson
+ Petter Holmberg
+ Prashant Sharma (Ascendion, Inc)
+ Robert Hurley (Ascendion, Inc)
+ Robin Somers
+ Rodrick Edwards
+ Samuel Smethurst (Ascendion, Inc)
+ Sean Reilly
+ Stephen Trigger (Insight Global, Inc)
- Sumith Kumar (Virtuosity)
+ Tommy Wallberg
+ Udit Gandhi (Ascendion, Inc)
- Uma Senthil Raj (Virtuosity)
- Vignesh Masilamani (Virtuosity)
+ Volodymyr Belianinov (Ascendion, Inc)
+ Will Van Keulen
+ William Harmon (Insight Global, Inc)
+ Zeshan Ahmed (Ascendion, Inc)
```

</details>
<details>
<summary>
Architects
</summary>

```diff
- Michael Seydl
```

</details>
<details>
<summary>
Production Leads
</summary>

```diff
+ Sarah Carton
```

</details>
<details>
<summary>
Producers
</summary>

```diff
+ Allan Contreras (Insight Global, Inc)
+ Annica Strand
+ Carolin Szymaniak
+ Charlotte Angantyr
- Ellen Karlsten
+ Emily Steele (Formosa)
+ Isaac Barron (Globant)
+ Josefine Brink
+ Luis Qiang Liu
+ Megan Rodes (Formosa)
+ Natalie Selin
+ Seyit Ivhed
+ Steph Huske (Allegis Group Services, Inc)
+ Susanne Granlöf
+ Tess Kearney (Formosa)
```

</details>
<details>
<summary>
Organizational Coaches
</summary>

```diff
+ Rasmus Noah Hansen
```

</details>
<details>
<summary>
Technical Writers
</summary>

```diff
- Jeff Kim (Insight Global, Inc)
+ Jim Seaman (Insight Global, Inc)
```

</details>
<details>
<summary>
Technical Program Managers
</summary>

```diff
+ Aysha Davis (Cyborg Mobile LLC)
+ Devarshi Hazarika
+ Dom Arcamone
+ Eloise Espel
+ Joshua Mueller (Apex Systems, Inc)
+ Roger Duke (Insight Global, Inc)
+ Stephen Frothingham (Wimmer Solutions)
```

</details>
<details>
<summary>
Playtest Coordinators
</summary>

```diff
+ Axel Savage
```

</details>
<details>
<summary>
Art Directors
</summary>

```diff
+ Lynwood Montgomery (Formosa)
+ Telemachus Stavropoulos
+ Viktor Blanke
```

</details>
<details>
<summary>
Artists
</summary>

```diff
+ Aleesa Tana (Formosa)
+ Andrea Sanchez Sepulveda (Formosa)
+ Claire Selvog (Formosa)
+ Erin Biafore (Formosa)
+ Florian Decupper
+ Jei Ling (Formosa)
+ Kailey Hara (Formosa)
+ Kate Anderson (Formosa)
+ Linus Chan (Formosa)
- Linus Chan (TEKsystems, Inc.)
+ Mariana Salimena
+ Mark Eash Hershberger (Formosa)
+ Mark Reyes (Formosa)
+ Patrick Rodes (Formosa)
+ Rudy Solidarios (Formosa)
+ Salinee Goldenberg (Formosa)
+ Sarah Corean (Formosa)
+ Sarah Martino (Formosa)
+ William Thomas
```

</details>
<details>
<summary>
Product Designers
</summary>

```diff
+ Affe Piran
+ Kelsey Ranallo
+ Lisa Dahlström
```

</details>
<details>
<summary>
Sound Designers
</summary>

```diff
+ Magnus Mikander
```

</details>
<details>
<summary>
User Experience Designers
</summary>

```diff
+ Clory Luo (Formosa)
+ Nirali Vadera (Ascendion, Inc)
+ Sarah Mack (Digital Intelligence Systems, LLC)
+ Shaun Basil Mendonsa
- Timothy Lusk (Randstad)
+ William Hollowell
```

</details>
<details>
<summary>
Operations Managers
</summary>

```diff
+ Ellen Hahm
+ Mira Aboulhoson
```

</details>
<details>
<summary>
Business Development Managers
</summary>

```diff
+ Maru Zamora
+ Nick Gallagher (Digital Intelligence Systems, LLC)
+ Ryan Eng (Aerotek, Inc)
```

</details>
<details>
<summary>
Program Managers
</summary>

```diff
+ Amador Abreu (Insight Global, Inc)
+ Aria Azizi
+ Brian Canning (Experis)
+ Julie Olden
+ Stuart U (my3Twelve, LLC)
```

</details>
<details>
<summary>
Business Managers
</summary>

```diff
+ Dana Friesen (Insight Global, Inc)
+ Sarah Souza (Epitec Inc)
```

</details>
<details>
<summary>
Human Resources
</summary>

```diff
+ Alexandra Ward
+ Jennie Sjöman
+ Jonas Bergelli
+ Katarina Starendal
+ Marie Tolf
+ Milica Tesic Stojanovic
+ Richard Nelléus
+ Ulrika Wörding
```

</details>
<details>
<summary>
Talent Acquisition
</summary>

```diff
+ Elnaz Tajahmadi Tabrizi
- Sofia Andersson
```

</details>
<details>
<summary>
IT
</summary>

```diff
+ Anton Wu
+ Cesar Sima Falck
+ Derek Wilson (my3Twelve, LLC)
+ Morris Kellokoski
- Tim Foster (Warner Marketing, Inc)
```

</details>
<details>
<summary>
Automation Support
</summary>

```diff
+ Bill Erhard (Insight Global, Inc)
- Jordan Crockett (TEKsystems, Inc.)
```

</details>
<details>
<summary>
Analytics Environment Engineering
</summary>

```diff
+ Saif Adeeb (Ascendion, Inc)
```

</details>
<details>
<summary>
Data Science
</summary>

```diff
+ Erin Michet
+ Jonathan Bush (KellyMitchell Group, LLC)
+ Julianne Toto (Kelly Management Services, Inc)
+ Matilda Eriksson
+ Max Davidson
+ Ricardo Silva Oquendo (KellyMitchell Group, LLC)
```

</details>
<details>
<summary>
Player Support
</summary>

```diff
+ Dan Coronel (Apex Systems, Inc)
```

</details>
<details>
<summary>
Communications Managers
</summary>

```diff
+ Hollis Wacker-Leja
+ Katie Guo (Assembly Media, Inc)
```

</details>
<details>
<summary>
Social Media Managers
</summary>

```diff
+ Chad Oetken (Troy Consulting LLC)
```

</details>
<details>
<summary>
Community Managers
</summary>

```diff
+ DèJa Easter (Apex Systems, Inc)
+ Nadine Ebri (Apex Systems, Inc)
```

</details>
<details>
<summary>
Marketing Managers
</summary>

```diff
+ Cori Anne Montero
- Emily Orrson (Emily)
- Lindsay Auten (Simplicity Consulting Inc.)
```

</details>
<details>
<summary>
Financial Accountants
</summary>

```diff
+ Aleksandra Dragosavljevic
```

</details>
<h1>Studios Quality Alumni<a name="credits-studios-quality-alumni"></a></h1>
<h3>Main<a name="credits-studios-quality-alumni-main"></a></h3>
<details>
<summary>
🗒️ Titles
</summary>

```diff
+ Quality Analyst
- Quality Analysts
- Test Managers
```

</details>
<details>
<summary>
Quality Engineers
</summary>

```diff
- Jeff MacDermot
```

</details>
<details>
<summary>
Program Managers
</summary>

```diff
- Amador Abreu (Insight Global, Inc)
```

</details>
<details>
<summary>
Software Engineers
</summary>

```diff
- Henry Golding
```

</details>
<details>
<summary>
Team Leads
</summary>

```diff
- Michał Sławek (Lionbridge)
- Paweł Piekarski (Lionbridge)
- Sebastian Polanica (Lionbridge)
```

</details>
<details>
<summary>
Software Test Engineers
</summary>

```diff
- Marcin Słoniewski (Lionbridge)
- Mateusz Janiszewski (Lionbridge)
```

</details>
<details>
<summary>
Test Associates
</summary>

```diff
- Casper Sparks (Insight Global, Inc.)
- Kacper Bujakowski (Lionbridge)
- Karol Mikusek (Lionbridge)
- Robert Thomas (Experis)
- Wiktor Wrona (Lionbridge)
```

</details>
<details>
<summary>
Studios Quality Special Thanks
</summary>

```diff
- Aaron Brindell (Experis)
- Aaron Ingram (Experis)
- Alex Luschen – Executive Business Administrator
- Brian Canning (Experis) – Test Manager, Tempe
- Carol Stearns (Experis)
- Ryan Burns – Software Engineering Lead
```

</details>
<h1>Development Partner - Blackbird Interactive Alumni<a name="credits-development-partner---blackbird-interactive-alumni"></a></h1>
<h3>Main<a name="credits-development-partner---blackbird-interactive-alumni-main"></a></h3>
<details>
<summary>
🗒️ Titles
</summary>

```diff
+ Quality Assurance Director
+ Technical Director
+ UI Artist
+ UX Designer
```

</details>
<details>
<summary>
Programmers
</summary>

```diff
+ Aaron Freytag
+ Ben Jones
+ Curtis Hodgins
+ Darren Grant
+ Dylan Reviczky
+ Jacky Cai
+ Jakob Trounce
+ Samuel Lapointe
+ Zehao Lu
```

</details>
<details>
<summary>
Producers
</summary>

```diff
+ Matt Kernachan
+ Paul Pera
```

</details>
<details>
<summary>
Quality Assurance Analysts
</summary>

```diff
+ Jamie Cheung
+ Jonathan Lin
+ Kelsey Gottschlich
```

</details>
<h1>Development Partner - SiProgs Alumni<a name="credits-development-partner---siprogs-alumni"></a></h1>
<h3>Main<a name="credits-development-partner---siprogs-alumni-main"></a></h3>
<details>
<summary>
🗒️ Titles
</summary>

```diff
- Software Engineer
```

</details>
<details>
<summary>
Software Engineers
</summary>

```diff
+ Anton Mateasik
```

</details>
<h1>Development Partner - Skybox Alumni<a name="credits-development-partner---skybox-alumni"></a></h1>
<h3>Main<a name="credits-development-partner---skybox-alumni-main"></a></h3>
<details>
<summary>
🗒️ Titles
</summary>

```diff
- Quality Assurance
- Software Developers
```

</details>
<details>
<summary>
Main title
</summary>

```diff
- Ace Cheung
+ Amy Liu
+ Amy Zhao
+ Baktash Abdollah-Shamshir-saz
+ Carsten Hooker
+ Casey White
+ Chuan Shi Yu
+ Cody Clattenburg
+ Cole Pollock
+ Cyro Paulino da Costa Jr
+ Dan Wesley
+ Dayna Cassidy
+ Dee Rueter
+ Felipe Mauricio
+ Gordon Tisher
+ Graham Park
+ Guillermo Trejo Torres
+ Gursaanj Singh Bajaj
+ Gustav Louw
+ Hamza Khachan
+ Houman Gholami
+ Isaac Calon
+ Jacob Jensen
+ Jai Kristjan
+ Jake Megrian
+ Jake Roman-Barnes
+ Jeffrey Chou
+ Joseph Cameron
+ Kelsey Zirk
+ Leonardo Stark
+ Mauricio A. P. Burdelis
+ Mitch Filmer
+ Mitch Lockhart
+ Richard Hawkes
+ Rick Huang
+ Ronald Ariel Kamanga
+ Russell Gillette
+ Sean Siemens
+ Supriya Singh
- Ting-Chun Sun
+ Ty Lauriente
+ William Sherif
+ Yang Zhao
+ Yen-Chun Wang
```

</details>
</details>
<hr/>
<details><summary><b><ins>MISC</ins></b><a name="misc"></a></summary>
<br/>
<details>
<summary>
splashes
</summary>

```diff
- 10 years of Mining and Crafting!
+ 15 years of Mining and Crafting!
+ Chicken Jockey!
+ Flint and Steel!
- Minors welcome!
+ Music by Aaron Cherof!
+ Music by Amos Roddy!
+ Music by Kumi Tanioka!
- Pumpa kungen!
+ Pumpakungen!
```

</details>
<details>
<summary>
parsers
</summary>

```diff
+ minecraft:dialog
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
- XXX.chat.contents.BlockDataSource
+ XXX.chat.contents.DataSource
- XXX.chat.contents.DataSource$Type
+ XXX.chat.contents.EntityDataSource
- XXX.chat.contents.KeybindContents
+ XXX.chat.contents.KeybindResolver
- XXX.chat.contents.NbtContents
+ XXX.chat.contents.package-info
+ XXX.chat.contents.PlainTextContents
- XXX.chat.contents.PlainTextContents$1
+ XXX.chat.contents.PlainTextContents$LiteralContents
- XXX.chat.contents.ScoreContents
+ XXX.chat.contents.SelectorContents
- XXX.chat.contents.StorageDataSource
+ XXX.chat.contents.TranslatableContents
- XXX.chat.contents.TranslatableFormatException
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
+ XXX.datafix.fixes.ItemRemoveBlockEntityTagFix
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
- XXX.datafix.fixes.LevelDataGeneratorOptionsFix
+ XXX.datafix.fixes.LevelFlatGeneratorInfoFix
- XXX.datafix.fixes.LevelLegacyWorldGenSettingsFix
+ XXX.datafix.fixes.LevelUUIDFix
- XXX.datafix.fixes.LockComponentPredicateFix
+ XXX.datafix.fixes.LodestoneCompassComponentFix
- XXX.datafix.fixes.MapBannerBlockPosFormatFix
+ XXX.datafix.fixes.MapIdFix
- XXX.datafix.fixes.MemoryExpiryDataFix
+ XXX.datafix.fixes.MissingDimensionFix
- XXX.datafix.fixes.MobEffectIdFix
+ XXX.datafix.fixes.MobSpawnerEntityIdentifiersFix
- XXX.datafix.fixes.NamedEntityConvertUncheckedFix
+ XXX.datafix.fixes.NamedEntityFix
- XXX.datafix.fixes.NamedEntityWriteReadFix
+ XXX.datafix.fixes.NamespacedTypeRenameFix
- XXX.datafix.fixes.NewVillageFix
+ XXX.datafix.fixes.ObjectiveRenderTypeFix
- XXX.datafix.fixes.OminousBannerBlockEntityRenameFix
+ XXX.datafix.fixes.OminousBannerRarityFix
- XXX.datafix.fixes.OminousBannerRenameFix
+ XXX.datafix.fixes.OptionsAccessibilityOnboardFix
- XXX.datafix.fixes.OptionsAddTextBackgroundFix
+ XXX.datafix.fixes.OptionsAmbientOcclusionFix
- XXX.datafix.fixes.OptionsForceVBOFix
+ XXX.datafix.fixes.OptionsKeyLwjgl3Fix
- XXX.datafix.fixes.OptionsKeyTranslationFix
+ XXX.datafix.fixes.OptionsLowerCaseLanguageFix
- XXX.datafix.fixes.OptionsMenuBlurrinessFix
+ XXX.datafix.fixes.OptionsProgrammerArtFix
- XXX.datafix.fixes.OptionsRenameFieldFix
+ XXX.datafix.fixes.OverreachingTickFix
- XXX.datafix.fixes.ParticleUnflatteningFix
+ XXX.datafix.fixes.PlayerEquipmentFix
- XXX.datafix.fixes.PlayerHeadBlockProfileFix
+ XXX.datafix.fixes.PlayerUUIDFix
- XXX.datafix.fixes.PoiTypeRemoveFix
+ XXX.datafix.fixes.PoiTypeRenameFix
- XXX.datafix.fixes.PrimedTntBlockStateFixer
+ XXX.datafix.fixes.ProjectileStoredWeaponFix
- XXX.datafix.fixes.RaidRenamesDataFix
+ XXX.datafix.fixes.RandomSequenceSettingsFix
- XXX.datafix.fixes.RecipesFix
+ XXX.datafix.fixes.RecipesRenameningFix
- XXX.datafix.fixes.RedstoneWireConnectionsFix
+ XXX.datafix.fixes.References
- XXX.datafix.fixes.References$1
+ XXX.datafix.fixes.RemapChunkStatusFix
- XXX.datafix.fixes.RemoveBlockEntityTagFix
- XXX.dialog.body.DialogBody
- XXX.dialog.body.ItemBody
- XXX.dialog.body.package-info
- XXX.dialog.input.InputControl
- XXX.dialog.input.NumberRangeInput
- XXX.dialog.input.SingleOptionInput
- XXX.dialog.input.TextInput
- XXX.dialog.submit.CustomForm
- XXX.dialog.submit.CustomTemplate
- XXX.dialog.submit.package-info
- XXX.dialog.submit.SubmitMethod
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
- XXX.level.progress.ChunkProgressListener
+ XXX.level.progress.ChunkProgressListenerFactory
- XXX.level.progress.LoggerChunkProgressListener
+ XXX.level.progress.package-info
+ XXX.level.progress.ProcessorChunkProgressListener
- XXX.level.progress.StoringChunkProgressListener
- XXX.metadata.pack.package-info
+ XXX.metadata.pack.PackMetadataSection
+ XXX.minecraft.commands.Commands$1$1
- XXX.minecraft.commands.Commands$2
- XXX.minecraft.commands.Commands$CommandSelection
+ XXX.minecraft.commands.Commands$ParseFunction
- XXX.minecraft.commands.ExecutionCommandSource
+ XXX.minecraft.commands.FunctionInstantiationException
- XXX.minecraft.commands.ParserUtils
- XXX.minecraft.commands.PermissionSource$Check
+ XXX.minecraft.commands.SharedSuggestionProvider
- XXX.minecraft.commands.SharedSuggestionProvider$ElementSuggestionType
+ XXX.minecraft.commands.SharedSuggestionProvider$TextCoordinates
- XXX.minecraft.gametest.Main
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
+ XXX.minecraft.network.MonitoredLocalFrameDecoder
- XXX.minecraft.network.PacketBundlePacker
+ XXX.minecraft.network.PacketBundleUnpacker
- XXX.minecraft.network.PacketDecoder
+ XXX.minecraft.network.PacketEncoder
- XXX.minecraft.network.PacketListener
+ XXX.minecraft.network.PacketSendListener
- XXX.minecraft.network.PacketSendListener$1
+ XXX.minecraft.network.PacketSendListener$2
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
+ XXX.minecraft.server.package-info
+ XXX.minecraft.sounds.Music
- XXX.minecraft.sounds.Musics
- XXX.minecraft.sounds.package-info
+ XXX.minecraft.sounds.SoundEvent
- XXX.minecraft.sounds.SoundEvents
+ XXX.minecraft.sounds.SoundSource
- XXX.minecraft.stats.package-info
+ XXX.minecraft.stats.RecipeBook
- XXX.minecraft.stats.RecipeBookSettings
+ XXX.minecraft.stats.RecipeBookSettings$1
- XXX.minecraft.stats.RecipeBookSettings$TypeSettings
+ XXX.minecraft.stats.ServerRecipeBook
- XXX.minecraft.stats.ServerRecipeBook$DisplayResolver
+ XXX.minecraft.stats.ServerRecipeBook$Packed
- XXX.minecraft.stats.ServerStatsCounter
+ XXX.minecraft.stats.Stat
- XXX.minecraft.stats.StatFormatter
- XXX.minecraft.stats.Stats
+ XXX.minecraft.stats.StatsCounter
+ XXX.minecraft.stats.StatType
+ XXX.minecraft.tags.BannerPatternTags
- XXX.minecraft.tags.BiomeTags
+ XXX.minecraft.tags.BlockTags
- XXX.minecraft.tags.DamageTypeTags
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
- XXX.network.chat.ClickEvent$ShowDialog
+ XXX.network.chat.ClickEvent$SuggestCommand
- XXX.network.chat.CommonComponents
+ XXX.network.chat.Component
- XXX.network.chat.ComponentContents
+ XXX.network.chat.ComponentContents$Type
- XXX.network.chat.ComponentSerialization
+ XXX.network.chat.ComponentSerialization$1
- XXX.network.chat.ComponentSerialization$FuzzyCodec
+ XXX.network.chat.ComponentSerialization$StrictEither
- XXX.network.chat.ComponentUtils
+ XXX.network.chat.FilterMask
- XXX.network.chat.FilterMask$Type
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
- XXX.network.chat.package-info
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
- XXX.network.config.JoinWorldTask
+ XXX.network.config.package-info
+ XXX.network.config.ServerResourcePackConfigurationTask
- XXX.network.config.SynchronizeRegistriesTask
- XXX.packs.linkfs.DummyFileAttributes
+ XXX.packs.linkfs.LinkFileSystem
- XXX.packs.linkfs.LinkFileSystem$Builder
+ XXX.packs.linkfs.LinkFileSystem$DirectoryEntry
+ XXX.packs.linkfs.LinkFSFileStore
- XXX.packs.linkfs.LinkFSPath
+ XXX.packs.linkfs.LinkFSPath$1
- XXX.packs.linkfs.LinkFSPath$2
+ XXX.packs.linkfs.LinkFSPath$3
- XXX.packs.linkfs.LinkFSProvider
+ XXX.packs.linkfs.LinkFSProvider$1
- XXX.packs.linkfs.LinkFSProvider$2
+ XXX.packs.linkfs.package-info
- XXX.packs.linkfs.PathContents
+ XXX.packs.linkfs.PathContents$1
- XXX.packs.linkfs.PathContents$2
+ XXX.packs.linkfs.PathContents$DirectoryContents
- XXX.packs.linkfs.PathContents$FileContents
- XXX.packs.metadata.MetadataSectionType
+ XXX.packs.metadata.package-info
+ XXX.packs.repository.BuiltInPackSource
- XXX.packs.repository.BuiltInPackSource$1
+ XXX.packs.repository.FolderRepositorySource
- XXX.packs.repository.FolderRepositorySource$FolderPackDetector
+ XXX.packs.repository.KnownPack
- XXX.packs.repository.Pack
+ XXX.packs.repository.Pack$Metadata
- XXX.packs.repository.Pack$Position
+ XXX.packs.repository.Pack$ResourcesSupplier
+ XXX.packs.repository.package-info
- XXX.packs.repository.PackCompatibility
+ XXX.packs.repository.PackDetector
- XXX.packs.repository.PackRepository
+ XXX.packs.repository.PackSource
- XXX.packs.repository.PackSource$1
+ XXX.packs.repository.RepositorySource
- XXX.packs.repository.ServerPacksSource
- XXX.packs.resources.CloseableResourceManager
+ XXX.packs.resources.FallbackResourceManager
- XXX.packs.resources.FallbackResourceManager$1ResourceWithSourceAndIndex
+ XXX.packs.resources.FallbackResourceManager$EntryStack
- XXX.packs.resources.FallbackResourceManager$LeakedResourceWarningInputStream
+ XXX.packs.resources.FallbackResourceManager$PackEntry
- XXX.packs.resources.FallbackResourceManager$ResourceWithSource
+ XXX.packs.resources.IoSupplier
- XXX.packs.resources.MultiPackResourceManager
+ XXX.packs.resources.package-info
+ XXX.packs.resources.PreparableReloadListener
- XXX.packs.resources.PreparableReloadListener$PreparationBarrier
+ XXX.packs.resources.ProfiledReloadInstance
- XXX.packs.resources.ProfiledReloadInstance$State
- XXX.packs.resources.ReloadableResourceManager
+ XXX.packs.resources.ReloadInstance
+ XXX.packs.resources.Resource
- XXX.packs.resources.ResourceFilterSection
+ XXX.packs.resources.ResourceManager
- XXX.packs.resources.ResourceManager$Empty
+ XXX.packs.resources.ResourceManagerReloadListener
- XXX.packs.resources.ResourceMetadata
+ XXX.packs.resources.ResourceMetadata$1
- XXX.packs.resources.ResourceMetadata$2
+ XXX.packs.resources.ResourceMetadata$Builder
- XXX.packs.resources.ResourceMetadata$Builder$1
+ XXX.packs.resources.ResourceProvider
- XXX.packs.resources.SimpleJsonResourceReloadListener
+ XXX.packs.resources.SimplePreparableReloadListener
- XXX.packs.resources.SimpleReloadInstance
+ XXX.packs.resources.SimpleReloadInstance$1
- XXX.packs.resources.SimpleReloadInstance$StateFactory
- XXX.protocol.common.ClientboundClearDialogPacket
+ XXX.protocol.common.ClientboundCustomPayloadPacket
- XXX.protocol.common.ClientboundCustomReportDetailsPacket
+ XXX.protocol.common.ClientboundDisconnectPacket
- XXX.protocol.common.ClientboundKeepAlivePacket
+ XXX.protocol.common.ClientboundPingPacket
- XXX.protocol.common.ClientboundResourcePackPopPacket
+ XXX.protocol.common.ClientboundResourcePackPushPacket
- XXX.protocol.common.ClientboundServerLinksPacket
- XXX.protocol.game.ClientboundCommandsPacket$NodeInspector
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
- XXX.protocol.game.ServerboundCustomClickActionPacket
- XXX.rcon.thread.GenericThread
+ XXX.rcon.thread.package-info
+ XXX.rcon.thread.QueryThreadGs4
- XXX.rcon.thread.QueryThreadGs4$RequestChallenge
+ XXX.rcon.thread.RconClient
- XXX.rcon.thread.RconThread
- XXX.server.commands.DialogCommand
+ XXX.server.commands.DifficultyCommand
- XXX.server.commands.EffectCommands
+ XXX.server.commands.EmoteCommands
- XXX.server.commands.EnchantCommand
+ XXX.server.commands.ExecuteCommand
- XXX.server.commands.ExecuteCommand$CommandNumericPredicate
+ XXX.server.commands.ExecuteCommand$CommandPredicate
- XXX.server.commands.ExecuteCommand$ExecuteIfFunctionCustomModifier
+ XXX.server.commands.ExecuteCommand$IntBiPredicate
- XXX.server.commands.ExperienceCommand
+ XXX.server.commands.ExperienceCommand$Type
- XXX.server.commands.FillBiomeCommand
+ XXX.server.commands.FillCommand
- XXX.server.commands.FillCommand$1UpdatedPosition
+ XXX.server.commands.FillCommand$Affector
- XXX.server.commands.FillCommand$Filter
+ XXX.server.commands.FillCommand$Mode
- XXX.server.commands.FillCommand$NullableCommandFunction
+ XXX.server.commands.ForceLoadCommand
- XXX.server.commands.FunctionCommand
+ XXX.server.commands.FunctionCommand$1
- XXX.server.commands.FunctionCommand$1Accumulator
+ XXX.server.commands.FunctionCommand$2
- XXX.server.commands.FunctionCommand$3
+ XXX.server.commands.FunctionCommand$4
- XXX.server.commands.FunctionCommand$5
+ XXX.server.commands.FunctionCommand$Callbacks
- XXX.server.commands.FunctionCommand$FunctionCustomExecutor
+ XXX.server.commands.GameModeCommand
- XXX.server.commands.GameRuleCommand
+ XXX.server.commands.GameRuleCommand$1
- XXX.server.commands.GiveCommand
+ XXX.server.commands.HelpCommand
- XXX.server.commands.InCommandFunction
+ XXX.server.commands.ItemCommands
- XXX.server.commands.JfrCommand
+ XXX.server.commands.KickCommand
- XXX.server.commands.KillCommand
+ XXX.server.commands.ListPlayersCommand
- XXX.server.commands.LocateCommand
+ XXX.server.commands.LookAt
- XXX.server.commands.LookAt$LookAtEntity
+ XXX.server.commands.LookAt$LookAtPosition
- XXX.server.commands.LootCommand
+ XXX.server.commands.LootCommand$Callback
- XXX.server.commands.LootCommand$DropConsumer
+ XXX.server.commands.LootCommand$TailProvider
- XXX.server.commands.MsgCommand
+ XXX.server.commands.OpCommand
- XXX.server.commands.PardonCommand
+ XXX.server.commands.PardonIpCommand
- XXX.server.commands.ParticleCommand
+ XXX.server.commands.PerfCommand
- XXX.server.commands.PermissionCheck
- XXX.server.dialog.ButtonListDialog
- XXX.server.dialog.CommonButtonData
- XXX.server.dialog.ConfirmationDialog
- XXX.server.dialog.DialogListDialog
- XXX.server.dialog.Dialogs
- XXX.server.dialog.InputFormDialog$Input
- XXX.server.dialog.MultiActionDialog
- XXX.server.dialog.NoticeDialog
- XXX.server.dialog.package-info
- XXX.server.dialog.SimpleDialog
+ XXX.server.gui.MinecraftServerGui
- XXX.server.gui.MinecraftServerGui$1
+ XXX.server.gui.MinecraftServerGui$2
- XXX.server.gui.package-info
- XXX.server.gui.PlayerListComponent
+ XXX.server.gui.StatsComponent
+ XXX.server.level.BlockDestructionProgress
- XXX.server.level.ChunkGenerationTask
+ XXX.server.level.ChunkHolder
- XXX.server.level.ChunkHolder$LevelChangeListener
+ XXX.server.level.ChunkHolder$PlayerProvider
- XXX.server.level.ChunkLevel
+ XXX.server.level.ChunkLevel$1
- XXX.server.level.ChunkMap
+ XXX.server.level.ChunkMap$DistanceManager
- XXX.server.level.ChunkMap$TrackedEntity
+ XXX.server.level.ChunkResult
- XXX.server.level.ChunkResult$Fail
+ XXX.server.level.ChunkResult$Success
- XXX.server.level.ChunkTaskDispatcher
+ XXX.server.level.ChunkTaskPriorityQueue
- XXX.server.level.ChunkTaskPriorityQueue$TasksForChunk
+ XXX.server.level.ChunkTracker
- XXX.server.level.ChunkTrackingView
+ XXX.server.level.ChunkTrackingView$1
- XXX.server.level.ChunkTrackingView$Positioned
+ XXX.server.level.ClientInformation
- XXX.server.level.ColumnPos
+ XXX.server.level.DemoMode
- XXX.server.level.DistanceManager
+ XXX.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
- XXX.server.level.DistanceManager$PlayerTicketTracker
+ XXX.server.level.FullChunkStatus
- XXX.server.level.GeneratingChunkMap
+ XXX.server.level.GenerationChunkHolder
- XXX.server.level.LoadingChunkTracker
+ XXX.server.level.package-info
+ XXX.server.level.ParticleStatus
- XXX.server.level.PlayerMap
+ XXX.server.level.PlayerRespawnLogic
- XXX.server.level.SectionTracker
+ XXX.server.level.ServerBossEvent
- XXX.server.level.ServerChunkCache
+ XXX.server.level.ServerChunkCache$MainThreadExecutor
- XXX.server.level.ServerEntity
+ XXX.server.level.ServerEntityGetter
- XXX.server.level.ServerLevel
+ XXX.server.level.ServerLevel$1
- XXX.server.level.ServerLevel$EntityCallbacks
+ XXX.server.level.ServerPlayer
- XXX.server.level.ServerPlayer$1
+ XXX.server.level.ServerPlayer$1$1
- XXX.server.level.ServerPlayer$2
+ XXX.server.level.ServerPlayer$3
- XXX.server.level.ServerPlayer$RespawnConfig
+ XXX.server.level.ServerPlayer$RespawnPosAngle
- XXX.server.level.ServerPlayerGameMode
+ XXX.server.level.SimulationChunkTracker
- XXX.server.level.ThreadedLevelLightEngine
+ XXX.server.level.ThreadedLevelLightEngine$TaskType
- XXX.server.level.ThrottlingChunkTaskDispatcher
+ XXX.server.level.Ticket
- XXX.server.level.TicketType
+ XXX.server.level.TicketType$TicketUse
- XXX.server.level.WorldGenRegion
- XXX.server.network.CommonListenerCookie
+ XXX.server.network.ConfigurationTask
- XXX.server.network.ConfigurationTask$Type
+ XXX.server.network.Filterable
- XXX.server.network.FilteredText
+ XXX.server.network.LegacyProtocolUtils
- XXX.server.network.LegacyQueryHandler
+ XXX.server.network.LegacyTextFilter
- XXX.server.network.LegacyTextFilter$1
+ XXX.server.network.LegacyTextFilter$JoinOrLeaveEncoder
- XXX.server.network.MemoryServerHandshakePacketListenerImpl
- XXX.server.network.package-info
+ XXX.server.network.PlayerChunkSender
- XXX.server.network.PlayerSafetyServiceTextFilter
+ XXX.server.network.ServerCommonPacketListenerImpl
- XXX.server.network.ServerConfigurationPacketListenerImpl
+ XXX.server.network.ServerConnectionListener
- XXX.server.network.ServerConnectionListener$1
+ XXX.server.network.ServerConnectionListener$2
- XXX.server.network.ServerConnectionListener$LatencySimulator
+ XXX.server.network.ServerConnectionListener$LatencySimulator$DelayedMessage
- XXX.server.network.ServerGamePacketListenerImpl
+ XXX.server.network.ServerGamePacketListenerImpl$1
- XXX.server.network.ServerGamePacketListenerImpl$2
+ XXX.server.network.ServerGamePacketListenerImpl$EntityInteraction
- XXX.server.network.ServerHandshakePacketListenerImpl
+ XXX.server.network.ServerHandshakePacketListenerImpl$1
- XXX.server.network.ServerLoginPacketListenerImpl
+ XXX.server.network.ServerLoginPacketListenerImpl$1
- XXX.server.network.ServerLoginPacketListenerImpl$State
+ XXX.server.network.ServerPlayerConnection
- XXX.server.network.ServerStatusPacketListenerImpl
+ XXX.server.network.ServerTextFilter
- XXX.server.network.ServerTextFilter$IgnoreStrategy
+ XXX.server.network.ServerTextFilter$MessageEncoder
- XXX.server.network.ServerTextFilter$PlayerContext
+ XXX.server.network.ServerTextFilter$RequestFailedException
- XXX.server.network.TextFilter
+ XXX.server.network.TextFilter$1
- XXX.server.packs.AbstractPackResources
+ XXX.server.packs.BuiltInMetadata
- XXX.server.packs.CompositePackResources
+ XXX.server.packs.DownloadCacheCleaner
- XXX.server.packs.DownloadCacheCleaner$1
+ XXX.server.packs.DownloadCacheCleaner$PathAndPriority
- XXX.server.packs.DownloadCacheCleaner$PathAndTime
+ XXX.server.packs.DownloadQueue
- XXX.server.packs.DownloadQueue$BatchConfig
+ XXX.server.packs.DownloadQueue$BatchResult
- XXX.server.packs.DownloadQueue$DownloadRequest
+ XXX.server.packs.DownloadQueue$FileInfoEntry
- XXX.server.packs.DownloadQueue$LogEntry
+ XXX.server.packs.FeatureFlagsMetadataSection
- XXX.server.packs.FilePackResources
+ XXX.server.packs.FilePackResources$FileResourcesSupplier
- XXX.server.packs.FilePackResources$SharedZipFileAccess
+ XXX.server.packs.OverlayMetadataSection
- XXX.server.packs.OverlayMetadataSection$OverlayEntry
- XXX.server.packs.package-info
+ XXX.server.packs.PackLocationInfo
- XXX.server.packs.PackResources
+ XXX.server.packs.PackResources$ResourceOutput
- XXX.server.packs.PackSelectionConfig
+ XXX.server.packs.PackType
- XXX.server.packs.PathPackResources
+ XXX.server.packs.PathPackResources$PathResourcesSupplier
- XXX.server.packs.VanillaPackResources
+ XXX.server.packs.VanillaPackResourcesBuilder
- XXX.server.players.BanListEntry
+ XXX.server.players.GameProfileCache
- XXX.server.players.GameProfileCache$GameProfileInfo
+ XXX.server.players.IpBanList
- XXX.server.players.IpBanListEntry
+ XXX.server.players.OldUsersConverter
- XXX.server.players.OldUsersConverter$1
+ XXX.server.players.OldUsersConverter$2
- XXX.server.players.OldUsersConverter$3
+ XXX.server.players.OldUsersConverter$4
- XXX.server.players.OldUsersConverter$5
+ XXX.server.players.OldUsersConverter$ConversionError
+ XXX.server.players.package-info
- XXX.server.players.PlayerList
+ XXX.server.players.PlayerList$1
- XXX.server.players.ServerOpList
+ XXX.server.players.ServerOpListEntry
- XXX.server.players.SleepStatus
+ XXX.server.players.StoredUserEntry
- XXX.server.players.StoredUserList
+ XXX.server.players.UserBanList
- XXX.server.players.UserBanListEntry
+ XXX.server.players.UserWhiteList
- XXX.server.players.UserWhiteListEntry
- XXX.server.rcon.NetworkDataOutputStream
+ XXX.server.rcon.package-info
+ XXX.server.rcon.PktUtils
- XXX.server.rcon.RconConsoleSource
- XXX.server.waypoints.ServerWaypointManager
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
XXX.minecraft.commands.Commands +6M -7M | +1P
```
```
XXX.commands.synchronization.SuggestionProviders +2M -3M | +1P -1P
```
```
XXX.protocol.game.ClientboundCommandsPacket$ArgumentNodeStub +7M -3M
```
```
XXX.protocol.game.ClientboundCommandsPacket$LiteralNodeStub +5M -1M
```
```
XXX.protocol.game.ClientboundCommandsPacket$NodeStub +1P -1P
```
```
XXX.minecraft.server.MinecraftServer +1M
```
```
XXX.minecraft.server.ReloadableServerRegistries$Holder +1M -2M
```
```
XXX.server.commands.AttributeCommand +12M -13M
```
```
XXX.server.commands.BanListCommands +4M -5M
```
```
XXX.server.commands.BossBarCommands +17M -18M
```
```
XXX.server.commands.ClearInventoryCommands +5M -6M
```
```
XXX.server.commands.DamageCommand +2M -3M
```
```
XXX.server.commands.DebugCommand +3M -5M
```
```
XXX.server.commands.DebugConfigCommand +4M -5M
```
```
XXX.server.commands.DebugPathCommand +2M -3M
```
```
XXX.server.commands.PlaySoundCommand +3M -4M
```
```
XXX.server.commands.RaidCommand +6M -7M
```
```
XXX.server.commands.RecipeCommand +3M -4M
```
```
XXX.server.commands.ReturnCommand -1M
```
```
XXX.server.commands.RideCommand +4M -5M
```
```
XXX.server.commands.SaveAllCommand +2M -3M
```
```
XXX.server.commands.SaveOnCommand +2M -3M
```
```
XXX.server.commands.ScheduleCommand +3M -4M
```
```
XXX.server.commands.ServerPackCommand +3M -4M
```
```
XXX.server.commands.SetSpawnCommand +2M -3M
```
```
XXX.server.commands.SpawnArmorTrimsCommand +4M -5M
```
```
XXX.server.commands.SpreadPlayersCommand +2M -3M
```
```
XXX.server.commands.StopCommand +2M -3M
```
```
XXX.server.commands.SummonCommand +3M -4M
```
```
XXX.server.commands.TeamCommand +19M -20M
```
```
XXX.server.commands.TeleportCommand +5M -7M
```
```
XXX.server.commands.TickCommand +18M -19M
```
```
XXX.server.commands.TitleCommand +5M -6M
```
```
XXX.server.commands.WardenSpawnTrackerCommand +4M -5M
```
```
XXX.server.commands.WeatherCommand +4M -5M
```
```
XXX.server.commands.WorldBorderCommand +9M -10M
```
```
XXX.commands.data.DataCommands +30M -31M
```
```
XXX.minecraft.world.Difficulty +1P
```
```
XXX.world.entity.Entity +2M -1M
```
```
XXX.world.entity.Leashable +1M
```
```
XXX.world.entity.Mob +1M
```
```
XXX.entity.animal.HappyGhast +2M | -1P
```
```
XXX.animal.sheep.Sheep -2M | -1P
```
```
XXX.animal.wolf.Wolf +1M
```
```
XXX.entity.player.Player +1M
```
```
XXX.world.item.Items +1P
```
```
XXX.item.equipment.Equippable +3M -1M | +2P
```
```
XXX.world.level.GameType +1P
```
```
XXX.level.block.DriedGhastBlock -1M
```
```
XXX.block.entity.SignBlockEntity +2M -2M
```

</details>
<details>
<summary>
net.minecraft.commands.Commands
</summary>

```diff
- boolean lambda$createValidator$5(Commands$ParseFunction,String)
+ boolean lambda$createValidator$7(Commands$ParseFunction,String)
+ boolean lambda$fillUsableCommands$5(SharedSuggestionProvider)
- boolean lambda$validate$7(ArgumentType)
+ boolean lambda$validate$9(ArgumentType)
+ int lambda$fillUsableCommands$6(CommandContext)
- PermissionCheck hasPermission(int)
+ String lambda$validate$10(ArgumentType)
- String lambda$validate$8(ArgumentType)
+ void fillUsableCommands(CommandNode,CommandNode,CommandSourceStack,Map)
- void fillUsableCommands(CommandNode,CommandNode,Object,Map)
- void lambda$validate$6(CommandDispatcher,CommandNode,CommandNode,CommandNode,Collection)
+ void lambda$validate$8(CommandDispatcher,CommandNode,CommandNode,CommandNode,Collection)
```

</details>
<details>
<summary>
net.minecraft.commands.synchronization.SuggestionProviders
</summary>

```diff
- CompletableFuture lambda$static$3(CommandContext,SuggestionsBuilder)
+ CompletableFuture lambda$static$4(CommandContext,SuggestionsBuilder)
+ Message lambda$static$3(EntityType)
- SuggestionProvider cast(SuggestionProvider)
+ SuggestionProvider safelySwap(SuggestionProvider)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundCommandsPacket$ArgumentNodeStub
</summary>

```diff
- ArgumentBuilder build(CommandBuildContext,ClientboundCommandsPacket$NodeBuilder)
+ ArgumentBuilder build(CommandBuildContext)
- ArgumentTypeInfo$Template argumentType()
- boolean equals(Object)
- int hashCode()
+ ResourceLocation getSuggestionId(SuggestionProvider)
- ResourceLocation suggestionId()
- String id()
- String toString()
+ void <init>(ArgumentCommandNode)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundCommandsPacket$LiteralNodeStub
</summary>

```diff
- ArgumentBuilder build(CommandBuildContext,ClientboundCommandsPacket$NodeBuilder)
+ ArgumentBuilder build(CommandBuildContext)
- boolean equals(Object)
- int hashCode()
- String id()
- String toString()
```

</details>
<details>
<summary>
net.minecraft.server.MinecraftServer
</summary>

```diff
- void handleCustomClickAction(ResourceLocation,Optional)
```

</details>
<details>
<summary>
net.minecraft.server.ReloadableServerRegistries$Holder
</summary>

```diff
+ Collection getKeys(ResourceKey)
+ HolderGetter$Provider lookup()
- HolderLookup$Provider lookup()
```

</details>
<details>
<summary>
net.minecraft.server.commands.AttributeCommand
</summary>

```diff
+ boolean lambda$register$4(CommandSourceStack)
- CompletableFuture lambda$register$13(CommandContext,SuggestionsBuilder)
+ CompletableFuture lambda$register$14(CommandContext,SuggestionsBuilder)
- CompletableFuture lambda$register$15(CommandContext,SuggestionsBuilder)
+ CompletableFuture lambda$register$16(CommandContext,SuggestionsBuilder)
- Component lambda$addModifier$23(ResourceLocation,Holder,Entity)
+ Component lambda$addModifier$24(ResourceLocation,Holder,Entity)
- Component lambda$getAttributeBase$19(Holder,Entity,double)
+ Component lambda$getAttributeBase$20(Holder,Entity,double)
- Component lambda$getAttributeModifier$20(ResourceLocation,Holder,Entity,double)
+ Component lambda$getAttributeModifier$21(ResourceLocation,Holder,Entity,double)
- Component lambda$getAttributeValue$18(Holder,Entity,double)
+ Component lambda$getAttributeValue$19(Holder,Entity,double)
- Component lambda$removeModifier$24(ResourceLocation,Holder,Entity)
+ Component lambda$removeModifier$25(ResourceLocation,Holder,Entity)
- Component lambda$resetAttributeBase$22(Holder,Entity,double)
+ Component lambda$resetAttributeBase$23(Holder,Entity,double)
- Component lambda$setAttributeBase$21(Holder,Entity,double)
+ Component lambda$setAttributeBase$22(Holder,Entity,double)
+ int lambda$register$13(CommandContext)
- int lambda$register$14(CommandContext)
+ int lambda$register$15(CommandContext)
- int lambda$register$16(CommandContext)
+ int lambda$register$18(CommandContext)
- int lambda$register$4(CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.BanListCommands
</summary>

```diff
+ boolean lambda$register$0(CommandSourceStack)
- Component lambda$showList$3()
+ Component lambda$showList$4()
- Component lambda$showList$4(Collection)
- Component lambda$showList$5(BanListEntry)
+ Component lambda$showList$5(Collection)
+ Component lambda$showList$6(BanListEntry)
- int lambda$register$0(CommandContext)
+ int lambda$register$3(CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.BossBarCommands
</summary>

```diff
+ boolean lambda$register$3(CommandSourceStack)
- Component lambda$createBar$45(CustomBossEvent)
+ Component lambda$createBar$46(CustomBossEvent)
- Component lambda$getMax$29(CustomBossEvent)
+ Component lambda$getMax$30(CustomBossEvent)
- Component lambda$getPlayers$32(CustomBossEvent)
+ Component lambda$getPlayers$34(CustomBossEvent)
- Component lambda$getValue$28(CustomBossEvent)
+ Component lambda$getValue$29(CustomBossEvent)
- Component lambda$getVisible$30(CustomBossEvent)
+ Component lambda$getVisible$32(CustomBossEvent)
- Component lambda$listBars$43()
+ Component lambda$listBars$44()
- Component lambda$listBars$44(Collection)
+ Component lambda$listBars$45(Collection)
- Component lambda$removeBar$46(CustomBossEvent)
+ Component lambda$removeBar$47(CustomBossEvent)
- Component lambda$setColor$38(CustomBossEvent)
+ Component lambda$setColor$39(CustomBossEvent)
- Component lambda$setMax$37(CustomBossEvent,int)
+ Component lambda$setMax$38(CustomBossEvent,int)
- Component lambda$setName$40(CustomBossEvent)
+ Component lambda$setName$41(CustomBossEvent)
- Component lambda$setPlayers$41(CustomBossEvent)
- Component lambda$setPlayers$42(CustomBossEvent,Collection)
+ Component lambda$setPlayers$42(CustomBossEvent)
+ Component lambda$setPlayers$43(CustomBossEvent,Collection)
- Component lambda$setStyle$39(CustomBossEvent)
+ Component lambda$setStyle$40(CustomBossEvent)
- Component lambda$setValue$36(CustomBossEvent,int)
+ Component lambda$setValue$37(CustomBossEvent,int)
- Component lambda$setVisible$34(CustomBossEvent)
+ Component lambda$setVisible$36(CustomBossEvent)
+ int lambda$register$28(CommandContext)
- int lambda$register$3(CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.ClearInventoryCommands
</summary>

```diff
+ boolean lambda$register$2(CommandSourceStack)
- boolean lambda$register$2(ItemStack)
+ boolean lambda$register$3(ItemStack)
- boolean lambda$register$4(ItemStack)
+ boolean lambda$register$5(ItemStack)
+ Component lambda$clearInventory$12(int,Collection)
- Component lambda$clearInventory$8(int,Collection)
- int lambda$register$3(CommandContext)
+ int lambda$register$4(CommandContext)
- int lambda$register$5(CommandContext)
+ int lambda$register$8(CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.DamageCommand
</summary>

```diff
+ boolean lambda$register$0(CommandSourceStack)
- Component lambda$damage$5(float,Entity)
+ Component lambda$damage$6(float,Entity)
- int lambda$register$0(CommandContext)
+ int lambda$register$5(CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.DebugCommand
</summary>

```diff
+ boolean lambda$register$0(CommandSourceStack)
+ boolean lambda$register$3(CommandSourceStack)
- Component lambda$start$2()
+ Component lambda$start$4()
- Component lambda$stop$3(double,ProfileResults,double)
+ Component lambda$stop$5(double,ProfileResults,double)
- int lambda$register$0(CommandContext)
+ int lambda$register$2(CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.DebugConfigCommand
</summary>

```diff
+ boolean lambda$register$0(CommandSourceStack)
- CompletableFuture lambda$register$1(CommandContext,SuggestionsBuilder)
+ CompletableFuture lambda$register$2(CommandContext,SuggestionsBuilder)
- Component lambda$config$3(GameProfile)
+ Component lambda$config$4(GameProfile)
- int lambda$register$0(CommandContext)
+ int lambda$register$1(CommandContext)
- int lambda$register$2(CommandContext)
+ int lambda$register$3(CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.DebugPathCommand
</summary>

```diff
+ boolean lambda$register$0(CommandSourceStack)
- Component lambda$fillBlocks$1()
+ Component lambda$fillBlocks$2()
- int lambda$register$0(CommandContext)
+ int lambda$register$1(CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.PlaySoundCommand
</summary>

```diff
+ boolean lambda$register$1(CommandSourceStack)
- Component lambda$playSound$7(ResourceLocation,List)
- Component lambda$playSound$8(ResourceLocation,int)
+ Component lambda$playSound$8(ResourceLocation,List)
+ Component lambda$playSound$9(ResourceLocation,int)
- int lambda$source$1(SoundSource,CommandContext)
+ int lambda$source$7(SoundSource,CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.RaidCommand
</summary>

```diff
+ boolean lambda$register$0(CommandSourceStack)
- Component lambda$check$11(StringBuilder)
+ Component lambda$check$13(StringBuilder)
- Component lambda$setRaidOmenLevel$7(int,int)
+ Component lambda$setRaidOmenLevel$8(int,int)
- Component lambda$spawnLeader$8()
+ Component lambda$spawnLeader$9()
+ Component lambda$start$10()
- Component lambda$start$9()
- Component lambda$stop$10()
+ Component lambda$stop$11()
- int lambda$register$0(CommandContext)
+ int lambda$register$7(CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.RecipeCommand
</summary>

```diff
+ boolean lambda$register$0(CommandSourceStack)
- Component lambda$giveRecipes$4(Collection,Collection)
+ Component lambda$giveRecipes$6(Collection,Collection)
- Component lambda$takeRecipes$6(Collection,Collection)
+ Component lambda$takeRecipes$8(Collection,Collection)
- int lambda$register$0(CommandContext)
+ int lambda$register$4(CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.ReturnCommand
</summary>

```diff
+ boolean lambda$register$0(ExecutionCommandSource)
```

</details>
<details>
<summary>
net.minecraft.server.commands.RideCommand
</summary>

```diff
- boolean lambda$mount$5(Entity,Entity)
+ boolean lambda$mount$6(Entity,Entity)
+ boolean lambda$register$3(CommandSourceStack)
- Component lambda$dismount$7(Entity,Entity)
+ Component lambda$dismount$8(Entity,Entity)
- Component lambda$mount$6(Entity,Entity)
+ Component lambda$mount$7(Entity,Entity)
- int lambda$register$3(CommandContext)
+ int lambda$register$5(CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.SaveAllCommand
</summary>

```diff
+ boolean lambda$register$0(CommandSourceStack)
- Component lambda$saveAll$2()
+ Component lambda$saveAll$4()
- int lambda$register$0(CommandContext)
+ int lambda$register$2(CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.SaveOnCommand
</summary>

```diff
+ boolean lambda$register$0(CommandSourceStack)
- Component lambda$register$0()
+ Component lambda$register$1()
- int lambda$register$1(CommandContext)
+ int lambda$register$2(CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.ScheduleCommand
</summary>

```diff
+ boolean lambda$register$2(CommandSourceStack)
- Component lambda$remove$8(int,String)
+ Component lambda$remove$9(int,String)
- Component lambda$schedule$6(ResourceLocation,int,long)
+ Component lambda$schedule$8(ResourceLocation,int,long)
- int lambda$register$2(CommandContext)
+ int lambda$register$6(CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.ServerPackCommand
</summary>

```diff
+ boolean lambda$register$0(CommandSourceStack)
- int lambda$register$0(CommandContext)
+ int lambda$register$4(CommandContext)
- UUID lambda$pushPack$5(String)
+ UUID lambda$pushPack$6(String)
- void lambda$sendToAllConnections$4(Packet,Connection)
+ void lambda$sendToAllConnections$5(Packet,Connection)
```

</details>
<details>
<summary>
net.minecraft.server.commands.SetSpawnCommand
</summary>

```diff
+ boolean lambda$register$0(CommandSourceStack)
- Component lambda$setSpawn$4(BlockPos,float,String,Collection)
+ Component lambda$setSpawn$6(BlockPos,float,String,Collection)
- int lambda$register$0(CommandContext)
+ int lambda$register$4(CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.SpawnArmorTrimsCommand
</summary>

```diff
+ boolean lambda$register$1(CommandSourceStack)
- Component lambda$spawnArmorTrims$5()
+ Component lambda$spawnArmorTrims$6()
- int lambda$register$1(CommandContext)
+ int lambda$register$3(CommandContext)
- Integer lambda$spawnArmorTrims$3(Holder$Reference)
+ Integer lambda$spawnArmorTrims$5(Holder$Reference)
- void lambda$findEquippableItemsWithAssets$6(List,Holder$Reference)
+ void lambda$findEquippableItemsWithAssets$7(List,Holder$Reference)
```

</details>
<details>
<summary>
net.minecraft.server.commands.SpreadPlayersCommand
</summary>

```diff
+ boolean lambda$register$3(CommandSourceStack)
- Component lambda$spreadPlayers$5(boolean,SpreadPlayersCommand$Position[],Vec2,double)
+ Component lambda$spreadPlayers$6(boolean,SpreadPlayersCommand$Position[],Vec2,double)
- int lambda$register$3(CommandContext)
+ int lambda$register$5(CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.StopCommand
</summary>

```diff
+ boolean lambda$register$0(CommandSourceStack)
- Component lambda$register$0()
+ Component lambda$register$1()
- int lambda$register$1(CommandContext)
+ int lambda$register$2(CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.SummonCommand
</summary>

```diff
+ boolean lambda$register$0(CommandSourceStack)
- Component lambda$spawnEntity$4(Entity)
+ Component lambda$spawnEntity$5(Entity)
- Entity lambda$createEntity$3(Vec3,Entity)
+ Entity lambda$createEntity$4(Vec3,Entity)
- int lambda$register$0(CommandContext)
+ int lambda$register$3(CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.TeamCommand
</summary>

```diff
+ boolean lambda$register$0(CommandSourceStack)
- Component lambda$createTeam$40(PlayerTeam)
+ Component lambda$createTeam$41(PlayerTeam)
- Component lambda$deleteTeam$39(PlayerTeam)
+ Component lambda$deleteTeam$40(PlayerTeam)
- Component lambda$emptyTeam$38(Collection,PlayerTeam)
+ Component lambda$emptyTeam$39(Collection,PlayerTeam)
- Component lambda$joinTeam$29(Collection,PlayerTeam)
+ Component lambda$joinTeam$31(Collection,PlayerTeam)
- Component lambda$leaveTeam$27(Collection)
+ Component lambda$leaveTeam$29(Collection)
- Component lambda$listMembers$41(PlayerTeam)
- Component lambda$listMembers$42(PlayerTeam,Collection)
+ Component lambda$listMembers$42(PlayerTeam)
+ Component lambda$listMembers$43(PlayerTeam,Collection)
- Component lambda$listTeams$43()
+ Component lambda$listTeams$44()
- Component lambda$listTeams$44(Collection)
+ Component lambda$listTeams$45(Collection)
- Component lambda$setCollision$33(PlayerTeam,Team$CollisionRule)
+ Component lambda$setCollision$34(PlayerTeam,Team$CollisionRule)
- Component lambda$setColor$37(PlayerTeam,ChatFormatting)
+ Component lambda$setColor$38(PlayerTeam,ChatFormatting)
- Component lambda$setDeathMessageVisibility$32(PlayerTeam,Team$Visibility)
+ Component lambda$setDeathMessageVisibility$33(PlayerTeam,Team$Visibility)
- Component lambda$setDisplayName$36(PlayerTeam)
+ Component lambda$setDisplayName$37(PlayerTeam)
- Component lambda$setFriendlyFire$35(boolean,PlayerTeam)
+ Component lambda$setFriendlyFire$36(boolean,PlayerTeam)
- Component lambda$setFriendlySight$34(boolean,PlayerTeam)
+ Component lambda$setFriendlySight$35(boolean,PlayerTeam)
- Component lambda$setNametagVisibility$31(PlayerTeam,Team$Visibility)
+ Component lambda$setNametagVisibility$32(PlayerTeam,Team$Visibility)
- Component lambda$setPrefix$45(Component)
+ Component lambda$setPrefix$46(Component)
- Component lambda$setSuffix$46(Component)
+ Component lambda$setSuffix$47(Component)
- int lambda$register$0(CommandContext)
+ int lambda$register$27(CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.TeleportCommand
</summary>

```diff
+ boolean lambda$register$0(CommandSourceStack)
+ boolean lambda$register$9(CommandSourceStack)
+ Component lambda$teleportToEntity$10(Collection,Entity)
+ Component lambda$teleportToEntity$11(Collection,Entity)
- Component lambda$teleportToEntity$8(Collection,Entity)
- Component lambda$teleportToEntity$9(Collection,Entity)
- Component lambda$teleportToPos$10(Collection,Vec3)
- Component lambda$teleportToPos$11(Collection,Vec3)
+ Component lambda$teleportToPos$12(Collection,Vec3)
+ Component lambda$teleportToPos$13(Collection,Vec3)
- int lambda$register$0(CommandContext)
+ int lambda$register$8(CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.TickCommand
</summary>

```diff
+ boolean lambda$register$0(CommandSourceStack)
- CompletableFuture lambda$register$1(CommandContext,SuggestionsBuilder)
+ CompletableFuture lambda$register$2(CommandContext,SuggestionsBuilder)
- CompletableFuture lambda$register$5(CommandContext,SuggestionsBuilder)
+ CompletableFuture lambda$register$6(CommandContext,SuggestionsBuilder)
- CompletableFuture lambda$register$8(CommandContext,SuggestionsBuilder)
+ CompletableFuture lambda$register$9(CommandContext,SuggestionsBuilder)
- Component lambda$setFreeze$22()
+ Component lambda$setFreeze$24()
- Component lambda$setTickingRate$12(String)
+ Component lambda$setTickingRate$13(String)
- Component lambda$sprint$20()
+ Component lambda$sprint$22()
- Component lambda$step$24(int)
+ Component lambda$step$25(int)
- Component lambda$stopSprinting$26()
+ Component lambda$stopSprinting$27()
- Component lambda$stopStepping$25()
+ Component lambda$stopStepping$26()
- Component lambda$tickQuery$13()
+ Component lambda$tickQuery$14()
- Component lambda$tickQuery$14(String,String)
- Component lambda$tickQuery$15()
+ Component lambda$tickQuery$15(String,String)
+ Component lambda$tickQuery$18()
- Component lambda$tickQuery$18(String,String,String)
- Component lambda$tickQuery$19(String,String,String,long[])
+ Component lambda$tickQuery$19(String,String,String)
+ Component lambda$tickQuery$20(String,String,String,long[])
- int lambda$register$0(CommandContext)
+ int lambda$register$1(CommandContext)
+ int lambda$register$12(CommandContext)
- int lambda$register$2(CommandContext)
+ int lambda$register$5(CommandContext)
- int lambda$register$6(CommandContext)
+ int lambda$register$8(CommandContext)
- int lambda$register$9(CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.TitleCommand
</summary>

```diff
+ boolean lambda$register$0(CommandSourceStack)
- Component lambda$clearTitle$6(Collection)
+ Component lambda$clearTitle$8(Collection)
+ Component lambda$resetTitle$10(Collection)
- Component lambda$resetTitle$8(Collection)
- Component lambda$setTimes$12(Collection)
+ Component lambda$setTimes$14(Collection)
- Component lambda$showTitle$10(String,Collection)
+ Component lambda$showTitle$12(String,Collection)
- int lambda$register$0(CommandContext)
+ int lambda$register$6(CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.WardenSpawnTrackerCommand
</summary>

```diff
+ boolean lambda$register$0(CommandSourceStack)
- Component lambda$resetTracker$5(Collection)
+ Component lambda$resetTracker$7(Collection)
- Component lambda$setWarningLevel$3(Collection)
+ Component lambda$setWarningLevel$5(Collection)
- int lambda$register$0(CommandContext)
+ int lambda$register$2(CommandContext)
- void lambda$setWarningLevel$2(int,WardenSpawnTracker)
+ void lambda$setWarningLevel$3(int,WardenSpawnTracker)
```

</details>
<details>
<summary>
net.minecraft.server.commands.WeatherCommand
</summary>

```diff
+ boolean lambda$register$0(CommandSourceStack)
- Component lambda$setClear$6()
+ Component lambda$setClear$7()
- Component lambda$setRain$7()
+ Component lambda$setRain$8()
- Component lambda$setThunder$8()
+ Component lambda$setThunder$9()
- int lambda$register$0(CommandContext)
+ int lambda$register$6(CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.WorldBorderCommand
</summary>

```diff
+ boolean lambda$register$0(CommandSourceStack)
- Component lambda$getSize$14(double)
+ Component lambda$getSize$15(double)
- Component lambda$setCenter$15(Vec2)
+ Component lambda$setCenter$16(Vec2)
- Component lambda$setDamageAmount$11(float)
+ Component lambda$setDamageAmount$12(float)
- Component lambda$setDamageBuffer$10(float)
+ Component lambda$setDamageBuffer$11(float)
- Component lambda$setSize$16(double,long)
+ Component lambda$setSize$18(double,long)
- Component lambda$setSize$18(double)
+ Component lambda$setSize$19(double)
- Component lambda$setWarningDistance$13(int)
+ Component lambda$setWarningDistance$14(int)
- Component lambda$setWarningTime$12(int)
+ Component lambda$setWarningTime$13(int)
- int lambda$register$0(CommandContext)
+ int lambda$register$10(CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.data.DataCommands
</summary>

```diff
- ArgumentBuilder lambda$decorateModification$23(DataCommands$DataProvider,DataCommands$DataManipulator,DataCommands$DataProvider,ArgumentBuilder)
+ ArgumentBuilder lambda$decorateModification$24(DataCommands$DataProvider,DataCommands$DataManipulator,DataCommands$DataProvider,ArgumentBuilder)
- ArgumentBuilder lambda$decorateModification$24(DataCommands$DataProvider,DataCommands$DataProvider,DataCommands$DataManipulator)
+ ArgumentBuilder lambda$decorateModification$25(DataCommands$DataProvider,DataCommands$DataProvider,DataCommands$DataManipulator)
- ArgumentBuilder lambda$decorateModification$33(DataCommands$DataProvider,DataCommands$DataManipulator,DataCommands$DataProvider,ArgumentBuilder)
+ ArgumentBuilder lambda$decorateModification$34(DataCommands$DataProvider,DataCommands$DataManipulator,DataCommands$DataProvider,ArgumentBuilder)
- ArgumentBuilder lambda$decorateModification$34(DataCommands$DataProvider,DataCommands$DataProvider,DataCommands$DataManipulator)
+ ArgumentBuilder lambda$decorateModification$35(DataCommands$DataProvider,DataCommands$DataProvider,DataCommands$DataManipulator)
- ArgumentBuilder lambda$decorateModification$36(DataCommands$DataProvider,DataCommands$DataManipulator)
- ArgumentBuilder lambda$decorateModification$37(BiConsumer,DataCommands$DataProvider,ArgumentBuilder)
+ ArgumentBuilder lambda$decorateModification$37(DataCommands$DataProvider,DataCommands$DataManipulator)
+ ArgumentBuilder lambda$decorateModification$38(BiConsumer,DataCommands$DataProvider,ArgumentBuilder)
- ArgumentBuilder lambda$register$12(DataCommands$DataProvider,ArgumentBuilder)
+ ArgumentBuilder lambda$register$13(DataCommands$DataProvider,ArgumentBuilder)
- ArgumentBuilder lambda$register$14(DataCommands$DataProvider,ArgumentBuilder)
+ ArgumentBuilder lambda$register$15(DataCommands$DataProvider,ArgumentBuilder)
- ArgumentBuilder lambda$register$8(DataCommands$DataProvider,ArgumentBuilder)
+ ArgumentBuilder lambda$register$9(DataCommands$DataProvider,ArgumentBuilder)
+ boolean lambda$register$7(CommandSourceStack)
- Component lambda$getData$40(DataAccessor,Tag)
+ Component lambda$getData$41(DataAccessor,Tag)
- Component lambda$getData$42(DataAccessor,CompoundTag)
+ Component lambda$getData$43(DataAccessor,CompoundTag)
- Component lambda$getNumeric$41(DataAccessor,NbtPathArgument$NbtPath,double,int)
+ Component lambda$getNumeric$42(DataAccessor,NbtPathArgument$NbtPath,double,int)
- Component lambda$manipulateData$38(DataAccessor)
+ Component lambda$manipulateData$39(DataAccessor)
- Component lambda$mergeData$43(DataAccessor)
+ Component lambda$mergeData$44(DataAccessor)
- Component lambda$removeData$39(DataAccessor)
+ Component lambda$removeData$40(DataAccessor)
- int lambda$decorateModification$21(DataCommands$DataProvider,DataCommands$DataManipulator,DataCommands$DataProvider,CommandContext)
+ int lambda$decorateModification$23(DataCommands$DataProvider,DataCommands$DataManipulator,DataCommands$DataProvider,CommandContext)
- int lambda$decorateModification$26(DataCommands$DataProvider,DataCommands$DataManipulator,DataCommands$DataProvider,CommandContext)
+ int lambda$decorateModification$27(DataCommands$DataProvider,DataCommands$DataManipulator,DataCommands$DataProvider,CommandContext)
- int lambda$decorateModification$28(DataCommands$DataProvider,DataCommands$DataManipulator,DataCommands$DataProvider,CommandContext)
+ int lambda$decorateModification$29(DataCommands$DataProvider,DataCommands$DataManipulator,DataCommands$DataProvider,CommandContext)
- int lambda$decorateModification$30(DataCommands$DataProvider,DataCommands$DataManipulator,DataCommands$DataProvider,CommandContext)
+ int lambda$decorateModification$31(DataCommands$DataProvider,DataCommands$DataManipulator,DataCommands$DataProvider,CommandContext)
- int lambda$decorateModification$32(DataCommands$DataProvider,DataCommands$DataManipulator,DataCommands$DataProvider,CommandContext)
+ int lambda$decorateModification$33(DataCommands$DataProvider,DataCommands$DataManipulator,DataCommands$DataProvider,CommandContext)
- int lambda$decorateModification$35(DataCommands$DataProvider,DataCommands$DataManipulator,CommandContext)
+ int lambda$decorateModification$36(DataCommands$DataProvider,DataCommands$DataManipulator,CommandContext)
+ int lambda$register$12(DataCommands$DataProvider,CommandContext)
- int lambda$register$13(DataCommands$DataProvider,CommandContext)
+ int lambda$register$14(DataCommands$DataProvider,CommandContext)
- int lambda$register$15(CommandContext,CompoundTag,NbtPathArgument$NbtPath,List)
+ int lambda$register$20(CommandContext,CompoundTag,NbtPathArgument$NbtPath,List)
- int lambda$register$7(DataCommands$DataProvider,CommandContext)
+ int lambda$register$8(DataCommands$DataProvider,CommandContext)
- int lambda$register$9(DataCommands$DataProvider,CommandContext)
- String lambda$decorateModification$25(String)
+ String lambda$decorateModification$26(String)
- String lambda$decorateModification$27(String)
+ String lambda$decorateModification$28(String)
- String lambda$decorateModification$29(CommandContext,String)
+ String lambda$decorateModification$30(CommandContext,String)
- String lambda$decorateModification$31(CommandContext,String)
+ String lambda$decorateModification$32(CommandContext,String)
- void lambda$register$20(ArgumentBuilder,DataCommands$DataManipulatorDecorator)
+ void lambda$register$21(ArgumentBuilder,DataCommands$DataManipulatorDecorator)
```

</details>
<details>
<summary>
net.minecraft.world.entity.Entity
</summary>

```diff
- boolean attemptToShearEquipment(Player,InteractionHand,ItemStack,Mob)
- ItemEntity spawnAtLocation(ServerLevel,ItemStack,Vec3)
+ Level getCommandSenderWorld()
```

</details>
<details>
<summary>
net.minecraft.world.entity.Leashable
</summary>

```diff
- Vec3 getHolderMovement(Entity)
```

</details>
<details>
<summary>
net.minecraft.world.entity.Mob
</summary>

```diff
- boolean canShearEquipment(Player)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.HappyGhast
</summary>

```diff
- Vec3 getLeashOffset()
- void tick()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.sheep.Sheep
</summary>

```diff
+ int createSheepColor(DyeColor)
+ int getColor(DyeColor)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.wolf.Wolf
</summary>

```diff
- boolean canShearEquipment(Player)
```

</details>
<details>
<summary>
net.minecraft.world.entity.player.Player
</summary>

```diff
- void openDialog(Holder)
```

</details>
<details>
<summary>
net.minecraft.world.item.equipment.Equippable
</summary>

```diff
- boolean canBeSheared()
- Holder shearingSound()
- void <init>(EquipmentSlot,Holder,Optional,Optional,Optional,boolean,boolean,boolean,boolean,boolean,Holder)
+ void <init>(EquipmentSlot,Holder,Optional,Optional,Optional,boolean,boolean,boolean,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.DriedGhastBlock
</summary>

```diff
+ boolean canPlaceLiquid(LivingEntity,BlockGetter,BlockPos,BlockState,Fluid)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.SignBlockEntity
</summary>

```diff
+ boolean executeClickCommandsIfPresent(Player,Level,BlockPos,boolean)
- boolean executeClickCommandsIfPresent(ServerLevel,Player,BlockPos,boolean)
+ CommandSourceStack createCommandSourceStack(Player,Level,BlockPos)
- CommandSourceStack createCommandSourceStack(Player,ServerLevel,BlockPos)
```

</details>
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
+ net.minecraft.BlockUtil
- net.minecraft.BlockUtil$FoundRectangle
+ net.minecraft.BlockUtil$IntBounds
- net.minecraft.CharPredicate
+ net.minecraft.ChatFormatting
- net.minecraft.CrashReport
+ net.minecraft.CrashReportCategory
- net.minecraft.CrashReportCategory$Entry
+ net.minecraft.CrashReportDetail
- net.minecraft.DefaultUncaughtExceptionHandler
+ net.minecraft.DefaultUncaughtExceptionHandlerWithName
- net.minecraft.DetectedVersion
+ net.minecraft.FieldsAreNonnullByDefault
- net.minecraft.FileUtil
+ net.minecraft.MethodsReturnNonnullByDefault
- net.minecraft.Optionull
- net.minecraft.ReportedException
+ net.minecraft.ReportType
+ net.minecraft.ResourceLocationException
- net.minecraft.SharedConstants
+ net.minecraft.SuppressForbidden
- net.minecraft.SystemReport
+ net.minecraft.TracingExecutor
- net.minecraft.Util
+ net.minecraft.Util$1
- net.minecraft.Util$10
+ net.minecraft.Util$11
- net.minecraft.Util$2
+ net.minecraft.Util$5
- net.minecraft.Util$6
+ net.minecraft.Util$7
- net.minecraft.Util$8
+ net.minecraft.Util$9
- net.minecraft.Util$OS
+ net.minecraft.Util$OS$1
- net.minecraft.Util$OS$2
+ net.minecraft.WorldVersion
- net.minecraft.WorldVersion$1
+ net.minecraft.WorldVersion$Simple
- XXX.advancements.critereon.AnyBlockInteractionTrigger
+ XXX.advancements.critereon.AnyBlockInteractionTrigger$TriggerInstance
- XXX.advancements.critereon.BeeNestDestroyedTrigger
+ XXX.advancements.critereon.BeeNestDestroyedTrigger$TriggerInstance
- XXX.advancements.critereon.BlockPredicate
+ XXX.advancements.critereon.BlockPredicate$Builder
- XXX.advancements.critereon.BredAnimalsTrigger
+ XXX.advancements.critereon.BredAnimalsTrigger$TriggerInstance
- XXX.advancements.critereon.BrewedPotionTrigger
+ XXX.advancements.critereon.BrewedPotionTrigger$TriggerInstance
- XXX.advancements.critereon.ChangeDimensionTrigger
+ XXX.advancements.critereon.ChangeDimensionTrigger$TriggerInstance
- XXX.advancements.critereon.ChanneledLightningTrigger
+ XXX.advancements.critereon.ChanneledLightningTrigger$TriggerInstance
- XXX.advancements.critereon.CollectionContentsPredicate
+ XXX.advancements.critereon.CollectionContentsPredicate$Multiple
- XXX.advancements.critereon.CollectionContentsPredicate$Single
+ XXX.advancements.critereon.CollectionContentsPredicate$Zero
- XXX.advancements.critereon.CollectionCountsPredicate
+ XXX.advancements.critereon.CollectionCountsPredicate$Entry
- XXX.advancements.critereon.CollectionCountsPredicate$Multiple
+ XXX.advancements.critereon.CollectionCountsPredicate$Single
- XXX.advancements.critereon.CollectionCountsPredicate$Zero
+ XXX.advancements.critereon.CollectionPredicate
- XXX.advancements.critereon.ConstructBeaconTrigger
+ XXX.advancements.critereon.ConstructBeaconTrigger$TriggerInstance
- XXX.advancements.critereon.ConsumeItemTrigger
+ XXX.advancements.critereon.ConsumeItemTrigger$TriggerInstance
- XXX.advancements.critereon.ContextAwarePredicate
+ XXX.advancements.critereon.CriterionValidator
- XXX.advancements.critereon.CuredZombieVillagerTrigger
+ XXX.advancements.critereon.CuredZombieVillagerTrigger$TriggerInstance
- XXX.advancements.critereon.DamagePredicate
+ XXX.advancements.critereon.DamagePredicate$Builder
- XXX.advancements.critereon.DamageSourcePredicate
+ XXX.advancements.critereon.DamageSourcePredicate$Builder
- XXX.advancements.critereon.DataComponentMatchers
+ XXX.advancements.critereon.DataComponentMatchers$Builder
- XXX.advancements.critereon.DefaultBlockInteractionTrigger
+ XXX.advancements.critereon.DefaultBlockInteractionTrigger$TriggerInstance
- XXX.advancements.critereon.DistancePredicate
+ XXX.advancements.critereon.DistanceTrigger
- XXX.advancements.critereon.DistanceTrigger$TriggerInstance
+ XXX.advancements.critereon.EffectsChangedTrigger
- XXX.advancements.critereon.EffectsChangedTrigger$TriggerInstance
+ XXX.advancements.critereon.EnchantedItemTrigger
- XXX.advancements.critereon.EnchantedItemTrigger$TriggerInstance
+ XXX.advancements.critereon.EnchantmentPredicate
- XXX.advancements.critereon.EnterBlockTrigger
+ XXX.advancements.critereon.EnterBlockTrigger$TriggerInstance
- XXX.advancements.critereon.EntityEquipmentPredicate
+ XXX.advancements.critereon.EntityEquipmentPredicate$Builder
- XXX.advancements.critereon.EntityFlagsPredicate
+ XXX.advancements.critereon.EntityFlagsPredicate$Builder
- XXX.advancements.critereon.EntityHurtPlayerTrigger
+ XXX.advancements.critereon.EntityHurtPlayerTrigger$TriggerInstance
- XXX.advancements.critereon.EntityPredicate
+ XXX.advancements.critereon.EntityPredicate$Builder
- XXX.advancements.critereon.EntityPredicate$LocationWrapper
+ XXX.advancements.critereon.EntitySubPredicate
- XXX.advancements.critereon.EntitySubPredicates
+ XXX.advancements.critereon.EntityTypePredicate
- XXX.advancements.critereon.FallAfterExplosionTrigger
+ XXX.advancements.critereon.FallAfterExplosionTrigger$TriggerInstance
- XXX.advancements.critereon.FilledBucketTrigger
+ XXX.advancements.critereon.FilledBucketTrigger$TriggerInstance
- XXX.advancements.critereon.FishingHookPredicate
+ XXX.advancements.critereon.FishingRodHookedTrigger
- XXX.advancements.critereon.FishingRodHookedTrigger$TriggerInstance
+ XXX.advancements.critereon.FluidPredicate
- XXX.advancements.critereon.FluidPredicate$Builder
+ XXX.advancements.critereon.GameTypePredicate
- XXX.advancements.critereon.ImpossibleTrigger
+ XXX.advancements.critereon.ImpossibleTrigger$TriggerInstance
- XXX.advancements.critereon.InputPredicate
+ XXX.advancements.critereon.InventoryChangeTrigger
- XXX.advancements.critereon.InventoryChangeTrigger$TriggerInstance
+ XXX.advancements.critereon.InventoryChangeTrigger$TriggerInstance$Slots
- XXX.advancements.critereon.ItemDurabilityTrigger
+ XXX.advancements.critereon.ItemDurabilityTrigger$TriggerInstance
- XXX.advancements.critereon.ItemPredicate
+ XXX.advancements.critereon.ItemPredicate$Builder
- XXX.advancements.critereon.ItemUsedOnLocationTrigger
+ XXX.advancements.critereon.ItemUsedOnLocationTrigger$TriggerInstance
- XXX.advancements.critereon.KilledByArrowTrigger
+ XXX.advancements.critereon.KilledByArrowTrigger$TriggerInstance
- XXX.advancements.critereon.KilledTrigger
+ XXX.advancements.critereon.KilledTrigger$TriggerInstance
- XXX.advancements.critereon.LevitationTrigger
+ XXX.advancements.critereon.LevitationTrigger$TriggerInstance
- XXX.advancements.critereon.LightningBoltPredicate
+ XXX.advancements.critereon.LightningStrikeTrigger
- XXX.advancements.critereon.LightningStrikeTrigger$TriggerInstance
- XXX.advancements.critereon.LightPredicate
+ XXX.advancements.critereon.LightPredicate$Builder
+ XXX.advancements.critereon.LocationPredicate
- XXX.advancements.critereon.LocationPredicate$Builder
+ XXX.advancements.critereon.LocationPredicate$PositionPredicate
- XXX.advancements.critereon.LootTableTrigger
+ XXX.advancements.critereon.LootTableTrigger$TriggerInstance
- XXX.advancements.critereon.MinMaxBounds
+ XXX.advancements.critereon.MinMaxBounds$1
- XXX.advancements.critereon.MinMaxBounds$BoundsFactory
+ XXX.advancements.critereon.MinMaxBounds$BoundsFromReaderFactory
- XXX.advancements.critereon.MinMaxBounds$Doubles
+ XXX.advancements.critereon.MinMaxBounds$Ints
- XXX.advancements.critereon.MobEffectsPredicate
+ XXX.advancements.critereon.MobEffectsPredicate$Builder
- XXX.advancements.critereon.MobEffectsPredicate$MobEffectInstancePredicate
+ XXX.advancements.critereon.MovementPredicate
- XXX.advancements.critereon.NbtPredicate
- XXX.advancements.critereon.package-info
+ XXX.advancements.critereon.PickedUpItemTrigger
- XXX.advancements.critereon.PickedUpItemTrigger$TriggerInstance
+ XXX.advancements.critereon.PlayerHurtEntityTrigger
- XXX.advancements.critereon.PlayerHurtEntityTrigger$TriggerInstance
+ XXX.advancements.critereon.PlayerInteractTrigger
- XXX.advancements.critereon.PlayerInteractTrigger$TriggerInstance
+ XXX.advancements.critereon.PlayerPredicate
- XXX.advancements.critereon.PlayerPredicate$AdvancementCriterionsPredicate
+ XXX.advancements.critereon.PlayerPredicate$AdvancementDonePredicate
- XXX.advancements.critereon.PlayerPredicate$AdvancementPredicate
+ XXX.advancements.critereon.PlayerPredicate$Builder
- XXX.advancements.critereon.PlayerPredicate$StatMatcher
+ XXX.advancements.critereon.PlayerTrigger
- XXX.advancements.critereon.PlayerTrigger$TriggerInstance
+ XXX.advancements.critereon.RaiderPredicate
- XXX.advancements.critereon.RecipeCraftedTrigger
+ XXX.advancements.critereon.RecipeCraftedTrigger$TriggerInstance
- XXX.advancements.critereon.RecipeUnlockedTrigger
+ XXX.advancements.critereon.RecipeUnlockedTrigger$TriggerInstance
- XXX.advancements.critereon.SheepPredicate
+ XXX.advancements.critereon.ShotCrossbowTrigger
- XXX.advancements.critereon.ShotCrossbowTrigger$TriggerInstance
+ XXX.advancements.critereon.SimpleCriterionTrigger
- XXX.advancements.critereon.SimpleCriterionTrigger$SimpleInstance
+ XXX.advancements.critereon.SingleComponentItemPredicate
- XXX.advancements.critereon.SlideDownBlockTrigger
+ XXX.advancements.critereon.SlideDownBlockTrigger$TriggerInstance
- XXX.advancements.critereon.SlimePredicate
+ XXX.advancements.critereon.SlotsPredicate
- XXX.advancements.critereon.StartRidingTrigger
+ XXX.advancements.critereon.StartRidingTrigger$TriggerInstance
- XXX.advancements.critereon.StatePropertiesPredicate
+ XXX.advancements.critereon.StatePropertiesPredicate$Builder
- XXX.advancements.critereon.StatePropertiesPredicate$ExactMatcher
+ XXX.advancements.critereon.StatePropertiesPredicate$PropertyMatcher
- XXX.advancements.critereon.StatePropertiesPredicate$RangedMatcher
+ XXX.advancements.critereon.StatePropertiesPredicate$ValueMatcher
- XXX.advancements.critereon.SummonedEntityTrigger
+ XXX.advancements.critereon.SummonedEntityTrigger$TriggerInstance
- XXX.advancements.critereon.TagPredicate
+ XXX.advancements.critereon.TameAnimalTrigger
- XXX.advancements.critereon.TameAnimalTrigger$TriggerInstance
+ XXX.advancements.critereon.TargetBlockTrigger
- XXX.advancements.critereon.TargetBlockTrigger$TriggerInstance
+ XXX.advancements.critereon.TradeTrigger
- XXX.advancements.critereon.TradeTrigger$TriggerInstance
+ XXX.advancements.critereon.UsedEnderEyeTrigger
- XXX.advancements.critereon.UsedEnderEyeTrigger$TriggerInstance
+ XXX.advancements.critereon.UsedTotemTrigger
- XXX.advancements.critereon.UsedTotemTrigger$TriggerInstance
+ XXX.advancements.critereon.UsingItemTrigger
- XXX.advancements.critereon.UsingItemTrigger$TriggerInstance
+ XXX.advancements.critereon.WrappedMinMaxBounds
- XXX.animation.definitions.ArmadilloAnimation
+ XXX.animation.definitions.BatAnimation
- XXX.animation.definitions.BreezeAnimation
+ XXX.animation.definitions.CamelAnimation
- XXX.animation.definitions.CreakingAnimation
+ XXX.animation.definitions.FrogAnimation
- XXX.animation.definitions.package-info
- XXX.animation.definitions.SnifferAnimation
+ XXX.animation.definitions.WardenAnimation
- XXX.atlas.sources.DirectoryLister
+ XXX.atlas.sources.LazyLoadedImage
+ XXX.atlas.sources.package-info
- XXX.atlas.sources.PalettedPermutations
+ XXX.atlas.sources.PalettedPermutations$PalettedSpriteSupplier
- XXX.atlas.sources.SingleFile
+ XXX.atlas.sources.SourceFilter
- XXX.atlas.sources.Unstitcher
+ XXX.atlas.sources.Unstitcher$Region
- XXX.atlas.sources.Unstitcher$RegionInstance
- XXX.block.model.BakedQuad
+ XXX.block.model.BlockElement
- XXX.block.model.BlockElement$Deserializer
+ XXX.block.model.BlockElementFace
- XXX.block.model.BlockElementFace$Deserializer
+ XXX.block.model.BlockElementFace$UVs
- XXX.block.model.BlockElementRotation
+ XXX.block.model.BlockModel
- XXX.block.model.BlockModel$Deserializer
+ XXX.block.model.BlockModelDefinition
- XXX.block.model.BlockModelDefinition$MultiPartDefinition
+ XXX.block.model.BlockModelDefinition$SimpleModelSelectors
- XXX.block.model.BlockModelPart
+ XXX.block.model.BlockModelPart$Unbaked
- XXX.block.model.BlockStateModel
+ XXX.block.model.BlockStateModel$SimpleCachedUnbakedRoot
- XXX.block.model.BlockStateModel$SimpleCachedUnbakedRoot$1
+ XXX.block.model.BlockStateModel$Unbaked
- XXX.block.model.BlockStateModel$UnbakedRoot
+ XXX.block.model.FaceBakery
- XXX.block.model.FaceBakery$1
+ XXX.block.model.ItemModelGenerator
- XXX.block.model.ItemModelGenerator$Span
+ XXX.block.model.ItemModelGenerator$SpanFacing
- XXX.block.model.ItemTransform
+ XXX.block.model.ItemTransform$Deserializer
- XXX.block.model.ItemTransforms
+ XXX.block.model.ItemTransforms$1
- XXX.block.model.ItemTransforms$Deserializer
+ XXX.block.model.package-info
+ XXX.block.model.SimpleModelWrapper
- XXX.block.model.SimpleUnbakedGeometry
+ XXX.block.model.SingleVariant
- XXX.block.model.SingleVariant$Unbaked
+ XXX.block.model.TextureSlots
- XXX.block.model.TextureSlots$Data
+ XXX.block.model.TextureSlots$Data$Builder
- XXX.block.model.TextureSlots$Reference
+ XXX.block.model.TextureSlots$Resolver
- XXX.block.model.TextureSlots$SlotContents
+ XXX.block.model.TextureSlots$Value
- XXX.block.model.Variant
+ XXX.block.model.Variant$SimpleModelState
- XXX.block.model.VariantMutator
+ XXX.block.model.VariantMutator$VariantProperty
- XXX.block.model.VariantSelector
- XXX.chat.contents.BlockDataSource
+ XXX.chat.contents.DataSource
- XXX.chat.contents.DataSource$Type
+ XXX.chat.contents.EntityDataSource
- XXX.chat.contents.KeybindContents
+ XXX.chat.contents.KeybindResolver
- XXX.chat.contents.NbtContents
+ XXX.chat.contents.package-info
+ XXX.chat.contents.PlainTextContents
- XXX.chat.contents.PlainTextContents$1
+ XXX.chat.contents.PlainTextContents$LiteralContents
- XXX.chat.contents.ScoreContents
+ XXX.chat.contents.SelectorContents
- XXX.chat.contents.StorageDataSource
+ XXX.chat.contents.TranslatableContents
- XXX.chat.contents.TranslatableFormatException
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
- XXX.chat.report.AbuseReportSender
+ XXX.chat.report.AbuseReportSender$1
- XXX.chat.report.AbuseReportSender$SendException
+ XXX.chat.report.AbuseReportSender$Services
- XXX.chat.report.BanReason
+ XXX.chat.report.ChatReport
- XXX.chat.report.ChatReport$Builder
+ XXX.chat.report.ChatReportContextBuilder
- XXX.chat.report.ChatReportContextBuilder$Collector
+ XXX.chat.report.ChatReportContextBuilder$Handler
- XXX.chat.report.NameReport
+ XXX.chat.report.NameReport$Builder
- XXX.chat.report.package-info
- XXX.chat.report.Report
+ XXX.chat.report.Report$Builder
- XXX.chat.report.Report$CannotBuildReason
+ XXX.chat.report.Report$Result
- XXX.chat.report.ReportEnvironment
+ XXX.chat.report.ReportEnvironment$Server
- XXX.chat.report.ReportEnvironment$Server$Realm
+ XXX.chat.report.ReportEnvironment$Server$ThirdParty
+ XXX.chat.report.ReportingContext
- XXX.chat.report.ReportReason
+ XXX.chat.report.ReportReason$1
- XXX.chat.report.ReportType
- XXX.chat.report.SkinReport
+ XXX.chat.report.SkinReport$Builder
+ XXX.client.animation.AnimationChannel
- XXX.client.animation.AnimationChannel$Interpolation
+ XXX.client.animation.AnimationChannel$Interpolations
- XXX.client.animation.AnimationChannel$Target
+ XXX.client.animation.AnimationChannel$Targets
- XXX.client.animation.AnimationDefinition
+ XXX.client.animation.AnimationDefinition$Builder
- XXX.client.animation.Keyframe
+ XXX.client.animation.KeyframeAnimations
+ XXX.client.animation.package-info
- XXX.client.color.ColorLerper
+ XXX.client.data.AtlasProvider
- XXX.client.data.Main
+ XXX.client.data.package-info
- XXX.client.gui.BundleMouseActions
+ XXX.client.gui.ComponentPath
- XXX.client.gui.ComponentPath$Leaf
+ XXX.client.gui.ComponentPath$Path
- XXX.client.gui.Font
+ XXX.client.gui.Font$DisplayMode
- XXX.client.gui.Font$GlyphVisitor
- XXX.client.gui.Font$PreparedText
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
- XXX.client.model.BlazeModel
+ XXX.client.model.BoatModel
- XXX.client.model.BoggedModel
+ XXX.client.model.BookModel
- XXX.client.model.BreezeModel
+ XXX.client.model.CamelModel
- XXX.client.model.CamelSaddleModel
+ XXX.client.model.CatModel
- XXX.client.model.ChestModel
+ XXX.client.model.ChickenModel
- XXX.client.model.CodModel
+ XXX.client.model.ColdChickenModel
- XXX.client.model.ColdCowModel
+ XXX.client.model.ColdPigModel
- XXX.client.model.CowModel
+ XXX.client.model.CreakingModel
- XXX.client.model.CreeperModel
+ XXX.client.model.DolphinModel
- XXX.client.model.DonkeyModel
+ XXX.client.model.DrownedModel
- XXX.client.model.ElytraModel
+ XXX.client.model.EndCrystalModel
- XXX.client.model.EndermanModel
+ XXX.client.model.EndermiteModel
- XXX.client.model.EntityModel
+ XXX.client.model.EquineSaddleModel
- XXX.client.model.EvokerFangsModel
+ XXX.client.model.FelineModel
- XXX.client.model.FoxModel
+ XXX.client.model.FrogModel
- XXX.client.model.GhastModel
+ XXX.client.model.GiantZombieModel
- XXX.client.model.GoatModel
+ XXX.client.model.GuardianModel
- XXX.client.model.HappyGhastHarnessModel
+ XXX.client.model.HappyGhastModel
- XXX.client.model.HeadedModel
+ XXX.client.model.HoglinModel
- XXX.client.model.HorseModel
+ XXX.client.model.HumanoidArmorModel
- XXX.client.model.HumanoidModel
+ XXX.client.model.HumanoidModel$ArmPose
- XXX.client.model.IllagerModel
+ XXX.client.model.IronGolemModel
- XXX.client.model.LavaSlimeModel
+ XXX.client.model.LeashKnotModel
- XXX.client.model.LlamaModel
+ XXX.client.model.LlamaSpitModel
- XXX.client.model.MinecartModel
+ XXX.client.model.Model
- XXX.client.model.Model$Simple
+ XXX.client.model.OcelotModel
+ XXX.client.model.package-info
- XXX.client.model.PandaModel
+ XXX.client.model.ParrotModel
- XXX.client.model.ParrotModel$Pose
+ XXX.client.model.PhantomModel
+ XXX.client.model.PiglinHeadModel
- XXX.client.model.PiglinModel
- XXX.client.model.PigModel
+ XXX.client.model.PlayerCapeModel
- XXX.client.model.PlayerEarsModel
+ XXX.client.model.PlayerModel
- XXX.client.model.PolarBearModel
+ XXX.client.model.PufferfishBigModel
- XXX.client.model.PufferfishMidModel
+ XXX.client.model.PufferfishSmallModel
- XXX.client.model.QuadrupedModel
+ XXX.client.model.RabbitModel
- XXX.client.model.RaftModel
+ XXX.client.model.RavagerModel
- XXX.client.model.SalmonModel
+ XXX.client.model.SheepFurModel
- XXX.client.model.SheepModel
+ XXX.client.model.ShieldModel
- XXX.client.model.ShulkerBulletModel
+ XXX.client.model.ShulkerModel
- XXX.client.model.SilverfishModel
+ XXX.client.model.SkeletonModel
- XXX.client.model.SkullModel
+ XXX.client.model.SkullModelBase
- XXX.client.model.SlimeModel
+ XXX.client.model.SnifferModel
- XXX.client.model.SnowGolemModel
+ XXX.client.model.SpiderModel
- XXX.client.model.SpinAttackEffectModel
+ XXX.client.model.SquidModel
- XXX.client.model.StriderModel
+ XXX.client.model.TadpoleModel
- XXX.client.model.TridentModel
+ XXX.client.model.TropicalFishModelA
- XXX.client.model.TropicalFishModelB
+ XXX.client.model.TurtleModel
- XXX.client.model.VexModel
+ XXX.client.model.VillagerLikeModel
- XXX.client.model.VillagerModel
+ XXX.client.model.WardenModel
- XXX.client.model.WarmCowModel
+ XXX.client.model.WindChargeModel
- XXX.client.model.WitchModel
+ XXX.client.model.WitherBossModel
- XXX.client.model.WolfModel
+ XXX.client.model.ZombieModel
- XXX.client.model.ZombieVillagerModel
+ XXX.client.model.ZombifiedPiglinModel
- XXX.client.multiplayer.AccountProfileKeyPairManager
+ XXX.client.multiplayer.CacheSlot
- XXX.client.multiplayer.CacheSlot$Cleaner
+ XXX.client.multiplayer.ChunkBatchSizeCalculator
- XXX.client.multiplayer.ClientAdvancements
+ XXX.client.multiplayer.ClientAdvancements$Listener
- XXX.client.multiplayer.ClientChunkCache
+ XXX.client.multiplayer.ClientChunkCache$Storage
- XXX.client.multiplayer.ClientCommonPacketListenerImpl
+ XXX.client.multiplayer.ClientCommonPacketListenerImpl$DeferredPacket
- XXX.client.multiplayer.ClientCommonPacketListenerImpl$PackConfirmScreen
+ XXX.client.multiplayer.ClientCommonPacketListenerImpl$PackConfirmScreen$PendingRequest
- XXX.client.multiplayer.ClientConfigurationPacketListenerImpl
+ XXX.client.multiplayer.ClientConfigurationPacketListenerImpl$1
- XXX.client.multiplayer.ClientHandshakePacketListenerImpl
+ XXX.client.multiplayer.ClientHandshakePacketListenerImpl$State
- XXX.client.multiplayer.ClientLevel
+ XXX.client.multiplayer.ClientLevel$1
- XXX.client.multiplayer.ClientLevel$ClientLevelData
+ XXX.client.multiplayer.ClientLevel$EntityCallbacks
- XXX.client.multiplayer.ClientPacketListener
+ XXX.client.multiplayer.ClientPacketListener$1
- XXX.client.multiplayer.ClientPacketListener$2
- XXX.client.multiplayer.ClientRecipeContainer
+ XXX.client.multiplayer.ClientRegistryLayer
- XXX.client.multiplayer.ClientSuggestionProvider
+ XXX.client.multiplayer.ClientSuggestionProvider$1
- XXX.client.multiplayer.CommonListenerCookie
+ XXX.client.multiplayer.DebugSampleSubscriber
- XXX.client.multiplayer.KnownPacksManager
+ XXX.client.multiplayer.LegacyServerPinger
- XXX.client.multiplayer.LegacyServerPinger$Output
+ XXX.client.multiplayer.LevelLoadStatusManager
- XXX.client.multiplayer.LevelLoadStatusManager$Status
+ XXX.client.multiplayer.MultiPlayerGameMode
+ XXX.client.multiplayer.package-info
- XXX.client.multiplayer.PingDebugMonitor
+ XXX.client.multiplayer.PlayerInfo
- XXX.client.multiplayer.ProfileKeyPairManager
+ XXX.client.multiplayer.ProfileKeyPairManager$1
- XXX.client.multiplayer.RegistryDataCollector
+ XXX.client.multiplayer.RegistryDataCollector$ContentsCollector
- XXX.client.multiplayer.RegistryDataCollector$TagCollector
+ XXX.client.multiplayer.ServerData
- XXX.client.multiplayer.ServerData$ServerPackStatus
+ XXX.client.multiplayer.ServerData$State
- XXX.client.multiplayer.ServerData$Type
+ XXX.client.multiplayer.ServerList
- XXX.client.multiplayer.ServerStatusPinger
+ XXX.client.multiplayer.ServerStatusPinger$1
- XXX.client.multiplayer.ServerStatusPinger$2
+ XXX.client.multiplayer.SessionSearchTrees
- XXX.client.multiplayer.SessionSearchTrees$Key
+ XXX.client.multiplayer.TransferState
- XXX.client.particle.AshParticle
+ XXX.client.particle.AshParticle$Provider
- XXX.client.particle.AttackSweepParticle
+ XXX.client.particle.AttackSweepParticle$Provider
- XXX.client.particle.BaseAshSmokeParticle
+ XXX.client.particle.BlockMarker
- XXX.client.particle.BlockMarker$Provider
+ XXX.client.particle.BreakingItemParticle
- XXX.client.particle.BreakingItemParticle$CobwebProvider
+ XXX.client.particle.BreakingItemParticle$ItemParticleProvider
- XXX.client.particle.BreakingItemParticle$Provider
+ XXX.client.particle.BreakingItemParticle$SlimeProvider
- XXX.client.particle.BreakingItemParticle$SnowballProvider
+ XXX.client.particle.BubbleColumnUpParticle
- XXX.client.particle.BubbleColumnUpParticle$Provider
+ XXX.client.particle.BubbleParticle
- XXX.client.particle.BubbleParticle$Provider
+ XXX.client.particle.BubblePopParticle
- XXX.client.particle.BubblePopParticle$Provider
+ XXX.client.particle.CampfireSmokeParticle
- XXX.client.particle.CampfireSmokeParticle$CosyProvider
+ XXX.client.particle.CampfireSmokeParticle$SignalProvider
- XXX.client.particle.CritParticle
+ XXX.client.particle.CritParticle$DamageIndicatorProvider
- XXX.client.particle.CritParticle$MagicProvider
+ XXX.client.particle.CritParticle$Provider
- XXX.client.particle.DragonBreathParticle
+ XXX.client.particle.DragonBreathParticle$Provider
- XXX.client.particle.DripParticle
+ XXX.client.particle.DripParticle$CoolingDripHangParticle
- XXX.client.particle.DripParticle$DripHangParticle
+ XXX.client.particle.DripParticle$DripLandParticle
- XXX.client.particle.DripParticle$DripstoneFallAndLandParticle
+ XXX.client.particle.DripParticle$FallAndLandParticle
- XXX.client.particle.DripParticle$FallingParticle
+ XXX.client.particle.DripParticle$HoneyFallAndLandParticle
- XXX.client.particle.DustColorTransitionParticle
+ XXX.client.particle.DustColorTransitionParticle$Provider
- XXX.client.particle.DustParticle
+ XXX.client.particle.DustParticle$Provider
- XXX.client.particle.DustParticleBase
+ XXX.client.particle.DustPlumeParticle
- XXX.client.particle.DustPlumeParticle$Provider
+ XXX.client.particle.EndRodParticle
- XXX.client.particle.EndRodParticle$Provider
+ XXX.client.particle.ExplodeParticle
- XXX.client.particle.ExplodeParticle$Provider
+ XXX.client.particle.FallingDustParticle
- XXX.client.particle.FallingDustParticle$Provider
+ XXX.client.particle.FallingLeavesParticle
- XXX.client.particle.FallingLeavesParticle$CherryProvider
+ XXX.client.particle.FallingLeavesParticle$PaleOakProvider
- XXX.client.particle.FallingLeavesParticle$TintedLeavesProvider
+ XXX.client.particle.FireflyParticle
- XXX.client.particle.FireflyParticle$FireflyProvider
+ XXX.client.particle.FireworkParticles
- XXX.client.particle.FireworkParticles$1
+ XXX.client.particle.FireworkParticles$FlashProvider
- XXX.client.particle.FireworkParticles$OverlayParticle
+ XXX.client.particle.FireworkParticles$SparkParticle
- XXX.client.particle.FireworkParticles$SparkProvider
+ XXX.client.particle.FireworkParticles$Starter
- XXX.client.particle.FlameParticle
+ XXX.client.particle.FlameParticle$Provider
- XXX.client.particle.FlameParticle$SmallFlameProvider
+ XXX.client.particle.FlyStraightTowardsParticle
- XXX.client.particle.FlyStraightTowardsParticle$OminousSpawnProvider
+ XXX.client.particle.FlyTowardsPositionParticle
- XXX.client.particle.FlyTowardsPositionParticle$EnchantProvider
+ XXX.client.particle.FlyTowardsPositionParticle$NautilusProvider
- XXX.client.particle.FlyTowardsPositionParticle$VaultConnectionProvider
+ XXX.client.particle.GlowParticle
- XXX.client.particle.GlowParticle$ElectricSparkProvider
+ XXX.client.particle.GlowParticle$GlowSquidProvider
- XXX.client.particle.GlowParticle$ScrapeProvider
+ XXX.client.particle.GlowParticle$WaxOffProvider
- XXX.client.particle.GlowParticle$WaxOnProvider
+ XXX.client.particle.GustParticle
- XXX.client.particle.GustParticle$Provider
+ XXX.client.particle.GustParticle$SmallProvider
- XXX.client.particle.GustSeedParticle
+ XXX.client.particle.GustSeedParticle$Provider
- XXX.client.particle.HeartParticle
+ XXX.client.particle.HeartParticle$AngryVillagerProvider
- XXX.client.particle.HeartParticle$Provider
+ XXX.client.particle.HugeExplosionParticle
- XXX.client.particle.HugeExplosionParticle$Provider
+ XXX.client.particle.HugeExplosionSeedParticle
- XXX.client.particle.HugeExplosionSeedParticle$Provider
+ XXX.client.particle.ItemPickupParticle
- XXX.client.particle.LargeSmokeParticle
+ XXX.client.particle.LargeSmokeParticle$Provider
- XXX.client.particle.LavaParticle
+ XXX.client.particle.LavaParticle$Provider
- XXX.client.particle.MobAppearanceParticle
+ XXX.client.particle.MobAppearanceParticle$Provider
- XXX.client.particle.NoRenderParticle
+ XXX.client.particle.NoteParticle
- XXX.client.particle.NoteParticle$Provider
- XXX.client.particle.package-info
+ XXX.client.particle.Particle
- XXX.client.particle.Particle$LifetimeAlpha
+ XXX.client.particle.ParticleDescription
- XXX.client.particle.ParticleEngine
+ XXX.client.particle.ParticleEngine$1ParticleDefinition
- XXX.client.particle.ParticleEngine$MutableSpriteSet
+ XXX.client.particle.ParticleEngine$SpriteParticleRegistration
- XXX.client.particle.ParticleProvider
+ XXX.client.particle.ParticleProvider$Sprite
- XXX.client.particle.ParticleRenderType
+ XXX.client.particle.PlayerCloudParticle
- XXX.client.particle.PlayerCloudParticle$Provider
+ XXX.client.particle.PlayerCloudParticle$SneezeProvider
- XXX.client.particle.PortalParticle
+ XXX.client.particle.PortalParticle$Provider
- XXX.client.particle.ReversePortalParticle
+ XXX.client.particle.ReversePortalParticle$ReversePortalProvider
- XXX.client.particle.RisingParticle
+ XXX.client.particle.SculkChargeParticle
- XXX.client.particle.SculkChargeParticle$Provider
+ XXX.client.particle.SculkChargePopParticle
- XXX.client.particle.SculkChargePopParticle$Provider
+ XXX.client.particle.ShriekParticle
- XXX.client.particle.ShriekParticle$Provider
+ XXX.client.particle.SimpleAnimatedParticle
- XXX.client.particle.SingleQuadParticle
+ XXX.client.particle.SingleQuadParticle$FacingCameraMode
- XXX.client.particle.SmokeParticle
+ XXX.client.particle.SmokeParticle$Provider
- XXX.client.particle.SnowflakeParticle
+ XXX.client.particle.SnowflakeParticle$Provider
- XXX.client.particle.SonicBoomParticle
+ XXX.client.particle.SonicBoomParticle$Provider
- XXX.client.particle.SoulParticle
+ XXX.client.particle.SoulParticle$EmissiveProvider
- XXX.client.particle.SoulParticle$Provider
+ XXX.client.particle.SpellParticle
- XXX.client.particle.SpellParticle$InstantProvider
+ XXX.client.particle.SpellParticle$MobEffectProvider
- XXX.client.particle.SpellParticle$Provider
+ XXX.client.particle.SpellParticle$WitchProvider
- XXX.client.particle.SpitParticle
+ XXX.client.particle.SpitParticle$Provider
- XXX.client.particle.SplashParticle
+ XXX.client.particle.SplashParticle$Provider
- XXX.client.particle.SpriteSet
+ XXX.client.particle.SquidInkParticle
- XXX.client.particle.SquidInkParticle$GlowInkProvider
+ XXX.client.particle.SquidInkParticle$Provider
- XXX.client.particle.SuspendedParticle
+ XXX.client.particle.SuspendedParticle$CrimsonSporeProvider
- XXX.client.particle.SuspendedParticle$SporeBlossomAirProvider
+ XXX.client.particle.SuspendedParticle$SporeBlossomAirProvider$1
- XXX.client.particle.SuspendedParticle$UnderwaterProvider
+ XXX.client.particle.SuspendedParticle$WarpedSporeProvider
- XXX.client.particle.SuspendedTownParticle
+ XXX.client.particle.SuspendedTownParticle$ComposterFillProvider
- XXX.client.particle.SuspendedTownParticle$DolphinSpeedProvider
+ XXX.client.particle.SuspendedTownParticle$EggCrackProvider
- XXX.client.particle.SuspendedTownParticle$HappyVillagerProvider
+ XXX.client.particle.SuspendedTownParticle$Provider
- XXX.client.particle.TerrainParticle
+ XXX.client.particle.TerrainParticle$CrumblingProvider
- XXX.client.particle.TerrainParticle$DustPillarProvider
+ XXX.client.particle.TerrainParticle$Provider
- XXX.client.particle.TextureSheetParticle
+ XXX.client.particle.TotemParticle
- XXX.client.particle.TotemParticle$Provider
+ XXX.client.particle.TrackingEmitter
- XXX.client.particle.TrailParticle
+ XXX.client.particle.TrailParticle$Provider
- XXX.client.particle.TrialSpawnerDetectionParticle
+ XXX.client.particle.TrialSpawnerDetectionParticle$Provider
- XXX.client.particle.VibrationSignalParticle
+ XXX.client.particle.VibrationSignalParticle$Provider
- XXX.client.particle.WakeParticle
+ XXX.client.particle.WakeParticle$Provider
- XXX.client.particle.WaterCurrentDownParticle
+ XXX.client.particle.WaterCurrentDownParticle$Provider
- XXX.client.particle.WaterDropParticle
+ XXX.client.particle.WaterDropParticle$Provider
- XXX.client.particle.WhiteAshParticle
+ XXX.client.particle.WhiteAshParticle$Provider
- XXX.client.particle.WhiteSmokeParticle
+ XXX.client.particle.WhiteSmokeParticle$Provider
+ XXX.client.player.AbstractClientPlayer
- XXX.client.player.ClientInput
+ XXX.client.player.KeyboardInput
- XXX.client.player.LocalPlayer
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
- XXX.client.renderer.FaceInfo
+ XXX.client.renderer.FaceInfo$Constants
- XXX.client.renderer.FaceInfo$VertexInfo
+ XXX.client.renderer.GameRenderer
- XXX.client.renderer.GlobalSettingsUniform
+ XXX.client.renderer.GpuWarnlistManager
- XXX.client.renderer.GpuWarnlistManager$Preparations
+ XXX.client.renderer.ItemBlockRenderTypes
- XXX.client.renderer.ItemInHandRenderer
+ XXX.client.renderer.ItemInHandRenderer$1
- XXX.client.renderer.ItemInHandRenderer$HandRenderSelection
+ XXX.client.renderer.LevelEventHandler
- XXX.client.renderer.LevelRenderer
+ XXX.client.renderer.LevelRenderer$1
- XXX.client.renderer.LevelRenderer$BrightnessGetter
+ XXX.client.renderer.LevelTargetBundle
- XXX.client.renderer.LightTexture
- XXX.client.renderer.MappableRingBuffer
+ XXX.client.renderer.MapRenderer
+ XXX.client.renderer.MaterialMapper
- XXX.client.renderer.MultiBufferSource
+ XXX.client.renderer.MultiBufferSource$BufferSource
- XXX.client.renderer.Octree
+ XXX.client.renderer.Octree$AxisSorting
- XXX.client.renderer.Octree$Branch
+ XXX.client.renderer.Octree$Leaf
- XXX.client.renderer.Octree$Node
+ XXX.client.renderer.Octree$OctreeVisitor
- XXX.client.renderer.OutlineBufferSource
+ XXX.client.renderer.OutlineBufferSource$EntityOutlineGenerator
+ XXX.client.renderer.package-info
- XXX.client.renderer.PanoramaRenderer
+ XXX.client.renderer.PerspectiveProjectionMatrixBuffer
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
+ XXX.client.renderer.Rect2i
- XXX.client.renderer.RenderBuffers
+ XXX.client.renderer.RenderPipelines
- XXX.client.renderer.RenderStateShard
+ XXX.client.renderer.RenderStateShard$BooleanStateShard
- XXX.client.renderer.RenderStateShard$EmptyTextureStateShard
+ XXX.client.renderer.RenderStateShard$LayeringStateShard
- XXX.client.renderer.RenderStateShard$LightmapStateShard
+ XXX.client.renderer.RenderStateShard$LineStateShard
- XXX.client.renderer.RenderStateShard$MultiTextureStateShard
+ XXX.client.renderer.RenderStateShard$MultiTextureStateShard$Builder
- XXX.client.renderer.RenderStateShard$MultiTextureStateShard$Entry
+ XXX.client.renderer.RenderStateShard$OffsetTexturingStateShard
- XXX.client.renderer.RenderStateShard$OutputStateShard
+ XXX.client.renderer.RenderStateShard$OverlayStateShard
- XXX.client.renderer.RenderStateShard$TextureStateShard
+ XXX.client.renderer.RenderStateShard$TexturingStateShard
- XXX.client.renderer.RenderType
+ XXX.client.renderer.RenderType$CompositeRenderType
- XXX.client.renderer.RenderType$CompositeState
+ XXX.client.renderer.RenderType$CompositeState$CompositeStateBuilder
- XXX.client.renderer.RenderType$OutlineProperty
+ XXX.client.renderer.RunningTrimmedMean
- XXX.client.renderer.ScreenEffectRenderer
+ XXX.client.renderer.SectionBufferBuilderPack
- XXX.client.renderer.SectionBufferBuilderPool
+ XXX.client.renderer.SectionOcclusionGraph
- XXX.client.renderer.SectionOcclusionGraph$GraphEvents
+ XXX.client.renderer.SectionOcclusionGraph$GraphState
- XXX.client.renderer.SectionOcclusionGraph$GraphStorage
+ XXX.client.renderer.SectionOcclusionGraph$Node
- XXX.client.renderer.SectionOcclusionGraph$SectionToNodeMap
+ XXX.client.renderer.ShaderDefines
- XXX.client.renderer.ShaderDefines$Builder
+ XXX.client.renderer.ShaderManager
- XXX.client.renderer.ShaderManager$1
+ XXX.client.renderer.ShaderManager$CompilationCache
- XXX.client.renderer.ShaderManager$CompilationException
+ XXX.client.renderer.ShaderManager$Configs
- XXX.client.renderer.ShaderManager$ShaderSourceKey
+ XXX.client.renderer.ShapeRenderer
- XXX.client.renderer.ShapeRenderer$1
+ XXX.client.renderer.Sheets
- XXX.client.renderer.Sheets$1
+ XXX.client.renderer.SkyRenderer
- XXX.client.renderer.SpecialBlockModelRenderer
+ XXX.client.renderer.SpriteCoordinateExpander
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
+ XXX.client.resources.ClientPackSource
- XXX.client.resources.DefaultPlayerSkin
+ XXX.client.resources.DryFoliageColorReloadListener
- XXX.client.resources.FoliageColorReloadListener
+ XXX.client.resources.GrassColorReloadListener
- XXX.client.resources.IndexedAssetSource
+ XXX.client.resources.LegacyStuffWrapper
- XXX.client.resources.MapDecorationTextureManager
+ XXX.client.resources.MapTextureManager
- XXX.client.resources.MapTextureManager$MapInstance
+ XXX.client.resources.package-info
+ XXX.client.resources.PaintingTextureManager
- XXX.client.resources.PlayerSkin
+ XXX.client.resources.PlayerSkin$Model
- XXX.client.resources.SkinManager
+ XXX.client.resources.SkinManager$1
- XXX.client.resources.SkinManager$2
+ XXX.client.resources.SkinManager$CacheKey
- XXX.client.resources.SkinManager$TextureCache
+ XXX.client.resources.SplashManager
- XXX.client.resources.TextureAtlasHolder
+ XXX.client.resources.WaypointStyle
- XXX.client.resources.WaypointStyleManager
+ XXX.client.searchtree.FullTextSearchTree
- XXX.client.searchtree.IdSearchTree
+ XXX.client.searchtree.IntersectionIterator
- XXX.client.searchtree.MergingUniqueIterator
- XXX.client.searchtree.package-info
+ XXX.client.searchtree.ResourceLocationSearchTree
- XXX.client.searchtree.ResourceLocationSearchTree$1
+ XXX.client.searchtree.ResourceLocationSearchTree$2
- XXX.client.searchtree.SearchTree
+ XXX.client.searchtree.SuffixArray
+ XXX.client.server.IntegratedPlayerList
- XXX.client.server.IntegratedServer
+ XXX.client.server.LanServer
- XXX.client.server.LanServerDetection
+ XXX.client.server.LanServerDetection$LanServerDetector
- XXX.client.server.LanServerDetection$LanServerList
+ XXX.client.server.LanServerPinger
- XXX.client.server.package-info
+ XXX.client.sounds.AudioStream
- XXX.client.sounds.ChannelAccess
+ XXX.client.sounds.ChannelAccess$ChannelHandle
- XXX.client.sounds.ChunkedSampleByteBuf
+ XXX.client.sounds.FiniteAudioStream
- XXX.client.sounds.FloatSampleSource
+ XXX.client.sounds.JOrbisAudioStream
- XXX.client.sounds.LoopingAudioStream
+ XXX.client.sounds.LoopingAudioStream$AudioStreamProvider
- XXX.client.sounds.LoopingAudioStream$NoCloseBuffer
+ XXX.client.sounds.MusicInfo
- XXX.client.sounds.MusicManager
- XXX.color.block.BlockColor
+ XXX.color.block.BlockColors
- XXX.color.block.BlockTintCache
+ XXX.color.block.BlockTintCache$CacheData
- XXX.color.block.BlockTintCache$LatestCacheInfo
+ XXX.color.block.package-info
- XXX.color.item.Constant
+ XXX.color.item.CustomModelDataSource
- XXX.color.item.Dye
+ XXX.color.item.Firework
- XXX.color.item.GrassColorSource
+ XXX.color.item.ItemTintSource
- XXX.color.item.ItemTintSources
+ XXX.color.item.MapColor
- XXX.color.item.package-info
- XXX.color.item.Potion
+ XXX.color.item.TeamColor
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
- XXX.components.debugchart.AbstractDebugChart
+ XXX.components.debugchart.BandwidthDebugChart
- XXX.components.debugchart.FpsDebugChart
+ XXX.components.debugchart.PingDebugChart
- XXX.components.debugchart.ProfilerPieChart
+ XXX.components.debugchart.TpsDebugChart
- XXX.components.events.AbstractContainerEventHandler
+ XXX.components.events.ContainerEventHandler
- XXX.components.events.GuiEventListener
+ XXX.components.events.package-info
- XXX.components.spectator.package-info
+ XXX.components.spectator.SpectatorGui
+ XXX.components.tabs.GridLayoutTab
- XXX.components.tabs.package-info
- XXX.components.tabs.Tab
+ XXX.components.tabs.TabManager
- XXX.components.tabs.TabNavigationBar
+ XXX.components.tabs.TabNavigationBar$Builder
+ XXX.components.toasts.AdvancementToast
- XXX.components.toasts.NowPlayingToast
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
+ XXX.datafix.fixes.ItemRemoveBlockEntityTagFix
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
- XXX.datafix.fixes.LevelDataGeneratorOptionsFix
+ XXX.datafix.fixes.LevelFlatGeneratorInfoFix
- XXX.datafix.fixes.LevelLegacyWorldGenSettingsFix
+ XXX.datafix.fixes.LevelUUIDFix
- XXX.datafix.fixes.LockComponentPredicateFix
+ XXX.datafix.fixes.LodestoneCompassComponentFix
- XXX.datafix.fixes.MapBannerBlockPosFormatFix
+ XXX.datafix.fixes.MapIdFix
- XXX.datafix.fixes.MemoryExpiryDataFix
+ XXX.datafix.fixes.MissingDimensionFix
- XXX.datafix.fixes.MobEffectIdFix
+ XXX.datafix.fixes.MobSpawnerEntityIdentifiersFix
- XXX.datafix.fixes.NamedEntityConvertUncheckedFix
+ XXX.datafix.fixes.NamedEntityFix
- XXX.datafix.fixes.NamedEntityWriteReadFix
+ XXX.datafix.fixes.NamespacedTypeRenameFix
- XXX.datafix.fixes.NewVillageFix
+ XXX.datafix.fixes.ObjectiveRenderTypeFix
- XXX.datafix.fixes.OminousBannerBlockEntityRenameFix
+ XXX.datafix.fixes.OminousBannerRarityFix
- XXX.datafix.fixes.OminousBannerRenameFix
+ XXX.datafix.fixes.OptionsAccessibilityOnboardFix
- XXX.datafix.fixes.OptionsAddTextBackgroundFix
+ XXX.datafix.fixes.OptionsAmbientOcclusionFix
- XXX.datafix.fixes.OptionsForceVBOFix
+ XXX.datafix.fixes.OptionsKeyLwjgl3Fix
- XXX.datafix.fixes.OptionsKeyTranslationFix
+ XXX.datafix.fixes.OptionsLowerCaseLanguageFix
- XXX.datafix.fixes.OptionsMenuBlurrinessFix
+ XXX.datafix.fixes.OptionsProgrammerArtFix
- XXX.datafix.fixes.OptionsRenameFieldFix
+ XXX.datafix.fixes.OverreachingTickFix
- XXX.datafix.fixes.ParticleUnflatteningFix
+ XXX.datafix.fixes.PlayerEquipmentFix
- XXX.datafix.fixes.PlayerHeadBlockProfileFix
+ XXX.datafix.fixes.PlayerUUIDFix
- XXX.datafix.fixes.PoiTypeRemoveFix
+ XXX.datafix.fixes.PoiTypeRenameFix
- XXX.datafix.fixes.PrimedTntBlockStateFixer
+ XXX.datafix.fixes.ProjectileStoredWeaponFix
- XXX.datafix.fixes.RaidRenamesDataFix
+ XXX.datafix.fixes.RandomSequenceSettingsFix
- XXX.datafix.fixes.RecipesFix
+ XXX.datafix.fixes.RecipesRenameningFix
- XXX.datafix.fixes.RedstoneWireConnectionsFix
+ XXX.datafix.fixes.References
- XXX.datafix.fixes.References$1
+ XXX.datafix.fixes.RemapChunkStatusFix
- XXX.datafix.fixes.RemoveBlockEntityTagFix
- XXX.dialog.body.DialogBody
- XXX.dialog.body.DialogBodyHandlers
- XXX.dialog.body.DialogBodyHandlers$PlainMessageHandler
- XXX.dialog.body.ItemBody
- XXX.dialog.body.package-info
- XXX.dialog.input.InputControl
- XXX.dialog.input.InputControlHandler
- XXX.dialog.input.InputControlHandlers
- XXX.dialog.input.InputControlHandlers$NumberRangeHandler
- XXX.dialog.input.InputControlHandlers$SingleOptionHandler
- XXX.dialog.input.NumberRangeInput
- XXX.dialog.input.package-info
- XXX.dialog.input.SingleOptionInput
- XXX.dialog.input.TextInput
- XXX.dialog.submit.CustomForm
- XXX.dialog.submit.CustomTemplate
- XXX.dialog.submit.package-info
- XXX.dialog.submit.SubmitMethod
- XXX.dialog.submit.SubmitMethodHandler
- XXX.dialog.submit.SubmitMethodHandlers
- XXX.dialog.submit.SubmitMethodHandlers$SendCustom
+ XXX.entity.layers.ArrowLayer
- XXX.entity.layers.BeeStingerLayer
+ XXX.entity.layers.BreezeEyesLayer
- XXX.entity.layers.BreezeWindLayer
+ XXX.entity.layers.CapeLayer
- XXX.entity.layers.CarriedBlockLayer
+ XXX.entity.layers.CatCollarLayer
- XXX.entity.layers.CreeperPowerLayer
+ XXX.entity.layers.CrossedArmsItemLayer
- XXX.entity.layers.CustomHeadLayer
+ XXX.entity.layers.CustomHeadLayer$Transforms
- XXX.entity.layers.Deadmau5EarsLayer
+ XXX.entity.layers.DolphinCarryingItemLayer
- XXX.entity.layers.DrownedOuterLayer
+ XXX.entity.layers.EnderEyesLayer
- XXX.entity.layers.EnergySwirlLayer
+ XXX.entity.layers.EquipmentLayerRenderer
- XXX.entity.layers.EquipmentLayerRenderer$LayerTextureKey
+ XXX.entity.layers.EquipmentLayerRenderer$TrimSpriteKey
- XXX.entity.layers.EyesLayer
+ XXX.entity.layers.FoxHeldItemLayer
- XXX.entity.layers.HorseMarkingLayer
+ XXX.entity.layers.HumanoidArmorLayer
- XXX.entity.layers.HumanoidArmorLayer$1
+ XXX.entity.layers.IronGolemCrackinessLayer
- XXX.entity.layers.IronGolemFlowerLayer
+ XXX.entity.layers.ItemInHandLayer
- XXX.entity.layers.LivingEntityEmissiveLayer
+ XXX.entity.layers.LivingEntityEmissiveLayer$AlphaFunction
- XXX.entity.layers.LivingEntityEmissiveLayer$DrawSelector
+ XXX.entity.layers.LlamaDecorLayer
- XXX.entity.layers.MushroomCowMushroomLayer
+ XXX.entity.layers.package-info
+ XXX.entity.layers.PandaHoldsItemLayer
- XXX.entity.layers.ParrotOnShoulderLayer
+ XXX.entity.layers.PhantomEyesLayer
- XXX.entity.layers.PlayerItemInHandLayer
+ XXX.entity.layers.RenderLayer
- XXX.entity.layers.RopesLayer
+ XXX.entity.layers.SheepWoolLayer
- XXX.entity.layers.SheepWoolUndercoatLayer
+ XXX.entity.layers.SimpleEquipmentLayer
- XXX.entity.layers.SkeletonClothingLayer
+ XXX.entity.layers.SlimeOuterLayer
- XXX.entity.layers.SnowGolemHeadLayer
+ XXX.entity.layers.SpiderEyesLayer
- XXX.entity.layers.SpinAttackEffectLayer
+ XXX.entity.layers.StuckInBodyLayer
- XXX.entity.layers.StuckInBodyLayer$PlacementStyle
+ XXX.entity.layers.TropicalFishPatternLayer
- XXX.entity.layers.TropicalFishPatternLayer$1
+ XXX.entity.layers.VillagerProfessionLayer
- XXX.entity.layers.WingsLayer
+ XXX.entity.layers.WitchItemLayer
- XXX.entity.layers.WitherArmorLayer
+ XXX.entity.layers.WolfArmorLayer
- XXX.entity.layers.WolfCollarLayer
- XXX.entity.player.package-info
+ XXX.entity.player.PlayerRenderer
+ XXX.entity.state.AllayRenderState
- XXX.entity.state.ArmadilloRenderState
+ XXX.entity.state.ArmedEntityRenderState
- XXX.entity.state.ArmorStandRenderState
+ XXX.entity.state.ArrowRenderState
- XXX.entity.state.AxolotlRenderState
+ XXX.entity.state.BatRenderState
- XXX.entity.state.BeeRenderState
+ XXX.entity.state.BlockDisplayEntityRenderState
- XXX.entity.state.BoatRenderState
+ XXX.entity.state.BoggedRenderState
- XXX.entity.state.BreezeRenderState
+ XXX.entity.state.CamelRenderState
- XXX.entity.state.CatRenderState
+ XXX.entity.state.ChickenRenderState
- XXX.entity.state.CowRenderState
+ XXX.entity.state.CreakingRenderState
- XXX.entity.state.CreeperRenderState
+ XXX.entity.state.DisplayEntityRenderState
- XXX.entity.state.DolphinRenderState
+ XXX.entity.state.DonkeyRenderState
- XXX.entity.state.EndCrystalRenderState
+ XXX.entity.state.EnderDragonRenderState
- XXX.entity.state.EndermanRenderState
+ XXX.entity.state.EntityRenderState
- XXX.entity.state.EntityRenderState$LeashState
+ XXX.entity.state.EquineRenderState
- XXX.entity.state.EvokerFangsRenderState
+ XXX.entity.state.EvokerRenderState
- XXX.entity.state.ExperienceOrbRenderState
+ XXX.entity.state.FallingBlockRenderState
- XXX.entity.state.FelineRenderState
+ XXX.entity.state.FireworkRocketRenderState
- XXX.entity.state.FishingHookRenderState
+ XXX.entity.state.FoxRenderState
- XXX.entity.state.FrogRenderState
+ XXX.entity.state.GhastRenderState
- XXX.entity.state.GoatRenderState
+ XXX.entity.state.GuardianRenderState
- XXX.entity.state.HappyGhastRenderState
- XXX.entity.state.HitboxesRenderState
+ XXX.entity.state.HitboxRenderState
+ XXX.entity.state.HoglinRenderState
- XXX.entity.state.HoldingEntityRenderState
+ XXX.entity.state.HorseRenderState
- XXX.entity.state.HumanoidRenderState
+ XXX.entity.state.IllagerRenderState
- XXX.entity.state.IllusionerRenderState
+ XXX.entity.state.IronGolemRenderState
- XXX.entity.state.ItemClusterRenderState
+ XXX.entity.state.ItemDisplayEntityRenderState
- XXX.entity.state.ItemEntityRenderState
+ XXX.entity.state.ItemFrameRenderState
- XXX.entity.state.LightningBoltRenderState
+ XXX.entity.state.LivingEntityRenderState
- XXX.entity.state.LlamaRenderState
+ XXX.entity.state.LlamaSpitRenderState
- XXX.entity.state.MinecartRenderState
+ XXX.entity.state.MinecartTntRenderState
- XXX.entity.state.MushroomCowRenderState
+ XXX.entity.state.package-info
+ XXX.entity.state.PaintingRenderState
- XXX.entity.state.PandaRenderState
+ XXX.entity.state.ParrotRenderState
- XXX.entity.state.PhantomRenderState
- XXX.entity.state.PiglinRenderState
+ XXX.entity.state.PigRenderState
+ XXX.entity.state.PlayerRenderState
- XXX.entity.state.PolarBearRenderState
+ XXX.entity.state.PufferfishRenderState
- XXX.entity.state.RabbitRenderState
+ XXX.entity.state.RavagerRenderState
- XXX.entity.state.SalmonRenderState
+ XXX.entity.state.ServerHitboxesRenderState
- XXX.entity.state.SheepRenderState
+ XXX.entity.state.ShulkerBulletRenderState
- XXX.entity.state.ShulkerRenderState
+ XXX.entity.state.SkeletonRenderState
- XXX.entity.state.SlimeRenderState
+ XXX.entity.state.SnifferRenderState
- XXX.entity.state.SnowGolemRenderState
+ XXX.entity.state.SquidRenderState
- XXX.entity.state.StriderRenderState
+ XXX.entity.state.TextDisplayEntityRenderState
- XXX.entity.state.ThrownItemRenderState
+ XXX.entity.state.ThrownTridentRenderState
- XXX.entity.state.TippableArrowRenderState
+ XXX.entity.state.TntRenderState
- XXX.entity.state.TropicalFishRenderState
+ XXX.entity.state.TurtleRenderState
- XXX.entity.state.VexRenderState
+ XXX.entity.state.VillagerDataHolderRenderState
- XXX.entity.state.VillagerRenderState
+ XXX.entity.state.WardenRenderState
- XXX.entity.state.WitchRenderState
+ XXX.entity.state.WitherRenderState
- XXX.entity.state.WitherSkullRenderState
+ XXX.entity.state.WolfRenderState
- XXX.entity.state.ZombieRenderState
+ XXX.entity.state.ZombieVillagerRenderState
- XXX.entity.state.ZombifiedPiglinRenderState
+ XXX.fog.environment.AirBasedFogEnvironment
- XXX.fog.environment.AtmosphericFogEnvironment
+ XXX.fog.environment.BlindnessFogEnvironment
- XXX.fog.environment.DarknessFogEnvironment
+ XXX.fog.environment.DimensionOrBossFogEnvironment
- XXX.fog.environment.FogEnvironment
+ XXX.fog.environment.LavaFogEnvironment
- XXX.fog.environment.MobEffectFogEnvironment
+ XXX.fog.environment.PowderedSnowFogEnvironment
- XXX.fog.environment.WaterFogEnvironment
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
- XXX.geom.builders.CubeDefinition
+ XXX.geom.builders.CubeDeformation
- XXX.geom.builders.CubeListBuilder
+ XXX.geom.builders.LayerDefinition
- XXX.geom.builders.MaterialDefinition
+ XXX.geom.builders.MeshDefinition
- XXX.geom.builders.MeshTransformer
+ XXX.geom.builders.package-info
+ XXX.geom.builders.PartDefinition
- XXX.geom.builders.UVPair
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
- XXX.gui.components.SplashRenderer
+ XXX.gui.components.SpriteIconButton
- XXX.gui.components.SpriteIconButton$Builder
+ XXX.gui.components.SpriteIconButton$CenteredIcon
- XXX.gui.components.SpriteIconButton$TextAndIcon
+ XXX.gui.components.StateSwitchingButton
- XXX.gui.components.StringWidget
+ XXX.gui.components.SubtitleOverlay
- XXX.gui.components.SubtitleOverlay$SoundPlayedAt
+ XXX.gui.components.SubtitleOverlay$Subtitle
- XXX.gui.components.TabButton
+ XXX.gui.components.TabOrderedElement
- XXX.gui.components.Tooltip
+ XXX.gui.components.Whence
- XXX.gui.components.WidgetSprites
+ XXX.gui.components.WidgetTooltipHolder
- XXX.gui.render.GuiRenderer$1
+ XXX.gui.render.GuiRenderer$AtlasPosition
- XXX.gui.render.GuiRenderer$Draw
+ XXX.gui.render.GuiRenderer$MeshToDraw
+ XXX.gui.render.package-info
- XXX.gui.render.TextureSetup
+ XXX.gui.screens.AccessibilityOnboardingScreen
- XXX.gui.screens.AddRealmPopupScreen
- XXX.gui.screens.AlertScreen
+ XXX.gui.screens.BackupConfirmScreen
- XXX.gui.screens.BackupConfirmScreen$Listener
+ XXX.gui.screens.BanNoticeScreens
- XXX.gui.screens.ChatScreen
+ XXX.gui.screens.ChatScreen$1
- XXX.gui.screens.ConfirmLinkScreen
+ XXX.gui.screens.ConfirmScreen
- XXX.gui.screens.ConnectScreen
+ XXX.gui.screens.ConnectScreen$1
- XXX.gui.screens.ConnectScreen$2
+ XXX.gui.screens.CreateBuffetWorldScreen
- XXX.gui.screens.CreateBuffetWorldScreen$BiomeList
+ XXX.gui.screens.CreateBuffetWorldScreen$BiomeList$Entry
- XXX.gui.screens.CreateFlatWorldScreen
+ XXX.gui.screens.CreateFlatWorldScreen$DetailsList
- XXX.gui.screens.CreateFlatWorldScreen$DetailsList$Entry
+ XXX.gui.screens.CreditsAndAttributionScreen
- XXX.gui.screens.DatapackLoadFailureScreen
+ XXX.gui.screens.DeathScreen
- XXX.gui.screens.DeathScreen$TitleConfirmScreen
+ XXX.gui.screens.DemoIntroScreen
- XXX.gui.screens.DirectJoinServerScreen
+ XXX.gui.screens.DisconnectedScreen
- XXX.gui.screens.EditServerScreen
+ XXX.gui.screens.ErrorScreen
- XXX.gui.screens.FaviconTexture
+ XXX.gui.screens.GenericMessageScreen
- XXX.gui.screens.GenericWaitingScreen
+ XXX.gui.screens.InBedChatScreen
- XXX.gui.screens.LevelLoadingScreen
+ XXX.gui.screens.LoadingDotsText
- XXX.gui.screens.LoadingOverlay
+ XXX.gui.screens.LoadingOverlay$LogoTexture
- XXX.gui.screens.MenuScreens
+ XXX.gui.screens.MenuScreens$ScreenConstructor
- XXX.gui.screens.NoticeWithLinkScreen
+ XXX.gui.screens.OutOfMemoryScreen
- XXX.gui.screens.Overlay
- XXX.gui.screens.package-info
+ XXX.gui.screens.PauseScreen
- XXX.gui.screens.PauseScreen$FeedbackSubScreen
+ XXX.gui.screens.PresetFlatWorldScreen
- XXX.gui.screens.PresetFlatWorldScreen$PresetsList
+ XXX.gui.screens.PresetFlatWorldScreen$PresetsList$Entry
- XXX.gui.screens.ProgressScreen
+ XXX.gui.screens.RealmsBrokenWorldScreen
- XXX.gui.screens.RealmsClientOutdatedScreen
+ XXX.gui.screens.RealmsConfirmScreen
- XXX.gui.screens.RealmsCreateRealmScreen
+ XXX.gui.screens.RealmsDownloadLatestWorldScreen
- XXX.gui.screens.RealmsDownloadLatestWorldScreen$DownloadStatus
+ XXX.gui.screens.RealmsGenericErrorScreen
- XXX.gui.screens.RealmsGenericErrorScreen$ErrorMessage
+ XXX.gui.screens.RealmsNotificationsScreen
- XXX.gui.screens.RealmsNotificationsScreen$1
+ XXX.gui.screens.RealmsNotificationsScreen$2
- XXX.gui.screens.RealmsNotificationsScreen$DataFetcherConfiguration
+ XXX.gui.screens.RealmsParentalConsentScreen
- XXX.gui.screens.RealmsPendingInvitesScreen
+ XXX.gui.screens.RealmsPendingInvitesScreen$Entry
- XXX.gui.screens.RealmsPendingInvitesScreen$Entry$AcceptRowButton
+ XXX.gui.screens.RealmsPendingInvitesScreen$Entry$RejectRowButton
- XXX.gui.screens.RealmsPendingInvitesScreen$PendingInvitationSelectionList
+ XXX.gui.screens.RealmsPopups
- XXX.gui.screens.RealmsResetWorldScreen
+ XXX.gui.screens.RealmsResetWorldScreen$1
- XXX.gui.screens.RealmsResetWorldScreen$FrameButton
+ XXX.gui.screens.RealmsSelectFileToUploadScreen
- XXX.gui.screens.RealmsSelectFileToUploadScreen$Entry
+ XXX.gui.screens.RealmsSelectFileToUploadScreen$WorldSelectionList
- XXX.gui.screens.RealmsSelectWorldTemplateScreen
+ XXX.gui.screens.RealmsSelectWorldTemplateScreen$1
- XXX.gui.screens.RealmsSelectWorldTemplateScreen$Entry
+ XXX.gui.screens.RealmsSelectWorldTemplateScreen$WorldTemplateList
- XXX.gui.screens.RealmsTermsScreen
+ XXX.gui.screens.RealmsUploadScreen
+ XXX.gui.screens.ReceivingLevelScreen
- XXX.gui.screens.ReceivingLevelScreen$Reason
+ XXX.gui.screens.RecoverWorldDataScreen
- XXX.gui.screens.Screen
+ XXX.gui.screens.Screen$NarratableSearchResult
- XXX.gui.screens.ShareToLanScreen
+ XXX.gui.screens.TitleScreen
- XXX.gui.screens.UploadResult
+ XXX.gui.screens.UploadResult$Builder
- XXX.gui.screens.WinScreen
+ XXX.gui.screens.WinScreen$CreditsReader
- XXX.gui.spectator.package-info
- XXX.gui.spectator.PlayerMenuItem
+ XXX.gui.spectator.RootSpectatorMenuCategory
- XXX.gui.spectator.SpectatorMenu
+ XXX.gui.spectator.SpectatorMenu$1
- XXX.gui.spectator.SpectatorMenu$CloseSpectatorItem
+ XXX.gui.spectator.SpectatorMenu$ScrollMenuItem
- XXX.gui.spectator.SpectatorMenuCategory
+ XXX.gui.spectator.SpectatorMenuItem
- XXX.gui.spectator.SpectatorMenuListener
+ XXX.gui.task.DataFetcher
- XXX.gui.task.DataFetcher$ComputationResult
+ XXX.gui.task.DataFetcher$SubscribedTask
- XXX.gui.task.DataFetcher$Subscription
+ XXX.gui.task.DataFetcher$SuccessfulComputationResult
- XXX.gui.task.DataFetcher$Task
- XXX.gui.task.package-info
+ XXX.gui.task.RepeatedDelayStrategy
- XXX.gui.task.RepeatedDelayStrategy$1
+ XXX.gui.task.RepeatedDelayStrategy$2
+ XXX.inventory.tooltip.BelowOrAboveWidgetTooltipPositioner
- XXX.inventory.tooltip.ClientActivePlayersTooltip
+ XXX.inventory.tooltip.ClientActivePlayersTooltip$ActivePlayersTooltip
- XXX.inventory.tooltip.ClientBundleTooltip
+ XXX.inventory.tooltip.ClientTextTooltip
- XXX.inventory.tooltip.ClientTooltipComponent
+ XXX.inventory.tooltip.ClientTooltipPositioner
- XXX.inventory.tooltip.DefaultTooltipPositioner
+ XXX.inventory.tooltip.MenuTooltipPositioner
+ XXX.inventory.tooltip.package-info
- XXX.inventory.tooltip.TooltipRenderUtil
+ XXX.item.properties.package-info
- XXX.level.progress.ChunkProgressListener
+ XXX.level.progress.ChunkProgressListenerFactory
- XXX.level.progress.LoggerChunkProgressListener
+ XXX.level.progress.package-info
+ XXX.level.progress.ProcessorChunkProgressListener
- XXX.level.progress.StoringChunkProgressListener
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
- XXX.metadata.pack.package-info
+ XXX.metadata.pack.PackMetadataSection
+ XXX.metadata.texture.package-info
- XXX.metadata.texture.TextureMetadataSection
- XXX.minecraft.advancements.Advancement
+ XXX.minecraft.advancements.Advancement$Builder
- XXX.minecraft.advancements.AdvancementHolder
+ XXX.minecraft.advancements.AdvancementNode
- XXX.minecraft.advancements.AdvancementProgress
+ XXX.minecraft.advancements.AdvancementRequirements
- XXX.minecraft.advancements.AdvancementRequirements$Strategy
+ XXX.minecraft.advancements.AdvancementRewards
- XXX.minecraft.advancements.AdvancementRewards$Builder
+ XXX.minecraft.advancements.AdvancementTree
- XXX.minecraft.advancements.AdvancementTree$Listener
+ XXX.minecraft.advancements.AdvancementType
- XXX.minecraft.advancements.CriteriaTriggers
+ XXX.minecraft.advancements.Criterion
- XXX.minecraft.advancements.CriterionProgress
+ XXX.minecraft.advancements.CriterionTrigger
- XXX.minecraft.advancements.CriterionTrigger$Listener
+ XXX.minecraft.advancements.CriterionTriggerInstance
- XXX.minecraft.advancements.DisplayInfo
+ XXX.minecraft.advancements.package-info
+ XXX.minecraft.advancements.TreeNodePosition
- XXX.minecraft.client.AttackIndicatorStatus
+ XXX.minecraft.client.Camera
- XXX.minecraft.client.Camera$NearPlane
+ XXX.minecraft.client.CameraType
- XXX.minecraft.client.ClientBootstrap
+ XXX.minecraft.client.ClientBrandRetriever
- XXX.minecraft.client.ClientRecipeBook
+ XXX.minecraft.client.CloudStatus
- XXX.minecraft.client.CommandHistory
+ XXX.minecraft.client.ComponentCollector
- XXX.minecraft.client.DebugQueryHandler
+ XXX.minecraft.client.DeltaTracker
- XXX.minecraft.client.DeltaTracker$DefaultValue
+ XXX.minecraft.client.DeltaTracker$Timer
- XXX.minecraft.client.GameNarrator
+ XXX.minecraft.client.GameNarrator$NarratorInitException
- XXX.minecraft.client.GraphicsStatus
+ XXX.minecraft.client.GuiMessage
- XXX.minecraft.client.GuiMessage$Line
+ XXX.minecraft.client.GuiMessageTag
- XXX.minecraft.client.GuiMessageTag$Icon
+ XXX.minecraft.client.HotbarManager
- XXX.minecraft.client.InactivityFpsLimit
+ XXX.minecraft.client.InputType
+ XXX.minecraft.client.KeyboardHandler
- XXX.minecraft.client.KeyboardHandler$1
- XXX.minecraft.client.KeyMapping
+ XXX.minecraft.client.Minecraft
- XXX.minecraft.client.Minecraft$1
+ XXX.minecraft.client.Minecraft$2
- XXX.minecraft.client.Minecraft$ChatStatus
+ XXX.minecraft.client.Minecraft$ChatStatus$1
- XXX.minecraft.client.Minecraft$ChatStatus$2
+ XXX.minecraft.client.Minecraft$ChatStatus$3
- XXX.minecraft.client.Minecraft$ChatStatus$4
+ XXX.minecraft.client.Minecraft$GameLoadCookie
- XXX.minecraft.client.MouseHandler
+ XXX.minecraft.client.NarratorStatus
- XXX.minecraft.client.OptionInstance
+ XXX.minecraft.client.OptionInstance$AltEnum
- XXX.minecraft.client.OptionInstance$CaptionBasedToString
+ XXX.minecraft.client.OptionInstance$ClampingLazyMaxIntRange
- XXX.minecraft.client.OptionInstance$CycleableValueSet
+ XXX.minecraft.client.OptionInstance$CycleableValueSet$ValueSetter
- XXX.minecraft.client.OptionInstance$Enum
+ XXX.minecraft.client.OptionInstance$IntRange
- XXX.minecraft.client.OptionInstance$IntRangeBase
+ XXX.minecraft.client.OptionInstance$IntRangeBase$1
- XXX.minecraft.client.OptionInstance$LazyEnum
+ XXX.minecraft.client.OptionInstance$OptionInstanceSliderButton
- XXX.minecraft.client.OptionInstance$SliderableOrCyclableValueSet
+ XXX.minecraft.client.OptionInstance$SliderableValueSet
- XXX.minecraft.client.OptionInstance$TooltipSupplier
+ XXX.minecraft.client.OptionInstance$UnitDouble
- XXX.minecraft.client.OptionInstance$UnitDouble$1
+ XXX.minecraft.client.OptionInstance$ValueSet
- XXX.minecraft.client.Options
+ XXX.minecraft.client.Options$1
- XXX.minecraft.client.Options$2
+ XXX.minecraft.client.Options$3
- XXX.minecraft.client.Options$4
+ XXX.minecraft.client.Options$5
- XXX.minecraft.client.Options$FieldAccess
+ XXX.minecraft.client.Options$OptionAccess
+ XXX.minecraft.client.package-info
- XXX.minecraft.client.PeriodicNotificationManager
+ XXX.minecraft.client.PeriodicNotificationManager$Notification
- XXX.minecraft.client.PeriodicNotificationManager$NotificationTask
+ XXX.minecraft.client.PrioritizeChunkUpdates
- XXX.minecraft.client.ResourceLoadStateTracker
+ XXX.minecraft.client.ResourceLoadStateTracker$RecoveryInfo
- XXX.minecraft.client.ResourceLoadStateTracker$ReloadReason
+ XXX.minecraft.client.ResourceLoadStateTracker$ReloadState
- XXX.minecraft.client.Screenshot
+ XXX.minecraft.client.ScrollWheelHandler
- XXX.minecraft.client.StringSplitter
+ XXX.minecraft.client.StringSplitter$1
- XXX.minecraft.client.StringSplitter$FlatComponents
+ XXX.minecraft.client.StringSplitter$LineBreakFinder
- XXX.minecraft.client.StringSplitter$LineComponent
+ XXX.minecraft.client.StringSplitter$LinePosConsumer
- XXX.minecraft.client.StringSplitter$WidthLimitedCharSink
+ XXX.minecraft.client.StringSplitter$WidthProvider
- XXX.minecraft.client.ToggleKeyMapping
+ XXX.minecraft.client.User
- XXX.minecraft.client.User$Type
+ XXX.minecraft.commands.Commands$1$1
- XXX.minecraft.commands.Commands$2
- XXX.minecraft.commands.Commands$CommandSelection
+ XXX.minecraft.commands.Commands$ParseFunction
- XXX.minecraft.commands.ExecutionCommandSource
+ XXX.minecraft.commands.FunctionInstantiationException
- XXX.minecraft.commands.ParserUtils
- XXX.minecraft.commands.PermissionSource$Check
+ XXX.minecraft.commands.SharedSuggestionProvider
- XXX.minecraft.commands.SharedSuggestionProvider$ElementSuggestionType
+ XXX.minecraft.commands.SharedSuggestionProvider$TextCoordinates
- XXX.minecraft.gametest.Main
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
+ XXX.minecraft.network.MonitoredLocalFrameDecoder
- XXX.minecraft.network.PacketBundlePacker
+ XXX.minecraft.network.PacketBundleUnpacker
- XXX.minecraft.network.PacketDecoder
+ XXX.minecraft.network.PacketEncoder
- XXX.minecraft.network.PacketListener
+ XXX.minecraft.network.PacketSendListener
- XXX.minecraft.network.PacketSendListener$1
+ XXX.minecraft.network.PacketSendListener$2
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
+ XXX.minecraft.server.package-info
+ XXX.minecraft.sounds.Music
- XXX.minecraft.sounds.Musics
- XXX.minecraft.sounds.package-info
+ XXX.minecraft.sounds.SoundEvent
- XXX.minecraft.sounds.SoundEvents
+ XXX.minecraft.sounds.SoundSource
- XXX.minecraft.stats.package-info
+ XXX.minecraft.stats.RecipeBook
- XXX.minecraft.stats.RecipeBookSettings
+ XXX.minecraft.stats.RecipeBookSettings$1
- XXX.minecraft.stats.RecipeBookSettings$TypeSettings
+ XXX.minecraft.stats.ServerRecipeBook
- XXX.minecraft.stats.ServerRecipeBook$DisplayResolver
+ XXX.minecraft.stats.ServerRecipeBook$Packed
- XXX.minecraft.stats.ServerStatsCounter
+ XXX.minecraft.stats.Stat
- XXX.minecraft.stats.StatFormatter
- XXX.minecraft.stats.Stats
+ XXX.minecraft.stats.StatsCounter
+ XXX.minecraft.stats.StatType
+ XXX.minecraft.tags.BannerPatternTags
- XXX.minecraft.tags.BiomeTags
+ XXX.minecraft.tags.BlockTags
- XXX.minecraft.tags.DamageTypeTags
- XXX.model.dragon.DragonHeadModel
+ XXX.model.dragon.EnderDragonModel
- XXX.model.dragon.package-info
+ XXX.model.geom.EntityModelSet
- XXX.model.geom.LayerDefinitions
+ XXX.model.geom.ModelLayerLocation
- XXX.model.geom.ModelLayers
+ XXX.model.geom.ModelPart
- XXX.model.geom.ModelPart$Cube
+ XXX.model.geom.ModelPart$Polygon
- XXX.model.geom.ModelPart$Vertex
+ XXX.model.geom.ModelPart$Visitor
- XXX.model.geom.package-info
- XXX.model.geom.PartNames
+ XXX.model.geom.PartPose
+ XXX.model.multipart.CombinedCondition
- XXX.model.multipart.CombinedCondition$Operation
+ XXX.model.multipart.CombinedCondition$Operation$1
- XXX.model.multipart.CombinedCondition$Operation$2
+ XXX.model.multipart.Condition
- XXX.model.multipart.KeyValueCondition
+ XXX.model.multipart.KeyValueCondition$Term
- XXX.model.multipart.KeyValueCondition$Terms
+ XXX.model.multipart.MultiPartModel
- XXX.model.multipart.MultiPartModel$Selector
+ XXX.model.multipart.MultiPartModel$SharedBakedState
- XXX.model.multipart.MultiPartModel$Unbaked
+ XXX.model.multipart.MultiPartModel$Unbaked$1
- XXX.model.multipart.MultiPartModel$Unbaked$1Key
- XXX.model.multipart.package-info
+ XXX.model.multipart.Selector
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
+ XXX.mojang.realmsclient.package-info
- XXX.multiplayer.chat.ChatListener
+ XXX.multiplayer.chat.ChatListener$Message
- XXX.multiplayer.chat.ChatLog
+ XXX.multiplayer.chat.ChatTrustLevel
- XXX.multiplayer.chat.LoggedChatEvent
+ XXX.multiplayer.chat.LoggedChatEvent$Type
- XXX.multiplayer.chat.LoggedChatMessage
+ XXX.multiplayer.chat.LoggedChatMessage$Player
- XXX.multiplayer.chat.LoggedChatMessage$System
+ XXX.multiplayer.chat.package-info
- XXX.multiplayer.prediction.BlockStatePredictionHandler
+ XXX.multiplayer.prediction.BlockStatePredictionHandler$ServerVerifiedState
+ XXX.multiplayer.prediction.package-info
- XXX.multiplayer.prediction.PredictiveAction
- XXX.multiplayer.resolver.AddressCheck
+ XXX.multiplayer.resolver.AddressCheck$1
- XXX.multiplayer.resolver.package-info
- XXX.multiplayer.resolver.ResolvedServerAddress
+ XXX.multiplayer.resolver.ResolvedServerAddress$1
- XXX.multiplayer.resolver.ServerAddress
+ XXX.multiplayer.resolver.ServerAddressResolver
- XXX.multiplayer.resolver.ServerNameResolver
+ XXX.multiplayer.resolver.ServerRedirectHandler
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
- XXX.network.chat.ClickEvent$ShowDialog
+ XXX.network.chat.ClickEvent$SuggestCommand
- XXX.network.chat.CommonComponents
+ XXX.network.chat.Component
- XXX.network.chat.ComponentContents
+ XXX.network.chat.ComponentContents$Type
- XXX.network.chat.ComponentSerialization
+ XXX.network.chat.ComponentSerialization$1
- XXX.network.chat.ComponentSerialization$FuzzyCodec
+ XXX.network.chat.ComponentSerialization$StrictEither
- XXX.network.chat.ComponentUtils
+ XXX.network.chat.FilterMask
- XXX.network.chat.FilterMask$Type
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
- XXX.network.chat.package-info
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
- XXX.network.config.JoinWorldTask
+ XXX.network.config.package-info
+ XXX.network.config.ServerResourcePackConfigurationTask
- XXX.network.config.SynchronizeRegistriesTask
- XXX.packs.linkfs.DummyFileAttributes
+ XXX.packs.linkfs.LinkFileSystem
- XXX.packs.linkfs.LinkFileSystem$Builder
+ XXX.packs.linkfs.LinkFileSystem$DirectoryEntry
+ XXX.packs.linkfs.LinkFSFileStore
- XXX.packs.linkfs.LinkFSPath
+ XXX.packs.linkfs.LinkFSPath$1
- XXX.packs.linkfs.LinkFSPath$2
+ XXX.packs.linkfs.LinkFSPath$3
- XXX.packs.linkfs.LinkFSProvider
+ XXX.packs.linkfs.LinkFSProvider$1
- XXX.packs.linkfs.LinkFSProvider$2
+ XXX.packs.linkfs.package-info
- XXX.packs.linkfs.PathContents
+ XXX.packs.linkfs.PathContents$1
- XXX.packs.linkfs.PathContents$2
+ XXX.packs.linkfs.PathContents$DirectoryContents
- XXX.packs.linkfs.PathContents$FileContents
- XXX.packs.metadata.MetadataSectionType
+ XXX.packs.metadata.package-info
+ XXX.packs.repository.BuiltInPackSource
- XXX.packs.repository.BuiltInPackSource$1
+ XXX.packs.repository.FolderRepositorySource
- XXX.packs.repository.FolderRepositorySource$FolderPackDetector
+ XXX.packs.repository.KnownPack
- XXX.packs.repository.Pack
+ XXX.packs.repository.Pack$Metadata
- XXX.packs.repository.Pack$Position
+ XXX.packs.repository.Pack$ResourcesSupplier
+ XXX.packs.repository.package-info
- XXX.packs.repository.PackCompatibility
+ XXX.packs.repository.PackDetector
- XXX.packs.repository.PackRepository
+ XXX.packs.repository.PackSource
- XXX.packs.repository.PackSource$1
+ XXX.packs.repository.RepositorySource
- XXX.packs.repository.ServerPacksSource
- XXX.packs.resources.CloseableResourceManager
+ XXX.packs.resources.FallbackResourceManager
- XXX.packs.resources.FallbackResourceManager$1ResourceWithSourceAndIndex
+ XXX.packs.resources.FallbackResourceManager$EntryStack
- XXX.packs.resources.FallbackResourceManager$LeakedResourceWarningInputStream
+ XXX.packs.resources.FallbackResourceManager$PackEntry
- XXX.packs.resources.FallbackResourceManager$ResourceWithSource
+ XXX.packs.resources.IoSupplier
- XXX.packs.resources.MultiPackResourceManager
+ XXX.packs.resources.package-info
+ XXX.packs.resources.PreparableReloadListener
- XXX.packs.resources.PreparableReloadListener$PreparationBarrier
+ XXX.packs.resources.ProfiledReloadInstance
- XXX.packs.resources.ProfiledReloadInstance$State
- XXX.packs.resources.ReloadableResourceManager
+ XXX.packs.resources.ReloadInstance
+ XXX.packs.resources.Resource
- XXX.packs.resources.ResourceFilterSection
+ XXX.packs.resources.ResourceManager
- XXX.packs.resources.ResourceManager$Empty
+ XXX.packs.resources.ResourceManagerReloadListener
- XXX.packs.resources.ResourceMetadata
+ XXX.packs.resources.ResourceMetadata$1
- XXX.packs.resources.ResourceMetadata$2
+ XXX.packs.resources.ResourceMetadata$Builder
- XXX.packs.resources.ResourceMetadata$Builder$1
+ XXX.packs.resources.ResourceProvider
- XXX.packs.resources.SimpleJsonResourceReloadListener
+ XXX.packs.resources.SimplePreparableReloadListener
- XXX.packs.resources.SimpleReloadInstance
+ XXX.packs.resources.SimpleReloadInstance$1
- XXX.packs.resources.SimpleReloadInstance$StateFactory
- XXX.player.inventory.Hotbar
+ XXX.player.inventory.package-info
+ XXX.properties.conditional.Broken
- XXX.properties.conditional.BundleHasSelectedItem
+ XXX.properties.conditional.ComponentMatches
- XXX.properties.conditional.ConditionalItemModelProperties
+ XXX.properties.conditional.ConditionalItemModelProperty
- XXX.properties.conditional.CustomModelDataProperty
+ XXX.properties.conditional.Damaged
- XXX.properties.conditional.ExtendedView
+ XXX.properties.conditional.FishingRodCast
- XXX.properties.conditional.HasComponent
+ XXX.properties.conditional.IsCarried
- XXX.properties.conditional.IsKeybindDown
+ XXX.properties.conditional.IsSelected
- XXX.properties.conditional.IsUsingItem
+ XXX.properties.conditional.IsViewEntity
- XXX.properties.conditional.ItemModelPropertyTest
+ XXX.properties.conditional.package-info
- XXX.properties.numeric.BundleFullness
+ XXX.properties.numeric.CompassAngle
- XXX.properties.numeric.CompassAngleState
+ XXX.properties.numeric.CompassAngleState$CompassTarget
- XXX.properties.numeric.CompassAngleState$CompassTarget$1
+ XXX.properties.numeric.CompassAngleState$CompassTarget$2
- XXX.properties.numeric.CompassAngleState$CompassTarget$3
+ XXX.properties.numeric.CompassAngleState$CompassTarget$4
- XXX.properties.numeric.Cooldown
+ XXX.properties.numeric.Count
- XXX.properties.numeric.CrossbowPull
+ XXX.properties.numeric.CustomModelDataProperty
- XXX.properties.numeric.Damage
+ XXX.properties.numeric.NeedleDirectionHelper
- XXX.properties.numeric.NeedleDirectionHelper$1
+ XXX.properties.numeric.NeedleDirectionHelper$2
- XXX.properties.numeric.NeedleDirectionHelper$Wobbler
- XXX.properties.numeric.package-info
+ XXX.properties.numeric.RangeSelectItemModelProperties
- XXX.properties.numeric.RangeSelectItemModelProperty
+ XXX.properties.numeric.Time
- XXX.properties.numeric.Time$TimeSource
+ XXX.properties.numeric.Time$TimeSource$1
- XXX.properties.numeric.Time$TimeSource$2
+ XXX.properties.numeric.Time$TimeSource$3
- XXX.properties.numeric.UseCycle
+ XXX.properties.numeric.UseDuration
- XXX.properties.select.Charge
+ XXX.properties.select.ComponentContents
- XXX.properties.select.ContextDimension
+ XXX.properties.select.ContextEntityType
- XXX.properties.select.CustomModelDataProperty
+ XXX.properties.select.DisplayContext
- XXX.properties.select.ItemBlockState
+ XXX.properties.select.LocalTime
- XXX.properties.select.LocalTime$Data
+ XXX.properties.select.MainHand
- XXX.properties.select.package-info
- XXX.properties.select.SelectItemModelProperties
+ XXX.properties.select.SelectItemModelProperty
- XXX.properties.select.SelectItemModelProperty$Type
+ XXX.properties.select.TrimMaterialProperty
- XXX.protocol.common.ClientboundClearDialogPacket
+ XXX.protocol.common.ClientboundCustomPayloadPacket
- XXX.protocol.common.ClientboundCustomReportDetailsPacket
+ XXX.protocol.common.ClientboundDisconnectPacket
- XXX.protocol.common.ClientboundKeepAlivePacket
+ XXX.protocol.common.ClientboundPingPacket
- XXX.protocol.common.ClientboundResourcePackPopPacket
+ XXX.protocol.common.ClientboundResourcePackPushPacket
- XXX.protocol.common.ClientboundServerLinksPacket
- XXX.protocol.game.ClientboundCommandsPacket$NodeInspector
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
- XXX.protocol.game.ServerboundCustomClickActionPacket
- XXX.rcon.thread.GenericThread
+ XXX.rcon.thread.package-info
+ XXX.rcon.thread.QueryThreadGs4
- XXX.rcon.thread.QueryThreadGs4$RequestChallenge
+ XXX.rcon.thread.RconClient
- XXX.rcon.thread.RconThread
+ XXX.realmsclient.dto.package-info
- XXX.realmsclient.dto.RealmsJoinInformation
+ XXX.realmsclient.dto.RealmsServerAddress
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
- XXX.realmsclient.dto.RegionSelectionPreferenceDto
+ XXX.realmsclient.dto.RegionSelectionPreferenceDto$RegionSelectionPreference
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
+ XXX.realmsclient.gui.package-info
+ XXX.realmsclient.gui.RealmsDataFetcher
- XXX.realmsclient.gui.RealmsDataFetcher$ServerListData
+ XXX.realmsclient.gui.RealmsNewsManager
- XXX.realmsclient.gui.RealmsServerList
+ XXX.realmsclient.gui.RealmsWorldSlotButton
- XXX.realmsclient.gui.RealmsWorldSlotButton$Action
+ XXX.realmsclient.gui.RealmsWorldSlotButton$State
- XXX.realmsclient.gui.RowButton
- XXX.realmsclient.util.JsonUtils
+ XXX.realmsclient.util.LevelType
+ XXX.realmsclient.util.package-info
- XXX.realmsclient.util.RealmsPersistence
+ XXX.realmsclient.util.RealmsPersistence$RealmsPersistenceData
- XXX.realmsclient.util.RealmsTextureManager
+ XXX.realmsclient.util.RealmsTextureManager$RealmsTexture
- XXX.realmsclient.util.RealmsUtil
+ XXX.realmsclient.util.TextRenderingUtils
- XXX.realmsclient.util.TextRenderingUtils$Line
+ XXX.realmsclient.util.TextRenderingUtils$LineSegment
- XXX.realmsclient.util.UploadTokenCache
- XXX.render.pip.GuiBannerResultRenderer
+ XXX.render.pip.GuiBookModelRenderer
- XXX.render.pip.GuiEntityRenderer
+ XXX.render.pip.GuiProfilerChartRenderer
- XXX.render.pip.GuiSignRenderer
+ XXX.render.pip.GuiSkinRenderer
+ XXX.render.pip.package-info
- XXX.render.pip.PictureInPictureRenderer
- XXX.render.state.BlitRenderState
+ XXX.render.state.ColoredRectangleRenderState
- XXX.render.state.GlyphEffectRenderState
- XXX.render.state.package-info
+ XXX.render.state.TextRenderState
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
- XXX.renderer.block.package-info
+ XXX.renderer.blockentity.AbstractSignRenderer
- XXX.renderer.blockentity.BannerRenderer
+ XXX.renderer.blockentity.BeaconRenderer
- XXX.renderer.blockentity.BedRenderer
+ XXX.renderer.blockentity.BellRenderer
- XXX.renderer.blockentity.BlockEntityRenderDispatcher
+ XXX.renderer.blockentity.BlockEntityRenderer
- XXX.renderer.blockentity.BlockEntityRendererProvider
+ XXX.renderer.blockentity.BlockEntityRendererProvider$Context
- XXX.renderer.blockentity.BlockEntityRenderers
+ XXX.renderer.blockentity.BlockEntityWithBoundingBoxRenderer
- XXX.renderer.blockentity.BrightnessCombiner
+ XXX.renderer.blockentity.BrushableBlockRenderer
- XXX.renderer.blockentity.BrushableBlockRenderer$1
+ XXX.renderer.blockentity.CampfireRenderer
- XXX.renderer.blockentity.ChestRenderer
+ XXX.renderer.blockentity.ConduitRenderer
- XXX.renderer.blockentity.DecoratedPotRenderer
+ XXX.renderer.blockentity.EnchantTableRenderer
- XXX.renderer.blockentity.HangingSignRenderer
+ XXX.renderer.blockentity.HangingSignRenderer$AttachmentType
- XXX.renderer.blockentity.HangingSignRenderer$ModelKey
+ XXX.renderer.blockentity.LecternRenderer
+ XXX.renderer.blockentity.package-info
- XXX.renderer.blockentity.PistonHeadRenderer
+ XXX.renderer.blockentity.ShulkerBoxRenderer
- XXX.renderer.blockentity.ShulkerBoxRenderer$ShulkerBoxModel
+ XXX.renderer.blockentity.SignRenderer
- XXX.renderer.blockentity.SignRenderer$Models
+ XXX.renderer.blockentity.SkullBlockRenderer
- XXX.renderer.blockentity.SkullBlockRenderer$1
+ XXX.renderer.blockentity.SpawnerRenderer
- XXX.renderer.blockentity.TestInstanceRenderer
+ XXX.renderer.blockentity.TheEndGatewayRenderer
- XXX.renderer.blockentity.TheEndPortalRenderer
+ XXX.renderer.blockentity.TrialSpawnerRenderer
- XXX.renderer.blockentity.VaultRenderer
- XXX.renderer.chunk.CompileTaskDynamicQueue
+ XXX.renderer.chunk.package-info
+ XXX.renderer.chunk.RenderChunk
- XXX.renderer.chunk.RenderChunkRegion
+ XXX.renderer.chunk.RenderRegionCache
- XXX.renderer.chunk.RenderRegionCache$ChunkInfo
+ XXX.renderer.chunk.SectionCompiler
- XXX.renderer.chunk.SectionCompiler$Results
+ XXX.renderer.chunk.SectionRenderDispatcher
- XXX.renderer.chunk.SectionRenderDispatcher$CompiledSection
+ XXX.renderer.chunk.SectionRenderDispatcher$CompiledSection$1
- XXX.renderer.chunk.SectionRenderDispatcher$CompiledSection$2
+ XXX.renderer.chunk.SectionRenderDispatcher$RenderSection
- XXX.renderer.chunk.SectionRenderDispatcher$RenderSection$CompileTask
+ XXX.renderer.chunk.SectionRenderDispatcher$RenderSection$RebuildTask
- XXX.renderer.chunk.SectionRenderDispatcher$RenderSection$ResortTransparencyTask
+ XXX.renderer.chunk.SectionRenderDispatcher$SectionBuffers
- XXX.renderer.chunk.SectionRenderDispatcher$SectionTaskResult
+ XXX.renderer.chunk.SectionRenderDispatcher$TranslucencyPointOfView
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
+ XXX.renderer.entity.CowRenderer
- XXX.renderer.entity.CreakingRenderer
+ XXX.renderer.entity.CreeperRenderer
- XXX.renderer.entity.DisplayRenderer
+ XXX.renderer.entity.DisplayRenderer$1
- XXX.renderer.entity.DisplayRenderer$BlockDisplayRenderer
+ XXX.renderer.entity.DisplayRenderer$ItemDisplayRenderer
- XXX.renderer.entity.DisplayRenderer$TextDisplayRenderer
+ XXX.renderer.entity.DolphinRenderer
- XXX.renderer.entity.DonkeyRenderer
+ XXX.renderer.entity.DonkeyRenderer$Type
- XXX.renderer.entity.DragonFireballRenderer
+ XXX.renderer.entity.DrownedRenderer
- XXX.renderer.entity.ElderGuardianRenderer
+ XXX.renderer.entity.EndCrystalRenderer
- XXX.renderer.entity.EnderDragonRenderer
+ XXX.renderer.entity.EndermanRenderer
- XXX.renderer.entity.EndermiteRenderer
+ XXX.renderer.entity.EntityRenderDispatcher
- XXX.renderer.entity.EntityRenderer
+ XXX.renderer.entity.EntityRendererProvider
- XXX.renderer.entity.EntityRendererProvider$Context
+ XXX.renderer.entity.EntityRenderers
- XXX.renderer.entity.EvokerFangsRenderer
+ XXX.renderer.entity.EvokerRenderer
- XXX.renderer.entity.EvokerRenderer$1
+ XXX.renderer.entity.ExperienceOrbRenderer
- XXX.renderer.entity.FallingBlockRenderer
+ XXX.renderer.entity.FireworkEntityRenderer
- XXX.renderer.entity.FishingHookRenderer
+ XXX.renderer.entity.FoxRenderer
- XXX.renderer.entity.FrogRenderer
+ XXX.renderer.entity.GhastRenderer
- XXX.renderer.entity.GiantMobRenderer
+ XXX.renderer.entity.GlowSquidRenderer
- XXX.renderer.entity.GoatRenderer
+ XXX.renderer.entity.GuardianRenderer
- XXX.renderer.entity.HappyGhastRenderer
+ XXX.renderer.entity.HoglinRenderer
- XXX.renderer.entity.HorseRenderer
+ XXX.renderer.entity.HumanoidMobRenderer
- XXX.renderer.entity.HuskRenderer
+ XXX.renderer.entity.IllagerRenderer
- XXX.renderer.entity.IllusionerRenderer
+ XXX.renderer.entity.IllusionerRenderer$1
- XXX.renderer.entity.IronGolemRenderer
+ XXX.renderer.entity.ItemEntityRenderer
- XXX.renderer.entity.ItemFrameRenderer
+ XXX.renderer.entity.ItemRenderer
- XXX.renderer.entity.LeashKnotRenderer
+ XXX.renderer.entity.LightningBoltRenderer
- XXX.renderer.entity.LivingEntityRenderer
+ XXX.renderer.entity.LivingEntityRenderer$1
- XXX.renderer.entity.LlamaRenderer
+ XXX.renderer.entity.LlamaRenderer$1
- XXX.renderer.entity.LlamaSpitRenderer
+ XXX.renderer.entity.MagmaCubeRenderer
- XXX.renderer.entity.MinecartRenderer
+ XXX.renderer.entity.MobRenderer
- XXX.renderer.entity.MushroomCowRenderer
+ XXX.renderer.entity.NoopRenderer
- XXX.renderer.entity.OcelotRenderer
+ XXX.renderer.entity.OminousItemSpawnerRenderer
- XXX.renderer.entity.package-info
- XXX.renderer.entity.PaintingRenderer
+ XXX.renderer.entity.PaintingRenderer$1
- XXX.renderer.entity.PandaRenderer
+ XXX.renderer.entity.ParrotRenderer
- XXX.renderer.entity.ParrotRenderer$1
+ XXX.renderer.entity.PhantomRenderer
+ XXX.renderer.entity.PiglinRenderer
- XXX.renderer.entity.PigRenderer
- XXX.renderer.entity.PillagerRenderer
+ XXX.renderer.entity.PolarBearRenderer
- XXX.renderer.entity.PufferfishRenderer
+ XXX.renderer.entity.RabbitRenderer
- XXX.renderer.entity.RabbitRenderer$1
+ XXX.renderer.entity.RaftRenderer
- XXX.renderer.entity.RavagerRenderer
+ XXX.renderer.entity.RenderLayerParent
- XXX.renderer.entity.SalmonRenderer
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
- XXX.renderer.fog.FogData
+ XXX.renderer.fog.FogRenderer
- XXX.renderer.fog.FogRenderer$FogMode
+ XXX.renderer.fog.package-info
- XXX.renderer.item.BlockModelWrapper
+ XXX.renderer.item.BlockModelWrapper$Unbaked
- XXX.renderer.item.BundleSelectedItemSpecialRenderer
+ XXX.renderer.item.BundleSelectedItemSpecialRenderer$Unbaked
- XXX.renderer.item.ClientItem
+ XXX.renderer.item.ClientItem$Properties
- XXX.renderer.item.CompositeModel
+ XXX.renderer.item.CompositeModel$Unbaked
- XXX.renderer.item.ConditionalItemModel
+ XXX.renderer.item.ConditionalItemModel$Unbaked
- XXX.renderer.item.EmptyModel
+ XXX.renderer.item.EmptyModel$Unbaked
- XXX.renderer.item.ItemModel
+ XXX.renderer.item.ItemModel$BakingContext
- XXX.renderer.item.ItemModel$Unbaked
+ XXX.renderer.item.ItemModelResolver
- XXX.renderer.item.ItemModels
+ XXX.renderer.item.ItemStackRenderState
- XXX.renderer.item.ItemStackRenderState$FoilType
+ XXX.renderer.item.ItemStackRenderState$LayerRenderState
- XXX.renderer.item.MissingItemModel
+ XXX.renderer.item.ModelRenderProperties
- XXX.renderer.item.package-info
- XXX.renderer.item.RangeSelectItemModel
+ XXX.renderer.item.RangeSelectItemModel$Entry
- XXX.renderer.item.RangeSelectItemModel$Unbaked
+ XXX.renderer.item.SelectItemModel
- XXX.renderer.item.SelectItemModel$ModelSelector
+ XXX.renderer.item.SelectItemModel$SwitchCase
- XXX.renderer.item.SelectItemModel$Unbaked
+ XXX.renderer.item.SelectItemModel$UnbakedSwitch
- XXX.renderer.item.SpecialModelWrapper
+ XXX.renderer.item.SpecialModelWrapper$Unbaked
- XXX.renderer.special.BannerSpecialRenderer
+ XXX.renderer.special.BannerSpecialRenderer$Unbaked
- XXX.renderer.special.BedSpecialRenderer
+ XXX.renderer.special.BedSpecialRenderer$Unbaked
- XXX.renderer.special.ChestSpecialRenderer
+ XXX.renderer.special.ChestSpecialRenderer$Unbaked
- XXX.renderer.special.ConduitSpecialRenderer
+ XXX.renderer.special.ConduitSpecialRenderer$Unbaked
- XXX.renderer.special.DecoratedPotSpecialRenderer
+ XXX.renderer.special.DecoratedPotSpecialRenderer$Unbaked
- XXX.renderer.special.HangingSignSpecialRenderer
+ XXX.renderer.special.HangingSignSpecialRenderer$Unbaked
- XXX.renderer.special.NoDataSpecialModelRenderer
- XXX.renderer.special.package-info
+ XXX.renderer.special.ShieldSpecialRenderer
- XXX.renderer.special.ShieldSpecialRenderer$Unbaked
+ XXX.renderer.special.ShulkerBoxSpecialRenderer
- XXX.renderer.special.ShulkerBoxSpecialRenderer$Unbaked
+ XXX.renderer.special.SkullSpecialRenderer
- XXX.renderer.special.SkullSpecialRenderer$Unbaked
+ XXX.renderer.special.SpecialModelRenderer
- XXX.renderer.special.SpecialModelRenderer$Unbaked
+ XXX.renderer.special.SpecialModelRenderers
- XXX.renderer.special.StandingSignSpecialRenderer
+ XXX.renderer.special.StandingSignSpecialRenderer$Unbaked
- XXX.renderer.special.TridentSpecialRenderer
+ XXX.renderer.special.TridentSpecialRenderer$Unbaked
+ XXX.renderer.state.MapRenderState
- XXX.renderer.state.MapRenderState$MapDecorationRenderState
+ XXX.renderer.state.package-info
- XXX.renderer.texture.AbstractTexture
+ XXX.renderer.texture.CubeMapTexture
- XXX.renderer.texture.Dumpable
+ XXX.renderer.texture.DynamicTexture
- XXX.renderer.texture.MipmapGenerator
+ XXX.renderer.texture.MissingTextureAtlasSprite
- XXX.renderer.texture.OverlayTexture
- XXX.renderer.texture.package-info
+ XXX.renderer.texture.ReloadableTexture
- XXX.renderer.texture.SimpleTexture
+ XXX.renderer.texture.SkinTextureDownloader
- XXX.renderer.texture.SpriteContents
+ XXX.renderer.texture.SpriteContents$AnimatedTexture
- XXX.renderer.texture.SpriteContents$FrameInfo
+ XXX.renderer.texture.SpriteContents$InterpolationData
- XXX.renderer.texture.SpriteContents$Ticker
+ XXX.renderer.texture.SpriteLoader
- XXX.renderer.texture.SpriteLoader$Preparations
+ XXX.renderer.texture.SpriteTicker
- XXX.renderer.texture.Stitcher
+ XXX.renderer.texture.Stitcher$Entry
- XXX.renderer.texture.Stitcher$Holder
+ XXX.renderer.texture.Stitcher$Region
- XXX.renderer.texture.Stitcher$SpriteLoader
+ XXX.renderer.texture.StitcherException
- XXX.renderer.texture.TextureAtlas
+ XXX.renderer.texture.TextureAtlasSprite
- XXX.renderer.texture.TextureAtlasSprite$1
+ XXX.renderer.texture.TextureAtlasSprite$Ticker
- XXX.renderer.texture.TextureContents
+ XXX.renderer.texture.TextureManager
- XXX.renderer.texture.TextureManager$PendingReload
+ XXX.renderer.texture.Tickable
+ XXX.resources.language.ClientLanguage
- XXX.resources.language.FormattedBidiReorder
+ XXX.resources.language.I18n
- XXX.resources.language.LanguageInfo
+ XXX.resources.language.LanguageManager
- XXX.resources.language.package-info
+ XXX.resources.metadata.package-info
- XXX.resources.model.AtlasIds
+ XXX.resources.model.AtlasSet
- XXX.resources.model.AtlasSet$AtlasEntry
+ XXX.resources.model.AtlasSet$StitchResult
- XXX.resources.model.BlockModelRotation
+ XXX.resources.model.BlockModelRotation$WithUvLock
- XXX.resources.model.BlockStateDefinitions
+ XXX.resources.model.BlockStateModelLoader
- XXX.resources.model.BlockStateModelLoader$LoadedBlockModelDefinition
+ XXX.resources.model.BlockStateModelLoader$LoadedModels
- XXX.resources.model.ClientItemInfoLoader
+ XXX.resources.model.ClientItemInfoLoader$LoadedClientInfos
- XXX.resources.model.ClientItemInfoLoader$PendingLoad
+ XXX.resources.model.EquipmentAssetManager
- XXX.resources.model.EquipmentClientInfo
+ XXX.resources.model.EquipmentClientInfo$Builder
- XXX.resources.model.EquipmentClientInfo$Dyeable
+ XXX.resources.model.EquipmentClientInfo$Layer
- XXX.resources.model.EquipmentClientInfo$LayerType
+ XXX.resources.model.Material
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
+ XXX.resources.sounds.ElytraOnPlayerSoundInstance
- XXX.resources.sounds.EntityBoundSoundInstance
+ XXX.resources.sounds.GuardianAttackSoundInstance
- XXX.resources.sounds.MinecartSoundInstance
- XXX.resources.sounds.package-info
+ XXX.resources.sounds.RidingHappyGhastSoundInstance
- XXX.resources.sounds.RidingMinecartSoundInstance
+ XXX.resources.sounds.SimpleSoundInstance
- XXX.resources.sounds.SnifferSoundInstance
+ XXX.resources.sounds.Sound
- XXX.resources.sounds.Sound$Type
+ XXX.resources.sounds.SoundEventRegistration
- XXX.resources.sounds.SoundEventRegistrationSerializer
+ XXX.resources.sounds.SoundInstance
- XXX.resources.sounds.SoundInstance$Attenuation
+ XXX.resources.sounds.TickableSoundInstance
- XXX.resources.sounds.UnderwaterAmbientSoundHandler
+ XXX.resources.sounds.UnderwaterAmbientSoundInstances
- XXX.resources.sounds.UnderwaterAmbientSoundInstances$SubSound
+ XXX.resources.sounds.UnderwaterAmbientSoundInstances$UnderwaterAmbientSoundInstance
- XXX.screens.achievement.package-info
- XXX.screens.achievement.StatsScreen
+ XXX.screens.achievement.StatsScreen$GeneralStatisticsList
- XXX.screens.achievement.StatsScreen$GeneralStatisticsList$Entry
+ XXX.screens.achievement.StatsScreen$ItemStatisticsList
- XXX.screens.achievement.StatsScreen$ItemStatisticsList$ItemRow
+ XXX.screens.achievement.StatsScreen$ItemStatisticsList$ItemRowComparator
- XXX.screens.achievement.StatsScreen$MobsStatisticsList
+ XXX.screens.achievement.StatsScreen$MobsStatisticsList$MobRow
+ XXX.screens.advancements.AdvancementsScreen
+ XXX.screens.advancements.AdvancementTab
- XXX.screens.advancements.AdvancementTabType
+ XXX.screens.advancements.AdvancementTabType$Sprites
- XXX.screens.advancements.AdvancementWidget
+ XXX.screens.advancements.AdvancementWidgetType
- XXX.screens.advancements.AdvancementWidgetType$1
- XXX.screens.advancements.package-info
+ XXX.screens.configuration.package-info
- XXX.screens.configuration.RealmsBackupInfoScreen
+ XXX.screens.configuration.RealmsBackupInfoScreen$BackupInfoList
- XXX.screens.configuration.RealmsBackupInfoScreen$BackupInfoListEntry
+ XXX.screens.configuration.RealmsBackupScreen
- XXX.screens.configuration.RealmsBackupScreen$1
+ XXX.screens.configuration.RealmsBackupScreen$BackupObjectSelectionList
- XXX.screens.configuration.RealmsBackupScreen$Entry
+ XXX.screens.configuration.RealmsConfigurationTab
- XXX.screens.configuration.RealmsConfigureWorldScreen
+ XXX.screens.configuration.RealmsInviteScreen
- XXX.screens.configuration.RealmsPlayersTab
+ XXX.screens.configuration.RealmsPlayersTab$Entry
- XXX.screens.configuration.RealmsPlayersTab$InvitedObjectSelectionList
+ XXX.screens.configuration.RealmsPreferredRegionSelectionScreen
- XXX.screens.configuration.RealmsPreferredRegionSelectionScreen$RegionSelectionList
+ XXX.screens.configuration.RealmsPreferredRegionSelectionScreen$RegionSelectionList$Entry
- XXX.screens.configuration.RealmsSettingsTab
+ XXX.screens.configuration.RealmsSettingsTab$RegionSelection
- XXX.screens.configuration.RealmsSlotOptionsScreen
+ XXX.screens.configuration.RealmsSlotOptionsScreen$SettingsSlider
- XXX.screens.configuration.RealmsSubscriptionTab
+ XXX.screens.configuration.RealmsWorldsTab
- XXX.screens.configuration.RealmsWorldsTab$1
+ XXX.screens.debug.GameModeSwitcherScreen
- XXX.screens.debug.GameModeSwitcherScreen$1
+ XXX.screens.debug.GameModeSwitcherScreen$GameModeIcon
- XXX.screens.debug.GameModeSwitcherScreen$GameModeSlot
+ XXX.screens.debug.package-info
- XXX.screens.dialog.ButtonListDialogScreen
- XXX.screens.dialog.DialogScreen
- XXX.screens.dialog.DialogScreens$Factory
- XXX.screens.dialog.MultiActionInputFormDialogScreen
- XXX.screens.dialog.ServerLinksDialogScreen
- XXX.screens.dialog.SimpleInputFormDialogScreen
- XXX.screens.inventory.AbstractCommandBlockEditScreen
+ XXX.screens.inventory.AbstractCommandBlockEditScreen$1
- XXX.screens.inventory.AbstractContainerScreen
+ XXX.screens.inventory.AbstractContainerScreen$SnapbackData
- XXX.screens.inventory.AbstractFurnaceScreen
+ XXX.screens.inventory.AbstractRecipeBookScreen
- XXX.screens.inventory.AbstractSignEditScreen
+ XXX.screens.inventory.AnvilScreen
- XXX.screens.inventory.BeaconScreen
+ XXX.screens.inventory.BeaconScreen$1
- XXX.screens.inventory.BeaconScreen$BeaconButton
+ XXX.screens.inventory.BeaconScreen$BeaconCancelButton
- XXX.screens.inventory.BeaconScreen$BeaconConfirmButton
+ XXX.screens.inventory.BeaconScreen$BeaconPowerButton
- XXX.screens.inventory.BeaconScreen$BeaconScreenButton
+ XXX.screens.inventory.BeaconScreen$BeaconSpriteScreenButton
- XXX.screens.inventory.BeaconScreen$BeaconUpgradePowerButton
+ XXX.screens.inventory.BlastFurnaceScreen
- XXX.screens.inventory.BookEditScreen
+ XXX.screens.inventory.BookSignScreen
- XXX.screens.inventory.BookViewScreen
+ XXX.screens.inventory.BookViewScreen$BookAccess
- XXX.screens.inventory.BrewingStandScreen
+ XXX.screens.inventory.CartographyTableScreen
- XXX.screens.inventory.CommandBlockEditScreen
+ XXX.screens.inventory.CommandBlockEditScreen$1
- XXX.screens.inventory.ContainerScreen
+ XXX.screens.inventory.CrafterScreen
- XXX.screens.inventory.CrafterScreen$1
+ XXX.screens.inventory.CraftingScreen
- XXX.screens.inventory.CreativeInventoryListener
+ XXX.screens.inventory.CreativeModeInventoryScreen
- XXX.screens.inventory.CreativeModeInventoryScreen$CustomCreativeSlot
+ XXX.screens.inventory.CreativeModeInventoryScreen$ItemPickerMenu
- XXX.screens.inventory.CreativeModeInventoryScreen$SlotWrapper
+ XXX.screens.inventory.CyclingSlotBackground
- XXX.screens.inventory.DispenserScreen
+ XXX.screens.inventory.EffectsInInventory
- XXX.screens.inventory.EnchantmentNames
+ XXX.screens.inventory.EnchantmentScreen
- XXX.screens.inventory.FurnaceScreen
+ XXX.screens.inventory.GrindstoneScreen
- XXX.screens.inventory.HangingSignEditScreen
+ XXX.screens.inventory.HopperScreen
- XXX.screens.inventory.HorseInventoryScreen
+ XXX.screens.inventory.InventoryScreen
- XXX.screens.inventory.ItemCombinerScreen
+ XXX.screens.inventory.JigsawBlockEditScreen
- XXX.screens.inventory.JigsawBlockEditScreen$1
+ XXX.screens.inventory.LecternScreen
- XXX.screens.inventory.LecternScreen$1
+ XXX.screens.inventory.LoomScreen
- XXX.screens.inventory.MenuAccess
+ XXX.screens.inventory.MerchantScreen
- XXX.screens.inventory.MerchantScreen$TradeOfferButton
+ XXX.screens.inventory.MinecartCommandBlockEditScreen
- XXX.screens.inventory.package-info
- XXX.screens.inventory.PageButton
+ XXX.screens.inventory.ShulkerBoxScreen
- XXX.screens.inventory.SignEditScreen
+ XXX.screens.inventory.SmithingScreen
- XXX.screens.inventory.SmokerScreen
+ XXX.screens.inventory.StonecutterScreen
- XXX.screens.inventory.StructureBlockEditScreen
+ XXX.screens.inventory.StructureBlockEditScreen$1
- XXX.screens.inventory.StructureBlockEditScreen$2
+ XXX.screens.inventory.TestBlockEditScreen
- XXX.screens.inventory.TestInstanceBlockEditScreen
+ XXX.screens.inventory.TestInstanceBlockEditScreen$1
- XXX.screens.multiplayer.JoinMultiplayerScreen
+ XXX.screens.multiplayer.SafetyScreen
+ XXX.screens.multiplayer.ServerLinksScreen$LinkList
+ XXX.screens.worldselection.InitialWorldCreationOptions
- XXX.screens.worldselection.OptimizeWorldScreen
+ XXX.screens.worldselection.package-info
+ XXX.screens.worldselection.PresetEditor
- XXX.screens.worldselection.SelectWorldScreen
+ XXX.screens.worldselection.SwitchGrid
- XXX.screens.worldselection.SwitchGrid$Builder
+ XXX.screens.worldselection.SwitchGrid$InfoUnderneathSettings
- XXX.screens.worldselection.SwitchGrid$LabeledSwitch
+ XXX.screens.worldselection.SwitchGrid$SwitchBuilder
- XXX.screens.worldselection.WorldCreationContext
+ XXX.screens.worldselection.WorldCreationContext$DimensionsUpdater
- XXX.screens.worldselection.WorldCreationContext$OptionsModifier
+ XXX.screens.worldselection.WorldCreationContextMapper
- XXX.screens.worldselection.WorldCreationUiState
+ XXX.screens.worldselection.WorldCreationUiState$SelectedGameMode
- XXX.screens.worldselection.WorldCreationUiState$WorldTypeEntry
+ XXX.screens.worldselection.WorldOpenFlows
- XXX.screens.worldselection.WorldOpenFlows$1Data
+ XXX.screens.worldselection.WorldSelectionList
- XXX.screens.worldselection.WorldSelectionList$Entry
+ XXX.screens.worldselection.WorldSelectionList$LoadingHeader
- XXX.screens.worldselection.WorldSelectionList$WorldListEntry
- XXX.server.commands.DialogCommand
+ XXX.server.commands.DifficultyCommand
- XXX.server.commands.EffectCommands
+ XXX.server.commands.EmoteCommands
- XXX.server.commands.EnchantCommand
+ XXX.server.commands.ExecuteCommand
- XXX.server.commands.ExecuteCommand$CommandNumericPredicate
+ XXX.server.commands.ExecuteCommand$CommandPredicate
- XXX.server.commands.ExecuteCommand$ExecuteIfFunctionCustomModifier
+ XXX.server.commands.ExecuteCommand$IntBiPredicate
- XXX.server.commands.ExperienceCommand
+ XXX.server.commands.ExperienceCommand$Type
- XXX.server.commands.FillBiomeCommand
+ XXX.server.commands.FillCommand
- XXX.server.commands.FillCommand$1UpdatedPosition
+ XXX.server.commands.FillCommand$Affector
- XXX.server.commands.FillCommand$Filter
+ XXX.server.commands.FillCommand$Mode
- XXX.server.commands.FillCommand$NullableCommandFunction
+ XXX.server.commands.ForceLoadCommand
- XXX.server.commands.FunctionCommand
+ XXX.server.commands.FunctionCommand$1
- XXX.server.commands.FunctionCommand$1Accumulator
+ XXX.server.commands.FunctionCommand$2
- XXX.server.commands.FunctionCommand$3
+ XXX.server.commands.FunctionCommand$4
- XXX.server.commands.FunctionCommand$5
+ XXX.server.commands.FunctionCommand$Callbacks
- XXX.server.commands.FunctionCommand$FunctionCustomExecutor
+ XXX.server.commands.GameModeCommand
- XXX.server.commands.GameRuleCommand
+ XXX.server.commands.GameRuleCommand$1
- XXX.server.commands.GiveCommand
+ XXX.server.commands.HelpCommand
- XXX.server.commands.InCommandFunction
+ XXX.server.commands.ItemCommands
- XXX.server.commands.JfrCommand
+ XXX.server.commands.KickCommand
- XXX.server.commands.KillCommand
+ XXX.server.commands.ListPlayersCommand
- XXX.server.commands.LocateCommand
+ XXX.server.commands.LookAt
- XXX.server.commands.LookAt$LookAtEntity
+ XXX.server.commands.LookAt$LookAtPosition
- XXX.server.commands.LootCommand
+ XXX.server.commands.LootCommand$Callback
- XXX.server.commands.LootCommand$DropConsumer
+ XXX.server.commands.LootCommand$TailProvider
- XXX.server.commands.MsgCommand
+ XXX.server.commands.OpCommand
- XXX.server.commands.PardonCommand
+ XXX.server.commands.PardonIpCommand
- XXX.server.commands.ParticleCommand
+ XXX.server.commands.PerfCommand
- XXX.server.commands.PermissionCheck
- XXX.server.dialog.ButtonListDialog
- XXX.server.dialog.CommonButtonData
- XXX.server.dialog.ConfirmationDialog
- XXX.server.dialog.DialogListDialog
- XXX.server.dialog.Dialogs
- XXX.server.dialog.InputFormDialog$Input
- XXX.server.dialog.MultiActionDialog
- XXX.server.dialog.NoticeDialog
- XXX.server.dialog.package-info
- XXX.server.dialog.SimpleDialog
+ XXX.server.gui.MinecraftServerGui
- XXX.server.gui.MinecraftServerGui$1
+ XXX.server.gui.MinecraftServerGui$2
- XXX.server.gui.package-info
- XXX.server.gui.PlayerListComponent
+ XXX.server.gui.StatsComponent
+ XXX.server.level.BlockDestructionProgress
- XXX.server.level.ChunkGenerationTask
+ XXX.server.level.ChunkHolder
- XXX.server.level.ChunkHolder$LevelChangeListener
+ XXX.server.level.ChunkHolder$PlayerProvider
- XXX.server.level.ChunkLevel
+ XXX.server.level.ChunkLevel$1
- XXX.server.level.ChunkMap
+ XXX.server.level.ChunkMap$DistanceManager
- XXX.server.level.ChunkMap$TrackedEntity
+ XXX.server.level.ChunkResult
- XXX.server.level.ChunkResult$Fail
+ XXX.server.level.ChunkResult$Success
- XXX.server.level.ChunkTaskDispatcher
+ XXX.server.level.ChunkTaskPriorityQueue
- XXX.server.level.ChunkTaskPriorityQueue$TasksForChunk
+ XXX.server.level.ChunkTracker
- XXX.server.level.ChunkTrackingView
+ XXX.server.level.ChunkTrackingView$1
- XXX.server.level.ChunkTrackingView$Positioned
+ XXX.server.level.ClientInformation
- XXX.server.level.ColumnPos
+ XXX.server.level.DemoMode
- XXX.server.level.DistanceManager
+ XXX.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
- XXX.server.level.DistanceManager$PlayerTicketTracker
+ XXX.server.level.FullChunkStatus
- XXX.server.level.GeneratingChunkMap
+ XXX.server.level.GenerationChunkHolder
- XXX.server.level.LoadingChunkTracker
+ XXX.server.level.package-info
+ XXX.server.level.ParticleStatus
- XXX.server.level.PlayerMap
+ XXX.server.level.PlayerRespawnLogic
- XXX.server.level.SectionTracker
+ XXX.server.level.ServerBossEvent
- XXX.server.level.ServerChunkCache
+ XXX.server.level.ServerChunkCache$MainThreadExecutor
- XXX.server.level.ServerEntity
+ XXX.server.level.ServerEntityGetter
- XXX.server.level.ServerLevel
+ XXX.server.level.ServerLevel$1
- XXX.server.level.ServerLevel$EntityCallbacks
+ XXX.server.level.ServerPlayer
- XXX.server.level.ServerPlayer$1
+ XXX.server.level.ServerPlayer$1$1
- XXX.server.level.ServerPlayer$2
+ XXX.server.level.ServerPlayer$3
- XXX.server.level.ServerPlayer$RespawnConfig
+ XXX.server.level.ServerPlayer$RespawnPosAngle
- XXX.server.level.ServerPlayerGameMode
+ XXX.server.level.SimulationChunkTracker
- XXX.server.level.ThreadedLevelLightEngine
+ XXX.server.level.ThreadedLevelLightEngine$TaskType
- XXX.server.level.ThrottlingChunkTaskDispatcher
+ XXX.server.level.Ticket
- XXX.server.level.TicketType
+ XXX.server.level.TicketType$TicketUse
- XXX.server.level.WorldGenRegion
- XXX.server.network.CommonListenerCookie
+ XXX.server.network.ConfigurationTask
- XXX.server.network.ConfigurationTask$Type
+ XXX.server.network.Filterable
- XXX.server.network.FilteredText
+ XXX.server.network.LegacyProtocolUtils
- XXX.server.network.LegacyQueryHandler
+ XXX.server.network.LegacyTextFilter
- XXX.server.network.LegacyTextFilter$1
+ XXX.server.network.LegacyTextFilter$JoinOrLeaveEncoder
- XXX.server.network.MemoryServerHandshakePacketListenerImpl
- XXX.server.network.package-info
+ XXX.server.network.PlayerChunkSender
- XXX.server.network.PlayerSafetyServiceTextFilter
+ XXX.server.network.ServerCommonPacketListenerImpl
- XXX.server.network.ServerConfigurationPacketListenerImpl
+ XXX.server.network.ServerConnectionListener
- XXX.server.network.ServerConnectionListener$1
+ XXX.server.network.ServerConnectionListener$2
- XXX.server.network.ServerConnectionListener$LatencySimulator
+ XXX.server.network.ServerConnectionListener$LatencySimulator$DelayedMessage
- XXX.server.network.ServerGamePacketListenerImpl
+ XXX.server.network.ServerGamePacketListenerImpl$1
- XXX.server.network.ServerGamePacketListenerImpl$2
+ XXX.server.network.ServerGamePacketListenerImpl$EntityInteraction
- XXX.server.network.ServerHandshakePacketListenerImpl
+ XXX.server.network.ServerHandshakePacketListenerImpl$1
- XXX.server.network.ServerLoginPacketListenerImpl
+ XXX.server.network.ServerLoginPacketListenerImpl$1
- XXX.server.network.ServerLoginPacketListenerImpl$State
+ XXX.server.network.ServerPlayerConnection
- XXX.server.network.ServerStatusPacketListenerImpl
+ XXX.server.network.ServerTextFilter
- XXX.server.network.ServerTextFilter$IgnoreStrategy
+ XXX.server.network.ServerTextFilter$MessageEncoder
- XXX.server.network.ServerTextFilter$PlayerContext
+ XXX.server.network.ServerTextFilter$RequestFailedException
- XXX.server.network.TextFilter
+ XXX.server.network.TextFilter$1
- XXX.server.packs.AbstractPackResources
+ XXX.server.packs.BuiltInMetadata
- XXX.server.packs.CompositePackResources
+ XXX.server.packs.DownloadCacheCleaner
- XXX.server.packs.DownloadCacheCleaner$1
+ XXX.server.packs.DownloadCacheCleaner$PathAndPriority
- XXX.server.packs.DownloadCacheCleaner$PathAndTime
+ XXX.server.packs.DownloadQueue
- XXX.server.packs.DownloadQueue$BatchConfig
+ XXX.server.packs.DownloadQueue$BatchResult
- XXX.server.packs.DownloadQueue$DownloadRequest
+ XXX.server.packs.DownloadQueue$FileInfoEntry
- XXX.server.packs.DownloadQueue$LogEntry
+ XXX.server.packs.FeatureFlagsMetadataSection
- XXX.server.packs.FilePackResources
+ XXX.server.packs.FilePackResources$FileResourcesSupplier
- XXX.server.packs.FilePackResources$SharedZipFileAccess
+ XXX.server.packs.OverlayMetadataSection
- XXX.server.packs.OverlayMetadataSection$OverlayEntry
- XXX.server.packs.package-info
+ XXX.server.packs.PackLocationInfo
- XXX.server.packs.PackResources
+ XXX.server.packs.PackResources$ResourceOutput
- XXX.server.packs.PackSelectionConfig
+ XXX.server.packs.PackType
- XXX.server.packs.PathPackResources
+ XXX.server.packs.PathPackResources$PathResourcesSupplier
- XXX.server.packs.VanillaPackResources
+ XXX.server.packs.VanillaPackResourcesBuilder
- XXX.server.players.BanListEntry
+ XXX.server.players.GameProfileCache
- XXX.server.players.GameProfileCache$GameProfileInfo
+ XXX.server.players.IpBanList
- XXX.server.players.IpBanListEntry
+ XXX.server.players.OldUsersConverter
- XXX.server.players.OldUsersConverter$1
+ XXX.server.players.OldUsersConverter$2
- XXX.server.players.OldUsersConverter$3
+ XXX.server.players.OldUsersConverter$4
- XXX.server.players.OldUsersConverter$5
+ XXX.server.players.OldUsersConverter$ConversionError
+ XXX.server.players.package-info
- XXX.server.players.PlayerList
+ XXX.server.players.PlayerList$1
- XXX.server.players.ServerOpList
+ XXX.server.players.ServerOpListEntry
- XXX.server.players.SleepStatus
+ XXX.server.players.StoredUserEntry
- XXX.server.players.StoredUserList
+ XXX.server.players.UserBanList
- XXX.server.players.UserBanListEntry
+ XXX.server.players.UserWhiteList
- XXX.server.players.UserWhiteListEntry
- XXX.server.rcon.NetworkDataOutputStream
+ XXX.server.rcon.package-info
+ XXX.server.rcon.PktUtils
- XXX.server.rcon.RconConsoleSource
- XXX.server.waypoints.ServerWaypointManager
+ XXX.spectator.categories.package-info
+ XXX.spectator.categories.SpectatorPage
- XXX.spectator.categories.TeleportToPlayerMenuCategory
+ XXX.spectator.categories.TeleportToTeamMenuCategory
- XXX.spectator.categories.TeleportToTeamMenuCategory$TeamSelectionItem
+ XXX.state.pip.GuiBannerResultRenderState
- XXX.state.pip.GuiBookModelRenderState
+ XXX.state.pip.GuiEntityRenderState
- XXX.state.pip.GuiProfilerChartRenderState
+ XXX.state.pip.GuiSignRenderState
- XXX.state.pip.GuiSkinRenderState
- XXX.state.pip.package-info
+ XXX.state.pip.PictureInPictureRenderState
+ XXX.texture.atlas.package-info
- XXX.texture.atlas.SpriteResourceLoader
+ XXX.texture.atlas.SpriteSource
- XXX.texture.atlas.SpriteSource$Output
+ XXX.texture.atlas.SpriteSource$SpriteSupplier
- XXX.texture.atlas.SpriteSourceList
+ XXX.texture.atlas.SpriteSourceList$1
- XXX.texture.atlas.SpriteSources
- XXX.util.task.CloseServerTask
+ XXX.util.task.ConnectTask
- XXX.util.task.DownloadTask
+ XXX.util.task.GetServerDetailsTask
- XXX.util.task.LongRunningTask
+ XXX.util.task.OpenServerTask
- XXX.util.task.package-info
- XXX.util.task.RealmCreationTask
+ XXX.util.task.ResettingTemplateWorldTask
- XXX.util.task.ResettingWorldTask
+ XXX.util.task.RestoreTask
- XXX.util.task.SwitchMinigameTask
+ XXX.util.task.SwitchSlotTask
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
XXX.mojang.realmsclient.RealmsMainScreen -5P
```
```
XXX.realmsclient.client.RealmsClient +2M -2M
```
```
XXX.realmsclient.client.RealmsError$CustomError +1M | +2P
```
```
XXX.components.toasts.ToastManager$ToastInstance +1M
```
```
XXX.gui.font.GlyphRenderTypes +2M -1M | +1P
```
```
XXX.font.glyphs.BakedGlyph +9M -4M
```
```
XXX.font.glyphs.BakedGlyph$GlyphInstance +4M
```
```
XXX.render.state.GuiTextRenderState +2M -11M | +7P -2P
```
```
XXX.screens.options.SoundOptionsScreen +1M -3M
```
```
XXX.screens.worldselection.ExperimentsScreen -1M | +1P -1P
```
```
XXX.minecraft.commands.Commands +6M -7M | +1P
```
```
XXX.commands.synchronization.SuggestionProviders +2M -3M | +1P -1P
```
```
XXX.protocol.game.ClientboundCommandsPacket$ArgumentNodeStub +7M -3M
```
```
XXX.protocol.game.ClientboundCommandsPacket$LiteralNodeStub +5M -1M
```
```
XXX.protocol.game.ClientboundCommandsPacket$NodeStub +1P -1P
```
```
XXX.minecraft.realms.RealmsScreen +2M | +5P
```
```
XXX.minecraft.server.MinecraftServer +1M
```
```
XXX.minecraft.server.ReloadableServerRegistries$Holder +1M -2M
```
```
XXX.server.commands.AttributeCommand +12M -13M
```
```
XXX.server.commands.BanListCommands +4M -5M
```
```
XXX.server.commands.BossBarCommands +17M -18M
```
```
XXX.server.commands.ClearInventoryCommands +5M -6M
```
```
XXX.server.commands.DamageCommand +2M -3M
```
```
XXX.server.commands.DebugCommand +3M -5M
```
```
XXX.server.commands.DebugConfigCommand +4M -5M
```
```
XXX.server.commands.DebugPathCommand +2M -3M
```
```
XXX.server.commands.PlaySoundCommand +3M -4M
```
```
XXX.server.commands.RaidCommand +6M -7M
```
```
XXX.server.commands.RecipeCommand +3M -4M
```
```
XXX.server.commands.ReturnCommand -1M
```
```
XXX.server.commands.RideCommand +4M -5M
```
```
XXX.server.commands.SaveAllCommand +2M -3M
```
```
XXX.server.commands.SaveOnCommand +2M -3M
```
```
XXX.server.commands.ScheduleCommand +3M -4M
```
```
XXX.server.commands.ServerPackCommand +3M -4M
```
```
XXX.server.commands.SetSpawnCommand +2M -3M
```
```
XXX.server.commands.SpawnArmorTrimsCommand +4M -5M
```
```
XXX.server.commands.SpreadPlayersCommand +2M -3M
```
```
XXX.server.commands.StopCommand +2M -3M
```
```
XXX.server.commands.SummonCommand +3M -4M
```
```
XXX.server.commands.TeamCommand +19M -20M
```
```
XXX.server.commands.TeleportCommand +5M -7M
```
```
XXX.server.commands.TickCommand +18M -19M
```
```
XXX.server.commands.TitleCommand +5M -6M
```
```
XXX.server.commands.WardenSpawnTrackerCommand +4M -5M
```
```
XXX.server.commands.WeatherCommand +4M -5M
```
```
XXX.server.commands.WorldBorderCommand +9M -10M
```
```
XXX.commands.data.DataCommands +30M -31M
```
```
XXX.minecraft.world.Difficulty +1P
```
```
XXX.world.entity.Entity +2M -1M
```
```
XXX.world.entity.Leashable +1M
```
```
XXX.world.entity.Mob +1M
```
```
XXX.entity.animal.HappyGhast +2M | -1P
```
```
XXX.animal.sheep.Sheep -2M | -1P
```
```
XXX.animal.wolf.Wolf +1M
```
```
XXX.entity.player.Player +1M
```
```
XXX.world.item.Items +1P
```
```
XXX.item.equipment.Equippable +3M -1M | +2P
```
```
XXX.world.level.GameType +1P
```
```
XXX.level.block.DriedGhastBlock -1M
```
```
XXX.block.entity.SignBlockEntity +2M -2M
```

</details>
<details>
<summary>
com.mojang.realmsclient.client.RealmsClient
</summary>

```diff
- List invite(long,String)
- RealmsJoinInformation join(long)
+ RealmsServer invite(long,String)
+ RealmsServerAddress join(long)
```

</details>
<details>
<summary>
com.mojang.realmsclient.client.RealmsError$CustomError
</summary>

```diff
- RealmsError$CustomError htmlPayload(int,String)
```

</details>
<details>
<summary>
net.minecraft.client.gui.components.toasts.ToastManager$ToastInstance
</summary>

```diff
- void resetToast()
```

</details>
<details>
<summary>
net.minecraft.client.gui.font.GlyphRenderTypes
</summary>

```diff
- RenderPipeline guiPipeline()
- void <init>(RenderType,RenderType,RenderType,RenderPipeline)
+ void <init>(RenderType,RenderType,RenderType)
```

</details>
<details>
<summary>
net.minecraft.client.gui.font.glyphs.BakedGlyph
</summary>

```diff
- float bottom(BakedGlyph$GlyphInstance)
- float extraThickness(boolean)
- float left(BakedGlyph$GlyphInstance)
- float right(BakedGlyph$GlyphInstance)
- float shearBottom()
- float shearTop()
- float top(BakedGlyph$GlyphInstance)
- GpuTextureView textureView()
- RenderPipeline guiPipeline()
+ void extract(GuiRenderState,RenderType,boolean,float,float,int,boolean,boolean,GuiTextRenderState)
+ void extractBackground(GuiRenderState,RenderType,BakedGlyph$Effect,GuiTextRenderState)
+ void extractChar(GuiRenderState,RenderType,BakedGlyph$GlyphInstance,boolean,GuiTextRenderState)
+ void extractEffect(GuiRenderState,RenderType,BakedGlyph$Effect,boolean,GuiTextRenderState)
```

</details>
<details>
<summary>
net.minecraft.client.gui.font.glyphs.BakedGlyph$GlyphInstance
</summary>

```diff
- float bottom()
- float left()
- float right()
- float top()
```

</details>
<details>
<summary>
net.minecraft.client.gui.render.state.GuiTextRenderState
</summary>

```diff
+ boolean equals(Object)
- Font$PreparedText ensurePrepared()
+ int hashCode()
+ int x()
+ int y()
+ Matrix3x2f pose()
+ ScreenRectangle getBounds(int,int,TextRenderState,Matrix3x2f,ScreenRectangle)
+ ScreenRectangle scissorArea()
+ String toString()
+ TextRenderState textRenderState()
- void <init>(Font,FormattedCharSequence,Matrix3x2f,int,int,int,int,boolean,ScreenRectangle)
+ void <init>(TextRenderState,Matrix3x2f,int,int,ScreenRectangle,ScreenRectangle)
+ void <init>(TextRenderState,Matrix3x2f,int,int,ScreenRectangle)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.options.SoundOptionsScreen
</summary>

```diff
+ OptionInstance lambda$getAllSoundOptionsExceptMaster$1(SoundSource)
+ OptionInstance[] buttonOptions(Options)
- OptionInstance[] lambda$getAllSoundOptionsExceptMaster$1(int)
+ OptionInstance[] lambda$getAllSoundOptionsExceptMaster$2(int)
```

</details>
<details>
<summary>
net.minecraft.client.gui.screens.worldselection.ExperimentsScreen
</summary>

```diff
+ Minecraft access$000(ExperimentsScreen)
```

</details>
<details>
<summary>
net.minecraft.commands.Commands
</summary>

```diff
- boolean lambda$createValidator$5(Commands$ParseFunction,String)
+ boolean lambda$createValidator$7(Commands$ParseFunction,String)
+ boolean lambda$fillUsableCommands$5(SharedSuggestionProvider)
- boolean lambda$validate$7(ArgumentType)
+ boolean lambda$validate$9(ArgumentType)
+ int lambda$fillUsableCommands$6(CommandContext)
- PermissionCheck hasPermission(int)
+ String lambda$validate$10(ArgumentType)
- String lambda$validate$8(ArgumentType)
+ void fillUsableCommands(CommandNode,CommandNode,CommandSourceStack,Map)
- void fillUsableCommands(CommandNode,CommandNode,Object,Map)
- void lambda$validate$6(CommandDispatcher,CommandNode,CommandNode,CommandNode,Collection)
+ void lambda$validate$8(CommandDispatcher,CommandNode,CommandNode,CommandNode,Collection)
```

</details>
<details>
<summary>
net.minecraft.commands.synchronization.SuggestionProviders
</summary>

```diff
- CompletableFuture lambda$static$3(CommandContext,SuggestionsBuilder)
+ CompletableFuture lambda$static$4(CommandContext,SuggestionsBuilder)
+ Message lambda$static$3(EntityType)
- SuggestionProvider cast(SuggestionProvider)
+ SuggestionProvider safelySwap(SuggestionProvider)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundCommandsPacket$ArgumentNodeStub
</summary>

```diff
- ArgumentBuilder build(CommandBuildContext,ClientboundCommandsPacket$NodeBuilder)
+ ArgumentBuilder build(CommandBuildContext)
- ArgumentTypeInfo$Template argumentType()
- boolean equals(Object)
- int hashCode()
+ ResourceLocation getSuggestionId(SuggestionProvider)
- ResourceLocation suggestionId()
- String id()
- String toString()
+ void <init>(ArgumentCommandNode)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundCommandsPacket$LiteralNodeStub
</summary>

```diff
- ArgumentBuilder build(CommandBuildContext,ClientboundCommandsPacket$NodeBuilder)
+ ArgumentBuilder build(CommandBuildContext)
- boolean equals(Object)
- int hashCode()
- String id()
- String toString()
```

</details>
<details>
<summary>
net.minecraft.realms.RealmsScreen
</summary>

```diff
- ImageWidget realmsLogo()
- void <clinit>()
```

</details>
<details>
<summary>
net.minecraft.server.MinecraftServer
</summary>

```diff
- void handleCustomClickAction(ResourceLocation,Optional)
```

</details>
<details>
<summary>
net.minecraft.server.ReloadableServerRegistries$Holder
</summary>

```diff
+ Collection getKeys(ResourceKey)
+ HolderGetter$Provider lookup()
- HolderLookup$Provider lookup()
```

</details>
<details>
<summary>
net.minecraft.server.commands.AttributeCommand
</summary>

```diff
+ boolean lambda$register$4(CommandSourceStack)
- CompletableFuture lambda$register$13(CommandContext,SuggestionsBuilder)
+ CompletableFuture lambda$register$14(CommandContext,SuggestionsBuilder)
- CompletableFuture lambda$register$15(CommandContext,SuggestionsBuilder)
+ CompletableFuture lambda$register$16(CommandContext,SuggestionsBuilder)
- Component lambda$addModifier$23(ResourceLocation,Holder,Entity)
+ Component lambda$addModifier$24(ResourceLocation,Holder,Entity)
- Component lambda$getAttributeBase$19(Holder,Entity,double)
+ Component lambda$getAttributeBase$20(Holder,Entity,double)
- Component lambda$getAttributeModifier$20(ResourceLocation,Holder,Entity,double)
+ Component lambda$getAttributeModifier$21(ResourceLocation,Holder,Entity,double)
- Component lambda$getAttributeValue$18(Holder,Entity,double)
+ Component lambda$getAttributeValue$19(Holder,Entity,double)
- Component lambda$removeModifier$24(ResourceLocation,Holder,Entity)
+ Component lambda$removeModifier$25(ResourceLocation,Holder,Entity)
- Component lambda$resetAttributeBase$22(Holder,Entity,double)
+ Component lambda$resetAttributeBase$23(Holder,Entity,double)
- Component lambda$setAttributeBase$21(Holder,Entity,double)
+ Component lambda$setAttributeBase$22(Holder,Entity,double)
+ int lambda$register$13(CommandContext)
- int lambda$register$14(CommandContext)
+ int lambda$register$15(CommandContext)
- int lambda$register$16(CommandContext)
+ int lambda$register$18(CommandContext)
- int lambda$register$4(CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.BanListCommands
</summary>

```diff
+ boolean lambda$register$0(CommandSourceStack)
- Component lambda$showList$3()
+ Component lambda$showList$4()
- Component lambda$showList$4(Collection)
- Component lambda$showList$5(BanListEntry)
+ Component lambda$showList$5(Collection)
+ Component lambda$showList$6(BanListEntry)
- int lambda$register$0(CommandContext)
+ int lambda$register$3(CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.BossBarCommands
</summary>

```diff
+ boolean lambda$register$3(CommandSourceStack)
- Component lambda$createBar$45(CustomBossEvent)
+ Component lambda$createBar$46(CustomBossEvent)
- Component lambda$getMax$29(CustomBossEvent)
+ Component lambda$getMax$30(CustomBossEvent)
- Component lambda$getPlayers$32(CustomBossEvent)
+ Component lambda$getPlayers$34(CustomBossEvent)
- Component lambda$getValue$28(CustomBossEvent)
+ Component lambda$getValue$29(CustomBossEvent)
- Component lambda$getVisible$30(CustomBossEvent)
+ Component lambda$getVisible$32(CustomBossEvent)
- Component lambda$listBars$43()
+ Component lambda$listBars$44()
- Component lambda$listBars$44(Collection)
+ Component lambda$listBars$45(Collection)
- Component lambda$removeBar$46(CustomBossEvent)
+ Component lambda$removeBar$47(CustomBossEvent)
- Component lambda$setColor$38(CustomBossEvent)
+ Component lambda$setColor$39(CustomBossEvent)
- Component lambda$setMax$37(CustomBossEvent,int)
+ Component lambda$setMax$38(CustomBossEvent,int)
- Component lambda$setName$40(CustomBossEvent)
+ Component lambda$setName$41(CustomBossEvent)
- Component lambda$setPlayers$41(CustomBossEvent)
- Component lambda$setPlayers$42(CustomBossEvent,Collection)
+ Component lambda$setPlayers$42(CustomBossEvent)
+ Component lambda$setPlayers$43(CustomBossEvent,Collection)
- Component lambda$setStyle$39(CustomBossEvent)
+ Component lambda$setStyle$40(CustomBossEvent)
- Component lambda$setValue$36(CustomBossEvent,int)
+ Component lambda$setValue$37(CustomBossEvent,int)
- Component lambda$setVisible$34(CustomBossEvent)
+ Component lambda$setVisible$36(CustomBossEvent)
+ int lambda$register$28(CommandContext)
- int lambda$register$3(CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.ClearInventoryCommands
</summary>

```diff
+ boolean lambda$register$2(CommandSourceStack)
- boolean lambda$register$2(ItemStack)
+ boolean lambda$register$3(ItemStack)
- boolean lambda$register$4(ItemStack)
+ boolean lambda$register$5(ItemStack)
+ Component lambda$clearInventory$12(int,Collection)
- Component lambda$clearInventory$8(int,Collection)
- int lambda$register$3(CommandContext)
+ int lambda$register$4(CommandContext)
- int lambda$register$5(CommandContext)
+ int lambda$register$8(CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.DamageCommand
</summary>

```diff
+ boolean lambda$register$0(CommandSourceStack)
- Component lambda$damage$5(float,Entity)
+ Component lambda$damage$6(float,Entity)
- int lambda$register$0(CommandContext)
+ int lambda$register$5(CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.DebugCommand
</summary>

```diff
+ boolean lambda$register$0(CommandSourceStack)
+ boolean lambda$register$3(CommandSourceStack)
- Component lambda$start$2()
+ Component lambda$start$4()
- Component lambda$stop$3(double,ProfileResults,double)
+ Component lambda$stop$5(double,ProfileResults,double)
- int lambda$register$0(CommandContext)
+ int lambda$register$2(CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.DebugConfigCommand
</summary>

```diff
+ boolean lambda$register$0(CommandSourceStack)
- CompletableFuture lambda$register$1(CommandContext,SuggestionsBuilder)
+ CompletableFuture lambda$register$2(CommandContext,SuggestionsBuilder)
- Component lambda$config$3(GameProfile)
+ Component lambda$config$4(GameProfile)
- int lambda$register$0(CommandContext)
+ int lambda$register$1(CommandContext)
- int lambda$register$2(CommandContext)
+ int lambda$register$3(CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.DebugPathCommand
</summary>

```diff
+ boolean lambda$register$0(CommandSourceStack)
- Component lambda$fillBlocks$1()
+ Component lambda$fillBlocks$2()
- int lambda$register$0(CommandContext)
+ int lambda$register$1(CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.PlaySoundCommand
</summary>

```diff
+ boolean lambda$register$1(CommandSourceStack)
- Component lambda$playSound$7(ResourceLocation,List)
- Component lambda$playSound$8(ResourceLocation,int)
+ Component lambda$playSound$8(ResourceLocation,List)
+ Component lambda$playSound$9(ResourceLocation,int)
- int lambda$source$1(SoundSource,CommandContext)
+ int lambda$source$7(SoundSource,CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.RaidCommand
</summary>

```diff
+ boolean lambda$register$0(CommandSourceStack)
- Component lambda$check$11(StringBuilder)
+ Component lambda$check$13(StringBuilder)
- Component lambda$setRaidOmenLevel$7(int,int)
+ Component lambda$setRaidOmenLevel$8(int,int)
- Component lambda$spawnLeader$8()
+ Component lambda$spawnLeader$9()
+ Component lambda$start$10()
- Component lambda$start$9()
- Component lambda$stop$10()
+ Component lambda$stop$11()
- int lambda$register$0(CommandContext)
+ int lambda$register$7(CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.RecipeCommand
</summary>

```diff
+ boolean lambda$register$0(CommandSourceStack)
- Component lambda$giveRecipes$4(Collection,Collection)
+ Component lambda$giveRecipes$6(Collection,Collection)
- Component lambda$takeRecipes$6(Collection,Collection)
+ Component lambda$takeRecipes$8(Collection,Collection)
- int lambda$register$0(CommandContext)
+ int lambda$register$4(CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.ReturnCommand
</summary>

```diff
+ boolean lambda$register$0(ExecutionCommandSource)
```

</details>
<details>
<summary>
net.minecraft.server.commands.RideCommand
</summary>

```diff
- boolean lambda$mount$5(Entity,Entity)
+ boolean lambda$mount$6(Entity,Entity)
+ boolean lambda$register$3(CommandSourceStack)
- Component lambda$dismount$7(Entity,Entity)
+ Component lambda$dismount$8(Entity,Entity)
- Component lambda$mount$6(Entity,Entity)
+ Component lambda$mount$7(Entity,Entity)
- int lambda$register$3(CommandContext)
+ int lambda$register$5(CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.SaveAllCommand
</summary>

```diff
+ boolean lambda$register$0(CommandSourceStack)
- Component lambda$saveAll$2()
+ Component lambda$saveAll$4()
- int lambda$register$0(CommandContext)
+ int lambda$register$2(CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.SaveOnCommand
</summary>

```diff
+ boolean lambda$register$0(CommandSourceStack)
- Component lambda$register$0()
+ Component lambda$register$1()
- int lambda$register$1(CommandContext)
+ int lambda$register$2(CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.ScheduleCommand
</summary>

```diff
+ boolean lambda$register$2(CommandSourceStack)
- Component lambda$remove$8(int,String)
+ Component lambda$remove$9(int,String)
- Component lambda$schedule$6(ResourceLocation,int,long)
+ Component lambda$schedule$8(ResourceLocation,int,long)
- int lambda$register$2(CommandContext)
+ int lambda$register$6(CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.ServerPackCommand
</summary>

```diff
+ boolean lambda$register$0(CommandSourceStack)
- int lambda$register$0(CommandContext)
+ int lambda$register$4(CommandContext)
- UUID lambda$pushPack$5(String)
+ UUID lambda$pushPack$6(String)
- void lambda$sendToAllConnections$4(Packet,Connection)
+ void lambda$sendToAllConnections$5(Packet,Connection)
```

</details>
<details>
<summary>
net.minecraft.server.commands.SetSpawnCommand
</summary>

```diff
+ boolean lambda$register$0(CommandSourceStack)
- Component lambda$setSpawn$4(BlockPos,float,String,Collection)
+ Component lambda$setSpawn$6(BlockPos,float,String,Collection)
- int lambda$register$0(CommandContext)
+ int lambda$register$4(CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.SpawnArmorTrimsCommand
</summary>

```diff
+ boolean lambda$register$1(CommandSourceStack)
- Component lambda$spawnArmorTrims$5()
+ Component lambda$spawnArmorTrims$6()
- int lambda$register$1(CommandContext)
+ int lambda$register$3(CommandContext)
- Integer lambda$spawnArmorTrims$3(Holder$Reference)
+ Integer lambda$spawnArmorTrims$5(Holder$Reference)
- void lambda$findEquippableItemsWithAssets$6(List,Holder$Reference)
+ void lambda$findEquippableItemsWithAssets$7(List,Holder$Reference)
```

</details>
<details>
<summary>
net.minecraft.server.commands.SpreadPlayersCommand
</summary>

```diff
+ boolean lambda$register$3(CommandSourceStack)
- Component lambda$spreadPlayers$5(boolean,SpreadPlayersCommand$Position[],Vec2,double)
+ Component lambda$spreadPlayers$6(boolean,SpreadPlayersCommand$Position[],Vec2,double)
- int lambda$register$3(CommandContext)
+ int lambda$register$5(CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.StopCommand
</summary>

```diff
+ boolean lambda$register$0(CommandSourceStack)
- Component lambda$register$0()
+ Component lambda$register$1()
- int lambda$register$1(CommandContext)
+ int lambda$register$2(CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.SummonCommand
</summary>

```diff
+ boolean lambda$register$0(CommandSourceStack)
- Component lambda$spawnEntity$4(Entity)
+ Component lambda$spawnEntity$5(Entity)
- Entity lambda$createEntity$3(Vec3,Entity)
+ Entity lambda$createEntity$4(Vec3,Entity)
- int lambda$register$0(CommandContext)
+ int lambda$register$3(CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.TeamCommand
</summary>

```diff
+ boolean lambda$register$0(CommandSourceStack)
- Component lambda$createTeam$40(PlayerTeam)
+ Component lambda$createTeam$41(PlayerTeam)
- Component lambda$deleteTeam$39(PlayerTeam)
+ Component lambda$deleteTeam$40(PlayerTeam)
- Component lambda$emptyTeam$38(Collection,PlayerTeam)
+ Component lambda$emptyTeam$39(Collection,PlayerTeam)
- Component lambda$joinTeam$29(Collection,PlayerTeam)
+ Component lambda$joinTeam$31(Collection,PlayerTeam)
- Component lambda$leaveTeam$27(Collection)
+ Component lambda$leaveTeam$29(Collection)
- Component lambda$listMembers$41(PlayerTeam)
- Component lambda$listMembers$42(PlayerTeam,Collection)
+ Component lambda$listMembers$42(PlayerTeam)
+ Component lambda$listMembers$43(PlayerTeam,Collection)
- Component lambda$listTeams$43()
+ Component lambda$listTeams$44()
- Component lambda$listTeams$44(Collection)
+ Component lambda$listTeams$45(Collection)
- Component lambda$setCollision$33(PlayerTeam,Team$CollisionRule)
+ Component lambda$setCollision$34(PlayerTeam,Team$CollisionRule)
- Component lambda$setColor$37(PlayerTeam,ChatFormatting)
+ Component lambda$setColor$38(PlayerTeam,ChatFormatting)
- Component lambda$setDeathMessageVisibility$32(PlayerTeam,Team$Visibility)
+ Component lambda$setDeathMessageVisibility$33(PlayerTeam,Team$Visibility)
- Component lambda$setDisplayName$36(PlayerTeam)
+ Component lambda$setDisplayName$37(PlayerTeam)
- Component lambda$setFriendlyFire$35(boolean,PlayerTeam)
+ Component lambda$setFriendlyFire$36(boolean,PlayerTeam)
- Component lambda$setFriendlySight$34(boolean,PlayerTeam)
+ Component lambda$setFriendlySight$35(boolean,PlayerTeam)
- Component lambda$setNametagVisibility$31(PlayerTeam,Team$Visibility)
+ Component lambda$setNametagVisibility$32(PlayerTeam,Team$Visibility)
- Component lambda$setPrefix$45(Component)
+ Component lambda$setPrefix$46(Component)
- Component lambda$setSuffix$46(Component)
+ Component lambda$setSuffix$47(Component)
- int lambda$register$0(CommandContext)
+ int lambda$register$27(CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.TeleportCommand
</summary>

```diff
+ boolean lambda$register$0(CommandSourceStack)
+ boolean lambda$register$9(CommandSourceStack)
+ Component lambda$teleportToEntity$10(Collection,Entity)
+ Component lambda$teleportToEntity$11(Collection,Entity)
- Component lambda$teleportToEntity$8(Collection,Entity)
- Component lambda$teleportToEntity$9(Collection,Entity)
- Component lambda$teleportToPos$10(Collection,Vec3)
- Component lambda$teleportToPos$11(Collection,Vec3)
+ Component lambda$teleportToPos$12(Collection,Vec3)
+ Component lambda$teleportToPos$13(Collection,Vec3)
- int lambda$register$0(CommandContext)
+ int lambda$register$8(CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.TickCommand
</summary>

```diff
+ boolean lambda$register$0(CommandSourceStack)
- CompletableFuture lambda$register$1(CommandContext,SuggestionsBuilder)
+ CompletableFuture lambda$register$2(CommandContext,SuggestionsBuilder)
- CompletableFuture lambda$register$5(CommandContext,SuggestionsBuilder)
+ CompletableFuture lambda$register$6(CommandContext,SuggestionsBuilder)
- CompletableFuture lambda$register$8(CommandContext,SuggestionsBuilder)
+ CompletableFuture lambda$register$9(CommandContext,SuggestionsBuilder)
- Component lambda$setFreeze$22()
+ Component lambda$setFreeze$24()
- Component lambda$setTickingRate$12(String)
+ Component lambda$setTickingRate$13(String)
- Component lambda$sprint$20()
+ Component lambda$sprint$22()
- Component lambda$step$24(int)
+ Component lambda$step$25(int)
- Component lambda$stopSprinting$26()
+ Component lambda$stopSprinting$27()
- Component lambda$stopStepping$25()
+ Component lambda$stopStepping$26()
- Component lambda$tickQuery$13()
+ Component lambda$tickQuery$14()
- Component lambda$tickQuery$14(String,String)
- Component lambda$tickQuery$15()
+ Component lambda$tickQuery$15(String,String)
+ Component lambda$tickQuery$18()
- Component lambda$tickQuery$18(String,String,String)
- Component lambda$tickQuery$19(String,String,String,long[])
+ Component lambda$tickQuery$19(String,String,String)
+ Component lambda$tickQuery$20(String,String,String,long[])
- int lambda$register$0(CommandContext)
+ int lambda$register$1(CommandContext)
+ int lambda$register$12(CommandContext)
- int lambda$register$2(CommandContext)
+ int lambda$register$5(CommandContext)
- int lambda$register$6(CommandContext)
+ int lambda$register$8(CommandContext)
- int lambda$register$9(CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.TitleCommand
</summary>

```diff
+ boolean lambda$register$0(CommandSourceStack)
- Component lambda$clearTitle$6(Collection)
+ Component lambda$clearTitle$8(Collection)
+ Component lambda$resetTitle$10(Collection)
- Component lambda$resetTitle$8(Collection)
- Component lambda$setTimes$12(Collection)
+ Component lambda$setTimes$14(Collection)
- Component lambda$showTitle$10(String,Collection)
+ Component lambda$showTitle$12(String,Collection)
- int lambda$register$0(CommandContext)
+ int lambda$register$6(CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.WardenSpawnTrackerCommand
</summary>

```diff
+ boolean lambda$register$0(CommandSourceStack)
- Component lambda$resetTracker$5(Collection)
+ Component lambda$resetTracker$7(Collection)
- Component lambda$setWarningLevel$3(Collection)
+ Component lambda$setWarningLevel$5(Collection)
- int lambda$register$0(CommandContext)
+ int lambda$register$2(CommandContext)
- void lambda$setWarningLevel$2(int,WardenSpawnTracker)
+ void lambda$setWarningLevel$3(int,WardenSpawnTracker)
```

</details>
<details>
<summary>
net.minecraft.server.commands.WeatherCommand
</summary>

```diff
+ boolean lambda$register$0(CommandSourceStack)
- Component lambda$setClear$6()
+ Component lambda$setClear$7()
- Component lambda$setRain$7()
+ Component lambda$setRain$8()
- Component lambda$setThunder$8()
+ Component lambda$setThunder$9()
- int lambda$register$0(CommandContext)
+ int lambda$register$6(CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.WorldBorderCommand
</summary>

```diff
+ boolean lambda$register$0(CommandSourceStack)
- Component lambda$getSize$14(double)
+ Component lambda$getSize$15(double)
- Component lambda$setCenter$15(Vec2)
+ Component lambda$setCenter$16(Vec2)
- Component lambda$setDamageAmount$11(float)
+ Component lambda$setDamageAmount$12(float)
- Component lambda$setDamageBuffer$10(float)
+ Component lambda$setDamageBuffer$11(float)
- Component lambda$setSize$16(double,long)
+ Component lambda$setSize$18(double,long)
- Component lambda$setSize$18(double)
+ Component lambda$setSize$19(double)
- Component lambda$setWarningDistance$13(int)
+ Component lambda$setWarningDistance$14(int)
- Component lambda$setWarningTime$12(int)
+ Component lambda$setWarningTime$13(int)
- int lambda$register$0(CommandContext)
+ int lambda$register$10(CommandContext)
```

</details>
<details>
<summary>
net.minecraft.server.commands.data.DataCommands
</summary>

```diff
- ArgumentBuilder lambda$decorateModification$23(DataCommands$DataProvider,DataCommands$DataManipulator,DataCommands$DataProvider,ArgumentBuilder)
+ ArgumentBuilder lambda$decorateModification$24(DataCommands$DataProvider,DataCommands$DataManipulator,DataCommands$DataProvider,ArgumentBuilder)
- ArgumentBuilder lambda$decorateModification$24(DataCommands$DataProvider,DataCommands$DataProvider,DataCommands$DataManipulator)
+ ArgumentBuilder lambda$decorateModification$25(DataCommands$DataProvider,DataCommands$DataProvider,DataCommands$DataManipulator)
- ArgumentBuilder lambda$decorateModification$33(DataCommands$DataProvider,DataCommands$DataManipulator,DataCommands$DataProvider,ArgumentBuilder)
+ ArgumentBuilder lambda$decorateModification$34(DataCommands$DataProvider,DataCommands$DataManipulator,DataCommands$DataProvider,ArgumentBuilder)
- ArgumentBuilder lambda$decorateModification$34(DataCommands$DataProvider,DataCommands$DataProvider,DataCommands$DataManipulator)
+ ArgumentBuilder lambda$decorateModification$35(DataCommands$DataProvider,DataCommands$DataProvider,DataCommands$DataManipulator)
- ArgumentBuilder lambda$decorateModification$36(DataCommands$DataProvider,DataCommands$DataManipulator)
- ArgumentBuilder lambda$decorateModification$37(BiConsumer,DataCommands$DataProvider,ArgumentBuilder)
+ ArgumentBuilder lambda$decorateModification$37(DataCommands$DataProvider,DataCommands$DataManipulator)
+ ArgumentBuilder lambda$decorateModification$38(BiConsumer,DataCommands$DataProvider,ArgumentBuilder)
- ArgumentBuilder lambda$register$12(DataCommands$DataProvider,ArgumentBuilder)
+ ArgumentBuilder lambda$register$13(DataCommands$DataProvider,ArgumentBuilder)
- ArgumentBuilder lambda$register$14(DataCommands$DataProvider,ArgumentBuilder)
+ ArgumentBuilder lambda$register$15(DataCommands$DataProvider,ArgumentBuilder)
- ArgumentBuilder lambda$register$8(DataCommands$DataProvider,ArgumentBuilder)
+ ArgumentBuilder lambda$register$9(DataCommands$DataProvider,ArgumentBuilder)
+ boolean lambda$register$7(CommandSourceStack)
- Component lambda$getData$40(DataAccessor,Tag)
+ Component lambda$getData$41(DataAccessor,Tag)
- Component lambda$getData$42(DataAccessor,CompoundTag)
+ Component lambda$getData$43(DataAccessor,CompoundTag)
- Component lambda$getNumeric$41(DataAccessor,NbtPathArgument$NbtPath,double,int)
+ Component lambda$getNumeric$42(DataAccessor,NbtPathArgument$NbtPath,double,int)
- Component lambda$manipulateData$38(DataAccessor)
+ Component lambda$manipulateData$39(DataAccessor)
- Component lambda$mergeData$43(DataAccessor)
+ Component lambda$mergeData$44(DataAccessor)
- Component lambda$removeData$39(DataAccessor)
+ Component lambda$removeData$40(DataAccessor)
- int lambda$decorateModification$21(DataCommands$DataProvider,DataCommands$DataManipulator,DataCommands$DataProvider,CommandContext)
+ int lambda$decorateModification$23(DataCommands$DataProvider,DataCommands$DataManipulator,DataCommands$DataProvider,CommandContext)
- int lambda$decorateModification$26(DataCommands$DataProvider,DataCommands$DataManipulator,DataCommands$DataProvider,CommandContext)
+ int lambda$decorateModification$27(DataCommands$DataProvider,DataCommands$DataManipulator,DataCommands$DataProvider,CommandContext)
- int lambda$decorateModification$28(DataCommands$DataProvider,DataCommands$DataManipulator,DataCommands$DataProvider,CommandContext)
+ int lambda$decorateModification$29(DataCommands$DataProvider,DataCommands$DataManipulator,DataCommands$DataProvider,CommandContext)
- int lambda$decorateModification$30(DataCommands$DataProvider,DataCommands$DataManipulator,DataCommands$DataProvider,CommandContext)
+ int lambda$decorateModification$31(DataCommands$DataProvider,DataCommands$DataManipulator,DataCommands$DataProvider,CommandContext)
- int lambda$decorateModification$32(DataCommands$DataProvider,DataCommands$DataManipulator,DataCommands$DataProvider,CommandContext)
+ int lambda$decorateModification$33(DataCommands$DataProvider,DataCommands$DataManipulator,DataCommands$DataProvider,CommandContext)
- int lambda$decorateModification$35(DataCommands$DataProvider,DataCommands$DataManipulator,CommandContext)
+ int lambda$decorateModification$36(DataCommands$DataProvider,DataCommands$DataManipulator,CommandContext)
+ int lambda$register$12(DataCommands$DataProvider,CommandContext)
- int lambda$register$13(DataCommands$DataProvider,CommandContext)
+ int lambda$register$14(DataCommands$DataProvider,CommandContext)
- int lambda$register$15(CommandContext,CompoundTag,NbtPathArgument$NbtPath,List)
+ int lambda$register$20(CommandContext,CompoundTag,NbtPathArgument$NbtPath,List)
- int lambda$register$7(DataCommands$DataProvider,CommandContext)
+ int lambda$register$8(DataCommands$DataProvider,CommandContext)
- int lambda$register$9(DataCommands$DataProvider,CommandContext)
- String lambda$decorateModification$25(String)
+ String lambda$decorateModification$26(String)
- String lambda$decorateModification$27(String)
+ String lambda$decorateModification$28(String)
- String lambda$decorateModification$29(CommandContext,String)
+ String lambda$decorateModification$30(CommandContext,String)
- String lambda$decorateModification$31(CommandContext,String)
+ String lambda$decorateModification$32(CommandContext,String)
- void lambda$register$20(ArgumentBuilder,DataCommands$DataManipulatorDecorator)
+ void lambda$register$21(ArgumentBuilder,DataCommands$DataManipulatorDecorator)
```

</details>
<details>
<summary>
net.minecraft.world.entity.Entity
</summary>

```diff
- boolean attemptToShearEquipment(Player,InteractionHand,ItemStack,Mob)
- ItemEntity spawnAtLocation(ServerLevel,ItemStack,Vec3)
+ Level getCommandSenderWorld()
```

</details>
<details>
<summary>
net.minecraft.world.entity.Leashable
</summary>

```diff
- Vec3 getHolderMovement(Entity)
```

</details>
<details>
<summary>
net.minecraft.world.entity.Mob
</summary>

```diff
- boolean canShearEquipment(Player)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.HappyGhast
</summary>

```diff
- Vec3 getLeashOffset()
- void tick()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.sheep.Sheep
</summary>

```diff
+ int createSheepColor(DyeColor)
+ int getColor(DyeColor)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.wolf.Wolf
</summary>

```diff
- boolean canShearEquipment(Player)
```

</details>
<details>
<summary>
net.minecraft.world.entity.player.Player
</summary>

```diff
- void openDialog(Holder)
```

</details>
<details>
<summary>
net.minecraft.world.item.equipment.Equippable
</summary>

```diff
- boolean canBeSheared()
- Holder shearingSound()
- void <init>(EquipmentSlot,Holder,Optional,Optional,Optional,boolean,boolean,boolean,boolean,boolean,Holder)
+ void <init>(EquipmentSlot,Holder,Optional,Optional,Optional,boolean,boolean,boolean,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.DriedGhastBlock
</summary>

```diff
+ boolean canPlaceLiquid(LivingEntity,BlockGetter,BlockPos,BlockState,Fluid)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.SignBlockEntity
</summary>

```diff
+ boolean executeClickCommandsIfPresent(Player,Level,BlockPos,boolean)
- boolean executeClickCommandsIfPresent(ServerLevel,Player,BlockPos,boolean)
+ CommandSourceStack createCommandSourceStack(Player,Level,BlockPos)
- CommandSourceStack createCommandSourceStack(Player,ServerLevel,BlockPos)
```

</details>
</details>
<hr/>