<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.3
Language: es
-->

# Guía de configuración

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🇸🇦 العربية](setup-guide.ar.md) | [🇪🇸 Català](setup-guide.ca.md) | [🇨🇿 Čeština](setup-guide.cs.md) | [🇩🇰 Dansk](setup-guide.da.md) | [🇬🇷 Ελληνικά](setup-guide.el.md) | 🇪🇸 Español | [🇲🇽 Español (México)](setup-guide.es-MX.md) | [🇫🇮 Suomi](setup-guide.fi.md) | [🇫🇷 Français](setup-guide.fr.md) | [🇮🇱 עברית](setup-guide.he.md) | [🇮🇳 हिन्दी](setup-guide.hi.md) | [🇭🇷 Hrvatski](setup-guide.hr.md) | [🇭🇺 Magyar](setup-guide.hu.md) | [🇮🇩 Bahasa Indonesia](setup-guide.id.md) | [🇮🇹 Italiano](setup-guide.it.md) | [🇯🇵 日本語](setup-guide.ja.md) | [🇰🇷 한국어](setup-guide.ko.md) | [🇲🇾 Bahasa Melayu](setup-guide.ms.md) | [🇳🇴 Norsk Bokmål](setup-guide.nb.md) | [🇳🇱 Nederlands](setup-guide.nl.md) | [🇵🇱 Polski](setup-guide.pl.md) | [🇧🇷 Português (Brasil)](setup-guide.pt-BR.md) | [🇵🇹 Português (Portugal)](setup-guide.pt-PT.md) | [🇷🇴 Română](setup-guide.ro.md) | [🇷🇺 Русский](setup-guide.ru.md) | [🇸🇰 Slovenčina](setup-guide.sk.md) | [🇸🇪 Svenska](setup-guide.sv.md) | [🇹🇭 ไทย](setup-guide.th.md) | [🇹🇷 Türkçe](setup-guide.tr.md) | [🇺🇦 Українська](setup-guide.uk.md) | [🇻🇳 Tiếng Việt](setup-guide.vi.md) | [🇨🇳 简体中文](setup-guide.zh-Hans.md) | [🇹🇼 繁體中文](setup-guide.zh-Hant.md)

---

Conecte GateTap a su controlador de acceso

## Antes de empezar

Asegúrese de que su iPhone esté conectado a la misma red local que su controlador de acceso.

GateTap funciona completamente dentro de su red local y necesita:
• La dirección IP del controlador
• Un nombre de usuario y contraseña


## Paso 1: busque la dirección y las credenciales del controlador

Para conectar GateTap, necesita la dirección IP del controlador y las credenciales de inicio de sesión.

Elija una de las siguientes opciones:


## Opción A: Consulte a su instalador (recomendado)

Si su sistema fue instalado por un electricista o técnico, probablemente ya hayan configurado todo.

En muchos casos:
• El controlador utiliza una dirección IP fija
• O el enrutador asigna la misma IP mediante reserva

Pídales la dirección IP y los datos de inicio de sesión. Esta suele ser la forma más fácil y rápida.


## Opción B: Verifique su enrutador

Abra la página de configuración de su enrutador y busque los dispositivos conectados.

Para acceder a su enrutador, normalmente necesita su dirección local (por ejemplo, `192.168.1.1` o un nombre como `fritz.box`) y las credenciales de inicio de sesión del enrutador.

Esta sección puede llamarse:
• Dispositivos conectados
• LAN
• Clientes DHCP

Busque:
• Dispositivos cableados desconocidos
• Entradas que podrían representar su controlador

La dirección IP normalmente se verá así:
`192.168.x.x` o `10.0.x.x`

![Ejemplo de dispositivos conectados al enrutador](../assets/setup-guide/es/img_01.png)


## Opción C: escanea tu red

Utilice una aplicación de escáner de red en su iPhone o computadora.

Escanee su red e intente abrir direcciones IP descubiertas en Safari, por ejemplo:

`http://192.168.1.50`

Si aparece la página de inicio de sesión del controlador, ha encontrado la dirección correcta.

![Ejemplo de escáner de red](../assets/setup-guide/es/img_02.png)


## Paso 2: agregue el controlador en GateTap

Abra GateTap e ingrese:
• La dirección IP
• Su nombre de usuario
• Tu contraseña

Utilice las mismas credenciales que para la interfaz web del controlador.


## Paso 3: prueba la conexión

Guarde su configuración e intente abrir una puerta o portón.

Si no sucede nada, verifique:
• Tu iPhone está en la misma red
• La dirección IP es correcta
• El controlador está encendido y accesible


## Paso 4: Mantenga estable la dirección IP

Para evitar problemas posteriores, el controlador siempre debe utilizar la misma dirección IP.

Esto se puede hacer mediante:
• Configuración de una IP estática en el controlador
• Crear una reserva DHCP en su enrutador


## Seguridad

Tus datos permanecen en tu dispositivo.

Opcionalmente, puedes proteger GateTap usando Face ID o Touch ID en la configuración de la aplicación.


