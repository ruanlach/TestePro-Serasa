nome = input(' Informe o seu nome completo \n').title()
data_nascimento = input('Informe a sua data de nascimento\n')
num_rg = input('Informe seu RG\n')
num_cpf = input('Informe o seu CPF\n')
nome_pai = input('Informe o nome do seu pai\n')
nome_mae = input('Informe o nome da sua mãe\n')
renda_mensal = float(input(f'Olá {nome} informe sua renda mensal \n'))
parcmax = renda_mensal * 30 / 100
valor_solicitado = float(input(f'Informe o valor do empréstimo que você precisa \n'))

parc_6 = (valor_solicitado / 6) + (valor_solicitado * (10.45 / 100))
parc_12 = (valor_solicitado / 12) + (valor_solicitado * (3.62 / 100))
parc_24 = (valor_solicitado / 24) + (valor_solicitado * (2.29 / 100))
parc_36 = (valor_solicitado / 36) + (valor_solicitado * (2.15 / 100))
parc_48 = (valor_solicitado / 48) + (valor_solicitado * (2.12 / 100))

if parcmax < parc_48:
    print('Infelizmente não temos nenhuma linha de crédito para você')
elif parcmax > parc_6:
    parcelas_disp = [6, 12, 24, 36, 48]
    num_parcelas = int(input(f'Informe em quantas parcelas deseja pagar: 6XR${parc_6} / 12XR${parc_12} / 24XR${parc_24}'
                             f' / 36XR${parc_36} ou 48XR${parc_48} \n'))
    while num_parcelas not in parcelas_disp:
        num_parcelas = int(input('Número de parcelas inválido, seleciona entre 6,12,24,36 ou 48 parcelas'))
elif parcmax > parc_12:
    parcelas_disp = [12, 24, 36, 48]
    num_parcelas = int(input(f'Informe em quantas parcelas deseja pagar: 12XR${parc_12} / 24XR${parc_24} /'
                             f' 36XR${parc_36} ou 48X{parc_48} \n'))
    while num_parcelas not in parcelas_disp:
        num_parcelas = int(input('Número de parcelas inválido, seleciona entre 12,24,36 ou 48 parcelas'))
elif parcmax > parc_24:
    parcelas_disp = [24, 36, 48]
    num_parcelas = int(input(f'Informe em quantas parcelas deseja pagar: 24XR${parc_24}, 36XR${parc_36} ou '
                             f'48XR${parc_48} \n'))
    while num_parcelas not in parcelas_disp:
        num_parcelas = int(input('Número de parcelas inválido, seleciona entre 24,36 ou 48 parcelas'))
elif parcmax > parc_36:
    parcelas_disp = [36, 48]
    num_parcelas = int(input(f'Informe em quantas parcelas deseja pagar: 36XR${parc_36} ou 48XR${parc_48} \n'))
    while num_parcelas not in parcelas_disp:
        num_parcelas = int(input('Número de parcelas inválido, seleciona entre 36 ou 48 parcelas'))
else:
    num_parcelas = 48
    print(F'A única linha de crédito disponível para você é em 48X{parc_48} parcelas')

if num_parcelas == 6:
    resposta = input(f'O valor do empréstimo é de R${valor_solicitado} e plano de pagamento é: 6 X de R${parc_6}.'
                     f'deseja contratar?S(Sim) N(Não)')
    resposta_poss = ['S', 's', 'N', 'n']
    while resposta not in resposta_poss:
        resposta = input('Resposta inválida, deseja contratar? S(Sim) N(Não)')

elif num_parcelas == 12:
    resposta = input(f'O valor do empréstimo é de R${valor_solicitado} e o plano de pagamento é: 12 X de R${parc_12}.'
                     f'deseja contratar?S(Sim) N(Não)')
    resposta_poss = ['S', 's', 'N', 'n']
    while resposta not in resposta_poss:
        resposta = input('Resposta inválida, deseja contratar? S(Sim) N(Não)')

elif num_parcelas == 24:
    resposta = input(f'O valor do empréstimo é de R${valor_solicitado} e o plano de pagamento é: 24 X de R${parc_24}.'
                     f'deseja contratar?S(Sim) N(Não)')
    resposta_poss = ['S', 's', 'N', 'n']
    while resposta not in resposta_poss:
        resposta = input('Resposta inválida, deseja contratar? S(Sim) N(Não)')

elif num_parcelas == 36:
    resposta = input(f'O valor do empréstimo é de R${valor_solicitado} e o plano de pagamento é: 36 X de R${parc_36}.'
                     f'deseja contratar?S(Sim) N(Não)')
    resposta_poss = ['S', 's', 'N', 'n']
    while resposta not in resposta_poss:
        resposta = input('Resposta inválida, deseja contratar? S(Sim) N(Não)')

elif num_parcelas == 48:
    resposta = input(f'O valor do empréstimo é de R${valor_solicitado} e o plano de pagamento é: 48 X de R${parc_48}.'
                     f'deseja contratar? S(Sim) N(Não)')
    resposta_poss = ['S', 's', 'N', 'n']
    while resposta not in resposta_poss:
        resposta = input('Resposta inválida, deseja contratar? S(Sim) N(Não)')

if resposta == 'S' or 's':
    print(f'Revisando os dados\n'
          f'Nome:{nome}\n '
          f'RG:{num_rg}\n'
          f'CPF:{num_cpf}\n'
          f'Valor Solicitado: {valor_solicitado}\n'
          f'Plano de pagamento: 48 X de R${parc_48}\n')
else:
    print(f'Obrigado e volte sempre')
