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
description: Office 365 およびスタンドアロン プランの SharePoint の制限について説明します。
ms.openlocfilehash: 4b544803132d212dc3db01c6b0fbf18193f9fb3d
ms.sourcegitcommit: dc98fc886827d7ecc3af8ecd2ec567335bced117
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/31/2021
ms.locfileid: "51484780"
---
# <a name="sharepoint-limits"></a>SharePoint の制限

Microsoft 365 の SharePoint のサービス制限について説明します。
  
## <a name="limits-by-plan"></a>プラン別制限 

| 機能 | Microsoft 365 Business Basic、Business Standard、Business Premium | Microsoft 365 E3 または E5、 Office 365 E1、 E3, または E5 または SharePoint Plan 1 または 2 | Microsoft 365 F1 または F3、Office 365 F3 |
|:-----|:-----|:-----|:-----|
|組織あたりの合計ストレージ <sup>1、2、6</sup> <br/> |1 TB および購入ライセンスあたり 10 GB <sup>3</sup>  <br/> |1 TB および購入ライセンスあたり 10 GB <sup>3</sup> <br/> |1 TB <sup>3</sup> <br/> |
|サイト (サイト コレクション) あたりの最大ストレージ <sup>4</sup><br/> |25 TB <br/> |25 TB <br/> |25 TB <sup>5</sup> <br/> |
|組織あたりのサイト (サイト コレクション)  <br/> |200 万 <sup>6</sup> <br/> |200 万 <sup>6</sup> <br/> |200 万<br/> |
|ユーザー数  <br/> |最大 300  <br/> |1 から 500,000<sup>7</sup> <br/> |1 から 500,000<sup>7</sup> <br/> |
   
