# My FreeCAD Models

My personal collection of my FreeCAD design files.

## Gallery

**[View the CAD Gallery →](https://josefgst.github.io/my_freecad_models/)**

The gallery is built and deployed automatically on every push to `main` via [schmiddim/freecad-action](https://github.com/schmiddim/freecad-action).


## Adding a new model

1. Drop the `.FCStd` file into the configured `freecad_dir` (currently [vibration_feeder/](vibration_feeder/)).
2. (Optional) Add a metadata YAML file to describe it (title, description, tags, images) — see the [freecad-action docs](https://github.com/schmiddim/freecad-action) for the format.
3. Push to `main` — the gallery rebuilds and redeploys automatically.
