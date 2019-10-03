# Hall-neurozz
  from datetime import date
atual = date.today().year
nasc = int(input('Ano de Nascimento : '))
idade = atual - nasc
print('Quem nasceu em {} tem {} anos em {} '.format(nasc,idade,atual))
if idade == 18 :
    print('Voce tem que se alistar \33[32mIMEDIATAMENTE!\33[32m')
elif idade < 18 :
    saldo = 18 - idade
    print('Ainda faltam {} anos para o alistamento '.format(saldo))
    ano = atual + saldo
    print('Seu alistamneto será em {}'. format(ano))

elif  idade > 18  :
    saldo = idade - 18
    print('Voce deveria ter se Alistado a  {} anos  '.format(saldo))
    ano = atual - saldo
    print('Seu alistamneto foi em {}'.format(ano))

