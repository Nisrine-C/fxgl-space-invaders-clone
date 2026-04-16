# FXGL Space Invaders Clone

A classic Space Invaders clone built in Java using the FXGL game engine.


## Features

- Modern Java 17+ codebase built with FXGL (JavaFX game engine)
- Classic wave-based gameplay: shoot aliens, avoid enemy fire, clear levels!
- Player, enemy and wall entity system
- High score saving (`hiscore.dat`)
- Particle system, levels, and power-ups
- Organized package structure for components, collision, events, UI, and more

## Project Structure

```
src/
└── main/
    └── java/
        └── fxgl/
            └── spaceinvader/
                ├── GameApp.java           # Main class/entry point
                ├── Config.java
                ├── EnemyManager.java
                ├── Player.java
                ├── ...
                ├── collision/
                ├── component/
                ├── event/
                ├── level/
                ├── particles/
                └── ui/
    └── resources/
```


## Getting Started

1. **Clone the repo**
   ```sh
   git clone https://github.com/Nisrine-C/SpaceInvader.git
   cd SpaceInvader
   ```
2. **Build and Run with Maven**
   ```sh
   ./mvnw clean install
   ./mvnw exec:java -Dexec.mainClass="fxgl.spaceinvader.GameApp"
   ```
   Or run with your favorite IDE (set `fxgl.spaceinvader.GameApp` as the main class).


## Controls

- **Arrow Keys / A/D or Left/Right:** Move ship
- **Space:** Fire
- **Esc:** Exit


## Dependencies

- Java 11+
- FXGL 11 (see [FXGL website](https://github.com/AlmasB/FXGL))
- Maven

## Screenshots

*Add gameplay screenshots here!*


## Acknowledgments

- FXGL Game Engine ([github.com/AlmasB/FXGL](https://github.com/AlmasB/FXGL))
- Inspired by Space Invaders by Taito 1978
