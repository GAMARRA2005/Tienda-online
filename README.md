# Tienda-online
Este programa modela una tienda en línea con productos, pedidos y clientes, permitiendo la gestión de estos elementos mediante estructuras de datos en Python.

Funcionalidades

Almacena una lista de productos con su información (ID, nombre, precio y stock).

Registra clientes con su nombre, email y dirección.

Gestiona pedidos con un estado inicial de "Pendiente".

Permite agregar nuevos productos a la tienda.

Permite actualizar el estado de los pedidos.

Permite buscar pedidos de un cliente específico por su email.

Casos de Prueba

Datos Iniciales:

Producto: "Camisa", $19.99, stock 50

Cliente: "Ana Gómez", email "ana@example.com"

Pedido: ID 101, Cliente "Ana Gómez", Producto "Sombrero", Estado: "Pendiente"

Operaciones Realizadas:

Se agregó un nuevo producto: "Pantalón", $39.99, stock 75.

Se cambió el estado del pedido 101 a "Entregado".

Se buscaron los pedidos de "Ana Gómez".

Salida Esperada:

Lista de productos con "Pantalón" incluido.

Pedido 101 ahora tiene estado "Entregado".

Se muestra el pedido de "Ana Gómez" en la búsqueda por email.
