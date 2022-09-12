---
layout: guides
title: Asphodelos - The Fourth Circle (Savage) | P4S (Part 1)
imagePath: /assets/img/guides/savages/pandaemonium/P4S_Part1/
slideNumber: 2
---

*Patch: 6.05  
Minimum ilvl: i580  
DPS Requirement: 48.2k  
Enrage timer: 07:13  
Loot: None since it's a door boss*

___

<h1><a id='AbilitiesBreakdown'>Abilities Breakdown</a></h1>

<div class='guideSection' markdown='1'>
<h2><a id='ABGeneralAbilities'>General Abilities</a></h2>

+ **<u>Decollation</u>:**
Raid-wide AoE dealing <span class='magic'>magical damage</span>.

___

+ **<u>Bloodrake</u>:**
*Hesperos* will tether to three tiles of the stage and/or four players, either Tanks/Healers or DPS, or every players dealing high <span class='magic'>magical damage</span> to tethered players and sucking their aether.  
The boss will receive the <span class='buff'>Aethersucker</span> <img class='iconImg' src='{{ site.data.iconList.P4S.Aethersucker }}'> buff, containing the aether of the role(s) he absorbed. The next casted mechanic will consume the buff and deal lethal damage to the absorbed role(s).

___

+ **<u>Aetheric Chlamys</u>:**
*Hesperos* will convert his <span class='buff'>Aethersucker</span> buff into a <span class='buff'>Casting Chlamys</span> <img class='iconImg' src='{{ site.data.iconList.P4S.CastingChlamys }}'> buff, also transferring the absorbed roles. This new buff will be consumed when he uses **Inversive Chlamys**.

___

+ **<u>Director’s Belone</u>:**
*Heperos* will consume his <span class='buff'>Aethersucker</span> buff and apply the <span class='speDebuff'>Role Call</span> <img class='iconImg' src='{{ site.data.iconList.P4S.RoleCall }}'> debuff on a Tank, a Healer and two DPS at random, lasting 15 seconds. The role(s) sucked by the <span class='buff'>Aethersucker</span> buff will die when <span class='speDebuff'>Role Call</span> resolves.  
If a player with <span class='speDebuff'>Role Call</span> touches another player without it, it will transfer the debuff to the second player. The first player will receive the <span class='speDebuff'>Miscast</span> <img class='iconImg' src='{{ site.data.iconList.P4S.Miscast }}'> debuff, making impossible to receive <span class='speDebuff'>Role Call</span> again.

___

+ **<u>Inversive Chlamys</u>:**
Four tethers on random players, dealing AoE <span class='phys'>magical damage</span> and applying a <span class='debuff'>Magic Vulnerability Up</span> debuff. Consumes <span class='buff'>Casting Chlamys</span> buff and deals lethal damage to the player of the absorbed role(s).

___

+ **<u>Elegent Eviseration</u>:**
Two hit AoE tank buster on the main target. The first hit deals <span class='phys'>magical damage</span> and applying a <span class='debuff'>Magic Vulnerability Up</span> debuff. The second hit only deals <span class='phys'>magical damage</span>.  
Swap tank during the cast or use any invulnerability.

___

+ **<u>Setting the Scene</u>:**
*Hesperos* will cover 4 quadrants of the arena with his cloak, modifying the quadrant and the effect of the next **Pinax**.  
When a quadrant resolves, it will explode, dealing <span class='magic'>magical damage</span> and applying a <span class='debuff'>Damage Down</span> debuff.  
If a player stands in the hole of a quadrant, it will give a DoT debuff based on the quadrant element among <span class='debuff'>Pollen</span>, <span class='debuff'>Dropsy</span>, <span class='debuff'>Burns</span> or <span class='debuff'>Electrocution</span>.

___

+ **<u>Pinax</u>:**
*Hesperos* will activate the quadrants from **Settings the Scene**. Each quadrant's well will erupt, one at a time, before activating. All of **Pinax** attacks deal <span class='magic'>magical damage</span>:  
  + **Levinstrike Mekhane** (Thunder): proximity raid-wide AoE from the centre of the arena.  
  + **Well Mekhane** (Water): raid-wide knockback from the centre of the arena.  
  + **Acid Mekhane** (Poison): AoE on every players.  
  + **Lava Mekhane** (Fire): stack markers on both Healers applying a <span class='debuff'>Magic Vulnerability Up</span> debuff.

  The tiles will activate in this order:  
  + 1st: **Levinstrike Mekhane (Thunder)** or **Well Mekhane (Water)**.  
  + 2nd: **Acid Mekhane (Poison)** or **Lava Mekhane(Fire)**.  
  + 3rd: **Well Mekhane (Water)** or **Levinstrike Mekhane (Thunder)**, the one that didn't fire in first.  
  + 4th: **Lava Mekhane (Fire)** or **Acid Mekhane (Poison)**, the one that didn't fire in second.

___

