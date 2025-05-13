# 🛒 Sistema de Gestión de Inventario para Tiendas

Un sistema básico de consola desarrollado en Python para gestionar el inventario de una tienda. Permite agregar, listar, buscar, eliminar y modificar productos de forma sencilla e interactiva.

---

## 📌 Autor

**Manuel Sánchez**  
Desarrollador del sistema y responsable de la arquitectura funcional del inventario.

---

## 📦 Funcionalidades

- [x] Agregar nuevos productos con precio y stock.
- [x] Listar todos los productos disponibles.
- [x] Buscar productos por nombre.
- [x] Eliminar productos existentes con confirmación.
- [x] Modificar la cantidad (stock) de un producto.
- [x] Manejo de interrupciones con `Ctrl+C`.

---

## 🧠 Validaciones

El sistema incluye validación robusta para asegurar que los valores ingresados como precio o cantidad sean numéricos y correctamente formateados. Esto evita errores comunes de entrada del usuario.

---

## 🧪 Versión

**`v2.0.1`**

---

## 🧾 Historial de versiones

- **15/04/2025**: Inicio del desarrollo `v1.0.0`
- **22/04/2025**: Se agrega opción 5: Modificar Cantidad `v1.1.0`
- **22/04/2025**: Se optimiza la búsqueda en opciones 3 y 4 usando bucle `while` `v1.1.1`
- **29/04/2025**: Migración a paradigma funcional `v2.0.0`
- **05/05/2025**: Reemplazo de funciones de búsqueda y visualización + control de `KeyboardInterrupt` `v2.0.1`

---

## ⚙️ Requisitos

- Python 3.x

---

## ▶️ Cómo ejecutar

```bash
python inventario.py
```
