# DUNGEON SPIKE — playable web build

This repository contains **only the exported HTML5/WebAssembly build** of the
Godot 4.3 game *DUNGEON SPIKE*. The game's source project lives in the private
repository `Dacoder637/dungeon_spikes`.

Play it at: https://dacoder637.github.io/dungeon_spikes_web/

## Rebuilding

From the source project:

```bash
mkdir -p build/web
./run_godot.sh --headless --path . --export-release "Web" build/web/index.html
```

The Web export template (`4.3.stable`) must be installed in
`~/.local/share/godot/export_templates/`.

## Credits

- Art: AI-generated for this project.
- Audio: Pixabay (free commercial use, no standalone resale). See `audio/CREDITS.txt` in the source repo.
