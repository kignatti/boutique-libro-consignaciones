# Módulo de Gestión de Consignaciones y Control de Inventario 🛠️
### La Boutique del Libro — Sucursal Trelew

---

## 🏫 Institucional
* **Institución:** Universidad Tecnológica Nacional (UTN)
* **Carrera:** Tecnicatura Universitaria en Programación a Distancia (TUP AD)
* **Asignatura:** Organización Empresarial
* **Entrega:** Entrega Nº 4 — Procesos, Trabajo Colaborativo y Control Integrador
* **Alumno:** Kevin Ignatti
* **Docente Titular:** Prof. Gabriela Martínez
* **Docentes Adjuntos/Tutores:** Prof. Carolina Bruno, Prof. Mario Raúl López, Prof. Andrea Ramos, Prof. Gilda Jaquelina Domínguez

---

## 🔗 Accesos Directos del Proyecto
* **Tablero Interactivo de Gestión (GitHub Projects):** https://github.com/kignatti/boutique-libro-consignaciones/projects
* **Repositorio Público de GitHub:** https://github.com/kignatti/tpi-oe-kevin-ignatti
---

## 📄 Descripción del Sistema
Este software ha sido diseñado y desarrollado para transformar y automatizar el flujo operativo y financiero de **La Boutique del Libro (Sucursal Trelew)**. El sistema reemplaza de forma definitiva el antiguo control analógico mediante planillas de papel por un procesamiento digitalizado en tiempo real. 

El foco principal de la aplicación consiste en trazar con precisión matemática el ciclo de vida de las obras literarias recibidas bajo la modalidad de **consignación** (títulos cedidos por editoriales independientes y autores locales), automatizando las alertas de stock crítico en mostrador y optimizando las liquidaciones comerciales al cierre de cada período con un 0% de margen de error de cálculo.

---

## 📂 Estructura del Repositorio
Para garantizar la máxima legibilidad y navegabilidad por parte de la cátedra, los artefactos del proyecto se encuentran ordenados bajo la siguiente estructura modular:

* `README.md` → Portada oficial, descripción técnica del sistema e integrantes.
* `docs/01-bpmn/` → Modelado de procesos organizacionales en notación estándar BPMN 2.0 y guía de lectura.
* `docs/02-backlog/` → Tabulación formal de las tres Historias de Usuario y criterios de aceptación.
* `docs/03-control/` → Indicadores de control de gestión y estándares de desempeño.
* `docs/04-ia/` → Declaración ampliada de uso crítico de Inteligencia Artificial Generativa.
* `src/` → Código fuente ejecutable de la aplicación en Python (`.py`).

---

## 🌿 Estrategia de Versionado (Gitflow Adaptado)
El proyecto implementa una política estricta de aislamiento de funciones para proteger la integridad de la rama de producción:
* `main`: Línea base estable y entregable. Solo recibe integraciones revisadas mediante Pull Requests aprobados.
* `feature/bpmn-consignacion`: Bifurcación secundaria utilizada para el modelado de datos y diccionarios iniciales.
* `feature/backlog-historias`: Desarrollo de los requerimientos y trazabilidad ágil.
* `feature/control-excepciones`: Codificación defensiva, control de datos alfanuméricos (`try/except`) y reglas de negocio en caja (`raise ValueError`).

---
Mecanismos de Control e Indicadores de Desempeño

Para garantizar el correcto funcionamiento del sistema de gestión de consignaciones de La Boutique del Libro, se establecen diferentes mecanismos de control que permiten evaluar el desempeño de sus principales operaciones.

Los indicadores propuestos son los siguientes:

1. Registro de consignaciones

Indicador: porcentaje de libros recibidos que fueron registrados correctamente.

Estándar: el 100 % de los libros recibidos debe quedar registrado con sus datos correspondientes.

2. Actualización del inventario

Indicador: correspondencia entre las ventas realizadas y las modificaciones del stock.

Estándar: cada venta debe reflejarse correctamente en el inventario.

3. Registro de ventas

Indicador: porcentaje de operaciones de venta registradas.

Estándar: el 100 % de las ventas realizadas debe quedar registrado en el sistema.

4. Exactitud de liquidaciones

Indicador: coincidencia entre los importes calculados y las cantidades vendidas a cada proveedor.

Estándar: las liquidaciones deben reflejar correctamente los acuerdos establecidos con cada proveedor.

5. Trazabilidad de operaciones

Indicador: posibilidad de consultar e identificar las operaciones realizadas.

Estándar: cada operación debe contar con información suficiente para permitir su seguimiento y verificación.

Estos indicadores permiten establecer parámetros de evaluación y detectar posibles errores o desviaciones en los procesos, facilitando la aplicación de medidas correctivas y la mejora continua del sistema.
Declaración de Uso de Inteligencia Artificial (IA)

Durante el desarrollo del proyecto se utilizaron herramientas de Inteligencia Artificial Generativa, principalmente ChatGPT, como recurso de apoyo para organizar la documentación, estructurar los procesos del sistema y mejorar la presentación de los contenidos técnicos.

Los prompts utilizados estuvieron orientados principalmente a:

Organización y documentación: solicitar asistencia para estructurar las distintas secciones del proyecto y mejorar la claridad de las descripciones.

Modelado de procesos: consultar sobre la representación de los procesos organizacionales mediante la notación BPMN.

Gestión del proyecto: recibir orientación para organizar las historias de usuario y las actividades mediante GitHub Projects.

Revisión conceptual: solicitar explicaciones y sugerencias para verificar la coherencia entre los procesos de negocio y las funcionalidades del sistema.

Correcciones y validación humana

Los resultados proporcionados por las herramientas de IA fueron utilizados como propuestas iniciales y no se incorporaron de manera automática.

Se realizó una revisión humana de los contenidos para verificar que fueran coherentes con las características reales de La Boutique del Libro y con los objetivos del proyecto.

Entre las tareas de revisión se contemplaron la adaptación de las respuestas al contexto de la organización, la corrección de posibles imprecisiones conceptuales y la validación de los procesos y funcionalidades propuestos.

La responsabilidad final sobre las decisiones de diseño, la documentación y la coherencia del sistema corresponde a los integrantes del proyecto.

En conclusión, la Inteligencia Artificial fue utilizada como una herramienta complementaria de asistencia, manteniendo el criterio propio y la responsabilidad humana sobre el trabajo realizado
