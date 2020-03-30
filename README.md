# vuepress-plugin-code-copy

> A vuepress plugin for clipboard-copy

[![npm](https://img.shields.io/npm/v/vuepress-plugin-code-copy.svg)](https://www.npmjs.com/package/vuepress-plugin-code-copy)
[![GitHub stars](https://img.shields.io/github/stars/vxhly/vuepress-plugin-code-copy)](https://github.com/vxhly/vuepress-plugin-code-copy/stargazers)
[![GitHub license](https://img.shields.io/github/license/vxhly/vuepress-plugin-code-copy)](https://github.com/vxhly/vuepress-plugin-code-copy/blob/master/LICENSE)

## Install

``` bash
# install dependencies
npm i vuepress-plugin-code-copy -D

# or use yarn
yarn add vuepress-plugin-code-copy -D
```

## Usage

Write vuepress config

``` javascript
module.exports = {
  plugins: ['code-copy']
}
```

## Options

This plugin supports the following configurations.

``` javascript
module.exports = {
  plugins: ['code-copy', {
    copySelector: ['div[class*="language-"] pre', 'div[class*="aside-code"] aside'], // String or Array
    copyMessage: 'Copy successfully and then paste it for use.', // default is 'Copy successfully and then paste it for use.'
    duration: 300, // prompt message display time.
    showInMobile: false // whether to display on the mobile side, default: false.
  }]
}
```

## License

[MIT](https://github.com/vxhly/vuepress-plugin-code-copy/blob/master/LICENSE).