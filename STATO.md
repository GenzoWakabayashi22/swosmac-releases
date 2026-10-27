# STATO — SWOS Mac releases (download del DMG)

> Ultimo aggiornamento: 2026-10-27 · casa · Claude Sonnet 5.5
> Riga indice: Repo pubblico che ospita solo le Release (ultima v6.8, 2026-10-27) del DMG di SWOS 2020 Mac Edition; prossimo passo: nuova Release solo se esce una nuova versione.

## Cos'è
Repo GitHub **pubblico** `GenzoWakabayashi22/swosmac-releases` (https://github.com/GenzoWakabayashi22/swosmac-releases) che contiene solo un `README.md` e, nelle **Release**, il file `SWOS-2020-Mac-Edition.dmg` (circa 215 MB; Cloudflare accetta file di 25 MB, per questo il DMG non sta nel sito). In Developer: `Siti/SwosMac-releases/`. Il sito di download è `Siti/SwosMac/` (swosmac.nathco.app).

## Dove siamo arrivati
- Ultima Release: **v6.8** (2026-10-27), «Latest», DMG 215.135.119 byte (SHA-256 `ee9c0fb2…7d47`); precedenti 6.7.2 (2026-10-16), 6.7.1 (2026-10-14), 6.7 (2026-10-13), 6.6.1 e 6.6 (2026-10-12) (letto con `gh release list`).
- Il link «latest» del sito punta alla Release più recente: si aggiorna da solo.
- Repo locale pulito e allineato con `origin/main` (2026-10-18). Ultimo commit 2026-10-09: README con la rinomina in «SWOS 2020 Mac Edition».

## Prossimo passo
1. Nessuno. Quando esce una nuova versione dell'app: `gh release create vX.Y SWOS-2020-Mac-Edition.dmg` (il file deve chiamarsi esattamente così), poi aggiornare versione e peso in `Siti/SwosMac/index.html` e ripubblicare il sito (vedi `Siti/SwosMac/STATO.md`).

## In sospeso / trappole
- Il nome del gioco è **SWOS 2020 Mac Edition** (rinomina richiesta il 2026-10-09 da sensiblesoccer.de; «SWOS United» sarà il loro prossimo gioco nativo): non usare il vecchio nome. Il vecchio file `SWOS-United-Mac.dmg` della Release v5.2 è storia (da verificare se ancora presente).
- Il DMG non è nel repo: non committarlo.
- Progetto non commerciale: gratuito, non affiliato; crediti a sensiblesoccer.de e Sensible Software.

## Come si lavora
- Release con `gh release create` (account `GenzoWakabayashi22`). Il DMG viene dall'app notarizzata (firma Developer ID); le build dell'app non stanno in questo repo.
- Nessun deploy: il repo non è un sito.
- Documento correlato: `Siti/SwosMac/STATO.md` e `Siti/SwosMac/README.md`.

## Cronologia
- 2026-10-27 — Release v6.8 (DMG notarizzato) — casa, Claude Sonnet 5.5
- 2026-10-18 — creato STATO.md dalla lettura di README/git log/documenti — casa, Claude Sonnet 5.5
- 2026-10-16 — Release v6.7.2 (DMG)
- 2026-10-14 — Release v6.7.1; 2026-10-13 v6.7; 2026-10-12 v6.6.1 e v6.6
- 2026-10-09 — README: rinomina in SWOS 2020 Mac Edition (Release v6.0)
- 2026-10-08 — primo README del repo
