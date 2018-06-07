# docs
> 📃 General documentation and setup.

## 📖 Introduction
This repository explains the use of this github organization and how repositories are structured. Aimed at developer at &samhoud to continue working on these projects or make changes.

## Access

### GitHub organization
Please contact me at hi@dandevri.es to request access for this GitHub organization. After approval from &samhoud I will add you as a **member of the &samhoudmedia organization**.

### Bitbucket
Due to content of the 360-video's (needed to be kept private) they are hosted on the Bitbucket platform since GitHub requires payment for private repo's. 

After approval of &samhoud please contact me at hi@dandevri.es to get the credentials of the **bitbucket account**. There you will have access to the private repo's.

## Hosting
All prototypes are hosted via [`GitHub Pages`](https://pages.github.com/) to serve up the static files. These repositories have a `gh-pages` branch and have the url for the live version at the top of the repository. The 360-video's are hosted in the same manner but on [`BitBucket Cloud`](https://confluence.atlassian.com/bitbucket/publishing-a-website-on-bitbucket-cloud-221449776.html). 

The showcase repository is a dynamic node app so it is deployed to a `node` environment on [`Heroku`](heroku.com). With Heroku you can have a free tier with a custom domain.

## Installation & Development

Each repository contains a detailed `readme` explaining how get the project up and running. Most how them have the following tech prerequisites.

### Prerequisites
* Make sure you have [`node`](https://nodejs.org/en/) installed on your machine.
* [`npm`](https://www.npmjs.com/) comes with node.
* You can check versions with; `npm -v` and `node -v`
* Configure [ESLint](https://eslint.org/docs/user-guide/integrations)
* Configure [EditorConfig](https://editorconfig.org/#download)
* Configure [Stylelint](https://stylelint.io/user-guide/complementary-tools/)

All dependencies are local and specified in the `package.json` you won't have to install any global packages.

### Tech Stack
Most repository make use of the following technologies:
* [`A-frame`](https://aframe.io/)
* [`Webpack`](https://webpack.js.org/)
* [`Express`](https://expressjs.com/)
* [`Pug`](https://pugjs.org)
* [`Sass`](https://sass-lang.com/)

### Installation
Please refer to the `readme` of the specific repo to get up and running. Mostly `npm install` and `npm start` will do. 

## Contributing
Feel free to make pull requests and create issue, if you have any more questions please contact me at hi@dandevri.es

## 📃 License
[`MIT`](LICENSE) © [Danny de Vries](https://github.com/dandevri)
