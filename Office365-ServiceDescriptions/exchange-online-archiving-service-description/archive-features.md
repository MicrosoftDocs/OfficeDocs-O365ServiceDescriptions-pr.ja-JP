---
title: Exchange Online Archiving のアーカイブ機能
ms.author: pebaum
author: pebaum
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- archive-features-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 38abfbd2-5aaa-444a-a431-5e71c566f3e4
description: 次のセクションでは、Microsoft Exchange Online のアーカイブのアーカイブ機能について説明します。
ms.openlocfilehash: 2bffa9fccb2c040fde4edcf8a5c80f3bc109bba2
ms.sourcegitcommit: d6dfbaacd56c0855e12500b38acd06be16cd1560
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 09/19/2018
ms.locfileid: "24036312"
---
# <a name="archive-features-in-exchange-online-archiving"></a><span data-ttu-id="ff1dc-103">Exchange Online Archiving のアーカイブ機能</span><span class="sxs-lookup"><span data-stu-id="ff1dc-103">Archive Features in Exchange Online Archiving</span></span>

<span data-ttu-id="ff1dc-104">次のセクションでは、Microsoft Exchange Online のアーカイブのアーカイブ機能について説明します。</span><span class="sxs-lookup"><span data-stu-id="ff1dc-104">The following sections describe the archive features of Microsoft Exchange Online Archiving.</span></span>
  
## <a name="archive-mailbox"></a><span data-ttu-id="ff1dc-105">アーカイブ メールボックス</span><span class="sxs-lookup"><span data-stu-id="ff1dc-105">Archive mailbox</span></span>

<span data-ttu-id="ff1dc-p101">Exchange Online Archiving は、アーカイブ メールボックス機能を使用した高度なアーカイブ機能をユーザーに提供します。アーカイブ メールボックスは、Outlook または Outlook Web App でユーザーのプライマリ メールボックス フォルダーと一緒に表示される特殊なメールボックスです。ユーザーは、プライマリ メールボックスと同じ方法でアーカイブにアクセスできます。加えて、アーカイブとプライマリ メールボックスの両方を検索することができます。</span><span class="sxs-lookup"><span data-stu-id="ff1dc-p101">Exchange Online Archiving offers users advanced archiving capabilities with the archive mailbox feature. An archive mailbox is a specialized mailbox that appears alongside the users' primary mailbox folders in Outlook or Outlook Web App. Users can access the archive in the same way that they access their primary mailboxes. In addition, they can search both their archives and primary mailboxes.</span></span>
  
