# Parterapi
![Node.js](https://img.shields.io/badge/Node.js-339933?logo=node.js&logoColor=white)
![Three.js](https://img.shields.io/badge/Three.js-black?logo=three.js)
![JavaScript](https://img.shields.io/badge/JavaScript-yellow?logo=javascript)

Parterapi is a browser-based memory (concentration) game for up to four players. Players flip cards to find matching pairs using memory and strategy.

The game features smooth animations and a visual experience powered by Three.js.

---

## Features

- Multiplayer memory game (up to 4 players)
- Smooth card flip animations
- Real-time gameplay using WebSockets
- 3D-rendered interface with Three.js

---

## How It Works

- Game state and logic run on a Node.js server  
- The browser handles rendering and user interaction using Three.js  
- Client and server communicate in real time via WebSockets  

---


## Getting Started

### Prerequisites

- Node.js installed

---

### Installation

1. Clone the repository:

```bash
git clone https://github.com/Timalm90/Parterapi
cd Parterapi
```

2. Install dependencies:

```bash
npm install
```

---

### Running the Application

Start the server:

```bash
npm start
```

Then open:

```
http://localhost:3000
```

---

## Technology Stack

- Three.js — 3D rendering  
- Node.js — server runtime  
- WebSocket (`ws`) — real-time communication  

