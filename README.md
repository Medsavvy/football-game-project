# Saturday League — Football

A browser football project with a playable 2D match, an experimental 3D match, and club career mode.

## Play

- **[3D football match](3d.html)** — WebGL stadium, perspective camera, 3D player models, animated movement, pitch, ball, goals, and stands. Requires a modern browser with WebGL and internet access for the Three.js library.
- **[2D football match](index.html)** — lightweight Canvas version; no dependencies.
- **[Club career](career.html)** — squad, transfers, training, facilities, and league progression.

### 3D match controls

- **WASD / arrow keys** move the selected player
- **Shift** sprint
- **Space** shoot when in possession
- **E** pass
- **Q** switch to the nearest teammate
- **Escape** pause; **Enter** restart after full time
- Touch controls are available on small screens

The 3D match runs a 90-minute game clock in about three real minutes. Players use role-based positioning, support runs, pressure, and passing/shooting decisions. This is a stylized real-time 3D prototype, not photorealistic 3D or a full commercial football simulation.

## 2D controls

WASD or arrows to move, Shift to sprint, Space to shoot, E to pass, and Q to switch players.

## Career mode

Manage a squad, make transfers, train players, upgrade facilities, and advance through the league. Career mode currently simulates match results separately from the live match.

## Inspiration

An original project inspired by the broad appeal of football games such as Dream League Soccer. It does not use DLS branding, code, art, or proprietary assets.
