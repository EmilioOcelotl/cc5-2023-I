![portada](https://github.com/EmilioOcelotl/cc4-ct-2022-2/blob/main/IMG_5776.jpeg)

# Código creativo 5: iluminación interactiva y render en tiempo real

- [x] Sesión 01

  - [Presentación](https://emilioocelotl.github.io/)
  - Acuerdos (cámara, asistencia y entregas)
  - Revisión de temario 
  - Repositorio en github 
  - Presentación y experiencias previas ( Código Creativo )  
    - Touch Designer 
    - ¿Qué es?
    - Lenguajes de programación visual 
    - Licencias e instalación
  
  
- [ ] Sesión 02
  
  - Instalación y licencias 
    - Posibles problemas de controladores > https://forum.derivative.ca/t/solved-2021-38090-win11-vulkan-initialization-failed/232784
  - Programación gráfica ( también es posible usar Python )  
  - Interfaz, timeline, tiempo real/tiempo diferido y duraciones 
  - Controles del mouse ( de preferencia usar un mouse de 3 botones ) 
  - Operadores objeto preprogramado > similitudes y diferencias con respecto a Processing  
  - Si los operadores son más oscuros esto quiere decir que generan imágenes 
  - Morado claro > alteradores de la imagen 
  - Es posible leer errores ( caso de operadores que no tienen entrada ) 
  - Para ver familias de operadores hay que dar TAB
  - Existen las siguientes familias de operadores. Por el momento nos vamos a centrar en TOP  
    - TOP > Texture operator 
       - MovieFileIn 
    - CHOP > Channel operator 
    - SOP > Surface operator 
    - MAT > Materiales 
    - DAT > Datos (manejo) 
    - CUSTOM > Objetos personalizados 
  - Conexión y flujos entre operadores ( izquierda a derecha y de arriba a abajo ) 
  - Parámetros de operadores sencillos como movieFieIn y Blur 
  - Operadores tienen banderas que están abajo.
  - Display muestra el resultado al fondo del programa ( Pueden ser varios ) 
  - Level para mostrar una cadena de procesamiento de imagen, por ejemplo brillo ( puede ser imagen o puede ser otra cosa ) 
  - Opciones para operadores > view   
  - Es posible ahorrar recursos con Viewer para no visualizar los resultados de cada operador 
  - Si da tiempo, hablar de switch y null como contenedor final 
  - Cambio del nombre de los nodos 
  - Operador composite ( blending modes ) y ramp 
  - Aproximaciones sintéticas y concretas  
  - Tile    
  - Animación, casillas y formas de transformar parámetros
  - Expresiones > absTime.seconds
  - ramificaciones, contenedores, entradas y salida (out) 
  - MovieFileOut para grabar
