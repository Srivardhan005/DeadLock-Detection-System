
# 🧠 Deadlock Detection System (Python)

A visual and interactive deadlock detection simulator using **Resource Allocation Graphs**, built completely in Python with **no frameworks** — ideal for understanding OS & DSA concepts like **graph traversal (DFS)** and **cycle detection**.

## 🔍 What It Does

This project simulates deadlock scenarios by letting users define:
- Processes (e.g., A, B, C...)
- Resources (e.g., R1, R2...)
- Which process **holds** and **requests** which resources

It then:
- **Visualizes the resource allocation graph** with colored edges
- **Detects deadlocks** using DFS-based cycle detection
- **Suggests deadlock resolution** by terminating the **least-priority process**
- Supports user actions like: `Add Process`, `Check Deadlock`, `Release Resource`, `Resolve Deadlock`

---

## 📸 Example Graph Output

<img width="484" height="504" alt="image" src="https://github.com/user-attachments/assets/0eb514c4-fda5-487f-8e2c-c7940a35637c" />


---

## ✨ Features

| Feature                        | Description                                       |
|-------------------------------|---------------------------------------------------|
| 🔁 Dynamic Input               | Add any number of processes and resources         |
| 🧠 DFS Cycle Detection         | Manual deadlock detection using depth-first search|
| 🟢 Green = HOLD                | Edge: Resource → Process                         |
| 🟠 Orange Dashed = REQUEST     | Edge: Process → Resource                         |
| 🔥 Deadlock Resolution         | Suggests terminating lowest-priority process      |
| 📊 Graph Visualization         | Clean, colored visual output using `matplotlib`   |
| 🧪 Debug Mode (optional)       | Shows full graph internals                       |

---

## 🛠 How to Run

> This is a **Jupyter Notebook / Colab-ready project**. No installation needed.

1. Clone the repository:
```bash
git clone https://github.com/yourusername/deadlock-detection-system.git
cd deadlock-detection-system
```

2. Open in [Google Colab](https://colab.research.google.com/) or Jupyter Notebook

3. Run cells and interact by calling:
```python
add_process('A', 'R1', 'R2', 1)
add_process('B', 'R3', 'R2', 2)
detect_deadlock()
resolve_deadlock()
```

---

## 📁 Project Structure

```
├── deadlock_detection.ipynb     # Main logic + UI
├── README.md                    # This file
```

---

## 🧠 Concepts Used

- Graph Theory
- Depth-First Search (DFS)
- Cycle Detection in Directed Graphs
- Deadlock in Operating Systems
- Data Structures: Dict, Set
- Visualization with `matplotlib` & `networkx`

---

## 🤖 Tech Stack

- Python 3.x
- `networkx` for graph structure
- `matplotlib` for visualization
- `IPython.display` for rich output in notebooks

---

## 💡 Future Enhancements

- GUI interface using `Tkinter` or `Streamlit`
- Drag-and-drop process/resource simulation
- Import from JSON or CSV
- Save simulation as PNG or PDF

---

## 💼 Why This Project Stands Out

> This project shows strong understanding of both **Computer Science fundamentals** and **clean Python coding**, making it perfect for:

- OS concept demonstrations
- DSA/Graph theory practice
- Placement-ready project portfolios
- Technical interview discussions

---

## 📄 License

This project is open-sourced under the [MIT License](LICENSE).

---

## 🙋‍♂️ Author

Made by [SRIVARDHAN](https://github.com/Srivardhan005)
