---
title: SharePoint の制限
ms.author: sharik
author: skjerland
audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 34c5d8a8-eec7-46ae-82c7-9e9bdbe39895
description: Office 365 およびスタンドアロンプランの SharePoint の制限について説明します。
ms.openlocfilehash: 03cf3a792bb88d1a6c6d6048752fe2caaf695f35
ms.sourcegitcommit: 06d43eca33da7d747494beaa9847e98b99367b0d
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 02/26/2020
ms.locfileid: "42279870"
---
# <a name="sharepoint-limits"></a>SharePoint の制限

Microsoft 365 用の SharePoint のサービス制限について説明します。
  
## <a name="limits-by-plan"></a>プラン別制限 

|||||
|:-----|:-----|:-----|:-----|
|**機能** <br/> |**Office 365 Business Essentials または Business Premium** <br/> |**Office 365 Enterprise E1、E3、E5、または SharePoint プラン1または2** <br/> | **Office 365 Enterprise F1** <br/> |
|組織<sup>1、2、6の</sup>合計記憶域 <br/> |1 TB、購入したライセンスごとに 10 GB  <br/> |1 TB<sup>、購入し</sup>たライセンスごとに 10 GB <br/> |1 TB<sup>3</sup> <br/> |
|サイトごとの最大記憶域 (サイトコレクション)<sup>4</sup><br/> |25 TB <br/> |25 TB <br/> |25 TB<sup>5</sup> <br/> |
|組織ごとのサイト (サイトコレクション)  <br/> |200万<sup>6</sup> <br/> |200万<sup>6</sup> <br/> |200万<br/> |
|ユーザー数  <br/> |最大 300  <br/> |1 から 500,000<sup>7</sup> <br/> |1 から 500,000<sup>7</sup> <br/> |
   
