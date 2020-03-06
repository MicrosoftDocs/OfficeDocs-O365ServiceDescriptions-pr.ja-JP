---
title: 受信者、ドメイン、および会社の管理
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- recipient-domain-and-company-management-features-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 10812b48-7df5-47e9-b643-dbc3c85d7de0
description: Microsoft Exchange Online Protection (EOP) は、受信者、ドメイン、および会社の情報を管理するためのいくつかの手段を提供します。 管理者は、Exchange 管理センター (EAC) 内で特定の管理タスクを実行し、Microsoft 365 管理センターで実行されたその他の管理タスクを確認できます。
ms.openlocfilehash: 1183a90754edc2bab698fb4d8d8b97acff90370c
ms.sourcegitcommit: b957054b6d0a96dbb2b9ced39b5c9935aa07111c
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/05/2020
ms.locfileid: "42545850"
---
# <a name="recipient-domain-and-company-management"></a><span data-ttu-id="70c25-104">受信者、ドメイン、および会社の管理</span><span class="sxs-lookup"><span data-stu-id="70c25-104">Recipient, domain, and company management</span></span>

<span data-ttu-id="70c25-105">Microsoft Exchange Online Protection (EOP) は、受信者、ドメイン、および会社の情報を管理するためのいくつかの手段を提供します。</span><span class="sxs-lookup"><span data-stu-id="70c25-105">Microsoft Exchange Online Protection (EOP) offers several means of managing your recipient, domain, and company information.</span></span> <span data-ttu-id="70c25-106">管理者は、Exchange 管理センター (EAC) 内で特定の管理タスクを実行し、Microsoft 365 管理センターで実行されたその他の管理タスクを確認できます。</span><span class="sxs-lookup"><span data-stu-id="70c25-106">As an administrator, you can perform certain management tasks within the Exchange admin center (EAC), and verify other management tasks performed in the Microsoft 365 admin center.</span></span>
  
