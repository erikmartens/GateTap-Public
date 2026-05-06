<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.3
Language: en
-->

# Setup Guide

---

🌍 **This Document is available in other Languages:**  
🇺🇸 English | [🇩🇪 Deutsch](setup-guide.de.md) | [🇸🇦 العربية](setup-guide.ar.md) | [🇪🇸 Català](setup-guide.ca.md) | [🇨🇿 Čeština](setup-guide.cs.md) | [🇩🇰 Dansk](setup-guide.da.md) | [🇬🇷 Ελληνικά](setup-guide.el.md) | [🇪🇸 Español](setup-guide.es.md) | [🇲🇽 Español (México)](setup-guide.es-MX.md) | [🇫🇮 Suomi](setup-guide.fi.md) | [🇫🇷 Français](setup-guide.fr.md) | [🇮🇱 עברית](setup-guide.he.md) | [🇮🇳 हिन्दी](setup-guide.hi.md) | [🇭🇷 Hrvatski](setup-guide.hr.md) | [🇭🇺 Magyar](setup-guide.hu.md) | [🇮🇩 Bahasa Indonesia](setup-guide.id.md) | [🇮🇹 Italiano](setup-guide.it.md) | [🇯🇵 日本語](setup-guide.ja.md) | [🇰🇷 한국어](setup-guide.ko.md) | [🇲🇾 Bahasa Melayu](setup-guide.ms.md) | [🇳🇴 Norsk Bokmål](setup-guide.nb.md) | [🇳🇱 Nederlands](setup-guide.nl.md) | [🇵🇱 Polski](setup-guide.pl.md) | [🇧🇷 Português (Brasil)](setup-guide.pt-BR.md) | [🇵🇹 Português (Portugal)](setup-guide.pt-PT.md) | [🇷🇴 Română](setup-guide.ro.md) | [🇷🇺 Русский](setup-guide.ru.md) | [🇸🇰 Slovenčina](setup-guide.sk.md) | [🇸🇪 Svenska](setup-guide.sv.md) | [🇹🇭 ไทย](setup-guide.th.md) | [🇹🇷 Türkçe](setup-guide.tr.md) | [🇺🇦 Українська](setup-guide.uk.md) | [🇻🇳 Tiếng Việt](setup-guide.vi.md) | [🇨🇳 简体中文](setup-guide.zh-Hans.md) | [🇹🇼 繁體中文](setup-guide.zh-Hant.md)

---

Connect GateTap to your access controller

## Before you start

Make sure your iPhone is connected to the same local network as your access controller.

GateTap works entirely within your local network and needs:
• The controller’s IP address
• A username and password


## Step 1: Find controller address and credentials

To connect GateTap, you need the controller’s IP address and login credentials.

Choose one of the following options:


## Option A: Ask your installer (recommended)

If your system was installed by an electrician or technician, they likely already configured everything.

In many cases:
• The controller uses a fixed IP address
• Or the router assigns the same IP via reservation

Ask them for the IP address and login details. This is usually the easiest and fastest way.


## Option B: Check your router

Open your router’s configuration page and look for connected devices.

To access your router, you usually need its local address (e.g. `192.168.1.1` or a name like `fritz.box`) and the router’s login credentials.

This section may be called:
• Connected Devices
• LAN
• DHCP Clients

Look for:
• Unknown wired devices
• Entries that might represent your controller

The IP address will usually look like:
`192.168.x.x` or `10.0.x.x`

![Router connected devices example](../assets/setup-guide/en/img_01.png)


## Option C: Scan your network

Use a network scanner app on your iPhone or computer.

Scan your network and try opening discovered IP addresses in Safari, for example:

`http://192.168.1.50`

If the controller’s login page appears, you’ve found the correct address.

![Network scanner example](../assets/setup-guide/en/img_02.png)


## Step 2: Add the controller in GateTap

Open GateTap and enter:
• The IP address
• Your username
• Your password

Use the same credentials as for the controller’s web interface.


## Step 3: Test the connection

Save your configuration and try opening a door or gate.

If nothing happens, check:
• Your iPhone is on the same network
• The IP address is correct
• The controller is powered and reachable


## Step 4: Keep the IP address stable

To avoid issues later, the controller should always use the same IP address.

This can be done by:
• Setting a static IP on the controller
• Creating a DHCP reservation in your router


## Security

Your data stays on your device.

You can optionally protect GateTap using Face ID or Touch ID in the app settings.


