# git-work — flujo colaborativo con Git

Repositorio de práctica del flujo colaborativo (fork, issue, rama, PR,
conflicto, etiqueta y release) del módulo DPL.

## Índice

- [Entorno e instalación](#entorno-e-instalacion)
- [Configuración](#configuracion)
- [Comprobación](#comprobacion)
- [Problemas encontrados y solución](#problemas-encontrados-y-solucion)
- [Repositorio remoto](#repositorio-remoto)

## Entorno e instalación
Clonar el repositorio y abrir `index.html` en el navegador web.

## Configuración
En `css/cover.css`, la línea 10 define el color del botón principal y la línea 11 define su sombra visual.

## Comprobación
Comandos ejecutados y sus salidas reales para verificar la estructura del árbol de Git, tags y configuración remota (ver `comprobaciones.txt`).

## Problemas encontrados y solución

| Problema | Causa | Solución |
| --- | --- | --- |
| Fallo en GitHub Actions (CI) | Enlace relativo no soportado por `mkdocs build --strict` | Se eliminó el enlace relativo en `docs/index.md` |
| Conflicto de fusión en `css/cover.css` | Edición simultánea de la línea 10 en `main` local y la rama `cool-colors` | Se resolvió el conflicto a mano conservando los cambios de `user2` (`darkgreen`) |

## Repositorio remoto
- Repositorio principal: https://github.com/xerachrrm/git-work
- Repositorio espejo (fork): https://github.com/xerachrrm/git-work-espejo
