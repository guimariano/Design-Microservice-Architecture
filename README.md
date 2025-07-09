# 🧠 Portfólio Técnico – Arquitetura e Desenvolvimento de Sistemas

## 🎨 Front-end

### 🛠️ Omni-Admin
Interface administrativa principal do ecossistema Omnichannel. Responsável pela **gestão de lojas, usuários, vendas e operações**, oferecendo controle total sobre a operação.

### 📄 Omni-Controller
Aplicação voltada para **gestão e configuração de contratos de clientes** da Infracommerce. Permite customizações por contrato com flexibilidade e governança.

### 🛒 POX (Point of Experience)
Aplicativo de vendas para atendimento presencial. Possui recursos como **prateleira infinita**, permitindo ao vendedor acesso a um catálogo estendido de produtos.

---

## ⚙️ Back-end

### 🌐 Omni-API
Serviço unificado que centraliza a **comunicação e as regras de negócio** entre as diversas aplicações. Atua como o backbone da operação Omnichannel.

### 📬 Omni-Queue
Gerenciador de **filas e tarefas assíncronas**, responsável por executar processos em background de forma eficiente, sem sobrecarregar os serviços principais.

### 📦 Omni-Fetch
Aplicação responsável pela **integração com catálogos externos**, sincronizando ofertas e dados de produtos de diferentes parceiros.

### 🧾 Occtotax
Sistema de **automação fiscal** que realiza a geração de **notas fiscais eletrônicas (NF-e)** e **cupons fiscais (SAT/NFC-e)**, garantindo conformidade tributária.

---

## 🌍 Aplicações Externas

### 💳 Adyen
Gateway de pagamento integrado com **maquininhas POS**, oferecendo adquirência conectada diretamente ao ecossistema Omnichannel.

---

## 🧱 Contextos de Conteúdo

### 🗂️ Catálogo (on-demand)
Sistema de **catálogo de produtos sob demanda**, fornecido via **CXaaS**, com acesso em tempo real pelas aplicações.

### 🏷️ Price & Promotion (on-demand)
Gerenciamento de **preços e promoções** dinâmico, configurado sob demanda por meio da plataforma CXaaS.

### 🔎 Search (on-demand)
Sistema de busca integrado com **filtros avançados, termos compostos e relevância contextual**, fornecido também pela CXaaS.

### 📦 Estoque (synced)
Sistema de controle de **estoque sincronizado** com iHub a cada hora e **revalidado no momento da venda** para garantir consistência.

---

## 🔌 Integrações

### 🔁 iHUB
Responsável pela **integração com ERPs, sistemas de BI e legados**, além da sincronização de dados operacionais com sistemas externos.

---

## ☁️ Serviços na Huawei Cloud

### 🧰 Hospedagem (Kubernetes)
Infraestrutura **conteinerizada com Kubernetes**, garantindo **escalabilidade, resiliência e segurança** dos serviços.

### 🗃️ Object Storage
Armazenamento de **documentos, imagens e dados não estruturados**, utilizado em diversas etapas da operação (ex: notas fiscais, relatórios, produtos).

### ⚡ Redis
Usado para:
- **Cache de API**
- **Cache de banco de dados**
- **Gerenciamento de filas assíncronas**

---

## 🗄️ Bancos de Dados (MySQL)

### 🔐 DB Controller
Banco de dados central para:
- **Gestão de usuários e contratos**
- **Controle de acesso**
- **Orquestração de conexões multi-tenant**

### 🧾 DB Occtotax
Banco especializado para a aplicação fiscal, incluindo:
- Geração de **notas e cupons fiscais**
- Regras tributárias específicas por estado e cliente

### 🧳 Bancos de dados por cliente
Ambiente multi-tenant com **bancos dedicados por cliente**, oferecendo **isolamento, segurança e personalização**.

---

📌 *Este portfólio reflete minha atuação prática como desenvolvedor sênior, com foco em soluções escaláveis, orientadas a domínio, e integradas com diversas plataformas, seguindo boas práticas de arquitetura e engenharia de software.*
