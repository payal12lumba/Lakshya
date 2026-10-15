# Lakshya — placement prep tracker

Plan: **16 Oct – 15 Nov 2026**. All syllabus areas finish by **4 Nov**; final prep runs after that.

## How the plan works

| Track | Order |
|---|---|
| **Conceptual** | One area at a time: Classical ML → Model evaluation → Deep learning → Computer vision → NLP → GenAI → Probability & stats → Linear algebra → Case studies (16 Oct – 4 Nov) |
| **Coding** | Python → NumPy & Pandas → SQL → DSA → CS basics, in parallel with the conceptual track. ML / DL coding is scheduled only after its matching theory. |
| **Projects** | One project in week 1, two a week from week 2 |
| **Final prep** | Puzzles, aptitude, mock OAs, resume & project sheets, HR and mock interviews (from 5 Nov) |

### Projects by week

| Week | Dates | Projects |
|---|---|---|
| 1 | 16–22 Oct | Fraud detection |
| 2 | 23–29 Oct | CIFAR-10 CNN → ResNet-18 · Movie recommender web app (TuteDude M13, deployed on Render) |
| 3 | 30 Oct – 5 Nov | RAG teaching assistant (CodeWithHarry §23) · LSTM next-word app (TuteDude M22) |
| 4 | 6–12 Nov | U-Net segmentation · PDF Q&A chatbot with memory (TuteDude M33–34, deployed on HF Spaces) |
| 5 | 13–15 Nov | ViT vs CNN on MedMNIST · SQL agent app (TuteDude M36) |

## Tabs

| Tab | What it shows |
|---|---|
| **Conceptual** | Day-wise theory plan, with a week summary (areas, projects, days left in the syllabus) |
| **Coding** | Day-wise coding plan: Python / SQL / DSA, ML / DL coding and projects |
| **Areas** | The 14 syllabus areas with their topics, mapped lectures and extra resources |
| **Courses** | Every course, every lecture numbered with its own tick and link |
| **Extra** | Resources outside your courses (NeetCode 150, SQL 50, papers…) grouped by area |
| **Insights** | Roadmap with dates for every phase, progress, pace, and backup / restore |

Ticks you made in the earlier version carry over: topic IDs are unchanged.

## Build the APK (GitHub)

1. In your existing `lakshya` repository, replace these files with the ones here:
   - `www/index.html` (the app)
   - `index.html` (same file, for browser preview)
   - `README.md`, `package.json`, `capacitor.config.json`
   - `.github/workflows/build-apk.yml`
2. **Keep `lakshya-debug.keystore`** in the repository root. It is not in this ZIP. It is the fixed signing key that lets the new APK install over the old one and keep your progress.
3. Commit. Open **Actions → Build Lakshya APK** (it runs on every push, or press *Run workflow*).
4. When it's green, open the run → **Artifacts** → download **Lakshya-APK** → unzip → install `Lakshya.apk`.

Before installing, open the current app → **Insights → Backup progress → Copy backup**, and keep the text somewhere safe.
