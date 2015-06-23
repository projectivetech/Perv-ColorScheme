# Color Schemes - Perv #

> "**Actually, as a native from Perv, I prefer to be called a '_Pervect_'**" <_Aahz:japanese_ogre: in [Myth Directions]_>

[![release badge]][release] [![sublime text badge]][sublime-text] [![licence badge]][licence] [![stars badge]][repo] [![issues badge]][issues] [![paypal badge]][paypal]

## Introduction ##

--------------------------
### **NEEDS RE-WRITE** ###
--------------------------

The colour scheme was started because I was unsatisfied with the limited syntax colouring of various colour schemes--mainly missing (more) colouring for Markdown, reStructuredText, Ruby, C/C++ &amp; JSON--and a missing structure of the colouring.  Therefore I created the _Color Schemes - Perv_ family.  In the meantime the support for syntax highlighting support has been expanded to more languages.  Currently the scheme supports the following syntax highlighters and packages (look at the [Update](#update-history) section for more details):

|         Syntax        |                         Package                         |       Syntax       |         Package          |
| --------------------: | :------------------------------------------------------ | -----------------: | :----------------------- |
|     `Markdown`, `GFM` | [knockdown], [Markdown Editing]                         | `reStructuredText` | Default, [ReST extended] |
|         `Ruby`, `ERB` | Default                                                 |            `C/C++` | Default                  |
| `CSS`, `SCSS`, `SASS` | Default, [SCSS], [Syntax Highlighting for SASS], [SASS] |     `JSON`, `YAML` | Default                  |
|         `Git`, `Diff` | [Git], [Sublime Git], [Git Gutter], [SubliMerge Pro]    |           `Linter` | [Sublime Linter]         |

## The Perv Color Schemes

### Perv Orange :tangerine: Family

The colours are grouped together based on scopes:

+ **Comments**: Grey
+ **Classes & Objects**: Variations of Blue
+ **Functions**: Variations of Red
+ **Keywords & Tags**: Variations of Orange
+ **Storages**: Variations of Yellow
+ **Strings & Constants**: Variations of green

#### Perv Orange

Dark and retro:
![Perv Orange] ### todo ###

#### Perv Orange Moonlight

With a darker background and a higher contrast:
![Perv Orange Moonlight]

The screenshots were made with [Soda Theme] installed--nice addition to the _Color Schemes - Perv_.

## Advanced usage

----------------------------------
### **NEEDS CONSITENCY CHECK** ###
----------------------------------

~~There are so many different personal tastes, that it is nearly impossible to make one colour scheme, which satisfies even those guys, who's colour taste is the same.  Some guys don't like _italics_ or **bold** font faces, other's dislike the selection colour.  As it is currently impossible to create "switches" for specific effects in colour schemes and as it is very easy to edit those effects to your personal liking.~~

~~In order to edit the specific scheme file, you want to amend, please select the `Preferences -> Browse Packages` menu entry in Sublime Text.  That will open the Packages directory either in the "Finder" (on Mac OS X), "flavoured file explorer" (on Linux) or in "Explorer" (on Windows).  Go into the "Color Schemes - Perv" directory and drag'n'drop the colour scheme file, which you would like to use, to your Sublime Text editor.~~  After the file is loaded, do the following depending on the desired change:

+ *Switch of italic or bold font faces*: search for either "italic" or "bold" in the file.  ~~Just comment the line below the comment/instruction out.  Rinse and repeat for all font faces you want to remove.~~

> **Hint:** as you're already using Sublime Text -- commenting and uncommenting is as easy as a key-press: Mac: <kbd>&#x2318;</kbd>+<kbd>/</kbd> and for the PCs: <kbd>CTRL</kbd>+<kbd>/</kbd>)

## Installation

### Sublime Text

For the Sublime Text editor the schemes can be installed easily by using [Package Control] to install the 'Color Schemes - Perv' package from the official repository.

Otherwise, first find your Sublime Text packages directory--use the `Preferences -> Browse Packages` menu from within Sublime Text, if you don't know where the directory is located.

Now either create a `Color Schemes - Perv` folder within this directory, and copy the contents of the GitHub repository, or clone the repository using the GIT software within the packages directory:

    git clone https://github.com/FlavourSys/Perv-ColorScheme "Color Schemes - Perv"

Now simply use the `Color Scheme -> Color Schemes - Perv -> Perv YOUR FLAVOUR` option of your preferences menu to switch between the schemes & enjoy!

## Update history

### Version 1.4

--------------------------
### **COPY FROM TODO** ###
--------------------------

...

## Contribute

If you have any kind of problems or enhancement requests, please don't hesitate to open an issue.  And if you want to make an improvement, please don't hesitate to fork, create a branch and request a pull.

## Thanks!

A very big thanks goes to @daylerees :bow: for the work he has done with his [Colour Schemes].  His Laravel Dark scheme was used as a starting point for this colour scheme, as well as part of his readme file :sunglasses:.

Also I would like to thank my colleagues at [FlavourSys]--if you're working in the :video_camera: industry, you _need_ to see what they do--for their valued input and comments--as well as the kick in the b:dizzy_face: to push to :octocat:.

*Always have fun:sunny: in what you're doing and* "DON'T PANIC"...:rocket:

**Enjoy!**

<!-- reference section -->

[Myth Directions]: https://en.wikipedia.org/wiki/Myth_Directions
[release]: https://github.com/FlavourSys/Perv-ColorScheme/releases
[sublime-text]: http://www.sublimetext.com/
[licence]: <LICENSE.txt>
[repo]: https://github.com/FlavourSys/Perv-ColorScheme
[issues]: https://github.com/FlavourSys/Perv-ColorScheme/issues
[paypal]: https://www.paypal.com/###donnot###forget####to####change####this###

[release badge]: https://img.shields.io/github/release/FlavourSys/perv-colorscheme.svg
[sublime text badge]: https://img.shields.io/badge/Sublime%20Text-v2%2C%20v3-green.svg
[licence badge]: https://img.shields.io/badge/license-MIT-blue.svg
[stars badge]: https://img.shields.io/github/stars/FlavourSys/Perv-ColorScheme.svg
[issues badge]: https://img.shields.io/github/issues/FlavourSys/Perv-ColorScheme.svg
[paypal badge]: https://img.shields.io/badge/paypal-donate-ff69b4.svg

[Perv Orange]: https://raw.githubusercontent.com/micck/miccks-packages/master/screenshots/perv/perv-orange.png
[Perv Orange Moonlight]: https://raw.githubusercontent.com/micck/miccks-packages/master/screenshots/perv/perv-orange-moonlight.png

[Soda Theme]: http://buymeasoda.github.io/soda-theme/
[knockdown]: https://packagecontrol.io/packages/knockdown
[Markdown Editing]: https://packagecontrol.io/packages/MarkdownEditing
[ReST extended]: https://github.com/jhaubrich/Jesse-s-Sublime-Mods "abandoned"
[SCSS]: https://packagecontrol.io/packages/SCSS
[Syntax Highlighting for Sass]: https://packagecontrol.io/packages/Syntax%20Highlighting%20for%20Sass
[SASS]: https://packagecontrol.io/packages/Sass
[Git]: https://packagecontrol.io/packages/Git
[Sublime Git]: https://www.sublimegit.net/
[Git Gutter]: https://packagecontrol.io/packages/GitGutter
[SubliMerge Pro]: http://www.sublimerge.com/
[Sublime Linter]: http://www.sublimelinter.com/

[Package Control]: https://packagecontrol.io/installation

[Bracket Highlighter]: https://packagecontrol.io/packages/BracketHighlighter
[Generic Config]: https://packagecontrol.io/packages/Generic%20Config
[Dotfile]: https://packagecontrol.io/packages/Dotfiles%20Syntax%20Highlighting
[nginx]: https://packagecontrol.io/packages/nginx
[BBCode]: https://packagecontrol.io/packages/BBCode%20Syntax
[Scope Hunter]: https://packagecontrol.io/packages/ScopeHunter

[Colour Schemes]: https://github.com/daylerees/colour-schemes
[FlavourSys]: http://www.flavoursys.com
