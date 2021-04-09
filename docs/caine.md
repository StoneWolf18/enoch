<div class="pageHero" style="background-image: url('assets/subpageCover.png')";>
  <div class="pageHeroHeader">
      Caine
  </div>
</div>

<div class = "container">

<input class ="toc" id="toggle" type="checkbox">
 <label class ="toc" for="toggle">Table of Contents</label>
 <div id="expand">
   <section class ="toc">
   <ul class="toc">
   <li><a class="toc" href="#caine#notes">Important Notes</a></li>
   <li><a class="toc" href="#caine#utility">Utility</a></li>
     <ul class="toc">
     <li><a class="toc" href="#caine#embrace">Embrace</a></li>
     </ul>
   <li><a class="toc" href="#caine#profiles">Profiles</a></li>
     <ul class="toc">
     <li><a class="toc" href="#caine#profile-create">Create</a></li>
     <li><a class="toc" href="#caine#profile-show">Show</a></li>
     <li><a class="toc" href="#caine#profile-delete">Delete</a></li>
     <li><a class="toc" href="#caine#profile-edit">Edit</a></li>
     </ul>
   <li><a class="toc" href="#caine#profile-type">Profile Type Change</a></li>
     <ul class="toc">
     <li><a class="toc" href="#caine#profile-ghoul">Ghoul</a></li>
     <li><a class="toc" href="#caine#profile-embrace">Embrace</a></li>
     </ul>
   <li><a class="toc" href="#caine#resource-gain">Resource Gain</a></li>
     <ul class="toc">
     <li><a class="toc" href="#caine#hunt">Hunt</a></li>
     <li><a class="toc" href="#caine#earn">Earn</a></li>
     <li><a class="toc" href="#caine#rest">Rest</a></li>
     </ul>
   <li><a class="toc" href="#caine#resource-spend">Resource Spend</a></li>
     <ul class="toc">
     <li><a class="toc" href="#caine#bp">Blood Points</a></li>
     <li><a class="toc" href="#caine#wp">Willpower</a></li>
     <li><a class="toc" href="#caine#xp">Experience</a></li>
     </ul>
   <li><a class="toc" href="#caine#damage-tracking">Damage Tracking</a></li>
     <ul class="toc">
     <li><a class="toc" href="#caine#damage-take">Take</a></li>
     <li><a class="toc" href="#caine#damage-heal">Heal</a></li>
     </ul>
   <li><a class="toc" href="#caine#dice">Dice</a></li>
     <ul class="toc">
     <li><a class="toc" href="#caine#roll">Roll</a></li>
       <ul class="toc">
       <li><a class="toc" href="#caine#dice-conditions">Conditions</a></li>
       </ul>
     <li><a class="toc" href="#caine#init">Init</a></li>
     <li><a class="toc" href="#caine#custom">Custom Roll</a></li>
       <ul class="toc">
       <li><a class="toc" href="#caine#group-init">Group Initiative</a></li>
       </ul>
     <li><a class="toc" href="#caine#repeat">Repeat</a></li>
     </ul>
   <li><a class="toc" href="#caine#scene-management">Scene Management</a></li>
     <ul class="toc">
     <li><a class="toc" href="#caine#scene-start">Start</a></li>
     <li><a class="toc" href="#caine#scene-end">End</a></li>
     </ul>
   <li><a class="toc" href="#caine#mod-mail">Mod Mail</a></li>
     <ul class="toc">
     <li><a class="toc" href="#caine#mail-update">Update</a></li>
     <li><a class="toc" href="#caine#mail-request">Scene Request</a></li>
     </ul>
   <li><a class="toc" href="#caine#search">Search</a></li>
     <ul class="toc">
     <li><a class="toc" href="#caine#merits-flaws">Merits/Flaws</a></li>
     </ul>
   </ul>
   <li><a class="toc" href="#caine#misc">Miscellaneous</a></li>
     <ul class="toc">
     <li><a class="toc" href="#caine#sheet-submission">Sheet Submission</a></li>
     <li><a class="toc" href="#caine#weekly-xp">Weekly Experience</a></li>
     <li><a class="toc" href="#caine#reactions">Emoji Reactions</a></li>
     </ul>
   </ul>
   </section>
 </div>

