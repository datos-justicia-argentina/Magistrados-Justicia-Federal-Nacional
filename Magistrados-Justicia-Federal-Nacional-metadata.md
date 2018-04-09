Magistrados de la Justicia Federal y de la Justicia Nacional
==============================================================================

En este conjunto de datos se detallan la estructura y la nómina de jueces, fiscales y defensores de la Justicia Federal y de la Justicia Nacional de la República Argentina, estado de cobertura de cargos, estado de los concursos destinados a cubrir los cargos que se encuentran vacantes, decretos y/o resoluciones de designación y/o traslado de los jueces, fiscales o defensores y Presidente y Ministro de Justicia y Derechos Humanos en funciones al momento de la designación.

Lo detallado es el resultado del trabajo de la Oficina Decretos, dependiente de la Subsecretaría de Relaciones con el Poder Judicial y Asuntos Penitenciarios, la que tiene entre sus funciones llevar a cabo los procedimientos de preselección de magistrados regulados por los Decretos Nº 222/03 y Nº 588/03. Asimismo, interviene en el trámite de aceptación de renuncia de magistrados y traslado de jueces conforme a lo previsto en la Constitución Nacional y reglamentación complementaria. 

La actualización de la información relativa a subrogancias, vacancias, estado de tramitación de los concursos en el ámbito del Consejo de la Magistratura y los Ministerios Públicos, se realiza a través de un constante relevamiento telefónico con soporte en las páginas oficiales de los organismos mencionados. 

http://datos.jus.gob.ar/dataset/magistrados-justicia-federal-y-de-la-justicia-nacional

Características
---------------

- **Fecha de Primera Publicación:** 14/09/2016

- **Tags o Etiquetas:** judiciales, jueces, fiscales, defensores, magistrados, vacantes, órganos, cargos, subrogantes, concursos, federales, nacionales, justicia

- **Organización:** Ministerio de Justicia y Derechos Humanos. Secretaría de Justicia. Subsecretaría de Relaciones con el Poder Judicial y Asuntos Penitenciarios

- **Autor:** Ministerio de Justicia y Derechos Humanos. Secretaría de Justicia. Subsecretaría de Relaciones con el Poder Judicial y Asuntos Penitenciarios

- **Responsable:** Ministerio de Justicia y Derechos Humanos. Secretaría de Justicia. Subsecretaría de Relaciones con el Poder Judicial y Asuntos Penitenciarios

- **Grupo:** Poder Judicial

- **Frecuencia de Actualización:** Eventual

Recursos disponibles
--------------------

### Magistrados de la Justicia Federal y de la Justicia Nacional - AAAA-MM-DD

- **Nombre:** magistrados-justicia-federal-nacional-AAAA-MM-DD.csv

- **Descripción del contenido:** se detalla la nómina de jueces, fiscales y defensores de la Justicia Federal y de la Justicia Nacional.  No se incluyen los magistrados de la Corte Suprema de Justicia de la Nación, de la Procuración General de la Nación ni de la Defensoría General de la Nación

- **Formato:** CSV delimitado por comas, codificado en UTF-8

- **Rango temporal:** nómina de jueces, fiscales y defensores de la Justicia Federal y de la Justicia Nacional desde el año 1976 hasta la fecha consignada como "Datos actualizados al"

### Campos del recurso

- **orden (int):** número correlativo que permite ordenar los órganos por tipo de justicia, cámaras, salas, juzgados, tribunales y ministerio público

- **justicia_federal_o_nacional (string):** indica si se trata de un órgano de la justicia federal o nacional. Toma los valores Federal/Nacional

- **camara (string):** cámara de la que depende el órgano

- **organo_tipo (string):** tipo órgano. Toma los valores Cámara/Tribunal/Juzgado/Fiscalía/Defensoría

- **organo_nombre (string):** nombre del órgano

- **organo_habilitado (string):** habilitación del órgano. Toma los valores Sí/No

- **cargo_tipo (string):** tipo de cargo. Toma los valores juez, fiscal o defensor

- **magistrado_nombre (string):** nombre del juez, fiscal o defensor

- **magistrado_sexo (string):** sexo del magistrado

- **cargo_cobertura (string):** tipo de cobertura del cargo. Toma los valores Titular/Subrogante/Sin subrogante designado/No corresponde (en el caso de los cargos no habilitados)

- **presidente_camara (string):** describe si el magistrado es presidente de cámara. Toma los valores Sí/No

- **cargo_vacante (string):** describe si el cargo está vacante. Toma los valores Sí/No

- **cargo_licencia (string):** describe si el juez, fiscal o defensor titular está de licencia. Toma los valores Sí/No

- **concurso_en_tramite (string):** describe si el cargo tiene o no concurso asignado para la cobertura de la vacante

- **concurso_numero (string):** número de concurso asignado a los cargos que se encuentran vacantes

- **concurso_ambito (int):** ámbito en el que se encuentra tramitando el concurso

- **calidad_subrogante (string):** describe la calidad de subrogante. Toma los valores Convocado (si es un juez jubilado)/ juez/a (es juez/a en otro órgano) / fiscal (es fiscal en otro órgano) / defensor/a (es defensor/a en otro órgano) / Sin especificación (es subrogante pero no se especifica su calidad de surogancia)

- **norma_fecha (date):** fecha de designación o traslado del juez, fiscal o defensor titular del cargo

- **norma_movimiento (string):** número del decreto o resolución de designación o traslado

- **norma_tipo (string):** toma los valores Designación o traslado

- **norma_presidente (string):** nombre del Presidente en ejercicio a la fecha de la designación o traslado

- **norma_ministro (string):** nombre del Ministro de Justicia y Derechos Humanos a la fecha de la designación o traslado

### Magistrados de la Justicia Federal y de la Justicia Nacional - AAAA

- **Nombre:** magistrados-justicia-federal-nacional-AAAA.zip

- **Descripción del contenido:** archivo comprimido correspondiente al año AAAA con los archivos publicados en el portal datos.jus.gob.ar durante dicho año

- **Formato:** ZIP

Notas
-----
Este Conjunto de datos es publicado en el Portal de Datos Abiertos de la Justicia Argentina mediante [Resolución Nº 986 del Ministerio de Justicia y Derechos Humanos](http://datos.jus.gob.ar/resoluciones/RESOL-2016-986-E-APN-MJ.pdf), del 26 de Octubre de 2016.
