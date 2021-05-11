---
title: アーカイブ機能のExchange Online Archiving
ms.author: office365servicedesc
author: pamelaar
manager: gailw
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
description: '[アーカイブ] で使用できるアーカイブ機能Microsoft Exchange Onlineします。'
ms.openlocfilehash: cfc5832e3167f29465f387253694e56b66b932fd
ms.sourcegitcommit: 9fac5d9579e3b370b15384b36d0f1805cab20065
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/09/2021
ms.locfileid: "51653099"
---
# <a name="archive-features-in-exchange-online-archiving"></a><span data-ttu-id="20d0e-103">アーカイブ機能のExchange Online Archiving</span><span class="sxs-lookup"><span data-stu-id="20d0e-103">Archive features in Exchange Online Archiving</span></span>

<span data-ttu-id="20d0e-104">以下のセクションでは、アーカイブのアーカイブ機能Microsoft Exchange Onlineします。</span><span class="sxs-lookup"><span data-stu-id="20d0e-104">The following sections describe the archive features of Microsoft Exchange Online Archiving.</span></span>
  
## <a name="archive-mailbox"></a><span data-ttu-id="20d0e-105">アーカイブ メールボックス</span><span class="sxs-lookup"><span data-stu-id="20d0e-105">Archive mailbox</span></span>

<span data-ttu-id="20d0e-106">Exchange Online Archiving は、アーカイブ メールボックス機能を使用した高度なアーカイブ機能をユーザーに提供します。</span><span class="sxs-lookup"><span data-stu-id="20d0e-106">Exchange Online Archiving offers users advanced archiving capabilities with the archive mailbox feature.</span></span> <span data-ttu-id="20d0e-107">アーカイブ メールボックスは、Web 上のユーザーのプライマリ メールボックス フォルダーと一緒にOutlookまたはOutlookメールボックスです。</span><span class="sxs-lookup"><span data-stu-id="20d0e-107">An archive mailbox is a specialized mailbox that appears alongside the users' primary mailbox folders in Outlook or Outlook on the web.</span></span> <span data-ttu-id="20d0e-108">ユーザーは、プライマリ メールボックスと同じ方法でアーカイブにアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="20d0e-108">Users can access the archive in the same way that they access their primary mailboxes.</span></span> <span data-ttu-id="20d0e-109">加えて、アーカイブとプライマリ メールボックスの両方を検索することができます。</span><span class="sxs-lookup"><span data-stu-id="20d0e-109">In addition, they can search both their archives and primary mailboxes.</span></span>
  
<span data-ttu-id="20d0e-p102">管理者は、Exchange 管理センター (EAC) またはリモート Windows PowerShell を使用して特定のユーザーのアーカイブ機能を有効にすることができます。詳細については、「[Exchange Online のアーカイブ メールボックスを有効または無効にする](/office365/securitycompliance/enable-archive-mailboxes)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="20d0e-p102">Administrators can use the Exchange admin center (EAC) or remote Windows PowerShell to enable the archive feature for specific users. For more information, see [Enable or disable archive mailboxes in Exchange Online](/office365/securitycompliance/enable-archive-mailboxes).</span></span>
  
> [!IMPORTANT]
>  <span data-ttu-id="20d0e-p103">アーカイブの目的で、ジャーナリング、トランスポート ルール、または自動転送ルールを使用して Exchange Online Archiving にメッセージをコピーすることは許可されていません。</span><span class="sxs-lookup"><span data-stu-id="20d0e-p103">Using journaling, transport rules, or auto-forwarding rules to copy messages to Exchange Online Archiving for the purposes of archiving is not permitted. </span></span><br/>
>  <span data-ttu-id="20d0e-113">ユーザーのアーカイブ メールボックスは、そのユーザー専用です。</span><span class="sxs-lookup"><span data-stu-id="20d0e-113">A user's archive mailbox is intended for just that user.</span></span> <span data-ttu-id="20d0e-114">Microsoft は、ユーザーのアーカイブ メールボックスを使用して他のユーザーのアーカイブ データを格納する、またはその他の不適切な使用の場合には、インスタンスに無制限アーカイブを拒否する権利を有します。</span><span class="sxs-lookup"><span data-stu-id="20d0e-114">Microsoft reserves the right to deny unlimited archiving in instances where a user's archive mailbox is used to store archive data for other users or in other cases of inappropriate use.</span></span>
  
### <a name="move-messages-to-exchange-online-archiving"></a><span data-ttu-id="20d0e-115">Exchange Online Archiving へのメッセージの移動</span><span class="sxs-lookup"><span data-stu-id="20d0e-115">Move messages to Exchange Online Archiving</span></span>

