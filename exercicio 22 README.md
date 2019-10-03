# Hall-neurozz
  nome = str(input('Digite o nome completo : ')).strip()
print(f'O nome com letras MAÍSCULAS é \33[31m{nome.upper()}\33[m')
print(f'O nome com letras MINUSCULAS é \33[31m{nome.lower()}\33[m')
print(f'Total de letras sem considerar os espaços: \33[32m{len(nome)-nome.count(" ")}\33[m')
print(f'O primeiro nome tem o total de \33[32m{nome.find(" ")}\33[m letras .')
