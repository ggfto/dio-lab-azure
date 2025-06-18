# 💻 Desafio Prático - Máquinas Virtuais na Azure

Este repositório contém a documentação do desafio prático proposto no laboratório de **Máquinas Virtuais na Azure**, com o objetivo de aplicar os conhecimentos adquiridos ao longo das vídeo-aulas.

---

## 🎯 Objetivos do Desafio

- Aplicar na prática os conceitos aprendidos sobre Máquinas Virtuais na Azure.
- Documentar de forma clara e estruturada os processos realizados.
- Utilizar o GitHub como ferramenta de versionamento e compartilhamento da documentação técnica.

---

## ✅ Pré-requisitos

Antes de iniciar, certifique-se de que possui:

- Uma conta ativa no [Microsoft Azure](https://portal.azure.com)
- Acesso ao portal e permissões para criação de recursos
- Git e GitHub configurados para versionamento de código

---

## 🧪 Etapas Realizadas

### 1. Criação da Máquina Virtual

- Acesso ao portal Azure: https://portal.azure.com
- Criação de um novo recurso: **Máquina Virtual**
- Configurações principais:
  - Sistema Operacional: `Ubuntu Server 20.04 LTS`
  - Tamanho: `B1s (1 vCPU, 1 GiB RAM)`
  - Autenticação: `Chave SSH` ou `Senha`
  - Região: `South Brazil`
- Grupo de Recursos criado: `lab-vm-grupo`

### 2. Configurações de Rede

- Regras de entrada configuradas para permitir acesso SSH (porta 22)
- IP público associado para acesso remoto

### 3. Acesso à VM

- Conexão via terminal (Linux/macOS) ou PuTTY (Windows)
- Atualização do sistema:  
  ```bash
  sudo apt update && sudo apt upgrade -y
  ```
