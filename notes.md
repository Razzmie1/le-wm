# Additional Notes

## Fixing Issues

**Installation on Windows**
- Installation failed initially, so I used the workaround written [here](https://github.com/lucas-maes/le-wm/issues/56)
- In addition the following packages need to be installed: `uv pip install lancedb kornia ipykernel`
- Run `uv run test_imports.py` to check all necessary imports
- Alternatively: Install directly using: `uv pip install -r requirements.txt`

**Conversion of Config and Weights into Checkpoint**
- Conversion failed with README script, so I included the renaming defined [here](https://github.com/lucas-maes/le-wm/pull/73)
- Cleaned a bit the instantiation of config classes using Hydra