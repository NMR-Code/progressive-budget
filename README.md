# Progressive Budget App

![npm](https://img.shields.io/npm/v/express?color=purple&label=express&logo=NPM&style=flat)
![npm](https://img.shields.io/npm/v/mongoose?color=red&label=mongoose&logo=NPM&style=flat)
![npm](https://img.shields.io/npm/v/compression?color=yellow&label=compression&logo=NPM&style=flat)

## Table of Contents

-  [Description](#description)
-  [Links for Submission Items](#links-for-submission-items)
-  [Assignment Scope](#assignment-scope)
-  [Installation](#installation)
-  [Final Output](#final-output)

## Description

The purpose of this assignment is to create a progressive budget application that allows users to manage financial activity while online or offline.

Overall, the user should be able to add expenses and deposits to their budget with or without an internet connection. When entering transactions offline, they should populate the total when brought back online.

The list below outlines the main functionality for this application:

-  Offline Functionality:

   -  Enter deposits offline

   -  Enter expenses offline

-  When brought back online:

   -  Offline entries should be added to tracker.

## Links for Submission Items

Link to deployed application on Heroku - [https://progessive-budget-app-ked.herokuapp.com/](https://progessive-budget-app-ked.herokuapp.com/)

Link to GitHub Repository - [https://github.com/NMR-Code/progressive-budget](https://github.com/NMR-Code/progressive-budget)

## Assignment Scope

Here is the `user story` and `Acceptance Criteria` that was provided by the Trilogy team.

### User Story

```
AS AN avid traveller
I WANT to be able to track my withdrawals and deposits with or without a data/internet connection
SO THAT my account balance is accurate when I am traveling
```

### Acceptance Criteria

```
GIVEN a user is on Budget App without an internet connection
WHEN the user inputs a withdrawal or deposit
THEN that will be shown on the page, and added to their transaction history when their connection is back online.
```

_Return to TOC - [Table of Contents](#table-of-contents)_

---

## Installation

In order to install this app you must first clone the repository.

### Required Technology

In order to success launch this web application, you will need to have the following installed in your local working environment:

-  **Node.js** - Make sure Node.js is installed in your machine. If Node.js is not installed on your machine, [click here](https://nodejs.org/en/) to download the application.

### Instructions

All NPM packages needed for this application are already listed as dependencies in the `package.json` file. If running this
web application in your local environment, please run the
`npm install` command in your terminal.

### Start Application

After all required dependencies have been installed using the instructions in the Installation Instructions section, run the command `node server.js` in you the terminal under the root directory in order to launch the application in your local environment.
