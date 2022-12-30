# BGT Spawn Tweak
This little mod for Baldur's Gate Trilogy allows you to tweak the parameters of the area spawn points to change the difficulty of the encounters.

[**Download**](https://github.com/SpellholdStudios/BGT-Spawn-Tweak/releases) &nbsp;|&nbsp; [**Config**](https://github.com/SpellholdStudios/BGT-Spawn-Tweak/blob/main/spawntweak/config.ini) &nbsp;|&nbsp; [**Forum**](http://www.shsforums.net/topic/60654-bgt-spawn-tweak/)

## Installation steps
1. Install [Baldur's Gate Trilogy](https://github.com/SpellholdStudios/BGT-WeiDU).
2. Copy **setup-spawntweak.exe** and the folder **spawntweak** to your game directory.
3. Open **spawntweak/config.ini**, read the descriptions and tweak the parameters to your liking.
4. Run **setup-spawntweak.exe** to install the mod with the configured parameters.

## Compatibility notes
BGT Spawn Tweak is fundamentally incompatible with other BGT spawn mods, such as BGSpawn or BGT Tweak Pack component "Altered Spawns".

## Available tweaks
* Spawn difficulty modifier
* Maximum number of creatures per spawn point
* Delay between entering an area and spawning
* Spawn probability
* Deactivate the spawn point after spawning once
* Disable all spawns

## Difficulty calculator
To calculate the desired spawn difficulty, use the spawning formula and the creature power level list below.

```
No. spawns = (Spawn Difficulty * Avg. Party Lvl * Party Size) / Creature Power Lvl (rounded down)
```
```
CRE: KOBOLA_A  LVL:  3  HP:  4  XP:    7  Name: Kobold
CRE: KOBOLA_B  LVL:  3  HP:  4  XP:    7  Name: Kobold
CRE: KOBOLA_C  LVL:  3  HP:  4  XP:    7  Name: Kobold
CRE: KOBOLA_D  LVL:  3  HP:  4  XP:    7  Name: Kobold
CRE: KOBOLA_E  LVL:  3  HP:  4  XP:    7  Name: Kobold
CRE: KOBOLDA   LVL:  3  HP:  4  XP:    7  Name: Kobold
CRE: KOBOLD_A  LVL:  3  HP:  4  XP:    7  Name: Kobold
CRE: KOBOLD_B  LVL:  3  HP:  4  XP:    7  Name: Kobold
CRE: KOBOLD_C  LVL:  3  HP:  4  XP:    7  Name: Kobold
CRE: KOBOLD_D  LVL:  3  HP:  4  XP:    7  Name: Kobold
CRE: KOBOLD_E  LVL:  3  HP:  4  XP:    7  Name: Kobold

CRE: XVART_A   LVL:  4  HP:  7  XP:   15  Name: Xvart
CRE: XVART_B   LVL:  4  HP:  7  XP:   15  Name: Xvart
CRE: XVART_C   LVL:  4  HP:  7  XP:   15  Name: Xvart
CRE: GIBBER2   LVL:  4  HP:  4  XP:   35  Name: Diseased Gibberling
CRE: GIBBER    LVL:  4  HP:  8  XP:   35  Name: Gibberling
CRE: TASLOI    LVL:  4  HP:  8  XP:   35  Name: Tasloi
CRE: DOGWI     LVL:  4  HP:  9  XP:   35  Name: Wild Dog

CRE: SKELET03  LVL:  5  HP:  8  XP:   65  Name: Skeleton
CRE: SKELETS   LVL:  5  HP:  8  XP:   65  Name: Skeleton
CRE: SKELET_A  LVL:  5  HP:  8  XP:   65  Name: Skeleton
CRE: SKELET_B  LVL:  5  HP:  8  XP:   65  Name: Skeleton
CRE: SKELET_C  LVL:  5  HP:  8  XP:   65  Name: Skeleton
CRE: ZOMBIE_A  LVL:  5  HP: 15  XP:   65  Name: Zombie
CRE: ZOMBIE_B  LVL:  5  HP: 15  XP:   65  Name: Zombie
CRE: ZOMBIE_C  LVL:  5  HP: 15  XP:   65  Name: Zombie
CRE: ZOMBIE_D  LVL:  5  HP: 15  XP:   65  Name: Zombie
CRE: ZOMBIE_E  LVL:  5  HP: 15  XP:   65  Name: Zombie

CRE: HOBGOA_A  LVL:  6  HP:  8  XP:   35  Name: Hobgoblin
CRE: HOBGOA_B  LVL:  6  HP:  8  XP:   35  Name: Hobgoblin
CRE: HOBGOA_C  LVL:  6  HP:  8  XP:   35  Name: Hobgoblin
CRE: HOBGOA_D  LVL:  6  HP:  8  XP:   35  Name: Hobgoblin
CRE: HOBGOA_E  LVL:  6  HP:  8  XP:   35  Name: Hobgoblin
CRE: HOBGOB_A  LVL:  6  HP:  8  XP:   35  Name: Hobgoblin
CRE: HOBGOB_B  LVL:  6  HP:  8  XP:   35  Name: Hobgoblin
CRE: HOBGOB_C  LVL:  6  HP:  8  XP:   35  Name: Hobgoblin
CRE: HOBGOB_D  LVL:  6  HP:  8  XP:   35  Name: Hobgoblin
CRE: HOBGOB_E  LVL:  6  HP:  8  XP:   35  Name: Hobgoblin
CRE: BANDIT    LVL:  6  HP:  8  XP:   65  Name: Bandit

CRE: BGWOLF    LVL:  7  HP: 24  XP:   65  Name: Wolf

CRE: GNOLL     LVL:  8  HP: 15  XP:   35  Name: Gnoll
CRE: GNOLL_B   LVL:  8  HP: 15  XP:   35  Name: Gnoll
CRE: GNOLL_D   LVL:  8  HP: 15  XP:   65  Name: Gnoll Slasher
CRE: GNOLL_A   LVL:  8  HP: 18  XP:   65  Name: Gnoll Elite
CRE: GNOLL_E   LVL:  8  HP: 22  XP:   65  Name: Gnoll Veteran
CRE: DOGWA     LVL:  8  HP: 17  XP:   65  Name: War Dog
CRE: FLIND     LVL:  8  HP: 19  XP:  120  Name: Flind

CRE: IRONGU    LVL: 10  HP: 23  XP:  120  Name: Guard
CRE: WORG      LVL: 10  HP: 26  XP:  120  Name: Worg

CRE: BEARBL    LVL: 12  HP: 25  XP:  175  Name: Black Bear
CRE: OGREGR    LVL: 12  HP: 19  XP:  175  Name: Ogrillon
CRE: IRONELIT  LVL: 12  HP: 26  XP:  240  Name: Black Talon Elite

CRE: WOLFDI    LVL: 14  HP: 33  XP:  125  Name: Dire Wolf
CRE: GHOUL     LVL: 14  HP: 15  XP:  175  Name: Ghoul
CRE: SPIDHU    LVL: 14  HP: 18  XP:  270  Name: Huge Spider

CRE: KOBCOMM   LVL: 20  HP:  7  XP:   35  Name: Kobold Commando
CRE: JELLYGR   LVL: 20  HP: 16  XP:   65  Name: Green Slime
CRE: HOBELITE  LVL: 20  HP: 16  XP:   95  Name: Hobgoblin Elite
CRE: JELLGR    LVL: 20  HP: 25  XP:  275  Name: Gray Ooze
CRE: WOLFDR    LVL: 20  HP: 33  XP:  650  Name: Dread Wolf
CRE: OGREBERZ  LVL: 20  HP: 50  XP:  650  Name: Ogre Berserker

CRE: CARRIO    LVL: 25  HP: 22  XP:  420  Name: Carrion Crawler
CRE: BEARBR    LVL: 25  HP: 41  XP:  420  Name: Brown Bear
CRE: WOLFWI    LVL: 25  HP: 45  XP:  975  Name: Winter Wolf
CRE: ANKHEG    LVL: 25  HP: 52  XP:  975  Name: Ankheg

CRE: GHAST     LVL: 28  HP: 29  XP:  650  Name: Ghast

CRE: GHOULLOR  LVL: 30  HP: 48  XP: 1000  Name: Greater Ghoul
CRE: WOLFVA    LVL: 30  HP: 50  XP: 2000  Name: Vampiric Wolf

CRE: DOPPLE    LVL: 35  HP: 31  XP:  420  Name: Doppleganger
CRE: ETTERC    LVL: 35  HP: 40  XP:  650  Name: Ettercap

CRE: WEREWO    LVL: 40  HP: 35  XP:  420  Name: Werewolf
CRE: SPIDGI    LVL: 40  HP: 35  XP:  450  Name: Giant Spider
CRE: BEARCA    LVL: 40  HP: 50  XP:  650  Name: Cave Bear
CRE: SPIDWR    LVL: 40  HP: 27  XP: 1400  Name: Wraith Spider

CRE: OGREMA    LVL: 50  HP: 41  XP:  650  Name: Ogre Mage
CRE: SPIDPH    LVL: 50  HP: 44  XP: 1400  Name: Phase Spider
CRE: WOLFWEGL  LVL: 50  HP: 51  XP: 1800  Name: Wolfwere
CRE: FGOLEM    LVL: 50  HP: 40  XP: 2000  Name: Flesh Golem
CRE: SPIDSW    LVL: 50  HP: 45  XP: 2000  Name: Sword Spider

CRE: JELLOC    LVL: 60  HP: 41  XP:  270  Name: Ochre Jelly
CRE: JELLMU    LVL: 60  HP: 65  XP: 2000  Name: Mustard Jelly
CRE: JELLYMU   LVL: 60  HP: 65  XP: 2000  Name: Mustard Jelly

CRE: BATTHO    LVL: 80  HP: 58  XP: 4000  Name: Battle Horror
CRE: DOPPGR    LVL: 80  HP: 65  XP: 4000  Name: Greater Doppleganger
```
