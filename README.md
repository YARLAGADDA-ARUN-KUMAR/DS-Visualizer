# 🎨 Data Structures Visualizer

An interactive, responsive web application to visualize the internal workings of common data structures.

## 🔗 Live Demo

🚀 **View Live Application:** [https://ds-visualizer-six.vercel.app/](https://ds-visualizer-six.vercel.app/)

## 📖 About

**DS Visualizer** is an educational tool designed to help students and developers understand how data structures function under the hood. Unlike static diagrams, this application provides real-time, animated visualizations of operations like insertion, deletion, and traversal.

Built entirely with **Vanilla JavaScript**, **HTML5**, and **CSS3**, it focuses on performance and clean, dependency-free code.

## ✨ Features

The application currently supports the following data structures and operations:

### 1. 📚 Stack (LIFO)

-   **Push**: Add an element to the top.
-   **Pop**: Remove the top element with animation.
-   **Peek**: Highlight the top element without removing it.
-   **Clear**: Reset the stack.

### 2. 🚶 Queue (FIFO)

-   **Enqueue**: Add an element to the rear.
-   **Dequeue**: Remove an element from the front.
-   **Front / Rear**: Highlight the first or last element.

### 3. 🔗 Singly Linked List

-   **Insert**: Add nodes at the **Head** or **Tail**.
-   **Delete**: Remove nodes from the **Head** or **Tail**.
-   **Visuals**: Shows pointers (`→`) and `NULL` termination.

### 4. 🔄 Circular Linked List

-   **Circular Logic**: Visualizes the last node pointing back to the Head (`↻`).
-   **Operations**: Insert / Delete at **Head** or **Tail**.

### 5. 🌳 Binary Search Tree (BST)

-   **Insert**: Recursively places nodes based on value (`Left < Root < Right`).
-   **Search**: Highlights the path taken to find a specific value.
-   **Traversals**: Visualizes and outputs:

    -   In-order (**Left, Root, Right**)
    -   Pre-order (**Root, Left, Right**)
    -   Post-order (**Left, Right, Root**)

-   **Dynamic Rendering**: Uses SVG lines to draw edges between nodes dynamically.

## 🛠️ Technologies Used

-   **HTML5** – Semantic structure.
-   **CSS3** – Custom properties (CSS variables), Flexbox layout, keyframe animations (`popIn`, `slideOut`), and responsive design.
-   **JavaScript (ES6+)** – Object-oriented programming (classes for nodes), DOM manipulation, and recursive algorithms for BST.

## 💻 Local Installation

No build tools (npm/yarn) are required for this project.

```bash
# Clone the repository
git clone https://github.com/yarlagadda-arun-kumar/ds-visualizer.git

# Navigate to the project directory
cd ds-visualizer
```

Now open `index.html` directly in your web browser.

For a better development experience, you can use the **Live Server** extension in VS Code.

## 📂 Project Structure

```text
ds-visualizer/
├── index.html      # Main HTML structure and layout
├── style.css       # Global styles, themes, and animations
├── script.js       # Core logic, data structure implementations, and DOM manipulation
└── README.md       # Project documentation
```

## 🎨 UI/UX Highlights

-   **Dark Mode**: Easy-on-the-eyes dark theme (`#121212` background).
-   **Responsive Sidebar**: Sidebar navigation transforms into a scrollable top bar on smaller screens.
-   **Error Handling**: Custom message box for user feedback (e.g., `Stack Empty`, `Not Found`).

## 🧩 Possible Future Improvements

-   Support for additional data structures (Heaps, Graphs, Hash Tables).
-   Step-by-step playback controls for operations.
-   Exporting operation history or screenshots for teaching material.

## 🤝 Contributing

Contributions, suggestions, and feedback are welcome!

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-name`.
3. Commit your changes: `git commit -m "Add feature"`.
4. Push to the branch: `git push origin feature-name`.
5. Open a pull request.

## 📄 License

This project is open-source. You are free to use, modify, and share it for learning and educational purposes.
