<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.3
Language: fr
-->

# Guide de configuration

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🇸🇦 العربية](setup-guide.ar.md) | [🇪🇸 Català](setup-guide.ca.md) | [🇨🇿 Čeština](setup-guide.cs.md) | [🇩🇰 Dansk](setup-guide.da.md) | [🇬🇷 Ελληνικά](setup-guide.el.md) | [🇪🇸 Español](setup-guide.es.md) | [🇲🇽 Español (México)](setup-guide.es-MX.md) | [🇫🇮 Suomi](setup-guide.fi.md) | 🇫🇷 Français | [🇮🇱 עברית](setup-guide.he.md) | [🇮🇳 हिन्दी](setup-guide.hi.md) | [🇭🇷 Hrvatski](setup-guide.hr.md) | [🇭🇺 Magyar](setup-guide.hu.md) | [🇮🇩 Bahasa Indonesia](setup-guide.id.md) | [🇮🇹 Italiano](setup-guide.it.md) | [🇯🇵 日本語](setup-guide.ja.md) | [🇰🇷 한국어](setup-guide.ko.md) | [🇲🇾 Bahasa Melayu](setup-guide.ms.md) | [🇳🇴 Norsk Bokmål](setup-guide.nb.md) | [🇳🇱 Nederlands](setup-guide.nl.md) | [🇵🇱 Polski](setup-guide.pl.md) | [🇧🇷 Português (Brasil)](setup-guide.pt-BR.md) | [🇵🇹 Português (Portugal)](setup-guide.pt-PT.md) | [🇷🇴 Română](setup-guide.ro.md) | [🇷🇺 Русский](setup-guide.ru.md) | [🇸🇰 Slovenčina](setup-guide.sk.md) | [🇸🇪 Svenska](setup-guide.sv.md) | [🇹🇭 ไทย](setup-guide.th.md) | [🇹🇷 Türkçe](setup-guide.tr.md) | [🇺🇦 Українська](setup-guide.uk.md) | [🇻🇳 Tiếng Việt](setup-guide.vi.md) | [🇨🇳 简体中文](setup-guide.zh-Hans.md) | [🇹🇼 繁體中文](setup-guide.zh-Hant.md)

---

Connectez GateTap à votre contrôleur d'accès

## Avant de commencer

Assurez-vous que votre iPhone est connecté au même réseau local que votre contrôleur d'accès.

GateTap fonctionne entièrement au sein de votre réseau local et a besoin :
• L'adresse IP du contrôleur
• Un nom d'utilisateur et un mot de passe


## Étape 1 : Rechercher l'adresse et les informations d'identification du contrôleur

Pour connecter GateTap, vous avez besoin de l’adresse IP et des informations de connexion du contrôleur.

Choisissez l'une des options suivantes :


## Option A : Demandez à votre installateur (recommandé)

Si votre système a été installé par un électricien ou un technicien, il est probable qu'il ait déjà tout configuré.

Dans de nombreux cas :
• Le contrôleur utilise une adresse IP fixe
• Soit le routeur attribue la même IP via réservation

Demandez-leur l’adresse IP et les informations de connexion. C’est généralement le moyen le plus simple et le plus rapide.


## Option B : Vérifiez votre routeur

Ouvrez la page de configuration de votre routeur et recherchez les appareils connectés.

Pour accéder à votre routeur, vous avez généralement besoin de son adresse locale (par exemple « `192.168.1.1` » ou d'un nom comme « `fritz.box` ») et des informations de connexion du routeur.

Cette section peut s'appeler :
• Appareils connectés
• Réseau local
• Clients DHCP

Recherchez :
• Appareils filaires inconnus
• Entrées pouvant représenter votre contrôleur

L'adresse IP ressemblera généralement à :
`192.168.x.x` ou `10.0.x.x`

![Exemple d'appareils connectés à un routeur](../assets/setup-guide/fr/img_01.png)


## Option C : analysez votre réseau

Utilisez une application de scanner réseau sur votre iPhone ou votre ordinateur.

Analysez votre réseau et essayez d'ouvrir les adresses IP découvertes dans Safari, par exemple :

`http://192.168.1.50`

Si la page de connexion du contrôleur apparaît, vous avez trouvé la bonne adresse.

![Exemple de scanner réseau](../assets/setup-guide/fr/img_02.png)


## Étape 2 : Ajoutez le contrôleur dans GateTap

Ouvrez GateTap et entrez :
• L'adresse IP
• Votre nom d'utilisateur
• Votre mot de passe

Utilisez les mêmes informations d’identification que pour l’interface Web du contrôleur.


## Étape 3 : Testez la connexion

Enregistrez votre configuration et essayez d'ouvrir une porte ou un portail.

Si rien ne se passe, vérifiez :
• Votre iPhone est sur le même réseau
• L'adresse IP est correcte
• Le contrôleur est alimenté et accessible


## Étape 4 : Maintenir la stabilité de l'adresse IP

Pour éviter des problèmes ultérieurs, le contrôleur doit toujours utiliser la même adresse IP.

Cela peut être fait par :
• Définition d'une adresse IP statique sur le contrôleur
• Création d'une réservation DHCP sur votre routeur


## Sécurité

Vos données restent sur votre appareil.

Vous pouvez éventuellement protéger GateTap à l'aide de Face ID ou Touch ID dans les paramètres de l'application.


