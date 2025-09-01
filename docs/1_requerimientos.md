# 1. Requerimientos Funcionales y No Funcionales

## 1.1 Objetivo
Definir los requerimientos del sistema de banca digital para clientes corporativos.

## 1.2 Requerimientos Funcionales

| ID | Descripción | Prioridad |
|----|-------------|---------|
| RF-101 | El usuario debe autenticarse con certificado digital o token | Alta |
| RF-102 | El sistema debe permitir crear una orden de pago internacional | Alta |
| RF-103 | Si el monto > USD 10,000, se requiere aprobación de al menos 2 usuarios autorizados | Media |
| RF-104 | El sistema debe generar un reporte diario de transacciones ejecutadas | Baja |
| RF-105 | El usuario debe poder consultar el estado de sus órdenes pendientes | Alta |

## 1.3 Requerimientos No Funcionales

| ID | Descripción | Categoría |
|----|-------------|---------|
| RNF-201 | Tiempo de respuesta < 2 segundos en operaciones críticas | Rendimiento |
| RNF-202 | Disponibilidad del sistema 99.9% (SLA) | Disponibilidad |
| RNF-203 | Autenticación de dos factores (2FA) obligatoria | Seguridad |
| RNF-204 | Logs de auditoría para todas las transacciones | Auditoría |
| RNF-205 | Interfaz en español e inglés | Usabilidad |
