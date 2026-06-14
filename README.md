# Basketball With Swords

**Basketball With Swords** is a fast arcade sports game where basketball, sword fighting, and tournament progression collide in one browser-playable HTML5 game.

You control the Kings and fight through a three-team crown ladder:

1. The Rookies
2. The Challengers
3. The Reigning Champs

Each matchup is played over four short quarters. Move, dash, slash, steal, shoot, dunk, and win each crown on the road to the championship final.

## Play

- **Playable game:** https://boneshaman.github.io/BasketballWithSwords/
- **GitHub repository:** https://github.com/BoneShaman/BasketballWithSwords

The game is designed for modern desktop and mobile browsers. Landscape orientation is recommended on mobile.

## Features

- A complete Rookies → Challengers → Reigning Champs tournament.
- Rookie Crown, Challenger Crown, and Champ Crown progression screens.
- Four-quarter basketball matches.
- Sword-rush attacks, steals, blocks, and passing-lane cuts.
- Hold-and-release shooting with a timing meter.
- Two-point and three-point scoring based on court position.
- Buzzer-beater logic for shots released before the horn.
- Quarter-break scoreboard screens.
- Keyboard, mouse, touch, and gamepad-style input logic.
- Fullscreen landscape requests on supported mobile browsers.
- Distinct uniforms for each opponent tier.
- Adaptive two-tier rubber banding that escalates opponent pressure.
- Quarter-aware original music, Canvas-rendered visual effects, and procedural arcade sound effects.

## How To Play

### Objective

Climb the crown ladder:

1. Beat the **Rookies** and win the **Rookie Crown**.
2. Beat the **Challengers** and win the **Challenger Crown**.
3. Beat the **Reigning Champs** and win the **Champ Crown**.

If you lose, **Try Again** restarts the current team rather than the entire tournament.

### Keyboard And Mouse

- Move: `WASD` or arrow keys
- Action / sword rush / slash / block: `Space` or left click
- Shoot: hold `M` or right click, then release
- Pause: `P` or `Escape`

Right click is captured by the game while playing, so it does not open the browser context menu.

### Touch

- Left joystick: move
- **ACTION**: dash, slash, rush, or block
- **SHOOT**: hold to charge and release to shoot
- **PAUSE**: pause or resume

### Core Mechanics

- Release SHOOT in the green timing zone for the best scoring chance.
- Shoot from behind the painted arc for three points.
- Use ACTION while carrying the ball to sword-rush through defenders.
- Use ACTION on defence to slash at the carrier, cut a pass, or block a dunk.
- A shot released before the buzzer can still count after time expires.
- The ACTION button refills as the sword-rush cooldown recovers.

## What I Made

This is a single-player browser arcade game built primarily as one self-contained HTML file using Canvas and JavaScript. It includes the court renderer, player controls, opponent AI, tournament state, scoring, touch layout, sound effects, visual effects, and responsive presentation.

The game intentionally aims for strange, immediate arcade fun rather than realistic basketball simulation. Every match should create a compact story of steals, sword clashes, rushed shots, dunks, comebacks, and last-second attempts.

## How Codex Helped

Codex helped rapidly prototype, test, and iterate the game through many focused gameplay passes rather than one large static build.

Major iteration areas included:

- Turning the concept into a working HTML5 Canvas game.
- Building movement, AI opponents, shooting, scoring, and sword-rush systems.
- Improving mobile controls and landscape playability.
- Fixing buzzer beaters, score transitions, cooldowns, and match flow.
- Adding tournament progression and same-team retry logic.
- Balancing opponent behaviour with adaptive rubber banding.
- Improving score screens, cooldown indicators, team readability, and progression.
- Testing keyboard, mouse, touch, and browser gameplay paths.

## Development Status

This competition build is still being finished. The music tracks are integrated; upcoming work includes expanding sound effects and completing the last polish and balancing passes.

The repository will be updated as those competition-ready improvements land.
