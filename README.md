# Dev
from unidecode import unidecode # type: ignore
print("Vamos Ver Se e palíndromo: ")
frase = input()
frase = unidecode(frase)
frase = frase.lower()
frase = frase.replace(" ", "")
texto = frase[::-1] 

print("A frase e um palíndromo" if frase == texto else "A frase não e um palíndromo")
