---
title: Exchange Online Archiving のクライアント機能
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
audience: ITPro
ms.topic: reference
f1_keywords:
- clients-and-devices-in-exchange-online-archiving
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: c8d5f97a-607f-4949-a4f7-0b9e3b246851
description: Microsoft Exchange Online アーカイブを使用すると、ユーザーはさまざまなデバイスやプラットフォームから自分のアーカイブメールボックスに接続することができます。 ユーザーのアーカイブへのすべてのネットワーク接続がインターネット経由で行われるため、仮想プライベート ネットワーク (VPN) 接続は必要ありません。 組織は、社内のクライアント アクセス サーバーを公開して、VPN 接続がなくてもユーザーが Outlook Anywhere を使用してプライマリ メールボックスにアクセスできるようにできます。 社内サーバーに配置されたユーザーのプライマリ メールボックスにアクセスするのに VPN アクセスが必要な場合も、この要件に変わりはありません。
ms.openlocfilehash: 616de5cb187f74b048d14770abb8fe640d0782d3
ms.sourcegitcommit: 15e92292209454f6778bfef26ecab96bfc71ef5f
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 05/22/2019
ms.locfileid: "34341846"
---
# <a name="client-features-in-exchange-online-archiving"></a><span data-ttu-id="c951e-106">Exchange Online Archiving のクライアント機能</span><span class="sxs-lookup"><span data-stu-id="c951e-106">Client Features in Exchange Online Archiving</span></span>

<span data-ttu-id="c951e-107">Microsoft Exchange Online アーカイブを使用すると、ユーザーはさまざまなデバイスやプラットフォームから自分のアーカイブメールボックスに接続することができます。</span><span class="sxs-lookup"><span data-stu-id="c951e-107">Microsoft Exchange Online Archiving enables users to connect to their archive mailboxes from a variety of devices and platforms.</span></span> <span data-ttu-id="c951e-108">ユーザーのアーカイブへのすべてのネットワーク接続がインターネット経由で行われるため、仮想プライベート ネットワーク (VPN) 接続は必要ありません。</span><span class="sxs-lookup"><span data-stu-id="c951e-108">All network connectivity to the user's archive occurs over the Internet, and virtual private network (VPN) connections are not required.</span></span> <span data-ttu-id="c951e-109">組織は、社内のクライアント アクセス サーバーを公開して、VPN 接続がなくてもユーザーが Outlook Anywhere を使用してプライマリ メールボックスにアクセスできるようにできます。</span><span class="sxs-lookup"><span data-stu-id="c951e-109">Organizations can publish an on-premises Client Access server to allow users to access their primary mailbox using Outlook Anywhere, without requiring a VPN connection.</span></span> <span data-ttu-id="c951e-110">社内サーバーに配置されたユーザーのプライマリ メールボックスにアクセスするのに VPN アクセスが必要な場合も、この要件に変わりはありません。</span><span class="sxs-lookup"><span data-stu-id="c951e-110">If VPN access is required to access the user's primary mailbox located on an on-premises server, this requirement does not change.</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="c951e-111">Microsoft は、Exchange Online Archiving サービスの正常性に悪影響を及ぼすクライアント ソフトウェアからの接続をブロックまたは制限する権利を有します。</span><span class="sxs-lookup"><span data-stu-id="c951e-111">Microsoft reserves the right to block or throttle connections from any client software that negatively impacts the health of the Exchange Online Archiving service.</span></span> 
  
## <a name="microsoft-outlook"></a><span data-ttu-id="c951e-112">Microsoft Outlook</span><span class="sxs-lookup"><span data-stu-id="c951e-112">Microsoft Outlook</span></span>

<span data-ttu-id="c951e-p103">Microsoft Outlook は、予定表作成、連絡先、タスクのサポートを含む多機能の電子メール プログラムです。Exchange Online Archiving は、Outlook 2013、Outlook 2010、Outlook 2007 をサポートします。主な機能には以下のものがあります。</span><span class="sxs-lookup"><span data-stu-id="c951e-p103">Microsoft Outlook is a rich email program that includes support for calendaring, contacts, and tasks. Exchange Online Archiving supports Outlook 2013, Outlook 2010, and Outlook 2007. Key features include:</span></span>
  
