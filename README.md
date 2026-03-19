Reto 1: Filtrado por contenido y estado.
//recurso[categoria='CSS' and disponible='true']/titulo /string()
//recurso: Esta es la raiz de la busqueda
[categoria='CSS' and disponible='true']: Busca dentro de recurso aquellos que tengan la categoria CSS y la disponivilidad sea true
/titulo /string(): Muestra el titulo de aquellos recursos que cumplan la condicion anterior.

Reto 2: Atributos y negaciones.
//recurso[not(@formato='PDF')]/@id /string()
//recurso: Esta es la raiz de la busqueda
[not(@formato='PDF')]: Esta condicion busca los recursos que NO tengan en el atributo formato PDF el resto si
/@id /string(): Muestra el id de todos los recursos de los cuales se cumpla la condicion anterior

Reto 3: Manejo de múltiples nodos (Autores).
//recurso[anio > 2015]/autor[1] /string()
//recurso: Esta es la raiz de la busqueda
