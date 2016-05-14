# Grayscale Games - ESLint Shareable Config

#### An ESLint [Shareable Config](http://eslint.org/docs/developer-guide/shareable-configs) for Grayscale Games

## Install

```bash
npm install eslint-config-gg
```

## Usage

Shareable configs are designed to work with the `extends` feature of `.eslintrc.json` files.
You can learn more about
[Shareable Configs](http://eslint.org/docs/developer-guide/shareable-configs) on the
official ESLint website.

To use the Grayscale Games shareable config, first run this:

```bash
npm install --save-dev eslint eslint-config-gg
npm install --save-dev eslint-plugin-standard eslint-plugin-promise
```

Then, add this to your `.eslintrc.json` file:

```
{
  "extends": "gg"
}
```

*Note: We omitted the `eslint-config-` prefix since it is automatically assumed by ESLint.*

You can override settings from the shareable config by adding them directly into your
`.eslintrc.json` file.
