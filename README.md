# Spacebar

A calm, keyboard-first work planner for product managers. One HTML file. No server, no account, no build step.

## Use it

Download `index.html` and open it in your browser. It starts with a sample workspace (a rider-app PM at Uber); click **Start fresh** when you are ready for your own.

Everything saves in your browser as you go.

## How it is organised

- **Board.** Initiatives sit in stages: Shape, Build, Land. Star up to 5 as priority; they stay expanded, the rest fold to one line. Each initiative has dates, a Slack link and its next steps.
- **Planner.** A side sheet with three cards:
  - **Daily**: your short list for today, capped at 10. When it is full, a task joins only by swapping another out.
  - **Weekly**: up to 3 objectives for the cycle, each with a status and the tasks that move it.
  - **Scratchpad**: quick notes.
- **Modes.** Every task is Think, Do or Chase, so you can pick work by the energy you have. Daily groups tasks by mode.

Stages, modes, limits and the cycle length are all editable in Settings.

## Keyboard

| Key | Action |
|---|---|
| Space | Cycle the Planner: closed, Daily, Weekly, Scratchpad |
| N | Open the Scratchpad |
| Arrows or j k h l | Move between cards |
| Enter | Edit a task, or expand an initiative or objective |
| A | Add a next step |
| D | Add to or remove from Daily |
| X | Complete |
| 1, 2, 3 | Set mode |
| O | Link to an objective |
| . | More actions |
| / | Search |
| ? | All shortcuts |

## Editing with Claude

In Settings, under **Data and Claude**, choose **Create data file**. Spacebar writes every change to that JSON file and reloads within about 2 seconds when the file changes, so Claude (or any script) can read and edit your workspace by editing the file. The file explains its own format. This needs a Chromium browser (Chrome, Edge, Arc). In any browser you can also use **Copy JSON** and **Paste JSON** to hand your workspace to Claude in a chat and load back what it returns.

## Credits

Drag and drop by [SortableJS](https://github.com/SortableJS/Sortable) (MIT), inlined in the file.
