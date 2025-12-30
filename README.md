# MyRPG - 2D Adventure Game

An open-world RPG developed in **C** using the **CSFML** library, inspired by classics like Undertale/Zelda.

## 🎮 Game Overview
In this game, you explore a world, interact with NPCs, manage your inventory, and fight enemies. This project was a major milestone in learning software architecture and game loop optimization.

## ✨ Key Features
- **Dynamic Engine:** Smooth movements, collision handling, and map transitions.
- **Inventory System:** Item management and equipment stats.
- **Combat System:** Real-time / Turn-based (à adapter selon ton projet) combat logic.
- **Save/Load:** Persistence of player data.
- **UI/UX:** Custom menus, health bars, and dialogue boxes.

## 🖼️ Screenshots
| Exploration | Combat / Inventory |
|:---:|:---:|
| ![Explo](screenshots/gameplay1.png) | ![Combat](screenshots/gameplay2.png) |

## 🛠️ Installation
Requires `libcsfml-dev` to be installed.
```bash
# Successor RPG

Un jeu d'aventure 2D développé en **C** avec la bibliothèque **CSFML**. Projet réalisé dans le cadre d'un projet de groupe à l'Epitech — objectif : concevoir un moteur simple, un système d'inventaire, et un système de combat tout en appliquant de bonnes pratiques en C.

## Table des matières
- Description
- Fonctionnalités
- Prérequis
- Compilation et exécution
- Structure du dépôt
- Contribution
- Auteurs & Remerciements
# Successor RPG

Successor RPG is a 2D adventure game written in C using the CSFML library. It was created by a group of students (Epitech) as a learning project and for fun — intended for education and non-commercial enjoyment.

## Table of Contents
- Description
- Features
- Requirements
- Build & Run
- Repository Structure
- Contribution
- Authors & Credits
- Licensing

## Description
Successor RPG is a prototype 2D RPG featuring exploration, dialogues, quests, inventory, and combat. The codebase is organized for readability and modularity to make it easier to extend.

## Key Features
- 2D engine with collision handling and zone transitions
- Inventory and equipment system
- Combat mechanics (see `srcs/combat`)
- Save/load support
- Menus and dialogue system

## Requirements
- Linux
- C compiler (gcc/clang)
- `libcsfml-dev` (CSFML graphics/window/system/audio)

On Debian/Ubuntu:
```bash
sudo apt update
sudo apt install build-essential libcsfml-dev
```

## Build & Run
From the repository root:
```bash
make
./my_rpg
```

Useful targets:
- `make` : build the project
- `make clean` : remove object files
- `make fclean` : remove object files and the executable
- `make re` : clean and rebuild

## Repository Structure (selected)
- `srcs/` : C source files
- `lib/` : utility functions
- `assets/` : images, music, dialogue text
- `includes/` : public headers
- `saves/` : save files

See `srcs/init` for entity initialization and `srcs/combat` for combat logic.

## Contribution
Contributions are welcome — please follow `CONTRIBUTING.md` for the contribution guide.

## Authors & Credits
This project was created by a team of Epitech students. Contributors:

- Angel-42 — https://github.com/Angel-42
- Mattaiuss — https://github.com/Mattaiuss
- EmilioEpitech — https://github.com/EmilioEpitech
- ReverteOlivier — https://github.com/ReverteOlivier

See `AUTHORS.md` for details.

## Licensing
The project uses dual-licensing:

- **Source code** (files `.c`, `.h`, `lib/`, `srcs/`, etc.): licensed under the **MIT License** (see `LICENSE`).
- **Assets** (images, music, sounds, dialogues, files under `assets/`, `musics/`, etc.): licensed under **Creative Commons Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)** — see `LICENSE-ASSETS`.

This separation keeps code open for reuse while protecting assets from commercial use without permission.

## Bug reports / Contact
- Open an `issue` to report a bug or suggest an improvement.
- For direct contact, use the repository's GitHub page (issues or PRs).

---