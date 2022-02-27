# LaunchX-PrimeraSemana

Entregables de la primera semana de la Misión Frontend del programa LaunchX de InnovaccionVirtual

## Caso: Abogabot 


Descripción: Es un despacho de abogados que quiere automatizar las demandas de sus clientes, esto lo harán a través de una página web llenando un formulario. Al momento de llenar el formulario se manda al proceso de pago para finalizar la transacción. Para dar seguimiento a su demanda, el cliente crea una cuenta en la plataforma y verá el seguimiento de cada una de las actualizaciones del proceso legal. El administrador del sitio recibe la notificación de una nueva demanda y con los datos llenados del formulario se crea automáticamente el documento legal en formato word para empezar el proceso. El administrador recibe el pago y debe de ser capaz de verlo en un dashboard para ver la cantidad de ingresos recibidos. El administrador actualiza el proceso de la demanda y agrega comentarios en cada paso del proceso. Al usuario le llegan correos de notificación para saber el avance de su proceso. La página debe de ser responsive para poderla ver desde el celular. La preferencia de colores del cliente es azul marino y blanco, pero acepta propuestas.

## Bosquejo de la app:

### Usuario
El usuario debe loguearse para llegar al home, en caso de no tener cuenta debe crear una.
En el Home tendrán dos opciones. Crear una solicitud nueva o ver el estado de su solicitud.
Crear una nueva solicitud de demanda: debe llenar un formulario con los datos pertinentes a la demanda, luego un formulario de pago por el recibimiento de la demanda.
Ver demandas: el usuario podrá ver el estado de su demanda de acuerdo a las actualizaciones del proceso y los comentarios que el abogado va ingresando a medida que el proceso avance.
Modificar sus datos de perfil y contraseña.

### Administrador (Abogado)
El administrador debe loguearse con la cuenta que les fue asignada
Ver solicitudes nuevas de demanda
Ingresar actualización en demandas anteriores: Selecciona demandas anteriores, luego en la lista selecciona la demanda a actualizar, luego un formulario para ingresar una actualización del proceso y los comentarios del mismo también puede solicitar un pago adicional para que el proceso continúe a la siguiente fase.
Ver pagos recibidos.

## Requerimientos:

1.	Sistema de sign in y sign up
2.	Formulario de nueva solicitud de consulta legal
3.	Formulario o pasarela de pago
4.	Visualización de actualizaciones en el proceso de la demanda
5.	Sign up para administradores
6.	Dashboard mostrando los pagos recibidos, las nuevas consultas solicitadas y en proceso
7.	Pantalla para hacer modificaciones, agregar comentarios y solicitar nuevos pagos de las demandas en proceso
8.	Crear documento legal en .docx automáticamente

## Buyer Persona:

Santiago Mendoza, Edad 30, Dueño de la concesionaria Mendoza Motors. Santiago es una persona muy activa. Es el primero en llegar a su trabajo y el último en irse. Estudió Contabilidad en la universidad porque siempre tuvo facilidad con las matemáticas y quería manejar las finanzas del negocio de su padre. Al graduarse empezó a trabajar tiempo completo en el negocio de su padre haciendo de esta una de las más exitosas del estado. Al pasar de los años compró la empresa a su padre, convirtiéndose en el único dueño. Tiene un grupo pequeño de amigos con los que les gusta salir a divertirse, pero rara vez encuentra tiempo para hacerlo. No tiene esposa aún, pero planea tenerla en los próximos años. 

**Personalidad:** Es una persona muy positiva y alegre. Le gusta tomar el liderazgo y tomar las decisiones. Disfruta de la compañía de sus amigos.

**Metas:** Sueña con convertir a su concesionaria en la primera del estado. Fundar franquicias en todo el país. Invertir en nuevos emprendimientos. Tener una familia.

**Frustraciones:** Que tenga que hacer todo por sí mismo por incompetencia de sus empleados. Tener que lidiar con cuestiones legales. No tener suficiente tiempo para otras actividades. Que ya tiene treinta años y aún no se ha casado.

**Necesidades:** Más tiempo para otras actividades fuera del trabajo. Necesita personas calificadas a su alrededor. Requiere de una familia para sentirse completo.

![Buyer Persona - Khisus19](https://github.com/khisus19/LaunchX-PrimeraSemana/blob/master/Buyer%20Persona%20-%20Santiago%20Mendoza.png)

## Público Objetivo:

### Perfil Geográfico:

-	Que vivan en Tabasco o Chiapas. 
-	Que hablen español. 
-	Habitantes urbanos.

### Perfil Demográfico:

-	Personas entre 28 y 50 años. 
-	Con ingresos de 8000 pesos en adelante. 
-	Sin distinción de género. 
-	Con título universitario. 
-	Trabajan en finanzas o negocios. 
-	Tienen vivienda propia.

### Perfil Psicográfico:

-	Que tengan un estilo de vida ocupado. 
-	Valoran el tiempo y no les gusta esperar. 
-	Han tenido problemas legales anteriormente. 
-	No están conformes con el manejo de sus asuntos legales actualmente. 

### Perfil de comportamiento:

-	Personas activas y trabajadoras. 
-	Son abiertos a las nuevas tecnologías. 
-	Buscan la rapidez en los servicios. 
-	Les gusta lo moderno. 
- Son activos en las redes sociales. 
- Les gusta el orden y quieren estar en control en todos los aspectos de su vida.

![Público Objetivo - Khisus19](https://github.com/khisus19/LaunchX-PrimeraSemana/blob/master/Publico%20Objetivo.png)

### User Experience - Wireframes

Por falta de tiempo solo hice 4 screens :)

![Ux 1](https://github.com/khisus19/LaunchX-PrimeraSemana/blob/master/UX/Abogabot%20-%20UX%20Wireframe_UX%201.jpg)
![Ux 2](https://github.com/khisus19/LaunchX-PrimeraSemana/blob/master/UX/Abogabot%20-%20UX%20Wireframe_UX%202.jpg)
![Ux 3](https://github.com/khisus19/LaunchX-PrimeraSemana/blob/master/UX/Abogabot%20-%20UX%20Wireframe_UX%203.jpg)
![Ux 4](https://github.com/khisus19/LaunchX-PrimeraSemana/blob/master/UX/Abogabot%20-%20UX%20Wireframe_UX%204.jpg)

## User Interface

Igual, solo 4 screens

![UI 1](https://github.com/khisus19/LaunchX-PrimeraSemana/blob/master/Ui/Abogabot%20-%20UI%201.jpg)
![UI 2](https://github.com/khisus19/LaunchX-PrimeraSemana/blob/master/Ui/Abogabot%20-%20UI%202.jpg)
![UI 3](https://github.com/khisus19/LaunchX-PrimeraSemana/blob/master/Ui/Abogabot%20-%20UI%203.jpg)
![UI 4](https://github.com/khisus19/LaunchX-PrimeraSemana/blob/master/Ui/Abogabot%20-%20UI%204.jpg)

