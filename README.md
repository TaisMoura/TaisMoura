# Olá! Eu sou a Tais Moura 👋

### Backend Developer | Java | Spring Boot | Spring AI

Profissional com experiência em Controladoria e Finanças, atualmente direcionando minha carreira para Tecnologia, com foco em desenvolvimento backend.

Tenho experiência prática em projetos utilizando Java, Spring Boot, APIs REST, SQL, JPA/Hibernate, Docker, Git/GitHub, testes automatizados e Spring AI.

Meu objetivo é atuar no desenvolvimento de software, com foco em Backend, Java, APIs REST e sistemas corporativos.

---

## 👩‍💻 Sobre mim

Minha experiência profissional em Finanças e Controladoria me permite unir conhecimento de negócio com desenvolvimento de software.

Tenho interesse em desenvolver soluções de software que resolvam problemas reais de negócio, unindo conhecimento financeiro e tecnologia.

- Desenvolvimento Backend
- Sistemas financeiros
- APIs REST
- Automação de processos
- Inteligência Artificial
- Dados

---

## 🚀 Tecnologias

### Backend

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![Spring AI](https://img.shields.io/badge/Spring%20AI-6DB33F?style=for-the-badge&logo=spring&logoColor=white)

### Banco de Dados

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=for-the-badge&logo=databricks&logoColor=white)

### Ferramentas

![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)

### Testes

JUnit 5 • Mockito • Spring Boot Test • MockMvc

### Conceitos

REST APIs • Clean Architecture • DDD • Repository Pattern • Testes Automatizados

---
## 📜 Certificados

### ☕ Java

- Fundamentos Para Começar a Programar em Java
- Java e a Arte da Abstração com Classes e Encapsulamento
- Programando o Mundo Real com Orientação a Objetos no Java]
- Herança e Polimorfismo em Java
- Imersão Prática com Collections e Outras Classes Úteis do Java
- Dominando Interfaces e Lambda em Java
- Boas Práticas, Padrões e Dados no Java
- SOLID e Clean Code em Java
- Design Patterns com Java

### 🌱 Spring Boot e Backend

- Criando sua Primeira API REST com Spring Boot
- Potencializando Sua Produtividade com Spring Boot
- Conectando sua API com Banco de Dados Através do Spring Data
- Consumindo APIs Externas com Spring Cloud OpenFeign
- Simplificando a Segurança em APIs REST com Spring Security

### 🤖 Inteligência Artificial

- Assistente Virtual Inteligente por Voz
- Desenvolvendo API com Reconhecimento de Fala e Spring Boot
- Introdução à Engenharia de Prompts
- Fundamentos da IA Moderna
- Copilotos com IA no Desenvolvimento de Soluções

  https://github.com/TaisMoura/certificados.git

# ⭐ Projetos em destaque

## 💰 Budgeting Spring AI

Aplicação backend para gerenciamento financeiro integrada com Inteligência Artificial.

O projeto permite processar comandos financeiros por voz, transformar áudio em texto, utilizar Spring AI com Tool Calling e executar casos de uso responsáveis pela persistência e consulta das transações.

### Principais tecnologias

- Java
- Spring Boot
- Spring AI
- OpenAI
- MySQL
- JPA/Hibernate
- Docker
- Gradle
- JUnit
- Mockito

### Minha contribuição

Além da implementação original do projeto, desenvolvi uma funcionalidade de **resumo financeiro**, permitindo consultar informações consolidadas das transações.

A funcionalidade utiliza o endpoint **GET `/transactions/summary`**.

### Informações retornadas

- Quantidade de transações
- Valor total
- Valor médio
- Maior transação
- Menor transação

### Implementação

A funcionalidade foi desenvolvida utilizando o caso de uso **`GetFinancialSummaryUseCase`**, mantendo a regra de negócio isolada da camada HTTP.

### Testes

Foram implementados testes automatizados para validar:

- Cálculo do resumo financeiro
- Comportamento com diferentes transações
- Resposta do endpoint
- Integração com a camada de aplicação

**Como executar**

`docker compose up -d`

`./gradlew test`

`./gradlew bootRun`

### 🔗 Repositório

[Ver projeto completo no GitHub]
