# 3. Clone the Official QubiC Repositories

## Objective

The QubiC framework consists of multiple repositories, each serving a specific purpose within the quantum control software stack. This section explains how to clone the required repositories and organize them into a single workspace.

---

## Create a Workspace

Open **Windows PowerShell** and create a dedicated workspace to store all QubiC-related repositories.

```powershell
cd D:\

mkdir software

cd software
```

> **Note:** You may choose a different location if preferred. Throughout this guide, `D:\software` is used as the working directory.

---

## Clone the Required Repositories

### 1. QubiC Software

The main software framework for pulse-level programming, experiment compilation, and execution.

```powershell
git clone https://gitlab.com/LBL-QubiC/qubic.git
```

---

### 2. Distributed Processor

Contains the distributed processor implementation used by the QubiC framework.

```powershell
git clone https://gitlab.com/LBL-QubiC/distributed_processor.git
```

---

### 3. QubiC Emulator

Provides a software-based emulator for verifying pulse programs without requiring RFSoC hardware.

```powershell
git clone https://gitlab.com/LBL-QubiC/qubic_emulator.git
```

---

### 4. QubicCali2021a

Contains calibration configurations and resources used by several QubiC tutorials.

```powershell
git clone https://gitlab.com/LBL-QubiC/QubicCali2021a.git
```

---

## Expected Folder Structure

After cloning all repositories, your workspace should look similar to the following:

```text
D:\software
│
├── qubic
├── distributed_processor
├── qubic_emulator
└── QubicCali2021a
```

---

## Repository Summary

| Repository | Purpose |
|------------|---------|
| **qubic** | Main QubiC software framework and tutorial notebooks |
| **distributed_processor** | Distributed processor implementation used by QubiC |
| **qubic_emulator** | Emulator for testing pulse programs without FPGA hardware |
| **QubicCali2021a** | Calibration files and configuration data |

---

## Official Resources

- **QubiC GitLab Repository:** https://gitlab.com/LBL-QubiC
- **QubiC Documentation:** https://lbl-qubic.gitlab.io/
- **QubiC Software Repository:** https://gitlab.com/LBL-QubiC/qubic
- **Distributed Processor:** https://gitlab.com/LBL-QubiC/distributed_processor
- **QubiC Emulator:** https://gitlab.com/LBL-QubiC/qubic_emulator
- **QubicCali2021a:** https://gitlab.com/LBL-QubiC/QubicCali2021a

---

## Next Step

Continue to **[04_Create_Python_Environment.md](04_Create_Python_Environment.md)**.
