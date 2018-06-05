Variables visuales
~~~~~~~~~~~~~~~~~~

Definición
""""""""""

Entendemos como variable visual::

    Cualquier aspecto que puede hacer diferir una marca o señal de otra

Las variables
"""""""""""""

En el lenguaje gráfico actual se reconocen las siguientes variables

* Posición
* Forma
* Orientación
* Tamaño
* Color

  + Tono
  + Saturación
  + Valor
  + Transparencia

* Estructura del relleno

  + Textura
  + Densidad
  + Módulo
  + Estructura

* Foco
* Resolución


Características
"""""""""""""""

Estas variables nos permiten a su vez representar una serie de características:

Selectiva
   el cambio nos permite destacar elementos sobre un grupo

Asociativa
   el cambio nos permite percibir elementos como parte de un grupo

Orden
   el cambio permite apreciar un cambio en el ordenamiento de los elementos

Cuantitativa
   el cambio permite realizar apreciaciones numéricas

Elementos del diseño cartográfico
"""""""""""""""""""""""""""""""""

Por otro lado siempre entenderemos que vamos a usar las variables visuales
sobre tres tipos de elementos:

* Puntos
* Líneas
* Áreas

Aunque con herramientas como  `Carto <https://abel.carto.com/builder/28d1dd06-2d85-11e6-ae20-0ecd1babdde5/embed?state=%7B%22map%22%3A%7B%22ne%22%3A%5B38.535536074264044%2C-0.12233018875122072%5D%2C%22sw%22%3A%5B38.54224123392013%2C-0.11242747306823732%5D%2C%22center%22%3A%5B38.53888873222173%2C-0.11737883090972902%5D%2C%22zoom%22%3A17%7D%2C%22widgets%22%3A%7B%222b60c32f-7959-4278-b1ac-de3614381d67%22%3A%7B%22normalized%22%3Atrue%7D%2C%221e701f3d-ac23-4188-b51e-c02c3ff2abd1%22%3A%7B%22normalized%22%3Atrue%7D%7D%7D>`_
o `Kepler.gl <https://uber.github.io/kepler.gl/>`_ hay que empezar a pensar
también en volúmenes.

.. figure:: ../img/010020_018.jpg
   :alt: Mapa de datos de la producción forestal en Europa

   La correcta proporción de los símbolos ayuda a la interpretación.


Posición
""""""""

La prima-ballerina en el ballet los Mapas.

En general es más bien poco *"variable"*

.. figure:: ../img/010020_001.jpg
   :alt: Captura de pantalla de un mapa con Londres mal posicionado

   La "Posición" es la variable reina de los mapas

Forma
"""""

La base de la simbología.

.. figure:: ../img/010020_002.jpg
   :alt: Captura de pantalla de un grupo de iconos

   Grupo de iconos Maki diseñado por Mapbox

Tiene menos sentido aplicado a Líneas y a Áreas que a Puntos

Aunque ...

.. figure:: ../img/010020_003.jpg
   :alt: Captura de pantalla de un Cartograma

   Distribución de la población en España

Orientación
"""""""""""

Algunos autores la consideran parte de la forma.

No tiene mucho sentido en Líneas.

Pero **ojo** con los posibles errores de interpretación.

.. figure:: ../img/010020_004.jpg
   :alt: Captura de pantalla de un error de Orientación

   ¿Pinos o flechas?


Tamaño (o grosor)
"""""""""""""""""

Esta es una variable que solo se aplica a Puntos y Líneas.

Su uso principal es para representar **Orden**.

Un error muy común es intentar representar **Cantidad** con áreas y volúmenes

.. figure:: ../img/010020_009.jpg
   :alt: Figura con la propoción entre superficie y área

   Es muy dificil comparar a ojo tamaños de superficies y de áreas

*Cuidado* Las variaciones de tamaño hay que representarlas bien para que sean
significativas.

.. figure:: ../img/010020_008.jpg
   :alt: Mapa de datos de la producción forestal en Europa

   La correcta proporción de los símbolos ayuda a la interpretación.

La mejor proporción que se puede usar suele ser el número áureo.

.. figure:: ../img/010020_017.jpg
   :alt: Imagen con proporciones en el radio y el superficie

   Los círculos rojos tienen una progresión en el radio y los azules en la
   superficie.


Color
"""""

El pollo del arroz con pollo de los mapas.


.. figure:: ../img/010020_005.jpg
   :alt: Fotografía de un plato de arroz con pollo

   El color es como el Pollo

Es especialmente poderoso y generalmente suele estar mal usado.

Tradicionalmente el color tiene tres componentes

.. figure:: ../img/010020_006.jpg
   :alt: Imagen de los componentes clásicos del color

   Tono, valor y saturación, los componentes del color

Aunque en tiempos modernos se le añade un componente más: la transparencia


.. figure:: ../img/010020_007.jpg
   :alt: Imagen de la transparencia de un tono

   Transparencia (u opacidad) de un color

Los componentes del color se aplican por igual a Puntos, Líneas y Áreas, pero
aplicarlos bien ya es otro tema.

Algunos errores con el color
''''''''''''''''''''''''''''

El primer error que se suele cometer es usar **demasiado**::

    No más de 6 o 7 colores diferentes en un mapa


.. figure:: ../img/010020_014.jpg
   :alt: Imágen con 11 colores diferentes

   Puede que no tengamos más remedio que hacerlo... pero protestemos y
   rechinemos de dientes.

El segundo: No todos los componentes sirven para representar todas las
características.

.. figure:: ../img/010020_015.jpg
   :alt: Mapa de coropletas con datos del paro

   Parece que en Castilla se produce mucho un fenómeno... pero lo que sobretodo
   hay son grandes superficies en los municipios.


El tercero: Se debería siempre tener en cuenta que se va a hacer con el mapa y
elegir el sistema de color adecuado:

.. figure:: ../img/010020_016.jpg
   :alt: Imagen de composiciones de color CMYK y RGB

   Imprimirlo -> CMYK / Visualizarlo en pantalla -> RGB/Hex


Estructura del relleno
""""""""""""""""""""""

Los componentes de la variable dependen del autor que se consulte.

Solo se aplica a elementos que se *rellenan*, preminentemente Áreas.

.. figure:: ../img/010020_010.jpg
   :alt: Imagen con las componentes de la Estructura del relleno

   Textura, densidad, módulo y estructura conformar los componentes del relleno

En líneas puede ser un poco más complejo de *ver*

.. figure:: ../img/010020_011.jpg
   :alt: Imagen con distintas estructuras de relleno en líneas

   Estructuras de relleno en líneas.

Foco
""""

Literalmente *Lo definidos que están los bordes de un objeto*

.. figure:: ../img/010020_012.jpg
   :alt: Imagen con un simbolo y diversos niveles de foco

   Las variaciones de Foco hacen una figura menos definida


Para algunos autores es perfectamente sustituible por variaciones de
saturación.

Resolución
""""""""""

Cantidad de información que compone un elemento.

.. figure:: ../img/010020_013.jpg
   :alt: Imágen de un mapa de Nueva Zelanda hecho en Lego

   La resolución a.k.a. el tamaño del pixel.

Conclusión
""""""""""

Todo buen cartógrafo debería tener una copia de este imagen siempre a mano:

.. figure:: ../img/010020_000.jpg
   :alt: Imagen resumen de las variables visuales y su uso

   Uso esperado de las variables visuales.


