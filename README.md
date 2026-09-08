# Rooster
Data analysis on an online retailer of premium activewear, with a range of products for women and men.

# Setup
## Project Setup

Follow these steps to set up the project on your computer.

### 1. Clone the GitHub Repository

Open **Terminal** in VS Code and run:

```bash
git clone <YOUR-GITHUB-REPOSITORY->
```

Then move into the project folder:

```bash
cd ROOSTER
```

Alternatively, you can clone the project using:

**VS Code → Source Control → Clone Repository**

---

### 2. Create a Python Virtual Environment

Create a virtual environment inside the project:

```bash
python3 -m venv .venv
```

Activate the environment.

**macOS:**

```bash
source .venv/bin/activate
```

**Windows:**

```bash
.venv\Scripts\activate
```

After activation, you should see something similar to:

```text
(.venv)
```

at the beginning of your terminal.

---

### 3. Install Required Libraries

Make sure the virtual environment is activated, then run:

```bash 
pip install pandas
pip install numpy
pip install matplotlib
pip install seaborn
pip install scikit-learn
```
note. only the relevant librarys
This will automatically install the Python libraries required for the project.

---

### 4. Select the Python Environment in VS Code

Press:

**Mac:** `Command + Shift + P`

**Windows:** `Ctrl + Shift + P`

Search for:

```text
Python: Select Interpreter
```

Select:

```text
.venv
```

If you are using a Jupyter Notebook (`.ipynb`), also select `.venv` as the notebook **Kernel** in the top-right corner.

---

### 5. Open the Notebook

Open the required `.ipynb` file from the `notebooks` folder.

Run the library cells to check that everything is working.

