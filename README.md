# GraphLab — Graph Algorithm Visualizer

A responsive educational website for the **Algorithm Analysis and Design (ADA)** subject.

## Features
- Breadth-First Search (BFS)
- Depth-First Search (DFS)
- Dijkstra's shortest path on weighted graphs
- Classic, weighted, and sparse sample graphs
- Start/target node selection and step-by-step algorithm trace
- Visit order, queue/frontier, current node, and path highlighting
- Responsive layout for desktop and mobile

## Run locally
No build tools are required. Download or clone this repository and open `index.html` in a web browser.

## GitHub Pages
1. Open repository **Settings → Pages**.
2. Under **Build and deployment**, select **Deploy from a branch**.
3. Select the `main` branch and `/(root)`, then save.
4. Open the URL shown after GitHub Pages publishes the site.

## Files
- `index.html` — page structure
- `style.css` — responsive styling
- `app.js` — graph data and algorithm visualization logic

## Complexity
| Algorithm | Time complexity |
| --- | --- |
| BFS | O(V + E) |
| DFS | O(V + E) |
| Dijkstra (priority queue implementation) | O((V + E) log V) |

V = vertices; E = edges.
