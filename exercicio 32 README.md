# Hall-neurozz
  from datetime import date
ano = int (input('Digite um ano que você quer analisar : '))
if ano==0:
    ano = date.today().year
if ano%4 == 0 and ano % 100 !=0 or ano % 400 ==0:
#if ano%4 == 0  and ano % 100 ! = 0 or ano % 400 == 0:
    print('O ano \33[31m{}\33[m é BISSEXTO.'.format(ano))
else:
    print(' O ano \33[31m{}\33[m Não é BISSEXTO'.format(ano))
