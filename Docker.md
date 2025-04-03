🧾**Dockerfile:**  
- É um arquivo de texto que funciona como uma "receita" para construir uma imagem Docker. Nele, você define, por exemplo, qual imagem base usar (por meio da instrução `FROM`), quais comandos executar durante o build (como `RUN` para instalar pacotes), quais arquivos copiar para dentro do contêiner (`COPY` ou `ADD`), além de definir variáveis de ambiente e portas a serem expostas. Essa automatização facilita a padronização e a replicação de ambientes ​

🖼️**Imagem :**  
- Uma imagem é um template imutável que contém tudo o que é necessário para criar um contêiner – desde o sistema de arquivos com bibliotecas e dependências até as configurações e instruções para executar a aplicação. As imagens são construídas em camadas, o que permite reutilização e otimização durante o processo de build 

📦**Contêiner:**  
- Um contêiner é uma instância em execução de uma imagem Docker. Ele funciona como um ambiente isolado que compartilha o kernel do sistema operacional do host, mas mantém a aplicação e suas dependências separadas, garantindo leveza e alta performance. Essa abordagem é bem diferente da virtualização tradicional, pois não há necessidade de carregar um sistema operacional completo dentro de cada contêiner 


**Comandos:**
`
```
docker
```
