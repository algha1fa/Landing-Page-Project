# Landing Page Process

This project aims to give you real-world scenarios of manipulating the DOM. The functionality being used serves two purposes: to append dynamically added data to the DOM, and to show how javascript can improve the usability of an otherwise static site.

Open and view the Project using the .zip file provided.

## Table of Sections

- [Getting Started](#getting-started)
	- [Tools Required](#tools-required)
	- [Installation](#installation)
	- [Instructions](#instructions)
- [Development](#development)
- [Features](#features)
- [Running the App](#running-the-app)
- [References](#references)

## Started Sections

The project will be evaluated by a Udacity code reviewer according to the Landing Page project

### Required Points

No additional tools are required apart from a text-editor of your choice. 

### Installation

No additional installation is required for this project

### Instructions

* The starter code has some HTML and CSS styling to display a static version of the Landing Page project. You'll need to convert this project from a static project to an interactive one. This will require modifying the HTML and CSS files, but primarily the JavaScript file.  

* To get started, open `js/app.js` and start building out the app's functionality  

## Development Strategy

* First challenge is to build the navbar dynamically based on the sections of the page. This can be achieved by using the below mentioned methods of javascript
    > `for or forEach loop` </br>
      `document.getElementById` or  `document.querySelector` </br>
      `document.createElement` </br>
      `.setAttribute` </br>
      `.appendChild` </br>

* Next step would be to add functionality to distinguish the section in view. This can be achieved by using the `.getBoundingClientRect()` method of javascript. Active states have to be added to the sections as well as the corresponding nav-links.  

* Last part is to add the functionality to scroll to sections. This can be achieved by using the below mentioned methods of javascript
    >  scroll(), scrollBy(), and scrollIntoView()

## Features of landing page

* Active State change for sections and nav links as user scrolls the viewport
* Smooth scrolling using `scrollIntoView` when a nav link is clicked 

## Running the App

* Open the project through the `.zip` file provided and extract the files. 
  > Open `index.html` in the browser of your choice.
