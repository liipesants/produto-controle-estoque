#  Produto com Controle de Estoque

Projeto desenvolvido em **C#** com foco na aplicação prática de **Encapsulamento** e aplicação de **regras de negócio** para garantir a integridade dos dados em um sistema de controle de estoque.

---

##  Objetivo

Desenvolver uma classe `Produto` contendo:

- `Nome`
- `Preço`
- `QuantidadeEmEstoque`

Aplicando validações para impedir estados inválidos no objeto.

---

##  Regras de Negócio

- O preço nunca pode ser negativo.
- A quantidade em estoque nunca pode ser negativa.
- O estoque não pode ser alterado diretamente.
- O estoque só pode ser modificado através dos métodos:
  - `AdicionarEstoque(int quantidade)`
  - `RemoverEstoque(int quantidade)`
- Não é permitido remover mais itens do que existem em estoque.

---

##  Por que impedir alteração direta do estoque?

Em sistemas reais, permitir alteração direta de atributos pode gerar inconsistências, como:

- Estoque negativo
- Dados manipulados incorretamente
- Falhas na lógica do sistema
- Problemas financeiros

Ao utilizar métodos controlados para alterar o estoque, garantimos que todas as regras de negócio sejam respeitadas, aumentando a segurança e confiabilidade da aplicação.

---

##  Conceitos Aplicados

- Encapsulamento
- Validação de dados
- Regras de negócio
- Métodos de controle
- Organização de classe em C#

---

## Tecnologias Utilizadas

- C#
- .NET
- Aplicação Console
