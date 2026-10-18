**Italiano** · [Português](README.pt.md) · [English](README.en.md)

# BIMit — plugin per Autodesk Revit

[![Ultima versione](https://img.shields.io/github/v/release/DynaTools/BIMit-Release?label=versione)](https://github.com/DynaTools/BIMit-Release/releases/latest)
![Revit 2022–2026](https://img.shields.io/badge/Revit-2022%E2%80%932026-0696D7)
![Windows 10 | 11](https://img.shields.io/badge/Windows-10%20%7C%2011-555)

BIMit assegna la **WBS** agli elementi del modello, esporta **tavole e viste** in tutti i formati in un
colpo solo e aggiunge gli strumenti che mancano in Revit per **parametri**, **modello** e impianti
**MEP**. Con **Claude (MCP)** puoi anche chiedere a Claude di farlo per te, in italiano.

Durante la **beta** BIMit è gratuito.

**[Scarica l'ultima versione (MSI)](https://github.com/DynaTools/BIMit-Release/releases/latest)** ·
[Guida](https://unibim.io/it/bimit/guida/) · [unibim.io/it/bimit](https://unibim.io/it/bimit/)

## Cosa fa

| Strumento | Cosa fa |
|---|---|
| **WBS** | Parti dalla WBS normativa o da una tua struttura, definisci i parametri una volta per tutto il progetto, cambia solo quello che serve in ogni categoria, controlla l'anteprima e scrivi nel modello. |
| **Esporta tavole e viste** | PDF, DWG, DGN, DWF, NWC, IFC e immagini in un colpo solo: formato carta dal cartiglio, nomi dei file dai parametri, solo le tavole nuove o con la revisione cambiata, coda, report, esportazioni pianificate, elenco elaborati in Excel, profili da condividere con il team. |
| **Parametri** | Aggiungi i parametri condivisi a tutte le categorie che scegli, trova ed elimina i parametri di progetto vuoti o inutili, togli dalle famiglie caricate i parametri che non servono. |
| **Modello** | Sblocca gli elementi bloccati categoria per categoria, sposta un livello con tutto quello che dipende da lui, esporta il modello in tabelle CSV per un assistente IA. |
| **MEP** | Manicotti e forometrie dove gli impianti attraversano muri, solai, travi e altri elementi; linee di separazione degli spazi dal contorno dei locali di un modello collegato. |
| **Claude (MCP)** | Collega Claude con il tuo account: usa tutti gli strumenti di BIMit sul modello aperto, anche su più Revit aperti insieme. Ogni modifica si annulla con Ctrl+Z. |

## Requisiti

- Windows 10 o 11
- Autodesk Revit 2022, 2023, 2024, 2025 o 2026
- Un account BIMit, che crei dal plugin al primo avvio

## Installazione

1. Chiudi Revit.
2. Scarica `BIMit_Setup_<versione>.msi` dall'[ultima release](https://github.com/DynaTools/BIMit-Release/releases/latest).
3. Aprilo con doppio clic. **Non servono permessi di amministratore**: BIMit si installa per il tuo
   utente, in tutte le versioni di Revit presenti.
4. Apri Revit: trovi la scheda **BIMit**.

### Installer firmato digitalmente

L'installer è firmato con un certificato di firma del codice **Certum** intestato a
**GIAVONI PAULO AUGUSTO**. Per verificarlo: clic destro sul file `.msi` → *Proprietà* →
*Firme digitali*. Se Windows SmartScreen mostra un avviso, controlla che l'editore sia
GIAVONI PAULO AUGUSTO e scegli *Ulteriori informazioni* → *Esegui comunque*.

## Aggiornamenti

Automatici: BIMit scarica la nuova versione, ne verifica l'integrità e la installa quando chiudi Revit.

## Disinstallazione

*Impostazioni di Windows* → *App* → *App installate* → **BIMit** → *Disinstalla*.
Per eliminare anche l'account e i dati: in Revit, *BIMit* → *Account* → *Elimina account*.

## Guida e documenti

| | Italiano | Português | English |
|---|---|---|---|
| Guida | [Guida](https://unibim.io/it/bimit/guida/) | [Guia](https://unibim.io/pt/bimit/guia/) | [Guide](https://unibim.io/en/bimit/guide/) |
| Privacy | [Informativa privacy](https://unibim.io/it/bimit/privacy/) | [Privacidade](https://unibim.io/pt/bimit/privacidade/) | [Privacy](https://unibim.io/en/bimit/privacy/) |
| Termini | [Termini d'uso](https://unibim.io/it/bimit/termini/) | [Termos de uso](https://unibim.io/pt/bimit/termos/) | [Terms of use](https://unibim.io/en/bimit/terms/) |

La guida si apre anche dal pulsante **Guida** in ogni finestra del plugin, sulla sezione giusta.

## Assistenza

- Dal plugin: pulsante **Feedback** in alto in ogni finestra.
- E-mail: paulo.giavoni@gmail.com

---

© DynaTools · Autodesk e Revit sono marchi registrati di Autodesk, Inc. BIMit non è affiliato né
approvato da Autodesk.
