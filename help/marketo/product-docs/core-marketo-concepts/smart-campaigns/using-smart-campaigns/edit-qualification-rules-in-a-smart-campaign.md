---
unique-page-id: 1146974
description: スマートキャンペーンでのクオリフィケーションルールの編集 - Marketo ドキュメント - 製品ドキュメント
title: スマートキャンペーンでのクオリフィケーションルールの編集
exl-id: 8b016fe4-8caf-4266-9f8f-2b05dae78cff
feature: Smart Campaigns
source-git-commit: fec5219c599c805328d77797d2636e549e489ca5
workflow-type: tm+mt
source-wordcount: '212'
ht-degree: 57%

---

# スマートキャンペーンでのクオリフィケーションルールの編集 {#edit-qualification-rules-in-a-smart-campaign}

クオリフィケーションルールは、スマートキャンペーンのフローを何回実行できるかを制御します。 デフォルトでは、スマートキャンペーンを複数回トリガーした場合でも、フローを介して送信されるのは 1 回のみです。 これらの設定の変更方法を次に示します。

1. スマートキャンペーンで、「**[!UICONTROL スケジュール]**」タブをクリックし、「**[!UICONTROL 設定を編集]**」をクリックします。

   ![](assets/edit-qualification-rules-in-a-smart-campaign-1.png)

   >[!TIP]
   >
   >また、「スマートキャンペーン設定」の右にある「**[!UICONTROL 編集]**」をクリックすることもできます。

1. スマートキャンペーンフローで担当者を実行する頻度を選択してください： **[!UICONTROL 1 回のみ]**, **[!UICONTROL 毎回]**&#x200B;または **毎日 1 回**/**週**/**か月**.

   ![](assets/edit-qualification-rules-in-a-smart-campaign-2.png)

   >[!NOTE]
   >
   >ルールを毎日 1 回に設定すると、Marketo はそのルールを時間に変換します。例えば、ルールを 1 日に 1 回に設定し、日曜日の夜の午後 10 時に人物が条件を満たした場合、月曜日の夜の午後 10 時まで再度条件を満たすことはできません。このロジックは、週や月を使用する場合にも適用されます。1 か月は常に 30 日とカウントされます。

   >[!NOTE]
   >
   >デフォルトでは、スマートキャンペーンに通信制限は適用されません。 方法を学ぶ [スマートキャンペーンへの通信制限の適用](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/using-smart-campaigns/apply-communication-limits-to-smart-campaign.md){target="_blank"}.

   >[!NOTE]
   >
   >[スマートキャンペーンへの通信制限の適用](/help/marketo/product-docs/core-marketo-concepts/smart-campaigns/using-smart-campaigns/apply-communication-limits-to-smart-campaign.md){target="_blank"}

ミッション完了です。これで、スマートキャンペーンでの選定ルールの制御方法がわかりました。
