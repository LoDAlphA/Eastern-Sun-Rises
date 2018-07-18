[INSTALLATION] 

Step 1: Install the ES Com version which can be found on the Snejportal.
Step 2: Remove all Tokens, Weapons with Quantity, Keys, Tome of Townportal,Tome of Identify
 and Items with Selfrepair Itemstat (if you wanna keep all items with Quantity, 
 go to D2Mod.ini and change SaveBits=14 to SaveBits=9. However, 
 you wont be able to play with people who have a different value.)
Step 3: Copy all files from this folder directly into the ES Com folder. You should overwrite some files.
Step 4: Remove Utility.dll, D2AnimatedItems.dll and Statfix.dll (from previous patches)
Step 5: If you can load your Character, delete the charname.d2x file
Step 6: Replace all Damage Augmenters with new ones

[Important] 

-SINGLEPLAYER ONLY
-FULLY COMPATIBLE WITH PREVIOUS VERSIONS IF YOU FOLLOW STEP 2

[AUTOPICK- AUTOCUBE PLUGIN]

You can find all necessary informations on the following website: 
https://sites.google.com/site/madbrahmin/d2es

Beware that it is neither allowed to talk about this @Phrozenkeep or @Snej. So if you run into any
trouble setting it up PM me on either. I warned you.

As the current version feature the bufficon overlay and d2dye system which both are NOT compatible with D2Loader.
I recommend to stop using it and load the D2HackIt.dll and nohide.dll via D2Mod or Plugy by adding D2HackIt=D2HackIt.dll 
and nohide=nohide.dll for NON D2SE Users.D2SE Users can use the D2SE_Setup.ini by adding ModDll1=D2Hackit.dll 
and ModDll2=nohide.dll. You will need to place both dlls and the d2hackit.ini in your ES Main folder. 
The rest can stay in the plugin folder.

If you keep using the loader, you need to prevent D2Mod loading the bufficons.dll and d2dyes by removing the following lines: 
D2BuffIcons=D2BuffIcons.dll
D2Dyes=D2Dyes.dll

In order to run your game with Gilde and this Plugin you need to add -w to your shortcut. 
("...Diablo II.exe" -txt -direct -glide). 

I won't add any of the required files into this patch, but with the informations provided above you
should be able to do so yourself.  

[PLUGY]

If you are not using D2SE to run Eastern Sun I recommend to update your Plugy folder to the newest 
version v.11.02. All necessary informations can be found on the following website:
http://plugy.free.fr/en/index.html

[DATABASE]

You can find the Eastern Sun Database here: http://esdb.d2se.org/ 
Beware, it does not include any changes featured in my patches. 

Additional informations can be found here: http://miyoshino.la.coocan.jp/eswiki/?FrontPage

[CHANGELOG 4.2A]
-disabled wisdom and identify scrolls, keys, stamina, antidote and thawing pots to drop after Normal
 difficulty
-disabled all throwing pots to drop after Normal difficulty
-reduced droprate for health/mana pots in Nightmare (~50%) and Hell difficulty (~70%)
-disabled normal gems to drop after Nightmare difficulty
-lowered the chance to drop arrows and bolts, but increased the chance to drop rare and unique
 versions (in Nightmare and Hell)
-slightly increased the chance to drop higher tier weapons/armors
-limited another tier of low level affixes for armors and wepaons to a certain lvl range, will
 slightly improve magic/rare drops in Nightmare and Hell
-Kanji runes needing only 1 crystal instead of 2 (except God and Heaven runes)
-added fixes for various Vanilla bugs (thanks to LastCorpse)
-added Gold Pickup.dll 
-added Statfix.dll to fix caps on life, mana and stamina
-reworked Damage Augmenter  (Strength of the Ancients, Vigor of the Ancients and Iron Skin
 dont need Damage Augmenter anymore)
-removed Barbarian Passive 

[CHANGELOG 4.2B]
-removed all item color transformations for rings and amulets (also removes some color
 transformations for other items, as they shared suffixes/prefixes)
-to undo this change simply replace the MagicPrefix.txt and MagicSuffix.txt
-added 112 new jewelry graphics and replaced all old ones

[CHANGELOG 4.2C]
-fixed a bug with Fire Mastery
-changed Questskillrewards back to 2,2,3
-added new stats to Plugystatscreen
-fixed Maul Synergies
-improved Synergies for Shockwave, Hunger(20%) and Maul(20%)
-changed SWearbear to be a Druid Skill (added 6 Dummy Skills for other classes), added skillicon 
-changed the FoH skillrequirements, no longer requires Hyno Blast.
-reduced the manacost of Bone Wave, Multishot and Poison Nova by approximately half
-increased damage for vampires from (0,0,1,2,3,3 per lvlrange to 1,1,2,3,4,4)

