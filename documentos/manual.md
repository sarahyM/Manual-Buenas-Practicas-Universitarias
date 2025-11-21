![Logo Universidad](/imagenes/logo.png)
UNIVERSIDAD Valle del Momboy
Facultad de Ingeniería (Computación)
Prof: Edgardo Paolini

<br><br>

# MANUAL DE BUENAS PRÁCTICAS ACADÉMICAS UNIVERSITARIAS

## PROTOCOLOS PARA TRABAJOS UNIVERSITARIOS EN GRUPO

<br><br>

**Elaborado por:**
Sarahy Ocanto


<br>
---

# MANUAL DE BUENAS PRÁCTICAS ACADÉMICAS

## DOCUMENTACIÓN Y CONTROL DE VERSIONES

Este manual es una guía detallada para la creación, organización y presentación de trabajos académicos colaborativos de alta calidad.

---

## I. ORGANIZACIÓN Y GESTIÓN DE TIEMPOS

El éxito de un trabajo en grupo se fundamenta en una planificación rigurosa y la responsabilidad compartida de todos los integrantes.

### 1.1. Estrategia de Desglose de Tareas

La primera fase es descomponer el trabajo en unidades mínimas e independientes.

* **Definición de Hitos:** Establecer las fechas clave de entrega para cada sección (ej: Recopilación de fuentes, Redacción de la Introducción).
* **Sistema Kanban (GitHub Projects):** Cada hito o subsección debe convertirse en un **Issue** en GitHub. Esto permite la trazabilidad y garantiza que no haya tareas olvidadas.

### 1.2. Protocolo de Reuniones y Comunicación (NUEVO)

La comunicación debe ser estructurada para minimizar la pérdida de tiempo.

* **Reuniones Asíncronas:** Utilizar herramientas de mensajería (ej. Slack, Teams) para preguntas rápidas y urgentes, y evitar saturar el correo electrónico.
* **Actas y Acuerdos:** En el trabajo en grupo, un miembro debe redactar un resumen breve de los acuerdos y responsables, guardándolo en el repositorio (`/documentos/actas/`).
* **Uso de Ramas Aisladas (`feature/`):** El medio principal de **comunicación colaborativa** sobre el texto es el Pull Request (PR), donde se revisa el trabajo del compañero antes de fusionarlo a la rama principal.

### 1.3. Estructura de Archivos (NUEVO)

Mantener una estructura clara evita la duplicidad de archivos y la confusión:

* **`/documentos`**: Solo contiene el documento principal (`manual.md`) y borradores finales.
* **`/referencias`**: Almacena documentos fuente clave, PDFs, y el listado consolidado de bibliografía.
* **`/imagenes`**: Contiene todos los gráficos, diagramas o capturas utilizados. No deben mezclarse con archivos de otras carpetas.

---

## II. FORMATO DE INFORME Y PRESENTACIÓN

El manual debe seguir una estructura formal, típicamente requerida en informes académicos.

### 2.1. Estructura Formal del Documento

![Ilustración de estructura](/imagenes/estructura.png)

Un informe completo requiere, además de las secciones de contenido, elementos de contextualización y metadatos:

* **Portada:** Nombre de la universidad, título, autores, asignatura y fecha.
* **Resumen Ejecutivo (Abstract):** Un párrafo conciso (máx. 250 palabras) del objetivo, metodología y principales conclusiones. Se escribe en último lugar.
* **Cuerpo del Documento:** Introducción, Desarrollo (dividido en secciones temáticas), Conclusiones.
* **Apéndices:** Material adicional relevante (actas de reuniones, cuestionarios, etc.).

### 2.2. Guía de Diseño y Estilo

| Elemento | Especificación |
| :--- | :--- |
| **Márgenes** | 2.54 cm (1 pulgada) en todos los lados. |
| **Fuente del Texto** | **Times New Roman** o **Arial**, 12pt. |
| **Interlineado** | Doble espacio (2.0) en todo el cuerpo del texto. |
| **Encabezado y Numeración:** | Usar sangría de media pulgada para la primera línea de cada párrafo. Numeración de página desde el pie de página. |

---

## III. CITACIÓN Y RIGOR ACADÉMICO (Normas APA)

La integridad del informe depende de la correcta atribución de ideas. Se utilizará el **Estilo APA (7ª Edición)**.

### 3.1. Tipos de Cita y Uso de Paráfrasis

La **paráfrasis** (citar la idea de otro con tus propias palabras) debe ser priorizada sobre la cita textual, ya que demuestra mayor asimilación del contenido.

* **Cita Paréntetica:** Se incluye la información al final de la frase: (Autor, Año).
* **Cita Narrativa:** Se incorpora el apellido del autor en la narrativa: Según Martínez (2023),...

### 3.2. Citas Textuales Directas (Mayor detalle)

Solo se usan si el lenguaje es crucial para el argumento (definiciones o leyes).

* **Citas Cortas (menos de 40 palabras):** Se incorporan al texto entre comillas y se incluye siempre el número de página o párrafo. **Ejemplo:** "El control de versiones es clave" (Smith, 2023, p. 55).
* **Citas en Bloque (40 o más palabras):** Se colocan en un bloque aparte, sin comillas, con sangría a 1.27 cm (media pulgada) en todo el bloque.

### 3.3. Formato de Referencias y Listado Final

La lista de referencias debe ser exhaustiva y coherente.

* **Orden Alfabético:** Las fuentes se ordenan estrictamente por el apellido del primer autor.
* **Sangría Francesa:** La primera línea de cada referencia va al margen, y las líneas subsiguientes llevan sangría de 1.27 cm.
* **Ejemplo de Libro (Formato Correcto):**
    Apellido, A. A. (Año). *Título del libro en cursiva*. Editorial.
* **Ejemplo de Fuente Digital sin Fecha:**
    Apellido, A. A. (s.f.). *Título del artículo*. Nombre del Sitio Web. URL.

---