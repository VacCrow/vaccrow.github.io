---
layout: guides
title: Anabaseios - The Twelfth Circle (Savage) | P12S (Part 1)
imagePath: /assets/img/guides/savages/pandaemonium/P12S_Part1/
slideNumber: 7
---

  {% comment %}
      <!-- cSpell:ignore dvance -->
  {% endcomment %}

*Patch: 6.4  
Minimum ilvl: i640  
DPS Requirement: 71.1k (with downtime)  
Enrage timer: 7:45  
<span class='debuff'>Damage Down</span> potency: 38%  
Loot: None since it's a door boss*

___

<h1><a id='AbilitiesBreakdown'>Abilities Breakdown</a></h1>

<div class='guideSection' markdown='1'>
<h2><a id='ABGeneralAbilities'>General Abilities</a></h2>

+ **<u>On the Soul</u>:**
Raid-wide AoE dealing <span class='magic'>magical damage</span>.

___

+ **<u>Trinity of Souls</u>:**
Three of *Athena* wings will glow in sequence, one top wing, one middle wing and one bottom wing. Following the same order, *Athena* will cleave the same side as the glowing wings, dealing <span class='magic'>magical damage</span> and applying a <span class='debuff'>Damage Down</span> to anyone hit.  
If the wings glow from the botton to the top, *Athena* will do a U-turn after each cleave so the second cleave will hit the other side.

___

+ **<u>Glaukopis</u>:**
Two hits line AoE tank buster dealing <span class='magic'>magical damage</span>, applying a <span class='debuff'>Magic Vulnerability Up</span> debuff for 4 seconds.  
Target for the first attack is set when the cast begins, target for the second attack is set when the cast is over.

___

+ **<u>Apodialogos/Peridialogos</u>:**
*Athena* will choose two targets and perform a shared AoE tank-buster dealing <span class='phys'>physical damage</span> and applying a <span class='debuff'>Bleed</span> and a <span class='debuff'>Magic Vulnerability Up</span> debuffs on one target and a shared AoE dealing <span class='magic'>magical damage</span> on the other target.

  + **Apodialogos**: shared AoE tank-buster on the furthest target and shared AoE on the closest target.
  + **Peridialogos**: shared AoE tank-buster on the closest target and shared AoE on the furthest target.

  The shared AoE is called **Dialogos**.

___

+ **<u>Unnatural Enchainment</u>:**
*Athena* will tether herself to tiles and will destroy them after 7 seconds. There is, at least, always one tile remaining.

___

+ **<u>Ultima Blade</u>:**
Raid-wide AoE dealing high <span class='magic'>magical damage</span>. It also create new walls in the arena forming an octagon.  
Furthemore, 8 *Anthropos* will spawn around *Athena* and cardinal ones will glow yellow and use **White Flame** while the others will glow purple and use **Clear Cut**.

___

+ **<u>Palladion</u>:**
Player will be numbered from 1 to 8. then *Athena* will jump to a random (inter)cardinal and will dash toward each number in order. It's a line AoE that deals <span class='magic'>magical damage</span> and applies a <span class='debuff'>Magic Vulnerability Up</span> debuff to anyone hit.  
Damage inflicted decreases with distance and will leave a puddle, that apply a <span class='debuff'>Bleed</span> debuff, at the location where the main target is hit.

  During the cast, the 8 adds will fly off in a certain order and while **Palladion** is happening, following that same order, they will fly down in the middle and use their ability then will proceed to leave the arena.

___

+ **<u>Theos's Ultima</u>:**
Raid-wide AoE dealing high <span class='magic'>magical damage</span>.  
The second cast is the enrage, a 7 second long cast.

</div>

