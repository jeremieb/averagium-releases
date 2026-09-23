# 1.0.23

****

**Added**
- Git branch switching. A new branch menu next to the Git menu shows the project's current branch, lists local and remote branches with their ahead/behind status, and lets you switch safely. Switching is blocked when it could overwrite unrelated changes, and Averagium content can be stashed first with an explicit confirmation.
- View README and Edit README actions in the project menu, opening the README in the existing Markdown viewer and editor.
- Project ordering in Overview. Choose between manual and alphabetical order, and drag projects into place.
- Timeline navigation. Click a project or feature in Timeline to open its project detail; clicking a feature also expands it.
- Collapsible task details in the project view, so long task descriptions can be folded away.

**Improved**
- Commit & Push now checks the current branch against its upstream first and stops with a clear explanation if the remote is ahead or has diverged.
- Sidebar Git change badges update faster and do less work in the background.

**Removed**
- The Share project button from the project toolbar.

****
