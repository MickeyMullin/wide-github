# Wide GitHub

This plugin changes all GitHub repository pages to be full width and dynamically sized. Gists are supported as of version 1.1.0.

This fork adds my company's Enterprise GitHub URL to the manifest. I do not guarantee that it will remain contains the latest version from the original repository.

## Installing

### Stylus / UserCSS

This style can be installed into Stylus ([Firefox addon](https://addons.mozilla.org/en-US/firefox/addon/styl-us/)/[Chrome extension](https://chrome.google.com/webstore/detail/stylus/clngdbkpkpeebahjckkjfobafhncgmne)): [wide-github.user.css](https://raw.githubusercontent.com/MickeyMullin/wide-github/master/build/wide-github.user.css)

### Greasemonkey / Tampermonkey / UserScript

This script can be installed into the [Greasemonkey Firefox addon](https://addons.mozilla.org/en-US/firefox/addon/greasemonkey/), the [Tampermonkey Chrome extension](https://chrome.google.com/webstore/detail/tampermonkey/dhdgffkkebhmkfjojejmpbldmpobfkfo), or other user script plugins: [wide-github.user.js](https://raw.githubusercontent.com/MickeyMullin/wide-github/master/build/wide-github.user.js).

### Stand-alone Chrome Extension

1. Download the [pre-built Extension](https://github.com/MickeyMullin/wide-github/raw/master/build/wide-github.zip) (or clone this repo and run `make chrome` from repository root to locally build zip file of Chrome extension)
2. Unzip generated zip file
3. Within the [Extensions settings page](chrome://extensions/), ensure "Developer mode" (top right) is enabled
4. Click "Load unpacked" and browse to directory created in step (2) from unzipping built extension

### Wide-GitHub

This is forked from [xthexder/wide-github](https://github.com/xthexder/wide-github/) in order to add Verizon Media's Enterprise GitHub URL to the sites affected.

## Development

After cloning locally:

* to generate the `user.js` for Greasemonkey, run `make js`
* `user.css` can be built using `make css`
* the chrome extension can be built using `make chrome`

## Firefox Addon

There is also a stand-alone [Firefox addon](https://addons.mozilla.org/en-US/firefox/addon/widegithub/), but the [addon repository](https://github.com/fabiocchetti/widegithub) would have to be forked and the GitHub Enterprise domain added in order for it to work for an Enterprise GitHub server.
