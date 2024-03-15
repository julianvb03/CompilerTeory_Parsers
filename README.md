# Nombre del Proyecto: Parser LL(1) y LR(0)

## Descripción
Este proyecto implementa parsers LL(1) y LR(0) para analizar gramáticas y cadenas proporcionadas por el usuario. Permite procesar cadenas, verificar si una gramática es LL(1), y realizar análisis sintáctico tanto ascendente como descendente. La implementación está diseñada para ser extendible y fácil de utilizar en aplicaciones educativas o de investigación en el campo de la teoría de lenguajes de programación.

## Características
- Análisis de cadenas mediante parsers LL(1) y LR(0).
- Verificación de gramáticas LL(1).
- Generación de conjuntos First y Follow para gramáticas.
- Análisis sintáctico ascendente y descendente.

## Instalación
El proyecto no requiere instalación de dependencias externas más allá de Python estándar. Para ejecutarlo, clona el repositorio en tu máquina local:

Sigue las instrucciones en consola para seleccionar entre análisis LL(1) y LR(0), ingresar cadenas para análisis, y más. Hay gramaticas de ejemplo en la carpeta tests, de la cual podras sacar el formato para usar las tuyas propias. 

### Ejemplo de uso:
1. Ejecuta el script: `python main.py`
2. Selecciona el tipo de gramática ingresando `1` para LL(1) o `2` para LR(0).
3. Elige la operación deseada (procesar cadena, mostrar First y Follow, verificar si la gramática es LL(1), etc.).
4. Si eliges procesar una cadena, ingrésala cuando se te solicite.

## Contribuir
Este proyecto es de código abierto, y las contribuciones son bienvenidas. Si deseas contribuir con mejoras, corrige un problema o agregas funcionalidades, por favor realiza un fork del repositorio y envía un pull request con tus cambios.
