# Network energy

## Setup

This is a Jupyter Notebook designed to run with a Python 3.10 kernel.
Dependencies are defined in `requirements.txt` and installed automatically by
the notebook.

### Manual setup

```shell
python3 -m venv .venv
source .venv/bin/activate
pip3 install -r requirements.txt
nbdev_install_hooks
```

## Git hooks

Git hooks from [nbdev](https://nbdev.fast.ai/) are used to clean notebooks
before they're committed. This avoids committing all the metadata that changes
on each run. See the [nbdev Git hooks
docs](https://nbdev.fast.ai/tutorials/git_friendly_jupyter.html) for more
details.

Cleaning the notebook before commit can be done with `nbdev_clean`.
Installing the Git hooks using `nbdev_install_hooks` will do this
automatically on commit.