<span data-ttu-id="20d0e-116">ユーザーは、メッセージを .pst ファイルからアーカイブにドラッグ アンド ドロップするだけで簡単にオンラインでアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="20d0e-116">Users can drag and drop messages from .pst files into the archive, for easy online access.</span></span> <span data-ttu-id="20d0e-117">また、アーカイブ ポリシーを使用して電子メール アイテムをプライマリ メールボックスからアーカイブ メールボックスに自動的に移動することによって、プライマリ メールボックスのサイズを削減し、パフォーマンスを向上させることができます。</span><span class="sxs-lookup"><span data-stu-id="20d0e-117">Users can also move email items from the primary mailbox to the archive mailbox automatically, using Archive Polices, to reduce the size and improve the performance of the primary mailbox.</span></span> 
  
### <a name="import-data-to-the-archive"></a><span data-ttu-id="20d0e-118">アーカイブへのデータのインポート</span><span class="sxs-lookup"><span data-stu-id="20d0e-118">Import data to the archive</span></span>

<span data-ttu-id="20d0e-119">ユーザーは、以下の方法でアーカイブにデータをインポートできます。</span><span class="sxs-lookup"><span data-stu-id="20d0e-119">Users can import data to the archive in the following ways:</span></span>
  
- <span data-ttu-id="20d0e-120">Outlook のインポート/エクスポート ウィザードを使用して .pst ファイルからデータをインポートします。</span><span class="sxs-lookup"><span data-stu-id="20d0e-120">Import data from a .pst file using Outlook's Import and Export wizard.</span></span>
    
- <span data-ttu-id="20d0e-121">電子メール メッセージを .pst ファイルからアーカイブにドラッグします。</span><span class="sxs-lookup"><span data-stu-id="20d0e-121">Drag email messages from .pst files into the archive.</span></span>
    
- <span data-ttu-id="20d0e-122">電子メールメッセージをプライマリ メールボックスからアーカイブにドラッグします。</span><span class="sxs-lookup"><span data-stu-id="20d0e-122">Drag email messages from the primary mailbox into the archive.</span></span>
    
- <span data-ttu-id="20d0e-p106">アーカイブ ポリシーを利用して、電子メール メッセージをその保存期間に基づいてプライマリ メールボックスから自動的に移動します。詳細については、「[保持タグおよびアイテム保持ポリシー](/Exchange/policy-and-compliance/mrm/retention-tags-and-retention-policies)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="20d0e-p106">Let archive policies automatically move email messages from the primary mailbox, based on the age of the messages. For more information, see [Retention Tags and Retention Policies](/Exchange/policy-and-compliance/mrm/retention-tags-and-retention-policies).</span></span>
    
> [!NOTE]
> <span data-ttu-id="20d0e-p107">管理者は、ユーザーのクラウドベースのアーカイブ メールボックスに .pst ファイルをインポートするため Office 365 インポート サービスを使用することもできます。詳細については、「[ネットワーク アップロードを使用して PST ファイルを Office 365 にインストールする](/office365/securitycompliance/use-network-upload-to-import-pst-files)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="20d0e-p107">Administrators can also use Office 365 Import service to import .pst files to users' cloud-based archive mailboxes. For more information, see [Use network upload to import PST files to Office 365](/office365/securitycompliance/use-network-upload-to-import-pst-files).</span></span> 
  
## <a name="deleted-item-recovery"></a><span data-ttu-id="20d0e-127">削除済みアイテムの回復</span><span class="sxs-lookup"><span data-stu-id="20d0e-127">Deleted item recovery</span></span>

<span data-ttu-id="20d0e-p108">ユーザーは、アーカイブ内の任意の電子メール フォルダーから削除されたアイテムを復元できます。削除されたアイテムは、アーカイブの [削除済みアイテム] フォルダーに移動されます。このアイテムは、ユーザーが手動で削除するか、保持ポリシーによって自動的に削除されるまで、[削除済みアイテム] フォルダーに残ります。</span><span class="sxs-lookup"><span data-stu-id="20d0e-p108">Users can restore items they have deleted from any email folder in their archive. When an item is deleted, it is kept in the archive's Deleted Items folder. It remains there until it is manually removed by the user, or automatically removed by retention policies.</span></span>
  
<span data-ttu-id="20d0e-131">アーカイブの [削除済みアイテム] フォルダーからアイテムが削除されると、さらに 14 日間アーカイブの回復可能なアイテム フォルダー内に保存されてから、完全に削除されます。</span><span class="sxs-lookup"><span data-stu-id="20d0e-131">After an item has been removed from the archive's Deleted Items folder, the item is kept in the archive's Recoverable Items folder for an additional 14 days before being permanently removed.</span></span> <span data-ttu-id="20d0e-132">ユーザーは、Microsoft の[削除済みアイテムの回復] 機能を使用して、OutlookまたはOutlookを回復できます。</span><span class="sxs-lookup"><span data-stu-id="20d0e-132">Users can recover these items using the **Recover Deleted Items** feature in Microsoft Outlook or Outlook on the web.</span></span> 
  
