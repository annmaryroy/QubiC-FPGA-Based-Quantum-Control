# 5. Install Python Dependencies

## Objective

This section installs the Python packages required to run the **LBL QubiC Framework** and its official tutorial notebooks.

All packages should be installed **after activating the Python virtual environment**.

---

## Upgrade pip

Before installing the required packages, upgrade **pip** to the latest version.

```powershell
python -m pip install --upgrade pip
```

---

## Install the Required Packages

### Option 1 (Recommended)

Install all required packages using the provided **requirements.txt** file.

```powershell
pip install -r requirements.txt
```

---

### Option 2 (Manual Installation)

If you prefer, install the packages individually.

Example:

```powershell
pip install numpy==1.26.4
```

```powershell
pip install qutip==5.0.4
```

Install the remaining packages as listed in **requirements.txt**.

---

## Verify the Installation

Display all installed Python packages.

```powershell
pip list
```

Verify that the required packages have been installed successfully.

---

## Official Resources

- **pip Documentation:** https://pip.pypa.io/en/stable/
- **Python Packaging User Guide:** https://packaging.python.org/
- **NumPy Documentation:** https://numpy.org/doc/
- **QuTiP Documentation:** https://qutip.readthedocs.io/

---

## Next Step

Proceed to **[06_Run_Jupyter.md](06_Run_Jupyter.md)** to launch Jupyter Notebook and execute the official QubiC tutorials.
