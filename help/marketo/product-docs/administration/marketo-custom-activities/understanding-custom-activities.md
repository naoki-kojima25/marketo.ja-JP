---
unique-page-id: 10100266
description: カスタムアクティビティについて - Marketo ドキュメント - 製品ドキュメント
title: カスタムアクティビティについて
exl-id: 0bb74d9d-3a9d-4ef7-8c8c-2de36cd6190b
feature: Custom Activities
source-git-commit: 2b610cc3486b745212b0b1f36018a83214d7ecd7
workflow-type: tm+mt
source-wordcount: '259'
ht-degree: 99%

---

# カスタムアクティビティについて {#understanding-custom-activities}

リードが実行したアクションを、ビジネスに特化したカスタムアクティビティとしてトラックできます。

**アクティビティとは**

ユーザーが組織とやり取りする方法はいくつかあります。企業の web サイトを訪問する、展示会に参加する、受け取ったメールのリンクをクリックするなどが考えられます。こうしたアクションがアクティビティです。どのようなアクションも Marketo で取得されるので、マーケティングチームはタイムリーで適切な内容の情報をどのように送信すればよいか、深く理解することができます。

**カスタムアクティビティ**

カスタムアクティビティは、Marketo のフォームやメール、ランディングページに関連していないアクティビティをトラックするときに便利です。例えば、いつ現金を預けたのかをトラックしたい場合には、カスタムアクティビティを使用します。いつウェビナーへ参加したのかを記録したい場合も、カスタムアクティビティを使用します。

>[!NOTE]
>
>カスタムアクティビティは、カスタムオブジェクトとは異なります。値が変化する（例えば、「車の色」が青から赤に変化する）場合は、カスタムオブジェクトを使用します。発生するタイミングをトラックする際に詳細が変わらない場合（例えば、「購入した車」）は、カスタムアクティビティを使用します。

**フィールド**：アクティビティに関連付けたい[フィールドを追加](/help/marketo/product-docs/administration/marketo-custom-activities/add-edit-delete-marketo-custom-activity-fields.md)することもできます。プライマリフィールドと同じように、スマートリストを絞り込む基準として使用できます。

**開始方法**

カスタムアクティビティは、標準のアクティビティと同じように機能します。ただし、設定は 2 つの手順で行います。

手順 1：[Marketo アカウントでカスタムアクティビティ](/help/marketo/product-docs/administration/marketo-custom-activities/create-a-custom-activity.md)を作成します。

手順 2：アドビの API を使用している組織の従業員が実装を開始します。詳しくは、[カスタムアクティビティの API](https://developer.adobe.com/marketo-apis/api/mapi/#tag/Activities/operation/addCustomActivityUsingPOST) を参照してください。

お楽しみください。
