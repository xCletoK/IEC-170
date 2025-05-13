# 🛒 Sistema de Gestión de Inventario para Tiendas

Un sistema básico de consola desarrollado en Python para gestionar el inventario de una tienda. Permite agregar, listar, buscar, eliminar y modificar productos de forma sencilla e interactiva.

Desde la versión `v2.1.1`, el código ha sido modularizado para mejorar su mantenimiento y escalabilidad.

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
- [x] Modularización del código (`v2.1.1`)
- [x] Separación de datos a un módulo externo (`v2.1.2`)

---

## 🧠 Validaciones

El sistema incluye validación robusta para asegurar que los valores ingresados como precio o cantidad sean numéricos y correctamente formateados. Esto evita errores comunes de entrada del usuario.

---

## 🧪 Versión

**`v2.1.2`**

---

## 🧾 Historial de versiones

> Basado en el esquema `MAJOR.MINOR.PATCH`
>
> - **MAJOR**: Cambios incompatibles o estructurales mayores.
> - **MINOR**: Nuevas funciones sin romper compatibilidad.
> - **PATCH**: Correcciones de errores o mejoras internas.

- **15/04/2025**: Inicio del desarrollo `v1.0.0`
- **22/04/2025**: Se agrega opción 5: Modificar Cantidad `v1.1.0`
- **22/04/2025**: Mejora de búsqueda en opciones 3 y 4 con `while` `v1.1.1`
- **29/04/2025**: Migración a paradigma funcional `v2.0.0`
- **05/05/2025**: Reemplazo de lógica de búsqueda y visualización por funciones; manejo de `KeyboardInterrupt` `v2.0.1`
- **13/05/2025**: Modularización del código base `v2.1.1`
- **13/05/2025**: Separación de listas de productos a un módulo externo `v2.1.2`

---

## ⚙️ Requisitos

- Python 3.x

---

## ▶️ Cómo ejecutar

```bash
python iec-170.py
```
