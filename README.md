# ❤️ Angina Adventure - Final Upgrade

A health-themed platformer game where you navigate through arterial challenges to reach the heart!

## Features

### Gameplay
- **Platforming**: Navigate ascending platforms across a 4500px world
- **Resource Management**: Collect oxygen coins to survive (oxygen depletes rapidly)
- **Combat**: Shoot plaques (cholesterol blockages) with the F key
- **Multiple Difficulty Levels**: Easy, Normal, and Hard modes
- **Final Boss Area**: Plaque rush with three enemy types

### Game Mechanics

#### Oxygen System
- Oxygen depletes constantly at different rates per difficulty
- Collect cyan coins (+10 oxygen)
- Screen darkens as oxygen runs low (visual feedback)
- Lose a life when oxygen hits 0

#### Enemy Types (Final Wave)
- **Normal Plaques** (Red): Standard speed, 50 points
- **Fast Plaques** (Orange): Double speed, 75 points
- **Tank Plaques** (Dark Red): Slow, durable, 100 points

#### Scoring
- **+50 points**: Kill normal plaque
- **+75 points**: Kill fast plaque
- **+100 points**: Kill tank plaque
- **+10 points**: Collect oxygen coin
- **+5 points**: Fire a bullet

### Features
- ✅ **Difficulty Modes** (Easy/Normal/Hard) - affects oxygen drain and enemy density
- ✅ **Pause System** (Press P) - pause and resume gameplay anytime
- ✅ **Score Tracking** - real-time score display
- ✅ **Time Tracking** - elapsed time in seconds
- ✅ **Mobile Controls** - touch buttons for mobile/tablet play
- ✅ **Enemy Variety** - normal, fast, and tank plaques with different behaviors
- ✅ **Immersive Audio** - heartbeat sound that intensifies with low oxygen
- ✅ **Polish** - smooth animations, pulsing heart, oxygen overlay effects

## Controls

### Keyboard
- **Arrow Keys** - Move left/right or jump
- **Space** - Jump
- **F** - Shoot
- **P** - Pause/Resume
- **R** - Restart after game over
- **Enter** - Start game from menu

### Mobile/Touch
- **D-Pad** - Move left/right
- **JUMP Button** - Jump
- **SHOOT Button** - Fire

## Game Flow

1. **Menu** → Select difficulty → Press ENTER
2. **Play** → Collect oxygen, shoot plaques, reach the heart
3. **Win/Lose Screen** → Final score and time
4. **Restart** → Press R or ENTER for menu

## Difficulty Settings

| Setting | Oxygen Drain | Enemy Count | Final Wave |
|---------|------|------------|------------|
| **Easy** | Slow (0.03/frame) | 4 plaques | 5 max |
| **Normal** | Medium (0.06/frame) | 6 plaques | 5 max |
| **Hard** | Fast (0.1/frame) | 8 plaques | 8 max + spawning |

## How to Play

1. Start the game and select your difficulty
2. Use arrow keys or touch controls to move
3. Press SPACE or JUMP to double-jump
4. Press F or SHOOT to fire bullets at plaques
5. Collect cyan oxygen coins to refill your oxygen meter
6. Avoid touching plaques - they cause you to lose a life
7. Reach the glowing heart at the end to win!

## Technical

- Pure JavaScript (no dependencies)
- Canvas-based rendering
- Web Audio API for heartbeat sounds
- Responsive touch controls for mobile
- Collision detection
- Particle-style animations

## Color Theme

- **Background**: Dark red (#7a0f0f) - arterial theme
- **Player**: Red cell with pink nucleus
- **Plaques**: Gold (normal), Orange (fast), Dark red (tank)
- **Oxygen**: Cyan coins
- **Heart**: Pulsing pink/red gradient
- **UI**: White text

---

**Play online**: Open `index.html` in any modern web browser!
