# 6. Run Jupyter Notebook

## Objective

The official **LBL QubiC** tutorials are provided as Jupyter Notebooks. This section explains how to launch Jupyter Notebook and access the tutorial notebooks after setting up the Python environment.

---

## Activate the Virtual Environment

Before launching Jupyter Notebook, activate the Python virtual environment.

```powershell
qubic_env\Scripts\activate
```

The PowerShell prompt should change to:

```text
(qubic_env) PS D:\software>
```

---

## Launch Jupyter Notebook

Start Jupyter Notebook by running:

```powershell
jupyter notebook
```

---

## Expected Output

A browser window should open automatically and display the Jupyter Notebook dashboard.

If the browser does not open automatically, copy and paste the URL displayed in the PowerShell window into your web browser.

Example:

```text
http://localhost:8888/tree
```

---

## Open the QubiC Tutorial Notebooks

Using the Jupyter dashboard, navigate to the directory containing the official QubiC tutorial notebooks.

For example:

```text
qubic/
└── tutorials/
```

Select the notebook you want to study and open it.

---

## Execute the Notebook

Run the notebook cells **sequentially from top to bottom**.

This ensures that:

- Required Python modules are imported.
- Configuration files are loaded correctly.
- Variables are initialized in the proper order.
- The notebook executes without dependency errors.

---

## Official Resources

- **Project Jupyter:** https://jupyter.org/
- **Jupyter Notebook Documentation:** https://docs.jupyter.org/
- **QubiC Documentation:** https://lbl-qubic.gitlab.io/

---

## Next Step

Continue to **[07_Verify_Installation.md](07_Verify_Installation.md)** to verify that the QubiC software environment has been configured successfully.
