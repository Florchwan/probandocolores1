# Prueba de Colores



## Introducción
Nuestro sitio ofrece la compra de vinilos y cds. Este apunta a un público de 20 años en adelante, coleccionistas y consumidores que prefieran el formato físico.


## Integrantes

* **COLORES**: (Buenos Aires).

* **colores**: (CABA). 

- ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) `#f03c15` - ![#c5f015](https://via.placeholder.com/15/c5f015/000000?text=+) `#c5f015` - ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) `#1589F0`


```diff 
- text in red 
+ text in green 
! text in orange 
# text in gray 
@@ text in purple (and bold)@@ 
```

```diff 
- Este es un color red 
+ Este es un color green 
! Este es un color orange 
# text in green 
@@ text in purple (and bold)@@ 
```

```js
  import { Component } from '@angular/core';
  import { MovieService } from './services/movie.service';

  @Component({
    selector: 'app-root',
    templateUrl: './app.component.html',
    styleUrls: ['./app.component.css'],
    providers: [ MovieService ]
  })
  export class AppComponent {
    title = 'app works!';
  }
```
