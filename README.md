# Catálogo Virtual — Z&O Turbo Dinamic E.I.R.L.

Catálogo de productos industriales (motores, sopladores, motovibradores, bridas, etc.)
en una sola página web autónoma. Funciona sin internet una vez cargada y permite
armar un pedido que se envía por WhatsApp al **924667782**.

> Creado por IMP Ingenieros con IA.

---

## Contenido de esta carpeta

| Archivo | Para qué sirve |
|---|---|
| `index.html` | El catálogo completo. Es TODO lo que se necesita. |
| `vercel.json` | Configuración para publicarlo en Vercel (opcional). |
| `.gitignore` | Lista de archivos que Git debe ignorar. |
| `README.md` | Este instructivo. |

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
4. Arrastra los 4 archivos de esta carpeta (`index.html`, `README.md`,
   `vercel.json`, `.gitignore`).
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

Actualmente el pedido llega SIEMPRE al número **924667782** con todos los datos
en texto (cliente, empresa, RUC/DNI, productos y cantidades).

Cuando el catálogo ya esté publicado (paso 2), se puede hacer que cada producto
también muestre su foto en el chat de WhatsApp. Para eso hay que agregar a cada
producto un enlace público de su imagen. Puedo ayudarte con eso cuando quieras.

---

## Actualizar el catálogo en el futuro

Cada vez que tengas una versión nueva del `index.html`, solo súbela otra vez a
GitHub (reemplazando la anterior). Vercel actualizará la web automáticamente en
segundos, sin cambiar la dirección ni el código QR.
