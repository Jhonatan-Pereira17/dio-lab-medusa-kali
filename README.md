# Laboratório — Auditoria de Força-Bruta (Kali + Medusa)

## Descrição
Laboratório didático para executar e documentar testes de força-bruta em serviços comuns (FTP, formulários web e SMB) usando **Kali Linux** e **Medusa** em ambiente controlado. Objetivo: reproduzir ataques em ambientes de teste, coletar evidências e propor mitigação — sempre com autorização explícita.

## Estrutura do repositório

FTP/
├─ enumeracao
  ├─ imagens/conexao_FTP.png|NMAP.png
  ├─ scripts/comandos.txt
├─ Exploracao
  ├─ imagens/login_successful.png|medusa-ataque.png
  ├─ scripts/comandos.txt
Formularios_Web/
├─ enumeracao
  ├─ imagens/brute_force.png|observando_requisição.png
  ├─scripts/comandos.txt
├─exploração
  ├─imagens/formulario_invadido.png
SMB
├─enumeração
  ├─imagens/enum4linux.png
  ├─scripts.txt
├─exploração
  ├─imagens/ataque bem sucedido.png| ataque_smb.png
  ├─scripts.txt


## Pré-requisitos
- Máquina atacante: **Kali Linux** (VM)
  - Instalar Medusa:
  ```bash
  sudo apt update && sudo apt install medusa -y



