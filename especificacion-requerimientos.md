# Especificación de Requerimientos

## 1. Descripción del sistema

## 2. Integrantes

- Nombre:sebastian sanchez sotelo
- Nombre:isabella forero duarte
- Nombre:juan esteban peña
- Nombre:
- Nombre:

## 3. Requerimientos Funcionales

### RF-01 - [registro de tutorias]

#### Resumen

#### Entradas

| Entrada | Tipo de dato | Descripción |
|---|---|---|

#### Reglas o condiciones

#### Salidas

| Salida | Tipo de dato | Descripción |
|---|---|---|

#### Resultado esperado


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

#### Entradas

| Entrada | Tipo de dato | Descripción |
|---|---|---|

#### Reglas o condiciones

#### Salidas

| Salida | Tipo de dato | Descripción |
|---|---|---|

#### Resultado esperado


### RF-04 - [cancelacion de participacion]

#### Resumen

#### Entradas

| Entrada | Tipo de dato | Descripción |
|---|---|---|

#### Reglas o condiciones

#### Salidas

| Salida | Tipo de dato | Descripción |
|---|---|---|

#### Resultado esperado


## 4. Gestión de Versiones

### Ramas utilizadas

### Proceso de integración

### Conflictos encontrados
