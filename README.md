# Laborat-rio-Azure

# Desafio - Criação e Configuração de Máquina Virtual no Microsoft Azure

## 📌 Descrição

Este repositório contém os resumos, anotações e dicas adquiridas durante a prática de criação e configuração de uma máquina virtual na plataforma **Microsoft Azure**. O objetivo é documentar o processo de forma clara, servindo como referência para futuros estudos e projetos semelhantes.

---

## 🎯 Objetivos de Aprendizagem

- Aplicar os conceitos aprendidos em um ambiente prático;
- Documentar processos técnicos de forma clara e estruturada;
- Utilizar o GitHub como ferramenta de documentação técnica.

---

## ⚙️ Etapas Realizadas

### 1. Criação da Conta no Azure
- Conta criada com plano gratuito (ou educacional, se for o caso).
- Configurações iniciais do portal exploradas.

### 2. Configuração da Máquina Virtual
- **Sistema Operacional:** (ex: Ubuntu 20.04 LTS)
- **Tamanho da VM:** (ex: B1s - 1 vCPU, 1 GB RAM)
- **Região:** (ex: Brazil South)
- **Nome da VM:** (ex: minha-vm-teste)
- **Usuário:** (ex: azureuser)
- **Autenticação:** (Senha ou chave SSH)

### 3. Abertura de Portas (NSG)
- Porta 22 (SSH) aberta para acesso remoto.
- Porta 80 (HTTP), se necessário.

### 4. Acesso Remoto à VM
- Acesso via SSH com comando:
  ```bash
  ssh azureuser@<ip_da_vm>
