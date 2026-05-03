# sort.study — Sorting Algorithms Visualiser

Interactive sorting algorithm visualiser for **OCR A-Level Computer Science H446**.

**Live demo:** `https://<your-username>.github.io/<repo-name>/`

## Algorithms covered

| Algorithm | Best | Average | Worst | Space |
|-----------|------|---------|-------|-------|
| Bubble Sort | O(n) | O(n²) | O(n²) | O(1) |
| Insertion Sort | O(n) | O(n²) | O(n²) | O(1) |
| Merge Sort | O(n log n) | O(n log n) | O(n log n) | O(n) |
| Quick Sort | O(n log n) | O(n log n) | O(n²) | O(log n) |

## Features

- **Animated visualiser** — step through every comparison and swap
- **Speed control** — from slow (study each step) to fast (watch the sort complete)
- **Three code views** — OCR pseudocode, JavaScript, and Python for each algorithm
- **Colour coded** — yellow = comparing, red = swapping, green = sorted, orange = pivot
- **Array size control** — 10, 20, 30, or 40 elements
- **Statistics** — live comparison and swap counters
- **Master comparison table** — all algorithms at a glance
- **Works offline** — single HTML file, no build step, no dependencies

## Running locally

Just open `index.html` in any modern browser. No server required.

```bash
# Or serve locally:
npx serve .
# Then visit http://localhost:3000
```

## Deploying to GitHub Pages

1. Push this repository to GitHub
2. Go to **Settings → Pages**
3. Set source to **GitHub Actions**
4. Push to `main` — the workflow in `.github/workflows/deploy.yml` handles the rest

Your site will be live at `https://<username>.github.io/<repo-name>/`

## Specification reference

All content aligns to **OCR H446 Section 2.3.1(f) — Standard Algorithms**.

Pseudocode notation follows the [OCR Pseudocode Guide for Teachers (H446)](https://www.ocr.org.uk).

## File structure

```
index.html                    ← The entire application (single file)
README.md                     ← This file
.github/
  workflows/
    deploy.yml                ← GitHub Pages deployment workflow
```
