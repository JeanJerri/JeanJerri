<h1 align="center">Bem-vindo ao meu GitHub, eu sou o Jean Jerri! 🚀</h1>

<h3 align="center">Desenvolvedor de Software</h3>

<div align="center">
  <img height="150" src="https://media.giphy.com/media/M9gbBd9nbDrOTu1Mqx/giphy.gif" alt="gif codando de casa" />
</div>

<div align="center">
  <a href="https://www.linkedin.com/in/jean-jerri/" target="_blank">
    <img src="https://img.shields.io/static/v1?message=LinkedIn&logo=linkedin&label=&color=0077B5&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="linkedin logo"  />
  </a>
  <a href="mailto:jeanjerry2015@gmail.com" target="_blank">
    <img src="https://img.shields.io/static/v1?message=Gmail&logo=gmail&label=&color=D14836&logoColor=white&labelColor=&style=for-the-badge" height="25" alt="gmail logo"  />
  </a>
</div>

---

## 👨🏾‍💻 Sobre o meu perfil técnico

Sou um profissional de tecnologia focado em projetar, desenvolver e escalar soluções de software de ponta a ponta. Atualmente no 6º período de **Sistemas de Informação no IFBA**, transito com fluidez entre o desenvolvimento de interfaces reativas, a construção de APIs corporativas robustas e a orquestração de pipelines de dados em nuvem. 

Tenho facilidade de adaptação a novos desafios, visão de negócio voltada para a entrega de valor e utilizo práticas de desenvolvimento auxiliado por Inteligência Artificial (AI-Augmented Development) para otimização de lógica e validação contínua de código.

---

## 🌟 Projetos em Destaque (Engenharia & Arquitetura)

