# Asteroid Game (C++ / SFML with CMake)

This repository contains a simple **Asteroids-style arcade game** written in modern C++ and built with **CMake** and **SFML**.

It started from the official SFML CMake project template, and has been adapted into a small game project where you control a spaceship, dodge and destroy asteroids, and try to survive as long as possible.

Features (planned / in progress):

- C++17/20 codebase using CMake
- SFML-based windowing, graphics, input, and audio
- Player ship movement and rotation
- Asteroid spawning and movement
- Basic collision detection and scoring
- Cross-platform build support (Windows / Linux / macOS), depending on your toolchain

---

## Quick Start

### 1. Prerequisites

- [Git](https://git-scm.com/downloads)
- [CMake](https://cmake.org/download/)
- A C++ compiler:
  - **Windows**: MSVC (Visual Studio), or MinGW via MSYS2
  - **Linux**: `g++` or `clang++`
  - **macOS**: Xcode / `clang++`

You don’t need to install SFML manually — it’s fetched and built automatically by CMake using `FetchContent`.

---

### 2. Getting the Code

If you haven’t already:

```bash
git clone <your-repo-url> AsteroidGame
cd AsteroidGame
