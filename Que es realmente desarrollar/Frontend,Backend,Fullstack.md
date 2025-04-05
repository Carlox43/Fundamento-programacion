# ¿Frontend, Backend, Fullstack?

Al comenzar en el Desarro web (_O incluso más adelante_), mucha gente tiene dudas y no entiende exactamente que diferencias hay entre los términos _front-end y backend_. Para simplificar, muchas veces se suele decir que la parte _visual_ se realiza en el fronted, y la parte de funcionjalidad en el _backend_. Sin embargo, aunque puede ser una buena primera aproximación, no es técnicamente correcto.

¿Qué es front-end y back-end?.

la palabra _front-end_ hace referencia a la parte frontal, mientras que la palabra _Back-end_ hace referencia a la parte de atrás. En ambos casos, esto se refiere a como se ve una página web desde el punto de vista del visitante de la misma. la parte frontal es la parte visible, con la que interactúa el usuario, y la parte trasera es la que no se ve, donde el sistema realiza las tareas que no son visibles al usuario, como gestiones con la base de datos, cacheo de información, etc.

Lo habitual suele ser optar por asociar tecnologías a cada una de estas especialidades:

En el _front-end_ se utilizan tecnologías como:

·🌐 HTML: la estructura y contenido de la página.

· 🎨 CSS: el diseño y aspecto visual de la página.

· ⚡ javascript: la interactividad y control de la página.

en el _back-end_ lo habitual es que se elija una sola tecnología como algunas de las siguientes:

· ☕ Java: Lenguaje tradicional para backend.

·📗 Nodejs: Lenguaje Javascript para backend.

·⚙️ Rust: Lenguaje enfocado en alta eficiencia.

·🐘 PHP: lenguaje enfocado en facilidad y flexibilidad.

·🚀 Go: lenguaje enfocado en alta concurrencia.

·🐍 Python: Lenguaje enfocado en ciencia de datos.

Sin embargo, lo más _Importante_ aquí, es entender que las tecnologías de front-end funcionan en el navegador del usuario (_despues de enviarlas por Internet_), mientras que las tecnologías de back-end funcionan en la máquina o servidor donde esta alojada la web (_antes de enviarlas por Internet_).

¿Qué son los frameworks?

como trabajar con estos lenguajes directamente puede resultar complejo, sobre todo para usuarios n'oveles, lo habitual es utilizar _frameworks_ que son más fáciles de aprender. Un _framework_ es una capa de un cierto lenguaje que nos hace escribir menos código para hacer tareas comunes y habituales. Además, suelen venir junto a consejos y recomendaciones a la hora de trabajar, de modo que sea más intuitivo escribir código.

Existen _frameworks_ tanto para la parte de _front-end_ como para la parte de _back-end_:

·🎨 CSS: TailwindCSS, Bootstrap...

·⚡ Javascript: React, Vue, Angular...

·☕ Java: springboot, Micronaut...

·📗 NodeJs: Expressjs, Nestjs...

·🐍 Python: Django, Flask...

·⚙️ Rust: Rocket, Actix...

·🐘 PHP: lavarel, Symfony...

·🚀 Go: Gin, Echo...

Sólo he colocado dos o tres de lo más populares de cada lenguaje, pero existen muchísimos más, Ten en cuenta que cada uno de estos frameworks tienen su forma de escribit código, su forma diferente de trabajar, etc. Por lo que es imposible conocerlo todos.

Lo habitual suele ser buscar el que más se adapta a tu proyecto, o el que más encaja con la empresa en la que estás trabajando, o el que más se demanda en empresas para tener más oportunidad de contratación.

muchas veces suele llamas _stack_ a la lista de tecnologías con la que trabajas, y se suelen utilizar las iniciales para identificarlas. Por ejemplo, Mern (_MongoDB + Express + React + Node_), Tall (_Tailwind + AlpineJS + Lavarel + linewire_), LAMP (_Limnux + Apche + MariaDB + PHP_), etc.

Modalidades

Otro detalle que merece la pena mencionar es que un sitio web no se construye siempre de la misma forma. Dependiendo de las nescesidades del sitio web, puede carecer de ciertas partes o utilizar un esquema completo con todas las partes. Observa el siguiente esquema general:

· Front-end + back-end: Esta modalidad es la que se ve en el gráfico anterior y es una unión de las dos siguientes. En estos esquemas, normalmente se utiliza un framework de frontend para gestionar la parte e interacccion con el usuario, y un framework en el back-end para realizar ciertas tareas y enviar/ recibir datos al frontend a traves de una API.

· Front-end: las tecnologías de frontend se ejecuta en el navegador, después de haber sido descargadas, por esa razón, las tecnologias de font-end tienen como ventaja ser más rápida y no tener mucha latencia. Si tenemos frameworks de Javascript (React, Vue, Angular...), éstos trabajan en este extremo. A través de Javascript, se puede recibir/ enviar informacion al back-end a través de una API. Si tenemos esquema de sólo frontend, se suele prescindi del backend/ base de datos y se utilizan servicion de terceros en su lugar.
