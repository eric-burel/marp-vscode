# Marp for VS Code

[![CircleCI](https://img.shields.io/circleci/project/github/marp-team/marp-vscode/master.svg?style=flat-square&logo=circleci)](https://circleci.com/gh/marp-team/marp-vscode/)
[![Codecov](https://img.shields.io/codecov/c/github/marp-team/marp-vscode/master.svg?style=flat-square&logo=codecov)](https://codecov.io/gh/marp-team/marp-vscode)
[![Visual Studio Marketplace](https://img.shields.io/visual-studio-marketplace/v/marp-team.marp-vscode.svg?style=flat-square&logo=visual-studio-code&label=VS%20Marketplace)](https://marketplace.visualstudio.com/items?itemName=marp-team.marp-vscode)
[![LICENSE](https://img.shields.io/github/license/marp-team/marp-vscode.svg?style=flat-square)](./LICENSE)

> :information_source: Marp extension requires VS Code >= 1.31 ([January 2019 release](https://code.visualstudio.com/updates/v1_31)) to install.

**Preview [Marp] Markdown slide deck in VS Code.**

We will enhance your VS Code as the slide deck writer. Mark `marp: true`, and write your deck!

<p align="center">
  <img src="https://raw.githubusercontent.com/marp-team/marp-vscode/master/images/screenshot.png" width="800" />
</p>

See the documentation of [Marpit Markdown](https://marpit.marp.app/markdown) and [the features of Marp Core](https://github.com/marp-team/marp-core#features) about how to write.

> Please refer **[https://marp.app/][marp]** for more details of Marp ecosystem. We have powerful tools for Marp Markdown: [Marpit Framework](https://marpit.marp.app/), [CLI tool](https://github.com/marp-team/marp-cli), [Web interface](https://web.marp.app/) and so on.

[marp]: https://marp.app/

## Usage

Marp preview will only be enabled when `marp: true` is written in front-matter.

```markdown
---
marp: true
---

# Your slide deck

Start writing!
```

## Author

Managed by [@marp-team](https://github.com/marp-team).

- <img src="https://github.com/yhatt.png" width="16" height="16"/> Yuki Hattori ([@yhatt](https://github.com/yhatt))

## License

This plugin releases under the [MIT License](LICENSE).
