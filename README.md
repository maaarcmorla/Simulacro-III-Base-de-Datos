# Simulacro-III-Base-de-Datos

1- select nombre_pieza from piezas where color = "rojo";

2- select nombre_proveedor from proveedores where ciudad_proveedor = "madrid";

3- select nombre_pieza from piezas order by peso asc limit 1;

4- select max(nombre_proveedor) from proveedores inner join piezas on proveedores.id_proveedor = piezas.id_proveedor ?????

5- select nombre_proveedor from proveedores inner join piezas on proveedores.id_proveedor = piezas.id_proveedor where piezas.color = "azul";

6- slect nombre_proveedor, nombre_pieza from proveedores inner join piezas on proveedores.id_proveedor =  piezas.id_proveedor where nombre_proveedor = "Proveedor A" and order by piezas.peso desc limit 1;

7- select nombre_ proveedor from proveedores inner join piezas on proveedores.id_proveedor = piezas.id_proveedor order by piezas.peso asc limit 1;

8- select nombre_piezas from piezas inner join proveedor on piezas.id_proveedor = proveedores.id_proveedor where ciudad_proveedores = "Barcelona";

9- select max(nombre_proveedor) from proveedor inner join piezas on proveedores.id_proveedor = piezas.id_proveedor group by color= "verde";

10- select max(nombre_pieza) from piezas inner join proveedores on piezas.id_proveedor = proveedores.id_proveedor where proveedores.ciudad_proveedore = "valencia";
