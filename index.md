# プライバシーポリシー

**アプリ名**: どこでもガード
**最終更新日**: 2026年8月15日

本ポリシーは、本アプリにおける個人情報・利用者情報の取り扱いについて説明するものです。本アプリをご利用いただくことで、本ポリシーの内容に同意いただいたものとします。

## 1. 本アプリが取得する情報

本アプリは、外部のサーバーに利用者の個人情報や位置情報を送信することはありません。位置情報・お気に入り・PINコードなど、本アプリの機能そのものに関わる情報は、利用者の端末内にのみ保存されます(クラッシュ発生時の診断データを除く。詳細は下記)。

- **位置情報(実際のGPS位置・設定した仮の位置)**: 本アプリの機能を提供するために端末内でのみ処理され、外部に送信されることはありません。
- **お気に入りのスポット・ルート情報**: 端末内のデータベースにのみ保存されます。外部への送信・バックアップは行いません。
- **PINコード(ロック機能を有効にした場合)**: 元のPINコードそのものは保存せず、復元不可能な形式(ハッシュ化)に変換した上で端末内にのみ保存されます。
- **クラッシュ診断データ(アプリが異常終了した場合)**: Firebase Crashlyticsを通じて、エラー発生箇所(スタックトレース)・端末の機種名/OSバージョン・アプリのバージョンといった診断情報が開発者に送信されます。氏名・メールアドレス・位置情報など利用者を特定できる情報は含まれません。詳細は「4. 外部サービスの利用」をご覧ください。

本アプリは、氏名・メールアドレス・電話番号など、利用者を直接特定できる情報の入力を求めることはありません。

## 2. 取得する端末の権限とその目的

| 権限 | 目的 |
|---|---|
| 位置情報(おおよその位置・詳細な位置) | 現在地の表示、仮の位置情報を設定する機能の提供 |
| 通知の送信 | ルート移動中の到着・出発通知、動作状況の通知 |
| バックグラウンドでの位置情報利用・フォアグラウンドサービス | アプリを閉じても仮の位置情報を継続して反映させるため |
| インターネットへのアクセス、ネットワーク状態の取得 | 地図(国土地理院のタイル地図、鉄道路線図)の表示に必要な地図データを取得するため |
| バッテリー最適化の除外 | バックグラウンドでの位置情報の継続提供が中断されないようにするため |

インターネット通信は地図タイルデータの取得のみに使用され、この通信に利用者個人を特定できる情報は含まれません。

## 3. 第三者への情報提供

本アプリは、利用者の情報を第三者(広告事業者・解析事業者を含む)に提供・共有・販売することはありません。本アプリには広告SDK・行動分析(アクセス解析)SDKは組み込まれていません。なお、アプリの安定性向上を目的としたクラッシュレポートSDK(Firebase Crashlytics)のみ組み込んでおり、その送信内容は「4. 外部サービスの利用」に記載の通りです。

## 4. 外部サービスの利用

本アプリは地図の表示のために以下の外部データソースへ通信を行います。これらは地図タイル画像・データの取得のみを目的としたものであり、利用者個人を特定できる情報を送信するものではありません。

- 国土地理院(GSI)提供の地図タイル
- OpenRailwayMap提供の鉄道路線タイル

また、有料機能の購入にはGoogle Playの課金システム(Google Play Billing Library)を利用します。決済情報(クレジットカード番号等)は本アプリを経由せずGoogle Playが直接処理し、本アプリ・開発者側で取得・保存することはありません。詳細はGoogleのプライバシーポリシーをご確認ください。

さらに、アプリが予期せず終了した場合の原因調査・品質改善を目的として、Firebase Crashlytics(Google提供)を利用しています。アプリの異常終了時に、エラー発生箇所(スタックトレース)・端末の機種名/OSバージョン・アプリのバージョン・アプリ固有のインストールID(利用者個人やGoogleアカウントとは紐付かない匿名の識別子)が自動的にGoogleのサーバーに送信されます。位置情報や氏名・メールアドレスなど利用者を特定できる情報が含まれることはありません。詳細はFirebaseのプライバシーとセキュリティに関するポリシーをご確認ください。

