---
unique-page-id: 11382122
description: 監査証跡の有効化 - Marketo ドキュメント - 製品ドキュメント
title: 監査証跡の有効化
exl-id: 3ab2d7b2-1be1-4b3f-a9cc-d3edfa963679
feature: Audit Trail
source-git-commit: 431bd258f9a68bbb9df7acf043085578d3d91b1f
workflow-type: ht
source-wordcount: '245'
ht-degree: 100%

---

# 監査証跡の有効化 {#enable-audit-trail}

監査証跡は、すべてのお客様が使用でき、2 つの管理権限で管理されます。

>[!NOTE]
>
>デフォルトでは、すべてのシステム管理者のロールで、両方の権限が有効になっています。

## ロールの監査証跡を有効にする {#enable-audit-trail-for-a-role}

1. 「**[!UICONTROL 管理者]**」をクリックします。

   ![](assets/enable-audit-trail-1.png)

1. 「**[!UICONTROL ユーザー＆ロール]**」を選択し、「**[!UICONTROL ロール]**」をクリックします。

   ![](assets/enable-audit-trail-2.png)

1. 監査証跡を有効にするロールを選択し、「**[!UICONTROL ロールの編集]**」をクリックします。

   ![](assets/enable-audit-trail-3.png)

   >[!NOTE]
   >
   >また、新しいロールを作成したり、監査証跡アクセス権を付与したりするオプションも表示されます。

1. **[!UICONTROL 管理アクセス]**&#x200B;権限を展開します。必要に応じて、「**[!UICONTROL 監査証跡にアクセス]**」と「**[!UICONTROL ログイン履歴にアクセス]**」のいずれかまたは両方を選択します。「**[!UICONTROL 保存]**」をクリックします。

   ![](assets/enable-audit-trail-4.png)

   >[!NOTE]
   >
   >**定義**
   >
   >**[!UICONTROL 監査証跡にアクセス]** - [!UICONTROL アセット監査証跡]と[!UICONTROL 管理監査証跡]の両方にアクセスできるようにします。
   >
   >**[!UICONTROL ログイン履歴にアクセス]**：[ユーザーログイン履歴](/help/marketo/product-docs/administration/audit-trail/user-login-history.md)にアクセスできるようにします。

## 監査証跡のロールをユーザーに割り当てる {#assign-audit-trail-role-to-a-user}

>[!PREREQUISITES]
>
>ロールを[作成](/help/marketo/product-docs/administration/users-and-roles/create-delete-edit-and-change-a-user-role.md#create-a-role)するか、既存のロールを[有効](#enable-audit-trail)にして、監査証跡の権限を付与します。

1. **[!UICONTROL ユーザー＆ロール]**&#x200B;で、「**[!UICONTROL ユーザー]**」をクリックします。

   ![](assets/enable-audit-trail-5.png)

1. 監査証跡の権限を付与するユーザーを選択して、「**[!UICONTROL ユーザーを編集]**」をクリックします。

   ![](assets/enable-audit-trail-6.png)

   >[!NOTE]
   >
   >この手順は、新規ユーザーを作成している場合でも同様です。

1. 作成した監査証跡のロールを選択します。ここでは、「監査証跡 - アセットと管理」と「監査証跡 - ログイン履歴」を作成しています。

   ![](assets/enable-audit-trail-7.png)

   >[!CAUTION]
   >
   >ワークスペースを有効にしている場合は、必ずロールのチェックボックスを選択し、ワークスペースをすべて選択してください。個々のワークスペースの選択を解除すると、「監査証跡」が非表示になります。つまり、すべてのワークスペースの「監査証跡」データが表示されます。[フィルター](/help/marketo/product-docs/administration/audit-trail/filtering-in-audit-trail.md)を適用すると、ワークスペースを非表示にするオプションがあります。

1. 「**[!UICONTROL 保存]**」をクリックします。

   ![](assets/enable-audit-trail-8.png)
