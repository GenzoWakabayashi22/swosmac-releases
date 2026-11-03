# STATO — SWOS Mac releases (download del DMG)

> Ultimo aggiornamento: 2026-11-03 · casa · Claude Sonnet 5.5
> Riga indice: Repo pubblico che ospita solo le Release (ultima v7.2, 2026-11-03) del DMG di SWOS Mac (SWOS 2020 + OpenSWOS + mod 96/97 di Davide); il file si chiama SWOS-Mac.dmg; prossimo passo: nuova Release solo se esce una nuova versione.

## Cos'è
Repo GitHub **pubblico** `GenzoWakabayashi22/swosmac-releases` (https://github.com/GenzoWakabayashi22/swosmac-releases) che contiene solo un `README.md` e, nelle **Release**, il file `SWOS-2020-Mac-Edition.dmg` (circa 215 MB; Cloudflare accetta file di 25 MB, per questo il DMG non sta nel sito). In Developer: `Siti/SwosMac-releases/`. Il sito di download è `Siti/SwosMac/` (swosmac.nathco.app).

## Dove siamo arrivati
- **Ultima Release: v7.2 (2026-11-03), «Latest»**, titolo «SWOS Mac 7.2», `SWOS-Mac.dmg` 276.783.030 byte, SHA-256 `73aa071b7038f94ca2c8c9945e5e5c79dc46d1794ec92d5c954ad7bf03c81895` (digest GitHub = file locale; link «latest» risponde 200 con la stessa dimensione). OpenSWOS `4708b6ab` + crediti di tutti. Tag `v7.2` nel repo privato SWOS (commit 9fe9697, `main` portato lì). La v7.1 resta nelle Release.
- Precedente: v7.1 (2026-11-01), titolo «SWOS Mac 7.1», `SWOS-Mac.dmg` 277.828.055 byte, SHA-256 `b2623053e18434a6bda7d9a47ab34677e0ea499a51f94c07b4e17a0ac3a73ae4` (scaricato dal link «latest» e confrontato). Include la mod di Davide Lorigliola e DOSBox Staging. Tag `v7.1` nel repo privato SWOS (commit a9a27c4). La v7.0 (235.723.952 byte) resta nelle Release.
- **Ultima Release: v7.0 (2026-11-01), «Latest»**, titolo «SWOS Mac 7.0», DMG `SWOS-Mac.dmg` 235.723.952 byte, SHA-256 `baafb69b656d17b6e488f6c040c447527ce7adca15610145f38f4c5d90b7800e` (scaricato dal link «latest» e confrontato). **Cambio di nome del file:** i vecchi link a `SWOS-2020-Mac-Edition.dmg` con `latest` ora danno 404; le Release fino alla 6.8 conservano il vecchio nome. Tag `v7.0` anche nel repo privato SWOS (commit 0294e17).
- Ultima Release: **v6.8** (2026-10-27), «Latest», DMG 215.135.119 byte (SHA-256 `ee9c0fb2…7d47`); precedenti 6.7.2 (2026-10-16), 6.7.1 (2026-10-14), 6.7 (2026-10-13), 6.6.1 e 6.6 (2026-10-12) (letto con `gh release list`).
- Il link «latest» del sito punta alla Release più recente: si aggiorna da solo.
- Repo locale pulito e allineato con `origin/main` (2026-10-18). Ultimo commit 2026-10-09: README con la rinomina in «SWOS 2020 Mac Edition».

## Prossimo passo
1. Nessuno. Quando esce una nuova versione dell'app: `gh release create vX.Y SWOS-Mac.dmg` (il file deve chiamarsi esattamente così, dalla 7.0), poi aggiornare versione e peso in `Siti/SwosMac/index.html` e ripubblicare il sito (vedi `Siti/SwosMac/STATO.md`).

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
