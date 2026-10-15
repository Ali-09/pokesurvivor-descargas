# PokéSurvivor · App de escritorio

Aquí están las versiones de la app de escritorio de PokéSurvivor para Mac y Windows.

- **Beta**: lo último, con cosas nuevas que todavía se están probando. Puede tener fallos.
- **Legacy**: la versión estable.

Puedes tener las dos instaladas a la vez. Cada una guarda su partida por separado. Si entras con tu cuenta, el progreso en la nube es el mismo en las dos.

👉 **[Ver todas las versiones y descargas](../../releases)**

---

## Instalar por primera vez

### Mac (chip Apple: M1, M2, M3…)

1. En [Releases](../../releases), abre la última versión y descarga **`PokeSurvivor-Beta-mac.zip`**.
2. Haz doble clic en el zip para descomprimirlo.
3. **Arrastra `PokeSurvivor-Beta` a la carpeta Aplicaciones.** Si la abres desde Descargas no se podrá actualizar sola.
4. La primera vez, en Aplicaciones, haz **clic derecho sobre la app > Abrir** y luego **Abrir** otra vez. La app no está firmada por Apple, por eso macOS pregunta. Solo se hace una vez.

Si macOS dice que la app "está dañada y no se puede abrir", abre la app Terminal, pega esto y pulsa Intro:

```
xattr -dr com.apple.quarantine /Applications/PokeSurvivor-Beta.app
```

Por ahora no hay versión para Macs con procesador Intel.

### Windows

1. En [Releases](../../releases), descarga **`PokeSurvivor-Beta-windows.zip`**.
2. Haz clic derecho sobre el zip > **Extraer todo…**, y extráelo en tu carpeta de usuario, por ejemplo en `Documentos`. **No lo pongas en "Archivos de programa"**: ahí no se podría actualizar sola.
3. Abre la carpeta `PokeSurvivor-Beta` y haz doble clic en `PokeSurvivor-Beta.exe`.
4. Si Windows muestra "Windows protegió su PC", pulsa **Más información > Ejecutar de todas formas**. Solo pasa la primera vez.

---

## Actualizar

Desde la **v1.5.2**, el juego te avisa solo cuando hay una versión nueva. Aparece un cartel abajo a la derecha en el menú:

1. Pulsa **Actualizar**.
2. Espera a que termine la barra de descarga. El juego se cierra solo, se cambia por la versión nueva y se vuelve a abrir.
3. Tu partida se queda como estaba.

Si en Mac te pregunta si la app puede "modificar otras apps", pulsa **Permitir**. Si pulsas **Luego**, el aviso no vuelve hasta la siguiente versión. También puedes buscar a mano en **Ajustes > Buscar actualizaciones**.

### ¿Tienes la Beta 88 (v1.5.1)?

Esa versión todavía no sabía actualizarse sola: su botón se llamaba "Descargar" y solo abría esta página. **Instala la nueva a mano una sola vez:**

1. Cierra el juego.
2. Descarga la última versión desde [Releases](../../releases).
3. **Mac:** arrastra la nueva `PokeSurvivor-Beta` a Aplicaciones y pulsa **Reemplazar**.
   **Windows:** borra la carpeta `PokeSurvivor-Beta` vieja y extrae la nueva en el mismo sitio.
4. Ábrela. En la esquina de abajo a la derecha debe poner **v1.5.2 · Beta …** o más.

Tu partida no se pierde: está guardada aparte, no dentro de la app. A partir de aquí, todas las actualizaciones son con un clic.

---

## Si algo va mal

- **"No se pudo actualizar"**: el juego se queda en la versión que tenías. Prueba otra vez o instala la nueva a mano siguiendo los pasos de arriba.
- **El aviso dice "Mueve la app a la carpeta Aplicaciones"** (Mac): ciérrala, arrástrala a Aplicaciones y ábrela desde ahí.
- **La partida en grupo dice que tu amigo tiene otra versión**: actualizad los dos a la última.
- **Dónde está la partida guardada**:
  - Mac: `~/Library/Application Support/pokesurvivor-beta/`
  - Windows: `%APPDATA%\pokesurvivor-beta\`
  - En la Legacy es lo mismo, pero en la carpeta `pokesurvivor`.

Este repositorio solo guarda las descargas, no el código del juego.
