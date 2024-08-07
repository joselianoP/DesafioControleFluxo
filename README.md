# DesafioControleFluxo

## Descrição
O projeto `DesafioControleFluxo` é um programa Java simples que recebe dois números inteiros como parâmetros e imprime uma contagem baseada nesses números. Se o primeiro número for maior que o segundo, o programa lança uma exceção customizada chamada `ParametrosInvalidosException`.

## Estrutura do Projeto
O projeto possui a seguinte estrutura:

DesafioControleFluxo/
│
├── src/
│ ├── main/
│ ├── java/
│ ├── ParametrosInvalidosException.java
│ └── Contador.java
│
└── README.md

## Classes

### `ParametrosInvalidosException`
Classe que representa uma exceção customizada para o caso onde o segundo parâmetro é menor que o primeiro.

### `Contador`
Classe principal que contém a lógica de leitura dos parâmetros e contagem.

## Como Executar

1. **Clone o repositório**:
    ```sh
    git clone <URL do repositório>
    cd DesafioControleFluxo
    ```

2. **Compile as classes**:
    ```sh
    javac src/main/java/ParametrosInvalidosException.java src/main/java/Contador.java -d out
    ```

3. **Execute o programa**:
    ```sh
    java -cp out Contador
    ```

## Exemplo de Uso

Ao executar o programa, você será solicitado a inserir dois números inteiros. O programa imprimirá a contagem do menor número até o maior. Exemplo:

