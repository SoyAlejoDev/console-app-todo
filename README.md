# Console App Todo

Una aplicación de consola para la gestión de tareas con Node.js.

## Características

- Crear tareas
- Listar tareas
- Listar tareas completadas
- Listar tareas pendientes
- Completar tareas
- Borrar tareas

## Instalación

Para instalar las dependencias del proyecto, puedes usar:

```sh
pnpm i
```

O si prefieres npm:

```sh
npm i
```

## Uso

Para ejecutar la aplicación, usa:

```sh
pnpm start
```

O con npm:

```sh
npm start
```

## Dependencias

El proyecto usa las siguientes dependencias:

- `colors`: Para mejorar la visualización en la consola.
- `inquirer`: Para manejar la entrada del usuario en la consola.
- `uuid`: Para generar identificadores únicos para las tareas.

## Estructura del Proyecto

```
app/
│-- db/
│-- helpers/
│   ├── guardarArchivo.js
│   ├── inquirer.js
│   ├── mensajes.js
│-- model/
│   ├── tarea.js
│   ├── tareas.js
│-- node_modules/
│-- .gitignore
│-- app.js
│-- package.json
│-- pnpm-lock.yaml
│-- README.md
```

## Autor

Este proyecto fue desarrollado como una práctica de Node.js y gestión de tareas en consola
