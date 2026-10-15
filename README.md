# ARKO Studio — Graph & Algorithm Engine v0.1

A dependency-free, local-first graph editor and algorithm execution visualizer.

## Run

Open `index.html` in a modern browser. No packages, keys, or server needed.

## Features

- Drag and rename nodes; connect nodes and edit edge weights.
- Toggle directed and undirected graph representation.
- Run BFS, DFS, and Dijkstra with step-by-step traces.
- Generate copyable JavaScript implementations using your current graph.
- Import/export JSON graphs and persist data in browser localStorage.
- Two sample graph templates.

## Scope

This is a **graph-algorithm solver**, not yet a general natural-language problem-to-algorithm generator. Dijkstra requires nonnegative weights; this editor enforces that constraint. The solver is deliberately educational and uses an O(V² + E) minimum-vertex search rather than a heap. Graph layouts are local coordinate positions. Local storage is not a secure shared database.

## Proposed next milestones

1. Flowchart/block-program node editor with typed input/output ports.
2. Typed intermediate representation, workflow validation, and execution runtime.
3. A* and Bellman-Ford, priority queues, benchmark datasets, unit tests.
4. Code generation and equivalence testing for multiple languages.
5. Optional server-side run sandbox with strict resource limits.
