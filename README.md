# EnterWAS
Enterprise Web Application Service

## Descripcion General
Aplicacion web destinada a empresas y los clientes de esta, incluyendo funcionalidades tanto para todo el público como para clientes
y empleados.

## Funcionalidades

### Pública
- Pantalla de comunicación, con un "media feed" con información interesante de proyectos o novedades en la empresa
- Articulos detallados al interactuar con cada noticia de la pantalla de comunicación.
- Registro a clientes nuevos, el registro debe ser confirmado por la empresa en base a lo rellenado en formulario.

### Privada
- Cliente:
  1. Los clientes pueden acceder mediante una ventana rellenando su usuario y la contraseña que le han otorgado posteriormente al registro.
  2. Al iniciar sesion, se le mostrara un indice con las solicitudes realizadas, el estado de estas y el manager asignado. Tambien podra acceder a su configuración personal y a una pestaña de solicitudes.
  3. En la ventana de configuración, el cliente podra cambiar sus datos de contacto, su contraseña y cualquier observacion mas.
  4. En la pestaña de solicitudes, se presentara un formulario a rellenar por el cliente y se le presentara un indice con los servicios.

- Empleado.Trabajador:
  1. Los empleados pueden acceder mediante una ventana rellenando su usuario y la contraseña que le ha otorgado la empresa.
  2. Al iniciar sesión, se les mostrara una pestaña con actualidad de sus compañeros, indice con los proyectos asignados, una pestaña de horarios donde recopilar sus horas trabajadas, una pestaña de contacto con su manager, una pestaña al correo empresarial y una pestaña donde acceder a su configuracion personal.
  3. La ventana de configuracion le permitira cambiar valores personales, su foto y sus datos de contacto entre otros.
  4. Al interactuar con cualquiera de las pestañas de actualidad, se le mostrara una informacion mas completa y la posibiliadad de comentar al respecto.
  5. Pulsando en cualquiera de los proyectos se le proporcionará informacion sobre este, manager al cargo, contacto con el cliente y direccion en la que encontrar todo lo referente a este.
  6. En la pestaña horarios, le aparecera un timesheet con sus horas confirmadas en un calendario, y un calendario para rellenar con sus horas trabajadas este mes. 
  7. Al utilizar la pestaña de contacto con Manager, este le redigira a un correo nuevo pero con la direccion ya cuplimentada con su respectivo manager.
  8. Al utilizar la pestaña de correo, este le redigira al cliente de correo y al correo corporativo.

- Empleado.Manager:
  1. Todas las funcionalidades son similares al Empleado.Trabajador, a excepción de la pestaña Manager (que pasa a ser sustituida por trabajadores asignados) y una nueva pestaña con solicitudes.
  2. En la pestaña trabajadores, se le mostrara un indice con sus trabajadores asignados(datos personales), los timesheet de estos y el contacto(similar a la funcionalidad de contacto con manager).
  3. Al pulsar en los timesheet, estos se muestran y el manager debe aceptarlos.
  4. En la pestaña solicitudes, el manager revisa el formulario, les asigna unos trabajadores y se asigna a si mismo como manager. Cada manager puede llevar 2 proyectos máximo.

## Entidades

## Equipo de Desarrollo
