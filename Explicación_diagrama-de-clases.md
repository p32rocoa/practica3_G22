## Diagrama de clases

#### Existen cuatro clases diferentes en el diagrama:

- **Persona:**<br>
Engloba a las clases *Alumno* y *Profesor*. Además contiene la información básica de cada persona.

- **Alumno:**<br>
Es una especialización de la clase *Persona* y representa a un alumno de la asignatura.

- **Profesores:**<br>
Es una especialización de la clase *Persona* y representa a los profesores de la asignatura y, a su vez, a los usuarios de la aplicación.

- **Agenda:**<br>
Esta clase representa a la lista de alumnos que será gestionada por la aplicación.

---

#### Algunas aclaraciones:

- La relación entre *Alumno* y *Agenda* se trata de una agregación (en lugar de una composición), debido a que se ha determinado que la lista de alumnos podría estar vacía.

- Al no formar parte de la interfaz del usuario de forma directa, algunas funciones internas (como las funciones de búsqueda) se han establecido como invisibles.
