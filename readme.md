## TRANSFORM

## translate
*translate(x, y)* mueve el objeto, ejes x, y
*translateX(x)* mueve el objeto en el eje x
*translateY(y)* mueve el objeto en el eje y

### scale
*scale(x%, y%)* escala el objeto en los porcentajes ejemplo: (1->100% , 0.5-> 50% , 2->200%)
*scaleX(x%)* lo escala en el eje x
*scaleY(y%)* lo escala en el eje y

### rotate
*rotate(ndeg)* lo rota en sentido de las agujas del reloj.
*rotateX(xdeg)* rota a lo largo del eje x ejemplo:
(90deg , 180deg)
*rotateY(y)* rota a lo largo del eje y
*rotateZ(z)* rota a lo largo del eje z

**transform: translateX(200px) rotateZ(90deg) scale(2);**
se ejecuta uno por uno de izquierda a derecha

## TRANSITION

*transition(ns)* el parametro se da en segundos, ejemplo (1s). Usado con el hover.

## KEYFRAME
*animation-name: name* ejemplo: @keyframe name{ }
*animation-duration: ns* ejemplo: animation-duration: 3s; tiempo de duracion de la animacion