hi-hspec
=================

A template for [hi](https://github.com/fujimura/hi).

example:

```
$ hi -m Foo.Bar -p foo-bar  -r git@github.com:fujimura/hi-hspec.git
$ tree
.
├── ChangeLog.md
├── LICENSE
├── README.md
├── foo-bar.cabal
├── src
│   └── Main.hs
│   └── Foo
│       ├── Bar
│       │   └── Internal.hs
│       └── Bar.hs
└── test
    ├── Foo
    │   └── BarSpec.hs
    └── Spec.hs

5 directories, 8 files
```

Copyright 2013-2014 Fujimura Daisuke, under the MIT license.
