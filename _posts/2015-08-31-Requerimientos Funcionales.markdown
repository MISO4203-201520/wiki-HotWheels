---
layout: page
title:  "Requerimientos Funcionales"
date:   2015-08-31 00:00:04
categories: jekyll update
---

#Requerimientos existentes

**ER1.** El sistema debe ofrecer a los usuarios la opción de registrar sus datos personales (usuario, password, nombre, correo, rol) para poder crear una nueva cuenta en la plataforma. El sistema debe permitir seleccionar el rol (provider o user) con el que se quiere crear la cuenta . Adicionalmente la plataforma debe pedir al usuario la confirmación de su cuenta de correo antes de poder autenticarse por primera vez.

**ER2.** El sistema debe ofrecer a los usuarios la opción de autenticación, se debe mostrar un formulario que permita ingresar el nombre de usuario y contraseña. El sistema debe permitir recordar esta información para acelerar el ingreso a futuro; una vez el usuario ingrese al sistema, este lo debe redireccionar a la página de inicio dependiendo del rol (provider o user)

**ER3.** El sistema debe ofrecer a los usuarios la posibilidad de consultar el catálogo de vehículos que actualmente ofrece la plataforma. En particular el usuario debe poder visualizar la referencia del vehículo, el precio y el vendedor que lo provee.

**ER4.** El sistema debe ofrecer al usuario la posibilidad de agregar artículos (vehículos) al carrito de compras, una vez finalizado el proceso de selección de artículos el usuario debe poder ver el resumen de su selección para poder confirmar o editar su selección. a su vez el usuario podrá eliminar artículos del mismo.

#Requerimientos por realizar

**Ciclo1**

**R1.** El sistema debe ofrecer al comprador la opción de pagar la compra. Se debe mostrar un formulario para realizar el pago que despliegue el total de la compra y el desglose en impuestos. Suponga que hay un impuesto a las ventas del 16% . Debe estar la posibilidad de seleccionar el tipo de tarjeta crédito/debito con el que se realizará el pago. Cuando el usuario seleccione pagar, el sistema debe guardar la información sobre el pago de forma persistente en la base de datos. (8) DIEGO AGUDELO

**R2.** El sistema debe ofrecer al comprador la posibilidad de agregar comentarios sobre los productos. El comentario va  asociado con un producto específico y es una descripción en texto libre de no más de 255 caracteres. Los comentarios asociados con los productos se deben persistir incluyendo la fecha, el usuario y la descripción.  (3) Guillermo Ferro
R3. El sistema debe ofrecer al usuario con el rol de administrador el servicio de ver los usuarios registrados en la aplicación y sus roles. Se debe agregar el rol de administrador en Stormpath (el mecanismo de seguridad que está utilizando la aplicación). (3) DAVID

**R4.** El sistema debe ofrecer al comprador la posibilidad de registrar preguntas sobre un producto de un proveedor específico. La pregunta se debe persistir con el producto al que hace referencia, el usuario, su email, la fecha y la descripción.  Cuando se registre la pregunta al proveedor, al proveedor debe llegarle una notificación por email. (5) HAROLD
R5.  El sistema debe ofrecer al comprador la posibilidad de realizar una búsqueda sobre el catálogo de productos que retorne el producto más barato de un proveedor dado, o el proveedor que ofrece el producto más barato de un tipo de producto dado. (5)  WILMAR FUQUEN

**R6.** El sistema debe ofrecer al proveedor la posibilidad de agregar un descuento especial a alguno de sus productos. Esta información debe desplegarse en el catálogo. (3) 

#Otros ciclos

**R7.** Disponer de una galería virtual de proveedores de carros usados, que admita criterios de clasificación (modelo, marca, ciudad de venta, rango de precios, etc.). C3

**R8.** Contar con un sistema de búsqueda que permita localizar de manera simple las distintas ofertas. 

**R9.** Brindar herramientas de envío de mensajes internos (entre proveedores de carros, entre clientes o entre ambos).

**R10.** Foros de discusión para los usuarios de la plataforma (estos deben poder ser almacenados y posteriormente consultados por los clientes involucrados en la discusión).

**R11.** Soportar servicios de comercio electrónico, manejo de transacciones, con carritos de compras. Validación de las transacciones. El MP debe ser capaz de determinar en cualquier momento el estado de cualquier transacción de compra/venta del sistema.

**R12.** Registrase en el sitio web al momento de efectuar la compra de un producto

**R13.** Revisar histórico de transacciones efectuadas sobre la plataforma en un periodo de tiempo determinado

**R14.** Calificar el servicio adquirido(s) luego de haber hecho uso del mismo dentro de un periodo de tiempo razonable

**R15.** Buscar productos por varios criterios [Rel R7 Y R8]

**R18.** Consultar el Estado de un pedido

**R19.** Registrar/actualizar un proveedor de carros en el sitio web

**R20.** Registrar/actualizar un producto

**R21.** Publicar ofertas de los productos (Preguntar si es el mismo R6)

**R22.** Revisar históricos de ventas [Rel R13]

**R23.** Consultar las calificaciones de los compradores

**R24.** Responder preguntas de usuarios compradores

**R25.** Actualizar el estado del pedido de un cliente
