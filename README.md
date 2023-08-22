# Introduction 

Ce projet est une application Web qui permet aux utilisateurs de créer et de gérer des calendriers. L'application est écrite en JavaScript et utilise React et Next.js.

L'application est conçue pour être simple à utiliser et à naviguer. Les utilisateurs peuvent facilement créer des calendriers, ajouter des événements à leurs calendriers, partager leurs calendriers avec d'autres utilisateurs et exporter leurs calendriers au format iCal.

L'application est également conçue pour être collaborative. Les utilisateurs peuvent facilement partager leurs calendriers avec d'autres utilisateurs, ce qui permet de collaborer plus facilement sur des projets.

L'application permet également de garder une trace de événements de ces utilisateurs et de rester organisés. L'application est facile à utiliser et à naviguer, et elle est conçue pour être collaborative.

En plus des fonctionnalités mentionnées ci-dessus, l'application dispose également des fonctionnalités suivantes :

* Intégration de l'API Google Calendar
* Importation et exportation des calendriers
* Notifications pour les événements à venir
* Partage des calendriers avec d'autres utilisateurs

L'application est une application puissante et polyvalente qui peut être utilisée par les personnes de tous les horizons. Si vous êtes à la recherche d'une application pour vous aider à garder une trace de vos événements et à rester organisé, l'application est la solution idéale pour vous.

Merci pour votre intérêt pour notre projet!

# Biblios et Framework exploité(e)s

Les bilbiothéques/frameworks utilisés pour mettre en oeuvre le projet comprend la liste suivante :

| <img src="https://miro.medium.com/v2/resize:fit:1200/1*y6C4nSvy2Woe0m7bWEn4BA.png" alt="Description de l'image" width="300" > | React est une bibliothèque JavaScript pour créer des interfaces utilisateur. C'est une bibliothèque populaire et bien documentée, ce qui en fait un choix idéal pour développer des projets d'interface utilisateur. |
|---|---|

| <img src="https://dev-to-uploads.s3.amazonaws.com/uploads/articles/rd3omc5vp71r5k9z69b4.png" alt="Description de l'image" width="250" > | Next.js est un framework React qui permet de créer des applications Web statiques et dynamiques. Il est populaire pour sa vitesse, sa scalabilité et sa facilité d'utilisation. |
|---|---|

| <img src="https://blog.logrocket.com/wp-content/uploads/2021/08/default-styling-react-calendar.png" alt="Description de l'image" width="300" > | Calendrier React est une bibliothèque React qui permet de créer des calendriers. C'est une bibliothèque populaire et bien documentée, ce qui en fait un choix idéal pour développer des projets de calendrier. |
|---|---|

| <img src="https://ucarecdn.com/95a1afed-cc7c-45d8-b74e-9c3adc6b9430/-/format/auto/-/progressive/yes/-/preview/2048x2048/" alt="Description de l'image" width="400" > | date-fns est une bibliothèque JavaScript qui fournit une variété de fonctions pour manipuler les dates et les heures. C'est une bibliothèque populaire et bien documentée, ce qui en fait un choix idéal pour développer des projets qui nécessitent de manipuler les dates et les heures. |
|---|---|

| <img src="https://miro.medium.com/v2/resize:fit:640/0*LPvu8HCNQfYNPK7I" alt="Description de l'image" width="400" > | react-helmet est une bibliothèque React qui permet d'ajouter des métadonnées à la page HTML. C'est une bibliothèque populaire et bien documentée, ce qui en fait un choix idéal pour développer des projets qui nécessitent d'ajouter des métadonnées à la page HTML. |
|---|---|

| <img src="https://res.cloudinary.com/practicaldev/image/fetch/s--Fp3q-3G9--/c_imagga_scale,f_auto,fl_progressive,h_420,q_auto,w_1000/https://dev-to-uploads.s3.amazonaws.com/i/ke6hqywlnr8b3r896hii.png" alt="Description de l'image" width="350" > | react-icons est une bibliothèque React qui fournit une variété d'icônes. C'est une bibliothèque populaire et bien documentée, ce qui en fait un choix idéal pour développer des projets qui nécessitent d'utiliser des icônes. |
|---|---|

| <img src="https://miro.medium.com/v2/resize:fit:4800/format:webp/1*vD4mY6iEQ34HTcAYyPTlnw.png" alt="Description de l'image" width="350" > | react-query est une bibliothèque React qui permet de gérer l'état des données. C'est une bibliothèque populaire et bien documentée, ce qui en fait un choix idéal pour développer des projets qui nécessitent de gérer l'état des données. |
|---|---|

| <img src="https://miro.medium.com/v2/resize:fit:4800/format:webp/0*Zb9Uoad33rLb7v03.png" alt="Description de l'image" width="350" > | react-router-dom est une bibliothèque React qui permet de gérer l'itinéraire d'une application Web. C'est une bibliothèque populaire et bien documentée, ce qui en fait un choix idéal pour développer des projets qui nécessitent une navigation entre différentes pages. |
|---|---|

| <img src="https://img1.daumcdn.net/thumb/R1280x0/?scode=mtistory2&fname=https%3A%2F%2Fblog.kakaocdn.net%2Fdn%2Fb8oEEQ%2FbtqCB81szbm%2FoQ0nb1HQG4GGidFtKjJmn1%2Fimg.png" alt="Description de l'image" width="300" > | styled-components est une bibliothèque React pour créer des styles CSS. C'est une bibliothèque populaire et bien documentée, ce qui en fait un choix idéal pour développer des projets qui nécessitent des styles CSS. |
|---|---|

| <img src="https://miro.medium.com/v2/resize:fit:720/format:webp/1*oPL8C-i04sqAUoOS_da9aA.jpeg" alt="Description de l'image" width="400" > | tailwindcss est une bibliothèque CSS qui fournit une variété de classes CSS prêtes à l'emploi. C'est une bibliothèque populaire et bien documentée, ce qui en fait un choix idéal pour développer des projets qui nécessitent d'utiliser des classes CSS prêtes à l'emploi. |
|---|---|

# Organisation et Arborescence du repos

voici l'arborescence complète du projet :

```
.
├── README.md
├── .env.example
├── .eslintrc.js
├── .gitignore
├── .prettierrc
├── next.config.js
├── package.json
├── public
│   └── index.html
├── src
│   ├── components
│   │   ├── Calendar
│   │   └── Event
│   ├── pages
│   │   ├── calendar
│   │   │   ├── index.js
│   │   │   └── styles.css
│   │   └── events
│   │       ├── index.js
│   │       └── styles.css
│   └── styles
│       └── index.css
└── test
    └── unit
        └── calendar
            ├── calendar.test.js
            └── event.test.js
```

# Mise en déploiement coté Dev :

## Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

### Available Scripts

In the project directory, you can run:

#### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

#### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

#### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

#### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

### Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

#### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

#### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

#### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

#### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

#### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

#### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)

Test Website Worked Fine.
