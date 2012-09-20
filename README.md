This is a fully responsive theme for ruhoh. It is built on top of
[Twitter Bootstrap](http://twitter.github.com/bootstrap/).

Compatible with ruhohSpec (Directory API) v1.0

<http://ruhoh.com> for more information.

![Screenshot](https://raw.github.com/dhulihan/hooligan/master/screenshot.png)

(The screenshot lies! Go to http://nserror.me/ for what's probably a
reasonably up to date rendering of what this theme code will do to your
browser).

## Installation

`git clone` or download the hooligan folder into your themes directory
in the root of your blog.

in `config.yml`

    theme: "hooligan"
    
Then reload your development environment to see the changes.

## Modifications made by NSError

* The font size has been tweaked to be responsive, and slightly smaller
  on mobile form factors. This aids in readability.
* The theme has been tweaked for use with the
  [Highlight.js][highlightjs-plugin] plugin.
* The theme has been tweaked for use with the [MathJax][mathjax-plugin]
  plugin.
* The theme has been tweaked for use with the
  [Hyphenate.js][hyphenatejs-plugin] plugin.
* The header and footer has been modified to look more betterer. The
  footer in particular has been tweaked to be more grammatically correct.
* The theme kind of assumes that you use Feedburner to serve up your RSS
  feed. Your normally RSS will still be there, but the autodiscovery
  tools (meta tag, etc) are expecting to be activated only on presence
  of a feedburner variable in your site config.
* The theme has been updated to use Twitter Bootstrap 2.1.1 and jQuery
  1.8.1. They're much nicer, don't you think?

## Other interesting forks

I've found that watching the changes and modifications at
[davedoesdev][davedoesdev-hooligan] has been very enlightening in the
direction I want to take my fork.

[highlightjs-plugin]: https://github.com/NSError/ruhoh-highlightjs
[mathjax-plugin]: https://github.com/NSError/ruhoh-mathjax
[hyphenatejs-plugin]: https://github.com/NSError/ruhoh-hyphenator
[davedoesdev]: https://github.com/davedoesdev/hooligan