+ **<u>Northernly/Easternly/Southernly/Westernly Shift</u>:**
*Hesperos* will teleport to a cardinal, based on the name of the cast, and will perform an attack based on the weapon that glows:  
  + Sword: a 90° cone toward the centre of the arena dealing <span class='magic'>magical damage</span> and applying a <span class='debuff'>Damage Down</span> debuff.  
  + Cape: knock back from *Hesperos* position.

___

+ **<u>Vengeful Belone</u>:**
Every players will receive an <span class='speDebuff'>Acting Role</span> debuff:
  + Tanks and Healers will receive <span class='speDebuff'>Acting DPS</span> <img class='iconImg' src='{{ site.data.iconList.P4S.ActingDPS }}'>.
  + Two DPS will receive <span class='speDebuff'>Acting Healer</span> <img class='iconImg' src='{{ site.data.iconList.P4S.ActingHealer }}'>.
  + The other two DPS will receive <span class='speDebuff'>Acting Tank</span> <img class='iconImg' src='{{ site.data.iconList.P4S.ActingTank }}'>.

  When <span class='speDebuff'>Acting Role</span> resolves, it gives a <span class='speDebuff'>Thrice-come Ruin</span> debuff.  
  <span class='speDebuff'>Acting Role</span> is removed after a player soaked a mechanic of the indicated role.

___

+ **<u>Elemental Belone</u>:**
*Hesperos*' <span class='buff'>Aethersucker</span> buff will be consumed and every players receive <span class='speDebuff'>Elemental Resistance Down</span> <img class='iconImg' src='{{ site.data.iconList.P4S.ElementalResistanceDown }}'>. Player will take lethal damage from the three elements contained into the <span class='buff'>Aethersucker</span> debuff.

___

+ **<u>Belone Burst</u>:**
*Hesperos* will consume his <span class='buff'>Aethersucker</span> and 8 orbs will spawn on cardinals/intercardinals. They will tether to the closest player and will be marked with that player role. If a player pops an orb with the same role as his, he will die.  
When an orb is popped, it deals high <span class='magic'>magical damage</span> that need to be soaked by two players and applies a <span class='speDebuff'>Thrice-come Ruin</span> <img class='iconImg' src='{{ site.data.iconList.P4S.ThriceComeRuin }}'> stack to anyone hit, transforming into a <span class='speDebuff'>Doom</span> debuff at 3 stacks.  
Orbs has to be pop by players with an <span class='speDebuff'>Acting Role</span> debuff that correspond to the orb's role mark.

___

+ **<u>Periaktoi</u>:**
All tiles will explode and deal <span class='magic'>magical damage</span>.

___

+ **<u>Belone Coils</u>:**
Four towers will appear, spread around the middle of the arena. Each tower will contain a role that is forbidden. At least one player, not of a forbidden role, has to stand inside the towers.  
The cast of **Belone Coils** will modify *Heperos*' <span class='buff'>Aethersucker</span> debuff. The towers' forbidden role(s) will be removed from <span class='buff'>Aethersucker</span> when it will be used on **Aetheric Chlamys** or **Director’s Belone**.

</div>
___
<h1><a id='Strategy'>Strategy</a></h1>

<div class='guideSection' markdown='1'>
<a id='SPhase1'></a>

*Hesperos* starts with **Decollation**.

Next is **Bloodrake** on 4 random players (Tanks/Healers or DPS) followed by **Aetheric Chlamys**. Right after there is another **Bloodrake** on 4 random players again.

The players hit by the second **Bloodrake** will stack behind *Hesperos*. Then he will cast **Director's Belone** and assign <span class='speDebuff'>Role Call</span> to 4 players. The debuffs will spread immediately among the player in the stack. The two players left without a debuff have to ran into the stack, one at a time, to get their <span class='speDebuff'>Role Call</span>.  
Once everyone got a debuff, the players hit by the first **Bloodrake** will stack behind the boss at max melee range while he start casting **Inversive Chlamys**. During the cast, the other players have to move between the boss and the stack to grab the tethers. Once every tethers are taken, the Ranged tethers will move away from the boss East and West while the two Melee tethers will move North of the boss and spread:
{% assign slideCounter = 0 %}
{% include slideshow.html imgLink="bd1-1.jpg;bd1-2.jpg;bd1-3.jpg;bd1-4.jpg;bd1-5.jpg" imgDesc="Second <strong>Bloodrake</strong> players stack South;<strong>Role Call</strong> debuffs are assigned;The two players without <strong>Role Call</strong> ran into the stack to get them;First <strong>Bloodrake</strong> players stack South outside the boss, the others inside;The players inside grab the tethers and fan out on the North side" slideNumber=slideCounter %}

Heal everyone before **Decollation**. It's followed by **Elegant Evisceration** on the main target, use the Tank invulnerability here.

*Hesperos* will then cast **Setting the Scene**, as soon as the cast is over the main Tank can move the boss to a cardinal next to the Lava(fire) tile for uptime.
Right after, the boss will cast **Pinax** activating the tiles:

