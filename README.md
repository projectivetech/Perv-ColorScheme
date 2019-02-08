# (DEPRECATED) Perv Color Schemes #

## Note ##

> **This version is DEPRECATED! The new version, rewritten from scratch, is available at [Color Scheme - Perv](https://github.com/micck/perv-colorscheme). This version is kept in the last state, as the new one does look a bit different. Also, if you have Sublime Text with a version <=3149, please keep this version.**

-----------------

> "**Actually, as a native from Perv, I prefer to be called a '_Pervect_'**" <_Aahz:japanese_ogre: in [Myth Directions][01]_>

[![release badge]][release] [![sublime text badge]][sublime-text] [![Package Control](https://packagecontrol.herokuapp.com/downloads/Perv%20-%20Color%20Scheme.svg?color=50C32E)](https://packagecontrol.io/packages/Perv%20-%20Color%20Scheme) [![licence badge]][licence] [![stars badge]][repo] [![issues badge]][issues]

## Introduction ##

This colour schemes are created with two goals in mind: covering as many syntax (highlighters) as possible and using logical and consistent colour palette(s) (throughout all different syntax).

This project started a couple of years back, when there were nearly to none colour schemes, which covered the syntax I was interested in (`Markdown`, `ReStructuredText`, `Ruby`, `JSON`, `XML`).  Heck, the majority of the available colour schemes back then, even didn't highlight the settings (`JSON`) or tmTheme files (`XML`).

Currently the scheme(s) supports the following syntax highlighters and packages (please, check the [Update](#update-history) section for more details about new additions and changes):

|         Syntax        |                                    Package                                    |         Syntax        |           Package            |
| --------------------: | :---------------------------------------------------------------------------- | --------------------: | :--------------------------- |
|     `Markdown`, `GFM` | [Markdown Editing][12] (recommended), [knockdown][11], Default                |    `reStructuredText` | Default, [ReST extended][13] |
| `CSS`, `SCSS`, `SASS` | Default, [SCSS][15], [Syntax Highlighting for SASS][16], [SASS][17]           |        `JSON`, `YAML` | Default                      |
|         `Ruby`, `ERB` | Default                                                                       |              `Python` | Default                      |
|         `Git`, `Diff` | [Git][20], [Sublime Git][21], [Git Gutter][22], [SubliMerge Pro][23], Default |              `Linter` | [Sublime Linter][24]         |
|              `BBCode` | [BBCode][30]                                                                  |               `C/C++` | Default                      |
|              `Config` | [Generic Config][26], [Dotfile][27], [nginx][28]                              | `Bracket Highlighter` | [Bracket Highlighter][29]    |

## The Perv Color Schemes ##

### Perv Orange :tangerine: Family ###

The colours are grouped together based on scopes:

- **Comments & Selections**: Grey
- **Classes & Objects**: Variations of Blue
- **Functions**: Variations of Red
- **Keywords & Tags**: Variations of Orange
- **Storages**: Variations of Yellow
- **Strings & Constants**: Variations of green

#### Perv Orange ####

Dark and retro:
![Perv Orange][img1]

#### Perv Orange Moonlight ####

With a darker background and a higher contrast:
![Perv Orange Moonlight][img2]

The screenshots were made with [Soda Theme][50] installed--nice addition to the _Color Schemes - Perv_.

## Advanced usage ##

There are so many different personal tastes that it is nearly impossible to make one colour scheme, which satisfies even those guys, who's colour taste is the same.  Some guys don't like _italics_ or **bold** font faces, other's dislike the selection colour.  You can edit the colour scheme to fit your personal taste.

> **Note:** As of [Sublime Text 3][52] packages are normally installed as an archive with the suffix `.sublime-package`, the below changes cannot be done directly.  You either need to install the package through `Add Repository` in [Package Control][53], by using Git to clone the repository or by extracting the archive.

In order to edit the specific scheme file, you want to amend, please select the `Preferences -> Browse Packages` menu entry in [Sublime Text][51].  That will open the packages directory either in the "Finder" (on Mac OS X), "_flavoured_ file explorer" (on Linux) or in "Explorer" (on Windows).  Go into the "Color Schemes - Perv" directory and drag'n'drop the colour scheme file, which you would like to use, to your [Sublime Text][51] editor.  After the file is loaded, do the following depending on the desired change:

- *Switch of italic or bold font faces*: search for either "italic" or "bold" in the file.  Just comment the line you find, rinse and repeat for all font faces you want to remove.
- *Change the gutter and line highlight colour*: search for "lineHighlight" and either change the colour value to one to your liking or use one of the available presets.

> **Hint:** as you're already using [Sublime Text][51]--commenting and uncommenting is as easy as a key-press: Mac: <kbd>&#x2318;</kbd>+<kbd>/</kbd> and for the PCs: <kbd>CTRL</kbd>+<kbd>/</kbd>)

## Installation ##

### Sublime Text ###

For the [Sublime Text][51] editor the schemes can be installed easily using [Package Control][53] and searching for the `Color Schemes - Perv` package in the official repository.

Otherwise, first you need to locate your [Sublime Text][51] packages directory--use the `Preferences -> Browse Packages` menu from within [Sublime Text][51], if you don't know where the directory is located.

Now either create a `Color Schemes - Perv` folder within this directory, and copy the contents of the GitHub repository, or clone the repository using the Git software within the packages directory:

    git clone https://github.com/FlavourSys/Perv-ColorScheme "Color Schemes - Perv"

Now simply use the `"Color Scheme" -> "Color Schemes - Perv" -> "Perv YOUR FLAVOUR"` option of your preferences menu to switch between the schemes & enjoy!

## Update history ##

> **This is the last version before the rewrite. Please look at [Color Scheme - Perv](https://github.com/micck/perv-colorscheme) for future versions.**

### Version 1.4 ###

- _major change:_ complete overhaul of the `Markdown (&amp; GFM)` syntax highlighting.  I added support for [Markdown Editing][12] including: background colour for inline code, fenced code and block quotes; striped a lot of colours (e. g. all header texts and link texts are white now); added support for ~~strike-through~~ (as there is no underline or strike-through font style in [Sublime Text][51]--it is a text editor and not a text processor after all :expressionless:--a reddish background colour was used).  Overall `Markdown` should now be easier to write and read.
- _major change:_ added support for [BBCode][30] syntax highlighting
- _major change:_ added basic support for [Bracket Highlighter][29]
- _change:_ the colouring of parenthesis in  `JSON`, `XML` and `HTML` files was changed to reflect the tag/name for easier readability
- _changed:_ the selection background colouring (to make it better readable in all different syntax scopes)
- _changed:_ the line highlighting colour, to make the icons in the Gutter used by different packages ([Bracket Highlighter][29], [Git Gutter][22], [Color Highlighter][32], etc.) better visible--additionally that also solved the problem with the `"highlight_line": true,` setting
- _change:_ merged [Git Gutter][22] additions from @jisaacks
- _change:_ merged `ERB` additions from @Kaboofa
- _minor change:_ in order to decrease the size of the package, I moved the screenshots to a different location.

## Thanks ##

A very big thanks goes to @daylerees :bow: for the work he has done with his [Colour Schemes][91].  His Laravel Dark scheme was used as a starting point for this colour scheme, as well as part of his readme file :sunglasses:.

Also I would like to thank my friends at [FlavourSys][92]--if you're working in the :video_camera: industry, you _need_ to see what they are doing--for their valued input and comments--as well as the kick in the b:dizzy_face: to push to :octocat:.

*Always have fun:sunny: in what you're doing and* "DON'T PANIC"...:rocket:

… **Enjoy**

<!-- reference section -->

[01]: https://en.wikipedia.org/wiki/Myth_Directions
[release]: https://github.com/FlavourSys/Perv-ColorScheme/releases
[sublime-text]: http://www.sublimetext.com/
[licence]: <LICENSE.txt>
[repo]: https://github.com/FlavourSys/Perv-ColorScheme
[issues]: https://github.com/FlavourSys/Perv-ColorScheme/issues

[release badge]: https://img.shields.io/github/release/FlavourSys/perv-colorscheme.svg
[sublime text badge]: https://img.shields.io/badge/Sublime%20Text-v2%2C%20v3-green.svg
[licence badge]: https://img.shields.io/badge/license-MIT-blue.svg
[stars badge]: https://img.shields.io/github/stars/FlavourSys/Perv-ColorScheme.svg
[issues badge]: https://img.shields.io/github/issues/FlavourSys/Perv-ColorScheme.svg
[paypal badge]: https://img.shields.io/badge/paypal-donate-ff69b4.svg

[11]: https://packagecontrol.io/packages/knockdown
[12]: https://packagecontrol.io/packages/MarkdownEditing
[13]: https://github.com/jhaubrich/Jesse-s-Sublime-Mods "abandoned"
[15]: https://packagecontrol.io/packages/SCSS
[16]: https://packagecontrol.io/packages/Syntax%20Highlighting%20for%20Sass
[17]: https://packagecontrol.io/packages/Sass
[20]: https://packagecontrol.io/packages/Git
[21]: https://www.sublimegit.net/
[22]: https://packagecontrol.io/packages/GitGutter
[23]: http://www.sublimerge.com/
[24]: http://www.sublimelinter.com/
[26]: https://packagecontrol.io/packages/Generic%20Config
[27]: https://packagecontrol.io/packages/Dotfiles%20Syntax%20Highlighting
[28]: https://packagecontrol.io/packages/nginx
[29]: https://packagecontrol.io/packages/BracketHighlighter
[30]: https://packagecontrol.io/packages/BBCode%20Syntax
[31]: https://packagecontrol.io/packages/TWiki
[32]: https://packagecontrol.io/packages/Color%20Highlighter
[img1]: https://raw.githubusercontent.com/micck/miccks-packages/master/screenshots/perv/perv-orange.png
[img2]: https://raw.githubusercontent.com/micck/miccks-packages/master/screenshots/perv/perv-orange-moonlight.png
[50]: http://buymeasoda.github.io/soda-theme/
[51]: http://www.sublimetext.com/
[52]: http://www.sublimetext.com/3
[53]: https://packagecontrol.io/installation
[91]: https://github.com/daylerees/colour-schemes
[92]: http://www.flavoursys.com
