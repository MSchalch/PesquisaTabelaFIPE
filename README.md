# 🚗 Pesquisa Tabela FIPE - Projeto Java com Spring Boot

Este projeto foi desenvolvido como parte de um **desafio** do curso **Programa One - Alura + Oracle**.

O objetivo do projeto é realizar consultas à **API pública da Tabela FIPE** para buscar informações sobre veículos (Carros, Motos e Caminhões). A aplicação é feita em **Java**, utilizando **Maven** para gerenciamento de dependências e **Spring Boot** para facilitar o desenvolvimento.

---

## ✅ Tecnologias utilizadas

- Java
- Maven
- Spring Boot
- API REST - [Tabela FIPE](https://deividfortuna.github.io/fipe/)
- Programação Orientada a Objetos (POO)
- Manipulação de JSON

---

## 🚀 Descrição do Projeto

A aplicação permite ao usuário:

1. Escolher o tipo de veículo: **Carro**, **Moto** ou **Caminhão**.
2. Consultar todas as **marcas** disponíveis para aquele tipo.
3. Selecionar uma marca e consultar os **modelos**.
4. Filtrar os modelos por um trecho do nome.
5. Selecionar um modelo e consultar os **anos** de fabricação.
6. Exibir todas as informações detalhadas, como **preço médio**, **combustível**, e **código FIPE**, para cada ano do modelo.

---

### 📌 Fluxo resumido:

1. Exibe menu com as opções: Carro, Moto ou Caminhão.
2. Realiza a consulta na API conforme a escolha.
3. Exibe lista de marcas → usuário escolhe o código.
4. Exibe lista de modelos → usuário pode filtrar pelo nome.
5. Consulta os anos do modelo escolhido.
6. Exibe detalhes de preço para cada ano.

---

## 🧑‍🎓 Autor: Matheus Schalch