- <span data-ttu-id="c951e-p104">**Outlook Anywhere** Outlook Anywhere を使用すれば、Outlook ユーザーは、VPN 接続がなくても、インターネット経由で Exchange Server や Exchange Online Archiving に接続できます。Outlook と Exchange Online Archiving 間の通信は、RPC-over-HTTP Windows ネットワーク コンポーネントを使用し、SSL で保護されたトンネルを介して行われます。</span><span class="sxs-lookup"><span data-stu-id="c951e-p104">**Outlook Anywhere** Outlook Anywhere lets Outlook users connect to Exchange Server and Exchange Online Archiving over the Internet with no need for a VPN connection. Communication between Outlook and Exchange Online Archiving occurs via an SSL-secured tunnel, using the RPC-over-HTTP Windows networking component.</span></span> 
    
- <span data-ttu-id="c951e-p105">**自動検出** Exchange 自動検出サービスは、Exchange Online Archiving と連動するように Outlook を自動的に構成します。Outlook ユーザーは、電子メール アドレスとパスワードを使って初めてサインインしたときに (および、その後は一定間隔で)、自動検出によって直接 Exchange から必要なプロファイルを受け取ることができます。</span><span class="sxs-lookup"><span data-stu-id="c951e-p105">**Autodiscover** The Exchange Autodiscover service automatically configures Outlook to work with Exchange Online Archiving. Autodiscover enables Outlook users to receive their required profile settings directly from Exchange the first time (and at fixed intervals thereafter) that they sign in with their email address and password.</span></span> 
    
<span data-ttu-id="c951e-120">Outlook 2010 以降と Outlook Web App では、アーカイブのすべての機能に加えて、保持ポリシーやアーカイブ ポリシーなどの関連機能もユーザーに提供されます。</span><span class="sxs-lookup"><span data-stu-id="c951e-120">Outlook 2010 and later and Outlook Web App provide users with the full features of the archive, as well as related features like retention and archive policies.</span></span>
  
<span data-ttu-id="c951e-p106">Outlook 2007 はアーカイブの基本的なサポートを提供しますが、一部のアーカイブ機能とコンプライアンス機能が Outlook 2007 では使用できません。たとえば、Outlook 2007 では、ユーザーは、保持ポリシーやアーカイブ ポリシーをメールボックス内のアイテムに適用できません。代わりに、管理者によってプロビジョニングされるポリシーを使用する必要があります。Outlook 2007 ユーザーがアーカイブにアクセスするためには、2011 年 2 月の Office 2007 累積更新プログラムが必要です。</span><span class="sxs-lookup"><span data-stu-id="c951e-p106">Outlook 2007 provides basic support for the archive, but not all archiving and compliance features are available in Outlook 2007. For example, with Outlook 2007, users cannot apply retention or archive policies to items in their mailboxes. They must rely on administrator-provisioned policies instead. Outlook 2007 users require the Office 2007 Cumulative Update for February 2011 to access the archive.</span></span>
  
