https://gemini.google.com/app


Create an interactive hand-gesture-based game with MediaPipe hand tracking and HTML5 Canvas.

Gameplay Overview
Players use their hands (detected via webcam) to catch falling objects on screen:

❄️ Snowflakes (+1 point) - Basic collectibles
⭐ Gold Stars (+5 points) - High-value items
🧨 Fireballs (-1 life) - Hazards to avoid
❤️ Hearts - Life recovery items that appear every 50 points

Key Features
60-second timed gameplay with increasing difficulty
Lives system: Start with 3 lives, lose one per fireball contact
Power-up mechanic: Close your fist to trigger a "snowstorm" that clears non-fireball entities and freezes cooldown for 5 seconds
Real-time hand tracking: Uses finger tips to detect collisions with falling objects
Dynamic difficulty: Entity speeds increase over time
Audio feedback: Different tones for various actions (catches, damage, power-ups)
Visual effects: Screen shake on damage, color flashes for penalties/healing

Technical Stack
- MediaPipe Hands API for hand gesture recognition
- Web Audio API for procedural sound generation
- HTML5 Canvas for game rendering
- Vanilla JavaScript for game logic

The game combines motion capture with casual arcade-style mechanics, creating an engaging full-body interactive experience.

Use one html file only.


Enjoy! 
Happy Holidays! ☃️