<div class='guideSection' markdown='1'>
<h2><a id='ABDarkAndLightDebuffs'>Dark And Light Debuffs</a></h2>
Through the fight, *Athena* will apply dark or light polarized debuff(s) that will interact with other polarized debuffs or mechanics. If a player is hit by an attack from the same element, he will die. Here is the list of all the debuffs:
  + <span class='speDebuff'>Astralbright/Umbralbright Soul</span> <img class='iconImg' src='{{ site.data.iconList.P12S.AstralbrightSoul }}'>/<img class='iconImg' src='{{ site.data.iconList.P12S.UmbralbrightSoul }}'>: when it resolves, drops a tower of the same element under the player and do a small AoE, dealing <u>dark/light</u> <span class='magic'> magical damage</span>.  
  The tower must be soaked by a player with a debuff from the opposite element, dealing <span class='magic'>magical damage</span>. If not soaked, deals raid-wide <span class='magic'>magical damage</span> and applies a  <span class='debuff'>Damage Down</span> debuff.
  + <span class='speDebuff'>Astralstrong/Umbralstrong Soul</span> <img class='iconImg' src='{{ site.data.iconList.P12S.AstralstrongSoul }}'>/<img class='iconImg' src='{{ site.data.iconList.P12S.UmbralstrongSoul }}'>: *Athena* fires a shared line AoE of the same element toward the player, dealing <span class='magic'>magical damage</span>.  
  It will apply <span class='speDebuff'>Astral/Umbral Tilt</span> of the same element to any player hit or swap their <span class='speDebuff'>Astral/Umbral Tilt</span> element if a debuff is already applied.
  + <span class='speDebuff'>Astral/Umbral Tilt</span> <img class='iconImg' src='{{ site.data.iconList.P12S.AstralTilt }}'>/<img class='iconImg' src='{{ site.data.iconList.P12S.UmbralTilt }}'>: swap the debuff element when hit by an attack of the opposite element.

</div>

<div class='guideSection' markdown='1'>
<h2><a id='ABParadeigma'>Paradeigma</a></h2>

**Paradeigma** is a mechanic that appears four times in the fight acting differently each time. *Athena* will jump middle and a number of small orbs will spawn around her with different colors available. They will transform into adds named *Anthropos* and perform different action based on their color:

+ Yellow - **White Flame**: Line AoE from *Anthropos* aimed at the closest player, dealing <span class='magic'>magical damage</span> and applying a <span class='debuff'>Magic Vulnerability Up</span> debuff.
+ Blue - **Polarized Sear**: Polarized tether with damage based on distance, the further the better. When it resolves, fires a line AoE dealing <u>dark/light</u> <span class='magic'>magical damage</span>.
+ Red - **Ray of Light**: *Anthropos* fires a large line AoE in front of it, dealing <span class='magic'>magical damage</span> and applying a <span class='debuff'>Damage Down</span> debuff. They spawn on the North edge of the arena.
+ Purple - **Clear Cut**: small 270° cleave in front the add, dealing <span class='magic'>magical damage</span> (TBD).

*Athena* will usually cast **Engravement of Souls** right after, applying debuff(s) or tether on players for the incoming mechanic.

___

+ **<u>Paradeigma 1</u>:**
*Athena* will spawn four *Anthropos* on either the North or South side of the arena, a pair on each East/West side. Each pair will use **White Flame** sequentially.

___

+ **<u>Paradeigma 2</u>:**
Six *Anthropos* will spawn, two on North edge that will use **Ray of Light** and four on cardinals (slightly tilted) that will use **Polarized Sear**.  
There is two Astral and two Umbral **Polarized Sear** tether, randomly, on 2 Tanks/Healers and 2 DPS .  
The non-tethered players will receive <span class='speDebuff'>Astralbright/Umbralbright Soul</span> <img class='iconImg' src='{{ site.data.iconList.P12S.AstralbrightSoul }}'>/<img class='iconImg' src='{{ site.data.iconList.P12S.UmbralbrightSoul }}'> debuffs, two of each element.

___

+ **<u>Paradeigma 3</u>:**
Six *Anthropos* will spawn, two East, two West and two on opposite intercardinal. East/West will use **Polarized Sear** and the others two will use **White Flame**.  

  + All DPS will receive <span class='speDebuff'>Astral/Umbral Tilt</span> <img class='iconImg' src='{{ site.data.iconList.P12S.AstralTilt }}'>/<img class='iconImg' src='{{ site.data.iconList.P12S.UmbralTilt }}'>, two debuffs of each element.
  + Two Tanks/Healers will receive <span class='speDebuff'>Astralbright/Umbralbright Soul</span> <img class='iconImg' src='{{ site.data.iconList.P12S.AstralbrightSoul }}'>/<img class='iconImg' src='{{ site.data.iconList.P12S.UmbralbrightSoul }}'> debuffs of the same element.
  + The other two will respectively get <span class='speDebuff'>Quartered Soul</span> <img class='iconImg' src='{{ site.data.iconList.P12S.QuarteredSoul }}'> and <span class='speDebuff'>X-marked Soul</span> <img class='iconImg' src='{{ site.data.iconList.P12S.XMarkedSoul }}'>:
    + <span class='speDebuff'>Quartered Soul</span> : the player will drop a + shaped AoE when it resolves. The AoE will trigger after 3 seconds dealing <span class='magic'>magical damage</span>.
    + <span class='speDebuff'>X-marked Soul</span> : the player will drop a X shaped AoE when it resolves. The AoE will trigger after 3 seconds dealing <span class='magic'>magical damage</span>.

  Once debuff are applied, *Athena* will cast **Unnatural Enchainment** and destroy 4 platforms making it impossible to move to another platform.

