<!--
Generated from GateTap app setup guide JSON.
Do not edit manually.
Version: 1.3
Language: ja
-->

# セットアップガイド

---

🌍 **This Document is available in other Languages:**  
[🇺🇸 English](setup-guide.en.md) | [🇩🇪 Deutsch](setup-guide.de.md) | [🌐 ar](setup-guide.ar.md) | [🌐 ca](setup-guide.ca.md) | [🌐 cs](setup-guide.cs.md) | [🌐 da](setup-guide.da.md) | [🌐 el](setup-guide.el.md) | [🌐 es](setup-guide.es.md) | [🌐 es-MX](setup-guide.es-MX.md) | [🌐 fi](setup-guide.fi.md) | [🌐 fr](setup-guide.fr.md) | [🌐 he](setup-guide.he.md) | [🌐 hi](setup-guide.hi.md) | [🌐 hr](setup-guide.hr.md) | [🌐 hu](setup-guide.hu.md) | [🌐 id](setup-guide.id.md) | [🌐 it](setup-guide.it.md) | 🌐 ja | [🌐 ko](setup-guide.ko.md) | [🌐 ms](setup-guide.ms.md) | [🌐 nb](setup-guide.nb.md) | [🌐 nl](setup-guide.nl.md) | [🌐 pl](setup-guide.pl.md) | [🌐 pt-BR](setup-guide.pt-BR.md) | [🌐 pt-PT](setup-guide.pt-PT.md) | [🌐 ro](setup-guide.ro.md) | [🌐 ru](setup-guide.ru.md) | [🌐 sk](setup-guide.sk.md) | [🌐 sv](setup-guide.sv.md) | [🌐 th](setup-guide.th.md) | [🌐 tr](setup-guide.tr.md) | [🌐 uk](setup-guide.uk.md) | [🌐 vi](setup-guide.vi.md) | [🇨🇳 中文](setup-guide.zh-Hans.md) | [🇨🇳 中文](setup-guide.zh-Hant.md)

---

GateTap をアクセス コントローラーに接続します

## 始める前に

iPhone がアクセス コントローラーと同じローカル ネットワークに接続されていることを確認してください。

GateTap は完全にローカル ネットワーク内で動作し、次のものが必要です。
• コントローラの IP アドレス
• ユーザー名とパスワード


## ステップ 1: コントローラーのアドレスと資格情報を見つける

GateTap に接続するには、コントローラーの IP アドレスとログイン資格情報が必要です。

次のオプションのいずれかを選択します。


## オプション A: 設置者に問い合わせる (推奨)

システムが電気技師または技術者によって設置された場合は、すでにすべての設定が行われている可能性があります。

多くの場合:
• コントローラーは固定 IP アドレスを使用します。
• または、ルーターが予約によって同じ IP を割り当てます。

IP アドレスとログインの詳細を尋ねます。通常、これが最も簡単で早い方法です。


## オプション B: ルーターを確認する

ルーターの設定ページを開いて、接続されているデバイスを探します。

ルーターにアクセスするには、通常、そのローカル アドレス (例: `192.168.1.1` または `fritz.box` のような名前) とルーターのログイン資格情報が必要です。

このセクションは次のように呼ばれます。
• 接続されたデバイス
・LAN
• DHCP クライアント

探してください:
• 不明な有線デバイス
• コントローラーを表す可能性のあるエントリ

通常、IP アドレスは次のようになります。
`192.168.x.x`または`10.0.x.x`

![ルーター接続機器例](../assets/setup-guide/ja/img_01.png)


## オプション C: ネットワークをスキャンする

iPhone またはコンピュータでネットワーク スキャナ アプリを使用します。

ネットワークをスキャンし、検出された IP アドレスを Safari で開いてみます。次に例を示します。

`http://192.168.1.50`

コントローラのログイン ページが表示されたら、正しいアドレスが見つかったことになります。

![ネットワークスキャナー例](../assets/setup-guide/ja/img_02.png)


## ステップ 2: GateTap にコントローラーを追加する

GateTap を開いて次のように入力します。
• IP アドレス
• あなたのユーザー名
• あなたのパスワード

コントローラーの Web インターフェイスと同じ認証情報を使用します。


## ステップ 3: 接続をテストする

設定を保存し、ドアまたはゲートを開いてみてください。

何も起こらない場合は、次のことを確認してください。
• iPhone が同じネットワーク上にある
• IP アドレスが正しい
• コントローラに電力が供給されており、到達可能である


## ステップ 4: IP アドレスを安定した状態に保つ

後で問題が発生するのを避けるために、コントローラーは常に同じ IP アドレスを使用する必要があります。

これは次の方法で実行できます。
• コントローラに静的 IP を設定する
• ルーターでの DHCP 予約の作成


## 安全

データはデバイス上に残ります。

オプションで、アプリ設定で Face ID または Touch ID を使用して GateTap を保護できます。


