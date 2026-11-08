<p align="center"><img src="icono.png" width="96" alt=""></p>

<h1 align="center">hito.</h1>
<p align="center">Tu agenda, tus marcadores, tu entrenamiento y tus finanzas en una sola línea de tiempo.<br>
Funciona sin internet y tus datos se quedan en tu computadora.</p>

## Descargar

| Sistema | Descarga |
|---|---|
| **Windows 10 / 11** | [Hito-0.2.0-win-x64.zip](https://github.com/miguelhuerta-dev/hitodemo/raw/main/Hito-0.2.0-win-x64.zip) |
| **Mac con chip M1, M2, M3 o M4** | [Hito-0.2.0-osx-arm64.zip](https://github.com/miguelhuerta-dev/hitodemo/raw/main/Hito-0.2.0-osx-arm64.zip) |
| **Mac con Intel** | [Hito-0.2.0-osx-x64.zip](https://github.com/miguelhuerta-dev/hitodemo/raw/main/Hito-0.2.0-osx-x64.zip) |
| **Linux** | [Hito-0.2.0-linux-x64.zip](https://github.com/miguelhuerta-dev/hitodemo/raw/main/Hito-0.2.0-linux-x64.zip) |

No hay que instalar nada.

## Cómo abrirlo

### Windows
1. Descarga el `.zip` y **descomprímelo** (clic derecho → *Extraer todo*). No lo abras desde dentro del `.zip`.
2. Abre la carpeta y haz doble clic en **`Hito.exe`**.
3. Si aparece *"Windows protegió su PC"*: **Más información → Ejecutar de todas formas**. Sale porque la app no está firmada con un certificado de pago.
4. Hito se abre en su propia ventana. Para salir, solo ciérrala.

### Mac
1. Descarga el `.zip` y descomprímelo.
2. Abre **Terminal** en esa carpeta y ejecuta una sola vez:
   ```
   xattr -dr com.apple.quarantine . && chmod +x Hito
   ```
3. Doble clic en **`Hito`**. Se abre mejor si tienes Google Chrome o Microsoft Edge instalado; si no, se abre en tu navegador.

### Linux
```
chmod +x Hito && ./Hito
```

## Antes de empezar
- La primera vez verás **datos de ejemplo** para explorar. Bórralos en **Ajustes → Empezar de nuevo**.
- Tus datos se guardan en la carpeta `datos`, junto al programa. Para llevártelos, copia la carpeta completa o usa **Ajustes → Descargar respaldo**.
- Hito solo funciona en tu equipo: no se conecta a internet ni envía nada.
- Atajo útil: **Ctrl + K** (o ⌘ + K) para buscar lo que sea.

¿Algo no abre? Manda el archivo `datos/hito.log`; ahí queda escrito qué pasó.

---

<p align="center">Designed by <strong>Miguel Huerta</strong> · <a href="https://github.com/miguelhuerta-dev">@miguelhuerta-dev</a></p>