<span data-ttu-id="70c25-107">すべての EOP 機能に関する情報をお探しですか?</span><span class="sxs-lookup"><span data-stu-id="70c25-107">Looking for information about all EOP features?</span></span> <span data-ttu-id="70c25-108">「 [Exchange Online Protection サービスの説明](exchange-online-protection-service-description.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="70c25-108">See the [Exchange Online Protection service description](exchange-online-protection-service-description.md).</span></span>
  
## <a name="mail-recipients"></a><span data-ttu-id="70c25-109">Mail recipients</span><span class="sxs-lookup"><span data-stu-id="70c25-109">Mail recipients</span></span>

<span data-ttu-id="70c25-110">メールの受信者は、メール ユーザーまたはメール グループに分類され、ディレクトリ同期によって管理することも、EAC またはリモート Windows PowerShell で直接管理することもできます。</span><span class="sxs-lookup"><span data-stu-id="70c25-110">Mail recipients are categorized as mail users or groups and can be managed through directory synchronization, directly in the EAC, or via remote Windows PowerShell.</span></span> <span data-ttu-id="70c25-111">社内で受信者を管理している場合は、ディレクトリ同期を実行してメール受信者を EAC に反映させる必要があります。</span><span class="sxs-lookup"><span data-stu-id="70c25-111">If you're managing your recipients on-premises, you must run directory synchronization in order for your mail recipients to be reflected in the EAC.</span></span> <span data-ttu-id="70c25-112">Microsoft 365 管理センターだけで管理されているユーザーは、EAC では表示できませんが、EAC の管理者の役割グループのメンバーシップに追加または削除することができます。</span><span class="sxs-lookup"><span data-stu-id="70c25-112">Users managed solely in the Microsoft 365 admin center aren't viewable in the EAC, but they can be added to or removed from membership in an administrator role group in the EAC.</span></span> <span data-ttu-id="70c25-113">EOP の受信者の詳細については、「[EOP で受信者を管理する](https://go.microsoft.com/fwlink/p/?LinkId=280011)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="70c25-113">For more information about recipients in EOP, see [Recipients in EOP](https://go.microsoft.com/fwlink/p/?LinkId=280011).</span></span>
  
## <a name="admin-role-group-permissions"></a><span data-ttu-id="70c25-114">Admin role group permissions</span><span class="sxs-lookup"><span data-stu-id="70c25-114">Admin role group permissions</span></span>

<span data-ttu-id="70c25-p105">EOP では、管理役割の構成のみが可能です。EAC では、既定の管理役割グループに対してユーザーを直接、追加または削除できます。RBAC のカスタマイズはできません。詳細については、「[EOP で管理役割グループのアクセス許可を管理する](https://go.microsoft.com/fwlink/p/?LinkId=282238)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="70c25-p105">In EOP, you can configure administrative roles only. Users can be added and removed from default admin role groups directly in the EAC. No RBAC customization is available. For more information, see [Manage Admin Role Group Permissions in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282238).</span></span>
  
## <a name="domain-management"></a><span data-ttu-id="70c25-119">Domain management</span><span class="sxs-lookup"><span data-stu-id="70c25-119">Domain management</span></span>

<span data-ttu-id="70c25-120">管理対象ドメインは、EOP によって保護されているドメインです。</span><span class="sxs-lookup"><span data-stu-id="70c25-120">Managed domains are domains that are protected by EOP.</span></span> <span data-ttu-id="70c25-121">EAC では、管理対象ドメインの表示とドメインの種類の編集ができます。</span><span class="sxs-lookup"><span data-stu-id="70c25-121">Managed domains can be viewed and domain types can be edited in the EAC.</span></span> <span data-ttu-id="70c25-122">ドメインのプロビジョニングと管理は、Microsoft 365 管理センターで行われ、変更が EAC に反映されます。</span><span class="sxs-lookup"><span data-stu-id="70c25-122">Domain provisioning and management occurs in the Microsoft 365 admin center and changes are reflected in the EAC.</span></span> <span data-ttu-id="70c25-123">詳細については、「[EOP で承認済みドメインを管理する](https://go.microsoft.com/fwlink/p/?LinkId=282239)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="70c25-123">For more information, see [View or Edit Managed Domains in EOP](https://go.microsoft.com/fwlink/p/?LinkId=282239).</span></span>
  
## <a name="match-subdomains"></a><span data-ttu-id="70c25-124">一致サブドメイン</span><span class="sxs-lookup"><span data-stu-id="70c25-124">Match subdomains</span></span>

<span data-ttu-id="70c25-p107">EOP では、管理対象ドメインのサブドメインへのメール フローを有効にできます。詳細については、「[EOP でサブドメインの電子メール フローを有効にする](https://go.microsoft.com/fwlink/p/?LinkId=397213)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="70c25-p107">In EOP, you can enable mail flow to subdomains of a managed domain. For more information, see [Enable Email Flow for Subdomains in EOP](https://go.microsoft.com/fwlink/p/?LinkId=397213).</span></span> 
  
## <a name="directory-based-edge-blocking-dbeb"></a><span data-ttu-id="70c25-127">Directory Based Edge Blocking (DBEB)</span><span class="sxs-lookup"><span data-stu-id="70c25-127">Directory Based Edge Blocking (DBEB)</span></span>

<span data-ttu-id="70c25-p108">ディレクトリ ベースのエッジ ブロック機能では、サービス ネットワーク境界で無効な受信者宛てのメッセージを拒否することができます。管理者は DBEB を使用することにより、メールが有効な受信者を Office 365 に追加したり、Office 365 内に存在しない電子メール アドレスに送信されたすべてのメッセージをブロックしたりすることができます。メッセージの送信先が Office 365 内に存在する有効なメール アドレスの場合、そのメッセージはサービスの残りのフィルター層 (マルウェア対策、スパム対策、トランスポート ルールなど) を通ります。宛先のアドレスが存在しない場合、メッセージはフィルターを適用する前にブロックされ、送信者には、メッセージが配信されなかったことを通知する配信不能レポート (NDR) が送信されます。</span><span class="sxs-lookup"><span data-stu-id="70c25-p108">The Directory Based Edge Blocking feature lets you reject messages for invalid recipients at the service network perimeter. DBEB lets admins add mail-enabled recipients to Office 365 and block all messages sent to email addresses that aren't present in Office 365. If a message is sent to a valid email address present in Office 365, the message continues through the rest of the service filtering layers (anti-malware, anti-spam, transport rules). If the address is not present, the service blocks the message before filtering even occurs, and a non-delivery report (NDR) is sent to the sender informing them that their message was not delivered.</span></span> 
  
<span data-ttu-id="70c25-p109">DBEB を有効にするには、ユーザーおよびドメインの構成が必要です。詳細については、「[ディレクトリ ベースのエッジ ブロックを使用して無効な受信者に送信されたメッセージを拒否する](https://go.microsoft.com/fwlink/p/?LinkId=390676)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="70c25-p109">Enabling DBEB requires some user and domain configuration. For more information, see [Use Directory Based Edge Blocking to Reject Messages Sent to Invalid Recipients](https://go.microsoft.com/fwlink/p/?LinkId=390676).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="70c25-134">機能の可用性</span><span class="sxs-lookup"><span data-stu-id="70c25-134">Feature availability</span></span>

<span data-ttu-id="70c25-135">Office 365 プラン、スタンドアロンのオプション、オンプレミスソリューション全体の機能の可用性を表示するには、「 [Exchange Online Protection サービスの説明](exchange-online-protection-service-description.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="70c25-135">To view feature availability across Office 365 plans, standalone options, and on-premises solutions, see [Exchange Online Protection service description](exchange-online-protection-service-description.md).</span></span>
