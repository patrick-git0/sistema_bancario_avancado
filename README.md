Sistema Bancário Avançado 🏦

Este é um projeto simples de sistema bancário em Python. Ele foi desenvolvido como uma aplicação de linha de comando para simular operações básicas, como depósitos, saques e visualização de extrato.

🌟 Funcionalidades
Depósito: Adicione dinheiro à sua conta. 💰

Saque: Retire dinheiro da sua conta, com um limite diário de R$ 500,00 e no máximo 3 saques por dia. 💸

Extrato: Veja todo o histórico de transações e o saldo atual da sua conta. 📊

Novo Usuário: Crie um novo perfil de usuário com CPF, nome, data de nascimento e endereço. 🧑‍💻

Nova Conta: Abra uma nova conta bancária vinculada a um usuário existente. 💳

Listar Contas: Veja todas as contas criadas no sistema. 📋

⚙️ Como Usar
Execute o arquivo sistema_bancario.py em um terminal.

Use o menu exibido para escolher a operação desejada.

👩‍💻 Estrutura do Código
O código é estruturado com funções para cada funcionalidade principal, garantindo organização e reuso:

menu(): Exibe o menu de opções.

depositar(): Cuida da lógica de depósito.

sacar(): Implementa a lógica de saque com todas as validações (saldo, limite, número de saques).

exibir_extrato(): Mostra o extrato da conta.

criar_usuario(): Adiciona um novo usuário.

filtrar_usuario(): Função auxiliar para buscar um usuário pelo CPF.

criar_conta(): Cria uma nova conta bancária.

listar_contas(): Lista todas as contas existentes.

main(): A função principal que gerencia o fluxo do programa.

