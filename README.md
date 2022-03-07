# LaunchX- Ejercicios Semana 1

Estos son los entregables de la primer semana de la Misión Frontend del Curso de Innovacción Digital

## Índice
1. [Introducción](##introducción)
2. [Descripción y requerimientos de caso "Abogabot"](##descripción-y-requerimientos-de-caso-"abogabot")
3. [Buyer persona](##descripción-del-buyer-persona)
4. [Público Objetivo](##público-objetivo)
5. [Wireframing de la aplicación](##wireframing-de-la-aplicación)
	- [ Wireframing - Usuario Común](###wireframing---usuario-común)
	- [ Wireframing - Usuario de tipo Administrador](###wireframing---usuario-de-tipo-administrador)
6. [User Interface App](##user-interface-app)


## Introducción
En el presente ejercicio se asignó el caso de Abogabot, un asistente jurídico virtual el cual tiene como funcionalidad automatizar el proceso de los clientes de __M&V S.A de C.V__, la cual es un buffet de abogados, para ello se requiere llevar a cabo un proceso de desarrollo de software en su fase de __Especificación de Requerimientos de Software__ y __Análisis de estudio de caso__ previo a la programación e implementación del software ya mencionado.

En la siguiente documentación, se podrá apreciar el proceso de análisis de requerimientos realizado con la finalidad de presentar una propuesta de diseño de interfaz y de experiencia de usuario, basada en los requerimientos descritos a continuación.

## Descripción y requerimientos de caso *"Abogabot"*

* Es un despacho de abogados que quiere automatizar las demandas de sus clientes, esto lo harán a traves de una página web llenando un formulario.

* Al momento de llenar el formulario se manda al proceso de pago para finalizar la transacción.

* Para dar seguimiento a su demanda, el cliente crea una cuenta en la plataforma y verá el seguimiento de cada una de las actualizaciones del proceso legal.

* El administrador del sitio recbe la notificación de una nueva demanda y con los datos llenados del formulario se crea automaticamente el documento legal en formato word para empezar el proceso.

* El administrador recibe el pago y debe de ser capaz de verlo en un dashboard para ver la cantidad de ingresos recibidos.

* El administrador actualiza el proceso de la demanda y agrega comentarios en cada paso del proceso.

* Al usuario le llegan correos de notificación para saber el avance de su proceso.

* La página debe de ser responsive para poderla ver desde el celular.

* La preferencia de colores del cliente es azul marino y blanco, pero acepta propuestas.

## Descripción del Buyer Persona

![Buyer Persona](https://github.com/MikoVelascoRamirez/IntroProgramaci-nFrontend/blob/master/BuyerPersona/Mario%20Figueroa.pdf)

Para este caso, se creó un prototipo de nombre Mario Figueroa, de origen mexicano, actualmente tiene 35 años y es CEO Manager de *FinGaining*, una empresa asesora en inversión en activos digitales, esposo y padre de dos hijos.

Egresado de la Licenciatura de Finanzas de la Universidad Autónoma de México, siempre ha demostrado una personalidad caritativa y filántropa a ayudar a todo aquello existente, en especial a las personas de bajos recursos y con problemas para generar riqueza que le permitan cumplir sus objetivos y lograr la libertad financiera.
Desde pequeño, sufrió varias carencias económicas que no le permitieron desarrollar su crecimiento en las mejores condiciones posibles debido a la situación nacional de aquel entonces la cual era complicada. Dicho esto último, Mario se prometió a si mismo que nadie debería padecer si de dinero se trataba.

### Datos demográficos
* Reside en la Ciudad de México
* 35 años
* Sus ingresos mensuales son superiores a $15,000 pesos

### Retos
* Posicionar a su empresa, "FinGaining" como la principal opción de asesoría financiera nacional en México.
* Crear un ambiente propicio y sano para sus trabajadores a través de mejores prestaciones laborales.
* Posicionar a su empresa dentro del negocio de las criptomonedas.
* Comenzar a cotizar dentro de la bolsa de valores.

### Objetivos
* Brindar a su familia una mejor calidad de vida en otro país.
* Pasar mas tiempo con su familia.
* Contratar mas personal que le permitan cumplir con el objetivo anterior, a modo de pasar menos tiempo en la empresa.
* Lograr la independencia financiera a través de la implementación de sus métodos financieros

### Hábitos
* Inicia sus actividades a las 5 de la mañana.
* Realiza ejercicio 3 veces a la semana
* Suele interactuar mucho con las personas. Sociable.
* Le gusta ayudar a las personas con sus problemas e inquietudes.

### Frustraciones
* Tener que lidiar personalmente con la jurisprudencia local de la Ciudad de México en materia jurídica y legislativa.
* No tener un equipo calificado de abogados que lleven y gestionen los procesos de la empresa.
* Que su empresa no cuente con el blindaje suficiente que le aporte estabilidad a sus empleados ante la ley.
* No contar con tiempo suficiente para su esposa e hijos.

## Público Objetivo
![Público Objetivo](https://github.com/MikoVelascoRamirez/IntroProgramaci-nFrontend/blob/master/P%C3%BAblico%20Objetivo/P%C3%BAblico%20objetivo%20Abogabot.jpg)

### Marco 
Se entiende como marco como las características generales que ayudarán a segmentar al público, debe contemplar la descripción del producto.

* Mexicano
* Licenciatura concluída
* Ingresos superiores a $10,000
* Sexo indistinto
* Trabajadores o pertenecientes al entorno empresarial

### Intereses
Cosas o lugares que el público consume.

* Política
* Noticias
* Eventos sociales
* Economía y finanzas

### Preocupaciones
¿Cuáles miedos se disipan con el producto en turno?

* No recibir asesoría legal adecuada
* Prevenir consecuencias negativas o no deseadas ante un conflicto
* Poner en riesgo integridad propia o de familiares y conocidos
* No tener noción o conocimiento de como resolver algún conflicto
* Desconocimiento de derechos y obligaciones jurídicas
* Evitar problemas laborales con empleados

### Capacidades
Son las características que debe un cliente tener obligatoriamente para calificar como uno.

* Tener una necesidad o proceso jurídico en turno
* Ser mayor de edad
* Ser reconocido jurídicamente ante la ley

## Wireframing de la aplicación
Para el maquetado de la aplicación se realizaron dos prototipos de aplicación, uno para el __usuario de tipo común__ y otro para el __administrador__,
segmentando por secciones y funcionalidades las interfaces de aplicación, con el fin de darle mayor claridad y legibilidad al usuario que esté leyendo la presente documentación.

### Wireframing - Usuario Común

![Wireframing Abogabot](https://github.com/MikoVelascoRamirez/IntroProgramaci-nFrontend/blob/master/Wireframing/Abogabot%20-%20User%20Wireframe.png)

1. __Vista General__: en esta sección, podremos observar las ventanas principales del sitio web de __M&V S.A de C.V.__, disponibles al momento de su visita por primera vez, indicando el inicio de dicha experiencia para este tipo de usuario.
2. __Solicitud de demanda (inicio)__: el usuario deberá dar click en el menú del encabezado donde se encuentra la opción de *Abogabot*, la cual lo redirigirá a la sección informativa del producto donde encontrará un banner principal con otro botón, que será el inicio del __proceso de solicitud de demanda__.
3. __Solicitud de demanda (proceso)__: En dicha ventana, el usuario común encontrará formularios múltiples con información necesaria y obligatoria para comenzar un proceso jurídico de demanda, si la digitación de los campos son correctos, se procederá a realizar un pago a través de un formulario, (acepta pagos con tarjeta o cartera digital), se deberá aceptar los términos y condiciones para poder realizar el pago, si hay algún error, se indicará con una leyenda sobre la misma, de lo contrario se le notificará mediante un mensaje de *Pago aceptado*, con la posibilidad de descargar un documento de puntos petitorios, el cual es necesario para dar inicio a una nueva demanda.
4. Para poder visualizar y dar seguimiento a su demanda, el usuario deberá proceder a registrarse mediante un enlace disponible en la ventana de confirmación de pago, introduciendo un nombre de usuario y una contraseña (en dos ocasiones, con fines de autenticidad), da paso a registrarse. En caso de algún error, este se registrará en pantalla.
5. __Inicio de sesión__: el usuario introucirá su nombre de usuario y contraseña, si hay algún error, se notifica mediante pantalla con una leyend, de lo contrario podrá acceder a su perfil de usuario.
6. __Gestión y seguimiento__: En esta sección podrá consultar y realizar lo siguiente:
* Consultar demandas: El usuario dará click en el menú del encabezado, específicamente en la sección de *"Mis demandas"*, donde consultará todos los detalles de sus procesos jurídicos en turno, datos como los detalles, el estado legal de la misma, etc.
* Detalle de la demanda: el usuario dará click en el botón *Ver detalle* del proceso a seleccionar en el registro de demandas, verá datos como foto de perfil del demandante, su edad, domicilio y estado civil. En dicha sección podrá observar el documento cargado en turno.
* Enviar mensajes: el usuario tendrá una sección de mensajería vía correo, misma que se puede acceder desde la opción del menú "Mensajes" del encabezado, en ella podrá ver la bandeja de entrada con los mensajes/notificaciones del abogado que lleva el caso, tendrá la opción de responder a la notificación en otra pantalla.
6. __Panel de notificaciones__: el usuario tendrá el ícono de una campana en el menú del encabezado donde podrá consultar todas las novedades o actualizaciones a su proceso de demanda a través de un panel.
7. __Finalización del proceso - finiquito de pago__: En dicha sección, el usuario podrá nuevamente realizar el pago total de los honorarios del abogado por prestar sus servicios en el mismo formulario donde realizó su pago inicial, si la transacción es correcta, el proceso habrá terminado, de lo contario, se indicará mediante pantalla.

*Hecho lo último, el usuario podrá cerrar sesión*

### Wireframing - Usuario de tipo Administrador

![Wireframing Abogabot](https://github.com/MikoVelascoRamirez/IntroProgramaci-nFrontend/blob/master/Wireframing/Abogabot%20-%20Administrator%20Wireframe.png)

1. __Vista General__: en esta sección, podremos observar las ventanas principales del sitio web de __M&V S.A de C.V.__, disponibles al momento de su visita por primera vez, indicando el inicio de dicha experiencia para este tipo de usuario.
2. __Inicio de sesión__: el usuario introucirá su nombre de usuario y contraseña, si hay algún error, se notifica mediante pantalla con una leyend, de lo contrario podrá acceder a su perfil de usuario.
3. __Demandas en curso__: el administrador podrá consultar todas las demandas en curso que el despacho tiene a su cargo, para ello, deberá dar click en el menú del encabezado donde se encuentra la opción de *Demandas*, la cual lo redirigirá a un registro de todos los procesos en turno, podrá ver información importante como el id de la demanda, el estado de la misma, sus detalles, nombre del demandante, etc. En cada registro tiene la posibilidad de terminar un proceso de demanda. 
4. __Solicitudes entrantes__: En dicha ventana, el usuario común encontrará todos las peticiones de usuarios múltiples con información adjunta necesaria para revisión, el administrador notificará a través de un pequeño grupo de controles si la petición es óptima para *Admisión*, *Prevención* o *Desecho*, es decir, si esta "pasa", "se manda a corrección" o "se rechaza" por falta de información.
5. __Visualizar documento con puntos petitorios__: El administrador podrá observar a detalle el documento que incluyen los puntos petitorios de la persona, que le ayudarán a tomar una decisión dentro del proceso de demanda.
6. __Visualizar demanda__: El administrador podrá consultar los detalles de una demanda ya admitida, dando click en el botón *Ver detalle* ubicada por registro en el registro de demandas, visualizará datos como foto de perfil del demandante, su edad, domicilio y estado civil. En dicha sección podrá observar el documento cargado en turno.
7. __Panel de notificaciones__: el usuario tendrá el ícono de una campana en el menú del encabezado donde podrá consultar todas las novedades o actualizaciones a su proceso de demanda a través de un panel.
8. __Fin del proceso__: En dicha sección, el usuario podrá enviar al usuario una factura con el total de los honorarios a cobrar por parte del abogado por prestar sus servicios a través de un pequeño formulario donde deberá introducir el remitente, el destinatario, su asunto y algún mensaje, si no hay inconvenientes con el envío, se le redirigrá al registro de demandas, de lo contario, se indicará mediante pantalla.	

*Hecho lo último, el usuario recibirá una notificación para realizar el finiquito de los honorarios, hecho esto, el adminisitrador podrá dirigirse a la ventana del final del proceso, donde puede omitir este último paso indicando que el proceso ha finalizado*.

## User Interface App

Para visualizar el diseño de interfaz de usuario, puede hacerlo dando clic ![aquí](https://github.com/MikoVelascoRamirez/IntroProgramaci-nFrontend/tree/master/User%20Interface).

