## 1.0.22 — 2026-09-21

# 1.0.22

****

**Added**
- iCloud sync for your project library. The new Sync settings show the current storage mode, let you check your iCloud account, and surface sync activity or errors.
- Project transfer tools in Settings → Sync. Export your current projects to a private JSON file, then review and import them on another Mac without overwriting projects already there.
- Collapsible project rows in Timeline. Collapse a project to focus on the big picture while still seeing markers for upcoming due dates.

**Improved**
- Stream Overlay now shows each item’s project name and project color, making items from different projects easier to distinguish.
- The Stream Overlay picker now filters by task name and only offers unfinished features, tasks, and bugs.
- Selected sidebar change-count badges now use the standard selected-row color for better readability.

**Fixed**
- Stream Overlay selections now remain distinct when projects or items share the same name, preventing the wrong item from being selected or updated.

****

## 1.0.21 — 2026-09-19

# 1.0.21

****

**Fixed**
- Sidebar folders no longer force themselves open on launch; they respect their collapsed/expanded state again.

****


## 1.0.20 — 2026-09-19

# 1.0.20

****

**Added**
- Sidebar badge showing how many files have uncommitted changes for a project, and for a collapsed folder's projects combined. The badge tints to the project's or folder's own color and updates automatically as you edit.

****


## 1.0.19 — 2026-09-19

# 1.0.19

****

**Added**
- Create documentation directly from Project, Feature, Task, and Bug menus. New files are saved under `averagium/doc` and automatically linked to the selected item.

**Improved**
- Markdown viewer and editor paths can now be copied directly from their headers.

**Fixed**
- Widgets now refresh their project data after an app update, preventing stale tasks or bugs from being displayed. If a refresh is needed, the widget clearly asks you to open Averagium Projects.

****

## 1.0.18 — 2026-09-18

# 1.0.18

****

**Added**
- Customizable folder icons: pick from a large curated set of SF Symbols in a new icon picker popover, or enter any custom SF Symbol name.

**Improved**
- Sidebar folder and tag icons now keep their assigned color, and switch to the standard selected-row tint only while selected.
- The color picker row in Add/Edit forms is now vertically aligned with its label, matching the rest of the form layout.

****

## 1.0.17 — 2026-09-17

# 1.0.17

****

**Improved**
- About is now its own window, opened from the app menu, instead of living inside Settings.
- Copying a feature or archived-feature path now copies its full path on disk, instead of the truncated relative path shown in the UI.

****

## 1.0.16 — 2026-09-17

# 1.0.16

****

**Improved**
- The generated Stream Overlay HTML is now responsive: fluid typography, spacing, and a narrow-width breakpoint adapt it to any OBS browser source size.
- The overlay configurator badges selected items that can no longer be found after re-resolving them on open.
- Settings window is now resizable.

**Fixed**
- Stream Overlay now updates live: progress changes to tracked features, tasks, and bugs are picked up automatically and pushed to the overlay and to iCloud sync.
- A paired streaming Mac now regenerates its overlay file as soon as the synced payload arrives, instead of only at launch.
- Disabling the Stream Overlay removes the stale overlay file.

****

## 1.0.15 — 2026-09-17

# 1.0.15

****

**Added**
- Stream Overlay (Experimental): show up to 5 tracked features, tasks, or bugs, with live progress bars, directly in OBS.
- New "Experimental" tab in Settings to enable the overlay and open its configurator.
- Overlay configurator window: pick, reorder, and remove up to 5 items across all your projects, with a live preview.
- The overlay is a self-contained HTML file you add to OBS as a local browser source; it refreshes itself every minute and updates automatically as your items progress.
- Optional iCloud sync: a second Mac on the same iCloud account can generate the overlay from synced snapshots, without access to your project folders.
- The overlay file is written to your Documents folder (or a folder you choose), with "Reveal in Finder" and "Copy OBS Path" actions.

**Notes**
- Stream Overlay is experimental: it may change or be removed in future updates.

****

## 1.0.14 — 2026-09-17

# 1.0.14

****

**Added**
- Git Review can now stash, reapply, fetch, and pull a project's Averagium changes.

