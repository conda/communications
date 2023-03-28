March releases are here! Both conda 23.3.0 and conda-build 3.24.0 are now available on both main and conda-forge:

To update conda run:

```
conda install -n base conda=23.3.0
```

To update conda-build run:

```
conda install -n base conda-build=3.24.0
```

Both conda and conda-build have dropped Python 3.7 support and efforts are underway to add Python 3.11 support for the May release. Conda and conda-build continue to deprecate and remove old, unused, and outdated code (e.g. conda-build drops `conda <4.13` logic).

Conda adds improved error messages for environment creation via `conda env create`, introduces new configuration parameters, adds 64-bit RISC-V architecture compatibility, enhances code coverage, and adds experimental support for faster `repodata.json` parsing via incremental fetching.

Conda-build addresses a Git LFS failure, reduces false-positives when detecting Perl modules in `conda skeleton cpan`, and starts to address a `subdir` issue with testing downstream packages.

Checkout [conda's changelog](https://github.com/conda/conda/releases/tag/23.3.0) and [conda-build's changelog](https://github.com/conda/conda-build/releases/tag/3.24.0) for a complete list of improvements.

Snake away!
