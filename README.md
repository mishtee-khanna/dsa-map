# The DSA Metro Map 🚇

An interactive, single-file website that maps out Data Structures & Algorithms the way a city maps out its subway system — topics as stations, related concepts grouped into color-coded lines, and a few key interchanges where everything connects.

---

## What it is

Instead of a flat checklist, DSA topics are laid out as six subway lines:

| Line | Covers |
|---|---|
| 🟡 **Foundations Line** | Arrays, Strings, Hashing, Two Pointers, Sliding Window, Prefix Sums |
| 🔵 **Linear Structures Line** | Linked List, Stack, Queue/Deque, Monotonic Stack |
| 🟠 **Search & Sort Line** | Sorting, Binary Search, Binary Search on Answer, Greedy |
| 🟢 **Tree Line** | Binary Trees, BST, Heaps, Tries, Segment Trees |
| 🟣 **Graph Line** | Graph Basics (BFS/DFS), Union-Find, Topological Sort, Shortest Paths, MST |
| 🌸 **Recursion & DP Line** | Recursion/Backtracking, 1D DP, Knapsack, Interval/2D DP, Bitmask DP |

All lines pass through a central **Recursion & Backtracking** interchange and converge at a final **Interview Ready** terminus — the shape of the map tells the story of how these topics build on each other.

## Features

- **30 topic "stations,"** each with a short explanation, a difficulty tag, and 3 key problems to practice
- **Click any station** to open a detail panel with more info
- **Line filtering** — click a line in the legend to highlight just that track and dim the rest
- **Search** — jump straight to a topic by typing its name
- **Progress tracking** — mark stations as visited and watch the counter/progress bar fill up
- Fully responsive, with a horizontally scrollable map on smaller screens
- Zero dependencies, zero build step — one HTML file

## Tech Stack

- **HTML5 + inline SVG** — the map itself is a hand-plotted SVG line diagram
- **CSS3** — custom properties, responsive layout, `prefers-reduced-motion`-aware animations
- **Vanilla JavaScript** — renders stations/lines from a data array and handles all interactivity
- **Google Fonts** — Space Grotesk, Inter, and JetBrains Mono (loaded via CDN)

No frameworks, no npm install, no build tools.

## Getting Started

This is a static, single-file site — just open it in a browser.

1. Clone the repository
   ```bash
   git clone https://github.com/<your-username>/<your-repo>.git
   cd <your-repo>
   ```
2. Open `dsa-map.html` directly in your browser, **or** serve it locally:
   ```bash
   python3 -m http.server 8000
   # then visit http://localhost:8000/dsa-map.html
   ```

### Deploying to GitHub Pages

1. Push this repo to GitHub.
2. Go to **Settings → Pages**.
3. Under "Build and deployment," set the source to your default branch.
4. If `dsa-map.html` isn't your repo's `index.html`, either rename it to `index.html` or link to it directly, e.g. `https://<your-username>.github.io/<your-repo>/dsa-map.html`.

## Project Structure

```
.
├── dsa-map.html   # The entire site — markup, styles, and script in one file
└── README.md
```

## Notes & Limitations

- **Progress isn't saved.** Visited stations reset on page refresh, since the map intentionally avoids browser storage — treat it as a session-based study companion rather than a persistent tracker. Adding real persistence (e.g. `localStorage`, or an account-backed backend) is a natural next step.
- Topic descriptions and recommended problems are meant as a starting point, not an exhaustive curriculum.

## Roadmap Ideas

- [ ] Persist visited stations across sessions
- [ ] Link each station directly to curated problem sets (LeetCode/NeetCode/etc.)
- [ ] Add a "suggested route" mode that walks through stations in recommended order
- [ ] Dark/light theme toggle
- [ ] Export progress as a shareable image

## Contributing

Contributions are welcome — whether it's fixing a typo in a description, adding more practice problems, or improving the map layout.

```bash
git checkout -b feature/your-feature-name
git commit -m "Add your feature"
git push origin feature/your-feature-name
```

## License

This project is currently unlicensed. Consider adding a [LICENSE](https://choosealicense.com/) file (e.g., MIT) if you'd like others to freely reuse or build on it.
