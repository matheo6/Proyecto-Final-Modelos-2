# Universidad Distrital Francisco jose de caldas 
# Proyecto-Final-Modelos-2

Presentado por Mateo Bohorquez Rodriguez Cod:20162021299 

Proyecto Final MODELOS2 Implementacion de un servicio atravez de la web para consultar usuarios de twitter desarrollado en python usando diferentes paradigmas y principios de programacion, uso de diferentes frameworks tanto para el front-end 
como para el back-end

## Distribucion

El proyecto se divide en dos modulos:
### logica

[el modulo de la logica ](https://github.com/matheo6/Proyecto-Final-Modelos-2/tree/master/Server%20Tweeter) donde se encuentran 3 archivos escritos en python un que se encarga de administrar y consumir los servicios del appi de tweeter llamado 
[twitter_tools.py](https://github.com/matheo6/Proyecto-Final-Modelos-2/blob/master/Server%20Tweeter/api.py)

otro encargado de realizar una generalizacion atravez de la orientacion a obetos para encapsular los usuarurios extraidos del api llamado 
[models.py](https://github.com/matheo6/Proyecto-Final-Modelos-2/blob/master/Server%20Tweeter/models.py)

el ultimo encargado de lanzar el servidor que responde a las peticiones realizadas desde las vistas llamado
[api.py](https://github.com/matheo6/Proyecto-Final-Modelos-2/blob/master/Server%20Tweeter/twitter_tools.py) 

### vista
[El modulo de la vista](https://github.com/matheo6/Proyecto-Final-Modelos-2/tree/master/View) contiene dos carpetas

Una para las vistas en donde se encuentran tres [Archivos Html](https://github.com/matheo6/Proyecto-Final-Modelos-2/tree/master/View/templates)

El primero es una plantilla que contiene la configuracion general donde se cargan los archivos css y el framwork bootstrap v 4 usado tanto en el html como en una pequeña funcionalidad de java script, addemas de los elemtos de diseño que compartiran las 2 vistas como la creacion de un navbar que permitira la navegacion este documento html se puede encontrar aqui [layout.html](https://github.com/matheo6/Proyecto-Final-Modelos-2/blob/master/View/templates/layout.html)

El segundo la vista princpial de ingreso del usuario de tweeter que desea consultar llamado [search.html](https://github.com/matheo6/Proyecto-Final-Modelos-2/blob/master/View/templates/search.html)

El tercero es la segunda vista, que se muestra al realizar la busqueda del usuario ingresado llamado [show.html](https://github.com/matheo6/Proyecto-Final-Modelos-2/blob/master/View/templates/show.html)

La segunda Carpeta Contiene el documento css para los stilos [static](https://github.com/matheo6/Proyecto-Final-Modelos-2/tree/master/View/static)   en donde se vera el archivo css [main.css](https://github.com/matheo6/Proyecto-Final-Modelos-2/blob/master/View/static/main.css)

Ademas en este mismo modulo " [El modulo de la vista](https://github.com/matheo6/Proyecto-Final-Modelos-2/tree/master/View) "se encontraran otros dos arcihvos escritos en python encargados de realizar la conexion al servidor llamado [webapp.py](https://github.com/matheo6/Proyecto-Final-Modelos-2/blob/master/View/webapp.py) el cual atravez de flask permite crear la aplicacion web y el otro recive los datos de la web para ser enviados al servidor [forms.py](https://github.com/matheo6/Proyecto-Final-Modelos-2/blob/master/View/forms.py) 






