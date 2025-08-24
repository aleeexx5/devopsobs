Para completar este ejercicio, debes: 

1. Modificar la configuración de Vector: 
    Actualizar el fichero vector.yaml para cambiar el sink de stdout a elasticsearch. 
    Configurar los detalles de conexión a Elasticsearch, incluyendo host y puerto. 
    Definir un nombre básico para el índice donde se almacenarán los logs. 
    
2. Comprobar cambios en Vector: 
    Aplicar los cambios de Vector para activar la nueva configuración. 

3. Verificación en Kibana: 
    Acceder a Kibana > Discover y verificar que los logs enviados por Vector están siendo recibidos correctamente en Elasticsearch. 
    Crear un Index Pattern en Kibana que permita visualizar los logs enviados por Vector. 