**Improved**
- Feature, task, and bug rows use the available window width for easier reading.
- Drag a feature, task, or bug below the final row to move it to the end of its list.

**Fixed**
- Completed bugs no longer appear in the Bugs widget.

****

## 1.0.13 — 2026-09-17

# 1.0.12

****

**Fixed**
- Corrupted widget package

****

## 1.0.12 — 2026-09-16

# 1.0.12

****

**Improved**
- UI Adjustments

****

## 1.0.11 — 2026-09-16

# 1.0.11

**Added**
- Full bug actions from the workspace Bugs view: edit bugs, mark them complete, attach, view, or edit documentation, edit the underlying Markdown, and delete bugs.

**Improved**
- Project tiles now show the number of unresolved bugs alongside outstanding features and tasks.
- The workspace Bugs view now opens Markdown and documentation in a dedicated detail pane.

**Fixed**
-

**Notes**
-

## 1.0.10 — 2026-09-16

# 1.0.10

**Added**
- Dedicated bug tracking for each project, with progress, priority, documentation, editing, deletion, and drag-to-reorder support.
- A Bugs workspace view that gathers bugs from all your projects and groups them by project.
- A Bugs widget for small, medium, and large sizes, showing your highest-priority bugs across projects.

**Improved**
- Task widgets now keep features and their tasks together when sorting upcoming work.
- Widget data refreshes when project content, access, or license status changes.
- Commit & Push now includes bug files and their attached documentation.

**Fixed**
- 

**Notes**
-

## 1.0.9 — 2026-09-16

# 1.0.8

**Added**
- 

**Improved**
- 

**Fixed**
- 

**Notes**
-

## 1.0.8 — 2026-09-16

# 1.0.8

**Added**
- Feature filenames are now generated automatically from their titles, using a clean, portable kebab-case format.
- The free version now supports one project, two features per project, and three tasks per feature. Activate a license to remove these limits.

**Improved**
- Creating a feature now uses a simple filename field instead of requiring a Markdown path.

**Fixed**
- Commit & Push now includes deletions of Averagium feature, archive, and documentation files.

**Notes**
-

## 1.0.7 — 2026-09-16

# 1.0.7

**Added**
- An Updates settings tab with automatic update checks, launch-time checks, and hourly, daily, weekly, or monthly check frequencies.
- A choice between being notified before an update or having updates download and install automatically when possible.

**Improved**
- Updates now default to notifying you before downloading or installing anything.

**Fixed**
-

**Notes**
-

## 1.0.6 — 2026-09-16

# 1.0.6

**Added**
-

**Improved**
-

**Fixed**
- Marking a feature as complete now also marks all of its tasks as 100%, keeping feature progress from being reset by later task edits.

**Notes**
-

## 1.0.5 — 2026-09-16

# 1.0.5

**Added**
-

**Improved**
-

**Fixed**
- Marking a feature as complete now also marks all of its tasks as 100%, keeping feature progress from being reset by later task edits.

**Notes**
-

## 1.0.4 — 2026-09-16

# 1.0.4

**Added**
- Sparkle-based auto-update pipeline (this release is a dry-run test of that pipeline)

**Improved**
-

**Fixed**
-
- auto update fix

**Notes**



## 1.0.3 — 2026-09-16

# 1.0.3

**Added**
- Sparkle-based auto-update pipeline (this release is a dry-run test of that pipeline)

**Improved**
-

**Fixed**
-

**Notes**
- This release notes file exists to validate the release CI pipeline end-to-end.


## 1.0.2 — 2026-09-16

# 1.0.2

**Added**
- Sparkle-based auto-update pipeline (this release is a dry-run test of that pipeline)

**Improved**
-

**Fixed**
-

**Notes**
- This release notes file exists to validate the release CI pipeline end-to-end.

## 1.0.2 — 2026-09-16

# 1.0.2

**Added**
- Sparkle-based auto-update pipeline (this release is a dry-run test of that pipeline)

**Improved**
-

**Fixed**
-

**Notes**
- This release notes file exists to validate the release CI pipeline end-to-end.

# Changelog

All notable changes to Averagium are listed here, most recent first. This file is generated by CI — do not hand-edit.
