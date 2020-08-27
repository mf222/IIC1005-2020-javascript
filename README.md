# IIC1005-2020-javascript

Repositorio para clase del 27 de Agosto sobre Javascript.

La carpeta `example` contiene el archivo `index.html` sobre el cual se desarrollarán los ejercicios.

## Resolución ejercicios

Esta es una de las soluciones posibles. No es la única:

**1. ¿Cómo podríamos mostrar el nodo `<title>` del documento?**

R: > 
```
let node = document.documentElement;
node.firstChild.firstElementChild;
```

**2. ¿Cómo podríamos mostrar el elemento “simple” del documento? (navegando el árbol)**

R: > 
```
let node = document.documentElement;
node.firstElementChild.nextElementSibling.firstElementChild.nextElementSibling.firstElementChild.textContent;
```

Existen otras formas más directas, que puedes investigar ;)

**3. ¿Cómo agregamos un texto?**

R: > _Respuesta del Material Denis Parra, año 2018_
```
var h=document.createElement("H1")
var t=document.createTextNode("Hello World");
h.appendChild(t);
```

