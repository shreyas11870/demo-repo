# Little List

Little List is a small, browser-based to-do list for keeping track of one thing at a time. It is built with plain HTML, CSS, and JavaScript, with no framework, dependencies, or build step.

## Features

- Add tasks with up to 200 characters.
- Mark tasks as complete or active.
- Filter the list to show all tasks, tasks to do, or completed tasks.
- Delete individual tasks or clear all completed tasks.
- See how many tasks remain.
- Keep tasks between visits with browser `localStorage`.
- Use a responsive layout with keyboard focus styles and reduced-motion support.

## Run locally

Open `index.html` in a modern web browser. To serve it over HTTP instead, run a static file server from the project directory, for example:

```sh
python3 -m http.server 8000
```

Then visit <http://localhost:8000>.

## Data and privacy

Tasks are saved in the current browser's local storage under the key `little-list-tasks`. They are not sent to a server. Clearing the browser's site data removes the saved list.

## Project files

- `index.html` — the complete application, including styles and behavior.
- `README.md` — project overview and usage instructions.
