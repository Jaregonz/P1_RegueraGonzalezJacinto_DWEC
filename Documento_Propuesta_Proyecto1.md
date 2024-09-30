# *Ez Learning*

!["Icono"](https://github.com/Jaregonz/P1_RegueraGonzalezJacinto_DWEC/blob/main/imagenes/Icono%20EzLearning.png)



### Idea de la aplicación

*Ez Learning* será una aplicación web cuya finalidad consistirá  en mejorar el nivel de inglés de los usuarios de forma fácil y entretenida.
Estará pensada para ayudar a los usuarios practicando mediante ejercicios y tests las tres _skills_ básicas del inglés (Grammar, Listening, Vocabulary).
Conforme se vayan superando los tests, el usuario podrá optar a tomar un examen el cual le permitirá subir el nivel de los tests de la aplicación. Estos niveles son los niveles de las titulaciones que ofrecen las universidades (*A2, B1 , B2, C1*). Habrá diferentes usuarios; unos serán los alumnos, que serán los que hagan los tests y los exámenes, y los profesores, que serán usuarios que podrán crear tests para que sean realizados por los alumnos.

### Audiencia Objetivo

La aplicación está destinada para cualquier persona que quiera mejorar su nivel de inglés, sin embargo, el sistema de niveles haría que fuera más indicada para aquellos usuarios que se hallen preparándose para los exámenes de certificados de inglés. Está pensada con los profesores de academias de certificación en mente, puesto que ellos son los que usarán esta web como herramienta para sus clases.

### Análisis de mercado

En el mercado existen una gran variedad de aplicaciones para aprender inglés, veáse por ejemplo la más famosa de ellas [_Duolingo_](https://es.duolingo.com/) cuya finalidad y funcionalidad es similar a la de *Ez Learning*, aun así no se podría considerar compentencia directa ya que *Ez Learning* estaría destinada a ser una aplicación web mientras que _Duolingo_ es una aplicación para dispositivos móviles, además _Duolingo_ está pensada para usarse en solitario mientras que _Ez Learning_ estaría destinada a usarse como herramienta en clase. Otras destacables pero menos parecidas son [_Preply_](https://preply.com/es/) y [_English Live_](https://englishlive.ef.com/es-es/) pero al ser aplicaciones cuya función es mejorar el inglés a través de tutores mediante clases en vivo no haría competencia directa con la aplicación.
Aunque es cierto que existen numerosas aplicaciones para aprender idiomas, es menor el número de aplicaciones que te permiten poder entrenar tus habilidades del idioma específicamente de cara a presentarte a exámenes de certificados de inglés, siendo este concretamente el principal objetivo de nuestro sistema.

### Funcionalidades clave

Las primeras funciones fundamentales que tendrá la aplicación son un sistema de registros mediante el cual los usuarios podrás registrarse para usar la aplicación y un sistema deauntentificación mediante el cuál los usuarios deberán logarse antes de entrar a la aplicación. A partir de aquí la aplicación se dividiría entre profesores y alumnos.

#### Funcionalidades del Alumno
Una vez dentro, al usuario se le mostrará una pantalla de inicio desde la que podrá acceder a los diferentes contenidos de la aplicación. Además, el usuario será capaz de observar su progreso actual y cuanto le queda para poder someterse al examen para optar a subir de nivel. 
En lo referente a las _skills_, el usuario podrá entrar a una pantalla en la cuál podrá acceder a los tests de cada tipo. Los tests serán diferentes dependiendo de cada _skill_, por ejemplo, en los tests de _Listening_ habrá un reproductor que permite la reproducción de un audio relacionado con el test a realizar. Cada una de las opciones tendrá varios tests cuya dificultad dependerán del nivel de inglés que posea el usuario. Los tests serán rellenados por el usuario y al final del cuestionario habrá un botón que le permitirá corregir y mostrar la puntuación obtenida para saber si ha aprobado el test(si ha acertado correctamente más de la mitad de las preguntas), pudiendo así elegir si 
quiere guardar su puntuación o si quiere volver a repetir el test. Si el usuario guarda una puntuación de un
test que ya ha sido realizado podrá sobreescribir la puntuación antigua.
Finalmente, una vez que el usuario haya aprobado todos los tests tendrá la opción de tomar un examen especial el cual le permitirá subir su nivel, pudiendo acceder a tests de mayor dificultad. 

#### Funcionalidades del Alumno
Cuando sea un usuario prefesor el que se ha logado, también podrá ver sus datos pero sus funcionalidades so un poco más básicas ya que su rol principalmente sería el de crear tests para los alumnos. No obstante, es el rol que más privilegios posee ya que puede acceder a los datos personales de los alumnos, pudiendo editar y/o inhabilitar usuarios alumnos.


A continuación, una lista de los requisitos funcionales de los que dispondrá la aplicación:

##### Requisito Funcional 1 - Registrar Usuario
Descripción
Antes de entrar a la aplicación y si no se posee un usuario, se deberá registrar para poder acceder a la aplicación.

##### Requisito Funcional 2 - Realizar Test
Descripción
Funcionalidad principal de la aplicación, se seleccionará el test y se podrá proceder a realizarlo.

##### Requisito Funcional 3 - Corregir Test
Descripción
Una vez finalizado el test, este se podrá corregir y se mostrará la cantidad de preguntas acertadas

##### Requisito Funcional 4 - Subir Test
Descripción
Se podrán subir test personalizado desde una de las aplicaciones.

##### Requisito Funcional 5 - Eliminar Test
Descripción
Desde la aplicación que es capaz de subir tests, también se podrá eliminar tests.

##### Requisito Funcional 6 - Modificar Test
Descripción
Se podrán eliminar y crear nuevas preguntas en tests ya existentes.

##### Requisito Funcional 7 - Inhabilitar Usuarios
Descripción
Los usuarios administradores tendrán la posibilidad de inhabilitar o habilitar usuarios no administradores.

##### Requisito Funcional 8 - Visualizar Datos Personales
Descripción
Dentro de nuestra aplicación, habrá un apartado que nos mostrará los datos del usuario que está logueado en el momento. 

##### Requisito Funcional 9 - Cambiar Datos Personales
Descripción
Se podrán cambiar los datos del usuario en la sección de Perfil. 

##### Requisito Funcional 10 - Realizar Examen
Descripción
Un test con características específicas (Con una puntuación concreta y formado por test aleatorios del nivel del usuario y de cada tipo de habilidad) que se deberá realizar para poder acceder a tests de mayor dificultad.

##### Requisito Funcional 11 - Desbloquear Nivel De Dificultad
Descripción
Una vez superado el examen, se habilitarán nuevos tests de mayor dificultad.

##### Requisito Funcional 12 - Reproducción de Audio
Descripción
En los test del tipo Listening, habrá un botón que reproducirá un audio relacionado con las preguntas del mismo.

##### Requisito Funcional 13 - Contraseña Olvidada
Descripción
Habrá una opción antes de entrar a la aplicación en la que el usuario podrá obtener una nueva contraseña, la cual será enviada por correo, si se le ha olvidado la anterior.

##### Requisito Funcional 14 - Subir Archivo de Audio
Descripción
Se podrán subir nuevos audios al crear tests desde la aplicación.




### Tecnologías seleccionadas para el desarrollo
*Ez Learning* usará diferentes tipos de tecnologías para sus diferentes partes. En backend, la aplicación será desarrollada en [_Springboot_](https://spring.io/projects/spring-boot) debido a sus múltiples ventajas. Se ha decidio usar _Springboot_ como técnología para el backend principalmente porque gracias a su integración nativa con APIs REST, será más fácil la interación con frontend. Además, gracias a Spring Security podremos crear una aplicación más segura de forma fácil.
En cuanto a la tecnología elegida para frontend, el lenguaje de programación que ha sido elegido es Javascript. Como se busca una página interactiva, Javascript viene como anillo al dedo para ello. Además, a parte de ser un lenguaje bastante bien optimizado, gracias a su amplia selección de herramientas y frameworks se podrán buscar más mejoras para la aplicación, lo que mejora su escalabilidad. Finalmente gracias a que Javascript facilita el consumo de APIs RESTful la facilitaremos la comunicación entre ambas partes del proyecto, al igual que con _Springboot_.
Estas dos técnologías son las bases de la aplicación, pero en el [Informe Técnico](https://github.com/Jaregonz/P1_RegueraGonzalezJacinto_DWEC/blob/main/Informe_Tecnico_Proyecto1.md) se hablará en más profundidad de otras tecnologías que serán utilizadas durante el desarrollo del proyecto.


