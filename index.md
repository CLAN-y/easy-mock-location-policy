<img width="1920" height="3226" alt="image" src="https://github.com/user-attachments/assets/3ddda568-c33a-4262-807b-b2a08d146629" /><img width="1920" height="3226" alt="image" src="https://github.com/user-attachments/assets/43d34800-d960-450e-b5f3-db554dda840d" /># プライバシーポリシー

**アプリ名**: どこでもガード
**最終更新日**: 2026年10月3日

本ポリシーは、本アプリにおける個人情報・利用者情報の取り扱いについて説明するものです。本アプリをご利用いただくことで、本ポリシーの内容に同意いただいたものとします。

## 1. 本アプリが取得する情報

本アプリは、原則として外部のサーバーに利用者の個人情報や位置情報を送信しません。例外は、(1)クラッシュ発生時の診断データ、(2)有料の「自動ルート生成」機能を利用した際に経路計算のために送信される地点の座標、(3)地図の「検索」機能を利用した際に場所を探すために送信される検索語、の3つのみです(いずれも詳細は下記)。位置情報・お気に入り・PINコードなど、本アプリの機能そのものに関わる情報は、利用者の端末内に保存されます(端末の標準バックアップについては下記「お気に入りのスポット・ルート情報、設定」参照)。

- **位置情報(実際のGPS位置・設定した仮の位置)**: 本アプリの機能を提供するために端末内で処理され、端末内にのみ保存されます。実際のGPS位置が外部に送信されることはありません。ただし、有料の「自動ルート生成」機能を利用した場合に限り、利用者が経路上の地点として指定した座標が経路計算のために外部サービスへ送信されます(下記「4. 外部サービスの利用」参照)。
- **お気に入りのスポット・ルート情報、設定**: 端末内に保存されます。Android標準のバックアップ機能が有効な場合は、機種変更や再インストール時に復元できるよう、利用者ご自身のGoogleアカウントのバックアップ(Googleが提供するAndroid標準機能)に含まれます(PINコードのハッシュ値、無料お試しの利用状況、自動ルートのクレジット残高を含みます)。開発者のサーバーに送信されることはなく、開発者がその内容を閲覧することもできません。
- **地図の検索履歴**: 「検索」機能で見つけた場所と入力した検索語の履歴(最大10件)は、端末内にのみ保存されます。上記のバックアップの対象外としており、外部に送信されることはありません。
- **PINコード(ロック機能を有効にした場合)**: 元のPINコードそのものは保存せず、復元不可能な形式(ハッシュ化)に変換した上で端末内にのみ保存されます。
- **クラッシュ診断データ(アプリが異常終了した場合)**: Firebase Crashlyticsを通じて、エラー発生箇所(スタックトレース)・端末の機種名/OSバージョン・アプリのバージョンといった診断情報が開発者に送信されます。氏名・メールアドレス・位置情報など利用者を特定できる情報は含まれません。詳細は「4. 外部サービスの利用」をご覧ください。

本アプリは、氏名・メールアドレス・電話番号など、利用者を直接特定できる情報の入力を求めることはありません。

## 2. 取得する端末の権限とその目的

| 権限 | 目的 |
|---|---|
| 位置情報(おおよその位置・詳細な位置) | 現在地の表示、仮の位置情報を設定する機能の提供 |
| 通知の送信 | ルート移動中の到着・出発通知、動作状況の通知 |
| バックグラウンドでの位置情報利用・フォアグラウンドサービス | アプリを閉じても仮の位置情報を継続して反映させるため |
| インターネットへのアクセス、ネットワーク状態の取得 | 地図(国土地理院のタイル地図、鉄道路線図)の表示に必要な地図データの取得、「自動ルート生成」機能での経路検索、および地図の「検索」機能での場所の検索のため |
| バッテリー最適化の除外 | バックグラウンドでの位置情報の継続提供が中断されないようにするため |

インターネット通信は地図データの取得、「自動ルート生成」機能での経路検索、および地図の「検索」機能での場所の検索にのみ使用されます。これらの通信に、氏名・メールアドレスなど利用者個人を直接特定できる情報が含まれることはありません。

## 3. 第三者への情報提供

本アプリは、利用者の情報を広告事業者や行動分析(アクセス解析)事業者に提供・共有・販売することはありません。本アプリには広告SDK・行動分析SDKは組み込まれていません。第三者への情報の送信は、次の目的に限られます — (1)アプリの安定性向上を目的としたクラッシュレポート(Firebase Crashlytics)、(2)有料の「自動ルート生成」機能における経路計算(Google Routes API、NAVITIME 経路検索 API)、(3)地図の「検索」機能における場所の検索(Android標準の住所検索機能、Google提供)。いずれも送信内容は「4. 外部サービスの利用」に記載の通りで、利用者を特定できる情報は含まれません。

