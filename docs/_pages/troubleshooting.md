---
title: troubleshooting
layout: page
---

## current status / todolist

before next laser day
- vacuum dust out of rails and drive belts
- belt tensioning
- clean down the air assist slats and lens
- soak and clean slats and tray
- sort out the requisite damp cloth

next laser day
- run speed/power/passes testing
- do mog's thing
- make proper corner jigs. 25 long and 20 wide seems to be the go?
- cut a moebius strip
- experiment with other materials, including a rock or two
- run an experimental art or two
- run the full stack of living hinge test cards

eventually
- make the camera behave like dude managed to
- make gallery pictures linkable to their related post

critical path to production
- use FH and lighthouse for promo art - get websites up and whatever, and I'll need svg files for those, and I'll still eventually have to make a logo for the laser side too
- put all the product options through the laser, then post them up separately on the website, then handoff
- file system planning

---

## issues

lightburn tells you yourlaser is busy: check the COM port is at COM4 instead of COM1

remember to home the laser if you've moved it to get to your piece, otherwise it gets Unhappy. but if you framed it and decided to move it, you can just shuffle it to the new bottom left corner

jiggles where the line should be straight/curves not as they should be: probably a belt tensioning issue. I gotta fix that. 

stopped in the middle and blinking red at you: hit stop on lightburn, open preview window (icon that looks like a tv on toolbar), use slider to go to just about where you were, and select "start from here". 

(not yet tried)

In lightburn I recommend turning on advanced settings and using optimisation settings to set the priority layer -> group. apparently this makes it cut piece by piece instead of jumping all over the place? 

extra passes at decreased power helps with fire-detection-in-error issues apparently
