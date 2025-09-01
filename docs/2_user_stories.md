 Historias de Usuario (User Stories)

Todas las historias siguen el formato INVEST y tienen criterios de aceptación claros.

---

Como usuario del sistema

US-01: Iniciar sesión

Como usuario, quiero iniciar sesión con mi certificado digital para acceder al sistema.

**Criterios de aceptación:**
- El sistema valida el certificado contra la CA.
- Si es inválido, muestra mensaje: "Certificado no válido".
- Si es válido, redirige al dashboard.

---

 US-02: Crear orden de pago

Como gerente financiero, quiero crear una orden de pago internacional y asignarla a un aprobador.

**Criterios de aceptación:**
- El sistema valida que el monto esté dentro del límite autorizado.
- Si supera USD 10,000, marca la orden como "Pendiente de aprobación".
- Se registra la fecha y usuario creador.

---

US-03: Aprobar orden

Como aprobador, quiero recibir notificaciones de órdenes pendientes y poder aprobar/rechazar desde el panel.

**Criterios de aceptación:**
- Notificación por email y en el sistema.
- Botones claros: "Aprobar" / "Rechazar" con justificación obligatoria si se rechaza.
- Historial de aprobaciones guardado.
