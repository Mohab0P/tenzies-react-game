# 🎲 Tenzies - Dice Game

A fun and interactive dice game built with React where players roll dice until all dice show the same value. Click dice to freeze them and try to get all ten dice to match!

![Tenzies Game](https://img.shields.io/badge/React-18.3.1-blue?style=for-the-badge&logo=react)
![Vite](https://img.shields.io/badge/Vite-Latest-purple?style=for-the-badge&logo=vite)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

## 🎮 How to Play

1. **Roll the dice** - Click the "Roll" button to roll all unfrozen dice
2. **Freeze dice** - Click on any die to freeze it at its current value (it will turn green)
3. **Match all dice** - Keep rolling and freezing until all 10 dice show the same number
4. **Win!** - When all dice match, confetti will appear and you can start a new game

## ✨ Features

- 🎯 **Interactive dice rolling** with realistic animations
- 🔒 **Freeze mechanism** - Click dice to hold their values
- 🎉 **Victory celebration** with confetti animation
- ♿ **Accessibility features** - Screen reader support and ARIA labels
- 📱 **Responsive design** - Works on desktop and mobile devices
- 🎨 **Modern UI** - Clean, intuitive interface with smooth animations

## 🚀 Getting Started

### Prerequisites

- Node.js (version 14 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/tenzies-dice-game.git
   cd tenzies-dice-game
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```

4. **Open your browser**
   Navigate to `http://localhost:5173` to play the game!

### Build for Production

```bash
npm run build
```

## 🛠️ Tech Stack

- **React 18.3.1** - Modern React with hooks
- **Vite** - Fast build tool and development server
- **nanoid** - Unique ID generation for dice
- **react-confetti** - Victory celebration animation
- **CSS3** - Custom styling with Grid and Flexbox

## 📁 Project Structure

```
tenzies-dice-game/
├── src/
│   ├── App.jsx          # Main game component
│   ├── Die.jsx          # Individual die component
│   ├── index.jsx        # App entry point
│   └── index.css        # Game styles
├── index.html           # HTML template
├── package.json         # Dependencies and scripts
└── README.md           # This file
```

## 🎯 Game Logic

The game uses React hooks to manage state:
- `useState` for dice state and game status
- `useRef` for button focus management
- `useEffect` for victory detection

Each die has:
- **Value**: Random number 1-6
- **isHeld**: Boolean for frozen state
- **id**: Unique identifier

## 🎨 Styling

The game features a modern, clean design with:
- Dark blue background (`#0B2434`)
- Light gray game board (`#F5F5F5`)
- Green frozen dice (`#59E391`)
- Purple roll button (`#5035FF`)
- Responsive grid layout for dice

## 🤝 Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Inspired by the classic Tenzies dice game
- Built as part of a React learning project
- Uses Google Fonts (Karla) for typography

---
