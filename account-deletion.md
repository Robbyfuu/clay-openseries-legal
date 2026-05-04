---
layout: default
title: Eliminación de Cuenta — Clay Open Series
---

# Eliminación de Cuenta — Clay Open Series

**Última actualización:** 4 de mayo de 2026

Esta página describe cómo solicitar la eliminación de tu cuenta de Clay Open Series y los datos personales asociados.

**Aplicación:** Clay Open Series  
**Desarrollador:** Roberto Hernan Arce Muñoz (rarcemu@gmail.com)  
**Plataformas:** iOS (App Store) y Android (Google Play)

---

## Cómo solicitar la eliminación

Para solicitar la eliminación de tu cuenta y todos los datos personales asociados, sigue uno de estos pasos:

### Opción A — Desde la app (recomendado)

1. Abre la app **Clay Open Series**
2. Inicia sesión con tu cuenta
3. Ve a **Perfil** → **Cuenta** → **Eliminar cuenta**
4. Confirma la eliminación

> **Nota V1:** la opción "Eliminar cuenta" desde la app está en desarrollo. Mientras tanto, usa la **Opción B**.

### Opción B — Por email

Envía un correo a **rarcemu@gmail.com** con:

- **Asunto:** `Eliminar cuenta — Clay Open Series`
- **Cuerpo:** incluye tu email registrado en la app y, opcionalmente, el motivo de la eliminación.

Procesaremos tu solicitud dentro de **30 días corridos** y recibirás una confirmación por correo cuando se complete.

---

## Qué datos se eliminan

Al confirmar la eliminación, borramos permanentemente:

- **Datos de cuenta:** email, nombre completo, avatar de perfil
- **Inscripciones a torneos y ligas:** equipo, categoría, seed, fecha de inscripción
- **Resultados de partidos:** sets, games, ganador, estadísticas individuales
- **Preferencias:** configuración de la app, idioma, tema
- **Tokens de sesión:** access tokens, refresh tokens, biometric tokens cacheados en tu dispositivo
- **Foto de perfil y archivos asociados** (almacenados en Cloudflare R2 / Backblaze)

---

## Qué datos se conservan

Por requerimientos legales, técnicos o de integridad del juego, conservamos los siguientes datos de manera **anonimizada o agregada**:

- **Resultados históricos de torneos** (sin identificar al jugador) — para mantener la integridad de standings y rankings de torneos pasados que ya están publicados.
- **Logs técnicos de operación** — durante 90 días para debugging y seguridad. No incluyen datos personales identificables tras la eliminación.
- **Registros contables de pagos** (si los hubo) — durante el plazo legal vigente en Chile (6 años por SII), únicamente con monto y fecha de transacción, sin asociar a tu identidad.

---

## Períodos de retención adicionales

| Tipo de dato | Retención |
|--------------|-----------|
| Datos de cuenta + uso | Eliminados en hasta 30 días tras la solicitud |
| Backups encriptados | Hasta 90 días tras la eliminación (rotación automática) |
| Logs de seguridad | Hasta 90 días tras la eliminación |
| Registros contables (anonimizados) | 6 años (requerimiento SII Chile) |

Tras estos plazos, todos los datos personales son irreversiblemente eliminados.

---

## Eliminación parcial

Si solo deseas eliminar **algunos** datos sin cerrar tu cuenta (por ejemplo, tu avatar o una inscripción específica), puedes hacerlo desde la app o solicitarlo en el mismo correo indicando claramente qué datos quieres borrar.

---

## Contacto

¿Dudas sobre el proceso de eliminación?

**Email:** [rarcemu@gmail.com](mailto:rarcemu@gmail.com)  
**Política de Privacidad completa:** [Privacy Policy](privacy.html)
