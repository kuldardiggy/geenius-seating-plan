# Seatplan

A static monthly office seating planner. It automatically generates a plan based on the configured attendance rules, supports manual desk and team adjustments, and includes a person view showing each person's office dates and desk assignments.

## Run locally

Open `index.html` directly in a browser. No build process, server, database, or dependencies are required.

## Publish with GitHub Pages

1. Create a new GitHub repository.
2. Upload all files from this folder to the repository root.
3. Open **Settings → Pages** in the repository.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select the `main` branch and the `/ (root)` folder, then click **Save**.
6. GitHub will show the public URL after deployment finishes.

## Data storage

This prototype stores changes in the browser's `localStorage`. Data is therefore specific to each browser and device. It does not synchronize changes between users.

For shared live editing, authentication, or centralized data storage, the app will need a backend or a hosted database service.

## Files

- `index.html` — complete application
- `.nojekyll` — tells GitHub Pages to serve the files directly
- `.gitignore` — excludes common local system files

