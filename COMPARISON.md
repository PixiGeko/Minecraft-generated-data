## Comparison with [23w13a](https://github.com/PixiGeko/Minecraft-generated-data/tree/23w13a)

- [Version data](#version-data)
- [Registries](#registries)
- [Tags](#tags)
- [Commands](#commands)
- [Recipes](#recipes)
- [Translations](#translations)
- [File structure](#file-structure)
- [Misc](#misc)
- [Mappings](#mappings)
  - [Server](#server)
  - [Client](#client)

<hr/>
<details><summary>Version data</summary>
<table><tr><th></th><th align="left">23w13a</th><th>23w13a_or_b</th></tr><tr><td>World version</td><td><code>3443</code></td><td><code>3444</code></td></tr><tr><td>Protocol version</td><td><code>1073741952</code></td><td><code>1073741953</code></td></tr></table>
</details>
<details><summary>Registries</summary>
<details>
<summary>
List
</summary>

```diff
+ rules.txt
```

</details>

<details>
<summary>
attribute.txt
</summary>

```diff
+ minecraft:generic.scale
```

</details>
<details>
<summary>
banner_pattern.txt
</summary>

```diff
+ minecraft:m
```

</details>
<details>
<summary>
block.txt
</summary>

```diff
+ minecraft:cheese
+ minecraft:copper_sink
+ minecraft:copper_spleaves
+ minecraft:filled_copper_sink
+ minecraft:other_portal
+ minecraft:packed_air
+ minecraft:pickaxe_block
+ minecraft:place_block
```

</details>





<details>
<summary>
custom_stat.txt
</summary>

```diff
+ minecraft:votes
```

</details>


<details>
<summary>
entity_type.txt
</summary>

```diff
+ minecraft:moon_cow
+ minecraft:ray_tracing
+ minecraft:stencil_display
```

</details>







<details>
<summary>
item.txt
</summary>

```diff
+ minecraft:air_block
+ minecraft:bit
+ minecraft:bottle_of_entity
+ minecraft:bottle_of_void
+ minecraft:byte_tag
+ minecraft:cheese
+ minecraft:compound_tag
+ minecraft:copper_sink
+ minecraft:copper_spleaves
+ minecraft:double_tag
+ minecraft:dupe_hack
+ minecraft:float_tag
+ minecraft:int_tag
+ minecraft:la_baguette
+ minecraft:le_tricolore
+ minecraft:left_curly
+ minecraft:left_square
+ minecraft:list_tag
+ minecraft:long_tag
+ minecraft:m_banner_pattern
+ minecraft:moon_cow_spawn_egg
+ minecraft:name
+ minecraft:packed_air
+ minecraft:pickaxe_block
+ minecraft:place_block
+ minecraft:right_curly
+ minecraft:right_square
+ minecraft:short_tag
+ minecraft:splash_bottle_of_entity
+ minecraft:string_tag
+ minecraft:string2
+ minecraft:syntax_error
+ minecraft:tag
```

</details>








<details>
<summary>
mob_effect.txt
</summary>

```diff
+ minecraft:big
+ minecraft:small
```

</details>

<details>
<summary>
particle_type.txt
</summary>

```diff
+ minecraft:footstep
```

</details>



<details>
<summary>
potion.txt
</summary>

```diff
+ minecraft:big
+ minecraft:long_big
+ minecraft:long_small
+ minecraft:small
+ minecraft:strong_big
+ minecraft:strong_small
```

</details>
<details>
<summary>
recipe_serializer.txt
</summary>

```diff
+ minecraft:crafting_special_dupehack
+ minecraft:nbt_crafting_recipe
```

</details>





<details>
<summary>
sound_event.txt
</summary>

```diff
+ minecraft:the_joke
```

</details>



<details>
<summary>
worldgen/biome_source.txt
</summary>

```diff
+ minecraft:the_moon
```

</details>




<details>
<summary>
worldgen/feature.txt
</summary>

```diff
+ minecraft:crater
+ minecraft:lunar_base
```

</details>
</details>
<details><summary>Tags</summary>
<details>
<summary>
List
</summary>

```diff
+ universal_tags/rules.json
```

</details>
<details>
<summary>
all_blocks_without_drop.json
</summary>

```diff
+ minecraft:copper_spleaves
+ minecraft:other_portal
+ minecraft:packed_air
```

</details>
<details>
<summary>
all_blocks_with_drop.json
</summary>

```diff
+ minecraft:cheese
+ minecraft:copper_sink
+ minecraft:filled_copper_sink
+ minecraft:pickaxe_block
+ minecraft:place_block
```

</details>
<details>
<summary>
all_entities_without_drop.json
</summary>

```diff
+ minecraft:ray_tracing
+ minecraft:stencil_display
```

</details>
<details>
<summary>
all_entities_with_drop.json
</summary>

```diff
+ minecraft:moon_cow
```

</details>
<details>
<summary>
all_living_entities_without_drop.json
</summary>

```diff
+ minecraft:ray_tracing
```

</details>
<details>
<summary>
all_survival_blocks_without_drop.json
</summary>

```diff
+ minecraft:copper_spleaves
+ minecraft:other_portal
```

</details>

<details>
<summary>
universal_tags/attribute.json
</summary>

```diff
+ minecraft:generic.scale
```

</details>
<details>
<summary>
universal_tags/banner_pattern.json
</summary>

```diff
+ minecraft:m
```

</details>
<details>
<summary>
universal_tags/block.json
</summary>

```diff
+ minecraft:cheese
+ minecraft:copper_sink
+ minecraft:copper_spleaves
+ minecraft:filled_copper_sink
+ minecraft:other_portal
+ minecraft:packed_air
+ minecraft:pickaxe_block
+ minecraft:place_block
```

</details>





<details>
<summary>
universal_tags/custom_stat.json
</summary>

```diff
+ minecraft:votes
```

</details>


<details>
<summary>
universal_tags/entity_type.json
</summary>

```diff
+ minecraft:moon_cow
+ minecraft:ray_tracing
+ minecraft:stencil_display
```

</details>







<details>
<summary>
universal_tags/item.json
</summary>

```diff
+ minecraft:air_block
+ minecraft:bit
+ minecraft:bottle_of_entity
+ minecraft:bottle_of_void
+ minecraft:byte_tag
+ minecraft:cheese
+ minecraft:compound_tag
+ minecraft:copper_sink
+ minecraft:copper_spleaves
+ minecraft:double_tag
+ minecraft:dupe_hack
+ minecraft:float_tag
+ minecraft:int_tag
+ minecraft:la_baguette
+ minecraft:le_tricolore
+ minecraft:left_curly
+ minecraft:left_square
+ minecraft:list_tag
+ minecraft:long_tag
+ minecraft:m_banner_pattern
+ minecraft:moon_cow_spawn_egg
+ minecraft:name
+ minecraft:packed_air
+ minecraft:pickaxe_block
+ minecraft:place_block
+ minecraft:right_curly
+ minecraft:right_square
+ minecraft:short_tag
+ minecraft:splash_bottle_of_entity
+ minecraft:string_tag
+ minecraft:string2
+ minecraft:syntax_error
+ minecraft:tag
```

</details>








<details>
<summary>
universal_tags/mob_effect.json
</summary>

```diff
+ minecraft:big
+ minecraft:small
```

</details>

<details>
<summary>
universal_tags/particle_type.json
</summary>

```diff
+ minecraft:footstep
```

</details>



<details>
<summary>
universal_tags/potion.json
</summary>

```diff
+ minecraft:big
+ minecraft:long_big
+ minecraft:long_small
+ minecraft:small
+ minecraft:strong_big
+ minecraft:strong_small
```

</details>
<details>
<summary>
universal_tags/recipe_serializer.json
</summary>

```diff
+ minecraft:crafting_special_dupehack
+ minecraft:nbt_crafting_recipe
```

</details>





<details>
<summary>
universal_tags/sound_event.json
</summary>

```diff
+ minecraft:the_joke
```

</details>



<details>
<summary>
universal_tags/worldgen/biome_source.json
</summary>

```diff
+ minecraft:the_moon
```

</details>




<details>
<summary>
universal_tags/worldgen/feature.json
</summary>

```diff
+ minecraft:crater
+ minecraft:lunar_base
```

</details>
</details>
<details><summary>Commands</summary>
<details>
<summary>
List
</summary>

```diff
+ transform.json
+ vote.json
```

</details>
</details>
<details><summary>Recipes</summary>
<details>
<summary>
List
</summary>

```diff
+ air_block.json
+ bit_from_name_stonecutting.json
+ bit_from_tag_stonecutting.json
+ copper_sink.json
+ diamond_drows.json
+ dupe_hack.json
+ left_curly.json
+ left_square.json
+ m_banner_pattern.json
+ name_from_name_tag_stonecutting.json
+ nbt_crafting.json
+ packed_air.json
+ pickaxe_block.json
+ place_block.json
+ right_curly.json
+ right_square.json
+ string_concatenation.json
+ tag_from_name_tag_stonecutting.json
+ wob.json
```

</details>
</details>
<details><summary>Translations</summary>
<details>
<summary>
Keys
</summary>

```diff
+ action.approve: Approve "%s"
+ action.repeal: Repeal "%s"
+ advancements.adventure.vote_1.description: Voted for the first time
+ advancements.adventure.vote_1.title: I Voted!
+ advancements.adventure.vote_256.description: Voted 256 times
+ advancements.adventure.vote_256.title: Pro Voter
+ attribute.name.generic.scale: Entity Scale
+ block.minecraft.banner.m.black: Black New Thing
+ block.minecraft.banner.m.blue: Blue New Thing
+ block.minecraft.banner.m.brown: Brown New Thing
+ block.minecraft.banner.m.cyan: Cyan New Thing
+ block.minecraft.banner.m.gray: Gray New Thing
+ block.minecraft.banner.m.green: Green New Thing
+ block.minecraft.banner.m.light_blue: Light Blue New Thing
+ block.minecraft.banner.m.light_gray: Light Gray New Thing
+ block.minecraft.banner.m.lime: Lime New Thing
+ block.minecraft.banner.m.magenta: Magenta New Thing
+ block.minecraft.banner.m.orange: Orange New Thing
+ block.minecraft.banner.m.pink: Pink New Thing
+ block.minecraft.banner.m.purple: Purple New Thing
+ block.minecraft.banner.m.red: Red New Thing
+ block.minecraft.banner.m.white: White New Thing
+ block.minecraft.banner.m.yellow: Yellow New Thing
+ block.minecraft.bed.no_sleep_v2: You can sleep only at day or during thunderstorms
+ block.minecraft.cheese: Cheese
+ block.minecraft.chest.lab: Lunar Laboratory Equipment
+ block.minecraft.chest.moon: Moon Mission Resupply Crate
+ block.minecraft.copper_sink: Copper Sink
+ block.minecraft.copper_spleaves: Copper Spleaves
+ block.minecraft.dropper.lunar: ACME Self-Building Lunar Base
+ block.minecraft.filled_copper_sink: Filled Copper Sink
+ block.minecraft.other_portal: Other Portal
+ block.minecraft.packed_air: Packed Air
+ block.minecraft.pickaxe_block: Pickaxe Block
+ block.minecraft.place_block: Place Block
+ death.attack.onMoon: %1$s experienced the dark side of the moon
+ death.midas.turned_into_gold: %1$s was turned into gold
+ effect.minecraft.big: Big
+ effect.minecraft.small: Small
+ entity.minecraft.moon_cow: Moon Cow
+ entity.minecraft.ray_tracing: Ray Tracing
+ entity.minecraft.stencil_display: Stencil Display
+ gui.pending_votes.title: Pending Votes
+ gui.voting.do_it: Vote!
+ gui.voting.next: Next Vote
+ gui.voting.prev: Previous Vote
+ gui.voting.title: Voting
+ item.minecraft.air_block: Air
+ item.minecraft.bit: Bit
+ item.minecraft.bottle_of_entity: Bottle of Entity
+ item.minecraft.bottle_of_entity.specific: Bottle of %s
+ item.minecraft.bottle_of_void: Bottle of Void
+ item.minecraft.byte_tag: Byte Tag
+ item.minecraft.compound_tag: Compound Tag
+ item.minecraft.double_tag: Double Tag
+ item.minecraft.dupe_hack: minecraft:dupe_hack
+ item.minecraft.float_tag: Float Tag
+ item.minecraft.glass_bottle_air: Glass Bottle filled with Air
+ item.minecraft.int_tag: Int Tag
+ item.minecraft.la_baguette: La Baguette
+ item.minecraft.le_tricolore: Le Tricolore
+ item.minecraft.left_curly: Left Curly
+ item.minecraft.left_square: Left Square
+ item.minecraft.lingering_potion.effect.big: Lingering Potion of Big
+ item.minecraft.lingering_potion.effect.small: Lingering Potion of Small
+ item.minecraft.list_tag: List Tag
+ item.minecraft.long_tag: Long Tag
+ item.minecraft.m_banner_pattern: Banner Pattern
+ item.minecraft.m_banner_pattern.desc: New Thing
+ item.minecraft.moon_cow_spawn_egg: Moon Cow Spawn Egg
+ item.minecraft.name: Name
+ item.minecraft.potion.effect.big: Potion of Big
+ item.minecraft.potion.effect.small: Potion of Small
+ item.minecraft.right_curly: Right Curly
+ item.minecraft.right_square: Right Square
+ item.minecraft.ruby: Ruby
+ item.minecraft.short_tag: Short Tag
+ item.minecraft.splash_bottle_of_entity: Splash Bottle of Entity
+ item.minecraft.splash_bottle_of_entity.specific: Splash Bottle of %s
+ item.minecraft.splash_potion.effect.big: Splash Potion of Big
+ item.minecraft.splash_potion.effect.small: Splash Potion of Small
+ item.minecraft.string_tag: String Tag
+ item.minecraft.string2: Longer String
+ item.minecraft.syntax_error: Sssyntax Error
+ item.minecraft.tag: Tag
+ item.minecraft.tipped_arrow.effect.big: Arrow of Big
+ item.minecraft.tipped_arrow.effect.small: Arrow of Small
+ key.voting: Voting
+ rule.ai_attack: Replace player %s with advanced AI bot
+ rule.ai_attack.decorate: [BOT] %s
+ rule.air_blocks: Unlock edible Air Blocks, Packed Air to survive on moon and rideable baloon cows to get there
+ rule.always_flying: According to all known laws of aviation, there is no way a mob should be able to walk
+ rule.anonymize_skins: Anonymize player skins
+ rule.attack_knockback: Multiply knockback by %s%%
+ rule.autoJump.also_default_vanilla_to_true: Auto jump on. Also set default value of auto jump in vanilla to true
+ rule.autoJump.of_course: Auto jump? Of course
+ rule.autojump.off: Auto jump off
+ rule.autoJump.on: Auto jump on
+ rule.autoJump.true: Auto jump: true
+ rule.autoJump.yes: Auto jump? Yes
+ rule.bed_pvp: Bed PVP
+ rule.bed_pvp.tooltip: Highly explosive!
+ rule.bedrock_shadows: Minecraft Bedrock Edition style entity shadows
+ rule.beds_on_banners: Beds on Banners
+ rule.beeloons: Enable Beeloons
+ rule.beta_entity_ids: Show id above every entity
+ rule.big_heads: Big Head Mode
+ rule.biome_color.fog: Set fog color in %s to %s
+ rule.biome_color.foliage: Set foliage color in %s to %s
+ rule.biome_color.grass: Set grass color in %s to %s
+ rule.biome_color.sky: Set sky color in %s to %s
+ rule.biome_color.water_fog: Set water fog color in %s to %s
+ rule.biome_color.water: Set water color in %s to %s
+ rule.boat_collisions.break: Boats break on high-speed collisions
+ rule.boat_collisions.explode: Boats explode on high-speed collisions
+ rule.boat_collisions.none: Disable boats breaking on collision
+ rule.bouncy_castle: Super bouncy Slime blocks
+ rule.buff_fishing: Buff fishing
+ rule.buttons_on_things: You can place buttons (and much more stuff), on much more stuff
+ rule.caep.awesom: Give everyone an awesom caep
+ rule.caep.no_circle: NO ROUND SHAPES ALLOWED!
+ rule.caep.nyan: Nya, nya, nya! UwU!
+ rule.caep.squid: Give everyone a squid cape squid
+ rule.caep.veterinarian: Give all the animal lovers a veterinarian cape
+ rule.change_integer_gamerule: Change value of game rule '%s' to %s
+ rule.change_world_shape: Change Overworld shape
+ rule.charged_creepers: All creepers are charged
+ rule.codepoint_replace: Replace '%s' with '%s'
+ rule.colored_light: Add %s colored light
+ rule.connector: %s, but %s
+ rule.copper_sink: Add Copper Sink
+ rule.copy_skin: Everyone Copies %s!
+ rule.damage_modifier: Multiply damage type '%s' by %s
+ rule.day_beds: Bed skip days instead nights
+ rule.day_length.change: Change day length from %s to %s
+ rule.day_length.set: Set day length %s
+ rule.dead_bush_renewability: Dead Bushes are now renewable, but saplings need much more water not to dry out
+ rule.decrease_scale: Decrease player scale by %sx
+ rule.default_sheep_color: Set spawn sheep color to %s
+ rule.dinnerbonize: Dinnerbonize %s
+ rule.disable_item_tooltips: Disable item tooltips
+ rule.disable_shield: Disable shield blocking
+ rule.dream_mode: Life's a Dream
+ rule.drink_air: Bottle of Void: obtained by drinking from empty Bottles. May have side-effects.
+ rule.dupe_hack_break_chance: Set chance of dupe hack breaking to %s%%
+ rule.dupe_hack_occurrence_chance: Set chance of dupe hack occurring to %s%%
+ rule.egg_free.item: Chickens lay %s
+ rule.egg_free.seed_reshuffle: Chicken lay random assigned item (reshuffle)
+ rule.egg_free.seed: Chickens lay randomly assigned item
+ rule.endermen_block_update: Teach Endermen how to place blocks correctly
+ rule.endermen_pick_up_anything: Endermen Pick Up Anything
+ rule.entity_collisions: Entities collide with each other
+ rule.evil_eye: Get evil eyes
+ rule.exploding_phantoms: Phantoms explode on contact
+ rule.explosion_power.change: Change extra explosion power from %s to %s
+ rule.explosion_power.set: Set extra explosion power to %s
+ rule.fast_hoppers: Fast Hoppers, but hopper minecarts are now slow
+ rule.fire_sponge: Sponges can be used to remove lave
+ rule.fish_anything: Polluted Oceans: Fish Anything!
+ rule.fix_piston: Pistons explode when powered
+ rule.fix_qc: Quasi-fix Connectivity
+ rule.flailing.extreme: Limbs all over the place
+ rule.flailing.mild: Mild flailing
+ rule.flailing.none: Stop all that flailing
+ rule.flailing.normal: Normal flailing levels
+ rule.flailing.wild: Wild flailing
+ rule.flailing.windmill: WINDMILL MODE ON!!!
+ rule.flammability.high: Change flammability of %s to high
+ rule.flammability.low: Change flammability of %s to low
+ rule.flammability.medium: Change flammability of %s to medium
+ rule.flammability.very_high: Change flammability of %s to 'literally dry grass'
+ rule.flintsploder: Flint and Steel can explode any block
+ rule.flip_binary_gamerule: Flip game rule '%s'
+ rule.floating_heads: Floating Head Mode
+ rule.fog_off: Remove fog from the game where there was fog before. Anv vice versa.
+ rule.food_restriction.any: A Balanced Diet
+ rule.food_restriction.apple: An Apple Party Diet
+ rule.food_restriction.baked_potato: A Get Baked Diet
+ rule.food_restriction.beef: A Cow Sushi Diet
+ rule.food_restriction.beetroot_soup: A Soup Kitchen Diet
+ rule.food_restriction.beetroot: A Beeter Diet
+ rule.food_restriction.bread: A Toasty Diet
+ rule.food_restriction.cake: A Birthday Diet
+ rule.food_restriction.carrot: A Rabbit Diet
+ rule.food_restriction.chicken: A Salmonella Diet
+ rule.food_restriction.chorus_fruit: A Nomportation Diet
+ rule.food_restriction.cod: A Fishy Diet
+ rule.food_restriction.cooked_beef: A Meat Lovers Diet
+ rule.food_restriction.cooked_chicken: A Nugget Time Diet
+ rule.food_restriction.cooked_cod: A Fish Without Chips Diet
+ rule.food_restriction.cooked_mutton: A Woolsome Diet
+ rule.food_restriction.cooked_porkchop: Bringing Home the Bacon Diet
+ rule.food_restriction.cooked_rabbit: A Bingo Diet
+ rule.food_restriction.cooked_salmon: A River Diet
+ rule.food_restriction.cookie: An Unhealthy Diet
+ rule.food_restriction.dried_kelp: A Weedy Food Diet
+ rule.food_restriction.edible: Food
+ rule.food_restriction.enchanted_golden_apple: Michellin Level Expensive Diet
+ rule.food_restriction.glow_berries: An X-Ray Diet
+ rule.food_restriction.golden_apple: A Healthy Diet
+ rule.food_restriction.golden_carrot: Expensive Rabbit Food Diet
+ rule.food_restriction.honey_bottle: A Sugar Drink Diet
+ rule.food_restriction.inedible.apple: Oak Tree Nut
+ rule.food_restriction.inedible.baked_potato: Baked Bump from the Dirt
+ rule.food_restriction.inedible.beef: Cut Cow
+ rule.food_restriction.inedible.beetroot_soup: Blood in a Bowl?
+ rule.food_restriction.inedible.beetroot: Red Dirtbump
+ rule.food_restriction.inedible.bread: Dried Porridge
+ rule.food_restriction.inedible.cake: Lies
+ rule.food_restriction.inedible.carrot: Rabbit Feed
+ rule.food_restriction.inedible.chicken: Birdbits
+ rule.food_restriction.inedible.chorus_fruit: Purple Alien Orb
+ rule.food_restriction.inedible.cod: Slimy Water Thing
+ rule.food_restriction.inedible.cooked_beef: Cremated Cow
+ rule.food_restriction.inedible.cooked_chicken: Burnt Bird
+ rule.food_restriction.inedible.cooked_cod: Ruined Sushi
+ rule.food_restriction.inedible.cooked_mutton: Disgusting Burnt Sheep Piece
+ rule.food_restriction.inedible.cooked_porkchop: Charred Pig Part
+ rule.food_restriction.inedible.cooked_rabbit: It Liked Jumping Around You Murderer
+ rule.food_restriction.inedible.cooked_salmon: Slimy Fish Goop
+ rule.food_restriction.inedible.cookie: Yucky Yellow Thing
+ rule.food_restriction.inedible.dried_kelp: Dried But Somehow Also Slimy
+ rule.food_restriction.inedible.enchanted_golden_apple: Inedible Shining Blob
+ rule.food_restriction.inedible.glow_berries: Light Bulbs
+ rule.food_restriction.inedible.golden_apple: Inedible Yellow Blob
+ rule.food_restriction.inedible.golden_carrot: Rabbit Food
+ rule.food_restriction.inedible.honey_bottle: Too Much Sugar
+ rule.food_restriction.inedible.melon_slice: Mostly Seeds
+ rule.food_restriction.inedible.mushroom_stew: Fungal Goop
+ rule.food_restriction.inedible.mutton: Sheet of Sheep
+ rule.food_restriction.inedible.poisonous_potato: Useless Knob
+ rule.food_restriction.inedible.porkchop: Piece of Pig
+ rule.food_restriction.inedible.potato: Root Thing?
+ rule.food_restriction.inedible.pufferfish: The Terror of the Deep
+ rule.food_restriction.inedible.pumpkin_pie: It's Not a Pie You Didn't Even Bake It
+ rule.food_restriction.inedible.rabbit_stew: Who Stewed Roger Rabbit?
+ rule.food_restriction.inedible.rabbit: Bunneh :(
+ rule.food_restriction.inedible.rotten_flesh: Unhealthy Thing
+ rule.food_restriction.inedible.salmon: Red Slimy Water Thing
+ rule.food_restriction.inedible.spider_eye: Arcachneous Orb
+ rule.food_restriction.inedible.suspicious_stew: Sus
+ rule.food_restriction.inedible.sweet_berries: Stick Blobs
+ rule.food_restriction.inedible.tropical_fish: Nemo
+ rule.food_restriction.maybe_edible: Food (May Have Side Effects)
+ rule.food_restriction.melon_slice: sliceddiet
+ rule.food_restriction.mushroom_stew: Shrooms! Only Shrooms!
+ rule.food_restriction.mutton: A Raw And Wooly Diet
+ rule.food_restriction.poisonous_potato: A Dubious Spud Diet
+ rule.food_restriction.porkchop: A Pork Belly Diet
+ rule.food_restriction.potato: Unboiled, Unmashed, Unstewed Diet
+ rule.food_restriction.pufferfish: A Killer Diet
+ rule.food_restriction.pumpkin_pie: Mmmm, Pie. Pie! Only Pie!
+ rule.food_restriction.rabbit_stew: An Auto-Jump Diet
+ rule.food_restriction.rabbit: Raw Jumpers Only
+ rule.food_restriction.rotten_flesh: A Rotten Diet
+ rule.food_restriction.salmon: A Sushi Diet
+ rule.food_restriction.spider_eye: A Witching Diet
+ rule.food_restriction.suspicious_stew: A Sus Diet
+ rule.food_restriction.sweet_berries: A Sweet, Sweet Diet
+ rule.food_restriction.tropical_fish: Only Eating Nemo
+ rule.footprint: Advance Project Footprint status from '%s' to '%s'
+ rule.footprint.0: Footprints? What footprints?
+ rule.footprint.1: Start process for restoring footprint particles
+ rule.footprint.10: Go-no go meeting
+ rule.footprint.11: Enable footprints
+ rule.footprint.2: Re-evaluate footprint principles
+ rule.footprint.3: Pre-estimate footprint timeline
+ rule.footprint.4: Research existing footprint solutions in competing products
+ rule.footprint.5: Acquire buy-in from parties relevant to footprint initiative
+ rule.footprint.6: Research results from footprint focus groups
+ rule.footprint.7: Iterate on footprint look and feel
+ rule.footprint.8: Ask on wider forum about gameplay impact of footprints
+ rule.footprint.9: Q&A footprint pass
+ rule.french_mode: French Mode
+ rule.give_effect: Give every player infinite %s
+ rule.give_items: Give every online player %s of %s
+ rule.global_pitch: Change pitch of every sound by %s%%
+ rule.glow_bees: Glow Bees
+ rule.glowing_glow_squids: Make Glow Squids actually glow
+ rule.god_of_lightning: Aquire more than just the power of thunder
+ rule.grappling_fishing_rods: Grappling Fishing Rods
+ rule.grummize: Grummize %s
+ rule.haunted_world: The World is Haunted
+ rule.increase_scale: Increase player scale by %sx
+ rule.infinite_cakes: Infinite cakes
+ rule.instacheese: Instacheese from Buckets
+ rule.invisible_armor: Make armor invisible
+ rule.item_despawn_time.change: Change item despawn timer from %s to %s
+ rule.item_despawn_time.set: Set item despawn timer to %s
+ rule.item_despawn.despawn_all: Despawn all items on ground
+ rule.item_despawn.despawn_none: Never despawn items on ground
+ rule.item_despawn.keep_player_drops: Don't despawn items dropped by player
+ rule.item_use_speed: Multiply tool speed by %s%%
+ rule.item.disabled: Disabled item: you haven't voted for this!
+ rule.keep_friends_close: Keep your friends close
+ rule.lava_blue_ice_replace: Spawn %s instead of %s when lava interacts with blue ice
+ rule.lava_spread_tick_delay: Lava spread tick delay set to: %s
+ rule.lava_water_replace: Spawn %s instead of %s when lava interacts with water
+ rule.less_gravity: Flip gravity rules. Earth feels like moon now
+ rule.less_interaction_updates: Less block updates from player interactions. Actually none at all...
+ rule.loot_double_or_half: Multiply loot drops of %s by %s
+ rule.mbe: Minecraft Bedrock Edition (aka Movable Block Entities)
+ rule.midas_touch: Claim the power of the mighty Midas
+ rule.milk_every_mob: Every mob can be milked
+ rule.minecart_collisions.break: Minecarts break on high-speed collisions
+ rule.minecart_collisions.explode: Minecarts explode on high-speed collisions
+ rule.minecart_collisions.none: Disable minecarts breaking on collision
+ rule.minecart_lies: Expose Minecart LIES!
+ rule.mini_players: Mini Player Mode
+ rule.moon.0: Just the normal Moon
+ rule.moon.1: Big Romantic Moon. Be careful what you wish for, our scientists have warned us about unintended consequences.
+ rule.moon.2: Buff the Moon to be even bigger and stronger!
+ rule.moon.3: MOON TO THE MAX!
+ rule.morrowind_power_player_movement: Move like a Morrowind powergamer
+ rule.name_visibility.none: Never show entity names
+ rule.name_visibility.normal: Hide entity names behind blocks
+ rule.name_visibility.see_through: Always show entity names from behind blocks
+ rule.natural_spawn_disable: Never naturally spawn %s
+ rule.natural_spawn_replace: Replace natural spawns of %s with %s
+ rule.nbt_crafting: Enable NBT crafting
+ rule.new_vote_approve_option_count: Set maximum number of options per new approval vote to %s
+ rule.new_vote_chance_per_tick: Set chance to start new vote on every tick to 1/%s
+ rule.new_vote_cost: Set voting cost and/or limits to: %s
+ rule.new_vote_disable_opt_out: Don't opt-out option to new votes with multiple choices
+ rule.new_vote_duration_minutes: Set duration of new votes to %s minutes
+ rule.new_vote_extra_effect_chance: Set probability of creating combined votes to %s%%
+ rule.new_vote_extra_effect_max_count: Set maximum number of extra effects for new combined votes to %s
+ rule.new_vote_max_approve_vote_count: Set maximum number of approval votes to %s
+ rule.new_vote_max_repeal_vote_count: Set maximum number of repeal votes to %s
+ rule.new_vote_repeal_option_count: Set maximum number of options per new repeal vote to %s
+ rule.new_vote_repeal_vote_chance: Set chance of a new vote being a repeal vote to %s%%
+ rule.normal_name_visibility: Set normal entity name display to: %s
+ rule.nothing: Do Nothing
+ rule.obfuscate_player_names: Obfuscate player names
+ rule.only_mending_trades: Villagers only trade Mending
+ rule.optimize_light_engine.always_light: Turn on light everywhere to improve light engine  performance
+ rule.optimize_light_engine.loadshedding: Implement loadshedding to improve light engine performance
+ rule.optimize_light_engine.never_light: Turn off light everywhere to improve light engine performance
+ rule.optimize_light_engine.none: De-optimize light engine
+ rule.optimize.change: Change optimization level from %s to %s
+ rule.optimize.set: Set optimization level to %s
+ rule.other_portal: Enable Other Portal
+ rule.other_portal.oops: Error 404 Terrain Not Found
+ rule.parent_trap: Parent Trap
+ rule.payment.item: Villagers accept %s instead of gems
+ rule.payment.seed_reshuffle: Villagers accept randomly assigned item instead of gems (reshuffle)
+ rule.payment.seed: Villagers accept randomly assigned item instead of gems
+ rule.persistent_parrots: Persistent Parrots. They will NEVER leave you.
+ rule.phantom_phantom: Phantom Phantoms
+ rule.pickaxe_block: Add Pickaxe Block
+ rule.place_block: Add Place Block
+ rule.player_head_drop: Players can drop head when exploded by charged creeper
+ rule.pot_gems: Decorated pots drop gems when broken
+ rule.potions_of_big: Brew Potion of Big with Bottle O' Enchanting
+ rule.potions_of_small: Brew Potion of Small with Rabbit Hide
+ rule.president: %s for president
+ rule.president.tag: President %s
+ rule.prevent_floating_trees: Prevent floating trees
+ rule.proposal: Proposal #%s
+ rule.push_limit: Piston Push Limit: %s
+ rule.quorum_percent: Set number of players needed for a vote to pass to %s%% of online players
+ rule.random_tnt_fuse: TNT fuse timer is random
+ rule.ray_tracing: Add Ray Tracing. Note: Ray Tracing requires additional processing resources.
+ rule.recipe_double_or_half: Multiply recipe output of %s by %s
+ rule.recipe_flip.both: Shaped recipes accept all orientations
+ rule.recipe_flip.flipped_only: Shaped recipes accept only mirrored recipes
+ rule.recipe_flip.normal_only: Shaped recipes accept only exact recipes
+ rule.recipe.minecraft.diamond_drows: Enable diamond drows
+ rule.recipe.minecraft.m_banner_pattern: Enable suspicious banner pattern
+ rule.recipe.minecraft.string_concatenation: Enable string concatenation
+ rule.recipe.minecraft.wob: Enable wob recipe
+ rule.remove_phantoms: Remove Phantoms
+ rule.replace_block_model: Replace block model for %s with %s
+ rule.replace_item_model: Replace item model for %s with %s
+ rule.replace_items: Replace all %s with %s in player inventories
+ rule.replace_loot_drop: Replace loot drop %s with %s
+ rule.replace_recipe_output: Replace recipe output %s with %s
+ rule.replace_sound: Replace sound %s with %s
+ rule.reset_entity_transform: Clear every player's entity transform
+ rule.reset_scale: Reset every player's scale
+ rule.reset_skin: Reset all player skins
+ rule.rideable_entities: Make all %s entities rideable
+ rule.rowing_up_that_hill: Acknowledge boats as the superior way of transportation
+ rule.rubies: Replace emerald item with ruby (and only that - we are too lazy to do it properly)
+ rule.silent_vote: Don't display voting output
+ rule.sneaking_name_visibility: Set sneaking entity name display to: %s
+ rule.snitch: Announce player votes in chat
+ rule.snitch.msg: %s voted for %s. %s
+ rule.spawn_egg_chance: Set chance of entity dropping spawn egg to %s%%
+ rule.stack_size_double_or_half: Multiply maximum stack size of %s by %s
+ rule.sticky: Realistic piston block sticking rules. It now makes sense now!
+ rule.swap_skies: Swap overworld and The End sky
+ rule.text_style.aqua: Change '%s' to always render as aqua
+ rule.text_style.black: Change '%s' to always render as black
+ rule.text_style.blank: Blank '%s'
+ rule.text_style.blue: Change '%s' to always render as blue
+ rule.text_style.bold: Change '%s' to be thick
+ rule.text_style.dark_aqua: Change '%s' to always render as dark aqua
+ rule.text_style.dark_blue: Change '%s' to always render as dark blue
+ rule.text_style.dark_gray: Change '%s' to always render as dark gray
+ rule.text_style.dark_green: Change '%s' to always render as dark green
+ rule.text_style.dark_purple: Change '%s' to always render as dark purple
+ rule.text_style.dark_red: Change '%s' to always render as dark red
+ rule.text_style.gold: Change '%s' to always render as gold
+ rule.text_style.gray: Change '%s' to always render as gray
+ rule.text_style.green: Change '%s' to always render as green
+ rule.text_style.hide: Change '%s' to never render
+ rule.text_style.illager: Send '%s' to dungeons
+ rule.text_style.italic: Skew '%s'
+ rule.text_style.light_purple: Change '%s' to always render as light purple
+ rule.text_style.obfuscated: Change '%s' to a mess of pixels
+ rule.text_style.red: Change '%s' to always render as red
+ rule.text_style.sga: Change '%s' to be magic
+ rule.text_style.strikethrough: Strike '%s' through
+ rule.text_style.thin: Change '%s' to be thin
+ rule.text_style.underline: Strike '%s' under
+ rule.text_style.white: Change '%s' to always render as white
+ rule.text_style.yellow: Change '%s' to always render as yellow
+ rule.the_joke: Keep ignoring Mobbo
+ rule.tie_strategy.fail: On tie fail vote
+ rule.tie_strategy.pick_all: On tie pick all options
+ rule.tie_strategy.pick_high: On tie pick option with higher number
+ rule.tie_strategy.pick_low: On tie pick option with lower number
+ rule.tie_strategy.pick_none: On tie remove tied option
+ rule.tie_strategy.pick_random: On tie pick random option
+ rule.tnt_tennis: Primed TNT can be knocked back
+ rule.trails_and_tails: Get the Trails & Tails Update
+ rule.transform_entity: Transform every player into a %s
+ rule.transparent_players: Ghost Mode
+ rule.ultra_realistic_mode: Ultra Realistic Mode
+ rule.uncontrolable_lave: Uncontrollable lava
+ rule.undead_players: Players are Undead
+ rule.universal_jeb: The universal jeb_ experience™
+ rule.unstable_tnt: All newly placed TNT blocks are unstable
+ rule.vote_max_results: Pass up to %s rules per vote
+ rule.vote_result_pass_without_voters: Pass vote even if it has no players voting for it
+ rule.vote_result_pass_without_votes: Also apply options that have received no votes
+ rule.vote_result_pick_random_if_vote_fails: Pass random options if vote fails
+ rule.vote_result_reverse_counts: Pass lowest-voted option instead of highest-voted ones
+ rule.vote_result_show_options: Don't show final vote counts
+ rule.vote_result_show_voters: Reveal voters at the end of vote
+ rule.votes_to_win_percent: Require passing votes to receive at least %s%% of all cast votes
+ rule.voting_fireworks: Celebrate voting!
+ rule.weather.rain.always: Always rain
+ rule.weather.rain.default: Default rain rules
+ rule.weather.rain.never: Never rain
+ rule.weather.thunder.always: Always thunder
+ rule.weather.thunder.default: Default thunder rules
+ rule.weather.thunder.never: Never thunder
+ rule.wheels_on_minecarts: Wheels-4-Minecarts!
+ rule.world_of_giants: A World of Giants
+ rule.zombie_apocalypse: It's the zombie apocalypse! Watch out for mushrooms. And zombies.
+ selectWorld.edit.resetVotes: Reset All Vote Data :(
+ selectWorld.edit.resetVotes.msg: Proceeding will remove all voting data, including all pending and/or approved proposals.
Use only when you can't live with consequences of your own actions and/or your world is otherwise unrecoverable.
+ stat.minecraft.votes: Votes Cast
+ tooltip.more_like_cooltip: The Long Tooltip Screen
+ tooltip.too_long: Tooltip too long, press ctrl-click to show all
+ vote.cost_diplay: %s × %s
+ vote.cost: Cost:
+ vote.cost.health: Health
+ vote.cost.xp: Enchantment Points
+ vote.count_per_option.description: votes per option
+ vote.count_per_option.limit: %s/%s votes for this option
+ vote.count_per_option.no_limit: %s votes for this option
+ vote.count_per_proposal.description: votes per proposal
+ vote.count_per_proposal.limit: %s/%s votes for this proposal
+ vote.count_per_proposal.no_limit: %s votes for this proposal
+ vote.current_rules: All approved rules (so far)
+ vote.failed: Failed to vote: %s
+ vote.finished: Voting finished for %s
+ vote.no_change: No change
+ vote.no_more_votes: No more votes
+ vote.no_option: No option passed
+ vote.no_option.random: No option passed, picking random option(s)
+ vote.no_resources: Missing resources
+ vote.option_count: Option #%s '%s' received %s vote(s) from %s player(s)
+ vote.option_display: %s. %s
+ vote.option_no_count: Option #%s '%s' voter(s):
+ vote.option_vote_title: %s: option %s/%s
+ vote.option_won: Option #%s '%s' won
+ vote.option_won.no_effect: Option #%s '%s' won, but has no effects
+ vote.quorum.not_reached: Quorum (%s) not reached
+ vote.quorum.passed: Quorum passed: %s out of %s
+ vote.show_current_rules: Show applied proposals
+ vote.started: Started voting for %s (%s)
+ vote.tie: Voting tie, using strategy '%s'
+ vote.total_count: Received %s vote(s) from %s voter(s)
+ vote.vote_count.minimum: Passing option needs at least %s votes
+ vote.voted: ⯪ I Voted! ⯫
+ vote.voter:     %s: %s
+ vote.voters: Voters:
```

</details>
</details>
<details><summary>File structure</summary>
<details>
<summary>
data
</summary>

```diff
+ minecraft/advancements/adventure/vote_1.json
+ minecraft/advancements/adventure/vote_256.json
+ minecraft/advancements/recipes/brewing/copper_sink.json
+ minecraft/advancements/recipes/building_blocks/air_block.json
+ minecraft/advancements/recipes/building_blocks/packed_air.json
+ minecraft/advancements/recipes/combat/diamond_drows.json
+ minecraft/advancements/recipes/combat/wob.json
+ minecraft/advancements/recipes/misc/m_banner_pattern.json
+ minecraft/advancements/recipes/misc/string_concatenation.json
+ minecraft/advancements/recipes/redstone/bit_from_name_stonecutting.json
+ minecraft/advancements/recipes/redstone/bit_from_tag_stonecutting.json
+ minecraft/advancements/recipes/redstone/left_curly.json
+ minecraft/advancements/recipes/redstone/left_square.json
+ minecraft/advancements/recipes/redstone/name_from_name_tag_stonecutting.json
+ minecraft/advancements/recipes/redstone/pickaxe_block.json
+ minecraft/advancements/recipes/redstone/place_block.json
+ minecraft/advancements/recipes/redstone/right_curly.json
+ minecraft/advancements/recipes/redstone/right_square.json
+ minecraft/advancements/recipes/redstone/tag_from_name_tag_stonecutting.json
+ minecraft/damage_type/midas_curse.json
+ minecraft/damage_type/on_moon.json
+ minecraft/dimension_type/the_moon.json
+ minecraft/loot_tables/blocks/cheese.json
+ minecraft/loot_tables/blocks/copper_sink.json
+ minecraft/loot_tables/blocks/copper_spleaves.json
+ minecraft/loot_tables/blocks/filled_copper_sink.json
+ minecraft/loot_tables/blocks/other_portal.json
+ minecraft/loot_tables/blocks/pickaxe_block.json
+ minecraft/loot_tables/blocks/place_block.json
+ minecraft/loot_tables/chests/moon_lab.json
+ minecraft/loot_tables/chests/moon_resuply.json
+ minecraft/loot_tables/entities/moon_cow.json
+ minecraft/loot_tables/entities/ray_tracing.json
+ minecraft/loot_tables/gameplay/dream_piglin_bartering.json
+ minecraft/recipes/air_block.json
+ minecraft/recipes/bit_from_name_stonecutting.json
+ minecraft/recipes/bit_from_tag_stonecutting.json
+ minecraft/recipes/copper_sink.json
+ minecraft/recipes/diamond_drows.json
+ minecraft/recipes/dupe_hack.json
+ minecraft/recipes/left_curly.json
+ minecraft/recipes/left_square.json
+ minecraft/recipes/m_banner_pattern.json
+ minecraft/recipes/name_from_name_tag_stonecutting.json
+ minecraft/recipes/nbt_crafting.json
+ minecraft/recipes/packed_air.json
+ minecraft/recipes/pickaxe_block.json
+ minecraft/recipes/place_block.json
+ minecraft/recipes/right_curly.json
+ minecraft/recipes/right_square.json
+ minecraft/recipes/string_concatenation.json
+ minecraft/recipes/tag_from_name_tag_stonecutting.json
+ minecraft/recipes/wob.json
+ minecraft/tags/banner_pattern/pattern_item/m.json
+ minecraft/tags/blocks/cordycep_block.json
+ minecraft/tags/items/copper.json
+ minecraft/tags/items/heavy.json
+ minecraft/worldgen/biome/the_moon.json
+ minecraft/worldgen/configured_feature/large_crater.json
+ minecraft/worldgen/configured_feature/lunar_base.json
+ minecraft/worldgen/configured_feature/mega_crater.json
+ minecraft/worldgen/configured_feature/small_crater.json
+ minecraft/worldgen/noise_settings/moon.json
+ minecraft/worldgen/placed_feature/crater_large.json
+ minecraft/worldgen/placed_feature/crater_mega.json
+ minecraft/worldgen/placed_feature/crater_small.json
+ minecraft/worldgen/placed_feature/lunar_base.json
```

</details>
<details>
<summary>
assets
</summary>

```diff
+ minecraft/blockstates/cheese.json
+ minecraft/blockstates/copper_sink.json
+ minecraft/blockstates/copper_spleaves.json
+ minecraft/blockstates/filled_copper_sink.json
+ minecraft/blockstates/other_portal.json
+ minecraft/blockstates/packed_air.json
+ minecraft/blockstates/pickaxe_block.json
+ minecraft/blockstates/place_block.json
+ minecraft/models/block/cheese_1.json
+ minecraft/models/block/cheese_10.json
+ minecraft/models/block/cheese_100.json
+ minecraft/models/block/cheese_1000.json
+ minecraft/models/block/cheese_10000.json
+ minecraft/models/block/cheese_100000.json
+ minecraft/models/block/cheese_1000000.json
+ minecraft/models/block/cheese_10000000.json
+ minecraft/models/block/cheese_10000001.json
+ minecraft/models/block/cheese_1000001.json
+ minecraft/models/block/cheese_10000010.json
+ minecraft/models/block/cheese_10000011.json
+ minecraft/models/block/cheese_100001.json
+ minecraft/models/block/cheese_1000010.json
+ minecraft/models/block/cheese_10000100.json
+ minecraft/models/block/cheese_10000101.json
+ minecraft/models/block/cheese_1000011.json
+ minecraft/models/block/cheese_10000110.json
+ minecraft/models/block/cheese_10000111.json
+ minecraft/models/block/cheese_10001.json
+ minecraft/models/block/cheese_100010.json
+ minecraft/models/block/cheese_1000100.json
+ minecraft/models/block/cheese_10001000.json
+ minecraft/models/block/cheese_10001001.json
+ minecraft/models/block/cheese_1000101.json
+ minecraft/models/block/cheese_10001010.json
+ minecraft/models/block/cheese_10001011.json
+ minecraft/models/block/cheese_100011.json
+ minecraft/models/block/cheese_1000110.json
+ minecraft/models/block/cheese_10001100.json
+ minecraft/models/block/cheese_10001101.json
+ minecraft/models/block/cheese_1000111.json
+ minecraft/models/block/cheese_10001110.json
+ minecraft/models/block/cheese_10001111.json
+ minecraft/models/block/cheese_1001.json
+ minecraft/models/block/cheese_10010.json
+ minecraft/models/block/cheese_100100.json
+ minecraft/models/block/cheese_1001000.json
+ minecraft/models/block/cheese_10010000.json
+ minecraft/models/block/cheese_10010001.json
+ minecraft/models/block/cheese_1001001.json
+ minecraft/models/block/cheese_10010010.json
+ minecraft/models/block/cheese_10010011.json
+ minecraft/models/block/cheese_100101.json
+ minecraft/models/block/cheese_1001010.json
+ minecraft/models/block/cheese_10010100.json
+ minecraft/models/block/cheese_10010101.json
+ minecraft/models/block/cheese_1001011.json
+ minecraft/models/block/cheese_10010110.json
+ minecraft/models/block/cheese_10010111.json
+ minecraft/models/block/cheese_10011.json
+ minecraft/models/block/cheese_100110.json
+ minecraft/models/block/cheese_1001100.json
+ minecraft/models/block/cheese_10011000.json
+ minecraft/models/block/cheese_10011001.json
+ minecraft/models/block/cheese_1001101.json
+ minecraft/models/block/cheese_10011010.json
+ minecraft/models/block/cheese_10011011.json
+ minecraft/models/block/cheese_100111.json
+ minecraft/models/block/cheese_1001110.json
+ minecraft/models/block/cheese_10011100.json
+ minecraft/models/block/cheese_10011101.json
+ minecraft/models/block/cheese_1001111.json
+ minecraft/models/block/cheese_10011110.json
+ minecraft/models/block/cheese_10011111.json
+ minecraft/models/block/cheese_101.json
+ minecraft/models/block/cheese_1010.json
+ minecraft/models/block/cheese_10100.json
+ minecraft/models/block/cheese_101000.json
+ minecraft/models/block/cheese_1010000.json
+ minecraft/models/block/cheese_10100000.json
+ minecraft/models/block/cheese_10100001.json
+ minecraft/models/block/cheese_1010001.json
+ minecraft/models/block/cheese_10100010.json
+ minecraft/models/block/cheese_10100011.json
+ minecraft/models/block/cheese_101001.json
+ minecraft/models/block/cheese_1010010.json
+ minecraft/models/block/cheese_10100100.json
+ minecraft/models/block/cheese_10100101.json
+ minecraft/models/block/cheese_1010011.json
+ minecraft/models/block/cheese_10100110.json
+ minecraft/models/block/cheese_10100111.json
+ minecraft/models/block/cheese_10101.json
+ minecraft/models/block/cheese_101010.json
+ minecraft/models/block/cheese_1010100.json
+ minecraft/models/block/cheese_10101000.json
+ minecraft/models/block/cheese_10101001.json
+ minecraft/models/block/cheese_1010101.json
+ minecraft/models/block/cheese_10101010.json
+ minecraft/models/block/cheese_10101011.json
+ minecraft/models/block/cheese_101011.json
+ minecraft/models/block/cheese_1010110.json
+ minecraft/models/block/cheese_10101100.json
+ minecraft/models/block/cheese_10101101.json
+ minecraft/models/block/cheese_1010111.json
+ minecraft/models/block/cheese_10101110.json
+ minecraft/models/block/cheese_10101111.json
+ minecraft/models/block/cheese_1011.json
+ minecraft/models/block/cheese_10110.json
+ minecraft/models/block/cheese_101100.json
+ minecraft/models/block/cheese_1011000.json
+ minecraft/models/block/cheese_10110000.json
+ minecraft/models/block/cheese_10110001.json
+ minecraft/models/block/cheese_1011001.json
+ minecraft/models/block/cheese_10110010.json
+ minecraft/models/block/cheese_10110011.json
+ minecraft/models/block/cheese_101101.json
+ minecraft/models/block/cheese_1011010.json
+ minecraft/models/block/cheese_10110100.json
+ minecraft/models/block/cheese_10110101.json
+ minecraft/models/block/cheese_1011011.json
+ minecraft/models/block/cheese_10110110.json
+ minecraft/models/block/cheese_10110111.json
+ minecraft/models/block/cheese_10111.json
+ minecraft/models/block/cheese_101110.json
+ minecraft/models/block/cheese_1011100.json
+ minecraft/models/block/cheese_10111000.json
+ minecraft/models/block/cheese_10111001.json
+ minecraft/models/block/cheese_1011101.json
+ minecraft/models/block/cheese_10111010.json
+ minecraft/models/block/cheese_10111011.json
+ minecraft/models/block/cheese_101111.json
+ minecraft/models/block/cheese_1011110.json
+ minecraft/models/block/cheese_10111100.json
+ minecraft/models/block/cheese_10111101.json
+ minecraft/models/block/cheese_1011111.json
+ minecraft/models/block/cheese_10111110.json
+ minecraft/models/block/cheese_10111111.json
+ minecraft/models/block/cheese_11.json
+ minecraft/models/block/cheese_110.json
+ minecraft/models/block/cheese_1100.json
+ minecraft/models/block/cheese_11000.json
+ minecraft/models/block/cheese_110000.json
+ minecraft/models/block/cheese_1100000.json
+ minecraft/models/block/cheese_11000000.json
+ minecraft/models/block/cheese_11000001.json
+ minecraft/models/block/cheese_1100001.json
+ minecraft/models/block/cheese_11000010.json
+ minecraft/models/block/cheese_11000011.json
+ minecraft/models/block/cheese_110001.json
+ minecraft/models/block/cheese_1100010.json
+ minecraft/models/block/cheese_11000100.json
+ minecraft/models/block/cheese_11000101.json
+ minecraft/models/block/cheese_1100011.json
+ minecraft/models/block/cheese_11000110.json
+ minecraft/models/block/cheese_11000111.json
+ minecraft/models/block/cheese_11001.json
+ minecraft/models/block/cheese_110010.json
+ minecraft/models/block/cheese_1100100.json
+ minecraft/models/block/cheese_11001000.json
+ minecraft/models/block/cheese_11001001.json
+ minecraft/models/block/cheese_1100101.json
+ minecraft/models/block/cheese_11001010.json
+ minecraft/models/block/cheese_11001011.json
+ minecraft/models/block/cheese_110011.json
+ minecraft/models/block/cheese_1100110.json
+ minecraft/models/block/cheese_11001100.json
+ minecraft/models/block/cheese_11001101.json
+ minecraft/models/block/cheese_1100111.json
+ minecraft/models/block/cheese_11001110.json
+ minecraft/models/block/cheese_11001111.json
+ minecraft/models/block/cheese_1101.json
+ minecraft/models/block/cheese_11010.json
+ minecraft/models/block/cheese_110100.json
+ minecraft/models/block/cheese_1101000.json
+ minecraft/models/block/cheese_11010000.json
+ minecraft/models/block/cheese_11010001.json
+ minecraft/models/block/cheese_1101001.json
+ minecraft/models/block/cheese_11010010.json
+ minecraft/models/block/cheese_11010011.json
+ minecraft/models/block/cheese_110101.json
+ minecraft/models/block/cheese_1101010.json
+ minecraft/models/block/cheese_11010100.json
+ minecraft/models/block/cheese_11010101.json
+ minecraft/models/block/cheese_1101011.json
+ minecraft/models/block/cheese_11010110.json
+ minecraft/models/block/cheese_11010111.json
+ minecraft/models/block/cheese_11011.json
+ minecraft/models/block/cheese_110110.json
+ minecraft/models/block/cheese_1101100.json
+ minecraft/models/block/cheese_11011000.json
+ minecraft/models/block/cheese_11011001.json
+ minecraft/models/block/cheese_1101101.json
+ minecraft/models/block/cheese_11011010.json
+ minecraft/models/block/cheese_11011011.json
+ minecraft/models/block/cheese_110111.json
+ minecraft/models/block/cheese_1101110.json
+ minecraft/models/block/cheese_11011100.json
+ minecraft/models/block/cheese_11011101.json
+ minecraft/models/block/cheese_1101111.json
+ minecraft/models/block/cheese_11011110.json
+ minecraft/models/block/cheese_11011111.json
+ minecraft/models/block/cheese_111.json
+ minecraft/models/block/cheese_1110.json
+ minecraft/models/block/cheese_11100.json
+ minecraft/models/block/cheese_111000.json
+ minecraft/models/block/cheese_1110000.json
+ minecraft/models/block/cheese_11100000.json
+ minecraft/models/block/cheese_11100001.json
+ minecraft/models/block/cheese_1110001.json
+ minecraft/models/block/cheese_11100010.json
+ minecraft/models/block/cheese_11100011.json
+ minecraft/models/block/cheese_111001.json
+ minecraft/models/block/cheese_1110010.json
+ minecraft/models/block/cheese_11100100.json
+ minecraft/models/block/cheese_11100101.json
+ minecraft/models/block/cheese_1110011.json
+ minecraft/models/block/cheese_11100110.json
+ minecraft/models/block/cheese_11100111.json
+ minecraft/models/block/cheese_11101.json
+ minecraft/models/block/cheese_111010.json
+ minecraft/models/block/cheese_1110100.json
+ minecraft/models/block/cheese_11101000.json
+ minecraft/models/block/cheese_11101001.json
+ minecraft/models/block/cheese_1110101.json
+ minecraft/models/block/cheese_11101010.json
+ minecraft/models/block/cheese_11101011.json
+ minecraft/models/block/cheese_111011.json
+ minecraft/models/block/cheese_1110110.json
+ minecraft/models/block/cheese_11101100.json
+ minecraft/models/block/cheese_11101101.json
+ minecraft/models/block/cheese_1110111.json
+ minecraft/models/block/cheese_11101110.json
+ minecraft/models/block/cheese_11101111.json
+ minecraft/models/block/cheese_1111.json
+ minecraft/models/block/cheese_11110.json
+ minecraft/models/block/cheese_111100.json
+ minecraft/models/block/cheese_1111000.json
+ minecraft/models/block/cheese_11110000.json
+ minecraft/models/block/cheese_11110001.json
+ minecraft/models/block/cheese_1111001.json
+ minecraft/models/block/cheese_11110010.json
+ minecraft/models/block/cheese_11110011.json
+ minecraft/models/block/cheese_111101.json
+ minecraft/models/block/cheese_1111010.json
+ minecraft/models/block/cheese_11110100.json
+ minecraft/models/block/cheese_11110101.json
+ minecraft/models/block/cheese_1111011.json
+ minecraft/models/block/cheese_11110110.json
+ minecraft/models/block/cheese_11110111.json
+ minecraft/models/block/cheese_11111.json
+ minecraft/models/block/cheese_111110.json
+ minecraft/models/block/cheese_1111100.json
+ minecraft/models/block/cheese_11111000.json
+ minecraft/models/block/cheese_11111001.json
+ minecraft/models/block/cheese_1111101.json
+ minecraft/models/block/cheese_11111010.json
+ minecraft/models/block/cheese_11111011.json
+ minecraft/models/block/cheese_111111.json
+ minecraft/models/block/cheese_1111110.json
+ minecraft/models/block/cheese_11111100.json
+ minecraft/models/block/cheese_11111101.json
+ minecraft/models/block/cheese_1111111.json
+ minecraft/models/block/cheese_11111110.json
+ minecraft/models/block/cheese_11111111.json
+ minecraft/models/block/copper_sink.json
+ minecraft/models/block/copper_spleaves_broken.json
+ minecraft/models/block/copper_spleaves.json
+ minecraft/models/block/filled_copper_sink.json
+ minecraft/models/block/other_portal_ew.json
+ minecraft/models/block/other_portal_ns.json
+ minecraft/models/block/packed_air.json
+ minecraft/models/block/pickaxe_block.json
+ minecraft/models/block/place_block.json
+ minecraft/models/block/spleaves.json
+ minecraft/models/block/template_copper_sink_full.json
+ minecraft/models/item/air_block.json
+ minecraft/models/item/bit.json
+ minecraft/models/item/bottle_of_entity.json
+ minecraft/models/item/bottle_of_void.json
+ minecraft/models/item/byte_tag.json
+ minecraft/models/item/cheese.json
+ minecraft/models/item/compound_tag.json
+ minecraft/models/item/copper_sink.json
+ minecraft/models/item/copper_spleaves.json
+ minecraft/models/item/double_tag.json
+ minecraft/models/item/dupe_hack.json
+ minecraft/models/item/float_tag.json
+ minecraft/models/item/int_tag.json
+ minecraft/models/item/la_baguette.json
+ minecraft/models/item/le_tricolore.json
+ minecraft/models/item/left_curly.json
+ minecraft/models/item/left_square.json
+ minecraft/models/item/list_tag.json
+ minecraft/models/item/long_tag.json
+ minecraft/models/item/m_banner_pattern.json
+ minecraft/models/item/moon_cow_spawn_egg.json
+ minecraft/models/item/name.json
+ minecraft/models/item/packed_air.json
+ minecraft/models/item/pickaxe_block.json
+ minecraft/models/item/place_block.json
+ minecraft/models/item/right_curly.json
+ minecraft/models/item/right_square.json
+ minecraft/models/item/ruby.json
+ minecraft/models/item/short_tag.json
+ minecraft/models/item/splash_bottle_of_entity.json
+ minecraft/models/item/string_tag.json
+ minecraft/models/item/string2.json
+ minecraft/models/item/syntax_error.json
+ minecraft/models/item/tag.json
+ minecraft/particles/footstep.json
+ minecraft/shaders/core/position_tex_funky.fsh
+ minecraft/shaders/core/position_tex_funky.json
+ minecraft/shaders/post/bloom.json
+ minecraft/shaders/program/brightness_threshold.fsh
+ minecraft/shaders/program/brightness_threshold.json
+ minecraft/shaders/program/merge_bloom.fsh
+ minecraft/shaders/program/merge_bloom.json
+ minecraft/textures/block/cheese.png
+ minecraft/textures/block/copper_sink_bottom.png
+ minecraft/textures/block/copper_sink_inner.png
+ minecraft/textures/block/copper_sink_side.png
+ minecraft/textures/block/copper_sink_top.png
+ minecraft/textures/block/copper_spleaves_broken.png
+ minecraft/textures/block/copper_spleaves.png
+ minecraft/textures/block/other_portal.png
+ minecraft/textures/block/other_portal.png.mcmeta
+ minecraft/textures/block/packed_air_alt.png
+ minecraft/textures/block/packed_air.png
+ minecraft/textures/block/pickaxe_block_back.png
+ minecraft/textures/block/pickaxe_block_front.png
+ minecraft/textures/block/pickaxe_block_side.png
+ minecraft/textures/block/place_block_back.png
+ minecraft/textures/block/place_block_front.png
+ minecraft/textures/block/place_block_side.png
+ minecraft/textures/effect/crown.png
+ minecraft/textures/effect/mustache.png
+ minecraft/textures/entity/banner/m.png
+ minecraft/textures/entity/chest/gold.png
+ minecraft/textures/entity/cow/moon_cow.png
+ minecraft/textures/entity/player/caeps/awesom.png
+ minecraft/textures/entity/player/caeps/blonk.png
+ minecraft/textures/entity/player/caeps/no_circle.png
+ minecraft/textures/entity/player/caeps/nyan.png
+ minecraft/textures/entity/player/caeps/squid.png
+ minecraft/textures/entity/player/caeps/veterinarian.png
+ minecraft/textures/entity/player/tails/alex.png
+ minecraft/textures/entity/player/tails/ari.png
+ minecraft/textures/entity/player/tails/black_fox.png
+ minecraft/textures/entity/player/tails/brown_bear.png
+ minecraft/textures/entity/player/tails/earthern.png
+ minecraft/textures/entity/player/tails/efe.png
+ minecraft/textures/entity/player/tails/fire_fox.png
+ minecraft/textures/entity/player/tails/kai.png
+ minecraft/textures/entity/player/tails/makena.png
+ minecraft/textures/entity/player/tails/noor.png
+ minecraft/textures/entity/player/tails/red_fox.png
+ minecraft/textures/entity/player/tails/snow_fox.png
+ minecraft/textures/entity/player/tails/steve.png
+ minecraft/textures/entity/player/tails/striped.png
+ minecraft/textures/entity/player/tails/sunny.png
+ minecraft/textures/entity/player/tails/zuri.png
+ minecraft/textures/entity/player/wide/ray.png
+ minecraft/textures/entity/shield/m.png
+ minecraft/textures/environment/earth_1.png
+ minecraft/textures/environment/earth_a.png
+ minecraft/textures/environment/earth_prime.png
+ minecraft/textures/environment/earth.png
+ minecraft/textures/font/checkmark.png
+ minecraft/textures/gui/tvpi.png
+ minecraft/textures/gui/votes.png
+ minecraft/textures/gui/voting.png
+ minecraft/textures/item/air_block.png
+ minecraft/textures/item/bit.png
+ minecraft/textures/item/bottle_of_entity.png
+ minecraft/textures/item/bottle_of_void.png
+ minecraft/textures/item/byte_tag.png
+ minecraft/textures/item/compound_tag.png
+ minecraft/textures/item/double_tag.png
+ minecraft/textures/item/end_tag.png
+ minecraft/textures/item/float_tag.png
+ minecraft/textures/item/int_tag.png
+ minecraft/textures/item/la_baguette.png
+ minecraft/textures/item/le_tricolore.png
+ minecraft/textures/item/left_curly.png
+ minecraft/textures/item/left_square.png
+ minecraft/textures/item/list_tag.png
+ minecraft/textures/item/long_tag.png
+ minecraft/textures/item/m_banner_pattern.png
+ minecraft/textures/item/name.png
+ minecraft/textures/item/right_curly.png
+ minecraft/textures/item/right_square.png
+ minecraft/textures/item/ruby.png
+ minecraft/textures/item/short_tag.png
+ minecraft/textures/item/skis.png
+ minecraft/textures/item/splash_bottle_of_entity.png
+ minecraft/textures/item/string_tag.png
+ minecraft/textures/item/string2.png
+ minecraft/textures/item/syntax_error.png
+ minecraft/textures/item/tag.png
+ minecraft/textures/misc/enchanted_glint_gold.png
+ minecraft/textures/mob_effect/big.png
+ minecraft/textures/mob_effect/small.png
+ minecraft/textures/models/armor/beret.png
+ minecraft/textures/particle/footprint.png
+ nothingtoseeheremovealong/lang/fr_fr.json
+ nothingtoseeheremovealong/sounds.json
+ nothingtoseeheremovealong/sounds/the_joke/sad1.ogg
+ nothingtoseeheremovealong/sounds/the_joke/sad2.ogg
+ nothingtoseeheremovealong/sounds/the_joke/sad3.ogg
+ nothingtoseeheremovealong/sounds/the_joke/sad4.ogg
```

</details>
</details>
<details><summary>Misc</summary>
<details>
<summary>
splashes
</summary>

```diff
- ...!
- .party()!
- "Almost never" is an interesting concept!
- "Autological" is!
- [this splash text is now available]
- §1C§2o§3l§4o§5r§6m§7a§8t§9i§ac
- §kFUNKY LOL
- /give @a hugs 64
- #minecraftfarms
- <3 Max & 99 & Ducky!
+ ✅
+ ❎
- 1% sugar!
- 10 years of Mining and Crafting!
- 100% pure!
- 12 herbs and spices!
- 12345 is a bad password!
- 150 bpm for 400000 minutes!
- 150% hyperbole!
- 20 GOTO 10!
- 4815162342 lines of code!
- 90% bug free!
- 90210!
- A riddle, wrapped in a mystery!
- A skeleton popped out!
+ A/B Voting!
- Absolutely fixed relatively broken coordinates
- Absolutely no memes!
- Afraid of the big, black bat!
- Age of Wonders is better!
- Ahhhhhh!
- All inclusive!
- All is full of love!
- All rumors are true!
- Also try Braid!
- Also try Limbo!
- Also try Minecraft Dungeons!
- Also try Mount And Blade!
- Also try Pixeljunk Shooter!
- Also try Project Zomboid!
- Also try Super Meat Boy!
- Also try Terraria!
- Also try VVVVVV!
- Also try World of Goo!
- Amplify and listen to BIPOC voices!
- An illusion! What are you hiding?
- And my pickaxe!
- Any computer is a laptop if you're brave enough!
- As seen on TV!
+ As You Wish!
- Ask your doctor!
- Autonomous!
- Awesome community!
- Awesome game design right there!
- Awesome!
- Aww man!
- Be anti-racist!
- Bees, bees, bees, bees!
- Bekarton guards the gate!
- Best in class!
- Big Pointy Teeth!
- Bigger than a bread box!
- Black lives matter!
- Blue warrior shot the food!
- Board game version also available!
- Boats FTW
- Boots with the fur!
- Bread is pain!
- Bring it on!
- Bring me Ray Cokes!
- Bringing home the bacon!
- BTAF used to be good!
- Buckets of lava!
- Bushy eyebrows!
- Buzzy Bees!
+ By Popular Vote!
- Call your mother!
+ Can't Blame The Developers For Your Choices!
- Casual gaming!
- Ceci n'est pas une title screen!
- Check it out!
- Check out the far lands!
- Child's play!
+ Choice Edition!
+ Choose Wisely!
+ Choose Your Own Adventure!
- Classy!
- Closed source!
- Cloud computing!
- Cogito ergo sum!
- Collaborate and listen!
+ Community Choice!
- Complex cellular automata!
- Consummate V's!
- Contains infinite genders!
- Contains simulated goats!
- Conventional!
- Cough or sneeze into your elbow!
- Cow Tools!
- Create!
- Croak team!
- Cruising streets for gold!
- Cześć Polsko!
- Déjà vu!
- Déjà vu!
+ Democratic!
- Do it all, everything!
- Do not distribute!
- Do you want to join my server?
- Does barrel rolls!
- Doesn't avoid double negatives!
- Doesn't use the U-word!
- Don't bother with the clones!
- Don't feed avocados to parrots!
- Don't feed chocolate to parrots!
- Don't look directly at the bugs!
- Don’t touch your face!
- Don't worry, be happy!
- doot doot
- Double buffered!
- DRR! DRR! DRR!
- Dungeon!
- DungeonQuest is unfair!
- Edit is a name!
- Educate your friends on anti-racism!
- Engage!
- Enhanced!
- Envision! Create! Share!
- Eple (original edit)!
- Euclidian!
- Everybody do the Leif!
- Excitement!
- Exclusive!
- Exploding creepers!
- Extra things!
- Fabulous graphics!
+ Fair Votes Guaranteed!
- Falling off cliffs!
- Falling with style!
- Fan fiction!
- Fantasy!
- Fat free!
- Feature packed!
- Finally complete!
- Finally with ladders!
- Find your claw!
- Finger-licking!
- Flashing letters!
- Flavor with no seasoning!
- Flaxkikare!
- Flower forest TM perfume
- Fnord!
- Follow the train, CJ!
- Freaky!
- Free dental!
+ Freedom of Choice!
- From free range developers!
- From the streets of Södermalm!
- Full of stars!
- Funk soul brother!
+ Game-Changing Votes!
- Gamers unite – separately in your own homes!
- Gargamel plays it!
- Gasp!
- Get to the coppah!
- Ghoughpteighbteau tchoghs!
- Give us Gordon!
- GNU Terry Pratchett
- Go to the dentist!
- Google anlyticsed!
- Got your nose!
- GOTY!
- Guaranteed!
- Haha, LOL!
- Haley loves Elan!
- Hampsterdance!
- Han shot first!
- Hang out with your friends online!
- Hard to label!
- Has an ending!
- Hat Fridays!
- Haunted!
- Heaps of hits on YouTube!
- Helo Cymru!
- Herregud!
- Holy cow, man!
- Home-made!
- Homeomorphic to a 3-sphere!
- Honey, I grew the bees!
- Honey, I waxed the copper!
- Hot tamale, hot hot tamale!
- Hotter than the sun!
- HURNERJSGER?
+ I Demand a Recount!
- I have a suggestion.
- I miss ADOM!
- I need more context.
- I see your vocabulary has improved!
+ I Voted!
- I'm glad you're here!
- idspispopd!
- if not ok then return end
- In case it isn't obvious, foxes aren't players.
- Indev!
- Indie!
- Information wants to be free!
- Ingots!
- Inspirational!
- Internet enabled!
- It came from space.
- It swings, it jives!
- It's a game!
- It's finished!
- It's groundbreaking!
- It's here!
- Jag känner en bot!
- Jason! Jason! Jason!
- Java 16 + 1 = 17!
- Javalicious edition
- Jeb has amazing hair!
- Joel is neat!
- Jump up, jump up, and get down!
- Kaaneeeedaaaa!
- Keyboard compatible!
- Khaaaaaaaaan!
- Kick it root down!
- Kind of dragon free!
- Kinda like Lemmings!
- Kiss the sky!
- l33t!
- Larger than Earth!
- Learn about allyship!
- Legal in Finland!
- Lennart lennart = new Lennart();
- Less addictive than TV Tropes!
- Let our battle's begin!
- Let's danec!
- Leveraging synergy!
- Limited edition!
- Lives in a pineapple under the sea!
- Livestreamed!
- Look mum, I'm in a splash!
- Lots of truthiness!
- Loved by millions!
+ Machine Voting!
- Macroscopic!
- Made by "real" people!
- Made by Jeb!
- Made in Sweden!
- Made with lave!
- Make me a table, a funky table!
+ Make Your Voice Heard!
- MAP11 has two names!
- Matt Damon!
- May contain nuts!
- May contain traces of citrus!
- Meeting expectations!
- Menger sponge!
- Millions of peaches!
- Minecraft Java Edition presents: Disgusting Bugs
- Minecraft!
- Minors welcome!
- Mmmph, mmph!
+ Mob Votes! Biome Votes! Food Votes! Moon Votes!
- Moderately attractive!
- Monster infighting!
- More addictive than lemonade!
- More Digital!
- More polygons!
- More than 500 sold!
+ Multiple Choice Gaming!
- Music by C418!
- Music by Lena Raine!
- My life for Aiur!
- Never dig down!
- Nice to meet you!
- Nooooooooooooo!
- Not as cool as Spock!
- Not linear!
- Not on steam!
- Now contains 32 random daily cats!
- Now in 3D!
- Now on OpenGL 3.2 core profile!
- Now supports åäö!
- Now with additional stuff!
- Now with difficulty!
- Now with extra hugs!
- Now With Multiplayer!
- Now you are thinking with pistons!
- NP is not in P!
- Octagonal!
- Oh man!
- Oh, ok, Pigmen!
- OICU812!
- Omnipotent!
- One day, somewhere in the future, my work will be quoted!
- One of a kind!
+ Online Voting!
- PC gaming since 1873!
+ People's Choice!
- Peter Griffin!
- Ph1lza had a good run!
- Phobos anomaly!
+ Picking and Choosing!
- Ping the human!
- Pixels!
- Place ALL the blocks!
- Plant a tree!
- Plant-based light sources!
- Play him off, keyboard cat!
- Play Minecraft, Watch Topgear, Get Pig!
- Played by cowboys!
- pls rt
- Plz reply to my tweet!
- Pneumatic!
- Polynomial!
- Prepare, but don’t hoard!
- Pretty scary!
- Pretty!
- Pumpa kungen!
- Pumpkinhead!
- Punching wood!
- Put a little fence around it!
- Put that cookie down!
- Rainbow turtle?
- Random splash!
- Read more books!
- Reference implementation!
- Regional resources!
- Replaced molten cheese with blood?
- Representing Edsbyn!
- Reticulating splines!
- RIBBIT!
- Ride the pig!
- Rise from your grave!
- Rita is the new top dog!
- Rule #1: it's never my fault
- Run, coward! I hunger!
- Ryan also has amazing hair!
- Save the world – stay inside!
- Scary!
- Scientific!
- See you next Friday or so!
- Seecret Friday update!
- Sensational!
- Shop for your elders!
- Should not be played while driving
- Shriek like a Sculk Shrieker!
- Singleplayer!
- Slow acting portals!
- So fresh, so clean!
- So sweet, like a nice bon bon!
- Soap and water!
- Something funny!
- Something's not quite right...
- Speak OUT against injustice and UP for equality!
- Spiders everywhere!
- sqrt(-1) love you!
- Stand up for equality in your community!
- Stay a while and listen!
- Stay a while, stay forever!
- Stay home and play games!
- Stay safe!
- Stay strong!
- Stop being reasonable, this is the Internet!
- Stop, hammertime!
- Strange, but not a stranger!
- Sublime!
- Supercalifragilisticexpialidocious!
- Support elderly relatives and friends!
- Support local businesses!
- Support the BIPOC community and creators!
- Survive!
- SWM forever!
- Swords for everyone!
- Synecdoche!
- Take an eggbeater and beat it against a skillet!
- Take frequent breaks!
- Take her pillow!
- Take the elevator to the mezzanine!
- Technically good!
- Technoblade never dies!
- Technologic!
- Teetsuuuuoooo!
- Tell your friends!
- Terrestrial!
- Testificates!
- Thank you for the fish!
- That's no moon!
- That's Numberwang!
- That's super!
- The bee's knees!
+ The Chosen Challenge!
- The creeper is a spy!
- The cutest predator you'll ever meet!
+ The Golden Vote!
- The sky is the limit!
- The sum of its parts!
- The true meaning of covfefe
- Thematic!
- There's <<a cat on ,my keyboard!~
- There's no stopping the Trollmaso
- This is good for Realms.
- This is my true form!
- This message will never appear on the splash screen, isn't that weird?
- This parrot is no more! It has ceased to be!
- This text is hard to read if you play the game at the default resolution, but at 1080p it's fine!
- Thousands of colors!
- Throw a blanket over it!
- Throw yourself at the ground and miss
- Tip your waiter!
+ To the Moon!
- Tougher than diamonds, rich like cream!
- Treatment for your rash!
- Truly gone fishing!
- Try it!
- Try the mushroom stew!
- Try the Nether!
- Turing complete!
- Twittered about!
- Tyrion would love it!
- Ultimate edition!
- umop-apisdn!
- Undefeated!
- Une baguette!
- Uninflammable!
- Uses LWJGL!
- Vanilla!
- Verlet intregration!
- Very fun!
- Very influential in its circle!
- Vote for net neutrality!
+ Vote With Your Gaming!
+ Vote-Driven Development!
+ Vote!
+ Voted Game of the Year!
+ Voting About Voting!
+ Vox Populi, Vox Dei!
- Warning! A huge battleship "STEVE" is approaching fast!
- Wash your hands!
- Water bottle!
- Water proof!
- Welcome to your Doom!
- What do you expect?
- What's the question?
- What's up, Doc?
- Where there is not light, there can spider!
- Who let the frogs out?
- Who put it there?
- Whoa, dude!
- Woah.
- Woo, 2pp!
- Woo, facepunch!
- Woo, reddit!
- Woo, somethingawful!
- Woo, tigsource!
- Woo, worldofminecraft!
- Wow!
- Yaaay!
- Yay, puppies for everyone!
- Yes, sir!
- You are valid!
- You are welcome here!
- You can't explain that!
+ You Decide!
- You're going too fast!
- You've got a brand new key!
+ Your Call!
- Your gender is valid!
- Zoglin!?
- Γεια σου Ελλάδα!
- 한국 안녕하세요!
- 你好中国！
- 日本ハロー！
```

</details>
</details>
<details><summary>Mappings</summary>
<h2>Server</h2>
<details>
<summary>
Classes
</summary>

```diff
- net.minecraft.data.worldgen.biome.NetherBiomes
+ net.minecraft.data.worldgen.biome.OverworldBiomes
- net.minecraft.data.worldgen.biome.package-info
+ net.minecraft.data.worldgen.features.AquaticFeatures
- net.minecraft.data.worldgen.features.CaveFeatures
+ net.minecraft.data.worldgen.features.EndFeatures
- net.minecraft.data.worldgen.features.FeatureUtils
+ net.minecraft.data.worldgen.features.MiscOverworldFeatures
- net.minecraft.data.worldgen.features.NetherFeatures
+ net.minecraft.data.worldgen.features.OreFeatures
+ net.minecraft.data.worldgen.features.package-info
- net.minecraft.data.worldgen.features.PileFeatures
+ net.minecraft.data.worldgen.features.TreeFeatures
- net.minecraft.data.worldgen.features.VegetationFeatures
- net.minecraft.data.worldgen.package-info
+ net.minecraft.data.worldgen.placement.AquaticPlacements
- net.minecraft.data.worldgen.placement.CavePlacements
+ net.minecraft.data.worldgen.placement.EndPlacements
- net.minecraft.data.worldgen.placement.MiscOverworldPlacements
+ net.minecraft.data.worldgen.placement.NetherPlacements
- net.minecraft.data.worldgen.placement.OrePlacements
+ net.minecraft.data.worldgen.placement.package-info
+ net.minecraft.data.worldgen.placement.PlacementUtils
- net.minecraft.data.worldgen.placement.TreePlacements
+ net.minecraft.data.worldgen.placement.VegetationPlacements
- net.minecraft.data.worldgen.placement.VillagePlacements
- net.minecraft.gametest.framework.AfterBatch
+ net.minecraft.gametest.framework.BeforeBatch
- net.minecraft.gametest.framework.ExhaustedAttemptsException
+ net.minecraft.gametest.framework.GameTest
- net.minecraft.gametest.framework.GameTestAssertException
+ net.minecraft.gametest.framework.GameTestAssertPosException
- net.minecraft.gametest.framework.GameTestBatch
+ net.minecraft.gametest.framework.GameTestBatchRunner
- net.minecraft.gametest.framework.GameTestBatchRunner$1
+ net.minecraft.gametest.framework.GameTestEvent
- net.minecraft.gametest.framework.GameTestGenerator
+ net.minecraft.gametest.framework.GameTestHelper
- net.minecraft.gametest.framework.GameTestHelper$1
+ net.minecraft.gametest.framework.GameTestHelper$2
- net.minecraft.gametest.framework.GameTestInfo
+ net.minecraft.gametest.framework.GameTestListener
- net.minecraft.gametest.framework.GameTestRegistry
+ net.minecraft.gametest.framework.GameTestRunner
- net.minecraft.gametest.framework.GameTestSequence
+ net.minecraft.gametest.framework.GameTestSequence$Condition
- net.minecraft.gametest.framework.GameTestServer
+ net.minecraft.gametest.framework.GameTestServer$1
- net.minecraft.gametest.framework.GameTestTicker
+ net.minecraft.gametest.framework.GameTestTimeoutException
- net.minecraft.gametest.framework.GlobalTestReporter
+ net.minecraft.gametest.framework.JUnitLikeTestReporter
- net.minecraft.gametest.framework.LogTestReporter
+ net.minecraft.gametest.framework.MultipleTestTracker
- net.minecraft.gametest.framework.MultipleTestTracker$1
+ net.minecraft.gametest.framework.package-info
+ net.minecraft.gametest.framework.ReportGameListener
- net.minecraft.gametest.framework.StructureUtils
+ net.minecraft.gametest.framework.StructureUtils$1
- net.minecraft.gametest.framework.TeamcityTestReporter
+ net.minecraft.gametest.framework.TestClassNameArgument
- net.minecraft.gametest.framework.TestCommand
+ net.minecraft.gametest.framework.TestCommand$TestSummaryDisplayer
- net.minecraft.gametest.framework.TestFunction
+ net.minecraft.gametest.framework.TestFunctionArgument
- net.minecraft.gametest.framework.TestReporter
- net.minecraft.locale.Language
+ net.minecraft.locale.Language$1
- net.minecraft.locale.package-info
+ net.minecraft.nbt.ByteArrayTag
- net.minecraft.nbt.ByteArrayTag$1
+ net.minecraft.nbt.ByteTag
- net.minecraft.nbt.ByteTag$1
+ net.minecraft.nbt.ByteTag$Cache
- net.minecraft.nbt.CollectionTag
+ net.minecraft.nbt.CompoundTag
- net.minecraft.nbt.CompoundTag$1
+ net.minecraft.nbt.CompoundTag$2
- net.minecraft.nbt.DoubleTag
+ net.minecraft.nbt.DoubleTag$1
- net.minecraft.nbt.EndTag
+ net.minecraft.nbt.EndTag$1
- net.minecraft.nbt.FloatTag
+ net.minecraft.nbt.FloatTag$1
- net.minecraft.nbt.IntArrayTag
+ net.minecraft.nbt.IntArrayTag$1
- net.minecraft.nbt.IntTag
+ net.minecraft.nbt.IntTag$1
- net.minecraft.nbt.IntTag$Cache
+ net.minecraft.nbt.ListTag
- net.minecraft.nbt.ListTag$1
+ net.minecraft.nbt.ListTag$2
- net.minecraft.nbt.LongArrayTag
+ net.minecraft.nbt.LongArrayTag$1
- net.minecraft.nbt.LongTag
+ net.minecraft.nbt.LongTag$1
- net.minecraft.nbt.LongTag$Cache
+ net.minecraft.nbt.NbtAccounter
- net.minecraft.nbt.NbtAccounter$1
+ net.minecraft.nbt.NbtIo
- net.minecraft.nbt.NbtIo$1
+ net.minecraft.nbt.NbtOps
- net.minecraft.nbt.NbtOps$1
+ net.minecraft.nbt.NbtOps$ByteListCollector
- net.minecraft.nbt.NbtOps$HeterogenousListCollector
+ net.minecraft.nbt.NbtOps$HomogenousListCollector
- net.minecraft.nbt.NbtOps$InitialListCollector
+ net.minecraft.nbt.NbtOps$IntListCollector
- net.minecraft.nbt.NbtOps$ListCollector
+ net.minecraft.nbt.NbtOps$LongListCollector
- net.minecraft.nbt.NbtOps$NbtRecordBuilder
+ net.minecraft.nbt.NbtUtils
- net.minecraft.nbt.NumericTag
+ net.minecraft.nbt.package-info
+ net.minecraft.nbt.ShortTag
- net.minecraft.nbt.ShortTag$1
+ net.minecraft.nbt.ShortTag$Cache
- net.minecraft.nbt.SnbtPrinterTagVisitor
+ net.minecraft.nbt.StreamTagVisitor
- net.minecraft.nbt.StreamTagVisitor$EntryResult
+ net.minecraft.nbt.StreamTagVisitor$ValueResult
- net.minecraft.nbt.StringTag
+ net.minecraft.nbt.StringTag$1
- net.minecraft.nbt.StringTagVisitor
+ net.minecraft.nbt.Tag
- net.minecraft.nbt.TagParser
+ net.minecraft.nbt.TagType
- net.minecraft.nbt.TagType$1
+ net.minecraft.nbt.TagType$2
- net.minecraft.nbt.TagType$StaticSize
+ net.minecraft.nbt.TagType$VariableSize
- net.minecraft.nbt.TagTypes
+ net.minecraft.nbt.TagVisitor
- net.minecraft.nbt.TextComponentTagVisitor
- net.minecraft.nbt.visitors.CollectFields
+ net.minecraft.nbt.visitors.CollectToTag
- net.minecraft.nbt.visitors.FieldSelector
+ net.minecraft.nbt.visitors.FieldTree
+ net.minecraft.nbt.visitors.package-info
- net.minecraft.nbt.visitors.SkipAll
+ net.minecraft.nbt.visitors.SkipAll$1
- net.minecraft.nbt.visitors.SkipFields
+ net.minecraft.network.chat.ChatDecorator
- net.minecraft.network.chat.ChatType
+ net.minecraft.network.chat.ChatType$Bound
- net.minecraft.network.chat.ChatType$BoundNetwork
+ net.minecraft.network.chat.ChatTypeDecoration
- net.minecraft.network.chat.ChatTypeDecoration$Parameter
+ net.minecraft.network.chat.ChatTypeDecoration$Parameter$Selector
- net.minecraft.network.chat.ClickEvent
+ net.minecraft.network.chat.ClickEvent$Action
- net.minecraft.network.chat.CommonComponents
+ net.minecraft.network.chat.Component
- net.minecraft.network.chat.Component$Serializer
+ net.minecraft.network.chat.ComponentContents
- net.minecraft.network.chat.ComponentContents$1
+ net.minecraft.network.chat.ComponentUtils
- net.minecraft.network.chat.contents.BlockDataSource
+ net.minecraft.network.chat.contents.DataSource
- net.minecraft.network.chat.contents.EntityDataSource
+ net.minecraft.network.chat.contents.KeybindContents
- net.minecraft.network.chat.contents.KeybindResolver
+ net.minecraft.network.chat.contents.LiteralContents
- net.minecraft.network.chat.contents.NbtContents
- net.minecraft.network.chat.contents.package-info
+ net.minecraft.network.chat.contents.ScoreContents
- net.minecraft.network.chat.contents.SelectorContents
+ net.minecraft.network.chat.contents.StorageDataSource
- net.minecraft.network.chat.contents.TranslatableContents
+ net.minecraft.network.chat.contents.TranslatableFormatException
- net.minecraft.network.chat.FilterMask
+ net.minecraft.network.chat.FilterMask$1
- net.minecraft.network.chat.FilterMask$Type
+ net.minecraft.network.chat.FormattedText
- net.minecraft.network.chat.FormattedText$1
+ net.minecraft.network.chat.FormattedText$2
- net.minecraft.network.chat.FormattedText$3
+ net.minecraft.network.chat.FormattedText$4
- net.minecraft.network.chat.FormattedText$ContentConsumer
+ net.minecraft.network.chat.FormattedText$StyledContentConsumer
- net.minecraft.network.chat.HoverEvent
+ net.minecraft.network.chat.HoverEvent$Action
- net.minecraft.network.chat.HoverEvent$EntityTooltipInfo
+ net.minecraft.network.chat.HoverEvent$ItemStackInfo
- net.minecraft.network.chat.LastSeenMessages
+ net.minecraft.network.chat.LastSeenMessages$Packed
- net.minecraft.network.chat.LastSeenMessages$Update
+ net.minecraft.network.chat.LastSeenMessagesTracker
- net.minecraft.network.chat.LastSeenMessagesTracker$Update
+ net.minecraft.network.chat.LastSeenMessagesValidator
- net.minecraft.network.chat.LastSeenTrackedEntry
+ net.minecraft.network.chat.LocalChatSession
- net.minecraft.network.chat.MessageSignature
+ net.minecraft.network.chat.MessageSignature$Packed
- net.minecraft.network.chat.MessageSignatureCache
+ net.minecraft.network.chat.MutableComponent
- net.minecraft.network.chat.OutgoingChatMessage
+ net.minecraft.network.chat.OutgoingChatMessage$Disguised
- net.minecraft.network.chat.OutgoingChatMessage$Player
+ net.minecraft.network.chat.package-info
+ net.minecraft.network.chat.PlayerChatMessage
- net.minecraft.network.chat.RemoteChatSession
+ net.minecraft.network.chat.RemoteChatSession$Data
- net.minecraft.network.chat.SignableCommand
+ net.minecraft.network.chat.SignableCommand$Argument
- net.minecraft.network.chat.SignedMessageBody
+ net.minecraft.network.chat.SignedMessageBody$Packed
- net.minecraft.network.chat.SignedMessageChain
+ net.minecraft.network.chat.SignedMessageChain$DecodeException
- net.minecraft.network.chat.SignedMessageChain$Decoder
+ net.minecraft.network.chat.SignedMessageChain$Encoder
- net.minecraft.network.chat.SignedMessageLink
+ net.minecraft.network.chat.SignedMessageValidator
- net.minecraft.network.chat.SignedMessageValidator$KeyBased
+ net.minecraft.network.chat.Style
- net.minecraft.network.chat.Style$1
+ net.minecraft.network.chat.Style$1Collector
- net.minecraft.network.chat.Style$Serializer
+ net.minecraft.network.chat.SubStringSource
- net.minecraft.network.chat.TextColor
+ net.minecraft.network.chat.ThrowingComponent
- net.minecraft.network.CipherBase
+ net.minecraft.network.CipherDecoder
- net.minecraft.network.CipherEncoder
+ net.minecraft.network.CompressionDecoder
- net.minecraft.network.CompressionEncoder
+ net.minecraft.network.Connection
- net.minecraft.network.Connection$1
+ net.minecraft.network.Connection$2
- net.minecraft.network.Connection$PacketHolder
+ net.minecraft.network.ConnectionProtocol
- net.minecraft.network.ConnectionProtocol$PacketSet
+ net.minecraft.network.ConnectionProtocol$ProtocolBuilder
- net.minecraft.network.FriendlyByteBuf
+ net.minecraft.network.FriendlyByteBuf$1
- net.minecraft.network.FriendlyByteBuf$Reader
+ net.minecraft.network.FriendlyByteBuf$Writer
- net.minecraft.network.package-info
- net.minecraft.network.PacketBundlePacker
+ net.minecraft.network.PacketBundleUnpacker
- net.minecraft.network.PacketDecoder
+ net.minecraft.network.PacketEncoder
- net.minecraft.network.PacketListener
+ net.minecraft.network.PacketSendListener
- net.minecraft.network.PacketSendListener$1
+ net.minecraft.network.PacketSendListener$2
+ net.minecraft.network.protocol.BundleDelimiterPacket
- net.minecraft.network.protocol.BundlePacket
+ net.minecraft.network.protocol.BundlerInfo
- net.minecraft.network.protocol.BundlerInfo$1
+ net.minecraft.network.protocol.BundlerInfo$2
- net.minecraft.network.protocol.BundlerInfo$2$1
+ net.minecraft.network.protocol.BundlerInfo$Bundler
- net.minecraft.network.protocol.BundlerInfo$Provider
+ net.minecraft.network.protocol.game.ClientboundAddEntityPacket
- net.minecraft.network.protocol.game.ClientboundAddExperienceOrbPacket
+ net.minecraft.network.protocol.game.ClientboundAddPlayerPacket
- net.minecraft.network.protocol.game.ClientboundAnimatePacket
+ net.minecraft.network.protocol.game.ClientboundAwardStatsPacket
- net.minecraft.network.protocol.game.ClientboundBlockChangedAckPacket
+ net.minecraft.network.protocol.game.ClientboundBlockDestructionPacket
- net.minecraft.network.protocol.game.ClientboundBlockEntityDataPacket
+ net.minecraft.network.protocol.game.ClientboundBlockEventPacket
- net.minecraft.network.protocol.game.ClientboundBlockUpdatePacket
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$1
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket$AddOperation
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$Handler
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket$Operation
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$OperationType
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket$UpdateNameOperation
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$UpdateProgressOperation
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket$UpdatePropertiesOperation
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$UpdateStyleOperation
- net.minecraft.network.protocol.game.ClientboundSectionBlocksUpdatePacket
+ net.minecraft.network.protocol.game.ClientboundSelectAdvancementsTabPacket
- net.minecraft.network.protocol.game.ClientboundServerDataPacket
+ net.minecraft.network.protocol.game.ClientboundSetActionBarTextPacket
- net.minecraft.network.protocol.game.ClientboundSetBorderCenterPacket
+ net.minecraft.network.protocol.game.ClientboundSetBorderLerpSizePacket
- net.minecraft.network.protocol.game.ClientboundSetBorderSizePacket
+ net.minecraft.network.protocol.game.ClientboundSetBorderWarningDelayPacket
- net.minecraft.network.protocol.game.ClientboundSetBorderWarningDistancePacket
+ net.minecraft.network.protocol.game.ClientboundSetCameraPacket
- net.minecraft.network.protocol.game.ClientboundSetCarriedItemPacket
+ net.minecraft.network.protocol.game.ClientboundSetChunkCacheCenterPacket
- net.minecraft.network.protocol.game.ClientboundSetChunkCacheRadiusPacket
+ net.minecraft.network.protocol.game.ClientboundSetDefaultSpawnPositionPacket
- net.minecraft.network.protocol.game.ClientboundSetDisplayObjectivePacket
+ net.minecraft.network.protocol.game.ClientboundSetEntityDataPacket
- net.minecraft.network.protocol.game.ClientboundSetEntityLinkPacket
+ net.minecraft.network.protocol.game.ClientboundSetEntityMotionPacket
- net.minecraft.network.protocol.game.ClientboundSetEquipmentPacket
+ net.minecraft.network.protocol.game.ClientboundSetExperiencePacket
- net.minecraft.network.protocol.game.ClientboundSetHealthPacket
+ net.minecraft.network.protocol.game.ClientboundSetObjectivePacket
- net.minecraft.network.protocol.game.ClientboundSetPassengersPacket
+ net.minecraft.network.protocol.game.ClientboundSetPlayerTeamPacket
- net.minecraft.network.protocol.game.ClientboundSetPlayerTeamPacket$Action
+ net.minecraft.network.protocol.game.ClientboundSetPlayerTeamPacket$Parameters
- net.minecraft.network.protocol.game.ClientboundSetScorePacket
+ net.minecraft.network.protocol.game.ClientboundSetSimulationDistancePacket
- net.minecraft.network.protocol.game.ClientboundSetSubtitleTextPacket
+ net.minecraft.network.protocol.game.ClientboundSetTimePacket
+ net.minecraft.network.protocol.game.ClientboundSetTitlesAnimationPacket
- net.minecraft.network.protocol.game.ClientboundSetTitleTextPacket
- net.minecraft.network.protocol.game.ClientboundSoundEntityPacket
+ net.minecraft.network.protocol.game.ClientboundSoundPacket
- net.minecraft.network.protocol.game.ClientboundStopSoundPacket
+ net.minecraft.network.protocol.game.ClientboundSystemChatPacket
- net.minecraft.network.protocol.game.ClientboundTabListPacket
+ net.minecraft.network.protocol.game.ClientboundTagQueryPacket
- net.minecraft.network.protocol.game.ClientboundTakeItemEntityPacket
+ net.minecraft.network.protocol.game.ClientboundTeleportEntityPacket
- net.minecraft.network.protocol.game.ClientboundUpdateAdvancementsPacket
+ net.minecraft.network.protocol.game.ClientboundUpdateAttributesPacket
- net.minecraft.network.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
+ net.minecraft.network.protocol.game.ClientboundUpdateEnabledFeaturesPacket
- net.minecraft.network.protocol.game.ClientboundUpdateMobEffectPacket
+ net.minecraft.network.protocol.game.ClientboundUpdateRecipesPacket
- net.minecraft.network.protocol.game.ClientboundUpdateTagsPacket
- net.minecraft.network.protocol.game.ClientboundVoteFinishPacket
- net.minecraft.network.protocol.game.ClientboundVoteStartPacket
- net.minecraft.network.protocol.game.ClientGamePacketListener
+ net.minecraft.network.protocol.game.DebugEntityNameGenerator
- net.minecraft.network.protocol.game.DebugPackets
+ net.minecraft.network.protocol.game.package-info
+ net.minecraft.network.protocol.game.ServerboundAcceptTeleportationPacket
- net.minecraft.network.protocol.game.ServerboundBlockEntityTagQuery
+ net.minecraft.network.protocol.game.ServerboundChangeDifficultyPacket
- net.minecraft.network.protocol.game.ServerboundChatAckPacket
+ net.minecraft.network.protocol.game.ServerboundChatCommandPacket
- net.minecraft.network.protocol.game.ServerboundChatPacket
+ net.minecraft.network.protocol.game.ServerboundChatSessionUpdatePacket
- net.minecraft.network.protocol.game.ServerboundClientCommandPacket
+ net.minecraft.network.protocol.game.ServerboundClientCommandPacket$Action
- net.minecraft.network.protocol.game.ServerboundClientInformationPacket
+ net.minecraft.network.protocol.game.ServerboundCommandSuggestionPacket
- net.minecraft.network.protocol.game.ServerboundContainerButtonClickPacket
+ net.minecraft.network.protocol.game.ServerboundContainerClickPacket
- net.minecraft.network.protocol.game.ServerboundContainerClosePacket
+ net.minecraft.network.protocol.game.ServerGamePacketListener
- net.minecraft.network.protocol.game.ServerPacketListener
- net.minecraft.network.protocol.game.VecDeltaCodec
- net.minecraft.network.protocol.handshake.ClientIntentionPacket
- net.minecraft.network.protocol.handshake.package-info
+ net.minecraft.network.protocol.handshake.ServerHandshakePacketListener
- net.minecraft.network.protocol.login.ClientboundCustomQueryPacket
+ net.minecraft.network.protocol.login.ClientboundGameProfilePacket
- net.minecraft.network.protocol.login.ClientboundHelloPacket
+ net.minecraft.network.protocol.login.ClientboundLoginCompressionPacket
- net.minecraft.network.protocol.login.ClientboundLoginDisconnectPacket
+ net.minecraft.network.protocol.login.ClientLoginPacketListener
+ net.minecraft.network.protocol.login.package-info
- net.minecraft.network.protocol.login.ServerboundCustomQueryPacket
+ net.minecraft.network.protocol.login.ServerboundHelloPacket
- net.minecraft.network.protocol.login.ServerboundKeyPacket
+ net.minecraft.network.protocol.login.ServerLoginPacketListener
- net.minecraft.network.protocol.package-info
+ net.minecraft.network.protocol.Packet
- net.minecraft.network.protocol.PacketFlow
+ net.minecraft.network.protocol.PacketUtils
- net.minecraft.network.protocol.status.ClientboundPongResponsePacket
+ net.minecraft.network.protocol.status.ClientboundStatusResponsePacket
+ net.minecraft.network.protocol.status.ClientStatusPacketListener
+ net.minecraft.network.protocol.status.package-info
+ net.minecraft.network.protocol.status.ServerboundPingRequestPacket
- net.minecraft.network.protocol.status.ServerboundStatusRequestPacket
- net.minecraft.network.protocol.status.ServerStatus
+ net.minecraft.network.protocol.status.ServerStatus$Favicon
- net.minecraft.network.protocol.status.ServerStatus$Players
+ net.minecraft.network.protocol.status.ServerStatus$Version
- net.minecraft.network.protocol.status.ServerStatusPacketListener
- net.minecraft.network.RateKickingConnection
+ net.minecraft.network.SkipPacketException
- net.minecraft.network.syncher.EntityDataAccessor
+ net.minecraft.network.syncher.EntityDataSerializer
- net.minecraft.network.syncher.EntityDataSerializer$1
+ net.minecraft.network.syncher.EntityDataSerializer$ForValueType
- net.minecraft.network.syncher.EntityDataSerializers
+ net.minecraft.network.syncher.EntityDataSerializers$1
- net.minecraft.network.syncher.EntityDataSerializers$2
+ net.minecraft.network.syncher.EntityDataSerializers$3
- net.minecraft.network.syncher.EntityDataSerializers$4
+ net.minecraft.network.syncher.EntityDataSerializers$5
- net.minecraft.network.syncher.EntityDataSerializers$6
+ net.minecraft.network.syncher.EntityDataSerializers$7
+ net.minecraft.network.syncher.package-info
- net.minecraft.network.syncher.SynchedEntityData
+ net.minecraft.network.syncher.SynchedEntityData$DataItem
- net.minecraft.network.syncher.SynchedEntityData$DataValue
- net.minecraft.network.TickablePacketListener
+ net.minecraft.network.Varint21FrameDecoder
- net.minecraft.network.Varint21LengthFieldPrepender
- net.minecraft.obfuscate.DontObfuscate
+ net.minecraft.obfuscate.package-info
- net.minecraft.package-info
+ net.minecraft.recipebook.package-info
+ net.minecraft.recipebook.PlaceRecipe
- net.minecraft.recipebook.ServerPlaceRecipe
- net.minecraft.resources.DelegatingOps
+ net.minecraft.resources.FileToIdConverter
- net.minecraft.resources.HolderSetCodec
+ net.minecraft.resources.package-info
+ net.minecraft.resources.RegistryDataLoader
- net.minecraft.resources.RegistryDataLoader$1
+ net.minecraft.resources.RegistryDataLoader$Loader
- net.minecraft.resources.RegistryDataLoader$RegistryData
+ net.minecraft.resources.RegistryFileCodec
- net.minecraft.resources.RegistryFixedCodec
+ net.minecraft.resources.RegistryOps
- net.minecraft.resources.RegistryOps$1
+ net.minecraft.resources.RegistryOps$2
- net.minecraft.resources.RegistryOps$RegistryInfo
+ net.minecraft.resources.RegistryOps$RegistryInfoLookup
- net.minecraft.resources.ResourceKey
+ net.minecraft.resources.ResourceKey$InternKey
- net.minecraft.resources.ResourceLocation
+ net.minecraft.resources.ResourceLocation$Dummy
- net.minecraft.resources.ResourceLocation$Serializer
- net.minecraft.server.advancements.AdvancementVisibilityEvaluator
+ net.minecraft.server.advancements.AdvancementVisibilityEvaluator$Output
- net.minecraft.server.advancements.AdvancementVisibilityEvaluator$VisibilityRule
+ net.minecraft.server.advancements.package-info
- net.minecraft.server.Bootstrap
+ net.minecraft.server.Bootstrap$1
- net.minecraft.server.bossevents.CustomBossEvent
+ net.minecraft.server.bossevents.CustomBossEvents
- net.minecraft.server.bossevents.package-info
- net.minecraft.server.ChainedJsonException
+ net.minecraft.server.ChainedJsonException$Entry
+ net.minecraft.server.chase.ChaseClient
- net.minecraft.server.chase.ChaseClient$TeleportTarget
+ net.minecraft.server.chase.ChaseServer
- net.minecraft.server.chase.ChaseServer$PlayerPosition
+ net.minecraft.server.chase.package-info
- net.minecraft.server.commands.AdvancementCommands
+ net.minecraft.server.commands.AdvancementCommands$Action
- net.minecraft.server.commands.AdvancementCommands$Action$1
+ net.minecraft.server.commands.AdvancementCommands$Action$2
- net.minecraft.server.commands.AdvancementCommands$Mode
+ net.minecraft.server.commands.AttributeCommand
- net.minecraft.server.commands.BanIpCommands
+ net.minecraft.server.commands.BanListCommands
- net.minecraft.server.commands.BanPlayerCommands
+ net.minecraft.server.commands.BossBarCommands
- net.minecraft.server.commands.ChaseCommand
+ net.minecraft.server.commands.ClearInventoryCommands
- net.minecraft.server.commands.CloneCommands
+ net.minecraft.server.commands.CloneCommands$CloneBlockInfo
- net.minecraft.server.commands.CloneCommands$CommandFunction
+ net.minecraft.server.commands.CloneCommands$DimensionAndPosition
- net.minecraft.server.commands.CloneCommands$Mode
+ net.minecraft.server.commands.DamageCommand
- net.minecraft.server.commands.data.BlockDataAccessor
+ net.minecraft.server.commands.data.BlockDataAccessor$1
- net.minecraft.server.commands.data.DataAccessor
+ net.minecraft.server.commands.data.DataCommands
- net.minecraft.server.commands.data.DataCommands$DataManipulator
+ net.minecraft.server.commands.data.DataCommands$DataManipulatorDecorator
- net.minecraft.server.commands.data.DataCommands$DataProvider
+ net.minecraft.server.commands.data.EntityDataAccessor
- net.minecraft.server.commands.data.EntityDataAccessor$1
+ net.minecraft.server.commands.data.package-info
+ net.minecraft.server.commands.data.StorageDataAccessor
- net.minecraft.server.commands.data.StorageDataAccessor$1
- net.minecraft.server.commands.DataPackCommand
+ net.minecraft.server.commands.DataPackCommand$Inserter
+ net.minecraft.server.commands.DebugCommand
- net.minecraft.server.commands.DebugCommand$Tracer
+ net.minecraft.server.commands.DebugMobSpawningCommand
- net.minecraft.server.commands.DebugPathCommand
+ net.minecraft.server.commands.DefaultGameModeCommands
- net.minecraft.server.commands.DeOpCommands
- net.minecraft.server.commands.DifficultyCommand
+ net.minecraft.server.commands.EffectCommands
- net.minecraft.server.commands.EmoteCommands
+ net.minecraft.server.commands.EnchantCommand
- net.minecraft.server.commands.ExecuteCommand
+ net.minecraft.server.commands.ExecuteCommand$CommandNumericPredicate
- net.minecraft.server.commands.ExecuteCommand$CommandPredicate
+ net.minecraft.server.commands.ExperienceCommand
- net.minecraft.server.commands.ExperienceCommand$Type
+ net.minecraft.server.commands.FillBiomeCommand
- net.minecraft.server.commands.FillCommand
+ net.minecraft.server.commands.FillCommand$Mode
- net.minecraft.server.commands.ForceLoadCommand
+ net.minecraft.server.commands.FunctionCommand
- net.minecraft.server.commands.GameModeCommand
+ net.minecraft.server.commands.GameRuleCommand
- net.minecraft.server.commands.GameRuleCommand$1
+ net.minecraft.server.commands.GiveCommand
- net.minecraft.server.commands.HelpCommand
+ net.minecraft.server.commands.ItemCommands
- net.minecraft.server.commands.JfrCommand
+ net.minecraft.server.commands.KickCommand
- net.minecraft.server.commands.KillCommand
+ net.minecraft.server.commands.ListPlayersCommand
- net.minecraft.server.commands.LocateCommand
+ net.minecraft.server.commands.LootCommand
- net.minecraft.server.commands.LootCommand$Callback
+ net.minecraft.server.commands.LootCommand$DropConsumer
- net.minecraft.server.commands.LootCommand$TailProvider
+ net.minecraft.server.commands.MsgCommand
- net.minecraft.server.commands.OpCommand
- net.minecraft.server.commands.package-info
+ net.minecraft.server.commands.PardonCommand
- net.minecraft.server.commands.PardonIpCommand
+ net.minecraft.server.commands.ParticleCommand
- net.minecraft.server.commands.PerfCommand
+ net.minecraft.server.commands.PlaceCommand
- net.minecraft.server.commands.PlaySoundCommand
+ net.minecraft.server.commands.PublishCommand
- net.minecraft.server.commands.RaidCommand
+ net.minecraft.server.commands.RecipeCommand
- net.minecraft.server.commands.ReloadCommand
+ net.minecraft.server.commands.ResetChunksCommand
- net.minecraft.server.commands.RideCommand
+ net.minecraft.server.commands.SaveAllCommand
- net.minecraft.server.commands.SaveOffCommand
+ net.minecraft.server.commands.SaveOnCommand
- net.minecraft.server.commands.SayCommand
+ net.minecraft.server.commands.ScheduleCommand
- net.minecraft.server.commands.ScoreboardCommand
+ net.minecraft.server.commands.SeedCommand
- net.minecraft.server.commands.SetBlockCommand
+ net.minecraft.server.commands.SetBlockCommand$Filter
- net.minecraft.server.commands.SetBlockCommand$Mode
+ net.minecraft.server.commands.SetPlayerIdleTimeoutCommand
- net.minecraft.server.commands.SetSpawnCommand
+ net.minecraft.server.commands.SetWorldSpawnCommand
- net.minecraft.server.commands.SpawnArmorTrimsCommand
+ net.minecraft.server.commands.SpectateCommand
- net.minecraft.server.commands.SpreadPlayersCommand
+ net.minecraft.server.commands.SpreadPlayersCommand$Position
- net.minecraft.server.commands.StopCommand
+ net.minecraft.server.commands.StopSoundCommand
- net.minecraft.server.commands.SummonCommand
+ net.minecraft.server.commands.TagCommand
- net.minecraft.server.commands.TeamCommand
+ net.minecraft.server.commands.TeamMsgCommand
- net.minecraft.server.commands.TeleportCommand
+ net.minecraft.server.commands.TeleportCommand$LookAt
- net.minecraft.server.commands.TellRawCommand
+ net.minecraft.server.commands.TimeCommand
- net.minecraft.server.commands.TitleCommand
+ net.minecraft.server.commands.TriggerCommand
- net.minecraft.server.commands.WardenSpawnTrackerCommand
+ net.minecraft.server.commands.WeatherCommand
- net.minecraft.server.commands.WhitelistCommand
+ net.minecraft.server.commands.WorldBorderCommand
- net.minecraft.server.ConsoleInput
+ net.minecraft.server.DebugLoggedPrintStream
+ net.minecraft.server.dedicated.DedicatedPlayerList
- net.minecraft.server.dedicated.DedicatedServer
+ net.minecraft.server.dedicated.DedicatedServer$1
- net.minecraft.server.dedicated.DedicatedServerProperties
+ net.minecraft.server.dedicated.DedicatedServerProperties$WorldDimensionData
- net.minecraft.server.dedicated.DedicatedServerSettings
+ net.minecraft.server.dedicated.package-info
+ net.minecraft.server.dedicated.ServerWatchdog
- net.minecraft.server.dedicated.ServerWatchdog$1
+ net.minecraft.server.dedicated.Settings
- net.minecraft.server.dedicated.Settings$MutableValue
- net.minecraft.server.Eula
- net.minecraft.server.gui.MinecraftServerGui
+ net.minecraft.server.gui.MinecraftServerGui$1
- net.minecraft.server.gui.MinecraftServerGui$2
+ net.minecraft.server.gui.package-info
+ net.minecraft.server.gui.PlayerListComponent
- net.minecraft.server.gui.StatsComponent
- net.minecraft.server.level.BlockDestructionProgress
+ net.minecraft.server.level.ChunkHolder
- net.minecraft.server.level.ChunkHolder$1
+ net.minecraft.server.level.ChunkHolder$ChunkLoadingFailure
- net.minecraft.server.level.ChunkHolder$ChunkLoadingFailure$1
+ net.minecraft.server.level.ChunkHolder$ChunkSaveDebug
- net.minecraft.server.level.ChunkHolder$FullChunkStatus
+ net.minecraft.server.level.ChunkHolder$LevelChangeListener
- net.minecraft.server.level.ChunkHolder$PlayerProvider
+ net.minecraft.server.level.ChunkMap
- net.minecraft.server.level.ChunkMap$1
+ net.minecraft.server.level.ChunkMap$2
- net.minecraft.server.level.ChunkMap$DistanceManager
+ net.minecraft.server.level.ChunkMap$TrackedEntity
- net.minecraft.server.level.ChunkTaskPriorityQueue
+ net.minecraft.server.level.ChunkTaskPriorityQueueSorter
- net.minecraft.server.level.ChunkTaskPriorityQueueSorter$Message
+ net.minecraft.server.level.ChunkTaskPriorityQueueSorter$Release
- net.minecraft.server.level.ChunkTracker
+ net.minecraft.server.level.ColumnPos
- net.minecraft.server.level.DemoMode
+ net.minecraft.server.level.DistanceManager
- net.minecraft.server.level.DistanceManager$ChunkTicketTracker
+ net.minecraft.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
- net.minecraft.server.level.DistanceManager$PlayerTicketTracker
+ net.minecraft.server.level.PlayerMap
- net.minecraft.server.level.PlayerRespawnLogic
+ net.minecraft.server.level.SectionTracker
- net.minecraft.server.level.ServerBossEvent
+ net.minecraft.server.level.ServerChunkCache
- net.minecraft.server.level.ServerChunkCache$ChunkAndHolder
+ net.minecraft.server.level.ServerChunkCache$MainThreadExecutor
- net.minecraft.server.level.ServerEntity
+ net.minecraft.server.level.ServerLevel
- net.minecraft.server.level.ServerLevel$1
+ net.minecraft.server.LoggedPrintStream
- net.minecraft.server.Main
+ net.minecraft.server.Main$1
- net.minecraft.server.MinecraftServer
+ net.minecraft.server.MinecraftServer$1
- net.minecraft.server.MinecraftServer$ReloadableResources
+ net.minecraft.server.MinecraftServer$ServerResourcePackInfo
- net.minecraft.server.MinecraftServer$TimeProfiler
+ net.minecraft.server.MinecraftServer$TimeProfiler$1
- net.minecraft.server.PlayerAdvancements
+ net.minecraft.server.PlayerAdvancements$1
- net.minecraft.server.RegistryLayer
+ net.minecraft.server.ReloadableServerResources
- net.minecraft.server.RunningOnDifferentThreadException
+ net.minecraft.server.ServerAdvancementManager
- net.minecraft.server.ServerFunctionLibrary
+ net.minecraft.server.ServerFunctionManager
- net.minecraft.server.ServerFunctionManager$ExecutionContext
+ net.minecraft.server.ServerFunctionManager$QueuedCommand
- net.minecraft.server.ServerFunctionManager$TraceCallbacks
+ net.minecraft.server.ServerInterface
- net.minecraft.server.ServerScoreboard
+ net.minecraft.server.ServerScoreboard$Method
- net.minecraft.server.Services
+ net.minecraft.server.TickTask
- net.minecraft.server.WorldLoader
+ net.minecraft.server.WorldLoader$DataLoadContext
- net.minecraft.server.WorldLoader$DataLoadOutput
+ net.minecraft.server.WorldLoader$InitConfig
- net.minecraft.server.WorldLoader$PackConfig
+ net.minecraft.server.WorldLoader$ResultFactory
- net.minecraft.server.WorldLoader$WorldDataSupplier
+ net.minecraft.server.WorldStem
+ net.minecraft.util.datafix.schemas.package-info
- net.minecraft.util.datafix.schemas.V3444
+ net.minecraft.util.datafix.schemas.V501
- net.minecraft.util.datafix.schemas.V700
+ net.minecraft.util.datafix.schemas.V701
- net.minecraft.util.datafix.schemas.V702
+ net.minecraft.util.datafix.schemas.V703
- net.minecraft.util.datafix.schemas.V704
+ net.minecraft.util.datafix.schemas.V704$1
- net.minecraft.util.datafix.schemas.V705
+ net.minecraft.util.datafix.schemas.V705$1
- net.minecraft.util.datafix.schemas.V808
+ net.minecraft.util.datafix.schemas.V99
- net.minecraft.util.datafix.schemas.V99$1
- net.minecraft.util.eventlog.EventLogDirectory
+ net.minecraft.util.eventlog.EventLogDirectory$CompressedFile
- net.minecraft.util.eventlog.EventLogDirectory$File
+ net.minecraft.util.eventlog.EventLogDirectory$FileId
- net.minecraft.util.eventlog.EventLogDirectory$FileList
+ net.minecraft.util.eventlog.EventLogDirectory$RawFile
- net.minecraft.util.eventlog.JsonEventLog
+ net.minecraft.util.eventlog.JsonEventLog$1
- net.minecraft.util.eventlog.JsonEventLogReader
+ net.minecraft.util.eventlog.JsonEventLogReader$1
- net.minecraft.util.eventlog.package-info
+ net.minecraft.util.monitoring.jmx.MinecraftServerStatistics
- net.minecraft.util.monitoring.jmx.MinecraftServerStatistics$AttributeDescription
+ net.minecraft.util.monitoring.jmx.package-info
- net.minecraft.util.package-info
+ net.minecraft.util.profiling.ActiveProfiler
- net.minecraft.util.profiling.ActiveProfiler$PathEntry
+ net.minecraft.util.profiling.ContinuousProfiler
- net.minecraft.util.profiling.EmptyProfileResults
+ net.minecraft.util.profiling.FilledProfileResults
- net.minecraft.util.profiling.FilledProfileResults$1
+ net.minecraft.util.profiling.FilledProfileResults$CounterCollector
- net.minecraft.util.profiling.InactiveProfiler
- net.minecraft.util.profiling.jfr.callback.package-info
+ net.minecraft.util.profiling.jfr.callback.ProfiledDuration
- net.minecraft.util.profiling.jfr.Environment
+ net.minecraft.util.profiling.jfr.event.ChunkGenerationEvent
- net.minecraft.util.profiling.jfr.event.ChunkGenerationEvent$Fields
+ net.minecraft.util.profiling.jfr.event.NetworkSummaryEvent
- net.minecraft.util.profiling.jfr.event.NetworkSummaryEvent$Fields
+ net.minecraft.util.profiling.jfr.event.NetworkSummaryEvent$SumAggregation
+ net.minecraft.util.profiling.jfr.event.package-info
- net.minecraft.util.profiling.jfr.event.PacketEvent
+ net.minecraft.util.profiling.jfr.event.PacketEvent$Fields
- net.minecraft.util.profiling.jfr.event.PacketReceivedEvent
+ net.minecraft.util.profiling.jfr.event.PacketSentEvent
- net.minecraft.util.profiling.jfr.event.ServerTickTimeEvent
+ net.minecraft.util.profiling.jfr.event.ServerTickTimeEvent$Fields
- net.minecraft.util.profiling.jfr.event.WorldLoadFinishedEvent
+ net.minecraft.util.profiling.jfr.JfrProfiler
- net.minecraft.util.profiling.jfr.JfrProfiler$1
+ net.minecraft.util.profiling.jfr.JvmProfiler
- net.minecraft.util.profiling.jfr.JvmProfiler$NoOpProfiler
- net.minecraft.util.profiling.jfr.package-info
+ net.minecraft.util.profiling.jfr.parse.JfrStatsParser
- net.minecraft.util.profiling.jfr.parse.JfrStatsParser$1
+ net.minecraft.util.profiling.jfr.parse.JfrStatsParser$MutableCountAndSize
- net.minecraft.util.profiling.jfr.parse.JfrStatsResult
+ net.minecraft.util.profiling.jfr.parse.package-info
+ net.minecraft.util.profiling.jfr.Percentiles
- net.minecraft.util.profiling.jfr.serialize.JfrResultJsonSerializer
+ net.minecraft.util.profiling.jfr.serialize.package-info
- net.minecraft.util.profiling.jfr.stats.ChunkGenStat
+ net.minecraft.util.profiling.jfr.stats.CpuLoadStat
- net.minecraft.util.profiling.jfr.stats.FileIOStat
+ net.minecraft.util.profiling.jfr.stats.FileIOStat$Summary
- net.minecraft.util.profiling.jfr.stats.GcHeapStat
+ net.minecraft.util.profiling.jfr.stats.GcHeapStat$Summary
- net.minecraft.util.profiling.jfr.stats.GcHeapStat$Timing
+ net.minecraft.util.profiling.jfr.stats.NetworkPacketSummary
- net.minecraft.util.profiling.jfr.stats.NetworkPacketSummary$PacketCountAndSize
+ net.minecraft.util.profiling.jfr.stats.NetworkPacketSummary$PacketIdentification
- net.minecraft.util.profiling.jfr.stats.package-info
- net.minecraft.util.profiling.jfr.stats.ThreadAllocationStat
+ net.minecraft.util.profiling.jfr.stats.ThreadAllocationStat$Summary
- net.minecraft.util.profiling.jfr.stats.TickTimeStat
- net.minecraft.util.profiling.jfr.stats.TimedStat
+ net.minecraft.util.profiling.jfr.stats.TimedStatSummary
+ net.minecraft.util.profiling.jfr.stats.TimeStamped
- net.minecraft.util.profiling.jfr.SummaryReporter
+ net.minecraft.util.profiling.metrics.MetricCategory
- net.minecraft.util.profiling.metrics.MetricSampler
+ net.minecraft.util.profiling.metrics.MetricSampler$MetricSamplerBuilder
- net.minecraft.util.profiling.metrics.MetricSampler$SamplerResult
+ net.minecraft.util.profiling.metrics.MetricSampler$ThresholdTest
- net.minecraft.util.profiling.metrics.MetricSampler$ValueIncreasedByPercentage
+ net.minecraft.util.profiling.metrics.MetricsRegistry
- net.minecraft.util.profiling.metrics.MetricsRegistry$AggregatedMetricSampler
+ net.minecraft.util.profiling.metrics.MetricsSamplerProvider
+ net.minecraft.util.profiling.metrics.package-info
- net.minecraft.util.profiling.metrics.ProfilerMeasured
- net.minecraft.util.profiling.metrics.profiling.ActiveMetricsRecorder
+ net.minecraft.util.profiling.metrics.profiling.InactiveMetricsRecorder
- net.minecraft.util.profiling.metrics.profiling.MetricsRecorder
+ net.minecraft.util.profiling.metrics.profiling.package-info
+ net.minecraft.util.profiling.metrics.profiling.ProfilerSamplerAdapter
- net.minecraft.util.profiling.metrics.profiling.ServerMetricsSamplersProvider
+ net.minecraft.util.profiling.metrics.profiling.ServerMetricsSamplersProvider$1
- net.minecraft.util.profiling.metrics.profiling.ServerMetricsSamplersProvider$CpuStats
- net.minecraft.util.profiling.metrics.storage.MetricsPersister
- net.minecraft.util.profiling.metrics.storage.package-info
+ net.minecraft.util.profiling.metrics.storage.RecordedDeviation
+ net.minecraft.util.profiling.package-info
+ net.minecraft.util.profiling.ProfileCollector
- net.minecraft.util.profiling.ProfileResults
+ net.minecraft.util.profiling.ProfilerFiller
- net.minecraft.util.profiling.ProfilerFiller$1
+ net.minecraft.util.profiling.ProfilerPathEntry
- net.minecraft.util.profiling.ResultField
+ net.minecraft.util.profiling.SingleTickProfiler
- net.minecraft.util.random.package-info
- net.minecraft.util.random.SimpleWeightedRandomList
+ net.minecraft.util.random.SimpleWeightedRandomList$Builder
- net.minecraft.util.random.Weight
+ net.minecraft.util.random.WeightedEntry
- net.minecraft.util.random.WeightedEntry$IntrusiveBase
+ net.minecraft.util.random.WeightedEntry$Wrapper
- net.minecraft.util.random.WeightedRandom
+ net.minecraft.util.random.WeightedRandomList
- net.minecraft.util.RgbTxt
+ net.minecraft.util.thread.BlockableEventLoop
- net.minecraft.util.thread.NamedThreadFactory
+ net.minecraft.util.thread.package-info
+ net.minecraft.util.thread.ProcessorHandle
- net.minecraft.util.thread.ProcessorHandle$1
+ net.minecraft.util.thread.ProcessorMailbox
- net.minecraft.util.thread.ReentrantBlockableEventLoop
+ net.minecraft.util.thread.StrictQueue
- net.minecraft.util.thread.StrictQueue$FixedPriorityQueue
+ net.minecraft.util.thread.StrictQueue$IntRunnable
- net.minecraft.util.thread.StrictQueue$QueueStrictQueue
- net.minecraft.util.valueproviders.BiasedToBottomInt
+ net.minecraft.util.valueproviders.ClampedInt
- net.minecraft.util.valueproviders.ClampedNormalFloat
+ net.minecraft.util.valueproviders.ClampedNormalInt
- net.minecraft.util.valueproviders.ConstantFloat
+ net.minecraft.util.valueproviders.ConstantInt
- net.minecraft.util.valueproviders.FloatProvider
+ net.minecraft.util.valueproviders.FloatProviderType
- net.minecraft.util.valueproviders.IntProvider
+ net.minecraft.util.valueproviders.IntProviderType
- net.minecraft.util.valueproviders.MultipliedFloats
- net.minecraft.util.valueproviders.package-info
+ net.minecraft.util.valueproviders.SampledFloat
- net.minecraft.util.valueproviders.TrapezoidFloat
+ net.minecraft.util.valueproviders.UniformFloat
- net.minecraft.util.valueproviders.UniformInt
+ net.minecraft.util.valueproviders.WeightedListInt
- net.minecraft.util.worldupdate.package-info
+ net.minecraft.util.worldupdate.WorldUpgrader
- net.minecraft.voting.rules.actual.BinaryGameRuleRule
- net.minecraft.voting.rules.actual.BiomeColorRule
- net.minecraft.voting.rules.actual.BlockFlammabilityRule$Flammability
- net.minecraft.voting.rules.actual.BlockModelReplacementRule
- net.minecraft.voting.rules.actual.BlockModelReplacementRule$Replacements
- net.minecraft.voting.rules.actual.CaepType
- net.minecraft.voting.rules.actual.CodepointReplaceRule
- net.minecraft.voting.rules.actual.CodepointStyleRule$CodepointChange
- net.minecraft.voting.rules.actual.CopySkinRule
- net.minecraft.voting.rules.actual.DayLengthRule
- net.minecraft.voting.rules.actual.DoubleOrHalfItemMapRule
- net.minecraft.voting.rules.actual.FlailingLevel
- net.minecraft.voting.rules.actual.FootprintRule
- net.minecraft.voting.rules.actual.GiveEffectRule$MobEffectEntry
- net.minecraft.voting.rules.actual.Goldifier$1
- net.minecraft.voting.rules.actual.IntegerGameRuleRule$RuleRuleChange
- net.minecraft.voting.rules.actual.ItemEntityDespawn
- net.minecraft.voting.rules.actual.ItemGiveRule$GiveItemRule
- net.minecraft.voting.rules.actual.ItemReplacementRule
- net.minecraft.voting.rules.actual.LightEngineMode
- net.minecraft.voting.rules.actual.MoonRule
- net.minecraft.voting.rules.actual.NaturalSpawnReplaceRule
- net.minecraft.voting.rules.actual.package-info
- net.minecraft.voting.rules.actual.ParentTrapRule
- net.minecraft.voting.rules.actual.PlayerEntry
- net.minecraft.voting.rules.actual.RecipeEnableRule
- net.minecraft.voting.rules.actual.ReplaceItemsRule
- net.minecraft.voting.rules.actual.ReplaceItemsRule$ReplaceRuleChange
- net.minecraft.voting.rules.actual.SoundEventReplacementRule
- net.minecraft.voting.rules.actual.TheJokeRule$1
- net.minecraft.voting.rules.actual.ThreadedAnvilChunkStorage$1
- net.minecraft.voting.rules.actual.TransformEntityRule
- net.minecraft.voting.rules.actual.TransformScaleRule
- net.minecraft.voting.rules.actual.VehicleCollisionRule
- net.minecraft.voting.rules.actual.WeatherOption
- net.minecraft.voting.rules.BooleanRule
- net.minecraft.voting.rules.CounterRule
- net.minecraft.voting.rules.CounterRule$CounterRuleChange
- net.minecraft.voting.rules.DoubleOrHalfMapRule
- net.minecraft.voting.rules.EnumRule
- net.minecraft.voting.rules.EnumRule$EnumRuleChange
- net.minecraft.voting.rules.FixedOrRandomKeyRule$1
- net.minecraft.voting.rules.MapRule
- net.minecraft.voting.rules.MapRule$MapRuleChange
- net.minecraft.voting.rules.OneShotRule$1
- net.minecraft.voting.rules.OneShotRule$Resettable
- net.minecraft.voting.rules.RandomNumberRule
- net.minecraft.voting.rules.RandomNumberRule$RandomFloat
- net.minecraft.voting.rules.RandomNumberRule$RandomNumberRuleChange
- net.minecraft.voting.rules.ResourceKeySetRule
- net.minecraft.voting.rules.ResourceKeySingleRule$1
- net.minecraft.voting.rules.Rule
- net.minecraft.voting.rules.RuleChange
- net.minecraft.voting.rules.RuleChange$Simple
- net.minecraft.voting.rules.Rules$1
- net.minecraft.voting.rules.Rules$11
- net.minecraft.voting.rules.Rules$13
- net.minecraft.voting.rules.Rules$15
- net.minecraft.voting.rules.Rules$17
- net.minecraft.voting.rules.Rules$19
- net.minecraft.voting.rules.Rules$20
- net.minecraft.voting.rules.Rules$22
- net.minecraft.voting.rules.Rules$24
- net.minecraft.voting.rules.Rules$26
- net.minecraft.voting.rules.Rules$28
- net.minecraft.voting.rules.Rules$3
- net.minecraft.voting.rules.Rules$31
- net.minecraft.voting.rules.Rules$33
- net.minecraft.voting.rules.Rules$35
- net.minecraft.voting.rules.Rules$37
- net.minecraft.voting.rules.Rules$39
- net.minecraft.voting.rules.Rules$40
- net.minecraft.voting.rules.Rules$42
- net.minecraft.voting.rules.Rules$5
- net.minecraft.voting.rules.Rules$7
- net.minecraft.voting.rules.Rules$9
- net.minecraft.voting.rules.SetRule$SetRuleChange
- net.minecraft.voting.rules.UniformIntRule$1
- net.minecraft.voting.rules.VotingCostRule
- net.minecraft.voting.rules.VotingCostRule$Change
- net.minecraft.voting.VoteCommand$1
- net.minecraft.voting.votes.ClientVote
- net.minecraft.voting.votes.CommonVoteData
- net.minecraft.voting.votes.FinishedVote$1
- net.minecraft.voting.votes.FinishedVote$UnpackOptions
- net.minecraft.voting.votes.OptionVoteStorage
- net.minecraft.voting.votes.ServerVote
- net.minecraft.voting.votes.ServerVote$Option
- net.minecraft.voting.votes.ServerVoteStorage
- net.minecraft.voting.votes.ServerVoteStorage$VoteResult
- net.minecraft.voting.votes.Voter
- net.minecraft.voting.votes.VoteResults
- net.minecraft.voting.votes.VoteResults$VoteCounts
- net.minecraft.voting.votes.VotingMaterial
- net.minecraft.voting.votes.VotingMaterial$2
- net.minecraft.voting.votes.VotingMaterial$CustomCost
- net.minecraft.voting.votes.VotingMaterial$Type$1
- net.minecraft.voting.votes.VotingMaterial$Type$3
- net.minecraft.voting.votes.VotingMaterial$Type$5
- net.minecraft.voting.votes.VotingMaterial$VotingResource
- net.minecraft.voting.votes.VotingMaterial$VotingResource$2
+ net.minecraft.world.entity.ai.attributes.Attribute
- net.minecraft.world.entity.ai.attributes.AttributeInstance
+ net.minecraft.world.entity.ai.attributes.AttributeMap
- net.minecraft.world.entity.ai.attributes.AttributeModifier
+ net.minecraft.world.entity.ai.attributes.AttributeModifier$Operation
- net.minecraft.world.entity.ai.attributes.Attributes
- net.minecraft.world.entity.ai.attributes.AttributeSupplier
+ net.minecraft.world.entity.ai.attributes.AttributeSupplier$Builder
+ net.minecraft.world.entity.ai.attributes.DefaultAttributes
+ net.minecraft.world.entity.ai.attributes.package-info
- net.minecraft.world.entity.ai.attributes.RangedAttribute
- net.minecraft.world.entity.ai.behavior.AcquirePoi
+ net.minecraft.world.entity.ai.behavior.AcquirePoi$JitteredLinearRetry
- net.minecraft.world.entity.ai.behavior.AnimalMakeLove
+ net.minecraft.world.entity.ai.behavior.AnimalPanic
- net.minecraft.world.entity.ai.behavior.AssignProfessionFromJobSite
+ net.minecraft.world.entity.ai.behavior.BabyFollowAdult
- net.minecraft.world.entity.ai.behavior.BackUpIfTooClose
+ net.minecraft.world.entity.ai.behavior.BecomePassiveIfMemoryPresent
- net.minecraft.world.entity.ai.behavior.Behavior
+ net.minecraft.world.entity.ai.behavior.Behavior$Status
- net.minecraft.world.entity.ai.behavior.BehaviorControl
+ net.minecraft.world.entity.ai.behavior.BehaviorUtils
- net.minecraft.world.entity.ai.behavior.BlockPosTracker
+ net.minecraft.world.entity.ai.behavior.CelebrateVillagersSurvivedRaid
- net.minecraft.world.entity.ai.behavior.CopyMemoryWithExpiry
+ net.minecraft.world.entity.ai.behavior.CountDownCooldownTicks
- net.minecraft.world.entity.ai.behavior.Croak
+ net.minecraft.world.entity.ai.behavior.CrossbowAttack
- net.minecraft.world.entity.ai.behavior.CrossbowAttack$CrossbowState
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$1
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Constant
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Constant$1
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$1
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$2
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$3
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$4
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$5
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$Mu
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Mu
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$PureMemory
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$PureMemory$1
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$TriggerWithResult
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$TriggerWrapper
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$TriggerWrapper$1
- net.minecraft.world.entity.ai.behavior.declarative.MemoryAccessor
+ net.minecraft.world.entity.ai.behavior.declarative.MemoryCondition
- net.minecraft.world.entity.ai.behavior.declarative.MemoryCondition$Absent
+ net.minecraft.world.entity.ai.behavior.declarative.MemoryCondition$Present
- net.minecraft.world.entity.ai.behavior.declarative.MemoryCondition$Registered
- net.minecraft.world.entity.ai.behavior.declarative.package-info
+ net.minecraft.world.entity.ai.behavior.declarative.Trigger
+ net.minecraft.world.entity.ai.behavior.DismountOrSkipMounting
- net.minecraft.world.entity.ai.behavior.DoNothing
+ net.minecraft.world.entity.ai.behavior.EntityTracker
- net.minecraft.world.entity.ai.behavior.EraseMemoryIf
+ net.minecraft.world.entity.ai.behavior.FollowTemptation
- net.minecraft.world.entity.ai.behavior.GateBehavior
+ net.minecraft.world.entity.ai.behavior.GateBehavior$OrderPolicy
- net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy
+ net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$1
- net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$2
+ net.minecraft.world.entity.ai.behavior.GiveGiftToHero
- net.minecraft.world.entity.ai.behavior.GoAndGiveItemsToTarget
+ net.minecraft.world.entity.ai.behavior.GoToClosestVillage
- net.minecraft.world.entity.ai.behavior.GoToPotentialJobSite
+ net.minecraft.world.entity.ai.behavior.GoToTargetLocation
- net.minecraft.world.entity.ai.behavior.GoToWantedItem
+ net.minecraft.world.entity.ai.behavior.HarvestFarmland
- net.minecraft.world.entity.ai.behavior.InsideBrownianWalk
+ net.minecraft.world.entity.ai.behavior.InteractWith
- net.minecraft.world.entity.ai.behavior.InteractWithDoor
+ net.minecraft.world.entity.ai.behavior.JumpOnBed
- net.minecraft.world.entity.ai.behavior.LocateHidingPlace
+ net.minecraft.world.entity.ai.behavior.LongJumpMidJump
- net.minecraft.world.entity.ai.behavior.LongJumpToPreferredBlock
+ net.minecraft.world.entity.ai.behavior.LongJumpToRandomPos
- net.minecraft.world.entity.ai.behavior.LongJumpToRandomPos$PossibleJump
+ net.minecraft.world.entity.ai.behavior.LookAndFollowTradingPlayerSink
- net.minecraft.world.entity.ai.behavior.LookAtTargetSink
+ net.minecraft.world.entity.ai.behavior.MeleeAttack
- net.minecraft.world.entity.ai.behavior.Mount
+ net.minecraft.world.entity.ai.behavior.MoveToSkySeeingSpot
- net.minecraft.world.entity.ai.behavior.MoveToTargetSink
+ net.minecraft.world.entity.ai.behavior.OneShot
+ net.minecraft.world.entity.ai.behavior.package-info
- net.minecraft.world.entity.ai.behavior.PlayTagWithOtherKids
+ net.minecraft.world.entity.ai.behavior.PoiCompetitorScan
- net.minecraft.world.entity.ai.behavior.PositionTracker
+ net.minecraft.world.entity.ai.behavior.PrepareRamNearestTarget
- net.minecraft.world.entity.ai.behavior.PrepareRamNearestTarget$RamCandidate
+ net.minecraft.world.entity.ai.behavior.RamTarget
- net.minecraft.world.entity.ai.behavior.RandomLookAround
+ net.minecraft.world.entity.ai.behavior.RandomStroll
- net.minecraft.world.entity.ai.behavior.ReactToBell
+ net.minecraft.world.entity.ai.behavior.ResetProfession
- net.minecraft.world.entity.ai.behavior.ResetRaidStatus
+ net.minecraft.world.entity.ai.behavior.RingBell
- net.minecraft.world.entity.ai.behavior.RunOne
+ net.minecraft.world.entity.ai.behavior.SetClosestHomeAsWalkTarget
- net.minecraft.world.entity.ai.behavior.SetEntityLookTarget
+ net.minecraft.world.entity.ai.behavior.SetEntityLookTargetSometimes
- net.minecraft.world.entity.ai.behavior.SetEntityLookTargetSometimes$Ticker
+ net.minecraft.world.entity.ai.behavior.SetHiddenState
- net.minecraft.world.entity.ai.behavior.SetLookAndInteract
+ net.minecraft.world.entity.ai.behavior.SetRaidStatus
- net.minecraft.world.entity.ai.behavior.SetWalkTargetAwayFrom
+ net.minecraft.world.entity.ai.behavior.SetWalkTargetFromAttackTargetIfTargetOutOfReach
- net.minecraft.world.entity.ai.behavior.SetWalkTargetFromBlockMemory
+ net.minecraft.world.entity.ai.behavior.SetWalkTargetFromLookTarget
- net.minecraft.world.entity.ai.behavior.ShowTradesToPlayer
+ net.minecraft.world.entity.ai.behavior.ShufflingList
- net.minecraft.world.entity.ai.behavior.ShufflingList$WeightedEntry
+ net.minecraft.world.entity.ai.behavior.ShufflingList$WeightedEntry$1
- net.minecraft.world.entity.ai.behavior.SleepInBed
+ net.minecraft.world.entity.ai.behavior.SocializeAtBell
- net.minecraft.world.entity.ai.behavior.StartAttacking
+ net.minecraft.world.entity.ai.behavior.StartCelebratingIfTargetDead
- net.minecraft.world.entity.ai.behavior.StayCloseToTarget
+ net.minecraft.world.entity.ai.behavior.StopAttackingIfTargetInvalid
- net.minecraft.world.entity.ai.behavior.StopBeingAngryIfTargetDead
+ net.minecraft.world.entity.ai.behavior.StrollAroundPoi
- net.minecraft.world.entity.ai.behavior.StrollToPoi
+ net.minecraft.world.entity.ai.behavior.StrollToPoiList
- net.minecraft.world.entity.ai.behavior.Swim
+ net.minecraft.world.entity.ai.behavior.TradeWithVillager
- net.minecraft.world.entity.ai.behavior.TriggerGate
+ net.minecraft.world.entity.ai.behavior.TryFindLand
- net.minecraft.world.entity.ai.behavior.TryFindLandNearWater
+ net.minecraft.world.entity.ai.behavior.TryFindWater
- net.minecraft.world.entity.ai.behavior.TryLaySpawnOnWaterNearLand
+ net.minecraft.world.entity.ai.behavior.UpdateActivityFromSchedule
- net.minecraft.world.entity.ai.behavior.UseBonemeal
+ net.minecraft.world.entity.ai.behavior.ValidateNearbyPoi
- net.minecraft.world.entity.ai.behavior.VillageBoundRandomStroll
+ net.minecraft.world.entity.ai.behavior.VillagerCalmDown
- net.minecraft.world.entity.ai.behavior.VillagerGoalPackages
+ net.minecraft.world.entity.ai.behavior.VillagerMakeLove
- net.minecraft.world.entity.ai.behavior.VillagerPanicTrigger
+ net.minecraft.world.entity.ai.behavior.WakeUp
- net.minecraft.world.entity.ai.behavior.warden.Digging
+ net.minecraft.world.entity.ai.behavior.warden.Emerging
- net.minecraft.world.entity.ai.behavior.warden.ForceUnmount
+ net.minecraft.world.entity.ai.behavior.warden.package-info
+ net.minecraft.world.entity.ai.behavior.warden.Roar
- net.minecraft.world.entity.ai.behavior.warden.SetRoarTarget
+ net.minecraft.world.entity.ai.behavior.warden.SetWardenLookTarget
- net.minecraft.world.entity.ai.behavior.warden.Sniffing
+ net.minecraft.world.entity.ai.behavior.warden.SonicBoom
- net.minecraft.world.entity.ai.behavior.warden.TryToSniff
- net.minecraft.world.entity.ai.behavior.WorkAtComposter
+ net.minecraft.world.entity.ai.behavior.WorkAtPoi
- net.minecraft.world.entity.ai.behavior.YieldJobSite
+ net.minecraft.world.entity.ai.Brain
- net.minecraft.world.entity.ai.Brain$1
+ net.minecraft.world.entity.ai.Brain$MemoryValue
- net.minecraft.world.entity.ai.Brain$Provider
- net.minecraft.world.entity.ai.control.BodyRotationControl
+ net.minecraft.world.entity.ai.control.Control
- net.minecraft.world.entity.ai.control.FlyingMoveControl
+ net.minecraft.world.entity.ai.control.JumpControl
- net.minecraft.world.entity.ai.control.LookControl
+ net.minecraft.world.entity.ai.control.MoveControl
- net.minecraft.world.entity.ai.control.MoveControl$Operation
+ net.minecraft.world.entity.ai.control.package-info
+ net.minecraft.world.entity.ai.control.SmoothSwimmingLookControl
- net.minecraft.world.entity.ai.control.SmoothSwimmingMoveControl
- net.minecraft.world.entity.ai.goal.AvoidEntityGoal
+ net.minecraft.world.entity.ai.goal.BegGoal
- net.minecraft.world.entity.ai.goal.BoatGoals
+ net.minecraft.world.entity.ai.goal.BreakDoorGoal
- net.minecraft.world.entity.ai.goal.BreathAirGoal
+ net.minecraft.world.entity.ai.goal.BreedGoal
- net.minecraft.world.entity.ai.goal.CatLieOnBedGoal
+ net.minecraft.world.entity.ai.goal.CatSitOnBlockGoal
- net.minecraft.world.entity.ai.goal.ClimbOnTopOfPowderSnowGoal
+ net.minecraft.world.entity.ai.goal.DolphinJumpGoal
- net.minecraft.world.entity.ai.goal.DoorInteractGoal
+ net.minecraft.world.entity.ai.goal.EatBlockGoal
- net.minecraft.world.entity.ai.goal.FleeSunGoal
+ net.minecraft.world.entity.ai.goal.FloatGoal
- net.minecraft.world.entity.ai.goal.FollowBoatGoal
+ net.minecraft.world.entity.ai.goal.FollowFlockLeaderGoal
- net.minecraft.world.entity.ai.goal.FollowMobGoal
+ net.minecraft.world.entity.ai.goal.FollowOwnerGoal
- net.minecraft.world.entity.ai.goal.FollowParentGoal
+ net.minecraft.world.entity.ai.goal.Goal
- net.minecraft.world.entity.ai.goal.Goal$Flag
+ net.minecraft.world.entity.ai.goal.GoalSelector
- net.minecraft.world.entity.ai.goal.GoalSelector$1
+ net.minecraft.world.entity.ai.goal.GoalSelector$2
- net.minecraft.world.entity.ai.goal.GolemRandomStrollInVillageGoal
+ net.minecraft.world.entity.ai.goal.InteractGoal
- net.minecraft.world.entity.ai.goal.JumpGoal
+ net.minecraft.world.entity.ai.goal.LandOnOwnersShoulderGoal
- net.minecraft.world.entity.ai.goal.LeapAtTargetGoal
+ net.minecraft.world.entity.ai.goal.LlamaFollowCaravanGoal
- net.minecraft.world.entity.ai.goal.LookAtPlayerGoal
+ net.minecraft.world.entity.ai.goal.LookAtTradingPlayerGoal
- net.minecraft.world.entity.ai.goal.MeleeAttackGoal
+ net.minecraft.world.entity.ai.goal.MoveBackToVillageGoal
- net.minecraft.world.entity.ai.goal.MoveThroughVillageGoal
+ net.minecraft.world.entity.ai.goal.MoveToBlockGoal
- net.minecraft.world.entity.ai.goal.MoveTowardsRestrictionGoal
+ net.minecraft.world.entity.ai.goal.MoveTowardsTargetGoal
- net.minecraft.world.entity.ai.goal.OcelotAttackGoal
+ net.minecraft.world.entity.ai.goal.OfferFlowerGoal
- net.minecraft.world.entity.ai.goal.OpenDoorGoal
+ net.minecraft.world.entity.ai.goal.package-info
+ net.minecraft.world.entity.ai.goal.PanicGoal
- net.minecraft.world.entity.ai.goal.PathfindToRaidGoal
+ net.minecraft.world.entity.ai.goal.RandomLookAroundGoal
- net.minecraft.world.entity.ai.goal.RandomStandGoal
+ net.minecraft.world.entity.ai.goal.RandomStrollGoal
- net.minecraft.world.entity.ai.goal.RandomSwimmingGoal
+ net.minecraft.world.entity.ai.goal.RangedAttackGoal
- net.minecraft.world.entity.ai.goal.RangedBowAttackGoal
+ net.minecraft.world.entity.ai.goal.RangedCrossbowAttackGoal
- net.minecraft.world.entity.ai.goal.RangedCrossbowAttackGoal$CrossbowState
+ net.minecraft.world.entity.ai.goal.RemoveBlockGoal
- net.minecraft.world.entity.ai.goal.RestrictSunGoal
+ net.minecraft.world.entity.ai.goal.RunAroundLikeCrazyGoal
- net.minecraft.world.entity.ai.goal.SitWhenOrderedToGoal
+ net.minecraft.world.entity.ai.goal.StrollThroughVillageGoal
- net.minecraft.world.entity.ai.goal.SwellGoal
- net.minecraft.world.entity.ai.goal.target.DefendVillageTargetGoal
+ net.minecraft.world.entity.ai.goal.target.HurtByTargetGoal
- net.minecraft.world.entity.ai.goal.target.NearestAttackableTargetGoal
+ net.minecraft.world.entity.ai.goal.target.NearestAttackableWitchTargetGoal
- net.minecraft.world.entity.ai.goal.target.NearestHealableRaiderTargetGoal
+ net.minecraft.world.entity.ai.goal.target.NonTameRandomTargetGoal
- net.minecraft.world.entity.ai.goal.target.OwnerHurtByTargetGoal
+ net.minecraft.world.entity.ai.goal.target.OwnerHurtTargetGoal
- net.minecraft.world.entity.ai.goal.target.package-info
- net.minecraft.world.entity.ai.goal.target.ResetUniversalAngerTargetGoal
+ net.minecraft.world.entity.ai.goal.target.TargetGoal
+ net.minecraft.world.entity.ai.goal.TemptGoal
- net.minecraft.world.entity.ai.goal.TradeWithPlayerGoal
+ net.minecraft.world.entity.ai.goal.TryFindWaterGoal
- net.minecraft.world.entity.ai.goal.UseItemGoal
+ net.minecraft.world.entity.ai.goal.WaterAvoidingRandomFlyingGoal
- net.minecraft.world.entity.ai.goal.WaterAvoidingRandomStrollGoal
+ net.minecraft.world.entity.ai.goal.WrappedGoal
- net.minecraft.world.entity.ai.goal.ZombieAttackGoal
+ net.minecraft.world.entity.ai.gossip.GossipContainer
- net.minecraft.world.entity.ai.gossip.GossipContainer$EntityGossips
+ net.minecraft.world.entity.ai.gossip.GossipContainer$GossipEntry
- net.minecraft.world.entity.ai.gossip.GossipType
+ net.minecraft.world.entity.ai.gossip.package-info
- net.minecraft.world.entity.ai.memory.ExpirableValue
+ net.minecraft.world.entity.ai.memory.MemoryModuleType
- net.minecraft.world.entity.ai.memory.MemoryStatus
+ net.minecraft.world.entity.ai.memory.NearestVisibleLivingEntities
+ net.minecraft.world.entity.ai.memory.package-info
- net.minecraft.world.entity.ai.memory.WalkTarget
- net.minecraft.world.entity.ai.navigation.AmphibiousPathNavigation
+ net.minecraft.world.entity.ai.navigation.FlyingPathNavigation
- net.minecraft.world.entity.ai.navigation.GroundPathNavigation
- net.minecraft.world.entity.ai.navigation.package-info
+ net.minecraft.world.entity.ai.navigation.PathNavigation
- net.minecraft.world.entity.ai.navigation.WallClimberNavigation
+ net.minecraft.world.entity.ai.navigation.WaterBoundPathNavigation
+ net.minecraft.world.entity.ai.package-info
- net.minecraft.world.entity.ai.sensing.AdultSensor
+ net.minecraft.world.entity.ai.sensing.AxolotlAttackablesSensor
- net.minecraft.world.entity.ai.sensing.DummySensor
+ net.minecraft.world.entity.ai.sensing.FrogAttackablesSensor
- net.minecraft.world.entity.ai.sensing.GolemSensor
+ net.minecraft.world.entity.ai.sensing.HoglinSpecificSensor
- net.minecraft.world.entity.ai.sensing.HurtBySensor
+ net.minecraft.world.entity.ai.sensing.IsInWaterSensor
- net.minecraft.world.entity.ai.sensing.NearestBedSensor
+ net.minecraft.world.entity.ai.sensing.NearestItemSensor
- net.minecraft.world.entity.ai.sensing.NearestLivingEntitySensor
+ net.minecraft.world.entity.ai.sensing.NearestVisibleLivingEntitySensor
+ net.minecraft.world.entity.ai.sensing.package-info
- net.minecraft.world.entity.ai.sensing.PiglinBruteSpecificSensor
+ net.minecraft.world.entity.ai.sensing.PiglinSpecificSensor
- net.minecraft.world.entity.ai.sensing.PlayerSensor
+ net.minecraft.world.entity.ai.sensing.SecondaryPoiSensor
- net.minecraft.world.entity.ai.sensing.Sensing
+ net.minecraft.world.entity.ai.sensing.Sensor
- net.minecraft.world.entity.ai.sensing.SensorType
+ net.minecraft.world.entity.ai.sensing.TemptingSensor
- net.minecraft.world.entity.ai.sensing.VillagerBabiesSensor
+ net.minecraft.world.entity.ai.sensing.VillagerHostilesSensor
- net.minecraft.world.entity.ai.sensing.WardenEntitySensor
+ net.minecraft.world.entity.ai.targeting.package-info
- net.minecraft.world.entity.ai.targeting.TargetingConditions
- net.minecraft.world.entity.ai.util.AirAndWaterRandomPos
+ net.minecraft.world.entity.ai.util.AirRandomPos
- net.minecraft.world.entity.ai.util.DefaultRandomPos
+ net.minecraft.world.entity.ai.util.GoalUtils
- net.minecraft.world.entity.ai.util.HoverRandomPos
+ net.minecraft.world.entity.ai.util.LandRandomPos
+ net.minecraft.world.entity.ai.util.package-info
- net.minecraft.world.entity.ai.util.RandomPos
- net.minecraft.world.entity.ai.village.package-info
- net.minecraft.world.entity.ai.village.poi.package-info
+ net.minecraft.world.entity.ai.village.poi.PoiManager
- net.minecraft.world.entity.ai.village.poi.PoiManager$DistanceTracker
+ net.minecraft.world.entity.ai.village.poi.PoiManager$Occupancy
- net.minecraft.world.entity.ai.village.poi.PoiRecord
+ net.minecraft.world.entity.ai.village.poi.PoiSection
- net.minecraft.world.entity.ai.village.poi.PoiType
+ net.minecraft.world.entity.ai.village.poi.PoiTypes
- net.minecraft.world.entity.ai.village.ReputationEventType
+ net.minecraft.world.entity.ai.village.ReputationEventType$1
- net.minecraft.world.entity.ai.village.VillageSiege
+ net.minecraft.world.entity.ai.village.VillageSiege$State
+ net.minecraft.world.entity.ambient.AmbientCreature
- net.minecraft.world.entity.ambient.Bat
+ net.minecraft.world.entity.ambient.package-info
- net.minecraft.world.entity.animal.AbstractFish
+ net.minecraft.world.entity.animal.AbstractFish$FishMoveControl
- net.minecraft.world.entity.animal.AbstractFish$FishSwimGoal
+ net.minecraft.world.entity.animal.AbstractGolem
- net.minecraft.world.entity.animal.AbstractSchoolingFish
+ net.minecraft.world.entity.animal.AbstractSchoolingFish$SchoolSpawnGroupData
- net.minecraft.world.entity.animal.Animal
+ net.minecraft.world.entity.animal.Bee
- net.minecraft.world.entity.animal.Bee$1
+ net.minecraft.world.entity.animal.Bee$BaseBeeGoal
- net.minecraft.world.entity.animal.Bee$BeeAttackGoal
+ net.minecraft.world.entity.animal.Bee$BeeBecomeAngryTargetGoal
- net.minecraft.world.entity.animal.Bee$BeeEnterHiveGoal
+ net.minecraft.world.entity.animal.Bee$BeeGoToHiveGoal
- net.minecraft.world.entity.animal.Bee$BeeGoToKnownFlowerGoal
+ net.minecraft.world.entity.animal.Bee$BeeGrowCropGoal
- net.minecraft.world.entity.animal.Bee$BeeHurtByOtherGoal
+ net.minecraft.world.entity.animal.Bee$BeeLocateHiveGoal
- net.minecraft.world.entity.animal.Bee$BeeLookControl
+ net.minecraft.world.entity.animal.Bee$BeePollinateGoal
- net.minecraft.world.entity.animal.Bee$BeeWanderGoal
- net.minecraft.world.entity.animal.Bee$FloatDownGoal
- net.minecraft.world.entity.animal.MoonCow
- net.minecraft.world.entity.Display$KeyFrame
+ net.minecraft.world.entity.Display$LinearFloatInterpolator
- net.minecraft.world.entity.Display$LinearIntInterpolator
- net.minecraft.world.entity.Display$StencilDisplay$StencilRenderState
- net.minecraft.world.entity.Entity$InPortal
+ net.minecraft.world.entity.Entity$MoveFunction
- net.minecraft.world.entity.Entity$MovementEmission
+ net.minecraft.world.entity.Entity$RemovalReason
- net.minecraft.world.entity.EntityDimensions
+ net.minecraft.world.entity.EntityEvent
- net.minecraft.world.entity.EntitySelector
+ net.minecraft.world.entity.EntitySelector$MobCanWearArmorEntitySelector
- net.minecraft.world.entity.EntityType
+ net.minecraft.world.entity.EntityType$1
- net.minecraft.world.entity.EntityType$Builder
+ net.minecraft.world.entity.EntityType$EntityFactory
- net.minecraft.world.entity.EquipmentSlot
+ net.minecraft.world.entity.EquipmentSlot$Type
- net.minecraft.world.entity.ExperienceOrb
+ net.minecraft.world.entity.FlyingMob
- net.minecraft.world.entity.GlowSquid
+ net.minecraft.world.entity.HasCustomInventoryScreen
- net.minecraft.world.entity.HumanoidArm
+ net.minecraft.world.entity.Interaction
- net.minecraft.world.entity.Interaction$PlayerAction
+ net.minecraft.world.entity.item.package-info
- net.minecraft.world.entity.item.PrimedTnt
+ net.minecraft.world.entity.ItemBasedSteering
- net.minecraft.world.entity.ItemSteerable
+ net.minecraft.world.entity.LerpingModel
- net.minecraft.world.entity.LightningBolt
+ net.minecraft.world.entity.LivingEntity
- net.minecraft.world.entity.LivingEntity$1
+ net.minecraft.world.entity.LivingEntity$Fallsounds
- net.minecraft.world.entity.Marker
+ net.minecraft.world.entity.Mob
- net.minecraft.world.entity.Mob$1
+ net.minecraft.world.entity.MobCategory
- net.minecraft.world.entity.MobSpawnType
+ net.minecraft.world.entity.MobType
- net.minecraft.world.entity.monster.AbstractIllager
+ net.minecraft.world.entity.monster.AbstractIllager$IllagerArmPose
- net.minecraft.world.entity.monster.AbstractIllager$RaiderOpenDoorGoal
+ net.minecraft.world.entity.monster.AbstractSkeleton
- net.minecraft.world.entity.monster.AbstractSkeleton$1
+ net.minecraft.world.entity.monster.Blaze
- net.minecraft.world.entity.monster.Blaze$BlazeAttackGoal
+ net.minecraft.world.entity.monster.CaveSpider
- net.minecraft.world.entity.monster.Creeper
+ net.minecraft.world.entity.monster.CrossbowAttackMob
- net.minecraft.world.entity.monster.Drowned
+ net.minecraft.world.entity.monster.Drowned$DrownedAttackGoal
- net.minecraft.world.entity.monster.Drowned$DrownedGoToBeachGoal
+ net.minecraft.world.entity.monster.Drowned$DrownedGoToWaterGoal
- net.minecraft.world.entity.monster.Drowned$DrownedMoveControl
+ net.minecraft.world.entity.monster.Drowned$DrownedSwimUpGoal
- net.minecraft.world.entity.monster.Drowned$DrownedTridentAttackGoal
+ net.minecraft.world.entity.monster.ElderGuardian
- net.minecraft.world.entity.monster.EnderMan
+ net.minecraft.world.entity.monster.EnderMan$EndermanFreezeWhenLookedAt
- net.minecraft.world.entity.monster.EnderMan$EndermanLeaveBlockGoal
+ net.minecraft.world.entity.monster.EnderMan$EndermanLookForPlayerGoal
- net.minecraft.world.entity.monster.EnderMan$EndermanTakeBlockGoal
+ net.minecraft.world.entity.monster.Endermite
- net.minecraft.world.entity.monster.Enemy
+ net.minecraft.world.entity.monster.Evoker
- net.minecraft.world.entity.monster.Evoker$EvokerAttackSpellGoal
+ net.minecraft.world.entity.monster.Evoker$EvokerCastingSpellGoal
- net.minecraft.world.entity.monster.Evoker$EvokerSummonSpellGoal
+ net.minecraft.world.entity.monster.Evoker$EvokerWololoSpellGoal
- net.minecraft.world.entity.monster.Ghast
+ net.minecraft.world.entity.monster.Ghast$GhastLookGoal
- net.minecraft.world.entity.monster.Ghast$GhastMoveControl
+ net.minecraft.world.entity.monster.Ghast$GhastShootFireballGoal
- net.minecraft.world.entity.monster.Ghast$RandomFloatAroundGoal
+ net.minecraft.world.entity.monster.Giant
- net.minecraft.world.entity.monster.Guardian
+ net.minecraft.world.entity.monster.Guardian$GuardianAttackGoal
- net.minecraft.world.entity.monster.Guardian$GuardianAttackSelector
+ net.minecraft.world.entity.monster.Guardian$GuardianMoveControl
- net.minecraft.world.entity.monster.hoglin.Hoglin
+ net.minecraft.world.entity.monster.hoglin.HoglinAi
- net.minecraft.world.entity.monster.hoglin.HoglinBase
+ net.minecraft.world.entity.monster.hoglin.package-info
- net.minecraft.world.entity.monster.Husk
+ net.minecraft.world.entity.monster.Illusioner
- net.minecraft.world.entity.monster.Illusioner$IllusionerBlindnessSpellGoal
+ net.minecraft.world.entity.monster.Illusioner$IllusionerMirrorSpellGoal
- net.minecraft.world.entity.monster.MagmaCube
+ net.minecraft.world.entity.monster.Monster
- net.minecraft.world.entity.monster.package-info
- net.minecraft.world.entity.monster.PatrollingMonster
+ net.minecraft.world.entity.monster.PatrollingMonster$LongDistancePatrolGoal
- net.minecraft.world.entity.monster.Phantom
+ net.minecraft.world.entity.monster.Phantom$AttackPhase
- net.minecraft.world.entity.monster.Phantom$PhantomAttackPlayerTargetGoal
+ net.minecraft.world.entity.monster.Phantom$PhantomAttackStrategyGoal
- net.minecraft.world.entity.monster.Phantom$PhantomBodyRotationControl
+ net.minecraft.world.entity.monster.Phantom$PhantomCircleAroundAnchorGoal
- net.minecraft.world.entity.monster.Phantom$PhantomLookControl
+ net.minecraft.world.entity.monster.Phantom$PhantomMoveControl
- net.minecraft.world.entity.monster.Phantom$PhantomMoveTargetGoal
+ net.minecraft.world.entity.monster.Phantom$PhantomSweepAttackGoal
+ net.minecraft.world.entity.monster.piglin.AbstractPiglin
+ net.minecraft.world.entity.monster.piglin.package-info
- net.minecraft.world.entity.monster.piglin.Piglin
+ net.minecraft.world.entity.monster.piglin.PiglinAi
- net.minecraft.world.entity.monster.piglin.PiglinArmPose
+ net.minecraft.world.entity.monster.piglin.PiglinBrute
- net.minecraft.world.entity.monster.piglin.PiglinBruteAi
+ net.minecraft.world.entity.monster.piglin.RememberIfHoglinWasKilled
- net.minecraft.world.entity.monster.piglin.StartAdmiringItemIfSeen
+ net.minecraft.world.entity.monster.piglin.StartHuntingHoglin
- net.minecraft.world.entity.monster.piglin.StopAdmiringIfItemTooFarAway
+ net.minecraft.world.entity.monster.piglin.StopAdmiringIfTiredOfTryingToReachItem
- net.minecraft.world.entity.monster.piglin.StopHoldingItemIfNoLongerAdmiring
- net.minecraft.world.entity.monster.Pillager
+ net.minecraft.world.entity.monster.RangedAttackMob
- net.minecraft.world.entity.monster.Ravager
+ net.minecraft.world.entity.monster.Ravager$RavagerMeleeAttackGoal
- net.minecraft.world.entity.monster.RayTracing
- net.minecraft.world.entity.monster.warden.AngerLevel
+ net.minecraft.world.entity.monster.warden.AngerManagement
- net.minecraft.world.entity.monster.warden.AngerManagement$1
+ net.minecraft.world.entity.monster.warden.AngerManagement$Sorter
- net.minecraft.world.entity.monster.warden.package-info
- net.minecraft.world.entity.monster.warden.Warden
+ net.minecraft.world.entity.monster.warden.Warden$1
- net.minecraft.world.entity.monster.warden.Warden$1$1
+ net.minecraft.world.entity.monster.warden.Warden$2
- net.minecraft.world.entity.monster.warden.WardenAi
+ net.minecraft.world.entity.monster.warden.WardenSpawnTracker
- net.minecraft.world.entity.monster.Zombie$ZombieAttackTurtleEggGoal
+ net.minecraft.world.entity.monster.Zombie$ZombieGroupData
- net.minecraft.world.entity.monster.ZombieVillager
+ net.minecraft.world.entity.monster.ZombifiedPiglin
- net.minecraft.world.entity.MoverType
+ net.minecraft.world.entity.NeutralMob
+ net.minecraft.world.entity.npc.AbstractVillager
- net.minecraft.world.entity.npc.CatSpawner
+ net.minecraft.world.entity.npc.ClientSideMerchant
- net.minecraft.world.entity.npc.InventoryCarrier
+ net.minecraft.world.entity.npc.Npc
- net.minecraft.world.entity.npc.package-info
- net.minecraft.world.entity.npc.Villager
+ net.minecraft.world.entity.npc.VillagerData
- net.minecraft.world.entity.npc.VillagerDataHolder
+ net.minecraft.world.entity.npc.VillagerProfession
- net.minecraft.world.entity.npc.VillagerTrades
+ net.minecraft.world.entity.npc.VillagerTrades$DyedArmorForEmeralds
- net.minecraft.world.entity.npc.VillagerTrades$EmeraldForItems
+ net.minecraft.world.entity.npc.VillagerTrades$EmeraldsForVillagerTypeItem
- net.minecraft.world.entity.npc.VillagerTrades$EnchantBookForEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$EnchantedItemForEmeralds
- net.minecraft.world.entity.npc.VillagerTrades$ItemListing
+ net.minecraft.world.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
- net.minecraft.world.entity.npc.VillagerTrades$ItemsForEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$SuspiciousStewForEmerald
- net.minecraft.world.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$TreasureMapForEmeralds
- net.minecraft.world.entity.npc.VillagerType
+ net.minecraft.world.entity.npc.WanderingTrader
- net.minecraft.world.entity.npc.WanderingTrader$WanderToPositionGoal
+ net.minecraft.world.entity.npc.WanderingTraderSpawner
- net.minecraft.world.entity.OwnableEntity
+ net.minecraft.world.entity.package-info
+ net.minecraft.world.entity.PathfinderMob
- net.minecraft.world.entity.player.Abilities
+ net.minecraft.world.entity.player.ChatVisiblity
- net.minecraft.world.entity.player.Inventory
+ net.minecraft.world.entity.player.package-info
+ net.minecraft.world.entity.player.Player
- net.minecraft.world.entity.player.Player$1
+ net.minecraft.world.entity.player.Player$BedSleepingProblem
- net.minecraft.world.entity.player.PlayerModelPart
+ net.minecraft.world.entity.player.ProfileKeyPair
- net.minecraft.world.entity.player.ProfilePublicKey
+ net.minecraft.world.entity.player.ProfilePublicKey$Data
- net.minecraft.world.entity.player.ProfilePublicKey$ValidationException
+ net.minecraft.world.entity.player.StackedContents
- net.minecraft.world.entity.player.StackedContents$RecipePicker
- net.minecraft.world.entity.PlayerRideable
+ net.minecraft.world.entity.PlayerRideableJumping
- net.minecraft.world.entity.Pose
+ net.minecraft.world.entity.PowerableMob
- net.minecraft.world.entity.projectile.AbstractArrow
+ net.minecraft.world.entity.projectile.AbstractArrow$1
- net.minecraft.world.entity.projectile.AbstractArrow$Pickup
+ net.minecraft.world.entity.projectile.AbstractHurtingProjectile
- net.minecraft.world.entity.projectile.Arrow
+ net.minecraft.world.entity.projectile.DragonFireball
- net.minecraft.world.entity.projectile.EvokerFangs
+ net.minecraft.world.entity.projectile.EyeOfEnder
- net.minecraft.world.entity.projectile.Fireball
+ net.minecraft.world.entity.projectile.FireworkRocketEntity
- net.minecraft.world.entity.projectile.FishingHook
+ net.minecraft.world.entity.projectile.FishingHook$1
- net.minecraft.world.entity.projectile.FishingHook$FishHookState
+ net.minecraft.world.entity.projectile.FishingHook$OpenWaterType
- net.minecraft.world.entity.projectile.ItemSupplier
+ net.minecraft.world.entity.projectile.LargeFireball
- net.minecraft.world.entity.projectile.LlamaSpit
+ net.minecraft.world.entity.projectile.package-info
+ net.minecraft.world.entity.projectile.Projectile
- net.minecraft.world.entity.projectile.ProjectileUtil
+ net.minecraft.world.entity.projectile.ShulkerBullet
- net.minecraft.world.entity.projectile.SmallFireball
+ net.minecraft.world.entity.projectile.Snowball
- net.minecraft.world.entity.projectile.SpectralArrow
+ net.minecraft.world.entity.projectile.ThrowableItemProjectile
- net.minecraft.world.entity.projectile.ThrowableProjectile
+ net.minecraft.world.entity.projectile.ThrownEgg
- net.minecraft.world.entity.projectile.ThrownEnderpearl
+ net.minecraft.world.entity.projectile.ThrownExperienceBottle
- net.minecraft.world.entity.projectile.ThrownPotion
+ net.minecraft.world.entity.projectile.ThrownTrident
- net.minecraft.world.entity.projectile.WitherSkull
- net.minecraft.world.entity.raid.package-info
- net.minecraft.world.entity.raid.Raid
+ net.minecraft.world.entity.raid.Raid$1
+ net.minecraft.world.entity.raid.Raid$RaiderType
- net.minecraft.world.entity.raid.Raid$RaidStatus
- net.minecraft.world.entity.raid.Raider
+ net.minecraft.world.entity.raid.Raider$HoldGroundAttackGoal
- net.minecraft.world.entity.raid.Raider$ObtainRaidLeaderBannerGoal
+ net.minecraft.world.entity.raid.Raider$RaiderCelebration
- net.minecraft.world.entity.raid.Raider$RaiderMoveThroughVillageGoal
+ net.minecraft.world.entity.raid.Raids
- net.minecraft.world.entity.RelativeMovement
+ net.minecraft.world.entity.ReputationEventHandler
- net.minecraft.world.entity.RiderShieldingMount
+ net.minecraft.world.entity.Saddleable
+ net.minecraft.world.entity.schedule.Activity
- net.minecraft.world.entity.schedule.Keyframe
+ net.minecraft.world.entity.schedule.package-info
+ net.minecraft.world.entity.schedule.Schedule
- net.minecraft.world.entity.schedule.ScheduleBuilder
+ net.minecraft.world.entity.schedule.ScheduleBuilder$ActivityTransition
- net.minecraft.world.entity.schedule.Timeline
- net.minecraft.world.entity.Shearable
+ net.minecraft.world.entity.SlotAccess
- net.minecraft.world.entity.SlotAccess$1
+ net.minecraft.world.entity.SlotAccess$2
- net.minecraft.world.entity.SlotAccess$3
+ net.minecraft.world.entity.SpawnGroupData
- net.minecraft.world.entity.SpawnPlacements
+ net.minecraft.world.entity.SpawnPlacements$Data
- net.minecraft.world.entity.SpawnPlacements$SpawnPredicate
+ net.minecraft.world.entity.SpawnPlacements$Type
- net.minecraft.world.entity.TamableAnimal
+ net.minecraft.world.entity.Targeting
- net.minecraft.world.entity.TraceableEntity
- net.minecraft.world.entity.transform.EntityTransform
- net.minecraft.world.entity.transform.EntityTransformType$TypeModifier
- net.minecraft.world.entity.transform.package-info
+ net.minecraft.world.entity.VariantHolder
- net.minecraft.world.entity.WalkAnimationState
- net.minecraft.world.food.package-info
+ net.minecraft.world.inventory.AbstractContainerMenu
- net.minecraft.world.inventory.AbstractContainerMenu$1
+ net.minecraft.world.inventory.AbstractFurnaceMenu
- net.minecraft.world.inventory.AnvilMenu
+ net.minecraft.world.inventory.AnvilMenu$1
- net.minecraft.world.inventory.BeaconMenu
+ net.minecraft.world.inventory.BeaconMenu$1
- net.minecraft.world.inventory.BeaconMenu$PaymentSlot
+ net.minecraft.world.inventory.BlastFurnaceMenu
- net.minecraft.world.inventory.BrewingStandMenu
+ net.minecraft.world.inventory.BrewingStandMenu$FuelSlot
- net.minecraft.world.inventory.BrewingStandMenu$IngredientsSlot
+ net.minecraft.world.inventory.BrewingStandMenu$PotionSlot
- net.minecraft.world.inventory.CartographyTableMenu
+ net.minecraft.world.inventory.CartographyTableMenu$1
- net.minecraft.world.inventory.CartographyTableMenu$2
+ net.minecraft.world.inventory.CartographyTableMenu$3
- net.minecraft.world.inventory.CartographyTableMenu$4
+ net.minecraft.world.inventory.CartographyTableMenu$5
- net.minecraft.world.inventory.ChestMenu
+ net.minecraft.world.inventory.ClickAction
- net.minecraft.world.inventory.ClickType
+ net.minecraft.world.inventory.ContainerData
- net.minecraft.world.inventory.ContainerLevelAccess
+ net.minecraft.world.inventory.ContainerLevelAccess$1
- net.minecraft.world.inventory.ContainerLevelAccess$2
+ net.minecraft.world.inventory.ContainerListener
- net.minecraft.world.inventory.ContainerSynchronizer
+ net.minecraft.world.inventory.CraftingContainer
- net.minecraft.world.inventory.CraftingMenu
+ net.minecraft.world.inventory.DataSlot
- net.minecraft.world.inventory.DataSlot$1
+ net.minecraft.world.inventory.DataSlot$2
- net.minecraft.world.inventory.DataSlot$3
+ net.minecraft.world.inventory.DispenserMenu
- net.minecraft.world.inventory.EnchantmentMenu
+ net.minecraft.world.inventory.EnchantmentMenu$1
- net.minecraft.world.inventory.EnchantmentMenu$2
+ net.minecraft.world.inventory.EnchantmentMenu$3
- net.minecraft.world.inventory.FurnaceFuelSlot
+ net.minecraft.world.inventory.FurnaceMenu
- net.minecraft.world.inventory.FurnaceResultSlot
+ net.minecraft.world.inventory.GrindstoneMenu
- net.minecraft.world.inventory.GrindstoneMenu$1
+ net.minecraft.world.inventory.GrindstoneMenu$2
- net.minecraft.world.inventory.GrindstoneMenu$3
+ net.minecraft.world.inventory.GrindstoneMenu$4
- net.minecraft.world.inventory.HopperMenu
+ net.minecraft.world.inventory.HorseInventoryMenu
- net.minecraft.world.inventory.HorseInventoryMenu$1
+ net.minecraft.world.inventory.HorseInventoryMenu$2
- net.minecraft.world.inventory.InventoryMenu
+ net.minecraft.world.inventory.InventoryMenu$1
- net.minecraft.world.inventory.InventoryMenu$2
+ net.minecraft.world.inventory.ItemCombinerMenu
- net.minecraft.world.inventory.ItemCombinerMenu$1
+ net.minecraft.world.inventory.ItemCombinerMenu$2
- net.minecraft.world.inventory.ItemCombinerMenu$3
+ net.minecraft.world.inventory.ItemCombinerMenuSlotDefinition
- net.minecraft.world.inventory.ItemCombinerMenuSlotDefinition$Builder
+ net.minecraft.world.inventory.ItemCombinerMenuSlotDefinition$SlotDefinition
- net.minecraft.world.inventory.LecternMenu
+ net.minecraft.world.inventory.LecternMenu$1
- net.minecraft.world.inventory.LoomMenu
+ net.minecraft.world.inventory.LoomMenu$1
- net.minecraft.world.inventory.LoomMenu$2
+ net.minecraft.world.inventory.LoomMenu$3
- net.minecraft.world.inventory.LoomMenu$4
+ net.minecraft.world.inventory.LoomMenu$5
- net.minecraft.world.inventory.LoomMenu$6
+ net.minecraft.world.inventory.MenuConstructor
- net.minecraft.world.inventory.MenuType
+ net.minecraft.world.inventory.MenuType$MenuSupplier
- net.minecraft.world.inventory.MerchantContainer
+ net.minecraft.world.inventory.MerchantMenu
- net.minecraft.world.inventory.MerchantResultSlot
+ net.minecraft.world.inventory.package-info
+ net.minecraft.world.inventory.PlayerEnderChestContainer
- net.minecraft.world.inventory.RecipeBookMenu
+ net.minecraft.world.inventory.RecipeBookType
- net.minecraft.world.inventory.RecipeHolder
+ net.minecraft.world.inventory.ResultContainer
- net.minecraft.world.inventory.ResultSlot
+ net.minecraft.world.inventory.ShulkerBoxMenu
- net.minecraft.world.inventory.ShulkerBoxSlot
+ net.minecraft.world.inventory.SimpleContainerData
- net.minecraft.world.inventory.Slot
+ net.minecraft.world.inventory.SmithingMenu
- net.minecraft.world.inventory.SmokerMenu
+ net.minecraft.world.inventory.StackedContentsCompatible
- net.minecraft.world.inventory.StonecutterMenu
+ net.minecraft.world.inventory.StonecutterMenu$1
- net.minecraft.world.inventory.StonecutterMenu$2
- net.minecraft.world.inventory.tooltip.BundleTooltip
- net.minecraft.world.inventory.tooltip.package-info
+ net.minecraft.world.inventory.tooltip.TooltipComponent
+ net.minecraft.world.item.AdventureModeCheck
- net.minecraft.world.item.AirItem
+ net.minecraft.world.item.ArmorItem
- net.minecraft.world.item.ArmorItem$1
+ net.minecraft.world.item.ArmorItem$Type
- net.minecraft.world.item.ArmorMaterial
+ net.minecraft.world.item.ArmorMaterials
- net.minecraft.world.item.ArmorStandItem
+ net.minecraft.world.item.ArrowItem
- net.minecraft.world.item.AxeItem
+ net.minecraft.world.item.BannerItem
- net.minecraft.world.item.BannerPatternItem
+ net.minecraft.world.item.BedItem
- net.minecraft.world.item.BlockItem
+ net.minecraft.world.item.BoatItem
- net.minecraft.world.item.BoneMealItem
+ net.minecraft.world.item.BookItem
- net.minecraft.world.item.BottleItem
- net.minecraft.world.item.BottleOfVoidItem
+ net.minecraft.world.item.BowItem
- net.minecraft.world.item.BowlFoodItem
+ net.minecraft.world.item.BrushItem
- net.minecraft.world.item.BrushItem$1
+ net.minecraft.world.item.BrushItem$DustParticlesDelta
- net.minecraft.world.item.BucketItem
+ net.minecraft.world.item.BundleItem
- net.minecraft.world.item.ChorusFruitItem
+ net.minecraft.world.item.CompassItem
- net.minecraft.world.item.ComplexItem
+ net.minecraft.world.item.context.package-info
- net.minecraft.world.item.context.UseOnContext
- net.minecraft.world.item.crafting.AbstractCookingRecipe
+ net.minecraft.world.item.crafting.ArmorDyeRecipe
- net.minecraft.world.item.crafting.BannerDuplicateRecipe
+ net.minecraft.world.item.crafting.BlastingRecipe
- net.minecraft.world.item.crafting.BookCloningRecipe
+ net.minecraft.world.item.crafting.CampfireCookingRecipe
- net.minecraft.world.item.crafting.CookingBookCategory
+ net.minecraft.world.item.crafting.CraftingBookCategory
- net.minecraft.world.item.crafting.CraftingRecipe
+ net.minecraft.world.item.crafting.CustomRecipe
- net.minecraft.world.item.crafting.DecoratedPotRecipe
+ net.minecraft.world.item.crafting.package-info
- net.minecraft.world.item.crafting.Recipe
+ net.minecraft.world.item.crafting.RecipeManager
- net.minecraft.world.item.crafting.RecipeManager$1
+ net.minecraft.world.item.crafting.RecipeManager$CachedCheck
- net.minecraft.world.item.crafting.RecipeSerializer
+ net.minecraft.world.item.crafting.RecipeType
- net.minecraft.world.item.crafting.RecipeType$1
+ net.minecraft.world.item.crafting.RepairItemRecipe
- net.minecraft.world.item.crafting.ShapedRecipe
+ net.minecraft.world.item.crafting.ShapedRecipe$Serializer
- net.minecraft.world.item.crafting.ShapelessRecipe
+ net.minecraft.world.item.crafting.ShapelessRecipe$Serializer
- net.minecraft.world.item.crafting.ShieldDecorationRecipe
+ net.minecraft.world.item.crafting.ShulkerBoxColoring
- net.minecraft.world.item.crafting.SimpleCookingSerializer
+ net.minecraft.world.item.crafting.SimpleCookingSerializer$CookieBaker
- net.minecraft.world.item.crafting.SimpleCraftingRecipeSerializer
+ net.minecraft.world.item.crafting.SimpleCraftingRecipeSerializer$Factory
- net.minecraft.world.item.crafting.SingleItemRecipe
+ net.minecraft.world.item.crafting.SingleItemRecipe$Serializer
- net.minecraft.world.item.crafting.SingleItemRecipe$Serializer$SingleItemMaker
+ net.minecraft.world.item.crafting.SmeltingRecipe
- net.minecraft.world.item.crafting.SmithingRecipe
+ net.minecraft.world.item.crafting.SmithingTransformRecipe
- net.minecraft.world.item.crafting.SmithingTransformRecipe$Serializer
+ net.minecraft.world.item.crafting.SmithingTrimRecipe
- net.minecraft.world.item.crafting.SmithingTrimRecipe$Serializer
+ net.minecraft.world.item.crafting.SmokingRecipe
- net.minecraft.world.item.crafting.StonecutterRecipe
+ net.minecraft.world.item.crafting.SuspiciousStewRecipe
- net.minecraft.world.item.crafting.TippedArrowRecipe
+ net.minecraft.world.item.CreativeModeTab
- net.minecraft.world.item.CreativeModeTab$1
+ net.minecraft.world.item.CreativeModeTab$Builder
- net.minecraft.world.item.CreativeModeTab$DisplayItemsGenerator
+ net.minecraft.world.item.CreativeModeTab$ItemDisplayBuilder
- net.minecraft.world.item.CreativeModeTab$ItemDisplayParameters
+ net.minecraft.world.item.CreativeModeTab$Output
- net.minecraft.world.item.CreativeModeTab$Row
+ net.minecraft.world.item.CreativeModeTab$TabVisibility
- net.minecraft.world.item.CreativeModeTab$Type
+ net.minecraft.world.item.CreativeModeTabs
- net.minecraft.world.item.CrossbowItem
+ net.minecraft.world.item.DebugStickItem
- net.minecraft.world.item.DiggerItem
+ net.minecraft.world.item.DiscFragmentItem
- net.minecraft.world.item.DispensibleContainerItem
+ net.minecraft.world.item.DoubleHighBlockItem
- net.minecraft.world.item.DupeHackItem
- net.minecraft.world.item.EmeraldItem
+ net.minecraft.world.item.EmptyMapItem
- net.minecraft.world.item.EnchantedBookItem
+ net.minecraft.world.item.EnchantedGoldenAppleItem
- net.minecraft.world.item.enchantment.ArrowDamageEnchantment
+ net.minecraft.world.item.enchantment.ArrowFireEnchantment
- net.minecraft.world.item.enchantment.ArrowInfiniteEnchantment
+ net.minecraft.world.item.enchantment.ArrowKnockbackEnchantment
- net.minecraft.world.item.enchantment.ArrowPiercingEnchantment
+ net.minecraft.world.item.enchantment.BindingCurseEnchantment
- net.minecraft.world.item.enchantment.DamageEnchantment
+ net.minecraft.world.item.enchantment.DigDurabilityEnchantment
- net.minecraft.world.item.enchantment.DiggingEnchantment
+ net.minecraft.world.item.enchantment.Enchantment
- net.minecraft.world.item.enchantment.Enchantment$Rarity
+ net.minecraft.world.item.enchantment.EnchantmentCategory
- net.minecraft.world.item.enchantment.EnchantmentCategory$1
+ net.minecraft.world.item.enchantment.EnchantmentCategory$10
- net.minecraft.world.item.enchantment.EnchantmentCategory$11
+ net.minecraft.world.item.enchantment.EnchantmentCategory$12
- net.minecraft.world.item.enchantment.EnchantmentCategory$13
+ net.minecraft.world.item.enchantment.EnchantmentCategory$14
- net.minecraft.world.item.enchantment.EnchantmentCategory$2
+ net.minecraft.world.item.enchantment.EnchantmentCategory$3
- net.minecraft.world.item.enchantment.EnchantmentCategory$4
+ net.minecraft.world.item.enchantment.EnchantmentCategory$5
- net.minecraft.world.item.enchantment.EnchantmentCategory$6
+ net.minecraft.world.item.enchantment.EnchantmentCategory$7
- net.minecraft.world.item.enchantment.EnchantmentCategory$8
+ net.minecraft.world.item.enchantment.EnchantmentCategory$9
- net.minecraft.world.item.enchantment.EnchantmentHelper
+ net.minecraft.world.item.enchantment.EnchantmentHelper$EnchantmentVisitor
- net.minecraft.world.item.enchantment.EnchantmentInstance
+ net.minecraft.world.item.enchantment.Enchantments
- net.minecraft.world.item.enchantment.FireAspectEnchantment
+ net.minecraft.world.item.enchantment.FishingSpeedEnchantment
- net.minecraft.world.item.enchantment.FrostWalkerEnchantment
+ net.minecraft.world.item.enchantment.KnockbackEnchantment
- net.minecraft.world.item.enchantment.LootBonusEnchantment
+ net.minecraft.world.item.enchantment.MendingEnchantment
- net.minecraft.world.item.enchantment.MultiShotEnchantment
+ net.minecraft.world.item.enchantment.OxygenEnchantment
+ net.minecraft.world.item.enchantment.package-info
- net.minecraft.world.item.enchantment.ProtectionEnchantment
+ net.minecraft.world.item.enchantment.ProtectionEnchantment$Type
- net.minecraft.world.item.enchantment.QuickChargeEnchantment
+ net.minecraft.world.item.enchantment.SoulSpeedEnchantment
- net.minecraft.world.item.enchantment.SweepingEdgeEnchantment
+ net.minecraft.world.item.enchantment.SwiftSneakEnchantment
- net.minecraft.world.item.enchantment.ThornsEnchantment
+ net.minecraft.world.item.enchantment.TridentChannelingEnchantment
- net.minecraft.world.item.enchantment.TridentImpalerEnchantment
+ net.minecraft.world.item.enchantment.TridentLoyaltyEnchantment
- net.minecraft.world.item.enchantment.TridentRiptideEnchantment
+ net.minecraft.world.item.enchantment.UntouchingEnchantment
- net.minecraft.world.item.enchantment.VanishingCurseEnchantment
+ net.minecraft.world.item.enchantment.WaterWalkerEnchantment
- net.minecraft.world.item.enchantment.WaterWorkerEnchantment
- net.minecraft.world.item.EndCrystalItem
+ net.minecraft.world.item.EnderEyeItem
- net.minecraft.world.item.EnderpearlItem
+ net.minecraft.world.item.Equipable
- net.minecraft.world.item.ExperienceBottleItem
+ net.minecraft.world.item.FireChargeItem
- net.minecraft.world.item.FireworkRocketItem
+ net.minecraft.world.item.FireworkRocketItem$Shape
- net.minecraft.world.item.FireworkStarItem
+ net.minecraft.world.item.FishingRodItem
- net.minecraft.world.item.FlintAndSteelItem
+ net.minecraft.world.item.FoodOnAStickItem
- net.minecraft.world.item.GameMasterBlockItem
+ net.minecraft.world.item.GlowInkSacItem
- net.minecraft.world.item.HangingEntityItem
+ net.minecraft.world.item.HangingSignItem
- net.minecraft.world.item.HoeItem
+ net.minecraft.world.item.HoneyBottleItem
- net.minecraft.world.item.HoneycombItem
+ net.minecraft.world.item.HorseArmorItem
- net.minecraft.world.item.InkSacItem
+ net.minecraft.world.item.Instrument
- net.minecraft.world.item.InstrumentItem
+ net.minecraft.world.item.Instruments
- net.minecraft.world.item.Item
+ net.minecraft.world.item.Item$1
- net.minecraft.world.item.Item$Properties
+ net.minecraft.world.item.ItemCooldowns
- net.minecraft.world.item.ItemCooldowns$CooldownInstance
+ net.minecraft.world.item.ItemDisplayContext
- net.minecraft.world.item.ItemFrameItem
+ net.minecraft.world.item.ItemNameBlockItem
+ net.minecraft.world.item.Items
- net.minecraft.world.item.ItemStack
+ net.minecraft.world.item.ItemStack$TooltipPart
- net.minecraft.world.item.ItemStackLinkedSet
+ net.minecraft.world.item.ItemStackLinkedSet$1
- net.minecraft.world.item.ItemUtils
- net.minecraft.world.item.KnowledgeBookItem
+ net.minecraft.world.item.LeadItem
- net.minecraft.world.item.LingeringPotionItem
+ net.minecraft.world.item.MapItem
- net.minecraft.world.item.MilkBucketItem
+ net.minecraft.world.item.MinecartItem
- net.minecraft.world.item.MinecartItem$1
+ net.minecraft.world.item.MobBucketItem
- net.minecraft.world.item.NameItem
- net.minecraft.world.item.package-info
- net.minecraft.world.item.SplashPotionItem
+ net.minecraft.world.item.SpyglassItem
- net.minecraft.world.item.StandingAndWallBlockItem
+ net.minecraft.world.item.SuspiciousStewItem
- net.minecraft.world.item.SwordItem
+ net.minecraft.world.item.trading.Merchant
- net.minecraft.world.item.trading.MerchantOffer
+ net.minecraft.world.item.trading.MerchantOffers
- net.minecraft.world.item.trading.package-info
+ net.minecraft.world.level.BaseCommandBlock
- net.minecraft.world.level.BaseSpawner
- net.minecraft.world.level.biome.AmbientAdditionsSettings
+ net.minecraft.world.level.biome.AmbientMoodSettings
- net.minecraft.world.level.biome.AmbientParticleSettings
+ net.minecraft.world.level.biome.Biome
- net.minecraft.world.level.biome.Biome$1
+ net.minecraft.world.level.biome.Biome$BiomeBuilder
- net.minecraft.world.level.biome.Biome$ClimateSettings
+ net.minecraft.world.level.biome.Biome$Precipitation
- net.minecraft.world.level.biome.Biome$TemperatureModifier
+ net.minecraft.world.level.biome.Biome$TemperatureModifier$1
- net.minecraft.world.level.biome.Biome$TemperatureModifier$2
+ net.minecraft.world.level.biome.BiomeGenerationSettings
- net.minecraft.world.level.biome.BiomeGenerationSettings$Builder
+ net.minecraft.world.level.biome.BiomeGenerationSettings$PlainBuilder
- net.minecraft.world.level.biome.BiomeManager
+ net.minecraft.world.level.biome.BiomeManager$NoiseBiomeSource
- net.minecraft.world.level.biome.BiomeResolver
+ net.minecraft.world.level.biome.Biomes
+ net.minecraft.world.level.biome.BiomeSource
- net.minecraft.world.level.biome.BiomeSources
+ net.minecraft.world.level.biome.BiomeSpecialEffects
- net.minecraft.world.level.biome.BiomeSpecialEffects$Builder
+ net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier
- net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$1
+ net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$2
- net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$3
- net.minecraft.world.level.biome.CheckerboardColumnBiomeSource
+ net.minecraft.world.level.biome.Climate
- net.minecraft.world.level.biome.Climate$DistanceMetric
+ net.minecraft.world.level.biome.Climate$Parameter
- net.minecraft.world.level.biome.Climate$ParameterList
+ net.minecraft.world.level.biome.Climate$ParameterPoint
- net.minecraft.world.level.biome.Climate$RTree
+ net.minecraft.world.level.biome.Climate$RTree$Leaf
- net.minecraft.world.level.biome.Climate$RTree$Node
+ net.minecraft.world.level.biome.Climate$RTree$SubTree
- net.minecraft.world.level.biome.Climate$Sampler
+ net.minecraft.world.level.biome.Climate$SpawnFinder
- net.minecraft.world.level.biome.Climate$SpawnFinder$Result
+ net.minecraft.world.level.biome.Climate$TargetPoint
- net.minecraft.world.level.biome.FeatureSorter
+ net.minecraft.world.level.biome.FeatureSorter$1FeatureData
- net.minecraft.world.level.biome.FeatureSorter$StepFeatureData
+ net.minecraft.world.level.biome.FixedBiomeSource
- net.minecraft.world.level.biome.MobSpawnSettings
+ net.minecraft.world.level.biome.MobSpawnSettings$Builder
- net.minecraft.world.level.biome.MobSpawnSettings$MobSpawnCost
+ net.minecraft.world.level.biome.MobSpawnSettings$SpawnerData
- net.minecraft.world.level.biome.MultiNoiseBiomeSource
+ net.minecraft.world.level.biome.MultiNoiseBiomeSourceParameterList
- net.minecraft.world.level.biome.MultiNoiseBiomeSourceParameterList$Preset
+ net.minecraft.world.level.biome.MultiNoiseBiomeSourceParameterList$Preset$1
- net.minecraft.world.level.biome.MultiNoiseBiomeSourceParameterList$Preset$2
+ net.minecraft.world.level.biome.MultiNoiseBiomeSourceParameterList$Preset$SourceProvider
- net.minecraft.world.level.biome.MultiNoiseBiomeSourceParameterLists
+ net.minecraft.world.level.biome.OverworldBiomeBuilder
- net.minecraft.world.level.biome.TheEndBiomeSource
- net.minecraft.world.level.block.CherryLeavesBlock
+ net.minecraft.world.level.block.ChestBlock
- net.minecraft.world.level.block.ChestBlock$1
+ net.minecraft.world.level.block.ChestBlock$2
- net.minecraft.world.level.block.ChestBlock$2$1
+ net.minecraft.world.level.block.ChestBlock$3
- net.minecraft.world.level.block.ChestBlock$4
+ net.minecraft.world.level.block.ChiseledBookShelfBlock
- net.minecraft.world.level.block.ChiseledBookShelfBlock$1
+ net.minecraft.world.level.block.ChorusFlowerBlock
- net.minecraft.world.level.block.ChorusPlantBlock
+ net.minecraft.world.level.block.CocoaBlock
- net.minecraft.world.level.block.CocoaBlock$1
+ net.minecraft.world.level.block.CommandBlock
- net.minecraft.world.level.block.ComparatorBlock
+ net.minecraft.world.level.block.ComposterBlock
- net.minecraft.world.level.block.ComposterBlock$EmptyContainer
+ net.minecraft.world.level.block.ComposterBlock$InputContainer
- net.minecraft.world.level.block.ComposterBlock$OutputContainer
+ net.minecraft.world.level.block.ConcretePowderBlock
- net.minecraft.world.level.block.ConduitBlock
- net.minecraft.world.level.block.Fallable
+ net.minecraft.world.level.block.FallingBlock
- net.minecraft.world.level.block.FarmBlock
+ net.minecraft.world.level.block.FenceBlock
- net.minecraft.world.level.block.FenceGateBlock
+ net.minecraft.world.level.block.FenceGateBlock$1
- net.minecraft.world.level.block.FilledCopperSinkBlock
- net.minecraft.world.level.block.PackedAirBlock
- net.minecraft.world.level.block.PlaceBlock
+ net.minecraft.world.level.block.PlayerHeadBlock
- net.minecraft.world.level.block.PlayerWallHeadBlock
+ net.minecraft.world.level.block.PointedDripstoneBlock
- net.minecraft.world.level.block.PointedDripstoneBlock$FluidInfo
+ net.minecraft.world.level.block.PotatoBlock
- net.minecraft.world.level.block.PowderSnowBlock
+ net.minecraft.world.level.block.PowderSnowCauldronBlock
- net.minecraft.world.level.block.PoweredBlock
+ net.minecraft.world.level.block.PoweredRailBlock
- net.minecraft.world.level.block.PoweredRailBlock$1
+ net.minecraft.world.level.block.PressurePlateBlock
- net.minecraft.world.level.block.PressurePlateBlock$1
+ net.minecraft.world.level.block.PressurePlateBlock$Sensitivity
- net.minecraft.world.level.block.PumpkinBlock
+ net.minecraft.world.level.block.RailBlock
- net.minecraft.world.level.block.RailBlock$1
+ net.minecraft.world.level.block.RailState
- net.minecraft.world.level.block.RailState$1
- net.minecraft.world.level.block.RedstoneLampBlock
+ net.minecraft.world.level.block.RedStoneOreBlock
+ net.minecraft.world.level.block.RedstoneTorchBlock
- net.minecraft.world.level.block.RedstoneTorchBlock$Toggle
+ net.minecraft.world.level.block.RedstoneWallTorchBlock
- net.minecraft.world.level.block.RedStoneWireBlock
+ net.minecraft.world.level.block.RedStoneWireBlock$1
- net.minecraft.world.level.block.RenderShape
+ net.minecraft.world.level.block.RepeaterBlock
- net.minecraft.world.level.block.RespawnAnchorBlock
+ net.minecraft.world.level.block.RespawnAnchorBlock$1
- net.minecraft.world.level.block.RodBlock
+ net.minecraft.world.level.block.RodBlock$1
- net.minecraft.world.level.block.RootedDirtBlock
+ net.minecraft.world.level.block.RootsBlock
- net.minecraft.world.level.block.RotatedPillarBlock
+ net.minecraft.world.level.block.RotatedPillarBlock$1
- net.minecraft.world.level.block.Rotation
+ net.minecraft.world.level.block.Rotation$1
- net.minecraft.world.level.block.SandBlock
+ net.minecraft.world.level.block.SaplingBlock
- net.minecraft.world.level.block.ScaffoldingBlock
+ net.minecraft.world.level.block.SculkBehaviour
- net.minecraft.world.level.block.SculkBehaviour$1
+ net.minecraft.world.level.block.SculkBlock
- net.minecraft.world.level.block.SculkCatalystBlock
+ net.minecraft.world.level.block.SculkSensorBlock
- net.minecraft.world.level.block.SculkShriekerBlock
+ net.minecraft.world.level.block.SculkSpreader
- net.minecraft.world.level.block.SculkSpreader$ChargeCursor
+ net.minecraft.world.level.block.SculkVeinBlock
- net.minecraft.world.level.block.SculkVeinBlock$SculkVeinSpreaderConfig
- net.minecraft.world.level.block.SeagrassBlock
+ net.minecraft.world.level.block.SeaPickleBlock
+ net.minecraft.world.level.block.ShulkerBoxBlock
- net.minecraft.world.level.block.ShulkerBoxBlock$1
+ net.minecraft.world.level.block.SignBlock
- net.minecraft.world.level.block.SimpleWaterloggedBlock
+ net.minecraft.world.level.block.SkullBlock
- net.minecraft.world.level.block.SkullBlock$Type
+ net.minecraft.world.level.block.SkullBlock$Types
- net.minecraft.world.level.block.SlabBlock
+ net.minecraft.world.level.block.SlabBlock$1
- net.minecraft.world.level.block.SlimeBlock
+ net.minecraft.world.level.block.SmallDripleafBlock
- net.minecraft.world.level.block.SmithingTableBlock
+ net.minecraft.world.level.block.SmokerBlock
- net.minecraft.world.level.block.SnifferEggBlock
+ net.minecraft.world.level.block.SnowLayerBlock
- net.minecraft.world.level.block.SnowLayerBlock$1
+ net.minecraft.world.level.block.SnowyDirtBlock
- net.minecraft.world.level.block.SoulFireBlock
+ net.minecraft.world.level.block.SoulSandBlock
- net.minecraft.world.level.block.SoundType
+ net.minecraft.world.level.block.SpawnerBlock
- net.minecraft.world.level.block.SpleavesBlock
+ net.minecraft.world.level.BlockAndTintGetter
- net.minecraft.world.level.BlockCollisions
+ net.minecraft.world.level.BlockEventData
- net.minecraft.world.level.BlockGetter
+ net.minecraft.world.level.ChunkPos
- net.minecraft.world.level.ChunkPos$1
+ net.minecraft.world.level.ClipBlockStateContext
- net.minecraft.world.level.ClipContext
+ net.minecraft.world.level.ClipContext$Block
- net.minecraft.world.level.ClipContext$Fluid
+ net.minecraft.world.level.ClipContext$ShapeGetter
- net.minecraft.world.level.CollisionGetter
+ net.minecraft.world.level.ColorResolver
- net.minecraft.world.level.CommonLevelAccessor
+ net.minecraft.world.level.CustomSpawner
- net.minecraft.world.level.DataPackConfig
+ net.minecraft.world.level.EmptyBlockGetter
- net.minecraft.world.level.EntityBasedExplosionDamageCalculator
+ net.minecraft.world.level.EntityGetter
- net.minecraft.world.level.Explosion
+ net.minecraft.world.level.Explosion$BlockInteraction
- net.minecraft.world.level.ExplosionDamageCalculator
+ net.minecraft.world.level.FoliageColor
- net.minecraft.world.level.ForcedChunksSavedData
+ net.minecraft.world.level.GameRules
- net.minecraft.world.level.GameRules$BooleanValue
+ net.minecraft.world.level.GameRules$Category
- net.minecraft.world.level.GameRules$GameRuleTypeVisitor
+ net.minecraft.world.level.GameRules$IntegerValue
- net.minecraft.world.level.GameRules$Key
+ net.minecraft.world.level.GameRules$Type
- net.minecraft.world.level.GameRules$Value
+ net.minecraft.world.level.GameRules$VisitorCaller
- net.minecraft.world.level.GameType
+ net.minecraft.world.level.GrassColor
- net.minecraft.world.level.ItemLike
+ net.minecraft.world.level.Level
- net.minecraft.world.level.Level$1
+ net.minecraft.world.level.Level$2
- net.minecraft.world.level.Level$ExplosionInteraction
+ net.minecraft.world.level.LevelAccessor
+ net.minecraft.world.level.levelgen.blending.Blender
- net.minecraft.world.level.levelgen.blending.Blender$1
+ net.minecraft.world.level.levelgen.blending.Blender$BlendingOutput
- net.minecraft.world.level.levelgen.blending.Blender$CellValueGetter
+ net.minecraft.world.level.levelgen.blending.Blender$DistanceGetter
- net.minecraft.world.level.levelgen.blending.BlendingData
+ net.minecraft.world.level.levelgen.blending.BlendingData$BiomeConsumer
- net.minecraft.world.level.levelgen.blending.BlendingData$DensityConsumer
+ net.minecraft.world.level.levelgen.blending.BlendingData$HeightConsumer
- net.minecraft.world.level.levelgen.blending.package-info
+ net.minecraft.world.level.levelgen.blockpredicates.AllOfPredicate
- net.minecraft.world.level.levelgen.blockpredicates.AnyOfPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.BlockPredicate
- net.minecraft.world.level.levelgen.blockpredicates.BlockPredicateType
+ net.minecraft.world.level.levelgen.blockpredicates.CombiningPredicate
- net.minecraft.world.level.levelgen.blockpredicates.HasSturdyFacePredicate
+ net.minecraft.world.level.levelgen.blockpredicates.InsideWorldBoundsPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.MatchingBlocksPredicate
- net.minecraft.world.level.levelgen.blockpredicates.MatchingBlockTagPredicate
- net.minecraft.world.level.levelgen.blockpredicates.MatchingFluidsPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.NotPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.package-info
- net.minecraft.world.level.levelgen.blockpredicates.ReplaceablePredicate
+ net.minecraft.world.level.levelgen.blockpredicates.SolidPredicate
- net.minecraft.world.level.levelgen.blockpredicates.StateTestingPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.TrueBlockPredicate
- net.minecraft.world.level.levelgen.blockpredicates.WouldSurvivePredicate
- net.minecraft.world.level.levelgen.carver.CanyonCarverConfiguration
+ net.minecraft.world.level.levelgen.carver.CanyonCarverConfiguration$CanyonShapeConfiguration
- net.minecraft.world.level.levelgen.carver.CanyonWorldCarver
+ net.minecraft.world.level.levelgen.carver.CarverConfiguration
- net.minecraft.world.level.levelgen.carver.CarverDebugSettings
+ net.minecraft.world.level.levelgen.carver.CarvingContext
- net.minecraft.world.level.levelgen.carver.CaveCarverConfiguration
+ net.minecraft.world.level.levelgen.carver.CaveWorldCarver
- net.minecraft.world.level.levelgen.carver.ConfiguredWorldCarver
+ net.minecraft.world.level.levelgen.carver.NetherWorldCarver
- net.minecraft.world.level.levelgen.carver.package-info
- net.minecraft.world.level.levelgen.carver.WorldCarver
+ net.minecraft.world.level.levelgen.carver.WorldCarver$CarveSkipChecker
+ net.minecraft.world.level.levelgen.feature.AbstractHugeMushroomFeature
- net.minecraft.world.level.levelgen.feature.BambooFeature
+ net.minecraft.world.level.levelgen.feature.BasaltColumnsFeature
- net.minecraft.world.level.levelgen.feature.BasaltPillarFeature
+ net.minecraft.world.level.levelgen.feature.BlockBlobFeature
- net.minecraft.world.level.levelgen.feature.BlockColumnFeature
+ net.minecraft.world.level.levelgen.feature.BlockPileFeature
- net.minecraft.world.level.levelgen.feature.BlueIceFeature
+ net.minecraft.world.level.levelgen.feature.BonusChestFeature
- net.minecraft.world.level.levelgen.feature.ChorusPlantFeature
- net.minecraft.world.level.levelgen.feature.configurations.BlockColumnConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.BlockColumnConfiguration$Layer
- net.minecraft.world.level.levelgen.feature.configurations.BlockPileConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.BlockStateConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.ColumnFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.CountConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.CraterFeatureConfiguration
+ net.minecraft.world.level.levelgen.feature.ConfiguredFeature
- net.minecraft.world.level.levelgen.feature.CoralClawFeature
+ net.minecraft.world.level.levelgen.feature.CoralFeature
- net.minecraft.world.level.levelgen.feature.CoralMushroomFeature
+ net.minecraft.world.level.levelgen.feature.CoralTreeFeature
- net.minecraft.world.level.levelgen.feature.CraterFeature
- net.minecraft.world.level.levelgen.feature.LunarBaseFeature
+ net.minecraft.world.level.levelgen.feature.MonsterRoomFeature
- net.minecraft.world.level.levelgen.feature.MultifaceGrowthFeature
+ net.minecraft.world.level.levelgen.feature.NetherForestVegetationFeature
- net.minecraft.world.level.levelgen.feature.NoOpFeature
+ net.minecraft.world.level.levelgen.feature.OreFeature
- net.minecraft.world.level.levelgen.feature.PointedDripstoneFeature
+ net.minecraft.world.level.levelgen.feature.RandomBooleanSelectorFeature
- net.minecraft.world.level.levelgen.feature.RandomPatchFeature
+ net.minecraft.world.level.levelgen.feature.RandomSelectorFeature
- net.minecraft.world.level.levelgen.feature.ReplaceBlobsFeature
+ net.minecraft.world.level.levelgen.feature.ReplaceBlockFeature
- net.minecraft.world.level.levelgen.feature.RootSystemFeature
+ net.minecraft.world.level.levelgen.feature.ScatteredOreFeature
- net.minecraft.world.level.levelgen.feature.SculkPatchFeature
- net.minecraft.world.level.levelgen.feature.SeagrassFeature
+ net.minecraft.world.level.levelgen.feature.SeaPickleFeature
+ net.minecraft.world.level.levelgen.feature.SimpleBlockFeature
- net.minecraft.world.level.levelgen.feature.SimpleRandomSelectorFeature
+ net.minecraft.world.level.levelgen.feature.SnowAndFreezeFeature
- net.minecraft.world.level.levelgen.feature.SpikeFeature
+ net.minecraft.world.level.levelgen.feature.SpikeFeature$EndSpike
- net.minecraft.world.level.levelgen.feature.SpikeFeature$SpikeCacheLoader
+ net.minecraft.world.level.levelgen.feature.SpringFeature
- net.minecraft.world.level.levelgen.feature.TreeFeature
+ net.minecraft.world.level.levelgen.feature.TreeFeature$1
- net.minecraft.world.level.levelgen.feature.TwistingVinesFeature
+ net.minecraft.world.level.levelgen.feature.UnderwaterMagmaFeature
- net.minecraft.world.level.levelgen.feature.VegetationPatchFeature
+ net.minecraft.world.level.levelgen.feature.VinesFeature
- net.minecraft.world.level.levelgen.feature.VoidStartPlatformFeature
+ net.minecraft.world.level.levelgen.feature.WaterloggedVegetationPatchFeature
- net.minecraft.world.level.levelgen.feature.WeepingVinesFeature
+ net.minecraft.world.level.levelgen.feature.WeightedPlacedFeature
- net.minecraft.world.level.levelgen.MoonBaseBuilder
- net.minecraft.world.level.levelgen.MoonBaseBuilder$Branch
+ net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator
- net.minecraft.world.level.levelgen.NoiseChunk
+ net.minecraft.world.level.levelgen.NoiseChunk$1
- net.minecraft.world.level.levelgen.NoiseChunk$2
+ net.minecraft.world.level.levelgen.NoiseChunk$BlendAlpha
- net.minecraft.world.level.levelgen.NoiseChunk$BlendOffset
+ net.minecraft.world.level.levelgen.NoiseChunk$BlockStateFiller
- net.minecraft.world.level.levelgen.NoiseChunk$Cache2D
+ net.minecraft.world.level.levelgen.NoiseChunk$CacheAllInCell
- net.minecraft.world.level.levelgen.NoiseChunk$CacheOnce
+ net.minecraft.world.level.levelgen.NoiseChunk$FlatCache
- net.minecraft.world.level.levelgen.NoiseChunk$NoiseChunkDensityFunction
+ net.minecraft.world.level.levelgen.NoiseChunk$NoiseInterpolator
- net.minecraft.world.level.levelgen.NoiseGeneratorSettings
+ net.minecraft.world.level.levelgen.NoiseRouter
- net.minecraft.world.level.levelgen.NoiseRouterData
+ net.minecraft.world.level.levelgen.NoiseRouterData$QuantizedSpaghettiRarity
+ net.minecraft.world.level.levelgen.Noises
- net.minecraft.world.level.levelgen.NoiseSettings
- net.minecraft.world.level.levelgen.OreVeinifier
+ net.minecraft.world.level.levelgen.OreVeinifier$VeinType
- net.minecraft.world.level.levelgen.PatrolSpawner
+ net.minecraft.world.level.levelgen.PhantomSpawner
- net.minecraft.world.level.levelgen.PositionalRandomFactory
+ net.minecraft.world.level.levelgen.RandomState
- net.minecraft.world.level.levelgen.RandomState$1
+ net.minecraft.world.level.levelgen.RandomState$1NoiseWiringHelper
- net.minecraft.world.level.levelgen.RandomSupport
+ net.minecraft.world.level.levelgen.RandomSupport$Seed128bit
- net.minecraft.world.level.levelgen.SingleThreadedRandomSource
+ net.minecraft.world.level.levelgen.SurfaceRules
- net.minecraft.world.level.levelgen.SurfaceRules$AbovePreliminarySurface
+ net.minecraft.world.level.levelgen.SurfaceRules$Bandlands
- net.minecraft.world.level.levelgen.SurfaceRules$BiomeConditionSource
+ net.minecraft.world.level.levelgen.SurfaceRules$BiomeConditionSource$1BiomeCondition
- net.minecraft.world.level.levelgen.SurfaceRules$BlockRuleSource
+ net.minecraft.world.level.levelgen.SurfaceRules$Condition
- net.minecraft.world.level.levelgen.SurfaceRules$ConditionSource
+ net.minecraft.world.level.levelgen.SurfaceRules$Context
- net.minecraft.world.level.levelgen.SurfaceRules$Context$AbovePreliminarySurfaceCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$Context$HoleCondition
- net.minecraft.world.level.levelgen.SurfaceRules$Context$SteepMaterialCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$Context$TemperatureHelperCondition
- net.minecraft.world.level.levelgen.SurfaceRules$Hole
+ net.minecraft.world.level.levelgen.SurfaceRules$LazyCondition
- net.minecraft.world.level.levelgen.SurfaceRules$LazyXZCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$LazyYCondition
- net.minecraft.world.level.levelgen.SurfaceRules$NoiseThresholdConditionSource
+ net.minecraft.world.level.levelgen.SurfaceRules$NoiseThresholdConditionSource$1NoiseThresholdCondition
- net.minecraft.world.level.levelgen.SurfaceRules$NotCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$NotConditionSource
- net.minecraft.world.level.levelgen.SurfaceRules$RuleSource
+ net.minecraft.world.level.levelgen.SurfaceRules$SequenceRule
- net.minecraft.world.level.levelgen.SurfaceRules$SequenceRuleSource
+ net.minecraft.world.level.levelgen.SurfaceRules$StateRule
- net.minecraft.world.level.levelgen.SurfaceRules$Steep
+ net.minecraft.world.level.levelgen.SurfaceRules$StoneDepthCheck
- net.minecraft.world.level.levelgen.SurfaceRules$StoneDepthCheck$1StoneDepthCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$SurfaceRule
- net.minecraft.world.level.levelgen.SurfaceRules$Temperature
+ net.minecraft.world.level.levelgen.SurfaceRules$TestRule
- net.minecraft.world.level.levelgen.SurfaceRules$TestRuleSource
+ net.minecraft.world.level.levelgen.SurfaceRules$VerticalGradientConditionSource
- net.minecraft.world.level.levelgen.SurfaceRules$VerticalGradientConditionSource$1VerticalGradientCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$WaterConditionSource
- net.minecraft.world.level.levelgen.SurfaceRules$WaterConditionSource$1WaterCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$YConditionSource
- net.minecraft.world.level.levelgen.SurfaceRules$YConditionSource$1YCondition
+ net.minecraft.world.level.levelgen.SurfaceSystem
- net.minecraft.world.level.levelgen.SurfaceSystem$1
+ net.minecraft.world.level.levelgen.ThreadSafeLegacyRandomSource
- net.minecraft.world.level.levelgen.VerticalAnchor
+ net.minecraft.world.level.levelgen.VerticalAnchor$AboveBottom
- net.minecraft.world.level.levelgen.VerticalAnchor$Absolute
+ net.minecraft.world.level.levelgen.VerticalAnchor$BelowTop
- net.minecraft.world.level.levelgen.WorldDimensions
+ net.minecraft.world.level.levelgen.WorldDimensions$1Entry
- net.minecraft.world.level.levelgen.WorldDimensions$Complete
- net.minecraft.world.level.levelgen.WorldGenerationContext
- net.minecraft.world.level.levelgen.WorldgenRandom
+ net.minecraft.world.level.levelgen.WorldgenRandom$Algorithm
+ net.minecraft.world.level.levelgen.WorldGenSettings
+ net.minecraft.world.level.levelgen.WorldOptions
- net.minecraft.world.level.levelgen.Xoroshiro128PlusPlus
+ net.minecraft.world.level.levelgen.XoroshiroRandomSource
- net.minecraft.world.level.levelgen.XoroshiroRandomSource$XoroshiroPositionalRandomFactory
- net.minecraft.world.level.LevelHeightAccessor
+ net.minecraft.world.level.LevelHeightAccessor$1
- net.minecraft.world.level.LevelReader
+ net.minecraft.world.level.LevelSettings
+ net.minecraft.world.level.LevelSimulatedReader
- net.minecraft.world.level.LevelSimulatedRW
- net.minecraft.world.level.LevelTimeAccess
+ net.minecraft.world.level.LevelWriter
- net.minecraft.world.level.LightLayer
+ net.minecraft.world.level.LocalMobCapCalculator
- net.minecraft.world.level.LocalMobCapCalculator$MobCounts
+ net.minecraft.world.level.NaturalSpawner
- net.minecraft.world.level.NaturalSpawner$1
+ net.minecraft.world.level.NaturalSpawner$AfterSpawnCallback
- net.minecraft.world.level.NaturalSpawner$ChunkGetter
+ net.minecraft.world.level.NaturalSpawner$SpawnPredicate
- net.minecraft.world.level.NaturalSpawner$SpawnState
+ net.minecraft.world.level.NoiseColumn
- net.minecraft.world.level.PathNavigationRegion
+ net.minecraft.world.level.PotentialCalculator
- net.minecraft.world.level.PotentialCalculator$PointCharge
+ net.minecraft.world.level.ServerLevelAccessor
- net.minecraft.world.level.SignalGetter
+ net.minecraft.world.level.SpawnData
- net.minecraft.world.level.SpawnData$CustomSpawnRules
+ net.minecraft.world.level.StructureManager
- net.minecraft.world.level.WorldDataConfiguration
+ net.minecraft.world.level.WorldGenLevel
```

</details>
<details>
<summary>
Changes
</summary>

```
net.minecraft.ChatFormatting +1M | +2P
```
```
net.minecraft.SharedConstants +1P
```
```
net.minecraft.Util +2M -1M
```
```
XXX.advancements.critereon.PlayerTrigger$TriggerInstance +1M
```
```
XXX.minecraft.core.Direction +3P
```
```
XXX.minecraft.core.Direction$Axis +1P
```
```
XXX.minecraft.core.Direction$Axis$2 +1M
```
```
XXX.core.particles.ParticleTypes +1P
```
```
XXX.loot.packs.VanillaBlockLoot +2M -1M
```
```
XXX.data.models.BlockModelGenerators +11M -1M
```
```
XXX.models.model.ModelTemplates +2P
```
```
XXX.data.recipes.ShapedRecipeBuilder$Result +1M -1M | +2P
```
```
XXX.data.worldgen.SurfaceRuleData +1M | +1P
```
```
XXX.server.level.ServerPlayer +19M -12M | +3P
```
```
XXX.server.players.PlayerList +5M -2M
```
```
XXX.minecraft.stats.Stats +1P
```
```
XXX.minecraft.util.ExtraCodecs +40M -38M
```
```
XXX.world.damagesource.DamageSources +2M | +2P
```
```
XXX.world.damagesource.DamageTypes +2P
```
```
XXX.world.effect.MobEffects +2P
```
```
XXX.world.entity.Entity +18M -2M | +7P -1P
```
```
XXX.entity.animal.Chicken +3M | +1P
```
```
XXX.entity.animal.Cow +18M | +3P
```
```
XXX.entity.animal.IronGolem +1M -1M
```
```
XXX.entity.animal.Parrot +2M -1M
```
```
XXX.entity.animal.Pig +1M
```
```
XXX.entity.animal.Sheep +1M
```
```
XXX.entity.animal.Wolf +1M -1M
```
```
XXX.animal.axolotl.Axolotl +1M -1M
```
```
XXX.animal.horse.AbstractChestedHorse +1M
```
```
XXX.animal.horse.AbstractHorse +2M -1M
```
```
XXX.boss.enderdragon.EndCrystal +1M -1M
```
```
XXX.entity.decoration.ArmorStand +1M -1M
```
```
XXX.entity.item.ItemEntity +4M -2M | +1P
```
```
XXX.entity.monster.Silverfish +1M -1M
```
```
XXX.entity.monster.Vex +1M
```
```
XXX.entity.monster.Zombie +6M -1M
```
```
XXX.entity.vehicle.MinecartTNT +1M -1M
```
```
XXX.world.food.FoodProperties +2M -1M | +1P
```
```
XXX.world.food.Foods +1M | +1P
```
```
XXX.item.alchemy.Potions +6P
```
```
XXX.item.crafting.FireworkRocketRecipe +3M -3M
```
```
XXX.item.crafting.FireworkStarRecipe +3M -3M
```
```
XXX.item.crafting.MapExtendingRecipe +2M -2M
```
```
XXX.level.block.AbstractCandleBlock +2M
```
```
XXX.level.block.AirBlock +2M
```
```
XXX.level.block.ChainBlock +1M
```
```
XXX.level.block.CrossCollisionBlock +1M
```
```
XXX.level.block.DoorBlock +2M
```
```
XXX.level.block.EndRodBlock +1M
```
```
XXX.level.block.LevelEvent +2P
```
```
XXX.level.block.MudBlock +1M
```
```
XXX.level.block.TrapDoorBlock +2M
```
```
XXX.block.entity.BannerPatterns +1P
```
```
XXX.block.entity.HopperBlockEntity +1P
```
```
XXX.block.piston.MovingPistonBlock +2M -1M
```
```
XXX.level.chunk.ChunkAccess +2M | +1P
```
```
XXX.level.dimension.BuiltinDimensionTypes +2P
```
```
XXX.level.dimension.LevelStem +1P
```
```
XXX.levelgen.presets.WorldPresets$Bootstrap +1P
```
```
XXX.level.storage.LevelStorageSource$LevelStorageAccess +2M
```
```
XXX.storage.loot.BuiltInLootTables +3P
```

</details>








<details>
<summary>
net.minecraft.ChatFormatting
</summary>

```diff
- boolean lambda$static$2(ChatFormatting)
```

</details>







<details>
<summary>
net.minecraft.Util
</summary>

```diff
- int calculatePrefixSize(Iterable)
- void shuffle(List,RandomSource)
+ void shuffle(ObjectArrayList,RandomSource)
```

</details>





































































<details>
<summary>
net.minecraft.advancements.critereon.PlayerTrigger$TriggerInstance
</summary>

```diff
- PlayerTrigger$TriggerInstance vote(MinMaxBounds$Ints)
```

</details>















































































































<details>
<summary>
net.minecraft.core.Direction$Axis$2
</summary>

```diff
- Direction[] getOrthogonalDirections()
```

</details>
























































































<details>
<summary>
net.minecraft.data.loot.packs.VanillaBlockLoot
</summary>

```diff
+ LootPoolEntryContainer$Builder lambda$createPitcherCropLoot$238(Integer)
- LootPoolEntryContainer$Builder lambda$createPitcherCropLoot$239(Integer)
- LootTable$Builder lambda$generate$238(Block)
```

</details>




<details>
<summary>
net.minecraft.data.models.BlockModelGenerators
</summary>

```diff
- boolean isOnEdge(double,double,double,double,double,double,Direction)
- JsonElement lambda$createCheeseBlock$58(ResourceLocation,VoxelShape)
- JsonObject buildModelFromShape(ResourceLocation,VoxelShape)
- void createCheeseBlock()
- void createFacing(Block)
+ void createNetherPortalBlock()
- void createNetherPortalBlock(Block)
- void createPackedAir()
- void createSpleaves(Block)
- void lambda$buildModelFromShape$59(double,double,double,JsonArray)
- void lambda$buildModelFromShape$60(double,double,double,JsonArray)
- void lambda$buildModelFromShape$61(JsonArray,double,double,double,double,double,double)
```

</details>



























<details>
<summary>
net.minecraft.data.recipes.ShapedRecipeBuilder$Result
</summary>

```diff
- void <init>(ResourceLocation,Item,int,String,CraftingBookCategory,List,Map,Advancement$Builder,ResourceLocation,boolean,boolean,boolean)
+ void <init>(ResourceLocation,Item,int,String,CraftingBookCategory,List,Map,Advancement$Builder,ResourceLocation,boolean)
```

</details>



































<details>
<summary>
net.minecraft.data.worldgen.SurfaceRuleData
</summary>

```diff
- SurfaceRules$RuleSource moon()
```

</details>


































































<details>
<summary>
net.minecraft.server.level.ServerPlayer
</summary>

```diff
+ boolean hurt(DamageSource,float)
- boolean hurtInternal(DamageSource,float)
- boolean isInvertedHealAndHarm()
- boolean lambda$startSleepInBed$10(Monster)
+ boolean lambda$startSleepInBed$8(Monster)
+ boolean lambda$tellNeutralMobsThatIDied$6(Mob)
- boolean lambda$tellNeutralMobsThatIDied$8(Mob)
- boolean lambda$tick$3(ServerPlayer)
+ boolean teleportTo(ServerLevel,double,double,double,Set,float,float)
- double lambda$tick$4(ServerPlayer)
- Entity teleportTo(ServerLevel,double,double,double,Set,float,float)
- MobType getMobType()
+ Packet lambda$die$5(Component)
- Packet lambda$die$7(Component)
+ Packet lambda$sendSystemMessage$11(Component)
- Packet lambda$sendSystemMessage$13(Component)
+ Style lambda$die$4(Component,Style)
- Style lambda$die$6(Component,Style)
+ void lambda$awardStat$10(int,Score)
- void lambda$awardStat$12(int,Score)
+ void lambda$drop$12(Inventory,int)
- void lambda$drop$14(Inventory,int)
- void lambda$startSleepInBed$11(Unit)
+ void lambda$startSleepInBed$9(Unit)
+ void lambda$tellNeutralMobsThatIDied$7(Mob)
- void lambda$tellNeutralMobsThatIDied$9(Mob)
+ void lambda$updateScoreForCriteria$3(int,Score)
- void lambda$updateScoreForCriteria$5(int,Score)
- void stepOnBlock(BlockPos,BlockState,Block)
- void summonLightning(Vec3)
- void turnIntoGold()
```

</details>




































































<details>
<summary>
net.minecraft.server.players.PlayerList
</summary>

```diff
- ClientboundBulkVoteInfoPacket createVoteReloadPacket(UUID)
+ Component lambda$broadcastSystemMessage$3(Component,ServerPlayer)
- Component lambda$broadcastSystemMessage$5(Component,ServerPlayer)
- void lambda$createVoteReloadPacket$2(Map,UUID,ServerVote)
- void lambda$createVoteReloadPacket$3(Map,UUID,OptionId,Voter)
+ void lambda$remove$2(Entity)
- void lambda$remove$4(Entity)
```

</details>
















































<details>
<summary>
net.minecraft.util.ExtraCodecs
</summary>

```diff
+ App lambda$static$73(RecordCodecBuilder$Instance)
- App lambda$static$74(RecordCodecBuilder$Instance)
+ App lambda$static$83(RecordCodecBuilder$Instance)
- App lambda$static$84(RecordCodecBuilder$Instance)
+ BitSet lambda$static$69(LongStream)
- BitSet lambda$static$70(LongStream)
- Codec floatRange(float,float)
+ DataResult lambda$ensureHomogenous$57(Function,Collection)
- DataResult lambda$ensureHomogenous$58(Function,Collection)
+ DataResult lambda$floatRangeMinExclusiveWithMessage$50(float,float,Function,Float)
- DataResult lambda$floatRangeMinExclusiveWithMessage$51(float,float,Function,Float)
+ DataResult lambda$instantCodec$60(DateTimeFormatter,String)
- DataResult lambda$instantCodec$61(DateTimeFormatter,String)
+ DataResult lambda$nonEmptyHolderSet$55(HolderSet)
- DataResult lambda$nonEmptyHolderSet$56(HolderSet)
+ DataResult lambda$nonEmptyList$53(List)
- DataResult lambda$nonEmptyList$54(List)
+ DataResult lambda$sizeLimitedString$88(int,int,String)
- DataResult lambda$sizeLimitedString$89(int,int,String)
+ DataResult lambda$static$59(String)
- DataResult lambda$static$60(String)
+ DataResult lambda$static$62(String)
- DataResult lambda$static$63(String)
+ DataResult lambda$static$66(String)
- DataResult lambda$static$67(String)
+ DataResult lambda$static$85(String)
- DataResult lambda$static$86(String)
+ Either lambda$static$78(PropertyMap)
- Either lambda$static$79(PropertyMap)
+ ExtraCodecs$TagOrElementLocation lambda$static$64(ResourceLocation)
- ExtraCodecs$TagOrElementLocation lambda$static$66(ResourceLocation)
+ GameProfile lambda$static$82(GameProfile,PropertyMap)
- GameProfile lambda$static$83(GameProfile,PropertyMap)
+ LongStream lambda$static$70(BitSet)
- LongStream lambda$static$71(BitSet)
+ Optional lambda$static$68(OptionalLong)
- Optional lambda$static$69(OptionalLong)
+ Optional lambda$static$71(Property)
- Optional lambda$static$72(Property)
+ OptionalLong lambda$static$67(Optional)
- OptionalLong lambda$static$68(Optional)
+ Property lambda$static$72(String,String,Optional)
- Property lambda$static$73(String,String,Optional)
+ PropertyMap lambda$static$77(Either)
- PropertyMap lambda$static$78(Either)
+ String lambda$ensureHomogenous$56(Object,Object,Object)
- String lambda$ensureHomogenous$57(Object,Object,Object)
- String lambda$floatRange$49(float,float,Float)
+ String lambda$floatRangeMinExclusiveWithMessage$49(Function,Float)
- String lambda$floatRangeMinExclusiveWithMessage$50(Function,Float)
+ String lambda$nonEmptyHolderSet$54()
- String lambda$nonEmptyHolderSet$55()
+ String lambda$nonEmptyList$52()
- String lambda$nonEmptyList$53()
+ String lambda$sizeLimitedString$86(String,int,int,int)
- String lambda$sizeLimitedString$88(String,int,int,int)
+ String lambda$static$51(Float)
- String lambda$static$52(Float)
+ String lambda$static$58(String,PatternSyntaxException)
- String lambda$static$59(String,PatternSyntaxException)
+ String lambda$static$61()
- String lambda$static$62()
+ String lambda$static$63(byte[])
- String lambda$static$64(byte[])
+ String lambda$static$80(Optional)
- String lambda$static$81(Optional)
+ String lambda$static$84()
- String lambda$static$85()
+ UUID lambda$static$79(Optional)
- UUID lambda$static$80(Optional)
+ void lambda$static$74(PropertyMap,String,List)
+ void lambda$static$75(PropertyMap,Map)
- void lambda$static$75(PropertyMap,String,List)
+ void lambda$static$76(PropertyMap,List)
- void lambda$static$76(PropertyMap,Map)
- void lambda$static$77(PropertyMap,List)
+ void lambda$static$81(GameProfile,String,Property)
- void lambda$static$82(GameProfile,String,Property)
```

</details>




















































































































































































<details>
<summary>
net.minecraft.world.damagesource.DamageSources
</summary>

```diff
- DamageSource midasTouch()
- DamageSource onMoon()
```

</details>




















<details>
<summary>
net.minecraft.world.entity.Entity
</summary>

```diff
- boolean canSpawnFootprintParticle()
- boolean canTransformFly()
- boolean hurtInternal(DamageSource,float)
- boolean noCulling()
+ boolean teleportTo(ServerLevel,double,double,double,Set,float,float)
- Entity effectiveEntity()
- Entity teleportTo(ServerLevel,double,double,double,Set,float,float)
- EntityDimensions getCurrentDimensions()
- float getEffectiveGravity()
- float getGravity()
- String getSkinName()
- void copyTransformedProperties(LivingEntity)
- void handleInsidePortal(BlockPos,boolean)
+ void handleInsidePortal(BlockPos)
- void postTick()
- void setNoCulling(boolean)
- void spawnFootprintParticle()
- void stepOnBlock(BlockPos,BlockState,Block)
- void transformedTick(EntityTransform,LivingEntity)
- void turnIntoGold()
```

</details>



<details>
<summary>
net.minecraft.world.entity.animal.Chicken
</summary>

```diff
- void lambda$aiStep$0(Holder$Reference)
- void tickFlapping()
- void transformedTick(EntityTransform,LivingEntity)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.Cow
</summary>

```diff
- boolean isBaloonCowEnabled()
- boolean lambda$registerGoals$0()
- double getPassengersRidingOffset()
- EntityDimensions getDimensions(Pose)
- float getBloatScale()
- int getBloatLevel()
- LivingEntity getControllingPassenger()
- void <clinit>()
- void addAdditionalSaveData(CompoundTag)
- void aiStep()
- void defineSynchedData()
- void dropAllDeathLoot(DamageSource)
- void explode()
- void liftOff()
- void onDonePathing()
- void onSyncedDataUpdated(EntityDataAccessor)
- void readAdditionalSaveData(CompoundTag)
- void setBloatLevel(int)
```

</details>














<details>
<summary>
net.minecraft.world.entity.animal.IronGolem
</summary>

```diff
+ boolean hurt(DamageSource,float)
- boolean hurtInternal(DamageSource,float)
```

</details>









<details>
<summary>
net.minecraft.world.entity.animal.Parrot
</summary>

```diff
- boolean canTransformFly()
+ boolean hurt(DamageSource,float)
- boolean hurtInternal(DamageSource,float)
```

</details>

<details>
<summary>
net.minecraft.world.entity.animal.Pig
</summary>

```diff
- InteractionResult transformInteract(Player,LivingEntity,InteractionHand)
```

</details>








<details>
<summary>
net.minecraft.world.entity.animal.Sheep
</summary>

```diff
- DyeColor shiftColor(DyeColor,int)
```

</details>











<details>
<summary>
net.minecraft.world.entity.animal.Wolf
</summary>

```diff
+ boolean hurt(DamageSource,float)
- boolean hurtInternal(DamageSource,float)
```

</details>



<details>
<summary>
net.minecraft.world.entity.animal.axolotl.Axolotl
</summary>

```diff
+ boolean hurt(DamageSource,float)
- boolean hurtInternal(DamageSource,float)
```

</details>














<details>
<summary>
net.minecraft.world.entity.animal.horse.AbstractChestedHorse
</summary>

```diff
- void dropCustomDeathLoot(DamageSource,int,boolean)
```

</details>
<details>
<summary>
net.minecraft.world.entity.animal.horse.AbstractHorse
</summary>

```diff
+ boolean hurt(DamageSource,float)
- boolean hurtInternal(DamageSource,float)
- InteractionResult transformInteract(Player,LivingEntity,InteractionHand)
```

</details>















<details>
<summary>
net.minecraft.world.entity.boss.enderdragon.EndCrystal
</summary>

```diff
+ boolean hurt(DamageSource,float)
- boolean hurtInternal(DamageSource,float)
```

</details>











<details>
<summary>
net.minecraft.world.entity.decoration.ArmorStand
</summary>

```diff
+ boolean hurt(DamageSource,float)
- boolean hurtInternal(DamageSource,float)
```

</details>






<details>
<summary>
net.minecraft.world.entity.item.ItemEntity
</summary>

```diff
+ boolean hurt(DamageSource,float)
- boolean hurtInternal(DamageSource,float)
- boolean isThrownIntentionally()
- void setThrower(UUID,boolean)
+ void setThrower(UUID)
- void turnIntoGold()
```

</details>



<details>
<summary>
net.minecraft.world.entity.monster.Silverfish
</summary>

```diff
+ boolean hurt(DamageSource,float)
- boolean hurtInternal(DamageSource,float)
```

</details>










<details>
<summary>
net.minecraft.world.entity.monster.Vex
</summary>

```diff
- boolean canTransformFly()
```

</details>





<details>
<summary>
net.minecraft.world.entity.monster.Zombie
</summary>

```diff
+ boolean hurt(DamageSource,float)
- boolean hurtInternal(DamageSource,float)
- boolean lambda$addBehaviourGoals$1(Entity)
- float adjustDamage(float)
- float getSpeed()
- void burnInSun(LivingEntity)
- void transformedTick(EntityTransform,LivingEntity)
```

</details>










<details>
<summary>
net.minecraft.world.entity.vehicle.MinecartTNT
</summary>

```diff
+ boolean hurt(DamageSource,float)
- boolean hurtInternal(DamageSource,float)
```

</details>





<details>
<summary>
net.minecraft.world.food.FoodProperties
</summary>

```diff
- BiConsumer getOnEaten()
- void <init>(int,float,boolean,boolean,boolean,List,BiConsumer)
+ void <init>(int,float,boolean,boolean,boolean,List)
```

</details>
<details>
<summary>
net.minecraft.world.food.Foods
</summary>

```diff
- void lambda$static$0(ItemStack,LivingEntity)
```

</details>




























<details>
<summary>
net.minecraft.world.item.crafting.FireworkRocketRecipe
</summary>

```diff
+ ItemStack assemble(Container,RegistryAccess)
+ ItemStack assemble(CraftingContainer,RegistryAccess)
- ItemStack assembleRaw(Container,RegistryAccess)
- ItemStack assembleRaw(CraftingContainer,RegistryAccess)
+ ItemStack getResultItem(RegistryAccess)
- ItemStack getResultItemRaw(RegistryAccess)
```

</details>
<details>
<summary>
net.minecraft.world.item.crafting.FireworkStarRecipe
</summary>

```diff
+ ItemStack assemble(Container,RegistryAccess)
+ ItemStack assemble(CraftingContainer,RegistryAccess)
- ItemStack assembleRaw(Container,RegistryAccess)
- ItemStack assembleRaw(CraftingContainer,RegistryAccess)
+ ItemStack getResultItem(RegistryAccess)
- ItemStack getResultItemRaw(RegistryAccess)
```

</details>


<details>
<summary>
net.minecraft.world.item.crafting.MapExtendingRecipe
</summary>

```diff
+ ItemStack assemble(Container,RegistryAccess)
+ ItemStack assemble(CraftingContainer,RegistryAccess)
- ItemStack assembleRaw(Container,RegistryAccess)
- ItemStack assembleRaw(CraftingContainer,RegistryAccess)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.AbstractCandleBlock
</summary>

```diff
- boolean isRandomlyTicking(BlockState)
- void randomTick(BlockState,ServerLevel,BlockPos,RandomSource)
```

</details>


<details>
<summary>
net.minecraft.world.level.block.AirBlock
</summary>

```diff
- boolean canAirPass(BlockState,ServerLevel,BlockPos,Direction)
- boolean canStickToStuff(BlockState)
```

</details>






























<details>
<summary>
net.minecraft.world.level.block.ChainBlock
</summary>

```diff
- boolean isStickyToNeighbour(Level,BlockPos,BlockState,BlockPos,BlockState,Direction,Direction)
```

</details>




<details>
<summary>
net.minecraft.world.level.block.CrossCollisionBlock
</summary>

```diff
- boolean isStickyToNeighbour(Level,BlockPos,BlockState,BlockPos,BlockState,Direction,Direction)
```

</details>





<details>
<summary>
net.minecraft.world.level.block.DoorBlock
</summary>

```diff
- boolean isRandomlyTicking(BlockState)
- void randomTick(BlockState,ServerLevel,BlockPos,RandomSource)
```

</details>







<details>
<summary>
net.minecraft.world.level.block.EndRodBlock
</summary>

```diff
- void spawnAfterBreak(BlockState,ServerLevel,BlockPos,ItemStack,boolean)
```

</details>































<details>
<summary>
net.minecraft.world.level.block.MudBlock
</summary>

```diff
- boolean canAirPass(BlockState,ServerLevel,BlockPos,Direction)
```

</details>


























<details>
<summary>
net.minecraft.world.level.block.TrapDoorBlock
</summary>

```diff
- boolean isRandomlyTicking(BlockState)
- void randomTick(BlockState,ServerLevel,BlockPos,RandomSource)
```

</details>































































<details>
<summary>
net.minecraft.world.level.block.piston.MovingPistonBlock
</summary>

```diff
+ BlockEntity newMovingBlockEntity(BlockPos,BlockState,BlockState,Direction,boolean,boolean)
- boolean canAirPass(BlockState,ServerLevel,BlockPos,Direction)
- PistonMovingBlockEntity newMovingBlockEntity(BlockPos,BlockState,BlockState,Direction,boolean,boolean)
```

</details>









































<details>
<summary>
net.minecraft.world.level.chunk.ChunkAccess
</summary>

```diff
- boolean isLightsOut()
- void setLightsOut(boolean)
```

</details>



































































































































































































































































































































































<details>
<summary>
net.minecraft.world.level.storage.LevelStorageSource$LevelStorageAccess
</summary>

```diff
- void saveVotes(VoteStorage)
- VoteStorage loadVotes()
```

</details>


































































































































































<h2>Client</h2>
<details>
<summary>
Classes
</summary>

```diff
- net.minecraft.client.gui.components.AbstractButton
+ net.minecraft.client.gui.components.AbstractOptionSliderButton
- net.minecraft.client.gui.components.AbstractScrollWidget
+ net.minecraft.client.gui.components.AbstractSelectionList
- net.minecraft.client.gui.components.AbstractSelectionList$1
+ net.minecraft.client.gui.components.AbstractSelectionList$Entry
- net.minecraft.client.gui.components.AbstractSelectionList$TrackedList
+ net.minecraft.client.gui.components.AbstractSliderButton
- net.minecraft.client.gui.components.AbstractStringWidget
+ net.minecraft.client.gui.components.AbstractWidget
- net.minecraft.client.gui.components.AccessibilityOnboardingTextWidget
+ net.minecraft.client.gui.components.BossHealthOverlay
- net.minecraft.client.gui.components.BossHealthOverlay$1
+ net.minecraft.client.gui.components.Button
- net.minecraft.client.gui.components.Button$Builder
+ net.minecraft.client.gui.components.Button$CreateNarration
- net.minecraft.client.gui.components.Button$OnPress
+ net.minecraft.client.gui.components.ChatComponent
- net.minecraft.client.gui.components.ChatComponent$DelayedMessageDeletion
+ net.minecraft.client.gui.components.Checkbox
- net.minecraft.client.gui.components.CommandSuggestions
+ net.minecraft.client.gui.components.CommandSuggestions$SuggestionsList
- net.minecraft.client.gui.components.CommonButtons
+ net.minecraft.client.gui.components.ComponentRenderUtils
- net.minecraft.client.gui.components.ContainerObjectSelectionList
+ net.minecraft.client.gui.components.ContainerObjectSelectionList$1
- net.minecraft.client.gui.components.ContainerObjectSelectionList$Entry
+ net.minecraft.client.gui.components.CycleButton
- net.minecraft.client.gui.components.CycleButton$Builder
+ net.minecraft.client.gui.components.CycleButton$OnValueChange
- net.minecraft.client.gui.components.CycleButton$ValueListSupplier
+ net.minecraft.client.gui.components.CycleButton$ValueListSupplier$1
- net.minecraft.client.gui.components.CycleButton$ValueListSupplier$2
+ net.minecraft.client.gui.components.DebugScreenOverlay
- net.minecraft.client.gui.components.DebugScreenOverlay$1
+ net.minecraft.client.gui.components.DebugScreenOverlay$AllocationRateCalculator
- net.minecraft.client.gui.components.EditBox
- net.minecraft.client.gui.components.events.AbstractContainerEventHandler
+ net.minecraft.client.gui.components.events.ContainerEventHandler
- net.minecraft.client.gui.components.events.GuiEventListener
+ net.minecraft.client.gui.components.events.package-info
+ net.minecraft.client.gui.components.ImageButton
- net.minecraft.client.gui.components.ImageWidget
+ net.minecraft.client.gui.components.LerpingBossEvent
- net.minecraft.client.gui.components.LockIconButton
+ net.minecraft.client.gui.components.LockIconButton$Icon
- net.minecraft.client.gui.components.LogoRenderer
+ net.minecraft.client.gui.components.MultiLineEditBox
- net.minecraft.client.gui.components.MultiLineLabel
+ net.minecraft.client.gui.components.MultiLineLabel$1
- net.minecraft.client.gui.components.MultiLineLabel$2
+ net.minecraft.client.gui.components.MultiLineLabel$TextWithWidth
- net.minecraft.client.gui.components.MultilineTextField
+ net.minecraft.client.gui.components.MultilineTextField$1
- net.minecraft.client.gui.components.MultilineTextField$StringView
- net.minecraft.client.gui.components.MultiLineTextWidget
+ net.minecraft.client.gui.components.MultiLineTextWidget$CacheKey
+ net.minecraft.client.gui.components.ObjectSelectionList
- net.minecraft.client.gui.components.ObjectSelectionList$Entry
+ net.minecraft.client.gui.components.OptionsList
- net.minecraft.client.gui.components.OptionsList$Entry
- net.minecraft.client.gui.components.package-info
+ net.minecraft.client.gui.components.PlainTextButton
- net.minecraft.client.gui.components.PlayerFaceRenderer
+ net.minecraft.client.gui.components.PlayerTabOverlay
- net.minecraft.client.gui.components.PlayerTabOverlay$HealthState
+ net.minecraft.client.gui.components.Renderable
- net.minecraft.client.gui.components.spectator.package-info
+ net.minecraft.client.gui.components.spectator.SpectatorGui
- net.minecraft.client.gui.components.StateSwitchingButton
+ net.minecraft.client.gui.components.StringWidget
- net.minecraft.client.gui.components.SubtitleOverlay
+ net.minecraft.client.gui.components.SubtitleOverlay$Subtitle
- net.minecraft.client.gui.components.TabButton
+ net.minecraft.client.gui.components.TabOrderedElement
+ net.minecraft.client.gui.components.tabs.GridLayoutTab
- net.minecraft.client.gui.components.tabs.package-info
- net.minecraft.client.gui.components.tabs.Tab
+ net.minecraft.client.gui.components.tabs.TabManager
- net.minecraft.client.gui.components.tabs.TabNavigationBar
+ net.minecraft.client.gui.components.tabs.TabNavigationBar$Builder
- net.minecraft.client.gui.components.TextAndImageButton
+ net.minecraft.client.gui.components.TextAndImageButton$Builder
+ net.minecraft.client.gui.components.toasts.AdvancementToast
+ net.minecraft.client.gui.components.toasts.package-info
- net.minecraft.client.gui.components.toasts.RecipeToast
+ net.minecraft.client.gui.components.toasts.SystemToast
- net.minecraft.client.gui.components.toasts.SystemToast$SystemToastIds
+ net.minecraft.client.gui.components.toasts.Toast
- net.minecraft.client.gui.components.toasts.Toast$Visibility
+ net.minecraft.client.gui.components.toasts.ToastComponent
- net.minecraft.client.gui.components.toasts.ToastComponent$ToastInstance
+ net.minecraft.client.gui.components.toasts.TutorialToast
- net.minecraft.client.gui.components.toasts.TutorialToast$Icons
- net.minecraft.client.gui.components.toasts.VoteNagToast$Urgency
- net.minecraft.client.gui.components.Tooltip
+ net.minecraft.client.gui.components.Whence
- net.minecraft.client.gui.font.AllMissingGlyphProvider
+ net.minecraft.client.gui.font.FontManager
- net.minecraft.client.gui.font.FontManager$1
+ net.minecraft.client.gui.font.FontSet
- net.minecraft.client.gui.font.FontSet$GlyphInfoFilter
+ net.minecraft.client.gui.font.FontTexture
- net.minecraft.client.gui.font.FontTexture$Node
- net.minecraft.client.gui.font.glyphs.BakedGlyph
+ net.minecraft.client.gui.font.glyphs.BakedGlyph$1
- net.minecraft.client.gui.font.glyphs.BakedGlyph$Effect
+ net.minecraft.client.gui.font.glyphs.EmptyGlyph
+ net.minecraft.client.gui.font.glyphs.package-info
- net.minecraft.client.gui.font.glyphs.SpecialGlyphs
+ net.minecraft.client.gui.font.glyphs.SpecialGlyphs$1
- net.minecraft.client.gui.font.glyphs.SpecialGlyphs$PixelProvider
- net.minecraft.client.gui.font.package-info
+ net.minecraft.client.gui.font.providers.BitmapProvider
- net.minecraft.client.gui.font.providers.BitmapProvider$Builder
+ net.minecraft.client.gui.font.providers.BitmapProvider$Glyph
- net.minecraft.client.gui.font.providers.BitmapProvider$Glyph$1
+ net.minecraft.client.gui.font.providers.GlyphProviderBuilder
- net.minecraft.client.gui.font.providers.GlyphProviderBuilderType
+ net.minecraft.client.gui.font.providers.LegacyUnicodeBitmapsProvider
- net.minecraft.client.gui.font.providers.LegacyUnicodeBitmapsProvider$Builder
+ net.minecraft.client.gui.font.providers.LegacyUnicodeBitmapsProvider$Glyph
- net.minecraft.client.gui.font.providers.LegacyUnicodeBitmapsProvider$Glyph$1
+ net.minecraft.client.gui.font.providers.LegacyUnicodeBitmapsProvider$Sheet
+ net.minecraft.client.gui.font.providers.package-info
- net.minecraft.client.gui.font.providers.TrueTypeGlyphProviderBuilder
+ net.minecraft.client.gui.font.TextFieldHelper
- net.minecraft.client.gui.font.TextFieldHelper$1
+ net.minecraft.client.gui.font.TextFieldHelper$CursorStep
- net.minecraft.client.gui.Font$DisplayMode
+ net.minecraft.client.gui.Font$StringRenderOutput
- net.minecraft.client.gui.Gui
+ net.minecraft.client.gui.Gui$HeartType
- net.minecraft.client.gui.GuiComponent
+ net.minecraft.client.gui.GuiComponent$ScissorStack
- net.minecraft.client.gui.layouts.AbstractLayout
+ net.minecraft.client.gui.layouts.AbstractLayout$AbstractChildWrapper
- net.minecraft.client.gui.layouts.FrameLayout
+ net.minecraft.client.gui.layouts.FrameLayout$ChildContainer
- net.minecraft.client.gui.layouts.GridLayout
+ net.minecraft.client.gui.layouts.GridLayout$CellInhabitant
- net.minecraft.client.gui.layouts.GridLayout$RowHelper
+ net.minecraft.client.gui.layouts.HeaderAndFooterLayout
- net.minecraft.client.gui.layouts.Layout
+ net.minecraft.client.gui.layouts.LayoutElement
- net.minecraft.client.gui.layouts.LayoutSettings
+ net.minecraft.client.gui.layouts.LayoutSettings$LayoutSettingsImpl
- net.minecraft.client.gui.layouts.LinearLayout
+ net.minecraft.client.gui.layouts.LinearLayout$1
- net.minecraft.client.gui.layouts.LinearLayout$ChildContainer
+ net.minecraft.client.gui.layouts.LinearLayout$Orientation
+ net.minecraft.client.gui.layouts.package-info
- net.minecraft.client.gui.layouts.SpacerElement
- net.minecraft.client.gui.MapRenderer
+ net.minecraft.client.gui.MapRenderer$MapInstance
- net.minecraft.client.gui.narration.NarratableEntry
+ net.minecraft.client.gui.narration.NarratableEntry$NarrationPriority
- net.minecraft.client.gui.narration.NarratedElementType
+ net.minecraft.client.gui.narration.NarrationElementOutput
- net.minecraft.client.gui.narration.NarrationSupplier
+ net.minecraft.client.gui.narration.NarrationThunk
+ net.minecraft.client.gui.narration.package-info
- net.minecraft.client.gui.narration.ScreenNarrationCollector
+ net.minecraft.client.gui.narration.ScreenNarrationCollector$1
- net.minecraft.client.gui.narration.ScreenNarrationCollector$EntryKey
+ net.minecraft.client.gui.narration.ScreenNarrationCollector$NarrationEntry
- net.minecraft.client.gui.narration.ScreenNarrationCollector$Output
- net.minecraft.client.gui.navigation.FocusNavigationEvent
+ net.minecraft.client.gui.navigation.FocusNavigationEvent$ArrowNavigation
- net.minecraft.client.gui.navigation.FocusNavigationEvent$InitialFocus
+ net.minecraft.client.gui.navigation.FocusNavigationEvent$TabNavigation
- net.minecraft.client.gui.navigation.package-info
- net.minecraft.client.gui.navigation.ScreenAxis
+ net.minecraft.client.gui.navigation.ScreenAxis$1
- net.minecraft.client.gui.navigation.ScreenDirection
+ net.minecraft.client.gui.navigation.ScreenDirection$1
- net.minecraft.client.gui.navigation.ScreenPosition
+ net.minecraft.client.gui.navigation.ScreenPosition$1
- net.minecraft.client.gui.navigation.ScreenRectangle
+ net.minecraft.client.gui.navigation.ScreenRectangle$1
+ net.minecraft.client.gui.package-info
- net.minecraft.client.gui.screens.AccessibilityOnboardingScreen
+ net.minecraft.client.gui.screens.AccessibilityOptionsScreen
+ net.minecraft.client.gui.screens.achievement.package-info
- net.minecraft.client.gui.screens.achievement.StatsScreen
+ net.minecraft.client.gui.screens.achievement.StatsScreen$GeneralStatisticsList
- net.minecraft.client.gui.screens.achievement.StatsScreen$GeneralStatisticsList$Entry
+ net.minecraft.client.gui.screens.achievement.StatsScreen$ItemStatisticsList
- net.minecraft.client.gui.screens.achievement.StatsScreen$ItemStatisticsList$ItemRow
+ net.minecraft.client.gui.screens.achievement.StatsScreen$ItemStatisticsList$ItemRowComparator
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
- net.minecraft.client.gui.screens.AlertScreen
+ net.minecraft.client.gui.screens.BackupConfirmScreen
- net.minecraft.client.gui.screens.BackupConfirmScreen$Listener
+ net.minecraft.client.gui.screens.BanNoticeScreen
- net.minecraft.client.gui.screens.ChatOptionsScreen
+ net.minecraft.client.gui.screens.ChatScreen
- net.minecraft.client.gui.screens.ChatScreen$1
+ net.minecraft.client.gui.screens.ConfirmLinkScreen
- net.minecraft.client.gui.screens.ConfirmScreen
+ net.minecraft.client.gui.screens.ConnectScreen
- net.minecraft.client.gui.screens.ConnectScreen$1
+ net.minecraft.client.gui.screens.controls.ControlsScreen
- net.minecraft.client.gui.screens.controls.KeyBindsList
+ net.minecraft.client.gui.screens.controls.KeyBindsList$CategoryEntry
- net.minecraft.client.gui.screens.controls.KeyBindsList$CategoryEntry$1
+ net.minecraft.client.gui.screens.controls.KeyBindsList$Entry
- net.minecraft.client.gui.screens.controls.KeyBindsList$KeyEntry
+ net.minecraft.client.gui.screens.controls.KeyBindsScreen
- net.minecraft.client.gui.screens.controls.package-info
+ net.minecraft.client.gui.screens.CreateBuffetWorldScreen
- net.minecraft.client.gui.screens.CreateBuffetWorldScreen$BiomeList
+ net.minecraft.client.gui.screens.CreateBuffetWorldScreen$BiomeList$Entry
- net.minecraft.client.gui.screens.CreateFlatWorldScreen
+ net.minecraft.client.gui.screens.CreateFlatWorldScreen$DetailsList
- net.minecraft.client.gui.screens.CreateFlatWorldScreen$DetailsList$Entry
+ net.minecraft.client.gui.screens.CreditsAndAttributionScreen
- net.minecraft.client.gui.screens.DatapackLoadFailureScreen
+ net.minecraft.client.gui.screens.DeathScreen
- net.minecraft.client.gui.screens.DeathScreen$TitleConfirmScreen
+ net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen
- net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen$1
+ net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen$GameModeIcon
- net.minecraft.client.gui.screens.debug.GameModeSwitcherScreen$GameModeSlot
+ net.minecraft.client.gui.screens.debug.package-info
+ net.minecraft.client.gui.screens.DemoIntroScreen
- net.minecraft.client.gui.screens.DirectJoinServerScreen
+ net.minecraft.client.gui.screens.DisconnectedScreen
- net.minecraft.client.gui.screens.EditServerScreen
+ net.minecraft.client.gui.screens.ErrorScreen
- net.minecraft.client.gui.screens.GenericDirtMessageScreen
+ net.minecraft.client.gui.screens.GenericWaitingScreen
- net.minecraft.client.gui.screens.InBedChatScreen
- net.minecraft.client.gui.screens.inventory.AbstractCommandBlockEditScreen
+ net.minecraft.client.gui.screens.inventory.AbstractCommandBlockEditScreen$1
- net.minecraft.client.gui.screens.inventory.AbstractContainerScreen
+ net.minecraft.client.gui.screens.inventory.AbstractFurnaceScreen
- net.minecraft.client.gui.screens.inventory.AbstractSignEditScreen
+ net.minecraft.client.gui.screens.inventory.AnvilScreen
- net.minecraft.client.gui.screens.inventory.BeaconScreen
+ net.minecraft.client.gui.screens.inventory.BeaconScreen$1
- net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconButton
+ net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconCancelButton
- net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconConfirmButton
+ net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconPowerButton
- net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconScreenButton
+ net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconSpriteScreenButton
- net.minecraft.client.gui.screens.inventory.BeaconScreen$BeaconUpgradePowerButton
+ net.minecraft.client.gui.screens.inventory.BlastFurnaceScreen
- net.minecraft.client.gui.screens.inventory.BookEditScreen
+ net.minecraft.client.gui.screens.inventory.BookEditScreen$DisplayCache
- net.minecraft.client.gui.screens.inventory.BookEditScreen$LineInfo
+ net.minecraft.client.gui.screens.inventory.BookEditScreen$Pos2i
- net.minecraft.client.gui.screens.inventory.BookViewScreen
+ net.minecraft.client.gui.screens.inventory.BookViewScreen$1
- net.minecraft.client.gui.screens.inventory.BookViewScreen$BookAccess
+ net.minecraft.client.gui.screens.inventory.BookViewScreen$WritableBookAccess
- net.minecraft.client.gui.screens.inventory.BookViewScreen$WrittenBookAccess
+ net.minecraft.client.gui.screens.inventory.BrewingStandScreen
- net.minecraft.client.gui.screens.inventory.CartographyTableScreen
+ net.minecraft.client.gui.screens.inventory.CommandBlockEditScreen
- net.minecraft.client.gui.screens.inventory.CommandBlockEditScreen$1
+ net.minecraft.client.gui.screens.inventory.ContainerScreen
- net.minecraft.client.gui.screens.inventory.CraftingScreen
+ net.minecraft.client.gui.screens.inventory.CreativeInventoryListener
- net.minecraft.client.gui.screens.inventory.CreativeModeInventoryScreen
+ net.minecraft.client.gui.screens.inventory.CreativeModeInventoryScreen$CustomCreativeSlot
- net.minecraft.client.gui.screens.inventory.CreativeModeInventoryScreen$ItemPickerMenu
+ net.minecraft.client.gui.screens.inventory.CreativeModeInventoryScreen$SlotWrapper
- net.minecraft.client.gui.screens.inventory.CyclingSlotBackground
+ net.minecraft.client.gui.screens.inventory.DispenserScreen
- net.minecraft.client.gui.screens.inventory.EffectRenderingInventoryScreen
+ net.minecraft.client.gui.screens.inventory.EnchantmentNames
- net.minecraft.client.gui.screens.inventory.EnchantmentScreen
+ net.minecraft.client.gui.screens.inventory.FurnaceScreen
- net.minecraft.client.gui.screens.inventory.GrindstoneScreen
+ net.minecraft.client.gui.screens.inventory.HangingSignEditScreen
- net.minecraft.client.gui.screens.inventory.HopperScreen
+ net.minecraft.client.gui.screens.inventory.HorseInventoryScreen
- net.minecraft.client.gui.screens.inventory.InventoryScreen
+ net.minecraft.client.gui.screens.inventory.ItemCombinerScreen
- net.minecraft.client.gui.screens.inventory.JigsawBlockEditScreen
+ net.minecraft.client.gui.screens.inventory.JigsawBlockEditScreen$1
- net.minecraft.client.gui.screens.inventory.LecternScreen
+ net.minecraft.client.gui.screens.inventory.LecternScreen$1
- net.minecraft.client.gui.screens.inventory.LoomScreen
+ net.minecraft.client.gui.screens.inventory.MenuAccess
- net.minecraft.client.gui.screens.inventory.MerchantScreen
+ net.minecraft.client.gui.screens.inventory.MerchantScreen$TradeOfferButton
- net.minecraft.client.gui.screens.inventory.MinecartCommandBlockEditScreen
- net.minecraft.client.gui.screens.inventory.package-info
+ net.minecraft.client.gui.screens.inventory.PageButton
- net.minecraft.client.gui.screens.inventory.ShulkerBoxScreen
+ net.minecraft.client.gui.screens.inventory.SignEditScreen
- net.minecraft.client.gui.screens.inventory.SmithingScreen
+ net.minecraft.client.gui.screens.inventory.SmokerScreen
- net.minecraft.client.gui.screens.inventory.StonecutterScreen
+ net.minecraft.client.gui.screens.inventory.StructureBlockEditScreen
- net.minecraft.client.gui.screens.inventory.StructureBlockEditScreen$1
+ net.minecraft.client.gui.screens.inventory.StructureBlockEditScreen$2
+ net.minecraft.client.gui.screens.inventory.tooltip.BelowOrAboveWidgetTooltipPositioner
- net.minecraft.client.gui.screens.inventory.tooltip.ClientBundleTooltip
+ net.minecraft.client.gui.screens.inventory.tooltip.ClientBundleTooltip$Texture
- net.minecraft.client.gui.screens.inventory.tooltip.ClientTextTooltip
+ net.minecraft.client.gui.screens.inventory.tooltip.ClientTooltipComponent
- net.minecraft.client.gui.screens.inventory.tooltip.ClientTooltipPositioner
+ net.minecraft.client.gui.screens.inventory.tooltip.DefaultTooltipPositioner
- net.minecraft.client.gui.screens.inventory.tooltip.MenuTooltipPositioner
+ net.minecraft.client.gui.screens.inventory.tooltip.package-info
+ net.minecraft.client.gui.screens.inventory.tooltip.TooltipRenderUtil
- net.minecraft.client.gui.screens.inventory.tooltip.TooltipRenderUtil$BlitPainter
+ net.minecraft.client.gui.screens.LanguageSelectScreen
- net.minecraft.client.gui.screens.LanguageSelectScreen$LanguageSelectionList
+ net.minecraft.client.gui.screens.LanguageSelectScreen$LanguageSelectionList$Entry
- net.minecraft.client.gui.screens.LevelLoadingScreen
+ net.minecraft.client.gui.screens.LoadingDotsText
- net.minecraft.client.gui.screens.LoadingOverlay
+ net.minecraft.client.gui.screens.LoadingOverlay$LogoTexture
- net.minecraft.client.gui.screens.MenuScreens
+ net.minecraft.client.gui.screens.MenuScreens$ScreenConstructor
- net.minecraft.client.gui.screens.MouseSettingsScreen
- net.minecraft.client.gui.screens.multiplayer.JoinMultiplayerScreen
+ net.minecraft.client.gui.screens.multiplayer.package-info
+ net.minecraft.client.gui.screens.multiplayer.Realms32bitWarningScreen
- net.minecraft.client.gui.screens.multiplayer.SafetyScreen
+ net.minecraft.client.gui.screens.multiplayer.ServerSelectionList
- net.minecraft.client.gui.screens.multiplayer.ServerSelectionList$Entry
+ net.minecraft.client.gui.screens.multiplayer.ServerSelectionList$LANHeader
- net.minecraft.client.gui.screens.multiplayer.ServerSelectionList$NetworkServerEntry
+ net.minecraft.client.gui.screens.multiplayer.ServerSelectionList$OnlineServerEntry
- net.minecraft.client.gui.screens.multiplayer.WarningScreen
+ net.minecraft.client.gui.screens.OnlineOptionsScreen
- net.minecraft.client.gui.screens.OptionsScreen
+ net.minecraft.client.gui.screens.OptionsSubScreen
- net.minecraft.client.gui.screens.OutOfMemoryScreen
+ net.minecraft.client.gui.screens.Overlay
- net.minecraft.client.gui.screens.package-info
- net.minecraft.client.gui.screens.packs.package-info
+ net.minecraft.client.gui.screens.packs.PackSelectionModel
- net.minecraft.client.gui.screens.packs.PackSelectionModel$Entry
+ net.minecraft.client.gui.screens.packs.PackSelectionModel$EntryBase
- net.minecraft.client.gui.screens.packs.PackSelectionModel$SelectedPackEntry
+ net.minecraft.client.gui.screens.packs.PackSelectionModel$UnselectedPackEntry
- net.minecraft.client.gui.screens.packs.PackSelectionScreen
+ net.minecraft.client.gui.screens.packs.PackSelectionScreen$Watcher
- net.minecraft.client.gui.screens.packs.TransferableSelectionList
+ net.minecraft.client.gui.screens.packs.TransferableSelectionList$PackEntry
- net.minecraft.client.gui.screens.PauseScreen
+ net.minecraft.client.gui.screens.PopupScreen
- net.minecraft.client.gui.screens.PopupScreen$ButtonOption
+ net.minecraft.client.gui.screens.PresetFlatWorldScreen
- net.minecraft.client.gui.screens.PresetFlatWorldScreen$PresetsList
+ net.minecraft.client.gui.screens.PresetFlatWorldScreen$PresetsList$Entry
- net.minecraft.client.gui.screens.ProgressScreen
+ net.minecraft.client.gui.screens.ReceivingLevelScreen
+ net.minecraft.client.gui.screens.recipebook.AbstractFurnaceRecipeBookComponent
- net.minecraft.client.gui.screens.recipebook.BlastingRecipeBookComponent
+ net.minecraft.client.gui.screens.recipebook.GhostRecipe
- net.minecraft.client.gui.screens.recipebook.GhostRecipe$GhostIngredient
+ net.minecraft.client.gui.screens.recipebook.OverlayRecipeComponent
- net.minecraft.client.gui.screens.recipebook.OverlayRecipeComponent$OverlayRecipeButton
+ net.minecraft.client.gui.screens.recipebook.OverlayRecipeComponent$OverlayRecipeButton$Pos
- net.minecraft.client.gui.screens.recipebook.OverlayRecipeComponent$OverlaySmeltingRecipeButton
- net.minecraft.client.gui.screens.recipebook.package-info
+ net.minecraft.client.gui.screens.recipebook.RecipeBookComponent
- net.minecraft.client.gui.screens.recipebook.RecipeBookPage
+ net.minecraft.client.gui.screens.recipebook.RecipeBookTabButton
- net.minecraft.client.gui.screens.recipebook.RecipeButton
+ net.minecraft.client.gui.screens.recipebook.RecipeCollection
- net.minecraft.client.gui.screens.recipebook.RecipeShownListener
+ net.minecraft.client.gui.screens.recipebook.RecipeUpdateListener
- net.minecraft.client.gui.screens.recipebook.SmeltingRecipeBookComponent
+ net.minecraft.client.gui.screens.recipebook.SmokingRecipeBookComponent
+ net.minecraft.client.gui.screens.reporting.ChatReportScreen
- net.minecraft.client.gui.screens.reporting.ChatReportScreen$DiscardReportWarningScreen
+ net.minecraft.client.gui.screens.reporting.ChatSelectionLogFiller
- net.minecraft.client.gui.screens.reporting.ChatSelectionLogFiller$Output
+ net.minecraft.client.gui.screens.reporting.ChatSelectionScreen
- net.minecraft.client.gui.screens.reporting.ChatSelectionScreen$ChatSelectionList
+ net.minecraft.client.gui.screens.reporting.ChatSelectionScreen$ChatSelectionList$DividerEntry
- net.minecraft.client.gui.screens.reporting.ChatSelectionScreen$ChatSelectionList$Entry
+ net.minecraft.client.gui.screens.reporting.ChatSelectionScreen$ChatSelectionList$Heading
- net.minecraft.client.gui.screens.reporting.ChatSelectionScreen$ChatSelectionList$MessageEntry
+ net.minecraft.client.gui.screens.reporting.ChatSelectionScreen$ChatSelectionList$MessageHeadingEntry
- net.minecraft.client.gui.screens.reporting.ChatSelectionScreen$ChatSelectionList$PaddingEntry
- net.minecraft.client.gui.screens.reporting.package-info
+ net.minecraft.client.gui.screens.reporting.ReportReasonSelectionScreen
- net.minecraft.client.gui.screens.reporting.ReportReasonSelectionScreen$ReasonSelectionList
+ net.minecraft.client.gui.screens.reporting.ReportReasonSelectionScreen$ReasonSelectionList$Entry
- net.minecraft.client.gui.screens.Screen
+ net.minecraft.client.gui.screens.Screen$DeferredTooltipRendering
- net.minecraft.client.gui.screens.Screen$NarratableSearchResult
+ net.minecraft.client.gui.screens.ShareToLanScreen
- net.minecraft.client.gui.screens.SimpleOptionsSubScreen
+ net.minecraft.client.gui.screens.SkinCustomizationScreen
+ net.minecraft.client.gui.screens.social.package-info
+ net.minecraft.client.gui.screens.social.PlayerEntry
- net.minecraft.client.gui.screens.social.PlayerEntry$1
+ net.minecraft.client.gui.screens.social.PlayerEntry$2
- net.minecraft.client.gui.screens.social.PlayerEntry$3
+ net.minecraft.client.gui.screens.social.PlayerSocialManager
- net.minecraft.client.gui.screens.social.SocialInteractionsPlayerList
+ net.minecraft.client.gui.screens.social.SocialInteractionsScreen
- net.minecraft.client.gui.screens.social.SocialInteractionsScreen$1
+ net.minecraft.client.gui.screens.social.SocialInteractionsScreen$2
- net.minecraft.client.gui.screens.social.SocialInteractionsScreen$Page
- net.minecraft.client.gui.screens.SoundOptionsScreen
- net.minecraft.client.gui.screens.SuperSimpleTextScreen
- net.minecraft.client.gui.screens.SuperSimpleTextScreen$SimpleTextList$Entry
- net.minecraft.client.gui.screens.telemetry.package-info
- net.minecraft.client.gui.screens.telemetry.TelemetryEventWidget
+ net.minecraft.client.gui.screens.telemetry.TelemetryEventWidget$Content
- net.minecraft.client.gui.screens.telemetry.TelemetryEventWidget$ContentBuilder
+ net.minecraft.client.gui.screens.telemetry.TelemetryInfoScreen
+ net.minecraft.client.gui.screens.TitleScreen
- net.minecraft.client.gui.screens.TitleScreen$WarningLabel
+ net.minecraft.client.gui.screens.VideoSettingsScreen
- net.minecraft.client.gui.screens.voting.package-info
- net.minecraft.client.gui.screens.voting.VoteSelectionEntry
- net.minecraft.client.gui.screens.voting.VoteSelectionScreen
- net.minecraft.client.gui.screens.voting.VotingScreen$1
- net.minecraft.client.gui.screens.voting.VotingScreen$3
- net.minecraft.client.gui.screens.voting.VotingScreen$FakeAndTerrible
- net.minecraft.client.gui.screens.voting.VotingScreen$OptionSelectButton
- net.minecraft.client.gui.screens.WinScreen
+ net.minecraft.client.gui.screens.WinScreen$CreditsReader
+ net.minecraft.client.gui.screens.worldselection.ConfirmExperimentalFeaturesScreen
- net.minecraft.client.gui.screens.worldselection.ConfirmExperimentalFeaturesScreen$DetailsScreen
+ net.minecraft.client.gui.screens.worldselection.ConfirmExperimentalFeaturesScreen$DetailsScreen$PackList
- net.minecraft.client.gui.screens.worldselection.ConfirmExperimentalFeaturesScreen$DetailsScreen$PackListEntry
+ net.minecraft.client.gui.screens.worldselection.CreateWorldScreen
- net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$DataPackReloadCookie
+ net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$GameTab
- net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$MoreTab
+ net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$WorldTab
- net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$WorldTab$1
+ net.minecraft.client.gui.screens.worldselection.CreateWorldScreen$WorldTab$2
- net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen
+ net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$BooleanRuleEntry
- net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$CategoryRuleEntry
+ net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$CategoryRuleEntry$1
- net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$EntryFactory
+ net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$GameRuleEntry
- net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$IntegerRuleEntry
+ net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$RuleEntry
- net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$RuleList
+ net.minecraft.client.gui.screens.worldselection.EditGameRulesScreen$RuleList$1
- net.minecraft.client.gui.screens.worldselection.EditWorldScreen
+ net.minecraft.client.gui.screens.worldselection.ExperimentsScreen
- net.minecraft.client.gui.screens.worldselection.OptimizeWorldScreen
- net.minecraft.client.gui.screens.worldselection.package-info
+ net.minecraft.client.gui.screens.worldselection.PresetEditor
- net.minecraft.client.gui.screens.worldselection.SelectWorldScreen
+ net.minecraft.client.gui.screens.worldselection.SwitchGrid
- net.minecraft.client.gui.screens.worldselection.SwitchGrid$Builder
+ net.minecraft.client.gui.screens.worldselection.SwitchGrid$InfoUnderneathSettings
- net.minecraft.client.gui.screens.worldselection.SwitchGrid$LabeledSwitch
+ net.minecraft.client.gui.screens.worldselection.SwitchGrid$SwitchBuilder
- net.minecraft.client.gui.screens.worldselection.WorldCreationContext
+ net.minecraft.client.gui.screens.worldselection.WorldCreationContext$DimensionsUpdater
- net.minecraft.client.gui.screens.worldselection.WorldCreationContext$OptionsModifier
+ net.minecraft.client.gui.screens.worldselection.WorldCreationUiState
- net.minecraft.client.gui.screens.worldselection.WorldCreationUiState$SelectedGameMode
+ net.minecraft.client.gui.screens.worldselection.WorldCreationUiState$WorldTypeEntry
- net.minecraft.client.gui.screens.worldselection.WorldOpenFlows
+ net.minecraft.client.gui.screens.worldselection.WorldOpenFlows$1Data
- net.minecraft.client.gui.screens.worldselection.WorldSelectionList
+ net.minecraft.client.gui.screens.worldselection.WorldSelectionList$Entry
- net.minecraft.client.gui.screens.worldselection.WorldSelectionList$LoadingHeader
+ net.minecraft.client.gui.screens.worldselection.WorldSelectionList$WorldListEntry
- net.minecraft.client.gui.spectator.categories.package-info
- net.minecraft.client.gui.spectator.categories.SpectatorPage
+ net.minecraft.client.gui.spectator.categories.TeleportToPlayerMenuCategory
- net.minecraft.client.gui.spectator.categories.TeleportToTeamMenuCategory
+ net.minecraft.client.gui.spectator.categories.TeleportToTeamMenuCategory$TeamSelectionItem
+ net.minecraft.client.gui.spectator.package-info
+ net.minecraft.client.gui.spectator.PlayerMenuItem
- net.minecraft.client.gui.spectator.RootSpectatorMenuCategory
+ net.minecraft.client.gui.spectator.SpectatorMenu
- net.minecraft.client.gui.spectator.SpectatorMenu$1
+ net.minecraft.client.gui.spectator.SpectatorMenu$CloseSpectatorItem
- net.minecraft.client.gui.spectator.SpectatorMenu$ScrollMenuItem
+ net.minecraft.client.gui.spectator.SpectatorMenuCategory
- net.minecraft.client.gui.spectator.SpectatorMenuItem
+ net.minecraft.client.gui.spectator.SpectatorMenuListener
- net.minecraft.client.main.GameConfig
+ net.minecraft.client.main.GameConfig$FolderData
- net.minecraft.client.main.GameConfig$GameData
+ net.minecraft.client.main.GameConfig$ServerData
- net.minecraft.client.main.GameConfig$UserData
+ net.minecraft.client.main.Main
- net.minecraft.client.main.Main$1
+ net.minecraft.client.main.Main$2
- net.minecraft.client.main.Main$3
- net.minecraft.client.main.package-info
+ net.minecraft.client.main.SilentInitException
+ net.minecraft.client.model.AbstractZombieModel
- net.minecraft.client.model.AgeableHierarchicalModel
+ net.minecraft.client.model.AgeableListModel
- net.minecraft.client.model.AllayModel
+ net.minecraft.client.model.AnimationUtils
- net.minecraft.client.model.ArmedModel
+ net.minecraft.client.model.ArmorStandArmorModel
- net.minecraft.client.model.ArmorStandModel
+ net.minecraft.client.model.AxolotlModel
- net.minecraft.client.model.BatModel
+ net.minecraft.client.model.BeeModel
- net.minecraft.client.model.BeretModel
- net.minecraft.client.model.DolphinModel
- net.minecraft.client.model.dragon.DragonHeadModel
+ net.minecraft.client.model.dragon.package-info
+ net.minecraft.client.model.DrownedModel
- net.minecraft.client.model.ElytraModel
+ net.minecraft.client.model.EndermanModel
- net.minecraft.client.model.EndermiteModel
+ net.minecraft.client.model.EntityModel
- net.minecraft.client.model.EvokerFangsModel
+ net.minecraft.client.model.FoxModel
- net.minecraft.client.model.FrogModel
+ net.minecraft.client.model.geom.builders.CubeDefinition
- net.minecraft.client.model.geom.builders.CubeDeformation
+ net.minecraft.client.model.geom.builders.CubeListBuilder
- net.minecraft.client.model.geom.builders.LayerDefinition
+ net.minecraft.client.model.geom.builders.MaterialDefinition
- net.minecraft.client.model.geom.builders.MeshDefinition
+ net.minecraft.client.model.geom.builders.package-info
+ net.minecraft.client.model.geom.builders.PartDefinition
- net.minecraft.client.model.geom.builders.UVPair
- net.minecraft.client.model.geom.EntityModelSet
+ net.minecraft.client.model.geom.LayerDefinitions
- net.minecraft.client.model.geom.ModelLayerLocation
+ net.minecraft.client.model.geom.ModelLayers
- net.minecraft.client.model.geom.ModelPart
+ net.minecraft.client.model.geom.ModelPart$Cube
- net.minecraft.client.model.geom.ModelPart$Polygon
+ net.minecraft.client.model.geom.ModelPart$Vertex
- net.minecraft.client.model.geom.ModelPart$Visitor
- net.minecraft.client.model.geom.package-info
+ net.minecraft.client.model.geom.PartNames
- net.minecraft.client.model.geom.PartPose
+ net.minecraft.client.model.GhastModel
- net.minecraft.client.model.GiantZombieModel
+ net.minecraft.client.model.GoatModel
- net.minecraft.client.model.GuardianModel
+ net.minecraft.client.model.HeadedModel
- net.minecraft.client.model.HierarchicalModel
+ net.minecraft.client.model.HoglinModel
- net.minecraft.client.model.HorseModel
+ net.minecraft.client.model.HumanoidArmorModel
- net.minecraft.client.model.HumanoidModel
+ net.minecraft.client.model.HumanoidModel$1
- net.minecraft.client.model.HumanoidModel$ArmPose
+ net.minecraft.client.model.IllagerModel
- net.minecraft.client.model.IronGolemModel
+ net.minecraft.client.model.LavaSlimeModel
- net.minecraft.client.model.LeashKnotModel
+ net.minecraft.client.model.ListModel
- net.minecraft.client.model.LlamaModel
+ net.minecraft.client.model.LlamaSpitModel
- net.minecraft.client.model.MinecartModel
+ net.minecraft.client.model.Model
- net.minecraft.client.model.ModelUtils
+ net.minecraft.client.model.package-info
- net.minecraft.client.model.TridentModel
+ net.minecraft.client.model.TropicalFishModelA
- net.minecraft.client.model.TropicalFishModelB
+ net.minecraft.client.model.TurtleModel
- net.minecraft.client.model.VexModel
+ net.minecraft.client.model.VillagerHeadModel
- net.minecraft.client.model.VillagerModel
+ net.minecraft.client.model.WardenModel
- net.minecraft.client.model.WaterPatchModel
+ net.minecraft.client.model.WitchModel
- net.minecraft.client.model.WitherBossModel
+ net.minecraft.client.model.WolfModel
- net.minecraft.client.model.ZombieModel
+ net.minecraft.client.model.ZombieVillagerModel
- net.minecraft.client.multiplayer.AccountProfileKeyPairManager
+ net.minecraft.client.multiplayer.chat.ChatListener
- net.minecraft.client.multiplayer.chat.ChatListener$Message
+ net.minecraft.client.multiplayer.chat.ChatLog
- net.minecraft.client.multiplayer.chat.ChatTrustLevel
+ net.minecraft.client.multiplayer.chat.ChatTrustLevel$1
- net.minecraft.client.multiplayer.chat.LoggedChatEvent
+ net.minecraft.client.multiplayer.chat.LoggedChatEvent$Type
- net.minecraft.client.multiplayer.chat.LoggedChatMessage
+ net.minecraft.client.multiplayer.chat.LoggedChatMessage$Player
- net.minecraft.client.multiplayer.chat.LoggedChatMessage$System
+ net.minecraft.client.multiplayer.chat.package-info
- net.minecraft.client.multiplayer.chat.report.AbuseReportSender
+ net.minecraft.client.multiplayer.chat.report.AbuseReportSender$1
- net.minecraft.client.multiplayer.chat.report.AbuseReportSender$SendException
+ net.minecraft.client.multiplayer.chat.report.AbuseReportSender$Services
- net.minecraft.client.multiplayer.chat.report.BanReason
+ net.minecraft.client.multiplayer.chat.report.ChatReportBuilder
- net.minecraft.client.multiplayer.chat.report.ChatReportBuilder$CannotBuildReason
+ net.minecraft.client.multiplayer.chat.report.ChatReportBuilder$ChatReport
- net.minecraft.client.multiplayer.chat.report.ChatReportBuilder$Result
+ net.minecraft.client.multiplayer.chat.report.ChatReportContextBuilder
- net.minecraft.client.multiplayer.chat.report.ChatReportContextBuilder$Collector
+ net.minecraft.client.multiplayer.chat.report.ChatReportContextBuilder$Handler
- net.minecraft.client.multiplayer.chat.report.package-info
- net.minecraft.client.multiplayer.chat.report.ReportEnvironment
+ net.minecraft.client.multiplayer.chat.report.ReportEnvironment$Server
- net.minecraft.client.multiplayer.chat.report.ReportEnvironment$Server$Realm
+ net.minecraft.client.multiplayer.chat.report.ReportEnvironment$Server$ThirdParty
+ net.minecraft.client.multiplayer.chat.report.ReportingContext
- net.minecraft.client.multiplayer.chat.report.ReportReason
+ net.minecraft.client.multiplayer.ClientAdvancements
- net.minecraft.client.multiplayer.ClientAdvancements$Listener
+ net.minecraft.client.multiplayer.ClientChunkCache
- net.minecraft.client.multiplayer.ClientChunkCache$Storage
+ net.minecraft.client.multiplayer.ClientHandshakePacketListenerImpl
- net.minecraft.client.multiplayer.ClientLevel
+ net.minecraft.client.multiplayer.ClientLevel$1
- net.minecraft.client.multiplayer.ClientLevel$ClientLevelData
+ net.minecraft.client.multiplayer.ClientLevel$EntityCallbacks
- net.minecraft.client.multiplayer.ClientPacketListener
+ net.minecraft.client.multiplayer.ClientPacketListener$1
- net.minecraft.client.multiplayer.ClientPacketListener$DeferredPacket
+ net.minecraft.client.multiplayer.ClientRegistryLayer
- net.minecraft.client.multiplayer.ClientSuggestionProvider
+ net.minecraft.client.multiplayer.ClientSuggestionProvider$1
- net.minecraft.client.multiplayer.MultiPlayerGameMode
+ net.minecraft.client.multiplayer.package-info
+ net.minecraft.client.multiplayer.PlayerInfo
- net.minecraft.client.multiplayer.prediction.BlockStatePredictionHandler
+ net.minecraft.client.multiplayer.prediction.BlockStatePredictionHandler$ServerVerifiedState
+ net.minecraft.client.multiplayer.prediction.package-info
- net.minecraft.client.multiplayer.prediction.PredictiveAction
- net.minecraft.client.multiplayer.ProfileKeyPairManager
+ net.minecraft.client.multiplayer.ProfileKeyPairManager$1
- net.minecraft.client.multiplayer.resolver.AddressCheck
+ net.minecraft.client.multiplayer.resolver.AddressCheck$1
- net.minecraft.client.multiplayer.resolver.package-info
- net.minecraft.client.multiplayer.resolver.ResolvedServerAddress
+ net.minecraft.client.multiplayer.resolver.ResolvedServerAddress$1
- net.minecraft.client.multiplayer.resolver.ServerAddress
+ net.minecraft.client.multiplayer.resolver.ServerAddressResolver
- net.minecraft.client.multiplayer.resolver.ServerNameResolver
+ net.minecraft.client.multiplayer.resolver.ServerRedirectHandler
- net.minecraft.client.multiplayer.ServerData
+ net.minecraft.client.multiplayer.ServerData$ServerPackStatus
- net.minecraft.client.multiplayer.ServerList
+ net.minecraft.client.multiplayer.ServerStatusPinger
- net.minecraft.client.multiplayer.ServerStatusPinger$1
+ net.minecraft.client.multiplayer.ServerStatusPinger$2
- net.minecraft.client.multiplayer.ServerStatusPinger$2$1
+ net.minecraft.client.package-info
- net.minecraft.client.particle.AshParticle
+ net.minecraft.client.particle.AshParticle$Provider
- net.minecraft.client.particle.AttackSweepParticle
+ net.minecraft.client.particle.AttackSweepParticle$Provider
- net.minecraft.client.particle.BaseAshSmokeParticle
+ net.minecraft.client.particle.BlockMarker
- net.minecraft.client.particle.BlockMarker$Provider
+ net.minecraft.client.particle.BreakingItemParticle
- net.minecraft.client.particle.BreakingItemParticle$Provider
+ net.minecraft.client.particle.BreakingItemParticle$SlimeProvider
- net.minecraft.client.particle.BreakingItemParticle$SnowballProvider
+ net.minecraft.client.particle.BubbleColumnUpParticle
- net.minecraft.client.particle.BubbleColumnUpParticle$Provider
+ net.minecraft.client.particle.BubbleParticle
- net.minecraft.client.particle.BubbleParticle$Provider
+ net.minecraft.client.particle.BubblePopParticle
- net.minecraft.client.particle.BubblePopParticle$Provider
+ net.minecraft.client.particle.CampfireSmokeParticle
- net.minecraft.client.particle.CampfireSmokeParticle$CosyProvider
+ net.minecraft.client.particle.CampfireSmokeParticle$SignalProvider
- net.minecraft.client.particle.CherryParticle
+ net.minecraft.client.particle.CritParticle
- net.minecraft.client.particle.CritParticle$DamageIndicatorProvider
+ net.minecraft.client.particle.CritParticle$MagicProvider
- net.minecraft.client.particle.CritParticle$Provider
+ net.minecraft.client.particle.DragonBreathParticle
- net.minecraft.client.particle.DragonBreathParticle$Provider
+ net.minecraft.client.particle.DripParticle
- net.minecraft.client.particle.DripParticle$CoolingDripHangParticle
+ net.minecraft.client.particle.DripParticle$DripHangParticle
- net.minecraft.client.particle.DripParticle$DripLandParticle
+ net.minecraft.client.particle.DripParticle$DripstoneFallAndLandParticle
- net.minecraft.client.particle.DripParticle$FallAndLandParticle
+ net.minecraft.client.particle.DripParticle$FallingParticle
- net.minecraft.client.particle.DripParticle$HoneyFallAndLandParticle
+ net.minecraft.client.particle.DustColorTransitionParticle
- net.minecraft.client.particle.DustColorTransitionParticle$Provider
+ net.minecraft.client.particle.DustParticle
- net.minecraft.client.particle.DustParticle$Provider
+ net.minecraft.client.particle.DustParticleBase
- net.minecraft.client.particle.EnchantmentTableParticle
+ net.minecraft.client.particle.EnchantmentTableParticle$NautilusProvider
- net.minecraft.client.particle.EnchantmentTableParticle$Provider
+ net.minecraft.client.particle.EndRodParticle
- net.minecraft.client.particle.EndRodParticle$Provider
+ net.minecraft.client.particle.ExplodeParticle
- net.minecraft.client.particle.ExplodeParticle$Provider
+ net.minecraft.client.particle.FallingDustParticle
- net.minecraft.client.particle.FallingDustParticle$Provider
+ net.minecraft.client.particle.FireworkParticles
- net.minecraft.client.particle.FireworkParticles$1
+ net.minecraft.client.particle.FireworkParticles$FlashProvider
- net.minecraft.client.particle.FireworkParticles$OverlayParticle
+ net.minecraft.client.particle.FireworkParticles$SparkParticle
- net.minecraft.client.particle.FireworkParticles$SparkProvider
+ net.minecraft.client.particle.FireworkParticles$Starter
- net.minecraft.client.particle.FlameParticle
+ net.minecraft.client.particle.FlameParticle$Provider
- net.minecraft.client.particle.FlameParticle$SmallFlameProvider
- net.minecraft.client.particle.FootprintParticle$Provider
+ net.minecraft.client.particle.GlowParticle
- net.minecraft.client.particle.GlowParticle$ElectricSparkProvider
+ net.minecraft.client.particle.GlowParticle$GlowSquidProvider
- net.minecraft.client.particle.GlowParticle$ScrapeProvider
+ net.minecraft.client.particle.GlowParticle$WaxOffProvider
- net.minecraft.client.particle.GlowParticle$WaxOnProvider
+ net.minecraft.client.particle.HeartParticle
- net.minecraft.client.particle.HeartParticle$AngryVillagerProvider
+ net.minecraft.client.particle.HeartParticle$Provider
- net.minecraft.client.particle.HugeExplosionParticle
+ net.minecraft.client.particle.HugeExplosionParticle$Provider
- net.minecraft.client.particle.HugeExplosionSeedParticle
+ net.minecraft.client.particle.HugeExplosionSeedParticle$Provider
- net.minecraft.client.particle.ItemPickupParticle
+ net.minecraft.client.particle.LargeSmokeParticle
- net.minecraft.client.particle.LargeSmokeParticle$Provider
+ net.minecraft.client.particle.LavaParticle
- net.minecraft.client.particle.LavaParticle$Provider
+ net.minecraft.client.particle.MobAppearanceParticle
- net.minecraft.client.particle.MobAppearanceParticle$Provider
+ net.minecraft.client.particle.NoRenderParticle
- net.minecraft.client.particle.NoteParticle
+ net.minecraft.client.particle.NoteParticle$Provider
- net.minecraft.client.particle.package-info
- net.minecraft.client.particle.Particle
+ net.minecraft.client.particle.ParticleDescription
- net.minecraft.client.particle.ParticleEngine
+ net.minecraft.client.particle.ParticleEngine$1ParticleDefinition
- net.minecraft.client.particle.ParticleEngine$MutableSpriteSet
+ net.minecraft.client.particle.ParticleEngine$SpriteParticleRegistration
- net.minecraft.client.particle.ParticleProvider
+ net.minecraft.client.particle.ParticleProvider$Sprite
- net.minecraft.client.particle.ParticleRenderType
+ net.minecraft.client.particle.ParticleRenderType$1
- net.minecraft.client.particle.ParticleRenderType$2
+ net.minecraft.client.particle.ParticleRenderType$3
- net.minecraft.client.particle.ParticleRenderType$4
+ net.minecraft.client.particle.ParticleRenderType$5
- net.minecraft.client.particle.ParticleRenderType$6
+ net.minecraft.client.particle.PlayerCloudParticle
- net.minecraft.client.particle.PlayerCloudParticle$Provider
+ net.minecraft.client.particle.PlayerCloudParticle$SneezeProvider
- net.minecraft.client.particle.PortalParticle
+ net.minecraft.client.particle.PortalParticle$Provider
- net.minecraft.client.particle.ReversePortalParticle
+ net.minecraft.client.particle.ReversePortalParticle$ReversePortalProvider
- net.minecraft.client.particle.RisingParticle
+ net.minecraft.client.particle.SculkChargeParticle
- net.minecraft.client.particle.SculkChargeParticle$Provider
+ net.minecraft.client.particle.SculkChargePopParticle
- net.minecraft.client.particle.SculkChargePopParticle$Provider
+ net.minecraft.client.particle.ShriekParticle
- net.minecraft.client.particle.ShriekParticle$Provider
+ net.minecraft.client.particle.SimpleAnimatedParticle
- net.minecraft.client.particle.SingleQuadParticle
+ net.minecraft.client.particle.SmokeParticle
- net.minecraft.client.particle.SmokeParticle$Provider
+ net.minecraft.client.particle.SnowflakeParticle
- net.minecraft.client.particle.SnowflakeParticle$Provider
+ net.minecraft.client.particle.SonicBoomParticle
- net.minecraft.client.particle.SonicBoomParticle$Provider
+ net.minecraft.client.particle.SoulParticle
- net.minecraft.client.particle.SoulParticle$EmissiveProvider
+ net.minecraft.client.particle.SoulParticle$Provider
- net.minecraft.client.particle.SpellParticle
+ net.minecraft.client.particle.SpellParticle$AmbientMobProvider
- net.minecraft.client.particle.SpellParticle$InstantProvider
+ net.minecraft.client.particle.SpellParticle$MobProvider
- net.minecraft.client.particle.SpellParticle$Provider
+ net.minecraft.client.particle.SpellParticle$WitchProvider
- net.minecraft.client.particle.SpitParticle
+ net.minecraft.client.particle.SpitParticle$Provider
- net.minecraft.client.particle.SplashParticle
+ net.minecraft.client.particle.SplashParticle$Provider
- net.minecraft.client.particle.SpriteSet
+ net.minecraft.client.particle.SquidInkParticle
- net.minecraft.client.particle.SquidInkParticle$GlowInkProvider
+ net.minecraft.client.particle.SquidInkParticle$Provider
- net.minecraft.client.particle.SuspendedParticle
+ net.minecraft.client.particle.SuspendedParticle$CrimsonSporeProvider
- net.minecraft.client.particle.SuspendedParticle$SporeBlossomAirProvider
+ net.minecraft.client.particle.SuspendedParticle$SporeBlossomAirProvider$1
- net.minecraft.client.particle.SuspendedParticle$UnderwaterProvider
+ net.minecraft.client.particle.SuspendedParticle$WarpedSporeProvider
- net.minecraft.client.particle.SuspendedTownParticle
+ net.minecraft.client.particle.SuspendedTownParticle$ComposterFillProvider
- net.minecraft.client.particle.SuspendedTownParticle$DolphinSpeedProvider
+ net.minecraft.client.particle.SuspendedTownParticle$EggCrackProvider
- net.minecraft.client.particle.SuspendedTownParticle$HappyVillagerProvider
+ net.minecraft.client.particle.SuspendedTownParticle$Provider
- net.minecraft.client.particle.TerrainParticle
+ net.minecraft.client.particle.TerrainParticle$Provider
- net.minecraft.client.particle.TextureSheetParticle
+ net.minecraft.client.particle.TotemParticle
- net.minecraft.client.particle.TotemParticle$Provider
+ net.minecraft.client.particle.TrackingEmitter
- net.minecraft.client.particle.VibrationSignalParticle
+ net.minecraft.client.particle.VibrationSignalParticle$Provider
- net.minecraft.client.particle.WakeParticle
+ net.minecraft.client.particle.WakeParticle$Provider
- net.minecraft.client.particle.WaterCurrentDownParticle
+ net.minecraft.client.particle.WaterCurrentDownParticle$Provider
- net.minecraft.client.particle.WaterDropParticle
+ net.minecraft.client.particle.WaterDropParticle$Provider
- net.minecraft.client.particle.WhiteAshParticle
+ net.minecraft.client.particle.WhiteAshParticle$Provider
+ net.minecraft.client.player.AbstractClientPlayer
- net.minecraft.client.player.Input
+ net.minecraft.client.player.KeyboardInput
- net.minecraft.client.player.LocalPlayer
+ net.minecraft.client.renderer.block.BlockModelShaper
- net.minecraft.client.renderer.block.BlockRenderDispatcher
+ net.minecraft.client.renderer.block.BlockRenderDispatcher$1
- net.minecraft.client.renderer.block.LiquidBlockRenderer
+ net.minecraft.client.renderer.block.LiquidBlockRenderer$1
+ net.minecraft.client.renderer.block.model.BakedQuad
- net.minecraft.client.renderer.block.model.BlockElement
+ net.minecraft.client.renderer.block.model.BlockElement$1
- net.minecraft.client.renderer.block.model.BlockElement$Deserializer
+ net.minecraft.client.renderer.block.model.BlockElementFace
- net.minecraft.client.renderer.block.model.BlockElementFace$Deserializer
+ net.minecraft.client.renderer.block.model.BlockElementRotation
- net.minecraft.client.renderer.block.model.BlockFaceUV
+ net.minecraft.client.renderer.block.model.BlockFaceUV$Deserializer
- net.minecraft.client.renderer.block.model.BlockModel
+ net.minecraft.client.renderer.block.model.BlockModel$Deserializer
- net.minecraft.client.renderer.block.model.BlockModel$GuiLight
+ net.minecraft.client.renderer.block.model.BlockModel$LoopException
- net.minecraft.client.renderer.block.model.BlockModelDefinition
+ net.minecraft.client.renderer.block.model.BlockModelDefinition$Context
- net.minecraft.client.renderer.block.model.BlockModelDefinition$Deserializer
+ net.minecraft.client.renderer.block.model.BlockModelDefinition$MissingVariantException
- net.minecraft.client.renderer.block.model.FaceBakery
+ net.minecraft.client.renderer.block.model.FaceBakery$1
- net.minecraft.client.renderer.block.model.ItemModelGenerator
+ net.minecraft.client.renderer.block.model.ItemModelGenerator$1
- net.minecraft.client.renderer.block.model.ItemModelGenerator$Span
+ net.minecraft.client.renderer.block.model.ItemModelGenerator$SpanFacing
- net.minecraft.client.renderer.block.model.ItemOverride
+ net.minecraft.client.renderer.block.model.ItemOverride$Deserializer
- net.minecraft.client.renderer.block.model.ItemOverride$Predicate
+ net.minecraft.client.renderer.block.model.ItemOverrides
- net.minecraft.client.renderer.block.model.ItemOverrides$BakedOverride
+ net.minecraft.client.renderer.block.model.ItemOverrides$PropertyMatcher
- net.minecraft.client.renderer.block.model.ItemTransform
+ net.minecraft.client.renderer.block.model.ItemTransform$Deserializer
- net.minecraft.client.renderer.block.model.ItemTransforms
+ net.minecraft.client.renderer.block.model.ItemTransforms$1
- net.minecraft.client.renderer.block.model.ItemTransforms$Deserializer
+ net.minecraft.client.renderer.block.model.multipart.AndCondition
- net.minecraft.client.renderer.block.model.multipart.Condition
+ net.minecraft.client.renderer.block.model.multipart.KeyValueCondition
- net.minecraft.client.renderer.block.model.multipart.MultiPart
+ net.minecraft.client.renderer.block.model.multipart.MultiPart$Deserializer
- net.minecraft.client.renderer.block.model.multipart.OrCondition
+ net.minecraft.client.renderer.block.model.multipart.package-info
+ net.minecraft.client.renderer.block.model.multipart.Selector
- net.minecraft.client.renderer.block.model.multipart.Selector$Deserializer
+ net.minecraft.client.renderer.block.model.MultiVariant
- net.minecraft.client.renderer.block.model.MultiVariant$Deserializer
- net.minecraft.client.renderer.block.model.package-info
+ net.minecraft.client.renderer.block.model.Variant
- net.minecraft.client.renderer.block.model.Variant$Deserializer
- net.minecraft.client.renderer.block.ModelBlockRenderer
+ net.minecraft.client.renderer.block.ModelBlockRenderer$1
- net.minecraft.client.renderer.block.ModelBlockRenderer$AdjacencyInfo
+ net.minecraft.client.renderer.block.ModelBlockRenderer$AmbientOcclusionFace
- net.minecraft.client.renderer.block.ModelBlockRenderer$AmbientVertexRemap
+ net.minecraft.client.renderer.block.ModelBlockRenderer$Cache
- net.minecraft.client.renderer.block.ModelBlockRenderer$Cache$1
+ net.minecraft.client.renderer.block.ModelBlockRenderer$Cache$2
- net.minecraft.client.renderer.block.ModelBlockRenderer$SizeInfo
+ net.minecraft.client.renderer.block.package-info
- net.minecraft.client.renderer.blockentity.BannerRenderer
+ net.minecraft.client.renderer.blockentity.BeaconRenderer
- net.minecraft.client.renderer.blockentity.BedRenderer
+ net.minecraft.client.renderer.blockentity.BellRenderer
- net.minecraft.client.renderer.blockentity.BlockEntityRenderDispatcher
+ net.minecraft.client.renderer.blockentity.BlockEntityRenderer
- net.minecraft.client.renderer.blockentity.BlockEntityRendererProvider
+ net.minecraft.client.renderer.blockentity.BlockEntityRendererProvider$Context
- net.minecraft.client.renderer.blockentity.BlockEntityRenderers
+ net.minecraft.client.renderer.blockentity.BrightnessCombiner
- net.minecraft.client.renderer.blockentity.BrushableBlockRenderer
+ net.minecraft.client.renderer.blockentity.BrushableBlockRenderer$1
- net.minecraft.client.renderer.blockentity.CampfireRenderer
+ net.minecraft.client.renderer.blockentity.ChestRenderer
- net.minecraft.client.renderer.blockentity.ConduitRenderer
+ net.minecraft.client.renderer.blockentity.DecoratedPotRenderer
- net.minecraft.client.renderer.blockentity.EnchantTableRenderer
+ net.minecraft.client.renderer.blockentity.HangingSignRenderer
- net.minecraft.client.renderer.blockentity.HangingSignRenderer$HangingSignModel
+ net.minecraft.client.renderer.blockentity.LecternRenderer
- net.minecraft.client.renderer.blockentity.package-info
- net.minecraft.client.renderer.blockentity.PistonHeadRenderer
+ net.minecraft.client.renderer.blockentity.ShulkerBoxRenderer
- net.minecraft.client.renderer.blockentity.SignRenderer
+ net.minecraft.client.renderer.blockentity.SignRenderer$SignModel
- net.minecraft.client.renderer.blockentity.SkullBlockRenderer
+ net.minecraft.client.renderer.blockentity.SpawnerRenderer
- net.minecraft.client.renderer.blockentity.StructureBlockRenderer
+ net.minecraft.client.renderer.blockentity.StructureBlockRenderer$1
- net.minecraft.client.renderer.blockentity.TheEndGatewayRenderer
+ net.minecraft.client.renderer.blockentity.TheEndPortalRenderer
+ net.minecraft.client.renderer.chunk.ChunkRenderDispatcher
- net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$ChunkTaskResult
+ net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$CompiledChunk
- net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$CompiledChunk$1
+ net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$RenderChunk
- net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$RenderChunk$ChunkCompileTask
+ net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$RenderChunk$RebuildTask
- net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$RenderChunk$RebuildTask$CompileResults
+ net.minecraft.client.renderer.chunk.ChunkRenderDispatcher$RenderChunk$ResortTransparencyTask
+ net.minecraft.client.renderer.chunk.package-info
- net.minecraft.client.renderer.chunk.RenderChunk
+ net.minecraft.client.renderer.chunk.RenderChunkRegion
- net.minecraft.client.renderer.chunk.RenderRegionCache
+ net.minecraft.client.renderer.chunk.RenderRegionCache$ChunkInfo
- net.minecraft.client.renderer.chunk.VisGraph
+ net.minecraft.client.renderer.chunk.VisGraph$1
- net.minecraft.client.renderer.chunk.VisibilitySet
- net.minecraft.client.renderer.culling.Frustum
+ net.minecraft.client.renderer.culling.package-info
- net.minecraft.client.renderer.debug.BeeDebugRenderer
+ net.minecraft.client.renderer.debug.BeeDebugRenderer$BeeInfo
- net.minecraft.client.renderer.debug.BeeDebugRenderer$HiveInfo
+ net.minecraft.client.renderer.debug.BrainDebugRenderer
- net.minecraft.client.renderer.debug.BrainDebugRenderer$BrainDump
+ net.minecraft.client.renderer.debug.BrainDebugRenderer$PoiInfo
- net.minecraft.client.renderer.debug.ChunkBorderRenderer
+ net.minecraft.client.renderer.debug.ChunkDebugRenderer
- net.minecraft.client.renderer.debug.ChunkDebugRenderer$ChunkData
+ net.minecraft.client.renderer.debug.CollisionBoxRenderer
- net.minecraft.client.renderer.debug.DebugRenderer
+ net.minecraft.client.renderer.debug.DebugRenderer$SimpleDebugRenderer
- net.minecraft.client.renderer.debug.GameEventListenerRenderer
+ net.minecraft.client.renderer.debug.GameEventListenerRenderer$TrackedGameEvent
- net.minecraft.client.renderer.debug.GameEventListenerRenderer$TrackedListener
+ net.minecraft.client.renderer.debug.GameTestDebugRenderer
- net.minecraft.client.renderer.debug.GameTestDebugRenderer$Marker
+ net.minecraft.client.renderer.debug.GoalSelectorDebugRenderer
- net.minecraft.client.renderer.debug.GoalSelectorDebugRenderer$DebugGoal
+ net.minecraft.client.renderer.debug.HeightMapRenderer
- net.minecraft.client.renderer.debug.HeightMapRenderer$1
+ net.minecraft.client.renderer.debug.LightDebugRenderer
- net.minecraft.client.renderer.debug.NeighborsUpdateRenderer
- net.minecraft.client.renderer.debug.package-info
+ net.minecraft.client.renderer.debug.PathfindingRenderer
- net.minecraft.client.renderer.debug.RaidDebugRenderer
+ net.minecraft.client.renderer.debug.SolidFaceRenderer
- net.minecraft.client.renderer.debug.StructureRenderer
+ net.minecraft.client.renderer.debug.VillageSectionsDebugRenderer
- net.minecraft.client.renderer.debug.WaterDebugRenderer
+ net.minecraft.client.renderer.debug.WorldGenAttemptRenderer
- net.minecraft.client.renderer.DimensionSpecialEffects$MoonEffects
+ net.minecraft.client.renderer.DimensionSpecialEffects$NetherEffects
- net.minecraft.client.renderer.DimensionSpecialEffects$OverworldEffects
+ net.minecraft.client.renderer.DimensionSpecialEffects$SkyType
- net.minecraft.client.renderer.EffectInstance
+ net.minecraft.client.renderer.entity.AbstractHorseRenderer
- net.minecraft.client.renderer.entity.AbstractZombieRenderer
+ net.minecraft.client.renderer.entity.AllayRenderer
- net.minecraft.client.renderer.entity.ArmorStandRenderer
+ net.minecraft.client.renderer.entity.ArrowRenderer
- net.minecraft.client.renderer.entity.AxolotlRenderer
+ net.minecraft.client.renderer.entity.BatRenderer
- net.minecraft.client.renderer.entity.BeeRenderer
+ net.minecraft.client.renderer.entity.BlazeRenderer
- net.minecraft.client.renderer.entity.BoatRenderer
+ net.minecraft.client.renderer.entity.CamelRenderer
- net.minecraft.client.renderer.entity.CatRenderer
+ net.minecraft.client.renderer.entity.CaveSpiderRenderer
- net.minecraft.client.renderer.entity.ChestedHorseRenderer
+ net.minecraft.client.renderer.entity.ChickenRenderer
- net.minecraft.client.renderer.entity.CodRenderer
+ net.minecraft.client.renderer.entity.CowRenderer
- net.minecraft.client.renderer.entity.CreeperRenderer
+ net.minecraft.client.renderer.entity.DisplayRenderer
- net.minecraft.client.renderer.entity.DisplayRenderer$1
+ net.minecraft.client.renderer.entity.DisplayRenderer$BlockDisplayRenderer
- net.minecraft.client.renderer.entity.DisplayRenderer$ItemDisplayRenderer
- net.minecraft.client.renderer.entity.layers.CapeLayer
+ net.minecraft.client.renderer.entity.layers.CarriedBlockLayer
- net.minecraft.client.renderer.entity.layers.CatCollarLayer
+ net.minecraft.client.renderer.entity.layers.CreeperPowerLayer
- net.minecraft.client.renderer.entity.layers.CrossedArmsItemLayer
- net.minecraft.client.renderer.entity.layers.MustacheLayer
+ net.minecraft.client.renderer.entity.layers.PandaHoldsItemLayer
- net.minecraft.client.renderer.entity.layers.ParrotOnShoulderLayer
+ net.minecraft.client.renderer.entity.layers.PhantomEyesLayer
- net.minecraft.client.renderer.entity.layers.PlayerItemInHandLayer
+ net.minecraft.client.renderer.entity.layers.RenderLayer
- net.minecraft.client.renderer.entity.layers.SaddleLayer
+ net.minecraft.client.renderer.entity.layers.SheepFurLayer
- net.minecraft.client.renderer.entity.layers.ShulkerHeadLayer
+ net.minecraft.client.renderer.entity.layers.SlimeOuterLayer
- net.minecraft.client.renderer.entity.layers.SnowGolemHeadLayer
+ net.minecraft.client.renderer.entity.layers.SpiderEyesLayer
- net.minecraft.client.renderer.entity.layers.SpinAttackEffectLayer
+ net.minecraft.client.renderer.entity.layers.StrayClothingLayer
- net.minecraft.client.renderer.entity.layers.StuckInBodyLayer
- net.minecraft.client.renderer.entity.MoonCowRenderer
+ net.minecraft.client.renderer.entity.MushroomCowRenderer
- net.minecraft.client.renderer.entity.NoopRenderer
+ net.minecraft.client.renderer.entity.OcelotRenderer
- net.minecraft.client.renderer.entity.PaintingRenderer
+ net.minecraft.client.renderer.entity.PandaRenderer
- net.minecraft.client.renderer.entity.ParrotRenderer
+ net.minecraft.client.renderer.entity.ParrotRenderer$1
- net.minecraft.client.renderer.entity.PhantomRenderer
- net.minecraft.client.renderer.entity.PiglinRenderer
+ net.minecraft.client.renderer.entity.PigRenderer
+ net.minecraft.client.renderer.entity.PillagerRenderer
+ net.minecraft.client.renderer.entity.player.package-info
- net.minecraft.client.renderer.entity.player.PlayerRenderer$PlayerArmorModel
- net.minecraft.client.renderer.entity.PolarBearRenderer
+ net.minecraft.client.renderer.entity.PufferfishRenderer
- net.minecraft.client.renderer.entity.RabbitRenderer
+ net.minecraft.client.renderer.entity.RabbitRenderer$1
- net.minecraft.client.renderer.entity.RavagerRenderer
- net.minecraft.client.renderer.entity.StencilRenderer$Triangle
+ net.minecraft.client.renderer.FaceInfo
- net.minecraft.client.renderer.FaceInfo$Constants
+ net.minecraft.client.renderer.FaceInfo$VertexInfo
- net.minecraft.client.renderer.FogRenderer
+ net.minecraft.client.renderer.FogRenderer$BlindnessFogFunction
- net.minecraft.client.renderer.FogRenderer$DarknessFogFunction
+ net.minecraft.client.renderer.FogRenderer$FogData
- net.minecraft.client.renderer.FogRenderer$FogMode
+ net.minecraft.client.renderer.FogRenderer$MobEffectFogFunction
- net.minecraft.client.renderer.GameRenderer
+ net.minecraft.client.renderer.GameRenderer$1
- net.minecraft.client.renderer.GameRenderer$ResourceCache
+ net.minecraft.client.renderer.GpuWarnlistManager
- net.minecraft.client.renderer.GpuWarnlistManager$Preparations
- net.minecraft.client.renderer.item.ClampedItemPropertyFunction
+ net.minecraft.client.renderer.item.CompassItemPropertyFunction
- net.minecraft.client.renderer.item.CompassItemPropertyFunction$CompassTarget
+ net.minecraft.client.renderer.item.CompassItemPropertyFunction$CompassWobble
- net.minecraft.client.renderer.item.ItemProperties
+ net.minecraft.client.renderer.item.ItemProperties$1
- net.minecraft.client.renderer.item.ItemPropertyFunction
+ net.minecraft.client.renderer.item.package-info
+ net.minecraft.client.renderer.ItemBlockRenderTypes
- net.minecraft.client.renderer.ItemInHandRenderer
+ net.minecraft.client.renderer.ItemInHandRenderer$1
- net.minecraft.client.renderer.ItemInHandRenderer$HandRenderSelection
+ net.minecraft.client.renderer.ItemModelShaper
- net.minecraft.client.renderer.LevelRenderer
+ net.minecraft.client.renderer.LevelRenderer$RenderChunkInfo
- net.minecraft.client.renderer.LevelRenderer$RenderChunkStorage
+ net.minecraft.client.renderer.LevelRenderer$RenderInfoMap
- net.minecraft.client.renderer.LevelRenderer$TransparencyShaderException
+ net.minecraft.client.renderer.LightTexture
- net.minecraft.client.renderer.MultiBufferSource
+ net.minecraft.client.renderer.MultiBufferSource$BufferSource
- net.minecraft.client.renderer.OutlineBufferSource
+ net.minecraft.client.renderer.OutlineBufferSource$EntityOutlineGenerator
- net.minecraft.client.renderer.package-info
- net.minecraft.client.renderer.PanoramaRenderer
+ net.minecraft.client.renderer.PostChain
- net.minecraft.client.renderer.PostPass
+ net.minecraft.client.renderer.Rect2i
- net.minecraft.client.renderer.RenderBuffers
+ net.minecraft.client.renderer.RenderStateShard
- net.minecraft.client.renderer.RenderStateShard$BooleanStateShard
+ net.minecraft.client.renderer.RenderStateShard$CullStateShard
- net.minecraft.client.renderer.RenderStateShard$DepthTestStateShard
+ net.minecraft.client.renderer.RenderStateShard$EmptyTextureStateShard
- net.minecraft.client.renderer.RenderStateShard$LayeringStateShard
+ net.minecraft.client.renderer.RenderStateShard$LightmapStateShard
- net.minecraft.client.renderer.RenderStateShard$LineStateShard
+ net.minecraft.client.renderer.RenderStateShard$MultiTextureStateShard
- net.minecraft.client.renderer.RenderStateShard$MultiTextureStateShard$Builder
+ net.minecraft.client.renderer.RenderStateShard$OffsetTexturingStateShard
- net.minecraft.client.renderer.RenderStateShard$OutputStateShard
+ net.minecraft.client.renderer.RenderStateShard$OverlayStateShard
- net.minecraft.client.renderer.RenderStateShard$ShaderStateShard
+ net.minecraft.client.renderer.RenderStateShard$TextureStateShard
- net.minecraft.client.renderer.RenderStateShard$TexturingStateShard
+ net.minecraft.client.renderer.RenderStateShard$TransparencyStateShard
- net.minecraft.client.renderer.RenderStateShard$WriteMaskStateShard
+ net.minecraft.client.renderer.RenderType
- net.minecraft.client.renderer.RenderType$CompositeRenderType
+ net.minecraft.client.renderer.RenderType$CompositeState
- net.minecraft.client.renderer.RenderType$CompositeState$CompositeStateBuilder
+ net.minecraft.client.renderer.RenderType$OutlineProperty
- net.minecraft.client.renderer.RunningTrimmedMean
+ net.minecraft.client.renderer.ScreenEffectRenderer
- net.minecraft.client.renderer.ShaderInstance
+ net.minecraft.client.renderer.ShaderInstance$1
- net.minecraft.client.renderer.Sheets
+ net.minecraft.client.renderer.Sheets$1
- net.minecraft.client.renderer.SpriteCoordinateExpander
+ net.minecraft.client.renderer.texture.AbstractTexture
- net.minecraft.client.renderer.texture.atlas.package-info
+ net.minecraft.client.renderer.texture.atlas.sources.DirectoryLister
- net.minecraft.client.renderer.texture.atlas.sources.LazyLoadedImage
- net.minecraft.client.renderer.texture.atlas.sources.package-info
+ net.minecraft.client.renderer.texture.atlas.sources.PalettedPermutations
- net.minecraft.client.renderer.texture.atlas.sources.PalettedPermutations$PalettedSpriteSupplier
+ net.minecraft.client.renderer.texture.atlas.sources.SingleFile
- net.minecraft.client.renderer.texture.atlas.sources.SourceFilter
+ net.minecraft.client.renderer.texture.atlas.sources.Unstitcher
- net.minecraft.client.renderer.texture.atlas.sources.Unstitcher$Region
+ net.minecraft.client.renderer.texture.atlas.sources.Unstitcher$RegionInstance
+ net.minecraft.client.renderer.texture.atlas.SpriteResourceLoader
- net.minecraft.client.renderer.texture.atlas.SpriteResourceLoader$1
+ net.minecraft.client.renderer.texture.atlas.SpriteSource
- net.minecraft.client.renderer.texture.atlas.SpriteSource$Output
+ net.minecraft.client.renderer.texture.atlas.SpriteSource$SpriteSupplier
+ net.minecraft.client.renderer.texture.atlas.SpriteSources
- net.minecraft.client.renderer.texture.atlas.SpriteSourceType
- net.minecraft.client.renderer.texture.Dumpable
+ net.minecraft.client.renderer.texture.DynamicTexture
- net.minecraft.client.renderer.texture.HttpTexture
+ net.minecraft.client.renderer.texture.MipmapGenerator
- net.minecraft.client.renderer.texture.MissingTextureAtlasSprite
+ net.minecraft.client.renderer.texture.OverlayTexture
+ net.minecraft.client.renderer.texture.package-info
- net.minecraft.client.renderer.texture.PreloadedTexture
+ net.minecraft.client.renderer.texture.SimpleTexture
- net.minecraft.client.renderer.texture.SimpleTexture$TextureImage
+ net.minecraft.client.renderer.texture.SpriteContents
- net.minecraft.client.renderer.texture.SpriteContents$AnimatedTexture
+ net.minecraft.client.renderer.texture.SpriteContents$FrameInfo
- net.minecraft.client.renderer.texture.SpriteContents$InterpolationData
+ net.minecraft.client.renderer.texture.SpriteContents$Ticker
- net.minecraft.client.renderer.texture.SpriteLoader
+ net.minecraft.client.renderer.texture.SpriteLoader$Preparations
- net.minecraft.client.renderer.texture.SpriteTicker
+ net.minecraft.client.renderer.texture.Stitcher
- net.minecraft.client.renderer.texture.Stitcher$Entry
+ net.minecraft.client.renderer.texture.Stitcher$Holder
- net.minecraft.client.renderer.texture.Stitcher$Region
+ net.minecraft.client.renderer.texture.Stitcher$SpriteLoader
- net.minecraft.client.renderer.texture.StitcherException
+ net.minecraft.client.renderer.texture.TextureAtlas
- net.minecraft.client.renderer.texture.TextureAtlasSprite
+ net.minecraft.client.renderer.texture.TextureAtlasSprite$1
- net.minecraft.client.renderer.texture.TextureAtlasSprite$Ticker
+ net.minecraft.client.renderer.texture.TextureManager
- net.minecraft.client.renderer.texture.Tickable
+ net.minecraft.client.renderer.ViewArea
- net.minecraft.client.renderer.VirtualScreen
- net.minecraft.client.resources.ClientPackSource
+ net.minecraft.client.resources.DefaultPlayerSkin
- net.minecraft.client.resources.DefaultPlayerSkin$ModelType
+ net.minecraft.client.resources.DefaultPlayerSkin$SkinType
- net.minecraft.client.resources.DownloadedPackSource
+ net.minecraft.client.resources.FoliageColorReloadListener
- net.minecraft.client.resources.GrassColorReloadListener
+ net.minecraft.client.resources.IndexedAssetSource
+ net.minecraft.client.resources.language.ClientLanguage
- net.minecraft.client.resources.language.FormattedBidiReorder
+ net.minecraft.client.resources.language.I18n
- net.minecraft.client.resources.language.LanguageInfo
+ net.minecraft.client.resources.language.LanguageManager
- net.minecraft.client.resources.language.package-info
- net.minecraft.client.resources.LegacyStuffWrapper
+ net.minecraft.client.resources.metadata.animation.AnimationFrame
- net.minecraft.client.resources.metadata.animation.AnimationMetadataSection
+ net.minecraft.client.resources.metadata.animation.AnimationMetadataSection$1
- net.minecraft.client.resources.metadata.animation.AnimationMetadataSection$FrameOutput
+ net.minecraft.client.resources.metadata.animation.AnimationMetadataSectionSerializer
- net.minecraft.client.resources.metadata.animation.FrameSize
- net.minecraft.client.resources.metadata.animation.package-info
+ net.minecraft.client.resources.metadata.animation.VillagerMetaDataSection
- net.minecraft.client.resources.metadata.animation.VillagerMetaDataSection$Hat
+ net.minecraft.client.resources.metadata.animation.VillagerMetadataSectionSerializer
+ net.minecraft.client.resources.metadata.language.LanguageMetadataSection
- net.minecraft.client.resources.metadata.language.package-info
+ net.minecraft.client.resources.metadata.package-info
- net.minecraft.client.resources.metadata.texture.package-info
- net.minecraft.client.resources.metadata.texture.TextureMetadataSection
+ net.minecraft.client.resources.metadata.texture.TextureMetadataSectionSerializer
+ net.minecraft.client.resources.MobEffectTextureManager
+ net.minecraft.client.resources.model.AtlasSet
- net.minecraft.client.resources.model.AtlasSet$AtlasEntry
+ net.minecraft.client.resources.model.AtlasSet$StitchResult
- net.minecraft.client.resources.model.BakedModel
+ net.minecraft.client.resources.model.BlockModelRotation
- net.minecraft.client.resources.model.BuiltInModel
+ net.minecraft.client.resources.model.Material
- net.minecraft.client.resources.model.ModelBaker
+ net.minecraft.client.resources.model.ModelBakery
- net.minecraft.client.resources.model.ModelBakery$BakedCacheKey
+ net.minecraft.client.resources.model.ModelBakery$BlockStateDefinitionException
- net.minecraft.client.resources.model.ModelBakery$LoadedJson
+ net.minecraft.client.resources.model.ModelBakery$ModelBakerImpl
- net.minecraft.client.resources.model.ModelBakery$ModelGroupKey
+ net.minecraft.client.resources.model.ModelManager
- net.minecraft.client.resources.model.ModelManager$ReloadState
+ net.minecraft.client.resources.model.ModelResourceLocation
- net.minecraft.client.resources.model.ModelState
+ net.minecraft.client.resources.model.MultiPartBakedModel
- net.minecraft.client.resources.model.MultiPartBakedModel$Builder
- net.minecraft.client.resources.model.package-info
+ net.minecraft.client.resources.model.SimpleBakedModel
- net.minecraft.client.resources.model.SimpleBakedModel$Builder
+ net.minecraft.client.resources.model.UnbakedModel
- net.minecraft.client.resources.model.WeightedBakedModel
+ net.minecraft.client.resources.model.WeightedBakedModel$Builder
+ net.minecraft.client.resources.package-info
- net.minecraft.client.resources.PaintingTextureManager
+ net.minecraft.client.resources.SkinManager
- net.minecraft.client.resources.SkinManager$1
+ net.minecraft.client.resources.SkinManager$2
- net.minecraft.client.resources.SkinManager$SkinTextureCallback
- net.minecraft.client.resources.sounds.AbstractSoundInstance
+ net.minecraft.client.resources.sounds.AbstractTickableSoundInstance
- net.minecraft.client.resources.sounds.AmbientSoundHandler
+ net.minecraft.client.resources.sounds.BeeAggressiveSoundInstance
- net.minecraft.client.resources.sounds.BeeFlyingSoundInstance
+ net.minecraft.client.resources.sounds.BeeSoundInstance
- net.minecraft.client.resources.sounds.BiomeAmbientSoundsHandler
+ net.minecraft.client.resources.sounds.BiomeAmbientSoundsHandler$LoopSoundInstance
- net.minecraft.client.resources.sounds.BubbleColumnAmbientSoundHandler
+ net.minecraft.client.resources.sounds.ElytraOnPlayerSoundInstance
- net.minecraft.client.resources.sounds.EntityBoundSoundInstance
+ net.minecraft.client.resources.sounds.GuardianAttackSoundInstance
- net.minecraft.client.resources.sounds.MinecartSoundInstance
+ net.minecraft.client.resources.sounds.package-info
+ net.minecraft.client.resources.sounds.RidingMinecartSoundInstance
- net.minecraft.client.resources.sounds.SimpleSoundInstance
+ net.minecraft.client.resources.sounds.SnifferSoundInstance
- net.minecraft.client.resources.sounds.Sound
+ net.minecraft.client.resources.sounds.Sound$Type
- net.minecraft.client.resources.sounds.SoundEventRegistration
+ net.minecraft.client.resources.sounds.SoundEventRegistrationSerializer
- net.minecraft.client.resources.sounds.SoundInstance
+ net.minecraft.client.resources.sounds.SoundInstance$Attenuation
- net.minecraft.client.resources.sounds.TickableSoundInstance
+ net.minecraft.client.resources.sounds.UnderwaterAmbientSoundHandler
- net.minecraft.client.resources.sounds.UnderwaterAmbientSoundInstances
+ net.minecraft.client.resources.sounds.UnderwaterAmbientSoundInstances$SubSound
- net.minecraft.client.resources.sounds.UnderwaterAmbientSoundInstances$UnderwaterAmbientSoundInstance
+ net.minecraft.client.resources.SplashManager
- net.minecraft.client.resources.TextureAtlasHolder
- net.minecraft.client.searchtree.FullTextSearchTree
+ net.minecraft.client.searchtree.IdSearchTree
- net.minecraft.client.searchtree.IntersectionIterator
+ net.minecraft.client.searchtree.MergingUniqueIterator
+ net.minecraft.client.searchtree.package-info
- net.minecraft.client.searchtree.PlainTextSearchTree
+ net.minecraft.client.searchtree.RefreshableSearchTree
- net.minecraft.client.searchtree.ResourceLocationSearchTree
+ net.minecraft.client.searchtree.ResourceLocationSearchTree$1
- net.minecraft.client.searchtree.ResourceLocationSearchTree$2
+ net.minecraft.client.searchtree.SearchRegistry
- net.minecraft.client.searchtree.SearchRegistry$Key
+ net.minecraft.client.searchtree.SearchRegistry$TreeBuilderSupplier
- net.minecraft.client.searchtree.SearchRegistry$TreeEntry
+ net.minecraft.client.searchtree.SearchTree
- net.minecraft.client.searchtree.SuffixArray
- net.minecraft.client.server.IntegratedPlayerList
+ net.minecraft.client.server.IntegratedServer
- net.minecraft.client.server.LanServer
+ net.minecraft.client.server.LanServerDetection
- net.minecraft.client.server.LanServerDetection$LanServerDetector
+ net.minecraft.client.server.LanServerDetection$LanServerList
- net.minecraft.client.server.LanServerPinger
+ net.minecraft.client.server.package-info
- net.minecraft.client.sounds.AudioStream
+ net.minecraft.client.sounds.ChannelAccess
- net.minecraft.client.sounds.ChannelAccess$ChannelHandle
+ net.minecraft.client.sounds.LoopingAudioStream
- net.minecraft.client.sounds.LoopingAudioStream$AudioStreamProvider
+ net.minecraft.client.sounds.LoopingAudioStream$NoCloseBuffer
- net.minecraft.client.sounds.MusicManager
+ net.minecraft.client.sounds.package-info
+ net.minecraft.client.sounds.SoundBufferLibrary
- net.minecraft.client.sounds.SoundEngine
+ net.minecraft.client.sounds.SoundEngine$DeviceCheckState
- net.minecraft.client.sounds.SoundEngineExecutor
+ net.minecraft.client.sounds.SoundEventListener
- net.minecraft.client.sounds.SoundManager
+ net.minecraft.client.sounds.SoundManager$1
- net.minecraft.client.sounds.SoundManager$2
+ net.minecraft.client.sounds.SoundManager$Preparations
- net.minecraft.client.sounds.SoundManager$Preparations$1
+ net.minecraft.client.sounds.WeighedSoundEvents
- net.minecraft.client.sounds.Weighted
- net.minecraft.client.telemetry.ClientTelemetryManager
- net.minecraft.client.telemetry.events.AggregatedTelemetryEvent
- net.minecraft.client.telemetry.events.package-info
+ net.minecraft.client.telemetry.events.PerformanceMetricsEvent
- net.minecraft.client.telemetry.events.WorldLoadEvent
+ net.minecraft.client.telemetry.events.WorldLoadEvent$1
- net.minecraft.client.telemetry.events.WorldLoadTimesEvent
+ net.minecraft.client.telemetry.events.WorldUnloadEvent
+ net.minecraft.client.telemetry.package-info
+ net.minecraft.client.telemetry.TelemetryEventInstance
- net.minecraft.client.telemetry.TelemetryEventLog
+ net.minecraft.client.telemetry.TelemetryEventLogger
- net.minecraft.client.telemetry.TelemetryEventSender
+ net.minecraft.client.telemetry.TelemetryEventType
- net.minecraft.client.telemetry.TelemetryEventType$Builder
+ net.minecraft.client.telemetry.TelemetryLogManager
- net.minecraft.client.telemetry.TelemetryProperty
+ net.minecraft.client.telemetry.TelemetryProperty$Exporter
- net.minecraft.client.telemetry.TelemetryProperty$GameMode
+ net.minecraft.client.telemetry.TelemetryProperty$ServerType
- net.minecraft.client.telemetry.TelemetryPropertyMap
+ net.minecraft.client.telemetry.TelemetryPropertyMap$1
- net.minecraft.client.telemetry.TelemetryPropertyMap$Builder
+ net.minecraft.client.telemetry.WorldSessionTelemetryManager
- net.minecraft.client.tutorial.BundleTutorial
+ net.minecraft.client.tutorial.CompletedTutorialStepInstance
- net.minecraft.client.tutorial.CraftPlanksTutorialStep
+ net.minecraft.client.tutorial.FindTreeTutorialStepInstance
- net.minecraft.client.tutorial.MovementTutorialStepInstance
+ net.minecraft.client.tutorial.OpenInventoryTutorialStep
+ net.minecraft.client.tutorial.package-info
- net.minecraft.client.tutorial.PunchTreeTutorialStepInstance
+ net.minecraft.client.tutorial.Tutorial
- net.minecraft.client.tutorial.Tutorial$TimedToast
+ net.minecraft.client.tutorial.TutorialStepInstance
- net.minecraft.client.tutorial.TutorialSteps
- net.minecraft.client.voting.ClientVoteStorage
- net.minecraft.client.voting.ClientVoteStorage$CountAndLimit
- net.minecraft.client.voting.ClientVoteStorage$VoteInfo
- net.minecraft.client.voting.package-info
- net.minecraft.data.worldgen.biome.NetherBiomes
+ net.minecraft.data.worldgen.biome.OverworldBiomes
- net.minecraft.data.worldgen.biome.package-info
+ net.minecraft.data.worldgen.features.AquaticFeatures
- net.minecraft.data.worldgen.features.CaveFeatures
+ net.minecraft.data.worldgen.features.EndFeatures
- net.minecraft.data.worldgen.features.FeatureUtils
+ net.minecraft.data.worldgen.features.MiscOverworldFeatures
- net.minecraft.data.worldgen.features.NetherFeatures
+ net.minecraft.data.worldgen.features.OreFeatures
+ net.minecraft.data.worldgen.features.package-info
- net.minecraft.data.worldgen.features.PileFeatures
+ net.minecraft.data.worldgen.features.TreeFeatures
- net.minecraft.data.worldgen.features.VegetationFeatures
- net.minecraft.data.worldgen.package-info
+ net.minecraft.data.worldgen.placement.AquaticPlacements
- net.minecraft.data.worldgen.placement.CavePlacements
+ net.minecraft.data.worldgen.placement.EndPlacements
- net.minecraft.data.worldgen.placement.MiscOverworldPlacements
+ net.minecraft.data.worldgen.placement.NetherPlacements
- net.minecraft.data.worldgen.placement.OrePlacements
+ net.minecraft.data.worldgen.placement.package-info
+ net.minecraft.data.worldgen.placement.PlacementUtils
- net.minecraft.data.worldgen.placement.TreePlacements
+ net.minecraft.data.worldgen.placement.VegetationPlacements
- net.minecraft.data.worldgen.placement.VillagePlacements
- net.minecraft.gametest.framework.AfterBatch
+ net.minecraft.gametest.framework.BeforeBatch
- net.minecraft.gametest.framework.ExhaustedAttemptsException
+ net.minecraft.gametest.framework.GameTest
- net.minecraft.gametest.framework.GameTestAssertException
+ net.minecraft.gametest.framework.GameTestAssertPosException
- net.minecraft.gametest.framework.GameTestBatch
+ net.minecraft.gametest.framework.GameTestBatchRunner
- net.minecraft.gametest.framework.GameTestBatchRunner$1
+ net.minecraft.gametest.framework.GameTestEvent
- net.minecraft.gametest.framework.GameTestGenerator
+ net.minecraft.gametest.framework.GameTestHelper
- net.minecraft.gametest.framework.GameTestHelper$1
+ net.minecraft.gametest.framework.GameTestHelper$2
- net.minecraft.gametest.framework.GameTestInfo
+ net.minecraft.gametest.framework.GameTestListener
- net.minecraft.gametest.framework.GameTestRegistry
+ net.minecraft.gametest.framework.GameTestRunner
- net.minecraft.gametest.framework.GameTestSequence
+ net.minecraft.gametest.framework.GameTestSequence$Condition
- net.minecraft.gametest.framework.GameTestServer
+ net.minecraft.gametest.framework.GameTestServer$1
- net.minecraft.gametest.framework.GameTestTicker
+ net.minecraft.gametest.framework.GameTestTimeoutException
- net.minecraft.gametest.framework.GlobalTestReporter
+ net.minecraft.gametest.framework.JUnitLikeTestReporter
- net.minecraft.gametest.framework.LogTestReporter
+ net.minecraft.gametest.framework.MultipleTestTracker
- net.minecraft.gametest.framework.MultipleTestTracker$1
+ net.minecraft.gametest.framework.package-info
+ net.minecraft.gametest.framework.ReportGameListener
- net.minecraft.gametest.framework.StructureUtils
+ net.minecraft.gametest.framework.StructureUtils$1
- net.minecraft.gametest.framework.TeamcityTestReporter
+ net.minecraft.gametest.framework.TestClassNameArgument
- net.minecraft.gametest.framework.TestCommand
+ net.minecraft.gametest.framework.TestCommand$TestSummaryDisplayer
- net.minecraft.gametest.framework.TestFunction
+ net.minecraft.gametest.framework.TestFunctionArgument
- net.minecraft.gametest.framework.TestReporter
- net.minecraft.locale.Language
+ net.minecraft.locale.Language$1
- net.minecraft.locale.package-info
+ net.minecraft.nbt.ByteArrayTag
- net.minecraft.nbt.ByteArrayTag$1
+ net.minecraft.nbt.ByteTag
- net.minecraft.nbt.ByteTag$1
+ net.minecraft.nbt.ByteTag$Cache
- net.minecraft.nbt.CollectionTag
+ net.minecraft.nbt.CompoundTag
- net.minecraft.nbt.CompoundTag$1
+ net.minecraft.nbt.CompoundTag$2
- net.minecraft.nbt.DoubleTag
+ net.minecraft.nbt.DoubleTag$1
- net.minecraft.nbt.EndTag
+ net.minecraft.nbt.EndTag$1
- net.minecraft.nbt.FloatTag
+ net.minecraft.nbt.FloatTag$1
- net.minecraft.nbt.IntArrayTag
+ net.minecraft.nbt.IntArrayTag$1
- net.minecraft.nbt.IntTag
+ net.minecraft.nbt.IntTag$1
- net.minecraft.nbt.IntTag$Cache
+ net.minecraft.nbt.ListTag
- net.minecraft.nbt.ListTag$1
+ net.minecraft.nbt.ListTag$2
- net.minecraft.nbt.LongArrayTag
+ net.minecraft.nbt.LongArrayTag$1
- net.minecraft.nbt.LongTag
+ net.minecraft.nbt.LongTag$1
- net.minecraft.nbt.LongTag$Cache
+ net.minecraft.nbt.NbtAccounter
- net.minecraft.nbt.NbtAccounter$1
+ net.minecraft.nbt.NbtIo
- net.minecraft.nbt.NbtIo$1
+ net.minecraft.nbt.NbtOps
- net.minecraft.nbt.NbtOps$1
+ net.minecraft.nbt.NbtOps$ByteListCollector
- net.minecraft.nbt.NbtOps$HeterogenousListCollector
+ net.minecraft.nbt.NbtOps$HomogenousListCollector
- net.minecraft.nbt.NbtOps$InitialListCollector
+ net.minecraft.nbt.NbtOps$IntListCollector
- net.minecraft.nbt.NbtOps$ListCollector
+ net.minecraft.nbt.NbtOps$LongListCollector
- net.minecraft.nbt.NbtOps$NbtRecordBuilder
+ net.minecraft.nbt.NbtUtils
- net.minecraft.nbt.NumericTag
+ net.minecraft.nbt.package-info
+ net.minecraft.nbt.ShortTag
- net.minecraft.nbt.ShortTag$1
+ net.minecraft.nbt.ShortTag$Cache
- net.minecraft.nbt.SnbtPrinterTagVisitor
+ net.minecraft.nbt.StreamTagVisitor
- net.minecraft.nbt.StreamTagVisitor$EntryResult
+ net.minecraft.nbt.StreamTagVisitor$ValueResult
- net.minecraft.nbt.StringTag
+ net.minecraft.nbt.StringTag$1
- net.minecraft.nbt.StringTagVisitor
+ net.minecraft.nbt.Tag
- net.minecraft.nbt.TagParser
+ net.minecraft.nbt.TagType
- net.minecraft.nbt.TagType$1
+ net.minecraft.nbt.TagType$2
- net.minecraft.nbt.TagType$StaticSize
+ net.minecraft.nbt.TagType$VariableSize
- net.minecraft.nbt.TagTypes
+ net.minecraft.nbt.TagVisitor
- net.minecraft.nbt.TextComponentTagVisitor
- net.minecraft.nbt.visitors.CollectFields
+ net.minecraft.nbt.visitors.CollectToTag
- net.minecraft.nbt.visitors.FieldSelector
+ net.minecraft.nbt.visitors.FieldTree
+ net.minecraft.nbt.visitors.package-info
- net.minecraft.nbt.visitors.SkipAll
+ net.minecraft.nbt.visitors.SkipAll$1
- net.minecraft.nbt.visitors.SkipFields
+ net.minecraft.network.chat.ChatDecorator
- net.minecraft.network.chat.ChatType
+ net.minecraft.network.chat.ChatType$Bound
- net.minecraft.network.chat.ChatType$BoundNetwork
+ net.minecraft.network.chat.ChatTypeDecoration
- net.minecraft.network.chat.ChatTypeDecoration$Parameter
+ net.minecraft.network.chat.ChatTypeDecoration$Parameter$Selector
- net.minecraft.network.chat.ClickEvent
+ net.minecraft.network.chat.ClickEvent$Action
- net.minecraft.network.chat.CommonComponents
+ net.minecraft.network.chat.Component
- net.minecraft.network.chat.Component$Serializer
+ net.minecraft.network.chat.ComponentContents
- net.minecraft.network.chat.ComponentContents$1
+ net.minecraft.network.chat.ComponentUtils
- net.minecraft.network.chat.contents.BlockDataSource
+ net.minecraft.network.chat.contents.DataSource
- net.minecraft.network.chat.contents.EntityDataSource
+ net.minecraft.network.chat.contents.KeybindContents
- net.minecraft.network.chat.contents.KeybindResolver
+ net.minecraft.network.chat.contents.LiteralContents
- net.minecraft.network.chat.contents.NbtContents
- net.minecraft.network.chat.contents.package-info
+ net.minecraft.network.chat.contents.ScoreContents
- net.minecraft.network.chat.contents.SelectorContents
+ net.minecraft.network.chat.contents.StorageDataSource
- net.minecraft.network.chat.contents.TranslatableContents
+ net.minecraft.network.chat.contents.TranslatableFormatException
- net.minecraft.network.chat.FilterMask
+ net.minecraft.network.chat.FilterMask$1
- net.minecraft.network.chat.FilterMask$Type
+ net.minecraft.network.chat.FormattedText
- net.minecraft.network.chat.FormattedText$1
+ net.minecraft.network.chat.FormattedText$2
- net.minecraft.network.chat.FormattedText$3
+ net.minecraft.network.chat.FormattedText$4
- net.minecraft.network.chat.FormattedText$ContentConsumer
+ net.minecraft.network.chat.FormattedText$StyledContentConsumer
- net.minecraft.network.chat.HoverEvent
+ net.minecraft.network.chat.HoverEvent$Action
- net.minecraft.network.chat.HoverEvent$EntityTooltipInfo
+ net.minecraft.network.chat.HoverEvent$ItemStackInfo
- net.minecraft.network.chat.LastSeenMessages
+ net.minecraft.network.chat.LastSeenMessages$Packed
- net.minecraft.network.chat.LastSeenMessages$Update
+ net.minecraft.network.chat.LastSeenMessagesTracker
- net.minecraft.network.chat.LastSeenMessagesTracker$Update
+ net.minecraft.network.chat.LastSeenMessagesValidator
- net.minecraft.network.chat.LastSeenTrackedEntry
+ net.minecraft.network.chat.LocalChatSession
- net.minecraft.network.chat.MessageSignature
+ net.minecraft.network.chat.MessageSignature$Packed
- net.minecraft.network.chat.MessageSignatureCache
+ net.minecraft.network.chat.MutableComponent
- net.minecraft.network.chat.OutgoingChatMessage
+ net.minecraft.network.chat.OutgoingChatMessage$Disguised
- net.minecraft.network.chat.OutgoingChatMessage$Player
+ net.minecraft.network.chat.package-info
+ net.minecraft.network.chat.PlayerChatMessage
- net.minecraft.network.chat.RemoteChatSession
+ net.minecraft.network.chat.RemoteChatSession$Data
- net.minecraft.network.chat.SignableCommand
+ net.minecraft.network.chat.SignableCommand$Argument
- net.minecraft.network.chat.SignedMessageBody
+ net.minecraft.network.chat.SignedMessageBody$Packed
- net.minecraft.network.chat.SignedMessageChain
+ net.minecraft.network.chat.SignedMessageChain$DecodeException
- net.minecraft.network.chat.SignedMessageChain$Decoder
+ net.minecraft.network.chat.SignedMessageChain$Encoder
- net.minecraft.network.chat.SignedMessageLink
+ net.minecraft.network.chat.SignedMessageValidator
- net.minecraft.network.chat.SignedMessageValidator$KeyBased
+ net.minecraft.network.chat.Style
- net.minecraft.network.chat.Style$1
+ net.minecraft.network.chat.Style$1Collector
- net.minecraft.network.chat.Style$Serializer
+ net.minecraft.network.chat.SubStringSource
- net.minecraft.network.chat.TextColor
+ net.minecraft.network.chat.ThrowingComponent
- net.minecraft.network.CipherBase
+ net.minecraft.network.CipherDecoder
- net.minecraft.network.CipherEncoder
+ net.minecraft.network.CompressionDecoder
- net.minecraft.network.CompressionEncoder
+ net.minecraft.network.Connection
- net.minecraft.network.Connection$1
+ net.minecraft.network.Connection$2
- net.minecraft.network.Connection$PacketHolder
+ net.minecraft.network.ConnectionProtocol
- net.minecraft.network.ConnectionProtocol$PacketSet
+ net.minecraft.network.ConnectionProtocol$ProtocolBuilder
- net.minecraft.network.FriendlyByteBuf
+ net.minecraft.network.FriendlyByteBuf$1
- net.minecraft.network.FriendlyByteBuf$Reader
+ net.minecraft.network.FriendlyByteBuf$Writer
- net.minecraft.network.package-info
- net.minecraft.network.PacketBundlePacker
+ net.minecraft.network.PacketBundleUnpacker
- net.minecraft.network.PacketDecoder
+ net.minecraft.network.PacketEncoder
- net.minecraft.network.PacketListener
+ net.minecraft.network.PacketSendListener
- net.minecraft.network.PacketSendListener$1
+ net.minecraft.network.PacketSendListener$2
+ net.minecraft.network.protocol.BundleDelimiterPacket
- net.minecraft.network.protocol.BundlePacket
+ net.minecraft.network.protocol.BundlerInfo
- net.minecraft.network.protocol.BundlerInfo$1
+ net.minecraft.network.protocol.BundlerInfo$2
- net.minecraft.network.protocol.BundlerInfo$2$1
+ net.minecraft.network.protocol.BundlerInfo$Bundler
- net.minecraft.network.protocol.BundlerInfo$Provider
+ net.minecraft.network.protocol.game.ClientboundAddEntityPacket
- net.minecraft.network.protocol.game.ClientboundAddExperienceOrbPacket
+ net.minecraft.network.protocol.game.ClientboundAddPlayerPacket
- net.minecraft.network.protocol.game.ClientboundAnimatePacket
+ net.minecraft.network.protocol.game.ClientboundAwardStatsPacket
- net.minecraft.network.protocol.game.ClientboundBlockChangedAckPacket
+ net.minecraft.network.protocol.game.ClientboundBlockDestructionPacket
- net.minecraft.network.protocol.game.ClientboundBlockEntityDataPacket
+ net.minecraft.network.protocol.game.ClientboundBlockEventPacket
- net.minecraft.network.protocol.game.ClientboundBlockUpdatePacket
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$1
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket$AddOperation
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$Handler
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket$Operation
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$OperationType
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket$UpdateNameOperation
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$UpdateProgressOperation
+ net.minecraft.network.protocol.game.ClientboundBossEventPacket$UpdatePropertiesOperation
- net.minecraft.network.protocol.game.ClientboundBossEventPacket$UpdateStyleOperation
- net.minecraft.network.protocol.game.ClientboundSectionBlocksUpdatePacket
+ net.minecraft.network.protocol.game.ClientboundSelectAdvancementsTabPacket
- net.minecraft.network.protocol.game.ClientboundServerDataPacket
+ net.minecraft.network.protocol.game.ClientboundSetActionBarTextPacket
- net.minecraft.network.protocol.game.ClientboundSetBorderCenterPacket
+ net.minecraft.network.protocol.game.ClientboundSetBorderLerpSizePacket
- net.minecraft.network.protocol.game.ClientboundSetBorderSizePacket
+ net.minecraft.network.protocol.game.ClientboundSetBorderWarningDelayPacket
- net.minecraft.network.protocol.game.ClientboundSetBorderWarningDistancePacket
+ net.minecraft.network.protocol.game.ClientboundSetCameraPacket
- net.minecraft.network.protocol.game.ClientboundSetCarriedItemPacket
+ net.minecraft.network.protocol.game.ClientboundSetChunkCacheCenterPacket
- net.minecraft.network.protocol.game.ClientboundSetChunkCacheRadiusPacket
+ net.minecraft.network.protocol.game.ClientboundSetDefaultSpawnPositionPacket
- net.minecraft.network.protocol.game.ClientboundSetDisplayObjectivePacket
+ net.minecraft.network.protocol.game.ClientboundSetEntityDataPacket
- net.minecraft.network.protocol.game.ClientboundSetEntityLinkPacket
+ net.minecraft.network.protocol.game.ClientboundSetEntityMotionPacket
- net.minecraft.network.protocol.game.ClientboundSetEquipmentPacket
+ net.minecraft.network.protocol.game.ClientboundSetExperiencePacket
- net.minecraft.network.protocol.game.ClientboundSetHealthPacket
+ net.minecraft.network.protocol.game.ClientboundSetObjectivePacket
- net.minecraft.network.protocol.game.ClientboundSetPassengersPacket
+ net.minecraft.network.protocol.game.ClientboundSetPlayerTeamPacket
- net.minecraft.network.protocol.game.ClientboundSetPlayerTeamPacket$Action
+ net.minecraft.network.protocol.game.ClientboundSetPlayerTeamPacket$Parameters
- net.minecraft.network.protocol.game.ClientboundSetScorePacket
+ net.minecraft.network.protocol.game.ClientboundSetSimulationDistancePacket
- net.minecraft.network.protocol.game.ClientboundSetSubtitleTextPacket
+ net.minecraft.network.protocol.game.ClientboundSetTimePacket
+ net.minecraft.network.protocol.game.ClientboundSetTitlesAnimationPacket
- net.minecraft.network.protocol.game.ClientboundSetTitleTextPacket
- net.minecraft.network.protocol.game.ClientboundSoundEntityPacket
+ net.minecraft.network.protocol.game.ClientboundSoundPacket
- net.minecraft.network.protocol.game.ClientboundStopSoundPacket
+ net.minecraft.network.protocol.game.ClientboundSystemChatPacket
- net.minecraft.network.protocol.game.ClientboundTabListPacket
+ net.minecraft.network.protocol.game.ClientboundTagQueryPacket
- net.minecraft.network.protocol.game.ClientboundTakeItemEntityPacket
+ net.minecraft.network.protocol.game.ClientboundTeleportEntityPacket
- net.minecraft.network.protocol.game.ClientboundUpdateAdvancementsPacket
+ net.minecraft.network.protocol.game.ClientboundUpdateAttributesPacket
- net.minecraft.network.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
+ net.minecraft.network.protocol.game.ClientboundUpdateEnabledFeaturesPacket
- net.minecraft.network.protocol.game.ClientboundUpdateMobEffectPacket
+ net.minecraft.network.protocol.game.ClientboundUpdateRecipesPacket
- net.minecraft.network.protocol.game.ClientboundUpdateTagsPacket
- net.minecraft.network.protocol.game.ClientboundVoteFinishPacket
- net.minecraft.network.protocol.game.ClientboundVoteStartPacket
- net.minecraft.network.protocol.game.ClientGamePacketListener
+ net.minecraft.network.protocol.game.DebugEntityNameGenerator
- net.minecraft.network.protocol.game.DebugPackets
+ net.minecraft.network.protocol.game.package-info
+ net.minecraft.network.protocol.game.ServerboundAcceptTeleportationPacket
- net.minecraft.network.protocol.game.ServerboundBlockEntityTagQuery
+ net.minecraft.network.protocol.game.ServerboundChangeDifficultyPacket
- net.minecraft.network.protocol.game.ServerboundChatAckPacket
+ net.minecraft.network.protocol.game.ServerboundChatCommandPacket
- net.minecraft.network.protocol.game.ServerboundChatPacket
+ net.minecraft.network.protocol.game.ServerboundChatSessionUpdatePacket
- net.minecraft.network.protocol.game.ServerboundClientCommandPacket
+ net.minecraft.network.protocol.game.ServerboundClientCommandPacket$Action
- net.minecraft.network.protocol.game.ServerboundClientInformationPacket
+ net.minecraft.network.protocol.game.ServerboundCommandSuggestionPacket
- net.minecraft.network.protocol.game.ServerboundContainerButtonClickPacket
+ net.minecraft.network.protocol.game.ServerboundContainerClickPacket
- net.minecraft.network.protocol.game.ServerboundContainerClosePacket
+ net.minecraft.network.protocol.game.ServerGamePacketListener
- net.minecraft.network.protocol.game.ServerPacketListener
- net.minecraft.network.protocol.game.VecDeltaCodec
- net.minecraft.network.protocol.handshake.ClientIntentionPacket
- net.minecraft.network.protocol.handshake.package-info
+ net.minecraft.network.protocol.handshake.ServerHandshakePacketListener
- net.minecraft.network.protocol.login.ClientboundCustomQueryPacket
+ net.minecraft.network.protocol.login.ClientboundGameProfilePacket
- net.minecraft.network.protocol.login.ClientboundHelloPacket
+ net.minecraft.network.protocol.login.ClientboundLoginCompressionPacket
- net.minecraft.network.protocol.login.ClientboundLoginDisconnectPacket
+ net.minecraft.network.protocol.login.ClientLoginPacketListener
+ net.minecraft.network.protocol.login.package-info
- net.minecraft.network.protocol.login.ServerboundCustomQueryPacket
+ net.minecraft.network.protocol.login.ServerboundHelloPacket
- net.minecraft.network.protocol.login.ServerboundKeyPacket
+ net.minecraft.network.protocol.login.ServerLoginPacketListener
- net.minecraft.network.protocol.package-info
+ net.minecraft.network.protocol.Packet
- net.minecraft.network.protocol.PacketFlow
+ net.minecraft.network.protocol.PacketUtils
- net.minecraft.network.protocol.status.ClientboundPongResponsePacket
+ net.minecraft.network.protocol.status.ClientboundStatusResponsePacket
+ net.minecraft.network.protocol.status.ClientStatusPacketListener
+ net.minecraft.network.protocol.status.package-info
+ net.minecraft.network.protocol.status.ServerboundPingRequestPacket
- net.minecraft.network.protocol.status.ServerboundStatusRequestPacket
- net.minecraft.network.protocol.status.ServerStatus
+ net.minecraft.network.protocol.status.ServerStatus$Favicon
- net.minecraft.network.protocol.status.ServerStatus$Players
+ net.minecraft.network.protocol.status.ServerStatus$Version
- net.minecraft.network.protocol.status.ServerStatusPacketListener
- net.minecraft.network.RateKickingConnection
+ net.minecraft.network.SkipPacketException
- net.minecraft.network.syncher.EntityDataAccessor
+ net.minecraft.network.syncher.EntityDataSerializer
- net.minecraft.network.syncher.EntityDataSerializer$1
+ net.minecraft.network.syncher.EntityDataSerializer$ForValueType
- net.minecraft.network.syncher.EntityDataSerializers
+ net.minecraft.network.syncher.EntityDataSerializers$1
- net.minecraft.network.syncher.EntityDataSerializers$2
+ net.minecraft.network.syncher.EntityDataSerializers$3
- net.minecraft.network.syncher.EntityDataSerializers$4
+ net.minecraft.network.syncher.EntityDataSerializers$5
- net.minecraft.network.syncher.EntityDataSerializers$6
+ net.minecraft.network.syncher.EntityDataSerializers$7
+ net.minecraft.network.syncher.package-info
- net.minecraft.network.syncher.SynchedEntityData
+ net.minecraft.network.syncher.SynchedEntityData$DataItem
- net.minecraft.network.syncher.SynchedEntityData$DataValue
- net.minecraft.network.TickablePacketListener
+ net.minecraft.network.Varint21FrameDecoder
- net.minecraft.network.Varint21LengthFieldPrepender
- net.minecraft.obfuscate.DontObfuscate
+ net.minecraft.obfuscate.package-info
- net.minecraft.package-info
+ net.minecraft.realms.DisconnectedRealmsScreen
+ net.minecraft.realms.package-info
- net.minecraft.realms.RealmsConnect
+ net.minecraft.realms.RealmsConnect$1
- net.minecraft.realms.RealmsLabel
+ net.minecraft.realms.RealmsObjectSelectionList
- net.minecraft.realms.RealmsScreen
+ net.minecraft.realms.RepeatedNarrator
- net.minecraft.realms.RepeatedNarrator$Params
- net.minecraft.recipebook.package-info
- net.minecraft.recipebook.PlaceRecipe
+ net.minecraft.recipebook.ServerPlaceRecipe
+ net.minecraft.resources.DelegatingOps
- net.minecraft.resources.FileToIdConverter
+ net.minecraft.resources.HolderSetCodec
- net.minecraft.resources.package-info
- net.minecraft.resources.RegistryDataLoader
+ net.minecraft.resources.RegistryDataLoader$1
- net.minecraft.resources.RegistryDataLoader$Loader
+ net.minecraft.resources.RegistryDataLoader$RegistryData
- net.minecraft.resources.RegistryFileCodec
+ net.minecraft.resources.RegistryFixedCodec
- net.minecraft.resources.RegistryOps
+ net.minecraft.resources.RegistryOps$1
- net.minecraft.resources.RegistryOps$2
+ net.minecraft.resources.RegistryOps$RegistryInfo
- net.minecraft.resources.RegistryOps$RegistryInfoLookup
+ net.minecraft.resources.ResourceKey
- net.minecraft.resources.ResourceKey$InternKey
+ net.minecraft.resources.ResourceLocation
- net.minecraft.resources.ResourceLocation$Dummy
+ net.minecraft.resources.ResourceLocation$Serializer
+ net.minecraft.server.advancements.AdvancementVisibilityEvaluator
- net.minecraft.server.advancements.AdvancementVisibilityEvaluator$Output
+ net.minecraft.server.advancements.AdvancementVisibilityEvaluator$VisibilityRule
- net.minecraft.server.advancements.package-info
+ net.minecraft.server.Bootstrap
- net.minecraft.server.Bootstrap$1
+ net.minecraft.server.bossevents.CustomBossEvent
- net.minecraft.server.bossevents.CustomBossEvents
+ net.minecraft.server.bossevents.package-info
+ net.minecraft.server.ChainedJsonException
- net.minecraft.server.ChainedJsonException$Entry
- net.minecraft.server.chase.ChaseClient
+ net.minecraft.server.chase.ChaseClient$TeleportTarget
- net.minecraft.server.chase.ChaseServer
+ net.minecraft.server.chase.ChaseServer$PlayerPosition
- net.minecraft.server.chase.package-info
+ net.minecraft.server.commands.AdvancementCommands
- net.minecraft.server.commands.AdvancementCommands$Action
+ net.minecraft.server.commands.AdvancementCommands$Action$1
- net.minecraft.server.commands.AdvancementCommands$Action$2
+ net.minecraft.server.commands.AdvancementCommands$Mode
- net.minecraft.server.commands.AttributeCommand
+ net.minecraft.server.commands.BanIpCommands
- net.minecraft.server.commands.BanListCommands
+ net.minecraft.server.commands.BanPlayerCommands
- net.minecraft.server.commands.BossBarCommands
+ net.minecraft.server.commands.ChaseCommand
- net.minecraft.server.commands.ClearInventoryCommands
+ net.minecraft.server.commands.CloneCommands
- net.minecraft.server.commands.CloneCommands$CloneBlockInfo
+ net.minecraft.server.commands.CloneCommands$CommandFunction
- net.minecraft.server.commands.CloneCommands$DimensionAndPosition
+ net.minecraft.server.commands.CloneCommands$Mode
- net.minecraft.server.commands.DamageCommand
+ net.minecraft.server.commands.data.BlockDataAccessor
- net.minecraft.server.commands.data.BlockDataAccessor$1
+ net.minecraft.server.commands.data.DataAccessor
- net.minecraft.server.commands.data.DataCommands
+ net.minecraft.server.commands.data.DataCommands$DataManipulator
- net.minecraft.server.commands.data.DataCommands$DataManipulatorDecorator
+ net.minecraft.server.commands.data.DataCommands$DataProvider
- net.minecraft.server.commands.data.EntityDataAccessor
+ net.minecraft.server.commands.data.EntityDataAccessor$1
- net.minecraft.server.commands.data.package-info
- net.minecraft.server.commands.data.StorageDataAccessor
+ net.minecraft.server.commands.data.StorageDataAccessor$1
+ net.minecraft.server.commands.DataPackCommand
- net.minecraft.server.commands.DataPackCommand$Inserter
- net.minecraft.server.commands.DebugCommand
+ net.minecraft.server.commands.DebugCommand$Tracer
- net.minecraft.server.commands.DebugMobSpawningCommand
+ net.minecraft.server.commands.DebugPathCommand
- net.minecraft.server.commands.DefaultGameModeCommands
+ net.minecraft.server.commands.DeOpCommands
+ net.minecraft.server.commands.DifficultyCommand
- net.minecraft.server.commands.EffectCommands
+ net.minecraft.server.commands.EmoteCommands
- net.minecraft.server.commands.EnchantCommand
+ net.minecraft.server.commands.ExecuteCommand
- net.minecraft.server.commands.ExecuteCommand$CommandNumericPredicate
+ net.minecraft.server.commands.ExecuteCommand$CommandPredicate
- net.minecraft.server.commands.ExperienceCommand
+ net.minecraft.server.commands.ExperienceCommand$Type
- net.minecraft.server.commands.FillBiomeCommand
+ net.minecraft.server.commands.FillCommand
- net.minecraft.server.commands.FillCommand$Mode
+ net.minecraft.server.commands.ForceLoadCommand
- net.minecraft.server.commands.FunctionCommand
+ net.minecraft.server.commands.GameModeCommand
- net.minecraft.server.commands.GameRuleCommand
+ net.minecraft.server.commands.GameRuleCommand$1
- net.minecraft.server.commands.GiveCommand
+ net.minecraft.server.commands.HelpCommand
- net.minecraft.server.commands.ItemCommands
+ net.minecraft.server.commands.JfrCommand
- net.minecraft.server.commands.KickCommand
+ net.minecraft.server.commands.KillCommand
- net.minecraft.server.commands.ListPlayersCommand
+ net.minecraft.server.commands.LocateCommand
- net.minecraft.server.commands.LootCommand
+ net.minecraft.server.commands.LootCommand$Callback
- net.minecraft.server.commands.LootCommand$DropConsumer
+ net.minecraft.server.commands.LootCommand$TailProvider
- net.minecraft.server.commands.MsgCommand
+ net.minecraft.server.commands.OpCommand
+ net.minecraft.server.commands.package-info
- net.minecraft.server.commands.PardonCommand
+ net.minecraft.server.commands.PardonIpCommand
- net.minecraft.server.commands.ParticleCommand
+ net.minecraft.server.commands.PerfCommand
- net.minecraft.server.commands.PlaceCommand
+ net.minecraft.server.commands.PlaySoundCommand
- net.minecraft.server.commands.PublishCommand
+ net.minecraft.server.commands.RaidCommand
- net.minecraft.server.commands.RecipeCommand
+ net.minecraft.server.commands.ReloadCommand
- net.minecraft.server.commands.ResetChunksCommand
+ net.minecraft.server.commands.RideCommand
- net.minecraft.server.commands.SaveAllCommand
+ net.minecraft.server.commands.SaveOffCommand
- net.minecraft.server.commands.SaveOnCommand
+ net.minecraft.server.commands.SayCommand
- net.minecraft.server.commands.ScheduleCommand
+ net.minecraft.server.commands.ScoreboardCommand
- net.minecraft.server.commands.SeedCommand
+ net.minecraft.server.commands.SetBlockCommand
- net.minecraft.server.commands.SetBlockCommand$Filter
+ net.minecraft.server.commands.SetBlockCommand$Mode
- net.minecraft.server.commands.SetPlayerIdleTimeoutCommand
+ net.minecraft.server.commands.SetSpawnCommand
- net.minecraft.server.commands.SetWorldSpawnCommand
+ net.minecraft.server.commands.SpawnArmorTrimsCommand
- net.minecraft.server.commands.SpectateCommand
+ net.minecraft.server.commands.SpreadPlayersCommand
- net.minecraft.server.commands.SpreadPlayersCommand$Position
+ net.minecraft.server.commands.StopCommand
- net.minecraft.server.commands.StopSoundCommand
+ net.minecraft.server.commands.SummonCommand
- net.minecraft.server.commands.TagCommand
+ net.minecraft.server.commands.TeamCommand
- net.minecraft.server.commands.TeamMsgCommand
+ net.minecraft.server.commands.TeleportCommand
- net.minecraft.server.commands.TeleportCommand$LookAt
+ net.minecraft.server.commands.TellRawCommand
- net.minecraft.server.commands.TimeCommand
+ net.minecraft.server.commands.TitleCommand
- net.minecraft.server.commands.TriggerCommand
+ net.minecraft.server.commands.WardenSpawnTrackerCommand
- net.minecraft.server.commands.WeatherCommand
+ net.minecraft.server.commands.WhitelistCommand
- net.minecraft.server.commands.WorldBorderCommand
+ net.minecraft.server.ConsoleInput
- net.minecraft.server.DebugLoggedPrintStream
- net.minecraft.server.dedicated.DedicatedPlayerList
+ net.minecraft.server.dedicated.DedicatedServer
- net.minecraft.server.dedicated.DedicatedServer$1
+ net.minecraft.server.dedicated.DedicatedServerProperties
- net.minecraft.server.dedicated.DedicatedServerProperties$WorldDimensionData
+ net.minecraft.server.dedicated.DedicatedServerSettings
- net.minecraft.server.dedicated.package-info
- net.minecraft.server.dedicated.ServerWatchdog
+ net.minecraft.server.dedicated.ServerWatchdog$1
- net.minecraft.server.dedicated.Settings
+ net.minecraft.server.dedicated.Settings$MutableValue
+ net.minecraft.server.Eula
+ net.minecraft.server.gui.MinecraftServerGui
- net.minecraft.server.gui.MinecraftServerGui$1
+ net.minecraft.server.gui.MinecraftServerGui$2
- net.minecraft.server.gui.package-info
- net.minecraft.server.gui.PlayerListComponent
+ net.minecraft.server.gui.StatsComponent
+ net.minecraft.server.level.BlockDestructionProgress
- net.minecraft.server.level.ChunkHolder
+ net.minecraft.server.level.ChunkHolder$1
- net.minecraft.server.level.ChunkHolder$ChunkLoadingFailure
+ net.minecraft.server.level.ChunkHolder$ChunkLoadingFailure$1
- net.minecraft.server.level.ChunkHolder$ChunkSaveDebug
+ net.minecraft.server.level.ChunkHolder$FullChunkStatus
- net.minecraft.server.level.ChunkHolder$LevelChangeListener
+ net.minecraft.server.level.ChunkHolder$PlayerProvider
- net.minecraft.server.level.ChunkMap
+ net.minecraft.server.level.ChunkMap$1
- net.minecraft.server.level.ChunkMap$2
+ net.minecraft.server.level.ChunkMap$DistanceManager
- net.minecraft.server.level.ChunkMap$TrackedEntity
+ net.minecraft.server.level.ChunkTaskPriorityQueue
- net.minecraft.server.level.ChunkTaskPriorityQueueSorter
+ net.minecraft.server.level.ChunkTaskPriorityQueueSorter$Message
- net.minecraft.server.level.ChunkTaskPriorityQueueSorter$Release
+ net.minecraft.server.level.ChunkTracker
- net.minecraft.server.level.ColumnPos
+ net.minecraft.server.level.DemoMode
- net.minecraft.server.level.DistanceManager
+ net.minecraft.server.level.DistanceManager$ChunkTicketTracker
- net.minecraft.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
+ net.minecraft.server.level.DistanceManager$PlayerTicketTracker
- net.minecraft.server.level.PlayerMap
+ net.minecraft.server.level.PlayerRespawnLogic
- net.minecraft.server.level.SectionTracker
+ net.minecraft.server.level.ServerBossEvent
- net.minecraft.server.level.ServerChunkCache
+ net.minecraft.server.level.ServerChunkCache$ChunkAndHolder
- net.minecraft.server.level.ServerChunkCache$MainThreadExecutor
+ net.minecraft.server.level.ServerEntity
- net.minecraft.server.level.ServerLevel
- net.minecraft.server.LoggedPrintStream
+ net.minecraft.server.Main
- net.minecraft.server.Main$1
+ net.minecraft.server.MinecraftServer
- net.minecraft.server.MinecraftServer$1
+ net.minecraft.server.MinecraftServer$ReloadableResources
- net.minecraft.server.MinecraftServer$ServerResourcePackInfo
+ net.minecraft.server.MinecraftServer$TimeProfiler
- net.minecraft.server.MinecraftServer$TimeProfiler$1
+ net.minecraft.server.PlayerAdvancements
- net.minecraft.server.PlayerAdvancements$1
+ net.minecraft.server.RegistryLayer
- net.minecraft.server.ReloadableServerResources
+ net.minecraft.server.RunningOnDifferentThreadException
- net.minecraft.server.ServerAdvancementManager
+ net.minecraft.server.ServerFunctionLibrary
- net.minecraft.server.ServerFunctionManager
+ net.minecraft.server.ServerFunctionManager$ExecutionContext
- net.minecraft.server.ServerFunctionManager$QueuedCommand
+ net.minecraft.server.ServerFunctionManager$TraceCallbacks
- net.minecraft.server.ServerInterface
+ net.minecraft.server.ServerScoreboard
- net.minecraft.server.ServerScoreboard$Method
+ net.minecraft.server.Services
- net.minecraft.server.TickTask
+ net.minecraft.server.WorldLoader
- net.minecraft.server.WorldLoader$DataLoadContext
+ net.minecraft.server.WorldLoader$DataLoadOutput
- net.minecraft.server.WorldLoader$InitConfig
+ net.minecraft.server.WorldLoader$PackConfig
- net.minecraft.server.WorldLoader$ResultFactory
+ net.minecraft.server.WorldLoader$WorldDataSupplier
- net.minecraft.server.WorldStem
- net.minecraft.util.datafix.schemas.package-info
- net.minecraft.util.datafix.schemas.V501
+ net.minecraft.util.datafix.schemas.V700
- net.minecraft.util.datafix.schemas.V701
+ net.minecraft.util.datafix.schemas.V702
- net.minecraft.util.datafix.schemas.V703
+ net.minecraft.util.datafix.schemas.V704
- net.minecraft.util.datafix.schemas.V704$1
+ net.minecraft.util.datafix.schemas.V705
- net.minecraft.util.datafix.schemas.V705$1
+ net.minecraft.util.datafix.schemas.V808
- net.minecraft.util.datafix.schemas.V99
+ net.minecraft.util.datafix.schemas.V99$1
+ net.minecraft.util.eventlog.EventLogDirectory
- net.minecraft.util.eventlog.EventLogDirectory$CompressedFile
+ net.minecraft.util.eventlog.EventLogDirectory$File
- net.minecraft.util.eventlog.EventLogDirectory$FileId
+ net.minecraft.util.eventlog.EventLogDirectory$FileList
- net.minecraft.util.eventlog.EventLogDirectory$RawFile
+ net.minecraft.util.eventlog.JsonEventLog
- net.minecraft.util.eventlog.JsonEventLog$1
+ net.minecraft.util.eventlog.JsonEventLogReader
- net.minecraft.util.eventlog.JsonEventLogReader$1
+ net.minecraft.util.eventlog.package-info
- net.minecraft.util.monitoring.jmx.MinecraftServerStatistics
+ net.minecraft.util.monitoring.jmx.MinecraftServerStatistics$AttributeDescription
- net.minecraft.util.monitoring.jmx.package-info
+ net.minecraft.util.package-info
- net.minecraft.util.profiling.ActiveProfiler
+ net.minecraft.util.profiling.ActiveProfiler$PathEntry
- net.minecraft.util.profiling.ContinuousProfiler
+ net.minecraft.util.profiling.EmptyProfileResults
- net.minecraft.util.profiling.FilledProfileResults
+ net.minecraft.util.profiling.FilledProfileResults$1
- net.minecraft.util.profiling.FilledProfileResults$CounterCollector
+ net.minecraft.util.profiling.InactiveProfiler
+ net.minecraft.util.profiling.jfr.callback.package-info
- net.minecraft.util.profiling.jfr.callback.ProfiledDuration
+ net.minecraft.util.profiling.jfr.Environment
- net.minecraft.util.profiling.jfr.event.ChunkGenerationEvent
+ net.minecraft.util.profiling.jfr.event.ChunkGenerationEvent$Fields
- net.minecraft.util.profiling.jfr.event.NetworkSummaryEvent
+ net.minecraft.util.profiling.jfr.event.NetworkSummaryEvent$Fields
- net.minecraft.util.profiling.jfr.event.NetworkSummaryEvent$SumAggregation
- net.minecraft.util.profiling.jfr.event.package-info
+ net.minecraft.util.profiling.jfr.event.PacketEvent
- net.minecraft.util.profiling.jfr.event.PacketEvent$Fields
+ net.minecraft.util.profiling.jfr.event.PacketReceivedEvent
- net.minecraft.util.profiling.jfr.event.PacketSentEvent
+ net.minecraft.util.profiling.jfr.event.ServerTickTimeEvent
- net.minecraft.util.profiling.jfr.event.ServerTickTimeEvent$Fields
+ net.minecraft.util.profiling.jfr.event.WorldLoadFinishedEvent
- net.minecraft.util.profiling.jfr.JfrProfiler
+ net.minecraft.util.profiling.jfr.JfrProfiler$1
- net.minecraft.util.profiling.jfr.JvmProfiler
+ net.minecraft.util.profiling.jfr.JvmProfiler$NoOpProfiler
+ net.minecraft.util.profiling.jfr.package-info
- net.minecraft.util.profiling.jfr.parse.JfrStatsParser
+ net.minecraft.util.profiling.jfr.parse.JfrStatsParser$1
- net.minecraft.util.profiling.jfr.parse.JfrStatsParser$MutableCountAndSize
+ net.minecraft.util.profiling.jfr.parse.JfrStatsResult
- net.minecraft.util.profiling.jfr.parse.package-info
- net.minecraft.util.profiling.jfr.Percentiles
+ net.minecraft.util.profiling.jfr.serialize.JfrResultJsonSerializer
- net.minecraft.util.profiling.jfr.serialize.package-info
+ net.minecraft.util.profiling.jfr.stats.ChunkGenStat
- net.minecraft.util.profiling.jfr.stats.CpuLoadStat
+ net.minecraft.util.profiling.jfr.stats.FileIOStat
- net.minecraft.util.profiling.jfr.stats.FileIOStat$Summary
+ net.minecraft.util.profiling.jfr.stats.GcHeapStat
- net.minecraft.util.profiling.jfr.stats.GcHeapStat$Summary
+ net.minecraft.util.profiling.jfr.stats.GcHeapStat$Timing
- net.minecraft.util.profiling.jfr.stats.NetworkPacketSummary
+ net.minecraft.util.profiling.jfr.stats.NetworkPacketSummary$PacketCountAndSize
- net.minecraft.util.profiling.jfr.stats.NetworkPacketSummary$PacketIdentification
+ net.minecraft.util.profiling.jfr.stats.package-info
+ net.minecraft.util.profiling.jfr.stats.ThreadAllocationStat
- net.minecraft.util.profiling.jfr.stats.ThreadAllocationStat$Summary
+ net.minecraft.util.profiling.jfr.stats.TickTimeStat
+ net.minecraft.util.profiling.jfr.stats.TimedStat
- net.minecraft.util.profiling.jfr.stats.TimedStatSummary
- net.minecraft.util.profiling.jfr.stats.TimeStamped
+ net.minecraft.util.profiling.jfr.SummaryReporter
- net.minecraft.util.profiling.metrics.MetricCategory
+ net.minecraft.util.profiling.metrics.MetricSampler
- net.minecraft.util.profiling.metrics.MetricSampler$MetricSamplerBuilder
+ net.minecraft.util.profiling.metrics.MetricSampler$SamplerResult
- net.minecraft.util.profiling.metrics.MetricSampler$ThresholdTest
+ net.minecraft.util.profiling.metrics.MetricSampler$ValueIncreasedByPercentage
- net.minecraft.util.profiling.metrics.MetricsRegistry
+ net.minecraft.util.profiling.metrics.MetricsRegistry$AggregatedMetricSampler
- net.minecraft.util.profiling.metrics.MetricsSamplerProvider
- net.minecraft.util.profiling.metrics.package-info
+ net.minecraft.util.profiling.metrics.ProfilerMeasured
+ net.minecraft.util.profiling.metrics.profiling.ActiveMetricsRecorder
- net.minecraft.util.profiling.metrics.profiling.InactiveMetricsRecorder
+ net.minecraft.util.profiling.metrics.profiling.MetricsRecorder
- net.minecraft.util.profiling.metrics.profiling.package-info
- net.minecraft.util.profiling.metrics.profiling.ProfilerSamplerAdapter
+ net.minecraft.util.profiling.metrics.profiling.ServerMetricsSamplersProvider
- net.minecraft.util.profiling.metrics.profiling.ServerMetricsSamplersProvider$1
+ net.minecraft.util.profiling.metrics.profiling.ServerMetricsSamplersProvider$CpuStats
+ net.minecraft.util.profiling.metrics.storage.MetricsPersister
+ net.minecraft.util.profiling.metrics.storage.package-info
- net.minecraft.util.profiling.metrics.storage.RecordedDeviation
- net.minecraft.util.profiling.package-info
- net.minecraft.util.profiling.ProfileCollector
+ net.minecraft.util.profiling.ProfileResults
- net.minecraft.util.profiling.ProfilerFiller
+ net.minecraft.util.profiling.ProfilerFiller$1
- net.minecraft.util.profiling.ProfilerPathEntry
+ net.minecraft.util.profiling.ResultField
- net.minecraft.util.profiling.SingleTickProfiler
+ net.minecraft.util.random.package-info
+ net.minecraft.util.random.SimpleWeightedRandomList
- net.minecraft.util.random.SimpleWeightedRandomList$Builder
+ net.minecraft.util.random.Weight
- net.minecraft.util.random.WeightedEntry
+ net.minecraft.util.random.WeightedEntry$IntrusiveBase
- net.minecraft.util.random.WeightedEntry$Wrapper
+ net.minecraft.util.random.WeightedRandom
- net.minecraft.util.random.WeightedRandomList
- net.minecraft.util.RgbTxt$Entry
- net.minecraft.util.thread.BlockableEventLoop
+ net.minecraft.util.thread.NamedThreadFactory
- net.minecraft.util.thread.package-info
- net.minecraft.util.thread.ProcessorHandle
+ net.minecraft.util.thread.ProcessorHandle$1
- net.minecraft.util.thread.ProcessorMailbox
+ net.minecraft.util.thread.ReentrantBlockableEventLoop
- net.minecraft.util.thread.StrictQueue
+ net.minecraft.util.thread.StrictQueue$FixedPriorityQueue
- net.minecraft.util.thread.StrictQueue$IntRunnable
+ net.minecraft.util.thread.StrictQueue$QueueStrictQueue
+ net.minecraft.util.valueproviders.BiasedToBottomInt
- net.minecraft.util.valueproviders.ClampedInt
+ net.minecraft.util.valueproviders.ClampedNormalFloat
- net.minecraft.util.valueproviders.ClampedNormalInt
+ net.minecraft.util.valueproviders.ConstantFloat
- net.minecraft.util.valueproviders.ConstantInt
+ net.minecraft.util.valueproviders.FloatProvider
- net.minecraft.util.valueproviders.FloatProviderType
+ net.minecraft.util.valueproviders.IntProvider
- net.minecraft.util.valueproviders.IntProviderType
+ net.minecraft.util.valueproviders.MultipliedFloats
+ net.minecraft.util.valueproviders.package-info
- net.minecraft.util.valueproviders.SampledFloat
+ net.minecraft.util.valueproviders.TrapezoidFloat
- net.minecraft.util.valueproviders.UniformFloat
+ net.minecraft.util.valueproviders.UniformInt
- net.minecraft.util.valueproviders.WeightedListInt
+ net.minecraft.util.worldupdate.package-info
- net.minecraft.util.worldupdate.WorldUpgrader
- net.minecraft.voting.package-info
- net.minecraft.voting.rules.actual.AutoJumpAlternatives
- net.minecraft.voting.rules.actual.BinaryGameRuleRule$RuleRuleChange
- net.minecraft.voting.rules.actual.BlockFlammabilityRule
- net.minecraft.voting.rules.actual.BlockMapRule
- net.minecraft.voting.rules.actual.BlockModelReplacementRule$PotentialEntry
- net.minecraft.voting.rules.actual.BlockReplaceSingleRule
- net.minecraft.voting.rules.actual.ChickenEggRule
- net.minecraft.voting.rules.actual.CodepointStyleRule
- net.minecraft.voting.rules.actual.ColorRule
- net.minecraft.voting.rules.actual.CopySkinRule$CopySkinRuleChange
- net.minecraft.voting.rules.actual.DoubleOrHalfDamageTypeMapRule
- net.minecraft.voting.rules.actual.ExplosionExtraPowerRule
- net.minecraft.voting.rules.actual.FoodType
- net.minecraft.voting.rules.actual.GiveEffectRule
- net.minecraft.voting.rules.actual.Goldifier
- net.minecraft.voting.rules.actual.IntegerGameRuleRule
- net.minecraft.voting.rules.actual.ItemDespawnTime
- net.minecraft.voting.rules.actual.ItemGiveRule
- net.minecraft.voting.rules.actual.ItemModelReplacementRule
- net.minecraft.voting.rules.actual.LavaReplaceRule
- net.minecraft.voting.rules.actual.LightEngineMode$1
- net.minecraft.voting.rules.actual.NameVisiblity
- net.minecraft.voting.rules.actual.OptimizationRule
- net.minecraft.voting.rules.actual.ParentTrapRule$ParentTrapRuleChange
- net.minecraft.voting.rules.actual.PlayerSetRule
- net.minecraft.voting.rules.actual.RecipeFlip
- net.minecraft.voting.rules.actual.ReplaceItemsRule$ItemGenerator
- net.minecraft.voting.rules.actual.RuleFeatureToggles
- net.minecraft.voting.rules.actual.TheJokeRule
- net.minecraft.voting.rules.actual.ThreadedAnvilChunkStorage
- net.minecraft.voting.rules.actual.ThreadedAnvilChunkStorage$Change
- net.minecraft.voting.rules.actual.TransformEntityRule$TransformRuleChange
- net.minecraft.voting.rules.actual.TransformScaleRule$ScaleRuleChange
- net.minecraft.voting.rules.actual.VillagerPaymentRule
- net.minecraft.voting.rules.actual.WorldShape
- net.minecraft.voting.rules.BooleanRule$BooleanRuleChange
- net.minecraft.voting.rules.CounterRule$1
- net.minecraft.voting.rules.CounterRule$Simple
- net.minecraft.voting.rules.DoubleOrHalfRule
- net.minecraft.voting.rules.EnumRule$1
- net.minecraft.voting.rules.FixedOrRandomKeyRule
- net.minecraft.voting.rules.FixedOrRandomKeyRule$Change
- net.minecraft.voting.rules.MapRule$1
- net.minecraft.voting.rules.OneShotRule
- net.minecraft.voting.rules.OneShotRule$OneShotRuleChange
- net.minecraft.voting.rules.OneShotRule$Simple
- net.minecraft.voting.rules.package-info
- net.minecraft.voting.rules.RandomNumberRule$1
- net.minecraft.voting.rules.RandomNumberRule$RandomInt
- net.minecraft.voting.rules.ResourceKeyReplacementRule
- net.minecraft.voting.rules.ResourceKeySingleRule
- net.minecraft.voting.rules.ResourceKeySingleRule$Change
- net.minecraft.voting.rules.RuleAction
- net.minecraft.voting.rules.RuleChange$1
- net.minecraft.voting.rules.Rules
- net.minecraft.voting.rules.Rules$10
- net.minecraft.voting.rules.Rules$12
- net.minecraft.voting.rules.Rules$14
- net.minecraft.voting.rules.Rules$16
- net.minecraft.voting.rules.Rules$18
- net.minecraft.voting.rules.Rules$2
- net.minecraft.voting.rules.Rules$21
- net.minecraft.voting.rules.Rules$23
- net.minecraft.voting.rules.Rules$25
- net.minecraft.voting.rules.Rules$27
- net.minecraft.voting.rules.Rules$29
- net.minecraft.voting.rules.Rules$30
- net.minecraft.voting.rules.Rules$32
- net.minecraft.voting.rules.Rules$34
- net.minecraft.voting.rules.Rules$36
- net.minecraft.voting.rules.Rules$38
- net.minecraft.voting.rules.Rules$4
- net.minecraft.voting.rules.Rules$41
- net.minecraft.voting.rules.Rules$43
- net.minecraft.voting.rules.Rules$6
- net.minecraft.voting.rules.Rules$8
- net.minecraft.voting.rules.SetRule
- net.minecraft.voting.rules.UniformIntRule
- net.minecraft.voting.rules.UniformIntRule$Change
- net.minecraft.voting.rules.VotingCostRule$1
- net.minecraft.voting.VoteCommand
- net.minecraft.voting.votes.ClientVote$ClientOption
- net.minecraft.voting.votes.FinishedVote
- net.minecraft.voting.votes.FinishedVote$1ResultPair
- net.minecraft.voting.votes.OptionId
- net.minecraft.voting.votes.OptionVotes
- net.minecraft.voting.votes.package-info
- net.minecraft.voting.votes.ServerVote$Effect
- net.minecraft.voting.votes.ServerVote$VoteGenerationOptions
- net.minecraft.voting.votes.ServerVoteStorage$OptionAccess
- net.minecraft.voting.votes.TieResolutionStrategy
- net.minecraft.voting.votes.VoteResults$OptionResult
- net.minecraft.voting.votes.VoterMap
- net.minecraft.voting.votes.VoteStorage
- net.minecraft.voting.votes.VotingMaterial$1
- net.minecraft.voting.votes.VotingMaterial$Cost
- net.minecraft.voting.votes.VotingMaterial$Type
- net.minecraft.voting.votes.VotingMaterial$Type$2
- net.minecraft.voting.votes.VotingMaterial$Type$4
- net.minecraft.voting.votes.VotingMaterial$VotingItem
- net.minecraft.voting.votes.VotingMaterial$VotingResource$1
- net.minecraft.world.entity.ai.attributes.Attribute
+ net.minecraft.world.entity.ai.attributes.AttributeInstance
- net.minecraft.world.entity.ai.attributes.AttributeMap
+ net.minecraft.world.entity.ai.attributes.AttributeModifier
- net.minecraft.world.entity.ai.attributes.AttributeModifier$Operation
+ net.minecraft.world.entity.ai.attributes.Attributes
+ net.minecraft.world.entity.ai.attributes.AttributeSupplier
- net.minecraft.world.entity.ai.attributes.AttributeSupplier$Builder
- net.minecraft.world.entity.ai.attributes.DefaultAttributes
- net.minecraft.world.entity.ai.attributes.package-info
+ net.minecraft.world.entity.ai.attributes.RangedAttribute
+ net.minecraft.world.entity.ai.behavior.AcquirePoi
- net.minecraft.world.entity.ai.behavior.AcquirePoi$JitteredLinearRetry
+ net.minecraft.world.entity.ai.behavior.AnimalMakeLove
- net.minecraft.world.entity.ai.behavior.AnimalPanic
+ net.minecraft.world.entity.ai.behavior.AssignProfessionFromJobSite
- net.minecraft.world.entity.ai.behavior.BabyFollowAdult
+ net.minecraft.world.entity.ai.behavior.BackUpIfTooClose
- net.minecraft.world.entity.ai.behavior.BecomePassiveIfMemoryPresent
+ net.minecraft.world.entity.ai.behavior.Behavior
- net.minecraft.world.entity.ai.behavior.Behavior$Status
+ net.minecraft.world.entity.ai.behavior.BehaviorControl
- net.minecraft.world.entity.ai.behavior.BehaviorUtils
+ net.minecraft.world.entity.ai.behavior.BlockPosTracker
- net.minecraft.world.entity.ai.behavior.CelebrateVillagersSurvivedRaid
+ net.minecraft.world.entity.ai.behavior.CopyMemoryWithExpiry
- net.minecraft.world.entity.ai.behavior.CountDownCooldownTicks
+ net.minecraft.world.entity.ai.behavior.Croak
- net.minecraft.world.entity.ai.behavior.CrossbowAttack
+ net.minecraft.world.entity.ai.behavior.CrossbowAttack$CrossbowState
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$1
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Constant
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Constant$1
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$1
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$2
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$3
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$4
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$5
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Instance$Mu
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$Mu
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$PureMemory
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$PureMemory$1
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$TriggerWithResult
+ net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$TriggerWrapper
- net.minecraft.world.entity.ai.behavior.declarative.BehaviorBuilder$TriggerWrapper$1
+ net.minecraft.world.entity.ai.behavior.declarative.MemoryAccessor
- net.minecraft.world.entity.ai.behavior.declarative.MemoryCondition
+ net.minecraft.world.entity.ai.behavior.declarative.MemoryCondition$Absent
- net.minecraft.world.entity.ai.behavior.declarative.MemoryCondition$Present
+ net.minecraft.world.entity.ai.behavior.declarative.MemoryCondition$Registered
+ net.minecraft.world.entity.ai.behavior.declarative.package-info
- net.minecraft.world.entity.ai.behavior.declarative.Trigger
- net.minecraft.world.entity.ai.behavior.DismountOrSkipMounting
+ net.minecraft.world.entity.ai.behavior.DoNothing
- net.minecraft.world.entity.ai.behavior.EntityTracker
+ net.minecraft.world.entity.ai.behavior.EraseMemoryIf
- net.minecraft.world.entity.ai.behavior.FollowTemptation
+ net.minecraft.world.entity.ai.behavior.GateBehavior
- net.minecraft.world.entity.ai.behavior.GateBehavior$OrderPolicy
+ net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy
- net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$1
+ net.minecraft.world.entity.ai.behavior.GateBehavior$RunningPolicy$2
- net.minecraft.world.entity.ai.behavior.GiveGiftToHero
+ net.minecraft.world.entity.ai.behavior.GoAndGiveItemsToTarget
- net.minecraft.world.entity.ai.behavior.GoToClosestVillage
+ net.minecraft.world.entity.ai.behavior.GoToPotentialJobSite
- net.minecraft.world.entity.ai.behavior.GoToTargetLocation
+ net.minecraft.world.entity.ai.behavior.GoToWantedItem
- net.minecraft.world.entity.ai.behavior.HarvestFarmland
+ net.minecraft.world.entity.ai.behavior.InsideBrownianWalk
- net.minecraft.world.entity.ai.behavior.InteractWith
+ net.minecraft.world.entity.ai.behavior.InteractWithDoor
- net.minecraft.world.entity.ai.behavior.JumpOnBed
+ net.minecraft.world.entity.ai.behavior.LocateHidingPlace
- net.minecraft.world.entity.ai.behavior.LongJumpMidJump
+ net.minecraft.world.entity.ai.behavior.LongJumpToPreferredBlock
- net.minecraft.world.entity.ai.behavior.LongJumpToRandomPos
+ net.minecraft.world.entity.ai.behavior.LongJumpToRandomPos$PossibleJump
- net.minecraft.world.entity.ai.behavior.LookAndFollowTradingPlayerSink
+ net.minecraft.world.entity.ai.behavior.LookAtTargetSink
- net.minecraft.world.entity.ai.behavior.MeleeAttack
+ net.minecraft.world.entity.ai.behavior.Mount
- net.minecraft.world.entity.ai.behavior.MoveToSkySeeingSpot
+ net.minecraft.world.entity.ai.behavior.MoveToTargetSink
- net.minecraft.world.entity.ai.behavior.OneShot
- net.minecraft.world.entity.ai.behavior.package-info
+ net.minecraft.world.entity.ai.behavior.PlayTagWithOtherKids
- net.minecraft.world.entity.ai.behavior.PoiCompetitorScan
+ net.minecraft.world.entity.ai.behavior.PositionTracker
- net.minecraft.world.entity.ai.behavior.PrepareRamNearestTarget
+ net.minecraft.world.entity.ai.behavior.PrepareRamNearestTarget$RamCandidate
- net.minecraft.world.entity.ai.behavior.RamTarget
+ net.minecraft.world.entity.ai.behavior.RandomLookAround
- net.minecraft.world.entity.ai.behavior.RandomStroll
+ net.minecraft.world.entity.ai.behavior.ReactToBell
- net.minecraft.world.entity.ai.behavior.ResetProfession
+ net.minecraft.world.entity.ai.behavior.ResetRaidStatus
- net.minecraft.world.entity.ai.behavior.RingBell
+ net.minecraft.world.entity.ai.behavior.RunOne
- net.minecraft.world.entity.ai.behavior.SetClosestHomeAsWalkTarget
+ net.minecraft.world.entity.ai.behavior.SetEntityLookTarget
- net.minecraft.world.entity.ai.behavior.SetEntityLookTargetSometimes
+ net.minecraft.world.entity.ai.behavior.SetEntityLookTargetSometimes$Ticker
- net.minecraft.world.entity.ai.behavior.SetHiddenState
+ net.minecraft.world.entity.ai.behavior.SetLookAndInteract
- net.minecraft.world.entity.ai.behavior.SetRaidStatus
+ net.minecraft.world.entity.ai.behavior.SetWalkTargetAwayFrom
- net.minecraft.world.entity.ai.behavior.SetWalkTargetFromAttackTargetIfTargetOutOfReach
+ net.minecraft.world.entity.ai.behavior.SetWalkTargetFromBlockMemory
- net.minecraft.world.entity.ai.behavior.SetWalkTargetFromLookTarget
+ net.minecraft.world.entity.ai.behavior.ShowTradesToPlayer
- net.minecraft.world.entity.ai.behavior.ShufflingList
+ net.minecraft.world.entity.ai.behavior.ShufflingList$WeightedEntry
- net.minecraft.world.entity.ai.behavior.ShufflingList$WeightedEntry$1
+ net.minecraft.world.entity.ai.behavior.SleepInBed
- net.minecraft.world.entity.ai.behavior.SocializeAtBell
+ net.minecraft.world.entity.ai.behavior.StartAttacking
- net.minecraft.world.entity.ai.behavior.StartCelebratingIfTargetDead
+ net.minecraft.world.entity.ai.behavior.StayCloseToTarget
- net.minecraft.world.entity.ai.behavior.StopAttackingIfTargetInvalid
+ net.minecraft.world.entity.ai.behavior.StopBeingAngryIfTargetDead
- net.minecraft.world.entity.ai.behavior.StrollAroundPoi
+ net.minecraft.world.entity.ai.behavior.StrollToPoi
- net.minecraft.world.entity.ai.behavior.StrollToPoiList
+ net.minecraft.world.entity.ai.behavior.Swim
- net.minecraft.world.entity.ai.behavior.TradeWithVillager
+ net.minecraft.world.entity.ai.behavior.TriggerGate
- net.minecraft.world.entity.ai.behavior.TryFindLand
+ net.minecraft.world.entity.ai.behavior.TryFindLandNearWater
- net.minecraft.world.entity.ai.behavior.TryFindWater
+ net.minecraft.world.entity.ai.behavior.TryLaySpawnOnWaterNearLand
- net.minecraft.world.entity.ai.behavior.UpdateActivityFromSchedule
+ net.minecraft.world.entity.ai.behavior.UseBonemeal
- net.minecraft.world.entity.ai.behavior.ValidateNearbyPoi
+ net.minecraft.world.entity.ai.behavior.VillageBoundRandomStroll
- net.minecraft.world.entity.ai.behavior.VillagerCalmDown
+ net.minecraft.world.entity.ai.behavior.VillagerGoalPackages
- net.minecraft.world.entity.ai.behavior.VillagerMakeLove
+ net.minecraft.world.entity.ai.behavior.VillagerPanicTrigger
- net.minecraft.world.entity.ai.behavior.WakeUp
+ net.minecraft.world.entity.ai.behavior.warden.Digging
- net.minecraft.world.entity.ai.behavior.warden.Emerging
+ net.minecraft.world.entity.ai.behavior.warden.ForceUnmount
- net.minecraft.world.entity.ai.behavior.warden.package-info
- net.minecraft.world.entity.ai.behavior.warden.Roar
+ net.minecraft.world.entity.ai.behavior.warden.SetRoarTarget
- net.minecraft.world.entity.ai.behavior.warden.SetWardenLookTarget
+ net.minecraft.world.entity.ai.behavior.warden.Sniffing
- net.minecraft.world.entity.ai.behavior.warden.SonicBoom
+ net.minecraft.world.entity.ai.behavior.warden.TryToSniff
+ net.minecraft.world.entity.ai.behavior.WorkAtComposter
- net.minecraft.world.entity.ai.behavior.WorkAtPoi
+ net.minecraft.world.entity.ai.behavior.YieldJobSite
- net.minecraft.world.entity.ai.Brain
+ net.minecraft.world.entity.ai.Brain$1
- net.minecraft.world.entity.ai.Brain$MemoryValue
+ net.minecraft.world.entity.ai.Brain$Provider
+ net.minecraft.world.entity.ai.control.BodyRotationControl
- net.minecraft.world.entity.ai.control.Control
+ net.minecraft.world.entity.ai.control.FlyingMoveControl
- net.minecraft.world.entity.ai.control.JumpControl
+ net.minecraft.world.entity.ai.control.LookControl
- net.minecraft.world.entity.ai.control.MoveControl
+ net.minecraft.world.entity.ai.control.MoveControl$Operation
- net.minecraft.world.entity.ai.control.package-info
- net.minecraft.world.entity.ai.control.SmoothSwimmingLookControl
+ net.minecraft.world.entity.ai.control.SmoothSwimmingMoveControl
+ net.minecraft.world.entity.ai.goal.AvoidEntityGoal
- net.minecraft.world.entity.ai.goal.BegGoal
+ net.minecraft.world.entity.ai.goal.BoatGoals
- net.minecraft.world.entity.ai.goal.BreakDoorGoal
+ net.minecraft.world.entity.ai.goal.BreathAirGoal
- net.minecraft.world.entity.ai.goal.BreedGoal
+ net.minecraft.world.entity.ai.goal.CatLieOnBedGoal
- net.minecraft.world.entity.ai.goal.CatSitOnBlockGoal
+ net.minecraft.world.entity.ai.goal.ClimbOnTopOfPowderSnowGoal
- net.minecraft.world.entity.ai.goal.DolphinJumpGoal
+ net.minecraft.world.entity.ai.goal.DoorInteractGoal
- net.minecraft.world.entity.ai.goal.EatBlockGoal
+ net.minecraft.world.entity.ai.goal.FleeSunGoal
- net.minecraft.world.entity.ai.goal.FloatGoal
+ net.minecraft.world.entity.ai.goal.FollowBoatGoal
- net.minecraft.world.entity.ai.goal.FollowFlockLeaderGoal
+ net.minecraft.world.entity.ai.goal.FollowMobGoal
- net.minecraft.world.entity.ai.goal.FollowOwnerGoal
+ net.minecraft.world.entity.ai.goal.FollowParentGoal
- net.minecraft.world.entity.ai.goal.Goal
+ net.minecraft.world.entity.ai.goal.Goal$Flag
- net.minecraft.world.entity.ai.goal.GoalSelector
+ net.minecraft.world.entity.ai.goal.GoalSelector$1
- net.minecraft.world.entity.ai.goal.GoalSelector$2
+ net.minecraft.world.entity.ai.goal.GolemRandomStrollInVillageGoal
- net.minecraft.world.entity.ai.goal.InteractGoal
+ net.minecraft.world.entity.ai.goal.JumpGoal
- net.minecraft.world.entity.ai.goal.LandOnOwnersShoulderGoal
+ net.minecraft.world.entity.ai.goal.LeapAtTargetGoal
- net.minecraft.world.entity.ai.goal.LlamaFollowCaravanGoal
+ net.minecraft.world.entity.ai.goal.LookAtPlayerGoal
- net.minecraft.world.entity.ai.goal.LookAtTradingPlayerGoal
+ net.minecraft.world.entity.ai.goal.MeleeAttackGoal
- net.minecraft.world.entity.ai.goal.MoveBackToVillageGoal
+ net.minecraft.world.entity.ai.goal.MoveThroughVillageGoal
- net.minecraft.world.entity.ai.goal.MoveToBlockGoal
+ net.minecraft.world.entity.ai.goal.MoveTowardsRestrictionGoal
- net.minecraft.world.entity.ai.goal.MoveTowardsTargetGoal
+ net.minecraft.world.entity.ai.goal.OcelotAttackGoal
- net.minecraft.world.entity.ai.goal.OfferFlowerGoal
+ net.minecraft.world.entity.ai.goal.OpenDoorGoal
- net.minecraft.world.entity.ai.goal.package-info
- net.minecraft.world.entity.ai.goal.PanicGoal
+ net.minecraft.world.entity.ai.goal.PathfindToRaidGoal
- net.minecraft.world.entity.ai.goal.RandomLookAroundGoal
+ net.minecraft.world.entity.ai.goal.RandomStandGoal
- net.minecraft.world.entity.ai.goal.RandomStrollGoal
+ net.minecraft.world.entity.ai.goal.RandomSwimmingGoal
- net.minecraft.world.entity.ai.goal.RangedAttackGoal
+ net.minecraft.world.entity.ai.goal.RangedBowAttackGoal
- net.minecraft.world.entity.ai.goal.RangedCrossbowAttackGoal
+ net.minecraft.world.entity.ai.goal.RangedCrossbowAttackGoal$CrossbowState
- net.minecraft.world.entity.ai.goal.RemoveBlockGoal
+ net.minecraft.world.entity.ai.goal.RestrictSunGoal
- net.minecraft.world.entity.ai.goal.RunAroundLikeCrazyGoal
+ net.minecraft.world.entity.ai.goal.SitWhenOrderedToGoal
- net.minecraft.world.entity.ai.goal.StrollThroughVillageGoal
+ net.minecraft.world.entity.ai.goal.SwellGoal
+ net.minecraft.world.entity.ai.goal.target.DefendVillageTargetGoal
- net.minecraft.world.entity.ai.goal.target.HurtByTargetGoal
+ net.minecraft.world.entity.ai.goal.target.NearestAttackableTargetGoal
- net.minecraft.world.entity.ai.goal.target.NearestAttackableWitchTargetGoal
+ net.minecraft.world.entity.ai.goal.target.NearestHealableRaiderTargetGoal
- net.minecraft.world.entity.ai.goal.target.NonTameRandomTargetGoal
+ net.minecraft.world.entity.ai.goal.target.OwnerHurtByTargetGoal
- net.minecraft.world.entity.ai.goal.target.OwnerHurtTargetGoal
+ net.minecraft.world.entity.ai.goal.target.package-info
+ net.minecraft.world.entity.ai.goal.target.ResetUniversalAngerTargetGoal
- net.minecraft.world.entity.ai.goal.target.TargetGoal
- net.minecraft.world.entity.ai.goal.TemptGoal
+ net.minecraft.world.entity.ai.goal.TradeWithPlayerGoal
- net.minecraft.world.entity.ai.goal.TryFindWaterGoal
+ net.minecraft.world.entity.ai.goal.UseItemGoal
- net.minecraft.world.entity.ai.goal.WaterAvoidingRandomFlyingGoal
+ net.minecraft.world.entity.ai.goal.WaterAvoidingRandomStrollGoal
- net.minecraft.world.entity.ai.goal.WrappedGoal
+ net.minecraft.world.entity.ai.goal.ZombieAttackGoal
- net.minecraft.world.entity.ai.gossip.GossipContainer
+ net.minecraft.world.entity.ai.gossip.GossipContainer$EntityGossips
- net.minecraft.world.entity.ai.gossip.GossipContainer$GossipEntry
+ net.minecraft.world.entity.ai.gossip.GossipType
- net.minecraft.world.entity.ai.gossip.package-info
+ net.minecraft.world.entity.ai.memory.ExpirableValue
- net.minecraft.world.entity.ai.memory.MemoryModuleType
+ net.minecraft.world.entity.ai.memory.MemoryStatus
- net.minecraft.world.entity.ai.memory.NearestVisibleLivingEntities
- net.minecraft.world.entity.ai.memory.package-info
+ net.minecraft.world.entity.ai.memory.WalkTarget
+ net.minecraft.world.entity.ai.navigation.AmphibiousPathNavigation
- net.minecraft.world.entity.ai.navigation.FlyingPathNavigation
+ net.minecraft.world.entity.ai.navigation.GroundPathNavigation
+ net.minecraft.world.entity.ai.navigation.package-info
- net.minecraft.world.entity.ai.navigation.PathNavigation
+ net.minecraft.world.entity.ai.navigation.WallClimberNavigation
- net.minecraft.world.entity.ai.navigation.WaterBoundPathNavigation
- net.minecraft.world.entity.ai.package-info
+ net.minecraft.world.entity.ai.sensing.AdultSensor
- net.minecraft.world.entity.ai.sensing.AxolotlAttackablesSensor
+ net.minecraft.world.entity.ai.sensing.DummySensor
- net.minecraft.world.entity.ai.sensing.FrogAttackablesSensor
+ net.minecraft.world.entity.ai.sensing.GolemSensor
- net.minecraft.world.entity.ai.sensing.HoglinSpecificSensor
+ net.minecraft.world.entity.ai.sensing.HurtBySensor
- net.minecraft.world.entity.ai.sensing.IsInWaterSensor
+ net.minecraft.world.entity.ai.sensing.NearestBedSensor
- net.minecraft.world.entity.ai.sensing.NearestItemSensor
+ net.minecraft.world.entity.ai.sensing.NearestLivingEntitySensor
- net.minecraft.world.entity.ai.sensing.NearestVisibleLivingEntitySensor
- net.minecraft.world.entity.ai.sensing.package-info
+ net.minecraft.world.entity.ai.sensing.PiglinBruteSpecificSensor
- net.minecraft.world.entity.ai.sensing.PiglinSpecificSensor
+ net.minecraft.world.entity.ai.sensing.PlayerSensor
- net.minecraft.world.entity.ai.sensing.SecondaryPoiSensor
+ net.minecraft.world.entity.ai.sensing.Sensing
- net.minecraft.world.entity.ai.sensing.Sensor
+ net.minecraft.world.entity.ai.sensing.SensorType
- net.minecraft.world.entity.ai.sensing.TemptingSensor
+ net.minecraft.world.entity.ai.sensing.VillagerBabiesSensor
- net.minecraft.world.entity.ai.sensing.VillagerHostilesSensor
+ net.minecraft.world.entity.ai.sensing.WardenEntitySensor
- net.minecraft.world.entity.ai.targeting.package-info
+ net.minecraft.world.entity.ai.targeting.TargetingConditions
+ net.minecraft.world.entity.ai.util.AirAndWaterRandomPos
- net.minecraft.world.entity.ai.util.AirRandomPos
+ net.minecraft.world.entity.ai.util.DefaultRandomPos
- net.minecraft.world.entity.ai.util.GoalUtils
+ net.minecraft.world.entity.ai.util.HoverRandomPos
- net.minecraft.world.entity.ai.util.LandRandomPos
- net.minecraft.world.entity.ai.util.package-info
+ net.minecraft.world.entity.ai.util.RandomPos
+ net.minecraft.world.entity.ai.village.package-info
+ net.minecraft.world.entity.ai.village.poi.package-info
- net.minecraft.world.entity.ai.village.poi.PoiManager
+ net.minecraft.world.entity.ai.village.poi.PoiManager$DistanceTracker
- net.minecraft.world.entity.ai.village.poi.PoiManager$Occupancy
+ net.minecraft.world.entity.ai.village.poi.PoiRecord
- net.minecraft.world.entity.ai.village.poi.PoiSection
+ net.minecraft.world.entity.ai.village.poi.PoiType
- net.minecraft.world.entity.ai.village.poi.PoiTypes
+ net.minecraft.world.entity.ai.village.ReputationEventType
- net.minecraft.world.entity.ai.village.ReputationEventType$1
+ net.minecraft.world.entity.ai.village.VillageSiege
- net.minecraft.world.entity.ai.village.VillageSiege$State
- net.minecraft.world.entity.ambient.AmbientCreature
+ net.minecraft.world.entity.ambient.Bat
- net.minecraft.world.entity.ambient.package-info
+ net.minecraft.world.entity.animal.AbstractFish
- net.minecraft.world.entity.animal.AbstractFish$FishMoveControl
+ net.minecraft.world.entity.animal.AbstractFish$FishSwimGoal
- net.minecraft.world.entity.animal.AbstractGolem
+ net.minecraft.world.entity.animal.AbstractSchoolingFish
- net.minecraft.world.entity.animal.AbstractSchoolingFish$SchoolSpawnGroupData
+ net.minecraft.world.entity.animal.Animal
- net.minecraft.world.entity.animal.Bee
+ net.minecraft.world.entity.animal.Bee$1
- net.minecraft.world.entity.animal.Bee$BaseBeeGoal
+ net.minecraft.world.entity.animal.Bee$BeeAttackGoal
- net.minecraft.world.entity.animal.Bee$BeeBecomeAngryTargetGoal
+ net.minecraft.world.entity.animal.Bee$BeeEnterHiveGoal
- net.minecraft.world.entity.animal.Bee$BeeGoToHiveGoal
+ net.minecraft.world.entity.animal.Bee$BeeGoToKnownFlowerGoal
- net.minecraft.world.entity.animal.Bee$BeeGrowCropGoal
+ net.minecraft.world.entity.animal.Bee$BeeHurtByOtherGoal
- net.minecraft.world.entity.animal.Bee$BeeLocateHiveGoal
+ net.minecraft.world.entity.animal.Bee$BeeLookControl
- net.minecraft.world.entity.animal.Bee$BeelooningGoal
- net.minecraft.world.entity.animal.Bee$BeePollinateGoal
+ net.minecraft.world.entity.animal.Bee$BeeWanderGoal
- net.minecraft.world.entity.animal.Bee$MoveWithoutPathfindingGoal
- net.minecraft.world.entity.animal.MoonCow$MoonWalkControl
- net.minecraft.world.entity.Display$LinearFloatInterpolator
+ net.minecraft.world.entity.Display$LinearIntInterpolator
- net.minecraft.world.entity.Display$LinearlyInterpolatedBlockAnimator
- net.minecraft.world.entity.Display$StencilDisplay
- net.minecraft.world.entity.Entity$MoveFunction
+ net.minecraft.world.entity.Entity$MovementEmission
- net.minecraft.world.entity.Entity$RemovalReason
+ net.minecraft.world.entity.EntityDimensions
- net.minecraft.world.entity.EntityEvent
+ net.minecraft.world.entity.EntitySelector
- net.minecraft.world.entity.EntitySelector$MobCanWearArmorEntitySelector
+ net.minecraft.world.entity.EntityType
- net.minecraft.world.entity.EntityType$1
+ net.minecraft.world.entity.EntityType$Builder
- net.minecraft.world.entity.EntityType$EntityFactory
+ net.minecraft.world.entity.EquipmentSlot
- net.minecraft.world.entity.EquipmentSlot$Type
+ net.minecraft.world.entity.ExperienceOrb
- net.minecraft.world.entity.FlyingMob
+ net.minecraft.world.entity.GlowSquid
- net.minecraft.world.entity.HasCustomInventoryScreen
+ net.minecraft.world.entity.HumanoidArm
- net.minecraft.world.entity.Interaction
+ net.minecraft.world.entity.Interaction$PlayerAction
- net.minecraft.world.entity.item.ItemEntity$1
- net.minecraft.world.entity.item.package-info
+ net.minecraft.world.entity.item.PrimedTnt
- net.minecraft.world.entity.ItemBasedSteering
+ net.minecraft.world.entity.ItemSteerable
- net.minecraft.world.entity.LerpingModel
+ net.minecraft.world.entity.LightningBolt
- net.minecraft.world.entity.LivingEntity
+ net.minecraft.world.entity.LivingEntity$1
- net.minecraft.world.entity.LivingEntity$Fallsounds
+ net.minecraft.world.entity.Marker
- net.minecraft.world.entity.Mob
+ net.minecraft.world.entity.Mob$1
- net.minecraft.world.entity.MobCategory
+ net.minecraft.world.entity.MobSpawnType
- net.minecraft.world.entity.MobType
+ net.minecraft.world.entity.monster.AbstractIllager
- net.minecraft.world.entity.monster.AbstractIllager$IllagerArmPose
+ net.minecraft.world.entity.monster.AbstractIllager$RaiderOpenDoorGoal
- net.minecraft.world.entity.monster.AbstractSkeleton
+ net.minecraft.world.entity.monster.AbstractSkeleton$1
- net.minecraft.world.entity.monster.Blaze
+ net.minecraft.world.entity.monster.Blaze$BlazeAttackGoal
- net.minecraft.world.entity.monster.CaveSpider
+ net.minecraft.world.entity.monster.Creeper
- net.minecraft.world.entity.monster.CrossbowAttackMob
+ net.minecraft.world.entity.monster.Drowned
- net.minecraft.world.entity.monster.Drowned$DrownedAttackGoal
+ net.minecraft.world.entity.monster.Drowned$DrownedGoToBeachGoal
- net.minecraft.world.entity.monster.Drowned$DrownedGoToWaterGoal
+ net.minecraft.world.entity.monster.Drowned$DrownedMoveControl
- net.minecraft.world.entity.monster.Drowned$DrownedSwimUpGoal
+ net.minecraft.world.entity.monster.Drowned$DrownedTridentAttackGoal
- net.minecraft.world.entity.monster.ElderGuardian
+ net.minecraft.world.entity.monster.EnderMan
- net.minecraft.world.entity.monster.EnderMan$EndermanFreezeWhenLookedAt
+ net.minecraft.world.entity.monster.EnderMan$EndermanLeaveBlockGoal
- net.minecraft.world.entity.monster.EnderMan$EndermanLookForPlayerGoal
+ net.minecraft.world.entity.monster.EnderMan$EndermanTakeBlockGoal
- net.minecraft.world.entity.monster.Endermite
+ net.minecraft.world.entity.monster.Enemy
- net.minecraft.world.entity.monster.Evoker
+ net.minecraft.world.entity.monster.Evoker$EvokerAttackSpellGoal
- net.minecraft.world.entity.monster.Evoker$EvokerCastingSpellGoal
+ net.minecraft.world.entity.monster.Evoker$EvokerSummonSpellGoal
- net.minecraft.world.entity.monster.Evoker$EvokerWololoSpellGoal
+ net.minecraft.world.entity.monster.Ghast
- net.minecraft.world.entity.monster.Ghast$GhastLookGoal
+ net.minecraft.world.entity.monster.Ghast$GhastMoveControl
- net.minecraft.world.entity.monster.Ghast$GhastShootFireballGoal
+ net.minecraft.world.entity.monster.Ghast$RandomFloatAroundGoal
- net.minecraft.world.entity.monster.Giant
+ net.minecraft.world.entity.monster.Guardian
- net.minecraft.world.entity.monster.Guardian$GuardianAttackGoal
+ net.minecraft.world.entity.monster.Guardian$GuardianAttackSelector
- net.minecraft.world.entity.monster.Guardian$GuardianMoveControl
+ net.minecraft.world.entity.monster.hoglin.Hoglin
- net.minecraft.world.entity.monster.hoglin.HoglinAi
+ net.minecraft.world.entity.monster.hoglin.HoglinBase
- net.minecraft.world.entity.monster.hoglin.package-info
+ net.minecraft.world.entity.monster.Husk
- net.minecraft.world.entity.monster.Illusioner
+ net.minecraft.world.entity.monster.Illusioner$IllusionerBlindnessSpellGoal
- net.minecraft.world.entity.monster.Illusioner$IllusionerMirrorSpellGoal
+ net.minecraft.world.entity.monster.MagmaCube
- net.minecraft.world.entity.monster.Monster
+ net.minecraft.world.entity.monster.package-info
+ net.minecraft.world.entity.monster.PatrollingMonster
- net.minecraft.world.entity.monster.PatrollingMonster$LongDistancePatrolGoal
+ net.minecraft.world.entity.monster.Phantom
- net.minecraft.world.entity.monster.Phantom$AttackPhase
+ net.minecraft.world.entity.monster.Phantom$PhantomAttackPlayerTargetGoal
- net.minecraft.world.entity.monster.Phantom$PhantomAttackStrategyGoal
+ net.minecraft.world.entity.monster.Phantom$PhantomBodyRotationControl
- net.minecraft.world.entity.monster.Phantom$PhantomCircleAroundAnchorGoal
+ net.minecraft.world.entity.monster.Phantom$PhantomLookControl
- net.minecraft.world.entity.monster.Phantom$PhantomMoveControl
+ net.minecraft.world.entity.monster.Phantom$PhantomMoveTargetGoal
- net.minecraft.world.entity.monster.Phantom$PhantomSweepAttackGoal
- net.minecraft.world.entity.monster.piglin.AbstractPiglin
- net.minecraft.world.entity.monster.piglin.package-info
+ net.minecraft.world.entity.monster.piglin.Piglin
- net.minecraft.world.entity.monster.piglin.PiglinAi
+ net.minecraft.world.entity.monster.piglin.PiglinArmPose
- net.minecraft.world.entity.monster.piglin.PiglinBrute
+ net.minecraft.world.entity.monster.piglin.PiglinBruteAi
- net.minecraft.world.entity.monster.piglin.RememberIfHoglinWasKilled
+ net.minecraft.world.entity.monster.piglin.StartAdmiringItemIfSeen
- net.minecraft.world.entity.monster.piglin.StartHuntingHoglin
+ net.minecraft.world.entity.monster.piglin.StopAdmiringIfItemTooFarAway
- net.minecraft.world.entity.monster.piglin.StopAdmiringIfTiredOfTryingToReachItem
+ net.minecraft.world.entity.monster.piglin.StopHoldingItemIfNoLongerAdmiring
+ net.minecraft.world.entity.monster.Pillager
- net.minecraft.world.entity.monster.RangedAttackMob
+ net.minecraft.world.entity.monster.Ravager
- net.minecraft.world.entity.monster.Ravager$RavagerMeleeAttackGoal
+ net.minecraft.world.entity.monster.warden.AngerLevel
- net.minecraft.world.entity.monster.warden.AngerManagement
+ net.minecraft.world.entity.monster.warden.AngerManagement$1
- net.minecraft.world.entity.monster.warden.AngerManagement$Sorter
+ net.minecraft.world.entity.monster.warden.package-info
+ net.minecraft.world.entity.monster.warden.Warden
- net.minecraft.world.entity.monster.warden.Warden$1
+ net.minecraft.world.entity.monster.warden.Warden$1$1
- net.minecraft.world.entity.monster.warden.Warden$2
+ net.minecraft.world.entity.monster.warden.WardenAi
- net.minecraft.world.entity.monster.warden.WardenSpawnTracker
- net.minecraft.world.entity.monster.Zombie$1
+ net.minecraft.world.entity.monster.Zombie$ZombieAttackTurtleEggGoal
- net.minecraft.world.entity.monster.Zombie$ZombieGroupData
+ net.minecraft.world.entity.monster.ZombieVillager
- net.minecraft.world.entity.monster.ZombifiedPiglin
+ net.minecraft.world.entity.MoverType
- net.minecraft.world.entity.NeutralMob
- net.minecraft.world.entity.npc.AbstractVillager
+ net.minecraft.world.entity.npc.CatSpawner
- net.minecraft.world.entity.npc.ClientSideMerchant
+ net.minecraft.world.entity.npc.InventoryCarrier
- net.minecraft.world.entity.npc.Npc
+ net.minecraft.world.entity.npc.package-info
+ net.minecraft.world.entity.npc.Villager
- net.minecraft.world.entity.npc.VillagerData
+ net.minecraft.world.entity.npc.VillagerDataHolder
- net.minecraft.world.entity.npc.VillagerProfession
+ net.minecraft.world.entity.npc.VillagerTrades
- net.minecraft.world.entity.npc.VillagerTrades$DyedArmorForEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$EmeraldForItems
- net.minecraft.world.entity.npc.VillagerTrades$EmeraldsForVillagerTypeItem
+ net.minecraft.world.entity.npc.VillagerTrades$EnchantBookForEmeralds
- net.minecraft.world.entity.npc.VillagerTrades$EnchantedItemForEmeralds
+ net.minecraft.world.entity.npc.VillagerTrades$ItemListing
- net.minecraft.world.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
+ net.minecraft.world.entity.npc.VillagerTrades$ItemsForEmeralds
- net.minecraft.world.entity.npc.VillagerTrades$SuspiciousStewForEmerald
+ net.minecraft.world.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
- net.minecraft.world.entity.npc.VillagerTrades$TreasureMapForEmeralds
+ net.minecraft.world.entity.npc.VillagerType
- net.minecraft.world.entity.npc.WanderingTrader
+ net.minecraft.world.entity.npc.WanderingTrader$WanderToPositionGoal
- net.minecraft.world.entity.npc.WanderingTraderSpawner
+ net.minecraft.world.entity.OwnableEntity
- net.minecraft.world.entity.package-info
- net.minecraft.world.entity.PathfinderMob
+ net.minecraft.world.entity.player.Abilities
- net.minecraft.world.entity.player.ChatVisiblity
+ net.minecraft.world.entity.player.Inventory
- net.minecraft.world.entity.player.package-info
- net.minecraft.world.entity.player.Player
+ net.minecraft.world.entity.player.Player$1
- net.minecraft.world.entity.player.Player$BedSleepingProblem
+ net.minecraft.world.entity.player.PlayerModelPart
- net.minecraft.world.entity.player.ProfileKeyPair
+ net.minecraft.world.entity.player.ProfilePublicKey
- net.minecraft.world.entity.player.ProfilePublicKey$Data
+ net.minecraft.world.entity.player.ProfilePublicKey$ValidationException
- net.minecraft.world.entity.player.StackedContents
+ net.minecraft.world.entity.player.StackedContents$RecipePicker
+ net.minecraft.world.entity.PlayerRideable
- net.minecraft.world.entity.PlayerRideableJumping
+ net.minecraft.world.entity.Pose
- net.minecraft.world.entity.PowerableMob
+ net.minecraft.world.entity.projectile.AbstractArrow
- net.minecraft.world.entity.projectile.AbstractArrow$1
+ net.minecraft.world.entity.projectile.AbstractArrow$Pickup
- net.minecraft.world.entity.projectile.AbstractHurtingProjectile
+ net.minecraft.world.entity.projectile.Arrow
- net.minecraft.world.entity.projectile.DragonFireball
+ net.minecraft.world.entity.projectile.EvokerFangs
- net.minecraft.world.entity.projectile.EyeOfEnder
+ net.minecraft.world.entity.projectile.Fireball
- net.minecraft.world.entity.projectile.FireworkRocketEntity
+ net.minecraft.world.entity.projectile.FishingHook
- net.minecraft.world.entity.projectile.FishingHook$1
+ net.minecraft.world.entity.projectile.FishingHook$FishHookState
- net.minecraft.world.entity.projectile.FishingHook$OpenWaterType
+ net.minecraft.world.entity.projectile.ItemSupplier
- net.minecraft.world.entity.projectile.LargeFireball
+ net.minecraft.world.entity.projectile.LlamaSpit
- net.minecraft.world.entity.projectile.package-info
- net.minecraft.world.entity.projectile.Projectile
+ net.minecraft.world.entity.projectile.ProjectileUtil
- net.minecraft.world.entity.projectile.ShulkerBullet
+ net.minecraft.world.entity.projectile.SmallFireball
- net.minecraft.world.entity.projectile.Snowball
+ net.minecraft.world.entity.projectile.SpectralArrow
- net.minecraft.world.entity.projectile.ThrowableItemProjectile
+ net.minecraft.world.entity.projectile.ThrowableProjectile
- net.minecraft.world.entity.projectile.ThrownEgg
+ net.minecraft.world.entity.projectile.ThrownEnderpearl
- net.minecraft.world.entity.projectile.ThrownExperienceBottle
+ net.minecraft.world.entity.projectile.ThrownPotion
- net.minecraft.world.entity.projectile.ThrownTrident
+ net.minecraft.world.entity.projectile.WitherSkull
+ net.minecraft.world.entity.raid.package-info
+ net.minecraft.world.entity.raid.Raid
- net.minecraft.world.entity.raid.Raid$1
- net.minecraft.world.entity.raid.Raid$RaiderType
+ net.minecraft.world.entity.raid.Raid$RaidStatus
+ net.minecraft.world.entity.raid.Raider
- net.minecraft.world.entity.raid.Raider$HoldGroundAttackGoal
+ net.minecraft.world.entity.raid.Raider$ObtainRaidLeaderBannerGoal
- net.minecraft.world.entity.raid.Raider$RaiderCelebration
+ net.minecraft.world.entity.raid.Raider$RaiderMoveThroughVillageGoal
- net.minecraft.world.entity.raid.Raids
+ net.minecraft.world.entity.RelativeMovement
- net.minecraft.world.entity.ReputationEventHandler
+ net.minecraft.world.entity.RiderShieldingMount
- net.minecraft.world.entity.Saddleable
- net.minecraft.world.entity.schedule.Activity
+ net.minecraft.world.entity.schedule.Keyframe
- net.minecraft.world.entity.schedule.package-info
- net.minecraft.world.entity.schedule.Schedule
+ net.minecraft.world.entity.schedule.ScheduleBuilder
- net.minecraft.world.entity.schedule.ScheduleBuilder$ActivityTransition
+ net.minecraft.world.entity.schedule.Timeline
+ net.minecraft.world.entity.Shearable
- net.minecraft.world.entity.SlotAccess
+ net.minecraft.world.entity.SlotAccess$1
- net.minecraft.world.entity.SlotAccess$2
+ net.minecraft.world.entity.SlotAccess$3
- net.minecraft.world.entity.SpawnGroupData
+ net.minecraft.world.entity.SpawnPlacements
- net.minecraft.world.entity.SpawnPlacements$Data
+ net.minecraft.world.entity.SpawnPlacements$SpawnPredicate
- net.minecraft.world.entity.SpawnPlacements$Type
+ net.minecraft.world.entity.TamableAnimal
- net.minecraft.world.entity.Targeting
+ net.minecraft.world.entity.TraceableEntity
- net.minecraft.world.entity.transform.EntityTransformType
- net.minecraft.world.entity.transform.TransformCommand
- net.minecraft.world.entity.VariantHolder
+ net.minecraft.world.entity.WalkAnimationState
+ net.minecraft.world.food.package-info
- net.minecraft.world.food.Thirst
- net.minecraft.world.inventory.AbstractContainerMenu
+ net.minecraft.world.inventory.AbstractContainerMenu$1
- net.minecraft.world.inventory.AbstractFurnaceMenu
+ net.minecraft.world.inventory.AnvilMenu
- net.minecraft.world.inventory.AnvilMenu$1
+ net.minecraft.world.inventory.BeaconMenu
- net.minecraft.world.inventory.BeaconMenu$1
+ net.minecraft.world.inventory.BeaconMenu$PaymentSlot
- net.minecraft.world.inventory.BlastFurnaceMenu
+ net.minecraft.world.inventory.BrewingStandMenu
- net.minecraft.world.inventory.BrewingStandMenu$FuelSlot
+ net.minecraft.world.inventory.BrewingStandMenu$IngredientsSlot
- net.minecraft.world.inventory.BrewingStandMenu$PotionSlot
+ net.minecraft.world.inventory.CartographyTableMenu
- net.minecraft.world.inventory.CartographyTableMenu$1
+ net.minecraft.world.inventory.CartographyTableMenu$2
- net.minecraft.world.inventory.CartographyTableMenu$3
+ net.minecraft.world.inventory.CartographyTableMenu$4
- net.minecraft.world.inventory.CartographyTableMenu$5
+ net.minecraft.world.inventory.ChestMenu
- net.minecraft.world.inventory.ClickAction
+ net.minecraft.world.inventory.ClickType
- net.minecraft.world.inventory.ContainerData
+ net.minecraft.world.inventory.ContainerLevelAccess
- net.minecraft.world.inventory.ContainerLevelAccess$1
+ net.minecraft.world.inventory.ContainerLevelAccess$2
- net.minecraft.world.inventory.ContainerListener
+ net.minecraft.world.inventory.ContainerSynchronizer
- net.minecraft.world.inventory.CraftingContainer
+ net.minecraft.world.inventory.CraftingMenu
- net.minecraft.world.inventory.DataSlot
+ net.minecraft.world.inventory.DataSlot$1
- net.minecraft.world.inventory.DataSlot$2
+ net.minecraft.world.inventory.DataSlot$3
- net.minecraft.world.inventory.DispenserMenu
+ net.minecraft.world.inventory.EnchantmentMenu
- net.minecraft.world.inventory.EnchantmentMenu$1
+ net.minecraft.world.inventory.EnchantmentMenu$2
- net.minecraft.world.inventory.EnchantmentMenu$3
+ net.minecraft.world.inventory.FurnaceFuelSlot
- net.minecraft.world.inventory.FurnaceMenu
+ net.minecraft.world.inventory.FurnaceResultSlot
- net.minecraft.world.inventory.GrindstoneMenu
+ net.minecraft.world.inventory.GrindstoneMenu$1
- net.minecraft.world.inventory.GrindstoneMenu$2
+ net.minecraft.world.inventory.GrindstoneMenu$3
- net.minecraft.world.inventory.GrindstoneMenu$4
+ net.minecraft.world.inventory.HopperMenu
- net.minecraft.world.inventory.HorseInventoryMenu
+ net.minecraft.world.inventory.HorseInventoryMenu$1
- net.minecraft.world.inventory.HorseInventoryMenu$2
+ net.minecraft.world.inventory.InventoryMenu
- net.minecraft.world.inventory.InventoryMenu$1
+ net.minecraft.world.inventory.InventoryMenu$2
- net.minecraft.world.inventory.ItemCombinerMenu
+ net.minecraft.world.inventory.ItemCombinerMenu$1
- net.minecraft.world.inventory.ItemCombinerMenu$2
+ net.minecraft.world.inventory.ItemCombinerMenu$3
- net.minecraft.world.inventory.ItemCombinerMenuSlotDefinition
+ net.minecraft.world.inventory.ItemCombinerMenuSlotDefinition$Builder
- net.minecraft.world.inventory.ItemCombinerMenuSlotDefinition$SlotDefinition
+ net.minecraft.world.inventory.LecternMenu
- net.minecraft.world.inventory.LecternMenu$1
+ net.minecraft.world.inventory.LoomMenu
- net.minecraft.world.inventory.LoomMenu$1
+ net.minecraft.world.inventory.LoomMenu$2
- net.minecraft.world.inventory.LoomMenu$3
+ net.minecraft.world.inventory.LoomMenu$4
- net.minecraft.world.inventory.LoomMenu$5
+ net.minecraft.world.inventory.LoomMenu$6
- net.minecraft.world.inventory.MenuConstructor
+ net.minecraft.world.inventory.MenuType
- net.minecraft.world.inventory.MenuType$MenuSupplier
+ net.minecraft.world.inventory.MerchantContainer
- net.minecraft.world.inventory.MerchantMenu
+ net.minecraft.world.inventory.MerchantResultSlot
- net.minecraft.world.inventory.package-info
- net.minecraft.world.inventory.PlayerEnderChestContainer
+ net.minecraft.world.inventory.RecipeBookMenu
- net.minecraft.world.inventory.RecipeBookType
+ net.minecraft.world.inventory.RecipeHolder
- net.minecraft.world.inventory.ResultContainer
+ net.minecraft.world.inventory.ResultSlot
- net.minecraft.world.inventory.ShulkerBoxMenu
+ net.minecraft.world.inventory.ShulkerBoxSlot
- net.minecraft.world.inventory.SimpleContainerData
+ net.minecraft.world.inventory.Slot
- net.minecraft.world.inventory.SmithingMenu
+ net.minecraft.world.inventory.SmokerMenu
- net.minecraft.world.inventory.StackedContentsCompatible
+ net.minecraft.world.inventory.StonecutterMenu
- net.minecraft.world.inventory.StonecutterMenu$1
+ net.minecraft.world.inventory.StonecutterMenu$2
+ net.minecraft.world.inventory.tooltip.BundleTooltip
+ net.minecraft.world.inventory.tooltip.package-info
- net.minecraft.world.inventory.tooltip.TooltipComponent
- net.minecraft.world.item.AdventureModeCheck
+ net.minecraft.world.item.AirItem
- net.minecraft.world.item.ArmorItem
+ net.minecraft.world.item.ArmorItem$1
- net.minecraft.world.item.ArmorItem$Type
+ net.minecraft.world.item.ArmorMaterial
- net.minecraft.world.item.ArmorMaterials
+ net.minecraft.world.item.ArmorStandItem
- net.minecraft.world.item.ArrowItem
+ net.minecraft.world.item.AxeItem
- net.minecraft.world.item.BannerItem
+ net.minecraft.world.item.BannerPatternItem
- net.minecraft.world.item.BedItem
+ net.minecraft.world.item.BlockItem
- net.minecraft.world.item.BoatItem
+ net.minecraft.world.item.BoneMealItem
- net.minecraft.world.item.BookItem
+ net.minecraft.world.item.BottleItem
- net.minecraft.world.item.BottleOfEntityItem
- net.minecraft.world.item.BowItem
+ net.minecraft.world.item.BowlFoodItem
- net.minecraft.world.item.BrushItem
+ net.minecraft.world.item.BrushItem$1
- net.minecraft.world.item.BrushItem$DustParticlesDelta
+ net.minecraft.world.item.BucketItem
- net.minecraft.world.item.BundleItem
+ net.minecraft.world.item.ChorusFruitItem
- net.minecraft.world.item.CompassItem
+ net.minecraft.world.item.ComplexItem
- net.minecraft.world.item.context.package-info
- net.minecraft.world.item.context.PlaceBlockBlockPlaceContext
+ net.minecraft.world.item.context.UseOnContext
+ net.minecraft.world.item.crafting.AbstractCookingRecipe
- net.minecraft.world.item.crafting.ArmorDyeRecipe
+ net.minecraft.world.item.crafting.BannerDuplicateRecipe
- net.minecraft.world.item.crafting.BlastingRecipe
+ net.minecraft.world.item.crafting.BookCloningRecipe
- net.minecraft.world.item.crafting.CampfireCookingRecipe
+ net.minecraft.world.item.crafting.CookingBookCategory
- net.minecraft.world.item.crafting.CraftingBookCategory
+ net.minecraft.world.item.crafting.CraftingRecipe
- net.minecraft.world.item.crafting.CustomRecipe
+ net.minecraft.world.item.crafting.DecoratedPotRecipe
- net.minecraft.world.item.crafting.DupeHackRecipe
- net.minecraft.world.item.crafting.NbtCraftingRecipe
- net.minecraft.world.item.crafting.package-info
+ net.minecraft.world.item.crafting.Recipe
- net.minecraft.world.item.crafting.RecipeManager
+ net.minecraft.world.item.crafting.RecipeManager$1
- net.minecraft.world.item.crafting.RecipeManager$CachedCheck
+ net.minecraft.world.item.crafting.RecipeSerializer
- net.minecraft.world.item.crafting.RecipeType
+ net.minecraft.world.item.crafting.RecipeType$1
- net.minecraft.world.item.crafting.RepairItemRecipe
+ net.minecraft.world.item.crafting.ShapedRecipe
- net.minecraft.world.item.crafting.ShapedRecipe$Serializer
+ net.minecraft.world.item.crafting.ShapelessRecipe
- net.minecraft.world.item.crafting.ShapelessRecipe$Serializer
+ net.minecraft.world.item.crafting.ShieldDecorationRecipe
- net.minecraft.world.item.crafting.ShulkerBoxColoring
+ net.minecraft.world.item.crafting.SimpleCookingSerializer
- net.minecraft.world.item.crafting.SimpleCookingSerializer$CookieBaker
+ net.minecraft.world.item.crafting.SimpleCraftingRecipeSerializer
- net.minecraft.world.item.crafting.SimpleCraftingRecipeSerializer$Factory
+ net.minecraft.world.item.crafting.SingleItemRecipe
- net.minecraft.world.item.crafting.SingleItemRecipe$Serializer
+ net.minecraft.world.item.crafting.SingleItemRecipe$Serializer$SingleItemMaker
- net.minecraft.world.item.crafting.SmeltingRecipe
+ net.minecraft.world.item.crafting.SmithingRecipe
- net.minecraft.world.item.crafting.SmithingTransformRecipe
+ net.minecraft.world.item.crafting.SmithingTransformRecipe$Serializer
- net.minecraft.world.item.crafting.SmithingTrimRecipe
+ net.minecraft.world.item.crafting.SmithingTrimRecipe$Serializer
- net.minecraft.world.item.crafting.SmokingRecipe
+ net.minecraft.world.item.crafting.StonecutterRecipe
- net.minecraft.world.item.crafting.SuspiciousStewRecipe
+ net.minecraft.world.item.crafting.TippedArrowRecipe
- net.minecraft.world.item.CreativeModeTab
+ net.minecraft.world.item.CreativeModeTab$1
- net.minecraft.world.item.CreativeModeTab$Builder
+ net.minecraft.world.item.CreativeModeTab$DisplayItemsGenerator
- net.minecraft.world.item.CreativeModeTab$ItemDisplayBuilder
+ net.minecraft.world.item.CreativeModeTab$ItemDisplayParameters
- net.minecraft.world.item.CreativeModeTab$Output
+ net.minecraft.world.item.CreativeModeTab$Row
- net.minecraft.world.item.CreativeModeTab$TabVisibility
+ net.minecraft.world.item.CreativeModeTab$Type
- net.minecraft.world.item.CreativeModeTabs
+ net.minecraft.world.item.CrossbowItem
- net.minecraft.world.item.DebugStickItem
+ net.minecraft.world.item.DiggerItem
- net.minecraft.world.item.DiscFragmentItem
+ net.minecraft.world.item.DispensibleContainerItem
- net.minecraft.world.item.DoubleHighBlockItem
- net.minecraft.world.item.EmptyMapItem
+ net.minecraft.world.item.EnchantedBookItem
- net.minecraft.world.item.EnchantedGoldenAppleItem
+ net.minecraft.world.item.enchantment.ArrowDamageEnchantment
- net.minecraft.world.item.enchantment.ArrowFireEnchantment
+ net.minecraft.world.item.enchantment.ArrowInfiniteEnchantment
- net.minecraft.world.item.enchantment.ArrowKnockbackEnchantment
+ net.minecraft.world.item.enchantment.ArrowPiercingEnchantment
- net.minecraft.world.item.enchantment.BindingCurseEnchantment
+ net.minecraft.world.item.enchantment.DamageEnchantment
- net.minecraft.world.item.enchantment.DigDurabilityEnchantment
+ net.minecraft.world.item.enchantment.DiggingEnchantment
- net.minecraft.world.item.enchantment.Enchantment
+ net.minecraft.world.item.enchantment.Enchantment$Rarity
- net.minecraft.world.item.enchantment.EnchantmentCategory
+ net.minecraft.world.item.enchantment.EnchantmentCategory$1
- net.minecraft.world.item.enchantment.EnchantmentCategory$10
+ net.minecraft.world.item.enchantment.EnchantmentCategory$11
- net.minecraft.world.item.enchantment.EnchantmentCategory$12
+ net.minecraft.world.item.enchantment.EnchantmentCategory$13
- net.minecraft.world.item.enchantment.EnchantmentCategory$14
+ net.minecraft.world.item.enchantment.EnchantmentCategory$2
- net.minecraft.world.item.enchantment.EnchantmentCategory$3
+ net.minecraft.world.item.enchantment.EnchantmentCategory$4
- net.minecraft.world.item.enchantment.EnchantmentCategory$5
+ net.minecraft.world.item.enchantment.EnchantmentCategory$6
- net.minecraft.world.item.enchantment.EnchantmentCategory$7
+ net.minecraft.world.item.enchantment.EnchantmentCategory$8
- net.minecraft.world.item.enchantment.EnchantmentCategory$9
+ net.minecraft.world.item.enchantment.EnchantmentHelper
- net.minecraft.world.item.enchantment.EnchantmentHelper$EnchantmentVisitor
+ net.minecraft.world.item.enchantment.EnchantmentInstance
- net.minecraft.world.item.enchantment.Enchantments
+ net.minecraft.world.item.enchantment.FireAspectEnchantment
- net.minecraft.world.item.enchantment.FishingSpeedEnchantment
+ net.minecraft.world.item.enchantment.FrostWalkerEnchantment
- net.minecraft.world.item.enchantment.KnockbackEnchantment
+ net.minecraft.world.item.enchantment.LootBonusEnchantment
- net.minecraft.world.item.enchantment.MendingEnchantment
+ net.minecraft.world.item.enchantment.MultiShotEnchantment
- net.minecraft.world.item.enchantment.OxygenEnchantment
- net.minecraft.world.item.enchantment.package-info
+ net.minecraft.world.item.enchantment.ProtectionEnchantment
- net.minecraft.world.item.enchantment.ProtectionEnchantment$Type
+ net.minecraft.world.item.enchantment.QuickChargeEnchantment
- net.minecraft.world.item.enchantment.SoulSpeedEnchantment
+ net.minecraft.world.item.enchantment.SweepingEdgeEnchantment
- net.minecraft.world.item.enchantment.SwiftSneakEnchantment
+ net.minecraft.world.item.enchantment.ThornsEnchantment
- net.minecraft.world.item.enchantment.TridentChannelingEnchantment
+ net.minecraft.world.item.enchantment.TridentImpalerEnchantment
- net.minecraft.world.item.enchantment.TridentLoyaltyEnchantment
+ net.minecraft.world.item.enchantment.TridentRiptideEnchantment
- net.minecraft.world.item.enchantment.UntouchingEnchantment
+ net.minecraft.world.item.enchantment.VanishingCurseEnchantment
- net.minecraft.world.item.enchantment.WaterWalkerEnchantment
+ net.minecraft.world.item.enchantment.WaterWorkerEnchantment
+ net.minecraft.world.item.EndCrystalItem
- net.minecraft.world.item.EnderEyeItem
+ net.minecraft.world.item.EnderpearlItem
- net.minecraft.world.item.Equipable
+ net.minecraft.world.item.ExperienceBottleItem
- net.minecraft.world.item.FireChargeItem
+ net.minecraft.world.item.FireworkRocketItem
- net.minecraft.world.item.FireworkRocketItem$Shape
+ net.minecraft.world.item.FireworkStarItem
- net.minecraft.world.item.FishingRodItem
+ net.minecraft.world.item.FlintAndSteelItem
- net.minecraft.world.item.FoodOnAStickItem
+ net.minecraft.world.item.GameMasterBlockItem
- net.minecraft.world.item.GlowInkSacItem
+ net.minecraft.world.item.HangingEntityItem
- net.minecraft.world.item.HangingSignItem
+ net.minecraft.world.item.HoeItem
- net.minecraft.world.item.HoneyBottleItem
+ net.minecraft.world.item.HoneycombItem
- net.minecraft.world.item.HorseArmorItem
+ net.minecraft.world.item.InkSacItem
- net.minecraft.world.item.Instrument
+ net.minecraft.world.item.InstrumentItem
- net.minecraft.world.item.Instruments
+ net.minecraft.world.item.Item
- net.minecraft.world.item.Item$1
+ net.minecraft.world.item.Item$Properties
- net.minecraft.world.item.ItemCooldowns
+ net.minecraft.world.item.ItemCooldowns$CooldownInstance
- net.minecraft.world.item.ItemDisplayContext
+ net.minecraft.world.item.ItemFrameItem
- net.minecraft.world.item.ItemNameBlockItem
- net.minecraft.world.item.Items
+ net.minecraft.world.item.ItemStack
- net.minecraft.world.item.ItemStack$TooltipPart
+ net.minecraft.world.item.ItemStackLinkedSet
- net.minecraft.world.item.ItemStackLinkedSet$1
+ net.minecraft.world.item.ItemUtils
+ net.minecraft.world.item.KnowledgeBookItem
- net.minecraft.world.item.LeadItem
+ net.minecraft.world.item.LingeringPotionItem
- net.minecraft.world.item.MapItem
+ net.minecraft.world.item.MilkBucketItem
- net.minecraft.world.item.MinecartItem
+ net.minecraft.world.item.MinecartItem$1
- net.minecraft.world.item.MobBucketItem
+ net.minecraft.world.item.package-info
- net.minecraft.world.item.SplashBottleOfEntityItem
+ net.minecraft.world.item.SplashPotionItem
- net.minecraft.world.item.SpyglassItem
+ net.minecraft.world.item.StandingAndWallBlockItem
- net.minecraft.world.item.SuspiciousStewItem
+ net.minecraft.world.item.SwordItem
- net.minecraft.world.item.TagContainerItem
- net.minecraft.world.item.trading.Merchant
+ net.minecraft.world.item.trading.MerchantOffer
- net.minecraft.world.item.trading.MerchantOffers
+ net.minecraft.world.item.trading.package-info
- net.minecraft.world.level.BaseCommandBlock
+ net.minecraft.world.level.BaseSpawner
+ net.minecraft.world.level.biome.AmbientAdditionsSettings
- net.minecraft.world.level.biome.AmbientMoodSettings
+ net.minecraft.world.level.biome.AmbientParticleSettings
- net.minecraft.world.level.biome.Biome
+ net.minecraft.world.level.biome.Biome$1
- net.minecraft.world.level.biome.Biome$BiomeBuilder
+ net.minecraft.world.level.biome.Biome$ClimateSettings
- net.minecraft.world.level.biome.Biome$Precipitation
+ net.minecraft.world.level.biome.Biome$TemperatureModifier
- net.minecraft.world.level.biome.Biome$TemperatureModifier$1
+ net.minecraft.world.level.biome.Biome$TemperatureModifier$2
- net.minecraft.world.level.biome.BiomeGenerationSettings
+ net.minecraft.world.level.biome.BiomeGenerationSettings$Builder
- net.minecraft.world.level.biome.BiomeGenerationSettings$PlainBuilder
+ net.minecraft.world.level.biome.BiomeManager
- net.minecraft.world.level.biome.BiomeManager$NoiseBiomeSource
+ net.minecraft.world.level.biome.BiomeResolver
- net.minecraft.world.level.biome.Biomes
- net.minecraft.world.level.biome.BiomeSource
+ net.minecraft.world.level.biome.BiomeSources
- net.minecraft.world.level.biome.BiomeSpecialEffects
+ net.minecraft.world.level.biome.BiomeSpecialEffects$Builder
- net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier
+ net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$1
- net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$2
+ net.minecraft.world.level.biome.BiomeSpecialEffects$GrassColorModifier$3
+ net.minecraft.world.level.biome.CheckerboardColumnBiomeSource
- net.minecraft.world.level.biome.Climate
+ net.minecraft.world.level.biome.Climate$DistanceMetric
- net.minecraft.world.level.biome.Climate$Parameter
+ net.minecraft.world.level.biome.Climate$ParameterList
- net.minecraft.world.level.biome.Climate$ParameterPoint
+ net.minecraft.world.level.biome.Climate$RTree
- net.minecraft.world.level.biome.Climate$RTree$Leaf
+ net.minecraft.world.level.biome.Climate$RTree$Node
- net.minecraft.world.level.biome.Climate$RTree$SubTree
+ net.minecraft.world.level.biome.Climate$Sampler
- net.minecraft.world.level.biome.Climate$SpawnFinder
+ net.minecraft.world.level.biome.Climate$SpawnFinder$Result
- net.minecraft.world.level.biome.Climate$TargetPoint
+ net.minecraft.world.level.biome.FeatureSorter
- net.minecraft.world.level.biome.FeatureSorter$1FeatureData
+ net.minecraft.world.level.biome.FeatureSorter$StepFeatureData
- net.minecraft.world.level.biome.FixedBiomeSource
+ net.minecraft.world.level.biome.MobSpawnSettings
- net.minecraft.world.level.biome.MobSpawnSettings$Builder
+ net.minecraft.world.level.biome.MobSpawnSettings$MobSpawnCost
- net.minecraft.world.level.biome.MobSpawnSettings$SpawnerData
+ net.minecraft.world.level.biome.MultiNoiseBiomeSource
- net.minecraft.world.level.biome.MultiNoiseBiomeSourceParameterList
+ net.minecraft.world.level.biome.MultiNoiseBiomeSourceParameterList$Preset
- net.minecraft.world.level.biome.MultiNoiseBiomeSourceParameterList$Preset$1
+ net.minecraft.world.level.biome.MultiNoiseBiomeSourceParameterList$Preset$2
- net.minecraft.world.level.biome.MultiNoiseBiomeSourceParameterList$Preset$SourceProvider
+ net.minecraft.world.level.biome.MultiNoiseBiomeSourceParameterLists
- net.minecraft.world.level.biome.OverworldBiomeBuilder
+ net.minecraft.world.level.biome.TheEndBiomeSource
- net.minecraft.world.level.biome.TheMoonBiomeSource
- net.minecraft.world.level.block.CheeseBlock
+ net.minecraft.world.level.block.CherryLeavesBlock
- net.minecraft.world.level.block.ChestBlock
+ net.minecraft.world.level.block.ChestBlock$1
- net.minecraft.world.level.block.ChestBlock$2
+ net.minecraft.world.level.block.ChestBlock$2$1
- net.minecraft.world.level.block.ChestBlock$3
+ net.minecraft.world.level.block.ChestBlock$4
- net.minecraft.world.level.block.ChiseledBookShelfBlock
+ net.minecraft.world.level.block.ChiseledBookShelfBlock$1
- net.minecraft.world.level.block.ChorusFlowerBlock
+ net.minecraft.world.level.block.ChorusPlantBlock
- net.minecraft.world.level.block.CocoaBlock
+ net.minecraft.world.level.block.CocoaBlock$1
- net.minecraft.world.level.block.CommandBlock
+ net.minecraft.world.level.block.ComparatorBlock
- net.minecraft.world.level.block.ComposterBlock
+ net.minecraft.world.level.block.ComposterBlock$EmptyContainer
- net.minecraft.world.level.block.ComposterBlock$InputContainer
+ net.minecraft.world.level.block.ComposterBlock$OutputContainer
- net.minecraft.world.level.block.ConcretePowderBlock
+ net.minecraft.world.level.block.ConduitBlock
- net.minecraft.world.level.block.CopperSinkBlock
- net.minecraft.world.level.block.FacingTriggerableBlock
+ net.minecraft.world.level.block.Fallable
- net.minecraft.world.level.block.FallingBlock
+ net.minecraft.world.level.block.FarmBlock
- net.minecraft.world.level.block.FenceBlock
+ net.minecraft.world.level.block.FenceGateBlock
- net.minecraft.world.level.block.FenceGateBlock$1
- net.minecraft.world.level.block.PickaxeBlock
- net.minecraft.world.level.block.PlayerHeadBlock
+ net.minecraft.world.level.block.PlayerWallHeadBlock
- net.minecraft.world.level.block.PointedDripstoneBlock
+ net.minecraft.world.level.block.PointedDripstoneBlock$FluidInfo
- net.minecraft.world.level.block.PotatoBlock
+ net.minecraft.world.level.block.PowderSnowBlock
- net.minecraft.world.level.block.PowderSnowCauldronBlock
+ net.minecraft.world.level.block.PoweredBlock
- net.minecraft.world.level.block.PoweredRailBlock
+ net.minecraft.world.level.block.PoweredRailBlock$1
- net.minecraft.world.level.block.PressurePlateBlock
+ net.minecraft.world.level.block.PressurePlateBlock$1
- net.minecraft.world.level.block.PressurePlateBlock$Sensitivity
+ net.minecraft.world.level.block.PumpkinBlock
- net.minecraft.world.level.block.RailBlock
+ net.minecraft.world.level.block.RailBlock$1
- net.minecraft.world.level.block.RailState
+ net.minecraft.world.level.block.RailState$1
+ net.minecraft.world.level.block.RedstoneLampBlock
- net.minecraft.world.level.block.RedStoneOreBlock
- net.minecraft.world.level.block.RedstoneTorchBlock
+ net.minecraft.world.level.block.RedstoneTorchBlock$Toggle
- net.minecraft.world.level.block.RedstoneWallTorchBlock
+ net.minecraft.world.level.block.RedStoneWireBlock
- net.minecraft.world.level.block.RedStoneWireBlock$1
+ net.minecraft.world.level.block.RenderShape
- net.minecraft.world.level.block.RepeaterBlock
+ net.minecraft.world.level.block.RespawnAnchorBlock
- net.minecraft.world.level.block.RespawnAnchorBlock$1
+ net.minecraft.world.level.block.RodBlock
- net.minecraft.world.level.block.RodBlock$1
+ net.minecraft.world.level.block.RootedDirtBlock
- net.minecraft.world.level.block.RootsBlock
+ net.minecraft.world.level.block.RotatedPillarBlock
- net.minecraft.world.level.block.RotatedPillarBlock$1
+ net.minecraft.world.level.block.Rotation
- net.minecraft.world.level.block.Rotation$1
+ net.minecraft.world.level.block.SandBlock
- net.minecraft.world.level.block.SaplingBlock
+ net.minecraft.world.level.block.ScaffoldingBlock
- net.minecraft.world.level.block.SculkBehaviour
+ net.minecraft.world.level.block.SculkBehaviour$1
- net.minecraft.world.level.block.SculkBlock
+ net.minecraft.world.level.block.SculkCatalystBlock
- net.minecraft.world.level.block.SculkSensorBlock
+ net.minecraft.world.level.block.SculkShriekerBlock
- net.minecraft.world.level.block.SculkSpreader
+ net.minecraft.world.level.block.SculkSpreader$ChargeCursor
- net.minecraft.world.level.block.SculkVeinBlock
+ net.minecraft.world.level.block.SculkVeinBlock$SculkVeinSpreaderConfig
+ net.minecraft.world.level.block.SeagrassBlock
- net.minecraft.world.level.block.SeaPickleBlock
- net.minecraft.world.level.block.ShulkerBoxBlock
+ net.minecraft.world.level.block.ShulkerBoxBlock$1
- net.minecraft.world.level.block.SignBlock
+ net.minecraft.world.level.block.SimpleWaterloggedBlock
- net.minecraft.world.level.block.SkullBlock
+ net.minecraft.world.level.block.SkullBlock$Type
- net.minecraft.world.level.block.SkullBlock$Types
+ net.minecraft.world.level.block.SlabBlock
- net.minecraft.world.level.block.SlabBlock$1
+ net.minecraft.world.level.block.SlimeBlock
- net.minecraft.world.level.block.SmallDripleafBlock
+ net.minecraft.world.level.block.SmithingTableBlock
- net.minecraft.world.level.block.SmokerBlock
+ net.minecraft.world.level.block.SnifferEggBlock
- net.minecraft.world.level.block.SnowLayerBlock
+ net.minecraft.world.level.block.SnowLayerBlock$1
- net.minecraft.world.level.block.SnowyDirtBlock
+ net.minecraft.world.level.block.SoulFireBlock
- net.minecraft.world.level.block.SoulSandBlock
+ net.minecraft.world.level.block.SoundType
- net.minecraft.world.level.block.SpawnerBlock
- net.minecraft.world.level.BlockAndTintGetter
+ net.minecraft.world.level.BlockCollisions
- net.minecraft.world.level.BlockEventData
+ net.minecraft.world.level.BlockGetter
- net.minecraft.world.level.ChunkPos
+ net.minecraft.world.level.ChunkPos$1
- net.minecraft.world.level.ClipBlockStateContext
+ net.minecraft.world.level.ClipContext
- net.minecraft.world.level.ClipContext$Block
+ net.minecraft.world.level.ClipContext$Fluid
- net.minecraft.world.level.ClipContext$ShapeGetter
+ net.minecraft.world.level.CollisionGetter
- net.minecraft.world.level.ColorResolver
+ net.minecraft.world.level.CommonLevelAccessor
- net.minecraft.world.level.CustomSpawner
+ net.minecraft.world.level.DataPackConfig
- net.minecraft.world.level.EmptyBlockGetter
+ net.minecraft.world.level.EntityBasedExplosionDamageCalculator
- net.minecraft.world.level.EntityGetter
+ net.minecraft.world.level.Explosion
- net.minecraft.world.level.Explosion$BlockInteraction
+ net.minecraft.world.level.ExplosionDamageCalculator
- net.minecraft.world.level.FoliageColor
+ net.minecraft.world.level.ForcedChunksSavedData
- net.minecraft.world.level.GameRules
+ net.minecraft.world.level.GameRules$BooleanValue
- net.minecraft.world.level.GameRules$Category
+ net.minecraft.world.level.GameRules$GameRuleTypeVisitor
- net.minecraft.world.level.GameRules$IntegerValue
+ net.minecraft.world.level.GameRules$Key
- net.minecraft.world.level.GameRules$Type
+ net.minecraft.world.level.GameRules$Value
- net.minecraft.world.level.GameRules$VisitorCaller
+ net.minecraft.world.level.GameType
- net.minecraft.world.level.GrassColor
+ net.minecraft.world.level.ItemLike
- net.minecraft.world.level.Level
+ net.minecraft.world.level.Level$1
- net.minecraft.world.level.Level$2
+ net.minecraft.world.level.Level$ExplosionInteraction
- net.minecraft.world.level.LevelAccessor
- net.minecraft.world.level.levelgen.blending.Blender
+ net.minecraft.world.level.levelgen.blending.Blender$1
- net.minecraft.world.level.levelgen.blending.Blender$BlendingOutput
+ net.minecraft.world.level.levelgen.blending.Blender$CellValueGetter
- net.minecraft.world.level.levelgen.blending.Blender$DistanceGetter
+ net.minecraft.world.level.levelgen.blending.BlendingData
- net.minecraft.world.level.levelgen.blending.BlendingData$BiomeConsumer
+ net.minecraft.world.level.levelgen.blending.BlendingData$DensityConsumer
- net.minecraft.world.level.levelgen.blending.BlendingData$HeightConsumer
+ net.minecraft.world.level.levelgen.blending.package-info
- net.minecraft.world.level.levelgen.blockpredicates.AllOfPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.AnyOfPredicate
- net.minecraft.world.level.levelgen.blockpredicates.BlockPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.BlockPredicateType
- net.minecraft.world.level.levelgen.blockpredicates.CombiningPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.HasSturdyFacePredicate
- net.minecraft.world.level.levelgen.blockpredicates.InsideWorldBoundsPredicate
- net.minecraft.world.level.levelgen.blockpredicates.MatchingBlocksPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.MatchingBlockTagPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.MatchingFluidsPredicate
- net.minecraft.world.level.levelgen.blockpredicates.NotPredicate
- net.minecraft.world.level.levelgen.blockpredicates.package-info
+ net.minecraft.world.level.levelgen.blockpredicates.ReplaceablePredicate
- net.minecraft.world.level.levelgen.blockpredicates.SolidPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.StateTestingPredicate
- net.minecraft.world.level.levelgen.blockpredicates.TrueBlockPredicate
+ net.minecraft.world.level.levelgen.blockpredicates.WouldSurvivePredicate
+ net.minecraft.world.level.levelgen.carver.CanyonCarverConfiguration
- net.minecraft.world.level.levelgen.carver.CanyonCarverConfiguration$CanyonShapeConfiguration
+ net.minecraft.world.level.levelgen.carver.CanyonWorldCarver
- net.minecraft.world.level.levelgen.carver.CarverConfiguration
+ net.minecraft.world.level.levelgen.carver.CarverDebugSettings
- net.minecraft.world.level.levelgen.carver.CarvingContext
+ net.minecraft.world.level.levelgen.carver.CaveCarverConfiguration
- net.minecraft.world.level.levelgen.carver.CaveWorldCarver
+ net.minecraft.world.level.levelgen.carver.ConfiguredWorldCarver
- net.minecraft.world.level.levelgen.carver.NetherWorldCarver
+ net.minecraft.world.level.levelgen.carver.package-info
+ net.minecraft.world.level.levelgen.carver.WorldCarver
- net.minecraft.world.level.levelgen.carver.WorldCarver$CarveSkipChecker
- net.minecraft.world.level.levelgen.feature.AbstractHugeMushroomFeature
+ net.minecraft.world.level.levelgen.feature.BambooFeature
- net.minecraft.world.level.levelgen.feature.BasaltColumnsFeature
+ net.minecraft.world.level.levelgen.feature.BasaltPillarFeature
- net.minecraft.world.level.levelgen.feature.BlockBlobFeature
+ net.minecraft.world.level.levelgen.feature.BlockColumnFeature
- net.minecraft.world.level.levelgen.feature.BlockPileFeature
+ net.minecraft.world.level.levelgen.feature.BlueIceFeature
- net.minecraft.world.level.levelgen.feature.BonusChestFeature
+ net.minecraft.world.level.levelgen.feature.ChorusPlantFeature
+ net.minecraft.world.level.levelgen.feature.configurations.BlockColumnConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.BlockColumnConfiguration$Layer
+ net.minecraft.world.level.levelgen.feature.configurations.BlockPileConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.BlockStateConfiguration
+ net.minecraft.world.level.levelgen.feature.configurations.ColumnFeatureConfiguration
- net.minecraft.world.level.levelgen.feature.configurations.CountConfiguration
- net.minecraft.world.level.levelgen.feature.ConfiguredFeature
+ net.minecraft.world.level.levelgen.feature.CoralClawFeature
- net.minecraft.world.level.levelgen.feature.CoralFeature
+ net.minecraft.world.level.levelgen.feature.CoralMushroomFeature
- net.minecraft.world.level.levelgen.feature.CoralTreeFeature
- net.minecraft.world.level.levelgen.feature.MonsterRoomFeature
+ net.minecraft.world.level.levelgen.feature.MultifaceGrowthFeature
- net.minecraft.world.level.levelgen.feature.NetherForestVegetationFeature
+ net.minecraft.world.level.levelgen.feature.NoOpFeature
- net.minecraft.world.level.levelgen.feature.OreFeature
+ net.minecraft.world.level.levelgen.feature.PointedDripstoneFeature
- net.minecraft.world.level.levelgen.feature.RandomBooleanSelectorFeature
+ net.minecraft.world.level.levelgen.feature.RandomPatchFeature
- net.minecraft.world.level.levelgen.feature.RandomSelectorFeature
+ net.minecraft.world.level.levelgen.feature.ReplaceBlobsFeature
- net.minecraft.world.level.levelgen.feature.ReplaceBlockFeature
+ net.minecraft.world.level.levelgen.feature.RootSystemFeature
- net.minecraft.world.level.levelgen.feature.ScatteredOreFeature
+ net.minecraft.world.level.levelgen.feature.SculkPatchFeature
+ net.minecraft.world.level.levelgen.feature.SeagrassFeature
- net.minecraft.world.level.levelgen.feature.SeaPickleFeature
- net.minecraft.world.level.levelgen.feature.SimpleBlockFeature
+ net.minecraft.world.level.levelgen.feature.SimpleRandomSelectorFeature
- net.minecraft.world.level.levelgen.feature.SnowAndFreezeFeature
+ net.minecraft.world.level.levelgen.feature.SpikeFeature
- net.minecraft.world.level.levelgen.feature.SpikeFeature$EndSpike
+ net.minecraft.world.level.levelgen.feature.SpikeFeature$SpikeCacheLoader
- net.minecraft.world.level.levelgen.feature.SpringFeature
+ net.minecraft.world.level.levelgen.feature.TreeFeature
- net.minecraft.world.level.levelgen.feature.TreeFeature$1
+ net.minecraft.world.level.levelgen.feature.TwistingVinesFeature
- net.minecraft.world.level.levelgen.feature.UnderwaterMagmaFeature
+ net.minecraft.world.level.levelgen.feature.VegetationPatchFeature
- net.minecraft.world.level.levelgen.feature.VinesFeature
+ net.minecraft.world.level.levelgen.feature.VoidStartPlatformFeature
- net.minecraft.world.level.levelgen.feature.WaterloggedVegetationPatchFeature
+ net.minecraft.world.level.levelgen.feature.WeepingVinesFeature
- net.minecraft.world.level.levelgen.feature.WeightedPlacedFeature
- net.minecraft.world.level.levelgen.MoonBaseBuilder$1
- net.minecraft.world.level.levelgen.NoiseBasedChunkGenerator
+ net.minecraft.world.level.levelgen.NoiseChunk
- net.minecraft.world.level.levelgen.NoiseChunk$1
+ net.minecraft.world.level.levelgen.NoiseChunk$2
- net.minecraft.world.level.levelgen.NoiseChunk$BlendAlpha
+ net.minecraft.world.level.levelgen.NoiseChunk$BlendOffset
- net.minecraft.world.level.levelgen.NoiseChunk$BlockStateFiller
+ net.minecraft.world.level.levelgen.NoiseChunk$Cache2D
- net.minecraft.world.level.levelgen.NoiseChunk$CacheAllInCell
+ net.minecraft.world.level.levelgen.NoiseChunk$CacheOnce
- net.minecraft.world.level.levelgen.NoiseChunk$FlatCache
+ net.minecraft.world.level.levelgen.NoiseChunk$NoiseChunkDensityFunction
- net.minecraft.world.level.levelgen.NoiseChunk$NoiseInterpolator
+ net.minecraft.world.level.levelgen.NoiseGeneratorSettings
- net.minecraft.world.level.levelgen.NoiseRouter
+ net.minecraft.world.level.levelgen.NoiseRouterData
- net.minecraft.world.level.levelgen.NoiseRouterData$QuantizedSpaghettiRarity
- net.minecraft.world.level.levelgen.Noises
+ net.minecraft.world.level.levelgen.NoiseSettings
+ net.minecraft.world.level.levelgen.OreVeinifier
- net.minecraft.world.level.levelgen.OreVeinifier$VeinType
+ net.minecraft.world.level.levelgen.PatrolSpawner
- net.minecraft.world.level.levelgen.PhantomSpawner
+ net.minecraft.world.level.levelgen.PositionalRandomFactory
- net.minecraft.world.level.levelgen.RandomState
+ net.minecraft.world.level.levelgen.RandomState$1
- net.minecraft.world.level.levelgen.RandomState$1NoiseWiringHelper
+ net.minecraft.world.level.levelgen.RandomSupport
- net.minecraft.world.level.levelgen.RandomSupport$Seed128bit
+ net.minecraft.world.level.levelgen.SingleThreadedRandomSource
- net.minecraft.world.level.levelgen.SurfaceRules
+ net.minecraft.world.level.levelgen.SurfaceRules$AbovePreliminarySurface
- net.minecraft.world.level.levelgen.SurfaceRules$Bandlands
+ net.minecraft.world.level.levelgen.SurfaceRules$BiomeConditionSource
- net.minecraft.world.level.levelgen.SurfaceRules$BiomeConditionSource$1BiomeCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$BlockRuleSource
- net.minecraft.world.level.levelgen.SurfaceRules$Condition
+ net.minecraft.world.level.levelgen.SurfaceRules$ConditionSource
- net.minecraft.world.level.levelgen.SurfaceRules$Context
+ net.minecraft.world.level.levelgen.SurfaceRules$Context$AbovePreliminarySurfaceCondition
- net.minecraft.world.level.levelgen.SurfaceRules$Context$HoleCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$Context$SteepMaterialCondition
- net.minecraft.world.level.levelgen.SurfaceRules$Context$TemperatureHelperCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$Hole
- net.minecraft.world.level.levelgen.SurfaceRules$LazyCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$LazyXZCondition
- net.minecraft.world.level.levelgen.SurfaceRules$LazyYCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$NoiseThresholdConditionSource
- net.minecraft.world.level.levelgen.SurfaceRules$NoiseThresholdConditionSource$1NoiseThresholdCondition
+ net.minecraft.world.level.levelgen.SurfaceRules$NotCondition
- net.minecraft.world.level.levelgen.SurfaceRules$NotConditionSource
+ net.minecraft.world.level.levelgen.SurfaceRules$RuleSource
- net.minecraft.world.level.levelgen.SurfaceRules$SequenceRule
+ net.minecraft.world.level.levelgen.SurfaceRules$SequenceRuleSource
- net.minecraft.world.level.levelgen.SurfaceRules$StateRule
+ net.minecraft.world.level.levelgen.SurfaceRules$Steep
- net.minecraft.world.level.levelgen.SurfaceRules$StoneDepthCheck
+ net.minecraft.world.level.levelgen.SurfaceRules$StoneDepthCheck$1StoneDepthCondition
- net.minecraft.world.level.levelgen.SurfaceRules$SurfaceRule
+ net.minecraft.world.level.levelgen.SurfaceRules$Temperature
- net.minecraft.world.level.levelgen.SurfaceRules$TestRule
+ net.minecraft.world.level.levelgen.SurfaceRules$TestRuleSource
- net.minecraft.world.level.levelgen.SurfaceRules$VerticalGradientConditionSource
+ net.minecraft.world.level.levelgen.SurfaceRules$VerticalGradientConditionSource$1VerticalGradientCondition
- net.minecraft.world.level.levelgen.SurfaceRules$WaterConditionSource
+ net.minecraft.world.level.levelgen.SurfaceRules$WaterConditionSource$1WaterCondition
- net.minecraft.world.level.levelgen.SurfaceRules$YConditionSource
+ net.minecraft.world.level.levelgen.SurfaceRules$YConditionSource$1YCondition
- net.minecraft.world.level.levelgen.SurfaceSystem
+ net.minecraft.world.level.levelgen.SurfaceSystem$1
- net.minecraft.world.level.levelgen.ThreadSafeLegacyRandomSource
+ net.minecraft.world.level.levelgen.VerticalAnchor
- net.minecraft.world.level.levelgen.VerticalAnchor$AboveBottom
+ net.minecraft.world.level.levelgen.VerticalAnchor$Absolute
- net.minecraft.world.level.levelgen.VerticalAnchor$BelowTop
+ net.minecraft.world.level.levelgen.WorldDimensions
- net.minecraft.world.level.levelgen.WorldDimensions$1Entry
+ net.minecraft.world.level.levelgen.WorldDimensions$Complete
+ net.minecraft.world.level.levelgen.WorldGenerationContext
+ net.minecraft.world.level.levelgen.WorldgenRandom
- net.minecraft.world.level.levelgen.WorldgenRandom$Algorithm
- net.minecraft.world.level.levelgen.WorldGenSettings
- net.minecraft.world.level.levelgen.WorldOptions
+ net.minecraft.world.level.levelgen.Xoroshiro128PlusPlus
- net.minecraft.world.level.levelgen.XoroshiroRandomSource
+ net.minecraft.world.level.levelgen.XoroshiroRandomSource$XoroshiroPositionalRandomFactory
+ net.minecraft.world.level.LevelHeightAccessor
- net.minecraft.world.level.LevelHeightAccessor$1
+ net.minecraft.world.level.LevelReader
- net.minecraft.world.level.LevelSettings
- net.minecraft.world.level.LevelSimulatedReader
+ net.minecraft.world.level.LevelSimulatedRW
+ net.minecraft.world.level.LevelTimeAccess
- net.minecraft.world.level.LevelWriter
+ net.minecraft.world.level.LightLayer
- net.minecraft.world.level.LocalMobCapCalculator
+ net.minecraft.world.level.LocalMobCapCalculator$MobCounts
- net.minecraft.world.level.NaturalSpawner
+ net.minecraft.world.level.NaturalSpawner$1
- net.minecraft.world.level.NaturalSpawner$AfterSpawnCallback
+ net.minecraft.world.level.NaturalSpawner$ChunkGetter
- net.minecraft.world.level.NaturalSpawner$SpawnPredicate
+ net.minecraft.world.level.NaturalSpawner$SpawnState
- net.minecraft.world.level.NoiseColumn
+ net.minecraft.world.level.PathNavigationRegion
- net.minecraft.world.level.PotentialCalculator
+ net.minecraft.world.level.PotentialCalculator$PointCharge
- net.minecraft.world.level.ServerLevelAccessor
+ net.minecraft.world.level.SignalGetter
- net.minecraft.world.level.SpawnData
+ net.minecraft.world.level.SpawnData$CustomSpawnRules
- net.minecraft.world.level.StructureManager
+ net.minecraft.world.level.WorldDataConfiguration
- net.minecraft.world.level.WorldGenLevel
```

</details>
<details>
<summary>
Changes
</summary>

```
XXX.blaze3d.platform.GlConst +6P
```
```
XXX.blaze3d.systems.RenderSystem +65M -63M
```
```
net.minecraft.ChatFormatting +1M | +2P
```
```
net.minecraft.SharedConstants +1P
```
```
net.minecraft.Util +2M -1M
```
```
XXX.advancements.critereon.PlayerTrigger$TriggerInstance +1M
```
```
XXX.minecraft.client.Options +2P
```
```
XXX.client.gui.Font +1M -1M
```
```
XXX.client.model.PiglinModel +1M
```
```
XXX.client.player.RemotePlayer +1M -1M
```
```
XXX.client.renderer.BiomeColors +3M -2M
```
```
XXX.renderer.entity.EntityRenderDispatcher +3M | +1P
```
```
XXX.renderer.entity.GlowSquidRenderer +4M | +1P
```
```
XXX.renderer.entity.LivingEntityRenderer +1M | +1P
```
```
XXX.minecraft.core.Direction +3P
```
```
XXX.minecraft.core.Direction$Axis +1P
```
```
XXX.minecraft.core.Direction$Axis$2 +1M
```
```
XXX.core.particles.ParticleTypes +1P
```
```
XXX.loot.packs.VanillaBlockLoot +2M -1M
```
```
XXX.data.models.BlockModelGenerators +11M -1M
```
```
XXX.models.model.ModelTemplates +2P
```
```
XXX.data.recipes.ShapedRecipeBuilder$Result +1M -1M | +2P
```
```
XXX.data.worldgen.SurfaceRuleData +1M | +1P
```
```
XXX.server.network.ServerGamePacketListenerImpl +6M -1M | +4P -1P
```
```
XXX.minecraft.sounds.SoundEvents +1P
```
```
XXX.minecraft.tags.BannerPatternTags +1P
```
```
XXX.minecraft.tags.BlockTags +1P
```
```
XXX.minecraft.tags.ItemTags +2P
```
```
XXX.minecraft.util.StringUtil +1M -1M
```
```
XXX.world.damagesource.DeathMessageType +1P
```
```
XXX.entity.animal.Panda +1M -1M
```
```
XXX.entity.animal.Squid +2M -1M
```
```
XXX.entity.animal.WaterAnimal +1M
```
```
XXX.animal.allay.Allay +4M -1M
```
```
XXX.animal.camel.Camel +1M
```
```
XXX.entity.boss.EnderDragonPart +1M -1M
```
```
XXX.boss.enderdragon.EnderDragon +3M -1M
```
```
XXX.boss.wither.WitherBoss +1M -1M
```
```
XXX.entity.decoration.HangingEntity +1M -1M
```
```
XXX.entity.decoration.ItemFrame +1M -1M
```
```
XXX.entity.monster.Shulker +1M -1M
```
```
XXX.entity.monster.Strider +1M
```
```
XXX.entity.monster.Witch +1M
```
```
XXX.entity.monster.Zoglin +1M -1M
```
```
XXX.entity.vehicle.AbstractMinecart +1M -1M | +3P
```
```
XXX.entity.vehicle.Boat +3M -1M | +3P
```
```
XXX.entity.vehicle.MinecartHopper +2P
```
```
XXX.world.food.FoodProperties$Builder +2M | +1P
```
```
XXX.world.item.DyeColor +1P
```
```
XXX.item.crafting.FireworkStarFadeRecipe +2M -2M
```
```
XXX.item.crafting.MapCloningRecipe +2M -2M
```
```
XXX.level.block.Block +1M
```
```
XXX.level.block.Blocks +10M -8M | +8P
```
```
XXX.level.block.ButtonBlock +4M
```
```
XXX.level.block.CarpetBlock +1M
```
```
XXX.level.block.HoneyBlock +2M
```
```
XXX.level.block.IronBarsBlock +2M
```
```
XXX.level.block.LeverBlock +2M
```
```
XXX.level.block.LiquidBlock +2M
```
```
XXX.level.block.NetherPortalBlock +1M -1M | +1P
```
```
XXX.level.block.StainedGlassPaneBlock +1M
```
```
XXX.level.block.TntBlock +3M -1M
```
```
XXX.level.block.WeightedPressurePlateBlock +1M
```
```
XXX.block.entity.ChestBlockEntity +5M | +1P
```
```
XXX.block.entity.DropperBlockEntity +4M | +1P
```
```
XXX.block.piston.PistonBaseBlock +1M
```
```
XXX.block.piston.PistonMovingBlockEntity +2M | +1P
```
```
XXX.block.piston.PistonStructureResolver +1M -1M
```
```
XXX.block.state.BlockBehaviour +3M
```
```
XXX.block.state.BlockBehaviour$BlockStateBase +3M
```
```
XXX.levelgen.feature.Feature +2P
```
```
XXX.level.portal.PortalShape +7M -6M | +5P -1P
```
```
XXX.level.storage.LevelResource +2P
```
```
XXX.world.phys.AABB +1M
```

</details>














































<details>
<summary>
com.mojang.blaze3d.systems.RenderSystem
</summary>

```diff
- void cullFace(int)
+ void lambda$activeTexture$13(int)
- void lambda$activeTexture$14(int)
+ void lambda$applyModelViewMatrix$69(Matrix4f)
- void lambda$applyModelViewMatrix$70(Matrix4f)
+ void lambda$backupProjectionMatrix$70()
- void lambda$backupProjectionMatrix$71()
+ void lambda$bindTexture$16(int)
- void lambda$bindTexture$17(int)
+ void lambda$clear$25(int,boolean)
- void lambda$clear$26(int,boolean)
+ void lambda$clearColor$23(float,float,float,float)
- void lambda$clearColor$24(float,float,float,float)
+ void lambda$clearDepth$22(double)
- void lambda$clearDepth$23(double)
+ void lambda$clearStencil$24(int)
- void lambda$clearStencil$25(int)
+ void lambda$colorMask$18(boolean,boolean,boolean,boolean)
- void lambda$colorMask$19(boolean,boolean,boolean,boolean)
- void lambda$cullFace$10(int)
+ void lambda$deleteTexture$15(int)
- void lambda$deleteTexture$16(int)
+ void lambda$drawElements$33(int,int,int)
- void lambda$drawElements$34(int,int,int)
+ void lambda$getString$37(int,Consumer)
- void lambda$getString$38(int,Consumer)
+ void lambda$glBindBuffer$39(int,IntSupplier)
- void lambda$glBindBuffer$40(int,IntSupplier)
+ void lambda$glBindVertexArray$40(Supplier)
- void lambda$glBindVertexArray$41(Supplier)
+ void lambda$glDeleteBuffers$41(int)
- void lambda$glDeleteBuffers$42(int)
+ void lambda$glDeleteVertexArrays$42(int)
- void lambda$glDeleteVertexArrays$43(int)
+ void lambda$glGenBuffers$60(Consumer)
- void lambda$glGenBuffers$61(Consumer)
+ void lambda$glGenVertexArrays$61(Consumer)
- void lambda$glGenVertexArrays$62(Consumer)
+ void lambda$glUniform1$44(int,IntBuffer)
- void lambda$glUniform1$45(int,IntBuffer)
+ void lambda$glUniform1$48(int,FloatBuffer)
- void lambda$glUniform1$49(int,FloatBuffer)
+ void lambda$glUniform1i$43(int,int)
- void lambda$glUniform1i$44(int,int)
+ void lambda$glUniform2$45(int,IntBuffer)
- void lambda$glUniform2$46(int,IntBuffer)
+ void lambda$glUniform2$49(int,FloatBuffer)
- void lambda$glUniform2$50(int,FloatBuffer)
+ void lambda$glUniform3$46(int,IntBuffer)
- void lambda$glUniform3$47(int,IntBuffer)
+ void lambda$glUniform3$50(int,FloatBuffer)
- void lambda$glUniform3$51(int,FloatBuffer)
+ void lambda$glUniform4$47(int,IntBuffer)
- void lambda$glUniform4$48(int,IntBuffer)
+ void lambda$glUniform4$51(int,FloatBuffer)
- void lambda$glUniform4$52(int,FloatBuffer)
+ void lambda$glUniformMatrix2$52(int,boolean,FloatBuffer)
- void lambda$glUniformMatrix2$53(int,boolean,FloatBuffer)
+ void lambda$glUniformMatrix3$53(int,boolean,FloatBuffer)
- void lambda$glUniformMatrix3$54(int,boolean,FloatBuffer)
+ void lambda$glUniformMatrix4$54(int,boolean,FloatBuffer)
- void lambda$glUniformMatrix4$55(int,boolean,FloatBuffer)
+ void lambda$lineWidth$34(float)
- void lambda$lineWidth$35(float)
+ void lambda$logicOp$12(GlStateManager$LogicOp)
- void lambda$logicOp$13(GlStateManager$LogicOp)
+ void lambda$pixelStore$35(int,int)
- void lambda$pixelStore$36(int,int)
+ void lambda$polygonMode$10(int,int)
- void lambda$polygonMode$11(int,int)
+ void lambda$polygonOffset$11(float,float)
- void lambda$polygonOffset$12(float,float)
+ void lambda$readPixels$36(int,int,int,int,int,int,ByteBuffer)
- void lambda$readPixels$37(int,int,int,int,int,int,ByteBuffer)
+ void lambda$renderCrosshair$38(int)
- void lambda$renderCrosshair$39(int)
+ void lambda$resetTextureMatrix$68()
- void lambda$resetTextureMatrix$69()
+ void lambda$restoreProjectionMatrix$71()
- void lambda$restoreProjectionMatrix$72()
+ void lambda$setInverseViewRotationMatrix$66(Matrix3f)
- void lambda$setInverseViewRotationMatrix$67(Matrix3f)
+ void lambda$setProjectionMatrix$65(Matrix4f,VertexSorting)
- void lambda$setProjectionMatrix$66(Matrix4f,VertexSorting)
+ void lambda$setShader$62(Supplier)
- void lambda$setShader$63(Supplier)
+ void lambda$setShaderColor$32(float,float,float,float)
- void lambda$setShaderColor$33(float,float,float,float)
+ void lambda$setShaderFogColor$29(float,float,float,float)
- void lambda$setShaderFogColor$30(float,float,float,float)
+ void lambda$setShaderFogEnd$28(float)
- void lambda$setShaderFogEnd$29(float)
+ void lambda$setShaderFogShape$30(FogShape)
- void lambda$setShaderFogShape$31(FogShape)
+ void lambda$setShaderFogStart$26(float)
- void lambda$setShaderFogStart$27(float)
+ void lambda$setShaderGameTime$72(float)
- void lambda$setShaderGameTime$73(float)
+ void lambda$setShaderGlintAlpha$27(float)
- void lambda$setShaderGlintAlpha$28(float)
+ void lambda$setShaderLights$31(Vector3f,Vector3f)
- void lambda$setShaderLights$32(Vector3f,Vector3f)
+ void lambda$setShaderTexture$63(int,ResourceLocation)
+ void lambda$setShaderTexture$64(int,int)
- void lambda$setShaderTexture$64(int,ResourceLocation)
- void lambda$setShaderTexture$65(int,int)
+ void lambda$setTextureMatrix$67(Matrix4f)
- void lambda$setTextureMatrix$68(Matrix4f)
+ void lambda$setupGui3DDiffuseLighting$59(Vector3f,Vector3f)
- void lambda$setupGui3DDiffuseLighting$60(Vector3f,Vector3f)
+ void lambda$setupGuiFlatDiffuseLighting$58(Vector3f,Vector3f)
- void lambda$setupGuiFlatDiffuseLighting$59(Vector3f,Vector3f)
+ void lambda$setupLevelDiffuseLighting$57(Vector3f,Vector3f,Matrix4f)
- void lambda$setupLevelDiffuseLighting$58(Vector3f,Vector3f,Matrix4f)
+ void lambda$setupOverlayColor$55(IntSupplier)
- void lambda$setupOverlayColor$56(IntSupplier)
+ void lambda$stencilFunc$19(int,int,int)
- void lambda$stencilFunc$20(int,int,int)
+ void lambda$stencilMask$20(int)
- void lambda$stencilMask$21(int)
+ void lambda$stencilOp$21(int,int,int)
- void lambda$stencilOp$22(int,int,int)
+ void lambda$teardownOverlayColor$56()
- void lambda$teardownOverlayColor$57()
+ void lambda$texParameter$14(int,int,int)
- void lambda$texParameter$15(int,int,int)
+ void lambda$viewport$17(int,int,int,int)
- void lambda$viewport$18(int,int,int,int)
```

</details>
























































































































<details>
<summary>
net.minecraft.ChatFormatting
</summary>

```diff
- boolean lambda$static$2(ChatFormatting)
```

</details>







<details>
<summary>
net.minecraft.Util
</summary>

```diff
- int calculatePrefixSize(Iterable)
- void shuffle(List,RandomSource)
+ void shuffle(ObjectArrayList,RandomSource)
```

</details>





































































<details>
<summary>
net.minecraft.advancements.critereon.PlayerTrigger$TriggerInstance
</summary>

```diff
- PlayerTrigger$TriggerInstance vote(MinMaxBounds$Ints)
```

</details>






































































<details>
<summary>
net.minecraft.client.gui.Font
</summary>

```diff
- void renderChar(BakedGlyph,boolean,boolean,boolean,float,float,float,Matrix4f,VertexConsumer,float,float,float,float,int)
+ void renderChar(BakedGlyph,boolean,boolean,float,float,float,Matrix4f,VertexConsumer,float,float,float,float,int)
```

</details>











<details>
<summary>
net.minecraft.client.model.PiglinModel
</summary>

```diff
- boolean miniMe()
```

</details>













<details>
<summary>
net.minecraft.client.player.RemotePlayer
</summary>

```diff
+ boolean hurt(DamageSource,float)
- boolean hurtInternal(DamageSource,float)
```

</details>


<details>
<summary>
net.minecraft.client.renderer.BiomeColors
</summary>

```diff
+ int lambda$static$0(Biome,double,double)
- int lambda$static$0(Holder,double,double)
+ int lambda$static$1(Biome,double,double)
- int lambda$static$1(Holder,double,double)
- int lambda$static$2(Holder,double,double)
```

</details>







<details>
<summary>
net.minecraft.client.renderer.entity.EntityRenderDispatcher
</summary>

```diff
- boolean shouldRender0(Entity,Frustum,double,double,double)
- void render0(Entity,float,double,double,double,float,float,PoseStack,MultiBufferSource,int)
- void renderDynamicShadow(PoseStack,MultiBufferSource,float,float)
```

</details>







<details>
<summary>
net.minecraft.client.renderer.entity.GlowSquidRenderer
</summary>

```diff
- void render(Entity,float,float,PoseStack,MultiBufferSource,int)
- void render(GlowSquid,float,float,PoseStack,MultiBufferSource,int)
- void render(LivingEntity,float,float,PoseStack,MultiBufferSource,int)
- void render(Mob,float,float,PoseStack,MultiBufferSource,int)
```

</details>







<details>
<summary>
net.minecraft.client.renderer.entity.LivingEntityRenderer
</summary>

```diff
- VertexConsumer getVertexConsumer(LivingEntity,PoseStack,MultiBufferSource,boolean,boolean,boolean)
```

</details>





































































































































<details>
<summary>
net.minecraft.core.Direction$Axis$2
</summary>

```diff
- Direction[] getOrthogonalDirections()
```

</details>
























































































<details>
<summary>
net.minecraft.data.loot.packs.VanillaBlockLoot
</summary>

```diff
+ LootPoolEntryContainer$Builder lambda$createPitcherCropLoot$238(Integer)
- LootPoolEntryContainer$Builder lambda$createPitcherCropLoot$239(Integer)
- LootTable$Builder lambda$generate$238(Block)
```

</details>




<details>
<summary>
net.minecraft.data.models.BlockModelGenerators
</summary>

```diff
- boolean isOnEdge(double,double,double,double,double,double,Direction)
- JsonElement lambda$createCheeseBlock$58(ResourceLocation,VoxelShape)
- JsonObject buildModelFromShape(ResourceLocation,VoxelShape)
- void createCheeseBlock()
- void createFacing(Block)
+ void createNetherPortalBlock()
- void createNetherPortalBlock(Block)
- void createPackedAir()
- void createSpleaves(Block)
- void lambda$buildModelFromShape$59(double,double,double,JsonArray)
- void lambda$buildModelFromShape$60(double,double,double,JsonArray)
- void lambda$buildModelFromShape$61(JsonArray,double,double,double,double,double,double)
```

</details>



























<details>
<summary>
net.minecraft.data.recipes.ShapedRecipeBuilder$Result
</summary>

```diff
- void <init>(ResourceLocation,Item,int,String,CraftingBookCategory,List,Map,Advancement$Builder,ResourceLocation,boolean,boolean,boolean)
+ void <init>(ResourceLocation,Item,int,String,CraftingBookCategory,List,Map,Advancement$Builder,ResourceLocation,boolean)
```

</details>



































<details>
<summary>
net.minecraft.data.worldgen.SurfaceRuleData
</summary>

```diff
- SurfaceRules$RuleSource moon()
```

</details>















































































<details>
<summary>
net.minecraft.server.network.ServerGamePacketListenerImpl
</summary>

```diff
+ CompletableFuture lambda$resetPlayerChatState$15(RemoteChatSession,Executor)
- CompletableFuture lambda$resetPlayerChatState$16(RemoteChatSession,Executor)
- float maxInteractionDistanceSq()
- int lambda$fireworksYay$15(RandomSource)
- void fireworksYay()
- void handleCrashVehicle(ServerboundCrashVehiclePacket)
- void handleVoteCast(ServerboundVoteCastPacket)
```

</details>





































































































































<details>
<summary>
net.minecraft.util.StringUtil
</summary>

```diff
+ String formatTickDuration(int)
- String formatTickDuration(long)
```

</details>




































































































































































































<details>
<summary>
net.minecraft.world.entity.animal.Panda
</summary>

```diff
+ boolean hurt(DamageSource,float)
- boolean hurtInternal(DamageSource,float)
```

</details>



















<details>
<summary>
net.minecraft.world.entity.animal.Squid
</summary>

```diff
+ boolean hurt(DamageSource,float)
- boolean hurtInternal(DamageSource,float)
- void transformedTick(EntityTransform,LivingEntity)
```

</details>








<details>
<summary>
net.minecraft.world.entity.animal.WaterAnimal
</summary>

```diff
- boolean canTransformBreatheInAir()
```

</details>

<details>
<summary>
net.minecraft.world.entity.animal.allay.Allay
</summary>

```diff
- boolean canTransformFly()
+ boolean hurt(DamageSource,float)
- boolean hurtInternal(DamageSource,float)
- void tickAnimation()
- void transformedTick(EntityTransform,LivingEntity)
```

</details>






<details>
<summary>
net.minecraft.world.entity.animal.camel.Camel
</summary>

```diff
- InteractionResult transformInteract(Player,LivingEntity,InteractionHand)
```

</details>


























<details>
<summary>
net.minecraft.world.entity.boss.EnderDragonPart
</summary>

```diff
+ boolean hurt(DamageSource,float)
- boolean hurtInternal(DamageSource,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.boss.enderdragon.EnderDragon
</summary>

```diff
- boolean canTransformFly()
+ boolean hurt(DamageSource,float)
- boolean hurtInternal(DamageSource,float)
- void transformedTick(EntityTransform,LivingEntity)
```

</details>









<details>
<summary>
net.minecraft.world.entity.boss.wither.WitherBoss
</summary>

```diff
+ boolean hurt(DamageSource,float)
- boolean hurtInternal(DamageSource,float)
```

</details>


<details>
<summary>
net.minecraft.world.entity.decoration.HangingEntity
</summary>

```diff
+ boolean hurt(DamageSource,float)
- boolean hurtInternal(DamageSource,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.decoration.ItemFrame
</summary>

```diff
+ boolean hurt(DamageSource,float)
- boolean hurtInternal(DamageSource,float)
```

</details>




<details>
<summary>
net.minecraft.world.entity.monster.Shulker
</summary>

```diff
+ boolean hurt(DamageSource,float)
- boolean hurtInternal(DamageSource,float)
```

</details>












<details>
<summary>
net.minecraft.world.entity.monster.Strider
</summary>

```diff
- InteractionResult transformInteract(Player,LivingEntity,InteractionHand)
```

</details>





<details>
<summary>
net.minecraft.world.entity.monster.Witch
</summary>

```diff
- boolean isItAwkwardToMilk()
```

</details>
<details>
<summary>
net.minecraft.world.entity.monster.Zoglin
</summary>

```diff
+ boolean hurt(DamageSource,float)
- boolean hurtInternal(DamageSource,float)
```

</details>
<details>
<summary>
net.minecraft.world.entity.vehicle.AbstractMinecart
</summary>

```diff
+ boolean hurt(DamageSource,float)
- boolean hurtInternal(DamageSource,float)
```

</details>

<details>
<summary>
net.minecraft.world.entity.vehicle.Boat
</summary>

```diff
+ boolean hurt(DamageSource,float)
- boolean hurtInternal(DamageSource,float)
- float maxUpStep()
- void handleCrash(float)
```

</details>














<details>
<summary>
net.minecraft.world.food.FoodProperties$Builder
</summary>

```diff
- FoodProperties$Builder withMagic(BiConsumer)
- void lambda$new$0(ItemStack,LivingEntity)
```

</details>




























<details>
<summary>
net.minecraft.world.item.crafting.FireworkStarFadeRecipe
</summary>

```diff
+ ItemStack assemble(Container,RegistryAccess)
+ ItemStack assemble(CraftingContainer,RegistryAccess)
- ItemStack assembleRaw(Container,RegistryAccess)
- ItemStack assembleRaw(CraftingContainer,RegistryAccess)
```

</details>


<details>
<summary>
net.minecraft.world.item.crafting.MapCloningRecipe
</summary>

```diff
+ ItemStack assemble(Container,RegistryAccess)
+ ItemStack assemble(CraftingContainer,RegistryAccess)
- ItemStack assembleRaw(Container,RegistryAccess)
- ItemStack assembleRaw(CraftingContainer,RegistryAccess)
```

</details>




















<details>
<summary>
net.minecraft.world.level.block.Block
</summary>

```diff
- void playerStepOn(Level,BlockPos,BlockState,Entity)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.Blocks
</summary>

```diff
+ boolean lambda$static$36(BlockState,BlockGetter,BlockPos,EntityType)
- boolean lambda$static$37(BlockState,BlockGetter,BlockPos,EntityType)
+ boolean lambda$static$38(BlockState,BlockGetter,BlockPos,EntityType)
- boolean lambda$static$39(BlockState,BlockGetter,BlockPos,EntityType)
+ boolean lambda$static$51(BlockState,BlockGetter,BlockPos)
- boolean lambda$static$53(BlockState,BlockGetter,BlockPos)
- int lambda$static$21(BlockState)
+ int lambda$static$25(BlockState)
- int lambda$static$36(BlockState)
+ int lambda$static$37(BlockState)
- int lambda$static$38(BlockState)
+ int lambda$static$39(BlockState)
- int lambda$static$51(BlockState)
+ int lambda$static$53(BlockState)
- int lambda$static$56(BlockState)
- int lambda$static$57(BlockState)
+ Item lambda$static$21()
- Item lambda$static$25()
```

</details>



<details>
<summary>
net.minecraft.world.level.block.ButtonBlock
</summary>

```diff
- BlockState getValidAttachedState(BlockState,Direction,Direction)
- boolean isRandomlyTicking(BlockState)
- void randomTick(BlockState,ServerLevel,BlockPos,RandomSource)
- VoxelShape getCollisionShape(BlockState,BlockGetter,BlockPos,CollisionContext)
```

</details>



<details>
<summary>
net.minecraft.world.level.block.CarpetBlock
</summary>

```diff
- boolean isStickyToNeighbour(Level,BlockPos,BlockState,BlockPos,BlockState,Direction,Direction)
```

</details>



































<details>
<summary>
net.minecraft.world.level.block.HoneyBlock
</summary>

```diff
- boolean canStickToStuff(BlockState)
- boolean isStickyToNeighbour(Level,BlockPos,BlockState,BlockPos,BlockState,Direction,Direction)
```

</details>



<details>
<summary>
net.minecraft.world.level.block.IronBarsBlock
</summary>

```diff
- boolean canAirPass(BlockState,ServerLevel,BlockPos,Direction)
- boolean canAirPassThroughGlassPane(BlockState,ServerLevel,BlockPos,Direction)
```

</details>






<details>
<summary>
net.minecraft.world.level.block.LeverBlock
</summary>

```diff
- boolean isRandomlyTicking(BlockState)
- void randomTick(BlockState,ServerLevel,BlockPos,RandomSource)
```

</details>

<details>
<summary>
net.minecraft.world.level.block.LiquidBlock
</summary>

```diff
- boolean canAirPass(BlockState,ServerLevel,BlockPos,Direction)
- boolean canStickToStuff(BlockState)
```

</details>











<details>
<summary>
net.minecraft.world.level.block.NetherPortalBlock
</summary>

```diff
- void <init>(BlockBehaviour$Properties,boolean)
+ void <init>(BlockBehaviour$Properties)
```

</details>








<details>
<summary>
net.minecraft.world.level.block.StainedGlassPaneBlock
</summary>

```diff
- boolean canAirPass(BlockState,ServerLevel,BlockPos,Direction)
```

</details>










<details>
<summary>
net.minecraft.world.level.block.TntBlock
</summary>

```diff
- BlockState getStateForPlacement(BlockPlaceContext)
- void explode(Level,BlockPos,BlockState)
- void explode(Level,BlockPos,LivingEntity,BlockState)
+ void explode(Level,BlockPos,LivingEntity)
```

</details>















<details>
<summary>
net.minecraft.world.level.block.WeightedPressurePlateBlock
</summary>

```diff
- void entityInside(BlockState,Level,BlockPos,Entity)
```

</details>

















<details>
<summary>
net.minecraft.world.level.block.entity.ChestBlockEntity
</summary>

```diff
- boolean isGold()
- ClientboundBlockEntityDataPacket getUpdatePacket()
- CompoundTag getUpdateTag()
- Packet getUpdatePacket()
- void setGold(boolean)
```

</details>






<details>
<summary>
net.minecraft.world.level.block.entity.DropperBlockEntity
</summary>

```diff
- boolean isLunar()
- void load(CompoundTag)
- void saveAdditional(CompoundTag)
- void setLunar()
```

</details>
























<details>
<summary>
net.minecraft.world.level.block.piston.PistonBaseBlock
</summary>

```diff
- boolean isStickyToNeighbour(Level,BlockPos,BlockState,BlockPos,BlockState,Direction,Direction)
```

</details>


<details>
<summary>
net.minecraft.world.level.block.piston.PistonMovingBlockEntity
</summary>

```diff
- BlockEntity getRenderBlockEntity()
- void setCarriedBlockEntity(BlockEntity,Level)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.piston.PistonStructureResolver
</summary>

```diff
- boolean canStickToEachOther(BlockPos,BlockState,BlockPos,BlockState,Direction)
+ boolean canStickToEachOther(BlockState,BlockState)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.BlockBehaviour
</summary>

```diff
- boolean canAirPass(BlockState,ServerLevel,BlockPos,Direction)
- boolean canStickToStuff(BlockState)
- boolean isStickyToNeighbour(Level,BlockPos,BlockState,BlockPos,BlockState,Direction,Direction)
```

</details>
<details>
<summary>
net.minecraft.world.level.block.state.BlockBehaviour$BlockStateBase
</summary>

```diff
- boolean canAirPass(ServerLevel,BlockPos,Direction)
- boolean canStickToStuff()
- boolean isStickyToNeighbour(Level,BlockPos,BlockPos,BlockState,Direction,Direction)
```

</details>























































































































































































































































































































































































<details>
<summary>
net.minecraft.world.level.portal.PortalShape
</summary>

```diff
+ boolean lambda$findEmptyPortalShape$1(PortalShape)
- boolean lambda$findEmptyPortalShape$2(PortalShape)
- boolean lambda$static$1(BlockState,BlockGetter,BlockPos)
- Optional findEmptyPortalShape(LevelAccessor,BlockPos,Direction$Axis,boolean)
+ Optional findEmptyPortalShape(LevelAccessor,BlockPos,Direction$Axis)
- Optional findPortalShape(LevelAccessor,BlockPos,Predicate,Direction$Axis,boolean)
+ Optional findPortalShape(LevelAccessor,BlockPos,Predicate,Direction$Axis)
+ Vec3 lambda$findCollisionFreePosition$3(double,Vec3)
- Vec3 lambda$findCollisionFreePosition$4(double,Vec3)
- void <init>(LevelAccessor,BlockPos,Direction$Axis,boolean)
+ void <init>(LevelAccessor,BlockPos,Direction$Axis)
+ void lambda$createPortalBlocks$2(BlockState,BlockPos)
- void lambda$createPortalBlocks$3(BlockState,BlockPos)
```

</details>



















































































































































<details>
<summary>
net.minecraft.world.phys.AABB
</summary>

```diff
- AABB scale(float)
```

</details>
</details>