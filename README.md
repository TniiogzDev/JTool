# JTool
Proyecto Web de diferentes herramientas para diferentes departamentos. A continuación, se detalla la herramienta disponible hasta ahora.

---

### Guía de Usuario para el Generador de Horarios

Esta herramienta te ayuda a crear un horario mensual de manera fácil y rápida, asignando personas a diferentes equipos o roles. Sigue estos pasos para generar tu horario.

---

### 1. Configuración de Datos

Esta sección te permite gestionar la información principal del horario.

* **Definir los Días del Mes**: Aquí defines la estructura de tu horario. Utiliza el botón **"Agregar Día"** para añadir una fila donde ingresarás el **nombre del día** de la semana (ej. "Miércoles") y la **fecha** correspondiente (ej. "3"). Repite el proceso para todos los días que necesites incluir en el horario.

* **Definir tus Equipos**: En esta parte, creas los equipos o roles para los que necesitas generar el horario. Haz clic en **"Agregar Equipo"** para añadir un nuevo equipo. Escribe el **nombre del equipo** y, en el cuadro de texto, lista a los **miembros**, escribiendo cada nombre en una línea separada.

---

### 2. Gestión de Restricciones

Aquí puedes establecer reglas para la asignación de personas.

* **Restricción de Rotación**: Esta función evita que ciertas personas sean asignadas a un mismo equipo más de una vez en el mes. En el cuadro de texto, ingresa el nombre de las personas, **uno por línea**, que deben ser asignadas solo una vez por equipo durante el mes.

* **Restricción de Días**: Te permite especificar los días en los que una persona no está disponible. Usa el botón **"Agregar Restricción"** para añadir una fila. Escribe el **nombre completo** de la persona y, en el campo correspondiente, ingresa los números de los días del mes en que no puede ser asignada, separados por comas (ej. "3, 10, 17").

---

### 3. Generar y Exportar Horario

Este es el último paso para crear y guardar tu horario.

* **Generar Horario**: Una vez que hayas ingresado todos los datos y restricciones, puedes asignar un **título al horario**. Luego, haz clic en **"Generar Horario"** para que la tabla del horario aparezca en la página.

* **Exportar Horario**: La herramienta ofrece dos opciones para guardar tu trabajo:
    * **Exportar a PDF**: Convierte el horario en un documento PDF para imprimir o compartir fácilmente.
    * **Exportar a Excel**: Descarga el horario como un archivo de Excel (`.xlsx`) para que puedas editarlo en una hoja de cálculo.

---

### 4. Copia de Seguridad

Esta sección te permite guardar y cargar la configuración de tu trabajo para usarla en el futuro.

* **Guardar Datos**: Descarga un archivo (`.json`) con toda la configuración que has ingresado (equipos, miembros, restricciones, días).
* **Cargar Datos**: Carga un archivo de respaldo previamente guardado para restaurar tu configuración.

