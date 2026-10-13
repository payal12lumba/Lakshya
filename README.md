# Lakshya

Day-wise placement prep tracker for 13 Oct – 3 Nov 2026 (Must + Important topics).
Conceptual and Coding tabs, item-by-item ticks, add-on status, three layouts, and Insights.

## Get the APK

1. In your GitHub repo, open `.github/workflows` and delete every file except `build-apk.yml`.
2. Upload the contents of this ZIP so the repo's top level shows:
   `.github/`, `resources/`, `www/`, `index.html`, `package.json`, `capacitor.config.json`, `README.md`
3. Open the **Actions** tab → "Build Lakshya APK" → **Run workflow**.
4. When it finishes, download **Lakshya-APK** from the run page, unzip, and install `Lakshya.apk`.

Every build uses the same signing key and a higher version number, so new APKs install
over the old one and keep your ticks. Don't uninstall before updating.

## Change the plan

Edit `index.html` (the `const P = {...}` block) and push. The workflow copies it into `www/`.
