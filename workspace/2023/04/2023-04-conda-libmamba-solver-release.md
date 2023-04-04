We're excited to announce the release of conda-libmamba-solver 23.3.0! 🎉

Key highlights of this release:

- Compatible to the [new conda 23.3.x release](https://conda.discourse.group/t/conda-23-3-1-conda-build-3-24-0-releases/241)
- New [conflict reports](https://medium.com/@AntoineProuvost/managing-conflicts-with-mamba-6a5fa10ed6a) inherited from libmamba 1.4.x
- Improved repodata fetching and caching using conda's SubdirData
- Bug fixes for lockfiles, JSON serialization, and API breakage upstream
- Dropped support for Python 3.7, now requiring Python 3.8 or higher

This release brings enhancements in exception parsing and repodata management, while addressing several bug fixes. 
We've also updated our build system and CI environments for better development experience.

A big thank you to all our contributors!

Upgrade to the latest version and enjoy the improvements:

```
conda install -n base --solver=classic conda-libmamba-solver=23.3.0
```
