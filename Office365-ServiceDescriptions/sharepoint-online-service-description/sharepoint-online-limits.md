---
title: SharePoint Online の制限
ms.author: sharik
author: skjerland
audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 34c5d8a8-eec7-46ae-82c7-9e9bdbe39895
description: Office 365 Enterprise プランとスタンドアロン プランの場合の SharePoint Online の制限について説明します。
ms.openlocfilehash: 4ec162de7b5e005a177d0eb2f2122ba46422519c
ms.sourcegitcommit: 0d63d969bf286c3ab2b297867713d41f485ccc07
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/18/2019
ms.locfileid: "37035103"
---
# <a name="sharepoint-online-limits"></a>SharePoint Online の制限 

Office 365 プランと SharePoint Online スタンドアロン プランの場合の SharePoint の制限について説明します。
  
## <a name="limits-by-plan"></a>プラン別制限 

|||||
|:-----|:-----|:-----|:-----|
|**機能** <br/> |**Office 365 Business Essentials または Business Premium** <br/> |**Office 365 Enterprise E1、E3、または E5、または SharePoint Online Plan 1 または 2** <br/> | **Office 365 Enterprise F1** <br/> |
|組織あたりの合計ストレージ <sup>1、2</sup> <br/> |1 TB および購入ライセンスあたり 10 GB  <br/> |1 TB および購入ライセンスあたり 10 GB <sup>3</sup> <br/> |1 TB <sup>3</sup> <br/> |
|サイト コレクションあたりの最大ストレージ <sup>4</sup><br/> |25 TB <br/> |25 TB <br/> |25 TB <sup>5</sup> <br/> |
|1 組織あたりのサイト コレクション  <br/> |100万 <sup>6</sup> <br/> |100万 <sup>6</sup> <br/> |100 万<br/> |
|ユーザー数  <br/> |最大 300  <br/> |1 から 500,000<sup>7</sup> <br/> |1 から 500,000<sup>7</sup> <br/> |
   
<sup>1</sup> SharePoint のストレージを追加で購入できる量に制限はありません。 「 [サブスクリプションの記憶域を変更する](https://docs.microsoft.com/office365/admin/subscriptions-and-billing/add-storage-space)」を参照してください。 
<br/><sup>2</sup> ごみ箱を監視して定期的に空にすることをお勧めします。 使用されるストレージは、組織の合計ストレージの上限に含まれます。 
<br/> <sup>3</sup> Office 365 サブスクリプション、および Office 365 Extra File Storage アドオンを持っている場合は、ストレージの量が追加されます。 
<br/> <sup>4</sup> これは単一のサイト コレクションのストレージの制限であり、各サイト コレクションに提供されるストレージの量ではありません。 この制限は、Office 365 グループ接続のチーム サイトと OneDrive を含むすべての種類のサイト コレクションに適用されます。 SharePoint 管理者は、[手動でストレージの下限を設定](https://docs.microsoft.com/sharepoint/manage-site-collection-storage-limits)することができます。 
<br/> <sup>5</sup> 現場担当者は、SharePoint サイト コレクションを管理できません。 
<br/> <sup>6</sup> ライセンス ユーザーごとの OneDrive は含まれません。 
<br/> <sup>7</sup> ユーザー数が 500,000 を超える場合は、Microsoft の担当者にお問い合わせください。 
  
## <a name="service-limits-for-all-plans"></a>すべてのプランのサービスの制限

- **リストとライブラリのアイテム** - リストには最大 3,000 万個のアイテムを含めることができ、ライブラリには最大 3,000 万個のファイルとフォルダーを含めることができます。 リスト、ライブラリ、またはフォルダーに 10 万のアイテムを追加した後は、リスト、ライブラリ、またはフォルダーのアクセス許可の継承は変更できません。 大規模なリストを表示する場合のその他の制限の詳細については、「[Office 365 で大規模なリストとライブラリを管理する](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784)」を参照してください。 

- **ファイル サイズとファイル パスの長さ** - 15 GB。 リストアイテムの添付ファイルの最大サイズは 250 MB です。 新しい OneDrive 同期クライアント (OneDrive.exe) を使用する際の制限事項の詳細については、「[無効なファイル名とファイルの種類](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa)」を参照してください。

- **サイト コレクション間の移動とコピー** – 1 操作あたり 100 GB。 Web ブラウザーは開いたままにしておく必要があります。

- **同期** - ファイル オンデマンドを使用して、またはライブラリ内で特定のフォルダーのみを選択して同期を行っている場合であっても、パフォーマンスを最適化するには、同期されているすべてのドキュメント ライブラリ全体で 300,000 アイテム以上のファイルを格納しないようにすることをお勧めします。

    以前の OneDrive for Business 同期クライアント (Groove.exe) を使用している場合、同期されているすべてのライブラリ全体で、最大 20,000 万アイテムを同期できます。 これには、OneDrive for Business ライブラリ、チーム サイト ライブラリ、またはその両方が含まれます。 全体での同期制限とは別に、ライブラリの種類ごとに同期できるアイテムの数に制限があります。
    - OneDrive for Business ライブラリで同期できるのは、最大で 20,000 万アイテムです。 これには、フォルダーとファイルが含まれます。 
    - SharePoint ライブラリで同期できるのは、最大で 5,000 アイテムです。 これには、フォルダーとファイルが含まれます。 これらはさまざまな SharePoint サイトにあるライブラリで、チーム サイトやコミュニティ サイト、他のユーザーが作成したライブラリ、またはサイト ページから作成したライブラリなどが含まれます。 複数の SharePoint ライブラリを同期することができます。 同期するチーム サイトはすべて、同期されるすべてのライブラリ全体での 20,000 万アイテムの制限にカウントされます。

    > [!NOTE]
    > ユーザーが数十万ものファイルを含むドキュメント ライブラリ内のファイルを同期する必要がある場合、フォルダーのアクセス許可レベルを「制限付き読み取り」に設定することで、同期クライアントに対してフォルダーを「非表示」にすることができます。 

- **バージョン** - 50,000 のメジャー バージョンと 511 のマイナー バージョン。

- **SharePoint グループ** - ユーザーは 5,000 のグループに所属でき、各グループには最大 5,000 のユーザーを含めることができます。 サイト コレクションあたり最大 10,000 グループを含めることができます。
    > [!NOTE]
    > Azure AD グループの制限は、パブリック グループ サイトとプライベート グループ サイトのメンバーシップの管理に影響する可能性がありますので、「[Azure AD サービスの制限と制約](https://docs.microsoft.com/azure/active-directory/users-groups-roles/directory-service-limits-restrictions)」を参照してください。 
- **管理されたメタデータ** - 用語ストアに 200,000 語、1,000 グローバル用語セット、1,000 グループ。

- **サブサイト** - サイト コレクションあたり 2,000。

- **SharePoint でホストされているアプリケーション** – 1 組織あたり 20,000 インスタンス。

- **リストまたはライブラリあたりの固有のセキュリティ スコープ** - 5,000。 大きなリストの場合は、固有の権限ができるだけ少なくて済むように設計します。

- **ユーザー** - サイト コレクションあたり 200 万。
    > [!NOTE]
    > SharePoint サイト コレクションに招待できるゲストの数に制限はありません。 外部共有に関する詳細については、「[外部共有の概要](https://docs.microsoft.com/sharepoint/external-sharing-overview)」を参照してください。
## <a name="see-also"></a>関連項目

[SharePoint Online の検索制限](https://docs.microsoft.com/sharepoint/search-limits)
