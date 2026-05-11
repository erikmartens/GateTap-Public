<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.4
Language: ja
-->

# セットアップガイド

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🇸🇦 العربية](setup-guide.ar.md) | [🇪🇸 Català](setup-guide.ca.md) | [🇨🇿 Čeština](setup-guide.cs.md) | [🇩🇰 Dansk](setup-guide.da.md) | [🇬🇷 Ελληνικά](setup-guide.el.md) | [🇪🇸 Español](setup-guide.es.md) | [🇲🇽 Español (México)](setup-guide.es-MX.md) | [🇫🇮 Suomi](setup-guide.fi.md) | [🇫🇷 Français](setup-guide.fr.md) | [🇮🇱 עברית](setup-guide.he.md) | [🇮🇳 हिन्दी](setup-guide.hi.md) | [🇭🇷 Hrvatski](setup-guide.hr.md) | [🇭🇺 Magyar](setup-guide.hu.md) | [🇮🇩 Bahasa Indonesia](setup-guide.id.md) | [🇮🇹 Italiano](setup-guide.it.md) | 🇯🇵 日本語 | [🇰🇷 한국어](setup-guide.ko.md) | [🇲🇾 Bahasa Melayu](setup-guide.ms.md) | [🇳🇴 Norsk Bokmål](setup-guide.nb.md) | [🇳🇱 Nederlands](setup-guide.nl.md) | [🇵🇱 Polski](setup-guide.pl.md) | [🇧🇷 Português (Brasil)](setup-guide.pt-BR.md) | [🇵🇹 Português (Portugal)](setup-guide.pt-PT.md) | [🇷🇴 Română](setup-guide.ro.md) | [🇷🇺 Русский](setup-guide.ru.md) | [🇸🇰 Slovenčina](setup-guide.sk.md) | [🇸🇪 Svenska](setup-guide.sv.md) | [🇹🇭 ไทย](setup-guide.th.md) | [🇹🇷 Türkçe](setup-guide.tr.md) | [🇺🇦 Українська](setup-guide.uk.md) | [🇻🇳 Tiếng Việt](setup-guide.vi.md) | [🇨🇳 简体中文](setup-guide.zh-Hans.md) | [🇹🇼 繁體中文](setup-guide.zh-Hant.md)

---

GateTap をアクセス コントローラーに接続します

## 始める前に

デバイスがアクセスコントローラーと同じローカルネットワークに接続されていることを確認してください。たとえば、iPhone がモバイルデータ通信ではなく自宅の Wi-Fi に接続されていることを確認します。

GateTap はローカルネットワーク内だけで動作し、次の情報が必要です:

- コントローラーの IP アドレス
- ユーザー名とパスワード


## ステップ 1: アクセスコントローラーの IP アドレスを見つける

GateTap を接続するには、コントローラーの IP アドレスとログイン情報が必要です。ステップ 2 を参照してください。

次のいずれかの方法を選んでください:


## オプション A: 設置業者に問い合わせる（推奨）

システムが電気工事業者や技術者によって設置された場合、必要な設定はすでに済んでいる可能性があります。

多くの場合:

- コントローラーは固定 IP アドレスを使用しています
- またはルーターが DHCP 予約で同じ IP を割り当てています

IP アドレスとログイン情報を尋ねてください。通常、これが最も簡単で早い方法です。


## オプション B: ルーターを確認する

ルーターの設定ページを開き、接続済みデバイスを探します。

ルーターにアクセスするには、通常 `192.168.1.1` などのローカルアドレス、または `fritz.box` のような名前と、ルーターのログイン情報が必要です。

この項目は次のような名前の場合があります:

- ネットワーク
- 接続済みデバイス
- LAN
- DHCP クライアント

次を探します:

- 不明な有線デバイス
- コントローラーと思われる項目

IP アドレスは通常、次のような形式です:
`192.168.x.x` または `10.0.x.x`

![ルーターの接続済みデバイスの例](../assets/setup-guide/ja/img_01_en_US.png)


## オプション C: ネットワークをスキャンする

デバイスでネットワークスキャナーアプリを使用します。

ネットワークをスキャンし、見つかった IP アドレスを Safari で開いてみます。例:

`http://192.168.1.50`

アクセスコントローラーのログインページが表示されたら、正しいアドレスが見つかっています。

![ネットワークスキャナーアプリの例](../assets/setup-guide/ja/img_02_en_US.png)


## ステップ 2: アクセスコントローラーのログイン情報を見つける

一部のコントローラーでは、まだデフォルトのログイン情報が使われています。よくある例は、ユーザー名 `abc`、パスワード `654321` です。

その他によく使われる出荷時のユーザー名には `user`、`admin`、`123` があります。`1234`、`user`、`password` などの一般的なパスワードやそのバリエーションと組み合わせて試すことができます。

専門業者がシステムを設置した場合は、デフォルトのログイン情報が変更されたかどうかを設置業者に確認してください。


## ステップ 3: GateTap にアクセスコントローラーを追加する

GateTap を開いて入力します:

- IP アドレス
- ユーザー名
- パスワード

アクセスコントローラーの Web インターフェイスと同じログイン情報を使用してください。


## ステップ 4: 接続をテストする

設定を保存し、ドアまたはゲートを開いてみます。

何も起こらない場合は、次を確認してください:

- デバイスがアクセスコントローラーと同じネットワーク上にある
- IP アドレスが正しい
- アクセスコントローラーに電源が入り、到達可能である


## ステップ 5: IP アドレスを安定させる

後で問題を避けるため、コントローラーは常に同じ IP アドレスを使用する必要があります。

これは次の方法で行えます:

- コントローラーに静的 IP を設定する
- ルーターで DHCP 予約を作成する


## デモモード

GateTap にはデモモードも含まれています。アプリ内からローカルのデモ Web サーバーを起動し、通常のコントローラーと同じように追加できます。

これにより、物理的なアクセスコントローラーを現在利用できない場合でも、GateTap 自体が正しく機能していることを確認できる、既知の動作するテスト手順が得られます。


## 安全

データはデバイス上に残ります。

オプションで、アプリ設定で Face ID または Touch ID を使用して GateTap を保護できます。