[CHANGELOG 4.2D]
-fixed Inner Sight -% Damage Reduce, technically it is working as a curse now, so it can overwrite or
 be overwritten by such
-fixed Sway Defense%, removed Snynergies 
-added CustomTbl Plugin
-added 8 Hidden Treasures, they already spawn with the forged flag and can't be unforged

[CHANGELOG 4.2E]
-a change in the last patch resulted in a rather complicated pattern for maxlvl on skills 
 during lvling, you won't be able to max out skills until lvl 95, on the upside the 
 maxlvl is increased by 1 for every skill once you reach lvl 100
-slightly increased the dropchance for Hidden Treasures
-reworked parts of the User Interface, to disable go to the frontend folder in Data\Global\UI,
remove all files and restore the file in the old folder, next remove the charselect folder
-renamed two area's in act 5 to give credits to Tsuru and Perfect Cell
-attempted to fix the manaburn bug
-fixed a bug that allowed you to cast up to 25 Shadow Masters

[CHANGELOG 4.2F]
-added D2AnimatedItems.dll
-added Hellfire Torch (monster specific drop)
-reworked revieve code, playability should be much higher now
-fixed a bug in shadow masters attack behaviour 
-fixed mercenary running animation
-added dragonflight animations

[CHANGELOG 5.1A]
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

[CHANGELOG 5.1B]
-added D2Dyes.dll
-removed all char/inv color transformations from affixe/uniques and sets
-added 21 new pots to color items in whatever color you like
-fixed various strings
-fixed a bug with Hidden Treasures
-replaced a few baseitem gfx

[CHANGELOG 5.1C]
-fixed a bug with certain affixes when using D2Hackit.dll
-Act1 Hirelings can now use crossbows
-added D2Killcounter.dll
-added a new Unique charm which will display all kills correctly. Monsters with a level of 30 or lower than you wont count towards kills.
 This also replace the kill/death display on the attack skill
-added D2SmallUtility.dll
-removed (as replaced by D2SmallUtility.dll) Statfix.dll, D2AnimatedItems.dll and Utility.dll
-enabled defense while running
-removed the expcap of two screens while in a party
-gamble screen should be always full now
-added the gamble.exe
-disabled Bufficons.dll for now 
-increased Tome of Townportal to a total of 500
-increased Tome of Identify to a total of 500
-increased  all Weapons with Quantity to a total of 1000
-changed Replenish Quantity and Durability to 1 per 4 frames
-added a new suffix for jewels which adds Splash Damage on Striking
-tweaked the dropchance for the hellfire torch, diablo has a higher chance for dropping it, but it can be found elsewhere too (again:P)
-tweaked some armor prefix chances/lvl req

-Rerolls accept now Gem Cans. This works for every Rare/Magic Weapon/Armor part ( except the norm quality Axe for now )
 Rare Weapon/Armor + 2 Flawless Gems ( -58 Points in selected Gem Color ) = Rerolled Rare Weapon/Armor
 Eth Rare Weapon/Armor + 2 Perfect Gems ( -486 Points in selected Gem Color ) = Rerolled Eth Rare Weapon/Armor
 Magic Weapon/Armor + Flawless Gems ( -29 Points in selected Gem Color ) = Rerolled Magic Weapon/Armor
 Eth Magic Weapon/Armor + 2 Blemished Gems ( -162 Points in selected Gem Color ) = Rerolled Rare Weapon/Armor
-Weapon/Armor/Misc ( no Runewords ) + tp + magic eraser ( page 1 ) = removes Knockback from item
 (thanks to Sky)

[CHANGELOG 5.1D]
-fixed a bug with selfrepair spawning on throwing weapons
-finally was able to get bufficons.dll working 
-added the orginal ES Plugy statsinterface back
-fixed a bug a swearbear
-nerfed timestop and added a castdelay, also changed the castoverlay (thanks to maks)
-nerfed explosions caused by immolations fireballs
-nerfed creeping doom by about 10% less damage on lvl 20
-buffed ravens, they get a 5% base chance for open wounds and are now affected by auras
-fixed protection from evil, now works as intended
-buffed druid creepers, they attack slightly more often now
-higher level rare javalins now spawn with replenish again
-lowered CtC Splash Damage on Jewels to 5/10/10/15, the first two can spawn on rare jewels,
 the later can spawn only on mag jewels while the 10 Ctc a higher chance has than on rare jewels
