## Cheatsheet dataset grupo 4
 [Referencia](https://ucdp.uu.se/downloads/ged/ged251.pdf)

Descripcion de las columnas:

- id                 -> Identificador unico de cada evento (int)
- relid              -> Legacy, no deberiamos usarlo
- year               -> Ano del evento (int)
- active_year        -> Si el evento pertenece a uun conflicto/diada/actor-year (bool) 
- code_status        -> Siempre "clear". Esta no la entiendo del todo (string)
- type_of_violence   -> 1 para Conflicto de estado, 2 para Conflicto no de estado, 3 para Violencia unilateral (int)
- conflict_dset_id  ->  No deberia ser usado
- conflict_new_id   ->  Identificador unico de conflicto (int)
- conflict_name     ->  Nombre del conflicto (string)
- dyad_dset_id     ->  No deberia ser usado
- dyad_new_id      ->  Identificador unico de la diada (int)
- dyad_name        ->  Nombre de la diada. La diada son los 2 actores del conflicto. Las partes se separan por un "-" (string)
- side_a_dset_id    ->  No deberia ser usado (int)
- side_a_new_id     ->  Identificador unico del actor 1 (int)
- side_a            ->  Nombre del actor 1 (string)
- side_b_dset_id    ->  No deberia ser usado (int)
- side_b_new_id     ->  Identificador unico del actor 2 (int)
- side_b            ->  Nombre del actor 2 (string)
- number_of_sources -> Numero de fuentes relativas al evento, solo disponible en datos posteriores a 2013. Es -1 para los anteriores.(int)
- source_article    -> Referncia a las fuentes. Deberia haber almenos 1 por cada evento. (text)
- source_office     -> Organizacion publicadora del material fuente. Valido a partir de 2013. (text)
- source_date       -> Fecha de publicacion del material fuente. Valido a partir de 2013. (text)
- source_headline   -> Titulo del material fuente. Valido a partir de 2014 y para algunas de 2013. (text)
- source_original   -> Nombre, cargo, organizacion, etc que produjo el reporte (string)
- where_prec        -> Grado de precision de las coordenadas del evento. Usa numeros del 1 al 7, referise a documento. (int)
- where_coordinates -> Nombre de la localizacion (string)
- where_description -> Descripcion de la localizacion, es valido que este vacio (string)
- adm_1             -> Nombre de la division mayor donde ocurrio el evento (string)
- adm_2             -> Nombre de la division de segundo orden donde ocurrio el evento (string)
- latitude          -> Latitud en grados decimales (float)
- longitude         -> Longitud en grados decimales (float)
- geom_wkt          -> Representacion textual de la localizacion siguiendo un formato OGC WKT (string)
- priogrid_grid     -> ID de locacion en PRIO-GRID (int)
- country           -> Nombre del pais donde ocurrio el evento (string)
- country_id        -> Identificador unico del pais donde ocurrio el evento segun codigo Gleditsch and Ward(int)
- region            -> Nombre de la region donde ocurrio el evento, solo puede ser {Africa, Americas, Asia, Europe, Middle East} (string)
- event_clarity     -> Puede ser 1 si el evento es "discrimable", es decir no es un agregado de varios sucesos o 2 en caso contrario (int)
- date_prec         -> Grado de precision de la fecha, entre 1-5 (int)
- date_start        -> Fecha de inicio del evento (datetime YYYY-MM-DD)
- date_end          -> Fecha de finalizacion del evento (datetime YYYY-MM-DD)
- deaths_a          -> Mejor estimativo de muertes del actor 1 (int)
- deaths_b          -> Mejor estimativo de muertes del actor 2 (int)
- deaths_civilians  -> Mejor estimativo de muertes civiles
- deaths_unknown    -> Mejor estimativo de muertes desconocidas
- best              -> Suma de todas las muertes de antes (int)
- high              -> El numero confiable maximo de muertes estimadas (int)
- low               -> El numero confiable minimo de muertes estimadas (int)
- gwnoa             -> ID en codigo Gleditsch and Ward del bando A. Si no es un estado, esta vacia (string)
- gwnob             -> ID en codigo Gleditsch and Ward del bando B. Si no es un estado, esta vacia (string)









