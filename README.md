<html><table>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>⌈ PixiGeko | 18w02a ⌋<br/><img width="0" height="0"></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
:warning: This repository is not official, approved, endorsed, associated or connected with Mojang :warning:
<br/><img width="0" height="0"></td></tr>
<tr><th>Id</th><td>18w02a</td></tr>
<tr><th>Type</th><td>snapshots</td></tr>
<tr><th>Release time</th><td>2018-01-10T11:54:55+00:00</td></tr>
<tr><th>SHA1</th><td>8b9bdc1df5d704f0de0a1f2c6b8a721618371213</td></tr>
<tr><th>Url</th><td><a href="https://piston-meta.mojang.com/v1/packages/8b9bdc1df5d704f0de0a1f2c6b8a721618371213/18w02a.json">https://piston-meta.mojang.com/v1/packages/8b9bdc1df5d704f0de0a1f2c6b8a721618371213/18w02a.json</a></td></tr>
<tr><th>Asset index</th><td><a href="https://piston-meta.mojang.com/v1/packages/2175b85e150c64f7ed285e7624b87c18cd992497/1.13.json">https://piston-meta.mojang.com/v1/packages/2175b85e150c64f7ed285e7624b87c18cd992497/1.13.json</a></td></tr>
<tr><th>Server</th><td><a href="https://piston-data.mojang.com/v1/objects/950b737e9cefc9f91f286190166f062d6b0e0105/server.jar">https://piston-data.mojang.com/v1/objects/950b737e9cefc9f91f286190166f062d6b0e0105/server.jar</a></td></tr>
<tr><th>Client</th><td><a href="https://piston-data.mojang.com/v1/objects/05932046cbefd34e42ba21530b96986435163bda/client.jar">https://piston-data.mojang.com/v1/objects/05932046cbefd34e42ba21530b96986435163bda/client.jar</a></td></tr>
<tr><td colspan="2" align="center"><img width="0" height="0"><br/>
<i>Go to the README.md file to make sure you see the full comparison</i>
<br/><img width="0" height="0"></td></tr>
</table></html>

<br/>

<hr/>

# Comparison with <a href="https://github.com/PixiGeko/Minecraft-generated-data/tree/18w01a">18w01a</a>

# Folder structure

<details><summary>data/</summary>

```diff
+ minecraft/tags/blocks/enderman_holdable.json
```

</details>


<details><summary>assets/</summary>

```diff
+ minecraft/lang/en_us.json
- minecraft/lang/en_us.lang
```

</details>


# Commands

<details><summary>execute.txt</summary>

```diff
+ execute anchored <anchor: entity_anchor>
+ execute facing <pos: vec3>
+ execute facing entity <targets: entity> <anchor: entity_anchor>
+ execute if score <target: score_holder> <targetObjective: objective> matches <range: range>
+ execute in overworld
+ execute in the_end
+ execute in the_nether
- execute offset <pos: vec3>
+ execute positioned <pos: vec3>
+ execute positioned as <entities: entity>
+ execute rotated <rot: rotation>
+ execute rotated as <entities: entity>
+ execute unless score <target: score_holder> <targetObjective: objective> matches <range: range>
```

</details>


<details><summary>teleport.txt</summary>

```diff
+ teleport <destination: entity>
- teleport <destination: entity> facing <facingEntity: entity>
- teleport <destination: entity> facing <facingLocation: vec3>
+ teleport <location: vec3>
- teleport <location: vec3> <rotation: rotation>
- teleport <location: vec3> facing <facingEntity: entity>
- teleport <location: vec3> facing <facingLocation: vec3>
+ teleport <targets: entity> <destination: entity>
- teleport <targets: entity> <destination: entity> facing <facingEntity: entity>
- teleport <targets: entity> <destination: entity> facing <facingLocation: vec3>
- teleport <targets: entity> <location: vec3> facing <facingEntity: entity>
+ teleport <targets: entity> <location: vec3> facing entity <facingEntity: entity> <facingAnchor: entity_anchor>
```

</details>


# Tags

<details><summary>List</summary>

```diff
+ blocks/enderman_holdable.json
```

</details>


# Misc

<details><summary>List</summary>

```diff
+ languages.txt
```

</details>


<details><summary>sounds.txt</summary>

