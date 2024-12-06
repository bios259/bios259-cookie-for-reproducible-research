## Cookiecutter for Reproducible Research Project
> A boilerplate for starting a computationally reproducible research project.

## Requirements

You need to install `cookiecutter` first:

Using Mamba/Conda:

```bash
mamba install cookiecutter jinja2-time
```

Using PIP:
```bash
pip install cookiecutter jinja2-time
```


## How to usage

To start a new science project:

```bash
cookiecutter gh:bios259/reproducible-cookie
```

## Project folder structure

```bash
project_name/
│
├── bin/                       # Executable scripts and utilities
├── data/                      # Data files
│   ├── raw/                   # Raw, original data
│   └── processed/             # Cleaned and transformed data
├── src/                       # Source code
│   ├── scripts/               # Analysis and utility scripts
│   └── external/              # External scripts
├── environments/              # Environment configuration files
├── notebooks/                 # Jupyter or R Markdown notebooks
├── results/                   # Results of analyses
│   ├── figures/               # Visualizations (e.g., plots, graphs)
│   ├── tables/                # Tabular outputs (e.g., CSV, Excel files)
│   ├── logs/                  # Logs or intermediate textual outputs
│   └── summaries/             # Summary reports (e.g., PDFs, Markdown reports)
├── config/                    # Configuration files (e.g., YAML, JSON), 
├── .gitignore                 # Files and folders to ignore in Git
├── Dockerfile                 # Docker configuration for the environment
├── README.md                  # Overview and usage instructions
├── LICENSE                    # Open source license
```


> This structure is adopted from [Cookiecutter Data Science](https://github.com/drivendata/cookiecutter-data-science) and [Cookiecutter Reproducible Science](https://github.com/mkrapp/cookiecutter-reproducible-science)
