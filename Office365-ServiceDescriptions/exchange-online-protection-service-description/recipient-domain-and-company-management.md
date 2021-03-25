---
title: Exchange Online Protection の受信者、ドメイン、および会社の管理
ms.author: office365servicedesc
author: pamelaar
audience: ITPro
ms.topic: reference
f1_keywords:
- recipient-domain-and-company-management-features-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 10812b48-7df5-47e9-b643-dbc3c85d7de0
description: この記事では、受信者、ドメイン、および企業の管理について、Microsoft Exchange Onlineを参照してください。
ms.openlocfilehash: a01d572ce239e7d1a6c0c57814fb7494a6670f84
ms.sourcegitcommit: a2b77dae1341753f5f98c3d3b39d70454c3ab05f
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/24/2021
ms.locfileid: "51173722"
---
# <a name="recipient-domain-and-company-management-in-exchange-online-protection"></a><span data-ttu-id="7d1bd-103">Exchange Online Protection の受信者、ドメイン、および会社の管理</span><span class="sxs-lookup"><span data-stu-id="7d1bd-103">Recipient, domain, and company management in Exchange Online Protection</span></span>

<span data-ttu-id="7d1bd-104">Microsoft Exchange Online保護 (EOP) には、受信者、ドメイン、および会社の情報を管理するためのいくつかの手段があります。</span><span class="sxs-lookup"><span data-stu-id="7d1bd-104">Microsoft Exchange Online Protection (EOP) offers several means of managing your recipient, domain, and company information.</span></span> <span data-ttu-id="7d1bd-105">管理者は、Exchange 管理センター (EAC) 内で特定の管理タスクを実行し、Microsoft 365 管理センターで実行される他の管理タスクを確認できます。</span><span class="sxs-lookup"><span data-stu-id="7d1bd-105">As an administrator, you can perform certain management tasks within the Exchange admin center (EAC), and verify other management tasks performed in the Microsoft 365 admin center.</span></span>
  
