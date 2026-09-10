# twitter-bot

Experimento de automatización de Twitter con Node.js y `twit`. Las credenciales se leen desde variables de entorno.

## Estructura

- [index.js](index.js)

## Preparación y uso

Configura las cuatro credenciales de Twitter que se leen en `index.js`. La biblioteca `twit` y las rutas usadas son antiguas; verifica el acceso de tu cuenta y la compatibilidad actual de la API antes de ejecutar acciones.

### Raíz del repositorio

Requiere Node.js. Este paquete no fija una versión del runtime; valida compatibilidad con las dependencias antes de actualizarlo.

```sh
npm ci
```

No hay un script de arranque declarado en este paquete. Revisa el punto de entrada indicado arriba antes de ejecutar el código.

Comandos declarados en [package.json](package.json):

| Comando | Acción |
| --- | --- |
| `npm run test` | `echo "Error: no test specified" && exit 1` |

El script `test` es un marcador inicial, no una suite de pruebas.

## Configuración detectada en el código

Estas son referencias explícitas a variables de entorno, no una garantía de que toda la configuración esté externalizada. Los nombres y archivos permiten localizar dónde se usan; los valores deben corresponder a tu entorno.

| Variable | Referencia |
| --- | --- |
| `ACCESS_TOKEN` | [index.js](index.js) |
| `ACCESS_TOKEN_SECRET` | [index.js](index.js) |
| `API_KEY` | [index.js](index.js) |
| `API_KEY_SECRET` | [index.js](index.js) |

No guardes credenciales reales en la documentación. Si hay `.env.example`, úsalo como referencia y revisa cómo carga la configuración el punto de entrada.

## Validación y estado

Esta guía se contrastó con el árbol de archivos y los manifiestos del repositorio. No se ha validado una ejecución completa contra servicios externos, bases de datos o hardware. Las versiones y los scripts mostrados describen el código actual; no implican que sus dependencias antiguas sigan siendo compatibles.

## Documentación previa

Se conserva como referencia histórica, incluidas las imágenes y atribuciones originales. Los enlaces a demos y servicios no se han comprobado.

# Bot para twitter

En realidad me gustaría añadirle más funcionalidades pero por ahora estoy explorando con la API para ver que más cosas puedo implementarle

![Ejemplo usando la API de twitter retweet a una mención con Nodejs](https://pbs.twimg.com/media/Ehc4ZYEWsAEs7wE?format=png&name=small)
