# Panel de Asesores · Colombia y España

Panel de asesores de Turisto (versión 2), conectado a los datos **reales** de Colombia y España: el mismo Supabase (`feipxsctjjfsylosqxon`) y los mismos Apps Script del panel anterior. Reemplaza al panel v1.

## Qué hace

- Inicio de sesión con las mismas cuentas del panel anterior.
- Leads con comprobante de contacto y estados (nuevo, contactado, venta, perdido).
- Historial por periodo: hoy, 7, 30 o 90 días, todo el historial o fechas a elegir.
- Registro en el turno: primero la hoja de reparto (Apps Script) y después Supabase.
- Aviso cuando alguien figura en el turno del panel pero no en la hoja de reparto, con botón para volver a anotarlo.
- Leads erróneos con revisión de la captura por IA (función `swift-action`).
- Asignadora: rutas por asesor, bloquear, retirar, sacar del turno, pausa del reparto, asignar a mano y ajustes.
- Estadísticas por asesor con los mismos periodos que el historial.

## Pendiente (fase 2)

Etapas Cotizado y En seguimiento, gestiones y agenda, documentos, ventas con monto y comprobante, y leads propios. Necesitan un SQL nuevo.
