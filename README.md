# Planeación Sistemas Informáticos

**Líder del Proyecto:** Gabriela Palmezano

## Misión
Desarrollar un software integrado en gafas de realidad aumentada que traduzca el lenguaje de señas a texto escrito o audio, presentado como subtítulos en el visor de las gafas o a través de una voz sintetizada.

## Visión
Facilitar la comunicación entre personas que usan lenguaje de señas y aquellos que no lo conocen, promoviendo la inclusión y la accesibilidad en diversas situaciones cotidianas.

---

## Descripción del Proyecto

### Desarrollo
El proyecto consiste en crear un software capaz de integrarse con gafas de realidad aumentada existentes o con dispositivos móviles inteligentes con cámara. Este software detectará y procesará los movimientos de las manos en tiempo real, traduciendo las señas al idioma elegido. La versión inicial se enfocará en traducir lenguaje de señas en español a texto escrito en español.

---

## Riesgos

1. **Precisión del reconocimiento**: Posibles variaciones en las señas y desafíos técnicos derivados de condiciones como iluminación o ángulos de cámara.
2. **Privacidad y seguridad**: Asegurar la protección de los datos e imágenes capturadas, cumpliendo con normativas de privacidad.
3. **Accesibilidad**: Garantizar que el software sea fácil de usar para todo tipo de usuarios, sin importar sus conocimientos técnicos.
4. **Diversidad de lenguas de señas**: Considerar la amplia gama de variantes en el lenguaje de señas.
5. **Sesgo en el reconocimiento**: Evitar que el software tenga un desempeño desigual según los grupos demográficos o condiciones de uso.
6. **Compatibilidad con traductores convencionales**: Retos técnicos al integrar traducciones entre lenguas de señas y lenguas orales.

---

## Recursos Necesarios

### Tecnológicos

- **Hardware**: Gafas de realidad aumentada, cámaras de alta resolución, sensores de movimiento y unidades GPU para el procesamiento en tiempo real.
- **Software**: Modelos de IA para reconocimiento de gestos, base de datos de señas en español, algoritmos para conversión de texto a voz, y una interfaz de usuario accesible.
- **Infraestructura**: Servidores en la nube para el procesamiento de datos y redes de comunicación en tiempo real.

### Humanos

- **Desarrolladores**: Especialistas en visión por computadora, inteligencia artificial, programación en AR/VR y gestión de infraestructura en la nube.
- **Expertos en lenguaje de señas**: Intérpretes y lingüistas para la creación de la base de datos de gestos.
- **Diseñadores UX/UI**: Para diseñar una interfaz amigable y accesible.

---

## Análisis de Requerimientos

### Objetivo
Crear un software que permita traducir lenguaje de señas a texto o audio en tiempo real, usando gafas de realidad aumentada o dispositivos móviles con cámara. El fin es mejorar la comunicación entre personas que utilizan lenguaje de señas y quienes no lo conocen, mostrando subtítulos en las gafas o proporcionando una traducción mediante voz sintetizada.

### Documentación

#### Requisitos Funcionales

1. **Reconocimiento de señas en tiempo real**:
    - El sistema debe detectar y procesar los movimientos de las manos para identificar señas en tiempo real.
    - Compatible con cámaras integradas en gafas AR o dispositivos móviles.

2. **Traducción a texto**:
    - Las señas deben traducirse a texto en español, que se mostrará como subtítulos en las gafas o en la pantalla del dispositivo.

3. **Conversión a audio**:
    - El texto debe poder ser convertido a audio usando un sintetizador de voz, para permitir una traducción hablada en tiempo real.

4. **Selección de idioma de salida**:
    - El usuario podrá elegir el idioma de la traducción (inicialmente disponible solo en español).

5. **Interfaz de usuario**:
    - La aplicación debe ofrecer una interfaz accesible, permitiendo ajustar configuraciones como idioma, velocidad de subtítulos y volumen de la voz sintetizada.

#### Requisitos No Funcionales

1. **Rendimiento**:
    - El sistema debe ofrecer una respuesta en tiempo real con mínima latencia entre la detección de señas y la generación de texto o audio.

2. **Seguridad y privacidad**:
    - Las imágenes y datos deben ser procesados de forma segura, sin almacenarse sin consentimiento del usuario, cumpliendo las normativas de protección de datos.

3. **Escalabilidad**:
    - El sistema debe ser capaz de gestionar múltiples usuarios simultáneamente, utilizando servidores en la nube para el procesamiento si es necesario.

4. **Compatibilidad**:
    - El software debe ser compatible con diferentes modelos de gafas AR y dispositivos móviles con cámaras de alta resolución.

5. **Precisión**:
    - El reconocimiento de señas debe ser preciso, minimizando errores debidos a variaciones en ángulo, iluminación o gestos individuales.

6. **Usabilidad**:
    - La interfaz debe ser intuitiva y fácil de usar, independientemente del nivel técnico del usuario.

---

## Vista Previa de la Interfaz

Puedes explorar una vista previa de la interfaz gráfica del proyecto en el siguiente enlace:

[Ver Interfaz en Figma](https://www.figma.com/design/rg2hDV38r1uxADBCp3hQmp/Figma-basics?node-id=1669-162202&node-type=canvas&t=USGsFJQcRQlk16x4-0)
