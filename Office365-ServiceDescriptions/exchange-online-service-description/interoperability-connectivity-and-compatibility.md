---
title: 相互運用性、接続、および互換性
ms.author: sharik
author: skjerland
manager: mnirkhe
audience: ITPro
ms.topic: reference
f1_keywords:
- exchange-online-interoperability-connectivity-compatibility
ms.service: o365-administration
localization_priority: Normal
ms.custom: Adm_ServiceDesc
ms.assetid: cdfe686d-a059-4f4d-bb8d-9c2c0ebfa423
ms.openlocfilehash: 38ab8f7baf16c5bf837bca9310a0d34a5e25469f
ms.sourcegitcommit: 96dc758c790ddaf05f5c2b836451b417729cf119
ms.translationtype: MT
ms.contentlocale: ja-JP
ms.lasthandoff: 07/18/2019
ms.locfileid: "35776798"
---
# <a name="interoperability-connectivity-and-compatibility"></a><span data-ttu-id="eb3b3-102">相互運用性、接続、および互換性</span><span class="sxs-lookup"><span data-stu-id="eb3b3-102">Interoperability, Connectivity, and Compatibility</span></span>

## <a name="interoperability-with-other-microsoft-products"></a><span data-ttu-id="eb3b3-103">他のマイクロソフト製品との相互運用性</span><span class="sxs-lookup"><span data-stu-id="eb3b3-103">Interoperability with other Microsoft products</span></span>

### <a name="skype-for-business-online"></a><span data-ttu-id="eb3b3-104">Skype for Business Online</span><span class="sxs-lookup"><span data-stu-id="eb3b3-104">Skype for Business Online</span></span>

<span data-ttu-id="eb3b3-105">内部設置型の Microsoft Lync Server 2010、Lync Server 2013、または Microsoft Office Communications Server 2007 R2 を導入されているお客様の場合は、不在時の自動応答メッセージや予定表のデータにアクセスするために、Exchange Web Service を使用することで、Microsoft Office Communicator と Microsoft Exchange Online を接続できます。</span><span class="sxs-lookup"><span data-stu-id="eb3b3-105">For customers who have deployed Microsoft Lync Server 2010, Lync Server 2013 or Microsoft Office Communications Server 2007 R2 on-premises, Microsoft Office Communicator can connect to Microsoft Exchange Online by using Exchange Web Services to access out-of-office messages and calendar data.</span></span>
  
<span data-ttu-id="eb3b3-106">内部設置型の Lync Server 2010 と Lync Server 2013 は、次の 2 つの方法でも Exchange Online と相互運用できます。</span><span class="sxs-lookup"><span data-stu-id="eb3b3-106">On-premises Lync Server 2010 and Lync Server 2013 can interoperate with Exchange Online in two additional ways:</span></span>
  
- <span data-ttu-id="eb3b3-107">Outlook Web App での IM とプレゼンスの相互運用性</span><span class="sxs-lookup"><span data-stu-id="eb3b3-107">IM and presence interoperability in Outlook Web App</span></span>
    
- <span data-ttu-id="eb3b3-108">ボイス メールの相互運用性</span><span class="sxs-lookup"><span data-stu-id="eb3b3-108">Voice mail interoperability</span></span>
    
