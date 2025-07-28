# Projeto_cybersec_VNW
Repositório com proposta técnica de rede corporativa segura — Projeto CyberSec Vai na Web

<img width="1024" height="1024" alt="image" src="https://github.com/user-attachments/assets/c0dfbf53-4519-4d87-8f32-67a1b201f116" />

# Proposta Técnica – Projeto de Rede Corporativa com Foco em Segurança

**Cliente:** Mai Wolf S/A  
**Setor:** Serviços Financeiros  
**Localidades:** Matriz (SP), Filiais (RJ e MG)  
**Elaborado por:** Maiara Viegas – Analista de Segurança  
**Data:** 28/07/2025  

---

##  Sumário

1. [Sumário Executivo](#1-sumário-executivo)  
2. [Objetivo](#2-objetivo)  
3. [Escopo](#3-escopo)  
4. [Metodologia](#4-metodologia)  
5. [Diagrama de Rede](#5-diagrama-de-rede)  
6. [Proposta Técnica](#6-proposta-técnica)  
7. [Recomendações de Segurança](#7-recomendações-de-segurança)  
8. [Plano de Ação (modelo 80/20)](#8-plano-de-ação-modelo-8020)  
9. [Conclusão](#9-conclusão)  

---

## 1. Sumário Executivo

Esta proposta apresenta uma estrutura de rede corporativa com foco em segurança essencial, segmentação por setores e conectividade segura entre unidades.
A arquitetura utiliza segmentação por departamentos (VLANs), separação da rede de visitantes e acesso seguro entre os escritórios por meio de VPN.

---

## 2. Objetivo

Criar uma rede corporativa segura e funcional para atender às necessidades de conectividade entre matriz e filiais, separando o tráfego por departamentos e garantindo acesso remoto com segurança.

---

## 3. Escopo

- **Matriz (SP):** 80 usuários — Administrativo, Financeiro, TI e Atendimento  
- **Filial RJ:** 30 usuários — mesma estrutura da matriz em menor escala  
- **Filial MG:** 10 usuários — acesso remoto seguro à matriz  
- **Serviços:** ERP, arquivos, impressão e sistemas em nuvem (Office e CRM)  
- **Wi‑Fi:** funcionários e visitantes, em redes separadas  

---

## 4. Metodologia

A proposta foi elaborada com base no briefing fornecido, seguindo boas práticas de arquitetura de redes.  
Foram consideradas as necessidades específicas de cada unidade (matriz e filiais), número de usuários por setor e os principais serviços utilizados.
A proposta utiliza técnicas básicas de segurança como:

- Segmentação por VLANs  
- VPN  
- Separação lógica entre redes corporativas e visitantes
- Autenticação: controle de acesso aos equipamentos de rede com autenticação local ou via servidor centralizado

---

## 5. Diagrama de Rede
<img width="675" height="566" alt="image" src="https://github.com/user-attachments/assets/898cac3f-ec3e-475a-b99d-97b7d1de67b9" />

> **Figura 1:** Diagrama de Rede detalhado para a empresa Mai Wolf S/A.


---

## 6. Proposta Técnica

- **VLANs:** separação de departamentos evita que um problema em um setor afete outro  
- **VPN:** protege a comunicação entre unidades e acessos remotos  
- **Rede de visitantes isolada:** impede que dispositivos externos acessem sistemas internos  
- **Wi-Fi separado:** reduz riscos e melhora o controle  
- **Acesso remoto:** via VPN para MG e colaboradores externos  
- **Equipamentos:** roteadores, firewalls e switches com suporte a VLANs  

---

## 7. Recomendações de Segurança

- Revisar periodicamente os acessos  
- Manter backups das configurações da rede  
- Proibir o compartilhamento de credenciais entre usuários ou setores
- Manter firmwares e softwares atualizados
- Utilizar senhas complexas e, se possível, autenticação multifator (MFA) nos dispositivos de rede 

---

## 8. Plano de Ação (modelo 80/20)

| Etapa                          | Prioridade | Esforço | Impacto |
|-------------------------------|------------|---------|---------|
| Criar VLANs por setor         | Alta       | Média   | Alto    |
| Configurar rede de visitantes | Alta       | Fácil   | Alto    |
| Instalar e configurar VPN     | Alta       | Média   | Alto    |
| Separar Wi-Fi interno e guest | Alta       | Fácil   | Alto    |

---

## 9. Conclusão

A proposta entrega uma estrutura de rede segura, simples e funcional, dimensionada conforme a estrutura organizacional e as demandas operacionais da Mai Wolf S/A.  
Ela possibilita controle por departamento, acesso remoto seguro, melhor organização da rede, redução de riscos básicos de segurança e controles mínimos para **confidencialidade, integridade e disponibilidade**.

---

