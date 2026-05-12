<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.4
Language: ko
-->

# 설정 가이드

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🇸🇦 العربية](setup-guide.ar.md) | [🇪🇸 Català](setup-guide.ca.md) | [🇨🇿 Čeština](setup-guide.cs.md) | [🇩🇰 Dansk](setup-guide.da.md) | [🇬🇷 Ελληνικά](setup-guide.el.md) | [🇪🇸 Español](setup-guide.es.md) | [🇲🇽 Español (México)](setup-guide.es-MX.md) | [🇫🇮 Suomi](setup-guide.fi.md) | [🇫🇷 Français](setup-guide.fr.md) | [🇮🇱 עברית](setup-guide.he.md) | [🇮🇳 हिन्दी](setup-guide.hi.md) | [🇭🇷 Hrvatski](setup-guide.hr.md) | [🇭🇺 Magyar](setup-guide.hu.md) | [🇮🇩 Bahasa Indonesia](setup-guide.id.md) | [🇮🇹 Italiano](setup-guide.it.md) | [🇯🇵 日本語](setup-guide.ja.md) | 🇰🇷 한국어 | [🇲🇾 Bahasa Melayu](setup-guide.ms.md) | [🇳🇴 Norsk Bokmål](setup-guide.nb.md) | [🇳🇱 Nederlands](setup-guide.nl.md) | [🇵🇱 Polski](setup-guide.pl.md) | [🇧🇷 Português (Brasil)](setup-guide.pt-BR.md) | [🇵🇹 Português (Portugal)](setup-guide.pt-PT.md) | [🇷🇴 Română](setup-guide.ro.md) | [🇷🇺 Русский](setup-guide.ru.md) | [🇸🇰 Slovenčina](setup-guide.sk.md) | [🇸🇪 Svenska](setup-guide.sv.md) | [🇹🇭 ไทย](setup-guide.th.md) | [🇹🇷 Türkçe](setup-guide.tr.md) | [🇺🇦 Українська](setup-guide.uk.md) | [🇻🇳 Tiếng Việt](setup-guide.vi.md) | [🇨🇳 简体中文](setup-guide.zh-Hans.md) | [🇹🇼 繁體中文](setup-guide.zh-Hant.md)

---

GateTap을 액세스 컨트롤러에 연결하세요

## 액세스 컨트롤러란?

액세스 컨트롤러는 문, 게이트, 차고 또는 차단기의 열림을 관리하는 장치입니다. 예를 들어 도어 버저나 게이트 모터를 작동시킵니다.
일반적으로 열림 신호는 다음에서 받습니다.

- 인터폰 시스템
- 키패드
- 키 포브 또는 출입 카드

많은 최신 출입 제어 시스템은 로컬 네트워크에 연결되어 있으며 브라우저의 웹 인터페이스를 통해 작동할 수 있습니다. GateTap은 해당 시스템에 직접 연결되어 기기에서 편리하게 제어할 수 있게 해 줍니다.


## 시작하기 전에

기기가 액세스 컨트롤러와 동일한 로컬 네트워크에 연결되어 있는지 확인하세요. 예를 들어 iPhone이 모바일 데이터를 사용하지 않고 집 Wi‑Fi에 연결되어 있는지 확인하세요.

GateTap은 로컬 네트워크 안에서만 작동하며 다음이 필요합니다.

- 컨트롤러의 IP 주소
- 사용자 이름과 비밀번호


## 1단계: 액세스 컨트롤러의 IP 주소 찾기

GateTap을 연결하려면 컨트롤러의 IP 주소와 로그인 정보가 필요합니다 — 2단계를 참조하세요.

다음 옵션 중 하나를 선택하세요.


## 옵션 A: 설치자에게 문의(권장)

시스템을 전기 기사나 기술자가 설치했다면 이미 모든 설정을 완료했을 가능성이 높습니다.

대부분의 경우:

- 컨트롤러가 고정 IP 주소를 사용하거나
- 라우터가 DHCP 예약으로 같은 IP 주소를 할당합니다

