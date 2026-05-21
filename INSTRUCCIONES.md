# Guía de Uso y Compilación de tu CV en LaTeX

¡Felicidades! Ahora tienes tu CV en un formato LaTeX profesional y moderno (`cv.tex`). Al estar en LaTeX, tu CV tendrá una tipografía perfecta, alineación exacta y una presentación sumamente limpia, valorada en la industria de la tecnología.

A continuación, te explicamos cómo puedes ver y compilar tu CV para generar el archivo PDF de dos maneras distintas.

---

## Opción 1: Usando Overleaf (Recomendado - 100% Gratis y sin instalar nada)

**Overleaf** es un editor de LaTeX en la nube. Es la forma más rápida y recomendada si no deseas instalar nada en tu computadora.

### Pasos:
1. **Regístrate o inicia sesión** de forma gratuita en [Overleaf.com](https://www.overleaf.com/).
2. En tu panel principal, haz clic en el botón verde **"New Project"** (Nuevo Proyecto) y selecciona **"Blank Project"** (Proyecto en blanco). Nómbralo como prefieras (por ejemplo, `Mi_CV`).
3. Overleaf creará el proyecto y abrirá un archivo llamado `main.tex` por defecto.
4. Tienes dos opciones para llevar tu CV a Overleaf:
   * **Opción A (Copiar y pegar):** Abre el archivo `cv.tex` en tu editor actual (VS Code, etc.), copia todo su contenido, ve a Overleaf, selecciona todo el contenido de `main.tex`, bórralo y pega tu código allí.
   * **Opción B (Subir archivo):** En la barra lateral izquierda de Overleaf, haz clic en el botón de **"Upload"** (subir archivo) y arrastra tu archivo `cv.tex`. Luego puedes eliminar el archivo `main.tex` vacío que venía por defecto.
5. Haz clic en el botón azul **"Recompile"** (Recompilar) en el panel derecho (o presiona `Ctrl + Enter`).
6. **¡Listo!** Verás la vista previa en PDF de tu CV. Puedes descargarlo haciendo clic en el botón de **"Download PDF"** situado justo al lado del botón Recompile.

---

## Opción 2: Compilación Local en tu Computadora (Windows)

Si prefieres trabajar de manera local directamente desde tu computadora, necesitarás instalar una distribución de LaTeX y un editor.

### Pasos:
1. **Instalar la distribución de LaTeX:**
   * Descarga e instala **MiKTeX** desde [miktex.org/download](https://miktex.org/download). Es la opción más popular y ligera para Windows, ya que descarga automáticamente los paquetes que necesitas sobre la marcha.
   * *Durante la instalación, asegúrate de habilitar la opción de instalar paquetes faltantes automáticamente ("Always install missing packages on-the-fly").*

2. **Elegir un editor de texto:**
   * **VS Code (Recomendado si ya lo usas):**
     1. Abre tu carpeta en VS Code.
     2. Instala la extensión **"LaTeX Workshop"** de James Yu.
     3. Abre tu archivo `cv.tex`.
     4. Al guardar el archivo, la extensión lo compilará automáticamente en segundo plano y generará tu archivo `cv.pdf`.
   * **TeXstudio (Editor clásico e independiente):**
     1. Descarga e instala **TeXstudio** desde [texstudio.org](https://www.texstudio.org/).
     2. Abre tu archivo `cv.tex` con TeXstudio.
     3. Presiona la tecla `F5` (Compilar y Ver) para generar y visualizar tu PDF al instante.

3. **Compilar desde la terminal (Consola):**
   * Una vez instalado MiKTeX, abre PowerShell o CMD en la carpeta de tu repositorio y ejecuta:
     ```powershell
     pdflatex cv.tex
     ```
   * Esto generará el archivo `cv.pdf` directamente en la misma carpeta.

---

## Ventajas de esta versión en LaTeX

* **Cero problemas de impresión:** A diferencia del HTML, LaTeX no depende del navegador ni de la resolución de pantalla. El PDF siempre se verá idéntico y perfecto en cualquier dispositivo o impresora.
* **Separación de contenido y diseño:** Si en el futuro necesitas agregar nueva experiencia, solo modifica el texto dentro de los bloques `\resumeEntry` o `\begin{itemize}` sin preocuparte de que se rompa el diseño o se mueva el contenido.
* **Estándar en la industria:** Los reclutadores y sistemas ATS (sistemas automáticos de filtrado de CVs) leen los PDFs generados por LaTeX de manera sumamente eficiente y precisa.
