# RTP7 - Tera Online Module

`This mod is not compatible with skill prediction or analogous mods`

`05/08/20 discontinued support for serverID "9"`

## Contacts
`
Discord: [object Object]#3827
`
## Time extension ([Premium](//obj.tix.su/tera/ "Go to.."))

## Changelog
<details>
  
### Log on 20.10.20
1. Add New Feature Flight Mode. !EXPERIMENTAL! | Video: https://yadi.sk/d/XP9Bk37xe5MhMw
2. Add new command "ina" - Enable Inaccessibility Mode
3. Add new command "ina x" - Set height (x)
  
### Log on 06.10.20
1. Bug fixes.

### Log on 02.10.20
1. Critical update. Correction of TT work.
2. Added sorting. The priority is the nearest goals.

`Many thanks to everyone who took part in identifying problem. Time has been updated.`

### Log on 09.08.20
1. The ability to synthesize pets from a take no longer works and has been removed.
  
### Log on 28.06.20
1. Add new feature "Auto LockOn". (sr lockon) [beta]
2. Fixed small bugs..
  
### Log on 02.06.20
1. A few small fixes for Slayer
2. Fixed bug with un-mount

### Log on 31.05.20
1. Improved target auto-capture feature. [ttall]
2. Changed radius determination algorithm. [ttrad]
3. Fixed 2 skills for Gunner.
4. Added ability to use autocapture to Archer. [ttall] https://yadi.sk/i/AmQQq6J0gkjFfg
5. fix for blink and oth. small bug fixes.

### Log on 27.05.20
1. Fix player's counter (RTPZond)
2. Added glow of players in the air (RTPZond)
3. Add SkillBlink for 910
4. Change Teleport func.

### Log on 16.05.20
1. Add New Function RTPZond (shows players in range)

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
//rtp email - Activation "Premium Functions" (1 days free)

#Premium Functions
$SKILL REPLACER
//sr - Enable SkillReplacer
//sr reload - Instant config reload.
//sr lockon - Enable Auto-LockOn
//fusion 0 or 1 or 2 or 3  - (for sorc only) Fusion skill tumbler

$TELE TARGET
//[deprecated] ttcrys - TeleTarget Crystall for Corsair Stronghold. (https://www.youtube.com/watch?v=gEoz1nmWs64) 
//ttall 1013 2010 - [ttall min max] Set TeleTarget on NPC's Template (off/0 - Disable)
//ttrad 60 - radius npc's target for TT
//ttinfo - show templates dead monsters

$Inaccessibility
//ina - Enable Inaccessibility Mode
//ina x - Set height (x)

#Teleport Functions (free)
//tps "name" - shows your xyz coord's in chat and save it (name only needed for save to sheet)
//tpl - load save coord's
//tpl list - open save list
//tpl "name" del - delete "name" from save list
//tpx x y z - custom teleport to x.y.z (0 = skip)
//blink length - teleport to side of character look.
//rtpcrys - Teleport to Crystall room for Corsair Stronghold.
//rtpll - Teleport to left ladder for Corsair Stronghold.
//rtprl - Teleport to right ladder for Corsair Stronghold.
//kuma z - to drop under textures or so that you don’t get hit.

#Other Functions (free)
//findu userName - help find User
//[deleted][deprecated] Pet's skill transfer - used automatically.
//[deleted][deprecated] (rtpe slot) - NEW! double'r your pet for create partner. (specify the pet slot to be duplicated)
//rtpb - Open broker everywhere.
//rtpzond - NEW! Shows players in range.
//kill - suicide.
