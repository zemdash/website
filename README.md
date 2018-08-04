##Zemdash Website
**[www.zemdash.com](http://zemdash.com/)**

## Download and Installation

To begin using lone the repo: `git clone hgit@github.com:zemdash/website.git`

## Usage

After installation, run `npm install` and then run `gulp dev` which will open up a preview of the website in your default browser, watch for changes to core files, and live reload the browser when changes are saved. You can view the `gulpfile.js` to see which tasks are included with the dev environment.

#### Gulp Tasks

- `gulp` the default task that builds everything
- `gulp dev` browserSync opens the project in your default browser and live reloads when changes are made
- `gulp css` compiles SCSS files into CSS and minifies the compiled CSS
- `gulp js` minifies the themes JS file
- `gulp vendor` copies dependencies from node_modules to the vendor directory

You must have npm and Gulp installed globally on your machine in order to use these features.
