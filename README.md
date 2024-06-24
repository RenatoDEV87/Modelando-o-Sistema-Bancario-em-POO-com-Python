# Desafio Nível Avançado: Modelando o Sistema Bancário em POO com Python

Este projeto é uma implementação de um sistema bancário simples utilizando Programação Orientada a Objetos (POO) em Python. O sistema permite cadastrar usuários, criar contas bancárias e realizar operações básicas como depósitos, saques e consulta de extratos.

## Funcionalidades

- Cadastro de novos usuários
- Criação de novas contas bancárias
- Listagem de contas bancárias
- Depósito em contas bancárias
- Saque de contas bancárias
- Exibição de extratos bancários

## Estrutura do Código

O código está organizado em funções para melhorar a modularidade e a manutenção:

- **menu**: Exibe o menu principal e retorna a opção escolhida pelo usuário.
- **depositar**: Realiza um depósito em uma conta bancária.
- **sacar**: Realiza um saque de uma conta bancária.
- **exibir_extrato**: Exibe o extrato de uma conta bancária.
- **criar_usuario**: Cadastra um novo usuário.
- **filtrar_usuario**: Busca um usuário pelo CPF.
- **criar_conta**: Cria uma nova conta bancária para um usuário existente.
- **listar_contas**: Lista todas as contas bancárias cadastradas.
- **main**: Função principal que controla o fluxo do programa.

## Requisitos

- Python 3.x

## Como Executar

1. Clone este repositório para sua máquina local.
2. Navegue até o diretório onde o arquivo `sistema_bancario.py` está localizado.
3. Execute o arquivo `sistema_bancario.py` com Python:

```bash
python sistema_bancario.py
```

## Exemplo de Uso

```bash
=============== MENU ================
[d]	Depositar
[s]	Sacar
[e]	Extrato
[nc]	Nova conta
[lc]	Listar contas
[nu]	Novo usuário
[q]	Sair
=> nu
Informe o CPF (somente número): 12345678901
Informe o nome completo: João Silva
Informe a data de nascimento (dd-mm-aaaa): 01-01-1990
Informe o endereço (logradouro, nro - bairro - cidade/sigla estado): Rua A, 123 - Centro - Rio de Janeiro/RJ
=== Usuário criado com sucesso! ===

=============== MENU ================
[d]	Depositar
[s]	Sacar
[e]	Extrato
[nc]	Nova conta
[lc]	Listar contas
[nu]	Novo usuário
[q]	Sair
=> nc
Informe o CPF do usuário: 12345678901
=== Conta criada com sucesso! ===

=============== MENU ================
[d]	Depositar
[s]	Sacar
[e]	Extrato
[nc]	Nova conta
[lc]	Listar contas
[nu]	Novo usuário
[q]	Sair
=> d
Informe o valor do depósito: 500
=== Depósito realizado com sucesso! ===

=============== MENU ================
[d]	Depositar
[s]	Sacar
[e]	Extrato
[nc]	Nova conta
[lc]	Listar contas
[nu]	Novo usuário
[q]	Sair
=> e

================ EXTRATO ================
Depósito:	R$ 500.00

Saldo:		R$ 500.00
==========================================
```
## Contribuição
Contribuições são bem-vindas! Sinta-se à vontade para abrir issues e pull requests.

## Licença
Este projeto está licenciado sob a Licença MIT - veja o arquivo LICENSE para mais detalhes.


