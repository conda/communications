July 2023 releases are here! Conda 23.7.1 and conda-build 3.26.0 are now available on both main and conda-forge. 🎊

* * *

In the latest release of **conda**, [new pre- and post-command plugin hooks](link to blogpost) that allow you to run your code before or after a conda subcommand are now available, along with a much improved subcommand plugin hook and plugin infrastructure. There is also a new health check for `conda doctor` that detects altered packages in an environment by comparing expected and computed sha256 checksums, as well as a much-expanded API and command docs ([`conda env`](https://docs.conda.io/projects/conda/en/23.7.x/commands/env/index.html)!).

To update conda, run:

```
conda install -n base conda=23.7.1
```

* * *

In the latest version of **conda-build**, `extra-meta` data is logged to make it easier to verify that the right extra-meta data is burned into packages (which also helps to co-relate packages and their build-log). The feature was first introduced in [conda-build#4303](https://github.com/conda/conda-build/pull/4303) and is now improved via the logging call.

To update conda-build, run:

```
conda install -n base conda-build=3.26.0
```

* * *

Check out the changelogs for [conda 23.7.0](https://github.com/conda/conda/releases/tag/23.7.0), [conda 23.7.1](https://github.com/conda/conda/releases/tag/23.7.1), and [conda-build 3.26.0](https://github.com/conda/conda-build/releases/tag/3.26.0) to see what else is new!
