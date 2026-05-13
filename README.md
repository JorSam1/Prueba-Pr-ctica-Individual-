# Prueba-Pr-ctica-Individual-
# Sistema Interactivo de Gestión Académica (C++)

Este proyecto es una aplicación de consola desarrollada en **C++** como parte de la evaluación parcial. Integra operaciones matemáticas, procesamiento de arreglos para gestión de notas y persistencia de datos en archivos de texto.

## 📋 Características

El aplicativo se divide en cuatro módulos funcionales:
1. **Operaciones Básicas:** Realiza suma, resta, multiplicación y división (incluye validación para evitar la división por cero).
2. **Registro de Notas:** Permite el ingreso de 5 calificaciones, almacenándolas en un arreglo para su posterior análisis.
3. **Procesamiento de Datos:** Calcula automáticamente el promedio, identifica la nota mayor y menor, y contabiliza la cantidad de alumnos aprobados y reprobados.
4. **Persistencia:** Guarda los resultados finales en un archivo llamado `resultados.txt`, incluyendo la fecha del sistema y el nombre del estudiante.

## 📂 Estructura del Repositorio

De acuerdo con los requerimientos, el proyecto está organizado de la siguiente manera:

*   `/src`: Contiene el código fuente del programa.
*   `/resultados`: Carpeta destinada a almacenar el archivo `resultados.txt` generado.
*   `/capturas`: Evidencias visuales de la ejecución.
*   `README.md`: Documentación general del proyecto.

## 🚀 Instalación y Ejecución

Para correr este proyecto localmente usando **Code::Blocks**:

1. Descarga o clona este repositorio.
2. Abre Code::Blocks y ve a `File > Open...` para seleccionar el archivo `src/main.cpp`.
3. Presiona `F9` (Build and Run) para compilar y ejecutar.

## 📊 Análisis del Proyecto

### Objetivos Específicos
* **Implementar un menú interactivo** utilizando estructuras de control cíclicas (`do-while`) y selectivas (`switch-case`) para gestionar de forma eficiente las operaciones aritméticas y el registro de datos académicos.
* **Aplicar arreglos unidimensionales y lógica de programación** para el procesamiento de calificaciones, permitiendo el cálculo de promedios e identificación de valores máximos/mínimos.
* **Garantizar la persistencia de la información** mediante el uso de la librería `<fstream>` para el almacenamiento de resultados en archivos planos.

### Conclusiones
* Se logró integrar el uso de condicionales y ciclos para crear un flujo de programa robusto, cumpliendo con la validación de operaciones críticas.
* El uso de arreglos y estructuras (`struct`) permitió organizar la información de manera lógica, facilitando la obtención de estadísticas precisas.
* La implementación de archivos demuestra la capacidad de crear aplicaciones que trascienden la ejecución temporal de la memoria RAM.

### Recomendaciones
* Se sugiere implementar filtros de seguridad adicionales para las entradas de usuario, evitando caracteres no numéricos en campos de notas.
* Modularizar el código en archivos de cabecera (`.h`) para futuros proyectos de mayor escala.

## 🎓 Información del Autor
* **Institución:** Universidad Técnica de Ambato (UTA)/Estuiante:Samuel Bravo
* **Lenguaje utilizado:** C++
* **Fecha:** Mayo 2026
