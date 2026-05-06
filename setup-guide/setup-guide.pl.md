<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.3
Language: pl
-->

# Przewodnik konfiguracji

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🌐 ar](setup-guide.ar.md) | [🌐 ca](setup-guide.ca.md) | [🌐 cs](setup-guide.cs.md) | [🌐 da](setup-guide.da.md) | [🌐 el](setup-guide.el.md) | [🌐 es](setup-guide.es.md) | [🌐 es-MX](setup-guide.es-MX.md) | [🌐 fi](setup-guide.fi.md) | [🌐 fr](setup-guide.fr.md) | [🌐 he](setup-guide.he.md) | [🌐 hi](setup-guide.hi.md) | [🌐 hr](setup-guide.hr.md) | [🌐 hu](setup-guide.hu.md) | [🌐 id](setup-guide.id.md) | [🌐 it](setup-guide.it.md) | [🌐 ja](setup-guide.ja.md) | [🌐 ko](setup-guide.ko.md) | [🌐 ms](setup-guide.ms.md) | [🌐 nb](setup-guide.nb.md) | [🌐 nl](setup-guide.nl.md) | 🌐 pl | [🌐 pt-BR](setup-guide.pt-BR.md) | [🌐 pt-PT](setup-guide.pt-PT.md) | [🌐 ro](setup-guide.ro.md) | [🌐 ru](setup-guide.ru.md) | [🌐 sk](setup-guide.sk.md) | [🌐 sv](setup-guide.sv.md) | [🌐 th](setup-guide.th.md) | [🌐 tr](setup-guide.tr.md) | [🌐 uk](setup-guide.uk.md) | [🌐 vi](setup-guide.vi.md) | [🇨🇳 中文](setup-guide.zh-Hans.md) | [🇨🇳 中文](setup-guide.zh-Hant.md)

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


