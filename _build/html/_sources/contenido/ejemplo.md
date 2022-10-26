# Ejemplo práctico

## Creación de proyecto Ecore Model

>Creamos un nuevo proyecto accediento al menú `File > New > Other..`

![Proyecto Ecore](img/ejemplo/001.png)

>Continuamos y elegimos la opción `Eclipse Modeling Framework` y dentro del mismo el tipo `Ecore Modeling Project` y damos clic en `Next >`

![Proyecto Ecore](img/ejemplo/002.png)

>Colocamos un nombre a nuestro poryecto y damos click en `Next >`

![Proyecto Ecore](img/ejemplo/003.png)

>Damos click en `Next >`

![Proyecto Ecore](img/ejemplo/004.png)

>Damos click en `Finish`

![Proyecto Ecore](img/ejemplo/005.png)

>Arrastramos y soltamos de la Paleta el componente que corresponde para crear 2 clases `Estudiante` y `Matrícula`, agregamos un atributo a cada clase e incluímos la relación que corresponde de `1 estudiante puede tener de 0 a muchas matrículas`

![Proyecto Ecore](img/ejemplo/006.png)

>Del `Model Explorer` abrimos el archivo `.genmodel` que se encuentra dentro de la carpeta `model`

![Proyecto Ecore](img/ejemplo/007.png)

>Damos clic derecho sobre el primer elemento del árbol `Dsdm_proyecto_01` y damos clic en la opción `Generate Model Code`, para de esta forma el plugin nos genere el código fuente en el directorio `src-gen`

![Proyecto Ecore](img/ejemplo/008.png)

>Damos clic derecho sobre el primer elemento del árbol `Dsdm_proyecto_01` y damos clic en la opción `Generate Edit Code`, para de esta forma el plugin nos genere un nuevo proyecto con la extensión `.edit`

![Proyecto Ecore](img/ejemplo/009.png)

>Damos clic derecho sobre el primer elemento del árbol `Dsdm_proyecto_01` y damos clic en la opción `Generate Editor Code`, para de esta forma el plugin nos genere un nuevo proyecto con la extensión `.editor`

![Proyecto Ecore](img/ejemplo/010.png)

## Creación de nuevo proyecto para integrar y validar el modelo creado

>Ahora damos clic derecho sobre el tercer proyecto con extensión `.editor` y elegimos la opción `Run As` y a continuación damos clic en la opción `Eclipse Application`, esto nos generará una nueva ejecución de eclipse con la integración de nuestro modelo.

![Proyecto Ecore](img/ejemplo/011_1.png)

![Proyecto Ecore](img/ejemplo/011_2.png)

>Dentro de la nueva instancia de eclipse creamos un nuevo proyecto de tipo `Java Project`.

![Proyecto Ecore](img/ejemplo/012.png)

>Damos clic derecho sobre el proyecto ya vamos a agregar un nuevo elemento al mismo para ello nos vamos a las opciones `New > Other...`.

![Proyecto Ecore](img/ejemplo/013.png)

>Dentro de la opción `Example EMF Model Creation Wizards` elegimos la opción `Dsdm_proyecto_01 Model`, que corresponde a nuestro proyecto inicial y damos clic en `Next >`.

![Proyecto Ecore](img/ejemplo/014.png)

>Ahora nos pregunta que modelos deseamos crear, podemos elegir entre cualquiera de los creamos en el proyecto original, en este caso elegiremos `Estudiante` y damos clic en `finish`.

![Proyecto Ecore](img/ejemplo/015.png)

>Ahora dentro del archivo creado damos clic derecho en el modelo `Estudiante` y podremos apreciar que nos permite crear elementos de tipo `Matricula` esto nos permite apreciar que nuestro modelo del proyecto original es correcto y que podemos crear muchos objetos de tipo `Matricula` para el modelo `Estudiante`.

![Proyecto Ecore](img/ejemplo/016.png)

![Proyecto Ecore](img/ejemplo/017.png)