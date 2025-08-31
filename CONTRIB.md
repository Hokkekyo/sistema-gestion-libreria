# Guía de colaboración – TP Integrador: Sistema de gestión librería

*Este archivo define cómo colaborar correctamente en el proyecto para evitar*
*conflictos y trabajar de forma ordenada entre los integrantes del grupo.*

## Antes de empezar a trabajar:
1. Entrá al directorio del proyecto:
```sh
cd sistema-gestion-libreria/
```

2. Traé la última versión del proyecto desde GitHub:
```sh
git pull
```

## Para guardar tus cambios:
1. Verificá qué archivos modificaste (éste comando no es necesario para guardar los cambios):
```sh
git status
```

2. Agregá los cambios al área de staging.
El punto . selecciona todos los archivos dentro del directorio actual (directorio raíz del proyecto). También podés agregar archivos o carpetas de forma específica:
```sh
git add .           # Agrega todos los archivos modificados en el directorio actual y sus subdirectorios
git add CONTRIB.md  # Ejemplo: agrega un archivo específico
```

3. Hacé el commit (guarda los cambios que agregaste al staging) con un mensaje claro:
```sh
git commit -m "Descripción breve y clara de lo que hiciste"
```

4. Subí tus cambios al repo:
```sh
git push
```

## Reglas para los mensajes de commit
```markdown
## Escribí mensajes cortos, ejemplos:
“Agrego módulo de productos”,
“Corrijo error en validación de login”,
“Update README”.
```

## Buenas prácticas:
```text
• Usar nombres de variables y funciones descriptivos.
• Mantener el main.cpp lo más limpio posible.
• Mover la lógica a funciones en funciones.cpp.
• No modificar archivos en los que está trabajando otro compañero.
• Hacer git pull antes de empezar y git push cuando termines.
• Comentar el código cuando algo no sea obvio.
```