### **Cargar BD**

**ID:** 009 <br>
**Breve descripción:** Carga la base de datos del programa.

**Actores principales:** Profesor <br>
**Actores secundarios:** Alumno

**Precondiciones:**

+ Debe existir una base de de datos que cargar.

**Flujo principal:**

1. El caso de uso comienza cuando el sistema necesite cargar el archivo de la base de datos porque se le está pidiendo mediante interfaz.

**Postcondiciones:**

+ Los datos se cargan en el programa y son accesibles por el usuario.

**Flujos alternativos:**

1.a. Si no existe fichero de carga de base de datos, el programa lanza un error.<br>
1.b. Si el archivo está corrupto, el programa lanza un error.<br>
