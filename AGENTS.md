# Agent Instructions

## Issue Tracking

This project uses **bd (beads)** for issue tracking.
Run `bd prime` for workflow context.

**Quick reference:**
- `bd ready` - Find unblocked work
- `bd create "Title" --type task --priority 2` - Create issue
- `bd close <id>` - Complete work
- `bd sync` - Sync with git (run at session end)

For full workflow details: `bd prime`

## Focal Point: The Ralph Submodule
This repository is a wrapper project for the 'ralph' submodule.  The 'ralph' submodule is meant to be included as a submodule in many other projects.  As such, we need to keep it clean.  So, this wrapper project acts as a place to keep the .beads, .claude and .codex metadata useful for workin on 'ralph'.

As such, the VAST majority of the work you will do will be in the 'ralph' submodule.  However, as the beads metada is stored in this wrapper project, you'll usually need to commit and push the ralph submodule first, then this wrapper module. 




