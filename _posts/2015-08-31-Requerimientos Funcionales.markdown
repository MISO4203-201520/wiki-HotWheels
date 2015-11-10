---
layout: default
title:  "Requerimientos"
date:   2015-08-31 00:00:04
categories: posts
---

# Requerimientos

## Requerimientos existentes

**ER1.** El sistema debe ofrecer a los usuarios la opción de registrar sus datos personales (usuario, password, nombre, correo, rol) para poder crear una nueva cuenta en la plataforma. El sistema debe permitir seleccionar el rol (provider o user) con el que se quiere crear la cuenta . Adicionalmente la plataforma debe pedir al usuario la confirmación de su cuenta de correo antes de poder autenticarse por primera vez.

**ER2.** El sistema debe ofrecer a los usuarios la opción de autenticación, se debe mostrar un formulario que permita ingresar el nombre de usuario y contraseña. El sistema debe permitir recordar esta información para acelerar el ingreso a futuro; una vez el usuario ingrese al sistema, este lo debe redireccionar a la página de inicio dependiendo del rol (provider o user)

**ER3.** El sistema debe ofrecer a los usuarios la posibilidad de consultar el catálogo de vehículos que actualmente ofrece la plataforma. En particular el usuario debe poder visualizar la referencia del vehículo, el precio y el vendedor que lo provee.

**ER4.** El sistema debe ofrecer al usuario la posibilidad de agregar artículos (vehículos) al carrito de compras, una vez finalizado el proceso de selección de artículos el usuario debe poder ver el resumen de su selección para poder confirmar o editar su selección. a su vez el usuario podrá eliminar artículos del mismo.

## Requerimientos por realizar

### Ciclo 1

**R1.** El sistema debe ofrecer al comprador la opción de pagar la compra. Se debe mostrar un formulario para realizar el pago que despliegue el total de la compra y el desglose en impuestos. Suponga que hay un impuesto a las ventas del 16% . Debe estar la posibilidad de seleccionar el tipo de tarjeta crédito/debito con el que se realizará el pago. Cuando el usuario seleccione pagar, el sistema debe guardar la información sobre el pago de forma persistente en la base de datos. (8) DIEGO AGUDELO

**R2.** El sistema debe ofrecer al comprador la posibilidad de agregar comentarios sobre los productos. El comentario va  asociado con un producto específico y es una descripción en texto libre de no más de 255 caracteres. Los comentarios asociados con los productos se deben persistir incluyendo la fecha, el usuario y la descripción.  (3) GUILLERMO FERRO

**R3.** El sistema debe ofrecer al usuario con el rol de administrador el servicio de ver los usuarios registrados en la aplicación y sus roles. Se debe agregar el rol de administrador en Stormpath (el mecanismo de seguridad que está utilizando la aplicación). (3) DAVID JIMENEZ

**R4.** El sistema debe ofrecer al comprador la posibilidad de registrar preguntas sobre un producto de un proveedor específico. La pregunta se debe persistir con el producto al que hace referencia, el usuario, su email, la fecha y la descripción.  Cuando se registre la pregunta al proveedor, al proveedor debe llegarle una notificación por email. (5) HAROLD MURCIA

**R5.**  El sistema debe ofrecer al comprador la posibilidad de realizar una búsqueda sobre el catálogo de productos que retorne el producto más barato de un proveedor dado, o el proveedor que ofrece el producto más barato de un tipo de producto dado. (5)  WILMAR FUQUEN

### Ciclo 2

**R6.** El sistema debe ofrecer al proveedor la posibilidad de agregar un descuento especial a alguno de sus productos. Esta información debe desplegarse en el catálogo. Guillermo 

**R7.** Disponer de una galería virtual de proveedores de carros usados, que admita criterios de clasificación (modelo, marca, ciudad de venta, rango de precios, etc.). Explicación: Se espera que al final del desarrollo la aplicación cuente con filtros avanzados para la busqueda de proveedores. WILMAR FUQUEN

**R8.** Contar con un sistema de búsqueda que permita localizar de manera simple las distintas ofertas. (De acuerdo a lo conversado con el monitor, lo que el cliente necesita en este requerimiento es contar con un sistema de búsqueda avanzado para ubicar productos del catálogo de acuerdo a una serie de criterios (marca, modelo, capacidad de pasajeros, rangos de precios)). David 

**R18.** Registrar/actualizar un producto. Diego.

**R22.** Responder preguntas de usuarios compradores. Harold.

