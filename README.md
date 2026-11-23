# Calculadora Geométrica
Calculadora de áreas geométricas en Python

Aplicación de consola en Python para calcular el área de distintas figuras geométricas, desarrollada siguiendo el flujo de trabajo **GitHub Flow** con ramas y Pull Requests.


## Funcionalidades

El programa muestra un menú interactivo en consola que se repite hasta seleccionar la opción de salir (`0`):

1. **Rectángulo**.
2. **Cuadrado**.
3. **Círculo**.
0. **Salir**.

## Estructura del proyecto

```text
calculadoraGeometrica/
├── .gitignore
├── README.md
├── areas_geometricas.py
└── principal.py
```

- `README.md`: documentación del proyecto y guía de uso.
- `.gitignore`: excluye archivos locales o generados automáticamente (como caché de Python o entornos virtuales).
- `areas_geometricas.py`: módulo propio con las funciones de cálculo (`area_rectangulo`, `area_cuadrado` y `area_circulo`).
- `principal.py`: punto de entrada con el menú, lectura de datos y llamada al módulo de áreas.

## Requisitos e instalación

- **Python 3** instalado en el equipo (utiliza el módulo estándar `math`).

Clonar el repositorio desde GitHub:

```bash
git clone [https://github.com/aarriasol/calculadoraGeometrica.git](https://github.com/aarriasol/calculadoraGeometrica.git)
cd calculadoraGeometrica
```

## Uso

Ejecuta el programa principal desde la carpeta del proyecto:

```bash
python principal.py
```

