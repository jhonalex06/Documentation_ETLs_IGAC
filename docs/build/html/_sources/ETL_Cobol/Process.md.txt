Procedimiento para ejecutar el ETL
==================================

1. Abrir QGIS. 
2. Instalar el Asistente LADM-COL. 
3. Seleccionar LADM-COL -> Administración de datos -> Crear estructura LADM-COL. 
4. Realizamos clic en la opción, Configurar conexión. 
5. Diligenciamos los datos de Host, Puerto, Usuario, Contraseña y realizamos clic en Refrescar bases de datos y esquemas. 
6. Seleccionamos la base de datos y el esquema en donde queremos crear la estructura de LADM-COL, por último, clic en Aceptar. 

    ![Config_database](../_static/Process_Cobol/config_database.png "Configuración base de datos.")

7. En la interfaz que se despliega, seleccionamos el SRC de nuestros datos, el modelo Datos_Gestor_Catastral_V2_9_6 y clic en Crear estructura LADM-COL. 

    ![create_structure](../_static/Process_Cobol/create_structure.png "Creación de la estructura LADM-COL.")

8. Una vez se ha creado la estructura de Datos_Gestor_Catastral, se da clic en Cerrar. 
9. Seleccionar LADM-COL -> Gestión de insumos de datos -> Crear estructura LADM-COL. 
10. Seleccionar ETL para datos Cobol -> Clic en Next 

    ![initial_etl_snc](../_static/Process_Cobol/initial_etl_snc.png "Selección del ETL-SNC.")

11. Seguido es necesario cargar cada uno de los archivos con extensión .lis y definir la base de datos destino a partir del botón configurar conexión -> seleccionamos el esquema en el que deseamos crear los datos.
12. Por último, clic en Ejecutar ETL.

    ![supplies_etl_snc](../_static/Process_Cobol/supplies_etl_snc.png "Cargue de los insumos del ETL-SNC.")

13. Por último, se obtiene un resumen de los datos transferidos al modelo LADM-COL y clic en finalizar.

    ![result_etl_snc](../_static/Process_Cobol/result_etl_snc.png "Resultado del ETL-SNC.")