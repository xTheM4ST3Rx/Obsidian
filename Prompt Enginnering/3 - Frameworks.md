___
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
___
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
___
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
___
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
___
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
___
### 🏝️Coast
- **Context**: Forneça informações básicas
- **Objective**: Forneça a meta esperada
- **Actions**: Forneça as ações necessárias
- **Scenario**: Forneça o seu problema
- **Task**: Definir uma tarefa a ser realizada
```ts
CONTEXT:
Estou criando uma plataforma de mentoria online onde especialistas oferecem sessões individuais para iniciantes em suas áreas (ex: design, marketing, programação). O site será responsivo e precisa passar credibilidade e facilidade de uso.

OBJECTIVE:
Desenvolver o layout inicial da home page com foco em conversão: o usuário precisa entender o valor da mentoria em poucos segundos e ser incentivado a agendar uma sessão.

ACTIONS:
- Criar a hierarquia visual da página (hero, benefícios, depoimentos, CTA) 
- Escrever os textos principais da landing page
- Sugerir um esquema de cores moderno e profissional
- Incluir ideias para elementos interativos (ex: cards de mentor, carrossel de avaliações)

SCENARIO:
Muitos visitantes entram no site, mas poucos interagem com o botão de “Agendar Mentoria”. Acredito que o layout e o conteúdo visual/textual ainda não estão comunicando bem o diferencial da proposta.

TASK:
Crie uma proposta de estrutura para a home page, incluindo uma descrição por seção (em texto), sugestões de copy e elementos visuais que gerem confiança e ação imediata.
```
___
### 💔Pain
- **Problem**: Descreva seu problema
- **Action**: Definir uma tarefa a ser realizada
- **Information**: Informações para melhorar
- **Next Steps**: Explique os recursos a serem realizado
```ts
PROBLEM:
Usuários estão abandonando o formulário de cadastro da minha aplicação antes de concluir. A taxa de conversão está muito baixa, mesmo com tráfego qualificado vindo de campanhas pagas.

ACTION:
Analise o fluxo atual do formulário e sugira melhorias de UX/UI para reduzir o abandono e aumentar a taxa de finalização.

INFORMATION:
- O formulário possui 6 etapas 
- Não há barra de progresso visível 
- Alguns campos pedem informações sensíveis logo no início (CPF, telefone) 
- A versão mobile representa 80% dos acessos    
- Feedback de erro é genérico e só aparece ao final

NEXT STEPS:
- Reorganizar os campos para capturar o essencial primeiro
- Inserir barra de progresso clara e animada 
- Dividir em menos etapas ou tornar o fluxo mais leve visualmente
- Personalizar mensagens de erro e mostrar validação em tempo real
- Fazer A/B testing com duas versões de formulário mais simples
```
___
### 🔰Tag
- **Task**: Descreva seu problema
- **Action**: Definir uma tarefa a ser realizada
- **Goal**: Explicar o objetivo final
```ts
TASK:
Tenho um chatbot que responde bem a perguntas simples, mas se perde quando a conversa se estende por várias mensagens. Ele não mantém o contexto adequadamente.

ACTION:
Sugira melhorias na forma como armazeno e reutilizo o histórico de mensagens para manter o contexto da conversa com qualidade, usando a API da OpenAI.

GOAL:
Melhorar a coerência das respostas em diálogos mais longos, garantindo que o chatbot entenda o que foi dito anteriormente e responda de forma contextual e natural, como uma conversa humana fluida.
```
___
### 🚀Rise
- **Role**: Especifique a função
- **Input**: Definir contexto e instruções
- **Steps**: Passo a passo
- **Execution**: Explicar o resultado final
```ts
ROLE:
Você é um UX Writer com foco em transformar conteúdos técnicos em mensagens simples, acessíveis e com tom amigável.

INPUT:
Estou desenvolvendo uma interface de onboarding para um aplicativo de gestão financeira pessoal. O público é leigo em finanças, mas quer começar a organizar melhor o dinheiro. A interface precisa ser simples, acolhedora e educativa sem parecer chata.

STEPS:
- Escrever os textos para cada etapa do onboarding (máximo 3 etapas) 
- Usar linguagem inclusiva, simples e motivacional 
- Inserir CTA amigável ao final de cada etapa 
- Incluir sugestões de microtextos para botões e mensagens de ajuda

EXECUTION:
Gerar o conteúdo completo do onboarding em formato estruturado (título, subtítulo, CTA e mensagens de apoio), pronto para ser aplicado no app. O objetivo é que o usuário complete o onboarding com a sensação de que “organizar as finanças pode ser fácil”.
```
___
### 📝CREO
- **Context**: Forneça informações básicas
- **Request**: Definir uma tarefa a ser realizada
- **Explanation**: Explique a tarefa
- **Outcome**: Explicar o resultado final
```ts
CONTEXT:
Estou criando uma série de vídeos curtos para o Instagram, voltados a freelancers que estão começando a captar seus primeiros clientes. A ideia é entregar dicas práticas de forma leve e visual.

REQUEST:
Escreva o roteiro para um vídeo de até 60 segundos com o tema: “Como definir seu primeiro preço como freelancer”.

EXPLANATION:
O vídeo deve ter uma introdução rápida que chame atenção, um exemplo prático de cálculo de preço (sem complicar), e uma conclusão com dica bônus ou CTA. A linguagem precisa ser informal, mas passar autoridade. O público está começando e ainda tem medo de cobrar.

OUTCOME:
Receber um roteiro completo dividido em blocos (introdução, desenvolvimento, conclusão), pronto para ser narrado e transformado em conteúdo para Reels. O roteiro precisa informar, engajar e incentivar o seguidor a comentar ou salvar.
```
___
