## Comparison with [23w13a](https://github.com/PixiGeko/Minecraft-generated-data/tree/23w13a)

> [!TIP]
> - [Version data](#version-data)
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
<table><tr><th></th><th align="left">23w13a</th><th>23w13a_or_b</th></tr><tr><td>World version</td><td><pre>3443</pre></td><td><pre>3444</pre></td></tr><tr><td>Protocol version</td><td><pre>1073741952</pre></td><td><pre>1073741953</pre></td></tr></table>
</details>
<hr/>
<details><summary><b><ins>REGISTRIES</ins></b><a name="registries"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
+ rules.txt
```

</details>
<details>
<summary>
attribute
</summary>

```diff
+ minecraft:generic.scale
```

</details>
<details>
<summary>
banner_pattern
</summary>

```diff
+ minecraft:m
```

</details>
<details>
<summary>
block
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
custom_stat
</summary>

```diff
+ minecraft:votes
```

</details>
<details>
<summary>
entity_type
</summary>

```diff
+ minecraft:moon_cow
+ minecraft:ray_tracing
+ minecraft:stencil_display
```

</details>
<details>
<summary>
item
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
mob_effect
</summary>

```diff
+ minecraft:big
+ minecraft:small
```

</details>
<details>
<summary>
particle_type
</summary>

```diff
+ minecraft:footstep
```

</details>
<details>
<summary>
potion
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
recipe_serializer
</summary>

```diff
+ minecraft:crafting_special_dupehack
+ minecraft:nbt_crafting_recipe
```

</details>
<details>
<summary>
sound_event
</summary>

```diff
+ minecraft:the_joke
```

</details>
<details>
<summary>
worldgen/biome_source
</summary>

```diff
+ minecraft:the_moon
```

</details>
<details>
<summary>
worldgen/feature
</summary>

```diff
+ minecraft:crater
+ minecraft:lunar_base
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
<hr/>
<details><summary><b><ins>BLOCKS</ins></b><a name="blocks"></a></summary>
<br/>
<details>
<summary>
🗒️ List
</summary>

```diff
+ cheese.json
+ copper_sink.json
+ copper_spleaves.json
+ filled_copper_sink.json
+ other_portal.json
+ packed_air.json
+ pickaxe_block.json
+ place_block.json
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
+ transform.txt
+ vote.txt
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
<hr/>
<details><summary><b><ins>TRANSLATIONS</ins></b><a name="translations"></a></summary>
<br/>
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
<hr/>
<details><summary><b><ins>FILE STRUCTURE</ins></b><a name="file-structure"></a></summary>
<br/>
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
<hr/>
<details><summary><b><ins>MISC</ins></b><a name="misc"></a></summary>
<br/>
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
<hr/>
<details><summary><b><ins>MAPPINGS</ins></b><a name="mappings"></a></summary>
<br/>
<h2>Server<a name="server-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
- net.minecraft.package-info
+ XXX.ai.attributes.Attribute
- XXX.ai.attributes.AttributeInstance
+ XXX.ai.attributes.AttributeMap
- XXX.ai.attributes.AttributeModifier
+ XXX.ai.attributes.AttributeModifier$Operation
- XXX.ai.attributes.Attributes
- XXX.ai.attributes.AttributeSupplier
+ XXX.ai.attributes.AttributeSupplier$Builder
+ XXX.ai.attributes.DefaultAttributes
+ XXX.ai.attributes.package-info
- XXX.ai.attributes.RangedAttribute
- XXX.ai.behavior.AcquirePoi
+ XXX.ai.behavior.AcquirePoi$JitteredLinearRetry
- XXX.ai.behavior.AnimalMakeLove
+ XXX.ai.behavior.AnimalPanic
- XXX.ai.behavior.AssignProfessionFromJobSite
+ XXX.ai.behavior.BabyFollowAdult
- XXX.ai.behavior.BackUpIfTooClose
+ XXX.ai.behavior.BecomePassiveIfMemoryPresent
- XXX.ai.behavior.Behavior
+ XXX.ai.behavior.Behavior$Status
- XXX.ai.behavior.BehaviorControl
+ XXX.ai.behavior.BehaviorUtils
- XXX.ai.behavior.BlockPosTracker
+ XXX.ai.behavior.CelebrateVillagersSurvivedRaid
- XXX.ai.behavior.CopyMemoryWithExpiry
+ XXX.ai.behavior.CountDownCooldownTicks
- XXX.ai.behavior.Croak
+ XXX.ai.behavior.CrossbowAttack
- XXX.ai.behavior.CrossbowAttack$CrossbowState
+ XXX.ai.behavior.DismountOrSkipMounting
- XXX.ai.behavior.DoNothing
+ XXX.ai.behavior.EntityTracker
- XXX.ai.behavior.EraseMemoryIf
+ XXX.ai.behavior.FollowTemptation
- XXX.ai.behavior.GateBehavior
+ XXX.ai.behavior.GateBehavior$OrderPolicy
- XXX.ai.behavior.GateBehavior$RunningPolicy
+ XXX.ai.behavior.GateBehavior$RunningPolicy$1
- XXX.ai.behavior.GateBehavior$RunningPolicy$2
+ XXX.ai.behavior.GiveGiftToHero
- XXX.ai.behavior.GoAndGiveItemsToTarget
+ XXX.ai.behavior.GoToClosestVillage
- XXX.ai.behavior.GoToPotentialJobSite
+ XXX.ai.behavior.GoToTargetLocation
- XXX.ai.behavior.GoToWantedItem
+ XXX.ai.behavior.HarvestFarmland
- XXX.ai.behavior.InsideBrownianWalk
+ XXX.ai.behavior.InteractWith
- XXX.ai.behavior.InteractWithDoor
+ XXX.ai.behavior.JumpOnBed
- XXX.ai.behavior.LocateHidingPlace
+ XXX.ai.behavior.LongJumpMidJump
- XXX.ai.behavior.LongJumpToPreferredBlock
+ XXX.ai.behavior.LongJumpToRandomPos
- XXX.ai.behavior.LongJumpToRandomPos$PossibleJump
+ XXX.ai.behavior.LookAndFollowTradingPlayerSink
- XXX.ai.behavior.LookAtTargetSink
+ XXX.ai.behavior.MeleeAttack
- XXX.ai.behavior.Mount
+ XXX.ai.behavior.MoveToSkySeeingSpot
- XXX.ai.behavior.MoveToTargetSink
+ XXX.ai.behavior.OneShot
+ XXX.ai.behavior.package-info
- XXX.ai.behavior.PlayTagWithOtherKids
+ XXX.ai.behavior.PoiCompetitorScan
- XXX.ai.behavior.PositionTracker
+ XXX.ai.behavior.PrepareRamNearestTarget
- XXX.ai.behavior.PrepareRamNearestTarget$RamCandidate
+ XXX.ai.behavior.RamTarget
- XXX.ai.behavior.RandomLookAround
+ XXX.ai.behavior.RandomStroll
- XXX.ai.behavior.ReactToBell
+ XXX.ai.behavior.ResetProfession
- XXX.ai.behavior.ResetRaidStatus
+ XXX.ai.behavior.RingBell
- XXX.ai.behavior.RunOne
+ XXX.ai.behavior.SetClosestHomeAsWalkTarget
- XXX.ai.behavior.SetEntityLookTarget
+ XXX.ai.behavior.SetEntityLookTargetSometimes
- XXX.ai.behavior.SetEntityLookTargetSometimes$Ticker
+ XXX.ai.behavior.SetHiddenState
- XXX.ai.behavior.SetLookAndInteract
+ XXX.ai.behavior.SetRaidStatus
- XXX.ai.behavior.SetWalkTargetAwayFrom
+ XXX.ai.behavior.SetWalkTargetFromAttackTargetIfTargetOutOfReach
- XXX.ai.behavior.SetWalkTargetFromBlockMemory
+ XXX.ai.behavior.SetWalkTargetFromLookTarget
- XXX.ai.behavior.ShowTradesToPlayer
+ XXX.ai.behavior.ShufflingList
- XXX.ai.behavior.ShufflingList$WeightedEntry
+ XXX.ai.behavior.ShufflingList$WeightedEntry$1
- XXX.ai.behavior.SleepInBed
+ XXX.ai.behavior.SocializeAtBell
- XXX.ai.behavior.StartAttacking
+ XXX.ai.behavior.StartCelebratingIfTargetDead
- XXX.ai.behavior.StayCloseToTarget
+ XXX.ai.behavior.StopAttackingIfTargetInvalid
- XXX.ai.behavior.StopBeingAngryIfTargetDead
+ XXX.ai.behavior.StrollAroundPoi
- XXX.ai.behavior.StrollToPoi
+ XXX.ai.behavior.StrollToPoiList
- XXX.ai.behavior.Swim
+ XXX.ai.behavior.TradeWithVillager
- XXX.ai.behavior.TriggerGate
+ XXX.ai.behavior.TryFindLand
- XXX.ai.behavior.TryFindLandNearWater
+ XXX.ai.behavior.TryFindWater
- XXX.ai.behavior.TryLaySpawnOnWaterNearLand
+ XXX.ai.behavior.UpdateActivityFromSchedule
- XXX.ai.behavior.UseBonemeal
+ XXX.ai.behavior.ValidateNearbyPoi
- XXX.ai.behavior.VillageBoundRandomStroll
+ XXX.ai.behavior.VillagerCalmDown
- XXX.ai.behavior.VillagerGoalPackages
+ XXX.ai.behavior.VillagerMakeLove
- XXX.ai.behavior.VillagerPanicTrigger
+ XXX.ai.behavior.WakeUp
- XXX.ai.behavior.WorkAtComposter
+ XXX.ai.behavior.WorkAtPoi
- XXX.ai.behavior.YieldJobSite
- XXX.ai.control.BodyRotationControl
+ XXX.ai.control.Control
- XXX.ai.control.FlyingMoveControl
+ XXX.ai.control.JumpControl
- XXX.ai.control.LookControl
+ XXX.ai.control.MoveControl
- XXX.ai.control.MoveControl$Operation
+ XXX.ai.control.package-info
+ XXX.ai.control.SmoothSwimmingLookControl
- XXX.ai.control.SmoothSwimmingMoveControl
- XXX.ai.goal.AvoidEntityGoal
+ XXX.ai.goal.BegGoal
- XXX.ai.goal.BoatGoals
+ XXX.ai.goal.BreakDoorGoal
- XXX.ai.goal.BreathAirGoal
+ XXX.ai.goal.BreedGoal
- XXX.ai.goal.CatLieOnBedGoal
+ XXX.ai.goal.CatSitOnBlockGoal
- XXX.ai.goal.ClimbOnTopOfPowderSnowGoal
+ XXX.ai.goal.DolphinJumpGoal
- XXX.ai.goal.DoorInteractGoal
+ XXX.ai.goal.EatBlockGoal
- XXX.ai.goal.FleeSunGoal
+ XXX.ai.goal.FloatGoal
- XXX.ai.goal.FollowBoatGoal
+ XXX.ai.goal.FollowFlockLeaderGoal
- XXX.ai.goal.FollowMobGoal
+ XXX.ai.goal.FollowOwnerGoal
- XXX.ai.goal.FollowParentGoal
+ XXX.ai.goal.Goal
- XXX.ai.goal.Goal$Flag
+ XXX.ai.goal.GoalSelector
- XXX.ai.goal.GoalSelector$1
+ XXX.ai.goal.GoalSelector$2
- XXX.ai.goal.GolemRandomStrollInVillageGoal
+ XXX.ai.goal.InteractGoal
- XXX.ai.goal.JumpGoal
+ XXX.ai.goal.LandOnOwnersShoulderGoal
- XXX.ai.goal.LeapAtTargetGoal
+ XXX.ai.goal.LlamaFollowCaravanGoal
- XXX.ai.goal.LookAtPlayerGoal
+ XXX.ai.goal.LookAtTradingPlayerGoal
- XXX.ai.goal.MeleeAttackGoal
+ XXX.ai.goal.MoveBackToVillageGoal
- XXX.ai.goal.MoveThroughVillageGoal
+ XXX.ai.goal.MoveToBlockGoal
- XXX.ai.goal.MoveTowardsRestrictionGoal
+ XXX.ai.goal.MoveTowardsTargetGoal
- XXX.ai.goal.OcelotAttackGoal
+ XXX.ai.goal.OfferFlowerGoal
- XXX.ai.goal.OpenDoorGoal
+ XXX.ai.goal.package-info
+ XXX.ai.goal.PanicGoal
- XXX.ai.goal.PathfindToRaidGoal
+ XXX.ai.goal.RandomLookAroundGoal
- XXX.ai.goal.RandomStandGoal
+ XXX.ai.goal.RandomStrollGoal
- XXX.ai.goal.RandomSwimmingGoal
+ XXX.ai.goal.RangedAttackGoal
- XXX.ai.goal.RangedBowAttackGoal
+ XXX.ai.goal.RangedCrossbowAttackGoal
- XXX.ai.goal.RangedCrossbowAttackGoal$CrossbowState
+ XXX.ai.goal.RemoveBlockGoal
- XXX.ai.goal.RestrictSunGoal
+ XXX.ai.goal.RunAroundLikeCrazyGoal
- XXX.ai.goal.SitWhenOrderedToGoal
+ XXX.ai.goal.StrollThroughVillageGoal
- XXX.ai.goal.SwellGoal
+ XXX.ai.goal.TemptGoal
- XXX.ai.goal.TradeWithPlayerGoal
+ XXX.ai.goal.TryFindWaterGoal
- XXX.ai.goal.UseItemGoal
+ XXX.ai.goal.WaterAvoidingRandomFlyingGoal
- XXX.ai.goal.WaterAvoidingRandomStrollGoal
+ XXX.ai.goal.WrappedGoal
- XXX.ai.goal.ZombieAttackGoal
+ XXX.ai.gossip.GossipContainer
- XXX.ai.gossip.GossipContainer$EntityGossips
+ XXX.ai.gossip.GossipContainer$GossipEntry
- XXX.ai.gossip.GossipType
+ XXX.ai.gossip.package-info
- XXX.ai.memory.ExpirableValue
+ XXX.ai.memory.MemoryModuleType
- XXX.ai.memory.MemoryStatus
+ XXX.ai.memory.NearestVisibleLivingEntities
+ XXX.ai.memory.package-info
- XXX.ai.memory.WalkTarget
- XXX.ai.navigation.AmphibiousPathNavigation
+ XXX.ai.navigation.FlyingPathNavigation
- XXX.ai.navigation.GroundPathNavigation
- XXX.ai.navigation.package-info
+ XXX.ai.navigation.PathNavigation
- XXX.ai.navigation.WallClimberNavigation
+ XXX.ai.navigation.WaterBoundPathNavigation
- XXX.ai.sensing.AdultSensor
+ XXX.ai.sensing.AxolotlAttackablesSensor
- XXX.ai.sensing.DummySensor
+ XXX.ai.sensing.FrogAttackablesSensor
- XXX.ai.sensing.GolemSensor
+ XXX.ai.sensing.HoglinSpecificSensor
- XXX.ai.sensing.HurtBySensor
+ XXX.ai.sensing.IsInWaterSensor
- XXX.ai.sensing.NearestBedSensor
+ XXX.ai.sensing.NearestItemSensor
- XXX.ai.sensing.NearestLivingEntitySensor
+ XXX.ai.sensing.NearestVisibleLivingEntitySensor
+ XXX.ai.sensing.package-info
- XXX.ai.sensing.PiglinBruteSpecificSensor
+ XXX.ai.sensing.PiglinSpecificSensor
- XXX.ai.sensing.PlayerSensor
+ XXX.ai.sensing.SecondaryPoiSensor
- XXX.ai.sensing.Sensing
+ XXX.ai.sensing.Sensor
- XXX.ai.sensing.SensorType
+ XXX.ai.sensing.TemptingSensor
- XXX.ai.sensing.VillagerBabiesSensor
+ XXX.ai.sensing.VillagerHostilesSensor
- XXX.ai.sensing.WardenEntitySensor
+ XXX.ai.targeting.package-info
- XXX.ai.targeting.TargetingConditions
- XXX.ai.util.AirAndWaterRandomPos
+ XXX.ai.util.AirRandomPos
- XXX.ai.util.DefaultRandomPos
+ XXX.ai.util.GoalUtils
- XXX.ai.util.HoverRandomPos
+ XXX.ai.util.LandRandomPos
+ XXX.ai.util.package-info
- XXX.ai.util.RandomPos
- XXX.ai.village.package-info
- XXX.ai.village.ReputationEventType
+ XXX.ai.village.ReputationEventType$1
- XXX.ai.village.VillageSiege
+ XXX.ai.village.VillageSiege$State
+ XXX.behavior.declarative.BehaviorBuilder
- XXX.behavior.declarative.BehaviorBuilder$1
+ XXX.behavior.declarative.BehaviorBuilder$Constant
- XXX.behavior.declarative.BehaviorBuilder$Constant$1
+ XXX.behavior.declarative.BehaviorBuilder$Instance
- XXX.behavior.declarative.BehaviorBuilder$Instance$1
+ XXX.behavior.declarative.BehaviorBuilder$Instance$2
- XXX.behavior.declarative.BehaviorBuilder$Instance$3
+ XXX.behavior.declarative.BehaviorBuilder$Instance$4
- XXX.behavior.declarative.BehaviorBuilder$Instance$5
+ XXX.behavior.declarative.BehaviorBuilder$Instance$Mu
- XXX.behavior.declarative.BehaviorBuilder$Mu
+ XXX.behavior.declarative.BehaviorBuilder$PureMemory
- XXX.behavior.declarative.BehaviorBuilder$PureMemory$1
+ XXX.behavior.declarative.BehaviorBuilder$TriggerWithResult
- XXX.behavior.declarative.BehaviorBuilder$TriggerWrapper
+ XXX.behavior.declarative.BehaviorBuilder$TriggerWrapper$1
- XXX.behavior.declarative.MemoryAccessor
+ XXX.behavior.declarative.MemoryCondition
- XXX.behavior.declarative.MemoryCondition$Absent
+ XXX.behavior.declarative.MemoryCondition$Present
- XXX.behavior.declarative.MemoryCondition$Registered
- XXX.behavior.declarative.package-info
+ XXX.behavior.declarative.Trigger
- XXX.behavior.warden.Digging
+ XXX.behavior.warden.Emerging
- XXX.behavior.warden.ForceUnmount
+ XXX.behavior.warden.package-info
+ XXX.behavior.warden.Roar
- XXX.behavior.warden.SetRoarTarget
+ XXX.behavior.warden.SetWardenLookTarget
- XXX.behavior.warden.Sniffing
+ XXX.behavior.warden.SonicBoom
- XXX.behavior.warden.TryToSniff
- XXX.chat.contents.BlockDataSource
+ XXX.chat.contents.DataSource
- XXX.chat.contents.EntityDataSource
+ XXX.chat.contents.KeybindContents
- XXX.chat.contents.KeybindResolver
+ XXX.chat.contents.LiteralContents
- XXX.chat.contents.NbtContents
- XXX.chat.contents.package-info
+ XXX.chat.contents.ScoreContents
- XXX.chat.contents.SelectorContents
+ XXX.chat.contents.StorageDataSource
- XXX.chat.contents.TranslatableContents
+ XXX.chat.contents.TranslatableFormatException
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
- XXX.data.worldgen.package-info
+ XXX.datafix.schemas.package-info
- XXX.datafix.schemas.V3444
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
+ XXX.entity.ai.Brain
- XXX.entity.ai.Brain$1
+ XXX.entity.ai.Brain$MemoryValue
- XXX.entity.ai.Brain$Provider
+ XXX.entity.ai.package-info
+ XXX.entity.ambient.AmbientCreature
- XXX.entity.ambient.Bat
+ XXX.entity.ambient.package-info
- XXX.entity.animal.AbstractFish
+ XXX.entity.animal.AbstractFish$FishMoveControl
- XXX.entity.animal.AbstractFish$FishSwimGoal
+ XXX.entity.animal.AbstractGolem
- XXX.entity.animal.AbstractSchoolingFish
+ XXX.entity.animal.AbstractSchoolingFish$SchoolSpawnGroupData
- XXX.entity.animal.Animal
+ XXX.entity.animal.Bee
- XXX.entity.animal.Bee$1
+ XXX.entity.animal.Bee$BaseBeeGoal
- XXX.entity.animal.Bee$BeeAttackGoal
+ XXX.entity.animal.Bee$BeeBecomeAngryTargetGoal
- XXX.entity.animal.Bee$BeeEnterHiveGoal
+ XXX.entity.animal.Bee$BeeGoToHiveGoal
- XXX.entity.animal.Bee$BeeGoToKnownFlowerGoal
+ XXX.entity.animal.Bee$BeeGrowCropGoal
- XXX.entity.animal.Bee$BeeHurtByOtherGoal
+ XXX.entity.animal.Bee$BeeLocateHiveGoal
- XXX.entity.animal.Bee$BeeLookControl
+ XXX.entity.animal.Bee$BeePollinateGoal
- XXX.entity.animal.Bee$BeeWanderGoal
- XXX.entity.animal.Bee$FloatDownGoal
- XXX.entity.animal.MoonCow
+ XXX.entity.item.package-info
- XXX.entity.item.PrimedTnt
- XXX.entity.monster.AbstractIllager
+ XXX.entity.monster.AbstractIllager$IllagerArmPose
- XXX.entity.monster.AbstractIllager$RaiderOpenDoorGoal
+ XXX.entity.monster.AbstractSkeleton
- XXX.entity.monster.AbstractSkeleton$1
+ XXX.entity.monster.Blaze
- XXX.entity.monster.Blaze$BlazeAttackGoal
+ XXX.entity.monster.CaveSpider
- XXX.entity.monster.Creeper
+ XXX.entity.monster.CrossbowAttackMob
- XXX.entity.monster.Drowned
+ XXX.entity.monster.Drowned$DrownedAttackGoal
- XXX.entity.monster.Drowned$DrownedGoToBeachGoal
+ XXX.entity.monster.Drowned$DrownedGoToWaterGoal
- XXX.entity.monster.Drowned$DrownedMoveControl
+ XXX.entity.monster.Drowned$DrownedSwimUpGoal
- XXX.entity.monster.Drowned$DrownedTridentAttackGoal
+ XXX.entity.monster.ElderGuardian
- XXX.entity.monster.EnderMan
+ XXX.entity.monster.EnderMan$EndermanFreezeWhenLookedAt
- XXX.entity.monster.EnderMan$EndermanLeaveBlockGoal
+ XXX.entity.monster.EnderMan$EndermanLookForPlayerGoal
- XXX.entity.monster.EnderMan$EndermanTakeBlockGoal
+ XXX.entity.monster.Endermite
- XXX.entity.monster.Enemy
+ XXX.entity.monster.Evoker
- XXX.entity.monster.Evoker$EvokerAttackSpellGoal
+ XXX.entity.monster.Evoker$EvokerCastingSpellGoal
- XXX.entity.monster.Evoker$EvokerSummonSpellGoal
+ XXX.entity.monster.Evoker$EvokerWololoSpellGoal
- XXX.entity.monster.Ghast
+ XXX.entity.monster.Ghast$GhastLookGoal
- XXX.entity.monster.Ghast$GhastMoveControl
+ XXX.entity.monster.Ghast$GhastShootFireballGoal
- XXX.entity.monster.Ghast$RandomFloatAroundGoal
+ XXX.entity.monster.Giant
- XXX.entity.monster.Guardian
+ XXX.entity.monster.Guardian$GuardianAttackGoal
- XXX.entity.monster.Guardian$GuardianAttackSelector
+ XXX.entity.monster.Guardian$GuardianMoveControl
- XXX.entity.monster.Husk
+ XXX.entity.monster.Illusioner
- XXX.entity.monster.Illusioner$IllusionerBlindnessSpellGoal
+ XXX.entity.monster.Illusioner$IllusionerMirrorSpellGoal
- XXX.entity.monster.MagmaCube
+ XXX.entity.monster.Monster
- XXX.entity.monster.package-info
- XXX.entity.monster.PatrollingMonster
+ XXX.entity.monster.PatrollingMonster$LongDistancePatrolGoal
- XXX.entity.monster.Phantom
+ XXX.entity.monster.Phantom$AttackPhase
- XXX.entity.monster.Phantom$PhantomAttackPlayerTargetGoal
+ XXX.entity.monster.Phantom$PhantomAttackStrategyGoal
- XXX.entity.monster.Phantom$PhantomBodyRotationControl
+ XXX.entity.monster.Phantom$PhantomCircleAroundAnchorGoal
- XXX.entity.monster.Phantom$PhantomLookControl
+ XXX.entity.monster.Phantom$PhantomMoveControl
- XXX.entity.monster.Phantom$PhantomMoveTargetGoal
+ XXX.entity.monster.Phantom$PhantomSweepAttackGoal
- XXX.entity.monster.Pillager
+ XXX.entity.monster.RangedAttackMob
- XXX.entity.monster.Ravager
+ XXX.entity.monster.Ravager$RavagerMeleeAttackGoal
- XXX.entity.monster.RayTracing
- XXX.entity.monster.Zombie$ZombieAttackTurtleEggGoal
+ XXX.entity.monster.Zombie$ZombieGroupData
- XXX.entity.monster.ZombieVillager
+ XXX.entity.monster.ZombifiedPiglin
+ XXX.entity.npc.AbstractVillager
- XXX.entity.npc.CatSpawner
+ XXX.entity.npc.ClientSideMerchant
- XXX.entity.npc.InventoryCarrier
+ XXX.entity.npc.Npc
- XXX.entity.npc.package-info
- XXX.entity.npc.Villager
+ XXX.entity.npc.VillagerData
- XXX.entity.npc.VillagerDataHolder
+ XXX.entity.npc.VillagerProfession
- XXX.entity.npc.VillagerTrades
+ XXX.entity.npc.VillagerTrades$DyedArmorForEmeralds
- XXX.entity.npc.VillagerTrades$EmeraldForItems
+ XXX.entity.npc.VillagerTrades$EmeraldsForVillagerTypeItem
- XXX.entity.npc.VillagerTrades$EnchantBookForEmeralds
+ XXX.entity.npc.VillagerTrades$EnchantedItemForEmeralds
- XXX.entity.npc.VillagerTrades$ItemListing
+ XXX.entity.npc.VillagerTrades$ItemsAndEmeraldsToItems
- XXX.entity.npc.VillagerTrades$ItemsForEmeralds
+ XXX.entity.npc.VillagerTrades$SuspiciousStewForEmerald
- XXX.entity.npc.VillagerTrades$TippedArrowForItemsAndEmeralds
+ XXX.entity.npc.VillagerTrades$TreasureMapForEmeralds
- XXX.entity.npc.VillagerType
+ XXX.entity.npc.WanderingTrader
- XXX.entity.npc.WanderingTrader$WanderToPositionGoal
+ XXX.entity.npc.WanderingTraderSpawner
- XXX.entity.player.Abilities
+ XXX.entity.player.ChatVisiblity
- XXX.entity.player.Inventory
+ XXX.entity.player.package-info
+ XXX.entity.player.Player
- XXX.entity.player.Player$1
+ XXX.entity.player.Player$BedSleepingProblem
- XXX.entity.player.PlayerModelPart
+ XXX.entity.player.ProfileKeyPair
- XXX.entity.player.ProfilePublicKey
+ XXX.entity.player.ProfilePublicKey$Data
- XXX.entity.player.ProfilePublicKey$ValidationException
+ XXX.entity.player.StackedContents
- XXX.entity.player.StackedContents$RecipePicker
- XXX.entity.projectile.AbstractArrow
+ XXX.entity.projectile.AbstractArrow$1
- XXX.entity.projectile.AbstractArrow$Pickup
+ XXX.entity.projectile.AbstractHurtingProjectile
- XXX.entity.projectile.Arrow
+ XXX.entity.projectile.DragonFireball
- XXX.entity.projectile.EvokerFangs
+ XXX.entity.projectile.EyeOfEnder
- XXX.entity.projectile.Fireball
+ XXX.entity.projectile.FireworkRocketEntity
- XXX.entity.projectile.FishingHook
+ XXX.entity.projectile.FishingHook$1
- XXX.entity.projectile.FishingHook$FishHookState
+ XXX.entity.projectile.FishingHook$OpenWaterType
- XXX.entity.projectile.ItemSupplier
+ XXX.entity.projectile.LargeFireball
- XXX.entity.projectile.LlamaSpit
+ XXX.entity.projectile.package-info
+ XXX.entity.projectile.Projectile
- XXX.entity.projectile.ProjectileUtil
+ XXX.entity.projectile.ShulkerBullet
- XXX.entity.projectile.SmallFireball
+ XXX.entity.projectile.Snowball
- XXX.entity.projectile.SpectralArrow
+ XXX.entity.projectile.ThrowableItemProjectile
- XXX.entity.projectile.ThrowableProjectile
+ XXX.entity.projectile.ThrownEgg
- XXX.entity.projectile.ThrownEnderpearl
+ XXX.entity.projectile.ThrownExperienceBottle
- XXX.entity.projectile.ThrownPotion
+ XXX.entity.projectile.ThrownTrident
- XXX.entity.projectile.WitherSkull
- XXX.entity.raid.package-info
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
+ XXX.entity.schedule.Activity
- XXX.entity.schedule.Keyframe
+ XXX.entity.schedule.package-info
+ XXX.entity.schedule.Schedule
- XXX.entity.schedule.ScheduleBuilder
+ XXX.entity.schedule.ScheduleBuilder$ActivityTransition
- XXX.entity.schedule.Timeline
- XXX.entity.transform.EntityTransform
- XXX.entity.transform.EntityTransformType$TypeModifier
- XXX.entity.transform.package-info
- XXX.feature.configurations.BlockColumnConfiguration
+ XXX.feature.configurations.BlockColumnConfiguration$Layer
- XXX.feature.configurations.BlockPileConfiguration
+ XXX.feature.configurations.BlockStateConfiguration
- XXX.feature.configurations.ColumnFeatureConfiguration
+ XXX.feature.configurations.CountConfiguration
- XXX.feature.configurations.CraterFeatureConfiguration
- XXX.gametest.framework.AfterBatch
+ XXX.gametest.framework.BeforeBatch
- XXX.gametest.framework.ExhaustedAttemptsException
+ XXX.gametest.framework.GameTest
- XXX.gametest.framework.GameTestAssertException
+ XXX.gametest.framework.GameTestAssertPosException
- XXX.gametest.framework.GameTestBatch
+ XXX.gametest.framework.GameTestBatchRunner
- XXX.gametest.framework.GameTestBatchRunner$1
+ XXX.gametest.framework.GameTestEvent
- XXX.gametest.framework.GameTestGenerator
+ XXX.gametest.framework.GameTestHelper
- XXX.gametest.framework.GameTestHelper$1
+ XXX.gametest.framework.GameTestHelper$2
- XXX.gametest.framework.GameTestInfo
+ XXX.gametest.framework.GameTestListener
- XXX.gametest.framework.GameTestRegistry
+ XXX.gametest.framework.GameTestRunner
- XXX.gametest.framework.GameTestSequence
+ XXX.gametest.framework.GameTestSequence$Condition
- XXX.gametest.framework.GameTestServer
+ XXX.gametest.framework.GameTestServer$1
- XXX.gametest.framework.GameTestTicker
+ XXX.gametest.framework.GameTestTimeoutException
- XXX.gametest.framework.GlobalTestReporter
+ XXX.gametest.framework.JUnitLikeTestReporter
- XXX.gametest.framework.LogTestReporter
+ XXX.gametest.framework.MultipleTestTracker
- XXX.gametest.framework.MultipleTestTracker$1
+ XXX.gametest.framework.package-info
+ XXX.gametest.framework.ReportGameListener
- XXX.gametest.framework.StructureUtils
+ XXX.gametest.framework.StructureUtils$1
- XXX.gametest.framework.TeamcityTestReporter
+ XXX.gametest.framework.TestClassNameArgument
- XXX.gametest.framework.TestCommand
+ XXX.gametest.framework.TestCommand$TestSummaryDisplayer
- XXX.gametest.framework.TestFunction
+ XXX.gametest.framework.TestFunctionArgument
- XXX.gametest.framework.TestReporter
- XXX.goal.target.DefendVillageTargetGoal
+ XXX.goal.target.HurtByTargetGoal
- XXX.goal.target.NearestAttackableTargetGoal
+ XXX.goal.target.NearestAttackableWitchTargetGoal
- XXX.goal.target.NearestHealableRaiderTargetGoal
+ XXX.goal.target.NonTameRandomTargetGoal
- XXX.goal.target.OwnerHurtByTargetGoal
+ XXX.goal.target.OwnerHurtTargetGoal
- XXX.goal.target.package-info
- XXX.goal.target.ResetUniversalAngerTargetGoal
+ XXX.goal.target.TargetGoal
- XXX.inventory.tooltip.BundleTooltip
- XXX.inventory.tooltip.package-info
+ XXX.inventory.tooltip.TooltipComponent
+ XXX.item.context.package-info
- XXX.item.context.UseOnContext
- XXX.item.crafting.AbstractCookingRecipe
+ XXX.item.crafting.ArmorDyeRecipe
- XXX.item.crafting.BannerDuplicateRecipe
+ XXX.item.crafting.BlastingRecipe
- XXX.item.crafting.BookCloningRecipe
+ XXX.item.crafting.CampfireCookingRecipe
- XXX.item.crafting.CookingBookCategory
+ XXX.item.crafting.CraftingBookCategory
- XXX.item.crafting.CraftingRecipe
+ XXX.item.crafting.CustomRecipe
- XXX.item.crafting.DecoratedPotRecipe
+ XXX.item.crafting.package-info
- XXX.item.crafting.Recipe
+ XXX.item.crafting.RecipeManager
- XXX.item.crafting.RecipeManager$1
+ XXX.item.crafting.RecipeManager$CachedCheck
- XXX.item.crafting.RecipeSerializer
+ XXX.item.crafting.RecipeType
- XXX.item.crafting.RecipeType$1
+ XXX.item.crafting.RepairItemRecipe
- XXX.item.crafting.ShapedRecipe
+ XXX.item.crafting.ShapedRecipe$Serializer
- XXX.item.crafting.ShapelessRecipe
+ XXX.item.crafting.ShapelessRecipe$Serializer
- XXX.item.crafting.ShieldDecorationRecipe
+ XXX.item.crafting.ShulkerBoxColoring
- XXX.item.crafting.SimpleCookingSerializer
+ XXX.item.crafting.SimpleCookingSerializer$CookieBaker
- XXX.item.crafting.SimpleCraftingRecipeSerializer
+ XXX.item.crafting.SimpleCraftingRecipeSerializer$Factory
- XXX.item.crafting.SingleItemRecipe
+ XXX.item.crafting.SingleItemRecipe$Serializer
- XXX.item.crafting.SingleItemRecipe$Serializer$SingleItemMaker
+ XXX.item.crafting.SmeltingRecipe
- XXX.item.crafting.SmithingRecipe
+ XXX.item.crafting.SmithingTransformRecipe
- XXX.item.crafting.SmithingTransformRecipe$Serializer
+ XXX.item.crafting.SmithingTrimRecipe
- XXX.item.crafting.SmithingTrimRecipe$Serializer
+ XXX.item.crafting.SmokingRecipe
- XXX.item.crafting.StonecutterRecipe
+ XXX.item.crafting.SuspiciousStewRecipe
- XXX.item.crafting.TippedArrowRecipe
- XXX.item.enchantment.ArrowDamageEnchantment
+ XXX.item.enchantment.ArrowFireEnchantment
- XXX.item.enchantment.ArrowInfiniteEnchantment
+ XXX.item.enchantment.ArrowKnockbackEnchantment
- XXX.item.enchantment.ArrowPiercingEnchantment
+ XXX.item.enchantment.BindingCurseEnchantment
- XXX.item.enchantment.DamageEnchantment
+ XXX.item.enchantment.DigDurabilityEnchantment
- XXX.item.enchantment.DiggingEnchantment
+ XXX.item.enchantment.Enchantment
- XXX.item.enchantment.Enchantment$Rarity
+ XXX.item.enchantment.EnchantmentCategory
- XXX.item.enchantment.EnchantmentCategory$1
+ XXX.item.enchantment.EnchantmentCategory$10
- XXX.item.enchantment.EnchantmentCategory$11
+ XXX.item.enchantment.EnchantmentCategory$12
- XXX.item.enchantment.EnchantmentCategory$13
+ XXX.item.enchantment.EnchantmentCategory$14
- XXX.item.enchantment.EnchantmentCategory$2
+ XXX.item.enchantment.EnchantmentCategory$3
- XXX.item.enchantment.EnchantmentCategory$4
+ XXX.item.enchantment.EnchantmentCategory$5
- XXX.item.enchantment.EnchantmentCategory$6
+ XXX.item.enchantment.EnchantmentCategory$7
- XXX.item.enchantment.EnchantmentCategory$8
+ XXX.item.enchantment.EnchantmentCategory$9
- XXX.item.enchantment.EnchantmentHelper
+ XXX.item.enchantment.EnchantmentHelper$EnchantmentVisitor
- XXX.item.enchantment.EnchantmentInstance
+ XXX.item.enchantment.Enchantments
- XXX.item.enchantment.FireAspectEnchantment
+ XXX.item.enchantment.FishingSpeedEnchantment
- XXX.item.enchantment.FrostWalkerEnchantment
+ XXX.item.enchantment.KnockbackEnchantment
- XXX.item.enchantment.LootBonusEnchantment
+ XXX.item.enchantment.MendingEnchantment
- XXX.item.enchantment.MultiShotEnchantment
+ XXX.item.enchantment.OxygenEnchantment
+ XXX.item.enchantment.package-info
- XXX.item.enchantment.ProtectionEnchantment
+ XXX.item.enchantment.ProtectionEnchantment$Type
- XXX.item.enchantment.QuickChargeEnchantment
+ XXX.item.enchantment.SoulSpeedEnchantment
- XXX.item.enchantment.SweepingEdgeEnchantment
+ XXX.item.enchantment.SwiftSneakEnchantment
- XXX.item.enchantment.ThornsEnchantment
+ XXX.item.enchantment.TridentChannelingEnchantment
- XXX.item.enchantment.TridentImpalerEnchantment
+ XXX.item.enchantment.TridentLoyaltyEnchantment
- XXX.item.enchantment.TridentRiptideEnchantment
+ XXX.item.enchantment.UntouchingEnchantment
- XXX.item.enchantment.VanishingCurseEnchantment
+ XXX.item.enchantment.WaterWalkerEnchantment
- XXX.item.enchantment.WaterWorkerEnchantment
+ XXX.item.trading.Merchant
- XXX.item.trading.MerchantOffer
+ XXX.item.trading.MerchantOffers
- XXX.item.trading.package-info
- XXX.jfr.callback.package-info
+ XXX.jfr.callback.ProfiledDuration
+ XXX.jfr.event.ChunkGenerationEvent
- XXX.jfr.event.ChunkGenerationEvent$Fields
+ XXX.jfr.event.NetworkSummaryEvent
- XXX.jfr.event.NetworkSummaryEvent$Fields
+ XXX.jfr.event.NetworkSummaryEvent$SumAggregation
+ XXX.jfr.event.package-info
- XXX.jfr.event.PacketEvent
+ XXX.jfr.event.PacketEvent$Fields
- XXX.jfr.event.PacketReceivedEvent
+ XXX.jfr.event.PacketSentEvent
- XXX.jfr.event.ServerTickTimeEvent
+ XXX.jfr.event.ServerTickTimeEvent$Fields
- XXX.jfr.event.WorldLoadFinishedEvent
+ XXX.jfr.parse.JfrStatsParser
- XXX.jfr.parse.JfrStatsParser$1
+ XXX.jfr.parse.JfrStatsParser$MutableCountAndSize
- XXX.jfr.parse.JfrStatsResult
+ XXX.jfr.parse.package-info
- XXX.jfr.serialize.JfrResultJsonSerializer
+ XXX.jfr.serialize.package-info
- XXX.jfr.stats.ChunkGenStat
+ XXX.jfr.stats.CpuLoadStat
- XXX.jfr.stats.FileIOStat
+ XXX.jfr.stats.FileIOStat$Summary
- XXX.jfr.stats.GcHeapStat
+ XXX.jfr.stats.GcHeapStat$Summary
- XXX.jfr.stats.GcHeapStat$Timing
+ XXX.jfr.stats.NetworkPacketSummary
- XXX.jfr.stats.NetworkPacketSummary$PacketCountAndSize
+ XXX.jfr.stats.NetworkPacketSummary$PacketIdentification
- XXX.jfr.stats.package-info
- XXX.jfr.stats.ThreadAllocationStat
+ XXX.jfr.stats.ThreadAllocationStat$Summary
- XXX.jfr.stats.TickTimeStat
- XXX.jfr.stats.TimedStat
+ XXX.jfr.stats.TimedStatSummary
+ XXX.jfr.stats.TimeStamped
- XXX.level.biome.AmbientAdditionsSettings
+ XXX.level.biome.AmbientMoodSettings
- XXX.level.biome.AmbientParticleSettings
+ XXX.level.biome.Biome
- XXX.level.biome.Biome$1
+ XXX.level.biome.Biome$BiomeBuilder
- XXX.level.biome.Biome$ClimateSettings
+ XXX.level.biome.Biome$Precipitation
- XXX.level.biome.Biome$TemperatureModifier
+ XXX.level.biome.Biome$TemperatureModifier$1
- XXX.level.biome.Biome$TemperatureModifier$2
+ XXX.level.biome.BiomeGenerationSettings
- XXX.level.biome.BiomeGenerationSettings$Builder
+ XXX.level.biome.BiomeGenerationSettings$PlainBuilder
- XXX.level.biome.BiomeManager
+ XXX.level.biome.BiomeManager$NoiseBiomeSource
- XXX.level.biome.BiomeResolver
+ XXX.level.biome.Biomes
+ XXX.level.biome.BiomeSource
- XXX.level.biome.BiomeSources
+ XXX.level.biome.BiomeSpecialEffects
- XXX.level.biome.BiomeSpecialEffects$Builder
+ XXX.level.biome.BiomeSpecialEffects$GrassColorModifier
- XXX.level.biome.BiomeSpecialEffects$GrassColorModifier$1
+ XXX.level.biome.BiomeSpecialEffects$GrassColorModifier$2
- XXX.level.biome.BiomeSpecialEffects$GrassColorModifier$3
- XXX.level.biome.CheckerboardColumnBiomeSource
+ XXX.level.biome.Climate
- XXX.level.biome.Climate$DistanceMetric
+ XXX.level.biome.Climate$Parameter
- XXX.level.biome.Climate$ParameterList
+ XXX.level.biome.Climate$ParameterPoint
- XXX.level.biome.Climate$RTree
+ XXX.level.biome.Climate$RTree$Leaf
- XXX.level.biome.Climate$RTree$Node
+ XXX.level.biome.Climate$RTree$SubTree
- XXX.level.biome.Climate$Sampler
+ XXX.level.biome.Climate$SpawnFinder
- XXX.level.biome.Climate$SpawnFinder$Result
+ XXX.level.biome.Climate$TargetPoint
- XXX.level.biome.FeatureSorter
+ XXX.level.biome.FeatureSorter$1FeatureData
- XXX.level.biome.FeatureSorter$StepFeatureData
+ XXX.level.biome.FixedBiomeSource
- XXX.level.biome.MobSpawnSettings
+ XXX.level.biome.MobSpawnSettings$Builder
- XXX.level.biome.MobSpawnSettings$MobSpawnCost
+ XXX.level.biome.MobSpawnSettings$SpawnerData
- XXX.level.biome.MultiNoiseBiomeSource
+ XXX.level.biome.MultiNoiseBiomeSourceParameterList
- XXX.level.biome.MultiNoiseBiomeSourceParameterList$Preset
+ XXX.level.biome.MultiNoiseBiomeSourceParameterList$Preset$1
- XXX.level.biome.MultiNoiseBiomeSourceParameterList$Preset$2
+ XXX.level.biome.MultiNoiseBiomeSourceParameterList$Preset$SourceProvider
- XXX.level.biome.MultiNoiseBiomeSourceParameterLists
+ XXX.level.biome.OverworldBiomeBuilder
- XXX.level.biome.TheEndBiomeSource
- XXX.level.block.CherryLeavesBlock
+ XXX.level.block.ChestBlock
- XXX.level.block.ChestBlock$1
+ XXX.level.block.ChestBlock$2
- XXX.level.block.ChestBlock$2$1
+ XXX.level.block.ChestBlock$3
- XXX.level.block.ChestBlock$4
+ XXX.level.block.ChiseledBookShelfBlock
- XXX.level.block.ChiseledBookShelfBlock$1
+ XXX.level.block.ChorusFlowerBlock
- XXX.level.block.ChorusPlantBlock
+ XXX.level.block.CocoaBlock
- XXX.level.block.CocoaBlock$1
+ XXX.level.block.CommandBlock
- XXX.level.block.ComparatorBlock
+ XXX.level.block.ComposterBlock
- XXX.level.block.ComposterBlock$EmptyContainer
+ XXX.level.block.ComposterBlock$InputContainer
- XXX.level.block.ComposterBlock$OutputContainer
+ XXX.level.block.ConcretePowderBlock
- XXX.level.block.ConduitBlock
- XXX.level.block.Fallable
+ XXX.level.block.FallingBlock
- XXX.level.block.FarmBlock
+ XXX.level.block.FenceBlock
- XXX.level.block.FenceGateBlock
+ XXX.level.block.FenceGateBlock$1
- XXX.level.block.FilledCopperSinkBlock
- XXX.level.block.PackedAirBlock
- XXX.level.block.PlaceBlock
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
- XXX.level.block.SpleavesBlock
- XXX.level.levelgen.MoonBaseBuilder
- XXX.level.levelgen.MoonBaseBuilder$Branch
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
- XXX.levelgen.feature.CraterFeature
- XXX.levelgen.feature.LunarBaseFeature
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
- XXX.minecraft.locale.Language
+ XXX.minecraft.locale.Language$1
- XXX.minecraft.locale.package-info
+ XXX.minecraft.nbt.ByteArrayTag
- XXX.minecraft.nbt.ByteArrayTag$1
+ XXX.minecraft.nbt.ByteTag
- XXX.minecraft.nbt.ByteTag$1
+ XXX.minecraft.nbt.ByteTag$Cache
- XXX.minecraft.nbt.CollectionTag
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
- XXX.minecraft.nbt.NbtAccounter$1
+ XXX.minecraft.nbt.NbtIo
- XXX.minecraft.nbt.NbtIo$1
+ XXX.minecraft.nbt.NbtOps
- XXX.minecraft.nbt.NbtOps$1
+ XXX.minecraft.nbt.NbtOps$ByteListCollector
- XXX.minecraft.nbt.NbtOps$HeterogenousListCollector
+ XXX.minecraft.nbt.NbtOps$HomogenousListCollector
- XXX.minecraft.nbt.NbtOps$InitialListCollector
+ XXX.minecraft.nbt.NbtOps$IntListCollector
- XXX.minecraft.nbt.NbtOps$ListCollector
+ XXX.minecraft.nbt.NbtOps$LongListCollector
- XXX.minecraft.nbt.NbtOps$NbtRecordBuilder
+ XXX.minecraft.nbt.NbtUtils
- XXX.minecraft.nbt.NumericTag
+ XXX.minecraft.nbt.package-info
+ XXX.minecraft.nbt.ShortTag
- XXX.minecraft.nbt.ShortTag$1
+ XXX.minecraft.nbt.ShortTag$Cache
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
- XXX.minecraft.network.CipherBase
+ XXX.minecraft.network.CipherDecoder
- XXX.minecraft.network.CipherEncoder
+ XXX.minecraft.network.CompressionDecoder
- XXX.minecraft.network.CompressionEncoder
+ XXX.minecraft.network.Connection
- XXX.minecraft.network.Connection$1
+ XXX.minecraft.network.Connection$2
- XXX.minecraft.network.Connection$PacketHolder
+ XXX.minecraft.network.ConnectionProtocol
- XXX.minecraft.network.ConnectionProtocol$PacketSet
+ XXX.minecraft.network.ConnectionProtocol$ProtocolBuilder
- XXX.minecraft.network.FriendlyByteBuf
+ XXX.minecraft.network.FriendlyByteBuf$1
- XXX.minecraft.network.FriendlyByteBuf$Reader
+ XXX.minecraft.network.FriendlyByteBuf$Writer
- XXX.minecraft.network.package-info
- XXX.minecraft.network.PacketBundlePacker
+ XXX.minecraft.network.PacketBundleUnpacker
- XXX.minecraft.network.PacketDecoder
+ XXX.minecraft.network.PacketEncoder
- XXX.minecraft.network.PacketListener
+ XXX.minecraft.network.PacketSendListener
- XXX.minecraft.network.PacketSendListener$1
+ XXX.minecraft.network.PacketSendListener$2
- XXX.minecraft.network.RateKickingConnection
+ XXX.minecraft.network.SkipPacketException
- XXX.minecraft.network.TickablePacketListener
+ XXX.minecraft.network.Varint21FrameDecoder
- XXX.minecraft.network.Varint21LengthFieldPrepender
- XXX.minecraft.obfuscate.DontObfuscate
+ XXX.minecraft.obfuscate.package-info
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
- XXX.minecraft.util.package-info
- XXX.minecraft.util.RgbTxt
- XXX.minecraft.voting.VoteCommand$1
+ XXX.monitoring.jmx.MinecraftServerStatistics
- XXX.monitoring.jmx.MinecraftServerStatistics$AttributeDescription
+ XXX.monitoring.jmx.package-info
- XXX.monster.hoglin.Hoglin
+ XXX.monster.hoglin.HoglinAi
- XXX.monster.hoglin.HoglinBase
+ XXX.monster.hoglin.package-info
+ XXX.monster.piglin.AbstractPiglin
+ XXX.monster.piglin.package-info
- XXX.monster.piglin.Piglin
+ XXX.monster.piglin.PiglinAi
- XXX.monster.piglin.PiglinArmPose
+ XXX.monster.piglin.PiglinBrute
- XXX.monster.piglin.PiglinBruteAi
+ XXX.monster.piglin.RememberIfHoglinWasKilled
- XXX.monster.piglin.StartAdmiringItemIfSeen
+ XXX.monster.piglin.StartHuntingHoglin
- XXX.monster.piglin.StopAdmiringIfItemTooFarAway
+ XXX.monster.piglin.StopAdmiringIfTiredOfTryingToReachItem
- XXX.monster.piglin.StopHoldingItemIfNoLongerAdmiring
- XXX.monster.warden.AngerLevel
+ XXX.monster.warden.AngerManagement
- XXX.monster.warden.AngerManagement$1
+ XXX.monster.warden.AngerManagement$Sorter
- XXX.monster.warden.package-info
- XXX.monster.warden.Warden
+ XXX.monster.warden.Warden$1
- XXX.monster.warden.Warden$1$1
+ XXX.monster.warden.Warden$2
- XXX.monster.warden.WardenAi
+ XXX.monster.warden.WardenSpawnTracker
- XXX.nbt.visitors.CollectFields
+ XXX.nbt.visitors.CollectToTag
- XXX.nbt.visitors.FieldSelector
+ XXX.nbt.visitors.FieldTree
+ XXX.nbt.visitors.package-info
- XXX.nbt.visitors.SkipAll
+ XXX.nbt.visitors.SkipAll$1
- XXX.nbt.visitors.SkipFields
+ XXX.network.chat.ChatDecorator
- XXX.network.chat.ChatType
+ XXX.network.chat.ChatType$Bound
- XXX.network.chat.ChatType$BoundNetwork
+ XXX.network.chat.ChatTypeDecoration
- XXX.network.chat.ChatTypeDecoration$Parameter
+ XXX.network.chat.ChatTypeDecoration$Parameter$Selector
- XXX.network.chat.ClickEvent
+ XXX.network.chat.ClickEvent$Action
- XXX.network.chat.CommonComponents
+ XXX.network.chat.Component
- XXX.network.chat.Component$Serializer
+ XXX.network.chat.ComponentContents
- XXX.network.chat.ComponentContents$1
+ XXX.network.chat.ComponentUtils
- XXX.network.chat.FilterMask
+ XXX.network.chat.FilterMask$1
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
+ XXX.network.chat.HoverEvent$ItemStackInfo
- XXX.network.chat.LastSeenMessages
+ XXX.network.chat.LastSeenMessages$Packed
- XXX.network.chat.LastSeenMessages$Update
+ XXX.network.chat.LastSeenMessagesTracker
- XXX.network.chat.LastSeenMessagesTracker$Update
+ XXX.network.chat.LastSeenMessagesValidator
- XXX.network.chat.LastSeenTrackedEntry
+ XXX.network.chat.LocalChatSession
- XXX.network.chat.MessageSignature
+ XXX.network.chat.MessageSignature$Packed
- XXX.network.chat.MessageSignatureCache
+ XXX.network.chat.MutableComponent
- XXX.network.chat.OutgoingChatMessage
+ XXX.network.chat.OutgoingChatMessage$Disguised
- XXX.network.chat.OutgoingChatMessage$Player
+ XXX.network.chat.package-info
+ XXX.network.chat.PlayerChatMessage
- XXX.network.chat.RemoteChatSession
+ XXX.network.chat.RemoteChatSession$Data
- XXX.network.chat.SignableCommand
+ XXX.network.chat.SignableCommand$Argument
- XXX.network.chat.SignedMessageBody
+ XXX.network.chat.SignedMessageBody$Packed
- XXX.network.chat.SignedMessageChain
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
+ XXX.network.protocol.BundleDelimiterPacket
- XXX.network.protocol.BundlePacket
+ XXX.network.protocol.BundlerInfo
- XXX.network.protocol.BundlerInfo$1
+ XXX.network.protocol.BundlerInfo$2
- XXX.network.protocol.BundlerInfo$2$1
+ XXX.network.protocol.BundlerInfo$Bundler
- XXX.network.protocol.BundlerInfo$Provider
- XXX.network.protocol.package-info
+ XXX.network.protocol.Packet
- XXX.network.protocol.PacketFlow
+ XXX.network.protocol.PacketUtils
- XXX.network.syncher.EntityDataAccessor
+ XXX.network.syncher.EntityDataSerializer
- XXX.network.syncher.EntityDataSerializer$1
+ XXX.network.syncher.EntityDataSerializer$ForValueType
- XXX.network.syncher.EntityDataSerializers
+ XXX.network.syncher.EntityDataSerializers$1
- XXX.network.syncher.EntityDataSerializers$2
+ XXX.network.syncher.EntityDataSerializers$3
- XXX.network.syncher.EntityDataSerializers$4
+ XXX.network.syncher.EntityDataSerializers$5
- XXX.network.syncher.EntityDataSerializers$6
+ XXX.network.syncher.EntityDataSerializers$7
+ XXX.network.syncher.package-info
- XXX.network.syncher.SynchedEntityData
+ XXX.network.syncher.SynchedEntityData$DataItem
- XXX.network.syncher.SynchedEntityData$DataValue
- XXX.profiling.jfr.Environment
+ XXX.profiling.jfr.JfrProfiler
- XXX.profiling.jfr.JfrProfiler$1
+ XXX.profiling.jfr.JvmProfiler
- XXX.profiling.jfr.JvmProfiler$NoOpProfiler
- XXX.profiling.jfr.package-info
+ XXX.profiling.jfr.Percentiles
- XXX.profiling.jfr.SummaryReporter
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
+ XXX.protocol.game.ClientboundAddEntityPacket
- XXX.protocol.game.ClientboundAddExperienceOrbPacket
+ XXX.protocol.game.ClientboundAddPlayerPacket
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
- XXX.protocol.game.ClientboundSetCarriedItemPacket
+ XXX.protocol.game.ClientboundSetChunkCacheCenterPacket
- XXX.protocol.game.ClientboundSetChunkCacheRadiusPacket
+ XXX.protocol.game.ClientboundSetDefaultSpawnPositionPacket
- XXX.protocol.game.ClientboundSetDisplayObjectivePacket
+ XXX.protocol.game.ClientboundSetEntityDataPacket
- XXX.protocol.game.ClientboundSetEntityLinkPacket
+ XXX.protocol.game.ClientboundSetEntityMotionPacket
- XXX.protocol.game.ClientboundSetEquipmentPacket
+ XXX.protocol.game.ClientboundSetExperiencePacket
- XXX.protocol.game.ClientboundSetHealthPacket
+ XXX.protocol.game.ClientboundSetObjectivePacket
- XXX.protocol.game.ClientboundSetPassengersPacket
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
- XXX.protocol.game.ClientboundStopSoundPacket
+ XXX.protocol.game.ClientboundSystemChatPacket
- XXX.protocol.game.ClientboundTabListPacket
+ XXX.protocol.game.ClientboundTagQueryPacket
- XXX.protocol.game.ClientboundTakeItemEntityPacket
+ XXX.protocol.game.ClientboundTeleportEntityPacket
- XXX.protocol.game.ClientboundUpdateAdvancementsPacket
+ XXX.protocol.game.ClientboundUpdateAttributesPacket
- XXX.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
+ XXX.protocol.game.ClientboundUpdateEnabledFeaturesPacket
- XXX.protocol.game.ClientboundUpdateMobEffectPacket
+ XXX.protocol.game.ClientboundUpdateRecipesPacket
- XXX.protocol.game.ClientboundUpdateTagsPacket
- XXX.protocol.game.ClientboundVoteFinishPacket
- XXX.protocol.game.ClientboundVoteStartPacket
- XXX.protocol.game.ClientGamePacketListener
+ XXX.protocol.game.DebugEntityNameGenerator
- XXX.protocol.game.DebugPackets
+ XXX.protocol.game.package-info
+ XXX.protocol.game.ServerboundAcceptTeleportationPacket
- XXX.protocol.game.ServerboundBlockEntityTagQuery
+ XXX.protocol.game.ServerboundChangeDifficultyPacket
- XXX.protocol.game.ServerboundChatAckPacket
+ XXX.protocol.game.ServerboundChatCommandPacket
- XXX.protocol.game.ServerboundChatPacket
+ XXX.protocol.game.ServerboundChatSessionUpdatePacket
- XXX.protocol.game.ServerboundClientCommandPacket
+ XXX.protocol.game.ServerboundClientCommandPacket$Action
- XXX.protocol.game.ServerboundClientInformationPacket
+ XXX.protocol.game.ServerboundCommandSuggestionPacket
- XXX.protocol.game.ServerboundContainerButtonClickPacket
+ XXX.protocol.game.ServerboundContainerClickPacket
- XXX.protocol.game.ServerboundContainerClosePacket
+ XXX.protocol.game.ServerGamePacketListener
- XXX.protocol.game.ServerPacketListener
- XXX.protocol.game.VecDeltaCodec
- XXX.protocol.handshake.ClientIntentionPacket
- XXX.protocol.handshake.package-info
+ XXX.protocol.handshake.ServerHandshakePacketListener
- XXX.protocol.login.ClientboundCustomQueryPacket
+ XXX.protocol.login.ClientboundGameProfilePacket
- XXX.protocol.login.ClientboundHelloPacket
+ XXX.protocol.login.ClientboundLoginCompressionPacket
- XXX.protocol.login.ClientboundLoginDisconnectPacket
+ XXX.protocol.login.ClientLoginPacketListener
+ XXX.protocol.login.package-info
- XXX.protocol.login.ServerboundCustomQueryPacket
+ XXX.protocol.login.ServerboundHelloPacket
- XXX.protocol.login.ServerboundKeyPacket
+ XXX.protocol.login.ServerLoginPacketListener
- XXX.protocol.status.ClientboundPongResponsePacket
+ XXX.protocol.status.ClientboundStatusResponsePacket
+ XXX.protocol.status.ClientStatusPacketListener
+ XXX.protocol.status.package-info
+ XXX.protocol.status.ServerboundPingRequestPacket
- XXX.protocol.status.ServerboundStatusRequestPacket
- XXX.protocol.status.ServerStatus
+ XXX.protocol.status.ServerStatus$Favicon
- XXX.protocol.status.ServerStatus$Players
+ XXX.protocol.status.ServerStatus$Version
- XXX.protocol.status.ServerStatusPacketListener
- XXX.rules.actual.BinaryGameRuleRule
- XXX.rules.actual.BiomeColorRule
- XXX.rules.actual.BlockFlammabilityRule$Flammability
- XXX.rules.actual.BlockModelReplacementRule
- XXX.rules.actual.BlockModelReplacementRule$Replacements
- XXX.rules.actual.CaepType
- XXX.rules.actual.CodepointReplaceRule
- XXX.rules.actual.CodepointStyleRule$CodepointChange
- XXX.rules.actual.CopySkinRule
- XXX.rules.actual.DayLengthRule
- XXX.rules.actual.DoubleOrHalfItemMapRule
- XXX.rules.actual.FlailingLevel
- XXX.rules.actual.FootprintRule
- XXX.rules.actual.GiveEffectRule$MobEffectEntry
- XXX.rules.actual.Goldifier$1
- XXX.rules.actual.IntegerGameRuleRule$RuleRuleChange
- XXX.rules.actual.ItemEntityDespawn
- XXX.rules.actual.ItemGiveRule$GiveItemRule
- XXX.rules.actual.ItemReplacementRule
- XXX.rules.actual.LightEngineMode
- XXX.rules.actual.MoonRule
- XXX.rules.actual.NaturalSpawnReplaceRule
- XXX.rules.actual.package-info
- XXX.rules.actual.ParentTrapRule
- XXX.rules.actual.PlayerEntry
- XXX.rules.actual.RecipeEnableRule
- XXX.rules.actual.ReplaceItemsRule
- XXX.rules.actual.ReplaceItemsRule$ReplaceRuleChange
- XXX.rules.actual.SoundEventReplacementRule
- XXX.rules.actual.TheJokeRule$1
- XXX.rules.actual.ThreadedAnvilChunkStorage$1
- XXX.rules.actual.TransformEntityRule
- XXX.rules.actual.TransformScaleRule
- XXX.rules.actual.VehicleCollisionRule
- XXX.rules.actual.WeatherOption
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
- XXX.server.level.ServerLevel$1
- XXX.util.eventlog.EventLogDirectory
+ XXX.util.eventlog.EventLogDirectory$CompressedFile
- XXX.util.eventlog.EventLogDirectory$File
+ XXX.util.eventlog.EventLogDirectory$FileId
- XXX.util.eventlog.EventLogDirectory$FileList
+ XXX.util.eventlog.EventLogDirectory$RawFile
- XXX.util.eventlog.JsonEventLog
+ XXX.util.eventlog.JsonEventLog$1
- XXX.util.eventlog.JsonEventLogReader
+ XXX.util.eventlog.JsonEventLogReader$1
- XXX.util.eventlog.package-info
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
- XXX.util.profiling.ProfileResults
+ XXX.util.profiling.ProfilerFiller
- XXX.util.profiling.ProfilerFiller$1
+ XXX.util.profiling.ProfilerPathEntry
- XXX.util.profiling.ResultField
+ XXX.util.profiling.SingleTickProfiler
- XXX.util.random.package-info
- XXX.util.random.SimpleWeightedRandomList
+ XXX.util.random.SimpleWeightedRandomList$Builder
- XXX.util.random.Weight
+ XXX.util.random.WeightedEntry
- XXX.util.random.WeightedEntry$IntrusiveBase
+ XXX.util.random.WeightedEntry$Wrapper
- XXX.util.random.WeightedRandom
+ XXX.util.random.WeightedRandomList
+ XXX.util.thread.BlockableEventLoop
- XXX.util.thread.NamedThreadFactory
+ XXX.util.thread.package-info
+ XXX.util.thread.ProcessorHandle
- XXX.util.thread.ProcessorHandle$1
+ XXX.util.thread.ProcessorMailbox
- XXX.util.thread.ReentrantBlockableEventLoop
+ XXX.util.thread.StrictQueue
- XXX.util.thread.StrictQueue$FixedPriorityQueue
+ XXX.util.thread.StrictQueue$IntRunnable
- XXX.util.thread.StrictQueue$QueueStrictQueue
- XXX.util.valueproviders.BiasedToBottomInt
+ XXX.util.valueproviders.ClampedInt
- XXX.util.valueproviders.ClampedNormalFloat
+ XXX.util.valueproviders.ClampedNormalInt
- XXX.util.valueproviders.ConstantFloat
+ XXX.util.valueproviders.ConstantInt
- XXX.util.valueproviders.FloatProvider
+ XXX.util.valueproviders.FloatProviderType
- XXX.util.valueproviders.IntProvider
+ XXX.util.valueproviders.IntProviderType
- XXX.util.valueproviders.MultipliedFloats
- XXX.util.valueproviders.package-info
+ XXX.util.valueproviders.SampledFloat
- XXX.util.valueproviders.TrapezoidFloat
+ XXX.util.valueproviders.UniformFloat
- XXX.util.valueproviders.UniformInt
+ XXX.util.valueproviders.WeightedListInt
- XXX.util.worldupdate.package-info
+ XXX.util.worldupdate.WorldUpgrader
- XXX.village.poi.package-info
+ XXX.village.poi.PoiManager
- XXX.village.poi.PoiManager$DistanceTracker
+ XXX.village.poi.PoiManager$Occupancy
- XXX.village.poi.PoiRecord
+ XXX.village.poi.PoiSection
- XXX.village.poi.PoiType
+ XXX.village.poi.PoiTypes
- XXX.voting.rules.BooleanRule
- XXX.voting.rules.CounterRule
- XXX.voting.rules.CounterRule$CounterRuleChange
- XXX.voting.rules.DoubleOrHalfMapRule
- XXX.voting.rules.EnumRule
- XXX.voting.rules.EnumRule$EnumRuleChange
- XXX.voting.rules.FixedOrRandomKeyRule$1
- XXX.voting.rules.MapRule
- XXX.voting.rules.MapRule$MapRuleChange
- XXX.voting.rules.OneShotRule$1
- XXX.voting.rules.OneShotRule$Resettable
- XXX.voting.rules.RandomNumberRule
- XXX.voting.rules.RandomNumberRule$RandomFloat
- XXX.voting.rules.RandomNumberRule$RandomNumberRuleChange
- XXX.voting.rules.ResourceKeySetRule
- XXX.voting.rules.ResourceKeySingleRule$1
- XXX.voting.rules.Rule
- XXX.voting.rules.RuleChange
- XXX.voting.rules.RuleChange$Simple
- XXX.voting.rules.Rules$1
- XXX.voting.rules.Rules$11
- XXX.voting.rules.Rules$13
- XXX.voting.rules.Rules$15
- XXX.voting.rules.Rules$17
- XXX.voting.rules.Rules$19
- XXX.voting.rules.Rules$20
- XXX.voting.rules.Rules$22
- XXX.voting.rules.Rules$24
- XXX.voting.rules.Rules$26
- XXX.voting.rules.Rules$28
- XXX.voting.rules.Rules$3
- XXX.voting.rules.Rules$31
- XXX.voting.rules.Rules$33
- XXX.voting.rules.Rules$35
- XXX.voting.rules.Rules$37
- XXX.voting.rules.Rules$39
- XXX.voting.rules.Rules$40
- XXX.voting.rules.Rules$42
- XXX.voting.rules.Rules$5
- XXX.voting.rules.Rules$7
- XXX.voting.rules.Rules$9
- XXX.voting.rules.SetRule$SetRuleChange
- XXX.voting.rules.UniformIntRule$1
- XXX.voting.rules.VotingCostRule
- XXX.voting.rules.VotingCostRule$Change
- XXX.voting.votes.ClientVote
- XXX.voting.votes.CommonVoteData
- XXX.voting.votes.FinishedVote$1
- XXX.voting.votes.FinishedVote$UnpackOptions
- XXX.voting.votes.OptionVoteStorage
- XXX.voting.votes.ServerVote
- XXX.voting.votes.ServerVote$Option
- XXX.voting.votes.ServerVoteStorage
- XXX.voting.votes.ServerVoteStorage$VoteResult
- XXX.voting.votes.Voter
- XXX.voting.votes.VoteResults
- XXX.voting.votes.VoteResults$VoteCounts
- XXX.voting.votes.VotingMaterial
- XXX.voting.votes.VotingMaterial$2
- XXX.voting.votes.VotingMaterial$CustomCost
- XXX.voting.votes.VotingMaterial$Type$1
- XXX.voting.votes.VotingMaterial$Type$3
- XXX.voting.votes.VotingMaterial$Type$5
- XXX.voting.votes.VotingMaterial$VotingResource
- XXX.voting.votes.VotingMaterial$VotingResource$2
- XXX.world.entity.Display$KeyFrame
+ XXX.world.entity.Display$LinearFloatInterpolator
- XXX.world.entity.Display$LinearIntInterpolator
- XXX.world.entity.Display$StencilDisplay$StencilRenderState
- XXX.world.entity.Entity$InPortal
+ XXX.world.entity.Entity$MoveFunction
- XXX.world.entity.Entity$MovementEmission
+ XXX.world.entity.Entity$RemovalReason
- XXX.world.entity.EntityDimensions
+ XXX.world.entity.EntityEvent
- XXX.world.entity.EntitySelector
+ XXX.world.entity.EntitySelector$MobCanWearArmorEntitySelector
- XXX.world.entity.EntityType
+ XXX.world.entity.EntityType$1
- XXX.world.entity.EntityType$Builder
+ XXX.world.entity.EntityType$EntityFactory
- XXX.world.entity.EquipmentSlot
+ XXX.world.entity.EquipmentSlot$Type
- XXX.world.entity.ExperienceOrb
+ XXX.world.entity.FlyingMob
- XXX.world.entity.GlowSquid
+ XXX.world.entity.HasCustomInventoryScreen
- XXX.world.entity.HumanoidArm
+ XXX.world.entity.Interaction
- XXX.world.entity.Interaction$PlayerAction
+ XXX.world.entity.ItemBasedSteering
- XXX.world.entity.ItemSteerable
+ XXX.world.entity.LerpingModel
- XXX.world.entity.LightningBolt
+ XXX.world.entity.LivingEntity
- XXX.world.entity.LivingEntity$1
+ XXX.world.entity.LivingEntity$Fallsounds
- XXX.world.entity.Marker
+ XXX.world.entity.Mob
- XXX.world.entity.Mob$1
+ XXX.world.entity.MobCategory
- XXX.world.entity.MobSpawnType
+ XXX.world.entity.MobType
- XXX.world.entity.MoverType
+ XXX.world.entity.NeutralMob
- XXX.world.entity.OwnableEntity
+ XXX.world.entity.package-info
+ XXX.world.entity.PathfinderMob
- XXX.world.entity.PlayerRideable
+ XXX.world.entity.PlayerRideableJumping
- XXX.world.entity.Pose
+ XXX.world.entity.PowerableMob
- XXX.world.entity.RelativeMovement
+ XXX.world.entity.ReputationEventHandler
- XXX.world.entity.RiderShieldingMount
+ XXX.world.entity.Saddleable
- XXX.world.entity.Shearable
+ XXX.world.entity.SlotAccess
- XXX.world.entity.SlotAccess$1
+ XXX.world.entity.SlotAccess$2
- XXX.world.entity.SlotAccess$3
+ XXX.world.entity.SpawnGroupData
- XXX.world.entity.SpawnPlacements
+ XXX.world.entity.SpawnPlacements$Data
- XXX.world.entity.SpawnPlacements$SpawnPredicate
+ XXX.world.entity.SpawnPlacements$Type
- XXX.world.entity.TamableAnimal
+ XXX.world.entity.Targeting
- XXX.world.entity.TraceableEntity
+ XXX.world.entity.VariantHolder
- XXX.world.entity.WalkAnimationState
- XXX.world.food.package-info
+ XXX.world.inventory.AbstractContainerMenu
- XXX.world.inventory.AbstractContainerMenu$1
+ XXX.world.inventory.AbstractFurnaceMenu
- XXX.world.inventory.AnvilMenu
+ XXX.world.inventory.AnvilMenu$1
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
- XXX.world.inventory.InventoryMenu$2
+ XXX.world.inventory.ItemCombinerMenu
- XXX.world.inventory.ItemCombinerMenu$1
+ XXX.world.inventory.ItemCombinerMenu$2
- XXX.world.inventory.ItemCombinerMenu$3
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
+ XXX.world.inventory.package-info
+ XXX.world.inventory.PlayerEnderChestContainer
- XXX.world.inventory.RecipeBookMenu
+ XXX.world.inventory.RecipeBookType
- XXX.world.inventory.RecipeHolder
+ XXX.world.inventory.ResultContainer
- XXX.world.inventory.ResultSlot
+ XXX.world.inventory.ShulkerBoxMenu
- XXX.world.inventory.ShulkerBoxSlot
+ XXX.world.inventory.SimpleContainerData
- XXX.world.inventory.Slot
+ XXX.world.inventory.SmithingMenu
- XXX.world.inventory.SmokerMenu
+ XXX.world.inventory.StackedContentsCompatible
- XXX.world.inventory.StonecutterMenu
+ XXX.world.inventory.StonecutterMenu$1
- XXX.world.inventory.StonecutterMenu$2
+ XXX.world.item.AdventureModeCheck
- XXX.world.item.AirItem
+ XXX.world.item.ArmorItem
- XXX.world.item.ArmorItem$1
+ XXX.world.item.ArmorItem$Type
- XXX.world.item.ArmorMaterial
+ XXX.world.item.ArmorMaterials
- XXX.world.item.ArmorStandItem
+ XXX.world.item.ArrowItem
- XXX.world.item.AxeItem
+ XXX.world.item.BannerItem
- XXX.world.item.BannerPatternItem
+ XXX.world.item.BedItem
- XXX.world.item.BlockItem
+ XXX.world.item.BoatItem
- XXX.world.item.BoneMealItem
+ XXX.world.item.BookItem
- XXX.world.item.BottleItem
- XXX.world.item.BottleOfVoidItem
+ XXX.world.item.BowItem
- XXX.world.item.BowlFoodItem
+ XXX.world.item.BrushItem
- XXX.world.item.BrushItem$1
+ XXX.world.item.BrushItem$DustParticlesDelta
- XXX.world.item.BucketItem
+ XXX.world.item.BundleItem
- XXX.world.item.ChorusFruitItem
+ XXX.world.item.CompassItem
- XXX.world.item.ComplexItem
+ XXX.world.item.CreativeModeTab
- XXX.world.item.CreativeModeTab$1
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
+ XXX.world.item.DebugStickItem
- XXX.world.item.DiggerItem
+ XXX.world.item.DiscFragmentItem
- XXX.world.item.DispensibleContainerItem
+ XXX.world.item.DoubleHighBlockItem
- XXX.world.item.DupeHackItem
- XXX.world.item.EmeraldItem
+ XXX.world.item.EmptyMapItem
- XXX.world.item.EnchantedBookItem
+ XXX.world.item.EnchantedGoldenAppleItem
- XXX.world.item.EndCrystalItem
+ XXX.world.item.EnderEyeItem
- XXX.world.item.EnderpearlItem
+ XXX.world.item.Equipable
- XXX.world.item.ExperienceBottleItem
+ XXX.world.item.FireChargeItem
- XXX.world.item.FireworkRocketItem
+ XXX.world.item.FireworkRocketItem$Shape
- XXX.world.item.FireworkStarItem
+ XXX.world.item.FishingRodItem
- XXX.world.item.FlintAndSteelItem
+ XXX.world.item.FoodOnAStickItem
- XXX.world.item.GameMasterBlockItem
+ XXX.world.item.GlowInkSacItem
- XXX.world.item.HangingEntityItem
+ XXX.world.item.HangingSignItem
- XXX.world.item.HoeItem
+ XXX.world.item.HoneyBottleItem
- XXX.world.item.HoneycombItem
+ XXX.world.item.HorseArmorItem
- XXX.world.item.InkSacItem
+ XXX.world.item.Instrument
- XXX.world.item.InstrumentItem
+ XXX.world.item.Instruments
- XXX.world.item.Item
+ XXX.world.item.Item$1
- XXX.world.item.Item$Properties
+ XXX.world.item.ItemCooldowns
- XXX.world.item.ItemCooldowns$CooldownInstance
+ XXX.world.item.ItemDisplayContext
- XXX.world.item.ItemFrameItem
+ XXX.world.item.ItemNameBlockItem
+ XXX.world.item.Items
- XXX.world.item.ItemStack
+ XXX.world.item.ItemStack$TooltipPart
- XXX.world.item.ItemStackLinkedSet
+ XXX.world.item.ItemStackLinkedSet$1
- XXX.world.item.ItemUtils
- XXX.world.item.KnowledgeBookItem
+ XXX.world.item.LeadItem
- XXX.world.item.LingeringPotionItem
+ XXX.world.item.MapItem
- XXX.world.item.MilkBucketItem
+ XXX.world.item.MinecartItem
- XXX.world.item.MinecartItem$1
+ XXX.world.item.MobBucketItem
- XXX.world.item.NameItem
- XXX.world.item.package-info
- XXX.world.item.SplashPotionItem
+ XXX.world.item.SpyglassItem
- XXX.world.item.StandingAndWallBlockItem
+ XXX.world.item.SuspiciousStewItem
- XXX.world.item.SwordItem
+ XXX.world.level.BaseCommandBlock
- XXX.world.level.BaseSpawner
+ XXX.world.level.BlockAndTintGetter
- XXX.world.level.BlockCollisions
+ XXX.world.level.BlockEventData
- XXX.world.level.BlockGetter
+ XXX.world.level.ChunkPos
- XXX.world.level.ChunkPos$1
+ XXX.world.level.ClipBlockStateContext
- XXX.world.level.ClipContext
+ XXX.world.level.ClipContext$Block
- XXX.world.level.ClipContext$Fluid
+ XXX.world.level.ClipContext$ShapeGetter
- XXX.world.level.CollisionGetter
+ XXX.world.level.ColorResolver
- XXX.world.level.CommonLevelAccessor
+ XXX.world.level.CustomSpawner
- XXX.world.level.DataPackConfig
+ XXX.world.level.EmptyBlockGetter
- XXX.world.level.EntityBasedExplosionDamageCalculator
+ XXX.world.level.EntityGetter
- XXX.world.level.Explosion
+ XXX.world.level.Explosion$BlockInteraction
- XXX.world.level.ExplosionDamageCalculator
+ XXX.world.level.FoliageColor
- XXX.world.level.ForcedChunksSavedData
+ XXX.world.level.GameRules
- XXX.world.level.GameRules$BooleanValue
+ XXX.world.level.GameRules$Category
- XXX.world.level.GameRules$GameRuleTypeVisitor
+ XXX.world.level.GameRules$IntegerValue
- XXX.world.level.GameRules$Key
+ XXX.world.level.GameRules$Type
- XXX.world.level.GameRules$Value
+ XXX.world.level.GameRules$VisitorCaller
- XXX.world.level.GameType
+ XXX.world.level.GrassColor
- XXX.world.level.ItemLike
+ XXX.world.level.Level
- XXX.world.level.Level$1
+ XXX.world.level.Level$2
- XXX.world.level.Level$ExplosionInteraction
+ XXX.world.level.LevelAccessor
- XXX.world.level.LevelHeightAccessor
+ XXX.world.level.LevelHeightAccessor$1
- XXX.world.level.LevelReader
+ XXX.world.level.LevelSettings
+ XXX.world.level.LevelSimulatedReader
- XXX.world.level.LevelSimulatedRW
- XXX.world.level.LevelTimeAccess
+ XXX.world.level.LevelWriter
- XXX.world.level.LightLayer
+ XXX.world.level.LocalMobCapCalculator
- XXX.world.level.LocalMobCapCalculator$MobCounts
+ XXX.world.level.NaturalSpawner
- XXX.world.level.NaturalSpawner$1
+ XXX.world.level.NaturalSpawner$AfterSpawnCallback
- XXX.world.level.NaturalSpawner$ChunkGetter
+ XXX.world.level.NaturalSpawner$SpawnPredicate
- XXX.world.level.NaturalSpawner$SpawnState
+ XXX.world.level.NoiseColumn
- XXX.world.level.PathNavigationRegion
+ XXX.world.level.PotentialCalculator
- XXX.world.level.PotentialCalculator$PointCharge
+ XXX.world.level.ServerLevelAccessor
- XXX.world.level.SignalGetter
+ XXX.world.level.SpawnData
- XXX.world.level.SpawnData$CustomSpawnRules
+ XXX.world.level.StructureManager
- XXX.world.level.WorldDataConfiguration
+ XXX.world.level.WorldGenLevel
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
<h2>Client<a name="client-mappings"></a></h2>
<details>
<summary>
Classes
</summary>

```diff
- net.minecraft.package-info
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
+ XXX.atlas.sources.DirectoryLister
- XXX.atlas.sources.LazyLoadedImage
- XXX.atlas.sources.package-info
+ XXX.atlas.sources.PalettedPermutations
- XXX.atlas.sources.PalettedPermutations$PalettedSpriteSupplier
+ XXX.atlas.sources.SingleFile
- XXX.atlas.sources.SourceFilter
+ XXX.atlas.sources.Unstitcher
- XXX.atlas.sources.Unstitcher$Region
+ XXX.atlas.sources.Unstitcher$RegionInstance
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
+ XXX.block.model.BakedQuad
- XXX.block.model.BlockElement
+ XXX.block.model.BlockElement$1
- XXX.block.model.BlockElement$Deserializer
+ XXX.block.model.BlockElementFace
- XXX.block.model.BlockElementFace$Deserializer
+ XXX.block.model.BlockElementRotation
- XXX.block.model.BlockFaceUV
+ XXX.block.model.BlockFaceUV$Deserializer
- XXX.block.model.BlockModel
+ XXX.block.model.BlockModel$Deserializer
- XXX.block.model.BlockModel$GuiLight
+ XXX.block.model.BlockModel$LoopException
- XXX.block.model.BlockModelDefinition
+ XXX.block.model.BlockModelDefinition$Context
- XXX.block.model.BlockModelDefinition$Deserializer
+ XXX.block.model.BlockModelDefinition$MissingVariantException
- XXX.block.model.FaceBakery
+ XXX.block.model.FaceBakery$1
- XXX.block.model.ItemModelGenerator
+ XXX.block.model.ItemModelGenerator$1
- XXX.block.model.ItemModelGenerator$Span
+ XXX.block.model.ItemModelGenerator$SpanFacing
- XXX.block.model.ItemOverride
+ XXX.block.model.ItemOverride$Deserializer
- XXX.block.model.ItemOverride$Predicate
+ XXX.block.model.ItemOverrides
- XXX.block.model.ItemOverrides$BakedOverride
+ XXX.block.model.ItemOverrides$PropertyMatcher
- XXX.block.model.ItemTransform
+ XXX.block.model.ItemTransform$Deserializer
- XXX.block.model.ItemTransforms
+ XXX.block.model.ItemTransforms$1
- XXX.block.model.ItemTransforms$Deserializer
+ XXX.block.model.MultiVariant
- XXX.block.model.MultiVariant$Deserializer
- XXX.block.model.package-info
+ XXX.block.model.Variant
- XXX.block.model.Variant$Deserializer
- XXX.chat.contents.BlockDataSource
+ XXX.chat.contents.DataSource
- XXX.chat.contents.EntityDataSource
+ XXX.chat.contents.KeybindContents
- XXX.chat.contents.KeybindResolver
+ XXX.chat.contents.LiteralContents
- XXX.chat.contents.NbtContents
- XXX.chat.contents.package-info
+ XXX.chat.contents.ScoreContents
- XXX.chat.contents.SelectorContents
+ XXX.chat.contents.StorageDataSource
- XXX.chat.contents.TranslatableContents
+ XXX.chat.contents.TranslatableFormatException
- XXX.chat.report.AbuseReportSender
+ XXX.chat.report.AbuseReportSender$1
- XXX.chat.report.AbuseReportSender$SendException
+ XXX.chat.report.AbuseReportSender$Services
- XXX.chat.report.BanReason
+ XXX.chat.report.ChatReportBuilder
- XXX.chat.report.ChatReportBuilder$CannotBuildReason
+ XXX.chat.report.ChatReportBuilder$ChatReport
- XXX.chat.report.ChatReportBuilder$Result
+ XXX.chat.report.ChatReportContextBuilder
- XXX.chat.report.ChatReportContextBuilder$Collector
+ XXX.chat.report.ChatReportContextBuilder$Handler
- XXX.chat.report.package-info
- XXX.chat.report.ReportEnvironment
+ XXX.chat.report.ReportEnvironment$Server
- XXX.chat.report.ReportEnvironment$Server$Realm
+ XXX.chat.report.ReportEnvironment$Server$ThirdParty
+ XXX.chat.report.ReportingContext
- XXX.chat.report.ReportReason
- XXX.client.gui.Font$DisplayMode
+ XXX.client.gui.Font$StringRenderOutput
- XXX.client.gui.Gui
+ XXX.client.gui.Gui$HeartType
- XXX.client.gui.GuiComponent
+ XXX.client.gui.GuiComponent$ScissorStack
- XXX.client.gui.MapRenderer
+ XXX.client.gui.MapRenderer$MapInstance
+ XXX.client.gui.package-info
- XXX.client.main.GameConfig
+ XXX.client.main.GameConfig$FolderData
- XXX.client.main.GameConfig$GameData
+ XXX.client.main.GameConfig$ServerData
- XXX.client.main.GameConfig$UserData
+ XXX.client.main.Main
- XXX.client.main.Main$1
+ XXX.client.main.Main$2
- XXX.client.main.Main$3
- XXX.client.main.package-info
+ XXX.client.main.SilentInitException
+ XXX.client.model.AbstractZombieModel
- XXX.client.model.AgeableHierarchicalModel
+ XXX.client.model.AgeableListModel
- XXX.client.model.AllayModel
+ XXX.client.model.AnimationUtils
- XXX.client.model.ArmedModel
+ XXX.client.model.ArmorStandArmorModel
- XXX.client.model.ArmorStandModel
+ XXX.client.model.AxolotlModel
- XXX.client.model.BatModel
+ XXX.client.model.BeeModel
- XXX.client.model.BeretModel
- XXX.client.model.DolphinModel
+ XXX.client.model.DrownedModel
- XXX.client.model.ElytraModel
+ XXX.client.model.EndermanModel
- XXX.client.model.EndermiteModel
+ XXX.client.model.EntityModel
- XXX.client.model.EvokerFangsModel
+ XXX.client.model.FoxModel
- XXX.client.model.FrogModel
+ XXX.client.model.GhastModel
- XXX.client.model.GiantZombieModel
+ XXX.client.model.GoatModel
- XXX.client.model.GuardianModel
+ XXX.client.model.HeadedModel
- XXX.client.model.HierarchicalModel
+ XXX.client.model.HoglinModel
- XXX.client.model.HorseModel
+ XXX.client.model.HumanoidArmorModel
- XXX.client.model.HumanoidModel
+ XXX.client.model.HumanoidModel$1
- XXX.client.model.HumanoidModel$ArmPose
+ XXX.client.model.IllagerModel
- XXX.client.model.IronGolemModel
+ XXX.client.model.LavaSlimeModel
- XXX.client.model.LeashKnotModel
+ XXX.client.model.ListModel
- XXX.client.model.LlamaModel
+ XXX.client.model.LlamaSpitModel
- XXX.client.model.MinecartModel
+ XXX.client.model.Model
- XXX.client.model.ModelUtils
+ XXX.client.model.package-info
- XXX.client.model.TridentModel
+ XXX.client.model.TropicalFishModelA
- XXX.client.model.TropicalFishModelB
+ XXX.client.model.TurtleModel
- XXX.client.model.VexModel
+ XXX.client.model.VillagerHeadModel
- XXX.client.model.VillagerModel
+ XXX.client.model.WardenModel
- XXX.client.model.WaterPatchModel
+ XXX.client.model.WitchModel
- XXX.client.model.WitherBossModel
+ XXX.client.model.WolfModel
- XXX.client.model.ZombieModel
+ XXX.client.model.ZombieVillagerModel
- XXX.client.multiplayer.AccountProfileKeyPairManager
+ XXX.client.multiplayer.ClientAdvancements
- XXX.client.multiplayer.ClientAdvancements$Listener
+ XXX.client.multiplayer.ClientChunkCache
- XXX.client.multiplayer.ClientChunkCache$Storage
+ XXX.client.multiplayer.ClientHandshakePacketListenerImpl
- XXX.client.multiplayer.ClientLevel
+ XXX.client.multiplayer.ClientLevel$1
- XXX.client.multiplayer.ClientLevel$ClientLevelData
+ XXX.client.multiplayer.ClientLevel$EntityCallbacks
- XXX.client.multiplayer.ClientPacketListener
+ XXX.client.multiplayer.ClientPacketListener$1
- XXX.client.multiplayer.ClientPacketListener$DeferredPacket
+ XXX.client.multiplayer.ClientRegistryLayer
- XXX.client.multiplayer.ClientSuggestionProvider
+ XXX.client.multiplayer.ClientSuggestionProvider$1
- XXX.client.multiplayer.MultiPlayerGameMode
+ XXX.client.multiplayer.package-info
+ XXX.client.multiplayer.PlayerInfo
- XXX.client.multiplayer.ProfileKeyPairManager
+ XXX.client.multiplayer.ProfileKeyPairManager$1
- XXX.client.multiplayer.ServerData
+ XXX.client.multiplayer.ServerData$ServerPackStatus
- XXX.client.multiplayer.ServerList
+ XXX.client.multiplayer.ServerStatusPinger
- XXX.client.multiplayer.ServerStatusPinger$1
+ XXX.client.multiplayer.ServerStatusPinger$2
- XXX.client.multiplayer.ServerStatusPinger$2$1
- XXX.client.particle.AshParticle
+ XXX.client.particle.AshParticle$Provider
- XXX.client.particle.AttackSweepParticle
+ XXX.client.particle.AttackSweepParticle$Provider
- XXX.client.particle.BaseAshSmokeParticle
+ XXX.client.particle.BlockMarker
- XXX.client.particle.BlockMarker$Provider
+ XXX.client.particle.BreakingItemParticle
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
- XXX.client.particle.CherryParticle
+ XXX.client.particle.CritParticle
- XXX.client.particle.CritParticle$DamageIndicatorProvider
+ XXX.client.particle.CritParticle$MagicProvider
- XXX.client.particle.CritParticle$Provider
+ XXX.client.particle.DragonBreathParticle
- XXX.client.particle.DragonBreathParticle$Provider
+ XXX.client.particle.DripParticle
- XXX.client.particle.DripParticle$CoolingDripHangParticle
+ XXX.client.particle.DripParticle$DripHangParticle
- XXX.client.particle.DripParticle$DripLandParticle
+ XXX.client.particle.DripParticle$DripstoneFallAndLandParticle
- XXX.client.particle.DripParticle$FallAndLandParticle
+ XXX.client.particle.DripParticle$FallingParticle
- XXX.client.particle.DripParticle$HoneyFallAndLandParticle
+ XXX.client.particle.DustColorTransitionParticle
- XXX.client.particle.DustColorTransitionParticle$Provider
+ XXX.client.particle.DustParticle
- XXX.client.particle.DustParticle$Provider
+ XXX.client.particle.DustParticleBase
- XXX.client.particle.EnchantmentTableParticle
+ XXX.client.particle.EnchantmentTableParticle$NautilusProvider
- XXX.client.particle.EnchantmentTableParticle$Provider
+ XXX.client.particle.EndRodParticle
- XXX.client.particle.EndRodParticle$Provider
+ XXX.client.particle.ExplodeParticle
- XXX.client.particle.ExplodeParticle$Provider
+ XXX.client.particle.FallingDustParticle
- XXX.client.particle.FallingDustParticle$Provider
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
- XXX.client.particle.FootprintParticle$Provider
+ XXX.client.particle.GlowParticle
- XXX.client.particle.GlowParticle$ElectricSparkProvider
+ XXX.client.particle.GlowParticle$GlowSquidProvider
- XXX.client.particle.GlowParticle$ScrapeProvider
+ XXX.client.particle.GlowParticle$WaxOffProvider
- XXX.client.particle.GlowParticle$WaxOnProvider
+ XXX.client.particle.HeartParticle
- XXX.client.particle.HeartParticle$AngryVillagerProvider
+ XXX.client.particle.HeartParticle$Provider
- XXX.client.particle.HugeExplosionParticle
+ XXX.client.particle.HugeExplosionParticle$Provider
- XXX.client.particle.HugeExplosionSeedParticle
+ XXX.client.particle.HugeExplosionSeedParticle$Provider
- XXX.client.particle.ItemPickupParticle
+ XXX.client.particle.LargeSmokeParticle
- XXX.client.particle.LargeSmokeParticle$Provider
+ XXX.client.particle.LavaParticle
- XXX.client.particle.LavaParticle$Provider
+ XXX.client.particle.MobAppearanceParticle
- XXX.client.particle.MobAppearanceParticle$Provider
+ XXX.client.particle.NoRenderParticle
- XXX.client.particle.NoteParticle
+ XXX.client.particle.NoteParticle$Provider
- XXX.client.particle.package-info
- XXX.client.particle.Particle
+ XXX.client.particle.ParticleDescription
- XXX.client.particle.ParticleEngine
+ XXX.client.particle.ParticleEngine$1ParticleDefinition
- XXX.client.particle.ParticleEngine$MutableSpriteSet
+ XXX.client.particle.ParticleEngine$SpriteParticleRegistration
- XXX.client.particle.ParticleProvider
+ XXX.client.particle.ParticleProvider$Sprite
- XXX.client.particle.ParticleRenderType
+ XXX.client.particle.ParticleRenderType$1
- XXX.client.particle.ParticleRenderType$2
+ XXX.client.particle.ParticleRenderType$3
- XXX.client.particle.ParticleRenderType$4
+ XXX.client.particle.ParticleRenderType$5
- XXX.client.particle.ParticleRenderType$6
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
+ XXX.client.particle.SmokeParticle
- XXX.client.particle.SmokeParticle$Provider
+ XXX.client.particle.SnowflakeParticle
- XXX.client.particle.SnowflakeParticle$Provider
+ XXX.client.particle.SonicBoomParticle
- XXX.client.particle.SonicBoomParticle$Provider
+ XXX.client.particle.SoulParticle
- XXX.client.particle.SoulParticle$EmissiveProvider
+ XXX.client.particle.SoulParticle$Provider
- XXX.client.particle.SpellParticle
+ XXX.client.particle.SpellParticle$AmbientMobProvider
- XXX.client.particle.SpellParticle$InstantProvider
+ XXX.client.particle.SpellParticle$MobProvider
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
+ XXX.client.particle.TerrainParticle$Provider
- XXX.client.particle.TextureSheetParticle
+ XXX.client.particle.TotemParticle
- XXX.client.particle.TotemParticle$Provider
+ XXX.client.particle.TrackingEmitter
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
+ XXX.client.player.AbstractClientPlayer
- XXX.client.player.Input
+ XXX.client.player.KeyboardInput
- XXX.client.player.LocalPlayer
- XXX.client.renderer.DimensionSpecialEffects$MoonEffects
+ XXX.client.renderer.DimensionSpecialEffects$NetherEffects
- XXX.client.renderer.DimensionSpecialEffects$OverworldEffects
+ XXX.client.renderer.DimensionSpecialEffects$SkyType
- XXX.client.renderer.EffectInstance
+ XXX.client.renderer.FaceInfo
- XXX.client.renderer.FaceInfo$Constants
+ XXX.client.renderer.FaceInfo$VertexInfo
- XXX.client.renderer.FogRenderer
+ XXX.client.renderer.FogRenderer$BlindnessFogFunction
- XXX.client.renderer.FogRenderer$DarknessFogFunction
+ XXX.client.renderer.FogRenderer$FogData
- XXX.client.renderer.FogRenderer$FogMode
+ XXX.client.renderer.FogRenderer$MobEffectFogFunction
- XXX.client.renderer.GameRenderer
+ XXX.client.renderer.GameRenderer$1
- XXX.client.renderer.GameRenderer$ResourceCache
+ XXX.client.renderer.GpuWarnlistManager
- XXX.client.renderer.GpuWarnlistManager$Preparations
+ XXX.client.renderer.ItemBlockRenderTypes
- XXX.client.renderer.ItemInHandRenderer
+ XXX.client.renderer.ItemInHandRenderer$1
- XXX.client.renderer.ItemInHandRenderer$HandRenderSelection
+ XXX.client.renderer.ItemModelShaper
- XXX.client.renderer.LevelRenderer
+ XXX.client.renderer.LevelRenderer$RenderChunkInfo
- XXX.client.renderer.LevelRenderer$RenderChunkStorage
+ XXX.client.renderer.LevelRenderer$RenderInfoMap
- XXX.client.renderer.LevelRenderer$TransparencyShaderException
+ XXX.client.renderer.LightTexture
- XXX.client.renderer.MultiBufferSource
+ XXX.client.renderer.MultiBufferSource$BufferSource
- XXX.client.renderer.OutlineBufferSource
+ XXX.client.renderer.OutlineBufferSource$EntityOutlineGenerator
- XXX.client.renderer.package-info
- XXX.client.renderer.PanoramaRenderer
+ XXX.client.renderer.PostChain
- XXX.client.renderer.PostPass
+ XXX.client.renderer.Rect2i
- XXX.client.renderer.RenderBuffers
+ XXX.client.renderer.RenderStateShard
- XXX.client.renderer.RenderStateShard$BooleanStateShard
+ XXX.client.renderer.RenderStateShard$CullStateShard
- XXX.client.renderer.RenderStateShard$DepthTestStateShard
+ XXX.client.renderer.RenderStateShard$EmptyTextureStateShard
- XXX.client.renderer.RenderStateShard$LayeringStateShard
+ XXX.client.renderer.RenderStateShard$LightmapStateShard
- XXX.client.renderer.RenderStateShard$LineStateShard
+ XXX.client.renderer.RenderStateShard$MultiTextureStateShard
- XXX.client.renderer.RenderStateShard$MultiTextureStateShard$Builder
+ XXX.client.renderer.RenderStateShard$OffsetTexturingStateShard
- XXX.client.renderer.RenderStateShard$OutputStateShard
+ XXX.client.renderer.RenderStateShard$OverlayStateShard
- XXX.client.renderer.RenderStateShard$ShaderStateShard
+ XXX.client.renderer.RenderStateShard$TextureStateShard
- XXX.client.renderer.RenderStateShard$TexturingStateShard
+ XXX.client.renderer.RenderStateShard$TransparencyStateShard
- XXX.client.renderer.RenderStateShard$WriteMaskStateShard
+ XXX.client.renderer.RenderType
- XXX.client.renderer.RenderType$CompositeRenderType
+ XXX.client.renderer.RenderType$CompositeState
- XXX.client.renderer.RenderType$CompositeState$CompositeStateBuilder
+ XXX.client.renderer.RenderType$OutlineProperty
- XXX.client.renderer.RunningTrimmedMean
+ XXX.client.renderer.ScreenEffectRenderer
- XXX.client.renderer.ShaderInstance
+ XXX.client.renderer.ShaderInstance$1
- XXX.client.renderer.Sheets
+ XXX.client.renderer.Sheets$1
- XXX.client.renderer.SpriteCoordinateExpander
+ XXX.client.renderer.ViewArea
- XXX.client.renderer.VirtualScreen
- XXX.client.resources.ClientPackSource
+ XXX.client.resources.DefaultPlayerSkin
- XXX.client.resources.DefaultPlayerSkin$ModelType
+ XXX.client.resources.DefaultPlayerSkin$SkinType
- XXX.client.resources.DownloadedPackSource
+ XXX.client.resources.FoliageColorReloadListener
- XXX.client.resources.GrassColorReloadListener
+ XXX.client.resources.IndexedAssetSource
- XXX.client.resources.LegacyStuffWrapper
+ XXX.client.resources.MobEffectTextureManager
+ XXX.client.resources.package-info
- XXX.client.resources.PaintingTextureManager
+ XXX.client.resources.SkinManager
- XXX.client.resources.SkinManager$1
+ XXX.client.resources.SkinManager$2
- XXX.client.resources.SkinManager$SkinTextureCallback
+ XXX.client.resources.SplashManager
- XXX.client.resources.TextureAtlasHolder
- XXX.client.searchtree.FullTextSearchTree
+ XXX.client.searchtree.IdSearchTree
- XXX.client.searchtree.IntersectionIterator
+ XXX.client.searchtree.MergingUniqueIterator
+ XXX.client.searchtree.package-info
- XXX.client.searchtree.PlainTextSearchTree
+ XXX.client.searchtree.RefreshableSearchTree
- XXX.client.searchtree.ResourceLocationSearchTree
+ XXX.client.searchtree.ResourceLocationSearchTree$1
- XXX.client.searchtree.ResourceLocationSearchTree$2
+ XXX.client.searchtree.SearchRegistry
- XXX.client.searchtree.SearchRegistry$Key
+ XXX.client.searchtree.SearchRegistry$TreeBuilderSupplier
- XXX.client.searchtree.SearchRegistry$TreeEntry
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
+ XXX.client.sounds.LoopingAudioStream
- XXX.client.sounds.LoopingAudioStream$AudioStreamProvider
+ XXX.client.sounds.LoopingAudioStream$NoCloseBuffer
- XXX.client.sounds.MusicManager
+ XXX.client.sounds.package-info
+ XXX.client.sounds.SoundBufferLibrary
- XXX.client.sounds.SoundEngine
+ XXX.client.sounds.SoundEngine$DeviceCheckState
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
- XXX.client.tutorial.BundleTutorial
+ XXX.client.tutorial.CompletedTutorialStepInstance
- XXX.client.tutorial.CraftPlanksTutorialStep
+ XXX.client.tutorial.FindTreeTutorialStepInstance
- XXX.client.tutorial.MovementTutorialStepInstance
+ XXX.client.tutorial.OpenInventoryTutorialStep
+ XXX.client.tutorial.package-info
- XXX.client.tutorial.PunchTreeTutorialStepInstance
+ XXX.client.tutorial.Tutorial
- XXX.client.tutorial.Tutorial$TimedToast
+ XXX.client.tutorial.TutorialStepInstance
- XXX.client.tutorial.TutorialSteps
- XXX.client.voting.ClientVoteStorage
- XXX.client.voting.ClientVoteStorage$CountAndLimit
- XXX.client.voting.ClientVoteStorage$VoteInfo
- XXX.client.voting.package-info
+ XXX.commands.data.BlockDataAccessor
- XXX.commands.data.BlockDataAccessor$1
+ XXX.commands.data.DataAccessor
- XXX.commands.data.DataCommands
+ XXX.commands.data.DataCommands$DataManipulator
- XXX.commands.data.DataCommands$DataManipulatorDecorator
+ XXX.commands.data.DataCommands$DataProvider
- XXX.commands.data.EntityDataAccessor
+ XXX.commands.data.EntityDataAccessor$1
- XXX.commands.data.package-info
- XXX.commands.data.StorageDataAccessor
+ XXX.commands.data.StorageDataAccessor$1
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
+ XXX.components.toasts.package-info
- XXX.components.toasts.RecipeToast
+ XXX.components.toasts.SystemToast
- XXX.components.toasts.SystemToast$SystemToastIds
+ XXX.components.toasts.Toast
- XXX.components.toasts.Toast$Visibility
+ XXX.components.toasts.ToastComponent
- XXX.components.toasts.ToastComponent$ToastInstance
+ XXX.components.toasts.TutorialToast
- XXX.components.toasts.TutorialToast$Icons
- XXX.components.toasts.VoteNagToast$Urgency
- XXX.data.worldgen.package-info
- XXX.datafix.schemas.package-info
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
- XXX.entity.animal.Bee$BeelooningGoal
- XXX.entity.animal.Bee$BeePollinateGoal
+ XXX.entity.animal.Bee$BeeWanderGoal
- XXX.entity.animal.Bee$MoveWithoutPathfindingGoal
- XXX.entity.animal.MoonCow$MoonWalkControl
- XXX.entity.item.ItemEntity$1
- XXX.entity.item.package-info
+ XXX.entity.item.PrimedTnt
- XXX.entity.layers.CapeLayer
+ XXX.entity.layers.CarriedBlockLayer
- XXX.entity.layers.CatCollarLayer
+ XXX.entity.layers.CreeperPowerLayer
- XXX.entity.layers.CrossedArmsItemLayer
- XXX.entity.layers.MustacheLayer
+ XXX.entity.layers.PandaHoldsItemLayer
- XXX.entity.layers.ParrotOnShoulderLayer
+ XXX.entity.layers.PhantomEyesLayer
- XXX.entity.layers.PlayerItemInHandLayer
+ XXX.entity.layers.RenderLayer
- XXX.entity.layers.SaddleLayer
+ XXX.entity.layers.SheepFurLayer
- XXX.entity.layers.ShulkerHeadLayer
+ XXX.entity.layers.SlimeOuterLayer
- XXX.entity.layers.SnowGolemHeadLayer
+ XXX.entity.layers.SpiderEyesLayer
- XXX.entity.layers.SpinAttackEffectLayer
+ XXX.entity.layers.StrayClothingLayer
- XXX.entity.layers.StuckInBodyLayer
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
- XXX.entity.monster.Zombie$1
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
+ XXX.entity.player.package-info
- XXX.entity.player.package-info
- XXX.entity.player.Player
+ XXX.entity.player.Player$1
- XXX.entity.player.Player$BedSleepingProblem
+ XXX.entity.player.PlayerModelPart
- XXX.entity.player.PlayerRenderer$PlayerArmorModel
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
- XXX.entity.transform.EntityTransformType
- XXX.entity.transform.TransformCommand
+ XXX.feature.configurations.BlockColumnConfiguration
- XXX.feature.configurations.BlockColumnConfiguration$Layer
+ XXX.feature.configurations.BlockPileConfiguration
- XXX.feature.configurations.BlockStateConfiguration
+ XXX.feature.configurations.ColumnFeatureConfiguration
- XXX.feature.configurations.CountConfiguration
- XXX.font.glyphs.BakedGlyph
+ XXX.font.glyphs.BakedGlyph$1
- XXX.font.glyphs.BakedGlyph$Effect
+ XXX.font.glyphs.EmptyGlyph
+ XXX.font.glyphs.package-info
- XXX.font.glyphs.SpecialGlyphs
+ XXX.font.glyphs.SpecialGlyphs$1
- XXX.font.glyphs.SpecialGlyphs$PixelProvider
+ XXX.font.providers.BitmapProvider
- XXX.font.providers.BitmapProvider$Builder
+ XXX.font.providers.BitmapProvider$Glyph
- XXX.font.providers.BitmapProvider$Glyph$1
+ XXX.font.providers.GlyphProviderBuilder
- XXX.font.providers.GlyphProviderBuilderType
+ XXX.font.providers.LegacyUnicodeBitmapsProvider
- XXX.font.providers.LegacyUnicodeBitmapsProvider$Builder
+ XXX.font.providers.LegacyUnicodeBitmapsProvider$Glyph
- XXX.font.providers.LegacyUnicodeBitmapsProvider$Glyph$1
+ XXX.font.providers.LegacyUnicodeBitmapsProvider$Sheet
+ XXX.font.providers.package-info
- XXX.font.providers.TrueTypeGlyphProviderBuilder
- XXX.gametest.framework.AfterBatch
+ XXX.gametest.framework.BeforeBatch
- XXX.gametest.framework.ExhaustedAttemptsException
+ XXX.gametest.framework.GameTest
- XXX.gametest.framework.GameTestAssertException
+ XXX.gametest.framework.GameTestAssertPosException
- XXX.gametest.framework.GameTestBatch
+ XXX.gametest.framework.GameTestBatchRunner
- XXX.gametest.framework.GameTestBatchRunner$1
+ XXX.gametest.framework.GameTestEvent
- XXX.gametest.framework.GameTestGenerator
+ XXX.gametest.framework.GameTestHelper
- XXX.gametest.framework.GameTestHelper$1
+ XXX.gametest.framework.GameTestHelper$2
- XXX.gametest.framework.GameTestInfo
+ XXX.gametest.framework.GameTestListener
- XXX.gametest.framework.GameTestRegistry
+ XXX.gametest.framework.GameTestRunner
- XXX.gametest.framework.GameTestSequence
+ XXX.gametest.framework.GameTestSequence$Condition
- XXX.gametest.framework.GameTestServer
+ XXX.gametest.framework.GameTestServer$1
- XXX.gametest.framework.GameTestTicker
+ XXX.gametest.framework.GameTestTimeoutException
- XXX.gametest.framework.GlobalTestReporter
+ XXX.gametest.framework.JUnitLikeTestReporter
- XXX.gametest.framework.LogTestReporter
+ XXX.gametest.framework.MultipleTestTracker
- XXX.gametest.framework.MultipleTestTracker$1
+ XXX.gametest.framework.package-info
+ XXX.gametest.framework.ReportGameListener
- XXX.gametest.framework.StructureUtils
+ XXX.gametest.framework.StructureUtils$1
- XXX.gametest.framework.TeamcityTestReporter
+ XXX.gametest.framework.TestClassNameArgument
- XXX.gametest.framework.TestCommand
+ XXX.gametest.framework.TestCommand$TestSummaryDisplayer
- XXX.gametest.framework.TestFunction
+ XXX.gametest.framework.TestFunctionArgument
- XXX.gametest.framework.TestReporter
+ XXX.geom.builders.CubeDefinition
- XXX.geom.builders.CubeDeformation
+ XXX.geom.builders.CubeListBuilder
- XXX.geom.builders.LayerDefinition
+ XXX.geom.builders.MaterialDefinition
- XXX.geom.builders.MeshDefinition
+ XXX.geom.builders.package-info
+ XXX.geom.builders.PartDefinition
- XXX.geom.builders.UVPair
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
- XXX.gui.components.AbstractButton
+ XXX.gui.components.AbstractOptionSliderButton
- XXX.gui.components.AbstractScrollWidget
+ XXX.gui.components.AbstractSelectionList
- XXX.gui.components.AbstractSelectionList$1
+ XXX.gui.components.AbstractSelectionList$Entry
- XXX.gui.components.AbstractSelectionList$TrackedList
+ XXX.gui.components.AbstractSliderButton
- XXX.gui.components.AbstractStringWidget
+ XXX.gui.components.AbstractWidget
- XXX.gui.components.AccessibilityOnboardingTextWidget
+ XXX.gui.components.BossHealthOverlay
- XXX.gui.components.BossHealthOverlay$1
+ XXX.gui.components.Button
- XXX.gui.components.Button$Builder
+ XXX.gui.components.Button$CreateNarration
- XXX.gui.components.Button$OnPress
+ XXX.gui.components.ChatComponent
- XXX.gui.components.ChatComponent$DelayedMessageDeletion
+ XXX.gui.components.Checkbox
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
+ XXX.gui.components.DebugScreenOverlay$AllocationRateCalculator
- XXX.gui.components.EditBox
+ XXX.gui.components.ImageButton
- XXX.gui.components.ImageWidget
+ XXX.gui.components.LerpingBossEvent
- XXX.gui.components.LockIconButton
+ XXX.gui.components.LockIconButton$Icon
- XXX.gui.components.LogoRenderer
+ XXX.gui.components.MultiLineEditBox
- XXX.gui.components.MultiLineLabel
+ XXX.gui.components.MultiLineLabel$1
- XXX.gui.components.MultiLineLabel$2
+ XXX.gui.components.MultiLineLabel$TextWithWidth
- XXX.gui.components.MultilineTextField
+ XXX.gui.components.MultilineTextField$1
- XXX.gui.components.MultilineTextField$StringView
- XXX.gui.components.MultiLineTextWidget
+ XXX.gui.components.MultiLineTextWidget$CacheKey
+ XXX.gui.components.ObjectSelectionList
- XXX.gui.components.ObjectSelectionList$Entry
+ XXX.gui.components.OptionsList
- XXX.gui.components.OptionsList$Entry
- XXX.gui.components.package-info
+ XXX.gui.components.PlainTextButton
- XXX.gui.components.PlayerFaceRenderer
+ XXX.gui.components.PlayerTabOverlay
- XXX.gui.components.PlayerTabOverlay$HealthState
+ XXX.gui.components.Renderable
- XXX.gui.components.StateSwitchingButton
+ XXX.gui.components.StringWidget
- XXX.gui.components.SubtitleOverlay
+ XXX.gui.components.SubtitleOverlay$Subtitle
- XXX.gui.components.TabButton
+ XXX.gui.components.TabOrderedElement
- XXX.gui.components.TextAndImageButton
+ XXX.gui.components.TextAndImageButton$Builder
- XXX.gui.components.Tooltip
+ XXX.gui.components.Whence
- XXX.gui.font.AllMissingGlyphProvider
+ XXX.gui.font.FontManager
- XXX.gui.font.FontManager$1
+ XXX.gui.font.FontSet
- XXX.gui.font.FontSet$GlyphInfoFilter
+ XXX.gui.font.FontTexture
- XXX.gui.font.FontTexture$Node
- XXX.gui.font.package-info
+ XXX.gui.font.TextFieldHelper
- XXX.gui.font.TextFieldHelper$1
+ XXX.gui.font.TextFieldHelper$CursorStep
- XXX.gui.layouts.AbstractLayout
+ XXX.gui.layouts.AbstractLayout$AbstractChildWrapper
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
+ XXX.gui.layouts.LinearLayout$1
- XXX.gui.layouts.LinearLayout$ChildContainer
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
- XXX.gui.navigation.FocusNavigationEvent
+ XXX.gui.navigation.FocusNavigationEvent$ArrowNavigation
- XXX.gui.navigation.FocusNavigationEvent$InitialFocus
+ XXX.gui.navigation.FocusNavigationEvent$TabNavigation
- XXX.gui.navigation.package-info
- XXX.gui.navigation.ScreenAxis
+ XXX.gui.navigation.ScreenAxis$1
- XXX.gui.navigation.ScreenDirection
+ XXX.gui.navigation.ScreenDirection$1
- XXX.gui.navigation.ScreenPosition
+ XXX.gui.navigation.ScreenPosition$1
- XXX.gui.navigation.ScreenRectangle
+ XXX.gui.navigation.ScreenRectangle$1
- XXX.gui.screens.AccessibilityOnboardingScreen
+ XXX.gui.screens.AccessibilityOptionsScreen
- XXX.gui.screens.AlertScreen
+ XXX.gui.screens.BackupConfirmScreen
- XXX.gui.screens.BackupConfirmScreen$Listener
+ XXX.gui.screens.BanNoticeScreen
- XXX.gui.screens.ChatOptionsScreen
+ XXX.gui.screens.ChatScreen
- XXX.gui.screens.ChatScreen$1
+ XXX.gui.screens.ConfirmLinkScreen
- XXX.gui.screens.ConfirmScreen
+ XXX.gui.screens.ConnectScreen
- XXX.gui.screens.ConnectScreen$1
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
- XXX.gui.screens.GenericDirtMessageScreen
+ XXX.gui.screens.GenericWaitingScreen
- XXX.gui.screens.InBedChatScreen
+ XXX.gui.screens.LanguageSelectScreen
- XXX.gui.screens.LanguageSelectScreen$LanguageSelectionList
+ XXX.gui.screens.LanguageSelectScreen$LanguageSelectionList$Entry
- XXX.gui.screens.LevelLoadingScreen
+ XXX.gui.screens.LoadingDotsText
- XXX.gui.screens.LoadingOverlay
+ XXX.gui.screens.LoadingOverlay$LogoTexture
- XXX.gui.screens.MenuScreens
+ XXX.gui.screens.MenuScreens$ScreenConstructor
- XXX.gui.screens.MouseSettingsScreen
+ XXX.gui.screens.OnlineOptionsScreen
- XXX.gui.screens.OptionsScreen
+ XXX.gui.screens.OptionsSubScreen
- XXX.gui.screens.OutOfMemoryScreen
+ XXX.gui.screens.Overlay
- XXX.gui.screens.package-info
- XXX.gui.screens.PauseScreen
+ XXX.gui.screens.PopupScreen
- XXX.gui.screens.PopupScreen$ButtonOption
+ XXX.gui.screens.PresetFlatWorldScreen
- XXX.gui.screens.PresetFlatWorldScreen$PresetsList
+ XXX.gui.screens.PresetFlatWorldScreen$PresetsList$Entry
- XXX.gui.screens.ProgressScreen
+ XXX.gui.screens.ReceivingLevelScreen
- XXX.gui.screens.Screen
+ XXX.gui.screens.Screen$DeferredTooltipRendering
- XXX.gui.screens.Screen$NarratableSearchResult
+ XXX.gui.screens.ShareToLanScreen
- XXX.gui.screens.SimpleOptionsSubScreen
+ XXX.gui.screens.SkinCustomizationScreen
- XXX.gui.screens.SoundOptionsScreen
- XXX.gui.screens.SuperSimpleTextScreen
- XXX.gui.screens.SuperSimpleTextScreen$SimpleTextList$Entry
+ XXX.gui.screens.TitleScreen
- XXX.gui.screens.TitleScreen$WarningLabel
+ XXX.gui.screens.VideoSettingsScreen
- XXX.gui.screens.WinScreen
+ XXX.gui.screens.WinScreen$CreditsReader
+ XXX.gui.spectator.package-info
+ XXX.gui.spectator.PlayerMenuItem
- XXX.gui.spectator.RootSpectatorMenuCategory
+ XXX.gui.spectator.SpectatorMenu
- XXX.gui.spectator.SpectatorMenu$1
+ XXX.gui.spectator.SpectatorMenu$CloseSpectatorItem
- XXX.gui.spectator.SpectatorMenu$ScrollMenuItem
+ XXX.gui.spectator.SpectatorMenuCategory
- XXX.gui.spectator.SpectatorMenuItem
+ XXX.gui.spectator.SpectatorMenuListener
+ XXX.inventory.tooltip.BelowOrAboveWidgetTooltipPositioner
+ XXX.inventory.tooltip.BundleTooltip
- XXX.inventory.tooltip.ClientBundleTooltip
+ XXX.inventory.tooltip.ClientBundleTooltip$Texture
- XXX.inventory.tooltip.ClientTextTooltip
+ XXX.inventory.tooltip.ClientTooltipComponent
- XXX.inventory.tooltip.ClientTooltipPositioner
+ XXX.inventory.tooltip.DefaultTooltipPositioner
- XXX.inventory.tooltip.MenuTooltipPositioner
+ XXX.inventory.tooltip.package-info
+ XXX.inventory.tooltip.package-info
- XXX.inventory.tooltip.TooltipComponent
+ XXX.inventory.tooltip.TooltipRenderUtil
- XXX.inventory.tooltip.TooltipRenderUtil$BlitPainter
- XXX.item.context.package-info
- XXX.item.context.PlaceBlockBlockPlaceContext
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
- XXX.item.crafting.DupeHackRecipe
- XXX.item.crafting.NbtCraftingRecipe
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
- XXX.level.biome.TheMoonBiomeSource
- XXX.level.block.CheeseBlock
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
- XXX.level.block.CopperSinkBlock
- XXX.level.block.FacingTriggerableBlock
+ XXX.level.block.Fallable
- XXX.level.block.FallingBlock
+ XXX.level.block.FarmBlock
- XXX.level.block.FenceBlock
+ XXX.level.block.FenceGateBlock
- XXX.level.block.FenceGateBlock$1
- XXX.level.block.PickaxeBlock
- XXX.level.block.PlayerHeadBlock
+ XXX.level.block.PlayerWallHeadBlock
- XXX.level.block.PointedDripstoneBlock
+ XXX.level.block.PointedDripstoneBlock$FluidInfo
- XXX.level.block.PotatoBlock
+ XXX.level.block.PowderSnowBlock
- XXX.level.block.PowderSnowCauldronBlock
+ XXX.level.block.PoweredBlock
- XXX.level.block.PoweredRailBlock
+ XXX.level.block.PoweredRailBlock$1
- XXX.level.block.PressurePlateBlock
+ XXX.level.block.PressurePlateBlock$1
- XXX.level.block.PressurePlateBlock$Sensitivity
+ XXX.level.block.PumpkinBlock
- XXX.level.block.RailBlock
+ XXX.level.block.RailBlock$1
- XXX.level.block.RailState
+ XXX.level.block.RailState$1
+ XXX.level.block.RedstoneLampBlock
- XXX.level.block.RedStoneOreBlock
- XXX.level.block.RedstoneTorchBlock
+ XXX.level.block.RedstoneTorchBlock$Toggle
- XXX.level.block.RedstoneWallTorchBlock
+ XXX.level.block.RedStoneWireBlock
- XXX.level.block.RedStoneWireBlock$1
+ XXX.level.block.RenderShape
- XXX.level.block.RepeaterBlock
+ XXX.level.block.RespawnAnchorBlock
- XXX.level.block.RespawnAnchorBlock$1
+ XXX.level.block.RodBlock
- XXX.level.block.RodBlock$1
+ XXX.level.block.RootedDirtBlock
- XXX.level.block.RootsBlock
+ XXX.level.block.RotatedPillarBlock
- XXX.level.block.RotatedPillarBlock$1
+ XXX.level.block.Rotation
- XXX.level.block.Rotation$1
+ XXX.level.block.SandBlock
- XXX.level.block.SaplingBlock
+ XXX.level.block.ScaffoldingBlock
- XXX.level.block.SculkBehaviour
+ XXX.level.block.SculkBehaviour$1
- XXX.level.block.SculkBlock
+ XXX.level.block.SculkCatalystBlock
- XXX.level.block.SculkSensorBlock
+ XXX.level.block.SculkShriekerBlock
- XXX.level.block.SculkSpreader
+ XXX.level.block.SculkSpreader$ChargeCursor
- XXX.level.block.SculkVeinBlock
+ XXX.level.block.SculkVeinBlock$SculkVeinSpreaderConfig
+ XXX.level.block.SeagrassBlock
- XXX.level.block.SeaPickleBlock
- XXX.level.block.ShulkerBoxBlock
+ XXX.level.block.ShulkerBoxBlock$1
- XXX.level.block.SignBlock
+ XXX.level.block.SimpleWaterloggedBlock
- XXX.level.block.SkullBlock
+ XXX.level.block.SkullBlock$Type
- XXX.level.block.SkullBlock$Types
+ XXX.level.block.SlabBlock
- XXX.level.block.SlabBlock$1
+ XXX.level.block.SlimeBlock
- XXX.level.block.SmallDripleafBlock
+ XXX.level.block.SmithingTableBlock
- XXX.level.block.SmokerBlock
+ XXX.level.block.SnifferEggBlock
- XXX.level.block.SnowLayerBlock
+ XXX.level.block.SnowLayerBlock$1
- XXX.level.block.SnowyDirtBlock
+ XXX.level.block.SoulFireBlock
- XXX.level.block.SoulSandBlock
+ XXX.level.block.SoundType
- XXX.level.block.SpawnerBlock
- XXX.level.levelgen.MoonBaseBuilder$1
- XXX.level.levelgen.NoiseBasedChunkGenerator
+ XXX.level.levelgen.NoiseChunk
- XXX.level.levelgen.NoiseChunk$1
+ XXX.level.levelgen.NoiseChunk$2
- XXX.level.levelgen.NoiseChunk$BlendAlpha
+ XXX.level.levelgen.NoiseChunk$BlendOffset
- XXX.level.levelgen.NoiseChunk$BlockStateFiller
+ XXX.level.levelgen.NoiseChunk$Cache2D
- XXX.level.levelgen.NoiseChunk$CacheAllInCell
+ XXX.level.levelgen.NoiseChunk$CacheOnce
- XXX.level.levelgen.NoiseChunk$FlatCache
+ XXX.level.levelgen.NoiseChunk$NoiseChunkDensityFunction
- XXX.level.levelgen.NoiseChunk$NoiseInterpolator
+ XXX.level.levelgen.NoiseGeneratorSettings
- XXX.level.levelgen.NoiseRouter
+ XXX.level.levelgen.NoiseRouterData
- XXX.level.levelgen.NoiseRouterData$QuantizedSpaghettiRarity
- XXX.level.levelgen.Noises
+ XXX.level.levelgen.NoiseSettings
+ XXX.level.levelgen.OreVeinifier
- XXX.level.levelgen.OreVeinifier$VeinType
+ XXX.level.levelgen.PatrolSpawner
- XXX.level.levelgen.PhantomSpawner
+ XXX.level.levelgen.PositionalRandomFactory
- XXX.level.levelgen.RandomState
+ XXX.level.levelgen.RandomState$1
- XXX.level.levelgen.RandomState$1NoiseWiringHelper
+ XXX.level.levelgen.RandomSupport
- XXX.level.levelgen.RandomSupport$Seed128bit
+ XXX.level.levelgen.SingleThreadedRandomSource
- XXX.level.levelgen.SurfaceRules
+ XXX.level.levelgen.SurfaceRules$AbovePreliminarySurface
- XXX.level.levelgen.SurfaceRules$Bandlands
+ XXX.level.levelgen.SurfaceRules$BiomeConditionSource
- XXX.level.levelgen.SurfaceRules$BiomeConditionSource$1BiomeCondition
+ XXX.level.levelgen.SurfaceRules$BlockRuleSource
- XXX.level.levelgen.SurfaceRules$Condition
+ XXX.level.levelgen.SurfaceRules$ConditionSource
- XXX.level.levelgen.SurfaceRules$Context
+ XXX.level.levelgen.SurfaceRules$Context$AbovePreliminarySurfaceCondition
- XXX.level.levelgen.SurfaceRules$Context$HoleCondition
+ XXX.level.levelgen.SurfaceRules$Context$SteepMaterialCondition
- XXX.level.levelgen.SurfaceRules$Context$TemperatureHelperCondition
+ XXX.level.levelgen.SurfaceRules$Hole
- XXX.level.levelgen.SurfaceRules$LazyCondition
+ XXX.level.levelgen.SurfaceRules$LazyXZCondition
- XXX.level.levelgen.SurfaceRules$LazyYCondition
+ XXX.level.levelgen.SurfaceRules$NoiseThresholdConditionSource
- XXX.level.levelgen.SurfaceRules$NoiseThresholdConditionSource$1NoiseThresholdCondition
+ XXX.level.levelgen.SurfaceRules$NotCondition
- XXX.level.levelgen.SurfaceRules$NotConditionSource
+ XXX.level.levelgen.SurfaceRules$RuleSource
- XXX.level.levelgen.SurfaceRules$SequenceRule
+ XXX.level.levelgen.SurfaceRules$SequenceRuleSource
- XXX.level.levelgen.SurfaceRules$StateRule
+ XXX.level.levelgen.SurfaceRules$Steep
- XXX.level.levelgen.SurfaceRules$StoneDepthCheck
+ XXX.level.levelgen.SurfaceRules$StoneDepthCheck$1StoneDepthCondition
- XXX.level.levelgen.SurfaceRules$SurfaceRule
+ XXX.level.levelgen.SurfaceRules$Temperature
- XXX.level.levelgen.SurfaceRules$TestRule
+ XXX.level.levelgen.SurfaceRules$TestRuleSource
- XXX.level.levelgen.SurfaceRules$VerticalGradientConditionSource
+ XXX.level.levelgen.SurfaceRules$VerticalGradientConditionSource$1VerticalGradientCondition
- XXX.level.levelgen.SurfaceRules$WaterConditionSource
+ XXX.level.levelgen.SurfaceRules$WaterConditionSource$1WaterCondition
- XXX.level.levelgen.SurfaceRules$YConditionSource
+ XXX.level.levelgen.SurfaceRules$YConditionSource$1YCondition
- XXX.level.levelgen.SurfaceSystem
+ XXX.level.levelgen.SurfaceSystem$1
- XXX.level.levelgen.ThreadSafeLegacyRandomSource
+ XXX.level.levelgen.VerticalAnchor
- XXX.level.levelgen.VerticalAnchor$AboveBottom
+ XXX.level.levelgen.VerticalAnchor$Absolute
- XXX.level.levelgen.VerticalAnchor$BelowTop
+ XXX.level.levelgen.WorldDimensions
- XXX.level.levelgen.WorldDimensions$1Entry
+ XXX.level.levelgen.WorldDimensions$Complete
+ XXX.level.levelgen.WorldGenerationContext
+ XXX.level.levelgen.WorldgenRandom
- XXX.level.levelgen.WorldgenRandom$Algorithm
- XXX.level.levelgen.WorldGenSettings
- XXX.level.levelgen.WorldOptions
+ XXX.level.levelgen.Xoroshiro128PlusPlus
- XXX.level.levelgen.XoroshiroRandomSource
+ XXX.level.levelgen.XoroshiroRandomSource$XoroshiroPositionalRandomFactory
- XXX.levelgen.blending.Blender
+ XXX.levelgen.blending.Blender$1
- XXX.levelgen.blending.Blender$BlendingOutput
+ XXX.levelgen.blending.Blender$CellValueGetter
- XXX.levelgen.blending.Blender$DistanceGetter
+ XXX.levelgen.blending.BlendingData
- XXX.levelgen.blending.BlendingData$BiomeConsumer
+ XXX.levelgen.blending.BlendingData$DensityConsumer
- XXX.levelgen.blending.BlendingData$HeightConsumer
+ XXX.levelgen.blending.package-info
- XXX.levelgen.blockpredicates.AllOfPredicate
+ XXX.levelgen.blockpredicates.AnyOfPredicate
- XXX.levelgen.blockpredicates.BlockPredicate
+ XXX.levelgen.blockpredicates.BlockPredicateType
- XXX.levelgen.blockpredicates.CombiningPredicate
+ XXX.levelgen.blockpredicates.HasSturdyFacePredicate
- XXX.levelgen.blockpredicates.InsideWorldBoundsPredicate
- XXX.levelgen.blockpredicates.MatchingBlocksPredicate
+ XXX.levelgen.blockpredicates.MatchingBlockTagPredicate
+ XXX.levelgen.blockpredicates.MatchingFluidsPredicate
- XXX.levelgen.blockpredicates.NotPredicate
- XXX.levelgen.blockpredicates.package-info
+ XXX.levelgen.blockpredicates.ReplaceablePredicate
- XXX.levelgen.blockpredicates.SolidPredicate
+ XXX.levelgen.blockpredicates.StateTestingPredicate
- XXX.levelgen.blockpredicates.TrueBlockPredicate
+ XXX.levelgen.blockpredicates.WouldSurvivePredicate
+ XXX.levelgen.carver.CanyonCarverConfiguration
- XXX.levelgen.carver.CanyonCarverConfiguration$CanyonShapeConfiguration
+ XXX.levelgen.carver.CanyonWorldCarver
- XXX.levelgen.carver.CarverConfiguration
+ XXX.levelgen.carver.CarverDebugSettings
- XXX.levelgen.carver.CarvingContext
+ XXX.levelgen.carver.CaveCarverConfiguration
- XXX.levelgen.carver.CaveWorldCarver
+ XXX.levelgen.carver.ConfiguredWorldCarver
- XXX.levelgen.carver.NetherWorldCarver
+ XXX.levelgen.carver.package-info
+ XXX.levelgen.carver.WorldCarver
- XXX.levelgen.carver.WorldCarver$CarveSkipChecker
- XXX.levelgen.feature.AbstractHugeMushroomFeature
+ XXX.levelgen.feature.BambooFeature
- XXX.levelgen.feature.BasaltColumnsFeature
+ XXX.levelgen.feature.BasaltPillarFeature
- XXX.levelgen.feature.BlockBlobFeature
+ XXX.levelgen.feature.BlockColumnFeature
- XXX.levelgen.feature.BlockPileFeature
+ XXX.levelgen.feature.BlueIceFeature
- XXX.levelgen.feature.BonusChestFeature
+ XXX.levelgen.feature.ChorusPlantFeature
- XXX.levelgen.feature.ConfiguredFeature
+ XXX.levelgen.feature.CoralClawFeature
- XXX.levelgen.feature.CoralFeature
+ XXX.levelgen.feature.CoralMushroomFeature
- XXX.levelgen.feature.CoralTreeFeature
- XXX.levelgen.feature.MonsterRoomFeature
+ XXX.levelgen.feature.MultifaceGrowthFeature
- XXX.levelgen.feature.NetherForestVegetationFeature
+ XXX.levelgen.feature.NoOpFeature
- XXX.levelgen.feature.OreFeature
+ XXX.levelgen.feature.PointedDripstoneFeature
- XXX.levelgen.feature.RandomBooleanSelectorFeature
+ XXX.levelgen.feature.RandomPatchFeature
- XXX.levelgen.feature.RandomSelectorFeature
+ XXX.levelgen.feature.ReplaceBlobsFeature
- XXX.levelgen.feature.ReplaceBlockFeature
+ XXX.levelgen.feature.RootSystemFeature
- XXX.levelgen.feature.ScatteredOreFeature
+ XXX.levelgen.feature.SculkPatchFeature
+ XXX.levelgen.feature.SeagrassFeature
- XXX.levelgen.feature.SeaPickleFeature
- XXX.levelgen.feature.SimpleBlockFeature
+ XXX.levelgen.feature.SimpleRandomSelectorFeature
- XXX.levelgen.feature.SnowAndFreezeFeature
+ XXX.levelgen.feature.SpikeFeature
- XXX.levelgen.feature.SpikeFeature$EndSpike
+ XXX.levelgen.feature.SpikeFeature$SpikeCacheLoader
- XXX.levelgen.feature.SpringFeature
+ XXX.levelgen.feature.TreeFeature
- XXX.levelgen.feature.TreeFeature$1
+ XXX.levelgen.feature.TwistingVinesFeature
- XXX.levelgen.feature.UnderwaterMagmaFeature
+ XXX.levelgen.feature.VegetationPatchFeature
- XXX.levelgen.feature.VinesFeature
+ XXX.levelgen.feature.VoidStartPlatformFeature
- XXX.levelgen.feature.WaterloggedVegetationPatchFeature
+ XXX.levelgen.feature.WeepingVinesFeature
- XXX.levelgen.feature.WeightedPlacedFeature
+ XXX.metadata.animation.AnimationFrame
- XXX.metadata.animation.AnimationMetadataSection
+ XXX.metadata.animation.AnimationMetadataSection$1
- XXX.metadata.animation.AnimationMetadataSection$FrameOutput
+ XXX.metadata.animation.AnimationMetadataSectionSerializer
- XXX.metadata.animation.FrameSize
- XXX.metadata.animation.package-info
+ XXX.metadata.animation.VillagerMetaDataSection
- XXX.metadata.animation.VillagerMetaDataSection$Hat
+ XXX.metadata.animation.VillagerMetadataSectionSerializer
+ XXX.metadata.language.LanguageMetadataSection
- XXX.metadata.language.package-info
- XXX.metadata.texture.package-info
- XXX.metadata.texture.TextureMetadataSection
+ XXX.metadata.texture.TextureMetadataSectionSerializer
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
+ XXX.minecraft.client.package-info
- XXX.minecraft.locale.Language
+ XXX.minecraft.locale.Language$1
- XXX.minecraft.locale.package-info
+ XXX.minecraft.nbt.ByteArrayTag
- XXX.minecraft.nbt.ByteArrayTag$1
+ XXX.minecraft.nbt.ByteTag
- XXX.minecraft.nbt.ByteTag$1
+ XXX.minecraft.nbt.ByteTag$Cache
- XXX.minecraft.nbt.CollectionTag
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
- XXX.minecraft.nbt.NbtAccounter$1
+ XXX.minecraft.nbt.NbtIo
- XXX.minecraft.nbt.NbtIo$1
+ XXX.minecraft.nbt.NbtOps
- XXX.minecraft.nbt.NbtOps$1
+ XXX.minecraft.nbt.NbtOps$ByteListCollector
- XXX.minecraft.nbt.NbtOps$HeterogenousListCollector
+ XXX.minecraft.nbt.NbtOps$HomogenousListCollector
- XXX.minecraft.nbt.NbtOps$InitialListCollector
+ XXX.minecraft.nbt.NbtOps$IntListCollector
- XXX.minecraft.nbt.NbtOps$ListCollector
+ XXX.minecraft.nbt.NbtOps$LongListCollector
- XXX.minecraft.nbt.NbtOps$NbtRecordBuilder
+ XXX.minecraft.nbt.NbtUtils
- XXX.minecraft.nbt.NumericTag
+ XXX.minecraft.nbt.package-info
+ XXX.minecraft.nbt.ShortTag
- XXX.minecraft.nbt.ShortTag$1
+ XXX.minecraft.nbt.ShortTag$Cache
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
- XXX.minecraft.network.CipherBase
+ XXX.minecraft.network.CipherDecoder
- XXX.minecraft.network.CipherEncoder
+ XXX.minecraft.network.CompressionDecoder
- XXX.minecraft.network.CompressionEncoder
+ XXX.minecraft.network.Connection
- XXX.minecraft.network.Connection$1
+ XXX.minecraft.network.Connection$2
- XXX.minecraft.network.Connection$PacketHolder
+ XXX.minecraft.network.ConnectionProtocol
- XXX.minecraft.network.ConnectionProtocol$PacketSet
+ XXX.minecraft.network.ConnectionProtocol$ProtocolBuilder
- XXX.minecraft.network.FriendlyByteBuf
+ XXX.minecraft.network.FriendlyByteBuf$1
- XXX.minecraft.network.FriendlyByteBuf$Reader
+ XXX.minecraft.network.FriendlyByteBuf$Writer
- XXX.minecraft.network.package-info
- XXX.minecraft.network.PacketBundlePacker
+ XXX.minecraft.network.PacketBundleUnpacker
- XXX.minecraft.network.PacketDecoder
+ XXX.minecraft.network.PacketEncoder
- XXX.minecraft.network.PacketListener
+ XXX.minecraft.network.PacketSendListener
- XXX.minecraft.network.PacketSendListener$1
+ XXX.minecraft.network.PacketSendListener$2
- XXX.minecraft.network.RateKickingConnection
+ XXX.minecraft.network.SkipPacketException
- XXX.minecraft.network.TickablePacketListener
+ XXX.minecraft.network.Varint21FrameDecoder
- XXX.minecraft.network.Varint21LengthFieldPrepender
- XXX.minecraft.obfuscate.DontObfuscate
+ XXX.minecraft.obfuscate.package-info
+ XXX.minecraft.realms.DisconnectedRealmsScreen
+ XXX.minecraft.realms.package-info
- XXX.minecraft.realms.RealmsConnect
+ XXX.minecraft.realms.RealmsConnect$1
- XXX.minecraft.realms.RealmsLabel
+ XXX.minecraft.realms.RealmsObjectSelectionList
- XXX.minecraft.realms.RealmsScreen
+ XXX.minecraft.realms.RepeatedNarrator
- XXX.minecraft.realms.RepeatedNarrator$Params
- XXX.minecraft.recipebook.package-info
- XXX.minecraft.recipebook.PlaceRecipe
+ XXX.minecraft.recipebook.ServerPlaceRecipe
+ XXX.minecraft.resources.DelegatingOps
- XXX.minecraft.resources.FileToIdConverter
+ XXX.minecraft.resources.HolderSetCodec
- XXX.minecraft.resources.package-info
- XXX.minecraft.resources.RegistryDataLoader
+ XXX.minecraft.resources.RegistryDataLoader$1
- XXX.minecraft.resources.RegistryDataLoader$Loader
+ XXX.minecraft.resources.RegistryDataLoader$RegistryData
- XXX.minecraft.resources.RegistryFileCodec
+ XXX.minecraft.resources.RegistryFixedCodec
- XXX.minecraft.resources.RegistryOps
+ XXX.minecraft.resources.RegistryOps$1
- XXX.minecraft.resources.RegistryOps$2
+ XXX.minecraft.resources.RegistryOps$RegistryInfo
- XXX.minecraft.resources.RegistryOps$RegistryInfoLookup
+ XXX.minecraft.resources.ResourceKey
- XXX.minecraft.resources.ResourceKey$InternKey
+ XXX.minecraft.resources.ResourceLocation
- XXX.minecraft.resources.ResourceLocation$Dummy
+ XXX.minecraft.resources.ResourceLocation$Serializer
+ XXX.minecraft.server.Bootstrap
- XXX.minecraft.server.Bootstrap$1
+ XXX.minecraft.server.ChainedJsonException
- XXX.minecraft.server.ChainedJsonException$Entry
+ XXX.minecraft.server.ConsoleInput
- XXX.minecraft.server.DebugLoggedPrintStream
+ XXX.minecraft.server.Eula
- XXX.minecraft.server.LoggedPrintStream
+ XXX.minecraft.server.Main
- XXX.minecraft.server.Main$1
+ XXX.minecraft.server.MinecraftServer
- XXX.minecraft.server.MinecraftServer$1
+ XXX.minecraft.server.MinecraftServer$ReloadableResources
- XXX.minecraft.server.MinecraftServer$ServerResourcePackInfo
+ XXX.minecraft.server.MinecraftServer$TimeProfiler
- XXX.minecraft.server.MinecraftServer$TimeProfiler$1
+ XXX.minecraft.server.PlayerAdvancements
- XXX.minecraft.server.PlayerAdvancements$1
+ XXX.minecraft.server.RegistryLayer
- XXX.minecraft.server.ReloadableServerResources
+ XXX.minecraft.server.RunningOnDifferentThreadException
- XXX.minecraft.server.ServerAdvancementManager
+ XXX.minecraft.server.ServerFunctionLibrary
- XXX.minecraft.server.ServerFunctionManager
+ XXX.minecraft.server.ServerFunctionManager$ExecutionContext
- XXX.minecraft.server.ServerFunctionManager$QueuedCommand
+ XXX.minecraft.server.ServerFunctionManager$TraceCallbacks
- XXX.minecraft.server.ServerInterface
+ XXX.minecraft.server.ServerScoreboard
- XXX.minecraft.server.ServerScoreboard$Method
+ XXX.minecraft.server.Services
- XXX.minecraft.server.TickTask
+ XXX.minecraft.server.WorldLoader
- XXX.minecraft.server.WorldLoader$DataLoadContext
+ XXX.minecraft.server.WorldLoader$DataLoadOutput
- XXX.minecraft.server.WorldLoader$InitConfig
+ XXX.minecraft.server.WorldLoader$PackConfig
- XXX.minecraft.server.WorldLoader$ResultFactory
+ XXX.minecraft.server.WorldLoader$WorldDataSupplier
- XXX.minecraft.server.WorldStem
+ XXX.minecraft.util.package-info
- XXX.minecraft.util.RgbTxt$Entry
- XXX.minecraft.voting.package-info
- XXX.minecraft.voting.VoteCommand
- XXX.model.dragon.DragonHeadModel
+ XXX.model.dragon.package-info
- XXX.model.geom.EntityModelSet
+ XXX.model.geom.LayerDefinitions
- XXX.model.geom.ModelLayerLocation
+ XXX.model.geom.ModelLayers
- XXX.model.geom.ModelPart
+ XXX.model.geom.ModelPart$Cube
- XXX.model.geom.ModelPart$Polygon
+ XXX.model.geom.ModelPart$Vertex
- XXX.model.geom.ModelPart$Visitor
- XXX.model.geom.package-info
+ XXX.model.geom.PartNames
- XXX.model.geom.PartPose
+ XXX.model.multipart.AndCondition
- XXX.model.multipart.Condition
+ XXX.model.multipart.KeyValueCondition
- XXX.model.multipart.MultiPart
+ XXX.model.multipart.MultiPart$Deserializer
- XXX.model.multipart.OrCondition
+ XXX.model.multipart.package-info
+ XXX.model.multipart.Selector
- XXX.model.multipart.Selector$Deserializer
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
+ XXX.multiplayer.chat.ChatListener
- XXX.multiplayer.chat.ChatListener$Message
+ XXX.multiplayer.chat.ChatLog
- XXX.multiplayer.chat.ChatTrustLevel
+ XXX.multiplayer.chat.ChatTrustLevel$1
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
- XXX.nbt.visitors.FieldSelector
+ XXX.nbt.visitors.FieldTree
+ XXX.nbt.visitors.package-info
- XXX.nbt.visitors.SkipAll
+ XXX.nbt.visitors.SkipAll$1
- XXX.nbt.visitors.SkipFields
+ XXX.network.chat.ChatDecorator
- XXX.network.chat.ChatType
+ XXX.network.chat.ChatType$Bound
- XXX.network.chat.ChatType$BoundNetwork
+ XXX.network.chat.ChatTypeDecoration
- XXX.network.chat.ChatTypeDecoration$Parameter
+ XXX.network.chat.ChatTypeDecoration$Parameter$Selector
- XXX.network.chat.ClickEvent
+ XXX.network.chat.ClickEvent$Action
- XXX.network.chat.CommonComponents
+ XXX.network.chat.Component
- XXX.network.chat.Component$Serializer
+ XXX.network.chat.ComponentContents
- XXX.network.chat.ComponentContents$1
+ XXX.network.chat.ComponentUtils
- XXX.network.chat.FilterMask
+ XXX.network.chat.FilterMask$1
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
+ XXX.network.chat.HoverEvent$ItemStackInfo
- XXX.network.chat.LastSeenMessages
+ XXX.network.chat.LastSeenMessages$Packed
- XXX.network.chat.LastSeenMessages$Update
+ XXX.network.chat.LastSeenMessagesTracker
- XXX.network.chat.LastSeenMessagesTracker$Update
+ XXX.network.chat.LastSeenMessagesValidator
- XXX.network.chat.LastSeenTrackedEntry
+ XXX.network.chat.LocalChatSession
- XXX.network.chat.MessageSignature
+ XXX.network.chat.MessageSignature$Packed
- XXX.network.chat.MessageSignatureCache
+ XXX.network.chat.MutableComponent
- XXX.network.chat.OutgoingChatMessage
+ XXX.network.chat.OutgoingChatMessage$Disguised
- XXX.network.chat.OutgoingChatMessage$Player
+ XXX.network.chat.package-info
+ XXX.network.chat.PlayerChatMessage
- XXX.network.chat.RemoteChatSession
+ XXX.network.chat.RemoteChatSession$Data
- XXX.network.chat.SignableCommand
+ XXX.network.chat.SignableCommand$Argument
- XXX.network.chat.SignedMessageBody
+ XXX.network.chat.SignedMessageBody$Packed
- XXX.network.chat.SignedMessageChain
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
+ XXX.network.protocol.BundleDelimiterPacket
- XXX.network.protocol.BundlePacket
+ XXX.network.protocol.BundlerInfo
- XXX.network.protocol.BundlerInfo$1
+ XXX.network.protocol.BundlerInfo$2
- XXX.network.protocol.BundlerInfo$2$1
+ XXX.network.protocol.BundlerInfo$Bundler
- XXX.network.protocol.BundlerInfo$Provider
- XXX.network.protocol.package-info
+ XXX.network.protocol.Packet
- XXX.network.protocol.PacketFlow
+ XXX.network.protocol.PacketUtils
- XXX.network.syncher.EntityDataAccessor
+ XXX.network.syncher.EntityDataSerializer
- XXX.network.syncher.EntityDataSerializer$1
+ XXX.network.syncher.EntityDataSerializer$ForValueType
- XXX.network.syncher.EntityDataSerializers
+ XXX.network.syncher.EntityDataSerializers$1
- XXX.network.syncher.EntityDataSerializers$2
+ XXX.network.syncher.EntityDataSerializers$3
- XXX.network.syncher.EntityDataSerializers$4
+ XXX.network.syncher.EntityDataSerializers$5
- XXX.network.syncher.EntityDataSerializers$6
+ XXX.network.syncher.EntityDataSerializers$7
+ XXX.network.syncher.package-info
- XXX.network.syncher.SynchedEntityData
+ XXX.network.syncher.SynchedEntityData$DataItem
- XXX.network.syncher.SynchedEntityData$DataValue
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
+ XXX.protocol.game.ClientboundAddEntityPacket
- XXX.protocol.game.ClientboundAddExperienceOrbPacket
+ XXX.protocol.game.ClientboundAddPlayerPacket
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
- XXX.protocol.game.ClientboundSetCarriedItemPacket
+ XXX.protocol.game.ClientboundSetChunkCacheCenterPacket
- XXX.protocol.game.ClientboundSetChunkCacheRadiusPacket
+ XXX.protocol.game.ClientboundSetDefaultSpawnPositionPacket
- XXX.protocol.game.ClientboundSetDisplayObjectivePacket
+ XXX.protocol.game.ClientboundSetEntityDataPacket
- XXX.protocol.game.ClientboundSetEntityLinkPacket
+ XXX.protocol.game.ClientboundSetEntityMotionPacket
- XXX.protocol.game.ClientboundSetEquipmentPacket
+ XXX.protocol.game.ClientboundSetExperiencePacket
- XXX.protocol.game.ClientboundSetHealthPacket
+ XXX.protocol.game.ClientboundSetObjectivePacket
- XXX.protocol.game.ClientboundSetPassengersPacket
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
- XXX.protocol.game.ClientboundStopSoundPacket
+ XXX.protocol.game.ClientboundSystemChatPacket
- XXX.protocol.game.ClientboundTabListPacket
+ XXX.protocol.game.ClientboundTagQueryPacket
- XXX.protocol.game.ClientboundTakeItemEntityPacket
+ XXX.protocol.game.ClientboundTeleportEntityPacket
- XXX.protocol.game.ClientboundUpdateAdvancementsPacket
+ XXX.protocol.game.ClientboundUpdateAttributesPacket
- XXX.protocol.game.ClientboundUpdateAttributesPacket$AttributeSnapshot
+ XXX.protocol.game.ClientboundUpdateEnabledFeaturesPacket
- XXX.protocol.game.ClientboundUpdateMobEffectPacket
+ XXX.protocol.game.ClientboundUpdateRecipesPacket
- XXX.protocol.game.ClientboundUpdateTagsPacket
- XXX.protocol.game.ClientboundVoteFinishPacket
- XXX.protocol.game.ClientboundVoteStartPacket
- XXX.protocol.game.ClientGamePacketListener
+ XXX.protocol.game.DebugEntityNameGenerator
- XXX.protocol.game.DebugPackets
+ XXX.protocol.game.package-info
+ XXX.protocol.game.ServerboundAcceptTeleportationPacket
- XXX.protocol.game.ServerboundBlockEntityTagQuery
+ XXX.protocol.game.ServerboundChangeDifficultyPacket
- XXX.protocol.game.ServerboundChatAckPacket
+ XXX.protocol.game.ServerboundChatCommandPacket
- XXX.protocol.game.ServerboundChatPacket
+ XXX.protocol.game.ServerboundChatSessionUpdatePacket
- XXX.protocol.game.ServerboundClientCommandPacket
+ XXX.protocol.game.ServerboundClientCommandPacket$Action
- XXX.protocol.game.ServerboundClientInformationPacket
+ XXX.protocol.game.ServerboundCommandSuggestionPacket
- XXX.protocol.game.ServerboundContainerButtonClickPacket
+ XXX.protocol.game.ServerboundContainerClickPacket
- XXX.protocol.game.ServerboundContainerClosePacket
+ XXX.protocol.game.ServerGamePacketListener
- XXX.protocol.game.ServerPacketListener
- XXX.protocol.game.VecDeltaCodec
- XXX.protocol.handshake.ClientIntentionPacket
- XXX.protocol.handshake.package-info
+ XXX.protocol.handshake.ServerHandshakePacketListener
- XXX.protocol.login.ClientboundCustomQueryPacket
+ XXX.protocol.login.ClientboundGameProfilePacket
- XXX.protocol.login.ClientboundHelloPacket
+ XXX.protocol.login.ClientboundLoginCompressionPacket
- XXX.protocol.login.ClientboundLoginDisconnectPacket
+ XXX.protocol.login.ClientLoginPacketListener
+ XXX.protocol.login.package-info
- XXX.protocol.login.ServerboundCustomQueryPacket
+ XXX.protocol.login.ServerboundHelloPacket
- XXX.protocol.login.ServerboundKeyPacket
+ XXX.protocol.login.ServerLoginPacketListener
- XXX.protocol.status.ClientboundPongResponsePacket
+ XXX.protocol.status.ClientboundStatusResponsePacket
+ XXX.protocol.status.ClientStatusPacketListener
+ XXX.protocol.status.package-info
+ XXX.protocol.status.ServerboundPingRequestPacket
- XXX.protocol.status.ServerboundStatusRequestPacket
- XXX.protocol.status.ServerStatus
+ XXX.protocol.status.ServerStatus$Favicon
- XXX.protocol.status.ServerStatus$Players
+ XXX.protocol.status.ServerStatus$Version
- XXX.protocol.status.ServerStatusPacketListener
+ XXX.renderer.block.BlockModelShaper
- XXX.renderer.block.BlockRenderDispatcher
+ XXX.renderer.block.BlockRenderDispatcher$1
- XXX.renderer.block.LiquidBlockRenderer
+ XXX.renderer.block.LiquidBlockRenderer$1
- XXX.renderer.block.ModelBlockRenderer
+ XXX.renderer.block.ModelBlockRenderer$1
- XXX.renderer.block.ModelBlockRenderer$AdjacencyInfo
+ XXX.renderer.block.ModelBlockRenderer$AmbientOcclusionFace
- XXX.renderer.block.ModelBlockRenderer$AmbientVertexRemap
+ XXX.renderer.block.ModelBlockRenderer$Cache
- XXX.renderer.block.ModelBlockRenderer$Cache$1
+ XXX.renderer.block.ModelBlockRenderer$Cache$2
- XXX.renderer.block.ModelBlockRenderer$SizeInfo
+ XXX.renderer.block.package-info
- XXX.renderer.blockentity.BannerRenderer
+ XXX.renderer.blockentity.BeaconRenderer
- XXX.renderer.blockentity.BedRenderer
+ XXX.renderer.blockentity.BellRenderer
- XXX.renderer.blockentity.BlockEntityRenderDispatcher
+ XXX.renderer.blockentity.BlockEntityRenderer
- XXX.renderer.blockentity.BlockEntityRendererProvider
+ XXX.renderer.blockentity.BlockEntityRendererProvider$Context
- XXX.renderer.blockentity.BlockEntityRenderers
+ XXX.renderer.blockentity.BrightnessCombiner
- XXX.renderer.blockentity.BrushableBlockRenderer
+ XXX.renderer.blockentity.BrushableBlockRenderer$1
- XXX.renderer.blockentity.CampfireRenderer
+ XXX.renderer.blockentity.ChestRenderer
- XXX.renderer.blockentity.ConduitRenderer
+ XXX.renderer.blockentity.DecoratedPotRenderer
- XXX.renderer.blockentity.EnchantTableRenderer
+ XXX.renderer.blockentity.HangingSignRenderer
- XXX.renderer.blockentity.HangingSignRenderer$HangingSignModel
+ XXX.renderer.blockentity.LecternRenderer
- XXX.renderer.blockentity.package-info
- XXX.renderer.blockentity.PistonHeadRenderer
+ XXX.renderer.blockentity.ShulkerBoxRenderer
- XXX.renderer.blockentity.SignRenderer
+ XXX.renderer.blockentity.SignRenderer$SignModel
- XXX.renderer.blockentity.SkullBlockRenderer
+ XXX.renderer.blockentity.SpawnerRenderer
- XXX.renderer.blockentity.StructureBlockRenderer
+ XXX.renderer.blockentity.StructureBlockRenderer$1
- XXX.renderer.blockentity.TheEndGatewayRenderer
+ XXX.renderer.blockentity.TheEndPortalRenderer
+ XXX.renderer.chunk.ChunkRenderDispatcher
- XXX.renderer.chunk.ChunkRenderDispatcher$ChunkTaskResult
+ XXX.renderer.chunk.ChunkRenderDispatcher$CompiledChunk
- XXX.renderer.chunk.ChunkRenderDispatcher$CompiledChunk$1
+ XXX.renderer.chunk.ChunkRenderDispatcher$RenderChunk
- XXX.renderer.chunk.ChunkRenderDispatcher$RenderChunk$ChunkCompileTask
+ XXX.renderer.chunk.ChunkRenderDispatcher$RenderChunk$RebuildTask
- XXX.renderer.chunk.ChunkRenderDispatcher$RenderChunk$RebuildTask$CompileResults
+ XXX.renderer.chunk.ChunkRenderDispatcher$RenderChunk$ResortTransparencyTask
+ XXX.renderer.chunk.package-info
- XXX.renderer.chunk.RenderChunk
+ XXX.renderer.chunk.RenderChunkRegion
- XXX.renderer.chunk.RenderRegionCache
+ XXX.renderer.chunk.RenderRegionCache$ChunkInfo
- XXX.renderer.chunk.VisGraph
+ XXX.renderer.chunk.VisGraph$1
- XXX.renderer.chunk.VisibilitySet
- XXX.renderer.culling.Frustum
+ XXX.renderer.culling.package-info
- XXX.renderer.debug.BeeDebugRenderer
+ XXX.renderer.debug.BeeDebugRenderer$BeeInfo
- XXX.renderer.debug.BeeDebugRenderer$HiveInfo
+ XXX.renderer.debug.BrainDebugRenderer
- XXX.renderer.debug.BrainDebugRenderer$BrainDump
+ XXX.renderer.debug.BrainDebugRenderer$PoiInfo
- XXX.renderer.debug.ChunkBorderRenderer
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
- XXX.renderer.debug.GoalSelectorDebugRenderer$DebugGoal
+ XXX.renderer.debug.HeightMapRenderer
- XXX.renderer.debug.HeightMapRenderer$1
+ XXX.renderer.debug.LightDebugRenderer
- XXX.renderer.debug.NeighborsUpdateRenderer
- XXX.renderer.debug.package-info
+ XXX.renderer.debug.PathfindingRenderer
- XXX.renderer.debug.RaidDebugRenderer
+ XXX.renderer.debug.SolidFaceRenderer
- XXX.renderer.debug.StructureRenderer
+ XXX.renderer.debug.VillageSectionsDebugRenderer
- XXX.renderer.debug.WaterDebugRenderer
+ XXX.renderer.debug.WorldGenAttemptRenderer
+ XXX.renderer.entity.AbstractHorseRenderer
- XXX.renderer.entity.AbstractZombieRenderer
+ XXX.renderer.entity.AllayRenderer
- XXX.renderer.entity.ArmorStandRenderer
+ XXX.renderer.entity.ArrowRenderer
- XXX.renderer.entity.AxolotlRenderer
+ XXX.renderer.entity.BatRenderer
- XXX.renderer.entity.BeeRenderer
+ XXX.renderer.entity.BlazeRenderer
- XXX.renderer.entity.BoatRenderer
+ XXX.renderer.entity.CamelRenderer
- XXX.renderer.entity.CatRenderer
+ XXX.renderer.entity.CaveSpiderRenderer
- XXX.renderer.entity.ChestedHorseRenderer
+ XXX.renderer.entity.ChickenRenderer
- XXX.renderer.entity.CodRenderer
+ XXX.renderer.entity.CowRenderer
- XXX.renderer.entity.CreeperRenderer
+ XXX.renderer.entity.DisplayRenderer
- XXX.renderer.entity.DisplayRenderer$1
+ XXX.renderer.entity.DisplayRenderer$BlockDisplayRenderer
- XXX.renderer.entity.DisplayRenderer$ItemDisplayRenderer
- XXX.renderer.entity.MoonCowRenderer
+ XXX.renderer.entity.MushroomCowRenderer
- XXX.renderer.entity.NoopRenderer
+ XXX.renderer.entity.OcelotRenderer
- XXX.renderer.entity.PaintingRenderer
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
- XXX.renderer.entity.RavagerRenderer
- XXX.renderer.entity.StencilRenderer$Triangle
- XXX.renderer.item.ClampedItemPropertyFunction
+ XXX.renderer.item.CompassItemPropertyFunction
- XXX.renderer.item.CompassItemPropertyFunction$CompassTarget
+ XXX.renderer.item.CompassItemPropertyFunction$CompassWobble
- XXX.renderer.item.ItemProperties
+ XXX.renderer.item.ItemProperties$1
- XXX.renderer.item.ItemPropertyFunction
+ XXX.renderer.item.package-info
+ XXX.renderer.texture.AbstractTexture
- XXX.renderer.texture.Dumpable
+ XXX.renderer.texture.DynamicTexture
- XXX.renderer.texture.HttpTexture
+ XXX.renderer.texture.MipmapGenerator
- XXX.renderer.texture.MissingTextureAtlasSprite
+ XXX.renderer.texture.OverlayTexture
+ XXX.renderer.texture.package-info
- XXX.renderer.texture.PreloadedTexture
+ XXX.renderer.texture.SimpleTexture
- XXX.renderer.texture.SimpleTexture$TextureImage
+ XXX.renderer.texture.SpriteContents
- XXX.renderer.texture.SpriteContents$AnimatedTexture
+ XXX.renderer.texture.SpriteContents$FrameInfo
- XXX.renderer.texture.SpriteContents$InterpolationData
+ XXX.renderer.texture.SpriteContents$Ticker
- XXX.renderer.texture.SpriteLoader
+ XXX.renderer.texture.SpriteLoader$Preparations
- XXX.renderer.texture.SpriteTicker
+ XXX.renderer.texture.Stitcher
- XXX.renderer.texture.Stitcher$Entry
+ XXX.renderer.texture.Stitcher$Holder
- XXX.renderer.texture.Stitcher$Region
+ XXX.renderer.texture.Stitcher$SpriteLoader
- XXX.renderer.texture.StitcherException
+ XXX.renderer.texture.TextureAtlas
- XXX.renderer.texture.TextureAtlasSprite
+ XXX.renderer.texture.TextureAtlasSprite$1
- XXX.renderer.texture.TextureAtlasSprite$Ticker
+ XXX.renderer.texture.TextureManager
- XXX.renderer.texture.Tickable
+ XXX.resources.language.ClientLanguage
- XXX.resources.language.FormattedBidiReorder
+ XXX.resources.language.I18n
- XXX.resources.language.LanguageInfo
+ XXX.resources.language.LanguageManager
- XXX.resources.language.package-info
+ XXX.resources.metadata.package-info
+ XXX.resources.model.AtlasSet
- XXX.resources.model.AtlasSet$AtlasEntry
+ XXX.resources.model.AtlasSet$StitchResult
- XXX.resources.model.BakedModel
+ XXX.resources.model.BlockModelRotation
- XXX.resources.model.BuiltInModel
+ XXX.resources.model.Material
- XXX.resources.model.ModelBaker
+ XXX.resources.model.ModelBakery
- XXX.resources.model.ModelBakery$BakedCacheKey
+ XXX.resources.model.ModelBakery$BlockStateDefinitionException
- XXX.resources.model.ModelBakery$LoadedJson
+ XXX.resources.model.ModelBakery$ModelBakerImpl
- XXX.resources.model.ModelBakery$ModelGroupKey
+ XXX.resources.model.ModelManager
- XXX.resources.model.ModelManager$ReloadState
+ XXX.resources.model.ModelResourceLocation
- XXX.resources.model.ModelState
+ XXX.resources.model.MultiPartBakedModel
- XXX.resources.model.MultiPartBakedModel$Builder
- XXX.resources.model.package-info
+ XXX.resources.model.SimpleBakedModel
- XXX.resources.model.SimpleBakedModel$Builder
+ XXX.resources.model.UnbakedModel
- XXX.resources.model.WeightedBakedModel
+ XXX.resources.model.WeightedBakedModel$Builder
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
+ XXX.resources.sounds.package-info
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
- XXX.rules.actual.AutoJumpAlternatives
- XXX.rules.actual.BinaryGameRuleRule$RuleRuleChange
- XXX.rules.actual.BlockFlammabilityRule
- XXX.rules.actual.BlockMapRule
- XXX.rules.actual.BlockModelReplacementRule$PotentialEntry
- XXX.rules.actual.BlockReplaceSingleRule
- XXX.rules.actual.ChickenEggRule
- XXX.rules.actual.CodepointStyleRule
- XXX.rules.actual.ColorRule
- XXX.rules.actual.CopySkinRule$CopySkinRuleChange
- XXX.rules.actual.DoubleOrHalfDamageTypeMapRule
- XXX.rules.actual.ExplosionExtraPowerRule
- XXX.rules.actual.FoodType
- XXX.rules.actual.GiveEffectRule
- XXX.rules.actual.Goldifier
- XXX.rules.actual.IntegerGameRuleRule
- XXX.rules.actual.ItemDespawnTime
- XXX.rules.actual.ItemGiveRule
- XXX.rules.actual.ItemModelReplacementRule
- XXX.rules.actual.LavaReplaceRule
- XXX.rules.actual.LightEngineMode$1
- XXX.rules.actual.NameVisiblity
- XXX.rules.actual.OptimizationRule
- XXX.rules.actual.ParentTrapRule$ParentTrapRuleChange
- XXX.rules.actual.PlayerSetRule
- XXX.rules.actual.RecipeFlip
- XXX.rules.actual.ReplaceItemsRule$ItemGenerator
- XXX.rules.actual.RuleFeatureToggles
- XXX.rules.actual.TheJokeRule
- XXX.rules.actual.ThreadedAnvilChunkStorage
- XXX.rules.actual.ThreadedAnvilChunkStorage$Change
- XXX.rules.actual.TransformEntityRule$TransformRuleChange
- XXX.rules.actual.TransformScaleRule$ScaleRuleChange
- XXX.rules.actual.VillagerPaymentRule
- XXX.rules.actual.WorldShape
+ XXX.screens.achievement.package-info
- XXX.screens.achievement.StatsScreen
+ XXX.screens.achievement.StatsScreen$GeneralStatisticsList
- XXX.screens.achievement.StatsScreen$GeneralStatisticsList$Entry
+ XXX.screens.achievement.StatsScreen$ItemStatisticsList
- XXX.screens.achievement.StatsScreen$ItemStatisticsList$ItemRow
+ XXX.screens.achievement.StatsScreen$ItemStatisticsList$ItemRowComparator
- XXX.screens.achievement.StatsScreen$MobsStatisticsList
+ XXX.screens.achievement.StatsScreen$MobsStatisticsList$MobRow
- XXX.screens.achievement.StatsUpdateListener
+ XXX.screens.advancements.AdvancementsScreen
- XXX.screens.advancements.AdvancementTab
+ XXX.screens.advancements.AdvancementTabType
- XXX.screens.advancements.AdvancementTabType$1
+ XXX.screens.advancements.AdvancementWidget
- XXX.screens.advancements.AdvancementWidgetType
- XXX.screens.advancements.package-info
+ XXX.screens.controls.ControlsScreen
- XXX.screens.controls.KeyBindsList
+ XXX.screens.controls.KeyBindsList$CategoryEntry
- XXX.screens.controls.KeyBindsList$CategoryEntry$1
+ XXX.screens.controls.KeyBindsList$Entry
- XXX.screens.controls.KeyBindsList$KeyEntry
+ XXX.screens.controls.KeyBindsScreen
- XXX.screens.controls.package-info
+ XXX.screens.debug.GameModeSwitcherScreen
- XXX.screens.debug.GameModeSwitcherScreen$1
+ XXX.screens.debug.GameModeSwitcherScreen$GameModeIcon
- XXX.screens.debug.GameModeSwitcherScreen$GameModeSlot
+ XXX.screens.debug.package-info
- XXX.screens.inventory.AbstractCommandBlockEditScreen
+ XXX.screens.inventory.AbstractCommandBlockEditScreen$1
- XXX.screens.inventory.AbstractContainerScreen
+ XXX.screens.inventory.AbstractFurnaceScreen
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
+ XXX.screens.inventory.BookEditScreen$DisplayCache
- XXX.screens.inventory.BookEditScreen$LineInfo
+ XXX.screens.inventory.BookEditScreen$Pos2i
- XXX.screens.inventory.BookViewScreen
+ XXX.screens.inventory.BookViewScreen$1
- XXX.screens.inventory.BookViewScreen$BookAccess
+ XXX.screens.inventory.BookViewScreen$WritableBookAccess
- XXX.screens.inventory.BookViewScreen$WrittenBookAccess
+ XXX.screens.inventory.BrewingStandScreen
- XXX.screens.inventory.CartographyTableScreen
+ XXX.screens.inventory.CommandBlockEditScreen
- XXX.screens.inventory.CommandBlockEditScreen$1
+ XXX.screens.inventory.ContainerScreen
- XXX.screens.inventory.CraftingScreen
+ XXX.screens.inventory.CreativeInventoryListener
- XXX.screens.inventory.CreativeModeInventoryScreen
+ XXX.screens.inventory.CreativeModeInventoryScreen$CustomCreativeSlot
- XXX.screens.inventory.CreativeModeInventoryScreen$ItemPickerMenu
+ XXX.screens.inventory.CreativeModeInventoryScreen$SlotWrapper
- XXX.screens.inventory.CyclingSlotBackground
+ XXX.screens.inventory.DispenserScreen
- XXX.screens.inventory.EffectRenderingInventoryScreen
+ XXX.screens.inventory.EnchantmentNames
- XXX.screens.inventory.EnchantmentScreen
+ XXX.screens.inventory.FurnaceScreen
- XXX.screens.inventory.GrindstoneScreen
+ XXX.screens.inventory.HangingSignEditScreen
- XXX.screens.inventory.HopperScreen
+ XXX.screens.inventory.HorseInventoryScreen
- XXX.screens.inventory.InventoryScreen
+ XXX.screens.inventory.ItemCombinerScreen
- XXX.screens.inventory.JigsawBlockEditScreen
+ XXX.screens.inventory.JigsawBlockEditScreen$1
- XXX.screens.inventory.LecternScreen
+ XXX.screens.inventory.LecternScreen$1
- XXX.screens.inventory.LoomScreen
+ XXX.screens.inventory.MenuAccess
- XXX.screens.inventory.MerchantScreen
+ XXX.screens.inventory.MerchantScreen$TradeOfferButton
- XXX.screens.inventory.MinecartCommandBlockEditScreen
- XXX.screens.inventory.package-info
+ XXX.screens.inventory.PageButton
- XXX.screens.inventory.ShulkerBoxScreen
+ XXX.screens.inventory.SignEditScreen
- XXX.screens.inventory.SmithingScreen
+ XXX.screens.inventory.SmokerScreen
- XXX.screens.inventory.StonecutterScreen
+ XXX.screens.inventory.StructureBlockEditScreen
- XXX.screens.inventory.StructureBlockEditScreen$1
+ XXX.screens.inventory.StructureBlockEditScreen$2
- XXX.screens.multiplayer.JoinMultiplayerScreen
+ XXX.screens.multiplayer.package-info
+ XXX.screens.multiplayer.Realms32bitWarningScreen
- XXX.screens.multiplayer.SafetyScreen
+ XXX.screens.multiplayer.ServerSelectionList
- XXX.screens.multiplayer.ServerSelectionList$Entry
+ XXX.screens.multiplayer.ServerSelectionList$LANHeader
- XXX.screens.multiplayer.ServerSelectionList$NetworkServerEntry
+ XXX.screens.multiplayer.ServerSelectionList$OnlineServerEntry
- XXX.screens.multiplayer.WarningScreen
- XXX.screens.packs.package-info
+ XXX.screens.packs.PackSelectionModel
- XXX.screens.packs.PackSelectionModel$Entry
+ XXX.screens.packs.PackSelectionModel$EntryBase
- XXX.screens.packs.PackSelectionModel$SelectedPackEntry
+ XXX.screens.packs.PackSelectionModel$UnselectedPackEntry
- XXX.screens.packs.PackSelectionScreen
+ XXX.screens.packs.PackSelectionScreen$Watcher
- XXX.screens.packs.TransferableSelectionList
+ XXX.screens.packs.TransferableSelectionList$PackEntry
+ XXX.screens.recipebook.AbstractFurnaceRecipeBookComponent
- XXX.screens.recipebook.BlastingRecipeBookComponent
+ XXX.screens.recipebook.GhostRecipe
- XXX.screens.recipebook.GhostRecipe$GhostIngredient
+ XXX.screens.recipebook.OverlayRecipeComponent
- XXX.screens.recipebook.OverlayRecipeComponent$OverlayRecipeButton
+ XXX.screens.recipebook.OverlayRecipeComponent$OverlayRecipeButton$Pos
- XXX.screens.recipebook.OverlayRecipeComponent$OverlaySmeltingRecipeButton
- XXX.screens.recipebook.package-info
+ XXX.screens.recipebook.RecipeBookComponent
- XXX.screens.recipebook.RecipeBookPage
+ XXX.screens.recipebook.RecipeBookTabButton
- XXX.screens.recipebook.RecipeButton
+ XXX.screens.recipebook.RecipeCollection
- XXX.screens.recipebook.RecipeShownListener
+ XXX.screens.recipebook.RecipeUpdateListener
- XXX.screens.recipebook.SmeltingRecipeBookComponent
+ XXX.screens.recipebook.SmokingRecipeBookComponent
+ XXX.screens.reporting.ChatReportScreen
- XXX.screens.reporting.ChatReportScreen$DiscardReportWarningScreen
+ XXX.screens.reporting.ChatSelectionLogFiller
- XXX.screens.reporting.ChatSelectionLogFiller$Output
+ XXX.screens.reporting.ChatSelectionScreen
- XXX.screens.reporting.ChatSelectionScreen$ChatSelectionList
+ XXX.screens.reporting.ChatSelectionScreen$ChatSelectionList$DividerEntry
- XXX.screens.reporting.ChatSelectionScreen$ChatSelectionList$Entry
+ XXX.screens.reporting.ChatSelectionScreen$ChatSelectionList$Heading
- XXX.screens.reporting.ChatSelectionScreen$ChatSelectionList$MessageEntry
+ XXX.screens.reporting.ChatSelectionScreen$ChatSelectionList$MessageHeadingEntry
- XXX.screens.reporting.ChatSelectionScreen$ChatSelectionList$PaddingEntry
- XXX.screens.reporting.package-info
+ XXX.screens.reporting.ReportReasonSelectionScreen
- XXX.screens.reporting.ReportReasonSelectionScreen$ReasonSelectionList
+ XXX.screens.reporting.ReportReasonSelectionScreen$ReasonSelectionList$Entry
+ XXX.screens.social.package-info
+ XXX.screens.social.PlayerEntry
- XXX.screens.social.PlayerEntry$1
+ XXX.screens.social.PlayerEntry$2
- XXX.screens.social.PlayerEntry$3
+ XXX.screens.social.PlayerSocialManager
- XXX.screens.social.SocialInteractionsPlayerList
+ XXX.screens.social.SocialInteractionsScreen
- XXX.screens.social.SocialInteractionsScreen$1
+ XXX.screens.social.SocialInteractionsScreen$2
- XXX.screens.social.SocialInteractionsScreen$Page
- XXX.screens.telemetry.package-info
- XXX.screens.telemetry.TelemetryEventWidget
+ XXX.screens.telemetry.TelemetryEventWidget$Content
- XXX.screens.telemetry.TelemetryEventWidget$ContentBuilder
+ XXX.screens.telemetry.TelemetryInfoScreen
- XXX.screens.voting.package-info
- XXX.screens.voting.VoteSelectionEntry
- XXX.screens.voting.VoteSelectionScreen
- XXX.screens.voting.VotingScreen$1
- XXX.screens.voting.VotingScreen$3
- XXX.screens.voting.VotingScreen$FakeAndTerrible
- XXX.screens.voting.VotingScreen$OptionSelectButton
+ XXX.screens.worldselection.ConfirmExperimentalFeaturesScreen
- XXX.screens.worldselection.ConfirmExperimentalFeaturesScreen$DetailsScreen
+ XXX.screens.worldselection.ConfirmExperimentalFeaturesScreen$DetailsScreen$PackList
- XXX.screens.worldselection.ConfirmExperimentalFeaturesScreen$DetailsScreen$PackListEntry
+ XXX.screens.worldselection.CreateWorldScreen
- XXX.screens.worldselection.CreateWorldScreen$DataPackReloadCookie
+ XXX.screens.worldselection.CreateWorldScreen$GameTab
- XXX.screens.worldselection.CreateWorldScreen$MoreTab
+ XXX.screens.worldselection.CreateWorldScreen$WorldTab
- XXX.screens.worldselection.CreateWorldScreen$WorldTab$1
+ XXX.screens.worldselection.CreateWorldScreen$WorldTab$2
- XXX.screens.worldselection.EditGameRulesScreen
+ XXX.screens.worldselection.EditGameRulesScreen$BooleanRuleEntry
- XXX.screens.worldselection.EditGameRulesScreen$CategoryRuleEntry
+ XXX.screens.worldselection.EditGameRulesScreen$CategoryRuleEntry$1
- XXX.screens.worldselection.EditGameRulesScreen$EntryFactory
+ XXX.screens.worldselection.EditGameRulesScreen$GameRuleEntry
- XXX.screens.worldselection.EditGameRulesScreen$IntegerRuleEntry
+ XXX.screens.worldselection.EditGameRulesScreen$RuleEntry
- XXX.screens.worldselection.EditGameRulesScreen$RuleList
+ XXX.screens.worldselection.EditGameRulesScreen$RuleList$1
- XXX.screens.worldselection.EditWorldScreen
+ XXX.screens.worldselection.ExperimentsScreen
- XXX.screens.worldselection.OptimizeWorldScreen
- XXX.screens.worldselection.package-info
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
+ XXX.screens.worldselection.WorldCreationUiState
- XXX.screens.worldselection.WorldCreationUiState$SelectedGameMode
+ XXX.screens.worldselection.WorldCreationUiState$WorldTypeEntry
- XXX.screens.worldselection.WorldOpenFlows
+ XXX.screens.worldselection.WorldOpenFlows$1Data
- XXX.screens.worldselection.WorldSelectionList
+ XXX.screens.worldselection.WorldSelectionList$Entry
- XXX.screens.worldselection.WorldSelectionList$LoadingHeader
+ XXX.screens.worldselection.WorldSelectionList$WorldListEntry
+ XXX.server.advancements.AdvancementVisibilityEvaluator
- XXX.server.advancements.AdvancementVisibilityEvaluator$Output
+ XXX.server.advancements.AdvancementVisibilityEvaluator$VisibilityRule
- XXX.server.advancements.package-info
+ XXX.server.bossevents.CustomBossEvent
- XXX.server.bossevents.CustomBossEvents
+ XXX.server.bossevents.package-info
- XXX.server.chase.ChaseClient
+ XXX.server.chase.ChaseClient$TeleportTarget
- XXX.server.chase.ChaseServer
+ XXX.server.chase.ChaseServer$PlayerPosition
- XXX.server.chase.package-info
+ XXX.server.commands.AdvancementCommands
- XXX.server.commands.AdvancementCommands$Action
+ XXX.server.commands.AdvancementCommands$Action$1
- XXX.server.commands.AdvancementCommands$Action$2
+ XXX.server.commands.AdvancementCommands$Mode
- XXX.server.commands.AttributeCommand
+ XXX.server.commands.BanIpCommands
- XXX.server.commands.BanListCommands
+ XXX.server.commands.BanPlayerCommands
- XXX.server.commands.BossBarCommands
+ XXX.server.commands.ChaseCommand
- XXX.server.commands.ClearInventoryCommands
+ XXX.server.commands.CloneCommands
- XXX.server.commands.CloneCommands$CloneBlockInfo
+ XXX.server.commands.CloneCommands$CommandFunction
- XXX.server.commands.CloneCommands$DimensionAndPosition
+ XXX.server.commands.CloneCommands$Mode
- XXX.server.commands.DamageCommand
+ XXX.server.commands.DataPackCommand
- XXX.server.commands.DataPackCommand$Inserter
- XXX.server.commands.DebugCommand
+ XXX.server.commands.DebugCommand$Tracer
- XXX.server.commands.DebugMobSpawningCommand
+ XXX.server.commands.DebugPathCommand
- XXX.server.commands.DefaultGameModeCommands
+ XXX.server.commands.DeOpCommands
+ XXX.server.commands.DifficultyCommand
- XXX.server.commands.EffectCommands
+ XXX.server.commands.EmoteCommands
- XXX.server.commands.EnchantCommand
+ XXX.server.commands.ExecuteCommand
- XXX.server.commands.ExecuteCommand$CommandNumericPredicate
+ XXX.server.commands.ExecuteCommand$CommandPredicate
- XXX.server.commands.ExperienceCommand
+ XXX.server.commands.ExperienceCommand$Type
- XXX.server.commands.FillBiomeCommand
+ XXX.server.commands.FillCommand
- XXX.server.commands.FillCommand$Mode
+ XXX.server.commands.ForceLoadCommand
- XXX.server.commands.FunctionCommand
+ XXX.server.commands.GameModeCommand
- XXX.server.commands.GameRuleCommand
+ XXX.server.commands.GameRuleCommand$1
- XXX.server.commands.GiveCommand
+ XXX.server.commands.HelpCommand
- XXX.server.commands.ItemCommands
+ XXX.server.commands.JfrCommand
- XXX.server.commands.KickCommand
+ XXX.server.commands.KillCommand
- XXX.server.commands.ListPlayersCommand
+ XXX.server.commands.LocateCommand
- XXX.server.commands.LootCommand
+ XXX.server.commands.LootCommand$Callback
- XXX.server.commands.LootCommand$DropConsumer
+ XXX.server.commands.LootCommand$TailProvider
- XXX.server.commands.MsgCommand
+ XXX.server.commands.OpCommand
+ XXX.server.commands.package-info
- XXX.server.commands.PardonCommand
+ XXX.server.commands.PardonIpCommand
- XXX.server.commands.ParticleCommand
+ XXX.server.commands.PerfCommand
- XXX.server.commands.PlaceCommand
+ XXX.server.commands.PlaySoundCommand
- XXX.server.commands.PublishCommand
+ XXX.server.commands.RaidCommand
- XXX.server.commands.RecipeCommand
+ XXX.server.commands.ReloadCommand
- XXX.server.commands.ResetChunksCommand
+ XXX.server.commands.RideCommand
- XXX.server.commands.SaveAllCommand
+ XXX.server.commands.SaveOffCommand
- XXX.server.commands.SaveOnCommand
+ XXX.server.commands.SayCommand
- XXX.server.commands.ScheduleCommand
+ XXX.server.commands.ScoreboardCommand
- XXX.server.commands.SeedCommand
+ XXX.server.commands.SetBlockCommand
- XXX.server.commands.SetBlockCommand$Filter
+ XXX.server.commands.SetBlockCommand$Mode
- XXX.server.commands.SetPlayerIdleTimeoutCommand
+ XXX.server.commands.SetSpawnCommand
- XXX.server.commands.SetWorldSpawnCommand
+ XXX.server.commands.SpawnArmorTrimsCommand
- XXX.server.commands.SpectateCommand
+ XXX.server.commands.SpreadPlayersCommand
- XXX.server.commands.SpreadPlayersCommand$Position
+ XXX.server.commands.StopCommand
- XXX.server.commands.StopSoundCommand
+ XXX.server.commands.SummonCommand
- XXX.server.commands.TagCommand
+ XXX.server.commands.TeamCommand
- XXX.server.commands.TeamMsgCommand
+ XXX.server.commands.TeleportCommand
- XXX.server.commands.TeleportCommand$LookAt
+ XXX.server.commands.TellRawCommand
- XXX.server.commands.TimeCommand
+ XXX.server.commands.TitleCommand
- XXX.server.commands.TriggerCommand
+ XXX.server.commands.WardenSpawnTrackerCommand
- XXX.server.commands.WeatherCommand
+ XXX.server.commands.WhitelistCommand
- XXX.server.commands.WorldBorderCommand
- XXX.server.dedicated.DedicatedPlayerList
+ XXX.server.dedicated.DedicatedServer
- XXX.server.dedicated.DedicatedServer$1
+ XXX.server.dedicated.DedicatedServerProperties
- XXX.server.dedicated.DedicatedServerProperties$WorldDimensionData
+ XXX.server.dedicated.DedicatedServerSettings
- XXX.server.dedicated.package-info
- XXX.server.dedicated.ServerWatchdog
+ XXX.server.dedicated.ServerWatchdog$1
- XXX.server.dedicated.Settings
+ XXX.server.dedicated.Settings$MutableValue
+ XXX.server.gui.MinecraftServerGui
- XXX.server.gui.MinecraftServerGui$1
+ XXX.server.gui.MinecraftServerGui$2
- XXX.server.gui.package-info
- XXX.server.gui.PlayerListComponent
+ XXX.server.gui.StatsComponent
+ XXX.server.level.BlockDestructionProgress
- XXX.server.level.ChunkHolder
+ XXX.server.level.ChunkHolder$1
- XXX.server.level.ChunkHolder$ChunkLoadingFailure
+ XXX.server.level.ChunkHolder$ChunkLoadingFailure$1
- XXX.server.level.ChunkHolder$ChunkSaveDebug
+ XXX.server.level.ChunkHolder$FullChunkStatus
- XXX.server.level.ChunkHolder$LevelChangeListener
+ XXX.server.level.ChunkHolder$PlayerProvider
- XXX.server.level.ChunkMap
+ XXX.server.level.ChunkMap$1
- XXX.server.level.ChunkMap$2
+ XXX.server.level.ChunkMap$DistanceManager
- XXX.server.level.ChunkMap$TrackedEntity
+ XXX.server.level.ChunkTaskPriorityQueue
- XXX.server.level.ChunkTaskPriorityQueueSorter
+ XXX.server.level.ChunkTaskPriorityQueueSorter$Message
- XXX.server.level.ChunkTaskPriorityQueueSorter$Release
+ XXX.server.level.ChunkTracker
- XXX.server.level.ColumnPos
+ XXX.server.level.DemoMode
- XXX.server.level.DistanceManager
+ XXX.server.level.DistanceManager$ChunkTicketTracker
- XXX.server.level.DistanceManager$FixedPlayerDistanceChunkTracker
+ XXX.server.level.DistanceManager$PlayerTicketTracker
- XXX.server.level.PlayerMap
+ XXX.server.level.PlayerRespawnLogic
- XXX.server.level.SectionTracker
+ XXX.server.level.ServerBossEvent
- XXX.server.level.ServerChunkCache
+ XXX.server.level.ServerChunkCache$ChunkAndHolder
- XXX.server.level.ServerChunkCache$MainThreadExecutor
+ XXX.server.level.ServerEntity
- XXX.server.level.ServerLevel
- XXX.spectator.categories.package-info
- XXX.spectator.categories.SpectatorPage
+ XXX.spectator.categories.TeleportToPlayerMenuCategory
- XXX.spectator.categories.TeleportToTeamMenuCategory
+ XXX.spectator.categories.TeleportToTeamMenuCategory$TeamSelectionItem
- XXX.telemetry.events.AggregatedTelemetryEvent
- XXX.telemetry.events.package-info
+ XXX.telemetry.events.PerformanceMetricsEvent
- XXX.telemetry.events.WorldLoadEvent
+ XXX.telemetry.events.WorldLoadEvent$1
- XXX.telemetry.events.WorldLoadTimesEvent
+ XXX.telemetry.events.WorldUnloadEvent
- XXX.texture.atlas.package-info
+ XXX.texture.atlas.SpriteResourceLoader
- XXX.texture.atlas.SpriteResourceLoader$1
+ XXX.texture.atlas.SpriteSource
- XXX.texture.atlas.SpriteSource$Output
+ XXX.texture.atlas.SpriteSource$SpriteSupplier
+ XXX.texture.atlas.SpriteSources
- XXX.texture.atlas.SpriteSourceType
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
- XXX.voting.rules.BooleanRule$BooleanRuleChange
- XXX.voting.rules.CounterRule$1
- XXX.voting.rules.CounterRule$Simple
- XXX.voting.rules.DoubleOrHalfRule
- XXX.voting.rules.EnumRule$1
- XXX.voting.rules.FixedOrRandomKeyRule
- XXX.voting.rules.FixedOrRandomKeyRule$Change
- XXX.voting.rules.MapRule$1
- XXX.voting.rules.OneShotRule
- XXX.voting.rules.OneShotRule$OneShotRuleChange
- XXX.voting.rules.OneShotRule$Simple
- XXX.voting.rules.package-info
- XXX.voting.rules.RandomNumberRule$1
- XXX.voting.rules.RandomNumberRule$RandomInt
- XXX.voting.rules.ResourceKeyReplacementRule
- XXX.voting.rules.ResourceKeySingleRule
- XXX.voting.rules.ResourceKeySingleRule$Change
- XXX.voting.rules.RuleAction
- XXX.voting.rules.RuleChange$1
- XXX.voting.rules.Rules
- XXX.voting.rules.Rules$10
- XXX.voting.rules.Rules$12
- XXX.voting.rules.Rules$14
- XXX.voting.rules.Rules$16
- XXX.voting.rules.Rules$18
- XXX.voting.rules.Rules$2
- XXX.voting.rules.Rules$21
- XXX.voting.rules.Rules$23
- XXX.voting.rules.Rules$25
- XXX.voting.rules.Rules$27
- XXX.voting.rules.Rules$29
- XXX.voting.rules.Rules$30
- XXX.voting.rules.Rules$32
- XXX.voting.rules.Rules$34
- XXX.voting.rules.Rules$36
- XXX.voting.rules.Rules$38
- XXX.voting.rules.Rules$4
- XXX.voting.rules.Rules$41
- XXX.voting.rules.Rules$43
- XXX.voting.rules.Rules$6
- XXX.voting.rules.Rules$8
- XXX.voting.rules.SetRule
- XXX.voting.rules.UniformIntRule
- XXX.voting.rules.UniformIntRule$Change
- XXX.voting.rules.VotingCostRule$1
- XXX.voting.votes.ClientVote$ClientOption
- XXX.voting.votes.FinishedVote
- XXX.voting.votes.FinishedVote$1ResultPair
- XXX.voting.votes.OptionId
- XXX.voting.votes.OptionVotes
- XXX.voting.votes.package-info
- XXX.voting.votes.ServerVote$Effect
- XXX.voting.votes.ServerVote$VoteGenerationOptions
- XXX.voting.votes.ServerVoteStorage$OptionAccess
- XXX.voting.votes.TieResolutionStrategy
- XXX.voting.votes.VoteResults$OptionResult
- XXX.voting.votes.VoterMap
- XXX.voting.votes.VoteStorage
- XXX.voting.votes.VotingMaterial$1
- XXX.voting.votes.VotingMaterial$Cost
- XXX.voting.votes.VotingMaterial$Type
- XXX.voting.votes.VotingMaterial$Type$2
- XXX.voting.votes.VotingMaterial$Type$4
- XXX.voting.votes.VotingMaterial$VotingItem
- XXX.voting.votes.VotingMaterial$VotingResource$1
- XXX.world.entity.Display$LinearFloatInterpolator
+ XXX.world.entity.Display$LinearIntInterpolator
- XXX.world.entity.Display$LinearlyInterpolatedBlockAnimator
- XXX.world.entity.Display$StencilDisplay
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
- XXX.world.food.Thirst
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
- XXX.world.item.BottleOfEntityItem
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
+ XXX.world.item.package-info
- XXX.world.item.SplashBottleOfEntityItem
+ XXX.world.item.SplashPotionItem
- XXX.world.item.SpyglassItem
+ XXX.world.item.StandingAndWallBlockItem
- XXX.world.item.SuspiciousStewItem
+ XXX.world.item.SwordItem
- XXX.world.item.TagContainerItem
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
<hr/>