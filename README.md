# ⚡ CloudArchitect AI — Consultor de System Patterns & AWS Architecture

<p align="center">
  <img src="https://img.shields.io/badge/AWS-Prescriptive_Guidance-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white" alt="AWS Guidance" />
  <img src="https://img.shields.io/badge/Design_Patterns-GoF-00F0FF?style=for-the-badge" alt="GoF Patterns" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-3.0-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/Deploy-GitHub_Pages-2EA44F?style=for-the-badge&logo=github&logoColor=white" alt="GitHub Pages" />
</p>

> **Plataforma interativa de consultoria e recomendação de arquitetura cloud**, desenvolvida para mapear desafios técnicos em soluções nativas AWS fundamentadas nos clássicos **Design Patterns (GoF)** e no **AWS Prescriptive Guidance**.

---

## 🚀 Demonstração Online

Acesse a versão em produção diretamente no GitHub Pages:  
🔗 **[https://kaiquerios.github.io/CloudArchitect/](https://kaiquerios.github.io/CloudArchitect/)**

---

## 📌 Sobre o Projeto

O **CloudArchitect AI** atua como um consultor de arquitetura orientado a padrões de projeto. Em vez de apenas exibir serviços isolados, a aplicação traduz problemas de software e requisitos de negócios em **System Patterns** validados pelo mercado.

Seja analisando intenções de alto nível (ex: *"Sistema de compras e e-commerce"*) ou problemas específicos de engenharia (ex: *"Integração com legado XML"*), o sistema indica a combinação de padrões ideal (como **CQRS**, **Observer**, **Facade** e **Circuit Breaker**) juntamente com os serviços AWS correspondentes e o código de infraestrutura como código (IaC em Terraform).

Projetado em parceria com o **AWS Student Builder Group — SENAI CIMATEC**.

---

## ✨ Funcionalidades Principais

* **🤖 Motor de Consultoria Arquitetural:** Campo interativo que analisa a dor descrita pelo usuário e recomenda automaticamente o *System Pattern* (ou combinação de padrões) mais adequado para o cenário.
* **📚 Catálogo Estruturado por Categorias:**
  * **AWS Cloud Patterns:** Padrões nativos para escalabilidade, resiliência e desacoplamento (ex: *CQRS*, *Circuit Breaker*).
  * **Padrões Criacionais (GoF):** Controle de concorrência e gerenciamento de estado (ex: *Singleton* / State Locking).
  * **Padrões Estruturais (GoF):** Facilitação de interfaces e tradução de protocolos (ex: *Facade*, *Adapter*).
  * **Padrões Comportamentais (GoF):** Arquiteturas orientadas a eventos e mensagens (ex: *Observer / Pub-Sub*).
* **🔍 Explicação Detalhada do Problema vs. Solução:** Exposição clara de qual gargalo o padrão resolve e como a AWS implementa a solução de forma nativa.
* **🛠️ Pipelines e Código IaC (Terraform):** Diagramação lógica dos nós de serviço envolvidos e exportação direta do código HashiCorp HCL (Terraform) pronto para provisionamento.
* **🌐 100% Client-Side & Estático:** Executa nativamente no navegador utilizando JavaScript puro e Tailwind CSS via CDN, sem dependência de servidores backend.

---

## 🛠️ Tecnologias Utilizadas

* **HTML5 & JavaScript (ES6+):** Lógica dinâmica de consulta, filtragem e renderização no client-side.
* **Tailwind CSS (Play CDN):** Estilização responsiva e tema escuro (*dark mode*) customizado para a identidade visual AWS.
* **FontAwesome 6:** Iconografia técnica para componentes, padrões e serviços AWS.
* **GitHub Pages:** Hospedagem contínua e distribuição estática de alta performance.

---

## 📂 Estrutura do Repositório

```text
CloudArchitect/
├── assets/
│   ├── css/
│   │   └── style.css            # Customizações de efeitos visuais e scrollbar
│   └── js/
│       ├── app.js               # Motor de consulta (NLP leve), renderização e modais
│       └── architectureData.js  # Base de dados de padrões GoF/AWS, palavras-chave e IaC
├── index.html                   # Interface principal da aplicação (SPA)
└── README.md                    # Documentação oficial do repositório