___

+ **<u>Paradeigma 4</u>:**
Two *Anthropos* will spawn on the North edge of the arena that will cast **Ray of Light**.  
The adds won't be perfectly placed and must looked at to properly avoid their attack.

</div>

<div class='guideSection' markdown='1'>
<h2><a id='ABSuperchainTheory'>Superchain Theory</a></h2>
Superchain Theory is a mechanic that appears three times in the fight acting differently each time. A number of static orbs will appear and after a few seconds, new shapes will be chained to them. The shapes will then start to move toward their orb and will be resolved when they reach it:

+ **Superchain Emission** (purple spikes): cone AoE on every Tanks/Healers or DPS than must be shared with another player and applies a <span class='debuff'>Magic Vulnerability Up</span> debuff.
+ **Superchain Radiation** (orange spikes): cone AoE on every player and applies a <span class='debuff'>Magic Vulnerability Up</span> debuff.
+ **Superchain Burst** (green sphere): pointblank AoE that applies a <span class='debuff'>Damage Down</span> debuff.
+ **Superchain Coil** (blue donut): donut-shaped AoE that applies a <span class='debuff'>Damage Down</span> debuff.

All shapes deals <span class='magic'>magical damage</span>.

___

+ **<u>Superchain Theory 1</u>:**
Players will receive the following debuffs (roles shown below can be swapped when applied, DPS <=> Tanks/Healers):
  + <span class='speDebuff'>Heavensflame Soul</span> on every Tanks/Healers. Explodes in AoE on the beared when it resolves, dealing <span class='magic'>magical damage</span> and applying a <span class='debuff'>Magic Vulnerability Up</span> debuff.
  + <span class='speDebuff'>Astral/Umbral Tilt</span> <img class='iconImg' src='{{ site.data.iconList.P12S.AstralTilt }}'>/<img class='iconImg' src='{{ site.data.iconList.P12S.UmbralTilt }}'> on every Tanks/Healers, two elements of each.
  + <span class='speDebuff'>Astralbright/Umbralbright Soul</span> <img class='iconImg' src='{{ site.data.iconList.P12S.AstralbrightSoul }}'>/<img class='iconImg' src='{{ site.data.iconList.P12S.UmbralbrightSoul }}'> on two DPS, one element of each.
  + <span class='speDebuff'>Astralstrong/Umbralstrong Soul</span> <img class='iconImg' src='{{ site.data.iconList.P12S.AstralstrongSoul }}'>/<img class='iconImg' src='{{ site.data.iconList.P12S.UmbralstrongSoul }}'> on the other two DPS, one element of each.

  4 static orbs spawn on intercardinals and will resolve following this order:
  + On a random corner: **Superchain Emission** (purple spikes) or **Superchain Radiation** (orange spikes) <u>AND</u> **Superchain Burst** (green sphere) or **Superchain Coil** (blue donut).
  + Adjacent corners: **Superchain Burst** (green sphere) on a corner and **Superchain Coil** (blue donut) on the other.
  + Remaining corner: **Superchain Burst** (green sphere) <u>AND</u> **Superchain Coil** (blue donut), one after the other, the order is random.

___

+ **<u>Superchain Theory 2A</u>:**
Three static orbs will appear, one North, one middle and one South and will resolve following this order:
  + North or South: **Superchain Emission** (purple spikes).
  + Middle: **Superchain Coil** (blue donut).
  + North or South: **Superchain Emission** (purple spikes) or **Superchain Radiation** (orange spikes).
  Some **Superchain Burst** (green sphere) will be chained to static orb blocking spots where nothing can happen (i.e. during the middle **Superchain Coil**, **Superchain Burst** will happen North and South).

  The orb order is fully random, so it can be North > Middle > North or South > Middle > North for example, only Middle is fixed.

  In the meantime, *Athena* will cast **Trinity of Souls**.

