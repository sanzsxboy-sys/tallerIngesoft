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

#### Entradas

| Entrada | Tipo de dato | Descripción |
|---|---|---|

#### Reglas o condiciones

#### Salidas

| Salida | Tipo de dato | Descripción |
|---|---|---|

#### Resultado esperado


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
## En este rf de cancelación de participación, el sistema debe permitir al usuario de utilizar su codigo estudiantil y el id de la tutoria para realizar el proceso de cancelación, al momneto de cumplirse el proceso el sistema debe darle un mensaje de exito al usuario, además es necesario que el sistema libere el espacio de reserva, de no ser capaz de completarse el procedimiento un mensaje de error es presentado al usuario. 
#### Entradas

| Entrada | Tipo de dato | Descripción |
|---|---|---|
## |idEstudiante | int | un numero unico de estudiante
## |idTutoria | int | un numero especifico de tutoria

#### Reglas o condiciones
## Debe existir una reserva de tutoria y que la tutoria no haya empezado, además que los ids de ambas entradas sea correcto.

#### Salidas

| Salida | Tipo de dato | Descripción |
|---|---|---|
## |mensajeDeExito | String | mensaje general de exito confirmando que el proceso fue cumplido|
## |mensjaeDeFallo | String | mensaje especifico de fallo explicando que el proceso no se pudo cumplir por fallo al cumplir con los requisitos|

#### Resultado esperado
## Que el sistema de el mensaje de confirmación salga confirmando que el resto de los procesos se cumplieron, esto significa que el sistema libero el espacio de reserva.

## 4. Gestión de Versiones

### Ramas utilizadas
## develop, feature/rf4
### Proceso de integración
## atravez del proceso se utilizo el proceso de commits
### Conflictos encontrados
## pues la persona que se encarga de los merges VA A ENCONTRAR conflictos por lo que cada uno de los integrantes trabajo por su cuenta 
