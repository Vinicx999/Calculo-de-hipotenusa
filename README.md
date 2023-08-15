#Código
import math
a = float (input ("Digite o valor do CATETO ADJACENTE:")) 
b = float (input ("Digite o valor do CATETO OPOSTO:"))
a2 = a**2
b2 = b**2
h = a**2 + b**2
h2 = math.sqrt(h)

#Impressão
print (f"{a}² + {b}² = h")
print (f"{a2} + {b2} = h")
print (f"h = {h}")
print (f"A hipotenusa é igual a: {h2}")
