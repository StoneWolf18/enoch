<head>
  <title>LAiA - Combat</title>
  <meta name="description" content="LA in Anarchy's NPC Guidelines.">
</head>
<div class="pageHero" style="background-image: url('assets/combatCover.png'); background-size: cover;">
  <div class="pageHeroHeader">
      Combat
  </div>
</div>

<div class="container">

<input class ="toc" id="toggle" type="checkbox">
 <label class ="toc" for="toggle">Table of Contents</label>
 <div id="expand">
   <section class ="toc">
   <ul class="toc">
   <li><a class="toc" href="#combat#initiative">Initiative</a></li>
   <li><a class="toc" href="#combat#flow">Flow of Combat</a></li>
   <li><a class="toc" href="#combat#turns">Anatomy of a Turn</a></li>
   <li><a class="toc" href="#combat#actions">Types of Actions</a></li>
     <ul class="toc">
     <li><a class="toc" href="#combat#free-actions">Free Actions</a></li>
       <ul class="toc">
       <li><a class="toc" href="#combat#blood-points">Spending Blood Points</a></li>
       <li><a class="toc" href="#combat#standing-up">Standing Up</a></li>
       <li><a class="toc" href="#combat#moving>Moving</a></li>
       <li><a class="toc" href="#combat#readying-a-weapon>Readying a Weapon</a></li>
       </ul>
     <li><a class="toc" href="#combat#discipline">Using a Discipline</a></li>
     <li><a class="toc" href="#combat#action-combat">Combat Maneuvers</a></li>
     </ul>
   <li><a class="toc" href="#combat#damage-types">Damage</a></li>
     <ul class="toc">
     <li><a class="toc" href="#combat#bashing">Bashing</a></li>
     <li><a class="toc" href="#combat#lethal">Lethal</a></li>
     <li><a class="toc" href="#combat#aggravated">Aggravated</a></li>
     </ul>
   <li><a class="toc" href="#combat#equipment">Equipment</a></li>
     <ul class="toc">
     <li><a class="toc" href="#combat#armor">Armor</a></li>
     <li><a class="toc" href="#combat#weapons">Weapons</a></li>
       <ul class="toc">
       <li><a class="toc" href="#combat#melee-weapons">Melee Weapon Chart</a></li>
       <li><a class="toc" href="#combat#ranged-weapons">Ranged Weapons Chart</a></li>
       </ul>
     </ul>
   <li><a class="toc" href="#combat#combat-maneuvers">Combat Maneuvers</a></li>
     <ul class="toc">
     <li><a class="toc" href="#combat#targeting">Targeting</a></li>
     <li><a class="toc" href="#combat#maneuver-complications">Maneuver Complications</a></li>
     <li><a class="toc" href="#combat#close-combat">Close Combat Maneuvers</a></li>
       <ul class="toc">
       <li><a class="toc" href="#combat#close-combat-table">Close Combat Maneuvers Table</a></li>
       <li><a class="toc" href="#combat#bite">Bite</a></li>
       <li><a class="toc" href="#combat#claw">Claw</a></li>
       <li><a class="toc" href="#combat#clinch">Clinch</a></li>
       <li><a class="toc" href="#combat#disarm">Disarm</a></li>
       <li><a class="toc" href="#combat#hold">Hold</a></li>
       <li><a class="toc" href="#combat#kick">Kick</a></li>
       <li><a class="toc" href="#combat#staking">Stake</a></li>
       <li><a class="toc" href="#combat#strike">Strike</a></li>
       <li><a class="toc" href="#combat#Sweep">Sweep</a></li>
       <li><a class="toc" href="#combat#Tackle">Tackle</a></li>
       </ul>
     </ul>
     <li><a class="toc" href="#combat#ranged-combat">Ranged Combat Maneuvers</a></li>
       <ul class="toc">
       <li><a class="toc" href="#combat#close-combat-table">Ranged Combat Maneuvers Table</a></li>
       <li><a class="toc" href="#combat#aiming">Aiming</a></li>
       <li><a class="toc" href="#combat#automatic-fire">Automatic Fire</a></li>
       <li><a class="toc" href="#combat#cover">Cover</a></li>
       <li><a class="toc" href="#combat#multiple-shots">Multiple Shots</a></li>
       <li><a class="toc" href="#combat#reloading">Reloading</a></li>
       <li><a class="toc" href="#combat#strafing">Strafing</a></li>
       <li><a class="toc" href="#combat#three-round-burst">Three-Round Burst</a></li>
       <li><a class="toc" href="#combat#two-weapons">Two Weapons</a></li>
       </ul>
     </ul>
   </ul>
   </section>
 </div>


In Vampire, combat mechanics have been made in such a way to highlight the drama violent conflict can bring to a story without diminishing the dark reality behind it. This is to give both the feeling of dynamic, vicious, combat, while still allowing for the spectacular elements that vampires bring to it.

