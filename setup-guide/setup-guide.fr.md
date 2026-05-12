<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.4
Language: fr
-->

# Guide de configuration

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🇸🇦 العربية](setup-guide.ar.md) | [🇪🇸 Català](setup-guide.ca.md) | [🇨🇿 Čeština](setup-guide.cs.md) | [🇩🇰 Dansk](setup-guide.da.md) | [🇬🇷 Ελληνικά](setup-guide.el.md) | [🇪🇸 Español](setup-guide.es.md) | [🇲🇽 Español (México)](setup-guide.es-MX.md) | [🇫🇮 Suomi](setup-guide.fi.md) | 🇫🇷 Français | [🇮🇱 עברית](setup-guide.he.md) | [🇮🇳 हिन्दी](setup-guide.hi.md) | [🇭🇷 Hrvatski](setup-guide.hr.md) | [🇭🇺 Magyar](setup-guide.hu.md) | [🇮🇩 Bahasa Indonesia](setup-guide.id.md) | [🇮🇹 Italiano](setup-guide.it.md) | [🇯🇵 日本語](setup-guide.ja.md) | [🇰🇷 한국어](setup-guide.ko.md) | [🇲🇾 Bahasa Melayu](setup-guide.ms.md) | [🇳🇴 Norsk Bokmål](setup-guide.nb.md) | [🇳🇱 Nederlands](setup-guide.nl.md) | [🇵🇱 Polski](setup-guide.pl.md) | [🇧🇷 Português (Brasil)](setup-guide.pt-BR.md) | [🇵🇹 Português (Portugal)](setup-guide.pt-PT.md) | [🇷🇴 Română](setup-guide.ro.md) | [🇷🇺 Русский](setup-guide.ru.md) | [🇸🇰 Slovenčina](setup-guide.sk.md) | [🇸🇪 Svenska](setup-guide.sv.md) | [🇹🇭 ไทย](setup-guide.th.md) | [🇹🇷 Türkçe](setup-guide.tr.md) | [🇺🇦 Українська](setup-guide.uk.md) | [🇻🇳 Tiếng Việt](setup-guide.vi.md) | [🇨🇳 简体中文](setup-guide.zh-Hans.md) | [🇹🇼 繁體中文](setup-guide.zh-Hant.md)

---

Connectez GateTap à votre contrôleur d'accès

## Qu’est-ce qu’un contrôleur d’accès ?

Un contrôleur d’accès est un appareil qui gère l’ouverture de portes, portails, garages ou barrières — par exemple en activant une gâche ou un moteur de portail.
Il reçoit généralement le signal d’ouverture depuis :

- un interphone
- un clavier
- un badge ou une carte d’accès

De nombreux systèmes modernes de contrôle d’accès sont connectés au réseau local et peuvent être utilisés via une interface web dans un navigateur. GateTap se connecte directement à votre système de contrôle d’accès afin que vous puissiez l’utiliser facilement depuis votre appareil.


## Avant de commencer

Assurez-vous que votre appareil est connecté au même réseau local que votre contrôleur d’accès. Par exemple, vérifiez que votre iPhone est connecté au Wi-Fi de votre domicile et non aux données mobiles.

GateTap fonctionne entièrement sur votre réseau local et a besoin de :

- L’adresse IP du contrôleur
- Un nom d’utilisateur et un mot de passe


## Étape 1 : Trouver l’adresse IP de votre contrôleur d’accès

Pour connecter GateTap, vous avez besoin de l’adresse IP du contrôleur et des identifiants de connexion — voir l’étape 2.

Choisissez l’une des options suivantes :


## Option A : Demandez à votre installateur (recommandé)

Si votre système a été installé par un électricien ou un technicien, il a probablement déjà tout configuré.

Dans de nombreux cas :

- Le contrôleur utilise une adresse IP fixe
- Ou le routeur lui attribue la même IP via une réservation DHCP

Demandez-lui l’adresse IP et les identifiants de connexion. C’est généralement la méthode la plus simple et la plus rapide.


## Option B : Vérifiez votre routeur

Pour accéder à votre routeur, vous avez généralement besoin de son adresse locale, par exemple `192.168.1.1` ou d’un nom comme `fritz.box`, ainsi que des identifiants du routeur.

Ouvrez la page de configuration de votre routeur et recherchez les appareils connectés.

Cette section peut s’appeler :

- Réseau
- Appareils connectés
- LAN
- Clients DHCP

Recherchez :

- Des appareils câblés inconnus
- Des entrées qui pourraient correspondre à votre contrôleur

L’adresse IP ressemble généralement à :
`192.168.x.x` ou `10.0.x.x`

![Exemple d’appareils connectés dans le routeur](../assets/setup-guide/fr/img_01_en_US.png)


## Option C : Analysez votre réseau

Utilisez une app de scan réseau sur votre appareil.

Analysez votre réseau et recherchez :

- Des appareils câblés inconnus
- Des entrées qui pourraient correspondre à votre contrôleur

L’adresse IP ressemble généralement à :
`192.168.x.x` ou `10.0.x.x`


## Tester l’adresse IP

Essayez d’ouvrir l’adresse IP trouvée dans Safari, par exemple :

`http://192.168.1.50`

Si la page de connexion du contrôleur d’accès apparaît, vous avez trouvé la bonne adresse.


## Étape 2 : Trouver les identifiants du contrôleur d’accès

Certains contrôleurs d’accès utilisent encore des identifiants par défaut. Un exemple courant est le nom d’utilisateur `abc` avec le mot de passe `654321`.

Les autres noms d’utilisateur par défaut courants sont `user`, `admin` ou `123`. Vous pouvez les essayer avec des mots de passe typiques comme `1234`, `user` ou `password`, ou une variante.

Si votre système a été installé par un professionnel, demandez à votre installateur si les identifiants par défaut ont été modifiés.


## Étape 3 : Ajouter le contrôleur d’accès dans GateTap

Ouvrez GateTap. Si la page d’ajout d’un contrôleur n’apparaît pas automatiquement, passez à l’onglet "Controller" et touchez le bouton "+" dans la barre de navigation en haut à droite.

Sur la page qui s’affiche, saisissez :

- L’adresse IP
- Votre nom d’utilisateur
- Votre mot de passe

Utilisez les mêmes identifiants que pour l’interface web du contrôleur d’accès.


## Étape 4 : Tester la connexion

Enregistrez votre configuration. L’app essaiera automatiquement de se connecter.

Si la connexion ne peut pas être établie, vérifiez :

- Que votre appareil est sur le même réseau que le contrôleur d’accès
- Que l’adresse IP est correcte
- Que le contrôleur d’accès est alimenté et joignable


## Étape 5 : Garder l’adresse IP stable

Pour éviter les problèmes plus tard, le contrôleur devrait toujours utiliser la même adresse IP.

Cela peut se faire en :

- Définissant une IP statique sur le contrôleur
- Créant une réservation DHCP dans votre routeur


## Mode démo

GateTap inclut également un mode démo. Vous pouvez démarrer un contrôleur d’accès virtuel depuis l’app, qui sert l’interface d’administration comme le ferait un système réel. Vous pouvez ensuite l’ajouter comme un contrôleur normal à l’aide de l’adresse IP et des identifiants affichés.

Cela vous donne un parcours de test connu et fonctionnel pour explorer les fonctionnalités de GateTap, même si vous n’avez pas actuellement de contrôleur d’accès physique.


## Sécurité

Vos données restent sur votre appareil.

Vous pouvez éventuellement protéger GateTap à l'aide de Face ID ou Touch ID dans les paramètres de l'application.