___

+ **<u>Superchain Theory 2B</u>:**
Four static orbs will appear, one on each cardinal and will resolve following this order:
  + North and South: **Superchain Coil** (blue donut) on one orb, **Superchain Burst** (green sphere) on the other.
  + East and West: **Superchain Burst** (green sphere) on one orb, **Superchain Emission** (purple spikes) or **Superchain Radiation** (orange spikes) on the other.
  + North and South: **Superchain Burst** (green sphere) AND **Superchain Radiation** (orange spikes) on one orb, **Superchain Burst** (green sphere) on the other.

  The orb order is fully random.

  When the first set of shapes start to move, *Athena* will cast **Parthenos**.  
  After the second set of shapes, adds from **Paradeigma** will perform **Ray of Light**.  
  During the third set of shapes, the boss will start to cast **Unnatural Enchainment** leaving only one tile left.

  ___

  + **<u>Parthenos</u>:**
  Line AoE going through *Athena* aimed at the main target, dealing <span class='magic'>magical damage</span>.

</div>

<h1><a id='Strategy'>Strategy</a></h1>

<div class='guideSection' markdown='1'>
<h1><a id='SPhase1'>Phase 1</a></h1>

*Athena* starts with **On the Soul** followed by **Paradeigma 1**.

Identify which side of the arena the *Anthropos* spawned and have the group to the opposite side. Then on the adds side, one ranged DPS will move to the middle on the arena, one Tank will move at max melee range from the boss and the other Tank will stand between these two players.  
Before the first set of **White Flame** happens, the middle Tank must use his invulnerability because he will receive 2 **White Flame** at once while the other Tank and the ranged DPS will get hit once.  
Then, once the first set is done, the ranged DPS will move back to the group while both Tanks will use their invulnerability to cancel the second set.

At the same time, *Athena* will prepare and use **Trinity of Souls**. Identify which sides are safes and dodge while **White Flames** happen. For this cast the wings will always glow from bot to top.

{% assign slideCounter = 0 %}
{% include slideshow.html imgLink="para1-1.jpg;para1-2.jpg;para1-3.jpg;para1-4.jpg" imgDesc="Dodge first <strong>Trinity</strong>;First <strong>White Flame</strong> happen;Dodge second <strong>Trinity</strong>;Dodge third <strong>Trinity</strong> and second <strong>White Flame</strong> happen at the same time" slideNumber=slideCounter %}

> There's an alternative way, where both Tanks use their invulnerability but the main Tank must mitigate the next auto attack since the <span class='debuff'>Magic Vulnerability Up</span> is still up.

Afterward *Athena* will begin **Paradeigma 2**. The four adds on cardinals will tether to 2 Tanks/Healers and 2 DPS that must move away from their add to stretch the tether in a straight line and form a box around *Athena* with their tethers.  
Meanwhile, the players with <span class='speDebuff'>Astralbright/Umbralbright Soul</span> must drop a tower next to a tethered player of the opposite element. To do so, while looking at the North, Tanks/Healers will rotate clockwise to take the first available spot and DPS will rotate counter-clockwise.  
Once the towers are dropped, players who had the tethers soak the near tower and check the adds North to dodge the line AoEs that come after a few seconds. The two adds North cannot spawn next to each other, thus their attacks will have a safe space in between.

{% assign slideCounter = slideCounter | plus: 1 %}
{% include slideshow.html imgLink="para2-1.jpg;para2-2.jpg;para2-3.jpg;para2-4.jpg" imgDesc="Get in positions;Towers are dropped and <strong>Polarized Sear</strong> happens;Tether players soak the tower next to them;Dodge <strong>Ray of Light</strong> from the North adds" slideNumber=slideCounter %}

Afterward, *Athena* will cast **On the Soul** followed by **Glaukopis**, swap Tanks during the cast and after the second hit.

