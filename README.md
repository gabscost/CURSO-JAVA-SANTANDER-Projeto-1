# CURSO-JAVA-SANTANDER-Projeto-1
#### Autores
- [Gleyson Sampaio](https://github.com/glysns)

## Sintaxe - Desafio

Vamos exercitar todo o conteúdo apresentado no módulo de Sintaxe codificando o seguinte cenário.

1. Crie o projeto `ContaBanco` que receberá dados via terminal contendo as características de conta em banco conforme atributos abaixo:
2. Dentro do projeto, crie a classe `ContaTerminal.java` para realizar toda a codificação do nosso programa.

###### Revise sobre regras de declaração de variáveis

| Atributo  | Tipo     | Exemplo   
| --------- | ---------| ------- 
| Numero    | Inteiro  | 1021 
| Agencia   | Texto    | 067-8
| Nome Cliente | Texto    | MARIO ANDRADE
| Saldo | Decimal |237.48


###### Revise sobre terminal, main args e a classe Scanner
2. Permita que os dados sejam inseridos via terminal sendo que o usuário receberá a mensagem de qual informação será solicitada, exemplo:

* Programa: "Por favor, digite o número da Agência !"
* Usuário: 1021 *(depois ENTER para o próximo campo)* 

###### Revise sobre concatenação e classe String com método concat

3. Depois de todas as informações terem sido inseridas, o sistema deverá exibir a seguinte mensagem:

*"Olá [Nome Cliente], obrigado por criar uma conta em nosso banco, sua agência é [Agencia], conta [Numero] e seu saldo [Saldo] já está disponível para saque".*

Os campos em [ ] devem ser alterados pelas informações que forem inseridas pelos usuários.

## Exercício operadores
Crie o programa chamado `BancoTerminal.java` para implementar o algorítmo conforme abaixo:

O programa deverá simular uma operação de saque onde:

1. Terá uma variável denominada `saldo` do tipo double contendo o valor inicial igual a 25;
1. Terá uma variável denominada de `valor solicitado` do tipo double contendo o valor inicial igual a 18;
1. Criar uma expressão relacional para que caso o saldo seja `maior` que o valor solicitado, o saldo recebe o novo valor como saldo é igual saldo menos o valor solicitado. Caso o saldo seja menor que o valor solicitado, devemos exibir a mensagem "Saldo insuficiente";
1. Imprima o valor do saldo;

1. Em seguida, realize a mesma execução do programana agora com os valores saldo igual a 15 e valor solicitado igual a 22 e exiba o resultado;
