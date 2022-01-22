# **Front-End Web UI Frameworks and Tools: Bootstrap 4**
 
This project is the exercises of the [Frameworks and Tools: Bootstrap 4](https://www.coursera.org/learn/bootstrap-4/home/info "Bootstrap 4") 

## About Front-End Web UI Frameworks and Tools: Bootstrap 4

This course will give you an overview of client-side web UI frameworks, in particular Bootstrap 4. You will learn about grids and responsive design, Bootstrap CSS and JavaScript components. You will learn about CSS preprocessors, Less and Sass. You will also learn the basics of Node.js and NPM and task runners like Grunt and Gulp.

## Errors because of Gulp 3.9.1 version and NodeJS latest versions
 - Gulp doesnt run ==> ReferenceError: primordials is not defined.
   - In the same directory where you have package.json create an npm-shrinkwrap.json file with the following contents:  
      {
       "dependencies": {
         "graceful-fs": {
           "version": "4.2.2"
         }
       }
     }
    - npm install
    - gulp
  - Npm script doesnt run 
    - npm uninstall --save-dev parallelshell@3.0.2
    - npm install --save-dev parallelshell@3.0.1
    - npm start

## Table of Content

- [Week 1: Front-end Web UI Frameworks Overview: Bootstrap]
  - [Responsive Design and Boostrap Grid System](https://getbootstrap.com/docs/4.0/layout/grid)

- [Week 2: Bootstrap CSS Components]
  - [Navbar](https://getbootstrap.com/docs/4.0/components/navbar/) and  [Breadcrumbs](https://getbootstrap.com/docs/4.0/components/breadcrumb/)
  
  - [Buttons](https://getbootstrap.com/docs/4.0/components/buttons/) and  [Forms](https://getbootstrap.com/docs/4.0/components/forms/)

  - [Tables](https://getbootstrap.com/docs/4.0/content/tables/) and  [Cards](https://getbootstrap.com/docs/4.0/components/card/)
  
  - [Images](https://getbootstrap.com/docs/4.0/content/images/) and  [Media](https://getbootstrap.com/docs/4.0/layout/media-object/)
  
  - [Alert](https://getbootstrap.com/docs/4.0/components/alerts/) and  [Badges](https://getbootstrap.com/docs/4.0/components/badge/) and [Progress-bars](https://getbootstrap.com/docs/4.0/components/progress/)


- [Week 3: Bootstrap Javascript Components]
  - [Navs](https://getbootstrap.com/docs/4.0/components/navs/) and [Tabs](https://getbootstrap.com/docs/4.0/components/#tabs/) and  [Pills](https://getbootstrap.com/docs/4.0/components/#pills/)

  - [Collapse](https://getbootstrap.com/docs/4.0/components/collapse) and  [Accordion](https://getbootstrap.com/docs/4.0/components/collapse/#accordion-example)

  - [Tooltips](https://getbootstrap.com/docs/4.0/components/tooltips/) and  [Popovers](https://getbootstrap.com/docs/4.0/components/popovers/) and [Modals](https://getbootstrap.com/docs/4.0/components/modal/) 

  - [Carousel](https://getbootstrap.com/docs/4.0/components/carousel/)
  
- [Week 4: Web Tools]
  - [Jquery](https://jquery.com/) and [Bootstrap-Jquery](https://getbootstrap.com/docs/4.0/components/carousel/#methods)
  
  - [Less](https://lesscss.org/) and [Sass](https://sass-lang.com/guide)
  
  - [NPM scripts](https://www.keithcirkel.co.uk/how-to-use-npm-as-a-build-tool/)
  
  - [Grunt](https://gruntjs.com/) and  [Gulp](https://gulpjs.com/)
