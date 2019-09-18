# Multi-Language-Translation-Sketch-Plugin
A Sketch plugin for easy multi-language translation for all your layers, inspired and initially forked from [Hoai Nguyen's Sketch plugin](https://github.com/hoai265/Language-Sketch-Plugin). This plugin has extended symbol support (for symbol with multiply equal instances).

# Support Symbol
 * Override symbol instance content

# Install
 * Download `Multi-Language Translation.sketchplugin` file.
 * Double click or put `Translation.sketchplugin` in Sketch Plugins folder (normally: /Users/<USERNAME>/Library/Application Support/com.bohemiancoding.sketch3/Plugins).

# Usage

## Action `Generate language file`:

* In Sketch: `Plugins` -> `Multi-Language Translation` -> `Generate language file` -> Add your language keys with format: `key1,key2,...,keyn`
* You can open the `.json` file in any Text Editor to edit. The `.json` file is located in the same folder with the `.sketch` file.

## Action `Translate page`:

* In Sketch: `Plugins` > `Multi-Language Translation` -> `Translate page` -> choose the language key

## Action `Selected to language file`:
After generating language file, if you want to add some more text:

* Select all text layer you want to add
* Change your text layers name you want to add with prefix **o_**
* In Sketch : `Plugins` -> `Multi-Language Translation` -> `Selected to language file`
