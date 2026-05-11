<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.4
Language: zh-Hant
-->

# 設定指南

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🇸🇦 العربية](setup-guide.ar.md) | [🇪🇸 Català](setup-guide.ca.md) | [🇨🇿 Čeština](setup-guide.cs.md) | [🇩🇰 Dansk](setup-guide.da.md) | [🇬🇷 Ελληνικά](setup-guide.el.md) | [🇪🇸 Español](setup-guide.es.md) | [🇲🇽 Español (México)](setup-guide.es-MX.md) | [🇫🇮 Suomi](setup-guide.fi.md) | [🇫🇷 Français](setup-guide.fr.md) | [🇮🇱 עברית](setup-guide.he.md) | [🇮🇳 हिन्दी](setup-guide.hi.md) | [🇭🇷 Hrvatski](setup-guide.hr.md) | [🇭🇺 Magyar](setup-guide.hu.md) | [🇮🇩 Bahasa Indonesia](setup-guide.id.md) | [🇮🇹 Italiano](setup-guide.it.md) | [🇯🇵 日本語](setup-guide.ja.md) | [🇰🇷 한국어](setup-guide.ko.md) | [🇲🇾 Bahasa Melayu](setup-guide.ms.md) | [🇳🇴 Norsk Bokmål](setup-guide.nb.md) | [🇳🇱 Nederlands](setup-guide.nl.md) | [🇵🇱 Polski](setup-guide.pl.md) | [🇧🇷 Português (Brasil)](setup-guide.pt-BR.md) | [🇵🇹 Português (Portugal)](setup-guide.pt-PT.md) | [🇷🇴 Română](setup-guide.ro.md) | [🇷🇺 Русский](setup-guide.ru.md) | [🇸🇰 Slovenčina](setup-guide.sk.md) | [🇸🇪 Svenska](setup-guide.sv.md) | [🇹🇭 ไทย](setup-guide.th.md) | [🇹🇷 Türkçe](setup-guide.tr.md) | [🇺🇦 Українська](setup-guide.uk.md) | [🇻🇳 Tiếng Việt](setup-guide.vi.md) | [🇨🇳 简体中文](setup-guide.zh-Hans.md) | 🇹🇼 繁體中文

---

將 GateTap 連接到你的門禁控制器

## 開始之前

請確認你的裝置與門禁控制器連接到同一個本機網路。例如，確認 iPhone 連接的是家中的 Wi-Fi，而不是行動數據連線。

GateTap 完全在你的本機網路內運作，並需要：
• 控制器的 IP 位址
• 使用者名稱和密碼


## 步驟 1：找到門禁控制器的 IP 位址

若要連接 GateTap，你需要控制器的 IP 位址和登入憑證 - 請參閱步驟 2。

請選擇以下其中一種方式：


## 選項 A：詢問安裝人員（建議）

如果你的系統由電工或技術人員安裝，他們很可能已經完成所有設定。

在許多情況下：
• 控制器使用固定 IP 位址
• 或路由器透過 DHCP 保留指派相同 IP

向他們詢問 IP 位址和登入資料。這通常是最簡單、最快的方式。


## 選項 B：檢查路由器

開啟路由器的設定頁面，尋找已連線的裝置。

若要存取路由器，通常需要其本機位址，例如 `192.168.1.1` 或 `fritz.box` 這類名稱，以及路由器的登入憑證。

此區段可能稱為：
• 網路
• 已連線裝置
• LAN
• DHCP 用戶端

請尋找：
• 不明的有線裝置
• 可能代表你的控制器的項目

IP 位址通常類似於：
`192.168.x.x` 或 `10.0.x.x`

![路由器已連線裝置範例](../assets/setup-guide/zh-Hant/img_01_zh_Hant.png)


## 選項 C：掃描網路

在裝置上使用網路掃描 app。

掃描你的網路，並嘗試在 Safari 中開啟找到的 IP 位址，例如：

`http://192.168.1.50`

如果出現門禁控制器的登入頁面，就表示你找到了正確位址。

![網路掃描 app 範例](../assets/setup-guide/zh-Hant/img_02_zh_Hant.png)


## 步驟 2：找到門禁控制器的登入憑證

有些控制器仍使用預設登入憑證。常見範例是使用者名稱 `abc`，密碼 `654321`。

其他常見的出廠使用者名稱包括 `user`、`admin` 或 `123`。你可以搭配常見密碼如 `1234`、`user` 或 `password`，或其變體一起嘗試。

如果你的系統是由專業人員安裝，請詢問安裝人員預設憑證是否已變更。


## 步驟 3：在 GateTap 中新增門禁控制器

開啟 GateTap 並輸入：
• IP 位址
• 使用者名稱
• 密碼

請使用與門禁控制器網頁介面相同的登入憑證。


## 步驟 4：測試連線

儲存設定，並嘗試開啟門或閘門。

如果沒有反應，請檢查：
• 你的裝置與門禁控制器位於同一網路
• IP 位址正確
• 門禁控制器已供電且可連線


## 步驟 5：保持 IP 位址穩定

為避免日後發生問題，控制器應始終使用相同的 IP 位址。

可透過以下方式完成：
• 在控制器上設定靜態 IP
• 在路由器中建立 DHCP 保留


## 示範模式

GateTap 也包含示範模式。你可以從 app 內啟動本機示範 Web 伺服器，然後像一般控制器一樣新增它。

這提供一個已知可運作的測試路徑，用來確認 GateTap 本身是否正常運作，即使你目前無法使用實體門禁控制器。


## 安全

你的資料會保留在你的裝置上。

你也可以在 App 設定中使用 Face ID 或 Touch ID 保護 GateTap。


