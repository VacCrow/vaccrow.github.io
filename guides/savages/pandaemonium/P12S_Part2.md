---
layout: guides
title: Anabaseios - The Twelfth Circle (Savage) | P12S (Part 2)
imagePath: /assets/img/guides/savages/pandaemonium/P12S_Part2/
slideNumber: 10
---

  {% comment %}
      <!-- cSpell:ignore verti hori calo -->
  {% endcomment %}

*Patch: 6.4  
Minimum ilvl: i640  
DPS Requirement: 76.4k  
Enrage timer: 8:43  
<span class='debuff'>Damage Down</span> potency: 42%  
Loot:*

+ *Chest n°1: Anabaseios Weapon*
+ *Chest n°2: Anabaseios Chest/Weapon coffer + Megaloambystoma Horn*
+ *Token: Book of Anabaseios Mythos IV (8 tokens for Anabaseios Chest or Weapon)*

___

<h1><a id='AbilitiesBreakdown'>Abilities Breakdown</a></h1>

<div class='guideSection' markdown='1'>
<h2><a id='ABGeneralAbilities'>General Abilities</a></h2>

+ **<u>Ultima</u>:**
Raid-wide AoE dealing <span class='magic'>magical damage</span>.

___

+ **<u>Palladian Grasp</u>:**
Two hits cleave tank buster dealing <span class='phys'>physical damage</span>, applying a <span class='debuff'>Physical Vulnerability Up</span> debuff for 4 seconds. *Pallas Athena* will cleave the half side of the arena (East/West) where the main target is standing.  
Target for the first attack is set when the cast begins, target for the second attack is set when the cast is over.

___

+ **<u>Crush Helm</u>:**
Five hits tank buster on the top 2 enmity list, dealing <span class='phys'>physical damage</span> and applying a <span class='debuff'>Physical Vulnerability Up</span> stack debuff on each hit that can be dispelled. <u>The last hit deals very high damage</u>.

___

+ **<u>Ignorabimus</u>:**
Enrage.

</div>

<div class='guideSection' markdown='1'>
<h2><a id='ABGaiaochos'>Gaiaochos</a></h2>

+ **<u>Gaiaochos</u>:**
Raid-wide AoE dealing <span class='magic'>magical damage</span>. *Pallas Athena* will also perform a donut AoE that will destroy a part of the arena leaving only a small circle until the next **Ultima** is casted.  
Everyone will receive the <span class='speDebuff'>Ascended</span> debuff <img class='iconImg' src='{{ site.data.iconList.P12S.Ascended }}'>, shrinking everyone size and reducing movement speed. Removed when the next **Ultima** is casted.

___

+ **<u>Summon Darkness</u>:**
A number of add(s) will be summoned outside the arena and their number will change through the fight:
  + The first cast will summon 3 adds. They will cast **Ultima Ray**, a line AoE dealing <span class='magic'>magical damage</span>. The combination will create two safe spots opposite of each other.
  + The second cast will summon 1 add. He will cast **Ultima Ray**, a line AoE dealing <span class='magic'>magical damage</span>, cleaving the arena in two.
  + The third cast will summon 8 adds surrounding the arena. Four random adds will tether to either the DPS or the Tanks/Healers, they will receive a <span class='debuff'>Magic Vulnerability Up</span> debuff lasting 10 seconds and each add will perform **Ultima Blow**, a line AoE dealing <span class='magic'>magical damage</span>. Then the 4 other adds will tether to the 4 other players and do another **Ultima Blow**.

___

+ **<u>Missing Link</u>:**
Each DPS will be chained to a Tank/Healer with <span class='speDebuff'>Missing Link</span> <img class='iconImg' src='{{ site.data.iconList.P12S.MissingLink }}'> that can be broken with enough distance. Easier to break if the chained players are close to each other when <span class='speDebuff'>Missing Link</span> is applied.  
Players movement will be slowed while they are chained.

___

