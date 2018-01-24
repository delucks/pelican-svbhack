# SOLARIZEDHACK

pelican-solarizedhack is a responsive theme for [Pelican](http://getpelican.com), based on svbtle's layout and the solarized color scheme. This was forked from [pelican-svbhack by gfidente](https://github.com/gfidente/pelican-svbhack) and modified to have a different color scheme and arrangement of text that I find aesthetically pleasing.

## FEATURES

- responsive
- syntax highlighting for pre blocks
- supports google analytics
- custom list of links

## KNOWN ISSUES

- no IE testing
- no custom menu

## INSTALL

Clone the [repository](https://github.com/delucks/pelican-solarizedhack), edit your `pelicanconf.py` and modify the `THEME` variable to make it point to the downloaded theme location.

## PELICANCONF.PY

Supports a number of common global variables but patches are welcomed if you need better support.

- `GOOGLE_ANALYTICS` to use Google Analytics, set this var to your UA-XYZ code

- `DISQUS_SITENAME` set this to your Disqus sitename to enable disqus comments in articles

- `TAGLINE` some text rendered right below the logo

When developing locally, you may want to set the following variable: `SITEURL = http://localhost:8000`

## MODIFICATIONS

- Less styling has been removed, modify the css directly to change things around

## AUTHOR

pelican-solarizedhack is authored by Jamie Luck (delucks).

Credit for the original design goes to gfidente. Credit for the solarized dark theme used in code highlights goes to [nicolashery](https://gist.github.com/nicolashery/5765395).

## LICENSE

Released under MIT License, full details in `LICENSE` file.
