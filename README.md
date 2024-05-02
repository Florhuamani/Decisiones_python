# CONTROLES DE FLUJO
Se trata de una estructura de control condicional. Nos permite evaluar si una o más condiciones se cumplen, para decir qué acción vamos a ejecutar. Esta evaluación de condiciones sólo puede dar un resultado Verdadero o un resultado Falso.
## Decisiones
Las decisiones en pythonse refieren a la capacidad de un programa para tomar diferentes caminos de ejecución basados en ciertas condiciones. Una forma común de implementar decisiones en python es mediante el uso de estructuras de control como ```if```, ```elif``` y ```else```.
> Ejemplo:
supongamos que queremos crear un programa que determine si un numero es positivo, negativo o cero. Podriamos hacerlonde la siguiente manera en python.
```python
número = 10
if número > 0 :
    print("el numero es positivo")
elif número < 0 :
    print("el numero es negativo")
else :
    print("el numero es cero")
```
