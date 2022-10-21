# homeys-test-front

## Exercice

Le test fonctionne par étape. Chaque étape augmente la difficulté du problème. A pars la première étape, tu n’es pas obligé de suivre les étapes dans l’ordre. Le but est d'arriver à passer le plus d'étapes possibles.
Pour le test, nous allons te fournir un projet `NuxtJS` contenant les SVG des icônes et une page `index` dans laquelle tu réaliseras les étapes. L’idée est de mettre en place le nouveau design des notifications.

Le design est trouvable ici : 
https://www.figma.com/file/xNnIJ6vaGkD95gtpMeS603/Integration?node-id=0%3A1

Tu devras nous rendre un projet Git dans lequel tu auras clone le repo :

Pour chaque étape, tu devras faire un commit avec dans le message du commit, le numéro de l’étape.

### Étapes:

1 - Afficher dans la page `index` le composant suivant. Ce composant a 4 états :
- danger (rouge)
- success (vert)
- warning (jaune)
- info (bleu)

2 - Permettre à l’utilisateur de faire disparaître la notification quand il clique sur la croix en haut à droite.

3 - Ajouter un bouton au milieu de l’écran permettant de faire apparaître des notifications en bas à gauche de l’écran.

4 - Ajouter une limite de 5 notifications affichées en bas à gauche de l’écran.

Bonus : créer un store pour sauvegarder les notifications en cours.


## Build Setup

```bash
# install dependencies
$ npm install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm run start

# generate static project
$ npm run generate
```

For detailed explanation on how things work, check out the [documentation](https://nuxtjs.org).

## Special Directories

You can create the following extra directories, some of which have special behaviors. Only `pages` is required; you can delete them if you don't want to use their functionality.

### `assets`

The assets directory contains your uncompiled assets such as Stylus or Sass files, images, or fonts.

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/directory-structure/assets).

### `components`

The components directory contains your Vue.js components. Components make up the different parts of your page and can be reused and imported into your pages, layouts and even other components.

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/directory-structure/components).

### `layouts`

Layouts are a great help when you want to change the look and feel of your Nuxt app, whether you want to include a sidebar or have distinct layouts for mobile and desktop.

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/directory-structure/layouts).

### `pages`

This directory contains your application views and routes. Nuxt will read all the `*.vue` files inside this directory and setup Vue Router automatically.

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/get-started/routing).

### `plugins`

The plugins directory contains JavaScript plugins that you want to run before instantiating the root Vue.js Application. This is the place to add Vue plugins and to inject functions or constants. Every time you need to use `Vue.use()`, you should create a file in `plugins/` and add its path to plugins in `nuxt.config.js`.

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/directory-structure/plugins).

### `static`

This directory contains your static files. Each file inside this directory is mapped to `/`.

Example: `/static/robots.txt` is mapped as `/robots.txt`.

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/directory-structure/static).

### `store`

This directory contains your Vuex store files. Creating a file in this directory automatically activates Vuex.

More information about the usage of this directory in [the documentation](https://nuxtjs.org/docs/2.x/directory-structure/store).
