# 🚗 Sistema de Gerenciamento de Estacionamento - Desafio DIO .NET

Este projeto foi desenvolvido como parte do desafio proposto no módulo de Fundamentos da trilha .NET da DIO. O objetivo principal foi aplicar os conhecimentos iniciais da linguagem C# e conceitos de programação orientada a objetos para resolver um problema prático.

## 📝 Descrição do Projeto

![Diagrama de classe estacionamento](diagrama_classe_estacionamento.png)

O sistema simula um estacionamento simples que permite ao usuário:

- **Cadastrar veículos** por meio da inserção da placa
- **Remover veículos**, informando o tempo de permanência no local e calculando o valor a ser cobrado com base no preço inicial e preço por hora
- **Listar veículos** atualmente estacionados

A aplicação foi estruturada com base em uma classe chamada **Estacionamento**, que contém os seguintes membros:

- **precoInicial (decimal):** valor fixo cobrado no momento da entrada
- **precoPorHora (decimal):** valor adicional cobrado por cada hora de permanência
- **veiculos (List\<string\>):** lista contendo as placas dos veículos cadastrados

Também foram implementados três métodos principais:

- **AdicionarVeiculo():** adiciona uma placa à lista de veículos
- **RemoverVeiculo():** remove uma placa após calcular e exibir o valor total a ser pago
- **ListarVeiculos():** exibe todos os veículos atualmente estacionados ou uma mensagem caso não haja nenhum

## 🛠️ Tecnologias Utilizadas

- C#
- .NET
- Programação orientada a objetos

## 🎯 Aprendizados

Durante o desenvolvimento, reforcei conceitos fundamentais como:

- Manipulação de listas em C#
- Criação de classes e métodos
- Entrada e saída de dados via terminal
- Controle de fluxo com estruturas condicionais e loops

## 👨‍💻 Desenvolvedor

Desenvolvido como parte do desafio da **Trilha .NET** da [DIO](https://www.dio.me).

---

## 📄 Licença

Este projeto está sob a licença MIT.

---

⭐ **Gostou do projeto? Deixe uma estrela!** ⭐
