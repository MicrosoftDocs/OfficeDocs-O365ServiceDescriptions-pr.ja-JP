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
ms.openlocfilehash: b5ba34d3a1ebd80d7833e09e70a76b57882ae6fd
ms.sourcegitcommit: 81ba764537d6bfb99fe6f96cdbd0c0ac1534cae1
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 01/24/2020
ms.locfileid: "41519198"
---
# <a name="sharepoint-online-limits"></a>SharePoint Online の制限

Office 365 プランと SharePoint Online スタンドアロン プランの場合の SharePoint の制限について説明します。
  
## <a name="limits-by-plan"></a>プラン別制限 

|||||
|:-----|:-----|:-----|:-----|
|**機能** <br/> |**Office 365 Business Essentials または Business Premium** <br/> |**Office 365 Enterprise E1、E3、または E5、または SharePoint Online Plan 1 または 2** <br/> | **Office 365 Enterprise F1** <br/> |
|組織<sup>1、2、6の</sup>合計記憶域 <br/> |1 TB、購入したライセンスごとに 10 GB  <br/> |1 TB<sup>、購入し</sup>たライセンスごとに 10 GB <br/> |1 TB<sup>3</sup> <br/> |
|サイトコレクション<sup>4</sup>あたりの最大記憶域<br/> |25 TB <br/> |25 TB <br/> |25 TB<sup>5</sup> <br/> |
|1 組織あたりのサイト コレクション  <br/> |200万<sup>6</sup> <br/> |200万<sup>6</sup> <br/> |200万<br/> |
|ユーザー数  <br/> |最大 300  <br/> |1 から 500,000<sup>7</sup> <br/> |1 から 500,000<sup>7</sup> <br/> |
   
<sup>1</sup> [組織で使用可能なストレージの合計を調べる方法について説明](/sharepoint/manage-site-collection-storage-limits)します。 追加の SharePoint ストレージを無制限に購入することができます。 「 [サブスクリプションの記憶域を変更する](/office365/admin/subscriptions-and-billing/add-storage-space)」を参照してください。 
<br/><sup>2</sup> ごみ箱を監視して定期的に空にすることをお勧めします。 使用する記憶領域は、組織の記憶域の合計の制限の一部です。 
<br/> <sup>3</sup> office 365 サブスクリプションと office 365 追加のファイル記憶域アドオンがある場合は、ストレージ容量が追加されます。 
<br/> <sup>4</sup>これは、サイトコレクションごとに提供される記憶域の量ではなく、1つのサイトコレクションの記憶域の制限です。 この制限は、Office 365 グループに接続されたチームサイトと OneDrive を含む、すべての種類のサイトコレクションに適用されます。 SharePoint 管理者は、[より低い記憶域制限を手動で設定](/sharepoint/manage-site-collection-storage-limits#manage-individual-site-storage-limits)できます。 
<br/> <sup>最初の</sup>1 行のワーカーは SharePoint サイトコレクションを管理できません。 
<br/> <sup>6</sup>ライセンスユーザーごとに作成された OneDrive は含まれません。 
<br/> <sup>7</sup> ユーザー数が 500,000 を超える場合は、Microsoft の担当者にお問い合わせください。 
  
## <a name="service-limits-for-all-plans"></a>すべてのプランのサービスの制限

- **リストとライブラリのアイテム** - リストには最大 3,000 万個のアイテムを含めることができ、ライブラリには最大 3,000 万個のファイルとフォルダーを含めることができます。 リスト、ライブラリ、またはフォルダーに10万アイテムが追加された後は、リスト、ライブラリ、またはフォルダーのアクセス許可の継承を変更することはできません。 大規模なリストを表示する場合のその他の制限の詳細については、「[Office 365 で大規模なリストとライブラリを管理する](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784)」を参照してください。 

- **ファイル サイズとファイル パスの長さ** - 15 GB。 リストアイテムに添付されるファイルの最大サイズは 250 MB です。 新しい OneDrive 同期クライアント (OneDrive) を使用する際の制限事項と制限の詳細については、「[無効なファイル名とファイルの種類](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa)」を参照してください。

- **サイト コレクション間の移動とコピー** – 1 操作あたり 100 GB。 Web ブラウザーは開いたままにしておく必要があります。

- **同期**-最適なパフォーマンスを実現するため、必要なファイルを使用している場合や、同期するライブラリ内の一部のフォルダーのみを選択している場合でも、すべての同期されたドキュメントライブラリに30万個を超えるファイルを保存することをお勧めします。

    以前の OneDrive for business 同期クライアント (Groove) を使用している場合は、同期されているすべてのライブラリで最大2万個のアイテムの合計を同期することができます。 これには、OneDrive for Business ライブラリ、チームサイトライブラリ、またはその両方が含まれます。 全体的な同期制限とは別に、各ライブラリの種類に対して同期できるアイテムの数に制限があります。
    - OneDrive for Business ライブラリでは、最大2万個のアイテムを同期することができます。 これには、フォルダーとファイルが含まれます。 
    - SharePoint ライブラリでは、最大5000個のアイテムを同期することができます。 これには、フォルダーとファイルが含まれます。 これらは、チームサイトやコミュニティサイト、他のユーザーが作成したライブラリ、サイトページから作成したライブラリなど、さまざまな SharePoint サイトで見つけたライブラリです。 複数の SharePoint ライブラリを同期することができます。 同期するすべてのチームサイトは、同期されたすべてのライブラリにわたる2万アイテム全体の制限についてもカウントします。

    > [!NOTE]
    > ユーザーが数十万のファイルが含まれるドキュメントライブラリ内のファイルを同期する必要がある場合は、フォルダーのアクセス許可レベルを "制限付き読み取り" に設定することによって、同期クライアントからフォルダーを非表示にすることができます。 

- **バージョン** - 50,000 のメジャー バージョンと 511 のマイナー バージョン。

- **SharePoint グループ** - ユーザーは 5,000 のグループに所属でき、各グループには最大 5,000 のユーザーを含めることができます。 サイト コレクションあたり最大 10,000 グループを含めることができます。
    > [!NOTE]
    > Azure AD グループの制限については、「 [AZURE ad サービスの制限と制限](https://docs.microsoft.com/azure/active-directory/users-groups-roles/directory-service-limits-restrictions)」を参照してください。この制限によって、パブリックおよびプライベートグループサイトメンバーシップの管理に影響する可能性があります。 
- **管理されたメタデータ** - 用語ストアに 200,000 語、1000 グローバル用語セット、1000 グループ。

- **サブ**サイト-サイトコレクションごとに2000。

- **SharePoint でホストされているアプリケーション** – 1 組織あたり 20,000 インスタンス。

- **リストまたはライブラリごとの固有のセキュリティスコープ**-サポートされる制限は5万ですが、推奨される一般的な制限は5000です。 5000より上では、アクセス制御リスト (ACL) サイズは重要です。 スコープは、サポートされている5万の制限に達するまで追加できますが、特に注意が必要なシナリオがない限り、Microsoft はお勧めしません。 大きなリストの場合は、固有の権限ができるだけ少なくて済むように設計します。

- **ユーザー** - サイト コレクションあたり 200 万。
    > [!NOTE]
    > SharePoint サイトコレクションに招待できるゲストの数に制限はありません。 外部共有の詳細については、「[外部共有の概要](https://docs.microsoft.com/sharepoint/external-sharing-overview)」を参照してください。
## <a name="see-also"></a>関連項目

[SharePoint Online の検索制限](https://docs.microsoft.com/sharepoint/search-limits)
