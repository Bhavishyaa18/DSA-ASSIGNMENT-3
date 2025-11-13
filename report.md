
---

# `report.md` (root)
```markdown
# Report: Campus Navigation and Utility Planner

## 1. Building Data ADT
Attributes: BuildingID (int), BuildingName (str), LocationDetails (str).
Methods: insertBuilding, traverseBuildings, evaluateExpression (via expression tree).

## 2. Implementation strategy
- Binary Search Tree (BST) for building records keyed by BuildingID.
- AVL Tree for balanced storage and to demonstrate rotations.
- Graph represented with adjacency list (for algorithms) and adjacency matrix (for lookups).
- Map building IDs to compact graph indices (0..n-1).

## 3. Algorithms implemented
- BST traversals: inorder, preorder, postorder.
- AVL rotations: LL, RR, LR, RL (handled automatically by code).
- Graph traversals: BFS, DFS.
- Dijkstra's algorithm for shortest path (heapq).
- Kruskal's algorithm for minimum spanning tree (union-find).
- Expression tree: build from postfix and evaluate.

## 4. Complexity
- AVL insert/search: O(log n)
- BST worst-case: O(n)
- Dijkstra (binary heap): O((V+E) log V)
- Kruskal: O(E log E)

## 5. Test
Run `python3 src/main.py` to view sample outputs and use `test_data.txt` for building/edge examples.

Prepared for ENCS205 — Assignment 3.
