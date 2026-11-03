# Indicadores y estándares de desempeño

El tablero técnico compara metas con resultados verificables. Los valores siguientes provienen de los criterios del proyecto o se proponen para control documental; no son mediciones realizadas.

| Indicador | Cómo se mide | Objetivo | Responsable | Evidencia |
|---|---|---|---|---|
| Cumplimiento de plazo | Entrega del MVP respecto al 29/11/2026 | 8 semanas desde el 05/10/2026 | Dirección / desarrollo | Hitos y registro de entrega |
| Rendimiento de operaciones | (Operaciones < 2 s / operaciones medidas) × 100, con 20 usuarios concurrentes | ≥ 95 % | Desarrollo / QA | Reporte de prueba de carga |
| Pruebas críticas aprobadas | (Pruebas críticas aprobadas / críticas ejecutadas) × 100 | ≥ 90 % | QA | Casos y resultados de ejecución |
| Defectos críticos abiertos | Recuento al cierre de la validación previa al despliegue | 0 | QA / desarrollo | Registro de defectos |
| Integridad referencial del circuito | (Movimientos y comprobantes con vínculos correctos / total de casos de integración evaluados) × 100 | 100 % | Backend / QA | Pruebas de integración y consultas |
| Saldos consistentes | (Operaciones evaluadas sin saldo negativo ni exceso de imputación / total evaluado) × 100 | 100 % (propuesto) | Finanzas / QA | Validaciones y casos de prueba |
| Trazabilidad de historias | (HU con issue y estado en tablero / 3 HU) × 100 | 100 % (propuesto) | Coordinación | GitHub Projects |
| Revisión de cambios documentales | (PR fusionados con revisión externa registrada / PR fusionados) × 100 | 100 % (propuesto) | Equipo / revisor | Historial de PR |

## Reglas de decisión

- Si el rendimiento queda por debajo del objetivo, identificar consultas lentas y repetir la prueba en las mismas condiciones.
- Si alguna prueba crítica falla, registrar el defecto; no declarar listo un componente con defectos críticos abiertos.
- Si hay vínculos incorrectos o saldos negativos, bloquear la operación y corregir el flujo antes de validar el MVP.
- Si una historia no tiene issue o estado, completar la trazabilidad antes de cerrar el backlog.
- Si un PR no recibió revisión real de otra persona, no presentarlo como evidencia de revisión entre pares.
