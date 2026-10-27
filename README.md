# Projeto de QA — Testes Manuais Funcionais | Swag Labs

Desafio de projeto do curso **"O Dia a Dia de um QA: A Prática de Testes Manuais Funcionais"** (DIO).

A aplicação testada é o [Swag Labs](https://www.saucedemo.com), uma loja virtual de demonstração. O foco está na jornada de compra: adicionar e remover produtos do carrinho e finalizar o pedido.

## 📂 Documentação

| # | Documento | Conteúdo |
|---|-----------|----------|
| 1 | [Fluxo de trabalho e ciclo de vida do bug](01_fluxo_trabalho_e_bugs.pdf) | Status das tarefas, ciclo de vida do bug, informações mínimas de um defeito e regras de trabalho |
| 2 | [User Stories](02_user_stories.pdf) | 2 histórias de usuário, com regras de negócio e critérios de aceite |
| 3 | [Mind map](03_mind_map.pdf) | Mapa mental da US 1 (Adicionar produto ao carrinho), com rastreabilidade para os casos de teste |
| 4 | [Casos de teste — Step-by-Step](04_casos_step_by_step.pdf) | CT-01 e CT-02, com pré-condições, dados de teste e o resultado esperado de cada passo |
| 5 | [Casos de teste — BDD](05_casos_BDD.pdf) | CT-BDD-01 e CT-BDD-02, escritos em Gherkin (Dado / Quando / Então) |
| 6 | [Plano e ciclo de testes](06_plano_e_ciclo_de_testes.pdf) | Objetivo, escopo, estratégia, ambiente, critérios de entrada e saída, ciclo de testes e riscos |

## 🔎 Rastreabilidade

| User Story | Critérios | Casos de teste |
|------------|-----------|----------------|
| US 1 — Adicionar produto ao carrinho | CA1, CA2 | CT-01, CT-BDD-01 |
| US 1 — Adicionar produto ao carrinho | CA3 | CT-02, CT-BDD-02 |

## 🛠️ Abordagem

- **Tipo:** teste funcional caixa-preta, manual
- **Técnicas:** casos step-by-step e BDD
- **Ambiente:** Google Chrome (desktop), em https://www.saucedemo.com, com o usuário `standard_user`
- **Fluxo:** Backlog → A fazer → Em andamento → Em teste → Concluído

## 📚 Aprendizados

- Escrever User Stories com critérios de aceite que possam ser testados
- Usar um mapa mental para levantar cenários positivos, negativos e riscos
- Transformar critérios de aceite em casos de teste nos formatos step-by-step e BDD
- Organizar o trabalho de QA em um plano de testes e em um ciclo de vida de bugs
