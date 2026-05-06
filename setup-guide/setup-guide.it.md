<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.3
Language: it
-->

# Guida all'installazione

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🇸🇦 العربية](setup-guide.ar.md) | [🇪🇸 Català](setup-guide.ca.md) | [🇨🇿 Čeština](setup-guide.cs.md) | [🇩🇰 Dansk](setup-guide.da.md) | [🇬🇷 Ελληνικά](setup-guide.el.md) | [🇪🇸 Español](setup-guide.es.md) | [🇲🇽 Español (México)](setup-guide.es-MX.md) | [🇫🇮 Suomi](setup-guide.fi.md) | [🇫🇷 Français](setup-guide.fr.md) | [🇮🇱 עברית](setup-guide.he.md) | [🇮🇳 हिन्दी](setup-guide.hi.md) | [🇭🇷 Hrvatski](setup-guide.hr.md) | [🇭🇺 Magyar](setup-guide.hu.md) | [🇮🇩 Bahasa Indonesia](setup-guide.id.md) | 🇮🇹 Italiano | [🇯🇵 日本語](setup-guide.ja.md) | [🇰🇷 한국어](setup-guide.ko.md) | [🇲🇾 Bahasa Melayu](setup-guide.ms.md) | [🇳🇴 Norsk Bokmål](setup-guide.nb.md) | [🇳🇱 Nederlands](setup-guide.nl.md) | [🇵🇱 Polski](setup-guide.pl.md) | [🇧🇷 Português (Brasil)](setup-guide.pt-BR.md) | [🇵🇹 Português (Portugal)](setup-guide.pt-PT.md) | [🇷🇴 Română](setup-guide.ro.md) | [🇷🇺 Русский](setup-guide.ru.md) | [🇸🇰 Slovenčina](setup-guide.sk.md) | [🇸🇪 Svenska](setup-guide.sv.md) | [🇹🇭 ไทย](setup-guide.th.md) | [🇹🇷 Türkçe](setup-guide.tr.md) | [🇺🇦 Українська](setup-guide.uk.md) | [🇻🇳 Tiếng Việt](setup-guide.vi.md) | [🇨🇳 简体中文](setup-guide.zh-Hans.md) | [🇹🇼 繁體中文](setup-guide.zh-Hant.md)

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