+ **<u>Demi Parthelion</u>:**
AoEs on the ground in a defined partern that trigger multiple times, dealing <span class='magic'>magical damage</span>.

___

+ **<u>Geocentrism</u>:**
*Pallan Athena* tentacles will surround the arena and affect the **Demi Parthelion** AoEs. The tentacles position will show how they are affected:
  + <u>Surrounding the arena</u>: outer **Demi Parthelion** will create a donut AoE, leaving a safe spot at the edge of the central **Demi Parthelion** AoE.
  + <u>Horizontally above the arena</u>: **Demi Parthelion** will move horizontally, leaving two horizontal lanes as safe spot between the previous **Demi Parthelion** AoEs.
  + <u>Vertically above the arena</u>: **Demi Parthelion** will move vertically, leaving two vertical lanes as safe spot between the previous **Demi Parthelion** AoEs.

___

+ **<u>Divine Excoriation</u>:**
Very small AoE on every player, dealing <span class='magic'>magical damage</span> and applying a <span class='debuff'>Magic Vulnerability Up</span> debuff.

___

+ **<u>Ultima Blow</u>:**
Tether from adds on four players. Performs a line AoE dealing proximity <span class='magic'>magical damage</span> and applying a <span class='debuff'>Magic Vulnerability Up</span> debuff to the first person hit.

</div>

<div class='guideSection' markdown='1'>
<h2><a id='ABTheClassicalConcepts'>The Classical Concepts</a></h2>

+ **<u>The Classical Concepts</u>:**
12 shapes (among a blue icosahedron (20 faces), a red pyramid and a yellow cube) will appear in the arena, 4 of each. These shapes will be placed in a 3 rows x 4 columns grid. Each column will have one and only one blue icosahedron.  
After a few seconds, each red pyramid and yellow cube will tether to a unique adjacent blue icosahedron. **Implode** will vary if shapes are tethered.

  Four players will receive the <span class='speDebuff'>Alpha Target</span> <img class='iconImg' src='{{ site.data.iconList.P12S.AlphaTarget }}'> debuff and the other four will receive <span class='speDebuff'>Beta Target</span> <img class='iconImg' src='{{ site.data.iconList.P12S.BetaTarget }}'>:
  + If a player with <span class='speDebuff'>Alpha Target</span> stand between a blue icosahedron and a red pyramid, the two shapes won't be tethered.
  + If a player with <span class='speDebuff'>Beta Target</span> stand between a blue icosahedron and a yellow cube, the two shapes won't be tethered.

  Furthermore, all players will be paired with someone of the opposite debuff with a marker among <span style='color: dodgerblue'>Cross</span>, <span style='color: MediumSeaGreen'>Triangle</span>, <span style='color: MediumPurple'>Square</span> and <span style='color: Tomato'>Circles</span>. After 3 seconds, players with the same marker will receive <span class='speDebuff'>Shackled Together</span> <img class='iconImg' src='{{ site.data.iconList.P12S.ShackledTogether }}'> tethering them for 11 seconds. If tethered players are too far from each other, they'll die.

___

+ **<u>Implode</u>:**
Each geometrical shapes will explode in a small AoE dealing <span class='magic'>magical damage</span> and applying a  debuff.  
Will explode in a raid-wide AoE if shapes are tether to other(s).

___

+ **<u>Palladian Ray</u>:**
Two tentacle blades will stab the floor and after a few second, each blade will target the four closest player with a cone AoE dealing <span class='magic'>magical damage</span>. The cone will persist for 3 seconds.

___

+ **<u>Panta Rhei</u>:**
*Pallen Athena* will rotate the whole block of shapes by 180°.

</div>

<div class='guideSection' markdown='1'>
<h2><a id='ABCaloricTheory'>Caloric Theory</a></h2>