<div class="leftHeader" id="important-notes">Important Notes</div>

* <b>Any profile name with more than one word will require "quotation marks" around the name to function properly</b>
* Any command prompting a response has a time limit of 2 minutes. Once it ends, you'll need to run the command again.
* Using a command without anything else (such as `v.profile`) will produce a help message. Help messages can also be viewed by using `v.help NAME`, with NAME being the name of the command/set of commands you want to view (like `v.help roll`).
* If you run into problems, such as needing to change something on a profile, or a command not working, please ping Stone so she can help you!

<div class="leftHeader" id="utility">Utility</div>

<div class="secondHeader" id="embrace">Embrace</div>

* <b>Default Command:</b> `v.embrace`
* <b>Alternate Name:</b> None
* <b>Parameters</b> Name

Embrace (`v.embrace`) assigns the named role in for a colored username.

<b>Name</b> is the name of a role listed in #rules-and-more.

<b><em>Example - Assigning yourself the Toreador role</em></b>

`v.embrace Toreador`

<div class="leftHeader" id="profiles">Profiles</div>
Profiles are the custom method we use to track individual character information, like blood points and experience. Once a character is approved, a profile <em>must</em> be created for them before they can be used in scenes.

Because everyone needs to be using a profile for all of their characters, <b>names are not case sensitive</b>. This means no one would be able to have a character named 'Caine' and 'caine'. Of course, full names such as "John Smith" and "John Grey" are considered different.

Note that <b>all</b> of the commands listed below are subcommands of profile. This means all of them will require `v.profile` or `v.p` before them to function.

<div class="yourAttentionPlease">

<b>Important</b>

Character names with more than one word will require "quotation marks" around to function properly.

</div>

<div class="secondHeader" id="profile-create">Create</div>

* <b>Default Command:</b> `v.profile create`
* <b>Alternate Name:</b> `v.p create`
* <b>Parameters:</b> None