The summary below has been reworded from what is described into V20 Core to give a clearer explanation of how combat functions.

<div class="leftHeader" id="initiative">Initiative</div>

Before anything can take place, we need to be aware of who managed to act first. This is why whenever a combat encounter beings, all characters will roll for initiative: a sum of their wits + dex dots added to a single d10. (For ease of use, the command `v.init RATING` can be sent instead of a regular roll.) The values of all the characters involved are put into order, and those who rolled highest will act first. In the event of a tie, the character with a higher initiative rating goes first.

<div class="leftHeader" id="flow">Flow of Combat</div>

Since everything is more or less happening at the same time, combat is divided into a series of parts: stages, turns, and rounds.

A <b>round</b> is when everyone in the initiative order has gone. In other words, once everyone takes their turn, a round has been completed.

As such, a <b>turn</b> is what rounds are divided into. When it's your time to act, that would be your turn.

<b>Stage</b> are the two parts turns are divided into: <em>Action</em> and <em>Resolution</em>.

An <b>action</b> is anything that requires a dice roll, such as an attack and many disciplines. The <b>resolution</b> is resolving the effects of your action, if there were any.

You are able to split your dice pool to accomplish multiple actions during a round. See the <a href="#system-reference#multiple-actions">system reference page</a> for more information on how that works.

<div class="yourAttentionPlease">

<b>What difficulty do I roll at?</b>

Unless a difficulty is outright stated, it will always be a default of 6.

</div>

<div class="leftHeader" id="turns">Anatomy of a Turn</div>

Generally, turns will go as follows:

* Declare free actions, such as movement or blood expenditure
* Take an action
  * Dexterity + Brawl for unarmed attacks
  * Dexterity + Melee for melee weapon attacks
  * Dexterity + Athletics for thrown ranged weapons
  * Dexterity + Firearms for guns and ballistic weapons
* Resolve the action
  * If an attack hit, the attacker rolls damage equal to strength + potence + weapon damage + any additional successes past the first on the attack roll. A minimum of one damage is always dealt, even if the roll is failed.
  * The target rolls to Stamina + Fortitude to soak the damage. Mortals can only soak bashing damage, Vampires can soak bashing (after halving the initial value) and lethal. Aggravated can only be soaked with dots of <a href="#disciplines/fortitude">Fortitude</a>.

<div class="leftHeader" id="actions">Types of Actions</div>

When your turn comes up, you can really attempt whatever you'd like as long as it's within the realm of possibility, according to the Storyteller. Though, unless you want to something specific, you are generally choosing between the options listed below.

<div class="secondHeader" id="free-actions">Free Actions</div>

Of course, not everything done during combat is going to require you to dedicate your entire action. Free Actions are:

<div class="thirdHeader" id="blood-points">Spending Blood Points</div>

This includes healing, buffing attributes, and some disciplines.

Healing while taking another action requires a successful Stamina + Survival roll versus difficulty 8. Failure means any blood spent is lost without effect, while botching will result in both that blood loss and receiving an additional health level of damage.

If an ability requires spending more blood to active than you can per turn (limited by your <a href="#backgrounds#generation">generation</a>), you would still need to wait until the required amount has been spent. This might require waiting 2-3 rounds, depending on the ability in question.

<div class="thirdHeader" id="standing-up">Standing Up</div>

Anyone knocked prone can devote their turn to standing without a roll. Those wanting to stand while doing something else will have to <a href="#system-reference#multiple-actions">take multiple actions</a>.

<div class="thirdHeader" id="moving">Moving</div>

A character can move up to half their total running speed (20 + [3x Dexterity] yards/meters) per turn without any penalty.

<div class="thirdHeader" id="readying-a-weapon">Readying a Weapon</div>

Drawing a blade or reloading a magazine can be accomplished without issue if nothing else is done that turn. Readying a weapon and acting in the same turn (such as drawing a pistol and firing) requires a Dexterity + Melee/Firearms roll versus difficulty 4.

<div class="secondHeader" id="discipline">Using a Discipline</div>

Any discipline that requires a dice roll is considered an action. Those that don't (such as Feral Claws or Baal's Caress) can be done for free.

<div class="secondHeader" id="action-combat">Combat Maneuvers</div>

Combat maneuvers are what make up the bulk of combat in Vampire. These include both melee and ranged attacks, and defensive actions such as blocking or dodging. See <a href="#combat#combat-maneuvers">the list of combat maneuvers</a> listed below for specifics.

<div class="leftHeader" id="damage-types">Damage</div>

There are three types of damage tracked: bashing (/), lethal (X), and aggravated (*). These are applied to a character's health track, starting at 'bruised'.

