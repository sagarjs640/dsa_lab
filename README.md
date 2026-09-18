# 3rd Sem DSA Lab Visualizer & Code Stepper

An interactive, browser-based data structures and algorithms visualization laboratory tailored for university curriculum (VTU / Autonomous) lab courses. It features synchronized line-by-line C source tracking, real-time memory visualizers, dynamic pointer tracing, and an in-place code editor.

---

## Features

- **8 Core DSA Lab Implementations**:
  1. **Array Operations**: Dynamic 1-based vs 0-based index tracing, right/left shifting on insertion and deletion.
  2. **KMP String Matching**: Preprocessing of Longest Prefix Suffix (LPS) arrays and non-backtracking pattern searching.
  3. **Stack Operations & Palindrome**: Array-based LIFO stack visualization with underflow/overflow guards and string validation.
  4. **Infix to Postfix Converter**: Operator precedence-based expression parsing with real-time operator stack tracing.
  5. **Circular Queue**: Modulo-based wrap-around FIFO queue tracking front and rear pointers.
  6. **Singly Linked List (SLL)**: Heap node insertion at front, key deletion, search, and sequential traversal.
  7. **Doubly Linked List (DLL)**: Bidirectional pointer linking, node deletion, and left-side key insertion.
  8. **Binary Search Tree (BST)**: Dynamic SVG rendering of binary search trees with syllabus presets, recursive insertions, tree height metrics, and Preorder, Inorder, and Postorder traversals.

- **Interactive Execution Engine**:
  - **Live C Stepper**: Highlights corresponding lines in standard C syntax during runtime execution.
  - **Adjustable Speeds**: Choose between Slow (0.9s), Normal (0.4s), and Fast (0.15s) execution rates.
  - **Virtual C Terminal (`stdout`)**: Timestamped operational traces mimicking runtime standard output.
  - **In-Browser Code Editor**: Modify source code on the fly and restore default program templates anytime.

---

## Tech Stack

- **Markup & Layout**: Semantic HTML5 & Modern Flexbox/Grid
- **Styling**: [Tailwind CSS CDN](https://tailwindcss.com/)
- **Visual Rendering**: Pure CSS animations and dynamic SVG coordinate mapping
- **Engine**: Native ES6+ JavaScript (zero runtime dependencies)

---

## Getting Started

### 1. Run Locally
Because this project requires no compiler, build tools, or Node.js packages, it runs entirely in the browser.

1. Clone or download the repository:
   ```bash
   git clone [https://github.com/your-username/dsa-lab-visualizer.git](https://github.com/your-username/dsa-lab-visualizer.git)
   cd dsa-lab-visualizer
