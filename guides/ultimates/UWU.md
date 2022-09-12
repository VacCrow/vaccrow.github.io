---
layout: guides
title: The Weapon's Refrain (Ultimate) | UWU
imagePath: /assets/img/guides/ultimates/UWU/
slideNumber: 1
---

*Patch: 4.31  
Minimum ilvl: i370  
Maximum ilvl: i375  
Maxsubstat ilvl: i470 (if you use a Bozjan relic weapon, substats are capped to 318, 227 and 91 for a paladin sword and shield)  
DPS Requirement: non existent KEKW  
Loot:*

+ *Token: Ultima Totem (1 token for an Ultima weapon)*

> Notes: Two pots can be used in Ultima phase. One when the phase starts and the second during/after the primal roulette.

___

<h1><a id='AethericallyCharged&Woken'>Aetherically Charged & Woken</a></h1>

<div class='guideSection' markdown='1'>
During the first three phases, each primal can gain an <span class='buff'>Aetherically Charged</span> <img class='iconImg' src='{{ site.data.iconList.UWU.AethericallyCharged }}'>stack under specific conditions. When a primal reaches 4 stacks, it will gain <span class='buff'>Woken</span> <img class='iconImg' src='{{ site.data.iconList.UWU.Woken }}'>, gaining new abilities or modifying existing ones.  
When a primal with <span class='buff'>Woken</span> is killed, it will drop a small puddle on the ground. When a player walks over it, he will receive the <span class='buff'>Beyond Limit</span> <img class='iconImg' src='{{ site.data.iconList.UWU.BeyondLimit }}'> buff. After that player uses a LB3, you LB bar will be refilled.  
This buff is mandatory since the transition phase after killing all 3 primals requires four LB3 used in a row.

Garuda gains 1 stack of <span class='buff'>Aetherically Charged</span> when 2 stacks of <span class='speDebuff'>Thermal Low</span> are purged.
Ifrit gains 1 stack of <span class='buff'>Aetherically Charged</span> when a *Nail* that grown twice is killed.
Titan gains 1 stack of <span class='buff'>Aetherically Charged</span> when he stands inside his puddle for X seconds.
</div>

<h1><a id='Garuda'>Garuda</a></h1>

<div class='guideSection' markdown='1'>
<h2><a id='GarudaAbilitiesBreakdown'>Abilities Breakdown</a></h2>

+ **<u>Slipstream</u>:**
Untelegraphed frontal cleave dealing high <span class='magic'>magical damage</span> and applying a <span class='debuff'>Stun</span> debuff.

___

+ **<u>Mistral Song</u>:**
A random Healer will be marked before *Garuda* fires a Line Aoe toward that player, dealing <span class='magic'>magical damage</span> to anyone hit.  
The first player hit will receive high <span class='magic'>magical damage</span> and a *Great Whirlwind* AoE will spawn under that player. The *Great Whirlwind* will pulse 3 times, dealing lethal damage each time.

___

+ **<u>Satin Plume / Spiny Plume</u>:**
  + *Satin Plume*: 4 adds that will tether and move to a DPS. Explode after a set time, inflicting <span class='debuff'>Sleep</span> to everyone.
  + *Spiny Plume*: Add that will tether and move to the first player that deals damage to it. Every 9 seconds, it will cast **Cyclone**, dealing moderate <span class='magic'>magical damage</span> to its target and applying a <span class='debuff'>Thermal Low</span> stack.  
    On death, it will cast **Gigastorm**.

___

+ **<u>Gigastorm</u>:**
AoE dealing lethal damage that leaves a bubble afterward for 22s. While inside it, it gives the <span class='buff'>Thermal High</span> <img class='iconImg' src='{{ site.data.iconList.UWU.ThermalHigh }}'> buff reducing all incoming wind damage.
If a player with <span class='speDebuff'>Thermal Low</span> <img class='iconImg' src='{{ site.data.iconList.UWU.ThermalLow }}'> stack(s) steps inside, it will purge them and deal <span class='magic'>magical damage</span> (named **Super Cyclone**) based on the number of <span class='speDebuff'>Thermal Low</span>:
  + 1 stack: low damage
  + 2 stacks: medium damage
  + 3 stacks: lethal damage

___

+ **<u>Downburst</u>:**

Cleave tank buster on the main target dealing <span class='phys'>physical damage</span>.
When <span class='buff'>Woken</span>: share on the main target dealing high <span class='magic'>magical damage</span>.