A higher level of damage are always applied at the top of the track, shifting the rest down. Meaning: if a character has taken 3 bashing [/][/][/][ ][ ][ ][ ] and then takes 1 lethal (X), it would be applied as: [X][/][/][/][ ][ ][ ].

Sustaining damage that overflows the health track causes the lowest form of damage currently taken to upgrade in severity. So, someone with 7 bashing [/][/][/][/][/][/][/] who sustains another level of bashing (/) would record it as: [X][/][/][/][/][/][/].

Wounded characters will have a dice penalty to their rolls depending on the amount of damage sustained. See the <a href="#system-reference#health-chart">system reference page</a> for the table.

For easier tracking, all character profiles managed by Caine will automatically update their health track accordingly through `v.damage heal` and `v.damage take`.

<div class="secondHeader" id="bashing">Bashing</div>

Bashing damage is blunt force trauma, such as punches, the use of a club, or throwing someone through a wall. This is always marked as a forward slash (/) on the health track.

Everyone can soak bashing damage when it's taken, though because vampires are more resilient then mortals, any bashing they received is halved before rolling for soak. Firearms are also considered bashing against Kindred targets, unless circumstance dictates otherwise.

Only mortals with a full health track of bashing will fall unconscious.

<div class="secondHeader" id="lethal">Lethal</div>

Lethal damage is caused by almost anything meant to draw blood, whether that's a sword or firearm. This is always recorded as an X on the health track.

Only vampires can resist lethal damage. Mortals sustaining any lethal damage past 'hurt' will require medical treatment to repair the wounds sustained, and take the time listed on page 286 of the core rulebook to heal.

Vampires whose health track reaches 'incapacitated' with a full health track of lethal will be put into torpor.

<div class="yourAttentionPlease">

<b>Important</b>

Any attacks targeting the head will <b>always</b> inflict lethal damage instead of bashing.

</div>

<div class="secondHeader" id="aggravated">Aggravated</div>

Aggravated damage originates from supernatural sources. A vampire's fangs, a lupine's claws, and sunlight are all examples of being a source of aggravated, which is marked on the health track with an asterisk (*).

Only supernatural creatures can sustain aggravated damage. Mortals suffering from such things will always apply the damage as lethal.

Vampires can only soak aggravated damage with the use of <a href="#disciplines/fortitude">Fortitude</a>.

A full health track of aggravated will cause Final Death, the vampire's corpse quickly crumbling to ash.

<div class="leftHeader" id="equipment">Equipment</div>

All weapons carried <b>must</b> be declared before initiative is rolled if they're to be used during a fight. Armor will not be counted unless prepared in advance (so you can't spontaneously be wearing a Kevlar police vest).

<div class="secondHeader" id="armor">Armor</div>

Armor adds dice to your character's soak pool against all damage types (except fire and sunlight), though most with a penalty to Dexterity-based actions. It isn't indestructible, though, and will break if a single attack equals twice the armor's rating.

<table>
<thead>
  <tr>
    <th class="blue">Class</th>
    <th class="blue">Example</th>
    <th class="blue">Armor Rating</th>
    <th class="blue">Penalty</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Class One</td>
    <td>Reinforced clothing</td>
    <td>1</td>
    <td>0</td>
  </tr>
  <tr>
    <td>Class Two</td>
    <td>Armor T-shirt</td>
    <td>2</td>
    <td>1</td>
  </tr>
  <tr>
    <td>Class Three</td>
    <td>Kevlar vest</td>
    <td>3</td>
    <td>1</td>
  </tr>
  <tr>
    <td>Class Four</td>
    <td>Flak jacket</td>
    <td>4</td>
    <td>2</td>
  </tr>
  <tr>
    <td>Class Five</td>
    <td>Full riot gear</td>
    <td>5</td>
    <td>3</td>
  </tr>
</tbody>
</table>

<div class="secondHeader" id="weapons">Weapons</div>

Given a lack of natural weapons, it's a given both Kindred and Kine alike would want to be carrying something to defend themselves with. All weapons have the following statistics:

<b>Damage:</b> the pool rolled for damage. <br>
<b>Conceal:</b> what type of clothing is needed to hide the weapon, whether that's a pocket (P), jacket (J), trench coat (T), or it can't be hidden (N). <br>

Ranged weapons will also have the following:

<b>Range:</b> the practical shot range in yards/meters. Firing at twice that distance is doable at an increase difficulty (8) <br>
<b>Rate:</b> the max amount of shots or three-round bursts that can be fired in a single turn. Does not apply to full-auto or spray attacks. <br>
<b>Capacity:</b> the amount of ammunition a weapon can hold. +1 indicates one held in the chamber, ready to fire.

<div class="yourAttentionPlease">

<b>Important</b>

