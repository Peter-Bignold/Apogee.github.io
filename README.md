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
- Random planet sprites:
  - Stars
  - Eliptical/non-spherical planets with craters, etc.
- "Hero" Planets:
  - Unique planets that stand out and reward exploring farther from the starting planet
  - Largebois, supernovas, black holes, planets with rings, etc.
- Fuel/energy system:
  - The current system works but it's rough
  - I may redesign it into an item-based system later on
- Actual effects when hitting a planet/dying:
  - Right now the rocket sprite just disappears then the game fades to the end screen
  - Explosion/camera shake
- Ship Customization:
  - Hitting different "planets visited" milestones unlocks new ship sprites
- Actually implementing the info (?) interface: ✔
  - Will briefly explain the game's objective and controls
- Adding sound:
  - There are some UE4 bugs that make implementing sound in an HTML5 project extremely difficult
  - I'll grind it out eventually
- Getting rid of the ugly interface around the actual game
  - This is imbedded into the UE4 packaging of the game, and I'm trying to work out a solution to remove it
- Optimizing Procedural Generation: ✔
  - Transparent materials are really expensive on mobile and HTML, so instead of using 2D sprites I'm using actual models and basic shaders instead, which is actually way faster
- Aesthetic and colour correction improvements:
  - Bringing everything together (will come in time)
