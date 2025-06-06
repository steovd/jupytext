# 1.4.4 (2025-04-05)

The context menu has a "New Text Notebook" entry. Thanks to [Mahendra Paipuri](https://github.com/mahendrapaipuri) for this PR ([#1365](https://github.com/mwouts/jupytext/pull/1365))!

We have updated the JupyterLab extension dependencies ([#1300](https://github.com/mwouts/jupytext/pull/1300), [#1355](https://github.com/mwouts/jupytext/pull/1355), [#1360](https://github.com/mwouts/jupytext/pull/1360)). Thanks to [Mahendra Paipuri](https://github.com/mahendrapaipuri) for these PRs!

The dependencies of the JupyterLab extension were updated to address [security issues](https://github.com/mwouts/jupytext/security/dependabot):

- [#1272](https://github.com/mwouts/jupytext/issues/1272)
- [#1273](https://github.com/mwouts/jupytext/issues/1273)
- [#1280](https://github.com/mwouts/jupytext/issues/1280)
- [#1285](https://github.com/mwouts/jupytext/issues/1285)
- [#1290](https://github.com/mwouts/jupytext/issues/1290)
- [#1304](https://github.com/mwouts/jupytext/pull/1304)

# 1.4.3 (2024-05-05)

- JupyterLab's dependency `ejs` was updated from 3.1.9 to 3.1.10 ([#1231](https://github.com/mwouts/jupytext/issues/1231))
- JupyterLab's dependency `follow-redirects` was updated from 1.15.4 to 1.15.6 ([#1218](https://github.com/mwouts/jupytext/issues/1218))
- JupyterLab's dependency `ip` was updated from 2.0.0 to 2.0.1 ([#1216](https://github.com/mwouts/jupytext/issues/1216))

# 1.4.2 (2024-01-13)

- Fixed an issue about unpairing notebooks from the Jupytext Menu ([#1197](https://github.com/mwouts/jupytext/issues/1197))
- JupyterLab's dependency `follow-redirects` was updated from 1.15.3 to 1.15.4 ([#1203](https://github.com/mwouts/jupytext/issues/1203))

# 1.4.1 (2023-11-27)

- The Jupytext Menu is back! And text notebooks can be created directly from the launcher. This is an outstanding contribution by [Mahendra Paipuri](https://github.com/mahendrapaipuri) ([#1154](https://github.com/mwouts/jupytext/issues/1154), [#1163](https://github.com/mwouts/jupytext/issues/1163)). This requires JupyterLab 4.x or Jupyter Notebook 7.x.

# 1.4.0 (2023-10-22)

- This version of the JupyterLab extension is fully compatible with (and requires) JupyterLab 4.x.

# 1.3.11 (2023-10-22)

- This version is the same as 1.3.10. It was re-published to include the README that was missing in 1.3.10.

# 1.3.10 (2023-10-22)

- The server extension for `jupytext` has been moved from core Jupytext to the (Python) `jupyterlab-jupytext` extension.
- The Jupyter Lab extension is now compatible with the [JupyterLab RISE](https://github.com/jupyterlab-contrib/rise) extension. Many thanks to [Frédéric Collonval](https://github.com/fcollonval) for his PR ([#1126](https://github.com/mwouts/jupytext/pull/1126))!
- This version of the JupyterLab extension is compatible with JupyterLab 4.x. Many thanks to [Thierry Parmentelat](https://github.com/parmentelat) for his PRs! ([#1092](https://github.com/mwouts/jupytext/pull/1092), [#1109](https://github.com/mwouts/jupytext/pull/1109))

# 1.3.9 (2022-06-02)

- We updated the `yarn.lock` file for the jupyter lab extension to address security vulnerabilities ([#904](https://github.com/mwouts/jupytext/issues/904), [#925](https://github.com/mwouts/jupytext/issues/925), [#935](https://github.com/mwouts/jupytext/issues/935), [#939](https://github.com/mwouts/jupytext/issues/939), [#984](https://github.com/mwouts/jupytext/issues/984), [#1005](https://github.com/mwouts/jupytext/issues/1005), [#1011](https://github.com/mwouts/jupytext/issues/1011), [#1030](https://github.com/mwouts/jupytext/issues/1030), [#1036](https://github.com/mwouts/jupytext/issues/1036), [#1052](https://github.com/mwouts/jupytext/pull/1052))
- This version is the last version that is compatible with `jupyterlab==3.x`.

# 1.3.8 (2021-12-03)

- The "Jupytext Notebook" factory that lets the user configure the Notebook viewer as the default for text notebooks accepts more filetypes: "myst", "r-markdown" and "quarto" ([#803](https://github.com/mwouts/jupytext/issues/803))

# 1.3.7 (2021-11-30)

The extension for Jupyter Lab benefited from a series of improvements contributed by [Frédéric Collonval](https://github.com/fcollonval):

- A new "Jupytext Notebook" factory offers the option to open text notebooks directly with the notebook view (#803). To use it, follow the instructions in the [documentation](https://github.com/mwouts/jupytext/blob/main/docs/index.md#Install).
- The ICommandPalette is optional, for compatibility with RISE within JupyterLab [RISE#605](https://github.com/damianavila/RISE/pull/605)
- Added support for translation.

We also upgraded the extension dependency and especially `json-schema` to address a security vulnerability.

# 1.3.6 (2021-09-23)

- We have upgraded the extension dependencies and especially `ansi-regex` to fix a security vulnerability (#857)

# 1.3.5 (2021-09-05)

- The extension can pair notebooks with `.qmd` files (Quarto format) (#837)

# 1.3.4 (2021-08-31)

- We have upgraded the extension dependencies and especially `tar` and `url-parse` to fix two security vulnerabilities (#842) (#843)

# 1.3.3 (2021-06-10)

- We have upgraded the extension dependencies and especially `ws` to fix a security vulnerability (#798)

# 1.3.2 (2021-05-21)

- We have upgraded the extension dependencies and especially `hosted-git-info` to fix a security vulnerability (#783)

# 1.3.1 (2021-03-07)

- We have updated `yarn.lock` to upgrade `marked` to `2.0` and fix a moderate vulnerability in the extension dependencies (#750)

# 1.3.0 (2021-01-05)

- The `jupyterlab-jupytext` extension is now distributed using `jupyter-packaging`, thanks to Martin Renou's awesome contribution (#683).

# 1.2.3 (2020-10-14)

- Remove duplicate `jupyterlab` entry in `package.json` (#654)

# 1.2.2 (2020-10-13)

- The description of the `jupyterlab-jupytext` extension was updated (#654)
- The explicit dependency on the `jupytext` Python package was documented in `package.json` (#654)

# 1.2.1 (2020-03-18)

- The extension can pair a notebook to the new MyST Markdown format, developed by the [ExecutableBookProject](https://github.com/ExecutableBookProject) team. Thanks to Chris Sewell for his PRs! (#447 #456 #458)

# 1.2.0 (2020-03-09)

- This version of the extension is compatible with JupyterLab 2.0. Many thanks to Jean Helie! (#449)

# 1.1.1 (2019-12-26)

- The `nomarker` format is available through the Jupytext commands (requires `jupytext>=1.3.1`).

# 1.1.0 (2019-11-03)

- Multiple pairings are supported (#290)
- The documentation includes the last version numbers for both Jupytext Python and for this extension (#311)
- Documentation says clearly that the extension is bundled with the Python package (#350)

# 1.0.2 (2019-07-18)

- Fixed an incorrect `target_format` entry inserted by the version 1.0.1 of the extension.

# 1.0.1 (2019-07-18)

- A click on a selected format toggle the pairing (#289)
- Use `JupyterFrontEnd` and `JupyterFrontEndPlugin` from `@jupyterlab/application` rather than `JupyterLab` and `JupyterLabPlugin` for compatibility with JupyterLab 1.0.

# 1.0.0 (2019-07-06)

- First extension compatible with JupyterLab 1.0

# 0.19.0 (2019-07-06)

- Last extension compatible with JupyterLab 0.35

# 0.1.0 (2018-10-02)

- Initial release of the extension
