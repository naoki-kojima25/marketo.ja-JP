---
unique-page-id: 2953467
description: SFDC の同期 - 商談の同期 - Marketo ドキュメント - 製品ドキュメント
title: SFDC の同期 - 商談の同期
exl-id: f8acc528-c631-43f0-8899-2f3c6fdabe9e
feature: Salesforce Integration
source-git-commit: 0087a5e88b8bd9601875f68a2e7cadeebdb5d682
workflow-type: tm+mt
source-wordcount: '292'
ht-degree: 93%

---

# SFDC 同期：商談の同期 {#sfdc-sync-opportunity-sync}

## 2 つのシステム間で商談の詳細を同期させる方法を教えてください。 {#how-are-opportunity-details-kept-in-sync-between-the-two-systems}

同期は、Salesforce からMarketo Engageへの 1 つの方法です。 Salesforce での商談のアップデートは、Marketo に同期されます。

>[!NOTE]
>
>[Salesforce 用に Marketo で入力した資格情報](/help/marketo/product-docs/crm-sync/salesforce-sync/setup/enterprise-unlimited-edition/step-2-of-3-create-a-salesforce-user-for-marketo-enterprise-unlimited.md){target="_blank"}は、データの同期に使用されます。その資格情報でアクセスできるデータのみが含まれます。

## 商談の同期を開始できますか？ {#can-i-initiate-an-opportunity-sync}

いいえ、できません。Salesforce での商談に対する変更は、Marketo に自動的に同期されます。

## Marketo は、商談額で複数の通貨をサポートしていますか。 {#does-marketo-support-more-than-one-currency-in-the-opportunity-amount}

いいえ。Marketo では 1 つの通貨のみをサポートしています。商談額は Salesforce から同期されますが、通貨は Marketo サブスクリプションの[デフォルトの通貨](/help/marketo/product-docs/administration/settings/set-default-location-settings-for-a-subscription.md#set-the-default-currency-settings-for-a-subscription){target="_blank"}になります。

## Marketo は商談額と取引先責任者をどのように関連付けますか？ {#how-does-marketo-associate-opportunities-and-contacts}

Marketoは次を使用して商談と連絡先を関連付けます： [オポチュニティ連絡先の役割](https://help.salesforce.com/HTViewHelpDoc?id=contactroles.htm){target="_blank"}. 取引先責任者のロールが割り当てられていない商談は、Marketo に同期されますが、誰にも属していません。例えば、「Has Opportunity」フィルターは認定されません。

## ユーザのすべての商談を表示するにはどうすればいいですか。 {#how-can-i-see-all-the-opportunities-of-a-person}

商談のリストは、[個人の詳細](/help/marketo/product-docs/core-marketo-concepts/smart-lists-and-static-lists/managing-people-in-smart-lists/using-the-person-detail-page.md){target="_blank"}ページの「**商談情報**」タブで表示できます。

## 商談に関連するトリガー／フィルターは何ですか。 {#what-are-the-triggers-filters-related-to-opportunity}

トリガー：

* 商談に追加
* 商談から削除
* 商談のアップデート

フィルター：

* 商談あり
* 商談がアップデートされた／されなかった
* 商談に追加された／されなかった
* 商談から削除された／されなかった
* 合計商談額
* 商談数
* 商談の合計収益予測

>[!TIP]
>
>フィルターとトリガーの制約を確認してください。そこには、たくさんの素晴らしい詳細があります。
>
>Salesforce の商談オブジェクトに新しいフィールドを作成するだけで、自動的に制約になります。
