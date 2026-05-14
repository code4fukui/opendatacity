# opendatacity

日本の地方自治体に関連するオープンデータを分析するためのダッシュボード、ビジュアライゼーション、ツールのコレクションです。

本プロジェクトでは、自治体のウェブサイト、オープンデータの取り組み、教育の準備状況に関するデータを活用し、インタラクティブな地図やチャートを作成しています。

## ビジュアライゼーションとデモ

### セキュリティとドメイン分析
*   [**AOSSLダッシュボード（市区町村）**](https://code4fukui.github.io/opendatacity/citiesratio7x7ssl.html) - 日本全国の市区町村ウェブサイトにおける常時SSL（AOSSL）化率を可視化した7x7のカラム地図です。
*   [**ウェブセキュリティ率**](https://code4fukui.github.io/opendatacity/localgovjp-secureornot.html) - 全地方自治体ウェブサイトにおける `https` と `http` の比率を示す円グラフです。
*   [**信頼できる情報源率**](https://code4fukui.github.io/opendatacity/localgovjp-trust.html) - 情報の信頼性の指標として、SSL（`https`）と公式の `.lg.jp` ドメインの両方の導入状況を分析します。
*   [**市区町村ドメイン調査**](https://code4fukui.github.io/opendatacity/localgovjp-domain.html) - 日本の市区町村が使用しているドメインの調査結果です。
*   [**AOSSLダッシュボード（都道府県）**](https://code4fukui.github.io/opendatacity/prefratio7x7ssl.html) - 47都道府県の公式ウェブサイトにおける常時SSL化率に焦点を当てたカラム地図です。

### オープンデータと教育ダッシュボード
*   [**プログラミング教育準備状況**](https://code4fukui.github.io/opendatacity/progedu7x7.html) - 文部科学省の調査データに基づき、市区町村のプログラミング教育の準備状況を可視化します。
*   [**住所データ公開率**](https://code4fukui.github.io/opendatacity/jpaddress.html) - どの市区町村が公式の住所データを公開しているかを示すダッシュボードです。
*   [**エリア別オープンデータ都市**](https://code4fukui.github.io/opendatacity/area.html) - オープンデータに取り組む都市を地理的なエリア別に分類したものです。
*   [**データ種別オープンデータ**](https://code4fukui.github.io/opendatacity/type.html) - 公開されているオープンデータのカテゴリ別の分布を示すチャートです。
*   [**オープンデータ伝道師**](https://code4fukui.github.io/opendatacity/evangelist.html) - 日本の公式なオープンデータ伝道師の検索可能な一覧です。

### クイズ
*   [**クイズ: むら or そん？**](https://code4fukui.github.io/opendatacity/muraorson.html) - 日本の村名の読み方（「むら」か「そん」か）の知識を試すシンプルなクイズゲームです。

## 使い方

1.  リポジトリをクローンします: `git clone https://github.com/code4fukui/opendatacity.git`
2.  プロジェクトのディレクトリに移動します: `cd opendatacity`
3.  Webブラウザで任意の `.html` ファイルを開き、ビジュアライゼーションを表示します。一部の機能にはローカルWebサーバーが必要になる場合があります。

コアとなるデータセット `localgovjp.js` を更新または置き換えることで、独自の分析を行うことができます。

## データソースと参考資料

*   **[localgovjp](https://github.com/code4fukui/localgovjp)**: 日本の地方自治体のリスト、ウェブサイト、その他のメタデータを含む主要なデータセット。（Code for Fukui 提供）
*   **[TabularMaps / カラム地図](https://github.com/tabularmaps/hq)**: 地理的な可視化に使用される7x7のグリッドマップレイアウト。
*   **文部科学省 プログラミング教育調査**: プログラミング教育の準備状況に関する文部科学省のデータ。
*   **政府CIOポータル**: オープンデータ伝道師一覧のデータソース。
*   **国土地理院**: 住所データのデータソース。

## ライセンス

MIT License
