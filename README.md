# Paperguesser backend

## Description

Paperguesser is an online multiplayer guessing game.

The game provides:

- A login and lobby built with React, with the ability to password protect rooms
- An in-game chatroom , built with Socket.IO
- A fully functional guessing game

## Instructions

This backend will be live on [Heroku](https://paperguesser-server.herokuapp.com/).
<br/>
The frontend counterpart repository can be found [here](https://github.com/chicorycolumn/Paperguesser-frontend).
<br/>
The live site will be live on [Netlify](https://paperguesser.netlify.app/).
<br/>
You can also download this repository and run the project locally by following these steps:

1. Fork this repository by clicking the button labelled 'Fork' on the [project page](https://github.com/chicorycolumn/Paperguesser-backend).
   <br/>
   Copy the url of your forked copy of the repository, and run `git clone the_url_of_your_forked_copy` in a Terminal window on your computer, replacing the long underscored word with your url.
   <br/>
   If you are unsure, instructions on forking can be found [here](https://guides.github.com/activities/forking/) or [here](https://www.toolsqa.com/git/git-fork/), and cloning [here](https://www.wikihow.com/Clone-a-Repository-on-Github) or [here](https://www.howtogeek.com/451360/how-to-clone-a-github-repository/).

2. Open the project in a code editor, and run `npm install` to install necessary packages. You may also need to install [Node.js](https://nodejs.org/en/) by running `npm install node.js`.

3. Run `npm start` to open the project in development mode.
   <br/>
   Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Deploy

General instructions for hosting on **Heroku** for **automatic deployment** are as follows:

0. Ensure the project is initialised in a Git repository. If you are unsure what this means, instructions can be found [here](https://medium.com/@JinnaBalu/initialize-local-git-repository-push-to-the-remote-repository-787f83ff999) and [here](https://www.theserverside.com/video/How-to-create-a-local-repository-with-the-git-init-command).

1. Install the Heroku CLI if not already, with `npm install heroku`.

2. Run these three commands:

- `heroku login`
- `heroku create my-awesome-app`
- `heroku git:remote -a my-awesome-app`

3. Login to Heroku and enable automatic deploys from Github, and connect the repo.

Now when you commit and push to Github, Heroku will deploy the latest version of the project automatically.

## Built with

- [JavaScript](https://www.javascript.com/) - The primary coding language
- [VisualStudioCode](https://code.visualstudio.com/) - The code editor

- [Heroku](https://www.heroku.com/) - The cloud application platform used for the backend
- [Netlify](https://www.netlify.com/) - The hosting service used for the frontend

- [Socket.IO](https://socket.io/) - The realtime library

- [React](https://reactjs.org/) - The frontend framework
- [CSS Modules](https://github.com/css-modules/css-modules) - The design organisation system
