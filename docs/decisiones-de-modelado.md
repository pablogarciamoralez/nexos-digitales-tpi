# Alcance y decisiones de modelado BPMN

Se separaron dos procesos para no mezclar facturas a clientes con obligaciones a proveedores. Ambos forman parte del módulo integrado definido en los trabajos previos.

## Facturación y cobranzas

**Participantes:** Cliente, Nexos Digitales S.R.L., ARCA y entidad bancaria. Dentro del pool de Nexos se distinguen las lanes de Comercialización, Finanzas y Control y Sistema (comportamiento automático).

**Secuencia habitual:** solicitud → control del contrato → obtención de horas y datos → revisión del borrador → solicitud de autorización externa → registro de factura y vencimiento → aviso de cobro → validación → aplicación al saldo.

**Excepciones:** información insuficiente, condiciones no aprobadas, rechazo fiscal y diferencias en cobranzas. Las tareas internas están enlazadas con flujos de secuencia; los intercambios con participantes externos se muestran mediante flujos de mensaje. Se modela una propuesta futura, no una integración ya probada.

## Cuentas por pagar

**Participantes:** Proveedor, Nexos Digitales S.R.L. y entidad bancaria. Las lanes distinguen Finanzas y Control y Sistema.

**Secuencia habitual:** recibir obligación → registrar vencimiento → verificar datos → programar pago → enviar orden → confirmar operación → registrar pago y recalcular saldo.

**Excepciones:** datos incompletos o inconsistentes, y rechazo de la orden bancaria.

## Notación aplicada

- Evento de inicio (círculo fino) y de fin (círculo grueso).
- Tareas representadas por rectángulos redondeados.
- Compuertas exclusivas (rombos con X) para decisiones Sí/No.
- Eventos intermedios de mensaje para recibir comunicaciones externas cuando corresponde.
- Pools para participantes y lanes para separar responsabilidades internas.
- Flujo de secuencia continuo dentro del proceso y flujos de mensaje discontinuos entre participantes.

El dibujo está disponible en SVG/PNG y la definición BPMN 2.0 en XML (`.bpmn`) para revisar o ajustar con un modelador compatible.