<span data-ttu-id="7d1bd-106">すべての EOP 機能に関する情報をお探しですか?</span><span class="sxs-lookup"><span data-stu-id="7d1bd-106">Looking for information about all EOP features?</span></span> <span data-ttu-id="7d1bd-107">Exchange [Online Protection サービスの説明を参照してください](exchange-online-protection-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="7d1bd-107">See the [Exchange Online Protection service description](exchange-online-protection-service-description.md).</span></span>
  
## <a name="mail-recipients"></a><span data-ttu-id="7d1bd-108">Mail recipients</span><span class="sxs-lookup"><span data-stu-id="7d1bd-108">Mail recipients</span></span>

<span data-ttu-id="7d1bd-109">メールの受信者は、メール ユーザーまたはメール グループに分類され、ディレクトリ同期によって管理することも、EAC またはリモート Windows PowerShell で直接管理することもできます。</span><span class="sxs-lookup"><span data-stu-id="7d1bd-109">Mail recipients are categorized as mail users or groups and can be managed through directory synchronization, directly in the EAC, or via remote Windows PowerShell.</span></span> <span data-ttu-id="7d1bd-110">社内で受信者を管理している場合は、ディレクトリ同期を実行してメール受信者を EAC に反映させる必要があります。</span><span class="sxs-lookup"><span data-stu-id="7d1bd-110">If you're managing your recipients on-premises, you must run directory synchronization in order for your mail recipients to be reflected in the EAC.</span></span> <span data-ttu-id="7d1bd-111">Microsoft 365 管理センターでのみ管理されているユーザーは、EAC では表示できませんが、EAC の管理者役割グループのメンバーシップに追加または削除できます。</span><span class="sxs-lookup"><span data-stu-id="7d1bd-111">Users managed solely in the Microsoft 365 admin center aren't viewable in the EAC, but they can be added to or removed from membership in an administrator role group in the EAC.</span></span> <span data-ttu-id="7d1bd-112">EOP の受信者の詳細については、「[EOP で受信者を管理する](/microsoft-365/security/office-365-security/manage-recipients-in-eop)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="7d1bd-112">For more information about recipients in EOP, see [Recipients in EOP](/microsoft-365/security/office-365-security/manage-recipients-in-eop).</span></span>
  
## <a name="admin-role-group-permissions"></a><span data-ttu-id="7d1bd-113">Admin role group permissions</span><span class="sxs-lookup"><span data-stu-id="7d1bd-113">Admin role group permissions</span></span>

<span data-ttu-id="7d1bd-p104">EOP では、管理役割の構成のみが可能です。EAC では、既定の管理役割グループに対してユーザーを直接、追加または削除できます。RBAC のカスタマイズはできません。詳細については、「[EOP で管理役割グループのアクセス許可を管理する](/microsoft-365/security/office-365-security/manage-admin-role-group-permissions-in-eop)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="7d1bd-p104">In EOP, you can configure administrative roles only. Users can be added and removed from default admin role groups directly in the EAC. No RBAC customization is available. For more information, see [Manage Admin Role Group Permissions in EOP](/microsoft-365/security/office-365-security/manage-admin-role-group-permissions-in-eop).</span></span>
  
## <a name="domain-management"></a><span data-ttu-id="7d1bd-118">Domain management</span><span class="sxs-lookup"><span data-stu-id="7d1bd-118">Domain management</span></span>

<span data-ttu-id="7d1bd-119">管理対象ドメインは、EOP によって保護されているドメインです。</span><span class="sxs-lookup"><span data-stu-id="7d1bd-119">Managed domains are domains that are protected by EOP.</span></span> <span data-ttu-id="7d1bd-120">EAC では、管理対象ドメインの表示とドメインの種類の編集ができます。</span><span class="sxs-lookup"><span data-stu-id="7d1bd-120">Managed domains can be viewed and domain types can be edited in the EAC.</span></span> <span data-ttu-id="7d1bd-121">ドメインのプロビジョニングと管理は Microsoft 365 管理センターで行われます。変更は EAC に反映されます。</span><span class="sxs-lookup"><span data-stu-id="7d1bd-121">Domain provisioning and management occurs in the Microsoft 365 admin center and changes are reflected in the EAC.</span></span> <span data-ttu-id="7d1bd-122">詳細については、「[EOP で承認済みドメインを管理する](/microsoft-365/security/office-365-security/exchange-online-protection-overview)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="7d1bd-122">For more information, see [View or Edit Managed Domains in EOP](/microsoft-365/security/office-365-security/exchange-online-protection-overview).</span></span>
  
## <a name="match-subdomains"></a><span data-ttu-id="7d1bd-123">一致サブドメイン</span><span class="sxs-lookup"><span data-stu-id="7d1bd-123">Match subdomains</span></span>

<span data-ttu-id="7d1bd-p106">EOP では、管理対象ドメインのサブドメインへのメール フローを有効にできます。詳細については、「[EOP でサブドメインの電子メール フローを有効にする](/microsoft-365/security/office-365-security/mail-flow-in-eop)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="7d1bd-p106">In EOP, you can enable mail flow to subdomains of a managed domain. For more information, see [Enable Email Flow for Subdomains in EOP](/microsoft-365/security/office-365-security/mail-flow-in-eop).</span></span> 
  
## <a name="directory-based-edge-blocking-dbeb"></a><span data-ttu-id="7d1bd-126">Directory Based Edge Blocking (DBEB)</span><span class="sxs-lookup"><span data-stu-id="7d1bd-126">Directory Based Edge Blocking (DBEB)</span></span>

<span data-ttu-id="7d1bd-127">ディレクトリ ベースのエッジ ブロック機能では、サービス ネットワーク境界で無効な受信者宛てのメッセージを拒否することができます。</span><span class="sxs-lookup"><span data-stu-id="7d1bd-127">The Directory Based Edge Blocking feature lets you reject messages for invalid recipients at the service network perimeter.</span></span> <span data-ttu-id="7d1bd-128">DBEB を使用すると、管理者はメールが有効な受信者を Microsoft に追加し、Microsoft に存在しない電子メール アドレスに送信されるメッセージをブロックできます。</span><span class="sxs-lookup"><span data-stu-id="7d1bd-128">DBEB lets admins add mail-enabled recipients to Microsoft and block all messages sent to email addresses that aren't present in Microsoft.</span></span> <span data-ttu-id="7d1bd-129">メッセージが Microsoft に存在する有効な電子メール アドレスに送信された場合、メッセージはサービス フィルターレイヤーの残りの部分 (マルウェア対策、スパム対策、トランスポート ルール) を通じて続行されます。</span><span class="sxs-lookup"><span data-stu-id="7d1bd-129">If a message is sent to a valid email address present in Microsoft, the message continues through the rest of the service filtering layers (anti-malware, anti-spam, transport rules).</span></span> <span data-ttu-id="7d1bd-130">宛先のアドレスが存在しない場合、メッセージはフィルターを適用する前にブロックされ、送信者には、メッセージが配信されなかったことを通知する配信不能レポート (NDR) が送信されます。</span><span class="sxs-lookup"><span data-stu-id="7d1bd-130">If the address is not present, the service blocks the message before filtering even occurs, and a non-delivery report (NDR) is sent to the sender informing them that their message was not delivered.</span></span> 
  
<span data-ttu-id="7d1bd-p108">DBEB を有効にするには、ユーザーおよびドメインの構成が必要です。詳細については、「[ディレクトリ ベースのエッジ ブロックを使用して無効な受信者に送信されたメッセージを拒否する](/exchange/mail-flow-best-practices/use-directory-based-edge-blocking)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="7d1bd-p108">Enabling DBEB requires some user and domain configuration. For more information, see [Use Directory Based Edge Blocking to Reject Messages Sent to Invalid Recipients](/exchange/mail-flow-best-practices/use-directory-based-edge-blocking).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="7d1bd-133">機能の可用性</span><span class="sxs-lookup"><span data-stu-id="7d1bd-133">Feature availability</span></span>

<span data-ttu-id="7d1bd-134">プラン、スタンドアロン オプション、オンプレミス ソリューションの機能の可用性を表示するには、「Exchange Online Protection サービスの説明」 [を参照してください](exchange-online-protection-service-description.md)。</span><span class="sxs-lookup"><span data-stu-id="7d1bd-134">To view feature availability across plans, standalone options, and on-premises solutions, see [Exchange Online Protection service description](exchange-online-protection-service-description.md).</span></span>