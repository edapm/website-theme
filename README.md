# Etch / Website Theme

This is my [website](https://edwardmason.vercel.app)'s theme, based on [Etch](https://github.com/LukasJoswiak/etch) by [Lukas Joswiak](https://github.com/LukasJoswiak).

Etch is a simple, responsive theme for [Hugo](https://gohugo.io) with a focus on writing. A live demo is available at https://lukasjoswiak.github.io/etch/.

## Features:

* Homepage with list of posts.
* Support for pages.
* Responsive design for optimized mobile experience.
* Syntax highlighting with customizable theme.
* Dark theme which automatically adjusts based on users' setting ([example](https://github.com/LukasJoswiak/etch/wiki/Dark-mode)).
* No external dependencies, no JavaScript, no web fonts.
* Internationalization friendly: use default English translations or create your own

## Installation

To install `etch`, download the repository into the `themes` folder in the root of your site.

```
$ git submodule add https://github.com/edapm/website-theme.git themes/etch
```

Then, use the theme to generate your site.

```
$ hugo server -t etch
```

Use the [sample configuration](https://github.com/LukasJoswiak/etch/wiki/Configuration#sample-configuration) as a starting point. See the [configuration](https://github.com/LukasJoswiak/etch/wiki/Configuration) page for more info.

Read the [wiki](https://github.com/LukasJoswiak/etch/wiki) to learn about more options.
