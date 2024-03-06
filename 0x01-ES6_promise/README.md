Project: ES6 Promise Challenges
This project focuses on understanding and implementing ES6 Promises to handle asynchronous operations in JavaScript. It includes various tasks aimed at solving problems using Promises and related concepts.

Learning Objectives
Upon completing this project, you should be able to:

Explain the concept of Promises, including how and why they are used.
Utilize then, resolve, and catch methods to handle Promise states and outcomes.
Understand and use the every method of the Promise object.
Implement error handling with throw and try in asynchronous operations.
Utilize the await operator and understand how to use async functions effectively.
Requirements
Operating Environment: Ubuntu 18.04 LTS with NodeJS 12.11.x
Supported Editors: vi, vim, emacs, Visual Studio Code
All files must end with a new line.
Include a README.md file at the root of the project directory.
Use the .js extension for JavaScript files.
Test your code using Jest by running npm run test.
Verify your code against ESLint for linting.
Setup
Install NodeJS 12.11.x:

arduino
Copy code
curl -sL https://deb.nodesource.com/setup_12.x -o nodesource_setup.sh
sudo bash nodesource_setup.sh
sudo apt install nodejs -y
nodejs -v
npm -v
Install Jest, Babel, and ESLint:

bash
Copy code
cd project_directory
npm install
Configuration Files:

package.json
babel.config.js
utils.js
.eslintrc.js
Tasks Overview
The project consists of several tasks, each focusing on different aspects of working with Promises and asynchronous JavaScript operations. Here's a brief overview of the tasks:

Keep every promise you make and only make promises you can keep

Implement a function that returns a Promise using a given prototype.
Don't make a promise...if you know you can't keep it

Create a Promise based on a boolean parameter and handle resolution/rejection accordingly.
Catch me if you can!

Append handlers to a given Promise function and handle resolutions/rejections.
Handle multiple successful promises

Resolve multiple promises and handle their outcomes collectively.
Simple promise

Create a resolved Promise with specific attributes.
Reject the promises

Implement a function returning a rejected Promise with a custom error message.
Handle multiple promises

Call multiple Promise-based functions and return their outcomes collectively.
Load balancer

Implement a function that returns the first resolved value from two given Promises.
Throw error / try catch

Create a function that throws an error under certain conditions.
Throw an error

Implement a function that captures errors from another function and appends them to an array along with other values.
Each task provides hands-on practice in using Promises and related concepts.

Usage
To execute any task, run:

arduino
Copy code
npm run dev filename
Replace filename with the specific task file.

