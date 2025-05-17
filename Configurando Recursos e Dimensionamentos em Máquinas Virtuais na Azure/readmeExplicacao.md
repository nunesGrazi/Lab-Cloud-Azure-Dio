# ⚙️ Configurando Recursos e Dimensionamento de Máquinas Virtuais no Azure

Este repositório contém informações, exemplos e orientações práticas sobre como configurar recursos e realizar o dimensionamento adequado de **Máquinas Virtuais (VMs)** no Microsoft Azure.

## 🧠 Objetivo

Capacitar desenvolvedores e administradores de sistemas a criar e gerenciar máquinas virtuais no Azure de forma eficiente, otimizando recursos computacionais e custos.

## 📌 Tópicos Abordados

### 🔧 1. Criação de Máquinas Virtuais
- Seleção de **imagem do sistema operacional** (Windows, Linux).
- Escolha do **tamanho da VM** (Séries B, D, E, F, etc).
- Configuração de:
  - CPU e memória
  - Disco (OS e dados)
  - Grupo de recursos
  - Região (Ex: **Brazil South** ou **Brazil Southeast**)

### 📊 2. Dimensionamento de Recursos
- Como escolher o **tamanho ideal da VM** com base em carga de trabalho.
- Uso de **escalonamento vertical** (alteração de SKU) e **horizontal** (instâncias via VMSS).
- Métricas importantes:
  - CPU %
  - Memória
  - Disco IOPS
  - Latência de rede

### 🔁 3. Redimensionamento de VMs
- Como parar e redimensionar uma VM (ex: de B1s para D2s_v3).
- Downgrade e upgrade de instâncias.
- Considerações de compatibilidade e tempo de inatividade.

### 📈 4. Escalabilidade com Conjuntos de Dimensionamento (VM Scale Sets)
- Configuração de **autoscale**
- Regras com base em métricas (CPU > 70%, etc.)
- Integração com balanceadores de carga

### 💵 5. Otimização de Custos
- Comparação entre tipos de VM (geral, computação otimizada, memória otimizada)
- Uso de **instâncias reservadas** e **spot VMs**
- Análise de custos com o **Azure Cost Management**

## 🌎 Regiões do Azure no Brasil

- **Brazil South** (São Paulo):  
  Primeira região brasileira, maior disponibilidade de serviços e zonas de disponibilidade.

- **Brazil Southeast** (Rio de Janeiro):  
  Região adicional com foco em **redundância, recuperação de desastres e baixa latência** para a região Sudeste.

> 💡 Ambas podem ser usadas para balanceamento geográfico, replicação ou failover.