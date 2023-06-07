# Meta!

**Summary**

Conda project news for the June NumFOCUS newsletter

**Where**:

Sent directly to Arliss at NumFOCUS and then appear in the April newsletter. There is no formatting requirement for bullet lists, bolding, etc.  So go with whatever looks good.

**When**: 2023/06/09

The summary itself is in an HTML comment, so as to avoid indexing.

# Content

## Conda

**Community events**

* The Mamba project has [bi-weekly community calls](https://hackmd.io/iOgkxNMpTea6lWczjCov9Q?view) on Tuesdays.
* The overall conda community has [bi-weekly calls](https://hackmd.io/@conda-community?tags=%5B%22meeting-notes%22%5D) on Wednesdays.
* [PackagingCon 2023](https://packaging-con.org/) will be Octover 26-28 in Berlin.

**Conda on the web**

* **[conda.org](https://conda.org/), the conda community website, [has been launched](https://conda.org/blog/2022-04-27-welcome-to-conda-dot-org)!**
* [The sleight-of-hand trick that can simplify scientific computing](https://www.nature.com/articles/d41586-023-01469-0, ), *Nature* post by Jeffrey M. Perkel.
* Two conda-centric presentations from PyCon US 2023 are now avaialble:
    * [Publishing your Python project, the conda way](https://youtu.be/NSgTFf40vHQ)
    * [Plug life into your codebase: Making established Python codebase pluggable](https://youtu.be/OeSv0_HesaU)
* [How to use conda-build to build a Python package with C/C++ dependencies](https://conda.org/blog/2023-05-18-how-to-use-conda-build), blog post by Vasvi Sood
* [How we reduced conda's index fetch bandwidth by 99%](https://conda.org/blog/2023-05-05-how-we-reduced-the-conda-index-fetch-bandwidth), blog post by Daniel Holth

**Releases and announcements**

* [**rattler-build**](https://prefix.dev/blog/the_new_rattler_build) - a new rewrite of the core concepts of conda-build in *Rust*.
* **[conda-lock 2.0.0](https://github.com/conda/conda-lock/releases/tag/v2.0.0)** - a lightweight library for generating fully reproducible lock files for conda environments.
* **[conda 23.5.0](https://conda.org/blog/2023-05-31-may-2023-releases#changes-in-conda)** - Python 3.11 support and the new [**conda doctor** subcommand plugin](https://conda.org/blog/2023-06-01-conda-doctor) for detecting corrupted installs.
* **[conda-build 3.25.0](https://conda.org/blog/2023-05-31-may-2023-releases#changes-in-conda-build)** - an update to `conda`'s package builder.
* **[conda-libmamba-solver 23.5.0](https://conda.org/blog/2023-05-31-may-2023-releases#changes-in-conda-libmamba-solver)** - An update to the fast `libmamba` solver in `conda`.
* **[grayskull 2.3.1](https://github.com/conda/grayskull/releases/tag/v2.3.1)** - An automatic recipe generator for the conda ecosystem.
* **[Prefix.dev Channels](https://prefix.dev/blog/introducing_channels)** - A new option for creating your own conda channels