## 4. 外部サービスの利用

本アプリは地図の表示のために以下の外部データソースへ通信を行います。これらは地図タイル画像・データの取得のみを目的としたものであり、利用者個人を特定できる情報を送信するものではありません。

- 国土地理院(GSI)提供の地図タイル
- OpenRailwayMap提供の鉄道路線タイル

また、有料の「自動ルート生成」機能をご利用の場合に限り、出発地・目的地・経由地として指定された地点の緯度経度、移動手段の種別、および(公共交通機関の場合)検索時刻が、経路を計算するために以下の外部サービスへ送信されます。これらの地点は利用者が地図上で指定する仮の経路上の地点であり、氏名・メールアドレス・端末の実際のGPS位置・広告IDなど利用者を特定できる情報が併せて送信されることはありません。

- Google Routes API(Google提供) — 徒歩・自動車の経路計算に使用
- NAVITIME 経路検索 API(株式会社ナビタイムジャパン提供、RapidAPI 経由) — 公共交通機関の経路計算に使用

送信された座標の取り扱いについては、各社のプライバシーポリシーをご確認ください。本アプリの開発者はこれらの座標を保存するためのサーバーを保有しておらず、経路計算の結果は端末内にのみ保存されます。

地図の「検索」機能をご利用の場合は、利用者が入力した住所・駅名・建物名などの検索語が、場所の緯度経度を調べるために、Android標準の住所検索機能(Geocoder、Google提供)を通じてGoogleのサーバーへ送信されます。端末の実際のGPS位置・氏名・メールアドレスなど利用者を特定できる情報が本アプリから併せて送信されることはありません。送信された検索語の取り扱いについては、Googleのプライバシーポリシーをご確認ください。

有料機能の購入にはGoogle Playの課金システム(Google Play Billing Library)を利用します。決済情報(クレジットカード番号等)は本アプリを経由せずGoogle Playが直接処理し、本アプリ・開発者側で取得・保存することはありません。詳細はGoogleのプライバシーポリシーをご確認ください。

さらに、アプリが予期せず終了した場合の原因調査・品質改善を目的として、Firebase Crashlytics(Google提供)を利用しています。アプリの異常終了時に、エラー発生箇所(スタックトレース)・端末の機種名/OSバージョン・アプリのバージョン・アプリ固有のインストールID(利用者個人やGoogleアカウントとは紐付かない匿名の識別子)が自動的にGoogleのサーバーに送信されます。位置情報や氏名・メールアドレスなど利用者を特定できる情報が含まれることはありません。詳細はFirebaseのプライバシーとセキュリティに関するポリシーをご確認ください。

## 5. 情報の保存期間・削除

端末内に保存された情報(お気に入り・設定・PINハッシュ・検索履歴等)は、利用者が本アプリ内の機能で削除するか、本アプリをアンインストールすることでいつでも消去できます。Googleアカウントのバックアップに含まれる情報は、端末の「設定」またはGoogleアカウントのバックアップ管理画面から削除できます。本アプリの開発者側でこれらの情報を保持することはありません。

## 6. お子様のプライバシーについて

本アプリは子供を対象としたものではなく、子供から意図的に情報を収集することはありません。

## 7. 本ポリシーの変更

法令の改正や本アプリの機能追加(例: 将来的な有料機能の追加)に伴い、本ポリシーの内容を変更することがあります。重要な変更がある場合は、本ページの「最終更新日」を更新してお知らせします。

## 8. お問い合わせ先

本ポリシーに関するお問い合わせは、以下までご連絡ください。

dokodemoguard.support@gmail.com

---

# Privacy Policy (English)

**App name**: Anyware Guard (どこでもガード)
**Last updated**: October 3, 2026

This policy explains how this app handles personal information and user data. By using this app, you agree to the contents of this policy.

## 1. Information this app collects

As a rule, this app does not send your personal information or location data to any external server. There are only three exceptions: (1) diagnostic data sent when the app crashes, (2) the coordinates of the points you specify when using the paid "automatic route generation" feature, which are sent to calculate a route, and (3) the words you type when using the map "Search" feature, which are sent to find the place. All are described below. Information tied to the app's core features (location, favorites, PIN code) is stored on your device (see "Favorite spots and routes, settings" below regarding Android's standard backup).

