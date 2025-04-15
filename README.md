# DonutRun - A Platform Game with Kaboom.js

A Mario-style platformer game built using Kaboom.js, featuring multiple levels, enemies, and coin collection mechanics.

## 🛠️ Technical Stack

- **Game Engine**: Kaboom.js
- **Language**: JavaScript (ES6+)
- **Asset Loading**: Custom asset loader
- **Sound Management**: Custom sound manager
- **UI System**: Custom UI manager

## 🎮 Game Features

- Multiple levels with increasing difficulty
- Coin collection system
- Lives system with respawn mechanics
- Various enemies (Fish, Spiders, Birds)
- Different environments (Forest, Castle, Sky)
- Smooth character animations
- Background music and sound effects
- Responsive controls

## 🎯 Gameplay

- Use arrow keys for movement (←, →)
- Space bar to jump
- Collect all coins to progress to next level
- Avoid enemies and obstacles
- You have 3 lives to complete each level

## 📁 Project Structure
project/
├── assets/ # Game sprites and images
├── content/ # Level layouts and configurations
├── entities/ # Game characters and objects
├── libs/ # Kaboom.js library
├── sounds/ # Game audio files
├── utils/ # Helper functions and managers
├── index.html # Entry point
└── main.js # Game initialization


## 🚀 Getting Started

1. Clone the repository:
```bash
git clone <repository-url>
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

4. Open your browser and navigate to `http://localhost:5500`

## 🎮 Controls

- **←**: Move left
- **→**: Move right
- **↓**: Drop through platforms
- **Space**: Jump
- **Enter**: Start game/Confirm

## 🔧 Game Components

### Player
- Double jump capability
- Coin collection
- Lives system
- Collision detection with enemies

### Levels
- Unique backgrounds
- Different enemy types
- Platform layouts
- Coin placement

### UI Elements
- Lives counter
- Coin counter
- Menu screens
- Control instructions

## 🎵 Sound System

- Background music for each level
- Sound effects for:
  - Jumping
  - Coin collection
  - Enemy hits
  - Menu navigation

## 🛠️ Development

### Adding New Levels
1. Create a new level layout in `content/levelX/`
2. Add level configuration
3. Create level mappings
4. Register the level in `main.js`

### Adding New Enemies
1. Create enemy sprite
2. Add enemy class in `entities/`
3. Configure enemy behavior
4. Add to level configuration
