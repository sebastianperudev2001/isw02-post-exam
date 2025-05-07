# isw02-post-exam

3 puntos extras

## Caso

Una pequeña empresa de delivery desea crear una aplicación que permita a los usuarios ordenar comida desde su celular. La aplicación debe permitir registrar distintos tipos de comida (como pizza, hamburguesas, ensaladas), manejar pedidos que contienen uno o más de estos productos, y hacer un seguimiento del estado del pedido (pendiente, en preparación, entregado). El sistema debe tener una única instancia central que gestione todos los pedidos activos para evitar inconsistencias y permitir el seguimiento en tiempo real. Además, la creación de los distintos tipos de comida debe estar organizada de forma que el código no tenga que modificarse cada vez que se añade un nuevo platillo.

Preguntas:

1. Diseña las clases principales del sistema (como comida, pedido, usuario, etc.) e incluye sus atributos y métodos esenciales.

2. Implementa un patrón de diseño para que la creación de distintos tipos de comida (pizza, hamburguesa, ensalada) se realice de manera flexible y escalable sin modificar el código existente.

3. Implementa un segundo patrón de diseño en una clase que gestiona todos los pedidos activos no pueda ser instanciada más de una vez y siempre devuelva la misma instancia al ser usada.
