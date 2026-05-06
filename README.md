# Azure Infrastructure Hands-On Lab

## Sobre o projeto

Projeto prático realizado em Microsoft Azure com foco em infraestrutura cloud, provisionamento de máquinas virtuais, gerenciamento de recursos e monitoramento financeiro.

Este laboratório foi desenvolvido como prática de estudos em computação em nuvem, utilizando recursos fundamentais do Azure para administração de ambientes corporativos.

---

# Tecnologias utilizadas

- Microsoft Azure
- Windows Server
- Azure Virtual Machines
- Azure Resource Groups
- Azure Cost Management
- RDP (Remote Desktop Protocol)

---

# Estrutura do ambiente

O ambiente foi organizado utilizando múltiplos Resource Groups separados por região, simulando uma estrutura corporativa distribuída internacionalmente.

## Resource Groups criados

| Nome | Região |
|---|---|
| HQ-BR | Central US |
| Breach-BR | Brazil South |
| Breach-FR | France Central |
| Breach-JP | Japan East |

---

# Virtual Machine

Foi realizado o provisionamento de uma máquina virtual Windows Server no Azure.

## Configuração da VM

| Configuração | Valor |
|---|---|
| Sistema Operacional | Windows Server |
| Status | Running |
| Tipo | Standard_D2s_v3 |
| Resource Group | vm_production |
| Região | Central US |
| Acesso remoto | RDP |
| IP Público | Configurado |

---

# Funcionalidades implementadas

- Provisionamento de Virtual Machine
- Gerenciamento de Resource Groups
- Organização de infraestrutura por região
- Configuração de acesso remoto via RDP
- Configuração de monitoramento financeiro
- Criação de alertas de custo
- Gerenciamento de custos no Azure

---

# Cost Management

Durante o laboratório foram realizados testes utilizando os recursos de monitoramento financeiro do Azure.

## Recursos utilizados

- Budgets
- Cost Alerts
- Monitoramento de utilização
- Controle de gastos da assinatura

---

# Evidências do laboratório

## Resource Groups

![Resource Groups](images/resource-groups.png)

---

## Virtual Machine em execução

![Virtual Machine](images/vm.png)

---

## Cost Alerts

![Cost Alerts](images/alerts.png)

---

## Acesso remoto via RDP

![RDP](images/rdp.png)

---

# Objetivos do laboratório

- Praticar conceitos fundamentais de cloud computing
- Aprender gerenciamento de infraestrutura no Azure
- Trabalhar com provisionamento de recursos
- Entender organização lógica utilizando Resource Groups
- Implementar monitoramento de custos
- Validar conectividade remota em ambiente cloud

---

# Aprendizados obtidos

Durante este hands-on foram praticados conceitos importantes relacionados a:

- Infraestrutura como serviço (IaaS)
- Administração básica no Azure
- Virtualização em nuvem
- Gerenciamento de recursos
- Custos e monitoramento
- Conectividade remota
- Organização de ambientes cloud

---

# Próximos passos

- Implementar Network Security Groups (NSG)
- Configurar VNet e Subnets
- Trabalhar com Azure Monitor
- Implementar RBAC
- Configurar Backup
- Adicionar automação com PowerShell
- Estudar Azure Administrator (AZ-104)

---

# Autor

Lucas Mello

Projeto desenvolvido para fins de estudo, prática de infraestrutura cloud e evolução profissional em Microsoft Azure.