# Especificación de Requerimientos

## 1. Descripción del sistema

## 2. Integrantes

- Nombre:sebastian sanchez sotelo
- Nombre:isabela forero
- Nombre:santiago calero
- Nombre:kevin delgado
- Nombre:miguel asprilla
- Nombre:jacobo cardona

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
se utilizaron las ramas main,develop
features/rf1:se hizo el analisis de requerimiento 1 como entradas,salidas,tipo de dato,descripcion
### Proceso de integración
cree mi propio branch y atravez del proceso se utilizo la evolucion de los commits
### Conflictos encontrados
no hubieron conflictos al subir los commits