+ **<u>Caloric Theory 1</u>:**
Raid-wide AoE dealing <span class='magic'>magical damage</span>.

  One DPS and one Tank/Healer will receive a fire marker. Once **Caloric Theory** cast is over, one of the markers will perform a share AoE dealing <span class='magic'>magical damage</span>, needing 2 players at least.

  Afterward, multiple debuffs will be applied to everyone:
  + Four random players (always including the players who got the fire markers before) will receive <span class='speDebuff'>Atmosfaction</span> <img class='iconImg' src='{{ site.data.iconList.P12S.Atmosfaction }}'> lasting 23 seconds. Performs **Dynamic Atmosphere** when it resolves.
  + The other four players will receive <span class='speDebuff'>Pyrefaction</span> <img class='iconImg' src='{{ site.data.iconList.P12S.Pyrefaction }}'> lasting 12 seconds. Performs **Pyre Pulse** when it resolves. The bearers can be identified by a flame above their heads.
  + Everyone will also receive <span class='speDebuff'>Close Caloric</span> <img class='iconImg' src='{{ site.data.iconList.P12S.CloseCaloric }}'> that can stack up to 5 times until the end of the mechanic. A stack is gain each time a player move or take damage from a <span class='speDebuff'>Pyrefaction</span> share.  
  If a player moves more than 9m, he will wipe the group. The lines that appear on the ground can be used to know how far you can move. The diagonal of a rectangle is equal to ~8m and the "height" of a rectangle is equal to ~4m.  
  <span class='speDebuff'>Atmosfaction</span> players receive 2 stacks and <span class='speDebuff'>Pyrefaction</span> players receive 1 stack.

  Once the first set of <span class='speDebuff'>Pyrefaction</span> resolves, two players among them will receive another <span class='speDebuff'>Pyrefaction</span> debuff lasting 11 seconds.

___

+ **<u>Pyre Pulse</u>:**
Share AoE dealing <span class='magic'>magical damage</span> and applying <span class='debuff'>Magic Vulnerability Up</span>.

___

+ **<u>Dynamic Atmosphere</u>:**
Large AoE dealing <span class='magic'>magical damage</span> and applying <span class='debuff'>Magic Vulnerability Up</span>.

___

+ **<u>Ekpyrosis</u>:**
Exaflare AoEs and proximity AoEs will appear. If the exaflares are along the North/South edge, the proximity AoE will be in the middle East/West of the arena. If the exaflares are along the East/West edge, the proximity AoE will be in the middle North/South of the arena.  
The proximity AoEs will resolve as the exaflares start moving. While the East/West exaflares move in a straight line the North/South ones will move sideways.  
4 seconds after the exaflares start moving, everyone will get hit by an AoE applying a <span class='debuff'>Magic Vulnerability Up</span> debuff.

  Every **Ekpyrosis** AoE deals <span class='magic'>magical damage</span>.

___

+ **<u>Caloric Theory 2</u>:**
Raid-wide AoE dealing <span class='magic'>magical damage</span>.

  One random player will receive a fire marker and the others will receive a wind marker. Once **Caloric Theory** cast is over, all wind marker will perform an AoE dealing <span class='magic'>magical damage</span>.

  Afterward, multiple debuffs will be applied to everyone:
  + A random player, except the player who got the fire marker, will receive <span class='speDebuff'>Entropifaction</span> <img class='iconImg' src='{{ site.data.iconList.P12S.Entropifaction }}'> with 8 stacks and lasting 26 seconds, the bearer can be identified by a flame above his head.  
  Every 3 seconds, <span class='speDebuff'>Entropifaction</span> will lose one stack and drop a fire AoE on the ground (**Entropic Excess**) that explodes after 3 seconds.  
  When the bearer touches another player, the debuff will be transferred to that player. The previous owner will get <span class='speDebuff'>Entropy Resistance</span> <img class='iconImg' src='{{ site.data.iconList.P12S.EntropyResistance }}'> for 3 seconds, forbidding him to receive <span class='speDebuff'>Entropifaction</span>.  
  + Everyone will receive the <span class='speDebuff'>Atmosfaction</span> debuff lasting 27 seconds.  
  + Everyone will also receive 2 stacks of <span class='speDebuff'>Close Caloric</span> debuff while the player who got the fire marker will receive 3 stacks.

