# DIO - Trilha .NET - Fundamentos  
[www.dio.me](https://www.dio.me)

## Projeto Estacionamento - Solução do Desafio

Este projeto foi desenvolvido como solução ao desafio da trilha .NET Fundamentos da DIO, onde foi implementado um sistema simples para gerenciar um estacionamento.

---

## Funcionalidades implementadas

- **Adicionar veículo:** Permite cadastrar um veículo informando sua placa.  
- **Remover veículo:** Remove um veículo existente, solicitando o tempo estacionado e calculando o valor a ser cobrado com base no preço inicial e preço por hora.  
- **Listar veículos:** Exibe todos os veículos atualmente estacionados, ou uma mensagem informando se não houver nenhum veículo.  
- **Menu interativo:** Interface simples no console para navegar entre as opções e encerrar o programa.

---

## Detalhes da implementação

- A classe `Estacionamento` contém os atributos `precoInicial`, `precoPorHora` e uma lista `veiculos` que armazena as placas dos veículos estacionados.
- O método `AdicionarVeiculo` lê a placa digitada pelo usuário e adiciona à lista.
- O método `RemoverVeiculo` verifica a existência do veículo, solicita o número de horas estacionadas, calcula o valor final usando a fórmula:  
  `valor = precoInicial + precoPorHora * horas`  
  e remove o veículo da lista.
- O método `ListarVeiculos` percorre a lista e exibe as placas, ou exibe mensagem caso esteja vazia.
- O programa exibe um menu de opções para o usuário escolher as operações.

---

## Como executar

1. Clone este repositório  
2. Navegue até a pasta do projeto  
3. Execute `dotnet run` no terminal para iniciar o programa  
4. Utilize o menu para testar as funcionalidades

---


---

## Conclusão

Este projeto cumpriu os requisitos do desafio proposto, demonstrando o uso básico de listas, manipulação de dados pelo console e lógica de cálculo em C#.

---


Obrigado por acompanhar meu projeto! 🚗🚙

