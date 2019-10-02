## Sistema de subastas en tiempo real

base de datos:
>SQL

Descripcion del modelo de Datos

>Cada subasta tiene precio establecido por el ofertante, fecha de inicio, fecha final,

>id_producto, tipo de subasta, precio del ganador, usuario ganador, tipo de subasta.

>Los usuarios tienen nombre. apellido, correo, nombre de usuario, clave de usuario, rol.

>La clase rol describe el rol que tiene cada usuario

>Cada producto pertenece a una categoria y una marca

>Se subastan productos en diferentes tipos de subastas y por pujas

>Cada puja tiene precio, fecha, hora, subasta, ofertantes.

>los ofertantes tienen nombre, apellido, direccion, grado de instruccion, estado civil
  sexo, fecha de nacimiento, nombre de usuario, cable de usuario, correo, tipo de oferta 
  y tiṕo de ofertantes.

priorización de Requerimientos

Requisitos específicos
>El sistema debe de asegurar que los usurios se registran con el formulario de forma segura
 y puedan ingresar con su nombre de usuario y clave de usuario (Login)

>Los usuarios pueden ser ofertantes, el sistema debe registrar los productos a ofertar 
  con sus respectivas caracteristicas.
  
>Dinero se representa como puja


Requisitos de rendimiento (no funcionales) 
>El sistema de debe de actualizar en tiempo real para que no exista cruces.

>El sistema debe priorizar resguardar la seguridad de cada usuario.

>El sistema debe seguir con grandes cantidades de usuarios activos.
