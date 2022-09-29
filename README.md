# Ajuste Gamma de Imágenes.
Imágenes digitales, este repositorio contiene la información para realizar el ajuste gamma

## Objetivo.
Implementar la mejora del contraste en imagenes digitales usando el ajuste gamma
##                                TEORIA.
El ajuste gamma permite el aumento de contraste para mejorar areas muy claras o muy oscuras. Normalmente modifica los valores medios-bajos, sin afectar el blanco(255) ni el negro(0).

Otra de sus caracteristicas es que compensa el rendimiento de diferentes dispositivos frente a una imagen, (se usa y usaba en televisores, pantallas, etc).

### ¿Como se implementa el ajuste gamma?

-Ajustando el brillo y el contraste.
-Actuando sobre la intensidad de cada uno de los pixeles de forma puntual.
-Modificando el valor del contraste que aumenta la intensidad para corregir los datos d la imagen, asi nos mostrara los detalles que pasan desapercibidos.

### Funcion de Ajuste Gamma.
La función se puede implementar sobre una imagen en escala de grises o sobre una imagen en color real RGB.
![image](https://user-images.githubusercontent.com/114626288/192912507-e30f2d8c-cab5-43be-b7b4-5545cbacea75.png)

*Efecto del factor de ajuste
1.Para gamma = 1 no hay ninguna corrección. No se modifica la imagen.
2.Para gamma > 1 hay una gran correccion para valores pequeños del color de entrada.
3.Para gamma < 1 hay una gran correccion en el contraste para valores grandes.
