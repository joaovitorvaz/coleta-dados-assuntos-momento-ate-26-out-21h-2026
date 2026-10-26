# Assuntos do momento (até 26/out/2026 21h)

Coleta contínua dos **trending topics** Brasil (Twitee + Nitter), com busca profunda em cada tópico.

- **Início:** quando o agente foi ligado (25/out/2026)
- **Fim do agente:** **26/out/2026 21:00** (horário de Brasília)
- **Filtro de tweets:** `since` 25/out · `until` 27/out (cobre todo o domingo)

```bash
cd ../projeto-coleta
coleta trends-now-agent --config-id assuntos_momento_ate_26out21h_20261025 --mode daemon
```

Snapshot: `data/manifests/trends_live_snapshot.json`  
Dados: `data/normalized/termos/assuntos_momento_br/`