___

+ **<u>Feather Rain</u>:**

*Garuda* will shriek and jump away. At the same time, 5 players will be targeted by small AoEs under them dealing <span class='magic'>magical damage</span> and applying the <span class='speDebuff'>Windburn</span> debuff, a DoT lasting 18s.  
Player positions are snapshot when *Garuda* shrieks.

___

+ **<u>Mistral Shriek</u>:**

Raid-wide AoE dealing <span class='magic'>magical damage</span>.

___

+ **<u>Friction</u>:**

Small AoE on a random player dealing <span class='magic'>magical damage</span> and applying a <span class='speDebuff'>Thermal Low</span> stack on anyone hit.

___

+ **<u>Aerial Blast</u>:**

Raid-wide AoE dealing high <span class='magic'>magical damage</span>.

  The second **Aerial Blast** is the enrage.

___

+ **<u>Eye Of The Storm</u>:**

A *Great Whirlwind* with a donut shape will cover the outer part of the arena. The *Great Whirlwind* will pulse 3 times, dealing lethal damage each time.

___

+ **<u>Wicked Wheel</u>:**

Pointblank AoE on *Garuda* dealing lethal damage.
When <span class='buff'>Woken</span>: **Wicked Wheel** is followed by an instant **Wicked Tornado**, a donut shaped AoE dealing lethal damage.

___

+ **<u>Mesohigh</u>:**

A random player will be tether to a clone of *Garuda*. After 5 seconds, it will perform an AoE on the target, purging any <span class='speDebuff'>Thermal Low</span> stack(s). When purged, **Super Cyclone** will deal raid-wide AoE <span class='magic'>magical damage</span> damage based on the number of <span class='speDebuff'>Thermal Low</span> removed.  
Deals lethal damage if the target isn’t afflicted with <span class='speDebuff'>Thermal Low</span>.

</div>

<div class='guideSection' markdown='1'>
<h2><a id='GarudaStrategy'>Strategy</a></h2>

Pull *Garuda* in the middle of the arena.

The main Tank has to move to the side to avoid the first **Slipstream**.
At the same time, the Healer with the **Mistral Song** marker will position himself to the side of *Garuda* and slightly away. The second Tank will move in front of him (still away from *Garuda*) to take frontal hit. If done properly, the *Great Whirlwind* will be dropped far enough from the boss to avoid any movement for the group.

Afterward, 4 *Satin Plume* and 1 *Spiny Plume* will spawn. The second Tank has to quickly attack the *Spiny Plume* to get the aggro and everyone must stack behind *Garuda* to pack the *Satin /Spiny Plumes* in order to burn them down. Quickly kill the *Satin Plumes* but let the *Spiny Plume* alive until the Tank gets two stacks of <span class='speDebuff'>Thermal Low</span>.  
Meanwhile Garuda will cast another **Slipstream** followed by **Downburst** right after on the main target.

Once **Downburst** is done (and the *Satin Plumes* dead in theory), *Garuda* will use **Feather Rain**. Stack beforehand to stack the AoEs and remember to use *Garuda* ’s shriek as a cue to move.  
The second Tank can use that moment to move the *Spiny Plume* to the side and kill it there since he will gain the second stack of <span class='speDebuff'>Thermal Low</span> when **Feather Rain** happens.

When *Garuda* reappears, she will use **Mistral Shriek**.

After that,  everyone can move inside the dome. The Tank with <span class='speDebuff'>Thermal Low</span> stacks will wait outside for the group to be healed. Then the Tank can move inside too to purge his stacks, giving to *Garuda* her first <span class='buff'>Aetherically Charged</span> stack.

For the incoming **Friction**, everyone stays still inside the bubble except for the Main Tank and the 2 Melee DPS, that will stay outside. These two groups must be on the dome border so they both get hit by **Friction**.  

*Garuda* will now use **Friction** hitting everyone. Every player inside the bubble will get their <span class='speDebuff'>Thermal Low</span> purged instantly. There should be 3 players with 1 stack.  
*Garuda* will use another **Friction** but this time, the whole party will stack outside the bubble. There should be 5 players with 1 stack and 3 players with 2 stacks.

Quickly heal the group, then the first DPS with 2 Thermal Low will move inside the bubble to purge them, and the second DPS will do the same after the group has been healed.

Garuda will use another **Feather Rain**, move out to dodge.  
When *Garuda* reappears, she will use **Aerial Blast** that must be mitigated.

