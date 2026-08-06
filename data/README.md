# Datasett

## `talk_time.csv`

Taletid og talerturstatistikk for flere analyseomfang.

Viktige rader:

- `record1_after_chris`: Record-1 etter 19:15
- `record3_full`: hele Record-3
- `primary_two_person`: summen av disse to omfangene

Viktige felt:

- `talk_seconds` / `talk_minutes`: modellert aktiv taletid
- `attributed_share_pct`: andel av taletid som er tilskrevet navngitte talere
- `turns`: antall talerturer
- `mean_turn_s`, `median_turn_s`, `longest_turn_s`: talerturenes varighet

## `interruption_events.csv`

Tidskodede konkurrerende overlapp og vellykkede gulvovertakelser i primæranalysen.

- `competitive_overlap`: en ny taler går inn før den første er ferdig, uten at hendelsen nødvendigvis gir varig overtakelse
- `successful_floor_take`: den nye taleren starter i den andres ytring og fortsetter etter at den første stopper
- `overlap_s`: varigheten av samtidig tale
- `new_speaker_turn_s`: varigheten av den nye talerens tur
- `new_speaker_continues_after_prior_s`: hvor lenge den nye taleren fortsetter etter at den første har stoppet

CSV-filene er UTF-8-kodet og bruker punktum som desimalskilletegn.
