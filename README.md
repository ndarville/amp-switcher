AMP Switcher ![Project version][] ![Travis build status][]
============
This extension detects whether a page has an [AMP version][] and lets users swap between the AMP and non-AMP version of the page.

In the future, I might add a settings feature for default both default and per-site preferences.

Why this extension?
-------------------
Because there is no official feature nor extension for Chrome that does this basic thing.

What happens then is users end up installing the first third-party extension they find.

Since an AMP extension requires permission to view all the sites you visit, you will, at minimum, tell a third-party extension your entire browser history. Furthermore, you have no way of actually knowing what the extension does as all the most popular extensions aren’t open source.

**Ideally**, you want a first-party extension for this. **Alternatively**, you want an extension you don’t have to trust to do the right thing because it’s open source. **Otherwise**, *don’t install the extension*.

This extension is on GitHub and will soon be in the Chrome Web Store, but you can also download a local version and load it in Chrome if you want. Or fork it and make your own adjustments.


[project version]: https://img.shields.io/github/release/ndarville/amp-switcher.svg
[travis build status]: https://travis-ci.org/ndarville/amp-switcher.svg?branch=master
[amp version]: https://www.ampproject.org/docs/guides/discovery
