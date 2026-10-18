# Informativa privacy di BIMit

*Ultimo aggiornamento: 18 ottobre 2026*

Questa informativa spiega quali dati personali tratta il plugin BIMit per Autodesk Revit, perché
e quali sono i tuoi diritti, ai sensi del Regolamento (UE) 2016/679 (GDPR).

## Titolare del trattamento

Paulo Giavoni — DynaTools
E-mail: paulo.giavoni@gmail.com

## Cosa non raccogliamo

**Il contenuto dei tuoi modelli non lascia mai il tuo computer per opera di BIMit.** BIMit legge e
scrive i modelli Revit solo in locale: nomi dei file, elementi, parametri, valori e configurazioni
WBS non vengono inviati ai nostri server.

## Claude (MCP)

Se attivi **Claude (MCP)** e usi un client MCP (Claude Desktop, Claude Code o altri), BIMit risponde
alle richieste di quel client, e solo sul tuo computer: il collegamento è locale, riservato al tuo
utente Windows, e si spegne quando chiudi Revit. Quello che chiedi a Claude e i dati del modello che
Claude legge con gli strumenti di BIMit (elementi, parametri, configurazioni, file che gli indichi)
vengono inviati da quel client ad **Anthropic** (o al fornitore del client che usi), con il **tuo**
account e secondo le sue condizioni e la sua informativa privacy. Per quei dati il titolare è il
fornitore del client, non DynaTools. Se non attivi Claude (MCP), non cambia nulla.

Ogni Revit con MCP acceso annota in `%LOCALAPPDATA%\BIMit\Mcp\istanze` la sua versione e il suo
collegamento, perché Claude trovi tutti i Revit aperti; la nota si cancella quando spegni MCP o
chiudi Revit.

## Quali dati trattiamo

| Dati | Quando | Perché | Base giuridica |
|---|---|---|---|
| E-mail e password dell'account BIMit | Registrazione e accesso | Identificarti e proteggere l'accesso | Esecuzione del contratto (art. 6.1.b) |
| Nome, cognome, paese, città | Registrazione, profilo | Gestire l'account e l'assistenza, conoscere la diffusione del prodotto | Esecuzione del contratto (art. 6.1.b) |
| Piano, data di accettazione dei termini | Registrazione | Gestire la licenza | Esecuzione del contratto (art. 6.1.b) |
| Consenso al marketing e sua data | Se lo dai (facoltativo) | Inviarti novità, guide e offerte su BIMit e sugli altri prodotti DynaTools | Consenso (art. 6.1.a) |
| Versione di BIMit e di Revit, data e ora dell'ultimo utilizzo | A ogni avvio di Revit e, mentre Revit è aperto e hai fatto l'accesso, circa ogni 10 minuti | Gestire aggiornamenti e compatibilità, sapere quanti usano BIMit e chi lo sta usando in quel momento | Esecuzione del contratto (art. 6.1.b) |
| Statistiche d'uso: quali funzioni usi (avvio, comandi, nomi degli strumenti chiamati da Claude e se sono riusciti, numero di elementi scritti e di errori, tipo di errore) collegate al tuo account; mai i contenuti delle richieste | Durante l'uso (disattivabile) | Migliorare il prodotto e correggere errori | Legittimo interesse (art. 6.1.f) |
| Messaggi di feedback e, se scegli di allegarle, le ultime righe del registro tecnico di BIMit | Quando ci scrivi dal plugin | Rispondere e risolvere il problema | Esecuzione del contratto (art. 6.1.b) |

La password è gestita da Google Firebase Authentication: noi non la vediamo mai.

L'ultimo utilizzo è un solo valore per account (data e ora dell'ultimo segnale, con versione di BIMit e di
Revit), che viene sovrascritto: non è una cronologia delle tue sessioni. Lo vede solo il titolare, per
sapere quanti usano BIMit e se in quel momento è aperto.

Puoi disattivare le statistiche d'uso in qualsiasi momento: *BIMit* → *Account* → *Privacy*.

## Dove sono conservati i dati

I dati sono conservati su Google Firebase (Google Cloud): le funzioni del servizio sono eseguite
nell'Unione Europea (Belgio), il database si trova negli **Stati Uniti**. Il trasferimento verso
Google LLC avviene sulla base dell'EU-US Data Privacy Framework e delle clausole contrattuali
standard della Commissione Europea.

Sul tuo computer BIMit salva, nella cartella `%LOCALAPPDATA%\BIMit`, la sessione di accesso
(cifrata con Windows), le impostazioni e un registro tecnico che si cancella dopo 14 giorni.

## Per quanto tempo

- Account, profilo e messaggi di feedback: finché non elimini l'account.
- Statistiche d'uso: al massimo 24 mesi, poi vengono cancellate automaticamente.
- Consenso al marketing: finché non lo revochi.

## Chi può vedere i dati

Solo il titolare. I dati non vengono venduti né ceduti a terzi. Google agisce come responsabile
del trattamento per l'infrastruttura.

## I tuoi diritti

Puoi chiedere in qualsiasi momento l'accesso ai tuoi dati, la rettifica, la cancellazione, la
limitazione, la portabilità, e opporti al trattamento basato sul legittimo interesse.

- **Revocare il consenso al marketing** o disattivare le statistiche: *BIMit* → *Account*.
- **Eliminare l'account e tutti i dati** (profilo, statistiche, messaggi e account):
  *BIMit* → *Account* → *Elimina account*. L'operazione è immediata e non si può annullare.
- Per tutte le altre richieste scrivi a paulo.giavoni@gmail.com: rispondiamo entro 30 giorni.

Hai anche il diritto di proporre reclamo al Garante per la protezione dei dati personali
([www.garanteprivacy.it](https://www.garanteprivacy.it)).

## Modifiche

Se questa informativa cambia in modo sostanziale te lo diremo nel plugin. La versione in vigore è
sempre questa pagina.
