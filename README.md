# Nexos Digitales S.R.L. — Módulo de Facturación y Cuentas

**Trabajo Práctico Integrador y Progresivo de Organización Empresarial — Entrega N.º 4**  
Tecnicatura Universitaria en Programación a Distancia | UTN

**Alumno:** Pablo Matías García Moralez  
**Caso de estudio:** Nexos Digitales S.R.L.

## Descripción

El proyecto propone un módulo web para relacionar contratos, proyectos y horas trabajadas con la facturación electrónica y el seguimiento de cuentas por cobrar y por pagar. Se busca evitar registros separados y facilitar el control de vencimientos, cobros, pagos y saldos.

El repositorio contiene la **documentación y el modelado de un MVP propuesto**. No se presenta como un sistema desarrollado, desplegado ni conectado a servicios reales de ARCA o de bancos.

## Material del proyecto

- [Proceso BPMN: facturación y cobranzas](diagramas/facturacion_cobranzas.bpmn) y su [vista gráfica](diagramas/facturacion_cobranzas.svg).
- [Proceso BPMN: cuentas por pagar](diagramas/cuentas_por_pagar.bpmn) y su [vista gráfica](diagramas/cuentas_por_pagar.svg).
- [Historias de usuario y criterios de aceptación](docs/historias-de-usuario.md).
- [Indicadores y criterios de control](docs/indicadores-de-control.md).
- [Revisión del proceso y decisiones de modelado](docs/decisiones-de-modelado.md).
- [Guía de Git/GitHub y evidencias a completar](docs/guia-github.md).
- [Registro de revisión y PR](docs/registro-pull-request.md).

## Historias del backlog

| ID | Historia resumida | Estado inicial sugerido |
|---|---|---|
| HU-01 | Registrar y consultar contratos, proyectos y horas | Por Hacer |
| HU-02 | Preparar, revisar y emitir facturas de clientes | Por Hacer |
| HU-03 | Registrar cobros y pagos, actualizar saldos y vencimientos | Por Hacer |

Las historias se formalizan a partir del alcance de las Entregas 1, 2 y 3. **No representan funcionalidades ya implementadas.** El estado real debe actualizarse en el tablero según el trabajo efectivamente realizado.

## Alcance y criterios de control

El plan de la Entrega 2 considera un desarrollo en ocho semanas, del 05/10/2026 al 29/11/2026. Se adopta como objetivo que al menos el 95 % de las operaciones respondan en menos de 2 segundos con 20 usuarios concurrentes, que se apruebe al menos el 90 % de las pruebas críticas y que la integridad de las relaciones entre comprobantes, movimientos y cuentas sea del 100 % en el conjunto de pruebas de integración. Las métricas son **objetivos planificados**, no resultados medidos.

## Declaración de uso de IA

Se utilizó **ChatGPT** como herramienta de apoyo para ordenar la documentación de esta entrega, redactar una primera propuesta de historias de usuario y criterios de control, y construir representaciones editables de los procesos. Se contrastaron los resultados con las Entregas 1, 2 y 3 y con el material de la Unidad 5. En particular, se ajustó la separación entre tareas humanas y automáticas, se agregaron compuertas de decisión y se evitó presentar integraciones externas o métricas como resultados ya existentes.

## Bibliografía y antecedentes

- García Moralez, P. M. (2026). Entrega N.º 1: La organización y su enfoque sistémico. UTN.
- García Moralez, P. M. (2026). Entrega N.º 2: Diagnóstico y planeación del proyecto tecnológico. UTN.
- García Moralez, P. M. (2026). Entrega N.º 3: Estructura formal y diseño de datos. UTN.
- UTN. Organización Empresarial. Unidad 5: Procesos; Modelado de procesos con BPMN; Máquinas de Estado Finito (material de cátedra).
