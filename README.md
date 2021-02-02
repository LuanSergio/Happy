<h1 align="center">
  <a href="https://happy-nlw-web.netlify.app/">	
    <img alt="Happy" title="Happy" src="https://github.com/luansergiomattos/Happy/blob/master/readme/logo.png" />
  </a>
</h1>

<h4 align="center">
  Happy is an application that connects people to institutional care homes.
</h4>

<div align="center">
  <a href="https://happy-nlw-web.netlify.app/">	
    <img  src="https://github.com/luansergiomattos/Happy/blob/master/readme/happy.png" />
  </a>
</div>

<p>&nbsp;</p>

<p align="center">
  <a href="#page_facing_up-About"><strong>About</strong></a> &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#art-Layout"><strong>Layout</strong></a> &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#robot-Technologies"><strong>Technologies</strong></a> &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#man_technologist-Running-Locally"><strong>Running Locally</strong></a> &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-License"><strong>License</strong></a>
</p>

<div align="center">
  <img  src="https://github.com/luansergiomattos/Happy/blob/master/readme/division.png" />
</div>

## :page_facing_up: About
Happy is an application that connects people to institutional care homes. It was created with the purpose of training React, React Native and NodeJS.

#### Features:
You can register new orphanages. and view previously registered orphanages. <br>
Each orphanage contains photos, opening hours, information about the institution and a map position that you can interactively mark.

#### IMPORTANT NOTE:
I'm not using an external filestore like Amazon S3, so when we upload a imagem to create a orphanage, heroku will remove all images when it restarts (which it will do every day), since Heroku does not support file uploads. However, you can still upload an image when creating a new orphanage to test the feature.

<div align="center">
  <img  src="https://github.com/luansergiomattos/Happy/blob/master/readme/division.png" />
</div>

<div align="center">
  <img  src="https://github.com/luansergiomattos/Happy/blob/master/readme/nlw.svg" />
  <p><strong>This application is part of NLW.</strong></p>
</div>

NLW is a free online experience with lots of content and challenges to help developers improve their skills. <br>
NLW is a project created by [Rocketseat](https://blog.rocketseat.com.br/primeira-next-level-week/).

<div align="center">
  <img  src="https://github.com/luansergiomattos/Happy/blob/master/readme/division.png" />
</div>

## :art: Layout
<div align="center">
  <a href="https://www.figma.com/file/mDEbnoojksG4w8sOxmudh3/Happy-Web?node-id=0%3A1">
    <img  src="https://github.com/luansergiomattos/Happy/blob/master/readme/layout.png" />
  </a>
</div>
You can acces the layout design on figma on the links below:

- [Layout Web](https://www.figma.com/file/mDEbnoojksG4w8sOxmudh3/Happy-Web?node-id=0%3A1) 
- [Layout Mobile](https://www.figma.com/file/X27FfVxAgy9f5IFa7ONlph/Happy-Mobile?node-id=0%3A1) 

**Note:** You will need a figma account to access the layout, but you can create one for free

<div align="center">
  <img  src="https://github.com/luansergiomattos/Happy/blob/master/readme/division.png" />
</div>

## :robot: Technologies
Technologies that I used:

- [Node.js](https://nodejs.org/en/)
- [Express](https://expressjs.com/pt-br/)
- [SQLite](https://www.sqlite.org/index.html)
- [MongoDB](https://www.mongodb.com/)
- [NextJS](https://nextjs.org/)
- [React](https://reactjs.org/)

<div align="center">
  <img  src="https://github.com/luansergiomattos/Happy/blob/master/readme/division.png" />
</div>

## :man_technologist: Running Locally
You must have [Git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git), [NodeJS](https://nodejs.org/en/) and [Yarn](https://yarnpkg.com/) installed.

### Clone the repository and navigate to the folder
```bash
# Clone the repository
$ git clone https://github.com/luansergiomattos/Happy.git

# Navigate to the directory
$ cd Happy
```

### Install and run the Web version
```bash
# Navigate to the directory
$ cd web

# Install dependencies
$ yarn install 

# Run the aplication locally
$ yarn start

# Build the aplication for production
$ yarn build
```

### Install and run the Backend
```bash
# Navigate to the directory
$ cd backend

# Install dependencies
$ yarn install

# Run your migrations
yarn typeorm migration:run

# Run the aplication locally
$ yarn start

# Build the aplication for production
$ yarn build
```

### Install and run the Mobile
```bash
# Install expo on your computer
$ yarn add --global expo-cli

# Navigate to the directory
$ cd mobile

# Install dependencies
$ yarn install 

# Run the aplication locally
$ yarn start
```
**Note:** When you run the mobile aplication you must connect it to an android emulator or your own smartphone, [click here](https://medium.com/@webcore1/how-run-expo-for-react-native-on-your-ios-device-and-first-impressions-49882c38763d) for more details.

<div align="center">
  <img  src="https://github.com/luansergiomattos/Happy/blob/master/readme/division.png" />
</div>

## :memo: License
This project is under the MIT license.
**[Click here for more information](https://github.com/luansergiomattos/Happy/blob/master/LICENSE)**.
