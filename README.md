# babel-core-5-patched

This repository adds a try/catch to the `var $defineProperty = function defineProperty(it, key, D){` declaration, since
this was causing a fatal error on IE11 with "TypeError: Cannot redefine non-configurable property 'startsWith'".
