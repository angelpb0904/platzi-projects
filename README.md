# CURSO DE PLATZI

## Recap Programación básica. 

### La creacion de aplicaciones web se basan en 3 pilares: que son HTML, CCS, JavaScrip.

- HTML (.html) es todo el contenido de l página web, aqui es donde se desarrollará la información.
- CCS (.css) es donde se define el diseno y todo lo que tiene que ver con los visual en la página web.
- JavaScript (.js) es el lenuaje de programacion que se utliza para el desarrollo de la dinámica de la página web.

**Todos los lenguajes de programación trabajan con varios elementos como: arreglos, variables, condicionales, funciones y clases. Cada una de ellas tiene propositos importantes en el lenguaje de programación.**


## Mi Primera linea de código.

### alert("Mi nombre es Ángel");

**Para empezar a aprender JS solo tenemos que aprende lo básico, que unas de ella son las variables, es un espacio que se crea para guardar una información.** 


## ¿Qué es HTML/CSS/JS?

**HTML, CSS y JavaScript son los tres lenguajes que están en el centro de crear aplicaciones web por tal razón, habalaremos de ellos:**

- HTML no es un lenguaje de promagramción, en HTML es donde vamos a encontrar toda la información de nuestra página web.
- CCS tampoco es un lenguaje de programación, en este es donde vemos el diseño de nuestra página, todo lo relativo con los visual esta relacionado con CSS, ni en JS ni en HTML tienen que ver con eso.
- JavaScrip es un lenguaje de programación que tiene interactividad, es cuando desarrollamos código para que nuestros dispositivos hagan algo. 

**El Browser (Navegador) es el que toma todo los códigos y etiquetas y los interpreta y organiza y podemos ver todo lo que hemos creado.**


## JavaScript no es Java.

**JS y Java no es lo mismo, son dos cosas muy diferentes, entre ellas están:**

**Java**
  - Es de Oracle.
  - Es creado para servidores.
  - Lenguaje pensado para crear aplicaciones de escritorio.
  - Es muy popular en bancos.
  - Es donde se crea aplicacones para android.

**JavaScript**
  - JavaScript es el lenguaje de la web, servidores, robots, etc.


## Primeros pasos en el navegador con alert.

- Alert es la forma que mandamos un mensaje, muestra información o resultados en la pantalla. También muestra advertencias.
- Para poner una alerta se pone la palabra especifica "Alert", seguida de dos commilas y dentro de ellas el texto ue queremos que aparezca. Cerramos con punto y coma.
- Para declarar una variable, solo tenemos que poner la palabra "var", luego pones el nombre de esa variable, el operador de asignación y luego su valor. Cerramos con punto y coma.
- Las comillas se utilizan para limitar textos, porque son datos tipo string.

## HTML, CSS, JavaScript de verdad.

- Muy importantes las reglas para nombrar variables en JavaScript:

- No pueden empezar con números, sólo con letras.
- Se diferencian mayúsculas y minúsculas.
- No se pueden utilizar caracteres "raros" como ñ o tildes.
- Para poner nombres largos se utlizanan la rayita baja.

**Con este ejemplo se pudo experimentar con HTML, CSS y JS, asi como:**

- Nuevas etiquetas de HTML.
- Nuevas etiquetas CCS.
- Codigos jS.
- Se abre una etiqueta co un nombre, y se cierra con el mismo nombre pero con el slash al final, admas se le agrega los simblos de mayor y menor en sus extremos.
- El JavaScritp se pone el el body, y se abre una etiqueta llamada script.
- El CCS se pone en el Head, con la etiqueta style.
- Se utiliza "document.write" para escribir o emprimir texto en el navegador.


## Peso en otro planeta.

**En este video Freddy nos enseña a como calcular el peso en otro planeta, y el nos decia que eso va depender de la fuerza de la gravedad y de nuestro peso, ya que estas son las dos variables principales para saber o cacular nuestr peso en cualquier planeta. Cabe recalcar que no todas las gravedades son las mismas en los planetas. Es decir, en MARTE voy a ser mas liviano que en la TIERRA, porque la gravedad en MARTE es 3,7 metros por segundo y en la tierra es 9,8 metros por segundo.**

