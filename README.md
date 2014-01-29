Sublime Text TXL syntax
=======================

This is a simple syntax highlighter for the [TXL programming language](http://txl.ca). It was designed for Sublime Text 2, but should work for Sublime Text 3.

It supports the entire base TXL language as of version 10.5.

Only basic syntax highlighting is provided. The language is not fully scoped.

##File associations

With this package, Sublime Text will recognize `txl` and `grm` files as having TXL syntax.

##Installation

The easiest way to install is to just copy the `sublime-package` file (bundled with the [releases](https://github.com/MikeHoffert/Sublime-Text-TXL-syntax/releases)) to the `Installed Packages` folder of your personal Sublime Text folder.

For Windows users, that's likely located in `%appdata%\Sublime Text 2`.

Alternatively, you can find it by going to Preferences > Browse Packages, and then going up one folder.

You could also install by copying the `txl.tmLanguage` file into a `Sublime Text 2\Packages\txl` folder (making the `txl` folder).

##Building

The `tmLanguage` file is generated from the `JSON-tmLanguage` file, which requires the [AAAPackageDev](https://github.com/SublimeText/AAAPackageDev) package to create. With the `tmLanguage` file loaded, press `F7` to compile it into the `tmLanguage` file (which is a pList file).
