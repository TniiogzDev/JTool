# JTool
Proyecto Web de diferentes herramientas para diferentes departamentos, a continuación explicaré la herramienta disponible hasta ahora:

### Guía de Usuario para el Generador de Horarios 📅

Esta herramienta te ayuda a crear un horario mensual de manera fácil y rápida, asignando personas a diferentes equipos o roles. Sigue estos pasos para generar tu horario:

---

### 1. Copia de Seguridad 💾

Esta sección te permite guardar y cargar tus datos de configuración.

* **Guardar Datos**: Haz clic en este botón para descargar un archivo (`.json`) con toda la información que has ingresado (equipos, miembros, restricciones). Esto es útil para **respaldar tu trabajo** o para **continuar editando** en otro momento.
* **Cargar Datos**: Utiliza este botón para seleccionar y subir un archivo de respaldo previamente guardado. La aplicación se llenará automáticamente con tu configuración anterior.

---

### 2. Definir los Días del Mes 🗓️

Aquí defines la estructura de tu horario.

* **Agregar Día**: Pulsa este botón para añadir una fila. En cada fila, ingresa el **nombre del día** de la semana (ej. "Miércoles") y la **fecha** del mes que le corresponde (ej. "3"). Repite este proceso para todos los días que necesites en tu horario.

---

### 3. Definir tus Equipos 🤝

En esta sección, creas los equipos o roles para los que necesitas generar el horario.

* **Agregar Equipo**: Haz clic para añadir un nuevo equipo.
* **Nombre del Equipo**: Escribe el nombre del equipo o rol (ej. "Audio", "Proyección").
* **Miembros**: En el cuadro de texto, escribe el nombre completo de cada miembro, **uno por línea**.

---

### 4. Restricción de Rotación 🔄

Esta característica evita que ciertas personas sean asignadas a un mismo equipo más de una vez en el mes.

* **Lista de Rotación**: Escribe el nombre de las personas, **uno por línea**, que solo deben ser asignadas una vez por equipo durante el mes. Por ejemplo, si una persona está en la lista y es asignada al "Equipo 1", la herramienta intentará no asignarla de nuevo a ese mismo equipo en el resto del mes.

---

### 5. Restricción de Días 🚫

Aquí puedes especificar los días en los que una persona no está disponible.

* **Agregar Restricción**: Haz clic en este botón para añadir una fila.
* **Nombre Completo**: Escribe el nombre de la persona que tiene restricciones.
* **Días que no puede**: Ingresa los números de los días del mes en los que esa persona no está disponible, separados por comas (ej. "3, 10, 17"). La aplicación se asegurará de no asignarla en esas fechas.

---

### 6. Generar y Exportar Horario ✅

Este es el último paso para ver y guardar tu horario.

* **Título del Horario**: Puedes poner un nombre a tu horario, como "Horario de Julio". Este título aparecerá en la tabla generada.
* **Generar Horario**: Una vez que hayas ingresado todos los datos, haz clic aquí. El horario aparecerá como una tabla debajo de los botones.
* **Exportar a PDF**: Convierte el horario generado en un archivo PDF que puedes imprimir o compartir fácilmente.
* **Exportar a Excel**: Descarga el horario en un archivo de Excel (`.xlsx`) para que puedas editarlo o guardarlo como una hoja de cálculo.


