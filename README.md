# Shadow Ninjas

**Shadow Ninjas** is a 3D action game built with Unity and C#. Play as a ninja, navigate enemy-filled levels, use shurikens to take down targets, and progress through the game's stages.

## Features

- Third-person 3D ninja gameplay
- Player movement and jumping
- Target locking and shuriken throwing
- Enemy behaviour and projectile combat
- Multiple playable levels
- Main menu, controls guide, pause menu, and credits
- Gameplay audio, animations, and environmental assets
- Player progress/save-system scripts

## Built With

- **Game engine:** Unity
- **Programming language:** C#
- **Packages:** Unity UI, TextMesh Pro, Timeline, and Unity Test Framework

## Getting Started

### Requirements

- Unity Hub
- A Unity Editor version compatible with the project files
- A desktop computer that can run the Unity Editor

> The uploaded project archive does not include `ProjectSettings/ProjectVersion.txt`, so the exact Unity Editor version could not be confirmed. If Unity prompts you to select an editor version, use a compatible version and check for upgrade warnings before saving changes.

### Open the project

1. Download or clone this repository.
2. Open **Unity Hub**.
3. Select **Add** (or **Add project from disk**).
4. Choose the folder containing `Assets`, `Packages`, and `ProjectSettings`.
5. Open the project and allow Unity to import its assets.

### Run the game

1. In Unity, open `Assets/Scenes/MainMenu.unity`.
2. Press **Play** in the Editor.
3. Start the game from the main menu.

The configured build scenes are `MainMenu`, `Level_0`, `Level_1`, `Level_2`, `Level_3`, and `Credits`.

## Controls

| Input | Action |
| --- | --- |
| `W` `A` `S` `D` | Move |
| `Space` | Jump |
| Right mouse button | Aim / lock on to a target |
| Left mouse button | Throw a shuriken at a locked target |
| `Esc` | Pause or resume |

Controls are based on the player and pause-menu scripts; in-game instructions may provide additional context.

## Project Structure

```text
Assets/
  Animation/       Animation clips and controllers
  Audio/           Music and sound effects
  Backgrounds/     Background and UI images
  Characters/      Character models, textures, and animations
  Scenes/          Main menu, levels, and credits
  Scripts/         Player, enemy, menu, save, and gameplay logic
  Textures/        Environment and object textures
Packages/          Unity package manifest
ProjectSettings/   Unity project and build settings
```

## Main Scenes

- `MainMenu.unity` — game entry point and controls/menu flow
- `Level_0.unity` — first configured gameplay scene
- `Level_1.unity` — level 1
- `Level_2.unity` — level 2
- `Level_3.unity` — level 3
- `Credits.unity` — credits screen

## Notes

- Open the project through Unity Hub rather than opening individual asset files.
- Unity generates local folders such as `Library/` and `Temp/`; these are excluded by the repository's `.gitignore`.
- Some source assets are large. GitHub rejects individual files larger than 100 MB and warns about files over 50 MB. If a push reports a large-file warning or rejection, consider Git LFS for suitable assets or reduce the asset size before pushing.
- Verify that you have permission to redistribute all included models, textures, music, and sound effects before publishing the repository publicly.

## License

No license file was included with the supplied project. Unless a license is added, others should not assume they have permission to reuse or redistribute the code or assets.
