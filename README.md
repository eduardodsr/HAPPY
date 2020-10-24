# HAPPY - Rocketseat 🚀

[![](https://img.shields.io/badge/made_by-eduardodsr-green)](https://github.com/eduardodsr/)
![GitHub repo size](https://img.shields.io/github/repo-size/eduardodsr/HAPPY)
![GitHub top language](https://img.shields.io/github/languages/top/eduardodsr/HAPPY)
![GitHub language count](https://img.shields.io/github/languages/count/eduardodsr/HAPPY)
![Visitor](https://visitor-badge.glitch.me/badge?page_id=eduardodsr.HAPPY)

<p align="center">
 <h2> NWL#3 (Next Level Week #3) 
 </h2> 
  <a href="https://rocketseat.com.br">
    <img alt="Made by Rocketseat" src="https://img.shields.io/badge/made%20by-Rocketseat-7519C1">
  </a>
</p>

O projeto Happy consiste em criar uma aplicação web para cadastro de orfanatos. :rocket:


##  Projeto 🚀

O projeto está divido em três partes:
1. **Back End** (pasta backend) 
2. **Front End** (pasta web)
3. **Mobile** (pasta mobile)

## OBS ⚠️

Tanto o Front End quanto o Mobile precisam que o Back End esteja sendo executado para funcionar. 💡


## Tecnologias 🛠

As seguintes ferramentas foram usadas na construção do projeto:

- Expo
- Node.js
- React JS
- React Native
- TypeScript



### 🎲 Rodando o Back End (servidor)

```bash
# Clone este repositório
$ git clone 

# Acesse a pasta do projeto no terminal/cmd
$ cd Happy

# Vá para a pasta server
$ cd backend

# Instale as dependências
$ npm install 

# Execute a aplicação em modo de desenvolvimento
$ npm run dev:server

# O servidor inciará na porta:3333 - acesse http://localhost:3333 
```

### 🌐 Rodando a aplicação web (Front End)

```bash
# Clone este repositório
$ git clone 

# Acesse a pasta do projeto no seu terminal/cmd
$ cd Happy

# Vá para a pasta da aplicação Front End
$ cd web

# Instale as dependências
$ npm install

# Execute a aplicação em modo de desenvolvimento
$ npm start

# A aplicação será aberta na porta:3000 - acesse http://localhost:3000
```


### 📱 Rodando a aplicação mobile 

```bash
# Clone este repositório
$ git clone 

# Acesse a pasta do projeto no seu terminal/cmd
$ cd Happy

# Vá para a pasta da aplicação Mobile
$ cd mobile

# Instale as dependências
$ npm install

# Execute a aplicação em modo de desenvolvimento
$ npm start

```


### 🌐 Web

This project use third party dependencies that need to be installed, use that command to install all needed dependencies

```ps
$ cd web
$ yarn install
```

>The above command will install all third party dependencies used. If you want to install manually see all dependencies bellow

```json
   "dependencies": {
      "@testing-library/jest-dom": "^4.2.4",
      "@testing-library/react": "^9.3.2",
      "@testing-library/user-event": "^7.1.2",
      "@types/jest": "^24.0.0",
      "@types/node": "^12.0.0",
      "@types/react": "^16.9.0",
      "@types/react-dom": "^16.9.0",
      "leaflet": "^1.7.1",
      "react": "^16.13.1",
      "react-dom": "^16.13.1",
      "react-icons": "^3.11.0",
      "react-leaflet": "^2.7.0",
      "react-router-dom": "^5.2.0",
      "react-scripts": "3.4.3",
      "typescript": "~3.7.2"
   },
   "devDependencies": {
      "@types/react-leaflet": "^2.5.2",
      "@types/react-router-dom": "^5.1.6"
   }
```

<!-- ##### Server 

This project use third party dependencies that need to be installed, use that command to install all needed dependencies

```ps
$ cd server
$ yarn install
```

>The above command will install all third party dependencies used. If you want to install manually all the dependencies follow the steps bellow

```ps
# Entering in server directory
$ cd server

# Installing dependencies
$ yarn add @types/cors -D
$ yarn add @types/express -D
$ yarn add ts-node-dev -D
$ yarn add knex

# Proffy Version 2.0
$ yarn add pg
$ yarn add dotenv
```

##### Mobile

This projects use third party dependencies and fonts that need to be installed in development, use that command to install all needed dependencies and fonts

```ps
$ cd mobile

# Installing all fonts used
$ expo install expo-font @expo-google-fonts/archivo @expo-google-fonts/poppins

# Installing all dependencies required
$ yarn install
```
>The above command will install all third party dependencies and fonts used. If you want to install manually all dependencies and fonts used. follow the steps bellow

```ps
# Installing fonts used
$ expo install expo-font @expo-google-fonts/archivo
$ expo install expo-font @expo-google-fonts/poppins

# Installing dependencies required
$ yarn add @react-navigation/native
$ expo install react-native-gesture-handler react-native-reanimated react-native-screens react-native-safe-area-context @react-native-community/masked-view
$ yarn add @react-navigation/stack
$ yarn add @react-navigation/bottom-tabs
$ yarn add axios
$ expo install @react-native-community/async-storage
``` -->

#### Running

To start the Web Server run the command

```ps
# Entering in web directory
$ cd web

# Run the web server
$ yarn start
```

<!-- To start the Back Server run the command

```ps
# Entering in Server directory
$ cd server

# Run the Back Server
$ yarn start
```

To run the mobile version run the command

```ps
# Entering in Mobile directory
$ cd mobile

# Run the Mobile Version
$ yarn start
``` -->

---

## Create React App

<img alt="Logo" align="right" src="https://create-react-app.dev/img/logo.svg" width="20%" />

Create React apps with no build configuration.

- [Creating an App](#creating-an-app) – How to create a new app.
- [User Guide](https://facebook.github.io/create-react-app/) – How to develop apps bootstrapped with Create React App.


## Creating an App

**You’ll need to have Node 8.16.0 or Node 10.16.0 or later version on your local development machine** (but it’s not required on the server). You can use [nvm](https://github.com/creationix/nvm#installation) (macOS/Linux) or [nvm-windows](https://github.com/coreybutler/nvm-windows#node-version-manager-nvm-for-windows) to switch Node versions between different projects.

To create a new app, you may choose one of the following methods:

### npx

```sh
npx create-react-app my-app
```

_([npx](https://medium.com/@maybekatz/introducing-npx-an-npm-package-runner-55f7d4bd282b) is a package runner tool that comes with npm 5.2+ and higher, see [instructions for older npm versions](https://gist.github.com/gaearon/4064d3c23a77c74a3614c498a8bb1c5f))_

### npm

```sh
npm init react-app my-app
```

_`npm init <initializer>` is available in npm 6+_

### Yarn

```sh
yarn create react-app my-app
```

_[`yarn create <starter-kit-package>`](https://yarnpkg.com/lang/en/docs/cli/create/) is available in Yarn 0.25+_

It will create a directory called `my-app` inside the current folder.<br>
Inside that directory, it will generate the initial project structure and install the transitive dependencies:

```
my-app
├── README.md
├── node_modules
├── package.json
├── .gitignore
├── public
│   ├── favicon.ico
│   ├── index.html
│   └── manifest.json
└── src
    ├── App.css
    ├── App.js
    ├── App.test.js
    ├── index.css
    ├── index.js
    ├── logo.svg
    └── serviceWorker.js
    └── setupTests.js
```

No configuration or complicated folder structures, only the files you need to build your app.<br>
Once the installation is done, you can open your project folder:

```sh
cd my-app
```

Inside the newly created project, you can run some built-in commands:

### `npm start` or `yarn start`

Runs the app in development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.


### `npm test` or `yarn test`

Runs the test watcher in an interactive mode.<br>
By default, runs tests related to files changed since the last commit.

[Read more about testing.](https://facebook.github.io/create-react-app/docs/running-tests)

### `npm run build` or `yarn build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>

Your app is ready to be deployed.

## User Guide

You can find detailed instructions on using Create React App and many tips in [its documentation](https://facebook.github.io/create-react-app/).

## License 📝

Create React App is open source software [licensed as MIT](https://github.com/facebook/create-react-app/blob/master/LICENSE).

