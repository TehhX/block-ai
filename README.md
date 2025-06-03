# ![Block AI Logo](firefox/icons/ai_off_light.svg) Block AI
<!-- ALL-CONTRIBUTORS-BADGE:START - Do not remove or modify this section -->
[![All Contributors](https://img.shields.io/badge/all_contributors-1-orange.svg?style=flat-square)](#contributors-)
<!-- ALL-CONTRIBUTORS-BADGE:END -->

[<img src=".github/firefox-get-add-on.svg" width="129" height="45">](https://addons.mozilla.org/firefox/addon/block-ai)

A browser extension that blocks AI features on websites such as AI-assisted search results and chat.

**Why disable AI features?**

* AI-assisted search results can provide inaccurate, misleading, or outdated information.
* Relying on AI content may discourage deeper analysis and independent research.
* AI features can encourage less private browsing, especially when relying on non-local models.
* AI models often use significantly energy and water than traditional web features.

Block AI puts you in control, letting you decide when AI helps and when it gets in the way.

## Supported Sites

* Google Search
  * Blocks AI Overview.
* DuckDuckGo
  * Blocks AI Assist.
  * Hides links to Duck.ai on the homepage.
* Amazon
  * Hides AI overview of user reviews.

## Build Instructions

Tested with **Node v22.12.0** (npm v11.2.0).

### Installation

Install all of the dependencies in the project.

```sh
npm install
```

---

### Usage

### 🔨 Build

Compile a packed extension to the `web-ext-artifacts` directory:

```sh
npm run build
```

### ✅ Validation

Run automated validation tests:

```sh
npm run lint
```

### 🚀 Running

Start the extension in development mode:

```sh
npm run start
```

## Contributors

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<table>
  <tbody>
    <tr>
      <td align="center" valign="top" width="14.28%"><a href="https://github.com/TehhX"><img src="https://avatars.githubusercontent.com/u/156055395?v=4?s=100" width="100px;" alt="Sam"/><br /><sub><b>Sam</b></sub></a><br /><a href="https://github.com/thatrobotdev/block-ai/commits?author=TehhX" title="Code">💻</a></td>
    </tr>
  </tbody>
</table>

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

## License

This extension is licensed under the MIT License, [which you can read here](LICENSE).

The logo, located in `src/icons`, is the "Search Off" icon from Material Symbols by Google, which are licensed under the [Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0.html). The license is distributed alongside the icons in their respective folders and on extension build.

The Firefox "Get the add-on" button, located at [`.github/firefox-get-add-on.svg`](.github/firefox-get-add-on.svg), is a branded asset and should be used in accordance with [Mozilla’s Trademark Guidelines](https://www.mozilla.org/en-US/foundation/trademarks/policy/).

Mozilla, Firefox, and the Firefox logo are trademarks of the Mozilla Foundation in the U.S. and other countries. All rights are reserved by their respective authors.
