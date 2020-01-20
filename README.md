![Imgur](https://i.imgur.com/k9pMRGE.png)
## By Peter Lefaivre of Noodle Games

### About:
Apogee is the accidental result of my experiments with procedural generation and physics-based gameplay in UE4. The goal is to create an accessible and mobile-compatible game that adds exploration elements to the traditional infinite scroller genre. I'm only a couple weeks into development, and as such still laying the foundations for the procedural algorithm, mechanics, and aesthetics. So far I've been having tons of fun creating the procedural planet generation algorithm and am super excited to expand upon it's complexity to provide a more interesting exploration-based experience. Apogee comes from a simple root concept, but holds the potential to become a pretty cool game, and that's where I want to take it!

### Link to the Game:
Apogee is hosted on github pages:
https://noodle-games.github.io/Apogee.github.io/index.html

### Controls:
- Boost: Lmb/Space/W
- Brake: Rmb/LCtrl/S
- Pause: P
- Dev Camera Zoom Out: Q
- Dev Camera Zoom In: E

### Roadmap:
A loose list of ideas and concepts in no particular order:
- Random planet colours: ✔
  - Two-toned randomization, ie. random land and ocean colours
- Random planet sprites: ✔
  - There's currently a fair amount of planet variety, but the more the better
- "Hero" Planets:
  - Unique planets that stand out and reward exploring farther from the starting planet
  - Largebois, supernovas, black holes, planets with rings, etc.
- Fuel/energy system: ✔
  - After quite a few iterations I'm becoming more happy with the current system
  - Outside orbit = lose fuel
  - Boosting = lose fuel
  - Inside orbit = gain fuel
- Actual effects when hitting a planet/dying: ✔
  - There's now big booms when hitting a planet or running out of fuel
- Ship Customization:
  - Hitting different "planets visited" milestones unlocks new ship sprites
- Actually implementing the info (?) interface: ✔
  - Briefly explain the game's objective and controls
  - Controls, How To Play, and Credits menus
- Adding sound:
  - There are some UE4 bugs that make implementing sound in an HTML5 project very cumbersome
  - I'll grind it out eventually
- Getting rid of the ugly interface around the actual game
  - Wrangling with all the extra garbage UE4 imbeds into packaged projects is a pain
  - Currently it's less ugly than version 0.0.1, but still needs some work
- Optimizing Procedural Generation: ✔
  - Transparent materials are really expensive on mobile and HTML, so instead of using 2D sprites I'm using models and basic shaders instead, which is actually way faster
  - Planets will despawn when outside of a certain radius of the player
- Aesthetic and colour correction improvements: ✔
  - Bringing everything together
