# ProblemHub

ProblemHub is a lightweight, responsive web application for discovering real-world problem statements, confirming user demand with willingness-to-pay signals, and tracking builder solutions from ideation to delivery.

Built as a zero-dependency, self-contained single-page application using vanilla HTML, CSS, and modern JavaScript.

---

## Features

- **Executive Dashboard**: Live telemetry for Total Problems, Demand Votes, Claimed Opportunities, and Solved Challenges.
- **Explore & Filter**: Instant search across titles, descriptions, and categories. Filter by Category (`Cybersecurity`, `Local Business`, `Entrepreneurship`, `Productivity`, `Education`, `Other`) and Status (`Open`, `Claimed`, `Prototype`, `Testing`, `Solved`).
- **Problem Submission**: Form for posting bottlenecks with target audience identification and current workarounds.
- **Confirm Demand**: "I have this problem too" interaction with optional "Willing to pay" indicator, preventing duplicate votes per browser session.
- **AI Problem Analyzer**: Heuristic problem statement synthesizer, auto-tagger, and discovery question generator (structured for LLM API plug-and-play).
- **Claim & Solution Proposals**: Enables builders to claim open opportunities, propose solutions, and link prototypes.
- **Status Lifecycle**: Transitions problems through `Open` → `Claimed` → `Prototype` → `Testing` → `Solved`.
- **Zero Configuration & Persistence**: Runs completely in the browser via `localStorage` with a 1-click **Reset Demo Data** option.

---

## Getting Started

No installation, build tools, Node.js, or server setup is required.

### Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/64gude/PROBLEM-HUB.git
   ```
2. Open `index.html` directly in any modern web browser:
   - On Windows: Double-click `index.html` or run `Start-Process index.html` in PowerShell.
   - On macOS/Linux: Run `open index.html` or `xdg-open index.html`.

---

## License

MIT License. Feel free to use and modify for your own projects.
