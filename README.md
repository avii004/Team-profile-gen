# team-profile-gen

This node.js application uses inquirer to gather employee data from the command line and then creates an HTML webpage that organizes each employee into a card.


## Installation

1. Download/clone my repository
2. This app requires node.js to be used.
3. Do `npm install` to install the required npm dependecies


## Features

* JavaScript
* Node.js
* Jest
* NPM
* Bootstrap


## Usage

* This app will be ran by using the following command: `npm start`


* The following information will be requested of each employee with validation.
  * Name
  * ID
  * Email
  
  * The user will then be asked to choose one of three employee types by providing information.
  * Manager (Limit: 1)
  * Engineer (no limit)
  * Intern (no limit)
  

* Additionally, each role has unique information.
  * Manager - Office Number
  * Engineer - GitHub Username
  * Intern - School

* After everything has been selected a index.html file will be generated with user input data located in the `dist` folder
