# Deploying to GitHub Pages

1. Install the `gh-pages` package:

   ```sh
   npm install --save-dev gh-pages
   ```

2. Add the following scripts to your `package.json`:

   ```json
   "scripts": {
     "predeploy": "npm run build",
     "deploy": "gh-pages -d dist"
   }
   ```

3. Ensure your `homepage` field in `package.json` is set to:

   ```json
   "homepage": "https://Ronniegrg.git.io/countdown-timer"
   ```

4. Deploy your project by running:

   ```sh
   npm run deploy
   ```

5. Your project should now be live at `https://Ronniegrg.git.io/countdown-timer`.

```

Replace `Ronniegrg` and `countdown-timer` with your GitHub username and repository name, respectively.
```
