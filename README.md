<div align="center">
  <strong>Start your next web extension in seconds.</strong>
  <br /><br />
  <a href="https://github.com/AndersonMamede/web-extension-boilerplate/blob/master/LICENSE">
    <img src="https://img.shields.io/badge/license-MIT%20License-blue.svg" alt="License"/>
  </a>
  <a href="https://github.com/AndersonMamede/web-extension-boilerplate/">
    <img src="https://img.shields.io/badge/dependencies-none-orange.svg" alt="Dependencies"/>
  </a>
  <img src="http://hits.dwyl.io/AndersonMamede/minimalistic-webextension-boilerplate.svg" alt="Hits"/>
</div>

<br />

# Web Extension Boilerplate
A minimalistic template for building web extensions for Chrome and Firefox.

This boilerplate is here to give you a simple starting point for your Chrome/Firefox web extensions projects.

# Installation / Usage

Just clone this repository:

```sh
git clone https://github.com/AndersonMamede/minimalistic-webextension-boilerplate.git
```

... and you have a working web extension.

From there, you should rename the *boilerplate* folder and [configure the manifest.json file](https://developer.mozilla.org/en-US/Add-ons/WebExtensions/manifest.json) (name and description of your project) and you're ready to [develop your web extension](https://developer.mozilla.org/en-US/Add-ons/WebExtensions).

# Structure

The basic structure of the boilerplate project is given in the following way:

```
└── boilerplate/
    ├── img/
    │   ├── icon-16.png
    │   ├── icon-24.png
    │   ├── icon-32.png
    │   ├── icon-48.png
    │   ├── icon-64.png
    │   ├── icon-96.png
    │   └── icon-128.png
    ├── pages/
    │   └── popup/
    │       ├── index.html
    │       └── index.js
    └── manifest.json
```

#### [boilerplate/](boilerplate)

This is where the boilerplate files are stored.

#### [img/](boilerplate/img)

Contains the extension's icons. You can put any other images here.

#### [pages/](boilerplate/pages)

Contains all extension's inner pages and their JS/CSS files: popup page, configuration page, or any other HTML page.

#### [manifest.json](boilerplate/manifest.json)

manifest.json is the main file for an extension and it is where you set all configurations read by the browser (e.g., name, permissions, resources, etc).

> Check [https://developer.mozilla.org/en-US/Add-ons/WebExtensions/manifest.json](https://developer.mozilla.org/en-US/Add-ons/WebExtensions/manifest.json) if you have doubts when configuring manifest.json.

# License

Licensed under the MIT License. Please see [LICENSE](LICENSE) for more information © Anderson Mamede <mamede.anderson@gmail.com>
