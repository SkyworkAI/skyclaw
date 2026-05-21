# SkyClaw-v1.0 Release Page

Static GitHub Pages site for the SkyClaw-v1.0 model release.

## Local Preview

Run a local static server from this directory:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000/
```

## Main Files

- `index.html` - main release page
- `benchmark_style_chart_1600.png` - optimized benchmark chart used on the page
- `*_preview.png` - rendered preview images used by Showcase cards
- `benchmark_style_chart.png` - original large benchmark chart source

## Showcase Preview Images

The Showcase cards use local preview images so the page loads faster and does not embed remote demos directly.

Current preview assets:

- `bouncing_balls_preview.png`
- `bingo_blast_preview.png`
- `china_nev_report_preview.png`
- `financial_terminal_preview.png`
- `flight_travel_preview.png`
- `instagram_preview.png`
- `mag7_report_preview.png`
- `super_mario_preview.png`
- `xiaohongshu_preview.png`

Regenerate these screenshots when the linked demo pages change.

## Deployment

This is a static site. Deploy by pushing the repository to the branch configured for GitHub Pages.
