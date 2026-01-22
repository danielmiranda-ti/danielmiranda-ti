<h1 align="center">👋 Olá! Eu sou o Daniel Miranda</h1>

<p align="center">
Desenvolvedor apaixonado por arquitetura de software, microsserviços, e soluções inteligentes usando Python, Java e AWS ☁️
</p>


---

## 🚀 Tecnologias e Ferramentas

<table>
  <tr>
    <td align="center" width="120">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" width="40"/><br/>
      <sub><b>Java</b></sub>
    </td>
    <td align="center" width="120">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" width="40"/><br/>
      <sub><b>Python</b></sub>
    </td>
    <td align="center" width="120">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" width="40"/><br/>
      <sub><b>Docker</b></sub>
    </td> 
    <td align="center" width="120">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/terraform/terraform-original.svg" width="40"/><br/>
      <sub><b>Terraform</b></sub>
    </td>    
    <td align="center" width="120">
      <img src="https://commons.wikimedia.org/wiki/Special:Redirect/file/DBeaver_logo.svg"  width="40" /><br/>
      <sub><b>DBeaver</b></sub>
    </td>
    <td align="center" width="120">
      <img src="https://www.vectorlogo.zone/logos/postgresql/postgresql-icon.svg" width="40"  /><br/>
      <sub><b>PostgreSQL</b></sub>
    </td>
    <td align="center" width="120">
      <img src="https://www.vectorlogo.zone/logos/oracle/oracle-icon.svg"  width="40" /><br/>
      <sub><b>Oracle Database</b></sub>
    </td>
  </tr>
  <tr>
    <td align="center" width="120">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-original-wordmark.svg" width="30"/><br/>
      <sub><b>AWS</b></sub>
    </td>
    <td align="center" width="120">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" width="40"/><br/>
      <sub><b>Git</b></sub>
    </td>
    <td align="center" width="120">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" width="40" /><br/>
      <sub><b>GitHub</b></sub>
    </td>
    <td align="center" width="120">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/pycharm/pycharm-original.svg" width="40"/><br/>
      <sub><b>PyCharm</b></sub>
    </td>
    <td align="center" width="120"> 
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/intellij/intellij-original.svg" width="40" /><br/>
      <sub><b>IntelliJ IDEA</b></sub>
    </td>
    <td align="center" width="120">
      <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" width="40" /><br/>
      <sub><b>VSCode</b></sub>
    </td>
    <td align="center" width="120">
      <img src="https://raw.githubusercontent.com/gilbarbara/logos/main/logos/sonarqube.svg" alt="SonarQube" width="80" h/><br/>
      <sub><b>SonarQube</b></sub>
    </td>
    <td align="center" width="120">      
      <img src="https://insomnia.rest/images/insomnia-logo.svg" width="110" />
      <sub><b>Insomnia</b></sub>
    </td>    
  </tr>
</table>


<!--
---
## ☕ Projetos em Java
Projetos em Java, usando spring.

#### 🧩	Organização de estrutura do projeto
-->
---
## 🐍 Projetos em Python
Projetos em Python para automações, análise de dados e scraping.

<details>
  <summary><strong> 🌟 Api Rest Flask </strong></summary>
  
  - ## 🌟 Com LocalStack

    ### 🔧 Serviço REST para SNS/SQS/DynamoDB (LocalStack)
    [🔗 Ver repositório](https://github.com/danielmiranda-ti/api-utilitaria-local-stack)
    
    Serviço em **Python/Flask** que expõe uma API REST para trabalhar com **SQS**, **SNS** e **DynamoDB** usando **LocalStack** como mock da AWS.
    
    - 🧱 Stack: Python, Flask, boto3, LocalStack, Docker
    - ☁️ Focado em: integrações com serviços AWS em ambiente local
    - 🔌 Funcionalidades:
      - Envio e consumo de mensagens **SQS** por nome de fila
      - Criação de tópicos **SNS** e publicação por nome de tópico
      - Criação de **subscriptions SNS → SQS** e **SNS → Lambda**
      - Leitura de itens no **DynamoDB** (scan e get por chave)
    - 🧪 Uso típico:
      - Desenvolvimento e testes locais de fluxos assíncronos
      - Simulação de arquitetura orientada a eventos sem usar AWS real
</details>

<!--
---
## ☁️ Cloud / AWS / DevOps

Soluções e experimentos com serviços em nuvem e automações DevOps.
-->

---

## 📊 Observabilidade & DevOps

Projetos focados em monitoramento, logs centralizados e infraestrutura para aplicações distribuídas.

<details>
  <summary><strong>🚦 Observability – Logs centralizados com Grafana, Loki e Alloy</strong></summary>
  
  - 🧩 Infraestrutura completa para observabilidade de aplicações backend e microsserviços.
  - 📦 Orquestrado com <strong>Docker Compose</strong>, subindo <strong>Grafana</strong>, <strong>Loki</strong> e <strong>Alloy</strong>.
  - 📁 Coleta logs em JSON (via arquivo/STDOUT) com campos como:
    - <code>correlation_id</code>
    - <code>service</code>
    - <code>step</code>
    - <code>status</code>
  - 📈 Inclui dashboard pronto no Grafana para:
    - Visualizar a linha do tempo da saga por <code>correlation_id</code>
    - Analisar volume de logs, erros por aplicação, steps da saga, etc.
  - 🔗 <a href="https://github.com/danielmiranda-ti/observability">Ver repositório</a>

</details>

---

## 🧪 Projetos de Estudo e POCs

Pequenos projetos e provas de conceito.

<details>
  <summary><strong>🧱 Arquitetura de Software - Padrões de Sagas </strong></summary>
  
  - ### 🌀 Epic Saga (sao)
  
    #### 🔧 Repositórios:
  
    - [epic-saga-orquestrador](https://github.com/danielmiranda-ti/epic-saga-orquestrador) – Orquestrador central responsável por iniciar e coordenar as etapas da saga

<!--
  ---
  - ### 📞 Phone Tag Saga (sac)

    #### 🔧 Repositórios:
    
    - []()
  ---

  - ### 🧚 Fairy Tale Saga (seo)

    #### 🔧 Repositórios:
    
    - []()
  ---

  - ### ⏳ Time Travel Saga (sec)

    #### 🔧 Repositórios:
    
    - []()
  ---

  - ### 🦄 Fantasy Fiction Saga (aao)

    #### 🔧 Repositórios:
    
    - []()
  ---

  - ### 👻 Horror Story Saga (aac)

    #### 🔧 Repositórios:
    
    - []()
  ---

  - ### 🔀 Parallel Saga (aeo)

    #### 🔧 Repositórios:
    
    - []()
  ---

  - ### 📚 Anthology Saga (aec)

    #### 🔧 Repositórios:
    
    - []()
  -->
</details>

---





## 📬 Contato

- 💼 [LinkedIn](https://www.linkedin.com/in/daniel-miranda-b6a3483b)
- 📧 danielmiranda.ti@gmail.com
