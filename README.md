# proyectoGenexusGMarr
Aplicación para un Club Deportivo  con los siguientes requerimientos:
Se tienen tipos de socios (por ejemplo, cadete, activo, vitalicio, pero pueden haber más), de los cuales se almacena un identificador, una descripción y el valor de
la cuota. Ningún dato puede quedar vacío.
Se tiene un registro de socios, de los cuales se almacena un identificador, nombre, apellido, cédula, foto, teléfono, email, tipo de socio y fecha de ingreso.
Los datos de nombre, apellido, cédula y tipo de socio no pueden quedar vacíos. La fecha de ingreso se ingresa automáticamente con la fecha actual y no se puede
modificar
e tiene un registro de profesores, de los cuales se almacena un identificador, nombre, apellido, cédula, foto, teléfono y email.
Los datos de nombre, apellido y cédula no pueden quedar vacíos.
•   Se registran disciplinas, de las cuales se almacena un identificador, nombre, el profesor encargado y el profesor ayudante.
Ningún dato puede quedar vacío.
Una disciplina tiene sólo un encargado y un ayudante y un profesor puede ser encargado o ayudante de varias disciplinas. El profesor encargado y ayudante de
una disciplina no puede ser el mismo.    A su vez se registran actividades, de las cuales se quiere almacenar un  identificador, fecha, hora, a que disciplina corresponde, comentarios y quienes son los profesores supervisores. Salvo los comentarios, ningún otro dato puede quedar vacío. No se pueden registrar
actividades para una fecha/hora pasada.
Cada actividad puede tener uno o varios profesores supervisores, pero debe tener al
menos uno.
Se quiere registrar la asistencia de los socios a las actividades. Se almacena los datos del socio, la actividad a la que se anotó y un campo que indica si
efectivamente asistió o no a la misma. No se puede anotar un socio a una actividad de una fecha/hora pasada.
