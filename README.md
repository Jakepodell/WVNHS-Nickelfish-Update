# Welcome to the [WVNHS Nickelfish Update](http://www.wvnhs.com/search)!

This page is the newest addition to Wayne Valley's National Honor Society website. It was created as an example to practice new Web Development technologies and philosophies. These include:
*** Javascript namespace objects**
*** Bootstrap CSS**
*** Angular.js**
*** CSS @media queries**
*** Improved project documentation**
*** Organized stylesheet and js scripts**

##Improved Design
The site works seamlessly on both mobile and desktop based browsers because of the Bootstrap integration. An @media query is used to add table padding when viewed from a larger screen without affecting the mobile experience.

##Back-end Upgrades
Using an Angular.js MVC design, the table contents were bound to an array of database entries loaded in the app's controller using php and json encoding. After the data is retrieved, each entry is converted to a namespaced NHS.member JavaScript object. The table then loads the data using Angular's ng-repeat function, with a real-time filter to the input field. 
All files and content for the system have been organized into easily readable res, lib, js, and css directories.

##Improved Documentation
You're looking at it.
