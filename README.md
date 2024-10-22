
# Sistema Bancário Simples

Este é um sistema bancário básico desenvolvido em Node.js. O usuário pode criar uma conta, verificar saldo, depositar e sacar dinheiro através da interface de terminal. Ele também possui armazenamento persistente de contas usando o sistema de arquivos.

## Funcionalidades:
- Criar uma nova conta
- Depositar dinheiro em uma conta
- Sacar dinheiro de uma conta
- Verificar o saldo da conta
- Sair do sistema

## Instalação

Para começar a usar o programa, siga os seguintes passos:

1. Clone o repositório ou faça o download do código-fonte.
2. Certifique-se de que o Node.js está instalado em sua máquina.
3. Instale as dependências necessárias executando:

```bash
npm install inquirer chalk
```

## Uso

Execute o programa com o seguinte comando:

```bash
node seu_programa.js
```

Siga as instruções no terminal para interagir com o sistema bancário.

### Comandos Exemplos:

- **Criar Conta**: Crie uma nova conta com um nome único.
- **Depositar**: Adicione dinheiro à sua conta especificando o nome da conta e o valor do depósito.
- **Consultar Saldo**: Mostra o saldo da conta.
- **Sacar**: Retira um valor especificado da sua conta.
- **Sair**: Encerra o sistema.

## Notas:

- Os dados da conta são armazenados na pasta `accounts` como arquivos JSON.
- Cada arquivo representa uma única conta com seu saldo.

## Dependências

- **inquirer**: Para prompts e interação no terminal.
- **chalk**: Para saída colorida no terminal.

## Licença

Este projeto é open-source e disponível para uso pessoal.

