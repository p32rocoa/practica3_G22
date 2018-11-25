### **Cargar copia de seguridad**

**ID:** 0011 <br>
**Breve descripción:** Carga una copia de seguridad de la base de datos del programa.

**Actores principales:** Coordinador <br>

**Precondiciones:**

+ Debe existir una copia de seguridad que cargar.<br>
+ La acción la debe activar un coordinador y no cualquier profesor.

**Flujo principal:**

1. El caso de uso comienza cuando el sistema necesite cargar una copia de seguridad.
2. Sustituye el archivo de copia de seguridad por el archivo de bd que el programa esté usando en ese momento.

**Postcondiciones:**

+ El nombre de la copia adopta el nombre de la base de datos actual.
+ La base de datos actual es borrada.

**Flujos alternativos:**

1.a. Si la base de datos a cargar está vacía, muestra un mensaje que de error.<br>
2.a. Si la localización proveida no existe oe l fichero no está, lanza un mensaje de error.<br>
