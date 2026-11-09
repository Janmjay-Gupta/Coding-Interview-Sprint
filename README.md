# DSA High-Frequency Interview Sprint

An interactive, zero-dependency interview revision companion engineered to help engineers bridge the gap between brute-force intuition and optimal $O(n)$ derivations in high-pressure technical interviews. 

Initially built as a single-page rapid revision tool for high-frequency algorithmic patterns in Java, this repository is evolving into an end-to-end interview preparation platform tailored for **Java Backend and Full-Stack Engineering roles**.

---

## Current Highlights

* **15 High-Yield Curated Problems:** Scoped specifically to high-frequency Day 1 (Arrays, Hashing, Two Pointers), Day 2 (Sliding Window, Intervals, Linked Lists), and Day 3 (Binary Search Essentials) challenges.
* **The "Aha!" Derivation Framework:** Breaks down the exact cognitive trigger to move from an $O(n^2)$ nested loop to an $O(n)$ optimal solution without rote memorization.
* **Side-by-Side Java Solutions:** Tabbed views for Brute Force vs. Optimal approaches with clean, idiomatic Java implementations and Big-O complexity breakdowns.
* **Visual Memory Anchors:** ASCII and structural diagrams for visualizing pointer movement, sliding window bounds, complement lookups, and cycle detection.
* **Verbal Communication Scripts:** Exact 5-step scripts (Clarify &rarr; Brute Force &rarr; State the Bottleneck &rarr; Optimal Strategy &rarr; Dry Run) to guide live whiteboard communication.
* **Device & Embed Adaptive:** Fully responsive across mobile displays (360px+), 13"–14" laptops, and 24"+ monitors, with sandboxed `localStorage` fail-safes for embedding directly inside Google Sites or Notion iframes.
* **Keyboard-First Workflow:** Navigate seamlessly during quick review sessions:
  * `J`: Next problem
  * `K`: Previous problem
  * `M`: Toggle mastery status

---

## Problem Coverage

| Day | Focus Area | Problems Included |
|---|---|---|
| **Day 1** | Arrays, Hash Maps & Two Pointers | LC 1 (Two Sum), LC 121 (Best Time to Buy/Sell Stock), LC 217 (Contains Duplicate), LC 242 (Valid Anagram), LC 49 (Group Anagrams), LC 53 (Maximum Subarray), LC 167 (Two Sum II), LC 15 (3Sum) |
| **Day 2** | Sliding Window, Intervals & Linked Lists | LC 3 (Longest Substring Without Repeating Characters), LC 11 (Container With Most Water), LC 56 (Merge Intervals), LC 206 (Reverse Linked List), LC 141 (Linked List Cycle) |
| **Day 3** | Binary Search Essentials | LC 704 (Binary Search), LC 33 (Search in Rotated Sorted Array) |

---

## Quick Start

### Run Locally
The current version is completely standalone with no Node.js or build-tool prerequisites:

```bash
# Clone the repository
git clone [https://github.com/](https://github.com/)<your-username>/<repo-name>.git

# Navigate into the project directory
cd <repo-name>

# Open directly in your browser
open index.html       # macOS
start index.html      # Windows
xdg-open index.html   # Linux
