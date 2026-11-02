# Módulo de Gestión de Consignaciones y Control de Inventario 🛠️
### La Boutique del Libro — Sucursal Trelew

---

## 🏫 Institucional
* **Institución:** Universidad Tecnológica Nacional (UTN)
* **Carrera:** Tecnicatura Universitaria en Programación a Distancia (TUP AD)
* **Asignatura:** Organización Empresarial
* **Trabajo Práctico Integrador (TPI) — Progresivo**
* **Alumno:** Kevin Ignatti
* **Docente Titular:** Prof. Gabriela Martínez
* **Docentes Adjuntos/Tutores:** Prof. Carolina Bruno, Prof. Mario Raúl López, Prof. Andrea Ramos, Prof. Gilda Jaquelina Domínguez

---

## 🔗 Accesos Directos del Proyecto
* **Tablero Interactivo de Gestión (GitHub Projects):** [Ver Tablero](https://github.com/kignatti/boutique-libro-consignaciones/projects)
* **Repositorio Público de GitHub:** [Ver Repositorio](https://github.com/kignatti/tpi-oe-kevin-ignatti)

---

## 📖 Descripción General del Proyecto
Este repositorio contiene el desarrollo del **Trabajo Práctico Integrador** de la materia Organización Empresarial. El proyecto se estructuró de manera progresiva a lo largo de tres entregas fundamentales:
1. **Modelado como Sistema Abierto (TGS):** Análisis de *La Boutique del Libro* (sucursal Trelew) como un sistema abierto, identificando entradas, procesos de transformación (curaduría, venta especializada y eventos culturales), salidas y su interacción con el entorno.
2. **Diagnóstico y Planeación Tecnológica:** Elaboración de matriz FODA, establecimiento de metas cuantitativas e implementación de un cronograma de trabajo (Diagrama de Gantt) a 6 meses.
3. **Estructura Formal y Diseño de Datos:** Modelado de la estructura organizacional de la sucursal (organigrama vertical) y diseño inicial del Diccionario de Datos relacional para el control de consignaciones.

---

## 🗂️ Arquitectura y Estructura de Datos (Entrega 3)
El módulo propuesto automatiza el ciclo de vida de los libros en consignación (editoriales independientes y autores locales). Las **5 entidades críticas** modeladas en el sistema son:

* **Proveedor:** Almacena datos de las editoriales y autores (ID, nombre, contacto, porcentaje de comisión acordado).
* **Consignación:** Registra el ingreso inicial de ejemplares y controla el stock disponible en tiempo real.
* **Venta de Consignación:** Registra cada transacción vinculada para descontar el inventario de forma automática.
* **Liquidación:** Automatiza el cálculo periódico de los importes a pagar a cada proveedor según las ventas y comisiones retenidas.
* **Reposición:** Gestiona las solicitudes automáticas de stock ante unidades agotadas.

---

## 🌿 Estrategia de Versionado (Gitflow Adaptado)
El proyecto implementa una política estricta de aislamiento de funciones para proteger la integridad de la rama de producción:
* `main`: Línea base estable y entregable. Solo recibe integraciones revisadas mediante Pull Requests aprobados.
* `feature/bpmn-consignacion`: Modelado de procesos y diccionarios iniciales.
* `feature/backlog-historias`: Desarrollo de requerimientos y trazabilidad ágil.
* `feature/control-excepciones`: Codificación defensiva, validación de datos alfanuméricos y control de excepciones.

---

## 📊 Mecanismos de Control e Indicadores de Desempeño
Para evaluar el éxito operacional del sistema, se definieron los siguientes indicadores:
1. **Registro de Consignaciones:** 100% de los libros recibidos registrados correctamente con sus datos.
2. **Actualización de Inventario:** Coincidencia estricta entre las ventas en caja y la baja automática de stock.
3. **Exactitud de Liquidaciones:** Margen de error del 0% en el cálculo de importes y comisiones a proveedores.
4. **Trazabilidad:** Disponibilidad de información histórica para auditar cualquier operación del sistema.

---

## 🤖 Declaración de Uso de Inteligencia Artificial (IA)
Durante el desarrollo del proyecto se utilizaron herramientas de Inteligencia Artificial Generativa (principalmente ChatGPT) como recurso de apoyo para la estructuración de la documentación, la redacción formal, la organización de historias de usuario y la maquetación visual de diagramas.

* **Revisión y Validación Humana:** Los resultados de la IA se emplearon estrictamente como borradores o propuestas iniciales. Todo el contenido conceptual, la adecuación al caso de estudio real de *La Boutique del Libro*, la validación de procesos y las decisiones de diseño fueron revisadas, corregidas y asumidas de manera crítica por el alumno. La responsabilidad intelectual sobre el proyecto recae íntegramente en su autor