<span data-ttu-id="ff1dc-p102">管理者は、Exchange 管理センター (EAC) またはリモート Windows PowerShell を使用して特定のユーザーのアーカイブ機能を有効にすることができます。詳細については、「[Exchange Online のアーカイブ メールボックスを有効または無効にする](https://go.microsoft.com/fwlink/p/?LinkId=404425)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="ff1dc-p102">Administrators can use the Exchange admin center (EAC) or remote Windows PowerShell to enable the archive feature for specific users. For more information, see [Enable or disable archive mailboxes in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=404425).</span></span>
  
> [!IMPORTANT]
>  <span data-ttu-id="ff1dc-p103">アーカイブの目的で、ジャーナリング、トランスポート ルール、または自動転送ルールを使用して Exchange Online Archiving にメッセージをコピーすることは許可されていません。 >  ユーザーのアーカイブ メールボックスは、そのユーザー専用です。Microsoft は、ユーザーのアーカイブ メールボックスを使用して他のユーザーのアーカイブ データを格納する、インスタンスでの無制限アーカイブを拒否する権利を有します。</span><span class="sxs-lookup"><span data-stu-id="ff1dc-p103">Using journaling, transport rules, or auto-forwarding rules to copy messages to Exchange Online Archiving for the purposes of archiving is not permitted. >  A user's archive mailbox is intended for just that user. Microsoft reserves the right to deny unlimited archiving in instances where a user's archive mailbox is used to store archive data for other users.</span></span> 
  
### <a name="move-messages-to-exchange-online-archiving"></a><span data-ttu-id="ff1dc-115">Exchange Online Archiving へのメッセージの移動</span><span class="sxs-lookup"><span data-stu-id="ff1dc-115">Move messages to Exchange Online Archiving</span></span>

<span data-ttu-id="ff1dc-p104">ユーザーは、メッセージを .pst ファイルからアーカイブにドラッグ アンド ドロップするだけで簡単にオンラインでアクセスできます。また、アーカイブ ポリシーを使用して電子メール アイテムをプライマリ メールボックスからアーカイブ メールボックスに自動的に移動することによって、プライマリ メールボックスのサイズを削減し、パフォーマンスを向上させることができます。この動作はアーカイブ内に各メッセージの 2 次コピーが作成される Exchange Hosted Archive と異なりますが、どちらのシナリオでも保存要件を満たすことができます。メッセージをアーカイブに移動するその他の方法については「[Exchange Online のアーカイブ メールボックス](https://go.microsoft.com/fwlink/p/?LinkId=404421)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="ff1dc-p104">Users can drag and drop messages from .pst files into the archive, for easy online access. Users can also move email items from the primary mailbox to the archive mailbox automatically, using Archive Polices, to reduce the size and improve the performance of the primary mailbox. While this behavior is different than Exchange Hosted Archive, which will create a secondary copy of each message in the archive, retention requirements can be achieved in either scenario. For details on additional methods to move messages into the archive, see [Archive mailboxes in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=404421).</span></span>
  
### <a name="import-data-to-the-archive"></a><span data-ttu-id="ff1dc-120">アーカイブへのデータのインポート</span><span class="sxs-lookup"><span data-stu-id="ff1dc-120">Import data to the archive</span></span>

<span data-ttu-id="ff1dc-121">ユーザーは、以下の方法でアーカイブにデータをインポートできます。</span><span class="sxs-lookup"><span data-stu-id="ff1dc-121">Users can import data to the archive in the following ways:</span></span>
  
- <span data-ttu-id="ff1dc-122">Outlook のインポート/エクスポート ウィザードを使用して .pst ファイルからデータをインポートします。</span><span class="sxs-lookup"><span data-stu-id="ff1dc-122">Import data from a .pst file using Outlook's Import and Export wizard.</span></span>
    
- <span data-ttu-id="ff1dc-123">電子メール メッセージを .pst ファイルからアーカイブにドラッグします。</span><span class="sxs-lookup"><span data-stu-id="ff1dc-123">Drag email messages from .pst files into the archive.</span></span>
    
- <span data-ttu-id="ff1dc-124">電子メールメッセージをプライマリ メールボックスからアーカイブにドラッグします。</span><span class="sxs-lookup"><span data-stu-id="ff1dc-124">Drag email messages from the primary mailbox into the archive.</span></span>
    
- <span data-ttu-id="ff1dc-p105">アーカイブ ポリシーを利用して、電子メール メッセージをその保存期間に基づいてプライマリ メールボックスから自動的に移動します。詳細については、「[保持タグおよびアイテム保持ポリシー](https://go.microsoft.com/fwlink/p/?LinkId=314153)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="ff1dc-p105">Let archive policies automatically move email messages from the primary mailbox, based on the age of the messages. For more information, see [Retention Tags and Retention Policies](https://go.microsoft.com/fwlink/p/?LinkId=314153).</span></span>
    
> [!NOTE]
> <span data-ttu-id="ff1dc-p106">管理者は、ユーザーのクラウドベースのアーカイブ メールボックスに .pst ファイルをインポートするため Office 365 インポート サービスを使用することもできます。詳細については、「[ネットワーク アップロードを使用して PST ファイルを Office 365 にインストールする](https://go.microsoft.com/fwlink/p/?linkid=823074)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="ff1dc-p106">Administrators can also use Office 365 Import service to import .pst files to users' cloud-based archive mailboxes. For more information, see [Use network upload to import PST files to Office 365](https://go.microsoft.com/fwlink/p/?linkid=823074).</span></span> 
  
## <a name="deleted-item-recovery"></a><span data-ttu-id="ff1dc-129">削除済みアイテムの回復</span><span class="sxs-lookup"><span data-stu-id="ff1dc-129">Deleted item recovery</span></span>

<span data-ttu-id="ff1dc-p107">ユーザーは、アーカイブ内の任意の電子メール フォルダーから削除されたアイテムを復元できます。削除されたアイテムは、アーカイブの [削除済みアイテム] フォルダーに移動されます。このアイテムは、ユーザーが手動で削除するか、保持ポリシーによって自動的に削除されるまで、[削除済みアイテム] フォルダーに残ります。</span><span class="sxs-lookup"><span data-stu-id="ff1dc-p107">Users can restore items they have deleted from any email folder in their archive. When an item is deleted, it is kept in the archive's Deleted Items folder. It remains there until it is manually removed by the user, or automatically removed by retention policies.</span></span>
  
<span data-ttu-id="ff1dc-p108">アーカイブの [削除済みアイテム] フォルダーからアイテムが削除されると、さらに 14 日間アーカイブの回復可能なアイテム フォルダー内に保存されてから、完全に削除されます。ユーザーは、これらのアイテムを Microsoft Outlook または Outlook Web App の **[削除済みアイテムの回復]** 機能を使用して回復できます。</span><span class="sxs-lookup"><span data-stu-id="ff1dc-p108">After an item has been removed from the archive's Deleted Items folder, the item is kept in the archive's Recoverable Items folder for an additional 14 days before being permanently removed. Users can recover these items using the **Recover Deleted Items** feature in Microsoft Outlook or Outlook Web App.</span></span> 
  
<span data-ttu-id="ff1dc-p109">ユーザーが回復可能なアイテム フォルダーからアイテムを手動で削除した場合、管理者は単一アイテムの回復と呼ばれる機能を使って同じ 14 日間の期間内にアイテムを回復できます。管理者は、この機能を使用して、複数のメールボックスを検索して削除されたアイテムを検索してから、 `Search-Mailbox` Windows PowerShell コマンドレットを使用してそれらのアイテムを探索メールボックスからユーザーのメールボックスに移動できます。詳細については、「 [メールボックスの単一アイテムの回復を有効または無効にする](https://go.microsoft.com/fwlink/p/?LinkId=314155)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="ff1dc-p109">If a user has manually purged an item from the Recoverable Items folder, an administrator can recover the item within the same 14 day window, through a feature called Single Item Recovery. This feature allows administrators to conduct a multi-mailbox search to find purged items and then use the  `Search-Mailbox` Windows PowerShell cmdlet to move the items from the discovery mailbox to users' mailboxes. For more information, see [Enable or disable single item recovery for a mailbox](https://go.microsoft.com/fwlink/p/?LinkId=314155).</span></span>
  
> [!NOTE]
>  <span data-ttu-id="ff1dc-p110">既定で、単一アイテムの回復期間は 14 日間ですが、一部の環境ではカスタマイズができます。 >  管理者がユーザーのメールボックスでインプレース保持または訴訟ホールドを設定にしている場合は、削除されたアイテムが無期限に保存されるため、14 日間の期間が適用されません。</span><span class="sxs-lookup"><span data-stu-id="ff1dc-p110">The Single Item Recovery period is 14 days by default, but it can be customized in some circumstances. >  If an administrator has placed a user's mailbox on In-Place Hold or Litigation Hold, purged items are retained indefinitely and the 14-day window does not apply.</span></span> 
  
## <a name="deleted-mailbox-recovery"></a><span data-ttu-id="ff1dc-140">削除済みメールボックスの回復</span><span class="sxs-lookup"><span data-stu-id="ff1dc-140">Deleted mailbox recovery</span></span>

<span data-ttu-id="ff1dc-p111">管理者が社内の Exchange Server からユーザーを削除すると、そのユーザーのアーカイブも削除されます。削除されたアーカイブ メールボックスを回復する必要がある場合は、Office 365 サポート チームがこの回復を実行できます。回復されたアーカイブには、削除時点で保存されていたすべてのメールが含まれています。</span><span class="sxs-lookup"><span data-stu-id="ff1dc-p111">When administrators delete users from the on-premises Exchange Server, the users' archives are also deleted. If the deleted archive mailboxes need to be recovered, the Office 365 support team can perform this recovery. A recovered archive will contain all of the mail stored in it at the time it was deleted.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="ff1dc-p112">管理者は、ユーザーのメールボックスが削除された時点から 30 日間、アーカイブ メールボックスの回復を要求できます。30 日後、アーカイブ メールボックスは回復できなくなります。</span><span class="sxs-lookup"><span data-stu-id="ff1dc-p112">Administrators have 30 days from the time a user's mailbox is deleted to request an archive mailbox recovery. After 30 days, the archive mailbox is not recoverable.</span></span> 
  
## <a name="mailbox-service-redundancy"></a><span data-ttu-id="ff1dc-146">メールボックス サービスの冗長性</span><span class="sxs-lookup"><span data-stu-id="ff1dc-146">Mailbox service redundancy</span></span>

<span data-ttu-id="ff1dc-p113">Exchange Online Archiving のアーカイブ メールボックスは、メッセージング インフラストラクチャの障害が発生した場合のデータ復元機能を提供する、地理的に分散されている Microsoft データ センター内の複数のデータベース コピーにレプリケートされます。大規模な障害は、ビジネス継続性の管理が開始されます。</span><span class="sxs-lookup"><span data-stu-id="ff1dc-p113">Archive mailboxes in Exchange Online Archiving are replicated to multiple database copies, in geographically dispersed Microsoft data centers, to provide data restoration capability in the event of a messaging infrastructure failure. For large-scale failures, business continuity management is initiated.</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="ff1dc-149">機能の可用性</span><span class="sxs-lookup"><span data-stu-id="ff1dc-149">Feature Availability</span></span>

<span data-ttu-id="ff1dc-150">Office 365 のプラン、スタンドアロンのオプション、オンプレミス ソリューション全体の機能の可用性を表示するには、「[Exchange Online Archiving サービスの説明](exchange-online-archiving-service-description.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="ff1dc-150">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Archiving Service Description](exchange-online-archiving-service-description.md).</span></span>
  
