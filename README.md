<h1 align="center">
    <img alt="Whatsapp with hat, glasses and tie" src="./public/github/logo.svg?raw=true" />
    <br>
    Whatsapp Api
</h1>
<h3 align="center">
  <a href="https://github.com/mckatoo/whatsapp-bot">
  For Whatsapp Bot
  </a>
  <br>
Api for use with <a href="https://github.com/mckatoo/whatsapp-bot">Whatsapp Bot</a> providing easy registration of menus and their items.
</h3>
<h4 align="center">
<br>
<img alt="Commitizen friendly" src="https://img.shields.io/badge/commitizen-friendly-brightgreen.svg">
<img alt="GitHub repo size" src="https://img.shields.io/github/repo-size/mckatoo/whatsapp-api">
<img alt="GitHub All Releases" src="https://img.shields.io/github/downloads/mckatoo/whatsapp-api/total">
<img alt="GitHub issues" src="https://img.shields.io/github/issues/mckatoo/whatsapp-api">
<img alt="GitHub" src="https://img.shields.io/github/license/mckatoo/whatsapp-api">
<img alt="GitHub followers" src="https://img.shields.io/github/followers/mckatoo">
<img alt="GitHub forks" src="https://img.shields.io/github/forks/mckatoo/whatsapp-api">
<img alt="GitHub stars" src="https://img.shields.io/github/stars/mckatoo/whatsapp-api">
<img alt="GitHub watchers" src="https://img.shields.io/github/watchers/mckatoo/whatsapp-api">
<img alt="GitHub commit activity" src="https://img.shields.io/github/commit-activity/m/mckatoo/whatsapp-api">
<img alt="GitHub contributors" src="https://img.shields.io/github/contributors/mckatoo/whatsapp-api">
<img alt="GitHub last commit" src="https://img.shields.io/github/last-commit/mckatoo/whatsapp-api">
<img alt="GitHub top language" src="https://img.shields.io/github/languages/top/mckatoo/whatsapp-api">
<img alt="GitHub release (latest by date)" src="https://img.shields.io/github/v/release/mckatoo/whatsapp-api">
<br>
<a href="http://standardjs.com" target="blank"><img alt="JavaScript Style Guide" src="https://cdn.rawgit.com/standard/standard/master/badge.svg"></a>
</h4>

<p align="center">
  <a href="#rocket-technologies">Technologies</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#warning-prerequisites">Prerequisites</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#information_source-how-to-use">How To Use</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#information_source-how-to-contribute">How To Contribute</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-license">License</a>
</p>

## :rocket: Technologies

This project was developed with the [William Justen Video](https://www.youtube.com/watch?v=ReEutDvYPQY) with the following technologies:

- [Strapi](http://strapi.io/)
- [Commitizen](https://github.com/commitizen/cz-cli)
- [Commitlint](https://github.com/conventional-changelog/commitlint)
- [JS Standard Style](http://standardjs.com)

## :warning: Prerequisites

To use and test the application, you must have already set up the development environment for NodeJS applications. You can install and configure NodeJS:

<a href="https://nodejs.org/"><img height=60 src="./public/github/nodejs.svg"></a>

## :information_source: How To Use

To clone and run this application, you'll need [Git](https://git-scm.com), [Node.js v12.18][nodejs] or higher + [Yarn v1.22][yarn] or higher installed on your computer. From your command line:

```bash
# Clone this repository
$ git clone https://github.com/mckatoo/whatsapp-api.git

# Go into the repository
$ cd whatsapp-api

# Install dependencies
$ yarn
# or
$ npm install

# Copy .env.example for .env and create ADMIN_JWT_SECRET token
$ cp .env.example .env && echo "ADMIN_JWT_SECRET=$(openssl rand 64 | base64)" >> .env

# Run the app
$ yarn develop
# or
$ npm run develop
```

## :information_source: How To Contribute



## :memo: License

This project is under the MIT license. See the [LICENSE](https://github.com/mckatoo/whatsapp-api/blob/master/LICENSE) for more information.

---

Made with ♥ by Milton Carlos Katoo :wave: <a href="https://www.linkedin.com/in/mckatoo/" target="blank">Get in touch!</a>

[nodejs]: https://nodejs.org/
[yarn]: https://yarnpkg.com/
