# Pokétwo Collection Command Center

A self-contained Pokétwo companion for caught, missing, shiny, wishlist, hunt-target, event-form, and command tracking.

## Features

- Saves progress in browser `localStorage` under `poketwo_collection_command_center_v2`.
- Migrates the older Kanto shiny checklist data from `kanto_shiny_checklist_v1` when available.
- Supports separate player profiles for personal and friend tracking.
- Loads full species data from PokéAPI, with a Kanto fallback if offline.
- Uses animated PokéAPI/Showdown sprites when available, with still-art fallbacks.
- Tracks caught, shiny, wishlist, active hunt target, notes, and custom Pokétwo event forms.
- Includes paste import for Pokétwo output and copy-ready command builders.
- Exports and imports full JSON backups.
- Runs as a static GitHub Pages site with no build step.

## Local Preview

Open `index.html` directly, or serve the folder:

```powershell
python -m http.server 4173
```

Then open `http://localhost:4173`.

## Notes

This is a personal tracker and command helper. It does not automate Discord or play Pokétwo for you.

Pokémon imagery and names belong to their respective rights holders. This tool is intended for private, non-commercial tracking.
