<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.3
Language: pt-PT
-->

# Guia de configuração

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🇸🇦 العربية](setup-guide.ar.md) | [🇪🇸 Català](setup-guide.ca.md) | [🇨🇿 Čeština](setup-guide.cs.md) | [🇩🇰 Dansk](setup-guide.da.md) | [🇬🇷 Ελληνικά](setup-guide.el.md) | [🇪🇸 Español](setup-guide.es.md) | [🇲🇽 Español (México)](setup-guide.es-MX.md) | [🇫🇮 Suomi](setup-guide.fi.md) | [🇫🇷 Français](setup-guide.fr.md) | [🇮🇱 עברית](setup-guide.he.md) | [🇮🇳 हिन्दी](setup-guide.hi.md) | [🇭🇷 Hrvatski](setup-guide.hr.md) | [🇭🇺 Magyar](setup-guide.hu.md) | [🇮🇩 Bahasa Indonesia](setup-guide.id.md) | [🇮🇹 Italiano](setup-guide.it.md) | [🇯🇵 日本語](setup-guide.ja.md) | [🇰🇷 한국어](setup-guide.ko.md) | [🇲🇾 Bahasa Melayu](setup-guide.ms.md) | [🇳🇴 Norsk Bokmål](setup-guide.nb.md) | [🇳🇱 Nederlands](setup-guide.nl.md) | [🇵🇱 Polski](setup-guide.pl.md) | [🇧🇷 Português (Brasil)](setup-guide.pt-BR.md) | 🇵🇹 Português (Portugal) | [🇷🇴 Română](setup-guide.ro.md) | [🇷🇺 Русский](setup-guide.ru.md) | [🇸🇰 Slovenčina](setup-guide.sk.md) | [🇸🇪 Svenska](setup-guide.sv.md) | [🇹🇭 ไทย](setup-guide.th.md) | [🇹🇷 Türkçe](setup-guide.tr.md) | [🇺🇦 Українська](setup-guide.uk.md) | [🇻🇳 Tiếng Việt](setup-guide.vi.md) | [🇨🇳 简体中文](setup-guide.zh-Hans.md) | [🇹🇼 繁體中文](setup-guide.zh-Hant.md)

---

Conecte o GateTap ao seu controlador de acesso

## Antes de começar

Certifique-se de que seu iPhone esteja conectado à mesma rede local que seu controlador de acesso.

GateTap funciona inteiramente dentro de sua rede local e precisa:
• O endereço IP do controlador
• Um nome de usuário e senha


## Etapa 1: Encontre o endereço e as credenciais do controlador

Para conectar o GateTap, você precisa do endereço IP e das credenciais de login do controlador.

Escolha uma das seguintes opções:


## Opção A: pergunte ao seu instalador (recomendado)

Se o seu sistema foi instalado por um eletricista ou técnico, provavelmente ele já configurou tudo.

Em muitos casos:
• O controlador usa um endereço IP fixo
• Ou o roteador atribui o mesmo IP via reserva

Peça-lhes o endereço IP e os detalhes de login. Geralmente essa é a maneira mais fácil e rápida.


## Opção B: verifique seu roteador

Abra a página de configuração do seu roteador e procure os dispositivos conectados.

Para acessar seu roteador, você geralmente precisa do endereço local (por exemplo, `192.168.1.1` ou um nome como `fritz.box`) e das credenciais de login do roteador.

Esta seção pode ser chamada:
• Dispositivos conectados
• LAN
• Clientes DHCP

Procure:
• Dispositivos com fio desconhecidos
• Entradas que podem representar seu controlador

O endereço IP geralmente será semelhante a:
`192.168.x.x` ou `10.0.x.x`

![Exemplo de dispositivos conectados ao roteador](../assets/setup-guide/pt-PT/img_01.png)


## Opção C: verifique sua rede

Use um aplicativo de scanner de rede no seu iPhone ou computador.

Faça uma varredura em sua rede e tente abrir endereços IP descobertos no Safari, por exemplo:

`http://192.168.1.50`

Se a página de login do controlador aparecer, você encontrou o endereço correto.

![Exemplo de scanner de rede](../assets/setup-guide/pt-PT/img_02.png)


## Etapa 2: adicione o controlador no GateTap

Abra o GateTap e digite:
• O endereço IP
• Seu nome de usuário
• Sua senha

Use as mesmas credenciais da interface web do controlador.


## Etapa 3: teste a conexão

Salve sua configuração e tente abrir uma porta ou portão.

Se nada acontecer, verifique:
• Seu iPhone está na mesma rede
• O endereço IP está correto
• O controlador está ligado e acessível


## Etapa 4: mantenha o endereço IP estável

Para evitar problemas posteriores, o controlador deve usar sempre o mesmo endereço IP.

Isso pode ser feito por:
• Configurando um IP estático no controlador
• Criando uma reserva DHCP em seu roteador


## Segurança

Seus dados permanecem no seu dispositivo.

Opcionalmente, você pode proteger o GateTap usando Face ID ou Touch ID nas configurações do aplicativo.


