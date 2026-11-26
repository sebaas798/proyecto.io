# eMercado — workspace inicial

Base del **proyecto final de JAP (Jóvenes a Programar) 2023**: un e-commerce llamado eMercado que se construye a lo largo del curso. Este repo tiene el punto de partida que da el curso más los primeros avances.

## Qué hay

Dentro de `workspace-inicial/`:

- **Páginas:** inicio, login, categorías, listado de productos, detalle de producto, carrito, vender y mi perfil.
- **`js/init.js`:** las URLs de la API pública de eMercado (categorías, productos, comentarios, carrito, compra) y la función `getJSONData()`, que hace el `fetch`, muestra un spinner mientras carga y devuelve `{ status, data }`.
- **`js/categories.js`:** lista las categorías traídas de la API, con orden alfabético, por cantidad de productos y filtro por rango.
- **`js/sell.js`:** formulario para publicar un producto con carga de imágenes (Dropzone) y cálculo del costo según el tipo de publicación.
- El resto de los scripts (`login.js`, `products.js`, `product-info.js`, `cart.js`, `my-profile.js`) están vacíos, listos para las entregas del curso.

## Cómo verlo

Abrí `workspace-inicial/index.html` con Live Server o cualquier servidor estático (hace falta para que funcionen los `fetch`).

## Tecnología

- HTML, CSS y JavaScript vanilla
- Bootstrap 5, Font Awesome y Dropzone.js
- API de datos: https://japceibal.github.io/emercado-api/

> El proyecto completo, hecho en grupo, está en [janbrugger/Proyecto-Final](https://github.com/janbrugger/Proyecto-Final).
