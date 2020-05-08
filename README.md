# RTPort - Tera Online Module

`On [v92+], a lot has already been fixed and does not work. `

`05/08/20 discontinued support for serverID "9"`


## Contacts
`
Discord: [object Object]#3827
`
## Changelog
<details>

### Log on 07.05.20
1. Added feature "RTPShift" (BETA) [Do not use in a group with strangers.]
2. small fixes for Brawler.

### Log on 02.05.20
1. Added NEW! function (command "rtpe slot" double your pet for create partner). [https://yadi.sk/i/1y9h0Pn-z3_mrA]
2. [deleted][deprecated] "ttcrys" commmand.
3. Add SpeedCast mode for Berserker and two skill's.
4. Berserker status is checked.
5. Added small fixes for Sorc and Lancer.
6. Lancer status is checked.
7. Add Unlimited Evade for Brawler.
8. Add SuperArmor mode for Brawler and two skill's.
9. Brawler status is checked.
10. Change command TP to RTPORT

### Log on 16.03.20
1. Added fixes for Reaper and +1 skill.
2. Removed unnecessary functionality. (Servant Exp Transform)
3. Added new const in config.. (Reload).
4. Some minor bug fixes.

### Log on 24.02.20
1. Add Unlimited Evade for Ninja.
2. Add Unlimited Evade for Reaper.
3. Add SpeedCast mode for Reaper.
4. Reaper status is checked.
5. Ninja status is checked.
6. Some minor bug fixes.

### Log on 29.01.20
1. Add command "sr reload" - Instant config reload.
2. Add 4 skill's + SpeedCast mode for Warrior.
3. Warrior status is checked.
4. Add ChatCommand's Defender
5. Add command /rtpb - open broker.
6. Fixed SERVANT SKILL TRANSFER (https://yadi.sk/i/rW70AZ6NkHlSHg)
7. Made several corrections regarding the mass extermination of targets (ttall).
```
I express my gratitude for finding of problem and help in resolving it: Smile#6367
```
### Log on 17.12.19
1. Add New function (beta): https://yadi.sk/i/zwKGV3BHGVrXDQ
2. Add radius conf for TT
3. Some minor bug fixes
4. Priest status is checked.
5. Hide dmgNumbers on use 'ttall'
6. Add new function "TeleTarget" (autouse)
7. Add command ttcrys (for TeleTarget on Corsair battleground)
8. change commands "crys" "ll" "rl" to "tpcrys" "tpll" "tprl"
9. Some minor bug fixes
10. Added hack for pets.

info: If you got any “TEMPORARY" pet, now you have the opportunity to transfer all his skills to your "permanent" companion :)
```
free pet key for RU: TERA-AWAKE-NING2
```
### Log on 06.11.19
1. Add Unlimited Evade (for Slayer)
2. Add SpeedCast mode (for Slayer)
3. Slayer status is checked.
4. Add 6 Skill's (for Valkyrie)
5. Add SpeedCast mode (for Valkyrie)
6. Valkyrie status is checked.

### Log on 31.10.19
1. Add Unlimited Evade (for Gunner)
2. Add Fusion tumbler (for Sorc)
3. Add one skill for Sorc [Awakening Energy >> UnAgro skill without CD]
4. UPPDATE For Last version Client [TERA TOOLBOX]
5. Made corrections for Shinobi (possibly Valkyrie too)
6. Added 2 skills for Gunner
</details>


==========================
```
                //Warrior 6 [checked]
                //Lancer 2 [checked]
                //Slayer 1 [checked]
                //Berserker 3 [checked]
                //sorcerer 5 [checked]
                //archer 2
                //priest 4 [checked]
                //mystic 0
                //reaper 6 [checked]
                //gunner 6 [checked]
                //brawler 3 [checked]
                //ninja 7 [checked]
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
//[deleted][deprecated] - TeleTarget Crystall for Corsair Stronghold. (https://www.youtube.com/watch?v=gEoz1nmWs64) 
//ttall 1013 2010 - [ttall min max] Set TeleTarget on NPC's Template (off/0 - Disable)
//ttrad 1800 - radius npc's target for TT

$SHIFT MOD
//rtpshift - Enable\Disable mod. [BETA]

#Teleport Functions (free)
//coord - shows your xyz coordinate in the chat and save it.
//tpx - load coord
//rtport x y z - teleport to xyz (0 = skip)
//rtpcrys - Teleport to Crystall room for Corsair Stronghold.
//rtpll - Teleport to left ladder for Corsair Stronghold.
//rtprl - Teleport to right ladder for Corsair Stronghold.
//[deleted][deprecated] - Teleport to "hide zone" for Corsair Stronghold.

#Other Functions (free)
//findu userName - help find User
//rtpinfo - other dbg infos (show templates dead monsters) (for tt)
//Pet's skill transfer - used automatically.
//rtpe slot - NEW! double'r your pet for create partner. (specify the pet slot to be duplicated)
//rtpb - Open broker everywhere
