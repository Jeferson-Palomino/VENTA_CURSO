Base de datos
El nombre de la base de datos es VENTA_CURSO.
Estructura y descripción de tablas
 Esta base de datos estará conformada por las siguientes tablas:
	01) PERSONA: contiene los datos generales de toda persona, además especifica si es estudiante o empleado.
	02) EMPLEADO: contiene la información necesaria del empleado.
	03) DEPARTAMENTO: contiene toda la información de los departamentos en los que trabajan los empleados.
	04) CURSO: contiene toda la información referente a los cursos que se ofertan.
	05) OFERTA: contiene las ofertas de cursos con su respectiva fecha de inicio y profesor. asignado. 
	06) NIVEL_SUELDO: contiene los niveles o grados de sueldo que puede alcanzar el empleado de acuerdo a su productividad.
	07) INSCRIPCION: contiene todas las inscripciones realizadas a los cursos ofertados y que son atendidos por los empleados del departamento de ventas.
	08) HISTORICO: contiene la información histórica de los años trabajados de un empleado dentro de la empresa.
Relaciones entre tablas
  Para establecer las relaciones debe tener en cuenta lo siguiente:
	01. Un empleado puede ser Jefe de ninguno, uno o muchos empleados.
	02. Un departamento está conformado por ninguno, uno o muchos empleados.
	03. En un nivel o grado de sueldo pueden estar comprendidos 0, 1 ó muchos sueldos de los empleados.
	04. Un curso puede estar presente en ninguna, una o muchas ofertas.
	05. Un profesor puede dictar ninguno, uno o más cursos.
	06. Una persona puede estar registrado como empleado ninguna, una o muchas veces.
	07. Un empleado del departamento de ventas puede registrar la inscripción de ninguno, uno o muchos cursos.
	08. Un persona de tipo de estudiante se puede registrar ninguna, una o muchas veces en los cursos.
	09. Una oferta de curso puede estar en 0, 1 o muchas veces inscripciones.
	010. Un empleado puede ser ascendido o irse de la empresa ninguna, una o muchas veces.
