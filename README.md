# vo - visual organizer

A tkinter-based organizer of notes of thoughts.

Usage:
  python vo [VOFILE]

## Using vo

Run `python vo` to start a new board. It uses `VizOrg.yaml` as the save
filename. To open a board, pass its YAML file as an argument:

```sh
python vo vos/trainingmaterials.yaml
```

If the specified file exists, its boxes are loaded. If it does not exist, vo
starts a new board that can be saved to that path. Use **New Box** or `Ctrl-n`
to add a box, then click its title or text to edit it. Drag a box by its
border, and right-click its border to cycle through background colors. Select
a URL in a box and right-click to open it in a browser.

Save with **Save** or `Ctrl-s`. When closing, vo asks whether to save if there
are unsaved changes. Boards are stored as YAML files.

## Keyboard shortcuts

| Shortcut               | Action                                      |
| ---------------------- | ------------------------------------------- |
| `Ctrl-h`               | Show help                                   |
| `Ctrl-s              ` | Save the board                              |
| `Ctrl-n`               | Create a box                                |
| `Ctrl-f`               | Focus text search; press Enter to search    |
| `Ctrl-+` / `Ctrl--`    | Zoom in / out                               |
| `Ctrl-0`               | Reset zoom                                  |
| `Esc`                  | Stop editing                                |
| `Alt-Left`/`Alt-Right` | Decrease / increase the selected box width  |
| `Alt-Up`/`Alt-Down`    | Decrease / increase the selected box height |
| `Ctrl-Arrow`           | Move all boxes                              |
| `Ctrl-Home`            | Reset the position of all boxes             |
| Arrow keys             | Move the selected box if not editing        |
| `Shift-Arrow`          | Move the selected box in larger steps       |




