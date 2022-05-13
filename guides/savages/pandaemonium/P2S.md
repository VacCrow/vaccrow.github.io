---
layout: guides
title: Asphodelos - The Second Circle (Savage) | P2S
imagePath: /assets/img/guides/savages/pandaemonium/P2S/
slideNumber: 5
---

*Patch: 6.05  
Minimum ilvl: i575  
DPS Requirement: 41.9k  
Enrage timer: 10:28  
Loot:*
+ *Chest n°1: Asphodelos Head/Hand/Foot coffer + Discal Tomestone (Weapon Token)*
+ *Chest n°2: Asphodelos Head/Hand/Foot coffer + Radiant Coating  (Accesory Upgrade)*
+ *Token: Book of Asphodelos Mythos II (6 tokens for Asphodelos Head/Hand/Foot or 4 tokens for Accessory upgrade)*

___

<h1><a id="AbilitiesBreakdown">Abilities Breakdown</a></h1>

<div class="guideSection" markdown="1">
<h2><a id="ABGeneralAbilities">General Abilities</a></h2>

+ **<ins>Murky Depths</ins>:**
Raid-wide AoE dealing <span class="magic">magical damage</span>.

___

+ **<ins>Doubled Impact</ins>:**
Shared tank buster on the main target dealing <span class="magic">magical damage</span>.

___

+ **<ins>Sewage Deluge</ins>:**
*Hippokampos* will perform a aaid-wide AoE dealing major <span class="magic">magical damage</span> and flood the arena leaving only the drains and platforms dry. One random plaform will be flooded and kill any player who walks on it. Standing into the water elsewhere will give a <span class="speDebuff">Dropsy</span> debuff, dealing <span class="magic">magical damage</span> overtime.

___

+ **<ins>Spoken/Winged Cataract</ins>:**
*Hippokampos* head and body will split and face different cardinal direction. The body will perform a line AoE through the arena. While the head will perform a 180° frontal cleave if he casts **Spoken Cataract** or a 180° backward cleave if casts **Winged Cataract**.  
Both attacks deal <span class="magic">magical damage</span> and apply a <span class="debuff">vunl / Damage Down</span> debuff.

___

+ **<ins>Coherence</ins>:**
*Hippokampos* will tether a random player that can be grabed. When the cast is over, the head will attack the tethered player and dealing proxymity based raid-wide <span class="magic">magical damage</span>.  
Then the head will do a share line AoE on a random player, except the player who got the tether, dealing <span class="magic">magical damage</span>. The first player hit will recieve extra damage requiering a Tank.

___

+ **<ins>Ominous Bubbling</ins>:**
Both Healers will recieve a stack after a short delay, dealing water <span class="magic">magical damage</span> and applying a <span class="debuff">Water Resistance Down II</span> debuff.

___


+ **<ins>Shockwave</ins>:**
*Hippokampos* will turn toward a random platform and jump there. The impact will knockback everyone away from the centre of the platform and deal <span class="magic">magical damage</span>.

___

+ **<ins>Predatory Avarice</ins>:**
*Hyppokampos* applies a <span class="speDebuff">Mark of the Tides</span> debuff on a random Tank and DPS and a <span class="speDebuff">Mark of the Depths</span> debuff on a random Healer, both debuffs lasting 23 seconds:  
	+ <span class="speDebuff">Mark of the Tides</span>: cast **Deadly Current**, an AoE around the player that knockback everyone else hit into the wall.  
	+ <span class="speDebuff">Mark of the Depths</span>: cast **Hard Water**, a shared AoE dealing <span class="magic">magical damage</span>.

___

+ **<ins>Channeling Flow</ins>:**
Every player will recieve a <span class="speDebuff">Left/Right/Fore/Rear Mark of the Tides</span> debuff lasting 13. Every player will have an arrow next to him pointing in a cardinal direction, based on the name of the debuff. One Tank, one Healer and two DPS will always have different direction.  
When it resolves, the player will be stunned. Then he will be pushed all the way to wall except if he collides with another player going on the opposite direction, dealing water <span class="magic">magical damage</span> and applying a <span class="debuff">Water Resistance Down II</span> debuff. However, if the distance beetween these is too small before they collide, it will deal lethal damage.

___

