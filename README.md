<h1 align="center">
  <img src="https://github.com/Silvio-Ronaldo/Ecoleta/blob/master/web/src/assets/logo.svg" alt="Ecoleta Logo" height=100 />
</h1>

<p align="center"><strong>♻️ Ecoleta - is a way to connect companies and entities that collect organic and inorganic waste to people who need to dispose of their waste in an ecological way.</strong></br>Developed at NLW#1</br>Practical project for study<p>

<p align="center">
  <a href="./LICENSE">
    <img src="https://img.shields.io/badge/license-MIT-blue" alt="Ecoleta is released under the MIT license" />
  </a>
  <a href="https://GitHub.com/Silvio-Ronaldo/Ecoleta/graphs/commit-activity">
    <img src="https://img.shields.io/badge/Maintained%3F-yes-brightgreen" alt="Ecoleta is currently maintained by Silvio Ronaldo" />
  </a>
  <a href="https://GitHub.com/Silvio-Ronaldo/Ecoleta/network/">
    <img src="https://img.shields.io/github/forks/Silvio-Ronaldo/Ecoleta?style=social" alt="This is the number of forks in this repository" />
  </a>
  <a href="https://GitHub.com/Silvio-Ronaldo/Ecoleta/stargazers/">
    <img src="https://img.shields.io/github/stars/Silvio-Ronaldo/Ecoleta?style=social" alt="This is the number of stars in this repository" />
  </a>
  <a href="https://github.com/Naereen/badges">
    <img src="https://img.shields.io/badge/badge-awesome-brightgreen" alt="Badges are awesome" />
  </a>
</p></br>


<h2>
  📋 Table of contents
</h2>
<ul>
  <li><a href="https://github.com/Silvio-Ronaldo/Ecoleta#-status">Status</a></li>
  <li><a href="https://github.com/Silvio-Ronaldo/Ecoleta#%EF%B8%8F-demonstration">Demonstration</a></li>
  <li><a href="https://github.com/Silvio-Ronaldo/Ecoleta#%EF%B8%8F-running-locally">Running Locally</a></li></br>
  <ul>
    <li><a href="https://github.com/Silvio-Ronaldo/Ecoleta#-running-the-backend-server">Running Backend Server</a></li>  
    <li><a href="https://github.com/Silvio-Ronaldo/Ecoleta#%EF%B8%8F-running-the-react-app">Running React App</a></li>
    <li><a href="https://github.com/Silvio-Ronaldo/Ecoleta#-running-the-mobile-app">Running Mobile App</a></li></br>
  </ul>
  <li><a href="https://github.com/Silvio-Ronaldo/Ecoleta#%EF%B8%8F-technologies">Technologies</a></li>
  <li><a href="https://github.com/Silvio-Ronaldo/Ecoleta#-author">Author</a></li>
  <li><a href="https://github.com/Silvio-Ronaldo/Ecoleta#%EF%B8%8F-license">License</a></li>
</ul></br>



<h2>📌 Status</h2>
<h4 align="center">🚧 Ecoleta is in development... 🚀</h4></br>



<h2>🖥️ Demonstration</h2>
<h3>Web Layout</h3>
  <p align="center">
    <img src="./assets/home.gif" alt="Ecoleta Layout" />
  </p></br>
  
<h3>Web Usage</h3>
  <p align="center">
    <img src="./assets/usage.gif" alt="Ecoleta Usage" />
  </p></br>

<h3>Mobile</h3>
  <p align="center">
    <img src="https://github.com/tgmarinho/Ecoleta/blob/master/assets/home-mobile.png?raw=true" alt="Ecoleta Mobile Screen 1" />
    <img src="https://raw.githubusercontent.com/tgmarinho/Ecoleta/65fa69a3e1fe1c02008fcee6efc34ebe2cf5a1da/assets/detalhes-mobile.svg" alt="Ecoleta Mobile Screen 2" />
  </p></br>
  


<h2>🕹️ Running locally</h2>
<h3>Prerequisites</h3>
<ol>
  <li><strong>Installing Git:</strong> You need to have Git on your machine to perform a few steps. To download Git, click <a href="https://git-scm.com/downloads">here.</a></li></br>
  <li><strong>Installing Node:</strong> To run the server you will need Node.js, to download it, click <a href="https://nodejs.org/en/">here.</a></strong></li></br>
  <li><strong>Installing Expo:</strong> To run the mobile, you need to install the Expo, click <a href="https://docs.expo.io/get-started/installation/">here.</a></li></br>
  <li><strong>Installing Yarn 1:</strong> Yarn is a package manager that you can download directly from the website by clicking <a href="https://classic.yarnpkg.com/en/docs/install#windows-stable">here.</a> If you prefer, use the NPM.</li></br>
  <li><strong>Code Editor (optional):</strong> Make sure you have a code editor of your choice. I recommend using the VS Code. If you need to, download it <a href="https://code.visualstudio.com/Download">here.</a></li>
</ol></br>

