# Saturday League — Football

A small browser-playable football game made with HTML, CSS, and Canvas.

## Play

Open `index.html` in a modern browser. The full 90-minute match runs in about three real-time minutes.

- **WASD / arrow keys** move the selected player
- **Shift** sprint
- **Space** shoot when in possession
- **E** pass
- **Q** switch to the nearest teammate
- **Escape** pause; **Enter** restart after full time
- Touch controls appear on smaller screens

## Recent gameplay improvements

- A richer pitch: twelve mowing bands, subtle turf texture and lighting, precise field markings, penalty areas and six-yard boxes, center circle, corner flags, and detailed goal nets.
- More purposeful team movement: players return to role-based positions, adjust their shape toward the ball, spread out to avoid bunching, support teammates in possession, and defend by pressing or covering space.
- Smarter ball decisions: AI players look for forward passing options, dribble into open space, and shoot when near goal; opponents challenge for loose balls and possession.
- Animated spectators, stadium lighting, ad boards, benches, tunnel, player movement, and fluttering kits.

This is still a lightweight 2D game, not a 3D simulation. The players are controlled by simple game AI, but their movement is now designed around team shape, space, and ball possession rather than all chasing the ball.

## Club career

Open [`career.html`](career.html) to manage your squad, make transfers, train players, upgrade facilities, and progress through the league. Career mode currently simulates match results separately from the live match.

## Inspiration

An original project inspired by the broad appeal of football games such as Dream League Soccer. It does not use DLS branding, code, art, or proprietary assets.
