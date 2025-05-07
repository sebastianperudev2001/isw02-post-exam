# isw02-post-exam

3 puntos extras

## Caso

Una pequeña empresa de delivery desea crear una aplicación que permita a los usuarios ordenar comida desde su celular. La aplicación debe permitir registrar distintos tipos de comida (como pizza, hamburguesas, ensaladas), manejar pedidos que contienen uno o más de estos productos, y hacer un seguimiento del estado del pedido (pendiente, en preparación, entregado). El sistema debe tener una única instancia central que gestione todos los pedidos activos para evitar inconsistencias y permitir el seguimiento en tiempo real. Además, la creación de los distintos tipos de comida debe estar organizada de forma que el código no tenga que modificarse cada vez que se añade un nuevo platillo.

Preguntas:

1. Diseña las clases principales del sistema (como comida, pedido, usuario, etc.) e incluye sus atributos y métodos esenciales.

2. Implementa un patrón de diseño para que la creación de distintos tipos de comida (pizza, hamburguesa, ensalada) se realice de manera flexible y escalable sin modificar el código existente.

3. Implementa un segundo patrón de diseño en una clase que gestiona todos los pedidos activos no pueda ser instanciada más de una vez y siempre devuelva la misma instancia al ser usada.

Requerimientos de tu clase Main:

- Los nombres y precios de las comidas creadas.

- El total del pedido y su estado antes y después de cambiarlo.

- La lista de pedidos registrados en el sistema (usando la clase centralizada).

- Una verificación de que la instancia del gestor de pedidos es única (debe imprimir true al comparar dos llamadas a getInstancia() o equivalente).

Output ideal:

```
Comidas creadas:
- Pizza S/.25.0
- Ensalada S/.15.0
- Hamburguesa S/.18.0

Total del pedido: S/.58.0
Estado inicial: pendiente
Estado actualizado: en preparación

Pedidos registrados en el sistema:
- Pedido #1: 3 comidas, estado: en preparación

¿Gestores son iguales? true
```
