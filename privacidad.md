---
title: Aviso de privacidad · Privacy notice — Hito
permalink: /privacidad/
---

<p><strong>Español</strong> · <a href="#english">English</a> · <a href="../terminos/">Términos de uso · Terms of use</a></p>

# Aviso de privacidad de Hito

*Vigente desde el 12 de noviembre de 2026 · Versión 0.6*

Este aviso explica qué datos personales usa **Hito** (la aplicación para Windows, Android, macOS y Linux, y este sitio), para qué y qué derechos tienes. Se emite en atención a la Ley Federal de Protección de Datos Personales en Posesión de los Particulares y, en lo aplicable, a otras leyes de privacidad como el Reglamento General de Protección de Datos de la Unión Europea (RGPD).

## 1. Quién es el responsable
Hito es una aplicación gratuita desarrollada por **Miguel Huerta** ("el desarrollador"). Medio de contacto para todo lo relacionado con privacidad: [abre un *issue* en github.com/miguelhuerta-dev/hitodemo](https://github.com/miguelhuerta-dev/hitodemo/issues) o escribe a través de [github.com/miguelhuerta-dev](https://github.com/miguelhuerta-dev).

## 2. Resumen
- **Hito no tiene servidores, ni cuentas de usuario, ni analítica, ni publicidad.** El desarrollador **no recibe, no ve y no guarda** ninguno de tus datos.
- Todo lo que registras se queda **en tu propio dispositivo**.
- Si **tú decides** conectar Google Calendar o un calendario por enlace, Hito se comunica **directamente desde tu dispositivo** con ese servicio. Nada pasa por servidores de Hito.
- Hito **no vende, no comparte, no transfiere y no usa tus datos** para publicidad ni para entrenar modelos de inteligencia artificial.

## 3. Datos que se guardan en tu dispositivo
| Dato | Para qué | Dónde |
|---|---|---|
| Actividades, historial, marcadores, rutinas y entrenamientos | Que la agenda funcione | Archivo local de Hito |
| Gastos, tarjetas, suscripciones y presupuesto | Calcular tus finanzas personales | Archivo local de Hito |
| Medicamentos y dieta que registres (pueden ser datos de salud) | Mostrarlos en tu agenda | Archivo local de Hito |
| Preferencias (idioma, tema, recorrido visto) | Recordar cómo usas la app | Archivo local y almacenamiento del navegador interno |
| Registro técnico de errores (`hito.log`, solo versión portable) | Que tú puedas diagnosticar fallas | Carpeta `datos`, nunca se envía |

Estos datos **no salen de tu dispositivo** salvo que tú los exportes (respaldo, archivo .ics) o conectes una agenda externa. Los datos de salud y financieros que registres son **datos sensibles**: como solo existen en tu dispositivo, tú tienes el control total sobre ellos. Te recomendamos proteger tu equipo o teléfono con contraseña.

## 4. Google Calendar (opcional)
Si eliges **Conectar** en *Ajustes → Agendas conectadas*, Hito solicita, con tu autorización expresa en la pantalla de Google, permiso para ver y editar tus calendarios (`https://www.googleapis.com/auth/calendar`) para conocer tu correo electrónico (`email`) y, solo si activas la sincronización entre dispositivos, para usar la **carpeta privada de Hito en tu Google Drive** (`https://www.googleapis.com/auth/drive.appdata`; Hito no puede ver ningún otro archivo de tu Drive), con el único fin de:
- mostrar tus eventos de Google dentro de Hito;
- guardar en tu Google Calendar las actividades que creas o cambias en Hito;
- crear un calendario llamado "Hito" en tu cuenta;
- mostrarte qué cuenta está conectada;
- guardar el archivo cifrado de sincronización entre tus dispositivos (ver punto 5 bis).

**Cómo se guardan:** los eventos sincronizados se guardan en el archivo local de Hito. El permiso de acceso (token) se guarda **cifrado en tu dispositivo** (en Windows y Android, con la protección del sistema operativo). **Con quién se comparten:** con nadie; solo viajan entre tu dispositivo y Google, cuyo tratamiento se rige por la [Política de privacidad de Google](https://policies.google.com/privacy).

**Uso limitado:** el uso que hace Hito de la información recibida de las API de Google cumple con la [Política de datos de usuario de los servicios de las API de Google](https://developers.google.com/terms/api-services-user-data-policy), incluidos los requisitos de Uso Limitado.

## 5. Calendarios por enlace (.ics) (opcional)
Si agregas un enlace, Hito descarga ese calendario directamente desde la dirección que escribiste, solo para mostrarlo. El servicio que lo publica puede registrar la descarga según sus propias políticas.

## 5 bis. Sincronización entre tus dispositivos (opcional)
Si activas *Ajustes → Tus dispositivos*, Hito guarda una copia de tus datos **cifrada con una clave que solo tú conoces** (AES-256-GCM) en el lugar que elijas: la carpeta privada de Hito en tu Google Drive o una carpeta de tu propio servicio de nube (OneDrive, Dropbox, iCloud Drive…). Ese servicio guarda el archivo, pero **no puede leerlo**; el desarrollador tampoco tiene acceso. La clave nunca sale de tus dispositivos. Puedes desactivarlo en cualquier momento.

## 5 ter. Avisos y notificaciones
Para avisarte de tus actividades, Hito programa notificaciones **en tu propio dispositivo** (en Android, con alarmas del sistema). No se usa ningún servicio de notificaciones externo. En Android, si tienes activada la copia de seguridad de tu teléfono, el sistema puede incluir los datos de Hito en tu copia personal de Google.

## 6. Cookies y tecnologías similares
Hito **no usa cookies de rastreo, de publicidad ni de analítica**, ni las de terceros.
- **Cookie técnica de seguridad** (`.AspNetCore.Antiforgery…`), solo en la versión portable: la crea el pequeño servidor que Hito ejecuta en tu propio equipo (`127.0.0.1`) para proteger los formularios. No contiene datos personales y nunca sale de tu equipo.
- **Almacenamiento local**: `hito-lang` (idioma elegido, para mostrar la pantalla de carga en tu idioma) y `hito-splash` (si ya viste la animación de inicio en esta sesión; se borra al cerrar).

Todas son estrictamente necesarias para que la app funcione, por lo que no requieren consentimiento. Este sitio (GitHub Pages) no agrega cookies propias ni analítica; GitHub puede tratar datos técnicos de tu visita según la [Declaración de privacidad de GitHub](https://docs.github.com/es/site-policy/privacy-policies/github-general-privacy-statement).

## 7. Tus derechos (ARCO) y cómo ejercerlos
Tienes derecho a **acceder, rectificar, cancelar u oponerte** al tratamiento de tus datos, a **revocar tu consentimiento** y, si aplica el RGPD, a la portabilidad y a la limitación. Como tus datos están solo en tu dispositivo, puedes ejercerlos tú mismo en cualquier momento:
- **Acceder y llevarte tus datos:** *Ajustes → Descargar respaldo* (archivo JSON) o exportar a calendario (.ics).
- **Rectificar:** edita cualquier registro en la app.
- **Cancelar (borrar):** *Ajustes → Empezar de nuevo*, o desinstala la app (el instalador de Windows te pregunta si deseas borrar tus datos; en la versión portable, borra la carpeta `datos`).
- **Revocar el acceso a Google:** *Ajustes → Agendas conectadas → Desconectar*, o en [myaccount.google.com/permissions](https://myaccount.google.com/permissions).

Para cualquier duda o solicitud, usa el medio de contacto del punto 1. Si consideras que tus derechos fueron vulnerados, puedes acudir a la autoridad de protección de datos de tu país.

## 8. Menores de edad
Hito no está dirigido a menores de 13 años (o la edad mínima que fije tu país). El desarrollador no recopila datos de nadie.

## 9. Cambios a este aviso
Cualquier cambio se publicará en esta misma página con su nueva fecha y se mencionará en las notas de versión.

---

<h1 id="english">Hito Privacy Notice</h1>

*Effective November 12, 2026 · Version 0.6*

This notice explains what personal data **Hito** (the app for Windows, Android, macOS and Linux, and this website) uses, why, and what rights you have. It is issued under Mexico's Federal Law on the Protection of Personal Data Held by Private Parties and, where applicable, other privacy laws such as the EU General Data Protection Regulation (GDPR).

## 1. Who is responsible
Hito is a free app developed by **Miguel Huerta** ("the developer"). Privacy contact: [open an issue at github.com/miguelhuerta-dev/hitodemo](https://github.com/miguelhuerta-dev/hitodemo/issues) or reach out via [github.com/miguelhuerta-dev](https://github.com/miguelhuerta-dev).

## 2. Summary
- **Hito has no servers, user accounts, analytics, or ads.** The developer **does not receive, see, or store** any of your data.
- Everything you enter stays **on your own device**.
- If **you choose** to connect Google Calendar or a calendar link, Hito talks **directly from your device** to that service. Nothing goes through Hito servers.
- Hito **does not sell, share, transfer, or use your data** for advertising or to train artificial intelligence models.

## 3. Data stored on your device
| Data | Purpose | Where |
|---|---|---|
| Activities, history, milestones, routines and workouts | Make the planner work | Hito's local file |
| Expenses, cards, subscriptions and budget | Calculate your personal finances | Hito's local file |
| Medications and diet you enter (may be health data) | Show them on your schedule | Hito's local file |
| Preferences (language, theme, tour seen) | Remember how you use the app | Local file and the built-in browser storage |
| Technical error log (`hito.log`, portable version only) | Let you diagnose problems | `datos` folder, never sent |

This data **never leaves your device** unless you export it (backup, .ics file) or connect an external calendar. Health and financial data you enter are **sensitive data**: since they exist only on your device, you are in full control of them. We recommend protecting your computer or phone with a password.

## 4. Google Calendar (optional)
If you choose **Connect** in *Settings → Connected calendars*, Hito requests, with your express authorization on Google's screen, permission to see and edit your calendars (`https://www.googleapis.com/auth/calendar`) to know your email address (`email`) and, only if you turn on device sync, to use **Hito's private folder in your Google Drive** (`https://www.googleapis.com/auth/drive.appdata`; Hito can't see any other file in your Drive), solely to:
- show your Google events inside Hito;
- save the activities you create or change in Hito to your Google Calendar;
- create a calendar named "Hito" in your account;
- show you which account is connected;
- store the encrypted sync file shared by your devices (see section 5a).

**How it's stored:** synced events are saved in Hito's local file. The access permission (token) is stored **encrypted on your device** (on Windows and Android, with the operating system's protection). **Who it's shared with:** no one; it only travels between your device and Google, whose processing is governed by the [Google Privacy Policy](https://policies.google.com/privacy).

**Limited Use:** Hito's use of information received from Google APIs adheres to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements.

## 5. Calendars by link (.ics) (optional)
If you add a link, Hito downloads that calendar directly from the address you entered, only to display it. The service publishing it may log the download under its own policies.

## 5a. Sync between your devices (optional)
If you turn on *Settings → Your devices*, Hito stores a copy of your data **encrypted with a passphrase only you know** (AES-256-GCM) in the place you choose: Hito's private folder in your Google Drive or a folder in your own cloud service (OneDrive, Dropbox, iCloud Drive…). That service stores the file but **cannot read it**; the developer has no access either. The passphrase never leaves your devices. You can turn it off at any time.

## 5b. Reminders and notifications
To remind you of your activities, Hito schedules notifications **on your own device** (on Android, with system alarms). No external notification service is used. On Android, if your phone backup is on, the system may include Hito's data in your personal Google backup.

## 6. Cookies and similar technologies
Hito **does not use tracking, advertising, or analytics cookies**, nor third-party cookies.
- **Technical security cookie** (`.AspNetCore.Antiforgery…`), portable version only: created by the small server Hito runs on your own computer (`127.0.0.1`) to protect forms. It contains no personal data and never leaves your computer.
- **Local storage**: `hito-lang` (chosen language, to show the loading screen in your language) and `hito-splash` (whether you already saw the startup animation this session; cleared on close).

All are strictly necessary for the app to work, so they do not require consent. This website (GitHub Pages) adds no cookies or analytics of its own; GitHub may process technical data about your visit under the [GitHub Privacy Statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement).

## 7. Your rights and how to exercise them
You have the right to **access, rectify, delete, or object** to the processing of your data, to **withdraw consent**, and, where the GDPR applies, to portability and restriction. Since your data is only on your device, you can exercise them yourself at any time:
- **Access and take your data:** *Settings → Download backup* (JSON file) or export to calendar (.ics).
- **Rectify:** edit any record in the app.
- **Delete:** *Settings → Start over*, or uninstall the app (the Windows installer asks whether to delete your data; for the portable version, delete the `datos` folder).
- **Revoke Google access:** *Settings → Connected calendars → Disconnect*, or at [myaccount.google.com/permissions](https://myaccount.google.com/permissions).

For any question or request, use the contact in section 1. If you believe your rights were violated, you may contact the data protection authority in your country.

## 8. Children
Hito is not directed to children under 13 (or the minimum age set by your country). The developer collects no one's data.

## 9. Changes to this notice
Any change will be posted on this page with its new date and mentioned in the release notes.
