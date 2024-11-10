# Simple CSS Grid
A simple Flexbox based grid system for CSS.

## Instalación en Angular usando css
### npm
`npm install simple-css-grid --s`  

Agregaremos el paquete en las importaciones de Angular.json de la siguiente manera:
    `"styles": 
    [
    "./node_modules/simple-css-grid/css/simple-grid.css",
     "src/styles.css"
    ],`

## Uso en componentes. Considerando que hemos instalado Simple CSS en toda la app podremos usar en cualquier componente.
HTML:
<div class="container">
    <div class="row">
        <div class="col-6"> I'm a half width sized column </div>
        <div class="col-3 col-md-6"> I'm a quarter width sized column, but I'll be half width on 768px+ displays. </div>
        <div class="col-3"> I'm a quarter width sized column </div>
    </div>
</div>
```

## Browser support

| [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/edge/edge_48x48.png" alt="IE / Edge" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>IE / Edge | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/firefox/firefox_48x48.png" alt="Firefox" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Firefox | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/chrome/chrome_48x48.png" alt="Chrome" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Chrome | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/safari/safari_48x48.png" alt="Safari" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Safari | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/safari-ios/safari-ios_48x48.png" alt="iOS Safari" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>iOS Safari | [<img src="https://raw.githubusercontent.com/alrra/browser-logos/master/src/opera/opera_48x48.png" alt="Opera" width="24px" height="24px" />](http://godban.github.io/browsers-support-badges/)</br>Opera |
| --------- | --------- | --------- | --------- | --------- | --------- |
| IE11, Edge| last 2 versions| last 2 versions| last 2 versions| last 2 versions| last 2 versions

## Licence
Copyright 2019 Juicy Media Ltd. Code released under the [MIT License](LICENSE).
