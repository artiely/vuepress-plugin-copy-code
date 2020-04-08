# vuepress-plugin-copy-code

> A vuepress plugin for clipboard-copy

## Install

``` bash
# install dependencies
npm i vuepress-plugin-copy-code -D

# or use yarn
yarn add vuepress-plugin-copy-code -D
```

## Usage

Write vuepress config

``` javascript
module.exports = {
  plugins: ['copy-code']
}
```

## Options

This plugin supports the following configurations.

``` javascript
module.exports = {
  plugins: ['copy-code', {
    copySelector: ['div[class*="language-"] pre', 'div[class*="aside-code"] aside'], // String or Array
    copyMessage: 'Copy successfully and then paste it for use.', // default is 'Copy successfully and then paste it for use.'
    duration: 300, // prompt message display time.
    showInMobile: false // whether to display on the mobile side, default: false.
  }]
}
```
## demo
[https://artiely.gitee.io](https://artiely.gitee.io)
## License

[MIT](https://github.com/vxhly/vuepress-plugin-copy-code/blob/master/LICENSE).
