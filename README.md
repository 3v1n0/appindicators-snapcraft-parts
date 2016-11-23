# AppIndicators snapcraft parts
Parts for creating app-indicators snaps with [snapcraft](https://github.com/ubuntu-core/snapcraft/).

Parts to show app-indicators for gtk2, gtk3, qt4 and qt5.

Usage:

1. add `after: [indicator-<technology>]` to your part:
  - `gtk2`, `gtk3`, `qt4` and `qt5` corresponds to their respective toolkit.
2. add 'unity7' plug to your application

Read more about the [snap parts ecosystem](http://blog.sergiusens.org/posts/The-Snapcraft-Parts-Ecosystem/).
