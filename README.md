# Perv Color Schemes

> **"Actually, as a native from Perv, I prefer to be called a 'Pervect'"**  < *Aahz in Myth Directions* >

## Introduction

The color scheme was made because I was unsatisfied with the limited syntax coloring of various color schemes--mainly missing (more) coloring for C/C++, JSON and ReST (reStructuredText)--and a missing structure to the coloring.  Therefore I created the *Perv Color Scheme* Family.  In the meantime the support for syntax highlighting support has been expanded to more languages.  Currently the scheme supports the following syntax highlighters and packages (look at the [Update](#update-history) section for more details):

1. reStructuredText (and reStructuredTextExtended)
2. Ruby
3. JSON
4. Git
5. DIFF
6. SublimeLinter
7. GitGutter
8. C/C++

As it may happen, I may create additional color schemes, therefore the name of the repository is just "Perv Color Scheme" and the actual color scheme is called "Perv Orange".

## Installation

### Sublime Text

For the Sublime Text editor the schemes can be installed easily by using [Package Control](http://wbond.net/sublime_packages/package_control) to install the 'Perv Color Schemes' package from the official repository.

Otherwise, first find your Sublime Text packages directory, you can find this by using the `Preferences -> Browse Packages` menu from within Sublime Text.

Now either create a `Perv -  Color Scheme` folder within this directory, and copy the contents of the GitHub repository inside, or clone the repository using the GIT software within the packages directory :

	git clone https://github.com/FlavourSys/Perv-ColorScheme "Perv - Color Scheme"

Now simply use the `Color Schemes` option of your preferences menu to switch between schemes & enjoy!

## The Color Schemes

### Perv Orange

Dark and retro color scheme:

![Perv Orange](https://raw.github.com/FlavourSys/Perv-ColorScheme/master/screenshots/perv-orange.png)


## Advanced usage

There are so many different personal tastes, that it is nearly impossible to make one color scheme, which satisfies even those guys, who's color taste is the same.  Some guys don't like *italics* or **bold** font faces, other's are using line highlight.  As it is currently impossible to create "switches" for specific effects in color schemes and as it is very easy to edit those effects to your personal liking, I added a couple of comments in my scheme files to help you out.

In order to edit the specific scheme file, you want to use/amend, please select the `Preferences -> Browse Packages` menu entry in Sublime Text.  That will open the Packages directory either in the "Finder" (on Mac OS X) or in the "Explorer" (on Windows).  Go into the "Perv - Color Scheme" directory and drag'n'drop the color scheme file, which you would like to use, to your Sublime Text editor.  After the file is loaded in the editor do the following regarding what you would like to change:

* *Using Line highlight*: search for "highlight_line". There are two "lineHighlight" entries in the file (one is commented out). Just comment the currently active line out and uncomment the other line.
* *Switch of italic or bold font faces*: search for either "italic" or "bold" in the file.  Just comment (Mac:<kbd>&#x2318;</kbd>+<kbd>/</kbd>, PC:<kbd>CTRL</kbd>+<kbd>/</kbd>) the line below the comment/instruction out.  Rinse and repeat for all font faces you want to remove.

> **Hint:** as you're already using Sublime Text -- commeting and uncommenting is as easy as a key-press: Mac: <kbd>&#x2318;</kbd>+<kbd>/</kbd> and for PC: <kbd>CTRL</kbd>+<kbd>/</kbd>)


## Contribute

If you find any problems, please don't hesitate to open an issue.  And if you want to make an improvement, please don't hesitate to clone and request a pull.


## Thanks!

A very big thanks goes to [Dayle Rees](https://github.com/daylerees) for the work he has done with his [Color Schemes](https://github.com/daylerees/colour-schemes).  I used his Laravel Dark scheme as a skeleton for this color scheme, as well as I used part of his readme.

Also I need to thank my colleagues at [FlavourSys](http://www.flavoursys.com) for their valued input and comments--as well as the kick in the b... to push to GitHub.

*Always have fun in what you're doing and* "DON'T PANIC"...

**Enjoy!**
