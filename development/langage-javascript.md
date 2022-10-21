# Langage Javascript

> ❌ A travailler

> ✔️ Auto validation par l'étudiant 

## 🎓 J'ai compris et je peux expliquer

- les `structures` de base du langage  ✔️JavaScript est un langage de programmation qui ajoute de l'interactivité à votre site web (par exemple : jeux, réponses quand on clique sur un bouton ou des données entrées dans des formulaires, composition dynamique, animations)
- 
- les normes `ecmascript` ✔️ ECMAScript est un ensemble de normes concernant les langages de programmation de type script et standardisées par Ecma International dans le cadre de la spécification ECMA-262.
- 
- l'utilisation de l'`asynchrone`✔️ La programmation asynchrone est une technique qui permet à un programme de démarrer une tâche à l'exécution potentiellement longue et, au lieu d'avoir à attendre la fin de la tâche, de pouvoir continuer à réagir aux autres évènements pendant l'exécution de cette tâche. Une fois la tâche terminée, le programme en reçoit le résultat.
- 
- les spécifités du mot-clef `this` ✔️ En JavaScript, le mot-clé this se comporte légèrement différemment des autres langages de programmation. Son comportement variera également légèrement selon qu'on utilise le mode strict ou le mode non-strict. Dans la plupart des cas, la valeur de this sera déterminée à partir de la façon dont une fonction est appelée.

## 💻 Je code en Javascript ✔️

### Un exemple de code commenté ✔️

```javascript
//Find the unique string

const arr = ['abc', 'acb', 'bac', 'foo', 'bca', 'cab', 'cba']

function findUniq(a) {
    let newArr = a.map(a => { return [...new Set(a.toLowerCase())].sort().join('') }); //remove alphabet repeted 
    for (let i = 0; i < newArr.length; i++) {
        if (newArr.indexOf(newArr[i]) === newArr.lastIndexOf(newArr[i]))
            return a[i]
    }
}

console.log(findUniq(arr));

```


### Utilisation dans un projet  ✔️

[lien github]([...](https://github.com/amirhatam/loisir))

Description :

Une plateforme de différent Calculatrices et jeux vidéos.

### J'ai utilisé ce langage en production  ✔️

[lien du projet]([...](https://portfolio-amir-hatam-dev.netlify.app/))

Description :
✔️ J'ai utilisé ce langage en production 15 projets qui ont déjà déployé dans mon portfolio.  

### J'ai utilisé ce langage en environement professionnel  ✔️

Description :

✔️ Pendant mon stage j'ai créé un site web statique et dynamique pour l'association Azimuto, dans ce projet j'ai créé les fonctionnalités pour que administrateur puisse modifier certaines parties de site web.

## 🌐 J'utilise des ressources

### Titre

- lien
- https://developer.mozilla.org/fr/docs/Web/JavaScript
- description
- MDN Web Docs est un dépôt de documentation et une ressource d'apprentissage pour les développeurs web utilisés par Mozilla, Microsoft, Google et Samsung.

## 🚧 Je franchis les obstacles

### Point de blocage  ✔️

Description:
 
 
Plan d'action : (à valider par le formateur)

- action 1  ❌ / ✔️

- action 2 ❌ / ✔️
- ...

Résolution :

## 📽️ J'en fais la démonstration

- J'ai ecrit un [tutoriel](...) ❌ / ✔️
- J'ai fait une [présentation](...) ❌ / ✔️

