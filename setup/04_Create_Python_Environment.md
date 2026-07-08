# 4. Create a Python Virtual Environment

A Python virtual environment keeps the project dependencies isolated from the system-wide Python installation.

---

## Navigate to the Working Directory

Open **Windows PowerShell** and move to the directory where you cloned the repositories.

```powershell
cd D:\software
```

> Replace `D:\software` with the location where you created your workspace.

---

## Create a Virtual Environment

```powershell
python -m venv qubic_env
```

A new folder named **qubic_env** will be created.

---

## Activate the Environment

```powershell
qubic_env\Scripts\activate
```

If activated successfully, PowerShell will display:

```text
(qubic_env) PS D:\software>
```

---

## Verify Python Version

```powershell
python --version
```

The recommended version used in this project is **Python 3.10.x**.

---

Next: [05_Install_Dependencies.md](05_Install_Dependencies.md)
