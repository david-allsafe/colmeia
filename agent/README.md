# Agente

Agente de triagem L1 com tool use (API Claude). Ferramentas só de leitura: consultas KQL parametrizadas ao Sentinel, reputação de IP (AbuseIPDB), URL (VirusTotal, URLhaus) e hash (VirusTotal), mapeamento MITRE ATT&CK e proposta de resposta. Saída em JSON validada por esquema. Nenhuma ação é executada sem aprovação humana.
