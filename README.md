# cookiecutter-def-proj

Project template for data science projects, mainly based on cookiecutter-data-science.

### The resulting directory structure

The directory structure of your new project will look something like this (depending on the settings that you choose):

```
├── LICENSE            # [Optional]
├── Makefile           # Makefile with self commenting commands
├── README.md
├── data               # Data, by default ignored
│   ├── external       # Data from third party sources.
│   ├── interim        # Transformed data
│   ├── processed      # Final model data
│   └── raw            # Immutable data dump, possibly the only subfolder sensible to un-ignore
├── docs               # Documentation
├── notebooks          # Jupyter notebooks, may serve as docs. Usually not production ready code
├── pyproject.toml     # Project configuration file with package metadata for {{ cookiecutter.module_name }} and configuration, e.g., for ruff, pytest
├── references         # Explanatory materials
│   └── figures        # Generated graphics and figures. By default ignored
├── requirements.txt
├── scripts            # Utility scripts
└── src/{{ cookiecutter.module_name }}  # Source code for use in this project
└── tests                # Tests
```