</div>

<div class='guideSection' markdown='1'>
<h2><a id='ABPangenesis'>Pangenesis</a></h2>

+ **<u>Pangenesis</u>:**
Raid-wide AoE dealing high <span class='magic'>magical damage</span>.

  *Pallen Athena* will apply different debuff among the following:
  + <span class='speDebuff'>Unstable Factor</span> <img class='iconImg' src='{{ site.data.iconList.P12S.UnstableFactor }}'> : two players will fuse their <span class='speDebuff'>Unstable Factor</span> when they are close to each other. It will add both stacks, divide it by 2 (rounded down) and redistribute the stacks among the two players. To put it simply, if two players have a different number of stacks, the player with the most stack will lose one and the other none.  
  (i.e. a 2 stacks and a one stack players fuse: 2+1=3 => 3/2=1.5 (rounded down to 1) => one stack given to each players).
  + <span class='speDebuff'>Critical Factor</span> <img class='iconImg' src='{{ site.data.iconList.P12S.CriticalFactor }}'> : receive when losing the last stack of <span class='speDebuff'>Unstable Factor</span>. A slime (*Forbidden Factor*) will appear on the ground and will tether to a player once all towers are soaked, the tether can be grabbed by other player. After a few seconds, the slimes will rush to their player and perform **Factor In**
  + <span class='speDebuff'>Stable System</span> <img class='iconImg' src='{{ site.data.iconList.P12S.StableSystem }}'> : prevent player from fusing their <span class='speDebuff'>Unstable Factor</span>.
  + <span class='speDebuff'>Astral/Umbral Tilt</span> <img class='iconImg' src='{{ site.data.iconList.P12S.AstralTilt }}'>/<img class='iconImg' src='{{ site.data.iconList.P12S.UmbralTilt }}'>: swap the debuff element when hit by an attack of the opposite element. Die when hit by the same element.

  Everyone will receive a set of debuff with a <span class='speDebuff'>Stable System</span> debuff to avoid triggering <span class='speDebuff'>Unstable Factor</span> immediately:
  + Two random players with 2 stacks of <span class='speDebuff'>Unstable Factor</span> and a 16 seconds long <span class='speDebuff'>Astral/Umbral Tilt</span> debuff (one of each).
  + Two random players with 2 stacks of <span class='speDebuff'>Unstable Factor</span> and a 20 seconds long <span class='speDebuff'>Astral/Umbral Tilt</span> debuff (one of each).
  + Two random players with 1 stack of <span class='speDebuff'>Unstable Factor</span>.
  + Two random players with nothing, considered having 0 stack of <span class='speDebuff'>Unstable Factor</span>.

___

+ **<u>Pantheos</u>:**
<a id='ABPantheos'></a>
3 sets of polarized towers will spawn in a half random partern. Each tower requires two players to soak it, one player with a <span class='speDebuff'>Astral/Umbral Tilt</span> debuff of the opposite element and one player without a polarized debuff.  
The spawn order is shown below and follow this order: towers n°1 > towers n°2 and n°3 > towers n°4 and n°5. And then on each side, the towers elements are based on the first tower:
  + Tower n°1 element is random. Each side have opposite element.
  + Towers n°2 and n°4 have the same element as tower n°1.
  + Towers n°3 and n°5 are of the opposite element as tower n°1.

<img class='soloImg' src='{{ page.imagePath | append: 'pangenesisBase.jpg' }}'>

___

