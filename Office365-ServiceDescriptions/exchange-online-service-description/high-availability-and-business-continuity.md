---
title: 高可用性とビジネス継続性
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-high-availability-and-business-continuity
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 7b03465e-3b9c-4500-8956-a83377f4c2c3
description: Microsoft Exchange Online は、組織の電子メールインフラストラクチャに対して広範な保存と回復のサポートを提供します。 これには、データ センターでのメールボックス レプリケーションと、削除済みメールボックスと削除済みアイテムを復元する機能が含まれます。
ms.openlocfilehash: d9aac8e2843e085bea9aa4c1e3edc0dbb0789130
ms.sourcegitcommit: 15e92292209454f6778bfef26ecab96bfc71ef5f
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/22/2019
ms.locfileid: "34342886"
---
# <a name="high-availability-and-business-continuity"></a><span data-ttu-id="ba8ce-104">高可用性とビジネス継続性</span><span class="sxs-lookup"><span data-stu-id="ba8ce-104">High Availability and Business Continuity</span></span>

<span data-ttu-id="ba8ce-105">Microsoft Exchange Online は、組織の電子メールインフラストラクチャに対して広範な保存と回復のサポートを提供します。</span><span class="sxs-lookup"><span data-stu-id="ba8ce-105">Microsoft Exchange Online offers extensive retention and recovery support for an organization's email infrastructure.</span></span> <span data-ttu-id="ba8ce-106">これには、データ センターでのメールボックス レプリケーションと、削除済みメールボックスと削除済みアイテムを復元する機能が含まれます。</span><span class="sxs-lookup"><span data-stu-id="ba8ce-106">This includes mailbox replication at data centers and the ability to restore deleted mailboxes and deleted items.</span></span>
  
## <a name="mailbox-replication-at-data-centers"></a><span data-ttu-id="ba8ce-107">データ センターでのメールボックス レプリケーション</span><span class="sxs-lookup"><span data-stu-id="ba8ce-107">Mailbox replication at data centers</span></span>

<span data-ttu-id="ba8ce-p103">Exchange Online メールボックスは、地理的に分散した Microsoft データ センター内で、複数のデータベース コピーに継続的にレプリケートされ、ローカルのメッセージング インフラストラクチャに障害が発生した場合にデータ復元機能を提供します。大規模な障害の場合、サービス継続性管理手順が開始されます。</span><span class="sxs-lookup"><span data-stu-id="ba8ce-p103">Exchange Online mailboxes are continuously replicated to multiple database copies, in geographically dispersed Microsoft data centers, to provide data restoration capability in the event of a local messaging infrastructure failure. For large-scale failures, service continuity management procedures are initiated.</span></span>
  
