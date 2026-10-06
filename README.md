# Colmeia

Mini-SOC em Azure com honeypot Cowrie, Microsoft Sentinel e um agente de IA para triagem de alertas.

## Estrutura

- `detections/sigma/` – regras Sigma
- `detections/kql/` – consultas KQL para o Sentinel
- `preprocessing/` – preparação dos alertas do Sentinel antes da triagem (hash, agregação, descodificação, sanitização)
- `baseline/` – triagem determinística por regras, como termo de comparação com a IA
- `agent/` – agente de triagem por IA
- `playbooks/` – playbooks/SOPs que orientam a investigação e a severidade do agente
- `eval/` – avaliação do agente
- `docs/` – documentação
- `data/` – dados locais (ignorados pelo Git)
