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
# <a name="archive-features-in-exchange-online-archiving"></a><span data-ttu-id="9efa7-103">Exchange Online アーカイブのアーカイブ機能</span><span class="sxs-lookup"><span data-stu-id="9efa7-103">Archive features in Exchange Online Archiving</span></span>

<span data-ttu-id="9efa7-104">次のセクションでは、Microsoft Exchange Online アーカイブのアーカイブ機能について説明します。</span><span class="sxs-lookup"><span data-stu-id="9efa7-104">The following sections describe the archive features of Microsoft Exchange Online Archiving.</span></span>
  
## <a name="archive-mailbox"></a><span data-ttu-id="9efa7-105">アーカイブ メールボックス</span><span class="sxs-lookup"><span data-stu-id="9efa7-105">Archive mailbox</span></span>

<span data-ttu-id="9efa7-106">Exchange Online Archiving は、アーカイブ メールボックス機能を使用した高度なアーカイブ機能をユーザーに提供します。</span><span class="sxs-lookup"><span data-stu-id="9efa7-106">Exchange Online Archiving offers users advanced archiving capabilities with the archive mailbox feature.</span></span> <span data-ttu-id="9efa7-107">アーカイブメールボックスは、Outlook または web 上の Outlook のユーザーのプライマリメールボックスフォルダーと共に表示される専用のメールボックスです。</span><span class="sxs-lookup"><span data-stu-id="9efa7-107">An archive mailbox is a specialized mailbox that appears alongside the users' primary mailbox folders in Outlook or Outlook on the web.</span></span> <span data-ttu-id="9efa7-108">ユーザーは、プライマリ メールボックスと同じ方法でアーカイブにアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="9efa7-108">Users can access the archive in the same way that they access their primary mailboxes.</span></span> <span data-ttu-id="9efa7-109">加えて、アーカイブとプライマリ メールボックスの両方を検索することができます。</span><span class="sxs-lookup"><span data-stu-id="9efa7-109">In addition, they can search both their archives and primary mailboxes.</span></span>
  
