<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.3
Language: fr
-->

# Guide de configuration

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🌐 ar](setup-guide.ar.md) | [🌐 ca](setup-guide.ca.md) | [🌐 cs](setup-guide.cs.md) | [🌐 da](setup-guide.da.md) | [🌐 el](setup-guide.el.md) | [🌐 es](setup-guide.es.md) | [🌐 es-MX](setup-guide.es-MX.md) | [🌐 fi](setup-guide.fi.md) | 🌐 fr | [🌐 he](setup-guide.he.md) | [🌐 hi](setup-guide.hi.md) | [🌐 hr](setup-guide.hr.md) | [🌐 hu](setup-guide.hu.md) | [🌐 id](setup-guide.id.md) | [🌐 it](setup-guide.it.md) | [🌐 ja](setup-guide.ja.md) | [🌐 ko](setup-guide.ko.md) | [🌐 ms](setup-guide.ms.md) | [🌐 nb](setup-guide.nb.md) | [🌐 nl](setup-guide.nl.md) | [🌐 pl](setup-guide.pl.md) | [🌐 pt-BR](setup-guide.pt-BR.md) | [🌐 pt-PT](setup-guide.pt-PT.md) | [🌐 ro](setup-guide.ro.md) | [🌐 ru](setup-guide.ru.md) | [🌐 sk](setup-guide.sk.md) | [🌐 sv](setup-guide.sv.md) | [🌐 th](setup-guide.th.md) | [🌐 tr](setup-guide.tr.md) | [🌐 uk](setup-guide.uk.md) | [🌐 vi](setup-guide.vi.md) | [🇨🇳 中文](setup-guide.zh-Hans.md) | [🇨🇳 中文](setup-guide.zh-Hant.md)

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


