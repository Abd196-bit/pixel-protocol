# Pixel Protocol

Pixel Protocol is a pixel-art platformer built with Godot. The project currently includes a startup screen, a playable level, animated player movement, collectible coins, background music, and a collection of reusable platformer assets.

## Requirements

- Godot 4.7 or newer

## Running the game

1. Clone the repository:

   ```bash
   git clone https://github.com/Abd196-bit/pixel-protocol.git
   cd pixel-protocol
   ```

2. Import `project.godot` in Godot.
3. Press **F6** to run the current scene or **F5** to run the project.

## Controls

| Action | Input |
| --- | --- |
| Move left | Left arrow |
| Move right | Right arrow |
| Jump | Spacebar |

## Project structure

```text
Assets/
  backgrounds/       Level and menu backgrounds
  branding/          Project and game icons
  player/            Player animation sprite sheets
  rocky_roads/       Environment, enemy, effect, object, tile, and UI art
Scenes/               Godot scenes
Script/               GDScript files
project.godot         Godot project configuration
```

All image filenames use lowercase `snake_case` and are stored under `Assets/`.

## Development status

Pixel Protocol is under active development. More levels, gameplay systems, and polish may be added over time.

