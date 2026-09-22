# Cierre Rentas Tango

PWA independiente para control diario de rentas, pagos y depósitos de Tango.

## Reglas V1
- Depósitos: siempre efectivo; Q, US$ o €; separados de ingresos.
- Renta: efectivo Q/US$/€ o tarjeta.
- Tarjeta: el cierre muestra únicamente la renta neta; el 10% adicional queda implícito en el cobro.
- Moneda extranjera: registrar el efectivo físico recibido. La tarifa debe calcularse con la regla Tango y redondearse hacia arriba al siguiente monto terminado en 5 o 0.
- No permite cierre si hay método de pago pendiente.

Datos guardados localmente en el dispositivo en esta V1.