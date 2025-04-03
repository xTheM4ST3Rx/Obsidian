# Guia Docker: Conceitos Básicos e Boas Práticas

Docker é uma plataforma open source que simplifica a criação, distribuição e execução de aplicações em contêineres. Este guia apresenta os conceitos fundamentais de Docker de forma clara e fácil de entender.

---

## Sumário

- [Introdução](#introdução)
- [Conceitos Básicos](#conceitos-básicos)
  - [Dockerfile](#dockerfile)
  - [Imagem](#imagem)
  - [Contêiner](#contêiner)
- [Vantagens do Uso do Docker](#vantagens-do-uso-do-docker)
- [Exemplo Prático](#exemplo-prático)
- [Conclusão](#conclusão)

---

## Introdução

Docker permite que você empacote uma aplicação e todas as suas dependências (bibliotecas, ferramentas, configurações) em um ambiente isolado, chamado **contêiner**. Dessa forma, a aplicação roda de forma consistente em qualquer ambiente, seja no computador do desenvolvedor, em servidores on-premise ou na nuvem.

---

## Conceitos Básicos

### Dockerfile

- **O que é?**  
  Um arquivo de texto que funciona como uma “receita” para construir uma imagem Docker.
  
- **Principais Funções:**
  - Define a **imagem base** a ser utilizada através da instrução `FROM`.
  - Executa comandos durante o build com `RUN` (ex.: instalar pacotes).
  - Copia arquivos para dentro do contêiner usando `COPY` ou `ADD`.
  - Define variáveis de ambiente com `ENV`.
  - Especifica quais portas o contêiner deverá expor com `EXPOSE`.

- **Benefícios:**  
  Automatiza o processo de construção da imagem, garantindo padronização e facilitando a replicação de ambientes.

---

### Imagem

- **O que é?**  
  Um template imutável que contém tudo o que é necessário para criar um contêiner.
  
- **Conteúdo de uma Imagem:**
  - Sistema de arquivos com bibliotecas e dependências.
  - Configurações e instruções para executar a aplicação.
  
- **Características Importantes:**
  - Construída em **camadas**, permitindo a reutilização e otimização do processo de build.
  - Armazenada em repositórios (como o Docker Hub) para fácil compartilhamento e versionamento.

---

### Contêiner

- **O que é?**  
  Uma instância em execução de uma imagem Docker.
  
- **Características:**
  - Funciona como um ambiente isolado que utiliza o kernel do sistema operacional do host.
  - Garante que a aplicação e suas dependências operem de forma separada do sistema hospedeiro.
  
- **Vantagens:**
  - **Leveza:** Não há necessidade de carregar um sistema operacional completo, como em máquinas virtuais.
  - **Performance:** Uso eficiente dos recursos do host, possibilitando a execução de vários contêineres simultaneamente.

---

## Vantagens do Uso do Docker

- **Portabilidade e Consistência:**  
  A aplicação empacotada em um contêiner roda da mesma forma em qualquer ambiente.
  
- **Leveza:**  
  Os contêineres compartilham o kernel do host, consumindo menos recursos do que máquinas virtuais.
  
- **Facilidade de Distribuição:**  
  Imagens podem ser facilmente versionadas, armazenadas em repositórios e distribuídas para diferentes ambientes.
  
- **Automação:**  
  A criação e a atualização de ambientes se tornam automáticas por meio do Dockerfile e dos pipelines de CI/CD.

---

## Exemplo Prático

A seguir, um exemplo simples de um Dockerfile para uma aplicação baseada em Ubuntu:

```dockerfile
# Definir a imagem base
FROM ubuntu:18.04

# Atualizar repositórios e instalar o Java 8
RUN apt-get update && apt-get install -y openjdk-8-jdk

# Copiar um arquivo de boas-vindas para dentro do contêiner
RUN touch /arquivo-de-boas-vindas

# Comando padrão ao iniciar o contêiner (pode ser sobrescrito)
CMD ["bash"]
