### Comentarios Generales

Belu, en primer lugar tengo que felicitarte por un un excelente trabajo. Me impresiona la cantidad de cosas que agregaste, los detalles que abundan a cada paso en tu TP. Los efectos en el hover, la originalidad del diseño, el hermoso efecto en tu presentacion, todo habla maravillas de tu capacidad de aprendizaje, tu curiosidad y tus ganas de aprender. Espero que te sientas muy orgullosa. 

Temo sin embargo que en algunas de las cosas que cambiaste también te escapaste de las consignas, y si bien lo resolviste bien a nivel visual y código, tengo que contemplar que no todo lo que pedimos está cumplido. No son requisitos porque sí: si bien es importante cumplir requerimientos a nivel laboral no dudo que vos vayas a hacerlo en ese ámbito, pero más bien le doy importancia porque hay algunas cosas que agregamos específicamente porque queríamos ver cómo las resolvían (por darte un ejemplo sencillo, no es casual que el botón "lo que hago" tenga el mismo estilo que el link de "contacto"). 

Entiendo que no llegaste tan bien con el tiempo, por lo que noto que algunas consignas no estan incumplidas. El responsive no funciona correctamente, en parte por algunos detalles en el CSS que te voy a comentar mas en detalle. 
- En todas las resoluciones tenes un scroll horizontal (lo vas a identificar como una barra blanca a la derecha) provocado port u barra de navegacion, en donde confluyen a la vez dos estilos: el general que le diste a todos los ul le agrega un margin-right de 150px, y el que le diste especificamente a .barra le da un width de 100%. Al juntarse estas dos ordenes, lo que le estas diciendo al elemento es: quiero que seas tan ancho como el body, pero que ademas tengas 150px de mas a tu derecha. Eso provoca el scroll. En general, no son necesarios los width de 100% salvo excepciones muy puntuales (imagenes) ya que los elementos naturalmente tienden a ocupar el 100% de su contenedor. 
- En resoluciones menores a 760px, tus tarjetas se ponen a la izquierda en lugar de posicionarse al centro. Les queda ademas muchisimo espacio libre a la derecha. 
- En resoluciones menores a 700px, la seccion "Mis conocmientos" tiene un margin-left de 700px que hace que aparezca una barra gris a la izquierda. Ocurre lo mismo con la cita. Si la intencion era darle espacio, un padding seria mejor, ya que conserva el color de fondo. Estos problemas de arrastran a las resoluciones de celular.
- Por el margin de la barra de navegacion, en celulares tu menu hamburguesa no queda a la derecha sino levemente al centro. 
- En celulares, el titulo "Mis conocimientos" tiene un tamaño de texto muy grande, por lo que rebalsa el body. Ocurre lo mismo con "Mis proyectos". "proyectos-botones" es muy ancho, rebalsa todas las medidas de celulares: deberia tener flex-wrap. Lo mismo con footer-links-redes. 
- Tus links internos a las secciones no estan hechos. Tampoco los links externos. 

Tu repositorio está ordenado, y cuenta con un buen README. Debo mencionar que hay relativamente pocos commits. Si bien entiendo que no es fácil subir un código cuando está recién empezado y lleno de problemas, es lo mejor, tanto para irse acostumbrando una a hacerlo, como para permitir que colegas (y profes!) puedan ver la evolución del código y encontrar rapidamente los commits en donde se hicieron determinados cambios. Cuando trabajamos en equipo es muy importante hacer commits breves, asi cualquier cambio puede identificarse facilmente. 

- Tus nombres de commits no son buenos, ya que la idea principal es que un colega o curioso pueda ver cómo fuiste haciendo tu proyecto y qué cambió de versión a versión. Lo ideal es que nunca se repitan y que describan bien que fue lo que hiciste en cada commit (no "cambios generales", sino "actualizo estilos en el header"). Hoy quizá no parezca importante, pero te aseguro que cuando trabajamos en equipo es muuuuy valioso saber qué hizo cada uno en el proyecto para encontrar los cambios que buscamos rápidamente. 

- Tengo que comentar y felicitarte por la prolijidad del código, tanto HTML como CSS. Tenes tendencia a dejar saltos de linea innecesarios, que dificultan la lectura del codigo. Tambien tenes algunas etiquetas de cierre que no hacen nada. Mas alla de eso, todo está muy prolijo y muy bien indentado, dos cosas que no son habituales cuando recién empezamos. Los nombres de clases son por lo general muy buenos, claros y descriptivos. Tu CSS también está muy bien, aunque agregas algunos estilos innecesarios - te lo dejo comentado alli.  

Dejo algunos comentarios específicos a lo largo de tu código. 

Notarás, viendo esos comentarios, que comento muchisimas cosas y soy bastante quisquillosa con las correcciones. La idea es comentarte todo lo que vea para que puedas mejorar tu código y que tu portfolio quede lo mejor posible. Ojala te sirva :)  


### Nota final: 7

Nota desagregada: 
✅ Estructura correcta de documento HTML 
✔️  Respeta la consigna --> con observaciones. 
✔️ Respeta el diseño dado --> con observaciones
❌  Responsive funciona correctamente
✅ Código bien indentado. 
✅ Comentarios que permiten mejorar la legibilidad del código.
✅ Uso correcto de etiquetas semánticas.
✅ Buenos nombres de clases 
✅ Reutilización de estilos.
✅ Código CSS ordenado 
❌ Commits con mensajes adecuados.
