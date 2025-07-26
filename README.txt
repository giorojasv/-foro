# Proyecto API Foro - Desafío Alura

Esta API permite a los usuarios crear, listar y eliminar tópicos. Solo usuarios autenticados con JWT pueden modificar el contenido.

## Endpoints principales:
- `GET /topicos` - Lista todos los tópicos.
- `POST /topicos` - Crea un nuevo tópico (requiere autenticación).
- `DELETE /topicos/{id}` - Elimina un tópico (requiere autenticación).
- `POST /auth` - Devuelve un JWT válido al enviar login y contraseña.

Base de datos recomendada: PostgreSQL.