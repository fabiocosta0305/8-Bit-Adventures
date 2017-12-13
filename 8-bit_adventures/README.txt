
                            MM
                            MN
                            MN
                            MM
                            MM
                         MN$MM$NM
                            MM
                          MMMMMMM
                        8MM MM DMM:
                       MMM  MM  :MM=
                      IMM=  MM   MMM  MN MM    MMM= MM: MM
                      MMM$  MM   MMM  MMMMMM OMMMMM8MMMMMMM
                      ZMM   MM   MMM  MM  MM  MMM    MM ,M8
                       MMM  MM   MM$  MM  MM  MM     MM  MO
                        MMM MM DMM    MMMMMMI MMMNM  MMM$MM
                          ZMMMMM      MMM 7M     8M  NM  IM
                            MM        MM
                            MM        MM
          MM           ?N   MM
         MMMMM      NDMMM   \/                   $M,+M
       ~M M MMM         MM,                       =MM
      ,M  M  MMM     ZMMMM, MM MMM ,MMMM ZMM$MM ~MMMMMM MM:MMM MMMMMM  ?MMMM
     MM8 NM  OMMMD  MMD MM  MM MM, MM M   MM  MM   MM   MM +MZ  MM  ND=MM:M
     M  MMMM   OMM  MMD MM  MM MM7 MMM    MM  MM   MM   MM ~MI  MM     MMM
    IM   ,M     MM8 MMZ MM  MM MM  MM  O  MM  MM   MM   MM OMI  MM    :MM  M    
    MMZM     O  MMM MMMMMMM MMMM   8MMMM  MMM+MM   MM   MMMMMM MMM     8MMMM    
    ::::      :::::                                MM Z
                                                   $MMM

