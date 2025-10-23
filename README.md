# StarFlight - Space Shooter Game

A complete browser-based space shooter game built with HTML5, CSS3, and JavaScript featuring realistic physics, sound effects, and multiple difficulty levels.

## 🎮 Features

### Core Gameplay
- 🚀 **Controllable spaceship** with realistic physics and rotation
- 🔥 **Dynamic flame trail** that shrinks with distance behind the rocket
- 🪨 **Smart asteroids** with random movement and collision physics
- 🔴 **Laser shooting system** with realistic projectile physics
- 💥 **Asteroid destruction** with explosion effects
- ⚡ **Realistic collision physics** between all objects

### Game Modes
- 🟢 **Easy Mode**: 1 asteroid - perfect for beginners
- 🟡 **Medium Mode**: 5 asteroids - balanced challenge  
- 🔴 **Hard Mode**: 10 asteroids - intense space combat

### Audio Experience
- 🎵 **Laser sound effects**: High-pitched pew-pew sounds
- 💥 **Explosion sounds**: Deep rumbling when asteroids are destroyed
- 🚀 **Thruster sounds**: TIE fighter-like engine noise during acceleration
- 🔊 **Web Audio API**: All sounds generated synthetically for consistent experience

### Visual Effects
- ✨ **Rocket rotation**: Ship points in direction of movement
- 🔥 **Shrinking flame trail**: Realistic exhaust that fades with distance
- 🎯 **Collision detection**: Precise physics between all objects
- 🏆 **Victory screen**: Celebration when all asteroids are destroyed

## 🎯 Controls

| Key | Action |
|-----|--------|
| **Arrow Keys** | Steer the rocket in any direction |
| **+ / =** | Increase rocket speed |
| **- / _** | Decrease rocket speed |
| **Spacebar** | Fire laser in direction rocket is pointing |

## 🚀 How to Play

1. **Start**: Open `index.html` in your web browser
2. **Choose Difficulty**: Select Easy (1), Medium (5), or Hard (10 asteroids)
3. **Navigate**: Use arrow keys to fly through space
4. **Combat**: Press spacebar to shoot lasers at asteroids
5. **Physics**: Collide with asteroids for realistic bouncing effects
6. **Win**: Destroy all asteroids to see the victory screen
7. **Repeat**: Click "Play Again" to try a different difficulty

## 🛠 Technical Features

### Physics Engine
- **Elastic collisions** between rocket and asteroids
- **Velocity exchange** based on implied mass differences
- **Boundary bouncing** for all objects
- **Directional movement** with momentum conservation

### Graphics System
- **Real-time rotation** using CSS transforms
- **Dynamic trail generation** with opacity and scale effects
- **Collision detection** using distance calculations
- **Responsive design** that works in any browser window size

### Audio System
- **Web Audio API** for all sound generation
- **Oscillator-based synthesis** for consistent cross-platform audio
- **Frequency modulation** for realistic sound effects
- **Volume balancing** between different sound types

## 🌐 Browser Compatibility

Works in all modern browsers supporting:
- HTML5 Canvas and DOM manipulation
- CSS3 Transforms and Animations  
- Web Audio API for sound effects
- ES6 JavaScript features

**Tested on**: Chrome, Firefox, Safari, Edge

## 🎯 Game Strategy Tips

- **Easy Mode**: Learn the controls and physics
- **Medium Mode**: Practice laser accuracy and movement
- **Hard Mode**: Master collision avoidance while staying aggressive
- **Pro Tip**: Use asteroid collisions to change direction quickly
- **Advanced**: Try to clear all asteroids without using speed controls

## 🚀 Future Enhancements

Potential features for future versions:
- Power-ups and special weapons
- Multiple rocket types
- Asteroid types with different behaviors
- Score system and leaderboards
- Multiplayer support

---

**Enjoy your space adventure!** 🌌✨

*Built with vanilla JavaScript - no frameworks required!*
