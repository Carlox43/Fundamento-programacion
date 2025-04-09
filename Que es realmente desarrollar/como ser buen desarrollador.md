# ¿Como ser buen desarrollador?

En el ámbito del desarrollo es común centrarse exclusivamente en los resultados _a corto plazo_ de la programación, debido muchas veces por desconocimiento o por la presión de cumplir tareas. Las metas que normalmente nos planteamos son las siguientes:

· ✅Nuestro código _debe funcionar_ y cumplir propósito sin errores.

· ✅ Nuestro código _deber ser eficiente_ y hacerlo de forma rápida y óptima.

Estas expectativas son indiscutibles. Generalmente, todos sabemos que el código debe cumplir con lo que se espera de él, y cuanto más eficiente sea, mejor.

Hay que entender que, cuando desarrollamos, lo importante es alcanzar el _Objetivo final_. El tiempo es dinero y cuanto más tiempo tardemos en lograr nuestro objetivo, menos rentable será. Por eso, debemos cuidar e intentar reducir el tiempo que nos lleva desarrollar algo.

Punto clave en el desarrollo

Aunque estos dos primeros puntos que hemos mencionado son muy importantes, en muchas ocasiones olvidan otros puntos igual de importantes y factores clave, en las etapas futuras del desarrollo:

·✅ Funcionalidad -> Debe cumplir el objetivo clave.

·✅ Eficiencia -> Debe hacerlo lo más rápido y eficiente posible.

·🙈 Mantenibilidad -> Debe ser facil de modificar y ampliar si se necesita.

·🙈 Legibilidad -> Debe ser código fácil de leer y entender.

·🙈 Modularización -> Debe estar separado y no depender de otras cosas

·🙈 Testabilidad -> Debe ser fácil de comprobar si funciona correctamente.

·🙈 Usabilidad -> Debe ser fácil de utilizar por el usuario final.

·🙈 Tiempo de desarrollo -> Debe crearse lo más rapido posible.

Vamos a explicar cada uno de ellos y porque tienen un papel importante en el mundo del desarrollo y la programación.

Código legacy

Antes de comenzar a analizar estos puntos, veamos primero un concepto fundamental que hay que conocer: el código <<Legacy>>(_código heredado_). Se conoce como _código legacy_ al código que se ha desarrollado en un proyecto o empresa y que, aunque aún se utiliza y funciona correctamente, ha quedado obsoleto o anticuado en la comparación con las tecnologías y prácticas actuales, perjudicando de forma directa o indirecta al proceso de desarrollo.

Hay que tener en cuenta en la mayoría de la empresas, los desarrolladores no realizan desarrollos desde cero, sino que se enfrentan a _código legacy_ desarrollado desde hace hace algún tiempo, el cuál debe mantenerse, modificarse, mejorarse y apliarse sin introducir nuevos errores, sin perder funcionalidades e intentando conseguir mejores resultados.

Generealmente, el _código legacy_ no usa tecnologías de ultima generación, ni sigue las mejores prácticas, lo que puede dificultar mucho trabajar con él. Sin embargo, tampoco se suele poder invertir tiempo en migrar a otra tecnología o prácticas, porque requeriría invertir mucho tiempo de desarrollo.

Mantenibilidad y escalabilidad

La _mantenibilidad_ y la _escalabilidad_ son algunos de los criterios más importantes a la hora de crear código, ya que cuando desarrollamos y escribimos código, normalmente lo hacemos con planes de que el código de ese proyecto siga funcionando a largo plazo.

· Mantenibilidad: Por un lado, se busca crear código _mantenible_, es decir, seguir unos ciertos criterios para que el código sea fácil de _modificar_ y pueda adaptarse a nuevas nescesidades sin perder la funcionalidad actual.

· Escalabilidad: Por otro lado, un código _escalable_ es un código que es fácil de ampliar y extender, sin que se rompa el funcionamiento actual.

Al código difícil de mantener, mezclado y desordenado se le suele llamar _codigo spaghetti_, debido a la similtud de apariencia caotica con un plato de spaghettis.

Legibilidad y simplicidad.

La _legibilidad_ y _simplicidad_ son criterios muy deseables en nuestros código, y en general en nuestros desarrollos. Cuando creamos código,lo primero que se busca es que funcione. Sin embargo, para conseguir una buena mantenibilidad y escalabilidad, suele ser nescesario que el código sea _fácil de leer_ para que lo programadores no tarden tiempo en entenderlo o modificarlo.

