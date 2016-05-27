#Changelog

## May 25, 2016 v5.0.0
* The document to another repository #58
* Removed `html{ font-size: 62.5% }` #79
* `bs-font-size()`, `bs-line-height()` and `bs-font-size-line-height()` support px #79
* Refactoring `$bs-between-lines` #79
* Changed `$bs-font-size` to `$bs-base-font-size`
* Added a variable `$bs-base-font-size-px`
* Removed auto build on npm install #81
* Fixed opacity transition bug #82
* Added CHANGELOG.md
* Added .editorconfig
* Changed indent style
* Refactoring gulpfile.js

## May 10, 2016 v4.3.2
* Update README

## May 8, 2016 v4.3.1
* Fixed a bug that the Basis set incorrect breakpoint when `$bs-font-size` isn't 1.6rem.

## May 8, 2016 v4.3.0
* Added extending underline animation mixin `bs-extend-underline()`
* Added extending underline animation class `._u-animate-extend-underline`
* Added padding helper mixins.
* Added `._c-row--reverse`

## May 5, 2016 v4.2.7
* Refactoring `._c-hero--cover`
* Refactoring `bs-vertical-rhythm()`
* Changed container margin on smartphone.
* Fixed a image position of media object bug when `$bs-between-lines` changed.

## May 3, 2016 v4.2.6
* Fixed error when npm install
* Fixed media object bug on IE

## May 3, 2016 v4.2.0
* Change comments format.
* Added mixin `bs-bp-md-min`, `bs-bp-md-max`
* Refactoring around media query.

## April 24, 2016 v4.1.0
* Changed GitHub repository.
* Changed license.
* Move imports out of if statement.

## April 21, 2016 v4.0.2
* Fixed a `._c-container` bug.

## April 18, 2016 v4.0.0
* Refactoring directory structure.
* Refactoring input-group style.
* Added variable `$bs-use-mixin-only`. If you don't need classes of the Basis, set to true.
* Added mixins to make the Basis components.
* Added variables for the components of style.

## April 12, 2016 v3.2.0
* Fixed a grid margin bug.
* Added `._c-row--nowrap` class.
* Changed color settings.
* Added the coefficient variable for margin.
* Added the heading element scale variable.
* Added mixin `bs-font-size-line-height`

## April 6, 2016 v3.1.0
* Fixed hidden and visible classes bug.
* Added styles of readonly, disabled and aria-hidden.
* Changed blockquote and form-control styles.

## April 6, 2016 v3.0.1
* Fixed grid margin.

## April 6, 2016 v3.0.0
* Added the hero component.
* Added transition and animation utility classes.
* Updated normalize.css
* Changed base margin.
* Changed breakpoint unit px to em.

## March 10, 2016 v2.2.0
* Fixed a bug that characters aren't displayed on IE8
* Fixed bugs bs-bp-md-only and bs-bp-lg-only
* Added visible classes.
* Added how to contribute section in readme.md

## February 28, 2016 v2.1.2
* Fire Travis CI only master and develop.

## February 28, 2016 v2.1.1
* Added release branch from Travis CI
* Added viewport at the doc.

## February 27, 2016 v2.0.0
* Refactoring gulpfile.js
* Refactoring the grid gutter.
* Fixed grid system bugs.
* Changed directories and files name.
* Changed the col class name.
* Changed to use normalize.css of npm.
* Added vertical mode for the media module.
* Added FLOCSS object type prefix.
* Added IE9 Support ( optional )
* Added some utility classes.
* Removed `._c-row__col--flex` and added `._c-row--fill`
* Removed `._c-row--row`, `._c-row--column`

## January 14, 2016 v1.4.0
* Changed prefix of class name.
* Changed grid system classes name.
* Changed break points.
* Changed form control classes.
* Changed heading elements margin.
* Removed table classes.
* Removed button size classes.
* Removed colors classes.
* Added media object class.

## December 27, 2015 v1.3.0
* Remove text alignment classes.
* Changed directory structure.

## December 16, 2015 v1.2.4
* Remove .bs-item--full
* Refactoring grid system.
* Added hidden classes.
* Changed font size unit. px to rem.
* Changed base font size.

## November 28, 2015 v1.2.3
* Changed wrapper styles.
* Added .bs-container--size-no-gutter
* Removed xs prefix.
* Added button styles.
* Updated alert style.
* Updated wrapper style.

## November 27, 2015 v1.2.2
* Added default flags.

## November 25, 2015 v1.2.0
* Changed heading elements font size.
* Added styles: heading secondary text, tables.
* Added text alignment classes.
* Updated code element style.

## November 21, 2015 v1.1.0
* Added normalize.css
* Added styles: Lists, Blockquote, Forms.
* Added container-gutter style.
* Fixed button style.

## November 20, 2015 v1.0.0
* Release
