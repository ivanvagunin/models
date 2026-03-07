# 3D Printing Models

This repository stores editable source files and print-ready exports for small FDM/FFF projects.

## Repository Structure

- Keep each model in its own folder.
- Store the editable source file with the model.
- Store only useful print artifacts, preferably a print-oriented STL when orientation matters.
- Avoid duplicate mesh exports when Git history already preserves older revisions.

Current layout:

- `hairdryer_fan/` - replacement hairdryer fan model and print files

## Workflow

1. Edit the model source file first.
2. Export a print-ready STL from the source.
3. Slice the oriented STL in your preferred slicer.
4. Print and validate fit before making further geometry changes.

## Tool Usage

- Use source files for dimensional changes whenever possible.
- Treat STL files as print artifacts, not the preferred editing format.
- Keep model-specific notes in a per-model `README.md` inside that model folder.

## Recommended Print Setup

- Layer height: `0.2 mm`
- Walls/perimeters: `3`
- Infill: `20-40%`
- Material: `PLA` or another suitable material
- Supports: only if required by the model geometry

Adjust settings for your printer, filament, and nozzle size.

## License

Add your preferred license if you want to publish or share the models more broadly.
