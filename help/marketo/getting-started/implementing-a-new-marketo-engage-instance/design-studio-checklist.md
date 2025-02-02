---
description: 新しいMarketo Engageインスタンス用に Design Studio セクションを設定します。
title: 新しいインスタンスのベストプラクティス - Design Studio チェックリスト
feature: Getting Started
exl-id: 070ee235-dad0-4627-bac0-14bf0174bb03
source-git-commit: 7805983cdaff0b99a38aefc2c2467b53f3386da3
workflow-type: tm+mt
source-wordcount: '369'
ht-degree: 27%

---

# 新しいインスタンスのベストプラクティス：Design Studio チェックリスト {#new-instance-best-practices-design-studio-checklist}

Design Studio セクションには、再利用可能な「グローバルアセット」を配置する必要があります。 組織がプログラムで使用する予定のグローバルアセットを作成し、一貫性のある命名規則を使用して、サブフォルダーに整理して検索を容易にします。

忘れずに[チェックリストをダウンロード](/help/marketo/getting-started/implementing-a-new-marketo-engage-instance/assets/adobe-marketo-engage-new-instance-admin-checklist.xlsx)し、進捗状況を追跡してください。

## ランディングページ {#landing-pages}

<table>
<thead>
  <tr>
    <th style="width:20%">エリア</th>
    <th style="width:80%">アクション項目</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>グローバルランディングページ</td>
    <td><li>作成 <a href="https://experienceleague.adobe.com/ja/docs/marketo/using/product-docs/demand-generation/landing-pages/understanding-landing-pages/understanding-free-form-vs-guided-landing-pages#product-docs" target="_blank">グローバルランディングページ （フリーフォーム/ガイド付き）</a>.</li>
    <li><a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/demand-generation/landing-pages/understanding-landing-pages/landing-page-test-groups" target="_blank">テストページの作成</a> を使用して、勝者のランディングページテンプレートを A/B テストします（該当する場合）。</li></td>
  </tr>
  <tr>
    <td>テンプレート</td>
    <td><li>グローバルランディングページのデザインを作成します。</li></td>
  </tr>
  <tr>
    <td>プライバシーとコンプライアンス</td>
    <td><li>を使用したフッターの作成 <a href="https://experienceleague.adobe.com/ja/docs/marketo/using/product-docs/demand-generation/landing-pages/personalizing-landing-pages/add-a-snippet-to-a-landing-page" target="_blank">スニペット</a> または <a href="https://experienceleague.adobe.com/ja/docs/marketo/using/product-docs/demand-generation/landing-pages/personalizing-landing-pages/add-text-and-tokens-to-a-landing-page#add-a-token-to-your-landing-page" target="_blank">トークン</a> をランディングページに追加して、プライバシーコンプライアンスを確保します。</li></td>
  </tr>
</tbody>
</table>

## フォーム {#forms}

<table>
<thead>
  <tr>
    <th style="width:20%">エリア</th>
    <th style="width:80%">アクション項目</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>グローバルフォーム</td>
    <td><li>の設定 <a href="https://experienceleague.adobe.com/ja/docs/marketo/using/product-docs/demand-generation/forms/creating-a-form/create-a-form#product-docs" target="_blank">グローバルフォーム</a> サブスクリプション環境設定、ゲートされたコンテンツのダウンロード、デモのリクエスト、ウェビナー登録などのユースケースの場合。</li></td>
  </tr>
  <tr>
    <td>プライバシーとコンプライアンス</td>
    <td><li>フォームを保持 <a href="https://business.adobe.com/resources/ebooks/the-gdpr-and-the-marketer.html" target="_blank">EU 一般データ保護規則（GDPR）</a> 準拠。</li></td>
  </tr>
  <tr>
    <td>データの標準化</td>
    <td><li>データが乱雑にならないように、オープンテキストフィールドではなく、<a href="https://experienceleague.adobe.com/ja/docs/marketo/using/product-docs/demand-generation/forms/creating-a-form/add-a-field-to-a-form#product-docs" target="_blank">フォームフィールド</a>に選択リストを適用することを検討してください。</li></td>
  </tr>
