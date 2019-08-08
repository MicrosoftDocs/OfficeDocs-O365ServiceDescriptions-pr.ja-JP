---
title: メール フロー
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-mail-flow
ms.service: o365-administration
localization_priority: Normal
ms.custom:
- Adm_ServiceDesc
- Adm_ServiceDesc_top
ms.assetid: 8e5267e6-d224-485b-a081-c71a1fd0c4c3
description: Office 365 を使用しているほとんどの組織では、メールボックスをホストし、メールフローを処理します。 Office 365 によってすべてのメールボックスとフィルターを管理するのが最も簡単な構成方法です。 ただし、組織によっては特定の規制や業務上のニーズを満たしていることを保証するためのより複雑なメール フロー セットアップが必要な場合があります。 以下に、こうしたオプションについて記します。
ms.openlocfilehash: a50c85fff3ba023706932f227db1df3915923545
ms.sourcegitcommit: 5b1670c36e256aef7f222951a49a4411afc3bcb6
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 08/07/2019
ms.locfileid: "36231415"
---
# <a name="mail-flow"></a><span data-ttu-id="3d14f-106">メール フロー</span><span class="sxs-lookup"><span data-stu-id="3d14f-106">Mail Flow</span></span>

<span data-ttu-id="3d14f-107">Office 365 を使用しているほとんどの組織では、メールボックスをホストし、メールフローを処理します。</span><span class="sxs-lookup"><span data-stu-id="3d14f-107">For most organizations using Office 365, we host your mailboxes and take care of mail flow.</span></span> <span data-ttu-id="3d14f-108">Office 365 によってすべてのメールボックスとフィルターを管理するのが最も簡単な構成方法です。</span><span class="sxs-lookup"><span data-stu-id="3d14f-108">It's the simplest configuration and means that Office 365 manages all mailboxes and filtering.</span></span> <span data-ttu-id="3d14f-109">ただし、組織によっては特定の規制や業務上のニーズを満たしていることを保証するためのより複雑なメール フロー セットアップが必要な場合があります。</span><span class="sxs-lookup"><span data-stu-id="3d14f-109">However, some organizations need more complex mail flow setups to make sure that they comply with specific regulatory or business needs.</span></span> <span data-ttu-id="3d14f-110">以下に、こうしたオプションについて記します。</span><span class="sxs-lookup"><span data-stu-id="3d14f-110">You can find out about those options here.</span></span> 
  
## <a name="custom-routing-of-outbound-email"></a><span data-ttu-id="3d14f-111">送信電子メールのカスタム ルーティング</span><span class="sxs-lookup"><span data-stu-id="3d14f-111">Custom routing of outbound email</span></span>

<span data-ttu-id="3d14f-p103">Microsoft Exchange Online は、社内サーバーまたはホステッド サービス (「スマート ホスティング」と呼ぶ) を通じて、組織からのメール フローをルーティングできます。この機能により組織は、データ損失防止 (DLP) アプライアンスを使用したり、送信電子メールのカスタムの事後処理を実行したり、プライベート ネットワーク経由でビジネス パートナーに電子メールを送信できます。Exchange Online はアドレス書き換えもサポートします。アドレス書き換え機能により、送信電子メールはアドレスを変更するオンプレミス ゲートウェイを通るようにルーティングされます。この機能により組織は、サブドメインを非公開にしたり、マルチドメイン組織からの電子メールを単一ドメインのように見せかけたり、パートナーからの中継電子メールを組織内部から送信されたように見せかけられます。管理者は、Exchange 管理センター (EAC) でカスタム電子メール ルーティングを構成します。</span><span class="sxs-lookup"><span data-stu-id="3d14f-p103">Microsoft Exchange Online can route mail flowing from your organization through an on-premises server or a hosted service (sometimes called "smart hosting"). This enables your organization to use data loss prevention (DLP) appliances, perform custom post-processing of outgoing email, and deliver email to business partners through private networks. Exchange Online also supports Address Rewrite, which routes outgoing email through an on-premises gateway that modifies the addresses. This feature enables you to hide sub-domains, make email from a multi-domain organization appear as a single domain, or make partner-relayed email appear as if it were sent from inside your organization. Administrators configure custom email routing within the Exchange admin center (EAC).</span></span>
  
