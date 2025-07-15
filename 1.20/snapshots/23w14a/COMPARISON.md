## Comparison with [23w13a_or_b](https://github.com/PixiGeko/Minecraft-generated-data/tree/23w13a_or_b)

> [!TIP]
> - [Version data](#version-data)
>     - [Libraries](#version-data-libraries)
> - [Registries](#registries)
> - [Tags](#tags)
> - [Blocks](#blocks)
> - [Commands](#commands)
> - [Recipes](#recipes)
> - [Translations](#translations)
> - [File structure](#file-structure)
> - [Misc](#misc)
> - [Mappings](#mappings)
>   - [Server](#server-mappings)
>   - [Client](#client-mappings)

<br/><br/>
<details><summary><b><ins>VERSION DATA</ins></b><a name="version-data"></a></summary>
<br/>
<table><tr><th></th><th align="left">23w13a_or_b</th><th>23w14a</th></tr><tr><td>ResourcePack version</td><td><pre>13</pre></td><td><pre>14</pre></td></tr><tr><td>World version</td><td><pre>3444</pre></td><td><pre>3445</pre></td></tr><tr><td>Protocol version</td><td><pre>1073741953</pre></td><td><pre>1073741954</pre></td></tr></table>
<h3>Libraries<a name="version-data-libraries"></a></h3>
<details>
<summary>
Versions
</summary>
<table><tr><th></th><th align="left">23w13a_or_b</th><th>23w14a</th></tr><tr><td>com.mojang:brigadier</td><td><pre>1.0.18</pre></td><td><pre>1.1.8</pre></td></tr></table>
</details>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
- rules.txt
```

</details>
<details>
<summary>
attribute
</summary>

```diff
- minecraft:generic.scale
```

</details>
<details>
<summary>
banner_pattern
</summary>

```diff
- minecraft:m
```

</details>
<details>
<summary>
block
</summary>

```diff
- minecraft:cheese
- minecraft:copper_sink
- minecraft:copper_spleaves
- minecraft:filled_copper_sink
- minecraft:other_portal
- minecraft:packed_air
- minecraft:pickaxe_block
- minecraft:place_block
```

</details>
<details>
<summary>
custom_stat
</summary>

```diff
- minecraft:votes
```

</details>
<details>
<summary>
entity_type
</summary>

```diff
- minecraft:moon_cow
- minecraft:ray_tracing
- minecraft:stencil_display
```

</details>
<details>
<summary>
item
</summary>

```diff
- minecraft:air_block
- minecraft:bit
- minecraft:bottle_of_entity
- minecraft:bottle_of_void
- minecraft:byte_tag
- minecraft:cheese
- minecraft:compound_tag
- minecraft:copper_sink
- minecraft:copper_spleaves
- minecraft:double_tag
- minecraft:dupe_hack
- minecraft:float_tag
- minecraft:int_tag
- minecraft:la_baguette
- minecraft:le_tricolore
- minecraft:left_curly
- minecraft:left_square
- minecraft:list_tag
- minecraft:long_tag
- minecraft:m_banner_pattern
- minecraft:moon_cow_spawn_egg
- minecraft:name
- minecraft:packed_air
- minecraft:pickaxe_block
- minecraft:place_block
- minecraft:right_curly
- minecraft:right_square
- minecraft:short_tag
- minecraft:splash_bottle_of_entity
- minecraft:string_tag
- minecraft:string2
- minecraft:syntax_error
- minecraft:tag
```

</details>
<details>
<summary>
loot_function_type
</summary>

```diff
+ minecraft:reference
```

</details>
<details>
<summary>
mob_effect
</summary>

```diff
- minecraft:big
- minecraft:small
```

</details>
<details>
<summary>
particle_type
</summary>

```diff
- minecraft:footstep
```

</details>
<details>
<summary>
potion
</summary>

```diff
- minecraft:big
- minecraft:long_big
- minecraft:long_small
- minecraft:small
- minecraft:strong_big
- minecraft:strong_small
```

</details>
<details>
<summary>
recipe_serializer
</summary>

```diff
- minecraft:crafting_special_dupehack
- minecraft:nbt_crafting_recipe
```

</details>
<details>
<summary>
sensor_type
</summary>

```diff
+ minecraft:sniffer_temptations
```

</details>
<details>
<summary>
sound_event
</summary>

```diff
+ minecraft:block.sniffer.egg_crack
+ minecraft:block.sniffer.egg_hatch
- minecraft:entity.sniffer.egg_crack
- minecraft:entity.sniffer.egg_hatch
- minecraft:the_joke
```

</details>
<details>
<summary>
worldgen/biome_source
</summary>

```diff
- minecraft:the_moon
```

</details>
<details>
<summary>
worldgen/feature
</summary>

```diff
- minecraft:crater
- minecraft:lunar_base
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
- universal_tags/rules.json
```

</details>
<details>
<summary>
all_blocks_without_drop.json
</summary>

```diff
- minecraft:copper_spleaves
- minecraft:other_portal
- minecraft:packed_air
```

</details>
<details>
<summary>
all_blocks_with_drop.json
</summary>

```diff
- minecraft:cheese
- minecraft:copper_sink
- minecraft:filled_copper_sink
- minecraft:pickaxe_block
- minecraft:place_block
```

</details>
<details>
<summary>
all_entities_without_drop.json
</summary>

```diff
- minecraft:ray_tracing
- minecraft:stencil_display
```

</details>
<details>
<summary>
all_entities_with_drop.json
</summary>

```diff
- minecraft:moon_cow
```

</details>
<details>
<summary>
all_living_entities_without_drop.json
</summary>

```diff
- minecraft:ray_tracing
```

</details>
<details>
<summary>
all_survival_blocks_without_drop.json
</summary>

```diff
- minecraft:copper_spleaves
- minecraft:other_portal
```

</details>
<details>
<summary>
universal_tags/attribute.json
</summary>

```diff
- minecraft:generic.scale
```

</details>
<details>
<summary>
universal_tags/banner_pattern.json
</summary>

```diff
- minecraft:m
```

</details>
<details>
<summary>
universal_tags/block.json
</summary>

```diff
- minecraft:cheese
- minecraft:copper_sink
- minecraft:copper_spleaves
- minecraft:filled_copper_sink
- minecraft:other_portal
- minecraft:packed_air
- minecraft:pickaxe_block
- minecraft:place_block
```

</details>
<details>
<summary>
universal_tags/custom_stat.json
</summary>

```diff
- minecraft:votes
```

</details>
<details>
<summary>
universal_tags/entity_type.json
</summary>

```diff
- minecraft:moon_cow
- minecraft:ray_tracing
- minecraft:stencil_display
```

</details>
<details>
<summary>
universal_tags/item.json
</summary>

```diff
- minecraft:air_block
- minecraft:bit
- minecraft:bottle_of_entity
- minecraft:bottle_of_void
- minecraft:byte_tag
- minecraft:cheese
- minecraft:compound_tag
- minecraft:copper_sink
- minecraft:copper_spleaves
- minecraft:double_tag
- minecraft:dupe_hack
- minecraft:float_tag
- minecraft:int_tag
- minecraft:la_baguette
- minecraft:le_tricolore
- minecraft:left_curly
- minecraft:left_square
- minecraft:list_tag
- minecraft:long_tag
- minecraft:m_banner_pattern
- minecraft:moon_cow_spawn_egg
- minecraft:name
- minecraft:packed_air
- minecraft:pickaxe_block
- minecraft:place_block
- minecraft:right_curly
- minecraft:right_square
- minecraft:short_tag
- minecraft:splash_bottle_of_entity
- minecraft:string_tag
- minecraft:string2
- minecraft:syntax_error
- minecraft:tag
```

</details>
<details>
<summary>
universal_tags/loot_function_type.json
</summary>

```diff
+ minecraft:reference
```

</details>
<details>
<summary>
universal_tags/mob_effect.json
</summary>

```diff
- minecraft:big
- minecraft:small
```

</details>
<details>
<summary>
universal_tags/particle_type.json
</summary>

```diff
- minecraft:footstep
```

</details>
<details>
<summary>
universal_tags/potion.json
</summary>

```diff
- minecraft:big
- minecraft:long_big
- minecraft:long_small
- minecraft:small
- minecraft:strong_big
- minecraft:strong_small
```

</details>
<details>
<summary>
universal_tags/recipe_serializer.json
</summary>

```diff
- minecraft:crafting_special_dupehack
- minecraft:nbt_crafting_recipe
```

</details>
<details>
<summary>
universal_tags/sensor_type.json
</summary>

```diff
+ minecraft:sniffer_temptations
```

</details>
<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:block.sniffer.egg_crack
+ minecraft:block.sniffer.egg_hatch
- minecraft:entity.sniffer.egg_crack
- minecraft:entity.sniffer.egg_hatch
- minecraft:the_joke
```

</details>
<details>
<summary>
universal_tags/worldgen/biome_source.json
</summary>

```diff
- minecraft:the_moon
```

</details>
<details>
<summary>
universal_tags/worldgen/feature.json
</summary>

```diff
- minecraft:crater
- minecraft:lunar_base
```

</details>
</details>
<hr/>
<details><summary><b><ins>BLOCKS</ins></b><a name="blocks"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
- cheese.json
- copper_sink.json
- copper_spleaves.json
- filled_copper_sink.json
- other_portal.json
- packed_air.json
- pickaxe_block.json
- place_block.json
```

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
- transform.txt
- vote.txt
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
- air_block.json
- bit_from_name_stonecutting.json
- bit_from_tag_stonecutting.json
- copper_sink.json
- diamond_drows.json
- dupe_hack.json
- left_curly.json
- left_square.json
- m_banner_pattern.json
- name_from_name_tag_stonecutting.json
- nbt_crafting.json
- packed_air.json
- pickaxe_block.json
- place_block.json
- right_curly.json
- right_square.json
- string_concatenation.json
- tag_from_name_tag_stonecutting.json
- wob.json
```

</details>
<details>
<summary>
cyan_dye.json
</summary>

```
Group: none -> cyan_dye
```

</details>
<details>
<summary>
cyan_dye_from_pitcher_plant.json
</summary>

```
Result: cyan_dye x1 -> cyan_dye x2
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
- action.approve: Approve "%s"
- action.repeal: Repeal "%s"
- advancements.adventure.vote_1.description: Voted for the first time
- advancements.adventure.vote_1.title: I Voted!
- advancements.adventure.vote_256.description: Voted 256 times
- advancements.adventure.vote_256.title: Pro Voter
- attribute.name.generic.scale: Entity Scale
- block.minecraft.banner.m.black: Black New Thing
- block.minecraft.banner.m.blue: Blue New Thing
- block.minecraft.banner.m.brown: Brown New Thing
- block.minecraft.banner.m.cyan: Cyan New Thing
- block.minecraft.banner.m.gray: Gray New Thing
- block.minecraft.banner.m.green: Green New Thing
- block.minecraft.banner.m.light_blue: Light Blue New Thing
- block.minecraft.banner.m.light_gray: Light Gray New Thing
- block.minecraft.banner.m.lime: Lime New Thing
- block.minecraft.banner.m.magenta: Magenta New Thing
- block.minecraft.banner.m.orange: Orange New Thing
- block.minecraft.banner.m.pink: Pink New Thing
- block.minecraft.banner.m.purple: Purple New Thing
- block.minecraft.banner.m.red: Red New Thing
- block.minecraft.banner.m.white: White New Thing
- block.minecraft.banner.m.yellow: Yellow New Thing
- block.minecraft.bed.no_sleep_v2: You can sleep only at day or during thunderstorms
- block.minecraft.cheese: Cheese
- block.minecraft.chest.lab: Lunar Laboratory Equipment
- block.minecraft.chest.moon: Moon Mission Resupply Crate
- block.minecraft.copper_sink: Copper Sink
- block.minecraft.copper_spleaves: Copper Spleaves
- block.minecraft.dropper.lunar: ACME Self-Building Lunar Base
- block.minecraft.filled_copper_sink: Filled Copper Sink
- block.minecraft.other_portal: Other Portal
- block.minecraft.packed_air: Packed Air
- block.minecraft.pickaxe_block: Pickaxe Block
- block.minecraft.place_block: Place Block
- death.attack.onMoon: %1$s experienced the dark side of the moon
- death.midas.turned_into_gold: %1$s was turned into gold
- effect.minecraft.big: Big
- effect.minecraft.small: Small
- entity.minecraft.moon_cow: Moon Cow
- entity.minecraft.ray_tracing: Ray Tracing
- entity.minecraft.stencil_display: Stencil Display
- gui.pending_votes.title: Pending Votes
+ gui.toRealms: Back to Realms List
+ gui.toWorld: Back to World List
- gui.voting.do_it: Vote!
- gui.voting.next: Next Vote
- gui.voting.prev: Previous Vote
- gui.voting.title: Voting
- item.minecraft.air_block: Air
- item.minecraft.bit: Bit
- item.minecraft.bottle_of_entity: Bottle of Entity
- item.minecraft.bottle_of_entity.specific: Bottle of %s
- item.minecraft.bottle_of_void: Bottle of Void
- item.minecraft.byte_tag: Byte Tag
- item.minecraft.compound_tag: Compound Tag
- item.minecraft.double_tag: Double Tag
- item.minecraft.dupe_hack: minecraft:dupe_hack
- item.minecraft.float_tag: Float Tag
- item.minecraft.glass_bottle_air: Glass Bottle filled with Air
- item.minecraft.int_tag: Int Tag
- item.minecraft.la_baguette: La Baguette
- item.minecraft.le_tricolore: Le Tricolore
- item.minecraft.left_curly: Left Curly
- item.minecraft.left_square: Left Square
- item.minecraft.lingering_potion.effect.big: Lingering Potion of Big
- item.minecraft.lingering_potion.effect.small: Lingering Potion of Small
- item.minecraft.list_tag: List Tag
- item.minecraft.long_tag: Long Tag
- item.minecraft.m_banner_pattern: Banner Pattern
- item.minecraft.m_banner_pattern.desc: New Thing
- item.minecraft.moon_cow_spawn_egg: Moon Cow Spawn Egg
- item.minecraft.name: Name
- item.minecraft.potion.effect.big: Potion of Big
- item.minecraft.potion.effect.small: Potion of Small
- item.minecraft.right_curly: Right Curly
- item.minecraft.right_square: Right Square
- item.minecraft.ruby: Ruby
- item.minecraft.short_tag: Short Tag
- item.minecraft.splash_bottle_of_entity: Splash Bottle of Entity
- item.minecraft.splash_bottle_of_entity.specific: Splash Bottle of %s
- item.minecraft.splash_potion.effect.big: Splash Potion of Big
- item.minecraft.splash_potion.effect.small: Splash Potion of Small
- item.minecraft.string_tag: String Tag
- item.minecraft.string2: Longer String
- item.minecraft.syntax_error: Sssyntax Error
- item.minecraft.tag: Tag
- item.minecraft.tipped_arrow.effect.big: Arrow of Big
- item.minecraft.tipped_arrow.effect.small: Arrow of Small
- key.voting: Voting
+ quickplay.error.invalid_identifier: Could not find world with the provided identifier
+ quickplay.error.realm_connect: Could not connect to Realm
+ quickplay.error.realm_permission: Lacking permission to connect to this Realm
+ quickplay.error.title: Failed to Quick Play
- rule.ai_attack: Replace player %s with advanced AI bot
- rule.ai_attack.decorate: [BOT] %s
- rule.air_blocks: Unlock edible Air Blocks, Packed Air to survive on moon and rideable baloon cows to get there
- rule.always_flying: According to all known laws of aviation, there is no way a mob should be able to walk
- rule.anonymize_skins: Anonymize player skins
- rule.attack_knockback: Multiply knockback by %s%%
- rule.autoJump.also_default_vanilla_to_true: Auto jump on. Also set default value of auto jump in vanilla to true
- rule.autoJump.of_course: Auto jump? Of course
- rule.autojump.off: Auto jump off
- rule.autoJump.on: Auto jump on
- rule.autoJump.true: Auto jump: true
- rule.autoJump.yes: Auto jump? Yes
- rule.bed_pvp: Bed PVP
- rule.bed_pvp.tooltip: Highly explosive!
- rule.bedrock_shadows: Minecraft Bedrock Edition style entity shadows
- rule.beds_on_banners: Beds on Banners
- rule.beeloons: Enable Beeloons
- rule.beta_entity_ids: Show id above every entity
- rule.big_heads: Big Head Mode
- rule.biome_color.fog: Set fog color in %s to %s
- rule.biome_color.foliage: Set foliage color in %s to %s
- rule.biome_color.grass: Set grass color in %s to %s
- rule.biome_color.sky: Set sky color in %s to %s
- rule.biome_color.water_fog: Set water fog color in %s to %s
- rule.biome_color.water: Set water color in %s to %s
- rule.boat_collisions.break: Boats break on high-speed collisions
- rule.boat_collisions.explode: Boats explode on high-speed collisions
- rule.boat_collisions.none: Disable boats breaking on collision
- rule.bouncy_castle: Super bouncy Slime blocks
- rule.buff_fishing: Buff fishing
- rule.buttons_on_things: You can place buttons (and much more stuff), on much more stuff
- rule.caep.awesom: Give everyone an awesom caep
- rule.caep.no_circle: NO ROUND SHAPES ALLOWED!
- rule.caep.nyan: Nya, nya, nya! UwU!
- rule.caep.squid: Give everyone a squid cape squid
- rule.caep.veterinarian: Give all the animal lovers a veterinarian cape
- rule.change_integer_gamerule: Change value of game rule '%s' to %s
- rule.change_world_shape: Change Overworld shape
- rule.charged_creepers: All creepers are charged
- rule.codepoint_replace: Replace '%s' with '%s'
- rule.colored_light: Add %s colored light
- rule.connector: %s, but %s
- rule.copper_sink: Add Copper Sink
- rule.copy_skin: Everyone Copies %s!
- rule.damage_modifier: Multiply damage type '%s' by %s
- rule.day_beds: Bed skip days instead nights
- rule.day_length.change: Change day length from %s to %s
- rule.day_length.set: Set day length %s
- rule.dead_bush_renewability: Dead Bushes are now renewable, but saplings need much more water not to dry out
- rule.decrease_scale: Decrease player scale by %sx
- rule.default_sheep_color: Set spawn sheep color to %s
- rule.dinnerbonize: Dinnerbonize %s
- rule.disable_item_tooltips: Disable item tooltips
- rule.disable_shield: Disable shield blocking
- rule.dream_mode: Life's a Dream
- rule.drink_air: Bottle of Void: obtained by drinking from empty Bottles. May have side-effects.
- rule.dupe_hack_break_chance: Set chance of dupe hack breaking to %s%%
- rule.dupe_hack_occurrence_chance: Set chance of dupe hack occurring to %s%%
- rule.egg_free.item: Chickens lay %s
- rule.egg_free.seed_reshuffle: Chicken lay random assigned item (reshuffle)
- rule.egg_free.seed: Chickens lay randomly assigned item
- rule.endermen_block_update: Teach Endermen how to place blocks correctly
- rule.endermen_pick_up_anything: Endermen Pick Up Anything
- rule.entity_collisions: Entities collide with each other
- rule.evil_eye: Get evil eyes
- rule.exploding_phantoms: Phantoms explode on contact
- rule.explosion_power.change: Change extra explosion power from %s to %s
- rule.explosion_power.set: Set extra explosion power to %s
- rule.fast_hoppers: Fast Hoppers, but hopper minecarts are now slow
- rule.fire_sponge: Sponges can be used to remove lave
- rule.fish_anything: Polluted Oceans: Fish Anything!
- rule.fix_piston: Pistons explode when powered
- rule.fix_qc: Quasi-fix Connectivity
- rule.flailing.extreme: Limbs all over the place
- rule.flailing.mild: Mild flailing
- rule.flailing.none: Stop all that flailing
- rule.flailing.normal: Normal flailing levels
- rule.flailing.wild: Wild flailing
- rule.flailing.windmill: WINDMILL MODE ON!!!
- rule.flammability.high: Change flammability of %s to high
- rule.flammability.low: Change flammability of %s to low
- rule.flammability.medium: Change flammability of %s to medium
- rule.flammability.very_high: Change flammability of %s to 'literally dry grass'
- rule.flintsploder: Flint and Steel can explode any block
- rule.flip_binary_gamerule: Flip game rule '%s'
- rule.floating_heads: Floating Head Mode
- rule.fog_off: Remove fog from the game where there was fog before. Anv vice versa.
- rule.food_restriction.any: A Balanced Diet
- rule.food_restriction.apple: An Apple Party Diet
- rule.food_restriction.baked_potato: A Get Baked Diet
- rule.food_restriction.beef: A Cow Sushi Diet
- rule.food_restriction.beetroot_soup: A Soup Kitchen Diet
- rule.food_restriction.beetroot: A Beeter Diet
- rule.food_restriction.bread: A Toasty Diet
- rule.food_restriction.cake: A Birthday Diet
- rule.food_restriction.carrot: A Rabbit Diet
- rule.food_restriction.chicken: A Salmonella Diet
- rule.food_restriction.chorus_fruit: A Nomportation Diet
- rule.food_restriction.cod: A Fishy Diet
- rule.food_restriction.cooked_beef: A Meat Lovers Diet
- rule.food_restriction.cooked_chicken: A Nugget Time Diet
- rule.food_restriction.cooked_cod: A Fish Without Chips Diet
- rule.food_restriction.cooked_mutton: A Woolsome Diet
- rule.food_restriction.cooked_porkchop: Bringing Home the Bacon Diet
- rule.food_restriction.cooked_rabbit: A Bingo Diet
- rule.food_restriction.cooked_salmon: A River Diet
- rule.food_restriction.cookie: An Unhealthy Diet
- rule.food_restriction.dried_kelp: A Weedy Food Diet
- rule.food_restriction.edible: Food
- rule.food_restriction.enchanted_golden_apple: Michellin Level Expensive Diet
- rule.food_restriction.glow_berries: An X-Ray Diet
- rule.food_restriction.golden_apple: A Healthy Diet
- rule.food_restriction.golden_carrot: Expensive Rabbit Food Diet
- rule.food_restriction.honey_bottle: A Sugar Drink Diet
- rule.food_restriction.inedible.apple: Oak Tree Nut
- rule.food_restriction.inedible.baked_potato: Baked Bump from the Dirt
- rule.food_restriction.inedible.beef: Cut Cow
- rule.food_restriction.inedible.beetroot_soup: Blood in a Bowl?
- rule.food_restriction.inedible.beetroot: Red Dirtbump
- rule.food_restriction.inedible.bread: Dried Porridge
- rule.food_restriction.inedible.cake: Lies
- rule.food_restriction.inedible.carrot: Rabbit Feed
- rule.food_restriction.inedible.chicken: Birdbits
- rule.food_restriction.inedible.chorus_fruit: Purple Alien Orb
- rule.food_restriction.inedible.cod: Slimy Water Thing
- rule.food_restriction.inedible.cooked_beef: Cremated Cow
- rule.food_restriction.inedible.cooked_chicken: Burnt Bird
- rule.food_restriction.inedible.cooked_cod: Ruined Sushi
- rule.food_restriction.inedible.cooked_mutton: Disgusting Burnt Sheep Piece
- rule.food_restriction.inedible.cooked_porkchop: Charred Pig Part
- rule.food_restriction.inedible.cooked_rabbit: It Liked Jumping Around You Murderer
- rule.food_restriction.inedible.cooked_salmon: Slimy Fish Goop
- rule.food_restriction.inedible.cookie: Yucky Yellow Thing
- rule.food_restriction.inedible.dried_kelp: Dried But Somehow Also Slimy
- rule.food_restriction.inedible.enchanted_golden_apple: Inedible Shining Blob
- rule.food_restriction.inedible.glow_berries: Light Bulbs
- rule.food_restriction.inedible.golden_apple: Inedible Yellow Blob
- rule.food_restriction.inedible.golden_carrot: Rabbit Food
- rule.food_restriction.inedible.honey_bottle: Too Much Sugar
- rule.food_restriction.inedible.melon_slice: Mostly Seeds
- rule.food_restriction.inedible.mushroom_stew: Fungal Goop
- rule.food_restriction.inedible.mutton: Sheet of Sheep
- rule.food_restriction.inedible.poisonous_potato: Useless Knob
- rule.food_restriction.inedible.porkchop: Piece of Pig
- rule.food_restriction.inedible.potato: Root Thing?
- rule.food_restriction.inedible.pufferfish: The Terror of the Deep
- rule.food_restriction.inedible.pumpkin_pie: It's Not a Pie You Didn't Even Bake It
- rule.food_restriction.inedible.rabbit_stew: Who Stewed Roger Rabbit?
- rule.food_restriction.inedible.rabbit: Bunneh :(
- rule.food_restriction.inedible.rotten_flesh: Unhealthy Thing
- rule.food_restriction.inedible.salmon: Red Slimy Water Thing
- rule.food_restriction.inedible.spider_eye: Arcachneous Orb
- rule.food_restriction.inedible.suspicious_stew: Sus
- rule.food_restriction.inedible.sweet_berries: Stick Blobs
- rule.food_restriction.inedible.tropical_fish: Nemo
- rule.food_restriction.maybe_edible: Food (May Have Side Effects)
- rule.food_restriction.melon_slice: sliceddiet
- rule.food_restriction.mushroom_stew: Shrooms! Only Shrooms!
- rule.food_restriction.mutton: A Raw And Wooly Diet
- rule.food_restriction.poisonous_potato: A Dubious Spud Diet
- rule.food_restriction.porkchop: A Pork Belly Diet
- rule.food_restriction.potato: Unboiled, Unmashed, Unstewed Diet
- rule.food_restriction.pufferfish: A Killer Diet
- rule.food_restriction.pumpkin_pie: Mmmm, Pie. Pie! Only Pie!
- rule.food_restriction.rabbit_stew: An Auto-Jump Diet
- rule.food_restriction.rabbit: Raw Jumpers Only
- rule.food_restriction.rotten_flesh: A Rotten Diet
- rule.food_restriction.salmon: A Sushi Diet
- rule.food_restriction.spider_eye: A Witching Diet
- rule.food_restriction.suspicious_stew: A Sus Diet
- rule.food_restriction.sweet_berries: A Sweet, Sweet Diet
- rule.food_restriction.tropical_fish: Only Eating Nemo
- rule.footprint: Advance Project Footprint status from '%s' to '%s'
- rule.footprint.0: Footprints? What footprints?
- rule.footprint.1: Start process for restoring footprint particles
- rule.footprint.10: Go-no go meeting
- rule.footprint.11: Enable footprints
- rule.footprint.2: Re-evaluate footprint principles
- rule.footprint.3: Pre-estimate footprint timeline
- rule.footprint.4: Research existing footprint solutions in competing products
- rule.footprint.5: Acquire buy-in from parties relevant to footprint initiative
- rule.footprint.6: Research results from footprint focus groups
- rule.footprint.7: Iterate on footprint look and feel
- rule.footprint.8: Ask on wider forum about gameplay impact of footprints
- rule.footprint.9: Q&A footprint pass
- rule.french_mode: French Mode
- rule.give_effect: Give every player infinite %s
- rule.give_items: Give every online player %s of %s
- rule.global_pitch: Change pitch of every sound by %s%%
- rule.glow_bees: Glow Bees
- rule.glowing_glow_squids: Make Glow Squids actually glow
- rule.god_of_lightning: Aquire more than just the power of thunder
- rule.grappling_fishing_rods: Grappling Fishing Rods
- rule.grummize: Grummize %s
- rule.haunted_world: The World is Haunted
- rule.increase_scale: Increase player scale by %sx
- rule.infinite_cakes: Infinite cakes
- rule.instacheese: Instacheese from Buckets
- rule.invisible_armor: Make armor invisible
- rule.item_despawn_time.change: Change item despawn timer from %s to %s
- rule.item_despawn_time.set: Set item despawn timer to %s
- rule.item_despawn.despawn_all: Despawn all items on ground
- rule.item_despawn.despawn_none: Never despawn items on ground
- rule.item_despawn.keep_player_drops: Don't despawn items dropped by player
- rule.item_use_speed: Multiply tool speed by %s%%
- rule.item.disabled: Disabled item: you haven't voted for this!
- rule.keep_friends_close: Keep your friends close
- rule.lava_blue_ice_replace: Spawn %s instead of %s when lava interacts with blue ice
- rule.lava_spread_tick_delay: Lava spread tick delay set to: %s
- rule.lava_water_replace: Spawn %s instead of %s when lava interacts with water
- rule.less_gravity: Flip gravity rules. Earth feels like moon now
- rule.less_interaction_updates: Less block updates from player interactions. Actually none at all...
- rule.loot_double_or_half: Multiply loot drops of %s by %s
- rule.mbe: Minecraft Bedrock Edition (aka Movable Block Entities)
- rule.midas_touch: Claim the power of the mighty Midas
- rule.milk_every_mob: Every mob can be milked
- rule.minecart_collisions.break: Minecarts break on high-speed collisions
- rule.minecart_collisions.explode: Minecarts explode on high-speed collisions
- rule.minecart_collisions.none: Disable minecarts breaking on collision
- rule.minecart_lies: Expose Minecart LIES!
- rule.mini_players: Mini Player Mode
- rule.moon.0: Just the normal Moon
- rule.moon.1: Big Romantic Moon. Be careful what you wish for, our scientists have warned us about unintended consequences.
- rule.moon.2: Buff the Moon to be even bigger and stronger!
- rule.moon.3: MOON TO THE MAX!
- rule.morrowind_power_player_movement: Move like a Morrowind powergamer
- rule.name_visibility.none: Never show entity names
- rule.name_visibility.normal: Hide entity names behind blocks
- rule.name_visibility.see_through: Always show entity names from behind blocks
- rule.natural_spawn_disable: Never naturally spawn %s
- rule.natural_spawn_replace: Replace natural spawns of %s with %s
- rule.nbt_crafting: Enable NBT crafting
- rule.new_vote_approve_option_count: Set maximum number of options per new approval vote to %s
- rule.new_vote_chance_per_tick: Set chance to start new vote on every tick to 1/%s
- rule.new_vote_cost: Set voting cost and/or limits to: %s
- rule.new_vote_disable_opt_out: Don't opt-out option to new votes with multiple choices
- rule.new_vote_duration_minutes: Set duration of new votes to %s minutes
- rule.new_vote_extra_effect_chance: Set probability of creating combined votes to %s%%
- rule.new_vote_extra_effect_max_count: Set maximum number of extra effects for new combined votes to %s
- rule.new_vote_max_approve_vote_count: Set maximum number of approval votes to %s
- rule.new_vote_max_repeal_vote_count: Set maximum number of repeal votes to %s
- rule.new_vote_repeal_option_count: Set maximum number of options per new repeal vote to %s
- rule.new_vote_repeal_vote_chance: Set chance of a new vote being a repeal vote to %s%%
- rule.normal_name_visibility: Set normal entity name display to: %s
- rule.nothing: Do Nothing
- rule.obfuscate_player_names: Obfuscate player names
- rule.only_mending_trades: Villagers only trade Mending
- rule.optimize_light_engine.always_light: Turn on light everywhere to improve light engine  performance
- rule.optimize_light_engine.loadshedding: Implement loadshedding to improve light engine performance
- rule.optimize_light_engine.never_light: Turn off light everywhere to improve light engine performance
- rule.optimize_light_engine.none: De-optimize light engine
- rule.optimize.change: Change optimization level from %s to %s
- rule.optimize.set: Set optimization level to %s
- rule.other_portal: Enable Other Portal
- rule.other_portal.oops: Error 404 Terrain Not Found
- rule.parent_trap: Parent Trap
- rule.payment.item: Villagers accept %s instead of gems
- rule.payment.seed_reshuffle: Villagers accept randomly assigned item instead of gems (reshuffle)
- rule.payment.seed: Villagers accept randomly assigned item instead of gems
- rule.persistent_parrots: Persistent Parrots. They will NEVER leave you.
- rule.phantom_phantom: Phantom Phantoms
- rule.pickaxe_block: Add Pickaxe Block
- rule.place_block: Add Place Block
- rule.player_head_drop: Players can drop head when exploded by charged creeper
- rule.pot_gems: Decorated pots drop gems when broken
- rule.potions_of_big: Brew Potion of Big with Bottle O' Enchanting
- rule.potions_of_small: Brew Potion of Small with Rabbit Hide
- rule.president: %s for president
- rule.president.tag: President %s
- rule.prevent_floating_trees: Prevent floating trees
- rule.proposal: Proposal #%s
- rule.push_limit: Piston Push Limit: %s
- rule.quorum_percent: Set number of players needed for a vote to pass to %s%% of online players
- rule.random_tnt_fuse: TNT fuse timer is random
- rule.ray_tracing: Add Ray Tracing. Note: Ray Tracing requires additional processing resources.
- rule.recipe_double_or_half: Multiply recipe output of %s by %s
- rule.recipe_flip.both: Shaped recipes accept all orientations
- rule.recipe_flip.flipped_only: Shaped recipes accept only mirrored recipes
- rule.recipe_flip.normal_only: Shaped recipes accept only exact recipes
- rule.recipe.minecraft.diamond_drows: Enable diamond drows
- rule.recipe.minecraft.m_banner_pattern: Enable suspicious banner pattern
- rule.recipe.minecraft.string_concatenation: Enable string concatenation
- rule.recipe.minecraft.wob: Enable wob recipe
- rule.remove_phantoms: Remove Phantoms
- rule.replace_block_model: Replace block model for %s with %s
- rule.replace_item_model: Replace item model for %s with %s
- rule.replace_items: Replace all %s with %s in player inventories
- rule.replace_loot_drop: Replace loot drop %s with %s
- rule.replace_recipe_output: Replace recipe output %s with %s
- rule.replace_sound: Replace sound %s with %s
- rule.reset_entity_transform: Clear every player's entity transform
- rule.reset_scale: Reset every player's scale
- rule.reset_skin: Reset all player skins
- rule.rideable_entities: Make all %s entities rideable
- rule.rowing_up_that_hill: Acknowledge boats as the superior way of transportation
- rule.rubies: Replace emerald item with ruby (and only that - we are too lazy to do it properly)
- rule.silent_vote: Don't display voting output
- rule.sneaking_name_visibility: Set sneaking entity name display to: %s
- rule.snitch: Announce player votes in chat
- rule.snitch.msg: %s voted for %s. %s
- rule.spawn_egg_chance: Set chance of entity dropping spawn egg to %s%%
- rule.stack_size_double_or_half: Multiply maximum stack size of %s by %s
- rule.sticky: Realistic piston block sticking rules. It now makes sense now!
- rule.swap_skies: Swap overworld and The End sky
- rule.text_style.aqua: Change '%s' to always render as aqua
- rule.text_style.black: Change '%s' to always render as black
- rule.text_style.blank: Blank '%s'
- rule.text_style.blue: Change '%s' to always render as blue
- rule.text_style.bold: Change '%s' to be thick
- rule.text_style.dark_aqua: Change '%s' to always render as dark aqua
- rule.text_style.dark_blue: Change '%s' to always render as dark blue
- rule.text_style.dark_gray: Change '%s' to always render as dark gray
- rule.text_style.dark_green: Change '%s' to always render as dark green
- rule.text_style.dark_purple: Change '%s' to always render as dark purple
- rule.text_style.dark_red: Change '%s' to always render as dark red
- rule.text_style.gold: Change '%s' to always render as gold
- rule.text_style.gray: Change '%s' to always render as gray
- rule.text_style.green: Change '%s' to always render as green
- rule.text_style.hide: Change '%s' to never render
- rule.text_style.illager: Send '%s' to dungeons
- rule.text_style.italic: Skew '%s'
- rule.text_style.light_purple: Change '%s' to always render as light purple
- rule.text_style.obfuscated: Change '%s' to a mess of pixels
- rule.text_style.red: Change '%s' to always render as red
- rule.text_style.sga: Change '%s' to be magic
- rule.text_style.strikethrough: Strike '%s' through
- rule.text_style.thin: Change '%s' to be thin
- rule.text_style.underline: Strike '%s' under
- rule.text_style.white: Change '%s' to always render as white
- rule.text_style.yellow: Change '%s' to always render as yellow
- rule.the_joke: Keep ignoring Mobbo
- rule.tie_strategy.fail: On tie fail vote
- rule.tie_strategy.pick_all: On tie pick all options
- rule.tie_strategy.pick_high: On tie pick option with higher number
- rule.tie_strategy.pick_low: On tie pick option with lower number
- rule.tie_strategy.pick_none: On tie remove tied option
- rule.tie_strategy.pick_random: On tie pick random option
- rule.tnt_tennis: Primed TNT can be knocked back
- rule.trails_and_tails: Get the Trails & Tails Update
- rule.transform_entity: Transform every player into a %s
- rule.transparent_players: Ghost Mode
- rule.ultra_realistic_mode: Ultra Realistic Mode
- rule.uncontrolable_lave: Uncontrollable lava
- rule.undead_players: Players are Undead
- rule.universal_jeb: The universal jeb_ experience™
- rule.unstable_tnt: All newly placed TNT blocks are unstable
- rule.vote_max_results: Pass up to %s rules per vote
- rule.vote_result_pass_without_voters: Pass vote even if it has no players voting for it
- rule.vote_result_pass_without_votes: Also apply options that have received no votes
- rule.vote_result_pick_random_if_vote_fails: Pass random options if vote fails
- rule.vote_result_reverse_counts: Pass lowest-voted option instead of highest-voted ones
- rule.vote_result_show_options: Don't show final vote counts
- rule.vote_result_show_voters: Reveal voters at the end of vote
- rule.votes_to_win_percent: Require passing votes to receive at least %s%% of all cast votes
- rule.voting_fireworks: Celebrate voting!
- rule.weather.rain.always: Always rain
- rule.weather.rain.default: Default rain rules
- rule.weather.rain.never: Never rain
- rule.weather.thunder.always: Always thunder
- rule.weather.thunder.default: Default thunder rules
- rule.weather.thunder.never: Never thunder
- rule.wheels_on_minecarts: Wheels-4-Minecarts!
- rule.world_of_giants: A World of Giants
- rule.zombie_apocalypse: It's the zombie apocalypse! Watch out for mushrooms. And zombies.
- selectWorld.edit.resetVotes: Reset All Vote Data :(
- selectWorld.edit.resetVotes.msg: Proceeding will remove all voting data, including all pending and/or approved proposals.
Use only when you can't live with consequences of your own actions and/or your world is otherwise unrecoverable.
- stat.minecraft.votes: Votes Cast
+ subtitles.block.sign.waxed_interact_fail: Sign wobbles
+ subtitles.block.sniffer.egg_crack: Sniffer Egg cracks
+ subtitles.block.sniffer.egg_hatch: Sniffer Egg hatches
- subtitles.entity.sniffer.egg_crack: Sniffer Egg cracks
- subtitles.entity.sniffer.egg_hatch: Sniffer Egg hatches
- tooltip.more_like_cooltip: The Long Tooltip Screen
- tooltip.too_long: Tooltip too long, press ctrl-click to show all
- vote.cost_diplay: %s × %s
- vote.cost: Cost:
- vote.cost.health: Health
- vote.cost.xp: Enchantment Points
- vote.count_per_option.description: votes per option
- vote.count_per_option.limit: %s/%s votes for this option
- vote.count_per_option.no_limit: %s votes for this option
- vote.count_per_proposal.description: votes per proposal
- vote.count_per_proposal.limit: %s/%s votes for this proposal
- vote.count_per_proposal.no_limit: %s votes for this proposal
- vote.current_rules: All approved rules (so far)
- vote.failed: Failed to vote: %s
- vote.finished: Voting finished for %s
- vote.no_change: No change
- vote.no_more_votes: No more votes
- vote.no_option: No option passed
- vote.no_option.random: No option passed, picking random option(s)
- vote.no_resources: Missing resources
- vote.option_count: Option #%s '%s' received %s vote(s) from %s player(s)
- vote.option_display: %s. %s
- vote.option_no_count: Option #%s '%s' voter(s):
- vote.option_vote_title: %s: option %s/%s
- vote.option_won: Option #%s '%s' won
- vote.option_won.no_effect: Option #%s '%s' won, but has no effects
- vote.quorum.not_reached: Quorum (%s) not reached
- vote.quorum.passed: Quorum passed: %s out of %s
- vote.show_current_rules: Show applied proposals
- vote.started: Started voting for %s (%s)
- vote.tie: Voting tie, using strategy '%s'
- vote.total_count: Received %s vote(s) from %s voter(s)
- vote.vote_count.minimum: Passing option needs at least %s votes
- vote.voted: ⯪ I Voted! ⯫
- vote.voter:     %s: %s
- vote.voters: Voters:
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
- minecraft/advancements/adventure/vote_1.json
- minecraft/advancements/adventure/vote_256.json
- minecraft/advancements/recipes/brewing/copper_sink.json
- minecraft/advancements/recipes/building_blocks/air_block.json
- minecraft/advancements/recipes/building_blocks/packed_air.json
- minecraft/advancements/recipes/combat/diamond_drows.json
- minecraft/advancements/recipes/combat/wob.json
- minecraft/advancements/recipes/misc/m_banner_pattern.json
- minecraft/advancements/recipes/misc/string_concatenation.json
- minecraft/advancements/recipes/redstone/bit_from_name_stonecutting.json
- minecraft/advancements/recipes/redstone/bit_from_tag_stonecutting.json
- minecraft/advancements/recipes/redstone/left_curly.json
- minecraft/advancements/recipes/redstone/left_square.json
- minecraft/advancements/recipes/redstone/name_from_name_tag_stonecutting.json
- minecraft/advancements/recipes/redstone/pickaxe_block.json
- minecraft/advancements/recipes/redstone/place_block.json
- minecraft/advancements/recipes/redstone/right_curly.json
- minecraft/advancements/recipes/redstone/right_square.json
- minecraft/advancements/recipes/redstone/tag_from_name_tag_stonecutting.json
- minecraft/damage_type/midas_curse.json
- minecraft/damage_type/on_moon.json
- minecraft/dimension_type/the_moon.json
- minecraft/loot_tables/blocks/cheese.json
- minecraft/loot_tables/blocks/copper_sink.json
- minecraft/loot_tables/blocks/copper_spleaves.json
- minecraft/loot_tables/blocks/filled_copper_sink.json
- minecraft/loot_tables/blocks/other_portal.json
- minecraft/loot_tables/blocks/pickaxe_block.json
- minecraft/loot_tables/blocks/place_block.json
- minecraft/loot_tables/chests/moon_lab.json
- minecraft/loot_tables/chests/moon_resuply.json
- minecraft/loot_tables/entities/moon_cow.json
- minecraft/loot_tables/entities/ray_tracing.json
- minecraft/loot_tables/gameplay/dream_piglin_bartering.json
- minecraft/recipes/air_block.json
- minecraft/recipes/bit_from_name_stonecutting.json
- minecraft/recipes/bit_from_tag_stonecutting.json
- minecraft/recipes/copper_sink.json
- minecraft/recipes/diamond_drows.json
- minecraft/recipes/dupe_hack.json
- minecraft/recipes/left_curly.json
- minecraft/recipes/left_square.json
- minecraft/recipes/m_banner_pattern.json
- minecraft/recipes/name_from_name_tag_stonecutting.json
- minecraft/recipes/nbt_crafting.json
- minecraft/recipes/packed_air.json
- minecraft/recipes/pickaxe_block.json
- minecraft/recipes/place_block.json
- minecraft/recipes/right_curly.json
- minecraft/recipes/right_square.json
- minecraft/recipes/string_concatenation.json
- minecraft/recipes/tag_from_name_tag_stonecutting.json
- minecraft/recipes/wob.json
- minecraft/tags/banner_pattern/pattern_item/m.json
- minecraft/tags/blocks/cordycep_block.json
+ minecraft/tags/blocks/enchantment_power_provider.json
+ minecraft/tags/blocks/enchantment_power_transmitter.json
+ minecraft/tags/blocks/replaceable_by_trees.json
- minecraft/tags/blocks/replaceable_plants.json
+ minecraft/tags/blocks/replaceable.json
+ minecraft/tags/blocks/sword_efficient.json
- minecraft/tags/items/copper.json
- minecraft/tags/items/heavy.json
- minecraft/worldgen/biome/the_moon.json
- minecraft/worldgen/configured_feature/large_crater.json
- minecraft/worldgen/configured_feature/lunar_base.json
- minecraft/worldgen/configured_feature/mega_crater.json
- minecraft/worldgen/configured_feature/small_crater.json
- minecraft/worldgen/noise_settings/moon.json
- minecraft/worldgen/placed_feature/crater_large.json
- minecraft/worldgen/placed_feature/crater_mega.json
- minecraft/worldgen/placed_feature/crater_small.json
- minecraft/worldgen/placed_feature/lunar_base.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
- minecraft/blockstates/cheese.json
- minecraft/blockstates/copper_sink.json
- minecraft/blockstates/copper_spleaves.json
- minecraft/blockstates/filled_copper_sink.json
- minecraft/blockstates/other_portal.json
- minecraft/blockstates/packed_air.json
- minecraft/blockstates/pickaxe_block.json
- minecraft/blockstates/place_block.json
- minecraft/models/block/cheese_1.json
- minecraft/models/block/cheese_10.json
- minecraft/models/block/cheese_100.json
- minecraft/models/block/cheese_1000.json
- minecraft/models/block/cheese_10000.json
- minecraft/models/block/cheese_100000.json
- minecraft/models/block/cheese_1000000.json
- minecraft/models/block/cheese_10000000.json
- minecraft/models/block/cheese_10000001.json
- minecraft/models/block/cheese_1000001.json
- minecraft/models/block/cheese_10000010.json
- minecraft/models/block/cheese_10000011.json
- minecraft/models/block/cheese_100001.json
- minecraft/models/block/cheese_1000010.json
- minecraft/models/block/cheese_10000100.json
- minecraft/models/block/cheese_10000101.json
- minecraft/models/block/cheese_1000011.json
- minecraft/models/block/cheese_10000110.json
- minecraft/models/block/cheese_10000111.json
- minecraft/models/block/cheese_10001.json
- minecraft/models/block/cheese_100010.json
- minecraft/models/block/cheese_1000100.json
- minecraft/models/block/cheese_10001000.json
- minecraft/models/block/cheese_10001001.json
- minecraft/models/block/cheese_1000101.json
- minecraft/models/block/cheese_10001010.json
- minecraft/models/block/cheese_10001011.json
- minecraft/models/block/cheese_100011.json
- minecraft/models/block/cheese_1000110.json
- minecraft/models/block/cheese_10001100.json
- minecraft/models/block/cheese_10001101.json
- minecraft/models/block/cheese_1000111.json
- minecraft/models/block/cheese_10001110.json
- minecraft/models/block/cheese_10001111.json
- minecraft/models/block/cheese_1001.json
- minecraft/models/block/cheese_10010.json
- minecraft/models/block/cheese_100100.json
- minecraft/models/block/cheese_1001000.json
- minecraft/models/block/cheese_10010000.json
- minecraft/models/block/cheese_10010001.json
- minecraft/models/block/cheese_1001001.json
- minecraft/models/block/cheese_10010010.json
- minecraft/models/block/cheese_10010011.json
- minecraft/models/block/cheese_100101.json
- minecraft/models/block/cheese_1001010.json
- minecraft/models/block/cheese_10010100.json
- minecraft/models/block/cheese_10010101.json
- minecraft/models/block/cheese_1001011.json
- minecraft/models/block/cheese_10010110.json
- minecraft/models/block/cheese_10010111.json
- minecraft/models/block/cheese_10011.json
- minecraft/models/block/cheese_100110.json
- minecraft/models/block/cheese_1001100.json
- minecraft/models/block/cheese_10011000.json
- minecraft/models/block/cheese_10011001.json
- minecraft/models/block/cheese_1001101.json
- minecraft/models/block/cheese_10011010.json
- minecraft/models/block/cheese_10011011.json
- minecraft/models/block/cheese_100111.json
- minecraft/models/block/cheese_1001110.json
- minecraft/models/block/cheese_10011100.json
- minecraft/models/block/cheese_10011101.json
- minecraft/models/block/cheese_1001111.json
- minecraft/models/block/cheese_10011110.json
- minecraft/models/block/cheese_10011111.json
- minecraft/models/block/cheese_101.json
- minecraft/models/block/cheese_1010.json
- minecraft/models/block/cheese_10100.json
- minecraft/models/block/cheese_101000.json
- minecraft/models/block/cheese_1010000.json
- minecraft/models/block/cheese_10100000.json
- minecraft/models/block/cheese_10100001.json
- minecraft/models/block/cheese_1010001.json
- minecraft/models/block/cheese_10100010.json
- minecraft/models/block/cheese_10100011.json
- minecraft/models/block/cheese_101001.json
- minecraft/models/block/cheese_1010010.json
- minecraft/models/block/cheese_10100100.json
- minecraft/models/block/cheese_10100101.json
- minecraft/models/block/cheese_1010011.json
- minecraft/models/block/cheese_10100110.json
- minecraft/models/block/cheese_10100111.json
- minecraft/models/block/cheese_10101.json
- minecraft/models/block/cheese_101010.json
- minecraft/models/block/cheese_1010100.json
- minecraft/models/block/cheese_10101000.json
- minecraft/models/block/cheese_10101001.json
- minecraft/models/block/cheese_1010101.json
- minecraft/models/block/cheese_10101010.json
- minecraft/models/block/cheese_10101011.json
- minecraft/models/block/cheese_101011.json
- minecraft/models/block/cheese_1010110.json
- minecraft/models/block/cheese_10101100.json
- minecraft/models/block/cheese_10101101.json
- minecraft/models/block/cheese_1010111.json
- minecraft/models/block/cheese_10101110.json
- minecraft/models/block/cheese_10101111.json
- minecraft/models/block/cheese_1011.json
- minecraft/models/block/cheese_10110.json
- minecraft/models/block/cheese_101100.json
- minecraft/models/block/cheese_1011000.json
- minecraft/models/block/cheese_10110000.json
- minecraft/models/block/cheese_10110001.json
- minecraft/models/block/cheese_1011001.json
- minecraft/models/block/cheese_10110010.json
- minecraft/models/block/cheese_10110011.json
- minecraft/models/block/cheese_101101.json
- minecraft/models/block/cheese_1011010.json
- minecraft/models/block/cheese_10110100.json
- minecraft/models/block/cheese_10110101.json
- minecraft/models/block/cheese_1011011.json
- minecraft/models/block/cheese_10110110.json
- minecraft/models/block/cheese_10110111.json
- minecraft/models/block/cheese_10111.json
- minecraft/models/block/cheese_101110.json
- minecraft/models/block/cheese_1011100.json
- minecraft/models/block/cheese_10111000.json
- minecraft/models/block/cheese_10111001.json
- minecraft/models/block/cheese_1011101.json
- minecraft/models/block/cheese_10111010.json
- minecraft/models/block/cheese_10111011.json
- minecraft/models/block/cheese_101111.json
- minecraft/models/block/cheese_1011110.json
- minecraft/models/block/cheese_10111100.json
- minecraft/models/block/cheese_10111101.json
- minecraft/models/block/cheese_1011111.json
- minecraft/models/block/cheese_10111110.json
- minecraft/models/block/cheese_10111111.json
- minecraft/models/block/cheese_11.json
- minecraft/models/block/cheese_110.json
- minecraft/models/block/cheese_1100.json
- minecraft/models/block/cheese_11000.json
- minecraft/models/block/cheese_110000.json
- minecraft/models/block/cheese_1100000.json
- minecraft/models/block/cheese_11000000.json
- minecraft/models/block/cheese_11000001.json
- minecraft/models/block/cheese_1100001.json
- minecraft/models/block/cheese_11000010.json
- minecraft/models/block/cheese_11000011.json
- minecraft/models/block/cheese_110001.json
- minecraft/models/block/cheese_1100010.json
- minecraft/models/block/cheese_11000100.json
- minecraft/models/block/cheese_11000101.json
- minecraft/models/block/cheese_1100011.json
- minecraft/models/block/cheese_11000110.json
- minecraft/models/block/cheese_11000111.json
- minecraft/models/block/cheese_11001.json
- minecraft/models/block/cheese_110010.json
- minecraft/models/block/cheese_1100100.json
- minecraft/models/block/cheese_11001000.json
- minecraft/models/block/cheese_11001001.json
- minecraft/models/block/cheese_1100101.json
- minecraft/models/block/cheese_11001010.json
- minecraft/models/block/cheese_11001011.json
- minecraft/models/block/cheese_110011.json
- minecraft/models/block/cheese_1100110.json
- minecraft/models/block/cheese_11001100.json
- minecraft/models/block/cheese_11001101.json
- minecraft/models/block/cheese_1100111.json
- minecraft/models/block/cheese_11001110.json
- minecraft/models/block/cheese_11001111.json
- minecraft/models/block/cheese_1101.json
- minecraft/models/block/cheese_11010.json
- minecraft/models/block/cheese_110100.json
- minecraft/models/block/cheese_1101000.json
- minecraft/models/block/cheese_11010000.json
- minecraft/models/block/cheese_11010001.json
- minecraft/models/block/cheese_1101001.json
- minecraft/models/block/cheese_11010010.json
- minecraft/models/block/cheese_11010011.json
- minecraft/models/block/cheese_110101.json
- minecraft/models/block/cheese_1101010.json
- minecraft/models/block/cheese_11010100.json
- minecraft/models/block/cheese_11010101.json
- minecraft/models/block/cheese_1101011.json
- minecraft/models/block/cheese_11010110.json
- minecraft/models/block/cheese_11010111.json
- minecraft/models/block/cheese_11011.json
- minecraft/models/block/cheese_110110.json
- minecraft/models/block/cheese_1101100.json
- minecraft/models/block/cheese_11011000.json
- minecraft/models/block/cheese_11011001.json
- minecraft/models/block/cheese_1101101.json
- minecraft/models/block/cheese_11011010.json
- minecraft/models/block/cheese_11011011.json
- minecraft/models/block/cheese_110111.json
- minecraft/models/block/cheese_1101110.json
- minecraft/models/block/cheese_11011100.json
- minecraft/models/block/cheese_11011101.json
- minecraft/models/block/cheese_1101111.json
- minecraft/models/block/cheese_11011110.json
- minecraft/models/block/cheese_11011111.json
- minecraft/models/block/cheese_111.json
- minecraft/models/block/cheese_1110.json
- minecraft/models/block/cheese_11100.json
- minecraft/models/block/cheese_111000.json
- minecraft/models/block/cheese_1110000.json
- minecraft/models/block/cheese_11100000.json
- minecraft/models/block/cheese_11100001.json
- minecraft/models/block/cheese_1110001.json
- minecraft/models/block/cheese_11100010.json
- minecraft/models/block/cheese_11100011.json
- minecraft/models/block/cheese_111001.json
- minecraft/models/block/cheese_1110010.json
- minecraft/models/block/cheese_11100100.json
- minecraft/models/block/cheese_11100101.json
- minecraft/models/block/cheese_1110011.json
- minecraft/models/block/cheese_11100110.json
- minecraft/models/block/cheese_11100111.json
- minecraft/models/block/cheese_11101.json
- minecraft/models/block/cheese_111010.json
- minecraft/models/block/cheese_1110100.json
- minecraft/models/block/cheese_11101000.json
- minecraft/models/block/cheese_11101001.json
- minecraft/models/block/cheese_1110101.json
- minecraft/models/block/cheese_11101010.json
- minecraft/models/block/cheese_11101011.json
- minecraft/models/block/cheese_111011.json
- minecraft/models/block/cheese_1110110.json
- minecraft/models/block/cheese_11101100.json
- minecraft/models/block/cheese_11101101.json
- minecraft/models/block/cheese_1110111.json
- minecraft/models/block/cheese_11101110.json
- minecraft/models/block/cheese_11101111.json
- minecraft/models/block/cheese_1111.json
- minecraft/models/block/cheese_11110.json
- minecraft/models/block/cheese_111100.json
- minecraft/models/block/cheese_1111000.json
- minecraft/models/block/cheese_11110000.json
- minecraft/models/block/cheese_11110001.json
- minecraft/models/block/cheese_1111001.json
- minecraft/models/block/cheese_11110010.json
- minecraft/models/block/cheese_11110011.json
- minecraft/models/block/cheese_111101.json
- minecraft/models/block/cheese_1111010.json
- minecraft/models/block/cheese_11110100.json
- minecraft/models/block/cheese_11110101.json
- minecraft/models/block/cheese_1111011.json
- minecraft/models/block/cheese_11110110.json
- minecraft/models/block/cheese_11110111.json
- minecraft/models/block/cheese_11111.json
- minecraft/models/block/cheese_111110.json
- minecraft/models/block/cheese_1111100.json
- minecraft/models/block/cheese_11111000.json
- minecraft/models/block/cheese_11111001.json
- minecraft/models/block/cheese_1111101.json
- minecraft/models/block/cheese_11111010.json
- minecraft/models/block/cheese_11111011.json
- minecraft/models/block/cheese_111111.json
- minecraft/models/block/cheese_1111110.json
- minecraft/models/block/cheese_11111100.json
- minecraft/models/block/cheese_11111101.json
- minecraft/models/block/cheese_1111111.json
- minecraft/models/block/cheese_11111110.json
- minecraft/models/block/cheese_11111111.json
- minecraft/models/block/copper_sink.json
- minecraft/models/block/copper_spleaves_broken.json
- minecraft/models/block/copper_spleaves.json
- minecraft/models/block/filled_copper_sink.json
- minecraft/models/block/other_portal_ew.json
- minecraft/models/block/other_portal_ns.json
- minecraft/models/block/packed_air.json
- minecraft/models/block/pickaxe_block.json
- minecraft/models/block/place_block.json
- minecraft/models/block/spleaves.json
- minecraft/models/block/template_copper_sink_full.json
- minecraft/models/item/air_block.json
- minecraft/models/item/bit.json
- minecraft/models/item/bottle_of_entity.json
- minecraft/models/item/bottle_of_void.json
- minecraft/models/item/byte_tag.json
- minecraft/models/item/cheese.json
- minecraft/models/item/compound_tag.json
- minecraft/models/item/copper_sink.json
- minecraft/models/item/copper_spleaves.json
- minecraft/models/item/double_tag.json
- minecraft/models/item/dupe_hack.json
- minecraft/models/item/float_tag.json
- minecraft/models/item/int_tag.json
- minecraft/models/item/la_baguette.json
- minecraft/models/item/le_tricolore.json
- minecraft/models/item/left_curly.json
- minecraft/models/item/left_square.json
- minecraft/models/item/list_tag.json
- minecraft/models/item/long_tag.json
- minecraft/models/item/m_banner_pattern.json
- minecraft/models/item/moon_cow_spawn_egg.json
- minecraft/models/item/name.json
- minecraft/models/item/packed_air.json
- minecraft/models/item/pickaxe_block.json
- minecraft/models/item/place_block.json
- minecraft/models/item/right_curly.json
- minecraft/models/item/right_square.json
- minecraft/models/item/ruby.json
- minecraft/models/item/short_tag.json
- minecraft/models/item/splash_bottle_of_entity.json
- minecraft/models/item/string_tag.json
- minecraft/models/item/string2.json
- minecraft/models/item/syntax_error.json
- minecraft/models/item/tag.json
+ minecraft/models/item/template_music_disc.json
- minecraft/particles/footstep.json
- minecraft/shaders/core/position_tex_funky.fsh
- minecraft/shaders/core/position_tex_funky.json
- minecraft/shaders/post/bloom.json
- minecraft/shaders/program/brightness_threshold.fsh
- minecraft/shaders/program/brightness_threshold.json
- minecraft/shaders/program/merge_bloom.fsh
- minecraft/shaders/program/merge_bloom.json
- minecraft/textures/block/cheese.png
- minecraft/textures/block/copper_sink_bottom.png
- minecraft/textures/block/copper_sink_inner.png
- minecraft/textures/block/copper_sink_side.png
- minecraft/textures/block/copper_sink_top.png
- minecraft/textures/block/copper_spleaves_broken.png
- minecraft/textures/block/copper_spleaves.png
- minecraft/textures/block/other_portal.png
- minecraft/textures/block/other_portal.png.mcmeta
- minecraft/textures/block/packed_air_alt.png
- minecraft/textures/block/packed_air.png
- minecraft/textures/block/pickaxe_block_back.png
- minecraft/textures/block/pickaxe_block_front.png
- minecraft/textures/block/pickaxe_block_side.png
- minecraft/textures/block/place_block_back.png
- minecraft/textures/block/place_block_front.png
- minecraft/textures/block/place_block_side.png
- minecraft/textures/effect/crown.png
- minecraft/textures/effect/mustache.png
- minecraft/textures/entity/banner/m.png
- minecraft/textures/entity/chest/gold.png
- minecraft/textures/entity/cow/moon_cow.png
- minecraft/textures/entity/player/caeps/awesom.png
- minecraft/textures/entity/player/caeps/blonk.png
- minecraft/textures/entity/player/caeps/no_circle.png
- minecraft/textures/entity/player/caeps/nyan.png
- minecraft/textures/entity/player/caeps/squid.png
- minecraft/textures/entity/player/caeps/veterinarian.png
- minecraft/textures/entity/player/tails/alex.png
- minecraft/textures/entity/player/tails/ari.png
- minecraft/textures/entity/player/tails/black_fox.png
- minecraft/textures/entity/player/tails/brown_bear.png
- minecraft/textures/entity/player/tails/earthern.png
- minecraft/textures/entity/player/tails/efe.png
- minecraft/textures/entity/player/tails/fire_fox.png
- minecraft/textures/entity/player/tails/kai.png
- minecraft/textures/entity/player/tails/makena.png
- minecraft/textures/entity/player/tails/noor.png
- minecraft/textures/entity/player/tails/red_fox.png
- minecraft/textures/entity/player/tails/snow_fox.png
- minecraft/textures/entity/player/tails/steve.png
- minecraft/textures/entity/player/tails/striped.png
- minecraft/textures/entity/player/tails/sunny.png
- minecraft/textures/entity/player/tails/zuri.png
- minecraft/textures/entity/player/wide/ray.png
- minecraft/textures/entity/shield/m.png
- minecraft/textures/environment/earth_1.png
- minecraft/textures/environment/earth_a.png
- minecraft/textures/environment/earth_prime.png
- minecraft/textures/environment/earth.png
- minecraft/textures/font/checkmark.png
+ minecraft/textures/gui/title/edition.png.mcmeta
+ minecraft/textures/gui/title/minceraft.png
+ minecraft/textures/gui/title/minceraft.png.mcmeta
+ minecraft/textures/gui/title/minecraft.png.mcmeta
- minecraft/textures/gui/tvpi.png
- minecraft/textures/gui/votes.png
- minecraft/textures/gui/voting.png
- minecraft/textures/item/air_block.png
- minecraft/textures/item/bit.png
- minecraft/textures/item/bottle_of_entity.png
- minecraft/textures/item/bottle_of_void.png
- minecraft/textures/item/byte_tag.png
- minecraft/textures/item/compound_tag.png
- minecraft/textures/item/double_tag.png
- minecraft/textures/item/end_tag.png
- minecraft/textures/item/float_tag.png
- minecraft/textures/item/int_tag.png
- minecraft/textures/item/la_baguette.png
- minecraft/textures/item/le_tricolore.png
- minecraft/textures/item/left_curly.png
- minecraft/textures/item/left_square.png
- minecraft/textures/item/list_tag.png
- minecraft/textures/item/long_tag.png
- minecraft/textures/item/m_banner_pattern.png
- minecraft/textures/item/name.png
- minecraft/textures/item/right_curly.png
- minecraft/textures/item/right_square.png
- minecraft/textures/item/ruby.png
- minecraft/textures/item/short_tag.png
- minecraft/textures/item/skis.png
- minecraft/textures/item/splash_bottle_of_entity.png
- minecraft/textures/item/string_tag.png
- minecraft/textures/item/string2.png
- minecraft/textures/item/syntax_error.png
- minecraft/textures/item/tag.png
- minecraft/textures/misc/enchanted_glint_gold.png
- minecraft/textures/mob_effect/big.png
- minecraft/textures/mob_effect/small.png
- minecraft/textures/models/armor/beret.png
- minecraft/textures/particle/footprint.png
- nothingtoseeheremovealong/lang/fr_fr.json
- nothingtoseeheremovealong/sounds.json
- nothingtoseeheremovealong/sounds/the_joke/sad1.ogg
- nothingtoseeheremovealong/sounds/the_joke/sad2.ogg
- nothingtoseeheremovealong/sounds/the_joke/sad3.ogg
- nothingtoseeheremovealong/sounds/the_joke/sad4.ogg
+ realms/textures/gui/title/realms.png.mcmeta
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
+ ...!
+ .party()!
+ "Almost never" is an interesting concept!
+ "Autological" is!
+ [this splash text is now available]
+ §1C§2o§3l§4o§5r§6m§7a§8t§9i§ac
+ §kFUNKY LOL
+ /give @a hugs 64
+ #minecraftfarms
+ <3 Max & 99 & Ducky!
- ✅
- ❎
+ 1% sugar!
+ 10 years of Mining and Crafting!
+ 100% pure!
+ 12 herbs and spices!
+ 12345 is a bad password!
+ 150 bpm for 400000 minutes!
+ 150% hyperbole!
+ 20 GOTO 10!
+ 4815162342 lines of code!
+ 90% bug free!
+ 90210!
+ A riddle, wrapped in a mystery!
+ A skeleton popped out!
- A/B Voting!
+ Absolutely fixed relatively broken coordinates
+ Absolutely no memes!
+ Afraid of the big, black bat!
+ Age of Wonders is better!
+ Ahhhhhh!
+ All inclusive!
+ All is full of love!
+ All rumors are true!
+ Also try Braid!
+ Also try Limbo!
+ Also try Minecraft Dungeons!
+ Also try Mount And Blade!
+ Also try Pixeljunk Shooter!
+ Also try Project Zomboid!
+ Also try Super Meat Boy!
+ Also try Terraria!
+ Also try VVVVVV!
+ Also try World of Goo!
+ Amplify and listen to BIPOC voices!
+ An illusion! What are you hiding?
+ And my pickaxe!
+ Any computer is a laptop if you're brave enough!
+ As seen on TV!
- As You Wish!
+ Ask your doctor!
+ Autonomous!
+ Awesome community!
+ Awesome game design right there!
+ Awesome!
+ Aww man!
+ Be anti-racist!
+ Bees, bees, bees, bees!
+ Bekarton guards the gate!
+ Best in class!
+ Big Pointy Teeth!
+ Bigger than a bread box!
+ Black lives matter!
+ Blue warrior shot the food!
+ Board game version also available!
+ Boats FTW
+ Boots with the fur!
+ Bread is pain!
+ Bring it on!
+ Bring me Ray Cokes!
+ Bringing home the bacon!
+ BTAF used to be good!
+ Buckets of lava!
+ Bushy eyebrows!
+ Buzzy Bees!
- By Popular Vote!
+ Call your mother!
- Can't Blame The Developers For Your Choices!
+ Casual gaming!
+ Ceci n'est pas une title screen!
+ Check it out!
+ Check out the far lands!
+ Child's play!
- Choice Edition!
- Choose Wisely!
- Choose Your Own Adventure!
+ Classy!
+ Closed source!
+ Cloud computing!
+ Cogito ergo sum!
+ Collaborate and listen!
- Community Choice!
+ Complex cellular automata!
+ Consummate V's!
+ Contains infinite genders!
+ Contains simulated goats!
+ Conventional!
+ Cough or sneeze into your elbow!
+ Cow Tools!
+ Create!
+ Croak team!
+ Cruising streets for gold!
+ Cześć Polsko!
+ Déjà vu!
+ Déjà vu!
- Democratic!
+ Do it all, everything!
+ Do not distribute!
+ Do you want to join my server?
+ Does barrel rolls!
+ Doesn't avoid double negatives!
+ Doesn't use the U-word!
+ Don't bother with the clones!
+ Don't feed avocados to parrots!
+ Don't feed chocolate to parrots!
+ Don't look directly at the bugs!
+ Don’t touch your face!
+ Don't worry, be happy!
+ doot doot
+ Double buffered!
+ DRR! DRR! DRR!
+ Dungeon!
+ DungeonQuest is unfair!
+ Edit is a name!
+ Educate your friends on anti-racism!
+ Engage!
+ Enhanced!
+ Envision! Create! Share!
+ Eple (original edit)!
+ Euclidian!
+ Everybody do the Leif!
+ Excitement!
+ Exclusive!
+ Exploding creepers!
+ Extra things!
+ Fabulous graphics!
- Fair Votes Guaranteed!
+ Falling off cliffs!
+ Falling with style!
+ Fan fiction!
+ Fantasy!
+ Fat free!
+ Feature packed!
+ Finally complete!
+ Finally with ladders!
+ Find your claw!
+ Finger-licking!
+ Flashing letters!
+ Flavor with no seasoning!
+ Flaxkikare!
+ Flower forest TM perfume
+ Fnord!
+ Follow the train, CJ!
+ Freaky!
+ Free dental!
- Freedom of Choice!
+ From free range developers!
+ From the streets of Södermalm!
+ Full of stars!
+ Funk soul brother!
- Game-Changing Votes!
+ Gamers unite – separately in your own homes!
+ Gargamel plays it!
+ Gasp!
+ Get to the coppah!
+ Ghoughpteighbteau tchoghs!
+ Give us Gordon!
+ GNU Terry Pratchett
+ Go to the dentist!
+ Google anlyticsed!
+ Got your nose!
+ GOTY!
+ Guaranteed!
+ Haha, LOL!
+ Haley loves Elan!
+ Hampsterdance!
+ Han shot first!
+ Hang out with your friends online!
+ Hard to label!
+ Has an ending!
+ Hat Fridays!
+ Haunted!
+ Heaps of hits on YouTube!
+ Helo Cymru!
+ Herregud!
+ Holy cow, man!
+ Home-made!
+ Homeomorphic to a 3-sphere!
+ Honey, I grew the bees!
+ Honey, I waxed the copper!
+ Hot tamale, hot hot tamale!
+ Hotter than the sun!
+ HURNERJSGER?
- I Demand a Recount!
+ I have a suggestion.
+ I miss ADOM!
+ I need more context.
+ I see your vocabulary has improved!
- I Voted!
+ I'm glad you're here!
+ idspispopd!
+ if not ok then return end
+ In case it isn't obvious, foxes aren't players.
+ Indev!
+ Indie!
+ Information wants to be free!
+ Ingots!
+ Inspirational!
+ Internet enabled!
+ It came from space.
+ It swings, it jives!
+ It's a game!
+ It's finished!
+ It's groundbreaking!
+ It's here!
+ Jag känner en bot!
+ Jason! Jason! Jason!
+ Java 16 + 1 = 17!
+ Javalicious edition
+ Jeb has amazing hair!
+ Joel is neat!
+ Jump up, jump up, and get down!
+ Kaaneeeedaaaa!
+ Keyboard compatible!
+ Khaaaaaaaaan!
+ Kick it root down!
+ Kind of dragon free!
+ Kinda like Lemmings!
+ Kiss the sky!
+ l33t!
+ Larger than Earth!
+ Learn about allyship!
+ Legal in Finland!
+ Lennart lennart = new Lennart();
+ Less addictive than TV Tropes!
+ Let our battle's begin!
+ Let's danec!
+ Leveraging synergy!
+ Limited edition!
+ Lives in a pineapple under the sea!
+ Livestreamed!
+ Look mum, I'm in a splash!
+ Lots of truthiness!
+ Loved by millions!
- Machine Voting!
+ Macroscopic!
+ Made by "real" people!
+ Made by Jeb!
+ Made in Sweden!
+ Made with lave!
+ Make me a table, a funky table!
- Make Your Voice Heard!
+ MAP11 has two names!
+ Matt Damon!
+ May contain nuts!
+ May contain traces of citrus!
+ Meeting expectations!
+ Menger sponge!
+ Millions of peaches!
+ Minecraft Java Edition presents: Disgusting Bugs
+ Minecraft!
+ Minors welcome!
+ Mmmph, mmph!
- Mob Votes! Biome Votes! Food Votes! Moon Votes!
+ Moderately attractive!
+ Monster infighting!
+ More addictive than lemonade!
+ More Digital!
+ More polygons!
+ More than 500 sold!
- Multiple Choice Gaming!
+ Music by C418!
+ Music by Lena Raine!
+ My life for Aiur!
+ Never dig down!
+ Nice to meet you!
+ Nooooooooooooo!
+ Not as cool as Spock!
+ Not linear!
+ Not on steam!
+ Now contains 32 random daily cats!
+ Now in 3D!
+ Now on OpenGL 3.2 core profile!
+ Now supports åäö!
+ Now with additional stuff!
+ Now with difficulty!
+ Now with extra hugs!
+ Now With Multiplayer!
+ Now you are thinking with pistons!
+ NP is not in P!
+ Octagonal!
+ Oh man!
+ Oh, ok, Pigmen!
+ OICU812!
+ Omnipotent!
+ One day, somewhere in the future, my work will be quoted!
+ One of a kind!
- Online Voting!
+ PC gaming since 1873!
- People's Choice!
+ Peter Griffin!
+ Ph1lza had a good run!
+ Phobos anomaly!
- Picking and Choosing!
+ Ping the human!
+ Pixels!
+ Place ALL the blocks!
+ Plant a tree!
+ Plant-based light sources!
+ Play him off, keyboard cat!
+ Play Minecraft, Watch Topgear, Get Pig!
+ Played by cowboys!
+ pls rt
+ Plz reply to my tweet!
+ Pneumatic!
+ Polynomial!
+ Prepare, but don’t hoard!
+ Pretty scary!
+ Pretty!
+ Pumpa kungen!
+ Pumpkinhead!
+ Punching wood!
+ Put a little fence around it!
+ Put that cookie down!
+ Rainbow turtle?
+ Random splash!
+ Read more books!
+ Reference implementation!
+ Regional resources!
+ Replaced molten cheese with blood?
+ Representing Edsbyn!
+ Reticulating splines!
+ RIBBIT!
+ Ride the pig!
+ Rise from your grave!
+ Rita is the new top dog!
+ Rule #1: it's never my fault
+ Run, coward! I hunger!
+ Ryan also has amazing hair!
+ Save the world – stay inside!
+ Scary!
+ Scientific!
+ See you next Friday or so!
+ Seecret Friday update!
+ Sensational!
+ Shop for your elders!
+ Should not be played while driving
+ Shriek like a Sculk Shrieker!
+ Singleplayer!
+ Slow acting portals!
+ So fresh, so clean!
+ So sweet, like a nice bon bon!
+ Soap and water!
+ Something funny!
+ Something's not quite right...
+ Speak OUT against injustice and UP for equality!
+ Spiders everywhere!
+ sqrt(-1) love you!
+ Stand up for equality in your community!
+ Stay a while and listen!
+ Stay a while, stay forever!
+ Stay home and play games!
+ Stay safe!
+ Stay strong!
+ Stop being reasonable, this is the Internet!
+ Stop, hammertime!
+ Strange, but not a stranger!
+ Sublime!
+ Supercalifragilisticexpialidocious!
+ Support elderly relatives and friends!
+ Support local businesses!
+ Support the BIPOC community and creators!
+ Survive!
+ SWM forever!
+ Swords for everyone!
+ Synecdoche!
+ Take an eggbeater and beat it against a skillet!
+ Take frequent breaks!
+ Take her pillow!
+ Take the elevator to the mezzanine!
+ Technically good!
+ Technoblade never dies!
+ Technologic!
+ Teetsuuuuoooo!
+ Tell your friends!
+ Terrestrial!
+ Testificates!
+ Thank you for the fish!
+ That's no moon!
+ That's Numberwang!
+ That's super!
+ The bee's knees!
- The Chosen Challenge!
+ The creeper is a spy!
+ The cutest predator you'll ever meet!
- The Golden Vote!
+ The sky is the limit!
+ The sum of its parts!
+ The true meaning of covfefe
+ Thematic!
+ There's <<a cat on ,my keyboard!~
+ There's no stopping the Trollmaso
+ This is good for Realms.
+ This is my true form!
+ This message will never appear on the splash screen, isn't that weird?
+ This parrot is no more! It has ceased to be!
+ This text is hard to read if you play the game at the default resolution, but at 1080p it's fine!
+ Thousands of colors!
+ Throw a blanket over it!
+ Throw yourself at the ground and miss
+ Tip your waiter!
- To the Moon!
+ Tougher than diamonds, rich like cream!
+ Treatment for your rash!
+ Truly gone fishing!
+ Try it!
+ Try the mushroom stew!
+ Try the Nether!
+ Turing complete!
+ Twittered about!
+ Tyrion would love it!
+ Ultimate edition!
+ umop-apisdn!
+ Undefeated!
+ Une baguette!
+ Uninflammable!
+ Uses LWJGL!
+ Vanilla!
+ Verlet intregration!
+ Very fun!
+ Very influential in its circle!
+ Vote for net neutrality!
- Vote With Your Gaming!
- Vote-Driven Development!
- Vote!
- Voted Game of the Year!
- Voting About Voting!
- Vox Populi, Vox Dei!
+ Warning! A huge battleship "STEVE" is approaching fast!
+ Wash your hands!
+ Water bottle!
+ Water proof!
+ Welcome to your Doom!
+ What do you expect?
+ What's the question?
+ What's up, Doc?
+ Where there is not light, there can spider!
+ Who let the frogs out?
+ Who put it there?
+ Whoa, dude!
+ Woah.
+ Woo, 2pp!
+ Woo, facepunch!
+ Woo, reddit!
+ Woo, somethingawful!
+ Woo, tigsource!
+ Woo, worldofminecraft!
+ Wow!
+ Yaaay!
+ Yay, puppies for everyone!
+ Yes, sir!
+ You are valid!
+ You are welcome here!
+ You can't explain that!
- You Decide!
+ You're going too fast!
+ You've got a brand new key!
- Your Call!
+ Your gender is valid!
+ Zoglin!?
+ Γεια σου Ελλάδα!
+ 한국 안녕하세요!
+ 你好中国！
+ 日本ハロー！
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
- XXX.ai.attributes.Attribute
+ XXX.ai.attributes.AttributeInstance
- XXX.ai.attributes.AttributeMap
+ XXX.ai.attributes.AttributeModifier
- XXX.ai.attributes.AttributeModifier$Operation
+ XXX.ai.attributes.Attributes
+ XXX.ai.attributes.AttributeSupplier
- XXX.ai.attributes.AttributeSupplier$Builder
- XXX.ai.attributes.DefaultAttributes
- XXX.ai.attributes.package-info
+ XXX.ai.attributes.RangedAttribute
+ XXX.ai.behavior.AcquirePoi
- XXX.ai.behavior.AcquirePoi$JitteredLinearRetry
+ XXX.ai.behavior.AnimalMakeLove
- XXX.ai.behavior.AnimalPanic
+ XXX.ai.behavior.AssignProfessionFromJobSite
- XXX.ai.behavior.BabyFollowAdult
+ XXX.ai.behavior.BackUpIfTooClose
- XXX.ai.behavior.BecomePassiveIfMemoryPresent
+ XXX.ai.behavior.Behavior
- XXX.ai.behavior.Behavior$Status
+ XXX.ai.behavior.BehaviorControl
- XXX.ai.behavior.BehaviorUtils
+ XXX.ai.behavior.BlockPosTracker
- XXX.ai.behavior.CelebrateVillagersSurvivedRaid
+ XXX.ai.behavior.CopyMemoryWithExpiry
- XXX.ai.behavior.CountDownCooldownTicks
+ XXX.ai.behavior.Croak
- XXX.ai.behavior.CrossbowAttack
+ XXX.ai.behavior.CrossbowAttack$CrossbowState
- XXX.ai.behavior.DismountOrSkipMounting
+ XXX.ai.behavior.DoNothing
- XXX.ai.behavior.EntityTracker
+ XXX.ai.behavior.EraseMemoryIf
- XXX.ai.behavior.FollowTemptation
+ XXX.ai.behavior.GateBehavior
- XXX.ai.behavior.GateBehavior$OrderPolicy
+ XXX.ai.behavior.GateBehavior$RunningPolicy
- XXX.ai.behavior.GateBehavior$RunningPolicy$1
+ XXX.ai.behavior.GateBehavior$RunningPolicy$2
- XXX.ai.behavior.GiveGiftToHero
+ XXX.ai.behavior.GoAndGiveItemsToTarget
- XXX.ai.behavior.GoToClosestVillage
+ XXX.ai.behavior.GoToPotentialJobSite
- XXX.ai.behavior.GoToTargetLocation
+ XXX.ai.behavior.GoToWantedItem
- XXX.ai.behavior.HarvestFarmland
+ XXX.ai.behavior.InsideBrownianWalk
- XXX.ai.behavior.InteractWith
+ XXX.ai.behavior.InteractWithDoor
- XXX.ai.behavior.JumpOnBed
+ XXX.ai.behavior.LocateHidingPlace
- XXX.ai.behavior.LongJumpMidJump
+ XXX.ai.behavior.LongJumpToPreferredBlock
- XXX.ai.behavior.LongJumpToRandomPos
+ XXX.ai.behavior.LongJumpToRandomPos$PossibleJump
- XXX.ai.behavior.LookAndFollowTradingPlayerSink
+ XXX.ai.behavior.LookAtTargetSink
- XXX.ai.behavior.MeleeAttack
+ XXX.ai.behavior.Mount
- XXX.ai.behavior.MoveToSkySeeingSpot
+ XXX.ai.behavior.MoveToTargetSink
- XXX.ai.behavior.OneShot
- XXX.ai.behavior.package-info
+ XXX.ai.behavior.PlayTagWithOtherKids
- XXX.ai.behavior.PoiCompetitorScan
+ XXX.ai.behavior.PositionTracker
- XXX.ai.behavior.PrepareRamNearestTarget
+ XXX.ai.behavior.PrepareRamNearestTarget$RamCandidate
- XXX.ai.behavior.RamTarget
+ XXX.ai.behavior.RandomLookAround
- XXX.ai.behavior.RandomStroll
+ XXX.ai.behavior.ReactToBell
- XXX.ai.behavior.ResetProfession
+ XXX.ai.behavior.ResetRaidStatus
- XXX.ai.behavior.RingBell
+ XXX.ai.behavior.RunOne
- XXX.ai.behavior.SetClosestHomeAsWalkTarget
+ XXX.ai.behavior.SetEntityLookTarget
- XXX.ai.behavior.SetEntityLookTargetSometimes
+ XXX.ai.behavior.SetEntityLookTargetSometimes$Ticker
- XXX.ai.behavior.SetHiddenState
+ XXX.ai.behavior.SetLookAndInteract
- XXX.ai.behavior.SetRaidStatus
+ XXX.ai.behavior.SetWalkTargetAwayFrom
- XXX.ai.behavior.SetWalkTargetFromAttackTargetIfTargetOutOfReach
+ XXX.ai.behavior.SetWalkTargetFromBlockMemory
- XXX.ai.behavior.SetWalkTargetFromLookTarget
+ XXX.ai.behavior.ShowTradesToPlayer
- XXX.ai.behavior.ShufflingList
+ XXX.ai.behavior.ShufflingList$WeightedEntry
- XXX.ai.behavior.ShufflingList$WeightedEntry$1
+ XXX.ai.behavior.SleepInBed
- XXX.ai.behavior.SocializeAtBell
+ XXX.ai.behavior.StartAttacking
- XXX.ai.behavior.StartCelebratingIfTargetDead
+ XXX.ai.behavior.StayCloseToTarget
- XXX.ai.behavior.StopAttackingIfTargetInvalid
+ XXX.ai.behavior.StopBeingAngryIfTargetDead
- XXX.ai.behavior.StrollAroundPoi
+ XXX.ai.behavior.StrollToPoi
- XXX.ai.behavior.StrollToPoiList
+ XXX.ai.behavior.Swim
- XXX.ai.behavior.TradeWithVillager
+ XXX.ai.behavior.TriggerGate
- XXX.ai.behavior.TryFindLand
+ XXX.ai.behavior.TryFindLandNearWater
- XXX.ai.behavior.TryFindWater
+ XXX.ai.behavior.TryLaySpawnOnWaterNearLand
- XXX.ai.behavior.UpdateActivityFromSchedule
+ XXX.ai.behavior.UseBonemeal
- XXX.ai.behavior.ValidateNearbyPoi
+ XXX.ai.behavior.VillageBoundRandomStroll
- XXX.ai.behavior.VillagerCalmDown
+ XXX.ai.behavior.VillagerGoalPackages
- XXX.ai.behavior.VillagerMakeLove
+ XXX.ai.behavior.VillagerPanicTrigger
- XXX.ai.behavior.WakeUp
+ XXX.ai.behavior.WorkAtComposter
- XXX.ai.behavior.WorkAtPoi
+ XXX.ai.behavior.YieldJobSite
+ XXX.ai.control.BodyRotationControl
- XXX.ai.control.Control
+ XXX.ai.control.FlyingMoveControl
- XXX.ai.control.JumpControl
+ XXX.ai.control.LookControl
- XXX.ai.control.MoveControl
+ XXX.ai.control.MoveControl$Operation
- XXX.ai.control.package-info
- XXX.ai.control.SmoothSwimmingLookControl
+ XXX.ai.control.SmoothSwimmingMoveControl
+ XXX.ai.goal.AvoidEntityGoal
- XXX.ai.goal.BegGoal
+ XXX.ai.goal.BoatGoals
- XXX.ai.goal.BreakDoorGoal
+ XXX.ai.goal.BreathAirGoal
- XXX.ai.goal.BreedGoal
+ XXX.ai.goal.CatLieOnBedGoal
- XXX.ai.goal.CatSitOnBlockGoal
+ XXX.ai.goal.ClimbOnTopOfPowderSnowGoal
- XXX.ai.goal.DolphinJumpGoal
+ XXX.ai.goal.DoorInteractGoal
- XXX.ai.goal.EatBlockGoal
+ XXX.ai.goal.FleeSunGoal
- XXX.ai.goal.FloatGoal
+ XXX.ai.goal.FollowBoatGoal
- XXX.ai.goal.FollowFlockLeaderGoal
+ XXX.ai.goal.FollowMobGoal
- XXX.ai.goal.FollowOwnerGoal
+ XXX.ai.goal.FollowParentGoal
- XXX.ai.goal.Goal
+ XXX.ai.goal.Goal$Flag
- XXX.ai.goal.GoalSelector
+ XXX.ai.goal.GoalSelector$1
- XXX.ai.goal.GoalSelector$2
+ XXX.ai.goal.GolemRandomStrollInVillageGoal
- XXX.ai.goal.InteractGoal
+ XXX.ai.goal.JumpGoal
- XXX.ai.goal.LandOnOwnersShoulderGoal
+ XXX.ai.goal.LeapAtTargetGoal
- XXX.ai.goal.LlamaFollowCaravanGoal
+ XXX.ai.goal.LookAtPlayerGoal
- XXX.ai.goal.LookAtTradingPlayerGoal
+ XXX.ai.goal.MeleeAttackGoal
- XXX.ai.goal.MoveBackToVillageGoal
+ XXX.ai.goal.MoveThroughVillageGoal
- XXX.ai.goal.MoveToBlockGoal
+ XXX.ai.goal.MoveTowardsRestrictionGoal
- XXX.ai.goal.MoveTowardsTargetGoal
+ XXX.ai.goal.OcelotAttackGoal
- XXX.ai.goal.OfferFlowerGoal
+ XXX.ai.goal.OpenDoorGoal
- XXX.ai.goal.package-info
- XXX.ai.goal.PanicGoal
+ XXX.ai.goal.PathfindToRaidGoal
- XXX.ai.goal.RandomLookAroundGoal
+ XXX.ai.goal.RandomStandGoal
- XXX.ai.goal.RandomStrollGoal
+ XXX.ai.goal.RandomSwimmingGoal
- XXX.ai.goal.RangedAttackGoal
+ XXX.ai.goal.RangedBowAttackGoal
- XXX.ai.goal.RangedCrossbowAttackGoal
+ XXX.ai.goal.RangedCrossbowAttackGoal$CrossbowState
- XXX.ai.goal.RemoveBlockGoal
+ XXX.ai.goal.RestrictSunGoal
- XXX.ai.goal.RunAroundLikeCrazyGoal
+ XXX.ai.goal.SitWhenOrderedToGoal
- XXX.ai.goal.StrollThroughVillageGoal
+ XXX.ai.goal.SwellGoal
- XXX.ai.goal.TemptGoal
+ XXX.ai.goal.TradeWithPlayerGoal
- XXX.ai.goal.TryFindWaterGoal
+ XXX.ai.goal.UseItemGoal
- XXX.ai.goal.WaterAvoidingRandomFlyingGoal
+ XXX.ai.goal.WaterAvoidingRandomStrollGoal
- XXX.ai.goal.WrappedGoal
+ XXX.ai.goal.ZombieAttackGoal
- XXX.ai.gossip.GossipContainer
+ XXX.ai.gossip.GossipContainer$EntityGossips
- XXX.ai.gossip.GossipContainer$GossipEntry
+ XXX.ai.gossip.GossipType
- XXX.ai.gossip.package-info
+ XXX.ai.memory.ExpirableValue
- XXX.ai.memory.MemoryModuleType
+ XXX.ai.memory.MemoryStatus
- XXX.ai.memory.NearestVisibleLivingEntities
- XXX.ai.memory.package-info
+ XXX.ai.memory.WalkTarget
+ XXX.ai.navigation.AmphibiousPathNavigation
- XXX.ai.navigation.FlyingPathNavigation
+ XXX.ai.navigation.GroundPathNavigation
+ XXX.ai.navigation.package-info
- XXX.ai.navigation.PathNavigation
+ XXX.ai.navigation.WallClimberNavigation
- XXX.ai.navigation.WaterBoundPathNavigation
+ XXX.ai.sensing.AdultSensor
- XXX.ai.sensing.AxolotlAttackablesSensor
+ XXX.ai.sensing.DummySensor
- XXX.ai.sensing.FrogAttackablesSensor
+ XXX.ai.sensing.GolemSensor
- XXX.ai.sensing.HoglinSpecificSensor
+ XXX.ai.sensing.HurtBySensor
- XXX.ai.sensing.IsInWaterSensor
+ XXX.ai.sensing.NearestBedSensor
- XXX.ai.sensing.NearestItemSensor
+ XXX.ai.sensing.NearestLivingEntitySensor
- XXX.ai.sensing.NearestVisibleLivingEntitySensor
- XXX.ai.sensing.package-info
+ XXX.ai.sensing.PiglinBruteSpecificSensor
- XXX.ai.sensing.PiglinSpecificSensor
+ XXX.ai.sensing.PlayerSensor
- XXX.ai.sensing.SecondaryPoiSensor
+ XXX.ai.sensing.Sensing
- XXX.ai.sensing.Sensor
+ XXX.ai.sensing.SensorType
- XXX.ai.sensing.TemptingSensor
+ XXX.ai.sensing.VillagerBabiesSensor
- XXX.ai.sensing.VillagerHostilesSensor
+ XXX.ai.sensing.WardenEntitySensor
- XXX.ai.targeting.package-info
+ XXX.ai.targeting.TargetingConditions
+ XXX.ai.util.AirAndWaterRandomPos
- XXX.ai.util.AirRandomPos
+ XXX.ai.util.DefaultRandomPos
- XXX.ai.util.GoalUtils
+ XXX.ai.util.HoverRandomPos
- XXX.ai.util.LandRandomPos
- XXX.ai.util.package-info
+ XXX.ai.util.RandomPos
+ XXX.ai.village.package-info
+ XXX.ai.village.ReputationEventType
- XXX.ai.village.ReputationEventType$1
+ XXX.ai.village.VillageSiege
- XXX.ai.village.VillageSiege$State
- XXX.animal.sniffer.SnifferAi$3
- XXX.behavior.declarative.BehaviorBuilder
+ XXX.behavior.declarative.BehaviorBuilder$1
- XXX.behavior.declarative.BehaviorBuilder$Constant
+ XXX.behavior.declarative.BehaviorBuilder$Constant$1
- XXX.behavior.declarative.BehaviorBuilder$Instance
+ XXX.behavior.declarative.BehaviorBuilder$Instance$1
- XXX.behavior.declarative.BehaviorBuilder$Instance$2
+ XXX.behavior.declarative.BehaviorBuilder$Instance$3
- XXX.behavior.declarative.BehaviorBuilder$Instance$4
+ XXX.behavior.declarative.BehaviorBuilder$Instance$5
- XXX.behavior.declarative.BehaviorBuilder$Instance$Mu
+ XXX.behavior.declarative.BehaviorBuilder$Mu
- XXX.behavior.declarative.BehaviorBuilder$PureMemory
+ XXX.behavior.declarative.BehaviorBuilder$PureMemory$1
- XXX.behavior.declarative.BehaviorBuilder$TriggerWithResult
+ XXX.behavior.declarative.BehaviorBuilder$TriggerWrapper
- XXX.behavior.declarative.BehaviorBuilder$TriggerWrapper$1
+ XXX.behavior.declarative.MemoryAccessor
- XXX.behavior.declarative.MemoryCondition
+ XXX.behavior.declarative.MemoryCondition$Absent
- XXX.behavior.declarative.MemoryCondition$Present
+ XXX.behavior.declarative.MemoryCondition$Registered
+ XXX.behavior.declarative.package-info
- XXX.behavior.declarative.Trigger
+ XXX.behavior.warden.Digging
- XXX.behavior.warden.Emerging
+ XXX.behavior.warden.ForceUnmount
- XXX.behavior.warden.package-info
- XXX.behavior.warden.Roar
+ XXX.behavior.warden.SetRoarTarget
- XXX.behavior.warden.SetWardenLookTarget
+ XXX.behavior.warden.Sniffing
- XXX.behavior.warden.SonicBoom
+ XXX.behavior.warden.TryToSniff
- XXX.block.entity.AbstractFurnaceBlockEntity
+ XXX.block.entity.AbstractFurnaceBlockEntity$1
- XXX.block.entity.BannerBlockEntity
+ XXX.block.entity.BannerPattern
- XXX.block.entity.BannerPattern$Builder
+ XXX.block.entity.BannerPatterns
- XXX.block.entity.BarrelBlockEntity
+ XXX.block.entity.BarrelBlockEntity$1
- XXX.block.entity.BaseContainerBlockEntity
+ XXX.block.entity.BeaconBlockEntity
- XXX.block.entity.BeaconBlockEntity$1
+ XXX.block.entity.BeaconBlockEntity$BeaconBeamSection
- XXX.block.entity.BedBlockEntity
+ XXX.block.entity.BeehiveBlockEntity
- XXX.block.entity.BeehiveBlockEntity$BeeData
+ XXX.block.entity.BeehiveBlockEntity$BeeReleaseStatus
- XXX.block.entity.BellBlockEntity
+ XXX.block.entity.BellBlockEntity$ResonationEndAction
- XXX.block.entity.BlastFurnaceBlockEntity
+ XXX.block.entity.BlockEntity
- XXX.block.entity.BlockEntityTicker
+ XXX.block.entity.BlockEntityType
- XXX.block.entity.BlockEntityType$BlockEntitySupplier
+ XXX.block.entity.BlockEntityType$Builder
- XXX.block.entity.BrewingStandBlockEntity
+ XXX.block.entity.BrewingStandBlockEntity$1
- XXX.block.entity.BrushableBlockEntity
+ XXX.block.entity.CalibratedSculkSensorBlockEntity
- XXX.block.entity.CalibratedSculkSensorBlockEntity$VibrationConfig
+ XXX.block.entity.CampfireBlockEntity
- XXX.block.entity.ChestBlockEntity
+ XXX.block.entity.ChestBlockEntity$1
- XXX.block.entity.ChestLidController
+ XXX.block.entity.ChiseledBookShelfBlockEntity
- XXX.block.entity.CommandBlockEntity
+ XXX.block.entity.CommandBlockEntity$1
- XXX.block.entity.CommandBlockEntity$Mode
+ XXX.block.entity.ComparatorBlockEntity
- XXX.block.entity.ConduitBlockEntity
+ XXX.block.entity.ContainerOpenersCounter
- XXX.block.entity.DaylightDetectorBlockEntity
+ XXX.block.entity.DecoratedPotBlockEntity
- XXX.block.entity.DecoratedPotPatterns
+ XXX.block.entity.DispenserBlockEntity
- XXX.block.entity.DropperBlockEntity
+ XXX.block.entity.EnchantmentTableBlockEntity
- XXX.block.entity.EnderChestBlockEntity
+ XXX.block.entity.EnderChestBlockEntity$1
- XXX.block.entity.FurnaceBlockEntity
+ XXX.block.entity.HangingSignBlockEntity
- XXX.block.entity.Hopper
+ XXX.block.entity.HopperBlockEntity
- XXX.block.entity.JigsawBlockEntity
+ XXX.block.entity.JigsawBlockEntity$JointType
- XXX.block.entity.JukeboxBlockEntity
+ XXX.block.entity.LecternBlockEntity
- XXX.block.entity.LecternBlockEntity$1
+ XXX.block.entity.LecternBlockEntity$2
- XXX.block.entity.LidBlockEntity
+ XXX.block.entity.package-info
+ XXX.block.entity.RandomizableContainerBlockEntity
- XXX.block.entity.SculkCatalystBlockEntity
+ XXX.block.entity.SculkSensorBlockEntity
- XXX.block.entity.SculkSensorBlockEntity$VibrationConfig
+ XXX.block.entity.SculkShriekerBlockEntity
- XXX.block.entity.ShulkerBoxBlockEntity
+ XXX.block.entity.ShulkerBoxBlockEntity$1
- XXX.block.entity.ShulkerBoxBlockEntity$AnimationStatus
+ XXX.block.entity.SignBlockEntity
- XXX.block.entity.SignText
+ XXX.block.entity.SkullBlockEntity
- XXX.block.entity.SmokerBlockEntity
+ XXX.block.entity.SpawnerBlockEntity
- XXX.block.entity.SpawnerBlockEntity$1
+ XXX.block.entity.StructureBlockEntity
- XXX.block.entity.StructureBlockEntity$UpdateType
+ XXX.block.entity.TheEndGatewayBlockEntity
- XXX.block.entity.TheEndPortalBlockEntity
+ XXX.block.entity.TickingBlockEntity
- XXX.block.entity.TrappedChestBlockEntity
- XXX.block.grower.AbstractMegaTreeGrower
+ XXX.block.grower.AbstractTreeGrower
- XXX.block.grower.AcaciaTreeGrower
+ XXX.block.grower.AzaleaTreeGrower
- XXX.block.grower.BirchTreeGrower
+ XXX.block.grower.CherryTreeGrower
- XXX.block.grower.DarkOakTreeGrower
+ XXX.block.grower.JungleTreeGrower
- XXX.block.grower.MangroveTreeGrower
+ XXX.block.grower.OakTreeGrower
+ XXX.block.grower.package-info
- XXX.block.grower.SpruceTreeGrower
+ XXX.block.piston.MovingPistonBlock
+ XXX.block.piston.package-info
- XXX.block.piston.PistonBaseBlock
+ XXX.block.piston.PistonBaseBlock$1
- XXX.block.piston.PistonHeadBlock
+ XXX.block.piston.PistonHeadBlock$1
- XXX.block.piston.PistonMath
+ XXX.block.piston.PistonMath$1
- XXX.block.piston.PistonMovingBlockEntity
+ XXX.block.piston.PistonMovingBlockEntity$1
- XXX.block.piston.PistonStructureResolver
- XXX.block.state.BlockBehaviour
+ XXX.block.state.BlockBehaviour$1
- XXX.block.state.BlockBehaviour$BlockStateBase
+ XXX.block.state.BlockBehaviour$BlockStateBase$Cache
- XXX.block.state.BlockBehaviour$OffsetFunction
+ XXX.block.state.BlockBehaviour$OffsetType
- XXX.block.state.BlockBehaviour$Properties
+ XXX.block.state.BlockBehaviour$StateArgumentPredicate
- XXX.block.state.BlockBehaviour$StatePredicate
+ XXX.block.state.BlockState
+ XXX.block.state.package-info
- XXX.block.state.StateDefinition
+ XXX.block.state.StateDefinition$Builder
- XXX.block.state.StateDefinition$Factory
+ XXX.block.state.StateHolder
- XXX.block.state.StateHolder$1
+ XXX.chunk.storage.ChunkScanAccess
- XXX.chunk.storage.ChunkSerializer
+ XXX.chunk.storage.ChunkStorage
- XXX.chunk.storage.EntityStorage
+ XXX.chunk.storage.IOWorker
- XXX.chunk.storage.IOWorker$PendingStore
+ XXX.chunk.storage.IOWorker$Priority
- XXX.chunk.storage.package-info
- XXX.chunk.storage.RegionBitmap
+ XXX.chunk.storage.RegionFile
- XXX.chunk.storage.RegionFile$ChunkBuffer
+ XXX.chunk.storage.RegionFile$CommitOp
- XXX.chunk.storage.RegionFileStorage
+ XXX.chunk.storage.RegionFileVersion
- XXX.chunk.storage.RegionFileVersion$StreamWrapper
+ XXX.chunk.storage.SectionStorage
- XXX.data.loot.LootTableProvider$1
+ XXX.data.loot.LootTableProvider$SubProviderEntry
- XXX.data.loot.LootTableSubProvider
+ XXX.data.loot.package-info
- XXX.data.metadata.package-info
+ XXX.data.metadata.PackMetadataGenerator
+ XXX.data.models.BlockModelGenerators
- XXX.data.models.BlockModelGenerators$1
+ XXX.data.models.BlockModelGenerators$BlockEntityModelGenerator
- XXX.data.models.BlockModelGenerators$BlockFamilyProvider
+ XXX.data.models.BlockModelGenerators$BlockStateGeneratorSupplier
- XXX.data.models.BlockModelGenerators$BookSlotModelCacheKey
+ XXX.data.models.BlockModelGenerators$TintState
- XXX.data.models.BlockModelGenerators$WoodProvider
+ XXX.data.models.ItemModelGenerators
- XXX.data.models.ItemModelGenerators$TrimModelData
+ XXX.data.models.ModelProvider
+ XXX.data.models.package-info
+ XXX.data.recipes.CraftingRecipeBuilder
- XXX.data.recipes.CraftingRecipeBuilder$1
+ XXX.data.recipes.CraftingRecipeBuilder$CraftingResult
- XXX.data.recipes.FinishedRecipe
- XXX.data.recipes.package-info
+ XXX.data.recipes.RecipeBuilder
- XXX.data.recipes.RecipeCategory
+ XXX.data.recipes.RecipeProvider
- XXX.data.recipes.ShapedRecipeBuilder
+ XXX.data.recipes.ShapedRecipeBuilder$Result
- XXX.data.recipes.ShapelessRecipeBuilder
+ XXX.data.recipes.ShapelessRecipeBuilder$Result
- XXX.data.recipes.SimpleCookingRecipeBuilder
+ XXX.data.recipes.SimpleCookingRecipeBuilder$Result
- XXX.data.recipes.SingleItemRecipeBuilder
+ XXX.data.recipes.SingleItemRecipeBuilder$Result
- XXX.data.recipes.SmithingTransformRecipeBuilder
+ XXX.data.recipes.SmithingTransformRecipeBuilder$Result
- XXX.data.recipes.SmithingTrimRecipeBuilder
+ XXX.data.recipes.SmithingTrimRecipeBuilder$Result
- XXX.data.recipes.SpecialRecipeBuilder
+ XXX.data.recipes.SpecialRecipeBuilder$1
- XXX.data.registries.package-info
- XXX.data.registries.RegistriesDatapackGenerator
+ XXX.data.registries.VanillaRegistries
+ XXX.data.structures.NbtToSnbt
+ XXX.data.structures.package-info
- XXX.data.structures.SnbtToNbt
+ XXX.data.structures.SnbtToNbt$Filter
- XXX.data.structures.SnbtToNbt$StructureConversionException
+ XXX.data.structures.SnbtToNbt$TaskResult
- XXX.data.structures.StructureUpdater
- XXX.data.tags.BannerPatternTagsProvider
+ XXX.data.tags.BiomeTagsProvider
- XXX.data.tags.CatVariantTagsProvider
+ XXX.data.tags.DamageTypeTagsProvider
- XXX.data.tags.EntityTypeTagsProvider
+ XXX.data.tags.FlatLevelGeneratorPresetTagsProvider
- XXX.data.tags.FluidTagsProvider
+ XXX.data.tags.GameEventTagsProvider
- XXX.data.tags.InstrumentTagsProvider
+ XXX.data.tags.IntrinsicHolderTagsProvider
- XXX.data.tags.IntrinsicHolderTagsProvider$IntrinsicTagAppender
+ XXX.data.tags.ItemTagsProvider
- XXX.data.tags.package-info
- XXX.data.tags.PaintingVariantTagsProvider
+ XXX.data.tags.PoiTypeTagsProvider
- XXX.data.tags.StructureTagsProvider
+ XXX.data.tags.TagsProvider
- XXX.data.tags.TagsProvider$1CombinedData
+ XXX.data.tags.TagsProvider$TagAppender
- XXX.data.tags.TagsProvider$TagLookup
+ XXX.data.tags.VanillaBlockTagsProvider
- XXX.data.tags.VanillaItemTagsProvider
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
- XXX.data.worldgen.BootstapContext
+ XXX.data.worldgen.Carvers
- XXX.data.worldgen.DesertVillagePools
+ XXX.data.worldgen.DimensionTypes
- XXX.data.worldgen.NoiseData
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
+ XXX.data.worldgen.VillagePools
+ XXX.datafix.fixes.AbstractArrowPickupFix
- XXX.datafix.fixes.AbstractPoiSectionFix
+ XXX.datafix.fixes.AbstractUUIDFix
- XXX.datafix.fixes.AddFlagIfNotPresentFix
+ XXX.datafix.fixes.AddNewChoices
- XXX.datafix.fixes.AdvancementsFix
+ XXX.datafix.fixes.AdvancementsRenameFix
- XXX.datafix.fixes.AttributesRename
+ XXX.datafix.fixes.BedItemColorFix
- XXX.datafix.fixes.BiomeFix
+ XXX.datafix.fixes.BitStorageAlignFix
- XXX.datafix.fixes.BlendingDataFix
+ XXX.datafix.fixes.BlendingDataRemoveFromNetherEndFix
- XXX.datafix.fixes.BlockEntityBannerColorFix
+ XXX.datafix.fixes.BlockEntityBlockStateFix
- XXX.datafix.fixes.BlockEntityCustomNameToComponentFix
+ XXX.datafix.fixes.BlockEntityIdFix
- XXX.datafix.fixes.BlockEntityJukeboxFix
+ XXX.datafix.fixes.BlockEntityKeepPacked
- XXX.datafix.fixes.BlockEntityRenameFix
+ XXX.datafix.fixes.BlockEntityShulkerBoxColorFix
- XXX.datafix.fixes.BlockEntitySignDoubleSidedEditableTextFix
+ XXX.datafix.fixes.BlockEntitySignTextStrictJsonFix
- XXX.datafix.fixes.BlockEntitySignTextStrictJsonFix$1
+ XXX.datafix.fixes.BlockEntityUUIDFix
- XXX.datafix.fixes.BlockNameFlatteningFix
+ XXX.datafix.fixes.BlockRenameFix
- XXX.datafix.fixes.BlockRenameFix$1
+ XXX.datafix.fixes.BlockRenameFixWithJigsaw
- XXX.datafix.fixes.BlockRenameFixWithJigsaw$1
+ XXX.datafix.fixes.BlockStateData
- XXX.datafix.fixes.BlockStateStructureTemplateFix
+ XXX.datafix.fixes.CatTypeFix
- XXX.datafix.fixes.CauldronRenameFix
+ XXX.datafix.fixes.CavesAndCliffsRenames
- XXX.datafix.fixes.ChunkBedBlockEntityInjecterFix
+ XXX.datafix.fixes.ChunkBiomeFix
- XXX.datafix.fixes.ChunkDeleteIgnoredLightDataFix
+ XXX.datafix.fixes.ChunkHeightAndBiomeFix
- XXX.datafix.fixes.ChunkLightRemoveFix
+ XXX.datafix.fixes.ChunkPalettedStorageFix
- XXX.datafix.fixes.ChunkPalettedStorageFix$1
+ XXX.datafix.fixes.ChunkPalettedStorageFix$DataLayer
- XXX.datafix.fixes.ChunkPalettedStorageFix$Direction
+ XXX.datafix.fixes.ChunkPalettedStorageFix$Direction$Axis
- XXX.datafix.fixes.ChunkPalettedStorageFix$Direction$AxisDirection
+ XXX.datafix.fixes.ChunkPalettedStorageFix$Section
- XXX.datafix.fixes.ChunkPalettedStorageFix$UpgradeChunk
+ XXX.datafix.fixes.ChunkProtoTickListFix
- XXX.datafix.fixes.ChunkProtoTickListFix$PoorMansPalettedContainer
+ XXX.datafix.fixes.ChunkRenamesFix
- XXX.datafix.fixes.ChunkStatusFix
+ XXX.datafix.fixes.ChunkStatusFix2
- XXX.datafix.fixes.ChunkStructuresTemplateRenameFix
+ XXX.datafix.fixes.ChunkToProtochunkFix
- XXX.datafix.fixes.ColorlessShulkerEntityFix
+ XXX.datafix.fixes.CriteriaRenameFix
- XXX.datafix.fixes.DyeItemRenameFix
+ XXX.datafix.fixes.EffectDurationFix
- XXX.datafix.fixes.EntityArmorStandSilentFix
+ XXX.datafix.fixes.EntityBlockStateFix
- XXX.datafix.fixes.EntityBrushableBlockFieldsRenameFix
+ XXX.datafix.fixes.EntityCatSplitFix
- XXX.datafix.fixes.EntityCodSalmonFix
+ XXX.datafix.fixes.EntityCustomNameToComponentFix
- XXX.datafix.fixes.EntityElderGuardianSplitFix
+ XXX.datafix.fixes.EntityEquipmentToArmorAndHandFix
- XXX.datafix.fixes.EntityGoatMissingStateFix
+ XXX.datafix.fixes.EntityHealthFix
- XXX.datafix.fixes.EntityHorseSaddleFix
+ XXX.datafix.fixes.EntityHorseSplitFix
- XXX.datafix.fixes.EntityIdFix
+ XXX.datafix.fixes.EntityItemFrameDirectionFix
- XXX.datafix.fixes.EntityMinecartIdentifiersFix
+ XXX.datafix.fixes.EntityPaintingFieldsRenameFix
- XXX.datafix.fixes.EntityPaintingItemFrameDirectionFix
+ XXX.datafix.fixes.EntityPaintingMotiveFix
- XXX.datafix.fixes.EntityProjectileOwnerFix
+ XXX.datafix.fixes.EntityPufferfishRenameFix
- XXX.datafix.fixes.EntityRavagerRenameFix
+ XXX.datafix.fixes.EntityRedundantChanceTagsFix
- XXX.datafix.fixes.EntityRenameFix
+ XXX.datafix.fixes.EntityRidingToPassengersFix
- XXX.datafix.fixes.EntityShulkerColorFix
+ XXX.datafix.fixes.EntityShulkerRotationFix
- XXX.datafix.fixes.EntitySkeletonSplitFix
+ XXX.datafix.fixes.EntityStringUuidFix
- XXX.datafix.fixes.EntityTheRenameningFix
+ XXX.datafix.fixes.EntityTippedArrowFix
- XXX.datafix.fixes.EntityUUIDFix
+ XXX.datafix.fixes.EntityVariantFix
- XXX.datafix.fixes.EntityWolfColorFix
+ XXX.datafix.fixes.EntityZombieSplitFix
- XXX.datafix.fixes.EntityZombieVillagerTypeFix
+ XXX.datafix.fixes.EntityZombifiedPiglinRenameFix
- XXX.datafix.fixes.FeatureFlagRemoveFix
+ XXX.datafix.fixes.FilteredBooksFix
- XXX.datafix.fixes.FilteredSignsFix
+ XXX.datafix.fixes.ForcePoiRebuild
- XXX.datafix.fixes.FurnaceRecipeFix
+ XXX.datafix.fixes.GoatHornIdFix
- XXX.datafix.fixes.GossipUUIDFix
+ XXX.datafix.fixes.HeightmapRenamingFix
- XXX.datafix.fixes.IglooMetadataRemovalFix
+ XXX.datafix.fixes.ItemBannerColorFix
- XXX.datafix.fixes.ItemCustomNameToComponentFix
+ XXX.datafix.fixes.ItemIdFix
- XXX.datafix.fixes.ItemLoreFix
+ XXX.datafix.fixes.ItemPotionFix
- XXX.datafix.fixes.ItemRemoveBlockEntityTagFix
+ XXX.datafix.fixes.ItemRenameFix
- XXX.datafix.fixes.ItemRenameFix$1
+ XXX.datafix.fixes.ItemShulkerBoxColorFix
- XXX.datafix.fixes.ItemSpawnEggFix
+ XXX.datafix.fixes.ItemStackEnchantmentNamesFix
- XXX.datafix.fixes.ItemStackMapIdFix
+ XXX.datafix.fixes.ItemStackSpawnEggFix
- XXX.datafix.fixes.ItemStackTagFix
+ XXX.datafix.fixes.ItemStackTheFlatteningFix
- XXX.datafix.fixes.ItemStackUUIDFix
+ XXX.datafix.fixes.ItemWaterPotionFix
- XXX.datafix.fixes.ItemWrittenBookPagesStrictJsonFix
+ XXX.datafix.fixes.JigsawPropertiesFix
- XXX.datafix.fixes.JigsawRotationFix
+ XXX.datafix.fixes.LeavesFix
- XXX.datafix.fixes.LeavesFix$LeavesSection
+ XXX.datafix.fixes.LeavesFix$Section
- XXX.datafix.fixes.LevelDataGeneratorOptionsFix
+ XXX.datafix.fixes.LevelFlatGeneratorInfoFix
- XXX.datafix.fixes.LevelUUIDFix
+ XXX.datafix.fixes.MapIdFix
- XXX.datafix.fixes.MemoryExpiryDataFix
+ XXX.datafix.fixes.MissingDimensionFix
- XXX.datafix.fixes.MobSpawnerEntityIdentifiersFix
+ XXX.datafix.fixes.NamedEntityFix
- XXX.datafix.fixes.NamespacedTypeRenameFix
+ XXX.datafix.fixes.NewVillageFix
- XXX.datafix.fixes.ObjectiveDisplayNameFix
+ XXX.datafix.fixes.ObjectiveRenderTypeFix
- XXX.datafix.fixes.OminousBannerBlockEntityRenameFix
+ XXX.datafix.fixes.OminousBannerRenameFix
- XXX.datafix.fixes.OptionsAccessibilityOnboardFix
+ XXX.datafix.fixes.OptionsAddTextBackgroundFix
- XXX.datafix.fixes.OptionsAmbientOcclusionFix
+ XXX.datafix.fixes.OptionsForceVBOFix
- XXX.datafix.fixes.OptionsKeyLwjgl3Fix
+ XXX.datafix.fixes.OptionsKeyTranslationFix
- XXX.datafix.fixes.OptionsLowerCaseLanguageFix
+ XXX.datafix.fixes.OptionsProgrammerArtFix
- XXX.datafix.fixes.OptionsRenameFieldFix
+ XXX.datafix.fixes.OverreachingTickFix
- XXX.datafix.fixes.PlayerUUIDFix
+ XXX.datafix.fixes.PoiTypeRemoveFix
- XXX.datafix.fixes.PoiTypeRenameFix
+ XXX.datafix.fixes.RecipesFix
- XXX.datafix.fixes.RecipesRenameningFix
+ XXX.datafix.fixes.RedstoneWireConnectionsFix
- XXX.datafix.fixes.References
+ XXX.datafix.fixes.RemoveGolemGossipFix
- XXX.datafix.fixes.RenamedCoralFansFix
+ XXX.datafix.fixes.RenamedCoralFix
- XXX.datafix.fixes.ReorganizePoi
+ XXX.datafix.fixes.SavedDataFeaturePoolElementFix
- XXX.datafix.fixes.SavedDataUUIDFix
- XXX.datafix.schemas.package-info
+ XXX.datafix.schemas.V3444
- XXX.datafix.schemas.V501
+ XXX.datafix.schemas.V700
- XXX.datafix.schemas.V701
+ XXX.datafix.schemas.V702
- XXX.datafix.schemas.V703
+ XXX.datafix.schemas.V704
- XXX.datafix.schemas.V704$1
+ XXX.datafix.schemas.V705
- XXX.datafix.schemas.V705$1
+ XXX.datafix.schemas.V808
- XXX.datafix.schemas.V99
+ XXX.datafix.schemas.V99$1
- XXX.dimension.end.DragonRespawnAnimation
+ XXX.dimension.end.DragonRespawnAnimation$1
- XXX.dimension.end.DragonRespawnAnimation$2
+ XXX.dimension.end.DragonRespawnAnimation$3
- XXX.dimension.end.DragonRespawnAnimation$4
+ XXX.dimension.end.DragonRespawnAnimation$5
- XXX.dimension.end.EndDragonFight
+ XXX.dimension.end.package-info
- XXX.entity.ai.Brain
+ XXX.entity.ai.Brain$1
- XXX.entity.ai.Brain$MemoryValue
+ XXX.entity.ai.Brain$Provider
- XXX.entity.ai.package-info
- XXX.entity.ambient.AmbientCreature
+ XXX.entity.ambient.Bat
- XXX.entity.ambient.package-info
+ XXX.entity.animal.AbstractFish
- XXX.entity.animal.AbstractFish$FishMoveControl
+ XXX.entity.animal.AbstractFish$FishSwimGoal
- XXX.entity.animal.AbstractGolem
+ XXX.entity.animal.AbstractSchoolingFish
- XXX.entity.animal.AbstractSchoolingFish$SchoolSpawnGroupData
+ XXX.entity.animal.Animal
- XXX.entity.animal.Bee
+ XXX.entity.animal.Bee$1
- XXX.entity.animal.Bee$BaseBeeGoal
+ XXX.entity.animal.Bee$BeeAttackGoal
- XXX.entity.animal.Bee$BeeBecomeAngryTargetGoal
+ XXX.entity.animal.Bee$BeeEnterHiveGoal
- XXX.entity.animal.Bee$BeeGoToHiveGoal
+ XXX.entity.animal.Bee$BeeGoToKnownFlowerGoal
- XXX.entity.animal.Bee$BeeGrowCropGoal
+ XXX.entity.animal.Bee$BeeHurtByOtherGoal
- XXX.entity.animal.Bee$BeeLocateHiveGoal
+ XXX.entity.animal.Bee$BeeLookControl
- XXX.entity.animal.Bee$BeePollinateGoal
+ XXX.entity.animal.Bee$BeeWanderGoal
+ XXX.entity.animal.Bee$FloatDownGoal
+ XXX.entity.animal.MoonCow
- XXX.entity.item.package-info
+ XXX.entity.item.PrimedTnt
+ XXX.entity.monster.AbstractIllager
- XXX.entity.monster.AbstractIllager$IllagerArmPose
+ XXX.entity.monster.AbstractIllager$RaiderOpenDoorGoal
- XXX.entity.monster.AbstractSkeleton
+ XXX.entity.monster.AbstractSkeleton$1
- XXX.entity.monster.Blaze
+ XXX.entity.monster.Blaze$BlazeAttackGoal
- XXX.entity.monster.CaveSpider
+ XXX.entity.monster.Creeper
- XXX.entity.monster.CrossbowAttackMob
+ XXX.entity.monster.Drowned
- XXX.entity.monster.Drowned$DrownedAttackGoal
+ XXX.entity.monster.Drowned$DrownedGoToBeachGoal
- XXX.entity.monster.Drowned$DrownedGoToWaterGoal
+ XXX.entity.monster.Drowned$DrownedMoveControl
- XXX.entity.monster.Drowned$DrownedSwimUpGoal
+ XXX.entity.monster.Drowned$DrownedTridentAttackGoal
- XXX.entity.monster.ElderGuardian
+ XXX.entity.monster.EnderMan
- XXX.entity.monster.EnderMan$EndermanFreezeWhenLookedAt
+ XXX.entity.monster.EnderMan$EndermanLeaveBlockGoal
- XXX.entity.monster.EnderMan$EndermanLookForPlayerGoal
+ XXX.entity.monster.EnderMan$EndermanTakeBlockGoal
- XXX.entity.monster.Endermite
+ XXX.entity.monster.Enemy
- XXX.entity.monster.Evoker
+ XXX.entity.monster.Evoker$EvokerAttackSpellGoal
- XXX.entity.monster.Evoker$EvokerCastingSpellGoal
+ XXX.entity.monster.Evoker$EvokerSummonSpellGoal
- XXX.entity.monster.Evoker$EvokerWololoSpellGoal
+ XXX.entity.monster.Ghast
- XXX.entity.monster.Ghast$GhastLookGoal
+ XXX.entity.monster.Ghast$GhastMoveControl
- XXX.entity.monster.Ghast$GhastShootFireballGoal
+ XXX.entity.monster.Ghast$RandomFloatAroundGoal
- XXX.entity.monster.Giant
+ XXX.entity.monster.Guardian
- XXX.entity.monster.Guardian$GuardianAttackGoal
+ XXX.entity.monster.Guardian$GuardianAttackSelector
- XXX.entity.monster.Guardian$GuardianMoveControl
+ XXX.entity.monster.Husk
- XXX.entity.monster.Illusioner
+ XXX.entity.monster.Illusioner$IllusionerBlindnessSpellGoal
- XXX.entity.monster.Illusioner$IllusionerMirrorSpellGoal
+ XXX.entity.monster.MagmaCube
- XXX.entity.monster.Monster
+ XXX.entity.monster.package-info
+ XXX.entity.monster.PatrollingMonster
- XXX.entity.monster.PatrollingMonster$LongDistancePatrolGoal
+ XXX.entity.monster.Phantom
- XXX.entity.monster.Phantom$AttackPhase
+ XXX.entity.monster.Phantom$PhantomAttackPlayerTargetGoal
- XXX.entity.monster.Phantom$PhantomAttackStrategyGoal
+ XXX.entity.monster.Phantom$PhantomBodyRotationControl
- XXX.entity.monster.Phantom$PhantomCircleAroundAnchorGoal
+ XXX.entity.monster.Phantom$PhantomLookControl
- XXX.entity.monster.Phantom$PhantomMoveControl
+ XXX.entity.monster.Phantom$PhantomMoveTargetGoal
- XXX.entity.monster.Phantom$PhantomSweepAttackGoal
+ XXX.entity.monster.Pillager
- XXX.entity.monster.RangedAttackMob
+ XXX.entity.monster.Ravager
- XXX.entity.monster.Ravager$RavagerMeleeAttackGoal
+ XXX.entity.monster.RayTracing
+ XXX.entity.monster.Zombie$ZombieAttackTurtleEggGoal
- XXX.entity.monster.Zombie$ZombieGroupData
+ XXX.entity.monster.ZombieVillager
- XXX.entity.monster.ZombifiedPiglin
- XXX.entity.npc.AbstractVillager
+ XXX.entity.npc.CatSpawner
- XXX.entity.npc.ClientSideMerchant
+ XXX.entity.npc.InventoryCarrier
- XXX.entity.npc.Npc
+ XXX.entity.npc.package-info
+ XXX.entity.npc.Villager
- XXX.entity.npc.VillagerData
+ XXX.entity.npc.VillagerDataHolder
- XXX.entity.npc.VillagerProfession
+ XXX.entity.npc.VillagerTrades
- XXX.entity.npc.VillagerTrades$DyedArmorForEmeralds
+ XXX.entity.npc.VillagerTrades$EmeraldForItems
- XXX.entity.npc.VillagerTrades$EmeraldsForVillagerTypeItem
+ XXX.entity.npc.VillagerTrades$EnchantBookForEmeralds
- XXX.entity.npc.VillagerTrades$EnchantedItemForEmeralds
+ XXX.entity.npc.VillagerTrades$ItemListing
- XXX.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
+ XXX.entity.npc.VillagerTrades$ItemsForEmeralds
- XXX.entity.npc.VillagerTrades$SuspiciousStewForEmerald
+ XXX.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
- XXX.entity.npc.VillagerTrades$TreasureMapForEmeralds
+ XXX.entity.npc.VillagerType
- XXX.entity.npc.WanderingTrader
+ XXX.entity.npc.WanderingTrader$WanderToPositionGoal
- XXX.entity.npc.WanderingTraderSpawner
+ XXX.entity.player.Abilities
- XXX.entity.player.ChatVisiblity
+ XXX.entity.player.Inventory
- XXX.entity.player.package-info
- XXX.entity.player.Player
+ XXX.entity.player.Player$1
- XXX.entity.player.Player$BedSleepingProblem
+ XXX.entity.player.PlayerModelPart
- XXX.entity.player.ProfileKeyPair
+ XXX.entity.player.ProfilePublicKey
- XXX.entity.player.ProfilePublicKey$Data
+ XXX.entity.player.ProfilePublicKey$ValidationException
- XXX.entity.player.StackedContents
+ XXX.entity.player.StackedContents$RecipePicker
+ XXX.entity.projectile.AbstractArrow
- XXX.entity.projectile.AbstractArrow$1
+ XXX.entity.projectile.AbstractArrow$Pickup
- XXX.entity.projectile.AbstractHurtingProjectile
+ XXX.entity.projectile.Arrow
- XXX.entity.projectile.DragonFireball
+ XXX.entity.projectile.EvokerFangs
- XXX.entity.projectile.EyeOfEnder
+ XXX.entity.projectile.Fireball
- XXX.entity.projectile.FireworkRocketEntity
+ XXX.entity.projectile.FishingHook
- XXX.entity.projectile.FishingHook$1
+ XXX.entity.projectile.FishingHook$FishHookState
- XXX.entity.projectile.FishingHook$OpenWaterType
+ XXX.entity.projectile.ItemSupplier
- XXX.entity.projectile.LargeFireball
+ XXX.entity.projectile.LlamaSpit
- XXX.entity.projectile.package-info
- XXX.entity.projectile.Projectile
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
+ XXX.entity.projectile.ThrownPotion
- XXX.entity.projectile.ThrownTrident
+ XXX.entity.projectile.WitherSkull
+ XXX.entity.raid.package-info
+ XXX.entity.raid.Raid
- XXX.entity.raid.Raid$1
- XXX.entity.raid.Raid$RaiderType
+ XXX.entity.raid.Raid$RaidStatus
+ XXX.entity.raid.Raider
- XXX.entity.raid.Raider$HoldGroundAttackGoal
+ XXX.entity.raid.Raider$ObtainRaidLeaderBannerGoal
- XXX.entity.raid.Raider$RaiderCelebration
+ XXX.entity.raid.Raider$RaiderMoveThroughVillageGoal
- XXX.entity.raid.Raids
- XXX.entity.schedule.Activity
+ XXX.entity.schedule.Keyframe
- XXX.entity.schedule.package-info
- XXX.entity.schedule.Schedule
+ XXX.entity.schedule.ScheduleBuilder
- XXX.entity.schedule.ScheduleBuilder$ActivityTransition
+ XXX.entity.schedule.Timeline
+ XXX.entity.transform.EntityTransform
+ XXX.entity.transform.EntityTransformType$TypeModifier
+ XXX.entity.transform.package-info
+ XXX.feature.configurations.CraterFeatureConfiguration
- XXX.feature.configurations.DeltaFeatureConfiguration
+ XXX.feature.configurations.DiskConfiguration
- XXX.feature.configurations.DripstoneClusterConfiguration
+ XXX.feature.configurations.EndGatewayConfiguration
- XXX.feature.configurations.FeatureConfiguration
+ XXX.feature.configurations.GeodeConfiguration
- XXX.feature.configurations.HugeMushroomFeatureConfiguration
+ XXX.feature.configurations.LargeDripstoneConfiguration
- XXX.feature.configurations.LayerConfiguration
+ XXX.feature.configurations.MultifaceGrowthConfiguration
- XXX.feature.configurations.NetherForestVegetationConfig
+ XXX.feature.configurations.NoneFeatureConfiguration
- XXX.feature.configurations.OreConfiguration
+ XXX.feature.configurations.OreConfiguration$TargetBlockState
- XXX.feature.configurations.package-info
- XXX.feature.configurations.PointedDripstoneConfiguration
+ XXX.feature.configurations.ProbabilityFeatureConfiguration
- XXX.feature.configurations.RandomBooleanFeatureConfiguration
+ XXX.feature.configurations.RandomFeatureConfiguration
- XXX.feature.configurations.RandomPatchConfiguration
+ XXX.feature.configurations.ReplaceBlockConfiguration
- XXX.feature.configurations.ReplaceSphereConfiguration
+ XXX.feature.configurations.RootSystemConfiguration
- XXX.feature.configurations.SculkPatchConfiguration
+ XXX.feature.configurations.SimpleBlockConfiguration
- XXX.feature.configurations.SimpleRandomFeatureConfiguration
+ XXX.feature.configurations.SpikeConfiguration
- XXX.feature.configurations.SpringConfiguration
+ XXX.feature.configurations.TreeConfiguration
- XXX.feature.configurations.TreeConfiguration$TreeConfigurationBuilder
+ XXX.feature.configurations.TwistingVinesConfig
- XXX.feature.configurations.UnderwaterMagmaConfiguration
+ XXX.feature.configurations.VegetationPatchConfiguration
+ XXX.feature.featuresize.FeatureSize
- XXX.feature.featuresize.FeatureSizeType
+ XXX.feature.featuresize.package-info
+ XXX.feature.featuresize.ThreeLayersFeatureSize
- XXX.feature.featuresize.TwoLayersFeatureSize
- XXX.feature.foliageplacers.AcaciaFoliagePlacer
+ XXX.feature.foliageplacers.BlobFoliagePlacer
- XXX.feature.foliageplacers.BushFoliagePlacer
+ XXX.feature.foliageplacers.CherryFoliagePlacer
- XXX.feature.foliageplacers.DarkOakFoliagePlacer
+ XXX.feature.foliageplacers.FancyFoliagePlacer
- XXX.feature.foliageplacers.FoliagePlacer
+ XXX.feature.foliageplacers.FoliagePlacer$FoliageAttachment
- XXX.feature.foliageplacers.FoliagePlacer$FoliageSetter
+ XXX.feature.foliageplacers.FoliagePlacerType
- XXX.feature.foliageplacers.MegaJungleFoliagePlacer
+ XXX.feature.foliageplacers.MegaPineFoliagePlacer
+ XXX.feature.foliageplacers.package-info
- XXX.feature.foliageplacers.PineFoliagePlacer
+ XXX.feature.foliageplacers.RandomSpreadFoliagePlacer
- XXX.feature.foliageplacers.SpruceFoliagePlacer
+ XXX.feature.rootplacers.AboveRootPlacement
- XXX.feature.rootplacers.MangroveRootPlacement
+ XXX.feature.rootplacers.MangroveRootPlacer
- XXX.feature.rootplacers.package-info
- XXX.feature.rootplacers.RootPlacer
+ XXX.feature.rootplacers.RootPlacerType
+ XXX.feature.stateproviders.BlockStateProvider
- XXX.feature.stateproviders.BlockStateProviderType
+ XXX.feature.stateproviders.DualNoiseProvider
- XXX.feature.stateproviders.NoiseBasedStateProvider
+ XXX.feature.stateproviders.NoiseProvider
- XXX.feature.stateproviders.NoiseThresholdProvider
+ XXX.feature.stateproviders.package-info
+ XXX.feature.stateproviders.RandomizedIntStateProvider
- XXX.feature.stateproviders.RotatedBlockProvider
+ XXX.feature.stateproviders.RuleBasedBlockStateProvider
- XXX.feature.stateproviders.RuleBasedBlockStateProvider$Rule
+ XXX.feature.stateproviders.SimpleStateProvider
- XXX.feature.stateproviders.WeightedStateProvider
- XXX.feature.treedecorators.AlterGroundDecorator
+ XXX.feature.treedecorators.AttachedToLeavesDecorator
- XXX.feature.treedecorators.BeehiveDecorator
+ XXX.feature.treedecorators.CocoaDecorator
- XXX.feature.treedecorators.LeaveVineDecorator
+ XXX.feature.treedecorators.package-info
+ XXX.feature.treedecorators.TreeDecorator
- XXX.feature.treedecorators.TreeDecorator$Context
+ XXX.feature.treedecorators.TreeDecoratorType
- XXX.feature.treedecorators.TrunkVineDecorator
- XXX.feature.trunkplacers.BendingTrunkPlacer
+ XXX.feature.trunkplacers.CherryTrunkPlacer
- XXX.feature.trunkplacers.DarkOakTrunkPlacer
+ XXX.feature.trunkplacers.FancyTrunkPlacer
- XXX.feature.trunkplacers.FancyTrunkPlacer$FoliageCoords
+ XXX.feature.trunkplacers.ForkingTrunkPlacer
- XXX.feature.trunkplacers.GiantTrunkPlacer
+ XXX.feature.trunkplacers.MegaJungleTrunkPlacer
- XXX.feature.trunkplacers.package-info
- XXX.feature.trunkplacers.StraightTrunkPlacer
+ XXX.feature.trunkplacers.TrunkPlacer
- XXX.feature.trunkplacers.TrunkPlacerType
+ XXX.feature.trunkplacers.UpwardsBranchingTrunkPlacer
+ XXX.gameevent.vibrations.package-info
+ XXX.gameevent.vibrations.VibrationInfo
- XXX.gameevent.vibrations.VibrationListener
+ XXX.gameevent.vibrations.VibrationListener$Config
- XXX.gameevent.vibrations.VibrationSelector
+ XXX.goal.target.DefendVillageTargetGoal
- XXX.goal.target.HurtByTargetGoal
+ XXX.goal.target.NearestAttackableTargetGoal
- XXX.goal.target.NearestAttackableWitchTargetGoal
+ XXX.goal.target.NearestHealableRaiderTargetGoal
- XXX.goal.target.NonTameRandomTargetGoal
+ XXX.goal.target.OwnerHurtByTargetGoal
- XXX.goal.target.OwnerHurtTargetGoal
+ XXX.goal.target.package-info
+ XXX.goal.target.ResetUniversalAngerTargetGoal
- XXX.goal.target.TargetGoal
+ XXX.inventory.tooltip.BundleTooltip
+ XXX.inventory.tooltip.package-info
- XXX.inventory.tooltip.TooltipComponent
- XXX.item.context.package-info
+ XXX.item.context.UseOnContext
+ XXX.item.crafting.AbstractCookingRecipe
- XXX.item.crafting.ArmorDyeRecipe
+ XXX.item.crafting.BannerDuplicateRecipe
- XXX.item.crafting.BlastingRecipe
+ XXX.item.crafting.BookCloningRecipe
- XXX.item.crafting.CampfireCookingRecipe
+ XXX.item.crafting.CookingBookCategory
- XXX.item.crafting.CraftingBookCategory
+ XXX.item.crafting.CraftingRecipe
- XXX.item.crafting.CustomRecipe
+ XXX.item.crafting.DecoratedPotRecipe
- XXX.item.crafting.package-info
+ XXX.item.crafting.Recipe
- XXX.item.crafting.RecipeManager
+ XXX.item.crafting.RecipeManager$1
- XXX.item.crafting.RecipeManager$CachedCheck
+ XXX.item.crafting.RecipeSerializer
- XXX.item.crafting.RecipeType
+ XXX.item.crafting.RecipeType$1
- XXX.item.crafting.RepairItemRecipe
+ XXX.item.crafting.ShapedRecipe
- XXX.item.crafting.ShapedRecipe$Serializer
+ XXX.item.crafting.ShapelessRecipe
- XXX.item.crafting.ShapelessRecipe$Serializer
+ XXX.item.crafting.ShieldDecorationRecipe
- XXX.item.crafting.ShulkerBoxColoring
+ XXX.item.crafting.SimpleCookingSerializer
- XXX.item.crafting.SimpleCookingSerializer$CookieBaker
+ XXX.item.crafting.SimpleCraftingRecipeSerializer
- XXX.item.crafting.SimpleCraftingRecipeSerializer$Factory
+ XXX.item.crafting.SingleItemRecipe
- XXX.item.crafting.SingleItemRecipe$Serializer
+ XXX.item.crafting.SingleItemRecipe$Serializer$SingleItemMaker
- XXX.item.crafting.SmeltingRecipe
+ XXX.item.crafting.SmithingRecipe
- XXX.item.crafting.SmithingTransformRecipe
+ XXX.item.crafting.SmithingTransformRecipe$Serializer
- XXX.item.crafting.SmithingTrimRecipe
+ XXX.item.crafting.SmithingTrimRecipe$Serializer
- XXX.item.crafting.SmokingRecipe
+ XXX.item.crafting.StonecutterRecipe
- XXX.item.crafting.SuspiciousStewRecipe
+ XXX.item.crafting.TippedArrowRecipe
+ XXX.item.enchantment.ArrowDamageEnchantment
- XXX.item.enchantment.ArrowFireEnchantment
+ XXX.item.enchantment.ArrowInfiniteEnchantment
- XXX.item.enchantment.ArrowKnockbackEnchantment
+ XXX.item.enchantment.ArrowPiercingEnchantment
- XXX.item.enchantment.BindingCurseEnchantment
+ XXX.item.enchantment.DamageEnchantment
- XXX.item.enchantment.DigDurabilityEnchantment
+ XXX.item.enchantment.DiggingEnchantment
- XXX.item.enchantment.Enchantment
+ XXX.item.enchantment.Enchantment$Rarity
- XXX.item.enchantment.EnchantmentCategory
+ XXX.item.enchantment.EnchantmentCategory$1
- XXX.item.enchantment.EnchantmentCategory$10
+ XXX.item.enchantment.EnchantmentCategory$11
- XXX.item.enchantment.EnchantmentCategory$12
+ XXX.item.enchantment.EnchantmentCategory$13
- XXX.item.enchantment.EnchantmentCategory$14
+ XXX.item.enchantment.EnchantmentCategory$2
- XXX.item.enchantment.EnchantmentCategory$3
+ XXX.item.enchantment.EnchantmentCategory$4
- XXX.item.enchantment.EnchantmentCategory$5
+ XXX.item.enchantment.EnchantmentCategory$6
- XXX.item.enchantment.EnchantmentCategory$7
+ XXX.item.enchantment.EnchantmentCategory$8
- XXX.item.enchantment.EnchantmentCategory$9
+ XXX.item.enchantment.EnchantmentHelper
- XXX.item.enchantment.EnchantmentHelper$EnchantmentVisitor
+ XXX.item.enchantment.EnchantmentInstance
- XXX.item.enchantment.Enchantments
+ XXX.item.enchantment.FireAspectEnchantment
- XXX.item.enchantment.FishingSpeedEnchantment
+ XXX.item.enchantment.FrostWalkerEnchantment
- XXX.item.enchantment.KnockbackEnchantment
+ XXX.item.enchantment.LootBonusEnchantment
- XXX.item.enchantment.MendingEnchantment
+ XXX.item.enchantment.MultiShotEnchantment
- XXX.item.enchantment.OxygenEnchantment
- XXX.item.enchantment.package-info
+ XXX.item.enchantment.ProtectionEnchantment
- XXX.item.enchantment.ProtectionEnchantment$Type
+ XXX.item.enchantment.QuickChargeEnchantment
- XXX.item.enchantment.SoulSpeedEnchantment
+ XXX.item.enchantment.SweepingEdgeEnchantment
- XXX.item.enchantment.SwiftSneakEnchantment
+ XXX.item.enchantment.ThornsEnchantment
- XXX.item.enchantment.TridentChannelingEnchantment
+ XXX.item.enchantment.TridentImpalerEnchantment
- XXX.item.enchantment.TridentLoyaltyEnchantment
+ XXX.item.enchantment.TridentRiptideEnchantment
- XXX.item.enchantment.UntouchingEnchantment
+ XXX.item.enchantment.VanishingCurseEnchantment
- XXX.item.enchantment.WaterWalkerEnchantment
+ XXX.item.enchantment.WaterWorkerEnchantment
- XXX.item.trading.Merchant
+ XXX.item.trading.MerchantOffer
- XXX.item.trading.MerchantOffers
+ XXX.item.trading.package-info
+ XXX.jfr.callback.package-info
- XXX.jfr.callback.ProfiledDuration
- XXX.jfr.event.ChunkGenerationEvent
+ XXX.jfr.event.ChunkGenerationEvent$Fields
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
+ XXX.jfr.event.WorldLoadFinishedEvent
- XXX.jfr.parse.JfrStatsParser
+ XXX.jfr.parse.JfrStatsParser$1
- XXX.jfr.parse.JfrStatsParser$MutableCountAndSize
+ XXX.jfr.parse.JfrStatsResult
- XXX.jfr.parse.package-info
+ XXX.jfr.serialize.JfrResultJsonSerializer
- XXX.jfr.serialize.package-info
+ XXX.jfr.stats.ChunkGenStat
- XXX.jfr.stats.CpuLoadStat
+ XXX.jfr.stats.FileIOStat
- XXX.jfr.stats.FileIOStat$Summary
+ XXX.jfr.stats.GcHeapStat
- XXX.jfr.stats.GcHeapStat$Summary
+ XXX.jfr.stats.GcHeapStat$Timing
- XXX.jfr.stats.NetworkPacketSummary
+ XXX.jfr.stats.NetworkPacketSummary$PacketCountAndSize
- XXX.jfr.stats.NetworkPacketSummary$PacketIdentification
+ XXX.jfr.stats.package-info
+ XXX.jfr.stats.ThreadAllocationStat
- XXX.jfr.stats.ThreadAllocationStat$Summary
+ XXX.jfr.stats.TickTimeStat
+ XXX.jfr.stats.TimedStat
- XXX.jfr.stats.TimedStatSummary
- XXX.jfr.stats.TimeStamped
+ XXX.level.biome.AmbientAdditionsSettings
- XXX.level.biome.AmbientMoodSettings
+ XXX.level.biome.AmbientParticleSettings
- XXX.level.biome.Biome
+ XXX.level.biome.Biome$1
- XXX.level.biome.Biome$BiomeBuilder
+ XXX.level.biome.Biome$ClimateSettings
- XXX.level.biome.Biome$Precipitation
+ XXX.level.biome.Biome$TemperatureModifier
- XXX.level.biome.Biome$TemperatureModifier$1
+ XXX.level.biome.Biome$TemperatureModifier$2
- XXX.level.biome.BiomeGenerationSettings
+ XXX.level.biome.BiomeGenerationSettings$Builder
- XXX.level.biome.BiomeGenerationSettings$PlainBuilder
+ XXX.level.biome.BiomeManager
- XXX.level.biome.BiomeManager$NoiseBiomeSource
+ XXX.level.biome.BiomeResolver
- XXX.level.biome.Biomes
- XXX.level.biome.BiomeSource
+ XXX.level.biome.BiomeSources
- XXX.level.biome.BiomeSpecialEffects
+ XXX.level.biome.BiomeSpecialEffects$Builder
- XXX.level.biome.BiomeSpecialEffects$GrassColorModifier
+ XXX.level.biome.BiomeSpecialEffects$GrassColorModifier$1
- XXX.level.biome.BiomeSpecialEffects$GrassColorModifier$2
+ XXX.level.biome.BiomeSpecialEffects$GrassColorModifier$3
+ XXX.level.biome.CheckerboardColumnBiomeSource
- XXX.level.biome.Climate
+ XXX.level.biome.Climate$DistanceMetric
- XXX.level.biome.Climate$Parameter
+ XXX.level.biome.Climate$ParameterList
- XXX.level.biome.Climate$ParameterPoint
+ XXX.level.biome.Climate$RTree
- XXX.level.biome.Climate$RTree$Leaf
+ XXX.level.biome.Climate$RTree$Node
- XXX.level.biome.Climate$RTree$SubTree
+ XXX.level.biome.Climate$Sampler
- XXX.level.biome.Climate$SpawnFinder
+ XXX.level.biome.Climate$SpawnFinder$Result
- XXX.level.biome.Climate$TargetPoint
+ XXX.level.biome.FeatureSorter
- XXX.level.biome.FeatureSorter$1FeatureData
+ XXX.level.biome.FeatureSorter$StepFeatureData
- XXX.level.biome.FixedBiomeSource
+ XXX.level.biome.MobSpawnSettings
- XXX.level.biome.MobSpawnSettings$Builder
+ XXX.level.biome.MobSpawnSettings$MobSpawnCost
- XXX.level.biome.MobSpawnSettings$SpawnerData
+ XXX.level.biome.MultiNoiseBiomeSource
- XXX.level.biome.MultiNoiseBiomeSourceParameterList
+ XXX.level.biome.MultiNoiseBiomeSourceParameterList$Preset
- XXX.level.biome.MultiNoiseBiomeSourceParameterList$Preset$1
+ XXX.level.biome.MultiNoiseBiomeSourceParameterList$Preset$2
- XXX.level.biome.MultiNoiseBiomeSourceParameterList$Preset$SourceProvider
+ XXX.level.biome.MultiNoiseBiomeSourceParameterLists
- XXX.level.biome.OverworldBiomeBuilder
+ XXX.level.biome.TheEndBiomeSource
+ XXX.level.block.CherryLeavesBlock
- XXX.level.block.ChestBlock
+ XXX.level.block.ChestBlock$1
- XXX.level.block.ChestBlock$2
+ XXX.level.block.ChestBlock$2$1
- XXX.level.block.ChestBlock$3
+ XXX.level.block.ChestBlock$4
- XXX.level.block.ChiseledBookShelfBlock
+ XXX.level.block.ChiseledBookShelfBlock$1
- XXX.level.block.ChorusFlowerBlock
+ XXX.level.block.ChorusPlantBlock
- XXX.level.block.CocoaBlock
+ XXX.level.block.CocoaBlock$1
- XXX.level.block.CommandBlock
+ XXX.level.block.ComparatorBlock
- XXX.level.block.ComposterBlock
+ XXX.level.block.ComposterBlock$EmptyContainer
- XXX.level.block.ComposterBlock$InputContainer
+ XXX.level.block.ComposterBlock$OutputContainer
- XXX.level.block.ConcretePowderBlock
+ XXX.level.block.ConduitBlock
+ XXX.level.block.Fallable
- XXX.level.block.FallingBlock
- XXX.level.block.FarmableBlock
+ XXX.level.block.FarmBlock
+ XXX.level.block.FilledCopperSinkBlock
- XXX.level.block.FireBlock
+ XXX.level.block.FletchingTableBlock
- XXX.level.block.FlowerBlock
+ XXX.level.block.FlowerPotBlock
- XXX.level.block.FrogspawnBlock
+ XXX.level.block.FrostedIceBlock
- XXX.level.block.FungusBlock
+ XXX.level.block.FurnaceBlock
- XXX.level.block.GameMasterBlock
+ XXX.level.block.GlassBlock
- XXX.level.block.GlazedTerracottaBlock
+ XXX.level.block.GlowLichenBlock
- XXX.level.block.GrassBlock
+ XXX.level.block.GravelBlock
- XXX.level.block.GrindstoneBlock
+ XXX.level.block.GrindstoneBlock$1
- XXX.level.block.GrowingPlantBlock
+ XXX.level.block.GrowingPlantBodyBlock
- XXX.level.block.GrowingPlantHeadBlock
+ XXX.level.block.HalfTransparentBlock
- XXX.level.block.HangingRootsBlock
+ XXX.level.block.HayBlock
- XXX.level.block.HoneyBlock
+ XXX.level.block.HopperBlock
- XXX.level.block.HopperBlock$1
+ XXX.level.block.HorizontalDirectionalBlock
- XXX.level.block.HugeMushroomBlock
+ XXX.level.block.IceBlock
- XXX.level.block.InfestedBlock
+ XXX.level.block.InfestedRotatedPillarBlock
- XXX.level.block.IronBarsBlock
+ XXX.level.block.JigsawBlock
- XXX.level.block.JukeboxBlock
+ XXX.level.block.KelpBlock
- XXX.level.block.KelpPlantBlock
+ XXX.level.block.LadderBlock
- XXX.level.block.LadderBlock$1
+ XXX.level.block.LanternBlock
- XXX.level.block.LavaCauldronBlock
+ XXX.level.block.LayeredCauldronBlock
- XXX.level.block.LeavesBlock
+ XXX.level.block.LecternBlock
- XXX.level.block.LecternBlock$1
+ XXX.level.block.LevelEvent
- XXX.level.block.LeverBlock
+ XXX.level.block.LeverBlock$1
- XXX.level.block.LightBlock
+ XXX.level.block.LightningRodBlock
- XXX.level.block.LiquidBlock
+ XXX.level.block.LiquidBlockContainer
- XXX.level.block.LoomBlock
+ XXX.level.block.MagmaBlock
- XXX.level.block.MangroveLeavesBlock
+ XXX.level.block.MangrovePropaguleBlock
- XXX.level.block.MangroveRootsBlock
+ XXX.level.block.MelonBlock
- XXX.level.block.Mirror
+ XXX.level.block.Mirror$1
- XXX.level.block.MossBlock
+ XXX.level.block.MudBlock
- XXX.level.block.MultifaceBlock
+ XXX.level.block.MultifaceSpreader
- XXX.level.block.MultifaceSpreader$DefaultSpreaderConfig
+ XXX.level.block.MultifaceSpreader$SpreadConfig
- XXX.level.block.MultifaceSpreader$SpreadPos
+ XXX.level.block.MultifaceSpreader$SpreadPredicate
- XXX.level.block.MultifaceSpreader$SpreadType
+ XXX.level.block.MultifaceSpreader$SpreadType$1
- XXX.level.block.MultifaceSpreader$SpreadType$2
+ XXX.level.block.MultifaceSpreader$SpreadType$3
- XXX.level.block.MushroomBlock
+ XXX.level.block.MyceliumBlock
- XXX.level.block.NetherPortalBlock
+ XXX.level.block.NetherPortalBlock$1
+ XXX.level.block.NetherrackBlock
- XXX.level.block.NetherSproutsBlock
+ XXX.level.block.NetherVines
- XXX.level.block.NetherWartBlock
- XXX.level.block.NoteBlock
+ XXX.level.block.NyliumBlock
- XXX.level.block.ObserverBlock
- XXX.level.block.package-info
+ XXX.level.block.PackedAirBlock
+ XXX.level.block.PiglinWallSkullBlock
- XXX.level.block.PinkPetalsBlock
+ XXX.level.block.PipeBlock
- XXX.level.block.PitcherCropBlock
+ XXX.level.block.PlaceBlock
+ XXX.level.block.SpleavesBlock
- XXX.level.block.SpongeBlock
+ XXX.level.block.SporeBlossomBlock
- XXX.level.block.SpreadingSnowyDirtBlock
+ XXX.level.block.StainedGlassBlock
- XXX.level.block.StainedGlassPaneBlock
+ XXX.level.block.StairBlock
- XXX.level.block.StairBlock$1
+ XXX.level.block.StandingSignBlock
- XXX.level.block.StemBlock
+ XXX.level.block.StemGrownBlock
- XXX.level.block.StonecutterBlock
+ XXX.level.block.StructureBlock
- XXX.level.block.StructureBlock$1
+ XXX.level.block.StructureVoidBlock
- XXX.level.block.SugarCaneBlock
+ XXX.level.block.SupportType
- XXX.level.block.SupportType$1
+ XXX.level.block.SupportType$2
- XXX.level.block.SupportType$3
+ XXX.level.block.SuspiciousEffectHolder
- XXX.level.block.SweetBerryBushBlock
+ XXX.level.block.TallFlowerBlock
- XXX.level.block.TallGrassBlock
+ XXX.level.block.TallSeagrassBlock
- XXX.level.block.TargetBlock
+ XXX.level.block.TintedGlassBlock
- XXX.level.block.TntBlock
+ XXX.level.block.TorchBlock
- XXX.level.block.TorchflowerCropBlock
+ XXX.level.block.TrapDoorBlock
- XXX.level.block.TrapDoorBlock$1
+ XXX.level.block.TrappedChestBlock
- XXX.level.block.TripWireBlock
+ XXX.level.block.TripWireBlock$1
- XXX.level.block.TripWireHookBlock
+ XXX.level.block.TripWireHookBlock$1
- XXX.level.block.TurtleEggBlock
+ XXX.level.block.TwistingVinesBlock
- XXX.level.block.TwistingVinesPlantBlock
+ XXX.level.block.VineBlock
- XXX.level.block.VineBlock$1
+ XXX.level.block.WallBannerBlock
- XXX.level.block.WallBlock
+ XXX.level.block.WallBlock$1
- XXX.level.block.WallHangingSignBlock
+ XXX.level.block.WallHangingSignBlock$1
- XXX.level.block.WallSignBlock
+ XXX.level.block.WallSkullBlock
- XXX.level.block.WallTorchBlock
+ XXX.level.block.WaterlilyBlock
- XXX.level.block.WeatheringCopper
+ XXX.level.block.WeatheringCopper$WeatherState
- XXX.level.block.WeatheringCopperFullBlock
+ XXX.level.block.WeatheringCopperSlabBlock
- XXX.level.block.WeatheringCopperStairBlock
+ XXX.level.block.WebBlock
- XXX.level.block.WeepingVinesBlock
+ XXX.level.block.WeepingVinesPlantBlock
- XXX.level.block.WeightedPressurePlateBlock
+ XXX.level.block.WetSpongeBlock
- XXX.level.block.WitherRoseBlock
+ XXX.level.block.WitherSkullBlock
- XXX.level.block.WitherWallSkullBlock
+ XXX.level.block.WoolCarpetBlock
- XXX.level.border.BorderChangeListener
+ XXX.level.border.BorderChangeListener$DelegateBorderChangeListener
- XXX.level.border.BorderStatus
- XXX.level.border.package-info
+ XXX.level.border.WorldBorder
- XXX.level.border.WorldBorder$BorderExtent
+ XXX.level.border.WorldBorder$MovingBorderExtent
- XXX.level.border.WorldBorder$Settings
+ XXX.level.border.WorldBorder$StaticBorderExtent
+ XXX.level.chunk.BlockColumn
- XXX.level.chunk.BulkSectionAccess
+ XXX.level.chunk.CarvingMask
- XXX.level.chunk.CarvingMask$Mask
+ XXX.level.chunk.ChunkAccess
- XXX.level.chunk.ChunkAccess$TicksToSave
+ XXX.level.chunk.ChunkGenerator
+ XXX.level.chunk.ChunkGenerators
- XXX.level.chunk.ChunkGeneratorStructureState
- XXX.level.chunk.ChunkSource
+ XXX.level.chunk.ChunkStatus
- XXX.level.chunk.ChunkStatus$ChunkType
+ XXX.level.chunk.ChunkStatus$GenerationTask
- XXX.level.chunk.ChunkStatus$LoadingTask
+ XXX.level.chunk.ChunkStatus$SimpleGenerationTask
- XXX.level.chunk.DataLayer
+ XXX.level.chunk.EmptyLevelChunk
- XXX.level.chunk.GlobalPalette
+ XXX.level.chunk.HashMapPalette
- XXX.level.chunk.ImposterProtoChunk
+ XXX.level.chunk.LevelChunk
- XXX.level.chunk.LevelChunk$1
+ XXX.level.chunk.LevelChunk$BoundTickingBlockEntity
- XXX.level.chunk.LevelChunk$EntityCreationType
+ XXX.level.chunk.LevelChunk$PostLoadProcessor
- XXX.level.chunk.LevelChunk$RebindableTickingBlockEntityWrapper
+ XXX.level.chunk.LevelChunkSection
- XXX.level.chunk.LevelChunkSection$1BlockCounter
+ XXX.level.chunk.LightChunkGetter
- XXX.level.chunk.LinearPalette
+ XXX.level.chunk.MissingPaletteEntryException
- XXX.level.chunk.package-info
- XXX.level.chunk.Palette
+ XXX.level.chunk.Palette$Factory
+ XXX.level.chunk.PalettedContainer
- XXX.level.chunk.PalettedContainer$Configuration
+ XXX.level.chunk.PalettedContainer$CountConsumer
- XXX.level.chunk.PalettedContainer$Data
+ XXX.level.chunk.PalettedContainer$Strategy
- XXX.level.chunk.PalettedContainer$Strategy$1
+ XXX.level.chunk.PalettedContainer$Strategy$2
- XXX.level.chunk.PalettedContainerRO
+ XXX.level.chunk.PalettedContainerRO$PackedData
- XXX.level.chunk.PalettedContainerRO$Unpacker
- XXX.level.chunk.PaletteResize
+ XXX.level.chunk.ProtoChunk
- XXX.level.chunk.SingleValuePalette
+ XXX.level.chunk.StructureAccess
- XXX.level.chunk.UpgradeData
+ XXX.level.chunk.UpgradeData$BlockFixer
- XXX.level.chunk.UpgradeData$BlockFixers
+ XXX.level.chunk.UpgradeData$BlockFixers$1
- XXX.level.chunk.UpgradeData$BlockFixers$2
+ XXX.level.chunk.UpgradeData$BlockFixers$3
- XXX.level.chunk.UpgradeData$BlockFixers$4
+ XXX.level.chunk.UpgradeData$BlockFixers$5
+ XXX.level.dimension.BuiltinDimensionTypes
- XXX.level.dimension.DimensionDefaults
+ XXX.level.dimension.DimensionType
- XXX.level.dimension.DimensionType$MonsterSettings
+ XXX.level.dimension.LevelStem
- XXX.level.dimension.package-info
+ XXX.level.entity.ChunkEntities
- XXX.level.entity.ChunkStatusUpdateListener
+ XXX.level.entity.EntityAccess
- XXX.level.entity.EntityInLevelCallback
+ XXX.level.entity.EntityInLevelCallback$1
- XXX.level.entity.EntityLookup
+ XXX.level.entity.EntityPersistentStorage
- XXX.level.entity.EntitySection
+ XXX.level.entity.EntitySectionStorage
- XXX.level.entity.EntityTickList
+ XXX.level.entity.EntityTypeTest
- XXX.level.entity.EntityTypeTest$1
+ XXX.level.entity.LevelCallback
- XXX.level.entity.LevelEntityGetter
+ XXX.level.entity.LevelEntityGetterAdapter
- XXX.level.entity.package-info
- XXX.level.entity.PersistentEntitySectionManager
+ XXX.level.entity.PersistentEntitySectionManager$Callback
- XXX.level.entity.PersistentEntitySectionManager$ChunkLoadStatus
+ XXX.level.entity.TransientEntitySectionManager
- XXX.level.entity.TransientEntitySectionManager$Callback
+ XXX.level.entity.Visibility
+ XXX.level.gameevent.BlockPositionSource
- XXX.level.gameevent.BlockPositionSource$Type
+ XXX.level.gameevent.DynamicGameEventListener
- XXX.level.gameevent.EntityPositionSource
+ XXX.level.gameevent.EntityPositionSource$Type
- XXX.level.gameevent.EuclideanGameEventListenerRegistry
+ XXX.level.gameevent.GameEvent
- XXX.level.gameevent.GameEvent$Context
+ XXX.level.gameevent.GameEvent$ListenerInfo
- XXX.level.gameevent.GameEventDispatcher
+ XXX.level.gameevent.GameEventListener
- XXX.level.gameevent.GameEventListener$DeliveryMode
+ XXX.level.gameevent.GameEventListenerRegistry
- XXX.level.gameevent.GameEventListenerRegistry$1
+ XXX.level.gameevent.GameEventListenerRegistry$ListenerVisitor
- XXX.level.gameevent.package-info
- XXX.level.gameevent.PositionSource
+ XXX.level.gameevent.PositionSourceType
- XXX.level.levelgen.Aquifer
+ XXX.level.levelgen.Aquifer$1
- XXX.level.levelgen.Aquifer$FluidPicker
+ XXX.level.levelgen.Aquifer$FluidStatus
- XXX.level.levelgen.Aquifer$NoiseBasedAquifer
+ XXX.level.levelgen.Beardifier
- XXX.level.levelgen.Beardifier$1
+ XXX.level.levelgen.Beardifier$Rigid
- XXX.level.levelgen.BelowZeroRetrogen
+ XXX.level.levelgen.BelowZeroRetrogen$1
- XXX.level.levelgen.BitRandomSource
+ XXX.level.levelgen.Column
- XXX.level.levelgen.Column$Line
+ XXX.level.levelgen.Column$Range
- XXX.level.levelgen.Column$Ray
+ XXX.level.levelgen.DebugLevelSource
- XXX.level.levelgen.Density
+ XXX.level.levelgen.DensityFunction
- XXX.level.levelgen.DensityFunction$ContextProvider
+ XXX.level.levelgen.DensityFunction$FunctionContext
- XXX.level.levelgen.DensityFunction$NoiseHolder
+ XXX.level.levelgen.DensityFunction$SimpleFunction
- XXX.level.levelgen.DensityFunction$SinglePointContext
+ XXX.level.levelgen.DensityFunction$Visitor
- XXX.level.levelgen.DensityFunctions
+ XXX.level.levelgen.DensityFunctions$1
- XXX.level.levelgen.DensityFunctions$Ap2
+ XXX.level.levelgen.DensityFunctions$BeardifierMarker
- XXX.level.levelgen.DensityFunctions$BeardifierOrMarker
+ XXX.level.levelgen.DensityFunctions$BlendAlpha
- XXX.level.levelgen.DensityFunctions$BlendDensity
+ XXX.level.levelgen.DensityFunctions$BlendOffset
- XXX.level.levelgen.DensityFunctions$Clamp
+ XXX.level.levelgen.DensityFunctions$Constant
- XXX.level.levelgen.DensityFunctions$EndIslandDensityFunction
+ XXX.level.levelgen.DensityFunctions$HolderHolder
- XXX.level.levelgen.DensityFunctions$Mapped
+ XXX.level.levelgen.DensityFunctions$Mapped$Type
- XXX.level.levelgen.DensityFunctions$Marker
+ XXX.level.levelgen.DensityFunctions$Marker$Type
- XXX.level.levelgen.DensityFunctions$MarkerOrMarked
+ XXX.level.levelgen.DensityFunctions$MulOrAdd
- XXX.level.levelgen.DensityFunctions$MulOrAdd$Type
+ XXX.level.levelgen.DensityFunctions$Noise
- XXX.level.levelgen.DensityFunctions$PureTransformer
+ XXX.level.levelgen.DensityFunctions$RangeChoice
- XXX.level.levelgen.DensityFunctions$Shift
+ XXX.level.levelgen.DensityFunctions$ShiftA
- XXX.level.levelgen.DensityFunctions$ShiftB
- XXX.level.levelgen.DensityFunctions$ShiftedNoise
+ XXX.level.levelgen.DensityFunctions$ShiftNoise
+ XXX.level.levelgen.DensityFunctions$Spline
- XXX.level.levelgen.DensityFunctions$Spline$Coordinate
+ XXX.level.levelgen.DensityFunctions$Spline$Point
- XXX.level.levelgen.DensityFunctions$TransformerWithContext
+ XXX.level.levelgen.DensityFunctions$TwoArgumentSimpleFunction
- XXX.level.levelgen.DensityFunctions$TwoArgumentSimpleFunction$Type
+ XXX.level.levelgen.DensityFunctions$WeirdScaledSampler
- XXX.level.levelgen.DensityFunctions$WeirdScaledSampler$RarityValueMapper
+ XXX.level.levelgen.DensityFunctions$YClampedGradient
- XXX.level.levelgen.FlatLevelSource
+ XXX.level.levelgen.GenerationStep
- XXX.level.levelgen.GenerationStep$Carving
+ XXX.level.levelgen.GenerationStep$Decoration
- XXX.level.levelgen.GeodeBlockSettings
+ XXX.level.levelgen.GeodeCrackSettings
- XXX.level.levelgen.GeodeLayerSettings
+ XXX.level.levelgen.Heightmap
- XXX.level.levelgen.Heightmap$Types
+ XXX.level.levelgen.Heightmap$Usage
- XXX.level.levelgen.LegacyRandomSource
+ XXX.level.levelgen.LegacyRandomSource$LegacyPositionalRandomFactory
- XXX.level.levelgen.MarsagliaPolarGaussian
+ XXX.level.levelgen.MoonBaseBuilder
+ XXX.level.levelgen.MoonBaseBuilder$Branch
+ XXX.level.levelgen.package-info
+ XXX.level.lighting.BlockLightEngine
- XXX.level.lighting.BlockLightSectionStorage
+ XXX.level.lighting.BlockLightSectionStorage$BlockDataLayerStorageMap
- XXX.level.lighting.DataLayerStorageMap
+ XXX.level.lighting.DynamicGraphMinFixedPoint
- XXX.level.lighting.DynamicGraphMinFixedPoint$1
+ XXX.level.lighting.LayerLightEngine
- XXX.level.lighting.LayerLightEventListener
+ XXX.level.lighting.LayerLightEventListener$DummyLightLayerEventListener
- XXX.level.lighting.LayerLightSectionStorage
+ XXX.level.lighting.LayerLightSectionStorage$1
+ XXX.level.lighting.LeveledPriorityQueue
- XXX.level.lighting.LeveledPriorityQueue$1
- XXX.level.lighting.LevelLightEngine
+ XXX.level.lighting.LightEventListener
- XXX.level.lighting.package-info
- XXX.level.lighting.SkyLightEngine
+ XXX.level.lighting.SkyLightSectionStorage
- XXX.level.lighting.SkyLightSectionStorage$1
+ XXX.level.lighting.SkyLightSectionStorage$SkyDataLayerStorageMap
- XXX.level.lighting.SpatialLongSet
+ XXX.level.lighting.SpatialLongSet$InternalMap
+ XXX.level.material.EmptyFluid
- XXX.level.material.FlowingFluid
+ XXX.level.material.FlowingFluid$1
- XXX.level.material.Fluid
- XXX.level.material.Fluids
+ XXX.level.material.FluidState
+ XXX.level.material.FogType
- XXX.level.material.LavaFluid
+ XXX.level.material.LavaFluid$Flowing
- XXX.level.material.LavaFluid$Source
+ XXX.level.material.Material
- XXX.level.material.Material$Builder
+ XXX.level.material.MaterialColor
- XXX.level.material.MaterialColor$Brightness
+ XXX.level.material.package-info
+ XXX.level.material.PushReaction
- XXX.level.material.WaterFluid
+ XXX.level.material.WaterFluid$Flowing
- XXX.level.material.WaterFluid$Source
+ XXX.level.pathfinder.AmphibiousNodeEvaluator
- XXX.level.pathfinder.BinaryHeap
+ XXX.level.pathfinder.BlockPathTypes
- XXX.level.pathfinder.FlyNodeEvaluator
+ XXX.level.pathfinder.Node
- XXX.level.pathfinder.NodeEvaluator
+ XXX.level.pathfinder.package-info
+ XXX.level.pathfinder.Path
- XXX.level.pathfinder.PathComputationType
+ XXX.level.pathfinder.PathFinder
- XXX.level.pathfinder.SwimNodeEvaluator
+ XXX.level.pathfinder.Target
- XXX.level.pathfinder.WalkNodeEvaluator
+ XXX.level.portal.package-info
- XXX.level.portal.PortalForcer
+ XXX.level.portal.PortalInfo
- XXX.level.portal.PortalShape
- XXX.level.progress.ChunkProgressListener
+ XXX.level.progress.ChunkProgressListenerFactory
- XXX.level.progress.LoggerChunkProgressListener
+ XXX.level.progress.package-info
+ XXX.level.progress.ProcessorChunkProgressListener
- XXX.level.progress.StoringChunkProgressListener
- XXX.level.redstone.CollectingNeighborUpdater
+ XXX.level.redstone.CollectingNeighborUpdater$FullNeighborUpdate
- XXX.level.redstone.CollectingNeighborUpdater$MultiNeighborUpdate
+ XXX.level.redstone.CollectingNeighborUpdater$NeighborUpdates
- XXX.level.redstone.CollectingNeighborUpdater$ShapeUpdate
+ XXX.level.redstone.CollectingNeighborUpdater$SimpleNeighborUpdate
- XXX.level.redstone.InstantNeighborUpdater
+ XXX.level.redstone.NeighborUpdater
+ XXX.level.redstone.package-info
- XXX.level.redstone.Redstone
+ XXX.level.saveddata.package-info
- XXX.level.saveddata.SavedData
- XXX.level.storage.CommandStorage
+ XXX.level.storage.CommandStorage$Container
- XXX.level.storage.DataVersion
+ XXX.level.storage.DerivedLevelData
- XXX.level.storage.DimensionDataStorage
+ XXX.level.storage.LevelData
- XXX.level.storage.LevelResource
+ XXX.level.storage.LevelStorageException
- XXX.level.storage.LevelStorageSource
+ XXX.level.storage.LevelStorageSource$LevelCandidates
- XXX.level.storage.LevelStorageSource$LevelDirectory
+ XXX.level.storage.LevelStorageSource$LevelStorageAccess
- XXX.level.storage.LevelStorageSource$LevelStorageAccess$1
+ XXX.level.storage.LevelStorageSource$LevelStorageAccess$2
- XXX.level.storage.LevelSummary
+ XXX.level.storage.LevelSummary$BackupStatus
- XXX.level.storage.LevelVersion
- XXX.level.storage.package-info
+ XXX.level.storage.PlayerDataStorage
- XXX.level.storage.PrimaryLevelData
+ XXX.level.storage.PrimaryLevelData$SpecialWorldProperty
- XXX.level.storage.ServerLevelData
+ XXX.level.storage.WorldData
- XXX.level.storage.WritableLevelData
+ XXX.level.timers.FunctionCallback
- XXX.level.timers.FunctionCallback$Serializer
+ XXX.level.timers.FunctionTagCallback
- XXX.level.timers.FunctionTagCallback$Serializer
- XXX.level.timers.package-info
+ XXX.level.timers.TimerCallback
- XXX.level.timers.TimerCallback$Serializer
+ XXX.level.timers.TimerCallbacks
- XXX.level.timers.TimerQueue
+ XXX.level.timers.TimerQueue$Event
+ XXX.levelgen.feature.CraterFeature
- XXX.levelgen.feature.DeltaFeature
+ XXX.levelgen.feature.DesertWellFeature
- XXX.levelgen.feature.DiskFeature
+ XXX.levelgen.feature.DripstoneClusterFeature
- XXX.levelgen.feature.DripstoneUtils
+ XXX.levelgen.feature.EndGatewayFeature
- XXX.levelgen.feature.EndIslandFeature
+ XXX.levelgen.feature.EndPodiumFeature
- XXX.levelgen.feature.Feature
+ XXX.levelgen.feature.FeatureCountTracker
- XXX.levelgen.feature.FeatureCountTracker$1
+ XXX.levelgen.feature.FeatureCountTracker$FeatureData
- XXX.levelgen.feature.FeatureCountTracker$LevelData
+ XXX.levelgen.feature.FeaturePlaceContext
- XXX.levelgen.feature.FillLayerFeature
+ XXX.levelgen.feature.FossilFeature
- XXX.levelgen.feature.FossilFeatureConfiguration
+ XXX.levelgen.feature.GeodeFeature
- XXX.levelgen.feature.GlowstoneFeature
+ XXX.levelgen.feature.HugeBrownMushroomFeature
- XXX.levelgen.feature.HugeFungusConfiguration
+ XXX.levelgen.feature.HugeFungusFeature
- XXX.levelgen.feature.HugeRedMushroomFeature
- XXX.levelgen.feature.IcebergFeature
+ XXX.levelgen.feature.IceSpikeFeature
+ XXX.levelgen.feature.KelpFeature
- XXX.levelgen.feature.LakeFeature
+ XXX.levelgen.feature.LakeFeature$Configuration
- XXX.levelgen.feature.LargeDripstoneFeature
+ XXX.levelgen.feature.LargeDripstoneFeature$LargeDripstone
- XXX.levelgen.feature.LargeDripstoneFeature$WindOffsetter
+ XXX.levelgen.feature.LunarBaseFeature
- XXX.levelgen.feature.package-info
+ XXX.levelgen.flat.FlatLayerInfo
- XXX.levelgen.flat.FlatLevelGeneratorPreset
+ XXX.levelgen.flat.FlatLevelGeneratorPresets
- XXX.levelgen.flat.FlatLevelGeneratorPresets$Bootstrap
+ XXX.levelgen.flat.FlatLevelGeneratorSettings
- XXX.levelgen.flat.package-info
+ XXX.levelgen.heightproviders.BiasedToBottomHeight
- XXX.levelgen.heightproviders.ConstantHeight
+ XXX.levelgen.heightproviders.HeightProvider
- XXX.levelgen.heightproviders.HeightProviderType
+ XXX.levelgen.heightproviders.package-info
+ XXX.levelgen.heightproviders.TrapezoidHeight
- XXX.levelgen.heightproviders.UniformHeight
+ XXX.levelgen.heightproviders.VeryBiasedToBottomHeight
- XXX.levelgen.heightproviders.WeightedListHeight
- XXX.levelgen.material.MaterialRuleList
- XXX.levelgen.material.package-info
+ XXX.levelgen.material.WorldGenMaterialRule
- XXX.levelgen.placement.BiomeFilter
+ XXX.levelgen.placement.BlockPredicateFilter
- XXX.levelgen.placement.CarvingMaskPlacement
+ XXX.levelgen.placement.CaveSurface
- XXX.levelgen.placement.CountOnEveryLayerPlacement
+ XXX.levelgen.placement.CountPlacement
- XXX.levelgen.placement.EnvironmentScanPlacement
- XXX.levelgen.placement.HeightmapPlacement
+ XXX.levelgen.placement.HeightRangePlacement
+ XXX.levelgen.placement.InSquarePlacement
- XXX.levelgen.placement.NoiseBasedCountPlacement
+ XXX.levelgen.placement.NoiseThresholdCountPlacement
- XXX.levelgen.placement.package-info
- XXX.levelgen.placement.PlacedFeature
+ XXX.levelgen.placement.PlacementContext
- XXX.levelgen.placement.PlacementFilter
+ XXX.levelgen.placement.PlacementModifier
- XXX.levelgen.placement.PlacementModifierType
+ XXX.levelgen.placement.RandomOffsetPlacement
- XXX.levelgen.placement.RarityFilter
+ XXX.levelgen.placement.RepeatingPlacement
- XXX.levelgen.placement.SurfaceRelativeThresholdFilter
+ XXX.levelgen.placement.SurfaceWaterDepthFilter
- XXX.levelgen.presets.package-info
+ XXX.levelgen.presets.WorldPreset
- XXX.levelgen.presets.WorldPresets
+ XXX.levelgen.presets.WorldPresets$Bootstrap
+ XXX.levelgen.structure.BoundingBox
- XXX.levelgen.structure.BoundingBox$1
- XXX.levelgen.structure.BuiltinStructures
+ XXX.levelgen.structure.BuiltinStructureSets
+ XXX.levelgen.structure.LegacyStructureDataHandler
- XXX.levelgen.structure.package-info
- XXX.levelgen.structure.PoolElementStructurePiece
+ XXX.levelgen.structure.PostPlacementProcessor
- XXX.levelgen.structure.ScatteredFeaturePiece
+ XXX.levelgen.structure.SinglePieceStructure
- XXX.levelgen.structure.SinglePieceStructure$PieceConstructor
+ XXX.levelgen.structure.Structure
- XXX.levelgen.structure.Structure$GenerationContext
+ XXX.levelgen.structure.Structure$GenerationStub
- XXX.levelgen.structure.Structure$StructureSettings
+ XXX.levelgen.structure.StructureCheck
- XXX.levelgen.structure.StructureCheckResult
+ XXX.levelgen.structure.StructureFeatureIndexSavedData
- XXX.levelgen.structure.StructurePiece
+ XXX.levelgen.structure.StructurePiece$1
- XXX.levelgen.structure.StructurePiece$BlockSelector
+ XXX.levelgen.structure.StructurePieceAccessor
- XXX.levelgen.structure.StructureSet
+ XXX.levelgen.structure.StructureSet$StructureSelectionEntry
- XXX.levelgen.structure.StructureSpawnOverride
+ XXX.levelgen.structure.StructureSpawnOverride$BoundingBoxType
- XXX.levelgen.structure.StructureStart
+ XXX.levelgen.structure.StructureType
- XXX.levelgen.structure.TemplateStructurePiece
+ XXX.levelgen.structure.TerrainAdjustment
- XXX.levelgen.synth.BlendedNoise
+ XXX.levelgen.synth.ImprovedNoise
- XXX.levelgen.synth.NoiseUtils
+ XXX.levelgen.synth.NormalNoise
- XXX.levelgen.synth.NormalNoise$NoiseParameters
- XXX.levelgen.synth.package-info
+ XXX.levelgen.synth.PerlinNoise
- XXX.levelgen.synth.PerlinSimplexNoise
+ XXX.levelgen.synth.SimplexNoise
+ XXX.loot.entries.AlternativesEntry
- XXX.loot.entries.AlternativesEntry$Builder
+ XXX.loot.entries.ComposableEntryContainer
- XXX.loot.entries.CompositeEntryBase
+ XXX.loot.entries.CompositeEntryBase$1
- XXX.loot.entries.CompositeEntryBase$CompositeEntryConstructor
+ XXX.loot.entries.DynamicLoot
- XXX.loot.entries.DynamicLoot$Serializer
+ XXX.loot.entries.EmptyLootItem
- XXX.loot.entries.EmptyLootItem$Serializer
+ XXX.loot.entries.EntryGroup
- XXX.loot.entries.EntryGroup$Builder
+ XXX.loot.entries.LootItem
- XXX.loot.entries.LootItem$Serializer
+ XXX.loot.entries.LootPoolEntries
- XXX.loot.entries.LootPoolEntry
+ XXX.loot.entries.LootPoolEntryContainer
- XXX.loot.entries.LootPoolEntryContainer$Builder
+ XXX.loot.entries.LootPoolEntryContainer$Serializer
- XXX.loot.entries.LootPoolEntryType
+ XXX.loot.entries.LootPoolSingletonContainer
- XXX.loot.entries.LootPoolSingletonContainer$1
+ XXX.loot.entries.LootPoolSingletonContainer$Builder
- XXX.loot.entries.LootPoolSingletonContainer$DummyBuilder
+ XXX.loot.entries.LootPoolSingletonContainer$EntryBase
- XXX.loot.entries.LootPoolSingletonContainer$EntryConstructor
+ XXX.loot.entries.LootPoolSingletonContainer$Serializer
- XXX.loot.entries.LootTableReference
+ XXX.loot.entries.LootTableReference$Serializer
+ XXX.loot.entries.package-info
- XXX.loot.entries.SequentialEntry
+ XXX.loot.entries.SequentialEntry$Builder
- XXX.loot.entries.TagEntry
+ XXX.loot.entries.TagEntry$1
- XXX.loot.entries.TagEntry$Serializer
- XXX.loot.functions.ApplyBonusCount
+ XXX.loot.functions.ApplyBonusCount$BinomialWithBonusCount
- XXX.loot.functions.ApplyBonusCount$Formula
+ XXX.loot.functions.ApplyBonusCount$FormulaDeserializer
- XXX.loot.functions.ApplyBonusCount$OreDrops
+ XXX.loot.functions.ApplyBonusCount$Serializer
- XXX.loot.functions.ApplyBonusCount$UniformBonusCount
+ XXX.loot.functions.ApplyExplosionDecay
- XXX.loot.functions.ApplyExplosionDecay$Serializer
+ XXX.loot.functions.CopyBlockState
- XXX.loot.functions.CopyBlockState$Builder
+ XXX.loot.functions.CopyBlockState$Serializer
- XXX.loot.functions.CopyNameFunction
+ XXX.loot.functions.CopyNameFunction$NameSource
- XXX.loot.functions.CopyNameFunction$Serializer
+ XXX.loot.functions.CopyNbtFunction
- XXX.loot.functions.CopyNbtFunction$Builder
+ XXX.loot.functions.CopyNbtFunction$CopyOperation
- XXX.loot.functions.CopyNbtFunction$MergeStrategy
+ XXX.loot.functions.CopyNbtFunction$MergeStrategy$1
- XXX.loot.functions.CopyNbtFunction$MergeStrategy$2
+ XXX.loot.functions.CopyNbtFunction$MergeStrategy$3
- XXX.loot.functions.CopyNbtFunction$Serializer
+ XXX.loot.functions.EnchantRandomlyFunction
- XXX.loot.functions.EnchantRandomlyFunction$Builder
+ XXX.loot.functions.EnchantRandomlyFunction$Serializer
- XXX.loot.functions.EnchantWithLevelsFunction
+ XXX.loot.functions.EnchantWithLevelsFunction$Builder
- XXX.loot.functions.EnchantWithLevelsFunction$Serializer
+ XXX.loot.functions.ExplorationMapFunction
- XXX.loot.functions.ExplorationMapFunction$Builder
+ XXX.loot.functions.ExplorationMapFunction$Serializer
- XXX.loot.functions.FillPlayerHead
+ XXX.loot.functions.FillPlayerHead$Serializer
- XXX.loot.functions.FunctionReference
- XXX.loot.functions.FunctionUserBuilder
+ XXX.loot.functions.LimitCount
- XXX.loot.functions.LimitCount$Serializer
+ XXX.loot.functions.LootingEnchantFunction
- XXX.loot.functions.LootingEnchantFunction$Builder
+ XXX.loot.functions.LootingEnchantFunction$Serializer
+ XXX.loot.functions.LootItemConditionalFunction
- XXX.loot.functions.LootItemConditionalFunction$Builder
+ XXX.loot.functions.LootItemConditionalFunction$DummyBuilder
- XXX.loot.functions.LootItemConditionalFunction$Serializer
+ XXX.loot.functions.LootItemFunction
- XXX.loot.functions.LootItemFunction$Builder
- XXX.loot.functions.LootItemFunctions
+ XXX.loot.functions.LootItemFunctionType
+ XXX.loot.functions.package-info
- XXX.loot.functions.SetAttributesFunction
+ XXX.loot.functions.SetAttributesFunction$1
- XXX.loot.functions.SetAttributesFunction$Builder
+ XXX.loot.functions.SetAttributesFunction$Modifier
- XXX.loot.functions.SetAttributesFunction$ModifierBuilder
+ XXX.loot.functions.SetAttributesFunction$Serializer
- XXX.loot.functions.SetBannerPatternFunction
+ XXX.loot.functions.SetBannerPatternFunction$Builder
- XXX.loot.functions.SetBannerPatternFunction$Serializer
+ XXX.loot.functions.SetContainerContents
- XXX.loot.functions.SetContainerContents$Builder
+ XXX.loot.functions.SetContainerContents$Serializer
- XXX.loot.functions.SetContainerLootTable
+ XXX.loot.functions.SetContainerLootTable$Serializer
- XXX.loot.functions.SetEnchantmentsFunction
+ XXX.loot.functions.SetEnchantmentsFunction$Builder
- XXX.loot.functions.SetEnchantmentsFunction$Serializer
+ XXX.loot.functions.SetInstrumentFunction
- XXX.loot.functions.SetInstrumentFunction$Serializer
+ XXX.loot.functions.SetItemCountFunction
- XXX.loot.functions.SetItemCountFunction$Serializer
+ XXX.loot.functions.SetItemDamageFunction
- XXX.loot.functions.SetItemDamageFunction$Serializer
+ XXX.loot.functions.SetLoreFunction
- XXX.loot.functions.SetLoreFunction$Builder
+ XXX.loot.functions.SetLoreFunction$Serializer
- XXX.loot.functions.SetNameFunction
+ XXX.loot.functions.SetNameFunction$Serializer
- XXX.loot.functions.SetNbtFunction
+ XXX.loot.functions.SetNbtFunction$Serializer
- XXX.loot.functions.SetPotionFunction
+ XXX.loot.functions.SetPotionFunction$Serializer
- XXX.loot.functions.SetStewEffectFunction
+ XXX.loot.functions.SetStewEffectFunction$Builder
- XXX.loot.functions.SetStewEffectFunction$Serializer
+ XXX.loot.functions.SmeltItemFunction
- XXX.loot.functions.SmeltItemFunction$Serializer
- XXX.loot.packs.package-info
- XXX.loot.packs.VanillaArchaeologyLoot
+ XXX.loot.packs.VanillaBlockLoot
- XXX.loot.packs.VanillaChestLoot
+ XXX.loot.packs.VanillaEntityLoot
- XXX.loot.packs.VanillaFishingLoot
+ XXX.loot.packs.VanillaGiftLoot
- XXX.loot.packs.VanillaLootTableProvider
+ XXX.loot.packs.VanillaPiglinBarterLoot
+ XXX.loot.parameters.LootContextParam
+ XXX.loot.parameters.LootContextParams
- XXX.loot.parameters.LootContextParamSet
+ XXX.loot.parameters.LootContextParamSet$Builder
- XXX.loot.parameters.LootContextParamSets
- XXX.loot.parameters.package-info
+ XXX.loot.predicates.AlternativeLootItemCondition
- XXX.loot.predicates.AlternativeLootItemCondition$Builder
+ XXX.loot.predicates.AlternativeLootItemCondition$Serializer
- XXX.loot.predicates.BonusLevelTableCondition
+ XXX.loot.predicates.BonusLevelTableCondition$Serializer
- XXX.loot.predicates.ConditionReference
+ XXX.loot.predicates.ConditionReference$Serializer
- XXX.loot.predicates.ConditionUserBuilder
+ XXX.loot.predicates.DamageSourceCondition
- XXX.loot.predicates.DamageSourceCondition$Serializer
+ XXX.loot.predicates.EntityHasScoreCondition
- XXX.loot.predicates.EntityHasScoreCondition$Builder
+ XXX.loot.predicates.EntityHasScoreCondition$Serializer
- XXX.loot.predicates.ExplosionCondition
+ XXX.loot.predicates.ExplosionCondition$Serializer
- XXX.loot.predicates.InvertedLootItemCondition
+ XXX.loot.predicates.InvertedLootItemCondition$Serializer
- XXX.loot.predicates.LocationCheck
+ XXX.loot.predicates.LocationCheck$Serializer
- XXX.loot.predicates.LootItemBlockStatePropertyCondition
+ XXX.loot.predicates.LootItemBlockStatePropertyCondition$Builder
- XXX.loot.predicates.LootItemBlockStatePropertyCondition$Serializer
+ XXX.loot.predicates.LootItemCondition
- XXX.loot.predicates.LootItemCondition$Builder
- XXX.loot.predicates.LootItemConditions
+ XXX.loot.predicates.LootItemConditionType
+ XXX.loot.predicates.LootItemEntityPropertyCondition
- XXX.loot.predicates.LootItemEntityPropertyCondition$Serializer
+ XXX.loot.predicates.LootItemKilledByPlayerCondition
- XXX.loot.predicates.LootItemKilledByPlayerCondition$Serializer
+ XXX.loot.predicates.LootItemRandomChanceCondition
- XXX.loot.predicates.LootItemRandomChanceCondition$Serializer
+ XXX.loot.predicates.LootItemRandomChanceWithLootingCondition
- XXX.loot.predicates.LootItemRandomChanceWithLootingCondition$Serializer
+ XXX.loot.predicates.MatchTool
- XXX.loot.predicates.MatchTool$Serializer
+ XXX.loot.predicates.package-info
+ XXX.loot.predicates.TimeCheck
- XXX.loot.predicates.TimeCheck$Builder
+ XXX.loot.predicates.TimeCheck$Serializer
- XXX.loot.predicates.ValueCheckCondition
+ XXX.loot.predicates.ValueCheckCondition$Serializer
- XXX.loot.predicates.WeatherCheck
+ XXX.loot.predicates.WeatherCheck$Builder
- XXX.loot.predicates.WeatherCheck$Serializer
- XXX.metadata.pack.package-info
- XXX.metadata.pack.PackMetadataSection
+ XXX.metadata.pack.PackMetadataSectionSerializer
+ XXX.metrics.profiling.ActiveMetricsRecorder
- XXX.metrics.profiling.InactiveMetricsRecorder
+ XXX.metrics.profiling.MetricsRecorder
- XXX.metrics.profiling.package-info
- XXX.metrics.profiling.ProfilerSamplerAdapter
+ XXX.metrics.profiling.ServerMetricsSamplersProvider
- XXX.metrics.profiling.ServerMetricsSamplersProvider$1
+ XXX.metrics.profiling.ServerMetricsSamplersProvider$CpuStats
+ XXX.metrics.storage.MetricsPersister
+ XXX.metrics.storage.package-info
- XXX.metrics.storage.RecordedDeviation
- XXX.minecraft.data.package-info
- XXX.minecraft.server.package-info
+ XXX.minecraft.sounds.Music
- XXX.minecraft.sounds.Musics
- XXX.minecraft.sounds.package-info
+ XXX.minecraft.sounds.SoundEvent
- XXX.minecraft.sounds.SoundEvents
+ XXX.minecraft.sounds.SoundSource
+ XXX.minecraft.stats.package-info
+ XXX.minecraft.stats.RecipeBook
- XXX.minecraft.stats.RecipeBookSettings
+ XXX.minecraft.stats.RecipeBookSettings$TypeSettings
- XXX.minecraft.stats.ServerRecipeBook
+ XXX.minecraft.stats.ServerStatsCounter
- XXX.minecraft.stats.Stat
+ XXX.minecraft.stats.StatFormatter
+ XXX.minecraft.stats.Stats
- XXX.minecraft.stats.StatsCounter
- XXX.minecraft.stats.StatType
- XXX.minecraft.tags.BannerPatternTags
+ XXX.minecraft.tags.BiomeTags
- XXX.minecraft.tags.BlockTags
+ XXX.minecraft.tags.CatVariantTags
- XXX.minecraft.tags.DamageTypeTags
+ XXX.minecraft.tags.EntityTypeTags
- XXX.minecraft.tags.FlatLevelGeneratorPresetTags
+ XXX.minecraft.tags.FluidTags
- XXX.minecraft.tags.GameEventTags
+ XXX.minecraft.tags.InstrumentTags
- XXX.minecraft.tags.ItemTags
- XXX.minecraft.tags.package-info
+ XXX.minecraft.tags.PaintingVariantTags
- XXX.minecraft.tags.PoiTypeTags
+ XXX.minecraft.tags.StructureTags
- XXX.minecraft.tags.TagBuilder
+ XXX.minecraft.tags.TagEntry
- XXX.minecraft.tags.TagEntry$Lookup
+ XXX.minecraft.tags.TagFile
- XXX.minecraft.tags.TagKey
+ XXX.minecraft.tags.TagLoader
- XXX.minecraft.tags.TagLoader$1
+ XXX.minecraft.tags.TagLoader$EntryWithSource
- XXX.minecraft.tags.TagManager
+ XXX.minecraft.tags.TagManager$LoadResult
- XXX.minecraft.tags.TagNetworkSerialization
+ XXX.minecraft.tags.TagNetworkSerialization$NetworkPayload
- XXX.minecraft.tags.TagNetworkSerialization$TagOutput
+ XXX.minecraft.tags.WorldPresetTags
+ XXX.minecraft.util.AbortableIterationConsumer
- XXX.minecraft.util.AbortableIterationConsumer$Continuation
+ XXX.minecraft.util.BitStorage
- XXX.minecraft.util.Brightness
+ XXX.minecraft.util.ByIdMap
- XXX.minecraft.util.ByIdMap$1
+ XXX.minecraft.util.ByIdMap$OutOfBoundsStrategy
- XXX.minecraft.util.ClassInstanceMultiMap
+ XXX.minecraft.util.CommonColors
- XXX.minecraft.util.CommonLinks
+ XXX.minecraft.util.CrudeIncrementalIntIdentityHashBiMap
- XXX.minecraft.util.Crypt
+ XXX.minecraft.util.Crypt$ByteArrayToKeyFunction
- XXX.minecraft.util.Crypt$SaltSignaturePair
+ XXX.minecraft.util.Crypt$SaltSupplier
- XXX.minecraft.util.CryptException
+ XXX.minecraft.util.CsvOutput
- XXX.minecraft.util.CsvOutput$Builder
+ XXX.minecraft.util.CubicSampler
- XXX.minecraft.util.CubicSampler$Vec3Fetcher
+ XXX.minecraft.util.CubicSpline
- XXX.minecraft.util.CubicSpline$1Point
+ XXX.minecraft.util.CubicSpline$Builder
- XXX.minecraft.util.CubicSpline$Constant
+ XXX.minecraft.util.CubicSpline$CoordinateVisitor
- XXX.minecraft.util.CubicSpline$Multipoint
+ XXX.minecraft.util.DebugBuffer
- XXX.minecraft.util.DirectoryLock
+ XXX.minecraft.util.DirectoryLock$LockException
- XXX.minecraft.util.ExceptionCollector
+ XXX.minecraft.util.ExtraCodecs
- XXX.minecraft.util.ExtraCodecs$1
+ XXX.minecraft.util.ExtraCodecs$1ContextRetrievalCodec
- XXX.minecraft.util.ExtraCodecs$2
+ XXX.minecraft.util.ExtraCodecs$3
- XXX.minecraft.util.ExtraCodecs$4
+ XXX.minecraft.util.ExtraCodecs$EitherCodec
- XXX.minecraft.util.ExtraCodecs$LazyInitializedCodec
+ XXX.minecraft.util.ExtraCodecs$TagOrElementLocation
- XXX.minecraft.util.ExtraCodecs$XorCodec
+ XXX.minecraft.util.FastBufferedInputStream
- XXX.minecraft.util.FastColor
+ XXX.minecraft.util.FastColor$ABGR32
- XXX.minecraft.util.FastColor$ARGB32
+ XXX.minecraft.util.FileZipper
- XXX.minecraft.util.FormattedCharSequence
+ XXX.minecraft.util.FormattedCharSink
- XXX.minecraft.util.FrameTimer
+ XXX.minecraft.util.FutureChain
- XXX.minecraft.util.Graph
+ XXX.minecraft.util.GsonHelper
- XXX.minecraft.util.HttpUtil
+ XXX.minecraft.util.InclusiveRange
- XXX.minecraft.util.KeyDispatchDataCodec
+ XXX.minecraft.util.LazyLoadedValue
- XXX.minecraft.util.LinearCongruentialGenerator
+ XXX.minecraft.util.LowerCaseEnumTypeAdapterFactory
- XXX.minecraft.util.LowerCaseEnumTypeAdapterFactory$1
+ XXX.minecraft.util.MemoryReserve
- XXX.minecraft.util.ModCheck
+ XXX.minecraft.util.ModCheck$Confidence
- XXX.minecraft.util.Mth
+ XXX.minecraft.util.NativeModuleLister
- XXX.minecraft.util.NativeModuleLister$NativeModuleInfo
+ XXX.minecraft.util.NativeModuleLister$NativeModuleVersion
- XXX.minecraft.util.OptionEnum
+ XXX.minecraft.util.package-info
+ XXX.minecraft.util.ParticleUtils
- XXX.minecraft.util.ProgressListener
+ XXX.minecraft.util.RandomSource
- XXX.minecraft.util.ResourceLocationPattern
+ XXX.minecraft.util.RgbTxt
+ XXX.minecraft.util.SegmentedAnglePrecision
- XXX.minecraft.util.SignatureUpdater
+ XXX.minecraft.util.SignatureUpdater$Output
- XXX.minecraft.util.SignatureValidator
+ XXX.minecraft.util.Signer
- XXX.minecraft.util.SimpleBitStorage
+ XXX.minecraft.util.SimpleBitStorage$InitializationException
- XXX.minecraft.util.SingleKeyCache
+ XXX.minecraft.util.SmoothDouble
- XXX.minecraft.util.SortedArraySet
+ XXX.minecraft.util.SortedArraySet$ArrayIterator
- XXX.minecraft.util.SpawnUtil
+ XXX.minecraft.util.SpawnUtil$Strategy
- XXX.minecraft.util.StringDecomposer
+ XXX.minecraft.util.StringRepresentable
- XXX.minecraft.util.StringRepresentable$1
+ XXX.minecraft.util.StringRepresentable$EnumCodec
- XXX.minecraft.util.StringUtil
+ XXX.minecraft.util.TaskChainer
- XXX.minecraft.util.TaskChainer$DelayedTask
+ XXX.minecraft.util.ThreadingDetector
- XXX.minecraft.util.TimeSource
+ XXX.minecraft.util.TimeSource$NanoTimeSource
- XXX.minecraft.util.TimeUtil
+ XXX.minecraft.util.ToFloatFunction
- XXX.minecraft.util.ToFloatFunction$1
+ XXX.minecraft.util.ToFloatFunction$2
- XXX.minecraft.util.Tuple
+ XXX.minecraft.util.Unit
- XXX.minecraft.util.VisibleForDebug
+ XXX.minecraft.util.ZeroBitStorage
+ XXX.minecraft.voting.VoteCommand$1
+ XXX.minecraft.world.package-info
- XXX.models.blockstates.BlockStateGenerator
+ XXX.models.blockstates.Condition
- XXX.models.blockstates.Condition$CompositeCondition
+ XXX.models.blockstates.Condition$Operation
- XXX.models.blockstates.Condition$TerminalCondition
+ XXX.models.blockstates.MultiPartGenerator
- XXX.models.blockstates.MultiPartGenerator$ConditionalEntry
+ XXX.models.blockstates.MultiPartGenerator$Entry
- XXX.models.blockstates.MultiVariantGenerator
- XXX.models.blockstates.package-info
+ XXX.models.blockstates.PropertyDispatch
- XXX.models.blockstates.PropertyDispatch$C1
+ XXX.models.blockstates.PropertyDispatch$C2
- XXX.models.blockstates.PropertyDispatch$C3
+ XXX.models.blockstates.PropertyDispatch$C4
- XXX.models.blockstates.PropertyDispatch$C5
+ XXX.models.blockstates.PropertyDispatch$PentaFunction
- XXX.models.blockstates.PropertyDispatch$QuadFunction
+ XXX.models.blockstates.PropertyDispatch$TriFunction
- XXX.models.blockstates.Selector
+ XXX.models.blockstates.Variant
- XXX.models.blockstates.VariantProperties
+ XXX.models.blockstates.VariantProperties$Rotation
- XXX.models.blockstates.VariantProperty
+ XXX.models.blockstates.VariantProperty$Value
+ XXX.models.model.DelegatedModel
- XXX.models.model.ModelLocationUtils
+ XXX.models.model.ModelTemplate
- XXX.models.model.ModelTemplate$JsonFactory
+ XXX.models.model.ModelTemplates
- XXX.models.model.package-info
- XXX.models.model.TexturedModel
+ XXX.models.model.TexturedModel$Provider
- XXX.models.model.TextureMapping
+ XXX.models.model.TextureSlot
- XXX.monitoring.jmx.MinecraftServerStatistics
+ XXX.monitoring.jmx.MinecraftServerStatistics$AttributeDescription
- XXX.monitoring.jmx.package-info
+ XXX.monster.hoglin.Hoglin
- XXX.monster.hoglin.HoglinAi
+ XXX.monster.hoglin.HoglinBase
- XXX.monster.hoglin.package-info
- XXX.monster.piglin.AbstractPiglin
- XXX.monster.piglin.package-info
+ XXX.monster.piglin.Piglin
- XXX.monster.piglin.PiglinAi
+ XXX.monster.piglin.PiglinArmPose
- XXX.monster.piglin.PiglinBrute
+ XXX.monster.piglin.PiglinBruteAi
- XXX.monster.piglin.RememberIfHoglinWasKilled
+ XXX.monster.piglin.StartAdmiringItemIfSeen
- XXX.monster.piglin.StartHuntingHoglin
+ XXX.monster.piglin.StopAdmiringIfItemTooFarAway
- XXX.monster.piglin.StopAdmiringIfTiredOfTryingToReachItem
+ XXX.monster.piglin.StopHoldingItemIfNoLongerAdmiring
+ XXX.monster.warden.AngerLevel
- XXX.monster.warden.AngerManagement
+ XXX.monster.warden.AngerManagement$1
- XXX.monster.warden.AngerManagement$Sorter
+ XXX.monster.warden.package-info
+ XXX.monster.warden.Warden
- XXX.monster.warden.Warden$1
+ XXX.monster.warden.Warden$1$1
- XXX.monster.warden.Warden$2
+ XXX.monster.warden.WardenAi
- XXX.monster.warden.WardenSpawnTracker
+ XXX.packs.linkfs.DummyFileAttributes
- XXX.packs.linkfs.LinkFileSystem
+ XXX.packs.linkfs.LinkFileSystem$Builder
- XXX.packs.linkfs.LinkFileSystem$DirectoryEntry
- XXX.packs.linkfs.LinkFSFileStore
+ XXX.packs.linkfs.LinkFSPath
- XXX.packs.linkfs.LinkFSPath$1
+ XXX.packs.linkfs.LinkFSPath$2
- XXX.packs.linkfs.LinkFSPath$3
+ XXX.packs.linkfs.LinkFSProvider
- XXX.packs.linkfs.LinkFSProvider$1
+ XXX.packs.linkfs.LinkFSProvider$2
- XXX.packs.linkfs.package-info
+ XXX.packs.linkfs.PathContents
- XXX.packs.linkfs.PathContents$1
+ XXX.packs.linkfs.PathContents$2
- XXX.packs.linkfs.PathContents$DirectoryContents
+ XXX.packs.linkfs.PathContents$FileContents
+ XXX.packs.metadata.MetadataSectionSerializer
- XXX.packs.metadata.MetadataSectionType
+ XXX.packs.metadata.MetadataSectionType$1
+ XXX.packs.metadata.package-info
+ XXX.packs.repository.BuiltInPackSource
- XXX.packs.repository.FolderRepositorySource
+ XXX.packs.repository.Pack
- XXX.packs.repository.Pack$Info
+ XXX.packs.repository.Pack$Position
- XXX.packs.repository.Pack$ResourcesSupplier
+ XXX.packs.repository.package-info
+ XXX.packs.repository.PackCompatibility
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
+ XXX.packs.resources.ResourceProvider
- XXX.packs.resources.SimpleJsonResourceReloadListener
+ XXX.packs.resources.SimplePreparableReloadListener
- XXX.packs.resources.SimpleReloadInstance
+ XXX.packs.resources.SimpleReloadInstance$1
- XXX.packs.resources.SimpleReloadInstance$StateFactory
- XXX.phys.shapes.ArrayVoxelShape
+ XXX.phys.shapes.ArrayVoxelShape$1
- XXX.phys.shapes.BitSetDiscreteVoxelShape
+ XXX.phys.shapes.BooleanOp
- XXX.phys.shapes.CollisionContext
+ XXX.phys.shapes.CubePointRange
- XXX.phys.shapes.CubeVoxelShape
+ XXX.phys.shapes.DiscreteCubeMerger
- XXX.phys.shapes.DiscreteVoxelShape
+ XXX.phys.shapes.DiscreteVoxelShape$IntFaceConsumer
- XXX.phys.shapes.DiscreteVoxelShape$IntLineConsumer
+ XXX.phys.shapes.EntityCollisionContext
- XXX.phys.shapes.EntityCollisionContext$1
+ XXX.phys.shapes.IdenticalMerger
- XXX.phys.shapes.IndexMerger
+ XXX.phys.shapes.IndexMerger$IndexConsumer
- XXX.phys.shapes.IndirectMerger
+ XXX.phys.shapes.NonOverlappingMerger
- XXX.phys.shapes.OffsetDoubleList
- XXX.phys.shapes.package-info
+ XXX.phys.shapes.Shapes
- XXX.phys.shapes.Shapes$DoubleLineConsumer
+ XXX.phys.shapes.SliceShape
- XXX.phys.shapes.SubShape
+ XXX.phys.shapes.VoxelShape
+ XXX.profiling.jfr.Environment
- XXX.profiling.jfr.JfrProfiler
+ XXX.profiling.jfr.JfrProfiler$1
- XXX.profiling.jfr.JvmProfiler
+ XXX.profiling.jfr.JvmProfiler$NoOpProfiler
+ XXX.profiling.jfr.package-info
- XXX.profiling.jfr.Percentiles
+ XXX.profiling.jfr.SummaryReporter
- XXX.profiling.metrics.MetricCategory
+ XXX.profiling.metrics.MetricSampler
- XXX.profiling.metrics.MetricSampler$MetricSamplerBuilder
+ XXX.profiling.metrics.MetricSampler$SamplerResult
- XXX.profiling.metrics.MetricSampler$ThresholdTest
+ XXX.profiling.metrics.MetricSampler$ValueIncreasedByPercentage
- XXX.profiling.metrics.MetricsRegistry
+ XXX.profiling.metrics.MetricsRegistry$AggregatedMetricSampler
- XXX.profiling.metrics.MetricsSamplerProvider
- XXX.profiling.metrics.package-info
+ XXX.profiling.metrics.ProfilerMeasured
+ XXX.protocol.game.ClientboundBundlePacket
- XXX.protocol.game.ClientboundChangeDifficultyPacket
+ XXX.protocol.game.ClientboundChunksBiomesPacket
- XXX.protocol.game.ClientboundChunksBiomesPacket$ChunkBiomeData
+ XXX.protocol.game.ClientboundClearTitlesPacket
+ XXX.protocol.game.ClientboundCommandsPacket
- XXX.protocol.game.ClientboundCommandsPacket$ArgumentNodeStub
+ XXX.protocol.game.ClientboundCommandsPacket$Entry
- XXX.protocol.game.ClientboundCommandsPacket$LiteralNodeStub
+ XXX.protocol.game.ClientboundCommandsPacket$NodeResolver
- XXX.protocol.game.ClientboundCommandsPacket$NodeStub
- XXX.protocol.game.ClientboundCommandSuggestionsPacket
+ XXX.protocol.game.ClientboundContainerClosePacket
- XXX.protocol.game.ClientboundContainerSetContentPacket
+ XXX.protocol.game.ClientboundContainerSetDataPacket
- XXX.protocol.game.ClientboundContainerSetSlotPacket
+ XXX.protocol.game.ClientboundCooldownPacket
- XXX.protocol.game.ClientboundCustomChatCompletionsPacket
+ XXX.protocol.game.ClientboundCustomChatCompletionsPacket$Action
- XXX.protocol.game.ClientboundCustomPayloadPacket
+ XXX.protocol.game.ClientboundDamageEventPacket
- XXX.protocol.game.ClientboundDeleteChatPacket
+ XXX.protocol.game.ClientboundDisconnectPacket
- XXX.protocol.game.ClientboundDisguisedChatPacket
+ XXX.protocol.game.ClientboundEntityEventPacket
- XXX.protocol.game.ClientboundExplodePacket
+ XXX.protocol.game.ClientboundForgetLevelChunkPacket
- XXX.protocol.game.ClientboundGameEventPacket
+ XXX.protocol.game.ClientboundGameEventPacket$Type
- XXX.protocol.game.ClientboundHorseScreenOpenPacket
+ XXX.protocol.game.ClientboundHurtAnimationPacket
- XXX.protocol.game.ClientboundInitializeBorderPacket
+ XXX.protocol.game.ClientboundKeepAlivePacket
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
+ XXX.protocol.game.ClientboundMoveVehiclePacket
- XXX.protocol.game.ClientboundOpenBookPacket
+ XXX.protocol.game.ClientboundOpenScreenPacket
- XXX.protocol.game.ClientboundOpenSignEditorPacket
+ XXX.protocol.game.ClientboundPingPacket
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
+ XXX.protocol.game.ClientboundRecipePacket
- XXX.protocol.game.ClientboundRecipePacket$State
+ XXX.protocol.game.ClientboundRemoveEntitiesPacket
- XXX.protocol.game.ClientboundRemoveMobEffectPacket
+ XXX.protocol.game.ClientboundResourcePackPacket
- XXX.protocol.game.ClientboundRespawnPacket
+ XXX.protocol.game.ClientboundRotateHeadPacket
+ XXX.protocol.game.ClientboundVoteFinishPacket
+ XXX.protocol.game.ClientboundVoteStartPacket
+ XXX.protocol.game.ServerboundCustomPayloadPacket
- XXX.protocol.game.ServerboundEditBookPacket
+ XXX.protocol.game.ServerboundEntityTagQuery
- XXX.protocol.game.ServerboundInteractPacket
+ XXX.protocol.game.ServerboundInteractPacket$1
- XXX.protocol.game.ServerboundInteractPacket$Action
+ XXX.protocol.game.ServerboundInteractPacket$ActionType
- XXX.protocol.game.ServerboundInteractPacket$Handler
+ XXX.protocol.game.ServerboundInteractPacket$InteractionAction
- XXX.protocol.game.ServerboundInteractPacket$InteractionAtLocationAction
+ XXX.protocol.game.ServerboundJigsawGeneratePacket
- XXX.protocol.game.ServerboundKeepAlivePacket
+ XXX.protocol.game.ServerboundLockDifficultyPacket
- XXX.protocol.game.ServerboundMovePlayerPacket
+ XXX.protocol.game.ServerboundMovePlayerPacket$Pos
- XXX.protocol.game.ServerboundMovePlayerPacket$PosRot
+ XXX.protocol.game.ServerboundMovePlayerPacket$Rot
- XXX.protocol.game.ServerboundMovePlayerPacket$StatusOnly
+ XXX.protocol.game.ServerboundMoveVehiclePacket
- XXX.protocol.game.ServerboundPaddleBoatPacket
+ XXX.protocol.game.ServerboundPickItemPacket
- XXX.protocol.game.ServerboundPlaceRecipePacket
+ XXX.protocol.game.ServerboundPlayerAbilitiesPacket
- XXX.protocol.game.ServerboundPlayerActionPacket
+ XXX.protocol.game.ServerboundPlayerActionPacket$Action
- XXX.protocol.game.ServerboundPlayerCommandPacket
+ XXX.protocol.game.ServerboundPlayerCommandPacket$Action
- XXX.protocol.game.ServerboundPlayerInputPacket
+ XXX.protocol.game.ServerboundPongPacket
- XXX.protocol.game.ServerboundRecipeBookChangeSettingsPacket
+ XXX.protocol.game.ServerboundRecipeBookSeenRecipePacket
- XXX.protocol.game.ServerboundRenameItemPacket
+ XXX.protocol.game.ServerboundResourcePackPacket
- XXX.protocol.game.ServerboundResourcePackPacket$Action
+ XXX.protocol.game.ServerboundSeenAdvancementsPacket
- XXX.protocol.game.ServerboundSeenAdvancementsPacket$Action
+ XXX.protocol.game.ServerboundSelectTradePacket
- XXX.protocol.game.ServerboundSetBeaconPacket
+ XXX.protocol.game.ServerboundSetCarriedItemPacket
- XXX.protocol.game.ServerboundSetCommandBlockPacket
+ XXX.protocol.game.ServerboundSetCommandMinecartPacket
- XXX.protocol.game.ServerboundSetCreativeModeSlotPacket
+ XXX.protocol.game.ServerboundSetJigsawBlockPacket
- XXX.protocol.game.ServerboundSetStructureBlockPacket
+ XXX.protocol.game.ServerboundSignUpdatePacket
- XXX.protocol.game.ServerboundSwingPacket
+ XXX.protocol.game.ServerboundTeleportToEntityPacket
- XXX.protocol.game.ServerboundUseItemOnPacket
+ XXX.protocol.game.ServerboundUseItemPacket
- XXX.providers.nbt.ContextNbtProvider
+ XXX.providers.nbt.ContextNbtProvider$1
- XXX.providers.nbt.ContextNbtProvider$2
+ XXX.providers.nbt.ContextNbtProvider$Getter
- XXX.providers.nbt.ContextNbtProvider$InlineSerializer
+ XXX.providers.nbt.ContextNbtProvider$Serializer
- XXX.providers.nbt.LootNbtProviderType
+ XXX.providers.nbt.NbtProvider
- XXX.providers.nbt.NbtProviders
+ XXX.providers.nbt.package-info
+ XXX.providers.nbt.StorageNbtProvider
- XXX.providers.nbt.StorageNbtProvider$Serializer
- XXX.providers.number.BinomialDistributionGenerator
+ XXX.providers.number.BinomialDistributionGenerator$Serializer
- XXX.providers.number.ConstantValue
+ XXX.providers.number.ConstantValue$InlineSerializer
- XXX.providers.number.ConstantValue$Serializer
+ XXX.providers.number.LootNumberProviderType
- XXX.providers.number.NumberProvider
+ XXX.providers.number.NumberProviders
- XXX.providers.number.package-info
- XXX.providers.number.ScoreboardValue
+ XXX.providers.number.ScoreboardValue$Serializer
- XXX.providers.number.UniformGenerator
+ XXX.providers.number.UniformGenerator$Serializer
+ XXX.providers.score.ContextScoreboardNameProvider
- XXX.providers.score.ContextScoreboardNameProvider$InlineSerializer
+ XXX.providers.score.ContextScoreboardNameProvider$Serializer
- XXX.providers.score.FixedScoreboardNameProvider
+ XXX.providers.score.FixedScoreboardNameProvider$Serializer
- XXX.providers.score.LootScoreProviderType
+ XXX.providers.score.package-info
+ XXX.providers.score.ScoreboardNameProvider
- XXX.providers.score.ScoreboardNameProviders
+ XXX.rcon.thread.GenericThread
- XXX.rcon.thread.package-info
- XXX.rcon.thread.QueryThreadGs4
+ XXX.rcon.thread.QueryThreadGs4$RequestChallenge
- XXX.rcon.thread.RconClient
+ XXX.rcon.thread.RconThread
+ XXX.recipes.packs.BundleRecipeProvider
+ XXX.recipes.packs.package-info
- XXX.recipes.packs.VanillaRecipeProvider
+ XXX.rule.blockentity.AppendLoot
- XXX.rule.blockentity.AppendStatic
+ XXX.rule.blockentity.Clear
+ XXX.rule.blockentity.package-info
- XXX.rule.blockentity.Passthrough
+ XXX.rule.blockentity.RuleBlockEntityModifier
- XXX.rule.blockentity.RuleBlockEntityModifierType
+ XXX.rules.actual.BinaryGameRuleRule
+ XXX.rules.actual.BiomeColorRule
+ XXX.rules.actual.BlockFlammabilityRule$Flammability
+ XXX.rules.actual.BlockModelReplacementRule
+ XXX.rules.actual.BlockModelReplacementRule$Replacements
+ XXX.rules.actual.CaepType
+ XXX.rules.actual.CodepointReplaceRule
+ XXX.rules.actual.CodepointStyleRule$CodepointChange
+ XXX.rules.actual.CopySkinRule
+ XXX.rules.actual.DayLengthRule
+ XXX.rules.actual.DoubleOrHalfItemMapRule
+ XXX.rules.actual.FlailingLevel
+ XXX.rules.actual.FootprintRule
+ XXX.rules.actual.GiveEffectRule$MobEffectEntry
+ XXX.rules.actual.Goldifier$1
+ XXX.rules.actual.IntegerGameRuleRule$RuleRuleChange
+ XXX.rules.actual.ItemEntityDespawn
+ XXX.rules.actual.ItemGiveRule$GiveItemRule
+ XXX.rules.actual.ItemReplacementRule
+ XXX.rules.actual.LightEngineMode
+ XXX.rules.actual.MoonRule
+ XXX.rules.actual.NaturalSpawnReplaceRule
+ XXX.rules.actual.package-info
+ XXX.rules.actual.ParentTrapRule
+ XXX.rules.actual.PlayerEntry
+ XXX.rules.actual.RecipeEnableRule
+ XXX.rules.actual.ReplaceItemsRule
+ XXX.rules.actual.ReplaceItemsRule$ReplaceRuleChange
+ XXX.rules.actual.SoundEventReplacementRule
+ XXX.rules.actual.TheJokeRule$1
+ XXX.rules.actual.ThreadedAnvilChunkStorage$1
+ XXX.rules.actual.TransformEntityRule
+ XXX.rules.actual.TransformScaleRule
+ XXX.rules.actual.VehicleCollisionRule
+ XXX.rules.actual.WeatherOption
+ XXX.saveddata.maps.MapBanner
- XXX.saveddata.maps.MapBanner$1
+ XXX.saveddata.maps.MapDecoration
- XXX.saveddata.maps.MapDecoration$Type
+ XXX.saveddata.maps.MapFrame
- XXX.saveddata.maps.MapIndex
+ XXX.saveddata.maps.MapItemSavedData
- XXX.saveddata.maps.MapItemSavedData$HoldingPlayer
+ XXX.saveddata.maps.MapItemSavedData$MapPatch
- XXX.saveddata.maps.package-info
+ XXX.scores.criteria.ObjectiveCriteria
- XXX.scores.criteria.ObjectiveCriteria$RenderType
+ XXX.scores.criteria.package-info
+ XXX.server.level.package-info
+ XXX.server.level.ServerLevel$1
- XXX.server.level.ServerLevel$EntityCallbacks
+ XXX.server.level.ServerPlayer
- XXX.server.level.ServerPlayer$1
+ XXX.server.level.ServerPlayer$2
- XXX.server.level.ServerPlayerGameMode
+ XXX.server.level.ThreadedLevelLightEngine
- XXX.server.level.ThreadedLevelLightEngine$TaskType
+ XXX.server.level.Ticket
- XXX.server.level.TicketType
+ XXX.server.level.TickingTracker
- XXX.server.level.WorldGenRegion
- XXX.server.network.FilteredText
+ XXX.server.network.LegacyQueryHandler
- XXX.server.network.MemoryServerHandshakePacketListenerImpl
+ XXX.server.network.package-info
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
+ XXX.server.network.TextFilter
- XXX.server.network.TextFilter$1
+ XXX.server.network.TextFilterClient
- XXX.server.network.TextFilterClient$IgnoreStrategy
+ XXX.server.network.TextFilterClient$JoinOrLeaveEncoder
- XXX.server.network.TextFilterClient$MessageEncoder
+ XXX.server.network.TextFilterClient$PlayerContext
- XXX.server.network.TextFilterClient$RequestFailedException
+ XXX.server.packs.AbstractPackResources
- XXX.server.packs.BuiltInMetadata
+ XXX.server.packs.FeatureFlagsMetadataSection
- XXX.server.packs.FilePackResources
- XXX.server.packs.package-info
+ XXX.server.packs.PackResources
- XXX.server.packs.PackResources$ResourceOutput
+ XXX.server.packs.PackType
- XXX.server.packs.PathPackResources
+ XXX.server.packs.VanillaPackResources
- XXX.server.packs.VanillaPackResourcesBuilder
- XXX.server.players.BanListEntry
+ XXX.server.players.GameProfileCache
- XXX.server.players.GameProfileCache$1
+ XXX.server.players.GameProfileCache$GameProfileInfo
- XXX.server.players.IpBanList
+ XXX.server.players.IpBanListEntry
- XXX.server.players.OldUsersConverter
+ XXX.server.players.OldUsersConverter$1
- XXX.server.players.OldUsersConverter$2
+ XXX.server.players.OldUsersConverter$3
- XXX.server.players.OldUsersConverter$4
+ XXX.server.players.OldUsersConverter$5
- XXX.server.players.OldUsersConverter$ConversionError
- XXX.server.players.package-info
+ XXX.server.players.PlayerList
- XXX.server.players.PlayerList$1
+ XXX.server.players.ServerOpList
- XXX.server.players.ServerOpListEntry
+ XXX.server.players.SleepStatus
- XXX.server.players.StoredUserEntry
+ XXX.server.players.StoredUserList
- XXX.server.players.UserBanList
+ XXX.server.players.UserBanListEntry
- XXX.server.players.UserWhiteList
+ XXX.server.players.UserWhiteListEntry
+ XXX.server.rcon.NetworkDataOutputStream
- XXX.server.rcon.package-info
- XXX.server.rcon.PktUtils
+ XXX.server.rcon.RconConsoleSource
- XXX.state.pattern.BlockInWorld
+ XXX.state.pattern.BlockPattern
- XXX.state.pattern.BlockPattern$BlockCacheLoader
+ XXX.state.pattern.BlockPattern$BlockPatternMatch
- XXX.state.pattern.BlockPatternBuilder
+ XXX.state.pattern.package-info
+ XXX.state.predicate.BlockMaterialPredicate$1
- XXX.state.predicate.BlockPredicate
+ XXX.state.predicate.BlockStatePredicate
- XXX.state.predicate.package-info
+ XXX.state.properties.AttachFace
- XXX.state.properties.BambooLeaves
+ XXX.state.properties.BedPart
- XXX.state.properties.BellAttachType
+ XXX.state.properties.BlockSetType
- XXX.state.properties.BlockStateProperties
+ XXX.state.properties.BooleanProperty
- XXX.state.properties.ChestType
+ XXX.state.properties.ChestType$1
- XXX.state.properties.ComparatorMode
+ XXX.state.properties.DirectionProperty
- XXX.state.properties.DoorHingeSide
+ XXX.state.properties.DoubleBlockHalf
- XXX.state.properties.DripstoneThickness
+ XXX.state.properties.EnumProperty
- XXX.state.properties.Half
+ XXX.state.properties.IntegerProperty
- XXX.state.properties.NoteBlockInstrument
+ XXX.state.properties.NoteBlockInstrument$Type
+ XXX.state.properties.package-info
- XXX.state.properties.PistonType
+ XXX.state.properties.Property
- XXX.state.properties.Property$Value
+ XXX.state.properties.RailShape
- XXX.state.properties.RedstoneSide
+ XXX.state.properties.RotationSegment
- XXX.state.properties.SculkSensorPhase
+ XXX.state.properties.SlabType
- XXX.state.properties.StairsShape
+ XXX.state.properties.StructureMode
- XXX.state.properties.Tilt
+ XXX.state.properties.WallSide
- XXX.state.properties.WoodType
+ XXX.storage.loot.BuiltInLootTables
- XXX.storage.loot.Deserializers
+ XXX.storage.loot.GsonAdapterFactory
- XXX.storage.loot.GsonAdapterFactory$Builder
+ XXX.storage.loot.GsonAdapterFactory$InlineSerializer
- XXX.storage.loot.GsonAdapterFactory$JsonAdapter
+ XXX.storage.loot.IntRange
- XXX.storage.loot.IntRange$IntChecker
+ XXX.storage.loot.IntRange$IntLimiter
- XXX.storage.loot.IntRange$Serializer
+ XXX.storage.loot.ItemModifierManager
+ XXX.storage.loot.LootContext
- XXX.storage.loot.LootContext$Builder
+ XXX.storage.loot.LootContext$DynamicDrop
- XXX.storage.loot.LootContext$EntityTarget
+ XXX.storage.loot.LootContext$EntityTarget$Serializer
- XXX.storage.loot.LootContext$VisitedEntry
- XXX.storage.loot.LootDataId
- XXX.storage.loot.LootDataManager$1
- XXX.storage.loot.LootDataManager$FunctionSequence
- XXX.storage.loot.LootDataType
+ XXX.storage.loot.LootTables
- XXX.storage.loot.package-info
+ XXX.storage.loot.PredicateManager$CompositePredicate
- XXX.storage.loot.Serializer
+ XXX.storage.loot.SerializerType
- XXX.storage.loot.ValidationContext
+ XXX.structure.pieces.package-info
+ XXX.structure.pieces.PieceGenerator
- XXX.structure.pieces.PieceGenerator$Context
+ XXX.structure.pieces.PieceGeneratorSupplier
- XXX.structure.pieces.PieceGeneratorSupplier$Context
+ XXX.structure.pieces.PiecesContainer
- XXX.structure.pieces.StructurePiecesBuilder
- XXX.structure.pieces.StructurePieceSerializationContext
+ XXX.structure.pieces.StructurePieceType
- XXX.structure.pieces.StructurePieceType$ContextlessType
+ XXX.structure.pieces.StructurePieceType$StructureTemplateType
- XXX.structure.placement.ConcentricRingsStructurePlacement
+ XXX.structure.placement.package-info
+ XXX.structure.placement.RandomSpreadStructurePlacement
- XXX.structure.placement.RandomSpreadType
+ XXX.structure.placement.RandomSpreadType$1
- XXX.structure.placement.StructurePlacement
+ XXX.structure.placement.StructurePlacement$ExclusionZone
- XXX.structure.placement.StructurePlacement$FrequencyReducer
+ XXX.structure.placement.StructurePlacement$FrequencyReductionMethod
- XXX.structure.placement.StructurePlacementType
- XXX.structure.pools.EmptyPoolElement
+ XXX.structure.pools.FeaturePoolElement
- XXX.structure.pools.JigsawJunction
+ XXX.structure.pools.JigsawPlacement
- XXX.structure.pools.JigsawPlacement$PieceState
+ XXX.structure.pools.JigsawPlacement$Placer
- XXX.structure.pools.LegacySinglePoolElement
+ XXX.structure.pools.ListPoolElement
+ XXX.structure.pools.package-info
- XXX.structure.pools.SinglePoolElement
+ XXX.structure.pools.StructurePoolElement
- XXX.structure.pools.StructurePoolElementType
+ XXX.structure.pools.StructureTemplatePool
- XXX.structure.pools.StructureTemplatePool$Projection
- XXX.structure.structures.BuriedTreasurePieces
+ XXX.structure.structures.BuriedTreasurePieces$BuriedTreasurePiece
- XXX.structure.structures.BuriedTreasureStructure
+ XXX.structure.structures.DesertPyramidPiece
- XXX.structure.structures.DesertPyramidStructure
+ XXX.structure.structures.EndCityPieces
- XXX.structure.structures.EndCityPieces$1
+ XXX.structure.structures.EndCityPieces$2
- XXX.structure.structures.EndCityPieces$3
+ XXX.structure.structures.EndCityPieces$4
- XXX.structure.structures.EndCityPieces$EndCityPiece
+ XXX.structure.structures.EndCityPieces$SectionGenerator
- XXX.structure.structures.EndCityStructure
+ XXX.structure.structures.IglooPieces
- XXX.structure.structures.IglooPieces$IglooPiece
+ XXX.structure.structures.IglooStructure
- XXX.structure.structures.JigsawStructure
+ XXX.structure.structures.JigsawStructure$1
- XXX.structure.structures.JungleTemplePiece
+ XXX.structure.structures.JungleTemplePiece$MossStoneSelector
- XXX.structure.structures.JungleTempleStructure
+ XXX.structure.structures.MineshaftPieces
- XXX.structure.structures.MineshaftPieces$1
+ XXX.structure.structures.MineshaftPieces$MineShaftCorridor
- XXX.structure.structures.MineshaftPieces$MineShaftCrossing
+ XXX.structure.structures.MineshaftPieces$MineShaftPiece
- XXX.structure.structures.MineshaftPieces$MineShaftRoom
+ XXX.structure.structures.MineshaftPieces$MineShaftStairs
- XXX.structure.structures.MineshaftStructure
+ XXX.structure.structures.MineshaftStructure$Type
- XXX.structure.structures.NetherFortressPieces
+ XXX.structure.structures.NetherFortressPieces$1
- XXX.structure.structures.NetherFortressPieces$BridgeCrossing
+ XXX.structure.structures.NetherFortressPieces$BridgeEndFiller
- XXX.structure.structures.NetherFortressPieces$BridgeStraight
+ XXX.structure.structures.NetherFortressPieces$CastleCorridorStairsPiece
- XXX.structure.structures.NetherFortressPieces$CastleCorridorTBalconyPiece
+ XXX.structure.structures.NetherFortressPieces$CastleEntrance
- XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorCrossingPiece
+ XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorLeftTurnPiece
- XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorPiece
+ XXX.structure.structures.NetherFortressPieces$CastleSmallCorridorRightTurnPiece
- XXX.structure.structures.NetherFortressPieces$CastleStalkRoom
+ XXX.structure.structures.NetherFortressPieces$MonsterThrone
- XXX.structure.structures.NetherFortressPieces$NetherBridgePiece
+ XXX.structure.structures.NetherFortressPieces$PieceWeight
- XXX.structure.structures.NetherFortressPieces$RoomCrossing
+ XXX.structure.structures.NetherFortressPieces$StairsRoom
- XXX.structure.structures.NetherFortressPieces$StartPiece
+ XXX.structure.structures.NetherFortressStructure
- XXX.structure.structures.NetherFossilPieces
+ XXX.structure.structures.NetherFossilPieces$NetherFossilPiece
- XXX.structure.structures.NetherFossilStructure
+ XXX.structure.structures.OceanMonumentPieces
- XXX.structure.structures.OceanMonumentPieces$1
+ XXX.structure.structures.OceanMonumentPieces$FitDoubleXRoom
- XXX.structure.structures.OceanMonumentPieces$FitDoubleXYRoom
+ XXX.structure.structures.OceanMonumentPieces$FitDoubleYRoom
- XXX.structure.structures.OceanMonumentPieces$FitDoubleYZRoom
+ XXX.structure.structures.OceanMonumentPieces$FitDoubleZRoom
- XXX.structure.structures.OceanMonumentPieces$FitSimpleRoom
+ XXX.structure.structures.OceanMonumentPieces$FitSimpleTopRoom
- XXX.structure.structures.OceanMonumentPieces$MonumentBuilding
+ XXX.structure.structures.OceanMonumentPieces$MonumentRoomFitter
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentCoreRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleXRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleXYRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleYRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleYZRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentDoubleZRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentEntryRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentPenthouse
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentPiece
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentSimpleRoom
- XXX.structure.structures.OceanMonumentPieces$OceanMonumentSimpleTopRoom
+ XXX.structure.structures.OceanMonumentPieces$OceanMonumentWingRoom
- XXX.structure.structures.OceanMonumentPieces$RoomDefinition
+ XXX.structure.structures.OceanMonumentStructure
- XXX.structure.structures.OceanRuinPieces
+ XXX.structure.structures.OceanRuinPieces$1
- XXX.structure.structures.OceanRuinPieces$OceanRuinPiece
+ XXX.structure.structures.OceanRuinStructure
- XXX.structure.structures.OceanRuinStructure$Type
+ XXX.structure.structures.package-info
+ XXX.structure.structures.RuinedPortalPiece
- XXX.structure.structures.RuinedPortalPiece$Properties
+ XXX.structure.structures.RuinedPortalPiece$VerticalPlacement
- XXX.structure.structures.RuinedPortalStructure
+ XXX.structure.structures.RuinedPortalStructure$Setup
- XXX.structure.structures.ShipwreckPieces
+ XXX.structure.structures.ShipwreckPieces$ShipwreckPiece
- XXX.structure.structures.ShipwreckStructure
+ XXX.structure.structures.StrongholdPieces
- XXX.structure.structures.StrongholdPieces$1
+ XXX.structure.structures.StrongholdPieces$2
- XXX.structure.structures.StrongholdPieces$3
+ XXX.structure.structures.StrongholdPieces$ChestCorridor
- XXX.structure.structures.StrongholdPieces$FillerCorridor
+ XXX.structure.structures.StrongholdPieces$FiveCrossing
- XXX.structure.structures.StrongholdPieces$LeftTurn
+ XXX.structure.structures.StrongholdPieces$Library
- XXX.structure.structures.StrongholdPieces$PieceWeight
+ XXX.structure.structures.StrongholdPieces$PortalRoom
- XXX.structure.structures.StrongholdPieces$PrisonHall
+ XXX.structure.structures.StrongholdPieces$RightTurn
- XXX.structure.structures.StrongholdPieces$RoomCrossing
+ XXX.structure.structures.StrongholdPieces$SmoothStoneSelector
- XXX.structure.structures.StrongholdPieces$StairsDown
+ XXX.structure.structures.StrongholdPieces$StartPiece
- XXX.structure.structures.StrongholdPieces$Straight
+ XXX.structure.structures.StrongholdPieces$StraightStairsDown
- XXX.structure.structures.StrongholdPieces$StrongholdPiece
+ XXX.structure.structures.StrongholdPieces$StrongholdPiece$SmallDoorType
- XXX.structure.structures.StrongholdPieces$Turn
+ XXX.structure.structures.StrongholdStructure
- XXX.structure.structures.SwampHutPiece
+ XXX.structure.structures.SwampHutStructure
- XXX.structure.structures.WoodlandMansionPieces
+ XXX.structure.structures.WoodlandMansionPieces$FirstFloorRoomCollection
- XXX.structure.structures.WoodlandMansionPieces$FloorRoomCollection
+ XXX.structure.structures.WoodlandMansionPieces$MansionGrid
- XXX.structure.structures.WoodlandMansionPieces$MansionPiecePlacer
+ XXX.structure.structures.WoodlandMansionPieces$PlacementData
- XXX.structure.structures.WoodlandMansionPieces$SecondFloorRoomCollection
+ XXX.structure.structures.WoodlandMansionPieces$SimpleGrid
- XXX.structure.structures.WoodlandMansionPieces$ThirdFloorRoomCollection
+ XXX.structure.structures.WoodlandMansionPieces$WoodlandMansionPiece
- XXX.structure.structures.WoodlandMansionStructure
- XXX.structure.templatesystem.AlwaysTrueTest
+ XXX.structure.templatesystem.AxisAlignedLinearPosTest
- XXX.structure.templatesystem.BlackstoneReplaceProcessor
+ XXX.structure.templatesystem.BlockAgeProcessor
- XXX.structure.templatesystem.BlockIgnoreProcessor
+ XXX.structure.templatesystem.BlockMatchTest
- XXX.structure.templatesystem.BlockRotProcessor
+ XXX.structure.templatesystem.BlockStateMatchTest
- XXX.structure.templatesystem.CappedProcessor
+ XXX.structure.templatesystem.GravityProcessor
- XXX.structure.templatesystem.JigsawReplacementProcessor
+ XXX.structure.templatesystem.LavaSubmergedBlockProcessor
- XXX.structure.templatesystem.LinearPosTest
+ XXX.structure.templatesystem.NopProcessor
- XXX.structure.templatesystem.package-info
- XXX.structure.templatesystem.PosAlwaysTrueTest
+ XXX.structure.templatesystem.PosRuleTest
- XXX.structure.templatesystem.PosRuleTestType
+ XXX.structure.templatesystem.ProcessorRule
- XXX.structure.templatesystem.ProtectedBlockProcessor
+ XXX.structure.templatesystem.RandomBlockMatchTest
- XXX.structure.templatesystem.RandomBlockStateMatchTest
+ XXX.structure.templatesystem.RuleProcessor
- XXX.structure.templatesystem.RuleTest
+ XXX.structure.templatesystem.RuleTestType
- XXX.structure.templatesystem.StructurePlaceSettings
+ XXX.structure.templatesystem.StructureProcessor
- XXX.structure.templatesystem.StructureProcessorList
+ XXX.structure.templatesystem.StructureProcessorType
- XXX.structure.templatesystem.StructureTemplate
+ XXX.structure.templatesystem.StructureTemplate$1
- XXX.structure.templatesystem.StructureTemplate$Palette
+ XXX.structure.templatesystem.StructureTemplate$SimplePalette
- XXX.structure.templatesystem.StructureTemplate$StructureBlockInfo
+ XXX.structure.templatesystem.StructureTemplate$StructureEntityInfo
- XXX.structure.templatesystem.StructureTemplateManager
+ XXX.structure.templatesystem.StructureTemplateManager$InputStreamOpener
- XXX.structure.templatesystem.StructureTemplateManager$Source
+ XXX.structure.templatesystem.TagMatchTest
+ XXX.util.datafix.DataFixers
- XXX.util.datafix.DataFixers$1
+ XXX.util.datafix.DataFixers$2
- XXX.util.datafix.DataFixTypes
- XXX.util.datafix.PackedBitStorage
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
- XXX.util.profiling.ActiveProfiler
+ XXX.util.profiling.ActiveProfiler$PathEntry
- XXX.util.profiling.ContinuousProfiler
+ XXX.util.profiling.EmptyProfileResults
- XXX.util.profiling.FilledProfileResults
+ XXX.util.profiling.FilledProfileResults$1
- XXX.util.profiling.FilledProfileResults$CounterCollector
+ XXX.util.profiling.InactiveProfiler
- XXX.util.profiling.package-info
- XXX.util.profiling.ProfileCollector
+ XXX.util.profiling.ProfileResults
- XXX.util.profiling.ProfilerFiller
+ XXX.util.profiling.ProfilerFiller$1
- XXX.util.profiling.ProfilerPathEntry
+ XXX.util.profiling.ResultField
- XXX.util.profiling.SingleTickProfiler
+ XXX.util.random.package-info
+ XXX.util.random.SimpleWeightedRandomList
- XXX.util.random.SimpleWeightedRandomList$Builder
+ XXX.util.random.Weight
- XXX.util.random.WeightedEntry
+ XXX.util.random.WeightedEntry$IntrusiveBase
- XXX.util.random.WeightedEntry$Wrapper
+ XXX.util.random.WeightedRandom
- XXX.util.random.WeightedRandomList
- XXX.util.thread.BlockableEventLoop
+ XXX.util.thread.NamedThreadFactory
- XXX.util.thread.package-info
- XXX.util.thread.ProcessorHandle
+ XXX.util.thread.ProcessorHandle$1
- XXX.util.thread.ProcessorMailbox
+ XXX.util.thread.ReentrantBlockableEventLoop
- XXX.util.thread.StrictQueue
+ XXX.util.thread.StrictQueue$FixedPriorityQueue
- XXX.util.thread.StrictQueue$IntRunnable
+ XXX.util.thread.StrictQueue$QueueStrictQueue
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
+ XXX.util.worldupdate.package-info
- XXX.util.worldupdate.WorldUpgrader
+ XXX.village.poi.package-info
- XXX.village.poi.PoiManager
+ XXX.village.poi.PoiManager$DistanceTracker
- XXX.village.poi.PoiManager$Occupancy
+ XXX.village.poi.PoiRecord
- XXX.village.poi.PoiSection
+ XXX.village.poi.PoiType
- XXX.village.poi.PoiTypes
+ XXX.voting.rules.BooleanRule
+ XXX.voting.rules.CounterRule
+ XXX.voting.rules.CounterRule$CounterRuleChange
+ XXX.voting.rules.DoubleOrHalfMapRule
+ XXX.voting.rules.EnumRule
+ XXX.voting.rules.EnumRule$EnumRuleChange
+ XXX.voting.rules.FixedOrRandomKeyRule$1
+ XXX.voting.rules.MapRule
+ XXX.voting.rules.MapRule$MapRuleChange
+ XXX.voting.rules.OneShotRule$1
+ XXX.voting.rules.OneShotRule$Resettable
+ XXX.voting.rules.RandomNumberRule
+ XXX.voting.rules.RandomNumberRule$RandomFloat
+ XXX.voting.rules.RandomNumberRule$RandomNumberRuleChange
+ XXX.voting.rules.ResourceKeySetRule
+ XXX.voting.rules.ResourceKeySingleRule$1
+ XXX.voting.rules.Rule
+ XXX.voting.rules.RuleChange
+ XXX.voting.rules.RuleChange$Simple
+ XXX.voting.rules.Rules$1
+ XXX.voting.rules.Rules$11
+ XXX.voting.rules.Rules$13
+ XXX.voting.rules.Rules$15
+ XXX.voting.rules.Rules$17
+ XXX.voting.rules.Rules$19
+ XXX.voting.rules.Rules$20
+ XXX.voting.rules.Rules$22
+ XXX.voting.rules.Rules$24
+ XXX.voting.rules.Rules$26
+ XXX.voting.rules.Rules$28
+ XXX.voting.rules.Rules$3
+ XXX.voting.rules.Rules$31
+ XXX.voting.rules.Rules$33
+ XXX.voting.rules.Rules$35
+ XXX.voting.rules.Rules$37
+ XXX.voting.rules.Rules$39
+ XXX.voting.rules.Rules$40
+ XXX.voting.rules.Rules$42
+ XXX.voting.rules.Rules$5
+ XXX.voting.rules.Rules$7
+ XXX.voting.rules.Rules$9
+ XXX.voting.rules.SetRule$SetRuleChange
+ XXX.voting.rules.UniformIntRule$1
+ XXX.voting.rules.VotingCostRule
+ XXX.voting.rules.VotingCostRule$Change
+ XXX.voting.votes.ClientVote
+ XXX.voting.votes.CommonVoteData
+ XXX.voting.votes.FinishedVote$1
+ XXX.voting.votes.FinishedVote$UnpackOptions
+ XXX.voting.votes.OptionVoteStorage
+ XXX.voting.votes.ServerVote
+ XXX.voting.votes.ServerVote$Option
+ XXX.voting.votes.ServerVoteStorage
+ XXX.voting.votes.ServerVoteStorage$VoteResult
+ XXX.voting.votes.Voter
+ XXX.voting.votes.VoteResults
+ XXX.voting.votes.VoteResults$VoteCounts
+ XXX.voting.votes.VotingMaterial
+ XXX.voting.votes.VotingMaterial$2
+ XXX.voting.votes.VotingMaterial$CustomCost
+ XXX.voting.votes.VotingMaterial$Type$1
+ XXX.voting.votes.VotingMaterial$Type$3
+ XXX.voting.votes.VotingMaterial$Type$5
+ XXX.voting.votes.VotingMaterial$VotingResource
+ XXX.voting.votes.VotingMaterial$VotingResource$2
+ XXX.world.entity.Display$KeyFrame
- XXX.world.entity.Display$LinearFloatInterpolator
+ XXX.world.entity.Display$LinearIntInterpolator
+ XXX.world.entity.Display$StencilDisplay$StencilRenderState
+ XXX.world.entity.Entity$InPortal
- XXX.world.entity.Entity$MoveFunction
+ XXX.world.entity.Entity$MovementEmission
- XXX.world.entity.Entity$RemovalReason
+ XXX.world.entity.EntityDimensions
- XXX.world.entity.EntityEvent
+ XXX.world.entity.EntitySelector
- XXX.world.entity.EntitySelector$MobCanWearArmorEntitySelector
+ XXX.world.entity.EntityType
- XXX.world.entity.EntityType$1
+ XXX.world.entity.EntityType$Builder
- XXX.world.entity.EntityType$EntityFactory
+ XXX.world.entity.EquipmentSlot
- XXX.world.entity.EquipmentSlot$Type
+ XXX.world.entity.ExperienceOrb
- XXX.world.entity.FlyingMob
+ XXX.world.entity.GlowSquid
- XXX.world.entity.HasCustomInventoryScreen
+ XXX.world.entity.HumanoidArm
- XXX.world.entity.Interaction
+ XXX.world.entity.Interaction$PlayerAction
- XXX.world.entity.ItemBasedSteering
+ XXX.world.entity.ItemSteerable
- XXX.world.entity.LerpingModel
+ XXX.world.entity.LightningBolt
- XXX.world.entity.LivingEntity
+ XXX.world.entity.LivingEntity$1
- XXX.world.entity.LivingEntity$Fallsounds
+ XXX.world.entity.Marker
- XXX.world.entity.Mob
+ XXX.world.entity.Mob$1
- XXX.world.entity.MobCategory
+ XXX.world.entity.MobSpawnType
- XXX.world.entity.MobType
+ XXX.world.entity.MoverType
- XXX.world.entity.NeutralMob
+ XXX.world.entity.OwnableEntity
- XXX.world.entity.package-info
- XXX.world.entity.PathfinderMob
+ XXX.world.entity.PlayerRideable
- XXX.world.entity.PlayerRideableJumping
+ XXX.world.entity.Pose
- XXX.world.entity.PowerableMob
+ XXX.world.entity.RelativeMovement
- XXX.world.entity.ReputationEventHandler
+ XXX.world.entity.RiderShieldingMount
- XXX.world.entity.Saddleable
+ XXX.world.entity.Shearable
- XXX.world.entity.SlotAccess
+ XXX.world.entity.SlotAccess$1
- XXX.world.entity.SlotAccess$2
+ XXX.world.entity.SlotAccess$3
- XXX.world.entity.SpawnGroupData
+ XXX.world.entity.SpawnPlacements
- XXX.world.entity.SpawnPlacements$Data
+ XXX.world.entity.SpawnPlacements$SpawnPredicate
- XXX.world.entity.SpawnPlacements$Type
+ XXX.world.entity.TamableAnimal
- XXX.world.entity.Targeting
+ XXX.world.entity.TraceableEntity
- XXX.world.entity.VariantHolder
+ XXX.world.entity.WalkAnimationState
+ XXX.world.food.package-info
- XXX.world.inventory.AbstractContainerMenu
+ XXX.world.inventory.AbstractContainerMenu$1
- XXX.world.inventory.AbstractFurnaceMenu
+ XXX.world.inventory.AnvilMenu
- XXX.world.inventory.AnvilMenu$1
+ XXX.world.inventory.BeaconMenu
- XXX.world.inventory.BeaconMenu$1
+ XXX.world.inventory.BeaconMenu$PaymentSlot
- XXX.world.inventory.BlastFurnaceMenu
+ XXX.world.inventory.BrewingStandMenu
- XXX.world.inventory.BrewingStandMenu$FuelSlot
+ XXX.world.inventory.BrewingStandMenu$IngredientsSlot
- XXX.world.inventory.BrewingStandMenu$PotionSlot
+ XXX.world.inventory.CartographyTableMenu
- XXX.world.inventory.CartographyTableMenu$1
+ XXX.world.inventory.CartographyTableMenu$2
- XXX.world.inventory.CartographyTableMenu$3
+ XXX.world.inventory.CartographyTableMenu$4
- XXX.world.inventory.CartographyTableMenu$5
+ XXX.world.inventory.ChestMenu
- XXX.world.inventory.ClickAction
+ XXX.world.inventory.ClickType
- XXX.world.inventory.ContainerData
+ XXX.world.inventory.ContainerLevelAccess
- XXX.world.inventory.ContainerLevelAccess$1
+ XXX.world.inventory.ContainerLevelAccess$2
- XXX.world.inventory.ContainerListener
+ XXX.world.inventory.ContainerSynchronizer
- XXX.world.inventory.CraftingContainer
+ XXX.world.inventory.CraftingMenu
- XXX.world.inventory.DataSlot
+ XXX.world.inventory.DataSlot$1
- XXX.world.inventory.DataSlot$2
+ XXX.world.inventory.DataSlot$3
- XXX.world.inventory.DispenserMenu
+ XXX.world.inventory.EnchantmentMenu
- XXX.world.inventory.EnchantmentMenu$1
+ XXX.world.inventory.EnchantmentMenu$2
- XXX.world.inventory.EnchantmentMenu$3
+ XXX.world.inventory.FurnaceFuelSlot
- XXX.world.inventory.FurnaceMenu
+ XXX.world.inventory.FurnaceResultSlot
- XXX.world.inventory.GrindstoneMenu
+ XXX.world.inventory.GrindstoneMenu$1
- XXX.world.inventory.GrindstoneMenu$2
+ XXX.world.inventory.GrindstoneMenu$3
- XXX.world.inventory.GrindstoneMenu$4
+ XXX.world.inventory.HopperMenu
- XXX.world.inventory.HorseInventoryMenu
+ XXX.world.inventory.HorseInventoryMenu$1
- XXX.world.inventory.HorseInventoryMenu$2
+ XXX.world.inventory.InventoryMenu
- XXX.world.inventory.InventoryMenu$1
+ XXX.world.inventory.InventoryMenu$2
- XXX.world.inventory.ItemCombinerMenu
+ XXX.world.inventory.ItemCombinerMenu$1
- XXX.world.inventory.ItemCombinerMenu$2
+ XXX.world.inventory.ItemCombinerMenu$3
- XXX.world.inventory.ItemCombinerMenuSlotDefinition
+ XXX.world.inventory.ItemCombinerMenuSlotDefinition$Builder
- XXX.world.inventory.ItemCombinerMenuSlotDefinition$SlotDefinition
+ XXX.world.inventory.LecternMenu
- XXX.world.inventory.LecternMenu$1
+ XXX.world.inventory.LoomMenu
- XXX.world.inventory.LoomMenu$1
+ XXX.world.inventory.LoomMenu$2
- XXX.world.inventory.LoomMenu$3
+ XXX.world.inventory.LoomMenu$4
- XXX.world.inventory.LoomMenu$5
+ XXX.world.inventory.LoomMenu$6
- XXX.world.inventory.MenuConstructor
+ XXX.world.inventory.MenuType
- XXX.world.inventory.MenuType$MenuSupplier
+ XXX.world.inventory.MerchantContainer
- XXX.world.inventory.MerchantMenu
+ XXX.world.inventory.MerchantResultSlot
- XXX.world.inventory.package-info
- XXX.world.inventory.PlayerEnderChestContainer
+ XXX.world.inventory.RecipeBookMenu
- XXX.world.inventory.RecipeBookType
+ XXX.world.inventory.RecipeHolder
- XXX.world.inventory.ResultContainer
+ XXX.world.inventory.ResultSlot
- XXX.world.inventory.ShulkerBoxMenu
+ XXX.world.inventory.ShulkerBoxSlot
- XXX.world.inventory.SimpleContainerData
+ XXX.world.inventory.Slot
- XXX.world.inventory.SmithingMenu
+ XXX.world.inventory.SmokerMenu
- XXX.world.inventory.StackedContentsCompatible
+ XXX.world.inventory.StonecutterMenu
- XXX.world.inventory.StonecutterMenu$1
+ XXX.world.inventory.StonecutterMenu$2
- XXX.world.item.AdventureModeCheck
+ XXX.world.item.AirItem
- XXX.world.item.ArmorItem
+ XXX.world.item.ArmorItem$1
- XXX.world.item.ArmorItem$Type
+ XXX.world.item.ArmorMaterial
- XXX.world.item.ArmorMaterials
+ XXX.world.item.ArmorStandItem
- XXX.world.item.ArrowItem
+ XXX.world.item.AxeItem
- XXX.world.item.BannerItem
+ XXX.world.item.BannerPatternItem
- XXX.world.item.BedItem
+ XXX.world.item.BlockItem
- XXX.world.item.BoatItem
+ XXX.world.item.BoneMealItem
- XXX.world.item.BookItem
+ XXX.world.item.BottleItem
+ XXX.world.item.BottleOfVoidItem
- XXX.world.item.BowItem
+ XXX.world.item.BowlFoodItem
- XXX.world.item.BrushItem
+ XXX.world.item.BrushItem$1
- XXX.world.item.BrushItem$DustParticlesDelta
+ XXX.world.item.BucketItem
- XXX.world.item.BundleItem
+ XXX.world.item.ChorusFruitItem
- XXX.world.item.CompassItem
+ XXX.world.item.ComplexItem
- XXX.world.item.CreativeModeTab
+ XXX.world.item.CreativeModeTab$1
- XXX.world.item.CreativeModeTab$Builder
+ XXX.world.item.CreativeModeTab$DisplayItemsGenerator
- XXX.world.item.CreativeModeTab$ItemDisplayBuilder
+ XXX.world.item.CreativeModeTab$ItemDisplayParameters
- XXX.world.item.CreativeModeTab$Output
+ XXX.world.item.CreativeModeTab$Row
- XXX.world.item.CreativeModeTab$TabVisibility
+ XXX.world.item.CreativeModeTab$Type
- XXX.world.item.CreativeModeTabs
+ XXX.world.item.CrossbowItem
- XXX.world.item.DebugStickItem
+ XXX.world.item.DiggerItem
- XXX.world.item.DiscFragmentItem
+ XXX.world.item.DispensibleContainerItem
- XXX.world.item.DoubleHighBlockItem
+ XXX.world.item.DupeHackItem
+ XXX.world.item.EmeraldItem
- XXX.world.item.EmptyMapItem
+ XXX.world.item.EnchantedBookItem
- XXX.world.item.EnchantedGoldenAppleItem
+ XXX.world.item.EndCrystalItem
- XXX.world.item.EnderEyeItem
+ XXX.world.item.EnderpearlItem
- XXX.world.item.Equipable
+ XXX.world.item.ExperienceBottleItem
- XXX.world.item.FireChargeItem
+ XXX.world.item.FireworkRocketItem
- XXX.world.item.FireworkRocketItem$Shape
+ XXX.world.item.FireworkStarItem
- XXX.world.item.FishingRodItem
+ XXX.world.item.FlintAndSteelItem
- XXX.world.item.FoodOnAStickItem
+ XXX.world.item.GameMasterBlockItem
- XXX.world.item.GlowInkSacItem
+ XXX.world.item.HangingEntityItem
- XXX.world.item.HangingSignItem
+ XXX.world.item.HoeItem
- XXX.world.item.HoneyBottleItem
+ XXX.world.item.HoneycombItem
- XXX.world.item.HorseArmorItem
+ XXX.world.item.InkSacItem
- XXX.world.item.Instrument
+ XXX.world.item.InstrumentItem
- XXX.world.item.Instruments
+ XXX.world.item.Item
- XXX.world.item.Item$1
+ XXX.world.item.Item$Properties
- XXX.world.item.ItemCooldowns
+ XXX.world.item.ItemCooldowns$CooldownInstance
- XXX.world.item.ItemDisplayContext
+ XXX.world.item.ItemFrameItem
- XXX.world.item.ItemNameBlockItem
- XXX.world.item.Items
+ XXX.world.item.ItemStack
- XXX.world.item.ItemStack$TooltipPart
+ XXX.world.item.ItemStackLinkedSet
- XXX.world.item.ItemStackLinkedSet$1
+ XXX.world.item.ItemUtils
+ XXX.world.item.KnowledgeBookItem
- XXX.world.item.LeadItem
+ XXX.world.item.LingeringPotionItem
- XXX.world.item.MapItem
+ XXX.world.item.MilkBucketItem
- XXX.world.item.MinecartItem
+ XXX.world.item.MinecartItem$1
- XXX.world.item.MobBucketItem
+ XXX.world.item.NameItem
+ XXX.world.item.package-info
+ XXX.world.item.SplashPotionItem
- XXX.world.item.SpyglassItem
+ XXX.world.item.StandingAndWallBlockItem
- XXX.world.item.SuspiciousStewItem
+ XXX.world.item.SwordItem
- XXX.world.level.BaseCommandBlock
+ XXX.world.level.BaseSpawner
- XXX.world.level.BlockAndTintGetter
+ XXX.world.level.BlockCollisions
- XXX.world.level.BlockEventData
+ XXX.world.level.BlockGetter
- XXX.world.level.ChunkPos
+ XXX.world.level.ChunkPos$1
- XXX.world.level.ClipBlockStateContext
+ XXX.world.level.ClipContext
- XXX.world.level.ClipContext$Block
+ XXX.world.level.ClipContext$Fluid
- XXX.world.level.ClipContext$ShapeGetter
+ XXX.world.level.CollisionGetter
- XXX.world.level.ColorResolver
+ XXX.world.level.CommonLevelAccessor
- XXX.world.level.CustomSpawner
+ XXX.world.level.DataPackConfig
- XXX.world.level.EmptyBlockGetter
+ XXX.world.level.EntityBasedExplosionDamageCalculator
- XXX.world.level.EntityGetter
+ XXX.world.level.Explosion
- XXX.world.level.Explosion$BlockInteraction
+ XXX.world.level.ExplosionDamageCalculator
- XXX.world.level.FoliageColor
+ XXX.world.level.ForcedChunksSavedData
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
- XXX.world.level.Level$2
+ XXX.world.level.Level$ExplosionInteraction
- XXX.world.level.LevelAccessor
+ XXX.world.level.LevelHeightAccessor
- XXX.world.level.LevelHeightAccessor$1
+ XXX.world.level.LevelReader
- XXX.world.level.LevelSettings
- XXX.world.level.LevelSimulatedReader
+ XXX.world.level.LevelSimulatedRW
+ XXX.world.level.LevelTimeAccess
- XXX.world.level.LevelWriter
+ XXX.world.level.LightLayer
- XXX.world.level.LocalMobCapCalculator
+ XXX.world.level.LocalMobCapCalculator$MobCounts
- XXX.world.level.NaturalSpawner
+ XXX.world.level.NaturalSpawner$1
- XXX.world.level.NaturalSpawner$AfterSpawnCallback
+ XXX.world.level.NaturalSpawner$ChunkGetter
- XXX.world.level.NaturalSpawner$SpawnPredicate
+ XXX.world.level.NaturalSpawner$SpawnState
- XXX.world.level.NoiseColumn
- XXX.world.level.package-info
+ XXX.world.level.PathNavigationRegion
- XXX.world.level.PotentialCalculator
+ XXX.world.level.PotentialCalculator$PointCharge
- XXX.world.level.ServerLevelAccessor
+ XXX.world.level.SignalGetter
- XXX.world.level.SpawnData
+ XXX.world.level.SpawnData$CustomSpawnRules
- XXX.world.level.StructureManager
+ XXX.world.level.WorldDataConfiguration
- XXX.world.level.WorldGenLevel
- XXX.world.phys.AABB
+ XXX.world.phys.BlockHitResult
- XXX.world.phys.EntityHitResult
+ XXX.world.phys.HitResult
- XXX.world.phys.HitResult$Type
+ XXX.world.phys.package-info
+ XXX.world.phys.Vec2
- XXX.world.phys.Vec3
+ XXX.world.scores.Objective
- XXX.world.scores.package-info
- XXX.world.scores.PlayerTeam
+ XXX.world.scores.Score
- XXX.world.scores.Scoreboard
+ XXX.world.scores.ScoreboardSaveData
- XXX.world.scores.Team
+ XXX.world.scores.Team$CollisionRule
- XXX.world.scores.Team$Visibility
+ XXX.world.ticks.BlackholeTickAccess
- XXX.world.ticks.BlackholeTickAccess$1
+ XXX.world.ticks.BlackholeTickAccess$2
- XXX.world.ticks.ContainerSingleItem
+ XXX.world.ticks.LevelChunkTicks
- XXX.world.ticks.LevelTickAccess
+ XXX.world.ticks.LevelTicks
- XXX.world.ticks.LevelTicks$PosAndContainerConsumer
+ XXX.world.ticks.package-info
+ XXX.world.ticks.ProtoChunkTicks
- XXX.world.ticks.SavedTick
+ XXX.world.ticks.SavedTick$1
- XXX.world.ticks.ScheduledTick
+ XXX.world.ticks.ScheduledTick$1
- XXX.world.ticks.SerializableTickContainer
+ XXX.world.ticks.TickAccess
- XXX.world.ticks.TickContainerAccess
+ XXX.world.ticks.TickPriority
- XXX.world.ticks.WorldGenTickAccess
- XXX.worldgen.biome.BiomeData
+ XXX.worldgen.biome.EndBiomes
```

</details>
<details>
<summary>
Changes
</summary>

```
net.minecraft.ChatFormatting -1M | -2P
```
```
net.minecraft.SharedConstants -1P
```
```
net.minecraft.Util +1M -2M
```
```
XXX.advancements.critereon.DeserializationContext +2M -3M | +1P -1P
```
```
XXX.advancements.critereon.PlayerTrigger$TriggerInstance -1M
```
```
XXX.minecraft.core.Direction -3P
```
```
XXX.minecraft.core.Direction$Axis -1P
```
```
XXX.minecraft.core.Direction$Axis$2 -1M
```
```
XXX.core.particles.ParticleTypes -1P
```
```
XXX.worldgen.features.CaveFeatures -4P
```
```
XXX.worldgen.placement.CavePlacements -4P
```
```
XXX.minecraft.network.FriendlyByteBuf +3M -6M
```
```
XXX.protocol.game.ClientGamePacketListener -6P
```
```
XXX.protocol.game.ClientboundSetHealthPacket +1M -2M | -1P
```
```
XXX.network.syncher.EntityDataSerializers -1M | -1P
```
```
XXX.minecraft.server.MinecraftServer +22M -40M | -3P
```
```
XXX.world.damagesource.DamageSources -2M | -2P
```
```
XXX.world.damagesource.DamageTypes -2P
```
```
XXX.world.effect.MobEffects -2P
```
```
XXX.world.entity.Entity +4M -19M | +1P -7P
```
```
XXX.entity.animal.Chicken -3M | -1P
```
```
XXX.entity.animal.Cow -18M | -3P
```
```
XXX.entity.animal.IronGolem +1M -1M
```
```
XXX.entity.animal.Parrot +1M -2M
```
```
XXX.entity.animal.Pig -1M
```
```
XXX.entity.animal.Sheep -1M
```
```
XXX.entity.animal.Wolf +1M -1M
```
```
XXX.animal.axolotl.Axolotl +1M -1M
```
```
XXX.animal.horse.AbstractChestedHorse -1M
```
```
XXX.animal.horse.AbstractHorse +1M -2M
```
```
XXX.animal.sniffer.Sniffer +6M
```
```
XXX.animal.sniffer.SnifferAi$Scenting +2M
```
```
XXX.boss.enderdragon.EndCrystal +1M -1M
```
```
XXX.entity.decoration.ArmorStand +1M -1M
```
```
XXX.entity.item.ItemEntity +2M -4M | -1P
```
```
XXX.entity.monster.Silverfish +1M -1M
```
```
XXX.entity.monster.Vex -1M
```
```
XXX.entity.monster.Zombie +2M -7M
```
```
XXX.entity.vehicle.MinecartTNT +1M -1M
```
```
XXX.world.food.FoodProperties +1M -2M | -1P
```
```
XXX.world.food.Foods -1M | -1P
```
```
XXX.item.alchemy.Potions -6P
```
```
XXX.item.crafting.FireworkRocketRecipe +3M -3M
```
```
XXX.item.crafting.FireworkStarRecipe +3M -3M
```
```
XXX.item.crafting.MapExtendingRecipe +3M -2M
```
```
XXX.level.block.AbstractCandleBlock -2M
```
```
XXX.level.block.AirBlock -2M
```
```
XXX.level.block.BasePressurePlateBlock +1M -1M
```
```
XXX.level.block.CarvedPumpkinBlock +2M
```
```
XXX.level.block.ChainBlock -1M
```
```
XXX.level.block.CrossCollisionBlock -1M
```
```
XXX.level.block.DoorBlock +1M -2M
```
```
XXX.level.block.EndRodBlock -1M
```
```
XXX.level.block.FenceGateBlock -2M
```
```
XXX.level.block.RotatedPillarBlock -1M
```
```
XXX.level.block.SlimeBlock -2M
```
```
XXX.level.block.SnifferEggBlock +2M -1M | +2P -2P
```
```
XXX.level.levelgen.NoiseGeneratorSettings -1M | -1P
```
```
XXX.level.levelgen.NoiseRouterData -2M
```
```
XXX.level.levelgen.WorldDimensions -1M
```
```
XXX.levelgen.feature.TreeFeature +7M -10M
```

</details>
<details>
<summary>
net.minecraft.ChatFormatting
</summary>

```diff
+ boolean lambda$static$2(ChatFormatting)
```

</details>
<details>
<summary>
net.minecraft.Util
</summary>

```diff
+ int calculatePrefixSize(Iterable)
+ void shuffle(List,RandomSource)
- void shuffle(ObjectArrayList,RandomSource)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.DeserializationContext
</summary>

```diff
+ LootTable lambda$deserializeConditions$0(ResourceLocation)
- void <init>(ResourceLocation,LootDataManager)
+ void <init>(ResourceLocation,PredicateManager)
- void lambda$deserializeConditions$0(String,String,String)
+ void lambda$deserializeConditions$1(String,String,String)
```

</details>
<details>
<summary>
net.minecraft.advancements.critereon.PlayerTrigger$TriggerInstance
</summary>

```diff
+ PlayerTrigger$TriggerInstance vote(MinMaxBounds$Ints)
```

</details>
<details>
<summary>
net.minecraft.core.Direction$Axis$2
</summary>

```diff
+ Direction[] getOrthogonalDirections()
```

</details>
<details>
<summary>
net.minecraft.network.FriendlyByteBuf
</summary>

```diff
+ CompoundTag castToCompound(Tag)
- CompoundTag readNbt(NbtAccounter)
- DecoderException lambda$readWithCodec$0(CompoundTag,String)
+ DecoderException lambda$readWithCodec$0(Tag,String)
- FriendlyByteBuf writeNbt(CompoundTag)
+ FriendlyByteBuf writeNbt(Tag)
+ Object read(FriendlyByteBuf$Reader)
+ Tag readNbt(NbtAccounter)
+ void write(FriendlyByteBuf$Writer,Object)
```

</details>
<details>
<summary>
net.minecraft.network.protocol.game.ClientboundSetHealthPacket
</summary>

```diff
+ int getThirst()
+ void <init>(float,int,float,int)
- void <init>(float,int,float)
```

</details>
<details>
<summary>
net.minecraft.network.syncher.EntityDataSerializers
</summary>

```diff
+ void lambda$static$1(FriendlyByteBuf,EntityTransformType)
```

</details>
<details>
<summary>
net.minecraft.server.MinecraftServer
</summary>

```diff
- boolean lambda$getSelectedPacks$26(Collection,String)
+ boolean lambda$getSelectedPacks$30(Collection,String)
- boolean lambda$loadStatusIcon$10(Path)
+ boolean lambda$loadStatusIcon$12(Path)
+ boolean lambda$loadStatusIcon$13(Path)
- boolean lambda$loadStatusIcon$9(Path)
+ boolean lambda$waitUntilNextTick$11()
- boolean lambda$waitUntilNextTick$8()
+ boolean vote(OptionId,Entity,int)
- CompletionStage lambda$reloadResources$24(RegistryAccess$Frozen,ImmutableList)
+ CompletionStage lambda$reloadResources$28(RegistryAccess$Frozen,ImmutableList)
+ FinishedVote finishVote(UUID,boolean)
+ FinishedVote$UnpackOptions gatherOptions()
- ImmutableList lambda$reloadResources$21(Collection)
+ ImmutableList lambda$reloadResources$25(Collection)
+ ItemModifierManager getItemModifierManager()
- LootDataManager getLootData()
+ LootTables getLootTables()
- MinecraftServer$ReloadableResources lambda$reloadResources$23(CloseableResourceManager,ReloadableServerResources)
+ MinecraftServer$ReloadableResources lambda$reloadResources$27(CloseableResourceManager,ReloadableServerResources)
- Optional lambda$loadStatusIcon$11()
- Optional lambda$loadStatusIcon$12(Path)
+ Optional lambda$loadStatusIcon$14()
+ Optional lambda$loadStatusIcon$15(Path)
+ PredicateManager getPredicateManager()
+ ServerVoteStorage getVoteStorage()
- String lambda$dumpNativeModules$27(NativeModuleLister$NativeModuleInfo)
+ String lambda$dumpNativeModules$31(NativeModuleLister$NativeModuleInfo)
- String lambda$fillSystemReport$14()
- String lambda$fillSystemReport$15()
- String lambda$fillSystemReport$16(Pack)
- String lambda$fillSystemReport$17()
- String lambda$fillSystemReport$20()
+ String lambda$fillSystemReport$20(Pack)
+ String lambda$fillSystemReport$21()
+ String lambda$fillSystemReport$22()
+ String lambda$fillSystemReport$23()
+ String lambda$fillSystemReport$24()
- String lambda$tickChildren$13(ServerLevel)
+ String lambda$tickChildren$17(ServerLevel)
+ Style lambda$finishVote$9(Component,Style)
+ void checkAllScheduledTasks()
+ void executeLater(int,Runnable)
+ void finishVote(FinishedVote,boolean)
+ void flushVotes()
+ void lambda$finishVote$10(ServerVote$Effect)
- void lambda$reloadResources$22(CloseableResourceManager,ReloadableServerResources,Throwable)
- void lambda$reloadResources$25(Collection,MinecraftServer$ReloadableResources)
+ void lambda$reloadResources$26(CloseableResourceManager,ReloadableServerResources,Throwable)
+ void lambda$reloadResources$29(Collection,MinecraftServer$ReloadableResources)
+ void lambda$reloadVotes$8(ServerPlayer)
- void lambda$startMetricsRecordingTick$28(Path)
- void lambda$startMetricsRecordingTick$29(Path)
+ void lambda$startMetricsRecordingTick$32(Path)
+ void lambda$startMetricsRecordingTick$33(Path)
- void lambda$startRecordingMetrics$30(Consumer,ProfileResults)
+ void lambda$startRecordingMetrics$34(Consumer,ProfileResults)
+ void lambda$tickChildren$16(FinishedVote)
+ void reloadVotes()
+ void startVote(UUID,ServerVote)
+ void syncVotesForPlayer(ServerPlayer,OptionId)
+ VoteStorage loadVotes()
```

</details>
<details>
<summary>
net.minecraft.world.damagesource.DamageSources
</summary>

```diff
+ DamageSource midasTouch()
+ DamageSource onMoon()
```

</details>
<details>
<summary>
net.minecraft.world.entity.Entity
</summary>

```diff
+ boolean canSpawnFootprintParticle()
+ boolean canTransformFly()
+ boolean hurtInternal(DamageSource,float)
- boolean killedEntity(ServerLevel,LivingEntity)
+ boolean noCulling()
- boolean teleportTo(ServerLevel,double,double,double,Set,float,float)
+ boolean wasKilled(ServerLevel,LivingEntity)
+ Entity effectiveEntity()
+ Entity teleportTo(ServerLevel,double,double,double,Set,float,float)
+ EntityDimensions getCurrentDimensions()
+ float getEffectiveGravity()
+ float getGravity()
- float getNameTagOffsetY()
+ String getSkinName()
+ void copyTransformedProperties(LivingEntity)
+ void handleInsidePortal(BlockPos,boolean)
- void handleInsidePortal(BlockPos)
+ void postTick()
+ void setNoCulling(boolean)
+ void spawnFootprintParticle()
+ void stepOnBlock(BlockPos,BlockState,Block)
+ void transformedTick(EntityTransform,LivingEntity)
+ void turnIntoGold()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Chicken
</summary>

```diff
+ void lambda$aiStep$0(Holder$Reference)
+ void tickFlapping()
+ void transformedTick(EntityTransform,LivingEntity)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Cow
</summary>

```diff
+ boolean isBaloonCowEnabled()
+ boolean lambda$registerGoals$0()
+ double getPassengersRidingOffset()
+ EntityDimensions getDimensions(Pose)
+ float getBloatScale()
+ int getBloatLevel()
+ LivingEntity getControllingPassenger()
+ void <clinit>()
+ void addAdditionalSaveData(CompoundTag)
+ void aiStep()
+ void defineSynchedData()
+ void dropAllDeathLoot(DamageSource)
+ void explode()
+ void liftOff()
+ void onDonePathing()
+ void onSyncedDataUpdated(EntityDataAccessor)
+ void readAdditionalSaveData(CompoundTag)
+ void setBloatLevel(int)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.IronGolem
</summary>

```diff
- boolean hurt(DamageSource,float)
+ boolean hurtInternal(DamageSource,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Parrot
</summary>

```diff
+ boolean canTransformFly()
- boolean hurt(DamageSource,float)
+ boolean hurtInternal(DamageSource,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Pig
</summary>

```diff
+ InteractionResult transformInteract(Player,LivingEntity,InteractionHand)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Sheep
</summary>

```diff
+ DyeColor shiftColor(DyeColor,int)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Wolf
</summary>

```diff
- boolean hurt(DamageSource,float)
+ boolean hurtInternal(DamageSource,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.axolotl.Axolotl
</summary>

```diff
- boolean hurt(DamageSource,float)
+ boolean hurtInternal(DamageSource,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.horse.AbstractChestedHorse
</summary>

```diff
+ void dropCustomDeathLoot(DamageSource,int,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.horse.AbstractHorse
</summary>

```diff
- boolean hurt(DamageSource,float)
+ boolean hurtInternal(DamageSource,float)
+ InteractionResult transformInteract(Player,LivingEntity,InteractionHand)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.sniffer.Sniffer
</summary>

```diff
- boolean canSniff()
- boolean isTempted()
- boolean lambda$calculateDigPosition$1(BlockPos)
- boolean lambda$canDig$2(BlockPos,GlobalPos)
- float getNameTagOffsetY()
- Sniffer onScentingStart()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.sniffer.SnifferAi$Scenting
</summary>

```diff
- boolean checkExtraStartConditions(ServerLevel,LivingEntity)
- boolean checkExtraStartConditions(ServerLevel,Sniffer)
```

</details>
<details>
<summary>
net.minecraft.world.entity.boss.enderdragon.EndCrystal
</summary>

```diff
- boolean hurt(DamageSource,float)
+ boolean hurtInternal(DamageSource,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.decoration.ArmorStand
</summary>

```diff
- boolean hurt(DamageSource,float)
+ boolean hurtInternal(DamageSource,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.item.ItemEntity
</summary>

```diff
- boolean hurt(DamageSource,float)
+ boolean hurtInternal(DamageSource,float)
+ boolean isThrownIntentionally()
+ void setThrower(UUID,boolean)
- void setThrower(UUID)
+ void turnIntoGold()
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Silverfish
</summary>

```diff
- boolean hurt(DamageSource,float)
+ boolean hurtInternal(DamageSource,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Vex
</summary>

```diff
+ boolean canTransformFly()
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Zombie
</summary>

```diff
- boolean hurt(DamageSource,float)
+ boolean hurtInternal(DamageSource,float)
- boolean killedEntity(ServerLevel,LivingEntity)
+ boolean lambda$addBehaviourGoals$1(Entity)
+ boolean wasKilled(ServerLevel,LivingEntity)
+ float adjustDamage(float)
+ float getSpeed()
+ void burnInSun(LivingEntity)
+ void transformedTick(EntityTransform,LivingEntity)
```

</details>
<details>
<summary>
net.minecraft.world.entity.vehicle.MinecartTNT
</summary>

```diff
- boolean hurt(DamageSource,float)
+ boolean hurtInternal(DamageSource,float)
```

</details>
<details>
<summary>
net.minecraft.world.food.FoodProperties
</summary>

```diff
+ BiConsumer getOnEaten()
+ void <init>(int,float,boolean,boolean,boolean,List,BiConsumer)
- void <init>(int,float,boolean,boolean,boolean,List)
```

</details>
<details>
<summary>
net.minecraft.world.food.Foods
</summary>

```diff
+ void lambda$static$0(ItemStack,LivingEntity)
```

</details>
<details>
<summary>
net.minecraft.world.item.crafting.FireworkRocketRecipe
</summary>

```diff
- ItemStack assemble(Container,RegistryAccess)
- ItemStack assemble(CraftingContainer,RegistryAccess)
+ ItemStack assembleRaw(Container,RegistryAccess)
+ ItemStack assembleRaw(CraftingContainer,RegistryAccess)
- ItemStack getResultItem(RegistryAccess)
+ ItemStack getResultItemRaw(RegistryAccess)
```

</details>
<details>
<summary>
net.minecraft.world.item.crafting.FireworkStarRecipe
</summary>

```diff
- ItemStack assemble(Container,RegistryAccess)
- ItemStack assemble(CraftingContainer,RegistryAccess)
+ ItemStack assembleRaw(Container,RegistryAccess)
+ ItemStack assembleRaw(CraftingContainer,RegistryAccess)
- ItemStack getResultItem(RegistryAccess)
+ ItemStack getResultItemRaw(RegistryAccess)
```

</details>
<details>
<summary>
net.minecraft.world.item.crafting.MapExtendingRecipe
</summary>

```diff
- ItemStack assemble(Container,RegistryAccess)
- ItemStack assemble(CraftingContainer,RegistryAccess)
+ ItemStack assembleRaw(Container,RegistryAccess)
+ ItemStack assembleRaw(CraftingContainer,RegistryAccess)
- ItemStack findFilledMap(CraftingContainer)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.AbstractCandleBlock
</summary>

```diff
+ boolean isRandomlyTicking(BlockState)
+ void randomTick(BlockState,ServerLevel,BlockPos,RandomSource)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.AirBlock
</summary>

```diff
+ boolean canAirPass(BlockState,ServerLevel,BlockPos,Direction)
+ boolean canStickToStuff(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.BasePressurePlateBlock
</summary>

```diff
+ boolean isPossibleToRespawnInThis()
- boolean isPossibleToRespawnInThis(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CarvedPumpkinBlock
</summary>

```diff
- boolean lambda$getOrCreateIronGolemBase$1(BlockInWorld)
- boolean lambda$getOrCreateIronGolemFull$2(BlockInWorld)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.ChainBlock
</summary>

```diff
+ boolean isStickyToNeighbour(Level,BlockPos,BlockState,BlockPos,BlockState,Direction,Direction)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.CrossCollisionBlock
</summary>

```diff
+ boolean isStickyToNeighbour(Level,BlockPos,BlockState,BlockPos,BlockState,Direction,Direction)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.DoorBlock
</summary>

```diff
- BlockSetType type()
+ boolean isRandomlyTicking(BlockState)
+ void randomTick(BlockState,ServerLevel,BlockPos,RandomSource)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.EndRodBlock
</summary>

```diff
+ void spawnAfterBreak(BlockState,ServerLevel,BlockPos,ItemStack,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.FenceGateBlock
</summary>

```diff
+ boolean isRandomlyTicking(BlockState)
+ void randomTick(BlockState,ServerLevel,BlockPos,RandomSource)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.RotatedPillarBlock
</summary>

```diff
+ void spawnAfterBreak(BlockState,ServerLevel,BlockPos,ItemStack,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SlimeBlock
</summary>

```diff
+ boolean canStickToStuff(BlockState)
+ boolean isStickyToNeighbour(Level,BlockPos,BlockState,BlockPos,BlockState,Direction,Direction)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.SnifferEggBlock
</summary>

```diff
- boolean isPathfindable(BlockState,BlockGetter,BlockPos,PathComputationType)
+ int getAge(BlockState)
- int getHatchLevel(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.NoiseGeneratorSettings
</summary>

```diff
+ NoiseGeneratorSettings moon(BootstapContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.NoiseRouterData
</summary>

```diff
+ DensityFunction slideMoon(DensityFunction)
+ NoiseRouter moon(HolderGetter)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.WorldDimensions
</summary>

```diff
+ boolean isStableMoon(LevelStem)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.feature.TreeFeature
</summary>

```diff
- BlockPos lambda$doPlace$3(BlockPos,RandomSource,RootPlacer)
+ BlockPos lambda$doPlace$4(BlockPos,RandomSource,RootPlacer)
+ boolean isBlockWater(LevelSimulatedReader,BlockPos)
+ boolean isReplaceablePlant(LevelSimulatedReader,BlockPos)
- boolean lambda$isAirOrLeaves$1(BlockState)
+ boolean lambda$isAirOrLeaves$2(BlockState)
+ boolean lambda$isBlockWater$1(BlockState)
+ boolean lambda$isReplaceablePlant$3(BlockState)
+ Boolean lambda$place$10(WorldGenLevel,Set,Set,Set,BoundingBox)
- Boolean lambda$place$9(WorldGenLevel,Set,Set,Set,BoundingBox)
- boolean lambda$validTreePos$2(BlockState)
- void lambda$doPlace$4(TreeConfiguration,WorldGenLevel,FoliagePlacer$FoliageSetter,RandomSource,int,int,int,FoliagePlacer$FoliageAttachment)
+ void lambda$doPlace$5(TreeConfiguration,WorldGenLevel,FoliagePlacer$FoliageSetter,RandomSource,int,int,int,FoliagePlacer$FoliageAttachment)
- void lambda$place$5(Set,WorldGenLevel,BlockPos,BlockState)
+ void lambda$place$8(Set,WorldGenLevel,BlockPos,BlockState)
- void lambda$place$8(TreeDecorator$Context,TreeDecorator)
+ void lambda$place$9(TreeDecorator$Context,TreeDecorator)
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
+ net.minecraft.package-info
+ net.minecraft.ReportedException
- net.minecraft.ResourceLocationException
+ net.minecraft.SharedConstants
- net.minecraft.SystemReport
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
+ net.minecraft.Util$IdentityStrategy
- net.minecraft.Util$OS
+ net.minecraft.Util$OS$1
- net.minecraft.Util$OS$2
+ net.minecraft.WorldVersion
- XXX.advancements.critereon.AbstractCriterionTriggerInstance
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
+ XXX.advancements.critereon.ConstructBeaconTrigger
- XXX.advancements.critereon.ConstructBeaconTrigger$TriggerInstance
+ XXX.advancements.critereon.ConsumeItemTrigger
- XXX.advancements.critereon.ConsumeItemTrigger$TriggerInstance
+ XXX.advancements.critereon.CuredZombieVillagerTrigger
- XXX.advancements.critereon.CuredZombieVillagerTrigger$TriggerInstance
+ XXX.advancements.critereon.DamagePredicate
- XXX.advancements.critereon.DamagePredicate$Builder
+ XXX.advancements.critereon.DamageSourcePredicate
- XXX.advancements.critereon.DamageSourcePredicate$Builder
+ XXX.advancements.critereon.DeserializationContext
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
- XXX.advancements.critereon.EntityPredicate$Composite
+ XXX.advancements.critereon.EntitySubPredicate
- XXX.advancements.critereon.EntitySubPredicate$1
+ XXX.advancements.critereon.EntitySubPredicate$Type
- XXX.advancements.critereon.EntitySubPredicate$Types
+ XXX.advancements.critereon.EntityTypePredicate
- XXX.advancements.critereon.EntityTypePredicate$1
+ XXX.advancements.critereon.EntityTypePredicate$TagPredicate
- XXX.advancements.critereon.EntityTypePredicate$TypePredicate
+ XXX.advancements.critereon.EntityVariantPredicate
- XXX.advancements.critereon.EntityVariantPredicate$1
+ XXX.advancements.critereon.FilledBucketTrigger
- XXX.advancements.critereon.FilledBucketTrigger$TriggerInstance
+ XXX.advancements.critereon.FishingHookPredicate
- XXX.advancements.critereon.FishingRodHookedTrigger
+ XXX.advancements.critereon.FishingRodHookedTrigger$TriggerInstance
- XXX.advancements.critereon.FluidPredicate
+ XXX.advancements.critereon.FluidPredicate$Builder
- XXX.advancements.critereon.ImpossibleTrigger
+ XXX.advancements.critereon.ImpossibleTrigger$TriggerInstance
- XXX.advancements.critereon.InventoryChangeTrigger
+ XXX.advancements.critereon.InventoryChangeTrigger$TriggerInstance
- XXX.advancements.critereon.ItemDurabilityTrigger
+ XXX.advancements.critereon.ItemDurabilityTrigger$TriggerInstance
- XXX.advancements.critereon.ItemInteractWithBlockTrigger
+ XXX.advancements.critereon.ItemInteractWithBlockTrigger$TriggerInstance
- XXX.advancements.critereon.ItemPredicate
+ XXX.advancements.critereon.ItemPredicate$Builder
- XXX.advancements.critereon.KilledByCrossbowTrigger
+ XXX.advancements.critereon.KilledByCrossbowTrigger$TriggerInstance
- XXX.advancements.critereon.KilledTrigger
+ XXX.advancements.critereon.KilledTrigger$TriggerInstance
- XXX.advancements.critereon.LevitationTrigger
+ XXX.advancements.critereon.LevitationTrigger$TriggerInstance
- XXX.advancements.critereon.LighthingBoltPredicate
+ XXX.advancements.critereon.LightningStrikeTrigger
- XXX.advancements.critereon.LightningStrikeTrigger$TriggerInstance
- XXX.advancements.critereon.LightPredicate
+ XXX.advancements.critereon.LightPredicate$Builder
+ XXX.advancements.critereon.LocationPredicate
- XXX.advancements.critereon.LocationPredicate$Builder
+ XXX.advancements.critereon.LootTableTrigger
- XXX.advancements.critereon.LootTableTrigger$TriggerInstance
+ XXX.advancements.critereon.MinMaxBounds
- XXX.advancements.critereon.MinMaxBounds$BoundsFactory
+ XXX.advancements.critereon.MinMaxBounds$BoundsFromReaderFactory
- XXX.advancements.critereon.MinMaxBounds$Doubles
+ XXX.advancements.critereon.MinMaxBounds$Ints
- XXX.advancements.critereon.MobEffectsPredicate
+ XXX.advancements.critereon.MobEffectsPredicate$MobEffectInstancePredicate
- XXX.advancements.critereon.NbtPredicate
- XXX.advancements.critereon.package-info
+ XXX.advancements.critereon.PickedUpItemTrigger
- XXX.advancements.critereon.PickedUpItemTrigger$TriggerInstance
+ XXX.advancements.critereon.PlacedBlockTrigger
- XXX.advancements.critereon.PlacedBlockTrigger$TriggerInstance
+ XXX.advancements.critereon.PlayerHurtEntityTrigger
- XXX.advancements.critereon.PlayerHurtEntityTrigger$TriggerInstance
+ XXX.advancements.critereon.PlayerInteractTrigger
- XXX.advancements.critereon.PlayerInteractTrigger$TriggerInstance
+ XXX.advancements.critereon.PlayerPredicate
- XXX.advancements.critereon.PlayerPredicate$AdvancementCriterionsPredicate
+ XXX.advancements.critereon.PlayerPredicate$AdvancementDonePredicate
- XXX.advancements.critereon.PlayerPredicate$AdvancementPredicate
+ XXX.advancements.critereon.PlayerPredicate$Builder
- XXX.advancements.critereon.PlayerTrigger
+ XXX.advancements.critereon.PlayerTrigger$TriggerInstance
- XXX.advancements.critereon.RecipeUnlockedTrigger
+ XXX.advancements.critereon.RecipeUnlockedTrigger$TriggerInstance
- XXX.advancements.critereon.SerializationContext
+ XXX.advancements.critereon.ShotCrossbowTrigger
- XXX.advancements.critereon.ShotCrossbowTrigger$TriggerInstance
+ XXX.advancements.critereon.SimpleCriterionTrigger
- XXX.advancements.critereon.SlideDownBlockTrigger
+ XXX.advancements.critereon.SlideDownBlockTrigger$TriggerInstance
- XXX.advancements.critereon.SlimePredicate
+ XXX.advancements.critereon.StartRidingTrigger
- XXX.advancements.critereon.StartRidingTrigger$TriggerInstance
+ XXX.advancements.critereon.StatePropertiesPredicate
- XXX.advancements.critereon.StatePropertiesPredicate$Builder
+ XXX.advancements.critereon.StatePropertiesPredicate$ExactPropertyMatcher
- XXX.advancements.critereon.StatePropertiesPredicate$PropertyMatcher
+ XXX.advancements.critereon.StatePropertiesPredicate$RangedPropertyMatcher
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
- XXX.advancements.packs.package-info
- XXX.advancements.packs.VanillaAdvancementProvider
+ XXX.advancements.packs.VanillaAdventureAdvancements
- XXX.advancements.packs.VanillaHusbandryAdvancements
+ XXX.advancements.packs.VanillaNetherAdvancements
- XXX.advancements.packs.VanillaStoryAdvancements
+ XXX.advancements.packs.VanillaTheEndAdvancements
+ XXX.animal.allay.Allay
- XXX.animal.allay.Allay$AllayVibrationListenerConfig
+ XXX.animal.allay.Allay$JukeboxListener
- XXX.animal.allay.AllayAi
+ XXX.animal.allay.package-info
- XXX.animal.axolotl.Axolotl
+ XXX.animal.axolotl.Axolotl$AxolotlGroupData
- XXX.animal.axolotl.Axolotl$AxolotlLookControl
+ XXX.animal.axolotl.Axolotl$AxolotlMoveControl
- XXX.animal.axolotl.Axolotl$Variant
+ XXX.animal.axolotl.AxolotlAi
- XXX.animal.axolotl.package-info
- XXX.animal.axolotl.PlayDead
+ XXX.animal.axolotl.ValidatePlayDead
+ XXX.animal.camel.Camel
- XXX.animal.camel.Camel$CamelBodyRotationControl
+ XXX.animal.camel.Camel$CamelMoveControl
- XXX.animal.camel.CamelAi
+ XXX.animal.camel.CamelAi$CamelPanic
- XXX.animal.camel.CamelAi$RandomSitting
+ XXX.animal.camel.package-info
- XXX.animal.frog.Frog
+ XXX.animal.frog.Frog$FrogLookControl
- XXX.animal.frog.Frog$FrogNodeEvaluator
+ XXX.animal.frog.Frog$FrogPathNavigation
- XXX.animal.frog.FrogAi
- XXX.animal.frog.package-info
+ XXX.animal.frog.ShootTongue
- XXX.animal.frog.ShootTongue$1
+ XXX.animal.frog.ShootTongue$State
- XXX.animal.frog.Tadpole
+ XXX.animal.frog.TadpoleAi
+ XXX.animal.goat.Goat
- XXX.animal.goat.GoatAi
+ XXX.animal.goat.package-info
- XXX.animal.horse.AbstractChestedHorse
+ XXX.animal.horse.AbstractChestedHorse$1
- XXX.animal.horse.AbstractHorse
+ XXX.animal.horse.AbstractHorse$1
- XXX.animal.horse.Donkey
+ XXX.animal.horse.Horse
- XXX.animal.horse.Horse$HorseGroupData
+ XXX.animal.horse.Llama
- XXX.animal.horse.Llama$LlamaAttackWolfGoal
+ XXX.animal.horse.Llama$LlamaGroupData
- XXX.animal.horse.Llama$LlamaHurtByTargetGoal
+ XXX.animal.horse.Llama$Variant
- XXX.animal.horse.Markings
+ XXX.animal.horse.Mule
- XXX.animal.horse.package-info
- XXX.animal.horse.SkeletonHorse
+ XXX.animal.horse.SkeletonTrapGoal
- XXX.animal.horse.TraderLlama
+ XXX.animal.horse.TraderLlama$TraderLlamaDefendWanderingTraderGoal
- XXX.animal.horse.Variant
+ XXX.animal.horse.ZombieHorse
- XXX.animal.sniffer.Sniffer
+ XXX.animal.sniffer.Sniffer$1
- XXX.animal.sniffer.Sniffer$State
+ XXX.animal.sniffer.SnifferAi
- XXX.animal.sniffer.SnifferAi$1
- XXX.animal.sniffer.SnifferAi$3
+ XXX.animal.sniffer.SnifferAi$Digging
- XXX.animal.sniffer.SnifferAi$FeelingHappy
+ XXX.animal.sniffer.SnifferAi$FinishedDigging
- XXX.animal.sniffer.SnifferAi$Scenting
+ XXX.animal.sniffer.SnifferAi$Searching
- XXX.animal.sniffer.SnifferAi$Sniffing
+ XXX.animation.definitions.CamelAnimation
- XXX.animation.definitions.FrogAnimation
+ XXX.animation.definitions.package-info
+ XXX.animation.definitions.SnifferAnimation
- XXX.animation.definitions.WardenAnimation
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
+ XXX.arguments.item.FunctionArgument
- XXX.arguments.item.FunctionArgument$1
+ XXX.arguments.item.FunctionArgument$2
- XXX.arguments.item.FunctionArgument$Result
+ XXX.arguments.item.ItemArgument
- XXX.arguments.item.ItemInput
+ XXX.arguments.item.ItemParser
- XXX.arguments.item.ItemParser$ItemResult
+ XXX.arguments.item.ItemParser$TagResult
- XXX.arguments.item.ItemPredicateArgument
+ XXX.arguments.item.ItemPredicateArgument$Result
- XXX.arguments.item.package-info
- XXX.arguments.selector.EntitySelector
+ XXX.arguments.selector.EntitySelector$1
- XXX.arguments.selector.EntitySelectorParser
+ XXX.arguments.selector.package-info
- XXX.boss.enderdragon.EndCrystal
+ XXX.boss.enderdragon.EnderDragon
- XXX.boss.enderdragon.package-info
+ XXX.boss.wither.package-info
+ XXX.boss.wither.WitherBoss
- XXX.boss.wither.WitherBoss$WitherDoNothingGoal
+ XXX.chat.contents.BlockDataSource
- XXX.chat.contents.DataSource
+ XXX.chat.contents.EntityDataSource
- XXX.chat.contents.KeybindContents
+ XXX.chat.contents.KeybindResolver
- XXX.chat.contents.LiteralContents
+ XXX.chat.contents.NbtContents
+ XXX.chat.contents.package-info
- XXX.chat.contents.ScoreContents
+ XXX.chat.contents.SelectorContents
- XXX.chat.contents.StorageDataSource
+ XXX.chat.contents.TranslatableContents
- XXX.chat.contents.TranslatableFormatException
+ XXX.chat.report.AbuseReportSender
- XXX.chat.report.AbuseReportSender$1
+ XXX.chat.report.AbuseReportSender$SendException
- XXX.chat.report.AbuseReportSender$Services
+ XXX.chat.report.BanReason
- XXX.chat.report.ChatReportBuilder
+ XXX.chat.report.ChatReportBuilder$CannotBuildReason
- XXX.chat.report.ChatReportBuilder$ChatReport
+ XXX.chat.report.ChatReportBuilder$Result
- XXX.chat.report.ChatReportContextBuilder
+ XXX.chat.report.ChatReportContextBuilder$Collector
- XXX.chat.report.ChatReportContextBuilder$Handler
+ XXX.chat.report.package-info
+ XXX.chat.report.ReportEnvironment
- XXX.chat.report.ReportEnvironment$Server
+ XXX.chat.report.ReportEnvironment$Server$Realm
- XXX.chat.report.ReportEnvironment$Server$ThirdParty
- XXX.chat.report.ReportingContext
+ XXX.chat.report.ReportReason
- XXX.client.animation.AnimationChannel
+ XXX.client.animation.AnimationChannel$Interpolation
- XXX.client.animation.AnimationChannel$Interpolations
+ XXX.client.animation.AnimationChannel$Target
- XXX.client.animation.AnimationChannel$Targets
+ XXX.client.animation.AnimationDefinition
- XXX.client.animation.AnimationDefinition$Builder
+ XXX.client.animation.Keyframe
- XXX.client.animation.KeyframeAnimations
- XXX.client.animation.package-info
- XXX.client.gui.ComponentPath
+ XXX.client.gui.ComponentPath$Leaf
- XXX.client.gui.ComponentPath$Path
+ XXX.client.gui.Font
- XXX.client.gui.package-info
+ XXX.client.main.GameConfig
- XXX.client.main.GameConfig$FolderData
+ XXX.client.main.GameConfig$GameData
- XXX.client.main.GameConfig$QuickPlayData
+ XXX.client.main.GameConfig$UserData
- XXX.client.main.Main
+ XXX.client.main.Main$1
- XXX.client.main.Main$2
+ XXX.client.main.Main$3
+ XXX.client.main.package-info
- XXX.client.main.SilentInitException
- XXX.client.model.AbstractZombieModel
+ XXX.client.model.AgeableHierarchicalModel
- XXX.client.model.AgeableListModel
+ XXX.client.model.AllayModel
- XXX.client.model.AnimationUtils
+ XXX.client.model.ArmedModel
- XXX.client.model.ArmorStandArmorModel
+ XXX.client.model.ArmorStandModel
- XXX.client.model.AxolotlModel
+ XXX.client.model.BatModel
- XXX.client.model.BeeModel
+ XXX.client.model.BeretModel
+ XXX.client.model.DolphinModel
- XXX.client.model.DrownedModel
+ XXX.client.model.ElytraModel
- XXX.client.model.EndermanModel
+ XXX.client.model.EndermiteModel
- XXX.client.model.EntityModel
+ XXX.client.model.EvokerFangsModel
- XXX.client.model.FoxModel
+ XXX.client.model.FrogModel
- XXX.client.model.GhastModel
+ XXX.client.model.GiantZombieModel
- XXX.client.model.GoatModel
+ XXX.client.model.GuardianModel
- XXX.client.model.HeadedModel
+ XXX.client.model.HierarchicalModel
- XXX.client.model.HoglinModel
+ XXX.client.model.HorseModel
- XXX.client.model.HumanoidArmorModel
+ XXX.client.model.HumanoidModel
- XXX.client.model.HumanoidModel$1
+ XXX.client.model.HumanoidModel$ArmPose
- XXX.client.model.IllagerModel
+ XXX.client.model.IronGolemModel
- XXX.client.model.LavaSlimeModel
+ XXX.client.model.LeashKnotModel
- XXX.client.model.ListModel
+ XXX.client.model.LlamaModel
- XXX.client.model.LlamaSpitModel
+ XXX.client.model.MinecartModel
- XXX.client.model.Model
+ XXX.client.model.ModelUtils
- XXX.client.model.package-info
+ XXX.client.model.TridentModel
- XXX.client.model.TropicalFishModelA
+ XXX.client.model.TropicalFishModelB
- XXX.client.model.TurtleModel
+ XXX.client.model.VexModel
- XXX.client.model.VillagerHeadModel
+ XXX.client.model.VillagerModel
- XXX.client.model.WardenModel
+ XXX.client.model.WaterPatchModel
- XXX.client.model.WitchModel
+ XXX.client.model.WitherBossModel
- XXX.client.model.WolfModel
+ XXX.client.model.ZombieModel
- XXX.client.model.ZombieVillagerModel
+ XXX.client.multiplayer.AccountProfileKeyPairManager
- XXX.client.multiplayer.ClientAdvancements
+ XXX.client.multiplayer.ClientAdvancements$Listener
- XXX.client.multiplayer.ClientChunkCache
+ XXX.client.multiplayer.ClientChunkCache$Storage
- XXX.client.multiplayer.ClientHandshakePacketListenerImpl
+ XXX.client.multiplayer.ClientLevel
- XXX.client.multiplayer.ClientLevel$1
+ XXX.client.multiplayer.ClientLevel$ClientLevelData
- XXX.client.multiplayer.ClientLevel$EntityCallbacks
+ XXX.client.multiplayer.ClientPacketListener
- XXX.client.multiplayer.ClientPacketListener$1
+ XXX.client.multiplayer.ClientPacketListener$DeferredPacket
- XXX.client.multiplayer.ClientRegistryLayer
+ XXX.client.multiplayer.ClientSuggestionProvider
- XXX.client.multiplayer.ClientSuggestionProvider$1
+ XXX.client.multiplayer.MultiPlayerGameMode
- XXX.client.multiplayer.package-info
- XXX.client.multiplayer.PlayerInfo
+ XXX.client.multiplayer.ProfileKeyPairManager
- XXX.client.multiplayer.ProfileKeyPairManager$1
+ XXX.client.multiplayer.ServerData
- XXX.client.multiplayer.ServerData$ServerPackStatus
+ XXX.client.multiplayer.ServerList
- XXX.client.multiplayer.ServerStatusPinger
+ XXX.client.multiplayer.ServerStatusPinger$1
- XXX.client.multiplayer.ServerStatusPinger$2
+ XXX.client.multiplayer.ServerStatusPinger$2$1
+ XXX.client.particle.AshParticle
- XXX.client.particle.AshParticle$Provider
+ XXX.client.particle.AttackSweepParticle
- XXX.client.particle.AttackSweepParticle$Provider
+ XXX.client.particle.BaseAshSmokeParticle
- XXX.client.particle.BlockMarker
+ XXX.client.particle.BlockMarker$Provider
- XXX.client.particle.BreakingItemParticle
+ XXX.client.particle.BreakingItemParticle$Provider
- XXX.client.particle.BreakingItemParticle$SlimeProvider
+ XXX.client.particle.BreakingItemParticle$SnowballProvider
- XXX.client.particle.BubbleColumnUpParticle
+ XXX.client.particle.BubbleColumnUpParticle$Provider
- XXX.client.particle.BubbleParticle
+ XXX.client.particle.BubbleParticle$Provider
- XXX.client.particle.BubblePopParticle
+ XXX.client.particle.BubblePopParticle$Provider
- XXX.client.particle.CampfireSmokeParticle
+ XXX.client.particle.CampfireSmokeParticle$CosyProvider
- XXX.client.particle.CampfireSmokeParticle$SignalProvider
+ XXX.client.particle.CherryParticle
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
+ XXX.client.particle.EnchantmentTableParticle
- XXX.client.particle.EnchantmentTableParticle$NautilusProvider
+ XXX.client.particle.EnchantmentTableParticle$Provider
- XXX.client.particle.EndRodParticle
+ XXX.client.particle.EndRodParticle$Provider
- XXX.client.particle.ExplodeParticle
+ XXX.client.particle.ExplodeParticle$Provider
- XXX.client.particle.FallingDustParticle
+ XXX.client.particle.FallingDustParticle$Provider
- XXX.client.particle.FireworkParticles
+ XXX.client.particle.FireworkParticles$1
- XXX.client.particle.FireworkParticles$FlashProvider
+ XXX.client.particle.FireworkParticles$OverlayParticle
- XXX.client.particle.FireworkParticles$SparkParticle
+ XXX.client.particle.FireworkParticles$SparkProvider
- XXX.client.particle.FireworkParticles$Starter
+ XXX.client.particle.FlameParticle
- XXX.client.particle.FlameParticle$Provider
+ XXX.client.particle.FlameParticle$SmallFlameProvider
+ XXX.client.particle.FootprintParticle$Provider
- XXX.client.particle.GlowParticle
+ XXX.client.particle.GlowParticle$ElectricSparkProvider
- XXX.client.particle.GlowParticle$GlowSquidProvider
+ XXX.client.particle.GlowParticle$ScrapeProvider
- XXX.client.particle.GlowParticle$WaxOffProvider
+ XXX.client.particle.GlowParticle$WaxOnProvider
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
+ XXX.client.particle.package-info
+ XXX.client.particle.Particle
- XXX.client.particle.ParticleDescription
+ XXX.client.particle.ParticleEngine
- XXX.client.particle.ParticleEngine$1ParticleDefinition
+ XXX.client.particle.ParticleEngine$MutableSpriteSet
- XXX.client.particle.ParticleEngine$SpriteParticleRegistration
+ XXX.client.particle.ParticleProvider
- XXX.client.particle.ParticleProvider$Sprite
+ XXX.client.particle.ParticleRenderType
- XXX.client.particle.ParticleRenderType$1
+ XXX.client.particle.ParticleRenderType$2
- XXX.client.particle.ParticleRenderType$3
+ XXX.client.particle.ParticleRenderType$4
- XXX.client.particle.ParticleRenderType$5
+ XXX.client.particle.ParticleRenderType$6
- XXX.client.particle.PlayerCloudParticle
+ XXX.client.particle.PlayerCloudParticle$Provider
- XXX.client.particle.PlayerCloudParticle$SneezeProvider
+ XXX.client.particle.PortalParticle
- XXX.client.particle.PortalParticle$Provider
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
- XXX.client.particle.SpellParticle$AmbientMobProvider
+ XXX.client.particle.SpellParticle$InstantProvider
- XXX.client.particle.SpellParticle$MobProvider
+ XXX.client.particle.SpellParticle$Provider
- XXX.client.particle.SpellParticle$WitchProvider
+ XXX.client.particle.SpitParticle
- XXX.client.particle.SpitParticle$Provider
+ XXX.client.particle.SplashParticle
- XXX.client.particle.SplashParticle$Provider
+ XXX.client.particle.SpriteSet
- XXX.client.particle.SquidInkParticle
+ XXX.client.particle.SquidInkParticle$GlowInkProvider
- XXX.client.particle.SquidInkParticle$Provider
+ XXX.client.particle.SuspendedParticle
- XXX.client.particle.SuspendedParticle$CrimsonSporeProvider
+ XXX.client.particle.SuspendedParticle$SporeBlossomAirProvider
- XXX.client.particle.SuspendedParticle$SporeBlossomAirProvider$1
+ XXX.client.particle.SuspendedParticle$UnderwaterProvider
- XXX.client.particle.SuspendedParticle$WarpedSporeProvider
+ XXX.client.particle.SuspendedTownParticle
- XXX.client.particle.SuspendedTownParticle$ComposterFillProvider
+ XXX.client.particle.SuspendedTownParticle$DolphinSpeedProvider
- XXX.client.particle.SuspendedTownParticle$EggCrackProvider
+ XXX.client.particle.SuspendedTownParticle$HappyVillagerProvider
- XXX.client.particle.SuspendedTownParticle$Provider
+ XXX.client.particle.TerrainParticle
- XXX.client.particle.TerrainParticle$Provider
+ XXX.client.particle.TextureSheetParticle
- XXX.client.particle.TotemParticle
+ XXX.client.particle.TotemParticle$Provider
- XXX.client.particle.TrackingEmitter
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
- XXX.client.player.AbstractClientPlayer
+ XXX.client.player.Input
- XXX.client.player.KeyboardInput
+ XXX.client.player.LocalPlayer
- XXX.client.quickplay.package-info
- XXX.client.quickplay.QuickPlay
- XXX.client.quickplay.QuickPlayLog$1
- XXX.client.quickplay.QuickPlayLog$QuickPlayWorld
+ XXX.client.renderer.BiomeColors
- XXX.client.renderer.BlockEntityWithoutLevelRenderer
+ XXX.client.renderer.ChunkBufferBuilderPack
- XXX.client.renderer.CubeMap
+ XXX.client.renderer.DimensionSpecialEffects
- XXX.client.renderer.DimensionSpecialEffects$EndEffects
+ XXX.client.renderer.DimensionSpecialEffects$MoonEffects
+ XXX.client.voting.ClientVoteStorage
+ XXX.client.voting.ClientVoteStorage$CountAndLimit
+ XXX.client.voting.ClientVoteStorage$VoteInfo
+ XXX.client.voting.package-info
+ XXX.color.block.BlockColor
- XXX.color.block.BlockColors
+ XXX.color.block.BlockTintCache
- XXX.color.block.BlockTintCache$CacheData
+ XXX.color.block.BlockTintCache$LatestCacheInfo
- XXX.color.block.package-info
+ XXX.color.item.ItemColor
- XXX.color.item.ItemColors
+ XXX.color.item.package-info
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
+ XXX.commands.arguments.ScoreboardSlotArgument
- XXX.commands.arguments.ScoreHolderArgument
+ XXX.commands.arguments.ScoreHolderArgument$Info
- XXX.commands.arguments.ScoreHolderArgument$Info$Template
+ XXX.commands.arguments.ScoreHolderArgument$Result
- XXX.commands.arguments.ScoreHolderArgument$SelectorResult
- XXX.commands.arguments.SignedArgument
+ XXX.commands.arguments.SlotArgument
- XXX.commands.arguments.StringRepresentableArgument
+ XXX.commands.arguments.TeamArgument
- XXX.commands.arguments.TemplateMirrorArgument
+ XXX.commands.arguments.TemplateRotationArgument
- XXX.commands.arguments.TimeArgument
+ XXX.commands.arguments.TimeArgument$Info
- XXX.commands.arguments.TimeArgument$Info$Template
+ XXX.commands.arguments.UuidArgument
- XXX.commands.data.BlockDataAccessor
+ XXX.commands.data.BlockDataAccessor$1
- XXX.commands.data.DataAccessor
+ XXX.commands.data.DataCommands
- XXX.commands.data.DataCommands$DataManipulator
+ XXX.commands.data.DataCommands$DataManipulatorDecorator
- XXX.commands.data.DataCommands$DataProvider
+ XXX.commands.data.EntityDataAccessor
- XXX.commands.data.EntityDataAccessor$1
+ XXX.commands.data.package-info
+ XXX.commands.data.StorageDataAccessor
- XXX.commands.data.StorageDataAccessor$1
+ XXX.commands.synchronization.ArgumentTypeInfo
- XXX.commands.synchronization.ArgumentTypeInfo$Template
+ XXX.commands.synchronization.ArgumentTypeInfos
- XXX.commands.synchronization.ArgumentUtils
+ XXX.commands.synchronization.package-info
+ XXX.commands.synchronization.SingletonArgumentInfo
- XXX.commands.synchronization.SingletonArgumentInfo$Template
+ XXX.commands.synchronization.SuggestionProviders
- XXX.commands.synchronization.SuggestionProviders$Wrapper
+ XXX.components.toasts.VoteNagToast$Urgency
- XXX.core.cauldron.CauldronInteraction
+ XXX.core.cauldron.package-info
- XXX.core.dispenser.AbstractProjectileDispenseBehavior
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
+ XXX.core.dispenser.DispenseItemBehavior$16
- XXX.core.dispenser.DispenseItemBehavior$17
+ XXX.core.dispenser.DispenseItemBehavior$18
- XXX.core.dispenser.DispenseItemBehavior$19
+ XXX.core.dispenser.DispenseItemBehavior$2
- XXX.core.dispenser.DispenseItemBehavior$20
+ XXX.core.dispenser.DispenseItemBehavior$21
- XXX.core.dispenser.DispenseItemBehavior$22
+ XXX.core.dispenser.DispenseItemBehavior$23
- XXX.core.dispenser.DispenseItemBehavior$24
+ XXX.core.dispenser.DispenseItemBehavior$25
- XXX.core.dispenser.DispenseItemBehavior$26
+ XXX.core.dispenser.DispenseItemBehavior$27
- XXX.core.dispenser.DispenseItemBehavior$3
+ XXX.core.dispenser.DispenseItemBehavior$4
- XXX.core.dispenser.DispenseItemBehavior$5
+ XXX.core.dispenser.DispenseItemBehavior$6
- XXX.core.dispenser.DispenseItemBehavior$7
+ XXX.core.dispenser.DispenseItemBehavior$7$1
- XXX.core.dispenser.DispenseItemBehavior$8
+ XXX.core.dispenser.DispenseItemBehavior$8$1
- XXX.core.dispenser.DispenseItemBehavior$9
+ XXX.core.dispenser.OptionalDispenseItemBehavior
- XXX.core.dispenser.package-info
- XXX.core.dispenser.ShearsDispenseItemBehavior
+ XXX.core.dispenser.ShulkerBoxDispenseBehavior
- XXX.core.particles.BlockParticleOption
+ XXX.core.particles.BlockParticleOption$1
- XXX.core.particles.DustColorTransitionOptions
+ XXX.core.particles.DustColorTransitionOptions$1
- XXX.core.particles.DustParticleOptions
+ XXX.core.particles.DustParticleOptions$1
- XXX.core.particles.DustParticleOptionsBase
+ XXX.core.particles.ItemParticleOption
- XXX.core.particles.ItemParticleOption$1
+ XXX.core.particles.package-info
+ XXX.core.particles.ParticleGroup
- XXX.core.particles.ParticleOptions
+ XXX.core.particles.ParticleOptions$Deserializer
- XXX.core.particles.ParticleType
+ XXX.core.particles.ParticleTypes
- XXX.core.particles.ParticleTypes$1
+ XXX.core.particles.SculkChargeParticleOptions
- XXX.core.particles.SculkChargeParticleOptions$1
+ XXX.core.particles.ShriekParticleOption
- XXX.core.particles.ShriekParticleOption$1
+ XXX.core.particles.SimpleParticleType
- XXX.core.particles.SimpleParticleType$1
+ XXX.core.particles.VibrationParticleOption
- XXX.core.particles.VibrationParticleOption$1
- XXX.core.registries.BuiltInRegistries
+ XXX.core.registries.BuiltInRegistries$RegistryBootstrap
+ XXX.core.registries.package-info
- XXX.core.registries.Registries
+ XXX.data.advancements.AdvancementProvider
- XXX.data.advancements.AdvancementSubProvider
+ XXX.data.advancements.package-info
+ XXX.data.info.BiomeParametersDumpReport
- XXX.data.info.BlockListReport
+ XXX.data.info.CommandsReport
+ XXX.data.info.package-info
- XXX.data.info.RegistryDumpReport
- XXX.data.loot.BlockLootSubProvider
+ XXX.data.loot.EntityLootSubProvider
- XXX.data.loot.LootTableProvider
+ XXX.data.worldgen.package-info
- XXX.datafix.fixes.package-info
- XXX.datafix.fixes.SimpleEntityRenameFix
+ XXX.datafix.fixes.SimplestEntityRenameFix
- XXX.datafix.fixes.SpawnerDataFix
+ XXX.datafix.fixes.StatsCounterFix
- XXX.datafix.fixes.StatsRenameFix
+ XXX.datafix.fixes.StriderGravityFix
- XXX.datafix.fixes.StructureReferenceCountFix
- XXX.datafix.fixes.StructuresBecomeConfiguredFix
+ XXX.datafix.fixes.StructuresBecomeConfiguredFix$Conversion
+ XXX.datafix.fixes.StructureSettingsFlattenFix
- XXX.datafix.fixes.TeamDisplayNameFix
+ XXX.datafix.fixes.TrappedChestBlockEntityFix
- XXX.datafix.fixes.TrappedChestBlockEntityFix$TrappedChestSection
+ XXX.datafix.fixes.VariantRenameFix
- XXX.datafix.fixes.VillagerDataFix
+ XXX.datafix.fixes.VillagerFollowRangeFix
- XXX.datafix.fixes.VillagerRebuildLevelAndXpFix
+ XXX.datafix.fixes.VillagerTradeFix
- XXX.datafix.fixes.WallPropertyFix
+ XXX.datafix.fixes.WeaponSmithChestLootTableFix
- XXX.datafix.fixes.WorldGenSettingsDisallowOldCustomWorldsFix
+ XXX.datafix.fixes.WorldGenSettingsFix
- XXX.datafix.fixes.WorldGenSettingsFix$StructureFeatureConfiguration
+ XXX.datafix.fixes.WorldGenSettingsHeightAndBiomeFix
- XXX.datafix.fixes.WriteAndReadFix
+ XXX.datafix.fixes.ZombieVillagerRebuildXpFix
- XXX.datafix.schemas.NamespacedSchema
+ XXX.datafix.schemas.NamespacedSchema$1
- XXX.datafix.schemas.V100
+ XXX.datafix.schemas.V102
- XXX.datafix.schemas.V1022
+ XXX.datafix.schemas.V106
- XXX.datafix.schemas.V107
+ XXX.datafix.schemas.V1125
- XXX.datafix.schemas.V135
+ XXX.datafix.schemas.V143
- XXX.datafix.schemas.V1451
+ XXX.datafix.schemas.V1451_1
- XXX.datafix.schemas.V1451_2
+ XXX.datafix.schemas.V1451_3
- XXX.datafix.schemas.V1451_4
+ XXX.datafix.schemas.V1451_5
- XXX.datafix.schemas.V1451_6
+ XXX.datafix.schemas.V1451_6$1
- XXX.datafix.schemas.V1451_6$2
+ XXX.datafix.schemas.V1460
- XXX.datafix.schemas.V1466
+ XXX.datafix.schemas.V1470
- XXX.datafix.schemas.V1481
+ XXX.datafix.schemas.V1483
- XXX.datafix.schemas.V1486
+ XXX.datafix.schemas.V1510
- XXX.datafix.schemas.V1800
+ XXX.datafix.schemas.V1801
- XXX.datafix.schemas.V1904
+ XXX.datafix.schemas.V1906
- XXX.datafix.schemas.V1909
+ XXX.datafix.schemas.V1920
- XXX.datafix.schemas.V1928
+ XXX.datafix.schemas.V1929
- XXX.datafix.schemas.V1931
+ XXX.datafix.schemas.V2100
- XXX.datafix.schemas.V2501
+ XXX.datafix.schemas.V2502
- XXX.datafix.schemas.V2505
+ XXX.datafix.schemas.V2509
- XXX.datafix.schemas.V2519
+ XXX.datafix.schemas.V2522
- XXX.datafix.schemas.V2551
+ XXX.datafix.schemas.V2568
- XXX.datafix.schemas.V2571
+ XXX.datafix.schemas.V2684
- XXX.datafix.schemas.V2686
+ XXX.datafix.schemas.V2688
- XXX.datafix.schemas.V2704
+ XXX.datafix.schemas.V2707
- XXX.datafix.schemas.V2831
+ XXX.datafix.schemas.V2832
- XXX.datafix.schemas.V2842
+ XXX.datafix.schemas.V3076
- XXX.datafix.schemas.V3078
+ XXX.datafix.schemas.V3081
- XXX.datafix.schemas.V3082
+ XXX.datafix.schemas.V3083
- XXX.datafix.schemas.V3202
+ XXX.datafix.schemas.V3203
- XXX.datafix.schemas.V3204
+ XXX.datafix.schemas.V3325
- XXX.datafix.schemas.V3326
+ XXX.datafix.schemas.V3327
- XXX.datafix.schemas.V3328
+ XXX.datafix.schemas.V3438
+ XXX.enderdragon.phases.AbstractDragonPhaseInstance
- XXX.enderdragon.phases.AbstractDragonSittingPhase
+ XXX.enderdragon.phases.DragonChargePlayerPhase
- XXX.enderdragon.phases.DragonDeathPhase
+ XXX.enderdragon.phases.DragonHoldingPatternPhase
- XXX.enderdragon.phases.DragonHoverPhase
+ XXX.enderdragon.phases.DragonLandingApproachPhase
- XXX.enderdragon.phases.DragonLandingPhase
+ XXX.enderdragon.phases.DragonPhaseInstance
- XXX.enderdragon.phases.DragonSittingAttackingPhase
+ XXX.enderdragon.phases.DragonSittingFlamingPhase
- XXX.enderdragon.phases.DragonSittingScanningPhase
+ XXX.enderdragon.phases.DragonStrafePlayerPhase
- XXX.enderdragon.phases.DragonTakeoffPhase
+ XXX.enderdragon.phases.EnderDragonPhase
- XXX.enderdragon.phases.EnderDragonPhaseManager
+ XXX.enderdragon.phases.package-info
+ XXX.entity.animal.Bee$BeelooningGoal
+ XXX.entity.animal.Bee$MoveWithoutPathfindingGoal
- XXX.entity.animal.Bucketable
+ XXX.entity.animal.Cat
- XXX.entity.animal.Cat$CatAvoidEntityGoal
+ XXX.entity.animal.Cat$CatRelaxOnOwnerGoal
- XXX.entity.animal.Cat$CatTemptGoal
+ XXX.entity.animal.CatVariant
- XXX.entity.animal.Chicken
+ XXX.entity.animal.Cod
- XXX.entity.animal.Cow
+ XXX.entity.animal.Dolphin
- XXX.entity.animal.Dolphin$DolphinSwimToTreasureGoal
+ XXX.entity.animal.Dolphin$DolphinSwimWithPlayerGoal
- XXX.entity.animal.Dolphin$PlayWithItemsGoal
+ XXX.entity.animal.FlyingAnimal
- XXX.entity.animal.Fox
+ XXX.entity.animal.Fox$DefendTrustedTargetGoal
- XXX.entity.animal.Fox$FaceplantGoal
+ XXX.entity.animal.Fox$FoxAlertableEntitiesSelector
- XXX.entity.animal.Fox$FoxBehaviorGoal
+ XXX.entity.animal.Fox$FoxBreedGoal
- XXX.entity.animal.Fox$FoxEatBerriesGoal
+ XXX.entity.animal.Fox$FoxFloatGoal
- XXX.entity.animal.Fox$FoxFollowParentGoal
+ XXX.entity.animal.Fox$FoxGroupData
- XXX.entity.animal.Fox$FoxLookAtPlayerGoal
+ XXX.entity.animal.Fox$FoxLookControl
- XXX.entity.animal.Fox$FoxMeleeAttackGoal
+ XXX.entity.animal.Fox$FoxMoveControl
- XXX.entity.animal.Fox$FoxPanicGoal
+ XXX.entity.animal.Fox$FoxPounceGoal
- XXX.entity.animal.Fox$FoxSearchForItemsGoal
+ XXX.entity.animal.Fox$FoxStrollThroughVillageGoal
- XXX.entity.animal.Fox$PerchAndSearchGoal
+ XXX.entity.animal.Fox$SeekShelterGoal
- XXX.entity.animal.Fox$SleepGoal
+ XXX.entity.animal.Fox$StalkPreyGoal
- XXX.entity.animal.Fox$Type
+ XXX.entity.animal.FrogVariant
- XXX.entity.animal.IronGolem
+ XXX.entity.animal.IronGolem$Crackiness
+ XXX.entity.animal.MoonCow$MoonWalkControl
- XXX.entity.animal.MushroomCow
+ XXX.entity.animal.MushroomCow$MushroomType
- XXX.entity.animal.Ocelot
+ XXX.entity.animal.Ocelot$OcelotAvoidEntityGoal
- XXX.entity.animal.Ocelot$OcelotTemptGoal
+ XXX.entity.animal.package-info
+ XXX.entity.animal.Panda
- XXX.entity.animal.Panda$Gene
+ XXX.entity.animal.Panda$PandaAttackGoal
- XXX.entity.animal.Panda$PandaAvoidGoal
+ XXX.entity.animal.Panda$PandaBreedGoal
- XXX.entity.animal.Panda$PandaHurtByTargetGoal
+ XXX.entity.animal.Panda$PandaLieOnBackGoal
- XXX.entity.animal.Panda$PandaLookAtPlayerGoal
+ XXX.entity.animal.Panda$PandaMoveControl
- XXX.entity.animal.Panda$PandaPanicGoal
+ XXX.entity.animal.Panda$PandaRollGoal
- XXX.entity.animal.Panda$PandaSitGoal
+ XXX.entity.animal.Panda$PandaSneezeGoal
- XXX.entity.animal.Parrot
+ XXX.entity.animal.Parrot$1
- XXX.entity.animal.Parrot$ParrotWanderGoal
+ XXX.entity.animal.Parrot$Variant
- XXX.entity.animal.Pig
+ XXX.entity.animal.PolarBear
- XXX.entity.animal.PolarBear$PolarBearAttackPlayersGoal
+ XXX.entity.animal.PolarBear$PolarBearHurtByTargetGoal
- XXX.entity.animal.PolarBear$PolarBearMeleeAttackGoal
+ XXX.entity.animal.PolarBear$PolarBearPanicGoal
- XXX.entity.animal.Pufferfish
+ XXX.entity.animal.Pufferfish$PufferfishPuffGoal
- XXX.entity.animal.Rabbit
+ XXX.entity.animal.Rabbit$EvilRabbitAttackGoal
- XXX.entity.animal.Rabbit$RabbitAvoidEntityGoal
+ XXX.entity.animal.Rabbit$RabbitGroupData
- XXX.entity.animal.Rabbit$RabbitJumpControl
+ XXX.entity.animal.Rabbit$RabbitMoveControl
- XXX.entity.animal.Rabbit$RabbitPanicGoal
+ XXX.entity.animal.Rabbit$RaidGardenGoal
- XXX.entity.animal.Rabbit$Variant
+ XXX.entity.animal.Salmon
- XXX.entity.animal.Sheep
+ XXX.entity.animal.Sheep$1
- XXX.entity.animal.Sheep$2
+ XXX.entity.animal.ShoulderRidingEntity
- XXX.entity.animal.SnowGolem
+ XXX.entity.animal.Squid
- XXX.entity.animal.Squid$SquidFleeGoal
+ XXX.entity.animal.Squid$SquidRandomMovementGoal
- XXX.entity.animal.TropicalFish
+ XXX.entity.animal.TropicalFish$Base
- XXX.entity.animal.TropicalFish$Pattern
+ XXX.entity.animal.TropicalFish$TropicalFishGroupData
- XXX.entity.animal.TropicalFish$Variant
+ XXX.entity.animal.Turtle
- XXX.entity.animal.Turtle$TurtleBreedGoal
+ XXX.entity.animal.Turtle$TurtleGoHomeGoal
- XXX.entity.animal.Turtle$TurtleGoToWaterGoal
+ XXX.entity.animal.Turtle$TurtleLayEggGoal
- XXX.entity.animal.Turtle$TurtleMoveControl
+ XXX.entity.animal.Turtle$TurtlePanicGoal
- XXX.entity.animal.Turtle$TurtlePathNavigation
+ XXX.entity.animal.Turtle$TurtleRandomStrollGoal
- XXX.entity.animal.Turtle$TurtleTravelGoal
+ XXX.entity.animal.WaterAnimal
- XXX.entity.animal.Wolf
+ XXX.entity.animal.Wolf$WolfAvoidEntityGoal
- XXX.entity.animal.Wolf$WolfPanicGoal
+ XXX.entity.boss.EnderDragonPart
- XXX.entity.boss.package-info
- XXX.entity.decoration.ArmorStand
+ XXX.entity.decoration.ArmorStand$1
- XXX.entity.decoration.GlowItemFrame
+ XXX.entity.decoration.HangingEntity
- XXX.entity.decoration.HangingEntity$1
+ XXX.entity.decoration.ItemFrame
- XXX.entity.decoration.ItemFrame$1
+ XXX.entity.decoration.ItemFrame$2
- XXX.entity.decoration.LeashFenceKnotEntity
- XXX.entity.decoration.package-info
+ XXX.entity.decoration.Painting
- XXX.entity.decoration.PaintingVariant
+ XXX.entity.decoration.PaintingVariants
+ XXX.entity.item.FallingBlockEntity
- XXX.entity.item.ItemEntity
+ XXX.entity.item.ItemEntity$1
- XXX.entity.layers.ArrowLayer
+ XXX.entity.layers.BeeStingerLayer
+ XXX.entity.layers.CustomHeadLayer
- XXX.entity.layers.Deadmau5EarsLayer
+ XXX.entity.layers.DolphinCarryingItemLayer
- XXX.entity.layers.DrownedOuterLayer
+ XXX.entity.layers.ElytraLayer
- XXX.entity.layers.EnderEyesLayer
+ XXX.entity.layers.EnergySwirlLayer
- XXX.entity.layers.EyesLayer
+ XXX.entity.layers.FoxHeldItemLayer
- XXX.entity.layers.HorseArmorLayer
+ XXX.entity.layers.HorseMarkingLayer
- XXX.entity.layers.HumanoidArmorLayer
+ XXX.entity.layers.HumanoidArmorLayer$1
- XXX.entity.layers.IronGolemCrackinessLayer
+ XXX.entity.layers.IronGolemFlowerLayer
- XXX.entity.layers.ItemInHandLayer
+ XXX.entity.layers.LlamaDecorLayer
- XXX.entity.layers.MushroomCowMushroomLayer
+ XXX.entity.layers.MustacheLayer
- XXX.entity.layers.package-info
+ XXX.entity.layers.TropicalFishPatternLayer
- XXX.entity.layers.TropicalFishPatternLayer$1
+ XXX.entity.layers.VillagerProfessionLayer
- XXX.entity.layers.WardenEmissiveLayer
+ XXX.entity.layers.WardenEmissiveLayer$AlphaFunction
- XXX.entity.layers.WardenEmissiveLayer$DrawSelector
+ XXX.entity.layers.WitchItemLayer
- XXX.entity.layers.WitherArmorLayer
+ XXX.entity.layers.WolfCollarLayer
+ XXX.entity.monster.Shulker
- XXX.entity.monster.Shulker$ShulkerAttackGoal
+ XXX.entity.monster.Shulker$ShulkerBodyRotationControl
- XXX.entity.monster.Shulker$ShulkerDefenseAttackGoal
+ XXX.entity.monster.Shulker$ShulkerLookControl
- XXX.entity.monster.Shulker$ShulkerNearestAttackGoal
+ XXX.entity.monster.Shulker$ShulkerPeekGoal
- XXX.entity.monster.Silverfish
+ XXX.entity.monster.Silverfish$SilverfishMergeWithStoneGoal
- XXX.entity.monster.Silverfish$SilverfishWakeUpFriendsGoal
+ XXX.entity.monster.Skeleton
- XXX.entity.monster.Slime
+ XXX.entity.monster.Slime$SlimeAttackGoal
- XXX.entity.monster.Slime$SlimeFloatGoal
+ XXX.entity.monster.Slime$SlimeKeepOnJumpingGoal
- XXX.entity.monster.Slime$SlimeMoveControl
+ XXX.entity.monster.Slime$SlimeRandomDirectionGoal
- XXX.entity.monster.SpellcasterIllager
+ XXX.entity.monster.SpellcasterIllager$IllagerSpell
- XXX.entity.monster.SpellcasterIllager$SpellcasterCastingSpellGoal
+ XXX.entity.monster.SpellcasterIllager$SpellcasterUseSpellGoal
- XXX.entity.monster.Spider
+ XXX.entity.monster.Spider$SpiderAttackGoal
- XXX.entity.monster.Spider$SpiderEffectsGroupData
+ XXX.entity.monster.Spider$SpiderTargetGoal
- XXX.entity.monster.Stray
+ XXX.entity.monster.Strider
- XXX.entity.monster.Strider$StriderGoToLavaGoal
+ XXX.entity.monster.Strider$StriderPathNavigation
- XXX.entity.monster.Vex
+ XXX.entity.monster.Vex$VexChargeAttackGoal
- XXX.entity.monster.Vex$VexCopyOwnerTargetGoal
+ XXX.entity.monster.Vex$VexMoveControl
- XXX.entity.monster.Vex$VexRandomMoveGoal
+ XXX.entity.monster.Vindicator
- XXX.entity.monster.Vindicator$VindicatorBreakDoorGoal
+ XXX.entity.monster.Vindicator$VindicatorJohnnyAttackGoal
- XXX.entity.monster.Vindicator$VindicatorMeleeAttackGoal
+ XXX.entity.monster.Witch
- XXX.entity.monster.WitherSkeleton
+ XXX.entity.monster.Zoglin
- XXX.entity.monster.Zombie
+ XXX.entity.monster.Zombie$1
- XXX.entity.player.PlayerRenderer
+ XXX.entity.player.PlayerRenderer$PlayerArmorModel
+ XXX.entity.transform.EntityTransformType
+ XXX.entity.transform.TransformCommand
+ XXX.entity.vehicle.AbstractMinecart
- XXX.entity.vehicle.AbstractMinecart$1
+ XXX.entity.vehicle.AbstractMinecart$Type
- XXX.entity.vehicle.AbstractMinecartContainer
+ XXX.entity.vehicle.Boat
- XXX.entity.vehicle.Boat$1
+ XXX.entity.vehicle.Boat$Status
- XXX.entity.vehicle.Boat$Type
+ XXX.entity.vehicle.ChestBoat
- XXX.entity.vehicle.ChestBoat$1
+ XXX.entity.vehicle.ContainerEntity
- XXX.entity.vehicle.ContainerEntity$1
+ XXX.entity.vehicle.DismountHelper
- XXX.entity.vehicle.Minecart
+ XXX.entity.vehicle.MinecartChest
- XXX.entity.vehicle.MinecartCommandBlock
+ XXX.entity.vehicle.MinecartCommandBlock$MinecartCommandBase
- XXX.entity.vehicle.MinecartFurnace
+ XXX.entity.vehicle.MinecartHopper
- XXX.entity.vehicle.MinecartSpawner
+ XXX.entity.vehicle.MinecartSpawner$1
- XXX.entity.vehicle.MinecartTNT
+ XXX.entity.vehicle.package-info
- XXX.feature.configurations.BlockColumnConfiguration
+ XXX.feature.configurations.BlockColumnConfiguration$Layer
- XXX.feature.configurations.BlockPileConfiguration
+ XXX.feature.configurations.BlockStateConfiguration
- XXX.feature.configurations.ColumnFeatureConfiguration
+ XXX.feature.configurations.CountConfiguration
+ XXX.gametest.framework.AfterBatch
- XXX.gametest.framework.BeforeBatch
+ XXX.gametest.framework.ExhaustedAttemptsException
- XXX.gametest.framework.GameTest
+ XXX.gametest.framework.GameTestAssertException
- XXX.gametest.framework.GameTestAssertPosException
+ XXX.gametest.framework.GameTestBatch
- XXX.gametest.framework.GameTestBatchRunner
+ XXX.gametest.framework.GameTestBatchRunner$1
- XXX.gametest.framework.GameTestEvent
+ XXX.gametest.framework.GameTestGenerator
- XXX.gametest.framework.GameTestHelper
+ XXX.gametest.framework.GameTestHelper$1
- XXX.gametest.framework.GameTestHelper$2
+ XXX.gametest.framework.GameTestInfo
- XXX.gametest.framework.GameTestListener
+ XXX.gametest.framework.GameTestRegistry
- XXX.gametest.framework.GameTestRunner
+ XXX.gametest.framework.GameTestSequence
- XXX.gametest.framework.GameTestSequence$Condition
+ XXX.gametest.framework.GameTestServer
- XXX.gametest.framework.GameTestServer$1
+ XXX.gametest.framework.GameTestTicker
- XXX.gametest.framework.GameTestTimeoutException
+ XXX.gametest.framework.GlobalTestReporter
- XXX.gametest.framework.JUnitLikeTestReporter
+ XXX.gametest.framework.LogTestReporter
- XXX.gametest.framework.MultipleTestTracker
+ XXX.gametest.framework.MultipleTestTracker$1
- XXX.gametest.framework.package-info
- XXX.gametest.framework.ReportGameListener
+ XXX.gametest.framework.StructureUtils
- XXX.gametest.framework.StructureUtils$1
+ XXX.gametest.framework.TeamcityTestReporter
- XXX.gametest.framework.TestClassNameArgument
+ XXX.gametest.framework.TestCommand
- XXX.gametest.framework.TestCommand$TestSummaryDisplayer
+ XXX.gametest.framework.TestFunction
- XXX.gametest.framework.TestFunctionArgument
+ XXX.gametest.framework.TestReporter
- XXX.geom.builders.CubeDefinition
+ XXX.geom.builders.CubeDeformation
- XXX.geom.builders.CubeListBuilder
+ XXX.geom.builders.LayerDefinition
- XXX.geom.builders.MaterialDefinition
+ XXX.geom.builders.MeshDefinition
- XXX.geom.builders.package-info
- XXX.geom.builders.PartDefinition
+ XXX.geom.builders.UVPair
- XXX.gui.navigation.CommonInputs
+ XXX.gui.navigation.FocusNavigationEvent
- XXX.gui.navigation.FocusNavigationEvent$ArrowNavigation
+ XXX.gui.navigation.FocusNavigationEvent$InitialFocus
- XXX.gui.navigation.FocusNavigationEvent$TabNavigation
+ XXX.gui.navigation.package-info
+ XXX.gui.navigation.ScreenAxis
- XXX.gui.navigation.ScreenAxis$1
+ XXX.gui.navigation.ScreenDirection
- XXX.gui.navigation.ScreenDirection$1
+ XXX.gui.navigation.ScreenPosition
- XXX.gui.navigation.ScreenPosition$1
+ XXX.gui.navigation.ScreenRectangle
- XXX.gui.navigation.ScreenRectangle$1
+ XXX.gui.screens.AccessibilityOnboardingScreen
- XXX.gui.screens.AccessibilityOptionsScreen
+ XXX.gui.screens.AlertScreen
- XXX.gui.screens.BackupConfirmScreen
+ XXX.gui.screens.BackupConfirmScreen$Listener
- XXX.gui.screens.BanNoticeScreen
+ XXX.gui.screens.ChatOptionsScreen
- XXX.gui.screens.ChatScreen
+ XXX.gui.screens.ChatScreen$1
- XXX.gui.screens.ConfirmLinkScreen
+ XXX.gui.screens.ConfirmScreen
- XXX.gui.screens.ConnectScreen
+ XXX.gui.screens.ConnectScreen$1
- XXX.gui.screens.CreateBuffetWorldScreen
+ XXX.gui.screens.CreateBuffetWorldScreen$BiomeList
- XXX.gui.screens.CreateBuffetWorldScreen$BiomeList$Entry
+ XXX.gui.screens.CreateFlatWorldScreen
- XXX.gui.screens.CreateFlatWorldScreen$DetailsList
+ XXX.gui.screens.CreateFlatWorldScreen$DetailsList$Entry
- XXX.gui.screens.CreditsAndAttributionScreen
+ XXX.gui.screens.DatapackLoadFailureScreen
- XXX.gui.screens.DeathScreen
+ XXX.gui.screens.DeathScreen$TitleConfirmScreen
- XXX.gui.screens.DemoIntroScreen
+ XXX.gui.screens.DirectJoinServerScreen
- XXX.gui.screens.DisconnectedScreen
+ XXX.gui.screens.EditServerScreen
- XXX.gui.screens.ErrorScreen
+ XXX.gui.screens.GenericDirtMessageScreen
- XXX.gui.screens.GenericWaitingScreen
+ XXX.gui.screens.InBedChatScreen
- XXX.gui.screens.LanguageSelectScreen
+ XXX.gui.screens.LanguageSelectScreen$LanguageSelectionList
- XXX.gui.screens.LanguageSelectScreen$LanguageSelectionList$Entry
+ XXX.gui.screens.LevelLoadingScreen
- XXX.gui.screens.LoadingDotsText
+ XXX.gui.screens.LoadingOverlay
- XXX.gui.screens.LoadingOverlay$LogoTexture
+ XXX.gui.screens.MenuScreens
- XXX.gui.screens.MenuScreens$ScreenConstructor
+ XXX.gui.screens.MouseSettingsScreen
- XXX.gui.screens.OnlineOptionsScreen
+ XXX.gui.screens.OptionsScreen
- XXX.gui.screens.OptionsSubScreen
+ XXX.gui.screens.OutOfMemoryScreen
- XXX.gui.screens.Overlay
+ XXX.gui.screens.package-info
+ XXX.gui.screens.package-info
+ XXX.gui.screens.PauseScreen
- XXX.gui.screens.PopupScreen
+ XXX.gui.screens.PopupScreen$ButtonOption
- XXX.gui.screens.PresetFlatWorldScreen
+ XXX.gui.screens.PresetFlatWorldScreen$PresetsList
- XXX.gui.screens.PresetFlatWorldScreen$PresetsList$Entry
+ XXX.gui.screens.ProgressScreen
+ XXX.gui.screens.RealmsResetNormalWorldScreen
- XXX.gui.screens.RealmsResetWorldScreen
+ XXX.gui.screens.RealmsResetWorldScreen$1
- XXX.gui.screens.RealmsResetWorldScreen$FrameButton
+ XXX.gui.screens.RealmsSelectFileToUploadScreen
- XXX.gui.screens.RealmsSelectFileToUploadScreen$Entry
+ XXX.gui.screens.RealmsSelectFileToUploadScreen$WorldSelectionList
- XXX.gui.screens.RealmsSelectWorldTemplateScreen
+ XXX.gui.screens.RealmsSelectWorldTemplateScreen$1
- XXX.gui.screens.RealmsSelectWorldTemplateScreen$Entry
+ XXX.gui.screens.RealmsSelectWorldTemplateScreen$WorldTemplateObjectSelectionList
- XXX.gui.screens.RealmsSettingsScreen
+ XXX.gui.screens.RealmsSlotOptionsScreen
- XXX.gui.screens.RealmsSlotOptionsScreen$SettingsSlider
+ XXX.gui.screens.RealmsSubscriptionInfoScreen
- XXX.gui.screens.RealmsSubscriptionInfoScreen$1
+ XXX.gui.screens.RealmsTermsScreen
- XXX.gui.screens.RealmsUploadScreen
- XXX.gui.screens.ReceivingLevelScreen
+ XXX.gui.screens.Screen
- XXX.gui.screens.Screen$DeferredTooltipRendering
+ XXX.gui.screens.Screen$NarratableSearchResult
- XXX.gui.screens.ShareToLanScreen
+ XXX.gui.screens.SimpleOptionsSubScreen
- XXX.gui.screens.SkinCustomizationScreen
+ XXX.gui.screens.SoundOptionsScreen
+ XXX.gui.screens.SuperSimpleTextScreen
+ XXX.gui.screens.SuperSimpleTextScreen$SimpleTextList$Entry
- XXX.gui.screens.TitleScreen
+ XXX.gui.screens.TitleScreen$WarningLabel
+ XXX.gui.screens.UploadResult
- XXX.gui.screens.UploadResult$Builder
- XXX.gui.screens.VideoSettingsScreen
+ XXX.gui.screens.WinScreen
- XXX.gui.screens.WinScreen$CreditsReader
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
- XXX.inventory.tooltip.BelowOrAboveWidgetTooltipPositioner
+ XXX.inventory.tooltip.ClientBundleTooltip
- XXX.inventory.tooltip.ClientBundleTooltip$Texture
+ XXX.inventory.tooltip.ClientTextTooltip
- XXX.inventory.tooltip.ClientTooltipComponent
+ XXX.inventory.tooltip.ClientTooltipPositioner
- XXX.inventory.tooltip.DefaultTooltipPositioner
+ XXX.inventory.tooltip.MenuTooltipPositioner
- XXX.inventory.tooltip.package-info
- XXX.inventory.tooltip.TooltipRenderUtil
+ XXX.inventory.tooltip.TooltipRenderUtil$BlitPainter
+ XXX.item.alchemy.package-info
- XXX.item.alchemy.Potion
+ XXX.item.alchemy.PotionBrewing
- XXX.item.alchemy.PotionBrewing$Mix
- XXX.item.alchemy.Potions
+ XXX.item.alchemy.PotionUtils
- XXX.item.armortrim.ArmorTrim
+ XXX.item.armortrim.package-info
+ XXX.item.armortrim.TrimMaterial
- XXX.item.armortrim.TrimMaterials
+ XXX.item.armortrim.TrimPattern
- XXX.item.armortrim.TrimPatterns
- XXX.item.context.BlockPlaceContext
+ XXX.item.context.DirectionalPlaceContext
- XXX.item.context.DirectionalPlaceContext$1
+ XXX.item.context.PlaceBlockBlockPlaceContext
+ XXX.item.crafting.DupeHackRecipe
- XXX.item.crafting.FireworkRocketRecipe
+ XXX.item.crafting.FireworkStarFadeRecipe
- XXX.item.crafting.FireworkStarRecipe
+ XXX.item.crafting.Ingredient
- XXX.item.crafting.Ingredient$ItemValue
+ XXX.item.crafting.Ingredient$TagValue
- XXX.item.crafting.Ingredient$Value
+ XXX.item.crafting.MapCloningRecipe
- XXX.item.crafting.MapExtendingRecipe
+ XXX.item.crafting.NbtCraftingRecipe
- XXX.level.biome.package-info
+ XXX.level.biome.TheMoonBiomeSource
+ XXX.level.block.AbstractBannerBlock
- XXX.level.block.AbstractCandleBlock
+ XXX.level.block.AbstractCauldronBlock
- XXX.level.block.AbstractChestBlock
+ XXX.level.block.AbstractFurnaceBlock
- XXX.level.block.AbstractGlassBlock
+ XXX.level.block.AbstractSkullBlock
- XXX.level.block.AirBlock
+ XXX.level.block.AmethystBlock
- XXX.level.block.AmethystClusterBlock
+ XXX.level.block.AmethystClusterBlock$1
- XXX.level.block.AnvilBlock
+ XXX.level.block.AttachedStemBlock
- XXX.level.block.AzaleaBlock
+ XXX.level.block.BambooSaplingBlock
- XXX.level.block.BambooStalkBlock
+ XXX.level.block.BannerBlock
- XXX.level.block.BarrelBlock
+ XXX.level.block.BarrierBlock
- XXX.level.block.BaseCoralFanBlock
+ XXX.level.block.BaseCoralPlantBlock
- XXX.level.block.BaseCoralPlantTypeBlock
+ XXX.level.block.BaseCoralWallFanBlock
- XXX.level.block.BaseEntityBlock
+ XXX.level.block.BaseFireBlock
- XXX.level.block.BasePressurePlateBlock
+ XXX.level.block.BaseRailBlock
- XXX.level.block.BaseRailBlock$1
+ XXX.level.block.BeaconBeamBlock
- XXX.level.block.BeaconBlock
+ XXX.level.block.BedBlock
- XXX.level.block.BedBlock$1
+ XXX.level.block.BeehiveBlock
- XXX.level.block.BeetrootBlock
+ XXX.level.block.BellBlock
- XXX.level.block.BellBlock$1
+ XXX.level.block.BigDripleafBlock
- XXX.level.block.BigDripleafStemBlock
+ XXX.level.block.BigDripleafStemBlock$1
- XXX.level.block.BlastFurnaceBlock
+ XXX.level.block.Block
- XXX.level.block.Block$1
+ XXX.level.block.Block$2
- XXX.level.block.Block$BlockStatePairKey
+ XXX.level.block.Blocks
- XXX.level.block.BonemealableBlock
+ XXX.level.block.BrewingStandBlock
- XXX.level.block.BrushableBlock
+ XXX.level.block.BubbleColumnBlock
- XXX.level.block.BucketPickup
+ XXX.level.block.BuddingAmethystBlock
- XXX.level.block.BushBlock
+ XXX.level.block.ButtonBlock
- XXX.level.block.ButtonBlock$1
+ XXX.level.block.CactusBlock
- XXX.level.block.CakeBlock
+ XXX.level.block.CalibratedSculkSensorBlock
- XXX.level.block.CampfireBlock
+ XXX.level.block.CandleBlock
- XXX.level.block.CandleCakeBlock
+ XXX.level.block.CarpetBlock
- XXX.level.block.CarrotBlock
+ XXX.level.block.CartographyTableBlock
- XXX.level.block.CarvedPumpkinBlock
+ XXX.level.block.CauldronBlock
- XXX.level.block.CaveVines
+ XXX.level.block.CaveVinesBlock
- XXX.level.block.CaveVinesPlantBlock
+ XXX.level.block.CeilingHangingSignBlock
- XXX.level.block.ChainBlock
+ XXX.level.block.ChainBlock$1
- XXX.level.block.ChangeOverTimeBlock
+ XXX.level.block.CheeseBlock
+ XXX.level.block.CopperSinkBlock
- XXX.level.block.CoralBlock
+ XXX.level.block.CoralFanBlock
- XXX.level.block.CoralPlantBlock
+ XXX.level.block.CoralWallFanBlock
- XXX.level.block.CraftingTableBlock
+ XXX.level.block.CropBlock
- XXX.level.block.CrossCollisionBlock
+ XXX.level.block.CrossCollisionBlock$1
- XXX.level.block.CryingObsidianBlock
+ XXX.level.block.DaylightDetectorBlock
- XXX.level.block.DeadBushBlock
+ XXX.level.block.DecoratedPotBlock
- XXX.level.block.DetectorRailBlock
+ XXX.level.block.DetectorRailBlock$1
- XXX.level.block.DiodeBlock
+ XXX.level.block.DirectionalBlock
- XXX.level.block.DirtPathBlock
+ XXX.level.block.DispenserBlock
- XXX.level.block.DoorBlock
+ XXX.level.block.DoorBlock$1
- XXX.level.block.DoubleBlockCombiner
+ XXX.level.block.DoubleBlockCombiner$BlockType
- XXX.level.block.DoubleBlockCombiner$Combiner
+ XXX.level.block.DoubleBlockCombiner$NeighborCombineResult
- XXX.level.block.DoubleBlockCombiner$NeighborCombineResult$Double
+ XXX.level.block.DoubleBlockCombiner$NeighborCombineResult$Single
- XXX.level.block.DoublePlantBlock
+ XXX.level.block.DragonEggBlock
- XXX.level.block.DropExperienceBlock
+ XXX.level.block.DropperBlock
- XXX.level.block.EnchantmentTableBlock
+ XXX.level.block.EnderChestBlock
+ XXX.level.block.EndGatewayBlock
- XXX.level.block.EndPortalBlock
+ XXX.level.block.EndPortalFrameBlock
- XXX.level.block.EndRodBlock
- XXX.level.block.EntityBlock
+ XXX.level.block.FaceAttachedHorizontalDirectionalBlock
- XXX.level.block.FaceAttachedHorizontalDirectionalBlock$1
+ XXX.level.block.FacingTriggerableBlock
- XXX.level.block.FarmableBlock
+ XXX.level.block.FenceBlock
- XXX.level.block.FenceGateBlock
+ XXX.level.block.FenceGateBlock$1
+ XXX.level.block.PickaxeBlock
+ XXX.level.block.PlayerHeadBlock
- XXX.level.block.PlayerWallHeadBlock
+ XXX.level.block.PointedDripstoneBlock
- XXX.level.block.PointedDripstoneBlock$FluidInfo
+ XXX.level.block.PotatoBlock
- XXX.level.block.PowderSnowBlock
+ XXX.level.block.PowderSnowCauldronBlock
- XXX.level.block.PoweredBlock
+ XXX.level.block.PoweredRailBlock
- XXX.level.block.PoweredRailBlock$1
+ XXX.level.block.PressurePlateBlock
- XXX.level.block.PressurePlateBlock$1
+ XXX.level.block.PressurePlateBlock$Sensitivity
- XXX.level.block.PumpkinBlock
+ XXX.level.block.RailBlock
- XXX.level.block.RailBlock$1
+ XXX.level.block.RailState
- XXX.level.block.RailState$1
- XXX.level.block.RedstoneLampBlock
+ XXX.level.block.RedStoneOreBlock
+ XXX.level.block.RedstoneTorchBlock
- XXX.level.block.RedstoneTorchBlock$Toggle
+ XXX.level.block.RedstoneWallTorchBlock
- XXX.level.block.RedStoneWireBlock
+ XXX.level.block.RedStoneWireBlock$1
- XXX.level.block.RenderShape
+ XXX.level.block.RepeaterBlock
- XXX.level.block.RespawnAnchorBlock
+ XXX.level.block.RespawnAnchorBlock$1
- XXX.level.block.RodBlock
+ XXX.level.block.RodBlock$1
- XXX.level.block.RootedDirtBlock
+ XXX.level.block.RootsBlock
- XXX.level.block.RotatedPillarBlock
+ XXX.level.block.RotatedPillarBlock$1
- XXX.level.block.Rotation
+ XXX.level.block.Rotation$1
- XXX.level.block.SandBlock
+ XXX.level.block.SaplingBlock
- XXX.level.block.ScaffoldingBlock
+ XXX.level.block.SculkBehaviour
- XXX.level.block.SculkBehaviour$1
+ XXX.level.block.SculkBlock
- XXX.level.block.SculkCatalystBlock
+ XXX.level.block.SculkSensorBlock
- XXX.level.block.SculkShriekerBlock
+ XXX.level.block.SculkSpreader
- XXX.level.block.SculkSpreader$ChargeCursor
+ XXX.level.block.SculkVeinBlock
- XXX.level.block.SculkVeinBlock$SculkVeinSpreaderConfig
- XXX.level.block.SeagrassBlock
+ XXX.level.block.SeaPickleBlock
+ XXX.level.block.ShulkerBoxBlock
- XXX.level.block.ShulkerBoxBlock$1
+ XXX.level.block.SignBlock
- XXX.level.block.SimpleWaterloggedBlock
+ XXX.level.block.SkullBlock
- XXX.level.block.SkullBlock$Type
+ XXX.level.block.SkullBlock$Types
- XXX.level.block.SlabBlock
+ XXX.level.block.SlabBlock$1
- XXX.level.block.SlimeBlock
+ XXX.level.block.SmallDripleafBlock
- XXX.level.block.SmithingTableBlock
+ XXX.level.block.SmokerBlock
- XXX.level.block.SnifferEggBlock
+ XXX.level.block.SnowLayerBlock
- XXX.level.block.SnowLayerBlock$1
+ XXX.level.block.SnowyDirtBlock
- XXX.level.block.SoulFireBlock
+ XXX.level.block.SoulSandBlock
- XXX.level.block.SoundType
+ XXX.level.block.SpawnerBlock
+ XXX.level.levelgen.MoonBaseBuilder$1
+ XXX.level.levelgen.NoiseBasedChunkGenerator
- XXX.level.levelgen.NoiseChunk
+ XXX.level.levelgen.NoiseChunk$1
- XXX.level.levelgen.NoiseChunk$2
+ XXX.level.levelgen.NoiseChunk$BlendAlpha
- XXX.level.levelgen.NoiseChunk$BlendOffset
+ XXX.level.levelgen.NoiseChunk$BlockStateFiller
- XXX.level.levelgen.NoiseChunk$Cache2D
+ XXX.level.levelgen.NoiseChunk$CacheAllInCell
- XXX.level.levelgen.NoiseChunk$CacheOnce
+ XXX.level.levelgen.NoiseChunk$FlatCache
- XXX.level.levelgen.NoiseChunk$NoiseChunkDensityFunction
+ XXX.level.levelgen.NoiseChunk$NoiseInterpolator
- XXX.level.levelgen.NoiseGeneratorSettings
+ XXX.level.levelgen.NoiseRouter
- XXX.level.levelgen.NoiseRouterData
+ XXX.level.levelgen.NoiseRouterData$QuantizedSpaghettiRarity
+ XXX.level.levelgen.Noises
- XXX.level.levelgen.NoiseSettings
- XXX.level.levelgen.OreVeinifier
+ XXX.level.levelgen.OreVeinifier$VeinType
- XXX.level.levelgen.PatrolSpawner
+ XXX.level.levelgen.PhantomSpawner
- XXX.level.levelgen.PositionalRandomFactory
+ XXX.level.levelgen.RandomState
- XXX.level.levelgen.RandomState$1
+ XXX.level.levelgen.RandomState$1NoiseWiringHelper
- XXX.level.levelgen.RandomSupport
+ XXX.level.levelgen.RandomSupport$Seed128bit
- XXX.level.levelgen.SingleThreadedRandomSource
+ XXX.level.levelgen.SurfaceRules
- XXX.level.levelgen.SurfaceRules$AbovePreliminarySurface
+ XXX.level.levelgen.SurfaceRules$Bandlands
- XXX.level.levelgen.SurfaceRules$BiomeConditionSource
+ XXX.level.levelgen.SurfaceRules$BiomeConditionSource$1BiomeCondition
- XXX.level.levelgen.SurfaceRules$BlockRuleSource
+ XXX.level.levelgen.SurfaceRules$Condition
- XXX.level.levelgen.SurfaceRules$ConditionSource
+ XXX.level.levelgen.SurfaceRules$Context
- XXX.level.levelgen.SurfaceRules$Context$AbovePreliminarySurfaceCondition
+ XXX.level.levelgen.SurfaceRules$Context$HoleCondition
- XXX.level.levelgen.SurfaceRules$Context$SteepMaterialCondition
+ XXX.level.levelgen.SurfaceRules$Context$TemperatureHelperCondition
- XXX.level.levelgen.SurfaceRules$Hole
+ XXX.level.levelgen.SurfaceRules$LazyCondition
- XXX.level.levelgen.SurfaceRules$LazyXZCondition
+ XXX.level.levelgen.SurfaceRules$LazyYCondition
- XXX.level.levelgen.SurfaceRules$NoiseThresholdConditionSource
+ XXX.level.levelgen.SurfaceRules$NoiseThresholdConditionSource$1NoiseThresholdCondition
- XXX.level.levelgen.SurfaceRules$NotCondition
+ XXX.level.levelgen.SurfaceRules$NotConditionSource
- XXX.level.levelgen.SurfaceRules$RuleSource
+ XXX.level.levelgen.SurfaceRules$SequenceRule
- XXX.level.levelgen.SurfaceRules$SequenceRuleSource
+ XXX.level.levelgen.SurfaceRules$StateRule
- XXX.level.levelgen.SurfaceRules$Steep
+ XXX.level.levelgen.SurfaceRules$StoneDepthCheck
- XXX.level.levelgen.SurfaceRules$StoneDepthCheck$1StoneDepthCondition
+ XXX.level.levelgen.SurfaceRules$SurfaceRule
- XXX.level.levelgen.SurfaceRules$Temperature
+ XXX.level.levelgen.SurfaceRules$TestRule
- XXX.level.levelgen.SurfaceRules$TestRuleSource
+ XXX.level.levelgen.SurfaceRules$VerticalGradientConditionSource
- XXX.level.levelgen.SurfaceRules$VerticalGradientConditionSource$1VerticalGradientCondition
+ XXX.level.levelgen.SurfaceRules$WaterConditionSource
- XXX.level.levelgen.SurfaceRules$WaterConditionSource$1WaterCondition
+ XXX.level.levelgen.SurfaceRules$YConditionSource
- XXX.level.levelgen.SurfaceRules$YConditionSource$1YCondition
+ XXX.level.levelgen.SurfaceSystem
- XXX.level.levelgen.SurfaceSystem$1
+ XXX.level.levelgen.ThreadSafeLegacyRandomSource
- XXX.level.levelgen.VerticalAnchor
+ XXX.level.levelgen.VerticalAnchor$AboveBottom
- XXX.level.levelgen.VerticalAnchor$Absolute
+ XXX.level.levelgen.VerticalAnchor$BelowTop
- XXX.level.levelgen.WorldDimensions
+ XXX.level.levelgen.WorldDimensions$1Entry
- XXX.level.levelgen.WorldDimensions$Complete
- XXX.level.levelgen.WorldGenerationContext
- XXX.level.levelgen.WorldgenRandom
+ XXX.level.levelgen.WorldgenRandom$Algorithm
+ XXX.level.levelgen.WorldGenSettings
+ XXX.level.levelgen.WorldOptions
- XXX.level.levelgen.Xoroshiro128PlusPlus
+ XXX.level.levelgen.XoroshiroRandomSource
- XXX.level.levelgen.XoroshiroRandomSource$XoroshiroPositionalRandomFactory
+ XXX.levelgen.blending.Blender
- XXX.levelgen.blending.Blender$1
+ XXX.levelgen.blending.Blender$BlendingOutput
- XXX.levelgen.blending.Blender$CellValueGetter
+ XXX.levelgen.blending.Blender$DistanceGetter
- XXX.levelgen.blending.BlendingData
+ XXX.levelgen.blending.BlendingData$BiomeConsumer
- XXX.levelgen.blending.BlendingData$DensityConsumer
+ XXX.levelgen.blending.BlendingData$HeightConsumer
- XXX.levelgen.blending.package-info
+ XXX.levelgen.blockpredicates.AllOfPredicate
- XXX.levelgen.blockpredicates.AnyOfPredicate
+ XXX.levelgen.blockpredicates.BlockPredicate
- XXX.levelgen.blockpredicates.BlockPredicateType
+ XXX.levelgen.blockpredicates.CombiningPredicate
- XXX.levelgen.blockpredicates.HasSturdyFacePredicate
+ XXX.levelgen.blockpredicates.InsideWorldBoundsPredicate
+ XXX.levelgen.blockpredicates.MatchingBlocksPredicate
- XXX.levelgen.blockpredicates.MatchingBlockTagPredicate
- XXX.levelgen.blockpredicates.MatchingFluidsPredicate
+ XXX.levelgen.blockpredicates.NotPredicate
+ XXX.levelgen.blockpredicates.package-info
- XXX.levelgen.blockpredicates.ReplaceablePredicate
+ XXX.levelgen.blockpredicates.SolidPredicate
- XXX.levelgen.blockpredicates.StateTestingPredicate
+ XXX.levelgen.blockpredicates.TrueBlockPredicate
- XXX.levelgen.blockpredicates.WouldSurvivePredicate
- XXX.levelgen.carver.CanyonCarverConfiguration
+ XXX.levelgen.carver.CanyonCarverConfiguration$CanyonShapeConfiguration
- XXX.levelgen.carver.CanyonWorldCarver
+ XXX.levelgen.carver.CarverConfiguration
- XXX.levelgen.carver.CarverDebugSettings
+ XXX.levelgen.carver.CarvingContext
- XXX.levelgen.carver.CaveCarverConfiguration
+ XXX.levelgen.carver.CaveWorldCarver
- XXX.levelgen.carver.ConfiguredWorldCarver
+ XXX.levelgen.carver.NetherWorldCarver
- XXX.levelgen.carver.package-info
- XXX.levelgen.carver.WorldCarver
+ XXX.levelgen.carver.WorldCarver$CarveSkipChecker
+ XXX.levelgen.feature.AbstractHugeMushroomFeature
- XXX.levelgen.feature.BambooFeature
+ XXX.levelgen.feature.BasaltColumnsFeature
- XXX.levelgen.feature.BasaltPillarFeature
+ XXX.levelgen.feature.BlockBlobFeature
- XXX.levelgen.feature.BlockColumnFeature
+ XXX.levelgen.feature.BlockPileFeature
- XXX.levelgen.feature.BlueIceFeature
+ XXX.levelgen.feature.BonusChestFeature
- XXX.levelgen.feature.ChorusPlantFeature
+ XXX.levelgen.feature.ConfiguredFeature
- XXX.levelgen.feature.CoralClawFeature
+ XXX.levelgen.feature.CoralFeature
- XXX.levelgen.feature.CoralMushroomFeature
+ XXX.levelgen.feature.CoralTreeFeature
+ XXX.levelgen.feature.MonsterRoomFeature
- XXX.levelgen.feature.MultifaceGrowthFeature
+ XXX.levelgen.feature.NetherForestVegetationFeature
- XXX.levelgen.feature.NoOpFeature
+ XXX.levelgen.feature.OreFeature
- XXX.levelgen.feature.PointedDripstoneFeature
+ XXX.levelgen.feature.RandomBooleanSelectorFeature
- XXX.levelgen.feature.RandomPatchFeature
+ XXX.levelgen.feature.RandomSelectorFeature
- XXX.levelgen.feature.ReplaceBlobsFeature
+ XXX.levelgen.feature.ReplaceBlockFeature
- XXX.levelgen.feature.RootSystemFeature
+ XXX.levelgen.feature.ScatteredOreFeature
- XXX.levelgen.feature.SculkPatchFeature
- XXX.levelgen.feature.SeagrassFeature
+ XXX.levelgen.feature.SeaPickleFeature
+ XXX.levelgen.feature.SimpleBlockFeature
- XXX.levelgen.feature.SimpleRandomSelectorFeature
+ XXX.levelgen.feature.SnowAndFreezeFeature
- XXX.levelgen.feature.SpikeFeature
+ XXX.levelgen.feature.SpikeFeature$EndSpike
- XXX.levelgen.feature.SpikeFeature$SpikeCacheLoader
+ XXX.levelgen.feature.SpringFeature
- XXX.levelgen.feature.TreeFeature
+ XXX.levelgen.feature.TreeFeature$1
- XXX.levelgen.feature.TwistingVinesFeature
+ XXX.levelgen.feature.UnderwaterMagmaFeature
- XXX.levelgen.feature.VegetationPatchFeature
+ XXX.levelgen.feature.VinesFeature
- XXX.levelgen.feature.VoidStartPlatformFeature
+ XXX.levelgen.feature.WaterloggedVegetationPatchFeature
- XXX.levelgen.feature.WeepingVinesFeature
+ XXX.levelgen.feature.WeightedPlacedFeature
- XXX.loot.functions.FunctionReference
- XXX.minecraft.advancements.Advancement
+ XXX.minecraft.advancements.Advancement$Builder
- XXX.minecraft.advancements.AdvancementList
+ XXX.minecraft.advancements.AdvancementList$Listener
- XXX.minecraft.advancements.AdvancementProgress
+ XXX.minecraft.advancements.AdvancementProgress$Serializer
- XXX.minecraft.advancements.AdvancementRewards
+ XXX.minecraft.advancements.AdvancementRewards$Builder
- XXX.minecraft.advancements.CriteriaTriggers
+ XXX.minecraft.advancements.Criterion
- XXX.minecraft.advancements.CriterionProgress
+ XXX.minecraft.advancements.CriterionTrigger
- XXX.minecraft.advancements.CriterionTrigger$Listener
+ XXX.minecraft.advancements.CriterionTriggerInstance
- XXX.minecraft.advancements.DisplayInfo
+ XXX.minecraft.advancements.FrameType
+ XXX.minecraft.advancements.package-info
- XXX.minecraft.advancements.RequirementsStrategy
+ XXX.minecraft.advancements.TreeNodePosition
- XXX.minecraft.client.AttackIndicatorStatus
+ XXX.minecraft.client.Camera
- XXX.minecraft.client.Camera$NearPlane
+ XXX.minecraft.client.CameraType
- XXX.minecraft.client.ClientBrandRetriever
+ XXX.minecraft.client.ClientRecipeBook
- XXX.minecraft.client.ClientRecipeBook$1
+ XXX.minecraft.client.CloudStatus
- XXX.minecraft.client.ComponentCollector
+ XXX.minecraft.client.DebugQueryHandler
- XXX.minecraft.client.GameNarrator
+ XXX.minecraft.client.GraphicsStatus
- XXX.minecraft.client.GraphicsStatus$1
+ XXX.minecraft.client.GuiMessage
- XXX.minecraft.client.GuiMessage$Line
+ XXX.minecraft.client.GuiMessageTag
- XXX.minecraft.client.GuiMessageTag$Icon
+ XXX.minecraft.client.HotbarManager
- XXX.minecraft.client.InputType
- XXX.minecraft.client.KeyboardHandler
+ XXX.minecraft.client.KeyboardHandler$1
+ XXX.minecraft.client.KeyMapping
- XXX.minecraft.client.Minecraft
+ XXX.minecraft.client.Minecraft$1
- XXX.minecraft.client.Minecraft$ChatStatus
+ XXX.minecraft.client.Minecraft$ChatStatus$1
- XXX.minecraft.client.Minecraft$ChatStatus$2
+ XXX.minecraft.client.Minecraft$ChatStatus$3
- XXX.minecraft.client.Minecraft$ChatStatus$4
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
- XXX.minecraft.client.Options$FieldAccess
- XXX.minecraft.client.package-info
+ XXX.minecraft.client.ParticleStatus
- XXX.minecraft.client.PeriodicNotificationManager
+ XXX.minecraft.client.PeriodicNotificationManager$Notification
- XXX.minecraft.client.PeriodicNotificationManager$NotificationTask
+ XXX.minecraft.client.PrioritizeChunkUpdates
- XXX.minecraft.client.Realms32BitWarningStatus
+ XXX.minecraft.client.RecipeBookCategories
- XXX.minecraft.client.RecipeBookCategories$1
+ XXX.minecraft.client.ResourceLoadStateTracker
- XXX.minecraft.client.ResourceLoadStateTracker$RecoveryInfo
+ XXX.minecraft.client.ResourceLoadStateTracker$ReloadReason
- XXX.minecraft.client.ResourceLoadStateTracker$ReloadState
+ XXX.minecraft.client.Screenshot
- XXX.minecraft.client.StringSplitter
+ XXX.minecraft.client.StringSplitter$1
- XXX.minecraft.client.StringSplitter$FlatComponents
+ XXX.minecraft.client.StringSplitter$LineBreakFinder
- XXX.minecraft.client.StringSplitter$LineComponent
+ XXX.minecraft.client.StringSplitter$LinePosConsumer
- XXX.minecraft.client.StringSplitter$WidthLimitedCharSink
+ XXX.minecraft.client.StringSplitter$WidthProvider
- XXX.minecraft.client.Timer
+ XXX.minecraft.client.ToggleKeyMapping
- XXX.minecraft.client.User
+ XXX.minecraft.client.User$Type
- XXX.minecraft.commands.BrigadierExceptions
+ XXX.minecraft.commands.CommandBuildContext
- XXX.minecraft.commands.CommandBuildContext$1
+ XXX.minecraft.commands.CommandBuildContext$2
- XXX.minecraft.commands.CommandBuildContext$2$1
+ XXX.minecraft.commands.CommandBuildContext$3
- XXX.minecraft.commands.CommandBuildContext$Configurable
+ XXX.minecraft.commands.CommandBuildContext$MissingTagAccessPolicy
- XXX.minecraft.commands.CommandFunction
+ XXX.minecraft.commands.CommandFunction$CacheableFunction
- XXX.minecraft.commands.CommandFunction$CommandEntry
+ XXX.minecraft.commands.CommandFunction$Entry
- XXX.minecraft.commands.CommandFunction$FunctionEntry
+ XXX.minecraft.commands.CommandRuntimeException
- XXX.minecraft.commands.Commands
+ XXX.minecraft.commands.Commands$1
- XXX.minecraft.commands.Commands$1$1
+ XXX.minecraft.commands.Commands$CommandSelection
- XXX.minecraft.commands.Commands$ParseFunction
- XXX.minecraft.commands.CommandSigningContext
+ XXX.minecraft.commands.CommandSigningContext$1
- XXX.minecraft.commands.CommandSigningContext$SignedArguments
+ XXX.minecraft.commands.CommandSource
- XXX.minecraft.commands.CommandSource$1
+ XXX.minecraft.commands.CommandSourceStack
- XXX.minecraft.commands.package-info
+ XXX.minecraft.commands.SharedSuggestionProvider
- XXX.minecraft.commands.SharedSuggestionProvider$ElementSuggestionType
+ XXX.minecraft.commands.SharedSuggestionProvider$TextCoordinates
- XXX.minecraft.core.AxisCycle
+ XXX.minecraft.core.AxisCycle$1
- XXX.minecraft.core.AxisCycle$2
+ XXX.minecraft.core.AxisCycle$3
- XXX.minecraft.core.BlockMath
+ XXX.minecraft.core.BlockPos
- XXX.minecraft.core.BlockPos$1
+ XXX.minecraft.core.BlockPos$2
- XXX.minecraft.core.BlockPos$3
+ XXX.minecraft.core.BlockPos$4
- XXX.minecraft.core.BlockPos$5
+ XXX.minecraft.core.BlockPos$MutableBlockPos
- XXX.minecraft.core.BlockSource
+ XXX.minecraft.core.BlockSourceImpl
- XXX.minecraft.core.Cursor3D
+ XXX.minecraft.core.DefaultedMappedRegistry
- XXX.minecraft.core.DefaultedRegistry
+ XXX.minecraft.core.Direction
- XXX.minecraft.core.Direction$1
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
- XXX.minecraft.core.HolderLookup$1
+ XXX.minecraft.core.HolderLookup$Delegate
- XXX.minecraft.core.HolderLookup$Provider
+ XXX.minecraft.core.HolderLookup$Provider$1
- XXX.minecraft.core.HolderLookup$Provider$2
+ XXX.minecraft.core.HolderLookup$RegistryLookup
- XXX.minecraft.core.HolderLookup$RegistryLookup$Delegate
+ XXX.minecraft.core.HolderOwner
- XXX.minecraft.core.HolderSet
+ XXX.minecraft.core.HolderSet$Direct
- XXX.minecraft.core.HolderSet$ListBacked
+ XXX.minecraft.core.HolderSet$Named
- XXX.minecraft.core.IdMap
+ XXX.minecraft.core.IdMapper
- XXX.minecraft.core.LayeredRegistryAccess
+ XXX.minecraft.core.MappedRegistry
- XXX.minecraft.core.MappedRegistry$1
+ XXX.minecraft.core.MappedRegistry$2
- XXX.minecraft.core.NonNullList
+ XXX.minecraft.core.package-info
+ XXX.minecraft.core.Position
- XXX.minecraft.core.PositionImpl
+ XXX.minecraft.core.QuartPos
- XXX.minecraft.core.Registry
+ XXX.minecraft.core.Registry$1
- XXX.minecraft.core.Registry$2
+ XXX.minecraft.core.RegistryAccess
- XXX.minecraft.core.RegistryAccess$1
+ XXX.minecraft.core.RegistryAccess$1FrozenAccess
- XXX.minecraft.core.RegistryAccess$Frozen
+ XXX.minecraft.core.RegistryAccess$ImmutableRegistryAccess
- XXX.minecraft.core.RegistryAccess$RegistryEntry
+ XXX.minecraft.core.RegistryCodecs
- XXX.minecraft.core.RegistryCodecs$RegistryEntry
+ XXX.minecraft.core.RegistrySetBuilder
- XXX.minecraft.core.RegistrySetBuilder$1
+ XXX.minecraft.core.RegistrySetBuilder$BuildState
- XXX.minecraft.core.RegistrySetBuilder$BuildState$1
+ XXX.minecraft.core.RegistrySetBuilder$CompositeOwner
- XXX.minecraft.core.RegistrySetBuilder$EmptyTagLookup
+ XXX.minecraft.core.RegistrySetBuilder$RegisteredValue
- XXX.minecraft.core.RegistrySetBuilder$RegistryBootstrap
+ XXX.minecraft.core.RegistrySetBuilder$RegistryContents
- XXX.minecraft.core.RegistrySetBuilder$RegistryContents$1
+ XXX.minecraft.core.RegistrySetBuilder$RegistryStub
- XXX.minecraft.core.RegistrySetBuilder$UniversalLookup
+ XXX.minecraft.core.RegistrySetBuilder$ValueAndHolder
- XXX.minecraft.core.RegistrySynchronization
+ XXX.minecraft.core.RegistrySynchronization$NetworkedRegistryData
- XXX.minecraft.core.Rotations
+ XXX.minecraft.core.SectionPos
- XXX.minecraft.core.SectionPos$1
+ XXX.minecraft.core.UUIDUtil
- XXX.minecraft.core.Vec3i
+ XXX.minecraft.core.WritableRegistry
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
- XXX.minecraft.data.HashCache$CacheUpdater
+ XXX.minecraft.data.HashCache$ProviderCache
- XXX.minecraft.data.HashCache$ProviderCacheBuilder
+ XXX.minecraft.data.HashCache$UpdateFunction
- XXX.minecraft.data.HashCache$UpdateResult
+ XXX.minecraft.data.Main
- XXX.minecraft.data.PackOutput
+ XXX.minecraft.data.PackOutput$PathProvider
- XXX.minecraft.data.PackOutput$Target
+ XXX.minecraft.locale.Language
- XXX.minecraft.locale.Language$1
+ XXX.minecraft.locale.package-info
- XXX.minecraft.nbt.ByteArrayTag
+ XXX.minecraft.nbt.ByteArrayTag$1
- XXX.minecraft.nbt.ByteTag
+ XXX.minecraft.nbt.ByteTag$1
- XXX.minecraft.nbt.ByteTag$Cache
+ XXX.minecraft.nbt.CollectionTag
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
+ XXX.minecraft.nbt.NbtAccounter$1
- XXX.minecraft.nbt.NbtIo
+ XXX.minecraft.nbt.NbtIo$1
- XXX.minecraft.nbt.NbtOps
+ XXX.minecraft.nbt.NbtOps$1
- XXX.minecraft.nbt.NbtOps$ByteListCollector
+ XXX.minecraft.nbt.NbtOps$HeterogenousListCollector
- XXX.minecraft.nbt.NbtOps$HomogenousListCollector
+ XXX.minecraft.nbt.NbtOps$InitialListCollector
- XXX.minecraft.nbt.NbtOps$IntListCollector
+ XXX.minecraft.nbt.NbtOps$ListCollector
- XXX.minecraft.nbt.NbtOps$LongListCollector
+ XXX.minecraft.nbt.NbtOps$NbtRecordBuilder
- XXX.minecraft.nbt.NbtUtils
+ XXX.minecraft.nbt.NumericTag
- XXX.minecraft.nbt.package-info
- XXX.minecraft.nbt.ShortTag
+ XXX.minecraft.nbt.ShortTag$1
- XXX.minecraft.nbt.ShortTag$Cache
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
+ XXX.minecraft.network.CipherBase
- XXX.minecraft.network.CipherDecoder
+ XXX.minecraft.network.CipherEncoder
- XXX.minecraft.network.CompressionDecoder
+ XXX.minecraft.network.CompressionEncoder
- XXX.minecraft.network.Connection
+ XXX.minecraft.network.Connection$1
- XXX.minecraft.network.Connection$2
+ XXX.minecraft.network.Connection$PacketHolder
- XXX.minecraft.network.ConnectionProtocol
+ XXX.minecraft.network.ConnectionProtocol$PacketSet
- XXX.minecraft.network.ConnectionProtocol$ProtocolBuilder
+ XXX.minecraft.network.FriendlyByteBuf
- XXX.minecraft.network.FriendlyByteBuf$1
+ XXX.minecraft.network.FriendlyByteBuf$Reader
- XXX.minecraft.network.FriendlyByteBuf$Writer
+ XXX.minecraft.network.package-info
+ XXX.minecraft.network.PacketBundlePacker
- XXX.minecraft.network.PacketBundleUnpacker
+ XXX.minecraft.network.PacketDecoder
- XXX.minecraft.network.PacketEncoder
+ XXX.minecraft.network.PacketListener
- XXX.minecraft.network.PacketSendListener
+ XXX.minecraft.network.PacketSendListener$1
- XXX.minecraft.network.PacketSendListener$2
+ XXX.minecraft.network.RateKickingConnection
- XXX.minecraft.network.SkipPacketException
+ XXX.minecraft.network.TickablePacketListener
- XXX.minecraft.network.Varint21FrameDecoder
+ XXX.minecraft.network.Varint21LengthFieldPrepender
+ XXX.minecraft.obfuscate.DontObfuscate
- XXX.minecraft.obfuscate.package-info
- XXX.minecraft.realms.DisconnectedRealmsScreen
- XXX.minecraft.realms.package-info
+ XXX.minecraft.realms.RealmsConnect
- XXX.minecraft.realms.RealmsConnect$1
+ XXX.minecraft.realms.RealmsLabel
- XXX.minecraft.realms.RealmsObjectSelectionList
+ XXX.minecraft.realms.RealmsScreen
- XXX.minecraft.realms.RepeatedNarrator
+ XXX.minecraft.realms.RepeatedNarrator$Params
+ XXX.minecraft.recipebook.package-info
+ XXX.minecraft.recipebook.PlaceRecipe
- XXX.minecraft.recipebook.ServerPlaceRecipe
- XXX.minecraft.resources.DelegatingOps
+ XXX.minecraft.resources.FileToIdConverter
- XXX.minecraft.resources.HolderSetCodec
+ XXX.minecraft.resources.package-info
+ XXX.minecraft.resources.RegistryDataLoader
- XXX.minecraft.resources.RegistryDataLoader$1
+ XXX.minecraft.resources.RegistryDataLoader$Loader
- XXX.minecraft.resources.RegistryDataLoader$RegistryData
+ XXX.minecraft.resources.RegistryFileCodec
- XXX.minecraft.resources.RegistryFixedCodec
+ XXX.minecraft.resources.RegistryOps
- XXX.minecraft.resources.RegistryOps$1
+ XXX.minecraft.resources.RegistryOps$2
- XXX.minecraft.resources.RegistryOps$RegistryInfo
+ XXX.minecraft.resources.RegistryOps$RegistryInfoLookup
- XXX.minecraft.resources.ResourceKey
+ XXX.minecraft.resources.ResourceKey$InternKey
- XXX.minecraft.resources.ResourceLocation
+ XXX.minecraft.resources.ResourceLocation$Dummy
- XXX.minecraft.resources.ResourceLocation$Serializer
- XXX.minecraft.server.Bootstrap
+ XXX.minecraft.server.Bootstrap$1
- XXX.minecraft.server.ChainedJsonException
+ XXX.minecraft.server.ChainedJsonException$Entry
- XXX.minecraft.server.ConsoleInput
+ XXX.minecraft.server.DebugLoggedPrintStream
- XXX.minecraft.server.Eula
+ XXX.minecraft.server.LoggedPrintStream
- XXX.minecraft.server.Main
+ XXX.minecraft.server.Main$1
- XXX.minecraft.server.MinecraftServer
+ XXX.minecraft.server.MinecraftServer$1
- XXX.minecraft.server.MinecraftServer$ReloadableResources
+ XXX.minecraft.server.MinecraftServer$ServerResourcePackInfo
- XXX.minecraft.server.MinecraftServer$TimeProfiler
+ XXX.minecraft.server.MinecraftServer$TimeProfiler$1
- XXX.minecraft.server.PlayerAdvancements
+ XXX.minecraft.server.PlayerAdvancements$1
- XXX.minecraft.server.RegistryLayer
+ XXX.minecraft.server.ReloadableServerResources
- XXX.minecraft.server.RunningOnDifferentThreadException
+ XXX.minecraft.server.ServerAdvancementManager
- XXX.minecraft.server.ServerFunctionLibrary
+ XXX.minecraft.server.ServerFunctionManager
- XXX.minecraft.server.ServerFunctionManager$ExecutionContext
+ XXX.minecraft.server.ServerFunctionManager$QueuedCommand
- XXX.minecraft.server.ServerFunctionManager$TraceCallbacks
+ XXX.minecraft.server.ServerInterface
- XXX.minecraft.server.ServerScoreboard
+ XXX.minecraft.server.ServerScoreboard$Method
- XXX.minecraft.server.Services
+ XXX.minecraft.server.TickTask
- XXX.minecraft.server.WorldLoader
+ XXX.minecraft.server.WorldLoader$DataLoadContext
- XXX.minecraft.server.WorldLoader$DataLoadOutput
+ XXX.minecraft.server.WorldLoader$InitConfig
- XXX.minecraft.server.WorldLoader$PackConfig
+ XXX.minecraft.server.WorldLoader$ResultFactory
- XXX.minecraft.server.WorldLoader$WorldDataSupplier
+ XXX.minecraft.server.WorldStem
+ XXX.minecraft.util.RgbTxt$Entry
+ XXX.minecraft.voting.package-info
+ XXX.minecraft.voting.VoteCommand
- XXX.minecraft.world.BossEvent
+ XXX.minecraft.world.BossEvent$BossBarColor
- XXX.minecraft.world.BossEvent$BossBarOverlay
+ XXX.minecraft.world.Clearable
- XXX.minecraft.world.CompoundContainer
+ XXX.minecraft.world.Container
- XXX.minecraft.world.ContainerHelper
+ XXX.minecraft.world.ContainerListener
- XXX.minecraft.world.Containers
+ XXX.minecraft.world.Difficulty
- XXX.minecraft.world.DifficultyInstance
+ XXX.minecraft.world.InteractionHand
- XXX.minecraft.world.InteractionResult
+ XXX.minecraft.world.InteractionResultHolder
- XXX.minecraft.world.LockCode
+ XXX.minecraft.world.MenuProvider
- XXX.minecraft.world.Nameable
+ XXX.minecraft.world.SimpleContainer
- XXX.minecraft.world.SimpleMenuProvider
+ XXX.minecraft.world.WorldlyContainer
- XXX.minecraft.world.WorldlyContainerHolder
+ XXX.model.dragon.DragonHeadModel
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
+ XXX.model.geom.package-info
- XXX.model.geom.PartNames
+ XXX.model.geom.PartPose
- XXX.mojang.realmsclient.package-info
- XXX.multiplayer.chat.ChatListener
+ XXX.multiplayer.chat.ChatListener$Message
- XXX.multiplayer.chat.ChatLog
+ XXX.multiplayer.chat.ChatTrustLevel
- XXX.multiplayer.chat.ChatTrustLevel$1
+ XXX.multiplayer.chat.LoggedChatEvent
- XXX.multiplayer.chat.LoggedChatEvent$Type
+ XXX.multiplayer.chat.LoggedChatMessage
- XXX.multiplayer.chat.LoggedChatMessage$Player
+ XXX.multiplayer.chat.LoggedChatMessage$System
- XXX.multiplayer.chat.package-info
+ XXX.multiplayer.prediction.BlockStatePredictionHandler
- XXX.multiplayer.prediction.BlockStatePredictionHandler$ServerVerifiedState
- XXX.multiplayer.prediction.package-info
+ XXX.multiplayer.prediction.PredictiveAction
+ XXX.multiplayer.resolver.AddressCheck
- XXX.multiplayer.resolver.AddressCheck$1
+ XXX.multiplayer.resolver.package-info
+ XXX.multiplayer.resolver.ResolvedServerAddress
- XXX.multiplayer.resolver.ResolvedServerAddress$1
+ XXX.multiplayer.resolver.ServerAddress
- XXX.multiplayer.resolver.ServerAddressResolver
+ XXX.multiplayer.resolver.ServerNameResolver
- XXX.multiplayer.resolver.ServerRedirectHandler
+ XXX.nbt.visitors.CollectFields
- XXX.nbt.visitors.CollectToTag
+ XXX.nbt.visitors.FieldSelector
- XXX.nbt.visitors.FieldTree
- XXX.nbt.visitors.package-info
+ XXX.nbt.visitors.SkipAll
- XXX.nbt.visitors.SkipAll$1
+ XXX.nbt.visitors.SkipFields
- XXX.network.chat.ChatDecorator
+ XXX.network.chat.ChatType
- XXX.network.chat.ChatType$Bound
+ XXX.network.chat.ChatType$BoundNetwork
- XXX.network.chat.ChatTypeDecoration
+ XXX.network.chat.ChatTypeDecoration$Parameter
- XXX.network.chat.ChatTypeDecoration$Parameter$Selector
+ XXX.network.chat.ClickEvent
- XXX.network.chat.ClickEvent$Action
+ XXX.network.chat.CommonComponents
- XXX.network.chat.Component
+ XXX.network.chat.Component$Serializer
- XXX.network.chat.ComponentContents
+ XXX.network.chat.ComponentContents$1
- XXX.network.chat.ComponentUtils
+ XXX.network.chat.FilterMask
- XXX.network.chat.FilterMask$1
+ XXX.network.chat.FilterMask$Type
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
- XXX.network.chat.HoverEvent$ItemStackInfo
+ XXX.network.chat.LastSeenMessages
- XXX.network.chat.LastSeenMessages$Packed
+ XXX.network.chat.LastSeenMessages$Update
- XXX.network.chat.LastSeenMessagesTracker
+ XXX.network.chat.LastSeenMessagesTracker$Update
- XXX.network.chat.LastSeenMessagesValidator
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
- XXX.network.protocol.BundleDelimiterPacket
+ XXX.network.protocol.BundlePacket
- XXX.network.protocol.BundlerInfo
+ XXX.network.protocol.BundlerInfo$1
- XXX.network.protocol.BundlerInfo$2
+ XXX.network.protocol.BundlerInfo$2$1
- XXX.network.protocol.BundlerInfo$Bundler
+ XXX.network.protocol.BundlerInfo$Provider
+ XXX.network.protocol.package-info
- XXX.network.protocol.Packet
+ XXX.network.protocol.PacketFlow
- XXX.network.protocol.PacketUtils
+ XXX.network.syncher.EntityDataAccessor
- XXX.network.syncher.EntityDataSerializer
+ XXX.network.syncher.EntityDataSerializer$1
- XXX.network.syncher.EntityDataSerializer$ForValueType
+ XXX.network.syncher.EntityDataSerializers
- XXX.network.syncher.EntityDataSerializers$1
+ XXX.network.syncher.EntityDataSerializers$2
- XXX.network.syncher.EntityDataSerializers$3
+ XXX.network.syncher.EntityDataSerializers$4
- XXX.network.syncher.EntityDataSerializers$5
+ XXX.network.syncher.EntityDataSerializers$6
- XXX.network.syncher.EntityDataSerializers$7
- XXX.network.syncher.package-info
+ XXX.network.syncher.SynchedEntityData
- XXX.network.syncher.SynchedEntityData$DataItem
+ XXX.network.syncher.SynchedEntityData$DataValue
- XXX.protocol.game.ClientboundAddEntityPacket
+ XXX.protocol.game.ClientboundAddExperienceOrbPacket
- XXX.protocol.game.ClientboundAddPlayerPacket
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
+ XXX.protocol.game.ClientboundSetCarriedItemPacket
- XXX.protocol.game.ClientboundSetChunkCacheCenterPacket
+ XXX.protocol.game.ClientboundSetChunkCacheRadiusPacket
- XXX.protocol.game.ClientboundSetDefaultSpawnPositionPacket
+ XXX.protocol.game.ClientboundSetDisplayObjectivePacket
- XXX.protocol.game.ClientboundSetEntityDataPacket
+ XXX.protocol.game.ClientboundSetEntityLinkPacket
- XXX.protocol.game.ClientboundSetEntityMotionPacket
+ XXX.protocol.game.ClientboundSetEquipmentPacket
- XXX.protocol.game.ClientboundSetExperiencePacket
+ XXX.protocol.game.ClientboundSetHealthPacket
- XXX.protocol.game.ClientboundSetObjectivePacket
+ XXX.protocol.game.ClientboundSetPassengersPacket
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
+ XXX.protocol.game.ClientboundStopSoundPacket
- XXX.protocol.game.ClientboundSystemChatPacket
+ XXX.protocol.game.ClientboundTabListPacket
- XXX.protocol.game.ClientboundTagQueryPacket
+ XXX.protocol.game.ClientboundTakeItemEntityPacket
- XXX.protocol.game.ClientboundTeleportEntityPacket
+ XXX.protocol.game.ClientboundUpdateAdvancementsPacket
- XXX.protocol.game.ClientboundUpdateAttributesPacket
+ XXX.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
- XXX.protocol.game.ClientboundUpdateEnabledFeaturesPacket
+ XXX.protocol.game.ClientboundUpdateMobEffectPacket
- XXX.protocol.game.ClientboundUpdateRecipesPacket
+ XXX.protocol.game.ClientboundUpdateTagsPacket
+ XXX.protocol.game.ClientboundVoteFinishPacket
+ XXX.protocol.game.ClientboundVoteStartPacket
+ XXX.protocol.game.ClientGamePacketListener
- XXX.protocol.game.DebugEntityNameGenerator
+ XXX.protocol.game.DebugPackets
- XXX.protocol.game.package-info
- XXX.protocol.game.ServerboundAcceptTeleportationPacket
+ XXX.protocol.game.ServerboundBlockEntityTagQuery
- XXX.protocol.game.ServerboundChangeDifficultyPacket
+ XXX.protocol.game.ServerboundChatAckPacket
- XXX.protocol.game.ServerboundChatCommandPacket
+ XXX.protocol.game.ServerboundChatPacket
- XXX.protocol.game.ServerboundChatSessionUpdatePacket
+ XXX.protocol.game.ServerboundClientCommandPacket
- XXX.protocol.game.ServerboundClientCommandPacket$Action
+ XXX.protocol.game.ServerboundClientInformationPacket
- XXX.protocol.game.ServerboundCommandSuggestionPacket
+ XXX.protocol.game.ServerboundContainerButtonClickPacket
- XXX.protocol.game.ServerboundContainerClickPacket
+ XXX.protocol.game.ServerboundContainerClosePacket
- XXX.protocol.game.ServerGamePacketListener
+ XXX.protocol.game.ServerPacketListener
+ XXX.protocol.game.VecDeltaCodec
+ XXX.protocol.handshake.ClientIntentionPacket
+ XXX.protocol.handshake.package-info
- XXX.protocol.handshake.ServerHandshakePacketListener
+ XXX.protocol.login.ClientboundCustomQueryPacket
- XXX.protocol.login.ClientboundGameProfilePacket
+ XXX.protocol.login.ClientboundHelloPacket
- XXX.protocol.login.ClientboundLoginCompressionPacket
+ XXX.protocol.login.ClientboundLoginDisconnectPacket
- XXX.protocol.login.ClientLoginPacketListener
- XXX.protocol.login.package-info
+ XXX.protocol.login.ServerboundCustomQueryPacket
- XXX.protocol.login.ServerboundHelloPacket
+ XXX.protocol.login.ServerboundKeyPacket
- XXX.protocol.login.ServerLoginPacketListener
+ XXX.protocol.status.ClientboundPongResponsePacket
- XXX.protocol.status.ClientboundStatusResponsePacket
- XXX.protocol.status.ClientStatusPacketListener
- XXX.protocol.status.package-info
- XXX.protocol.status.ServerboundPingRequestPacket
+ XXX.protocol.status.ServerboundStatusRequestPacket
+ XXX.protocol.status.ServerStatus
- XXX.protocol.status.ServerStatus$Favicon
+ XXX.protocol.status.ServerStatus$Players
- XXX.protocol.status.ServerStatus$Version
+ XXX.protocol.status.ServerStatusPacketListener
+ XXX.realmsclient.util.JsonUtils
- XXX.realmsclient.util.LevelType
- XXX.realmsclient.util.package-info
+ XXX.realmsclient.util.RealmsPersistence
- XXX.realmsclient.util.RealmsPersistence$RealmsPersistenceData
+ XXX.realmsclient.util.RealmsTextureManager
- XXX.realmsclient.util.RealmsTextureManager$RealmsTexture
+ XXX.realmsclient.util.RealmsUtil
- XXX.realmsclient.util.RealmsUtil$1
+ XXX.realmsclient.util.TextRenderingUtils
- XXX.realmsclient.util.TextRenderingUtils$Line
+ XXX.realmsclient.util.TextRenderingUtils$LineSegment
- XXX.realmsclient.util.UploadTokenCache
+ XXX.realmsclient.util.WorldGenerationInfo
+ XXX.renderer.entity.DisplayRenderer$TextDisplayRenderer
- XXX.renderer.entity.DolphinRenderer
+ XXX.renderer.entity.DragonFireballRenderer
- XXX.renderer.entity.DrownedRenderer
+ XXX.renderer.entity.ElderGuardianRenderer
- XXX.renderer.entity.EndCrystalRenderer
+ XXX.renderer.entity.EnderDragonRenderer
- XXX.renderer.entity.EnderDragonRenderer$DragonModel
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
+ XXX.renderer.entity.MoonCowRenderer
+ XXX.renderer.entity.package-info
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
+ XXX.renderer.entity.StencilRenderer$Triangle
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
- XXX.renderer.entity.VexRenderer
+ XXX.renderer.entity.VillagerRenderer
- XXX.renderer.entity.VindicatorRenderer
+ XXX.renderer.entity.VindicatorRenderer$1
- XXX.renderer.entity.WanderingTraderRenderer
+ XXX.renderer.entity.WardenRenderer
- XXX.renderer.entity.WitchRenderer
+ XXX.renderer.entity.WitherBossRenderer
- XXX.renderer.entity.WitherSkeletonRenderer
+ XXX.renderer.entity.WitherSkullRenderer
- XXX.renderer.entity.WolfRenderer
+ XXX.renderer.entity.ZoglinRenderer
- XXX.renderer.entity.ZombieRenderer
+ XXX.renderer.entity.ZombieVillagerRenderer
+ XXX.rules.actual.AutoJumpAlternatives
+ XXX.rules.actual.BinaryGameRuleRule$RuleRuleChange
+ XXX.rules.actual.BlockFlammabilityRule
+ XXX.rules.actual.BlockMapRule
+ XXX.rules.actual.BlockModelReplacementRule$PotentialEntry
+ XXX.rules.actual.BlockReplaceSingleRule
+ XXX.rules.actual.ChickenEggRule
+ XXX.rules.actual.CodepointStyleRule
+ XXX.rules.actual.ColorRule
+ XXX.rules.actual.CopySkinRule$CopySkinRuleChange
+ XXX.rules.actual.DoubleOrHalfDamageTypeMapRule
+ XXX.rules.actual.ExplosionExtraPowerRule
+ XXX.rules.actual.FoodType
+ XXX.rules.actual.GiveEffectRule
+ XXX.rules.actual.Goldifier
+ XXX.rules.actual.IntegerGameRuleRule
+ XXX.rules.actual.ItemDespawnTime
+ XXX.rules.actual.ItemGiveRule
+ XXX.rules.actual.ItemModelReplacementRule
+ XXX.rules.actual.LavaReplaceRule
+ XXX.rules.actual.LightEngineMode$1
+ XXX.rules.actual.NameVisiblity
+ XXX.rules.actual.OptimizationRule
+ XXX.rules.actual.ParentTrapRule$ParentTrapRuleChange
+ XXX.rules.actual.PlayerSetRule
+ XXX.rules.actual.RecipeFlip
+ XXX.rules.actual.ReplaceItemsRule$ItemGenerator
+ XXX.rules.actual.RuleFeatureToggles
+ XXX.rules.actual.TheJokeRule
+ XXX.rules.actual.ThreadedAnvilChunkStorage
+ XXX.rules.actual.ThreadedAnvilChunkStorage$Change
+ XXX.rules.actual.TransformEntityRule$TransformRuleChange
+ XXX.rules.actual.TransformScaleRule$ScaleRuleChange
+ XXX.rules.actual.VillagerPaymentRule
+ XXX.rules.actual.WorldShape
- XXX.screens.achievement.package-info
+ XXX.screens.achievement.StatsScreen
- XXX.screens.achievement.StatsScreen$GeneralStatisticsList
+ XXX.screens.achievement.StatsScreen$GeneralStatisticsList$Entry
- XXX.screens.achievement.StatsScreen$ItemStatisticsList
+ XXX.screens.achievement.StatsScreen$ItemStatisticsList$ItemRow
- XXX.screens.achievement.StatsScreen$ItemStatisticsList$ItemRowComparator
+ XXX.screens.achievement.StatsScreen$MobsStatisticsList
- XXX.screens.achievement.StatsScreen$MobsStatisticsList$MobRow
+ XXX.screens.achievement.StatsUpdateListener
- XXX.screens.advancements.AdvancementsScreen
+ XXX.screens.advancements.AdvancementTab
- XXX.screens.advancements.AdvancementTabType
+ XXX.screens.advancements.AdvancementTabType$1
- XXX.screens.advancements.AdvancementWidget
+ XXX.screens.advancements.AdvancementWidgetType
+ XXX.screens.advancements.package-info
- XXX.screens.controls.ControlsScreen
+ XXX.screens.controls.KeyBindsList
- XXX.screens.controls.KeyBindsList$CategoryEntry
+ XXX.screens.controls.KeyBindsList$CategoryEntry$1
- XXX.screens.controls.KeyBindsList$Entry
+ XXX.screens.controls.KeyBindsList$KeyEntry
- XXX.screens.controls.KeyBindsScreen
+ XXX.screens.controls.package-info
- XXX.screens.debug.GameModeSwitcherScreen
+ XXX.screens.debug.GameModeSwitcherScreen$1
- XXX.screens.debug.GameModeSwitcherScreen$GameModeIcon
+ XXX.screens.debug.GameModeSwitcherScreen$GameModeSlot
- XXX.screens.debug.package-info
+ XXX.screens.inventory.AbstractCommandBlockEditScreen
- XXX.screens.inventory.AbstractCommandBlockEditScreen$1
+ XXX.screens.inventory.AbstractContainerScreen
- XXX.screens.inventory.AbstractFurnaceScreen
+ XXX.screens.inventory.AbstractSignEditScreen
- XXX.screens.inventory.AnvilScreen
+ XXX.screens.inventory.BeaconScreen
- XXX.screens.inventory.BeaconScreen$1
+ XXX.screens.inventory.BeaconScreen$BeaconButton
- XXX.screens.inventory.BeaconScreen$BeaconCancelButton
+ XXX.screens.inventory.BeaconScreen$BeaconConfirmButton
- XXX.screens.inventory.BeaconScreen$BeaconPowerButton
+ XXX.screens.inventory.BeaconScreen$BeaconScreenButton
- XXX.screens.inventory.BeaconScreen$BeaconSpriteScreenButton
+ XXX.screens.inventory.BeaconScreen$BeaconUpgradePowerButton
- XXX.screens.inventory.BlastFurnaceScreen
+ XXX.screens.inventory.BookEditScreen
- XXX.screens.inventory.BookEditScreen$DisplayCache
+ XXX.screens.inventory.BookEditScreen$LineInfo
- XXX.screens.inventory.BookEditScreen$Pos2i
+ XXX.screens.inventory.BookViewScreen
- XXX.screens.inventory.BookViewScreen$1
+ XXX.screens.inventory.BookViewScreen$BookAccess
- XXX.screens.inventory.BookViewScreen$WritableBookAccess
+ XXX.screens.inventory.BookViewScreen$WrittenBookAccess
- XXX.screens.inventory.BrewingStandScreen
+ XXX.screens.inventory.CartographyTableScreen
- XXX.screens.inventory.CommandBlockEditScreen
+ XXX.screens.inventory.CommandBlockEditScreen$1
- XXX.screens.inventory.ContainerScreen
+ XXX.screens.inventory.CraftingScreen
- XXX.screens.inventory.CreativeInventoryListener
+ XXX.screens.inventory.CreativeModeInventoryScreen
- XXX.screens.inventory.CreativeModeInventoryScreen$CustomCreativeSlot
+ XXX.screens.inventory.CreativeModeInventoryScreen$ItemPickerMenu
- XXX.screens.inventory.CreativeModeInventoryScreen$SlotWrapper
+ XXX.screens.inventory.CyclingSlotBackground
- XXX.screens.inventory.DispenserScreen
+ XXX.screens.inventory.EffectRenderingInventoryScreen
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
+ XXX.screens.inventory.package-info
- XXX.screens.inventory.PageButton
+ XXX.screens.inventory.ShulkerBoxScreen
- XXX.screens.inventory.SignEditScreen
+ XXX.screens.inventory.SmithingScreen
- XXX.screens.inventory.SmokerScreen
+ XXX.screens.inventory.StonecutterScreen
- XXX.screens.inventory.StructureBlockEditScreen
+ XXX.screens.inventory.StructureBlockEditScreen$1
- XXX.screens.inventory.StructureBlockEditScreen$2
+ XXX.screens.multiplayer.JoinMultiplayerScreen
- XXX.screens.multiplayer.package-info
- XXX.screens.multiplayer.Realms32bitWarningScreen
+ XXX.screens.multiplayer.SafetyScreen
- XXX.screens.multiplayer.ServerSelectionList
+ XXX.screens.multiplayer.ServerSelectionList$Entry
- XXX.screens.multiplayer.ServerSelectionList$LANHeader
+ XXX.screens.multiplayer.ServerSelectionList$NetworkServerEntry
- XXX.screens.multiplayer.ServerSelectionList$OnlineServerEntry
+ XXX.screens.multiplayer.WarningScreen
+ XXX.screens.packs.package-info
- XXX.screens.packs.PackSelectionModel
+ XXX.screens.packs.PackSelectionModel$Entry
- XXX.screens.packs.PackSelectionModel$EntryBase
+ XXX.screens.packs.PackSelectionModel$SelectedPackEntry
- XXX.screens.packs.PackSelectionModel$UnselectedPackEntry
+ XXX.screens.packs.PackSelectionScreen
- XXX.screens.packs.PackSelectionScreen$Watcher
+ XXX.screens.packs.TransferableSelectionList
- XXX.screens.packs.TransferableSelectionList$PackEntry
- XXX.screens.recipebook.AbstractFurnaceRecipeBookComponent
+ XXX.screens.recipebook.BlastingRecipeBookComponent
- XXX.screens.recipebook.GhostRecipe
+ XXX.screens.recipebook.GhostRecipe$GhostIngredient
- XXX.screens.recipebook.OverlayRecipeComponent
+ XXX.screens.recipebook.OverlayRecipeComponent$OverlayRecipeButton
- XXX.screens.recipebook.OverlayRecipeComponent$OverlayRecipeButton$Pos
+ XXX.screens.recipebook.OverlayRecipeComponent$OverlaySmeltingRecipeButton
+ XXX.screens.recipebook.package-info
- XXX.screens.recipebook.RecipeBookComponent
+ XXX.screens.recipebook.RecipeBookPage
- XXX.screens.recipebook.RecipeBookTabButton
+ XXX.screens.recipebook.RecipeButton
- XXX.screens.recipebook.RecipeCollection
+ XXX.screens.recipebook.RecipeShownListener
- XXX.screens.recipebook.RecipeUpdateListener
+ XXX.screens.recipebook.SmeltingRecipeBookComponent
- XXX.screens.recipebook.SmokingRecipeBookComponent
- XXX.screens.reporting.ChatReportScreen
+ XXX.screens.reporting.ChatReportScreen$DiscardReportWarningScreen
- XXX.screens.reporting.ChatSelectionLogFiller
+ XXX.screens.reporting.ChatSelectionLogFiller$Output
- XXX.screens.reporting.ChatSelectionScreen
+ XXX.screens.reporting.ChatSelectionScreen$ChatSelectionList
- XXX.screens.reporting.ChatSelectionScreen$ChatSelectionList$DividerEntry
+ XXX.screens.reporting.ChatSelectionScreen$ChatSelectionList$Entry
- XXX.screens.reporting.ChatSelectionScreen$ChatSelectionList$Heading
+ XXX.screens.reporting.ChatSelectionScreen$ChatSelectionList$MessageEntry
- XXX.screens.reporting.ChatSelectionScreen$ChatSelectionList$MessageHeadingEntry
+ XXX.screens.reporting.ChatSelectionScreen$ChatSelectionList$PaddingEntry
+ XXX.screens.reporting.package-info
- XXX.screens.reporting.ReportReasonSelectionScreen
+ XXX.screens.reporting.ReportReasonSelectionScreen$ReasonSelectionList
- XXX.screens.reporting.ReportReasonSelectionScreen$ReasonSelectionList$Entry
- XXX.screens.social.package-info
- XXX.screens.social.PlayerEntry
+ XXX.screens.social.PlayerEntry$1
- XXX.screens.social.PlayerEntry$2
+ XXX.screens.social.PlayerEntry$3
- XXX.screens.social.PlayerSocialManager
+ XXX.screens.social.SocialInteractionsPlayerList
- XXX.screens.social.SocialInteractionsScreen
+ XXX.screens.social.SocialInteractionsScreen$1
- XXX.screens.social.SocialInteractionsScreen$2
+ XXX.screens.social.SocialInteractionsScreen$Page
+ XXX.screens.telemetry.package-info
+ XXX.screens.telemetry.TelemetryEventWidget
- XXX.screens.telemetry.TelemetryEventWidget$Content
+ XXX.screens.telemetry.TelemetryEventWidget$ContentBuilder
- XXX.screens.telemetry.TelemetryInfoScreen
+ XXX.screens.voting.package-info
+ XXX.screens.voting.VoteSelectionEntry
+ XXX.screens.voting.VoteSelectionScreen
+ XXX.screens.voting.VotingScreen$1
+ XXX.screens.voting.VotingScreen$3
+ XXX.screens.voting.VotingScreen$FakeAndTerrible
+ XXX.screens.voting.VotingScreen$OptionSelectButton
- XXX.screens.worldselection.ConfirmExperimentalFeaturesScreen
+ XXX.screens.worldselection.ConfirmExperimentalFeaturesScreen$DetailsScreen
- XXX.screens.worldselection.ConfirmExperimentalFeaturesScreen$DetailsScreen$PackList
+ XXX.screens.worldselection.ConfirmExperimentalFeaturesScreen$DetailsScreen$PackListEntry
- XXX.screens.worldselection.CreateWorldScreen
+ XXX.screens.worldselection.CreateWorldScreen$DataPackReloadCookie
- XXX.screens.worldselection.CreateWorldScreen$GameTab
+ XXX.screens.worldselection.CreateWorldScreen$MoreTab
- XXX.screens.worldselection.CreateWorldScreen$WorldTab
+ XXX.screens.worldselection.CreateWorldScreen$WorldTab$1
- XXX.screens.worldselection.CreateWorldScreen$WorldTab$2
+ XXX.screens.worldselection.EditGameRulesScreen
- XXX.screens.worldselection.EditGameRulesScreen$BooleanRuleEntry
+ XXX.screens.worldselection.EditGameRulesScreen$CategoryRuleEntry
- XXX.screens.worldselection.EditGameRulesScreen$CategoryRuleEntry$1
+ XXX.screens.worldselection.EditGameRulesScreen$EntryFactory
- XXX.screens.worldselection.EditGameRulesScreen$GameRuleEntry
+ XXX.screens.worldselection.EditGameRulesScreen$IntegerRuleEntry
- XXX.screens.worldselection.EditGameRulesScreen$RuleEntry
+ XXX.screens.worldselection.EditGameRulesScreen$RuleList
- XXX.screens.worldselection.EditGameRulesScreen$RuleList$1
+ XXX.screens.worldselection.EditWorldScreen
- XXX.screens.worldselection.ExperimentsScreen
+ XXX.screens.worldselection.OptimizeWorldScreen
+ XXX.screens.worldselection.package-info
- XXX.screens.worldselection.PresetEditor
+ XXX.screens.worldselection.SelectWorldScreen
- XXX.screens.worldselection.SwitchGrid
+ XXX.screens.worldselection.SwitchGrid$Builder
- XXX.screens.worldselection.SwitchGrid$InfoUnderneathSettings
+ XXX.screens.worldselection.SwitchGrid$LabeledSwitch
- XXX.screens.worldselection.SwitchGrid$SwitchBuilder
+ XXX.screens.worldselection.WorldCreationContext
- XXX.screens.worldselection.WorldCreationContext$DimensionsUpdater
+ XXX.screens.worldselection.WorldCreationContext$OptionsModifier
- XXX.screens.worldselection.WorldCreationUiState
+ XXX.screens.worldselection.WorldCreationUiState$SelectedGameMode
- XXX.screens.worldselection.WorldCreationUiState$WorldTypeEntry
+ XXX.screens.worldselection.WorldOpenFlows
- XXX.screens.worldselection.WorldOpenFlows$1Data
+ XXX.screens.worldselection.WorldSelectionList
- XXX.screens.worldselection.WorldSelectionList$Entry
+ XXX.screens.worldselection.WorldSelectionList$LoadingHeader
- XXX.screens.worldselection.WorldSelectionList$WorldListEntry
+ XXX.selector.options.EntitySelectorOptions
- XXX.selector.options.EntitySelectorOptions$Modifier
+ XXX.selector.options.EntitySelectorOptions$Option
- XXX.selector.options.package-info
- XXX.server.advancements.AdvancementVisibilityEvaluator
+ XXX.server.advancements.AdvancementVisibilityEvaluator$Output
- XXX.server.advancements.AdvancementVisibilityEvaluator$VisibilityRule
+ XXX.server.advancements.package-info
- XXX.server.bossevents.CustomBossEvent
+ XXX.server.bossevents.CustomBossEvents
- XXX.server.bossevents.package-info
+ XXX.server.chase.ChaseClient
- XXX.server.chase.ChaseClient$TeleportTarget
+ XXX.server.chase.ChaseServer
- XXX.server.chase.ChaseServer$PlayerPosition
+ XXX.server.chase.package-info
- XXX.server.commands.AdvancementCommands
+ XXX.server.commands.AdvancementCommands$Action
- XXX.server.commands.AdvancementCommands$Action$1
+ XXX.server.commands.AdvancementCommands$Action$2
- XXX.server.commands.AdvancementCommands$Mode
+ XXX.server.commands.AttributeCommand
- XXX.server.commands.BanIpCommands
+ XXX.server.commands.BanListCommands
- XXX.server.commands.BanPlayerCommands
+ XXX.server.commands.BossBarCommands
- XXX.server.commands.ChaseCommand
+ XXX.server.commands.ClearInventoryCommands
- XXX.server.commands.CloneCommands
+ XXX.server.commands.CloneCommands$CloneBlockInfo
- XXX.server.commands.CloneCommands$CommandFunction
+ XXX.server.commands.CloneCommands$DimensionAndPosition
- XXX.server.commands.CloneCommands$Mode
+ XXX.server.commands.DamageCommand
- XXX.server.commands.DataPackCommand
+ XXX.server.commands.DataPackCommand$Inserter
+ XXX.server.commands.DebugCommand
- XXX.server.commands.DebugCommand$Tracer
+ XXX.server.commands.DebugMobSpawningCommand
- XXX.server.commands.DebugPathCommand
+ XXX.server.commands.DefaultGameModeCommands
- XXX.server.commands.DeOpCommands
- XXX.server.commands.DifficultyCommand
+ XXX.server.commands.EffectCommands
- XXX.server.commands.EmoteCommands
+ XXX.server.commands.EnchantCommand
- XXX.server.commands.ExecuteCommand
+ XXX.server.commands.ExecuteCommand$CommandNumericPredicate
- XXX.server.commands.ExecuteCommand$CommandPredicate
+ XXX.server.commands.ExperienceCommand
- XXX.server.commands.ExperienceCommand$Type
+ XXX.server.commands.FillBiomeCommand
- XXX.server.commands.FillCommand
+ XXX.server.commands.FillCommand$Mode
- XXX.server.commands.ForceLoadCommand
+ XXX.server.commands.FunctionCommand
- XXX.server.commands.GameModeCommand
+ XXX.server.commands.GameRuleCommand
- XXX.server.commands.GameRuleCommand$1
+ XXX.server.commands.GiveCommand
- XXX.server.commands.HelpCommand
+ XXX.server.commands.ItemCommands
- XXX.server.commands.JfrCommand
+ XXX.server.commands.KickCommand
- XXX.server.commands.KillCommand
+ XXX.server.commands.ListPlayersCommand
- XXX.server.commands.LocateCommand
+ XXX.server.commands.LootCommand
- XXX.server.commands.LootCommand$Callback
+ XXX.server.commands.LootCommand$DropConsumer
- XXX.server.commands.LootCommand$TailProvider
+ XXX.server.commands.MsgCommand
- XXX.server.commands.OpCommand
- XXX.server.commands.package-info
+ XXX.server.commands.PardonCommand
- XXX.server.commands.PardonIpCommand
+ XXX.server.commands.ParticleCommand
- XXX.server.commands.PerfCommand
+ XXX.server.commands.PlaceCommand
- XXX.server.commands.PlaySoundCommand
+ XXX.server.commands.PublishCommand
- XXX.server.commands.RaidCommand
+ XXX.server.commands.RecipeCommand
- XXX.server.commands.ReloadCommand
+ XXX.server.commands.ResetChunksCommand
- XXX.server.commands.RideCommand
+ XXX.server.commands.SaveAllCommand
- XXX.server.commands.SaveOffCommand
+ XXX.server.commands.SaveOnCommand
- XXX.server.commands.SayCommand
+ XXX.server.commands.ScheduleCommand
- XXX.server.commands.ScoreboardCommand
+ XXX.server.commands.SeedCommand
- XXX.server.commands.SetBlockCommand
+ XXX.server.commands.SetBlockCommand$Filter
- XXX.server.commands.SetBlockCommand$Mode
+ XXX.server.commands.SetPlayerIdleTimeoutCommand
- XXX.server.commands.SetSpawnCommand
+ XXX.server.commands.SetWorldSpawnCommand
- XXX.server.commands.SpawnArmorTrimsCommand
+ XXX.server.commands.SpectateCommand
- XXX.server.commands.SpreadPlayersCommand
+ XXX.server.commands.SpreadPlayersCommand$Position
- XXX.server.commands.StopCommand
+ XXX.server.commands.StopSoundCommand
- XXX.server.commands.SummonCommand
+ XXX.server.commands.TagCommand
- XXX.server.commands.TeamCommand
+ XXX.server.commands.TeamMsgCommand
- XXX.server.commands.TeleportCommand
+ XXX.server.commands.TeleportCommand$LookAt
- XXX.server.commands.TellRawCommand
+ XXX.server.commands.TimeCommand
- XXX.server.commands.TitleCommand
+ XXX.server.commands.TriggerCommand
- XXX.server.commands.WardenSpawnTrackerCommand
+ XXX.server.commands.WeatherCommand
- XXX.server.commands.WhitelistCommand
+ XXX.server.commands.WorldBorderCommand
+ XXX.server.dedicated.DedicatedPlayerList
- XXX.server.dedicated.DedicatedServer
+ XXX.server.dedicated.DedicatedServer$1
- XXX.server.dedicated.DedicatedServerProperties
+ XXX.server.dedicated.DedicatedServerProperties$WorldDimensionData
- XXX.server.dedicated.DedicatedServerSettings
+ XXX.server.dedicated.package-info
+ XXX.server.dedicated.ServerWatchdog
- XXX.server.dedicated.ServerWatchdog$1
+ XXX.server.dedicated.Settings
- XXX.server.dedicated.Settings$MutableValue
- XXX.server.gui.MinecraftServerGui
+ XXX.server.gui.MinecraftServerGui$1
- XXX.server.gui.MinecraftServerGui$2
+ XXX.server.gui.package-info
+ XXX.server.gui.PlayerListComponent
- XXX.server.gui.StatsComponent
- XXX.server.level.BlockDestructionProgress
+ XXX.server.level.ChunkHolder
- XXX.server.level.ChunkHolder$1
+ XXX.server.level.ChunkHolder$ChunkLoadingFailure
- XXX.server.level.ChunkHolder$ChunkLoadingFailure$1
+ XXX.server.level.ChunkHolder$ChunkSaveDebug
- XXX.server.level.ChunkHolder$FullChunkStatus
+ XXX.server.level.ChunkHolder$LevelChangeListener
- XXX.server.level.ChunkHolder$PlayerProvider
+ XXX.server.level.ChunkMap
- XXX.server.level.ChunkMap$1
+ XXX.server.level.ChunkMap$2
- XXX.server.level.ChunkMap$DistanceManager
+ XXX.server.level.ChunkMap$TrackedEntity
- XXX.server.level.ChunkTaskPriorityQueue
+ XXX.server.level.ChunkTaskPriorityQueueSorter
- XXX.server.level.ChunkTaskPriorityQueueSorter$Message
+ XXX.server.level.ChunkTaskPriorityQueueSorter$Release
- XXX.server.level.ChunkTracker
+ XXX.server.level.ColumnPos
- XXX.server.level.DemoMode
+ XXX.server.level.DistanceManager
- XXX.server.level.DistanceManager$ChunkTicketTracker
+ XXX.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
- XXX.server.level.DistanceManager$PlayerTicketTracker
+ XXX.server.level.PlayerMap
- XXX.server.level.PlayerRespawnLogic
+ XXX.server.level.SectionTracker
- XXX.server.level.ServerBossEvent
+ XXX.server.level.ServerChunkCache
- XXX.server.level.ServerChunkCache$ChunkAndHolder
+ XXX.server.level.ServerChunkCache$MainThreadExecutor
- XXX.server.level.ServerEntity
+ XXX.server.level.ServerLevel
+ XXX.spectator.categories.package-info
+ XXX.spectator.categories.SpectatorPage
- XXX.spectator.categories.TeleportToPlayerMenuCategory
+ XXX.spectator.categories.TeleportToTeamMenuCategory
- XXX.spectator.categories.TeleportToTeamMenuCategory$TeamSelectionItem
+ XXX.state.predicate.BlockMaterialPredicate
+ XXX.storage.loot.ItemModifierManager$FunctionSequence
- XXX.storage.loot.LootContext$VisitedEntry
+ XXX.storage.loot.LootContextUser
- XXX.storage.loot.LootDataId
- XXX.storage.loot.LootDataManager$1
- XXX.storage.loot.LootDataManager$FunctionSequence
- XXX.storage.loot.LootDataType
- XXX.storage.loot.LootPool
+ XXX.storage.loot.LootPool$Builder
- XXX.storage.loot.LootPool$Serializer
+ XXX.storage.loot.LootTable
- XXX.storage.loot.LootTable$Builder
+ XXX.storage.loot.LootTable$Serializer
+ XXX.storage.loot.PredicateManager
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
+ XXX.util.datafix.package-info
+ XXX.util.task.CloseServerTask
- XXX.util.task.ConnectTask
+ XXX.util.task.DownloadTask
- XXX.util.task.GetServerDetailsTask
+ XXX.util.task.LongRunningTask
- XXX.util.task.OpenServerTask
- XXX.util.task.package-info
+ XXX.util.task.ResettingGeneratedWorldTask
- XXX.util.task.ResettingTemplateWorldTask
+ XXX.util.task.ResettingWorldTask
- XXX.util.task.RestoreTask
+ XXX.util.task.SwitchMinigameTask
- XXX.util.task.SwitchSlotTask
+ XXX.util.task.WorldCreationTask
+ XXX.voting.rules.BooleanRule$BooleanRuleChange
+ XXX.voting.rules.CounterRule$1
+ XXX.voting.rules.CounterRule$Simple
+ XXX.voting.rules.DoubleOrHalfRule
+ XXX.voting.rules.EnumRule$1
+ XXX.voting.rules.FixedOrRandomKeyRule
+ XXX.voting.rules.FixedOrRandomKeyRule$Change
+ XXX.voting.rules.MapRule$1
+ XXX.voting.rules.OneShotRule
+ XXX.voting.rules.OneShotRule$OneShotRuleChange
+ XXX.voting.rules.OneShotRule$Simple
+ XXX.voting.rules.package-info
+ XXX.voting.rules.RandomNumberRule$1
+ XXX.voting.rules.RandomNumberRule$RandomInt
+ XXX.voting.rules.ResourceKeyReplacementRule
+ XXX.voting.rules.ResourceKeySingleRule
+ XXX.voting.rules.ResourceKeySingleRule$Change
+ XXX.voting.rules.RuleAction
+ XXX.voting.rules.RuleChange$1
+ XXX.voting.rules.Rules
+ XXX.voting.rules.Rules$10
+ XXX.voting.rules.Rules$12
+ XXX.voting.rules.Rules$14
+ XXX.voting.rules.Rules$16
+ XXX.voting.rules.Rules$18
+ XXX.voting.rules.Rules$2
+ XXX.voting.rules.Rules$21
+ XXX.voting.rules.Rules$23
+ XXX.voting.rules.Rules$25
+ XXX.voting.rules.Rules$27
+ XXX.voting.rules.Rules$29
+ XXX.voting.rules.Rules$30
+ XXX.voting.rules.Rules$32
+ XXX.voting.rules.Rules$34
+ XXX.voting.rules.Rules$36
+ XXX.voting.rules.Rules$38
+ XXX.voting.rules.Rules$4
+ XXX.voting.rules.Rules$41
+ XXX.voting.rules.Rules$43
+ XXX.voting.rules.Rules$6
+ XXX.voting.rules.Rules$8
+ XXX.voting.rules.SetRule
+ XXX.voting.rules.UniformIntRule
+ XXX.voting.rules.UniformIntRule$Change
+ XXX.voting.rules.VotingCostRule$1
+ XXX.voting.votes.ClientVote$ClientOption
+ XXX.voting.votes.FinishedVote
+ XXX.voting.votes.FinishedVote$1ResultPair
+ XXX.voting.votes.OptionId
+ XXX.voting.votes.OptionVotes
+ XXX.voting.votes.package-info
+ XXX.voting.votes.ServerVote$Effect
+ XXX.voting.votes.ServerVote$VoteGenerationOptions
+ XXX.voting.votes.ServerVoteStorage$OptionAccess
+ XXX.voting.votes.TieResolutionStrategy
+ XXX.voting.votes.VoteResults$OptionResult
+ XXX.voting.votes.VoterMap
+ XXX.voting.votes.VoteStorage
+ XXX.voting.votes.VotingMaterial$1
+ XXX.voting.votes.VotingMaterial$Cost
+ XXX.voting.votes.VotingMaterial$Type
+ XXX.voting.votes.VotingMaterial$Type$2
+ XXX.voting.votes.VotingMaterial$Type$4
+ XXX.voting.votes.VotingMaterial$VotingItem
+ XXX.voting.votes.VotingMaterial$VotingResource$1
+ XXX.world.damagesource.CombatEntry
- XXX.world.damagesource.CombatRules
+ XXX.world.damagesource.CombatTracker
- XXX.world.damagesource.DamageEffects
+ XXX.world.damagesource.DamageScaling
- XXX.world.damagesource.DamageSource
+ XXX.world.damagesource.DamageSource$1
- XXX.world.damagesource.DamageSources
+ XXX.world.damagesource.DamageType
- XXX.world.damagesource.DamageTypes
+ XXX.world.damagesource.DeathMessageType
- XXX.world.damagesource.package-info
+ XXX.world.effect.AbsoptionMobEffect
- XXX.world.effect.AttackDamageMobEffect
+ XXX.world.effect.HealthBoostMobEffect
- XXX.world.effect.InstantenousMobEffect
+ XXX.world.effect.MobEffect
- XXX.world.effect.MobEffectCategory
+ XXX.world.effect.MobEffectInstance
- XXX.world.effect.MobEffectInstance$FactorData
- XXX.world.effect.MobEffects
+ XXX.world.effect.MobEffects$1
+ XXX.world.effect.MobEffectUtil
- XXX.world.effect.package-info
+ XXX.world.entity.AgeableMob
- XXX.world.entity.AgeableMob$AgeableMobGroupData
+ XXX.world.entity.AnimationState
- XXX.world.entity.AreaEffectCloud
+ XXX.world.entity.Attackable
- XXX.world.entity.Display
+ XXX.world.entity.Display$1
- XXX.world.entity.Display$BillboardConstraints
+ XXX.world.entity.Display$BlockDisplay
- XXX.world.entity.Display$BlockDisplay$BlockRenderState
+ XXX.world.entity.Display$ColorInterpolator
- XXX.world.entity.Display$FloatInterpolator
+ XXX.world.entity.Display$GenericInterpolator
- XXX.world.entity.Display$IntInterpolator
+ XXX.world.entity.Display$ItemDisplay
- XXX.world.entity.Display$ItemDisplay$1
+ XXX.world.entity.Display$ItemDisplay$ItemRenderState
+ XXX.world.entity.Display$LinearlyInterpolatedBlockAnimator
- XXX.world.entity.Display$RenderState
+ XXX.world.entity.Display$StencilDisplay
+ XXX.world.entity.Display$TextDisplay
- XXX.world.entity.Display$TextDisplay$Align
+ XXX.world.entity.Display$TextDisplay$CachedInfo
- XXX.world.entity.Display$TextDisplay$CachedLine
+ XXX.world.entity.Display$TextDisplay$LineSplitter
- XXX.world.entity.Display$TextDisplay$TextRenderState
+ XXX.world.entity.Display$TransformationInterpolator
- XXX.world.entity.Entity
+ XXX.world.entity.Entity$1
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
+ XXX.world.food.Thirst
+ XXX.world.item.BottleOfEntityItem
+ XXX.world.item.DyeableArmorItem
- XXX.world.item.DyeableHorseArmorItem
+ XXX.world.item.DyeableLeatherItem
+ XXX.world.item.DyeColor
- XXX.world.item.DyeItem
- XXX.world.item.EggItem
+ XXX.world.item.ElytraItem
+ XXX.world.item.NameTagItem
- XXX.world.item.PickaxeItem
+ XXX.world.item.PlaceOnWaterBlockItem
- XXX.world.item.PlayerHeadItem
+ XXX.world.item.PotionItem
- XXX.world.item.ProjectileWeaponItem
+ XXX.world.item.Rarity
- XXX.world.item.RecordItem
+ XXX.world.item.SaddleItem
- XXX.world.item.ScaffoldingBlockItem
+ XXX.world.item.ServerItemCooldowns
- XXX.world.item.ShearsItem
+ XXX.world.item.ShieldItem
- XXX.world.item.ShovelItem
+ XXX.world.item.SignApplicator
- XXX.world.item.SignItem
+ XXX.world.item.SimpleFoiledItem
- XXX.world.item.SmithingTemplateItem
+ XXX.world.item.SnowballItem
- XXX.world.item.SolidBucketItem
+ XXX.world.item.SpawnEggItem
- XXX.world.item.SpectralArrowItem
+ XXX.world.item.SplashBottleOfEntityItem
+ XXX.world.item.TagContainerItem
- XXX.world.item.ThrowablePotionItem
+ XXX.world.item.Tier
- XXX.world.item.TieredItem
+ XXX.world.item.Tiers
- XXX.world.item.TippedArrowItem
+ XXX.world.item.TooltipFlag
- XXX.world.item.TooltipFlag$Default
+ XXX.world.item.TridentItem
- XXX.world.item.UseAnim
+ XXX.world.item.Vanishable
- XXX.world.item.WritableBookItem
+ XXX.world.item.WrittenBookItem
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
XXX.blaze3d.platform.GlConst -6P
```
```
XXX.blaze3d.systems.RenderSystem +63M -65M
```
```
XXX.mojang.realmsclient.RealmsMainScreen$RealmSelectionList -3M
```
```
XXX.mojang.realmsclient.RealmsMainScreen$ServerEntry +1M
```
```
XXX.gui.screens.RealmsBackupScreen$Entry +8M -3M | +5P
```
```
XXX.gui.screens.RealmsPendingInvitesScreen +1M -1M
```
```
XXX.gui.screens.RealmsPlayerScreen +1M -6M | +2P -6P
```
```
XXX.gui.screens.RealmsPlayerScreen$InvitedObjectSelectionList +1M -2M
```
```
XXX.client.gui.Gui +1M -2M | -1P
```
```
XXX.gui.components.EditBox +2M -1M
```
```
XXX.gui.components.LogoRenderer -2M | +8P
```
```
XXX.font.glyphs.BakedGlyph +1M -1M
```
```
XXX.client.model.PiglinModel -1M
```
```
XXX.client.player.RemotePlayer +1M -1M
```
```
XXX.client.renderer.FogRenderer +1M -1M
```
```
XXX.client.renderer.GameRenderer +7M -10M | -2P
```
```
XXX.client.renderer.ShaderInstance -1P
```
```
XXX.client.renderer.Sheets -1P
```
```
XXX.renderer.blockentity.BannerRenderer -2P
```
```
XXX.renderer.blockentity.PistonHeadRenderer -1P
```
```
XXX.renderer.blockentity.SignRenderer +7M -5M | +2P -1P
```
```
XXX.renderer.entity.BeeRenderer -5M | -1P
```
```
XXX.renderer.item.ItemProperties +2M -3M
```
```
XXX.resources.sounds.SimpleSoundInstance +1M -1M
```
```
XXX.loot.packs.VanillaBlockLoot +1M -2M
```
```
XXX.data.models.BlockModelGenerators +1M -11M
```
```
XXX.models.model.ModelTemplates +1P -2P
```
```
XXX.data.recipes.ShapedRecipeBuilder$Result +1M -1M | -2P
```
```
XXX.data.tags.VanillaBlockTagsProvider +1M
```
```
XXX.data.worldgen.SurfaceRuleData -1M | -1P
```
```
XXX.server.network.ServerGamePacketListenerImpl +1M -6M | +1P -4P
```
```
XXX.packs.resources.SimpleJsonResourceReloadListener +1M
```
```
XXX.minecraft.sounds.SoundEvents -1P
```
```
XXX.minecraft.tags.BannerPatternTags -1P
```
```
XXX.minecraft.tags.BlockTags +5P -2P
```
```
XXX.minecraft.tags.ItemTags -2P
```
```
XXX.minecraft.util.StringUtil +1M -1M
```
```
XXX.util.random.WeightedRandomList -1M
```
```
XXX.world.entity.LivingEntity +9M -40M | -5P
```
```
XXX.world.entity.Mob +1M -7M
```
```
XXX.world.entity.PathfinderMob -1M
```
```
XXX.ai.behavior.CelebrateVillagersSurvivedRaid +1M -1M
```
```
XXX.ai.control.MoveControl -1M
```
```
XXX.ai.goal.RandomStrollGoal -1M | -1P
```
```
XXX.entity.animal.Bee +1M -2M
```
```
XXX.entity.monster.AbstractSkeleton -2M
```
```
XXX.entity.monster.Blaze -1M
```
```
XXX.monster.piglin.PiglinBrute +1M -1M
```
```
XXX.entity.npc.AbstractVillager -2M | -1P
```
```
XXX.entity.npc.VillagerTrades$DyedArmorForEmeralds +1M -1M
```
```
XXX.entity.npc.VillagerTrades$EmeraldsForVillagerTypeItem +1M -1M
```
```
XXX.entity.npc.VillagerTrades$EnchantedItemForEmeralds +1M -1M
```
```
XXX.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems +1M -1M
```
```
XXX.entity.npc.VillagerTrades$SuspiciousStewForEmerald +1M -1M
```
```
XXX.entity.npc.VillagerTrades$TreasureMapForEmeralds +1M -1M
```
```
XXX.entity.player.Player +6M -23M | -3P
```
```
XXX.entity.player.Player$BedSleepingProblem -1P
```
```
XXX.entity.projectile.AbstractHurtingProjectile +1M -1M
```
```
XXX.entity.projectile.DragonFireball +1M -1M
```
```
XXX.entity.projectile.EyeOfEnder -1M
```
```
XXX.entity.projectile.ShulkerBullet +1M -1M
```
```
XXX.entity.projectile.ThrowableItemProjectile -1M
```
```
XXX.world.inventory.AbstractContainerMenu +1M -3M
```
```
XXX.world.item.BedItem -3M | -1P
```
```
XXX.world.item.BrushItem +1M -1M
```
```
XXX.world.item.CreativeModeTabs +18M -23M
```
```
XXX.world.item.Items -33P
```
```
XXX.item.crafting.ArmorDyeRecipe +2M -2M
```
```
XXX.item.crafting.CustomRecipe +1M -1M
```
```
XXX.item.crafting.RecipeManager +8M -10M
```
```
XXX.item.crafting.RepairItemRecipe +3M -3M
```
```
XXX.item.crafting.ShulkerBoxColoring +2M -2M
```
```
XXX.item.crafting.SmithingTransformRecipe +2M -2M
```
```
XXX.item.crafting.SmithingTrimRecipe +2M -2M
```
```
XXX.item.crafting.SuspiciousStewRecipe +2M -2M
```
```
XXX.world.level.ColorResolver +1P -1P
```
```
XXX.world.level.Level +4M -12M | -5P
```
```
XXX.world.level.NaturalSpawner -1M
```
```
XXX.level.biome.Biome +6M -7M
```
```
XXX.level.biome.Biomes -1P
```
```
XXX.level.block.ChestBlock -1M
```
```
XXX.level.block.HoneyBlock -2M
```
```
XXX.level.block.IronBarsBlock -2M
```
```
XXX.level.block.LeverBlock -2M
```
```
XXX.level.block.LiquidBlock -2M
```
```
XXX.level.block.NetherPortalBlock +1M -1M | -1P
```
```
XXX.level.block.PitcherCropBlock +2M | +4P -2P
```
```
XXX.level.block.StainedGlassPaneBlock -1M
```
```
XXX.level.block.TntBlock +1M -3M
```
```
XXX.level.block.TorchflowerCropBlock +1P
```
```
XXX.level.block.WallHangingSignBlock +1M
```
```
XXX.level.block.WeightedPressurePlateBlock -1M
```
```
XXX.block.entity.CalibratedSculkSensorBlockEntity$VibrationConfig +1M
```
```
XXX.block.entity.ChestBlockEntity -5M | -1P
```
```
XXX.block.entity.DropperBlockEntity -4M | -1P
```
```
XXX.block.piston.PistonBaseBlock -1M
```
```
XXX.block.piston.PistonMovingBlockEntity -2M | -1P
```
```
XXX.block.piston.PistonStructureResolver +1M -1M
```
```
XXX.block.state.BlockBehaviour -3M
```
```
XXX.block.state.BlockBehaviour$BlockStateBase +1M -3M | +1P
```
```
XXX.block.state.BlockBehaviour$Properties +1M | +1P
```
```
XXX.state.properties.SculkSensorPhase -1P
```
```
XXX.gameevent.vibrations.VibrationListener +1M
```
```
XXX.levelgen.feature.Feature -2P
```
```
XXX.structure.structures.DesertPyramidStructure +2M -1M
```
```
XXX.level.material.Material$Builder -1M | -1P
```
```
XXX.level.portal.PortalShape +6M -7M | +1P -5P
```
```
XXX.level.storage.LevelResource -2P
```
```
XXX.storage.loot.ValidationContext +6M -10M | +2P -4P
```
```
XXX.loot.entries.LootTableReference +3M -1M
```
```
XXX.loot.functions.LootItemFunctions +1P
```
```
XXX.loot.predicates.ConditionReference +3M -1M
```
```
XXX.world.phys.AABB -1M
```

</details>
<details>
<summary>
com.mojang.blaze3d.systems.RenderSystem
</summary>

```diff
+ void cullFace(int)
- void lambda$activeTexture$13(int)
+ void lambda$activeTexture$14(int)
- void lambda$applyModelViewMatrix$69(Matrix4f)
+ void lambda$applyModelViewMatrix$70(Matrix4f)
- void lambda$backupProjectionMatrix$70()
+ void lambda$backupProjectionMatrix$71()
- void lambda$bindTexture$16(int)
+ void lambda$bindTexture$17(int)
- void lambda$clear$25(int,boolean)
+ void lambda$clear$26(int,boolean)
- void lambda$clearColor$23(float,float,float,float)
+ void lambda$clearColor$24(float,float,float,float)
- void lambda$clearDepth$22(double)
+ void lambda$clearDepth$23(double)
- void lambda$clearStencil$24(int)
+ void lambda$clearStencil$25(int)
- void lambda$colorMask$18(boolean,boolean,boolean,boolean)
+ void lambda$colorMask$19(boolean,boolean,boolean,boolean)
+ void lambda$cullFace$10(int)
- void lambda$deleteTexture$15(int)
+ void lambda$deleteTexture$16(int)
- void lambda$drawElements$33(int,int,int)
+ void lambda$drawElements$34(int,int,int)
- void lambda$getString$37(int,Consumer)
+ void lambda$getString$38(int,Consumer)
- void lambda$glBindBuffer$39(int,IntSupplier)
+ void lambda$glBindBuffer$40(int,IntSupplier)
- void lambda$glBindVertexArray$40(Supplier)
+ void lambda$glBindVertexArray$41(Supplier)
- void lambda$glDeleteBuffers$41(int)
+ void lambda$glDeleteBuffers$42(int)
- void lambda$glDeleteVertexArrays$42(int)
+ void lambda$glDeleteVertexArrays$43(int)
- void lambda$glGenBuffers$60(Consumer)
+ void lambda$glGenBuffers$61(Consumer)
- void lambda$glGenVertexArrays$61(Consumer)
+ void lambda$glGenVertexArrays$62(Consumer)
- void lambda$glUniform1$44(int,IntBuffer)
+ void lambda$glUniform1$45(int,IntBuffer)
- void lambda$glUniform1$48(int,FloatBuffer)
+ void lambda$glUniform1$49(int,FloatBuffer)
- void lambda$glUniform1i$43(int,int)
+ void lambda$glUniform1i$44(int,int)
- void lambda$glUniform2$45(int,IntBuffer)
+ void lambda$glUniform2$46(int,IntBuffer)
- void lambda$glUniform2$49(int,FloatBuffer)
+ void lambda$glUniform2$50(int,FloatBuffer)
- void lambda$glUniform3$46(int,IntBuffer)
+ void lambda$glUniform3$47(int,IntBuffer)
- void lambda$glUniform3$50(int,FloatBuffer)
+ void lambda$glUniform3$51(int,FloatBuffer)
- void lambda$glUniform4$47(int,IntBuffer)
+ void lambda$glUniform4$48(int,IntBuffer)
- void lambda$glUniform4$51(int,FloatBuffer)
+ void lambda$glUniform4$52(int,FloatBuffer)
- void lambda$glUniformMatrix2$52(int,boolean,FloatBuffer)
+ void lambda$glUniformMatrix2$53(int,boolean,FloatBuffer)
- void lambda$glUniformMatrix3$53(int,boolean,FloatBuffer)
+ void lambda$glUniformMatrix3$54(int,boolean,FloatBuffer)
- void lambda$glUniformMatrix4$54(int,boolean,FloatBuffer)
+ void lambda$glUniformMatrix4$55(int,boolean,FloatBuffer)
- void lambda$lineWidth$34(float)
+ void lambda$lineWidth$35(float)
- void lambda$logicOp$12(GlStateManager$LogicOp)
+ void lambda$logicOp$13(GlStateManager$LogicOp)
- void lambda$pixelStore$35(int,int)
+ void lambda$pixelStore$36(int,int)
- void lambda$polygonMode$10(int,int)
+ void lambda$polygonMode$11(int,int)
- void lambda$polygonOffset$11(float,float)
+ void lambda$polygonOffset$12(float,float)
- void lambda$readPixels$36(int,int,int,int,int,int,ByteBuffer)
+ void lambda$readPixels$37(int,int,int,int,int,int,ByteBuffer)
- void lambda$renderCrosshair$38(int)
+ void lambda$renderCrosshair$39(int)
- void lambda$resetTextureMatrix$68()
+ void lambda$resetTextureMatrix$69()
- void lambda$restoreProjectionMatrix$71()
+ void lambda$restoreProjectionMatrix$72()
- void lambda$setInverseViewRotationMatrix$66(Matrix3f)
+ void lambda$setInverseViewRotationMatrix$67(Matrix3f)
- void lambda$setProjectionMatrix$65(Matrix4f,VertexSorting)
+ void lambda$setProjectionMatrix$66(Matrix4f,VertexSorting)
- void lambda$setShader$62(Supplier)
+ void lambda$setShader$63(Supplier)
- void lambda$setShaderColor$32(float,float,float,float)
+ void lambda$setShaderColor$33(float,float,float,float)
- void lambda$setShaderFogColor$29(float,float,float,float)
+ void lambda$setShaderFogColor$30(float,float,float,float)
- void lambda$setShaderFogEnd$28(float)
+ void lambda$setShaderFogEnd$29(float)
- void lambda$setShaderFogShape$30(FogShape)
+ void lambda$setShaderFogShape$31(FogShape)
- void lambda$setShaderFogStart$26(float)
+ void lambda$setShaderFogStart$27(float)
- void lambda$setShaderGameTime$72(float)
+ void lambda$setShaderGameTime$73(float)
- void lambda$setShaderGlintAlpha$27(float)
+ void lambda$setShaderGlintAlpha$28(float)
- void lambda$setShaderLights$31(Vector3f,Vector3f)
+ void lambda$setShaderLights$32(Vector3f,Vector3f)
- void lambda$setShaderTexture$63(int,ResourceLocation)
- void lambda$setShaderTexture$64(int,int)
+ void lambda$setShaderTexture$64(int,ResourceLocation)
+ void lambda$setShaderTexture$65(int,int)
- void lambda$setTextureMatrix$67(Matrix4f)
+ void lambda$setTextureMatrix$68(Matrix4f)
- void lambda$setupGui3DDiffuseLighting$59(Vector3f,Vector3f)
+ void lambda$setupGui3DDiffuseLighting$60(Vector3f,Vector3f)
- void lambda$setupGuiFlatDiffuseLighting$58(Vector3f,Vector3f)
+ void lambda$setupGuiFlatDiffuseLighting$59(Vector3f,Vector3f)
- void lambda$setupLevelDiffuseLighting$57(Vector3f,Vector3f,Matrix4f)
+ void lambda$setupLevelDiffuseLighting$58(Vector3f,Vector3f,Matrix4f)
- void lambda$setupOverlayColor$55(IntSupplier)
+ void lambda$setupOverlayColor$56(IntSupplier)
- void lambda$stencilFunc$19(int,int,int)
+ void lambda$stencilFunc$20(int,int,int)
- void lambda$stencilMask$20(int)
+ void lambda$stencilMask$21(int)
- void lambda$stencilOp$21(int,int,int)
+ void lambda$stencilOp$22(int,int,int)
- void lambda$teardownOverlayColor$56()
+ void lambda$teardownOverlayColor$57()
- void lambda$texParameter$14(int,int,int)
+ void lambda$texParameter$15(int,int,int)
- void lambda$viewport$17(int,int,int,int)
+ void lambda$viewport$18(int,int,int,int)
```

</details>
<details>
<summary>
com.mojang.realmsclient.RealmsMainScreen$RealmSelectionList
</summary>

```diff
+ boolean keyPressed(int,int,int)
+ boolean mouseClicked(double,double,int)
+ void itemClicked(int,int,double,double,int,int)
```

</details>
<details>
<summary>
com.mojang.realmsclient.RealmsMainScreen$ServerEntry
</summary>

```diff
- boolean keyPressed(int,int,int)
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsBackupScreen$Entry
</summary>

```diff
- boolean mouseClicked(double,double,int)
- void addChangesButton()
- void addRestoreButton()
- void addToChangeList(String)
+ void drawInfo(PoseStack,int,int,int,int)
+ void drawRestore(PoseStack,int,int,int,int)
- void lambda$addChangesButton$0(Button)
- void lambda$addRestoreButton$1(Button)
- void lambda$render$2(int,PoseStack,int,int,float,AbstractWidget)
- void populateChangeList(Backup)
+ void renderBackupItem(PoseStack,Backup,int,int,int,int)
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsPendingInvitesScreen
</summary>

```diff
- void <init>(Screen,Component)
+ void <init>(Screen)
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsPlayerScreen
</summary>

```diff
+ void deleteFromInvitedList(int)
+ void drawNormal(PoseStack,int,int,int,int)
+ void drawOpped(PoseStack,int,int,int,int)
+ void drawRemoveIcon(PoseStack,int,int,int,int)
+ void lambda$uninvite$4(boolean)
- void lambda$uninvite$4(PlayerInfo,boolean)
+ void renderMousehoverTooltip(PoseStack,Component,int,int)
```

</details>
<details>
<summary>
com.mojang.realmsclient.gui.screens.RealmsPlayerScreen$InvitedObjectSelectionList
</summary>

```diff
+ boolean mouseClicked(double,double,int)
+ void itemClicked(int,int,double,double,int,int)
- void updateButtons()
```

</details>
<details>
<summary>
net.minecraft.client.gui.Gui
</summary>

```diff
+ void renderPortalOverlay(PoseStack,float,boolean)
- void renderPortalOverlay(PoseStack,float)
+ void renderTestVote(PoseStack)
```

</details>
<details>
<summary>
net.minecraft.client.gui.components.EditBox
</summary>

```diff
+ boolean mouseClicked(double,double,int)
- void onClick(double,double)
- void playDownSound(SoundManager)
```

</details>
<details>
<summary>
net.minecraft.client.gui.components.LogoRenderer
</summary>

```diff
+ void lambda$renderLogo$0(PoseStack,Integer,Integer)
+ void lambda$renderLogo$1(PoseStack,Integer,Integer)
```

</details>
<details>
<summary>
net.minecraft.client.gui.font.glyphs.BakedGlyph
</summary>

```diff
+ void render(boolean,boolean,float,float,Matrix4f,VertexConsumer,float,float,float,float,int)
- void render(boolean,float,float,Matrix4f,VertexConsumer,float,float,float,float,int)
```

</details>
<details>
<summary>
net.minecraft.client.model.PiglinModel
</summary>

```diff
+ boolean miniMe()
```

</details>
<details>
<summary>
net.minecraft.client.player.RemotePlayer
</summary>

```diff
- boolean hurt(DamageSource,float)
+ boolean hurtInternal(DamageSource,float)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.FogRenderer
</summary>

```diff
+ Vec3 lambda$setupColor$0(BiomeManager,ClientLevel,float,int,int,int)
- Vec3 lambda$setupColor$0(ClientLevel,BiomeManager,float,int,int,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.GameRenderer
</summary>

```diff
+ boolean isEffectActive(ResourceLocation)
- boolean lambda$pick$59(Entity)
+ boolean lambda$pick$60(Entity)
+ ShaderInstance getPositionTexFunkyShader()
- String lambda$render$60()
+ String lambda$render$62()
- String lambda$render$62(int,int)
- String lambda$render$63()
+ String lambda$render$63(int,int)
+ String lambda$render$65()
- void lambda$reloadShaders$57(Pair)
+ void lambda$reloadShaders$57(ShaderInstance)
+ void lambda$reloadShaders$59(Pair)
- void lambda$takeAutoScreenshot$66(NativeImage,Path)
+ void lambda$takeAutoScreenshot$67(NativeImage,Path)
- void lambda$tryTakeScreenshotIfNeeded$65(Path)
+ void lambda$tryTakeScreenshotIfNeeded$66(Path)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.blockentity.SignRenderer
</summary>

```diff
- float getSignModelRenderScale()
- float getSignTextRenderScale()
- Vec3 getTextOffset()
+ Vec3 getTextOffset(float)
+ void renderSign(PoseStack,MultiBufferSource,int,int,float,WoodType,Model)
- void renderSign(PoseStack,MultiBufferSource,int,int,WoodType,Model)
+ void renderSignText(BlockPos,SignText,PoseStack,MultiBufferSource,int,float,Vec3,int,int,boolean)
- void renderSignText(BlockPos,SignText,PoseStack,MultiBufferSource,int,int,int,boolean)
+ void renderSignWithText(SignBlockEntity,PoseStack,MultiBufferSource,int,int,BlockState,SignBlock,WoodType,Model,float)
- void renderSignWithText(SignBlockEntity,PoseStack,MultiBufferSource,int,int,BlockState,SignBlock,WoodType,Model)
+ void translateSignText(float,PoseStack,boolean,Vec3)
- void translateSignText(PoseStack,boolean,Vec3)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.entity.BeeRenderer
</summary>

```diff
+ boolean isGlowTime(LevelTimeAccess)
+ void render(Bee,float,float,PoseStack,MultiBufferSource,int)
+ void render(Entity,float,float,PoseStack,MultiBufferSource,int)
+ void render(LivingEntity,float,float,PoseStack,MultiBufferSource,int)
+ void render(Mob,float,float,PoseStack,MultiBufferSource,int)
```

</details>
<details>
<summary>
net.minecraft.client.renderer.item.ItemProperties
</summary>

```diff
+ float lambda$static$11(ItemStack,ClientLevel,LivingEntity,int)
- float lambda$static$13(ItemStack,ClientLevel,LivingEntity,int)
+ float lambda$static$23(ItemStack,ClientLevel,LivingEntity,int)
- GlobalPos lambda$static$11(ClientLevel,ItemStack,Entity)
+ GlobalPos lambda$static$13(ClientLevel,ItemStack,Entity)
```

</details>
<details>
<summary>
net.minecraft.client.resources.sounds.SimpleSoundInstance
</summary>

```diff
- void <init>(ResourceLocation,SoundSource,float,float,RandomSource,boolean,int,SoundInstance$Attenuation,double,double,double,boolean)
+ void <init>(SoundEvent,SoundSource,float,float,RandomSource,boolean,int,SoundInstance$Attenuation,double,double,double,boolean)
```

</details>
<details>
<summary>
net.minecraft.data.loot.packs.VanillaBlockLoot
</summary>

```diff
- LootPoolEntryContainer$Builder lambda$createPitcherCropLoot$238(Integer)
+ LootPoolEntryContainer$Builder lambda$createPitcherCropLoot$239(Integer)
+ LootTable$Builder lambda$generate$238(Block)
```

</details>
<details>
<summary>
net.minecraft.data.models.BlockModelGenerators
</summary>

```diff
+ boolean isOnEdge(double,double,double,double,double,double,Direction)
+ JsonElement lambda$createCheeseBlock$58(ResourceLocation,VoxelShape)
+ JsonObject buildModelFromShape(ResourceLocation,VoxelShape)
+ void createCheeseBlock()
+ void createFacing(Block)
- void createNetherPortalBlock()
+ void createNetherPortalBlock(Block)
+ void createPackedAir()
+ void createSpleaves(Block)
+ void lambda$buildModelFromShape$59(double,double,double,JsonArray)
+ void lambda$buildModelFromShape$60(double,double,double,JsonArray)
+ void lambda$buildModelFromShape$61(JsonArray,double,double,double,double,double,double)
```

</details>
<details>
<summary>
net.minecraft.data.recipes.ShapedRecipeBuilder$Result
</summary>

```diff
+ void <init>(ResourceLocation,Item,int,String,CraftingBookCategory,List,Map,Advancement$Builder,ResourceLocation,boolean,boolean,boolean)
- void <init>(ResourceLocation,Item,int,String,CraftingBookCategory,List,Map,Advancement$Builder,ResourceLocation,boolean)
```

</details>
<details>
<summary>
net.minecraft.data.tags.VanillaBlockTagsProvider
</summary>

```diff
- boolean lambda$addTags$1(Block)
```

</details>
<details>
<summary>
net.minecraft.data.worldgen.SurfaceRuleData
</summary>

```diff
+ SurfaceRules$RuleSource moon()
```

</details>
<details>
<summary>
net.minecraft.server.network.ServerGamePacketListenerImpl
</summary>

```diff
- CompletableFuture lambda$resetPlayerChatState$15(RemoteChatSession,Executor)
+ CompletableFuture lambda$resetPlayerChatState$16(RemoteChatSession,Executor)
+ float maxInteractionDistanceSq()
+ int lambda$fireworksYay$15(RandomSource)
+ void fireworksYay()
+ void handleCrashVehicle(ServerboundCrashVehiclePacket)
+ void handleVoteCast(ServerboundVoteCastPacket)
```

</details>
<details>
<summary>
net.minecraft.server.packs.resources.SimpleJsonResourceReloadListener
</summary>

```diff
- void scanDirectory(ResourceManager,String,Gson,Map)
```

</details>
<details>
<summary>
net.minecraft.util.StringUtil
</summary>

```diff
- String formatTickDuration(int)
+ String formatTickDuration(long)
```

</details>
<details>
<summary>
net.minecraft.util.random.WeightedRandomList
</summary>

```diff
+ Optional getRandomUnweighted(RandomSource)
```

</details>
<details>
<summary>
net.minecraft.world.entity.LivingEntity
</summary>

```diff
+ boolean canDie(DamageSource)
+ boolean canSpawnFootprintParticle()
+ boolean canTransformBreatheInAir()
+ boolean fireImmune()
- boolean hurt(DamageSource,float)
+ boolean hurtInternal(DamageSource,float)
+ boolean isGold()
+ boolean isSilent()
+ boolean isSunBurnTick()
+ Boolean lambda$checkBedExists$10(BlockPos)
- Boolean lambda$checkBedExists$7(BlockPos)
- boolean lambda$createEquipmentSlotAccess$10(EquipmentSlot,ItemStack)
+ boolean lambda$createEquipmentSlotAccess$13(EquipmentSlot,ItemStack)
- boolean lambda$isHolding$4(Item,ItemStack)
+ boolean lambda$isHolding$6(Item,ItemStack)
+ boolean noCulling()
+ double getMyRidingOffset()
+ double getPassengersRidingOffset()
+ Entity effectiveEntity()
+ EntityTransform getTransform()
+ EntityTransformType getTransformType()
+ EntityTransformType lambda$canDie$5(EntityTransformType)
+ EntityTransformType lambda$tick$7(float,EntityTransformType)
+ float getInWaterSpeed()
+ float getScaleModifier()
+ float getTransformScale(float)
+ float transformScaleDropModifier()
+ InteractionResult interact(Player,InteractionHand)
+ LivingEntity effectiveLivingEntity()
+ Vec3 lambda$stopSleeping$11(BlockPos)
- Vec3 lambda$stopSleeping$8(BlockPos)
+ void copyTransformedProperties(LivingEntity)
+ void knockback(double,double,double,boolean)
+ void lambda$addAdditionalSaveData$3(CompoundTag,Tag)
- void lambda$handleEquipmentChanges$5(List,EquipmentSlot,ItemStack)
+ void lambda$handleEquipmentChanges$8(List,EquipmentSlot,ItemStack)
+ void lambda$stopSleeping$12(BlockPos)
- void lambda$stopSleeping$9(BlockPos)
- void lambda$tickEffects$3(MobEffectInstance)
+ void lambda$tickEffects$4(MobEffectInstance)
- void lambda$updateFallFlying$6(LivingEntity)
+ void lambda$updateFallFlying$9(LivingEntity)
+ void onTransformChange()
+ void positionRider(Entity)
+ void postTick()
+ void setGold(boolean)
+ void setTransform(EntityTransformType)
+ void spawnDrownParticles()
+ void updateTransform(UnaryOperator)
```

</details>
<details>
<summary>
net.minecraft.world.entity.Mob
</summary>

```diff
+ boolean canBeCollidedWith()
+ boolean isItAwkwardToMilk()
- boolean isSunBurnTick()
+ float adjustDamage(float)
+ float getScaleModifier()
+ InteractionResult mobInteractButEarly(Player,InteractionHand)
+ InteractionResult transformInteract(Player,LivingEntity,InteractionHand)
+ void turnIntoGold()
```

</details>
<details>
<summary>
net.minecraft.world.entity.PathfinderMob
</summary>

```diff
+ void onDonePathing()
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.behavior.CelebrateVillagersSurvivedRaid
</summary>

```diff
- ItemStack getFirework(DyeColor,int)
+ ItemStack getFirework(int,int,int[])
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.control.MoveControl
</summary>

```diff
+ float targetYRot(double,double)
```

</details>
<details>
<summary>
net.minecraft.world.entity.ai.goal.RandomStrollGoal
</summary>

```diff
+ boolean lambda$new$0()
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Bee
</summary>

```diff
+ boolean canTransformFly()
- boolean hurt(DamageSource,float)
+ boolean hurtInternal(DamageSource,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.AbstractSkeleton
</summary>

```diff
+ void burnInSun(LivingEntity)
+ void transformedTick(EntityTransform,LivingEntity)
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Blaze
</summary>

```diff
+ boolean canTransformFly()
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.piglin.PiglinBrute
</summary>

```diff
- boolean hurt(DamageSource,float)
+ boolean hurtInternal(DamageSource,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.npc.AbstractVillager
</summary>

```diff
+ boolean isItAwkwardToMilk()
+ MerchantOffers getDefaultOffers()
```

</details>
<details>
<summary>
net.minecraft.world.entity.npc.VillagerTrades$DyedArmorForEmeralds
</summary>

```diff
+ MerchantOffer getOffer(Entity,RandomSource,Item)
- MerchantOffer getOffer(Entity,RandomSource)
```

</details>
<details>
<summary>
net.minecraft.world.entity.npc.VillagerTrades$EmeraldsForVillagerTypeItem
</summary>

```diff
+ MerchantOffer getOffer(Entity,RandomSource,Item)
- MerchantOffer getOffer(Entity,RandomSource)
```

</details>
<details>
<summary>
net.minecraft.world.entity.npc.VillagerTrades$EnchantedItemForEmeralds
</summary>

```diff
+ MerchantOffer getOffer(Entity,RandomSource,Item)
- MerchantOffer getOffer(Entity,RandomSource)
```

</details>
<details>
<summary>
net.minecraft.world.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
</summary>

```diff
+ MerchantOffer getOffer(Entity,RandomSource,Item)
- MerchantOffer getOffer(Entity,RandomSource)
```

</details>
<details>
<summary>
net.minecraft.world.entity.npc.VillagerTrades$SuspiciousStewForEmerald
</summary>

```diff
+ MerchantOffer getOffer(Entity,RandomSource,Item)
- MerchantOffer getOffer(Entity,RandomSource)
```

</details>
<details>
<summary>
net.minecraft.world.entity.npc.VillagerTrades$TreasureMapForEmeralds
</summary>

```diff
+ MerchantOffer getOffer(Entity,RandomSource,Item)
- MerchantOffer getOffer(Entity,RandomSource)
```

</details>
<details>
<summary>
net.minecraft.world.entity.player.Player
</summary>

```diff
+ boolean canFly()
- boolean hurt(DamageSource,float)
+ boolean hurtInternal(DamageSource,float)
+ boolean isFallFlying()
- boolean killedEntity(ServerLevel,LivingEntity)
+ boolean lambda$getBeeloons$7(Bee)
+ boolean lambda$getSpeedModifier$8(ItemStack)
+ boolean wasKilled(ServerLevel,LivingEntity)
+ float getInWaterSpeed()
+ float getJumpPower()
+ float getSpeedModifier()
+ int calculateFallDamage(float,float)
+ List getBeeloons()
- Optional lambda$addAdditionalSaveData$2(GlobalPos)
+ Optional lambda$addAdditionalSaveData$4(GlobalPos)
+ String getSkinName()
+ Style lambda$decorateDisplayNameComponent$10(String,Style)
- Style lambda$decorateDisplayNameComponent$6(String,Style)
+ Thirst thirst()
+ void callInsurance(float)
+ void dropCustomDeathLoot(DamageSource,int,boolean)
+ void lambda$addAdditionalSaveData$5(CompoundTag,Tag)
- void lambda$hurtCurrentlyUsedShield$4(InteractionHand,Player)
+ void lambda$hurtCurrentlyUsedShield$6(InteractionHand,Player)
+ void lambda$readAdditionalSaveData$2(Thirst)
- void lambda$respawnEntityOnShoulder$5(Entity)
+ void lambda$respawnEntityOnShoulder$9(Entity)
+ void onTransformChange()
+ void updateWalkAnimation(float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.AbstractHurtingProjectile
</summary>

```diff
- boolean hurt(DamageSource,float)
+ boolean hurtInternal(DamageSource,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.DragonFireball
</summary>

```diff
- boolean hurt(DamageSource,float)
+ boolean hurtInternal(DamageSource,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.EyeOfEnder
</summary>

```diff
+ void lambda$setItem$0(ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.ShulkerBullet
</summary>

```diff
- boolean hurt(DamageSource,float)
+ boolean hurtInternal(DamageSource,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.projectile.ThrowableItemProjectile
</summary>

```diff
+ void lambda$setItem$0(ItemStack)
```

</details>
<details>
<summary>
net.minecraft.world.inventory.AbstractContainerMenu
</summary>

```diff
- int getQuickCraftPlaceCount(Set,int,ItemStack)
+ void getQuickCraftSlotCount(Set,int,ItemStack,int)
+ void safeDropItem(Player,ItemStack)
+ void tick(Level)
```

</details>
<details>
<summary>
net.minecraft.world.item.BedItem
</summary>

```diff
+ boolean hurtEnemy(ItemStack,LivingEntity,LivingEntity)
+ Multimap getDefaultAttributeModifiers(EquipmentSlot)
+ void appendHoverText(ItemStack,Level,List,TooltipFlag)
```

</details>
<details>
<summary>
net.minecraft.world.item.BrushItem
</summary>

```diff
- void lambda$onUseTick$0(EquipmentSlot,LivingEntity)
+ void lambda$onUseTick$0(LivingEntity)
```

</details>
<details>
<summary>
net.minecraft.world.item.CreativeModeTabs
</summary>

```diff
- boolean lambda$buildAllTabContents$49(CreativeModeTab)
- boolean lambda$buildAllTabContents$51(CreativeModeTab)
+ boolean lambda$buildAllTabContents$52(CreativeModeTab)
+ boolean lambda$buildAllTabContents$54(CreativeModeTab)
- boolean lambda$generateEnchantmentBookTypesAllLevels$41(Set,Enchantment)
+ boolean lambda$generateEnchantmentBookTypesAllLevels$44(Set,Enchantment)
- boolean lambda$generateEnchantmentBookTypesOnlyMaxLevel$38(Set,Enchantment)
+ boolean lambda$generateEnchantmentBookTypesOnlyMaxLevel$41(Set,Enchantment)
+ boolean lambda$generateEntityPotions$35(Holder$Reference)
- boolean lambda$generatePotionEffectTypes$35(Holder$Reference)
+ boolean lambda$generatePotionEffectTypes$38(Holder$Reference)
- ItemStack lambda$generateEnchantmentBookTypesAllLevels$42(Enchantment,int)
+ ItemStack lambda$generateEnchantmentBookTypesAllLevels$45(Enchantment,int)
- ItemStack lambda$generateEnchantmentBookTypesOnlyMaxLevel$39(Enchantment)
+ ItemStack lambda$generateEnchantmentBookTypesOnlyMaxLevel$42(Enchantment)
+ ItemStack lambda$generateEntityPotions$36(Item,Holder$Reference)
- ItemStack lambda$generateInstrumentTypes$45(Item,Holder)
+ ItemStack lambda$generateInstrumentTypes$48(Item,Holder)
- ItemStack lambda$generatePotionEffectTypes$36(Item,Holder$Reference)
+ ItemStack lambda$generatePotionEffectTypes$39(Item,Holder$Reference)
- Stream lambda$generateEnchantmentBookTypesAllLevels$43(Enchantment)
+ Stream lambda$generateEnchantmentBookTypesAllLevels$46(Enchantment)
+ void generateEntityPotions(CreativeModeTab$Output,HolderLookup,Item,CreativeModeTab$TabVisibility)
- void lambda$buildAllTabContents$50(CreativeModeTab$ItemDisplayParameters,CreativeModeTab)
- void lambda$buildAllTabContents$52(CreativeModeTab$ItemDisplayParameters,CreativeModeTab)
+ void lambda$buildAllTabContents$53(CreativeModeTab$ItemDisplayParameters,CreativeModeTab)
+ void lambda$buildAllTabContents$55(CreativeModeTab$ItemDisplayParameters,CreativeModeTab)
- void lambda$generateEnchantmentBookTypesAllLevels$44(CreativeModeTab$Output,CreativeModeTab$TabVisibility,ItemStack)
+ void lambda$generateEnchantmentBookTypesAllLevels$47(CreativeModeTab$Output,CreativeModeTab$TabVisibility,ItemStack)
- void lambda$generateEnchantmentBookTypesOnlyMaxLevel$40(CreativeModeTab$Output,CreativeModeTab$TabVisibility,ItemStack)
+ void lambda$generateEnchantmentBookTypesOnlyMaxLevel$43(CreativeModeTab$Output,CreativeModeTab$TabVisibility,ItemStack)
+ void lambda$generateEntityPotions$37(CreativeModeTab$Output,CreativeModeTab$TabVisibility,ItemStack)
- void lambda$generateInstrumentTypes$46(CreativeModeTab$Output,CreativeModeTab$TabVisibility,ItemStack)
- void lambda$generateInstrumentTypes$47(Item,CreativeModeTab$Output,CreativeModeTab$TabVisibility,HolderSet$Named)
+ void lambda$generateInstrumentTypes$49(CreativeModeTab$Output,CreativeModeTab$TabVisibility,ItemStack)
+ void lambda$generateInstrumentTypes$50(Item,CreativeModeTab$Output,CreativeModeTab$TabVisibility,HolderSet$Named)
- void lambda$generatePotionEffectTypes$37(CreativeModeTab$Output,CreativeModeTab$TabVisibility,ItemStack)
+ void lambda$generatePotionEffectTypes$40(CreativeModeTab$Output,CreativeModeTab$TabVisibility,ItemStack)
- void lambda$generatePresetPaintings$48(CreativeModeTab$Output,CreativeModeTab$TabVisibility,Holder$Reference)
+ void lambda$generatePresetPaintings$51(CreativeModeTab$Output,CreativeModeTab$TabVisibility,Holder$Reference)
+ void resetTabContents()
```

</details>
<details>
<summary>
net.minecraft.world.item.crafting.ArmorDyeRecipe
</summary>

```diff
- ItemStack assemble(Container,RegistryAccess)
- ItemStack assemble(CraftingContainer,RegistryAccess)
+ ItemStack assembleRaw(Container,RegistryAccess)
+ ItemStack assembleRaw(CraftingContainer,RegistryAccess)
```

</details>
<details>
<summary>
net.minecraft.world.item.crafting.CustomRecipe
</summary>

```diff
- ItemStack getResultItem(RegistryAccess)
+ ItemStack getResultItemRaw(RegistryAccess)
```

</details>
<details>
<summary>
net.minecraft.world.item.crafting.RecipeManager
</summary>

```diff
+ boolean lambda$getAllRecipesFor$5(Map$Entry)
+ boolean lambda$getRecipeFor$2(Container,Level,Map$Entry)
- boolean lambda$getRecipeFor$2(Container,Level,Recipe)
+ boolean lambda$getRecipes$8(Map$Entry)
- boolean lambda$getRecipesFor$5(Container,Level,Recipe)
+ boolean lambda$getRecipesFor$6(Container,Level,Map$Entry)
+ JsonSyntaxException lambda$fromJson$11(String)
- JsonSyntaxException lambda$fromJson$9(String)
- Map lambda$replaceRecipes$10(RecipeType)
+ Map lambda$replaceRecipes$12(RecipeType)
+ Stream lambda$getRecipeIds$10(Map)
- Stream lambda$getRecipeIds$8(Map)
- Stream lambda$getRecipes$7(Map)
+ Stream lambda$getRecipes$9(Map)
- String lambda$getRecipesFor$6(Level,Recipe)
+ String lambda$getRecipesFor$7(Level,Recipe)
- void lambda$replaceRecipes$11(Map,ImmutableMap$Builder,Recipe)
+ void lambda$replaceRecipes$13(Map,ImmutableMap$Builder,Recipe)
```

</details>
<details>
<summary>
net.minecraft.world.item.crafting.RepairItemRecipe
</summary>

```diff
- ItemStack assemble(Container,RegistryAccess)
- ItemStack assemble(CraftingContainer,RegistryAccess)
+ ItemStack assembleRaw(Container,RegistryAccess)
+ ItemStack assembleRaw(CraftingContainer,RegistryAccess)
- void lambda$assemble$0(Map,Map,Map,Enchantment)
+ void lambda$assembleRaw$0(Map,Map,Map,Enchantment)
```

</details>
<details>
<summary>
net.minecraft.world.item.crafting.ShulkerBoxColoring
</summary>

```diff
- ItemStack assemble(Container,RegistryAccess)
- ItemStack assemble(CraftingContainer,RegistryAccess)
+ ItemStack assembleRaw(Container,RegistryAccess)
+ ItemStack assembleRaw(CraftingContainer,RegistryAccess)
```

</details>
<details>
<summary>
net.minecraft.world.item.crafting.SmithingTransformRecipe
</summary>

```diff
- ItemStack assemble(Container,RegistryAccess)
+ ItemStack assembleRaw(Container,RegistryAccess)
- ItemStack getResultItem(RegistryAccess)
+ ItemStack getResultItemRaw(RegistryAccess)
```

</details>
<details>
<summary>
net.minecraft.world.item.crafting.SmithingTrimRecipe
</summary>

```diff
- ItemStack assemble(Container,RegistryAccess)
+ ItemStack assembleRaw(Container,RegistryAccess)
- ItemStack getResultItem(RegistryAccess)
+ ItemStack getResultItemRaw(RegistryAccess)
```

</details>
<details>
<summary>
net.minecraft.world.item.crafting.SuspiciousStewRecipe
</summary>

```diff
- ItemStack assemble(Container,RegistryAccess)
- ItemStack assemble(CraftingContainer,RegistryAccess)
+ ItemStack assembleRaw(Container,RegistryAccess)
+ ItemStack assembleRaw(CraftingContainer,RegistryAccess)
```

</details>
<details>
<summary>
net.minecraft.world.level.Level
</summary>

```diff
- AbortableIterationConsumer$Continuation lambda$getEntities$2(Predicate,List,int,EntityTypeTest,Entity)
+ AbortableIterationConsumer$Continuation lambda$getEntities$4(Predicate,List,int,EntityTypeTest,Entity)
+ boolean isMoon()
+ boolean lambda$tickBlockEntities$1(BlockState)
+ double getGravity()
+ double getMoonSize()
+ int getRawBrightness(BlockPos,int)
+ Stream allChunks()
- String lambda$fillReportDetails$3()
- String lambda$fillReportDetails$4()
+ String lambda$fillReportDetails$5()
+ String lambda$fillReportDetails$6()
+ Vec3 getMoonPullVector()
- void lambda$getEntities$1(Entity,Predicate,List,Entity)
+ void lambda$getEntities$3(Entity,Predicate,List,Entity)
+ void lambda$tickBlockEntities$2(LevelChunkSection,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.NaturalSpawner
</summary>

```diff
+ EntityType replaceSpawnData(EntityType)
```

</details>
<details>
<summary>
net.minecraft.world.level.biome.Biome
</summary>

```diff
+ boolean increasedThirst(BlockPos)
- int getFogColor()
+ int getFogColor(Holder)
- int getFoliageColor()
+ int getFoliageColor(Holder)
- int getGrassColor(double,double)
+ int getGrassColor(Holder,double,double)
- int getSkyColor()
+ int getSkyColor(Holder)
- int getWaterColor()
+ int getWaterColor(Holder)
- int getWaterFogColor()
+ int getWaterFogColor(Holder)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.ChestBlock
</summary>

```diff
+ boolean isStickyToNeighbour(Level,BlockPos,BlockState,BlockPos,BlockState,Direction,Direction)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.HoneyBlock
</summary>

```diff
+ boolean canStickToStuff(BlockState)
+ boolean isStickyToNeighbour(Level,BlockPos,BlockState,BlockPos,BlockState,Direction,Direction)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.IronBarsBlock
</summary>

```diff
+ boolean canAirPass(BlockState,ServerLevel,BlockPos,Direction)
+ boolean canAirPassThroughGlassPane(BlockState,ServerLevel,BlockPos,Direction)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.LeverBlock
</summary>

```diff
+ boolean isRandomlyTicking(BlockState)
+ void randomTick(BlockState,ServerLevel,BlockPos,RandomSource)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.LiquidBlock
</summary>

```diff
+ boolean canAirPass(BlockState,ServerLevel,BlockPos,Direction)
+ boolean canStickToStuff(BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.NetherPortalBlock
</summary>

```diff
+ void <init>(BlockBehaviour$Properties,boolean)
- void <init>(BlockBehaviour$Properties)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.PitcherCropBlock
</summary>

```diff
- boolean isLower(BlockState)
- void entityInside(BlockState,Level,BlockPos,Entity)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.StainedGlassPaneBlock
</summary>

```diff
+ boolean canAirPass(BlockState,ServerLevel,BlockPos,Direction)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.TntBlock
</summary>

```diff
+ BlockState getStateForPlacement(BlockPlaceContext)
+ void explode(Level,BlockPos,BlockState)
+ void explode(Level,BlockPos,LivingEntity,BlockState)
- void explode(Level,BlockPos,LivingEntity)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.WallHangingSignBlock
</summary>

```diff
- BlockEntityTicker getTicker(Level,BlockState,BlockEntityType)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.WeightedPressurePlateBlock
</summary>

```diff
+ void entityInside(BlockState,Level,BlockPos,Entity)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.CalibratedSculkSensorBlockEntity$VibrationConfig
</summary>

```diff
- int getListenerRadius()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.ChestBlockEntity
</summary>

```diff
+ boolean isGold()
+ ClientboundBlockEntityDataPacket getUpdatePacket()
+ CompoundTag getUpdateTag()
+ Packet getUpdatePacket()
+ void setGold(boolean)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.entity.DropperBlockEntity
</summary>

```diff
+ boolean isLunar()
+ void load(CompoundTag)
+ void saveAdditional(CompoundTag)
+ void setLunar()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.piston.PistonBaseBlock
</summary>

```diff
+ boolean isStickyToNeighbour(Level,BlockPos,BlockState,BlockPos,BlockState,Direction,Direction)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.piston.PistonMovingBlockEntity
</summary>

```diff
+ BlockEntity getRenderBlockEntity()
+ void setCarriedBlockEntity(BlockEntity,Level)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.piston.PistonStructureResolver
</summary>

```diff
+ boolean canStickToEachOther(BlockPos,BlockState,BlockPos,BlockState,Direction)
- boolean canStickToEachOther(BlockState,BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.BlockBehaviour
</summary>

```diff
+ boolean canAirPass(BlockState,ServerLevel,BlockPos,Direction)
+ boolean canStickToStuff(BlockState)
+ boolean isStickyToNeighbour(Level,BlockPos,BlockState,BlockPos,BlockState,Direction,Direction)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase
</summary>

```diff
+ boolean canAirPass(ServerLevel,BlockPos,Direction)
+ boolean canStickToStuff()
+ boolean isStickyToNeighbour(Level,BlockPos,BlockPos,BlockState,Direction,Direction)
- boolean liquid()
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.BlockBehaviour$Properties
</summary>

```diff
- BlockBehaviour$Properties liquid()
```

</details>
<details>
<summary>
net.minecraft.world.level.gameevent.vibrations.VibrationListener
</summary>

```diff
- float distanceBetweenInBlocks(BlockPos,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.levelgen.structure.structures.DesertPyramidStructure
</summary>

```diff
+ void lambda$afterPlace$0(BlockPos,BrushableBlockEntity)
- void lambda$placeSuspiciousSand$0(BlockPos,BrushableBlockEntity)
- void placeSuspiciousSand(BoundingBox,WorldGenLevel,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.material.Material$Builder
</summary>

```diff
+ Material$Builder liquid()
```

</details>
<details>
<summary>
net.minecraft.world.level.portal.PortalShape
</summary>

```diff
- boolean lambda$findEmptyPortalShape$1(PortalShape)
+ boolean lambda$findEmptyPortalShape$2(PortalShape)
+ boolean lambda$static$1(BlockState,BlockGetter,BlockPos)
+ Optional findEmptyPortalShape(LevelAccessor,BlockPos,Direction$Axis,boolean)
- Optional findEmptyPortalShape(LevelAccessor,BlockPos,Direction$Axis)
+ Optional findPortalShape(LevelAccessor,BlockPos,Predicate,Direction$Axis,boolean)
- Optional findPortalShape(LevelAccessor,BlockPos,Predicate,Direction$Axis)
- Vec3 lambda$findCollisionFreePosition$3(double,Vec3)
+ Vec3 lambda$findCollisionFreePosition$4(double,Vec3)
+ void <init>(LevelAccessor,BlockPos,Direction$Axis,boolean)
- void <init>(LevelAccessor,BlockPos,Direction$Axis)
- void lambda$createPortalBlocks$2(BlockState,BlockPos)
+ void lambda$createPortalBlocks$3(BlockState,BlockPos)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.ValidationContext
</summary>

```diff
+ boolean hasVisitedCondition(ResourceLocation)
- boolean hasVisitedElement(LootDataId)
+ boolean hasVisitedTable(ResourceLocation)
- LootDataResolver resolver()
+ LootItemCondition resolveCondition(ResourceLocation)
+ LootTable resolveLootTable(ResourceLocation)
+ String lambda$enterCondition$3(String)
- String lambda$enterElement$2(String)
+ String lambda$enterTable$2(String)
+ ValidationContext enterCondition(String,ResourceLocation)
- ValidationContext enterElement(String,LootDataId)
+ ValidationContext enterTable(String,ResourceLocation)
+ void <init>(LootContextParamSet,Function,Function)
- void <init>(LootContextParamSet,LootDataResolver)
+ void <init>(Multimap,Supplier,LootContextParamSet,Function,Set,Function,Set)
- void <init>(Multimap,Supplier,LootContextParamSet,LootDataResolver,Set)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.entries.LootTableReference
</summary>

```diff
+ LootPoolSingletonContainer lambda$lootTableReference$0(ResourceLocation,int,int,LootItemCondition[],LootItemFunction[])
- LootPoolSingletonContainer lambda$lootTableReference$2(ResourceLocation,int,int,LootItemCondition[],LootItemFunction[])
- void lambda$validate$0(ValidationContext,LootDataId,LootTable)
- void lambda$validate$1(ValidationContext)
```

</details>
<details>
<summary>
net.minecraft.world.level.storage.loot.predicates.ConditionReference
</summary>

```diff
+ LootItemCondition lambda$conditionReference$0(ResourceLocation)
- LootItemCondition lambda$conditionReference$2(ResourceLocation)
- void lambda$validate$0(ValidationContext,LootDataId,LootItemCondition)
- void lambda$validate$1(ValidationContext)
```

</details>
<details>
<summary>
net.minecraft.world.phys.AABB
</summary>

```diff
+ AABB scale(float)
```

</details>
</details>
<hr/>