She will then summon her clones, *Chirada* and *Suparna*. They will use **Feather Rain** once they spawn and reappear at a random cardinal. Move away to a avoid the AoEs and bring *Garuda* to a clone.

*Garuda* will use **Eye Of The Storm** and **Wicked Wheel** at the same time, *Chirada* and *Suparna* will cast **Mistral Song** on a DPS and a Healer.  
Every DPS and Healer will stack in the middle while each Tanks move in front of the group to absorb the first hit. The Main Tank can cover the attack from the clone where *Garuda* is while the second Tank cover the attack of the remaining clone.

Right after, both clones will use **Feather Rain** and the *Great Whirlwind* from **Mistral Song** will appear, only for 1 tick. Move away from the middle to avoid both.

Then bring back *Garuda* middle as she summons 4 *Satin Plumes* and uses another **Eye of The Storm**.  
The Main Tank will now make the boss face toward the East as *Chirada* and *Suparna* will spawn on the East and West edges.

After that, one Ranged DPS with 1 <span class='speDebuff'>Thermal Low</span> left will grab the West tether while the East tether will be taken by the Main Tank. Have some heals and mitigation ready for the double **Super Cyclone** when the stacks are purged.
In the meantime, *Garuda* will use **Slipstream**.

From this moment, *Garuda* is fully awaked and can be killed at any time.

*Chirada* and *Suparna* will disappear with a **Feather Rain**. Remember to move.  
*Garuda** will follow up with a **Slipstream** and a **Wicked Wheel** + **Wicked Tornado** combo. Move in immediately after the **Wicked Wheel**.

Next is a **Downburst** that must be shared within the group.

*Garuda* will end the phase with a **Slipstream** followed by **Feather Rain** and **Aerial Blast**, the enrage.

> You have to end this phase with a <span class='speDebuff'>Thermal Low</span> on one Tank, both Healers and one Ranged DPS.
</div>

<h1><a id='Ifrit'>Ifrit</a></h1>

<div class='guideSection' markdown='1'>
<h2><a id='IfritAbilitiesBreakdown'>Abilities Breakdown</a></h2>

+ **<u>Radiant Plume</u>:**

Ground AoE dealing lethal damage.

___

+ **<u>Crimson Cyclone</u>:**

*Ifrit* or a clone will appear on the edge of the arena and dash in a straight line after 3 seconds, dealing lethal damage.
When <span class='buff'>Woken</span>: The dash from *Ifrit* will also perform **Crimson Cyclone Cross**, a cross shape AoE rotated by 45° based on his his dash.

___

+ **<u>Hellfire</u>:**

Raid-wide AoE dealing high <span class='magic'>magical damage</span>.

  The third **Hellfire** is the enrage.

___

+ **<u>Vulcan Burst</u>:**

Raid-wide AoE dealing small <span class='magic'>magical damage</span>. Can be avoided with a knockback immunity or if no damage has been taken with a shield on.

___

+ **<u>Incinerate</u>:**

Cleave tank buster dealing fire <span class='magic'>magical damage</span> and applying a <span class='debuff'>Fire Resistance Down II</span> lasting 5 seconds. Always happens 3 times in a row.

___

+ **<u>Infernal Nails</u>:**
4 *Infernal Nails* spawn with 86k HP. After 30 seconds, *Ifrit* will jump away and cast **Hellfire**. If at least one *Infernal Nails* remains, **Hellfire** will wipe the group.  
When a *Infernal Nails* is destroyed, it deals raid-wide <span class='magic'>magical damage</span> and applies a <span class='debuff'>Vulnerability Up</span> stack debuff for 1 second.  
When a *Infernal Nails* is hit by an **Eruption**, it will gain one stack of <span class='buff'>Damage Up</span> and <span class='buff'>Vulnerability Down</span>, up to 2 stacks. When a *Infernal Nails* with 2 stacks is destroyed, *Ifrit* gains one <span class='buff'>Aetherically Charged</span> stack.  
The order in which the *Infernal Nails* are killed will influence the order of the **Crimson Cyclones** later in the phase.

___

+ **<u>Inferno Howl</u>:**

A random Healer will receive the <span class='speDebuff'>Searing Wind</span> <img class='iconImg' src='{{ site.data.iconList.UWU.SearingWind }}'> debuff lasting 18 seconds. Every 6 seconds, the player will emit a wide shockwave dealing <span class='magic'>magical damage</span> and will knockback anyone else caught.
When <span class='buff'>Woken</span>: The debuff lasts 30 seconds.

