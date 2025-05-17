# 🌐 Arquiteturas no Microsoft Azure

Este repositório tem como objetivo reunir conteúdos, exemplos de código, diagramas e boas práticas sobre **arquiteturas em nuvem utilizando o Microsoft Azure**. O foco está em soluções escaláveis, resilientes e seguras, com ênfase nas regiões da América do Sul — mais especificamente as localizações no **Brasil**.

## ☁️ O que é o Microsoft Azure?

O Azure é a plataforma de nuvem da Microsoft que oferece mais de 200 produtos e serviços em nuvem. Ele permite construir, executar e gerenciar aplicativos em uma rede global de datacenters, com suporte a múltiplas linguagens, frameworks e ferramentas.

---

## 🧱 Tipos de Arquiteturas no Azure

Algumas arquiteturas comuns:

- **Web Apps e APIs** com App Services
- **Arquiteturas Serverless** com Azure Functions
- **Microserviços** com Azure Kubernetes Service (AKS)
- **Big Data & Analytics** com Azure Synapse, Data Lake e Data Factory
- **Machine Learning** com Azure ML
- **CI/CD Pipelines** com Azure DevOps ou GitHub Actions
- **Backup e Disaster Recovery**
- **Infraestrutura como Código** com Bicep ou Terraform

---

## 🌍 Regiões do Azure no Brasil

A América do Sul possui duas regiões do Azure ativas no Brasil:

### 🇧🇷 South America — **Brazil South (São Paulo)**

- **Localização física:** Estado de São Paulo
- **Código da região:** `brazilsouth`
- **Disponibilidade:** Pública e amplamente utilizada
- **Descrição:** Primeira região do Azure na América do Sul, amplamente utilizada por empresas no Brasil e em países vizinhos.
- **Serviços disponíveis:** A maioria dos serviços do Azure está disponível nessa região, incluindo máquinas virtuais, bancos de dados, redes virtuais, serviços gerenciados e muito mais.

### 🇧🇷 Southeast Brazil — **Brazil Southeast (Rio de Janeiro)**

- **Localização física:** Estado do Rio de Janeiro
- **Código da região:** `brazilsoutheast`
- **Disponibilidade:** Inicialmente limitada (com foco em alta disponibilidade e recuperação de desastres)
- **Descrição:** Região complementar à Brazil South. É frequentemente utilizada em conjunto com São Paulo para cenários de **alta disponibilidade (HA)**, **disaster recovery (DR)** e **redundância geográfica**.
- **Serviços disponíveis:** Subconjunto dos serviços disponíveis em `brazilsouth`, mas crescendo gradualmente.

---

## 🔄 Diferenças entre Brazil South e Brazil Southeast

| Característica              | Brazil South (São Paulo)     | Brazil Southeast (Rio de Janeiro)  |
|----------------------------|-------------------------------|-------------------------------------|
| Código da região           | `brazilsouth`                 | `brazilsoutheast`                   |
| Disponibilidade de serviços| Alta                          | Limitada (mas em expansão)          |
| Finalidade principal       | Uso geral                     | Redundância / Alta disponibilidade  |
| Lançamento                 | Mais antigo (primeira região) | Mais recente                        |
| Localização                | São Paulo                     | Rio de Janeiro                      |

---

## 📌 Casos de Uso Recomendados

- Use **Brazil South** para workloads principais e aplicações em produção.
- Use **Brazil Southeast** como fallback em planos de recuperação de desastre (DR) ou para distribuir cargas críticas com alta disponibilidade (HA).
- Considere o uso de **Zonas de Disponibilidade (AZ)** ou **Regiões Emparelhadas (Paired Regions)** para garantir tolerância a falhas.

---