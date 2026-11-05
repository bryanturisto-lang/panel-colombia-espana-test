# Panel Colombia/España (test)

Panel v2 de asesores de Turisto, conectado a los datos **reales** de Colombia y España: el mismo Supabase (`feipxsctjjfsylosqxon`) y los mismos Apps Script del panel actual. Lo que se hace aquí cuenta de verdad.

## Fase 1 (esta versión)

- Inicio de sesión con las mismas cuentas del panel actual.
- Leads de los últimos 7 días, comprobante de contacto, estados (nuevo, contactado, venta, perdido).
- Registro en el turno: primero la hoja de reparto (Apps Script) y después Supabase.
- Leads erróneos con revisión de la captura por IA (función `swift-action`).
- Asignadora: rutas por asesor, bloquear, retirar, sacar del turno, pausa del reparto, asignar a mano, ajustes.
- Estadísticas de hoy, 7 y 30 días.

## Fase 2 (pendiente)

Etapas Cotizado y En seguimiento, gestiones y agenda, documentos, ventas con monto y comprobante, leads propios. Necesitan un SQL nuevo.
