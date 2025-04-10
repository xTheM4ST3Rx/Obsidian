
### Formato de Prompt 
*Teste realizado (10/04/2025)*

| Formato           | Clareza para IA | Compatibilidade | Legibilidade | Estilo                  | Funciona sem `:` |
| ----------------- | --------------- | --------------- | ------------ | ----------------------- | ---------------- |
| `ROLE:` `ACTION:` | ⭐⭐⭐⭐⭐           | ⭐⭐⭐⭐⭐           | ⭐⭐⭐⭐⭐        | Profissional / Clean    | ✅ Sim            |
| `🧑‍💼 Role:`     | ⭐⭐⭐⭐            | ⭐⭐⭐⭐            | ⭐⭐⭐⭐         | Visual / Criativo       | ⚠️ Parcial       |
| `- Role:`         | ⭐⭐⭐⭐            | ⭐⭐⭐⭐            | ⭐⭐⭐⭐         | Neutro / Markdown-style | ✅ Sim            |
| `Role` `Action`   | ⭐⭐⭐             | ⭐⭐⭐             | ⭐⭐⭐          | Simples / Rápido        | ✅ Sim            |
| Texto corrido     | ⭐⭐              | ⭐⭐              | ⭐⭐           | Desorganizado           | ❌ Não se aplica  |
### 📊 Tabela Comparativa dos Frameworks de Prompt
*Teste realizado (10/04/2025)*

| Framework | Estrutura Principal                     | Foco Principal        | Melhor para...                                             | Nível de Detalhe | Quando evitar                                |
|-----------|------------------------------------------|------------------------|-------------------------------------------------------------|------------------|-----------------------------------------------|
| RACE      | Role, Action, Context, Explanation       | Instrução de tarefa    | Criar prompts objetivos para tarefas bem definidas          | Médio            | Processos vagos ou criativos demais            |
| CARE      | Context, Action, Result, Example         | Resultado claro        | Briefings de conteúdo e design com exemplo esperado         | Médio            | Quando não se sabe o exemplo desejado          |
| ROSES     | Role, Objective, Scenario, Expected, Steps | Planejamento detalhado | Tarefas longas ou com múltiplas etapas                      | Alto             | Situações muito simples ou diretas             |
| APE       | Action, Purpose, Execution               | Agilidade + clareza    | Tarefas rápidas e diretas com foco em resultado             | Baixo/Médio      | Projetos mais complexos e analíticos           |
| CREATE    | Character, Request, Examples, Adjustment, Type, Extras | Criação criativa       | Prompts criativos com controle total da saída esperada      | Alto             | Pedidos simples com estrutura fixa             |
| COAST     | Context, Objective, Actions, Scenario, Task | Diagnóstico + Solução | Análises, correção de fluxo, ou estruturação de sistema     | Alto             | Tarefas que não envolvam problema/situação     |
| PAIN      | Problem, Action, Information, Next Steps | Solução de problemas   | Identificar gargalos e planejar melhorias                   | Alto             | Processos criativos ou exploratórios           |
| TAG       | Task, Action, Goal                       | Simplicidade prática   | Resumos rápidos, microbriefings, ou tarefas pequenas        | Baixo            | Projetos estratégicos e detalhados             |
| RISE      | Role, Input, Steps, Execution            | Execução passo a passo | Planejar e executar ações com clareza de processo           | Médio/Alto       | Casos com pouca clareza do objetivo final      |
| CREO      | Context, Request, Explanation, Outcome   | Explicação + resultado | Entregas de conteúdo estruturado com propósito claro        | Médio            | Projetos técnicos muito específicos            |

## 📌 Sugestões de uso por cenário
*Teste realizado (10/04/2025)*

| Cenário                                                     | Framework Ideal      | Motivo                                                                 |
|-------------------------------------------------------------|----------------------|------------------------------------------------------------------------|
| Criar um prompt rápido para geração de texto simples        | **TAG** ou **APE**   | Menos estrutura, mais velocidade                                       |
| Planejar uma tarefa técnica com etapas                      | **ROSES** ou **RISE**| Divide bem o processo em objetivos claros e passos                     |
| Explicar um problema no fluxo de um sistema                 | **PAIN** ou **COAST**| Ideal pra diagnosticar e guiar melhorias                               |
| Produzir conteúdo criativo com parâmetros específicos       | **CREATE**           | Dá controle fino sobre a criação de conteúdo                           |
| Criar conteúdo com base em briefing com exemplo             | **CARE** ou **CREO** | Mostra o que se quer e como deve parecer no final                      |
| Delegar uma tarefa com papel claro                          | **RACE** ou **RISE** | Especifica o papel, ação e resultado esperado                          |

