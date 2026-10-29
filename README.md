# Physical Attribute Assignment for Reconstructed Indoor Scenes

Research progress on mesh-based physical attribute assignment: the CA-1M coffee-table VoMP / Isaac Lab pilot and earlier AI2-THOR FloorPlan209 reconstruction and contact tests.

## Website

https://normanisfine.github.io/dl_project_dashboard/

The report includes the original AI2-THOR source video, matched ground-truth/reconstruction views, a reconstruction fly-through, an Isaac screenshot, and laptop push trials with and without physics. It distinguishes simulator reference values, estimated furniture properties, and manually assigned laptop assumptions.

Static HTML and selected media are in the repository root and `assets/`. The existing GitHub Actions workflow publishes pushes to `main`. No build step or dependencies are required. `experiments.html` redirects to the current experiment.

## Latest update — 28 October 2026

The coffee-table section reports five dynamic plates and a tissue-box assembly on a fixed reconstructed table. It includes rest and force-pulse videos, predicted material fields, density comparisons, and evidence from 11 trials. Videos replay actual Isaac Lab trajectories in Blender. Baselines also pass; numerical stability does not establish accurate physical parameters. The implausible tissue-box mass and assumed friction are explicitly documented.

See `assets/coffee-evidence.json` for results, protocol, diagnostic history, and validation. No datasets, model weights, credentials, or local runtime files are included.
