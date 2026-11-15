# Rocket Game: Mission Architect

**Repository description:** A Turkish/English space mission design and flight game built with Python and Pygame. Design a spacecraft within budget and engineering limits, fly to objectives, complete missions, and unlock new hardware. Inspired by NASA missions; not affiliated with NASA.

Rocket Game: Mission Architect is a 2D space mission design and flight game with Turkish and English language support. Choose a mission, configure a spacecraft, and review its budget, mass, power, delta-v, and communications telemetry before launch. Then pilot the spacecraft, land at objectives, and scan them to complete the mission.

## Features

- Turkish and English interface
- Spacecraft design with budget, mass, power, delta-v, and communications telemetry
- Unlockable missions and hardware shop
- 2D flight, landing, scanning, and mission objectives
- Fullscreen toggle with `Esc`

## Requirements

- Python 3.10 or newer
- Pygame 2.5 or newer (2.x)

## Installation and launch

```bash
python -m pip install -r requirements.txt
python main.py
```

The game starts in fullscreen. Press `Esc` to switch between fullscreen and windowed mode. The game uses built-in shapes and system fonts, so no external assets are needed.

## Controls

| Key | Action |
| --- | --- |
| `W` / `↑` | Thrust |
| `S` / `↓` | Brake |
| `A` / `←`, `D` / `→` | Rotate |
| Hold `E` | Scan an objective while landed |
| `Esc` | Toggle fullscreen |
| Mouse wheel / arrow keys | Scroll the shop |

## Project structure

```text
.
├── main.py
├── requirements.txt
├── .gitignore
└── README.md
```

## Notes

- Mission data and gameplay are kept in `main.py` for a simple setup.
- Progress and purchased items reset when the game is restarted.
- This is an independent educational game. NASA-inspired names and concepts are used for gameplay only; the project is not affiliated with, endorsed by, or sponsored by NASA.