-the Killcounter can be forged with 2 Maples + PG Ruby/Saphire/Amethyst or Emerald to get +Vitality, Energy, Strength or Dexterity 
 per Kills, however the Maples are lost if you unforge the Killcounter

- Remove Sprite Limit
- TCP/IP Delay fix - Hyperjoin Multiplayers
- More informations on the /FPS chat command
- COF Cache Memory -> Increased from 2 Mb to 20 Mb.
- Sprite Cache Memory -> Increased from 67 Mb to 250 Mb.
- CelData Cache Memory -> Increased from 0,5 Mb to 5 Mb.
- CPU Infinite loop bug fix - CPU load drops to 1% or less on newer computers
- Fix Item lost and Remove corpses
 (thanks to thaison aka vietnam)

[CHANGELOG 5.1E]
-added Charm Iventory (Odd Charms and Square Charms can go over the line, cause the code cant handle 2x2/3 Charms, as such they will be changed in 5.4)
-fixed a display bug (Killcounter)
-enabled mag/phy pierce (Code edit ISC Line 358 for mag and 357 for phy, this is for ESR 5.4 and 6.0) 
-fixed tinkering runeword bug
-disabeld Charges as affixes
-slightly buffed the chance to roll splash damage on jewels
-changed Twister synergies to Soul Shiver and Energy Shield
-buffed Twister synergies to +15% per Level
-replaced Energy Shield and Telekinesis  Teleport synergy with Twister synergy
-fixed Poison Stream Dragon Blade and Command Mastery Skill Icon
-replaced Larzuk's Innovation CtC on Striking Death Sentry with lvl 20 Battle Cry
Psn Nova:
 -removed physical damage
 - lowered Duration to 1,5s from 2s
 - increased psn Damage by 100% ( please Note that the Damage shown isnt x2 since it is computed per Frame and the Framecount was lowered by 25% )
 -changed animation back to clod
Psn Explosion:
 -removed physical damage
 - lowered duration to 1 Frame making the damage instant
 - increased psn Damage by 64/50
 
 -added an Overlay for Vengeance
-buffed Lightning Arrow Synergies by additional 2% per Level
-buffed Immolation Arrow Burn Damage and reduced Fire Duration from 3 to 2 Seconds
-buffed Exploding Arrow from slvl 17+
-further buffed Arctic Creeper, Volcanic Creeper and Poison Creeper Synergies to 10% per level


[CHANGELOG 5.1H]
- Frost Nova has a new graphical appearance
- Frost Nova now freezes instead of chilling enemies
- Replaced Amazon's Fire Wall with Fire Hawk - A clone of the Raven ability which does 100% fire damage
- Updated/added synergies for Fire Hawk
- Fixed broken lightning damage on Druid's Raven skill
- Converted Druid's Bone Spear to Flame Lance
- Adjusted synergies/damage to new element
-Replaced Necro Hydra with Ghost Hydra, deals 100% magic damage
(thanks to reiyo_oki)

-

[Known Bugs]
Set items get stuck to a color after changing it 2-3 times, logout/login with the char fix this. 
If you using D2Hackit you will get an ingame message everytime you put a dye in your inventory, you can ignore those.
When reparing Quantity Weapons you sometimes need to repair them multiple times until they are fully repaired
Tinkerpoints cant go lower than 4 reamining, that's a limitation, not a bug.




[Hidden Treasure]
The first Hidden Treasure was discovered by Narzath. It increases the maximum Skill Level by one. Seven left for you guys to find;).


[Additional Content]

Added the D2AnniversaryUIPlugin by Lurix. To disable remove the PANEL folder (beside 800BorderFrame) in Data\Global\UI.
Added a new Font by thanosdk. To disable remove the font folder in Data\Local.
Added parts of the HU Improved FX MKII by PureRage. To disable remove the levels.txt in Data\Global\Excel.
Included Ogodei's Autumnal Theme for the current patch. To disable remove the folder Tiles in Data\Global.

[Feedback]

Let me know what you think about skillchanges and also if you have any suggestions for further
skillbalance feel free to post @Phrozenkeep or @Snej.

[Credits]

madbrahmin for various plugins
Lastcorpse for various bugfixes
Lurix for his D2AnniversaryUIPlugin 
SpiKe for help tracking and fixing bugs
thanosdk for his Font
PureRage for his Improved FX Plugin, Code Edits
MnW95 for various dlls and help tracking and fixing bugs
Ogodei for various code edits and other stuff
ocarinas for various animations
Dav92 for various dlls
Fog for help with txts
Sky for help with txts
Thaison for code edits






Cheers
AlphA
