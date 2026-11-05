**Idiomas:** [Español](./README.es.md) · [English](./README.md) · [简体中文](./README.zh-CN.md) · [日本語](./README.ja.md) · [Français](./README.fr.md)

# OutlineSave — ChatGPT Outline, Search & Export to HTML & PDF (edición comunitaria)

OutlineSave es una extensión de navegador que facilita la navegación, búsqueda, anotación y exportación de conversaciones largas con IA. Convierte los chats en contenido estructurado que puedes consultar y conservar sin tener que desplazarte interminablemente por el historial.

Este repositorio contiene una **demostración inicial de ChatGPT, con funciones limitadas y código fuente consultable**. No incluye el código de la extensión comercial actual ni representa su versión más reciente. La versión completa de OutlineSave se distribuye por separado en Chrome Web Store.

**[Instalar OutlineSave desde Chrome Web Store](https://chromewebstore.google.com/detail/opbngifmlnoahbhjhgmngkggedlofddj)** · **[Probar la demostración interactiva de HTML](https://wisteriasoftware.uk/demo)** · **[Ver el producto](https://wisteriasoftware.uk/outline-pro)**

![Demostración de ChatGPT Outline, edición comunitaria](./jump-ezgif.com-crop.gif)

> **Limitación de la edición comunitaria:** solo se puede saltar a los primeros 15 elementos del índice. La búsqueda, las anotaciones, la exportación y las demás funciones descritas más abajo pertenecen a la extensión completa de OutlineSave, que se instala por separado.

## Qué incluye la demostración comunitaria

- Índice navegable para conversaciones de ChatGPT
- Actualización automática del índice a medida que crece la conversación
- Posibilidad de colocar la barra lateral a la izquierda o a la derecha
- Demostración básica de la navegación por conversaciones

El límite de 15 elementos navegables se aplica **únicamente a esta demostración**, no a la versión completa de OutlineSave.

## Descubre la extensión completa de OutlineSave

La versión completa permite trabajar con conversaciones de **ChatGPT, Gemini, Claude y DeepSeek**. Las funciones y los controles pueden variar según la plataforma de IA.

### ChatGPT Outline: navegación por un índice de dos niveles

Las preguntas del usuario forman el primer nivel y los encabezados de las respuestas de IA, el segundo. Puedes buscar títulos en el índice y saltar a la sección correspondiente sin recorrer manualmente todos los mensajes.

En conversaciones muy largas de ChatGPT, el índice puede cargarse de forma progresiva. El tiempo de carga y la cobertura dependen de la plataforma y del contenido de la conversación.

### Search: encuentra lo que necesitas

Busca las preguntas y los encabezados de respuesta en el índice de la conversación activa. Tras exportar el chat a HTML, también puedes buscar palabras y fragmentos en el texto completo guardado.

### Export to HTML: guarda una página de conocimiento sin conexión

Exporta la conversación a un archivo HTML autónomo y adaptable a distintas pantallas. Ábrelo en tu equipo sin volver a ChatGPT ni esperar a que se cargue el historial original.

El archivo HTML puede conservar:

- El índice y la navegación por la conversación
- Búsqueda de texto completo
- Resaltados, subrayados, notas y marcadores existentes
- Filtros por marcadores y por color de resaltado
- Bloques de código, fórmulas matemáticas y diagramas Mermaid

**[Probar la demostración interactiva del HTML exportado](https://wisteriasoftware.uk/demo)**

### Exportación PDF

La exportación a PDF **está en desarrollo y todavía no forma parte de la versión publicada en Chrome Web Store** en la fecha de esta actualización. Consulta la [ficha de Chrome Web Store](https://chromewebstore.google.com/detail/opbngifmlnoahbhjhgmngkggedlofddj) para conocer las funciones disponibles.

### Resaltados, notas, marcadores, Markdown y JSON

La versión completa permite resaltar texto con cuatro colores, subrayar, añadir notas y guardar secciones importantes mediante marcadores. También ofrece exportación en Markdown y JSON.

### Procesamiento local de las conversaciones

OutlineSave procesa por defecto el contenido de las conversaciones localmente y no envía su texto a los servidores de Wisteria Software. No exige crear una cuenta de OutlineSave. Algunos datos de activación y funcionamiento pueden tratarse para las licencias y la operación del producto. Las copias opcionales en Google Drive las inicia el usuario y se guardan en su propia cuenta. Consulta la [Política de privacidad](https://wisteriasoftware.uk/privacy).

### Opcional: organizar el contenido con Inbox Local

[Inbox Local](https://github.com/sunny314woo/wisteria-suite/tree/main/apps/inbox-local) es una aplicación independiente para organizar de forma local contenido Markdown y HTML enriquecido exportado desde OutlineSave. No forma parte de esta demostración comunitaria.

## Comparación: demostración comunitaria y OutlineSave completo

| Función | Demostración de este repositorio | OutlineSave completo |
|---|---|---|
| Índice de conversaciones de ChatGPT | Sí | Sí |
| Navegación al hacer clic | Solo los primeros 15 elementos | Índice completo |
| Índice de dos niveles | No | Sí |
| Búsqueda de títulos del índice | No | Sí |
| Búsqueda de texto completo en HTML exportado | No | Sí |
| Resaltados, subrayados, notas y marcadores | No | Sí |
| Exportación HTML sin conexión | No | Sí |
| Exportación Markdown y JSON | No | Sí |
| Compatibilidad con Gemini, Claude y DeepSeek | No | Sí |
| Exportación PDF | No | En desarrollo; consultar la tienda |

## Preguntas frecuentes

### ¿Cómo añado un índice a una conversación larga de ChatGPT?

Instala la versión completa de OutlineSave desde [Chrome Web Store](https://chromewebstore.google.com/detail/opbngifmlnoahbhjhgmngkggedlofddj). La demostración de este repositorio solo permite navegar a 15 elementos.

### ¿Puedo buscar dentro de una conversación de ChatGPT?

La extensión completa permite buscar los títulos del índice en la conversación activa. Después de exportar a HTML, también puedes buscar dentro del texto completo guardado.

### ¿Puedo exportar ChatGPT a un archivo HTML sin conexión?

Sí. La extensión completa genera un HTML autónomo y adaptable, con índice, búsqueda y las anotaciones existentes compatibles. Puedes abrirlo localmente sin cargar ChatGPT.

### ¿OutlineSave sube mis conversaciones a sus servidores?

El texto se procesa localmente de forma predeterminada y no se envía a los servidores de Wisteria Software. Las copias opcionales y los servicios operativos tienen sus propios flujos de datos; consulta la [Política de privacidad](https://wisteriasoftware.uk/privacy).

### ¿OutlineSave es gratis?

Dispone de funciones gratuitas, así como opciones de prueba y de pago. Los límites de exportación y las condiciones de las licencias pueden cambiar; consulta la [página oficial del producto](https://wisteriasoftware.uk/outline-pro).

### ¿Puedo leer el HTML exportado en el móvil?

Sí. Puedes transferir el archivo HTML adaptable a un teléfono y abrirlo en un navegador compatible sin cargar la conversación original de ChatGPT.

## Ejecutar la demostración comunitaria localmente

1. Abre **chrome://extensions** en Chrome.
2. Activa el **modo de desarrollador**.
3. Selecciona **Cargar descomprimida**.
4. Elige la carpeta de este repositorio.

## Licencia y disponibilidad del código

Este repositorio es una **demostración comunitaria con código fuente consultable**, distribuida bajo la licencia personalizada [LICENSE](./LICENSE), **no bajo MIT ni Apache-2.0**. Acceder a este código no concede derechos sobre la extensión comercial, la marca, los servicios de servidor ni otros recursos propietarios. Consulta [NOTICE](./NOTICE).

**[Instalar OutlineSave desde Chrome Web Store](https://chromewebstore.google.com/detail/opbngifmlnoahbhjhgmngkggedlofddj)** · **[Probar la demostración interactiva de HTML](https://wisteriasoftware.uk/demo)**

**Idiomas:** [Español](./README.es.md) · [English](./README.md) · [简体中文](./README.zh-CN.md) · [日本語](./README.ja.md) · [Français](./README.fr.md)
