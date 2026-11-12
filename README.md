<p align="center"><img src="icono.png" width="96" alt=""></p>

<h1 align="center">hito.</h1>
<p align="center">Tu agenda, tus marcadores, tu entrenamiento y tus finanzas en una sola línea de tiempo.<br>
<em>Your schedule, milestones, workouts, and finances on a single timeline.</em></p>

<p align="center"><strong>Español</strong> · <a href="#english">English</a></p>

> **Nuevo en 0.6 · New in 0.6:** avisos para medicamentos y actividades (también con el celular bloqueado) · captura rápida escribiendo una frase · tus dispositivos sincronizados y cifrados · Google Calendar en los dos sentidos · logo nuevo.
> *Reminders (even on the lock screen) · quick add in natural language · encrypted sync between your devices · two-way Google Calendar · new logo.*

## Descargar · Download

### Recomendado · Recommended

| Sistema · System | Descarga · Download |
|---|---|
| **Windows 10 / 11** — instalador · installer | [Hito-0.6.0-Instalador.exe](https://github.com/miguelhuerta-dev/hitodemo/releases/download/v0.6.0/Hito-0.6.0-Instalador.exe) |
| **Android 7+** — app | [Hito-0.6.0-android.apk](https://github.com/miguelhuerta-dev/hitodemo/releases/download/v0.6.0/Hito-0.6.0-android.apk) |

### Portable (sin instalar · no install)

| Sistema · System | Descarga · Download |
|---|---|
| **Windows 10 / 11** | [Hito-0.6.0-win-x64.zip](https://github.com/miguelhuerta-dev/hitodemo/raw/main/Hito-0.6.0-win-x64.zip) |
| **Mac M1 / M2 / M3 / M4** | [Hito-0.6.0-osx-arm64.zip](https://github.com/miguelhuerta-dev/hitodemo/raw/main/Hito-0.6.0-osx-arm64.zip) |
| **Mac Intel** | [Hito-0.6.0-osx-x64.zip](https://github.com/miguelhuerta-dev/hitodemo/raw/main/Hito-0.6.0-osx-x64.zip) |
| **Linux** | [Hito-0.6.0-linux-x64.zip](https://github.com/miguelhuerta-dev/hitodemo/raw/main/Hito-0.6.0-linux-x64.zip) |

Funciona sin internet y tus datos se quedan en tu equipo.

## Cómo instalarlo

### Windows (instalador)
1. Descarga **Hito-0.6.0-Instalador.exe** y ábrelo.
2. Si aparece *"Windows protegió su PC"*: **Más información → Ejecutar de todas formas** (la app no está firmada con un certificado de pago).
3. Sigue el asistente. No pide permisos de administrador. Al terminar, abre Hito desde el menú Inicio o el escritorio.

### Android
1. Desde el celular, descarga **Hito-0.6.0-android.apk**.
2. Ábrelo. Android te pedirá permitir **"Instalar apps de origen desconocido"** para tu navegador o administrador de archivos: actívalo y vuelve.
3. Toca **Instalar**. Si Google Play Protect muestra un aviso, elige **Instalar de todas formas** (Hito no viene de la Play Store).
4. Las actualizaciones futuras se instalan encima sin perder tus datos.

## Versión portable (sin instalar)

### Windows
1. Descarga el `.zip` y **descomprímelo** (clic derecho → *Extraer todo*). No lo abras desde dentro del `.zip`.
2. Abre la carpeta y haz doble clic en **`Hito.exe`**.
3. Si aparece *"Windows protegió su PC"*: **Más información → Ejecutar de todas formas**. Sale porque la app no está firmada con un certificado de pago.
4. Elige tu idioma, mira el recorrido y listo. Para salir, cierra la ventana.

### Mac
1. Descarga el `.zip` y descomprímelo.
2. Abre **Terminal** en esa carpeta y ejecuta una sola vez:
   ```
   xattr -dr com.apple.quarantine . && chmod +x Hito
   ```
3. Doble clic en **`Hito`**. Se abre mejor si tienes Google Chrome o Microsoft Edge; si no, se abre en tu navegador.

### Linux
```
chmod +x Hito && ./Hito
```

## Antes de empezar
- La primera vez eliges **idioma** (español o inglés) y ves un **recorrido** por las funciones. Ambos se cambian o se repiten en **Ajustes**.
- Verás **datos de ejemplo** para explorar. Bórralos en **Ajustes → Empezar de nuevo**.
- Tus datos se guardan en la carpeta `datos`, junto al programa. Para llevártelos, copia la carpeta completa o usa **Ajustes → Descargar respaldo**.
- Atajo útil: **Ctrl + K** (o ⌘ + K) para buscar lo que sea.
- **¿Usas Google Calendar?** En **Ajustes → Agendas conectadas** toca **Conectar** e inicia sesión una vez: tus eventos aparecen en Hito y lo que hagas en Hito llega a Google. Hito habla directo con Google desde tu equipo ([política de privacidad](https://miguelhuerta-dev.github.io/hitodemo/privacidad/)).

¿Algo no abre? Manda el archivo `datos/hito.log`; ahí queda escrito qué pasó.

---

<h2 id="english">English</h2>

It works offline, and your data stays on your device. Download the file for your system from the tables above.

### Windows (installer)
1. Download **Hito-0.6.0-Instalador.exe** and open it.
2. If you see *"Windows protected your PC"*, click **More info → Run anyway** (the app isn't signed with a paid certificate).
3. Follow the setup wizard. No administrator rights needed. When it's done, open Hito from the Start menu or your desktop.

### Android
1. On your phone, download **Hito-0.6.0-android.apk**.
2. Open it. Android will ask you to allow **"Install unknown apps"** for your browser or file manager: turn it on and go back.
3. Tap **Install**. If Google Play Protect shows a warning, choose **Install anyway** (Hito doesn't come from the Play Store).
4. Future updates install on top without losing your data.

### Portable (no install)

### Windows
1. Download the `.zip` and **extract it** (right-click → *Extract All*). Don't run it from inside the `.zip`.
2. Open the folder and double-click **`Hito.exe`**.
3. If you see *"Windows protected your PC"*, click **More info → Run anyway**. It appears because the app isn't signed with a paid certificate.
4. Choose your language, take the quick tour, and you're all set. To quit, just close the window.

### Mac
1. Download the `.zip` and extract it.
2. Open **Terminal** in that folder and run this once:
   ```
   xattr -dr com.apple.quarantine . && chmod +x Hito
   ```
3. Double-click **`Hito`**. It works best with Google Chrome or Microsoft Edge installed; otherwise it opens in your browser.

### Linux
```
chmod +x Hito && ./Hito
```

### Before you start
- The first time, you'll choose a **language** (English or Spanish) and see a short **tour** of the features. You can change either one in **Settings**.
- You'll see **sample data** to explore. Clear it in **Settings → Start over**.
- Your data is saved in the `datos` folder next to the app. To take it with you, copy the whole folder or use **Settings → Download backup**.
- Handy shortcut: **Ctrl + K** (or ⌘ + K) to search for anything.
- **Use Google Calendar?** In **Settings → Connected calendars**, tap **Connect** and sign in once: your events show up in Hito and what you do in Hito reaches Google. Hito talks to Google directly from your device ([privacy policy](https://miguelhuerta-dev.github.io/hitodemo/privacidad/)).

Something won't open? Send the `datos/hito.log` file; it records what happened.

---

<p align="center"><a href="https://miguelhuerta-dev.github.io/hitodemo/privacidad/">Aviso de privacidad · Privacy notice</a> · <a href="https://miguelhuerta-dev.github.io/hitodemo/terminos/">Términos de uso · Terms of use</a></p>

<p align="center">Designed by <strong>Miguel Huerta</strong> · <a href="https://github.com/miguelhuerta-dev">@miguelhuerta-dev</a></p>
