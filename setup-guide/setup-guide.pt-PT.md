<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.4
Language: pt-PT
-->

# Guia de configuração

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🇸🇦 العربية](setup-guide.ar.md) | [🇪🇸 Català](setup-guide.ca.md) | [🇨🇿 Čeština](setup-guide.cs.md) | [🇩🇰 Dansk](setup-guide.da.md) | [🇬🇷 Ελληνικά](setup-guide.el.md) | [🇪🇸 Español](setup-guide.es.md) | [🇲🇽 Español (México)](setup-guide.es-MX.md) | [🇫🇮 Suomi](setup-guide.fi.md) | [🇫🇷 Français](setup-guide.fr.md) | [🇮🇱 עברית](setup-guide.he.md) | [🇮🇳 हिन्दी](setup-guide.hi.md) | [🇭🇷 Hrvatski](setup-guide.hr.md) | [🇭🇺 Magyar](setup-guide.hu.md) | [🇮🇩 Bahasa Indonesia](setup-guide.id.md) | [🇮🇹 Italiano](setup-guide.it.md) | [🇯🇵 日本語](setup-guide.ja.md) | [🇰🇷 한국어](setup-guide.ko.md) | [🇲🇾 Bahasa Melayu](setup-guide.ms.md) | [🇳🇴 Norsk Bokmål](setup-guide.nb.md) | [🇳🇱 Nederlands](setup-guide.nl.md) | [🇵🇱 Polski](setup-guide.pl.md) | [🇧🇷 Português (Brasil)](setup-guide.pt-BR.md) | 🇵🇹 Português (Portugal) | [🇷🇴 Română](setup-guide.ro.md) | [🇷🇺 Русский](setup-guide.ru.md) | [🇸🇰 Slovenčina](setup-guide.sk.md) | [🇸🇪 Svenska](setup-guide.sv.md) | [🇹🇭 ไทย](setup-guide.th.md) | [🇹🇷 Türkçe](setup-guide.tr.md) | [🇺🇦 Українська](setup-guide.uk.md) | [🇻🇳 Tiếng Việt](setup-guide.vi.md) | [🇨🇳 简体中文](setup-guide.zh-Hans.md) | [🇹🇼 繁體中文](setup-guide.zh-Hant.md)

---

Conecte o GateTap ao seu controlador de acesso

## Antes de começar

Certifique-se de que o dispositivo está ligado à mesma rede local que o controlador de acesso. Por exemplo, confirme que o iPhone está no Wi-Fi de casa e não numa ligação de dados móveis.

O GateTap funciona inteiramente dentro da sua rede local e precisa de:

- O endereço IP do controlador
- Um nome de utilizador e uma palavra-passe


## Etapa 1: Encontre o endereço IP do controlador de acesso

Para ligar o GateTap, precisa do endereço IP do controlador e das credenciais de início de sessão - veja a Etapa 2.

Escolha uma das seguintes opções:


## Opção A: pergunte ao seu instalador (recomendado)

Se o sistema foi instalado por um eletricista ou técnico, é provável que já tenha configurado tudo.

Em muitos casos:

- O controlador usa um endereço IP fixo
- Ou o router atribui o mesmo IP através de uma reserva DHCP

Peça o endereço IP e os dados de início de sessão. Normalmente é a forma mais fácil e rápida.


## Opção B: verifique o seu router

Abra a página de configuração do router e procure os dispositivos ligados.

Para aceder ao router, normalmente precisa do respetivo endereço local, por exemplo `192.168.1.1` ou um nome como `fritz.box`, e das credenciais do router.

Esta secção pode chamar-se:

- Rede
- Dispositivos ligados
- LAN
- Clientes DHCP

Procure:

- Dispositivos com fios desconhecidos
- Entradas que possam representar o seu controlador

O endereço IP normalmente tem este aspeto:
`192.168.x.x` ou `10.0.x.x`

![Exemplo de dispositivos ligados no router](../assets/setup-guide/pt-PT/img_01_en_US.png)


## Opção C: verifique a sua rede

Use uma aplicação de scanner de rede no seu dispositivo.

Faça a análise da rede e tente abrir os endereços IP encontrados no Safari, por exemplo:

`http://192.168.1.50`

Se aparecer a página de início de sessão do controlador de acesso, encontrou o endereço correto.

![Exemplo de aplicação de scanner de rede](../assets/setup-guide/pt-PT/img_02_en_US.png)


## Etapa 2: Encontre as credenciais do controlador de acesso

Alguns controladores ainda usam credenciais predefinidas. Um exemplo comum é o nome de utilizador `abc` com a palavra-passe `654321`.

Outros nomes de utilizador de fábrica comuns são `user`, `admin` ou `123`. Pode experimentá-los com palavras-passe típicas como `1234`, `user` ou `password`, ou alguma variação.

Se o sistema foi instalado profissionalmente, pergunte ao instalador se as credenciais predefinidas foram alteradas.


## Etapa 3: Adicione o controlador de acesso no GateTap

Abra o GateTap e introduza:

- O endereço IP
- O nome de utilizador
- A palavra-passe

Use as mesmas credenciais da interface web do controlador de acesso.


## Etapa 4: Teste a ligação

Guarde a configuração e tente abrir uma porta ou portão.

Se nada acontecer, verifique:

- Se o dispositivo está na mesma rede que o controlador de acesso
- Se o endereço IP está correto
- Se o controlador de acesso está ligado e acessível


## Etapa 5: Mantenha o endereço IP estável

Para evitar problemas mais tarde, o controlador deve usar sempre o mesmo endereço IP.

Isto pode ser feito através de:

- Definir um IP estático no controlador
- Criar uma reserva DHCP no router


## Modo demo

O GateTap também inclui um modo demo. Pode iniciar um servidor web demo local dentro da app e depois adicioná-lo como um controlador normal.

Isto dá-lhe um caminho de teste conhecido e funcional para verificar se o próprio GateTap está a funcionar corretamente, mesmo que neste momento não tenha acesso a um controlador de acesso físico.


## Segurança

Seus dados permanecem no seu dispositivo.

Opcionalmente, você pode proteger o GateTap usando Face ID ou Touch ID nas configurações do aplicativo.


