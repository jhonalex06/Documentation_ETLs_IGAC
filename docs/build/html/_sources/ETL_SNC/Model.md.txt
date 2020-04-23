Estructura del modelo
======================


Funciones involucradas
----------------------

* Corregir geometrías.
* Calculadora de campos.
* Eliminar vértices duplicados.
* Extraer por atributo.
* Insertar registros a la capa.
* Rehacer campos.
* Unir atributos por valor de campo.
* Unir capas vectoriales.

Flujo del diligenciamiento de tablas en el modelo LADM-COL
----------------------------------------------------------

GC_Predio_Catastro
------------------

1. Calculadora de campos.
2. Calculadora de campos.
3. Rehacer campos.
4. Insertar registros a la capa.
5. Calculadora de campos.
6. Calculadora de campos.
7. Rehacer campos.
8. Insertar registros a la capa.

    ![gc_predio](../_static/Model_Cobol/gc_predio.png "FLujo gc_predio.")

GC_Terreno
----------

1. Unir capas vectoriales. 
2. Corregir geometrías. 
3. Unir atributos por valor de campo. 
4. Unir atributos por valor de campo. 
5. Rehacer campos. 
6. Eliminar vértices duplicados. 
7. Insertar registros a la capa. 

    ![gc_terreno](../_static/Model_Cobol/gc_terreno.png "FLujo gc_terreno.")

GC_Comisiones_Terreno
---------------------

1. Unir capas vectoriales. 
2. Corregir geometrías. 
3. Unir atributos por valor de campo. 
4. Rehacer campos. 
5. Eliminar vértices duplicados. 
6. Insertar registros a la capa. 

    ![gc_comisiones_terreno](../_static/Model_Cobol/gc_comisiones_terreno.png "FLujo gc_comisiones_terreno.")

GC_Direccion
------------

1. Unir atributos por valor de campo. 
2. Unir atributos por valor de campo. 
3. Unir capas vectoriales. 

    --Ruta 1 

4. Unir atributos por valor de campo. 
5. Unir atributos por valor de campo. 
6. Rehacer campos. 

    --Ruta 2 

7. Extraer por atributo. 
8. Rehacer campos. 
9. Insertar registros a la capa. 
10. Insertar registros a la capa. 

    ![gc_direccion](../_static/Model_Cobol/gc_direccion.png "FLujo gc_direccion.")

GC_Construccion
---------------

1.  Unir capas vectoriales. 
2.  Corregir geometrías. 
3.  Unir atributos por valor de campo. 
4.  Rehacer campos. 
5.  Eliminar vértices duplicados. 
6.  Insertar registros a la capa. 

    ![gc_construccion](../_static/Model_Cobol/gc_construccion.png "FLujo gc_construccion.")

GC_Comisiones_Construccion
--------------------------

1.  Unir capas vectoriales. 
2.  Corregir geometrías. 
3.  Unir atributos por valor de campo. 
4.  Rehacer campos. 
5.  Eliminar vértices duplicados. 
6.  Insertar registros a la capa. 

    ![gc_comisiones_construccion](../_static/Model_Cobol/gc_comisiones_construccion.png "FLujo gc_comisiones_construccion.")

GC_Unidad_Construccion
----------------------

Nota: la parte superior hace referencia a la parte geográfica y la inferior a la alfanumérica. 

    Parte Superior  

1. Unir capas vectoriales. 
2. Corregir geometrías. 
3. Unir atributos por valor de campo. 
4. Rehacer campos. 

Parte Inferior 

5. Calculadora de campos. 
6. Calculadora de campos. 
7. Extraer por atributo x 3 (tres). 
8. Unir atributos por valor de campo x 3 (tres). 
9. Extraer por atributo x 3 (tres). 
10. Rehacer campos x 3 (tres). 
11. Unir capas vectoriales. 
12. Eliminar vértices duplicados. 
13. Insertar registros a la capa. 

    ![gc_unidad_construccion](../_static/Model_Cobol/gc_unidad_construccion.png "FLujo gc_unidad_construccion.")

GC_Comisiones_Unidad_Construccion
---------------------------------

1.  Unir capas vectoriales. 
2.  Corregir geometrías. 
3.  Unir atributos por valor de campo. 
4.  Rehacer campos. 
5.  Eliminar vértices duplicados. 
6.  Insertar registros a la capa. 

    ![gc_comisiones_construccion](../_static/Model_Cobol/gc_comisiones_unidad_construccion.png "FLujo gc_comisiones_construccion.")

GC_Propietario
--------------

1. Corregir geometrías. 
2. Rehacer campos. 
3. Eliminar vértices duplicados. 
4. Insertar registros a la capa.

    ![gc_propietario](../_static/Model_Cobol/gc_propietario.png "FLujo gc_propietario.")

GC_Perimetro
------------

1. Corregir geometrías. 
2. Rehacer campos. 
3. Eliminar vértices duplicados. 
4. Insertar registros a la capa.

    ![gc_perimetro](../_static/Model_Cobol/gc_perimetro.png "FLujo gc_perimetro.")

GC_Vereda
---------

1. Corregir geometrías. 
2. Rehacer campos. 
3. Eliminar vértices duplicados. 
4. Insertar registros a la capa.

    ![gc_vereda](../_static/Model_Cobol/gc_vereda.png "FLujo gc_vereda.")

GC_Manzana
----------

1. Corregir geometrías. 
2. Rehacer campos. 
3. Eliminar vértices duplicados. 
4. Insertar registros a la capa.

    ![gc_manzana](../_static/Model_Cobol/gc_manzana.png "FLujo gc_manzana.")

GC_Barrio
---------

1. Corregir geometrías. 
2. Rehacer campos. 
3. Eliminar vértices duplicados. 
4. Insertar registros a la capa.

    ![gc_barrio](../_static/Model_Cobol/gc_barrio.png "FLujo gc_barrio.")

GC_Sector_Urbano
----------------

1. Corregir geometrías. 
2. Rehacer campos. 
3. Eliminar vértices duplicados. 
4. Insertar registros a la capa.

    ![gc_sector_rural](../_static/Model_Cobol/gc_sector_urbano.png "FLujo gc_sector_urbano.")

GC_Sector_Rural
---------------

1. Corregir geometrías. 
2. Rehacer campos. 
3. Eliminar vértices duplicados. 
4. Insertar registros a la capa.

    ![gc_sector_rural](../_static/Model_Cobol/gc_sector_rural.png "FLujo gc_sector_rural.")