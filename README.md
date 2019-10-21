# Ejercicio grupal - operadores lógicos

Para una web comercial, tenemos los datos de la compra de un usuario. 

En una web real, recibiríamos estos datos desde el back end. 
Por ahora, vamos a declararlos nosotras en forma de variables:  

``` 
let productoSeleccionado = "Monitor Samsung 20 pulgadas";
let precioDelProducto = 2500;
let usuarioLogueado = true;
```


Consignas
1. Mostrar en consola la siguiente información


> Gracias por elegir ${productoSeleccionado} 

> El precio del producto es $ ${precioDelProducto} 

2. Modifiquemos nuestro código para que funcione incluso si el usuario no seleccionó ningún producto. 
En ese caso, el backend nos enviaría la variable productoSeleccionado como un string vacío. 
(Nosotras por ahora vamos a tener que modificar la variable que ya declaramos). 
Si no hay ningún producto seleccionado, lo que debemos mostrar en consola es el siguiente mensaje:

> No seleccionaste ningún producto.

(En ese caso, no debemos mostrar el precio del producto). 

3. Si hay un producto seleccionado, y el precio del producto es 0, debemos mostrar en consola el siguiente mensaje 

> Gracias por elegir ${productoSeleccionado}

> ¡Tu compra está 100% bonificada! 

4. Independientemente de lo que mostremos mas arriba, si usuarioLogueado es igual a false, 
debemos mostrar el siguiente mensaje:

> Por favor, iniciá sesión para continuar. 



Prueben su codigo con los siguientes casos, y chequeen si da los resultados esperados 



CASO 1 
```productoSeleccionado = "";
precioDelProducto = 0;
usuarioLogueado = false;
```

CASO 2 
```
productoSeleccionado = "";
precioDelProducto = 0;
usuarioLogueado = true;
```
CASO 3 
```
productoSeleccionado = "Mouse HP 360";
precioDelProducto = 200
usuarioLogueado = false;
```
CASO 4 
```
productoSeleccionado = "Caramelos de cortesía";
precioDelProducto = 0;
usuarioLogueado = true;
```
