# Bootstrap for Web Designers

https://webdesign.tutsplus.com/courses/bootstrap-3-for-web-design/

Twitter's Bootstrap is an excellent set of carefully crafted user interface elements, layouts and JavaScript tools, easily available to use in your next web design project. This course takes you through Bootstrap, from top to bottom.

## News

* Overwiew (like a sitemap) of bootstrap 3 documentation available at https://vision-index.codio.io/bootstrap3-docs-overview.html.
* Overview redone using Handlebarsjs for templating. More flexible to experiment with changes (e.g. collapsibles) https://vision-index.codio.io/overview.html
* A gallery of the different themes provided by http://bootswatch.com/ available at https://vision-index.codio.io/bootswatch.html

## Notes



### The Grid System

* The containing element requiered by Bootstrap must be `div.container`, `div.container-fluid`. It wraps the site contents and houses the grid system. It is not nestable! 
  `.container` - responsive fixed width container
  `.container-fluid` - full width container, spanning the entire width of the viewport.

* if you go over 12 columns the layouts makes a break
* you can move cols around with an offset-class, e.g. col-lg-offset-2
* Nesting: The rule of 12 columns applies for nested divs too. They use up the space given by their parent.
* What are the breakpoints?

##### deconstructing the column-class

* col-lg-2 -> type (column); viewportsize (lg - large, md - middle, sm - small, xs - extra small)
* the column numbers for a certain size, defines the size of bigger sizes too, if no specific value is given. ie. if you have col-sm-2 and no
specific class for middle and large they are also 2.

### Buttons and Icons

* warum muss die Klasse "btn bt-default" heissen? Warum reicht nicht "btn-default"?
* classes for button colors: default, primary, success, info, warning, danger, link
* classes for button sizes: btn-lg, btn-sm, btn-xs
* buttonable elements: a, button (type: button, submit, reset), input (type: submit)

### Forms

* Classes introduced in this chapter
  * `input-sm`, `input-lg` - the size of input fields
  * `sr-only` - only shown for screenreader
  * `help-block` - special formatting for a paragraph that describes the expected content of the input
  * has-classes: `has-error`, `has-warning`, `has-feedback`, `has-success`

* Add glyphicon to an input field - div.form-group needs to have the class `has-feedback` and contains a span.glyphicon.glyphicon-ok.form-control-feedback

* control the width of input fields with the column-sizes of the grid system. wrap an input.formcontrol in a div.col-sm-3 (as example).

### Dropdowns

Was genau ist die Funktion von data-toggle="dropdown"?
Wird von JavaScript verwendet. The data-toggle=dropdown attribute is relied on for closing dropdown menus at an application level, so it's a good idea to always use it.

### Tabs

### Navbar

* There are some classes to give elements the right alignment in the Navbar: navbar-btn, navbar-text

### List groups

* There is an `ul` and a `div` version of the list group element

### Panels

### Modal Windows

* tabindex="-1" - this prevents, that the content is reached while tabbing through the side. Mostly used for initially invisible content like modal windows

* role="xxx" - used for accessibility reasons. Whatever that means.

### Collapse

Modification: How to make the full area of the header clickable: http://stackoverflow.com/questions/19236717/how-to-make-bootstrap-accordion-collapse-when-clicking-div

### Carousel



### List of bootswatch theme names

themes = ["cerulean", "cosmo", "cyborg", "darkly", "flatly", "journal", "lumen", "paper", "readable", "sandstone", "simplex", "slate", "spacelab", "superhero", "united", "yeti"]

## Todo

* publish on gh-pages
* make a cool navigation for all the tutorial files
* bring kuler color-schemes and bootstrap custom build together.
* a glyph-icon gallery that works on a mobile phone

* on bootstrap3-docs-overview.html: let the structure be generated (Plain JS or Handlebars.js?). Add Filter-Script like https://github.com/DeuxHuitHuit/quicksearch
* use bower and grunt on the project?
