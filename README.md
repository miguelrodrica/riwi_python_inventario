# Ejercicio académico: Inventario básico en Python

Este repositorio contiene un ejercicio práctico de la **Semana 1 del módulo de Python** (contexto académico en Moodle), enfocado en el uso de:

- Entrada de datos por consola (`input`)
- Validación de tipos con `try` / `except`
- Operaciones básicas
- Salida formateada con `f-strings`

## ¿Qué es este ejercicio?

Es un programa de consola llamado `inventario.py` que simula el ingreso de un producto a un sistema de inventario simple.

El script solicita al usuario:

1. Nombre del producto
2. Precio del producto
3. Cantidad del producto

Luego calcula el **costo total** (`precio * cantidad`) y muestra un resumen con los datos ingresados.

## ¿En qué consiste?

El objetivo académico principal es practicar fundamentos de Python:

- **Variables** para almacenar información del producto.
- **Conversión de tipos** (`float` para precio, `int` para cantidad).
- **Manejo de errores** con `try`/`except ValueError` para evitar que el programa falle si el usuario escribe un dato inválido.
- **Bucles `while True`** para repetir la solicitud hasta que la entrada sea correcta.

## Estructura del repositorio

- `inventario.py`: código principal del ejercicio.
- `inventario.jpg`: imagen relacionada con el ejercicio.

## Requisitos

- Python 3.x instalado.

Puedes verificar tu versión con:

```bash
python --version
```

> En algunos sistemas puede ser necesario usar `python3` en lugar de `python`.

## ¿Cómo usarlo?

1. Clona el repositorio:

```bash
git clone https://github.com/miguelrodrica/riwi_python_inventario.git
```

2. Entra a la carpeta del proyecto:

```bash
cd riwi_python_inventario
```

3. Ejecuta el programa:

```bash
python inventario.py
```

(o `python3 inventario.py`)

4. Ingresa los datos solicitados por consola.

## Ejemplo de ejecución

```text
Bienvenido al software de Inventario
Escriba los siguientes datos del producto a ingresar
Nombre: Cuaderno
Precio: 2.5
Cantidad: 4
Usted ingresó: Producto: Cuaderno | Precio: 2.5 | Cantidad: 4 | Total: 10.0
```

## Nota académica

Este ejercicio está diseñado con fines de aprendizaje inicial. Es una base útil para evolucionar hacia versiones más completas (múltiples productos, almacenamiento en archivos o base de datos, menú interactivo, etc.).