IP 주소와 로그인 정보를 요청하세요. 보통 가장 쉽고 빠른 방법입니다.


## 옵션 B: 라우터 확인

라우터에 접속하려면 일반적으로 `192.168.1.1` 같은 로컬 주소나 `fritz.box` 같은 이름, 그리고 라우터 로그인 정보가 필요합니다.

라우터 설정 페이지를 열고 연결된 기기를 찾으세요.

이 항목은 다음과 같은 이름일 수 있습니다.

- 네트워크
- 연결된 기기
- LAN
- DHCP 클라이언트

다음을 찾아보세요.

- 알 수 없는 유선 기기
- 컨트롤러일 수 있는 항목

IP 주소는 일반적으로 다음과 같습니다.
`192.168.x.x` 또는 `10.0.x.x`

![라우터의 연결된 기기 예시](../assets/setup-guide/ko/img_01_en_US.png)


## 옵션 C: 네트워크 스캔

기기에서 네트워크 스캐너 앱을 사용하세요.

네트워크를 스캔하고 다음을 찾아보세요.

- 알 수 없는 유선 기기
- 컨트롤러일 수 있는 항목

IP 주소는 일반적으로 다음과 같습니다.
`192.168.x.x` 또는 `10.0.x.x`


## IP 주소 테스트

찾은 IP 주소를 Safari에서 열어 보세요. 예:

`http://192.168.1.50`

액세스 컨트롤러의 로그인 페이지가 나타나면 올바른 주소를 찾은 것입니다.


## 2단계: 액세스 컨트롤러의 로그인 정보 찾기

일부 액세스 컨트롤러는 아직 기본 로그인 정보를 사용합니다. 일반적인 예는 사용자 이름 `abc`, 비밀번호 `654321`입니다.

다른 일반적인 기본 사용자 이름으로는 `user`, `admin`, `123`이 있습니다. `1234`, `user`, `password` 같은 일반적인 비밀번호나 그 변형과 함께 시도해 볼 수 있습니다.

시스템을 전문가가 설치했다면 기본 로그인 정보가 변경되었는지 설치자에게 문의하세요.


## 3단계: GateTap에 액세스 컨트롤러 추가

GateTap을 엽니다. 컨트롤러 추가 페이지가 자동으로 나타나지 않으면 "Controller" 탭으로 이동한 다음 오른쪽 상단 내비게이션 바의 "+" 버튼을 탭하세요.

표시되는 페이지에서 다음을 입력하세요.

- IP 주소
- 사용자 이름
- 비밀번호

액세스 컨트롤러의 웹 인터페이스와 동일한 로그인 정보를 사용하세요.


## 4단계: 연결 테스트

설정을 저장합니다. 앱이 자동으로 연결을 시도합니다.

연결을 만들 수 없으면 다음을 확인하세요.

- 기기가 액세스 컨트롤러와 같은 네트워크에 있는지
- IP 주소가 올바른지
- 액세스 컨트롤러에 전원이 공급되고 접근 가능한지


## 5단계: IP 주소 안정적으로 유지

나중에 문제가 생기지 않도록 컨트롤러는 항상 같은 IP 주소를 사용해야 합니다.

방법은 다음과 같습니다.

- 컨트롤러에 고정 IP 설정
- 라우터에서 DHCP 예약 생성


## 데모 모드

GateTap에는 데모 모드도 포함되어 있습니다. 앱 안에서 가상 액세스 컨트롤러를 시작할 수 있으며, 실제 출입 제어 시스템처럼 관리 인터페이스를 제공합니다. 그런 다음 표시된 IP 주소와 로그인 정보를 사용해 일반 컨트롤러처럼 추가할 수 있습니다.

현재 물리적인 액세스 컨트롤러가 없어도 GateTap의 기능을 탐색할 수 있는, 작동이 확인된 테스트 경로를 제공합니다.


## 보안

귀하의 데이터는 귀하의 장치에 유지됩니다.

선택적으로 앱 설정에서 Face ID 또는 Touch ID를 사용하여 GateTap을 보호할 수 있습니다.


