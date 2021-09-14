# bootstrap-project

In this project I created a site for a made up interior design company called Atlas. Which I styled with [this template](https://preview.colorlib.com/theme/mosaic/index.html) as an inspitation.  
I used Bootstrap 5 with sass which I set up using npm in the terminal.  

I used some whole Bootstrap components but also used various Bootstrap classes, for example for padding, margins and font sizes and widths.  

This helped speed the process of setting up the website by using available components and classes instead of writing everything from scratch.
Having the sass/css already available makes the process fast and easy.  
<br/><br/>

## My setup

### Installation
I started by running in terminal:  
`npm init`

Then I imported bootstrap, sass and postcss within the terminal:  
`npm install sass --save-dev`  
`npm install bootstrap postcss --save`  
<br/><br/>

### Folder setup
I created two folders:
- sass
- dist

And in the sass folder I added folders for:
- Components
- Sections

In the dist folder I added two other folders
- js
- assets
<br/><br/>

### File structure
#### Sass folder structure
In the sass folder I created a style.scss file and used that file to import all other .scss files that will be compiled to dist/css/style.css which is the linked css file in the .html files.

The '_custom.scss' file is used to import all the Bootstrap sass files using:  
`@import "../node_modules/bootstrap/scss/bootstrap.scss";`  

Above the @import is where I put all the overrides of variables, colors, icons, fonts e.t.c.
Then I created files for each section and components and grouped them in their own folder and then imported all to the style.scss file.
<br/>
<br/>

#### Js folder structure
In the js folder I copied the .js files needed for the Bootstrap mobile menu and accordion component 
These were:
- bootstrap.bundle.js
- bootstrap.bundle.min.js.map
<br/>

#### Assets folder
In the assets folder I have all the image files, icons(logo) and favicons used on the website.
<br/>
<br/>

## Clone project

To clone the project to work on it you have to do the following:
#### Clone Project  
run in terminal: `git clone https://github.com/hebaulf/bootstrap-project.git`  
<br/>
#### Install dependencies
run in terminal: `npm install`
