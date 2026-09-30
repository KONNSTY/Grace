# Grace

A Unity 2D project (Universal Render Pipeline).

- **Unity version:** 6000.6.2f1 (Unity 6.2)
- **Render pipeline:** Universal Render Pipeline (2D Renderer)
- **Input:** Unity Input System

## Requirements

- [Unity Hub](https://unity.com/download)
- **Unity 6000.6.2f1** — or a newer 6000.6.x revision (Unity will offer to upgrade the project)

## Getting started

1. Clone the repository:

   ```bash
   git clone https://github.com/KONNSTY/Grace.git
   ```

2. Add the project folder in the Unity Hub and open it with Unity 6000.6.2f1.
3. Open `Assets/Scenes/SampleScene.unity` to start working.

The first import may take a while because Unity regenerates the `Library/` folder and resolves packages.

## Project structure

| Path | Purpose |
| --- | --- |
| `Assets/Scenes/` | Scenes (entry point: `SampleScene.unity`) |
| `Assets/Settings/` | URP assets, renderer settings and input actions |
| `Assets/Welcome/` | Unity 2D welcome template assets |
| `Packages/` | Package manifest and lock file |
| `ProjectSettings/` | Unity project settings |

## Version control

This repository uses the standard Unity `.gitignore` (generated folders such as
`Library/`, `Temp/`, `Logs/`, `UserSettings/` and build outputs are ignored) and a
Unity `.gitattributes` for text/YAML handling. Git LFS is **not** used, so no extra
tooling is required to clone the project.

## License

No license has been specified yet.
