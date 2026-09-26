# Cómo actualizar el catálogo Z&O Turbo Dinamic

Guía sencilla para mantener tu catálogo al día. No necesitas saber programar.

> Creado por IMP Ingenieros con IA.

---

## ¿Qué archivos tiene el proyecto?

| Archivo / carpeta | Qué es |
|---|---|
| `index.html` | El catálogo completo. Es la página que ven tus clientes. |
| `img/` | Las fotos de los productos (una por producto). Sirven para que se vean en el pedido de WhatsApp. |
| `README.md` | Instructivo para publicarlo en internet. |
| `COMO-ACTUALIZAR-EL-CATALOGO.md` | Este documento. |
| `vercel.json` / `.gitignore` | Archivos de configuración (no se tocan). |

---

## Regla de oro

Cada vez que subas una versión nueva a GitHub, **Vercel actualiza la web sola en
unos segundos**, sin cambiar la dirección (`https://zo-catalogo.vercel.app`) ni el
código QR. Así que el QR que imprimas hoy te sirve para siempre.

---

## Caso 1 — Recibiste un `index.html` nuevo (lo más común)

Cuando me pidas cambios (agregar productos, cambiar textos, etc.) te entregaré un
`index.html` nuevo. Para publicarlo:

1. Entra a tu repositorio en GitHub (`github.com/tu-usuario/zo-catalogo`).
2. Haz clic en el archivo `index.html`.
3. Arriba a la derecha, haz clic en el icono del lápiz (**Edit** / Editar)
   o usa **Add file → Upload files** para reemplazarlo.
4. Si usaste "Upload files", arrastra el nuevo `index.html` (mismo nombre, así
   reemplaza al anterior).
5. Baja hasta **Commit changes** y haz clic.
6. Espera ~30 segundos y recarga `https://zo-catalogo.vercel.app`. ¡Listo!

---

## Caso 2 — Agregar o cambiar la FOTO de un producto

Las fotos viven en la carpeta `img/`. El nombre de cada foto corresponde al
producto (por ejemplo `soplador.jpg`, `motovibrador-monofasico.jpg`).

Para cambiar una foto:

1. Prepara la nueva imagen con el **mismo nombre** que la que quieres reemplazar.
2. En GitHub entra a la carpeta `img/`.
3. **Add file → Upload files** y arrastra la imagen nueva.
4. **Commit changes**.

> Consejo: usa fotos cuadradas o rectangulares nítidas, de buen tamaño
> (por ejemplo 800×800 píxeles). Así se ven bien tanto en el catálogo como en
> la vista previa de WhatsApp.

---

## Caso 3 — Las fotos en el pedido de WhatsApp

El catálogo ya está preparado: cuando un cliente arma su pedido, el mensaje que
llega a tu WhatsApp (**924 667 782**) incluye, además de todos los datos, un
bloque **🖼️ IMÁGENES DE REFERENCIA** con el enlace de la foto de cada producto
pedido. Al abrir el enlace, WhatsApp muestra la imagen.

Esto **solo funciona cuando el catálogo está publicado en Vercel** (porque las
fotos necesitan una dirección pública en internet). Si abres el `index.html` con
doble clic en tu PC sin publicarlo, el pedido igual llega correcto al número,
pero los enlaces de imagen aún no estarán activos.

---

## Importante: lo que NO debe cambiar

- El **número de WhatsApp 924 667 782** está configurado en todo el catálogo.
  Si alguna vez cambia, avísame y te preparo la versión con el número nuevo.
- La **dirección web** (`zo-catalogo.vercel.app`) no cambia mientras uses el
  mismo proyecto en Vercel. Por eso el QR sigue sirviendo siempre.

---

## ¿Dudas?

Si algo no sale, mándame el mensaje de error o una captura y te guío paso a paso.