___

+ **<u>Infernal Fetters</u>:**

A random DPS and the second person in the aggro list will be tethered together and will receive the <span class='speDebuff'>Infernal Fetters</span> <img class='iconImg' src='{{ site.data.iconList.UWU.InfernalFetters }}'> DoT debuff that stacks the further away they are from each other. Each stack reduces the damage done and increases the DoT potency.

___

+ **<u>Eruption</u>:**

4 ground AoE appearing sequentially under the furthest player’s feet. They explode after 2.5 seconds dealing lethal damage.  

  In the last phase, anyone but the Tanks can be targeted.

___

+ **<u>Flaming Crush</u>:**

A random DPS will get the flame marker. After a 5 seconds, *Ifrit* will perform a share AoE dealing <span class='magic'>magical damage</span>.
When <span class='buff'>Woken</span>: Inflict <span class='speDebuff'>Accursed Flame</span> <img class='iconImg' src='{{ site.data.iconList.UWU.AccursedFlame }}'>, a DoT on every player in the stack whose duration is based on the number of players hit, with a minimum of 3 seconds for 6 players hit.

</div>

<div class='guideSection' markdown='1'>
<h2><a id='IfritStrategy'>Strategy</a></h2>

Once *Garuda* is dead, remember to pick up the <span class='buff'>Beyond Limit</span> buff.

Then everyone stack mid since *Ifrit* will appear at a random cardinal and prepare a **Crimson Cyclone**. After a few seconds, the arena will be covered with **Radiant Plumes** with two safe spots, the first one's on *Ifrit* ’s path and the second isn't.  
Once you see *Ifrit*, watch the cardinal to his left. If there’s no **Radiant Plume** there, move to that location. Otherwise, move to the opposite cardinal you’re looking at.

Afterward, *Ifrit* reappears in the middle and cast **Hellfire**. Soon followed by **Vulcan Burst**. Remember to shield the **Vulcan Burst** or use your knockback immunity to avoid being knocked into the wall.  
Immediately after, Ifrit will use **Incinerate** three times in a row on the main target. Either swap tanks after each hit or use a Tank invulnerability (Incinerates window is 7 seconds long). In the meantime, the second Tank can turn his stance on to be second in aggro.

*Ifrit* will now spawn the 4 *Infernal Nails* in the specific pattern:

+ Two of them will be close to each other on adjacent cardinal and intercardinal.
+ The other two will be further away.

The pattern is always the same but the orientation is random, here is an example:
<img class='soloImg' src='{{ page.imagePath | append: 'nails.jpg' }}'>

> The two *Infernal Nails* close to each other will be considered as the front side while the other two will be considered as the back side.

Once they appear, IDENTIFY WHERE THE BACK LEFT *INFERNAL NAIL* IS. Remember its axis since it's important for a later mechanic. ie. if this *Infernal Nails* is South, you have to memorize the North-South axis.  
Then the Main Tank has to move to the boss between the front *Infernal Nails*, the second Tank needs to be ensure that he's second in the aggro list and the two Ranged DPS need to be the furthest players from *Ifrit*, roughly around the back *Infernal Nails*.

After a few seconds, *Ifrit* casts **Infernal Howl** on a random Healer that will move between the back *Infernal Nails* along the edge.  
The second Tank and a random DPS will get tethered with <span class='speDebuff'>Infernal Fetters</span>, try to stay together to keep the debuff at 1 or 2 stacks at all time.  
The two ranged DPS will be targeted by 4 **Eruptions** in a row. These DPS, one on each side, will move from the back to the front and hit each *Infernal Nails* on their side with their **Eruption** twice.

Meanwhile, everyone has to try to bring the *Infernal Nails* at low HP so they are easy to kill even with their <span class='buff'>Vulnerability Down</span>. Be careful of any involuntary critical/direct hit.

The *Infernal Nails* kill order will determine the **Crimson Cyclone** order later in the phase. The kill order is:

+ <u>Back Right > Front Left > Front Right > Back Left</u>

Once the *Infernal Nails* are destroyed, *Ifrit* will leave and come back in the middle to cast **Hellfire**. Then bring the boss the North East intercardinal.  
Meanwhile *Ifrit* will cast **Inferno Howl** on a random Healer followed up by four **Eruptions** on the two furthest players. The Healer with the <span class='speDebuff'>Searing Wind</span> debuff will move to the North West. The ranged DPS will move to the South West to bait the **Eruptions** and once they drop the first one, they will rotate anticlockwise and drop their **Eruption** along the way to rejoin the rest of the group North East.  
At the end of **Eruption**, two *Ifrit* clones will spawn and dash through the cardinals.

