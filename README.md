# Elemental-Battlemage
Unity 2D game about elemental battlemage
Gameplay realisation

Home:
Initially level starts at the Headquarters (Home base level), short dialogue or non, book does not appear as a cursor yet. There is a sign that has written on it: “X Place” (probably forest / jungle thing name)

Jungle Thicket:
Scene loads into a thicket of a jungle entrance. Use Unlit, so we can actually use the book as a lighter. As elements change, fire actually has a bigger light source than the others. We’d encounter a few small stone golems (Enemy_RedDot), after defeating them, a hollow tree opening leading to the boss. Cutscene or a post processing effect plays and we are on top of the level, starting with jungle layout boss.

Golems are mostly stationary



Earth Golem Stage

Earth Golem Abilities:

Summon Elemental Golems
Small golem that moves towards the player as a Red Dot script would through the nodes. We can use a smaller version of the big golem as its Sprite (Mesh Renderer).

Rustled Ground
All ground becomes shaky, vfx effect that shows small rocks jumping up. Making you run to a place in which you have no hit ray on the golem (Between platforms). As rocks jump up, you’d be protected between two platforms.

Rock Toss - Rock is thrown

Upon defeating the first stage, the boss summons Planetary Devastation with extreme force pull over time and we are pulled, post processing effect that makes an explosion on the screen, we are loaded into a second scene. We move to the second stage:






Water Golem Stage

No platforms here, ground is icy and there are two spots where Water Vortex unleashes after time to time.

Icicles Area

Temporarily vortexes off. 
Water splashes on the ground as if it's the player's ice effect. 
Vortexes turn on again. 
Ice grows in places where water splashed leaving the player barely anything to stand on if he didn’t change the areas. Going through a vortex costs life.

Bubbles Everywhere!

Boss releases X amount of bubbles that travel from X to -X position in certain zig zags, trying to break it up. It travels in a sinusoid:


Ice Toss - Ice is thrown.

After boss is defeated, post processing to freeze the whole screen and we move to next and final stage:






Fire Golem Stage

Fiery Eye
Flame Golem summons a fiery eye that opens itself and starts rapidly firing projectiles to the player’s direction

Summon Flame Wisp
Tosses a stationary flame wisp that is immune to fire damage and occasionally shoots a fire projectile

Flame Spark type ability (Adjust accordingly)

Lava Ground
Randomly over the whole area small red dots appear as if it’s peering into hell itself. Then lava eruptions start from there (Extremely deadly)

Enemy drops a page that you can add to your book at home. You pick it up, sparkles fly, opening back home appears.
        





Homecoming

Upon defeating the Fire Golem, it drops its own Fire_3 Spell_Volcano_Eruption spell. We get a button to go back to headquarters and we can change our spells there. We change our Fire_3 Spell_Fire_Wall to Spell_Volcano_Eruption spell. It has a natural synergy with Earth spells and makes them molten.
