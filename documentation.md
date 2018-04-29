# Vus.js

## Installation

Installation [ici](https://fr.vuejs.org/v2/guide/installation.html)

## Rendu declaratif

Declarer ses donnees dans le DOM a l'aide de la syntaxe suivante :

```html
<!-- html -->
<div id="app">
  {{ message }}
</div>
```

```js
//javascript
var app = new Vue({
  el: '#app',
  data: {
    message: 'Hello Vue !'
  }
})
```
