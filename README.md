# html-js-particle-accellerator-modell
The Titles says Anything
---
I build out of thin Air an Modell of an Particle Accellerator,
based on physical formulas, but not too complex.
---
## Controls
You can controll nearly anything from the "controll-room" (the grey box in the upper left corner).
Your options are:
- in the first two input-boxes you can write the amount of Force you wan't to add to you particle, that controls nearly directly the accellertion
  - the accellertion won't go down by it self so the simulation doesn't simply stop
- with the "Apply Forces" button you can apply the changes, but attention: the accellertion (a) will behave like this: a = a + f
  - this means that the new force value (f) will be added to the accellertion (a)
  - to reduce the accellertion you will need two add a negative amount of force
- the "velocity..." inputs are directly controlling the velocity for the x and y value of the particle
- with "Apply Velocity" you can apply the changes, but the accellertion won't be resetet
- the checkbox "Show Trail?" can be used to controll if or if not the particle has an trail out of 4 red dots
- the "mode" dropdown menu lets you controll how your browser will render the particle:
  - "requestAnimationFrame" means the rendering speed (FPS) will be controllt by the Hz value of your monitor
  - "setTimout" with the number value in the input box right next to it will let you controll the time in ms that will be waited befor the next "tick" will be made
    - this can be usefull if you have a PC that is not that good
- the x and y inputs let you controll the position of the particle without resetting the accellertion and velocity
- "Load Coords" will load the coordinates of the particle in the moment your pressed the button (plus latency)
- "Apply Coords" will apply the new position data in the next "tick"
Want to experiment now? [https://taminodev.github.io/html-js-particle-accellerator-modell/](https://taminodev.github.io/html-js-particle-accellerator-modell/)
