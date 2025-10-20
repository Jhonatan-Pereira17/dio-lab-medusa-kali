# dio-lab-medusa-kali

# Desafio: Auditoria de Força Bruta com Kali + Medusa

## Objetivo
Demonstrar, em ambiente controlado, a execução prática de ataques de força bruta (FTP, formulário web e SMB) usando Kali Linux e Medusa; documentar comandos, wordlists, evidências e recomendações de mitigação para gerar um relatório técnico reproduzível.

---

## Sumário
- [Introdução](#introdução)  
- [Objetivo](#objetivo)  
- [Ambiente](#ambiente)  
- [Pré-requisitos](#pré-requisitos)  
- [Estrutura do repositório](#estrutura-do-repositório)  
- [Metodologia](#metodologia)  
- [Comandos e Wordlists](#comandos-e-wordlists)  
- [Resultados](#resultados)  
- [Análise de Riscos e Mitigações](#análise-de-riscos-e-mitigacoes)  
- [Conclusão](#conclusão)  
- [Referências](#referências)

---

## Introdução
Laboratório prático para estudar ataques de força bruta em serviços comuns e aplicar contramedidas em um ambiente controlado (Kali + Metasploitable/DVWA).

## Ambiente
- **VMs:** Kali Linux, Metasploitable 2 (ou VM com DVWA)  
- **Hypervisor:** VirtualBox  
- **Rede:** Host-only / Internal Network (entre VMs)

## Pré-requisitos
- VirtualBox instalado  
- Imagens/OVAs das VMs (Kali, Metasploitable2/DVWA)  
- Snapshot das VMs (recomendado)  
- `medusa` instalado no Kali (`sudo apt update && sudo apt install medusa -y`)

## Estrutura do repositório
README.md
/images/
wordlists/
scripts/
notes/


## Metodologia
1. Criar snapshots das VMs.  
2. Fazer descoberta de portas/serviços (ex.: `nmap`).  
3. Teste A — Força bruta em FTP com Medusa.  
4. Teste B — Automação de formulário web (DVWA).  
5. Teste C — Password spraying em SMB (enumeração de usuários).  
6. Registrar comandos, logs e evidências.  
7. Analisar e propor mitigação.

## Comandos e Wordlists
> Exemplos que você vai preencher em `/notes/` e `/wordlists/`.



