<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.3
Language: it
-->

# Guida all'installazione

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🌐 ar](setup-guide.ar.md) | [🌐 ca](setup-guide.ca.md) | [🌐 cs](setup-guide.cs.md) | [🌐 da](setup-guide.da.md) | [🌐 el](setup-guide.el.md) | [🌐 es](setup-guide.es.md) | [🌐 es-MX](setup-guide.es-MX.md) | [🌐 fi](setup-guide.fi.md) | [🌐 fr](setup-guide.fr.md) | [🌐 he](setup-guide.he.md) | [🌐 hi](setup-guide.hi.md) | [🌐 hr](setup-guide.hr.md) | [🌐 hu](setup-guide.hu.md) | [🌐 id](setup-guide.id.md) | 🌐 it | [🌐 ja](setup-guide.ja.md) | [🌐 ko](setup-guide.ko.md) | [🌐 ms](setup-guide.ms.md) | [🌐 nb](setup-guide.nb.md) | [🌐 nl](setup-guide.nl.md) | [🌐 pl](setup-guide.pl.md) | [🌐 pt-BR](setup-guide.pt-BR.md) | [🌐 pt-PT](setup-guide.pt-PT.md) | [🌐 ro](setup-guide.ro.md) | [🌐 ru](setup-guide.ru.md) | [🌐 sk](setup-guide.sk.md) | [🌐 sv](setup-guide.sv.md) | [🌐 th](setup-guide.th.md) | [🌐 tr](setup-guide.tr.md) | [🌐 uk](setup-guide.uk.md) | [🌐 vi](setup-guide.vi.md) | [🇨🇳 中文](setup-guide.zh-Hans.md) | [🇨🇳 中文](setup-guide.zh-Hant.md)

---

Collega GateTap al tuo controller di accesso

## Prima di iniziare

Assicurati che il tuo iPhone sia connesso alla stessa rete locale del controller di accesso.

GateTap funziona interamente all'interno della tua rete locale e necessita di:
• L'indirizzo IP del controller
• Un nome utente e una password


## Passaggio 1: trovare l'indirizzo e le credenziali del controller

Per connettere GateTap sono necessari l'indirizzo IP del controller e le credenziali di accesso.

Scegli una delle seguenti opzioni:


## Opzione A: chiedi al tuo installatore (consigliato)

Se il tuo sistema è stato installato da un elettricista o da un tecnico, probabilmente hanno già configurato tutto.

In molti casi:
• Il controller utilizza un indirizzo IP fisso
• Oppure il router assegna lo stesso IP tramite prenotazione

Chiedi loro l'indirizzo IP e i dettagli di accesso. Questo di solito è il modo più semplice e veloce.


## Opzione B: controlla il tuo router

Apri la pagina di configurazione del tuo router e cerca i dispositivi collegati.

Per accedere al router, di solito è necessario il suo indirizzo locale (ad esempio `192.168.1.1` o un nome come `fritz.box`) e le credenziali di accesso del router.

Questa sezione può essere chiamata:
• Dispositivi connessi
• LAN
• Client DHCP

Cerca:
• Dispositivi cablati sconosciuti
• Voci che potrebbero rappresentare il controller

L'indirizzo IP solitamente sarà simile a:
`192.168.x.x` o `10.0.x.x`.

![Esempio di dispositivi connessi al router](../assets/setup-guide/it/img_01.png)


## Opzione C: scansiona la tua rete

Utilizza un'app per scanner di rete sul tuo iPhone o computer.

Scansiona la tua rete e prova ad aprire gli indirizzi IP rilevati in Safari, ad esempio:

`http://192.168.1.50`.

Se viene visualizzata la pagina di accesso del controller, hai trovato l'indirizzo corretto.

![Esempio di scanner di rete](../assets/setup-guide/it/img_02.png)


## Passaggio 2: aggiungi il controller in GateTap

Apri GateTap e inserisci:
• L'indirizzo IP
• Il tuo nome utente
• La tua password

Utilizzare le stesse credenziali dell'interfaccia web del controller.


## Passaggio 3: testare la connessione

Salva la tua configurazione e prova ad aprire una porta o un cancello.

Se non succede nulla, controlla:
• Il tuo iPhone è sulla stessa rete
• L'indirizzo IP è corretto
• Il controller sia alimentato e raggiungibile


## Passaggio 4: mantieni stabile l'indirizzo IP

Per evitare problemi in seguito, il controller dovrebbe utilizzare sempre lo stesso indirizzo IP.

Questo può essere fatto:
• Impostazione di un IP statico sul controller
• Creazione di una prenotazione DHCP nel router


## Sicurezza

I tuoi dati rimangono sul tuo dispositivo.

Facoltativamente puoi proteggere GateTap utilizzando Face ID o Touch ID nelle impostazioni dell'app.


