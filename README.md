# 🚀 Space Invaders — OOP Semester Project

A Space Invaders clone built in C++17 using the raylib graphics library,
developed as a semester project for CSE142 Object Oriented Programming 
Techniques at IBA Karachi.

## 👥 Authors
- Anosha Kumari — ERP: 33429
- Kartar Singh — ERP: 32431
- Sagar Kataria — ERP: 32422

## 🎮 How to Play
| Key | Action |
|-----|--------|
| A / LEFT | Move left |
| D / RIGHT | Move right |
| SPACE | Fire laser |
| R | Restart game |

## 🛠️ How to Build
Make sure raylib is installed, then:
```bash
g++ -std=c++17 -Wall -o SpaceInvaders s.cpp -lraylib -lopengl32 -lgdi32 -lwinmm
./SpaceInvaders.exe
```

## 📁 Project Structure
- `Entity.h` — Abstract base class
- `Spaceship.h` — Player entity
- `Alien.h` — Enemy entity
- `Laser.h` — Player projectile
- `AllienBullets.h` — Enemy projectile
- `Game.h` — Master coordinator
- `s.cpp` — Entry point

## 🔧 Requirements
- C++17 compiler (g++ MinGW-w64)
- raylib 5.0
- Rocket.png and alien_2.png in same directory

## 📚 Course
CSE142 Object Oriented Programming Techniques
Spring 2026 — IBA Karachi
