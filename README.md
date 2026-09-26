# Catálogo Virtual — Z&O Turbo Dinamic E.I.R.L.

Catálogo de productos industriales (motores, sopladores, motovibradores, bridas, etc.)
en una sola página web autónoma. Funciona sin internet una vez cargada y permite
armar un pedido que se envía por WhatsApp al **924667782**.

> Creado por IMP Ingenieros con IA.

---

## Contenido de esta carpeta

| Archivo / carpeta | Para qué sirve |
|---|---|
| `index.html` | El catálogo completo. Es la página principal. |
| `img/` | Fotos de los productos (para la vista previa en el pedido de WhatsApp). |
| `vercel.json` | Configuración para publicarlo en Vercel. |
| `.gitignore` | Lista de archivos que Git debe ignorar. |
| `README.md` | Este instructivo. |
| `COMO-ACTUALIZAR-EL-CATALOGO.md` | Guía para mantener el catálogo al día. |

---

## Cómo publicarlo en internet (paso a paso)

### 1) Subirlo a GitHub

1. Entra a https://github.com y crea una cuenta (si aún no tienes).
2. Haz clic en **New repository** (Nuevo repositorio).
   - Nombre sugerido: `zo-catalogo`
   - Marca **Public**.
   - NO marques "Add a README" (ya tienes uno).
3. En la página del repositorio vacío, haz clic en **uploading an existing file**
   (subir un archivo existente).
4. Arrastra TODO el contenido de esta carpeta, **incluida la carpeta `img/`**
   (`index.html`, la carpeta `img/`, `README.md`, `vercel.json`, `.gitignore`,
   `COMO-ACTUALIZAR-EL-CATALOGO.md`).
5. Haz clic en **Commit changes** (Guardar cambios).

### 2) Conectarlo a Vercel para obtener la dirección web

1. Entra a https://vercel.com e inicia sesión **con tu cuenta de GitHub**.
2. Haz clic en **Add New… → Project** (Agregar nuevo → Proyecto).
3. Selecciona el repositorio `zo-catalogo` y pulsa **Import**.
4. No cambies nada en la configuración; pulsa **Deploy** (Publicar).
5. En unos segundos Vercel te dará una dirección como:
   `https://zo-catalogo.vercel.app`

¡Esa es la dirección pública de tu catálogo! Ábrela en el celular para probarla.

### 3) Generar el código QR

Una vez tengas la dirección de Vercel, avísame y te genero el código QR
que apunta a ella. Al escanearlo, cualquier cliente abre el catálogo al instante.

---

## Mostrar las fotos en el pedido de WhatsApp (opcional, más adelante)

El pedido llega SIEMPRE al número **924 667 782** con todos los datos en texto
(cliente, empresa, RUC/DNI, productos y cantidades). **Además ya viene incluido**
un bloque "IMÁGENES DE REFERENCIA" con el enlace de la foto de cada producto
pedido: al publicarlo en Vercel (paso 2), WhatsApp mostrará la vista previa de
esas fotos automáticamente. Las imágenes se toman de la carpeta `img/`.

---

## Actualizar el catálogo en el futuro

Cada vez que tengas una versión nueva del `index.html`, solo súbela otra vez a
GitHub (reemplazando la anterior). Vercel actualizará la web automáticamente en
segundos, sin cambiar la dirección ni el código QR.
