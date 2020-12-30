# Apuntes Proyecto Bienes Raíces (Udemy)

***blockquote***
Etiqueta para cita

***a***
Etiqueta para enlace

***target = _blank*** dentro de ***a*** =
_blank  abre enlace en otra pestaña.

----

Casi no se usan

***em***
Etiqueta para letras inclinadas

***b***
Etiqueta letra bold

***strong***
Etiqueta para resaltar para buscadores

----
Entidades HTML

***\&commat;***
para escribir un arroba

***\&copy;***
para escribir signo copyright

----

***control+d*** para seleccionar elementos iguales en visual studio code

***section***
Contenedor al cambiar de contenido, el primer hijo tiene que ser un titulo.

***article***
Para agrupar entrada de blog

(../img/header.jpg) 
los 2 puntos y la diagonal son para indicar que se entrara en la carpeta img


### Seudo-selectores de css

Por ejemplo **last-of-type** para seleccionar el ultimo elemento de un contenedor.
````css
/* navegacion */
.navegacion a {
    color: white;
    margin-right: 20px;
    text-decoration: none;
}

.navegacion a:last-of-type {
    margin-right: 0px;
}

````

Otro ejemplo es **hover**

### normalize 

https://necolas.github.io/normalize.css/

Es una libreria para normalizar las fuentes de fault en todos los navegadores.


### Usar rem en lugar de px

Para usar los rems de manera mas sencilla hay que hacer lo siguiente en el archivo de estilos css.

````css
html{
    font-size: 62.5%; /*reset para REMS -62.5% = 10px de 16px, es decir 1 REM son 10px*/
}
````

### calc

Usar **calc( )** para hacer operaciones matematicas en css

````css
.icono {
    flex-basis: calc (33.3% - 1rem);
}
````