Next is **Superchain theory 1**, regroup around the first set of shapes, either in or out, and spread around or form pairs based on shapes.  
Then move inside the adjacent **Superchain Coil** (blue donut) orb and form groups for <span class='speDebuff'>Astralstrong/Umbralstrong Soul</span>. Players with a Umbral debuff (light one) will group left while players with an Astral debuff (dark one) will group to the right. Player with <span class='speDebuff'>Umbralstrong Soul</span> debuffs will move with the left group and the <span class='speDebuff'>Astralstrong Soul</span> player with the right group.  
Finally move to the next corner and do a in/out or out/in based on the shapes order.  
Afterward, the <span class='speDebuff'>Heavensflame Soul</span> players will move away to not kill anyone with their explosion. The <span class='speDebuff'>Astralbright/Umbralbright Soul</span> players will drop their tower and the <span class='speDebuff'>Astralstrong/Umbralstrong Soul</span> players will soak them afterward.

{% assign slideCounter = slideCounter | plus: 1 %}
{% include slideshow.html imgLink="chain1-1.jpg;chain1-2.jpg;chain1-3.jpg;chain1-4.jpg;chain1-5.jpg;chain1-6.jpg" imgDesc="Do spread or pair <u>AND</u> in or out;Move in, umbral debuffs left and astral debuffs right, lasers adjust opposite;Do the first part of in/out;Do the second part;<strong>Heavensflame Soul</strong> players move away and tower are dropped;Laser players soak the towers" slideNumber=slideCounter %}

Once everything is over, *Athena* will perform another **Trinity of Souls** but the order for this one is random. It's followed by **Apodialogos/Peridialogos**, have the group moving inside and the Tanks outside for the former and do the opposite for the latter. Then quickly heal for the incoming **On the Soul**.

> An easy way to remember **Apodialogos** is that the group must <u>A</u>dvance to bait the share.

*Athena* will cast another **One The Soul** followed by **Paradeigma 3** and **Unnatural Enchainment**, destroying one platform on each row.

Every DPS will receive their tether and must stretch their tether by moving to the safe platform, opposite of their add (Check the diamgram to see how to position). The player with <span class='speDebuff'>Quartered Soul</span> will move to the North platform while the player with <span class='speDebuff'>X-marked Soul</span> will move to the South one. The Tanks/Healers with <span class='speDebuff'>Astralbright/Umbralbright Soul</span> will split to the middle East and West platform, one on each.  
After a few second, unaspected towers will appear on every platform and must be soaked by Tanks and Healers. Soon after,  **Polarized Sear** tethers will resolve and Tanks/Healers, especially the middle ones, may have to move away from the boss to avoid being clipped by it.  
Then the <span class='speDebuff'>Quartered Soul</span> player must place his AoE on the North corner while the <span class='speDebuff'>X-marked Soul</span> player will place his AoE at the South cardinal edge. At the same time, the <span class='speDebuff'>Astralbright/Umbralbright Soul</span> players must drop their tower at the correct place:

+ If the <span class='speDebuff'>Astralbright/Umbralbright Soul</span> player is next to DPS who had **Polarized Sear** of the same element, he must drop the tower in the middle of the arena so a DPS from the opposite side can soak it.
+ If the <span class='speDebuff'>Astralbright/Umbralbright Soul</span> player is next to DPS who had **Polarized Sear** of the opposite element, he can drop the tower on his current platform.

Finally, the DPS how can soak the aspected tower must do so, the DPS who had a horizontal tether will take the middle tower while the DPS who crossed his tether will take the other one. The DPS who aren't soaking along with the North/South player have to bait **White Flames** from the adds inside the arena.

{% assign slideCounter = slideCounter | plus: 1 %}
{% include slideshow.html imgLink="para3-1.jpg;para3-2.jpg;para3-3.jpg" imgDesc="Tanks/Healers on each platform in a tower, DPS stretch their tethers;X and + debuffs dropped, towers placed so DPS with opposite elements can soak them;North/South players with non-soaking DPS bait <strong>White Flame</strong>" slideNumber=slideCounter %}

*Athena* will cast another **On The Soul** and restore the platforms at the same time. It is followed by another **Glaukopis**, double swap tank as previously.

</div>

<div class='guideSection' markdown='1'>
<h1><a id='SUltimateBlade'>Ultimate Blade</a></h1>

