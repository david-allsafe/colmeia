# Colmeia

Mini-SOC em Azure com honeypot Cowrie, Microsoft Sentinel e um agente de IA para triagem de alertas.

## Estrutura

- `detections/sigma/` – regras Sigma
- `detections/kql/` – consultas KQL para o Sentinel
- `preprocessing/` – normalização e enriquecimento de logs
- `baseline/` – perfil de tráfego de referência
- `agent/` – agente de triagem por IA
- `playbooks/` – playbooks de resposta e automatização
- `eval/` – avaliação do agente
- `docs/` – documentação
- `data/` – dados locais (ignorados pelo Git)
