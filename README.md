# Game of War 🃏

A digital implementation of the classic card game "War" built with vanilla JavaScript, HTML, and CSS. This interactive web game allows players to battle against the computer using a deck of cards fetched from an external API.

## 🎮 Game Overview

Game of War is a simple card game where:
- Players draw cards simultaneously 
- The player with the higher card value wins the round
- Points are awarded to the winner of each round
- The game continues until all cards are drawn
- The player with the most points at the end wins

## Features

- **Interactive Gameplay**: Click to draw cards and see results instantly
- **Real-time Scoring**: Track your score vs. the computer's score
- **Dynamic Card Display**: Visual card images for an authentic experience
- **Remaining Cards Counter**: See how many cards are left in the deck
- **New Deck Option**: Start fresh games with a newly shuffled deck
- **Responsive Design**: Clean, poker table-themed interface

## Technologies Used

- **Frontend**: HTML5, CSS3, Vanilla JavaScript
- **Build Tool**: Vite
- **API**: Scrimba Deck of Cards API
- **Styling**: Custom CSS with Google Fonts (Exo 2)

## Getting Started

### Prerequisites
- Node.js (version 14 or higher)
- npm or yarn package manager

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd bataille
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
# or
npm run dev
```

4. Open your browser and navigate to `http://localhost:5173` (or the port shown in your terminal)

### Building for Production

To create a production build:
```bash
npm run build
```

To preview the production build:
```bash
npm run preview
```

## How to Play

1. Click **"New Deck"** to shuffle a fresh deck of cards
2. Click **"Draw"** to draw two cards (one for you, one for the computer)
3. The higher card wins the round and earns a point
4. Continue drawing until all cards are used
5. The player with the most points wins!

## Project Structure

```
bataille/
├── index.html          # Main HTML file
├── index.css           # Styling and layout
├── index.js            # Game logic and API interactions
├── package.json        # Dependencies and scripts
├── vite.config.js      # Vite configuration
├── img/
│   └── table.png       # Background poker table image
└── README.md           # Project documentation
```

## Game Logic

The game implements standard War card rules:
- Card values: 2-10 (face value), Jack (11), Queen (12), King (13), Ace (14)
- Higher card wins the round
- Ties result in "War!" (no points awarded)
- Game ends when deck is exhausted

## Contributing

This project was created as part of the Scrimba Frontend Developer Career Path. Feel free to fork and modify for your own learning purposes.

## License

This project is for educational purposes. Card images and API provided by Scrimba.