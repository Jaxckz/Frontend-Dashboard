# Frontend Dashboard

Create beautiful, responsive, single-file HTML data dashboards from raw data using AI frontend skills.

Inspired by the "show, don't tell" and "zero dependency" philosophy of [frontend-slides](https://github.com/zarazhangrui/frontend-slides), this skill allows non-designers and non-developers to instantly convert CSVs, JSON, or raw text data into stunning, interactive data dashboards.

## What This Does

Frontend Dashboard helps you create production-ready data visualizations without knowing CSS, JavaScript, or chart libraries like ECharts.

### Key Features
- **Zero Dependencies** — Generates a single HTML file with inline CSS and JS. Uses CDN for charting (ECharts/Chart.js). No npm, no build tools.
- **Visual Style Discovery** — Can't articulate design preferences? No problem. The AI presents 3 visual previews to choose from based on curated presets.
- **Data Storytelling** — Automatically extracts key KPIs and dimensions from raw data to build a logical dashboard structure.
- **Anti-AI-Slop** — Highly curated, distinctive styles that avoid generic AI aesthetics.
- **Production Quality** — Fully responsive, interactive hover effects, and accessible HTML.

## Installation

### For AI Coding Assistants (e.g., Claude Code, Cursor, Windsurf)

1. Download `SKILL.md` and `STYLE_PRESETS.md` from this repository.
2. Place them in your agent's skills or instructions directory. For example:
   - For Claude Code: `~/.claude/skills/frontend-dashboard/`
   - For custom local projects: `./skills/frontend-dashboard/`

## Usage

Simply invoke the skill and provide some data (or ask the AI to generate mock data).

```text
/frontend-dashboard > "Here is my Q4 e-commerce data: Revenue 2.45M (+14%), 124k active users... Please generate a dashboard."
```

The workflow:
1. **Analyze**: The AI ingests the data and identifies core KPIs.
2. **Pitch**: The AI shows you 3 distinct visual styles (e.g., *Modern SaaS*, *Cyberpunk Monitor*, *Glassmorphism Analytics*) and asks for your choice.
3. **Generate**: You reply with "1", "2", or "3".
4. **Deliver**: The AI writes a complete, single-file HTML dashboard and saves it to your machine.

## Included Styles

- **Modern SaaS** — Clean, trustworthy, high-contrast. Designed for modern B2B web applications (Silicon Valley inspired).
- **Cyberpunk Monitor** — Dark, glowing, high-density. Designed for real-time NOCs and hacker aesthetics.
- **Executive Financial** — Serious, dense, print-inspired. Emphasizes typography for high-stakes reporting.
- **Glassmorphism Analytics** — Trendy, colorful, blurred backgrounds. Modern and spatial (VisionOS inspired).

## Output Example

Each dashboard is a self-contained HTML file:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <!-- Fonts, CSS variables, all styles inline -->
    <script src="https://cdn.jsdelivr.net/npm/echarts/dist/echarts.min.js"></script>
</head>
<body>
    <header>...</header>
    <div class="kpi-grid">...</div>
    <div class="charts-grid">...</div>
    <script>
        // Chart initialization and responsive resize logic
    </script>
</body>
</html>
```

## Philosophy

1. **You don't need to be a designer to make beautiful things.** You just need to react to what you see.
2. **Dependencies are debt.** A single HTML file will work in 10 years. A complex React dashboard from 2019? Good luck.
3. **Automate the friction.** Going from raw data to a beautiful chart usually takes hours of boilerplate. This reduces it to seconds.

## License

MIT — Use it, modify it, share it.
