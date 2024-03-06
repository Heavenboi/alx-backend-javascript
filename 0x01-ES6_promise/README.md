# Project: ES6 Promise Challenges

## Overview

This project focuses on understanding and implementing ES6 Promises to handle asynchronous operations in JavaScript. It includes various tasks aimed at solving problems using Promises and related concepts.

---

## Learning Objectives

Upon completing this project, you should be able to:

- Explain the concept of Promises, including how and why they are used.
- Utilize `then`, `resolve`, and `catch` methods to handle Promise states and outcomes.
- Understand and use the `every` method of the Promise object.
- Implement error handling with `throw` and `try` in asynchronous operations.
- Utilize the `await` operator and understand how to use async functions effectively.

---

## Requirements

- **Operating Environment**: Ubuntu 18.04 LTS with NodeJS 12.11.x
- **Supported Editors**: vi, vim, emacs, Visual Studio Code
- **Testing**: Jest for testing (run `npm run dev` filename)
- **Linting**: Verify code against ESLint

---

## Setup

1. **Install NodeJS 12.11.x**:
   ```bash
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
... (similar for other tasks)

Usage
To execute any task, run:

arduino
Copy code
npm run dev filename
Replace filename with the specific task file.

