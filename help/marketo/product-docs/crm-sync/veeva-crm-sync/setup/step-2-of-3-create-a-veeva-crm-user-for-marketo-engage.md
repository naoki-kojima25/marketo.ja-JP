---
description: 手順 2 / 3 - Marketo Engage 用の Veeva CRM ユーザの作成 - Marketo ドキュメント - 製品ドキュメント
title: 手順 2 / 3 - Marketo Engage 用の Veeva CRM ユーザの作成
exl-id: 78945192-36b0-4e0b-830a-f37eb0b83484
feature: Veeva CRM
source-git-commit: 0087a5e88b8bd9601875f68a2e7cadeebdb5d682
workflow-type: tm+mt
source-wordcount: '631'
ht-degree: 77%

---

# 手順 2 / 3：Marketo Engage 用の Veeva CRM ユーザの作成 {#step-2-of-3-create-a-veeva-crm-user-for-marketo-engage}

>[!NOTE]
>
>この記事の手順は、Veeva CRM 管理者が実行する必要があります。

>[!PREREQUISITES]
>
>[手順 1／3：Marketo フィールドの Salesforce への追加（Professional）](/help/marketo/product-docs/crm-sync/veeva-crm-sync/setup/step-1-of-3-add-marketo-fields-to-veeva-crm.md){target="_blank"}

この記事では、Veeva CRM ページレイアウトを使用してフィールド権限をカスタマイズし、Marketo と Veeva CRM 間の同期ユーザを作成します。

## ページレイアウトの設定 {#set-page-layouts}

これらの手順に従うと、Marketo 同期ユーザはカスタムフィールドをアップデートできます。

1. ナビゲーション検索バーのアカウント（担当者アカウント）ページレイアウトを、Enter キーを押さずにクリックし、 **[!UICONTROL ページレイアウト]** [ 連絡先 ] の下

   ![](assets/step-2-of-3-create-a-veeva-crm-user-1.png)

1. 「**[!UICONTROL ページレイアウト]**」をクリックします。

   ![](assets/step-2-of-3-create-a-veeva-crm-user-2.png)

1. 「**[!UICONTROL HCP - プロフェッショナル]**」をクリックします。

   ![](assets/step-2-of-3-create-a-veeva-crm-user-3.png)

1. 新しい&#x200B;**[!UICONTROL セクション]**&#x200B;をページレイアウトに追加します。

1. 「セクション名」に「Marketo」と入力し、「**[!UICONTROL OK]**」をクリックします。

   ![](assets/step-2-of-3-create-a-veeva-crm-user-4.png)

1. 「スコア」フィールドをクリックし、「Marketo」セクションにドラッグします。

   ![](assets/step-2-of-3-create-a-veeva-crm-user-5.png)

1. 次のフィールドに対して、上記の手順を繰り返します。

   * 推測される市区町村
   * 推測される企業
   * 推測される国
   * 推測される都市圏
   * 推測される市外局番
   * 推測される郵便番号
   * 推測される都道府県／地域

   >[!NOTE]
   >
   >Marketo が読み取り／書き込みできるように、これらのフィールドをページレイアウト上に配置する必要があります。

   >[!TIP]
   >
   >ページの右側に下にドラッグして、フィールドの列を 2 つ作成します。列の長さのバランスを取るために、フィールドを片側から他方に移動できます。

1. HCP-Professional レイアウトが完了したら、「**[!UICONTROL 保存]**」をクリックします。

   ![](assets/step-2-of-3-create-a-veeva-crm-user-6.png)

   >[!NOTE]
   >
   >他のアカウントページレイアウトに対して、これを繰り返します。

## プロファイルの作成 {#create-a-profile}

1. 「**[!UICONTROL 設定]**」をクリックします。

   ![](assets/step-2-of-3-create-a-veeva-crm-user-7.png)

1. ナビゲーション検索バーに「プロファイル」と入力し、 **[!UICONTROL プロファイル]** リンク。

   ![](assets/step-2-of-3-create-a-veeva-crm-user-8.png)

1. 「**[!UICONTROL 新規]**」をクリックします。

   ![](assets/step-2-of-3-create-a-veeva-crm-user-9.png)

1. 「標準ユーザー」を選択し、プロファイルに「Marketo-Salesforce Sync」という名前を付け、 **[!UICONTROL 保存]**.

   ![](assets/step-2-of-3-create-a-veeva-crm-user-10.png)

## プロファイル権限の設定 {#set-profile-permissions}

1. 「**[!UICONTROL 編集]**」をクリックしてセキュリティ権限を設定します。

   ![](assets/step-2-of-3-create-a-veeva-crm-user-11.png)

