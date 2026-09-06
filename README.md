# 🚇 DSA Metro Map

> **Learn Data Structures & Algorithms like you would navigate a metro system.**
>
> Topics become **stations**, related concepts become **lines**, and important concepts become **interchanges** — giving you a visual roadmap from DSA fundamentals to interview readiness.

<p align="center">
  <a href="https://dsa-map-jet.vercel.app/"><strong>🚀 Live Demo</strong></a>
  &nbsp; • &nbsp;
  <a href="https://github.com/mishtee-khanna/dsa-map">📂 Repository</a>
</p>

---

## ✨ Overview

The **DSA Metro Map** is a lightweight, interactive study companion designed to make DSA easier to visualize and navigate.

Instead of studying from a long checklist, you can follow connected learning paths through different DSA areas and track the topics you have already explored.

### 🗺️ The Metro Lines

| Line | Topics Covered |
|---|---|
| 🟡 **Foundations Line** | Arrays, Strings, Hashing, Two Pointers, Sliding Window, Prefix Sums |
| 🔵 **Linear Structures Line** | Linked Lists, Stacks, Queues/Deques, Monotonic Stack |
| 🟠 **Search & Sort Line** | Sorting, Binary Search, Binary Search on Answer, Greedy |
| 🟢 **Tree Line** | Binary Trees, BST, Heaps, Tries, Segment Trees |
| 🟣 **Graph Line** | BFS/DFS, Union-Find, Topological Sort, Shortest Paths, MST |
| 🌸 **Recursion & DP Line** | Recursion, Backtracking, 1D DP, Knapsack, Interval/2D DP, Bitmask DP |

The lines connect through important **interchanges**, ultimately leading toward an **Interview Ready** destination.

---

## 🎯 Features

- 🚉 **30+ DSA stations** covering major interview topics
- 📖 **Topic details** with explanations, difficulty levels, and practice problems
- 🔎 **Search** to quickly find a DSA topic
- 🎨 **Line filtering** to focus on a specific learning path
- ✅ **Progress tracking** with visited stations and a progress indicator
- 📱 **Responsive design** for desktop and smaller screens
- ♿ **Reduced-motion support** through `prefers-reduced-motion`
- ⚡ **Zero dependencies** and no build process
- 📄 **Single-file application** — the complete site lives in `index.html`

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **HTML5** | Page structure and content |
| **CSS3** | Layout, styling, responsiveness and animations |
| **SVG** | Custom metro-map visualization |
| **Vanilla JavaScript** | Rendering, search, filtering and interactions |
| **Google Fonts** | Space Grotesk, Inter and JetBrains Mono |

### Why no framework?

This project intentionally uses **vanilla HTML, CSS and JavaScript**. Since the application is a static interactive visualization, a framework or build system would add unnecessary complexity.

That keeps the project:

- ⚡ Fast to load
- 🪶 Lightweight
- 🔧 Easy to modify
- 🚀 Simple to deploy

---

## 🚀 Getting Started

### 1. Clone the repository

```bash
git clone https://github.com/mishtee-khanna/dsa-map.git
cd dsa-map
```

### 2. Run locally

Because this is a static website, you can simply open `index.html` in your browser.

For a local development server, use Python:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

---

## ☁️ Deployment

The project is deployed as a static site on **Vercel**.

### Live Website

👉 **https://dsa-map-jet.vercel.app/**

Because the main file is named `index.html`, Vercel can serve the application directly from the root URL without a framework or build command.

---

## 📁 Project Structure

```text
dsa-map/
│
├── index.html     # Complete application: HTML + CSS + JavaScript
└── README.md      # Project documentation
```

---

## 🧠 How It Works

The map is generated from structured JavaScript data inside `index.html`.

Each DSA topic contains information such as:

```text
Topic
 ├── Line / Category
 ├── Difficulty
 ├── Description
 └── Practice Problems
```

JavaScript uses this data to render the stations and their interactions on the SVG-based map.

### User Flow

```text
Explore the Map
       ↓
Choose a Metro Line
       ↓
Select a DSA Station
       ↓
Read the Concept
       ↓
Practice Problems
       ↓
Mark Station as Visited
       ↓
Track Progress
       ↓
Interview Ready 🚀
```

---

## 📌 Current Limitations

- Progress is currently **session-based** and resets when the page is refreshed.
- Practice problems are curated starting points rather than an exhaustive problem list.
- There is currently no login or backend/database.

---

## 🔮 Future Improvements

- [ ] 💾 Persist progress using `localStorage`
- [ ] 🔗 Add direct links to LeetCode / NeetCode practice sets
- [ ] 🧭 Add a guided learning route
- [ ] 🌙 Add dark/light theme support
- [ ] 📊 Add detailed progress statistics
- [ ] 🖼️ Export a personalized DSA progress map
- [ ] 👤 Add optional user accounts and cloud progress syncing

---

## 🤝 Contributing

Contributions and suggestions are welcome!

```bash
git checkout -b feature/your-feature-name
git add .
git commit -m "Add your feature"
git push origin feature/your-feature-name
```

Then open a Pull Request on GitHub.

---

## 👩‍💻 Author

**Mishtee Khanna**

- GitHub: [@mishtee-khanna](https://github.com/mishtee-khanna)
- Project: [DSA Metro Map](https://github.com/mishtee-khanna/dsa-map)

---

## ⭐ Support

If you find the **DSA Metro Map** useful for your DSA preparation, consider giving the repository a ⭐ on GitHub!

<p align="center">
  <strong>🚇 Pick a line. Visit a station. Master DSA. 💻</strong>
</p>
