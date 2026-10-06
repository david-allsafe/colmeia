# Pré-processamento

Pré-processamento dos alertas e da evidência vindos do Sentinel antes da triagem (baseline e agente): hash SHA-256 da evidência original, agregação por IP e janela temporal, descodificação Base64 e sanitização. Não inclui enriquecimento, que é feito pelas ferramentas do agente.
