# java-caixa-eletronico

Caixa Eletrônico 
Descrição

O projeto "Caixa Eletrônico do Angelo" é um sistema simples de caixa eletrônico desenvolvido em Java. Ele simula as operações básicas de um caixa eletrônico bancário, permitindo que os usuários consultem seu saldo, façam depósitos e saques.
Funcionalidades

    Consultar Saldo: Permite ao usuário verificar o saldo atual da conta bancária.
    Fazer Depósito: Permite ao usuário adicionar um valor ao saldo da conta.
    Fazer Saque: Permite ao usuário retirar um valor da conta, desde que haja saldo suficiente.
    Sair: Encerra o programa.

Estrutura do Código
Classe CaixaEletronico

    Atributos:
        ContaBancaria conta: Representa a conta bancária associada ao caixa eletrônico.

    Métodos:
        CaixaEletronico(ContaBancaria conta): Construtor da classe que inicializa a conta bancária.
        exibirMenu(): Exibe o menu principal do caixa eletrônico e processa as opções selecionadas pelo usuário.
        consultarSaldo(): Exibe o saldo atual da conta.
        fazerDeposito(): Permite ao usuário realizar um depósito.
        fazerSaque(): Permite ao usuário realizar um saque.

Funcionamento

O método exibirMenu() exibe um menu para o usuário com opções para consultar o saldo, fazer depósitos, fazer saques ou sair. Dependendo da opção selecionada, o sistema executa a ação correspondente. O programa continua em execução até que o usuário escolha sair.
Dependências

    Java 8 ou superior

Como Executar

    Compile o Projeto:
        Certifique-se de que o Java está instalado e disponível no seu PATH.
        Compile o código fonte:

        bash

    javac -d bin src/angelo/project/CaixaEletronico.java

Execute o Projeto:

    Execute o programa:

    bash

        java -cp bin angelo.project.CaixaEletronico

Contribuição

Sinta-se à vontade para contribuir para o projeto. Caso deseje adicionar novas funcionalidades ou melhorias, faça um fork do repositório e envie um pull request com suas alterações.
