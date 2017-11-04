# Eastern-Sun-Rises

[size=150][b][CHANGELOG 4.2] [/b][/size]

-disabled wisdom and identify scrolls, keys, stamina, antidote and thawing pots to drop after Normal difficulty
-disabled all throwing pots to drop after Normal difficulty
-reduced droprate for health/mana pots in Nightmare (~50%) and Hell difficulty (~70%)
-disabled normal gems to drop after Nightmare difficulty
-lowered the chance to drop arrows and bolts, but increased the chance to drop rare and unique versions (in Nightmare and Hell)
-slightly increased the chance to drop higher tier weapons/armors 
-limited another tier of low level affixes for armors and wepaons to a certain lvl range, will slightly improve magic/rare drops in Nightmare and Hell
-Kanji runes needing only 1 crystal instead of 2 (except God and Heaven runes)
-added fixes for various Vanilla bugs (thanks to LastCorpse)
-added Gold Pickup.dll (thanks to MW95)
-added Statfix.dll to fix caps on life, mana and stamina
-reworked Damage Augmenter  (Strength of the Ancients, Vigor of the Ancients and Iron Skin dont need Damage Augmenter anymore)
-removed Barbarian Passive 
-removed all item color transformations for rings and amulets (also removes some color transformations for other items, as they shared suffixes/prefixes)
 (to undo this change simply replace the MagicPrefix.txt and MagicSuffix.txt)
-added 112 new jewelry graphics and replaced all old ones
-fixed a bug with Fire Mastery
-changed Questskillrewards back to 2,2,3
-added new stats to Plugystatscreen
-fixed Maul Synergies
-improved Synergies for Shockwave, Hunger(20%) and Maul(20%)
-changed SWearbear to be a Druid Skill (added 6 Dummy Skills for other classes), added skillicon 
-changed the FoH skillrequirements, no longer requires Hyno Blast.
-reduced the manacost of Bone Wave, Multishot and Poison Nova by approximately half
-increased damage for vampires from (0,0,1,2,3,3 per lvlrange to 1,1,2,3,4,4)
-fixed Inner Sight -% Damage Reduce, technically it is working as a curse now, so it can overwrite or
 be overwritten by such
-fixed Sway Defense%, removed Snynergies 
-added CustomTbl Plugin
-added 8 Hidden Treasures, they already spawn with the forged flag and can't be unforged
-you won't be able to max out skills until level 95, on the upside the 
 maxlevel is increased by 1 for every skill once you reach level 100
-slightly increased the dropchance for Hidden Treasures
-reworked parts of the User Interface, to disable go to the frontend folder in Data\Global\UI,
remove all files and restore the file in the old folder, next remove the charselect folder
-renamed two area's in act 5 to give credits to Tsuru and Perfect Cell
-attempted to fix the manaburn bug
-added D2AnimatedItems.dll
-added Hellfire Torch (monster specific drop)
-reworked revieve code, playability should be much higher now
-fixed a bug in shadow masters attack behaviour 
-fixed mercenary running animation
-added dragonflight animations

[size=150][b][CHANGELOG 5.1] [/b][/size]

-changed modname to Eastern Sun Rises
-replaced a few diablo 1 item gfx with updated versions from ogodei
-fixed UI background
-added a Buff/Debuff Overlay (all shrines share the same skillicon)
-added D2BuffIcons.dll
-increased the dropchance for the hellfire torch (for now only Diablo in hell act4 can drop it)
-fixed some minor gfx problems in some jwewels/amulets
-removed the tokenizer(for a) reduce the size of the debuglog.txt, b) we have plugy anyway and 
 c) if this ever go on any server, it will also help preventing from crashing)
-Items will now show how mnany Tinkerpoints are left
-replaced the MercMod.dll with the ExtendedMerc.dll, which should fix the following bug: 
 "If you give them the 2nd sword, it's lost forever", 
 however this limits the act5 merc to 1 1h/2h sword and he wont be able to wield shields anymore
-lowered the chance for several less wanted Oskill suffixes to spawn
-changed ctc suffixes to be a little more steady and higher
-added ctc suffixes for Decrepify, Lower Resist and Pierce Flesh and Bone (all curses are also now on their own suffix group)
-all ctc curses suffixes can now only spawn on weapons
-Lower Resist and Pierce Flesh and Bone are less likely to spawn than the other two
-magic and rare armors can now spawn with 2 all skills and 1-2 char skills
-armors can now roll a higher enhanced defense roll
-added a new group of prefixes for armors (find out yourself)
-added D2Dyes.dll
-removed all char/inv color transformations from affixe/uniques and sets
-added 21 new pots to color items in whatever color you like
-fixed various strings
-replaced a few baseitem gfx

Added the D2AnniversaryUIPlugin by Lurix. To disable remove the PANEL folder in Data\Global\UI.
Added a new Font by thanosdk. To disable remove the font folder in Data\Local.
Added parts of the HU Improved FX MKII by PureRage. To disable remove the levels.txt in Data\Global\Excel.
Included Ogodei's Autumnal Theme for the current patch. To disable remove the folder Tiles in Data\Global.

