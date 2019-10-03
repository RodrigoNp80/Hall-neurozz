# Hall-neurozz
  import random
from time import sleep
print('=-='*20)
print(f'Vou pensar num número de 0 a 5 , tente advinhar ! ')
print('=-='*20)
lista = [0,1,2,3,4,5]
num = int(input('Que número eu pensei ?'))
n = random.choice(lista)
print('PROCESSANDO...')
sleep(3)
if n==num:
   print(f'\33[34mPARABÉNS\33[m ! Você acertou ! O número que eu pensei foi \33[31m{n}\33[m')
else:
    print('\33[31mERROU !')
