# Kalman Filtering for Sparse Signals

This project explores the use of sparsity-aware Kalman filtering for tracking dynamic systems with sparse state vectors. The implementation includes signal generation, baseline Kalman filtering, sparsity enforcement, and performance evaluation.

---

## 🔧 Setup Instructions

### Step 1: Clone the Repository

```bash
git clone https://github.com/alireza-es/kalman-sparse-filtering.git
cd kalman-sparse-filtering
```

### Step 2: Create and Activate a Python Environment (Using pyenv + venv)

Make sure you have pyenv installed. Then:

```bash
pyenv install 3.10.11  # or skip if already installed
pyenv local 3.10.11    # sets the Python version locally
python -m venv .venv
source .venv/bin/activate
```

### Step 3: Install Python Dependencies

```bash
pip install --upgrade pip
pip install -r requirements.txt
```

### Step 4: Launch Jupyter Notebook

```bash
jupyter notebook
```

Open the notebooks in the notebooks/ directory to run each part of the project.


