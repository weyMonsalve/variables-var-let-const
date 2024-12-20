> QUE ES VAR?

Es un tipo de variable que sin importar donde se declare, sea dentro de un bloque o funcion particular, se podra acceder a 
esa variable var desde cualquier parte del codigo

> Si declaras una variable con var dentro de una función, será accesible solo dentro de esa función.

>Si la declaras fuera de cualquier función, será una variable global

>Se puedereasignar su valor sin problemas.

>Permite redeclarar la misma variable en el mismo ámbito, lo cual puede causar errores inesperados, por eso no es bueno utilizar la variable var

>Evita usar var en proyectos modernos, ya que su comportamiento puede ser fuente de errores y confusiones.

> Ejemplo

```javascript

console.log(x); // undefined
var x = 5;
console.log(x); // 5

```

> QUE ES LET?

 > Es un tipo de variable particular que podemos usar solo y unicamente dentro de bloque de codigo en particular, y solo se puede 
 utilizar donde se declaro

> Tiene un alcance de bloque (block scope), lo que significa que solo es accesible dentro del bloque {} donde fue declarada.

> Puedes reasignar su valor.

> No permite redeclarar la misma variable en el mismo ámbito, lo que reduce errores.

> Usa let para variables cuyo valor cambiará.

> Ejemplo

```javascript
if (true) {
    let nombre = "wbeimar";
    console.log(nombre);
}
```

> QUE ES CONST?

> Es un tipo de varible que esta pensado para definir un numero o un valor en particular se texto etc, pero una vez se define este valor 
con la vaiable const, osea que ya se a definido, no se podra cambiar ese valor en todo el codigo

> Igual que let, tiene un alcance de bloque.

> No permite reasignar valores después de la inicialización.

> No permite redeclarar la misma variable en el mismo ámbito.

> Similar a let, no puedes usarla antes de declararla.

> Usa const para valores que no necesitas reasignar, promoviendo un código más predecible.

> ejemplo

```javascript
 const email = "wmarmonsa@gmail.com";
    console.log(email);

if (true) {
  const saludo = "Hola, mundo!";
  console.log(saludo); 
}    
```

@weyMonsalve :smiley: :+1: