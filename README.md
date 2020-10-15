<img src="/readme-header.png" align="center"
     alt="Blind Ear Auditions" width="100%" height="auto">


---

## Table of Contents
  * [Summary](#Summary)
  * [Technologies](#technologies)
  * [Features And Functionality](#features-and-functionality)
  * [Challenges](#challenges)
  * [Future Development](#future-development)
  * [File Architecture](#file-architecture)
  * [Click here to visit the site!](https://bullring-fashion-fix.herokuapp.com/)
---

## Summary 
 > Blind Ear Auditions is an application for symphony orchestras to streamline the audition process.  Judges upload their scores and comments to a database through an elegant UI, and audition candidates retrieve their comments after the audition.   
---

## Technologies
> <b>Design Tools:</b>
  * Adobe Illustrator
  * Adobe Photoshop
  
> <b>Development Tools:</b>
  * <b>Framework:</b> Material UI
  * Handlebars
  * AJAX
  * Express
  * Path 
  * Google Charts
  * Sequelize
  * Node 
  * if-env
  * Git
  * Heroku (Heroku build)
---

## Features And Functionality


  * <b>Candidates receive average scores, written comments, and a visual display of scores using Google Charts.</b>
   <img src="/Candidate-score.gif" align="center"
       alt="Mobile Mock-Up Images" width="100%" height="auto">

---

## Challenges

 1. <b>Heroku / Git Hub:</b> When the application was initially created everything was running great locally, but the Client folder wasn't pushing to Git Hub. The client folder had accidently become a git submodule which prevented the application from deploying. 

 2. <b>Masonry Layout:</b> It took some time getting used to the Masonry style layout and identifying breakpoint to accommodate mobile responsiveness.
 
 3. <b>Date Sorting:</b> When I initially created the date sorting function to filter posts from newest to oldest I forgot to parse the data from the API. Once that was fixed I ran into another issue, in some browsers the date sorting function was not rendering correctly.  

---

## Future Development 

 1. <b>W3 MobileOk Checker:</b> Improve/investigate solutions for the identified alerts below: 
     <img src="client/src/Assets/images/Readme_files/W3C_mobile_checking.png" align="center"
        alt="W3 MobileOk Checker" width="80%" height="auto">
 
 2. <b>Tab Configuration:</b> Right now the navbar to filter post types does not fully meet accessibility guidelines. The component can be accessed by tab navigation however the tabs need to be reconfigured to perform an action (select/display the desired post) on a key press. 
 
 3. <b>Sizing:</b> The size of the inidividual cards containing post data could be reduced for a better user experience. The slider should modified for different screen sizes, it's very small on mobile devices. 
 
 4. <b>Lazy Loading Images:</b> The lazy loading image functionality needs to be modified. 

---

## File Architecture

<details><summary><b>Click To View</b></summary>
 

         Fashion Fix
         ├── Client
         │   ├── build
         │   ├── node_modules
         │   ├── public
         │   ├── src
         │   │   ├── Assets
         |   │   │   ├── globalCss
         |   |   │   │   ├── layout.css
         |   |   │   │   ├── mediaScreens.css  
         |   |   │   │   ├── reset.css  
         |   |   │   │   └── typography.css 
         |   │   │   └── images
         |   |   │   │   ├── image_1.gif  
         |   |   │   │   ├── image_2.gif  
         |   |   │   │   └── image_3.gif
         │   │   ├── Components
         |   │   │   ├── Cards
         |   |   │   │   ├── instagram.js          
         |   |   │   │   ├── manual.js
         |   |   │   │   └── twitter.js
         |   │   │   ├── Carousel
         |   |   │   │   ├── index.js
         |   |   │   │   └── style.css
         |   │   │   ├── Footer
         |   |   │   │   └── index.js
         |   │   │   └── Loading
         |   |   │       └── index.js
         │   │   ├── Pages
         |   │   │   └── socialWall.js
         │   │   ├── utils
         |   │   │   └── API.js
         │   │   ├── App.js
         │   │   ├── App.test.js
         │   │   ├── index.js
         │   │   ├── serviceWorker.js 
         │   │   └── setupTests.js
         │   ├── .gitignore
         │   └── package.json
         ├── node_modules
         ├── routes
         ├── .gitignore
         ├── package.json
         ├── Readme.md 
         └── server.js


</details>

---

[Back To Top](#welcome-to-Fashion-Fix)