# Requerimientos de Rutinas de Buena Salud

## Alcance

Aplicación para organizar y dar seguimiento a rutinas, hidratación, ejercicio, alimentación, descanso y bienestar personal.

## Organización

Se documentan 35 historias de usuario. Cada historia incluye el rol, la necesidad, el beneficio y criterios de aceptación verificables. La etiqueta `historia-usuario` permite distinguirlas de las tareas técnicas.

Repositorio: https://github.com/Lamayonesa/Proyecto-Salud

Tablero: https://github.com/users/Lamayonesa/projects/2

## Índice de historias

- [#6 Historia - Iniciar Sesion](https://github.com/Lamayonesa/Proyecto-Salud/issues/6)
- [#7 Historia - Recuperar Contraseña](https://github.com/Lamayonesa/Proyecto-Salud/issues/7)
- [#8 Historia - Registrarme](https://github.com/Lamayonesa/Proyecto-Salud/issues/8)
- [#9 Historia - Cerrar Sesion](https://github.com/Lamayonesa/Proyecto-Salud/issues/9)
- [#10 Historia - Editar mi perfil](https://github.com/Lamayonesa/Proyecto-Salud/issues/10)
- [#11 Historia - Guardar mis rutinas](https://github.com/Lamayonesa/Proyecto-Salud/issues/11)
- [#12 Historia - Consultar mis rutinas](https://github.com/Lamayonesa/Proyecto-Salud/issues/12)
- [#13 Historia - Editar una rutina guardada](https://github.com/Lamayonesa/Proyecto-Salud/issues/13)
- [#14 Historia - Eliminar una rutina](https://github.com/Lamayonesa/Proyecto-Salud/issues/14)
- [#15 Historia - Programar los días de una rutina](https://github.com/Lamayonesa/Proyecto-Salud/issues/15)
- [#16 Historia - Consultar mi agenda diaria](https://github.com/Lamayonesa/Proyecto-Salud/issues/16)
- [#17 Historia - Marcar una actividad como completada](https://github.com/Lamayonesa/Proyecto-Salud/issues/17)
- [#18 Historia - Corregir una actividad marcada por error](https://github.com/Lamayonesa/Proyecto-Salud/issues/18)
- [#19 Historia - Ver el progreso de una rutina](https://github.com/Lamayonesa/Proyecto-Salud/issues/19)
- [#20 Historia - Consultar mi historial de actividades](https://github.com/Lamayonesa/Proyecto-Salud/issues/20)
- [#21 Historia - Definir una meta personal de hábitos](https://github.com/Lamayonesa/Proyecto-Salud/issues/21)
- [#22 Historia - Registrar mi consumo de agua](https://github.com/Lamayonesa/Proyecto-Salud/issues/22)
- [#23 Historia - Corregir un registro de agua](https://github.com/Lamayonesa/Proyecto-Salud/issues/23)
- [#24 Historia - Establecer mi meta diaria de agua](https://github.com/Lamayonesa/Proyecto-Salud/issues/24)
- [#25 Historia - Consultar mi historial de hidratación](https://github.com/Lamayonesa/Proyecto-Salud/issues/25)
- [#26 Historia - Registrar una sesión de ejercicio](https://github.com/Lamayonesa/Proyecto-Salud/issues/26)
- [#27 Historia - Consultar y corregir mis sesiones de ejercicio](https://github.com/Lamayonesa/Proyecto-Salud/issues/27)
- [#28 Historia - Explorar un catálogo de actividades saludables](https://github.com/Lamayonesa/Proyecto-Salud/issues/28)
- [#29 Historia - Guardar actividades favoritas](https://github.com/Lamayonesa/Proyecto-Salud/issues/29)
- [#30 Historia - Registrar mis comidas](https://github.com/Lamayonesa/Proyecto-Salud/issues/30)
- [#31 Historia - Editar o eliminar una comida registrada](https://github.com/Lamayonesa/Proyecto-Salud/issues/31)
- [#32 Historia - Consultar mi diario de alimentación](https://github.com/Lamayonesa/Proyecto-Salud/issues/32)
- [#33 Historia - Registrar mi período de descanso](https://github.com/Lamayonesa/Proyecto-Salud/issues/33)
- [#34 Historia - Corregir mis registros de descanso](https://github.com/Lamayonesa/Proyecto-Salud/issues/34)
- [#35 Historia - Consultar mi historial de descanso](https://github.com/Lamayonesa/Proyecto-Salud/issues/35)
- [#36 Historia - Registrar mi estado de ánimo](https://github.com/Lamayonesa/Proyecto-Salud/issues/36)
- [#37 Historia - Realizar una pausa de respiración](https://github.com/Lamayonesa/Proyecto-Salud/issues/37)
- [#38 Historia - Configurar recordatorios de mis hábitos](https://github.com/Lamayonesa/Proyecto-Salud/issues/38)
- [#39 Historia - Consultar mi resumen semanal](https://github.com/Lamayonesa/Proyecto-Salud/issues/39)
- [#40 Historia - Exportar mi seguimiento de hábitos](https://github.com/Lamayonesa/Proyecto-Salud/issues/40)

## Historias y criterios de aceptación

### Requerimiento #6

Issue: https://github.com/Lamayonesa/Proyecto-Salud/issues/6

## Iniciar sesión

**Como** usuario registrado,  
**quiero** iniciar sesión con mi correo electrónico y contraseña,  
**para** volver a acceder a mi cuenta.

### Criterios de aceptación

- El sistema debe mostrar un formulario con los campos **Correo electrónico** y **Contraseña**.
- El usuario debe completar ambos campos para iniciar sesión.
- El sistema debe comprobar que el correo electrónico y la contraseña correspondan a una cuenta registrada.
- Si las credenciales son correctas, el sistema debe permitir el acceso a la cuenta.
- Si las credenciales son incorrectas, el sistema debe denegar el acceso y mostrar el mensaje «Correo electrónico o contraseña incorrectos».

---

### Requerimiento #7

Issue: https://github.com/Lamayonesa/Proyecto-Salud/issues/7

## Recuperar contraseña

**Como** usuario registrado,  
**quiero** restablecer mi contraseña si la olvido,  
**para** recuperar el acceso a mi cuenta.

### Criterios de aceptación

- La pantalla de inicio de sesión debe mostrar la opción **¿Olvidaste tu contraseña?**
- Al seleccionar esa opción, el sistema debe mostrar un formulario para ingresar el correo electrónico.
- Si el correo corresponde a una cuenta registrada, el sistema debe enviar un enlace de restablecimiento. En todos los casos, debe mostrar el mensaje **Si el correo está registrado, recibirás un enlace para restablecer tu contraseña**.
- Si el enlace es válido, el sistema debe mostrar un formulario para ingresar y confirmar la nueva contraseña.
- El sistema debe guardar la nueva contraseña solo si ambos campos coinciden y se cumplen los requisitos de seguridad.
- Si el enlace caducó o ya fue utilizado, el sistema debe informar al usuario y permitirle solicitar otro.
- Una vez restablecida la contraseña, el usuario debe poder iniciar sesión con la nueva contraseña.

---

### Requerimiento #8

Issue: https://github.com/Lamayonesa/Proyecto-Salud/issues/8

## Registrarse en el sistema

**Como** visitante del sistema,  
**quiero** crear una cuenta con mi correo electrónico y una contraseña,  
**para** iniciar sesión y acceder a las funciones del sistema.

### Criterios de aceptación

- La pantalla de inicio de sesión debe mostrar la opción **Crear cuenta**.
- Al seleccionar esa opción, el sistema debe mostrar un formulario con los campos **Nombre**, **Correo electrónico**, **Contraseña** y **Confirmar contraseña**.
- El sistema debe validar que todos los campos estén completos, que el correo tenga un formato válido y que la contraseña cumpla los requisitos de seguridad.
- Si las contraseñas no coinciden, el sistema debe mostrar un mensaje y permitir que el usuario las corrija.
- Si el correo ya está registrado, el sistema debe impedir la creación de una cuenta duplicada.
- Si los datos son válidos, el sistema debe crear la cuenta, confirmar el registro y permitir que el usuario inicie sesión con sus credenciales.

---

### Requerimiento #9

Issue: https://github.com/Lamayonesa/Proyecto-Salud/issues/9

## Cerrar sesión

**Como** usuario del sistema,  
**quiero** contar con un botón para cerrar sesión,  
**para** salir de mi cuenta de forma segura.

### Criterios de aceptación

- El sistema debe mostrar el botón **Cerrar sesión** cuando el usuario tenga una sesión activa.
- El usuario debe hacer clic en **Cerrar sesión** para salir de su cuenta.
- Al pulsar el botón, el sistema debe verificar que la sesión esté activa y finalizarla.

---

### Requerimiento #10

Issue: https://github.com/Lamayonesa/Proyecto-Salud/issues/10

## Editar mi perfil

**Como** usuario con una sesión activa,  
**quiero** editar la información de mi perfil,  
**para** mantener mis datos actualizados.

### Criterios de aceptación

- El sistema debe mostrar la opción **Editar perfil** en la sección **Mi perfil**.
- Al seleccionar esa opción, el sistema debe mostrar un formulario con el nombre actual del usuario.
- El usuario debe poder modificar su nombre y elegir **Guardar cambios** o **Cancelar**.
- Si el nombre está vacío, el sistema debe mostrar un mensaje y permitir que el usuario lo corrija.
- Si los datos son válidos, el sistema debe guardar los cambios, mostrar una confirmación y actualizar la información del perfil.
- Si el usuario selecciona **Cancelar**, el sistema debe volver al perfil sin guardar los cambios.

---

### Requerimiento #11

Issue: https://github.com/Lamayonesa/Proyecto-Salud/issues/11

## Guardar mis rutinas

**Como** usuario registrado,  
**quiero** guardar mis rutinas de salud,  
**para** consultarlas cuando las necesite y dar continuidad a mis hábitos.

### Criterios de aceptación

- El sistema debe mostrar la opción **Nueva rutina** en la sección **Mis rutinas**.
- El formulario debe permitir ingresar el nombre de la rutina, las actividades que la componen y la frecuencia con la que se realizará.
- Para guardar una rutina, el usuario debe ingresar un nombre y al menos una actividad. Si falta alguno de esos datos, el sistema debe indicarle qué debe completar.
- Al seleccionar **Guardar rutina**, el sistema debe asociarla con la cuenta del usuario, mostrar una confirmación y agregarla a **Mis rutinas**.
- El usuario debe poder consultar sus rutinas guardadas después de cerrar sesión y volver a iniciar sesión.
- Si el usuario selecciona **Cancelar**, el sistema debe regresar a **Mis rutinas** sin guardar la rutina.

---

### Requerimiento #12

Issue: https://github.com/Lamayonesa/Proyecto-Salud/issues/12

## Consultar mis rutinas

**Como** usuario registrado,  
**quiero** ver las rutinas que he guardado,  
**para** elegir la que deseo realizar y revisar sus actividades.

### Criterios de aceptación

- La sección Mis rutinas muestra únicamente las rutinas de la cuenta activa, con nombre, frecuencia y cantidad de actividades.
- Al seleccionar una rutina se muestran su nombre, actividades y frecuencia completa.
- Si no existen rutinas se muestra un estado vacío con acceso a Nueva rutina.
- Las rutinas guardadas siguen disponibles después de cerrar y volver a abrir la aplicación.

---

### Requerimiento #13

Issue: https://github.com/Lamayonesa/Proyecto-Salud/issues/13

## Editar una rutina guardada

**Como** usuario registrado,  
**quiero** modificar el contenido de una rutina existente,  
**para** adaptarla a mis horarios y hábitos actuales.

### Criterios de aceptación

- El detalle de una rutina propia ofrece Editar y carga sus datos actuales.
- Se pueden modificar nombre, actividades y frecuencia sin crear una rutina duplicada.
- El nombre y al menos una actividad son obligatorios; los errores se muestran junto al campo correspondiente.
- Guardar actualiza el detalle y el listado; Cancelar conserva los datos anteriores.

---

### Requerimiento #14

Issue: https://github.com/Lamayonesa/Proyecto-Salud/issues/14

## Eliminar una rutina

**Como** usuario registrado,  
**quiero** eliminar una rutina que ya no utilizo,  
**para** mantener organizada mi lista de rutinas.

### Criterios de aceptación

- La opción Eliminar está disponible únicamente para rutinas de la cuenta activa.
- Antes de eliminar se solicita confirmación e identifica el nombre de la rutina.
- Cancelar conserva la rutina; confirmar la elimina del listado y cancela sus recordatorios futuros.
- El historial de actividades ya realizadas se conserva y distingue que la rutina fue eliminada.

---

### Requerimiento #15

Issue: https://github.com/Lamayonesa/Proyecto-Salud/issues/15

## Programar los días de una rutina

**Como** usuario registrado,  
**quiero** seleccionar los días de la semana en que realizaré una rutina,  
**para** organizar mis actividades según mi disponibilidad.

### Criterios de aceptación

- Cada rutina permite seleccionar uno o varios días de lunes a domingo.
- Se exige al menos un día y se muestra un mensaje si no se selecciona ninguno.
- Los días elegidos se guardan y aparecen en el detalle de la rutina.
- La agenda muestra la rutina en los días programados, sin duplicarla si se guarda más de una vez.

---

### Requerimiento #16

Issue: https://github.com/Lamayonesa/Proyecto-Salud/issues/16

## Consultar mi agenda diaria

**Como** usuario registrado,  
**quiero** ver las actividades programadas para un día,  
**para** saber qué hábitos tengo pendientes.

### Criterios de aceptación

- La agenda abre en la fecha actual y permite consultar otra fecha.
- Muestra las actividades de las rutinas programadas para ese día y su estado pendiente o completado.
- Si el día no contiene actividades se indica mediante un mensaje claro.
- Al completar una actividad, su estado se actualiza en la agenda sin recargar la sesión.

---

### Requerimiento #17

Issue: https://github.com/Lamayonesa/Proyecto-Salud/issues/17

## Marcar una actividad como completada

**Como** usuario registrado,  
**quiero** registrar que realicé una actividad de mi rutina,  
**para** llevar un seguimiento de mi cumplimiento diario.

### Criterios de aceptación

- Cada actividad pendiente de una rutina programada ofrece la acción Completar.
- La acción guarda la actividad, la rutina, la fecha y la hora de realización para la cuenta activa.
- Marcar dos veces la misma actividad del mismo día no genera registros duplicados.
- La agenda y el progreso de la rutina reflejan el cambio, que se conserva tras reiniciar la aplicación.

---

### Requerimiento #18

Issue: https://github.com/Lamayonesa/Proyecto-Salud/issues/18

## Corregir una actividad marcada por error

**Como** usuario registrado,  
**quiero** desmarcar una actividad que registré accidentalmente,  
**para** mantener un historial de cumplimiento correcto.

### Criterios de aceptación

- Las actividades completadas permiten la acción Marcar como pendiente.
- Se solicita confirmar la corrección antes de cambiar el registro.
- Al confirmar se actualizan el estado y el progreso correspondiente a esa fecha.
- Cancelar no altera el registro y la actividad puede completarse de nuevo sin duplicados.

---

### Requerimiento #19

Issue: https://github.com/Lamayonesa/Proyecto-Salud/issues/19

## Ver el progreso de una rutina

**Como** usuario registrado,  
**quiero** consultar cuánto he completado de una rutina en el día seleccionado,  
**para** identificar las actividades que me faltan.

### Criterios de aceptación

- El detalle muestra actividades completadas y total de actividades programadas para la fecha elegida.
- El porcentaje se calcula como completadas dividido entre programadas por cien.
- Si no hay actividades programadas se muestra Sin actividades, sin dividir entre cero.
- Completar o corregir una actividad actualiza inmediatamente el contador y el porcentaje.

---

### Requerimiento #20

Issue: https://github.com/Lamayonesa/Proyecto-Salud/issues/20

## Consultar mi historial de actividades

**Como** usuario registrado,  
**quiero** revisar las actividades que he realizado en fechas anteriores,  
**para** conocer la continuidad de mis hábitos.

### Criterios de aceptación

- El historial lista fecha, rutina y actividad de los registros de la cuenta activa.
- Se puede filtrar por rango de fechas y por rutina.
- Un rango cuya fecha inicial sea posterior a la final muestra un error y no ejecuta la consulta.
- Si no existen resultados se indica expresamente y no se muestran datos de otras cuentas.

---

### Requerimiento #21

Issue: https://github.com/Lamayonesa/Proyecto-Salud/issues/21

## Definir una meta personal de hábitos

**Como** usuario registrado,  
**quiero** establecer una meta de actividades a completar durante la semana,  
**para** tener un objetivo personal y medir mi avance.

### Criterios de aceptación

- El usuario puede indicar una cantidad semanal de actividades y una fecha de inicio.
- La cantidad debe ser un entero mayor que cero; los valores inválidos muestran errores inline.
- La meta se guarda asociada a la cuenta y se puede consultar durante la semana correspondiente.
- El avance cuenta actividades completadas distintas y no aumenta por registros duplicados.

---

### Requerimiento #22

Issue: https://github.com/Lamayonesa/Proyecto-Salud/issues/22

## Registrar mi consumo de agua

**Como** usuario registrado,  
**quiero** anotar la cantidad de agua que tomo durante el día,  
**para** llevar un seguimiento de mi hidratación.

### Criterios de aceptación

- El formulario permite ingresar una cantidad en mililitros.
- Se rechazan campos vacíos, texto no numérico y cantidades menores o iguales a cero mediante mensajes inline.
- Al guardar se registra la cantidad con fecha y hora, se confirma el éxito y se limpia el campo.
- El total del día se actualiza y los registros se conservan al cerrar y volver a abrir la aplicación.

---

### Requerimiento #23

Issue: https://github.com/Lamayonesa/Proyecto-Salud/issues/23

## Corregir un registro de agua

**Como** usuario registrado,  
**quiero** editar o eliminar un consumo de agua registrado por error,  
**para** mantener correcto mi total diario.

### Criterios de aceptación

- El historial de agua ofrece Editar y Eliminar para los registros de la cuenta activa.
- Editar permite cambiar la cantidad y exige un valor numérico mayor que cero.
- Eliminar requiere confirmación; cancelar conserva el consumo original.
- Toda corrección actualiza el total de la fecha correspondiente y permanece guardada tras reiniciar.

---

### Requerimiento #24

Issue: https://github.com/Lamayonesa/Proyecto-Salud/issues/24

## Establecer mi meta diaria de agua

**Como** usuario registrado,  
**quiero** guardar una meta diaria de consumo elegida por mí,  
**para** compararla con el agua que registro.

### Criterios de aceptación

- La configuración permite introducir una meta personal en mililitros, sin asignar una recomendación médica automática.
- Se exige un valor numérico mayor que cero y se muestran errores inline si no es válido.
- El resumen diario muestra la meta y el consumo acumulado con sus unidades.
- Al superar la meta, el consumo real sigue visible y no se recorta ni se pierde información.

---

### Requerimiento #25

Issue: https://github.com/Lamayonesa/Proyecto-Salud/issues/25

## Consultar mi historial de hidratación

**Como** usuario registrado,  
**quiero** revisar el consumo de agua por fecha,  
**para** observar cómo cambia mi hábito de hidratación.

### Criterios de aceptación

- El historial muestra los consumos individuales y el total de cada día.
- Permite seleccionar una fecha y un rango con inicio no posterior al final.
- Los días sin registros se distinguen de aquellos con consumo registrado.
- Editar o eliminar un consumo actualiza el historial y solo se consultan datos de la cuenta activa.

---

### Requerimiento #26

Issue: https://github.com/Lamayonesa/Proyecto-Salud/issues/26

## Registrar una sesión de ejercicio

**Como** usuario registrado,  
**quiero** anotar una actividad física realizada y su duración,  
**para** llevar control de mis sesiones de ejercicio.

### Criterios de aceptación

- El formulario solicita nombre o tipo de actividad, fecha y duración en minutos.
- La actividad es obligatoria, la duración debe ser numérica y positiva y la fecha no puede ser futura.
- Los errores se muestran debajo de cada campo y bloquean el guardado.
- Guardar confirma el registro, limpia el formulario y añade la sesión al historial de la cuenta.

---

### Requerimiento #27

Issue: https://github.com/Lamayonesa/Proyecto-Salud/issues/27

## Consultar y corregir mis sesiones de ejercicio

**Como** usuario registrado,  
**quiero** revisar y corregir las sesiones de ejercicio que registré,  
**para** conservar un seguimiento fiel a lo que realicé.

### Criterios de aceptación

- El historial presenta actividad, fecha y minutos, con filtro por rango de fechas.
- Se pueden editar actividad, fecha y duración con las mismas validaciones del registro.
- Eliminar una sesión exige confirmación y Cancelar no modifica sus datos.
- Las correcciones actualizan el historial y los minutos acumulados del período.

---

### Requerimiento #28

Issue: https://github.com/Lamayonesa/Proyecto-Salud/issues/28

## Explorar un catálogo de actividades saludables

**Como** usuario registrado,  
**quiero** consultar actividades de ejercicio, descanso y bienestar,  
**para** encontrar ideas que pueda incorporar a mis rutinas.

### Criterios de aceptación

- El catálogo lista actividades con nombre, categoría y descripción breve.
- Se pueden filtrar las actividades por categoría y abrir su detalle.
- Si una categoría no tiene contenido se muestra un mensaje informativo.
- El contenido se presenta como información general de hábitos y no como diagnóstico o tratamiento personalizado.

---

### Requerimiento #29

Issue: https://github.com/Lamayonesa/Proyecto-Salud/issues/29

## Guardar actividades favoritas

**Como** usuario registrado,  
**quiero** marcar actividades del catálogo como favoritas,  
**para** encontrarlas rápidamente cuando organice mis rutinas.

### Criterios de aceptación

- Cada actividad del catálogo permite activar o desactivar su marca de favorita.
- La sección Favoritas muestra solo las actividades marcadas por la cuenta activa.
- Marcar repetidamente la misma actividad no genera duplicados.
- Las favoritas se conservan al reiniciar; si no existen, se ofrece regresar al catálogo.

---

### Requerimiento #30

Issue: https://github.com/Lamayonesa/Proyecto-Salud/issues/30

## Registrar mis comidas

**Como** usuario registrado,  
**quiero** anotar las comidas que realizo durante el día,  
**para** mantener un diario personal de alimentación.

### Criterios de aceptación

- El formulario solicita tipo de comida, descripción, fecha y hora.
- El tipo y la descripción son obligatorios y no se permiten fechas u horas futuras.
- Las validaciones aparecen inline y un formulario inválido no genera registros.
- Guardar añade la comida al diario, muestra confirmación y limpia el formulario sin calcular diagnósticos nutricionales.

---

### Requerimiento #31

Issue: https://github.com/Lamayonesa/Proyecto-Salud/issues/31

## Editar o eliminar una comida registrada

**Como** usuario registrado,  
**quiero** corregir entradas de mi diario de alimentación,  
**para** que mis registros coincidan con las comidas realizadas.

### Criterios de aceptación

- Desde una comida propia se puede abrir Editar con sus valores actuales.
- Los cambios respetan los campos obligatorios y la validación de fecha y hora del registro.
- Eliminar solicita confirmación y Cancelar mantiene la entrada.
- Guardar o eliminar actualiza el diario sin crear duplicados ni modificar comidas de otra cuenta.

---

### Requerimiento #32

Issue: https://github.com/Lamayonesa/Proyecto-Salud/issues/32

## Consultar mi diario de alimentación

**Como** usuario registrado,  
**quiero** ver mis comidas organizadas por día,  
**para** revisar mis hábitos de alimentación.

### Criterios de aceptación

- El diario abre en la fecha actual y permite consultar días anteriores.
- Muestra las comidas en orden horario con tipo y descripción.
- El usuario puede abrir una entrada para consultar sus datos completos.
- Si no hay comidas se muestra un estado vacío con acceso al formulario de registro.

---

### Requerimiento #33

Issue: https://github.com/Lamayonesa/Proyecto-Salud/issues/33

## Registrar mi período de descanso

**Como** usuario registrado,  
**quiero** anotar cuándo me dormí y cuándo desperté,  
**para** llevar un seguimiento de mi tiempo de descanso.

### Criterios de aceptación

- El formulario permite introducir fecha y hora completas de inicio y fin del descanso.
- El fin debe ser posterior al inicio y no puede estar en el futuro; se admiten períodos que cruzan medianoche.
- El sistema calcula la duración entre ambas fechas y muestra errores inline ante valores inválidos.
- Guardar confirma el registro y lo asocia a la cuenta sin emitir diagnósticos sobre la calidad del sueño.

---

### Requerimiento #34

Issue: https://github.com/Lamayonesa/Proyecto-Salud/issues/34

## Corregir mis registros de descanso

**Como** usuario registrado,  
**quiero** modificar o eliminar un período de descanso equivocado,  
**para** mantener precisos mis datos de sueño.

### Criterios de aceptación

- Cada registro propio permite editar sus fechas y horas con los datos actuales precargados.
- La edición exige fin posterior al inicio y fechas no futuras.
- Eliminar solicita confirmación; Cancelar conserva el registro.
- La duración se recalcula y las correcciones actualizan el historial y el resumen del período.

---

### Requerimiento #35

Issue: https://github.com/Lamayonesa/Proyecto-Salud/issues/35

## Consultar mi historial de descanso

**Como** usuario registrado,  
**quiero** revisar la duración de mis períodos de sueño,  
**para** observar la regularidad de mi descanso.

### Criterios de aceptación

- El historial muestra inicio, fin y duración de cada período registrado.
- Permite filtrar por rango de fechas y rechaza rangos invertidos.
- Los períodos que cruzan medianoche mantienen su duración completa y se agrupan por su fecha de finalización.
- Si no hay registros se informa al usuario sin generar valores de sueño ficticios.

---

### Requerimiento #36

Issue: https://github.com/Lamayonesa/Proyecto-Salud/issues/36

## Registrar mi estado de ánimo

**Como** usuario registrado,  
**quiero** anotar cómo me siento durante el día,  
**para** llevar un diario personal de bienestar emocional.

### Criterios de aceptación

- El formulario permite elegir un estado de ánimo y escribir una nota opcional.
- La selección del estado es obligatoria y el registro incorpora fecha y hora.
- Los registros se muestran únicamente para la cuenta activa y no se publican ni comparten automáticamente.
- El historial permite revisar las entradas y aclara que este seguimiento personal no sustituye una evaluación profesional.

---

### Requerimiento #37

Issue: https://github.com/Lamayonesa/Proyecto-Salud/issues/37

## Realizar una pausa de respiración

**Como** usuario registrado,  
**quiero** seguir una pausa breve de respiración con un temporizador,  
**para** dedicar un momento del día a relajarme.

### Criterios de aceptación

- La pantalla ofrece una pausa guiada con duración visible e instrucciones sencillas de respiración cómoda.
- El usuario puede iniciar, pausar, continuar o finalizar la sesión en cualquier momento.
- Al terminar se informa la duración realizada y solo se registra como completada si el usuario lo confirma.
- La actividad no exige retener el aire ni presenta promesas de tratamiento; se puede detener si resulta incómoda.

---

### Requerimiento #38

Issue: https://github.com/Lamayonesa/Proyecto-Salud/issues/38

## Configurar recordatorios de mis hábitos

**Como** usuario registrado,  
**quiero** elegir cuándo recibir recordatorios de mis rutinas,  
**para** recordar las actividades que he programado.

### Criterios de aceptación

- Cada rutina permite activar recordatorios y seleccionar hora y días compatibles con su programación.
- Las notificaciones solo se programan tras la autorización correspondiente del dispositivo; si se deniega, se explica cómo continuar sin ellas.
- Editar o desactivar un recordatorio cancela su programación anterior y evita duplicados.
- Al cerrar sesión se cancelan los recordatorios de esa cuenta para no mostrarlos a otra persona.

---

### Requerimiento #39

Issue: https://github.com/Lamayonesa/Proyecto-Salud/issues/39

## Consultar mi resumen semanal

**Como** usuario registrado,  
**quiero** ver un resumen de mis hábitos durante una semana,  
**para** evaluar mi constancia y decidir qué deseo mejorar.

### Criterios de aceptación

- El usuario puede elegir la semana que desea consultar.
- El resumen muestra actividades completadas, agua registrada, minutos de ejercicio y períodos de descanso disponibles.
- Cada indicador identifica su unidad y los días sin datos; no se interpretan registros ausentes como resultados médicos.
- Corregir un registro actualiza los totales y no se mezclan datos de cuentas diferentes.

---

### Requerimiento #40

Issue: https://github.com/Lamayonesa/Proyecto-Salud/issues/40

## Exportar mi seguimiento de hábitos

**Como** usuario registrado,  
**quiero** descargar un resumen de mis registros en un archivo,  
**para** conservar una copia y revisarla fuera de la aplicación.

### Criterios de aceptación

- El usuario selecciona un rango válido de fechas y las categorías de hábitos que desea exportar.
- Se genera un archivo CSV con encabezados, fechas, unidades y los registros de la cuenta activa que correspondan al filtro.
- Si no existen datos se informa antes de generar el archivo; los errores de exportación no alteran los registros.
- El archivo solo se guarda o comparte mediante una acción explícita del usuario y nunca se envía automáticamente a terceros.

---

