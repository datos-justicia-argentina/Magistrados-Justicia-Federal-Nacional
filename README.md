Magistrados de la Justicia Federal y de la Justicia Nacional
==============================================================================

En este conjunto de datos se detalla la estructura y la nómina de jueces, fiscales y defensores de la justicia nacional y de la justicia federal de la República Argentina, estado de cobertura de cargos, estado de los concursos destinados a cubrir los cargos que se encuentran vacantes, decretos y/o resoluciones de designación y/o traslado de los jueces, fiscales o defensores y Presidente y Ministro de Justicia y Derechos Humanos en funciones al momento de la designación.

Características
---------------

- **Fecha de Publicación:** 14/09/2016

- **Recurso:** Guía Judicial de la Justicia Nacional y de la Justicia Federal

- **Tags o Etiquetas:** judicial, juez, fiscal, defensor, magistrado, vacante, órgano, cargo, subrogante, concurso, federal, nacional, justicia

- **Organización:** Ministerio de Justicia y Derechos Humanos. Secretaría de Justicia. Subsecretaría de Relaciones con el Poder Judicial y Asuntos Penitenciarios

- **Autor:** Ministerio de Justicia y Derechos Humanos. Secretaría de Justicia. Subsecretaría de Relaciones con el Poder Judicial y Asuntos Penitenciarios

- **Responsable:** Ministerio de Justicia y Derechos Humanos. Secretaría de Justicia. Subsecretaría de Relaciones con el Poder Judicial y Asuntos Penitenciarios

- **Grupo:** Poder Judicial

- **Frecuencia de Actualización:** Eventual

Recursos disponibles
--------------------

### Magistrados de la Justicia Nacional y de la Justicia Federal

- **Nombre:** magistrados-justicia-federal-nacional.csv

- **Descripción:** Nómina de jueces, fiscales y defensores de la justicia nacional y de la justicia federal

- **Formato:** CSV delimitado por coma

- **Rango temporal: listado actualizado a la fecha consignada como "Fecha de actualización de los datos"

### Campos del recurso

- **orden (int):** Número correlativo

- **alzada (string):** Descripción de la Cámara de la que depende el órgano

- **nombre_organo (string):** Nombre del órgano

- **nombre_magistrado (string):** Nombre del juez, fiscal o defensor

- **cobertura (string):** Tipo de cobertura del cargo (titular, subrogante, presidente de cámara, convocado/a)

- **vacante_licencia (string):** Describe si el cargo está vacante o el juez, fiscal o defensor titular está de licencia

- **numero_concurso (string):** Número de concurso asignado a los cargos que se encuentran vacantes

- **ambito_concurso (int):** Ámbito en el que se encuentra tramitando el concurso

- **fecha_designacion (date):** Fecha de designación o traslado del juez, fiscal o defensror titular del cargo

- **decreto (string):** Número del decreto de designación o traslado

- **presidente (string):** Nombre del Presidente en ejercicio a la fecha de la designación o traslado

- **ministro (string):** Nombre del Ministro de Justicia y Derechos Humanos a la fecha de la designación o traslado

### Designaciones de magistrados de la justicia Federal y Nacional

- **Nombre:** magistrados-justicia-federal-nacional-designaciones.csv

- **Descripción:** Información de la designación de jueces, fiscales y defensores de la justicia nacional y de la justicia federal

- **Formato:** CSV delimitado por coma

- **Rango temporal: listado actualizado a la fecha consignada como "Fecha de actualización de los datos"

### Campos del recurso

- **alzada (string):** Descripción de la Cámara de la que depende el órgano

- **nombre_organo (string):** Nombre del órgano

- **detalle_cargo (string):** Nombre del cargo del juez, fiscal o defensor

- **nombre_magistrado (string):** Nombre del juez, fiscal o defensor

- **dni_magistrado (int):** número de dni del juez, fiscal o defensor

- **fecha_designacion (date):** Fecha de designación del juez, fiscal o defensror

- **decreto_designacion (string):** Número del decreto de designación del juez, fiscal o defensror

- **fecha_decreto (date):** Fecha del decreto o resolución de designación del juez, fiscal o defensror

- **concurso (string):** Número y ámbito del concurso de designación

- **presidente (string):** Nombre del Presidente en ejercicio a la fecha de la designación

- **ministro (string):** Nombre del Ministro de Justicia y Derechos Humanos a la fecha de la designación

### Renuncia de magistrados de la justicia Federal y Nacional

- **Nombre:** magistrados-justicia-federal-nacional-renuncias.csv

- **Descripción:** Información de la renuncia de jueces, fiscales y defensores de la justicia nacional y de la justicia federal

- **Formato:** CSV delimitado por coma

- **Rango temporal: listado actualizado a la fecha consignada como "Fecha de actualización de los datos"

### Campos del recurso

- **alzada (string):** Descripción de la Cámara de la que depende el órgano

- **nombre_organo (string):** Nombre del órgano

- **detalle_cargo (string):** Nombre del cargo del juez, fiscal o defensor

- **nombre_magistrado (string):** Nombre del juez, fiscal o defensor

- **dni_magistrado (int):** número de dni del juez, fiscal o defensor

- **fecha_renuncia (date):** Fecha de aceptación de la renuncia del juez, fiscal o defensror

- **decreto_renuncia (string):** Número del decreto de aceptación de la renuncia del juez, fiscal o defensror

- **fecha_decreto (date):** Fecha del decreto o resolución de aceptación de la renuncia del juez, fiscal o defensror

- **motivo (string):** Motivo que desencadenó la renuncia

- **presidente (string):** Nombre del Presidente en ejercicio a la fecha de la renuncia

- **ministro (string):** Nombre del Ministro de Justicia y Derechos Humanos a la fecha de la renuncia
