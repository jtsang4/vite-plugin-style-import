# @jtsang/vite-plugin-style-import

This package is a fork release of [vite-plugin-style-import](https://www.npmjs.com/package/vite-plugin-style-import), some issues listed below got fixed in this package. When the source package fixes these issues, it is recommended to use source package.

Fixed issues:

- Wrong dependency to `"console"`, it should be `"consola"`
- Source package could not handle the as alias with non-alphanumeric characters
