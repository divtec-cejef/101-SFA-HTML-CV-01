# Entraînez-vous en structurant votre CV

**À vous de jouer !** Pour vous entraîner, réalisez cet exercice étape par étape.

Une fois que vous avez terminé, vous pouvez comparer, auto-évaluer, votre travail avec ma **Check-list**

## Contexte

Vous cherchez du travail et vous décidez de créer votre CV en ligne.
Pour cela, vous allez devoir créer votre première page HTML.

### Exemples de solutions
* https://divtec-cejef.github.io/101-SFA-HTML-CV-01/
* https://static.oc-static.com/activities/198/evaluation_resources/structurez-votre-cv_exemple-2019-01-03T081950.zip

## Avant de commencer

Suivre les cours Treehouse suivants
  1. [Introduction to HTML and CSS (2h)](https://teamtreehouse.com/library/introduction-to-html-and-css)
  2. [HTML Basics (2-3h)](https://teamtreehouse.com/library/html-basics-2)

OU vou pouvez réaliser les 6 chapitres de la [Partie 1 - Maîtrisez les bases de HTML5 ](https://openclassrooms.com/fr/courses/1603881-creez-votre-site-web-avec-html5-et-css3/8061253-tirez-un-maximum-de-ce-cours) du cours [Créez votre site web avec HTML5 et CSS3](https://openclassrooms.com/fr/courses/1603881-creez-votre-site-web-avec-html5-et-css3)

	
```
Partie 1 - Maîtrisez les bases de HTML5
---------------------------------------
  1. Tirez un maximum de ce cours
  2. Comprenez la différence entre HTML et CSS
  3. Créez votre première page web en HTML
  4. Organisez votre texte
  5. Créez un lien hypertexte en HTML
  6. Insérez des images
```

## Votre mission

* Étape 1 : Créez un fichier `index.html`.
* Étape 2 : Lire et réaliser les étapes de l'article [Créer une page web de base avec HTML & CSS](https://fallinov.medium.com/cr%C3%A9er-un-page-web-de-base-avec-html-css-2c702e069a0c) 
* Étape 3 : Découper le contenu de votre page avec un entête, un contenu principal et un pied de page.
* Étape 4 : Dans l'entête, ajoutez une photo miniature sur laquelle on pourra cliquer pour afficher l'image dans un nouvel onglet.
* Étape 5 : Toujours dans l'entête, créer un menu de navigation contenant les trois liens vers les sections de votre page. Laissez les liens vides pour le moment: `<a href="#">Mon Expérience</a>`
  * Mon expérience
  * Mes compétences
  * Ma formation
* Étape 6 : Dans le contenu principal, ajoutez votre nom et votre prénom dans un titre de niveau 1.
* Étape 7 : À la suite du titre principal, ajoutez trois sections avec un titre de niveau 2.
  * Mon expérience (vous pouvez en inventer 😅)
  * Mes compétences (ce que vous maîtrisez en informatique)
  * Ma formation (Votre parcours scolaire)
  * _Chaque section contient un paragraphe ou une liste à puces._
* Étape 8 : Ajouter une ancre, en mettant ajoutant un attribut `id` aux titres de niveau 2.
```html
<h2 id="experience">Mon Expérience de fou</h2>
```
* Étape 9 : Modifier les liens de votre menu pout qu'ils pointent vers vos `id`
```html
<a href="#experience">Mon Expérience</a>
```
* Étape 10 : Ajouter le copyright, l'année et votre adresse e-mail dans le pied de page.

## Check-list

✅ La page HTML est un CV.

✅ On trouve votre nom et prénom dans l'onglet de la page.

✅ L'icône de la page s'affiche dans l'onglet.

✅ Le contenu de la page contient un entête `<header`> un contenu principal `<main>` et un pied de page `<footer>`.

✅ Dans l'entête, une photo miniature cliquable affiche la photo dans un nouvel onglet.

✅ Le menu de navigation vous permet d'atteindre les trois sections de votre CV (expérience, compétences, formation).

✅ Le titre principal est un `<h1>` et contient votre nom et prénom.

✅ Votre page a trois sections avec un titre `<h2>` :
* Mon expérience
* Mes compétences
* Ma formation

✅ Chaque section contient au minimum un paragraphe ou une liste à puce.

✅ Dans le pied de page on voit '©2023' suivi de votre adresse e-mail.

✅ Votre e-mail est un lien cliquable qui permet de vous écrire un e-mail.
