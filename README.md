# rascal-latino 🚀

**rascal-latino** es una extensión para el lenguaje de metaprogramación **Rascal**, diseñada para proporcionar análisis estático, transformación de programas, derivación de Árboles de Sintaxis Abstracta (AST) y reingeniería de código sobre el lenguaje de programación con sintaxis en español **Latino**.

Aprovechando la infraestructura de análisis de Rascal y la ejecución de alto rendimiento sobre **GraalVM**, este proyecto permite construir herramientas del lenguaje (como linters, refactorizadores automáticos y traductores) para programas escritos en Latino.

---

## 🌟 Características Principales

* **Gramática Concreta de Latino:** Especificación completa de la sintaxis y gramática del núcleo del lenguaje Latino (`lang::latino::syntax::Latino`) lista para parsing directo.
* **Mapeo AST y Modelado M3:** Conversión automática de código fuente Latino a tipos de datos algebraicos y estructuras de grafos relacionales para análisis estático profundo.
* **Motor de Transformación de Código:** Reglas de reescritura de términos (*term rewriting*) para automatizar la refactorización o la traducción de Latino hacia otros lenguajes (como JavaScript, C o Python).
* **Integración con la Cadena de Herramientas Rascal:** Análisis interactivo mediante el REPL de Rascal e inspección visual de dependencias y grafos de flujo de control.

---

## 🏗️ Arquitectura de la Plataforma

* **Latino Grammar Definition (`.rsc`):** Definición formal de la sintaxis concreta de Latino usando las capacidades de definición de gramáticas contextuales de Rascal.
* **AST Extractor & Importer:** Módulo encargado de convertir los árboles de derivación concretos en Árboles de Sintaxis Abstracta estructurados.
* **Transformation & Analysis Core:** Suite de funciones en Rascal para el cálculo de métricas de código, detección de patrones y reescritura de código fuente.

---

## 🚦 Inicio Rápido

### Prerrequisitos

* **GraalVM JDK** (versión 21 o superior) con componentes de Rascal activos.
* **Rascal CLI / REPL** o el plugin de Rascal para Eclipse / VS Code.

### Instalación

```bash
# Clonar el repositorio
git clone [https://github.com/tu-usuario/rascal-latino.git](https://github.com/tu-usuario/rascal-latino.git)
cd rascal-latino

# Empaquetar y construir la biblioteca de Rascal
rascal-shell pack
