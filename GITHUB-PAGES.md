# Deploy to GitHub Pages

1. Create a new GitHub repository.
2. Upload the **contents** of this folder to the repository root.
3. Commit the files to your main branch.
4. Open **Settings → Pages** in the repository.
5. Under **Build and deployment**, choose **Deploy from a branch**.
6. Select the `main` branch and `/ (root)` folder, then save.
7. GitHub will publish the site using `index.html` as the entry page.

The included `.nojekyll` file keeps GitHub Pages from applying Jekyll processing to this static app.
