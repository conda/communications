May 2023 releases are here! Conda 23.5.0, conda-build 3.25.0, and conda-libmamba-solver 23.5.0 are all now available on both main and conda-forge. 🎊

* * *

In **conda**, the [`conda doctor` subcommand plugin](https://github.com/conda-incubator/conda-dot-org/pull/133) has been implemented! The [related conda issue is over nine years old](https://github.com/conda/conda/issues/474) and has been a regularly requested feature. The `conda doctor` command enables conda users to detect any packages with files missing (_i.e._, corrupt packages) in their conda environment.

To update conda, run:

```
conda install -n base conda=23.5.0
```

* * *

In the latest version of **conda-build**, noarch packages that use virtual packages now can have them added to the hash contents of the package. This facilitates the building of noarch packages multiple times for different platforms with platform-specific dependencies. In conda-build 3.25.0, different variants can be built for `__linux`/`__osx`/`__win` and get distinguished, non-clashing package file names.

To update conda-build, run:

```
conda install -n base conda-build=3.25.0
```

* * *

Amongst other improvements and bug fixes, the newest version of **conda-libmamba-solver** provides a `CONDA_LIBMAMBA_SOLVER_NO_CHANNELS_FROM_INSTALLED` environment variable to prevent channels from being injected from installed packages, which is useful for air-gapped environments where outside channels are not available.

To update conda-libmamba-solver, run:

```
conda install -n base conda-libmamba-solver=23.5.0
```

Check out the changelogs for [conda 23.5.0](https://github.com/conda/conda/releases/tag/23.5.0), [conda-build 3.25.0](https://github.com/conda/conda-build/releases/tag/3.25.0), and [conda-libmamba-solver 23.5.0](https://github.com/conda/conda-libmamba-solver/releases/tag/23.5.0) to see what else is new!