The weapons listed on the charts below are the only we'll be using. Meaning, the use of an ornate dagger will use the stats of a knife, and a table-leg the stats of a club.

</div>

<div class="thirdHeader" id="melee-weapons" style="margin-top: 10px;">Melee Weapon Chart</div>

<table>
<thead>
  <tr>
    <th class="blue">Weapon</th>
    <th class="blue">Damage</th>
    <th class="blue">Conceal</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Sap<sup>B</sup></td>
    <td>Strength +1</td>
    <td>P</td>
  </tr>
  <tr>
    <td>Club<sup>B</sup></td>
    <td>Strength +2</td>
    <td>T</td>
  </tr>
  <tr>
    <td>Knife</td>
    <td>Strength +1</td>
    <td>J</td>
  </tr>
  <tr>
    <td>Sword</td>
    <td>Strength +2</td>
    <td>T</td>
  </tr>
  <tr>
    <td>Axe</td>
    <td>Strength +3</td>
    <td>N</td>
  </tr>
  <tr>
    <td>Stake<sup>P</sup></td>
    <td>Strength +1</td>
    <td>T</td>
  </tr>
</tbody>
</table>

<sup>B</sup> Denotes a blunt object; blunt objects inflict bashing damage unless targeted at the head <br>
<sup>P</sup> May paralyze a vampire if driven through the heart

<div class="thirdHeader" id="ranged-weapons">Ranged Weapons Chart</div>

<table>
<thead>
  <tr>
    <th class="blue">Type</th>
    <th class="blue">Example Weapon</th>
    <th class="blue">Damage</th>
    <th class="blue">Range</th>
    <th class="blue">Rate</th>
    <th class="blue">Capacity</th>
    <th class="blue">Conceal</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Revolver, Lt.</td>
    <td>SW Bodyguard (.38 Special)</td>
    <td>4</td>
    <td>12</td>
    <td>3</td>
    <td>6</td>
    <td>P</td>
  </tr>
  <tr>
    <td>Revolver, Hvy.</td>
    <td>Ruger Redhawk (.44 Magnum)</td>
    <td>6</td>
    <td>35</td>
    <td>2</td>
    <td>6</td>
    <td>J</td>
  </tr>
  <tr>
    <td>Pistol, Lt.</td>
    <td>HK USP (9mm)</td>
    <td>4</td>
    <td>20</td>
    <td>4</td>
    <td>15+1</td>
    <td>P</td>
  </tr>
  <tr>
    <td>Pistol, Hvy.</td>
    <td>Springfield XDM (.45 ACP)</td>
    <td>5</td>
    <td>25</td>
    <td>3</td>
    <td>13+1</td>
    <td>J</td>
  </tr>
  <tr>
    <td>Rifle</td>
    <td>Beretta Tikka T3 (30.06)</td>
    <td>8</td>
    <td>200</td>
    <td>1</td>
    <td>3+1</td>
    <td>N</td>
  </tr>
  <tr>
    <td>SMG, Small*</td>
    <td>Glock 18 (9mm)</td>
    <td>4</td>
    <td>20</td>
    <td>3</td>
    <td>17+1</td>
    <td>J</td>
  </tr>
  <tr>
    <td>SMG, Large*</td>
    <td>HK MP5 (9mm)</td>
    <td>4</td>
    <td>50</td>
    <td>3</td>
    <td>30+1</td>
    <td>T</td>
  </tr>
  <tr>
    <td>Assault Rifle*</td>
    <td>FN SCAR (5.56mm)</td>
    <td>7</td>
    <td>150</td>
    <td>3</td>
    <td>30+1</td>
    <td>N</td>
  </tr>
  <tr>
    <td>Shotgun</td>
    <td>Remington 870 (12-Gauge)</td>
    <td>8</td>
    <td>20</td>
    <td>1</td>
    <td>5+1</td>
    <td>T</td>
  </tr>
  <tr>
    <td>Shotgun, Semi-auto</td>
    <td>Benelli M4 Super 90 (12-Gauge)</td>
    <td>8</td>
    <td>20</td>
    <td>3</td>
    <td>6+1</td>
    <td>T</td>
  </tr>
  <tr>
    <td>Crossbow**</td>
    <td>n/a</td>
    <td>5</td>
    <td>20</td>
    <td>1</td>
    <td>1</td>
    <td>T</td>
  </tr>
</tbody>
</table>
*Indicates the weapon is capable of three-round bursts, full auto, and sprays.<br>
**The crossbow is included for characters who wish to try staking an opponent. Crossbows require five turns to reload. Unless the crossbow is aimed at the head or heart, it inflicts bashing damage on Kindred. It inflicts lethal damage versus mortals.

<div class="leftHeader" id="combat-maneuvers">Combat Maneuvers</div>

