# Funciones Lambda
lambda argumentos: manipular(argumentos)
```
suma = lambda x, y: x + y
print(suma(3, 5))
```

# Salida: 8

# Operadores ternario
```
es_bonito = True
estado = "Es bonito" if es_bonito else "No es bonito"
```

# String Formatting
Python usa un estilo de formato de cadenas parecido a C para crear nuevas cadenas de texto. El operador "%" es usado para dar este formato y fijar las variables encerradas en una "tupla" (una lista inmutable la cual no puede ser reasignada) juntos con una cadena con formato, que contiene el texto normal junto con "argumentos especificados", como los símbolos especiales "%s" y "%d".

Digamos que tienes una variable llamada "nombre" con tu nombre de usuario en ella y querrás darle un saludo al usuario.


# Esto imprime "Hola, Juan!"
```
nombre = "Juan"
print("Hola, %s!" % nombre)
Para usar dos o más especificadores de argumento, usa un tupla (con parentesis):
```

# Esto imprime "John is 23 years old."
```
nombre = "John"
edad = 23
print("%s tiene %d años." % (nombre, edad))
```
Cualquier objeto del cual no sea una cadena puede ser formateado usando el operador %s. La cadena que retorne de un método "repr" de ese objeto, será formateada como cadena, por ejemplo:

# Esto muestra lo siguiente: Una Lista: [1, 2, 3]
```
milista = [1,2,3]
print("Una lista: %s" % milista)
```
Aquí hay algunos especificadores de argumentos básicos como debes saber:

```
%s - Cadena (O cualquier objeto, como los números al representarlos en una cadena de texto)
%d - Integrales
%f - Números de punto flotante
%.<numero de digitos>f - Números de punto flotante con una cantidad de números fijos a la derecha del punto.
%x/%X - Integral con representacion hex (minúscula/mayúscula)
```