### 🏥 [Progest - Sistema de Gestão de Estoque Hospitalar](https://github.com/JeanJerri/progest-case-study) *(Case Study)*
Sistema completo e real desenvolvido para solucionar gargalos logísticos em uma rede hospitalar pública (HGVC) composta por múltiplos polos. O projeto englobou desde o levantamento de requisitos até a arquitetura de software, com MVP validado diretamente pela diretoria médica.
* **Stack Tecnológico:** **PHP (Laravel)**, **Vue.js**, **MySQL**, **Docker**, **Traefik**.
* **Arquitetura & Infraestrutura:** Aplicação modularizada com comunicação via API REST. Implementação de proxy reverso com **Traefik** para roteamento dinâmico e renovação autônoma de certificados SSL (Let's Encrypt).
* **Segurança & Hierarquia:** Desenvolvimento de um controle de rotas e interfaces estrito utilizando o padrão **RBAC (Controle de Acesso Baseado em Papéis)**, mapeando fluxos de permissão para 5 perfis distintos (da diretoria central às farmácias satélites).
* **Consistência de Dados (Backend):** Implementação de **Pessimistic Locking** (`lockForUpdate`) para evitar anomalias de concorrência (*Lost Update*) em solicitações simultâneas. Automatização do status de inventário utilizando o padrão arquitetural **Observer**.
* **Performance:** Otimização do motor de banco de dados aplicando **Eager Loading** e instruções avançadas de `JOIN` para a geração de relatórios volumosos de auditoria, eliminando gargalos de *N+1 queries*.

### ☁️ [Pipeline de Dados Cloud (Compass UOL)](https://github.com/JeanJerri/Compass_UOL)
Atuação como Estagiário focado na construção de um **Data Lake** corporativo na **AWS**, estruturado de forma escalável pelas camadas *Raw*, *Trusted* e *Refined*.
* **Stack Tecnológico:** **Python**, **Apache Spark / PySpark**, **AWS Ecosystem** (S3, Lambda, Glue, Athena, QuickSight), **Docker**.
* **Ingestão Serverless:** Desenvolvimento de funções em **AWS Lambda**, integrando bibliotecas customizadas através de **Docker Layers** (Pandas, Boto3) para consumo paginado de APIs externas (TMDb), armazenando dados brutos diretamente no Amazon S3.
* **Processamento (ETL) e Big Data:** Criação de rotinas distribuídas utilizando **PySpark** no **AWS Glue** para higienização, conversão de formatos (JSON para Parquet) e particionamento avançado de dados.
* **Modelagem e Governança:** Construção de um Modelo Dimensional (Tabelas Fato e Dimensão), catalogação automatizada com AWS Glue Crawlers e consumo analítico via **Amazon Athena**.
* **Visualização de Dados:** Geração de *dashboards* gerenciais no **Amazon QuickSight** contendo KPIs e gráficos interativos para auxiliar tomadas de decisão mercadológicas.

---

## ☕ Ecossistema Corporativo em Java

### 📍 [Bootcamp API - Gestão Hierárquica RESTful](https://github.com/JeanJerri/bootcampapi)
Desenvolvimento de uma API RESTful para cadastro de endereços com rigorosa integridade relacional de negócio (UF → Município → Bairro → Pessoa).
* **Stack Tecnológico:** **Java 21**, **Spring Boot**, **Oracle DB**, **JPA/Hibernate**.
* **Valor Técnico:** Implementação profunda do padrão **DTO (Data Transfer Object)**. Tratamento global e centralizado de exceções através de `@ControllerAdvice`, assegurando respostas consistentes, padronizadas e com validações estritas de não-duplicidade.

### 📚 [LiterAlura - Integração de APIs e Mapeamento ORM](https://github.com/JeanJerri/challenge-literalura)
Catálogo interativo desenvolvido para consumir, processar e armazenar dados da API pública Gutendex (que possui mais de 70 mil registros de livros).
* **Stack Tecnológico:** **Java 21**, **Spring Boot**, **PostgreSQL**.
* **Valor Técnico:** Foco em consumo resiliente de APIs externas, desserialização de estruturas JSON complexas com **Jackson** e mapeamento avançado de relacionamentos (Autores e Livros) utilizando *queries* customizadas abstraídas pelo Spring Data JPA.

### 🛒 [AgilStore - Engine de Gerenciamento de Produtos](https://github.com/JeanJerri/desafio-app-gerenciamento-agilstore)
Aplicação orientada a terminal (CLI) desenvolvida para controle completo (CRUD) de estoque de produtos eletrônicos.
* **Stack Tecnológico:** **Java 21**, **Spring Boot**, **Oracle DB**.
* **Valor Técnico:** Manipulação de persistência relacional combinada com a exportação simultânea do estado para arquivos JSON. Implementação de validações robustas de entrada de usuário em terminal e ordenação dinâmica com *Spring Data Sort*.

---

## 📌 Outros Projetos e Fundamentos
* **[Conversor de Moedas](https://github.com/JeanJerri/challenge-conversor-de-moeda):** Consumo de API REST em tempo real utilizando Java e desserialização com biblioteca **Gson**.
* **[Lógica e Algoritmos](https://github.com/JeanJerri/DesafioTecnico):** Resolução de desafios clássicos de engenharia de software (Fibonacci, Análise JSON, Inversão de Strings) utilizando o núcleo da linguagem **Java**.
* **[Jogo do Número Secreto](https://github.com/JeanJerri/jogo-numero-secreto):** Aplicação interativa focada em Front-end, com manipulação dinâmica de DOM e integração com a API `ResponsiveVoice.js` para sintetização de voz (Text-to-Speech), desenvolvida em **JavaScript Vanilla**, HTML5 e CSS3.

---

## 🛠️ Tecnologias e Ferramentas

**Linguagens & Frameworks:**  
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Engenharia de Dados & Nuvem:**  
![AWS](https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-web-services&logoColor=white)
![Apache Spark](https://img.shields.io/badge/Apache%20Spark-E25A1C?style=for-the-badge&logo=apachespark&logoColor=white)

**Banco de Dados, DevOps & Infraestrutura:**  
![MySQL](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=for-the-badge&logo=oracle&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![Traefik](https://img.shields.io/badge/Traefik-24A1C1?style=for-the-badge&logo=traefik&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

---
<div align="center">
  <img src="https://raw.githubusercontent.com/JeanJerri/JeanJerri/output/snake.svg" alt="Snake animation" />
</div>

