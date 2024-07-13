### FileSystem (fs) en Node.js
El módulo `fs` en Node.js se utiliza para interactuar con el sistema de archivos del sistema operativo. Permite leer y escribir archivos, así como realizar operaciones relacionadas con el sistema de archivos.

### Middleware en Express
Un middleware en Express es una función que tiene acceso al objeto de solicitud (`req`), al objeto de respuesta (`res`) y a la siguiente función de middleware en el ciclo de solicitud-respuesta de la aplicación. Su propósito principal es ejecutar código intermedio para manejar la solicitud antes de que llegue a su ruta final.

### Endpoint en una API RESTful
Un endpoint en una API RESTful es una URL específica que representa un recurso o colección de recursos. Su función es proporcionar acceso a estos recursos mediante operaciones HTTP como GET, POST, PUT o DELETE.

### Verbos HTTP
Los verbos HTTP son métodos estándar utilizados para indicar la acción que se debe realizar en un recurso. Los más comunes son:
- **GET**: Obtener datos.
- **POST**: Crear nuevos datos.
- **PUT**: Actualizar datos existentes.
- **DELETE**: Eliminar datos existentes.

### JSON en API RESTful
JSON (JavaScript Object Notation) es un formato ligero de intercambio de datos que es ampliamente utilizado en las API RESTful debido a su simplicidad y facilidad de uso para estructurar datos.

### Enviando datos a lo largo de los verbos HTTP
- **Body de una petición**: Contiene datos enviados al servidor en una solicitud.
- **Body de una respuesta**: Contiene datos enviados desde el servidor en una respuesta.
- **Query de una petición**: Contiene parámetros de consulta enviados en la URL.
- **Params de una petición**: Contiene parámetros de ruta enviados en la URL.

### Verbo POST
- **Propósito**: Se utiliza para enviar datos nuevos al servidor.
- **Cuándo se utiliza**: Cuando se desea crear recursos nuevos en el servidor.
- **Diferencia con otros verbos**: A diferencia de GET, PUT y DELETE, POST crea nuevos datos en el servidor.
- **Envío de datos**: Los datos se envían en el cuerpo (`body`) de la solicitud HTTP.

### Verbo GET
- **Propósito**: Se utiliza para obtener datos del servidor.
- **Cuándo se utiliza**: Para recuperar recursos existentes del servidor.
- **Diferencia con otros verbos**: GET no modifica ni elimina datos en el servidor; solo los obtiene.
  
### Verbo PUT
- **Propósito**: Se utiliza para actualizar datos existentes en el servidor.
- **Cuándo se utiliza**: Cuando se desea modificar recursos existentes en el servidor.
- **Diferencia con otros verbos**: PUT modifica datos específicos, mientras que POST crea nuevos recursos.

### Verbo DELETE
- **Propósito**: Se utiliza para eliminar datos existentes en el servidor.
- **Cuándo se utiliza**: Cuando se desea eliminar recursos del servidor.
- **Diferencia con otros verbos**: DELETE elimina datos específicos, a diferencia de GET, POST y PUT.

### Status Code
Los códigos de estado HTTP indican el resultado de la solicitud. Algunos comunes son:
- **200 OK**: La solicitud se completó correctamente.
- **400 Bad Request**: La solicitud no se pudo procesar debido a un error en el cliente.
- **404 Not Found**: El recurso solicitado no se encontró en el servidor.
- **500 Internal Server Error**: Error interno en el servidor al procesar la solicitud.

### Status Code por verbo HTTP
- **POST**: 201 Created (cuando se crea un recurso), 400 Bad Request (errores de validación).
- **GET**: 200 OK (cuando se encuentra el recurso), 404 Not Found (cuando no se encuentra el recurso).
- **PUT**: 200 OK (cuando se actualiza el recurso), 404 Not Found (cuando no se encuentra el recurso a actualizar).
- **DELETE**: 204 No Content (cuando se elimina el recurso con éxito), 404 Not Found (cuando no se encuentra el recurso a eliminar).
