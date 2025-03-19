# Jogo dos Dados

![Jogo dos Dados](https://i.imgur.com/YkJPhKz.gif)

## Introdução

Um jogo de tabuleiro virtual onde você compete contra o computador em uma corrida até a linha de chegada. Os jogadores avançam com base nos valores obtidos no lançamento de dados, com eventos especiais que podem ajudar ou atrapalhar seu progresso.

## Funcionalidades

- **Sistema de Turnos**: Alterna entre jogador e computador
- **Lançamento de Dados**: Sorteia valores de 1 a 6 para determinar o avanço
- **Eventos Especiais**:
  - **Avanço Extra**: Ganhe 3 casas extras nas posições 5, 10, 15 e 25
  - **Recuo**: Volte 2 casas nas posições 7, 13 e 20
- **Linha de Chegada**: Primeiro jogador a alcançar ou ultrapassar a posição 30 vence

## Como utilizar

1. Clone o repositório ou baixe o código fonte.
2. Abra o terminal ou o prompt de comando e navegue até a pasta raiz
3. Utilize o comando abaixo para restaurar as dependências do projeto.

```
dotnet restore
```

4. Em seguida, compile a solução utilizando o comando:

```
dotnet build --configuration Release
```

5. Para executar o projeto compilando em tempo real

```
dotnet run --project JogoDosDados.ConsoleApp
```

6. Para executar o arquivo compilado, navegue até a pasta `./JogoDosDados.ConsoleApp/bin/Release/net8.0/` e execute o arquivo:

```
JogoDosDados.ConsoleApp.exe
```

## Arquitetura

O projeto está estruturado como um aplicativo de console simples:

- **Program.cs**: Contém toda a lógica do jogo, incluindo o loop principal, o sistema de turnos e a implementação dos eventos especiais

## Requisitos

- .NET SDK (recomendado .NET 8.0 ou superior) para compilação e execução do projeto.
