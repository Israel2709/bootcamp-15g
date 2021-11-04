# Quizz CSS y HTML

1. Escribe el selector de CSS correspondiente a los siguientes enunciados:
    - Selecciona todos los elementos del tipo párrafo que tengan la clase main-text.
    - Selecciona todos los elementos de lista pares dentro de una lista no ordenada
    - Selecciona los links visitados dentro de una barra de navegación 
    - Selecciona la imagen que sea descendiente inmediato de una card sobre la que se coloca el puntero del mouse
    - Selecciona la primer sección que se enuentre dentro de una etiqueta main
    - Selecciona cualquier elemento que incluya en su classlist el texto "btn"
    - Selecciona todos los botones excepto aquellos que sean el último hijo

2. Describe qué elemento será seleccionado con base en los siguientes selectores:
    - ```header#main-header > ul```
    - ```aside ul li:not(even)```
    - ```section#posts article:nth-of-type( odd )```
    - ```table tr td```
    - ```footer > ul li a.nav-link```
    - ```p span.text-white```
    - ```section.bg-dark p.text-white span```

3. Escribir el código necesario para crear los siguientes componentes:
    - Un botón cuyo color orginal sea azul, texto blanco, y al poner el mouse sobre de él su color de fondo cambie a peru y el texto sea negro ( el botón no debe tener borde en ninguno de ambos estados )
    - una sección que mida el ancho completo de la pantalla, la mitad de la pantalla de alto, y que dentro tenga dos imágenes cuales quiera, ambas con espacio igual entre ellas y entre los bordes de la sección

4. El ejercicio pro!
    - Crear 3 inputs de tipo radio, con las etiquetas "círculo", "cuadrado", "rectangulo", también crear un elemento que cambie de forma dependiendo del radio que esté seleccionado ( si se selecciona "círculo", el elemento debe convertirse en un círculo, y así respectivamente). 
    * Para lograr que los radiobuttons sean excluyentes, se debe colocar el atributo "name" y todos deben tener el mismo valor, p.e:
        ```
        <input type="radio" name="shape" id="forma-1">
        <input type="radio" name="shape" id="forma-2"> 
        ```


