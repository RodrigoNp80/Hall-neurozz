# Hall-neurozz
  vel = float(input('Qual a velocidade do carro ?  '))
if vel>=80:
    multa=(vel-80)*7
    print(f'Você ultrapassou a velocidade de \33[31m80km\h\33[m, e será multado em \33[31m{multa:.2f} R$\33[m ')
else:
    print(f'\33[34mSiga devagar\33[m !')
