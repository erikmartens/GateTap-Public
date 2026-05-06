<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.3
Language: es-MX
-->

# Guía de configuración

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🌐 ar](setup-guide.ar.md) | [🌐 ca](setup-guide.ca.md) | [🌐 cs](setup-guide.cs.md) | [🌐 da](setup-guide.da.md) | [🌐 el](setup-guide.el.md) | [🌐 es](setup-guide.es.md) | 🌐 es-MX | [🌐 fi](setup-guide.fi.md) | [🌐 fr](setup-guide.fr.md) | [🌐 he](setup-guide.he.md) | [🌐 hi](setup-guide.hi.md) | [🌐 hr](setup-guide.hr.md) | [🌐 hu](setup-guide.hu.md) | [🌐 id](setup-guide.id.md) | [🌐 it](setup-guide.it.md) | [🌐 ja](setup-guide.ja.md) | [🌐 ko](setup-guide.ko.md) | [🌐 ms](setup-guide.ms.md) | [🌐 nb](setup-guide.nb.md) | [🌐 nl](setup-guide.nl.md) | [🌐 pl](setup-guide.pl.md) | [🌐 pt-BR](setup-guide.pt-BR.md) | [🌐 pt-PT](setup-guide.pt-PT.md) | [🌐 ro](setup-guide.ro.md) | [🌐 ru](setup-guide.ru.md) | [🌐 sk](setup-guide.sk.md) | [🌐 sv](setup-guide.sv.md) | [🌐 th](setup-guide.th.md) | [🌐 tr](setup-guide.tr.md) | [🌐 uk](setup-guide.uk.md) | [🌐 vi](setup-guide.vi.md) | [🇨🇳 中文](setup-guide.zh-Hans.md) | [🇨🇳 中文](setup-guide.zh-Hant.md)

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

![Ejemplo de dispositivos conectados al enrutador](../assets/setup-guide/es-MX/img_01.png)


## Opción C: escanea tu red

Utilice una aplicación de escáner de red en su iPhone o computadora.

Escanee su red e intente abrir direcciones IP descubiertas en Safari, por ejemplo:

`http://192.168.1.50`

Si aparece la página de inicio de sesión del controlador, ha encontrado la dirección correcta.

![Ejemplo de escáner de red](../assets/setup-guide/es-MX/img_02.png)


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