1. 「管理権限」セクションで、 **[!UICONTROL API 有効]** が選択されている。

   ![](assets/step-2-of-3-create-a-veeva-crm-user-12.png)

   >[!TIP]
   >
   >パスワードの有効期限なしボックスのチェックは必ずオンにしてください。

1. 「一般ユーザー権限」セクションで、 **[!UICONTROL イベントを編集]** および **[!UICONTROL タスクを編集]** が選択されている。

   ![](assets/step-2-of-3-create-a-veeva-crm-user-13.png)

1. 「標準オブジェクト権限」セクションで、 **[!UICONTROL 読み取り]**, **[!UICONTROL 作成]**, **[!UICONTROL 編集]**、および **[!UICONTROL 削除]** アカウントと連絡先に対する権限がチェックされます。

   ![](assets/step-2-of-3-create-a-veeva-crm-user-14.png)

1. 「カスタムオブジェクトの権限」セクションで、読み取り権限が **[!UICONTROL 通話]**, **[!UICONTROL 呼び出しキーメッセージ]**、およびその他の目的のカスタムオブジェクト。

   ![](assets/step-2-of-3-create-a-veeva-crm-user-15.png)

1. 終了したら、ページの下部にある「**[!UICONTROL 保存]**」をクリックします。

   ![](assets/step-2-of-3-create-a-veeva-crm-user-16.png)

## フィールド権限の設定 {#set-field-permissions}

1. 同期に必要なカスタムフィールドをマーケターと話し合います。

   >[!NOTE]
   >
   >この手順を実行すると、Marketo に表示する必要のないフィールドが防止され、混乱が軽減され、同期が高速化されます。

1. プロファイルの詳細ページで、[!UICONTROL フィールドレベルのセキュリティ]セクションに移動します。クリック **[!UICONTROL 表示]** 連絡先オブジェクトとアカウントオブジェクトのアクセシビリティを編集する場合。

   ![](assets/step-2-of-3-create-a-veeva-crm-user-17.png)

   >[!TIP]
   >
   >組織のニーズに応じて、他のオブジェクトを設定できます。

1. 各オブジェクトに対して、「**[!UICONTROL 編集]**」をクリックします。

   ![](assets/step-2-of-3-create-a-veeva-crm-user-18.png)

1. 不要なフィールドを見つけ、「読み取りアクセス」と「編集アクセス」が _オフ_. 終了したら「**[!UICONTROL 保存]**」をクリックします。

   ![](assets/step-2-of-3-create-a-veeva-crm-user-19.png)

   >[!NOTE]
   >
   >カスタムフィールドのアクセシビリティのみを編集します。

1. 不要なフィールドをすべて無効にした後で、次のオブジェクトフィールドの読み取りアクセスと編集アクセスのチェックをオンにします。終了したら「**[!UICONTROL 保存]**」をクリックします。

<table>
 <tbody>
  <tr>
   <th>オブジェクト
   <th>フィールド
  </tr>
  <tr>
   <td>アカウント</td>
   <td>タイプフィールド</td>
  </tr>
  <tr>
   <td>イベント</td>
   <td>すべてのフィールド</td>
  </tr>
  <tr>
   <td>タスク</td>
   <td>すべてのフィールド</td>
  </tr>
 </tbody>
</table>

## 同期ユーザを作成 {#create-sync-user}

Marketo は、Veeva CRM にアクセスするための資格情報が必要です。これは、次の手順で作成した専用ユーザで行うのが最適です。

>[!NOTE]
>
>組織に追加の Veeva CRM ライセンスがない場合は、システム管理者プロファイルを持つ既存のマーケティングユーザを使用できます。

1. ナビゲーション検索バーに「ユーザー」と入力し、「**[!UICONTROL ユーザーを管理]**」の下の「ユーザー」をクリックします。

   ![](assets/step-2-of-3-create-a-veeva-crm-user-20.png)

1. 「**[!UICONTROL 新規ユーザ]**」をクリックします。

   ![](assets/step-2-of-3-create-a-veeva-crm-user-21.png)

1. 必須フィールドに入力し、「ユーザライセンス：Salesforce」を選択、「プロファイル：Marketo 同期ユーザ」を設定して、「**[!UICONTROL 保存]**」をクリックします。

   ![](assets/step-2-of-3-create-a-veeva-crm-user-22.png)

>[!TIP]
>
>入力した電子メールアドレスが有効であることを確認します。パスワードをリセットするには、同期ユーザとしてログインする必要があります。

これで完了です。Marketo が Veeva CRM に接続するために使用できるアカウントが作成されました。やってみましょう。

>[!MORELIKETHIS]
>
>[手順 3/3：Marketo と Veeva CRM の接続](/help/marketo/product-docs/crm-sync/veeva-crm-sync/setup/step-3-of-3-connect-marketo-engage-and-veeva-crm.md){target="_blank"}
