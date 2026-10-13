# Pocket Kanban

A small three-column task board built with plain HTML, CSS, and JavaScript. No framework, dependencies, account, or build step.

## 使用方法 / Getting started

Open `index.html` in a modern browser. Add a task, change its status with the dropdown, or delete it. Three sample tasks are included on a fresh workspace.

直接双击 `index.html`，即可添加任务、切换“待办 / 进行中 / 已完成”状态和删除任务。

## Features

- Three task stages: To do, In progress, and Done.
- Responsive dark workspace with keyboard-accessible controls.
- Browser-local saving with `localStorage` and visible storage error messages.
- Task titles are inserted as text, not interpreted as HTML.

## Customize

Edit the CSS variables for your own theme. Edit the initial `tasks` array to replace the demonstration tasks. The entire application lives in `index.html`.

## Storage limits

Tasks stay in this browser; they are not synchronized or backed up. Clearing browser data can remove them. Persistence for files opened with `file://` depends on the browser. For consistent storage, serve the file from a static web host such as GitHub Pages. If storage is unavailable, the board still works in the current tab and displays a warning.

This is a starter template; no automated tests or dependency installation were performed.
