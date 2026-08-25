# Especificación de Requerimientos

## 1. Descripción del sistema

## 2. Integrantes

- Nombre:sebastian sanchez sotelo
- Nombre:isabela forero
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
El sistema debe permitir al estudiante solicitar un cupo para la asistir a la tutoria

#### Entradas

| Entrada | Tipo de dato | Descripción |
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
|mensajeConfirmacion|String|Mensaje en caso de exito|
|mensajeError|String|Mensaje en caso de no cumplir alguna de las condiciones|

#### Resultado esperado
- En caso de que se cumplan todas las condiciones, la inscripcion se realiza y se actualizan la cantidad de cupos, por el contrario, si no se puede realizar la inscripcion, se muestra un mensaje explicando el motivo


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
