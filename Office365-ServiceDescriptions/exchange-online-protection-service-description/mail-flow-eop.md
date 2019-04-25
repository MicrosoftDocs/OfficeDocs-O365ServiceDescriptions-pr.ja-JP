---
title: メール フロー [EOP]
ms.author: sharik
author: skjerland
manager: mnirkhe
ms.date: 6/13/2018
ms.audience: ITPro
ms.topic: reference
f1_keywords:
- mail-flow-in-eop
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: 214e5779-35c6-4912-af0c-8b0552239f13
description: Office 365 を使用するほとんどの組織では、Microsoft がメールボックスをホストし、メールフローを処理します。 Office 365 によってすべてのメールボックスとフィルターを管理するのが最も簡単な構成方法です。 ただし、自分たちのメールボックスすべてをオンプレミスで保持するという業務上のニーズがある組織もあります。 Exchange Online Protection (EOP) を使用すると、そのニーズを満たすことができ、クラウドでウィルス対策とスパム対策のメール処理を行えます。 詳細について、および EOP を購入するには、Exchange Online Protection にアクセスしてください。
ms.openlocfilehash: 0e9e5fffaa88b2ec654cb90dc5d432875336328e
ms.sourcegitcommit: 830694c729ab53fcc8518b0cdd5322b322514431
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 04/25/2019
ms.locfileid: "33244913"
---
# <a name="mail-floweop"></a><span data-ttu-id="71d50-107">メール フロー [EOP]</span><span class="sxs-lookup"><span data-stu-id="71d50-107">Mail Flow[EOP]</span></span>

<span data-ttu-id="71d50-108">Office 365 を使用するほとんどの組織では、Microsoft がメールボックスをホストし、メールフローを処理します。</span><span class="sxs-lookup"><span data-stu-id="71d50-108">For most organizations that use Office 365, we host your mailboxes and take care of mail flow.</span></span> <span data-ttu-id="71d50-109">Office 365 によってすべてのメールボックスとフィルターを管理するのが最も簡単な構成方法です。</span><span class="sxs-lookup"><span data-stu-id="71d50-109">It's the simplest configuration and means that Office 365 manages all mailboxes and filtering.</span></span> <span data-ttu-id="71d50-110">ただし、自分たちのメールボックスすべてをオンプレミスで保持するという業務上のニーズがある組織もあります。</span><span class="sxs-lookup"><span data-stu-id="71d50-110">However, some organizations have a business need to keep all their mailboxes on premises.</span></span> <span data-ttu-id="71d50-111">Exchange Online Protection (EOP) を使用すると、そのニーズを満たすことができ、クラウドでウィルス対策とスパム対策のメール処理を行えます。</span><span class="sxs-lookup"><span data-stu-id="71d50-111">Exchange Online Protection (EOP) enables you to do that and provides antivirus and anti-spam mail processing in the cloud.</span></span> <span data-ttu-id="71d50-112">詳細について、および EOP を購入するには、[Exchange Online Protection](https://products.office.com/en-us/exchange/exchange-email-security-spam-protection) にアクセスしてください。</span><span class="sxs-lookup"><span data-stu-id="71d50-112">For more information and to purchase EOP, go to [Exchange Online Protection](https://products.office.com/en-us/exchange/exchange-email-security-spam-protection).</span></span>
  
