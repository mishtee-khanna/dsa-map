<div align="center">

# 🚇 DSA Metro Map

### *Your visual route from DSA Beginner → Interview Ready.*

<p>
  <a href="https://dsa-map-jet.vercel.app/"><img src="https://img.shields.io/badge/🚀_Live_Demo-F2B705?style=for-the-badge&logoColor=111111" alt="Live Demo"></a>
  <a href="https://github.com/mishtee-khanna/dsa-map"><img src="https://img.shields.io/badge/⭐_GitHub-111827?style=for-the-badge&logo=github" alt="GitHub"></a>
</p>

<p>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=111111" alt="JavaScript">
  <img src="https://img.shields.io/badge/SVG-FFB13B?style=flat-square&logo=svg&logoColor=111111" alt="SVG">
  <img src="https://img.shields.io/badge/Zero_Dependencies-22C55E?style=flat-square" alt="Zero Dependencies">
</p>

**Topics are stations. Concepts are lines. Interchanges connect everything.**

</div>

---

## 🌟 What is DSA Metro Map?

The **DSA Metro Map** turns Data Structures & Algorithms preparation into an interactive subway journey.

Instead of staring at a huge checklist of topics, you can **follow learning paths, explore stations, practice problems, and track your progress** — all through a clean metro-style interface.

> 🧠 **Think of it as a visual roadmap for your DSA preparation.**

---

## 🗺️ Explore the Lines

| 🚇 Line | 📚 Topics |
|:---|:---|
| 🟡 **Foundations** | Arrays · Strings · Hashing · Two Pointers · Sliding Window · Prefix Sums |
| 🔵 **Linear Structures** | Linked Lists · Stacks · Queues/Deques · Monotonic Stack |
| 🟠 **Search & Sort** | Sorting · Binary Search · Binary Search on Answer · Greedy |
| 🟢 **Trees** | Binary Trees · BST · Heaps · Tries · Segment Trees |
| 🟣 **Graphs** | BFS/DFS · Union-Find · Topological Sort · Shortest Paths · MST |
| 🌸 **Recursion & DP** | Recursion · Backtracking · 1D DP · Knapsack · 2D/Interval DP · Bitmask DP |

### 🚉 The Journey

```text
                         ┌───────────────┐
                         │   FOUNDATIONS  │
                         └───────┬───────┘
                                 │
     ┌──────────────┐            │            ┌──────────────┐
     │    LINEAR    ├────────────┼────────────┤  SEARCH/SORT │
     └──────────────┘            │            └──────────────┘
                                 ▼
                    🔄 INTERCHANGE STATIONS
                                 │
                    ┌────────────┴────────────┐
                    ▼                         ▼
                 🌳 TREES                   🟣 GRAPHS
                    │                         │
                    └───────────┬─────────────┘
                                ▼
                         🌸 RECURSION & DP
                                │
                                ▼
                       🚀 INTERVIEW READY
```

---

## ✨ Features

<table>
<tr>
<td>🚉 <b>30+ Stations</b><br>Major DSA interview topics.</td>
<td>🔎 <b>Smart Search</b><br>Find a topic instantly.</td>
</tr>
<tr>
<td>🎨 <b>Line Filtering</b><br>Focus on one learning path.</td>
<td>📖 <b>Topic Details</b><br>Concepts, difficulty & problems.</td>
</tr>
<tr>
<td>✅ <b>Progress Tracking</b><br>Mark stations as visited.</td>
<td>📱 <b>Responsive</b><br>Works across screen sizes.</td>
</tr>
<tr>
<td>⚡ <b>Zero Dependencies</b><br>No npm or build setup.</td>
<td>♿ <b>Reduced Motion</b><br>Accessibility-aware animations.</td>
</tr>
</table>

---

## 🛠️ Tech Stack

```text
┌────────────────────────────────────────────────────┐
│                    DSA METRO MAP                   │
├──────────────────┬─────────────────────────────────┤
│ HTML5            │ Structure & content             │
│ CSS3              │ Styling, layout & animations   │
│ SVG               │ Interactive metro visualization │
│ Vanilla JavaScript│ Rendering & application logic   │
│ Google Fonts      │ Space Grotesk · Inter · Mono   │
└──────────────────┴─────────────────────────────────┘
```

### 💡 Why Vanilla JavaScript?

The project is intentionally framework-free. For a lightweight static visualization, using vanilla HTML, CSS and JavaScript keeps the application:

- ⚡ Fast
- 🪶 Lightweight
- 🔧 Easy to understand and customize
- 🚀 Extremely simple to deploy

---

## 🚀 Run Locally

### 1️⃣ Clone

```bash
git clone https://github.com/mishtee-khanna/dsa-map.git
cd dsa-map
```

### 2️⃣ Open

You can simply open `index.html` in your browser.

Or start a local server:

```bash
python3 -m http.server 8000
```

Then visit:

```text
http://localhost:8000
```

---

## ☁️ Live Deployment

The application is deployed as a **static website on Vercel**.

<div align="center">

### 🚀 [OPEN DSA METRO MAP](https://dsa-map-jet.vercel.app/)

*Pick a line. Visit a station. Master DSA.*

</div>

---

## 📁 Project Structure

```text
dsa-map/
│
├── 📄 index.html      # Complete application
│                       # HTML + CSS + JavaScript
│
└── 📘 README.md       # Documentation
```

> **One file. Zero setup. Complete interactive experience.**

---

## 🧠 How It Works

All station and line information is maintained as structured JavaScript data inside `index.html`.

```text
             DSA DATA
                 │
                 ▼
        ┌─────────────────┐
        │ JavaScript Data │
        └────────┬────────┘
                 │
                 ▼
        ┌─────────────────┐
        │  SVG Rendering  │
        └────────┬────────┘
                 │
        ┌────────┼────────┐
        ▼        ▼        ▼
     Search   Filter   Stations
        │        │        │
        └────────┼────────┘
                 ▼
          Detail Panel
                 │
                 ▼
        Mark as Visited
                 │
                 ▼
          Track Progress
```

### 🎯 Typical User Flow

**Explore → Choose a Line → Select a Station → Learn → Practice → Mark Visited → Track Progress → Interview Ready 🚀**

---

## 📌 Current Limitations

- 🔄 Progress resets when the page is refreshed.
- 📚 Practice problems are curated starting points, not an exhaustive problem bank.
- 👤 No login, backend, or database is currently required.

---

## 🔮 Roadmap

- [ ] 💾 Persist progress with `localStorage`
- [ ] 🔗 Add direct LeetCode / NeetCode links
- [ ] 🧭 Add guided learning routes
- [ ] 📊 Add detailed progress analytics
- [ ] 🌗 Add theme switching
- [ ] 🖼️ Export personalized progress maps
- [ ] ☁️ Optional account-based cloud sync

---

## 🤝 Contributing

Found something that could be better? Contributions are welcome!

```bash
git checkout -b feature/your-feature-name
git add .
git commit -m "Add your feature"
git push origin feature/your-feature-name
```

Then open a Pull Request. 🚀

---

## 👩‍💻 Author

<div align="center">

### **Mishtee Khanna**

Computer Science Engineering · DSA · Web Development

<a href="https://github.com/mishtee-khanna">GitHub Profile</a>

</div>

---

<div align="center">

### ⭐ If this helped your DSA preparation, consider starring the repository!

**🚇 Learn the route. Master the concepts. Ace the interview. 💻**

</div>
