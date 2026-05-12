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

## O que é um controlador de acesso?

Um controlador de acesso é um dispositivo que gerencia a abertura de portas, portões, garagens ou cancelas — por exemplo, acionando uma fechadura elétrica ou o motor de um portão.
Normalmente ele recebe o sinal de abertura de:

- um sistema de interfone
- um teclado
- um chaveiro eletrônico ou cartão de acesso

Muitos sistemas modernos de controle de acesso estão conectados à rede local e podem ser operados por uma interface web no navegador. O GateTap se conecta diretamente a esse sistema para que você possa controlá-lo com facilidade pelo seu dispositivo.


## Antes de começar

Verifique se o dispositivo está conectado à mesma rede local que o controlador de acesso. Por exemplo, confirme se o iPhone está conectado ao Wi‑Fi de casa e não está usando dados móveis.

O GateTap funciona totalmente dentro da sua rede local e precisa de:

- Endereço IP do controlador
- Nome de usuário e senha


## Etapa 1: Encontre o endereço IP do controlador de acesso

Para conectar o GateTap, você precisa do endereço IP do controlador e das credenciais de login — veja a Etapa 2.

Escolha uma das opções abaixo:


## Opção A: pergunte ao seu instalador (recomendado)

Se o sistema foi instalado por um eletricista ou técnico, é provável que ele já tenha configurado tudo.

Em muitos casos:

- O controlador usa um endereço IP fixo
- Ou o roteador atribui sempre o mesmo IP por uma reserva DHCP

Peça o endereço IP e as informações de login. Normalmente esse é o jeito mais fácil e rápido.


## Opção B: verifique seu roteador

Para acessar o roteador, normalmente você precisa do endereço local dele, por exemplo `192.168.1.1` ou um nome como `fritz.box`, e das credenciais de login do roteador.

Abra a página de configuração do roteador e procure os dispositivos conectados.

Essa seção pode se chamar:

- Rede
- Dispositivos conectados
- LAN
- Clientes DHCP

Procure por:

- Dispositivos cabeados desconhecidos
- Entradas que possam representar seu controlador

O endereço IP normalmente se parece com:
`192.168.x.x` ou `10.0.x.x`

![Exemplo de dispositivos conectados no roteador](../assets/setup-guide/pt-BR/img_01_en_US.png)


## Opção C: verifique sua rede

Use um app de scanner de rede no seu dispositivo.

Escaneie sua rede e procure por:

- Dispositivos cabeados desconhecidos
- Entradas que possam representar seu controlador

O endereço IP normalmente se parece com:
`192.168.x.x` ou `10.0.x.x`


## Teste o endereço IP

Tente abrir no Safari o endereço IP encontrado, por exemplo:

`http://192.168.1.50`

Se a página de login do controlador de acesso aparecer, você encontrou o endereço correto.


## Etapa 2: Encontre as credenciais do controlador de acesso

Alguns controladores de acesso ainda usam credenciais de login padrão. Um exemplo comum é o nome de usuário `abc` com a senha `654321`.

Outros nomes de usuário padrão comuns incluem `user`, `admin` ou `123`. Você pode testá-los com senhas típicas como `1234`, `user` ou `password`, ou alguma variação.

Se o sistema foi instalado profissionalmente, pergunte ao instalador se as credenciais padrão foram alteradas.


## Etapa 3: Adicione o controlador de acesso no GateTap

Abra o GateTap. Se a página para adicionar um controlador não aparecer automaticamente, vá para a aba "Controller" e toque no botão "+" na barra de navegação no canto superior direito.

Na página exibida, insira:

- Endereço IP
- Nome de usuário
- Senha

Use as mesmas credenciais de login usadas na interface web do controlador de acesso.


## Etapa 4: Teste a conexão

Salve a configuração. O app tentará se conectar automaticamente.

Se não for possível estabelecer a conexão, verifique:

- Se o dispositivo está na mesma rede que o controlador de acesso
- Se o endereço IP está correto
- Se o controlador de acesso está ligado e acessível


## Etapa 5: Mantenha o endereço IP estável

Para evitar problemas depois, o controlador deve sempre usar o mesmo endereço IP.

Isso pode ser feito por meio de:

- Configuração de IP estático no controlador
- Criação de uma reserva DHCP no roteador


## Modo demo

O GateTap também inclui um modo demo. Você pode iniciar um controlador de acesso virtual dentro do app, que fornece a interface de administração como um sistema real de controle de acesso faria. Depois, você pode adicioná-lo como um controlador normal usando o endereço IP e as credenciais exibidos.

Isso oferece um caminho de teste conhecido e funcional para explorar os recursos do GateTap, mesmo que você não tenha um controlador de acesso físico no momento.


## Segurança

Seus dados permanecem no seu dispositivo.

Opcionalmente, você pode proteger o GateTap usando Face ID ou Touch ID nas configurações do aplicativo.


