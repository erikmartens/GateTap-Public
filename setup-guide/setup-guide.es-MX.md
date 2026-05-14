<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.4
Language: es-MX
-->

# Guía de configuración

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🇸🇦 العربية](setup-guide.ar.md) | [🇪🇸 Català](setup-guide.ca.md) | [🇨🇿 Čeština](setup-guide.cs.md) | [🇩🇰 Dansk](setup-guide.da.md) | [🇬🇷 Ελληνικά](setup-guide.el.md) | [🇪🇸 Español](setup-guide.es.md) | 🇲🇽 Español (México) | [🇫🇮 Suomi](setup-guide.fi.md) | [🇫🇷 Français](setup-guide.fr.md) | [🇮🇱 עברית](setup-guide.he.md) | [🇮🇳 हिन्दी](setup-guide.hi.md) | [🇭🇷 Hrvatski](setup-guide.hr.md) | [🇭🇺 Magyar](setup-guide.hu.md) | [🇮🇩 Bahasa Indonesia](setup-guide.id.md) | [🇮🇹 Italiano](setup-guide.it.md) | [🇯🇵 日本語](setup-guide.ja.md) | [🇰🇷 한국어](setup-guide.ko.md) | [🇲🇾 Bahasa Melayu](setup-guide.ms.md) | [🇳🇴 Norsk Bokmål](setup-guide.nb.md) | [🇳🇱 Nederlands](setup-guide.nl.md) | [🇵🇱 Polski](setup-guide.pl.md) | [🇧🇷 Português (Brasil)](setup-guide.pt-BR.md) | [🇵🇹 Português (Portugal)](setup-guide.pt-PT.md) | [🇷🇴 Română](setup-guide.ro.md) | [🇷🇺 Русский](setup-guide.ru.md) | [🇸🇰 Slovenčina](setup-guide.sk.md) | [🇸🇪 Svenska](setup-guide.sv.md) | [🇹🇭 ไทย](setup-guide.th.md) | [🇹🇷 Türkçe](setup-guide.tr.md) | [🇺🇦 Українська](setup-guide.uk.md) | [🇻🇳 Tiếng Việt](setup-guide.vi.md) | [🇨🇳 简体中文](setup-guide.zh-Hans.md) | [🇹🇼 繁體中文](setup-guide.zh-Hant.md)

---

Conecte GateTap a su controlador de acceso

## ¿Qué es un controlador de acceso?

Un controlador de acceso es un dispositivo que gestiona la apertura de puertas, portones, garajes o barreras — por ejemplo activando un timbre eléctrico o el motor de una puerta.
Normalmente recibe la señal de apertura de:

- un sistema de intercomunicación
- un teclado
- un llavero electrónico o una tarjeta de acceso

Muchos sistemas modernos de control de acceso están conectados a la red local y pueden manejarse mediante una interfaz web en un navegador. GateTap se conecta directamente a tu sistema de control de acceso para que puedas operarlo cómodamente desde tu dispositivo.


## Antes de empezar

Asegúrate de que tu dispositivo esté conectado a la misma red local que tu controlador de acceso. Por ejemplo, comprueba que tu iPhone esté conectado a la Wi-Fi de casa y no esté usando datos móviles.

GateTap funciona completamente dentro de tu red local y necesita:

- La dirección IP del controlador
- Un nombre de usuario y una contraseña


## Paso 1: busca la dirección IP de tu controlador de acceso

Para conectar GateTap, necesitas la dirección IP del controlador y las credenciales de inicio de sesión — consulta el paso 2.

Elige una de las siguientes opciones:


## Opción A: pregunta a tu instalador (recomendado)

Si tu sistema fue instalado por un electricista o técnico, es probable que ya haya configurado todo.

En muchos casos:

- El controlador usa una dirección IP fija
- O el router le asigna la misma IP mediante una reserva DHCP

Pídele la dirección IP y los datos de inicio de sesión. Normalmente es la forma más fácil y rápida.


## Opción B: revisa tu router

Para acceder al router, normalmente necesitas su dirección local, por ejemplo `192.168.1.1` o un nombre como `fritz.box`, y las credenciales del router.

Abre la página de configuración de tu router y busca los dispositivos conectados.

Esta sección puede llamarse:

- Red
- Dispositivos conectados
- LAN
- Clientes DHCP

Busca:

- Dispositivos cableados desconocidos
- Entradas que puedan representar tu controlador

La dirección IP normalmente tendrá este aspecto:
`192.168.x.x` o `10.0.x.x`

![Ejemplo de dispositivos conectados en el router](../assets/setup-guide/es-MX/img_01_es-MX.png)


## Opción C: escanea tu red

Usa una app de escaneo de red en tu dispositivo.

Escanea tu red y busca:

- Dispositivos cableados desconocidos
- Entradas que puedan representar tu controlador

La dirección IP normalmente tendrá este aspecto:
`192.168.x.x` o `10.0.x.x`


## Prueba la dirección IP

Intenta abrir la dirección IP encontrada en Safari, por ejemplo:

`http://192.168.1.50`

Si aparece la página de inicio de sesión del controlador de acceso, encontraste la dirección correcta.


## Paso 2: busca las credenciales del controlador de acceso

Algunos controladores de acceso todavía usan credenciales predeterminadas. Un ejemplo común es el usuario `abc` con la contraseña `654321`.

Otros nombres de usuario predeterminados comunes son `user`, `admin` o `123`. Puedes probarlos con contraseñas típicas como `1234`, `user` o `password`, o alguna variación.

Si tu sistema se instaló profesionalmente, pregunta a tu instalador si se cambiaron las credenciales predeterminadas.


## Paso 3: añade el controlador de acceso en GateTap

Abre GateTap. Si la página para añadir un controlador no aparece automáticamente, cambia a la pestaña "Controller" y toca el botón "+" en la barra de navegación de la esquina superior derecha.

En la página que aparece, introduce:

- La dirección IP
- Tu nombre de usuario
- Tu contraseña

Usa las mismas credenciales que en la interfaz web del controlador de acceso.


## Paso 4: prueba la conexión

Guarda la configuración. La app intentará conectarse automáticamente.

Si no se puede establecer la conexión, comprueba:

- Que tu dispositivo esté en la misma red que el controlador de acceso
- Que la dirección IP sea correcta
- Que el controlador de acceso tenga alimentación y sea accesible


## Paso 5: mantén estable la dirección IP

Para evitar problemas más adelante, el controlador siempre debería usar la misma dirección IP.

Esto se puede hacer así:

- Configurando una IP estática en el controlador
- Creando una reserva DHCP en el router


## Modo demo

GateTap también incluye un modo demo. Puedes iniciar un controlador de acceso virtual desde la app, que ofrece la interfaz de administración como lo haría un sistema real. Luego puedes añadirlo como un controlador normal usando la dirección IP y las credenciales mostradas.

Esto te da una ruta de prueba conocida y funcional para explorar las funciones de GateTap, incluso si ahora no tienes un controlador de acceso físico.


## Seguridad

Tus datos permanecen en tu dispositivo.

Opcionalmente, puedes proteger GateTap usando Face ID o Touch ID en la configuración de la aplicación.


