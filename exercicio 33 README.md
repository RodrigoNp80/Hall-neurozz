# Hall-neurozz
  a = int(input('Primeiro Valor : '))
b = int(input('Segundo Valor: '))
c: int = int(input('Terceiro Valor : '))
menor = a
if b < a and b < c:
    menor = b
if c < a and c < b:
    menor = c

maior = a
if b > a and b > c:
    maior = b
if c > b and c > a:
    maior = c
print(f'O menor valor foi \33[31m{menor}\33[m')
print(f'O maior valor foi \33[31m{maior}\33[m')
