
--------------------------------------------------------------------------

Los servicios web que implementan los [[Principios REST]] se denominan servicios RESTful. Las API's web implementadas a través de servicios RESTful reciben el nombre de API's RESTful
Un servicio RESTful permite interaccionar de forma programática con un recurso e implementa una o varias operaciones CRUD (Creative, Retrieve, Update, Delete) sobre el recurso


| **Operación** | **Método HTTP** |
| ------------- | --------------- |
| Crear         | POST            |
| Consultar     | GET             |
| Actualizar    | PUT / PATCH     |
| Eliminar      | DELETE          |


|            | URL                 | Descripción                                                                                           |
| ---------- | ------------------- | ----------------------------------------------------------------------------------------------------- |
| **GET**    | /departamentos      | Obtiene todos los departamentos                                                                       |
| **GET**    | /departamentos/{id} | Obtiene el departamento con departamentoId={id}                                                       |
| **POST**   | /departamentos      | Inserta un nuevo departamento con los valores indicados en el body de la petición                     |
| **PUT**    | /departamentos/{id} | Actualiza el departamento con departamentoId={id} con los valores indicados en el body de la petición |
| **DELETE** | /departamentos/{id} | Elimina el departamento con departamentoId={id}                                                       |
