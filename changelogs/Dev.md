---
lang: en-US
title: Dev Changelogs
sidebar:
- { text: Latest Changelog, link: /Changelogs.html}
- { text: Previous Stable Changelogs, link: /changelogs/Stable.html}
- { text: Previous Canary Changelogs, link: /changelogs/Canary.html}
- { text: Previous Dev Changelogs, link: /changelogs/Dev.html}
---

# Dev Changelogs
----
To access Dev Builds, become a Sponsor on [Ko-Fi](https://ko-fi.com/tohen) or [Contribute](https://github.com/0xDrMoe/TownofHost-Enhanced)
---

## <font size=4em><b>v1.2.1 Dev 4</b></font><br>

+ By [**TommyXL**](https://github.com/Tommy-XL)<br>
= <font color=#1376f0><b>BUG FIX</b></font>: Fixed player names for desync impostor during Mushroom Mixup
= <font color=#1376f0><b>BUG FIX</b></font>: Fixed bug when shapeshift cooldown sets to 0 after Mushroom Mixup (Vanilla Bug)
= <font color=#1376f0><b>BUG FIX</b></font>: Fix Desync Impostor Reset Cooldown Sabotages (If setting Sabotage Cooldown Control is enabled, desync impostors resets cooldown sabotages when any sabotage is clicked)

* By [**ryuk**](https://github.com/ryuk2098)<br>
\- <font color=red><b>REMOVED</b></font>: Removed egoist count as setting from ParityCop
\+ <font color=green><b>NEW</b></font>: Added setting for Egoist to be counted as converted neutral
\+ <font color=green><b>NEW</b></font>: Added setting for converted madmate to kill without repercussions
---

## <font size=4em><b>v1.2.1 Dev 3</b></font><br>

* By [**NikoCat223**](https://github.com/NikoCat233)<br>
= <font color=#F6BE00><b>CHANGE</b></font>: Improved Banning system
= <font color=#1376f0><b>BUG FIX</b></font>: Fixed converted player win conditions
= <font color=#1376f0><b>BUG FIX</b></font>: Remove "Incompatible" role assign
= <font color=#1376f0><b>BUG FIX</b></font>: Fix bug Hurried can be madmate

* By [**LezaiYa**](https://github.com/LezaiYa)<br>
= <font color=#1376f0><b>BUG FIX</b></font>: Some miscellaneous fixes
\+ <font color=green><b>NEW</b></font>: Basic Crewmate Role: [Randomizer](/options/Crewmates/Basic/Randomizer.html) (from Night)


* By [**TommyXL**](https://github.com/Tommy-XL)<br>
= <font color=#1376f0><b>BUG FIX</b></font>: Fix Doomsayer showing wrong count in message
= <font color=#F6BE00><b>CHANGE</b></font>: Optimized showing settings in the lobby (Host)
= <font color=#1376f0><b>BUG FIX</b></font>: Fix Killing Machine Vision
= <font color=#1376f0><b>BUG FIX</b></font>: Fix /death Command For Host (Hopefully)
= <font color=#1376f0><b>BUG FIX</b></font>: Fix Killing Machine Can Sabotage
\+ <font color=green><b>NEW</b></font>: Disable Tasks In Fungle

* By [**NetherDragonTw**](https://github.com/NetherDragonTw)<br>
= <font color=#F6BE00><b>CHANGE</b></font>: Updated default Template message for Traditional Chinese

* By [**ryuk**](https://github.com/ryuk2098)<br>
= <font color=#F6BE00><b>CHANGE</b></font>: Made Vector incompatible with Unlucky
= <font color=#1376f0><b>BUG FIX</b></font>: Fix Lookout, Inspector and Swapper seeing double id with guesser addon
= <font color=#F6BE00><b>CHANGE</b></font>: Improved Trickster (Reverie killing Trickster increases cooldown, Always shows as a check mark for witness)
= <font color=#F6BE00><b>CHANGE</b></font>: Cyber is now incompatible with Doppelganger
\+ <font color=green><b>NEW</b></font>: Neutral Benign Role: [Taskinator](/options/Neutrals/Benign/Taskinator.html) (idea by Dx)
\+ <font color=green><b>NEW</b></font>: Neutral Benign Role: [Pixie](/options/Neutrals/Benign/Pixie.html) (idea by Azanthiel)
\+ <font color=green><b>NEW</b></font>: Role colors are now changable trough a new .dat file (User can change role colors by renaming templateRoleColor.dat to RoleColor.dat and adding hex colors in the file; Custom roles can be exported by pressing"F5+X" (same as custom translations))

* By [**lars-wu (papercut)**](https://github.com/lars-wu)<br>
\+ <font color=green><b>NEW</b></font>: Crewmate Support Role: [Enigma](/options/Crewmates/Support/Enigma.html)
\+ <font color=green><b>NEW</b></font>: impostor Killing role: [Instigator](/options/Impostors/Killing/Instigator.html)
---

## <font size=4em><b>v1.2.1 Dev 2</b></font><br>

* By [**NikoCat233**](https://github.com/NikoCat233) <br>
= <font color=#1376f0><b>BUG FIX</b></font>: Recode admirer for better performance
= <font color=#1376f0><b>BUG FIX</b></font>: Fix Admirer knowrole don't work properly
= <font color=#1376f0><b>BUG FIX</b></font>: Fix Admired Vrctor win condition check
= <font color=#1376f0><b>BUG FIX</b></font>: Fix Jackal killing Admirer, Sheriff (supposed to recruit) when use only recruit
= <font color=#F6BE00><b>CHANGE</b></font>: Temporarily prevent Cultist from charming Neutrals.
= <font color=#F6BE00><b>CHANGE</b></font>: If host is versioncheating, then mod clients wont automatically quit
= <font color=#1376f0><b>BUG FIX</b></font>: Fix Vulture (Now Vulture cant eat cleaned/stoned body)
\+ <font color=green><b>NEW</b></font>: Harmful Add-on: [Influenced](/options/Addons/Harmful/Influenced.html)
\+ <font color=green><b>NEW</b></font>: Experimental Add-on: [OIIAI](/options/Experimental/Addon/OIIAI.html)
\+ <font color=green><b>NEW</b></font>: Harmful Add-on: [Hurried](/options/Addons/Harmful/Hurried.html) (Added Dev 2, usable Dev 3)

* By [**KevOut**](#) <br>
= <font color=#1376f0><b>BUG FIX</b></font>: Fix taskbar always invisible

* By [**TommyXL**](https://github.com/Tommy-XL)
= <font color=#F6BE00><b>CHANGE</b></font>: Improved code base for better performance
\+ <font color=green><b>NEW</b></font>: Camouflage skins (<font color=#ec7578>TommyXL</font> and <font color=#919497>Gurge44</font>)
---