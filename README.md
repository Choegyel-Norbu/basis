# basis
A lightweight responsive CSS framework based on flexible box ( flexbox )

## Website

http://inc2734.github.io/basis/

## GitHub

https://github.com/inc2734/basis

## Get started

### Using npm

1. ```$ npm install sass-basis```
2. Import basis.scss your Sass/SCSS.
```scss
@import /PATH/TO/node_modules/basis/src/scss/basis;
```
or Just this link.
```html
<link rel="stylesheet" href="/PATH/TO/node_modules/basis/dist/css/basis.min.css" />
```

### Download from GitHub

1. Download the basis from https://github.com/inc2734/basis/releases
2. Build basis
```shell
$ cd /PATH/TO/basis
$ npm install
$ gulp build
```
3. Import basis.scss your Sass/SCSS.
```scss
@import /PATH/TO/basis/src/scss/basis;
```
or Just this link.
```html
<link rel="stylesheet" href="/PATH/TO/basis/dist/css/basis.min.css" />
```

### Option

Support IE9 ( Not perfect )

```html
<!--[if lt IE 10]>
<link rel="stylesheet" href="/PATH/TO/basis/dist/css/plugin/basis-ie9/basis-ie9.min.css" />
<![endif]-->
```

And support IE8 ( Not perfect )

```html
<!--[if lt IE 9]>
<script src="/PATH/TO/basis/vendor/html5.js"></script>
<![endif]-->
```

## Browser support
Modern Browser and IE10+

## How to contribute

Please make an issue if there is a problem and needs.
Please don't make the new issue if the issue of the same content already exists.
If you can coding, please give me a pull request.
But, please do not send in the master branch.
Pull request sent to the master branch doesn't merge.

## Third party licenses

#### normalize.css v3.0.3
* MIT License
* github.com/necolas/normalize.css

## Changelog

#### March 10, 2016 v2.2.0
* Fixed a bug that characters aren't displayed on IE8
* Fixed bugs bs-bp-md-only and bs-bp-lg-only
* Added visible classes.
* Added how to contribute section in readme.md

#### February 28, 2016 v2.1.2
* Fire Travis CI only master and develop.

#### February 28, 2016 v2.1.1
* Added release branch from Travis CI
* Added viewport at the doc.

#### February 27, 2016 v2.0.0
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

#### January 14, 2016 v1.4.0
* Changed prefix of class name.
* Changed grid system classes name.
* Changed break points.
* Changed form control classes.
* Changed heading elements margin.
* Removed table classes.
* Removed button size classes.
* Removed colors classes.
* Added media object class.

#### December 27, 2015 v1.3.0
* Remove text alignment classes.
* Changed directory structure.

#### December 16, 2015 v1.2.4
* Remove .bs-item--full
* Refactoring grid system.
* Added hidden classes.
* Changed font size unit. px to rem.
* Changed base font size.

#### November 28, 2015 v1.2.3
* Changed wrapper styles.
* Added .bs-container--size-no-gutter
* Removed xs prefix.
* Added button styles.
* Updated alert style.
* Updated wrapper style.

#### November 27, 2015 v1.2.2
* Added default flags.

#### November 25, 2015 v1.2.0
* Changed heading elements font size.
* Added styles: heading secondary text, tables.
* Added text alignment classes.
* Updated code element style.

#### November 21, 2015 v1.1.0
* Added normalize.css
* Added styles: Lists, Blockquote, Forms.
* Added container-gutter style.
* Fixed button style.

#### November 20, 2015 v1.0.0
* Release

## License

GPLv2 or later