Combat would be pretty boring if it was a giant slugfest the entire time, which is where maneuvers come in! Both melee and ranged maneuvers will have the following information:

<b>Traits:</b> The attribute + ability pool rolled  <br>
<b>Accuracy:</b> the amount of dice added to the roll to hit a target <br>
<b>Difficulty:</b> modification of the base difficulty of the attack, which is normally 6 <br>
<b>Damage:</b> the dice pool rolled for damage

<div class="secondHeader" id="targeting">Targeting</div>

Aiming for a specific location increases the difficulty of the attack, though will add extra damage dice and could potentially avoid hitting where a target is armored.

<table>
<thead>
  <tr>
    <th class="blue">Target Size</th>
    <th class="blue">Difficulty</th>
    <th class="blue">Damage</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Medium (limb, briefcase)</td>
    <td>+1</td>
    <td>No modifier</td>
  </tr>
  <tr>
    <td>Small (hand, head, cellphone)</td>
    <td>+2</td>
    <td>+1</td>
  </tr>
  <tr>
    <td>Precise (eye, heart, lock)</td>
    <td>+3</td>
    <td>+2</td>
  </tr>
</tbody>
</table>

<div class="secondHeader" id="maneuver-complications">Maneuver Complications</div>

Combat doesn't come without some hindrances. Below are some of the most common:

* <b>Blinded:</b> Add two dice to attack rolls made against a blinded target. Furthermore, blind characters are at +2 difficulty on all actions, and ranged actions can't be taken at all.
* <b>Dazed:</b> If (after soak) the total number of successes in a damage roll is greater than a mortal's stamina, or a vampire's stamina + 2, the target is dazed and must spend their next turn shaking off the effects.
* <b>Immobilization:</b> all attacks against a struggling but immobilized target are made with +2 dice.
* <b>Knockdown:</b> When knocked down, the target can roll Dexterity + Athletics. On a success, they manage to get right back up, though failure will require their next turn being spent getting back to their feet. Botches will incur additional situational penalties.
* <b>Stake Through Heart:</b> <a href="#combat#staking">Staking</a> a vampire is difficult, though if managed will render them completely paralyzed. Mental disciplines can still be used, though they are unable to move or spend blood. The 'stake' used must be made of wood, otherwise you'll just piss them off.

<div class="secondHeader" id="close-combat">Close Combat Maneuvers</div>

<div class="thirdHeader" id="close-combat-table">Close Combat Maneuvers Table</div>

<b>(A):</b> The maneuver inflicts aggravated damage. <br>
<b>(C):</b> The maneuver carries over on successive turns.<br>
<b>(K):</b> The maneuver causes knockdown.<br>
<b>(R):</b> The maneuver reduces an opponent’s attack successes.

<table>
<thead>
  <tr>
    <th class="blue">Maneuver</th>
    <th class="blue">Traits</th>
    <th class="blue">Accuracy</th>
    <th class="blue">Difficulty</th>
    <th class="blue">Damage</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Bite</td>
    <td>Dex + Brawl</td>
    <td>+1</td>
    <td>Normal</td>
    <td>Str +1 (A)</td>
  </tr>
  <tr>
    <td>Block</td>
    <td>Dex + Brawl</td>
    <td>Special</td>
    <td>Normal</td>
    <td>None (R)</td>
  </tr>
  <tr>
    <td>Claw</td>
    <td>Dex + Brawl</td>
    <td>Normal</td>
    <td>Normal</td>
    <td>Str +1 (A)</td>
  </tr>
  <tr>
    <td>Clinch</td>
    <td>Str + Brawl</td>
    <td>Normal</td>
    <td>Normal</td>
    <td>Str (C)</td>
  </tr>
  <tr>
    <td>Disarm</td>
    <td>Dex + Melee</td>
    <td>Normal</td>
    <td>+1</td>
    <td>Special</td>
  </tr>
  <tr>
    <td>Dodge</td>
    <td>Dex + Athletics</td>
    <td>Special</td>
    <td>Normal</td>
    <td>None (R)</td>
  </tr>
  <tr>
    <td>Hold</td>
    <td>Str + Brawl</td>
    <td>Normal</td>
    <td>Normal</td>
    <td>None (C)</td>
  </tr>
  <tr>
    <td>Kick</td>
    <td>Dex + Brawl</td>
    <td>Normal</td>
    <td>+1</td>
    <td>Str +1</td>
  </tr>
  <tr>
    <td>Parry</td>
    <td>Dex + Melee</td>
    <td>Special</td>
    <td>Normal</td>
    <td>None (R)</td>
  </tr>
  <tr>
    <td>Stake</td>
    <td>Dex + Melee</td>
    <td>Normal</td>
    <td>9</td>
    <td>Str+1</td>
  </tr>
  <tr>
    <td>Strike</td>
    <td>Dex + Brawl</td>
    <td>Normal</td>
    <td>Normal</td>
    <td>Str</td>
  </tr>
  <tr>
    <td>Sweep</td>
    <td>Dex + Brawl/Melee</td>
    <td>Normal</td>
    <td>+1</td>
    <td>Str (K)</td>
  </tr>
  <tr>
    <td>Tackle</td>
    <td>Str + Brawl</td>
    <td>Normal</td>
    <td>+1</td>
    <td>Str +1 (K)</td>
  </tr>
  <tr>
    <td>Weapon Strike</td>
    <td>Dex + Melee</td>
    <td>Normal</td>
    <td>Normal</td>
    <td>Weapon</td>
  </tr>