════════════════════════════════════════════════════════════════════════════════

          _____           _        _      ____                  _
         |  __ \         | |      | |    / __ \                | |    _
         | |__) |__   ___| | _____| |_  | |  | |_   _  ___  ___| |_  (_)
         |  ___/ _ \ / __| |/ / _ \ __| | |  | | | | |/ _ \/ __| __|  
         | |  | (_) | (__|   <  __/ |_  | |__| | |_| |  __/\__ \ |_   _
         |_|   \___/ \___|_|\_\___|\__|  \___\_\\__,_|\___||___/\__| (_)
  
         ___     ___ _ _       _      _             _                   
        ( _ )___| _ |_) |_    /_\  __| |_ _____ _ _| |_ _  _ _ _ ___ ___
        / _ \___| _ \ |  _|  / _ \/ _` \ V / -_) ' \  _| || | '_/ -_|_-<
        \___/   |___/_|\__| /_/ \_\__,_|\_/\___|_||_\__|\_,_|_| \___/__/
                                                                                   
                                                                                

════════════════════════════════════════════════════════════════════════════════

                   v.0.2 -- Copyright October 2015 Kyle Mecklem
                     Creative Commons ShareAlike CC BY-SA 4.0
                     <http://www.geekguild.com/openadventure>

════════════════════════════════════════════════════════════════════════════════


CHAPTER I: INTRODUCTION
────────────────────────────────────────────────────────────────────────────────
If you're reading this, chances are you're a fairly creative person. Perhaps
you've day-dreamed of living out the quests of the arthurian legends. Maybe
you've look upward to the night sky and fantasized what it would be like to
sail amongst the stars or visit an alien world. If so, this game is for you.

OPEN ADVENTURE: Pocket Quest was born out of a love for classic games. A time
when entire adventures of the imagination could take place with a few pages of
rules, some dice and a pencil and paper. In a time when high technology was
still in its infancy and players relied on text-based adventures--like this
one. Players connected to servers via telnet to play games that would display
text-based graphics and rows of imaginative text. These style of games are known
as a Multi-User Domain (MUD). In this interpretation of OPEN ADVENTURE: Pocket
Quest, the adventures can be played with your friends and family like a MUD, but
are primarily designed to be played solo. In this sense, a new term is needed:
Solo-User Domain (SUD). However, this is not a proper definition because this
game can be played by multiple players. For this we need a better, more generic
term: Simple Text Adventure Game (STAG). A STAG can be played either online or
offline, with multiple players or a single player, and can use text-based
visuals and descriptive text.

For this STAG, the UTF-8 character encoding is used throughout. UTF-8 uses 8-bit
code units to store a variable length of characters. In order to use this game,
and for it to display properly, you must have a text-rendering application
that is capable of displaying a monospaced typeface with the UTF-8 character
encoding. It is recomended to display this game with a black or dark background
and a white or light foreground. Because of the encoding standard used through
out this game, the title of the game is:

	OPEN ADVENTURE
	Pocket Quest: 8-Bit Adventures

We can think of 8-Bit Adventures (8BA) as a module to the Pocket Quest. Pocket
Quest is already a stand-alone ruleset playable on a traditional table-top.
Since this STAG uses Pocket Quest for its rule mechanics, it can be thought of
as something you can "plug in" to or "take out" of the main game, as desired.

To keep this file relatively small in bit-size, we will forgo the usual 
pleasantries of the history, philosophy and mission statement of this STAG.
Suffice it to say, if you'd like to learn more about this game, meet fellow
players, game designers and game moderators such as yourself, please visit:

	<http://www.geekguild.com/openadventure>


CHAPTER II: GAME BASICS
────────────────────────────────────────────────────────────────────────────────
8-Bit Adventures is played entirely in Text (TXT) files. A text file is any file
on your computer system that ends with an extension of ".txt", such as this
"README.txt" file. Because 8-Bit Adventures is played entirely through a
text-based medium, it can be played in any traditional text editor, terminal or
command line interface (CLI).

When playing 8BA, There are a few rules that must be followed at all times:

	* At no time can a line of characters (words, sentences, etc.) exceed
	that of	80 characters in width. Most e-mail programs, and many
	terminals and CLIs do not display more characters than this in width;
	resulting in the text to "wrap" to a new line, and thus can break some
	of the maps (maps will be explained later in this game).

	* The individual components of the game (maps, sections, character
	stats, rules and so forth) must be kept in their respective separate
	text files. This allows for players who are using a graphical user
	interface (GUI), or even some specialized CLIs, to open and display
	multiple text documents	simulatiously for quick reference.

	* As the game is played, various aspects of the adventure may change
	the state of an adventure. For example, as rooms are explored the player
	will remove the "?" icons on the floor plan maps. Players must be able
	to change and save certain text files of this game.

	* If two rules directly or indirectly conflict, the more specific
	rule shall take precedence over the broader or more general rule.

	* If an argument arises in which one party or player wishes to complete
	an action but another party or player does not believe the action is
	possible or in the spirit of the rules, and after much thoughtful
	debate, the default conclusion should be that the action cannot be
	completed.

	* When dealing with numeral fractions, always round down to the
	nearest whole number.

	* The rules in this book are simply a framework, not scripture. Any
	part of the rules can be changed or neglected by the adventure
	architect (though any exceptions should be duely noted).

	* When dealing with files and directories, all directories are labeled
	in all-capitalized letters (such as "PLAYER_CHARACTERS"). All files are
	labeled in all lower-case letters (such as "spells.txt"). Multiple
	words should be separated by an underscore ("_"). This file is the only
	file allowed to be an exception to this rule.


FILESYSTEM STRUCTURE
8-Bit Adventures is made up of many different text files stored in various
directories within a computer filesystem. Consult the file tree of the
8-Bit Adventures game below, before playing:

	* README.txt
	* adventure_introduction.txt
	* PLAYER_CHARACTERS
		-> read_first.txt (optional)
		-> blank_character_record_template.txt
		-> player_characters.txt
	* MAPS
		-> read_first.txt (optional)
		-> local_maps.txt
		-> floorplan_maps.txt
		-> settlement_maps.txt
		-> overland_maps.txt
	* ADVENTURES
		-> read_first.txt (optional)
		-> adventures.txt
	* NPCS
		-> read_first.txt (optional)
		-> non-player_characters.txt
	* ITEMS
		-> read_first.txt (optional)
		-> treasure.txt
		-> starting_equipment.txt
		-> weapons.txt
		-> armor.txt
		-> equipment.txt
	* MAGIC
		-> read_first.txt (optional)
		-> spells.txt
		-> psionics.txt

To begin, you should read this "README.txt" file to completion. Afterwards,
open and read the "adventure_introduction.txt" file. This file will have
introduction information and starting instructions written by the person or
persons who designed the adventure--known as the "Adventure Architect" (AA)--you
are about to play. The AA will guide the player through the process of begining
the adventure game. There will also be instructions on which subdirectories
(the "./PLAYER_CHARACTERS", "./MAPS", "./ADVENTURES", "./NPCS", "./ITEMS" and
"./MAGIC" directories) to read, and in which order. Note that there may be
special "read_first.txt" files in each of these sub directories with additional
information and/or instructions that apply to that directory (and all the files
contained within) only. Before beginning play, familairize yourself with the
"adventure_introduction.txt" file and any "read_first.txt" files found through
out the 8-Bit Adventures game.

!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!
!! NOTICE: Do not read any of the other TXT files, either in whole or in      !!
!! part, unless instructed to do so by the adventure architect!! Doing so may !!
!! spoil the secrets and mystery of the adventure!                            !!
!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!!


SECTIONS & LINKS
Text files in 8-Bit Adventures are divided into a series of Sections. A
section is a defined part or area of a text file. TXT files are designed to be
read one section at a time. Each section has a unique Identifer (ID) made up of
a three-digit alphanumeric code (e.g AB3). IDs are encased in a less-than and
greater-than symbol with a forward slash before the code. FOR EXAMPLE, </AB3>.

Sections are connected together through a series of Links. A link is a reference
to another section's ID. Links are encased in less-than and greater-than symbols
similair to a section's ID, but with no forward slash. FOR EXAMPLE, <AB3>. Most
links can only be used once a section has been read, or specific instructions
listed in that section have been followed. FOR EXAMPLE, a section may read "If
you open the oak door in front of you, go to <G20>. If you do not open the door,
go to <64R>." To use a link; invoke a "search and find" command on your computer
and search the current file for the section with the listed ID. FOR EXAMPLE,
if a player were to choose for their character to open the oak door from the
above example, they would search for "</G20>", which would take them to the
section with the same unique identifier.

Some links reference IDs of sections found in other text files. FOR EXAMPLE, a
section within the adventure.txt file may instruct the player to locate a map
found in the floorplan_maps.txt file. Links that reference IDs of different
files will appear the same as a normal link with the addition of a blank space
after the ID followed by the word "file" and an equal sign ("="). An address
(relative to the 8-Bit Adventures game directory) to the referenced file will
be shown encased in quotation marks after the "=" symbol. FOR EXAMPLE,
<F55 file="/ITEMS/treasure.txt">. To use a link of this type, follow the
provided address to the referenced file. Open this file and invoke a "search and
find" command within that file the same as a normal link. Follow all additional
rules concerning this link as if it were a normal link.


REQUIRED MATERIALS
Though this game is meant to be played in cyberspace, you'll still need a few
commonly-found items before playing:

	* Two six-sided dice

	* Several sheets of paper (for taking notes--graph paper works great)

	* A pencil (pens are not recomended because you'll be changing a lot
	of the things you write as the adventure unfolds)

	* A storage medium that will allow you to save the changes you make
	to the game files as you play the game

	* One or two of your friends or family who would like to play 8-Bit
	Adventures with you (optional)


HOW TO USE THE DICE
When referring to dice, an abbreviation is often used. The first number in the
abbreviation is the number of dice being rolled followed by the letter
“d” (shorthand for “die” or “dice”), and then the number of sides the dice
have. FOR EXAMPLE, “5d6” would mean to roll five six-sided dice and add the
total of all the dice rolls together. If a plus (“+”) or minus (“-”) symbol,
followed by a number, are present; this means to add or subtract the number
from the overall total. FOR EXAMPLE, “1d6+3” would mean roll a six-sided die
and add three to the result.

In 8-Bit Adventures, as in each version of OPEN ADVENTURE, you will be asked
to roll dice for various reasons (during combat to determine who wins the
battle, during skill tests to see if you are successful in your attempts, etc.).
These in-game challenges and can be resolved by rolling two six-sided dice of
different colors (preferably one die being white and the other black). The
white or lighter colored die represents positive numbers. The black or darker
die represents negative numbers.

When a character's ability must be tested both dice are rolled at the same
time–but a player only needs to pay attention to the die that rolled the lowest
number.

	* If the lowest number rolled was on the white die, add the number to
	whichever ability is being tested.

	* If the lowest number rolled was on the black die, subtract the number
	from whichever ability is being tested.

	* If the two dice rolls are the same, then there is no lowest number
	and the skill tested is unmodified.

                           STANDARD DICE ROLL RESULTS
                      ╒════╤════╤════╤════╤════╤════╤════╕
                      │ -- │ -1 │ -2 │ -3 │ -4 │ -5 │ -6 │
                      ├────┼────┼────┼────┼────┼────┼────┤
                      │ +1 │ -- │ +1 │ +1 │ +1 │ +1 │ +1 │
                      ├────┼────┼────┼────┼────┼────┼────┤
                      │ +2 │ -1 │ -- │ +2 │ +2 │ +2 │ +2 │
                      ├────┼────┼────┼────┼────┼────┼────┤
                      │ +3 │ -1 │ -2 │ -- │ +3 │ +3 │ +3 │
                      ├────┼────┼────┼────┼────┼────┼────┤
                      │ +4 │ -1 │ -2 │ -3 │ -- │ +4 │ +4 │
                      ├────┼────┼────┼────┼────┼────┼────┤
                      │ +5 │ -1 │ -2 │ -3 │ -4 │ -- │ +5 │
                      ├────┼────┼────┼────┼────┼────┼────┤
                      │ +6 │ -1 │ -2 │ -3 │ -4 │ -5 │ -- │
                      ╘════╧════╧════╧════╧════╧════╧════╛

FOR EXAMPLE, a roll of 5 on the white die and a 2 on the black die would mean a
result of -2 to a skill test. A roll of 1 on the white die and 1 on the black
die would mean a result of +0 to a skill test. A roll of 1 on the white die and
3 on the black die would mean a result of +1 to a skill test.


CHAPTER III: PLAYER CHARACTERS
────────────────────────────────────────────────────────────────────────────────
Players take on the role of an imaginary avatar, known as a Player Character
(PC). Other imaginary characters are known as Non-Player Characters (NPCs) and
are controlled by the rules of this game. A group of characters are known as a
Party.

Copy the blank_character_record_template.txt file and use the copy to make a new
PC (see below for details on the character creation process). Once finished,
rename the file as your character's full name (following the naming conventions
mentioned in chapter 2).

A character has seven Primary Traits:

	* Strength (STR)

	* Perception (PER)

	* Intelligence (INT)

	* Dexterity (DEX)

	* Vitality (VIT)

	* Charisma (CHA)

	* Magic (MAG)

Characters also have 12 secondary traits:

	* Health Points (HP) - Begins game equal to a character's VIT

	* Stamina Points (SP) - Begins game equal to a character's VIT

	* Skills (SKL) - Begins game with a number of skill points equal to a
	character's INT

	* Language Points (LP) - Begins game equal to a character's INT

	* Fortitude Save - Begins game equal to a character's VIT

	* Reflex Save - Begins game equal to a character's DEX

	* Will Save - Begins game equal to a character's INT

	* Melee Attack (MA) - Equal to a character's STR + Weapon Damage (WD)

	* Ranged Attack (RA) - Equal to a character's PER + WD

	* Unarmed Attack (UA) - Equal to a character's DEX

	* Defense (DFS) - Equal to a character's DEX + Armor Toughness (AT)

	* Mana Points (MP) & Psi Points (PSI) - Equal to a character's MAG


PLAYER CHARACTER CREATION
STEP 1: Choose a character Archetype (ARC) and record all of the bonuses and
detriments in your character's character record. Any missing stats should be
counted as a 0 during this step (more points will be added in the following
steps). Optionally, you may choose for your character to Dual-Arch by choosing
two ARCs, halving all bonuses & detriments (rounding down) and combining the
stats together. For mutually-exclusive stats, always choose the more restrictive
of the two.

STEP 2: Choose a race or species from the options listed below. Pick a number of
feats as allowed by the ARC chosen and record all +/- modifiers.

STEP 3: Add 3d6 Character Points (CP) to any of the primary traits in any order.
No primary trait may have less than 1 (MAG exempt) or greater than 10 CP.

STEP 4: Start with 3d6 money (silver coins or star credits known as SC).
Buy weapons, armor & equipment.

STEP 5: Think up a character name, background, profession and personality.


ARCHETYPES
ARCANIST: Perception 4, Intelligence 6, Charisma 4, Magic 6, 5 Feats,
Movement Points (MV) 7, +4 SKL (Intelligence), -2 Stamina Points, gains
1d6-1 HP per Level (LVL) attained.

FIGHTER: Strength 6, Intelligence 4, Dexterity 6, Vitality 4, 4 Feats, MV 5,
gains 1d6+1 HP per LVL attained.

HEALER: Strength 4, Perception 4, Charisma 6, Vitality 6, 4 Feats, MV 4,
+2 SKL (Intelligence), gains 1d6+1 HP per LVL attained.

LEADER: Perception 4, Intelligence 6, Charisma 6, Vitality 4, 4 Feats, MV 6,
+2 SKL (Charisma), gains 1d6-1 HP per LVL attained.

MARKSMAN: Perception 6, Intelligence 4, Dexterity 6, Charisma 4, 3 Feats, MV 8,
gains 1d6 HP per LVL attained.

SCOUT: Strength 4, Perception 6, Intelligence 6, Dexterity 4, 5 Feats, MV 7,
gains 1d6 HP per LVL attained.

WARRIOR: Strength 6, Dexterity 4, Charisma 4, Vitality 6, 3 Feats, MV 5, gains
1d6+2 HP per LVL attained, +2 Power Points (PP) per Attack (ATK), -2 Reflex,
-2 SKL (Intelligence).


RACES & SPECIES
DWARF
Size: Small
Feats Available: Heat Vision, Poison Resistance, Dark Vision, Improved Climb,
Fear Resistance
Bonuses: +4 SKL (Strength), +1 Will

ELF
Size: Medium
Feats Available: Magic Resistance, Heat Vision, Improved Listen, Sprint,
Illusion Resistance
Bonuses: +3 SKL (Dexterity), +2 Language Points (Dwarf), +2 Language Points
(Hobgoblin)
Detriments: -2 SKL (Strength)

HUMAN
Size: Medium
Feats Available: Sprint, Improved Jump, Improved Climb, Improved Swim, Fear
Resistance
Bonuses: +1 SKL (Strength), +3 Language Points (Any), +1 Will

KLANGON
Size: Large
Feats Available: Sprint, Improved Jump, Dark Vision, Fear Resistance, Improved
Climb
Bonuses: +3 Language Points (Megalisk), +2 SKL (Strength), +1 SKL (Perception),
Detriments: -1 Reflex

VULTOSS
Size: Medium
Feats Available: Psionics Resistance, Heal Self, Heat Vision, Illusion
Resistance, Improved Listen
Bonuses: +2 SKL (Charisma), +2 SKL (Dexterity)


FEATS
DARK VISION: You can see in “no illumination” environments as if they were
“partial illumination”, up to 6 spaces away. You cannot see color when using
dark vision.

FEAR RESISTANCE: You have +2 will against fear and charm.

HEAL SELF: Once per day, you may spend a full-turn action to heal a number of
HP equal to your LVL.

HEAT VISION: You can see bodies of heat in “no illumination” and “partial
illumination” environments, up to 6 spaces away. Heat vision cannot be used to
detect cold blooded characters.

ILLUSION RESISTANCE: You can see characters with invisibility up to 6 spaces
away and have +1 to SKL tests vs illusions, save tests vs illusions and DFS vs
illusions.

IMPROVED CLIMB: You have +2 to climb SKL tests and +2 MV when traveling through
vertical terrain.

IMPROVED JUMP: You have +2 to jump SKL tests and +2 to jump distances.

IMPROVED LISTEN: You have +2 to listen SKL tests and +2 to listen distances.

IMPROVED SWIM: You have +2 to swim SKL tests and +2 to MV when traveling
through water terrain.

MAGIC RESISTANCE: You are immune to paralysis and have +2 will vs spells and
abilities that use mana.

POISON RESISTANCE: You have immunity to disease and +1 fortitude vs poison &
paralysis.

PSIONICS RESISTANCE: You are immune to telepathy and have +2 will vs psionics
and abilities that use psi.

SPRINT: Spend 1 SP to gain twice the number of remaining MV until end of turn.


EXPERIENCE LEVELS
Every character starts at level 0. As CHRs collect Experience Points (XP), they
may reach a new LVL after collecting “New LVL^2 x 500” XP. Once a new LVL is
earned, each CHR gains a number of extra HP (according to their chosen ARC),
1d6 extra SKL, and can cast MAG of the same tier or lower as their new LVL.

	EXPERIENCE LEVELS
	╒═══════╤═════════════════╕
	│ Level │ Total XP Needed │
	├───────┼─────────────────┤
	│   0   │ 0 XP            │
	├───────┼─────────────────┤
	│   1   │ 500 XP          │
	├───────┼─────────────────┤
	│   2   │ 2,000 XP        │
	├───────┼─────────────────┤
	│   3   │ 4,500 XP        │
	├───────┼─────────────────┤
	│   4   │ 8,000 XP        │
	├───────┼─────────────────┤
	│   5   │ 12,500 XP       │
	╘═══════╧═════════════════╛

CHAPTER IV: MAPS & SYMBOLS
────────────────────────────────────────────────────────────────────────────────

┌──────────────────────────────────────────────────────────────────────────────┐
│ MAP SYMBOLS & GLYPHS                                                         │
╞═══════════════╤═══════════════╤═══════════════╤═══════════════╤══════════════╡
│ Symbol        │ Local Map     │ Floorplan Map │ Settlement Map│ Overland Map │
├───────────────┼───────────────┼───────────────┼───────────────┼──────────────┤
│ ╔═╦═╗ ╔═══╗   │ Wall          │ Wall          │ Wall          │ Road         │
│ ╠═╬═╣ ║   ║   │               │               │               │              │
│ ╚═╩═╝ ╚═══╝   │               │               │               │              │
├───────────────┼───────────────┼───────────────┼───────────────┼──────────────┤
│ . . . . . . . │ Floor / Square│ --            │ --            │ --           │
│ . . . . . . . │ Grid          │               │               │              │
│ . . . . . . . │               │               │               │              │
├───────────────┼───────────────┼───────────────┼───────────────┼──────────────┤
│ . . . . . . . │ --            │ --            │ Grass /       │ Grassland /  │
│  . . . . . .  │               │               │ Hexagon Grid  │ Hexagon Grid │
│ . . . . . . . │               │               │               │              │
├───────────────┼───────────────┼───────────────┼───────────────┼──────────────┤
│    ? or (?)   │ Mystery       │ Undiscovered  │ Undiscovered  │ Undiscovered │
│               │               │ Room          │ Building      │ Landmark     │
├───────────────┼───────────────┼───────────────┼───────────────┼──────────────┤
│   [#] or #    │ Portcullis or │ Portcullis or │ --            │ --           │
│               │ Gate          │ Gate          │               │              │
├───────────────┼───────────────┼───────────────┼───────────────┼──────────────┤
│ [Ʌ] and [V]   │ Stairs Up &   │ --            │ --            │ --           │
│               │ Stairs Down   │               │               │              │
├───────────────┼───────────────┼───────────────┼───────────────┼──────────────┤
│ Ʌ, V, < and > │ One-way       │ One-way       │ --            │ --           │
│               │ Passage       │ Passage       │               │              │
├───────────────┼───────────────┼───────────────┼───────────────┼──────────────┤
│       ǂ       │ Tree          │ --            │ Tree          │ Tree         │
│               │               │               │               │              │
├───────────────┼───────────────┼───────────────┼───────────────┼──────────────┤
│ [D], {D}, {L},│ Normal, Stuck,│ --            │ --            │ --           │
│ [S]           │ Locked and    │               │               │              │
│               │ Secret Door   │               │               │              │
├───────────────┼───────────────┼───────────────┼───────────────┼──────────────┤
│       O       │ Large Stone   │ --            │ --            │ --           │
├───────────────┼───────────────┼───────────────┼───────────────┼──────────────┤
│      (F)      │ Fountain      │ --            │ Fountain      │ --           │
├───────────────┼───────────────┼───────────────┼───────────────┼──────────────┤
│       Ψ       │ Useful Item   │ Useful Item   │ Useful Item   │ Useful Item  │
├───────────────┼───────────────┼───────────────┼───────────────┼──────────────┤
│       X       │ Your PC       │ Your PC       │ Your PC       │ Your PC      │
├───────────────┼───────────────┼───────────────┼───────────────┼──────────────┤
│ ╔─═─═─═─═─═─╗ │ Crenelated    │ Crenelated    │ Crenelated    │ --           │
│ ╚─═─═─═─═─═─╝ │ Wall          │ Wall          │ Wall          │              │
├───────────────┼───────────────┼───────────────┼───────────────┼──────────────┤
│       ░       │ Quicksand     │ --            │ Quicksand     │ Desert       │
├───────────────┼───────────────┼───────────────┼───────────────┼──────────────┤
│       ▒       │ Swamp / Marsh │ --            │ Swamp / Marsh │ Swamp / Marsh│
├───────────────┼───────────────┼───────────────┼───────────────┼──────────────┤
│       ▓       │ Ice           │ --            │ Ice           │ Ice          │
├───────────────┼───────────────┼───────────────┼───────────────┼──────────────┤
│      [∆]      │ Trap Door     │ --            │ --            │ Settlement   │
├───────────────┼───────────────┼───────────────┼───────────────┼──────────────┤
│       Ω       │ Altar / Shrine│ --            │ --            │ --           │
├───────────────┼───────────────┼───────────────┼───────────────┼──────────────┤
│     ≈ or ~    │ Water or Lava │ --            │ Water or Lava │ River / Sea  │
├───────────────┼───────────────┼───────────────┼───────────────┼──────────────┤
│    † or [†]   │ Grave Site or │ --            │ Grave Site or │ Grave Site   │
│               │ Sarcophagus   │               │ Sarcophagus   │ or Tomb      │
├───────────────┼───────────────┼───────────────┼───────────────┼──────────────┤
│   ¡ and Ж     │ Torch and Lamp│ --            │ --            │ --           │
├───────────────┼───────────────┼───────────────┼───────────────┼──────────────┤
│ ┌─┬─┐ ┌───┐   │ Miscellaneous │ Miscellaneous │ Miscellaneous │ Miscellaneous│
│ ├─┼─┤ │   │   │               │               │               │              │
│ └─┴─┘ └───┘   │               │               │               │              │
├───────────────┼───────────────┼───────────────┼───────────────┼──────────────┤
│   (!) or !    │ Quest Item    │ Quest Item    │ Quest Item    │ Quest Item   │
├───────────────┼───────────────┼───────────────┼───────────────┼──────────────┤
│          ║    │ Weak Wall     │ --            │ --            │ --           │
│   ═Z═ or N    │               │               │               │              │
│          ║    │               │               │               │              │
├───────────────┼───────────────┼───────────────┼───────────────┼──────────────┤
│      (¤)      │ Pit           │ --            │ Pit           │ --           │
├───────────────┼───────────────┼───────────────┼───────────────┼──────────────┤
│     + or ±    │ Holy Symbol   │ --            │ --            │ --           │
│               │ and Spellbook │               │               │              │
├───────────────┼───────────────┼───────────────┼───────────────┼──────────────┤
│ ≠ or T or (T) │ Trap          │ Trap          │ --            │ --           │
├───────────────┼───────────────┼───────────────┼───────────────┼──────────────┤
│    $ or [$]   │ Treasure and  │ Treasure and  │ --            │ --           │
│               │ Treasure Chest│ Treasure Chest│               │              │
├───────────────┼───────────────┼───────────────┼───────────────┼──────────────┤
│       λ       │ --            │ --            │ --            │ Mountain     │
├───────────────┼───────────────┼───────────────┼───────────────┼──────────────┤
│     Ξ or Ш    │ Bridge        │ --            │ --            │ Bridge       │
├───────────────┼───────────────┼───────────────┼───────────────┼──────────────┤
│       Ų       │ --            │ --            │ --            │ Canyon       │
├───────────────┼───────────────┼───────────────┼───────────────┼──────────────┤
│  «A» to «Z»   │ NPC           │ --            │ --            │ ---          │
├───────────────┼───────────────┼───────────────┼───────────────┼──────────────┤


00000000001111111111222222222233333333334444444444555555555566666666667777777777
01234567890123456789012345678901234567890123456789012345678901234567890123456789
════════════════════════════════════════════════════════════════════════════════
≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈
≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈
≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈.λ. . . .≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈
≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈. .ǂ. .ǂ.λ.ǂ. .λ.λ.λ.λ.(?).ǂ.ǂ.λ.ǂ.≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈
≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈.ǂ.ǂ.λ.λ.ǂ╔═[∆]λ.λ.λ.≈≈≈≈λ.ǂ.ǂ.ǂ.λ.ǂ.≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈
≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈. .ǂ.ǂ.λ.ǂ.║.ǂ.λ.λ.λ.λ.λ.λ.λ.ǂ.λ.ǂ.λ.ǂ.ǂ.≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈
≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈.λ. . .ǂ.λ.ǂ╚═╗ǂ. .λ.λ.λ.λ.λ. .ǂ.λ.ǂ. .ǂ.≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈
≈≈≈≈≈≈≈≈≈≈≈≈≈≈.ǂ.λ. . . .ǂ. . .║. .λ.λ.λ.▒.λ. .λ. .ǂ.λ.ǂ.λ.ǂ.λ.≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈
≈≈≈≈≈≈≈≈≈≈≈≈≈.ǂ.λ. . . . . . . ╠═══╗ .≈.λ.▒.▒.▒.▒.ǂ. .ǂ.λ.λ.λ.λ. .λ.≈≈≈≈≈≈≈≈≈≈≈≈
≈≈≈≈≈≈≈≈≈≈≈≈.ǂ. .λ. . . . . . .║. .╚═Ξ═╗.▒. .▒. .ǂ.ǂ. .λ.λ.λ.λ.ǂ. .λ.≈≈≈≈≈≈≈≈≈≈≈
≈≈≈≈≈≈≈≈≈≈≈≈≈.λ. .ǂ. . . . ╔═══╝ . .≈≈ ║▒.▒.▒.▒. ╔═══[∆]λ.λ.λ.λ.ǂ.λ.≈≈≈≈≈≈≈≈≈≈≈≈
≈≈≈≈≈≈≈≈≈≈≈≈.λ.ǂ. . . .╔══[∆] . . . ≈≈.╚═╗.▒.▒. .║. . .ǂ.λ. .λ.λ.λ.≈≈≈≈≈≈≈≈≈≈≈≈≈
≈≈≈≈≈≈≈≈≈.λ. .λ. ╔═════╝ . . . . .≈≈≈. . ╚═══════╝ .ǂ. . . . . .▒.▒.≈≈≈≈≈≈≈≈≈≈≈≈
≈≈≈≈≈≈≈≈. .λ.λ. .║. . . . . . . .≈≈ . . . . .ǂ. . . . . .ǂ. . .▒.ǂ.≈≈≈≈≈≈≈≈≈≈≈≈≈
≈≈≈≈≈≈≈≈≈.λ.λ. . ║ ≈≈≈≈≈ .ǂ. . . .≈. . . .ǂ.ǂ. . . . . . . . . .≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈
≈≈≈≈≈≈≈≈≈≈.λ.λ. .║≈≈≈▒≈≈≈ .ǂ. . .≈. . .ǂ.ǂ.ǂ.ǂ.ǂ.ǂ. . . .≈≈≈≈ .ǂ.≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈
≈≈≈≈≈≈≈≈≈. .λ. . ║ .▒.▒.ǂ. . . . ≈≈. .ǂ.ǂ.ǂ.ǂ.ǂ. . . . . ≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈
≈≈≈≈≈≈≈≈≈≈. .λ.λ.╚═╗.▒.▒. . . .≈≈≈. .ǂ.ǂ.ǂ.ǂ.ǂ. .ǂ. . . . . .≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈
≈≈≈≈≈≈≈≈≈.λ.λ. .λ. ║ . . . . .≈. .≈.ǂ.ǂ╔═══[∆]ǂ.ǂ.ǂ. . . . . .≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈
≈≈≈≈≈≈≈≈. .λ.λ. . .║. . .ǂ. .≈≈ ╔══Ξ═══╝.ǂ.ǂ.ǂ.ǂ.ǂ. . . . . . .≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈
≈≈≈≈≈. .λ.λ.λ.λ. . ║(?). . . . .║. .≈.ǂ.ǂ.ǂ.ǂ.ǂ.ǂ.ǂ.▒. . . .ǂ.ǂ.≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈
≈≈≈≈.λ.λ.λ. .λ. . .╠═══════╦════╝ .ǂ.≈.ǂ.ǂ.ǂ.ǂ.ǂ.ǂ. .ǂ.▒. . .ǂ.≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈
≈≈≈≈≈≈(?).λ.λ.λ.λ. ║ . . . ║ . . . .ǂ.≈.ǂ.ǂ.ǂ.ǂ.ǂ.ǂ. . .▒. . . . .≈≈≈≈≈≈≈≈≈≈≈≈≈≈
≈≈≈≈≈≈.λ.λ[∆]╗.λ. .║. . . .║. . . . .≈≈≈≈ .ǂ. .ǂ. .▒. .▒. . . . . .≈≈≈≈≈≈≈≈≈≈≈≈≈
≈≈≈≈≈≈≈.λ. .λ╚═════╝ . . . ╚══╗. . .≈≈≈≈≈. . . .ǂ. .▒. . . . ≈≈≈≈. . .≈≈≈≈≈≈≈≈≈≈
≈≈≈≈≈≈≈≈.λ.λ.λ.λ. . . . . . . ║ . . . . . . . . . .▒. . . . . . ≈≈. . .≈≈≈≈≈≈≈≈≈
≈≈≈≈≈≈≈≈≈.λ. .λ.λ.ǂ. . . . . .╚══╗ . . . . . . . . . . ╔══════╗.≈≈≈. .≈≈≈≈≈≈≈≈≈≈
≈≈≈≈≈≈≈≈. .λ. .λ.ǂ. . . .ǂ. . . .║. . . . . . . . . . .║. . . ║ . ≈≈≈≈≈≈≈≈≈≈≈≈≈≈
≈≈≈≈≈≈≈≈≈≈≈. . .λ.λ. . .ǂ.ǂ. . . ║ . . .ǂ. . . . . . . ║ . ≈≈.╚[∆]≈≈≈≈≈≈≈≈≈≈≈≈≈≈
≈≈≈≈≈≈≈≈≈≈≈≈.λ.λ. . . .ǂ.ǂ.ǂ. . .║. . .ǂ.ǂ. . . . . . .║. . ≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈
≈≈≈≈≈≈≈≈≈≈≈.λ.λ. .λ. .ǂ. . . . . ╚═══════╦═════════════╣ . . .≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈
≈≈≈≈≈≈.ǂ.≈≈≈. .λ. .λ. .ǂ. . . . . . . .ǂ[∆] . . . . . .║. . . . . .≈≈≈≈≈≈≈≈≈≈≈≈≈
≈≈≈≈≈.ǂ.ǂ.≈≈≈. .λ.λ.λ. . . . . . .ǂ.≈≈≈≈≈≈≈≈≈≈ . . . . ║ . . . . . .≈≈≈≈≈≈≈≈≈≈≈≈
≈≈≈≈≈≈.ǂ.ǂ.≈≈≈≈≈. . . . . . . . . ≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈ . . .║. . . . . . . .≈≈≈≈≈≈≈≈≈
≈≈≈≈≈≈≈.ǂ.ǂ.≈≈≈. . . .░. . . . . ≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈ . . ║ . . . . . . .≈≈≈≈≈≈≈≈≈≈
≈≈≈≈.ǂ.ǂ. .ǂ. . . . .░. .░. . . . .≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈ . .╚═══╗. . . . .≈≈≈≈≈≈≈≈≈≈≈
≈≈≈. . . . . . . .░.░.░.░. . . . .≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈ . . . ║ . . . . .≈≈≈≈≈≈≈≈≈≈
≈≈. . . . . . .░.░. .░.░.░. . . . .ǂ.≈≈≈≈≈≈≈≈≈≈≈≈ . . . . .║. . . . . .≈≈≈≈≈≈≈≈≈
≈≈≈. . . . .░. .░. .░.░. . . . . .≈≈≈≈≈≈≈≈≈≈≈≈≈≈ . . . . . ║ . .░. . .≈≈≈≈≈≈≈≈≈≈
≈≈≈≈. . . . .░. .░.Ų. .░.░.░. . . .≈≈≈.≈≈≈≈≈≈ . . . . . . .║. .░. . . . .≈≈≈≈≈≈≈
≈≈≈≈≈. . . .░.Ų.░.Ų. .░. . .░. . . .≈≈≈≈≈≈ .ǂ.ǂ. . . . . . ║ . .░.░. . . .≈≈≈≈≈≈
≈≈≈≈≈≈. . .░. .Ų.Ų.░.≈.░. . . . . . . ≈≈≈ .ǂ. . . . . . . .║. .░. . . .≈≈≈≈≈≈≈≈≈
≈≈≈. . . . .░.░.Ų.Ų.░.░.░. . . . . . .ǂ.≈≈≈. . . .░.░. . . ║ .░.░. . . .≈≈≈≈≈≈≈≈
≈≈. .λ. . . . .░.░.Ų.Ų.░.░. . .ǂ. .ǂ.ǂ.≈≈≈. . . . .░.░. . .║. . . . . . . .≈≈≈≈≈
≈. .λ. . . . . .░.Ų.Ų.░.░. . . . .ǂ.ǂ.≈≈≈. . . . .░. .░. . ║ . . . . .≈≈≈≈≈≈≈≈≈≈
≈≈. .λ. . . . .░.Ų.Ų.░. . . . . . . .≈≈≈. . .ǂ. .░. . . . [∆] . . . .≈≈≈≈≈≈≈≈≈≈≈
≈≈≈.λ.ǂ. . . . . .░.Ų.Ų.░. . .≈≈≈. . .≈≈≈. . . . .░.░. . . . . . . .≈≈≈≈≈≈≈≈≈≈≈≈
≈≈≈≈.λ.ǂ. . . . . .░.Ų.░. . . .≈≈≈≈ .≈≈≈≈ . . . .░. . . . . . . . . . .≈≈≈≈≈≈≈≈≈
≈≈≈.λ.λ.ǂ. . . . . . .Ų.░. .ǂ. . .≈≈≈.ǂ.≈≈≈. . . . . . . . . . . . . . .≈≈≈≈≈≈≈≈
≈≈≈≈.λ. . . . . . . . . . . .ǂ. .≈≈≈≈≈≈≈≈≈. . . .ǂ. . . . . . . .ǂ.≈≈≈≈≈≈≈≈≈≈≈≈≈
≈≈≈≈≈. . . . . . . . . . . . .ǂ.ǂ.ǂ.≈≈≈. . . . . . . . . . . . .ǂ.≈≈≈≈≈≈≈≈≈≈≈≈≈≈
≈≈≈≈. . . .ǂ. . . . . . . . . .ǂ.ǂ.≈≈≈. . . . . . . . . .≈≈≈.ǂ.ǂ.≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈
≈≈≈. . .ǂ. . .ǂ. . .ǂ. . .λ. . . . .≈≈≈. . . . . .≈≈≈≈≈≈≈≈≈.ǂ.≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈
≈≈≈≈. . . .ǂ.▒.▒.▒. . . . .λ. . .λ. .≈≈≈. . . . .≈≈≈≈≈.ǂ.≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈
≈≈≈. . .ǂ.▒.▒.▒.▒.▒.ǂ. . . .λ.λ.λ.λ. .≈≈≈. . . . . .≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈
≈≈≈≈. . .▒. .▒.▒.▒. . .▒.▒. . .λ. .λ. .≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈
≈≈≈≈≈. .▒.▒(?)▒.▒.▒.ǂ. .▒. . .λ. .λ.≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈
≈≈≈≈. . .▒.▒.ǂ.▒.ǂ.ǂ.ǂ. . . . . .λ. .≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈
≈≈≈≈≈.ǂ.ǂ.▒.▒.▒.▒.ǂ. .ǂ. . . .λ.λ.≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈
≈≈≈≈.ǂ.ǂ.ǂ.▒.ǂ.▒.▒. . . . .λ.λ. . .≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈
≈≈≈≈≈.ǂ. .ǂ. . . . . . .λ.λ. .≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈
≈≈≈≈≈≈.ǂ.ǂ.▒. .▒.▒. . .λ.≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈
≈≈≈≈≈. .ǂ. . .▒. . . .≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈
≈≈≈≈.ǂ.ǂ.ǂ[∆]▒. .≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈
≈≈≈.ǂ.ǂ.ǂ. . . .≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈
≈≈≈≈≈≈. . . .≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈
≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈
≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈
 . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . .
. . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . . 



Riverport

. . . . . . . ≈≈≈ . . . . . . . . . . . . . .│. . . . . . . . . . . . . . . . . 
 .╔─═─═─═─═─═─═≈≈≈─═─═─═─═─═─═─═─═─═─═─═─═╗. │ ╔═─═─═─═─═─═─═─╗. . . . . . . . .
. │ . . . . . . ≈≈≈ . . . . . .ǂ.ǂ. . .ǂ. ╚─[#]╝. . . . . . . │ . . . . . . . . 
 .║. . . . . . .≈≈≈. . . . . . .ǂ. . . . . . │ . . . . . . . .╚═─═─╗ . . . . . .
. │ . .ǂ. . . . .≈≈≈. . . . . . . . . . . . .│. . . . . . . . . . .│. . . . . .
 .║. . . .ǂ. . . ≈≈≈ . . . . . . . . . . . . │ǂ. . . . . . . . . . ╚═─╗. . . . .
. │ . . . . . . . .≈≈≈. . . . . . [∆] . .ǂ.ǂ.│.ǂ. . . . . . .ǂ.ǂ.ǂ. . │ . . . . 
 .║. . .┌───────────ΞΞΞ──────────────────────┴───────┐ . . . . .ǂ. . .╚═─═─═─╗ .
. │ . . │[∆]. . . . .≈≈≈. . . . . . . . . .ǂ.ǂ.ǂ. . .└───┐. . . . . . . . . .│. 
 .║. . .│. . . . . . .≈≈≈≈ . . . . . . . .ǂ.ǂ.ǂ.ǂ. . . . │ . . . . . . . . . ║ .
. │ . . │ . . . . . ≈≈≈ǂ.ǂ≈≈≈ . . . . . . .ǂ.ǂ. . . . [∆]│. . . . . . . . . .│.
 .║. . .│. . . . . ≈≈.ǂ. .ǂ≈≈≈ . . . . . .ǂ. .ǂ. . . . . └────┐. . . . . . . ║ .
. │ . . │ . . . . ≈≈.ǂ.ǂ. .ǂ≈≈≈ . . . . .ǂ. . . . . . . . . . │ . . . . . . .│. 
 .║. . .│. . . . . ≈≈.ǂ. ≈≈. ≈≈≈ . . . . . . . . . . . . . . .│. .ǂ. . . . . ║ .
. │ . . │ . . . . . .≈≈≈. .≈≈≈.≈≈≈. . . . . . . . .ǂ. . . . . │ . . . . . . .│. 
 .║. . .└───┐. . . . . . . . . . ≈≈≈≈≈≈. . . . . . . . . . . .│[∆] . . . . . ║ .
. │ . . . . │ . . . . . . . . . . . ≈≈≈ . . . . . . . . . . . │ . . . . . . .│.
 .╚─═╗ . . .│[∆] . . .[∆]. [∆] . . . ≈≈≈ . . . . . . . . . . .│. . . . . .╔─═╝ .
────[#]─────┼─────────────(F)─────────ΞΞΞ─────────────────────┼──────────[#]─── 
 .╔─═╝ . . .│. . . . . . . . . [∆] . .≈≈≈. . . . . . . . . . .│. . . . . .╚─═╗ .
. │ . . . . │ . . . . . . . . . . . .≈≈≈. . . . . . . . . . . │ . . . . . . .║. 
 .║. . . . .│.ǂ.ǂ. . . . . . . . . . ≈≈≈ . . . .ǂ.ǂ.ǂ. . . . .│[∆] . . . . . │ .
. │ . . .ǂ.ǂ│ǂ.ǂ.ǂ. . . . . . . . . . ≈≈≈ . . .ǂ.ǂ. .ǂ. . .┌──┘ . . . . . . .║.
 .║. . . .ǂ.└──────┐ . . . . . . . .≈≈≈. . . . .ǂ. . .ǂ. . │ . . . . . . .ǂ.ǂ│ .
. │ . . . . . . . .│. . . . . . . ≈≈≈ . . . . . . .ǂ.ǂ. . .│. . . . . .ǂ.ǂ. .║. 
 .║. . . . . .ǂ. . │ . . . . . ≈≈≈ . . . . . . . . . ┌─────┘ . . . . . .ǂ. . │ .
. │ . . . . . . . .└───┐. . . ≈≈. . . . . . . . . . .│. . . . . . . . . .╔─═─╝. 
 .║. .ǂ.ǂ.ǂ.▒. . . . . │ . .≈≈≈. . . . . . . . . .[∆]│†.†.†. . . . . . . │ . . .
. │ .ǂ.ǂ.ǂ.▒.▒. . . [∆]│. . ≈≈≈ . . . . [∆] . . . . .│.†.†.†. . . . . . .║. . .
 .║. .ǂ. .ǂ.ǂ. . . . . └────ΞΞΞ────┬────────────┬────┘†.†.†. . . . . . . │ . . .
. │ǂ.ǂ.ǂ. .ǂ.ǂ.▒.▒. . . . .≈≈≈. . .│. . . . . . │ . . . . . .ǂ.ǂ.ǂ. . . .║. . . 
 .╚─═─═─═─═╗ . .▒.▒. . . ≈≈≈ . . . │ (?) . [∆] .│. . . . . .ǂ.ǂ. .ǂ.ǂ. . │ . . .
. . . . . .│. .▒.▒.▒. .≈≈≈. . . . .└─ΞΞΞΞΞΞΞΞΞΞ─┘ . . . . . . . . .ǂ. . .║. . . 
 . . . . . ╚─═─═─═─═≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈ . . . . . ≈≈≈≈≈≈│ . . .
. . . . . . . . ≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈≈. . .
Map Legend
≈ = Water
▒ = Marsh
ǂ = Trees
Ξ = Bridge / Dock
(F) = Fountain
. . . = Hex Grid (100 m)
────┬─ = Road
═─═─═─═ = Crenelated Wall
[∆] = Building
(?) = Unexplored Building
[#] = Gate



        A
      ╔╝ ╚╗
      ║ ? ║
      ╚╗ ╔╝
╔═══╗_╔╝ ╚╗_╔─═─╗
║ X  _  ?  _  ? │
╚╗ ╔╝ ╚╗ ╔╝ ╚─═─╝
╔╝ ╚╗_╔╝ ╚╗_╔═══╗_╔═══╗_   A = North Entrance
║ ?  _  ?  _  ?  _  ?  _B  B = East Entrance
╚═══╝ ╚╗ ╔╝ ╚═══╝ ╚═══╝    C = South Entrance
╔═══╗_╔╝ ╚╗_╔═══╗
║ ?  _  ?  _  ? ║
╚═══╝ ╚╗ ╔╝ ╚═══╝
      ╔╝ ╚╗
      ║ ? ║
      ╚╗ ╔╝
        C


╔═══Z═══════╗    
║. . .Ж.Ω.Ж.║
║. . . .X. .╚═════
║. .T. . . . > . . 
S} . «D» . .╔═════
║. . . . . .║
╚═══╗[∆]╔═══╝





