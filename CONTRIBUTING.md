# Cómo trabajamos en nivef-sofftware

## Ramas

La rama main es la versión estable: nadie trabaja directamente sobre ella. Cada tarea se hace en su propia rama, creada desde main.

Se nombran con el formato tipo/descripcion-corta, en minúscula y con guiones:

- feat/formulario-contacto
- fix/error-login
- docs/perfil-equipo
- chore/actualizar-gitignore

Para crear una rama y cambiar entre ellas:

bash
git switch main
git switch -c feat/formulario-contacto


## Commits

Usamos el formato tipo: qué hiciste, en minúscula y en presente.

| Tipo | Para qué |
|---|---|
| feat | Una funcionalidad nueva |
| fix | Corregir un error |
| docs | Documentación |
| chore | Configuración y mantenimiento |

Ejemplos:

- feat: agrega formulario de contacto
- fix: corrige error al iniciar sesión
- docs: añade perfil de nataly
- chore: ignora carpeta .venv

## Revisión de Pull Requests

*Quién revisa a quién*

- Todo Pull Request lo revisa al menos otra persona del equipo, nunca quien lo escribió.
- El líder de desarrollo (Juan David Estrada) revisa los cambios de src/.
- Cada integrante revisa los cambios de los demás de forma rotativa en los demás casos.

*Qué miramos antes de aprobar*

- Que el cambio haga lo que dice el título y la descripción.
- Que los commits sigan la convención.
- Que no se suban claves, contraseñas ni archivos generados (.env, .venv/, __pycache__/).
- Que el código o documento sea claro y fácil de leer.

## Cuándo se aprueba un Pull Request

Un Pull Request se aprueba cuando cumple todo esto:

- La rama tiene un nombre válido y parte de main actualizada.
- Los commits siguen el formato tipo: qué hiciste.
- Tiene una descripción clara de qué cambia y por qué.
- Tiene al menos una aprobación de un compañero.
- No tiene conflictos con main.
- Los comentarios de la revisión fueron atendidos.