+ **<u>Factor In</u>:**
Massive AoE dealing <span class='magic'>magical damage</span> and applying a stack of <span class='speDebuff'>Fourfold-come Ruin</span>. If a player get 4 stacks of <span class='speDebuff'>Fourfold-come Ruin</span>, he'll receive the <span class='speDebuff'>Doom</span> debuff.  
Player with <span class='speDebuff'>Critical Factor</span> will receive lethal damage.

</div>
___
<h1><a id='Strategy'>Strategy</a></h1>

<div class='guideSection' markdown='1'>
<a id='SPhase1'></a>

The fight will start with **Ultima** followed by **Palladian Grasp**. The Tank targeted can stand alone on his side of the arena and use his invulnerability to trivialise the mechanic.

Right after, *Pallan Athena* will cast **Gaiaochos**, stack middle and mitigate as necessary. Once the arena has shrink, quickly check the adds to find the safe spots. When <span class='speDebuff'>Missing Link</span> is applied, DPS will move to the left safe spot while the Tanks/Healers will move to the right safe spot, breaking the chains at the same time.  
Then move back middle for **Geocentrism**. Wait for the tentacles to know **Geocentrism** will modify the ground AoEs and either spread around the centre **Demi Parthelion**, form a Melee and a Ranged horizontal line or form a Left/Right group vertical line. Check the diagrams bellow for fixed positions.  
While **Geocentrism** happens, **Divine Excoriation** will hit everyone so don't stack with anyone else.

{% assign slideCounter = 0 %}
{% include slideshow.html imgLink="gaia1-1.jpg;gaia1-2.jpg;gaia1-3donut.jpg;gaia1-3hori.jpg;gaia1-3verti.jpg" imgDesc="Regroup mid and check the adds;Split in DPS and Tanks/Healers groups;Positions for surrounding tentacles (<strong>Divine Excoriation</strong> not show here);Positions for horizontal tentacles;Positions for vertical tentacles" slideNumber=slideCounter %}

*Pallan Athena* will cast another **Ultima**, bringing back the original arena. She will immediately pursue with **The Classical Concept**, heal and mitigate if needed.  
Once your receive your marker, move in pair to your assigned column/blue icosahedron based on your marker: <span style='color: MediumSeaGreen'>Triangle</span> > <span style='color: Tomato'>Circles</span> > <span style='color: dodgerblue'>Cross</span> > <span style='color: MediumPurple'>Square</span>.  
Then the <span class='speDebuff'>Alpha Target</span> player will get in position to block the tether from an adjacent red pyramid and <span class='speDebuff'>Beta Target</span> will block an adjacent yellow square. If you have to choose between two possibilities for your shape, check the first shape and if it has another adjacent blue icosahedron it means it's the wrong one and you have to pick the other shape.  
After the tethers have been block, move between the shapes to dodge **Implode**.  
Right after, the two blades will stab the floor and **Palladian Ray** must be baited. Pairs on the left side (<span style='color: MediumSeaGreen'>Triangle</span> and <span style='color: Tomato'>Circles</span>) will bait the left blades while the pairs of the right side (<span style='color: dodgerblue'>Cross</span> > <span style='color: MediumPurple'>Square</span>) will bait the right blade. Be careful to not bait a cone toward the other group.

{% assign slideCounter = slideCounter | plus: 1 %}
{% include slideshow.html imgLink="concept1-1.jpg;concept1-2.jpg;concept1-3.jpg;concept1-4.jpg" imgDesc="Move in pair to your assigned position;Block your shape: alpha for red triangle, beta for yellow square;Dodge <strong>Implode</strong>;Bait <strong>Palladian Ray</strong> and move out" slideNumber=slideCounter %}

*Pallan Athena* will resume with another **Ultima** followed by **Crushing Helm**, remember to dispell the <span class='debuff'>Physical Vulnerability Up</span> debuff on the Tanks before the last hit.  
During this tank buster, everyone can get in their fixed position for the next mechanic, check the diagram below.

