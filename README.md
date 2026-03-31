# Interactive Discrete Mathematics Learning Model

A comprehensive, single-page web application designed to help students and enthusiasts visualize, calculate, and explore core concepts in discrete mathematics. Built entirely with standard web technologies, this tool requires no backend or complex setup to run.

## 🚀 Features

This application is divided into several interactive modules:

* **Logic:** Includes a propositional logic builder and a truth table generator for operations like AND, OR, NOT, Implies, Biconditional, and XOR. It also provides a reference for fundamental logical laws and predicate logic.
* **Set Theory:** Features a calculator for operations like union, intersection, difference, symmetric difference, cardinality, and power sets. Includes a visual Venn Diagram built with SVG.
* **Graph Theory:** Contains an interactive, canvas-based graph builder where users can add nodes and edges. It analyzes graph properties (degrees, vertices, edges), checks for Euler paths/circuits, and verifies if a graph is bipartite.
* **Combinatorics:** Offers a counting calculator for permutations, combinations, factorials, and derangements. It dynamically generates Pascal's Triangle and lists core counting principles.
* **Number Theory:** Provides a comprehensive calculator for GCD, LCM, prime factorization, modular arithmetic, and Euler's Totient. It also features a step-by-step Euclidean Algorithm trace tool.
* **Relations:** Features an interactive 4x4 relation matrix builder to test for reflexive, symmetric, antisymmetric, and transitive properties. It can identify equivalence relations and partial orders.
* **Practice Quiz:** A built-in interactive quiz with multiple-choice questions covering various discrete math topics with instant feedback and scoring.
* **AI Tutor Integration:** An interface designed to connect to an AI model (specifically configured for Anthropic's Claude API) to answer custom discrete math questions.

## 🛠️ Tech Stack

* **Frontend:** HTML5, CSS3 (with custom variables for theming), Vanilla JavaScript.
* **Graphics:** HTML5 `<canvas>` API for graph rendering and `<svg>` for set visualizations.
* **Typography:** Google Fonts (`DM Serif Display`, `DM Mono`, `Outfit`).

## 📦 Installation & Setup

Because this project is built as a single, self-contained HTML file, there is no build process or package installation required.

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/yourusername/discrete-math-model.git](https://github.com/yourusername/discrete-math-model.git)
    cd discrete-math-model
    ```
2.  **Run the application:**
    Simply open the `project.html` file directly in any modern web browser.

## ⚠️ Note on the AI Tutor Feature

The "Ask AI" tab is configured to make a client-side POST request to the Anthropic API (`api.anthropic.com`). For this feature to work in a live or production environment, you will need to implement a backend proxy to securely store and handle your API keys, as client-side API requests are typically blocked by CORS policies and expose your private keys. 

## 🤝 Contributing
Contributions, issues, and feature requests are welcome! Feel free to check the issues page if you want to contribute.
