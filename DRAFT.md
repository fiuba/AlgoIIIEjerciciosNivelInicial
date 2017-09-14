# Ejercicios de Nivel Inicial 

## Rango de Celdas
Buscamos implementar un subproblema que hace a la implementación de una hoja de cálculo tal como puede ser (SpreedSheet de Libre Office o Google Sheet).  Dados los siguientes rangos de celdas:

1. ```"a1:a10"```
2. ```"a1:z1"```
3. ```"a1:z10"```
4. ```"a1:c1,b5:b8"```

Necesitamos conocer cuáles direcciones pertenecen o no al rango.  Por ejemplo:

1. ```"a4"``` pertence al rango ```"a1:a10"```.
2. ```"z2"``` **no** pertenece al rango ```"a1:z1"```
3. ```"b5"``` pertenece al rango ```"a1:z10"```.
4. ```"b1"``` y ```"b7"``` pertenece al rango ```"a1:c1,b5:b8"```

## Venta de items

El objetivo de este dojo es implementar parcialmente el modelo precios y costos para compra/venta de items con el fin de poder calcular un márgen de ganancia.

Existen varios esquemas de precios de ventas:
- N unidades por un dolar.
- $ M por peso.
- Compra dos paga 1.
- Uno sorpresa (vemos si llegamos)

Existen varios esquemas de precios de compra:
- $ M por peso.
- $ M por N unidades.


La funcionalidad que buscamos implementar **no** cuenta con pruebas y se busca que decidamos que pruebas deberíamos escribir, ya sean de integración o de unidad.

### Metodología

Programación orientada a objetos + TDD

