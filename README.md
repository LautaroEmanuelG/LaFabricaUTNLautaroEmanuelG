# LaFabricaUTNLautaroEmanuelG
Proyecto Realizado con Java para la logica de negocios, Swing para interfaces y se usaron archivos para persistir informacion.

* Una empresa que se dedica a fabricar determinada gama de producto, requiere un sistema que  le permita realizar las órdenes de producción y mantener al día el estado del stock.*

- Las órdenes de producción indican la cantidad de unidades de un determinado 
producto que hay que fabricar.

- Para cumplir una orden de producción se debe analizar la existencia de las materias 
primas que componen el producto solicitado. En caso que pueda realizarse se da por cumplida 
la orden de producción y el pedido que le dio origen. Si de alguna de las materias primas no hay 
suficiente stock, se deja la orden pendiente.

## Enunciados de Proyectos para el examen Global
- Cada materia prima o producto se expresa siempre en la misma unidad de medida.
- Cada producto se elabora según la formula de fabricación en la que se enumeran sus 
materias primas y la cantidad necesaria de cada una de ellas.
- En la fórmula de fabricación de un producto, además de materias primas, puede 
haber también otros productos de los que produce la fábrica (se garantiza que no se producen 
ciclos)

### Hacer los métodos que permitan:
1. Procesar las órdenes pendientes para poder realizarlas.
2. Emitir un listado con los n productos en los que mas se utilice una determinada materia 
prima
