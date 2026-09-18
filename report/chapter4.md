# Capítulo IV: Product Design
## 4.1. Style Guidelines

Las Style Guidelines de Motus establecen los lineamientos visuales y de comunicación que orientarán el diseño de la landing page y de la aplicación web. Estos lineamientos permiten mantener una identidad visual consistente y facilitar una experiencia clara para los dos principales tipos de usuario: los encargados de flota y los conductores de carga ligera.

La propuesta visual de Motus busca transmitir confianza, prevención, control y agilidad. Por ello, se adopta un estilo moderno y predominantemente claro, evitando interfaces excesivamente oscuras o sobrecargadas y priorizando la rápida comprensión de la información relacionada con vehículos, mantenimientos, alertas e incidencias.

### 4.1.1. General Style Guidelines

#### Branding

Motus es la solución digital desarrollada por Telemtrix para facilitar la gestión y el mantenimiento preventivo de flotas de carga ligera. Su identidad visual busca representar movimiento, prevención y control, manteniendo una apariencia moderna, tecnológica y accesible.

El logotipo de Motus constituye el principal identificador visual del producto. Su diseño integra el concepto de movimiento mediante la representación de una carretera dentro de la letra inicial de la marca, relacionando directamente la identidad del producto con la operación continua de los vehículos.

<p align="center">
  <img src="images/chapter04/Motus-Logo.png" alt="Motus Logo" width="600">
</p>

El logotipo debe mantener sus proporciones originales y contar con suficiente espacio libre a su alrededor para conservar su legibilidad. Se priorizará su utilización sobre fondos blancos o de tonalidades claras.

#### Color Palette

La paleta de colores de Motus combina principalmente tonalidades azules y verdes con fondos claros. El azul representa confianza, estabilidad y control, mientras que el verde se relaciona con movimiento, disponibilidad y prevención. Adicionalmente, se incorporan colores de estado que permiten comunicar visualmente advertencias e incidencias dentro de la plataforma.

La siguiente paleta presenta los colores establecidos para la identidad visual de Motus:

<p align="center">
  <img src="images/chapter04/Motus-Color-Palette.png" alt="Motus Color Palette" width="700">
</p>

| Color | Código HEX | Aplicación |
|---|---|---|
| Azul Motus | `#1E4D6B` | Identidad de marca, títulos y navegación |
| Verde Motus | `#27A67A` | Acciones principales y estados positivos |
| Verde claro | `#E8F6F1` | Fondos destacados y elementos secundarios |
| Ámbar | `#F4A62A` | Advertencias y mantenimientos próximos |
| Rojo | `#E05252` | Fallas, incidencias y estados críticos |
| Gris claro | `#F5F8FA` | Fondos secundarios |
| Gris oscuro | `#263238` | Texto principal |
| Blanco | `#FFFFFF` | Fondo principal y tarjetas |

Los colores de estado mantienen un significado consistente dentro de Motus: el verde identifica condiciones normales o vehículos disponibles, el ámbar señala situaciones que requieren atención, como mantenimientos próximos, y el rojo se reserva para incidencias, mantenimientos vencidos o estados críticos.

#### Typography

Motus utiliza **Inter** como tipografía principal debido a su legibilidad, simplicidad y adecuada visualización en interfaces digitales. Su uso permite mantener una experiencia consistente tanto en la landing page como en la aplicación web responsiva.

La siguiente referencia visual establece la familia tipográfica y las principales jerarquías utilizadas por Motus:

<p align="center">
  <img src="images/chapter04/Motus-Typography.png" alt="Motus Typography" width="700">
</p>

La jerarquía tipográfica se establece de la siguiente manera:

- **Inter Bold (700):** títulos principales y encabezados de mayor jerarquía.
- **Inter SemiBold (600):** subtítulos y elementos destacados.
- **Inter Medium (500):** botones, etiquetas y elementos de navegación.
- **Inter Regular (400):** párrafos, descripciones y contenido general.

El tamaño y peso de los textos deberán mantener una jerarquía visual clara, facilitando la lectura y evitando la saturación de información.

#### Spacing and Visual Elements

Motus utiliza un sistema de espaciado basado en múltiplos de 8 px, permitiendo mantener una distribución consistente entre textos, botones, tarjetas y demás componentes de la interfaz.

Los elementos visuales mantienen formas simples, bordes ligeramente redondeados y espacios en blanco suficientes para separar adecuadamente la información. Las tarjetas y contenedores presentan una apariencia limpia, evitando sombras excesivas o elementos decorativos que puedan distraer al usuario.

La iconografía será sencilla y fácilmente reconocible, utilizando representaciones relacionadas con vehículos, mantenimiento, kilometraje, combustible, alertas, fotografías y listas de verificación.

#### Communication Tone

La comunicación de Motus será clara, directa y profesional. Debido a que la plataforma será utilizada durante actividades operativas, los mensajes deberán ser breves y fáciles de comprender, evitando términos técnicos innecesarios.

El tono de comunicación de Motus se caracteriza por ser:

