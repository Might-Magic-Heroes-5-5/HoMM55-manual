# Heroes of Might and Magic 5.5 manual

Open source manual for [Might & Magic: Heroes 5.5 mod](http://www.moddb.com/mods/might-magic-heroes-55).

Written on Ruby with [Shoes 3.3.7 framework](http://walkabout.mvmanila.com)

Latest version: [1.3 with MMH55 RC12b database](https://www.moddb.com/mods/might-magic-heroes-55/downloads/mmh55-reference-manual-rc12b)
 
## Repository files

**main.rb** - application code

**changes.txt** - tracker of release changes.

**text** - text descriptions only

**pics** - images only

**settings**

 **-> skillwheel.db** - MMH55 game information
 
 **-> app_settings.db** - keeps contants related to the app behaiour (resolution, default language)
 
 **-> fonts** - includes app fonts
 
**code** - some auxiliary code (Tooltip - popup functionality; readskills.rb - used for reading text files)

These are all the files the manual is built from.

Author: Dredknight.


## Release changes

version 1.3
added - spell pane - Spells that have mass version now include mass mana cost
added - spell pane - Spell formula description
removed - town pane - Note about Grypn dive + chain attack bug.


version 1.2
added - spell pane - Spells that can be Empowered now include empowered damage and mana stats.
added - spell pane - The 8th slot now presents magic guild summoning and formulas for each creature.
added - spell pane - Adventure pane now includes "Town Management" skill variations.
added - town pane - Bloodrage skill description.
added - town pane - Magic guild creature summoning and dragon blood description.
changed - town pane - highlights are rearranged into more meaningful manner.
fixed - hero pane - Betrand moved from Knights to Renegade class.
fixed - hero pane - Betrand does not have Curse spell.
fixed - hero pane - Iron Lord/Maiden spec description.
fixed - hero pane - teleport assault description.
fixed - hero pane - Barbrian classes "Khan" and "Veteran" buttons hover now has subtext referring to having access to 13 skills.
fixed - global - Fonts issues for english and russian.
fixed - artifact pane - axe of mountain lords description.
fixed - artifact pane - mini artifacts values now present the current game values.

version 1.1
added - artifact pane - The knowledge value at the moment of forging is now shown in the forged micro artifacts in brackets.
added - artifact pane - Artifact cost is now shown in brackets next to its name.
added - spell pane - better curse and bless hover description as well as prediction vs spellpower.
added - hero pane - Delete button added. The user can remove hero profiles from the "Choose a preset" pane.
added - town pane - "Duel mode" and "Known issues" sections.
added - town pane - Ability to change the size of the app size to fit laptop resolution (requires a restart) so it can fit laptop screens.
added - town pane - Ability to change application language
added - town pane - added a preview of for "Duel Mode" and new category for known ToTe issues that may cause game inconsistencies.
changed - global - right clicking on attributes that can be edited by the user now increase by 10 instead of being reduced by 1.
changed - global - Vivaldi font was changed with for 1-Vivaldi because it did not support cyrillic letters.
changed - global - font settings can be changed according to the loaded language pak. The settings are found in PROPERTIES directory of the pak file.
changed - global - minor design adjustments so the app items do not look ugly based on language text length.
changed - spell pane - Spell/Warcries/Rune data visualization is now presented into more pragmatic and visually pleasing way.
fixed - spell pane - Warcries clicked information was wrong.
fixed - spell pane - % values no longer go negative or above 100% (ressurect, raise dead, curse, bless, forgotfulness, celestial shield, deflect arrows) except where it is valid in the game formula.
fixed - spell pane - Conjure phoenix description and prediction is now shown properly when clicked/hovered.
fixed - spell pane - fire trap damage and mine count were reversed
fixed - creature pane - portraits for some creatures were inversed (Wyvern and the Foul Wyvern, and the Spectre and the Ghost, Djinn and Djinn Sultan)
fixed - hero pane - text was not displayed properly on the "save hero" tooltip.
