# Hall-neurozz
  n = str(input('Digite seu nome completo :')).strip()
nome = n.split()
print(f'Olá Prazer em te conhecer ! \33[34m{n}\33[m')
print(f'Seu primeiro nome é \33[31m{nome[0]}\33[m')
print(f'Seu último nome é \33[31m{nome[len(nome)-1]}')
