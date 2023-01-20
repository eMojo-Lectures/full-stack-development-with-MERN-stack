# Full-Stack Development with MERN stack.

## In this module, we will cover concepts such as:

- Develop MERN backend from scratch,
- - Setup backend database, MongoDB atlas, or self-hosted,
- - Setup backend Express server and connect to MongoDB,
- - Develop a skeleton backend for the Express server,
- - Implement user model, authentication, and user security,
- - Setup CRUD operations for the user model,
- - Integrate user security with protected API routes,
- - Finalize implementation of the backend with user security,

## Command line operations to setup environment:

### Prerequisites

To follow this steps along it will be helpful to have the following:

- A prior experience of Node.js, Express, npm, and React.js.
- Node.js installed.
- A text editor, preferably VS Code.
- A web browser, in this case, Google Chrome.

### Instructions

- The first thing you need to do is to create a new express application. To do so, you need to have `npm` installed. You can install NodeJS by following this [link](https://nodejs.org/en/download/) and installing a version compatible with your operating system. Instructions on setting up environment will be provided in the first video related to this module.
- After installing NPM as discribed above, you need to setup development dependencies from the command line with the following series of commands:

- #### First, you need to ensure that you have an Express application generator installed.
- - Please run the following command as with administrator provilages--or start the terminal as an admin.
- - Run `sudo npm install -g express-generator`.

- #### Now, you need to generate a new application with express.
- - Note that in this example we generate a new application running with a view templating language called [pug](https://pugjs.org/), and the name of the application is backend-skeleton.
- - Run `npx express-generator --view=pug backend-skeleton`.

- - Once you've done the above, you should be able to cd into the backend-skeleton application with the following command.
- - Run `cd backend-skeleton`.
- - Once you ran the above command, you should be able to install all dependencies which will be populated in a folder called node_modules. Node modules is the root folder which will contain all project files which are external to what you have developed--for now, let's call them dependencies. More on this later.
- - Run `npm install`.
- - Generally speacking, npx express generator brings a banch of vulnerabilities with it. To fix this, we need to run the following command. Most of them should have an auto-fix available.
- - Run `npm audit fix --force`.
- - Run `npm audit fix` audit to check if you have exactly 0 vulnerabilities.
