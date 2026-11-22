# Upload to GitHub

1. **Before making this public:** get agreement from all four group members and review both PDFs for any details you do not want public. Student IDs were removed from the bundled PDFs.
2. Sign in to https://github.com/new and create a **public** repository named `MeridianCare-Cloud-Migration`. Do **not** initialize it with a README, license or .gitignore.
3. Unzip this package locally, open a terminal in the `MeridianCare-Cloud-Migration` folder and run:

```bash
git init
git add .
git commit -m "Add MeridianCare cloud migration case study"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/MeridianCare-Cloud-Migration.git
git push -u origin main
```

Replace `YOUR_USERNAME` with your GitHub username. If Git prompts for credentials, use the supported GitHub authentication flow (not your account password).

**Alternative:** Create the repository with a README unchecked, choose **uploading an existing file**, then drag the contents of the unzipped folder into GitHub. Verify the folders and diagram links render correctly.

After upload, open the repository and confirm the README, diagrams and PDF links work.
