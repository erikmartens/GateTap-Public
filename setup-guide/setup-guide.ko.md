<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.3
Language: ko
-->

# 설정 가이드

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🌐 ar](setup-guide.ar.md) | [🌐 ca](setup-guide.ca.md) | [🌐 cs](setup-guide.cs.md) | [🌐 da](setup-guide.da.md) | [🌐 el](setup-guide.el.md) | [🌐 es](setup-guide.es.md) | [🌐 es-MX](setup-guide.es-MX.md) | [🌐 fi](setup-guide.fi.md) | [🌐 fr](setup-guide.fr.md) | [🌐 he](setup-guide.he.md) | [🌐 hi](setup-guide.hi.md) | [🌐 hr](setup-guide.hr.md) | [🌐 hu](setup-guide.hu.md) | [🌐 id](setup-guide.id.md) | [🌐 it](setup-guide.it.md) | [🌐 ja](setup-guide.ja.md) | 🌐 ko | [🌐 ms](setup-guide.ms.md) | [🌐 nb](setup-guide.nb.md) | [🌐 nl](setup-guide.nl.md) | [🌐 pl](setup-guide.pl.md) | [🌐 pt-BR](setup-guide.pt-BR.md) | [🌐 pt-PT](setup-guide.pt-PT.md) | [🌐 ro](setup-guide.ro.md) | [🌐 ru](setup-guide.ru.md) | [🌐 sk](setup-guide.sk.md) | [🌐 sv](setup-guide.sv.md) | [🌐 th](setup-guide.th.md) | [🌐 tr](setup-guide.tr.md) | [🌐 uk](setup-guide.uk.md) | [🌐 vi](setup-guide.vi.md) | [🇨🇳 中文](setup-guide.zh-Hans.md) | [🇨🇳 中文](setup-guide.zh-Hant.md)

---

GateTap을 액세스 컨트롤러에 연결하세요

## 시작하기 전에

iPhone이 액세스 컨트롤러와 동일한 로컬 네트워크에 연결되어 있는지 확인하세요.

GateTap은 로컬 네트워크 내에서 완전히 작동하며 다음이 필요합니다.
• 컨트롤러의 IP 주소
• 사용자 이름과 비밀번호


## 1단계: 컨트롤러 주소 및 자격 증명 찾기

GateTap을 연결하려면 컨트롤러의 IP 주소와 로그인 자격 증명이 필요합니다.

다음 옵션 중 하나를 선택하십시오.


## 옵션 A: 설치자에게 문의(권장)

전기 기술자나 기술자가 시스템을 설치한 경우 이미 모든 것을 구성했을 가능성이 높습니다.

많은 경우:
• 컨트롤러는 고정 IP 주소를 사용합니다.
• 또는 라우터가 예약을 통해 동일한 IP를 할당합니다.

IP 주소와 로그인 세부 정보를 문의하세요. 일반적으로 이 방법이 가장 쉽고 빠른 방법입니다.


## 옵션 B: 라우터 확인

라우터의 구성 페이지를 열고 연결된 장치를 찾으십시오.

라우터에 액세스하려면 일반적으로 로컬 주소(예: `192.168.1.1` 또는 `fritz.box`와 같은 이름)와 라우터의 로그인 자격 증명이 필요합니다.

이 섹션은 다음과 같이 불릴 수 있습니다.
• 연결된 장치
• LAN
• DHCP 클라이언트

다음을 찾으세요:
• 알 수 없는 유선 장치
• 컨트롤러를 나타낼 수 있는 항목

IP 주소는 일반적으로 다음과 같습니다.
`192.168.x.x` 또는 `10.0.x.x`

![라우터에 연결된 기기 예시](../assets/setup-guide/ko/img_01.png)


## 옵션 C: 네트워크 스캔

iPhone 또는 컴퓨터에서 네트워크 스캐너 앱을 사용하세요.

네트워크를 스캔하고 Safari에서 검색된 IP 주소를 열어보세요. 예:

`http://192.168.1.50`

컨트롤러의 로그인 페이지가 나타나면 올바른 주소를 찾은 것입니다.

![네트워크 스캐너 예시](../assets/setup-guide/ko/img_02.png)


## 2단계: GateTap에 컨트롤러 추가

GateTap을 열고 다음을 입력하세요.
• IP 주소
• 귀하의 사용자 이름
• 귀하의 비밀번호

컨트롤러의 웹 인터페이스와 동일한 자격 증명을 사용하십시오.


## 3단계: 연결 테스트

구성을 저장하고 문이나 게이트를 열어보세요.

아무 일도 일어나지 않으면 다음을 확인하세요.
• iPhone이 동일한 네트워크에 있습니다.
• IP 주소가 정확합니다.
• 컨트롤러에 전원이 공급되고 연결 가능합니다.


## 4단계: IP 주소를 안정적으로 유지

나중에 문제가 발생하지 않도록 컨트롤러는 항상 동일한 IP 주소를 사용해야 합니다.

이는 다음을 통해 수행할 수 있습니다.
• 컨트롤러에 고정 IP 설정
• 라우터에서 DHCP 예약 생성


## 보안

귀하의 데이터는 귀하의 장치에 유지됩니다.

선택적으로 앱 설정에서 Face ID 또는 Touch ID를 사용하여 GateTap을 보호할 수 있습니다.


