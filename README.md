
# Network Analysis for Digital Humanities Students

A foundational guide and resource repository for Digital Humanities students to learn and apply **Network Analysis** using **Python** and **NetworkX**. This project includes tutorials, datasets, and exercises to analyze, visualize, and interpret networks related to social, cultural, and historical studies.

---

## Table of Contents

1. [Project Overview](#project-overview)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Repository Structure](#repository-structure)
5. [Examples](#examples) (TBC)
6. [Contributing](#contributing)
7. [License](#license)

---

### Project Overview

**Network Analysis** enables researchers in Digital Humanities to explore relationships in literature, history, social networks, and cultural data.

- **What’s Included**:
  - Tutorials on **NetworkX** for creating, analyzing, and visualizing networks.
  - Sample datasets relevant to Digital Humanities.
  - Practical exercises and visualizations to support learning.

---

### Installation

To get started, clone this repository and install the required dependencies.

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/NetworkAnalysis-DH.git
   cd NetworkAnalysis-DH
   ```

2. **Install Required Packages**:
   ```bash
   pip install -r requirements.txt
   ```

   - **Dependencies**: `networkx`, `pandas`, `matplotlib`, and `jupyter`

3. **Optional**: Install Jupyter for interactive tutorials:
   ```bash
   pip install jupyter
   ```

---

### Usage

1. **Start Jupyter Notebook**:
   - Run Jupyter in the project directory to explore tutorials and examples interactively:
     ```bash
     jupyter notebook
     ```

2. **Explore the Notebooks**:
   - Each notebook covers specific aspects of network analysis:
     - `01-Basics.ipynb`: Network creation and manipulation basics.
     - `02-Visualizing-Networks.ipynb`: Techniques for network visualization.
     - `03-Analyzing-Graphs.ipynb`: Common network analysis techniques.

3. **Analyze Custom Datasets**:
   - Load custom CSV datasets (e.g., `source` and `target` columns) and apply network analysis techniques using provided tutorials.

---

### Repository Structure

```
NetworkAnalysis-DH/
├── data/                  # Sample datasets
├── notebooks/             # Jupyter notebooks for tutorials
├── scripts/               # Python scripts for network analysis
├── requirements.txt       # Dependencies
└── README.md              # Project overview and instructions
```

- **`data/`**: Sample datasets: we recommend sourcing sample datasets from Kaggle.
- **`notebooks/`**: Jupyter notebooks guiding students through creating and analyzing networks.
- **`scripts/`**: Standalone Python scripts for those who prefer working directly in the terminal.

---

### Contributing

We welcome contributions to improve this repository! If you have ideas for new examples, optimizations, or features, please feel free to fork the repository, make changes, and submit a pull request.

---

### License

This project is licensed under the MIT License. See `LICENSE` for more details.
