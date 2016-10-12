GitHub Enterprise Overrides
=============================

This stylesheet overrides GitHub enterprise styles to make it look like public GitHub. There are styles for the header, fonts, and forms (forms are custom, I removed the box-shadow inset and outline).

Depending which version of GitHub Enterprise you're using, you may want to use one or multiple of the provided stylesheets.

## Usage

Copy and paste the styles into your favorite stylesheet overrides browser extension. Stylish is a popular one - here are some links for it:
* Get the [Chrome][1] extension.
* Get the [Safari][2] extension.
* Get the [Firefox][3] addon.

## Updating

If you want to add styles, I recommend modifying the LESS files and then running `npm run compile` to rebuild the CSS. This way you get to use the variables and nesting.

## License

MIT

[1]: https://chrome.google.com/webstore/detail/stylish/fjnbnpbmkenffdnngjfgmeleoegfcffe "Stylish for Chrome"
[2]: http://sobolev.us/stylish/ "Stylish for Safari"
[3]: https://addons.mozilla.org/fr/firefox/addon/stylish/ "Stylish for Firefox"