> [!NOTE]
> <span data-ttu-id="c951e-p107">Outlook は Exchange Online Archiving に付属していません。Microsoft Office 365 ProPlus (Microsoft Outlook を含む) は、一部の Office 365 プランに含まれているほか、個別のサブスクリプションとして購入することもできます。詳細については、「[Office 365 プランのオプション](../office-365-platform-service-description/office-365-plan-options.md)」を参照してください。Office 365 ProPlus の詳細については、「[Office アプリケーション サービスの説明](../office-applications-service-description/office-applications-service-description.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="c951e-p107">Outlook is not provided with Exchange Online Archiving. Microsoft Office 365 ProPlus (which includes Microsoft Outlook) is included in some Office 365 plans and can be purchased as a separate subscription. For more information, see [Office 365 Plan Options](../office-365-platform-service-description/office-365-plan-options.md). For more information about Office 365 ProPlus, see the [Office Applications Service Description](../office-applications-service-description/office-applications-service-description.md).</span></span> 
  
### <a name="clients-supported-by-exchange-online-archiving"></a><span data-ttu-id="c951e-129">Exchange Online Archiving でサポートされているクライアント</span><span class="sxs-lookup"><span data-stu-id="c951e-129">Clients supported by Exchange Online Archiving</span></span>

<span data-ttu-id="c951e-130">下の表に、Exchange Online Archiving でサポートされているクライアントを列挙します。</span><span class="sxs-lookup"><span data-stu-id="c951e-130">The table below lists the clients supported by Exchange Online Archiving:</span></span>
  
|<span data-ttu-id="c951e-131">**クライアント**</span><span class="sxs-lookup"><span data-stu-id="c951e-131">**Client**</span></span>|<span data-ttu-id="c951e-132">**EOA サポート**</span><span class="sxs-lookup"><span data-stu-id="c951e-132">**EOA Support**</span></span>|
|:-----|:-----|
|<span data-ttu-id="c951e-133">Outlook 2010 以降</span><span class="sxs-lookup"><span data-stu-id="c951e-133">Outlook 2010 and later</span></span>  <br/> |<span data-ttu-id="c951e-134">Exchange Online Archiving の最新機能をサポートします。<sup>1</sup></span><span class="sxs-lookup"><span data-stu-id="c951e-134">Supports the latest features in Exchange Online Archiving.<sup>1</sup></span></span> <br/> |
|<span data-ttu-id="c951e-135">Outlook 2007</span><span class="sxs-lookup"><span data-stu-id="c951e-135">Outlook 2007</span></span>  <br/> |<span data-ttu-id="c951e-136">Exchange Online Archiving と一緒に使用するためにサポートされています。<sup>1、2</sup></span><span class="sxs-lookup"><span data-stu-id="c951e-136">Supported for use with Exchange Online Archiving.<sup>1,2</sup></span></span> <br/> |
|<span data-ttu-id="c951e-137">Outlook 2003</span><span class="sxs-lookup"><span data-stu-id="c951e-137">Outlook 2003</span></span>  <br/> |<span data-ttu-id="c951e-138">サポートされていません</span><span class="sxs-lookup"><span data-stu-id="c951e-138">Not supported</span></span>  <br/> |
|<span data-ttu-id="c951e-139">Outlook for Mac 2011</span><span class="sxs-lookup"><span data-stu-id="c951e-139">Outlook for Mac 2011</span></span>  <br/> |<span data-ttu-id="c951e-140">サポートされていません</span><span class="sxs-lookup"><span data-stu-id="c951e-140">Not supported</span></span>  <br/> |
|<span data-ttu-id="c951e-141">Outlook for Mac</span><span class="sxs-lookup"><span data-stu-id="c951e-141">Outlook for Mac</span></span>  <br/> |<span data-ttu-id="c951e-142">サポート対象外 Exchange Online Archiving<sup>3</sup></span><span class="sxs-lookup"><span data-stu-id="c951e-142">Supported for use with Exchange Online Archiving.<sup>3</sup></span></span> <br/> |
|<span data-ttu-id="c951e-143">Microsoft Office Entourage 2008 Web Services Edition</span><span class="sxs-lookup"><span data-stu-id="c951e-143">Microsoft Office Entourage 2008 Web Services Edition</span></span>  <br/> |<span data-ttu-id="c951e-144">サポートされていません</span><span class="sxs-lookup"><span data-stu-id="c951e-144">Not supported</span></span>  <br/> |
|<span data-ttu-id="c951e-145">IMAP と POP</span><span class="sxs-lookup"><span data-stu-id="c951e-145">IMAP and POP</span></span>  <br/> |<span data-ttu-id="c951e-146">サポートされていません</span><span class="sxs-lookup"><span data-stu-id="c951e-146">Not supported</span></span>  <br/> |
|<span data-ttu-id="c951e-147">Exchange ActiveSync (モバイル デバイス)</span><span class="sxs-lookup"><span data-stu-id="c951e-147">Exchange ActiveSync (Mobile devices)</span></span>  <br/> |<span data-ttu-id="c951e-148">サポート対象外</span><span class="sxs-lookup"><span data-stu-id="c951e-148">Not supported</span></span>  <br/> |
   
> [!NOTE]
> <span data-ttu-id="c951e-p108"><sup>1</sup> Microsoft Office Standard に付属の Outlook はサポートされません。詳細については、「 [Outlook の Exchange 機能に関するライセンス要件](https://go.microsoft.com/fwlink/?LinkId=389396)」を参照してください。 > <sup>2</sup> アーカイブ サポートを有効にするには更新プログラムが必要です。Outlook 2007 ユーザーは、保持ポリシーまたはアーカイブ ポリシーを表示することも、アーカイブ メールボックス内のアイテムに適用することもできません。管理者が準備したポリシーに従う必要があります。加えて、Outlook 2007 ユーザーは、オンプレミスのメールボックスとアーカイブを同時に検索できません。 > <sup>3</sup> Outlook 2016 for Mac または Outlook for Mac 以外の Outlook (Outlook 2016 for Windows など) を使用して、フォルダー、予定表アイテム、連絡先、タスク、メモをアーカイブに移動している場合は、Outlook 2016 for Mac または Outlook for Mac を使用してこれらのアイテムをアーカイブに移動したり、アーカイブ メールボックス内のこれらのアイテムを表示することはできません。詳細については、「 [Outlook 2016 for Mac でオンライン アーカイブを使用する](https://support.office.com/en-us/article/Use-your-online-archive-with-Outlook-2016-for-Mac-45b8439c-2982-4b6b-9097-eed71dbfe238))」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="c951e-p108"><sup>1</sup> Outlook included with Microsoft Office Standard is not supported. To learn more, see [License requirements for Personal Archive and retention policies](https://go.microsoft.com/fwlink/?LinkId=389396). > <sup>2</sup> Requires update to enable archiving support. Outlook 2007 users cannot view or apply retention or archive policies to items in their archive mailboxes; they must rely on administrator-provisioned policies. Additionally, Outlook 2007 users cannot search the on-premises mailbox and the archive at the same time. > <sup>3</sup> You can't use Outlook 2016 for Mac or Outlook for Mac to move or copy folders, calendar items, contacts, tasks, or notes to your archive, or view them in the archive mailbox, if the items were previously moved there by using any other version of Outlook (such as Outlook 2016 for Windows). For more information, see [Use your online archive with Outlook 2016 for Mac](https://support.office.com/en-us/article/Use-your-online-archive-with-Outlook-2016-for-Mac-45b8439c-2982-4b6b-9097-eed71dbfe238).</span></span> 
  
## <a name="outlook-web-app"></a><span data-ttu-id="c951e-156">Outlook Web App</span><span class="sxs-lookup"><span data-stu-id="c951e-156">Outlook Web App</span></span>

<span data-ttu-id="c951e-p109">Outlook Web App は、Exchange Online と一緒に使用される Outlook 電子メール プログラムの Web ベース バージョンです。ユーザーは自宅でも、オフィスでも、移動中でも、いつでもインターネットに接続して、Outlook Web App を介して電子メールにアクセスできます。</span><span class="sxs-lookup"><span data-stu-id="c951e-p109">Outlook Web App is a web-based version of the Outlook email program that is used with Exchange Online. Wherever users are connected to the Internet—at home, at the office, or on the road—they can access their email through Outlook Web App.</span></span>
  
<span data-ttu-id="c951e-p110">ユーザーは、オンプレミスの Outlook Web App にサインインすることによって (同じ URL を使用して) アーカイブにアクセスすることができます。アーカイブはプライマリ メールボックスと一緒に Outlook Web App に表示されます。Outlook Web App から直接アーカイブにアクセスする明示的な方法はありません。</span><span class="sxs-lookup"><span data-stu-id="c951e-p110">Users can access their archive by signing in to Outlook Web App on-premises (using the same URL). The archive appears alongside their primary mailbox in Outlook Web App. There is no explicit way to access the archive directly from Outlook Web App.</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="c951e-162">機能の可用性</span><span class="sxs-lookup"><span data-stu-id="c951e-162">Feature Availability</span></span>

<span data-ttu-id="c951e-163">Office 365 のプラン、スタンドアロンのオプション、オンプレミス ソリューション全体の機能の可用性を表示するには、「[Exchange Online Archiving サービスの説明](exchange-online-archiving-service-description.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="c951e-163">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Archiving Service Description](exchange-online-archiving-service-description.md).</span></span>
  

