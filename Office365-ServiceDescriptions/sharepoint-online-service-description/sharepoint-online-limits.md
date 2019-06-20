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
ms.openlocfilehash: dffe3f3ddbc68e286ce03d79e72e56e4fd3322b2
ms.sourcegitcommit: 7a67ef94d2f9101a7f9d8989bfd5013bc89dce00
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 06/07/2019
ms.locfileid: "34780666"
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

- **リストとライブラリのアイテム** - リストには最大 3,000 万個のアイテムを含めることができ、ライブラリには最大 3,000 万個のファイルとフォルダーを含めることができます。 リスト、ライブラリ、またはフォルダーに 10 万のアイテムを追加した後は、リスト、ライブラリ、またはフォルダーのアクセス許可の継承は変更できません。 大規模なリストを表示する場合のその他の制限の詳細については、「[Office 365 で大規模なリストとライブラリを管理する](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784)」を参照してください。 ファイル名で使用できない文字については、「[無効なファイル名またはフォルダー名の文字](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa)」を参照してください。

- **ファイル サイズとファイル パスの長さ** - 15 GB。 新しい OneDrive 同期クライアント (OneDrive.exe) を使用する際の制限事項の詳細については、「[OneDrive、OneDrive for Business、および SharePoint で無効なファイル名とファイルの種類](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa)」を参照してください。

- **サイト コレクション間の移動とコピー** – 1 操作あたり 100 GB。 Web ブラウザーは開いたままにしておく必要があります。

- **同期** - 最適なパフォーマンスを実現するために、ファイルのオンデマンドを使用している場合、またはライブラリ内の一部のフォルダーのみを同期対象として選択している場合でも、すべての同期済みドキュメント ライブラリにわたって 30 万以下のファイルを保存することをお勧めします。以前の OneDrive for Business 同期クライアント (Groove.exe) を使用している場合、ライブラリあたりの同期制限は 20,000 アイテム (チーム サイトあたり 5,000 アイテムを含む) です。

    > [!NOTE]
    > ユーザーが数十万ものファイルを含むドキュメント ライブラリ内のファイルを同期する必要がある場合、フォルダーのアクセス許可レベルを「制限付き読み取り」に設定することで、同期クライアントからフォルダーを「非表示」にすることができます。 

- **バージョン** - 50,000 のメジャー バージョンと 511 のマイナー バージョン。

- **SharePoint グループ** - ユーザーは 5,000 のグループに所属でき、各グループには最大 5,000 のユーザーを含めることができます。 サイト コレクションあたり最大 10,000 グループを含めることができます。

- **管理されたメタデータ** - 用語ストアに 200,000 語、1000 グローバル用語セット、1000 グループ。

- **サブサイト** - サイト コレクションあたり 2,000。

- **SharePoint でホストされているアプリケーション** – 1 組織あたり 20,000 インスタンス。

- **リストまたはライブラリあたりの固有のセキュリティ スコープ** - 5,000。 大きなリストの場合は、固有の権限ができるだけ少なくて済むように設計します。

- **ユーザー** - サイト コレクションあたり 200 万。

> [!NOTE]
> SharePoint サイト コレクションに招待できるゲストの数に制限はありません。 外部共有に関する詳細については、「[外部共有の概要](https://docs.microsoft.com/sharepoint/external-sharing-overview)」を参照してください。

## <a name="see-also"></a>関連項目

[SharePoint Online の検索制限](https://docs.microsoft.com/sharepoint/search-limits)