### Ciclo 3
**R09.** El sistema brinda la posibilidad de intercambiar mensajes internos entre proveedores de carros, clientes o ambos. - _Miguel_

**R15.** El sistema debe permitir a cualquier usuario filtrar por cualquier caracteristica del vehículo. Se espera que sea posible filtrar por una o varias carateristicas al momento de buscar un vehiculo a la venta. - _Wilmar_

**R16.** El sistema debe permitir a los usuarios poder consultar el estado de un pedido desde las opciones del usuario, donde deben estar listados todos los pedidos de dicho usuario. Los estados pueden ser Autorizado, Aceptado por el proveedor, Cancelado y Enviado. - _Viviana_

**R23.** El sistema debe permitir a los proveedores actualizar el estado del pedido realizado por un cliente - _Viviana_

#### Cambios incluídos

**R00.** Agregar un vehículo. _Cambio:_ Agregar campos al vehículo: modelo, placa par o impar, ubicación, .... - _Guillermo_
 
 **R1.** El sistema debe ofrecer al comprador la opción de pagar la compra. Se debe mostrar un formulario para realizar el pago que despliegue el total de la compra y el desglose en impuestos. Suponga que hay un impuesto a las ventas del 16% . Debe estar la posibilidad de seleccionar el tipo de tarjeta crédito/debito con el que se realizará el pago. Cuando el usuario seleccione pagar, el sistema debe guardar la información sobre el pago de forma persistente en la base de datos. _Cambio:_ Escoger en el formulario varios medios de pago: tarjeta débito, crédito, PSE y paypal. 
Debe dar feddback al usuario: un mensaje sobre el resultado del pago (simulando que el pago se hizo) - _Diego_

*	Se espera que los dos miembros que realizan cambios trabajen fuertemente sobre la deuda técnica del proyecto o sobre el cubrimiento de pruebas sobre el código.
	
La especificación de cada requerimiento se realizó por medio de mockups. Consulte [AQUÍ](https://docs.google.com/document/d/1CqNNPCR3mAW-G11B1Wwp5hZMXx8fy8lJqjoaQcxuMXk/edit?usp=sharing) el documentos con los mockups del ciclo.

### Ciclo 4

**R10.** El sistema cuenta con un foro de discusión abierto entre los usuarios de la plataforma (cliente y proveedores). Cada mensaje debe ser almacenado y posteriormente consultado por los clientes involucrados. Los foros deben tener un titulo, mensajes y participantes de la conversación.

**R13.** El sistema debe permitir que cada cliente puede visualizar el listado de transacciones realizadas en un periodo de tiempo determinado. _Wilmar_

**R14.** El sistema debe permitir que los clientes puedan calificar el producto que han comprado. La calificación se debe habilitar una semana después de finalizada la transacción. _Viviana_

**R20.** El administrador del MP debe poder revisar el histórico de las ventas realizadas en la plataforma. El historico debe incluir la fecha de relización de la venta, el proveedor y cliente involucrados, el monto pagado y el estado de la venta. _Guillermo_

**R21.** EL sistema debe permitir a los usuarios ver la calificacion de los compradores, al lado de su nombre en la aplicacion, como un numero de 0 a 5 (mayor es mejor). Con un decimal. Calculado en el promedio de calificaciones recibidas. _Viviana_

#### Cambios incluídos

**R07.** El sistema debe proveer una galeria virtual a cada proveedor que incluya para los usuarios: diferentes criterios de clasificación de los vehiculos para encontrarlos. Entre los criterios solicitados se espera clasificación por modelo, por marca, por ciudad de venta y rango de precios.  _Cambio:_ La galería debe de disponer de varias imagenes y/o videos para cada vehículo. _Miguel_

#### Deuda Tecnica

**99.** Validar e implementar mejoras a nivel gráfico de tal manera que la navegación a través del sistema sea lo suficientemente intuitiva como para permitir a los usuarios realizar las diferentes actividades ofrecidas por el sistema y así garantizar un incremento en las visitas/ventas del sistema. _Diego_

**100.** Validar e implementar mejoras a nivel de código de tal manera que el mantenimiento de la aplicación sea lo menos traumático posible y así poder soportar los cambios a futuro… se debe disminuir la deuda técnica a por lo menos 3 días teniendo como punto de partida la cifra obtenida el día 29/10/2015 (11 días). _Diego_



### Chequeo de Requerimientos
*	[Archivo de Chequeo](https://docs.google.com/spreadsheets/d/1gbqvh-xTR9Dhh9Hh1EkAM7dDza2q9yeNAdvAw7Zd8qU/edit?usp=sharing)