</tbody>
</table>

<div class="thirdHeader" id="bite">Bite</div>
This maneuver is available only to vampires (or other supernatural creatures with sharp teeth, such as werewolves). A bite maneuver is a “combat” bite, intended to cause damage rather than drain blood. Bite damage is aggravated. To use a bite attack, the vampire must first perform a successful clinch, hold, or tackle maneuver (see below). On the turn following the successful attack, the player may declare the bite attempt and make a roll using the modifiers below.

Alternatively, a player can declare her vampire’s bite to be a “Kiss” attack. A Kiss is resolved in the same way as a normal bite, but inflicts no health levels of damage. Upon connecting with a Kiss, the vampire may begin to drain the victim’s blood at the normal rate, and the victim is typically helpless to resist. Following the Kiss, a vampire may, if she chooses, lick the puncture wound of the Kiss closed, thereby removing any evidence that she has fed.

* <b>Traits:</b> Dexterity + Brawl
* <b>Difficulty:</b> Normal
* <b>Accuracy:</b> +1
* <b>Damage:</b> Strength +1

<div class="thirdHeader" id="claw">Claw</div>
This attack is available to vampires with claws, such as those from the Protean power of Feral Claws or bone spurs constructed with the Vicissitude power of Bonecraft. A few other supernatural creatures, such as werewolves, also have claws. A claw attack inflicts aggravated damage (if Feral Claws) or lethal damage (if a Vicissitude-constructed weapon).

* <b>Traits:</b> Dexterity + Brawl
* <b>Difficulty:</b> Normal
* <b>Accuracy:</b> Normal
* <b>Damage:</b> Strength +1

<div class="thirdHeader" id="clinch">Clinch</div>
On a successful attack roll, the attacker goes into a clinch with the target. In the first turn, the attacker may roll Strength damage. In each subsequent turn, combatants act on their orders in the initiative. A combatant can inflict Strength damage automatically or attempt to escape the clinch. No other actions are allowed until one combatant breaks free. To escape a clinch, make a resisted Strength + Brawl roll against the opponent. If the escaping character has more successes, she breaks free; if not, the characters continue to grapple in the next turn.

* <b>Traits:</b> Strength + Brawl
* <b>Difficulty:</b> Normal
* <b>Accuracy:</b> Normal
* <b>Damage:</b> Strength

<div class="thirdHeader" id="disarm">Disarm</div>
To strike an opponent’s weapon, the attacker must make an attack roll at +1 difficulty. If successful, the attacker rolls damage normally. If successes rolled exceed the opponent’s Strength rating, the opponent takes no damage but is disarmed. A botch usually means the attacker drops her own weapon or is struck by her target’s weapon.

* <b>Traits:</b> Dexterity + Melee
* <b>Difficulty:</b> +1
* <b>Accuracy:</b> Normal
* <b>Damage:</b> Special

<div class="thirdHeader" id="hold">Hold</div>
This attack inflicts no damage, as the intent is to immobilize rather than injure the subject. On a successful roll, the attacker holds the target until the subject’s next action. At that time, both combatants roll resisted Strength + Brawl actions; the subject remains immobilized (able to take no other action) until she rolls more successes than the attacker does.

* <b>Traits:</b> Strength + Brawl
* <b>Difficulty:</b> Normal
* <b>Accuracy:</b> Normal
* <b>Damage:</b> Strength

<div class="thirdHeader" id="kick">Kick</div>
Kicks range from simple front kicks to aerial spins. The base attack is at +1 difficulty and inflicts the attacker’s Strength +1 in damage. These ratings may be modified further at the Storyteller’s discretion, increasing in damage and/or difficulty as the maneuver increases in complexity.

* <b>Traits:</b> Dexterity + Brawl
* <b>Difficulty:</b> +1
* <b>Accuracy:</b> Normal
* <b>Damage:</b> Strength +1

<div class="thirdHeader" id="staking">Stake</div>
To stake a vampire, an attacker must target the heart (difficulty 9). If the attack succeeds and inflicts at least three health levels of damage, the target is immobilized. An immobilized victim is conscious (and may use perception powers, such as those in the Auspex Discipline), but may not move or spend blood points.

