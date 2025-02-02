---
description: WR-YYYY-MM-Web リクエストプログラム — Marketoドキュメント — 製品ドキュメント
title: WR-YYYY-MM-Web リクエストプログラム
feature: Programs
exl-id: 539dfd08-eed8-4fac-b976-7fe43f5d24b3
source-git-commit: 38274b4859ae38c018ee73d4f1715fdf6a78e815
workflow-type: tm+mt
source-wordcount: '402'
ht-degree: 16%

---

# WR-YYYY-MM-Web リクエストプログラム {#wr-yyyy-mm-web-request-program}

これは、Marketo Engageのデフォルトプログラムを利用した連絡先リクエスト、見積依頼、デモ依頼、または試用依頼フォームに最適なサンプルプログラムです。 Marketoランディングページで、またはMarketo以外のランディングページの埋め込みフォームとして使用できます。 フォームの送信時に、指定した個人にアラート電子メールが送信されます。

戦略に関するサポートやプログラムのカスタマイズについては、Adobeアカウントチームにお問い合わせいただくか、 [Adobe Professional Services](https://business.adobe.com/customers/consulting-services/main.html){target="_blank"} ページに貼り付けます。

## チャネルサマリ {#channel-summary}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th>チャネル</th> 
   <th>メンバーシップステータス</th>
   <th>アナリティクス動作</th>
   <th>プログラムのタイプ</th>
  </tr> 
  <tr> 
   <td>ウェブリクエスト</td> 
   <td>01 — エンゲージ済み — 成功</td>
   <td>包含</td>
   <td>デフォルト</td>
  </tr>
 </tbody> 
</table>

## プログラムに次のアセットが含まれています {#program-contains-the-following-assets}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th>タイプ</th> 
   <th>テンプレート名</th>
   <th>アセット名</th>
  </tr>
  <tr> 
   <td>フォーム</td> 
   <td> </td>
   <td>FM-WebRequestForm</td>
  </tr>
  <tr> 
   <td>メール</td> 
   <td><a href="/help/marketo/product-docs/core-marketo-concepts/programs/program-library/quick-start-email-template.md" target="_blank">クイックスタートメールテンプレート</a></td>
   <td>Alert-WebRequest</td>
  </tr>
  <tr> 
   <td>ランディングページ</td> 
   <td><a href="/help/marketo/product-docs/core-marketo-concepts/programs/program-library/quick-start-landing-page-template.md" target="_blank">クイックスタート LP テンプレート</a></td>
   <td>01 - LP — 要求</td>
  </tr>
  <tr> 
   <td>ランディングページ</td> 
   <td><a href="/help/marketo/product-docs/core-marketo-concepts/programs/program-library/quick-start-landing-page-template.md" target="_blank">クイックスタート LP テンプレート</a></td>
   <td>02 - LP - ThankYou</td>
  </tr>
  <tr> 
   <td>ローカルレポート</td> 
   <td> </td>
   <td>ランディングページの効果</td>
  </tr>
   <tr> 
   <td>スマートキャンペーン</td> 
   <td> </td>
   <td>Web リクエストからの新規担当者</td>
  </tr>
   <tr> 
   <td>スマートキャンペーン</td> 
   <td> </td>
   <td>ウェビナーからの新規担当者</td>
  </tr>
  <tr> 
   <td>フォルダー</td> 
   <td> </td>
   <td>アセット — すべてのクリエイティブアセットを格納します。 
<br/>（アラートおよびランディングページ用のサブフォルダー）</td>
  </tr>
  <tr> 
   <td>フォルダー</td> 
   <td> </td>
   <td>キャンペーン — すべてのスマートキャンペーンを格納</td>
  </tr>
  <tr> 
   <td>フォルダー</td> 
   <td> </td>
   <td>レポート</td>
  </tr>
 </tbody> 
</table>

![](assets/wr-yyyy-mm-web-request-program-1.png)

## 含まれるマイトークン {#my-tokens-included}

<table style="table-layout:auto"> 
 <tbody> 
  <tr> 
   <th>トークンのタイプ</th> 
   <th>トークン名</th>
   <th>値</th>
  </tr>
  <tr> 
   <td>テキスト</td> 
   <td><code>{{my.Request-Type}}</code></td>
   <td>お問い合わせ</td>
  </tr>
  <tr> 
   <td>テキスト</td> 
   <td><code>{{my.ALERT-FromAddress}}</code></td>
   <td>PlaceholderFrom.email@mydomain.com</td>
  </tr>
  <tr> 
   <td>テキスト</td> 
   <td><code>{{my.ALERT-FromName}}</code></td>
   <td><code><--My From Name Here--></code></td>
  </tr>
  <tr> 
   <td>テキスト</td> 
   <td><code>{{my.ALERT-ReplyToAddress}}</code></td>
   <td>reply-to.email@mydomain.com</td>
  </tr>
  <tr> 
   <td>テキスト</td> 
   <td><code>{{my.PageURL-ThankYou}}</code></td>
   <td>My.ThankYouPageURL?http://</td>
  </tr>
 </tbody> 
</table>

## 競合ルール {#conflict-rules}

* **プログラムタグ**
   * この配信登録にタグを作成 — _推奨_
   * 無視する

* **同じ名前のランディングページテンプレート**
   * 元のテンプレートのコピー
   * インポート先のテンプレートの使用 - _推奨_

* **同じ名前の画像**
   * どちらのファイルも保持する
   * この配信登録内アイテムの置換 - _推奨_

* **同じ名前のメールテンプレート**
   * どちらのテンプレートも保持する
   * 既存のテンプレートを置換 — _推奨_

## ベストプラクティス {#best-practices}

* ウェビナープログラムを読み込んだ後、フォームをローカルアセットから Design Studio 内のグローバルアセットに移動します。
   * フォームの数を減らし、Design Studio からより多くのグローバルアセットを利用することで、プログラムのデザインと管理ガバナンスにおけるスケーラビリティを高めることができます。 また、フィールド、オプトイン言語などの定期的なコンプライアンス更新を柔軟におこなうこともできます。

* 現在ブランド化されているテンプレートを利用するには、読み込んだプログラムでテンプレートを更新することを検討するか、スニペットまたは適切なロゴ/フッター情報を追加して、新しく読み込んだテンプレートをブランドに合わせて更新します。

* 命名規則に合わせて、このプログラム例の命名規則を更新することを検討してください。

>[!NOTE]
>
>必要に応じて、プログラムテンプレートのマイトークンの値を更新し、プログラムを使用するたびに値を更新してください。

>[!IMPORTANT]
>
>URL を参照する My Tokens にhttp://やhttps://を含めることはできません。含めないと、リンクがアセット内で適切に機能しません。
