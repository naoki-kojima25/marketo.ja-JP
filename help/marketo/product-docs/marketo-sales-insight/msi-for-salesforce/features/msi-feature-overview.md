---
unique-page-id: 37356893
description: MSI 機能の概要 - Marketo ドキュメント - 製品ドキュメント
title: MSI 機能の概要
exl-id: e6cd988c-afba-44e3-b240-68258236f344
feature: Marketo Sales Insights
source-git-commit: bda95da160c5a27a0a460d26c102e6166c1ddea0
workflow-type: tm+mt
source-wordcount: '965'
ht-degree: 70%

---

# MSI 機能の概要 {#msi-feature-overview}

MSI には、Salesforce Lightning および Classic で使用できる次の機能があります。

>[!NOTE]
>
>使用可能なすべてのデータを表示するには、Windows の場合はブラウザーのズームが 125% 以下、Mac OS の場合は 150% 以下に設定されていることを確認してください。

## Visualforce パネル {#visualforce-panel}

MSI Visualforce パネルには、次の機能が含まれています。

* タブ

   * [Insights ダッシュボード](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/features/insights-dashboard-feature-overview.md)
   * 注目のアクション
   * Web アクティビティ
   * メール
   * スコア

* アクション

   * Marketo キャンペーンに追加
   * Marketo メールの送信
   * ウォッチリストに追加／ウォッチリストから変更

* 星と炎

## リードのレイアウト {#lead-layout}

Visualforce ページ：

* リード – ハイパー「フルリストに移動」をクリックするオプションが含まれています。Salesforce の新しいタブに送信され、MSI パネルが完全なページレイアウトで表示されます
* リードの全リスト – 「全リストに移動」オプションは含まれません
* リード（モバイル） - Salesforce モバイルアプリケーションで表示できます
* リード取引先責任者ブリッジ - 「MSI 取引先責任者 ID」フィールドに追加した取引先責任者の MSI パネルが表示されます

フィールド：

* 最新の注目のアクション
* 最新の注目のアクション発生日
* 最新の注目のアクションの詳細
* 最新の注目のアクションのソース
* 最新の注目のアクションのタイプ
* セールスによる最後の Marketo アクティビティ
* セールスによる最後の Marketo エンゲージメント
* 相対スコア
* 相対スコア値
* 緊急度
* 緊急度の値
* Marketoで表示 – このフィールドをクリックすると、Marketoでリードの編集できないビューが開きます。 含まれるもの：リード情報、会社情報、SFDC リード情報、SFDC カスタムフィールド、アクティビティログ
* MSI 連絡先 ID – このフィールドに Salesforce 連絡先を追加し、リードレイアウトに「リード連絡先ブリッジ」パネルを含めて、連絡先の MSI パネルを表示します

## 取引先責任者のレイアウト {#contact-layout}

Visualforce ページ：

* 連絡先 – ハイパー「フルリストに移動」をクリックするオプションが含まれています。Salesforce の新しいタブに送信され、MSI パネルがフルページレイアウトで表示されます
* 連絡先の全リスト – 「全リストに移動」オプションは含まれません
* 取引先責任者（モバイル） - Salesforce モバイルアプリケーションで表示できます
* Marketo Campaign の取引先責任者ページに追加 - 「Marketo Campaign に追加」機能は、このパネル内で使用できます。

フィールド：

* 最新の注目のアクション
* 最新の注目のアクション発生日
* 最新の注目のアクションの詳細
* 最新の注目のアクションのソース
* 最新の注目のアクションのタイプ
* セールスによる最後の Marketo アクティビティ
* 相対スコア
* 相対スコア値
* 緊急度
* 緊急度の値
* Marketoで表示 – このフィールドをクリックすると、Marketoでリードの編集できないビューが開きます。 含まれるもの：リード情報、会社情報、SFDC リード情報、SFDC カスタムフィールド、アクティビティログ
* Mkto リードスコア
* Sales Insight - 取引先責任者の完全なリストページを開きます

## アカウントのレイアウト {#account-layout}

Visualforce ページ：

* アカウント – ハイパー「フルリストに移動」をクリックするオプションが含まれています。Salesforce の新しいタブに送信され、MSI パネルがフルページレイアウトで表示されます
* アカウントの完全なリスト – 「完全なリストに移動」オプションは含まれません
* アカウント（モバイル） - Salesforce モバイルアプリケーションで表示できます

フィールド：

* Sales Insight - 取引先責任者の完全なリストページを開きます

