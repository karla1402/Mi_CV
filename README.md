# Mi Curriculum Vitae (CV)

Este repositorio contiene mi Curriculum Vitae profesional en dos formatos complementarios de alta calidad: una **versión web moderna y responsiva** y una **versión clásica y elegante en LaTeX**.

---

## Estructura del Proyecto

- **`index.html`**: El código fuente de la versión web. Cuenta con diseño responsivo y botones interactivos para imprimir o descargar en PDF.
- **`cv.css`**: La hoja de estilos que define el diseño visual de la versión web, adaptado para pantallas móviles y optimizado para impresión física o a PDF (`@media print`).
- **`cv.tex`**: El código fuente en LaTeX de la versión impresa clásica de mi CV. Estructurado con tipografía Helvetica, espaciados perfectos y enlaces funcionales a contacto y redes.

---

## Formatos Disponibles

### 1. Versión Web Interactiva (HTML/CSS)

Una interfaz limpia, minimalista y responsiva que se adapta perfectamente a dispositivos móviles y de escritorio.

- **Descarga Vectorial y Copiable:** Utiliza la función de impresión nativa del navegador para exportar a PDF, garantizando que el texto se mantenga como texto real y seleccionable (ideal para análisis de IA y reclutadores).
- **Optimización de Impresión:** Cuenta con reglas CSS `@media print` específicas que ocultan elementos interactivos (botones) y ajustan márgenes al tamaño carta estándar al imprimir o guardar en PDF.

### 2. Versión Clásica e Impecable (LaTeX)

La versión clásica y formal preferida en la industria tecnológica.

- **Tipografía de Precisión:** Utiliza la tipografía Helvetica (sans-serif) para mantener un estilo limpio, moderno y alineado con mi perfil de diseño UX/UI.
- **Lectura Óptima para ATS:** Diseñado y estructurado para que los sistemas de reclutamiento automatizado (ATS) puedan procesar la información de forma 100% correcta y fluida.
- **Enlaces Activos:** Enlaces interactivos directos a mi correo electrónico y perfil de LinkedIn usando el paquete `hyperref`.

---

## ¿Cómo compilar la versión de LaTeX?

Si deseas compilar el archivo `cv.tex` para generar el PDF:

1.  **En la nube (Recomendado):** Sube el archivo `cv.tex` a [Overleaf.com](https://www.overleaf.com/) (es gratuito y no requiere instalación) y presiona **Recompile**.
2.  **En tu computadora:** Instala una distribución de LaTeX como MiKTeX y ejecuta el comando `pdflatex cv.tex` en tu consola.
