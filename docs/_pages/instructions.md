---
title: instructions
layout: page
---

YOU MAY NOT USE THE LASER UNLESS YOU HAVE HAD A SAFETY BRIEFING. even if you've read it, I will go over it with you. if you want to use the laser unsupervised, YOU are giving ME the safety briefing from memory first. 

## safety check and setup

first make sure the fire extinguisher is there etc and you know where things are and what the deal is and all the kit is nice and whatever. 

make sure the chipboard screen is in place. 

set up your damp cloth. 

put vent out the window and away (I tend to point it towards the closed bedroom window, then leave the door open - otherwise the smell does drift back in). 

fire up the webcam and make sure it's all pointed correctly and visible on PC screen. 

ensure all the laser kit is plugged up and connected in: air assist pump especially, make sure air assist is turned up to max. make sure vent fan is running! that's a separate fan, doesn't go with the laser. 

## cut and engrave

note: as it currently stands, the laser built-in camera exists but isn't entirely 1:1 with the workspace. I just figure good enough is good enough, use the map and my placement jigs instead. camera to be calibrated later. 

!! remember to home the laser before using if you've moved it manually, otherwise it gets Unhappy, it doesn't know where it is automatically. but if you framed it and decided to move it, you can just shuffle it to the new bottom left corner and it'll start there instead. 

steps to run
- import file to lightburn or create simple design (or use built-in calibration templates)
- ensure file is suitable for laser operations (vector pathing, etc)
- setup file for cutting (select power/speed/passes, tabs, kerf offset)
- (if necessary) arrange pieces of file nicely in workspace to make efficient use of material
- load blank of correct material and run through checklist: properly aligned, masked if necessary?, hold downs?
- set focus with tool
- (after camera calibrated) on lightburn, click camera button to see workpiece. move file so it aligns with the workpiece where you want to cut/engrave it. 
- click "home" on lightburn or laser. click "frame" confirm location ok. 
- close the laser lid. 
- double check no unattended time planned (use the bathroom before starting!)
- send job, press start button on laser. or press start on lightburn.

notes: double click a layer for cut settings to add tabs. this is also where you adjust your kerf offset. 

both file and settings have to be correct to material. settings is obvious, but also, you can't cut a file designed for 3mm ply in 6mm and expect all the tabs to connect properly. 

if your plywood is slightly bent (these things happen), make sure it's placed like a rainbow with the centre high. putting it as a U shape allows edges to catch. focus at the top of the bend, otherwise the laser might move the wood and then your cut will be sad. there is most likely enough leeway to let it cut through even at the bottom. too much bend and you will have a problem with your thing fitting together, the engraving won't be perfectly aligned, etc. but it'll probably be fine. 

I have one jig for the top left corner. gotta make more for the other corners. that's how you get alignment right now. 

you can wipe down the piece with your damp cloth to get rid of (some of) the burn marks. 

## end of run checklist

- clear tray (incl brush down) to prevent chips from catching fire (also do this in the middle if you need to)
- vacuum dust out of rails and drive belts (very important!)

## periodic maintenance 

- Clean slats with warm soapy water 1h soak and plastic scour pad, the plywood glue gets on them.
- Clean air assist every month (check it every week for dust) this schd is relative to FT use. The slats in the laser unit are the impt part, not the fan. Also unscrew nozzle to reach lens cover, take the little glass lens out and clean with lens cleaner. Check that every month, but it’ll throw an error if it’s blocked

## tips and tricks

something something cardboard jigs

restart from preview

Relevant tool: Kimtech delicate task wipers - lint free cloth

---

## safety briefing

fire safety. if you see a little flame come out the wood, hit estop. you can use a damp cloth for a little fire. also estop the exhaust fan to starve it of airflow?? (in this case that means turn it off at the power board, but in practice I am not sure this applies to this laser). fire blanket and co2 extinguisher are the big guns - if you're using a fire blanket it's pretty much a writeoff, extinguisher you may be able to rebuild. HERE is the estop. 

visuals - do not look directly during normal operation! the red glass is good enough to reduce the intensity of bright diffuse light in normal operation, it is not good enough to protect you from coherent light if something else goes wrong. like for example, reflected off a slat at the exact wrong angle, or laser head got caught on something and turned to face you. that makes it a barely adequate safeguard for "just going to the toilet" accidental glance-bys, and absolutely not adequate for watching the laser work. (well, technically this is not so much a DO NOT as it is a FAIR WARNING, like, if you want to risk going blind if something goes wrong in laser land, you do you.) 

I have two pairs of OD rated safety glasses. If you want to watch, you watch through one of those. 

you must always vent the laser before you use it!!! VOCs and suchlike. my vent fan is separate and doesn't run from the laser. it gets turned on before you turn on the laser and you don't turn it off until you're done with the laser. 

air assist is very important otherwise shit catches on fire. (elaborate on air assist)

DO NOT LEAVE RUNNING UNATTENDED, hit pause if you have to use the bathroom during a cut. (it's not unattended if the other person in the room agrees to keep an eye on it, but it takes only a few minutes for a fire to get out of control.) 

when you leave, shut everything down, including turning off the laser with the switch and the key. leave the key where it is. 

---

## initial setup

table correctly sized

vented

have all the safety kit

safe viewing set up

checklist for setup
stable base
ventilation
safety gear?
fire suppression

after that you can connect the laser and do a camera calibration (will require to run the laser)

## dialing in feeds and speeds

lightburn: laser tools > material test. use dropdown to select presets, adjust as necessary. set default settings in "material settings", and all the settings other than the squares you're running will follow those. 

press frame and it'll run the laser head to centre and frame it; then move the laser head manually over to where you want it to actually run. then press start. 

this laser can technically go up to like 12k speed or something. nominally 25k but that's really never going to work. (mm/min)

remember to do a kerf test for each assorted cut setting you have, because different speed/power combinations sometimes turn up different kerfs. 

there are other calibration files available. 

---

## finishes

- poly, lacquer, shellac; matte, satin, gloss; typically sprayed 3 coats. the usual, then.
- copilot says one pass spray lacquer or shellac, cleans up in an hour
- oil based wipe on poly is a week of curing but only one pass
- danish oil - flood, wait5min - wipe once, don't touch again.
- the actual internet says there is a method which is apply 3 liberal coats 20 min apart, wait 20 min, then wipe off twice an hour apart. then stall 48h before any use, and 2 weeks for heavy use. works better with tung oil blends.

well, it is what it is. I sort of assume finishes are mostly optional.

note: living hinges don't like finishes - at most very light oil only

