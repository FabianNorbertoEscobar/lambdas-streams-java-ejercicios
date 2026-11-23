# Prácticas de lambdas y streams en Java

Repositorio de ejercicios para practicar programación funcional y las APIs de Java aplicadas a lambdas, colecciones y streams. Los ejercicios están organizados en carpetas independientes y se acompañan de material de estudio en PDF.

## Stack y tecnologías

- **Java 8 o posterior**: expresiones lambda, interfaces funcionales, `Optional`, streams y métodos por defecto.
- **JUnit 4**: pruebas de los ejercicios, ubicadas en las carpetas `test_src`.
- **IDE Java**: los ejercicios pueden trabajarse desde un IDE con soporte para Java. No hay un build común ni configuración de Maven o Gradle en el repositorio.

## Ejercicios

| Carpeta | Contenidos y funcionalidades |
| --- | --- |
| `1_01_problema` | Introducción a lambdas: ordenar nombres con un `Comparator` basado en la longitud. |
| `1_02_default_methods` | Métodos `default` en interfaces e implementaciones de agrupadores con listas y arrays. |
| `2_02_lambda_expressions` | Implementación de interfaces funcionales con lambdas: constante, suma e inicialización de arrays. |
| `3_01_jdk_functional_interfaces` | Interfaces funcionales del JDK, como `Predicate`, y validación genérica configurable mediante predicados. |
| `3_03_optional` | Uso de `Optional` para representar datos ausentes y obtener información opcional del propietario de una vivienda. |
| `4_02_streams_pipeline` | Pipelines de streams para filtrar, transformar y ordenar datos de personas. |
| `4_04_reducciones_mutables` | Operaciones con streams y acumulación mutable: filtrar nulos, convertir texto a mayúsculas y contar pares e impares. |
| `5_01_collections` | Operaciones sobre colecciones con `removeIf`, `replaceAll` y `forEach`. |

## Pruebas y material

Las pruebas de cada ejercicio están en su correspondiente carpeta `test_src` y usan JUnit 4. El repositorio incluye PDFs sobre lambdas, interfaces funcionales, `Optional`, streams, pipelines, collectors, colecciones, comparators y reducciones, entre otros temas.
