### **Guardar copia de seguridad**

**ID:** 0010 <br>
**Breve descripción:** Guarda una copia de seguridad de la base de datos del programa.

**Actores principales:** Coordinador <br>
**Actores secundarios:** Alumno

**Precondiciones:**

+ Debe existir una base de de datos que copiar.
+ La acción la debe activar un coordinador y no cualquier profesor.

**Flujo principal:**

1. El caso de uso comienza cuando el sistema necesite crear una copia de seguridad de la bd que haya sido pedido mediante la interfaz del programa.
2. Crea un archivo de copia de la base de datos en un lugar diferente al de la base de datos que usa el programa directamente.

**Postcondiciones:**

+ La localización es elegida por el coordinador.

**Flujos alternativos:**

1.a. Si la base de datos está vacía, muestra un mensaje que de error, "No hay nada que copiar".<br>
2.a. Si la localización definida por el profesor no existe, lanza un mensaje de error.<br>
