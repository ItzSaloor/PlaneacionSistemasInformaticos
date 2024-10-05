# Planeación Sistemas Informáticos

**Líder:** Gabriela Palmezano

## Misión
Un software que pueda ser integrado a gafas de realidad aumentada el cual permita traducir lenguaje de señas a un lenguaje escrito, que será mostrado como subtítulos en el visor de las gafas o como audio, leído por una voz sintetizada.

## Visión
Se busca lograr una mejor comunicación entre las personas que hacen uso de lenguaje de señas y quienes no saben el lenguaje.

---

## Descripción del Proyecto

### Desarrollo
Se va a desarrollar el software, el cual puede ser integrado a gafas que actualmente están en producción o en dispositivos móviles inteligentes que tengan cámara. Las funciones serán detectar los movimientos de una persona en tiempo real y traducirlos al idioma seleccionado. Por ahora, se enfocará en traducir el lenguaje de señas en español al lenguaje escrito en español.

---

## Riesgos

1. **Precisión del reconocimiento**: Variaciones en las señas y condiciones de uso (como iluminación o ángulo).
2. **Privacidad y seguridad**: Protección de los datos y las imágenes capturadas.
3. **Accesibilidad**: Que el software sea fácil de usar por todos.
4. **Exclusión de variantes**: Considerar la diversidad de lenguas de señas.
5. **Sesgo algorítmico**: Evitar que el software funcione mejor para algunos grupos que para otros.
6. **Integración con traductores comunes**: Retos técnicos al traducir entre lenguas de señas y orales.

---

## Recursos Necesarios

### Recursos Tecnológicos

- **Hardware**: Gafas AR, cámaras de alta resolución, sensores de movimiento, y GPU para procesamiento en tiempo real.
- **Software**: Modelos de reconocimiento de gestos basados en IA, una base de datos del lenguaje de señas español, algoritmos de conversión de texto a voz y una interfaz de usuario optimizada.
- **Infraestructura**: Servidores en la nube para procesar datos y redes para la transmisión en tiempo real.

### Recursos Humanos

- **Desarrolladores**: Especialistas en visión por computadora, IA, programación AR/VR y gestión en la nube.
- **Expertos en lenguaje de señas**: Intérpretes y lingüistas para crear la base de datos de gestos.
- **Diseñadores**: Para crear una interfaz accesible y fácil de usar.

---

## Análisis de Requerimientos

### A. Objetivo
Desarrollar un software capaz de traducir lenguaje de señas a texto o audio en tiempo real, utilizando gafas de realidad aumentada o dispositivos móviles con cámara. El objetivo es mejorar la comunicación entre personas sordas que utilizan lenguaje de señas y aquellas que no lo conocen, mediante subtítulos en el visor de las gafas o una voz sintetizada.

### B. Documentación

#### Requisitos Funcionales:

1. **Detección de señas en tiempo real**:
    - El sistema debe reconocer y procesar los movimientos de las manos para identificar las señas.
    - El reconocimiento debe funcionar con una cámara integrada en gafas AR o en dispositivos móviles inteligentes.

2. **Traducción a lenguaje escrito**:
    - Las señas detectadas deben ser traducidas a texto en el idioma español, que será desplegado en forma de subtítulos en las gafas o en la pantalla del dispositivo móvil.

3. **Traducción a audio**:
    - El texto generado debe ser convertido en audio mediante un sintetizador de voz, permitiendo la opción de escuchar la traducción en tiempo real.

4. **Selección de idioma de salida**:
    - El usuario debe poder seleccionar el idioma de salida (por ahora español) en el que se realizará la traducción.

5. **Interfaz de usuario**:
    - La aplicación debe contar con una interfaz accesible que permita ajustar configuraciones como idioma, velocidad de subtítulos, y volumen de la voz sintetizada.

#### Requisitos No Funcionales:

1. **Rendimiento**:
    - El sistema debe funcionar en tiempo real, con una latencia mínima entre la detección de señas y la generación de texto o audio.

2. **Seguridad y privacidad**:
    - Las imágenes y los datos capturados deben ser procesados de manera segura, cumpliendo con las normativas de protección de datos.
    - No se debe almacenar ninguna imagen o dato personal sin el consentimiento del usuario.

3. **Escalabilidad**:
    - El software debe ser capaz de procesar un volumen alto de información cuando sea usado en múltiples dispositivos simultáneamente, empleando servidores en la nube para el procesamiento si es necesario.

4. **Compatibilidad**:
    - El sistema debe ser compatible con las gafas AR disponibles en el mercado, así como con dispositivos móviles inteligentes que cuenten con cámaras de alta resolución.

5. **Precisión**:
    - El sistema debe tener una alta precisión en el reconocimiento de señas, minimizando errores causados por variaciones en el ángulo, iluminación o gestos individuales.

6. **Facilidad de uso**:
    - El software debe ser intuitivo y fácil de usar por cualquier persona, incluyendo usuarios que no tengan conocimientos técnicos.
