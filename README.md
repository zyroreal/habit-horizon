# Habit Horizon — deployment package

This package contains the Habit Horizon static website and a GitHub Actions workflow that deploys it to GitHub Pages whenever you push changes to `main`.

## One-time setup

1. Create/sign in to a GitHub account: https://github.com/
2. Create a **public** repository named `habit-horizon`.
3. Upload the contents of this folder to the repository root (not the ZIP itself). Make sure `index.html` and `.github/workflows/deploy-pages.yml` appear at the root and workflow path respectively.
4. Commit the files to the `main` branch.
5. In the repository, open **Settings → Pages**. Under **Build and deployment → Source**, select **GitHub Actions**.
6. Open the **Actions** tab and wait for “Deploy Habit Horizon to GitHub Pages” to finish successfully.
7. Your site URL will be `https://YOUR-GITHUB-USERNAME.github.io/habit-horizon/`.

## Future updates

Upload or edit files and commit them to `main`. The workflow automatically deploys each new commit. You can also manually start a run from **Actions → Deploy Habit Horizon to GitHub Pages → Run workflow**.

## Data and privacy note

Habit Horizon currently saves habits and check-ins in the browser's local storage. Hosting the site online does not create accounts or synchronize data across devices. Browser data can be lost if cleared, so export CSV backups regularly. Because the repository is public, anyone can view the website source; do not put private information or personal habit records into the repository.
