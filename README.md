# Simulacro-III-Base-de-Datos

1- select nombre_pieza from piezas where color = "rojo";

2- select nombre_proveedor from proveedores where ciudad_proveedor = "madrid";

3- select nombre_pieza from piezas order by peso asc limit 1;

4- select max(nombre_proveedor) from proveedores inner join piezas on proveedores.id_proveedor = piezas.id_proveedor ?????

5- select nombre_proveedor from proveedores inner join piezas on proveedores.id_proveedor = piezas.id_proveedor where piezas.color = "azul";

6- slect nombre_proveedor, nombre_pieza from proveedores inner join piezas on proveedores.id_proveedor =  piezas.id_proveedor where nombre_proveedor = "Proveedor A" and order by piezas.peso desc limit 1;

7- 
