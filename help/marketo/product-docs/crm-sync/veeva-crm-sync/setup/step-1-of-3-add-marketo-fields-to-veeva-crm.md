---
description: 手順 1 / 3 - Marketo フィールドの Veeva CRM への追加 - Marketo ドキュメント - 製品ドキュメント
title: 手順 1 / 3：Marketo フィールドの Veeva CRM への追加
exl-id: a9a59e76-a7a4-4391-8169-922bd6acfb6d
feature: Veeva CRM
source-git-commit: 0087a5e88b8bd9601875f68a2e7cadeebdb5d682
workflow-type: tm+mt
source-wordcount: '533'
ht-degree: 89%

---

# 手順 1 / 3：Marketo フィールドを Veeva CRM に追加 {#step-1-of-3-add-marketo-fields-to-veeva-crm}

>[!PREREQUISITES]
>
>Veeva CRM インスタンスが Salesforce API にアクセスして、Marketo Engage と Veeva CRM の間でデータを同期する必要があります。

Marketo Engage は、一連のフィールドを使用して、特定の種類のマーケティング関連情報を取り込みます。Veeva CRM でこのデータを使用する場合は、以下の手順に従ってください。

`1.` 取引先責任者オブジェクト上の Veeva CRM にカスタムフィールド「スコア」を作成します。

`2.`必要に応じて、追加のフィールドを作成できます（以下の表を参照）。

これらのカスタムフィールドはすべてオプションで、Marketo Engage と Veeva CRM を同期するのに必須ではありません。

## Marketo フィールドを Veeva CRM に追加 {#add-marketo-fields-to-veeva-crm}

上記の Veeva CRM で、リードおよび取引先責任者オブジェクトにカスタムフィールドを追加します。さらに追加する場合は、この節の最後にある使用可能フィールドのテーブルを参照してください。

「スコア」フィールドに対して、次の手順を実行してフィールドを追加します。

1. Veeva CRM にログインし、「**[!UICONTROL 設定]**」をクリックします。

   ![](assets/step-1-of-3-add-marketo-fields-1.png)

1. クリック **[!UICONTROL オブジェクトとフィールド]** を選択し、 **[!UICONTROL Object Manager]**.

   ![](assets/step-1-of-3-add-marketo-fields-2.png)

1. 検索バーで「連絡先」を検索します。

   ![](assets/step-1-of-3-add-marketo-fields-3.png)

1. 次をクリック： **[!UICONTROL 連絡先]** オブジェクト。

1. 選択 **[!UICONTROL フィールドと関係]**.

1. 「**[!UICONTROL 新規]**」をクリックします。

   ![](assets/step-1-of-3-add-marketo-fields-4.png)

1. 適切なフィールドタイプを選択します（スコア — 数値）。

   ![](assets/step-1-of-3-add-marketo-fields-5.png)

1. 「**[!UICONTROL 次へ]**」をクリックします。

   ![](assets/step-1-of-3-add-marketo-fields-6.png)

1. 次を入力します。 **[!UICONTROL フィールドラベル]**, **[!UICONTROL 長さ]**、および **[!UICONTROL フィールド名]** フィールドの場合は、次の表に示すように使用します。

<table>
 <tbody>
  <tr>
   <th>フィールドラベル
   <th>フィールド名
   <th>データタイプ
   <th>フィールド属性
  </tr>
  <tr>
   <td>スコア</td>
   <td>mkto71_Lead_Score</td>
   <td>数字</td>
   <td>長さ 10 <br/>小数点以下桁数 0</td>
  </tr>
 </tbody>
</table>

>[!NOTE]
>
>Veeva CRM では、フィールド名を使用して API 名を作成するときに、フィールド名に __c を追加します。

![](assets/step-1-of-3-add-marketo-fields-7.png)

>[!NOTE]
>
>テキストフィールドと数値フィールドには長さが必要ですが、日付/時間フィールドには必要ありません。説明はオプションです。

1. 「**[!UICONTROL 次へ]**」をクリックします。

   ![](assets/step-1-of-3-add-marketo-fields-8.png)

1. アクセス設定を指定し、「**[!UICONTROL 次へ]**」をクリックします。

1. すべてのロールを表示および読み取り専用に設定します。

1. 同期ユーザのプロファイルの読み取り専用のチェックをオフにします。

* 同期ユーザとしてシステム管理者のプロファイルを持つユーザがいる場合は、システム管理者プロファイルの読み取り専用のチェックをオフにします（以下を参照）。
* 同期ユーザにカスタムプロファイルを作成した場合は、そのカスタムプロファイルの読み取り専用のチェックをオフにします。

  ![](assets/step-1-of-3-add-marketo-fields-9.png)

1. フィールドを表示するページレイアウトを選択します。

1. 「**[!UICONTROL 保存して新規作成]**」をクリックして戻り、他の 2 つのカスタムフィールドのそれぞれを作成します。

1. クリック **[!UICONTROL 保存]** 3 つ全てが終わったら

   ![](assets/step-1-of-3-add-marketo-fields-10.png)

>[!NOTE]
>
>フィールドを取引先責任者オブジェクトに追加することで、個人取引先オブジェクトにも追加されます。

オプション：このテーブルの追加のカスタムフィールドに対して上記の手順を実行します。

<table>
 <tbody>
  <tr>
   <th>フィールドラベル
   <th>フィールド名
   <th>データタイプ
   <th>フィールド属性
  </tr>
  <tr>
   <td>推測される市区町村</td>
   <td>mkto71_Inferred_City</td>
   <td>テキスト</td>
   <td>長さ 255</td>
  </tr>
  <tr>
   <td>推測される企業</td>
   <td>mkto71_Inferred_Company</td>
   <td>テキスト</td>
   <td>長さ 255</td>
  </tr>
  <tr>
   <td>推測される国</td>
   <td>mkto71_Inferred_Country</td>
   <td>テキスト</td>
   <td>長さ 255</td>
  </tr>
  <tr>
   <td>推測される都市圏</td>
   <td>mkto71_Inferred_Metropolitan_Area</td>
   <td>テキスト</td>
   <td>長さ 255</td>
  </tr>
  <tr>
   <td>推測される市外局番</td>
   <td>mkto71_Inferred_Phone_Area_Code</td>
   <td>テキスト</td>
   <td>長さ 255</td>
  </tr>
  <tr>
   <td>推測される郵便番号</td>
   <td>mkto71_Inferred_Postal_Code</td>
   <td>テキスト</td>
   <td>長さ 255</td>
  </tr>
  <tr>
   <td>推測される都道府県／地域</td>
   <td>mkto71_Inferred_State_Region</td>
   <td>テキスト</td>
   <td>長さ 255</td>
  </tr>
 </tbody>
</table>

>[!NOTE]
>
>Marketo によって自動的に割り当てられたフィールドの値は、新しいフィールドが作成されたときに Veeva CRM ですぐに使用できるわけではありません。Marketo は、次のアップデート時にいずれかのシステム上のレコードに対して Veeva CRM とデータを同期します（つまり、Marketo と Veeva CRM の間で同期されているフィールドのアップデート）。
