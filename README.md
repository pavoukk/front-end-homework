# Palo Alto

This project is made by me as a student studying on 7bits company's courses. It's a simple blog layout that has pages:
* Home
* Contact Us

## Project structure

1. build
⋅⋅⋅Includes *images* folder containing the whole project images and files:
..* [index.html][] represents a html structure of the page **Home**
..* [contacts.html][] represents a html structure of the page **Contacts**
..* [style.css][] represents the whole project style in css language

2. src
⋅⋅⋅Includes original project files splitted into folders:

⋅⋅1. components
⋅⋅⋅⋅⋅⋅Includes main components of the project
....* footer
⋅⋅⋅⋅⋅⋅⋅⋅⋅Contains *images* and *styles* of any page's footer and its [footer.hbs][] file.
....* header
⋅⋅⋅⋅⋅⋅⋅⋅⋅Contains *images* and *styles* of and page's header and its [header.hbs][] file.
....* layout
⋅⋅⋅⋅⋅⋅⋅⋅⋅Contains *images* and *styles* of and page's layout and its [layout.hbs][] file.

⋅⋅2. pages
⋅⋅⋅⋅⋅⋅Includes every page's folder containing *images* and *styles* related to the page. Also every page has it's own file with **".hbs"** extension.

⋅⋅3. styles
⋅⋅⋅⋅⋅⋅Includes every page's style with **".css"** extension.

It also has [gulpfile.js][] file written in JavaScript that is needed to build the project properly.

### How to build

To compile and run the layout, you have to install Gulp and some other dependencies:
* gulp-concat
⋅⋅⋅It's needed to concat all CSS and HTML files into one file
* browser-sync
⋅⋅⋅It's needed to refresh pages after every change in the project
* gulp-compile-handlebars
⋅⋅⋅It's needed to compile all the **".hbs"** files
* gulp-rename
⋅⋅⋅It's needed to change folders destination while compiling the project

When all the needed dependencies is installed, you have to run **gulp** using console in the root folder  to build the project.
