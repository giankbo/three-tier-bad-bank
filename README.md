<div align="center" id="top"> 
  <img src="./public/bank.png" alt="Bad Bank" width="265" height="250"/>

&#xa0;

<a href="https://giankbo.github.io/three-tier-bad-bank/" target="blank">Demo</a>

</div>

<h1 align="center">Bad Bank app</h1>

<p align="center">
  <img alt="Github top language" src="https://img.shields.io/github/languages/top/giankbo/three-tier-bad-bank?color=blue">

  <img alt="Github language count" src="https://img.shields.io/github/languages/count/giankbo/three-tier-bad-bank?color=blue">

  <img alt="Repository size" src="https://img.shields.io/github/repo-size/giankbo/three-tier-bad-bank?color=blue">

  <img alt="License" src="https://img.shields.io/github/license/giankbo/three-tier-bad-bank?color=tomato">
</p>

<p align="center" markdown="1">
  In this MIT xPRO project, we dockerized a MongoDB database. Next, we develop an Express application that serves static content. We then run the logic on the backend to establish a connection to the database. Finally, we write the frontend code to connect to the routes of our Express application.
</p>

<p align="center">
   <a href="#writing_hand-features">Features</a>
   ·
   <a href="#checkered_flag-how-to-run">How to run</a>
   ·
   <a href="#factory-improvements">Improvements</a>
   ·
   <a href="#handshake-credits">Credits</a>
   ·
   <a href="#memo-license">License</a>
   ·
   <a href="https://github.com/giankbo" target="blank">Author</a>
</p>

<br>

## :writing_hand: Features

- Three-tier architecture.
- Node.js app and routes in Express.
- Serve static files.
- Server API.
- Frontend calls to backend.
- Dockerized MongoDB database.
- Data Access Layer (DAL) setup.
- Firebase services. 🚧

## :checkered_flag: How to run

Before starting, you need to have [Git](https://git-scm.com), [Visual Studio Code](https://code.visualstudio.com/), [Node.js](https://nodejs.org/en/), [Docker](https://www.docker.com/), [MongoDB](https://www.mongodb.com/) installed. Then, clone the repo:

```bash
# Clone this project
$ git clone https://github.com/giankbo/three-tier-bad-bank
# Access
$ cd three-tier-bad-bank
# Install dependencies via npm
$ npm install
# Run Docker
$ docker run -p 27017:27017 --name badbank -d mongo
# Run your web server
$ node index.js
Once you've done the steps, you can view the message 'BadBank running on port: 3000' on your terminal and visit http://localhost:3000 to view your running application.
```

## :factory: Improvements

- Add authentication and authorization. 🚧

## :handshake: Credits

<a href="https://xpro.mit.edu/" target="_blank">MIT xPRO</a>

## :memo: License

This project is under license from MIT. For more details, see the [LICENSE](LICENSE.md) file.

&#xa0;

<a href="#top">Back to top</a>
