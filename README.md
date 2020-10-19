# HAPPY -  NLW#3 ROCKETSEAT 🚀




This project was bootstrapped with Create React App.

Available Scripts
In the project directory, you can run:

yarn start
Runs the app in the development mode.
Open http://localhost:3000 to view it in the browser.

The page will reload if you make edits.
You will also see any lint errors in the console.

yarn test
Launches the test runner in the interactive watch mode.
See the section about running tests for more information.

yarn build
Builds the app for production to the build folder.
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.
Your app is ready to be deployed!

See the section about deployment for more information.

yarn eject
Note: this is a one-way operation. Once you eject, you can’t go back!

If you aren’t satisfied with the build tool and configuration choices, you can eject at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except eject will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use eject. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

Learn More
You can learn more in the Create React App documentation.

To learn React, check out the React documentation.
 

##  NWL#3 (Next Level Week #3 da ROCKETSEAT)

:rocket: . O projeto Happy consiste em criar uma aplicação web para cadastro de orfanatos.


##  Projeto 🚀

O projeto está divido em três partes:
1. Back End (pasta backend) 
2. Front End (pasta web)
3. Mobile (pasta mobile)

## OBS: 

Tanto o Front End quanto o Mobile precisam que o Back End esteja sendo executado para funcionar. 💡


## 🛠 Tecnologias

As seguintes ferramentas foram usadas na construção do projeto:

- [Expo][expo]
- [Node.js][nodejs]
- [React][reactjs]
- [React Native][rn]
- [TypeScript][typescript]


### Pré-requisitos



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

### 🧭 Rodando a aplicação web (Front End)

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


### 📱Rodando a aplicação mobile 

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



#### Requirements
* [Node.js][node-url]
* [Yarn][yarn-url] or [npm][npm-url]
* [Expo][expo-url]

##### Web

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

### Issues 🐛

#### Report

In case you are having any problem do not be shy to report to us in [Issues][issues-url] session.

### Contributing 🤝 

There are many forms to contribute with the project, first of all you can give this github repo a Star.

If you want do help with the code follow the steps bellow

```ps
# Fork using GitHub official command line
# If you don't have the GitHub CLI, use the web site to do that.
$ gh repo fork pmqueiroz/happy

# Clone your fork
$ git clone {your-fork-url}
$ cd happy

# Create a branch with your feature
$ git checkout -b {branch-name}

# Make the commit with your changes
$ git commit -m 'Feat: {feature-name}'

# Send the code to your remote branch
$ git push origin {branch-name}
```

Then send a Pull Request that will be analyzed and approved if it helps with the project

### License 📝

This project is under the MIT license. See the [LICENSE][license-url] for more information.
