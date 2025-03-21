# Block AI

A browser extension that blocks AI features on websites such as AI-assisted search results and chat.

**Why disable AI features?**

* AI-assisted search results can provide inaccurate, misleading, or outdated information.
* Relying on AI content may discourage deeper analysis and independent research.
* AI features can encourage less private browsing, especially when relying on non-local models.
* AI models often use significantly energy and water than traditional web features.

Block AI puts you in control, letting you decide when AI helps and when it gets in the way.

[Homepage](https://www.jameskerrane.com/block-ai)

## Supported Sites

* Google Search
  * Blocks AI Overview.
* DuckDuckGo
  * Blocks AI Assist.
  * Hides links to Duck.ai on the homepage.

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

Compile an unpacked extension for Chrome and Firefox to the `build/chrome` and `build/firefox` directories:

```sh
npm run build
```

### ✅ Validation

Run automated validation tests (Firefox only):

```sh
npm run lint:firefox
```

### 🚀 Running

Start the extension in development mode:

#### Chrome

```sh
npm run start:chrome
```

#### Firefox

```sh
npm run start:firefox
```

### 📦 Publishing

Build a production-ready version for Firefox:

```sh
npm run publish:firefox
```

## License

This extension is licensed under the MIT License, [which you can read here](LICENSE).

The logo, located in the following directories:

- [`chrome/icons`](chrome/icons)
- [`firefox/icons`](firefox/icons)

is the "Search Off" icon from Material Symbols by Google, which are licensed under the [Apache License, Version 2.0](https://www.apache.org/licenses/LICENSE-2.0.html). The license is distributed alongside the icons in their respective folders and on extension build.
