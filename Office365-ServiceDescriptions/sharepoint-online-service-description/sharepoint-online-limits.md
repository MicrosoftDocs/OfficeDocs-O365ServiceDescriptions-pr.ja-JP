---
title: SharePoint の制限
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 34c5d8a8-eec7-46ae-82c7-9e9bdbe39895
description: Microsoft 365 およびスタンドアロンプランの SharePoint の制限について説明します。
ms.openlocfilehash: 2028f85fdf2998956e9f14bdcac13cc7902fad7e
ms.sourcegitcommit: c04cc8422d648df216d6c4f8b869736c97fc861f
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/16/2020
ms.locfileid: "45154365"
---
# <a name="sharepoint-limits"></a>SharePoint の制限

Microsoft 365 の SharePoint のサービス制限について説明します。
  
## <a name="limits-by-plan"></a>プラン別制限 

|||||
|:-----|:-----|:-----|:-----|
|**機能** <br/> |**Microsoft 365 Business Basic または Business Premium** <br/> |**Microsoft 365 E3 または E5、Office 365 Enterprise E1、E3、E5、または SharePoint プラン1または2** <br/> | **Microsoft 365 F1 または F3、Office 365 Enterprise F3** <br/> |
|組織あたりの合計ストレージ <sup>1、2、6</sup> <br/> |1 TB および購入ライセンスあたり 10 GB <sup>3</sup>  <br/> |1 TB および購入ライセンスあたり 10 GB <sup>3</sup> <br/> |1 TB <sup>3</sup> <br/> |
|サイト (サイト コレクション) あたりの最大ストレージ <sup>4</sup><br/> |25 TB <br/> |25 TB <br/> |25 TB <sup>5</sup> <br/> |
|組織あたりのサイト (サイト コレクション)  <br/> |200 万 <sup>6</sup> <br/> |200 万 <sup>6</sup> <br/> |200 万<br/> |
|ユーザー数  <br/> |最大 300  <br/> |1 から 500,000<sup>7</sup> <br/> |1 から 500,000<sup>7</sup> <br/> |
   
