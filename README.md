# Style Lab – Android app (Capacitor)

A learning app with 19 switchable UI themes (claymorphism, glassmorphism, neumorphism and more).
The whole app lives in `www/index.html`.

## Build the APK (no Android Studio needed)
1. Push this repo to GitHub (see commands below) or upload the files in the web UI.
2. Open the **Actions** tab, then **Build Android APK**. It runs on every push to `main`
   (or click **Run workflow**) and takes about 5 minutes.
3. Open the finished run, download **style-lab-apk** from Artifacts, unzip it, and install `app-debug.apk`.

## Git commands
```
git init
git add .
git commit -m "Style Lab"
git branch -M main
git remote add origin https://github.com/YOUR_USERNAME/style-lab-android.git
git push -u origin main
```

## Change the app
Edit `www/index.html`, commit and push. A new APK is built automatically.
To add a theme, copy a `[data-theme="..."]` block in the CSS and add one line to the `THEMES` list.
