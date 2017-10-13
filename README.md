# Laakmann fork notes (Oct 2017)

I am forking the [bootstrap theme](https://github.com/drlogout/hugo-bootstrap) with the intention of extending the functionality quite significantly because:

1. I have yet to find a theme for Hugo that does what I want.
2. bootstrap 4 is a decent base from which to build
3. The bootstrap theme appears fairly straight forward (I should be able to modify it with minimal fuss)
4. I can re-use the blog-like layout/features

## Target features

1. Option to browse one or more [sections](https://gohugo.io/content-management/sections/) with a scrollable sidenav.

    + It should also support some level of nesting
    + This should probably be configurable via the config.toml file
    + The [DocDock theme](https://github.com/vjeantet/hugo-theme-docdock) is a decent example of this feature.
    + (The difference is these "doc" themes only support this sort of navigation!)

2. Search

3. Probably some small tweaks that don't come to mind just yet, but mostly just that (I think)

Given the differences in use cases, not to mention my relative inexperience with Hugo and the like, I doubt a pull request will be in order *when* and *if* I finish this, but I'm happy to provide a starting point for others at least!

End of Notes
***



hugo-bootstrap
==============
A theme with bootstrap 4, font-awesome, highlightjs

*NOTE: This theme is copied inspired [Icarus] https://github.com/digitalcraftsman/hugo-icarus-theme
Feel free to make changes and open pull requests.*

You can find a live site using this theme [here](http://mmrath.com/).

## Screenshot

![preview](https://github.com/mmrath/hugo-bootstrap/blob/master/images/screenshot.png)

## Installation

```
$ cd your_site_repo/
$ mkdir themes
$ cd themes
$ git clone https://github.com/mmrath/hugo-bootstrap
```

See the [official Hugo themes documentation](http://gohugo.io/themes/installing) for more info.

## Usage

This theme expects a relatively standard Hugo blog/personal site layout:
```
.
└── content
    ├── post
    |   ├── post1.md
    |   └── post2.md
    ├── page
    |   ├── about-me.md
    |   ├── license.md
    └── other_page.md
```

Just run `hugo --theme=hugo-bootstrap` to generate your site!

## Configuration

Please see the config file of the example site in this repo for details of confguration.

### Hugo

An example of what your site's `config.toml` could look like. All theme-specific parameters are under `[params]` and standard Hugo parameters are used where possible.


## Questions, ideas, bugs, pull requests?

All feedback is welcome! Head over to the [issue tracker](https://github.com/mmrath/hugo-bootstrap/issues).

## License

Open sourced under the [MIT license](https://github.com/enten/hyde-y/blob/master/LICENSE).
