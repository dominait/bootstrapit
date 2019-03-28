
# bootstrapit  
Simple static site builder created on top of bootstrap. This kit uses more intermediate tools to build and deploy your site. There are a few things you must do before starting a new project with this kit.
  
 
  
## checklist
Make sure you run through this checklist before you start your project.  
- download the bootstrapit kit and in the terminal run npm install.
- add gulp to your local PATH  
* MAC:  
* open up your bash profile > code ~/.bash_profile  
* add > export PATH=$PATH:./node_modules/.bin

  
## gulpfile.js
Open the style.scss file. Remove the starting styles for the site entry point.
```javascript
     {
        const gulp = require('gulp')
     }
```

    
## build folder
Each folder contains an _index.scss partial. Inside the index.scss partial you can place @import statements to each of the files you want to included. The style.scss file contains links to each folder. Remove and add what you need. Here is a short description of each folder and its contents.
<dl>
  <dt>function</dt>
   <dd>for your scss functions</dd>
</dl>  


 
