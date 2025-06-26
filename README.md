# licitei-fullstack-challenge

## 🎬 Desafio: Sistema de Reserva de Assentos de Cinema

### 🎯 Objetivo

Desenvolver uma aplicação fullstack para gerenciamento de sessões de cinema, incluindo o cadastro de filmes e sessões, controle de reservas de assentos e geração de relatórios sobre ocupação e vendas. A aplicação também deve contar com um agente de IA que interprete comandos em linguagem natural para ações básicas e consultas.

---

## ✅ Funcionalidades

### 1. Cadastro de Filmes e Sessões
- Adicionar, editar e remover **filmes**.
- Adicionar, editar e remover **sessões** (data, horário e sala).
- Cada filme deve conter:
  - Título
  - Descrição
  - Duração
  - Gênero
  - Classificação indicativa
- Cada sessão deve conter:
  - ID do filme
  - Data e horário
  - Sala e layout de assentos (simples, ex: 5x10)
  - Preço por ingresso

### 2. Reserva de Assentos
- Registrar reservas e cancelamentos.
- Cada movimentação deve incluir:
  - ID da sessão
  - Assentos selecionados
  - Quantidade de ingressos
  - Data da reserva
  - Tipo de movimentação (reserva ou cancelamento)

### 3. Dashboard
- Lista atualizada de sessões e ocupação
- Sessões mais procuradas

### 4. Agente de IA
- Um simples chat com AI para consultar os dados das seções:
- "Quais os filmes para a semana?"
- "Quais os filme para hoje?"
- "Qual a sinopse do filme(?)"


---

## 🛠️ Tecnologias Recomendadas

### Front-end
- React

### Back-end
- TypeScript, Python ou qualquer linguagem de sua preferência
- Banco de dados relacional

> ⚠️ Instruções claras de instalação, configuração e execução devem estar no `README.md` da entrega.

---

## 📦 Organização do Projeto

O projeto pode seguir uma das abordagens abaixo:

### Monorepo
- Front-end e back-end organizados em subpastas dentro do mesmo repositório.

### Repositórios Separados
- Um repositório para o front-end e outro para o back-end.

> Em qualquer estrutura, é **obrigatório realizar o deploy completo** da aplicação.

---

## 🚀 Entrega

1. Faça um **fork** deste repositório.
2. Desenvolva a aplicação com base nos requisitos.
3. Faça o **deploy** (front e back).
4. Atualize este `README.md` com os links e instruções.
5. Envie o link do repositório finalizado.

---

## ✅ Critérios de Avaliação

| Critério                | Descrição                                                                 |
|-------------------------|---------------------------------------------------------------------------|
| **Design da Aplicação** | Organização visual, usabilidade e clareza da interface                   |
| **Qualidade do Código** | Boas práticas, organização, legibilidade e modularidade                  |
| **Arquitetura**         | Separação de responsabilidades, padrões utilizados, escalabilidade       |
| **Funcionalidade**      | Implementação correta e completa das funcionalidades                     |
---

Boa sessão!