+ **<ins>Channeling Overflow</ins>:**
Every player will recieve <span class="speDebuff">Left/Right/Fore/Rear Mark of the Tides</span> debuff. One Tank, one Healer and two DPS will have different direction and a 13 seconds long debuff while the debuff for the other 4 will last 28 seconds.

___

+ **<ins>Tainted Flood</ins>:**
AoE on a random Tank, Healer and 2 DPS, dealing water <span class="magic">magical damage</span> and applying a <span class="debuff">Water Resistance Down II</span> debuff.  
Will be on every player if the arena isn't flooded.

___

+ **<ins>Kampeos Harma</ins>:**
Every player will be marked with purple triangles or blue squares, number from 1 to 4 each.  
When the cast is over, *Hipokampos*' head will jump on players with purple triangles following the numbers order, dealing AoE <span class="phys">physical damage</span> and applying <span class="debuff">Physical Vulnerabilty Up</span>. Meanwhile its body will dash to the blue square players in order, dealing <span class="phys">physical damage</span> in a line AoE and and applying <span class="debuff">Physical Vulnerabilty Up</span>.

___

+ **<ins>Dissociation</ins>:**
*Hippokampos* will detach its head. The head wil appear along the (North?) edge and will dive half the arena, dealing <span class="phys">physical damage</span> and do some other shit I don't know man.

___

+ **<ins>Sewage Eruption</ins>:**
Chasing AoE on 4 players, 3 AoEs in a row. Deals <span class="magic">magical damage</span>.

</div>
___
<h1><a id="Strategy">Strategy</a></h1>

<div class="guideSection" markdown="1">
<a id="SPhase1"></a>

*Hippokampos* starts will **Murky Depths**. Soon followed by **Doubled Impact** where your main Tank can use his invulnerabilty to save cooldowns.

Afterward is **Sewage Deluge**, remember to mitigate since it deals massive damage. When the arena is flooded, try to stay on the plaform opposite of the flooded one so you can reach any part of the arena quickly.

*Hippokampos* will then use **Spoken Cataract** or **Winged Cataract** at random. Move to its body side then behind its head for **Spoken Cataract** or in front of its head for **Winged Cataract**.  
Exemple bellow with the head facing North the body facing South:

{% assign slideCounter = 0 %}
{% include slideshow.html imgLink="spoken.jpg;winged.jpg" imgDesc="<strong>Spoken Catarct</strong>, body AoE in orange and head AoE in red;<strong>Winged Catarct</strong>, body AoE in orange and head AoE in red" slideNumber=slideCounter %}

The group should stand where they end up and at max melee range for the incoming **Coherence**. Have a Tank grab the tether and move away from the group. Afterward the rest of the group has to be stack in a line with a Tank forefront to soak the line share:
<img class="soloImg" src="{{ page.imagePath | append: "coherence.jpg" }}">

Heal everyone and get ready for **Murky Depths**.

Next is **Ominous Bubbling** followed by **Shockwave**. Identify when *Hippokampos* is jumping then split into two groups, to the left and right of the boss destination. Use your knockback immunity to stand still (and possibly avoid to get pushed into the flooded platform) and share with your respective group:
<img class="soloImg" src="{{ page.imagePath | append: "bubbling.jpg" }}">

*Hippockampos* will then cast **Predatory Avarice**, check if you get a debuff and get ready for the incoming **Winged Cataract** or **Spoken Cataract**. Move to the safe spot and once the **Cataract** is done, the group will stay in place while the Tank with <span class="speDebuff">Mark of the Tides</span> will move to the left and the DPS to the right:
{% assign slideCounter = slideCounter | plus: 1 %}
{% include slideshow.html imgLink="predAva1.jpg;predAva2.jpg" imgDesc="<strong>Winged Catarct</strong> here, move to the safe spot;<em>Mark of the Tides</em> Tank to the left and DPS to the right" slideNumber=slideCounter %}

The water will be drained and the boss will cast **Channeling Flow**. Everyone will spread around the boss with their arrow facing the boss. Adjust your position to have another player in your path and be sure to be behind the drain (while facing the boss) when the debuff resolves to ensure that you're far enough from each other:
<img class="soloImg" src="{{ page.imagePath | append: "chanFlow.jpg" }}">

Swap tank for the incoming **Doubled Impact** and use the other Tank invulnarability. Have everyone ready for **Murky Depths** and prepare mitigation for **Sewage Deluge**.


</div>
<div class="guideSection" markdown="1">
<a id="SPhase2"></a>