+ If the first tile is **(Lightning)**, move to the edge where the boss is, inside the **(Fire)** tile:  
  + if **(Fire)** is second, form two light groups, one along the edge, the other close to the middle.  
  + if **(Poison)** is second, spread out in the arena, Melees around the boss and ranged anywhere else in the arena.  
+ If the first tile is **(Water)**, move to the edge where the boss is, inside the **(Fire)** tile. Or you can use your knockback immunity to prepare for the second tile positions:  
  + if **(Fire)** is second, form two light groups, one along the edge, the other close to the middle.  
  + if **(Poison)** is second, spread out in the arena, Melees around the boss and ranged anywhere else in the arena.

After the 2nd **Mekhane** *Hesperos* will move back to the middle and cast **Northernly/Easternly/Southernly/Westernly Shift**, check where he's jumping and if he'll use his sword or cape. After the third tile activated, he will jump and perform his attack, either stand on *Hesperos* sides for the sword **Swift** or in front of him for the cape **Swift**.  
There's 10 seconds between the third and fourth tile to do the **Swift** mechanic and get into positions for the fourth tile.

+ If the third tile is **(Lightning)**, move to the edge where *Hesperos* is jumping to:  
  + if **(Fire)** is fourth, form two light groups, one along the edge, the other close to the middle.  
  + if **(Poison)** is fourth, spread out in the arena, Melees around the boss and ranged anywhere else in the arena. The boss can be move middle as soon as **Swift** is over to create more space for Melees.  
+ If the third tile is **(Water)**, stand middle and aim to get knocked where *Hesperos* is jumping to. Or you can use your knockback immunity to prepare for the fourth tile positions and avoid, at the same time, the possible knockback from **Swift**:  
  + if **(Fire)** is fourth, form two light groups, one along the edge, the other close to the middle.  
  + if **(Poison)** is fourth, spread out in the arena, Melees around the boss and ranged anywhere else in the arena. The boss can be move middle as soon as **Swift** is over to create more space for Melees.

*Hesperos* wil continue with **Elegant Evisceration**, remember to swap before if you use the other Tank invulnerability.

Then he will use **Bloodrake** on everyone + 3 tiles, remember the element of the tile that wasn't tethered for later.

The tiles will come back with **Setting the Scene**, then he will use **Vengeful Belone** to assign an <span class='speDebuff'>Acting Role</span> to everyone. Next is **Elemental Belone**, giving you the <span class='speDebuff'>Elemental Resistance Down</span> debuff based on the previous **Bloodrake**.

*Hesperos* will use **Bloodrake** as a raid-wide and will follow up with **Belone Bursts**.  
Before **Belone Bursts** cast is over, take the following positions in pairs:

+ One Tank on North and one Healer on North East.
+ The other Tank South and the other Healer on South West.
+ A Melee and Ranged DPS on East and South East.
+ The other Melee and Ranged DPS on West and North West.

When the orbs appear, each pair will run to the next clockwise cardinal and pop the orb there. Next, move to the next intercardinal and pop the remaining orb. Remember to mitigate before or wait between the two orbs to receive some healing:
{% assign slideCounter = slideCounter | plus: 1 %}
{% include slideshow.html imgLink="burst1.jpg;burst2.jpg;burst3.jpg;burst4.jpg;burst5.jpg" imgDesc="Spread around the boss;Orbs spawn;Move to the next clockwise cardinal with your pair;Soak the first orb;Wait a bit for heals and soak the second orb" slideNumber=slideCounter %}

Quickly take out the orbs before he start casting **Periaktoi** then stand into the tile that wasn't tethered previously.
</div>

<div class='guideSection' markdown='1'>
<a id='SPhase2'></a>
Grab the boss North before he cast the next **Bloodrake** on everyone. He will be followed by **Belone Coils** and **Inversive Chlamys**. Have everyone stack behind the boss, players of the forbidden role(s) will grab the tether and spread along the North edge while the other will soak the towers.
Example with towers forbidden for DPS:
<img class='soloImg' src='{{ page.imagePath | append: 'coil.jpg' }}'>

He will then cast **Aetheric Chlamys** that will force the role(s) who grabbed the tethers to grab them again on the next **Inversive Chlamys**.

Next is another **Bloodrake** on every players followed by another **Belone Coils**. Players who can take the towers have to move in.  
Once they're soaked, these players will move middle for the incoming **Director's Belone** to immediately spread <span class='speDebuff'>Role Call</span> among these players. When it's done, the 2 players without a debuff have to move in to get one.  
Then the players who got hit by the previous **Inversive Chlamys** will grab the tethers and everyone will assume the same positions used for the first mechanic.

*Heperos* will carry on with **Decollation** followed by **Elegant Evisceration**, remember to swap to use the remaining Tank invulnerability.

Next is **Setting the Scene** into **Pinax**, same as previously. Four different **Mekhane** with a random **Swift** between the third and forth **Mekhane**.

*Heperos* will cast **Decollation** three time in a row before enraging. His needs to be brought down under 50% HP or it will be a wipe.

</div>
