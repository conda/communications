November 2023 releases are here! Conda 23.11.0, conda-build 3.28.1, and conda-libmamba-solver 23.11.1 are now available on both main and conda-forge. 🎊

The following is just the highlights, for a more in-depth announcement head on over to the [blog post on conda.org](https://conda.org/blog/2023-12-07-november-releases).

We would also like to highlight that the [docs](https://conda.io) have also gotten a little refresh, hopefully making them more approachable and easier to navigate. If you have any feedback, please let us know!

* * *

In the latest release of **conda**, `menuinst v2` support has been added bringing application shortcuts to macOS and Linux (previously only available for Windows). A new health checks plugin hook is also now available allowing `conda doctor` to be extended.

To update conda, run:

```
conda install -n base conda=23.11.0
```

* * *

In the latest version of **conda-build**, efforts are underway to eliminate legacy conda functionality (e.g., replacing `conda.models.dist.Dist` with `conda.models.records.PackageRecord`) and we also fixed `conda_index`'s unnecessarily verbose logging for cleaner build logs.

To update conda-build, run:

```
conda install -n base conda-build=3.28.1
```

* * *

In the latest version of **conda-libmamba-solver**, we added improved support for CTRL-C signal handling and continued to address inconsistencies between the classic and libmamba solvers.

To update conda-libmamba-solver, run:

```
conda install -n base conda-libmamba-solver=23.11.1
```

* * *

Check out the changelogs for [conda 23.11.0](https://github.com/conda/conda/releases/tag/23.11.0), [conda-build 3.28.0](https://github.com/conda/conda-build/releases/tag/3.28.0), [conda-build 3.28.1](https://github.com/conda/conda-build/releases/tag/3.28.1), [conda-libmamba-solver 23.11.0](https://github.com/conda/conda-libmamba-solver/releases/tag/23.11.0), and [conda-libmamba-solver 23.11.1](https://github.com/conda/conda-libmamba-solver/releases/tag/23.11.1) to see what else is new!
