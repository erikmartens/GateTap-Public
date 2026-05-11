<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.4
Language: pl
-->

# Przewodnik konfiguracji

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🇸🇦 العربية](setup-guide.ar.md) | [🇪🇸 Català](setup-guide.ca.md) | [🇨🇿 Čeština](setup-guide.cs.md) | [🇩🇰 Dansk](setup-guide.da.md) | [🇬🇷 Ελληνικά](setup-guide.el.md) | [🇪🇸 Español](setup-guide.es.md) | [🇲🇽 Español (México)](setup-guide.es-MX.md) | [🇫🇮 Suomi](setup-guide.fi.md) | [🇫🇷 Français](setup-guide.fr.md) | [🇮🇱 עברית](setup-guide.he.md) | [🇮🇳 हिन्दी](setup-guide.hi.md) | [🇭🇷 Hrvatski](setup-guide.hr.md) | [🇭🇺 Magyar](setup-guide.hu.md) | [🇮🇩 Bahasa Indonesia](setup-guide.id.md) | [🇮🇹 Italiano](setup-guide.it.md) | [🇯🇵 日本語](setup-guide.ja.md) | [🇰🇷 한국어](setup-guide.ko.md) | [🇲🇾 Bahasa Melayu](setup-guide.ms.md) | [🇳🇴 Norsk Bokmål](setup-guide.nb.md) | [🇳🇱 Nederlands](setup-guide.nl.md) | 🇵🇱 Polski | [🇧🇷 Português (Brasil)](setup-guide.pt-BR.md) | [🇵🇹 Português (Portugal)](setup-guide.pt-PT.md) | [🇷🇴 Română](setup-guide.ro.md) | [🇷🇺 Русский](setup-guide.ru.md) | [🇸🇰 Slovenčina](setup-guide.sk.md) | [🇸🇪 Svenska](setup-guide.sv.md) | [🇹🇭 ไทย](setup-guide.th.md) | [🇹🇷 Türkçe](setup-guide.tr.md) | [🇺🇦 Українська](setup-guide.uk.md) | [🇻🇳 Tiếng Việt](setup-guide.vi.md) | [🇨🇳 简体中文](setup-guide.zh-Hans.md) | [🇹🇼 繁體中文](setup-guide.zh-Hant.md)

---

Podłącz GateTap do swojego kontrolera dostępu

## Zanim zaczniesz

Upewnij się, że urządzenie jest połączone z tą samą siecią lokalną co kontroler dostępu. Na przykład sprawdź, czy iPhone korzysta z domowej sieci Wi-Fi, a nie z transmisji danych komórkowych.

GateTap działa całkowicie w Twojej sieci lokalnej i potrzebuje:
• Adresu IP kontrolera
• Nazwy użytkownika i hasła


## Krok 1: Znajdź adres IP kontrolera dostępu

Aby połączyć GateTap, potrzebujesz adresu IP kontrolera oraz danych logowania - patrz krok 2.

Wybierz jedną z poniższych opcji:


## Opcja A: Zapytaj instalatora (zalecane)

Jeśli system został zainstalowany przez elektryka lub technika, prawdopodobnie wszystko jest już skonfigurowane.

W wielu przypadkach:
• Kontroler używa stałego adresu IP
• Albo router przydziela ten sam adres IP przez rezerwację DHCP

Poproś o adres IP i dane logowania. To zwykle najłatwiejszy i najszybszy sposób.


## Opcja B: Sprawdź swój router

Otwórz stronę konfiguracji routera i poszukaj podłączonych urządzeń.

Aby uzyskać dostęp do routera, zwykle potrzebujesz jego adresu lokalnego, np. `192.168.1.1` lub nazwy typu `fritz.box`, oraz danych logowania do routera.

Ta sekcja może nazywać się:
• Sieć
• Podłączone urządzenia
• LAN
• Klienci DHCP

Szukaj:
• Nieznanych urządzeń przewodowych
• Wpisów, które mogą oznaczać Twój kontroler

Adres IP zwykle wygląda tak:
`192.168.x.x` lub `10.0.x.x`

![Przykład podłączonych urządzeń w routerze](../assets/setup-guide/pl/img_01_en_US.png)


## Opcja C: Przeskanuj swoją sieć

Użyj aplikacji skanera sieci na swoim urządzeniu.

Przeskanuj sieć i spróbuj otworzyć znalezione adresy IP w Safari, na przykład:

`http://192.168.1.50`

Jeśli pojawi się strona logowania kontrolera dostępu, znaleziono właściwy adres.

![Przykład aplikacji skanera sieci](../assets/setup-guide/pl/img_02_en_US.png)


## Krok 2: Znajdź dane logowania kontrolera dostępu

Niektóre kontrolery nadal używają domyślnych danych logowania. Częsty przykład to nazwa użytkownika `abc` z hasłem `654321`.

Inne często używane fabryczne nazwy użytkownika to `user`, `admin` lub `123`. Możesz spróbować ich z typowymi hasłami, takimi jak `1234`, `user` lub `password`, albo ich odmianą.

Jeśli system został zainstalowany profesjonalnie, zapytaj instalatora, czy domyślne dane zostały zmienione.


## Krok 3: Dodaj kontroler dostępu w GateTap

Otwórz GateTap i wpisz:
• Adres IP
• Nazwę użytkownika
• Hasło

Użyj tych samych danych logowania co w interfejsie web kontrolera dostępu.


## Krok 4: Przetestuj połączenie

Zapisz konfigurację i spróbuj otworzyć drzwi lub bramę.

Jeśli nic się nie dzieje, sprawdź:
• Czy urządzenie jest w tej samej sieci co kontroler dostępu
• Czy adres IP jest poprawny
• Czy kontroler dostępu jest zasilany i osiągalny


## Krok 5: Utrzymuj stabilny adres IP

Aby uniknąć późniejszych problemów, kontroler powinien zawsze używać tego samego adresu IP.

Można to zrobić przez:
• Ustawienie statycznego IP na kontrolerze
• Utworzenie rezerwacji DHCP w routerze


## Tryb demo

GateTap zawiera także tryb demo. Możesz uruchomić lokalny demo serwer web z poziomu aplikacji, a następnie dodać go jak zwykły kontroler.

Daje to znaną, działającą ścieżkę testową do sprawdzenia, czy sam GateTap działa poprawnie, nawet jeśli obecnie nie masz dostępu do fizycznego kontrolera dostępu.


## Bezpieczeństwo

Twoje dane pozostają na Twoim urządzeniu.

Opcjonalnie możesz chronić GateTap za pomocą Face ID lub Touch ID w ustawieniach aplikacji.


