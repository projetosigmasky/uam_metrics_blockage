# UAM KPI/KPA Dashboard — rodada fora da condição nominal: bloqueio de espaço aéreo

Site estático (GitHub Pages) com os resultados da rodada **bloqueio de espaço aéreo** de
06/11/2026 do projeto SIGMASky: 36 cenários (C1.x a C8.x) × 50 réplicas.

- RUN do orquestrador: `20261110_103558_8917e3db` (`/dados/orbolato/runs/sim_off_nominal_20261106/blockage` no Lessonia).
- Gerado com [projetosigmasky/uam_metrics](https://github.com/projetosigmasky/uam_metrics) `0fcf2af`
  (`generate_reports.py --run-id 20261110_103558_8917e3db --scenario-codes <36 códigos>`).
- Inclui a análise separada eVTOL × tráfego aeroportuário (FR24, dia de pico de SBSP,
  01/12/2022) na aba Segurança e em `assets/data/airport_traffic/`.

- A rodada nominal correspondente está em https://projetosigmasky.github.io/uam_metrics/.
- Sem os arquivos de auditoria locais (`passage_events.jsonl`, `waypoints_by_replica.csv`,
  `assets/data/runs/`) e sem a calibração dos baselines, que pertence à rodada nominal.
