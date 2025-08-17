---
title: "Segurança não é nova — o que mudou foi o incentivo"
date: 2025-08-17
tags: [iso27001, auditoria, historia, ameacas]
---

Quando alguém diz “segurança é coisa nova”, vale lembrar: **não é**.  
Os **firewalls** ganharam tração nos anos 90; **antivírus** já existiam nos 80; **IDS/IPS** vieram nos 90; **VPNs** corporativas (IPsec/PPTP) também dos 90; **MFA com tokens** é de décadas atrás; **backups, criptografia e trilhas de auditoria** vêm desde a era dos mainframes. O alicerce é antigo.

O que mudou — e muito — foi o **modelo de ataque e de recompensa**.

## 1) Linha do tempo relâmpago (meios clássicos)
- **Antivírus (anos 80)**: assinaturas contra malware conhecido.  
- **Firewalls (anos 90)**: filtragem/estado, segmentação de rede.  
- **IDS/IPS (anos 90)**: detecção de anomalias/assinaturas em rede/host.  
- **VPNs (anos 90)**: túneis seguros para acesso remoto.  
- **MFA**: tokens/hard/soft (muito antes de apps modernos).  
- **Backups & DR**: rotina de sobrevivência desde sempre.  
- **Criptografia**: de DES/PGP aos padrões atuais.  
- **Logs & auditoria**: trilhas formais em sistemas críticos há décadas.

## 2) O que realmente mudou
- **Motivação**: de “status” técnico para **monetização** direta.  
- **Modelos de crime-as-a-service**: *phishing-as-a-service*, *ransomware-as-a-service*, *botnets-as-a-service*.  
- **Mercado paralelo**: **brokers de acesso inicial**, venda de dados/vazamentos, revenda de credenciais.  
- **Superfície**: cloud, SaaS, integrações e terceiros multiplicaram os pontos de risco.  
- **Automação**: kits prontos, *playbooks* ofensivos e IA barateiam o ataque.

Resultado: **mais ataques, mais rápido, mais profissionais**.

## 3) O que isso significa na prática (ISO 27001)
A ISO 27001 **não inventa moda**: ela organiza o que já funciona com **governança + risco + melhoria contínua**.  
O que muda é **como aplicamos** os controles:

- **Risco e SoA vivos**: revisar ameaças e priorizar controles com base no negócio (não checklist).  
- **Novos temas da revisão 2022**: uso de **serviços em nuvem**, **inteligência de ameaças**, prevenção de **exfiltração** e **monitoramento contínuo** ganham destaque.  
- **Evidência > papel**: logs centralizados, métricas (MTTD/MTTR), testes periódicos e *runbooks* versionados.  
- **Fornecedores**: due diligence e monitoramento contínuo (contratos, segurança de integrações, resposta a incidentes compartilhada).  
- **Pessoas e operações**: MFA consistente, *least privilege*, segregação de funções, gestão de mudanças, *hardening* e vulnerabilidades com ciclo previsível.

## 4) Checklist rápido (para você se situar)
- [ ] **Risco atualizado** e SoA refletindo realidade (cloud, SaaS, terceiros).  
- [ ] **MFA e segmentação** aplicados onde dói (admin, remoto, críticos).  
- [ ] **Logs centralizados** + casos de uso que realmente detectam.  
- [ ] **Backups testados** (RTO/RPO claros, restaurações recentes).  
- [ ] **Gestão de vulnerabilidades** com métricas de tempo de correção.  
- [ ] **Plano de resposta a incidentes** com exercícios práticos.

> **Resumo:** segurança não é novidade; o **incentivo do atacante** é.  
> A resposta continua sendo **governança + controles sólidos + evidências confiáveis** — é isso que a ISO 27001 pede desde sempre.

👉 Precisa de apoio para organizar **risco**, **SoA** e **evidências**? Fale comigo pela **[página de Contato](/contato/)**.

<div class="tl">

  <div class="tl__item tl__item--top">
    <div class="tl__card">
      <strong>Anos 80 — Antivírus</strong><br>
      Assinaturas contra malware conhecido; base do endpoint desde então.
    </div>
    <span class="tl__dot"></span>
    <div class="tl__meta">1980s</div>
  </div>

  <div class="tl__item tl__item--bottom">
    <div class="tl__card">
      <strong>Anos 90 — Firewalls</strong><br>
      Filtragem/estado e segmentação de rede viram padrão corporativo.
    </div>
    <span class="tl__dot"></span>
    <div class="tl__meta">1990s</div>
  </div>

  <div class="tl__item tl__item--top">
    <div class="tl__card">
      <strong>Anos 90 — IDS/IPS</strong><br>
      Detecção por assinaturas e anomalias em rede/host.
    </div>
    <span class="tl__dot"></span>
    <div class="tl__meta">1990s</div>
  </div>

  <div class="tl__item tl__item--bottom">
    <div class="tl__card">
      <strong>Anos 90 — VPNs</strong><br>
      Túneis IPsec/SSL para acesso remoto seguro.
    </div>
    <span class="tl__dot"></span>
    <div class="tl__meta">1990s</div>
  </div>

  <div class="tl__item tl__item--top">
    <div class="tl__card">
      <strong>Anos 2000 — MFA</strong><br>
      Tokens físicos/soft e, depois, apps; reforço a contas críticas.
    </div>
    <span class="tl__dot"></span>
    <div class="tl__meta">2000s</div>
  </div>

  <div class="tl__item tl__item--bottom">
    <div class="tl__card">
      <strong>Sempre — Backups & Criptografia</strong><br>
      Restauração testada + proteção de dados em repouso e trânsito.
    </div>
    <span class="tl__dot"></span>
    <div class="tl__meta">base</div>
  </div>

  <div class="tl__item tl__item--top">
    <div class="tl__card">
      <strong>2010s — Cloud & DevOps</strong><br>
      Superfície expandida, controles as-a-service e automação.
    </div>
    <span class="tl__dot"></span>
    <div class="tl__meta">2010+</div>
  </div>

  <div class="tl__item tl__item--bottom">
    <div class="tl__card">
      <strong>2016+ — Crime como serviço</strong><br>
      Ransomware-as-a-service, brokers de acesso e extorsão de dados.
    </div>
    <span class="tl__dot"></span>
    <div class="tl__meta">2016+</div>
  </div>

</div>

