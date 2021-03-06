# FlexBox-flex-wrap
### flex-wrap: wrap o nowrap o wrap-reverse. shortHand flex-flow: row wrap

La propiedad flex-wrap de CSS especifica si los elementos "hijos" son obligados a permanecer en una misma línea (nowrap) o pueden fluir en varias líneas (wrap). Si la cobertura (wrap) está permitida, esta propiedad también te permite controlar la dirección (wrap-reverse) en la cual serán apilados los elementos.

```javascript
.contenedor-flex {
    /* inline-flex y flex deja en una linea y se sale del contenedor */
    display:flex;    
    border: 3px solid black;    
    flex-direction: row; 
    /*  flex-wrap: nowrap (por defecto). si tiene una fila larga y es necesario realizar scroll horizontalmente **/
    flex-wrap: nowrap;
}

.contenedor-flex-wrap {
    /* inline-flex y flex  */
    display:flex;    
    border: 3px solid black;    
    flex-direction: row; 
    /*  flex-wrap: wrap; . Llena el contenedor en borde negro*/
    /* flex-wrap normal es usar con flex-direction:row */
    flex-wrap: wrap;
}

.contenedor-flex-flow {
    display:flex;   
    border: 3px solid black;    
    flex-direction: row; 
  /* flex-flow: column o row   y wrap, nowrap o wrap-reverse */
    flex-flow: row wrap;
}
```
