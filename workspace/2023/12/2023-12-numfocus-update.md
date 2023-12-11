## Conda

### Community 

* Subscribe to the new [conda-announce mailing list](https://lists.conda.org/wws/subscribe/announce) to get occasional summaries on the conda ecosystem delivered to your inbox.
* The Mamba project has [bi-weekly community calls](https://hackmd.io/iOgkxNMpTea6lWczjCov9Q?view) on Tuesdays.
* The overall conda community has [bi-weekly calls](https://hackmd.io/@conda-community?tags=%5B%22meeting-notes%22%5D) on Wednesdays. 

**Releases**

* **`conda`** [23.11.0 release](https://conda.org/blog/2023-12-07-november-releases/#changes-in-conda-23110) includes 
  * The speedy `conda-libmamba-solver` as the default dependency solver.  This and other improvements make `conda` run 4-5x faster.
  * Support for plugins, enabling you to customize your conda installation.
  * Package builders can now include desktop icons across all operating systems.
  * The [conda documentation](https://docs.conda.io/en/latest/) has been reorganized and updated.
* [**`pixi`**](https://pixi.sh/) a new open-source conda-compatible package and environment manager led by the folks at prefix.dev. Implemented in Rust, using the recently intoruduced Rattler library as a foundation.  See [the announcement](https://prefix.dev/blog/launching_pixi) for details.
* **`conda-build`** now supports `emscripten-wasm32` and `wasi-wasm32` platforms.
* **`conda-lock`**, **`mamba`**, **`rattler-build`**, **`grayskull`**, **`quetz`**, **`rattler`**, **`condax`** and many other projects had new releases too.

**Newly welcomed projects**

These projects joined the [conda-incubator](https://github.com/conda-incubator):
* [`conda-store`](https://github.com/conda-incubator/conda-auth) and kin support storing, reusing, and sharing conda environments.   
* The [`conda-auth` plugin](https://github.com/conda-incubator/conda-auth) supports authenticated access to private channels in `conda`. (The [plugins repo](https://github.com/conda-incubator/plugins) lists this and other available plugins.)