Now it's time for **Caloric Theory**. When the cast starts, one DPS and Tank/Healer will receive the fire marker. These two players and the Tanks middle must swap their position. Have one Tank scanning counter-clockwise from North and the other Tank clockwise from North-West. Don't forget to use some mitigation to cover **Caloric Theory** and the share that happen at the same time.  
Then the outer <span class='speDebuff'>Atmosfaction</span> will form a pair with the next clockwise <span class='speDebuff'>Pyrefaction</span> player, if it's impossible pair up with the next counter-clockwise <span class='speDebuff'>Pyrefaction</span> player. Then the middle DPS will pair with a free <span class='speDebuff'>Pyrefaction</span> player and finally the middle Tank/Healer will complete the last pair.

{% assign slideCounter = slideCounter | plus: 1 %}
{% include slideshow.html imgLink="calo1-1.jpg;calo1-2.jpg;calo1-3.jpg;calo1-4.jpg;calo1-5.jpg;calo1-6.jpg" imgDesc="Get to your static position and wait for getting the fire marker;Marked players move mid and Tank(s) replace them;<strong>Caloric Theory</strong> can is over and debuffs are assigned;Outer wind debuff move to the next clockwise fire player (or counter-clockwise if impossible, as shown for the DRK);Middle players pair with remaining pyrefaction players, DPS first then Tank/Healer;Debuffs resolve" slideNumber=slideCounter %}

Then two <span class='speDebuff'>Pyrefaction</span> players will receive another <span class='speDebuff'>Pyrefaction</span> debuff. These two players will move diagonally to the outside so they can pair with someone from the next clockwise group. If there's the another <span class='speDebuff'>Pyrefaction</span>, go check the other way.  
Once they are in position, the players without debuff will pair with the closest <span class='speDebuff'>Pyrefaction</span> player.

{% assign slideCounter = slideCounter | plus: 1 %}
{% include slideshow.html imgLink="calo1-7.jpg;calo1-8.jpg;calo1-9.jpg;calo1-10.jpg" imgDesc="Debuffs are assigned;Pyrefaction players move out to pair with the next clockwise non-atmosfaction player (or counter-clockwise if impossible, as shown for the BRD);Players without debuff rejoin their partner;Debuffs resolve" slideNumber=slideCounter %}

> You can also have someone who will call the pairs to make since with this strategy it is easy to identify <span class='speDebuff'>Pyrefaction</span> players and how to group them.

Afterward, **Ekpyrosis** will be casted, spawning exaflares on North/South edges or the East/West edges on the arena.  
Based on where exaflares spawn, form Left/Right groups ou Melee/Ranged groups and move next to the exaflares so you're far from the proximity AoEs.  
Once the first set of exaflares starts moving, quickly spread along that edge to avoid cliping other player with the **Ekpyrosis** AoE that drop on everyone.  
Finally, move where the first exaflares were to dodge the passage of the exaflares from the opposite side.

{% assign slideCounter = slideCounter | plus: 1 %}
{% include slideshow.html imgLink="ek1.jpg;ek2.jpg;ek3.jpg" imgDesc="Split in two groups and move next to the exaflares;Spread along the edge;Group back to the dodge the opposite exaflares" slideNumber=slideCounter %}

Once it's over, *Pallen Athena* will cast another **Ultima** before starting **Pangenesis** followed by **Pantheos**.  
Make an horizontal line during **Pangenesis** to simplify player assignments. <u>For consistency, the main Tank MUST BE the rightmost player in the line.</u>  
Players with no stack of <span class='speDebuff'>Unstable Factor</span> will move forward, the players with 1 stack of <span class='speDebuff'>Unstable Factor</span> will move back, leaving the rest with 2 stacks of <span class='speDebuff'>Unstable Factor</span> middle. Then:

