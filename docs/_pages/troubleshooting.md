---
title: troubleshooting
layout: page
---

## current status / todolist

- vacuum dust out of rails and drive belts
- belt tensioning
- clean down the air assist slats and lens
- make jigs for other corners (cut a rectangle, push it into a corner, cut out the corner, label corner with marker)
- soak tray, not just slats
- sort out the requisite damp cloth

and also
- make the camera behave like dude managed

---

## issues

lightburn tells you yourlaser is busy: check the COM port is at COM4 instead of COM1

remember to home the laser if you've moved it to get to your piece, otherwise it gets Unhappy. but if you framed it and decided to move it, you can just shuffle it to the new bottom left corner

jiggles where the line should be straight/curves not as they should be: probably a belt tensioning issue. I gotta fix that. 

stopped in the middle and blinking red at you: hit stop on lightburn, open preview window (icon that looks like a tv on toolbar), use slider to go to just about where you were, and select "start from here". 

(not yet tried)

In lightburn I recommend turning on advanced settings and using optimisation settings to set the priority layer -> group. apparently this makes it cut piece by piece instead of jumping all over the place? 

extra passes at decreased power helps with fire-detection-in-error issues apparently
