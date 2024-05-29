---
redirect_from:
  - /kotor1/Route Guides/Any NMG
---
# Star Wars: Knights of the Old Republic - Any% No Major Glitches Guide

### v4.3: Male/Female Scout -> Jedi Guardian Route (Light Side)

This route defeats Malak on the Star Forge as fast as possible without major glitches.  Timing begins upon clicking "PLAY" after character creation and ends when the screen cuts to black at the start of the Malak Death cutscene. A load-removal tool and auto-splitter is available for LiveSplit thanks to [glasnonck](https://www.speedrun.com/users/glasnonck) and [XeroHR](https://www.speedrun.com/users/XeroHR) (results may vary for Windows 11 users); times are sorted based on load-removed times, since load times vary significantly in this game, and saving is frequent.   This guide will cover the character build for the run, as well as a detailed route.

If you have additional questions, you can check out the [KotOR Speedrunning Discord](http://discord.gg/Q2uPRVu) which is linked on the game's sidebar on speedrun.com.  There's a bunch of friendly folks there willing to answer questions!

**Table of Contents:**
- [NMG Ruleset](#nmg-ruleset)
- [Character Build](#character-build)
  - [Character Creation](#character-creation)
  - [Leveling Plan](#leveling-plan)
- [Equipment Plan](#equipment-plan)
- [Credit Route](#credit-route)
- [Alignment Route](#alignment-route)
- [Route Overview](#route-overview)
- [Detailed Route](#detailed-route)
- [Version History](#version-history)

## NMG Ruleset

**REMEMBER to show yourself restarting the game at the beginning of each attempt.**

The Any% No Major Glitches (NMG) run is a middle-ground category between [Any% Unrestricted](hmjxg) and [Any% Glitchless](xaobq).  

The following glitches and tricks are banned in Any% NMG:
- [Fake Level Up](<../Major Glitches/Fake Level Up>)
- [Menu Glitch](<../Major Glitches/Anywhere Menu Glitch>) including AMG
- [Fast Lane](<../Major Glitches/Fast Lane>)
- All varieties of [Hotshot](<../Major Glitches/Hotshot>)
- [Full Inventory Duping](<../Major Glitches/Item Duplication#full-inventory-duplication>)
- [Door Clipping](<../Major Glitches/Door Clipping>)
*Note:* [Door Clipping](<../Major Glitches/Door Clipping>) includes [GP Warps](<../Techniques/GP Warp#buffered-gp-warps>) that [bypass locked doors](<../Major Glitches/Door Clipping#gather-party-warp-clips>).

These glitches and tricks are allowed:
- [Save Buffers](<../Techniques/Save Buffering>) of all types
- [Save Teleports](<../Techniques/Save Teleporting>)
- [Map CS Skips](<../Techniques/Map Cutscene Skips>)
- [Combat Talking](<../Techniques/Combat Talking>)
- [Force Skips](<../Techniques/Force Skips>)
- [Wired Targeting](<../Techniques/Wired Targeting>)
- [Single Item Duping](<../Techniques/Item Duplication#single-item-duplication>)
- [Damage Stacking](<../Techniques/Damage Stacking>)
- [GP Warps](<../Techniques/GP Warp#buffered-gp-warps>) that do not bypass locked doors.

## Character Build

### Character Creation

We begin as a Scout; this guide as written can be completed as either a Male or Female character, but Male has the small advantage of an easier time sparing Bastila on the Star Forge with successful Persuade checks.  

Scout is used because it is guaranteed an Adrenal Alacrity in the initial footlocker on Endar Spire, which saves 12 seconds by enabling us to run faster earlier on Taris, and skip shopping with Zelka.  On becoming a Jedi we'll choose the Jedi Guardian class for maximum attack power, the Force Jump feat, and since we no longer need any skill points.

**Initial Attributes:**
* Str - 18
* Dex - 14
* Con - 14
* Int - 10
* Wis - 8
* Cha - 8

**Initial Skills:**
* Computer Use - 4
* Security - 1
* Treat Injury - 4
* Save 2 points

**Initial Feat** - Weapon Focus: Melee Weapons

We are going to focus on melee attacks with a lightsaber, so we max out Strength immediately, and get enough Dexterity and Constitution to help us survive.  The final two points are put into Intelligence; that plus the 4 points in Computer Use saves us 1 computer spike for every hacking action, which is essential for our spike route on Taris.

Besides Computer Use, Treat Injury (TI) will be our secondary skill, with Persuade the main skill; however since Persuade is not a Class Skill for Scouts, we'll save points to put into Persuade once we become a Jedi.  The point in Security is for a door on the Endar Spire and serves no other purpose, but does save a few seconds.

We choose Weapon Focus: Melee for the attack boost on Taris, in particular the fights in the Sith Base.  We choose it over Two-Weapon Fighting because it takes longer to select, so at level 2 it's faster to pick Two-Weapon Fighting.  Since character creation isn't timed, this is optimal.

### Leveling Plan

| Level | Feats | Powers | Skills |
| --- | :--- | :--- | :--- |
| 1 | Weapon Focus: Melee Weapons, *Flurry* | | Com to 4, Sec to 1, TI to 4, Save 2 |
| 2 | Two-Weapon Fighting | | Save All |
| 3 | Empathy | | TI to 6, Save Rest |
| 4 | Improved Two-Weapon Fighting | Burst of Speed, Force Valor | Save All |
| 5 | | Affect Mind | Save All |
| 6 | Improved Flurry | Dominate Mind | Per to 9 |
| 7 | | Stun Droid | Per to 10 |
| 8 | | Disable Droid | Per to 11 |
| 9 | Master Two-Weapon Fighting | Knight Speed | Per to 12 |
| 10 | Master Flurry | Knight Valor | Per to 13 |

Our main combat plan is lots of Strength, Master Two-Weapon Fighting, Master Flurry, and Knight Speed, using Bastila's Double-bladed Lightsaber as our main weapon.  This gives us multiple attacks that will deal as much damage as possible; we need as many attacks as we can get, since our chance to hit will be relatively low.  We are not guaranteed to hit level 11 in the run, but if we do it's best to just Auto-Level to get the +1 Attack bonus; we don't really need any additional skills or Force Powers at that point.  Other notes:

**Skill notes:**
- After the initial 4 points in Computer Use, we don't put any additional points in.  We would need to reach 8 to save additional spikes, and we don't have the skill points to spare.
- We need Persuade for four conversations:
  1. On Dantooine, we must Persuade Juhani to return to the Jedi.
  2. On Korriban, we must Persuade Shaardan to spare the hopefuls for Light Side points (LSP).
  3. On Korriban, we must Persuade Yuthura to allow us to enter the academy.
  4. On Korriban, we must Persuade Kel Alghwin to disclose his doubts to us.
- The rest is put into Treat Injury to make our medpac use more efficient.

**Feat notes:**
- Weapon Focus: Melee Weapons only gives us an attack boost on Taris, but that's where most of our fighting occurs, so it's a worthwhile feat to take.
- Empathy is chosen since there aren't other good feats at level 3, and it gives +1 to TI and +1 to Persuade, our two most important skills.
- Flurry and Two-Weapon Fighting are our main combat core.

**Force Power notes:**
- Force Speed is the most important Force power, giving double movement speed, although [Save Teleports](<../Techniques/Save Teleporting>) are eventually the fastest form of movement.  Knight Speed also grants +1 attack per round, which is highly important due to our relatively low chance to hit.
- Force Valor is used on Korriban to increase chances of a successful Persuade on Yuthura, as well as to boost stats for as many fights as possible.  Knight Valor also gives us Immunity: Poison, which protects against Affliction and Plague on the Star Forge.
- Disable Droid is used to free the Captured Jedi during the Malak fight at the end of the game.  This denies them to Malak, meaning you only have to kill him twice.  It also fills up your Force Points as well, though not your health.
- Affect and Dominate Mind are used for the following:
  1. Avoiding landing fees on Manaan, Tatooine, and Kashyyyk.
  2. Persuading Lashowe to assist us in finding the holocron.
  3. Persuading the Czerka guards in the Upper Shadowlands to give up the emitter codes.

## Equipment Plan

**Implant: None**
- While we used to use the Nerve Enhancement Package for Immunity: Mind-Affecting, skipping Zelka means it's more convenient to nab the Nerve Amplifier Belt for that purpose.  The other implants we obtain are sold for significant and important credits.

**Head: Verpine Headband** - Found on Dantooine, Casus Sandral's corpse
- This is the most convenient mask to grab, giving +3 to our Will save, which is our weakest.

**Gloves: Strength Enhancer** - Found on Taris, Sith Governor's corpse
- This is used for the +1 Strength; from levels 4 through 7, it nets us an extra +1 modifier, which helps for the fight against Lashowe.

**Body: Jedi Knight Robe** - Found on Dantooine, Nemo's remains
- We want to wear robes to allow us to cast our Force powers, and this is the most convenient robe to grab, since we loot Nemo anyway for the Sigil crystal.

**Weapon: Double-bladed Lightsaber** - Found on Taris, Brejik's "corpse"
- We borrow Bastila's lightsaber for the run (and probably give it back afterwards).  The crystals we use are as follows:
  - Sigil Crystal: Placed after Tatooine, used for +1 Attack
  - Opila Crystal: The only other convenient crystal on our route.  The damage boost and massive critical hits makes it worthwhile.  Placed after Tatooine.
  - Solari Crystal: The best crystal in the game and the reason we try to stay Light-aligned (see below).  Replaces Opila after Korriban.

**Belt: Nerve Amplifier Belt** - Found on Tatooine, Chewed Twi'lek corpse
- Skipping the CNS belt streamlines the credit route and lets us skip the strongbox in the Vulkar Garage, saving about a minute at the expense of slightly worse combat.  The Nerve Amplifier Belt is a convenient replacement that preserves Immunity: Mind-Affecting and lets us skip Zelka on Taris for a little further timesave.

All of our equipment should be equipped once we leave Tatooine, with the exception of the Solari crystal which is placed after Korriban.  We'll also use the Combat Suit, Prototype Vibroblade and a basic Vibroblade while on Taris.

## Credit Route

By skipping the CNS Strength Enhancer, we can concentrate all of our shopping into 3 to 5 trips, depending on how many safe strats we decide to use:

**1. Larrim on Taris**
- Sell: Nonessential items to reach ~1182 Credits
- Buy: 2 Concussion Grenades, 1 Frag Grenade, 1 Battle Stimulant (374 Credits)

**2. Zelka on Taris**
- ***Optional***: Buy 3x Adrenal Alacrity (150 Credits)

**3. Selkath Merchant on Manaan**
- Buy: Advanced Medpac, Hyper Battle Stimulant, Hyper Adrenal Strength (380 Credits total)
- Buy: Hyper Adrenal Alacrity **only** if you did not shop with Zelka (100 Credits)
- ***Optional:*** Buy a second Hyper Battle Stimulant and second Hyper Adrenal Strength if you are *not* doing Krayt Skip (300 Credits)

**4. Mic'Tunan'Jus Orgu on Tatooine**
- ***Optional***: Buy Bantha Fodder **only** if you are *not* doing Krayt Skip (1 Credit)

**5. Czerka Shop on Korriban**
- Sell: Nonessential items to reach ~4200 Credits
- Buy: 20x Advanced Medpac, 5x Echani Battle Stimulant, 5x All Hyper Adrenal Stims (4100 Credits total)

Our credits all come from selling items we don't need, though we do loot some extra corpses to be able to afford all the stims we want on Korriban. The Selkath Merchant on Manaan is useful for the Adrenal Alacrity for the underwater segment, since we would normally skip Zelka.  The other stims are for the second phase of Leviathan Malak and the Sand People fight (if not doing Krayt Skip).

## Alignment Route

Alignment in KotOR is a sliding scale from 0 to 100, initialized at 50; higher numbers are Light, lower numbers are dark.  Shifts in alignment are determined by a matrix; every alignment-shifting action is classified as Light or Dark, and then assigned a level (either Low, Mid, or High).  The player character (Revan) can either be aligned as Very Dark, Dark, Neutral, Light, or Very Light.  The more opposed your alignment and the action's classification, the more drastic your shift in alignment; for example, a Light-aligned character performing a High Dark action will have a large shift, while a Dark character performing a High Dark action will have a smaller shift.

Here is the alignment route used in the run:

| Aligned | Action | Type | Delta | New |
| --- | :--- | :--- | --- | --- |
| Neutral | Game Start | -- | 50 | 50 |
| Neutral | Rescue merchant from bounty hunters | Low Light | +2 | 52 |
| Neutral | Give merchant credits to pay his debt | Mid Light | +4 | 56 |
| Neutral | Save the alien informant | Low Light | +2 | 58 |
| Neutral | Agree to kill Gadon Thek | Low Dark | -2 | 56 |
| Neutral | Threaten Janice Nall to get T3-M4 | Mid Dark | -4 | 52 |
| Neutral | Tell Shaardan not to kill the hopefuls | Low Light | +2 | 54 |
| Neutral | Try to Persuade Shaardan to spare the hopefuls | Low Light | +2 | 56 |
| Neutral | Succeed in Persuading Shaardan | Hardcoded | +3 | 59 |
| Neutral | Persuade Yuthura to admit you to the academy | Low Dark | -2 | 57 |
| Neutral | Persuade Sith Thugs to leave you alone | Mid Light | +4 | 61 |
| Light | Snitch on Kel Algwinn to Uthar Wynn | Hardcoded | -5 | 56 |
| Neutral | Spare Yuthura Ban | Mid Light | +4 | 60 |
| Light |  | Low Light | +2 | 62 |
| Light | Stay true to the Light Side on Lehon | High Light | 4 | 66 |
| Light |  | Highest Light | 5 | 71 |

*Snitching on Kel Algwinn is for some reason hardcoded to always give -5 alignment; similarly, rescuing the hopefuls from Shaardan is hardcoded to give +3 alignment.*

There are two important points in this route:
1. We must be at 60 alignment or higher (the boundary between Neutral and Light) in order to equip any Light Side restricted equipment.  The Solari crystal is Light Side restricted, as well as being ridiculously good.  So we need to be at 60 alignment by the time we place the Solari Crystal (after Korriban) and stay there in order to keep our lightsaber equipped.

2. When Persuading Yuthura to allow us access to the Sith Academy, if we are at 61 or more alignment we will have a Persuade/Lie option in addition to the normal Persuade option.  The Persuade option is a Low Dark action and loses alignment, while Persuade/Lie is a neutral action.  While we used to try to reach 61 alignment before here, we use the Mid Light action of Persuading the Sith Thugs to counteract the Low Dark action of Persuading Yuthura genuinely.

However, wanting to equip the Solari crystal means we want to do mostly light side actions. Hence each dark side action we take is done for a specific and very good reason:
- Agreeing to kill Gadon Thek teleports you to entrance to the Vulkar Base, saving the 45 seconds it takes to run out of the base.
- Threatening Janice Nall to get T3 is the only way to obtain him, because we don't have the 2000 credits (and wouldn't want to spend them if we did).
- Persuading Yuthura is the fastest way into the Sith Academy (see above).
- Snitching on Kel Algwinn is part of the fastest way to gain the 5 necessary Prestige points on Korriban, and saves at least a minute over the next fastest option.

While we used to kill Freyyr in the Lower Shadowlands to enable a [Map CS Skip](<../Techniques/Map Cutscene Skips>) to reach the Ebon Hawk, we can avoid the fight and its associated DSP by simply [Save Teleporting](<../Techniques/Save Teleporting>) to the Wookiee Village and using a [Map CS Skip](<../Techniques/Map Cutscene Skips>) from there.  This saves time and alignment issues.

## Route Overview

This is a brief outline of the route for the Any% NMG run, including planet order and smaller skips:

1. **Taris**
  * Reach the Undercity and recruit Mission and Zaalbar to access Vulkar Base
  * Defense Turret Skip to access Vulkar Garage
  * Use Accelerator Warp to exit Vulkar Base
  * Skip the Brejik Fight to rescue Bastila 
  * Recruit T3 to access Sith Base
  * Kill the Sith Governor to get the Launch Codes
  * Steal the Ebon Hawk and escape Taris
2. **Dantooine**
  * Become a Jedi Padawan
  * Redeem Juhani to the light side
  * Find the Star Map in the ancient ruins
3. **Manaan**
  * Raid the Sith Base to recover the Data Module for the Republic
  * [Sonic Buffer](<../Techniques/Save Buffering#sonic-buffers>) to skip the Mother Firaxan
  * Find the Star Map on the ocean floor
4. **Tatooine**
  * [Save Teleport](<../Techniques/Save Teleporting>) into the Eastern Dune Sea
  * Kill the Krayt Dragon OR perform Krayt Skip to obtain the Star Map
5. **Korriban**
  * Inflitrate the Academy
  * Earn five prestige points with Uthar Wynn
  * Find the Star Map in Naga Sadow's Tomb
6. **Leviathan**
  * Rescue the crew using Mission
  * Skip the spacewalk sequence
  * Skip the Saul Karath fight
  * Defeat Darth Malak and escape
7. **Kashyyyk**
  * [Save Teleport](<../Techniques/Save Teleporting>) to skip visiting the Wookiee Village
  * Recruit Jolee Bindo to access Lower Shadowlands
  * Find the Star Map in the Lower Shadowlands
  * [Save Teleport](<../Techniques/Save Teleporting>) to the Wookiee Village to Return to the Ebon Hawk
8. **Lehon**
  * Rescue the Elder Warrior and obtain Ship Parts
  * Use the Rakatan Ritual to enter the Ancient Temple
  * Defeat Bastila and stay true to the Light Side
  * Repair the Ebon Hawk and fly to the Star Forge
9. **Star Forge**
  * Find and kill Darth Malak

The reasoning for the middle planets:
- Manaan is first because there are no fights we have to win, and thus our relatively weak combat abilities don't matter as much.
- Tatooine is second because there's either no combat (if you do Krayt Skip), or we get the Krayt Dragon Pearl for a much-needed Attack bonus.
- Korriban is third so that we can get the Solari crystal; we also may have reached Level 9 (and Knight Speed) before Uthar and Yuthura to make those fights easier.  We also buy top-notch stims and medpacs here to make some later fights easier.
- Kashyyyk is done last because you can skip the Star Map computer's quiz if your identity has already been revealed, and our Save Teleports will be maximally effective here.

## Detailed Route

This section will describe all the actions you'll need to take for the Any% NMG run.

Notation:
- `Level ups are highlighted in code block`
- *Inventory/Equipment changes are highlighted in italics*
- **Item Upgrades at a workbench are highlighted in bold**
- `Shopping trips are highlighted in large code blocks`

Conversation Notes: 
- If no conversation choices are specified, spamming will work (this chooses all 1 options).
- A ... indicates a break in the conversation, such as changing who you're talkng to or having to talk to the NPC again
- A * indicates a variable answer, such as in reciting the Sith Code.
- A #xY indicates repeat that option Y times, as in Gadon Thek's first conversation.

Abbreviations:
* MC - Stands for Main Character, your player character
* CS - Cutscene
* QS - Quick Save
* QL - Quick Load
* QS/QL - Quick Save then immediately Quick Load
* GP Warp - [Gather Party Warp](<../Techniques/GP Warp#buffered-gp-warps>)

**Jump to a Section:**
- [Endar Spire](#endar-spire)
- [Taris 1](#taris-1)
- [Taris 2](#taris-2)
- [Dantooine](#dantooine)
- [Manaan](#manaan)
- [Tatooine](#tatooine)
- [Korriban](#korriban)
- [The Leviathan](#the-leviathan)
- [Kashyyyk](#kashyyyk)
- [Lehon](#lehon)
- [The Star Forge](#the-star-forge)

## Endar Spire

### Character Creation

- Male/Female Scout - Custom Character
- Str to 18, Dex to 14, Con to 14, Int to 10
- Computer Use to 4, Security to 1, Treat Injury (TI) to 4, Save 2
- Initial Feat: Weapon Focus: Melee Weapons
- Pick a good name!
- Hit Play! (and be ready to [Hard Buffer](<../Techniques/Save Buffering#hard-buffers>)!)

### Endar Spire

- [Hard Buffer](<../Techniques/Save Buffering#hard-buffers>) past Intro CS
- Loot footlocker
- *Equip MC: Short Sword*
- Trask conversation twice (spam)
- *Equip Trask: Blaster Pistol Offhand*
- Use security on door
- Kill two Sith Soldiers
- Loot footlocker in next room
- Cutscene of Sith vs. Republic
- Kill front three Sith Soldiers with frag grenade
- Jedi vs. Sith cutscene
- Loot Jedi for Vibration Cell/Adrenal Strength
- Kill two Sith soldiers
- Kill front two Sith soldiers on bridge
- `Level to 2: Save skills, Two-Weapon Fighting`
- [Hard Buffer](<../Techniques/Save Buffering#hard-buffers>) past Trask's death scene
- Enter Starboard Section

### Starboard Section

- Loot footlocker in Terminal Room
- Hack terminal console: 2,3
- Loot Sith Commander for Prototype Vibroblade
- Carth talks to you
- Take Escape Pod to Taris

## Taris 1

### Upper City

- Use the stims hotkey to use two stims:
  - Once (for Adrenal Alacrity) before the dream CS
  - Once (for Adrenal Strength) before the waking up CS in the Hideout
- Carth talks to you: 1,1,1,5,3
- Loot footlocker for spikes and medpacs
- *Equip MC: Combat Suit, Prototype Vibroblade Mainhand, Vibroblade Offhand*
- Exit the apartment
- *Party: No change when prompted*
- [Hard Buffer](<../Techniques/Save Buffering#hard-buffers>) to skip Sith Raid CS
- Larrim accosts you: 1,2,4

```
SHOPPING: Larrim
- SELL ALL EXCEPT:
  - Medpacs
  - Computer Spikes
  - Vibroblade
  - Frag Grenade
- BUY:
  - 2x Concussion Grenade
  - Frag Grenade
  - Battle Stimulant
- End: ~808 Credits
```

- *Stims: Use Battle Stimulant on MC*
- Exit to Upper City South
- ***Optional Safe Strat: Zelka Stims***
  - *Skipping Zelka saves around 6-8 seconds, but gives no leeway in terms of stims, meaning you lose lots of time if Carth or MC die anywhere on Taris.  This strat is recommended for beginning runners until they are comfortable with the rest of Taris.*
  - *To perform the safe strat:*
    - Run towards statue at the end of the walkway
    - Activate Solo Mode
    - As Carth, open door to Upper City North
    - As MC, talk to Zelka in the medical clinic: 3
    - **BUY:** 3x Adrenal Alacrity (150 Credits)
    - Swap to Carth and [Buffer GP Warp](<../Techniques/GP Warp#buffered-gp-warps>) to warp MC
    - Run backwards to trigger the bullied merchant CS
  - *To skip the safe strat instead:*
    - Run down street to left and approach bullied merchant
- Bounty hunters accost you: 1 (+2 LSP)
- Kill the bounty hunters with a frag grenade
- Give credits to the merchant to pay his debt (+4 LSP)
- Enter Upper City North
- Run straight across to Upper City North Apartments
- Run to the left until Sith soldiers accost you (+2 LSP)
- Swap to Carth and queue Power Blasts on all three Sith soldiers
- Activate Solo Mode
- Swap to MC and run back to the door you entered through
- Swap to Carth and loot all three corpses for Sith Uniform, grenades, and adrenals
- *Stims: Use Adrenal Alacrity on Carth*
- Swap to MC and [Buffer GP Warp](<../Techniques/GP Warp#buffered-gp-warps>) to warp Carth
- Exit the apartments
- *Equip Carth: Sith Armor*
- Activate Solo Mode
- Run Carth down street to right until it narrows
- Swap to MC and [Buffer GP Warp](<../Techniques/GP Warp#buffered-gp-warps>) to warp Carth
  - The cutscene to enter the Lower City will play and warp MC there
- Enter the Lower City

### Lower City

- [Hard Buffer](<../Techniques/Save Buffering#hard-buffers>) past Vulkar/Bek CS
- *Equip Carth: Clothes or Nothing*
- Enter Javyar's Cantina
- Return to Hideout and immediately Transit Back
  - This sets the Transit Point, which we will use after rescuing Bastila
- Leave the cantina and enter the Hidden Bek Base
- Activate Solo Mode
- While MC opens door in front, Carth opens the exit door
- Zaerdra accosts you, then talk to Gadon Thek: 1x10, 3, 2
- Leave to Lower City
- *Party: Remove Carth*
- [Hard Buffer](<../Techniques/Save Buffering#hard-buffers>) past Canderous CS
- Enter the Undercity
  - We want extra enemies to die so we get enough XP for Bastila to hit level 4 when we recruit her
  - Some of the Black Vulkars will die to the blaster turrets as you enter the Undercity
  - If all three Vulkars die, you can skip some enemies later on

### Undercity

- [Hard Buffer](<../Techniques/Save Buffering#hard-buffers>) to skip beggar CS
- `Level to 3: TI to 6, Empathy`
- *Party: Add Carth*
- Exit the gate and kill the rakghoul
  - MC should use Flurry
  - Carth uses Power Blast at close range
- Mission agrees to help you
- *Party: No change when prompted*
- Enter the Lower Sewers

### Sewers

- ***Optional Strat: Lower Sewers [GP Warp](<../Techniques/GP Warp#buffered-gp-warps>)***
  - *This strat saves about 10 seconds, but can be risky as you may be trying to [GP Warp](<../Techniques/GP Warp#buffered-gp-warps>) while MC is in combat.*
  - *To perform this strat:*
    - Open first door, then door on right
    - Activate Solo Mode
    - Throw a frag grenade at the rakghouls
    - As MC, run up the path past the Gamorrean and open first door on right
      - While this happens, Carth and Mission should finish off the rakghouls
      - We need them out of the way for the upcoming [GP Warp](<../Techniques/GP Warp#buffered-gp-warps>)
      - This also helps us hit Bastila's XP threshold
    - Swap to Carth and open door on left (before the force field)
    - Swap to MC and rescue Zaalbar
    - *Party: Add Carth, Keep Mission when prompted*
    - Run MC slightly into Zaalbar's cell for protection from the Gamorreans
    - Swap to Carth and lower force field
    - Swap to Mission and [Buffer GP Warp](<../Techniques/GP Warp#buffered-gp-warps>) to teleport MC
  - *If you choose not to use the above strat:*
    - Activate Solo Mode and place Mission next to ladder
    - Run to cell and free Zaalbar
    - *Party: Add Carth, Keep Mission when prompted*
    - Switch to Mission and leave by ladder
    - Reenter sewers
    - Throw frag grenade at rakghouls
    - Swap to Mission and Deactivate Force Field
      - Carth and MC should finish off rakghouls while Mission does this
      - We need the rakghouls to die so we hit Bastila's XP threshold
- Enter Upper Sewers
- ***Optional Strat: Upper Sewers [GP Warp](<../Techniques/GP Warp#buffered-gp-warps>)***
  - *This strat saves about 10 seconds in the Vulkar Garage, but it's finicky.  It's personal preference whether to use this trick or not.*
  - *To perform this strat:*
    - *Party: Remove Mission*
    - Activate Solo Mode
    - As Carth, open the door behind you to Lower Sewers
    - As MC, run through sewers and kill the Malfunctioning Droid
      - You can skip this if all the Vulkars died while entering the Undercity
    - Quickly swap to Carth and [Buffer GP Warp](<../Techniques/GP Warp#buffered-gp-warps>) to teleport MC to end of sewers
    - Queue up Flurries on the Vulkar Guards, then swap back to Carth
      - We want these guards to die to hit Bastila's XP threshold
    - Run through sewers to same point as before (just after the Minor Gas Mine)
    - Watch MC's health during this section and heal as needed
    - Swap to MC and [Buffer GP Warp](<../Techniques/GP Warp#buffered-gp-warps>) to teleport Carth to end of sewers
  - *If you choose not to use the above strat:*
    - *Party: Remove Mission and Carth*
    - Run through left tunnel, then take right tunnel
    - Kill the Malfunctioning Droid
      - This is now needed to hit Bastila's XP threshold
    - Juke past the rancor and enter the Vulkar Base
      - Try to run always at a 90 degree angle from the rancor's pursuit
      - Or, loot the bones and add a Frag Grenade and some Synthesized Odor to the pile of bones to kill the rancor (wastes 20 seconds)
- Enter the Vulkar Base

### Vulkar Base

- Kill the patrol droid
  - We need it out of the way if Carth is present
  - This also goes towards Bastila's XP threshold
- Defense turret skip
  - Open door to elevator area
  - Stand in doorframe corner near terminal and QS
  - Throw both concussion grenades (use Carth if present) at center turret
  - If any turret remains unstunned, QL and try again
  - If all three turrets are stunned, take the elevator to the Garage
  - If MC is alone, you can try to reach the garage with only 2 turrets stunned. There's a 25% chance the remaining turret will miss you.
- Activate Solo Mode (if Carth is present)
- As Carth (or as MC if no Carth):
  - Take hallway on right and enter last door on right
  - Loot Garage Head's Desk (for keycard) and supplies (for Computer Spikes)
- Swap to MC (or continue as MC if no Carth):
  - Kill both Vulkars in the central hallway
  - Continue past the mines and take last door on left
  - [Hard Buffer](<../Techniques/Save Buffering#hard-buffers>) to skip Kandon Ark fight
- Get the swoop accelerator
- Talk to Kandon Ark: 1,1,1 (-2 DSP)
- This will teleport you outside the Vulkar base

### Rescuing Bastila

- Return to Hidden Bek base
- Talk to Zaerdra and Gadon Thek
- After loading into the Swoop Platform, [Hard Buffer](<../Techniques/Save Buffering#hard-buffers>) to skip the Ithorian convo
- Talk to the Race Coordinator to complete race one
  - Do not shift into the top gear for these swoop races; it's faster by roughly a second to stay in fourth gear!
  - Whatever time you get on this race will be beaten by 0.25s by Redros 
- Talk to the Race Coordinator to complete race two
  - You'll need to beat Redros's time on the second race, but your swoop accelerates faster than before
- After talking to the Ithorian but BEFORE Brejik's convo, [Hard Buffer](<../Techniques/Save Buffering#hard-buffers>) to skip the Brejik fight
  - The Ithorian's convo is only two dialogs, so click twice then immediately start buffering
- Talk to Bastila
  - If you miss the previous buffer, you can use [Combat Talking](<../Techniques/Combat Talking>) to talk to Bastila and skip the Brejik fight
  - Mash through the conversation
  - Bastila will loot Brejik's nonexistent corpse, so you still get her lightsaber and Brejik's equipment
  - This takes you back to the apartment hideout 

## Taris 2

### Upper City

- [Hard Buffer](<../Techniques/Save Buffering#hard-buffers>) to skip Carth/Bastila's conversation
- Exit the apartment
- After loading, use a [Map CS Skip](<../Techniques/Map Cutscene Skips>) to Transit Back into Javyar's Cantina
  - *Party: Add Bastila during the [Map CS Skip](<../Techniques/Map Cutscene Skips>)*
- Activate Solo Mode and run MC into the cantina
- Canderous talks to you
- `Level Bastila to 4: Recommended Attribute, Save Skills, Burst of Speed`
  - If Bastila cannot level yet, take this level as soon as it becomes available
  - ***Optional:** In Gameplay settings, enable Auto-Level for Party Members. This saves having to manually auto-level in a couple places, but you must remember to turn the setting off when you start a new run!*
- Exit the cantina as Bastila and run back to elevator to Upper City
  - Use Bastila's Force Speed for movement here
  - If she didn't have a level ready, use MC instead (should have Alacrity active)
- In Upper City, Activate Solo Mode to leave MC/Bastila at elevator
- Run to Droid Shop in Upper City North
- Talk to Janice Nall: 2,2,1 (-4 DSP)
- *Party: Add T3 when prompted*
- Swap to the party member near the elevator and Deactivate Solo Mode
- Click the elevator and mash the conversation
  - This warps the entire party to the elevator and gives you control of the MC
- Run to Sith Base (with Bastila's Force Speed or MC's Alacrity)
  - You can also [Save Teleport](<../Techniques/Save Teleporting>) with T3 if Bastila is still not level 4
- [Hard Buffer](<../Techniques/Save Buffering#hard-buffers>) to skip T3's door opening cutscene
- *Party: Remove Bastila, Add Zaalbar*
- *Equip Zaalbar: Mission's Vibroblade Mainhand, Vibroblade Offhand*
- *Stims: Adrenal Strength on Zaalbar*
- Enter Sith Base

### Sith Base

- [Hard Buffer](<../Techniques/Save Buffering#hard-buffers>) to skip secretary conversation
  - If you miss, the conversation is 3,1
- Kill both patrol droids at the end of the first hallway
- Take right hallway and kill patrol droid
- Defeat Sith soldiers in barracks
- Loot footlocker for passcard with T3
- As T3, [Hard Buffer](<../Techniques/Save Buffering#hard-buffers>) to skip Assault Droid intro CS
- Assault droid fight:
  - Pause and use a Concussion Grenade on Assault Droid with T3
  - MC attacks Assault Droid with Flurry
  - Zaalbar attacks Assault Droid with Improved Power Strike
  - T3 can use his Shield Disruptor to take out the Blaster Turrets (two shots each)
- Enter the elevator
- Recommended safety QS in case of death/bad luck
- Sith Governor fight:
  - MC: Poison Grenade, then Flurry
  - Zaalbar: Sonic Grenade, then Improved Power Strike
  - T3: Stun Ray x4, but keep queueing more Stun Rays until the Governor is stunned
  - If desired, T3 can switch to Shield Disruptors if you need more damage once the Governor is stunned
- Loot both strongboxes and Sith Governor's corpse for Launch Codes
  - T3 can start to loot these during the fight if the Governor is about to die
- Exit the Sith Base

### Escaping Taris

- *Party: Remove Zaalbar and T3, Add Bastila*
- Enter the Lower City
- Immediately QS/QL to make sure the MC follows Bastila sufficiently
- Enter Javyar's Cantina and talk to Canderous: 2
- *Party: Add T3, Keep Canderous when prompted*
- After loading in Davik's Estate, [Hard Buffer](<../Techniques/Save Buffering#hard-buffers>) to skip the Davik/Calo convo and fight
- Switch to T3 to hack security terminal: 1,2,2,4,3
- Enter the Hangar
- *Equip MC: Clothes or Nothing*
- ***Optional:*** If you are *not* doing Krayt Skip on Tatooine, *Unequip Canderous and T3 entirely*
- Board the Ebon Hawk, then use a [Map CS Skip](<../Techniques/Map Cutscene Skips>) to Return to Ebon Hawk
  - This skips the cutscenes between Taris and Dantooine, as well as the fighter skirmish 

## Dantooine

### Jedi Enclave

- Follow Bastila to Jedi Council
  - While doing this, check the menu in the bottom right to see if you have an Adrenal Alacrity
- [Hard Buffer](<../Techniques/Save Buffering#hard-buffers>) to skip Belaya's conversation
- [Open Buffer](<../Techniques/Save Buffering#open-buffers>) into the council conversation
  - This lets you skip the first text faster than usual, saving a few seconds
- If you have an Adrenal Alacrity, press the stim hotkey *before* the dream CS to use it
  - This will only happen if you got a random Alacrity drop *or* bought stims from Zelka
- Carth accosts you
- *Party: Remove Canderous, Keep T3 when prompted*
- [Open Buffer](<../Techniques/Save Buffering#open-buffers>) into the council conversation
  - Swap to T3 as the buffer ends
- IMMEDIATELY AFTER this conversation, [Hard Buffer](<../Techniques/Save Buffering#hard-buffers>) to skip training montage
  - The council conversation is seven 1s; I count those seven, then click twice
  - As Master Vrook says, "I can only hope you prove up to the task...", click to skip the text and IMMEDIATELY AFTER, start buffering
  - If you get the QS, but fail the load, kill the program, reopen, and reload the save
  - If you miss the QS, it's faster to kill the program and try again (the previous [Open Buffer](<../Techniques/Save Buffering#open-buffers>) acts as a safety save)
- Swap to T3 and talk to Master Zhar: 1,1
- Swap to MC and talk to Master Zhar again: 1,1,6,3,2,6,4
- Swap to T3 and talk to Master Dorak to become a Jedi Guardian
- `Level to 4: Strength to 19, Save Skills, Improved Two-Weapon Fighting, Force Speed and Force Valor`
- `Level to 5: Save Skills, Affect Mind`
- `Level to 6: Persuade to 9, Improved Flurry, Dominate Mind`
  - From here, you can take each level up as soon as possible; they're listed where they are guaranteed to occur
- Swap to T3 and talk to Master Zhar
- *Party: Remove T3*
- *Force: Cast Burst of Speed*
- Talk to Master Zhar once more
- Talk to droid and exit enclave
  - *Force: Cast Burst of Speed as you exit for Duration Glitch*

### Dantooine Savannah

- [Soft Buffer](<../Techniques/Save Buffering#soft-buffers>) to skip Jon's conversation
- [Soft Buffer](<../Techniques/Save Buffering#soft-buffers>) to skip kath hound spawn
- Run/Force Jump to closer entrance to Matale Grounds
- Run through Matale Grounds to Grove
- Run left, then [Soft Buffer](<../Techniques/Save Buffering#soft-buffers>) to skip Bolook's murder mystery
- Loot the Mandalorian corpse outside Juhani's enclosure
- [Soft Buffer](<../Techniques/Save Buffering#soft-buffers>) to skip the Juhani fight
- Talk to Juhani to redeem her
- Return to Ebon Hawk (RtEH)
- Talk to Master Zhar, then Master Vandar
- *Party: No change when prompted, then Remove Bastila after convo*
- Transit Back to Grove and run/Force Jump to Matale Grounds
- Loot Casus Sandral's corpse in Matale Grounds
  - This is the one surrounded by three Kath Hounds ahead and to the right
- Run/Force Jump to Courtyard
- As you approach the ruins, hug the right wall to skip a short CS
- Enter the Ruins

### Ancient Ruins

- *Party: Add T3, Keep Bastila when prompted*
- [Soft Buffer](<../Techniques/Save Buffering#soft-buffers>) to skip ancient droid conversation
- Activate Solo Mode and do the following actions simultaneously:
- As MC:
  - Open right hand door
  - Force Jump to guardian droid
  - Hack the console: 3,5,3,3,3,4
- As Bastila:
  - *Force: Cast Burst of Speed*
  - Open left hand door
  - Run through and loot droid wreckage
  - Hack the console through the left door: 3,5,3,1,1,3
- As T3:
  - Move in front of middle door
- Once both consoles are hacked, swap to T3 and Deactivate Solo Mode
- As T3, move forward through both doors
- [Soft Buffer](<../Techniques/Save Buffering#soft-buffers>) to skip short CS
  - The timing on this is tricky; open the door, wait a second, then start buffering
  - If done right, MC will end up in front of the Star Map without having to watch the CS
  - If the timing is off, MC will stay in front of the console they hacked and you'll have to run to the Star Map
- Star Map: Dantooine
- Loot Nero's corpse for Robe and Sigil crystal
- Exit Ruins
  - If one of your party members doesn't follow, use a [GP Warp](<../Techniques/GP Warp#buffered-gp-warps>) to get them out quickly

### Jedi Enclave
- *Party: Remove Bastila and T3*
- Return to Ebon Hawk and speak with the Council
- Transit Back and Return to Ebon Hawk to board it
- Fly to Manaan
  - [Map CS Skip](<../Techniques/Map Cutscene Skips>) once
  - Reboard Ebon Hawk
  - [Map CS Skip](<../Techniques/Map Cutscene Skips>) again
    - Add T3 during the second Map CS Skip

## Manaan

### Ahto City

- Having a party member skips a Selkath announcement after the first door
  - If you didn't add T3, [Soft Buffer](<../Techniques/Save Buffering#soft-buffers>) to skip it instead
- [Soft Buffer](<../Techniques/Save Buffering#soft-buffers>) to skip Sith/Republic soldier conversation
  - If you miss this, the conversation is just: 4
- Talk to Selkath Merchant: 3

```
SHOPPING: Selkath Merchant
- BUY: 
  - 1x Advanced Medpac
  - 1x Hyper Battle Stimulant
  - 1x Hyper Adrenal Strength
  - 1x Hyper Adrenal Alacrity only if you did not buy stims from Zelka on Taris
- Optional: If not doing Krayt Skip later
  - BUY: Another Hyper Battle Stimulant and Hyper Adrenal Strength
- End: ~500-800 Credits
```

- Exit to West Central Ahto City
- Talk to Port Authority: 1,3
- Run to East Central
- [Soft Buffer](<../Techniques/Save Buffering#soft-buffers>) to skip Sith/Republic soldier conversation again
- Talk to Roland Wann: 3, 1x8
- Return to Ebon Hawk and run to Sith Hangar at far end of hallway
  - T3 should still be with you
- [Soft Buffer](<../Techniques/Save Buffering#soft-buffers>) to skip Selkath announcement
- Enter transport to travel to Sith Base

### Sith Base

- Run right through two doors
- [Soft Buffer](<../Techniques/Save Buffering#soft-buffers>) to skip security fight
- Activate Solo Mode; open front door as T3
- As MC, go through door behind secretary, then turn left twice
- Loot data module from broken droid
- Swap to T3 and [Buffer GP Warp](<../Techniques/GP Warp#buffered-gp-warps>) to warp MC to entrance
- Exit Sith Base
- [Map CS Skip](<../Techniques/Map Cutscene Skips>) for Arrest Skip
  - *Party: Remove T3 during the [Map CS Skip](<../Techniques/Map Cutscene Skips>)*
- Transit Back and run back to Republic Embassy
  - Sith on the street accosts you: 2
  - You can [Soft Buffer](<../Techniques/Save Buffering#soft-buffers>) this as well
- Talk to Roland Wann
- ***Optional** Party: Add Zaalbar and Juhani*
  - *This gives more consistent extra XP from patrol droids in Hrakert Station, making it more likely to hit level 9 before Uthar and reach level 11 on Star Forge.*
- Take submersible to Hrakert Rift 

### Hrakert Rift

- Mercenary accosts you
- Loot Equipment Pack for Thermal Detonator
- Take first door on right
- Take door next to second droid, then go straight through several doors
- Get Environment Suit from floor
- Loot footlocker in next room for Sonic Emitter
- At the airlock, *Stims/Force: Cast Burst of Speed, Use Basic Adrenal Alacrity on MC*
- Exit to Sea Floor
- Survivor accosts you once
- [Sonic Buffer](<../Techniques/Save Buffering#soft-buffers>) (with Sonic Emitter) to skip survivor's death scene
- Underwater walk
  - *It is faster to go into the inventory menu, use the Sonic Emitter, and exit the menu; this skips the animation of the Sonic Emitter*
- Reenter station through lefthand door
- *Force: Cast Burst of Speed*
- Loot the first footlocker for 4 Computer Spikes
- Speak with scientists through force field: 3
  - Immediately after this, [Soft Buffer](<../Techniques/Save Buffering#soft-buffers>) to skip the second conversation
- Loot the footlocker in the corner of the next room for 2 Computer Spikes
- At the airlock, double check that Speed and Alacrity are active (they usually are)
  - If not, *Force/Stims: Cast Burst of Speed, Use Adrenal Alacrity on MC*
- Exit to Hrakert Rift
- [Sonic Buffer](<../Techniques/Save Buffering#soft-buffers>) (with Emitter) to get past Firaxan shark death trigger
- Star Map: Manaan
- [Sonic Buffer](<../Techniques/Save Buffering#soft-buffers>) (with Emitter) to skip death trigger when leaving
- Reenter station through righthand door
- `Level to 7: Persuade to 10, Stun Droid`
- Return to surface, RtEH and board
- ***Optional:*** If you are *not* doing Krayt Skip:
  - *Equip MC: Jedi Knight Robe, Strength Gauntlets, Verpine Headband, Double-Bladed Lightsaber*
  - **Upgrade Double-bladed Lightsaber: Add Sigil Crystal**
- Fly to Tatooine with a [Map CS Skip](<../Techniques/Map Cutscene Skips>)

## Tatooine

*Note: For Tatooine and almost every planet afterwards, [Save Teleports](<../Techniques/Save Teleporting>) are the most efficient form of movement.  These are more effective if you do NOT have Force Speed active, so try to keep it off as much as possible. [Force Skips](<../Techniques/Force Skips>) can still be done by casting Force Speed twice to cancel it.*

### Anchorhead

- Czerka Officer accosts you: 1,1,5
  - Or [Force Skip](<../Techniques/Force Skips>) the conversation
- ***Optional:*** If you are *not* doing Krayt Skip, talk to Mic'Tunan'Jus Orgu: 1

```
SHOPPING: Mic'Tunan'Jus Orgu
- BUY:
  - Bantha Fodder
- End: ~500-800 Credits
```

- [Soft Buffer](<../Techniques/Save Buffering#soft-buffers>) to skip the Gizka conversation
- Exit to Anchorhead
  - *Force: Cast Force Valor before exiting to Duration Glitch it*
- Enter Czerka Office
- [Force Skip](<../Techniques/Force Skips>) the Duros conversation
- Talk to the Czerka Officer: 1,1,1,3,2
- Exit the office
- [Soft Buffer](<../Techniques/Save Buffering#soft-buffers>) or [Save Teleport](<../Techniques/Save Teleporting>) to skip the Dark Jedi fight
- Speak to the Gate Guard to exit to Dune Sea

### Dune Sea

- [Soft Buffer](<../Techniques/Save Buffering#soft-buffers>) to skip the angry wife conversation
- [Save Teleport](<../Techniques/Save Teleporting>) towards the Eastern Dune Sea (left side of sandcrawler)
- [Save Teleport](<../Techniques/Save Teleporting>) past Eastern Dune Sea loading zone
  - This skips a trigger that prevents you from entering without a map
  - A [Soft Buffer](<../Techniques/Save Buffering#soft-buffers>) will also cancel the trigger preventing you from entering the loading zone
- ***Optional:*** If you *are* doing Krayt Skip, *Party: Add Bastila*
- Enter loading zone from the back to enter Eastern Dune Sea

### Eastern Dune Sea

- ***Optional Strat: Krayt Dragon Skip***
  - *This skip saves a minute if you get it first try, but has a 2-frame window, and retries take 14-15 seconds.  This is recommended only for runners going for top times.*
  - *To perform Krayt Dragon Skip:*
    - [Save Teleport](<../Techniques/Save Teleporting>)/[Soft Buffer](<../Techniques/Save Buffering#soft-buffers>) from entrance all the way into the Krayt Dragon's cave
      - Make sure Bastila follows you!
    - Loot left hand rubble for Opila crystal
    - Activate Solo Mode
    - As MC, run to mouth of cave
    - As Bastila, stand in a fairly precise position in front of the Krayt Dragon
      - We use Bastila to block the Krayt so it ends up in a specific spot
      - Use these pictures to help you line it up
![An image showing Bastila's positioning for Krayt Skip](/assets/images/imgur-dump/wWAiCqs.png)
![Another angle of Bastila's positioning for Krayt Skip](/assets/images/imgur-dump/GGjL3bL.png)
    - Swap to MC and QS
    - Run out of the cave to trigger the CS where the Krayt Dragon eats you
    - After the CS but before the pop-up indicating your death, QS
      - This is a 2-frame window at 60 FPS. Good luck!
      - If you fail, load the safety QS and run forward to try again
      - If you get it fourth try, it roughly breaks even with the no skip route
    - Once successful, load the QS
    - Swap to Bastila and talk to the Krayt Dragon
      - This freezes it in place
    - Deactivate Solo Mode
    - Loot the chewed Twi'lek corpse for Nerve Amplifier Belt
    - Star Map: Tatooine
      - If you can't make it around the Krayt's right side, Bastila's position was off; load the Autosave and redo the setup
      - If you can get the map but can't loot the belt, buy it from Mic'Tunan'Jus Orgu when you get back to the Docking Bay
      - You'll have to skip buying Hyper Staminas and some medpacs on Korriban in this case
  - *If you choose not to use the above strat:*
    - [Save Teleport](<../Techniques/Save Teleporting>) to skip anonymous hunter's death CS
    - Talk to Komad Fortuna: 1,2,1,1,3,1
    - [Save Teleport](<../Techniques/Save Teleporting>) to skip death CS on the way out
    - *Stims/Force: Hyper Adrenal Strength and Hyper Battle Stim on MC, Cast Force Valor*
    - Talk to banthas to lure them with fodder
    - Kill four Elite Sand People Warriors:
      - Force Jump and Flurry to kill the center warrior first
      - Force Jump and Flurry the right warrior next
      - Force Jump/Flurry to the remaining pair to finish those two off
      - Keep a close eye on your health and medpac as needed
    - Lure banthas with fodder again
    - Talk to Komad Fortuna: 1 ... 1
    - Loot chewed Twi'lek corpse for Nerve Amplifier Belt
    - Star Map: Tatooine
- [Hard Buffer](<../Techniques/Save Buffering#hard-buffers>) to skip Calo Nord fight (and possibly Krayt Death trigger)
  - The Calo CS cannot be [Soft Buffered](<../Techniques/Save Buffering#soft-buffers>)
- Exit to Dune Sea
- Return to the Ebon Hawk and board
- *Equip MC:*
  - *Verpine Headband*
  - *Strength Gauntlets*
  - *Nerve Amplifier Belt*
  - *Jedi Knight Robe*
  - *Double-Bladed Lightsaber*
- **Upgrade Double Lightsaber: To Sigil and Krayt Pearl or Opila**
- Fly to Korriban with two [Map CS Skips](<../Techniques/Map Cutscene Skips>)

## Korriban

### Dreshdae

- Port Authority accosts you: 1,1,3,2
- Intervene with Shaardan (+7 LSP)
- [Soft Buffer](<../Techniques/Save Buffering#soft-buffers>) to skip Lashowe's conversation
- Talk to the Czerka Shopkeeper

```
SHOPPING: Czerka Shop
- SELL ALL EXCEPT:
  - Advanced Medpacs
  - Computer Spikes
  - Hyper Stims (you can sell basic stims)
- BUY:
  - 20x Advanced Medpacs (but stay above 2500 Credits)
  - 5x Echani Battle Stim
  - 5x Hyper Adrenal Alacrity, Strength, and Stamina
  - You can buy Life Support Packs with any extra
- End: <80 Credits
```

- Leave Dreshdae
- Talk to guard outside academy
- Reenter Dreshdae
  - *Force: Cast Force Valor while the door is opening to improve Persuade*
- QS near Yuthura for safety
- Talk to Yuthura: 3,4,2,3,1 (-2 DSP)
  - If you fail the 75% Persuade check, QL and retry

### Gaining Prestige

- [Force Skip](<../Techniques/Force Skips>) to delay Uthar conversation
- Talk to Lashowe: 1x8, 4
- Speak with Uthar Wynn and students
- Yuthura talks to you: 1,1,1,1,4,2,7,5
- `Level to 8: Strength to 20, Persuade to 11, Disable Droid`
- Talk to Kel Algwinn
- Exit to Valley of the Dark Lords
- [Map CS Skip](<../Techniques/Map Cutscene Skips>) to Return to Ebon Hawk, then Transit Back 
  - This skips the Darth Bandon fight
- Run/[Save Teleport](<../Techniques/Save Teleporting>) over to Lashowe (can Force Jump to Shyracks)
- *Stims/Force: Hyper Adrenal Strength, Hyper Adrenal Stamina, and Echani Battle Stimulant on MC, Cast Force Valor*
- Kill the Tukatas
- Lashowe confronts you: 2,3
- Kill Lashowe and loot her corpse for Holocron
- Return to Ebon Hawk
- [Save Teleport](<../Techniques/Save Teleporting>) to skip Sith Apprentice
- Talk to Sith Thug Leader (+4 LSP, Light-aligned)
- Return to Academy
- Talk to Uthar Wynn: 3,1,3,1,3,3,2,3,4,4,X,3,2,2
  - The X is a variable answer based on one of three questions he asks after the Sith Code
  - Answers are:
    - There is nothing worse than love: 2. False
    - Victory by any means is desirable: 2. False
    - It is our passion that fuels the Force: 1. True
  - You snitch on Kel Algwinn during this conversation for (-5 DSP, Neutral-aligned)
- Talk to Uthar again: 3

### Tomb of Naga Sadow

- Uthar instructs you in the tomb: 4
- [Save Teleport](<../Techniques/Save Teleporting>) at first door to skip Wraid spawn
- Take right fork and open door
- [Soft Buffer](<../Techniques/Save Buffering#soft-buffers>) to skip door closing CS
- Open door and loot Pillar of Ice
- On way out, loot Skeletal Human Remains for Solari crystal
- Return to central branch and freeze acid pool
- Star Map: Korriban
- Loot Sith Statue for Sith Lightsaber
- `Level to 9: Persuade to 12, Master Two-Weapon, Knight Speed`
  - You may not have this level available if you didn't get enough extra XP in Hrakert Station
- *Force: Cast Force Valor and Knight Speed*
- Uthar accosts you: 5,1
- Kill Uthar and Yuthura accosts you: 1
- Defeat Yuthura and spare her: 3,2 (+4 LSP, Light-aligned)
- [Save Teleport](<../Techniques/Save Teleporting>) back to the academy
- After entering the academy, immediately leave and Return to Ebon Hawk to board
- **Upgrade Double Lightsaber: To Sigil/Solari or Krayt Pearl/Solari**
- If you haven't already, `Level to 9: Persuade to 12, Master Two-Weapon, Knight Speed`
- Fly to Kashyyyk (no Map CS Skip)

## The Leviathan

### Detention

- Carth whines at you on the Ebon Hawk: 1,1,1,2
- Saul Karath's interrogation scene
- IMMEDIATELY AFTER, [Hard Buffer](<../Techniques/Save Buffering#hard-buffers>) to skip Mission's prison break CS
- As Mission:
  - [Save Teleport](<../Techniques/Save Teleporting>) and take door at end of left hallway
  - Loot footlocker for Sith Passcard AND 3 Computer Spikes
  - [Save Teleport](<../Techniques/Save Teleporting>) all the way to the Detention Center
  - Activate the terminal
- As MC, loot rightmost locker
- *Equip MC:*
  - *Verpine Headband*
  - *Strength Gauntlets*
  - *Jedi Knight Robe*
  - *Nerve Amplifier Belt*
  - *Double-Bladed Lightsaber*
- [Save Teleport](<../Techniques/Save Teleporting>) to the elevator to Bridge: 2

### Bridge

*For the rest of the Leviathan, you have to keep Carth and Bastila close to you in order to go through loading zones.  Do your best to make sure they don't wander off, as that can and will lose you a lot of time.  It can help to QS/QL here.*

- Turn right and kill guard
  - It's possible to run past this guard without killing him
  - However, there's a small chance he'll shoot at Carth/Bastila and aggro them
- Turn left at the end of the hall; make sure Carth and Bastila are following you here
- Take first door on left, then immediately bash down armory door
  - If you're too slow, the Sith Guard here will aggro Carth and/or Bastila
- Get the Space Suits from the floor
- Bash down the door across the armory
- QS before door across the hall
- Run through next room, bash down door, and enter bridge storage
  - If you get stunned or your party wanders off, QL and retry
- [Hard Buffer](<../Techniques/Save Buffering#hard-buffers>) to skip the spacewalk
  - Click the door, QS once, then QL
  - Done perfectly, you can run through the space section without any trouble
  - If that fails, the door may look open but be closed and solid (if your QS was slightly late)
  - If that happens, QS/QL and you can open the door without donning the suit
- *Force: Cast Knight Speed as MC*
- *Force: Cast Burst of Speed as Bastila*
- *Stims: Hyper Adrenal Alacrity on Carth*
- Activate Solo Mode
- As Carth and Bastila, go through the door on the right
  - Tuck them in the corner to attempt to deaggro them 
  - The goal is to have them stay close enough to the exit while you do Saul Karath skip
- Swap back to MC and run up to bridge door
- Saul Karath skip
  - ***Optional:** Hard Save for safety; it is possible to softlock here
  - This trick is a [Hard Buffer](<../Techniques/Save Buffering#hard-buffers>), but the timing is quite precise
  - Open Bridge Door and QS twice
  - Load immediately
  - If the trick works, the bridge door will be open, the fight will not start, and Bastila and Carth will be in your party
  - If Bastila and Carth are not in your party, you've softlocked
  - If your last QS was too late, your game will crash when you load
- Once successful, hack bridge terminal: 1,2
- [Save Teleport](<../Techniques/Save Teleporting>) to the exit
  - Bastila and Carth may be dead; if they're still on the farther half of the room that's fine
  - If they died closer to the bridge, you'll have to kill the five soldiers to revive them
- *Medpacs: Everyone as needed*
- Kill the Sith guard nearby to the left
- QS/QL to get party to follow
- Take left path and loop around outside back to elevator
  - If you are quick, it's possible to skip killing the two guards right outside the elevator
  - If either Carth or Bastila aggros on them, you'll likely have to kill them
  - Or you can use Solo Mode and [Save Teleports](<../Techniques/Save Teleporting>) to try to get everyone into the elevator
- Take the elevator to the Hangar: 3

### Hangar

- Activate Solo Mode
- Run/[Save Teleport](<../Techniques/Save Teleporting>) straight through to the Darth Malak CS
- *Stims/Force: Cast Knight Speed and Force Valor, Hyper Stim Suite on MC*
  - **Hyper Stim Suite** is Hyper Alacrity, Hyper Strength, Hyper Stamina, and Echani Battle Stim
- Darth Malak accosts you
- Plot twist!
- Darth Malak accosts you again: 1,1,1,1,2,1,4,1
- Darth Malak fight, part one
- Run/[Save Teleport](<../Techniques/Save Teleporting>) through blast doors after Malak flees
  - *Force: Cast Knight Speed and Force Valor, Hyper Battle Stim and Hyper Strength on MC*
- Darth Malak fight, part two
- Bastila sacrifices herself, sort of
- Leave with Carth through blast doors on left
- Shoot down the Sith fighters
- Talk to the party on the ship
- Exit the ship after the sleeping CS

## Kashyyyk

### The Great Walkway

- Port authority accosts you
- [Soft Buffer](<../Techniques/Save Buffering#soft-buffers>) from lower level to door to Great Walkway
  - This skips a conversation with Ziagrom and the Czerka guard at the end
- *Party: Add T3*
- Exit to Great Walkway
- Activate Solo Mode to leave T3 at landing pad
- [Save Teleport](<../Techniques/Save Teleporting>) to skip Czerka patrol
  - If you talk to them the convo is just 5
- [Save Teleport](<../Techniques/Save Teleporting>) along walkway until you reach the Wookiee Guard
  - You can also Force Jump where able, but be aware it will sometimes target enemies behind you
- [Soft Buffer](<../Techniques/Save Buffering#soft-buffers>)/[Save Teleport](<../Techniques/Save Teleporting>) past the Wookiee Guard
  - This skips a trigger that forces you to visit the Wookiee Village first
- Swap to T3 and [Buffer GP Warp](<../Techniques/GP Warp#buffered-gp-warps>) the MC to the elevator
- Take elevator to Upper Shadowlands

### Upper Shadowlands

- [Save Teleport](<../Techniques/Save Teleporting>) to skip Katarn Spawn
  - An easy cue is to QS when you reach the hanging vine
- Jolee Bindo greets you
- Continue to the fork, then Activate Solo Mode
- Run/[Save Teleport](<../Techniques/Save Teleporting>) with T3 to Jolee's House
- With MC, take left path and [Save Teleport](<../Techniques/Save Teleporting>) to Czerka guards
  - If the captain speaks to you, convo is 1,4
- Talk to first Czerka guard: 1,1,3,1,2
- Hack the sonic emitter next to that guard
- Talk to second Czerka guard: 1,1,2
- Hack the sonic emitter next to that guard
- IMMEDIATELY AFTER, [Soft Buffer](<../Techniques/Save Buffering#soft-buffers>) to skip the terentatek CS
  - Avoid casting Knight Speed here to preserve [Save Teleports](<../Techniques/Save Teleporting>)
- Swap to T3 and speak with Jolee: 1,1,1,1,2,3,1,1,1,1,1
  - *Party: Add T3, Keep Jolee when prompted*
- Swap to T3 and [Save Teleport](<../Techniques/Save Teleporting>) to Force Field: 1,2

### Lower Shadowlands

- Activate Solo Mode
- [Soft Buffer](<../Techniques/Save Buffering#soft-buffers>) or [Save Teleport](<../Techniques/Save Teleporting>) to skip the Mandalorian CS
- [Save Teleport](<../Techniques/Save Teleporting>) to skip a kinrath spawn
  - If you miss it, kill the Kinrath, because we'll have to return with Jolee and T3
  - Try to QS a few steps after the hanging vine
- Speak to Star Map Computer: 2
- Star Map: Kashyyyk
- Jolee/T3 teleport to you
- Deactivate Solo Mode
- Run/Force Jump/[Save Teleport](<../Techniques/Save Teleporting>) back to Upper Shadowlands
  - Make sure your party follows you

### Leaving Kashyyyk

- Activate Solo Mode
- Run/Force Jump/[Save Teleport](<../Techniques/Save Teleporting>) to Gorwooken
- Speak to Gorwooken to reach the Great Walkway
- Run/Force Jump/[Save Teleport](<../Techniques/Save Teleporting>) to Wookiee Village
  - [Soft Buffer](<../Techniques/Save Buffering#soft-buffers>) to skip the Dark Jedi fight
- Wookiee Guard accosts you: 1,1,1
- After loading, [Map CS Skip](<../Techniques/Map Cutscene Skips>) to Return to Ebon Hawk and board
- Fly to Star Forge System (Lehon) with a [Map CS Skip](<../Techniques/Map Cutscene Skips>)
  - Reboard Ebon Hawk
  - Do not use a Map CS Skip the second time
  - Sometimes you'll have to shoot down some Sith fighters; whether or not this triggers is sadly random

## Lehon

*[Save Teleports](<../Techniques/Save Teleporting>) are again very useful for movement on Lehon.  Be careful not to overuse them, as we want to avoid game crashes.*

### Beaches

- Run/[Save Teleport](<../Techniques/Save Teleporting>) To North Beach
- Rakatan Warriors accost you
- Speak with The One: 1,1,1,1,1,4,4
- Run/[Save Teleport](<../Techniques/Save Teleporting>) straight to Elder Warrior without entering combat and talk to him
  - If you enter combat accidentally, use [Combat Talking](<../Techniques/Combat Talking>) to talk to the Elder Warrior
- `Level to 10: Persuade to 13, Master Flurry, Knight Valor`
- Loot Ship Parts from opposite cell
- Run/Force Jump/[Save Teleport](<../Techniques/Save Teleporting>) out of Rakatan Compound
- [Force Skip](<../Techniques/Force Skips>) short walking cutscene outside
- Run/Force Jump/[Save Teleport](<../Techniques/Save Teleporting>) to Central Beach
- [Save Teleport](<../Techniques/Save Teleporting>) through Central Beach
  - You want to try to keep the four Rakatan Warriors here as stationary as possible, so mash these teleports as much as possible
  - We're trying to keep them out of the way for a trick later
- Run/Force Jump/[Save Teleport](<../Techniques/Save Teleporting>) through Temple Exterior to South Beach
- [Soft Buffer](<../Techniques/Save Buffering#soft-buffers>) to skip gizka death scene
- Enter Elder Rakatan Compound
- Speak with Rakatan Elders
- Run/Force Jump/[Save Teleport](<../Techniques/Save Teleporting>) back to Temple Exterior
- Begin the Rakatan ritual to enter the temple
- After the CS ends but before the load into the STUNT module, QS
  - You should mash QS as the party runs towards the temple
  - Kill the program with Task Manager, then reload the QS
  - This skips the Malak cutscene and clears memory leaks
- *Party: Remove Juhani, Add Canderous*
- Enter the Temple

### Ancient Temple

- Activate Solo Mode; make sure Jolee and Canderous stay right near the entrance
- Run/Force Jump/[Save Teleport](<../Techniques/Save Teleporting>) to temple basement in back
- *Stims/Force: Hyper Stim Suite on MC, Cast Knight Speed and Knight Valor*
- Kill both guard droids in basement
- Solve floor puzzle with the following path (an H shape, starting from the reset tile)
![Image showing the H-shaped solution to the Catacombs floor puzzle](/assets/images/imgur-dump/CF497Fm.png)
- Speak to basement computer: 1,1,2,1,2
- Return to main floor
- Activate Solo Mode
- ***Optional Strat: Temple [GP Warp](<../Techniques/GP Warp#buffered-gp-warps>)***
  - *This strat saves some time moving to the front of the temple, but it's a very finicky trick, as it is diffcult to hit the loading zone to activate the [GP Warp](<../Techniques/GP Warp#buffered-gp-warps>). You can disable V-Sync in Advanced Graphics Options to make it easier, but remember to re-enable it afterwards.*
  - *To perform this strat:*
    - Run/[Save Teleport](<../Techniques/Save Teleporting>) the MC just outside the room with the two droids
    - Swap to your second party member
    - [Buffer GP Warp](<../Techniques/GP Warp#buffered-gp-warps>) by hitting the load zone, then swapping to the MC
  - *If you choose not to use the above strat:*
    - Run/Force Jump/[Save Teleport](<../Techniques/Save Teleporting>) to front of temple and enter Massive Door
- Enter Temple Summit
- Talk to and defeat Darth Waifu
- Choose to remain true to the light side
  - This is faster than the Dark Side ending; no party members on Star Forge to get in the way
- Hack computer terminal to lower disruptor field
- Run/Force Jump/[Save Teleport](<../Techniques/Save Teleporting>) back to Central Beach
- As soon as you reach the Central Beach:
  - Activate Solo Mode
  - Swap to Canderous and board the Ebon Hawk
  - Canderous teleports to be there for the CS outside the Ebon Hawk, but stays in your party
  - If it says you're in combat, move Jolee and MC as far away from the Rakatan Warriors as possible and try again
  - If it still says you're in combat, MC will have to kill the Rakatan warriors before Canderous can board
- Repair hyperdrive on the Ebon Hawk
- Fly to the Star Forge

## The Star Forge

*Note: The game has now deleted data so that your [Save Teleports](<../Techniques/Save Teleporting>) are greatly weakened.  It's fastest to use Knight Speed and Force Jump for movement on the Star Forge.*

### Deck 1

- Exit the Ebon Hawk
- [Force Skip](<../Techniques/Force Skips>) Jedi vs. Sith CS
- [Soft Buffer](<../Techniques/Save Buffering#soft-buffers>) to skip Assault Droid CS and spawn
- Go right, then left
  - To get past the two frozen assault droids, click on the distant door and watch the wonders of KotOR pathing
- *Stims: Hyper Adrenal Alacrity on MC while waiting for the first hostile pair of droids to move*
- [Hard Buffer](<../Techniques/Save Buffering#hard-buffers>) past Jedi vs. Sith CS
- *Force: Cast Knight Speed, then Cast Knight Valor as you enter Deck 2*

### Deck 2

- [Hard Buffer](<../Techniques/Save Buffering#hard-buffers>) past fight trigger
- Take left path, then right, then turn left
- Hack computer terminal: 1,1,5
- Return and take elevator to Command Deck

### Command Deck

- Immediately after loading, [Hard Buffer](<../Techniques/Save Buffering#hard-buffers>) to skip Bastila/Malak CS
- Run/Force Jump until double doors
- *Stims/Force: Hyper Stim Suite (minus Alacrity) on MC, Cast Knight Speed/Valor if needed*
- [Open Buffer](<../Techniques/Save Buffering#open-buffers>) into the triple Dark Jedi fight
  - DO NOT [Soft Buffer](<../Techniques/Save Buffering#soft-buffers>); this will softlock the game
  - This [Open Buffer](<../Techniques/Save Buffering#open-buffers>) messes with the Dark Jedi AI so they won't attack you unless you attack them first
- Defeat three Dark Jedi to unseal the door
- Darth Waifu fight
  - *As a male MC with 12 Persuade and Empathy*, you can spam all conversations after the first
  - *As a female MC or with less than 12 Persuade*, use the given conversations to guarantee sparing Bastila
  - First conversation: 2
  - First phase (use Flurry for all phases; try to make sure Speed stays active)
  - Second conversation: 2, 2, 1
    - Spam default action during this convo to immediately talk to Bastila and skip phase 2
    - If you fail to skip it, just attack Bastila
  - Third conversation: 2, 2 (if you got the phase skip, this convo is also skipped)
    - Do NOT spam default action here; if you talk to Bastila again, it's a softlock
  - Defeat her last phase
  - Last conversation
    - *As a male character without enough Persuade*: 1, 1, 1, 3, 2, 3, 1, 1, 1, 1, 1
    - *As a female character*: 1, 1, 1, 2, 2, 2, 1, 1, 1, 1
- Before the cutscene on the Harbinger, activate a [Map CS Skip](<../Techniques/Map Cutscene Skips>):
  - Add two party members (at least one should be Jolee or Bastila, for Disable Droid)
  - Close the menu and watch the cutscene
- `If you hit Level 11, Auto-Level MC`
- [Soft Buffer](<../Techniques/Save Buffering#soft-buffers>) to skip the Darth Malak conversation
  - To get to the elevator, run towards the corner near the left Jedi and rapidly switch party leaders
  - One of your characters will end up next to the elevator door; take it to the Viewing Platform

### Viewing Platform

- Darth Malak fight:
  - Hit him until he triggers the Dead Jedi CS
  - Use Disable Droid with MC/Jolee/Bastila to release the remaining seven Dead Jedi
  - You can split the Jedi between MC and a party member to save a little movement
  - Kill Malak once and for all
  - You have a backup Hyper Stim Suite if you need it; don't try to hit Malak without it, as your hit rate goes down 25% without stims active
  - You can also try to keep Knight Valor active (+10% to hit) but this is hard without duration glitch

## Version History

**v4.3 (May 2022)**
- Added Zelka back in as an optional shopping trip for beginners or marathons.
- Miscellaneous minor fixes and corrections.

**v4.2 (May 2022)**
- Separated the Detailed Route into its planetary sections.
- Miscellaneous minor fixes and corrections.

**[v4.1](https://web.archive.org/web/20220419164357/https://www.speedrun.com/kotor1/guide/d8i6l) (December 2021)**
- Route now skips the shopping trip with Zelka. 
- Updated stim and credit route.
- Route now uses Carth for the Sewer GP Warps instead of Mission.
- Added an optional strat before the submersible on Manaan.

**[v4.0](https://web.archive.org/web/20220806234524/https://pastebin.com/drdB40H0) (November 2021)**
- Updated the rules to reflect the unbanning of Krayt Skip and Wire Targeting.
- Added Krayt Skip as an optional strategy on Tatooine.
- Removed the Freyyr fight in favor of save teleporting to the Wookiee Village.
- Updated the credit and shopping route to skip the CNS Strength Enhancer and Nerve Enhancement Package.
- Updated the character build to save level 4 for the Jedi class, ensuring earlier combat feats.
- Tweaked the alignment route to save time.
- Other minor additions and updates.

**[v3.3](https://web.archive.org/web/20210729145021/https://www.speedrun.com/kotor1/guide/d8i6l) (August 2020)**
- Updated the credit/stims route.
- Small tweak to the leveling plan.
- Updated the ruleset to ban Wire Targeting.
- Other minor additions and updates.

**[v3.2](https://web.archive.org/web/20200808193256/https://www.speedrun.com/kotor1/guide/d8i6l) (June 2020)**
- Fixed an error with the table in the Leveling Plan
- Added the elevator warp after buying T3

**[v3.1](https://web.archive.org/web/20200603002358/https://www.speedrun.com/kotor1/guide/d8i6l) (April 2020)**
- Updated the ruleset to allow Single Item Duping (but still not Full Inventory Duping)

**[v3.0](https://web.archive.org/web/20200420143723/https://www.speedrun.com/kotor1/guide/d8i6l) (April 2020)**
- Rebranded the category to better reflect its nature
- Updated the ruleset to ban Fast Lane, Hotshots, and Inventory Duping
- Tweaked the character build and alignment route slightly
- Tweaked the credit/shopping route through Dantooine
- Added a few short GP Warps to Taris/Manaan
- Added the optional Sewer GP Warp to Taris
- Miscellaneous small corrections

**[v2.2](https://web.archive.org/web/20191206184558/https://www.speedrun.com/kotor1/guide/d8i6l) (November 2019)**
- Updated the ruleset to include GP Warps.

**v2.1 (September 2019)**
- Miscellaneous small fixes

**v2.0 (June 2019)**
- Switched the planet order to Manaan -> Tatooine -> Korriban
  - This ensures Level 9 (and Knight Speed) before fighting Uthar and Yuthura

**[v1.3](https://web.archive.org/web/20190530154822/https://www.speedrun.com/kotor1/guide/d8i6l) (May 2019)**
- Moved the Transit Point set on Taris to save ~35 seconds.
- Added more info about the Canderous trick on Lehon
- Fixed a couple miscellaneous mistakes.

**v1.2 (March 2019)**
- Tweaked Character Build:
  - Initial Attributes have 10 Charisma instead of 10 Wisdom
  - Force Powers include Knight Valor/Disable Droid instead of Dominate Mind/Drain Life

**v1.1 (March 2019)**
- Modified strategies for Assault Droid and Sith Governor fights
- Added skip with Canderous on Lehon

**v1.0 (March 2019)**
- Converted the Beginner's Guide to this one
- Scout -> Jedi Guardian build with Two-Weapon/Flurry
- Route is a blend of Any% and Glitchless

## Closing

If you made it this far, congratulations!  Thanks for reading the guide.  Please let indykenobi know if you have any comments or questions (best way to contact is via the KotOR Speedrunning Discord).

I'd like to acknowledge glasnonck and thinkshooter, whose runs got me into KotOR speedrunning, as well as glasnonck, sheepmetal, and wurwilf, who all discussed this category before it was implemented.

Just remember, Pazaak is not for everyone.