<sup>1</sup> [組織で使用可能なストレージの合計を調べる方法について説明](/sharepoint/manage-site-collection-storage-limits)します。 追加の SharePoint ストレージを無制限に購入することができます。 「 [サブスクリプションの記憶域を変更する](/office365/admin/subscriptions-and-billing/add-storage-space)」を参照してください。 
<br/><sup>2</sup> ごみ箱を監視して定期的に空にすることをお勧めします。 使用する記憶領域は、組織の記憶域の合計の制限の一部です。 
<br/> <sup>3</sup> office 365 サブスクリプションと office 365 追加のファイル記憶域アドオンがある場合は、ストレージ容量が追加されます。 
<br/> <sup>4</sup>これは、サイトごとに*提供さ*れる記憶域の量ではなく、1つのサイト (旧称 "サイトコレクション") の記憶域の*制限*です。 この制限は、Office 365 グループに接続されたチームサイトと OneDrive を含むすべての種類のサイトに適用されます。 SharePoint 管理者は、[より低い記憶域制限を手動で設定](/sharepoint/manage-site-collection-storage-limits#manage-individual-site-storage-limits)できます。 
<br/> 第<sup>5</sup>行のワーカーは SharePoint サイトを管理できません。 
<br/> <sup>6</sup>ライセンスユーザーごとに作成された OneDrive は含まれません。 
<br/> <sup>7</sup> ユーザー数が 500,000 を超える場合は、Microsoft の担当者にお問い合わせください。 
  
## <a name="service-limits-for-all-plans"></a>すべてのプランのサービスの制限

### <a name="items-in-lists-and-libraries"></a>リストとライブラリ内のアイテム

リストには最大3000万個のアイテムを含めることができ、ライブラリには最大で3000万のファイルとフォルダーを含めることができます。 リスト、ライブラリ、またはフォルダーに10万個を超えるアイテムが含まれている場合、リスト、ライブラリ、またはフォルダーのアクセス許可の継承を解除することはできません。 また、アクセス許可を再度継承することもできません。 ただし、リスト、ライブラリ、またはフォルダー内の個々のアイテムに対して、リストまたはライブラリ内の固有のアクセス許可の最大数 (次のセクションを参照) で継承を解除することはできます。 大規模なリストを表示する場合のその他の制限の詳細については、「[Office 365 で大規模なリストとライブラリを管理する](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784)」を参照してください。 

> [!NOTE]
> サイトに含めることができるドキュメントライブラリの数に制限はありません。

### <a name="unique-permissions-for-items-in-a-list-or-library"></a>リストまたはライブラリ内のアイテムの固有の権限

サポートされる制限は5万ですが、推奨される一般的な制限は5000です。 5000を超える一意の権限アイテムに変更を加えると、時間がかかります。 大きなリストの場合は、固有の権限ができるだけ少なくて済むように設計します。

### <a name="file-size-and-file-path-length"></a>ファイルサイズとファイルパスの長さ

15 GB リストアイテムに添付されるファイルの最大サイズは 250 MB です。 新しい OneDrive 同期アプリ (OneDrive) を使用する際の制限と制限の詳細については、「[無効なファイル名とファイルの種類](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa)」を参照してください。

### <a name="moving-and-copying-across-sites"></a>サイト間での移動とコピー

操作ごとに 100 GB。 Web ブラウザーは開いたままにしておく必要があります。

### <a name="sync"></a>同期

**新しい OneDrive 同期アプリ**-最適なパフォーマンスを実現するために、すべての同期されたドキュメントライブラリに30万個を超えるファイルを保存しないことをお勧めします。

**以前の OneDrive for business 同期アプリ (Groove)** -同期されているすべてのライブラリで最大2万個のアイテムを同期できます。 これには、OneDrive ライブラリ、チームサイトライブラリ、またはその両方が含まれます。 全体的な同期制限とは別に、ライブラリの種類ごとに同期できるアイテムの数に制限があります。

   - OneDrive ライブラリでは、最大2万個のアイテムを同期することができます。 これには、フォルダーとファイルが含まれます。 
   - SharePoint ライブラリでは、最大5000個のアイテムを同期することができます。 これには、フォルダーとファイルが含まれます。 これらは、チームサイトやコミュニティサイト、他のユーザーが作成したライブラリ、サイトページから作成したライブラリなど、さまざまな SharePoint サイトで見つけたライブラリです。 複数の SharePoint ライブラリを同期することができます。 同期するすべてのチームサイトは、同期されたすべてのライブラリにわたる2万アイテム全体の制限についてもカウントします。

> [!NOTE]
> ユーザーが数十万のファイルが含まれるドキュメントライブラリ内のファイルを同期する必要がある場合は、フォルダーのアクセス許可レベルを "制限付き読み取り" に設定することによって、同期アプリからフォルダーを非表示にすることができます。 

### <a name="versions"></a>バージョン

5万メジャーバージョンと511マイナーバージョン。

### <a name="sharepoint-groups"></a>SharePoint グループ

ユーザーは5000グループに属することができ、各グループは最大5000ユーザーを持つことができます。 サイトごとに最大で1万グループを割り当てることができます (サイトコレクション)。

> [!NOTE]
> Azure AD グループの制限については、「 [AZURE ad サービスの制限と制限](/azure/active-directory/users-groups-roles/directory-service-limits-restrictions)」を参照してください。この制限によって、パブリックおよびプライベートグループサイトメンバーシップの管理に影響する可能性があります。 

### <a name="managed-metadata"></a>管理メタデータ

20万用語ストアの用語、1000グローバル用語セット、1000グループ。

### <a name="subsites"></a>サイト 

サイトごとに 2000 (サイトコレクション)。 サイトを作成して、サブサイトを作成するのではなくハブに編成することをお勧めします。 サブサイトを使用する場合は、それらの数を制限することをお勧めします (特に、ずらしサイトが大きい場合)。

### <a name="sharepoint-hosted-applications"></a>SharePoint でホストされるアプリケーション

組織ごとに2万インスタンス。

### <a name="people-editing-a-document-at-the-same-time"></a>ドキュメントを同時に編集しているユーザー

99ユーザーは同時に編集用にドキュメントを開くことができます。 10人を超えるユーザーが同時にドキュメントを編集すると、その編集が競合する可能性が高くなり、ユーザーの操作が徐々に低下します。

### <a name="users"></a>ユーザー

サイトごとに 200万 (サイトコレクション)。
   
> [!NOTE]
> SharePoint サイトに招待できるゲストの数に制限はありません。 外部共有の詳細については、「[外部共有の概要](/sharepoint/external-sharing-overview)」を参照してください。

## <a name="see-also"></a>関連項目

[SharePoint の検索の制限](/sharepoint/search-limits)
