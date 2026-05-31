# Simulador de Cargas Eléctricas

## Breve descripción del proyecto
Este proyecto es un simulador web interactivo de física electromagnetica diseñado para visualizar y analizar las interacciones entre cargas eléctricas puntuales. La herramienta permite trabajar en entornos de una (1D) y dos dimensiones (2D), aplicando la Ley de Coulomb.
A traves de una interfaz gráfica intuitiva, se dan distintas opciones:
- Agregar cargas positivas o negativas especificando su magnitud y posicion.
- Observar en tiempo real los vectores de fuerza neta y calculsr su magnitud.
- Visualizar el campo electrico y sus lineas de campo.
- Realizar mediciones del campo electrico en puntos especificos del espacio.
- Revisar el desglose analitico y dimensional de las fórmulas usadas.

Es una excelente herramienta de apoyo visual y matemático para la resolución y comprension de ejercicios de electromagnetismo.

## Instrucciones de instalación
El simulador es una aplicacion *Single Page Application* (SPA) completamente estatica. Toda su estructura, lógica matemática y estilos estan contenidos dentro del mismo archivo fuente (.html). Fue elegido por su facilidad de uso ya que, **no requiere instalación previa**.

No es necesario configurar servidores locales, entornos virtuales, ni instalar dependencias.

## Instrucciones de ejecución
Estos son los paso que debe seguir para utulizar el prgrama:

1. Guarda el codigo fuente en tu equipo local asegurandote de que el archivo tenga la extensión `.html` (por ejemplo, `simulador.html`).
2. Haz doble clic sobre el archivo guardado para abrirlo con tu navegador web predeterminado.( 
3. Alternativamente, puedes arrastrar y soltar el archivo directamente sobre una pestaña vacía de tu navegador.

*Nota: Se recomienda utilizar versiones actualizadas de navegadores como Google Chrome, Mozilla Firefox, Microsoft Edge o Safari para un rendimiento óptimo del renderizado en el elemento Canvas.*

## Librerías utilizadas
Este proyecto está construido íntegramente con tecnologías web nativas, priorizando la ligereza y la compatibilidad. **No utiliza librerías ni frameworks externos de JavaScript** (como React, Vue, o motores de física como Matter.js).

Las tecnologías y recursos empleados son:
- **HTML5:** Para la estructura de la aplicación y el elemento `<canvas>`.
- **CSS3:** Para los estilos, utilizando variables nativas y *Grid/Flexbox* para la maquetación.
- **Vanilla JavaScript:** Para toda la lógica de cálculo de fuerzas (Ley de Coulomb), interacciones del usuario y renderizado de gráficos en el canvas.
- **Google Fonts (vía CDN):**
  - *Sora:* Utilizada para la tipografía principal de la interfaz.
  - *JetBrains Mono:* Tipografía monoespaciada utilizada específicamente para mostrar coordenadas, fórmulas matemáticas y resultados numéricos, garantizando una lectura técnica clara.
