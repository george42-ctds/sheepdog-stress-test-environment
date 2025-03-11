# sheepdog stress test

Sets up an environment for running a jupyer lab notebook for sheepdog submissions.
The notebook runs the Gen3 Expansion module.

## Installation

Clone this repo or pull in the `pyproject.toml` and `poetry.lock` files.

You can pull in the `expansion.py` module from [here](https://github.com/cgmeyer/gen3sdk-python) or run the notebook cell with the
`wget` command.

Create a virtual environment running python 3.9 and enter the environment.

Build the environment with poetry.

```
poetry install
```

Create a kernel, say `python-stress-env`, for the notebook

```
python -m ipykernel --user --name python-stress-env
```

Select this kernel when you start the notebook.
The dependencies should be available for the
import statements in the first few cells.




