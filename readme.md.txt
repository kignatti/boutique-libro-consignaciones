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
* **Tablero Interactivo de Gestión (GitHub Projects):** [Enlace a tu Tablero Kanban](https://github.com)
* **Repositorio Público de GitHub:** [Enlace a este Repositorio](https://github.com)

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

## 🤖 Declaración de Uso Crítico y Transparencia de IA
Para la elaboración de la base documental y la optimización sintáctica de este proyecto, se utilizó la asistencia técnica de Inteligencia Artificial Generativa bajo criterios profesionales de transparencia. 

**Supervisión Humana y Edición Crítica:** El equipo técnico llevó a cabo una auditoría rigurosa sobre los resultados del modelo de lenguaje. Se rechazaron de forma manual las lógicas de reintento infinito sugeridas por la IA para el módulo de caja, debido a que violaban las restricciones operativas de la cátedra. Asimismo, se corrigió de forma manual la dirección de las excepciones del software, forzando a que los errores de negocio de las funciones operativas se propaguen limpiamente hacia la función contenedora `main()`, asegurando así el cumplimiento conceptual estricto de la rúbrica y preservando la autoría intelectual del estudiante.
