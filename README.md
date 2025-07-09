# 🧠 Technical Portfolio – Software Architecture & System Development

📌 *This portfolio highlights my real-world experience as a senior developer, focused on delivering **scalable**, **domain-oriented**, and **platform-integrated** solutions, built with solid architecture and engineering principles.*

## 🔗 Architecture Diagram (Draw.io)
- https://drive.google.com/file/d/17xAo-AW_FbjyQy1nYo6SD0mhniHSU7ZW/view?usp=sharing

## 🖼️ Diagrams

### Simplified
![arch3](https://github.com/user-attachments/assets/495e5bf0-c6c4-4e65-add2-5b08c5c29e9e)

### Expanded
![arch1](https://github.com/user-attachments/assets/14fa407d-894a-4972-a733-1f4d31b11bc2)

---

## 🎨 Front-end

### 🛠️ Omni-Admin (ReactJS + CSS)
Main administrative interface of the Omnichannel ecosystem. Responsible for **managing stores, users, sales, and operations**, offering full control over the system.

### 📄 Omni-Controller (ReactJS + CSS)
Application designed for **managing and configuring client contracts** with Infracommerce. Enables contract-specific customizations with flexibility and governance.

### 🛒 POX (Point of Experience) (ReactJS + CSS)
Sales application for in-person service. Features include the **infinite shelf**, allowing sales associates to access an extended product catalog beyond physical inventory.

---

## ⚙️ Back-end

### 🌐 Omni-API (Clean Architecture with NestJS)
Unified service that centralizes **communication and business rules** across applications. Serves as the backbone of the Omnichannel operation.

### 📬 Omni-Queue (Clean Architecture with NestJS)
Asynchronous **queue and task manager**, responsible for processing background jobs efficiently without overloading core services.

### 📦 Omni-Fetch (Clean Architecture with NestJS + RabbitMQ)
Service responsible for **integrating external product catalogs**, synchronizing product data and offers from various suppliers.

### 🧾 Occtotax (MVC with PHP)
**Tax automation system** that handles the generation of **electronic invoices (NF-e)** and **fiscal coupons (SAT/NFC-e)**, ensuring full tax compliance.

---

## 🌍 External Applications

### 💳 Adyen
Payment gateway integrated with **POS terminals**, providing connected acquiring services fully integrated into the Omnichannel ecosystem.

---

## 🧱 Content Contexts

### 🗂️ Catalog (on-demand)
**On-demand product catalog** system, powered by **CXaaS**, with real-time access for all front-end applications.

### 🏷️ Price & Promotion (on-demand)
Dynamic **pricing and promotions management**, configured on demand through the CXaaS platform.

### 🔎 Search (on-demand)
Integrated search system featuring **advanced filters, compound terms, and contextual relevance**, also provided by CXaaS.

### 📦 Stock (synced)
**Stock management system** synced with iHub every hour and **revalidated at the time of sale** to ensure real-time inventory accuracy.

---

## 🔌 Integrations

### 🔁 iHUB
Handles **integration with ERPs, BI platforms, and legacy systems**, including operational data sync with external systems and analytics tools.

---

## ☁️ Huawei Cloud Services

### 🧰 Hosting (Kubernetes)
Infrastructure fully **containerized and orchestrated with Kubernetes**, providing **scalability, resilience, and security** across services.

### 🗃️ Object Storage
Cloud storage for **documents, images, and unstructured data**, used across the operation (e.g., invoices, reports, product assets).

### ⚡ Redis
Used for:
- **API caching**
- **Database caching**
- **Asynchronous queue management**

---

## 🗄️ Databases (MySQL)

### 🔐 DB Controller
Central database for:
- **User and contract management**
- **Access control**
- **Orchestration of multi-tenant connections**

### 🧾 DB Occtotax
Dedicated database for the fiscal application, including:
- Generation of **invoices and fiscal coupons**
- Specific tax rules per state and client

### 🧳 Client Databases
Multi-tenant environment with **isolated databases per client**, ensuring **security, data separation, and customization**.

---

