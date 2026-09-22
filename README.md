<div align="center">

<p align="center">
  <a href="README_EN.md">
    <b>🌐 Read this in English →</b>
  </a>
</p>

# 🎮 Epic-Claim
### Reclama tus juegos gratis de Epic Games en Android en 2 o 3 toques

[![Release](https://img.shields.io/github/v/release/RogzcaMX/Epic-Claim?color=6366f1&style=for-the-badge&logo=android)](https://github.com/RogzcaMX/Epic-Claim/releases)
[![License](https://img.shields.io/badge/License-Open%20Source-emerald?style=for-the-badge)](LICENSE)
[![Platform](https://img.shields.io/badge/Platform-Android-blue?style=for-the-badge&logo=android)](https://www.android.com/)
[![Ko-Fi](https://img.shields.io/badge/Ko--Fi-Buy%20a%20Coffee-ff5e5b?style=for-the-badge&logo=kofi)](https://ko-fi.com/rogzca)

<p align="center">
  <b>Epic-Claim</b> nace para los que nos da pereza encender la PC o abrir el navegador cada semana para reclamar los regalos de Epic Games. Especialmente pensado si administras múltiples cuentas y odias estar iniciando y cerrando sesión constantemente.
</p>

[Descargar APK (Última Versión)](https://github.com/RogzcaMX/Epic-Claim/releases) • [Sitio Web](https://rogzcamx.github.io/Epic-Claim/) • [Preguntas Frecuentes](#-preguntas-frecuentes)

</div>

---

## ✨ Características Principales

- 👥 **Soporte Multicuenta Sin Límites:** Vincula todas las cuentas que quieras y alterna entre ellas con un solo toque desde la barra superior.
- ⚡ **Canje Asistido Rápido:** Abre directo la pasarela de $0 con la sesión inyectada por cookies. Solo confirmas y marcas el canje.
- 📦 **Insignia "En Biblioteca":** Identifica al instante si la cuenta activa ya reclamó el título actual para no perder tiempo ni datos móviles.
- 📜 **Historial Independiente por Cuenta:** Cada perfil lleva su propio registro de juegos canjeados con fecha, hora y buscador en tiempo real.
- 🔔 **Alertas en Segundo Plano:** Notificaciones automáticas con `WorkManager`. Configúralas para el reseteo semanal de Epic (jueves 15:00 UTC), cada 24 horas o en tu horario personalizado.
- 🔒 **100% Privado y Local:** No hay servidores externos ni bases de datos en la nube. Tus sesiones se almacenan cifradas en tu teléfono mediante `EncryptedSharedPreferences` (AES-256).
- 🎨 **Personalización Total:** Tema claro, oscuro manual, según el sistema o programado por horas. Soporte en Español e Inglés.

---

## 📱 ¿Cómo funciona el flujo de reclamo?

1. **Añade tu cuenta:** Inicia sesión una única vez mediante el navegador seguro integrado para registrar las cookies de sesión.
2. **Revisa los juegos semanales:** La app consulta directamente la API oficial de promociones de Epic Games.
3. **Canjea en 2 taps:** Pulsa **Canjear**, la app te llevará directo a la pasarela de costo $0 con tu sesión iniciada. Confirma el pedido en Epic Games y marca el botón verde (✓) para añadirlo a tu historial.
4. **Alterna:** Cambia a tu siguiente cuenta desde el menú superior y repite el proceso en segundos.

---

## 📥 Descarga e Instalación

1. Ve a la sección de [Releases de GitHub](https://github.com/RogzcaMX/Epic-Claim/releases).
2. Descarga el archivo `.apk` de la versión más reciente (ej. `Epic-Claim.v1.0.Archikos.apk`).
3. Abre el archivo en tu dispositivo Android y acepta los permisos de instalación desde orígenes desconocidos si el sistema lo solicita.
4. ¡Listo! Ya puedes vincular tus cuentas.

---

## 🛠️ Tecnologías Utilizadas

- **Lenguaje:** Kotlin
- **UI:** Jetpack Compose & Material Design 3
- **Red:** Retrofit 2 & Gson (API pública de Epic Games Store)
- **Carga de Imágenes:** Coil
- **Segundo Plano:** Android Jetpack WorkManager
- **Seguridad y Persistencia:** AndroidX Security Crypto (`EncryptedSharedPreferences`) & SharedPreferences

---

## ❓ Preguntas Frecuentes

<details>
<summary><b>¿Por qué la app no automatiza el reclamo al 100%?</b></summary>
<br>
Epic Games integra protecciones anti-bot (hCaptcha) y pasarelas de pago que requieren interacción humana para evitar abusos automatizados. Epic-Claim se encarga de saltarse toda la navegación tediosa e inyectar tu sesión para que solo tengas que confirmar la orden.
</details>

<details>
<summary><b>¿El creador puede ver mis contraseñas o cuentas?</b></summary>
<br>
No. La aplicación no tiene servidores intermedios, bases de datos ni conexión con el creador. Todo el inicio de sesión se realiza directamente contra los servidores de Epic Games y las cookies se guardan exclusivamente en el almacenamiento protegido de tu propio teléfono.
</details>

<details>
<summary><b>¿Por qué después de unos días me pide renovar sesión?</b></summary>
<br>
Epic Games invalida los tokens y cookies periódicamente por seguridad. Cuando esto pase, solo pulsa en el menú de cuentas la opción <i>Reiniciar sesión de Cuenta</i> para actualizar las credenciales sin perder tu historial.
</details>

---

## ☕ Apoyo y Donaciones

Epic-Claim es un proyecto personal, gratuito y de código abierto. Si te resulta útil y te ahorra tiempo semana tras semana, puedes invitarme un café:

<div align="center">
  <a href="https://ko-fi.com/rogzca" target="_blank">
    <img src="https://ko-fi.com/img/githubbutton_sm.svg" alt="Apoyar en Ko-Fi">
  </a>
</div>

---

## 📬 Contacto

- **Reportes de errores o fallos:** `soporte_rogzca@yahoo.com`
- **Comentarios y sugerencias:** `feedback_rogzca@yahoo.com`

---

<div align="center">
  <sub>Desarrollado con dedicación por <b>Rogzca</b> con asistencia de Gemini AI.</sub><br>
  <sub>Este proyecto no está afiliado, respaldado ni asociado con Epic Games, Inc.</sub>
</div>
