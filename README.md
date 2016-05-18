## Primer - Support

[![Build Status](https://travis-ci.org/primer/support.svg?branch=master)](https://travis-ci.org/primer/support)

Support files are Sass variables, mixins, and functions that we import into different bases for use across components, objects, and utilities. Sharing these common properties across GitHub sites helps us to keep our styles more consistent.

Most of the time to include these you'll only need to add `@import "support/support";` to the top of your bundle. If you want only a specific partial you can import them separately.

## Install

Install via `npm install --save primer-support`

## Usage

Once you have the package installed, you can include in your bundle with something like this

```scss
@import "node_modules/primer-support/support";
```

For more info on the available support, visit our [Design systems docs](https://github.com/styleguide/css)

## Related

* [GitHub Design Systems](https://github.com/styleguide)
* [Primer](https://github.com/primer)

## License

MIT &copy; [GitHub](https://github.com/)
