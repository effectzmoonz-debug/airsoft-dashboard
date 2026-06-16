# Airsoft Dashboard — Android APK Builder

Automatically builds an Android APK using GitHub Actions (free, no Android Studio needed).

---

## How to get your APK (5 steps)

### Step 1 — Create a GitHub account
Go to https://github.com and sign up (free).

### Step 2 — Create a new repository
1. Click the **+** button → **New repository**
2. Name it: `airsoft-dashboard`
3. Set to **Public** (required for free Actions)
4. Click **Create repository**

### Step 3 — Upload these files
Drag and drop ALL files from this folder into the GitHub repository page.
Make sure the folder structure matches exactly:
```
airsoft-dashboard/
├── .github/
│   └── workflows/
│       └── build-apk.yml
├── www/
│   └── index.html
├── capacitor.config.json
├── package.json
└── .gitignore
```

### Step 4 — Wait for the build (~5 minutes)
1. Click the **Actions** tab in your repository
2. You'll see "Build Airsoft Dashboard APK" running
3. Wait for the green checkmark ✅

### Step 5 — Download your APK
1. Click on the completed workflow run
2. Scroll down to **Artifacts**
3. Click **airsoft-dashboard-debug** to download the APK
4. Transfer to your Android phone and install it

---

## Installing on Android
1. On your phone: **Settings → Security → Allow unknown sources** (or "Install unknown apps")
2. Open the downloaded `.apk` file
3. Tap **Install**
4. Find **Airsoft Dashboard** in your app drawer

---

## App features
- Register players with custom numbers
- Record gun tests (AEG/GBB/HPA/Spring) with FPS and BB weight
- Add penalties with offense tracking
- Score tracking (starts at 100, deducts on penalty)
- Search players by name, number, or phone
- All data saved locally on the device
