# Template Engine
This app takes user input on the command line about the members of their development team to include one manager, ulimited engineers, and unlimited interns. It then uses these inputs to generate an HTML document to display the team.

## Dependencies
* Node.js
* fs
* inquirer
* jest

## Instructions for use
To use this application, first download all files in the Develop folder. Once these files are downloaded, open the folder in a terminal or an editor with an integrated terminal. On the command line, run ``npm install`` to install dependencies. If not already installed, install Node.js. Once all necessary programs are installed, on the command line run ``node app.js`` and follow the prompts. Enter the information for every member of your team and once you have entered all team members, select "I'm done adding team members" at which point a file called ``team.html`` will appear in the ``outputs`` folder. Open this file in your preferred browser to view your team's webiste!

## Plans for future development
* Add validation to ensure that all fields are filled out for each team member
* Add validation to ensure that fields are filled out with the right kind of information (for example make sure NAme is a string, ID number is a number, email address is a valid email address)
