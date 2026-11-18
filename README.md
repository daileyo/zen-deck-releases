# Zen Deck releases

Release builds of the Zen Deck browser extension for the [Zen browser](https://zen-browser.app).

Zen checks `updates.json` in this repo and installs new versions automatically. To install for the first time, download the latest `.xpi` from [Releases](https://github.com/daileyo/zen-deck-releases/releases).

The extension is unsigned and uses an experiment API, so Zen needs two settings in `about:config` first:

- `xpinstall.signatures.required` set to `false`
- `extensions.experiments.enabled` set to `true`
