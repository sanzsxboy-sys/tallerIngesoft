# Especificación de Requerimientos

## 1. Descripción del sistema

## 2. Integrantes

- Nombre:sebastian sanchez sotelo
- Nombre:isabella forero duarte
- Nombre:jacobo cardona
- Nombre:miguel angel asprilla
- Nombre:kevin santiago delgado
- Nombre:santiago calero

## 3. Requerimientos Funcionales

### RF-01 - [registro de tutorias]

#### Resumen
los profesores tienen la oportunidad de ofrecer tutorias,con esto se necesitara registrar la informacion para que los estudiantes puedan estar informados con las tutorias, y para poder hacer esto se necesita codigo del profe,tema tutoria,fecha,hora inicio,cantidad maxima de estudiantes.

#### Entradas

| Entrada | Tipo de dato | Descripción |
|---|---|---|
|codigo_profe|Int|se necesita el codigo del profe para tutorias|
|tema tutoria|String|el tema central para que el estudiante este preparado|
|fecha(inicio)|localDate|la fecha donde se inicia la tutoria|
|cantidadMaxEstudiantes|Int|lo maximo que cabe en un salon de tutorias|


#### Reglas o condiciones
-se necesita registrar la informacion para que se pueda mostrar la tutoria
-se necesitara el codigo del profesor para que pueda aparecer la tutoria
-tambien se necesitara el tema de tutoria,la fecha,hora de inicio, cantidad maxima de estudiantes
-no se permitira una tutoria para una fecha anterior a la fecha actual
-la cantidad maxima de participantes debera estar entre 1 y 10.


#### Salidas

| Salida | Tipo de dato | Descripción |
|---|---|---|
|cuentaprofe|String|cuando se cree la cuenta del profesor se dara un aviso de que ya se creo la cuenta|

#### Resultado esperado
que el proceso se cumpla exitosamente
### RF-02 - [consultoria de tutorias]

#### Resumen

El usuario puede consultar tutorías en el sistema después de indicar la fecha deseada, y de manera opcional indicar un tema de interés, mostrando dentro del programa las tutorías en donde se indique en cada una de ellas, (Identificador de la tutoría,Tema,Profesor responsable, Fecha, Hora,Cantidad de cupos disponibles) En caso de que no existan tutorías que correspondan a la búsqueda se debe imprimir un mensaje informando.

#### Entradas

| FechaInteres | LocaleDate | Fecha en la cual el usuario esta interesado en buscar tutorias |

| temaInteres | String | Este es el tema de la tutoría del cual el usuario esta interesado |


#### Reglas o condiciones

- El estudiante debe indicar obligatoriamente una fecha para realizar la búsqueda.
- El estudiante puede indicar opcionalmente una asignatura o un tema de interés.
- El sistema debe mostrar únicamente las tutorías que correspondan con la fecha seleccionada.
- Si se especifica una asignatura o tema, el sistema debe filtrar las tutorías que coincidan con ese criterio.

- Por cada tutoría encontrada, el sistema debe mostrar:
(Identificador de la tutoría,Tema,Profesor responsable, Fecha, Hora,Cantidad de cupos disponibles)

Si no existen tutorías que cumplan con los criterios de búsqueda, el sistema debe mostrar un mensaje informativo indicando que no se encontraron tutorías.

La búsqueda debe permitir consultar las tutorías disponibles sin necesidad de especificar una asignatura o tema, siempre que se indique la fecha.


#### Salidas

| listaTutorias | String | Son las tutorías que se encuentran disponibles en el sistema y su informacion |

| mensajeNoEncontrado | String | Informa al usuario que el programa no cuenta con tutorias activas del tema seleccionado |


#### Resultado esperado

Como desarrolladores, esperamos que el usuario interactúe de forma intuitiva con el programa para agilizar sus consultas mediante un filtro donde la fecha es obligatoria y el tema es opcional, de este modo la plataforma entregará la información completa de las tutorías disponibles (Identificador de la tutoría,Tema,Profesor responsable, Fecha, Hora,Cantidad de cupos disponibles) o, en su defecto, desplegará el mensaje "no existen tutorías disponibles que coincidan con los criterios de búsqueda", evitando confusiones y optimizando el flujo de trabajo.

### RF-03 - [solicititud de inscipcion a la tutoria]

#### Resumen
El sistema debe permitir al estudiante solicitar un cupo para la asistir a la tutoria

#### Entradas

| Entrada | Tipo de dato | Descripción |
|---|---|---|
|idEstudiante|String|Codigo de identificacion del estudiante|
|idTutoria|String|Codigo de identificacion de la tutoria|

#### Reglas o condiciones
- El estudiante debe estar activo en la universidad. 
- La tutoria debe existir. 
- Debe haber cupo.
- El estudiante no debe encontrarse previamente escrito en la misma.
- Si el registro es exitoso se debera mostrar un mensaje de confirmacion, si no se notifica que no se pudo realizar la inscripcion.

#### Salidas

| Salida | Tipo de dato | Descripción |
|---|---|---|
|mensajeConfirmacion|String|Mensaje en caso de exito|
|mensajeError|String|Mensaje en caso de no cumplir alguna de las condiciones|

#### Resultado esperado
- En caso de que se cumplan todas las condiciones, la inscripcion se realiza y se actualizan la cantidad de cupos, por el contrario, si no se puede realizar la inscripcion, se muestra un mensaje explicando el motivo


### RF-04 - [cancelacion de participacion]

#### Resumen
En este rf de cancelación de participación, el sistema debe permitir al usuario de utilizar su codigo estudiantil y el id de la tutoria para realizar el proceso de cancelación, al momneto de cumplirse el proceso el sistema debe darle un mensaje de exito al usuario, además es necesario que el sistema libere el espacio de reserva, de no ser capaz de completarse el procedimiento un mensaje de error es presentado al usuario.

#### Entradas

| Entrada | Tipo de dato | Descripción |
|---|---|---|
|idEstudiante | int | un numero unico de estudiante
|idTutoria | int | un numero especifico de tutoria

#### Reglas o condiciones
Debe existir una reserva de tutoria y que la tutoria no haya empezado, además que los ids de ambas entradas sea correcto.

#### Salidas

| Salida | Tipo de dato | Descripción |
|---|---|---|
|mensajeDeExito | String | mensaje general de exito confirmando que el proceso fue cumplido|
|mensjaeDeFallo | String | mensaje especifico de fallo explicando que el proceso no se pudo cumplir por fallo al cumplir con los requisitos|

#### Resultado esperado
Que el sistema de el mensaje de confirmación salga confirmando que el resto de los procesos se cumplieron, esto significa que el sistema libero el espacio de reserva.


## 4. Gestión de Versiones

### Ramas utilizadas
- main
- develop
- feature/rf01
- feature/rf02
- feature/rf-03
- feature/rf04
- feat/docs


### Proceso de integración
main
   ↓
develop
   ↓
feature/*
   ↓
develop
   ↓
main

Se agrego una feature de docs para organizar la documentacion

### Conflictos encontrados
Hubo conflictos y se solucionaron dejando el codigo que se necesitaba y borrando lo viejo, el que entro en conflicto fue feature/rf-4 con develop
