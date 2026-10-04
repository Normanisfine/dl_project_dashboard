# dl_project_dashboard

SyncGeoMemory research dashboard: four reconstruction problems, representative papers, the chosen sparse-view dynamic reconstruction with imagination direction, and recorded experiment results.

The main priorities are less training and greater efficiency.

## Website

Expected GitHub Pages URL once deployed: https://normanisfine.github.io/dl_project_dashboard/

- `index.html`: research overview and chosen direction.
- `experiments.html`: recorded results, reconstruction previews, and next gates.
- `styles.css`: shared layout and typography.
- `outputs/`: selected previews and sanitized experiment summaries.

## Publish

Push this repository to `main`, then open the repository's **Settings → Pages** and select **GitHub Actions** as the source. The included workflow deploys the static dashboard on pushes to `main` and can also be run manually from the Actions tab.

No build or dependency installation is required. Open `index.html` in a browser to preview locally. Internal datasets, checkpoints, and credentials are excluded.

## Update

Edit the HTML files or refresh selected experiment snapshots, then commit and push. GitHub Pages publishes the new snapshot; the dashboard does not start experiments or scan the source machine.
