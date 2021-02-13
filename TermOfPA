from time import sleep
termo = int(input('Digite o valor para calculo de PA: '))
razao = int(input('Digite o valor da RAZÃO: '))
print('Calculando...')
sleep(1)
decimo = termo + (10 - 1) * razao
c = termo
while c < decimo + razao:
    print('{}'.format(c), end='→ ')
    c += razao
respot = 0
while respot != 1 or 2:
    print('\nDeseja ver mais alguns termos?')
    print('[ 1 ] SIM\n[ 2 ] NÃO')
    respot = int(input('Qual sua escolha?: '))
    if respot == 1:
        termo2 = int(input('Digite o valor para calculo de PA: '))
        razao2 = int(input('Digite o valor da RAZÃO: '))
        print('Calculando..')
        sleep(1)
        decimo2 = termo2 + (10 - 1) * razao2
        c2 = termo2
        while c2 < decimo + razao:
            print('{}'.format(c2), end='→ ')
            c2 += razao
    elif respot == 2:
        print('Ok, obrigado pela sua resposta.')
        sleep(0.1)
        print('=-=' * 19)
    else:
        print('Apenas 1 ou 2!')
