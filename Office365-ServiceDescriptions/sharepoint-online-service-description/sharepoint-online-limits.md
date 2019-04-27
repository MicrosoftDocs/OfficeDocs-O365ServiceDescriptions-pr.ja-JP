---
title: SharePoint Online の制限
ms.author: sharik
author: skjerland
ms.audience: ITPro
ms.topic: article
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 34c5d8a8-eec7-46ae-82c7-9e9bdbe39895
description: Office 365 Enterprise プランとスタンドアロン プランの場合の SharePoint Online の制限について説明します。
ms.openlocfilehash: 4615eeefe2f9f172a5baa43ce3a506015bfe159e
ms.sourcegitcommit: 2b88e04bd6850094e7dc21e61d52a46016fa6617
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/27/2019
ms.locfileid: "33368370"
---
# <a name="sharepoint-online-limits"></a>SharePoint Online の制限

Office 365 プランと SharePoint Online スタンドアロン プランの場合の SharePoint の制限について説明します。
  
## <a name="limits-by-plan"></a>プラン別制限

|||||
|:-----|:-----|:-----|:-----|
|**機能** <br/> |**Office 365 Business Essentials または Business Premium** <br/> |**Office 365 Enterprise E1、E3、または E5、または SharePoint Online Plan 1 または 2** <br/> | **Office 365 Enterprise F1** <br/> |
|記憶域<sup>1、2</sup> <br/> |1 組織につき 1 TB、さらに購入したライセンスごとに 10 GB  <br/> |1 組織につき 1 TB、さらに購入したライセンスごとに 10 GB<sup>3</sup> <br/> |1 組織につき 1 TB <sup>3</sup> <br/> |
|サイト コレクションの記憶域  <br/> |サイト コレクションまたはグループにつき最大 25 TB<sup>4</sup> <br/> |サイト コレクションまたはグループにつき最大 25 TB<sup>4</sup> <br/> |サイト コレクションまたはグループにつき最大 25 TB<sup>5</sup> <br/> |
|1 組織あたりのサイト コレクション  <br/> |500,000<sup>6</sup> <br/> |500,000<sup>6</sup> <br/> |500,000<br/> |
|ユーザー数  <br/> |最大 300  <br/> |1 から 500,000<sup>7</sup> <br/> |1 から 500,000<sup>7</sup> <br/> |
   
> [!NOTE]
> <sup>1</sup> SharePoint Online の記憶域を追加で購入できる量に制限はありません。 「 [サブスクリプションの記憶域を変更する](https://support.office.com/article/96EA3533-DE64-4B01-839A-C560875A662C)」を参照してください。 
<br/><sup>2</sup> ごみ箱を監視して定期的に空にすることをお勧めします。 使用される記憶領域は、組織の合計ファイル容量の上限に含まれます。 
<br/> <sup>3</sup> Office 365 サブスクリプションと SharePoint Online スタンドアロン プランを持っている場合は、ストレージ容量が追加されます。 <br/><sup>4</sup> SharePoint Online 管理者は、サイト コレクションとサイトの容量の上限を設定できます。 <br/> <sup>5</sup> Kiosk ワーカーは、SharePoint Online サイト コレクションを管理できません。 Kiosk サイト コレクションを管理するには、少なくとも 1 つの Enterprise ユーザーのライセンスが必要です。 
<br/> <sup>6</sup> ライセンス ユーザーごとの OneDrive for Business サイト コレクションは含まれません。 <br/><sup>7</sup> ユーザー数が 500,000 を超える場合は、Microsoft の担当者にお問い合わせください。 
  

  
## <a name="service-limits-for-all-plans"></a>すべてのプランのサービスの制限

- **リストとライブラリのアイテム** - リストには最大 3,000 万個のアイテムを含めることができ、ライブラリには最大 3,000 万個のファイルとフォルダーを含めることができます。 100を超えると、リスト、ライブラリ、またはフォルダーに、アイテムが追加され、リスト、ライブラリ、またはフォルダーのアクセス許可の継承が変更できなくなります。 大規模なリストを表示する場合のその他の制限の詳細については、「[Office 365 で大規模なリストとライブラリを管理する](https://support.office.com/article/b4038448-ec0e-49b7-b853-679d3d8fb784)」を参照してください。 ファイル名で使用できない文字については、「[無効なファイル名またはフォルダー名の文字](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa)」を参照してください。

- **ファイル サイズとファイル パスの長さ** - 15 GB。 新しい OneDrive 同期クライアント (OneDrive.exe) を使用する際の制限事項の詳細については、「[OneDrive、OneDrive for Business、および SharePoint で無効なファイル名とファイルの種類](https://support.office.com/article/64883a5d-228e-48f5-b3d2-eb39e07630fa)」を参照してください。

- **サイト コレクション間の移動とコピー** – 1 操作あたり 100 GB。 Web ブラウザーは開いたままにしておく必要があります。

- **同期** - 最適なパフォーマンスを得るには、1 つの OneDrive またはチーム サイト ライブラリのファイルを 300,000 個以下にすることをお勧めします。 SharePoint Online では、ライブラリごとに 3,000 万個のドキュメントを保存できますが、最適なパフォーマンスを得るには、すべてのドキュメント ライブラリで同期するファイルを 300,000 個以下にすることをお勧めします。 また、そのようなライブラリのすべてのアイテムを同期していなくても、同期しているライブラリ全体で 300,000 個以上のアイテムがあれば、同様のパフォーマンスの問題が発生する可能性があります。 以前の OneDrive for Business 同期クライアント (Groove.exe) を使用している場合、ライブラリあたりの同期制限は 20,000 アイテム (チーム サイトあたり 5,000 アイテムを含む) です。

- **バージョン** - 50,000 のメジャー バージョンと 511 のマイナー バージョン。

- **SharePoint グループ** - ユーザーは 5,000 のグループに所属でき、各グループには最大 5,000 のユーザーを含めることができます。 サイト コレクションあたり最大 10,000 グループを含めることができます。

- **管理されたメタデータ** - 用語ストアに 200,000 語、1000 グローバル用語セット、1000 グループ。

- **サブサイト** - サイト コレクションあたり最大 2,000。

- **SharePoint でホストされているアプリケーション** – 1 組織あたり 20,000 インスタンス。

- **リストまたはライブラリあたりの固有のセキュリティ スコープ** - 5,000。 大きなリストの場合は、固有の権限ができるだけ少なくて済むように設計します。

- **ユーザー** - サイト コレクションあたり 200 万。

> [!NOTE]
> SharePoint Online サイト コレクションに招待できる外部ユーザー数に制限はありません。 詳細については、「[SharePoint Online 環境の外部共有を管理する](/sharepoint/external-sharing-overview)」を参照してください。

## <a name="see-also"></a>関連項目

[SharePoint Online の検索制限](/sharepoint/search-limits)
