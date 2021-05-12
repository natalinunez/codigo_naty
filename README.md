# Posicionamiento en CSS
## `position: relative;`
- Puedo mover al elmento con 2 ejes de referencia:
    -   top:    cantidad de pixeles desde el extremo superior
    -   left:   cantidad de pixeles desde el extremo izquierdo
## `position:abolute`
-   El elemento sale del contexto de los demas elementos(tiene ek efecto de flotar sobre los demas elementos)
-   Los elementos que no tienen posistion absolute, ocupan el espacio de este elemento 
-Puedo mover al elemento con 4 ejes de referencia
    - top, left right y bottom
    obligatoriamente se debe especificar 2 ejes de referencia
    ele elmento absolute se mueve con referencia al proximo padre directo que tenga position relative. De no cumplirse el anteior puntpo, el padre de referencia seria el html