<span data-ttu-id="3d14f-117">詳細については、「[Set up connectors to route mail between Office 365 and your own email servers](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="3d14f-117">For more information, see [Set up connectors to route mail between Office 365 and your own email servers](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-to-route-mail).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="3d14f-118">Exchange Online は、組織との間を流れるメールを配信できます。</span><span class="sxs-lookup"><span data-stu-id="3d14f-118">Exchange Online can deliver mail flowing into and out of your organization.</span></span> <span data-ttu-id="3d14f-119">受信者のドメインが、Exchange Online Protection をポイントする DNS MX レコードと共に Exchange Online でホストされている場合、テナントから受信者へのメールフローはインターネット経由で転送されません。</span><span class="sxs-lookup"><span data-stu-id="3d14f-119">If your recipient domain is hosted in Exchange Online with DNS MX records pointing to Exchange Online Protection, mail flow from your tenant to the recipient will not travel over the Internet.</span></span>
  
## <a name="secure-messaging-with-a-trusted-partner"></a><span data-ttu-id="3d14f-120">Secure messaging with a trusted partner</span><span class="sxs-lookup"><span data-stu-id="3d14f-120">Secure messaging with a trusted partner</span></span>

<span data-ttu-id="3d14f-p105">Exchange Online のお客様は、Office 365 コネクタを使用して、信頼できるパートナーとのセキュリティで保護されたメール フローを設定することができます。Office 365 は、トランスポート層セキュリティ (TLS) 経由のセキュリティで保護された通信をサポートします。コネクタを作成して、TLS による暗号化を適用することができます。[TLS](https://docs.microsoft.com/office365/securitycompliance/exchange-online-uses-tls-to-secure-email-connections) は、インターネット上の通信にセキュリティを提供する暗号化プロトコルです。コネクタを使用すると、自己署名証明書または証明機関 (CA) 検証の証明書を使用した受信 TLS と送信 TLS の両方を強制するよう構成できます。パートナー組織のメールの送信元のドメイン名または IP アドレスの範囲を指定するなど、他のセキュリティ制限を適用することもできます。</span><span class="sxs-lookup"><span data-stu-id="3d14f-p105">As an Exchange Online customer, you can set up secure mail flow with a trusted partner by using Office 365 connectors. Office 365 supports secure communication through Transport Layer Security (TLS), and you can create a connector to enforce encryption via TLS. [TLS](https://docs.microsoft.com/office365/securitycompliance/exchange-online-uses-tls-to-secure-email-connections) is a cryptographic protocol that provides security for communications over the Internet. By using connectors, you can configure both forced incoming and outgoing TLS using self-signed or certification authority (CA)-validated certificates. You can also apply other security restrictions, such as specifying domain names or IP address ranges from which your partner organization sends mail.</span></span> 
  
<span data-ttu-id="3d14f-126">詳細については、「[Set up connectors for secure mail flow with a partner organization](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="3d14f-126">For more information, see [Set up connectors for secure mail flow with a partner organization](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/set-up-connectors-for-secure-mail-flow-with-a-partner).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="3d14f-127">CA 検証の証明書が必要な場合があります。</span><span class="sxs-lookup"><span data-stu-id="3d14f-127">A CA-validated certificate may be required.</span></span> 
  
## <a name="conditional-mail-routing"></a><span data-ttu-id="3d14f-128">条件付きメール ルーティング</span><span class="sxs-lookup"><span data-stu-id="3d14f-128">Conditional mail routing</span></span>

<span data-ttu-id="3d14f-p106">コネクタとトランスポート ルールを使用して特定のサイトにメールをルーティングできます。条件に基づいたルーティングでは、特定の条件に基づいてコネクタを選択できます。</span><span class="sxs-lookup"><span data-stu-id="3d14f-p106">You can direct mail to specific sites by using connectors and transport rules. With criteria-based routing, you can choose a connector based on specific conditions.</span></span>
  
<span data-ttu-id="3d14f-131">詳しくは、「[Scenario: Conditional mail routing](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="3d14f-131">For more information, see [Scenario: Conditional mail routing](https://docs.microsoft.com/exchange/mail-flow-best-practices/use-connectors-to-configure-mail-flow/conditional-mail-routing).</span></span>
  
## <a name="incoming-mail-safe-list"></a><span data-ttu-id="3d14f-132">受信メールのセーフ リスト</span><span class="sxs-lookup"><span data-stu-id="3d14f-132">Incoming mail safe list</span></span>

<span data-ttu-id="3d14f-p107">信頼できるパートナーの IP アドレスをセーフ リストに追加して、自分宛てにパートナーから送信されるメッセージにスパム対策フィルター処理を施さないようにすることができます。そのためには、接続フィルターの IP 許可一覧を使います。</span><span class="sxs-lookup"><span data-stu-id="3d14f-p107">You can add a trusted partner's IP address to a safe list to ensure that messages the partner sends to you are not subject to anti-spam filtering. To do this, you can use the connection filter's IP Allow list.</span></span>
  
<span data-ttu-id="3d14f-135">詳細については、「[Configure the connection filter policy](https://docs.microsoft.com/office365/SecurityCompliance/configure-the-connection-filter-policy)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="3d14f-135">For more information, see [Configure the connection filter policy](https://docs.microsoft.com/office365/SecurityCompliance/configure-the-connection-filter-policy).</span></span>
  
## <a name="hybrid-email-routing"></a><span data-ttu-id="3d14f-136">ハイブリッド電子メール ルーティング</span><span class="sxs-lookup"><span data-stu-id="3d14f-136">Hybrid email routing</span></span>

<span data-ttu-id="3d14f-p108">ハイブリッド展開によって、充実した機能の利用、および既存の社内 Microsoft Exchange 組織に対する管理制御をクラウドにまで展開することができます。ハイブリッド トランスポートでは、いずれかの組織の受信者間で送信されたメッセージは、認証、暗号化され、トランスポート層セキュリティ (TLS) を使用して転送され、トランスポート ルール、ジャーナリング、およびスパム対策ポリシーといった Exchange コンポーネントに対して「内部」として表示されます。ハイブリッド トランスポートは、Exchange Server のハイブリッド構成ウィザードを使用して構成します。</span><span class="sxs-lookup"><span data-stu-id="3d14f-p108">A hybrid deployment gives organizations the ability to extend the feature-rich experience and administrative control they have with their existing on-premises Microsoft Exchange organization to the cloud. With hybrid transport, messages sent between recipients in either organization are authenticated, encrypted, and transferred using Transport Layer Security (TLS), and appear as "internal" to Exchange components such as transport rules, journaling, and anti-spam policies. You configure hybrid transport by using the Hybrid Configuration Wizard in Exchange Server.</span></span>
  
<span data-ttu-id="3d14f-140">ハイブリッド展開でのメール ルーティングの詳細については、「[Exchange ハイブリッド展開でのトランスポート ルーティング](https://go.microsoft.com/fwlink/p/?LinkId=271757)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="3d14f-140">For more information about mail routing in a hybrid deployment, see [Transport routing in Exchange hybrid deployments](https://go.microsoft.com/fwlink/p/?LinkId=271757).</span></span>
  
<span data-ttu-id="3d14f-141">「[Microsoft Exchange Server 展開アシスタント](https://go.microsoft.com/fwlink/p/?LinkId=287036)」でも、ハイブリッド展開のプロビジョニングとハイブリッド メッセージ トランスポートの詳細なガイダンスを参照できます。</span><span class="sxs-lookup"><span data-stu-id="3d14f-141">The [Microsoft Exchange Server Deployment Assistant](https://go.microsoft.com/fwlink/p/?LinkId=287036) also provides detailed hybrid deployment provisioning and hybrid message transport guidance.</span></span> 
  
### <a name="shared-address-space-with-on-premises-routing-control-mx-points-to-on-premises"></a><span data-ttu-id="3d14f-142">社内ルーティング制御を使った共有アドレス スペース (MX が社内を指定)</span><span class="sxs-lookup"><span data-stu-id="3d14f-142">Shared Address Space with On-Premises Routing Control (MX Points to On-Premises)</span></span>

<span data-ttu-id="3d14f-p109">社内ルーティング制御を使った共有アドレス スペース (MX が社内を指定) はハイブリッド展開メールルーティング シナリオで、メールボックスの一部が Exchange Online、残りが社内でホストされます。受信および送信インターネット メール フローは社内 Exchange 組織を経由してルーティングされます。このシナリオは、集中型メール トランスポートとも呼びます。このシナリオでは、Exchange Online は EOP とプロビジョニングされ、受信インターネット メールは、EOP および最終的な Exchange Online でホストされるメールボックスにルーティングされる前に、社内メール サーバーにルーティングされます。さらに、Exchange Online メールボックスからの送信メールは、外部受信者宛てに送信されたメッセージ用の社内 Exchange 組織を通じてルーティングされます。この構成では、社内 Exchange 組織と Exchange Online 組織の両方に含まれるすべてのメールボックスに、単一の SMTP ドメイン名前空間を使用できます。</span><span class="sxs-lookup"><span data-stu-id="3d14f-p109">Shared Address Space with On-Premises Routing Control (MX Points to On-Premises) is a hybrid deployment mail-routing scenario in which your mailboxes are hosted partially in Exchange Online and partially on-premises, and incoming and outgoing Internet mail flow is routed through the on-premises Exchange organization. This scenario is also called centralized mail transport. In this scenario, Exchange Online is provisioned with EOP and incoming Internet mail is routed to your on-premises mail server before being routed to EOP and finally to mailboxes hosted in Exchange Online. Additionally, outgoing mail from Exchange Online mailboxes is routed through the on-premises Exchange organization for messages sent to external recipients. With this configuration, you can use a single SMTP domain namespace for all mailboxes in both your on-premises Exchange organization and your Exchange Online organization.</span></span> 
  
<span data-ttu-id="3d14f-148">ハイブリッド展開でのトランスポート オプションの詳細については、「[Exchange ハイブリッド展開でのトランスポート オプション](https://go.microsoft.com/fwlink/p/?LinkID=271758)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="3d14f-148">For more information about transport options in a hybrid deployment, see [Transport options in Exchange hybrid deployments](https://go.microsoft.com/fwlink/p/?LinkID=271758).</span></span>
  
### <a name="shared-address-space-without-on-premises-routing-control-mx-points-to-eop"></a><span data-ttu-id="3d14f-149">社内ルーティング制御を使わない共有アドレス スペース (MX が EOP を指定)</span><span class="sxs-lookup"><span data-stu-id="3d14f-149">Shared Address Space without On-Premises Routing Control (MX Points to EOP)</span></span>

<span data-ttu-id="3d14f-p110">社内ルーティング制御を使わない共有アドレス スペース (MX が EOP を指定) はハイブリッド展開メールルーティング シナリオで、メールボックスの一部が Exchange Online を使用したクラウド、残りが社内でホストされます。MX レコードは EOP をポイントします。Office 365 サービスを使用して組織の一部のメールボックスをホストし、EOP を使用して社内メールボックスとクラウド メールボックスの両方を保護する場合、このシナリオが適しています。このシナリオでは、組織内の受信者に送信されたメールは最初に EOP を経由してルーティングされます。EOP でスパムおよびポリシーのフィルタリングが行われ、その後、社内メールボックスおよびクラウド メールボックスに転送されます。</span><span class="sxs-lookup"><span data-stu-id="3d14f-p110">Shared Address Space without On-Premises Routing Control (MX Points to EOP) is a hybrid mail-routing scenario in which your mailboxes are hosted partially in the cloud using Exchange Online and partially on-premises, and your MX record points to EOP. This scenario is appropriate when you use the Office 365 service to host some of your organization's mailboxes and you want EOP to protect both your on-premises and cloud mailboxes. In this scenario, mail sent to recipients within your organization is initially routed through EOP, where spam and policy filtering occurs, before it reaches your on-premises mailboxes and cloud mailboxes.</span></span> 
  
<span data-ttu-id="3d14f-153">ハイブリッド展開でのトランスポート オプションの詳細については、「[Exchange ハイブリッド展開でのトランスポート オプション](https://go.microsoft.com/fwlink/p/?LinkID=271758)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="3d14f-153">For more information about transport options in a hybrid deployment, see [Transport options in Exchange hybrid deployments](https://go.microsoft.com/fwlink/p/?LinkID=271758).</span></span>
  
### <a name="troubleshooting-a-deployment-with-the-hybrid-configuration-wizard"></a><span data-ttu-id="3d14f-154">ハイブリッド構成ウィザードでの展開のトラブルシューティング</span><span class="sxs-lookup"><span data-stu-id="3d14f-154">Troubleshooting a deployment with the Hybrid Configuration Wizard</span></span>

<span data-ttu-id="3d14f-p111">ハイブリッド構成ウィザードを使用して Microsoft Exchange Server でハイブリッド展開を構成すると、ハイブリッド展開で問題が発生する可能性が大幅に低下します。ただし構成を誤った場合、ハイブリッド構成ウィザードの範囲外に、ハイブリッド展開で問題が発生する可能性がある一般的な領域がいくつかあります。このような領域には、クライアント アクセス サーバーの適切な構成、および証明書の適切なインストールと構成があります。</span><span class="sxs-lookup"><span data-stu-id="3d14f-p111">Using the Hybrid Configuration Wizard to configure a hybrid deployment in Microsoft Exchange Server greatly minimizes the potential that the hybrid deployment will experience problems. However, there are some typical areas outside the scope of the Hybrid Configuration Wizard that, if misconfigured, may present problems in a hybrid deployment. These include proper Client Access server configuration and proper certificate installation and configuration.</span></span>
  
<span data-ttu-id="3d14f-158">ハイブリッド構成ウィザードによる展開のトラブルシューティングの詳細については、「[ハイブリッド展開のトラブルシューティング](https://go.microsoft.com/fwlink/p/?LinkId=271040)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="3d14f-158">For more information about troubleshooting a deployment with the Hybrid Configuration Wizard, see [Troubleshoot a hybrid deployment](https://go.microsoft.com/fwlink/p/?LinkId=271040).</span></span>
  
### <a name="managing-a-hybrid-configuration"></a><span data-ttu-id="3d14f-159">ハイブリッド構成の管理</span><span class="sxs-lookup"><span data-stu-id="3d14f-159">Managing a hybrid configuration</span></span>

<span data-ttu-id="3d14f-p112">ハイブリッド構成ウィザードで設定を変更することにより、既存のハイブリッド構成を変更できます。シナリオには、集中型トランスポートを無効にするシナリオ、またはセキュリティで保護されたメール トランスポートを無効にするシナリオがあります。</span><span class="sxs-lookup"><span data-stu-id="3d14f-p112">You can modify an existing hybrid configuration by changing settings in the Hybrid Configuration Wizard. Scenarios include disabling centralized transport or disabling secure mail transport.</span></span>
  
<span data-ttu-id="3d14f-162">ハイブリッド展開の構成の管理の詳細については、「[ハイブリッド展開の管理](https://go.microsoft.com/fwlink/p/?LinkId=271044)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="3d14f-162">For more information about managing a hybrid deployment configuration, see [Manage a hybrid deployment](https://go.microsoft.com/fwlink/p/?LinkId=271044).</span></span>
  
### <a name="hybrid-deployment-requirements"></a><span data-ttu-id="3d14f-163">ハイブリッド展開の要件</span><span class="sxs-lookup"><span data-stu-id="3d14f-163">Hybrid deployment requirements</span></span>

<span data-ttu-id="3d14f-164">ハイブリッド展開の前提条件の詳細については、「[ハイブリッド展開の前提条件](https://go.microsoft.com/fwlink/p/?LinkId=271759)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="3d14f-164">For more information about hybrid deployment requirements, see [Hybrid deployment prerequisites](https://go.microsoft.com/fwlink/p/?LinkId=271759).</span></span>
  
> [!IMPORTANT]
> <span data-ttu-id="3d14f-165">一部のハイブリッド構成では、社内メールボックス用に Exchange Online Protection ライセンスの購入が必要となる場合があります。</span><span class="sxs-lookup"><span data-stu-id="3d14f-165">In some hybrid configurations, you may need to purchase Exchange Online Protection licenses for your on-premises mailboxes.</span></span> 
  
## <a name="feature-availability"></a><span data-ttu-id="3d14f-166">機能の可用性</span><span class="sxs-lookup"><span data-stu-id="3d14f-166">Feature Availability</span></span>

<span data-ttu-id="3d14f-167">Office 365 のプラン、スタンドアロンのオプション、オンプレミス ソリューション全体の機能の可用性を表示するには、「[Exchange Online サービスの説明](exchange-online-service-description.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="3d14f-167">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see the [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  