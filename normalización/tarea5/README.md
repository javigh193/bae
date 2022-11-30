# Pedidos

Se parte de la siguiente tabla:

orden (id_orden, fecha, id_cliente, nom_cliente, ciudad, num_art, nom_art, cant, precio)

![image](https://user-images.githubusercontent.com/115082160/204842497-c6450839-571b-401f-8579-eb46d7ac7235.png)

## 1. Comprobar si se cumple la 1ª Forma Normal

No se cumple la primera forma normal, ya que los valores no son atómicos. El campo id_orden tiene el mismo valor en diferentes tuplas. 

## 2. Normalizar si no se cumple el apartado 1

