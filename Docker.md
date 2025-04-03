🧾 -  **Dockerfile:**  
- Arquivo de texto que atua como uma “receita” para construir uma imagem Docker.
- Define a imagem base (com `FROM`), comandos de instalação e configuração (com `RUN`), arquivos a copiar (com `COPY` ou `ADD`), variáveis de ambiente e portas a expor.
- Automatiza o processo de build, garantindo padronização e replicação consistente dos ambientes.
---
🖼️ -  **Imagem :**  
-  Template imutável que contém o sistema de arquivos, bibliotecas, dependências, configurações e instruções necessárias para executar uma aplicação.
- Construída em camadas, permitindo a reutilização e otimização durante o processo de criação.
---
📦 -  **Contêiner:**  
- Instância em execução de uma imagem Docker.
- Fornece um ambiente isolado que utiliza o kernel do host, mantendo a aplicação e suas dependências separadas.
- Oferece leveza e alta performance, sem a necessidade de carregar um sistema operacional completo como em máquinas virtuais.
---




**Comandos:**
`
```
docker
```
