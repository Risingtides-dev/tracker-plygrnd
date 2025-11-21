# PLYGRND Sound Tracker

GitHub Pages deployment for PLYGRND sound usage analytics.

Generated: Fri Nov 21 08:04:05 EST 2025
Source: plgrnd_latest

## Setup Instructions

1. Create a new repository on GitHub named: **Tracker-Playground**
   - Go to: https://github.com/new
   - Repository name: Tracker-Playground
   - Make it Public (required for free GitHub Pages)
   - Do NOT initialize with README, .gitignore, or license

2. Add the remote and push:
   ```bash
   git remote add origin https://github.com/Risingtides-dev/Tracker-Playground.git
   git add .
   git commit -m "Initial PLYGRND tracker deployment"
   git push -u origin gh-pages
   ```

3. Enable GitHub Pages:
   - Go to: https://github.com/Risingtides-dev/Tracker-Playground/settings/pages
   - Under 'Source', select:
     - Branch: gh-pages
     - Folder: / (root)
   - Click Save

4. Your report will be live at:
   https://risingtides-dev.github.io/Tracker-Playground/

## Updating the Report

To update the report with new data:

```bash
cd warnertracker
./deploy_plygrnd_github_pages.sh campaigns/plgrnd/plgrnd_latest.csv
```

