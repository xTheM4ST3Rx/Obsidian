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
- [Exemplo Prático: Aplicação React com Vite](#exemplo-prático-aplicação-react-com-vite)
- [Conclusão](#conclusão)

---

## Introdução

Docker permite que você empacote uma aplicação e todas as suas dependências (bibliotecas, ferramentas e configurações) em um ambiente isolado, chamado **contêiner**. Dessa forma, a aplicação roda de forma consistente em qualquer ambiente, seja na máquina do desenvolvedor, em servidores on-premise ou na nuvem.

---

## Conceitos Básicos

### Dockerfile

- **O que é?**  
  Um arquivo de texto que atua como uma “receita” para construir uma imagem Docker.
  
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
  - Construída em **camadas**, permitindo a reutilização e otimização durante o processo de criação.
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
  A criação e atualização de ambientes se tornam automáticas por meio do Dockerfile e dos pipelines de CI/CD.

---

## Exemplo Prático: Aplicação React com Vite

A seguir, um exemplo de Dockerfile para uma aplicação React criada com Vite. Utilizaremos uma abordagem de multi-stage build para otimizar a imagem final.

### Estrutura do Projeto

Suponha que você já tenha criado sua aplicação React com Vite, com a seguinte estrutura básica:

