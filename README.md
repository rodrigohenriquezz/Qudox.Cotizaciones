# Cotizaciones Internacionales · Guía de Handoff

Sitio de una sola página que QUDOX usa en reuniones con productoras de
Honduras, Nicaragua y Costa Rica.

**En vivo:** https://qudox-cotizaciones.pages.dev/

---

## Qué hay en este repo

| Archivo | Qué es |
|---|---|
| `index.html` | El sitio completo. Un solo archivo con todo adentro: código, estilos, tipografías y logos. No depende de nada externo salvo los videos y fotos, que viven en Google Drive. |

No hay build. El servidor sirve `index.html` tal cual.

---

## Cómo actualizar el sitio

Cualquier cambio que se guarde en este repo se publica solo en menos de un
minuto. No hay que arrastrar archivos a ningún lado.

### Cambios de texto, precios o cantidades

Se pueden hacer desde el navegador, sin instalar nada:

1. Abrir `index.html` acá en GitHub.
2. Tocar el lápiz (**Edit this file**).
3. Buscar el texto con `Ctrl+F` (o `Cmd+F`). Por ejemplo `$125` o
   `6 a 8 historias`.
4. Cambiarlo y tocar **Commit changes**.
5. Esperar ~30 segundos y recargar el sitio.

El archivo está compilado, así que el código se ve apretado y sin saltos de
línea. Los textos y los números sí se leen y se pueden cambiar. Lo que **no**
se puede hacer así es mover secciones, agregar bloques nuevos o cambiar el
diseño: eso requiere regenerar el archivo.

### Volver atrás

Cada cambio queda guardado. En la pestaña **Commits** se puede ver el
historial y restaurar cualquier versión anterior.

---

## Antes de una reunión

- Abrir el sitio en una ventana de incógnito. Es la única forma de ver lo que
  va a ver la productora, y no lo que ve uno con la sesión de QUDOX abierta.
- Confirmar que los videos y las fotos de Drive estén compartidos como
  **"cualquiera con el enlace · lector"**.
- Reproducir una vez cada video pesado, para que Drive genere su versión de
  streaming y no se quede procesando en vivo.

---

## Importante

Este repo debe mantenerse **privado**. El sitio contiene tarifas de talento,
nombres de cuentas y entregables por país. En un repo público eso queda
indexado y visible para cualquiera.
