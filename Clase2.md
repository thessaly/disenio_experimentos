## ANOVA

Modelo estadístico

En una muestra aleatoria tomada de una pblacion con media mu, la observacion en una un exp es el resultado de la media, mas un error aleatorio

yij = mu + alphai + Eij

mu: media general, para toda la población
alphai: efecto del tratamiento o grupo i, comun a los miembros de la subpoblación i, varía de una subpoblación a otra (variación controlada)

condiciones:
- alphai son constantes
- la suma de alphai=0 (el efecto es constante)

Eij: error, variacion no controlada entre los miembros de cualquier subpoblación, varía de una observación a otra

Factor es la fuente devariación que se quiere comparar, los niveles de este factor son, en el caso general, cada uno de los grupos o tratamientos del mismo tipo

Modelo de efectos fijos: cuando la inferencia es válida solo para los niveles involucrados (alphai constantes). Cuando los efectos son aleatorios (alphai son variables aleatorias) y los niveles (tratamientos) son seleccionados de un conjunto mayor

En un modelo de efectos fijos se compara el efecto medio de los tratamientos. El experimentador asigna el tratamiento a cada unidad experimental elegida al azar de entre todas las disponibles.

### Supuestos para un modelo de efectos fijos

Se garantizan por diseño de experimento
- Los I grupos son muestras aleatorias extraídas de sus respectivas subpoblaciones
- Las I subpoblaciones son independientes

Testeadas previamente por prueba de hipotesis
- La respuesta o variable aleatoria que identifica a cada subpoblación está normalmente distribuida con media Mui y varianza Si2
- Las varianzas de las subpoblaciones son iguales - homogeneidad de varianzas. De esto se deduce que Eij aprox (0, S2) entonces errores normalmente distribuidos y son independientes

Varianza:

S2 = suma cuadrados (yi-ymedia)/n-1 (grados lib)

SC total: todos los datos mas alla del tratamiento, entre las medias
SC entre: dif entre medias de tratamientos y media total
SC dentro: dif entre dato tratamientoi vs mediai

SCtotal = SCentre+SCdentro

grados de libertad
GLtotal= n-1
GLentre=a-1
GLdentro=N-a

a= cantidad de tratamientos  

Cuadrados medios: SC/GL (total, entre, dentro) --> medida de la variabilidad

Cuando SCentre>SCdentro hay significancia entre tratamientos

Puedo establecer una comparación haciendo cociente de cuadrados medios, que tienen una distribución asimétrica (F = CMentre/CMdentro), asignando una probabilidad alpha=determinada y haciendo una prueba de hipótesis

El anova de un factor compara variabilidades entre y dentro tratamientos. Cuando p<0.05 rechazo Ho, es decir q rechazo la hipótesis que dice que todos los tratamientos son iguales

## Muestreo aleatorio

Las un exp deben tener la misma prob de ser elegidas para el experimento. Si no, implicaría no-normalidad de la distribucion de la variable o afectar la homogeneidad de varianzas.

## Independencia

Independencia de los errores, simplifico variables.

## Homogeneidad de varianzas

Razones de heterogeneidad:
- poblaciones más variables que otras
- especies uniformes para un caracter no para otro
- muestras tomadas en condiciones distintas
- mala eleccion de la escala de medición

Consecuencias:
- si el diseño es balanceado y la falta de homogeneidad es moderada, no pasa nada
- si la varianza es demasiado heterogenea no hay forma

Pruebas:
Mas comun, la de Bartlett

## Normalidad

Se supone normalidad de los errores
Se pueden aplicar transformaciones de los datos cuando no hay
La prueba de normalidad se hace para cada tratamiento (test Shapiro-Wilks)


## Independencia

Se garantiza con muestreo aleatorio
