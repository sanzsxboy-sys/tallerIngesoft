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
