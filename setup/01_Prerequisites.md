# 1. Prerequisites

## Objective

This section describes the software and system requirements needed to install and run the **LBL QubiC Framework** on a Windows system.

---

## Operating System

- Windows 11 (Recommended)

---

## Software Requirements

| Software | Purpose |
|-----------|---------|
| Git | Clone the official QubiC repositories from GitLab |
| Python 3.10 | Execute the QubiC software and tutorial notebooks |
| Windows PowerShell | Command-line interface used throughout this guide |
| Jupyter Notebook | Execute the official QubiC tutorial notebooks |
| Visual Studio Code *(Optional)* | View and edit Python scripts and notebooks |

---

## Before You Begin

Before proceeding, ensure that:

- Git is installed and accessible from Windows PowerShell.
- Python 3.10 is installed.
- `pip` is installed with Python.
- Windows PowerShell is available.
- A stable internet connection is available to download repositories and Python packages.

---

## Verify the Installation

Open **Windows PowerShell** and verify the installation of the required software.

### Check Python

```powershell
python --version
```

### Check Git

```powershell
git --version
```

### Check pip

```powershell
pip --version
```

---

## Expected Output

Each command should return the installed version number without any errors.

Example:

```text
Python 3.10.x

git version 2.xx.x.windows.x

pip xx.x.x
```

---

## Official Resources

- **Python Downloads:** https://www.python.org/downloads/
- **Git Downloads:** https://git-scm.com/downloads
- **Windows PowerShell Documentation:** https://learn.microsoft.com/powershell/
- **Jupyter Notebook Documentation:** https://jupyter.org/
- **Visual Studio Code:** https://code.visualstudio.com/

---

## Next Step

Continue to **[02_Install_Git.md](02_Install_Git.md)**.
