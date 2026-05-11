<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.4
Language: pt-BR
-->

# Guia de configuração

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🇸🇦 العربية](setup-guide.ar.md) | [🇪🇸 Català](setup-guide.ca.md) | [🇨🇿 Čeština](setup-guide.cs.md) | [🇩🇰 Dansk](setup-guide.da.md) | [🇬🇷 Ελληνικά](setup-guide.el.md) | [🇪🇸 Español](setup-guide.es.md) | [🇲🇽 Español (México)](setup-guide.es-MX.md) | [🇫🇮 Suomi](setup-guide.fi.md) | [🇫🇷 Français](setup-guide.fr.md) | [🇮🇱 עברית](setup-guide.he.md) | [🇮🇳 हिन्दी](setup-guide.hi.md) | [🇭🇷 Hrvatski](setup-guide.hr.md) | [🇭🇺 Magyar](setup-guide.hu.md) | [🇮🇩 Bahasa Indonesia](setup-guide.id.md) | [🇮🇹 Italiano](setup-guide.it.md) | [🇯🇵 日本語](setup-guide.ja.md) | [🇰🇷 한국어](setup-guide.ko.md) | [🇲🇾 Bahasa Melayu](setup-guide.ms.md) | [🇳🇴 Norsk Bokmål](setup-guide.nb.md) | [🇳🇱 Nederlands](setup-guide.nl.md) | [🇵🇱 Polski](setup-guide.pl.md) | 🇧🇷 Português (Brasil) | [🇵🇹 Português (Portugal)](setup-guide.pt-PT.md) | [🇷🇴 Română](setup-guide.ro.md) | [🇷🇺 Русский](setup-guide.ru.md) | [🇸🇰 Slovenčina](setup-guide.sk.md) | [🇸🇪 Svenska](setup-guide.sv.md) | [🇹🇭 ไทย](setup-guide.th.md) | [🇹🇷 Türkçe](setup-guide.tr.md) | [🇺🇦 Українська](setup-guide.uk.md) | [🇻🇳 Tiếng Việt](setup-guide.vi.md) | [🇨🇳 简体中文](setup-guide.zh-Hans.md) | [🇹🇼 繁體中文](setup-guide.zh-Hant.md)

---

Conecte o GateTap ao seu controlador de acesso

## Antes de começar

Verifique se o dispositivo está conectado à mesma rede local que o controlador de acesso. Por exemplo, confirme que o iPhone está no Wi-Fi de casa, e não usando dados móveis.

O GateTap funciona inteiramente dentro da sua rede local e precisa de:
• O endereço IP do controlador
• Um nome de usuário e uma senha


## Etapa 1: Encontre o endereço IP do controlador de acesso

Para conectar o GateTap, você precisa do endereço IP do controlador e das credenciais de login - veja a Etapa 2.

Escolha uma das opções abaixo:


## Opção A: pergunte ao seu instalador (recomendado)

Se o sistema foi instalado por um eletricista ou técnico, é provável que ele já tenha configurado tudo.

Em muitos casos:
• O controlador usa um endereço IP fixo
• Ou o roteador atribui o mesmo IP por reserva DHCP

Peça o endereço IP e os dados de login. Normalmente é a forma mais fácil e rápida.


## Opção B: verifique seu roteador

Abra a página de configuração do roteador e procure os dispositivos conectados.

Para acessar o roteador, você normalmente precisa do endereço local dele, por exemplo `192.168.1.1` ou um nome como `fritz.box`, e das credenciais do roteador.

Essa seção pode se chamar:
• Rede
• Dispositivos conectados
• LAN
• Clientes DHCP

Procure por:
• Dispositivos cabeados desconhecidos
• Entradas que possam representar seu controlador

O endereço IP normalmente se parece com:
`192.168.x.x` ou `10.0.x.x`

![Exemplo de dispositivos conectados no roteador](../assets/setup-guide/pt-BR/img_01_en_US.png)


## Opção C: verifique sua rede

Use um app de scanner de rede no seu dispositivo.

Escaneie a rede e tente abrir os endereços IP encontrados no Safari, por exemplo:

`http://192.168.1.50`

Se a página de login do controlador de acesso aparecer, você encontrou o endereço correto.

![Exemplo de app de scanner de rede](../assets/setup-guide/pt-BR/img_02_en_US.png)


## Etapa 2: Encontre as credenciais do controlador de acesso

Alguns controladores ainda usam credenciais padrão. Um exemplo comum é o nome de usuário `abc` com a senha `654321`.

Outros nomes de usuário de fábrica comuns são `user`, `admin` ou `123`. Você pode testá-los com senhas típicas como `1234`, `user` ou `password`, ou alguma variação.

Se o sistema foi instalado profissionalmente, pergunte ao instalador se as credenciais padrão foram alteradas.


## Etapa 3: Adicione o controlador de acesso no GateTap

Abra o GateTap e insira:
• O endereço IP
• Seu nome de usuário
• Sua senha

Use as mesmas credenciais da interface web do controlador de acesso.


## Etapa 4: Teste a conexão

Salve a configuração e tente abrir uma porta ou portão.

Se nada acontecer, verifique:
• Se o dispositivo está na mesma rede que o controlador de acesso
• Se o endereço IP está correto
• Se o controlador de acesso está ligado e acessível


## Etapa 5: Mantenha o endereço IP estável

Para evitar problemas depois, o controlador deve sempre usar o mesmo endereço IP.

Isso pode ser feito por:
• Configurar um IP estático no controlador
• Criar uma reserva DHCP no roteador


## Modo demo

O GateTap também inclui um modo demo. Você pode iniciar um servidor web demo local dentro do app e depois adicioná-lo como um controlador normal.

Isso oferece um caminho de teste conhecido e funcional para verificar se o próprio GateTap está funcionando corretamente, mesmo que você não tenha acesso a um controlador de acesso físico no momento.


## Segurança

Seus dados permanecem no seu dispositivo.

Opcionalmente, você pode proteger o GateTap usando Face ID ou Touch ID nas configurações do aplicativo.