Unlike other commands, this command requires <b>nothing else</b> to be added when using it. You will be asked for the information required. Please have your character description (found in #getting-started) copied so it can be pasted when prompted.

<div class="secondHeader" id="profile-show">Show</div>

* <b>Default Command:</b> `v.profile show`
* <b>Alternate Name:</b> `v.p show`
* <b>Parameters</b> Name

Show (`v.p show`) displays an already existing profile.

<b>Name</b> is the name of the character you're wanting to view.

<b><em>Example - Viewing John Smith's profile</em></b>

`v.p show "John Smith"`

<div class="secondHeader" id="profile-delete">Delete</div>

* <b>Default Command:</b> `v.profile delete`
* <b>Alternate Name:</b> `v.p delete`
* <b>Parameters</b> Name

Delete (`v.p delete`) deletes and existing profile you own. <b>This is irreversible.</b>

<b>Name</b> is the name of the character you're wanting to delete.

<b><em>Example - Deleting John Smith's profile</em></b>

`v.p delete "John Smith"`


<div class="secondHeader" id="profile-edit">Edit</div>

* <b>Default Command:</b> `v.profile edit`
* <b>Alternate Name:</b> `v.p edit`
* <b>Parameters</b> Field, Name, Value

Edit (`v.p edit`) displays an already existing profile.

<b>Field</b> is the part of the profile you want to edit. The only editable fields are the image (`v.p edit img`) and description (`v.p edit desc`). <br>
<b>Name</b> is the name of the character you're wanting to edit. <br>
<b>Value</b> is what you're going to be replacing the field's current content with. <br>

<b><em>Example - Editing John Smith's image</em></b>

`v.p edit img "John Smith" https://example.com/img.png`

<div class="yourAttentionPlease">

<b>What if I need to change something else?</b>

Ping Stone if a different part (such as max willpower) needs to be changed and she'll get it done for you!

</div>

<div class="leftHeader" id="profile-type">Profile Type Change</div>

<div class="secondHeader" id="profile-ghoul">Ghoul</div>

* <b>Default Command:</b> `v.profile ghoul`
* <b>Alternate Name:</b> `v.p ghoul`
* <b>Parameters</b> Name

Ghoul (`v.p ghoul`) makes a human profile a ghoul, tracking a small blood pool based on their Stamina.

<b>Name</b> is the name of the character you're wanting to ghoul.

<b><em>Example - Ghouling a profile for John Smith</em></b>

`v.p ghoul "John Smith"`

<div class="secondHeader" id="profile-embrace">Embrace</div>

* <b>Default Command:</b> `v.profile ghoul`
* <b>Alternate Name:</b> `v.p ghoul`
* <b>Parameters</b> Name

The <em>subcommand</em> Embrace (not the <a href="#caine#embrace">utility command</a>) (`v.p embrace`) makes a human or ghoul profile a vampire, tracking a full blood pool based on their generation.

<b>Name</b> is the name of the character you're wanting to embrace.

<b><em>Example - Embracing a profile for John Smith</em></b>

`v.p embrace "John Smith"`

<div class="leftHeader" id="resource-gain">Resource Gain</div>

<div class="secondHeader" id="hunt">Hunt</div>

* <b>Default Command:</b> `v.hunt`
* <b>Alternate Name:</b> None
* <b>Parameters</b> Name, Amount, Method

Hunt (`v.hunt`) adds the specified Amount of blood points to the named profile's blood pool, and tracks the amount and Method in #hunting-log.

<b><em>Example - Adding 3 BP to John Smith's profile after hunting successfully Downtown</em></b>

`v.hunt "John Smith" 3 smooth talker downtown`

<div class="yourAttentionPlease">

<b>Important</b>

A hunting roll must be made before blood points can be added. See <a href="#hunting">the hunting page</a> for more details.

</div>

<div class="secondHeader" id="earn">Earn</div>

* <b>Default Command:</b> `v.earn`
* <b>Alternate Name:</b> None
* <b>Parameters</b> Name, Amount, Reason

Earn (`v.earn`) adds the specified Amount of experience to the named profile's total.

<b><em>Example - Adding 2 XP to John Smith's profile after participating in an event</em></b>

`v.earn "John Smith" 2 event reward`

<div class="secondHeader" id="rest">Rest</div>

* <b>Default Command:</b> `v.rest`
* <b>Alternate Name:</b> None
* <b>Parameters</b> Name, Amount

Rest (`v.rest`) adds the specified Amount of willpower to the named profile's current willpower total.

<b><em>Example - Adding 1 WP to John Smith's profile</em></b>

`v.rest "John Smith" 1`

<div class="leftHeader" id="resource-spend">Resource Spend</div>
Spend (`v.spend`) allows for easy tracking of all three resources (blood points, willpower, and experience).

Note that <b>all</b> of the commands listed below are subcommands of spend. This means all of them will require `v.spend` before them to function.

<div class="secondHeader" id="bp">Blood Points</div>

* <b>Default Command:</b> `v.spend bp`
* <b>Alternate Name:</b> None
* <b>Parameters</b> Name, Amount, Reason

BP (`v.spend bp`) spends the Amount of the named profile's blood points, recording the loss and reason for it in #expenditures.

<b><em>Example - Spending 2 of John Smith's blood points to increase his strength</em></b>

`v.spend bp "John Smith" 2 blood buffing strength to 3`

<div class="secondHeader" id="wp">Willpower</div>

* <b>Default Command:</b> `v.spend wp`
* <b>Alternate Name:</b> None
* <b>Parameters</b> Name, Amount, Reason

WP (`v.spend wp`) spends the Amount of the named profile's willpower, recording the loss and reason for it in #expenditures.

<b><em>Example - Spending 1 of John Smith's willpower points on a hunting roll</em></b>

`v.spend wp "John Smith" 1 hunting downtown`

<div class="secondHeader" id="xp">Experience</div>

* <b>Default Command:</b> `v.spend xp`
* <b>Alternate Name:</b> None
* <b>Parameters</b> Name, Amount, Reason

XP (`v.spend wp`) spends the Amount of the named profile's experience, recording the loss and reason for it in #expenditures.

<b><em>Example - Spending 3 of John Smith's experience to take the first dot in Science</em></b>

`v.spend xp "John Smith" 3 increasing science to 1`

<div class="yourAttentionPlease">

<b>Important</b>

All experience purchases must be approved before hand before they're to be taken. See <a href="#caine#update-request">the request command</a> for more.

</div>

<div class="leftHeader" id="damage-tracking">Damage Tracking</div>
Damage (`v.damge`) is how all of the health tracks on the bottom of each character profile are edited. Characters with the merit Huge Size will automatically have the additional level added as long as it's specified in the profile description.

Note that <b>both</b> of the commands listed below are subcommands of damage. This means all of them will require `v.damage` before them to function.

<div class="secondHeader" id="damage-take">Take</div>

* <b>Default Command:</b> `v.damage take`
* <b>Alternate Name:</b> None
* <b>Parameters</b> Name, Amount, Type

Take (`v.damage take`) applies the Amount of damage of the given Type (bashing, lethal, or aggravated) to the named profile. Only one damage type can be applied at a time.

<b><em>Example - John Smith taking 3 bashing damage</em></b>

`v.damage take "John Smith" 3 bashing`

<div class="secondHeader" id="damage-heal">Heal</div>

* <b>Default Command:</b> `v.damage heal`
* <b>Alternate Name:</b> None
* <b>Parameters</b> Name, Amount

Heal (`v.damage heal`) heals the Amount of damage of the named profile, starting with the lowest type taken if applicable.

<b><em>Example - John Smith healing 1 level of damage</em></b>

`v.damage heal "John Smith" 1`

<div class="leftHeader" id="dice">Dice</div>

<div class="secondHeader" id="roll">Roll</div>

* <b>Default Command:</b>  `v.roll`
* <b>Alternate Name:</b>  `v.r`
* <b>Parameters:</b>  Pool, Difficulty, Comment (OPTIONAL)

Roll (`v.roll`) is the standard rolling method for V20: a pool of dice against a set difficulty.

<u>Pool</u> is the amount of dice you're rolling.  
<u>Difficulty</u> is the difficulty of the roll.  
<u>Comment</u> is to add text and conditions to the roll.

<b><em>Example - Rolling a pool of 5 versus a difficulty of 6</em></b>

`v.roll 5 6`

<div class="thirdHeader" id="dice-conditions">Conditions</div>

Conditions are words you can include in your comment to change how your roll is calculated.

The following conditions are currently supported. None of them are case sensitive:

* <b>Spec OR Specialty:</b> Roll with a specialty (all 10s count as 2 successes)
  * <u>Example:</u> `v.roll 5 6 spec` | `v.roll 5 6 specialty`
* <b>Wp OR Willpower:</b> Roll with willpower for an automatic success.
  * <u>Example:</u> `v.roll 5 6 wp` | `v.roll 5 6 willpower`
* <b>Auto AMOUNT:</b> Add AMOUNT number of automatic successes to your roll.
  * <u>Example:</u> `v.roll 5 6 auto 3`
* <b>Double:</b> Double the number of successes rolled.
  * <u>Example:</u> `v.roll 5 6 double`
* <b>Ignore:</b> Ignore botches if one is rolled.
  * <u>Example:</u> `v.roll 5 6 ignore`
* <b>Ovr OR Override:</b> Override the rule that subtracts 1s from successes rolled.
  * <u>Example:</u> `v.roll 5 6 ovr`

Conditions can be combined should it be necessary for the roll.

<b><em>Example - Rolling with potence 2 and a boxing specialty</em></b>

`v.roll 5 6 spec boxing auto 2`

<b><em>Example - Rolling attack damage with potence 2</em></b>

`v.roll 3 6 punch auto 2 ignore`

<div class="secondHeader" id="init">Init</div>

* <b>Default Command:</b> `v.init`
* <b>Alternate Name:</b> `v.i`
* <b>arameters:</b> Rating, Comment (OPTIONAL)

Init (`v.init`) rolls initiative for old World of Darkness systems: a d10 + the value given.

<u>Rating</u> is your initiative rating. This is normally Dexterity + Wits, though other traits could be added depending upon the specific game.

<b><em>Example - Rolling initiative with an initiative rating of 5</em></b>

`m.init 5`

<div class="secondHeader" id="custom">Custom Roll</div>

* <b>Default Command:</b>`v.customRoll`
* <b>Alternate Name:</b> `v.cr`
* <b>Parameters:</b> Amount, Faces, Comment (OPTIONAL)

customRoll (`v.customRoll`) allows for the rolling of dice that aren't d10s against a given difficulty.

<u>Amount</u> is how many dice you want to roll.  
<u>Faces</u> are how many faces/sides the dice have.

<b><em>Example - Rolling 5d6:</em></b>
`v.customRoll 5 6`

<b><em>Example - Rolling 1d20:</em></b>
`v.cr 1 20`

<div class="secondHeader" id="repeat">Repeat</div>

* <b>Default Command:</b> `v.repeat`
* <b>Alternate Name:</b> `v.re`
* <b>Parameters:</b> Times, Roll

Repeat (`v.repeat`) allows iterative rolling, that is: making the same roll more than once in a single command.

<u>Times</u> is how many times you want to make the roll.  
<u>Roll</u> is the actual roll you're making <b>without</b> the prefix. (`v.`)

<b><em>Example - Rolling a pool of 6 dice with a difficulty of 7 four times</em></b>

`v.repeat 4 roll 6 7`

<b><em>Example - Rolling a pool of 5 dice with a difficulty of 4 with specialty twice</em></b>

`v.re 2 roll 5 4 spec`

<b><em>Example - Rolling 4d8 three times</em></b>

`v.repeat 3 customRoll 4 8`

<div class="thirdHeader" id="group-init">Group Initiative</div>
Group initiatives are rolled differently, as each character will have a different name and rating. You <b>must</b> provide name and rating pairings equal to NUMBER for this command to function. The names and ratings must also follow that order, with nothing separating them.

<b>Command:</b> `v.repeat NUMBER init NAME RATING NAME RATING`

<u>Number</u> is how many are in the group you are rolling for.  
<u>Name</u> is the name of a character.  
<u>Rating</u>is the character's initiative rating.  

You are unable to add text comments to group initiatives because of how they are processed.

<b><em>Example - rolling for a group of three characters, the first with a rating of 3, the second with a rating of 5, and the third with a rating of 4</em></b>

`v.repeat 3 init Brujah 3 Toreador 5 Ventrue 4`

<div class="leftHeader" id="scene-management">Scene Management</div>
All scenes take place in a channel created specifically for it, and are archived once they end for ease of reference.

The start and end commands are completely separate from one another. This means that, if for some reason the channel doesn't end up in the correct category, it can be moved freely to the right spot.

Note that <b>both</b> of the commands listed below are subcommands of scene. This means all of them will require `v.scene` before them to function.

<div class="secondHeader" id="scene-start">Start</div>

* <b>Default Command:</b> `v.scene start`
* <b>Alternate Name:</b> None
* <b>Parameters</b> Name

Start (`v.scene start`) creates a channel by the Name given, and asks the user for both a location (Downtown, Inner City, Hollywood, Outskirts) and description. Descriptions should include the date and time of the scene at bare minimum.

<b><em>Example - Creating a scene titled 'New in Town'</em></b>

`v.scene start new in town`

<div class="secondHeader" id="scene-end">End</div>

* <b>Default Command:</b> `v.scene end`
* <b>Alternate Name:</b> None
* <b>Parameters</b> Name

End (`v.scene end`) takes all of the messages inside the scene channel and puts them into the location's respective archive channel. The link outputted is to be used to record the scene in the #scene-log for ease of reference later.

While a scene is being archived, all pings will give a new alert. They intentionally haven't been stripped from messages to allow for them to be easily distinguishable.

<b><em>Example - Creating a scene titled 'New in Town'</em></b>

`v.scene start new in town`

<div class="leftHeader" id="mod-mail">Mod Mail</div>
Mail allows you to send certain types of messages directly to the Storyteller and assistants.

<b>Both</b> of the commands below must be used directly in Caine's DMs to function. Sending them in the server, such as in #bot-spam, won't work.

Additionally, <b>both</b> of the commands listed below are subcommands of mail. This means all of them will require `v.mail` before them to function.

<div class="secondHeader" id="mail-update">Update</div>

* <b>Default Command:</b> `v.mail update`
* <b>Alternate Name:</b> None
* <b>Parameters</b> Request

Update (`v.mail update`) sends the given experience expenditure Request to the Storytellers for approval. If approved, you'll then be able to spend experience as seen under <a href="#caine#xp">`v.spend xp`</a>.

<div class="secondHeader" id="mail-request">Scene Request</div>

* <b>Default Command:</b> `v.mail request`
* <b>Alternate Name:</b> None
* <b>Parameters</b> Request

Request (`v.mail request`) sends the given scene Request to the Storytellers. If it's a scene they'd want to run, they'll get

<div class="leftHeader" id="search">Search</div>

Search lets you search for merits, flaws, disciplines, and systems by name.

Note that <b>all</b> of the commands listed below are subcommands of mail. This means all of them will require `v.search` before them to function.

<div class="yourAttentionPlease">

<b>Important</b>

At this time, only merits/flaws are searchable.

</div>

<div class="secondHeader" id="merits-flaws">Merits/Flaws</div>

* <b>Default Command:</b> `v.search merit or flaw`
* <b>Alternate Name:</b> None
* <b>Parameters</b> Name

Merit/Flaw (`v.search merit` OR `v.search flaw`) pulls information directly from our merits and flaws directory. The description, type, availability, learnabiltiy, and source are all display.

<div class="leftHeader" id="misc">Miscellaneous</div>

Below are a collection of functions that Caine has, but aren't explicitly commands themselves.

<div class="secondHeader" id="sheet-submission">Sheet Submission</div>

To submit a character sheet, the google drive share link has to be DM'd to Caine directly. Nothing else is required for this to work. You should receive a confirmation message if it went through.

<div class="secondHeader" id="weekly-xp">Weekly Experience</div>

All active characters (characters who had been played at least once during a scene) are given 2 experience every Sunday at 23:45 UTC. Characters <b>must</b> have a profile to earn experience this way.

<div class="secondHeader" id="reactions">Emoji Reactions</div>

React to a message with 💾 (a floppy disk) to save it in the #quote-book. Currently, this only works on messages sent by actual users, not proxies (tuppers).

</div>

<div class= blueWrapper>
  <div class=whiteBlueBreak> </div>
  <div class="footer" style="color: white; background-color: #384b7e;">
    La in Anarchy (LAiA) is not official World of Darkness material from White Wolf. Portions of this material are copyrights and trademarks of Paradox Interactive AB, and are used with permission. All rights reserved. For more information, please visit: <a href="https://worldofdarkness.com/">https://worldofdarkness.com/</a>
    <span style="margin-top: 10px;"> <img src='assets/darkPack.png' width="130px"> </span>
    </div>
</div>
