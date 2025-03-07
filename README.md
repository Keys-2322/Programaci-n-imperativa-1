def calcular_promedio(lista_de_numeros):
# paso 1 Verificamos si la lista está vacía. Si está vacía, devolvemos un mensaje que indique que no se puede calcular el promedio.
    if len(lista_de_numeros) == 0:
        return "La lista está vacía. No se puede calcular el promedio."
  # paso 2  y 3 Inicializamos una variable llamada suma en 0 y luego utilizamos un bucle for para recorrer la lista de números. En cada iteración, sumamos el número actual a la variable suma.
    suma = 0
    for numero in lista_de_numeros:
        suma += numero  
    
# paso 4 Una vez que tenemos la suma de todos los números, dividimos suma entre el número total de elementos en la lista (es decir, len(lista_de_numeros)) para obtener el promedio.
    promedio = suma / len(lista_de_numeros)
# paso 5 Devolvemos el promedio calculado.
    return promedio


numeros = [10, 20, 30, 40, 50]

resultado = calcular_promedio(numeros)
print("El promedio de los números es:", resultado)

Si hacemos todo bien el resultado esperado de [10,20,30,40,50] seria [30.0]