アクション：

* Marketo キャンペーンに追加
* Marketo メールの送信
* ウォッチリストに追加／ウォッチリストから変更

次の機能は、アカウントのレイアウトページでは&#x200B;**使用できません**。

* 星と炎

## 商談のレイアウト {#opportunity-layout}

Visualforce ページ：

* 商談 – ハイパー「フルリストに移動」をクリックするオプションが含まれます。Salesforce の新しいタブに送信され、MSI パネルが全ページレイアウトで表示されます。
* オポチュニティの全リスト – 「全リストに移動」オプションが含まれていない
* 商談（モバイル） - Salesforce モバイルアプリケーションで表示できます

フィールド：

* Sales Insight - 取引先責任者の完全なリストページを開きます
* Marketo 商談分析 - Marketo で商談の影響アナライザーを開く

アクション：

* Marketo キャンペーンに追加
* Marketo メールの送信
* ウォッチリストに追加／ウォッチリストから変更

次の機能は、商談のレイアウトページでは&#x200B;**使用できません**。

* 星と炎

## リードおよび取引先責任者のリスト表示（バルクアクション） {#lead-and-contact-list-view-bulk-actions}

Salesforce Lightning：「ウォッチリストに追加」、「Marketo キャンペーンに追加」、「リードおよび取引先責任者リスト」表示の「Marketo メールを送信」一括アクションボタン。

Salesforce Classic：「ウォッチリストに追加」、「Marketo Campaign に追加」、「Marketo メールを送信」一括アクションボタンを「リードおよび取引先責任者」リスト表示に追加します。

## Marketo タブ {#marketo-tab}

* 最優先

   * ビューを作成および編集する機能が含まれます。Marketo設定ページの「デフォルトの非表示」オプションの設定に応じて、おすすめコンテンツを非表示にする機能
   * 列 - 名前、アカウント、注目のアクション、ステータスヘッダー、アクション（星と炎）、非表示

* マイウォッチリスト

   * ビューの作成と編集が可能
   * 列 - 名前、アカウント、注目のアクション、ステータスヘッダー、アクション（星と炎）、削除

* Web アクティビティ

   * ビューの作成と編集、時間枠フィルタリング機能を含む
   * 列 - ページビュー、名前、アカウント、最終訪問

*  匿名の Web アクティビティ

   * ビューの作成と編集、時間枠フィルタリング機能を含む
   * 列 - ページビュー、会社、前回の訪問、調査（会社の LinkedIn ページを開く）

* メール

   * ビューの作成と編集が可能
   * 列 - 名前、アカウント、件名、日付、開封、クリック

* リードフィード - 注目のアクションを購読する機能が含まれます。この機能を使用するには、設定ページの RSS フィードを有効にする必要があります

   * この注目のアクションをおこなったリード／取引先責任者
   * 注目のアクションのタイプ（web、メール、またはマイルストーン）および説明
   * アカウント名
   * 注目のアクションの発生時刻
   * このタイプのイベントのメール通知を受信する購読オプション
   * この人を表示する高優先度アイコンは、「最有望見込客」です

## Marketo Sales Insight の「設定」タブ {#marketo-sales-insight-configuration-tab}

* 操作の設定：SFDC での MSI の設定に必要な Soap および Rest API の資格情報を含みます
* MSI 構成：Marketo タブと MSI visualforce パネルの設定が含まれます
* Marketo Sales Insight のリセット：すべての設定を消去する機能が含まれます

>[!MORELIKETHIS]
>
>[Salesforce の「Marketo Sales Insight の設定」タブ](/help/marketo/product-docs/marketo-sales-insight/msi-for-salesforce/configuration/marketo-sales-insight-configuration-tab-in-salesforce.md)

## Sales Insight パフォーマンスレポート {#sales-insight-performance-reports}

Salesforce、Microsoft Dynamics、Gmail または Outlook プラグインを通じて送信されるメールのパフォーマンスを表示します

## モバイル用 MSI {#msi-for-mobile}

MSI 機能は、Salesforce モバイルアプリケーションでサポートされています

## 言語サポート {#language-support}

Marketo Sales Insight は言語別に保存されます。したがって、複数の言語を扱う場合は、言語ごとに別個に資格情報を入力する必要があります。

>[!NOTE]
>
>* ウォッチリストに追加するには、連絡先/リードがデフォルトパーティションに存在する必要があります。
>
>* MSI Salesforce パッケージは、依存フィールドを含むカスタムビューをサポートしていません。
