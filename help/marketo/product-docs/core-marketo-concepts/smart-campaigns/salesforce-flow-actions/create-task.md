---
unique-page-id: 1147017
description: タスクの作成 - Marketo ドキュメント - 製品ドキュメント
title: タスクの作成
exl-id: c484d913-1fd8-4716-8caa-0bf318218ca1
feature: Smart Campaigns, Salesforce Integration
source-git-commit: 4bae0126d6b36720e170bea7b6b973508c855633
workflow-type: tm+mt
source-wordcount: '113'
ht-degree: 100%

---

# タスクの作成 {#create-task}

マーケターは、取引の成立に関して営業を支援できる情報を持っています。タスクを作成して、タスクの実行内容と実行タイミングを営業に知らせることができます。

![](assets/image2014-9-22-14-3a54-3a46.png)

>[!NOTE]
>
>Marketo 同期ユーザーがタスクを作成する場合、Salesforce でタスクを作成するには「**[!UICONTROL 期限]**」が必須フィールドです。この値がない場合、Marketo でデフォルトの 5 日が自動入力されます。

デフォルトでは、フローステップは次のようになります。

![](assets/image2014-9-22-14-3a54-3a49.png)

すべてのフィールドをカスタマイズして、目的のタスクを作成します。

![](assets/image2014-9-22-14-3a54-3a52.png)

>[!TIP]
>
>**[!UICONTROL 件名]**&#x200B;と&#x200B;**[!UICONTROL 説明]**&#x200B;で、`{{lead.tokens}}`、`{{company.tokens}}`、`{{campaign.tokens}}`、`{{system.tokens}}` を使用できます。詳しくは、[フローステップのトークン](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/flow-actions/use-tokens-in-flow-steps.md){target="_blank"}を参照してください。
