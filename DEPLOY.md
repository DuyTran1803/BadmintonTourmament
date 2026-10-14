# Deploy the Badminton Tournament app on GitHub Pages

The deploy-ready file is `index.html`. It is fully self-contained and works offline after it has loaded once or when opened directly from your computer.

## Create and push a new repository

1. On GitHub, create an empty public repository named `badminton-tournament`. Do not add a README, `.gitignore`, or licence during creation.
2. Open Terminal in the folder containing `index.html` and run:

```bash
git init
git add index.html
git commit -m "Add badminton tournament app"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/badminton-tournament.git
git push -u origin main
```

Replace `YOUR_USERNAME` with your GitHub username.

## Enable GitHub Pages

1. Open the repository on GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select the `main` branch and the `/ (root)` folder, then select **Save**.

The app will appear at:

`https://YOUR_USERNAME.github.io/badminton-tournament/`

GitHub may take a few minutes to publish the first deployment.

## Update it later

Replace `index.html`, then run:

```bash
git add index.html
git commit -m "Update tournament app"
git push
```

No custom-domain setup is included; the free `github.io` address needs no domain purchase.