<span data-ttu-id="ba8ce-p104">Microsoft がデータを保護する方法の詳細については、「[Office 365 セキュリティ センター](https://go.microsoft.com/fwlink/p/?LinkId=299135)」をご覧ください。21Vianet が運用している Office 365 をご使用の方は、「[21Vianet セキュリティ センター](http://www.21vbluecloud.com/office365/trustcenter/onlineservices.mdl)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="ba8ce-p104">For more information about how Microsoft protects your data, see [Office 365 Trust Center](https://go.microsoft.com/fwlink/p/?LinkId=299135). If you are using Office 365 operated by 21Vianet, see the [21Vianet Trust Center](http://www.21vbluecloud.com/office365/trustcenter/onlineservices.mdl).</span></span>
  
## <a name="deleted-mailbox-recovery"></a><span data-ttu-id="ba8ce-112">削除済みメールボックスの回復</span><span class="sxs-lookup"><span data-stu-id="ba8ce-112">Deleted mailbox recovery</span></span>

<span data-ttu-id="ba8ce-113">管理者は、Microsoft 365 管理センターを使用して、対応するユーザーアカウントを削除したり、Exchange Online ライセンスを削除したり、リモート Windows PowerShell で**メールボックスの削除**コマンドレットを使用して、exchange online メールボックスを削除したりできます。</span><span class="sxs-lookup"><span data-stu-id="ba8ce-113">Administrators can delete Exchange Online mailboxes by using the Microsoft 365 admin center to delete the corresponding user account or remove the Exchange Online license, or by using the **Remove-Mailbox** cmdlet in remote Windows PowerShell.</span></span> <span data-ttu-id="ba8ce-114">メールボックスが削除されると、Exchange Online がメールボックスとその内容を既定で 30 日間保持します。</span><span class="sxs-lookup"><span data-stu-id="ba8ce-114">When a mailbox is deleted, Exchange Online retains the mailbox and its contents for 30 days by default.</span></span> <span data-ttu-id="ba8ce-115">30 日後、メールボックスは回復不可能になります。</span><span class="sxs-lookup"><span data-stu-id="ba8ce-115">After 30 days, the mailbox is not recoverable.</span></span> <span data-ttu-id="ba8ce-116">回復したメールボックスには、削除された時点でメールボックスに格納されていたすべてのデータが含まれます。</span><span class="sxs-lookup"><span data-stu-id="ba8ce-116">A recovered mailbox contains all of the data stored in it at the time it was deleted.</span></span> <span data-ttu-id="ba8ce-117">管理者は、Microsoft 365 管理センターを使用して、保存期間内に削除されたメールボックスを回復できます。</span><span class="sxs-lookup"><span data-stu-id="ba8ce-117">Administrators can recover a deleted mailbox within the retention period by using the Microsoft 365 admin center.</span></span> <span data-ttu-id="ba8ce-118">削除されたメールボックスを回復するには、管理者が対応する Office 365 ユーザー アカウントを復元するか、Exchange Online ライセンスをユーザー アカウントに割り当て直す必要があります。</span><span class="sxs-lookup"><span data-stu-id="ba8ce-118">To recover a deleted mailbox, administrators have to restore the corresponding Office 365 user account or reassign an Exchange Online license to the user account.</span></span> <span data-ttu-id="ba8ce-119">詳細については、「 [Exchange Online でユーザー メールボックスを削除または復元する](https://go.microsoft.com/fwlink/p/?LinkId=286992)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="ba8ce-119">For more information, see [Delete or Restore User Mailboxes in Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=286992).</span></span>
  
## <a name="deleted-item-recovery"></a><span data-ttu-id="ba8ce-120">削除済みアイテムの回復</span><span class="sxs-lookup"><span data-stu-id="ba8ce-120">Deleted item recovery</span></span>

<span data-ttu-id="ba8ce-p106">Exchange Online では、削除済みアイテム フォルダーを含む電子メール フォルダーから削除したアイテムを回復できます。削除されたアイテムは、ユーザーの削除済みアイテム フォルダーに保持されます。削除済みアイテム フォルダー内のアイテムは、ユーザーが手動で削除するか、保持ポリシーによって自動的に削除されるまで、フォルダーに保持されたままになります。管理者は、EAC またはリモート Windows PowerShell を使用して、保持ポリシーをカスタマイズできます。</span><span class="sxs-lookup"><span data-stu-id="ba8ce-p106">Exchange Online enables users to restore items they have deleted from any email folder, including the Deleted Items folder. When an item is deleted, it's kept in a user's Deleted Items folder. It remains there until it's either manually removed by the user or automatically removed by retention policies. Administrators can customize retention policies in the EAC or by using remote Windows PowerShell.</span></span>
  
<span data-ttu-id="ba8ce-p107">削除済みアイテム フォルダーからアイテムが削除された後、さらに 14 日間は回復可能なアイテム フォルダーに保持され、その後に完全に削除されますが、管理者がリモート Windows PowerShell を使用してこの期間を延長した場合は、最大で 30 日間保持できます。ユーザーはこの期間中に、Outlook Web App または Outlook の削除済みアイテムの復元機能を使用してアイテムを復元できます。詳細については、「[Exchange Online メールボックスの完全に削除したアイテムの保持期間を変更する](https://go.microsoft.com/fwlink/p/?LinkId=286940)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="ba8ce-p107">After an item has been removed from the Deleted Items folder, it's kept in a Recoverable Items folder for an additional 14 days before being permanently removed, but administrators can increase this to a maximum of 30 days by using remote Windows PowerShell. Users can recover the item during this time period by using the Recover Deleted Items feature in Outlook Web App or Outlook. Learn how to [change the deleted item retention period](https://go.microsoft.com/fwlink/p/?LinkId=286940).</span></span>
  
<span data-ttu-id="ba8ce-p108">ユーザーが手動で回復可能なアイテム フォルダーからアイテムを削除した場合、管理者は同じ期間内であれば単一アイテムの回復機能とリモート Windows PowerShell を使用してアイテムを復元できます。既定では、メールボックスの作成時に単一アイテムの回復機能は有効になっています。詳細については、「[メールボックスの単一アイテムの回復を有効または無効にする](https://go.microsoft.com/fwlink/p/?LinkID=286941)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="ba8ce-p108">If a user has manually purged an item from the Recoverable Items folder, an administrator can recover the item within the same time period by using the Single Item Recovery feature with remote Windows PowerShell. By default, Single Item Recovery is enabled when a mailbox is created. To learn more, see [Enable or disable single item recovery for a mailbox](https://go.microsoft.com/fwlink/p/?LinkID=286941).</span></span>
  
<span data-ttu-id="ba8ce-p109">30 日より長い間メッセージを回復可能なアイテム フォルダーに保持するには、組織で、電子メールの保存期間を延長するか、時間ベースのインプレース保持を実装します。詳細については、「[インプレース保持と訴訟ホールド](https://go.microsoft.com/fwlink/p/?LinkId=271746)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="ba8ce-p109">To preserve messages for longer than 30 days in the Recoverable Items folder, organizations can implement longer-term email preservation or time-based In-Place Holds. Learn more about [placing a mailbox on In-Place Hold](https://go.microsoft.com/fwlink/p/?LinkId=271746).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="ba8ce-133">機能の可用性</span><span class="sxs-lookup"><span data-stu-id="ba8ce-133">Feature Availability</span></span>

<span data-ttu-id="ba8ce-134">Office 365 のプラン、スタンドアロンのオプション、オンプレミス ソリューション全体の機能の可用性を表示するには、「[Exchange Online サービスの説明](exchange-online-service-description.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="ba8ce-134">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  