<span data-ttu-id="20d0e-p110">ユーザーが回復可能なアイテム フォルダーからアイテムを手動で削除した場合、管理者は単一アイテムの回復と呼ばれる機能を使って同じ 14 日間の期間内にアイテムを回復できます。管理者は、この機能を使用して、複数のメールボックスを検索して削除されたアイテムを検索してから、 `Search-Mailbox` Windows PowerShell コマンドレットを使用してそれらのアイテムを探索メールボックスからユーザーのメールボックスに移動できます。詳細については、「 [メールボックスの単一アイテムの回復を有効または無効にする](/office365/securitycompliance/use-network-upload-to-import-pst-files)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="20d0e-p110">If a user has manually purged an item from the Recoverable Items folder, an administrator can recover the item within the same 14 day window, through a feature called Single Item Recovery. This feature allows administrators to conduct a multi-mailbox search to find purged items and then use the  `Search-Mailbox` Windows PowerShell cmdlet to move the items from the discovery mailbox to users' mailboxes. For more information, see [Enable or disable single item recovery for a mailbox](/office365/securitycompliance/use-network-upload-to-import-pst-files).</span></span>
  
> [!NOTE]
>  <span data-ttu-id="20d0e-p111">既定で、単一アイテムの回復期間は 14 日間ですが、一部の環境ではカスタマイズができます。</span><span class="sxs-lookup"><span data-stu-id="20d0e-p111">The Single Item Recovery period is 14 days by default, but it can be customized in some circumstances. </span></span><br/>
>  <span data-ttu-id="20d0e-137">管理者が In-Place 保留または訴訟ホールドにユーザーのメールボックスを配置した場合、削除されたアイテムは無期限に保持され、14 日間のウィンドウは適用されません。</span><span class="sxs-lookup"><span data-stu-id="20d0e-137">If an administrator has placed a user's mailbox on In-Place Hold or Litigation Hold, purged items are retained indefinitely and the 14-day window does not apply.</span></span> 
  
## <a name="deleted-mailbox-recovery"></a><span data-ttu-id="20d0e-138">削除済みメールボックスの回復</span><span class="sxs-lookup"><span data-stu-id="20d0e-138">Deleted mailbox recovery</span></span>

<span data-ttu-id="20d0e-139">管理者が社内の Exchange Server からユーザーを削除すると、そのユーザーのアーカイブも削除されます。</span><span class="sxs-lookup"><span data-stu-id="20d0e-139">When administrators delete users from the on-premises Exchange Server, the users' archives are also deleted.</span></span> <span data-ttu-id="20d0e-140">削除されたアーカイブ メールボックスを回復する必要がある場合、Microsoft サポート チームはこの回復を実行できます。</span><span class="sxs-lookup"><span data-stu-id="20d0e-140">If the deleted archive mailboxes need to be recovered, the Microsoft support team can perform this recovery.</span></span> <span data-ttu-id="20d0e-141">回復されたアーカイブには、削除時点で保存されていたすべてのメールが含まれています。</span><span class="sxs-lookup"><span data-stu-id="20d0e-141">A recovered archive will contain all of the mail stored in it at the time it was deleted.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="20d0e-p113">管理者は、ユーザーのメールボックスが削除された時点から 30 日間、アーカイブ メールボックスの回復を要求できます。30 日後、アーカイブ メールボックスは回復できなくなります。</span><span class="sxs-lookup"><span data-stu-id="20d0e-p113">Administrators have 30 days from the time a user's mailbox is deleted to request an archive mailbox recovery. After 30 days, the archive mailbox is not recoverable.</span></span> 
  
## <a name="mailbox-service-redundancy"></a><span data-ttu-id="20d0e-144">メールボックス サービスの冗長性</span><span class="sxs-lookup"><span data-stu-id="20d0e-144">Mailbox service redundancy</span></span>

<span data-ttu-id="20d0e-145">Exchange Online Archivingのアーカイブ メールボックスは、地理的に分散した Microsoft データ センター内の複数のデータベース コピーにレプリケートされ、メッセージング インフラストラクチャに障害が発生した場合のデータ復元機能を提供します。</span><span class="sxs-lookup"><span data-stu-id="20d0e-145">Archive mailboxes in Exchange Online Archiving are replicated to multiple database copies, in geographically dispersed Microsoft data centers, to provide data restoration capability in the event of a messaging infrastructure failure.</span></span> <span data-ttu-id="20d0e-146">大規模な障害の場合、ビジネス継続性管理が開始されます。</span><span class="sxs-lookup"><span data-stu-id="20d0e-146">For large-scale failures, business continuity management is initiated.</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="20d0e-147">機能の可用性</span><span class="sxs-lookup"><span data-stu-id="20d0e-147">Feature availability</span></span>

<span data-ttu-id="20d0e-148">プラン、スタンドアロン オプション、オンプレミス ソリューションの機能の可用性を表示するには、「サービスの説明Exchange Online Archiving[参照してください](exchange-online-archiving-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="20d0e-148">To view feature availability across plans, standalone options, and on-premises solutions, see [Exchange Online Archiving service description](exchange-online-archiving-service-description.md).</span></span>
