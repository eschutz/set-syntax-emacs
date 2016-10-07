# Set Syntax (Emacs) package
[![Build Status](https://travis-ci.org/eschutz/set-syntax-emacs.svg?branch=master)](https://travis-ci.org/eschutz/set-syntax-emacs)
[![Build status](https://ci.appveyor.com/api/projects/status/ktkhrs6mplrhui4k/branch/master?svg=true)](https://ci.appveyor.com/project/eschutz/set-syntax-emacs/branch/master)

The Set Syntax (Emacs) package fork of Lee Dohm's ['Set Syntax'](https://github.com/lee-dohm/set-syntax) package, specified for Emacs syntax.

## History
This package was created for use as a command in the [atom-console](https://github.com/eschutz/atom-console) package.

## Key Bindings

As within the original package, there are no key bindings set by default, though you could set keys for specific languages that you use often. For example:

```coffee
'atom-text-editor':
  'alt-cmd-Z': 'set-syntax-emacs:Ruby-mode'
```

## License
This package is available as open source under the terms of the [MIT License](https://opensource.org/licenses/MIT).
