# Shortest Path Spotlight: Visualizing Dijkstra's Algorithm

A small React-based demo to build a weighted graph and visualize Dijkstra's shortest path.

## Features

- Add nodes by clicking on the board
- Draw weighted edges between nodes
- Select start and end nodes
- Run Dijkstra's algorithm to highlight the shortest path and show total cost

## Tech

- React 18
- Parcel bundler (zero-config dev server and build)
- HTML, CSS, JavaScript

## Getting Started

1. Install dependencies:

```bash
npm install
```

2. Start the dev server:

```bash
npm run dev
```

Then open the URL shown in your terminal (default `http://localhost:5173`).

3. Build for production (optional):

```bash
npm run build
```

## Usage

- Click "Add Node" and then click on the board to place nodes.
- Click "Add Edge" and then click two nodes; you'll be prompted for a weight.
- Click "Select Start" and then a node; repeat for "Select End".
- Click "Run Dijkstra" to compute and visualize the shortest path and total cost.
- Click "Reset" to clear the board.

## Notes

- Edges are treated as undirected for simplicity.
- This is intended for small graphs (teaching/demo). The priority selection is linear-time; no heap is used.