* <b>Traits:</b> Dexterity + Melee
* <b>Difficulty:</b> 9
* <b>Accuracy:</b> Normal
* <b>Damage:</b> Strength +1

<div class="thirdHeader" id="strike">Strike</div>
The attacker lashes out with a fist. The base attack is a standard action and inflicts the character’s Strength in damage. The Storyteller may adjust the difficulty and/or damage depending on the type of punch: hook, jab, haymaker, karate strike.

* <b>Traits:</b> Dexterity + Brawl
* <b>Difficulty:</b> Normal
* <b>Accuracy:</b> Normal
* <b>Damage:</b> Strength

<div class="thirdHeader" id="sweep">Sweep</div>
The attacker uses her own legs to knock the legs out from under her opponent. The target takes Strength damage and must roll Dexterity + Athletics (difficulty 8) or suffer a <a href="#combat#maneuver-complications">knockdown</a>. The attacker can also use a staff, chain, or similar implement to perform a sweep. The effect is the same, although the target takes damage per the weapon type.

* <b>Traits:</b> Dexterity + Brawl/Melee
* <b>Difficulty:</b> +1
* <b>Accuracy:</b> Normal
* <b>Damage:</b> Strength; knockdown

<div class="thirdHeader" id="tackle">Tackle</div>
The attacker rushes her opponent, tackling him to the ground. The attack roll is at +1 difficulty, and the maneuver inflicts Strength +1 damage. Additionally, both combatants must roll Dexterity + Athletics (difficulty 7) or suffer a <a href="#combat#maneuver-complications">knockdown</a>. Even if the target’s Athletics roll succeeds, he is unbalanced, suffering +1 difficulty to his actions for the next turn.

* <b>Traits:</b> Strength + Brawl
* <b>Difficulty:</b> +1
* <b>Accuracy:</b> Normal
* <b>Damage:</b> Strength +1

<div class="secondHeader" id="ranged-combat">Ranged Combat Maneuvers</div>

<div class="thirdHeader" id="ranged-combat-table">Ranged Combat Maneuvers Table</div>

<table>
<thead>
  <tr>
    <th class="blue">Maneuver</th>
    <th class="blue">Traits</th>
    <th class="blue">Accuracy</th>
    <th class="blue">Difficulty</th>
    <th class="blue">Damage</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Automatic Fire</td>
    <td>Dex + Firearms</td>
    <td>+10</td>
    <td>+2</td>
    <td>Special</td>
  </tr>
  <tr>
    <td>Multiple Shots</td>
    <td>Dex + Firearms</td>
    <td>Special</td>
    <td>Normal</td>
    <td>Weapon</td>
  </tr>
  <tr>
    <td>Strafing</td>
    <td>Dex + Firearms</td>
    <td>+10</td>
    <td>+2</td>
    <td>Special</td>
  </tr>
  <tr>
    <td>3-Round Burst</td>
    <td>Dex + Firearms</td>
    <td>+2</td>
    <td>+1</td>
    <td>Weapon</td>
  </tr>
  <tr>
    <td>Two Weapons</td>
    <td>Dex + Firearms</td>
    <td>Normal</td>
    <td>+1/off-hand</td>
    <td>Weapon</td>
  </tr>
</tbody>
</table>

<div class="thirdHeader" id="aiming">Aiming</div>
The attacker adds one die to her attack dice pool on a single shot for each turn spent aiming. The maximum number of dice that can be added in this way is equal to the character’s Perception, and a character must have Firearms 1 or better to use this maneuver. A scope adds two more dice to the attacker’s pool in the first turn of aiming (in addition to those added for Perception). The attacker may do nothing but aim during this time. Additionally, it isn’t possible to aim at a target that is moving faster than a walk.

<div class="thirdHeader" id="automatic-fire" style="margin-top: 10px;">Automatic Fire</div>
The weapon unloads its entire ammunition clip in one attack against a single target. The attacker makes a single roll, adding 10 dice to her accuracy. However, the attack roll is at a +2 difficulty due to the weapon’s recoil. Extra successes add to the damage dice pool, which is still treated as equivalent to one bullet. An attacker using automatic fire may not target a specific area of the body. This attack is permissible only if the weapon’s clip is at least half-full to begin with.

* <b>Traits:</b> Dexterity + Firearms
* <b>Difficulty:</b> +2
* <b>Accuracy:</b> +10
* <b>Damage:</b> Special

