***NOTE (Read Please): This repository uses git submodules. After cloning, run
these commands:

git submodule init
git submodule update

Otherwise the modpack will not work properly.


Magical_Realm
=============
This is a modpack intended to include magical things. 

Mods included from other authors: smartfs


magic_spells
------------

An API for magical spells. See magic_spells/API.txt for more info.

To test spells, you can give yourself a testing wand with
"/give player_name magic_spells:creative_stick". If you are playing on single-player,
the player name will be "singleplayer". Also, give yourself a
magic_spells:creative_spellbook. You can also find these items in the creative
menu.

To learn a spell, click with the spellbook, click prepare,choose a spell,
and hit "Learn".
To prepare a spell, click with the spellbook, and choose a spell from the "Prepare" menu.

To use the wand, first select a spell by right-clicking. Then you can cast the spell
by left-clicking.

To remove all your prepared spells, go to the spellbook menu and hit
"Unprepare".


combat_spells
----------------

Spells geared for fighting or defending against other players

Current Spells (Display name in parentheses):

summon_tnt (Summon Lit TNT) - Places a lit tnt node where you are looking when your
  casting finishes.

magic_missile (Magic Missile) - Shoots homing force bolts.

reflect_lesser (Lesser Reflect) - Reflects weak magic projectiles.


travel_spells
-------------

Spells that help transport the player

Current Spells

blink (Blink) - Teleport to a random nearby location

ethereal_jaunt (Ethereal Jaunt) - Makes the player invisible and immaterial, so
they can fly and phase through walls. Kills the player if they are inside solid
material when the rematerialize.
