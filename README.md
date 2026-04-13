# Burninglog Templates

Stamp template registry for the Burninglog app, served via GitHub Pages.

## Structure

```
templates.json          # Template registry (fetched by app)
stamps/                 # SVG stamp files
  default_stamp.svg     # Default running stamp
thumbs/                 # Thumbnail images (PNG)
```

## Adding a New Template

1. Add the SVG file to `stamps/`
2. Add a thumbnail (88×88 PNG) to `thumbs/`
3. Add an entry to `templates.json`

### SVG Placeholder IDs

| ID | Field |
|----|-------|
| `bl-type` | Workout type (e.g., RUNNING) |
| `bl-distance` | Distance (e.g., 5.23 km) |
| `bl-pace` | Pace (e.g., 5'30"/km) |
| `bl-duration` | Duration (e.g., 28:45) |
| `bl-heartRate` | Heart rate (e.g., ♥ 142 bpm) |
| `bl-calories` | Calories (e.g., 🔥 312 kcal) |
| `bl-date` | Date (e.g., 2026.04.13) |
