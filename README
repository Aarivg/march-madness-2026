# 2026 March Madness Analytics Dashboard

A data-driven bracket analysis system built with Python, Google Sheets, and Chart.js.

## Live Dashboard
**[View the interactive dashboard here](https://aarivg.github.io/march-madness-2026)**

## The Problem
NCAA Tournament seeding underweights defensive efficiency and strength of schedule,
creating predictable mismatches between a team's seed and their true quality.
This project builds a model to surface those gaps.

## The Model
A Composite Performance Score (CPS) was calculated for all 68 tournament teams
using 8 weighted statistics:

| Stat | Weight | Why |
|------|--------|-----|
| SRS | 25% | Best overall quality predictor |
| SOS | 15% | Validates the record |
| Win % | 15% | Winning habit in elimination play |
| FG% | 10% | Efficient scoring wins close games |
| FT% | 10% | March games decided at the line |
| Rebounds/g | 10% | Second chances and stops |
| Steals/g | 8% | Chaos creators drive upsets |
| 3P% | 7% | Hot shooting teams go on runs |
| TOV/g | -5% | Penalty for turnovers |

## Key Findings
- **Michigan** ranks #1 overall by CPS — the model's top tournament pick
- **Louisville** (6-seed) ranks #11 by CPS — biggest underseeded team in the field
- **Kansas** (4-seed) ranks #21 — only top-4 seed the model flags as overseeded
- **South region** has the weakest average CPS (317.3) — most favorable Final Four path
- **5 upset alerts** flagged: Louisville, Vanderbilt, St. John's, Tennessee, Texas Tech

## Tools Used
- Python (pandas) — data cleaning and CPS calculation
- Google Sheets — structured model and conditional formatting
- HTML / CSS / Chart.js — interactive dashboard
- GitHub Pages — deployment

## Data Source
[Sports Reference College Basketball](https://www.sports-reference.com/cbb/) — 2025-26 season
