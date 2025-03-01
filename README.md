# Projeto ContaBanco

Este é um projeto simples em Java chamado **ContaBanco**, que recebe dados via terminal e exibe uma mensagem formatada com as informações de uma conta bancária.

##  Objetivo
Criar um sistema que:
- Solicita ao usuário informações como **número da conta, agência, nome do cliente e saldo**.
- Exibe uma mensagem formatada com os dados fornecidos.
- Utiliza conceitos básicos de **entrada de dados via terminal, Scanner, concatenação de strings e variáveis**.

##  Estrutura do Projeto
```
ContaBanco/
│── src/
│   │── ContaTerminal.java  <- Arquivo principal do programa
```

##  Tecnologias Utilizadas
- **Java**
- **Scanner** (para entrada de dados)
- **System.out.println** (para saída de dados)

##  Como Executar o Projeto

###  Clonar o Repositório
```sh
git clone https://github.com/seu-usuario/ContaBanco.git
cd ContaBanco
```

###  Compilar o Código
```sh
javac src/ContaTerminal.java
```

###  Executar o Programa
```sh
java -cp src ContaTerminal
```

##  Exemplo de Entrada e Saída

### Entrada do Usuário:
```
Por favor, digite o número da Conta:
1021
Por favor, digite o número da Agência:
067-8
Por favor, digite o nome do Cliente:
MARIO ANDRADE
Por favor, digite o saldo:
237.48
```

### Saída Esperada:
```
Olá MARIO ANDRADE, obrigado por criar uma conta em nosso banco, sua agência é 067-8, conta 1021 e seu saldo 237.48 já está disponível para saque.
```

##  Autor
Projeto desenvolvido por @AlineSilv

