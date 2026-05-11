<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.4
Language: it
-->

# Guida all'installazione

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🇸🇦 العربية](setup-guide.ar.md) | [🇪🇸 Català](setup-guide.ca.md) | [🇨🇿 Čeština](setup-guide.cs.md) | [🇩🇰 Dansk](setup-guide.da.md) | [🇬🇷 Ελληνικά](setup-guide.el.md) | [🇪🇸 Español](setup-guide.es.md) | [🇲🇽 Español (México)](setup-guide.es-MX.md) | [🇫🇮 Suomi](setup-guide.fi.md) | [🇫🇷 Français](setup-guide.fr.md) | [🇮🇱 עברית](setup-guide.he.md) | [🇮🇳 हिन्दी](setup-guide.hi.md) | [🇭🇷 Hrvatski](setup-guide.hr.md) | [🇭🇺 Magyar](setup-guide.hu.md) | [🇮🇩 Bahasa Indonesia](setup-guide.id.md) | 🇮🇹 Italiano | [🇯🇵 日本語](setup-guide.ja.md) | [🇰🇷 한국어](setup-guide.ko.md) | [🇲🇾 Bahasa Melayu](setup-guide.ms.md) | [🇳🇴 Norsk Bokmål](setup-guide.nb.md) | [🇳🇱 Nederlands](setup-guide.nl.md) | [🇵🇱 Polski](setup-guide.pl.md) | [🇧🇷 Português (Brasil)](setup-guide.pt-BR.md) | [🇵🇹 Português (Portugal)](setup-guide.pt-PT.md) | [🇷🇴 Română](setup-guide.ro.md) | [🇷🇺 Русский](setup-guide.ru.md) | [🇸🇰 Slovenčina](setup-guide.sk.md) | [🇸🇪 Svenska](setup-guide.sv.md) | [🇹🇭 ไทย](setup-guide.th.md) | [🇹🇷 Türkçe](setup-guide.tr.md) | [🇺🇦 Українська](setup-guide.uk.md) | [🇻🇳 Tiếng Việt](setup-guide.vi.md) | [🇨🇳 简体中文](setup-guide.zh-Hans.md) | [🇹🇼 繁體中文](setup-guide.zh-Hant.md)

---

Collega GateTap al tuo controller di accesso

## Prima di iniziare

Assicurati che il dispositivo sia connesso alla stessa rete locale del controller di accesso. Ad esempio, verifica che l’iPhone sia collegato al Wi-Fi di casa e non a una connessione dati mobile.

GateTap funziona interamente all’interno della tua rete locale e richiede:

- L’indirizzo IP del controller
- Un nome utente e una password


## Passaggio 1: trova l’indirizzo IP del controller di accesso

Per collegare GateTap, ti servono l’indirizzo IP del controller e le credenziali di accesso - vedi il passaggio 2.

Scegli una delle seguenti opzioni:


## Opzione A: chiedi al tuo installatore (consigliato)

Se il sistema è stato installato da un elettricista o da un tecnico, probabilmente ha già configurato tutto.

In molti casi:

- Il controller usa un indirizzo IP fisso
- Oppure il router assegna lo stesso IP tramite una prenotazione DHCP

Chiedi l’indirizzo IP e le credenziali di accesso. Di solito è il modo più semplice e veloce.


## Opzione B: controlla il tuo router

Apri la pagina di configurazione del router e cerca i dispositivi connessi.

Per accedere al router, di solito servono il suo indirizzo locale, ad esempio `192.168.1.1` o un nome come `fritz.box`, e le credenziali del router.

Questa sezione potrebbe chiamarsi:

- Rete
- Dispositivi connessi
- LAN
- Client DHCP

Cerca:

- Dispositivi cablati sconosciuti
- Voci che potrebbero rappresentare il controller

L’indirizzo IP di solito ha questo aspetto:
`192.168.x.x` o `10.0.x.x`

![Esempio di dispositivi connessi nel router](../assets/setup-guide/it/img_01_en_US.png)


## Opzione C: scansiona la tua rete

Usa un’app di scansione della rete sul tuo dispositivo.

Scansiona la rete e prova ad aprire in Safari gli indirizzi IP trovati, ad esempio:

`http://192.168.1.50`

Se appare la pagina di accesso del controller di accesso, hai trovato l’indirizzo corretto.

![Esempio di app di scansione della rete](../assets/setup-guide/it/img_02_en_US.png)


## Passaggio 2: trova le credenziali del controller di accesso

Alcuni controller usano ancora credenziali di accesso predefinite. Un esempio comune è il nome utente `abc` con la password `654321`.

Altri nomi utente di fabbrica comuni sono `user`, `admin` o `123`. Puoi provarli con password tipiche come `1234`, `user` o `password`, oppure con una variante.

Se il sistema è stato installato professionalmente, chiedi all’installatore se le credenziali predefinite sono state cambiate.


## Passaggio 3: aggiungi il controller di accesso in GateTap

Apri GateTap e inserisci:

- L’indirizzo IP
- Il nome utente
- La password

Usa le stesse credenziali dell’interfaccia web del controller di accesso.


## Passaggio 4: testa la connessione

Salva la configurazione e prova ad aprire una porta o un cancello.

Se non succede nulla, controlla:

- Che il dispositivo sia sulla stessa rete del controller di accesso
- Che l’indirizzo IP sia corretto
- Che il controller di accesso sia alimentato e raggiungibile


## Passaggio 5: mantieni stabile l’indirizzo IP

Per evitare problemi in seguito, il controller dovrebbe usare sempre lo stesso indirizzo IP.

Puoi farlo in questo modo:

- Impostando un IP statico sul controller
- Creando una prenotazione DHCP nel router


## Modalità demo

GateTap include anche una modalità demo. Puoi avviare un server web demo locale dall’app e poi aggiungerlo come un controller normale.

Questo ti offre un percorso di prova noto e funzionante per verificare che GateTap funzioni correttamente, anche se al momento non hai accesso a un controller di accesso fisico.


## Sicurezza

I tuoi dati rimangono sul tuo dispositivo.

Facoltativamente puoi proteggere GateTap utilizzando Face ID o Touch ID nelle impostazioni dell'app.


