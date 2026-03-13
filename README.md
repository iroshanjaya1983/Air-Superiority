Air Superiority
A fast-paced, web-based aerial combat simulation built with HTML5 Canvas and vanilla JavaScript. Take control of a fighter jet, engage ground targets, and evade enemy missiles in a procedurally generated battlefield.

Gameplay Preview.

Features
Physics-Based Flight: Smooth fighter jet controls with thrust, drag, and banking mechanics.
Combat Systems:
Air-to-Ground Missiles (AGM): Auto-lock and fire upon enemy targets.
Counter-Measures: Deploy anti-missile flares to intercept incoming threats.
Dynamic Enemies: Enemy SAM sites that track your movement and fire back.
Full HUD System: Includes health bars, ammo count, radar/minimap, and missile alerts.
Responsive Design: Plays smoothly on modern desktop browsers.
Zero Dependencies: Runs in a single HTML file with no external libraries (except Tailwind CSS via CDN for UI styling).
Controls
Key	Action
W / Arrow Up	Thrust (Accelerate)
S / Arrow Down	Brake / Slow Down
A / Arrow Left	Turn Left (Bank)
D / Arrow Right	Turn Right (Bank)
Space / Left Click	Fire Missile (Auto-locks nearest target)
E / Right Click	Launch Counter-Measure (Anti-Missile)
How to Play Locally
Clone the repository or download the source code.
Navigate to the project folder.
Open the index.html file in any modern web browser (Chrome, Firefox, Edge, Safari).
Technical Stack
HTML5 Canvas: For rendering the 2D game world, particles, and entities.
Vanilla JavaScript: For game logic, physics loops, and state management.
Tailwind CSS: For styling the UI elements (HUD, Menus).
RequestAnimationFrame: For smooth, frame-rate independent rendering.
Future Improvements
Add sound effects and background music.
Implement different enemy types (airborne enemies).
Add power-ups (health regeneration, weapon upgrades).
Mobile touch controls support.
License
This project is open source and available under the MIT License.