<sup>1</sup> [組織の合計と使用可能なストレージを検索する方法について説明します](/sharepoint/manage-site-collection-storage-limits)。 SharePoint のストレージを追加で購入できる量に制限はありません。 「 [サブスクリプションの記憶域を追加する」を参照してください](/office365/admin/subscriptions-and-billing/add-storage-space)。 
<br/><sup>2</sup> ごみ箱を監視して定期的に空にすることをお勧めします。 使用されるストレージは、組織の合計ストレージの上限に含まれます。 
<br/> <sup>3</sup> Office 365 サブスクリプション、および Office 365 Extra File Storage アドオンを持っている場合は、ストレージの量が追加されます。 
<br/> <sup>4</sup> これは単一のサイトのストレージ (以前の「サイト コレクション」) の *制限* であり、各サイトに *提供* されるストレージの量ではありません。 この制限は、Office 365 グループ接続のチーム サイトと OneDrive を含むすべての種類のサイトに適用されます。 SharePoint 管理者は、[手動でストレージの下限を設定](/sharepoint/manage-site-collection-storage-limits#manage-individual-site-storage-limits)することができます。 
<br/> <sup>5</sup> 現場担当者は、SharePoint サイトを管理できません。 
<br/> <sup>6</sup> ライセンス ユーザーごとの OneDrive は含まれません。 
<br/> <sup>7</sup> ユーザー数が 500,000 を超える場合は、Microsoft の担当者にお問い合わせください。 
  
## <a name="service-limits-for-all-plans"></a>すべてのプランのサービスの制限

### <a name="items-in-lists-and-libraries"></a>リストとライブラリのアイテム

リストには最大 3,000 万個のアイテムを含めることができ、ライブラリには最大 3,000 万個のファイルとフォルダーを含めることができます。 リスト、ライブラリ、またはフォルダーに 100,000 を超えるアイテムが含まれている場合、リスト、ライブラリ、またはフォルダーの権限の継承を解除することはできません。 また、権限を再び継承することはできません。 ただし、リスト、ライブラリ、またはフォルダー内の個々のアイテムの継承は、リストまたはライブラリの固有権限の最大数まで解除できます (次のセクションを参照)。 大規模なリストを表示する場合のその他の制限の詳細については、「[Office 365 で大規模なリストとライブラリを管理する](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784)」を参照してください。

### <a name="unique-security-scopes-per-list-or-library"></a>リストまたはライブラリごとの一意のセキュリティ スコープ

大規模なリストの場合、一意のアクセス許可をできる限り少なくし、合計で 5,000 を下回るままに設計します。

### <a name="file-size-and-file-path-length"></a>ファイル サイズとファイル パスの長さ

250 GB。 新しい OneDrive 同期アプリ (OneDrive.exe) を使用する際の制限事項の詳細については、「[無効なファイル名とファイルの種類](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa)」を参照してください。

### <a name="moving-and-copying-across-sites"></a>サイト間の移動とコピー

1回の操作で複数のファイルをコピーまたは移動するには、次の3つの要件があります。

- ファイルの合計サイズで 100 GB を超えることはできない
- 30,000 ファイル未満。
- 各ファイルは 15 GB 未満である必要があります

### <a name="sync"></a>同期

最適なパフォーマンスを得る場合は、1 つの OneDrive またはチーム サイト ライブラリに 300,000 を超えるファイルを保存することをお勧めします。 SharePoint Online では、ライブラリごとに 3,000 万個のドキュメントを保存できますが、最適なパフォーマンスを得るには、すべてのドキュメント ライブラリで同期するファイルを 300,000 個以下にすることをお勧めします。 また、そのようなライブラリのすべてのアイテムを同期していなくても、同期しているライブラリ全体で 300,000 個以上のアイテムがあれば、同様のパフォーマンスの問題が発生する可能性があります。 以前の OneDrive for Business 同期クライアント (Groove.exe) を使用している場合、ライブラリあたりの同期制限は 20,000 アイテム (チーム サイトあたり 5,000 アイテムを含む) です。

### <a name="versions"></a>バージョン

50,000 のメジャー バージョンと 511 のマイナー バージョン。

### <a name="sharepoint-groups"></a>SharePoint グループ

ユーザーはサイトごとに (サイト コレクション) 5,000 のグループに所属でき、各グループには最大 5,000 のユーザーを含めることができます。 サイト (サイト コレクション) あたり最大 10,000 グループを含めることができます。

> [!NOTE]
> Azure AD グループの制限は、パブリック グループ サイトとプライベート グループ サイトのメンバーシップの管理に影響する可能性がありますので、「[Azure AD サービスの制限と制約](/azure/active-directory/users-groups-roles/directory-service-limits-restrictions)」を参照してください。

### <a name="managed-metadata"></a>管理メタデータ

用語ストアに 200,000 語、1000 グローバル用語セット、1000 グループ。

### <a name="overall-site-metadata"></a>全体的なサイトのメタデータ

サイトあたり 1000 GB (メタデータはこのサイズに達することがめったにありません)。

### <a name="subsites"></a>サブサイト

サイト (サイト コレクション) ごとに 2,000 個。 サブサイトを作成するのではなく、サイトを作成してハブに整理することをお勧めします。 サブサイトを使用する場合は、そのサブサイトの数を制限することをお勧めします (特にトラフィックの多いサイト)。

> [!NOTE]
> 組織は、2000 hub サイト数に制限されています。 あらゆる機能にハブサイトは必要ないかもしれません。また、ハブを作成する前にいくらか計画することが重要です。 詳細については、「[SharePoint hub のサイトを計画する](/sharepoint/planning-hub-sites)」を参照してください。

### <a name="sharepoint-hosted-applications"></a>SharePoint ホスト型アプリケーション

1 組織につき 20,000 インスタンス

### <a name="users"></a>ユーザー

サイト コレクションあたり 200 万。

> [!NOTE]
> SharePoint サイトに招待できるゲストの数に明確な制限はありません。 外部共有に関する詳細については、「[外部共有の概要](/sharepoint/external-sharing-overview)」を参照してください。

## <a name="see-also"></a>関連項目

[SharePoint の検索制限](/sharepoint/search-limits)