*Hippokampos* will immediatly use **Shockwave**, take care to not get pushed into the flooded platform.

Next, he will mark everyone while casting **Kampeos Harma** and become untargetable:  
+ Every purple triangle players spread on the middle of the drain around the arena. One player per drain. You can also spread by following the numbers order for more style point.  
+ The blue square players will split into two groups, numbers 2 & 4 will move to the plaform where the boss is while numbers 1 & 3 will move to the plaftorm opposite of the boss, as muc has possible in the corner.  
The players 1 & 2 must be in front while the players 3 & 4 must stand behind their partner. Once the body dashes on number 1 or 2, they will swap their poosition with their partner.
{% assign slideCounter = slideCounter | plus: 1 %}
{% include slideshow.html imgLink="kampos1.jpg;kampos2.jpg;kampos3.jpg;kampos4.jpg" imgDesc="First dash;Second dash, 1 & 3 swap;Third dash, 2 & 4 swap;Fourth dash" slideNumber=slideCounter %}

If you had any 2 minutes raid buff, wait for **Kampos Harma** to be done and use them when the boss is once again targetable. The Tanks have to stack together for **Doubled Impact** and the group needs to be topped for the following **Murky Depths**.

Next is **Channeling Overflow**. The players with a short duration <span class="speDebuff">Mark of the Tides</span> (13 seconds) has to stand on the edge of the platforms to slide horizontally/vertically while avoiding the flooded platform to fullfill the debuff conditions. Meanwhile the other players will recieve **Tainted Flood** AoEs and has to stand out of other paths, on drains or away from other .  
Once the first set of <span class="speDebuff">Mark of the Tides</span> are done, quickly regroup to get healed and do the same thing but with reversed group:
{% assign slideCounter = slideCounter | plus: 1 %}
{% include slideshow.html imgLink="overflow1.jpg;overflow2.jpg" imgDesc="First set of debuffs;Second set of debuffs" slideNumber=slideCounter %}

The water will once again recede.

*Hippokampos* will use **Predatory Avarice** combined with **Dissociation** and **Spoken/Winged Cataract**. Watch when the head is to identify the half arena that is safe, then into the safe corner left by **Cataract**. The group have to stand close to the boss to share while the Tank and the DPS with <span class="speDebuff">Mark of the Tides</span> will move behind to the left and right respectively:
<img class="soloImg" src="{{ page.imagePath | append: "dissociation.jpg" }}">

Then *Hippokampos* will use **Sewage Eruption** combined with **Dissociation**. Once again, identify where the head is and regroup North at the edge of the Head path. Bait **Sewage Eruption** puddles as a group toward the safe side, then spread out for **Tainted Flood**. Immediatly after, have a Tank grab the tether and move North while the group will stack South for **Coherence**.

Swap Tank and use his invulnerability for **Doubled Impact** (if available, else Tanks stack together).

Heal and migitigate for the incoming **Murky Depths** and **Sewage Deluge**.
</div>
<div class="guideSection" markdown="1">
<a id="SPhase3"></a>

*Hippokampos* will open with a tight mechanic, **Channeling Overflow** with **Coherence**. The players with a short duration <span class="speDebuff">Mark of the Tides</span> will take the same position has before. The tank with a long duration debuff will grab the tether and move next to the flooded platform while the other will stack on the corner of the opposite platform.  
Once the first set of <span class="speDebuff">Mark of the Tides</span> resolves, quickly heal these players and have everyone stack with a Tank forefront for the line share.  
When it's done, heal everyone and take positions to solve the remaining <span class="speDebuff">Mark of the Tides</span> debuffs.
{% assign slideCounter = slideCounter | plus: 1 %}
{% include slideshow.html imgLink="overflowCo1.jpg;overflowCo2.jpg;overflowCo3.jpg" imgDesc="First set of debuffs, available Tank grab the tether;Heal and stack;Second set of debuffs" slideNumber=slideCounter %}

Afterward, **Dissociation** will be used with **Sewage Eruption**. Resolve as previously.

*Hippokampos* will use the combo **Ominous Bubbling** and **Shockwave** that can be solved the same way as earlier.

Swap tank to use the remaining invulnerability for **Doubled Impact** or have the Tanks stack.

Finally *Hippokampos* will use **Murky Depths** twice before casting the enrage, **Sewage Deluge**.
</div>