**Entonces, podemos calcular esto atraves de un algoritmo. Lo primero es hacer la estructura de la página, luego declaramos las variables dentro de una etiqueta script. Después declaramos la funcion que calculara nuestro peso. Y para saber si esto funciona, solo tenemos que hacer una alerta y declarar la variable peso, para que nos la diga, o simplemente imprimimos el resultado con document.write para que se vea un poo mejor. Para que el calculo no nos dé con tanto decimal es poner la funcion parseInt, es decir, nos va a redondear la ecuación.**

## Obteniendo datos del usuario.

**Para obtener los datos de los usuario utlizamos la funcion prompt, esto hace casi lo mimsmo que la funcion alert, en ves de eso los usuarios ingresan un valor.**

- La consola del navegador, nos puede servir para verificar las variables.
- Cuando un valor tiene comillas en el extremo es tipo texto.
- Concatenar es pegar cadenas de textos cn variables.
- parseInt es para traer numeros enteros.
- parseFloat es para traer numeros flotantes, es decir decimales.
- Si en nuestra consola aparecen errores, quiere decir que tenemos problemas en nuestro codigo.
- Los espacios tambien debn de ir dentro de las comillas.
- Las etiquetas son caracteres tipo texto, por eso deben ir dentro de las comillas.


## Flujo y condicionales.

**Las condiciones son las que controlan las condiciones para poder pensar, elegir entre una y otra.**

- Tenemos que hacer elegir al usuario entre las opciones que le ofrecemos atravez de las condiciones.
- Usar un signo de igual (=) es para asignar un valor.
- Usar dos signos de igual (==) es para comparar.
- En los diagramas de flujo, decidimos irnos por el camino que decidamos.
- Cuando elejimos un camino en el diagrama del flujo el otro camino nunca pasa.
- Podemos hacer un saldo de linea de el lenguaje de JS colocando "\n".
- Se puede poner la funcion paseInt en la misma linea que la funcion prompt, solo tener en cuenta los parentesis.
- Cuando el if es verdad ocurre lo del bloque, cuando no es verdad no ocurre lo del bloque.
- El if tiene una comparacion dentro de si misma.
- if() significa: que si.
- else significa: Sí no.
- else if() significa: Sí no, sí.
- Los bloques de codigos de no tieen punto y coma.
- En una condicion se puenden poner mas de dos lineas de codigo.
- Se debe tener pendiente los espaciones y variables cuando se concatena.

## El DOM: nuestro lugar de trabajo en la web.

- Los objetos son aquellos que contienen funciones, atributos, variables, etc.
- El navegador tiene su propios objetos los cuales son manipulables a traves de JS.
- Document es  todo el contenido creado por el programador.
- Window es el objeto que compone cada pestaña abierta dentro del navegador, se puede acceder a ella con window.
- Navigator lo compone el navegador en si, posee varias funciones interesantes como el poder acceder a los discos duros del usuario, utiliza la función GPS presente en los smartphones, tablets, laptops(a través del wifi) y otros.
- DOM es la manera en que el navegador organiza internamente el archivo HTML solicitado, dentro de un estructura que nos permite manejarlo desde JS, y crea una estructura tipo arbol.

## Cómo funcionan Window y Document

**Los objetos contienen lo sieguiente**

- Métodos: funciones dentro de un objeto.
- Atributo o propiedad: variables internas que almacenan valores.

- HTML solo puede contener dos etiquetas en el mismo nivel : <Head> y <Body>.
- La etiqueta <Script> va justo antes de cerrar el body.
- HTML que permite al navegador interpretar los caracteres especiales como tildes, acentos, la letra ñ.
- Console.log permite emitir mensajes que no vea el usuario.
- Charset significa colección de letras.

