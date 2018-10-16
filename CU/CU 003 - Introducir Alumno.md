## ID: 003 Introducir Alumno

**Breve descripción:** El sistema introduce un nuevo alumno en la base de datos.

**Actores principales:** Profesor
**Actores secundarios:** Alumno

**Precondiciones:**

 1. El alumno no debe existir en el sistema.
 2. No puede coincidir el DNI con el de otro alumno.

**Flujo principal:**

 1. El caso de uso empieza cuando el sistema necesita introducir la información de un nuevo alumno.
 2. El sistema comprueba que el alumno no exista.
 3. El sistema recoge los datos del alumno y los introduce en la base de datos.

**Postcondiciones:**

 - El sistema introduce un nuevo alumno.

**Flujos alternativos:**
- 2.a Si el alumno ya existía, el sistema lanzará un mensaje de error.
- 3.a Si el dni del nuevo alumno ya existía, el sistema lanzará un mensaje de error.