Shortly after, the second Healer receives the <span class='speDebuff'>Searing Wind</span> debuff and will move to South West, away from anyone else. The Tanks and DPS have to stack for the **Flaming Crush** attack.

Now you have to remember the axis of the last *Infernal Nail* you killed, the back left one. Once *Ifrit* leaves, the group will move and stack at the cardinal/intercardinal along this axis between the North and South East while the Healer with <span class='speDebuff'>Searing Wind</span> will move alone on the opposite side.  
*Ifrit* and 3 clones will spawn at the cardinals/intercardinals edges where the *Infernal Nails* previously were. They will dash through the arena following the same order as the *Infernal Nails* kill order.  
Identify where *Ifrit* is. Since he's woken, he has a blue glow around him. Then, once the first **Crimson Cyclone** happens, everyone will start to rotate clockwise:

+ If *Ifrit* is on the group sides, move to the next cardinal/intercardinal once.
+ If *Ifrit* isn't on the group sides, move to the next cardinal/intercardinal twice.

Once you done moving, stand still to dodge the **Crimson Cyclone Cross**.

*Ifrit* will land and use **Incineration** three times in a row, use same method as for the first one.
It is followed by 3 **Eruptions** on the two furthest players with a **Flaming Crush** to deal with for the rest of the group.

This phase will be concluded by *Ifrit* ’s enrage, **Hellfire*.

</div>

<h1><a id='Titan'>Titan</a></h1>

<div class='guideSection' markdown='1'>
<h2><a id='TitanAbilitiesBreakdown'>Abilities Breakdown</a></h2>

+ **<u>Geocrush</u>:**

*Titan* will jump into the arena Raid-wide AoE dealing proximity <span class='magic'>magical damage</span>.  
The first time he will jump in the middle of the arena. The two next times, he will jump at the edge he's facing before leaving the arena and destroy the outer ring of the arena.

___

+ **<u>Earthen Fury</u>:**

Raid-wide AoE dealing high <span class='magic'>magical damage</span>.

  The second **Earthen fury** is the enrage.

___

+ **<u>Rock Buster</u>:**

Tank buster dealing <span class='phys'>physical damage</span>.

___

+ **<u>Mountain Buster</u>:**

Cleave tank buster dealing high <span class='phys'>physical damage</span>.

___

+ **<u>Weight Of The Land</u>:**

4 random players will get a ground AoE under them, exploding after 2.5 seconds and dealing lethal damage.  
Immediately after the first set, the same players will be targeted by a second set.  
When <span class='buff'>Woken</span>: A third set will happen after the second one.

___

+ **<u>Upheaval</u>:**

Long knockback from Titan dealing <span class='magic'>magical damage</span>. The knockback distance is 3/4 of the arena diameter.

___

+ **<u>Bomb Boulder</u>:**

*Bomb Boulders* will drop into the arena. They will cast **Burst** and explode in AoE dealing lethal damage after 5 seconds.  
The first set will drop 5 *Bomb Boulders* to the opposite side of *Titan* leaving only one safe spot surrounded by the other *Bomb Boulders*. After they explode, a sixth one will drop where the safe spot was.  
The second set will drop 4 *Bomb Boulders* in the middle of the arena leaving that place unsafe.

___

+ **<u>Rock Throw</u>:**

Three random players but *Titan* 's main target will get a Gaol marker. After 5 seconds these players will receive the <span class='speDebuff'>Fetters</span> debuff, preventing any movements and imprisoning the player into a *Granite Gaol*. These *Granite Gaol* will cast **Granite Impact** killing the player inside after 5 seconds.  
If a *Granite Gaol* is caught inside a **Burst** explosion from a *Bomb Boulder*, the *Gaol* will be destroyed, leaving a puddle and freeing the player inside. It will also cast **Burst** and destroy any other *Granite Gaol* in range.

  The puddle gives a lethal DoT to any player who stand inside. When a player is freed from the his *Gaol*, he has a very short immunity to the puddle.  
  As long as *Titan* is standing inside the puddle, he will gain a stack of <span class='buff'>Aetherically Charged</span> every 3 seconds.

  The second cast will only target a random Healer and must be freed by destroying the *Granite Gaol*.

