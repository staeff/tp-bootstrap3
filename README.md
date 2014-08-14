# Bootstrap for Web Designers

https://webdesign.tutsplus.com/courses/bootstrap-3-for-web-design/
Instructor: Adi Purdila

Twitter's Bootstrap is an excellent set of carefully crafted user interface elements, layouts and JavaScript tools, easily available to use in your next web design project. This course takes you through Bootstrap, from top to bottom.

## Notes

### The Grid System

* "container" vs. "container-fluid"? I don't really understand this yet. How are they behaving different?
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



## Todo

* make a cool navigation for all the tutorial files
* bring kuler color-schemes and bootstrap custom build together.
* a glyph-icon gallery that works on a mobile phone