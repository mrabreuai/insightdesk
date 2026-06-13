# InsightDesk
> Plataforma de insights automáticos para atendimento ao cliente com IA Generativa

**Disciplina:** Fundamentos de Gestão de Projetos  
**Professor:** Paulo Lisboa  
**Instituição:** UniFECAF 

**Aluna:** Marcia Regina de Abreu

**RA:** 246330

**Trabalho:** Do Problema ao Produto — Planejamento de um Produto Digital com IA, MVP e Roadmap

---

## O Problema

Times de atendimento ao cliente em empresas de médio e grande porte lidam com volumes gigantescos de tickets, chats e e-mails. O resultado: incapacidade de priorizar temas críticos e gerar planos de ação com agilidade — o que compromete a qualidade do serviço e a satisfação do cliente.

## A Solução

O **InsightDesk** é uma plataforma SaaS baseada em IA Generativa que:
- Ingere automaticamente dados de atendimento (tickets, chats, e-mails)
- Classifica e agrupa temas por urgência e impacto
- Gera sugestões de planos de ação por tema em minutos
- Entrega visibilidade estratégica para gerentes e diretores de CX

---

## Artefatos do Projeto

| Artefato | Descrição | Link |
|----------|-----------|------|
| Canvas de Visão de Produto | Lean Canvas com os 9 blocos estratégicos do InsightDesk | https://insightdesk.netlify.app |
| Matriz de Riscos | 8 riscos classificados por probabilidade × impacto com planos de mitigação | https://insightdesk.netlify.app/riscos |
| Parte Teórica | Documento Word com visão, MVP, roadmap, ciclo de vida e gestão de riscos | `InsightDesk_Parte_Teorica.docx` |

---

## Lógica do Planejamento

### 1. Por que Lean Canvas?

O Lean Canvas (Ash Maurya) foi escolhido por ser o framework mais adequado para produtos digitais em estágio inicial. Diferente do Business Model Canvas, ele coloca **problema e solução no centro** — o que reflete exatamente o desafio do enunciado: partir de um problema real para estruturar um produto viável.

### 2. Por que esse MVP?

O MVP foi definido com base no framework **RICE** (Reach, Impact, Confidence, Effort), priorizando funcionalidades de alto alcance e alto impacto com menor esforço de desenvolvimento. A hipótese central é:

> *"Times de atendimento conseguem priorizar ações com mais eficiência quando insights sobre temas críticos são gerados automaticamente."*

As funcionalidades **Must Have** do MVP são:
- Ingestão de tickets via API (Zendesk/Freshdesk)
- Classificação automática de temas por IA
- Dashboard de temas críticos com ranking de urgência
- Sugestão automática de plano de ação por tema

Integrações de chat ao vivo e modelos preditivos foram deliberadamente excluídos do MVP — seguindo o princípio do Scrum Guide (2020) de **maximizar o trabalho não realizado**.

### 3. Como interpretar o Roadmap?

O roadmap é organizado em **4 fases incrementais**:

| Fase | Foco | Período |
|------|------|---------|
| 1 — MVP | Validar hipótese central com tickets | Semanas 1–6 |
| 2 — Expansão | Ampliar canais (e-mail) e análise histórica | Semanas 7–14 |
| 3 — Inteligência | Análise preditiva e recomendações personalizadas | Semanas 15–24 |
| 4 — Escala | Plataforma SaaS multi-tenant com onboarding self-service | Mês 7+ |

Cada fase tem **critérios de avanço mensuráveis** — sem evidência, não se avança. Essa abordagem reflete os pilares de **transparência, inspeção e adaptação** do Scrum (Schwaber & Sutherland, 2020).

### 4. Como interpretar a Matriz de Riscos?

A matriz segue a metodologia do **PMI/PMBOK 7ª ed.**, com dois eixos:
- **Probabilidade** (Alta / Média / Baixa)
- **Impacto** (Alto / Médio / Baixo)

A posição de cada risco no quadrante determina a estratégia de resposta:

| Quadrante | Cor | Estratégia |
|-----------|-----|------------|
| Alta prob. + Alto impacto | 🔴 Vermelho | Escalar / Mitigar imediatamente |
| Média prob. + Alto impacto | 🟠 Laranja | Mitigar com plano estruturado |
| Alta prob. + Médio impacto | 🟠 Laranja | Planejar resposta |
| Baixa prob. + Alto impacto | 🟡 Amarelo | Monitorar de perto |
| Baixa prob. + Baixo impacto | 🟢 Verde | Registrar e aceitar |

Os **8 riscos identificados** cobrem quatro dimensões: técnica (qualidade de dados, alucinação, custo de LLM), organizacional (adoção, perda de talento), legal (LGPD) e mercado (concorrência, dependência de API).

### 5. Ciclo de Vida vs. Roadmap — qual a diferença?

- O **roadmap** descreve a evolução das funcionalidades do produto ao longo do tempo
- O **ciclo de vida** descreve as macro-fases estratégicas do produto como negócio: Descoberta → Validação → Entrega → Evolução

O InsightDesk pode estar na **Fase C (Entrega)** do ciclo de vida enquanto ainda executa a **Fase 2 (Expansão)** do roadmap — são dimensões complementares, não redundantes.

---

## Fontes e Referências

- **PMI** — Project Management Institute. *PMBOK Guide*, 7ª ed., 2021. https://www.pmi.org
- **Scrum Guide** — Schwaber, K.; Sutherland, J. *The Scrum Guide*, 2020. https://scrumguides.org
- **LGPD** — Lei nº 13.709/2018. Lei Geral de Proteção de Dados Pessoais.
- **Disciplina** — Fundamentos de Gestão de Projetos. Prof. Paulo Lisboa. UniFECAF, 2025.
- **Lean Canvas** — Maurya, A. *Running Lean*, 3ª ed. O'Reilly Media, 2022.

---

## Estrutura de Arquivos da Entrega

```
insightdesk/
├── index.html                          ← Canvas de Visão de Produto (online)
├── riscos.html                         ← Matriz de Riscos (online)
├── InsightDesk_Parte_Teorica.docx      ← Documento teórico completo
└── README.md                           ← Este arquivo
```

---

*InsightDesk · Fundamentos de Gestão de Projetos · UniFECAF · 2026*