___

+ **<u>Landslide</u>:**

Lines AoEs from *Titan dealing <span class='phys'>physical damage</span> and knocking away anyone hit. These AoEs will be fired in front of him and towards his intercardinals.
When <span class='buff'>Woken</span>: An additional set will be fired to his 1 and 11 o'clock and his East, South and West cardinals.

___

+ **<u>Tumult</u>:**

8 consecutive raid-wide AoE dealing low <span class='magic'>magical damage</span>. The second cast only hits 6 times.

</div>

<div class='guideSection' markdown='1'>
<h2><a id='TitanStrategy'>Strategy</a></h2>

</div>

<h1><a id='Lahabrea'>Lahabrea</a></h1>

<div class='guideSection' markdown='1'>

Once *Titan* is dead, four **Freefire** proximity AoE will appear on the cardinal edges. Stack mid and migitate properly for the <span class='magic'>magical damage</span> impact. Then 6 *Magitek Bits* will spawn around the arena. They will cast **Self-Detonate** and wipe the group if at least one *Magitek Bit* can finish its cast. The Magical Ranged DPS with the <span class='buff'>Beyond Limit</span> has to use his LB3 to hit every *Magitek Bits*, the rest of the group may have to finish them.

Then *Lahabrea* will appear middle and cast **Blight**, setting everyone HP to 1 and applying a <span class='speDebuff'>Down for the Count</span> debuff lasting 5 second and preventing any actions and a <span class='speDebuff'>Doom</span> debuff lasting 9 seconds that can be removed when the player is full HP. Due to limited time, the Healer with <span class='buff'>Beyond Limit</span> will cast his LB3 to heal everyone and remove the <span class='speDebuff'>Doom</span>.

Finally *Lahabrea* will become targetable and cast **Dark IV** wiping the group. He will also gain the <span class='buff'>Woken</span> buff, reducing the damage taken. The Melee DPS with <span class='buff'>Beyond Limit</span> has to cast his LB as soon as the LB bar is filled to kill him. The rest of the group can hit the boss to generate resources since they deal laughable damage.  
Finally, *Ultima* will appear and immediately use the Tank LB3 to survive from **Ultima**.

</div>

<h1><a id='Ultima'>Ultima</a></h1>

<div class='guideSection' markdown='1'>
<h2><a id='UltimaAbilitiesBreakdown'>Abilities Breakdown</a></h2>

+ **<u>Ultima</u>:**

Raid-wide AoE dealing very high <span class='magic'>magical damage</span>. Require a Tank LB3.

___

+ **<u>Tank Purge</u>:**

Raid-wide AoE dealing high <span class='magic'>magical damage</span>.

___

+ **<u>Viscous Aetheroplasm</u>:**

AoE attack on the main target that apply the <span class='speDebuff'>Viscous Aetheroplasm</span> <img class='iconImg' src='{{ site.data.iconList.UWU.ViscousAetheroplasm }}'>. When it resolves, it deals high <span class='magic'>magical damage</span> in a small AoE around the bearer that can be shared.

___

+ **<u>Homing Lasers</u>:**

Small AoE Tank Buster dealing <span class='magic'>magical damage</span>.

___

+ **<u>Ultimate Predation</u>:**

  + **<u>Landslide</u>:**
  *Titan* spawn at a random cardinal edge, facing the opposite side of the arena and cast a <span class='buff'>Woken</span> **Landslide**.
  
  ___

  + **<u>Wicked Wheel</u>:**
  *Garuda* spawn near the middle along an intercardinal and cast a regular **Wicked Wheel**.
  
  ___

  + **<u>Crimson Cyclone</u>:**
  *Ifrit* spawn at a random intercardinal edge and cast a a <span class='buff'>Woken</span> **Crimson Cyclone**.
  
  ___

  + **<u>Ceruleum Vent</u>:**
  *Ultima* spawn at a random intercardinal edge and cast **Ceruleum Vent**, a pointblank AoE dealing lethal damage.

___

+ **<u>Landslide</u>:**
**Landslide** from *Ultima* on his front, 2' and 10' o'clock.

___

+ **<u>Ultimate Annihilation/u>:**

___

+ **<u>Ultimate Suppression</u>:**

___

+ **<u>Aetheric Boom</u>:**

___

</div>

<div class='guideSection' markdown='1'>
<h2><a id='UltimaStrategy'>Strategy</a></h2>

</div>
