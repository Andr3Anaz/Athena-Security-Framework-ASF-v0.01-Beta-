# 🛡️ Athena Security Framework (ASF) v0.01
**Framework de Maturidade em Segurança da Informação e Cibersegurança**  
Baseado em NIST CSF 2.0 • ISO/IEC 27001:2022 • COBIT 2019 • CIS Controls v8  
© Athena Security LTDA — 2025  

---

## 📘 1. Visão Geral

O **ASF (Athena Security Framework)** é um modelo de maturidade pragmático que estrutura a evolução da segurança da informação em **níveis progressivos e camadas de controle (Defcon 1 a 3)**.  
O objetivo é orientar empresas na **implementação estruturada de práticas de segurança**, mensurando sua maturidade e priorizando investimentos.

---

## 🧱 2. Estrutura de Domínios

| Domínio | Referência | Objetivo |
|----------|-------------|----------|
| **GOVERNANÇA E COMPLIANCE** | ISO 27001 / COBIT EDM / LGPD | Direcionar a gestão de risco, políticas e conformidade |
| **PROTEÇÃO** | NIST CSF “Protect” / CIS 3–13 | Implementar controles preventivos técnicos e organizacionais |
| **DETECÇÃO** | NIST CSF “Detect” / ISO 27002 A.8.16 | Garantir visibilidade e monitoramento contínuo |
| **RESPOSTA** | NIST CSF “Respond” / ISO 27035 | Reduzir impacto de incidentes e conter ameaças |
| **RECUPERAÇÃO** | NIST CSF “Recover” / ISO 27031 | Restaurar serviços críticos e aprender com os eventos |

---

## 🔺 3. Camadas de Maturidade Técnica (Defcon)

| Camada | Descrição | Exemplos de Controles |
|---------|------------|-----------------------|
| **D1 – Fundacional** | Base mínima de segurança corporativa | Firewall, Antivírus, Backup, Wireless Corporativo |
| **D2 – Gerencial** | Consolidação e automação de controles | WAF, MDM, SIEM, DLP, IAM/PAM |
| **D3 – Estratégica** | Integração e resposta proativa | Threat Intelligence, DevSecOps, CASB, ISO 27001 |
| **RM – Risk Management** | Gestão e priorização de riscos | ISO 31000, LGPD, Auditorias periódicas |

---

## 📈 4. Níveis de Maturidade (Modelo CMMI Adaptado)

| Nível | Classificação | Descrição |
|-------|----------------|-----------|
| **0 – Inexistente** | Sem controles implementados |
| **1 – Inicial** | Ações reativas e não documentadas |
| **2 – Básico** | Políticas mínimas e controles parciais |
| **3 – Gerenciado** | Processos definidos e mensurados |
| **4 – Otimizado** | Controles automatizados e integrados |
| **5 – Estratégico** | Segurança contínua e alinhada ao negócio |

---

## 🔄 5. Ciclo de Melhoria Contínua (PDCA Athena)

**Plan:** Avaliar riscos, criar plano de ação, definir KPIs.  
**Do:** Implementar controles prioritários (faseada em D1, D2, D3).  
**Check:** Auditar processos, revisar logs e medir maturidade.  
**Act:** Corrigir falhas, atualizar políticas e melhorar indicadores.

> Referências: ISO 27001 Clause 10 / COBIT MEA01 / NIST CSF “Recover”

---

## ⚙️ 6. Métricas e KPIs Recomendados

| Indicador | Fórmula | Objetivo |
|------------|----------|----------|
| **MTTR (Mean Time to Respond)** | tempo médio de resposta a incidentes | Agilidade operacional |
| **% Cobertura de Pentest** | ativos testados / ativos totais | Validação técnica |
| **Taxa de Phishing Clicado** | cliques / e-mails simulados | Eficácia de conscientização |
| **Compliance Score** | controles aderentes / controles exigidos | Conformidade |
| **Risco Residual Médio** | risco total – controles implementados | Governança de risco |

---

## 🧩 7. Roadmap de Evolução

### Fase 1 (0–6 meses)
- Nomear DPO e revisar política LGPD  
- Implementar antivírus corporativo e backup em nuvem  
- Concluir DLP e WAF  
- Iniciar gestão de vulnerabilidades e Pentest anual  

### Fase 2 (6–12 meses)
- Implantar SIEM, IAM/PAM e Threat Intelligence  
- Criar plano de resposta a incidentes  
- Realizar treinamentos de engenharia social  
- Consolidar políticas de conformidade e automação de relatórios  

### Fase 3 (12–24 meses)
- Implantar DevSecOps (SAST/DAST/SCA)  
- Aderir a ISO 27001 / 27701  
- Adotar CASB e ZTNA  
- Integrar monitoramento 24x7 e ISACs  

---

## 📚 8. Mapeamento de Normas e Compliance

| Norma / Framework | Área Aplicada | Requisito-Chave |
|--------------------|---------------|----------------|
| **ISO 27001:2022** | ISMS e controles A.5–A.18 | Estrutura do SGSI |
| **NIST CSF 2.0** | Identificar / Proteger / Detectar / Responder / Recuperar | Estrutura base |
| **COBIT 2019** | Governança e alinhamento estratégico | EDM, APO, DSS, MEA |
| **CIS Controls v8** | Segurança técnica operacional | 18 domínios essenciais |
| **LGPD / GDPR** | Proteção de dados pessoais | Consentimento, propósito, transparência |
| **PCI-DSS 4.0** | Ambientes com dados de pagamento | Segmentação, criptografia, monitoramento |

---

## 🧮 9. Modelo de Avaliação

```yaml
# Estrutura de scoring (exemplo YAML)
maturity_assessment:
  domains:
    - governance:
        score: 3
        actions: ["revisar PSI", "criar comitê de SI"]
    - protection:
        score: 2
        actions: ["implantar DLP", "configurar WAF"]
    - detection:
        score: 1
        actions: ["ativar SIEM", "definir alertas"]
  total_score: 2.0
  maturity_level: "Gerenciado"
