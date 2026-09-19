# Averagium Projects

> Paying down the feudal debt of your backlog, one ticket at a time.

Averagium Projects is a native macOS app for tracking features, tasks, and bugs across all your repositories — without inventing a second source of truth. Everything it manages is plain Markdown, stored right inside each project's own repo, alongside the code it describes.

**Current version:** 1.0.21 · [Full changelog](changelog.md) · [Download the latest release](https://github.com/jeremieb/averagium-releases/releases/latest)

This repository hosts only the update feed and release notes for Averagium Projects — the app's source code is private. If you're looking for a place to download the app, check for update notes, or report something you noticed after an update, you're in the right place.

## What it does

Every repository tends to accumulate its own pile of `.md` files describing what still needs doing. Averagium Projects gives that pile some structure:

- **Add your repositories as projects** and let Averagium track a dedicated `averagium/` folder inside each one.
- **Organize features, tasks, and bugs** with progress, priority, dates, and documentation — all backed by readable Markdown, not a hidden database.
- **See everything at once** in an Overview grid or a Gantt-style Timeline, across every connected project, instead of digging through folders one repo at a time.
- **Stay in sync with Git**: review a diff of what changed, then commit and push your Averagium updates directly from the app.
- **Track bugs** alongside features and tasks, with their own dedicated workspace view.
- **Check in from the menu bar and desktop**, with widgets for today's tasks and top-priority bugs.
- **Go live**, with an experimental Stream Overlay that shows tracked progress bars directly in OBS.

## Installing

1. Download the latest `.zip` from [Releases](https://github.com/jeremieb/averagium-releases/releases/latest).
2. Unzip it and move **Averagium Projects.app** to your Applications folder.
3. Launch it — macOS 27 or later is required.

## Staying up to date

Averagium Projects checks for updates automatically using [Sparkle](https://sparkle-project.org). You can choose how often it checks (launch-time, hourly, daily, weekly, or monthly) and whether it notifies you before installing or updates fully automatically, from **Settings → Updates**.

Every update ships with its own release notes, listed in the [changelog](changelog.md) and linked from each entry in the [appcast](appcast.xml).

## Free tier and licensing

Averagium Projects is free to use with one project, two features per project, and three tasks per feature. A license removes those limits.

[Get a license on Gumroad →](https://jeremieberduck.gumroad.com/l/averagium)

## Source code

The app's source lives in a private repository. This repo exists purely to serve release binaries, the Sparkle appcast, and per-version release notes via GitHub Pages — it contains no source code.

## Feedback

Found a bug after updating, or have a suggestion? Open an issue on this repository.
