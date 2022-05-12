# SavidDanders Beeg Y-Motor Mod
## What is it?

This is my mod to allow for a larger Y-axis motor on the boubounokefalos Ender 3 to Voron Switchwire conversion. My goal is to keep the Y-Motor within the bound of the frame to avoid having to make changes to the enclosure in the future. This re-work changes the belt path to match closer to the original Voron Switchwire design. Full credit to [Gizzle](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/Gizzle/ender-3_(pro)_switchwire) for the motor mounts. I have used the same motor mounts and idler as their mod just mirrored for clearance.

## Why should I do this?

If you are not happy with the speeds and accelerations of the smaller Creality or other motors, this allows for more clearance for a bigger motor. If you don't want to spend the money for 2 linear rails on the Y-Axis this reduces it to 1. If you have lots of friction or binding on the Y-Axis with 2 rails this is for you.

[Speed Test](https://discord.com/channels/460117602945990666/947303252372906014/973366943748866120) with [Nema 17 17HS24-2104S](https://www.omc-stepperonline.com/nema-17-bipolar-1-8deg-65ncm-92oz-in-2-1a-3-36v-42x42x60mm-4-wires-17hs24-2104s)

## How do I do this?

⚠️ Before you start this will involve drilling holes into your Y-Axis carriage! If you are not okay with this or do not have access to a drill do not attempt this mod.

Start by printing out all the parts in the STL folder. Mechanical parts that are going inside the enclosure should be printed in ABS. The grills, decks, and drill tool can be printed from PLA if it makes life easier.

Drilling the Y-Carriage. Follow the diagram below to align and secure the drill tool. Use 2x M5 bolts and nuts in the open holes to secure the tool in place. Use a drill with M3 or equivalent bit size to drill the remaining 3 holes. ⚠️ Be careful with this process. Have parts properly secured while drilling. I will not be liable for personal or property damages.

[Image goes here]

With the carriage drilled the single MGN12H linear rail can be attached to the top of the Y extrusion. From here you can reference the CAD files for a better idea of how everything is assembled. As of this initial release there is no belt tensioner for the Y-axis. Properly tensioning the Y belt is difficult but not impossible. My method involves having the motor attached, the belt-fed through the belt holder, and clamped. You can then use insert the y_idler_top and use the M5 bolt as leverage to secure the belt. 

## Future changes

This is my passion project updates may be sporadic or non-existent. With that being said I would like to improve this mod in the future.
* Bill of Materials
* Y-Axis Belt Tensioner
* Updated CAD with all hardware
* Better looking back middle grill
