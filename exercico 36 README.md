# Hall-neurozz
  print('=-='*20 )
print('ANALISADOR DE TRIANGULOS')
print('=-='*20 )
r1 = float(input('Primeiro Segmento : '))
r2 = float(input('Segundo Segmento : '))
r3 = float(input('Terceiro Segmento : '))
if r1 < r2 + r3 and r2 < r1 + r3 and r3 < r1 + r2 :
    print('Os segmentos acima \33[34mPODEM FORMAR\33[m um triângulo! ')
else:
    print('Os segmentos acima \33[34mN ÃO PODEM \33[mformar um triângulo !')