<span data-ttu-id="71d50-p103">ドメイン管理や、ディレクトリ ベースのエッジ ブロック (DBEB) に関する詳細情報は、「[受信者、ドメイン、および会社の管理](recipient-domain-and-company-management.md)」を参照してください。EOP のすべての機能についての詳細は、「[Exchange Online Protection サービスの説明](exchange-online-protection-service-description.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="71d50-p103">Looking for information about domain management or Directory Based Edge Blocking (DBEB)? See [Recipient, Domain, and Company Management](recipient-domain-and-company-management.md). To learn more about all EOP features, see the [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>
  
## <a name="routing-email-between-office-365-and-your-own-email-servers"></a><span data-ttu-id="71d50-116">Office 365 とご使用の電子メール サーバー間で電子メールをルーティングする</span><span class="sxs-lookup"><span data-stu-id="71d50-116">Routing email between Office 365 and your own email servers</span></span>
<span data-ttu-id="71d50-117"><a name="BKMK_outboundmailrouting"> </a></span><span class="sxs-lookup"><span data-stu-id="71d50-117"></span></span>

<span data-ttu-id="71d50-p104">Office 365 (Exchange Online または EOP を含む) と SMTP ベースの電子メール サーバー (Exchange など) の間でメール フローを有効にするようにコネクタを構成できます。詳細については、「[Do I need a connector](http://technet.microsoft.com/library/16731ae9-c909-49dd-bffc-a46e6151fc29.aspx)?」および「[Set up connectors to route mail between Office 365 and your own email servers](http://technet.microsoft.com/library/2e93fd60-a5ef-4e64-8e62-2b862b2d1033.aspx)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="71d50-p104">You can configure a connector to enable mail flow between Office 365 (including Exchange Online or EOP) and an SMTP-based email server such as Exchange. For details about this, see [Do I need a connector](http://technet.microsoft.com/library/16731ae9-c909-49dd-bffc-a46e6151fc29.aspx)? And [Set up connectors to route mail between Office 365 and your own email servers](http://technet.microsoft.com/library/2e93fd60-a5ef-4e64-8e62-2b862b2d1033.aspx).</span></span>
  
## <a name="secure-messaging-with-a-trusted-partner"></a><span data-ttu-id="71d50-121">Secure messaging with a trusted partner</span><span class="sxs-lookup"><span data-stu-id="71d50-121">Secure messaging with a trusted partner</span></span>
<span data-ttu-id="71d50-122"><a name="BKMK_securemessagingwithatrustedpartner"> </a></span><span class="sxs-lookup"><span data-stu-id="71d50-122"></span></span>

<span data-ttu-id="71d50-p105">EOP のお客様は、Office 365 コネクタを使用して、信頼できるパートナーとのセキュリティで保護されたメール フローを設定することができます。Office 365 は、トランスポート層セキュリティ (TLS) 経由のセキュリティで保護された通信をサポートします。コネクタを作成して、TLS による暗号化を適用することができます。[TLS](https://technet.microsoft.com/en-us/library/mt163898.aspx) は、インターネット上の通信にセキュリティを提供する暗号化プロトコルです。コネクタを使用すると、自己署名証明書または証明機関 (CA) 検証の証明書を使用した受信 TLS と送信 TLS の両方を強制するよう構成できます。パートナー組織のメールの送信元のドメイン名または IP アドレスの範囲を指定するなど、他のセキュリティ制限を適用することもできます。</span><span class="sxs-lookup"><span data-stu-id="71d50-p105">As an EOP customer, you can set up secure mail flow with a trusted partner by using Office 365 connectors. Office 365 supports secure communication through Transport Layer Security (TLS), and you can create a connector to enforce encryption via TLS. [TLS](https://technet.microsoft.com/en-us/library/mt163898.aspx) is a cryptographic protocol that provides security for communications over the Internet. By using connectors, you can configure both forced incoming and outgoing TLS using self-signed or certification authority (CA)-validated certificates. You can also apply other security restrictions, such as specifying domain names or IP address ranges from which your partner organization sends mail.</span></span> 
  
<span data-ttu-id="71d50-128">詳細については、「[パートナー組織とのセキュリティで保護されたメール フロー用のコネクタを設定する](https://technet.microsoft.com/en-us/library/dn751021%28v=exchg.150%29.aspx)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="71d50-128">For more information, see [Set up connectors for secure mail flow with a partner organization](https://technet.microsoft.com/en-us/library/dn751021%28v=exchg.150%29.aspx).</span></span>
  
## <a name="safe-listing-a-partners-ip-address"></a><span data-ttu-id="71d50-129">パートナーの IP アドレスのセーフ リスト</span><span class="sxs-lookup"><span data-stu-id="71d50-129">Safe listing a partner's IP address</span></span>
<span data-ttu-id="71d50-130"><a name="BKMK_safelistingapartnersipaddress"> </a></span><span class="sxs-lookup"><span data-stu-id="71d50-130"></span></span>

<span data-ttu-id="71d50-p106">信頼できるパートナーの IP アドレスをセーフ リストに追加して、そこから自分宛てに送信されるメッセージにスパム フィルター処理を施さないようにすることができます。そのためには、接続フィルターの IP 許可一覧を使います。詳細については、「[接続フィルター ポリシーを構成する](https://go.microsoft.com/fwlink/p/?LinkID=287108)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="71d50-p106">You can add a trusted partner's IP address to a safe list to ensure that messages they send to you are not subject to spam filtering. To do this, you can use the connection filter's IP Allow list. For more information, see [Configure the connection filter policy](https://go.microsoft.com/fwlink/p/?LinkID=287108).</span></span>
  
## <a name="conditional-mail-routing"></a><span data-ttu-id="71d50-134">条件付きメール ルーティング</span><span class="sxs-lookup"><span data-stu-id="71d50-134">Conditional mail routing</span></span>
<span data-ttu-id="71d50-135"><a name="BKMK_conditionalmailrouting"> </a></span><span class="sxs-lookup"><span data-stu-id="71d50-135"></span></span>

<span data-ttu-id="71d50-p107">条件に基づいてメールを特定のサイトにルーティングするためのトランスポート ルールを使ってコネクタを構成できます。詳しくは、「[Scenario: Conditional email routing](http://technet.microsoft.com/library/82d105e2-e955-4e03-99c3-3314a5d21a4c.aspx)」をご覧ください。</span><span class="sxs-lookup"><span data-stu-id="71d50-p107">You can configure a connector with a Transport rule that routes mail to a specific site, based on conditions. For more information, see [Scenario: Conditional email routing](http://technet.microsoft.com/library/82d105e2-e955-4e03-99c3-3314a5d21a4c.aspx).</span></span>
  
## <a name="hybrid-mail-routing"></a><span data-ttu-id="71d50-138">Hybrid mail routing</span><span class="sxs-lookup"><span data-stu-id="71d50-138">Hybrid mail routing</span></span>
<span data-ttu-id="71d50-139"><a name="BKMK_hybridmailrouting"> </a></span><span class="sxs-lookup"><span data-stu-id="71d50-139"></span></span>

<span data-ttu-id="71d50-p108">ハイブリッドとは、メールボックスの一部は社内でホストし、一部はクラウド (Exchange Online) でホストすることを意味します。(オンプレミスの) スタンドアロン展開からハイブリッド展開に移行できます。</span><span class="sxs-lookup"><span data-stu-id="71d50-p108">Hybrid means that you host a portion of your mailboxes on premises, and a portion in the cloud (Exchange Online). You can move from a standalone (on-premises) deployment to a hybrid deployment.</span></span>
  
<span data-ttu-id="71d50-p109">ハイブリッド展開を使用している場合は、EOP を使用してクラウド メールボックスと社内メールボックスを保護できます。社内メールボックスを EOP で保護する場合はスタンドアロン ライセンスが必要です。ハイブリッド展開でのメール ルーティングの詳細については、「[Exchange ハイブリッド展開でのトランスポート ルーティング](https://go.microsoft.com/fwlink/p/?LinkId=271757)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="71d50-p109">If you have a hybrid deployment, you can protect your cloud and on-premises mailboxes with EOP. Standalone licenses are required for on-premises mailboxes, when they are protected by EOP. For more information about mail routing in a hybrid deployment, see [Transport routing in Exchange hybrid deployments](https://go.microsoft.com/fwlink/p/?LinkId=271757).</span></span>
  
<span data-ttu-id="71d50-145">「[Microsoft Exchange Server 展開アシスタント](https://go.microsoft.com/fwlink/p/?LinkId=287036)」でも、ハイブリッド展開のプロビジョニングとハイブリッド メッセージ トランスポートの詳細なガイダンスを参照できます。</span><span class="sxs-lookup"><span data-stu-id="71d50-145">The [Microsoft Exchange Server Deployment Assistant](https://go.microsoft.com/fwlink/p/?LinkId=287036) also provides detailed hybrid deployment provisioning and hybrid message transport guidance.</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="71d50-146">機能の可用性</span><span class="sxs-lookup"><span data-stu-id="71d50-146">Feature Availability</span></span>
<span data-ttu-id="71d50-147"><a name="BKMK_hybridmailrouting"> </a></span><span class="sxs-lookup"><span data-stu-id="71d50-147"></span></span>

<span data-ttu-id="71d50-148">Office 365 のプラン、スタンドアロンのオプション、オンプレミス ソリューション全体の機能の可用性を表示するには、「[Exchange Online Protection サービスの説明](exchange-online-protection-service-description.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="71d50-148">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Protection Service Description](exchange-online-protection-service-description.md).</span></span>
  

