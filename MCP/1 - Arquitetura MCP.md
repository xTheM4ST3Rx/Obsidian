# 🛠️Tools
- São ferramentas que realizam ações. Elas são controladas pelo modelo , ou seja, **a própria LLM decide quando chamar**.
- **Autodiscovery**: LLM possui formas de entender quais tools estão disponíveis.

___
  
- # 🗂️Resources
- Permite que servidores disponibilizem dados que podem ser lidos clients e usado como contexto pelo LLM.
- Resources são controlados pelo client (Application-controlled), ou seja, **o cliente decide quando usar e não o modelo**.
- **Diferente tipos de dados:** Arquivos, Banco de dados, respostas de API, Imagens, Arquivos de Log.
- Cada resource possui seu próprio URI.
##### Exemplos:
- screen://host/image1
- file://caminho/file.pdf
- postgres://database/customers/schema

___
# 🖥️Prompts
- Permite que o server defina templates de prompt para que os clients possam usar.
- Prompts são "User-controlled", ou seja, os prompts ficam disponíveis, mas o usuário precisa "selecionar"
- Podem ser templates estáticas, dinâmicos passando parâmetros, inclusive pegando contexto de um resource.
- Dependendo da ferramenta pode ser utilizada com o "/"


___
# 🔌Formatos de Comunicação

##### 🐣STDIO
- O client MCP executa o servidor MCP como subprocesso.
- O servidor recebe mensagens JSON-RPC em sua entrada padrão (stdin) e escreve respostas para sua saída padrão (stdout)
- Comunicação local, onde o clliente e o servidor estão na mesma máquina.
- Simples e o mais comum de se ver no dia a dia
##### 🐣SSE (Server Sent Events)
- O cliente abre uma conexão SSE com o servidor, e o servidor enviar mensagens como eventos SSE usando HTTP
- Forma utilizada para acessar um Servidor MCP de forma remota (ex: Copilot Studio)
- Bem mais complexo de se desenvolver pelo fato de haver diversos fatores envolvidos, como segurança, controle de acesso, rate limiting.


