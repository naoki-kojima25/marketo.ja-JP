---
unique-page-id: 4719312
description: 選択リスト値の追加／削除 - Marketo ドキュメント - 製品ドキュメント
title: 選択リスト値の追加／削除
exl-id: f1230c43-10cb-47ff-89d7-9f835b034db0
feature: Salesforce Integration
source-git-commit: 4045f262889d06304111288d30da893529396e81
workflow-type: tm+mt
source-wordcount: '228'
ht-degree: 89%

---

# 選択リスト値の追加／削除 {#add-remove-picklist-values}

次は、Salesforce で選択リストの値を追加および削除する方法について知っておく必要があることです。

## 選択リスト値の追加 {#adding-picklist-values}

1. Salesforce で選択リストフィールドタイプに値が追加された場合、影響を受けるフォームを特定した[通知](/help/marketo/product-docs/core-marketo-concepts/miscellaneous/understanding-notifications.md){target="_blank"}が届きます。

   ![](assets/image2015-1-21-14-3a4-3a7.png)

1. フォームエディターに移動し、洲推奨リストに[追加の値を追加](/help/marketo/product-docs/demand-generation/forms/form-actions/add-a-country-picklist-to-your-form.md){target="_blank"}します。

## 選択リスト値の削除 {#remove-picklist-values}

Salesforce のフィールドから選択リスト値が削除された場合、このフィールドをホストするすべてのフォームからこの値を手動で削除する必要があります。

>[!NOTE]
>
>Salesforce のリードフィールドと連絡先フィールドの値が異なる場合、共通の値はMarketo Engageで使用できます。

Salesforce のリードフィールドと連絡先フィールドの値が異なる場合：

1. SFDC で選択リストに値を追加すると、通知が届きます。
1. 通知には、使用箇所が示されます。これで、この新しい値を必要に応じてフォーム上のオプションとして追加できます。

SFDC リードの選択リストの値が SFDC 連絡先の選択リストと異なる場合は、共通の値がフォームのデフォルト値オプションとして使用されます。

値を選択リストから削除する場合は、フォームからオプションとして手動で削除する必要があります。
