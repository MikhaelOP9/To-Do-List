# To-Do-List
Correction and improvement of a to-do list app for OpenClassrooms. Projet 8 - OpenClassrooms

## Badges
![GitHub repo size](https://img.shields.io/github/repo-size/MikhaelOP9/To-Do-List)
![GitHub last commit](https://img.shields.io/github/last-commit/MikhaelOP9/To-Do-List)
![GitHub top language](https://img.shields.io/github/languages/top/MikhaelOP9/To-Do-List)
![Website](https://img.shields.io/website?url=https%3A%2F%2Fag-dev.fr%2Fopenclassrooms%2Ftodolist%2F)

![GitHub](https://img.shields.io/github/license/MikhaelOP9/To-Do-List)
[![Codacy Badge](https://api.codacy.com/project/badge/Grade/97f077c5858a4ca99ce973e1868966c9)](https://www.codacy.com/manual/MikhaelOP9/To-Do-List?utm_source=github.com&amp;utm_medium=referral&amp;utm_content=MikhaelOP9/To-Do-List&amp;utm_campaign=Badge_Grade)
[![time tracker](https://wakatime.com/badge/github/MikhaelOP9/To-Do-List.svg)](https://wakatime.com/badge/github/MikhaelOP9/To-Do-List)

## Detailed App
You will find below the tree structure of the application's main files 
followed by their detailed description. 

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
If you want more informations about the app you can see it on [wiki](https://github.com/MikhaelOP9/To-Do-List/wiki/Detailed-App).

## Fixes
- **typo problem :** line 96 controller.js : Controller.prototype.adddItem in place of Controller.prototype.addItem
- **ID conflict :**

## Improvements
- **index.css :** 21	button -> font-smoothing property doesn't exist :  antialiased
- **index.css :** 34	body -> font-smoothing property doesn't exist  :  antialiased
- **index.css :** 104	.new-todo, .edit -> font-smoothing property doesn' exist  :  antialiased
- **base.js :** 145 GET http://127.0.0.1:5500/learn.json 404 (Not Found)
- Background and foreground colors do not have a sufficient contrast ratio.
- Does not have a <meta name="viewport"> tag with width or initial-scale
- Document doesn't use legible font sizes
- Tap targets are not sized appropriately
- Document does not have a meta description


## App's Tests
Tests on the Application are performed using **Jasmine**. You can find the list in the [wiki](https://github.com/MikhaelOP9/To-Do-List/wiki/App's-tests) or directly in the [ControllerSpec.js](test/ControllerSpec.js).

## Authors
Created by Oscar Godson
Refactored by Christoph Burgmer & Mikhaël Gautier

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