En muchas ocasiones ocurre, que tras algunos días sin programar, si volvemos a examinar nuestro código, nos puede llevar tiempo entenderlo (aunque lo hayamos hecho nosotros mismos). Esto es normal, y generalmente se basa en que no tenemos mucha experiencia en el desarrollo y/o que el código hace muy complejas que se podrían simplificar.

Si el código es _simple_, mucho mejor. Nuestro código puede funcionar correctamente, sin embargo, existen múltiples formas de hacer tareas, por lo que siempre será preferible que sea más _sencillo y claro_, a que sea complejo y largo.

En general, intentaremos que nuestro código funcione primero, pero una vez se cumpla esta caracteristicas hay que intentar simplificarlo y hacerlo más sencillo de entender para los demás.

Modularizar y refactorizar

Cuando desarrollamos, muchas veces tendemos a mezclar el código de ciertas funcionalidades con el de otras. lo ideal sería _modularizar_ el código de forma que sea independiente. Piensa que al tener funcionalidades mezcladas con otras, va a ser más difícil modificarlas, reutilizarlas, o si tenemos que eliminar una de ellas, podamos hacerlo porque no depende de otra.

existe un concepto denominado _refactorizar_ que es el proceso de _modificar el codigo para mejorar_ su estructura, legibilidad, eficiencia o mantenibilidad _sin alterar ni romper su funcionalidad_.

Otro concepto importante es el de las _dependencias_. Se le llama dependencia a librerías externas que nos ayudan a realizar tareas secundarias. En un mundo ideal nuestro desarrollo no tendríra dependencias, sin embargo, las dependencias nos ayudan a terminar antes nuestro desarrollo. Hay que intentar mantener un equilibrio entre no usar demasiadas dependencias y no tener que implementar funcionalidades donde no podemos aportar demasiado o vamos a tardar mucho.

Aunque usar dependencias nos facilita mucho el trabajo, por cada dependencia que utilicemos (como su propio nombre indica) no acoplamos a esa librería: los cambios que hagan, problemas de seguridad que tengan o si la abandinan, nos afectará a nuestro desarrollo.

Testabilidad

Una característica interesante en nuestro desarrollos es que incorporen _pruebas_ o _test_. Estos test son fragmento de código que se ejecutan para comprobar si ciertas partes de nuestro desarrollo funcionan correctamente.

De esta forma si realizamos cambios en nuestro desarrollo, podemos activar las pruebas para comprobar si tras los cambios sigue funcionando o han dejado de funcionar, con lo que sabríamos rápidamente si nos hemos equivocado al modificar el código.

Usabilidad

Al desarrollo nuestro código, no sólo debemos cuidad los aspectos técnicos del mismo. Por ejemplo, si estamos desarrollando una pagina web, esta página debe ser fácil de utilizar, intuitiva y satisfactoria de cara al usuario final.

Algunos ejemplos de _mala usabilidad_ podrían ser:

·🔴 Un botón aceptar en rojo y cancelar en verde.

·🔎 Una caja de búsqueda en la parte inferior de la pagina.

·🔑 Un formulario que reinicia todos los campos si hay un error en uno solo.

·🎭 campos de contraseña que no ocultan y dejan ver lo que escribes.

·🐌 Páginas que tardan en cargar sin medidor de progreso.

·🚪 Un enlace o botón de 'Descartar cambios' muy cerda de 'Guardar cambios'.

·🔊 Un sitio web que reproduce música automaticamente y sin botón de pausar.

Tiempo de desarrollo

Anteriormente comentamos que el tiempo que tardamos en desarrollar es un fartor _Clave_. Todos los puntos anteriores son importante en el ámbito del desarrollo, pero un aspecto _Crítico_ es _Reducir lo máximo posible el tiempo de desarrollo_. Sin embargo, no podemos reducir el tiempo sin sacrificar ciertas características, y _justo ahi está la clave_.

Un buen desarrollador con experiencia sabe (o intuye) que criterios puede sacrificar para reducir el tiempo de desarrollo, sin perjudicar la calidad final del. Por ejemplo, en ciertas situaciones, quizás no es tan prioritario que el código sea muy eficiente y este optimizado, y es prioritario que se termine cuanto antes.

Tener esa habilidad para equilibrar características lo da la experiencia, pero para poder tenerla es necesario estar concienciado y saber porque es importante.
