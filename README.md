# nivef-sofftware

nivef-sofftware es una empresa tecnológica que desarrolla soluciones de software a la medida.
Este repositorio reúne el código, la documentación y la información del equipo que trabaja en los encargos.

## Integrantes

| Nombre | Usuario de GitHub | Rol |
|---|---|---|
| Juan David Estrada | @arangojuandavid438-code | Líder de desarrollo |
| Nataly Sierra | @natysierra007-afk | Desarrolladora Frontend |
| Miguel Seguro | @miguel18-collab | Desarrollador Backend |
| Jhon Flores | @ELPO-star | Diseñador UI/UX |
| José Murillo | @JoSeSiTo712 | QA / Tester |

## Cómo está organizado el repositorio

```
nivef-sofftware/
├── README.md
├── CONTRIBUTING.md
├── .gitignore
├── docs/
├── equipo/
└── src/
```

| Elemento | Para qué sirve |
|---|---|
| `README.md` | Es la portada. GitHub lo muestra automáticamente al abrir el repositorio. |
| `CONTRIBUTING.md` | Las reglas para trabajar en este repositorio. GitHub lo reconoce y lo enlaza cuando alguien abre un issue o un Pull Request. |
| `src/` | El código fuente (source). Aquí van a vivir las automatizaciones de los encargos. Hoy queda vacía. |
| `docs/` | La documentación que no cabe en el README. Aquí van las bitácoras. |
| `equipo/` | Los perfiles de los integrantes. |
| `.gitignore` | La lista de lo que Git no debe guardar. La regla: se ignora lo generado, pesado o secreto. |

### Lo que ignoramos hoy

- `__pycache__/`: carpeta que Python crea sola al ejecutar el código.
- `.venv/`: donde quedan instaladas las librerías.
- `.env`: archivo donde se guardan claves y contraseñas.

### ¿Qué es `.gitkeep`?

Git no guarda carpetas vacías. Para que `src/` y `docs/` existan en el repositorio se les pone adentro un archivo vacío que, por costumbre, se llama `.gitkeep`.

## Cómo trabajar

Antes de aportar, lee [CONTRIBUTING.md](CONTRIBUTING.md).