+ Players with no stack: leftmost player move in the first tower on the left while the rightmost player will take the first right tower.
+ Players with 1 stack: leftmost player move in the second South tower on the left while the rightmost player will take the second South tower on the right.
+ Players with 2 stack: once **Pantheos** cast is over, they will move to the correct side based on their <span class='speDebuff'>Astral/Umbral Tilt</span> debuff element and the first tower element. The correct side being the side with a tower of the opposite element of the debuff. Then short duration debuff (16s) will soak the tower from the first set while the long duration debuff (20s) will get in position to soak the South tower form the second set.

{% assign slideCounter = slideCounter | plus: 1 %}
{% include slideshow.html imgLink="pant1.jpg;pant2.jpg;pant3.jpg;pant4.jpg" imgDesc="Form a line;1 stack players move in front, 0 stack players move in the back;1 stack players move move to South tower of 2nd set</br>0 stack players move to the first tower;Short <span class='speDebuff'>Tilt</span> duration (16s) move inside the first towers</br>Long <span class='speDebuff'>Tilt</span> duration (20s) move to South tower of 2nd set (timers not displayed here)" slideNumber=slideCounter %}

> For tower pattern, follow this link => <a href="{{ post_url | append: '#ABPantheos' }}">HERE</a> <=

While the first set of tower is done, each pair will start to start their <span class='speDebuff'>Unstable Factor</span> debuff. Wait for the fusing to be done before moving to the next spot. Players who soak the first tower will move into the North tower from the second set on their side.  
Once the second set is done, wait if your fusing isn't over yet and move into the next spot. Players with <span class='speDebuff'>Astral/Umbral Tilt</span> debuff must swap line (North -> South and vice versa) and player without <span class='speDebuff'>Astral/Umbral Tilt</span> will stay on the same line for the last tower.

Once the tower are done, the slime tethers will appear. The group will move to the South while staying of the left side of th arena.  
The left and right player who had no stack of <span class='speDebuff'>Unstable Factor</span> thus no <span class='speDebuff'>Critical Factor</span> debuff must grab the 3 tethers on their side. Then the left player will move to the North West corner and the right player will move North (East-ish) while staying on the right side of the arena.  
At the same time, the main Tank will get **Palladian Grasp** and should be on the right side of the arena. The right player who grabbed the tethers must remember to move to the left side once **Factor In** is done.

{% assign slideCounter = slideCounter | plus: 1 %}
{% include slideshow.html imgLink="pant5.jpg;pant6.jpg;pant7.jpg;pant8.jpg;pant9.jpg;pant10.jpg;pant11.jpg" imgDesc="<span class='speDebuff'>Unstable Factor</span> reduced and outer pairs move into the North towers ;<span class='speDebuff'>Unstable Factor</span> reduced, <span class='speDebuff'>Astral/Umbral Tilt</span> players swap line and other players keep moving into the next tower;All <span class='speDebuff'>Unstable Factor</span> removed;Regroup South while player without <span class='speDebuff'>Critical Factor</span> grab 3 tethers each;Left player moves in North West corner, right player moves North a bit East-ish, Tank is targeted by <strong>Crushing Helm</strong>;<strong>Factor In</strong> happens;North player sidesteps to dodge <strong>Crushing Helm</strong>" slideNumber=slideCounter %}

> To be noted, **Factor In** goes through tank invulnerability.

</div>

<div class='guideSection' markdown='1'>
<a id='SPhase2'></a>

The fight will continue with **The Classical Concept**, version 2. It is resolved the same way as the first one but *Pallen Athena* will cast **Panta Rhei** soon after, rotating the whole block of shapes by 180°.  
Move to your usual position and during the cast of **Panta Rhei**, cross though the middle of the arena to end up at your final position. Remember to move with your partner since you have <span class='speDebuff'>Shackled Together</span>.  
For example, if your base position is <u>White 4</u>, you have to move to <u>Grey 4</u> by running through the middle (number 9):

<img class='soloImg' src='{{ page.imagePath | append: 'concept2Base.jpg' }}'>

This time, **Palladian Ray** must be baited first then while move out of **Palladian Ray** cone, dodge the **Implode** AoEs at the same time.

