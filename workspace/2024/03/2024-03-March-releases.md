March releases are here! Conda 24.3.0 and conda-build 24.3.0 are now available on both `main` and `conda-forge`. 🎉

* * *

To update conda, run:

```
conda install -n base conda=24.3.0
```

The March release of **conda** implements new features such as a plugin hook that gives plugin authors the ability to define new settings, an updated `conda.gateways.subprocess.subprocess_call` function that uses `text=True` to avoid manual encoding/decoding, optimized module imports to speed up `conda activate`, and more.

* * *

To update conda-build, run:

```
conda install -n base conda-build=24.3.0
```

This new version of **conda-build** adds compatibility for `LIEF=0.14`, as well as a check to print an additional warning and return an empty string when bits is "arm64" in `msvc_env_cmd`.


Check out conda's changelogs for [24.3.0](https://github.com/conda/conda/releases/tag/24.3.0) and conda-build's changelog for [24.3.0](https://github.com/conda/conda-build/releases/tag/24.3.0) to see what else is new!
