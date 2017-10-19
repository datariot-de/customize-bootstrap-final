# SASS Mixins, variables and usage of an array

** Little exercise to define and use

## 1. Installing

*   Initialize a package.json (`npm init` and then answer the questions).
*   [bootstrap](https://npmjs.org/package/bootstrap) which will provide bootstrap SCSS source files (install it locally, as a development `npm i -D bootstrap@4.0.0-beta`)
*   [node-sass](https://npmjs.org/package/node-sass) which will compile the SCSS files into CSS (install it locally, as a development `npm i -D node-sass`)
*   Open the `package.json` and add "start" script like this:

    <pre>"scripts": {
      "start": "node-sass --watch --output dist --source-map true --source-map-contents sass --output-style compressed sass/styles.scss",
      "test": "echo \"Error: no test specified\" && exit 1"
    },</pre>

    Now, in the terminal, run `npm run start`.
    Make a change to your SCSS file and save to check.
*   If you want to run [live-server](https://npmjs.org/package/live-server), open a new tab in your terminal (`CTRL + SHIFT + T`) and run the command live-server.
* locate the sass file in the bootstrap folder in your node_modules and add an import to the file [sass/styles.scss]

## 2. Apply classes in index.html

* open [styles.html] in order to implement the given layout [layout.final.png]
* Classes to use: [container], [row], [col-...], [jumbotron], [btn], [btn-...], [img-fluid]

## 3. customize styles

** Little changes shall be done to the design that are different from bootstrap's default theme. It is your task to find out if the changes can be done by a) changing a bootstrap variable or b) overriding the styles with a selector in your styles.scss

* The layout shall be never wider than 1020px and the grid's gutter is 20px
* The border radii shall be way larger, set them all to 1.75rem
* The Jumbotron shall have a black background, white text color and no rounded borders
* Check the spacing of the hr and adjust

## 4. Extra

* Can you add a Navbar? See documentation at https://v4-alpha.getbootstrap.com/components/navbar/ and add a fixed navbar with the inverse, i.e. dark color scheme
