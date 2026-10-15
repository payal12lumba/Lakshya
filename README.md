# Lakshya — placement prep tracker

One app, six tabs:

| Tab | What it shows |
|---|---|
| **Conceptual** | Your date-wise theory plan (unchanged) |
| **Coding** | Your date-wise coding plan (unchanged) |
| **Areas** | The 14 syllabus areas. Each area has its Must / Important / Can-leave topics, every lecture from your courses mapped to that area, and that area's extra resources |
| **Courses** | Every course, every lecture numbered with its own tick and link. Skipped lectures say where they're covered |
| **Extra** | Resources outside your courses (NeetCode 150, LeetCode SQL 50, CS229, StatQuest, Stat 110, FPP3, papers, aptitude sites…) grouped by area |
| **Insights** | Progress for the date plan, plus checklist progress by course and a backup/restore box |

A tick is the same everywhere: tick a lecture in **Areas** and it's ticked in **Courses** too.

## Build the APK (GitHub)

1. Create a new GitHub repository (e.g. `lakshya`).
2. Upload **everything in this ZIP** (keep the folder structure — including the hidden `.github` folder). On the website: *Add file → Upload files*, drag the unzipped folder contents in, commit.
3. Open the **Actions** tab → **Build Lakshya APK**. It runs automatically on every push (or press *Run workflow*).
4. When it's green, open the run → **Artifacts** → download **Lakshya-APK** → unzip → install `Lakshya.apk` on your phone.

## Updating later
Replace `www/index.html` and commit. The build uses the fixed key `lakshya-debug.keystore`, so new APKs install over the old one and keep your progress. Don't delete that file.

## Moving from your old Lakshya APK
This build's package name is `com.lakshya.prep`. If your old APK used a different package name or key, Android installs this as a separate app and your old ticks stay in the old app. To bring them over: in the old app open **Insights → Backup progress** (if it has it) — otherwise just carry on; the new Areas/Courses/Extra ticks start fresh anyway.
From now on, use **Insights → Backup progress → Copy backup** before any reinstall.
