### File Name: `iris_decision_tree.py`

### README:

This project implements the ID3 (Iterative Dichotomiser 3) algorithm to construct a decision tree for the Iris dataset. It calculates entropy and information gain to determine the best features for splitting and visualizes the resulting decision tree using the Graphviz library.

---

**Features:**
- Calculates entropy and information gain for feature selection.
- Implements the ID3 algorithm to build a decision tree.
- Displays histograms of feature distributions.
- Generates a visual representation of the decision tree.

---

**Dependencies:**
- `numpy`
- `pandas`
- `matplotlib`
- `graphviz`

---

**Setup:**

Install Python dependencies:
   ```
   pip install numpy pandas matplotlib graphviz
   ```

**Instructions:**
1. Save the code in a file named `iris_decision_tree.py`.
2. Place the `iris.data` file (Iris dataset) in the same directory as the script.
3. Run the script:
   ```
   python iris_decision_tree.py
   ```

---

**Outputs:**
- **Histograms:** Displays feature distributions.
- **Decision Tree Visualization:** Saves a file named `Digraph.gv.pdf` containing the visualized decision tree.

---

This project serves as a simple educational implementation of the ID3 algorithm.
