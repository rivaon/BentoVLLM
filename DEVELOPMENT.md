- Check [configuration files](/.github/tools/config.yaml) for adding new models structure. You can copy the existing sets and then modify accordingly to the model specification
  - [`generate.py`](/.github/tools/generate.py) will then use the templates [source](/.github/src) to build a new folder for said models.
- Run `uv run .github/tools/generate.py`.
- Create a PR to [nightly](https://github.com/bentoml/BentoVLLM/tree/nightly)
