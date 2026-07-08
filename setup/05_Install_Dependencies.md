# 5. Install Python Dependencies

After activating the virtual environment, install all required Python packages.

---

## Upgrade pip

```powershell
python -m pip install --upgrade pip
```

---

## Install Required Packages

Install the required packages one by one.

Example:

```powershell
pip install numpy==1.26.4
```

```powershell
pip install qutip==5.0.4
```

Continue installing the remaining packages as required by the QubiC framework.

> In the next revision of this guide, the complete package list from `requirements_working.txt` will be included.

---

## Verify Installation

```powershell
pip list
```

This command displays all installed Python packages.

---

Next: [06_Run_Jupyter.md](06_Run_Jupyter.md)
