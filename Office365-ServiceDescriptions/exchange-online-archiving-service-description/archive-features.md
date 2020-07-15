---
title: Exchange Online アーカイブのアーカイブ機能
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- archive-features-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 38abfbd2-5aaa-444a-a431-5e71c566f3e4
description: 次のセクションでは、Microsoft Exchange Online アーカイブのアーカイブ機能について説明します。
ms.openlocfilehash: 7f6b5863d94862644fb90d1d0d85c3765ad05e9b
ms.sourcegitcommit: d2cd67e52dd646b68bfbfd8a387e70a6da140a62
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/14/2020
ms.locfileid: "45131531"
---
# <a name="archive-features-in-exchange-online-archiving"></a>Exchange Online アーカイブのアーカイブ機能

次のセクションでは、Microsoft Exchange Online アーカイブのアーカイブ機能について説明します。
  
## <a name="archive-mailbox"></a>アーカイブ メールボックス

Exchange Online Archiving は、アーカイブ メールボックス機能を使用した高度なアーカイブ機能をユーザーに提供します。 アーカイブメールボックスは、Outlook または web 上の Outlook のユーザーのプライマリメールボックスフォルダーと共に表示される専用のメールボックスです。 ユーザーは、プライマリ メールボックスと同じ方法でアーカイブにアクセスできます。 加えて、アーカイブとプライマリ メールボックスの両方を検索することができます。
  
Administrators can use the Exchange admin center (EAC) or remote Windows PowerShell to enable the archive feature for specific users. For more information, see [Enable or disable archive mailboxes in Exchange Online](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes).
  
> [!IMPORTANT]
>  アーカイブの目的で、ジャーナリング、トランスポート ルール、または自動転送ルールを使用して Exchange Online Archiving にメッセージをコピーすることは許可されていません。 <br/>
>  ユーザーのアーカイブ メールボックスは、そのユーザー専用です。 Microsoft は、ユーザーのアーカイブメールボックスを使用して他のユーザーのアーカイブデータを保存したり、不適切な使用をしたりする場合に、無制限のアーカイブを拒否する権利を留保します。
  
### <a name="move-messages-to-exchange-online-archiving"></a>Exchange Online Archiving へのメッセージの移動

ユーザーは、メッセージを .pst ファイルからアーカイブにドラッグ アンド ドロップするだけで簡単にオンラインでアクセスできます。 また、アーカイブ ポリシーを使用して電子メール アイテムをプライマリ メールボックスからアーカイブ メールボックスに自動的に移動することによって、プライマリ メールボックスのサイズを削減し、パフォーマンスを向上させることができます。 
  
### <a name="import-data-to-the-archive"></a>アーカイブへのデータのインポート

ユーザーは、以下の方法でアーカイブにデータをインポートできます。
  
- Outlook のインポート/エクスポート ウィザードを使用して .pst ファイルからデータをインポートします。
    
- 電子メール メッセージを .pst ファイルからアーカイブにドラッグします。
    
- 電子メールメッセージをプライマリ メールボックスからアーカイブにドラッグします。
    
- Let archive policies automatically move email messages from the primary mailbox, based on the age of the messages. For more information, see [Retention Tags and Retention Policies](https://docs.microsoft.com/Exchange/policy-and-compliance/mrm/retention-tags-and-retention-policies).
    
> [!NOTE]
> Administrators can also use Office 365 Import service to import .pst files to users' cloud-based archive mailboxes. For more information, see [Use network upload to import PST files to Office 365](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files). 
  
## <a name="deleted-item-recovery"></a>削除済みアイテムの回復

Users can restore items they have deleted from any email folder in their archive. When an item is deleted, it is kept in the archive's Deleted Items folder. It remains there until it is manually removed by the user, or automatically removed by retention policies.
  
アーカイブの [削除済みアイテム] フォルダーからアイテムが削除されると、さらに 14 日間アーカイブの回復可能なアイテム フォルダー内に保存されてから、完全に削除されます。 ユーザーは、Microsoft Outlook または web 上の Outlook の [**削除済みアイテムを復元**する機能を使用してこれらのアイテムを回復できます。 
  
If a user has manually purged an item from the Recoverable Items folder, an administrator can recover the item within the same 14 day window, through a feature called Single Item Recovery. This feature allows administrators to conduct a multi-mailbox search to find purged items and then use the  `Search-Mailbox` Windows PowerShell cmdlet to move the items from the discovery mailbox to users' mailboxes. For more information, see [Enable or disable single item recovery for a mailbox](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files).
  
> [!NOTE]
>  既定で、単一アイテムの回復期間は 14 日間ですが、一部の環境ではカスタマイズができます。 <br/>
>  管理者がユーザーのメールボックスをインプレース保持または訴訟ホールドの対象にしている場合、削除されたアイテムは無期限に保持されるため、14日間の期間は適用されません。 
  
## <a name="deleted-mailbox-recovery"></a>削除済みメールボックスの回復

管理者が社内の Exchange Server からユーザーを削除すると、そのユーザーのアーカイブも削除されます。 削除されたアーカイブメールボックスを回復する必要がある場合は、Microsoft サポートチームがこの回復を実行できます。 回復されたアーカイブには、削除時点で保存されていたすべてのメールが含まれています。
  
> [!IMPORTANT]
> Administrators have 30 days from the time a user's mailbox is deleted to request an archive mailbox recovery. After 30 days, the archive mailbox is not recoverable. 
  
## <a name="mailbox-service-redundancy"></a>メールボックス サービスの冗長性

Exchange Online アーカイブのアーカイブメールボックスは、地理的に分散した Microsoft データセンターの複数のデータベースコピーにレプリケートされ、メッセージングインフラストラクチャに障害が発生した場合にデータ復元機能を提供します。 大規模な障害については、ビジネス継続性管理が開始されます。 
  
## <a name="feature-availability"></a>機能の可用性

プラン、スタンドアロンのオプション、オンプレミスソリューション全体の機能の可用性を表示するには、「 [Exchange Online アーカイブサービスの説明](exchange-online-archiving-service-description.md)」を参照してください。
  