<sup>1</sup> [組織の合計と使用可能なストレージを検索する方法について説明します](/sharepoint/manage-site-collection-storage-limits)。 SharePoint のストレージを追加で購入できる量に制限はありません。 「 [サブスクリプションの記憶域を変更する](/office365/admin/subscriptions-and-billing/add-storage-space)」を参照してください。 
<br/><sup>2</sup> ごみ箱を監視して定期的に空にすることをお勧めします。 使用されるストレージは、組織の合計ストレージの上限に含まれます。 
<br/> <sup>3</sup> Microsoft 365 サブスクリプションと Office 365 追加のファイル記憶域アドオンがある場合は、ストレージ容量が追加されます。 
<br/> <sup>4</sup> これは単一のサイトのストレージ (以前の「サイト コレクション」) の*制限*であり、各サイトに*提供*されるストレージの量ではありません。 この制限は、Office 365 グループ接続のチーム サイトと OneDrive を含むすべての種類のサイトに適用されます。 SharePoint 管理者は、[手動でストレージの下限を設定](/sharepoint/manage-site-collection-storage-limits#manage-individual-site-storage-limits)することができます。 
<br/> <sup>5</sup> 現場担当者は、SharePoint サイトを管理できません。 
<br/> <sup>6</sup> ライセンス ユーザーごとの OneDrive は含まれません。 
<br/> <sup>7</sup> ユーザー数が 500,000 を超える場合は、Microsoft の担当者にお問い合わせください。 
  
## <a name="service-limits-for-all-plans"></a>すべてのプランのサービスの制限

### <a name="items-in-lists-and-libraries"></a>リストとライブラリのアイテム

リストには最大 3,000 万個のアイテムを含めることができ、ライブラリには最大 3,000 万個のファイルとフォルダーを含めることができます。 リスト、ライブラリ、またはフォルダーに 100,000 を超えるアイテムが含まれている場合、リスト、ライブラリ、またはフォルダーの権限の継承を解除することはできません。 また、権限を再び継承することはできません。 ただし、リスト、ライブラリ、またはフォルダー内の個々のアイテムの継承は、リストまたはライブラリの固有権限の最大数まで解除できます (次のセクションを参照)。 大規模なリストを表示する場合のその他の制限の詳細については、「[Office 365 で大規模なリストとライブラリを管理する](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784)」を参照してください。 

> [!NOTE]
> 1 つのサイトで使用できるドキュメント ライブラリの数に制限はありません。

### <a name="unique-permissions-for-items-in-a-list-or-library"></a>リストまたはライブラリ内のアイテムに対する固有の権限

サポートされる制限は5万一意権限アイテムですが、推奨される一般的な制限は5000です。 一度に 5,000 を超える固有の権限のアイテムに変更を加えると、時間がかかります。 大きなリストの場合は、固有の権限ができるだけ少なくて済むように設計します。

もう1つの制限は、一意の権限 item ごとに5000の役割の割り当てです。 

### <a name="file-size-and-file-path-length"></a>ファイル サイズとファイル パスの長さ

100 GB リストアイテムの添付ファイルの最大サイズは 250 MB です。 新しい OneDrive 同期アプリ (OneDrive.exe) を使用する際の制限事項の詳細については、「[無効なファイル名とファイルの種類](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa)」を参照してください。

### <a name="moving-and-copying-across-sites"></a>サイト間の移動とコピー

1回の操作で複数のファイルをコピーまたは移動するには、次の3つの要件があります。 

- ファイルサイズの合計は 100 GB 以下 
- 3万を超えるファイル
- 各ファイルは 2 GB 未満である必要があります。

### <a name="sync"></a>同期

**新しい OneDrive 同期アプリ** - ファイル オンデマンドを使用して、またはライブラリ内で特定のフォルダーのみを選択して同期を行っている場合であっても、パフォーマンスを最適化するには、同期されているすべてのドキュメント ライブラリ全体で 300,000 アイテム以上のファイルを格納しないようにすることをお勧めします。

**以前の OneDrive for Business 同期アプリ (Groove.exe)** - 同期されているすべてのライブラリ全体で、最大 20,000 アイテムを同期できます。 これには、OneDrive ライブラリ、チーム サイト ライブラリ、またはその両方が含まれます。 全体での同期制限とは別に、ライブラリの種類ごとに同期できるアイテムの数に制限があります。

   - OneDrive ライブラリで同期できるのは、最大で 20,000 アイテムです。 これには、フォルダーとファイルが含まれます。 
   - SharePoint ライブラリで同期できるのは、最大で 5,000 アイテムです。 これには、フォルダーとファイルが含まれます。 これらはさまざまな SharePoint サイトにあるライブラリで、チーム サイトやコミュニティ サイト、他のユーザーが作成したライブラリ、またはサイト ページから作成したライブラリなどが含まれます。 複数の SharePoint ライブラリを同期することができます。 同期するチーム サイトはすべて、同期されるすべてのライブラリ全体での 20,000 アイテムの制限にカウントされます。

> [!NOTE]
> ユーザーが数十万ものファイルを含むドキュメント ライブラリ内のファイルを同期する必要がある場合、フォルダーのアクセス許可レベルを「制限付き読み取り」に設定することで、同期アプリに対してフォルダーを「非表示」にすることができます。 

### <a name="versions"></a>バージョン

50,000 のメジャー バージョンと 511 のマイナー バージョン。

### <a name="sharepoint-groups"></a>SharePoint グループ

ユーザーは 5,000 のグループに所属でき、各グループには最大 5,000 のユーザーを含めることができます。 サイト (サイト コレクション) あたり最大 10,000 グループを含めることができます。

> [!NOTE]
> Azure AD グループの制限は、パブリック グループ サイトとプライベート グループ サイトのメンバーシップの管理に影響する可能性がありますので、「[Azure AD サービスの制限と制約](/azure/active-directory/users-groups-roles/directory-service-limits-restrictions)」を参照してください。 

### <a name="managed-metadata"></a>管理メタデータ

用語ストアに 200,000 語、1000 グローバル用語セット、1000 グループ。

### <a name="overall-site-metadata"></a>サイト全体のメタデータ

サイトごとに 1000 GB (メタデータがこのサイズに達することはほとんどありません)。

### <a name="subsites"></a>サブサイト 

サイト (サイト コレクション) ごとに 2,000 個。 サブサイトを作成するのではなく、サイトを作成してハブに整理することをお勧めします。 サブサイトを使用する場合は、そのサブサイトの数を制限することをお勧めします (特にトラフィックの多いサイト)。

### <a name="sharepoint-hosted-applications"></a>SharePoint ホスト型アプリケーション

1 組織につき 20,000 インスタンス

### <a name="people-editing-a-document-at-the-same-time"></a>ドキュメントを同時に編集できるユーザー

99 人のユーザーが同時にドキュメントを開いて編集できます。 10 人以上が同時にドキュメントを編集すると、編集内容が競合しやすくなり、ユーザー エクスペリエンスが徐々に低下します。

### <a name="users"></a>ユーザー

サイト (サイト コレクション) ごとに 200 万人。
   
> [!NOTE]
> SharePoint サイトに招待できるゲストの数に制限はありません。 外部共有に関する詳細については、「[外部共有の概要](/sharepoint/external-sharing-overview)」を参照してください。

## <a name="see-also"></a>関連項目

[SharePoint の検索制限](/sharepoint/search-limits)
