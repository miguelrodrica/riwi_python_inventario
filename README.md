# Inventario básico en Python – Actividad Académica (Riwi)

Este repositorio contiene una actividad desarrollada como parte del curso **Desarrollo de Software Web & Analítica de Datos** en Riwi, específicamente para el **Módulo 1 - Fundamentos de programación con Python**.

## Descripción general

El objetivo de este ejercicio es guiar, paso a paso, la evolución de un sistema de inventario implementado en Python. Se estructura en tres sprints que abordan crecientes niveles de dificultad: desde los conceptos fundamentales hasta la manipulación de archivos, el manejo de colecciones y la modularización del código.

---

## Estructura del repositorio y entregables

```
sprint_1/
│   inventario_sprint1.py
│   userstory_sprint1.md
│   diagrama_flujo.jpg
sprint_2/
│   inventario_sprint2.py
│   userstory_sprint2.md
sprint_3/
│   app.py
│   servicios.py
│   archivos.py
│   inventario.csv
│   userstory_sprint3.md
README.md
```

### Sprints y funcionalidades

#### 🟢 Sprint 1 – Fundamentos y Operaciones Básicas
- Manejo de variables, entrada de datos por consola, validación de tipos (try/except), operaciones aritméticas simples y salidas formateadas.
- Primer script: solicita al usuario nombre, precio y cantidad de un producto, calcula el costo total y muestra un resumen.

#### 🟡 Sprint 2 – Múltiples Registros y Menú Interactivo
- Gestión de varios productos mediante una estructura de lista de diccionarios.
- Presenta un menú en consola (agregar, mostrar inventario, estadísticas, salir), uso de condicionales y bucles.
- Introducción de funciones y código modularizado para hacer la lógica más mantenible.

#### 🟠 Sprint 3 – Colecciones, Modularidad y Persistencia
- Persistencia con archivos CSV (guardar y cargar inventario), manejo de fusión/reemplazo, validación rigurosa.
- Módulos separados: servicios para lógica de inventario y archivos para manipulación de CSV.
- CRUD completo, estadísticas avanzadas (producto más caro, mayor stock, etc.), y manejo detallado de errores/validaciones.

---

## ¿Cómo ejecutar el proyecto?

Requisitos:
- Python 3.x instalado en tu sistema.

Pasos básicos:

1. Clona este repositorio:
    ```bash
    git clone https://github.com/miguelrodrica/riwi_python_inventario.git
    cd riwi_python_inventario
    ```
2. Navega a la carpeta del sprint que deseas probar.
3. Ejecuta el script principal de ese sprint. Ejemplo para Sprint 3:
    ```bash
    cd sprint_3
    python app.py
    # (o python3 app.py dependiendo tu sistema)
    ```

---

## Notas académicas y recomendaciones

- Este proyecto tiene fines educativos, como ejercicio práctico y progresivo para afianzar los fundamentos de programación con Python.
- Cada sprint incluye un archivo user story (recomendado leerlo antes de abrir los scripts).
- Hay diagramas de flujo en los sprints que lo requieren.
- Recomendamos ejecutar primero Sprint 1, luego Sprint 2 y finalmente Sprint 3 para apreciar la evolución escalonada del sistema.
- El código está comentado y modularizado para facilitar la comprensión.

---

### Autoría y licencia

Desarrollado para uso académico en el marco de Riwi. Libre de uso, copia y adaptación con fines educativos.
