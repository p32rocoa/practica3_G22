## Diagramas de secuencia

#### Se pueden distribuir en varios grupos:
<br>

- **Gestión de usuarios:**<br><br>
En este grupo se encuentran:

  + ***Registro:*** Comprueba que no exista un usuario igual al que se quiere registrar, en la base de datos de usuarios. En caso de que no exista, se registrará al profesor con éxito.

  + ***Borrar_profesor:*** Solo en el caso de que ya esté registrado el profesor indicado y siempre que el que realice esta acción sea un coordinador, se procederá al borrado.

  + ***Iniciar_sesión:*** Comprueba que los datos introducidos existan y coincidan. En caso afirmativo, el sistema iniciará sesión con la cuenta de ese profesor.

  + ***Cerrar_sesión:*** Cierra la sesión de la cuenta actual.

<br>
- **Almacenamiento de datos:**<br><br>
En este grupo hay dos diagramas para la base de datos de la agenda y, otros dos diagramas, para la copia de seguridad de dicha base de datos.

  + ***Guardar_BD:*** Guardará los datos del sistema en la base de datos.

  + ***Cargar_BD:*** Los datos de los alumnos serán cargados en el sistema desde la base de datos.

  + ***Guardar_copia:*** Se guardarán los datos del sistema en una base de datos auxiliar, que hace el papel de copia de seguridad.

  + ***Cargar_copia:*** Los datos de los alumnos de la copia de seguridad serán cargados en el sistema.

<br>
- **Observadores de los datos de los alumnos:**<br>
Las acciones que nos permiten observar datos de la agenda están definidas en los siguientes diagramas:

  + ***Mostrar_alumno:*** Busca un alumno que coincida con los datos introducidos. En caso de que ocurra, será mostrado al usuario.

  + ***Mostrar_grupo:*** Busca un grupo que coincida con los datos introducidos. En caso de que ocurra, los miembros del grupo serán mostrados al usuario.

  + ***Listar_alumnos:*** Muestra a cada uno de los alumnos que existan en la agenda.

<br>
- **Modificadores de los datos de los alumnos:**<br>
Los diagramas de las acciones que permiten manipular los datos de los alumnos son los siguientes:

  + ***Insertar_alumno:*** Busca a algún alumno en el que los datos identificadores coincidan con los introducidos. Si ya hay un alumno con esos identificadores no se realizará la inserción. (También se tiene en cuenta que si el alumno a introducir tiene como rol de líder en un grupo que ya tiene líder, tampoco se podrá insertar)

  + ***Modificar_alumno:*** Realiza una búsqueda para confirmar que al alumno que se quiere modificar existe. También se comprueba que los datos nuevos sean posibles de realizar y no incumplan alguna restricción.

  + ***Borrar_alumno:*** Borrará al alumno introducido de la agenda, en caso de que exista.

  + ***Reiniciar_alumnos:*** Borrará toda la lista de alumnos de la agenda y la dejará vacía.