</tbody>
</table>

## メール {#emails}

<table>
<thead>
  <tr>
    <th style="width:20%">エリア</th>
    <th style="width:80%">アクション項目</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>グローバルメール</td>
    <td><li>グローバルメールを作成します。</li></td>
  </tr>
  <tr>
    <td>テンプレート</td>
    <td><li>モジュールベースの設計 <a href="https://experienceleague.adobe.com/ja/docs/marketo/using/product-docs/email-marketing/general/email-editor-2/create-an-email-template" target="_blank">メールテンプレート</a> デザイナーや開発者と協力するか、独自のHTMLを使用する。</li>
    <li>テスト済みのメールテンプレートを作成し、勝者テンプレートを A/B テストします（該当する場合）。</li></td>
  </tr>
  <tr>
    <td>プライバシーとコンプライアンス</td>
    <td><li><a href="https://experienceleague.adobe.com/ja/docs/marketo/using/product-docs/email-marketing/general/functions-in-the-editor/add-a-snippet-to-an-email" target="_blank">スニペットを追加</a> をメールテンプレートに追加して、著作権年、グローバルな場所、コンプライアンス固有の言語などの再利用可能なブロックを制御できるようにします。</li>
    <li><a href="https://experienceleague.adobe.com/en/docs/marketo/using/product-docs/email-marketing/general/using-tokens/add-an-email-script-token-to-your-email" target="_blank">トークンを追加</a> ターゲットオーディエンスに基づいてコンテンツをパーソナライズします。</li></td>
  </tr>
</tbody>
</table>

## スニペット {#snippets}

<table>
<thead>
  <tr>
    <th style="width:20%">エリア</th>
    <th style="width:80%">アクション項目</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>スニペット</td>
    <td><li>作成 <a href="https://experienceleague.adobe.com/ja/docs/marketo/using/product-docs/personalization/segmentation-and-snippets/snippets/create-a-snippet#product-docs" target="_blank">スニペット</a> 連絡先情報、ソーシャルメディアリンク、ブランド情報、メールやランディングページのプライバシーとコンプライアンスメモなど、複数のユースケースに使用できる再利用可能なコンテンツブロックを用意する場合。</li></td>
  </tr>
</tbody>
</table>

## 画像とファイル {#images-and-files}

<table>
<thead>
  <tr>
    <th style="width:20%">エリア</th>
    <th style="width:80%">アクション項目</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>命名規則</td>
    <td><li>画像とファイルには一貫した命名規則を使用します。</li>  
    <br>例：  
    <br><ul><li>ファイル命名規則：アセットタイプ – アセット名（例：White-Paper-Evaluating-Cloud-Computing-Get-Your-Board-on-Board）</li>
    <p><li>画像の命名規則：画像タイプ-アセットタイプ-アセット名（例：Thumbnail-White-Paper-Evaluating-Cloud-Computing-Get-Your-Board-on-Board）</li></td>
  </tr>
</tbody>
</table>

## 組織 {#organization}

<table>
<thead>
  <tr>
    <th style="width:20%">エリア</th>
    <th style="width:80%">アクション項目</th>
  </tr>
</thead>
<tbody>
  <tr>
    <td>フォルダー構造 </td>
    <td><li>アセットタイプごとのサブフォルダーの作成と <a href="https://experienceleague.adobe.com/ja/docs/marketo/using/product-docs/demand-generation/images-and-files/organize-your-images-and-files-using-folders" target="_blank">グローバルアセットの整理</a> （例：会話フロー、メールテンプレート、電子メール、フォーム、画像とファイル、ランディングページ、ランディングページテンプレート、スニペットなど）。 適切です。</li></td>
  </tr>
</tbody>
</table>
