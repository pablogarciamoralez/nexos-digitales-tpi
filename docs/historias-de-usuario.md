# Historias de usuario del MVP

Las siguientes historias se redactan en forma formal a partir de las funciones y entidades definidas en las entregas anteriores. Son especificaciones propuestas, no funcionalidades finalizadas.

## HU-01 — Gestión de contratos, proyectos y horas

**Como** integrante del área Comercialización o Desarrollo, **quiero** registrar y consultar clientes, contratos, proyectos y horas trabajadas, **para** contar con información única y consistente que sirva de base a la facturación.

**Criterios de aceptación**
1. Cada contrato está vinculado con un cliente existente.
2. Cada proyecto pertenece a un contrato existente.
3. El registro de horas indica proyecto, fecha, cantidad y si son facturables.
4. No se permite registrar horas negativas ni asociarlas a proyectos inexistentes.

## HU-02 — Preparación y emisión de comprobantes

**Como** integrante de Finanzas y Control, **quiero** preparar y revisar las facturas utilizando contratos y proyectos registrados, **para** emitir comprobantes coherentes y controlar sus vencimientos.

**Criterios de aceptación**
1. Antes de la emisión se comprueban datos del contrato, importes y vencimiento.
2. Si faltan datos, el comprobante no se confirma y se solicita corrección.
3. Ante un rechazo del servicio fiscal externo, se conserva la observación y no se marca la factura como autorizada.
4. Una factura autorizada queda vinculada con su contrato y puede consultarse por estado.

**Aclaración:** la integración con ARCA forma parte del diseño y no se considera implementada.

## HU-03 — Seguimiento de cuentas por cobrar y por pagar

**Como** integrante de Finanzas y Control, **quiero** registrar los cobros de facturas y los pagos de obligaciones a proveedores, **para** conocer saldos pendientes y vencimientos sin duplicar cálculos.

**Criterios de aceptación**
1. Cada cobro se relaciona con una factura; cada pago, con una obligación registrada.
2. Un movimiento debe tener importe positivo y no superar el saldo pendiente.
3. El saldo se recalcula a partir del importe original y los movimientos válidos.
4. Se distingue entre pendiente, parcial y cancelado/pagado según el tipo de cuenta.
5. Si un movimiento bancario o importe no puede conciliarse, queda pendiente de revisión.

## Seguimiento sugerido

| Historia | Issue real de GitHub | Estado en tablero |
|---|---|---|
| HU-01 | Completar con enlace a issue | Por Hacer (inicial) |
| HU-02 | Completar con enlace a issue | Por Hacer (inicial) |
| HU-03 | Completar con enlace a issue | Por Hacer (inicial) |
