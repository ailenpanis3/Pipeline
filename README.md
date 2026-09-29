Respuestas a las preguntas de la entrega:

Tabla clientes:

•	Decidí qué hacer con los dos registros que tienen nulos en email y ciudad. Justificá tu decisión en el documento de entrega: ¿los eliminás o los reemplazás con un valor por defecto? ¿Por qué?
Respuesta: no hay que eliminar los valores nulos, ya que no se puede eliminar todo un cliente por no tener un su valor de email o ciudad. Se podría remplazar por un valor por defecto, por ejemplo, “sin especificar” o, en el caso de la ciudad, remplazarlo por el valor más probable (en este caso Buenos Aires). Esto permite mantener el registro del cliente intacto, ya que aparecerán bajo la categoría “sin especificar", lo cual no afecta los indicadores al no inflar ningún valor y sin perder registros.

Tabla productos:

•	El producto con precio nulo es un problema crítico ya que sin precio no se puede calcular el ingreso. Decidí si lo eliminás o lo reemplazás con un valor lógico y justificalo.

•	El producto con categoria nula puede asignarse a una categoría existente o marcarse como "Sin Categoría". Justificá tu elección.
Respuesta: Cuando un producto no tiene precio, se corre el riesgo de que su valor nulo afecte a los cálculos de ingresos y costos, pero el producto no puede ser eliminado ya que rompería las relaciones del modelo (si es que ya se vendió o se va a vender), entonces, hay que asignarle un valor que sea lógico. Por ejemplo, por el valor promedio de la categoría.
En este caso, al ser el único producto de la categoría, se le agregará un margen sobre el costo del 90%, ya que el 90% es el margen de ganancia promedio de los demás productos.

El producto con categoría nula puede asignarse a una categoría existente o marcarse “Sin Categoría”. En este caso, conviene asignarle una categoría. Entre todos los productos, hay 4 categorías distintas y 6 subcategorías. El producto con ID_producto=111 pertenece a la subcategoría “Laptops”. Esta subcategoría, está asignada dentro de la Categoría “Computación”, entonces, lo lógico es que al artículo pertenezca a esa misma categoría. 
