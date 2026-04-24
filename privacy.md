# Política de Privacidad — Clay Open Series

**Última actualización:** 23 de abril de 2026
**Vigente desde:** 23 de abril de 2026

Clay Open Series ("nosotros", "nuestro" o "la app") respeta tu
privacidad. Este documento describe qué datos recolectamos, cómo los
usamos y tus derechos como usuario.

---

## 1. Quién somos

Clay Open Series es una aplicación móvil para la gestión de torneos,
ligas y partidos de tenis entre clubes. Esta política aplica al uso
de la app en iOS y Android y a cualquier servicio relacionado.

**Contacto:** rarcemu@gmail.com

---

## 2. Qué datos recolectamos

### 2.1 Datos de cuenta
- **Email** (obligatorio) — para autenticación e identificación.
- **Nombre completo** — provisto por ti o por Sign in with Apple /
  Google en el primer login.
- **Avatar** (opcional) — imagen de perfil que subes.

### 2.2 Datos de uso
- **Inscripciones a torneos y ligas** — equipo, categoría, seed.
- **Resultados de partidos** — sets, games, ganador.
- **Standings y rankings** generados a partir de resultados.

### 2.3 Datos de pago (cuando aplica)
- **ID de transacción** de MercadoPago para inscripciones pagadas.
- **Estado de pago** (pendiente, confirmado, fallido).
- **NO almacenamos tarjetas ni datos bancarios** — MercadoPago
  procesa todos los pagos directamente.

### 2.4 Datos técnicos
- **Device token** (para notificaciones push, si las activas).
- **Logs de errores** — capturados anónimamente para debugging.

---

## 3. Cómo usamos tus datos

Usamos tus datos exclusivamente para:

1. **Autenticar** tu acceso a la app.
2. **Gestionar** tu participación en torneos y ligas.
3. **Notificarte** sobre partidos, resultados y actualizaciones
   de tus inscripciones.
4. **Procesar pagos** vía MercadoPago cuando te inscribes a un
   torneo con costo.
5. **Mejorar** la app mediante análisis anónimos de uso.

**No vendemos, alquilamos ni compartimos tus datos con terceros
para fines publicitarios.**

---

## 4. Terceros que procesan tus datos

| Servicio | Propósito | Datos compartidos |
|----------|-----------|-------------------|
| Apple Sign In | Autenticación | ID de Apple (sub), email |
| Google Sign In | Autenticación | ID de Google, email, nombre |
| MercadoPago | Procesamiento de pagos | Monto, email, ID transacción |
| Resend | Envío de emails (magic link) | Email destinatario |
| Railway | Hosting de servidor | Todos los datos anteriores (alojados) |
| Apple Push Notification Service | Notificaciones iOS | Device token |

---

## 5. Dónde almacenamos tus datos

Los datos se almacenan en servidores de **Railway** ubicados en
**Estados Unidos** (región `us-east`). La base de datos usa PostgreSQL
con cifrado en tránsito (TLS 1.3) y en reposo.

---

## 6. Cuánto tiempo guardamos tus datos

- **Datos de cuenta**: mientras tu cuenta esté activa.
- **Historial de torneos y ligas**: indefinidamente (datos
  históricos de competencia).
- **Logs técnicos**: 30 días.
- **Magic links / códigos de verificación**: 15 minutos.

Si eliminas tu cuenta, borramos todos tus datos personales
identificables dentro de 30 días. El historial competitivo se
anonimiza pero se conserva para preservar la integridad de los
rankings.

---

## 7. Tus derechos

Tienes derecho a:

1. **Acceder** a los datos que tenemos sobre ti.
2. **Corregir** datos incorrectos.
3. **Eliminar** tu cuenta y datos personales.
4. **Exportar** tus datos en formato legible.
5. **Oponerte** al procesamiento con fines específicos.
6. **Retirar consentimiento** para notificaciones push.

Para ejercer cualquiera de estos derechos, escríbenos a
**rarcemu@gmail.com**. Respondemos dentro de 30 días.

---

## 8. Menores de edad

La app está pensada para usuarios mayores de 13 años. Si detectamos
que un usuario es menor de 13 años, eliminaremos su cuenta y datos
inmediatamente.

---

## 9. Seguridad

Implementamos medidas técnicas y organizativas para proteger tus
datos:

- Cifrado en tránsito (TLS 1.3) y en reposo.
- Autenticación mediante tokens JWT de corta duración (15 min).
- Rate limiting para prevenir ataques de fuerza bruta.
- Sesiones vinculadas a dispositivos con detección de uso
  sospechoso.

---

## 10. Cambios a esta política

Podemos actualizar esta política periódicamente. Te notificaremos
de cambios significativos por email o mediante aviso in-app antes
de que entren en vigor.

---

## 11. Contacto y consultas

Para dudas, reclamos o solicitudes:

**Email:** rarcemu@gmail.com
**Ubicación:** Santiago, Chile

---

_Versión 1.0.0 — Esta política aplica al uso de Clay Open Series
en iOS y Android._
