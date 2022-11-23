---
layout: guides
title: Dragonsong's Reprise | DSR
imagePath: /assets/img/guides/ultimates/DSR/
slideNumber: 25
---

*Patch: 6.11  
Minimum ilvl: i600  
Maximum ilvl: i605  
Maxsubstat ilvl: (i725 probably)  
DPS Requirement: ~1524890k or a bit less if you sacrifice a Lala  
Loot:*

+ *Token: 1 Dragonsong Totem (1 token for an Ultimate Weapon of the Heavens)*

> Notes: Only one potion can be used in the last phase. Note that if one potion is used at the beginning of *Nidhogg & Hraesvelgr* phase, a second one can be used at the end of *Dragon-king Thordan*.
> Every <span class='debuff'>Damage Down</span> in this fight last 3 minutes and reduce damage by 50%. If there's no incoming mechanic, it can be better to die and come back with a <span class='debuff'>Weakness</span>.

___

<h1><a id='Phase1-TheVaultKnights'>Phase 1 - The Vault Knights</a></h1>

<div class='guideSection' markdown='1'>
<h2><a id='Phase1-TheVaultKnightsAbilitiesBreakdown'>Abilities Breakdown</a></h2>

*Ser Adelphel* and *Ser Grinnaux* must be killed at the same time. When one die, the other will start casting his enrage.

___

+ **<u>Holiest of Holy</u>:**
Raid-wide AoE from *Ser Adelphel* dealing <span class='magic'>magical damage</span>.

___

+ **<u>Empty Dimension / Full Dimension</u>:**
AoE based on *Ser Grinnaux* position, dealing <span class='magic'>magical damage</span> and applying a <span class='debuff'>Damage Down</span> debuff:
  + **Empty Dimension** has a donut shape.
  + **Full Dimension** has a pointblank shape.

___

+ **<u>Holy Shield Bash</u>:**
AoE tank buster tether from *Ser Adelphel* (& *Ser Janlenoux*) dealing AoE <span class='phys'>physical damage</span> and applying <span class='speDebuff'>Down for the Count</span> debuff lasting 6 seconds.  
Deals less damage the further away *Ser Adelphel* is.

___

+ **<u>Holy Blade Dance</u>:**
6-hits tank buster from *Ser Adelphel* (& *Ser Janlenoux*) dealing <span class='phys'>physical damage</span>.  
If enough distance has been covered with **Holy Shield Bash**, the number of **Holy Blade Dance** hit can be reduced down to three.

___

+ **<u>Heavensblaze</u>:**
Share AoE from *Ser Charibert* dealing <span class='magic'>magical damage</span>. He will target any random player but the Tanks.  
Since *Ser Charibert* is outside and not targetable, he's not affected by targeted debuffs such as Reprisal.

___

+ **<u>Hyperdimensional Slash</u>:**
*Ser Grinnaux* will mark 4 random players than will get hit by a line AoE dealing <span class='magic'>magical damage</span> and applying a <span class='debuff'>Magic Vulnerability Up</span> debuff.  
An *Aetherical Tear* will appear where the line AoE meets the wall:

  + It deals very high <span class='magic'>magical damage</span> and applies a <span class='debuff'>Damage Down</span> debuff to any player close to it. (named **Dimensional Torsion**)
  + It deals raid-wide <span class='magic'>magical damage</span> and applies a <span class='debuff'>Damage Down</span> debuff if two *Aetherical Tear* are too close to each other or if a boss is too close to it. (named **Dimensional Purgation**)

  A random player among the 4 others players will get targeted by a 120° shared cleave dealing <span class='magic'>magical damage</span> and applying a <span class='debuff'>Magic Vulnerability Up</span> debuff.

___

+ **<u>Faith Unmoving</u>:**
AoE knockback from *Ser Grinnaux* dealing small <span class='phys'>physical damage</span>.

___

+ **<u>Shining Blade</u>:**
*Ser Adelphel* will appear on a random cardinal. He will dash between cardinals, 3 three times in a Z shape followed by a last dash towards his starting position. Each dash deals lethal damage and applies a <span class='debuff'>Damage Down</span> debuff.  
On the dash paths, multiple *Brightspheres* will spawn. After 2 seconds, the *Brightsphere* will explode in AoE, dealing <span class='magic'>magical damage</span> and applying a <span class='debuff'>Damage Down</span> debuff. (named **Bright Flare**)

___

+ **<u>Execution</u>:**
AoE tank buster from *Ser Adelphel* dealing <span class='magic'>magical damage</span>. It will knock away any player hit but the main target.

___

+ **<u>Holiest Hallowing</u>:**
After a 4 seconds cast, *Ser Adelphel* will heal himself for 500k HP and *Ser Grinnaux* for 1M HP. ***Can be interrupted.***

___

+ **<u>Holy Chain</u>:**
Every player will be chained and marked with <span class='speDebuff'>Burning Chains</span> to another random player, both sharing the same marker. The chains can be broken based on distance.  
If two players are close to each other when <span class='speDebuff'>Burning Chains</span> spawned, it will easily break meanwhile if they are far from each other at start, they'll have to run further away.  
After a set time and if the chains aren't broken, the players will receive <span class='magic'>magical damage</span> and a <span class='debuff'>Damage Down</span> debuff every 3 seconds.

  The markers are assigned in a half random manner:

  + Tanks will be marked with a <span style='color: dodgerblue'>Cross</span> and a <span style='color: MediumPurple'>Square</span>.
  + Healers will be marked with a <span style='color: dodgerblue'>Cross</span> and a <span style='color: MediumSeaGreen'>Triangle</span>.
  + DPS will be marked with a <span style='color: MediumPurple'>Square</span>, a <span style='color: MediumSeaGreen'>Triangle</span> and two <span style='color: Tomato'>Circles</span>.

___

+ **<u>Heavensflame</u>:**
AoE on every player dealing fire <span class='magic'>magical damage</span> and applying a <span class='debuff'>Fire Resistance Down II</span> debuff.

___

+ **<u>Brightblade's Steel & The Bull's Steel</u>:**
*Ser Adelphel* and *Ser Grinnaux* respective enrages. They will fully heal themselves and gain <span class='buff'>Invincibility</span> and <span class='buff'>Damage Up</span> buffs, wiping everyone with their next attacks.

___

+ **<u>Planar Prison</u>:**
*Ser Grinnaux* will stun and pull everyone towards him. Afterward, he will chain himself with every player, applying a <span class='speDebuff'>Planar Imprisonment</span> <img class='iconImg' src='{{ site.data.iconList.DSR.PlanarImprisonment }}'> debuff, forcing the players to stay inside the reduced arena.

___

+ **<u>Spear of the Fury</u>:**
*Ser Zephirin* will cast it from outside the arena. *Haurchefant* will move in to intercept the attack. He will receive a <span class='speDebuff'>HP Recovery Down</span> debuff that reduces incoming healing by 100%.  
While he's alive, *Haurchefant* and the group will get hit by **Shockwave** every second, dealing unaspected raid-wide damage.

___

+ **<u>Brightwinged Flight</u>:**
*Ser Adelphel* will protect *Ser Charibert* while giving him two buffs:
  + <span class='buff'>Brightwinged Fortitude</span>: reducing damage taken.
  + <span class='buff'>Brightwinged Fury</span>: when this buff has 18 seconds left, the two closest players will be targeted every 5 seconds with a thin cleave (**Brightwing**) dealing light <span class='magic'>magical damage</span>, applying a <span class='debuff'>Light Resistance Down</span> debuff lasting 18 seconds and a <span class='speDebuff'>Skyblind</span> <img class='iconImg' src='{{ site.data.iconList.DSR.Skyblind }}'> debuff lasting 5 seconds. When <span class='speDebuff'>Skyblind</span> resolves, a small AoE will explode at the player location after 2 seconds, dealing high <span class='magic'>magical damage</span>.

___

