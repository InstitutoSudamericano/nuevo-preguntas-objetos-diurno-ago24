**Video de YouTube:** https://youtu.be/X7vuSKG1vjg
### Pregunta 1:

¿Qué método HTTP deberías utilizar para actualizar recursos existentes en un controlador de NestJS?

a) GET

b) PUT

c) POST

- Respuesta:

b) PUT. Cuando trabajamos con controladores en NestJS y necesitamos actualizar un recurso existente en el servidor, utilizamos el método PUT. Esto se debe a que PUT se encarga de reemplazar completamente un recurso existente con los nuevos datos proporcionados. 

### Pregunta 2:

¿Cuál es el método HTTP apropiado para recuperar datos de un recurso en un controlador de NestJS?

a) GET

b) PUT

c) POST

- Respuesta:

a) GET. Cuando necesitamos obtener datos de un recurso en un servidor sin realizar cambios en ese recurso, utilizamos el método GET. En el contexto de un controlador de NestJS, al manejar una solicitud GET, respondemos con los datos del recurso solicitado. Por ejemplo, si queremos obtener los detalles de un usuario, utilizamos GET para devolver esos datos sin modificar el estado del usuario en la base de datos.

### Pregunta 3:

¿Qué método HTTP deberías usar para crear un nuevo recurso en un controlador de NestJS?

a) GET

b) PUT

c) POST

- Respuesta:

c) POST. Cuando necesitamos crear un nuevo recurso en el servidor, como agregar un nuevo registro a una base de datos, utilizamos el método POST. Al manejar una solicitud POST en un controlador de NestJS, procesamos los datos enviados en el cuerpo de la solicitud para crear y almacenar el nuevo recurso. 