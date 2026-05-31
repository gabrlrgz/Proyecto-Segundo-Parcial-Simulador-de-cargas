![logo](https://github.com/gabrlrgz/Proyecto-Segundo-Parcial-Simulador-de-cargas/blob/main/logo.png)
# Simulador de Cargas Eléctricas

## descripcion del proyecto
Este proyecto es un simulador web interactivo de física electromagnetica diseñado para visualizar y analizar las interacciones entre cargas electricas puntuales. La herramienta permite trabajar en entornos de una (1D) y dos dimensiones (2D), aplicando la Ley de Coulomb.
A traves de una interfaz gráfica intuitiva, se dan distintas opciones:
- Agregar cargas positivas o negativas especificando su magnitud y posicion.
- Observar en tiempo real los vectores de fuerza neta y calculsr su magnitud.
- Visualizar el campo electrico y sus lineas de campo.
- Realizar mediciones del campo electrico en puntos especificos del espacio.
- Revisar el desglose analitico y dimensional de las fórmulas usadas.

Es una excelente herramienta de apoyo visual y matemático para la resolución y comprension de ejercicios de electromagnetismo.

## Instrucciones de instalacion
El simulador es una aplicacion *Single Page Application* (SPA) completamente estatica. Toda su estructura, logica matematica y estilos estan contenidos dentro del mismo archivo fuente (.html). Fue elegido por su facilidad de uso ya que, **no requiere instalaciones previas**.

No es necesario configurar servidores locales, entornos virtuales, ni instalar dependencias.

## Instrucciones de ejecucion
Estos son los paso que debe seguir para utulizar el programa:

1. Guarda el codigo fuente en tu equipo local (su dispositivo) asegurandote de que el archivo tenga la extension `.html`.
2. Haz doble clic sobre el archivo guardado para abrirlo con tu navegador web predeterminado.(si se abre su IDE, de click derecho y seleccione `abrir con` y seleccione su navegador)
3. tambien se puede arrastrar y soltar el archivo directamente sobre una pestaña vacia de tu navegador.

*Nota: Se recomienda utilizar versiones actualizadas de navegadores como Google Chrome, Mozilla Firefox, Microsoft Edge para un rendimiento optimo del renderizado en el elemento Canvas.*

## Librerias utilizadas
Este proyecto esta construido íntegramente con tecnologías web nativas, priorizando la ligereza y la compatibilidad. **No utiliza librerías ni frameworks externos de JavaScript**.

Las tecnologias y recursos empleados son:
- **HTML5:** Para la estructura de la aplicacion y el elemento `<canvas>`.
- **CSS3:** Para los estilos, utilizando variables nativas y *Grid/Flexbox* para la maquetacion.
- **Vanilla JavaScript:** Para todos los calculos de fuerzas (Ley de Coulomb), interacciones con el prgrama y renderizado de graficos en el canvas.
- **Google Fonts (vía CDN):**
  - *Sora:* Utilizada para la tipografioa  de la interfaz.
  - *JetBrains Mono:* Tipografia monoespaciada utilizada especificamente para mostrar coordenadas, formulas matematicas y resultados numericos.