- **Location (real GPS position and any simulated position you set)**: processed on-device to provide the app's features and stored only on your device. Your real GPS position is never transmitted externally. However, when you use the paid "automatic route generation" feature, the coordinates of the points you specify along the route are sent to external services to calculate the route (see "4. External services used").
- **Favorite spots and routes, settings**: stored on your device. If Android's standard backup is turned on, they are included in your own Google account backup (a standard Android feature provided by Google) so they can be restored after a device change or reinstall — this includes the PIN hash, free-trial usage, and auto-route credit balance. They are never sent to the developer's servers, and the developer cannot view them.
- **Map search history**: the places found with the "Search" feature and the words you typed (up to 10 entries) are stored only on your device. They are excluded from the backup above and are never sent externally.
- **PIN code (if the lock feature is enabled)**: the raw PIN is never stored; only an irreversible hashed form is stored on-device.
- **Crash diagnostic data (if the app crashes)**: via Firebase Crashlytics, diagnostic information — the stack trace where the error occurred, device model/OS version, and app version — is sent to the developer. This never includes identifying information such as your name, email address, or location. See "4. External services used" for details.

This app never asks you to enter directly identifying information such as your name, email address, or phone number.

## 2. Device permissions and their purpose

| Permission | Purpose |
|---|---|
| Location (approximate / precise) | Showing your current location; providing the simulated-location feature |
| Notifications | Arrival/departure notifications while a route is running; status notifications |
| Background location use / foreground service | Keeping the simulated location active even after you close the app |
| Internet access, network state | Fetching the map data needed to render the map (GSI base map tiles, railway overlay), searching for routes in the "automatic route generation" feature, and finding places with the map "Search" feature |
| Battery optimization exemption | Preventing background simulated-location delivery from being interrupted |

Internet access is used only to fetch map data, to search for routes in the "automatic route generation" feature, and to find places with the map "Search" feature; this traffic never includes directly identifying information such as your name or email address.

## 3. Third-party sharing

This app does not provide, share, or sell your information to advertising or behavioral-analytics providers. No advertising or analytics SDK is embedded in this app. Data is transmitted to third parties only for the following purposes: (1) crash reporting to improve app stability (Firebase Crashlytics), (2) route calculation in the paid "automatic route generation" feature (Google Routes API, NAVITIME route search API), and (3) place lookup in the map "Search" feature (Android's standard geocoding service, provided by Google). In all cases the transmitted data contains nothing that identifies you personally — see "4. External services used" for details.

## 4. External services used

To render the map, this app communicates with the following external data sources. This traffic is limited to fetching map tile images/data and does not include any personally identifiable information.

- Map tiles provided by the Geospatial Information Authority of Japan (GSI)
- Railway overlay tiles provided by OpenRailwayMap

In addition, only when you use the paid "automatic route generation" feature, the latitude/longitude of the points specified as origin, destination, and waypoints, the selected travel mode, and (for public transit) the search time are sent to the following external services to calculate a route. These points are simulated route points that you choose on the map; no identifying information such as your name, email address, real device GPS position, or advertising ID is sent with them.

- Google Routes API (provided by Google) — used to calculate walking and driving routes
- NAVITIME route search API (provided by NAVITIME JAPAN Co., Ltd., via RapidAPI) — used to calculate public transit routes

Please refer to each provider's privacy policy for how the sent coordinates are handled. The developer of this app operates no server to store these coordinates, and the route calculation results are stored only on your device.

When you use the map "Search" feature, the search words you type (such as an address, station name, or building name) are sent to Google's servers through Android's standard geocoding service (Geocoder, provided by Google) to look up the place's latitude/longitude. This app does not send your real device GPS position, name, email address, or any other identifying information with them. See Google's privacy policy for how the search words are handled.

Purchases of paid features are processed through Google Play's billing system (Google Play Billing Library). Payment details (such as credit card numbers) are handled directly by Google Play and never pass through or are stored by this app or its developer. See Google's own privacy policy for details.

This app also uses Firebase Crashlytics (provided by Google) to investigate the cause of unexpected crashes and improve app quality. When the app crashes, diagnostic information — the stack trace where the error occurred, device model/OS version, app version, and an app-specific install ID (an anonymous identifier not tied to you personally or to any Google account) — is automatically sent to Google's servers. This never includes identifying information such as your location, name, or email address. See Firebase's privacy and security policies for details.

## 5. Data retention and deletion

Information stored on your device (favorites, settings, PIN hash, search history, etc.) can be deleted at any time either through this app's own features or by uninstalling the app. Information included in your Google account backup can be deleted from your device's Settings or your Google account's backup management. The developer never retains this information.

## 6. Children's privacy

This app is not directed at children, and does not knowingly collect information from children.

## 7. Changes to this policy

This policy may be updated to reflect legal changes or new app features (for example, future paid features). Material changes will be reflected in the "Last updated" date above.

## 8. Contact

For questions about this policy, please contact:

dokodemoguard.support@gmail.com