Pop some mitigation for the incoming **Ultima Blade** and get ready to receive your **Palladion** number. Then *Athena* will jump to a random (inter)cardinal that will be considered as North for the rest of the mechanic</u>.  
Quickly make pairs based on your number: 1/3 South, 2/4 North, 5/7 West and 6/8 East. The pair numbered 2/4 on North must stand away from the North until the first dash happens and avoid, then move North to get ready to the second **Palladion**.  
Once a pair is hit by **Palladion**, they must move clockwise to the edge of the newly appeared puddle to avoid the following **Palladion** and be ready to bait the one after. Once a pair reach the next cardinal, the other pair at that location will relay them.  
At the same time, the *Anthropos* at the centre of the arena will perform either **White Flame** and **Clear Cut**, avoid sitting in middle to dodge both **Clear Cut** and **Palladion**. Each **White Flame** must be baited by a pair who isn't currently soaking **Palladion**, the order is: 5/7 > 6/8 > 1/3 > 2/4.

Once **Palladion** is over and the arena is back to its original shape, regroup on the North platforms to dodge **Unnatural Enchainment** and mitigate for **Theos's Ultima**.

+ *Watch a video for now, I'm too lazy. uwu*

> Due to the fact that **White Flame** and **Clear Cut** order is a bit random, the timing may not be accurate. Only a rough timing is displayed here.

</div>

<div class='guideSection' markdown='1'>
<h1><a id='SPhase2'>Phase 2</a></h1>

The main tank must keep the boss middle and facing North until *Athena* starts casting **Superchain Theory2A**.  
Quickly identify where the short **Superchain Emission** (purple spikes) is chained with and move next to that orb. You should also check is the long **Superchain Emission** (purple spikes) or **Superchain Radiation** (orange spikes) is linked to the North or South orb.  
*Athena* will start casting **Trinity of Souls**, check the wings order and the sides cleaved.  
The group must stand on the safe spot for the first wing and make pair around the first orb.  
Once the first set of mechanic happens, quickly move middle inside the **Superchain Coil** (blue donut) and dodge the second wing while inside it.  
Finally move toward the final orb while dodging the last wing. Then either make pairs or spread around the orb based on the last shape. Since the third wing happens 1 second before the last shape you can now use the whole arena.

Here is an example with *Athena* facing North and cleaving Left > Right > Right:
{% assign slideCounter = slideCounter | plus: 1 %}
{% include slideshow.html imgLink="chain2A-1.jpg;chain2A-2.jpg;chain2A-3.jpg;chain2A-4.jpg;chain2A-5.jpg" imgDesc="Move to the safe side for wing and prepare for the first shape;First shape and wing resolve;Move middle and swap side if necessary to dodge second wing;Move toward the final shape and dodge the last wing;Do the final spread (or pairs)" slideNumber=slideCounter %}

After the last shape is done, *Athena* will cast **Apodialogos/Peridialogos** followed by **On The Soul**, mitigate as necessary.

Now *Athena* will cast **Superchain Theory2A** and **Paradeigma 4**. The main tank must keep her facing North until she starts casting **Parthenos**.  
First identify if **Superchain Coil** (blue donut) is linked to the North or South orb and move there. While the first shape is moving, check if the next shape, **Superchain Emission** (purple spikes) or **Superchain Radiation** (orange spikes) is chained to the East or West orb.  
Once the first shape resolve, move to the side where the second shape is and dodge **Parthenos**. Immediately after, make pairs or spread around the orb based on the shape.  
Then quickly check the North edge of the arena and move away from the adds' **Ray of Light**. Taking a few steps toward or away from the boss is usually enough.  
Finally move to the North/Side orb chained with **Superchain Radiation** (orange spikes) and make pairs or spread around it while staying out to dodge the **Superchain Burst** (green sphere).  
Once the last shape is resolved, *Athena* will cast **Unnatural Enchainment** leaving only one platform intact, next to the orb currently being used.

{% assign slideCounter = slideCounter | plus: 1 %}
{% include slideshow.html imgLink="chain2B-1.jpg;chain2B-2.jpg;chain2B-3.jpg;chain2B-4.jpg;chain2B-5.jpg;chain2B-6.jpg" imgDesc="Move to the inside the donut orb;First shapes resolve;Dodge <strong>Parthenos</strong> toward the next shape;Make pairs or spread around the orb;Look at the adds and dodge <strong>Ray of Light</strong>;Move to the orb chained to the orange shape and do out/spread" slideNumber=slideCounter %}

Once the platforms are down, heal up and mitigate for the two incoming **On The Soul**. *Athena* will conclude this fight with the enrage, **Theos's Blade**.

</div>
