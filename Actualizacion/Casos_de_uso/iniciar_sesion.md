### **Iniciar sesion**

**ID:** 0014 <br>
**Breve descripción:** Un profesor inicia su sesión en el sistema.

**Actores principales:** Profesor <br>
**Actores secundarios:** Alumno

**Precondiciones:**

+ Debe existir una cuenta a la que loguear<br>
+ La contraseña debe coincidir con la de la base de datos.<br>

**Flujo principal:**

1. El usuario clica en el boton de iniciar sesión.
2. El usuario escribe su cuenta y su contraseña.
3. El usuario pulsa el boton de iniciar sesión.

**Postcondiciones:**

+ El usuario obtiene acceso al sistema

**Flujos alternativos:**

2.a. Si no existe la cuenta, se muestra un mensaje de error.
2.b. Si la contraseña no coincide, se muestra un mensaje de error.
