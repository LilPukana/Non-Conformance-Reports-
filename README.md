# Defect Tracker

Field QA defect tracker for New Energy solar sites (STS1–STS4). Tracks punch-list
and rework items by table and pile, with a Defect & Repair Report per item
(before/after photos, DFT, QA/QC acceptance) and PDF export.

## Opening the app

Once GitHub Pages is switched on, the app runs at:

`https://<your-github-username>.github.io/<repo-name>/`

Everything is in one file, `index.html`. There is no build step.

## Data and Cloud Sync

- No data or API keys are stored in this repository.
- Each browser keeps its own local copy of the data.
- Team data syncs through JSONBin.io. In the app, open **Cloud Sync**, paste the
  team's API key and the site bin IDs, then click **Load from Cloud**.
- Keep the API key out of this repository. Share it with the team privately.

## Updating the app

Replace `index.html` with the new version and commit. GitHub Pages republishes
within a minute or two. Local data and Cloud Sync settings carry over, because
they're tied to the web address, not the file.
