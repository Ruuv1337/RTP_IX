# RTPort - Tera Online Module

## Contacts
`
Discord: [object Object]#3827
`
## Log List
Log on 29.01.20
1. Add command "sr reload" - Instant config reload.
2. Add 4 skill's + SpeedCast mode for Warrior.
3. Warrior status is checked.

Log on 24.01.20
1. Add ChatCommand's Defender
2. Add command /rtpb - open broker.
3. Fixed SERVANT SKILL TRANSFER (https://yadi.sk/i/rW70AZ6NkHlSHg)

Log on 19.01.20
1. Made several corrections regarding the mass extermination of targets (ttall).
```
I express my gratitude for finding of problem and help in resolving it: Smile#6367
```
Log on 17.12.19
1. Add New function (beta): https://yadi.sk/i/zwKGV3BHGVrXDQ
2. Add radius conf for TT
3. Some minor bug fixes
4. Priest status is checked.
5. Hide dmgNumbers on use 'ttall'

Log on 12.11.19
1. Add new function "TeleTarget" (autouse)
2. Add command ttcrys (for TeleTarget on Corsair battleground)
3. change commands "crys" "ll" "rl" to "tpcrys" "tpll" "tprl"

Log on 07.11.19
1. Some minor bug fixes
2. Added hack for pets.

info: If you got any “TEMPORARY" pet, now you have the opportunity to transfer all his skills to your "permanent" companion :)
```
free pet key for RU: TERA-AWAKE-NING2
```
Log on 06.11.19
1. Add Unlimited Evade (for Slayer)
2. Add SpeedCast mode (for Slayer)
3. Slayer status is checked.

Log on 04.11.19
1. Add 6 Skill's (for Valkyrie)
2. Add SpeedCast mode (for Valkyrie)
3. Valkyrie status is checked.

Log on 31.10.19
1. Add Unlimited Evade (for Gunner)
2. Add Fusion tumbler (for Sorc)
3. Add one skill for Sorc [Awakening Energy >> UnAgro skill without CD]
4. Add manual "skill tumbler" in config file for fusion skill [sorc].

Log on 28.10.19
1. UPPDATE For Last version Client [TERA TOOLBOX]
2. Made corrections for Shinobi (possibly Valkyrie too)
3. Added 2 skills for Gunner

==========================
```
                //Warrior 6 [checked]
                //Lancer 2
                //Slayer 1 [checked]
                //Berserker 1
                //sorcerer 5 [checked]
                //archer 2
                //priest 4 [checked]
                //mystic 0
                //reaper 4
                //gunner 6 [checked]
                //brawler 1
                //ninja 5
                //valkyrie 6 [checked]
```
==========================

[For idea thx OverImagine]

Analog mod link: https://github.com/tera-mod/Skill-Replacer

## Commands
**Need to be used in _Proxy Channel_ (/8)**
```
#Module Authorization
//rtp email - Activation "Premium Functions" (3 days free)

#Premium Functions
$SKILL REPLACER
//sr - Enable SkillReplacer
//sr reload - Instant config reload.
//fusion 0 or 1 or 2 or 3  - (for sorc only) Fusion skill tumbler

$TELE TARGET
//ttcrys - NEW! TeleTarget Crystall for Corsair Stronghold. (https://www.youtube.com/watch?v=gEoz1nmWs64)
//ttall 1013 2010 - NEW! [ttall min max] Set TeleTarget on NPC's Template (off/0 - Disable)
//ttrad 1800 - NEW! radius npc's target for TT

#Teleport Functions (free)
//coord - shows your xyz coordinate in the chat and save it.
//tpx - load coord
//tp x y z - teleport to xyz (0 = skip)
//tpcrys - Teleport to Crystall room for Corsair Stronghold.
//tpll - Teleport to left ladder for Corsair Stronghold.
//tprl - Teleport to right ladder for Corsair Stronghold.
//hide - Teleport to "hide zone" for Corsair Stronghold. [deleted]

#Other Functions (free)
//findu userName - help find User
//rtpinfo - NEW! other dbg infos (show templates dead monsters) (for tt)
//Pet's skill transfer - used automatically.
//rtpb - NEW! Open broker everywhere
