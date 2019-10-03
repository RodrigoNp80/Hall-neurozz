# Hall-neurozz
  nome = str(input('Digite uma frase : ' )).strip().upper()
print('A letra "A" aparece \33[31m{}\33[m vezes na frase'.format(nome.count('A')))
print('A primeira letra "A" apareceu na posição \33[31m{}\33[m'.format(nome.find('A')+1))
print('a última letra "A" apareceu na posiçao \33[31m{}\33[m'.format(nome.rfind('A')))