```diff
+ ambient/cave/cave19.ogg
+ ambient/underwater/additions/animal1.ogg
+ ambient/underwater/additions/animal2.ogg
+ ambient/underwater/additions/bass_whale1.ogg
+ ambient/underwater/additions/bass_whale2.ogg
+ ambient/underwater/additions/bubbles1.ogg
+ ambient/underwater/additions/bubbles2.ogg
+ ambient/underwater/additions/bubbles3.ogg
+ ambient/underwater/additions/bubbles4.ogg
+ ambient/underwater/additions/bubbles5.ogg
+ ambient/underwater/additions/bubbles6.ogg
+ ambient/underwater/additions/crackles1.ogg
+ ambient/underwater/additions/crackles2.ogg
+ ambient/underwater/additions/dark1.ogg
+ ambient/underwater/additions/dark2.ogg
+ ambient/underwater/additions/dark3.ogg
+ ambient/underwater/additions/dark4.ogg
+ ambient/underwater/additions/driplets1.ogg
+ ambient/underwater/additions/driplets2.ogg
+ ambient/underwater/additions/earth_crack.ogg
+ ambient/underwater/additions/water1.ogg
+ ambient/underwater/additions/water2.ogg
+ ambient/underwater/enter1.ogg
+ ambient/underwater/enter2.ogg
+ ambient/underwater/enter3.ogg
+ ambient/underwater/exit1.ogg
+ ambient/underwater/exit2.ogg
+ ambient/underwater/exit3.ogg
+ ambient/underwater/underwater_ambience.ogg
+ block/beacon/activate.ogg
+ block/beacon/ambient.ogg
+ block/beacon/deactivate.ogg
+ block/beacon/power1.ogg
+ block/beacon/power2.ogg
+ block/beacon/power3.ogg
+ block/bubble_column/bubble1.ogg
+ block/bubble_column/bubble2.ogg
+ block/bubble_column/bubble3.ogg
+ block/bubble_column/upwards_ambient1.ogg
+ block/bubble_column/upwards_ambient2.ogg
+ block/bubble_column/upwards_ambient3.ogg
+ block/bubble_column/upwards_ambient4.ogg
+ block/bubble_column/upwards_ambient5.ogg
+ block/bubble_column/upwards_inside.ogg
+ block/bubble_column/whirlpool_ambient1.ogg
+ block/bubble_column/whirlpool_ambient2.ogg
+ block/bubble_column/whirlpool_ambient3.ogg
+ block/bubble_column/whirlpool_ambient4.ogg
+ block/bubble_column/whirlpool_ambient5.ogg
+ block/bubble_column/whirlpool_inside.ogg
+ block/conduit/activate.ogg
+ block/conduit/ambient.ogg
+ block/conduit/attack1.ogg
+ block/conduit/attack2.ogg
+ block/conduit/attack3.ogg
+ block/conduit/deactivate.ogg
+ block/conduit/short1.ogg
+ block/conduit/short2.ogg
+ block/conduit/short3.ogg
+ block/conduit/short4.ogg
+ block/conduit/short5.ogg
+ block/conduit/short6.ogg
+ block/conduit/short7.ogg
+ block/conduit/short8.ogg
+ block/conduit/short9.ogg
+ block/pumpkin/carve1.ogg
+ block/pumpkin/carve2.ogg
+ block/wooden_door/close5.ogg
+ block/wooden_door/close6.ogg
+ dig/coral1.ogg
+ dig/coral2.ogg
+ dig/coral3.ogg
+ dig/coral4.ogg
+ dig/wet_grass1.ogg
+ dig/wet_grass2.ogg
+ dig/wet_grass3.ogg
+ dig/wet_grass4.ogg
+ entity/fish/flop1.ogg
+ entity/fish/flop2.ogg
+ entity/fish/flop3.ogg
+ entity/fish/flop4.ogg
+ entity/fish/hurt1.ogg
+ entity/fish/hurt2.ogg
+ entity/fish/hurt3.ogg
+ entity/fish/hurt4.ogg
+ entity/fish/swim1.ogg
+ entity/fish/swim2.ogg
+ entity/fish/swim3.ogg
+ entity/fish/swim4.ogg
+ entity/fish/swim5.ogg
+ entity/fish/swim6.ogg
+ entity/fish/swim7.ogg
+ entity/pufferfish/blow_out1.ogg
+ entity/pufferfish/blow_out2.ogg
+ entity/pufferfish/blow_up1.ogg
+ entity/pufferfish/blow_up2.ogg
+ entity/pufferfish/death1.ogg
+ entity/pufferfish/death2.ogg
+ entity/pufferfish/flop1.ogg
+ entity/pufferfish/flop2.ogg
+ entity/pufferfish/flop3.ogg
+ entity/pufferfish/flop4.ogg
+ entity/pufferfish/hurt1.ogg
+ entity/pufferfish/hurt2.ogg
+ entity/pufferfish/sting1.ogg
+ entity/pufferfish/sting2.ogg
+ entity/squid/squirt1.ogg
+ entity/squid/squirt2.ogg
+ entity/squid/squirt3.ogg
+ item/axe/strip1.ogg
+ item/axe/strip2.ogg
+ item/axe/strip3.ogg
+ item/axe/strip4.ogg
+ item/bucket/empty_fish1.ogg
+ item/bucket/empty_fish2.ogg
+ item/bucket/empty_fish3.ogg
+ item/bucket/fill_fish1.ogg
+ item/bucket/fill_fish2.ogg
+ item/bucket/fill_fish3.ogg
+ item/trident/ground_impact1.ogg
+ item/trident/ground_impact2.ogg
+ item/trident/ground_impact3.ogg
+ item/trident/ground_impact4.ogg
+ item/trident/pierce1.ogg
+ item/trident/pierce2.ogg
+ item/trident/pierce3.ogg
+ item/trident/return1.ogg
+ item/trident/return2.ogg
+ item/trident/return3.ogg
+ item/trident/riptide1.ogg
+ item/trident/riptide2.ogg
+ item/trident/riptide3.ogg
+ item/trident/throw1.ogg
+ item/trident/throw2.ogg
+ item/trident/thunder1.ogg
+ item/trident/thunder2.ogg
+ liquid/heavy_splash.ogg
+ liquid/swim10.ogg
+ liquid/swim11.ogg
+ liquid/swim12.ogg
+ liquid/swim13.ogg
+ liquid/swim14.ogg
+ liquid/swim15.ogg
+ liquid/swim16.ogg
+ liquid/swim17.ogg
+ liquid/swim18.ogg
+ liquid/swim5.ogg
+ liquid/swim6.ogg
+ liquid/swim7.ogg
+ liquid/swim8.ogg
+ liquid/swim9.ogg
+ mob/dolphin/attack1.ogg
+ mob/dolphin/attack2.ogg
+ mob/dolphin/attack3.ogg
+ mob/dolphin/blowhole1.ogg
+ mob/dolphin/blowhole2.ogg
+ mob/dolphin/death1.ogg
+ mob/dolphin/death2.ogg
+ mob/dolphin/eat1.ogg
+ mob/dolphin/eat2.ogg
+ mob/dolphin/eat3.ogg
+ mob/dolphin/hurt1.ogg
+ mob/dolphin/hurt2.ogg
+ mob/dolphin/hurt3.ogg
+ mob/dolphin/idle_water1.ogg
+ mob/dolphin/idle_water10.ogg
+ mob/dolphin/idle_water2.ogg
+ mob/dolphin/idle_water3.ogg
+ mob/dolphin/idle_water4.ogg
+ mob/dolphin/idle_water5.ogg
+ mob/dolphin/idle_water6.ogg
+ mob/dolphin/idle_water7.ogg
+ mob/dolphin/idle_water8.ogg
+ mob/dolphin/idle_water9.ogg
+ mob/dolphin/idle1.ogg
+ mob/dolphin/idle2.ogg
+ mob/dolphin/idle3.ogg
+ mob/dolphin/idle4.ogg
+ mob/dolphin/idle5.ogg
+ mob/dolphin/idle6.ogg
+ mob/dolphin/jump1.ogg
+ mob/dolphin/jump2.ogg
+ mob/dolphin/jump3.ogg
+ mob/dolphin/play1.ogg
+ mob/dolphin/play2.ogg
+ mob/dolphin/splash1.ogg
+ mob/dolphin/splash2.ogg
+ mob/dolphin/splash3.ogg
+ mob/dolphin/swim1.ogg
+ mob/dolphin/swim2.ogg
+ mob/dolphin/swim3.ogg
+ mob/dolphin/swim4.ogg
+ mob/drowned/convert1.ogg
+ mob/drowned/convert2.ogg
+ mob/drowned/convert3.ogg
+ mob/drowned/death1.ogg
+ mob/drowned/death2.ogg
+ mob/drowned/hurt1.ogg
+ mob/drowned/hurt2.ogg
+ mob/drowned/hurt3.ogg
+ mob/drowned/idle1.ogg
+ mob/drowned/idle2.ogg
+ mob/drowned/idle3.ogg
+ mob/drowned/idle4.ogg
+ mob/drowned/idle5.ogg
+ mob/drowned/step1.ogg
+ mob/drowned/step2.ogg
+ mob/drowned/step3.ogg
+ mob/drowned/step4.ogg
+ mob/drowned/step5.ogg
+ mob/drowned/water/death1.ogg
+ mob/drowned/water/death2.ogg
+ mob/drowned/water/hurt1.ogg
+ mob/drowned/water/hurt2.ogg
+ mob/drowned/water/hurt3.ogg
+ mob/drowned/water/idle1.ogg
+ mob/drowned/water/idle2.ogg
+ mob/drowned/water/idle3.ogg
+ mob/drowned/water/idle4.ogg
+ mob/horse/skeleton/water/gallop1.ogg
+ mob/horse/skeleton/water/gallop2.ogg
+ mob/horse/skeleton/water/gallop3.ogg
+ mob/horse/skeleton/water/gallop4.ogg
+ mob/horse/skeleton/water/idle1.ogg
+ mob/horse/skeleton/water/idle2.ogg
+ mob/horse/skeleton/water/idle3.ogg
+ mob/horse/skeleton/water/idle4.ogg
+ mob/horse/skeleton/water/idle5.ogg
+ mob/horse/skeleton/water/jump.ogg
+ mob/horse/skeleton/water/soft1.ogg
+ mob/horse/skeleton/water/soft2.ogg
+ mob/horse/skeleton/water/soft3.ogg
+ mob/horse/skeleton/water/soft4.ogg
+ mob/horse/skeleton/water/soft5.ogg
+ mob/horse/skeleton/water/soft6.ogg
+ mob/husk/convert1.ogg
+ mob/husk/convert2.ogg
+ mob/phantom/bite1.ogg
+ mob/phantom/bite2.ogg
+ mob/phantom/death1.ogg
+ mob/phantom/death2.ogg
+ mob/phantom/death3.ogg
+ mob/phantom/flap1.ogg
+ mob/phantom/flap2.ogg
+ mob/phantom/flap3.ogg
+ mob/phantom/flap4.ogg
+ mob/phantom/flap5.ogg
+ mob/phantom/flap6.ogg
+ mob/phantom/hurt1.ogg
+ mob/phantom/hurt2.ogg
+ mob/phantom/hurt3.ogg
+ mob/phantom/idle1.ogg
+ mob/phantom/idle2.ogg
+ mob/phantom/idle3.ogg
+ mob/phantom/idle4.ogg
+ mob/phantom/idle5.ogg
+ mob/phantom/swoop1.ogg
+ mob/phantom/swoop2.ogg
+ mob/phantom/swoop3.ogg
+ mob/phantom/swoop4.ogg
+ mob/turtle/armor.ogg
+ mob/turtle/baby/death1.ogg
+ mob/turtle/baby/death2.ogg
+ mob/turtle/baby/egg_hatched1.ogg
+ mob/turtle/baby/egg_hatched2.ogg
+ mob/turtle/baby/egg_hatched3.ogg
+ mob/turtle/baby/hurt1.ogg
+ mob/turtle/baby/hurt2.ogg
+ mob/turtle/baby/shamble1.ogg
+ mob/turtle/baby/shamble2.ogg
+ mob/turtle/baby/shamble3.ogg
+ mob/turtle/baby/shamble4.ogg
+ mob/turtle/death1.ogg
+ mob/turtle/death2.ogg
+ mob/turtle/death3.ogg
+ mob/turtle/egg/drop_egg1.ogg
+ mob/turtle/egg/drop_egg2.ogg
+ mob/turtle/egg/egg_break1.ogg
+ mob/turtle/egg/egg_break2.ogg
+ mob/turtle/egg/egg_crack1.ogg
+ mob/turtle/egg/egg_crack2.ogg
+ mob/turtle/egg/egg_crack3.ogg
+ mob/turtle/egg/egg_crack4.ogg
+ mob/turtle/egg/egg_crack5.ogg
+ mob/turtle/egg/jump_egg1.ogg
+ mob/turtle/egg/jump_egg2.ogg
+ mob/turtle/egg/jump_egg3.ogg
+ mob/turtle/egg/jump_egg4.ogg
+ mob/turtle/hurt1.ogg
+ mob/turtle/hurt2.ogg
+ mob/turtle/hurt3.ogg
+ mob/turtle/hurt4.ogg
+ mob/turtle/hurt5.ogg
+ mob/turtle/idle1.ogg
+ mob/turtle/idle2.ogg
+ mob/turtle/idle3.ogg
+ mob/turtle/swim/swim1.ogg
+ mob/turtle/swim/swim2.ogg
+ mob/turtle/swim/swim3.ogg
+ mob/turtle/swim/swim4.ogg
+ mob/turtle/swim/swim5.ogg
+ mob/turtle/walk1.ogg
+ mob/turtle/walk2.ogg
+ mob/turtle/walk3.ogg
+ mob/turtle/walk4.ogg
+ mob/turtle/walk5.ogg
+ music/game/water/axolotl.ogg
+ music/game/water/dragon_fish.ogg
+ music/game/water/shuniji.ogg
+ step/coral1.ogg
+ step/coral2.ogg
+ step/coral3.ogg
+ step/coral4.ogg
+ step/coral5.ogg
+ step/coral6.ogg
+ step/wet_grass1.ogg
+ step/wet_grass2.ogg
+ step/wet_grass3.ogg
+ step/wet_grass4.ogg
+ step/wet_grass5.ogg
+ step/wet_grass6.ogg
```

</details>


<details><summary>tags.txt</summary>

```diff
+ blocks/enderman_holdable.json
```

</details>


<details><summary>parsers.txt</summary>

```diff
+ minecraft:entity_anchor
+ minecraft:range
```

</details>