- **Serio antes que divertido**, debido al contexto de mantenimiento y operación vehicular.
- **Cercano antes que excesivamente formal**, utilizando instrucciones sencillas y comprensibles.
- **Respetuoso**, especialmente en mensajes de error y advertencias.
- **Calmado antes que alarmista**, comunicando claramente las incidencias y las acciones recomendadas.

Por ejemplo, ante un mantenimiento vencido se priorizará un mensaje como *“El mantenimiento de frenos está vencido. Programa una revisión para mantener el vehículo disponible”*, evitando mensajes excesivamente alarmistas o difíciles de interpretar.

#### Design Principles

El diseño de Motus se desarrolla considerando los siguientes principios:

- **Claridad:** La información relevante debe poder identificarse rápidamente, evitando interfaces sobrecargadas.
- **Consistencia:** Los colores, componentes, iconos y estados deben conservar el mismo significado en toda la plataforma.
- **Prevención:** La interfaz debe destacar información que permita anticipar mantenimientos y posibles incidencias.
- **Accesibilidad:** Los elementos deben utilizar textos legibles, contraste adecuado y etiquetas comprensibles.
- **Eficiencia:** Las acciones frecuentes, como registrar kilometraje, completar un checklist o reportar una incidencia, deben realizarse mediante flujos simples y con la menor cantidad posible de pasos.
### 4.1.2. Web Style Guidelines

Las Web Style Guidelines de Motus establecen los criterios visuales y de interacción que se aplicarán tanto en la landing page como en la aplicación web responsiva. Su objetivo es mantener una experiencia consistente, intuitiva y adaptable a diferentes tamaños de pantalla.

La interfaz seguirá un enfoque predominantemente claro y minimalista, utilizando espacios en blanco, jerarquías visuales definidas y componentes fácilmente reconocibles. Debido a que Motus será utilizado tanto por encargados de flota desde computadoras como por conductores desde dispositivos móviles, se priorizará un diseño responsive y una navegación sencilla.

#### Navigation

La navegación utilizará una estructura simple y fácilmente reconocible. En la landing page se empleará una barra de navegación horizontal en escritorio, mientras que en dispositivos móviles se adaptará a un menú compacto.

El logotipo de Motus se ubicará en la parte izquierda de la navegación y los principales accesos se distribuirán de manera ordenada, destacando visualmente las acciones principales mediante el color Verde Motus.

#### Buttons

Los botones tendrán un diseño simple, bordes ligeramente redondeados y textos breves que indiquen claramente la acción que realizará el usuario.

Se utilizarán tres variantes principales:

- **Primary Button:** fondo Verde Motus (#27A67A) y texto blanco. Se utilizará para acciones principales.
- **Secondary Button:** fondo blanco, borde Azul Motus (#1E4D6B) y texto del mismo color.
- **Destructive Button:** color rojo (#E05252) para acciones que requieran especial atención, como eliminar o cancelar determinados registros.

Los botones deberán presentar cambios visuales en estados como *hover*, *focus* y *disabled*, permitiendo que el usuario identifique fácilmente si un elemento es interactivo.

#### Cards and Containers

Las tarjetas se utilizarán para organizar información relacionada con vehículos, mantenimientos, incidencias, alertas y otros elementos relevantes del sistema.

Estas utilizarán fondos blancos, bordes suaves, esquinas ligeramente redondeadas y sombras discretas. La información más importante deberá ocupar una posición visual destacada, evitando incorporar contenido innecesario dentro de una misma tarjeta.

#### Forms and Inputs

Los formularios mantendrán una estructura sencilla y ordenada. Cada campo contará con una etiqueta visible que indique claramente la información requerida.

Los campos de entrada utilizarán fondos claros, bordes definidos y estados visuales diferenciados para indicar selección, error o deshabilitación. Los mensajes de validación serán breves y explicarán al usuario cómo corregir la información ingresada.

En dispositivos móviles, los campos y controles tendrán dimensiones adecuadas para facilitar la interacción táctil.

#### Alerts and Status

Las alertas y estados utilizarán tanto colores como textos e iconos para comunicar su significado, evitando depender exclusivamente del color.

- **Verde:** vehículo disponible o condición normal.
- **Ámbar:** mantenimiento próximo o situación que requiere atención.
- **Rojo:** incidencia crítica, mantenimiento vencido o vehículo inoperativo.

Las alertas deberán presentar información breve y, cuando corresponda, indicar claramente la acción que puede realizar el usuario.

#### Icons

La iconografía mantendrá un estilo simple y consistente. Se utilizarán iconos reconocibles para representar acciones y conceptos como vehículos, mantenimiento, kilometraje, combustible, checklist, fotografías, notificaciones e incidencias.

Siempre que sea necesario, los iconos estarán acompañados por etiquetas de texto para evitar ambigüedades.

#### Responsive Design

La interfaz de Motus seguirá un enfoque responsive que permita su correcta utilización en computadoras, tablets y dispositivos móviles.

En pantallas pequeñas, los componentes se reorganizarán verticalmente, la navegación se simplificará y las acciones principales mantendrán un tamaño adecuado para la interacción táctil.

Se priorizarán especialmente los flujos utilizados por los conductores, como el registro del odómetro, la realización del checklist pre-viaje y el reporte de incidencias, buscando reducir la cantidad de pasos necesarios para completar estas acciones.
