<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.3
Language: pl
-->

# Przewodnik konfiguracji

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🇸🇦 العربية](setup-guide.ar.md) | [🇪🇸 Català](setup-guide.ca.md) | [🇨🇿 Čeština](setup-guide.cs.md) | [🇩🇰 Dansk](setup-guide.da.md) | [🇬🇷 Ελληνικά](setup-guide.el.md) | [🇪🇸 Español](setup-guide.es.md) | [🇲🇽 Español (México)](setup-guide.es-MX.md) | [🇫🇮 Suomi](setup-guide.fi.md) | [🇫🇷 Français](setup-guide.fr.md) | [🇮🇱 עברית](setup-guide.he.md) | [🇮🇳 हिन्दी](setup-guide.hi.md) | [🇭🇷 Hrvatski](setup-guide.hr.md) | [🇭🇺 Magyar](setup-guide.hu.md) | [🇮🇩 Bahasa Indonesia](setup-guide.id.md) | [🇮🇹 Italiano](setup-guide.it.md) | [🇯🇵 日本語](setup-guide.ja.md) | [🇰🇷 한국어](setup-guide.ko.md) | [🇲🇾 Bahasa Melayu](setup-guide.ms.md) | [🇳🇴 Norsk Bokmål](setup-guide.nb.md) | [🇳🇱 Nederlands](setup-guide.nl.md) | 🇵🇱 Polski | [🇧🇷 Português (Brasil)](setup-guide.pt-BR.md) | [🇵🇹 Português (Portugal)](setup-guide.pt-PT.md) | [🇷🇴 Română](setup-guide.ro.md) | [🇷🇺 Русский](setup-guide.ru.md) | [🇸🇰 Slovenčina](setup-guide.sk.md) | [🇸🇪 Svenska](setup-guide.sv.md) | [🇹🇭 ไทย](setup-guide.th.md) | [🇹🇷 Türkçe](setup-guide.tr.md) | [🇺🇦 Українська](setup-guide.uk.md) | [🇻🇳 Tiếng Việt](setup-guide.vi.md) | [🇨🇳 简体中文](setup-guide.zh-Hans.md) | [🇹🇼 繁體中文](setup-guide.zh-Hant.md)

---

Podłącz GateTap do swojego kontrolera dostępu

## Zanim zaczniesz

Upewnij się, że Twój iPhone jest podłączony do tej samej sieci lokalnej, co kontroler dostępu.

GateTap działa całkowicie w obrębie Twojej sieci lokalnej i potrzebuje:
• Adres IP kontrolera
• Nazwa użytkownika i hasło


## Krok 1: Znajdź adres kontrolera i dane uwierzytelniające

Aby połączyć się z GateTap, potrzebujesz adresu IP kontrolera i danych logowania.

Wybierz jedną z następujących opcji:


## Opcja A: Zapytaj instalatora (zalecane)

Jeśli Twój system został zainstalowany przez elektryka lub technika, prawdopodobnie wszystko już skonfigurowali.

W wielu przypadkach:
• Kontroler wykorzystuje stały adres IP
• Lub router przydziela ten sam adres IP poprzez rezerwację

Zapytaj ich o adres IP i dane do logowania. Jest to zazwyczaj najłatwiejszy i najszybszy sposób.


## Opcja B: Sprawdź swój router

Otwórz stronę konfiguracji routera i poszukaj podłączonych urządzeń.

Aby uzyskać dostęp do routera, zazwyczaj potrzebujesz jego adresu lokalnego (np. `192.168.1.1` lub nazwy typu `fritz.box`) i danych logowania do routera.

Ta sekcja może nosić nazwę:
• Podłączone urządzenia
• LAN
• Klienci DHCP

Poszukaj:
• Nieznane urządzenia przewodowe
• Wpisy, które mogą reprezentować Twój kontroler

Adres IP będzie zazwyczaj wyglądał następująco:
`192.168.x.x` lub `10.0.x.x`

![Przykład urządzeń podłączonych do routera](../assets/setup-guide/pl/img_01.png)


## Opcja C: Przeskanuj swoją sieć

Użyj aplikacji skanera sieciowego na swoim iPhonie lub komputerze.

Przeskanuj swoją sieć i spróbuj otworzyć wykryte adresy IP w przeglądarce Safari, na przykład:

`http://192.168.1.50`

Jeśli pojawi się strona logowania kontrolera, znalazłeś właściwy adres.

![Przykład skanera sieciowego](../assets/setup-guide/pl/img_02.png)


## Krok 2: Dodaj kontroler w GateTap

Otwórz GateTap i wpisz:
• Adres IP
• Twoja nazwa użytkownika
• Twoje hasło

Użyj tych samych danych uwierzytelniających, co w przypadku interfejsu sieciowego kontrolera.


## Krok 3: Przetestuj połączenie

Zapisz konfigurację i spróbuj otworzyć drzwi lub bramę.

Jeśli nic się nie dzieje, sprawdź:
• Twój iPhone jest w tej samej sieci
• Adres IP jest poprawny
• Kontroler jest zasilany i osiągalny


## Krok 4: Utrzymuj stabilny adres IP

Aby uniknąć późniejszych problemów, kontroler powinien zawsze używać tego samego adresu IP.

Można tego dokonać poprzez:
• Ustawienie statycznego adresu IP na kontrolerze
• Tworzenie rezerwacji DHCP w routerze


## Bezpieczeństwo

Twoje dane pozostają na Twoim urządzeniu.

Opcjonalnie możesz chronić GateTap za pomocą Face ID lub Touch ID w ustawieniach aplikacji.


