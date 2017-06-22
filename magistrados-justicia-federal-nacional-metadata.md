Magistrados de la Justicia Federal y de la Justicia Nacional
==============================================================================

En este conjunto de datos se detalla la estructura y la nómina de jueces, fiscales y defensores de la Justicia Federal y de la Justicia Nacional de la República Argentina, estado de cobertura de cargos, estado de los concursos destinados a cubrir los cargos que se encuentran vacantes, decretos y/o resoluciones de designación y/o traslado de los jueces, fiscales o defensores y Presidente y Ministro de Justicia y Derechos Humanos en funciones al momento de la designación.

Lo detallado es el resultado del trabajo de la Oficina Decretos, dependiente de la Subsecretaría de Relaciones con el Poder Judicial y Asuntos Penitenciarios, la que tiene entre sus funciones llevar a cabo los procedimientos de preselección de magistrados regulados por los Decretos Nº 222/03 y Nº 588/03. Asimismo, interviene en el trámite de aceptación de renuncia de magistrados y traslado de jueces conforme a lo previsto en la Constitución Nacional y reglamentación complementaria. 

La actualización de la información relativa a subrogancias, vacancias, estado de tramitación de los concursos en el ámbito del Consejo de la Magistratura y los Ministerios Públicos, se realiza a través de un constante relevamiento telefónico con soporte en las páginas oficiales de los organismos mencionados. 


Características
---------------

- **Fecha de Primera Publicación:** 14/09/2016

- **Tags o Etiquetas:** judicial, juez, fiscal, defensor, magistrado, vacante, órgano, cargo, subrogante, concurso, federal, nacional, justicia

- **Organización:** Ministerio de Justicia y Derechos Humanos. Secretaría de Justicia. Subsecretaría de Relaciones con el Poder Judicial y Asuntos Penitenciarios

- **Autor:** Ministerio de Justicia y Derechos Humanos. Secretaría de Justicia. Subsecretaría de Relaciones con el Poder Judicial y Asuntos Penitenciarios

- **Responsable:** Ministerio de Justicia y Derechos Humanos. Secretaría de Justicia. Subsecretaría de Relaciones con el Poder Judicial y Asuntos Penitenciarios

- **Grupo:** Poder Judicial

- **Frecuencia de Actualización:** Eventual

Recursos disponibles
--------------------

### Magistrados de la Justicia Federal y de la Justicia Nacional - estado al dd-mm-aaaa

- **Nombre:** magistrados-justicia-federal-nacional - estado al dd-mm-aaaa.csv

- **Descripción:** Nómina de jueces, fiscales y defensores de la Justicia Federal y de la Justicia Nacional.  No se incluyen los magistrados de la Corte Suprema de Justicia de la Nación, de la Procuración General de la Nación ni de la Defensoría General de la Nación.

- **Formato:** CSV delimitado por comas, codificado en UTF-8

- **Rango temporal:** listado actualizado a la fecha consignada como "Datos actualizados al"

### Campos del recurso

- **orden (int):** Número correlativo

- **justicia_federal_o_nacional (string):** Indica si se trata de un órgano de la justicia federal o nacional. Toma los valores Federal/Nacional

- **camara (string):** Cámara de la que depende el órgano

- **tipo_organo (string):** Tipo órgano. Toma los valores Cámara/Tribunal/Juzgado/Fiscalía/Defensoría

- **nombre_organo (string):** Nombre del órgano

- **organo_habilitado (string):** Habilitación del órgano. Toma los valores Sí/No

- **tipo_cargo (string):** Tipo de cargo. Toma los valores juez, fiscal o defensor

- **nombre_magistrado (string):** Nombre del juez, fiscal o defensor

- **genero (string):** Género del magistrado

- **cobertura (string):** Tipo de cobertura del cargo. Toma los valores Titular/Subrogante/Sin subrogante designado/No corresponde (en el caso de los cargos no habilitados)

- **presidente_camara (string):** Describe si el magistrado es presidente de cámara. Toma los valores Sí/No

- **vacante (string):** Describe si el cargo está vacante. Toma los valores Sí/No

- **licencia (string):** Describe si el juez, fiscal o defensor titular está de licencia. Toma los valores Sí/No

- **concurso_en_tramite (string):** Describe si el cargo tiene o no concurso asignado para la cobertura de la vacante

- **numero_concurso (string):** Número de concurso asignado a los cargos que se encuentran vacantes

- **ambito_concurso (int):** Ámbito en el que se encuentra tramitando el concurso

- **calidad_subrogante (string):** Describe la calidad de subrogante. Toma los valores Convocado (si es un juez jubilado)/ juez/a (es juez/a en otro órgano) / fiscal (es fiscal en otro órgano) / defensor/a (es defensor/a en otro órgano) / Sin especificación (es subrogante pero no se especifica su calidad de surogancia)

- **fecha_movimiento (date):** Fecha de designación o traslado del juez, fiscal o defensor titular del cargo

- **norma_movimiento (string):** Número del decreto o resolución de designación o traslado

- **tipo_movimiento (string):** Toma los valores Designación o traslado

- **presidente (string):** Nombre del Presidente en ejercicio a la fecha de la designación o traslado

- **ministro (string):** Nombre del Ministro de Justicia y Derechos Humanos a la fecha de la designación o traslado
