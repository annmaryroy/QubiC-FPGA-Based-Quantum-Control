# Windows PowerShell Commands

This folder contains the **Windows PowerShell commands** used during my internship to set up and run the **LBL QubiC Framework** on Windows.

The commands are organized in the same order as the installation workflow, making it easy to reproduce the software environment from scratch.

---

## Workflow

```
PowerShell Setup
        │
        ▼
Clone Official QubiC Repositories
        │
        ▼
Create Python Virtual Environment
        │
        ▼
Install Dependencies
        │
        ▼
Launch Jupyter Notebook
        │
        ▼
Run the Official QubiC Tutorials
```

---

## Command Guide

| File | Description |
|------|-------------|
| `01_PowerShell_Setup.md` | Verify PowerShell, Git and Python installation. |
| `02_Clone_Repositories.md` | Clone all required official QubiC repositories from GitLab. |
| `03_Python_Environment.md` | Create and activate the Python virtual environment. |
| `04_Install_Dependencies.md` | Install the Python packages required by QubiC. |
| `05_Run_QubiC.md` | Launch Jupyter Notebook and execute the official tutorials. |

---

## Environment Used

- **Operating System:** Windows 11
- **Terminal:** Windows PowerShell
- **Python:** 3.10.x
- **Package Manager:** pip
- **Version Control:** Git
- **Notebook Environment:** Jupyter Notebook

---

## Notes

- All commands were tested during my internship at **National Institute of Technology Calicut (NITC)**.
- The commands are intended for reproducing the software workflow of the **QubiC** framework.
- The official QubiC source code is **not included** in this repository. Clone it directly from the official LBL GitLab repositories.

---

## Next Step

Follow the commands in numerical order:

```
01 → 02 → 03 → 04 → 05
```

to recreate the complete software environment.
