# RESPONSIVE WEB DESIGN
Es hacer que la pagina web sea adaptable o que se moldee  a cualquier dispositivo
## Enfoque mobile-first
Este enfoque se basa en la priorizacion del desarrollo web para  dispositivos moviles, y de acuerdo a las experiencias extender el desarrollo para la version de escritorio.
## Enfoque desktop first
Al contrario del enfoque mobile-first, primer se desarrolla para pantallas del tamaño mas grande,y luego elimina, reorganiza las caracteristicas y el contenido a medida que disminuye el tamaño de la pantalla.

# MEDIA QUERY
Regla que permite establecer una condicion (tamaño, viewport, orientacion de dispositivos), a  partir de  la cual se elimina ,cambia o reorganiza los estilos css.

```
@media (max-width:767px) {
 .menu{ flex-direction: column;
 }   
}
```
## breck point (pixel, resolucion, tamaño, etc)
Un breakpoint, es el ancho de un dispositivo en el cual queremos que la forma en la que mostramos nuestro contenido con CSS cambie. En el siguiente ejemplo tenemos un breakpoint a 767px.

```
@media (max-width:767px) {
}
```
# CREAR UN MENU HORIZONTAL Y QUE A 767 PX SE UBIQUE DE MANERA VERTICAL

![alt text](<Captura desde 2024-05-11 17-50-54.png>)
![alt text](<Captura desde 2024-05-11 17-53-40.png>)

## Authors

- [JOSE-DIAZ-ROJAS](https://github.com/JOSE-DIAZ-ROJAS)