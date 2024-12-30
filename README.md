# Sistema de gestión hotelera
Continuación del [trabajo](https://github.com/schjavier/TP-ProgramacionII) realizado por [@schjavier](https://github.com/schjavier), [@juliganga](https://github.com/juliganga) y [@Tomy52](https://github.com/Tomy52)

La idea de este proyecto es arreglar diversos problemas e incorporar distintas funcionalidades que no pudieron llegar a incorporarse en el original. Es un repositorio experimental, en donde voy a sumar distintas cosas que considere interesantes para el programa.


## Funcionalidades (actuales):

- Menú de inicio de sesión con 2 niveles de usuario
    - Administrador
    - Recepcionista
- Menú para administradores: 
    - Creación de habitaciones de 3 tipos
    - Gestión de habitación por ID
    - Creación de otros usuarios
    - Visualización de empleados en sistema
    - Eliminación de empleado por DNI
    - Posibilidad de hacer backup de todos los datos del sistema a demanda (habitaciones, empleados, pasajeros, reservas)
- Menú para recepcionistas:
    - Gestión de habitaciones por ID
    - Ver listado con todas las habitaciones creadas
    - Ver listado de habitaciones por tipo y estado
    - Ver la cantidad total de habitaciones
    - Ver la cantidad total de habitaciones en un determinado estado
    - Revisar las cocinas de todas las habitaciones que tengan una
    - Revisar los jacuzzis de todas las habitaciones que tengan uno
    - Manejar las reservas de los pasajeros:
        - Crear reservas
        - Eliminar reservas
        - Modificar reservas por ID
        - Ver reservas hechas por un DNI
        - Ver información de los pasajeros en reserva
- Excepciones personalizadas
- 3 tipos de habitación:
    - Standard
    - Suite
    - Presidencial
- Sistema de reservas con chequeo de fechas

## Tareas planificadas:

- Implementar una interfáz gráfica para simplificar el uso del programa
- Mudar la persistencia a una base de datos