<div class="thirdHeader" id="cover">Cover</div>
Cover increases an attacker’s difficulty to hit a target (and often the target’s ability to fire back). Difficulty penalties for hitting a target under various types of cover are listed below. A character who fires back from behind cover is also at something of a disadvantage to hit, as he exposes himself and ducks back under protection. Firearms attacks made by a defender who is under cover are at one lower difficulty than listed below. (If a listed difficulty is +1, then the defender suffers no penalty to make attacks from under that cover.) If your character hides behind a wall, attackers’ Firearms rolls have a +2 difficulty. Your character’s attacks staged from behind that wall are at +1 difficulty.

Note that difficulties for combatants who are both under cover are cumulative. If one combatant is prone and one is behind a wall, attacks staged by the prone character are at +2 difficulty, while attacks staged by the character behind the wall are also at +2 difficulty.

<table>
<thead>
  <tr>
    <th class="blue">Cover Type</th>
    <th class="blue">Difficulty Increase</th>
    <th class="blue">Accuracy</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>Light (lying prone)</td>
    <td>+1</td>
    <td>+10</td>
  </tr>
  <tr>
    <td>Good (behind wall)</td>
    <td>+2</td>
    <td>Special</td>
  </tr>
  <tr>
    <td>Superior (only head exposed)</td>
    <td>+3</td>
    <td>+10</td>
  </tr>
</tbody>
</table>

<div class="thirdHeader" id="multiple-shots">Multiple Shots</div>
The weapon unloads its entire ammunition clip in one attack against a single target. The attacker makes a single roll, adding 10 dice to her accuracy. However, the attack roll is at a +2 difficulty due to the weapon’s recoil. Extra successes add to the damage dice pool, which is still treated as equivalent to one bullet. An attacker using automatic fire may not target a specific area of the body. This attack is permissible only if the weapon’s clip is at least half-full to begin with.

* <b>Traits:</b> Dexterity + Firearms
* <b>Difficulty:</b> +2
* <b>Accuracy:</b> +10
* <b>Damage:</b> Special

<div class="thirdHeader" id="reloading">Reloading</div>
Reloading takes one full turn and requires the character’s concentration. Like any other maneuver, reloading can be performed as part of a multiple action.

<div class="thirdHeader" id="strafing" style="margin-top: 10px;">Strafing</div>
Instead of aiming at one target, fully-automatic weapons can be fired across an area. Strafing adds 10 dice to accuracy on a standard attack roll, and empties the clip. A maximum of three yards/meters can be covered with this maneuver. The attacker divides any successes gained on the attack roll evenly among all targets in the covered area (successes assigned to hit an individual are added to that target’s damage dice pool, as well). If only one target is within range or the area of effect, only half the successes affect him. The attacker then assigns any leftover successes as she desires. If fewer successes are rolled than there are targets, only one may be assigned per target until they are all allocated.

Dodge rolls against strafing are at +1 difficulty.

* <b>Traits:</b> Dexterity + Firearms
* <b>Difficulty:</b> +2
* <b>Accuracy:</b> +10
* <b>Damage:</b> Special

<div class="thirdHeader" id="three-round-burst">Three-Round Burst</div>
The attacker gains two additional dice on a single attack roll, and expends three shots from the weapon’s clip. Only certain weapons may perform this maneuver; see the <a href="#combat#ranged-weapons-chart">Ranged Weapons Chart</a> for particulars. Attacks are made at +1 difficulty due to recoil. As with automatic fire, the damage dice pool is based on one bullet from the weapon in question.

Dodge rolls against strafing are at +1 difficulty.

* <b>Traits:</b> Dexterity + Firearms
* <b>Difficulty:</b> +1
* <b>Accuracy:</b> +2
* <b>Damage:</b> Weapon type

<div class="thirdHeader" id="two-weapons">Two Weapons</div>
Firing two weapons is considered performing a multiple action, complete with dividing the dice of the lowest pool between two different targets. Additionally, the attacker suffers +1 difficulty for the attack with her off-hand (unless she’s ambidextrous). Each attack is rolled and resolved separately — multiple attacks made against the same target are covered by maneuvers such as “Automatic Fire” and “Three-Round Burst.”

Dodge rolls against strafing are at +1 difficulty.

* <b>Traits:</b> Dexterity + Firearms
* <b>Difficulty:</b> +1/off-hand
* <b>Accuracy:</b> Normal
* <b>Damage:</b> Weapon type

</div>
<div class= "blueWrapper" style="margin-top: -20px;">
<div class="whiteBlueBreak"> </div>
  <div class="footer" style="color: white; background-color: #384b7e;">
    La in Anarchy (LAiA) is not official World of Darkness material from White Wolf. Portions of this material are copyrights and trademarks of Paradox Interactive AB, and are used with permission. All rights reserved. For more information, please visit: <a href="https://worldofdarkness.com/">https://worldofdarkness.com/</a>
    <span style="margin-top: 10px;"> <img src='assets/darkPack.png' width="130px"> </span>
    </div>
</div>
