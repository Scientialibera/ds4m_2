# DS4M 2

Notebook-based data science repository with project data under `data/` and the main workflow in `notebooks/orchestration.ipynb`.

## Repository structure

```text
data/                       # analysis inputs and derived data
notebooks/
  orchestration.ipynb       # main notebook workflow
```

## Execution

Run `notebooks/orchestration.ipynb` in JupyterLab, Jupyter Notebook or a compatible notebook environment. The repository does not include a dependency manifest, so the Python environment must supply the packages imported by the notebook.

For reproducible reruns, record the source-data version, Python version and installed package versions alongside any new results. Keep generated notebook checkpoints and local environment files outside version control.

## Scope

The repository contains a notebook workflow rather than a packaged Python application. There is no documented service interface, deployment target or standalone command-line entry point on `main`.