🧾 -  **Dockerfile:**  
- Arquivo de texto que atua como uma “receita” para construir uma imagem Docker.
- Define a imagem base (com `FROM`), comandos de instalação e configuração (com `RUN`), arquivos a copiar (com `COPY` ou `ADD`), variáveis de ambiente e portas a expor.
- Automatiza o processo de build, garantindo padronização e replicação consistente dos ambientes.

🖼️ -  **Imagem :**  
-  Template imutável que contém o sistema de arquivos, bibliotecas, dependências, configurações e instruções necessárias para executar uma aplicação.
  
- Construída em camadas, permitindo a reutilização e otimização durante o processo de criação.

📦 -  **Contêiner:**  
- Um contêiner é uma instância em execução de uma imagem Docker. Ele funciona como um ambiente isolado que compartilha o kernel do sistema operacional do host, mas mantém a aplicação e suas dependências separadas, garantindo leveza e alta performance. Essa abordagem é bem diferente da virtualização tradicional, pois não há necessidade de carregar um sistema operacional completo dentro de cada contêiner 


**Comandos:**
`
```
docker
```