<span data-ttu-id="eb3b3-p101">Exchange Online を使用するように Skype for Business Server 2015 を設定する方法の詳細については、「[オンプレミスの Skype for Business Server 2015 と Exchange Online の間での統合の構成](https://go.microsoft.com/fwlink/p/?LinkId=271804)」を参照してください。ハイブリッド構成については、「[Skype for Business Server 2015 でサポートされるハイブリッド構成](https://go.microsoft.com/fwlink/?LinkID=513084)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="eb3b3-p101">For more information about how to configure Skype for Business Server 2015 with Exchange Online, see [Configuring On-premises Skype for Business Server 2015 Integration with Exchange Online](https://go.microsoft.com/fwlink/p/?LinkId=271804). For hybrid configurations, see [Supported Skype for Business Server 2015 hybrid configurations](https://go.microsoft.com/fwlink/?LinkID=513084).</span></span>
  
### <a name="microsoft-sharepoint"></a><span data-ttu-id="eb3b3-111">Microsoft SharePoint</span><span class="sxs-lookup"><span data-stu-id="eb3b3-111">Microsoft SharePoint</span></span>

<span data-ttu-id="eb3b3-112">Microsoft SharePoint Server または SharePoint Online を Office 365 加入プランの一部として展開されているお客様は、SharePoint を Exchange Online に接続して統合サービスを実現できます。</span><span class="sxs-lookup"><span data-stu-id="eb3b3-112">For customers who have deployed Microsoft SharePoint Server or SharePoint Online as part of an Office 365 subscription plan, SharePoint can connect to Exchange Online for integrated services.</span></span>
  
<span data-ttu-id="eb3b3-113">SharePoint を Exchange Online に接続する方法の詳細については、「[他の Office 365 サービスを設定している場合に、カスタム ドメイン名を使用して Office 365 の一般向け Web サイトの名前を変更する](https://go.microsoft.com/fwlink/?LinkId=271805)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="eb3b3-113">For more information about connecting SharePoint to Exchange Online, see [Use SharePoint Online on a custom domain together with other services](https://go.microsoft.com/fwlink/?LinkId=271805).</span></span>
  
## <a name="features-for-external-connectivity"></a><span data-ttu-id="eb3b3-114">外部接続のための機能</span><span class="sxs-lookup"><span data-stu-id="eb3b3-114">Features for external connectivity</span></span>

<span data-ttu-id="eb3b3-115">Exchange Online は、外部のアプリケーションおよびデバイスと接続するために次の機能を提供しています。</span><span class="sxs-lookup"><span data-stu-id="eb3b3-115">Exchange Online offers the following features for connecting with external applications and devices:</span></span>
  
- <span data-ttu-id="eb3b3-p102">**MAPI over HTTP、SMTP、POP3、IMAP4、Exchange Web サービスなどのメッセージング プロトコルを使用** 社内、Azure、または他のホステッド サービスで動作している外部アプリケーションは、MAPI over HTTP、SMTP、POP3、IMAPv4 などのメッセージング プロトコルを使用して、Exchange Online によって保存されたデータにアクセスすることができます。アプリケーション開発には、Exchange Web Service または Exchange Web Service マネージ API を使用することをお勧めします。</span><span class="sxs-lookup"><span data-stu-id="eb3b3-p102">**Through messaging protocols such as MAPI over HTTP, SMTP, POP3, IMAP4, or Exchange Web Services** External applications that are running on-premises, in Azure, or in other hosted services can access data stored with Exchange Online by using messaging protocols such as MAPI over HTTP, SMTP, POP3, and IMAPv4. Exchange Web Services or the Exchange Web Services Managed API is recommended for application development.</span></span> 
    
- <span data-ttu-id="eb3b3-118">**SMTP リレーとして** Exchange Online は、ファックス ゲートウェイ、ネットワーク アプライアンス、およびカスタム アプリケーションから送信された電子メール メッセージを中継する SMTP 配信サービスとして設定できます。</span><span class="sxs-lookup"><span data-stu-id="eb3b3-118">**As an SMTP relay** Exchange Online can be set up as an SMTP delivery service to relay email messages sent from fax gateways, network appliances, and custom applications.</span></span> 
    
### <a name="exchange-web-services"></a><span data-ttu-id="eb3b3-119">Exchange Web サービス</span><span class="sxs-lookup"><span data-stu-id="eb3b3-119">Exchange Web Services</span></span>

<span data-ttu-id="eb3b3-p103">Exchange Web Service (EWS) は、Exchange Server および Exchange Online 用に推奨される開発 API です。管理者は EWS または EWS マネージ API を使用して、社内、Azure、またはその他のホステッド サービスで実行されているアプリケーションから Exchange Online によって格納されたデータにアクセスできます。EWS によって、管理者は、メールボックスのコンテンツのクエリ、カレンダー イベントの登録、タスクの作成、電子メール メッセージの内容に基づく特定のアクションのトリガーなど特化したアクションを実行できます。Exchange Online では、顧客アカウントにアプリケーションのアクセス許可を付与することで EWS 機能を有効にできます。これらのアクセス許可によって、顧客のアプリケーションは、アプリケーション メールボックスにアクセスし、コンテンツを追加できます。Exchange の偽装は、アプリケーションのアクセス許可を付与するために使用する方法の 1 つです。Exchange Web Service と Exchange Online を併用する方法の詳細については、Exchange Online デベロッパー センターの技術情報を参照してください。</span><span class="sxs-lookup"><span data-stu-id="eb3b3-p103">Exchange Web Services (EWS) is the preferred development API for Exchange Server and Exchange Online. Using EWS or the EWS Managed API, administrators can access data stored with Exchange Online from applications that are running on-premises, in Azure, or in other hosted services. EWS enables administrators to perform specialized actions, such as querying the contents of a mailbox, posting a calendar event, creating a task, or triggering a specific action based on the content of an email message. Exchange Online enables EWS functionality by granting application permissions to customer accounts. These permissions allow the customer application to access the application mailbox and add content. Exchange Impersonation is one method used to grant application permissions. For details about how to use Exchange Web Services with Exchange Online, refer to the technical articles at the Exchange Online Developer Center.</span></span>
  
### <a name="smtp-relay"></a><span data-ttu-id="eb3b3-127">SMTP リレー</span><span class="sxs-lookup"><span data-stu-id="eb3b3-127">SMTP relay</span></span>

<span data-ttu-id="eb3b3-p104">Exchange Online は、ファックス ゲートウェイ、ネットワーク アプライアンス、およびカスタム アプリケーションから送信された電子メール メッセージを中継する SMTP 配信サービスとして設定できます。たとえば、基幹業務アプリケーションが電子メール アラートをユーザーに送信する場合に、Exchange Online をメール配信システムとして使用するように設定できます。アプリケーションまたはサービスは、有効なライセンスが付与された Exchange Online メールボックスのユーザー名とパスワードで認証を行い、トランスポート層セキュリティ (TLS) を使用して接続する必要があります。</span><span class="sxs-lookup"><span data-stu-id="eb3b3-p104">Exchange Online can be used as an SMTP delivery service to relay email messages sent from fax gateways, network appliances, and custom applications. For example, if a line-of-business application sends email alerts to users, it can be configured to use Exchange Online as the mail delivery system. The application or service must authenticate with the username and password of a valid, licensed Exchange Online mailbox, and connect by using Transport Layer Security (TLS).</span></span>
  
## <a name="feature-availability"></a><span data-ttu-id="eb3b3-131">機能の可用性</span><span class="sxs-lookup"><span data-stu-id="eb3b3-131">Feature Availability</span></span>

<span data-ttu-id="eb3b3-132">Office 365 のプラン、スタンドアロンのオプション、オンプレミス ソリューション全体の機能の可用性を表示するには、「[Exchange Online サービスの説明](exchange-online-service-description.md)」を参照してください。</span><span class="sxs-lookup"><span data-stu-id="eb3b3-132">To view feature availability across Office 365 plans, standalone options, and on-premise solutions, see [Exchange Online Service Description](exchange-online-service-description.md).</span></span>
  

