# Itaú Suprimentos — Blueprint de Arquitetura Salesforce

Blueprint de arquitetura para o módulo de Suprimentos da rede de agências do Itaú, cobrindo o ciclo completo de logística de agências: captura de demanda, gestão de compras, OMS, transporte e logística reversa.

## Acesse o Blueprint

Abra o arquivo [`blueprint-arquitetura.html`](blueprint-arquitetura.html) diretamente no navegador para visualizar a apresentação completa.

## Conteúdo

O blueprint cobre:

- **Visão Geral** — posicionamento do Salesforce no ecossistema de sistemas (OMS, WMS, TMS, SAP, AGV)
- **Decisões Arquiteturais (ADRs)** — 7 decisões com justificativa e trade-offs
- **Modelo de Dados** — objetos Salesforce, hierarquia e campos principais
- **Arquitetura de Integração** — DigiBee como barramento único (SAP ECC, AGV WMS, OMS AWS)
- **Automação** — mapa de Flows e uso restrito de Apex
- **Portal do Fornecedor** — Experience Cloud LWR para ~90 fornecedores/fabricantes
- **Portal de Reservas** — análise de opções arquiteturais (Option A: manter Angular / Option B: Experience Cloud)
- **Perfis e Acessos** — OWD, Role Hierarchy, Permission Sets
- **Licenças** — impacto do Sales Cloud Unlimited Edition
- **Mesa de Decisão S&OE** — interface de decisão integrada ao OMS AWS (Fase 2)
- **IA & Einstein** — roadmap Agentforce para a Mesa S&OE
- **Faseamento** — 3 fases em ~18 meses
- **Dependências Críticas** — blockers e questões arquiteturais abertas
- **Governor Limits** — riscos técnicos e mitigações

## Versão

**v2.0 — 2026-09-14**  
Baseado em: Dores PDF, Diagrama de Contexto C1 (v20260911), Briefing B2B, TO-BE v20260911