<span data-ttu-id="9efa7-110">Administrators can use the Exchange admin center (EAC) or remote Windows PowerShell to enable the archive feature for specific users.</span><span class="sxs-lookup"><span data-stu-id="9efa7-110">Administrators can use the Exchange admin center (EAC) or remote Windows PowerShell to enable the archive feature for specific users.</span></span> <span data-ttu-id="9efa7-111">For more information, see [Enable or disable archive mailboxes in Exchange Online](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes).</span><span class="sxs-lookup"><span data-stu-id="9efa7-111">For more information, see [Enable or disable archive mailboxes in Exchange Online](https://docs.microsoft.com/office365/securitycompliance/enable-archive-mailboxes).</span></span>
  
> [!IMPORTANT]
>  <span data-ttu-id="9efa7-112">アーカイブの目的で、ジャーナリング、トランスポート ルール、または自動転送ルールを使用して Exchange Online Archiving にメッセージをコピーすることは許可されていません。</span><span class="sxs-lookup"><span data-stu-id="9efa7-112">Using journaling, transport rules, or auto-forwarding rules to copy messages to Exchange Online Archiving for the purposes of archiving is not permitted.</span></span> <br/>
>  <span data-ttu-id="9efa7-113">ユーザーのアーカイブ メールボックスは、そのユーザー専用です。</span><span class="sxs-lookup"><span data-stu-id="9efa7-113">A user's archive mailbox is intended for just that user.</span></span> <span data-ttu-id="9efa7-114">Microsoft は、ユーザーのアーカイブメールボックスを使用して他のユーザーのアーカイブデータを保存したり、不適切な使用をしたりする場合に、無制限のアーカイブを拒否する権利を留保します。</span><span class="sxs-lookup"><span data-stu-id="9efa7-114">Microsoft reserves the right to deny unlimited archiving in instances where a user's archive mailbox is used to store archive data for other users or in other cases of inappropriate use.</span></span>
  
### <a name="move-messages-to-exchange-online-archiving"></a><span data-ttu-id="9efa7-115">Exchange Online Archiving へのメッセージの移動</span><span class="sxs-lookup"><span data-stu-id="9efa7-115">Move messages to Exchange Online Archiving</span></span>

<span data-ttu-id="9efa7-116">ユーザーは、メッセージを .pst ファイルからアーカイブにドラッグ アンド ドロップするだけで簡単にオンラインでアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="9efa7-116">Users can drag and drop messages from .pst files into the archive, for easy online access.</span></span> <span data-ttu-id="9efa7-117">また、アーカイブ ポリシーを使用して電子メール アイテムをプライマリ メールボックスからアーカイブ メールボックスに自動的に移動することによって、プライマリ メールボックスのサイズを削減し、パフォーマンスを向上させることができます。</span><span class="sxs-lookup"><span data-stu-id="9efa7-117">Users can also move email items from the primary mailbox to the archive mailbox automatically, using Archive Polices, to reduce the size and improve the performance of the primary mailbox.</span></span> 
  
### <a name="import-data-to-the-archive"></a><span data-ttu-id="9efa7-118">アーカイブへのデータのインポート</span><span class="sxs-lookup"><span data-stu-id="9efa7-118">Import data to the archive</span></span>

<span data-ttu-id="9efa7-119">ユーザーは、以下の方法でアーカイブにデータをインポートできます。</span><span class="sxs-lookup"><span data-stu-id="9efa7-119">Users can import data to the archive in the following ways:</span></span>
  
- <span data-ttu-id="9efa7-120">Outlook のインポート/エクスポート ウィザードを使用して .pst ファイルからデータをインポートします。</span><span class="sxs-lookup"><span data-stu-id="9efa7-120">Import data from a .pst file using Outlook's Import and Export wizard.</span></span>
    
- <span data-ttu-id="9efa7-121">電子メール メッセージを .pst ファイルからアーカイブにドラッグします。</span><span class="sxs-lookup"><span data-stu-id="9efa7-121">Drag email messages from .pst files into the archive.</span></span>
    
- <span data-ttu-id="9efa7-122">電子メールメッセージをプライマリ メールボックスからアーカイブにドラッグします。</span><span class="sxs-lookup"><span data-stu-id="9efa7-122">Drag email messages from the primary mailbox into the archive.</span></span>
    
- <span data-ttu-id="9efa7-123">Let archive policies automatically move email messages from the primary mailbox, based on the age of the messages.</span><span class="sxs-lookup"><span data-stu-id="9efa7-123">Let archive policies automatically move email messages from the primary mailbox, based on the age of the messages.</span></span> <span data-ttu-id="9efa7-124">For more information, see [Retention Tags and Retention Policies](https://docs.microsoft.com/Exchange/policy-and-compliance/mrm/retention-tags-and-retention-policies).</span><span class="sxs-lookup"><span data-stu-id="9efa7-124">For more information, see [Retention Tags and Retention Policies](https://docs.microsoft.com/Exchange/policy-and-compliance/mrm/retention-tags-and-retention-policies).</span></span>
    
> [!NOTE]
> <span data-ttu-id="9efa7-125">Administrators can also use Office 365 Import service to import .pst files to users' cloud-based archive mailboxes.</span><span class="sxs-lookup"><span data-stu-id="9efa7-125">Administrators can also use Office 365 Import service to import .pst files to users' cloud-based archive mailboxes.</span></span> <span data-ttu-id="9efa7-126">For more information, see [Use network upload to import PST files to Office 365](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files).</span><span class="sxs-lookup"><span data-stu-id="9efa7-126">For more information, see [Use network upload to import PST files to Office 365](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files).</span></span> 
  
## <a name="deleted-item-recovery"></a><span data-ttu-id="9efa7-127">削除済みアイテムの回復</span><span class="sxs-lookup"><span data-stu-id="9efa7-127">Deleted item recovery</span></span>

<span data-ttu-id="9efa7-128">Users can restore items they have deleted from any email folder in their archive.</span><span class="sxs-lookup"><span data-stu-id="9efa7-128">Users can restore items they have deleted from any email folder in their archive.</span></span> <span data-ttu-id="9efa7-129">When an item is deleted, it is kept in the archive's Deleted Items folder.</span><span class="sxs-lookup"><span data-stu-id="9efa7-129">When an item is deleted, it is kept in the archive's Deleted Items folder.</span></span> <span data-ttu-id="9efa7-130">It remains there until it is manually removed by the user, or automatically removed by retention policies.</span><span class="sxs-lookup"><span data-stu-id="9efa7-130">It remains there until it is manually removed by the user, or automatically removed by retention policies.</span></span>
  
<span data-ttu-id="9efa7-131">アーカイブの [削除済みアイテム] フォルダーからアイテムが削除されると、さらに 14 日間アーカイブの回復可能なアイテム フォルダー内に保存されてから、完全に削除されます。</span><span class="sxs-lookup"><span data-stu-id="9efa7-131">After an item has been removed from the archive's Deleted Items folder, the item is kept in the archive's Recoverable Items folder for an additional 14 days before being permanently removed.</span></span> <span data-ttu-id="9efa7-132">ユーザーは、Microsoft Outlook または web 上の Outlook の [**削除済みアイテムを復元**する機能を使用してこれらのアイテムを回復できます。</span><span class="sxs-lookup"><span data-stu-id="9efa7-132">Users can recover these items using the **Recover Deleted Items** feature in Microsoft Outlook or Outlook on the web.</span></span> 
  
<span data-ttu-id="9efa7-133">If a user has manually purged an item from the Recoverable Items folder, an administrator can recover the item within the same 14 day window, through a feature called Single Item Recovery.</span><span class="sxs-lookup"><span data-stu-id="9efa7-133">If a user has manually purged an item from the Recoverable Items folder, an administrator can recover the item within the same 14 day window, through a feature called Single Item Recovery.</span></span> <span data-ttu-id="9efa7-134">This feature allows administrators to conduct a multi-mailbox search to find purged items and then use the  `Search-Mailbox` Windows PowerShell cmdlet to move the items from the discovery mailbox to users' mailboxes.</span><span class="sxs-lookup"><span data-stu-id="9efa7-134">This feature allows administrators to conduct a multi-mailbox search to find purged items and then use the  `Search-Mailbox` Windows PowerShell cmdlet to move the items from the discovery mailbox to users' mailboxes.</span></span> <span data-ttu-id="9efa7-135">For more information, see [Enable or disable single item recovery for a mailbox](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files).</span><span class="sxs-lookup"><span data-stu-id="9efa7-135">For more information, see [Enable or disable single item recovery for a mailbox](https://docs.microsoft.com/office365/securitycompliance/use-network-upload-to-import-pst-files).</span></span>
  
> [!NOTE]
>  <span data-ttu-id="9efa7-136">既定で、単一アイテムの回復期間は 14 日間ですが、一部の環境ではカスタマイズができます。</span><span class="sxs-lookup"><span data-stu-id="9efa7-136">The Single Item Recovery period is 14 days by default, but it can be customized in some circumstances.</span></span> <br/>
>  <span data-ttu-id="9efa7-137">管理者がユーザーのメールボックスをインプレース保持または訴訟ホールドの対象にしている場合、削除されたアイテムは無期限に保持されるため、14日間の期間は適用されません。</span><span class="sxs-lookup"><span data-stu-id="9efa7-137">If an administrator has placed a user's mailbox on In-Place Hold or Litigation Hold, purged items are retained indefinitely and the 14-day window does not apply.</span></span> 
  
## <a name="deleted-mailbox-recovery"></a><span data-ttu-id="9efa7-138">削除済みメールボックスの回復</span><span class="sxs-lookup"><span data-stu-id="9efa7-138">Deleted mailbox recovery</span></span>

<span data-ttu-id="9efa7-139">管理者が社内の Exchange Server からユーザーを削除すると、そのユーザーのアーカイブも削除されます。</span><span class="sxs-lookup"><span data-stu-id="9efa7-139">When administrators delete users from the on-premises Exchange Server, the users' archives are also deleted.</span></span> <span data-ttu-id="9efa7-140">削除されたアーカイブメールボックスを回復する必要がある場合は、Microsoft サポートチームがこの回復を実行できます。</span><span class="sxs-lookup"><span data-stu-id="9efa7-140">If the deleted archive mailboxes need to be recovered, the Microsoft support team can perform this recovery.</span></span> <span data-ttu-id="9efa7-141">回復されたアーカイブには、削除時点で保存されていたすべてのメールが含まれています。</span><span class="sxs-lookup"><span data-stu-id="9efa7-141">A recovered archive will contain all of the mail stored in it at the time it was deleted.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="9efa7-142">Administrators have 30 days from the time a user's mailbox is deleted to request an archive mailbox recovery.</span><span class="sxs-lookup"><span data-stu-id="9efa7-142">Administrators have 30 days from the time a user's mailbox is deleted to request an archive mailbox recovery.</span></span> <span data-ttu-id="9efa7-143">After 30 days, the archive mailbox is not recoverable.</span><span class="sxs-lookup"><span data-stu-id="9efa7-143">After 30 days, the archive mailbox is not recoverable.</span></span> 
  
## <a name="mailbox-service-redundancy"></a><span data-ttu-id="9efa7-144">メールボックス サービスの冗長性</span><span class="sxs-lookup"><span data-stu-id="9efa7-144">Mailbox service redundancy</span></span>

<span data-ttu-id="9efa7-145">Exchange Online アーカイブのアーカイブメールボックスは、地理的に分散した Microsoft データセンターの複数のデータベースコピーにレプリケートされ、メッセージングインフラストラクチャに障害が発生した場合にデータ復元機能を提供します。</span><span class="sxs-lookup"><span data-stu-id="9efa7-145">Archive mailboxes in Exchange Online Archiving are replicated to multiple database copies, in geographically dispersed Microsoft data centers, to provide data restoration capability in the event of a messaging infrastructure failure.</span></span> <span data-ttu-id="9efa7-146">大規模な障害については、ビジネス継続性管理が開始されます。</span><span class="sxs-lookup"><span data-stu-id="9efa7-146">For large-scale failures, business continuity management is initiated.</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="9efa7-147">機能の可用性</span><span class="sxs-lookup"><span data-stu-id="9efa7-147">Feature availability</span></span>

<span data-ttu-id="9efa7-148">プラン、スタンドアロンのオプション、オンプレミスソリューション全体の機能の可用性を表示するには、「 [Exchange Online アーカイブサービスの説明](exchange-online-archiving-service-description.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="9efa7-148">To view feature availability across plans, standalone options, and on-premises solutions, see [Exchange Online Archiving service description](exchange-online-archiving-service-description.md).</span></span>
  
