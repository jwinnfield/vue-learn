# Techno utilisées

[VueJs](https://vuejs.org), [Vue Cli](https://cli.vuejs.org/guide/), [Vuex](https://vuex.vuejs.org/fr/), [Vue-router](https://router.vuejs.org)


# Mise en place de l'environnement

1. Installer Node.js ou NVM (version manager)

2. Installer Vue Cli

```sh
npm i -g @vue/cli

vue -version
```

3. Créer votre projet

```sh
vue create NOM_DE_MON_PROJET
or
vue create .
```

# Exercices

## VueJs
*[The bible](https://fr.vuejs.org/v2/style-guide/)*
*App.vue*
1. Faire un ```console.log(this)``` dans le created pour voir ce dont dispose un composant VueJs.

2. Afficher "Hello World !" sur la vue en utilisant la variable "message". [...doc](https://fr.vuejs.org/v2/guide/syntax.html#Texte)

3. Modifier la couleur du font au lanchement du composant. [...doc](https://fr.vuejs.org/v2/guide/instance.html#Diagramme-du-cycle-de-vie)

4. Sans modifier la variable "message", afficher "HELLO WORLD !", [...doc](https://fr.vuejs.org/v2/guide/computed.html#Proprietes-calculees)

5. Créer un bouton pour modifier la couleur de "HELLO WORLD !". [...doc](https://fr.vuejs.org/v2/guide/class-and-style.html#Liaison-de-Styles-HTML)

6. Utiliser la balise select pour afficher "Hello World !" ou "HELLO WORLD !"

7. Faire un CRUD.

8. Faire une transition en utilisant la balise transition [...doc](https://fr.vuejs.org/v2/guide/transitions.html)

9. Créer un deuxieme composant Modal et l'importer dans App.vue. Ce component doit renvoyer un evenement personnalisé @exit. [...doc](https://fr.vuejs.org/v2/guide/components-custom-events.html)

10. Créer un bouton pour afficher la modale avec la variable "message" en contenu. [...doc](https://fr.vuejs.org/v2/guide/components-slots.html)

11. Importer [axios](https://www.npmjs.com/package/axios) sur tout les composants sans utiliser d'import.


## VueX
*[Structure vueX](https://vuex.vuejs.org/fr/guide/structure.html)*
1. Afficher "Hello" en utilisant la variable msg du store. [..doc](https://vuex.vuejs.org/fr/guide/state.html)

2. Afficher "Hello" sans modifier la variable msg. [...doc](https://vuex.vuejs.org/fr/guide/getters.html)

3. Créer un formulaire pour modifier la variable msg. [...doc](https://vuex.vuejs.org/fr/guide/mutations.html)