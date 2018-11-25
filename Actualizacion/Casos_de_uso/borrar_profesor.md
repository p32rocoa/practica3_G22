### **Borrar profesor**

**ID:** 0013 <br>
**Breve descripción:** Borra una cuenta de profesor en el sistema.

**Actores principales:** Coordinador <br>
**Actores secundarios:** Profesor

**Precondiciones:**

+ Debe existir una cuenta que borrar<br>
+ Solo puede realizarlo un coordinador<br>

**Flujo principal:**

1. El caso de uso comienza cuando se pulsa el boton de administrar cuentas.
2. El usuario elige la cuenta a borrar.
3. El usuario pulsa el boton de borrado.

**Postcondiciones:**

+ La cuenta es eliminada del programa.

**Flujos alternativos:**

2.a. Si el boton de administrar cuentas no lo pulsa el coordiandor, muestra un mensaje de error.
