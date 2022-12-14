# STORYBOOK

## _Librairie de components et leurs stories_

&nbsp;&nbsp;

[![N|Solid](https://skillicons.dev/icons?i=github,bootstrap,css,html,js,react,styledcomponents,vscode)](https://skillicons.dev)

&nbsp;&nbsp;

**STORYBOOK** s'éxécute parallèlement à notre application en mode développement. Il nous aide à construire des composants UI(User Interface) qui sont isolés de la logique applicative et du contexte de notre application.
&nbsp; 
**STORYBOOK** est pour React et il exite d'autres éditions pour Vue, Angular ou Svelte.
&nbsp;
Nous avons 11 components décrit comme suit : 
- **Badge** : Le badge apparaît sous différentes formes (carré ou arrondi) à proximité des notifications ou des avatars des utilisateurs avec un attrait accrocheur, affichant généralement le nombre de messages non lus.
```
<Badge
  shape="circle"
  size="small"
/>
```
&nbsp; 
- **Button** : Un bouton signifie une opération (ou une série d'opérations). Cliquer sur un bouton déclenchera la logique métier correspondante.On peut changer la couleur de fond du bouton, sa dimension, et la couleur du texte écrit sur le bouton.
```
<Button
  backgroundColor="#002c88"
  color="#fff"
  width="200px"
/>
```
&nbsp;
- **Card** : Une carte peut être utilisée pour afficher un contenu lié à un seul sujet. Nous pouvons changer la largeur, la couleur de fond ainsi que la couleur du texte.
```
<Card
  backgroundColor="blue"
  color="#fff"
  width="400px"
/>
```
&nbsp;
- **Carousel** : Il est utilisé pour regrouper des images ou des cartes. On peut changer sa dimension en hauteur et en largeur, sa couleur de fond ainsi que la couleur du texte.
```
<Carousel
  background="#00ffff"
  color="#fff"
  height="180px"
  lineHeight="160px"
  textAlign="center"
  width="600px"
/>
```
&nbsp;
- **Collection** : Permet d'afficher différentes images. Elles peuvent avoir différentes dimensions.
```
<Collection
  imagesurl=
    'assets/macareux.jpg
     assets/img/sterne_artique1.jpg
     assets/img/sterne_artique2.jpg'
  width={200}
/>
```
&nbsp;
- **Modal** : Permet d'afficher une simple boite de dialogue. Le bouton peut changer de couleur de fond ainsi que la couleur du texte.
```
<Modal
  background="#ff0000"
  color="#ffffff"
/>
```
&nbsp;
- **Navbar** : La barre de navigation permet aux utilisateurs de se déplacer rapidement et efficacement sur le site. On peut changer la couleur de fond ainsi que la couleur du texte.
```
<NavBar
  background="#d9534f"
  color="#ffffff"
/>
```
&nbsp;
- **Popover** : Un menu contextuel simple pour fournir des informations ou des opérations supplémentaires. Le bouton peut changer de couleur ainsi que le texte et la couleur du texte.
```
<Popover
  backgroundColor="#c9082a"
  color="#fff"
  shape="round"
  width="400px"
/>
```
&nbsp;
- **Progress** : Cest une barre de progression en cercle ou en horizontale qui affiche le flux d'opération. On peut varier les couleurs de fond.
```
<Progress
  background="#d9534f"
  width="400px"
/>
```
&nbsp;
- **Spinner** : Permet d'indiquer à l'utilisateur lorsqu'une page attend des données asynchrones. La couleur de fond du contenu de description peut changer.
```
<Spinner
  background="#5cb85c"
  size="small"
/>
```
&nbsp;
- **Table** : Permet d'afficher un tableau de données avec des boutons à cocher et une pagination. La dimension peut être changée également.
```
<Table
  selectionType="checkbox"
  width="500px"
/>
```

&nbsp;&nbsp;
 
# 📒 Fonctionnalités
Les commandes pour vérifier rapidement que les différents environnements de notre application fonctionnent correctement:

## 🛠 - Exécutez le test (Jest) dans un terminal:
```sh
yarn test --watchAll
```
## 🚀 - Démarrer l'explorateur de composants sur le port 6006 :
```sh
yarn storybook
```
## 🚇 - Exécutez l'application frontale proprement dite sur le port 3000 :
```sh
yarn start
```

&nbsp;&nbsp;

# 🏅 Techno
Pour ce projet, nous avons utilisé les `open sources ` suivantes:

- [React] - Bibliothéque javascript pour la création des composants 

- [React-bootstrap-storybook] - Bootstrap de React!

- [Create-React-App] - Système de compilation

- [Storybook] - Test Jest

&nbsp;&nbsp;


# ✨ Installation

Storybook requiert [storybook.js](https://storybook.js.org/).

Voici les étapes pour configurer le processus de compilation dans votre environnement. Pour commencer, nous allons utiliser Create React App (CRA) pour mettre en place notre système de compilation, et ensuite ajouter Storybook et l'outil de test Jest dans notre application. Exécutons les commandes suivantes:

## Créer notre application:
```sh
npx create-react-app taskbox

cd taskbox
```

## Ajouter Storybook:
```sh
npx storybook init
```

&nbsp;&nbsp;


# 🔗 Plugins

| Plugin | README |
| ------ | ------ |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |

&nbsp;&nbsp;&nbsp;



# 👏 Contributions
Si vous désirez nous encourager pour la suite du développement de cette application vous pouvez nous payer un café!!!!

&nbsp;&nbsp;


# 👥 Communauté
Storybook est une communauté de développeurs que vous retrouverez sur les réseaux comme :

- Tweeting via [@storybookjs](https://twitter.com/storybookjs)

- Chatting on [Discord](https://discord.com/invite/storybook)

&nbsp;&nbsp;



# 📝 License

MIT

**Free Software, Hell Yeah!**