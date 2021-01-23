# To-Do-List
Correction et amélioration d'une application de to-do list pour OpenClassrooms - Projet 8.

## Badges
![GitHub repo size](https://img.shields.io/github/repo-size/MikhaelOP9/To-Do-List)
![GitHub last commit](https://img.shields.io/github/last-commit/MikhaelOP9/To-Do-List)
![GitHub top language](https://img.shields.io/github/languages/top/MikhaelOP9/To-Do-List)
![Website](https://img.shields.io/website?url=https%3A%2F%2Fag-dev.fr%2Fopenclassrooms%2Ftodolist%2F)

![GitHub](https://img.shields.io/github/license/MikhaelOP9/To-Do-List)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/97f077c5858a4ca99ce973e1868966c9)](https://www.codacy.com/manual/MikhaelOP9/To-Do-List?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=MikhaelOP9/To-Do-List&amp;utm_campaign=Badge_Grade)

## Application détaillée
Vous trouverez ci-dessous l'arborescence représentant les principaux fichiers de l'application,
suivi de leur déscription détaillé.

```
📄 index.html

📁 js
↳ 📄 helpers.js
↳ 📄 app.js
↳ 📄 store.js
↳ 📄 model.js
↳ 📄 template.js
↳ 📄 view.js
↳ 📄 controller.js

📁 node_modules

📁 test
↳ 📄 ControllerSpec.js
↳ 📄 SpecRunner.html
```
Vous trouverez plus d'information sur l'application dans le [wiki](https://github.com/MikhaelOP9/To-Do-List/wiki/To-Do-List-d%C3%A9taill%C3%A9).

## Correction
- **typo problem :** ligne 96 controller.js : Controller.prototype.adddItem in place of Controller.prototype.addItem
- **ID conflict :** ligne 40 index.html : il manquait id="toggle-all"

## Amelioration
- **index.css :** 21	button -> font-smoothing property doesn't exist :  antialiased
- **index.css :** 34	body -> font-smoothing property doesn't exist  :  antialiased
- **index.css :** 104	.new-todo, .edit -> font-smoothing property doesn' exist  :  antialiased
- **base.js :** 145 GET http://127.0.0.1:5500/learn.json 404 (Not Found)
- **controller.js:** no need for this forEach
- Background and foreground colors do not have a sufficient contrast ratio.
- Does not have a <meta name="viewport"> tag with width or initial-scale
- Document doesn't use legible font sizes
- Tap targets are not sized appropriately
- Document does not have a meta description


##  Tests Jasmine JS
Les tests sur l'application sont réalisés avec ** Jasmine **. Vous trouverez la liste des tests dans le [wiki](https://github.com/MikhaelOP9/To-Do-List/wiki/Test-Jasmine) ou directement dans [ControllerSpec.js](test/ControllerSpec.js).

## Guide utilisateur
(https://github.com/MikhaelOP9/To-Do-List/wiki/Guide-utilisateur)

## Auteurs
Created by Oscar Godson
Refactored by Christoph Burgmer & Mikhaël Gautier

## License
This project is licensed under the MIT License - see the https://github.com/MikhaelOP9/To-Do-List/blob/main/license.md file for details.