<h3>🎲 Running the backend server</h3>
<ol>
  <li>In a terminal, clone this repository:
    <p><code>git clone https://github.com/Silvio-Ronaldo/Ecoleta.git</code></p>
  </li>
  <li>Enter the project folder:
    <p><code>cd Ecoleta</code></p>
  </li>
  <li>Enter the server folder:
    <p><code>cd server</code></p>
  </li>
  <li>Install all dependencies:
    <p><code>yarn install</code> or <code>yarn</code></p>
  </li>
  <li>Start the database with Knex migrations:
    <p><code>yarn knex:migrate</code></p>
    <p><code>yarn knex:seed</code></p>
  </li>
  <li>Start the development server:
    <p><code>yarn dev</code></p>
  </li>
  <li>After these steps, the server should start at the <strong>3333</strong> port.</li>
</ol></br>


<h3>⚛️ Running the React app</h3>
<ol>
  <li>If you have already cloned the repository, proceed, otherwise, see step 1 in 'running the backend server'</li>
  <li>Enter the project folder:
    <p><code>cd Ecoleta</code></p>
  </li>
  <li>Enter the web folder:
    <p><code>cd web</code></p>
  </li>
  <li>Install all dependencies:
    <p><code>yarn install</code> or <code>yarn</code></p>
  </li>
  <li>Start the web development server:
    <p><code>yarn start</code></p>
  </li>
  <li>After these steps, the server should start at the <strong>3000</strong> port, open the browser and access <a href="http://localhost:3000">http://localhost:3000</a>.</li>
</ol></br>


<h3>📱 Running the Mobile app</h3>
<ol>
  <li>With the Expo installed, according to the documentation, follow</li>
  <li>Enter the project folder:
    <p><code>cd Ecoleta</code></p>
  </li>
  <li>Enter the mobile folder:
    <p><code>cd mobile</code></p>
  </li>
  <li>Install all dependencies:
    <p><code>yarn install</code> or <code>yarn</code></p>
  </li>
  <li>Start the mobile development server:
    <p><code>yarn start</code></p>
  </li>
  <li>After these steps, the mobile application must start on your emulator or on your device, according to your choice.</li>
</ol></br>



<h2>🛡️ Technologies</h2>
<p>The following tools were used in the development of the project: </p>

<h3>Backend</h3>
<ul>
  <li><a href="http://knexjs.org">Knex</a></li>
  <li><a href="https://expressjs.com/pt-br/">Express</a></li>
  <li><a href="https://www.typescriptlang.org">TypeScript</a></li>
  <li><a href="https://www.npmjs.com/package/multer">Multer</a></li>
  <li><a href="https://www.sqlite.org/index.html">SQLite</a></li>
  <li><a href="https://www.npmjs.com/package/cors">Cors</a></li>
  <li><a href="https://www.npmjs.com/package/ts-node-dev">ts-node-dev</a></li>
</ul></br>

<h3>Web</h3>
<ul>
  <li><a href="https://leafletjs.com">Leaflet</a></li>
  <li><a href="https://pt-br.reactjs.org">React</a></li>
  <li><a href="https://www.typescriptlang.org">TypeScript</a></li>
  <li><a href="https://github.com/axios/axios">Axios</a></li>
  <li><a href="https://react-leaflet.js.org">React-leaflet</a></li>
  <li><a href="https://react-icons.github.io/react-icons/">React Icons</a></li>
</ul></br>

<h3>Mobile</h3>
<ul>
  <li><a href="https://expo.io">Expo</a></li>
  <li><a href="https://reactnative.dev">React Native</a></li>
  <li><a href="https://www.typescriptlang.org">TypeScript</a></li>
  <li><a href="https://reactnavigation.org">React Navigation</a></li>
  <li><a href="https://github.com/react-native-maps/react-native-maps">React Native Maps</a></li>
  <li><a href="https://github.com/react-native-svg/react-native-svg">React Native Svg</a></li>
  <li><a href="https://github.com/software-mansion/react-native-reanimated">React Native Reanimated</a></li>
</ul></br>



<h2>👽 Author</h2>
<table>
  <tr>
    <td align="center"><a href="https://github.com/Silvio-Ronaldo"><img style="border-radius: 50%;" src="https://avatars.githubusercontent.com/u/48893927?v=4" width="100px;" alt="Silvio Ronaldo"/><br /><sub><b>Silvio Ronaldo</b></sub></a><br /><a href="https://github.com/Silvio-Ronaldo" title="Silvio Ronaldo">🍀</a></td>
  </tr>
</table>
<p>Leave your star, fork the project or open a pull request ❤️</p>
<p>Contact me on social networks: </p>
<p><a href="https://twitter.com/sivirinoo"><img src="https://img.shields.io/twitter/follow/sivirinoo?style=social" alt="Silvio Ronaldo's Twitter" /></a>
<a href="https://br.linkedin.com/in/silvio-ronaldo77"><img src="https://img.shields.io/badge/-Silvio-blue?style=flat&logo=Linkedin&logoColor=white" alt="Silvio Ronaldo's LinkedIn" /></a></p></br>


<h2>⚖️ License</h2>
<p><strong>Ecoleta is MIT licensed, as found in the <a href="./LICENSE">LICENSE file</a>.</strong></p>







