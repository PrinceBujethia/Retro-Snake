# Retro Snake

A modern, retro-inspired Snake game built with C++ and [raylib](https://www.raylib.com/). This project demonstrates clean code architecture, object-oriented programming, and real-time game development concepts.

## Download

**[Download Retro Snake for Windows](https://github.com/PrinceBujethia/Retro-Snake/releases/download/Downlaod/Retro-Snake.exe)**

Just click the link above to get the executable and start playing instantly!

## Features
- **Classic Snake Gameplay**: Eat food, grow longer, and avoid collisions with walls and yourself.
- **Smooth Animations**: Responsive controls and smooth movement using real-time event handling.
- **Audio Feedback**: Sound effects for eating food and hitting walls.
- **Custom Graphics**: Pixel art food and a retro-themed UI.
- **Score Tracking**: Real-time score display.

## Technologies & Concepts Used
- **C++ STL**: Utilizes `std::deque` for efficient snake body management.
- **Object-Oriented Design**: Encapsulated logic in `Snake`, `Food`, and `Game` classes for maintainability and scalability.
- **Raylib Library**: Handles graphics, input, audio, and timing for real-time gameplay.
- **Event-Driven Programming**: Uses time-based event triggers for smooth updates and input handling.
- **Collision Detection**: Implements collision logic for food, walls, and self-intersection.
- **Resource Management**: Proper loading/unloading of textures and sounds to prevent memory leaks.
- **Randomization**: Ensures food spawns in valid locations using random number generation and collision checks.
- **Separation of Concerns**: Game logic, rendering, and input are cleanly separated for clarity.

## Getting Started

### Prerequisites
- [raylib](https://www.raylib.com/) installed
- C++ compiler (e.g., MinGW-w64)

### Build & Run
1. Clone the repository:
   ```sh
   git clone https://github.com/PrinceBujethia/Retro-Snake.git
   ```
2. Build the project:
   ```sh
   mingw32-make RAYLIB_PATH=path/to/raylib PROJECT_NAME=main OBJS=src/*.cpp BUILD_MODE=DEBUG
   ```
3. Run the executable:
   ```sh
   ./main.exe
   ```

## Controls
- **Arrow Keys**: Change snake direction

## File Structure
```
├── src/main.cpp         # Main game logic
├── Graphics/food.png    # Food sprite
├── Sounds/eat.mp3       # Eat sound
├── Sounds/wall.mp3      # Wall collision sound
├── Makefile             # Build instructions
├── README.md            # Project documentation
```

## Why This Project Stands Out
- **Clean, modular code** suitable for extension and learning
- **Real-world game architecture** using C++ and raylib
- **Demonstrates mastery of OOP, resource management, and event-driven design**
- **Ready for portfolio and recruiter review**

---

**Created by PrinceBujethia**

