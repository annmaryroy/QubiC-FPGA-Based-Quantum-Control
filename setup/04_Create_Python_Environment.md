# 4. Create a Python Virtual Environment

## Objective

A Python virtual environment provides an isolated workspace for installing the packages required by the **LBL QubiC Framework**. This prevents conflicts with other Python projects and ensures a consistent software environment.

---

## Navigate to the Working Directory

Open **Windows PowerShell** and navigate to the directory where the QubiC repositories were cloned.

```powershell
cd D:\software
```

> **Note:** Replace `D:\software` with your own workspace location if you chose a different directory.

---

## Create the Virtual Environment

Create a virtual environment named **qubic_env**.

```powershell
python -m venv qubic_env
```

After the command completes successfully, a new folder named **qubic_env** will be created in your workspace.

---

## Activate the Virtual Environment

Activate the environment before installing any Python packages.

```powershell
qubic_env\Scripts\activate
```

---

## Expected Output

If the activation is successful, the PowerShell prompt will change to:

```text
(qubic_env) PS D:\software>
```

This indicates that the virtual environment is active.

---

## Verify the Python Installation

Confirm that the correct Python version is being used.

```powershell
python --version
```

The recommended version for this project is:

```text
Python 3.10.x
```

---

## Why Use a Virtual Environment?

Using a virtual environment provides several advantages:

- Isolates project-specific Python packages.
- Prevents conflicts with system-wide Python installations.
- Makes the software environment easier to reproduce.
- Simplifies dependency management for QubiC.

---

## Official Resources

- **Python Virtual Environments (venv):** https://docs.python.org/3/library/venv.html
- **Python Downloads:** https://www.python.org/downloads/

---

## Next Step

Proceed to **[05_Install_Dependencies.md](05_Install_Dependencies.md)** to install the Python packages required by the QubiC framework.
