### 🏁RACE
- **Role**: Especifique a função
- **Action**: Mencione a ação necessária
- **Context**: Forneça informações básicas
- **Explanation**: Descreva o resultado que você deseja
```ts
ROLE:
Você é um especialista em UX/UI com foco em design de interfaces intuitivas.

ACTION:
Crie sugestões de layout para uma dashboard de análise de dados.

CONTEXT:
A dashboard será usada por gestores de marketing para visualizar KPIs como CAC, LTV, ROI e taxa de conversão, com dados atualizados em tempo real.

EXPLANATION:
O resultado deve ser uma descrição clara de como organizar os elementos visuais da interface (gráficos, filtros, menus, cores) para maximizar a compreensão e a usabilidade, com foco em tomada de decisão rápida.
```
### 💗CARE
- **Context**: Forneça informações básicas
- **Action**: Mencione a ação necessária
- **Result**: Forneça a meta esperada
- **Example**: Descreva o resultado que você deseja
```ts
CONTEXT:
Estou desenvolvendo uma landing page para um curso online de produtividade pessoal voltado para profissionais autônomos. O público-alvo tem entre 25 e 45 anos, já consome conteúdo de desenvolvimento pessoal, mas ainda não encontrou uma metodologia que consiga aplicar no dia a dia.

ACTION:
Crie uma estrutura de texto persuasiva para a landing page, incluindo título principal, subtítulo, tópicos de benefícios e uma chamada para ação (CTA).

RESULT:
Quero um texto que desperte curiosidade e confiança, levando o usuário a clicar no botão de inscrição.

EXAMPLE:
Título: “Descubra o Método Simples que Transformou a Produtividade de Mais de 5.000 Profissionais”  
Subtítulo: “Sem fórmulas mágicas. Apenas passos práticos que funcionam.”  
Benefícios:

- Organize seu dia em menos de 10 minutos
- Acabe com a procrastinação sem esforço
- Aumente seu foco em até 300%  
    CTA: “Quero ser mais produtivo agora!”
```
### 🌹ROSES
- **Role**: Especifique a função
- **Objective**: Descreva o resultado que você deseja
- **Scenario**: Forneça informações básicas
- **Expected solution**: Descreva o resultado que você deseja
- **Steps**: Descreva as etapas para o resultado que você deseja
```ts
ROLE:
Você é um engenheiro de software especializado em IA generativa com foco em aplicações práticas para negócios.

OBJECTIVE:
Criar um sistema de chatbot personalizado usando a API da OpenAI, que seja capaz de manter o contexto da conversa com usuários em sessões diferentes.

SCENARIO:
Estou desenvolvendo uma plataforma SaaS onde clientes podem conversar com assistentes virtuais treinados com dados específicos de seus negócios. O sistema será construído com TypeScript, NestJS no backend, e armazenará as conversas em banco de dados relacional. Queremos que o bot lembre interações passadas de um usuário para oferecer respostas mais inteligentes e contextuais.

EXPECTED SOLUTION:
Quero um plano detalhado de como estruturar o backend para lidar com armazenamento, recuperação e injeção de contexto na API da OpenAI, garantindo baixo custo e boa performance.

STEPS:
- Definir o modelo de dados para armazenar mensagens por usuário e sessão.
- Criar uma API que salve e recupere as mensagens por ID de usuário.
- Desenvolver um mecanismo de reconstrução de contexto a partir do histórico (usando summarization, se necessário).
- Integrar esse histórico no payload enviado à OpenAI API.
- Testar com diferentes volumes e ajustar para otimizar custo vs. desempenho.
- Implementar limites e estratégias de fallback para quando o histórico for muito longo.
```
### 🐒APE
- **Action**: Defina o trabalho a ser feito
- **Purpose**: Forneça a meta esperada
- **Execution**: Descreva o resultado que você deseja
```ts
ACTION:
Crie uma sequência de e-mails automatizados para um funil de vendas de um curso online de design gráfico.

PURPOSE:
O objetivo é aumentar a conversão de leads frios em compradores, conduzindo o usuário do primeiro contato até a decisão de compra em no máximo 5 e-mails.

EXECUTION:
Preciso que cada e-mail tenha:
- Um assunto chamativo
- Texto envolvente com gatilhos mentais (ex: autoridade, escassez) 
- Um CTA claro 
- Progresso lógico entre os e-mails (introdução, dor, solução, prova, urgência) 
 
Os e-mails devem ser curtos, com linguagem informal e focados em designers iniciantes que querem viver de freelas.
```
### 💡Create
- **Character**: Especifique a função
- **Request**: Definir uma tarefa a ser realizada
- **Examples**: Defina exemplos de saída
- **Adjustment**: Fornecer instruções de melhoria
- **Type of output**: Especifique o formato da saída
- **Extras**: Adicione mais contexto
```ts
CHARACTER:
Você é um redator publicitário sênior especializado em marcas modernas e descoladas.

REQUEST:
Crie 3 variações de slogan para uma marca de roupas sustentáveis voltada ao público jovem e urbano.

EXAMPLE:
- “Vista o agora, pense no futuro.”
- “Moda consciente, atitude impactante.”
- “Estilo com propósito.”

ADJUSTMENT:
Evite clichês como “verde”, “planeta” ou “ecológico”. Use linguagem jovem, criativa, com um toque de rebeldia leve.

TYPE OF OUTPUT:
Uma lista numerada com slogans curtos (máximo 8 palavras cada), sem explicações adicionais.

EXTRA:
O nome da marca é "VIRA", e ela se posiciona como uma marca sustentável, urbana e com pegada cultural. Os slogans serão usados em campanhas no Instagram, então precisam ter impacto visual e sonoro.
```
### 🏝️Coast
- **Context**: Forneça informações básicas
- **Objective**: Forneça a meta esperada
- **Actions**: Forneça as ações necessárias
- **Scenario**: Forneça o seu problema
- **Task**: Definir uma tarefa a ser realizada
```ts
CHARACTER:
Você é um redator publicitário sênior especializado em marcas modernas e descoladas.

REQUEST:
Crie 3 variações de slogan para uma marca de roupas sustentáveis voltada ao público jovem e urbano.

EXAMPLE:
- “Vista o agora, pense no futuro.”
- “Moda consciente, atitude impactante.”
- “Estilo com propósito.”

ADJUSTMENT:
Evite clichês como “verde”, “planeta” ou “ecológico”. Use linguagem jovem, criativa, com um toque de rebeldia leve.

TYPE OF OUTPUT:
Uma lista numerada com slogans curtos (máximo 8 palavras cada), sem explicações adicionais.

EXTRA:
O nome da marca é "VIRA", e ela se posiciona como uma marca sustentável, urbana e com pegada cultural. Os slogans serão usados em campanhas no Instagram, então precisam ter impacto visual e sonoro.
```
### 💔Pain
- **Problem**: Descreva seu problema
- **Action**: Definir uma tarefa a ser realizada
- **Information**: Informações para melhorar
- **Next Steps**: Explique os recursos a serem realizado
### 🔰Tag
- **Task**: Descreva seu problema
- **Action**: Definir uma tarefa a ser realizada
- **Goal**: Explicar o objetivo final
### 🚀Rise
- **Role**: Especifique a função
- **Input**: Definir contexto e instruções
- **Steps**: Passo a passo
- **Execution**: Explicar o resultado final
### 📝CREO
- **Context**: Forneça informações básicas
- **Request**: Definir uma tarefa a ser realizada
- **Explanation**: Explique a tarefa
- **Outcome**: Explicar o resultado final