## 5. 情報の保存期間・削除

端末内に保存された情報(お気に入り・設定・PINハッシュ等)は、利用者が本アプリ内の機能で削除するか、本アプリをアンインストールすることでいつでも消去できます。本アプリの開発者側でこれらの情報を保持することはありません。

## 6. お子様のプライバシーについて

本アプリは子供を対象としたものではなく、子供から意図的に情報を収集することはありません。

## 7. 本ポリシーの変更

法令の改正や本アプリの機能追加(例: 将来的な有料機能の追加)に伴い、本ポリシーの内容を変更することがあります。重要な変更がある場合は、本ページの「最終更新日」を更新してお知らせします。

## 8. お問い合わせ先

本ポリシーに関するお問い合わせは、以下までご連絡ください。

dokodemoguard.support@gmail.com

---

# Privacy Policy (English)

**App name**: どこでもガード (DokodemoGuard)
**Last updated**: August 15, 2026

This policy explains how this app handles personal information and user data. By using this app, you agree to the contents of this policy.

## 1. Information this app collects

This app does not send your personal information or location data to any external server. Information tied to the app's core features (location, favorites, PIN code) is stored only on your device (with one exception — diagnostic data sent on a crash; see below).

- **Location (real GPS position and any simulated position you set)**: processed on-device only to provide the app's features, and never transmitted externally.
- **Favorite spots and routes**: stored only in an on-device database. Never sent externally or backed up.
- **PIN code (if the lock feature is enabled)**: the raw PIN is never stored; only an irreversible hashed form is stored on-device.
- **Crash diagnostic data (if the app crashes)**: via Firebase Crashlytics, diagnostic information — the stack trace where the error occurred, device model/OS version, and app version — is sent to the developer. This never includes identifying information such as your name, email address, or location. See "4. External services used" for details.

This app never asks you to enter directly identifying information such as your name, email address, or phone number.

## 2. Device permissions and their purpose

| Permission | Purpose |
|---|---|
| Location (approximate / precise) | Showing your current location; providing the simulated-location feature |
| Notifications | Arrival/departure notifications while a route is running; status notifications |
| Background location use / foreground service | Keeping the simulated location active even after you close the app |
| Internet access, network state | Fetching map data (GSI base map tiles, railway overlay) needed to render the map |
| Battery optimization exemption | Preventing background simulated-location delivery from being interrupted |

Internet access is used only to fetch map tile data; this traffic never includes any information that could identify you personally.

## 3. Third-party sharing

This app does not provide, share, or sell your information to any third party, including advertising or analytics providers. No advertising SDK or behavioral-analytics SDK is embedded in this app. It does embed a crash-reporting SDK (Firebase Crashlytics) for app-stability purposes only — see "4. External services used" for what it sends.

## 4. External services used

To render the map, this app communicates with the following external data sources. This traffic is limited to fetching map tile images/data and does not include any personally identifiable information.

- Map tiles provided by the Geospatial Information Authority of Japan (GSI)
- Railway overlay tiles provided by OpenRailwayMap

Purchases of paid features are processed through Google Play's billing system (Google Play Billing Library). Payment details (such as credit card numbers) are handled directly by Google Play and never pass through or are stored by this app or its developer. See Google's own privacy policy for details.

This app also uses Firebase Crashlytics (provided by Google) to investigate the cause of unexpected crashes and improve app quality. When the app crashes, diagnostic information — the stack trace where the error occurred, device model/OS version, app version, and an app-specific install ID (an anonymous identifier not tied to you personally or to any Google account) — is automatically sent to Google's servers. This never includes identifying information such as your location, name, or email address. See Firebase's privacy and security policies for details.

## 5. Data retention and deletion

Information stored on your device (favorites, settings, PIN hash, etc.) can be deleted at any time either through this app's own features or by uninstalling the app. The developer never retains this information.

## 6. Children's privacy

This app is not directed at children, and does not knowingly collect information from children.

## 7. Changes to this policy

This policy may be updated to reflect legal changes or new app features (for example, future paid features). Material changes will be reflected in the "Last updated" date above.

## 8. Contact

For questions about this policy, please contact:

dokodemoguard.support@gmail.com