+ **<u>Pure of Heart</u>:**
When the cast is over, *Ser Charibert* will deal raid-wide <span class='magic'>magical damage</span> based on his remaining HP (unchanged when he's under 30%).

</div>

<div class='guideSection' markdown='1'>
<h2><a id='Phase1-TheVaultKnightsStrategy'>Strategy</a></h2>

Pull both bosses and bring them middle. Focus *Ser Adelphel* during the opener since he will disappear multiple times during the phase.  
*Ser Adelphel* will use **Holiest of Holy**.

Next, *Ser Grinnaux* will start casting **Empty Dimension** and *Ser Adelphel* will tether to a random player.  
The group will move South, on *Ser Grinnaux* hitbox, to mitigate and stack together for the incoming **Heavensblaze**. Meanwhile, one Tank will grab the tether, move North of *Ser Grinnaux* and use his invulnerability to cover for **Holy Shield Bash** and **Holy Blade Dance**.  
<img class='soloImg' src='{{ page.imagePath | append: 'holyBash.jpg'}}'>

*Ser Adelphel* will leave the arena and *Ser Grinnaux* will jump to the middle to cast **Hyperdimensional Slash**.  
The marked players will fan out North and aim as shown in the diagram while the 4 others stack South the boss. Once the first set of attacks is done, roles will be reversed, with marked players fanning out South and the rest stacking North:
{% assign slideCounter = 0 %}
{% include slideshow.html imgLink="hyperdim1.jpg;hyperdim2.jpg" imgDesc="Marked players fan out North, the rest stack South;Marked players fan out South, the rest stack North" slideNumber=slideCounter %}

*Ser Adelphel* will appear on a cardinal and *Ser Grinnaux* will cast **Faith Unmoving**. Move away from *Ser Adelphel* or use the knockback from **Faith Unmoving** to do so and wait for *Ser Adelphel*.  
After the first dash, move towards the cardinal where *Ser Adelphel* dashed to and stop mid-way to dodge the *Brightspheres* explosions.  
The Tank with *Ser Adelphel* 's aggro will resume his course after the explosion to take **Execution** alone:
{% assign slideCounter = slideCounter | plus: 1 %}
{% include slideshow.html imgLink="shinning1.jpg;shinning2.jpg;shinning3.jpg;shinning4.jpg" imgDesc="Watch where <em>Ser Adelphel</em> is and get knocked to the opposite side;Watch where he dashes and move in that direction;Stop mid-way to dodge <em>Brightspheres</em> explosions;<em>Ser Adelphel</em>'s Tank resume his run for <strong>Execution</strong>" slideNumber=slideCounter %}

Bring back the bosses middle. The Tank in charge of *Ser Adelphel* must interrupt **Holiest Hallowing** cast in the mean time.

Soon after, *Ser Grinnaux* will cast **Faith Unmoving** and chain markers will be applied to everyone:

+ The Tanks move North of *Ser Grinnaux* and the Healers South before the chains are assigned.
+ The Tank and Healer with the <span style='color: dodgerblue'>Cross</span> won't move while the Tank with the <span style='color: Orchid'>Square</span> will move to the next clockwise spot and the Healer with the <span style='color: MediumSeaGreen'>Triangle</span> will move to the next counter-clockwise spot.
+ The DPS with the <span style='color: MediumSeaGreen'>Triangle</span> and <span style='color: Orchid'>Square</span> will move to the opposite side of their partner and the two <span style='color: Tomato'>Circle</span> take the remaining East and West spots.  
Stand inside *Ser Grinnaux* hitbox to get knocked away and easily break the chains then wait a bit for **Heavensflame** to resolve on everyone before regrouping.
{% assign slideCounter = slideCounter | plus: 1 %}
{% include slideshow.html imgLink="chain1.jpg;chain2.jpg;chain3.jpg;chain4.jpg;chain5.jpg" imgDesc="Tanks North and Healers South;Tank/Healer Cross stay, Tank Square move one spot clockwise, Healer Triangle move one spot counter-clockwise;DPS fill the gap and Circles adjust;Stand inside <em>Ser Grinnaux</em> hitbox and get knocked back;Wait for <strong>Heavensflame</strong>" slideNumber=slideCounter %}

The physical ranged DPS (or the Tank in charge of *Ser Grinnaux*) must interrupt **Holiest Hallowing** cast that happens right after **Heavensflame**.

Bring back the bosses together. Mitigate the incoming **Holiest of Holy** and move in or out for **Empty/Full Dimension**.  
Immediately after, the Tank in charge of *Ser Adelphel* must interrupt the **Holiest Hallowing** cast.  
Afterward, *Sir Adelphel* will cast another **Holiest of Holy**.

Finally they will cast their enrages **Brightblade's Steel** and **The Bull's Steel**.

___

<a id='SPlanarImprisonment'></a>If they are killed in time, *Ser Grinnaux* will pull everyone into a smaller arena. Right after, *Ser Charibert* will start to cast **Pure of Heart** and need to be brought as low as possible.

The group will stay middle at max melee range. Then the first pair will move inside *Ser Charibert*  's hitbox between him and the wall to bait the first set of **Brightwing** towards the outside. Once they're hit, they move to a side of the arena at max melee range and wait there to lose their <span class='speDebuff'>Skyblind</span> debuff before going back with the group.  
The pairs order is the following: <u>Healers -> Ranged DPS -> Melee DPS -> Tanks</u>. The Healers and Melee DPS will move to the left side to drop their debuff while the Ranged DPS will move to the right side:
{% assign slideCounter = slideCounter | plus: 1 %}
{% include slideshow.html imgLink="planar1.jpg;planar2.jpg;planar3.jpg;planar4.jpg;planar5.jpg;planar6.jpg" imgDesc="Healers move in;Healers to the left side and Ranged DPS move in;Ranged DPS to the right side and Melee DPS move in;Melee DPS to the left side and Tanks move in;Tanks can wait here;Tanks mid and prepare for <strong>Pure of Heart</strong>" slideNumber=slideCounter %}

If one person survive, you'll reach the next phase that has a checkpoint.  
*Note: if Ser Charibert won't be low enough, you can cheese the mechanic by boosting a Tank mitigation so he may survive the damage or timing a resurrection right when Pure of Heart is happening.*
</div>

<h1><a id='Phase2-KingThordan'>Phase 2 - King Thordan</a></h1>

<div class='guideSection' markdown='1'>
<h2><a id='Phase2-KingThordanAbilitiesBreakdown'>Abilities Breakdown</a></h2>

*King Thordan* auto-attacks are cone cleaves.

___

+ **<u>Ascalon’s Mercy Concealed</u>:**
Cone from *King Thordan* aimed at every players dealing <span class='phys'>physical damage</span> and applying a <span class='debuff'>Damage Down</span> debuff. The players positions are snapshot at the end of the cast and the cones are fired 2 seconds later.

___

+ **<u>Ascalon’s Might</u>:**
120° cleave tank buster on the main target dealing slashing <span class='phys'>physical damage</span>.

___

+ **<u>Strength Of The Ward</u>:**

  + **<u>Spiral Thrust</u>:**
  Line AoE performed by the Spear Knights that cross the arena through the middle, dealing <span class='phys'>physical damage</span>.

    ___

  + **<u>Lightning Storm</u>:**
  AoE on everyone dealing <span class='magic'>magical damage</span> and applying a <span class='debuff'>Lightning Resistance Down II</span> debuff.

    ___

  + **<u>Heavy Impact</u>:**
  Multiple delayed hit AoE performed by the Axe Knight that grow each time, dealing <span class='magic'>magical damage</span> on every hit and applying a <span class='debuff'>Damage Down</span> and a <span class='debuff'>Stun</span> debuff.  
  The first AoE is pointblank while the four next are donut-shaped. Each donut encompass the previous AoE.

    ___

  + **<u>Dimensional Collapse</u>:**
  Ground AoEs that grow over time, dealing <span class='magic'>magical damage</span>, applying a <span class='debuff'>Damage Down</span> debuff and a <span class='debuff'>Heavy</span> debuff that last 30 seconds. Grow 7 times before exploding.

    ___

  + **<u>Conviction</u>:**
  Towers that deal small <span class='magic'>magical damage</span> when soaked. Deals very high raid-wide <span class='magic'>magical damage</span> and applies a <span class='debuff'>Damage Down</span> and a <span class='debuff'>Paralysis</span> debuff when not soaked.

    ___

  + **<u>Skyward Leap</u>:**
  A non-Tank player receive a blue marker. After 9 seconds, a knight will dive that player in AoE, dealing <span class='magic'>magical damage</span>, applying a <span class='debuff'>Physical Vulnerability Up</span> debuff and a <span class='debuff'>Magic Vulnerability Up</span> debuff.

    ___

  + **<u>The Dragon’s Rage</u>:**
  Share AoE on a non-Tank and non **Skyward Leap** marked player, dealing <span class='magic'>magical damage</span>.

___

+ **<u>Ancient Quaga</u>:**
Raid-wide AoE dealing <span class='magic'>magical damage</span>.

___

+ **<u>Heavenly Heel</u>:**
Tank buster on the main target dealing <span class='phys'>physical damage</span> and applying a <span class='debuff'>Slashing Resistance Down</span> debuff.

___

+ **<u>Sanctity Of The Ward</u>:**

  + **<u>The Dragon’s Gaze / The Dragon's Glory</u>:**
  *King Thordan* and a *Dragon Eye* will appear on a different random cardinal/intercardinal. Require the players to look-away from both else they receive unaspected damage along with a <span class='debuff'>Damage Down</span> and an <span class='debuff'>Hysteria</span> debuff..

    ___

  + **<u>Sacred Sever</u>:**
  Two players will receive a one or two swords marker. After a few second *Ser Zephirin* will dash on the player with the one sword then to the two swords marked player. It will repeat this a second time.  
  Each hit is a share that deals <span class='phys'>physical damage</span> and applies <span class='debuff'>Physical Vulnerability Up</span> debuff. The damage decreases the further away the marked player is from *Ser Zephirin*.

    ___

  + **<u>Heimal Storm</u>:**
  Shares AoE dealing <span class='magic'>magical damage</span> and applying a <span class='debuff'>Ice Resistance Down II</span> debuff. Leaves an ice puddle that apply <span class='debuff'>Frostbite</span>.  
  *Ser Grinnaux* will target either the Tanks/Healers or the DPS.

    ___

  + **<u>Heavens' Stake</u>:**
  Four large fire AoE dealing <span class='magic'>magical damage</span> will appear on intercardinal halfway between the centre and the edge. They leave a fire puddle that apply <span class='debuff'>Burn</span>.

    ___

  + **<u>Holy Comet</u>:**
  Two Tanks/Healers or two DPS receive a red marker. When it disappears, meteors will drop at the player location at regular interval.  
  When a meteor drops it deals small <span class='magic'>magical damage</span> to surround players. If two meteors are to close to each other, they will explode and deal very high <span class='magic'>magical damage</span> and apply a <span class='debuff'>Damage Down</span> debuff.

___

+ **<u>Ultimate End</u>:**
Raid-wide AoE dealing very high <span class='magic'>magical damage</span> requiring mitigation. After the attack, *Thordan* will gain the <span class='debuff'>Discomposed</span> <img class='iconImg' src='{{ site.data.iconList.DSR.Discomposed }}'> debuff, increasing the damage taken.

___

+ **<u>Broad Swing</u>:**
*King Thordan* will perform three 120° cleaves dealing <span class='phys'>physical damage</span> and applying a <span class='debuff'>Damage Down</span> debuff. Each hit knocks away.  
He will cleave towards his North West, North East and South with the South one always being the last hit.

___

+ **<u>Aetheric Burst</u>:**
Enrage.

</div>

<div class='guideSection' markdown='1'>
<h2><a id='Phase2-KingThordanStrategy'>Strategy</a></h2>

> You can restart the fight to reset your cooldowns since this phase acts as a checkpoint.

Pull *King Thordan* and have the group stacked behind the boss to bait the incoming **Ascalon's Mercy Concealed**. When the cast bar is over, dodge to his sides.  
Right after, *King Thordan* will perform **Ascalon’s Might** three times in a row, mitigate this or use a Tank invulnerability to go through.  
Next *King Thordan* will summon his Knights and cast **Strength of the Ward**. You can swap Tanks during the cast for later.

<a id='SStrengthOfTheWard'></a>As soon as *King Thordan* leaves, everyone has to spread around the arena and wait for the Dragoon Knights to arrive. If a player has a Dragoon Knight behind him, that player will move towards the middle of the arena telling that his position is unsafe. The player on the opposite side will also move to the middle since it's not safe. The players who moved will regroup at the safe spots with their respective light party in order to dodge **Spiral Thrusts**.  
Then each light party will form a triangle within their safe spot to avoid overlapping **Lightning Storm**. The Healer shall be on the corner near the middle, the DPS on corners along the edge and the Tank along the edge between the DPS:
{% assign slideCounter = slideCounter | plus: 1 %}
{% include slideshow.html imgLink="strength1.jpg;strength2.jpg;strength3.jpg" imgDesc="Spread out;Find the safe spots;Regroup with your party" slideNumber=slideCounter %}

Once both attacks are done, each party regroups and dodge together the **Heavy Impact** AoEs. Watch the enemy list for **Ascalon’s Might** cast bar and move out to dodge them. Then, get some healing before the next mechanics.

Then two Paladin Knights will appear along with **Dimensional Collapse** AoEs and **Conviction** towers. *King Thordan* will also move to the cardinal/intercardinal opposite of the Paladin Knights (where they're facing at).  
Three non-Tank players will receive a **Skyward Leap** marker and each of them has to move to a safe spot away from *King Thordan*, next to the edge. <u>The two players on cardinals adjacent to <em>King Thordan</em> have to move away from him by a few step.</u>  
The non-Tank players that aren't marked will move right underneath *King Thordan* to receive **The Dragon’s Rage**. The two Tanks has to quickly grab the **Holy Shield Bash** tethers and run towards *King Thordan* safe spot. The Tanks will take the far left/right corner of the safe spot while crossing the tethers to reduce the damage taken and create a bigger safe zone for the non-marked players.  
Once **Skyward Leap** and **The Dragon’s Rage** are done. The previously marked players will move into the tower in front of them while the players who stacked will split among the 3 closest towers.
Example with *King Thordan* North:
{% assign slideCounter = slideCounter | plus: 1 %}
{% include slideshow.html imgLink="strength4.jpg;strength5.jpg;strength6.jpg" imgDesc="<strong>Skyward Leap</strong> players spread away from <em>King Thordan</em>, unmarked players under him and Tanks to their sides with tethers crossed;Everything resolves;Everyone moves into the closest tower" slideNumber=slideCounter %}

When *King Thordan* jumps back mid, regroup and heal everyone for the incoming **Ancient Quaga**.  
Followed by **Heavenly Heel** into three **Ascalon’s Might**, initiate a Tank swap during **Heavenly Heel** and mitigate or use a Tank invulnerability.  
Next *King Thordan* will once again summon his Knights and cast **Sanctity of the Ward**.

<a id='SSanctityOfTheWard'></a>Two Paladin Knights will appear mid, facing opposite direction and a Dark Knight (*Ser Zephirin*) will appear along the edge. Quickly identify *Ser Janlenoux* (Silver armour with a white plume), if he's on the West side, everyone will rotate counter-clockwise to dodge, if he's East then it's clockwise. (You can also check the closest Paladin after you're grouped, you'll move towards the intercardinal that this Paladin isn't facing to)  
When *King Thordan* leaves, quickly form two groups of 4 East and West. Then two **Sacred Sever** markers will appear and groups need to be readjusted:

+ Marked player: they change group in order that #1 is away from *Ser Zephirin* while #2 is near him.
+ Non-marked Tanks: if there's no marker in your group, swap group. Otherwise stay.
+ Non-marked player: do nothing ᕕ( ᐛ )ᕗ

With the group reformed, take position to the East and West next to the edge and turn away from *King Thordan* and the *Dragon Eye*. If one of them is East or West, you can take a few step clockwise/counter-clockwise to have an easier time to dodge.  
When everything is happening, both groups must run clockwise or counter-clockwise based on *Ser Janlenoux* 's position but stop before they reach the next intercardinal spot in order to end up in the small safe spot available.  
Once the *Brightspheres* from the second dash explode, go back to your East and West spot to avoid the last dashes.

Here's an example with *Ser Janlenoux* being West, so dodging counter-clockwise:
{% assign slideCounter = slideCounter | plus: 1 %}
{% include slideshow.html imgLink="sanctity1.jpg;sanctity2.jpg;sanctity3.jpg;sanctity4.jpg;sanctity5.jpg;sanctity6.jpg" imgDesc="Split into light group and look out for <em>King Thordan</em>, the <em>Dragon Eye</em> and <em>Ser Janlenoux</em>;Reform group with marker 1 away from <em>Ser Zephirin</em> and marker 2 close to him;Move to the East and West and look away from <em>King Thordan</em> and the <em>Dragon Eye</em>;Move to the next counter-clockwise intercardinal but stop a few notch away from it during the second dash;You're safe from the second set of <em>Brightspheres</em> explosion;Move back to the East and West" slideNumber=slideCounter %}

Everyone regroups mid for heal then pre-spread in pairs at each cardinal with a Tank/Healer and a DPS. Each pair will be in charge of a quadrant as shown below:
<img class='soloImg' src='{{ page.imagePath | append: 'sanctityMeteor.jpg'}}'>

Two players will get the meteor marker. These players need to be on pair opposite of each other: North and South by default, the only exception is if they're already opposite of each other East and West. If a player need to swap his position, he has to swap with a player of the same role, a Tank/Healer with another Tank/Healer for example.  
Once the groups are set, each pair has to stand between the **Heavens' Stake** AoEs to place **Heimal Storm** without overlapping inner and outer towers.  
After **Heimal Storm** happens, it's time to soak **Conviction** towers within your quadrant:

+ If there's one inner and one outer tower, the meteor player role moves out and the other moves in.
+ If there's two outer towers, the Tank/Healer takes the most clockwise one while the DPS takes the most counter-clockwise one.
+ Inner players adjust with the available towers *rollSafe*.

Once the first set of towers are soaked, the meteor players start to run clockwise around the arena without sprinting to reach the tower on the opposite side, North and South.  
<u>Players with the same role as the meteor players will soak the cardinals towers while the others will soak the intercardinal towers.</u>  
After a few second **Faith Unmoving** will happen, meteor and outer players must use their knockback immunity while the inner players use the knockback to get into their towers:
{% assign slideCounter = slideCounter | plus: 1 %}
{% include slideshow.html imgLink="sanctity7.jpg;sanctity8.jpg;sanctity9.jpg;sanctity10.jpg;sanctity11.jpg" imgDesc="Preform pairs on cardinals;Adjust pairs to have meteor players on North and South then move away to place the <em>Heimal Storm</em>;Move into your assigned tower;Meteor players start to run around clockwise, outer players get into their towers, inner players aligned themselves towards their towers;Either use the knockback to get into your towers or use your immunity" slideNumber=slideCounter %}

From this point, you may hold your 2 minutes cooldown for the reopener on the next phase if needed.  
*King Thordan* will teleport North and cast **Ultimate End**. Heal and use proper mitigation for this raid-wide.  
Then *King Thordan* will move a bit towards mid and use **Broad Swing**. Stand behind him and move into the first cleave once it happens. He will turn and repeat this a second time.

The enrage, **Aetheric Burst**, is then casted to end this phase.
</div>

<h1><a id='Phase3-Nidhogg'>Phase 3 - Nidhogg</a></h1>

<div class='guideSection' markdown='1'>
<h2><a id='Phase3-NidhoggAbilitiesBreakdown'>Abilities Breakdown</a></h2>

*Nidhogg* auto-attacks are line cleaves.

___

+ **<u>Final Chorus</u>:**
Raid-wide AoE dealing very high <span class='magic'>magical damage</span>. Require mitigation.

___

+ **<u>Dive from Grace</u>:**
Every player will receive a number along with a corresponding debuff tell them the order in which **Dark Elusive/High/Spineshatter Jump** will happen:
  + <span class='speDebuff'>First in Line</span> <img class='iconImg' src='{{ site.data.iconList.DSR.FirstInLine }}'>: on three players, attacked after 9 seconds.
  + <span class='speDebuff'>Second in Line</span> <img class='iconImg' src='{{ site.data.iconList.DSR.SecondInLine }}'>: on two players, attacked after 19 seconds.
  + <span class='speDebuff'>Third in Line</span> <img class='iconImg' src='{{ site.data.iconList.DSR.ThirdInLine }}'>: on three players, attacked after 30 seconds.

  At the end of the cast everyone will receive a second debuff among <span class='speDebuff'>High Jump Target</span>, <span class='speDebuff'>Elusive Jump Target</span> and <span class='speDebuff'>Spineshatter Dive Target</span>.

  *Note that for each set of <span class='speDebuff'>First/Second/Third in Line</span> debuff, an <span class='speDebuff'>Elusive Jump Target</span> is always pared with a <span class='speDebuff'>Spineshatter Dive Target</span>.*

___

+ **<u>Dark Elusive/High/Spineshatter Jump</u>:**
AoE on a player dealing <span class='phys'>physical damage</span> and applying a <span class='debuff'>Physical Vulnerability Up</span> for 3 seconds and a <span class='debuff'>Fire Resistance Down II</span> debuff for 12 seconds.  
It will also consume the player's Target debuff and a **Darkdragon Dive** tower will spawn based on the direction he's looking at:

  + <span class='speDebuff'>High Jump Target</span> <img class='iconImg' src='{{ site.data.iconList.DSR.HighJumpTarget }}'>: at the player feet
  + <span class='speDebuff'>Elusive Jump Target</span> <img class='iconImg' src='{{ site.data.iconList.DSR.ElusiveJumpTarget }}'>: 10m behind the player
  + <span class='speDebuff'>Spineshatter Dive Target</span> <img class='iconImg' src='{{ site.data.iconList.DSR.SpineshatterDiveTarget }}'>: 10m in front of the player

> Nidhogg hitbox is ~10m wide.

___

+ **<u>Darkdragon Dive</u>:**
Tower that deals small <span class='magic'>magical damage</span>, applies a <span class='debuff'>Fire Resistance Down II</span> and a <span class='debuff'>Physical Vulnerability Up</span> debuff when soaked. Deals very high raid-wide <span class='magic'>magical damage</span> and applies a <span class='debuff'>Damage Down</span> debuff when not soaked.  
Once the tower is soaked, a clone of *Nidhogg* appears and casts **Geirskogul**.

  After **Dive from Grace**, 4 towers will spawn at intercardinals, requiring 1 to 4 players per tower where the sum equals 8. Afterward, all the clones but one will cast **Geirskogul**, the last one will cast **Soul Tether**.

___

+ **<u>Geirskogul</u>:**
Untelegraphed line AoE aimed at the closest player from *Nidhogg* 's clone dealing <span class='magic'>magical damage</span> and applying a <span class='debuff'>Damage Down</span> debuff.

___

+ **<u>Gnash and Lash / Lash and Gnash</u>:**
*Nidhogg* will launch two AoE attacks with small knockback, both dealing <span class='magic'>magical damage</span> and applying a <span class='debuff'>Damage Down</span> debuff.  
**Gnash and Lash** consists of **Gnashing Wheel** into **Lashing Wheel** and **Lash and Gnash** is the opposite:
  + **Gnashing Wheel** has a pointblank shape.
  + **Lashing Wheel** has a donut shape.

  There's a 4 seconds delay between the end of the cast and the first attack.

___

+ **<u>Eye of the Tyrant</u>:**
A random player in front of *Nidhogg* is targeted by a share AoE dealing <span class='magic'>magical damage</span>.  
<u>It is non-casted and is always used when the cast of <strong>Gnash and Lash/Lash and Gnash</strong> is complete.</u>

___

+ **<u>Drachenlance</u>:**
Untelegraphed frontal cleave aimed at a random player dealing very high <span class='phys'>physical damage</span>.

___

+ **<u>Soul Tether</u>:**
AoE tank buster tether dealing <span class='magic'>magical damage</span>.

___

+ **<u>Revenge of the Horde</u>:**
Enrage.

</div>

<div class='guideSection' markdown='1'>
<h2><a id='Phase3-NidhoggEyesAbilities'>Eyes Abilities</a></h2>

After *Estinien* retakes control of his body, *Alphinaud* will appear along with *Haurchefant* and *Ysayle* spirits. Haurchefant will tether to a random player and Ysayle will tether to Alphinaud. After 5 seconds the tethered players will drop a AoE on the ground that gives a buff lasting 90 seconds to anyone inside:

+ <span class='buff'>Soul of Friendship</span> <img class='iconImg' src='{{ site.data.iconList.DSR.SoulOfFriendship }}'>: given by *Haurchefant*, allows to deal damage to the *Right Eye*.
+ <span class='buff'>Soul of Devotion</span> <img class='iconImg' src='{{ site.data.iconList.DSR.SoulOfDevotion }}'>: given by *Ysayle*, allows to deal damage to the *Left Eye*.

Once the *Left Eye* and *Right Eye* appear, the Duty Gauge will start to fill. When it reaches 100, *Nidhogg* will take control of *Estinien* and wipe the groupe. The Duty Gauge dissapears when both *Eyes* are dead.

The *Right Eye* appears with only 50% of its health.

___

+ **<u>Resentment</u>:**
Raid-wide AoE from *Estinien* dealing <span class='magic'>magical damage</span> and applying a <span class='debuff'>Bleeding</span> debuff for 6 seconds.

___

+ **<u>Hatebound</u>:**
2 groups of 4 random players will receive the following debuffs:
  + <span class='speDebuff'>Clawbound</span> <img class='iconImg' src='{{ site.data.iconList.DSR.Clawbound }}'>: these players will be chained to the *Left Eye*, in red. Any damage taken will also damage the *Left Eye*.
  + <span class='speDebuff'>Fangbound</span> <img class='iconImg' src='{{ site.data.iconList.DSR.Fangbound }}'>: these players will be chained to the *Right Eye*, in blue. Any damage taken will heal the *Right Eye*.

  These debuffs can be swapped if two players with different debuffs touch each other. After swapping, both players will receive a <span class='speDebuff'>Bound and Determined</span> <img class='iconImg' src='{{ site.data.iconList.DSR.BoundAndDetermined }}'> debuff for 3 seconds, preventing them to swap again.

___

+ **<u>Flare Nova & Flare Star</u>:**
6 orbs will spawn and grow in size overtime, detonating once they're big enough and wiping the group.  
Each orb deals sharable <span class='magic'>magical damage</span> and applying a <span class='debuff'>Fire Resistance Down II</span> debuff for 12 seconds. The damage scales with the orb size.

  + **Flare Nova**:
  2 medium sized yellow orbs that spawn East and West. Since they're already big, they need to popped by 2 players each. Grow twice before exploding.

    ___

  + **Flare Star**:
  4 small sized blue orbs that spawn North and South of each *Eye*. Since they are small enough they only need to popped by 1 player. Grow four times before exploding.

___

+ **<u>Mirage Dive</u>:**
AoE on 2 random players with <span class='speDebuff'>Clawbound</span> dealing <span class='phys'>piercing physical damage</span> and appylying <span class='debuff'>Piercing Resistance Down</span> debuff for 13 seconds. Any non-targeted player hit is also knocked away.
Happens 4 times with 5 seconds in between.

___

+ **<u>Steep in Rage</u>:**
Raid-wide AoE from both *Left Eye* and *Right Eye* dealing high <span class='magic'>magical damage</span>.

</div>

<div class='guideSection' markdown='1'>
<h2><a id='Phase3-NidhoggStrategy'>Strategy</a></h2>

><a id='SNidhogg'></a>A quick overview before diving in. During **Dive from Grace**, players will receive a set of debuffs and for the whole mechanic, they will use the following positions:
>
> + <span class='speDebuff'>First in Line</span> and <span class='speDebuff'>Third in Line</span>: they take position on West, South and East of *Nidhogg* hitbox. ***With <span class='speDebuff'>Elusive Jump Target</span> on East facing away from the boss and <span class='speDebuff'>Spineshatter Dive Target</span> on West looking at the boss.***
> + <span class='speDebuff'>Second in Line</span>: they take position on North East and North West, slightly outside of *Nidhogg* hitbox. If they have <span class='speDebuff'>Elusive Jump Target</span> and <span class='speDebuff'>Spineshatter Dive Target</span>, they must place their tower under each other.
>In this example, the Summoner will look towards the East to put his tower at *Nidhogg* West side, and the Ninja will look towards the West to put his tower under the Scholar:
><img class='soloImg' src='{{ page.imagePath | append: 'inLine.jpg'}}'>
>
>Furthermore, due to <span class='debuff'>Fire Resistance Down II</span> timers, the **Darkdragon Dive** towers must be soaked by specific player based of your debuff:
>
> + 1st towers: by <span class='speDebuff'>Third in Line</span> players.
> + 2nd towers: by <span class='speDebuff'>First in Line</span> East and West players.
> + 3rd towers: by <span class='speDebuff'>First in Line</span> South player and <span class='speDebuff'>Second in Line</span> players.

Once *King Thordan* is dealt with, heal everyone and use mitigation for when *Nidhogg* slams into the arena with **Final Chorus**.

When *Nidhogg* is casting **Dive from Grace** the players will receive their numbers. <span class='speDebuff'>First in Line</span> and <span class='speDebuff'>Third in Line</span> will pre-spread on East, South and West while <span class='speDebuff'>Second in Line</span> will show their position on North East and North West.  
Then, once the cast is over and Dive debuff are set, <span class='speDebuff'>First in Line</span> and <span class='speDebuff'>Third in Line</span> players can readjust to follow the rule of "<span class='speDebuff'>Elusive Jump Target</span> on East and <span class='speDebuff'>Spineshatter Dive Target</span> on West".

Have <span class='speDebuff'>First in Line</span> players ready for the dives, and the rest of the group stacked in front *Nidhogg* for **Eye of the Tyrant** during **Gnash and Lash/Lash and Gnash** cast, remember the in/out or out/in sequence.  
Once the share and dives happened, quickly move in or out for **Gnash** or **Lash**.  
In the meantime the <span class='speDebuff'>Third in Line</span> player have to get in position to soak the tower, remember to run around the boss hitbox if you must dodge **Gnashing Wheel** to reach South. Move out or in for **Lash** or **Gnash** when soaking the towers. Then move out to bait **Geirskogul**.

Example with **Lash and Gnash**:
{% assign slideCounter = slideCounter | plus: 1 %}
{% include slideshow.html imgLink="dfg1.jpg;dfg2.jpg;dfg3.jpg" imgDesc="<strong>First in Line</strong> dives on East, South and West. The rest stacks North;Dodge <strong>Lashing Wheel</strong>;Dodge <strong>Gnashing Wheel</strong> and <strong>Third in Line</strong> soak towers;Move slightly out to bait <strong>Geirskogul</strong>" slideNumber=slideCounter %}

Right after the second **Lash** or **Gnash** happened, the <span class='speDebuff'>Second in Line</span> players must move to their position to get dived at. Right after, the East and West <span class='speDebuff'>First in Line</span> players will move in to soak the towers and bait the incoming **Geirskogul**.
{% assign slideCounter = slideCounter | plus: 1 %}
{% include slideshow.html imgLink="dfg4.jpg;dfg5.jpg;dfg6.jpg" imgDesc="Move slightly out to bait <strong>Geirskogul</strong>. <strong>Second in Line</strong> dives on North East and North West;East and West <strong>First in Line</strong> soak the towers;Bait <strong>Geirskogul</strong>" slideNumber=slideCounter %}

As soon as the first **Geirskogul** are done, the <span class='speDebuff'>Third in Line</span> players must get into position for their dive and the rest of the party stack North for **Eye of the Tyrant**. Quickly get a look at the **Gnash and Lash/Lash and Gnash** cast and as soon as the **Dark Jumps** and **Eye of the Tyrant** happened, move out or in for **Lash** or **Gnash**.  
Then the <span class='speDebuff'>First in Line</span> South player and <span class='speDebuff'>Second in Line</span> players must get into the towers and dodge out or in for the second **Lash** or **Gnash**. Once it's done, move out and bait the **Geirskogul** as usual.

Example with **Gnash and Lash**:
{% assign slideCounter = slideCounter | plus: 1 %}
{% include slideshow.html imgLink="dfg7.jpg;dfg8.jpg;dfg9.jpg;dfg10.jpg" imgDesc="<strong>Third in Line</strong> at dives positions and the rest stacks North;Dodge <strong>Gnashing Wheel</strong>;Dodge <strong>Lashing Wheel</strong> and South <strong>First in Line</strong> and the <strong>Second in Line</strong> players soak the towers;Bait <strong>Geirskogul</strong>" slideNumber=slideCounter %}

*Nidhogg* will resume his auto-attacks so clear away from the main Tank. He will then cast **Drachenlance** on a random target, dodge it sideways.

Next is the final **Darkdragon Dive** towers, regroups in pairs at each intercardinal. If a tower only need one player, the Tank/Healer will adjust to satisfy another tower condition. The DPS will then bait the three **Geirskogul** towards the outside while the Tanks will grab the two **Soul Tether**. Have one Tank in front of *Nidhogg* and the second under him while the group stay away from them.  
Tanks must use all their mitigation tools and may need additional help from the Healers. One or both Tanks invulnerability can also be used here.

*Nidhogg* will cast a final **Drachenlance** before his enrage, **Revenge of the Horde**.

___

<a id='SLeft&RightEyes'></a>Stack up on *Alphinaud* to receive <span class='speDebuff'>Soul of Devotion</span> and <span class='speDebuff'>Soul of Friendship</span>.

Each Tank must grab the *Eyes* enmity since they will auto-attack. <u>Since the <em>Left Eye</em> will lose most of its health from damages taken by the players, everyone has to focus as much as possible the <em>Right Eye</em>.</u>  
And get some mitigation ready for the incoming **Resentment**.

Next, **Hatebound** will assign a debuff to everyone, be spread before the cast is over to avoid unnecessary swap:

+ Tanks and Melee DPS must get the blue chains, <span class='speDebuff'>Fangbound</span>.
+ Healers and Ranged DPS must get the red chains, <span class='speDebuff'>Clawbound</span>.

Any player with the wrong debuff has to stack mid, under *Estinien*. Thus they will automatically swap their debuffs to the correct one.

Then, Tanks and Healers will move towards the *Left Eye* while the DPS will move towards the *Right Eye*.  
Once the orbs are here, Healers and Ranged DPS have to wait for the yellow orbs to grow once before soaking them in pairs. Then the Tanks and Healers will swap their debuffs and Melee and Ranged DPS will do the same. Finally, the Tanks and Melee DPS will wait for the second growth to happen, before taking the blue orbs:
{% assign slideCounter = slideCounter | plus: 1 %}
{% include slideshow.html imgLink="flare1.jpg;flare2.jpg" imgDesc="Ranged take their orbs;Ranged and Melees swap debuffs then Melees take their orbs" slideNumber=slideCounter %}

Group up around the *Right Eye* without switching your debuffs. The Healers and Ranged DPS will first move inside the *Right Eye* while the Tanks and Melee DPS will spread around it afterward.  
Every time a set of **Mirage Dive** is done, the next pairs will swap their debuff and position with the two players hit. The order is the following one:  
<u>Healers -> Ranged DPS -> Flex</u> (the two players who got hit first, they should have 3s left on their <span class='debuff'>Piercing Resistance Down</span> debuff when the third **Mirage Dive** happened).

If the *Left Eye* and *Right Eye* aren't dead yet, quickly kill them before the next raid-wide, **Steep in Rage**, or it will heal up the *Right Eye* (or bring it back to life).  
There's only a few seconds left before the Duty Gauge is filled up to kill any remaining *Eye*.
</div>

<h1><a id='Intermission-HaurchefantRewind'>Intermission - Haurchefant Rewind</a></h1>

<div class='guideSection' markdown='1'>

> You jump into the Delorean and get teleported back in time to **Plannar Imprisonment** from Phase 1. Except this time, the Tank LB3 is ready to save *Haurchefant*. If *Haurchefant* still dies, the fight will loop back into Phase 2.

Once you're back to Phase 1, *Sir Charibert* will start to cast **Pure Heart**. Use the same strategy as previously to deal with with mechanic.  
When *Haurchefant* appears and in position between you and *Sir Zephirin* (or at the end of **Spear of the Fury** cast), use the Tank LB3 to protect him and reduce the <span class='speDebuff'>HP Recovery Down</span> debuff potency from 100% to 20%. Constantly heal *Haurchefant* so he ends up above 60/70% when **Pure Heart** cast is over. Since he stays alive, the Healers also have to heal the group from the multiples **Shockwave**.

Once **Pure Heart** is over and if *Haurchefant* is still alive, the *Spear of the Fury* will become targetable and cast **Pierce**, killing *Haurchefant* if the cast is completed. Quickly get rid of it to continue the fight in an alternative timeline.
</div>

<h1><a id='Phase4-KingThordanRefrain'>Phase 4 - King Thordan Refrain</a></h1>

<div class='guideSection' markdown='1'>
<h2><a id='Phase4-KingThordanRefrainAbilitiesBreakdown'>Abilities Breakdown</a></h2>

*King Thordan* auto-attacks are cone cleaves.

___

+ **<u>Incarnation</u>:**
*King Thordan* revives *Darkscale* (dark dragon), *Vedrfolnir* (white wyrm), and *Vidofnir* (white dragon) under his control.

___

+ **<u>The Dragon’s Eye</u>:**
*King Thordan* gains the <span class='buff'>Light of Ascalon</span> buff, boosting his damage.

___

+ **<u>Wrath of the Heavens</u>:**

  + **<u>Chain Lighting</u>:**
  Two random players get a <span class='speDebuff'>Thunderstruck</span> <img class='iconImg' src='{{ site.data.iconList.DSR.Thunderstruck }}'> debuff on lasting 15 seconds. When it resolves, **Chain Lightning**, a small AoE, will be cast on their owner. It will deal high <span class='magic'>magical damage</span>, apply a <span class='debuff'>Paralysis</span> debuff lasting 45 second and a <span class='debuff'>Damage Down</span> debuff to anyone else caught in the AoE.

    ___

  + **<u>Spiral Pierce</u>:**
  2 random players will receive a proximity tether that cannot be transferred from *Ser Ignasse* and *Ser Vellguine* located at *Vedrfolnir* sides.  
  The two Knights will perform a line AoE towards these players dealing <span class='magic'>magical damage</span> and applying a <span class='debuff'>Magic Vulnerability Up</span> debuff lasting 12 seconds. The damage are reduced the further away you are from the Knight.

    ___

  + **<u>Twisting Dive</u>:**
  **Divebomb** in a straight line from *Vedrfolnir* through the middle of the arena, dealing lethal damage and knocking away anyone caught.  
  When he starts his dive animation, every players will get a **Twister**, a small tornados placed under a player. If someone steps on it, it will kill that player and knock back any close player into the wall.

    ___

  + **<u>Ascalon’s Mercy Revealed</u>:**
  Cone from *King Thordan* aimed at every players dealing <span class='phys'>physical damage</span> and applying a <span class='debuff'>Physical Vulnerability Up</span> debuff.

    ___

  + **<u>Liquid Heaven</u>:**
  *Vedrfolnir* will target a random player without a <span class='debuff'>Magic Vulnerability Up</span>. He will attack 5 times, dealing small <span class='magic'>magical damage</span> and each attack will leave a fire puddle lasting 15 seconds. Standing inside a puddle will kill any player.

    ___

  + **<u>Altar Flare</u>:**
  4 ground AoE appearing sequentially under a random player’s feet. Will explode after 2.5 seconds dealing lethal damage.

    ___

  + **<u>Cauterize</u>:**
  **Divebomb** from *Darkscale* and *Vidofnir* on a random player, dealing lethal damage and knocking away anyone caught. The dive direction is locked when the marker is off.

___

+ **<u>Death of the Heavens</u>:**

  + **<u>Deathstorm</u>:**
  4 random players will receive a <span class='speDebuff'>Doom</span> debuff lasting 26 seconds, killing the player when it wears off.  
  This debuff cannot target all Tanks/Healers or all DPS at the same time.

    ___

  + **<u>Spear of the Fury</u>:**
  Line AoE from *Sir Zephirin* that goes though the middle of the arena dealing lethal damage.

    ___

  + **<u>Cauterize & Twisting Dive</u>:**
  Larger **Cauterize** from *Darkscale* and thinner **Twisting Dive** from *Vedrfolnir*. Both attacks don't have a dive marker and go through the middle of the arena.

    ___

  + **<u>Wings of Salvation</u>:**
  *Vidofnir* targets the 4 players without a <span class='speDebuff'>Doom</span> debuff and will place a white puddle on the ground. After 3 seconds, it will explode killing anyone inside and will leave a small cleanse puddle on the ground, used to remove the <span class='speDebuff'>Doom</span> debuff.

    ___

  + **<u>Holy Chain</u>:**
  Works the same way as in Phase 1 except the markers will follow new rules:
    + <span class='speDebuff'>Doom</span> players: two <span style='color: Tomato'>Circles</span>, a <span style='color: MediumPurple'>Square</span> and a <span style='color: MediumSeaGreen'>Triangle</span>.
    + Non-<span class='speDebuff'>Doom</span> players: two <span style='color: dodgerblue'>Crosses</span>, a <span style='color: MediumPurple'>Square</span> and a <span style='color: MediumSeaGreen'>Triangle</span>.

     *<u>The two <span style='color: Tomato'>Circles</span> will always be on the two <span class='speDebuff'>Doom</span> players that are the furthest away from Sir Grinnaux.</u>*

    ___

  + **<u>Holy Meteors</u>:**
  8 *Meteor Circles* will spawn at each cardinals/intercardinals. They must be killed within 15 seconds or the party will be wiped.

___

+ **<u>Aetheric Burst</u>:**
Enrage. It is interrupted when *King Thordan* is down below 3% HP.

</div>

<div class='guideSection' markdown='1'>
<h2><a id='Phase4-KingThordanRefrainStrategy'>Strategy</a></h2>

*King Thordan* starts the fight with **Incarnation** in order to revive the three dragons followed by **The Dragon's Eye**, buffing his damage.  
He'll continue with a few auto-attacks before summoning his Knights and cast **Wrath of the Heavens**.

<a id='SWrathOfTheHeavens'></a>Quickly identify where *Vedrfolnir* is and use him as a landmark for the first part of **Wrath of the Heavens**. The players with the **Spiral Pierce** tethers will move to the edge opposite of the Knight they're tethered with. The player with the **Skyward Leap** marker will move to the right side, not far from the Knight on his side. While the 5 other players will move to the left side, spread along the edge between the Knight and one of the players with **Spiral Pierce**.  
During that time, two random players will receive the <span class='speDebuff'>Thunderstruck</span> debuff for later.  
When *Vedrfolnir* dive animation starts, everyone has to take a few steps towards the middle to bait the **Twisters** along the edge. Never move sideways or you may walk on someone else **Twister**:
{% assign slideCounter = slideCounter | plus: 1 %}
{% include slideshow.html imgLink="wrath1.jpg;wrath2.jpg;wrath3.jpg" imgDesc="Place <em>Vedrfolnir</em> North;<strong>Spiral Pierce</strong> away from their Dragoons, <strong>Skyward Leap</strong> marker to the right and the rest spread to the left;Move towards the middle when the dive animation starts" slideNumber=slideCounter %}

At the same time, *Ser Grinnaux* will spawn at a random cardinal and will be the landmark for the rest of the mechanic.  
The player with **Cauterize** marker have to quickly move to the edge opposite of *Sir Grinnaux* and bait the dives there. Soon after, *King Thordan* will use **Ascalon's Mercy Revealed** from the centre of the arena, have everyone spread to avoid overlapping the cones. **Cauterize** is baited as soon as **Ascalon's Mercy Revealed** is happening.  
Next, a random player will be targeted by **Altar Flare** and another one by **Liquid Heaven**. These player must bait the AoEs/puddles on their way towards *Sir Grinnaux* but must not cover the area around him.  
In the mean time, the party will move under him since he'll be casting **Empty Dimension**. The group will stack inside the AoE between *Sir Grinnaux* and *King Thordan* while the two players with <span class='speDebuff'>Thunderstruck</span> will spread on the other side of *Sir Grinnaux* to avoid hitting anyone else with their **Chain Lightning** when the debuffs resolve:
{% assign slideCounter = slideCounter | plus: 1 %}
{% include slideshow.html imgLink="wrath4.jpg;wrath5.jpg;wrath6.jpg;wrath7.jpg" imgDesc="Place <em>Sir Grinnaux</em> North;Dive marker goes opposite of him, everyone spread around <em>King Thordan</em>;The players with <strong>Altar Flare</strong> and <strong>Liquid Heaven</strong> bait them away from <em>Sir Grinnaux</em>, the rest moves under him;<strong>Thunderstruck</strong> players spread North while the group stack South" slideNumber=slideCounter %}

*King Thordan* is now targetable and will cast **Ancient Quaga**, remember that his damages are buffed so mitigate accordingly. Followed by **Heavenly Heel** into triple **Ascalon's Might**, swap Tanks to cover the busters or have a Tank with his invulnerability.  
He will summon his Knights once again and cast **Death of the Heavens**.

<a id='SDeathOfTheHeavens'></a>*Sir Gerrique* will appear at a random cardinal and his position will be considered as North for the rest of the mechanic.  
Form a line from West to East, then 4 random players will get a <span class='speDebuff'>Doom</span> debuff. Based on the fact that you have or not a <span class='speDebuff'>Doom</span>, take the closest following positions:

+ The outer <span class='speDebuff'>Doom</span> players move West and East along the stone ring.
+ The inner <span class='speDebuff'>Doom</span> players move North West and North East along the edge.
+ The outer players without a debuff move West and East along the edge.
+ The inner players without a debuff players move South West and South East along the edge.

Be mindful, the players at intercardinals must stand on the tiles surrounded in red in order to dodge **Spear of the Fury** and **Twisting Dive**:
<img class='soloImg' src='{{ page.imagePath | append: 'doom.jpg'}}'>

*Darkscale* will cast **Cauterize**, diving in the North/South axis. *Ser Zephirin* and *Vedrfolnir* will respectively cast **Spear of the Fury** and **Twisting Dive**. Their will attack diagonally, NE->SW and NW->SE, but slightly tilted towards the East and West. (*Check diagram n°4 below to see the positions and line AoEs.*)  
When all the **Thunderstorms** resolve and **Twisting Dive** animation starts, everyone has to move to bait the **Twisters**. At the same time, *Vidofnir* will place a **Wings of Salvation** puddle under all the non-doom players, on top of their **Twisters**.  
Dodge the **Heavy Impact** from *Sir Gerrique* while moving towards the centre of the arena:
{% assign slideCounter = slideCounter | plus: 1 %}
{% include slideshow.html imgLink="death1.jpg;death2.jpg;death3.jpg;death4.jpg;death5.jpg" imgDesc="Place <em>Sir Gerrique</em> North and make a line;Move to your positions while <strong>Heavy Impact</strong> starts;THE TING GOES SKRAAA;Immediately move for <strong>Twisters</strong> while dodging <strong>Heavy Impact</strong> donut;Say hello to <em>Sir Grinnaux</em>" slideNumber=slideCounter %}

Everyone will regroup around *Sir Grinnaux* for **Holy Chain**:

1. The <span class='speDebuff'>Doom</span> players that were East and West have to stay a bit away from *Sir Grinnaux* to bait the <span style='color: Tomato'>Circles</span>. The <span class='speDebuff'>Doom</span> players that were at intercardinals will cross through *Sir Grinnaux* and stay there, getting their <span style='color: MediumPurple'>Square</span> and <span style='color: MediumSeaGreen'>Triangle</span> markers.  
2. The non-doom players with the <span style='color: MediumPurple'>Square</span> and the <span style='color: MediumSeaGreen'>Triangle</span> will move opposite of their <span class='speDebuff'>Doom</span> player while the two with the <span style='color: dodgerblue'>Cross</span> markers adjust North and South.

In the meantime, find both *King Thordan* and the *Dragon Eye* locations and look away from both once you're set with your marker.  
After a few seconds, **Faith Unmoving** will happen along with **The Dragon's Gaze** and **The Dragon's Glory**. Every <span class='speDebuff'>Doom</span> players should be knocked back next to a **Wings of Salvation** cleanse puddle to remove their debuff. Stay spread after the knockback until **Heavensflame** AoEs happen:
{% assign slideCounter = slideCounter | plus: 1 %}
{% include slideshow.html imgLink="death6.jpg;death7.jpg;death8.jpg;death9.jpg;death10.jpg" imgDesc="Intercardinals <strong>Doom</strong> players cross through <em>Sir Grinnaux</em> and East/West <strong>Doom</strong> players stay a bit away to bait the Circle markers;Markers appear, <strong>Doom</strong> players are anchored;<strong>Non-Doom</strong> players adjust and both Crosses are North and South;Move close to <em>Sir Grinnaux</em> and look away from <em>King Thordan</em> and the <em>Dragon Eye</em>;Get knocked away and grab the cleanse puddles" slideNumber=slideCounter %}

After the explosion, 8 *Meteor Circles* will spawn, quickly get rid of them to avoid a wipe. It can be useful to keep multi-hit albilities for this part.

It's time for *King Thordan* to come back with his **Ancient Quaga** into **Heavenly Heel** into triple **Ascalon's Might** combo. As previously, mitigate the raid-wide and swap Tanks for the tank busters or use a Tank invulnerability.  
He will then cast his enrage **Aetheric Burst**. The cast will be cancelled if he drops below 3% HP. Stop any kind of damage to spare him and go into Phase 5.  
> If he's killed, the fight will loop to Phase 3 but this time, since *Haurchefant* has been saved, he won't give the <span class='buff'>Soul of Friendship</span> buff allowing you to deal damage to the *Right Eye*.

</div>

<h1><a id='Phase5-Nidhogg&Hraesvelgr'>Phase 5 - Nidhogg & Hraesvelgr</a></h1>

<div class='guideSection' markdown='1'>
<h2><a id='Phase5-Nidhogg&HraesvelgrAbilitiesBreakdown'>Abilities Breakdown</a></h2>

Both *Nidhogg* and *Hraesvelgr* must be killed at the same time. When one dies, the other will start casting the enrage.

___

+ **<u>Vows</u>:**
Players have to uphold *Nidhogg* and *Hraesvelgr* vows. If a vow is broken, the holder of the vow will gain a <span class='buff'>Damage Up</span> and <span class='buff'>Vulnerability Down</span> buffs for the rest of the phase.

  + **Solemn Vow** <img class='iconImg' src='{{ site.data.iconList.DSR.SolemnVow }}'>:
  *“Recognized under the oath Hraesvelgr swore to his beloved Shiva – that he would never kill her kin.”*  
  *Hraesvelgr* will gain the <span class='buff'>Solemn Vow</span> buff. The vow is broken when a player dies from *Hraesvelgr* attacks.

    ___

  + **Mortal Vow** <img class='iconImg' src='{{ site.data.iconList.DSR.MortalVow }}'>:
  *“Condemned by Nidhogg’s vow to avenge his brood-sister. Healing potency is decreased. Taking damage overtime, and will inflict anguish on those nearby in turn when this effect expires.”*  
  A random DPS will receive <span class='magic'>magical damage</span> along with the <span class='speDebuff'>Mortal Vow</span> debuff, a DoT reducing healing potency by 95% and lasting 34 seconds. When the debuff resolves, it deals AoE <span class='magic'>magical damage</span> around the bearer and <span class='speDebuff'>Mortal Vow</span> is transferred to the closest player with its full duration. The vow is broken when <span class='speDebuff'>Mortal Vow</span> isn't transferred to a player.  

    The player who transferred <span class='speDebuff'>Mortal Vow</span> will gain the <span class='speDebuff'>Mortal Atonement</span> <img class='iconImg' src='{{ site.data.iconList.DSR.MortalAtonement }}'> debuff lasting 100 seconds, preventing this player to get <span class='speDebuff'>Mortal Vow</span>.  

    If any more players are present when <span class='speDebuff'>Mortal Vow</span> resolves, they'll get the <span class='speDebuff'>Suppuration</span> <img class='iconImg' src='{{ site.data.iconList.DSR.Suppuration }}'> debuff, reducing their HP by 50% and doubling the damage taken.

___

+ **<u>Swirling Blizzard</u>:**
Donut AoE dealing lethal damage from *Hraesvelgr*. The AoE will mostly cover the corners of the arena forcing the players to be in the middle of it.

___

+ **<u>Great Wyrmsbreath</u>:**
Set of attacks from *Hraesvelgr*:

  + **<u>Ice Breath</u>**:
  3 non-Tank player will get tethered to *Hraesvelgr*. The tether can be stretch to switch the colour from purple to blue, dealing higher damage if the tether is purple.  
  At the end of the cast, *Hraesvelgr* will attack these players with a cone dealing <span class='magic'>magical damage</span>, applying a <span class='debuff'>Ice Resistance Down II</span>, <span class='debuff'>Physical Vulnerability Up</span> and a <span class='speDebuff'>Freezing</span> debuff.  

    <span class='speDebuff'>Freezing</span> <img class='iconImg' src='{{ site.data.iconList.DSR.Freezing }}'> lasts 11 seconds. When it resolves, it becomes <span class='speDebuff'>Deep Freeze</span> <img class='iconImg' src='{{ site.data.iconList.DSR.DeepFreeze }}'> preventing any movements for 30 seconds. <span class='speDebuff'>Freezing</span> can be cleansed if the player receive <span class='speDebuff'>Boiling</span> from *Nidhogg*.

    ___

  + **<u>Staggering Breath / Holy Orb</u>:**
  If *Nidhogg* and *Hraesvelgr* 's mouths are glowing, *Hraesvelgr* will cast an AoE tank buster, **Holy Orb**, on his main target, dealing <span class='magic'>magical damage</span> and applying <span class='speDebuff'>Sustained Light Damage</span>, a strong DoT lasting 2 minutes.  
  <span class='speDebuff'>Sustained Light Damage</span> is cancelled by <span class='speDebuff'>Sustained Dark Damage</span> from **Dark Orb**.

    If only *Nidhogg* 's mouth is glowing, *Hraesvelgr* will cast **Staggering Breath** on his main target, a wide AoE tank buster dealing <span class='magic'>magical damage</span>.

    If only *Hraesvelgr* 's mouth is glowing, he will cast **Holy Breath** in front of him, a cone dealing lethal damage and applying <span class='debuff'>Damage Down</span>.

___

+ **<u>Dread Wyrmsbreath</u>:**
Set of attacks from *Nidhogg*:

  + **<u>Fire Breath</u>**:
  3 non-Tank player will get tethered to *Nidhogg*. The tether can be stretch to switch the colour from purple to red, dealing higher damage if the tether is purple.  
  At the end of the cast, *Nidhogg* will attack these players with a cone dealing <span class='magic'>magical damage</span>, applying a <span class='debuff'>Fire Resistance Down II</span>, <span class='debuff'>Physical Vulnerability Up</span> and a <span class='speDebuff'>Boiling</span> debuff.  

    <span class='speDebuff'>Boiling</span> <img class='iconImg' src='{{ site.data.iconList.DSR.Boiling }}'> lasts 11 seconds. When it resolves, it becomes <span class='speDebuff'>Pyretic</span> <img class='iconImg' src='{{ site.data.iconList.DSR.Pyretic }}'> dealing high damage when any action is performed for 30 seconds. <span class='speDebuff'>Boiling</span> can be cleansed if the player receive <span class='speDebuff'>Freezing</span> from *Hraesvelgr*.

    ___

  + **<u>Staggering Breath / Holy Orb</u>:**
  If *Nidhogg* and *Hraesvelgr* 's mouths are glowing, *Nidhogg* will cast an AoE tank buster, **Dark Orb**, on his main target, dealing <span class='magic'>magical damage</span> and applying <span class='speDebuff'>Sustained Dark Damage</span>, a strong DoT lasting 2 minutes.  
  <span class='speDebuff'>Sustained Dark Damage</span> is cancelled by <span class='speDebuff'>Sustained Light Damage</span> from **Light Orb**.

    If only *Hraesvelgr* 's mouth is glowing, *Nidhogg* will cast **Staggering Breath** on his main target, a wide AoE tank buster dealing <span class='magic'>magical damage</span>.

    If only *Nidhogg* 's mouth is glowing, he will cast **Dark Breath** in front of him, a cone dealing lethal damage and applying <span class='debuff'>Damage Down</span>.

___

+ **<u>Akh Afah</u>:**
Share AoE from both dragons on their respective main target. Deals heavy <span class='magic'>magical damage</span> and applies <span class='debuff'>Magic Vulnerability Up</span> for 1 second.

  If *Nidhogg* and *Hraesvelgr* health difference is higher than 3%, they will tether together. Both **Akh Afah** deal lethal damage if the dragons are tethered when the cast is over.

___

+ **<u>Hallowed Wings</u>:**
One of *Hraesvelgr* ’s wings will glow, cleaving this half side of the arena at the end of the cast, dealing lethal damage.  
He will also perform **Hallowed Plume** at the same time.

___

+ **<u>Hallowed Plume</u>:**
Wide AoE tank buster from *Hraesvelgr* on 2 players, dealing <span class='magic'>magical damage</span>. The players are chosen based on *Hraesvelgr* 's head position:
  + Head down: target the two closest players.
  + Head up: target the two furthest player.

___

+ **<u>Cauterize</u>:**

  + *Nidhogg*:
  He will move to the edge of the arena and dive through half the arena side he's on, dealing high <span class='magic'>magical damage</span> to anyone on his path and very high <span class='magic'>magical damage</span> to the first player hit.  
  Also apply a <span class='speDebuff'>Burns</span> debuff lasting 27 seconds. If a player with <span class='speDebuff'>Deep Freeze</span> is hit, both debuffs will be removed.

  + *Hraesvelgr*:
  He will move to the edge of the arena and dive through half the arena side he's on, dealing high <span class='magic'>magical damage</span> to anyone on his path and very high <span class='magic'>magical damage</span> to the first player hit.  
  Also apply a <span class='speDebuff'>Frostbite</span> debuff lasting 27 seconds. If a player with <span class='speDebuff'>Pyretic</span> is hit, both debuffs will be removed.

___

+ **<u>Wroth Flames</u>:**
3 sets of orbs will appear sequentially, middle then at one intercardinal and finally at the opposite intercardinal. Each set will explode (named **Fire Blast**) in a wide cross shaped AoE (along the cardinals) in the same order as they appeared, dealing high <span class='magic'>magical damage</span> and applying a <span class='debuff'>Damage Down</span> debuff.

  *Nidhogg* will also apply debuffs to 6 players:
  + **<u>Entangled Flames</u> <img class='iconImg' src='{{ site.data.iconList.DSR.EntangledFlames }}'>:**
  On 2 random players lasting 23 seconds. When it resolves or when the owner dies, it will explode in AoE dealing fire <span class='magic'>magical damage</span> and applying a <span class='debuff'>Fire Resistance Down II</span>. Only 2 players must get hit otherwise anyone caught in the explosion will die.

  + **<u>Spreading Flames</u> <img class='iconImg' src='{{ site.data.iconList.DSR.SpreadingFlames }}'>:**
  On 4 random players lasting 23 seconds. When it resolves or when the owner dies, it will explode in AoE killing anyone caught other than the owner.

___

+ **<u>Akh Morn</u>:**
4 hits share from *Nidhogg* on a random player, dealing <span class='magic'>magical damage</span>. Each hit leaves a puddle on the ground that gives a strong <span class='debuff'>Bleeding</span> to anyone who stands inside.

___

+ **<u>Hot Tail</u>:**
Line AoE from *Nidhogg* dealing lethal damage that goes through the middle of the arena.

___

+ **<u>Hot Wing</u>:**
2 line AoEs from *Nidhogg* sides dealing lethal damage. Cover the whole arena except for a thin line in front of him.

___

+ **<u>Touchdown</u>:**
*Nidhogg* and *Hraesvelgr* will jump back into the arena, dealing raid-wide distance based <span class='phys'>physical damage</span>.

___

+ **<u>Revenge of the Horde</u>:**
*Nidhogg* and *Hraesvelgr* enrages. The cast last 25 seconds.

</div>

<div class='guideSection' markdown='1'>
<h2><a id='Phase5-Nidhogg&HraesvelgrStrategy'>Strategy</a></h2>

> Since *Nidhogg* and *Hraesvelgr* perform a HP check twice, have to be killed at the same time and one of them may leave the arena from time to time, try to keep them at the same level of health as much as possible. At least until the last **Akh Afah**.

As soon as *Nidhogg* and *Hraesvelgr* arrive, each Tank has to grab a dragon's aggro. In the meantime, Healers and DPS will form a line from the middle towards the South in this order: Melees, Ranged, Healers.

When **Dread Wyrmsbreath** and **Great Wyrmsbreath** casts start, the DPS and Healers will get a tethers and have to form a pair composed of one Ice and one Fire tether in order to cancel their debuffs. They'll have to position themselves so each pair only get hit once per element. Use the line you made before to have pre-assigned positions.  
Meanwhile, the Tanks has to check the dragons' mouths:

+ Both are glowing: the Tanks stack together middle.
+ Only one is glowing: the dragon who glows will perform **Dark/Holy Breath** and the other one will use **Staggering Breath** on his target.

Example with only *Nidhogg* 's mouth glowing:
{% assign slideCounter = slideCounter | plus: 1 %}
{% include slideshow.html imgLink="wyrmbreath1-1.jpg;wyrmbreath1-2.jpg" imgDesc="Tanks check the dragons' mouths, DPS/Healers South and form an Ice/Fire pair;Tanks spread and avoid the breath" slideNumber=slideCounter %}

Right after, the DPS have to spread to avoid clipping other people when one of them receives <span class='speDebuff'>Mortal Vow</span>. The order to pass the debuff is the following:  
  DPS > Nidhogg Tank > Hraesvelgr Tank > Melee DPS 1 (or 2) > Phys Ranged DPS (if the Melee DPS 1 got the debuff first, Melee DPS 2 will replace him for the third pass)

Next is **Akh Afah**, split into light party and keep the bosses HP difference within 3%. It deals high damage so mitigate properly.

*Hraesvelgr* will then cast **Hallowed Wings** cleaving the North or South side of the arena. *Nidhogg* will leave the arena to appear North/South and cleave the East or West half with **Cauterize**.  
Identify and move into the safe quadrant, then check *Hraesvelgr* head for **Hallowed Plume**:

+ Head is up: Tanks behind and group in front.
+ Head is down: Tanks in front and group behind.

*Nidhogg* 's Tank will always be leftmost while *Hraesvelgr* 's Tank will be rightmost.

> Consider *Hraesvelgr* as North to have easier callouts.

{% assign slideCounter = slideCounter | plus: 1 %}
{% include slideshow.html imgLink="halloFrontDown.jpg;halloFrontUp.jpg;halloRearDown.jpg;halloRearUp.jpg" imgDesc="<strong>Cauterize</strong> on front row with <em>Hraesvelgr</em> head down;<strong>Cauterize</strong> on front row with <em>Hraesvelgr</em> head up;<strong>Cauterize</strong> on back row with <em>Hraesvelgr</em> head down;<strong>Cauterize</strong> on back row with <em>Hraesvelgr</em> head up" slideNumber=slideCounter %}

Quickly make some space middle so the DPS with <span class='speDebuff'>Mortal Vow</span> can pass it to *Nidhogg* 's Tank there.

Now, *Nidhogg* will cast **Wroth Flames** and *Hraesvelgr* will leave the arena for **Cauterize**. At the same time, 4 players will receive <span class='speDebuff'>Spreading Flames</span> and 2 other will get <span class='speDebuff'>Spreading Flames</span>. Futhermore, 3 sets of orbs will spawn with the first one middle and the two other on opposite intercardinal.  
First, find *Hraesvelgr* and where he'll dive through. If he dives mid or away from *Nidhogg* side, you can move all grouped together, next to him, to the intercardinal corner opposite of the second set of orbs, either diagonally or vertically. Otherwise, move away from *Nidhogg* but still to the intercardinal corner opposite of the second set.  
Then **Cauterize** and the first hit of **Akh Morn** will happen, start to move toward the middle on the arena while running along *Nidhogg* 's hitbox.  
The first **Fire Blast** happens along with the second hit of **Akh Morn**. Continue to drop the puddles next to the previous one's edge. Right after the fourth **Akh Morn** is done, the second **Fire Blast** will resolve.  
Move middle to avoid the third and final **Fire Blast**.

Example with *Hraesvelgr* diving middle:
{% assign slideCounter = slideCounter | plus: 1 %}
{% include slideshow.html imgLink="wroth1.jpg;wroth2.jpg;wroth3.jpg;wroth4.jpg;wroth5.jpg" imgDesc="Move to the corner vertically opposite of the second set;<strong>Cauterize</strong> and <strong>Akh Morn</strong> first hit happen;Start to move for the second <strong>Akh Morn</strong> along with the first <strong>Fire Blast</strong>;Keep running along the hitbox during the third and fourth <strong>Akh Morn</strong>;Move middle to avoid the last <strong>Fire Blast</strong>" slideNumber=slideCounter %}

Example with *Hraesvelgr* diving on *Nidhogg* 's side:
{% assign slideCounter = slideCounter | plus: 1 %}
{% include slideshow.html imgLink="wrothBis1.jpg;wrothBis2.jpg;wrothBis3.jpg;wrothBis4.jpg;wrothBis5.jpg" imgDesc="Move to the corner diagonally opposite of the second set;<strong>Cauterize</strong> and <strong>Akh Morn</strong> first hit happen;Start to move for the second <strong>Akh Morn</strong> along with the first <strong>Fire Blast</strong>;Keep running along the hitbox during the third and fourth <strong>Akh Morn</strong>;Move middle to avoid the last <strong>Fire Blast</strong>" slideNumber=slideCounter %}

While you're moving middle to dodge the last **Fire Blast**, check *Nidhogg* to see if he's casting **Hot Tail** or **Hot Wing**. For the former, don't stop and keep running in the same direction.  
Then the <span class='speDebuff'>Spreading Flames</span> players will spread on *Nidhogg* side while the <span class='speDebuff'>Entangled Flames</span> players will spread on *Hraesvelgr* side. Each player without a debuff will stack with a <span class='speDebuff'>Entangled Flames</span> player:

{% assign slideCounter = slideCounter | plus: 1 %}
{% include slideshow.html imgLink="hotTail.jpg;hotWing.jpg" imgDesc="Spread on the side;Spread middle" slideNumber=slideCounter %}

It's time for the second <span class='speDebuff'>Mortal Vow</span> pass where *Nidhogg* 's Tank gives it to *Hraesvelgr* 's Tank.

A new **Akh Afah** will be casted, do the same as previously. This is the last **Akh Afah** of the fight so there is no need to worry about their HP difference afterward.

Then *Hraesvelgr* will cast **Hallowed Wings** and *Nidhogg* will cast **Hot Tail / Hot Wing**. Same as before, watch out for the side *Hraesvelgr* is cleaving then move to the safe side if **Hot Tail** or move in the middle between the bosses if **Hot Wing**. Both Tanks will adjust based on *Hraesvelgr* head position while being as close as possible to their respective dragon.

> Take care about **Hot Tail** since **Hallowed Wings** cleave will cut the safe spot in two. Check the diagrams below for an example.

{% assign slideCounter = slideCounter | plus: 1 %}
{% include slideshow.html imgLink="halloWingDown.jpg;halloWingUp.jpg;halloTailDown.jpg;halloTailUp.jpg" imgDesc="<strong>Hot Wing</strong> with <em>Hraesvelgr</em> head down;<strong>Hot Wing</strong> with <em>Hraesvelgr</em> head up;<strong>Hot Tail</strong> with <em>Hraesvelgr</em> head down;<strong>Hot Tail</strong> with <em>Hraesvelgr</em> head up" slideNumber=slideCounter %}

Once again, quickly clear a spot so the *Hraesvelgr* 's Tank can pass <span class='speDebuff'>Mortal Vow</span> to the Melee DPS. Always pass it to the same Melee DPS except if he got the debuff first, then pass it to the second Melee DPS.

The second set of **Dread Wyrmsbreath** and **Great Wyrmsbreath** will happen. The Tanks will either stack mid if both dragon mouths are glowing or they'll move to their respective bosses to avoid the **Dark/Holy Breath**, **Ice/Fire Breaths** and take **Staggering Breath** alone.  
This time the Healers and DPS need to keep their debuffs on, so they will take their **Ice/Fire Breath** alone at fixed position. Based on your position and the tether you get, it may stay purple but will only deal slightly more damage. Check the next diagrams to see the positions:

Example with only *Hraesvelgr* 's mouth glowing:
{% assign slideCounter = slideCounter | plus: 1 %}
{% include slideshow.html imgLink="wyrmbreath2-1.jpg;wyrmbreath2-2.jpg" imgDesc="Tanks check the dragons' mouths, everyone moves their fixed positions;Tanks spread and avoid the breath" slideNumber=slideCounter %}

Here is more information about the positions if you're on:

+ Green: North and South along the **Swirling Blizzard**.
+ Purple: In the corner formed by **Swirling Blizzard** and the line of stones shown in orange.
+ White: Use the bleached stones shown by the white arrows as a cue.
+ Yellow: In the corner formed by **Swirling Blizzard** and the boss inner-hitbox.
<img class='soloImg' src='{{ page.imagePath | append: 'wyrmbreath2pos.jpg' }}'>

After everything resolve, both wryms will leave and reappear North for **Cauterize**. Players with <span class='speDebuff'>Boiling</span> will move on *Hraesvelgr* side while the players with <span class='speDebuff'>Freezing</span> will move on *Nidhogg* side. The Tanks will move in front of the group and their respective bosses and use their invulnerability. They can also use the rest of their mitigation tools (that can carry over from the previous tank buster) and keep their invulnerability for the last phase.  
Right before **Cauterize** happens, the debuffs will swap into <span class='speDebuff'>Pyretic</span> and <span class='speDebuff'>Deep Freeze</span> and will be removed if the players are on the correct side. If you end up with <span class='speDebuff'>Pyretic</span>, remember to not perform any action to avoid unnecessary damage.
<img class='soloImg' src='{{ page.imagePath | append: 'cauterize.jpg' }}'>

After **Cauterize**, stack on the cardinal where it happened. *Nidhogg* and *Hraesvelgr* will come back with **Touchdown** and its proximity damage, *Nidhogg* will jump mid while *Hraesvelgr* will jump on the opposite side where **Cauterize** happened.

Right after **Touchdown**, *Hraesvelgr* 's Tank will give his <span class='speDebuff'>Mortal Vow</span> to the Physical Ranged DPS.

Finally, *Nidhogg* and *Hraesvelgr* will start their enrage, **Revenge of the Horde** and you have 25 seconds to kill them.

</div>

<h1><a id='Phase6-Dragon-kingThordan'>Phase 6 - Dragon-king Thordan</a></h1>

<div class='guideSection' markdown='1'>
<h2><a id='Phase6-Dragon-kingThordanAbilitiesBreakdown'>Abilities Breakdown</a></h2>

During this phase, *Dragon-king Thordan* abilities **Exaflare’s Edge**, **Akh Morn’s Edge** and **Gigaflare’s Edge** will spawn AoEs or towers based on where he's facing. One behind him and two on his 2 and 10 o'clock thus forming an equilateral triangle.

___

+ **<u>Shockwave</u>:**
Raid-wide AoE dealing <span class='magic'>magical damage</span> and applying a <span class='debuff'>Bleeding</span> debuff lasting 9 seconds.

___

+ **<u>Alternative End</u>:**
Raid-wide AoE dealing massive <span class='magic'>magical damage</span> (110k to 120k unmitigated).

___

+ **<u>Trinity</u>:**
During this phase, *Dragon-king Thordan* will perform 2 AoE auto-attacks on 3 different target before every mechanic:
  + Highest enmity player: dealt dark <span class='magic'>magical damage</span> and receive a stackable <span class='debuff'>Dark Resistance Down</span> debuff lasting 37 seconds.
  + 2nd highest enmity player: dealt light <span class='magic'>magical damage</span> and receive a stackable <span class='debuff'>Light Resistance Down</span> debuff lasting 37 seconds.
  + Closest player: dealt light <u>and</u> dark <span class='phys'>physical damage</span> and receive a <span class='debuff'>Dark Resistance Down</span>, <span class='debuff'>Light Resistance Down</span> and a <span class='debuff'>Physical Vulnerability Up</span> debuffs lasting 60 seconds for the last one.

  Due to stacked debuff, Tanks has to swap when they reach 2 stacks of <span class='debuff'>Dark Resistance Down</span> <img class='iconImg' src='{{ site.data.iconList.DSR.DarkResistanceDown }}'> or <span class='debuff'>Light Resistance Down</span> <img class='iconImg' src='{{ site.data.iconList.DSR.LightResistanceDown }}'>.

___

+ **<u>Fire's Edge / Ice's Edge</u>:**
During any other **Edge** abilities, *Dragon-king Thordan* will imbue his sword with an element. He will release it at the beginning of that **Edge** ability:
  + <span style='color:firebrick'>Fire</span>: he'll perform a pointblank AoE.
  + <span style='color: dodgerblue'>Ice</span>: he'll perform a donut AoE.

> The limit between the pointblank and the donut AoE is the boss hitbox.

___

+ **<u>Exaflare’s Edge</u>:**
3 sets of **Exaflare** AoEs will appear on *Dragon-king Thordan* hitbox dealing lethal damage. Each **Exaflare** will spread in 3 directions in a T shape.

___

+ **<u>Akh Morn’s Edge</u>:**
3 towers will spawn on *Dragon-king Thordan* hitbox. Each tower will hit 5 times plus 1 time for each subsequent cast:
  + 2 towers need to be soaked by 3 players, dealing <span class='magic'>magical damage</span>. They spawn at 2 and 10 o'clock.
  + 1 towers need to be soaked by 2 players, dealing high <span class='magic'>magical damage</span>. It spawns behind the boss.

> When a tower spawn, there will be a similar effect to the old **Blood of the Dragon** animation. The 3 people towers will have red dragons along with red diamond markers, while the 2 people tower will have blue dragons and blue diamond markers.  
> However, please note that the number of people needed for a tower only shows the damage output. A Tank can perfectly use his invulnerability to solo soak any tower, nothing will happen.

___

+ **<u>Gigaflare’s Edge</u>:**
3 proximity AoEs will spawn sequentially, halfway between *Dragon-king Thordan* and the edge. They will explode in the same order and deal high <span class='magic'>magical damage</span>.

___

+ **<u>Morn Afah’s Edge</u>:**
*Dragon-king Thordan* soft enrage. 3 towers will appear on his hitbox. Each tower has to be soaked by one player, killing him in the process. Any non-soaked tower will wipe the group.  
*Dragon-king Thordan* will repeat this as soon as the previous towers explode, ultimately wiping the group.

    "Ultimately".. do you get it? (◞థ౪థ)ᴖ

</div>

<div class='guideSection' markdown='1'>
<h2><a id='Phase6-Dragon-kingThordanStrategy'>Strategy</a></h2>

During the transition, *Estinien* will perform a **Resentment** follow by a **Shockwave**. Be sure to heal the <span class='debuff'>Bleeding</span> damage.  
Then *Dragon-king Thordan* will perform **Alternative End**. Requiring a lot of mitigation.

When *Dragon-king Thordan* become targetable, one Tank has to quickly grab the aggro and keep him turned South since he will immediately cast **Exaflare's Edge**.  
Move to the sides of the **Exaflare** that is behind him. Check his blades to see if he's using **Fire's Edge** or **Ice's Edge** and move outside or inside his hitbox.  
After the first explosion, move inside it. Once the second explosion happen, move towards the edge and stop between the two black diamond shapes on the ground to dodge the third **Exaflare** and the next ones.  
Example with **Fire's Edge**:
{% assign slideCounter = slideCounter | plus: 1 %}
{% include slideshow.html imgLink="exa1.jpg;exa2.jpg;exa3.jpg" imgDesc="Stay out and next to the <strong>Exaflare</strong> that is behind the boss;Move inside the first <strong>Exaflare</strong> explosion;Move towards the edge and stop between the two diamond shapes" slideNumber=slideCounter %}

> This method works for any pattern of **Exaflares**.

Then *Dragon-king Thordan* will use his triple auto-attacks, **Trinity**. Be sure that Tanks hold the first 2 spots in the enmity list with a margin between them. Everyone will move out of the boss hitbox except the player who has to take the third auto-attack. Once a player has been hit he'll move out and the second player will replace him. Melee DPS will always take the 2 auto-attacks after **Exaflare's Edge**.  
Once the two auto-attacks are done, the Tanks will swap.

Next is **Akh Morn’s Edge**, hitting 5 times. Check *Dragon-king Thordan* for **Fire's Edge** or **Ice's Edge** and move into your tower. Tanks in the tower behind the boss for 2 players. The rest of light parties into 3 players towers. Remember to stand in or outside the boss hitbox before the first hit, then you can move a bit middle to catch the heals.  
> An alternative way to do it is to have one Tank in a tower with his invulnerability, the second Tank in another tower with all his mitigation on and the rest of the group in the last tower.

**Trinity** is making a come back, this time the third auto-attacks will be taken by the Ranged DPS.

Now is **Gigaflare’s Edge**, move to the opposite side from where the first AoE appeared. Stand either in or out for **Fire's Edge** or **Ice's Edge**. Then,  either run clockwise or counter-clockwise while being at max melee range to reduce the **Gigaflares** damage.

Once again, **Trinity** is back taken care of by the Healers.

From now on this cycle will repeat:

1. **Exaflare’s Edge** into **Trinity** with Melee DPS.
2. **Akh Morn’s Edge** with 6 hits into **Trinity** with Ranged DPS.
3. **Gigaflare’s Edge** into **Trinity** with Healers.
4. **Exaflare’s Edge** into **Trinity** with Melee DPS.
5. **Akh Morn’s Edge** with 7 hits into **Trinity** with Ranged DPS.

After two auto-attacks, *Dragon-king Thordan* will cast his enrage, **Morn Afah’s Edge**. Move into your assigned towers and quickly move in when a set is done:

+ First set of towers: 2 Healers in 2 and 10 o'clock towers, 1 Tank in the one behind.
+ Second set of towers: 2 Ranged DPS in 2 and 10 o'clock towers, 1 Tank in the one behind.

You may adjust people order based on DPS capabilities.

</div>