{% assign slideCounter = slideCounter | plus: 1 %}
{% include slideshow.html imgLink="concept2-1.jpg;concept2-2.jpg" imgDesc="Bait <strong>Palladian Ray</strong>;Move out and dodge <strong>Implode</strong> at the same time" slideNumber=slideCounter %}

Afterward, another **Ultima** is casted with another **Crush Helm**, mitigate and resolve as usual.

It's now time for the second **Caloric Theory**. For this version, move to your pre-assigned position and the player who got the fire marker must move in the middle and swap with the player there. Remember to mitigate since **Caloric Theory** will hit everyone twice, the initial cast + wind AoEs.  
Then a random player will get the <span class='speDebuff'>Entropifaction</span>.

{% assign slideCounter = slideCounter | plus: 1 %}
{% include slideshow.html imgLink="calo2-1.jpg;calo2-2.jpg;calo2-3.jpg" imgDesc="Get into your positions;Fire marker move mid and swap with that player;<strong>Caloric Theory</strong> can is over and debuffs are assigned" slideNumber=slideCounter %}

Once the first stack is lost, that player will move to the next clockwise player to give him the <span class='speDebuff'>Entropifaction</span> debuff and dodge the **Entropic Excess** AoE at the same time.  
Wait there and once another stack is lost, the player without the debuff will move toward the outside to dodge **Entropic Excess** and the <span class='speDebuff'>Entropifaction</span> player will resume the hot potato game.  
When there's no stack left, the player with the debuff can stay where he is and dodge the last **Entropic Excess** when it drops on the ground. And wait until the <span class='speDebuff'>Atmosfaction</span> debuffs run off.

{% assign slideCounter = slideCounter | plus: 1 %}
{% include slideshow.html imgLink="calo2-4.jpg;calo2-5.jpg;calo2-6.jpg;calo2-7.jpg;calo2-8.jpg;calo2-9.jpg;calo2-10.jpg;calo2-11.jpg;calo2-12.jpg" imgDesc="<span class='speDebuff'>Entropifaction</span> moves to the next clockwise spot;<span class='speDebuff'>Entropifaction</span> player moves to the next clockwise spot and the other moves away;<span class='speDebuff'>Entropifaction</span> player moves to the next clockwise spot and the other moves away;<span class='speDebuff'>Entropifaction</span> player moves to the next clockwise spot and the other moves away;<span class='speDebuff'>Entropifaction</span> player moves to the next clockwise spot and the other moves away;<span class='speDebuff'>Entropifaction</span> player moves to the next clockwise spot and the other moves away;<span class='speDebuff'>Entropifaction</span> player moves to the next clockwise spot and the other moves away;<span class='speDebuff'>Entropifaction</span> player moves away;Debuffs resolve" slideNumber=slideCounter %}

> The middle player shouldn't move during the whole mechanic. Also try to not block other players when moving out from **Entropic Excess**.

Right after is **Ekpyrosis** that is solved exactly as before. Quickly heal once it's over since the next **Ultima** is immediately after.

The next and final mechanic is **Gaiaochos**. Stack middle and mitigate and wait for **Summon Darkness**. Find the add and dodge its **Ultima Ray**, DPS to the left of the add and Tanks/Healers to the right to break the chains.  
When the chains are applied, **Demi Parthelion** AoE will appear on the ground and *Pallen Athena* will then cast **Geocentrism**. Break the chains and get in position for **Geocentrism** AoE. While **Geocentrism** AoE is hitting, spread out for **Divine Excoriation**.  
Another **Summon Darkness** will spawn 8 adds around the arena this time. The four tethered players must move to the opposite of their add and their partner must move right in front of them to same them.  
*Pallen Athena* will cast **Ultima** then the 4 other adds will tether to the four other players, solve it the same way.  
Right after, the boss will cast another **Ultima** before casting her long enrage **Ignorabimus**.

</div>
