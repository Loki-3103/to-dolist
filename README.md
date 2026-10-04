# Personal Notes & To-Do Page


Built a minimal, keyboard-first notes and to-do page that lives in the browser. It is a single HTML file with no install, no server and no dependencies, and it works offline.
A key feature is its on-demand checkboxes: instead of forcing every line to be a task, users write their day as plain text, then select any lines and press a hotkey to turn them into checkbox items. Each page is saved like a thread in the sidebar, so past days and projects are always one click away.
Features

* Pages - every note is its own page in the sidebar; click to open, rename from the title, hover and click × to delete
* Auto-save - everything saves as you type, and pages are still there after closing the browser
* Date bar - today's date sits in the top bar and stamps every new page, synced from the internet with a local-clock fallback
* Checkboxes on demand - select lines, press a hotkey, and a checkbox appears next to each; tick with a hotkey or a click
* Rich formatting - bold, underline, highlight and strikethrough, each with its own hotkey
* Smart paste - pasting a multi-line list gives one line per row; markdown such as `- [ ] task`, `# Heading` and `- item` is converted automatically
* Themes - Forest (default), Graphite, Midnight, Ink, Dusk, Ember and one light theme, Paper

Tech Stack

* Frontend: plain HTML, CSS and JavaScript in a single file
* Data: browser localStorage, no backend or database
* Date: internet time lookup with the system clock as fallback

How to Use

1. Open the file - put `todo.html` in your project folder and double-click it
2. Write your day - type plain lines; press Enter for a new line
3. Add checkboxes - select the lines you want and press `Ctrl + Shift + L`
4. Tick tasks off - press `Ctrl + Enter` on a line, or click its box
5. Format text - select text, then use the hotkeys below
6. Organise - press `Alt + N` for a new page, `Alt + ↑ / ↓` to switch pages, `Alt + T` to change theme

Hotkeys

| Action | Hotkey |
|---|---|
| Checkbox on or off | `Ctrl + Shift + L` |
| Tick / untick | `Ctrl + Enter` |
| Bold | `Ctrl + B` |
| Underline | `Ctrl + U` |
| Highlight | `Ctrl + Shift + H` |
| Strikethrough | `Ctrl + Shift + X` |
| New page | `Alt + N` |
| Switch page | `Alt + ↑ / ↓` |
| Change theme | `Alt + T` |

Use `Cmd` instead of `Ctrl` on Mac.

