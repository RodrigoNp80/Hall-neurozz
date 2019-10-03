# Hall-neurozz
  salario = float(input('Qual o sálario do fúncionario ?  '))

if salario <=1.250:
    novo = salario + (salario * 15 / 100)

else :
    novo = salario + (salario * 10 / 100)
print(f'Quem ganhava \33[31m{salario:.2f}\33[m R$ passa a ganhar \33[31m{novo:.2f} R$')
